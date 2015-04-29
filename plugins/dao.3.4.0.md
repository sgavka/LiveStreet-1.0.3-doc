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

### Dao
* ``public Init()``
* ``protected RegisterEvent()``
* ``public EventSearch()``
* ``protected EventFilter()``
* ``protected BuildFilter($iPage, $bPaging)``
* ``protected EventCompare()``
* ``protected EventModerate()``
* ``protected EventItem()``
* ``protected EventAjaxItem()``
* ``protected EventTag()``
* ``protected EventMap()``
* ``protected EventCategories()``
* ``protected EventCatalog()``
* ``protected EventCatblocks()``
* ``protected EventRssCategory()``
* ``protected EventByUser()``
* ``protected EventAdd()``
* ``protected SubmitAdd()``
* ``public Notify($oItem)``
* ``protected EventEdit()``
* ``protected SubmitAudioEdit($oItem, $oCategory)``
* ``protected SubmitVideoEdit($oItem, $oCategory)``
* ``protected SubmitEdit($oItem)``
* ``protected VideoAdd()``
* ``protected AudioAdd()``
* ``protected SubmitAudioAdd()``
* ``protected SubmitVideoAdd()``
* ``protected SubmitSeo($oItem)``
* ``protected SubmitBranding($oItem)``
* ``protected EventDelete()``
* ``public EventDeleteImg()``
* ``public EventUploadImg()``
* ``public EventUpload()``
* ``protected EventDownloadFile()``
* ``protected EventMusicload()``
* ``protected EventDeleteFile()``
* ``protected LinkFiles($aFiles, $oItem)``
* ``protected LinkLinks($aLinks, $oItem)``
* ``protected LinkPhotos($aPhotos, $oItem)``
* ``protected LinkShedule($item_from_id, $item_to_id, $aShedule)``
* ``protected LoadComments($oItem, $isAjax, $oViewer)``
* ``protected EventAjaxAddFavourite()``
* ``protected EventAjaxAddCompare()``
* ``protected EventAjaxEditFile()``
* ``protected EventAjaxEditPhoto()``
* ``protected EventAjaxTagAutoCompleter()``
* ``protected EventAjaxProducerAutoCompleter()``
* ``protected EventAjaxCityAutoCompleter()``
* ``protected EventCatalogFavourite()``
* ``protected EventNotpublished()``
* ``protected EventEditable()``
* ``protected EventPublished()``
* ``protected EventOverdue()``
* ``protected UpdateTags($oItem)``
* ``protected AjaxResponseComment()``
* ``protected AjaxAddComment()``
* ``protected SubmitComment()``
* ``public EventAjaxBlockStreamItems()``
* ``protected checkTags($sTags)``
* ``protected checkItemFields($oCategory)``
* ``public EventAjaxTitleSearch()``
* ``protected EventAjaxVoteItem()``
* ``public EventAjaxEditors()``
* ``public EventAjaxOnvideo()``
* ``protected EventDopayment()``
* ``protected EventPayment()``
* ``protected LoadLinksToItem($oItem)``
* ``public GetShedule($aItems)``
* ``protected LoadLinks($oItem)``
* ``protected LoadDate()``
* ``public EventShutdown()``
* ``protected EventFrame()``
* ``protected AddDaoBlocks($aParams)``
* ``public EventUpdateCounts()``
* ``protected getSort($aFilter, $prefix)``
* ``protected wordtodate()``
* ``public getTemplatePathPlugin()``
* ``public setTemplatePathPlugin($sTemplatePath)``
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
* ``public __call($sName, $aArgs)``

### DaoAdmin

* ``public Init()``
* ``protected RegisterEvent()``
* ``protected EventAdminLinks()``
* ``protected EventAdminCategories()``
* ``protected EventAdminProperties()``
* ``protected EventAdminItemlist()``
* ``protected EventAdminNotpublished()``
* ``protected EventAdminModeration()``
* ``protected EventAdminNewTypes()``
* ``protected EventAdminNew()``
* ``protected SubmitAdd()``
* ``protected EventAdminEdit()``
* ``protected SubmitEdit($oCatalogNew)``
* ``protected checkCatFields($add)``
* ``protected checkCategoryFields($add)``
* ``protected checkPropFields($add)``
* ``protected checkLinksFields($add)``
* ``protected UpdateLinkList()``
* ``protected UpdateAllCounts()``
* ``protected EventAdminDelete()``
* ``protected SubmitDelete($oCatalog)``
* ``protected EventAdminSheduleimport()``
* ``public EventShutdown()``
* ``public getTemplatePathPlugin()``
* ``public setTemplatePathPlugin($sTemplatePath)``
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
* ``public __call($sName, $aArgs)``

