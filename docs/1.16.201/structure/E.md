# E
### `ExternalServer`
Offset | Type | Name
-|-|-|-
0 | (48) `AsynchronousIPResolver` | mFutureIP
48 | (4) `int` | mId
52 | (4) `int` | mPort
56 | (4) `int` | mProtocol
60 | (4) `int` | mPlayers
64 | (4) `int` | mMaxPlayers
72 | (32) `std::string` | mName
104 | (32) `std::string` | mTitle
136 | (32) `std::string` | mVersion
168 | (32) `std::string` | mAddress
200 | (8) `__int64` | mLastAccessedTime


### `EducationEditionOfferValue`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mValue


### `ElkLogHandler`
Offset | Type | Name
-|-|-|-
0 | (8) `ElkLogHandler_vtbl *` | __vftable
8 | (32) `std::string` | mElkUrl
40 | (32) `std::string` | mProduct
72 | (32) `std::string` | mType
104 | (32) `std::string` | mVersion
136 | (32) `std::string` | mUid
168 | (32) `std::string` | mUrs
200 | (32) `std::string` | mFilename
232 | (32) `std::string` | mAssertCacheDir
264 | (1) `std::atomic<bool>` | mInAssert
272 | (64) `std::unordered_map<std::string,int>` | mAssertNums


### `EasyThread`
Offset | Type | Name
-|-|-|-
0 | (8) `EasyThread_vtbl *` | __vftable
8 | (1) `bool` | m_bRun
16 | (16) `std::thread` | m_thread


### `EasyDownloader`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsRunning
8 | (32) `EasyThread` | mThread
40 | (160) `Semaphore` | mSemphore
200 | (112) `tDownloadInfo` | mNowDownload
312 | (16) `std::list<tDownloadInfo>` | mDownloadQueue
328 | (1) `bool` | mIsHttpsEnable


### `EntityExtension`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,std::string>` | mEntityExtensionCollection


### `encodefuncentry`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (8) `_object *(__fastcall *)(_object *, _object *)` | encodefunc


### `EducationOptions`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackListener` | baseclass_0
8 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_8
24 | (8) `ResourcePackManager *` | mPackMan
32 | (1) `EducationFeature` | mFeatureFlags
40 | (8) `ServiceRegistrationToken<EducationOptions>` | mServiceRegistrationToken


### `ExperimentStorage`
Offset | Type | Name
-|-|-|-
0 | (32) `std::vector<bool>` | mExperimentData
32 | (1) `bool` | mExperimentsEverToggled


### `Experiments`
Offset | Type | Name
-|-|-|-
0 | (40) `ExperimentStorage` | baseclass_0


### `EntityId`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `EntityContextBase`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistryBase *` | mRegistry
8 | (4) `const EntityId` | mEntity


### `EntityContext`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContextBase` | baseclass_0


### `EnableGetWeakRef<EntityRefTraits>`
Offset | Type | Name
-|-|-|-


### `Entitlement`
Offset | Type | Name
-|-|-|-
0 | (24) `ContentIdentity` | mContentIdentity
24 | (32) `std::string` | mProductId
56 | (32) `std::string` | mName
88 | (32) `std::string` | mCreatorId
120 | (32) `std::string` | mOwnerId
152 | (4) `unsigned int` | mQuantity
160 | (32) `std::string` | mProofOfPurchase
192 | (32) `std::string` | mContentKey
224 | (1) `bool` | mIsValid
228 | (4) `Entitlement::Authority` | mAuthority
232 | (32) `std::string` | mVerificationKey
264 | (1) `bool` | mIsFromSubscription
272 | (32) `std::string` | mExpirationDate


### `ExpressionNode`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mOp
4 | (4) `float` | mMul
8 | (4) `float` | mAdd
16 | (88) `MolangScriptArg` | mValue
104 | (24) `std::vector<ExpressionNode>` | mChildren
128 | (24) `std::vector<std::function<void __cdecl(MolangEvalParams &)>>` | mInstructions
152 | (1) `bool` | mStoreStackState
153 | (1) `bool` | mNeedsToCompile
154 | (1) `std::atomic<bool>` | mIsBeingCompiled
160 | (32) `std::string` | _mExpressionString
192 | (16) `ExpressionOpBitField` | mUsedTokenFlags
208 | (1) `bool` | mIsRootExpressionWithVariable


### `ExpressionOpBitField`
Offset | Type | Name
-|-|-|-
0 | (16) `unsigned __int64[2]` | mBits


### `EducationLevelSettings`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | codeBuilderDefaultUri
32 | (32) `std::string` | codeBuilderTitle
64 | (1) `bool` | canResizeCodeBuilder
72 | (64) `std::unordered_map<std::string,CommandFlag>` | hiddenPlayerCommands
136 | (48) `EducationLocalLevelSettings` | localSettings


### `EducationLocalLevelSettings`
Offset | Type | Name
-|-|-|-
0 | (40) `std::optional<std::string >` | codeBuilderOverrideUri
40 | (1) `bool` | hasQuiz


### `EducationContentManagerScreenController::launchWorld::__l2::<lambda_9ec0a0a701853c2e37cee208edb1dde1>`
Offset | Type | Name
-|-|-|-
0 | (8) `EducationContentManagerScreenController *const` | __this
8 | (64) `const std::function<void __cdecl(void)>` | onLaunchSucceeded
72 | (64) `const std::function<void __cdecl(void)>` | onLaunchFailed
136 | (32) `std::string` | templateId
168 | (32) `std::string` | productId
200 | (1) `bool` | hasQuiz
208 | (136) `PackIdVersion` | templateIdVersion


### `EDUScreenHelpers::TemplateWrapper`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | mType
8 | (8) `$FF69CD063870CA30F025610930358A75` | ___u1


### `EDUDiscoveryDialogCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(void)>` | mToIpEntry
64 | (64) `std::function<void __cdecl(void)>` | mToJoincodeEntry


### `EDULibraryCategoryParser::getCategories::__l45::<lambda_da8fe009fabed056b3ef467463815ed0>`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | newScreenTitle
32 | (32) `std::string` | icon
64 | (32) `std::string` | description
96 | (24) `std::vector<std::string>` | tags
120 | (64) `std::function<void __cdecl(std::shared_ptr<MainMenuScreenModel>,std::string,std::string,std::string,std::vector<std::string>)>` | worldsCallback


### `EDULibraryCategoryParser::getCategories::__l24::<lambda_bc64e7a9c0fc45231d5ae139738f745b>`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | newScreenTitle
32 | (32) `std::string` | icon
64 | (32) `std::string` | description
96 | (32) `std::string` | screenshotRatio
128 | (4) `int` | itemsPerRow
136 | (24) `std::vector<std::string>` | categories
160 | (1) `bool` | firstPage
168 | (64) `std::function<void __cdecl(std::shared_ptr<MainMenuScreenModel>,std::string,std::string,std::string,std::string,int,std::vector<std::string>,bool)>` | subCategoryCallback


### `ExprToken`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::Value` | mValue
16 | (32) `UiExpression` | mAsExpression
48 | (4) `_BYTE[4]` | mOperatorType
52 | (4) `_BYTE[4]` | mLiteralType
56 | (4) `_BYTE[4]` | mTokenType


### `EducationContentServices::getLibraryItem::__l7::<lambda_9d6d370868ed710c1f2db810e3661c1f>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<EducationContentServices>` | weakThis
16 | (8) `LibraryService *` | service
24 | (64) `std::function<void __cdecl(std::shared_ptr<LibraryItem>)>` | callback


### `EducationContentServices::_fetchLibraryItems::__l2::<lambda_e8c138023c5ae50adcdb015bd43b2444>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<EducationContentServices>` | weakThis
16 | (8) `LibraryService *` | service
24 | (16) `std::weak_ptr<InstructionalContentCollection>` | collection
40 | (16) `std::shared_ptr<InstructionalContentQueryContext>` | context
56 | (16) `std::shared_ptr<LibraryCollectionConfig>` | config


### `EducationContentServices::_fetchChannelItems::__l2::<lambda_7494183596c58195619b3b2414670acb>`
Offset | Type | Name
-|-|-|-
0 | (8) `ChannelService *` | service
8 | (16) `std::weak_ptr<InstructionalContentCollection>` | collection
24 | (16) `std::shared_ptr<InstructionalContentQueryContext>` | context
40 | (32) `const std::string` | channelName


### `EducationContentServices::_getLibraryImage::__l2::<lambda_e39421a97b773421d2dd913758e32443>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<LessonItem>` | weakItem
16 | (64) `std::function<void __cdecl(void)>` | callback


### `EducationContentServices::_getChannelImage::__l2::<lambda_5c0ed10d2c4d4b28cc3a69c62f4957bd>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<LessonItem>` | weakItem
16 | (64) `std::function<void __cdecl(void)>` | callback


### `EntityNetId`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `ExternalContentManager::importContent::__l49::<lambda_d678ee9e8348c9fbc609068109e0c70f>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExternalContentManager *const` | __this
8 | (16) `std::shared_ptr<ImportContext>` | context
24 | (16) `std::shared_ptr<std::unique_ptr<PackManifest> >` | manifestPtr
40 | (16) `std::shared_ptr<PackReport>` | importReport
56 | (56) `ResourceLocation` | contentLocation
112 | (32) `Core::PathBuffer<std::string >` | mcContentHeapPath
144 | (1) `bool` | fromTemp
145 | (1) `bool` | loadLevel
146 | (1) `bool` | isTitleLocked


### `ExternalContentManager::importContent::__l49::<lambda_e1f4fe332ddbbeb8e782b45738314a25>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExternalContentManager *const` | __this
8 | (16) `std::shared_ptr<ImportContext>` | context
24 | (16) `std::shared_ptr<std::unique_ptr<PackManifest> >` | manifestPtr
40 | (16) `std::shared_ptr<PackReport>` | importReport
56 | (56) `ResourceLocation` | contentLocation


### `ExternalContentManager::importContent::__l49::<lambda_d678ee9e8348c9fbc609068109e0c70f>::()::__l49::<lambda_68c4c98f28c6aaccd5c3d405992a8f84>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExternalContentManager *const` | __this
8 | (16) `std::shared_ptr<ImportContext>` | context
24 | (16) `std::shared_ptr<bool>` | attemptImport
40 | (16) `std::shared_ptr<std::unique_ptr<PackManifest> >` | manifestPtr
56 | (16) `std::shared_ptr<PackReport>` | importReport
72 | (32) `Core::PathBuffer<std::string >` | mcContentHeapPath
104 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | tmpFolderPath
1144 | (32) `Core::PathBuffer<std::string >` | rootDirectoryPath
1176 | (1) `bool` | loadLevel
1177 | (1) `bool` | isTitleLocked


### `ExternalContentManager::importContent::__l49::<lambda_d678ee9e8348c9fbc609068109e0c70f>::()::__l49::<lambda_da31632bf30fea9a62c7a413c1096b11>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ImportContext>` | context
16 | (16) `std::shared_ptr<bool>` | attemptImport
32 | (56) `ResourceLocation` | contentLocation
88 | (32) `Core::PathBuffer<std::string >` | mcContentHeapPath
120 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | tmpFolderPath
1160 | (120) `Core::ZipUtils::UnzipSettings` | settings


### `ExternalContentManager::LoadingContentData`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | packType
8 | (56) `ResourceLocation` | packLocation


### `ExternalContentManager::_importMCPack::__l2::<lambda_0d815293ee69d5854edcdfb58e4d6129>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExternalContentManager *const` | __this
8 | (16) `std::shared_ptr<ImportContext>` | context
24 | (1) `bool` | fromTemp
32 | (32) `const std::string` | packName
64 | (1) `bool` | isZipStrategy
72 | (32) `Core::PathBuffer<std::string >` | manifestPath
104 | (64) `ExternalContentManager::LoadingContentData` | loadingData
168 | (1) `_BYTE[1]` | packType
172 | (4) `PackOrigin` | packOrigin
176 | (1) `bool` | hasWarnings
184 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | packOutputFolder
1224 | (32) `Core::PathBuffer<std::string >` | packBaseFolder
1256 | (1) `bool` | isTitleLocked


### `ExternalContentManager::_importMCAddon::__l2::<lambda_d9093fe1973220a7d352f71cbaa4bd85>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExternalContentManager *const` | __this
8 | (16) `std::shared_ptr<enum Core::ZipUtils::UnzipResult>` | unzipErrorCode
24 | (16) `std::shared_ptr<ImportContext>` | context
40 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | tmpFolder
1080 | (1) `bool` | isTitleLocked


### `ExternalContentManager::_importMCAddon::__l2::<lambda_79878216f9465baeda875fb6deec6338>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ImportContext>` | context
16 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | mcAddonStackPath
1056 | (16) `std::shared_ptr<enum Core::ZipUtils::UnzipResult>` | unzipErrorCode
1072 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | tmpFolder


### `EDUDiscovery::ServerID`
Offset | Type | Name
-|-|-|-
0 | (16) `EDUDiscovery::JoinCode` | joinCode
16 | (32) `std::string` | passcode
48 | (32) `std::string` | token


### `EDUDiscovery::JoinCode`
Offset | Type | Name
-|-|-|-
0 | (16) `std::array<int,4>` | code


### `EDUDiscovery::Dialog`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mId
32 | (56) `EDUDiscovery::LocKey` | mTitleText
88 | (56) `EDUDiscovery::LocKey` | mBodyText
144 | (24) `std::vector<EDUDiscovery::Button>` | mButtons
168 | (1) `EDUDiscovery::ButtonAction` | mCloseAction


### `EDUDiscovery::LocKey`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mKey
32 | (24) `std::vector<std::string>` | mArgs


### `EDUDiscovery::QueryContextInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `gsl::basic_string_span<char const ,-1>` | name
16 | (4) `int` | startTimeMS
24 | (48) `std::optional<EDUDiscovery::Error>` | error
72 | (184) `std::optional<EDUDiscovery::Dialog>` | dialog
256 | (8) `std::optional<int>` | retryAfterSeconds


### `EDUDiscovery::Error`
Offset | Type | Name
-|-|-|-
0 | (1) `EDUDiscovery::ErrorType` | type
4 | (4) `int` | code
8 | (32) `std::string` | reason


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AnimationEventComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BuoyancyComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InsideBlockNotifierComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `ExpressionNode::initializeMolang::__l6::<lambda_8c234082fa8512752ece3c5895984b5c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_039b2ef269ab9e93320b05c26d51ec16>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8354b77005621129856c83a4abd59c68>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b916456e3405ecf363c220ac1a1e8b0e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_eb6240e03bedb8f31b5d78ecbe73eda9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_d12b4adb9a790e7f592ae21e555e08ef>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_3ebd2d3a068677cbd7710e659df66b21>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b40481c0ece54810bab8f04b826cb7bf>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_5c3ef44fd4c772f22cf3e9a99f00d696>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_51a7e0953e78fabde5bf9078c5d0cc9e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_19886a0c20e19a2c282a1db38755416a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_2d275f74ca60156f12dfb75eb1405b87>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f22b33fe71d63213a65e736e5f222092>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_4d2392b1fdbb1334df0918bcf4e51b5d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_825673181dd772f8e5d9cd3b1501a4be>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_fa3e15dee22b1f75dff444b27af0a2a3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a10aa78aa36c08624160503b5812533b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_65180b253ac0eacb04b5247fca63091d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7635aca3040657e427f73cc880ed1ab3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_87b2fc2cb0b8f96135d6724244560256>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6dd60b81050da2f5e3cf5eeacbe6a8f0>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_cd7cf7323ea0d5dd2d065a4b9adfaa89>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7d4439dd6e5a6d7dfd5e8d0fad018056>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_12abca9c3ffd26a3c3c7ac68a850fa85>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_e0a3522af07c9181bfd9090b77f7b59d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_805fc43cec74705143c13ec044709dd9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7e3f984dd2320fb997bab8cc7a80fb5f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_120356ac50d10250e66ebf4fcee2cf23>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7dd9838119d72bcaed1e8ee7ff0f0121>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_cd8ad61e453d95172a4dd8c4049e7ab4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ef678ff496d5371a6db08740a705f63d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ac3298e6cbe5bf23ef42ebae5830d185>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_0e470e86d5cda176f8ff0059d9b5e564>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_bb9f14504eeced52d46635bde80ccb5c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_60f26937fbe943fc8c18d3bed5a6ff72>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_31b2986231915a84dedde26d9e5dc398>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8c742361b7252e03baa6080c61057d49>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_53d7ac56bd3f57323ad7fc5fe29a7842>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_d04a6b94dcacf36229b19f1f6013633f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6a9b826eb20b64e227e84db8c8466734>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_1b0405884ba7f6fe5416ea6a6e6bf847>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_60e80c44daf2741a7a2f01e7b4dc78aa>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_3feb88e75cf415da7280fa67d9241beb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b03528bfbc2de1067c9e6a08d0aea2f4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_824b6fb5ba24f123d5a9afab4b895c4a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_0c1ff660e1bf442cf4ec2b7b44b32994>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8919c298b594b5b186d2bc971196cafa>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_03c63a3d310a72d982a90bfe82eda44b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_585183d0c6f48c409b280e46ea1a5cc2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_473f3cbb9bb25ab4fd439ae82453b631>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_79f821bb81b1eb25987b1225294dd7d1>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7fd1845d86388b37df05f2cd63005b90>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_3e7882691e3087199b9e1d6a12feb1d3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ec190d035904c9337912ab705a11c30e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6b853ab8df9d498d8f73dfd99b901650>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ecfaf119601e6f3a4fb4d9d50b56164f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_da8390a562fafc91f77c35355911aa96>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_afed7556c9e22bbc481ed47922cbb93d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ab74f46805a8e55810ccb6763a3f0030>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_84eaaa59f1c6cde15780a765a7d21980>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6142dc60f8810b40a070344f0b2ca592>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_08b5324dcc5b3c30882d726bcac28c02>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_761d2b4b9ce03d8c30953cccceae539b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7fb58a171d19ed2a9b213428191e6d93>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_5036acfc0552be699c55192f82544d13>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_61c1f8159bfddf5f7a4f939361ccf81f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_4f8a0f098678e91be563744a56adc3c4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_0a74aacb83e9c9743f2c96fef2e071a1>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_d7840b51b5dfa5d12d08c11839ad46c2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f7577b59b1e904b20416a27bedc42ccb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a934e1c2b0d737c356087c99879aabfc>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b03edb3cafe9b18fc70c261d968cb5e1>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8e6d237f4c569e82d4ffbb92e8d49fba>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_559f5a7edab576cc042e7f5c97b378ac>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a3441893ca8fbf03f2a098f10328d3c2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b4bcb71761b0e38e59e84cc36f7a5968>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_38eeb76a6e13621de7dbbd9511fa8ff1>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f9126d5e07d963c1daca58c577f0d4bb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_2dcf4ca741d4b785adfedb05f58620ab>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_71bd68c6f367b0293e1fea7e7681a379>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_9e502e9b7b99da08f013f53b788e1c5e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_f59c738732ec6f629e9b24902479f013>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_1aed22607d19cfcc7453b64f79387464>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_b785945ef2f51e690b67c4411dd8c3a6>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_bc409238a5459d915239b795d6c179e2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_04a5f05e297c565f0a69e8e3472adc03>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_647eec298d00e82e18184f2cc82211f1>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_7fd407f0fb0233c78872ea8870c537b8>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_84ed6e5ed3dd47b2f461bda639fa3269>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_5d696e11742b83851411d2e1e5f20214>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_50bbae78398e7166ea1dd9c2b9f8049d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_42600b42d146c496aebb6e80b0f02dac>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_baddedb032330d404e3dd834ae293bd9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_05b9e1f1b6e1cf76f902f8b37ac5d230>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_06096cf911be12e66f4b2499f8e04889>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_413fdf6b10366ff8594baa58d313731c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_f08efa56d840b68784194e32978bb0eb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_f9964153463dceee0e3c8e111a9aad30>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_2a3459f8b67ae6b24034c91c61429ba2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_39306b08482aa7b788ce0fc89bac3a9d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_17e920b275c1e774cdd76c0d61aa160c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_2fbb7c155a3d0302f70bc9baad5c7ad7>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_f9194b295e2d237a7b71548145d4e757>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_582a9d2e5fa0605a1667313a3da4581d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_5718923b81101c47ee2570ce379453a5>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_9b59bb53219c48aa37add68bcbe2e817>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_99b60402aa7c8b28db26ccb7e3db8841>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_86635e0c3b739e9e8a3799aa15cf683b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_8ccfdd20985c850fb82ece1104f3512e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_995a3a26ac84c4a25e9f8718f9b5664f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_6bac4d2902db8e732f11c722fbfb2f5a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_ee08f67a7525a6dde59865838036cd0d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_f07234f6f9fdfd16ad93ecf6ed9492f2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_cf8f7e40e75ec817d9fbbe7a5c142c59>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_ccae028b150f5bdbe49b912e98e981a4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_4d8ba46041b5d6c59d0918ac13964fa3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_d32c9f33de940d00c2d06c44098bca25>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_af78ae829b1044a12f9454598528a76f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_1b1f69e2170c04b9f8eb727986efbc81>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_2e5f206bd02bc3f15390c17101c0d318>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_24360a8b8e865eb3dc4bac0b63bad42e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_1a6682370d167cc8692c8036b6e1c0b5>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_092f9fc4b37e99e498751956bc2222a9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_03be2025787c4db35af809a13a6820d3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_6af83c5ef992db9e1b6d54ee1b90c13f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_bfee9bdc0c4c6b4ae54c7bb643179726>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_6f5f7281cf09d55e6e6cf6143e1e2a9e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_045917ffcbcd02108669203ce030efe5>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_e51309525026fb0b09b059e04e5fad0c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_4d83f513ccf6c488a8b33079a9726749>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_89d3a68422909efbd8c93a33dcd622f4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_4710ef3404819d6729781aac9d1addfd>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_a72b7e731a4191c7279856c0aafecc4c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_0154487a9930c1e326b9d0b582df3e09>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_53443c4937fe447fb95dc385ce82d83a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_09a52275d6e47f799d9ca4b02903f606>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_ec2c0f288833a71d3aece77be73dfa69>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_a588a659ce2f9587d52767bbbc264a9e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_da065692803089f2da39de8fd2ac808e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_246b9119ee120f4617767802fb92158a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_6ecc0193ca3ca99c64a56c7c5c2b9017>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_e3991fa4a2b21a8b568a0f5b2cb23bd9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_a09604f6cb14f37867fc059ca1f008ab>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_d3cfc79e62f691cb8f3e5fbfed321e32>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_60cec8ab9364e227829fce9a02633893>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_75fbd8107e11f5e87bab78cc96ba2bcb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_a79d89762a0585d995ed0ed6ad9935f3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l10::<lambda_684227ecbc44ebfdf793f5b7d47a9edf>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_4e04f48327e264b8a9ba4dcc83c9440d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_841810ee30d8b3f42099ca016ed4c69a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_60cf300ce907d79d593546835b956c1b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f6bb0bfc49f5ed3761ec9137aa0438ea>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_903af9f66256261f34874b338a4a4f7f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_e13c7fd02a5e71a939e5ea74058cc49f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_c2e2f99b1c6874083ddf7f39ac6182c7>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_1e75c7d5f30e211f721774c7511a2d88>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8d7966a8f53bb669d64a03bdf019f5fa>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_4ae9e3171917cfd7619988c0e950188a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a516ce80e5ecf5e94019c75e8dde73a9>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a8d09948e945fce7ffab47f01c7a302e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_29f2b223a2461c40a1163c889fe6b87f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_5e6ff7484bd5c646e243964e25d300a0>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8cac01a5220aac05c847f3e2cce82661>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_d4408c130bbd8a8b832d03dc953b9211>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6cad7c4a472a880942d89d72a7cca62c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_966b88a21697b6de4a2bdf28cec116b3>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a79ecd2712ecf2e6b548111688dfe62d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8424208d67ec62437d9bf4eef8dcfbd7>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_d8992117c5f47c8041d4b8a4521098a4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_819752221f21ae4318f7ac9b940dbbc7>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_22de6a610c1c1dec93e93c6fb2f006f0>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_e5bd5bffd63655c9e798a5194a0aa271>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_bfe9148baaa3c02a2f0fe35a744c5f8e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_3a13ea4aefd442cb5345de35687c1c85>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f87a934996576160d3f855582ea7a69b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6d52c693f3d339a4bb3a6600d0195331>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_fb2e8da0186a7114dc9bbc3324ec7d59>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f091da43aa53a73263ef6859a4e5e64a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_bfaee7966b529e9759d07c821de93b8f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_9bb843d4bd9b2dcc4a9da12f6d29b0af>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_fb52345b647cf4365cdfd00308ec629b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_56d226e00364df4379ade620655b2e93>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_3354af0ff7f1a0679cde5676cc2ce810>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_00e065578a279ebe731ae7f711251003>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6c12460af13f8a21bfbf0a330d5007d5>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8270bb89b2a3058814424bf2095ed67e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ff9fb298ce6386db966c8e1928ed8346>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7f8e798d45920d0cfcdf49440ac5c728>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_742d4c7673b95a9c27a7b5e2592ef834>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7679a02d1433e29a186c3ee3f3d7db7f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_c39ff35c9e29873c7907ce46a58d6222>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_7bf348e0b14c005c365ebd80e3c76e14>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_86ca3c8c7ed387d8b592e3039002c5b2>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_50893b6b2aed74ee1f40a306730358be>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_0b4abe01a88c3bb5b7958db64bc10679>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f6ab757260a56989d611815c7fe7149d>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ed462d6433a55329dbdaf29e3ed39028>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_1bf193f40ae65c42b29c4e7a9d78d15c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_180880b5d8cbf1fa504082057e9d476c>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_1b2fdb4c0b427a54aafebcc71616309f>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_548f31616e4b0a980d309665f5f0860a>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_851ca10ea4160113879519e414b2c289>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_6dcf68998c0117383d5a400cc025e616>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_f6695b194d89c25e732a12cbf22da081>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ccea425cb69625d0ead2c205de9bd34e>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a333014e91706dbbe5416b709107f0e6>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_e02720ca3798caa120f3af0e187a6eac>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_5a5c30fc97496b068a58649ddaad43c7>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ab8a24d305c867775025f06fa9f578f6>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_90f410c942ec23030b9340239c7c5094>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b5f5606292cbdf6690faed347c7950f5>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_ce1967c1f2f87c5abaad01c60b55090b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_5cce5c64ebec7c7d0ca36c3eb50e0076>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_187da0bb4d8eb8fffa2256adc8f44e78>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_38601fcfcac7c49a59e909a8d3e292cb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_a71f270ec9f705a1f42a210c60e32828>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_075a47141d58348a882c7ee4f93b0af4>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_33378aa007acdda89eb831d542e7666b>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_b8db1893835474aec67416614d19d1ae>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_409bb526599a4c315ef8ff839e8f66e8>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_2201adf8fc1315e8800cd4b2a00c0bcb>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_1959bf99edd6a2c24fc6fccde58a0bb6>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_8c960fa7625b7f84b2a83d03c1957744>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_0452b4502f3dbdc9547f7381a805bc23>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_27ba812b4dbf429b63bf8a1b7473cefc>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_dc18206dcd7696f1945b14c7937d9490>`
Offset | Type | Name
-|-|-|-


### `ExpressionNode::initializeMolang::__l6::<lambda_319c01756c23237ec5cc113c93ac2b0f>`
Offset | Type | Name
-|-|-|-


### `EventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mPlayerId
48 | (200) `EventPacket::Data` | mEventData


### `EventPacket::Data`
Offset | Type | Name
-|-|-|-
0 | (4) `EventPacket::Type` | mType
4 | (1) `unsigned __int8` | mUsePlayerID
8 | (32) `$ADDA9D19C5EE994A4AB78192967BF400` | ___u2
40 | (32) `std::string` | mEntityName
72 | (32) `std::string` | mCommandName
104 | (32) `std::string` | mResultKey
136 | (32) `std::string` | mResultString
168 | (32) `std::string` | mErrorList


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_Achievement>`
Offset | Type | Name
-|-|-|-
0 | (4) `MinecraftEventing::AchievementIds` | mAchievementId


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_Interaction>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mInteractedEntityType
4 | (4) `MinecraftEventing::InteractionType` | mInteractionType
8 | (4) `int` | mInteractedEntityVariant
12 | (1) `unsigned __int8` | mInteractedEntityColor


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PortalCreated>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mBuiltInDimension


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PortalUsed>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFromDimension
4 | (4) `int` | mToDimension


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PetDied>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mKilledByOwner
8 | (8) `__int64` | mKillerEntityId
16 | (8) `__int64` | mKilledMobId
24 | (4) `int` | mDamageSource
28 | (4) `ActorType` | mKilledMobType


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_MobKilled>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | mKillerEntityId
8 | (8) `__int64` | mKilledMobId
16 | (4) `ActorType` | mDamageChildType
20 | (4) `int` | mDamageSource
24 | (4) `int` | mTraderTier


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_CauldronUsed>`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mContentsType
4 | (4) `unsigned int` | mContentsColor
8 | (2) `__int16` | mFillLevel


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PlayerDied>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mKillerId
4 | (4) `int` | mKillerVariant
8 | (4) `int` | mDamageSource
12 | (1) `bool` | mInRaid


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_BossKilled>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mPartySize
8 | (8) `__int64` | mBossUniqueId
16 | (4) `int` | mBossType


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_AgentCommand>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mResult
4 | (4) `int` | mResultNumber


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PatternRemoved>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mItemId
4 | (4) `int` | mItemAux
8 | (4) `int` | mLayerIndex
12 | (4) `int` | mPatternId
16 | (4) `int` | mPatternColor


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_SlashCommand>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSuccessCount
4 | (4) `int` | mErrorCount


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_MobBorn>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mBabyType
4 | (4) `int` | mBabyVariant
8 | (1) `unsigned __int8` | mBabyColor


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_POICauldronUsed>`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mItemId
4 | (4) `_BYTE[4]` | mInteractionType


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_ComposterUsed>`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mItemId
4 | (4) `_BYTE[4]` | mInteractionType


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_BellUsed>`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mItemId


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_RaidUpdate>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCurrentWave
4 | (4) `int` | mTotalWaves
8 | (1) `bool` | mSuccess


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PlayerMovementCorrected>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mPositionDelta
4 | (4) `float` | mObservedScore
8 | (4) `float` | mThresholdDistance
12 | (4) `float` | mThresholdScore
16 | (4) `int` | mThresholdDuration_ms


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PlayerMovementAnomaly>`
Offset | Type | Name
-|-|-|-
0 | (1) `MovementEventType` | mEventType
4 | (4) `float` | mObservedScore
8 | (4) `float` | mAveragePosDelta
12 | (4) `float` | mTotalPosDelta
16 | (4) `float` | mMinPosDelta
20 | (4) `float` | mMaxPosDelta


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_TargetBlockHit>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRedstoneLevel


### `EventPacket::Data::<anonymous-tag>::<unnamed_type_PiglinBarter>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mItemId
4 | (1) `bool` | mWasTargetingBarteringPlayer


### `EventResponseCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<EventResponse>>` | mResponses


### `Explosion`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (4) `float` | mRadius
16 | (64) `std::unordered_set<BlockPos>` | mToBlow
80 | (1) `bool` | mFire
81 | (1) `bool` | mBreaking
82 | (1) `bool` | mAllowUnderwater
88 | (8) `Actor *` | mSource
96 | (8) `BlockSource *` | mRegion
104 | (4) `float` | mMaxResistance
108 | (2) `std::optional<bool>` | mInWaterOverride
112 | (2516) `Random` | mRandom


### `EnchantResult`
Offset | Type | Name
-|-|-|-
0 | (1) `EnchantResultType` | result
8 | (8) `unsigned __int64` | enchantIdx
16 | (4) `int` | level


