# DAO (3.4.0)

## Actions
### Ajax
* ``protected RegisterEvent()``
* ``public EventAjaxDaoChangeOrder()``
* ``public EventAjaxDaoChangeOrderProperties()``
* ``public EventAjaxDaoChangeOrderCategories()``
* ``public EventAjaxLoadDao()``
* ``protected EventPreviewText()``
* ``public Init()``
* ``protected EventInfoboxInfoBlog()``
* ``protected EventGeoGetRegions()``
* ``protected EventGeoGetCities()``
* ``protected EventVoteComment()``
* ``protected EventVoteTopic()``
* ``protected EventVoteBlog()``
* ``protected EventVoteUser()``
* ``protected EventVoteQuestion()``
* ``protected EventFavouriteSaveTags()``
* ``protected EventFavouriteTopic()``
* ``protected EventFavouriteComment()``
* ``protected EventFavouriteTalk()``
* ``protected EventStreamComment()``
* ``protected EventStreamTopic()``
* ``protected EventBlogsTop()``
* ``protected EventBlogsSelf()``
* ``protected EventBlogsJoin()``
* ``protected EventPreviewTopic()``
* ``protected EventUploadImage()``
* ``protected EventAutocompleterTag()``
* ``protected EventAutocompleterUser()``
* ``protected EventCommentDelete()``
* ``public __construct(Engine $oEngine, $sAction)``
* ``protected AddEvent($sEventName, $sEventFunction)``
* ``protected AddEventPreg()``
* ``public ExecEvent()``
* ``public SetDefaultEvent($sEvent)``
* ``public GetDefaultEvent()``
* ``protected GetEventMatch($iItem)``
* ``protected GetParamEventMatch($iParamNum, $iItem)``
* ``public GetParam($iOffset, $default)``
* ``public GetParams()``
* ``public SetParam($iOffset, $value)``
* ``protected SetTemplate($sTemplate)``
* ``protected SetTemplateAction($sTemplate)``
* ``public GetTemplate()``
* ``public GetActionClass()``
* ``public GetCurrentEventName()``
* ``protected EventNotFound()``
* ``public EventShutdown()``
* ``public __call($sName, $aArgs)``