### Profile
* ``protected RegisterEvent()``
* ``protected EventDaoObjects()``
* ``public EventFavouriteDao()``
* ``public EventShutdown()``
* ``protected EventForumTopics()``
* ``protected EventForumPosts()``
* ``public Init()``
* ``protected CheckUserProfile()``
* ``protected EventStream()``
* ``protected EventFriends()``
* ``protected EventCreatedTopics()``
* ``protected EventCreatedComments()``
* ``protected EventFavourite()``
* ``protected EventFavouriteTopicsTag()``
* ``protected EventFavouriteComments()``
* ``protected EventWhois()``
* ``public EventWall()``
* ``public EventWallAdd()``
* ``public EventWallRemove()``
* ``public EventWallLoad()``
* ``public EventWallLoadReply()``
* ``public EventAjaxNoteSave()``
* ``public EventAjaxNoteRemove()``
* ``public EventCreatedNotes()``
* ``public EventFriendOffer()``
* ``public EventAjaxFriendAccept()``
* ``protected NoticeFriendOffer($oUser, $sAction)``
* ``public EventAjaxFriendAdd()``
* ``protected GetViewerLocal()``
* ``protected SubmitAddFriend($oUser, $sUserText, $oFriend)``
* ``public EventAjaxFriendDelete()``
* ``public EventChangemailConfirmFrom()``
* ``public EventChangemailConfirmTo()``
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
* ``public __call($sName, $aArgs)``

## Modules
### Advertisement
#### Module
##### Entities
##### Mappers

