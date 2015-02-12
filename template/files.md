## 2. Список файлов шаблонов ##

### 2.1. Файлы в корне шаблона [(док.)](http://docs.livestreetcms.com/template/1.0/) ###

| Название файла | Описание |
| -------------------------|---------------|
| blocks.tpl(#2_1_footer_tpl) | Вывод блоков |
| blog_list.tpl(#2_2_footer_tpl) | Вывод всех блогов на странице /blogs |
| comment.tpl(#2_3_footer_tpl) | Вывод комментариев |
| comment_list.tpl(#2_4_footer_tpl) | Список комментариев расположенный на странице /my/логин/comment/ |
| comment_paging.tpl(#2_5_footer_tpl) | Пагинация комментариев |
| comment_tree.tpl(#2_6_footer_tpl) | Шапка комментариев и форма добавления |
| [footer.tpl](#2_7_footer_tpl) | Вывод футера и окончание конструкции сайта |
| [header.tpl](#2_8_header_tpl) | Начало конструкции сайта |
| header_top.tpl | Шапка на основных страницах сайта |
| menu.blog.tpl | Меню, выводящееся на странице блогов, главной |
| menu.blog_edit.tpl | Меню, выводящееся на странице редактирования блога |
| menu.create.tpl | Меню, выводящееся на странице добавления топика |
| menu.people.tpl | Меню, выводящееся на странице «Люди» |
| menu.profile_created.tpl | Меню, выводящееся на странице профиля пользователя |
| menu.profile_favourite.tpl | Меню избранного, выводящееся на странице профиля пользователя |
| menu.settings.tpl | Меню, выводящееся на странице настроек профиля |
| menu.stream.tpl | Меню, выводящееся на странице активности |
| menu.talk.tpl | Меню, выводящееся на странице личных сообщений |
| nav.tpl | Меню навигации под шапкой |
| nav_content.tpl | Код общего вывода всех меню |
| paging.tpl | Пагинация топиков, людей, блогов |
| question_result.tpl | Вывод самих результатов голосования |
| sidebar.tpl | Общий вывод правого блока |
| statistics_performance.tpl | Статистика сайта, расположеная в самом низу сайта для администратора |
| system_message.tpl | Системные сообщения такие как: ошибки |
| toolbar.tpl | Вывод дополнительных кнопок, находящихся прижатыми справа экрана |
| toolbar_admin.tpl | Вывод кнопки админ-панели в блоке toolbar |
| toolbar_comment.tpl | Вывод кнопки обновления комментариев в блоке toolbar на полной странице топика |
| toolbar_scrollup.tpl | Вывод кнопки «Вверх» в блоке toolbar |
| toolbar_topic.tpl | Вывод кнопок перемещения по топикам в блоке toolbar |
| topic.tpl | Общий вывод топиков |
| topic_link.tpl | Вывод топика-ссылки |
| topic_list.tpl | Общий вывод краткого топика |
| topic_part_footer.tpl | Общий вывод окончания топика |
| topic_part_header.tpl | Общий вывод начала топика |
| topic_photoset.tpl | Вывод топиков-фотосетов |
| topic_preview.tpl | Вывод предпросмотра топика |
| topic_question.tpl | Вывод топиков-вопросов |
| topic_topic.tpl | Вывод полного и краткого топика |
| topic_topic.tpl | Вывод полного и краткого топика |
| user_list.tpl | Вывод полного списка пользователей |
| user_list_avatar.tpl | Вывод списка пользователей по аватаркам |
| window_favourite_form_tags.tpl | Всплывающее окно для добавления своих тегов к избранному топику |
| window_load_img.tpl | Всплывающее окно загрузки изображений |
| window_login.tpl | Всплывающее окно авторизации |
| window_write.tpl | Всплывающее окно выбора вида топика перед его добавлением |

<a id="2_7_footer_tpl"></a>
#### footer.tpl ####


<a id="2_8_header_tpl"></a>
#### header.tpl ####
Минимальная структура:
```html
<!DOCTYPE html>
<html lang="ru">
<head>
    {hook run='html_head_begin'}

    <!-- meta -->
    <title>{$sHtmlTitle}</title>
    <meta name="description" content="{$sHtmlDescription}">
    <meta name="keywords" content="{$sHtmlKeywords}">

    {$aHtmlHeadFiles.css}

    <link href="{cfg name='path.static.skin'}/css/main.css" rel="stylesheet"></link>

    <link href="{cfg name='path.static.skin'}/img/favicon.png" rel="icon">
    {if $sHtmlCanonical}
        <link rel="canonical" href="{$sHtmlCanonical}" />
    {/if}

    {$aHtmlHeadFiles.js}

    <script src="{cfg name='path.static.skin'}/js/jquery.js"></script>

    {hook run='html_head_end'}
</head>
<body>

```

{hook run='html_head_begin'} -- 