### `ExperienceRewardComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ExpressionNode>` | mOnBred
24 | (24) `std::vector<ExpressionNode>` | mOnDeath


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BehaviorComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BodyControlComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BoostableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreakDoorAnnotationComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,CelebrateHuntComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ActorFlagComponent<EnvironmentSensorFlag> >`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntitySensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mSensorRange
4 | (1) `bool` | mRelativeRange
8 | (4) `int` | mMinimumCount
12 | (4) `int` | mMaximumCount
16 | (1) `bool` | mRequireAll
24 | (64) `ActorFilterGroup` | mEventCondition
88 | (32) `std::string` | mEventName


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,FlockingComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,GrowsCropComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InteractComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,JumpControlComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LookAtComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LookControlComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MoveControlComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,NavigationComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SchedulerComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SensingComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TargetNearbyComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TeleportComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `ExtendedStreamReadResult`
Offset | Type | Name
-|-|-|-
0 | (4) `StreamReadResult` | result
8 | (32) `std::string` | resultContext


### `EndTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0


### `EducationMetadata`
Offset | Type | Name
-|-|-|-
0 | (4) `EducationMetadata::ContentType` | mContentType
4 | (4) `int` | mEstimatedTime
8 | (32) `std::string` | mDescription
40 | (32) `std::string` | mGoals
72 | (24) `std::vector<std::string>` | mTasks
96 | (24) `std::vector<std::string>` | mInstructions
120 | (32) `std::string` | mLinkToMore
152 | (4) `int` | mOrder
156 | (4) `_BYTE[4]` | mRole


### `EducationMetadataError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `ExecuteCommandPositionData`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mActorPosition
12 | (12) `BlockPos` | mDetectPosition


### `EquippableDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SlotDescriptor>` | mSlots


### `ExplodeDefinition`
Offset | Type | Name
-|-|-|-
0 | (8) `FloatRange` | mFuseLength
8 | (4) `float` | mExplosionPower
12 | (4) `float` | mMaxResistance
16 | (1) `bool` | mIsFuseLit
17 | (1) `bool` | mCausesFire
18 | (1) `bool` | mBreaksBlocks
19 | (1) `bool` | mFireAffectedByGriefing
20 | (1) `bool` | mDestroyAffectedByGriefing


### `ExpressionNode::_buildProgram::__l7::<lambda_ca7f7dcb23aab27a454ffdabf5c34517>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | addValue


### `EntityGoalUtility::NumericNodeData<int,std::less<int> >`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | base
4 | (4) `int` | defaultTo
16 | (32) `std::string` | msg
48 | (32) `std::string` | specifier
80 | (32) `std::string` | baseName
112 | (32) `std::string` | parent
144 | (32) `std::string` | name


### `EntityGoalUtility::addNode::__l2::<lambda_552f9f20b540ed5e3df8f839ca8542ca>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | base
4 | (4) `int` | defaultTo
16 | (32) `std::string` | msg
48 | (32) `std::string` | specifier
80 | (32) `std::string` | baseName
112 | (32) `std::string` | parent
144 | (32) `std::string` | name


### `EntityGoalUtility::addNode::__l2::<lambda_c571084d3e07e5a8dc3424d66257fe50>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_063f0dba8f666f1e4c07c656bcab5592>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | base
4 | (4) `float` | defaultTo
16 | (32) `std::string` | msg
48 | (32) `std::string` | specifier
80 | (32) `std::string` | baseName
112 | (32) `std::string` | parent
144 | (32) `std::string` | name


### `EntityGoalUtility::addNode::__l2::<lambda_42a2104b56a8472f16d1815baf0dc7df>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityTypes`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<MobDescriptor>` | mDescriptors


### `EntityGoalUtility::addNode::__l2::<lambda_0dd92dde9ac1a21c8c9b1726031654e4>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e06d1a12a5bdb7657af8701f035eed51>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EnchantmentInstance`
Offset | Type | Name
-|-|-|-
0 | (1) `Enchant::Type` | mEnchantType
4 | (4) `int` | mLevel


### `ElementInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `ElementCategory` | mCategory
8 | (8) `const char *` | mName


### `EndPortalShape`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mSource
8 | (4) `int` | mRightDir
12 | (4) `int` | mLeftDir
16 | (4) `int` | mDepthDir
20 | (12) `BlockPos` | mBottomLeft
32 | (12) `BlockPos` | mOrigin
44 | (4) `int` | mBlockDirection
48 | (24) `std::vector<std::vector<Block const *>>` | mPortalPattern


### `EntityGoalUtility::addNode::__l2::<lambda_e8a44547e63ebbfac2555e65a2f456a1>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_90b12e1219acd356d0be2dc1fcbf3981>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BalloonComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BossComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreedableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BribeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ActorFlagComponent<BurnsInDaylightFlag> >`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DanceComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DwellerComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HopperComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InsomniaComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MountTamingComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,PeekComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,RaidBossComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ScaffoldingClimberComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ScaleByAgeComponent,AgeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LegacyTradeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityGoalUtility::addNode::__l2::<lambda_f580b598cc760f2d25b9907df3c331e2>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e56cccd53edfb12c21d39d0170b34617>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_492b48aeb63b952dc4c970df65f37e95>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,EntityGoalUtility::UnsignedRange<float> >` | data


### `EntityGoalUtility::NumericNodeData<float,EntityGoalUtility::UnsignedRange<float> >`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | base
4 | (4) `float` | defaultTo
16 | (32) `std::string` | msg
48 | (32) `std::string` | specifier
80 | (32) `std::string` | baseName
112 | (32) `std::string` | parent
144 | (32) `std::string` | name


### `EntityGoalUtility::UnsignedRange<float>`
Offset | Type | Name
-|-|-|-


### `EntityGoalUtility::addNode::__l2::<lambda_d0ffae376705822c61f33c86fd45420a>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,EntityGoalUtility::UnsignedRange<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_f0e28672e6cb982d9e65ff17fa9aeba7>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_2a15948f070248c10addc6f0f8ad5d92>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_05f720b33ad110bfaee78aa63b2bbe65>`
Offset | Type | Name
-|-|-|-
0 | (4) `LevelSoundEvent *__ptr32` | member
8 | (32) `std::string` | name
40 | (4) `LevelSoundEvent` | defaultTo
48 | (32) `std::string` | defaultToDisplay


### `EntityGoalUtility::addNode::__l2::<lambda_97e60a0638014e1bc886194686dcaba9>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_de214653a437ae1c27a4529d11f95327>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e76f38828430340aa80a24b6d0fe0b37>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_5f5faf6d48f0aeaea68060a8c1619155>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_02398ad5b269ce057509f400a5afe2e6>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,EntityGoalUtility::UnsignedRange<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_09cfc25ecfda4a656e54d61b3cee780a>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,EntityGoalUtility::UnsignedRange<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_45f45b7815677c096835ecb319311419>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_54cc50192a1f0d4bcf62b30a60e1bc23>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_508f882e70b9c0eab56ffeee881d4cd6>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_c2393d1fb1bf9460f3687a907112331f>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e1b4ac295dc99e15c2090660255eebba>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_7ac0bc18237b1b06bb6261365a087ca2>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_0b023014a775c0a951685a1866660a9b>`
Offset | Type | Name
-|-|-|-
0 | (4) `LevelSoundEvent *__ptr32` | member
8 | (32) `std::string` | name
40 | (4) `LevelSoundEvent` | defaultTo
48 | (32) `std::string` | defaultToDisplay


### `EntityGoalUtility::addNode::__l2::<lambda_f6901c242fa1953b7eb2c499325cf32e>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_4bfc91417bbb07c27f9e3f5cdb13cef2>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_06115e46e8bce38b25a587de78f5a115>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_dde3afbacd76ba3d1a850c5a026656bc>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_6314867dffdc86e5005ec099cf2fc8b0>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_232f76154705c83e27ca9cf53d680ede>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_59b631ec34c497e5e595d29ff1462458>`
Offset | Type | Name
-|-|-|-
0 | (4) `std::string *__ptr32` | member
8 | (32) `std::string` | defaultTo
40 | (1) `bool` | jsonRequired
48 | (32) `std::string` | valueName


### `EntityGoalUtility::addNode::__l2::<lambda_324868e4f46e7bb7ce8d98ff14beae9f>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_4d6f64563c4a35ab9a6b275f17eec78b>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_1ac188c21a1aa65a77e3307411c7bd6f>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e4a4b651dad3a077ec95f1ff54839250>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_bcda22fb5ef38a4c948ef475b0e1c13c>`
Offset | Type | Name
-|-|-|-
0 | (4) `Vec3 *__ptr32` | member
4 | (12) `Vec3` | defaultTo
16 | (1) `bool` | jsonRequired
24 | (32) `std::string` | valueName


### `EntityGoalUtility::addNode::__l2::<lambda_b1a5fcc9229cf3aa2272b2b32dd9b3a7>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_715b50fbbf3b994c6d4c590c045aa5a1>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_6d92e034cdb633e7e330ce8f13e174e2>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_0dad914f5255f37b6bd6dedb8cae0ba4>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_fa9c1abc1c0c6697af96ba63c63d8fde>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_0706e7c4c2dcbc502c83ef441e1808c3>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e2a3622a02ee5b423bde5b542c5d007c>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_7fc6d0ec80b3a95fb0ee7dad2ed93987>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_08d6b6a96918cdc6ee8d9a32d3ed2ee9>`
Offset | Type | Name
-|-|-|-
0 | (4) `Vec3 *__ptr32` | member
4 | (12) `Vec3` | defaultTo
16 | (1) `bool` | jsonRequired
24 | (32) `std::string` | valueName


### `EntityGoalUtility::addNode::__l2::<lambda_50ef740bc426480560d6c0868ba4fab2>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_f829994cdb7390eb433a43a4d4fc2a4d>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_d1d2c29caf949475babc4c8a2b342861>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_183c95040d6fcfc727b53183bb622f7f>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_168654adce9bc4834475392bb02731f4>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_928ff68ba4edfd618ddb9306d7361522>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_fb2c57d3f85512c3c330b0eb78eb7be3>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_3d15eb5535c1fa38c00c0a531ecdecce>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_ec26b00e494c84fd473d7bedb9fe4e1c>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_243d973a565c63e400a468c314e57852>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_4c1f52c85d014f71af6670bc8f46aa1d>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_bcdc718fc59248479ed93392b2e45300>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e7620ae38545f4856780c51464c7080b>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_fdcbad9e2a75d5d411d4c8b4a1b4376c>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_f1c7ba150dff14bc4a7472a8501623c2>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_23a080e0d086f1d6b0cc9c8a13e459ad>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_b784871b700e8c412e3864fd9c74e096>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_39f4bba68f6f21aab85e5ea6b46b6c81>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_a9f7b76a5913b11b1bf9c5840cfde27c>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_ecc4eb07b1c252ad2dd9cc2a3d24b9cc>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_c4e6d5bf6562e3e202e435eaf68d4807>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::NumericNodeData<float,std::less<float> >`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | base
4 | (4) `float` | defaultTo
16 | (32) `std::string` | msg
48 | (32) `std::string` | specifier
80 | (32) `std::string` | baseName
112 | (32) `std::string` | parent
144 | (32) `std::string` | name


### `EntityGoalUtility::addNode::__l2::<lambda_c4da05db56432241cf15d3ec25ffbaad>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_5baa277e93d00a42c36eaa0b92a33ba4>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_a1dcb6b5ac743623854fe6c664ef4edd>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_8ca315d71145918e8c68bc79b96a319d>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_44bc3aa970591d06e9adc72021107a9d>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_d38284478f0b8bd62bc82d50c6af7722>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_ea48377fabd22651e2dfa9b21ff5a4c1>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_713a8b54513bdb758f976a360a49eeb6>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_1a21a17d49b5c3847b51d8bd5fe38ead>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_2795266f84082388d965a8fb3eb7deda>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_1bc076dedb876c37f3593b9a7000e7b6>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_efb4e981ac7bb8dfa62f134e13a203df>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_d9bbf6b8dd24a3bc9337aad02669ce8e>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_7bb6ad087ffff13ca80f20a5bf977bb1>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_641d07809c9f15731287e6a649e40da8>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_193f11f6da268d77b4e2579ad5e3721b>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_e30bdee6b760248e95f8af700d778927>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less_equal<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_fa68f6657493a92543dfcd9d9efe6035>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_56a6871e78a9b32db6cd5c26f648e7dd>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_bb6e0abf843a995dd5198c49e35566e9>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_6608d62bd5c57cae7e67ffb6e78f762e>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_b2320732ad5b3c034bfae1a6d06b6a52>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_1c2c2396849f1fab2691c4031ad6236c>`
Offset | Type | Name
-|-|-|-
0 | (4) `float *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<float,std::less<float> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_9c87911e95e1e2e1bcde9dc2ab53e398>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EntityGoalUtility::addNode::__l2::<lambda_77c40c55275dc20e1ddb154c226550a3>`
Offset | Type | Name
-|-|-|-
0 | (4) `int *__ptr32` | member
4 | (1) `bool` | jsonRequired
8 | (176) `EntityGoalUtility::NumericNodeData<int,std::less_equal<int> >` | data


### `EndDragonFight::GateWayGenerator`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mPlaceNewBlocks
8 | (8) `std::unique_ptr<ChunkViewSource>` | mSource
16 | (12) `BlockPos` | mPosition


### `EndGatewayFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `EndIslandFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `EndPodiumFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (1) `bool` | mActive


### `EHExceptionRecord::EHParameters`
```
struct EHExceptionRecord::EHParameters
{
  unsigned int magicNumber;
  void *pExceptionObject;
  const _s_ThrowInfo *pThrowInfo;
  void *pThrowImageBase;
};

```

### `EHExceptionRecord`
```
struct EHExceptionRecord
{
  unsigned int ExceptionCode;
  unsigned int ExceptionFlags;
  _EXCEPTION_RECORD *ExceptionRecord;
  void *ExceptionAddress;
  unsigned int NumberParameters;
  EHExceptionRecord::EHParameters params;
};

```

### `EndTag_vtbl`
```
struct /*VFT*/ EndTag_vtbl
{
  void (__fastcall *~Tag)(Tag *this);
  void (__fastcall *deleteChildren)(Tag *this);
  void (__fastcall *write)(Tag *this, IDataOutput *);
  void (__fastcall *load)(Tag *this, IDataInput *);
  void (__fastcall *writeScriptData)(Tag *this, IDataOutput *);
  void (__fastcall *loadScriptData)(Tag *this, IDataInput *);
  std::string *(__fastcall *toString)(Tag *this, std::string *result);
  Tag::Type (__fastcall *getId)(Tag *this);
  bool (__fastcall *equals)(Tag *this, const Tag *);
  void (__fastcall *print)(Tag *this, const std::string *, PrintStream *);
  void (__fastcall *print)(Tag *this, PrintStream *);
  std::unique_ptr<Tag> *(__fastcall *copy)(Tag *this, std::unique_ptr<Tag> *result);
  unsigned __int64 (__fastcall *hash)(Tag *this);
};

```

### `EncryptedNetworkPeer`
```
struct __cppobj EncryptedNetworkPeer : NetworkPeer
{
  std::unique_ptr<Crypto::Symmetric::Symmetric> mDecryption;
  std::unique_ptr<Crypto::Hash::HMAC> mEncryptionMAC;
  std::unique_ptr<Crypto::Symmetric::Symmetric> mEncryption;
  std::unique_ptr<Crypto::Hash::HMAC> mDecryptionMAC;
  unsigned __int64 mSendCounter;
  unsigned __int64 mReceiveCounter;
  std::string mSendEncryptedDataBuffer;
  std::string mSendSignedDataBuffer;
  std::string mRecvEncryptedDataBuffer;
  std::string mRecvSignedDataBuffer;
  std::string mRecvDecryptedDataBuffer;
};

```

### `EncryptedNetworkPeer_vtbl`
```
struct /*VFT*/ EncryptedNetworkPeer_vtbl
{
  void (__fastcall *~NetworkPeer)(NetworkPeer *this);
  void (__fastcall *sendPacket)(NetworkPeer *this, const std::string *, NetworkPeer::Reliability, int, unsigned __int16, Compressibility);
  NetworkPeer::DataStatus (__fastcall *receivePacket)(NetworkPeer *this, std::string *);
  NetworkPeer::NetworkStatus *(__fastcall *getNetworkStatus)(NetworkPeer *this, NetworkPeer::NetworkStatus *result);
  void (__fastcall *addIncomingData)(NetworkPeer *this, std::string);
  void (__fastcall *update)(NetworkPeer *this);
  void (__fastcall *flush)(NetworkPeer *this, std::function<void __cdecl(void)> *);
};

```

### `EducationSettingsPacket`
```
const struct __cppobj EducationSettingsPacket : Packet
{
  EducationLevelSettings mEducationLevelSettings;
};

```

### `EducationSettingsPacket_vtbl`
```
struct /*VFT*/ EducationSettingsPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EventPacket_vtbl`
```
struct /*VFT*/ EventPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EntityServerPacket`
```
struct __cppobj __declspec(align(8)) EntityServerPacket : Packet
{
  EntityNetId mEntityNetId;
};

```

### `EntityServerPacket_vtbl`
```
struct /*VFT*/ EntityServerPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EmotePacket`
```
const struct __cppobj __declspec(align(8)) EmotePacket : Packet
{
  ActorRuntimeID mRuntimeId;
  std::string mPieceId;
  unsigned __int8 mFlags;
};

```

### `EmotePacket_vtbl`
```
struct /*VFT*/ EmotePacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EmoteListPacket`
```
const struct __cppobj EmoteListPacket : Packet
{
  ActorRuntimeID mRuntimeId;
  std::vector<mce::UUID> mEmotePieceIds;
};

```

### `EmoteListPacket_vtbl`
```
struct /*VFT*/ EmoteListPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EntityRegistryBase::ICanModifyComponentPoolDuringView`
```
struct __cppobj EntityRegistryBase::ICanModifyComponentPoolDuringView
{
};

```

### `EntityRegistryBase`
```
struct __cppobj __declspec(align(8)) EntityRegistryBase
{
  entt::basic_registry<EntityId> *mRegistry;
  EntityId mViewedEntity;
  std::unique_ptr<EntityRegistryBase::ICanModifyComponentPoolDuringView> mCanModifyDuringView;
  bool mViewUsesViewedContext;
};

```

### `EnableGetWeakRef<EntityRegistryRefTraits>`
```
struct __cppobj EnableGetWeakRef<EntityRegistryRefTraits>
{
};

```

### `EntityRegistry`
```
struct __cppobj EntityRegistry : EntityRegistryBase, EnableGetWeakRef<EntityRegistryRefTraits>, std::enable_shared_from_this<EntityRegistry>
{
  _BYTE gap20;
};

```

### `EntityRegistryOwned`
```
struct __cppobj EntityRegistryOwned : EntityRegistry
{
  entt::basic_registry<EntityId> mOwnedRegistry;
};

```

### `EducationOptions_vtbl`
```
struct /*VFT*/ EducationOptions_vtbl
{
  void (__fastcall *~ResourcePackListener)(ResourcePackListener *this);
  void (__fastcall *onActiveResourcePacksChanged)(ResourcePackListener *this, ResourcePackManager *);
  void (__fastcall *onFullPackStackInvalid)(ResourcePackListener *this);
  void (__fastcall *onBaseGamePackDownloadComplete)(ResourcePackListener *this);
  void (__fastcall *onLanguageSubpacksChanged)(ResourcePackListener *this);
  void (__fastcall *onResourceManagerDestroyed)(ResourcePackListener *this, ResourcePackManager *);
};

```

### `EventInfo`
```
struct __cppobj EventInfo
{
  std::string mEventName;
};

```

### `EventCoordinator<ScriptEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ScriptEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ScriptEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ScriptEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EnumBitset<enum ScriptLogType,3>`
```
struct __cppobj EnumBitset<enum ScriptLogType,3>
{
  std::bitset<3> mBitset;
};

```

### `EntitlementChangeListener`
```
struct __cppobj __declspec(align(8)) EntitlementChangeListener : std::enable_shared_from_this<EntitlementChangeListener>
{
  EntitlementChangeListener_vtbl *__vftable /*VFT*/;
  bool mRefreshingEntitlements;
};

```

### `EntitlementChangeListener_vtbl`
```
struct /*VFT*/ EntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `EducationContentServices`
```
struct __cppobj EducationContentServices : Bedrock::Threading::EnableQueueForMainThread, std::enable_shared_from_this<EducationContentServices>
{
  LibraryService *mLibraryService;
  ChannelService *mChannelService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  const WorldTemplateManager *mWorldTemplateManager;
  std::shared_ptr<LessonItemCache> mItemCache;
};

```

### `EducationContentServices_vtbl`
```
struct /*VFT*/ EducationContentServices_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `ExternalContentManager::ImportRequestData`
```
struct __cppobj __declspec(align(8)) ExternalContentManager::ImportRequestData
{
  std::shared_ptr<ImportContext> mContext;
  const Core::PathBuffer<std::string > mMcContentPath;
  bool mFromTemp;
  bool mLoadLevel;
  bool mTitleLocked;
};

```

### `ExternalContentManager::LoadingContentDataHasher`
```
struct __cppobj ExternalContentManager::LoadingContentDataHasher
{
};

```

### `ExternalContentManagerProxyCallbacks`
```
struct __cppobj ExternalContentManagerProxyCallbacks
{
  std::function<std::shared_ptr<ImportContext> __cdecl(enum ImportContextType,Core::Path const &,IMinecraftEventing &,ToastManager &,std::function<void __cdecl(bool)>,std::function<void __cdecl(bool,PackManifest const *)>)> mCreateImportContext;
  std::function<bool __cdecl(void)> mIsContentLoading;
};

```

### `ExternalContentManagerProxy`
```
struct __cppobj ExternalContentManagerProxy
{
  ExternalContentManagerProxyCallbacks mCallbacks;
};

```

### `ExternalContentManager`
```
struct __cppobj ExternalContentManager
{
  gsl::not_null<Bedrock::NonOwnerPointer<LevelLoader> > mLevelLoader;
  ResourcePackRepository *mPackRepository;
  ResourcePackManager *mPackManager;
  WorldTemplateManager *mTemplateManager;
  PackManifestFactory *mManifestFactory;
  const IContentKeyProvider *mKeyProvider;
  std::shared_ptr<SkinRepository> mSkinRepository;
  PersonaRepository *mPersonaRepository;
  PackSourceFactory *mPackSourceFactory;
  ResourceLoadManager *mResourceLoadManager;
  bool mContentInTransit;
  std::queue<ExternalContentManager::ImportRequestData> mQueuedContent;
  Core::PathBuffer<std::string > mTempImportFolder;
  std::unordered_set<ExternalContentManager::LoadingContentData,ExternalContentManager::LoadingContentDataHasher,std::equal_to<ExternalContentManager::LoadingContentData>,std::allocator<ExternalContentManager::LoadingContentData> > mLoadingContent;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  std::unique_ptr<ExternalContentManagerProxy> mProxy;
};

```

### `EDULibraryCategory`
```
struct __cppobj EDULibraryCategory
{
  std::string categoryLabel;
  std::string icon;
  std::string screenshot;
  std::array<float,3> defaultColor;
  std::array<float,3> interactColor;
  std::function<void __cdecl(std::shared_ptr<MainMenuScreenModel>)> interactCallback;
};

```

### `EventToSoundListMap`
```
struct __cppobj EventToSoundListMap
{
  std::unordered_map<enum LevelSoundEvent,std::unique_ptr<std::unordered_map<enum BlockSoundType,Sound>>> mEventToSoundListMap;
  float mVolumeMin;
  float mVolumeMax;
  float mPitchMin;
  float mPitchMax;
};

```

### `EDUConfigData`
```
const struct __cppobj EDUConfigData
{
  std::optional<DiscoveryConfig> discovery;
  EduConfigPreset preset;
  std::optional<DemoConfig> demo;
  std::string feedbackURLOverride;
};

```

### `ExternalServerFile`
```
struct __cppobj ExternalServerFile
{
  std::unordered_map<int,std::unique_ptr<ExternalServer>> mExternalServers;
  Core::PathBuffer<std::string > mExternalServersFilePath;
};

```

### `EmoticonManager`
```
struct __cppobj EmoticonManager
{
  std::string mListFilename;
  std::unordered_map<std::string,int> mStringToEmoticonMap;
};

```

### `EDUWorldsScreenCapabilities`
```
struct __cppobj __declspec(align(8)) EDUWorldsScreenCapabilities : TypedScreenCapabilities<EDUWorldsScreenCapabilities>
{
  bool mLocalWorldManagementEnabled;
};

```

### `EDUWorldsScreenCapabilities_vtbl`
```
struct /*VFT*/ EDUWorldsScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `ExtraLicenseData`
```
struct __cppobj ExtraLicenseData
{
  __int64 mValidationTime;
  __int64 mRetryUntilTime;
  __int64 mRetryAttempts;
};

```

### `EduTransactionHandler`
```
struct __cppobj EduTransactionHandler : TransactionHandler
{
  GameStore *mGameStore;
  PurchaseCache *mPurchaseCache;
};

```

### `EduTransactionHandler_vtbl`
```
struct /*VFT*/ EduTransactionHandler_vtbl
{
  void (__fastcall *~TransactionHandler)(TransactionHandler *this);
  void (__fastcall *update)(TransactionHandler *this);
  void (__fastcall *transactPurchase)(TransactionHandler *this, Offer *, TransactionContext *, PurchasePath);
  bool (__fastcall *transactFulfillment)(TransactionHandler *this, Offer *, std::shared_ptr<Purchase>, std::unique_ptr<TransactionContext>, PurchasePath);
};

```

### `EventCoordinator<UIEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<UIEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<UIEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<UIEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<ClientHitDetectListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ClientHitDetectListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ClientHitDetectListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ClientHitDetectListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EffectDisplayInfo`
```
struct __cppobj EffectDisplayInfo
{
  float mAnimation;
  RectangleArea mIconArea;
  RectangleArea mBackgroundArea;
};

```

### `EventCoordinator<ClientInstanceEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ClientInstanceEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ClientInstanceEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ClientInstanceEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<ServerInstanceEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ServerInstanceEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ServerInstanceEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ServerInstanceEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EncryptedProxyEnv`
```
struct __cppobj __declspec(align(8)) EncryptedProxyEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  const std::string mContentKey;
  const std::string mProductId;
  EncryptedProxyReadMode mMode;
};

```

### `EncryptedProxyEnv_vtbl`
```
struct /*VFT*/ EncryptedProxyEnv_vtbl
{
  void (__fastcall *~Env)(leveldb::Env *this);
  leveldb::Status *(__fastcall *NewSequentialFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::SequentialFile **);
  leveldb::Status *(__fastcall *NewRandomAccessFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::RandomAccessFile **);
  leveldb::Status *(__fastcall *NewWritableFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::WritableFile **);
  leveldb::Status *(__fastcall *NewAppendableFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::WritableFile **);
  bool (__fastcall *FileExists)(leveldb::Env *this, const std::string *);
  leveldb::Status *(__fastcall *GetChildren)(leveldb::Env *this, leveldb::Status *result, const std::string *, std::vector<std::string> *);
  leveldb::Status *(__fastcall *DeleteFileA)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *CreateDir)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *DeleteDir)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *GetFileSize)(leveldb::Env *this, leveldb::Status *result, const std::string *, unsigned __int64 *);
  leveldb::Status *(__fastcall *RenameFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, const std::string *);
  leveldb::Status *(__fastcall *LockFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::FileLock **);
  leveldb::Status *(__fastcall *UnlockFile)(leveldb::Env *this, leveldb::Status *result, leveldb::FileLock *);
  void (__fastcall *Schedule)(leveldb::Env *this, void (__fastcall *)(void *), void *);
  void (__fastcall *StartThread)(leveldb::Env *this, void (__fastcall *)(void *), void *);
  leveldb::Status *(__fastcall *GetTestDirectory)(leveldb::Env *this, leveldb::Status *result, std::string *);
  leveldb::Status *(__fastcall *NewLogger)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::Logger **);
  unsigned __int64 (__fastcall *NowMicros)(leveldb::Env *this);
  void (__fastcall *SleepForMicroseconds)(leveldb::Env *this, int);
};

```

### `EDUDiscovery::Button`
```
struct __cppobj __declspec(align(8)) EDUDiscovery::Button
{
  EDUDiscovery::LocKey mText;
  EDUDiscovery::ButtonAction mAction;
};

```

### `EDUDiscovery::QueryContext<enum EDUDiscovery::Availability>`
```
struct __cppobj EDUDiscovery::QueryContext<enum EDUDiscovery::Availability>
{
  std::function<void __cdecl(EDUDiscovery::QueryContext<enum EDUDiscovery::Availability> const &)> mOnComplete;
  std::function<void __cdecl(EDUDiscovery::QueryContext<enum EDUDiscovery::Availability> const &)> mOnCancel;
  _BYTE mCurrentState[1];
  int mStartTimeMS;
  gsl::basic_string_span<char const ,-1> mName;
  std::optional<EDUDiscovery::Error> mError;
  std::optional<EDUDiscovery::Dialog> mDialog;
  std::optional<int> mRetryAfterSeconds;
};

```

### `EDUDiscovery::ServerDetails`
```
struct __cppobj EDUDiscovery::ServerDetails
{
  std::string worldName;
  std::string playerName;
  std::string localIp;
  std::string externalIp;
  std::string passcode;
  int playerCount;
  int maxPlayers;
};

```

### `EDUDiscovery::ListServersResponse`
```
const struct __cppobj EDUDiscovery::ListServersResponse
{
  std::optional<EDUDiscovery::Error> error;
  std::optional<std::vector<EDUDiscovery::ServerDetails> > servers;
  bool hasMorePages;
  int totalPages;
};

```

### `EDUDiscovery::JoinRequest`
```
const struct __cppobj EDUDiscovery::JoinRequest
{
  std::string productId;
  EDUDiscovery::JoinCode code;
};

```

### `EDUDiscovery::JoinServerQueryState`
```
const struct __cppobj EDUDiscovery::JoinServerQueryState
{
  _BYTE status[1];
  std::optional<EDUDiscovery::Error> error;
  std::optional<EDUDiscovery::ServerDetails> server;
};

```

### `EDUDiscovery::DiscoveryObserver`
```
struct __cppobj EDUDiscovery::DiscoveryObserver : Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>
{
};

```

### `EDUDiscovery::ServerInvalidationDetails`
```
const struct __cppobj EDUDiscovery::ServerInvalidationDetails
{
  _BYTE source[1];
  EDUDiscovery::ServerInvalidationDetails::Reason reason;
};

```

### `EDUDiscovery::DiscoveryObserver_vtbl`
```
struct /*VFT*/ EDUDiscovery::DiscoveryObserver_vtbl
{
  void (__fastcall *~Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>)(Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onServerInvalidated)(EDUDiscovery::DiscoveryObserver *this, const EDUDiscovery::ServerInvalidationDetails *);
  void (__fastcall *onHeartbeat)(EDUDiscovery::DiscoveryObserver *this);
  void (__fastcall *onJoinCodeGenerated)(EDUDiscovery::DiscoveryObserver *this, const EDUDiscovery::JoinCode *);
  void (__fastcall *onCredentialsInvalidated)(EDUDiscovery::DiscoveryObserver *this);
};

```

### `EDUDiscovery::IpInfo`
```
struct __cppobj EDUDiscovery::IpInfo
{
  std::string ip;
  std::string port;
};

```

### `EDUSystems`
```
struct __cppobj EDUSystems
{
  std::shared_ptr<Social::MultiplayerEDU> mDiscovery;
  std::unique_ptr<ActiveDirectorySystem> mActiveDirectorySystem;
  std::unique_ptr<WebviewSystem> mWebviewSystem;
};

```

### `EntityAOIInfo`
```
struct __cppobj __declspec(align(8)) EntityAOIInfo
{
  AABB mAABB;
  std::unordered_set<ActorUniqueID> mIgnoredEntities;
  std::unordered_set<ActorUniqueID> mEntitiesInAOI;
  std::unordered_set<ActorUniqueID> mLastEntitiesInAOI;
  ActorType entityTypeId;
};

```

### `EventCoordinator<NetworkPacketEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<NetworkPacketEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<NetworkPacketEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<NetworkPacketEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventResponse`
```
struct __cppobj EventResponse
{
  EventResponse_vtbl *__vftable /*VFT*/;
};