### Catalog
#### Module
* ``public Init()``
* ``public AddType($sType, $aParams)``
* ``public GetPluginByCatalogType($sType)``
* ``public LoadItemsByJoin($aFilter, $aFilterCat, $idCatalog)``
* ``public searchByParams($aFilter, $aFilterProps, $idCatalog)``
* ``public GetPriceSetInfo($sSum, $oCatalog, $oItem, $oOrder)``
* ``public GetPriceCartSetInfo($sSum, $oCatalog, $oOrder)``
* ``public setItemStat($oItem, $oCatalog, $sType)``
* ``public UploadItemPhoto($aFile)``
* ``public UploadPhoto($aFile, $oItem, $sType, $hash, $formid)``
* ``public UploadLinkPhoto($sUrl, $oItem, $hash, $formid)``
* ``public UploadManualVideoPreviewPhoto($aFile, $oItem, $hash, $formid)``
* ``public ACLIsAllowDeleteItem($oItem, $oUserCurrent, $oCatalog)``
* ``public ACLAllowAddItem($oCatalog, $oUser)``
* ``public ACLAllowEditItem($oItem, $oUserCurrent)``
* ``public ACLAllowShowItem($oItem, $oCatalog, $oUserCurrent)``
* ``public ACLCanVoteItem(ModuleUser_EntityUser $oUser, $oItem, $oCatalog)``
* ``public GetCategoryFilter($iCategoryId)``
* ``public GetFavouriteItem($sItemId, $sUserId, $oCatalog)``
* ``public AddFavouriteItem(ModuleFavourite_EntityFavourite $oFavouriteItem)``
* ``public DeleteFavouriteItem(ModuleFavourite_EntityFavourite $oFavouriteItem)``
* ``public GetItemsFavouriteByUserId($sUserId, $oCatalog, $iCurrPage, $iPerPage)``
* ``public GetCountItemsFavouriteByUserId($sUserId, $oCatalog)``
* ``public GetPriceCategory($oCategory, $type)``
* ``public GetPropMinMax($oProp, $oCategory)``
* ``public GetProducersByCategory($oCategory)``
* ``public GetItemTagsByLike($sTag, $iLimit, $idCatalog)``
* ``public GetItemCityByLike($sTag, $iLimit, $idCatalog)``
* ``public ItemProducersByLike($sTag, $iLimit, $idCatalog)``
* ``public GetItemProducers($iLimit, $idCatalog)``
* ``public GetItemCities($iLimit, $idCatalog)``
* ``public GetItemTags($iLimit, $idCatalog)``
* ``public GetItemsByTag($sTag, $iCount, $iPage, $iPerPage, $idCatalog)``
* ``public GetGroupPrefixItems($aFilter, $iPrefixLength)``
* ``public VoteItem(ModuleUser_EntityUser $oUser, PluginDao_ModuleCatalog_EntityCatalogItem $oItem, $oCatalog, $iValue)``
* ``public ItemReadUpdate($oItemRead)``
* ``public ItemReadAdd($oItemRead)``
* ``public adminCategoriesListCount($oCatalog, $iModer)``
* ``public updateCategoryCount($aUpdate)``
* ``public convertSec($time)``
* ``public ArrayListExtension($aList)``
* ``public readfileChunked($filename)``
* ``public AddEnumField($sCatalog, $bBlog)``
* ``public kav($ar)``
* ``public getv($n)``
* ``private getcd($n)``
* ``public getcn($n)``
* ``public getLicenceInfo()``
* ``public GetWithTypes($sType, $oCatalog)``
* ``public GetProfilePreg()``
* ``public MakeFriendlyUrl($sItemTitle, $sItemId, $oCatalog)``
* ``public extTransLiteration($sStr, $nLen)``
* ``public getCatalogsToLinkTopic($iTypeId)``
* ``public SwitchKeyboard($text)``
* ``public ConvertGeoData()``
* ``public GetGeoCityId($iCityId)``
* ``public GetItemBlogIds($oUser)``
* ``public DelItem($sItemId, $oCatalog)``
* ``protected UpdateCatalogCounter($oCatalog)``
* ``public UpdateCounts()``
* ``protected _LoadMapperORM()``
* ``protected _AddEntity($oEntity)``
* ``protected _UpdateEntity($oEntity)``
* ``protected _SaveEntity($oEntity)``
* ``protected _DeleteEntity($oEntity)``
* ``protected _ReloadEntity($oEntity)``
* ``protected _ShowColumnsFrom($oEntity)``
* ``protected _ShowPrimaryIndexFrom($oEntity)``
* ``protected _GetChildrenOfEntity($oEntity)``
* ``protected _GetParentOfEntity($oEntity)``
* ``protected _GetAncestorsOfEntity($oEntity)``
* ``protected _GetDescendantsOfEntity($oEntity)``
* ``public LoadTree($aFilter, $sEntityFull)``
* ``public GetByFilter($aFilter, $sEntityFull)``
* ``public GetItemsByFilter($aFilter, $sEntityFull)``
* ``protected _setIndexesFromField($aEntities, $aFilter)``
* ``public GetCountItemsByFilter($aFilter, $sEntityFull)``
* ``public GetItemsByArray($aFilter, $sEntityFull)``
* ``public GetItemsByJoinTable($aJoinData, $sEntityFull)``
* ``public GetCountItemsByJoinTable($aJoinData, $sEntityFull)``
* ``public __call($sName, $aArgs)``
* ``static public buildTree($aItems, $aList, $iLevel)``
* ``protected _updateManyToManySet($aRelation, $aRelationData, $iEntityId)``
* ``protected _deleteManyToManySet($sDbTableAlias, $sEntityKey, $iEntityId)``
* ``public __construct(Engine $oEngine)``
* ``protected __clone()``
* ``public Shutdown()``
* ``public isInit()``
* ``public SetInit()``

##### Entities
###### CatalogCategory
* ``public getMarker()``
* ``public getCountObjects()``
* ``public getCountChildrenObjects($aList)``
* ``public getFullUrl()``
* ``public getChildrensOneLevel()``
* ``public getChildrensOneLevelTree()``
* ``public getParentProps($all, $getobj)``
* ``public getAvatarPath($sWidth)``
* ``public getPriceMin()``
* ``public getPriceMax()``
* ``public getStep()``
* ``public getCategoryChildrensArrayIds()``
* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

