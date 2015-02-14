## 3. Стандартные переменные ##

### 3.1. Пути ###
#### 3.1.1. Активный шаблон ####
В кофиге:
```
$config['path']['static']['skin']     = '___path.static.root___/templates/skin/___view.skin___';
```
Для Smarty:
```smarty
{cfg name='path.static.skin'}
```

# [zxc](#zxxc)

### 3.2. Шаблон ###
### 3.2.1. Canonical URL ###
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

### 3.2.2. CSS-файлы ###
CSS-файлы из плагинов.
Smarty:
```smarty
{$aHtmlHeadFiles.css}
```

### 3.2.3. JS-файлы ###
JS-файлы из плагинов.
Smarty:
```smarty
{$aHtmlHeadFiles.js}
```

### 3.3. Hooks для шаблона ###
#### 3.3.1. Тег `<head>` ####
 * Сразу после начала тега 
```smarty
{hook run='html_head_begin'}
```
 * Сразу перед окончанием тега
```smarty
{hook run='html_head_end'}
```

#### 3.3.1. Тег `<body>` ####
 * Сразу после начала тега 
```smarty
{hook run='body_begin'}
```
 * Сразу перед окончанием тега
```smarty
{hook run='body_end'}
```

###  <a name="zxxc"></a>3.4. Переменные языка ###
Переменные языка находятся в масиве ``$aLang``. ``[item]`` надо заменить на нужную переменную.
```smarty
{$aLang.[item]}
```

#### 3.4.1. Поиск ####
 * Текс из поля поиска
```smarty
{$aLang.search}
```
 * Текст кнопки поиска
```smarty
{$aLang.search_submit}
```