```

### `EventResponse_vtbl`
```
struct /*VFT*/ EventResponse_vtbl
{
  void (__fastcall *~EventResponse)(EventResponse *this);
  const std::string *(__fastcall *getName)(EventResponse *this);
  void (__fastcall *executeAction)(EventResponse *this, RenderParams *);
  void (__fastcall *buildSchema)(EventResponse *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,EventResponseCollection> > *, const Factory<EventResponse> *);
};

```

### `EggComponent`
```
struct __cppobj EggComponent
{
  std::string mEntityName;
  const Item *mOwner;
  ActorDefinitionIdentifier mActorID;
};

```

### `EventCoordinator<PlayerEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<PlayerEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<PlayerEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<PlayerEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EnderChestContainer`
```
struct __cppobj EnderChestContainer : FillingContainer
{
  ChestBlockActor *activeChest;
};

```

### `EnderChestContainer_vtbl`
```
struct /*VFT*/ EnderChestContainer_vtbl
{
  void (__fastcall *~Container)(Container *this);
  void (__fastcall *init)(Container *this);
  void (__fastcall *serverInitItemStackIds)(Container *this, int, int, std::function<void __cdecl(int,ItemStack const &)>);
  void (__fastcall *addContentChangeListener)(Container *this, ContainerContentChangeListener *);
  void (__fastcall *removeContentChangeListener)(Container *this, ContainerContentChangeListener *);
  const ItemStack *(__fastcall *getItem)(Container *this, int);
  bool (__fastcall *hasRoomForItem)(Container *this, const ItemStack *);
  void (__fastcall *addItem)(Container *this, ItemStack *);
  bool (__fastcall *addItemToFirstEmptySlot)(Container *this, ItemStack *);
  void (__fastcall *setItem)(Container *this, int, const ItemStack *);
  void (__fastcall *setItemWithForceBalance)(Container *this, int, const ItemStack *, bool);
  void (__fastcall *removeItem)(Container *this, int, int);
  void (__fastcall *removeAllItems)(Container *this);
  void (__fastcall *dropContents)(Container *this, BlockSource *, const Vec3 *, bool);
  int (__fastcall *getContainerSize)(Container *this);
  int (__fastcall *getMaxStackSize)(Container *this);
  void (__fastcall *startOpen)(Container *this, Player *);
  void (__fastcall *stopOpen)(Container *this, Player *);
  std::vector<ItemStack> *(__fastcall *getSlotCopies)(Container *this, std::vector<ItemStack> *result);
  const std::vector<ItemStack const *> *(__fastcall *getSlots)(Container *this, const std::vector<ItemStack const *> *result);
  int (__fastcall *getItemCount)(Container *this, const ItemStack *);
  int (__fastcall *findFirstSlotForItem)(Container *this, const ItemStack *);
  bool (__fastcall *canPushInItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  bool (__fastcall *canPullOutItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  void (__fastcall *setContainerChanged)(Container *this, int);
  void (__fastcall *setContainerMoved)(Container *this);
  void (__fastcall *setCustomName)(Container *this, const std::string *);
  bool (__fastcall *hasCustomName)(Container *this);
  void (__fastcall *readAdditionalSaveData)(Container *this, const CompoundTag *);
  void (__fastcall *addAdditionalSaveData)(Container *this, CompoundTag *);
  void (__fastcall *createTransactionContext)(Container *this, std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>, std::function<void __cdecl(void)>);
  void (__fastcall *initializeContainerContents)(Container *this, BlockSource *);
  bool (__fastcall *reviewItems)(Container *this, Level *);
  bool (__fastcall *add)(FillingContainer *this, ItemStack *);
  bool (__fastcall *canAdd)(FillingContainer *this, const ItemStack *);
  void (__fastcall *clearSlot)(FillingContainer *this, int);
  int (__fastcall *clearInventory)(FillingContainer *this, int);
  void (__fastcall *load)(FillingContainer *this, const ListTag *, const SemVersion *, Level *);
  int (__fastcall *getEmptySlotsCount)(FillingContainer *this);
};

```

### `EventCoordinator<LevelEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<LevelEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<LevelEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<LevelEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EconomyTradeableDescription`
```
struct __cppobj __declspec(align(8)) EconomyTradeableDescription : ComponentDescription
{
  std::string mDisplayName;
  std::string mTradeTablePath;
  bool mUseNewTradeScreen;
  int mHeroDemandDiscount;
  IntRange mCuredDiscount;
  IntRange mMaxCuredDiscount;
  int mNearbyCuredDiscount;
  int mMaxNearbyCuredDiscount;
  bool mPersistTrades;
  bool mConvertTradesEconomy;
  bool mShowTradeScreen;
  bool mUseLegacyPrices;
};

```

### `EconomyTradeableDescription_vtbl`
```
struct /*VFT*/ EconomyTradeableDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `EntityComponentFactory`
```
struct __cppobj __declspec(align(8)) EntityComponentFactory
{
  std::unordered_map<HashedString,std::unique_ptr<IDefinitionSerializer>> mDefinitionSerializers;
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EventResponseFactory`
```
struct __cppobj EventResponseFactory : Factory<EventResponse>
{
  EventResponseFactory_vtbl *__vftable /*VFT*/;
  std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,EventResponseCollection> > mSchema;
};

```

### `EventResponseFactory_vtbl`
```
struct /*VFT*/ EventResponseFactory_vtbl
{
  void (__fastcall *~EventResponseFactory)(EventResponseFactory *this);
  void (__fastcall *initializeFactory)(EventResponseFactory *this, const Experiments *);
};

```

### `EventCoordinator<ActorEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ActorEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ActorEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ActorEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<BlockEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<BlockEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<BlockEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<BlockEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<ItemEventListener>`
```
struct __cppobj __declspec(align(8)) EventCoordinator<ItemEventListener> : Bedrock::EnableNonOwnerReferences
{
  std::vector<gsl::not_null<ItemEventListener *>> mListeners;
  std::vector<std::function<enum EventResult __cdecl(gsl::not_null<ItemEventListener *>)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EntityGoalFactory`
```
struct __cppobj EntityGoalFactory
{
  std::unordered_map<HashedString,std::unique_ptr<IDefinitionSerializer>> mDefinitionSerializers;
};

```

### `EntitySystems`
```
struct __cppobj EntitySystems
{
  std::vector<std::unique_ptr<ITickingSystem>> mTickingSystems;
  std::unique_ptr<PlayerInteractionSystem> mPlayerInteractionSystem;
};

```

### `EntityOptionalOwnerRef`
```
struct __cppobj EntityOptionalOwnerRef
{
  OwnerPtrT<EntityRefTraits> mOwnedEntity;
  WeakRefT<EntityRefTraits> mWeakEntity;
};

```

### `EquipmentTableDefinition`
```
const struct __cppobj EquipmentTableDefinition
{
  std::string mFilePath;
  std::vector<SlotDropChance> mDropChancesPerSlot;
};

```

### `EconomyTradeableComponent`
```
struct __cppobj EconomyTradeableComponent
{
  Player *mLastPlayerTradeName;
  int mUpdateMerchantTimer;
  bool mAddRecipeOnUpdate;
  int mRiches;
  Mob *mOwner;
  std::unique_ptr<MerchantRecipeList> mOffers;
  std::string mDisplayName;
  std::string mGeneratedTablePath;
  bool mConvertedFromVillagerV1;
  int mDiscountDegradationTimeStamp;
};

```

### `EntityFont`
```
struct __cppobj __declspec(align(8)) EntityFont
{
  std::string mStr;
  Vec3 mPos;
  float mSize;
  bool mDeepTest;
  mce::Color mTextColor;
  mce::Color mTagColor;
};

```

### `EntityRefTraits`
```
struct __cppobj EntityRefTraits
{
};

```

### `EntityRegistryRefTraits`
```
struct __cppobj EntityRegistryRefTraits
{
};

```

### `EntityConstRefTraits`
```
struct __cppobj EntityConstRefTraits
{
};

```

### `EntityRegistryConstRefTraits`
```
struct __cppobj EntityRegistryConstRefTraits
{
};

```

### `EnchantSlotEnumHasher`
```
struct __cppobj EnchantSlotEnumHasher
{
};

```

### `Enchant`
```
struct __cppobj __declspec(align(8)) Enchant
{
  Enchant_vtbl *__vftable /*VFT*/;
  const Enchant::Type mEnchantType;
  const Enchant::Frequency mFrequency;
  const bool mIsLootable;
  const int mPrimarySlots;
  const int mSecondarySlots;
  const int mCompatibility;
  const std::string mDescription;
  const HashedString mStringId;
  bool mIsDisabled;
};

```

### `Enchant_vtbl`
```
struct /*VFT*/ Enchant_vtbl
{
  void (__fastcall *~Enchant)(Enchant *this);
  bool (__fastcall *isCompatibleWith)(Enchant *this, Enchant::Type);
  int (__fastcall *getMinCost)(Enchant *this, int);
  int (__fastcall *getMaxCost)(Enchant *this, int);
  int (__fastcall *getMinLevel)(Enchant *this);
  int (__fastcall *getMaxLevel)(Enchant *this);
  int (__fastcall *getDamageProtection)(Enchant *this, int, const ActorDamageSource *);
  float (__fastcall *getDamageBonus)(Enchant *this, int, const Actor *);
  void (__fastcall *doPostAttack)(Enchant *this, Actor *, Actor *, int);
  void (__fastcall *doPostHurt)(Enchant *this, ItemInstance *, Actor *, Actor *, int);
  bool (__fastcall *isMeleeDamageEnchant)(Enchant *this);
  bool (__fastcall *isProtectionEnchant)(Enchant *this);
  bool (__fastcall *isTreasureOnly)(Enchant *this);
  bool (__fastcall *isDiscoverable)(Enchant *this);
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,LodestoneCompassComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,LodestoneCompassComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EduPurchaseDetails`
```
struct __cppobj EduPurchaseDetails
{
  bool foundPayload;
  std::string productSku;
  std::weak_ptr<Purchase> purchase;
};

```

### `EmptyProgressHandler`
```
struct __cppobj EmptyProgressHandler : ProgressHandler
{
};

```

### `EmptyProgressHandler_vtbl`
```
struct /*VFT*/ EmptyProgressHandler_vtbl
{
  void (__fastcall *~ProgressHandler)(ProgressHandler *this);
  void (__fastcall *onStart)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *tick)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onCancel)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onExit)(ProgressHandler *this, MinecraftScreenModel *);
  LoadingState (__fastcall *getLoadingState)(ProgressHandler *this, MinecraftScreenModel *);
  float (__fastcall *getLoadingProgress)(ProgressHandler *this, MinecraftScreenModel *);
  std::string *(__fastcall *getProgressMessage)(ProgressHandler *this, std::string *result, MinecraftScreenModel *);
  void (__fastcall *addEventProperties)(ProgressHandler *this, std::unordered_map<std::string,std::string> *);
  std::string *(__fastcall *getTTSProgressMessage)(ProgressHandler *this, std::string *result);
  std::string *(__fastcall *getTitleText)(ProgressHandler *this, std::string *result);
  ProgressAnimation (__fastcall *showLoadingBar)(ProgressHandler *this);
};

```

### `EmulatedScreenSize`
```
struct __cppobj __declspec(align(8)) EmulatedScreenSize
{
  const int w;
  const int h;
  const UIScalingRules scalingRules;
  const std::string desc;
  const int dpi;
};

```

### `EduContentCustom`
```
struct __cppobj __declspec(align(8)) EduContentCustom
{
  std::string mCreatorName;
  int mCompletionTime;
  int mMinAge;
  int mMaxAge;
  std::string mObjectives;
  std::string mLearningObjectives;
  std::string mVideoLink;
  std::string mWebLink;
  std::string mTeacherNotes;
  std::string mAssessment;
  std::string mStudentActivities;
  std::string mExtensions;
  std::string mEssentialQuestions;
  std::string mDifficulty;
  float mFileSizeMB;
};

```

### `EduContentDocument`
```
struct __cppobj EduContentDocument
{
  CommonDocument mCommon;
  EduContentCustom mCustom;
};

```

### `EduContentSearchResults`
```
const struct __cppobj EduContentSearchResults : CommonSearchResults
{
  std::vector<EduContentDocument> mDocuments;
};

```

### `EnchantUtils`
```
struct __cppobj EnchantUtils
{
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,BlockGeometryComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,BlockGeometryComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,BlockUnitCubeComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,BlockUnitCubeComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,BlockMaterialInstancesComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,BlockMaterialInstancesComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EventRegistrationToken`
```
struct EventRegistrationToken
{
  __int64 value;
};

```

### `EasyThread_vtbl`
```
struct /*VFT*/ EasyThread_vtbl
{
  void (__fastcall *~EasyThread)(EasyThread *this);
};

```

### `Easing`
```
struct __cppobj Easing
{
};

```

### `EnableEncryptionCommand`
```
struct __cppobj EnableEncryptionCommand : Command
{
  std::string mPublicKey;
  std::string mSalt;
};

```

### `EnableEncryptionCommand_vtbl`
```
struct /*VFT*/ EnableEncryptionCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `EduAppConfigs`
```
struct __cppobj EduAppConfigs : DataBackedAppConfigs
{
  std::vector<char> mGlobalKey;
};

```

### `EduAppConfigs_vtbl`
```
struct /*VFT*/ EduAppConfigs_vtbl
{
  void (__fastcall *~AppConfigs)(AppConfigs *this);
  void (__fastcall *loadFromData)(AppConfigs *this, const IAppConfigData *);
  bool (__fastcall *areResourcePacksAllowed)(AppConfigs *this);
  bool (__fastcall *isPlayScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isChatScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isGameTabShownInSettings)(AppConfigs *this);
  bool (__fastcall *areQuizzesSupported)(AppConfigs *this);
  bool (__fastcall *isLessonProgressionSupported)(AppConfigs *this);
  bool (__fastcall *useNormalizedFontSize)(AppConfigs *this);
  bool (__fastcall *useFullScreenByDefault)(AppConfigs *this);
  bool (__fastcall *muteByDefault)(AppConfigs *this);
  bool (__fastcall *isCoursesCacheEnabled)(AppConfigs *this);
  bool (__fastcall *shouldPromptBeforeExit)(AppConfigs *this);
  bool (__fastcall *gameArgumentsNeedAuthentication)(AppConfigs *this);
  bool (__fastcall *worldBuilderDisabled)(AppConfigs *this);
  bool (__fastcall *worldsAreSingleUse)(AppConfigs *this);
  EducationEditionOffer (__fastcall *getEducationEditionOffering)(AppConfigs *this);
  bool (__fastcall *requireTrustedContent)(AppConfigs *this);
  ConnectionDefinition *(__fastcall *getConnectionDefinition)(AppConfigs *this, ConnectionDefinition *result);
  bool (__fastcall *supportsChangingMultiplayerDuringPlay)(AppConfigs *this);
  bool (__fastcall *webSocketsDisabled)(AppConfigs *this);
  bool (__fastcall *sendPermissionsTelemetry)(AppConfigs *this);
  void (__fastcall *setCanAccessWorldCallback)(AppConfigs *this, IMinecraftGame *);
  std::vector<PackIdVersion> *(__fastcall *getAdditionalClientPacks)(AppConfigs *this, std::vector<PackIdVersion> *result, bool);
  std::unique_ptr<IScreenCapabilities> *(__fastcall *getScreenCapabilities)(AppConfigs *this, std::unique_ptr<IScreenCapabilities> *result, const std::string *);
  std::unique_ptr<IContentAccessibilityProvider> *(__fastcall *createContentAccessibility)(AppConfigs *this, std::unique_ptr<IContentAccessibilityProvider> *result, IEntitlementManager *);
  std::string *(__fastcall *getFeedbackURL)(AppConfigs *this, std::string *result);
  void (__fastcall *applyLevelDataOverride)(AppConfigs *this, LevelData *);
};

```

### `EduConfigDataWrapper`
```
struct __cppobj EduConfigDataWrapper : AppConfigData<EduConfigDataWrapper>
{
  const EDUConfigData *mDataView;
  IMinecraftEventing *mEventing;
  ADRole mRole;
  std::string mOid;
};

```

### `EduConfigDataWrapper_vtbl`
```
struct /*VFT*/ EduConfigDataWrapper_vtbl
{
  void (__fastcall *~IAppConfigData)(IAppConfigData *this);
  typeid_t<IAppConfigData> *(__fastcall *getType)(IAppConfigData *this, typeid_t<IAppConfigData> *result);
};

```

### `EduChinaArguments`
```
struct __cppobj EduChinaArguments : UriListener
{
  ToastManager *mToastManager;
};

```

### `EduChinaArguments_vtbl`
```
struct /*VFT*/ EduChinaArguments_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,ClientSkin>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,ClientSkin>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,AudioEmitterComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,AudioEmitterComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,ClientParticleTrackingComponent,ClientParticleTerminationComponent,ActorComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,ClientParticleTrackingComponent,ClientParticleTerminationComponent,ActorComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,ClientParticleInitializationComponent,ActorComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,ClientParticleInitializationComponent,ActorComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityClientPacket`
```
struct __cppobj __declspec(align(8)) EntityClientPacket : Packet
{
  EntityNetId mEntityNetId;
};

```

### `EntityClientPacket_vtbl`
```
struct /*VFT*/ EntityClientPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `EntityPlacerItemComponent`
```
struct __cppobj EntityPlacerItemComponent : ItemComponent
{
  ActorDefinitionIdentifier mIdentifier;
  std::vector<BlockDescriptor> mAllowedUseBlocks;
  std::vector<BlockDescriptor> mAllowedDispenseBlocks;
};

```

### `EntityPlacerItemComponent_vtbl`
```
struct /*VFT*/ EntityPlacerItemComponent_vtbl
{
  void (__fastcall *~ItemComponent)(ItemComponent *this);
  bool (__fastcall *checkComponentDataForContentErrors)(ItemComponent *this);
  void (__fastcall *writeSettings)(ItemComponent *this);
  bool (__fastcall *useOn)(ItemComponent *this, ItemStack *, Actor *, const BlockPos *, unsigned __int8, const Vec3 *);
  bool (__fastcall *isNetworkComponent)(ItemComponent *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(ItemComponent *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(ItemComponent *this, const CompoundTag *);
};

```

### `ExtendedCertificate`
```
struct __cppobj ExtendedCertificate
{
};

```

### `EDUSystems::onInitFinished::__l2::<lambda_77c3045325987d477e1bd283e031efde>`
```
struct __cppobj EDUSystems::onInitFinished::__l2::<lambda_77c3045325987d477e1bd283e031efde>
{
  LevelListCache *levelCache;
};

```

### `EDUSystems::onInitFinished::__l2::<lambda_461b33e77e7cf207dd0cf06f5654c847>`
```
struct __cppobj EDUSystems::onInitFinished::__l2::<lambda_461b33e77e7cf207dd0cf06f5654c847>
{
  ResourcePackManager *packManager;
  SceneStack *sceneStack;
  SceneFactory *sceneFactory;
};

```

### `EnchantingBookModel`
```
struct __cppobj EnchantingBookModel : Model
{
  bool mIsOnLectern;
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mBook[7];
};

```

### `EnchantingBookModel_vtbl`
```
struct /*VFT*/ EnchantingBookModel_vtbl
{
  void (__fastcall *~AppPlatformListener)(AppPlatformListener *this);
  void (__fastcall *onLowMemory)(AppPlatformListener *this);
  void (__fastcall *onAppPaused)(AppPlatformListener *this);
  void (__fastcall *onAppUnpaused)(AppPlatformListener *this);
  void (__fastcall *onAppPreSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppResumed)(AppPlatformListener *this);
  void (__fastcall *onAppFocusLost)(AppPlatformListener *this);
  void (__fastcall *onAppFocusGained)(AppPlatformListener *this);
  void (__fastcall *onAppTerminated)(AppPlatformListener *this);
  void (__fastcall *onOperationModeChanged)(AppPlatformListener *this, const OperationMode);
  void (__fastcall *onPerformanceModeChanged)(AppPlatformListener *this, const bool);
  void (__fastcall *onPushNotificationReceived)(AppPlatformListener *this, const PushNotificationMessage *);
  void (__fastcall *onResizeBegin)(AppPlatformListener *this);
  void (__fastcall *onResizeEnd)(AppPlatformListener *this);
  void (__fastcall *onDeviceLost)(AppPlatformListener *this);
  void (__fastcall *clear)(Model *this);
  void (__fastcall *preDraw)(Model *this, ScreenContext *);
  void (__fastcall *postDraw)(Model *this, ScreenContext *);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *);
  void (__fastcall *render)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, ScreenContext *);
  void (__fastcall *setupAnim)(Model *this);
  void (__fastcall *setupAnim)(Model *this, float, float, float, float, float, float);
  void (__fastcall *prepareMobModel)(Model *this, Mob *, float, float, float);
  Vec3 *(__fastcall *getLeashOffsetPosition)(Model *this, Vec3 *result, bool);
  void (__fastcall *renderAniModel)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  void (__fastcall *renderMod)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *youngTransform)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  float (__fastcall *getHeightAdjustment)(Model *this);
  AABB *(__fastcall *buildAABB)(Model *this, AABB *result);
};

```

### `EnchantingBookRenderer`
```
struct __cppobj __declspec(align(8)) EnchantingBookRenderer : MinecraftUICustomRenderer, ActorShaderManager
{
  std::unique_ptr<EnchantingBookModel> mBook;
  bool mPrevOpen;
  float mFlip;
  float mOFlip;
  float mFlipT;
  float mFlipA;
  float mOpen;
  float mOOpen;
};

```

### `EnchantingBookRenderer_vtbl`
```
struct /*VFT*/ EnchantingBookRenderer_vtbl
{
  void (__fastcall *~UICustomRenderer)(UICustomRenderer *this);
  void (__fastcall *preRenderSetup)(UICustomRenderer *this, UIRenderContext *);
  std::shared_ptr<UICustomRenderer> *(__fastcall *clone)(UICustomRenderer *this, std::shared_ptr<UICustomRenderer> *result);
  bool (__fastcall *update)(UICustomRenderer *this, IClientInstance *, UIControl *, const UIScene *);
  void (__fastcall *frameUpdate)(UICustomRenderer *this, UIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(UICustomRenderer *this, UIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  UIBatchType (__fastcall *getBatchType)(UICustomRenderer *this);
  int (__fastcall *getCustomId)(UICustomRenderer *this);
  int (__fastcall *getNumRenderPasses)(UICustomRenderer *this);
  ResourceLocation *(__fastcall *getResourceLocation)(UICustomRenderer *this, ResourceLocation *result, int, int);
  UIMaterialType (__fastcall *getUIMaterialType)(UICustomRenderer *this, int);
  bool (__fastcall *getRequiresPreRenderSetup)(UICustomRenderer *this, int);
  void (__fastcall *onVisibilityChanged)(UICustomRenderer *this, bool);
  void (__fastcall *collectScreenEvents)(UICustomRenderer *this, std::queue<ScreenEvent> *);
  void (__fastcall *frameUpdate)(MinecraftUICustomRenderer *this, MinecraftUIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  void (__fastcall *preRenderSetup)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *);
};

```

### `EmptyChunkSource`
```
struct __cppobj EmptyChunkSource : ChunkSource
{
};

```

### `EmptyChunkSource_vtbl`
```
struct /*VFT*/ EmptyChunkSource_vtbl
{
  void (__fastcall *~ChunkSource)(ChunkSource *this);
  void (__fastcall *shutdown)(ChunkSource *this);
  bool (__fastcall *isShutdownDone)(ChunkSource *this);
  std::shared_ptr<LevelChunk> *(__fastcall *getExistingChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *);
  std::shared_ptr<LevelChunk> *(__fastcall *getRandomChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, Random *);
  std::shared_ptr<LevelChunk> *(__fastcall *createNewChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  std::shared_ptr<LevelChunk> *(__fastcall *getOrLoadChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  bool (__fastcall *postProcess)(ChunkSource *this, ChunkViewSource *);
  void (__fastcall *checkAndReplaceChunk)(ChunkSource *this, ChunkViewSource *, LevelChunk *);
  void (__fastcall *loadChunk)(ChunkSource *this, LevelChunk *, bool);
  void (__fastcall *postProcessMobsAt)(ChunkSource *this, BlockSource *, int, int, Random *);
  bool (__fastcall *saveLiveChunk)(ChunkSource *this, LevelChunk *);
  void (__fastcall *hintDiscardBatchBegin)(ChunkSource *this);
  void (__fastcall *hintDiscardBatchEnd)(ChunkSource *this);
  void (__fastcall *acquireDiscarded)(ChunkSource *this, std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>);
  void (__fastcall *compact)(ChunkSource *this);
  void (__fastcall *flushPendingWrites)(ChunkSource *this);
  bool (__fastcall *isWithinWorldLimit)(ChunkSource *this, const ChunkPos *);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getChunkMap)(ChunkSource *this);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getStorage)(ChunkSource *this);
  void (__fastcall *clearDeletedEntities)(ChunkSource *this);
  void (__fastcall *removeDimensionData)(ChunkSource *this, const std::unordered_set<AutomaticID<Dimension,int>> *);
  bool (__fastcall *hasChunk)(ChunkSource *this, const ChunkPos *, AutomaticID<Dimension,int>);
  bool (__fastcall *canCreateViews)(ChunkSource *this);
};

```

### `EduTransactionContext`
```
struct __cppobj EduTransactionContext : TransactionContext
{
  std::shared_ptr<MinecraftScreenModel> mMinecraftScreenModel;
};

```

### `EducationContentManagerScreenController`
```
struct __cppobj __declspec(align(8)) EducationContentManagerScreenController : MainMenuScreenController
{
  std::shared_ptr<PlayScreenModel> mPlayScreenModel;
  std::function<void __cdecl(void)> mOnDownloadError;
  bool mIsDownloadInProgress;
  std::shared_ptr<WorldFileDownloadManager> mWorldFileDownloadManager;
  ResourcePackRepository *mResourcePackRepository;
  ResourcePackManager *mResourcePackManager;
  IMinecraftEventing *mEventing;
  ToastManager *mToastManager;
  _BYTE mOptionalBehavior[4];
};

```

### `EducationContentManagerScreenController_vtbl`
```
struct /*VFT*/ EducationContentManagerScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `ExpandoContainerModel`
```
struct __cppobj ExpandoContainerModel : ContainerModel
{
  std::vector<std::pair<ItemInstance,unsigned int>> mItems;
  std::vector<ExpandoModelElement> mCurrentItems;
  std::vector<ExpandoModelElement> mExpandedItems;
  std::function<void __cdecl(std::string const &,int,int)> mOnItemExpanded;
};

```

### `ExpandoModelElement`
```
struct __cppobj ExpandoModelElement
{
  const ItemInstance item;
  ContainerExpandStatus status;
  std::string groupName;
};

```

### `ExpandoContainerModel_vtbl`
```
struct /*VFT*/ ExpandoContainerModel_vtbl
{
  void (__fastcall *containerContentChanged)(ContainerContentChangeListener *this, int);
  void (__fastcall *~ContainerContentChangeListener)(ContainerContentChangeListener *this);
  void (__fastcall *containerAddCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *containerRemoveCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *postInit)(ContainerModel *this);
  void (__fastcall *releaseResources)(ContainerModel *this);
  int (__fastcall *getContainerSize)(ContainerModel *this);
  int (__fastcall *getFilteredContainerSize)(ContainerModel *this);
  void (__fastcall *tick)(ContainerModel *this, int);
  ContainerWeakRef *(__fastcall *getContainerWeakRef)(ContainerModel *this, ContainerWeakRef *result);
  const ItemStack *(__fastcall *getItemStack)(ContainerModel *this, int);
  const std::vector<ItemStack> *(__fastcall *getItems)(ContainerModel *this);
  const ItemInstance *(__fastcall *getItemInstance)(ContainerModel *this, int);
  const ItemStackBase *(__fastcall *getItemStackBase)(ContainerModel *this, int);
  bool (__fastcall *isItemInstanceBased)(ContainerModel *this);
  void (__fastcall *setItem)(ContainerModel *this, int, const ItemStack *);
  bool (__fastcall *isValid)(ContainerModel *this);
  bool (__fastcall *isItemFiltered)(ContainerModel *this, const ItemStackBase *);
  bool (__fastcall *isExpanableItemFiltered)(ContainerModel *this, int);
  ContainerExpandStatus (__fastcall *getItemExpandStatus)(ContainerModel *this, int);
  const std::string *(__fastcall *getItemGroupName)(ContainerModel *this, int);
  void (__fastcall *switchItemExpando)(ContainerModel *this, int);
  Container *(__fastcall *_getContainer)(ContainerModel *this);
  int (__fastcall *_getContainerOffset)(ContainerModel *this);
  void (__fastcall *_onItemChanged)(ContainerModel *this, int, const ItemStack *, const ItemStack *);
  void (__fastcall *setItemInstance)(ExpandoContainerModel *this, int, const ItemInstance *);
  void (__fastcall *refreshContainer)(ExpandoContainerModel *this, bool);
};

```

### `EDUDiscoveryDialogScreenController`
```
struct __cppobj EDUDiscoveryDialogScreenController : MinecraftScreenController
{
  std::unique_ptr<EDUDiscovery::Dialog> mDialog;
  EDUDiscoveryDialogCallbacks mCallbacks;
};

```

### `EDUDiscoveryDialogScreenController_vtbl`
```
struct /*VFT*/ EDUDiscoveryDialogScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EDULibraryCategoryScreenController`
```
struct __cppobj EDULibraryCategoryScreenController : MainMenuScreenController
{
  bool mFirstPage;
  std::string mTitle;
  std::string mIcon;
  std::string mDescription;
  std::string mScreenshotRatio;
  int mColumnCount;
  std::vector<EDULibraryCategory> mLibraryCategories;
};

```

### `EDULibraryCategoryScreenController_vtbl`
```
struct /*VFT*/ EDULibraryCategoryScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EDUPlayScreenController`
```
struct __cppobj EDUPlayScreenController : MainMenuScreenController
{
  std::shared_ptr<PlayScreenModel> mPlayScreenModel;
};

```

### `EDUPlayScreenController_vtbl`
```
struct /*VFT*/ EDUPlayScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EDUWorldsScreenController`
```
struct __cppobj EDUWorldsScreenController : MainMenuScreenController
{
  std::shared_ptr<PlayScreenModel> mPlayScreenModel;
  bool mMatchedWorldsNeedsRefresh;
  std::string mSearchString;
  std::vector<unsigned __int64> mMatchedWorlds;
};

```

### `EDUWorldsScreenController_vtbl`
```
struct /*VFT*/ EDUWorldsScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_72b8559641fed335663090d0216e99d8>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_72b8559641fed335663090d0216e99d8>
{
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_9ebe712e0aa58c94ee76aa52bc5044de>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_9ebe712e0aa58c94ee76aa52bc5044de>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_63646580417928ef509c55e1c9c03706>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_63646580417928ef509c55e1c9c03706>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_75b25835c8c8ece787f838e19b7887d1>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_75b25835c8c8ece787f838e19b7887d1>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_199ebc283e58abda08377d8e7184d4d8>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_199ebc283e58abda08377d8e7184d4d8>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_cdaa454dd1cac4fe3b83b17f1e6b3287>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_cdaa454dd1cac4fe3b83b17f1e6b3287>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerBindings::__l2::<lambda_2827205e97f71d06080243c4d3b1ec45>`
```
struct __cppobj EDUWorldsScreenController::_registerBindings::__l2::<lambda_2827205e97f71d06080243c4d3b1ec45>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_61cc37f07d56687219e23ce2cbe7fd10>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_61cc37f07d56687219e23ce2cbe7fd10>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_a912fdeb011409482b8297abf979a179>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_a912fdeb011409482b8297abf979a179>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_a912fdeb011409482b8297abf979a179>::()::__l2::<lambda_648b1dfb472426689ff41f94cd975b3d>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_a912fdeb011409482b8297abf979a179>::()::__l2::<lambda_648b1dfb472426689ff41f94cd975b3d>
{
  std::weak_ptr<EDUWorldsScreenController> weakThis;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_96e0cd59206c7640227561f3104622e2>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_96e0cd59206c7640227561f3104622e2>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_187fc86fa95ca74c9f5dfd1126d08f60>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_187fc86fa95ca74c9f5dfd1126d08f60>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_2e9b3eb765153a4c12fa3d490ff245c3>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_2e9b3eb765153a4c12fa3d490ff245c3>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_656f5fd20f7a7b58d30b69f74d48261c>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_656f5fd20f7a7b58d30b69f74d48261c>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_656f5fd20f7a7b58d30b69f74d48261c>::()::__l2::<lambda_b1790b3a636c822ab51081d6aa23ffd3>`
```
struct __cppobj EDUWorldsScreenController::_registerEventHandlers::__l2::<lambda_656f5fd20f7a7b58d30b69f74d48261c>::()::__l2::<lambda_b1790b3a636c822ab51081d6aa23ffd3>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_72c2aa5b3fcdcc8a179841945aee69fb>`
```
struct __cppobj EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_72c2aa5b3fcdcc8a179841945aee69fb>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_a02a071db15bff20263f4afd3873e15a>`
```
struct __cppobj EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_a02a071db15bff20263f4afd3873e15a>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_226ed66e6ad0e5e23deb061579c48738>`
```
struct __cppobj EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_226ed66e6ad0e5e23deb061579c48738>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_d682447ef0745dab2a111f9636b05529>`
```
struct __cppobj EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_d682447ef0745dab2a111f9636b05529>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_4e13de7623448659e7e3dc697e7692aa>`
```
struct __cppobj EDUWorldsScreenController::_registerControllerCallbacks::__l5::<lambda_4e13de7623448659e7e3dc697e7692aa>
{
  EDUWorldsScreenController *const __this;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_d07bf21238f4de8b5a3ef268404821bb>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_d07bf21238f4de8b5a3ef268404821bb>
{
  EDUPlayScreenController *const __this;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_d07bf21238f4de8b5a3ef268404821bb>::()::__l2::<lambda_a5f7f5abaf35bcb60a635e4cc60eed2a>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_d07bf21238f4de8b5a3ef268404821bb>::()::__l2::<lambda_a5f7f5abaf35bcb60a635e4cc60eed2a>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_ac9c05bb3ca2a72ed2d1dabe9d309434>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_ac9c05bb3ca2a72ed2d1dabe9d309434>
{
  EDUPlayScreenController *const __this;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_431ecfcc7b273b4b3283b98f58910611>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_431ecfcc7b273b4b3283b98f58910611>
{
  EDUPlayScreenController *const __this;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_431ecfcc7b273b4b3283b98f58910611>::()::__l2::<lambda_74714286228d4caa38a683b25d727c14>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_431ecfcc7b273b4b3283b98f58910611>::()::__l2::<lambda_74714286228d4caa38a683b25d727c14>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_6e78757d16c625f4b531b2dcbe113bc7>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_6e78757d16c625f4b531b2dcbe113bc7>
{
  EDUPlayScreenController *const __this;
};

```

### `EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_e20381e6ec567d4b7767f16e95c69e9e>`
```
struct __cppobj EDUPlayScreenController::_registerEventHandlers::__l2::<lambda_e20381e6ec567d4b7767f16e95c69e9e>
{
  EDUPlayScreenController *const __this;
};

```

### `EDUPlayScreenController::onEntered::__l2::<lambda_bf8996f916f2865314413ea540963776>`
```
struct __cppobj EDUPlayScreenController::onEntered::__l2::<lambda_bf8996f916f2865314413ea540963776>
{
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_8e7cbea35df2d841cd13a0f9b592558a>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_8e7cbea35df2d841cd13a0f9b592558a>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_63cd69f700e011c42b90f5a44071427f>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_63cd69f700e011c42b90f5a44071427f>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_ba9febdf2ceff8a9a076ed393d49c3a3>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_ba9febdf2ceff8a9a076ed393d49c3a3>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_480f7400aa5e44b4a7ecdc1d2509e1f4>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_480f7400aa5e44b4a7ecdc1d2509e1f4>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_d9db21243ea37138e5e380b4e6f67d3c>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_d9db21243ea37138e5e380b4e6f67d3c>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_a47d05d7778aacbad4bccfbe2de2463c>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_a47d05d7778aacbad4bccfbe2de2463c>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_d96a3567a5a3d95f6c707c8c85ebd64a>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerBindings::__l2::<lambda_d96a3567a5a3d95f6c707c8c85ebd64a>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerEventHandlers::__l2::<lambda_6a141037d0c2ee7eedb044757bb7ea32>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerEventHandlers::__l2::<lambda_6a141037d0c2ee7eedb044757bb7ea32>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerEventHandlers::__l2::<lambda_bc0369127833a1d79c87f5f94b1d49e6>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerEventHandlers::__l2::<lambda_bc0369127833a1d79c87f5f94b1d49e6>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_4a156165a33db633dd4765a222f064ee>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_4a156165a33db633dd4765a222f064ee>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_7e07a3c1a4197531facebc29df73bd63>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_7e07a3c1a4197531facebc29df73bd63>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_eabcbe6d3d205b599d6d34e5b83964e0>`
```
struct __cppobj EDULibraryCategoryScreenController::_registerControllerCallbacks::__l2::<lambda_eabcbe6d3d205b599d6d34e5b83964e0>
{
  EDULibraryCategoryScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_c55722cce6299c92c0601f68730afebb>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_c55722cce6299c92c0601f68730afebb>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_868386b196cf17ca76dc6538307bba55>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_868386b196cf17ca76dc6538307bba55>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_9d8d0e4ddcf6f36979ecde4bcafd4620>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_9d8d0e4ddcf6f36979ecde4bcafd4620>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_ae340a68b4a67dfbab04a76ff2258605>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_ae340a68b4a67dfbab04a76ff2258605>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_3e0c414a4ae4ab0c32e630486effb2d2>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerBindings::__l2::<lambda_3e0c414a4ae4ab0c32e630486effb2d2>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerEventHandlers::__l2::<lambda_8b389c442c333ed04d89a2035539863a>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerEventHandlers::__l2::<lambda_8b389c442c333ed04d89a2035539863a>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EDUDiscoveryDialogScreenController::_registerEventHandlers::__l2::<lambda_2dfa08ba3352d45be3b47fc49b6a2edb>`
```
struct __cppobj EDUDiscoveryDialogScreenController::_registerEventHandlers::__l2::<lambda_2dfa08ba3352d45be3b47fc49b6a2edb>
{
  EDUDiscoveryDialogScreenController *const __this;
};

```

### `EducationContentManagerScreenController::tick::__l15::<lambda_ca96e4a71e1891f87bdeea0007fdeac4>`
```
struct __cppobj EducationContentManagerScreenController::tick::__l15::<lambda_ca96e4a71e1891f87bdeea0007fdeac4>
{
  EducationContentManagerScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController`
```
struct __cppobj EDUWorldTemplatesScreenController : MainMenuScreenController
{
  std::shared_ptr<PlayScreenModel> mPlayScreenModel;
  std::shared_ptr<LibraryCollection> mLibraryCollection;
  bool mScreenNeedsRefresh;
  std::string mSearchString;
  std::vector<unsigned __int64> mMatchedTemplates;
};

```

### `EDUWorldTemplatesScreenController_vtbl`
```
struct /*VFT*/ EDUWorldTemplatesScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EmoteDescription`
```
struct __cppobj EmoteDescription
{
  std::string displayName;
  std::string emoteName;
  std::string imageName;
  std::string hoverImageName;
};

```

### `EmoteWheelScreenModel`
```
struct __cppobj EmoteWheelScreenModel : ClientInstanceScreenModel, PersonaScreenModelCommon
{
};

```

### `EmoteWheelScreenModel_vtbl`
```
struct /*VFT*/ EmoteWheelScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `EmoteWheelScreenController`
```
struct __cppobj EmoteWheelScreenController : ClientInstanceScreenController
{
  PersonaPiece mHoveredEmote;
  int mHoverIndex;
  int mHoverSlotIndex;
  bool mRebinding;
  LocalPlayer *mLocalPlayer;
  std::shared_ptr<EmoteWheelScreenModel> mEmoteWheelScreenModel;
  persona::PersonaPieceCollectionModel *mPersonaPieceCollectionModel;
};

```

### `EmoteWheelScreenController_vtbl`
```
struct /*VFT*/ EmoteWheelScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `EncryptionWarningScreenController`
```
struct __cppobj EncryptionWarningScreenController : MinecraftScreenController
{
  std::function<void __cdecl(bool)> mCallback;
};

```

### `EncryptionWarningScreenController_vtbl`
```
struct /*VFT*/ EncryptionWarningScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `ExpandedSkinPackScreenController`
```
struct __cppobj __declspec(align(8)) ExpandedSkinPackScreenController : PurchaseEnabledScreenController
{
  SkinPackCollectionModel *mSkinPackCollection;
  SkinPackModel *mSkinPackModel;
  SkinHandle mPreviewSkinHandle;
  const SkinHandle mInitialSkinHandle;
  int mHoverSkin;
  bool mForceSkinUpdate;
  bool mContentAreaActive;
  bool mRightSideVisible;
  bool mLeftSideVisible;
  bool mShouldCheckOwnedStatus;
};

```

### `ExpandedSkinPackScreenController_vtbl`
```
struct /*VFT*/ ExpandedSkinPackScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
  int (__fastcall *_getRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getColIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getLastRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getRemainderOffers)(StoreBaseScreenController *this, const int);
  void (__fastcall *onCatalogStatusUpdated)(PurchaseEnabledScreenController *this);
};

```

### `EncryptionWarningScreenController::onOpen::__l2::<lambda_5d7227e1150a07221cbd6b175f20947b>`
```
struct __cppobj EncryptionWarningScreenController::onOpen::__l2::<lambda_5d7227e1150a07221cbd6b175f20947b>
{
  std::weak_ptr<EncryptionWarningScreenController> weakThis;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_e40b4c8cee2f75e9485f3b99ff8fe9f9>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_e40b4c8cee2f75e9485f3b99ff8fe9f9>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_9c69ef1c095c1d1cbbec445705751599>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_9c69ef1c095c1d1cbbec445705751599>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_1a0dcc63acf5b0d8a99833aac9fc7e60>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_1a0dcc63acf5b0d8a99833aac9fc7e60>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_427d7b71706305f13048a5fe4581fce4>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_427d7b71706305f13048a5fe4581fce4>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_aee684a44a7c6f72d7de741e129d57b2>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_aee684a44a7c6f72d7de741e129d57b2>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_a81f69739e20c5a75b6b6a2c681ccd1d>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_a81f69739e20c5a75b6b6a2c681ccd1d>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_64835fabbce370036b36ebdfa0480f81>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_64835fabbce370036b36ebdfa0480f81>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_21809282fc6ba4e5af3884b5928bc9f0>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_21809282fc6ba4e5af3884b5928bc9f0>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_8ed2f29fdb8a9d68e6957e4ab3eb98c4>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_8ed2f29fdb8a9d68e6957e4ab3eb98c4>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_1815f00f1f2243613f43e1709d8e8dec>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_1815f00f1f2243613f43e1709d8e8dec>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_30d3e9adf3a6a4fcc649570af626fb20>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_30d3e9adf3a6a4fcc649570af626fb20>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_4712ae56bb8eb612d2db4603f4c90f8d>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_4712ae56bb8eb612d2db4603f4c90f8d>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_e67b0ba20d7524cb806cd920d6805ca4>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerBindings::__l2::<lambda_e67b0ba20d7524cb806cd920d6805ca4>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_2b4c8666da19bf3effc0b6becfb77855>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_2b4c8666da19bf3effc0b6becfb77855>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_bffca1b8bce1052cb05cc242e7ff834d>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_bffca1b8bce1052cb05cc242e7ff834d>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>`
```
struct __cppobj __declspec(align(8)) EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>
{
  EDUWorldTemplatesScreenController *const __this;
  WorldTemplateInfo *templateInfo;
  _BYTE collectionType[1];
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>::()::__l5::<lambda_85fffe3813154453c244e0893cec1f15>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>::()::__l5::<lambda_85fffe3813154453c244e0893cec1f15>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>::()::__l5::<lambda_9262aa5b3077a8ae30409ef4d1bbc82c>`
```
struct __cppobj __declspec(align(8)) EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_8217a43c37cd136393a1a027f20dc5e2>::()::__l8::<lambda_818718e7780c8cfe0befed57d67370df>::()::__l5::<lambda_9262aa5b3077a8ae30409ef4d1bbc82c>
{
  EDUWorldTemplatesScreenController *const __this;
  WorldTemplateInfo *templateInfo;
  _BYTE collectionType[1];
};

```

### `EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_37d7658173d03ec49fa15bdc29f22d9e>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerEventHandlers::__l2::<lambda_37d7658173d03ec49fa15bdc29f22d9e>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerNestedControls::__l2::<lambda_5ecab4c1661bc65932dd84879df0f635>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerNestedControls::__l2::<lambda_5ecab4c1661bc65932dd84879df0f635>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_registerNestedControls::__l2::<lambda_dfde4f44037d390354e4e9f2ac7f1db9>`
```
struct __cppobj EDUWorldTemplatesScreenController::_registerNestedControls::__l2::<lambda_dfde4f44037d390354e4e9f2ac7f1db9>
{
  EDUWorldTemplatesScreenController *const __this;
};

```

### `EDUWorldTemplatesScreenController::_instantiateTemplate::__l5::<lambda_0805a233344eb0223dd5cafb8447964e>`
```
struct __cppobj __declspec(align(8)) EDUWorldTemplatesScreenController::_instantiateTemplate::__l5::<lambda_0805a233344eb0223dd5cafb8447964e>
{
  std::weak_ptr<EDUWorldTemplatesScreenController> weakThis;
  bool isHost;
};

```

### `EDULibraryCategoryParser`
```
struct __cppobj EDULibraryCategoryParser
{
};

```

### `ExperienceOrb`
```
struct __cppobj __declspec(align(4)) ExperienceOrb : Actor
{
  ActorUniqueID mFollowingPlayer;
  int mFollowingTime;
  int mAge;
  int mHealth;
  bool mIsSpecial;
};

```

### `ExperienceOrb_vtbl`
```
struct /*VFT*/ ExperienceOrb_vtbl
{
  bool (__fastcall *hasComponent)(Actor *this, const HashedString *);
  void (__fastcall *reloadHardcoded)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadHardcodedClient)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *initializeComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *_serverInitItemStackIds)(Actor *this);
  void (__fastcall *_doInitialMove)(Actor *this);
  bool (__fastcall *checkAllSensitiveWords)(Actor *this);
  bool (__fastcall *checkNameTag)(Actor *this);
  void (__fastcall *~Actor)(Actor *this);
  void (__fastcall *reset)(Actor *this);
  int (__fastcall *getOnDeathExperience)(Actor *this);
  ActorType (__fastcall *getOwnerEntityType)(Actor *this);
  void (__fastcall *remove)(Actor *this);
  void (__fastcall *setPos)(Actor *this, const Vec3 *);
  const PredictedMovementValues *(__fastcall *getPredictedMovementValues)(Actor *this);
  const Vec3 *(__fastcall *getPos)(Actor *this);
  const Vec3 *(__fastcall *getPosOld)(Actor *this);
  const Vec3 *(__fastcall *getPosExtrapolated)(Actor *this, const Vec3 *result, float);
  Vec3 *(__fastcall *getAttachPos)(Actor *this, Vec3 *result, ActorLocation, float);
  Vec3 *(__fastcall *getFiringPos)(Actor *this, Vec3 *result);
  void (__fastcall *setRot)(Actor *this, const Vec2 *);
  void (__fastcall *move)(Actor *this, IActorMovementProxy *, const Vec3 *);
  void (__fastcall *move)(Actor *this, const Vec3 *);
  Vec3 *(__fastcall *getInterpolatedRidingPosition)(Actor *this, Vec3 *result, float);
  float (__fastcall *getInterpolatedBodyRot)(Actor *this, float);
  float (__fastcall *getInterpolatedHeadRot)(Actor *this, float);
  float (__fastcall *getInterpolatedBodyYaw)(Actor *this, float);
  float (__fastcall *getYawSpeedInDegreesPerSecond)(Actor *this);
  float (__fastcall *getInterpolatedWalkAnimSpeed)(Actor *this, float);
  Vec3 *(__fastcall *getInterpolatedRidingOffset)(Actor *this, Vec3 *result, float);
  void (__fastcall *checkBlockCollisions)(Actor *this);
  void (__fastcall *checkBlockCollisions)(Actor *this, const AABB *, std::function<void __cdecl(BlockSource &,Block const &,BlockPos const &,Actor &)>);
  bool (__fastcall *isFireImmune)(Actor *this);
  bool (__fastcall *breaksFallingBlocks)(Actor *this);
  void (__fastcall *blockedByShield)(Actor *this, const ActorDamageSource *, Actor *);
  void (__fastcall *teleportTo)(Actor *this, const Vec3 *, bool, int, int, const ActorUniqueID *);
  bool (__fastcall *tryTeleportTo)(Actor *this, const Vec3 *, bool, bool, int, int);
  void (__fastcall *chorusFruitTeleport)(Actor *this, Vec3 *);
  void (__fastcall *lerpTo)(Actor *this, const Vec3 *, const Vec2 *, int);
  void (__fastcall *lerpMotion)(Actor *this, const Vec3 *);
  std::unique_ptr<AddActorBasePacket> *(__fastcall *getAddPacket)(Actor *this, std::unique_ptr<AddActorBasePacket> *result);
  void (__fastcall *normalTick)(Actor *this);
  void (__fastcall *baseTick)(Actor *this);
  void (__fastcall *rideTick)(Actor *this);
  void (__fastcall *positionRider)(Actor *this, Actor *, float);
  float (__fastcall *getRidingHeight)(Actor *this);
  bool (__fastcall *startRiding)(Actor *this, Actor *);
  void (__fastcall *addRider)(Actor *this, Actor *);
  void (__fastcall *flagRiderToRemove)(Actor *this, Actor *);
  std::string *(__fastcall *getExitTip)(Actor *this, std::string *result, const std::string *, InputMode);
  bool (__fastcall *intersects)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *, float);
  bool (__fastcall *isInWall)(Actor *this);
  bool (__fastcall *isInvisible)(Actor *this);
  bool (__fastcall *canShowNameTag)(Actor *this);
  bool (__fastcall *canExistInPeaceful)(Actor *this);
  void (__fastcall *setNameTagVisible)(Actor *this, bool);
  const std::string *(__fastcall *getNameTag)(Actor *this);
  unsigned __int64 (__fastcall *getNameTagAsHash)(Actor *this);
  std::string *(__fastcall *getFormattedNameTag)(Actor *this, std::string *result);
  void (__fastcall *filterFormattedNameTag)(Actor *this, const UIProfanityContext *);
  void (__fastcall *setNameTag)(Actor *this, const std::string *);
  bool (__fastcall *getAlwaysShowNameTag)(Actor *this);
  void (__fastcall *setScoreTag)(Actor *this, const std::string *);
  const std::string *(__fastcall *getScoreTag)(Actor *this);
  bool (__fastcall *isInWater)(Actor *this);
  bool (__fastcall *hasEnteredWater)(Actor *this);
  bool (__fastcall *isImmersedInWater)(Actor *this);
  bool (__fastcall *isInWaterOrRain)(Actor *this);
  bool (__fastcall *isInLava)(Actor *this);
  bool (__fastcall *isUnderLiquid)(Actor *this, MaterialType);
  bool (__fastcall *isOverWater)(Actor *this);
  void (__fastcall *makeStuckInBlock)(Actor *this, const Vec3 *);
  float (__fastcall *getCameraOffset)(Actor *this);
  float (__fastcall *getShadowHeightOffs)(Actor *this);
  float (__fastcall *getShadowRadius)(Actor *this);
  Vec3 *(__fastcall *getHeadLookVector)(Actor *this, Vec3 *result, float);
  bool (__fastcall *canSeeInvisible)(Actor *this);
  bool (__fastcall *canSee)(Actor *this, const Vec3 *);
  bool (__fastcall *canSee)(Actor *this, const Actor *);
  bool (__fastcall *isSkyLit)(Actor *this, float);
  float (__fastcall *getBrightness)(Actor *this, float);
  bool (__fastcall *interactPreventDefault)(Actor *this);
  void (__fastcall *playerTouch)(Actor *this, Player *);
  void (__fastcall *onAboveBubbleColumn)(Actor *this, const bool);
  void (__fastcall *onInsideBubbleColumn)(Actor *this, const bool);
  bool (__fastcall *isImmobile)(Actor *this);
  bool (__fastcall *isSilent)(Actor *this);
  bool (__fastcall *isPickable)(Actor *this);
  bool (__fastcall *isFishable)(Actor *this);
  bool (__fastcall *isSleeping)(Actor *this);
  bool (__fastcall *isShootable)(Actor *this);
  void (__fastcall *setSneaking)(Actor *this, bool);
  bool (__fastcall *isBlocking)(Actor *this);
  bool (__fastcall *isDamageBlocked)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *isAlive)(Actor *this);
  bool (__fastcall *isOnFire)(Actor *this);
  bool (__fastcall *isOnHotBlock)(Actor *this);
  bool (__fastcall *isCreativeModeAllowed)(Actor *this);
  bool (__fastcall *isSurfaceMob)(Actor *this);
  bool (__fastcall *isTargetable)(Actor *this);
  bool (__fastcall *isLocalPlayer)(Actor *this);
  bool (__fastcall *isPlayer)(Actor *this);
  bool (__fastcall *canAttack)(Actor *this, Actor *, bool);
  void (__fastcall *setTarget)(Actor *this, Actor *);
  Actor *(__fastcall *findAttackTarget)(Actor *this);
  bool (__fastcall *isValidTarget)(Actor *this, Actor *);
  bool (__fastcall *attack)(Actor *this, Actor *);
  void (__fastcall *performRangedAttack)(Actor *this, Actor *, float);
  void (__fastcall *adjustDamageAmount)(Actor *this, int *);
  int (__fastcall *getEquipmentCount)(Actor *this);
  void (__fastcall *setOwner)(Actor *this, const ActorUniqueID);
  void (__fastcall *setSitting)(Actor *this, bool);
  void (__fastcall *onTame)(Actor *this);
  void (__fastcall *onFailedTame)(Actor *this);
  int (__fastcall *getInventorySize)(Actor *this);
  int (__fastcall *getEquipSlots)(Actor *this);
  int (__fastcall *getChestSlots)(Actor *this);
  void (__fastcall *setStanding)(Actor *this, bool);
  bool (__fastcall *canPowerJump)(Actor *this);
  void (__fastcall *setCanPowerJump)(Actor *this, bool);
  bool (__fastcall *isJumping)(Actor *this);
  bool (__fastcall *isEnchanted)(Actor *this);
  void (__fastcall *rideJumped)(Actor *this);
  void (__fastcall *rideLanded)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *shouldRender)(Actor *this);
  bool (__fastcall *isInvulnerableTo)(Actor *this, const ActorDamageSource *);
  ActorDamageCause (__fastcall *getBlockDamageCause)(Actor *this, const Block *);
  void (__fastcall *actuallyHurt)(Actor *this, int, const ActorDamageSource *, bool);
  void (__fastcall *animateHurt)(Actor *this);
  bool (__fastcall *doFireHurt)(Actor *this, int);
  void (__fastcall *onLightningHit)(Actor *this);
  void (__fastcall *onBounceStarted)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *feed)(Actor *this, int);
  void (__fastcall *handleEntityEvent)(Actor *this, ActorEvent, int);
  float (__fastcall *getPickRadius)(Actor *this);
  const HashedString *(__fastcall *getActorRendererId)(Actor *this);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const ItemStack *, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int);
  void (__fastcall *despawn)(Actor *this);
  void (__fastcall *killed)(Actor *this, Actor *);
  void (__fastcall *awardKillScore)(Actor *this, Actor *, int);
  void (__fastcall *setArmor)(Actor *this, ArmorSlot, const ItemStack *);
  const ItemStack *(__fastcall *getArmor)(Actor *this, ArmorSlot);
  ArmorMaterialType (__fastcall *getArmorMaterialTypeInSlot)(Actor *this, ArmorSlot);
  ArmorTextureType (__fastcall *getArmorMaterialTextureTypeInSlot)(Actor *this, ArmorSlot);
  float (__fastcall *getArmorColorInSlot)(Actor *this, ArmorSlot, int);
  const ItemStack *(__fastcall *getEquippedSlot)(Actor *this, EquipmentSlot);
  void (__fastcall *setEquippedSlot)(Actor *this, EquipmentSlot, const ItemStack *);
  const ItemStack *(__fastcall *getCarriedItem)(Actor *this);
  void (__fastcall *setCarriedItem)(Actor *this, const ItemStack *);
  void (__fastcall *setOffhandSlot)(Actor *this, const ItemStack *);
  const ItemStack *(__fastcall *getEquippedTotem)(Actor *this);
  bool (__fastcall *consumeTotem)(Actor *this);
  bool (__fastcall *save)(Actor *this, CompoundTag *);
  void (__fastcall *saveWithoutId)(Actor *this, CompoundTag *);
  bool (__fastcall *load)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *loadLinks)(Actor *this, const CompoundTag *, std::vector<ActorLink> *, DataLoadHelper *);
  ActorType (__fastcall *getEntityTypeId)(Actor *this);
  const HashedString *(__fastcall *queryEntityRenderer)(Actor *this);
  ActorUniqueID *(__fastcall *getSourceUniqueID)(Actor *this, ActorUniqueID *result);
  void (__fastcall *setOnFire)(Actor *this, int);
  AABB *(__fastcall *getHandleWaterAABB)(Actor *this, AABB *result);
  void (__fastcall *handleInsidePortal)(Actor *this, const BlockPos *);
  int (__fastcall *getPortalCooldown)(Actor *this);
  int (__fastcall *getPortalWaitTime)(Actor *this);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(Actor *this, AutomaticID<Dimension,int> *result);
  bool (__fastcall *canChangeDimensions)(Actor *this);
  void (__fastcall *changeDimension)(Actor *this, const ChangeDimensionPacket *);
  void (__fastcall *changeDimension)(Actor *this, AutomaticID<Dimension,int>, bool);
  ActorUniqueID *(__fastcall *getControllingPlayer)(Actor *this, ActorUniqueID *result);
  void (__fastcall *checkFallDamage)(Actor *this, float, bool);
  void (__fastcall *causeFallDamage)(Actor *this, float);
  void (__fastcall *handleFallDistanceOnServer)(Actor *this, float, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, int, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, const Block *, bool);
  void (__fastcall *onSynchedDataUpdate)(Actor *this, int);
  bool (__fastcall *canAddRider)(Actor *this, Actor *);
  bool (__fastcall *canPickupItem)(Actor *this, const ItemStack *);
  bool (__fastcall *canBePulledIntoVehicle)(Actor *this);
  bool (__fastcall *inCaravan)(Actor *this);
  bool (__fastcall *isLeashableType)(Actor *this);
  void (__fastcall *tickLeash)(Actor *this);
  void (__fastcall *sendMotionPacketIfNeeded)(Actor *this);
  bool (__fastcall *canSynchronizeNewEntity)(Actor *this);
  bool (__fastcall *stopRiding)(Actor *this, bool, bool, bool, bool);
  void (__fastcall *startSwimming)(Actor *this);
  void (__fastcall *stopSwimming)(Actor *this);
  void (__fastcall *buildDebugInfo)(Actor *this, std::string *);
  CommandPermissionLevel (__fastcall *getCommandPermissionLevel)(Actor *this);
  AttributeInstance *(__fastcall *getMutableAttribute)(Actor *this, const Attribute *);
  const AttributeInstance *(__fastcall *getAttribute)(Actor *this, const Attribute *);
  int (__fastcall *getDeathTime)(Actor *this);
  void (__fastcall *heal)(Actor *this, int);
  bool (__fastcall *isInvertedHealAndHarm)(Actor *this);
  bool (__fastcall *canBeAffected)(Actor *this, const MobEffectInstance *);
  bool (__fastcall *canBeAffected)(Actor *this, int);
  bool (__fastcall *canBeAffectedByArrow)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectAdded)(Actor *this, MobEffectInstance *);
  void (__fastcall *onEffectUpdated)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectRemoved)(Actor *this, MobEffectInstance *);
  AnimationComponent *(__fastcall *getAnimationComponent)(Actor *this);
  void (__fastcall *openContainerComponent)(Actor *this, Player *);
  void (__fastcall *swing)(Actor *this);
  void (__fastcall *useItem)(Actor *this, ItemStackBase *, ItemUseMethod, bool);
  bool (__fastcall *hasOutputSignal)(Actor *this, unsigned __int8);
  int (__fastcall *getOutputSignal)(Actor *this);
  void (__fastcall *getDebugText)(Actor *this, std::vector<std::string> *);
  float (__fastcall *getMapDecorationRotation)(Actor *this);
  float (__fastcall *getRiderYRotation)(Actor *this, const Actor *);
  float (__fastcall *getYHeadRot)(Actor *this);
  bool (__fastcall *isWorldBuilder)(Actor *this);
  bool (__fastcall *isCreative)(Actor *this);
  bool (__fastcall *isAdventure)(Actor *this);
  bool (__fastcall *add)(Actor *this, ItemStack *);
  bool (__fastcall *drop)(Actor *this, const ItemStack *, bool);
  bool (__fastcall *getInteraction)(Actor *this, Player *, ActorInteraction *, const Vec3 *);
  bool (__fastcall *canDestroyBlock)(Actor *this, const Block *);
  void (__fastcall *setAuxValue)(Actor *this, int);
  void (__fastcall *setSize)(Actor *this, float, float);
  int (__fastcall *getLifeSpan)(Actor *this);
  void (__fastcall *onOrphan)(Actor *this);
  void (__fastcall *wobble)(Actor *this);
  bool (__fastcall *wasHurt)(Actor *this);
  void (__fastcall *startSpinAttack)(Actor *this);
  void (__fastcall *stopSpinAttack)(Actor *this);
  void (__fastcall *setDamageNearbyMobs)(Actor *this, bool);
  bool (__fastcall *hasCritBox)(Actor *this);
  bool (__fastcall *isCritHit)(Actor *this);
  void (__fastcall *renderDebugServerState)(Actor *this, const Options *);
  void (__fastcall *reloadLootTable)(Actor *this, const EquipmentTableDefinition *);
  void (__fastcall *reloadLootTable)(Actor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(Actor *this);
  void (__fastcall *kill)(Actor *this);
  void (__fastcall *die)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *shouldTick)(Actor *this);
  std::shared_ptr<IActorMovementProxy> *(__fastcall *createMovementProxy)(Actor *this, std::shared_ptr<IActorMovementProxy> *result);
  void (__fastcall *updateEntitySpecificMolangVariables)(Actor *this, RenderParams *);
  bool (__fastcall *shouldTryMakeStepSound)(Actor *this);
  float (__fastcall *getNextStep)(Actor *this, const float);
  bool (__fastcall *canMakeStepSound)(Actor *this);
  void (__fastcall *outOfWorld)(Actor *this);
  bool (__fastcall *_hurt)(Actor *this, const ActorDamageSource *, int, bool, bool);
  void (__fastcall *markHurt)(Actor *this);
  void (__fastcall *readAdditionalSaveData)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *addAdditionalSaveData)(Actor *this, CompoundTag *);
  void (__fastcall *_playStepSound)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *_playFlySound)(Actor *this, const BlockPos *, const Block *);
  bool (__fastcall *_makeFlySound)(Actor *this);
  void (__fastcall *checkInsideBlocks)(Actor *this, float);
  void (__fastcall *pushOutOfBlocks)(Actor *this, const Vec3 *);
  bool (__fastcall *updateWaterState)(Actor *this);
  void (__fastcall *doWaterSplashEffect)(Actor *this);
  void (__fastcall *spawnTrailBubbles)(Actor *this);
  void (__fastcall *updateInsideBlock)(Actor *this);
  LootTable *(__fastcall *getLootTable)(Actor *this);
  LootTable *(__fastcall *getDefaultLootTable)(Actor *this);
  void (__fastcall *_removeRider)(Actor *this, const ActorUniqueID *, bool, bool, bool);
  void (__fastcall *_onSizeUpdated)(Actor *this);
  void (__fastcall *_doAutoAttackOnTouch)(Actor *this, Actor *);
};

```

### `EndOfString<93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56,51>`
```
struct __cppobj EndOfString<93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56,51>
{
};

```

### `EndOfString<100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11,3>`
```
struct __cppobj EndOfString<100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11,3>
{
};

```

### `EducationContentServices::_onChannelFetched::__l25::<lambda_cd43e388753c32a30d9d69ffa3a1564f>`
```
struct __cppobj EducationContentServices::_onChannelFetched::__l25::<lambda_cd43e388753c32a30d9d69ffa3a1564f>
{
  std::weak_ptr<InstructionalContentCollection> collection;
};

```

### `EducationContentServices::_onCatalogFetched::__l26::<lambda_a0c09c5ad1307dcbc1529457c4e0cd36>`
```
struct __cppobj EducationContentServices::_onCatalogFetched::__l26::<lambda_a0c09c5ad1307dcbc1529457c4e0cd36>
{
  std::weak_ptr<InstructionalContentCollection> collection;
};

```

### `EducationContentServices::_onLibraryFetched::__l26::<lambda_293a272e4185a3796a8be5dc5edde268>`
```
struct __cppobj EducationContentServices::_onLibraryFetched::__l26::<lambda_293a272e4185a3796a8be5dc5edde268>
{
  std::weak_ptr<InstructionalContentCollection> collection;
};

```

### `EducationContentServices::_getCatalogImage::__l2::<lambda_6995be38285c0ed77377c20f5596b82e>`
```
struct __cppobj EducationContentServices::_getCatalogImage::__l2::<lambda_6995be38285c0ed77377c20f5596b82e>
{
  std::weak_ptr<LessonItem> weakItem;
  std::function<void __cdecl(void)> callback;
};

```

### `EducationContentServices::_fetchCatalogItems::__l2::<lambda_dfd54bf96a233766efb5bf258ffc74eb>`
```
struct __cppobj EducationContentServices::_fetchCatalogItems::__l2::<lambda_dfd54bf96a233766efb5bf258ffc74eb>
{
  std::weak_ptr<EducationContentServices> weakThis;
  const gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > *service;
  std::weak_ptr<InstructionalContentCollection> collection;
  std::shared_ptr<InstructionalContentQueryContext> context;
  std::shared_ptr<LibraryCollectionConfig> config;
};

```

### `EducationContentServices::_createItemAndCheckImported::__l5::<lambda_4ee5762f36ab4b3b4b2fb0469093ffd7>`
```
struct __cppobj EducationContentServices::_createItemAndCheckImported::__l5::<lambda_4ee5762f36ab4b3b4b2fb0469093ffd7>
{
  std::weak_ptr<LibraryItem> weakNew;
  std::weak_ptr<EducationContentServices const > weakThis;
};

```

### `EducationContentServices::getLibraryItem::__l5::<lambda_b020947a43b6dc3fdf76e4eb60e1956c>`
```
struct __cppobj EducationContentServices::getLibraryItem::__l5::<lambda_b020947a43b6dc3fdf76e4eb60e1956c>
{
  std::weak_ptr<EducationContentServices> weakThis;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > *service;
  std::function<void __cdecl(std::shared_ptr<LibraryItem>)> callback;
};

```

### `EnchantingContainerManagerModel`
```
struct __cppobj EnchantingContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  bool mShouldBookBeOpen;
  std::vector<ItemEnchantOption> mEnchantOptions;
  bool mServerSendsOptions;
  std::function<void __cdecl(EnchantingContainerManagerModel &)> mOptionsChangedCallback;
};

```

### `EnchantingContainerManagerModel_vtbl`
```
struct /*VFT*/ EnchantingContainerManagerModel_vtbl
{
  void (__fastcall *~IContainerManager)(IContainerManager *this);
  ContainerID (__fastcall *getContainerId)(IContainerManager *this);
  void (__fastcall *setContainerId)(IContainerManager *this, ContainerID);
  ContainerType (__fastcall *getContainerType)(IContainerManager *this);
  void (__fastcall *setContainerType)(IContainerManager *this, ContainerType);
  void (__fastcall *serverInitItemStackIds)(IContainerManager *this);
  std::vector<ItemStack> *(__fastcall *getItemCopies)(IContainerManager *this, std::vector<ItemStack> *result);
  void (__fastcall *setSlot)(IContainerManager *this, int, const ItemStack *, bool);
  const ItemStack *(__fastcall *getSlot)(IContainerManager *this, int);
  void (__fastcall *setData)(IContainerManager *this, int, int);
  void (__fastcall *broadcastChanges)(IContainerManager *this);
  bool (__fastcall *validateContainer)(IContainerManager *this);
  bool (__fastcall *isValid)(ContainerManagerModel *this, float);
  ContainerScreenContext *(__fastcall *_postInit)(ContainerManagerModel *this, ContainerScreenContext *result);
};

```

### `EnumOption`
```
struct __cppobj EnumOption : IntOption
{
  const std::unordered_map<int,std::string> *ValueNameMap;
};

```

### `EnumOption_vtbl`
```
struct /*VFT*/ EnumOption_vtbl
{
  void (__fastcall *~Option)(Option *this);
  void (__fastcall *save)(Option *this, std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *load)(Option *this, const Json::Value *);
  void (__fastcall *load)(Option *this, std::map<std::string,std::string> *);
  void (__fastcall *load)(Option *this, const std::string *);
};

```

### `EndRodParticle`
```
struct __cppobj EndRodParticle : Particle
{
  mce::Color mFadeColor;
  int baseTex;
  Vec3 mDir;
};

```

### `EndRodParticle_vtbl`
```
struct /*VFT*/ EndRodParticle_vtbl
{
  void (__fastcall *init)(Particle *this, const Vec3 *, const Vec3 *, int, ParticleEngine *);
  void (__fastcall *addTagData)(Particle *this, const CompoundTag *);
  void (__fastcall *~Particle)(Particle *this);
  void (__fastcall *normalTick)(Particle *this);
  void (__fastcall *tessellate)(Particle *this, const ParticleRenderContext *);
  const mce::TexturePtr *(__fastcall *getParticleTexture)(Particle *this);
  mce::Color *(__fastcall *getParticleLightColor)(Particle *this, mce::Color *result, float, const LightTexture *);
  void (__fastcall *setEmittingEntity)(Particle *this, Actor *);
  bool (__fastcall *_shouldUpdateVertexData)(Particle *this, float);
};

```

### `EnchantingTableParticle`
```
struct __cppobj EnchantingTableParticle : Particle
{
  float mSizeOld;
  Vec3 mStart;
};

```

### `EnchantingTableParticle_vtbl`
```
struct /*VFT*/ EnchantingTableParticle_vtbl
{
  void (__fastcall *init)(Particle *this, const Vec3 *, const Vec3 *, int, ParticleEngine *);
  void (__fastcall *addTagData)(Particle *this, const CompoundTag *);
  void (__fastcall *~Particle)(Particle *this);
  void (__fastcall *normalTick)(Particle *this);
  void (__fastcall *tessellate)(Particle *this, const ParticleRenderContext *);
  const mce::TexturePtr *(__fastcall *getParticleTexture)(Particle *this);
  mce::Color *(__fastcall *getParticleLightColor)(Particle *this, mce::Color *result, float, const LightTexture *);
  void (__fastcall *setEmittingEntity)(Particle *this, Actor *);
  bool (__fastcall *_shouldUpdateVertexData)(Particle *this, float);
};

```

### `ExplodeParticle`
```
struct __cppobj ExplodeParticle : Particle
{
};

```

### `ExplodeParticle_vtbl`
```
struct /*VFT*/ ExplodeParticle_vtbl
{
  void (__fastcall *init)(Particle *this, const Vec3 *, const Vec3 *, int, ParticleEngine *);
  void (__fastcall *addTagData)(Particle *this, const CompoundTag *);
  void (__fastcall *~Particle)(Particle *this);
  void (__fastcall *normalTick)(Particle *this);
  void (__fastcall *tessellate)(Particle *this, const ParticleRenderContext *);
  const mce::TexturePtr *(__fastcall *getParticleTexture)(Particle *this);
  mce::Color *(__fastcall *getParticleLightColor)(Particle *this, mce::Color *result, float, const LightTexture *);
  void (__fastcall *setEmittingEntity)(Particle *this, Actor *);
  bool (__fastcall *_shouldUpdateVertexData)(Particle *this, float);
};

```

### `EffectComponentHelpers`
```
struct __cppobj EffectComponentHelpers
{
};

```

### `EntityExtensionDefault`
```
struct __cppobj EntityExtensionDefault : Actor
{
};

```

### `EntityExtensionDefault_vtbl`
```
struct /*VFT*/ EntityExtensionDefault_vtbl
{
  bool (__fastcall *hasComponent)(Actor *this, const HashedString *);
  void (__fastcall *reloadHardcoded)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadHardcodedClient)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *initializeComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *_serverInitItemStackIds)(Actor *this);
  void (__fastcall *_doInitialMove)(Actor *this);
  bool (__fastcall *checkAllSensitiveWords)(Actor *this);
  bool (__fastcall *checkNameTag)(Actor *this);
  void (__fastcall *~Actor)(Actor *this);
  void (__fastcall *reset)(Actor *this);
  int (__fastcall *getOnDeathExperience)(Actor *this);
  ActorType (__fastcall *getOwnerEntityType)(Actor *this);
  void (__fastcall *remove)(Actor *this);
  void (__fastcall *setPos)(Actor *this, const Vec3 *);
  const PredictedMovementValues *(__fastcall *getPredictedMovementValues)(Actor *this);
  const Vec3 *(__fastcall *getPos)(Actor *this);
  const Vec3 *(__fastcall *getPosOld)(Actor *this);
  const Vec3 *(__fastcall *getPosExtrapolated)(Actor *this, const Vec3 *result, float);
  Vec3 *(__fastcall *getAttachPos)(Actor *this, Vec3 *result, ActorLocation, float);
  Vec3 *(__fastcall *getFiringPos)(Actor *this, Vec3 *result);
  void (__fastcall *setRot)(Actor *this, const Vec2 *);
  void (__fastcall *move)(Actor *this, IActorMovementProxy *, const Vec3 *);
  void (__fastcall *move)(Actor *this, const Vec3 *);
  Vec3 *(__fastcall *getInterpolatedRidingPosition)(Actor *this, Vec3 *result, float);
  float (__fastcall *getInterpolatedBodyRot)(Actor *this, float);
  float (__fastcall *getInterpolatedHeadRot)(Actor *this, float);
  float (__fastcall *getInterpolatedBodyYaw)(Actor *this, float);
  float (__fastcall *getYawSpeedInDegreesPerSecond)(Actor *this);
  float (__fastcall *getInterpolatedWalkAnimSpeed)(Actor *this, float);
  Vec3 *(__fastcall *getInterpolatedRidingOffset)(Actor *this, Vec3 *result, float);
  void (__fastcall *checkBlockCollisions)(Actor *this);
  void (__fastcall *checkBlockCollisions)(Actor *this, const AABB *, std::function<void __cdecl(BlockSource &,Block const &,BlockPos const &,Actor &)>);
  bool (__fastcall *isFireImmune)(Actor *this);
  bool (__fastcall *breaksFallingBlocks)(Actor *this);
  void (__fastcall *blockedByShield)(Actor *this, const ActorDamageSource *, Actor *);
  void (__fastcall *teleportTo)(Actor *this, const Vec3 *, bool, int, int, const ActorUniqueID *);
  bool (__fastcall *tryTeleportTo)(Actor *this, const Vec3 *, bool, bool, int, int);
  void (__fastcall *chorusFruitTeleport)(Actor *this, Vec3 *);
  void (__fastcall *lerpTo)(Actor *this, const Vec3 *, const Vec2 *, int);
  void (__fastcall *lerpMotion)(Actor *this, const Vec3 *);
  std::unique_ptr<AddActorBasePacket> *(__fastcall *getAddPacket)(Actor *this, std::unique_ptr<AddActorBasePacket> *result);
  void (__fastcall *normalTick)(Actor *this);
  void (__fastcall *baseTick)(Actor *this);
  void (__fastcall *rideTick)(Actor *this);
  void (__fastcall *positionRider)(Actor *this, Actor *, float);
  float (__fastcall *getRidingHeight)(Actor *this);
  bool (__fastcall *startRiding)(Actor *this, Actor *);
  void (__fastcall *addRider)(Actor *this, Actor *);
  void (__fastcall *flagRiderToRemove)(Actor *this, Actor *);
  std::string *(__fastcall *getExitTip)(Actor *this, std::string *result, const std::string *, InputMode);
  bool (__fastcall *intersects)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *, float);
  bool (__fastcall *isInWall)(Actor *this);
  bool (__fastcall *isInvisible)(Actor *this);
  bool (__fastcall *canShowNameTag)(Actor *this);
  bool (__fastcall *canExistInPeaceful)(Actor *this);
  void (__fastcall *setNameTagVisible)(Actor *this, bool);
  const std::string *(__fastcall *getNameTag)(Actor *this);
  unsigned __int64 (__fastcall *getNameTagAsHash)(Actor *this);
  std::string *(__fastcall *getFormattedNameTag)(Actor *this, std::string *result);
  void (__fastcall *filterFormattedNameTag)(Actor *this, const UIProfanityContext *);
  void (__fastcall *setNameTag)(Actor *this, const std::string *);
  bool (__fastcall *getAlwaysShowNameTag)(Actor *this);
  void (__fastcall *setScoreTag)(Actor *this, const std::string *);
  const std::string *(__fastcall *getScoreTag)(Actor *this);
  bool (__fastcall *isInWater)(Actor *this);
  bool (__fastcall *hasEnteredWater)(Actor *this);
  bool (__fastcall *isImmersedInWater)(Actor *this);
  bool (__fastcall *isInWaterOrRain)(Actor *this);
  bool (__fastcall *isInLava)(Actor *this);
  bool (__fastcall *isUnderLiquid)(Actor *this, MaterialType);
  bool (__fastcall *isOverWater)(Actor *this);
  void (__fastcall *makeStuckInBlock)(Actor *this, const Vec3 *);
  float (__fastcall *getCameraOffset)(Actor *this);
  float (__fastcall *getShadowHeightOffs)(Actor *this);
  float (__fastcall *getShadowRadius)(Actor *this);
  Vec3 *(__fastcall *getHeadLookVector)(Actor *this, Vec3 *result, float);
  bool (__fastcall *canSeeInvisible)(Actor *this);
  bool (__fastcall *canSee)(Actor *this, const Vec3 *);
  bool (__fastcall *canSee)(Actor *this, const Actor *);
  bool (__fastcall *isSkyLit)(Actor *this, float);
  float (__fastcall *getBrightness)(Actor *this, float);
  bool (__fastcall *interactPreventDefault)(Actor *this);
  void (__fastcall *playerTouch)(Actor *this, Player *);
  void (__fastcall *onAboveBubbleColumn)(Actor *this, const bool);
  void (__fastcall *onInsideBubbleColumn)(Actor *this, const bool);
  bool (__fastcall *isImmobile)(Actor *this);
  bool (__fastcall *isSilent)(Actor *this);
  bool (__fastcall *isPickable)(Actor *this);
  bool (__fastcall *isFishable)(Actor *this);
  bool (__fastcall *isSleeping)(Actor *this);
  bool (__fastcall *isShootable)(Actor *this);
  void (__fastcall *setSneaking)(Actor *this, bool);
  bool (__fastcall *isBlocking)(Actor *this);
  bool (__fastcall *isDamageBlocked)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *isAlive)(Actor *this);
  bool (__fastcall *isOnFire)(Actor *this);
  bool (__fastcall *isOnHotBlock)(Actor *this);
  bool (__fastcall *isCreativeModeAllowed)(Actor *this);
  bool (__fastcall *isSurfaceMob)(Actor *this);
  bool (__fastcall *isTargetable)(Actor *this);
  bool (__fastcall *isLocalPlayer)(Actor *this);
  bool (__fastcall *isPlayer)(Actor *this);
  bool (__fastcall *canAttack)(Actor *this, Actor *, bool);
  void (__fastcall *setTarget)(Actor *this, Actor *);
  Actor *(__fastcall *findAttackTarget)(Actor *this);
  bool (__fastcall *isValidTarget)(Actor *this, Actor *);
  bool (__fastcall *attack)(Actor *this, Actor *);
  void (__fastcall *performRangedAttack)(Actor *this, Actor *, float);
  void (__fastcall *adjustDamageAmount)(Actor *this, int *);
  int (__fastcall *getEquipmentCount)(Actor *this);
  void (__fastcall *setOwner)(Actor *this, const ActorUniqueID);
  void (__fastcall *setSitting)(Actor *this, bool);
  void (__fastcall *onTame)(Actor *this);
  void (__fastcall *onFailedTame)(Actor *this);
  int (__fastcall *getInventorySize)(Actor *this);
  int (__fastcall *getEquipSlots)(Actor *this);
  int (__fastcall *getChestSlots)(Actor *this);
  void (__fastcall *setStanding)(Actor *this, bool);
  bool (__fastcall *canPowerJump)(Actor *this);
  void (__fastcall *setCanPowerJump)(Actor *this, bool);
  bool (__fastcall *isJumping)(Actor *this);
  bool (__fastcall *isEnchanted)(Actor *this);
  void (__fastcall *rideJumped)(Actor *this);
  void (__fastcall *rideLanded)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *shouldRender)(Actor *this);
  bool (__fastcall *isInvulnerableTo)(Actor *this, const ActorDamageSource *);
  ActorDamageCause (__fastcall *getBlockDamageCause)(Actor *this, const Block *);
  void (__fastcall *actuallyHurt)(Actor *this, int, const ActorDamageSource *, bool);
  void (__fastcall *animateHurt)(Actor *this);
  bool (__fastcall *doFireHurt)(Actor *this, int);
  void (__fastcall *onLightningHit)(Actor *this);
  void (__fastcall *onBounceStarted)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *feed)(Actor *this, int);
  void (__fastcall *handleEntityEvent)(Actor *this, ActorEvent, int);
  float (__fastcall *getPickRadius)(Actor *this);
  const HashedString *(__fastcall *getActorRendererId)(Actor *this);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const ItemStack *, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int);
  void (__fastcall *despawn)(Actor *this);
  void (__fastcall *killed)(Actor *this, Actor *);
  void (__fastcall *awardKillScore)(Actor *this, Actor *, int);
  void (__fastcall *setArmor)(Actor *this, ArmorSlot, const ItemStack *);
  const ItemStack *(__fastcall *getArmor)(Actor *this, ArmorSlot);
  ArmorMaterialType (__fastcall *getArmorMaterialTypeInSlot)(Actor *this, ArmorSlot);
  ArmorTextureType (__fastcall *getArmorMaterialTextureTypeInSlot)(Actor *this, ArmorSlot);
  float (__fastcall *getArmorColorInSlot)(Actor *this, ArmorSlot, int);
  const ItemStack *(__fastcall *getEquippedSlot)(Actor *this, EquipmentSlot);
  void (__fastcall *setEquippedSlot)(Actor *this, EquipmentSlot, const ItemStack *);
  const ItemStack *(__fastcall *getCarriedItem)(Actor *this);
  void (__fastcall *setCarriedItem)(Actor *this, const ItemStack *);
  void (__fastcall *setOffhandSlot)(Actor *this, const ItemStack *);
  const ItemStack *(__fastcall *getEquippedTotem)(Actor *this);
  bool (__fastcall *consumeTotem)(Actor *this);
  bool (__fastcall *save)(Actor *this, CompoundTag *);
  void (__fastcall *saveWithoutId)(Actor *this, CompoundTag *);
  bool (__fastcall *load)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *loadLinks)(Actor *this, const CompoundTag *, std::vector<ActorLink> *, DataLoadHelper *);
  ActorType (__fastcall *getEntityTypeId)(Actor *this);
  const HashedString *(__fastcall *queryEntityRenderer)(Actor *this);
  ActorUniqueID *(__fastcall *getSourceUniqueID)(Actor *this, ActorUniqueID *result);
  void (__fastcall *setOnFire)(Actor *this, int);
  AABB *(__fastcall *getHandleWaterAABB)(Actor *this, AABB *result);
  void (__fastcall *handleInsidePortal)(Actor *this, const BlockPos *);
  int (__fastcall *getPortalCooldown)(Actor *this);
  int (__fastcall *getPortalWaitTime)(Actor *this);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(Actor *this, AutomaticID<Dimension,int> *result);
  bool (__fastcall *canChangeDimensions)(Actor *this);
  void (__fastcall *changeDimension)(Actor *this, const ChangeDimensionPacket *);
  void (__fastcall *changeDimension)(Actor *this, AutomaticID<Dimension,int>, bool);
  ActorUniqueID *(__fastcall *getControllingPlayer)(Actor *this, ActorUniqueID *result);
  void (__fastcall *checkFallDamage)(Actor *this, float, bool);
  void (__fastcall *causeFallDamage)(Actor *this, float);
  void (__fastcall *handleFallDistanceOnServer)(Actor *this, float, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, int, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, const Block *, bool);
  void (__fastcall *onSynchedDataUpdate)(Actor *this, int);
  bool (__fastcall *canAddRider)(Actor *this, Actor *);
  bool (__fastcall *canPickupItem)(Actor *this, const ItemStack *);
  bool (__fastcall *canBePulledIntoVehicle)(Actor *this);
  bool (__fastcall *inCaravan)(Actor *this);
  bool (__fastcall *isLeashableType)(Actor *this);
  void (__fastcall *tickLeash)(Actor *this);
  void (__fastcall *sendMotionPacketIfNeeded)(Actor *this);
  bool (__fastcall *canSynchronizeNewEntity)(Actor *this);
  bool (__fastcall *stopRiding)(Actor *this, bool, bool, bool, bool);
  void (__fastcall *startSwimming)(Actor *this);
  void (__fastcall *stopSwimming)(Actor *this);
  void (__fastcall *buildDebugInfo)(Actor *this, std::string *);
  CommandPermissionLevel (__fastcall *getCommandPermissionLevel)(Actor *this);
  AttributeInstance *(__fastcall *getMutableAttribute)(Actor *this, const Attribute *);
  const AttributeInstance *(__fastcall *getAttribute)(Actor *this, const Attribute *);
  int (__fastcall *getDeathTime)(Actor *this);
  void (__fastcall *heal)(Actor *this, int);
  bool (__fastcall *isInvertedHealAndHarm)(Actor *this);
  bool (__fastcall *canBeAffected)(Actor *this, const MobEffectInstance *);
  bool (__fastcall *canBeAffected)(Actor *this, int);
  bool (__fastcall *canBeAffectedByArrow)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectAdded)(Actor *this, MobEffectInstance *);
  void (__fastcall *onEffectUpdated)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectRemoved)(Actor *this, MobEffectInstance *);
  AnimationComponent *(__fastcall *getAnimationComponent)(Actor *this);
  void (__fastcall *openContainerComponent)(Actor *this, Player *);
  void (__fastcall *swing)(Actor *this);
  void (__fastcall *useItem)(Actor *this, ItemStackBase *, ItemUseMethod, bool);
  bool (__fastcall *hasOutputSignal)(Actor *this, unsigned __int8);
  int (__fastcall *getOutputSignal)(Actor *this);
  void (__fastcall *getDebugText)(Actor *this, std::vector<std::string> *);
  float (__fastcall *getMapDecorationRotation)(Actor *this);
  float (__fastcall *getRiderYRotation)(Actor *this, const Actor *);
  float (__fastcall *getYHeadRot)(Actor *this);
  bool (__fastcall *isWorldBuilder)(Actor *this);
  bool (__fastcall *isCreative)(Actor *this);
  bool (__fastcall *isAdventure)(Actor *this);
  bool (__fastcall *add)(Actor *this, ItemStack *);
  bool (__fastcall *drop)(Actor *this, const ItemStack *, bool);
  bool (__fastcall *getInteraction)(Actor *this, Player *, ActorInteraction *, const Vec3 *);
  bool (__fastcall *canDestroyBlock)(Actor *this, const Block *);
  void (__fastcall *setAuxValue)(Actor *this, int);
  void (__fastcall *setSize)(Actor *this, float, float);
  int (__fastcall *getLifeSpan)(Actor *this);
  void (__fastcall *onOrphan)(Actor *this);
  void (__fastcall *wobble)(Actor *this);
  bool (__fastcall *wasHurt)(Actor *this);
  void (__fastcall *startSpinAttack)(Actor *this);
  void (__fastcall *stopSpinAttack)(Actor *this);
  void (__fastcall *setDamageNearbyMobs)(Actor *this, bool);
  bool (__fastcall *hasCritBox)(Actor *this);
  bool (__fastcall *isCritHit)(Actor *this);
  void (__fastcall *renderDebugServerState)(Actor *this, const Options *);
  void (__fastcall *reloadLootTable)(Actor *this, const EquipmentTableDefinition *);
  void (__fastcall *reloadLootTable)(Actor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(Actor *this);
  void (__fastcall *kill)(Actor *this);
  void (__fastcall *die)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *shouldTick)(Actor *this);
  std::shared_ptr<IActorMovementProxy> *(__fastcall *createMovementProxy)(Actor *this, std::shared_ptr<IActorMovementProxy> *result);
  void (__fastcall *updateEntitySpecificMolangVariables)(Actor *this, RenderParams *);
  bool (__fastcall *shouldTryMakeStepSound)(Actor *this);
  float (__fastcall *getNextStep)(Actor *this, const float);
  bool (__fastcall *canMakeStepSound)(Actor *this);
  void (__fastcall *outOfWorld)(Actor *this);
  bool (__fastcall *_hurt)(Actor *this, const ActorDamageSource *, int, bool, bool);
  void (__fastcall *markHurt)(Actor *this);
  void (__fastcall *readAdditionalSaveData)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *addAdditionalSaveData)(Actor *this, CompoundTag *);
  void (__fastcall *_playStepSound)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *_playFlySound)(Actor *this, const BlockPos *, const Block *);
  bool (__fastcall *_makeFlySound)(Actor *this);
  void (__fastcall *checkInsideBlocks)(Actor *this, float);
  void (__fastcall *pushOutOfBlocks)(Actor *this, const Vec3 *);
  bool (__fastcall *updateWaterState)(Actor *this);
  void (__fastcall *doWaterSplashEffect)(Actor *this);
  void (__fastcall *spawnTrailBubbles)(Actor *this);
  void (__fastcall *updateInsideBlock)(Actor *this);
  LootTable *(__fastcall *getLootTable)(Actor *this);
  LootTable *(__fastcall *getDefaultLootTable)(Actor *this);
  void (__fastcall *_removeRider)(Actor *this, const ActorUniqueID *, bool, bool, bool);
  void (__fastcall *_onSizeUpdated)(Actor *this);
  void (__fastcall *_doAutoAttackOnTouch)(Actor *this, Actor *);
};

```

### `EmptyRenderer`
```
struct __cppobj EmptyRenderer : ActorRenderer
{
};

```

### `EmptyRenderer_vtbl`
```
struct /*VFT*/ EmptyRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderDebug)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderEffects)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderTrading)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *, float);
  void (__fastcall *renderFlame)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderLeash)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderWaterHole)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *addAdditionalRenderingIfNeeded)(ActorRenderer *this, mce::TextureGroup *);
  void (__fastcall *renderWeaponEffect)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  void (__fastcall *renderBindEffects)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  AABB *(__fastcall *getRenderBounds)(ActorRenderer *this, AABB *result, const Actor *);
  Vec3 *(__fastcall *getLeashOffset)(ActorRenderer *this, Vec3 *result, Actor *, float, float, float, bool, bool);
  void (__fastcall *setIsOnScreen)(ActorRenderer *this, Actor *, const bool, float);
  bool (__fastcall *shouldUpdateBonesAndEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  bool (__fastcall *shouldUpdateEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  void (__fastcall *_bindModelEffectRender)(ActorRenderer *this, BaseActorRenderContext *, Mob *);
};

```

### `EnderMan`
```
struct __cppobj __declspec(align(8)) EnderMan : Monster
{
  bool mAggroedByPlayer;
  std::unique_ptr<CompoundTag> mCarryBlockSerId;
  NewBlockID mCarryBlockId;
  unsigned __int16 mCarryBlockData;
};

```

### `EnderChestBlockActor`
```
struct __cppobj EnderChestBlockActor : ChestBlockActor
{
};

```

### `EnchantingTableRenderer`
```
struct __cppobj EnchantingTableRenderer : BlockActorRenderer
{
  mce::TexturePtr mBookTex;
  EnchantingBookModel mBook;
};

```

### `EnchantingTableRenderer_vtbl`
```
struct /*VFT*/ EnchantingTableRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `EnchantingTableBlockActor`
```
struct __cppobj EnchantingTableBlockActor : BlockActor
{
  float mOpen;
  float mOpenOld;
  float mRot;
  float mRotOld;
  float mRotT;
  float mFlip;
  float mFlipOld;
  float mFlipT;
  float mFlipA;
  int mTime;
  std::string customName;
};

```

### `EnchantingTableBlockActor_vtbl`
```
struct /*VFT*/ EnchantingTableBlockActor_vtbl
{
  void (__fastcall *~BlockActor)(BlockActor *this);
  void (__fastcall *load)(BlockActor *this, Level *, const CompoundTag *, DataLoadHelper *);
  bool (__fastcall *save)(BlockActor *this, CompoundTag *);
  bool (__fastcall *saveItemInstanceData)(BlockActor *this, CompoundTag *);
  void (__fastcall *saveBlockData)(BlockActor *this, CompoundTag *, BlockSource *);
  void (__fastcall *loadBlockData)(BlockActor *this, const CompoundTag *, BlockSource *, DataLoadHelper *);
  void (__fastcall *onCustomTagLoadDone)(BlockActor *this, BlockSource *);
  void (__fastcall *tick)(BlockActor *this, BlockSource *);
  bool (__fastcall *isFinished)(BlockActor *this);
  void (__fastcall *onChanged)(BlockActor *this, BlockSource *);
  bool (__fastcall *isMovable)(BlockActor *this, BlockSource *);
  bool (__fastcall *isCustomNameSaved)(BlockActor *this);
  bool (__fastcall *onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *, const Player *);
  void (__fastcall *onPlace)(BlockActor *this, BlockSource *);
  void (__fastcall *onMove)(BlockActor *this);
  void (__fastcall *onRemoved)(BlockActor *this, BlockSource *);
  void (__fastcall *triggerEvent)(BlockActor *this, int, int);
  void (__fastcall *clearCache)(BlockActor *this);
  void (__fastcall *onNeighborChanged)(BlockActor *this, BlockSource *, const BlockPos *);
  float (__fastcall *getShadowRadius)(BlockActor *this, BlockSource *);
  bool (__fastcall *hasAlphaLayer)(BlockActor *this);
  BlockActor *(__fastcall *getCrackEntity)(BlockActor *this, BlockSource *, const BlockPos *);
  void (__fastcall *getDebugText)(BlockActor *this, std::vector<std::string> *, const BlockPos *);
  const std::string *(__fastcall *getCustomName)(BlockActor *this);
  const std::string *(__fastcall *getFilteredCustomName)(BlockActor *this, const UIProfanityContext *);
  std::string *(__fastcall *getName)(BlockActor *this, std::string *result);
  void (__fastcall *setCustomName)(BlockActor *this, const std::string *);
  std::string *(__fastcall *getImmersiveReaderText)(BlockActor *this, std::string *result, BlockSource *);
  int (__fastcall *getRepairCost)(BlockActor *this);
  PistonBlockActor *(__fastcall *getOwningPiston)(BlockActor *this, BlockSource *);
  const Container *(__fastcall *getContainer)(BlockActor *this);
  Container *(__fastcall *getContainer)(BlockActor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(BlockActor *this);
  void (__fastcall *checkWordsOnChunkLoad)(BlockActor *this, LevelChunk *);
  void (__fastcall *checkWordsOnUpdate)(BlockActor *this, Player *);
  void (__fastcall *onChunkLoaded)(BlockActor *this, LevelChunk *);
  void (__fastcall *onChunkUnloaded)(BlockActor *this, LevelChunk *);
  std::unique_ptr<BlockActorDataPacket> *(__fastcall *_getUpdatePacket)(BlockActor *this, std::unique_ptr<BlockActorDataPacket> *result, BlockSource *);
  void (__fastcall *_onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *);
  bool (__fastcall *_playerCanUpdate)(BlockActor *this, const Player *);
};

```

### `ExternalContentManager::_importMCAddon::__l2::<lambda_d9093fe1973220a7d352f71cbaa4bd85>::()::__l5::<lambda_b639197a9bd09c144dd062dece3e740b>`
```
struct __cppobj ExternalContentManager::_importMCAddon::__l2::<lambda_d9093fe1973220a7d352f71cbaa4bd85>::()::__l5::<lambda_b639197a9bd09c144dd062dece3e740b>
{
  std::vector<Core::PathBuffer<std::string >> *foundItemsToImport;
};

```

### `ExternalContentManager::_importMCPack::__l2::<lambda_0d815293ee69d5854edcdfb58e4d6129>::()::__l88::<lambda_86239db0601c98e1102fe71a812cfc5c>`
```
struct __cppobj ExternalContentManager::_importMCPack::__l2::<lambda_0d815293ee69d5854edcdfb58e4d6129>::()::__l88::<lambda_86239db0601c98e1102fe71a812cfc5c>
{
  ExternalContentManager *const __this;
  ExternalContentManager::LoadingContentData loadingData;
};

```

### `ExternalContentManager::_importMCPack::__l2::<lambda_0d815293ee69d5854edcdfb58e4d6129>::()::__l88::<lambda_fb0f3614c3d9bd291afc44ee9f6ec8ff>`
```
struct __cppobj __declspec(align(8)) ExternalContentManager::_importMCPack::__l2::<lambda_0d815293ee69d5854edcdfb58e4d6129>::()::__l88::<lambda_fb0f3614c3d9bd291afc44ee9f6ec8ff>
{
  Core::PathBuffer<std::string > manifestPath;
  bool isZipStrategy;
};

```

### `ExternalContentManager::{ctor}::__l2::<lambda_f6eab664f77911d2f21bcbbc2809f0c1>`
```
struct __cppobj ExternalContentManager::{ctor}::__l2::<lambda_f6eab664f77911d2f21bcbbc2809f0c1>
{
  ExternalContentManager *const __this;
};

```

### `ExternalContentManager::{ctor}::__l2::<lambda_0bd60419510b8462a93c0cd55abe41ca>`
```
struct __cppobj ExternalContentManager::{ctor}::__l2::<lambda_0bd60419510b8462a93c0cd55abe41ca>
{
  ExternalContentManager *const __this;
};

```

### `EDUDiscovery::QueryContext<enum EDUDiscovery::Availability>::<lambda_58ea59dd23cdc0a3b1f96bdc88d2297c>`
```
struct __cppobj EDUDiscovery::QueryContext<enum EDUDiscovery::Availability>::<lambda_58ea59dd23cdc0a3b1f96bdc88d2297c>
{
};

```

### `EntitlementManagerFactory`
```
struct __cppobj EntitlementManagerFactory
{
};

```

### `EduTransactionHandler::transactFulfillment::__l2::<lambda_341952be6d1717efcb6d96d964d3eac3>`
```
struct __cppobj EduTransactionHandler::transactFulfillment::__l2::<lambda_341952be6d1717efcb6d96d964d3eac3>
{
  EduTransactionHandler *const __this;
  std::shared_ptr<MinecraftScreenModel> minecraftScreenModel;
  std::shared_ptr<Purchase> purchase;
  Offer *offer;
};

```

### `EquipItemComponent::Definition`
```
struct __cppobj EquipItemComponent::Definition
{
};

```

### `EquipItemComponent`
```
struct __cppobj __declspec(align(8)) EquipItemComponent : IEntityComponent
{
  ItemStack mItemStack;
  bool mHasItemToEquip;
  int mCountToPickup;
  EquipItemComponent::Definition mDefinition;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,CameraShakeComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,CameraShakeComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,HitResultComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,HitResultComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,PlayerTickComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,PlayerTickComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EmptyActorGameplayHandler`
```
struct __cppobj EmptyActorGameplayHandler : ActorGameplayHandler
{
};

```

### `EmptyActorGameplayHandler_vtbl`
```
struct /*VFT*/ EmptyActorGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleActorGriefingBlock)(ActorGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ActorGriefingBlockEvent *);
  HandlerResult (__fastcall *handleActorAcquiredItem)(ActorGameplayHandler *this, const ActorAcquiredItemEvent *);
  HandlerResult (__fastcall *handleActorAddEffect)(ActorGameplayHandler *this, const ActorAddEffectEvent *);
  HandlerResult (__fastcall *handleActorAnimationChanged)(ActorGameplayHandler *this, const ActorAnimationChangedEvent *);
  HandlerResult (__fastcall *handleActorDefinitionEventTriggered)(ActorGameplayHandler *this, const ActorDefinitionEvent *);
  HandlerResult (__fastcall *handleActorHurt)(ActorGameplayHandler *this, const ActorHurtEvent *);
  HandlerResult (__fastcall *handleActorKilled)(ActorGameplayHandler *this, const ActorKilledEvent *);
  HandlerResult (__fastcall *handleActorRemoveEffect)(ActorGameplayHandler *this, const ActorRemoveEffectEvent *);
  HandlerResult (__fastcall *handleActorUseItem)(ActorGameplayHandler *this, const ActorUseItemEvent *);
  HandlerResult (__fastcall *handleKnockBack)(ActorGameplayHandler *this, const KnockBackEvent *);
  HandlerResult (__fastcall *handleMountTaming)(ActorGameplayHandler *this, const MountTamingEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleProjectileHit)(ActorGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ProjectileHitEvent *);
};

```

### `EmptyBlockGameplayHandler`
```
struct __cppobj EmptyBlockGameplayHandler : BlockGameplayHandler
{
};

```

### `EmptyBlockGameplayHandler_vtbl`
```
struct /*VFT*/ EmptyBlockGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleChestBlockTryPaired)(BlockGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ChestBlockTryPairEvent *);
};

```

### `EmptyPlayerGameplayHandler`
```
struct __cppobj EmptyPlayerGameplayHandler : PlayerGameplayHandler
{
};

```

### `EmptyPlayerGameplayHandler_vtbl`
```
struct /*VFT*/ EmptyPlayerGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  HandlerResult (__fastcall *handleAddExp)(PlayerGameplayHandler *this, const PlayerAddExpEvent *);
  HandlerResult (__fastcall *handleAddLevel)(PlayerGameplayHandler *this, const PlayerAddLevelEvent *);
  HandlerResult (__fastcall *handleArmorExchange)(PlayerGameplayHandler *this, const PlayerArmorExchangeEvent *);
  HandlerResult (__fastcall *handleDestroyBlock)(PlayerGameplayHandler *this, const PlayerDestroyBlockEvent *);
  HandlerResult (__fastcall *handleDie)(PlayerGameplayHandler *this, const PlayerDamageEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleGetExperienceOrb)(PlayerGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const PlayerGetExperienceOrbEvent *);
  HandlerResult (__fastcall *handleHurt)(PlayerGameplayHandler *this, const PlayerDamageEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleSayCommand)(PlayerGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const PlayerSayCommandEvent *);
  HandlerResult (__fastcall *handleShootArrow)(PlayerGameplayHandler *this, const PlayerShootArrowEvent *);
  HandlerResult (__fastcall *handleStopLoading)(PlayerGameplayHandler *this, const PlayerEvent *);
  HandlerResult (__fastcall *handleUseNameTag)(PlayerGameplayHandler *this, const PlayerUseNameTagEvent *);
};

```

### `EventCommand`
```
struct __cppobj EventCommand : Command
{
  EventCommand::EventAction mAction;
  __declspec(align(8)) CommandSelector<Actor> mTargets;
  std::string mEventName;
};

```

### `EventCommand_vtbl`
```
struct /*VFT*/ EventCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ExpressionNode::<lambda_730195dd5fb9ecbde21124a96b32e632>`
```
struct __cppobj ExpressionNode::<lambda_730195dd5fb9ecbde21124a96b32e632>
{
};

```

### `ExpressionNode::queryFunctionAccessorFromString::__l8::<lambda_cb4ab18883ed186d1fefa3f284ee16db>`
```
struct __cppobj ExpressionNode::queryFunctionAccessorFromString::__l8::<lambda_cb4ab18883ed186d1fefa3f284ee16db>
{
  const std::string functionName;
};

```

### `ExpressionNode::queryFunctionAccessorFromString::__l8::<lambda_cb4ab18883ed186d1fefa3f284ee16db>::()::__l2::<lambda_8a33fc954b83f09769c22204e1b28bfb>`
```
struct __cppobj ExpressionNode::queryFunctionAccessorFromString::__l8::<lambda_cb4ab18883ed186d1fefa3f284ee16db>::()::__l2::<lambda_8a33fc954b83f09769c22204e1b28bfb>
{
  RenderParams *renderParams;
  const std::string *functionName;
};

```

### `EventResponseCollection::buildSchema::__l2::<lambda_766e35e330802d837c272a7db62a8d18>`
```
struct __cppobj EventResponseCollection::buildSchema::__l2::<lambda_766e35e330802d837c272a7db62a8d18>
{
  const Factory<EventResponse> *factory;
};

```

### `EndOfString<44,73,84,92>`
```
struct __cppobj EndOfString<44,73,84,92>
{
};

```

### `EndOfString<43,65,95,66>`
```
struct __cppobj EndOfString<43,65,95,66>
{
};

```

### `EndOfString<45,68,94,123,76,65,68,73>`
```
struct __cppobj EndOfString<45,68,94,123,76,65,68,73>
{
};

```

### `EndOfString<41,89,72,80,69,70,72,77>`
```
struct __cppobj EndOfString<41,89,72,80,69,70,72,77>
{
};

```

### `EndOfString<40,90,77,91,88,71,70,91,77>`
```
struct __cppobj EndOfString<40,90,77,91,88,71,70,91,77>
{
};

```

### `EndOfString<42,88,79,91,95,79,89,94,99,78>`
```
struct __cppobj EndOfString<42,88,79,91,95,79,89,94,99,78>
{
};

```

### `EndOfString<37,77,81,81,85,86,31,10,10,72,64,64,86,64,87,83,76,70,64,86,8,86,81,68,66,76,75,66,11,68,95,80,87,64,82,64,71,86,76,81,64,86,11,75,64,81,10>`
```
struct __cppobj EndOfString<37,77,81,81,85,86,31,10,10,72,64,64,86,64,87,83,76,70,64,86,8,86,81,68,66,76,75,66,11,68,95,80,87,64,82,64,71,86,76,81,64,86,11,75,64,81,10>
{
};

```

### `EndOfString<39,106,110,110,101,110,77,102,105,101,64,76,86,79,76,78,96,30,80,23,101,102,118,98,97,102,102,104,100,102,118,31,102,106,110,110,101,100,64,108,100,102,118,98,102,78,109,82,30,64,17,105,117,82,21,119,67,93,109,21,99,70,93,64,110,106,30,78,19,108,79,67,8,64,16,65,98,106,108,77,127,96,84,100,94,83,94,98,12,22,112,70,23,95,118,115,115,116,74,118,113,85,73,84,95,31,108,116,70,16,64,113,80,73,20,127,99,109,114,100,102,74,109,16,79,31,102,17,126,22,126,87,106,116,80,115,65,125,12,98,70,115,67,82,96,117,110,97,98,23,22,78,105,81,67,22,80,126,119,117,65,107,96,67,17,30,87,87,18,64,31,72,76,77,106,108,115,82,22,118,110,102,98,76,127,94,99,116,72,114,73,119,110,113,97,127,98,70,84,104,16,112,78,30,73,73,100,65,20,105,80,68,75,114,95,126,93,111,77,23,12,31,104,68,111,117,81,94,102,17,126,19,97,127,102,73,87,96,74,100,75,112,79,75,98,97,97,68,75,87,116,64,23,87,76,12,78,22,81,85,110,93,108,112,75,16,107,75,113,18,68,106,113,17,87,87,99,8,21,111,72,87,117,96,77,76,22,98,101,81,112,21,19,82,118,22,67,86,82,87,21,12,76,115,21,87,119,70,98,68,86,65,83,85,12,74,76,106,81,126,83,17,126,118,85,75,81,74,99,115,66,93,18,67,125,125,106,119,106,70,100,72,12,72,72,65,95,18,112,111,93,20,19,127,95,12,106,127,109,85,87,110,65,69,20,126,104,99,115,109,104,81,80,22,75,20,97,74,8,96,12,30,75,69,101,116,80,110,99,102,118,102,101>`
```
struct __cppobj EndOfString<39,106,110,110,101,110,77,102,105,101,64,76,86,79,76,78,96,30,80,23,101,102,118,98,97,102,102,104,100,102,118,31,102,106,110,110,101,100,64,108,100,102,118,98,102,78,109,82,30,64,17,105,117,82,21,119,67,93,109,21,99,70,93,64,110,106,30,78,19,108,79,67,8,64,16,65,98,106,108,77,127,96,84,100,94,83,94,98,12,22,112,70,23,95,118,115,115,116,74,118,113,85,73,84,95,31,108,116,70,16,64,113,80,73,20,127,99,109,114,100,102,74,109,16,79,31,102,17,126,22,126,87,106,116,80,115,65,125,12,98,70,115,67,82,96,117,110,97,98,23,22,78,105,81,67,22,80,126,119,117,65,107,96,67,17,30,87,87,18,64,31,72,76,77,106,108,115,82,22,118,110,102,98,76,127,94,99,116,72,114,73,119,110,113,97,127,98,70,84,104,16,112,78,30,73,73,100,65,20,105,80,68,75,114,95,126,93,111,77,23,12,31,104,68,111,117,81,94,102,17,126,19,97,127,102,73,87,96,74,100,75,112,79,75,98,97,97,68,75,87,116,64,23,87,76,12,78,22,81,85,110,93,108,112,75,16,107,75,113,18,68,106,113,17,87,87,99,8,21,111,72,87,117,96,77,76,22,98,101,81,112,21,19,82,118,22,67,86,82,87,
{
};

```

### `EnvironmentRequirement`
```
struct __cppobj EnvironmentRequirement
{
  std::vector<BlockDescriptor> mBlockTypes;
  unsigned int mNumBlocksRequired;
  unsigned int mSearchRadius;
};

```

### `EntitySensorDefinition`
```
struct __cppobj EntitySensorDefinition
{
  float mSensorRange;
  bool mRelativeRange;
  int mMinimumCount;
  int mMaximumCount;
  bool mRequireAll;
  ActorFilterGroup mEventCondition;
  std::string mEventName;
};

```

### `EnvironmentSensorDefinition`
```
struct __cppobj EnvironmentSensorDefinition
{
  std::vector<DefinitionTrigger> mTriggers;
};

```

### `EquippableComponent`
```
struct __cppobj EquippableComponent : IEntityComponent
{
  std::vector<SlotDescriptor> mSlots;
};

```

### `ExperienceRewardDefinition`
```
struct __cppobj ExperienceRewardDefinition
{
  std::vector<ExpressionNode> mOnBred;
  std::vector<ExpressionNode> mOnDeath;
};

```

### `ExplodeComponent`
```
struct __cppobj __declspec(align(4)) ExplodeComponent : IEntityComponent
{
  int mFuseLength;
  int mInitialFuseLength;
  float mExplosionPower;
  float mMaxResistance;
  bool mIsFuseLit;
  bool mCausesFire;
  bool mBreaksBlocks;
  bool mFireAffectedByGriefing;
  bool mDestroyAffectedByGriefing;
  bool mAllowUnderwater;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntitySensorSystem`
```
struct __cppobj EntitySensorSystem : ITickingSystem
{
};

```

### `EntitySensorSystem_vtbl`
```
struct /*VFT*/ EntitySensorSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `EnvironmentSensorSystem`
```
struct __cppobj EnvironmentSensorSystem : ITickingSystem
{
};

```

### `EnvironmentSensorSystem_vtbl`
```
struct /*VFT*/ EnvironmentSensorSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DebugInfoComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DebugInfoComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,GroupSizeComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,GroupSizeComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MobEffectComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MobEffectComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,ActorComponent,RailMovementComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,ActorComponent,RailMovementComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>
{
  EntityRegistry *mRegistry;
};

```

### `EmoteListPacket::read::__l2::<lambda_882160dae8f12f17baa8823226614227>`
```
struct __cppobj EmoteListPacket::read::__l2::<lambda_882160dae8f12f17baa8823226614227>
{
};

```

### `EmoteListPacket::write::__l2::<lambda_c8a8b302758f3d4fe6df677e7ecd6f28>`
```
struct __cppobj EmoteListPacket::write::__l2::<lambda_c8a8b302758f3d4fe6df677e7ecd6f28>
{
};

```

### `EduKeyProvider`
```
struct __cppobj EduKeyProvider : IContentAccessibilityProvider
{
  std::function<std::string __cdecl(void)> mGetKey;
  std::unordered_map<ContentIdentity,std::string> mTempContentKeys;
};

```

### `EduKeyProvider_vtbl`
```
struct /*VFT*/ EduKeyProvider_vtbl
{
  void (__fastcall *~IContentKeyProvider)(IContentKeyProvider *this);
  std::string *(__fastcall *getContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  std::string *(__fastcall *getAlternateContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  bool (__fastcall *requireEncryptedReads)(IContentKeyProvider *this);
  void (__fastcall *setTempContentKeys)(IContentKeyProvider *this, const std::unordered_map<ContentIdentity,std::string> *);
  void (__fastcall *clearTempContentKeys)(IContentKeyProvider *this);
  bool (__fastcall *canAccess)(IContentAccessibilityProvider *this, const ContentIdentity *);
};

```

### `EndOfString<27,125,45,120,127,42,120,120,46,46,45,122,40,40,34,44,46,34,46,47,125,43,41,43,126,126,120,127,41,120,35,40,34>`
```
struct __cppobj EndOfString<27,125,45,120,127,42,120,120,46,46,45,122,40,40,34,44,46,34,46,47,125,43,41,43,126,126,120,127,41,120,35,40,34>
{
};

```

### `EduChinaAppConfigs`
```
struct __cppobj EduChinaAppConfigs : EduAppConfigs
{
};

```

### `EduChinaAppConfigs_vtbl`
```
struct /*VFT*/ EduChinaAppConfigs_vtbl
{
  void (__fastcall *~AppConfigs)(AppConfigs *this);
  void (__fastcall *loadFromData)(AppConfigs *this, const IAppConfigData *);
  bool (__fastcall *areResourcePacksAllowed)(AppConfigs *this);
  bool (__fastcall *isPlayScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isChatScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isGameTabShownInSettings)(AppConfigs *this);
  bool (__fastcall *areQuizzesSupported)(AppConfigs *this);
  bool (__fastcall *isLessonProgressionSupported)(AppConfigs *this);
  bool (__fastcall *useNormalizedFontSize)(AppConfigs *this);
  bool (__fastcall *useFullScreenByDefault)(AppConfigs *this);
  bool (__fastcall *muteByDefault)(AppConfigs *this);
  bool (__fastcall *isCoursesCacheEnabled)(AppConfigs *this);
  bool (__fastcall *shouldPromptBeforeExit)(AppConfigs *this);
  bool (__fastcall *gameArgumentsNeedAuthentication)(AppConfigs *this);
  bool (__fastcall *worldBuilderDisabled)(AppConfigs *this);
  bool (__fastcall *worldsAreSingleUse)(AppConfigs *this);
  EducationEditionOffer (__fastcall *getEducationEditionOffering)(AppConfigs *this);
  bool (__fastcall *requireTrustedContent)(AppConfigs *this);
  ConnectionDefinition *(__fastcall *getConnectionDefinition)(AppConfigs *this, ConnectionDefinition *result);
  bool (__fastcall *supportsChangingMultiplayerDuringPlay)(AppConfigs *this);
  bool (__fastcall *webSocketsDisabled)(AppConfigs *this);
  bool (__fastcall *sendPermissionsTelemetry)(AppConfigs *this);
  void (__fastcall *setCanAccessWorldCallback)(AppConfigs *this, IMinecraftGame *);
  std::vector<PackIdVersion> *(__fastcall *getAdditionalClientPacks)(AppConfigs *this, std::vector<PackIdVersion> *result, bool);
  std::unique_ptr<IScreenCapabilities> *(__fastcall *getScreenCapabilities)(AppConfigs *this, std::unique_ptr<IScreenCapabilities> *result, const std::string *);
  std::unique_ptr<IContentAccessibilityProvider> *(__fastcall *createContentAccessibility)(AppConfigs *this, std::unique_ptr<IContentAccessibilityProvider> *result, IEntitlementManager *);
  std::string *(__fastcall *getFeedbackURL)(AppConfigs *this, std::string *result);
  void (__fastcall *applyLevelDataOverride)(AppConfigs *this, LevelData *);
};

```

### `EducationMetadataError_vtbl`
```
struct /*VFT*/ EducationMetadataError_vtbl
{
  void (__fastcall *~PackError)(PackError *this);
  std::string *(__fastcall *getLocErrorMessage)(PackError *this, std::string *result);
  const std::unordered_map<int,std::string> *(__fastcall *getLocErrorMessageMap)(PackError *this);
  const std::unordered_map<int,std::string> *(__fastcall *getEventErrorMessageMap)(PackError *this);
};

```

### `ErrorPathStack`
```
struct __cppobj ErrorPathStack
{
  std::vector<std::string> *mErrorPath;
};

```

### `EncryptedFileAccessStrategy`
```
struct __cppobj EncryptedFileAccessStrategy : DirectoryPackAccessStrategy
{
  ContentIdentity mContentIdentity;
  const IContentKeyProvider *mKeyProvider;
  std::unordered_map<Core::PathBuffer<std::string >,std::string,std::hash<Core::PathBuffer<std::string > >,std::equal_to<Core::PathBuffer<std::string > >,std::allocator<std::pair<Core::PathBuffer<std::string > const ,std::string > > > mEncryptedAssetSet;
};

```

### `EncryptedFileAccessStrategy_vtbl`
```
struct /*VFT*/ EncryptedFileAccessStrategy_vtbl
{
  void (__fastcall *~PackAccessStrategy)(PackAccessStrategy *this);
  unsigned __int64 (__fastcall *getPackSize)(PackAccessStrategy *this);
  const ResourceLocation *(__fastcall *getPackLocation)(PackAccessStrategy *this);
  const std::string *(__fastcall *getPackName)(PackAccessStrategy *this);
  bool (__fastcall *isWritable)(PackAccessStrategy *this);
  void (__fastcall *setIsTrusted)(PackAccessStrategy *this, bool);
  bool (__fastcall *isTrusted)(PackAccessStrategy *this);
  bool (__fastcall *hasAsset)(PackAccessStrategy *this, const Core::Path *, bool);
  bool (__fastcall *hasFolder)(PackAccessStrategy *this, const Core::Path *);
  bool (__fastcall *getAsset)(PackAccessStrategy *this, const Core::Path *, std::string *, bool);
  bool (__fastcall *deleteAsset)(PackAccessStrategy *this, const Core::PathBuffer<std::string > *);
  bool (__fastcall *writeAsset)(PackAccessStrategy *this, const Core::Path *, const std::string *);
  void (__fastcall *forEachIn)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>, bool);
  void (__fastcall *forEachInAssetSet)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>);
  PackAccessStrategyType (__fastcall *getStrategyType)(PackAccessStrategy *this);
  const Core::PathBuffer<std::string > *(__fastcall *getSubPath)(PackAccessStrategy *this);
  std::unique_ptr<PackAccessStrategy> *(__fastcall *createSubPack)(PackAccessStrategy *this, std::unique_ptr<PackAccessStrategy> *result, const Core::Path *);
  PackAccessAssetGenerationResult (__fastcall *generateAssetSet)(PackAccessStrategy *this);
  bool (__fastcall *canRecurse)(PackAccessStrategy *this);
  void (__fastcall *unload)(PackAccessStrategy *this);
  __int64 (__fastcall *getLastModifiedTime)(PackAccessStrategy *this, const Core::Path *);
  std::unique_ptr<IDataOutput> *(__fastcall *createEncryptor)(PackAccessStrategy *this, std::unique_ptr<IDataOutput> *result, std::unique_ptr<IDataOutput>);
  std::unique_ptr<IDataInput> *(__fastcall *createDecryptor)(PackAccessStrategy *this, std::unique_ptr<IDataInput> *result, std::unique_ptr<IDataInput>);
  bool (__fastcall *hasUpgradeFiles)(PackAccessStrategy *this);
  ContentIdentity *(__fastcall *readContentIdentity)(PackAccessStrategy *this, ContentIdentity *result);
  bool (__fastcall *hasFile)(PackAccessStrategy *this, const Core::Path *);
  void (__fastcall *setSubPathAsPackName)(PackAccessStrategy *this);
};

```

### `EncryptedZipTransforms`
```
struct __cppobj EncryptedZipTransforms : FileAccessTransforms
{
  const IContentKeyProvider *mKeyProvider;
};

```

### `EncryptedZipTransforms_vtbl`
```
struct /*VFT*/ EncryptedZipTransforms_vtbl
{
  void (__fastcall *~FileAccessTransforms)(FileAccessTransforms *this);
  bool (__fastcall *readTransform)(FileAccessTransforms *this, std::vector<unsigned char> *);
  bool (__fastcall *writeTransform)(FileAccessTransforms *this, std::vector<unsigned char> *);
};

```

### `EmptyMapItem`
```
struct __cppobj EmptyMapItem : ComplexItem
{
};

```

### `EffectCommand`
```
struct __cppobj __declspec(align(8)) EffectCommand : Command
{
  CommandSelector<Actor> mTargets;
  EffectCommand::Mode mMode;
  const MobEffect *mEffect;
  int mDuration;
  int mAmplifier;
  bool mHideParticles;
};

```

### `EffectCommand_vtbl`
```
struct /*VFT*/ EffectCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ExecuteCommand`
```
struct __cppobj ExecuteCommand : Command
{
  CommandSelector<Actor> mTargets;
  CommandPositionFloat mPosition;
  CommandPosition mDetectPosition;
  const Block *mBlock;
  int mBlockData;
  ExecuteCommand::Mode mMode;
  std::unique_ptr<Command> mCommand;
};

```

### `ExecuteCommand_vtbl`
```
struct /*VFT*/ ExecuteCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `EnableEduNpcCommand`
```
struct __cppobj __declspec(align(8)) EnableEduNpcCommand : Command
{
  bool mEnable;
};

```

### `EnableEduNpcCommand_vtbl`
```
struct /*VFT*/ EnableEduNpcCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `EncryptedDataInput`
```
struct __cppobj EncryptedDataInput : BytesDataInput
{
  std::unique_ptr<IDataInput> mParent;
  std::unique_ptr<Crypto::Symmetric::ISystemInterface> mEncryption;
  std::string mKey;
  std::string mIV;
};

```

### `EncryptedDataInput_vtbl`
```
struct /*VFT*/ EncryptedDataInput_vtbl
{
  void (__fastcall *~IDataInput)(IDataInput *this);
  std::string *(__fastcall *readString)(IDataInput *this, std::string *result);
  std::string *(__fastcall *readLongString)(IDataInput *this, std::string *result);
  float (__fastcall *readFloat)(IDataInput *this);
  long double (__fastcall *readDouble)(IDataInput *this);
  char (__fastcall *readByte)(IDataInput *this);
  __int16 (__fastcall *readShort)(IDataInput *this);
  int (__fastcall *readInt)(IDataInput *this);
  __int64 (__fastcall *readLongLong)(IDataInput *this);
  bool (__fastcall *readBytes)(IDataInput *this, void *, unsigned __int64);
  unsigned __int64 (__fastcall *numBytesLeft)(IDataInput *this);
  bool (__fastcall *isOk)(IDataInput *this);
  bool (__fastcall *seek)(IDataInput *this, unsigned __int64);
};

```

### `EncryptedDataOutput`
```
struct __cppobj EncryptedDataOutput : BytesDataOutput
{
  std::unique_ptr<IDataOutput> mParent;
  std::unique_ptr<Crypto::Symmetric::ISystemInterface> mEncryption;
  std::string mKey;
  std::string mIV;
};

```

### `EncryptedDataOutput_vtbl`
```
struct /*VFT*/ EncryptedDataOutput_vtbl
{
  void (__fastcall *~IDataOutput)(IDataOutput *this);
  void (__fastcall *writeString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeLongString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeFloat)(IDataOutput *this, float);
  void (__fastcall *writeDouble)(IDataOutput *this, long double);
  void (__fastcall *writeByte)(IDataOutput *this, char);
  void (__fastcall *writeShort)(IDataOutput *this, __int16);
  void (__fastcall *writeInt)(IDataOutput *this, int);
  void (__fastcall *writeLongLong)(IDataOutput *this, __int64);
  void (__fastcall *writeBytes)(IDataOutput *this, const void *, unsigned __int64);
  bool (__fastcall *isOk)(IDataOutput *this);
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_df0dfb03288bf95d96bfe1947eb925d0>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_df0dfb03288bf95d96bfe1947eb925d0>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_dcf91af2417abbc552bbedb3a40d43a1>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_dcf91af2417abbc552bbedb3a40d43a1>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_2da74e5c6d2333016d60c44fba5b0951>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_2da74e5c6d2333016d60c44fba5b0951>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_9ff2a18fbc37c90b6ec6a6dd019b0c9c>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_9ff2a18fbc37c90b6ec6a6dd019b0c9c>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_3918663b65efac5de29460ee3092c791>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_3918663b65efac5de29460ee3092c791>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_87df4319fadd750ca927b98114af8857>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_87df4319fadd750ca927b98114af8857>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_81d87ee9c74c8ed30ed407f9912976ec>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_81d87ee9c74c8ed30ed407f9912976ec>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_d9ad316af0a2ace8601e25c5d8c25f74>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_d9ad316af0a2ace8601e25c5d8c25f74>
{
  Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_81d87ee9c74c8ed30ed407f9912976ec> easeOutBounce;
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_1422e756ba32738ea86093d600da0cd4>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_1422e756ba32738ea86093d600da0cd4>
{
  Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_d9ad316af0a2ace8601e25c5d8c25f74> easeInBounce;
  Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_81d87ee9c74c8ed30ed407f9912976ec> easeOutBounce;
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_cfce28ea581993c2dcdf4e0e47105678>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_cfce28ea581993c2dcdf4e0e47105678>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_d80965e4011326483fa91074481ef790>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_d80965e4011326483fa91074481ef790>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_9c2c0411522d2174e9d370067c4b88f4>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_9c2c0411522d2174e9d370067c4b88f4>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_6a6660ff28395711b6f0520f4f08ef22>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_6a6660ff28395711b6f0520f4f08ef22>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a77bbf45cec5882a57f92431e176fd0b>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a77bbf45cec5882a57f92431e176fd0b>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_df13a3c84cfc4caf1dba313f3f205935>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_df13a3c84cfc4caf1dba313f3f205935>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_89c56a0307fba15f9a771fdeca3a6f1e>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_89c56a0307fba15f9a771fdeca3a6f1e>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a13f8e03b718465cb571f6872512ca5d>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a13f8e03b718465cb571f6872512ca5d>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_7a9edc05f7896b4dac2ea87985be0eaa>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_7a9edc05f7896b4dac2ea87985be0eaa>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_8cdc208fb080a9ed5e35ae15edd2c747>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_8cdc208fb080a9ed5e35ae15edd2c747>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_3a7ec2d4f86d22d735c89a0c182b0ef2>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_3a7ec2d4f86d22d735c89a0c182b0ef2>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_80ab98d828924235d0a6049580fb27b1>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_80ab98d828924235d0a6049580fb27b1>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_34887b7ec06d3666c164a001743a9400>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_34887b7ec06d3666c164a001743a9400>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_8b84791ec9ada0764de8b73ace6cc07c>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_8b84791ec9ada0764de8b73ace6cc07c>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_24e6f210faf01edcb3e1108641c242fd>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_24e6f210faf01edcb3e1108641c242fd>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_2aab5dbc3cda1c9f1ec94a1c85cf4b40>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_2aab5dbc3cda1c9f1ec94a1c85cf4b40>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_44141c1509ac942352b0154700d8b99d>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_44141c1509ac942352b0154700d8b99d>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_50362e548cfa032085baf148b08c4f28>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_50362e548cfa032085baf148b08c4f28>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_e539974d004b8a04be25d7d2eebd1864>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_e539974d004b8a04be25d7d2eebd1864>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_38823b428f966015fb61dbc4c1dcba81>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_38823b428f966015fb61dbc4c1dcba81>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a4e8ea2bd8736774ffb99d77ea9a64a4>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_a4e8ea2bd8736774ffb99d77ea9a64a4>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_1e6c893d22d81df9cf521ded6602a9af>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_1e6c893d22d81df9cf521ded6602a9af>
{
};

```

### `Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_ceefefec1795c88bdf0862c2fd9a6807>`
```
struct __cppobj Easing::<lambda_8e6c056dd78e7e9d85d20851f83020f0>::()::__l2::<lambda_ceefefec1795c88bdf0862c2fd9a6807>
{
};

```

### `EntityRegistryBase::View<EntityContext,EntityRegistry,ActorComponent>`
```
struct __cppobj EntityRegistryBase::View<EntityContext,EntityRegistry,ActorComponent>
{
  EntityRegistry *mRegistry;
};

```

### `ExpressionNode::_buildProgram::__l585::<lambda_02d561912213bc21a45f53a2483e6105>`
```
struct __cppobj ExpressionNode::_buildProgram::__l585::<lambda_02d561912213bc21a45f53a2483e6105>
{
  const MolangScriptArg *value;
};

```

### `ExpressionNode::_buildProgram::__l583::<lambda_c275e092af79881de7ffb604313d94b6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l583::<lambda_c275e092af79881de7ffb604313d94b6>
{
  float value;
};

```

### `ExpressionNode::_buildProgram::__l7::<lambda_9ae9c8c4c94ff813a13a6e26cd25aaae>`
```
struct __cppobj ExpressionNode::_buildProgram::__l7::<lambda_9ae9c8c4c94ff813a13a6e26cd25aaae>
{
};

```

### `ExpressionNode::_buildProgram::__l7::<lambda_4fbf08146a22d8ef56ebef865957b173>`
```
struct __cppobj ExpressionNode::_buildProgram::__l7::<lambda_4fbf08146a22d8ef56ebef865957b173>
{
};

```

### `ExpressionNode::_buildProgram::__l580::<lambda_34288391e4a6276f53db5d127072207b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l580::<lambda_34288391e4a6276f53db5d127072207b>
{
};

```

### `ExpressionNode::_buildProgram::__l578::<lambda_02578d57b14e3a8ef39b708f88e56f54>`
```
struct __cppobj ExpressionNode::_buildProgram::__l578::<lambda_02578d57b14e3a8ef39b708f88e56f54>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l570::<lambda_69c344274de8fba4d870fee5c68f7a3b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l570::<lambda_69c344274de8fba4d870fee5c68f7a3b>
{
  float addValue;
  float mulValue;
  const std::function<MolangScriptArg const & __cdecl(RenderParams &,std::vector<ExpressionNode> const &)> *queryFunctionPtr;
  std::vector<ExpressionNode> args;
};

```

### `ExpressionNode::_buildProgram::__l559::<lambda_6c9ce42c1bbbce913721cd79a3c62c61>`
```
struct __cppobj __declspec(align(8)) ExpressionNode::_buildProgram::__l559::<lambda_6c9ce42c1bbbce913721cd79a3c62c61>
{
  unsigned __int64 loopCleanup;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l555::<lambda_494a9d9453b1aa080a58392e58b6d946>`
```
struct __cppobj __declspec(align(8)) ExpressionNode::_buildProgram::__l555::<lambda_494a9d9453b1aa080a58392e58b6d946>
{
  unsigned __int64 loopCleanup;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l529::<lambda_c33baca436a3d1838dbbf77994018e99>`
```
struct __cppobj ExpressionNode::_buildProgram::__l529::<lambda_c33baca436a3d1838dbbf77994018e99>
{
  unsigned __int64 nextStatement;
  unsigned __int64 loopIterationLogicCheck;
  unsigned __int64 loopCleanup;
};

```

### `ExpressionNode::_buildProgram::__l542::<lambda_f16f404e6aeb8305d31ebe5125a0e323>`
```
struct __cppobj __declspec(align(8)) ExpressionNode::_buildProgram::__l542::<lambda_f16f404e6aeb8305d31ebe5125a0e323>
{
  unsigned __int64 loopStartCheckLogic;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l538::<lambda_5064ef2971d7881f2a56dde49ec4cbc4>`
```
struct __cppobj __declspec(align(8)) ExpressionNode::_buildProgram::__l538::<lambda_5064ef2971d7881f2a56dde49ec4cbc4>
{
  unsigned __int64 loopStartCheckLogic;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l522::<lambda_840507042c34518784e31562947f6fa5>`
```
struct __cppobj ExpressionNode::_buildProgram::__l522::<lambda_840507042c34518784e31562947f6fa5>
{
  unsigned __int64 loopStart;
  unsigned __int64 loopCleanup;
};

```

### `ExpressionNode::_buildProgram::__l521::<lambda_6c0ef5afc72f5a8cec48dfd636d9756d>`
```
struct __cppobj ExpressionNode::_buildProgram::__l521::<lambda_6c0ef5afc72f5a8cec48dfd636d9756d>
{
};

```

### `ExpressionNode::_buildProgram::__l519::<lambda_4efdcc0a49604387b9928ad55284a6bd>`
```
struct __cppobj ExpressionNode::_buildProgram::__l519::<lambda_4efdcc0a49604387b9928ad55284a6bd>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l509::<lambda_12110cb555757cb0d56f264bd53f6028>`
```
struct __cppobj ExpressionNode::_buildProgram::__l509::<lambda_12110cb555757cb0d56f264bd53f6028>
{
  unsigned __int64 falseCaseStart;
};

```

### `ExpressionNode::_buildProgram::__l515::<lambda_ab8d3fa8e74a1c31e63a5418224b2978>`
```
struct __cppobj ExpressionNode::_buildProgram::__l515::<lambda_ab8d3fa8e74a1c31e63a5418224b2978>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l507::<lambda_5954eca4e895d7a939d38a0e6c72990c>`
```
struct __cppobj ExpressionNode::_buildProgram::__l507::<lambda_5954eca4e895d7a939d38a0e6c72990c>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l504::<lambda_723a36e8cd59494e71c26ac945cea6ac>`
```
struct __cppobj ExpressionNode::_buildProgram::__l504::<lambda_723a36e8cd59494e71c26ac945cea6ac>
{
  unsigned __int64 nextStatement;
};

```

### `ExpressionNode::_buildProgram::__l491::<lambda_3ce78d94534333071fc413f8729ea857>`
```
struct __cppobj ExpressionNode::_buildProgram::__l491::<lambda_3ce78d94534333071fc413f8729ea857>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l489::<lambda_c1107dcf4bd9b5f5d92469e48762afab>`
```
struct __cppobj ExpressionNode::_buildProgram::__l489::<lambda_c1107dcf4bd9b5f5d92469e48762afab>
{
  float addValue;
  float mulValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l479::<lambda_4eeff537ac44a1952a601e44682ed320>`
```
struct __cppobj ExpressionNode::_buildProgram::__l479::<lambda_4eeff537ac44a1952a601e44682ed320>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l477::<lambda_9264886225ad912225afbfa336201250>`
```
struct __cppobj ExpressionNode::_buildProgram::__l477::<lambda_9264886225ad912225afbfa336201250>
{
  float addValue;
  float mulValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l461::<lambda_47b000480bb5a8d5a01b68c3b3bb9ff4>`
```
struct __cppobj ExpressionNode::_buildProgram::__l461::<lambda_47b000480bb5a8d5a01b68c3b3bb9ff4>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l451::<lambda_db491cb11735e50effe3625096a86503>`
```
struct __cppobj ExpressionNode::_buildProgram::__l451::<lambda_db491cb11735e50effe3625096a86503>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l444::<lambda_a167ac6cb6c5766bf0ea74ffd3e52f3a>`
```
struct __cppobj ExpressionNode::_buildProgram::__l444::<lambda_a167ac6cb6c5766bf0ea74ffd3e52f3a>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l437::<lambda_ab3a591bac208f33133410ce613c2172>`
```
struct __cppobj ExpressionNode::_buildProgram::__l437::<lambda_ab3a591bac208f33133410ce613c2172>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l427::<lambda_d09056f8a65de6e4fd5222b9d1e51545>`
```
struct __cppobj ExpressionNode::_buildProgram::__l427::<lambda_d09056f8a65de6e4fd5222b9d1e51545>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l417::<lambda_556457a8492f46bf288f12ef716e3ea9>`
```
struct __cppobj ExpressionNode::_buildProgram::__l417::<lambda_556457a8492f46bf288f12ef716e3ea9>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l413::<lambda_a9a89e99a5bb09b600f60399763ab96d>`
```
struct __cppobj ExpressionNode::_buildProgram::__l413::<lambda_a9a89e99a5bb09b600f60399763ab96d>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l409::<lambda_ce846036270c8adcc1da59079a1a08d6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l409::<lambda_ce846036270c8adcc1da59079a1a08d6>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l405::<lambda_90ecb5ee8999cf404a97b48016a78448>`
```
struct __cppobj ExpressionNode::_buildProgram::__l405::<lambda_90ecb5ee8999cf404a97b48016a78448>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l401::<lambda_99133d12e6b2aaa2b54eef6c78cd5f80>`
```
struct __cppobj ExpressionNode::_buildProgram::__l401::<lambda_99133d12e6b2aaa2b54eef6c78cd5f80>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l397::<lambda_a88e99baf48224278e02f137d27ef6fa>`
```
struct __cppobj ExpressionNode::_buildProgram::__l397::<lambda_a88e99baf48224278e02f137d27ef6fa>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l395::<lambda_642cf1929c865f16b73d34e19590c69a>`
```
struct __cppobj ExpressionNode::_buildProgram::__l395::<lambda_642cf1929c865f16b73d34e19590c69a>
{
  float addValue;
  float mulValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l385::<lambda_675c2fc048fec5261fe36d7e969e7b8c>`
```
struct __cppobj ExpressionNode::_buildProgram::__l385::<lambda_675c2fc048fec5261fe36d7e969e7b8c>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l381::<lambda_04938591e5e3d6afa7329e4d37967106>`
```
struct __cppobj ExpressionNode::_buildProgram::__l381::<lambda_04938591e5e3d6afa7329e4d37967106>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l377::<lambda_274a5f81fbc4cce7f6969d77fb7ba8c8>`
```
struct __cppobj ExpressionNode::_buildProgram::__l377::<lambda_274a5f81fbc4cce7f6969d77fb7ba8c8>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l373::<lambda_ea893e8c5bdcc49d2cac2e6f73ba7c32>`
```
struct __cppobj ExpressionNode::_buildProgram::__l373::<lambda_ea893e8c5bdcc49d2cac2e6f73ba7c32>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l369::<lambda_6f9ffba401d560e5dbf75b5da1070698>`
```
struct __cppobj ExpressionNode::_buildProgram::__l369::<lambda_6f9ffba401d560e5dbf75b5da1070698>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l367::<lambda_63d67b73775ae751460a327f48e9108e>`
```
struct __cppobj ExpressionNode::_buildProgram::__l367::<lambda_63d67b73775ae751460a327f48e9108e>
{
  float addValue;
  float mulValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l351::<lambda_521ef6d17eeda4f3caa42540320d71bf>`
```
struct __cppobj ExpressionNode::_buildProgram::__l351::<lambda_521ef6d17eeda4f3caa42540320d71bf>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l347::<lambda_86667dd5b7ac0e8086ec4addae046cf6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l347::<lambda_86667dd5b7ac0e8086ec4addae046cf6>
{
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l343::<lambda_f9f1cae58aa3d4ecff203529b34cff97>`
```
struct __cppobj ExpressionNode::_buildProgram::__l343::<lambda_f9f1cae58aa3d4ecff203529b34cff97>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l339::<lambda_5bade2b8f71f444747f5f2f73ccb826d>`
```
struct __cppobj ExpressionNode::_buildProgram::__l339::<lambda_5bade2b8f71f444747f5f2f73ccb826d>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l332::<lambda_3040a7dfb856d6de5c84dcf86df990a6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l332::<lambda_3040a7dfb856d6de5c84dcf86df990a6>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l325::<lambda_5e31f164965b74989e936ba07a9b3d7b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l325::<lambda_5e31f164965b74989e936ba07a9b3d7b>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l321::<lambda_382f7c34fb30000e95db3c28eac59adb>`
```
struct __cppobj ExpressionNode::_buildProgram::__l321::<lambda_382f7c34fb30000e95db3c28eac59adb>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l317::<lambda_6303bd895255839376744bd4d4d9be58>`
```
struct __cppobj ExpressionNode::_buildProgram::__l317::<lambda_6303bd895255839376744bd4d4d9be58>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l313::<lambda_c18cf728044a9a7ca1d38aef21e5a423>`
```
struct __cppobj ExpressionNode::_buildProgram::__l313::<lambda_c18cf728044a9a7ca1d38aef21e5a423>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l309::<lambda_b3b4385ed47b175f3c5f221ba52ea273>`
```
struct __cppobj ExpressionNode::_buildProgram::__l309::<lambda_b3b4385ed47b175f3c5f221ba52ea273>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l302::<lambda_ed1fecfd1fe64ddff89e65b80666c52f>`
```
struct __cppobj ExpressionNode::_buildProgram::__l302::<lambda_ed1fecfd1fe64ddff89e65b80666c52f>
{
  float mulAddValue;
  unsigned __int64 nextStatementIndex;
};

```

### `ExpressionNode::_buildProgram::__l302::<lambda_808bba35af1ea76e6d150bd1af15706c>`
```
struct __cppobj ExpressionNode::_buildProgram::__l302::<lambda_808bba35af1ea76e6d150bd1af15706c>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l295::<lambda_dc3c645aa0dc13ea78bc049e84ad1656>`
```
struct __cppobj ExpressionNode::_buildProgram::__l295::<lambda_dc3c645aa0dc13ea78bc049e84ad1656>
{
  float addValue;
  unsigned __int64 nextStatementIndex;
};

```

### `ExpressionNode::_buildProgram::__l295::<lambda_b38cca3ffa27a30bd6e98506723af62c>`
```
struct __cppobj ExpressionNode::_buildProgram::__l295::<lambda_b38cca3ffa27a30bd6e98506723af62c>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l291::<lambda_b84e1d32094ed2409585b2d6122d2cee>`
```
struct __cppobj ExpressionNode::_buildProgram::__l291::<lambda_b84e1d32094ed2409585b2d6122d2cee>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l287::<lambda_e284d3d36049161a5292995c796bc621>`
```
struct __cppobj ExpressionNode::_buildProgram::__l287::<lambda_e284d3d36049161a5292995c796bc621>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l285::<lambda_7f5b82aae4fbd88538912be82da322db>`
```
struct __cppobj ExpressionNode::_buildProgram::__l285::<lambda_7f5b82aae4fbd88538912be82da322db>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l275::<lambda_a969ebe253f4e5f790dbf512bcd37ef6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l275::<lambda_a969ebe253f4e5f790dbf512bcd37ef6>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l273::<lambda_32379837db4ebd4fb78e138b5dd80932>`
```
struct __cppobj ExpressionNode::_buildProgram::__l273::<lambda_32379837db4ebd4fb78e138b5dd80932>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l263::<lambda_d57369e5379f8ec7dd77b04535bb9892>`
```
struct __cppobj ExpressionNode::_buildProgram::__l263::<lambda_d57369e5379f8ec7dd77b04535bb9892>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l259::<lambda_1554d51d6facc01c43ba48381ee57862>`
```
struct __cppobj ExpressionNode::_buildProgram::__l259::<lambda_1554d51d6facc01c43ba48381ee57862>
{
  float addValue;
  float mulAddValue;
  unsigned __int64 rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l255::<lambda_a959a2f4731b4f3182a686c200e1106b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l255::<lambda_a959a2f4731b4f3182a686c200e1106b>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l242::<lambda_6fe70cdaccf1f02c40d0474d5ee9db47>`
```
struct __cppobj ExpressionNode::_buildProgram::__l242::<lambda_6fe70cdaccf1f02c40d0474d5ee9db47>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l238::<lambda_c040d2ab9df307ab7f6761bd5a3e9d7e>`
```
struct __cppobj ExpressionNode::_buildProgram::__l238::<lambda_c040d2ab9df307ab7f6761bd5a3e9d7e>
{
  float addValue;
  float mulAddValue;
  unsigned __int64 rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l234::<lambda_fdf968de5074db74635b96c682ec3cb6>`
```
struct __cppobj ExpressionNode::_buildProgram::__l234::<lambda_fdf968de5074db74635b96c682ec3cb6>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l221::<lambda_13b160b8f1e707e8f186226022f7c2e4>`
```
struct __cppobj ExpressionNode::_buildProgram::__l221::<lambda_13b160b8f1e707e8f186226022f7c2e4>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l219::<lambda_4ec1b895cd519d94127f536be4b17596>`
```
struct __cppobj ExpressionNode::_buildProgram::__l219::<lambda_4ec1b895cd519d94127f536be4b17596>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l209::<lambda_bbb0f5db7371f83aab039bf8aec457a0>`
```
struct __cppobj ExpressionNode::_buildProgram::__l209::<lambda_bbb0f5db7371f83aab039bf8aec457a0>
{
  float addValue;
  float mulAddValue;
};

```

### `ExpressionNode::_buildProgram::__l207::<lambda_0458dfff8957d844ce8be63210b04783>`
```
struct __cppobj ExpressionNode::_buildProgram::__l207::<lambda_0458dfff8957d844ce8be63210b04783>
{
  float addValue;
  float mulAddValue;
  float rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l194::<lambda_68a1f8bf37ba8580d88e2a39cd7a7010>`
```
struct __cppobj ExpressionNode::_buildProgram::__l194::<lambda_68a1f8bf37ba8580d88e2a39cd7a7010>
{
  unsigned __int64 nextStatement;
};

```

### `ExpressionNode::_buildProgram::__l194::<lambda_ac5b66a383f0719d143a2d0cb52f8683>`
```
struct __cppobj ExpressionNode::_buildProgram::__l194::<lambda_ac5b66a383f0719d143a2d0cb52f8683>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l187::<lambda_6d6a79082b5505ee96f436ec6e611d5e>`
```
struct __cppobj ExpressionNode::_buildProgram::__l187::<lambda_6d6a79082b5505ee96f436ec6e611d5e>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l178::<lambda_b8233be6a48c926028c8e004af62d493>`
```
struct __cppobj ExpressionNode::_buildProgram::__l178::<lambda_b8233be6a48c926028c8e004af62d493>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l180::<lambda_d04ee7456a276022163559ae3d3cf94d>`
```
struct __cppobj ExpressionNode::_buildProgram::__l180::<lambda_d04ee7456a276022163559ae3d3cf94d>
{
};

```

### `ExpressionNode::_buildProgram::__l173::<lambda_2e75cba71ef9906f6de68cccc988e172>`
```
struct __cppobj ExpressionNode::_buildProgram::__l173::<lambda_2e75cba71ef9906f6de68cccc988e172>
{
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l171::<lambda_13e475af8ff8afc398110887e8d3b920>`
```
struct __cppobj __declspec(align(4)) ExpressionNode::_buildProgram::__l171::<lambda_13e475af8ff8afc398110887e8d3b920>
{
  float addValue;
  float mulValue;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l167::<lambda_20f1042cde2c21b5e13b9ddb7e5d622b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l167::<lambda_20f1042cde2c21b5e13b9ddb7e5d622b>
{
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l165::<lambda_0902883d6a5e48faedcfae72d1967599>`
```
struct __cppobj __declspec(align(4)) ExpressionNode::_buildProgram::__l165::<lambda_0902883d6a5e48faedcfae72d1967599>
{
  float addValue;
  float mulValue;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l161::<lambda_8a3f11e731200e437219583ae9a1e3ef>`
```
struct __cppobj ExpressionNode::_buildProgram::__l161::<lambda_8a3f11e731200e437219583ae9a1e3ef>
{
  unsigned __int64 nextStatement;
};

```

### `ExpressionNode::_buildProgram::__l159::<lambda_2523a2e0ca7583a6edbba934f08f85f1>`
```
struct __cppobj ExpressionNode::_buildProgram::__l159::<lambda_2523a2e0ca7583a6edbba934f08f85f1>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l159::<lambda_5266258eb509d623234175eb639f85b4>`
```
struct __cppobj ExpressionNode::_buildProgram::__l159::<lambda_5266258eb509d623234175eb639f85b4>
{
  float addValue;
  float mulValue;
  unsigned __int64 nextStatement;
};

```

### `ExpressionNode::_buildProgram::__l150::<lambda_c76cb41bd1a2df61dbe3ec88808a8109>`
```
struct __cppobj ExpressionNode::_buildProgram::__l150::<lambda_c76cb41bd1a2df61dbe3ec88808a8109>
{
  unsigned __int64 nextStatement;
};

```

### `ExpressionNode::_buildProgram::__l143::<lambda_cc572e85eb5b3bacefd86d554cd20e5b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l143::<lambda_cc572e85eb5b3bacefd86d554cd20e5b>
{
  ExpressionNode memberAccessor;
};

```

### `ExpressionNode::_buildProgram::__l141::<lambda_14c848e12aaca18c011e7b5ca2372eab>`
```
struct __cppobj ExpressionNode::_buildProgram::__l141::<lambda_14c848e12aaca18c011e7b5ca2372eab>
{
  float addValue;
  float mulValue;
  ExpressionNode memberAccessor;
};

```

### `ExpressionNode::_buildProgram::__l137::<lambda_1af5769cdfeb9ca80bb65292a54ec513>`
```
struct __cppobj ExpressionNode::_buildProgram::__l137::<lambda_1af5769cdfeb9ca80bb65292a54ec513>
{
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l135::<lambda_fdccd86f980251fadd4535a9f72aeb10>`
```
struct __cppobj __declspec(align(4)) ExpressionNode::_buildProgram::__l135::<lambda_fdccd86f980251fadd4535a9f72aeb10>
{
  float addValue;
  float mulValue;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l131::<lambda_3009dcec57d33164be95e312b7ae3e1d>`
```
struct __cppobj ExpressionNode::_buildProgram::__l131::<lambda_3009dcec57d33164be95e312b7ae3e1d>
{
  MolangScriptArg value;
};

```

### `ExpressionNode::_buildProgram::__l130::<lambda_2f8486be3caf6a56afa7da0b215b3845>`
```
struct __cppobj ExpressionNode::_buildProgram::__l130::<lambda_2f8486be3caf6a56afa7da0b215b3845>
{
};

```

### `ExpressionNode::_buildProgram::__l128::<lambda_7f2ebd9bc48782e7bd6c7c3ab7ad8876>`
```
struct __cppobj ExpressionNode::_buildProgram::__l128::<lambda_7f2ebd9bc48782e7bd6c7c3ab7ad8876>
{
  float addValue;
  float mulValue;
};

```

### `ExpressionNode::_buildProgram::__l119::<lambda_da569b9849ee514e9a489d9ed30aa5c9>`
```
struct __cppobj ExpressionNode::_buildProgram::__l119::<lambda_da569b9849ee514e9a489d9ed30aa5c9>
{
};

```

### `ExpressionNode::_buildProgram::__l110::<lambda_8b71d784c06a4bd36ba2acf74c21a23a>`
```
struct __cppobj ExpressionNode::_buildProgram::__l110::<lambda_8b71d784c06a4bd36ba2acf74c21a23a>
{
  unsigned __int64 arrayCount;
  const std::vector<ExpressionNode> *itemsSource;
};

```

### `ExpressionNode::_buildProgram::__l99::<lambda_f2129c39b7a581176cfaa5bb87b4b78e>`
```
struct __cppobj ExpressionNode::_buildProgram::__l99::<lambda_f2129c39b7a581176cfaa5bb87b4b78e>
{
  ExpressionNode memberAccessor;
};

```

### `ExpressionNode::_buildProgram::__l97::<lambda_555377ec604da24d98d6ac1bb22eb93a>`
```
struct __cppobj ExpressionNode::_buildProgram::__l97::<lambda_555377ec604da24d98d6ac1bb22eb93a>
{
  float addValue;
  float mulValue;
  ExpressionNode memberAccessor;
};

```

### `ExpressionNode::_buildProgram::__l89::<lambda_d6cf66862d5745df808d28b99f53c506>`
```
struct __cppobj ExpressionNode::_buildProgram::__l89::<lambda_d6cf66862d5745df808d28b99f53c506>
{
  ExpressionNode memberAccessor;
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l87::<lambda_f345da23ac49503053c539132764f69a>`
```
struct __cppobj ExpressionNode::_buildProgram::__l87::<lambda_f345da23ac49503053c539132764f69a>
{
  float returnValue;
  ExpressionNode memberAccessor;
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l77::<lambda_a3c76e64aad2d0e9ae4875879f82574b>`
```
struct __cppobj ExpressionNode::_buildProgram::__l77::<lambda_a3c76e64aad2d0e9ae4875879f82574b>
{
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l75::<lambda_ccdd9073806761a7a70854a656df81f5>`
```
struct __cppobj __declspec(align(4)) ExpressionNode::_buildProgram::__l75::<lambda_ccdd9073806761a7a70854a656df81f5>
{
  float addValue;
  float mulValue;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l67::<lambda_98f504cb25522885673e3f7c18a18797>`
```
struct __cppobj ExpressionNode::_buildProgram::__l67::<lambda_98f504cb25522885673e3f7c18a18797>
{
  _BYTE variableIndex[2];
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l65::<lambda_d91124f409b63c00cec234ac876cfe2f>`
```
struct __cppobj ExpressionNode::_buildProgram::__l65::<lambda_d91124f409b63c00cec234ac876cfe2f>
{
  float returnValue;
  _BYTE variableIndex[2];
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l55::<lambda_12f92e0415f7aec8191e4b025bbbe686>`
```
struct __cppobj ExpressionNode::_buildProgram::__l55::<lambda_12f92e0415f7aec8191e4b025bbbe686>
{
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l53::<lambda_71e47cb95e9f1b7a15741193368aaf5d>`
```
struct __cppobj __declspec(align(4)) ExpressionNode::_buildProgram::__l53::<lambda_71e47cb95e9f1b7a15741193368aaf5d>
{
  float addValue;
  float mulValue;
  _BYTE variableIndex[2];
};

```

### `ExpressionNode::_buildProgram::__l45::<lambda_30d9b5e48de6b345c394ca05cce9f85f>`
```
struct __cppobj ExpressionNode::_buildProgram::__l45::<lambda_30d9b5e48de6b345c394ca05cce9f85f>
{
  _BYTE variableIndex[2];
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l43::<lambda_b0b0d8c97a95dca9d48d51cddb523eca>`
```
struct __cppobj ExpressionNode::_buildProgram::__l43::<lambda_b0b0d8c97a95dca9d48d51cddb523eca>
{
  float returnValue;
  _BYTE variableIndex[2];
  MolangScriptArg rhsValue;
};

```

### `ExpressionNode::_buildProgram::__l12::<lambda_1d9d2bab92927534d53818f26708caff>`
```
struct __cppobj ExpressionNode::_buildProgram::__l12::<lambda_1d9d2bab92927534d53818f26708caff>
{
};

```

### `ExpressionNode::_buildProgram::__l18::<lambda_0c232f97c0fc32e32fff439c369930d8>`
```
struct __cppobj ExpressionNode::_buildProgram::__l18::<lambda_0c232f97c0fc32e32fff439c369930d8>
{
  float addValue;
};

```

### `ExpressionNode::_buildProgram::__l15::<lambda_45a7ef7c7e0367c34a563eab95daae44>`
```
struct __cppobj ExpressionNode::_buildProgram::__l15::<lambda_45a7ef7c7e0367c34a563eab95daae44>
{
  float addValue;
};

```

### `EvocationIllager`
```
struct __cppobj EvocationIllager : HumanoidMonster
{
};

```

### `EntityComponentDefinition<AmbientSoundIntervalDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AmbientSoundIntervalDefinition,void> : DefinitionInstance<EntityContext &,AmbientSoundIntervalDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AmbientSoundIntervalDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AmbientSoundIntervalDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AmbientSoundIntervalDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AmbientSoundIntervalDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AmbientSoundIntervalDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AmbientSoundIntervalDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<CanClimbDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<CanClimbDefinition,void> : DefinitionInstance<EntityContext &,CanClimbDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<CanClimbDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<CanClimbDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,CanClimbDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,CanClimbDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,CanClimbDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,CanClimbDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<CanFlyDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<CanFlyDefinition,void> : DefinitionInstance<EntityContext &,CanFlyDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<CanFlyDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<CanFlyDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,CanFlyDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,CanFlyDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,CanFlyDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,CanFlyDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<CanPowerJumpDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<CanPowerJumpDefinition,void> : DefinitionInstance<EntityContext &,CanPowerJumpDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<CanPowerJumpDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<CanPowerJumpDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,CanPowerJumpDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,CanPowerJumpDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,CanPowerJumpDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,CanPowerJumpDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<CollisionBoxDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<CollisionBoxDefinition,void> : DefinitionInstance<EntityContext &,CollisionBoxDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<CollisionBoxDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<CollisionBoxDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,CollisionBoxDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,CollisionBoxDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,CollisionBoxDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,CollisionBoxDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ColorDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ColorDefinition,void> : DefinitionInstance<EntityContext &,ColorDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ColorDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ColorDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ColorDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ColorDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ColorDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ColorDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<Color2Definition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<Color2Definition,void> : DefinitionInstance<EntityContext &,Color2Definition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<Color2Definition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<Color2Definition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,Color2Definition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,Color2Definition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,Color2Definition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,Color2Definition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<DefaultLookAngleDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<DefaultLookAngleDefinition,void> : DefinitionInstance<EntityContext &,DefaultLookAngleDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DefaultLookAngleDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<DefaultLookAngleDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,DefaultLookAngleDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,DefaultLookAngleDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,DefaultLookAngleDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,DefaultLookAngleDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<DyeableDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<DyeableDefinition,void> : DefinitionInstance<EntityContext &,DyeableDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DyeableDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<DyeableDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,DyeableDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,DyeableDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,DyeableDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,DyeableDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<EquipmentTableDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<EquipmentTableDefinition,void> : DefinitionInstance<EntityContext &,EquipmentTableDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EquipmentTableDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<EquipmentTableDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,EquipmentTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,EquipmentTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,EquipmentTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,EquipmentTableDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FamilyTypeDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FamilyTypeDefinition,void> : DefinitionInstance<EntityContext &,FamilyTypeDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FamilyTypeDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FamilyTypeDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FamilyTypeDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FamilyTypeDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FamilyTypeDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FamilyTypeDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FireImmuneDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FireImmuneDefinition,void> : DefinitionInstance<EntityContext &,FireImmuneDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FireImmuneDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FireImmuneDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FireImmuneDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FireImmuneDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FireImmuneDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FireImmuneDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FloatsInLiquidDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FloatsInLiquidDefinition,void> : DefinitionInstance<EntityContext &,FloatsInLiquidDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FloatsInLiquidDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FloatsInLiquidDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FloatsInLiquidDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FloatsInLiquidDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FloatsInLiquidDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FloatsInLiquidDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FlyingSpeedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FlyingSpeedDefinition,void> : DefinitionInstance<EntityContext &,FlyingSpeedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FlyingSpeedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FlyingSpeedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FlyingSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FlyingSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FlyingSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FlyingSpeedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FrictionModifierDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FrictionModifierDefinition,void> : DefinitionInstance<EntityContext &,FrictionModifierDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FrictionModifierDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FrictionModifierDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FrictionModifierDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FrictionModifierDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FrictionModifierDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FrictionModifierDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<GroundOffsetDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<GroundOffsetDefinition,void> : DefinitionInstance<EntityContext &,GroundOffsetDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GroundOffsetDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<GroundOffsetDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,GroundOffsetDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,GroundOffsetDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,GroundOffsetDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,GroundOffsetDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsBabyDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsBabyDefinition,void> : DefinitionInstance<EntityContext &,IsBabyDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsBabyDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsBabyDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsBabyDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsBabyDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsBabyDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsBabyDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsChargedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsChargedDefinition,void> : DefinitionInstance<EntityContext &,IsChargedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsChargedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsChargedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsChargedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsChargedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsChargedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsChargedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsChestedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsChestedDefinition,void> : DefinitionInstance<EntityContext &,IsChestedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsChestedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsChestedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsChestedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsChestedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsChestedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsChestedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsHiddenWhenInvisibleDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsHiddenWhenInvisibleDefinition,void> : DefinitionInstance<EntityContext &,IsHiddenWhenInvisibleDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsHiddenWhenInvisibleDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsHiddenWhenInvisibleDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsHiddenWhenInvisibleDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsHiddenWhenInvisibleDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsHiddenWhenInvisibleDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsHiddenWhenInvisibleDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsIgnitedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsIgnitedDefinition,void> : DefinitionInstance<EntityContext &,IsIgnitedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsIgnitedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsIgnitedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsIgnitedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsIgnitedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsIgnitedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsIgnitedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsIllagerCaptainDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsIllagerCaptainDefinition,void> : DefinitionInstance<EntityContext &,IsIllagerCaptainDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsIllagerCaptainDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsIllagerCaptainDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsIllagerCaptainDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsIllagerCaptainDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsIllagerCaptainDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsIllagerCaptainDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsSaddledDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsSaddledDefinition,void> : DefinitionInstance<EntityContext &,IsSaddledDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsSaddledDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsSaddledDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsSaddledDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsSaddledDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsSaddledDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsSaddledDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsShakingDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsShakingDefinition,void> : DefinitionInstance<EntityContext &,IsShakingDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsShakingDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsShakingDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsShakingDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsShakingDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsShakingDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsShakingDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsShearedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsShearedDefinition,void> : DefinitionInstance<EntityContext &,IsShearedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsShearedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsShearedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsShearedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsShearedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsShearedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsShearedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsStackableDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsStackableDefinition,void> : DefinitionInstance<EntityContext &,IsStackableDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsStackableDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsStackableDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsStackableDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsStackableDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsStackableDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsStackableDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsStunnedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsStunnedDefinition,void> : DefinitionInstance<EntityContext &,IsStunnedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsStunnedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsStunnedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsStunnedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsStunnedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsStunnedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsStunnedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<IsTamedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<IsTamedDefinition,void> : DefinitionInstance<EntityContext &,IsTamedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<IsTamedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<IsTamedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,IsTamedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,IsTamedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,IsTamedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,IsTamedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ItemControlDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ItemControlDefinition,void> : DefinitionInstance<EntityContext &,ItemControlDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ItemControlDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ItemControlDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ItemControlDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ItemControlDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ItemControlDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ItemControlDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<LootTableDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<LootTableDefinition,void> : DefinitionInstance<EntityContext &,LootTableDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LootTableDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<LootTableDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,LootTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,LootTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,LootTableDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,LootTableDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<MarkVariantDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<MarkVariantDefinition,void> : DefinitionInstance<EntityContext &,MarkVariantDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<MarkVariantDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<MarkVariantDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,MarkVariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,MarkVariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,MarkVariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,MarkVariantDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<PushThroughDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<PushThroughDefinition,void> : DefinitionInstance<EntityContext &,PushThroughDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<PushThroughDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<PushThroughDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,PushThroughDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,PushThroughDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,PushThroughDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,PushThroughDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ScaleDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ScaleDefinition,void> : DefinitionInstance<EntityContext &,ScaleDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ScaleDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ScaleDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ScaleDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ScaleDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ScaleDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ScaleDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<SkinIDDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<SkinIDDefinition,void> : DefinitionInstance<EntityContext &,SkinIDDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SkinIDDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<SkinIDDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,SkinIDDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,SkinIDDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,SkinIDDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,SkinIDDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<SoundVolumeDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<SoundVolumeDefinition,void> : DefinitionInstance<EntityContext &,SoundVolumeDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SoundVolumeDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<SoundVolumeDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,SoundVolumeDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,SoundVolumeDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,SoundVolumeDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,SoundVolumeDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<VariantDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<VariantDefinition,void> : DefinitionInstance<EntityContext &,VariantDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<VariantDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<VariantDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,VariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,VariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,VariantDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,VariantDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<WalkAnimationSpeedDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<WalkAnimationSpeedDefinition,void> : DefinitionInstance<EntityContext &,WalkAnimationSpeedDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<WalkAnimationSpeedDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<WalkAnimationSpeedDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,WalkAnimationSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,WalkAnimationSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,WalkAnimationSpeedDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,WalkAnimationSpeedDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<WantsJockeyDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<WantsJockeyDefinition,void> : DefinitionInstance<EntityContext &,WantsJockeyDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<WantsJockeyDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<WantsJockeyDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,WantsJockeyDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,WantsJockeyDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,WantsJockeyDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,WantsJockeyDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<WASDControlledDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<WASDControlledDefinition,void> : DefinitionInstance<EntityContext &,WASDControlledDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<WASDControlledDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<WASDControlledDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,WASDControlledDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,WASDControlledDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,WASDControlledDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,WASDControlledDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnDeathDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnDeathDefinition,void> : DefinitionInstance<EntityContext &,OnDeathDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnDeathDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnDeathDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnDeathDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnDeathDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnDeathDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnDeathDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnFriendlyAngerDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnFriendlyAngerDefinition,void> : DefinitionInstance<EntityContext &,OnFriendlyAngerDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnFriendlyAngerDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnFriendlyAngerDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnFriendlyAngerDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnFriendlyAngerDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnFriendlyAngerDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnFriendlyAngerDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnHurtDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnHurtDefinition,void> : DefinitionInstance<EntityContext &,OnHurtDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnHurtDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnHurtDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnHurtDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnHurtDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnHurtDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnHurtDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnHurtByPlayerDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnHurtByPlayerDefinition,void> : DefinitionInstance<EntityContext &,OnHurtByPlayerDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnHurtByPlayerDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnHurtByPlayerDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnHurtByPlayerDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnHurtByPlayerDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnHurtByPlayerDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnHurtByPlayerDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnIgniteDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnIgniteDefinition,void> : DefinitionInstance<EntityContext &,OnIgniteDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnIgniteDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnIgniteDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnIgniteDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnIgniteDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnIgniteDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnIgniteDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnStartLandingDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnStartLandingDefinition,void> : DefinitionInstance<EntityContext &,OnStartLandingDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnStartLandingDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnStartLandingDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnStartLandingDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnStartLandingDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnStartLandingDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnStartLandingDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnStartTakeoffDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnStartTakeoffDefinition,void> : DefinitionInstance<EntityContext &,OnStartTakeoffDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnStartTakeoffDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnStartTakeoffDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnStartTakeoffDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnStartTakeoffDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnStartTakeoffDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnStartTakeoffDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnTargetAcquiredDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnTargetAcquiredDefinition,void> : DefinitionInstance<EntityContext &,OnTargetAcquiredDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnTargetAcquiredDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnTargetAcquiredDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnTargetAcquiredDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnTargetAcquiredDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnTargetAcquiredDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnTargetAcquiredDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnTargetEscapeDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnTargetEscapeDefinition,void> : DefinitionInstance<EntityContext &,OnTargetEscapeDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnTargetEscapeDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnTargetEscapeDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnTargetEscapeDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnTargetEscapeDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnTargetEscapeDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnTargetEscapeDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OnWakeWithOwnerDefinition,void>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OnWakeWithOwnerDefinition,void> : DefinitionInstance<EntityContext &,OnWakeWithOwnerDefinition,void>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OnWakeWithOwnerDefinition,void>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OnWakeWithOwnerDefinition,void>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OnWakeWithOwnerDefinition,void> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OnWakeWithOwnerDefinition,void> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OnWakeWithOwnerDefinition,void> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OnWakeWithOwnerDefinition,void> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AddRiderDefinition,AddRiderComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AddRiderDefinition,AddRiderComponent> : DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AddRiderDefinition,AddRiderComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AddRiderDefinition,AddRiderComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AdmireItemDefinition,AdmireItemComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AdmireItemDefinition,AdmireItemComponent> : DefinitionInstance<EntityContext &,AdmireItemDefinition,AdmireItemComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AdmireItemDefinition,AdmireItemComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AdmireItemDefinition,AdmireItemComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AdmireItemDefinition,AdmireItemComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AdmireItemDefinition,AdmireItemComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AdmireItemDefinition,AdmireItemComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AdmireItemDefinition,AdmireItemComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AgeableDefinition,AgeableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AgeableDefinition,AgeableComponent> : DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AgeableDefinition,AgeableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AgeableDefinition,AgeableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AngryDefinition,AngryComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AngryDefinition,AngryComponent> : DefinitionInstance<EntityContext &,AngryDefinition,AngryComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AngryDefinition,AngryComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AngryDefinition,AngryComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AngryDefinition,AngryComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AngryDefinition,AngryComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AngryDefinition,AngryComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AngryDefinition,AngryComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent> : DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent> : DefinitionInstance<EntityContext &,AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,AttackCooldownComponent::AttackCooldownDefinition,AttackCooldownComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BarterDefinition,BarterComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BarterDefinition,BarterComponent> : DefinitionInstance<EntityContext &,BarterDefinition,BarterComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BarterDefinition,BarterComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BarterDefinition,BarterComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BarterDefinition,BarterComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BarterDefinition,BarterComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BarterDefinition,BarterComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BarterDefinition,BarterComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent> : DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BoostableDefinition,BoostableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BoostableDefinition,BoostableComponent> : DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BoostableDefinition,BoostableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BoostableDefinition,BoostableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BossDefinition,BossComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BossDefinition,BossComponent> : DefinitionInstance<EntityContext &,BossDefinition,BossComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BossDefinition,BossComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BossDefinition,BossComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BossDefinition,BossComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BossDefinition,BossComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BossDefinition,BossComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BossDefinition,BossComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BreathableDefinition,BreathableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BreathableDefinition,BreathableComponent> : DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BreathableDefinition,BreathableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BreathableDefinition,BreathableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BreedableDefinition,BreedableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BreedableDefinition,BreedableComponent> : DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BreedableDefinition,BreedableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BreedableDefinition,BreedableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BribeableDefinition,BribeableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BribeableDefinition,BribeableComponent> : DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BribeableDefinition,BribeableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BribeableDefinition,BribeableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > : DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > *this, EntityContext *);
};

```

### `EntityComponentDefinition<BuoyancyDefinition,BuoyancyComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BuoyancyDefinition,BuoyancyComponent> : DefinitionInstance<EntityContext &,BuoyancyDefinition,BuoyancyComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BuoyancyDefinition,BuoyancyComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BuoyancyDefinition,BuoyancyComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BuoyancyDefinition,BuoyancyComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BuoyancyDefinition,BuoyancyComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BuoyancyDefinition,BuoyancyComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BuoyancyDefinition,BuoyancyComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<CelebrateHuntDefinition,CelebrateHuntComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<CelebrateHuntDefinition,CelebrateHuntComponent> : DefinitionInstance<EntityContext &,CelebrateHuntDefinition,CelebrateHuntComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<CelebrateHuntDefinition,CelebrateHuntComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<CelebrateHuntDefinition,CelebrateHuntComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,CelebrateHuntDefinition,CelebrateHuntComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,CelebrateHuntDefinition,CelebrateHuntComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,CelebrateHuntDefinition,CelebrateHuntComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,CelebrateHuntDefinition,CelebrateHuntComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent> : DefinitionInstance<EntityContext &,ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ConditionalBandwidthOptimizationDefinition,ConditionalBandwidthOptimizationComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent> : DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent> : DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<DespawnDefinition,DespawnComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<DespawnDefinition,DespawnComponent> : DefinitionInstance<EntityContext &,DespawnDefinition,DespawnComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DespawnDefinition,DespawnComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<DespawnDefinition,DespawnComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,DespawnDefinition,DespawnComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,DespawnDefinition,DespawnComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,DespawnDefinition,DespawnComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,DespawnDefinition,DespawnComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent> : DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > : DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > *this, EntityContext *);
};

```

### `EntityComponentDefinition<EquipItemComponent::Definition,EquipItemComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<EquipItemComponent::Definition,EquipItemComponent> : DefinitionInstance<EntityContext &,EquipItemComponent::Definition,EquipItemComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EquipItemComponent::Definition,EquipItemComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<EquipItemComponent::Definition,EquipItemComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,EquipItemComponent::Definition,EquipItemComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,EquipItemComponent::Definition,EquipItemComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,EquipItemComponent::Definition,EquipItemComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,EquipItemComponent::Definition,EquipItemComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<EquippableDefinition,EquippableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<EquippableDefinition,EquippableComponent> : DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EquippableDefinition,EquippableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<EquippableDefinition,EquippableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent> : DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ExplodeDefinition,ExplodeComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ExplodeDefinition,ExplodeComponent> : DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ExplodeDefinition,ExplodeComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ExplodeDefinition,ExplodeComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<FlockingDefinition,FlockingComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<FlockingDefinition,FlockingComponent> : DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FlockingDefinition,FlockingComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<FlockingDefinition,FlockingComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<GeneticsDefinition,GeneticsComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<GeneticsDefinition,GeneticsComponent> : DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GeneticsDefinition,GeneticsComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<GeneticsDefinition,GeneticsComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<GiveableDefinition,GiveableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<GiveableDefinition,GiveableComponent> : DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GiveableDefinition,GiveableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<GiveableDefinition,GiveableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<GroupSizeDefinition,GroupSizeComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<GroupSizeDefinition,GroupSizeComponent> : DefinitionInstance<EntityContext &,GroupSizeDefinition,GroupSizeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GroupSizeDefinition,GroupSizeComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<GroupSizeDefinition,GroupSizeComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,GroupSizeDefinition,GroupSizeComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,GroupSizeDefinition,GroupSizeComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,GroupSizeDefinition,GroupSizeComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,GroupSizeDefinition,GroupSizeComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent> : DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<HealableDefinition,HealableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<HealableDefinition,HealableComponent> : DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HealableDefinition,HealableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<HealableDefinition,HealableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<HitboxDefinition,HitboxComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<HitboxDefinition,HitboxComponent> : DefinitionInstance<EntityContext &,HitboxDefinition,HitboxComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HitboxDefinition,HitboxComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<HitboxDefinition,HitboxComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,HitboxDefinition,HitboxComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,HitboxDefinition,HitboxComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,HitboxDefinition,HitboxComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,HitboxDefinition,HitboxComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<HomeDefinition,HomeComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<HomeDefinition,HomeComponent> : DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HomeDefinition,HomeComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<HomeDefinition,HomeComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<HopperDefinition,HopperComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<HopperDefinition,HopperComponent> : DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HopperDefinition,HopperComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<HopperDefinition,HopperComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent> : DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<InsideBlockNotifierDefinition,InsideBlockNotifierComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<InsideBlockNotifierDefinition,InsideBlockNotifierComponent> : DefinitionInstance<EntityContext &,InsideBlockNotifierDefinition,InsideBlockNotifierComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InsideBlockNotifierDefinition,InsideBlockNotifierComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<InsideBlockNotifierDefinition,InsideBlockNotifierComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,InsideBlockNotifierDefinition,InsideBlockNotifierComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,InsideBlockNotifierDefinition,InsideBlockNotifierComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,InsideBlockNotifierDefinition,InsideBlockNotifierComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,InsideBlockNotifierDefinition,InsideBlockNotifierComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<InsomniaDefinition,InsomniaComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<InsomniaDefinition,InsomniaComponent> : DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InsomniaDefinition,InsomniaComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<InsomniaDefinition,InsomniaComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<InstantDespawnDefinition,InstantDespawnComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<InstantDespawnDefinition,InstantDespawnComponent> : DefinitionInstance<EntityContext &,InstantDespawnDefinition,InstantDespawnComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InstantDespawnDefinition,InstantDespawnComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<InstantDespawnDefinition,InstantDespawnComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,InstantDespawnDefinition,InstantDespawnComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,InstantDespawnDefinition,InstantDespawnComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,InstantDespawnDefinition,InstantDespawnComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,InstantDespawnDefinition,InstantDespawnComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<InteractDefinition,InteractComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<InteractDefinition,InteractComponent> : DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InteractDefinition,InteractComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<InteractDefinition,InteractComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<LeashableDefinition,LeashableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<LeashableDefinition,LeashableComponent> : DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LeashableDefinition,LeashableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<LeashableDefinition,LeashableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent> : DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<LookAtDefinition,LookAtComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<LookAtDefinition,LookAtComponent> : DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LookAtDefinition,LookAtComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<LookAtDefinition,LookAtComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<MobEffectDefinition,MobEffectComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<MobEffectDefinition,MobEffectComponent> : DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<MobEffectDefinition,MobEffectComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<MobEffectDefinition,MobEffectComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<MountTameableDefinition,MountTamingComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<MountTameableDefinition,MountTamingComponent> : DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<MountTameableDefinition,MountTamingComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<MountTameableDefinition,MountTamingComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<NameableDefinition,NameableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<NameableDefinition,NameableComponent> : DefinitionInstance<EntityContext &,NameableDefinition,NameableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<NameableDefinition,NameableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<NameableDefinition,NameableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,NameableDefinition,NameableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,NameableDefinition,NameableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,NameableDefinition,NameableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,NameableDefinition,NameableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<OutOfControlDefinition,OutOfControlComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<OutOfControlDefinition,OutOfControlComponent> : DefinitionInstance<EntityContext &,OutOfControlDefinition,OutOfControlComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<OutOfControlDefinition,OutOfControlComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<OutOfControlDefinition,OutOfControlComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,OutOfControlDefinition,OutOfControlComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,OutOfControlDefinition,OutOfControlComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,OutOfControlDefinition,OutOfControlComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,OutOfControlDefinition,OutOfControlComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<PeekDefinition,PeekComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<PeekDefinition,PeekComponent> : DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<PeekDefinition,PeekComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<PeekDefinition,PeekComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<PhysicsDefinition,PhysicsComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<PhysicsDefinition,PhysicsComponent> : DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<PhysicsDefinition,PhysicsComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<PhysicsDefinition,PhysicsComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<RailActivatorDefinition,RailActivatorComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<RailActivatorDefinition,RailActivatorComponent> : DefinitionInstance<EntityContext &,RailActivatorDefinition,RailActivatorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<RailActivatorDefinition,RailActivatorComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<RailActivatorDefinition,RailActivatorComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,RailActivatorDefinition,RailActivatorComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,RailActivatorDefinition,RailActivatorComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,RailActivatorDefinition,RailActivatorComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,RailActivatorDefinition,RailActivatorComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<RailMovementDefinition,RailMovementComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<RailMovementDefinition,RailMovementComponent> : DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<RailMovementDefinition,RailMovementComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<RailMovementDefinition,RailMovementComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<RideableDefinition,RideableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<RideableDefinition,RideableComponent> : DefinitionInstance<EntityContext &,RideableDefinition,RideableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<RideableDefinition,RideableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<RideableDefinition,RideableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,RideableDefinition,RideableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,RideableDefinition,RideableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,RideableDefinition,RideableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,RideableDefinition,RideableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent> : DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent> : DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<SchedulerDefinition,SchedulerComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<SchedulerDefinition,SchedulerComponent> : DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SchedulerDefinition,SchedulerComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<SchedulerDefinition,SchedulerComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ShareableDefinition,ShareableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ShareableDefinition,ShareableComponent> : DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ShareableDefinition,ShareableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ShareableDefinition,ShareableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<ShooterDefinition,ShooterComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<ShooterDefinition,ShooterComponent> : DefinitionInstance<EntityContext &,ShooterDefinition,ShooterComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ShooterDefinition,ShooterComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<ShooterDefinition,ShooterComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,ShooterDefinition,ShooterComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,ShooterDefinition,ShooterComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,ShooterDefinition,ShooterComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,ShooterDefinition,ShooterComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<SittableDefinition,SitComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<SittableDefinition,SitComponent> : DefinitionInstance<EntityContext &,SittableDefinition,SitComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SittableDefinition,SitComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<SittableDefinition,SitComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,SittableDefinition,SitComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,SittableDefinition,SitComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,SittableDefinition,SitComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,SittableDefinition,SitComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<TameableDefinition,TameableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<TameableDefinition,TameableComponent> : DefinitionInstance<EntityContext &,TameableDefinition,TameableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<TameableDefinition,TameableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<TameableDefinition,TameableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,TameableDefinition,TameableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,TameableDefinition,TameableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,TameableDefinition,TameableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,TameableDefinition,TameableComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<TimerDefinition,TimerComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<TimerDefinition,TimerComponent> : DefinitionInstance<EntityContext &,TimerDefinition,TimerComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<TimerDefinition,TimerComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<TimerDefinition,TimerComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,TimerDefinition,TimerComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,TimerDefinition,TimerComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,TimerDefinition,TimerComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,TimerDefinition,TimerComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<SpawnActorDefinition,SpawnActorComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<SpawnActorDefinition,SpawnActorComponent> : DefinitionInstance<EntityContext &,SpawnActorDefinition,SpawnActorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SpawnActorDefinition,SpawnActorComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<SpawnActorDefinition,SpawnActorComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,SpawnActorDefinition,SpawnActorComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,SpawnActorDefinition,SpawnActorComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,SpawnActorDefinition,SpawnActorComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,SpawnActorDefinition,SpawnActorComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<TrustingDefinition,TrustingComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<TrustingDefinition,TrustingComponent> : DefinitionInstance<EntityContext &,TrustingDefinition,TrustingComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<TrustingDefinition,TrustingComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<TrustingDefinition,TrustingComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,TrustingDefinition,TrustingComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,TrustingDefinition,TrustingComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,TrustingDefinition,TrustingComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,TrustingDefinition,TrustingComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BalloonDefinition,BalloonComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BalloonDefinition,BalloonComponent> : DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BalloonDefinition,BalloonComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BalloonDefinition,BalloonComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent> *this, EntityContext *);
};

```

### `EntityComponentDefinition<BalloonableDefinition,BalloonableComponent>`
```
struct __cppobj __declspec(align(8)) EntityComponentDefinition<BalloonableDefinition,BalloonableComponent> : DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BalloonableDefinition,BalloonableComponent>_vtbl`
```
struct /*VFT*/ EntityComponentDefinition<BalloonableDefinition,BalloonableComponent>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent> *this, EntityContext *);
};

```

### `EntityGoalFactory::registerGoalDefinition::__l2::<lambda_040fd6af88f17fc8908cc6b5f829e7bc>`
```
struct __cppobj EntityGoalFactory::registerGoalDefinition::__l2::<lambda_040fd6af88f17fc8908cc6b5f829e7bc>
{
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_c33269de5b15d1d03943492327905da0>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_c33269de5b15d1d03943492327905da0>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e47f38c8d5eab3067dcc10bee5f4de8f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e47f38c8d5eab3067dcc10bee5f4de8f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_6e713f2382806573063c7dfd32c38ce4>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_6e713f2382806573063c7dfd32c38ce4>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_3985b71719394fd3ee1439d4be34b6b3>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_3985b71719394fd3ee1439d4be34b6b3>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5e8004d87df767ded1c50c7f3f48d6c8>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5e8004d87df767ded1c50c7f3f48d6c8>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ec050a7dfec548c4f687767482f55886>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ec050a7dfec548c4f687767482f55886>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_93e1fbb1901fd8acd616ccdded5cedb7>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_93e1fbb1901fd8acd616ccdded5cedb7>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ddbe8697c0ca28b7be5f9fdd5dff5f09>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ddbe8697c0ca28b7be5f9fdd5dff5f09>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_bbb5fe18e8415a111dcf664b2bc9e8d7>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_bbb5fe18e8415a111dcf664b2bc9e8d7>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e8622a4fb3155f5f9f564c467f4ec4a3>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e8622a4fb3155f5f9f564c467f4ec4a3>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_0bdc80938c3348814870215e8640130f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_0bdc80938c3348814870215e8640130f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_25738d7581c321ee7f60c537e4152ad7>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_25738d7581c321ee7f60c537e4152ad7>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_3e32de879817bb21834fe906d4ca8c23>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_3e32de879817bb21834fe906d4ca8c23>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_eecfb98e84bf0b7537a0f0fb940eb602>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_eecfb98e84bf0b7537a0f0fb940eb602>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_04df0c1d1e5d5d80b28c0b0bb036bac5>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_04df0c1d1e5d5d80b28c0b0bb036bac5>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b9a25e537494aa3fd0e3d32acc90954c>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b9a25e537494aa3fd0e3d32acc90954c>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_2bce585f018a1bb8966befcb56e2535d>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_2bce585f018a1bb8966befcb56e2535d>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_d64aa2ae0c9195dbdb9b6db20e83e61d>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_d64aa2ae0c9195dbdb9b6db20e83e61d>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_62d5a29da45f695b28116f8666543feb>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_62d5a29da45f695b28116f8666543feb>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_cfe1d288576b398f7ae0896f017db7ab>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_cfe1d288576b398f7ae0896f017db7ab>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_adfdf144d610e08afd38f3f92d8953f8>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_adfdf144d610e08afd38f3f92d8953f8>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5961e9b6f70709a8ce5efa7bcfef0683>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5961e9b6f70709a8ce5efa7bcfef0683>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_94568a0843cadd69861a1c1ab66aa24a>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_94568a0843cadd69861a1c1ab66aa24a>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1f616d86d554da30c680c436baa65df6>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1f616d86d554da30c680c436baa65df6>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1ff28e73c329a05b0d80c14a4684eb21>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1ff28e73c329a05b0d80c14a4684eb21>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e65069f23a0bd2c2d44077020a30c0f9>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e65069f23a0bd2c2d44077020a30c0f9>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_c43c32d0c00ce7414bcb78bfc5f36278>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_c43c32d0c00ce7414bcb78bfc5f36278>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_01a3e2be46572869d5f58c1b7c9f048b>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_01a3e2be46572869d5f58c1b7c9f048b>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_a0604df61c1211fb24ffcedba9ae3e92>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_a0604df61c1211fb24ffcedba9ae3e92>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7f0850029e05a361d53430fcd1ab2611>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7f0850029e05a361d53430fcd1ab2611>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_fbf57e47299ca0769d550830aaec2fb7>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_fbf57e47299ca0769d550830aaec2fb7>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_84b602bf12081d8d4b565774b019b410>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_84b602bf12081d8d4b565774b019b410>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b8387aef35125e696ada67fc502fdaba>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b8387aef35125e696ada67fc502fdaba>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_87925c7ef15caa751fdeaa1282764216>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_87925c7ef15caa751fdeaa1282764216>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_279c36ea0f2eaa3a8ef848c7d09fcf31>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_279c36ea0f2eaa3a8ef848c7d09fcf31>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_534c98e989e394c7e976539c9968c260>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_534c98e989e394c7e976539c9968c260>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_4bed2e71dc237f95ba0771a7bc75827b>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_4bed2e71dc237f95ba0771a7bc75827b>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_cdc32fe163e6ef9510ea46a1fad1cfb6>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_cdc32fe163e6ef9510ea46a1fad1cfb6>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_22e6971a9dcb69e8786905f2e3a205e3>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_22e6971a9dcb69e8786905f2e3a205e3>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_64d4055f173d73b65a74b60f950156d8>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_64d4055f173d73b65a74b60f950156d8>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_82b3e5747136edae225d7bc3f2d63377>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_82b3e5747136edae225d7bc3f2d63377>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_0d99517676fadee509220fb162f2c27d>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_0d99517676fadee509220fb162f2c27d>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b19389f54648c9aadff954e1ad75fd0a>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b19389f54648c9aadff954e1ad75fd0a>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_15020e5b1e34d396830f01ee0d43d4d9>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_15020e5b1e34d396830f01ee0d43d4d9>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_874b7812cc10dabe0692990143551619>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_874b7812cc10dabe0692990143551619>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_fd90e2c5e867a5609bd56657e3ba2f77>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_fd90e2c5e867a5609bd56657e3ba2f77>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b79f1c1928883bd12830f64e757d48bd>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b79f1c1928883bd12830f64e757d48bd>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_9eda1d422ba5b14680d3512dc9805b2f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_9eda1d422ba5b14680d3512dc9805b2f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_86d382c5f46fdd70a015a8f41cb8ac3b>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_86d382c5f46fdd70a015a8f41cb8ac3b>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_454c68097250e67d1e6c264cbef8d9bb>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_454c68097250e67d1e6c264cbef8d9bb>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_38ccfc4d3dfb55a3a047cb0e5ead653d>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_38ccfc4d3dfb55a3a047cb0e5ead653d>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_06ce88cbbc9607a8ecb951ed5a349b35>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_06ce88cbbc9607a8ecb951ed5a349b35>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1078a46d65c510dde817d5b6f9e04603>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_1078a46d65c510dde817d5b6f9e04603>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_562bac4d5ac9c246a8010c7ebd49bbb6>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_562bac4d5ac9c246a8010c7ebd49bbb6>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_300d5b67cb0a0e06ff27ed1f2809b611>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_300d5b67cb0a0e06ff27ed1f2809b611>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b8e60a9d889b32be77a45eb2bf895830>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b8e60a9d889b32be77a45eb2bf895830>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5f90f9ba609f19d10a479493be9b7402>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5f90f9ba609f19d10a479493be9b7402>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_339ab2df7a9fa2548265693c68cbf69b>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_339ab2df7a9fa2548265693c68cbf69b>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_54c954d8fe4cbeb087a1704ca8a7771f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_54c954d8fe4cbeb087a1704ca8a7771f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_4b2ca7606ac01d6e36a439d76b12a485>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_4b2ca7606ac01d6e36a439d76b12a485>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5f2de3d5dd36552deec8ae27d0152908>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_5f2de3d5dd36552deec8ae27d0152908>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7203bbbfca949d4ab26734c8c80fbaa4>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7203bbbfca949d4ab26734c8c80fbaa4>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b46ae13cfe3dec4d71d3dada9ffdf8b3>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_b46ae13cfe3dec4d71d3dada9ffdf8b3>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7aa9e0eb99eb43880f430354978a5bac>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_7aa9e0eb99eb43880f430354978a5bac>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e7af7148f7d7beee017e3bae47d6313f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_e7af7148f7d7beee017e3bae47d6313f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_350b5898868371dc9fda3492c89590f9>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_350b5898868371dc9fda3492c89590f9>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ed40b05713ecff419228349e8b545626>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ed40b05713ecff419228349e8b545626>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_d42449392fdc5725722bd04494c42da7>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_d42449392fdc5725722bd04494c42da7>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_51b053e3dbbebabe798d194a4b89a8bf>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_51b053e3dbbebabe798d194a4b89a8bf>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_430228ee6e4c580d35d629c10d57f080>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_430228ee6e4c580d35d629c10d57f080>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ee4924eb449c4a498335dc5688759a80>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_ee4924eb449c4a498335dc5688759a80>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_2321444409893dcb1df1902eeb86fdd0>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_2321444409893dcb1df1902eeb86fdd0>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_41905dd920d193cfa7f2679b5d8e560a>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_41905dd920d193cfa7f2679b5d8e560a>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_869dedbdac133eea6cbdb0afe68e505f>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_869dedbdac133eea6cbdb0afe68e505f>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_31d8deb72c6237b206007692f7002625>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_31d8deb72c6237b206007692f7002625>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_6da71a3c6d675b28575d994825811241>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_6da71a3c6d675b28575d994825811241>
{
  EntityComponentFactory *const __this;
};

```

### `EntityComponentFactory::registerComponentDefinition::__l2::<lambda_03fa1d9377889aef8463dd8229c474f9>`
```
struct __cppobj EntityComponentFactory::registerComponentDefinition::__l2::<lambda_03fa1d9377889aef8463dd8229c474f9>
{
  EntityComponentFactory *const __this;
};

```

