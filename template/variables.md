## Стандартные переменные ##

### 1. Пути ###
#### 1.1. Активный шаблон ####
В кофиге:
```
$config['path']['static']['skin']     = '___path.static.root___/templates/skin/___view.skin___';
```
Для Smarty:
```smarty
{cfg name='path.static.skin'}
```

### 2. Шаблон ###
### 2.1. Canonical URL ###
Smarty:
```smarty
{$sHtmlCanonical}
```
Пример:
```html
{if $sHtmlCanonical}
    <link rel="canonical" href="{$sHtmlCanonical}" />
{/if}
```

### 2.2. CSS-файлы ###
CSS-файлы из плагинов.
Smarty:
```smarty
{$aHtmlHeadFiles.css}
```

### 2.3. JS-файлы
JS-файлы из плагинов.
Smarty:
```smarty
{$aHtmlHeadFiles.js}
```

### 2.4. Зона для блоков
Задаём динамическую зону для блоков. Тоесть тут вместо ``$group`` должно быть название зоны. Выносим это в отдельный файл.

Файл **blocks.tpl**:
```smarty
{get_blocks assign='aBlocksLoad'}

{if isset($aBlocksLoad.$group)}
	{foreach from=$aBlocksLoad.$group item=aBlock}
		{if $aBlock.type=='block'}
			{insert name="block" block=$aBlock.name params=$aBlock.params}
		{/if}
		{if $aBlock.type=='template'}
			{include file=$aBlock.name params=$aBlock.params}
		{/if}
	{/foreach}
{/if}
```

И подключаем зоны для блоков, где они нужны:
```smarty
{include file='blocks.tpl' group='zone_name'}
```
Параметр group передаётся в blocks.tpl, это -- название зоны.

### 3. Hooks для шаблона ###
#### 3.1. Тег `<head>` ####
 * Сразу после начала тега 
```smarty
{hook run='html_head_begin'}
```
 * Сразу перед окончанием тега
```smarty
{hook run='html_head_end'}
```

#### 3.2. Тег `<body>` ####
 * Сразу после начала тега 
```smarty
{hook run='body_begin'}
```
 * Сразу перед окончанием тега
```smarty
{hook run='body_end'}
```

### 4. Языковые переменные ###
Переменные языка находятся в масиве ``$aLang``. ``[item]`` надо заменить на нужную переменную.
```smarty
{$aLang.[item]}
```

#### 4.1. Поиск ####
 * Текс из поля поиска
```smarty
{$aLang.search}
```
 * Текст кнопки поиска
```smarty
{$aLang.search_submit}
```