###### CatalogCategoryJoin
* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

###### CatalogFile

* ``public getSizeFormat()``
* ``public getMediaHash()``
* ``public getAllowDownload($oCatalog, $oUserCurrent)``
* ``public getFileFullPath()``
* ``protected extractMetaData()``
* ``public getMetaData($type)``
* ``public detect_enc($string)``
* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

###### CatalogItem

* ``public getLastTopics($iCount)``
* ``public getBlog()``
* ``public getTagsArray()``
* ``public getPhotosList()``
* ``public getIsPay()``
* ``public getFavouriteUsers()``
* ``public getItemDateStartStamp()``
* ``public getItemDateEndStamp()``
* ``public getIsMultiday()``
* ``public getIsFavourite()``
* ``public getAllowEdit()``
* ``public getVote()``
* ``public getItemVideoCode()``
* ``public getSite()``
* ``public getItemPriceNoFormat()``
* ``public getItemPrice()``
* ``public getItemPriceFormat()``
* ``public getItemPricePrefix($oCatalog)``
* ``public getEditors()``
* ``public getEditorsList()``
* ``public getUsersOnvideo()``
* ``public getUsersOnvideoList()``
* ``public getUrl()``
* ``public getPhotoPath($sWidth, $type)``
* ``public getAllowDownload($oCatalog)``
* ``public getRating()``
* ``protected getReadObj()``
* ``public getSubscribeNewComment()``
* ``public getDateReadLast()``
* ``public getCountCommentNew()``
* ``public getIsCart()``
* ``public getIsCompare()``
* ``public getDescription()``
* ``public getKeywords()``
* ``public getItemExtraProp()``
* ``protected extractExtra()``
* ``public getExtraField($id)``
* ``public setExtraField($oPropObj, $data)``
* ``public cleanExtra()``
* ``public getItemExtraSelf()``
* ``public getItemExtraValue($num)``
* ``protected extractExtraSelf()``
* ``public setItemExtraValue($num, $data)``
* ``public setExtraSelf($data)``
* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

###### CatalogItemAcl

* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

###### CatalogItemJoin

* ``public __construct($aParam)``
* ``public _getPrimaryKey()``
* ``public _getPrimaryKeyValue()``
* ``public _isNew()``
* ``public _SetIsNew($bIsNew)``
* ``public Add()``
* ``public Update()``
* ``public Save()``
* ``public Delete()``
* ``public Reload()``
* ``public ShowColumns()``
* ``public ShowPrimaryIndex()``
* ``protected beforeSave()``
* ``protected afterSave()``
* ``protected beforeDelete()``
* ``protected afterDelete()``
* ``public getChildren()``
* ``public getDescendants()``
* ``public getParent()``
* ``public getAncestors()``
* ``public setChildren($aChildren)``
* ``public setDescendants($aDescendants)``
* ``public setParent($oParent)``
* ``public setAncestors($oParent)``
* ``protected _Method($sName)``
* ``public _setData($aData)``
* ``public _getOriginalData()``
* ``public _getFields()``
* ``public _getField($sField, $iPersistence)``
* ``public _getRelations()``
* ``public _getRelationsData()``
* ``public _setRelationsData($aData)``
* ``public __call($sName, $aArgs)``
* ``public __get($sName)``
* ``public resetRelationsData($sKey)``
* ``public Init()``
* ``public _getData($aKeys)``
* ``public _getDataOne($sKey)``
* ``public _getDataArray()``
* ``public _Validate($aFields, $bClearErrors)``
* ``public _getValidators($sField)``
* ``public _createValidators()``
* ``public _hasValidateErrors($sField)``
* ``public _getValidateErrors($sField)``
* ``public _getValidateError($sField)``
* ``public _addValidateError($sField, $sError)``
* ``public _clearValidateErrors($sField)``
* ``public _getValidateScenario()``
* ``public _setValidateScenario($sValue)``

##### Mappers

### Advertisement
#### Module
##### Entities
##### Mappers
