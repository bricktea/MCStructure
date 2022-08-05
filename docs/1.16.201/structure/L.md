# L
### `LegacyWorldInfo`
Offset | Type | Name
-|-|-|-
0 | (568) `LocalWorldInfo` | baseclass_0
568 | (32) `std::string` | mIdentifier
600 | (1) `bool` | mIsBetaRetailSave


### `LocalWorldInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `WorldInfo` | baseclass_0
8 | (32) `std::string` | mScreenshotTexture
40 | (8) `unsigned __int64` | mFileSize
48 | (32) `std::string` | mFilesizeAsString
80 | (32) `std::string` | mWorldName
112 | (32) `std::string` | mDate
144 | (32) `std::string` | mGameType
176 | (1) `bool` | mLocalStorage
177 | (1) `bool` | mCloudStorage
178 | (1) `bool` | mIsDirty
179 | (1) `bool` | mIsBetaRetailSave
184 | (384) `LevelSummary` | mLevelSummary


### `LevelSummary`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mId
32 | (32) `std::string` | mName
64 | (8) `__int64` | mLastPlayed
72 | (4) `GameType` | mGameType
76 | (4) `Difficulty` | mGameDifficulty
80 | (4) `int` | mSeed
84 | (4) `int` | mNetworkProtocolVersion
88 | (8) `unsigned __int64` | mSizeOnDisk
96 | (1) `bool` | mConfirmedPlatformLockedContent
97 | (1) `bool` | mLANBroadcastIntent
100 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
104 | (1) `bool` | mCommandsEnabled
108 | (4) `EducationEditionOfferValue` | mEducationEditionOffer
112 | (56) `GameVersion` | mLastLoadedGameVersion
168 | (56) `GameVersion` | mMinCompatibleClientVersion
224 | (4) `_BYTE[4]` | mStorageVersion
232 | (32) `Core::PathBuffer<std::string >` | mWorldIconPath
264 | (32) `Core::PathBuffer<std::string >` | mWorldIconTargetPath
296 | (24) `ContentIdentity` | mPremiumTemplateContentIdentity
320 | (32) `std::string` | mEducationOid
352 | (1) `bool` | mIsSingleUseWorld
353 | (1) `bool` | mIsBetaRetailLevel
360 | (24) `ContentIdentity` | ?


### `LayoutRule::addStackPanelVisibilityTerm::__l2::<lambda_41e73def6e306693a2d0395c1cfcc6a2>`
Offset | Type | Name
-|-|-|-


### `LayoutManager::_update::__l2::<lambda_582f447c20f51f382c4eb7054a5dd98a>`
Offset | Type | Name
-|-|-|-


### `LevelBuilder::_prepareRenderChunkRenderList::__l2::<lambda_68215dddadd9af939d720f1d070375e1>`
Offset | Type | Name
-|-|-|-


### `LevelBuilder::_buildRenderChunks::__l2::<lambda_a08ac9d83425319e6a6e10392713a815>::()::__l2::<lambda_e21558297a2641a2000dbf4a718e58a4>`
Offset | Type | Name
-|-|-|-


### `Lockless::WeakAtomic<SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>::Block *>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>::Block *>` | mValue


### `ListTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (24) `std::vector<std::unique_ptr<Tag>>` | mList
32 | (1) `_BYTE[1]` | mType


### `LevelChunk::_fixupCorruptedBlockActors::__l2::<lambda_484ffdbe9c80c92eec14bddff882ab4a>`
Offset | Type | Name
-|-|-|-


### `Level::CompareLevelChunkQueuedSavingElement`
Offset | Type | Name
-|-|-|-


### `LayerFilters::BackCompatSorter`
Offset | Type | Name
-|-|-|-


### `LayerResult<enum BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char [0]>` | mResult


### `LoginStateMachine`
Offset | Type | Name
-|-|-|-
0 | (8) `LoginStateMachine_vtbl *` | __vftable
8 | (16) `std::shared_ptr<BaseStage>` | mCurrent
24 | (64) `std::function<void __cdecl(void)>` | mSuccCallback
88 | (64) `std::function<void __cdecl(enum eLoginStage,int,std::string,std::string)>` | mFailCallback
152 | (4) `eLoginStage` | mLoginStage
160 | (24) `std::vector<std::string>` | mDnsIpArray
184 | (4) `int` | mDnsTxtTTL
188 | (4) `unsigned int` | mDnsValidTime
192 | (16) `std::map<std::string,std::pair<std::vector<std::string>,unsigned int>>` | mDomainCacheMap
208 | (80) `std::mutex` | mResMutex
288 | (1) `bool` | mDirtyDNS
289 | (1) `bool` | misLoginEnable
290 | (1) `bool` | misLoginSuccess
296 | (32) `std::string` | mNickName
328 | (1) `bool` | mIsOfflineStart
329 | (1) `bool` | misOfflineStartEnable
336 | (16) `Json::Value` | mUpdatePatchInfo
352 | (1) `bool` | ?
353 | (1) `bool` | mRnInstalled
354 | (1) `bool` | mLogoHided
355 | (1) `bool` | mIsRnInited
356 | (1) `bool` | mIsCheckedPatch
357 | (1) `bool` | mNeedCheckUpdate
358 | (1) `bool` | mCheckUpdateFromOffline
360 | (32) `std::string` | mWebServerUrl
392 | (32) `std::string` | mCoreServerUrl
424 | (32) `std::string` | mWebServerGrayUrl
456 | (32) `std::string` | mTransServerUrl
488 | (32) `std::string` | mCdnServerUrl
520 | (32) `std::string` | mChatServerUrl
552 | (32) `std::string` | mAuthServerUrl
584 | (32) `std::string` | mApiGatewayUrl
616 | (32) `std::string` | mH5ResVersionUrl
648 | (32) `std::string` | mH5ResServerUrl
680 | (32) `std::string` | mTranSrvInfoJson
712 | (32) `std::string` | mChatServerJson
744 | (32) `std::string` | mSensitiveWordJson
776 | (32) `std::string` | mDebugUserName
808 | (32) `std::string` | mDebugPassword
840 | (32) `std::string` | mMomentUrl
872 | (32) `std::string` | mFirstLogin
904 | (4) `int` | mSelectServerIndex
912 | (32) `std::string` | mServerListUrl
944 | (32) `std::string` | mTestUpdateFlag
976 | (24) `std::vector<std::string>` | mServerListArray
1000 | (32) `std::string` | mServerListName
1032 | (32) `std::string` | mJf_gas_url
1064 | (32) `std::string` | mAuthenSeed
1096 | (32) `std::string` | mAuthenKey
1128 | (32) `std::string` | mAuthenValue1
1160 | (32) `std::string` | mAuthenValue2
1192 | (32) `std::string` | mAuthenValue3
1224 | (32) `std::string` | mAuthenSign
1256 | (32) `std::string` | mAuthenTimeStamp
1288 | (1) `bool` | mServerStop
1289 | (1) `bool` | mUpdateStop
1290 | (1) `bool` | mUseHttpDNS
1291 | (1) `bool` | ?
1292 | (1) `bool` | mIsPatchUpdated
1296 | (4) `int` | mPatchUpdateStatus
1304 | (8) `__int64` | mPatchStartTimeStamp
1312 | (8) `__int64` | mPatchSuccTimeStamp
1320 | (8) `__int64` | mPatchFailTimeStamp


### `Lockless::WeakAtomic<SPSCQueue<unsigned int,512>::Block *>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<SPSCQueue<unsigned int,512>::Block *>` | mValue


### `LayerResult<float>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char [0]>` | mResult


### `LayerValues::PreBiome`
Offset | Type | Name
-|-|-|-
0 | (1) `LayerValues::Terrain` | mTerrain
1 | (1) `_BYTE[1]` | mTemperature


### `LayerResult<bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char [0]>` | mResult


### `LoopingSoundState`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | position
12 | (4) `float` | pitch
16 | (4) `float` | volume


### `label`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | lb_type
8 | (8) `char *` | lb_str


### `LegacySkinSerialization`
Offset | Type | Name
-|-|-|-
0 | (112) `SkinHandle` | mSkinHandle
112 | (4) `persona::ProfileType` | mLastUsedSlot
116 | (1) `bool` | mBeingDeleted


### `labellist`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | ll_nlabels
8 | (8) `label *` | ll_label


### `lexicon_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | name
8 | (4) `int` | num_entries
16 | (8) `unsigned __int8 *` | data
24 | (4) `int` | num_bytes
32 | (8) `char **` | phone_table
40 | (8) `cst_lts_rules_struct *` | lts_rule_set
48 | (8) `int (__fastcall *)(const cst_item_struct *, const cst_val_struct *)` | syl_boundary
56 | (8) `cst_val_struct *(__fastcall *)(const lexicon_struct *, const char *, const char *, const cst_features_struct *)` | lts_function
64 | (8) `char ***` | addenda
72 | (8) `const char *const *` | phone_hufftable
80 | (8) `const char *const *` | entry_hufftable
88 | (8) `cst_utterance_struct *(__fastcall *)(cst_utterance_struct *)` | postlex
96 | (8) `cst_val_struct *` | lex_addenda


### `leveldb::Logger`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Logger_vtbl *` | __vftable


### `LocalConnectivitySystem`
Offset | Type | Name
-|-|-|-
0 | (8) `LocalConnector *` | mHostConnector


### `Localization`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mCommaSeperator
8 | (32) `const std::string` | mCode
40 | (16) `std::map<std::string,std::string>` | mStrings
56 | (16) `std::shared_ptr<std::mutex>` | m_lock


### `LegacyOptionsConverterInternal::ConversionRule`
Offset | Type | Name
-|-|-|-
0 | (4) `LegacyOption` | mSourceOption
4 | (4) `OptionID` | mTargetOption
8 | (64) `std::function<bool __cdecl(enum LegacyOption,enum OptionID,LegacyOptionsParser const &,Options &)>` | mConversionRecipe


### `LodestoneCompassComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `PositionTrackingId` | mTrackingHandle
8 | (64) `std::unordered_map<std::variant<ActorUniqueID,std::pair<BlockPos,AutomaticID<Dimension,int> > >,std::unique_ptr<LodestoneCompassComponentCalculator>,std::hash<std::variant<ActorUniqueID,std::pair<BlockPos,AutomaticID<Dimension,int> > > >,std::equal_to<std::variant<ActorUniqueID,std::pair<BlockPos,AutomaticID<Dimension,int> > > >,std::allocator<std::pair<std::variant<ActorUniqueID,std::pair<BlockPos,AutomaticID<Dimension,int> > > const ,std::unique_ptr<LodestoneCompassComponentCalculator> > > >` | mCalculators


### `LevelSoundEventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `LevelSoundEvent` | mEventId
44 | (12) `Vec3` | mPos
56 | (4) `int` | mData
64 | (32) `std::string` | mEntityIdentifier
96 | (1) `bool` | mIsBabyMob
97 | (1) `bool` | mIsGlobal


### `LevelLoader::_importLevel::__l2::<lambda_ef1a8fc506d0b5dfc78e5f6835e03656>`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelLoader *const` | __this
8 | (40) `const ImportLevelData` | levelData


### `LevelSettings`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mSeed
4 | (4) `GameType` | mGameType
8 | (4) `Difficulty` | mGameDifficulty
12 | (1) `bool` | mForceGameType
16 | (4) `GeneratorType` | mGenerator
20 | (1) `_BYTE[1]` | mNetherType
24 | (48) `SpawnSettings` | mSpawnSettings
72 | (1) `bool` | mAchievementsDisabled
76 | (4) `int` | mTime
80 | (4) `EducationEditionOfferValue` | mEducationEditionOffer
84 | (1) `bool` | mEducationFeaturesEnabled
85 | (1) `bool` | mImmutableWorld
88 | (4) `float` | mRainLevel
92 | (4) `float` | mLightningLevel
96 | (1) `bool` | mConfirmedPlatformLockedContent
97 | (1) `bool` | mMultiplayerGameIntent
98 | (1) `bool` | mLANBroadcastIntent
100 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
104 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
108 | (1) `bool` | mCommandsEnabled
109 | (1) `bool` | mTexturePacksRequired
110 | (1) `bool` | mHasLockedBehaviorPack
111 | (1) `bool` | mHasLockedResourcePack
112 | (1) `bool` | mIsFromLockedTemplate
113 | (1) `bool` | mUseMsaGamertagsOnly
114 | (1) `bool` | mOverrideSettings
115 | (1) `bool` | mBonusChestEnabled
116 | (1) `bool` | mStartWithMapEnabled
120 | (4) `int` | mServerChunkTickRange
124 | (1) `bool` | mIsFromWorldTemplate
125 | (1) `bool` | mIsWorldTemplateOptionLocked
126 | (1) `bool` | mSpawnV1Villagers
128 | (4) `int` | mLimitedWorldWidth
132 | (4) `int` | mLimitedWorldDepth
136 | (4) `int` | mTempPlayerDimensionIdToCreate
144 | (2712) `Abilities` | mDefaultAbilities
2856 | (12) `BlockPos` | mDefaultSpawn
2872 | (24) `std::vector<PackInstanceId>` | mNewWorldBehaviorPackIdentities
2896 | (24) `std::vector<PackInstanceId>` | mNewWorldResourcePackIdentities
2920 | (24) `GameRules` | mGameRules
2944 | (40) `ExperimentStorage` | mExperiments
2984 | (112) `BaseGameVersion` | mBaseGameVersion
3096 | (32) `std::string` | mEducationProductID
3128 | (32) `std::string` | mBiomeOverride
3160 | (192) `std::optional<EducationLevelSettings>` | mEducationLevelSettings
3352 | (2) `std::optional<bool>` | mOverrideForceExperimentalGameplayFlag


### `LessonInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | courseId
32 | (32) `std::string` | lessonId


### `LevelData`
Offset | Type | Name
-|-|-|-
0 | (5) `AdventureSettings` | mAdventureSettings
8 | (280) `WorldTemplateLevelData` | mWorldTemplateLevelData
288 | (24) `GameRules` | mGameRules
312 | (40) `ExperimentStorage` | mExperiments
352 | (2712) `Abilities` | mDefaultAbilities
3064 | (32) `std::string` | mLevelName
3096 | (4) `_BYTE[4]` | mStorageVersion
3104 | (56) `GameVersion` | mMinCompatibleClientVersion
3160 | (4) `int` | mNetworkVersion
3168 | (112) `SemVersion` | mInventoryVersion
3280 | (8) `Tick` | mCurrentTick
3288 | (1) `bool` | mHasSpawnPos
3292 | (12) `BlockPos` | mLimitedWorldOrigin
3304 | (4) `int` | mTime
3312 | (8) `__int64` | mLastPlayed
3320 | (4) `unsigned int` | mServerTickRange
3324 | (4) `float` | mRainLevel
3328 | (4) `int` | mRainTime
3332 | (4) `float` | mLightningLevel
3336 | (4) `int` | mLightningTime
3340 | (4) `int` | mNetherScale
3344 | (56) `GameVersion` | mLastOpenedWithVersion
3400 | (4) `Difficulty` | mGameDifficulty
3404 | (1) `bool` | mForceGameType
3405 | (1) `bool` | mSpawnMobs
3408 | (16) `Json::Value` | mFlatworldGeneratorOptions
3424 | (4) `unsigned int` | mWorldStartCount
3428 | (1) `bool` | mAchievementsDisabled
3432 | (4) `EducationEditionOfferValue` | mEducationEditionOffer
3436 | (1) `bool` | mEducationFeaturesEnabled
3437 | (1) `bool` | mIsSingleUseWorld
3438 | (1) `bool` | mConfirmedPlatformLockedContent
3439 | (1) `bool` | mMultiplayerGameIntent
3440 | (1) `bool` | mMultiplayerGame
3441 | (1) `bool` | mLANBroadcastIntent
3442 | (1) `bool` | mLANBroadcast
3444 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
3448 | (4) `Social::GamePublishSetting` | mXBLBroadcastMode
3452 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
3456 | (4) `Social::GamePublishSetting` | mPlatformBroadcastMode
3460 | (1) `bool` | mCommandsEnabled
3461 | (1) `bool` | mTexturePacksRequired
3462 | (1) `bool` | mHasLockedBehaviorPack
3463 | (1) `bool` | mHasLockedResourcePack
3464 | (1) `bool` | mIsFromLockedTemplate
3472 | (32) `std::string` | mEducationProductId
3504 | (1) `bool` | mUseMsaGamertagsOnly
3505 | (1) `bool` | mBonusChestEnabled
3506 | (1) `bool` | mBonusChestSpawned
3507 | (1) `bool` | mStartWithMapEnabled
3508 | (1) `bool` | mUselimitArea
3512 | (12) `Vec3` | mLimitAreaCenter
3524 | (4) `int` | mLimitAreaOffsetX
3528 | (4) `int` | mLimitAreaOffsetZ
3532 | (1) `bool` | mLockDifficulty
3533 | (1) `bool` | mDisableItemUse
3534 | (1) `bool` | mDisableItemUseOnBlock
3536 | (64) `std::unordered_map<int,int>` | mMapDimensionToVersion
3600 | (1) `bool` | mMapsCenteredToOrigin
3601 | (1) `bool` | mRequiresCopiedPackRemovalCheck
3602 | (1) `bool` | mSpawnV1Villagers
3603 | (1) `_BYTE[1]` | mNetherType
3608 | (48) `SpawnSettings` | mSpawnSettings
3656 | (64) `std::unordered_map<HashedString,LevelDataValue>` | mValues
3720 | (64) `std::unordered_map<HashedString,LevelDataValue>` | mOverrides
3784 | (32) `std::string` | mBiomeOverride
3816 | (24) `ContentIdentity` | ?


### `LARGE_INTEGER`
Offset | Type | Name
-|-|-|-
0 | (8) `$FAF74743FBE1C8632047CFB668F7028A` | __s0
1 | (8) `struct {unsigned int LowPart;int HighPart;}` | u
2 | (8) `__int64` | QuadPart


### `LockedStateEventData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | locked


### `LateJoinPreGameScreenController::_checkPremiumAccessAndShowUpsell::__l2::<lambda_2760d6c2b2b29a79ae8f23ce45c3a731>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<LateJoinPreGameScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | callback


### `leveldb::InternalKey`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | rep_


### `LevelRenderPreRenderUpdateParameters`
Offset | Type | Name
-|-|-|-
0 | (8) `FrustumCuller *` | leftCuller
8 | (8) `FrustumCuller *` | rightCuller
16 | (12) `glm::tvec3<float,0>` | cameraWorldPosition
28 | (12) `glm::tvec3<float,0>` | cameraTargetWorldPosition
40 | (12) `glm::tvec3<float,0>` | cameraForward
52 | (4) `const unsigned int` | viewBlockRadius
56 | (4) `const float` | currentTime
64 | (8) `BlockSource *` | region
72 | (8) `const glm::tvec3<float,0> *` | tickWorldPosition
80 | (1) `bool` | stereoRendering
84 | (4) `FakeHDRSetting` | enableFakeHDR
88 | (4) `float` | skyIntensityOverride
92 | (4) `float` | renderDistanceScalar
96 | (1) `LevelCullerType` | levelCullerType
97 | (1) `FrustumCullerType` | frustumCullerType
104 | (64) `std::function<void __cdecl(LevelRenderPreRenderUpdateParameters &)>` | preLevelBuildCallback


### `LayoutRule::addDynamicGridItemGridPositionTerm::__l2::<lambda_f55cbd476301545fb1f583c0e70c270e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<UIControl>` | weakParent
16 | (4) `ui::OrientationType` | rescalingType
20 | (1) `LayoutVariableType` | type
24 | (4) `int` | collectionIndex


### `LayoutRule::addStackPanelItemPositionTerms::__l2::<lambda_7d7bffcfcabf3e69cd7e400ef5cc8ea5>`
Offset | Type | Name
-|-|-|-
0 | (8) `UIControl *` | priorSibling


### `LayoutRule::addStackPanelVisibilityTerm::__l2::<lambda_65b4f493b8e36199de434873facedc43>`
Offset | Type | Name
-|-|-|-
0 | (8) `UIControl *` | control
8 | (1) `const LayoutVariableType` | sizeType


### `LayoutRule::addStackPanelItemRemainderSizeTerms::__l2::<lambda_db9e97e64f0225748868637354f669ba>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<float __cdecl(void)>` | calcFactorFunction


### `LecternUpdatePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `int` | mPage
44 | (4) `int` | mTotalPages
48 | (1) `bool` | mShouldDropBook
52 | (12) `NetworkBlockPosition` | mPos


### `LevelDataValue`
Offset | Type | Name
-|-|-|-
0 | (40) `std::variant<int,bool,float,std::string,enum GeneratorType,enum GameType,BlockPos,unsigned int,LevelDataValue::Tag>` | mValue


### `LevelDataValue::Tag`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<CompoundTag>` | mTag


### `LevelListCache::createBackupCopyOfWorld::__l5::<lambda_01ffea937a76700a6f61e699c9c52645>`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelListCache *const` | __this
8 | (32) `const std::string` | newLevelId


### `LibraryItem`
Offset | Type | Name
-|-|-|-
0 | (296) `LessonItem` | baseclass_0
296 | (32) `std::string` | mSubtitle
328 | (32) `std::string` | mDifficulty
360 | (24) `std::vector<std::string>` | mSearchKeywords
384 | (4) `_BYTE[4]` | mBadgeCategory
388 | (4) `_BYTE[4]` | mType
392 | (8) `std::optional<int>` | mDuration
400 | (8) `std::optional<int>` | mMinAge
408 | (8) `std::optional<int>` | mMaxAge
416 | (8) `std::optional<float>` | mFileSizeMB
424 | (64) `std::unordered_map<enum Library::OptionalProductInfo,std::string>` | mOptionalProductInfo
488 | (64) `std::unordered_map<enum Library::OptionalProductLink,std::string>` | mOptionalProductLinks
552 | (64) `std::function<void __cdecl(LibraryItem const &)>` | mDestructorCallback


### `LessonItem`
Offset | Type | Name
-|-|-|-
0 | (8) `LessonItem_vtbl *` | __vftable
8 | (16) `std::enable_shared_from_this<LessonItem>` | baseclass_8
24 | (32) `std::string` | mImageUri
56 | (8) `std::unique_ptr<LessonItem::ImageInfo>` | mImageInfo
64 | (32) `std::string` | mWorldDownloadUri
96 | (1) `bool` | mShouldRefresh
104 | (32) `std::string` | mProductId
136 | (32) `std::string` | mTitle
168 | (32) `std::string` | mDescription
200 | (32) `std::string` | mCreator
232 | (40) `std::optional<std::string >` | mWorldId
272 | (4) `_BYTE[4]` | mImportState
276 | (1) `bool` | mHasQuiz
280 | (16) `std::weak_ptr<InstructionalContentCollection>` | mCollection


### `LessonItemCache::createItem::__l2::<lambda_45b6fea0b32e146eac7eb8d3175611d0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<LessonItemCache>` | weakThis


### `LibraryCollection::refresh::__l12::<lambda_660a8991daf205c274a409143d346b65>`
Offset | Type | Name
-|-|-|-
0 | (8) `LibraryCollection *const` | __this


### `Legacy::WorldImporter::importWorld::__l2::<lambda_ae938f074dd3a375f0777a73fbeb379e>`
Offset | Type | Name
-|-|-|-
0 | (8) `Legacy::WorldImporter *const` | __this
8 | (16) `std::shared_ptr<Social::User>` | user
24 | (16) `std::shared_ptr<Legacy::WorldProcessRequest>` | processRequest
40 | (16) `Legacy::WorldImporter::importWorld::__l2::<lambda_366519f82ad483b9658c695262c21046>` | progressCallback


### `Legacy::WorldImporter::importWorld::__l2::<lambda_366519f82ad483b9658c695262c21046>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> > >` | context


### `LegacyOptionsConverterInternal::_makeGenericRecipe::__l2::<lambda_9f36d3efb04074791ed7f3702039126e>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(Option *,bool)>` | setOption


### `LegacyOptionsConverterInternal::_makeGenericRecipe::__l2::<lambda_3250100f958fa1f0f26c0275bd843c8d>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(Option *,unsigned char)>` | setOption


### `Legacy::WorldImporter::retrieveWorldList::__l2::<lambda_c472bd97cd77568961a14503f1a05380>`
Offset | Type | Name
-|-|-|-
0 | (8) `Legacy::WorldImporter *const` | __this
8 | (64) `std::function<void __cdecl(enum Legacy::RetrieveStatus)>` | fetchCompleteCB


### `Legacy::WorldImporter::importWorld::__l2::<lambda_b2029e45b00b21c59d0f455bcac15a46>`
Offset | Type | Name
-|-|-|-
0 | (8) `Legacy::WorldImporter *const` | __this
8 | (64) `std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)>` | statusCallback


### `Legacy::WorldConversionReport`
Offset | Type | Name
-|-|-|-
0 | (4) `Legacy::WorldConverter::ConversionResult` | mResult
8 | (32) `std::string` | mWorldName
40 | (8) `std::chrono::duration<double,std::ratio<1,1> >` | mConversionDurationSeconds
48 | (8) `unsigned __int64` | mChunksConverted
56 | (8) `unsigned __int64` | mTotalEstimatedChunks
64 | (4) `Legacy::WorldConverter::Type` | mOriginatingPlatform
72 | (32) `std::string` | mConverterVersion


### `LibraryDeeplinkListener::_navigateToLink::__l2::<lambda_d498d340354ce2f453ed38567f54fbc2>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<bool>` | existenceTracker
16 | (16) `std::shared_ptr<AsyncTracker>` | timeoutTracker
32 | (8) `const LibraryDeeplinkListener *const` | __this
40 | (16) `std::shared_ptr<SearchResult>` | searchResult
56 | (24) `std::vector<std::pair<std::string,std::string >>` | eventProperties


### `LabTablePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `LabTablePacket::Type` | mType
44 | (12) `BlockPos` | mPos
56 | (1) `LabTableReactionType` | mReaction


### `LegacyClientNetworkHandler::handle::__l2::<lambda_fa967f588a1ce712e27d64a182893b8b>`
Offset | Type | Name
-|-|-|-
0 | (64) `const BlockEventPacket` | packet


### `LegacyClientNetworkHandler::handle::__l2::<lambda_93d079b43c62f7e1248b34064f45323f>`
Offset | Type | Name
-|-|-|-
0 | (64) `const ContainerOpenPacket` | packet
64 | (8) `LocalPlayer *` | player
72 | (8) `MultiPlayerLevel *` | level


### `LegacyClientNetworkHandler::handle::__l5::<lambda_89563cba18849588825a7327afbb76f5>`
Offset | Type | Name
-|-|-|-
0 | (8) `LegacyClientNetworkHandler *const` | __this
8 | (16) `std::shared_ptr<LevelChunkPacketHandler>` | handler
24 | (152) `const NetworkIdentifier` | source


### `LegacyClientNetworkHandler::_applyPlayerSkin::__l7::<lambda_42405ada392c75a6c6b62314c754af1d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<IClientInstance>` | weakClient
16 | (16) `mce::UUID` | uuid
32 | (640) `const SerializedSkin` | serializableSkin
672 | (8) `LegacyClientNetworkHandler *const` | __this
680 | (16) `std::weak_ptr<bool>` | weakExistance
696 | (4) `unsigned int` | version


### `LevelChunkPacketHandler::_addReuseFromCacheStep::__l2::<lambda_00c643ea340363bdff366ebe864def6e>`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelChunkPacketHandler *const` | __this
8 | (8) `unsigned __int64` | i
16 | (4) `float` | abortRequestTime
24 | (64) `std::function<void __cdecl(VarIntDataInput &)>` | deserializer


### `LinearAllocator<ViewRenderObject>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LevelBuilder::scheduleChunkBuild::__l19::<lambda_72252b7199841403e2a415b3bd023c08>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | immediate
8 | (16) `std::shared_ptr<RenderChunkInstanced>` | renderChunkInstancedShared
24 | (16) `const std::shared_ptr<RenderChunkShared>` | renderChunkShared
40 | (1) `bool` | doSort
48 | (8) `LevelBuilder *const` | __this
56 | (16) `std::shared_ptr<SortTaskContext>` | sortTaskContext
72 | (16) `std::shared_ptr<BuildTaskContext>` | buildTaskContext
88 | (16) `const std::shared_ptr<RenderChunkGeometry>` | buildingRenderChunkGeometry
104 | (16) `const std::shared_ptr<RenderChunkGeometry>` | currentRenderChunkGeometry


### `LevelBuilder::scheduleChunkBuild::__l19::<lambda_06fe4843def8ec0a40648f31185946ab>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<RenderChunkInstanced>` | renderChunkInstancedShared
16 | (16) `const std::shared_ptr<RenderChunkShared>` | renderChunkShared
32 | (1) `const bool` | transparentLeaves
36 | (4) `_BYTE[4]` | lightingType
40 | (1) `const bool` | usePBRFormats
41 | (1) `const bool` | emitPointLights
42 | (1) `bool` | doSort
44 | (12) `Vec3` | currentCameraForward
56 | (1) `const bool` | cullerIsOrthographic
64 | (16) `std::shared_ptr<SortTaskContext>` | sortTaskContext
80 | (16) `std::shared_ptr<BuildTaskContext>` | buildTaskContext


### `LinearAllocator<ActorShadowRenderObject>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LinearAllocator<ParticleTypeRenderObject>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LinearAllocator<mce::TexturePtr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LinearAllocator<CrackRenderObject>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LinearAllocator<NameTagRenderObject>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AllocatorData>` | mData


### `LevelCullerCachedBase::UpdateChunkData`
Offset | Type | Name
-|-|-|-
0 | (12) `SubChunkPos` | mRenderChunkPosition
12 | (1) `bool` | mIsSkyLit
13 | (6) `VisibilityNode` | mVisibilityNode
19 | (1) `bool` | mChunkIsEmpty
20 | (1) `bool` | mForceRequery


### `LevelRendererCamera::updatePerChunkFaceSortState::__l10::<lambda_d6963569be67244178665fa6230fe26b>`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelRendererCamera *const` | __this
8 | (12) `const Vec3` | viewPos
20 | (12) `BlockPos` | blockSortPos
32 | (12) `const Vec3` | viewDir
44 | (12) `BlockPos` | lastFaceSortPos
56 | (12) `Vec3` | lastFaceSortDir
68 | (1) `bool` | isOrthoCamera
72 | (16) `std::shared_ptr<GridArea<std::shared_ptr<RenderChunkInstanced> > >` | bufferedViewArea


### `LevelRendererCamera::RenderChunkPosBounds`
Offset | Type | Name
-|-|-|-
0 | (12) `SubChunkPos` | min
12 | (12) `SubChunkPos` | max


### `Layer<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (24) `LayerDetails::LayerBase` | baseclass_0


### `LayerDetails::LayerBase`
Offset | Type | Name
-|-|-|-
0 | (8) `LayerDetails::LayerBase_vtbl *` | __vftable
8 | (8) `__int64` | mSeed
16 | (8) `__int64` | mSeedMixup


### `LegacyTradeableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAddRecipeOnUpdate
1 | (1) `bool` | mResetLockedOnFirstTrade
2 | (1) `bool` | mWillingToBreed
4 | (4) `int` | mRiches
8 | (4) `int` | mTradeTier
12 | (4) `int` | mUpdateMerchantTimer
16 | (8) `Player *` | mLastPlayerTradeName
24 | (8) `std::unique_ptr<MerchantRecipeList>` | mOffers
32 | (32) `std::string` | mDisplayName
64 | (24) `std::vector<int>` | mTradeRecipeFirstTime


### `ListTagFloatAdder`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ListTag>` | mTag


### `LootTableContext`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mLuck
8 | (8) `Level *` | mLevel
16 | (8) `BlockSource *` | mRegion
24 | (8) `Actor *` | mThisEntity
32 | (8) `Player *` | mKillerPlayer
40 | (8) `const ActorDamageSource *` | mDeathSource
48 | (64) `std::unordered_set<LootTable const *>` | mVisitedTables
112 | (4) `float` | mExplosionRadius
120 | (32) `std::string` | mOriginalItemName


### `ListTagIntAdder`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ListTag>` | mTag


### `LocalConnector::LocalConnection`
Offset | Type | Name
-|-|-|-
0 | (8) `LocalConnector *` | mConnector
8 | (152) `NetworkIdentifier` | mId


### `LookControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHasWantedPosition
1 | (1) `bool` | mHasWantedRotation
4 | (4) `float` | mYMax
8 | (4) `float` | mXMax
12 | (12) `Vec3` | mWantedPosition
24 | (12) `Vec3` | mWantedRotation
40 | (8) `std::unique_ptr<LookControl>` | mLookControl


### `leveldb::Status`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | state_


### `leveldb::Compressor`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Compressor_vtbl *` | __vftable
8 | (8) `unsigned __int64` | inputBytes
16 | (8) `unsigned __int64` | compressedBytes
24 | (1) `const char` | uniqueCompressionID


### `leveldb::ZlibCompressorBase`
Offset | Type | Name
-|-|-|-
0 | (32) `leveldb::Compressor` | baseclass_0
32 | (4) `const int` | compressionLevel
36 | (1) `const bool` | raw


### `LocalConnector::connect::__l5::<lambda_53fd3492de6269a51add08adad05dd5f>`
Offset | Type | Name
-|-|-|-
0 | (8) `LocalConnector *const` | __this
8 | (152) `NetworkIdentifier` | hostId
160 | (16) `std::shared_ptr<LocalNetworkPeer>` | newPeer


### `LocalConnector::createPeer::__l2::<lambda_ddc662792dc88affbd03064fa30cfc5e>`
Offset | Type | Name
-|-|-|-
0 | (8) `LocalConnector *const` | __this
8 | (152) `NetworkIdentifier` | clientId
160 | (16) `std::shared_ptr<LocalNetworkPeer>` | newPeer


### `ListDCommand::execute::__l2::<lambda_b3cf132935515dc31340e61291b1a510>`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value *` | playerList
8 | (8) `std::basic_stringstream<char,std::char_traits<char>,std::allocator<char> > *` | stream
16 | (8) `int *` | count
24 | (8) `std::basic_stringstream<char,std::char_traits<char>,std::allocator<char> > *` | hexFormatter
32 | (8) `bool *` | stats
40 | (8) `bool *` | listUUIDs
48 | (8) `bool *` | listIds
56 | (8) `std::string *` | globalMultiplayerCorrelationId


### `LookAtDefinition`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSetTarget
4 | (4) `float` | mSearchRadius
8 | (1) `bool` | mAllowInvulnerable
12 | (8) `FloatRange` | mLookCooldown
24 | (64) `ActorFilterGroup` | mFilter
88 | (320) `DefinitionTrigger` | mOnLookAt


### `LevelEventCoordinator::sendLevelWeatherChanged::__l2::<lambda_33b11a197678339fe6beb420e10f4191>`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | dimension
32 | (1) `bool` | raining
33 | (1) `bool` | lightning


### `LayerResult<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char [0]>` | mResult


### `LevelChunk::HardcodedSpawningArea`
Offset | Type | Name
-|-|-|-
0 | (24) `BoundingBox` | aabb
24 | (1) `HardcodedSpawnAreaType` | type


### `LevelChunkHashMapKey`
Offset | Type | Name
-|-|-|-
0 | (1) `LevelChunkTag` | mTag
8 | (8) `unsigned __int64` | mIndex


### `Level::LevelChunkQueuedSavingElement`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDist
8 | (8) `ChunkPos` | mPosition
16 | (4) `AutomaticID<Dimension,int>` | mDimensionId


### `Level::explode::__l5::<lambda_81dee22cf752cbc31af5429df6d1a2ac>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::string *` | sID
8 | (8) `long double *` | x
16 | (8) `long double *` | y
24 | (8) `long double *` | z
32 | (8) `float *` | explosionRadius
40 | (8) `bool *` | fire
48 | (8) `bool *` | breaksBlocks


### `LegacyBlockPlacementProcessor`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
4 | (2516) `Random` | mRandom
2520 | (1) `bool` | mHasGravity
2528 | (8) `const std::vector<std::unique_ptr<StructurePoolBlockRule>> *` | mBlockRules
2536 | (8) `const std::vector<std::unique_ptr<StructurePoolBlockTagRule>> *` | mBlockTagRules


### `LegacyJigsawPlacement`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mMaxDepth
8 | (64) `std::function<std::unique_ptr<PoolElementStructurePiece> __cdecl(StructurePoolElement const &,BlockPos const &,enum Rotation const &,int,JigsawJunction &,BoundingBox const &,BlockPos const &)>` | mFactory
72 | (64) `std::unordered_map<ChunkPos,std::unique_ptr<std::vector<short>>>` | mChunkHeightCache


### `LevelChunk`
Offset | Type | Name
-|-|-|-
0 | (80) `std::mutex` | mBlockEntityAccessLock
80 | (8) `Level *` | mLevel
88 | (8) `Dimension *` | mDimension
96 | (12) `BlockPos` | mMin
108 | (12) `BlockPos` | mMax
120 | (8) `ChunkPos` | mPosition
128 | (1) `bool` | mLightingFixupDone
129 | (1) `std::atomic<bool>` | mLightingTaskActive
130 | (1) `bool` | mReadOnly
136 | (8) `ChunkSource *` | mGenerator
144 | (2) `std::optional<enum LevelChunkFormat>` | mLoadedFormat
152 | (32) `std::string` | mSerializedEntitiesBuffer
184 | (1) `std::atomic<enum ChunkState>` | mLoadState
185 | (1) `ChunkTerrainDataState` | mTerrainDataState
186 | (1) `ChunkDebugDisplaySavedState` | mDebugDisplaySavedState
187 | (1) `ChunkCachedDataState` | mCachedDataState
192 | (32) `SpinLock` | mCachedDataStateSpinLock
224 | (8) `Tick` | mLastTick
232 | (8) `std::unique_ptr<BlockTickingQueue>` | mTickQueue
240 | (8) `std::unique_ptr<BlockTickingQueue>` | mRandomTickQueue
248 | (1832) `AppendOnlyAtomicLookupTable<SubChunk,32>` | mSubChunks
2080 | (1024) `std::array<SpinLock,32>` | mSubChunkSpinLocks
3104 | (256) `std::array<BiomeChunkData,256>` | mBiomes
3360 | (2048) `std::array<ColumnCachedData,256>` | mCachedData
5408 | (512) `std::array<ChunkLocalHeight,256>` | mHeightmap
5920 | (8) `std::unique_ptr<std::vector<short>>` | mPreWorldGenHeightmap
5928 | (64) `std::unordered_map<unsigned char,BiomeChunkState>` | mBiomeStates
5992 | (1) `bool` | mHasCachedTemperatureNoise
5993 | (256) `std::array<unsigned char,256>` | mBorderBlockMap
6252 | (4) `LevelChunk::Finalization` | mFinalized
6256 | (1) `bool` | mIsRedstoneLoaded
6257 | (1) `bool` | mOwnedByTickingThread
6260 | (56) `DirtyTicksCounter[7]` | mFullChunkDirtyTicksCounters
6316 | (512) `std::array<ChunkLocalHeight,256>` | mRainHeights
6832 | (24) `SmallSet<std::unique_ptr<Actor> >` | mEntities
6856 | (64) `std::unordered_map<ChunkBlockPos,std::shared_ptr<BlockActor>>` | mBlockEntities
6920 | (24) `std::vector<std::shared_ptr<BlockActor>>` | mDeletedBlockEntities
6944 | (2) `BrightnessPair` | mDefaultBrightness
6952 | (24) `std::vector<LevelChunk::HardcodedSpawningArea>` | mHardcodedSpawningAreas
6976 | (4) `unsigned __int8[2][2]` | mbChunkInterpolants
6980 | (1) `bool` | mbChunkHasConverterTag
6981 | (1) `bool` | mDBChunkSurroundedByNeighbors
6984 | (64) `std::unordered_map<LevelChunkHashMapKey,unsigned __int64>` | mLevelChunkChecksums
7048 | (1) `bool` | mOnChunkLoadedCalled
7056 | (80) `std::mutex` | mMicroBlockModelStorageLock
7136 | (80) `std::mutex` | mMicroBlockModelTableLock
7216 | (80) `std::mutex` | mStaticMicroBlockModelTableLock
7296 | (80) `std::mutex` | mMicroBlockUsingMapLock
7376 | (64) `?` | mMicroBlockModelStorage
7440 | (64) `std::unordered_map<BlockPos,std::string>` | mMicroBlockModelTable
7504 | (64) `std::unordered_map<BlockPos,std::string>` | mStaticMicroBlockModelTable
7568 | (64) `std::unordered_map<std::string,int>` | mMicroBlockUsingMap


### `LevelStorageWriteBatch`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelStorageWriteBatch_vtbl *` | __vftable
8 | (24) `std::vector<std::function<void __cdecl(void)>>` | mFlushCallbacks
32 | (16) `std::map<std::string,LevelStorageWriteBatch::BatchEntry>` | mBatch
48 | (80) `std::mutex` | mFlushCallbacksMutex


### `LevelLooseFileStorage::<lambda_243d65738535c465e89fa7d414db982c>`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | root
32 | (24) `const ContentIdentity` | contentIdentity
56 | (8) `const IContentKeyProvider *` | keyProvider


### `leveldb::Slice`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | data_
8 | (8) `unsigned __int64` | size_


### `LevelCache`
Offset | Type | Name
-|-|-|-
0 | (384) `LevelSummary` | summary
384 | (8) `std::unique_ptr<LevelData>` | data
392 | (1) `bool` | dirtySummary
393 | (1) `bool` | isPartiallyCopied


### `LoomScreenControllerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(int)>` | mAddItem
64 | (64) `std::function<void __cdecl(int)>` | mAddDye
128 | (64) `std::function<int __cdecl(BannerPattern const *)>` | mGetPatternIndex
192 | (64) `std::function<void __cdecl(int)>` | mSetSelectedPattern
256 | (64) `std::function<ItemStackBase const & __cdecl(void)>` | mGetResultItem


### `LayerBiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeSource` | baseclass_0
8 | (16) `std::shared_ptr<Layer<Biome *> const >` | mBlockResolutionLayer


### `LayerDetails::RandomProviderT<<lambda_771016eb0f7e2748065ada6628a00507> >`
Offset | Type | Name
-|-|-|-
0 | (8) `LayerDetails::LayerBase::initRandom::__l2::<lambda_771016eb0f7e2748065ada6628a00507>` | mNextRandom
8 | (8) `__int64` | mRval


### `LayerDetails::LayerBase::initRandom::__l2::<lambda_771016eb0f7e2748065ada6628a00507>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | seed


### `LakeFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock
32 | (8) `const Block *` | mEmptyBlock


### `LayerFilters::AddBiomeIsland::{ctor}::__l2::<lambda_d22b2d79a9b449dd8757e60c4491a3ad>`
Offset | Type | Name
-|-|-|-
0 | (8) `LayerFilters::AddBiomeIsland *const` | __this
8 | (224) `TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> >` | tagRegistry
232 | (1008) `WellKnownBiomeTags` | wellKnownBiomeTags


### `LayerFilters::RiverInit::{ctor}::__l2::<lambda_b3b651c19a7ac355c635e67204b20baa>`
Offset | Type | Name
-|-|-|-
0 | (8) `LayerFilters::RiverInit *const` | __this
8 | (224) `TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> >` | tagRegistry
232 | (1008) `WellKnownBiomeTags` | wellKnownBiomeTags


### `leveldb::MutexLock`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::port::Mutex *const` | mu_


### `leveldb::ParsedInternalKey`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::Slice` | user_key
16 | (8) `unsigned __int64` | sequence
24 | (4) `leveldb::ValueType` | type


### `leveldb::FileMetaData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | refs
4 | (4) `int` | allowed_seeks
8 | (8) `unsigned __int64` | number
16 | (8) `unsigned __int64` | file_size
24 | (32) `leveldb::InternalKey` | smallest
56 | (32) `leveldb::InternalKey` | largest


### `leveldb::VersionSet::Builder::BySmallestKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::InternalKeyComparator *` | internal_comparator


### `leveldb::VersionEdit`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | comparator_
32 | (8) `unsigned __int64` | log_number_
40 | (8) `unsigned __int64` | prev_log_number_
48 | (8) `unsigned __int64` | next_file_number_
56 | (8) `unsigned __int64` | last_sequence_
64 | (1) `bool` | has_comparator_
65 | (1) `bool` | has_log_number_
66 | (1) `bool` | has_prev_log_number_
67 | (1) `bool` | has_next_file_number_
68 | (1) `bool` | has_last_sequence_
72 | (24) `std::vector<std::pair<int,leveldb::InternalKey>>` | compact_pointers_
96 | (16) `std::set<std::pair<int,unsigned __int64>>` | deleted_files_
112 | (24) `std::vector<std::pair<int,leveldb::FileMetaData>>` | new_files_


### `leveldb::log::Writer`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::WritableFile *` | dest_
8 | (4) `int` | block_offset_
12 | (20) `unsigned int[5]` | type_crc_


### `leveldb::log::Reader`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::SequentialFile *const` | file_
8 | (8) `leveldb::log::Reader::Reporter *const` | reporter_
16 | (1) `const bool` | checksum_
24 | (8) `char *const` | backing_store_
32 | (16) `leveldb::Slice` | buffer_
48 | (1) `bool` | eof_
56 | (8) `unsigned __int64` | last_record_offset_
64 | (8) `unsigned __int64` | end_of_buffer_offset_
72 | (8) `const unsigned __int64` | initial_offset_
80 | (1) `bool` | resyncing_


### `leveldb::DBImpl::CompactionState::Output`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | number
8 | (8) `unsigned __int64` | file_size
16 | (32) `leveldb::InternalKey` | smallest
48 | (32) `leveldb::InternalKey` | largest


### `leveldb::ReadOptions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | verify_checksums
1 | (1) `bool` | fill_cache
8 | (8) `const leveldb::Snapshot *` | snapshot
16 | (8) `leveldb::DecompressAllocator *` | decompress_allocator


### `leveldb::LookupKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | start_
8 | (8) `const char *` | kstart_
16 | (8) `const char *` | end_
24 | (200) `char[200]` | space_


### `leveldb::Version::GetStats`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::FileMetaData *` | seek_file
8 | (4) `int` | seek_file_level


### `leveldb::WriteBatch::Handler`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::WriteBatch::Handler_vtbl *` | __vftable


### `leveldb::Options`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::Comparator *` | comparator
8 | (1) `bool` | create_if_missing
9 | (1) `bool` | error_if_exists
10 | (1) `bool` | paranoid_checks
16 | (8) `leveldb::Env *` | env
24 | (8) `leveldb::Logger *` | info_log
32 | (8) `unsigned __int64` | write_buffer_size
40 | (4) `int` | max_open_files
48 | (8) `leveldb::Cache *` | block_cache
56 | (8) `unsigned __int64` | block_size
64 | (4) `int` | block_restart_interval
72 | (8) `unsigned __int64` | max_file_size
80 | (2048) `leveldb::Compressor *[256]` | compressors
2128 | (1) `bool` | reuse_logs
2136 | (8) `const leveldb::FilterPolicy *` | filter_policy


### `leveldb::InternalKeyComparator`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Comparator` | baseclass_0
8 | (8) `const leveldb::Comparator *` | user_comparator_


### `leveldb::Comparator`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Comparator_vtbl *` | __vftable


### `leveldb::InternalFilterPolicy`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::FilterPolicy` | baseclass_0
8 | (8) `const leveldb::FilterPolicy *const` | user_policy_


### `leveldb::FilterPolicy`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::FilterPolicy_vtbl *` | __vftable


### `leveldb::VersionSet::Builder`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::VersionSet *` | vset_
8 | (8) `leveldb::Version *` | base_
16 | (168) `leveldb::VersionSet::Builder::LevelState[7]` | levels_


### `leveldb::VersionSet::Builder::LevelState`
Offset | Type | Name
-|-|-|-
0 | (16) `std::set<unsigned __int64>` | deleted_files
16 | (8) `std::set<leveldb::FileMetaData *,leveldb::VersionSet::Builder::BySmallestKey,std::allocator<leveldb::FileMetaData *> > *` | added_files


### `leveldb::Footer`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::BlockHandle` | metaindex_handle_
16 | (16) `leveldb::BlockHandle` | index_handle_


### `leveldb::BlockHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | offset_
8 | (8) `unsigned __int64` | size_


### `leveldb::BlockContents`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::Slice` | data
16 | (1) `bool` | cachable
17 | (1) `bool` | heap_allocated


### `leveldb::BlockBuilder`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::Options *` | options_
8 | (32) `std::string` | buffer_
40 | (24) `std::vector<unsigned int>` | restarts_
64 | (4) `int` | counter_
68 | (1) `bool` | finished_
72 | (32) `std::string` | last_key_


### `leveldb::port::AtomicPointer`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | rep_


### `LocaleInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | decimal_point
8 | (8) `char *` | thousands_sep
16 | (8) `char *` | grouping


### `ListTag_vtbl`
```
struct /*VFT*/ ListTag_vtbl
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

### `LocalConnector::ConnectionCallbacks`
```
struct __cppobj LocalConnector::ConnectionCallbacks
{
  LocalConnector::ConnectionCallbacks_vtbl *__vftable /*VFT*/;
};

```

### `LocalConnector::ConnectionCallbacks_vtbl`
```
struct /*VFT*/ LocalConnector::ConnectionCallbacks_vtbl
{
  void (__fastcall *~ConnectionCallbacks)(LocalConnector::ConnectionCallbacks *this);
  void (__fastcall *onNewIncomingLocalConnection)(LocalConnector::ConnectionCallbacks *this, const NetworkIdentifier *, std::shared_ptr<NetworkPeer>);
  void (__fastcall *onNewOutgoingLocalConnection)(LocalConnector::ConnectionCallbacks *this, const NetworkIdentifier *, std::shared_ptr<NetworkPeer>);
  void (__fastcall *onConnectionClosed)(LocalConnector::ConnectionCallbacks *this, const NetworkIdentifier *, const std::string *, bool);
  void (__fastcall *onOutgoingConnectionFailed)(LocalConnector::ConnectionCallbacks *this);
};

```

### `LocalConnector`
```
struct __cppobj LocalConnector : Connector
{
  LocalConnector::ConnectionCallbacks *mCallbacks;
  NetworkIdentifier mLocalId;
  std::vector<LocalConnector::LocalConnection> mConnections;
  std::vector<std::function<void __cdecl(void)>> mCallbackQueue;
};

```

### `LocalConnector_vtbl`
```
struct /*VFT*/ LocalConnector_vtbl
{
  void (__fastcall *~Connector)(Connector *this);
  std::vector<std::string> *(__fastcall *getLocalIps)(Connector *this, std::vector<std::string> *result);
  std::string *(__fastcall *getLocalIp)(Connector *this, std::string *result);
  unsigned __int16 (__fastcall *getPort)(Connector *this);
  std::vector<RakNet::SystemAddress> *(__fastcall *getRefinedLocalIps)(Connector *this, std::vector<RakNet::SystemAddress> *result);
  const Social::GameConnectionInfo *(__fastcall *getConnectedGameInfo)(Connector *this);
  void (__fastcall *setupNatPunch)(Connector *this, bool);
  Connector::NatPunchInfo *(__fastcall *getNatPunchInfo)(Connector *this, Connector::NatPunchInfo *result);
  void (__fastcall *startNatPunchingClient)(Connector *this, Social::GameConnectionInfo);
  void (__fastcall *addConnectionStateListener)(Connector *this, Connector::ConnectionStateListener *);
  void (__fastcall *removeConnectionStateListener)(Connector *this, Connector::ConnectionStateListener *);
  bool (__fastcall *isIPv4Supported)(Connector *this);
  bool (__fastcall *isIPv6Supported)(Connector *this);
  unsigned __int16 (__fastcall *getIPv4Port)(Connector *this);
  unsigned __int16 (__fastcall *getIPv6Port)(Connector *this);
  RakNet::RakNetGUID *(__fastcall *getGUID)(Connector *this, RakNet::RakNetGUID *result);
};

```

### `Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *>`
```
struct __cppobj Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *>
{
  std::atomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mValue;
};

```

### `LabTablePacket_vtbl`
```
struct /*VFT*/ LabTablePacket_vtbl
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

### `LecternUpdatePacket_vtbl`
```
struct /*VFT*/ LecternUpdatePacket_vtbl
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

### `LevelChunkPacket::SubChunkMetadata`
```
struct __cppobj LevelChunkPacket::SubChunkMetadata
{
  unsigned __int64 blobId;
};

```

### `LevelChunkPacket`
```
struct __cppobj LevelChunkPacket : Packet
{
  bool mCacheEnabled;
  ChunkPos mPos;
  std::string mSerializedChunk;
  unsigned __int64 mSubChunksCount;
  std::vector<LevelChunkPacket::SubChunkMetadata> mCacheMetadata;
};

```

### `LevelChunkPacket_vtbl`
```
struct /*VFT*/ LevelChunkPacket_vtbl
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

### `LevelEventGenericPacket`
```
const struct __cppobj LevelEventGenericPacket : Packet
{
  int mEventId;
  std::unique_ptr<CompoundTag> mData;
};

```

### `LevelEventGenericPacket_vtbl`
```
struct /*VFT*/ LevelEventGenericPacket_vtbl
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

### `LevelEventPacket`
```
const struct __cppobj __declspec(align(8)) LevelEventPacket : Packet
{
  int mEventId;
  Vec3 mPos;
  int mData;
};

```

### `LevelEventPacket_vtbl`
```
struct /*VFT*/ LevelEventPacket_vtbl
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

### `LevelSoundEventPacketV2`
```
const struct __cppobj __declspec(align(8)) LevelSoundEventPacketV2 : Packet
{
  LevelSoundEvent mEventId;
  Vec3 mPos;
  int mData;
  std::string mEntityIdentifier;
  bool mIsBabyMob;
  bool mIsGlobal;
};

```

### `LevelSoundEventPacketV2_vtbl`
```
struct /*VFT*/ LevelSoundEventPacketV2_vtbl
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

### `LevelSoundEventPacketV1`
```
const struct __cppobj __declspec(align(8)) LevelSoundEventPacketV1 : Packet
{
  LevelSoundEvent mEventId;
  Vec3 mPos;
  int mData;
  ActorType mEntityType;
  bool mIsBabyMob;
  bool mIsGlobal;
};

```

### `LevelSoundEventPacketV1_vtbl`
```
struct /*VFT*/ LevelSoundEventPacketV1_vtbl
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

### `LevelSoundEventPacket_vtbl`
```
struct /*VFT*/ LevelSoundEventPacket_vtbl
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

### `LoginPacket`
```
const struct __cppobj LoginPacket : Packet
{
  int mClientNetworkVersion;
  std::unique_ptr<ConnectionRequest> mConnectionRequest;
};

```

### `LoginPacket_vtbl`
```
struct /*VFT*/ LoginPacket_vtbl
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

### `Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *>`
```
struct __cppobj Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *>
{
  std::atomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *> mValue;
};

```

### `LegacyPackIdVersion`
```
struct __cppobj LegacyPackIdVersion
{
  std::string mId;
  std::string mVersion;
};

```

### `LoadedResourceData`
```
struct __cppobj LoadedResourceData
{
  int mIndex;
  std::string mContent;
};

```

### `LevelListener`
```
struct __cppobj LevelListener : BlockSourceListener
{
};

```

### `LightTexture`
```
struct __cppobj LightTexture
{
  std::shared_ptr<mce::Image> mBrightnessImage;
  _BYTE mBrightnessTextureId[1];
  std::shared_ptr<mce::ClientTexture> mBrightnessTexture;
  bool mIsTextureDirty;
  BaseLightData mLightData;
};

```

### `LegacyStructureBlockPalette`
```
struct __cppobj LegacyStructureBlockPalette
{
  std::unordered_map<int,Block const *> mMapper;
};

```

### `LegacyStructureBlockInfo`
```
struct __cppobj LegacyStructureBlockInfo
{
  BlockPos mPos;
  const Block *mBlock;
  const Block *mExtraBlock;
  std::unique_ptr<CompoundTag> mTag;
};

```

### `LegacyStructureActorInfo`
```
struct __cppobj LegacyStructureActorInfo
{
  Vec3 mPos;
  BlockPos mBlockPos;
  CompoundTag mTag;
};

```

### `LegacyStructureTemplate`
```
struct __cppobj LegacyStructureTemplate
{
  std::string mAuthor;
  BlockPos mSize;
  LegacyStructureBlockPalette mPalette;
  LegacyStructureBlockPalette mExtraBlockPalette;
  std::vector<LegacyStructureBlockInfo> mBlockInfo;
  std::vector<LegacyStructureActorInfo> mEntityInfo;
};

```

### `LevelChunkFinalDeleter`
```
struct __cppobj LevelChunkFinalDeleter
{
};

```

### `LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> >`
```
struct __cppobj LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> >
{
  std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> mChunkElemMap;
  SpinLock mSpinLock;
};

```

### `LevelChunkBuilderData::ChunkReadyForProcessingElement`
```
struct __cppobj __declspec(align(8)) LevelChunkBuilderData::ChunkReadyForProcessingElement
{
  std::pair<ChunkPos,enum ChunkState> mChunkPosAndExpectedState;
  int mPriority;
};

```

### `LevelChunkBuilderData`
```
struct __cppobj LevelChunkBuilderData
{
  SpinLock mChunkGenerationGridMapSpinLock;
  std::unordered_map<ChunkPos,std::shared_ptr<LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> > >> mChunkGenerationGridMap;
  SpinLock mChunksToAddToProcessingSpinLock;
  std::vector<std::pair<ChunkPos,enum ChunkState>> mChunksToAddToProcessing;
  SpinLock mChunksReadyForProcessingSpinLock;
  std::unordered_set<std::pair<ChunkPos,enum ChunkState>> mChunksReadyForProcessing;
  std::vector<LevelChunkBuilderData::ChunkReadyForProcessingElement> mChunkSortVector;
  std::atomic<int> mChunkGenerationTasksInFlight;
  SpinLock mSpawnTasksLock;
};

```

### `LoopbackPacketSender`
```
struct __cppobj LoopbackPacketSender : PacketSender
{
  NetworkHandler *mNetwork;
  std::vector<NetEventCallback *> mLoopbackCallbacks;
  const std::vector<std::unique_ptr<Player>> *mUserList;
  std::vector<NetworkIdentifierWithSubId> mTempUserIds;
};

```

### `LoopbackPacketSender_vtbl`
```
struct /*VFT*/ LoopbackPacketSender_vtbl
{
  void (__fastcall *~PacketSender)(PacketSender *this);
  void (__fastcall *send)(PacketSender *this, Packet *);
  void (__fastcall *sendToServer)(PacketSender *this, Packet *);
  void (__fastcall *sendToClient)(PacketSender *this, const NetworkIdentifier *, const Packet *, unsigned __int8);
  void (__fastcall *sendToClients)(PacketSender *this, const std::vector<NetworkIdentifierWithSubId> *, const Packet *);
  void (__fastcall *sendBroadcast)(PacketSender *this, const NetworkIdentifier *, unsigned __int8, const Packet *);
  void (__fastcall *sendBroadcast)(PacketSender *this, const Packet *);
  void (__fastcall *flush)(PacketSender *this, const NetworkIdentifier *, std::function<void __cdecl(void)> *);
};

```

### `LevelStorage`
```
struct __cppobj LevelStorage
{
  LevelStorage_vtbl *__vftable /*VFT*/;
};

```

### `LevelStorageObserver`
```
struct __cppobj LevelStorageObserver
{
  std::function<void __cdecl(std::string const &)> mOnSaveCallback;
};

```

### `LevelStorageWriteBatch_vtbl`
```
struct /*VFT*/ LevelStorageWriteBatch_vtbl
{
  void (__fastcall *~LevelStorageWriteBatch)(LevelStorageWriteBatch *this);
  void (__fastcall *putKey)(LevelStorageWriteBatch *this, const std::string *, std::shared_ptr<std::string >);
  void (__fastcall *putKey)(LevelStorageWriteBatch *this, const std::string *, std::string *);
  void (__fastcall *putKey)(LevelStorageWriteBatch *this, const std::string *, const std::string *);
  void (__fastcall *putKey)(LevelStorageWriteBatch *this, const std::string *, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *deleteKey)(LevelStorageWriteBatch *this, const std::string *);
  void (__fastcall *flush)(LevelStorageWriteBatch *this, LevelStorage *);
};

```

### `LevelStorageWriteBatch::BatchEntry`
```
struct __cppobj __declspec(align(8)) LevelStorageWriteBatch::BatchEntry
{
  std::shared_ptr<std::string > mLatestValue;
  bool mDeleted;
};

```

### `LevelStorage_vtbl`
```
struct /*VFT*/ LevelStorage_vtbl
{
  void (__fastcall *~LevelStorage)(LevelStorage *this);
  void (__fastcall *addStorageObserver)(LevelStorage *this, std::unique_ptr<LevelStorageObserver>);
  std::unique_ptr<CompoundTag> *(__fastcall *getCompoundTag)(LevelStorage *this, std::unique_ptr<CompoundTag> *result, const std::string *);
  bool (__fastcall *hasKey)(LevelStorage *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *forEachKeyWithPrefix)(LevelStorage *this, gsl::basic_string_span<char const ,-1>, const std::function<void __cdecl(gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1>)> *);
  bool (__fastcall *loadLevelData)(LevelStorage *this, LevelData *);
  std::unique_ptr<ChunkSource> *(__fastcall *createChunkStorage)(LevelStorage *this, std::unique_ptr<ChunkSource> *result, std::unique_ptr<ChunkSource>, StorageVersion);
  void (__fastcall *saveLevelData)(LevelStorage *this, const LevelData *);
  const Core::PathBuffer<std::string > *(__fastcall *getFullPath)(LevelStorage *this);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *saveData)(LevelStorage *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, const LevelStorageWriteBatch *);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *saveData)(LevelStorage *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, const std::string *, std::string *);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *deleteData)(LevelStorage *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, const std::string *);
  void (__fastcall *syncIO)(LevelStorage *this);
  void (__fastcall *getStatistics)(LevelStorage *this, std::string *);
  bool (__fastcall *clonePlayerData)(LevelStorage *this, gsl::basic_string_span<char const ,-1>, gsl::basic_string_span<char const ,-1>);
  Core::LevelStorageResult *(__fastcall *getLevelStorageState)(LevelStorage *this, Core::LevelStorageResult *result);
  void (__fastcall *startShutdown)(LevelStorage *this);
  bool (__fastcall *isShuttingDown)(LevelStorage *this);
  bool (__fastcall *checkShutdownDone)(LevelStorage *this);
  bool (__fastcall *loadData)(LevelStorage *this, gsl::basic_string_span<char const ,-1>, std::string *);
  Core::LevelStorageResult *(__fastcall *getState)(LevelStorage *this, Core::LevelStorageResult *result);
  std::vector<SnapshotFilenameAndLength> *(__fastcall *createSnapshot)(LevelStorage *this, std::vector<SnapshotFilenameAndLength> *result, const std::string *);
  void (__fastcall *releaseSnapshot)(LevelStorage *this);
  void (__fastcall *compactStorage)(LevelStorage *this);
  void (__fastcall *syncAndSuspendStorage)(LevelStorage *this);
  void (__fastcall *resumeStorage)(LevelStorage *this);
  void (__fastcall *setFlushAllowed)(LevelStorage *this, bool);
  void (__fastcall *flushToPermanentStorage)(LevelStorage *this);
  void (__fastcall *freeCaches)(LevelStorage *this);
  void (__fastcall *setCompactionCallback)(LevelStorage *this, std::function<void __cdecl(enum CompactionStatus)>);
  void (__fastcall *setCriticalSyncSaveCallback)(LevelStorage *this, std::function<void __cdecl(void)>);
  void (__fastcall *corruptLevel)(LevelStorage *this);
};

```

### `Lockless::WeakAtomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *>`
```
struct __cppobj Lockless::WeakAtomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *>
{
  std::atomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *> mValue;
};

```

### `LevelEventListener`
```
struct __cppobj LevelEventListener
{
  LevelEventListener_vtbl *__vftable /*VFT*/;
};

```

### `LevelEventListener_vtbl`
```
struct /*VFT*/ LevelEventListener_vtbl
{
  void (__fastcall *~LevelEventListener)(LevelEventListener *this);
  EventResult (__fastcall *onLevelInitialized)(LevelEventListener *this, Level *);
  EventResult (__fastcall *onLevelSaveData)(LevelEventListener *this, Level *, CompoundTag *);
  EventResult (__fastcall *onLevelAddedPlayer)(LevelEventListener *this, Level *, Player *);
  EventResult (__fastcall *onLevelRemovedPlayer)(LevelEventListener *this, Level *, Player *);
  EventResult (__fastcall *onLevelRemovedActor)(LevelEventListener *this, Level *, Actor *);
  EventResult (__fastcall *onLevelAddedActor)(LevelEventListener *this, Level *, Actor *);
  EventResult (__fastcall *onLevelTick)(LevelEventListener *this);
  EventResult (__fastcall *onLevelWeatherChange)(LevelEventListener *this, const std::string *, bool, bool);
  EventResult (__fastcall *onLevelBiomesRegistered)(LevelEventListener *this, BiomeRegistry *);
};

```

### `LocalPlayer::EmotePlayedTelemetryData`
```
struct __cppobj LocalPlayer::EmotePlayedTelemetryData
{
  std::string mEmoteProductId;
  bool mEmoteEndedEarly;
  bool mEmotePlayed;
  int mEmoteSlotNumber;
};

```

### `LocalPlayer::RegionListener`
```
struct __cppobj LocalPlayer::RegionListener
{
  LocalPlayer::RegionListener_vtbl *__vftable /*VFT*/;
};

```

### `LocalPlayer::RegionListener_vtbl`
```
struct /*VFT*/ LocalPlayer::RegionListener_vtbl
{
  void (__fastcall *~RegionListener)(LocalPlayer::RegionListener *this);
  void (__fastcall *onRegionDestroyed)(LocalPlayer::RegionListener *this);
};

```

### `LocalPlayer`
```
const struct __cppobj __declspec(align(8)) LocalPlayer : Player
{
  InventoryMenu mInventoryMenu;
  float mPortalEffectTime;
  float mOPortalEffectTime;
  LocalPlayer::EmotePlayedTelemetryData mEmotePlayedTelemetryData;
  IClientInstance *mClient;
  _BYTE mLoadingState[4];
  int mCanCloseScreenOnHurtAfterTime;
  bool mIsRotatingViaScript;
  bool mIsDenyInput;
  bool mCheatTesting;
  float mFlyX;
  float mFlyY;
  float mFlyZ;
  Vec3 mlastFrameDelta;
  Vec2 mLastHmdRot;
  Vec2 mHmdAngleDelta;
  float mActionOrStopGazeLock;
  bool mHmdRotRecorded;
  bool mActionOrStopThisFrame;
  bool mEnablePortalEffect;
  SmoothFloat mSmoothFlyX;
  SmoothFloat mSmoothFlyY;
  SmoothFloat mSmoothFlyZ;
  bool mWasAutoJumping;
  bool mAutoJumpEnabled;
  float mJumpRidingScale;
  ItemStack mSentOffhandItem;
  ItemStack mSentInventoryItem;
  int mSentSelectedSlot;
  float mPreloadingProgress;
  unsigned __int64 mSessionTickCount;
  Vec3 mStartRidingPosition;
  std::vector<LocalPlayer::RegionListener *> mRegionListeners;
  Vec2 mLookBob;
  Vec2 mOLookBob;
  float mCurrentXa;
  float mCurrentZa;
  bool mDamagedByMobThisFrame;
  bool mLeavingLevel;
  bool mIsTeacher;
  bool mHasBeenInitialized;
  bool mPrevTransitionBlocking;
  InventoryOptions mInventoryOptions;
  ItemInstance mCachedArmor[4];
  std::unordered_set<mce::UUID> mAllSentEmotePieceIds;
  StructureFeatureType mCurrentStructureFeature;
  ItemStack mItemActivationItem;
  int mItemActivationTicks;
  float mItemActivationOffsetX;
  float mItemActivationOffsetY;
  std::unique_ptr<PlayerAutomationObserver> mAutomationObserver;
  Vec2 mTurnDelta;
  Vec3 mLastDelta;
  Vec3 mLastPos;
  NetworkChunkSubscriber mChunkSubscriberView;
  Vec3 mInitPos;
  float mMoveDis;
  float mMaxDisX;
  float mMaxDisY;
  float mMaxDisZ;
  bool mCanButtonJump;
  bool mCanButtonMove;
  bool mCanButtonToggleWalkMode;
  bool mCanButtonTogglePerspective;
  bool mCanButtonPause;
  bool mCanButtonChat;
  bool mCanButtonScreenShot;
  bool mCanButtonOpenInv;
  bool mCanScreenDrag;
  bool mCanButtonInAir;
  bool mSpeedFovClosed;
  bool mIsAutoTransform;
  int mAutoTransformFlag;
  Vec3 CheckGM;
  bool mChangeRenderByScripts;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLoadIntoDimensionTimeOut;
  std::vector<ChunkPos> mChunksNeededForLoadOffsets;
  PlayerRespawnState mClientRespawnState;
  Vec3 mClientRespawnPotentialPosition;
  int mResetHMDAfterSleepTickDelay;
};

```

### `LevelStorageSource`
```
struct __cppobj LevelStorageSource : Bedrock::EnableNonOwnerReferences
{
  LevelStorageSource_vtbl *__vftable /*VFT*/;
};

```

### `LevelLooseFileStorage`
```
struct __cppobj LevelLooseFileStorage
{
  std::function<std::unique_ptr<PackAccessStrategy> __cdecl(void)> mConstructor;
};

```

### `LevelStorageSource_vtbl`
```
struct /*VFT*/ LevelStorageSource_vtbl
{
  void (__fastcall *~LevelStorageSource)(LevelStorageSource *this);
  const std::string *(__fastcall *getName)(LevelStorageSource *this);
  Core::Result *(__fastcall *getLevelData)(LevelStorageSource *this, Core::Result *result, const std::string *, LevelData *);
  LevelData *(__fastcall *getLevelData)(LevelStorageSource *this, LevelData *result, const std::string *);
  void (__fastcall *saveLevelData)(LevelStorageSource *this, const std::string *, const LevelData *);
  void (__fastcall *getLevelList)(LevelStorageSource *this, std::vector<Core::PathBuffer<std::string >> *);
  std::unique_ptr<LevelStorage> *(__fastcall *createLevelStorage)(LevelStorageSource *this, std::unique_ptr<LevelStorage> *result, Scheduler *, const std::string *, const ContentIdentity *, const IContentKeyProvider *, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *);
  std::unique_ptr<LevelLooseFileStorage> *(__fastcall *createLevelLooseStorage)(LevelStorageSource *this, std::unique_ptr<LevelLooseFileStorage> *result, const std::string *, const ContentIdentity *, const IContentKeyProvider *);
  bool (__fastcall *isNewLevelIdAcceptable)(LevelStorageSource *this, const std::string *);
  void (__fastcall *deleteLevel)(LevelStorageSource *this, const std::string *);
  void (__fastcall *renameLevel)(LevelStorageSource *this, LevelData *, const Core::Path *, const std::string *);
  bool (__fastcall *renameLevel)(LevelStorageSource *this, const std::string *, const std::string *);
  bool (__fastcall *createBackupCopyOfWorld)(LevelStorageSource *this, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *isConvertible)(LevelStorageSource *this, const std::string *);
  bool (__fastcall *requiresConversion)(LevelStorageSource *this, const std::string *);
  bool (__fastcall *convertLevel)(LevelStorageSource *this, const std::string *, struct ProgressListener *);
  bool (__fastcall *isLevelMarkedForSync)(LevelStorageSource *this, const Core::Path *);
  bool (__fastcall *isLevelPartiallyCopied)(LevelStorageSource *this, const Core::Path *);
  Core::PathBuffer<std::string > *(__fastcall *getLevelDatFoundPath)(LevelStorageSource *this, Core::PathBuffer<std::string > *result, const Core::Path *);
  const Core::PathBuffer<std::string > *(__fastcall *getBasePath)(LevelStorageSource *this, const Core::PathBuffer<std::string > *result);
  const Core::PathBuffer<std::string > *(__fastcall *getPathToLevel)(LevelStorageSource *this, const Core::PathBuffer<std::string > *result, const std::string *);
  const Core::PathBuffer<std::string > *(__fastcall *getPathToLevelInfo)(LevelStorageSource *this, const Core::PathBuffer<std::string > *result, const std::string *, bool);
  bool (__fastcall *isBetaRetailLevel)(LevelStorageSource *this, const std::string *);
};

```

### `LevelLocationObserver`
```
struct __cppobj LevelLocationObserver : Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>
{
};

```

### `LevelLocationObserver_vtbl`
```
struct /*VFT*/ LevelLocationObserver_vtbl
{
  void (__fastcall *~Observer<LevelLocationObserver,Core::SingleThreadedLock>)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onLevelAdded)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelUpdated)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelDeleted)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onStorageChanged)(LevelLocationObserver *this);
};

```

### `LevelListCache`
```
struct __cppobj LevelListCache : Bedrock::Threading::EnableQueueForMainThread
{
  LevelStorageSource *mLevelStorageSource;
  std::unordered_map<std::string,LevelCache> mCachedLevelData;
  std::unordered_map<std::string,LevelSummary> mCachedUnSyncedLevelData;
  bool mDiscoverLevels;
  Core::Subject<LevelLocationObserver,Core::SingleThreadedLock> mSubject;
  std::recursive_mutex mCacheLock;
  std::function<bool __cdecl(void)> mCheckIsSafeToFlushCache;
};

```

### `LevelListCache_vtbl`
```
struct /*VFT*/ LevelListCache_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `LibraryService`
```
struct __cppobj __declspec(align(8)) LibraryService : ServiceClient
{
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  std::string mAcceptLanguage;
  const Core::PathBuffer<std::string > mDefaultCacheLocation;
  std::unordered_map<enum LibraryRequestType,Core::PathBuffer<std::string >> mCacheLocationPerType;
  const std::string mHostUrl;
  std::string mPlatformOverride;
  unsigned int mCacheDurationHours;
};

```

### `LibraryService_vtbl`
```
struct /*VFT*/ LibraryService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `LessonItem_vtbl`
```
struct /*VFT*/ LessonItem_vtbl
{
  void (__fastcall *~LessonItem)(LessonItem *this);
  bool (__fastcall *isValid)(LessonItem *this);
  void (__fastcall *_createImageInfo)(LessonItem *this);
  const ResourceLocation *(__fastcall *_getImageResourceLocation)(LessonItem *this);
};

```

### `LessonItem::ImageInfo`
```
struct __cppobj __declspec(align(8)) LessonItem::ImageInfo
{
  std::string mUrl;
  glm::tvec2<int,0> mDimensions;
  std::shared_ptr<ResourceLocation> mResourceLocation;
  bool mFetching;
};

```

### `LessonItemCache`
```
struct __cppobj LessonItemCache : std::enable_shared_from_this<LessonItemCache>
{
  std::mutex mMutex;
  std::unordered_map<std::string,std::weak_ptr<LessonItem>> mActiveItems;
};

```

### `LayoutComponent`
```
struct __cppobj __declspec(align(8)) LayoutComponent : UIComponent
{
  std::weak_ptr<LayoutVariables> mAllVariables;
  std::array<std::unique_ptr<LayoutVariable>,11> mControlVariables;
  _BYTE mAnchorFrom[1];
  _BYTE mAnchorTo[1];
  ui::LayoutOffset mOffset;
  ui::LayoutOffset mSize;
  ui::LayoutOffset mMinSize;
  ui::LayoutOffset mMaxSize;
  glm::tvec2<float,0> mOffsetDelta;
  glm::tvec2<float,0> mGridDimensions;
  glm::tvec2<float,0> mDragPosition;
  _BYTE mDraggable[1];
  int mPriority;
  __int8 mIsBeingDragged : 1;
  __int8 mContained : 1;
  __int8 mFollowsCursor : 1;
  __int8 mActive : 1;
  __int8 mInheritMaxSiblingWidth : 1;
  __int8 mInheritMaxSiblingHeight : 1;
  __int8 mIsDelayingLayout : 1;
  __int8 mIsInitialized : 1;
};

```

### `LayoutRuleTerm`
```
struct __cppobj LayoutRuleTerm
{
  LayoutRuleTermType mType;
  std::vector<VariableRef> mDependentVariables;
  std::function<float __cdecl(std::vector<VariableRef> const &)> mFunction;
  std::function<float __cdecl(void)> mFactorFunction;
  float mFactor;
  float mConstant;
};

```

### `LayoutRule`
```
struct __cppobj LayoutRule
{
  std::vector<LayoutRuleTerm> mTerms;
};

```

### `LayoutVariable::RuleValue`
```
struct __cppobj LayoutVariable::RuleValue
{
  float mValue;
  LayoutRule mRule;
};

```

### `LayoutVariable::MinMaxRuleValue`
```
struct __cppobj LayoutVariable::MinMaxRuleValue
{
  LayoutVariable::RuleValue mMinValue;
  LayoutVariable::RuleValue mMaxValue;
};

```

### `LayoutVariable`
```
struct __cppobj __declspec(align(8)) LayoutVariable
{
  UIControl *mControl;
  std::vector<VariableRef> mDependsOnMe;
  LayoutVariable::RuleValue mRuleValue;
  std::unique_ptr<LayoutVariable::MinMaxRuleValue> mMinMaxValue;
  LayoutVariableType mType;
  __int8 mIsSatisfied : 1;
  __int8 mIsOverriden : 1;
};

```

### `LayoutComponent_vtbl`
```
struct /*VFT*/ LayoutComponent_vtbl
{
  void (__fastcall *~UIComponent)(UIComponent *this);
  void (__fastcall *OnScreenPop)(UIComponent *this);
  std::unique_ptr<UIComponent> *(__fastcall *clone)(UIComponent *this, std::unique_ptr<UIComponent> *result, UIControl *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, const ScreenEvent *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, VisualTree *, ScreenInputContext *, UIAnimationController *, const ScreenEvent *);
  void (__fastcall *onNotifyChildAdded)(UIComponent *this);
  void (__fastcall *onNotifyChildRemoved)(UIComponent *this);
  void (__fastcall *onRemoved)(UIComponent *this);
  void (__fastcall *onAdded)(UIComponent *this);
  void (__fastcall *onVisibilityChanged)(UIComponent *this, bool);
  void (__fastcall *onEnabledChanged)(UIComponent *this, bool);
  bool (__fastcall *isRenderableComponent)(UIComponent *this);
  bool (__fastcall *onLayoutChange)(UIComponent *this);
  void (__fastcall *reset)(UIComponent *this);
  void (__fastcall *reload)(UIComponent *this, const UIComponent *);
  const std::string *(__fastcall *getTextToSpeechComponentValue)(UIComponent *this);
};

```

### `LayoutVariables::UnsatisfiedVar`
```
struct __cppobj __declspec(align(8)) LayoutVariables::UnsatisfiedVar
{
  VariableRef mVar;
  bool mIsSatisfied;
};

```

### `LayoutVariables`
```
struct __cppobj LayoutVariables
{
  std::vector<PostOperation> mPostOperations;
  std::vector<LayoutVariables::UnsatisfiedVar> mUnsatisfiedVariables;
};

```

### `LayoutManager`
```
struct __cppobj LayoutManager
{
  std::shared_ptr<LayoutVariables> mVariables;
  glm::tvec2<float,0> mSize;
  std::vector<std::weak_ptr<UIControl>> mDelayedLayout;
};

```

### `LocalAuthentication`
```
struct __cppobj LocalAuthentication
{
  PrivateKeyManager mLocalKeys;
  std::unique_ptr<Certificate> mSelfSignedCertificate;
  std::string mSelfSignedId;
};

```

### `LibraryRepository`
```
struct __cppobj LibraryRepository : ResourcePackListener
{
  std::shared_ptr<EducationContentServices> mServices;
  std::function<ResourcePackManager & __cdecl(void)> mGetResourcePackManager;
  std::unordered_map<std::string,EDULibraryCategory> mLibraryCategories;
};

```

### `LibraryRepository_vtbl`
```
struct /*VFT*/ LibraryRepository_vtbl
{
  void (__fastcall *~ResourcePackListener)(ResourcePackListener *this);
  void (__fastcall *onActiveResourcePacksChanged)(ResourcePackListener *this, ResourcePackManager *);
  void (__fastcall *onFullPackStackInvalid)(ResourcePackListener *this);
  void (__fastcall *onBaseGamePackDownloadComplete)(ResourcePackListener *this);
  void (__fastcall *onLanguageSubpacksChanged)(ResourcePackListener *this);
  void (__fastcall *onResourceManagerDestroyed)(ResourcePackListener *this, ResourcePackManager *);
};

```

### `LinearAllocator<FrameRenderObject>`
```
struct __cppobj LinearAllocator<FrameRenderObject>
{
  std::shared_ptr<AllocatorData> mData;
};

```

### `LevelRendererCamera`
```
struct __cppobj LevelRendererCamera : PlayerListener, LevelListener
{
  unsigned __int64 mChunkQueueSize;
  unsigned __int64 mTerrainChunkQueueSize[3][18];
  std::unordered_multimap<HashedString,Actor *> mEntityRenderQueue;
  SortedMeshDrawList mSortedMeshDrawList;
  std::vector<gsl::not_null<BlockActor *>> mBlockEntityRenderQueue;
  std::vector<gsl::not_null<BlockActor *>> mBlockEntityRenderAlphaQueue;
  std::vector<gsl::not_null<BlockActor *>> mBlockEntityShadowQueue;
  std::vector<gsl::not_null<BlockActor *>> mBlockEntityProcessBarRenderQueue;
  mce::MaterialPtr shadowVolumeBack;
  mce::MaterialPtr shadowVolumeFront;
  mce::MaterialPtr shadowOverlayMat;
  mce::MaterialPtr starsMaterial;
  mce::MaterialPtr skyPlaneMaterial;
  mce::MaterialPtr sunMoonMaterial;
  mce::MaterialPtr endSkyMaterial;
  mce::MaterialPtr cloudMaterial;
  mce::MaterialPtr wireframeMaterial;
  mce::MaterialPtr mCubemapMaterial;
  std::vector<mce::TexturePtr> mCubemapTextures;
  mce::ClientTexture mCubemapTexture;
  OverlayTextureMap mOverlayTextureMap;
  _BYTE mActiveOverlayTextureId[4];
  TerrainMaterialVariationManager mTerrainMaterialVariationManager;
  float mDeltaTime;
  float mLastTime;
  float mWaterLevel;
  glm::tvec2<float,0> mFogControl;
  float mFogBrOriginal;
  float mFogBr;
  float mBaseFogEnd;
  float mBaseFogStart;
  FogDistanceSetting mCurrentDistanceFog;
  FogDistanceSetting mLastTargetDistanceFog;
  FogVolumetricDensitySetting mCurrentFogDensity;
  FogVolumetricCoefficientSetting mAirFogCoefficient;
  FogVolumetricCoefficientSetting mWaterFogCoefficient;
  FogVolumetricCoefficientSetting mCloudFogCoefficient;
  bool mFogWasUnderwaterLastCheck;
  bool mFogWasUnderLavaLastCheck;
  bool mFogWasUnderPowderSnowLastCheck;
  bool mBlendFogThisFrame;
  float mBlindnessLevel;
  const float mRenderDistanceCloudFadeOutMultiplier;
  float mRainPosX;
  float mRainPosY;
  float mRainPosZ;
  int mRainPosSamples;
  int mRainSoundTime;
  int mRainCount;
  float mFakeHDR;
  float mAverageBrightness;
  unsigned int mFrameID;
  int mViewAreaDistance;
  float mFarChunksDistance;
  float mRenderDistance;
  float mCullEndDistance;
  const int mMaxInflightChunks;
  std::shared_ptr<GridArea<std::shared_ptr<RenderChunkInstanced> > > mViewArea;
  BlockPos mLastFaceSortPos;
  Vec3 mLastFaceSortDir;
  Vec3 mLastDirtySortPos;
  BlockPos mLastNearbyFaceSortPos;
  LevelRendererCamera::RenderChunkPosBounds mLastFaceSortBounds;
  Vec3 mLastChunkResortPos;
  Vec3 mCameraPos;
  Vec3 mCameraTargetPos;
  std::shared_ptr<mce::Mesh> mCloudsMesh;
  mce::Camera mWorldSpaceCamera;
  Matrix mSunMatrix;
  Matrix mMoonMatrix;
  glm::tvec3<float,0> mSunDirection;
  glm::tvec3<float,0> mMoonDirection;
  std::unique_ptr<Tessellator> mCloudTessellator;
  std::unique_ptr<TextureTessellator> mCloudTextureTessellator;
  Vec3 mLastCloudUpdatePosition;
  unsigned __int8 mLastCloudSide;
  bool mUpdatingClouds;
  std::vector<Actor *> mWaterHoleEntityQueue;
  std::unique_ptr<WeatherRenderer> mWeatherRenderer;
  std::unique_ptr<ChunkRenderObjectCollection> mChunkRenderObjects;
  std::unique_ptr<Bedrock::Threading::AsyncDeferredResultT<void>> mFrameBuilderChunkRenderObjectsReadyEvent;
  bool mCameraUnderWater;
  bool mCameraUnderLiquid;
  bool mCameraUnderPowderSnow;
  bool mCameraUnderLava;
  bool mCameraInRain;
  bool mShowSky;
  Level *mLevel;
  std::unique_ptr<BlockSource> mViewRegion;
  Dimension *mDimension;
  __int16 mCloudHeight;
  LevelRenderer *mLevelRenderer;
  LevelBuilder mLevelBuilder;
  ResourcePackManager *mResourcePackManager;
  mce::TextureGroup *mTextures;
  std::vector<BlockActor *> mTempBlockEntityList;
  std::weak_ptr<cg::ImageBuffer> mCloudsImage;
  std::unique_ptr<LevelRendererCameraProxy> mProxy;
  ParticleRenderData mParticleRenderData;
  long double mLastFrameTimeStart;
  HistoricalFrameTimes mHistoricalFrameTimes;
  bool mRenderOpacityActor;
  mce::Color mUserDefineEmptyColor;
  std::vector<mce::Color> mUserDefineColors;
};

```

### `LevelRendererCommandListInit`
```
struct __cppobj __declspec(align(8)) LevelRendererCommandListInit
{
  mce::ViewportInfo vp;
  glm::tvec4<int,0> scissor;
  mce::Texture *shadowFrameBuffer;
  mce::FrameBufferObject *frameBuffer;
  mce::RenderTargetState renderTargetState;
};

```

### `LevelRenderer`
```
struct __cppobj LevelRenderer : LevelListener, AppPlatformListener
{
  std::unordered_map<AutomaticID<Dimension,int>,std::unique_ptr<RenderChunkCoordinator>,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::unique_ptr<RenderChunkCoordinator> > > > mRenderChunkCoordinators;
  mce::TextureGroup *mTextures;
  std::shared_ptr<mce::Mesh> mShadowCylinder;
  std::shared_ptr<mce::Mesh> mShadowOverlayCube;
  std::shared_ptr<mce::Mesh> mSkyMesh;
  std::shared_ptr<mce::Mesh> mStarsMesh;
  std::shared_ptr<mce::Mesh> mEndSkyMesh;
  std::shared_ptr<mce::Mesh> mSunMesh;
  std::shared_ptr<mce::Mesh> mMoonMesh[8];
  std::shared_ptr<mce::Mesh> mMilkyWayMesh;
  std::shared_ptr<mce::Mesh> mMeteorMesh[8];
  mce::TexturePtr mAtlasTexture;
  mce::TexturePtr mBrightnessTex;
  mce::TexturePtr mSunTex;
  mce::TexturePtr mMilkyWayTex;
  mce::TexturePtr mMeteorTex;
  mce::TexturePtr mMoonTex;
  mce::TexturePtr mEndSkyTex;
  std::vector<mce::TexturePtr> mCrackFrames;
  DebugRenderer mDebugRenderer;
  Tick mTicks;
  BlockActorRenderDispatcher *mBlockEntityRenderDispatcher;
  std::unique_ptr<BlockTessellator> mLocalRenderer;
  std::unique_ptr<ParticleEngine> mParticleEngine;
  std::unique_ptr<ParticleSystemEngine> mParticleSystemEngine;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::unique_ptr<TaskGroup> mSyncTaskGroup;
  GameRenderer *mGameRenderer;
  MinecraftGraphics *mMinecraftGraphics;
  Level *mLevel;
  std::shared_ptr<Options> mOptions;
  IClientInstance *mClientInstance;
  LocalPlayer *mLocalPlayer;
  HolographicPlatform *mHolographicPlatform;
  LevelRendererPlayer mLevelRendererPlayer;
  std::unique_ptr<LevelRendererProxy> mProxy;
  mce::Color mClearBufferColor;
  std::weak_ptr<PlayerRenderView> mPlayerView;
};

```

### `LevelRendererPlayer`
```
struct __cppobj LevelRendererPlayer : LevelRendererCamera
{
  const float WATER_VISION_QUICK_TIME;
  const float WATER_VISION_MAX_TIME;
  const float WATER_VISION_QUICK_PERCENT;
  Vec3 mComfortRenderAdjustment;
  std::unordered_map<BlockPos,unsigned __int64> mRecordSoundMap;
  std::unordered_map<BlockPos,BlockDestructInfo> mDestroyingBlockList;
  long double mLastDestroyRenderTime;
  std::unordered_map<BlockPos,BlockActorDelayedDeletionInfo> mBlockEntityDelayedDeletionList;
  std::vector<BlockPos> mRemoveBlockEntityTempList;
  float fov;
  float oFov;
  float fovOffset;
  float fovOffsetO;
  PlayerRenderingParameters mRenderingParameters;
  float thirdDistance;
  float thirdDistanceO;
  float thirdRotation;
  float thirdRotationO;
  float thirdTilt;
  float thirdTiltO;
  float cameraRoll;
  float cameraRollO;
  float currentCameraDist;
  float prevHeightOffset;
  float mHeightOffsetAdjustment;
  float mUnderwaterVisionTime;
  float mUnderwaterVisionTimePrevious;
  float mUnderwaterVisionClarity;
  float mUnderwaterVisionScale;
  mce::MaterialPtr selectionBlockEntityOverlayMaterial;
  mce::MaterialPtr selectionBlockEntityOverlayColorMaterial;
  mce::MaterialPtr selectionOverlayMaterial;
  mce::MaterialPtr selectionOpaqueMaterial;
  mce::MaterialPtr selectionTwoSidedMaterial;
  mce::MaterialPtr cracksOverlayMaterial;
  mce::MaterialPtr cracksOverlayAlphaTestMaterial;
  mce::MaterialPtr cracksOverlayBlockEntityMaterial;
  mce::MaterialPtr mOutlineSelectionMaterial;
  const SoundMapping *mSounds;
  std::vector<DeferredSound> mDeferredSounds;
  TextureAtlasItem uvBreakBlockItem;
  IClientInstance *mClientInstance;
  LocalPlayer *mLocalPlayer;
  LevelRenderer *mLevelRenderer;
  Bedrock::NonOwnerPointer<SoundPlayerInterface> mSoundPlayer;
  Level *mLevel;
  HolographicPlatform *mHolographicPlatform;
  std::unique_ptr<AmbientSoundController> mAmbientSoundController;
  std::function<float __cdecl(float,float,float)> mEase;
};

```

### `LevelRendererProxyCallbacks`
```
struct __cppobj LevelRendererProxyCallbacks
{
  std::function<RenderChunkCoordinatorProxy * __cdecl(AutomaticID<Dimension,int>)> mGetRenderChunkCoordinator;
  std::function<bool __cdecl(void)> isBuildingRenderChunks;
  std::function<std::shared_ptr<ClientBlockPipeline::SchematicsRepository> __cdecl(void)> getSchematicsRepository;
};

```

### `LevelRendererProxy`
```
struct __cppobj LevelRendererProxy
{
  LevelRendererProxyCallbacks mCallbacks;
};

```

### `LevelCullerBase`
```
struct __cppobj LevelCullerBase
{
  LevelCullerBase_vtbl *__vftable /*VFT*/;
};

```

### `LevelCullerBase_vtbl`
```
struct /*VFT*/ LevelCullerBase_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
};

```

### `LevelBuilder::PositionAndPriority`
```
struct __cppobj LevelBuilder::PositionAndPriority
{
  SubChunkPos mPosition;
  int mPriority;
};

```

### `LevelBuilder`
```
struct __cppobj LevelBuilder
{
  int maxCullingSteps;
  int numDirtyChunks;
  int numDirtyChunksPrevFrame;
  const int mMaxInflightChunks;
  bool bCheckRightCuller;
  bool mEnforceInterlocks;
  FrustumCuller mLeftFrustumCuller;
  FrustumCuller mRightFrustumCuller;
  std::unique_ptr<ChunkVisibilityCache> mChunkVisibilityCache;
  std::shared_ptr<LevelCullerBase> mLevelCuller;
  FrustumCullerType mFrustumCullerType;
  Vec3 mLastCameraPos;
  Vec3 mLastCameraDir;
  Vec3 mLastAreaCenter;
  float mLastFogEnd;
  float mLastSunAngle;
  int mViewAreaSide;
  __int16 mViewAreaHeight;
  PolygonOperatorPool<RenderChunkBuilder> mBuilders;
  PolygonOperatorPool<RenderChunkSorter> mSorters;
  LevelRenderer *mLevelRenderer;
  LevelRendererCamera *mLevelRendererCamera;
  MPMCQueue<SubChunkPos> mRenderChunksToBuild;
  std::vector<SubChunkPos> mRenderChunksToBuildEraseList;
  std::queue<std::shared_ptr<RenderChunkShared>> mRenderChunksToUpload;
  SpinLock mRenderChunksFinishedBuildingSpinLock;
  std::atomic<int> mImmediateChunkInFlightCount;
  std::vector<SubChunkPos> mRenderChunksToQueryForCuller;
  SpinLock mRenderChunksToQueryForCullerLock;
  std::vector<RenderChunkInstanced *> mSortedRenderChunkInstancedList;
  std::vector<LevelBuilder::PositionAndPriority> mSortedList;
  std::vector<SubChunkPos> mRenderChunksVisibleFromCullingPoint;
  std::unordered_set<SubChunkPos> mInterlockedRenderChunksToCheck;
  std::unordered_set<SubChunkPos> mInterlockGraphWalkSet;
  std::vector<SubChunkPos> mInterlockGraphWalkToCheckList;
  std::unordered_set<SubChunkPos> mExtraChunksToDrawUntilNextCull;
  std::vector<SubChunkPos> mExtraChunksToDrawUntilNextCullEraseList;
  unsigned int mLastCullIteration;
  unsigned __int64 mLastNumRenderChunksVisibleFromCullingPoint;
  bool mForceCulling;
  bool mRecullWhenNotBusy;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastTimeRenderChunksBeingBuilt;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mBuilderTask;
  LevelCullerType mLastCullerType;
  std::shared_ptr<RenderChunkSorterSharedInfo> mSharedSortInfo;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mCurrentTime;
};

```

### `LevelRendererCameraProxyCallbacks`
```
struct __cppobj LevelRendererCameraProxyCallbacks
{
  std::function<RenderChunkCoordinatorProxy * __cdecl(AutomaticID<Dimension,int>)> mGetRenderChunkCoordinator;
};

```

### `LevelRendererCameraProxy`
```
struct __cppobj LevelRendererCameraProxy
{
  LevelRendererCameraProxyCallbacks mCallbacks;
};

```

### `LevelRendererCamera_vtbl`
```
struct /*VFT*/ LevelRendererCamera_vtbl
{
  void (__fastcall *~PlayerListener)(PlayerListener *this);
  void (__fastcall *onWillChangeDimension)(PlayerListener *this, Player *);
  void (__fastcall *onDimensionChanged)(PlayerListener *this, Player *);
  void (__fastcall *onPlayerDestruction)(PlayerListener *this, Player *);
  void (__fastcall *addCameraListenerToRenderChunkCoordinator)(LevelRendererCamera *this);
  void (__fastcall *onAppSuspended)(LevelRendererCamera *this);
  void (__fastcall *onAppResumed)(LevelRendererCamera *this);
  void (__fastcall *onDeviceLost)(LevelRendererCamera *this);
  void (__fastcall *onLowMemory)(LevelRendererCamera *this);
  void (__fastcall *tickLevelRendererCamera)(LevelRendererCamera *this);
  void (__fastcall *tickRain)(LevelRendererCamera *this);
  void (__fastcall *callRenderNameTags)(LevelRendererCamera *this, ScreenContext *, const ViewRenderObject *, Font *);
  NameTagRenderObjectCollection *(__fastcall *extractNameTags)(LevelRendererCamera *this, NameTagRenderObjectCollection *result, ScreenContext *);
  void (__fastcall *callRenderCracks)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderObject *);
  CrackRenderObjectCollection *(__fastcall *extractCracks)(LevelRendererCamera *this, CrackRenderObjectCollection *result, ScreenContext *);
  void (__fastcall *renderEntityEffects)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderBlockEntities)(LevelRendererCamera *this, BaseActorRenderContext *, bool);
  void (__fastcall *renderBindEffects)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderFonts)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderHealth)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderData *);
  void (__fastcall *renderProcessBar)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderData *);
  void (__fastcall *renderHolographicCursor)(LevelRendererCamera *this, ScreenContext *);
  void (__fastcall *renderVRHitFlash)(LevelRendererCamera *this, ScreenContext *);
  bool (__fastcall *getForceFog)(LevelRendererCamera *this, const Actor *);
  void (__fastcall *setupFog)(LevelRendererCamera *this, ScreenContext *, const float);
  float (__fastcall *getAmbientBrightness)(LevelRendererCamera *this);
  void (__fastcall *preRenderUpdate)(LevelRendererCamera *this, ScreenContext *, LevelRenderPreRenderUpdateParameters *);
  void (__fastcall *render)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderObject *, IClientInstance *, LevelRendererCommandListInit *);
  void (__fastcall *postRenderUpdate)(LevelRendererCamera *this);
  bool (__fastcall *isPositionTooCloseToCamera)(LevelRendererCamera *this, const Vec3 *);
  void (__fastcall *blockEntityAboutToBeRemoved)(LevelRendererCamera *this, BlockSource *, std::shared_ptr<BlockActor>);
  void (__fastcall *notifyGeoChangedForAffectedEntities)(LevelRendererCamera *this, RenderChunkShared *, unsigned __int8);
  void (__fastcall *queueRenderEntities)(LevelRendererCamera *this, const LevelRenderPreRenderUpdateParameters *);
  const Block *(__fastcall *_getBlockForBlockEnity)(LevelRendererCamera *this, const BlockActor *);
  void (__fastcall *_fetchAdditionalBlockEntities)(LevelRendererCamera *this, std::vector<BlockActor *> *);
  FogDefinition::DistanceSettingType (__fastcall *_getFogDistanceSettingType)(LevelRendererCamera *this);
  FogDefinition::DensitySettingType (__fastcall *_getFogDensitySettingType)(LevelRendererCamera *this);
};

```

### `LevelRendererPlayer_vtbl`
```
struct /*VFT*/ LevelRendererPlayer_vtbl
{
  void (__fastcall *~PlayerListener)(PlayerListener *this);
  void (__fastcall *onWillChangeDimension)(PlayerListener *this, Player *);
  void (__fastcall *onDimensionChanged)(PlayerListener *this, Player *);
  void (__fastcall *onPlayerDestruction)(PlayerListener *this, Player *);
  void (__fastcall *addCameraListenerToRenderChunkCoordinator)(LevelRendererCamera *this);
  void (__fastcall *onAppSuspended)(LevelRendererCamera *this);
  void (__fastcall *onAppResumed)(LevelRendererCamera *this);
  void (__fastcall *onDeviceLost)(LevelRendererCamera *this);
  void (__fastcall *onLowMemory)(LevelRendererCamera *this);
  void (__fastcall *tickLevelRendererCamera)(LevelRendererCamera *this);
  void (__fastcall *tickRain)(LevelRendererCamera *this);
  void (__fastcall *callRenderNameTags)(LevelRendererCamera *this, ScreenContext *, const ViewRenderObject *, Font *);
  NameTagRenderObjectCollection *(__fastcall *extractNameTags)(LevelRendererCamera *this, NameTagRenderObjectCollection *result, ScreenContext *);
  void (__fastcall *callRenderCracks)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderObject *);
  CrackRenderObjectCollection *(__fastcall *extractCracks)(LevelRendererCamera *this, CrackRenderObjectCollection *result, ScreenContext *);
  void (__fastcall *renderEntityEffects)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderBlockEntities)(LevelRendererCamera *this, BaseActorRenderContext *, bool);
  void (__fastcall *renderBindEffects)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderFonts)(LevelRendererCamera *this, BaseActorRenderContext *);
  void (__fastcall *renderHealth)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderData *);
  void (__fastcall *renderProcessBar)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderData *);
  void (__fastcall *renderHolographicCursor)(LevelRendererCamera *this, ScreenContext *);
  void (__fastcall *renderVRHitFlash)(LevelRendererCamera *this, ScreenContext *);
  bool (__fastcall *getForceFog)(LevelRendererCamera *this, const Actor *);
  void (__fastcall *setupFog)(LevelRendererCamera *this, ScreenContext *, const float);
  float (__fastcall *getAmbientBrightness)(LevelRendererCamera *this);
  void (__fastcall *preRenderUpdate)(LevelRendererCamera *this, ScreenContext *, LevelRenderPreRenderUpdateParameters *);
  void (__fastcall *render)(LevelRendererCamera *this, BaseActorRenderContext *, const ViewRenderObject *, IClientInstance *, LevelRendererCommandListInit *);
  void (__fastcall *postRenderUpdate)(LevelRendererCamera *this);
  bool (__fastcall *isPositionTooCloseToCamera)(LevelRendererCamera *this, const Vec3 *);
  void (__fastcall *blockEntityAboutToBeRemoved)(LevelRendererCamera *this, BlockSource *, std::shared_ptr<BlockActor>);
  void (__fastcall *notifyGeoChangedForAffectedEntities)(LevelRendererCamera *this, RenderChunkShared *, unsigned __int8);
  void (__fastcall *queueRenderEntities)(LevelRendererCamera *this, const LevelRenderPreRenderUpdateParameters *);
  const Block *(__fastcall *_getBlockForBlockEnity)(LevelRendererCamera *this, const BlockActor *);
  void (__fastcall *_fetchAdditionalBlockEntities)(LevelRendererCamera *this, std::vector<BlockActor *> *);
  FogDefinition::DistanceSettingType (__fastcall *_getFogDistanceSettingType)(LevelRendererCamera *this);
  FogDefinition::DensitySettingType (__fastcall *_getFogDensitySettingType)(LevelRendererCamera *this);
  float (__fastcall *getUnderwaterVisionClarity)(LevelRendererPlayer *this);
};

```

### `LessonActionData`
```
const struct __cppobj LessonActionData
{
  _BYTE lessonAction[1];
  std::string source;
};

```

### `LessonProgressionService`
```
struct __cppobj LessonProgressionService : ServiceClient, ILessonProgressionService
{
  const std::string mHostUrl;
  LessonInfo mLessonInfo;
  std::string mUserToken;
};

```

### `LessonProgressionService_vtbl`
```
struct /*VFT*/ LessonProgressionService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `LibraryItemScreenCapabilities`
```
struct __cppobj __declspec(align(8)) LibraryItemScreenCapabilities : TypedScreenCapabilities<LibraryItemScreenCapabilities>
{
  bool mShareLinkIgnored;
};

```

### `LibraryItemScreenCapabilities_vtbl`
```
struct /*VFT*/ LibraryItemScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `LevelLoader`
```
struct __cppobj __declspec(align(8)) LevelLoader : Bedrock::EnableNonOwnerReferences
{
  IMinecraftGame *mMinecraft;
  std::shared_ptr<ImportLevelData> mQueuedImportLoad;
  std::vector<ImportLevelData> mLevelImportQueue;
  std::unique_ptr<LevelSummary> mLevelToLoad;
  std::atomic<bool> mPendingLoadRequest;
  std::string mRealmToLoad;
  std::atomic<bool> mLoadingRealmLink;
};

```

### `LatencyGraphDisplay::Measurement`
```
struct __cppobj LatencyGraphDisplay::Measurement
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimePoint;
  std::chrono::duration<__int64,std::ratio<1,1000> > mLatency;
};

```

### `LatencyGraphDisplay`
```
struct __cppobj LatencyGraphDisplay
{
  NetworkHandler *mNetworkHandler;
  RectangleArea mArea;
  bool mIsInGame;
  std::vector<LatencyGraphDisplay::Measurement> mLatencyMeasurements;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastLatencyUpdate;
};

```

### `LoadingScreen`
```
struct __cppobj LoadingScreen
{
  cg::ImageDescription mLoadingScreenImageDescription;
  float mWaveSeconds;
  long double mLastTimeStamp;
};

```

### `leveldb::Env`
```
struct __cppobj leveldb::Env
{
  leveldb::Env_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::SequentialFile`
```
struct __cppobj leveldb::SequentialFile
{
  leveldb::SequentialFile_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::SequentialFile_vtbl`
```
struct /*VFT*/ leveldb::SequentialFile_vtbl
{
  void (__fastcall *~SequentialFile)(leveldb::SequentialFile *this);
  leveldb::Status *(__fastcall *Read)(leveldb::SequentialFile *this, leveldb::Status *result, unsigned __int64, leveldb::Slice *, char *);
  leveldb::Status *(__fastcall *Skip)(leveldb::SequentialFile *this, leveldb::Status *result, unsigned __int64);
};

```

### `leveldb::RandomAccessFile`
```
struct __cppobj leveldb::RandomAccessFile
{
  leveldb::RandomAccessFile_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::RandomAccessFile_vtbl`
```
struct /*VFT*/ leveldb::RandomAccessFile_vtbl
{
  void (__fastcall *~RandomAccessFile)(leveldb::RandomAccessFile *this);
  leveldb::Status *(__fastcall *Read)(leveldb::RandomAccessFile *this, leveldb::Status *result, unsigned __int64, unsigned __int64, leveldb::Slice *, char *);
};

```

### `leveldb::WritableFile`
```
struct __cppobj leveldb::WritableFile
{
  leveldb::WritableFile_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::WritableFile_vtbl`
```
struct /*VFT*/ leveldb::WritableFile_vtbl
{
  void (__fastcall *~WritableFile)(leveldb::WritableFile *this);
  leveldb::Status *(__fastcall *Append)(leveldb::WritableFile *this, leveldb::Status *result, const leveldb::Slice *);
  leveldb::Status *(__fastcall *Close)(leveldb::WritableFile *this, leveldb::Status *result);
  leveldb::Status *(__fastcall *Flush)(leveldb::WritableFile *this, leveldb::Status *result);
  leveldb::Status *(__fastcall *Sync)(leveldb::WritableFile *this, leveldb::Status *result);
};

```

### `leveldb::FileLock`
```
struct __cppobj leveldb::FileLock
{
  leveldb::FileLock_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::FileLock_vtbl`
```
struct /*VFT*/ leveldb::FileLock_vtbl
{
  void (__fastcall *~FileLock)(leveldb::FileLock *this);
};

```

### `leveldb::Logger_vtbl`
```
struct /*VFT*/ leveldb::Logger_vtbl
{
  void (__fastcall *~Logger)(leveldb::Logger *this);
  void (__fastcall *Logv)(leveldb::Logger *this, const char *, char *);
};

```

### `leveldb::Env_vtbl`
```
struct /*VFT*/ leveldb::Env_vtbl
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

### `leveldb::EnvWrapper`
```
struct __cppobj leveldb::EnvWrapper : leveldb::Env
{
  leveldb::Env *target_;
};

```

### `leveldb::EnvWrapper_vtbl`
```
struct /*VFT*/ leveldb::EnvWrapper_vtbl
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

### `leveldb::Cache`
```
struct __cppobj leveldb::Cache
{
  leveldb::Cache_vtbl *__vftable /*VFT*/;
  struct leveldb::Cache::Rep *rep_;
};

```

### `leveldb::Cache::Handle`
```
struct __cppobj leveldb::Cache::Handle
{
};

```

### `leveldb::Cache_vtbl`
```
struct /*VFT*/ leveldb::Cache_vtbl
{
  void (__fastcall *~Cache)(leveldb::Cache *this);
  leveldb::Cache::Handle *(__fastcall *Insert)(leveldb::Cache *this, const leveldb::Slice *, void *, unsigned __int64, void (__fastcall *)(const leveldb::Slice *, void *));
  leveldb::Cache::Handle *(__fastcall *Lookup)(leveldb::Cache *this, const leveldb::Slice *);
  void (__fastcall *Release)(leveldb::Cache *this, leveldb::Cache::Handle *);
  void *(__fastcall *Value)(leveldb::Cache *this, leveldb::Cache::Handle *);
  void (__fastcall *Erase)(leveldb::Cache *this, const leveldb::Slice *);
  unsigned __int64 (__fastcall *NewId)(leveldb::Cache *this);
  void (__fastcall *Prune)(leveldb::Cache *this);
  unsigned __int64 (__fastcall *TotalCharge)(leveldb::Cache *this);
};

```

### `leveldb::FilterPolicy_vtbl`
```
struct /*VFT*/ leveldb::FilterPolicy_vtbl
{
  void (__fastcall *~FilterPolicy)(leveldb::FilterPolicy *this);
  const char *(__fastcall *Name)(leveldb::FilterPolicy *this);
  void (__fastcall *CreateFilter)(leveldb::FilterPolicy *this, const leveldb::Slice *, int, std::string *);
  bool (__fastcall *KeyMayMatch)(leveldb::FilterPolicy *this, const leveldb::Slice *, const leveldb::Slice *);
};

```

### `leveldb::Compressor_vtbl`
```
struct /*VFT*/ leveldb::Compressor_vtbl
{
  void (__fastcall *~Compressor)(leveldb::Compressor *this);
  void (__fastcall *compressImpl)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
  bool (__fastcall *decompress)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
};

```

### `leveldb::Comparator_vtbl`
```
struct /*VFT*/ leveldb::Comparator_vtbl
{
  void (__fastcall *~Comparator)(leveldb::Comparator *this);
  int (__fastcall *Compare)(leveldb::Comparator *this, const leveldb::Slice *, const leveldb::Slice *);
  const char *(__fastcall *Name)(leveldb::Comparator *this);
  void (__fastcall *FindShortestSeparator)(leveldb::Comparator *this, std::string *, const leveldb::Slice *);
  void (__fastcall *FindShortSuccessor)(leveldb::Comparator *this, std::string *);
};

```

### `leveldb::Snapshot`
```
const struct __cppobj leveldb::Snapshot
{
  leveldb::Snapshot_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::Snapshot_vtbl`
```
struct /*VFT*/ leveldb::Snapshot_vtbl
{
  void (__fastcall *~Snapshot)(leveldb::Snapshot *this);
};

```

### `leveldb::DecompressAllocator`
```
struct __cppobj leveldb::DecompressAllocator
{
  leveldb::DecompressAllocator_vtbl *__vftable /*VFT*/;
  std::mutex mutex;
  std::vector<std::string> stack;
};

```

### `leveldb::DecompressAllocator_vtbl`
```
struct /*VFT*/ leveldb::DecompressAllocator_vtbl
{
  void (__fastcall *~DecompressAllocator)(leveldb::DecompressAllocator *this);
  std::string *(__fastcall *get)(leveldb::DecompressAllocator *this, std::string *result);
  void (__fastcall *release)(leveldb::DecompressAllocator *this, std::string *);
  void (__fastcall *prune)(leveldb::DecompressAllocator *this);
};

```

### `leveldb::WriteOptions`
```
struct __cppobj leveldb::WriteOptions
{
  bool sync;
};

```

### `leveldb::DB`
```
struct __cppobj leveldb::DB
{
  leveldb::DB_vtbl *__vftable /*VFT*/;
};

```

### `leveldb::WriteBatch`
```
struct __cppobj leveldb::WriteBatch
{
  std::string rep_;
};

```

### `leveldb::Iterator`
```
struct __cppobj leveldb::Iterator
{
  leveldb::Iterator_vtbl *__vftable /*VFT*/;
  leveldb::Iterator::Cleanup cleanup_;
};

```

### `leveldb::Iterator_vtbl`
```
struct /*VFT*/ leveldb::Iterator_vtbl
{
  void (__fastcall *~Iterator)(leveldb::Iterator *this);
  bool (__fastcall *Valid)(leveldb::Iterator *this);
  void (__fastcall *SeekToFirst)(leveldb::Iterator *this);
  void (__fastcall *SeekToLast)(leveldb::Iterator *this);
  void (__fastcall *Seek)(leveldb::Iterator *this, const leveldb::Slice *);
  void (__fastcall *Next)(leveldb::Iterator *this);
  void (__fastcall *Prev)(leveldb::Iterator *this);
  leveldb::Slice *(__fastcall *key)(leveldb::Iterator *this, leveldb::Slice *result);
  leveldb::Slice *(__fastcall *value)(leveldb::Iterator *this, leveldb::Slice *result);
  leveldb::Status *(__fastcall *status)(leveldb::Iterator *this, leveldb::Status *result);
};

```

### `leveldb::Iterator::Cleanup`
```
struct leveldb::Iterator::Cleanup
{
  void (__fastcall *function)(void *, void *);
  void *arg1;
  void *arg2;
  leveldb::Iterator::Cleanup *next;
};

```

### `leveldb::Range`
```
const struct __cppobj leveldb::Range
{
  leveldb::Slice start;
  leveldb::Slice limit;
};

```

### `leveldb::DB_vtbl`
```
struct /*VFT*/ leveldb::DB_vtbl
{
  void (__fastcall *~DB)(leveldb::DB *this);
  leveldb::Status *(__fastcall *Put)(leveldb::DB *this, leveldb::Status *result, const leveldb::WriteOptions *, const leveldb::Slice *, const leveldb::Slice *);
  leveldb::Status *(__fastcall *Delete)(leveldb::DB *this, leveldb::Status *result, const leveldb::WriteOptions *, const leveldb::Slice *);
  leveldb::Status *(__fastcall *Write)(leveldb::DB *this, leveldb::Status *result, const leveldb::WriteOptions *, leveldb::WriteBatch *);
  leveldb::Status *(__fastcall *Get)(leveldb::DB *this, leveldb::Status *result, const leveldb::ReadOptions *, const leveldb::Slice *, std::string *);
  leveldb::Iterator *(__fastcall *NewIterator)(leveldb::DB *this, const leveldb::ReadOptions *);
  const leveldb::Snapshot *(__fastcall *GetSnapshot)(leveldb::DB *this);
  void (__fastcall *ReleaseSnapshot)(leveldb::DB *this, const leveldb::Snapshot *);
  bool (__fastcall *GetProperty)(leveldb::DB *this, const leveldb::Slice *, std::string *);
  void (__fastcall *GetApproximateSizes)(leveldb::DB *this, const leveldb::Range *, int, unsigned __int64 *);
  void (__fastcall *CompactRange)(leveldb::DB *this, const leveldb::Slice *, const leveldb::Slice *);
  void (__fastcall *SuspendCompaction)(leveldb::DB *this);
  void (__fastcall *ResumeCompaction)(leveldb::DB *this);
};

```

### `ListenerInfo`
```
struct __cppobj ListenerInfo
{
  std::function<void __cdecl(BlockPos const &,unsigned int,Block const &)> mCallback;
  Vec3 mPosition;
  float mRadiusSqr;
};

```

### `LevelChunkGarbageCollector`
```
struct __cppobj LevelChunkGarbageCollector
{
  Dimension *mDimension;
  MPMCQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter> > mLevelChunksToDiscard;
  std::atomic<unsigned __int64> mPendingDeletes;
};

```

### `LootItemFunction`
```
struct __cppobj LootItemFunction
{
  LootItemFunction_vtbl *__vftable /*VFT*/;
  std::vector<std::unique_ptr<LootItemCondition>> mPredicates;
};

```

### `LootPoolEntry`
```
struct __cppobj LootPoolEntry
{
  LootPoolEntry_vtbl *__vftable /*VFT*/;
  int mWeight;
  int mQuality;
  std::vector<std::unique_ptr<LootItemCondition>> mConditions;
  std::unique_ptr<LootPoolEntry> mSubTable;
};

```

### `LootPoolEntry_vtbl`
```
struct /*VFT*/ LootPoolEntry_vtbl
{
  bool (__fastcall *_createItem)(LootPoolEntry *this, std::vector<ItemStack> *, Random *, LootTableContext *);
  void (__fastcall *~LootPoolEntry)(LootPoolEntry *this);
};

```

### `LootItemCondition`
```
struct __cppobj LootItemCondition
{
  LootItemCondition_vtbl *__vftable /*VFT*/;
};

```

### `LootItemCondition_vtbl`
```
struct /*VFT*/ LootItemCondition_vtbl
{
  void (__fastcall *~LootItemCondition)(LootItemCondition *this);
  bool (__fastcall *applies)(LootItemCondition *this, Random *, LootTableContext *);
};

```

### `LootPoolTiers`
```
struct LootPoolTiers
{
  int mRangeForInitialTier;
  int mBonusRolls;
  float mBonusRollChance;
};

```

### `LootPool`
```
struct __cppobj LootPool
{
  std::vector<std::unique_ptr<LootPoolEntry>> mEntries;
  std::vector<std::unique_ptr<LootItemCondition>> mConditions;
  std::unique_ptr<LootPoolTiers> mTiers;
  RandomValueBounds mRolls;
  RandomValueBounds mBonusRolls;
};

```

### `LootTable`
```
const struct __cppobj LootTable
{
  std::string mDir;
  std::vector<std::unique_ptr<LootPool>> mPools;
};

```

### `LootItemFunction_vtbl`
```
struct /*VFT*/ LootItemFunction_vtbl
{
  void (__fastcall *~LootItemFunction)(LootItemFunction *this);
  int (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, LootTableContext *);
  int (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, LootTableContext *);
};

```

### `LegacyStructureSettings`
```
struct __cppobj LegacyStructureSettings
{
  float mIntegrity;
  unsigned int mSeed;
  Projection mProjection;
  Mirror mMirror;
  Rotation mRotation;
  bool mIgnoreStructureBlocks;
  bool mIgnoreJigsawBlocks;
  bool mWaterBelowSeaLevel;
  const Block *mIgnoreBlock;
  ChunkPos mChunkPos;
  BlockPos mRefPos;
  BoundingBox mBoundingBox;
  std::unordered_map<unsigned char,unsigned char> mSwapAuxValues;
  const std::vector<std::unique_ptr<StructurePoolBlockRule>> *mBlockRules;
  const std::vector<std::unique_ptr<StructurePoolBlockTagRule>> *mBlockTagRules;
};

```

### `LevelEventCoordinator`
```
struct __cppobj LevelEventCoordinator : EventCoordinator<LevelEventListener>
{
};

```

### `LevelDataWrapper`
```
struct __cppobj LevelDataWrapper
{
  LevelData *mLevelDataFromLevel;
  LevelData mLevelDataFromDisk;
};

```

### `LootTables`
```
struct __cppobj LootTables
{
  std::unordered_map<std::string,std::unique_ptr<LootTable>> mLootTables;
  std::mutex mLootTableMutex;
};

```

### `Level_vtbl`
```
struct /*VFT*/ Level_vtbl
{
  void (__fastcall *~BlockSourceListener)(BlockSourceListener *this);
  void (__fastcall *onSourceCreated)(BlockSourceListener *this, BlockSource *);
  void (__fastcall *onSourceDestroyed)(BlockSourceListener *this, BlockSource *);
  void (__fastcall *onAreaChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *, const BlockPos *);
  void (__fastcall *onBlockChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *, unsigned int, const Block *, const Block *, int, const ActorBlockSyncMessage *);
  void (__fastcall *onBrightnessChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *);
  void (__fastcall *onBlockEntityChanged)(BlockSourceListener *this, BlockSource *, BlockActor *);
  void (__fastcall *onBlockEntityAboutToBeRemoved)(BlockSourceListener *this, BlockSource *, std::shared_ptr<BlockActor>);
  void (__fastcall *onEntityChanged)(BlockSourceListener *this, BlockSource *, Actor *);
  void (__fastcall *onBlockEvent)(BlockSourceListener *this, BlockSource *, int, int, int, int, int);
  bool (__fastcall *initialize)(Level *this, const std::string *, const LevelSettings *, LevelData *, const std::string *);
  bool (__fastcall *postProcessResources)(Level *this);
  void (__fastcall *startLeaveGame)(Level *this);
  Actor *(__fastcall *addEntity)(Level *this, BlockSource *, std::unique_ptr<Actor>);
  Actor *(__fastcall *addGlobalEntity)(Level *this, BlockSource *, std::unique_ptr<Actor>);
  Actor *(__fastcall *addAutonomousEntity)(Level *this, BlockSource *, std::unique_ptr<Actor>);
  void (__fastcall *addPlayer)(Level *this, std::unique_ptr<Player>);
  std::unique_ptr<Actor> *(__fastcall *takeEntity)(Level *this, std::unique_ptr<Actor> *result, ActorUniqueID);
  std::unique_ptr<Actor> *(__fastcall *borrowEntity)(Level *this, std::unique_ptr<Actor> *result, ActorUniqueID, LevelChunk *);
  const Tick *(__fastcall *getCurrentServerTick)(Level *this, const Tick *result);
  Factory<BaseLightTextureImageBuilder,Level &,Scheduler &> *(__fastcall *getLightTextureImageBuilderFactory)(Level *this);
  const Factory<BaseLightTextureImageBuilder,Level &,Scheduler &> *(__fastcall *getLightTextureImageBuilderFactory)(Level *this);
  void (__fastcall *onPlayerDeath)(Level *this, Player *, const ActorDamageSource *);
  void (__fastcall *tick)(Level *this);
  void (__fastcall *directTickEntities)(Level *this, BlockSource *);
  void (__fastcall *updateSleepingPlayerList)(Level *this);
  void (__fastcall *setDifficulty)(Level *this, Difficulty);
  void (__fastcall *setCommandsEnabled)(Level *this, bool);
  void (__fastcall *setWorldTemplateOptionsUnlocked)(Level *this);
  void (__fastcall *saveAdditionalData)(Level *this);
  LevelEventCoordinator *(__fastcall *getLevelEventCoordinator)(Level *this);
  void (__fastcall *onChunkLoaded)(Level *this, ChunkSource *, LevelChunk *);
  void (__fastcall *queueEntityRemoval)(Level *this, std::unique_ptr<Actor> *, bool);
  void (__fastcall *removeEntityReferences)(Level *this, Actor *, bool);
  void (__fastcall *loadFunctionManager)(Level *this);
  ResourcePackManager *(__fastcall *getClientResourcePackManager)(Level *this);
  ResourcePackManager *(__fastcall *getServerResourcePackManager)(Level *this);
  TradeTables *(__fastcall *getTradeTables)(Level *this);
  void (__fastcall *addEntryToTagCache)(Level *this, const std::string *);
  void (__fastcall *addEntriesToTagCache)(Level *this, const std::vector<std::string>);
  void (__fastcall *dropEntryFromTagCache)(Level *this, const std::string *);
  void (__fastcall *clearTagCache)(Level *this);
  void (__fastcall *decrementTagCache)(Level *this, const std::string *, TagRegistry<IDType<LevelTagIDType>,IDType<LevelTagSetIDType> > *);
  void (__fastcall *incrementTagCache)(Level *this, const std::string *, TagRegistry<IDType<LevelTagIDType>,IDType<LevelTagSetIDType> > *);
  void (__fastcall *runCommand)(Level *this, Command *, CommandOrigin *, CommandOriginSystem);
  void (__fastcall *runCommand)(Level *this, const HashedString *, CommandOrigin *, CommandOriginSystem, const CurrentCmdVersion);
  TagRegistry<IDType<LevelTagIDType>,IDType<LevelTagSetIDType> > *(__fastcall *getTagRegistry)(Level *this);
  bool (__fastcall *canUseSkin)(Level *this, const SerializedSkin *, const NetworkIdentifier *, const mce::UUID *, const std::string *);
  PositionTrackingDB::PositionTrackingDBServer *(__fastcall *getPositionTrackerDBServer)(Level *this);
  void (__fastcall *setFinishedInitializing)(Level *this);
};

```

### `Lockless::WeakAtomic<unsigned __int64>`
```
struct __cppobj Lockless::WeakAtomic<unsigned __int64>
{
  std::atomic<unsigned __int64> mValue;
};

```

### `LegacyClientNetworkHandler`
```
struct __cppobj __declspec(align(8)) LegacyClientNetworkHandler : ClientNetworkHandler, LevelListener
{
  std::unique_ptr<LevelStorage> mCacheStorage;
  Bedrock::NonOwnerPointer<SoundPlayerInterface> mSoundPlayer;
  MultiPlayerLevel *mLevel;
  PacketSender *mPacketSender;
  std::vector<ActorLink> mPendingLinks;
  int mPendingTime;
  std::string mServerIdentifier;
  std::unique_ptr<NetworkChunkInserter> mChunkInsertQueue;
  NetworkIdentifier mServerGuid;
  std::unique_ptr<Certificate> mUserCertificate;
  std::shared_ptr<MPMCQueue<unsigned __int64> > mCacheMisses;
  std::shared_ptr<MPMCQueue<unsigned __int64> > mCacheHits;
  std::unordered_set<unsigned __int64> mBlobKeysNeedingResponse;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNextChunkRequestDrainTime;
  std::queue<std::pair<mce::UUID,SerializedSkin>> mPendingPersonaSkinsToProcess;
  std::queue<std::pair<mce::UUID,SerializedSkin>> mPendingLegacySkinsToProcess;
  std::shared_ptr<bool> mExistanceTracker;
  std::vector<std::pair<mce::UUID,SerializedSkin>> mSkinsCurrentlyProcessing;
  std::unordered_map<mce::UUID,persona::PersonaCharacterHandle> mSessionPersonas;
  unsigned int mSkinsRemainingToProcess;
};

```

### `LevelChunkPhase1Deleter`
```
struct __cppobj LevelChunkPhase1Deleter
{
};

```

### `LevelChunkBlockActorAccessToken`
```
struct __cppobj LevelChunkBlockActorAccessToken
{
};

```

### `LodestoneCompassComponentCalculator`
```
struct __cppobj LodestoneCompassComponentCalculator
{
  CompassSpriteCalculator mSpriteCalculator;
  float mExpiresAtTime;
  bool mTrackOnlyInSameDimension;
  BlockPos mLookFromPos;
  AutomaticID<Dimension,int> mLookFromDimension;
};

```

### `LodestoneCompassSystem`
```
struct __cppobj LodestoneCompassSystem : ITickingSystem
{
  IClientInstance *mClientInstance;
};

```

### `LodestoneCompassSystem_vtbl`
```
struct /*VFT*/ LodestoneCompassSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `LibraryItem_vtbl`
```
struct /*VFT*/ LibraryItem_vtbl
{
  void (__fastcall *~LessonItem)(LessonItem *this);
  bool (__fastcall *isValid)(LessonItem *this);
  void (__fastcall *_createImageInfo)(LessonItem *this);
  const ResourceLocation *(__fastcall *_getImageResourceLocation)(LessonItem *this);
};

```

### `LibraryCollectionConfig`
```
struct __cppobj LibraryCollectionConfig
{
  const WorldTemplateManager *mWorldTemplateManager;
  const std::optional<std::vector<std::string> > mKeywords;
  _BYTE mExcludedDisplayCategories[4];
  _BYTE mCollectionSource[4];
  std::string mChannelName;
};

```

### `LibraryCollection`
```
struct __cppobj LibraryCollection : InstructionalContentCollection, std::enable_shared_from_this<LibraryCollection>
{
  std::shared_ptr<LibraryCollectionConfig> mConfig;
  std::shared_ptr<LibraryItem> mInvalidItem;
};

```

### `LibraryCollection_vtbl`
```
struct /*VFT*/ LibraryCollection_vtbl
{
  void (__fastcall *~InstructionalContentCollection)(InstructionalContentCollection *this);
  void (__fastcall *addItem)(InstructionalContentCollection *this, std::shared_ptr<LessonItem>);
  void (__fastcall *refresh)(InstructionalContentCollection *this);
  void (__fastcall *fetchItems)(InstructionalContentCollection *this);
  void (__fastcall *onItemImported)(InstructionalContentCollection *this, const LessonItem *);
};

```

### `LecternBlockActor`
```
struct __cppobj LecternBlockActor : BlockActor, Container
{
  int mPage;
  int mTotalPages;
  ItemStack mBook;
};

```

### `LecternBlockActor_vtbl`
```
struct /*VFT*/ LecternBlockActor_vtbl
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

### `LoomScreenControllerProxy`
```
struct __cppobj LoomScreenControllerProxy : ScreenControllerProxy
{
  const LoomScreenControllerProxyCallbacks mCallbacks;
};

```

### `LoomScreenControllerProxy_vtbl`
```
struct /*VFT*/ LoomScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `LevelRendererCamera::LevelRendererDebugInformation`
```
struct __cppobj __declspec(align(8)) LevelRendererCamera::LevelRendererDebugInformation
{
  std::vector<FrustumEdges> lastFrusumEdges;
  std::vector<mce::Camera> lastCascadeCameras;
  mce::Camera lastDebugCamera;
  glm::tvec3<float,0> mReferenceForwardVector;
  std::vector<FrustumEdges> frusumEdges;
  std::vector<mce::Camera> cascadeCameras;
  int renderDebugCamera;
};

```

### `LinearAllocator<CrackRenderObject>::rebind<CrackRenderObject>`
```
struct __cppobj LinearAllocator<CrackRenderObject>::rebind<CrackRenderObject>
{
};

```

### `LinearAllocator<CrackRenderObject>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<CrackRenderObject>::rebind<std::_Container_proxy>
{
};

```

### `LinearAllocator<ActorShadowRenderObject>::rebind<ActorShadowRenderObject>`
```
struct __cppobj LinearAllocator<ActorShadowRenderObject>::rebind<ActorShadowRenderObject>
{
};

```

### `LinearAllocator<ActorShadowRenderObject>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<ActorShadowRenderObject>::rebind<std::_Container_proxy>
{
};

```

### `LinearAllocator<ParticleTypeRenderObject>::rebind<ParticleTypeRenderObject>`
```
struct __cppobj LinearAllocator<ParticleTypeRenderObject>::rebind<ParticleTypeRenderObject>
{
};

```

### `LinearAllocator<ParticleTypeRenderObject>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<ParticleTypeRenderObject>::rebind<std::_Container_proxy>
{
};

```

### `LinearAllocator<NameTagRenderObject>::rebind<NameTagRenderObject>`
```
struct __cppobj LinearAllocator<NameTagRenderObject>::rebind<NameTagRenderObject>
{
};

```

### `LinearAllocator<NameTagRenderObject>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<NameTagRenderObject>::rebind<std::_Container_proxy>
{
};

```

### `LinearAllocator<mce::TexturePtr>::rebind<mce::TexturePtr>`
```
struct __cppobj LinearAllocator<mce::TexturePtr>::rebind<mce::TexturePtr>
{
};

```

### `LinearAllocator<mce::TexturePtr>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<mce::TexturePtr>::rebind<std::_Container_proxy>
{
};

```

### `LinearAllocator<ViewRenderObject>::rebind<ViewRenderObject>`
```
struct __cppobj LinearAllocator<ViewRenderObject>::rebind<ViewRenderObject>
{
};

```

### `LinearAllocator<ViewRenderObject>::rebind<std::_Container_proxy>`
```
struct __cppobj LinearAllocator<ViewRenderObject>::rebind<std::_Container_proxy>
{
};

```

### `LIST_ENTRY64`
```
struct LIST_ENTRY64
{
  unsigned __int64 Flink;
  unsigned __int64 Blink;
};

```

### `LIST_ENTRY32`
```
struct LIST_ENTRY32
{
  unsigned int Flink;
  unsigned int Blink;
};

```

### `lconv`
```
struct lconv
{
  char *decimal_point;
  char *thousands_sep;
  char *grouping;
  char *int_curr_symbol;
  char *currency_symbol;
  char *mon_decimal_point;
  char *mon_thousands_sep;
  char *mon_grouping;
  char *positive_sign;
  char *negative_sign;
  char int_frac_digits;
  char frac_digits;
  char p_cs_precedes;
  char p_sep_by_space;
  char n_cs_precedes;
  char n_sep_by_space;
  char p_sign_posn;
  char n_sign_posn;
  wchar_t *_W_decimal_point;
  wchar_t *_W_thousands_sep;
  wchar_t *_W_int_curr_symbol;
  wchar_t *_W_currency_symbol;
  wchar_t *_W_mon_decimal_point;
  wchar_t *_W_mon_thousands_sep;
  wchar_t *_W_positive_sign;
  wchar_t *_W_negative_sign;
};

```

### `linger`
```
struct linger
{
  unsigned __int16 l_onoff;
  unsigned __int16 l_linger;
};

```

### `LiquidOffsetBehavior`
```
struct __cppobj __declspec(align(8)) LiquidOffsetBehavior : CameraBehavior<LiquidOffsetBehavior>
{
  float mHeightOffset;
};

```

### `LiquidOffsetBehavior_vtbl`
```
struct /*VFT*/ LiquidOffsetBehavior_vtbl
{
  void (__fastcall *~ICameraBehavior)(ICameraBehavior *this);
  void (__fastcall *onSetup)(ICameraBehavior *this, IClientInstance *, CameraDirector *);
  void (__fastcall *onStart)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *update)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *handleLookInput)(ICameraBehavior *this, Vec2 *, CameraDirector *);
  void (__fastcall *renderDebug)(ICameraBehavior *this, IClientInstance *, float, CameraDirector *);
  bool (__fastcall *handleCameraSetRot)(ICameraBehavior *this, const Vec2 *, CameraDirector *);
  HashedString *(__fastcall *getId)(ICameraBehavior *this, HashedString *result);
  ICameraBehavior::UpdateOrder (__fastcall *getUpdateOrder)(ICameraBehavior *this);
};

```

### `LookAtBehavior`
```
struct __cppobj LookAtBehavior : CameraBehavior<LookAtBehavior>
{
  RectangleArea mSoftBounds;
  RectangleArea mHardBounds;
  CriticallyDampedSpring<float> mSoftBoundsSmoothingSpring;
  float mAngularVelocity;
};

```

### `LookAtBehavior_vtbl`
```
struct /*VFT*/ LookAtBehavior_vtbl
{
  void (__fastcall *~ICameraBehavior)(ICameraBehavior *this);
  void (__fastcall *onSetup)(ICameraBehavior *this, IClientInstance *, CameraDirector *);
  void (__fastcall *onStart)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *update)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *handleLookInput)(ICameraBehavior *this, Vec2 *, CameraDirector *);
  void (__fastcall *renderDebug)(ICameraBehavior *this, IClientInstance *, float, CameraDirector *);
  bool (__fastcall *handleCameraSetRot)(ICameraBehavior *this, const Vec2 *, CameraDirector *);
  HashedString *(__fastcall *getId)(ICameraBehavior *this, HashedString *result);
  ICameraBehavior::UpdateOrder (__fastcall *getUpdateOrder)(ICameraBehavior *this);
};

```

### `LiquidOffsetBehaviorLoader`
```
struct __cppobj LiquidOffsetBehaviorLoader : CameraBehaviorLoader
{
};

```

### `LiquidOffsetBehaviorLoader_vtbl`
```
struct /*VFT*/ LiquidOffsetBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `LookAtBehaviorLoader`
```
struct __cppobj LookAtBehaviorLoader : CameraBehaviorLoader
{
};

```

### `LookAtBehaviorLoader_vtbl`
```
struct /*VFT*/ LookAtBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `LevelDataOverrideValues`
```
struct __cppobj __declspec(align(8)) LevelDataOverrideValues
{
  std::unordered_map<HashedString,LevelDataValue> mOverrides;
  std::vector<GameRule> mGameRules;
  std::unordered_map<enum AbilitiesIndex,Ability> mAbilities;
  AdventureSettingsOverride mAdventureSettings;
};

```

### `LegacyWorldConversionManager`
```
struct __cppobj LegacyWorldConversionManager
{
  MainMenuScreenModel *mMainMenuScreenModel;
  _BYTE mConversionState[4];
  float mLegacyWorldConversionProgress;
  std::shared_ptr<bool> mExistenceTracker;
  IDlcBatchModel *mDownloadingContent;
};

```

### `Legacy::WorldImporter`
```
struct __cppobj __declspec(align(8)) Legacy::WorldImporter
{
  Legacy::WorldImporter_vtbl *__vftable /*VFT*/;
  std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> > > mImportContext;
  std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> > > mRetrieveContext;
  std::vector<LegacyWorldInfo> mWorldList;
  std::atomic<bool> mFetchInProgress;
  std::mutex mWorldListMutex;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::shared_ptr<Legacy::WorldConverter> mWorldConverter;
  Legacy::WorldConverter::Type mWorldConverterType;
};

```

### `Legacy::WorldImporter_vtbl`
```
struct /*VFT*/ Legacy::WorldImporter_vtbl
{
  void (__fastcall *~WorldImporter)(Legacy::WorldImporter *this);
  void (__fastcall *deleteWorld)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, const std::string *, std::function<void __cdecl(void)>);
  void (__fastcall *_doRetrieve)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> > >);
  void (__fastcall *_doImport)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, const LegacyWorldInfo *, const Core::Path *, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> > >);
};

```

### `Legacy::WorldConverter`
```
struct __cppobj Legacy::WorldConverter
{
  Legacy::WorldConverter_vtbl *__vftable /*VFT*/;
};

```

### `Legacy::WorldConverter_vtbl`
```
struct /*VFT*/ Legacy::WorldConverter_vtbl
{
  void (__fastcall *~WorldConverter)(Legacy::WorldConverter *this);
  std::shared_future<void> *(__fastcall *addBlob)(Legacy::WorldConverter *this, std::shared_future<void> *result, const std::string *, Legacy::WorldConverterBlobType, std::vector<unsigned char> *);
  std::future<Legacy::WorldConversionReport> *(__fastcall *complete)(Legacy::WorldConverter *this, std::future<Legacy::WorldConversionReport> *result);
  void (__fastcall *setEstimatedBlobCount)(Legacy::WorldConverter *this, unsigned __int64);
  void (__fastcall *setBlobNames)(Legacy::WorldConverter *this, const std::vector<std::string> *);
};

```

### `Legacy::WorldProcessRequest`
```
struct __cppobj Legacy::WorldProcessRequest
{
  Legacy::WorldProcessRequest_vtbl *__vftable /*VFT*/;
  std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> mStatusCallback;
  LegacyWorldInfo mWorldInfo;
};

```

### `Legacy::WorldProcessRequest_vtbl`
```
struct /*VFT*/ Legacy::WorldProcessRequest_vtbl
{
  void (__fastcall *~WorldProcessRequest)(Legacy::WorldProcessRequest *this);
  Legacy::WorldProcessingType (__fastcall *getProcessingType)(Legacy::WorldProcessRequest *this);
  Core::PathBuffer<std::string > *(__fastcall *getOutputPath)(Legacy::WorldProcessRequest *this, Core::PathBuffer<std::string > *result);
};

```

### `Legacy::UploadWorldProcessRequest`
```
struct __cppobj Legacy::UploadWorldProcessRequest : Legacy::WorldProcessRequest
{
  std::unordered_map<std::string,std::string> mUserData;
};

```

### `Legacy::UploadWorldProcessRequest_vtbl`
```
struct /*VFT*/ Legacy::UploadWorldProcessRequest_vtbl
{
  void (__fastcall *~WorldProcessRequest)(Legacy::WorldProcessRequest *this);
  Legacy::WorldProcessingType (__fastcall *getProcessingType)(Legacy::WorldProcessRequest *this);
  Core::PathBuffer<std::string > *(__fastcall *getOutputPath)(Legacy::WorldProcessRequest *this, Core::PathBuffer<std::string > *result);
};

```

### `Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *>`
```
struct __cppobj Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *>
{
  std::atomic<SPSCQueue<std::string,512>::Block *> mValue;
};

```

### `LocalNetworkPeer`
```
struct __cppobj LocalNetworkPeer : NetworkPeer
{
  std::weak_ptr<LocalNetworkPeer> mOtherPeer;
  std::unique_ptr<SPSCQueue<std::string,512>> mIncomingData;
};

```

### `LocalNetworkPeer_vtbl`
```
struct /*VFT*/ LocalNetworkPeer_vtbl
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

### `LeaveLevelProgressHandler`
```
struct __cppobj __declspec(align(8)) LeaveLevelProgressHandler : EmptyProgressHandler
{
  std::string mProgressMessage;
  _BYTE mLoadingState[4];
};

```

### `LeaveLevelProgressHandler_vtbl`
```
struct /*VFT*/ LeaveLevelProgressHandler_vtbl
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

### `LibrarySearchQuery`
```
struct __cppobj LibrarySearchQuery
{
  int mSkip;
  std::string mProductId;
  _BYTE mType[1];
  std::optional<std::vector<std::string> > mKeywords;
  std::vector<std::string> mProductIds;
};

```

### `LibraryImageParams`
```
struct __cppobj LibraryImageParams
{
  std::string mContentUrl;
};

```

### `LogSettingsUpdater`
```
struct __cppobj LogSettingsUpdater
{
  LogSettingsUpdater_vtbl *__vftable /*VFT*/;
};

```

### `LogSettingsUpdater_vtbl`
```
struct /*VFT*/ LogSettingsUpdater_vtbl
{
  void (__fastcall *~LogSettingsUpdater)(LogSettingsUpdater *this);
  void (__fastcall *save)(LogSettingsUpdater *this);
  bool (__fastcall *getDevLogAppend)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogAppend)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogFlushImmediate)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogFlushImmediate)(LogSettingsUpdater *this, bool);
  int (__fastcall *getDevLogFlushDelay)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogFlushDelay)(LogSettingsUpdater *this, int);
  bool (__fastcall *getDevLogTimestamp)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogTimestamp)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogTrace)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogTrace)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogArea)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogArea)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogPriority)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogPriority)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogProcessId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogProcessId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogThreadId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogThreadId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogMessageId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogMessageId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogSilentLogging)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogSilentLogging)(LogSettingsUpdater *this, bool);
  std::string *(__fastcall *getDevLogAreaFilterString)(LogSettingsUpdater *this, std::string *result);
  void (__fastcall *setDevLogAreaFilterString)(LogSettingsUpdater *this, const std::string *);
  unsigned int (__fastcall *getDevLogPriorityFilter)(LogSettingsUpdater *this);
  void (__fastcall *toggleDevLogPriorityFilter)(LogSettingsUpdater *this, unsigned int);
};

```

### `LogOptionsUpdater`
```
struct __cppobj LogOptionsUpdater : LogSettingsUpdater
{
  std::shared_ptr<Options> mOptions;
};

```

### `LogOptionsUpdater_vtbl`
```
struct /*VFT*/ LogOptionsUpdater_vtbl
{
  void (__fastcall *~LogSettingsUpdater)(LogSettingsUpdater *this);
  void (__fastcall *save)(LogSettingsUpdater *this);
  bool (__fastcall *getDevLogAppend)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogAppend)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogFlushImmediate)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogFlushImmediate)(LogSettingsUpdater *this, bool);
  int (__fastcall *getDevLogFlushDelay)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogFlushDelay)(LogSettingsUpdater *this, int);
  bool (__fastcall *getDevLogTimestamp)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogTimestamp)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogTrace)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogTrace)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogArea)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogArea)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogPriority)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogPriority)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogProcessId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogProcessId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogThreadId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogThreadId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogMessageId)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogMessageId)(LogSettingsUpdater *this, bool);
  bool (__fastcall *getDevLogSilentLogging)(LogSettingsUpdater *this);
  void (__fastcall *setDevLogSilentLogging)(LogSettingsUpdater *this, bool);
  std::string *(__fastcall *getDevLogAreaFilterString)(LogSettingsUpdater *this, std::string *result);
  void (__fastcall *setDevLogAreaFilterString)(LogSettingsUpdater *this, const std::string *);
  unsigned int (__fastcall *getDevLogPriorityFilter)(LogSettingsUpdater *this);
  void (__fastcall *toggleDevLogPriorityFilter)(LogSettingsUpdater *this, unsigned int);
};

```

### `LoginStateMachine_vtbl`
```
struct /*VFT*/ LoginStateMachine_vtbl
{
  void (__fastcall *~LoginStateMachine)(LoginStateMachine *this);
};

```

### `LaunchScriptStage`
```
struct __cppobj LaunchScriptStage : BaseStage
{
};

```

### `LaunchScriptStage_vtbl`
```
struct /*VFT*/ LaunchScriptStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `LoginFinishStage`
```
struct __cppobj LoginFinishStage : BaseStage
{
};

```

### `LoginFinishStage_vtbl`
```
struct /*VFT*/ LoginFinishStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `LevelDbEnv`
```
struct __cppobj LevelDbEnv : leveldb::Env
{
  std::unique_ptr<TaskGroup> mLevelDBTasks;
};

```

### `LevelDbEnv_vtbl`
```
struct /*VFT*/ LevelDbEnv_vtbl
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

### `LibraryDeeplink`
```
struct __cppobj LibraryDeeplink
{
  std::string itemId;
};

```

### `LibraryDeeplinkListener`
```
struct __cppobj LibraryDeeplinkListener : UriListener
{
  std::function<SceneStack & __cdecl(void)> mGetSceneStack;
  std::function<SceneFactory & __cdecl(void)> mGetPrimarySceneFactory;
  std::function<LibraryRepository & __cdecl(void)> mGetLibraryRepository;
  std::function<void __cdecl(void)> mRequestLeaveGame;
  std::function<bool __cdecl(void)> mIsLeavingGameDone;
  std::function<bool __cdecl(void)> mIsInGame;
  std::unique_ptr<LibraryDeeplink> mPendingLink;
  std::mutex mLinkMutex;
  std::shared_ptr<bool> mExistenceTracker;
  std::unique_ptr<LibraryDeeplink> mLeaveGamePendingLink;
};

```

### `LibraryDeeplinkListener_vtbl`
```
struct /*VFT*/ LibraryDeeplinkListener_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `LowMemoryWatcher`
```
struct __cppobj LowMemoryWatcher
{
};

```

### `LevelLoader::_importLevel::__l19::<lambda_3bb3ecb6e11687a565c90fd72d569076>`
```
struct __cppobj LevelLoader::_importLevel::__l19::<lambda_3bb3ecb6e11687a565c90fd72d569076>
{
  LevelLoader *const __this;
  std::shared_ptr<ImportLevelData> modalOwnership;
};

```

### `LiveHorseRenderer`
```
struct __cppobj LiveHorseRenderer : MinecraftUICustomRenderer
{
};

```

### `LiveHorseRenderer_vtbl`
```
struct /*VFT*/ LiveHorseRenderer_vtbl
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

### `LivePlayerRenderer`
```
struct __cppobj LivePlayerRenderer : MinecraftUICustomRenderer
{
};

```

### `LivePlayerRenderer_vtbl`
```
struct /*VFT*/ LivePlayerRenderer_vtbl
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

### `LibraryProgressHandler`
```
struct __cppobj LibraryProgressHandler : StoreProgressHandler
{
  std::vector<std::pair<std::string,std::string >> mProperties;
};

```

### `LibraryProgressHandler_vtbl`
```
struct /*VFT*/ LibraryProgressHandler_vtbl
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

### `LodestoneCompassItem`
```
struct __cppobj LodestoneCompassItem : Item
{
  int mAtlasWidth;
  int mAtlasHeight;
  TextureUVCoordinateSet mFrames[32];
};

```

### `LodestoneBlockActor`
```
struct __cppobj __declspec(align(8)) LodestoneBlockActor : BlockActor
{
  PositionTrackingId mTrackingDBHandle;
};

```

### `LodestoneBlockActor_vtbl`
```
struct /*VFT*/ LodestoneBlockActor_vtbl
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

### `LegacyOptionsParser`
```
struct __cppobj LegacyOptionsParser
{
  std::unordered_map<enum LegacyOption,std::variant<bool,unsigned char,unsigned int>> mOptions;
  std::unordered_map<enum LegacyStat,std::variant<unsigned int,std::vector<unsigned int> >> mStats;
};

```

### `LibraryTemplatesScreenController`
```
struct __cppobj LibraryTemplatesScreenController : MainMenuScreenController
{
  std::shared_ptr<LibraryCollection> mCollection;
};

```

### `LibraryTemplatesScreenController_vtbl`
```
struct /*VFT*/ LibraryTemplatesScreenController_vtbl
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

### `LateJoinPreGameScreenController`
```
struct __cppobj __declspec(align(8)) LateJoinPreGameScreenController : MinecraftScreenController
{
  std::function<void __cdecl(void)> mUserReadyToJoinCallback;
  bool mIsSigningInToXBL;
  bool mIsUserReady;
  bool mShouldPromptForPlatformConnection;
  bool mShouldCheckPremiumPlatformAccess;
  bool mCheckingPremiumPlatformAccess;
  bool mHasBeenPromptedForXBLSignIn;
  bool mAutoXBLSignInAttempted;
  bool mShowingWarning;
  bool mIsAnimatingTextVisible;
  std::string mAnimatedMessage;
  int mAnimationCount;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastAnimatingTextUpdate;
  std::unique_ptr<PlatformMultiplayerRestrictions> mPlatformMultiplayerRestrictions;
  bool mHasXBLBroadcast;
};

```

### `LateJoinPreGameScreenController_vtbl`
```
struct /*VFT*/ LateJoinPreGameScreenController_vtbl
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

### `LeaveLevelProgressScreenController`
```
struct __cppobj __declspec(align(8)) LeaveLevelProgressScreenController : MinecraftScreenController
{
  bool mInitiated;
  bool mNext;
  bool mForceRenderBelow;
  std::string mCalledFrom;
  __int64 mLastAudioProgressNotificationUpdate;
  const __int64 mProgressMessageInterval;
  std::unique_ptr<ProgressHandler> mProgressHandler;
  std::deque<std::unique_ptr<ProgressHandler>> mProgressHandlerList;
  bool mHasTicked;
  bool mPostInitEventFired;
};

```

### `LeaveLevelProgressScreenController_vtbl`
```
struct /*VFT*/ LeaveLevelProgressScreenController_vtbl
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

### `LibraryInfo::BaseLibraryInfo`
```
struct __cppobj LibraryInfo::BaseLibraryInfo
{
  LibraryInfo::BaseLibraryInfo_vtbl *__vftable /*VFT*/;
  std::string mSectionHeader;
};

```

### `LibraryInfo::BaseLibraryInfo_vtbl`
```
struct /*VFT*/ LibraryInfo::BaseLibraryInfo_vtbl
{
  void (__fastcall *~BaseLibraryInfo)(LibraryInfo::BaseLibraryInfo *this);
  const gsl::basic_string_span<char const ,-1> *(__fastcall *getType)(LibraryInfo::BaseLibraryInfo *this);
};

```

### `LibraryInfo::Expandable`
```
struct __cppobj __declspec(align(8)) LibraryInfo::Expandable : LibraryInfo::BaseLibraryInfo
{
  std::string mBodyText;
  bool mCanExpand;
  bool mExpanded;
};

```

### `LibraryInfo::Expandable_vtbl`
```
struct /*VFT*/ LibraryInfo::Expandable_vtbl
{
  void (__fastcall *~BaseLibraryInfo)(LibraryInfo::BaseLibraryInfo *this);
  const gsl::basic_string_span<char const ,-1> *(__fastcall *getType)(LibraryInfo::BaseLibraryInfo *this);
};

```

### `LibraryItemScreenController`
```
struct __cppobj LibraryItemScreenController : MainMenuScreenController
{
  std::vector<std::unique_ptr<LibraryInfo::BaseLibraryInfo>> mInfoSections;
  std::shared_ptr<LibraryItem> mItem;
  std::shared_ptr<EducationContentManagerScreenController> mEducationContentManagerScreenController;
};

```

### `LibraryItemScreenController_vtbl`
```
struct /*VFT*/ LibraryItemScreenController_vtbl
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

### `LibraryModalScreenController`
```
struct __cppobj LibraryModalScreenController : MinecraftScreenController
{
  std::function<void __cdecl(bool)> mOnModalDismissed;
  LibraryModalScreenType mType;
  std::vector<std::pair<std::string,std::string >> mEventProperties;
};

```

### `LibraryModalScreenController_vtbl`
```
struct /*VFT*/ LibraryModalScreenController_vtbl
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

### `LibraryModalScreenController::_registerBindings::__l2::<lambda_087130434c3e499fd28e1431cd7fab25>`
```
struct __cppobj LibraryModalScreenController::_registerBindings::__l2::<lambda_087130434c3e499fd28e1431cd7fab25>
{
  LibraryModalScreenController *const __this;
};

```

### `LibraryScreenController`
```
struct __cppobj __declspec(align(8)) LibraryScreenController : MainMenuScreenController
{
  std::shared_ptr<LibraryCollection> mLibraryCollection;
  std::string mLibraryTitle;
  std::string mLibraryIcon;
  std::string mLibraryPageDescription;
  LibraryScreenController::ItemType mItemType;
  _BYTE mOptionalFeatures[4];
  LibraryScreenController::ScreenType mScreenType;
  std::string mSearchFilter;
  bool mShowingError;
  bool mShowingWelcome;
};

```

### `LibraryScreenController_vtbl`
```
struct /*VFT*/ LibraryScreenController_vtbl
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

### `LocalWorldUploadScreenController`
```
struct __cppobj LocalWorldUploadScreenController : PlayScreenController
{
  std::string mRealmID;
};

```

### `LocalWorldUploadScreenController_vtbl`
```
struct /*VFT*/ LocalWorldUploadScreenController_vtbl
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

### `LocalWorldUploadScreenController::_displayLockedWorldPopup::__l2::<lambda_fae9e036f6a709420bc784d748119f15>`
```
struct __cppobj __declspec(align(8)) LocalWorldUploadScreenController::_displayLockedWorldPopup::__l2::<lambda_fae9e036f6a709420bc784d748119f15>
{
  std::weak_ptr<LocalWorldUploadScreenController> weakThis;
  int worldIndex;
};

```

### `LocalWorldUploadScreenController::_displayLockedWorldPopup::__l2::<lambda_fae9e036f6a709420bc784d748119f15>::()::__l5::<lambda_42032e03240096d558f0ecd13cc817c1>`
```
struct __cppobj LocalWorldUploadScreenController::_displayLockedWorldPopup::__l2::<lambda_fae9e036f6a709420bc784d748119f15>::()::__l5::<lambda_42032e03240096d558f0ecd13cc817c1>
{
  std::weak_ptr<LocalWorldUploadScreenController> weakThis;
};

```

### `LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_9fcf662c83052d8e55bcccdf4358cecc>`
```
struct __cppobj LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_9fcf662c83052d8e55bcccdf4358cecc>
{
};

```

### `LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_d4b4b7c4a91a0108e2c65e3720de2740>`
```
struct __cppobj LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_d4b4b7c4a91a0108e2c65e3720de2740>
{
};

```

### `LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_becf3e005d1dab992c4902507fb24787>`
```
struct __cppobj LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_becf3e005d1dab992c4902507fb24787>
{
  LocalWorldUploadScreenController *const __this;
};

```

### `LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_becf3e005d1dab992c4902507fb24787>::()::__l11::<lambda_1066b5068e9cdcc2f4dbd9f71796742d>`
```
struct __cppobj LocalWorldUploadScreenController::_registerEventHandlers::__l2::<lambda_becf3e005d1dab992c4902507fb24787>::()::__l11::<lambda_1066b5068e9cdcc2f4dbd9f71796742d>
{
  std::weak_ptr<LocalWorldUploadScreenController> weakThis;
  const int index;
  LocalWorldInfo *localWorldInfo;
};

```

### `LocalWorldUploadScreenController::_upload::__l10::<lambda_2698453db4a1ba74e29f4215bf63a159>`
```
struct __cppobj __declspec(align(8)) LocalWorldUploadScreenController::_upload::__l10::<lambda_2698453db4a1ba74e29f4215bf63a159>
{
  std::weak_ptr<LocalWorldUploadScreenController> weakThis;
  const int worldIndex;
};

```

### `LibraryTemplatesScreenController::{ctor}::__l2::<lambda_29746ef258516070803c1c986989629c>`
```
struct __cppobj LibraryTemplatesScreenController::{ctor}::__l2::<lambda_29746ef258516070803c1c986989629c>
{
};

```

### `LibraryScreenController::_setSortMethod::__l2::<lambda_34cf7c76c65b80e6aef470045b73afd4>`
```
struct __cppobj LibraryScreenController::_setSortMethod::__l2::<lambda_34cf7c76c65b80e6aef470045b73afd4>
{
  LibraryScreenController::SortMode mode;
};

```

### `LibraryScreenController::_showFetchError::__l2::<lambda_526012f7c57d670a5a7e6daa10021cd4>`
```
struct __cppobj LibraryScreenController::_showFetchError::__l2::<lambda_526012f7c57d670a5a7e6daa10021cd4>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerEventHandlers::__l2::<lambda_2e85df82a80b79582bd9ee3c2037830b>`
```
struct __cppobj LibraryScreenController::_registerEventHandlers::__l2::<lambda_2e85df82a80b79582bd9ee3c2037830b>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerEventHandlers::__l2::<lambda_40fe056b894a595bec516c0d262394f0>`
```
struct __cppobj LibraryScreenController::_registerEventHandlers::__l2::<lambda_40fe056b894a595bec516c0d262394f0>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerEventHandlers::__l2::<lambda_4fc5d32bf862a581c7a8305ddb3d645a>`
```
struct __cppobj LibraryScreenController::_registerEventHandlers::__l2::<lambda_4fc5d32bf862a581c7a8305ddb3d645a>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_592aaa9af0f34fa7d316807ced80c51d>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_592aaa9af0f34fa7d316807ced80c51d>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_003322239f7d3b3a0e7dcf32a85acb00>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_003322239f7d3b3a0e7dcf32a85acb00>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_4ca42b3ff47004f759f016fb1d350a8b>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_4ca42b3ff47004f759f016fb1d350a8b>
{
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_1ad56a19b0aaec404015dfe5e71a7b51>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_1ad56a19b0aaec404015dfe5e71a7b51>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_58f7c788d2793cd65ab27620d2b58e14>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_58f7c788d2793cd65ab27620d2b58e14>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_6fc9dddd00491e3231bbb6b94fc16730>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_6fc9dddd00491e3231bbb6b94fc16730>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_faec0e1c485b695748d343d61d26e335>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_faec0e1c485b695748d343d61d26e335>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_a84e6a2879858b01baa1af4dc9cc0d84>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_a84e6a2879858b01baa1af4dc9cc0d84>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_aa3c29a3c9badb697bf403a6eec86020>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_aa3c29a3c9badb697bf403a6eec86020>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_4484ddcd96c40510c135b3d3e8d7c7b4>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_4484ddcd96c40510c135b3d3e8d7c7b4>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::_registerBindings::__l2::<lambda_b45253f217c103c3c281f24a56d9cc7a>`
```
struct __cppobj LibraryScreenController::_registerBindings::__l2::<lambda_b45253f217c103c3c281f24a56d9cc7a>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::{ctor}::__l2::<lambda_e2595befff5f97c37c862491bb6d8dc3>`
```
struct __cppobj LibraryScreenController::{ctor}::__l2::<lambda_e2595befff5f97c37c862491bb6d8dc3>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::{ctor}::__l2::<lambda_d163638d4056721e193208c1ef876d19>`
```
struct __cppobj LibraryScreenController::{ctor}::__l2::<lambda_d163638d4056721e193208c1ef876d19>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::{ctor}::__l2::<lambda_f522437ef474c2023bbd9f7d37663094>`
```
struct __cppobj LibraryScreenController::{ctor}::__l2::<lambda_f522437ef474c2023bbd9f7d37663094>
{
  LibraryScreenController *const __this;
};

```

### `LibraryScreenController::{ctor}::__l2::<lambda_1d96d24b26056472ec708bba1eb67920>`
```
struct __cppobj LibraryScreenController::{ctor}::__l2::<lambda_1d96d24b26056472ec708bba1eb67920>
{
  LibraryScreenController *const __this;
};

```

### `LibraryModalScreenController::_registerEventHandlers::__l2::<lambda_e97a7064925225453990c159c1b5a710>`
```
struct __cppobj LibraryModalScreenController::_registerEventHandlers::__l2::<lambda_e97a7064925225453990c159c1b5a710>
{
  LibraryModalScreenController *const __this;
};

```

### `LibraryModalScreenController::_registerEventHandlers::__l2::<lambda_cc8d376245468c569ce317f69c50021d>`
```
struct __cppobj LibraryModalScreenController::_registerEventHandlers::__l2::<lambda_cc8d376245468c569ce317f69c50021d>
{
  LibraryModalScreenController *const __this;
};

```

### `LibraryItemScreenController::_showDownloadError::__l2::<lambda_b67c97bb12ba6d2617e855b44112162c>`
```
struct __cppobj LibraryItemScreenController::_showDownloadError::__l2::<lambda_b67c97bb12ba6d2617e855b44112162c>
{
};

```

### `LibraryItemScreenController::_registerExpandableEventHandlers::__l2::<lambda_504f1c51c45ed55299e1a8b3b4a5e5a0>`
```
struct __cppobj LibraryItemScreenController::_registerExpandableEventHandlers::__l2::<lambda_504f1c51c45ed55299e1a8b3b4a5e5a0>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_4f0fbf9f691d41dc49368c26c8aab563>`
```
struct __cppobj LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_4f0fbf9f691d41dc49368c26c8aab563>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_835e671893d81523f10198403040902a>`
```
struct __cppobj LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_835e671893d81523f10198403040902a>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_f83a362b4b3275278afdfba6ad8196fd>`
```
struct __cppobj LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_f83a362b4b3275278afdfba6ad8196fd>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_f88d272e9fe6ad4770165d68281bc662>`
```
struct __cppobj LibraryItemScreenController::_registerExpandableBindings::__l2::<lambda_f88d272e9fe6ad4770165d68281bc662>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_03d032e11e2bf2824f88c76f19bce8e1>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_03d032e11e2bf2824f88c76f19bce8e1>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_a055fc0148af0ab9dc3c88d9a503c9ba>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_a055fc0148af0ab9dc3c88d9a503c9ba>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_ad859bdd7a509facab0bc14290af00b8>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_ad859bdd7a509facab0bc14290af00b8>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_0a736d5bacb4799a4171f194f00e16e5>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_0a736d5bacb4799a4171f194f00e16e5>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_423aa8538b7e6a879e79ac94b8908e05>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l5::<lambda_423aa8538b7e6a879e79ac94b8908e05>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_32691a90d1b36a98278bd07c6302b122>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_32691a90d1b36a98278bd07c6302b122>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_fd86b907f8ac3730499ec26fc21d04e1>`
```
struct __cppobj LibraryItemScreenController::_registerEventHandlers::__l2::<lambda_fd86b907f8ac3730499ec26fc21d04e1>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_9fdcb5459b12627cc618fff16a327770>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_9fdcb5459b12627cc618fff16a327770>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_ee6216ed259f203f73f369f52a7fbbcc>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_ee6216ed259f203f73f369f52a7fbbcc>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_b4bc70e6bc72bba158b072b609a3a118>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_b4bc70e6bc72bba158b072b609a3a118>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_89121a3083e353d2c662975b555e8c15>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_89121a3083e353d2c662975b555e8c15>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_6690d83ebe1652ca5dec16da007ac28d>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_6690d83ebe1652ca5dec16da007ac28d>
{
  LibraryItemScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerBindings::__l2::<lambda_69d9433a19f7d10ccb8ee4b8b008d492>`
```
struct __cppobj LibraryItemScreenController::_registerBindings::__l2::<lambda_69d9433a19f7d10ccb8ee4b8b008d492>
{
  LibraryItemScreenController *const __this;
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_7226532f83cfe7721df3c8fb6ebef7a2>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_7226532f83cfe7721df3c8fb6ebef7a2>
{
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_e9b0f1bfeddb77c39a03f871c3ee1a21>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_e9b0f1bfeddb77c39a03f871c3ee1a21>
{
  LeaveLevelProgressScreenController *const __this;
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_3403c299cda5ec0a610db5d55a315bbd>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_3403c299cda5ec0a610db5d55a315bbd>
{
  LeaveLevelProgressScreenController *const __this;
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_72a669de99520c8152738e82da58597f>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_72a669de99520c8152738e82da58597f>
{
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_cbb3e692c34d9e8db877e750b675b2d2>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_cbb3e692c34d9e8db877e750b675b2d2>
{
  LeaveLevelProgressScreenController *const __this;
};

```

### `LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_4780206e4404167244a0a482ba6bb3fc>`
```
struct __cppobj LeaveLevelProgressScreenController::_registerProgressBindings::__l2::<lambda_4780206e4404167244a0a482ba6bb3fc>
{
  LeaveLevelProgressScreenController *const __this;
};

```

### `LateJoinPreGameScreenController::_warnRestrictedPlatformMultiplayer::__l2::<lambda_1be6f90f58b2b81e229f2878164a7de3>`
```
struct __cppobj LateJoinPreGameScreenController::_warnRestrictedPlatformMultiplayer::__l2::<lambda_1be6f90f58b2b81e229f2878164a7de3>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_warnLockedSkin::__l2::<lambda_19391f408f1629e0c8aeeeb8df94d075>`
```
struct __cppobj LateJoinPreGameScreenController::_warnLockedSkin::__l2::<lambda_19391f408f1629e0c8aeeeb8df94d075>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_promptForXBLSignIn::__l5::<lambda_df34f8976fe36144931864476a9d9544>`
```
struct __cppobj LateJoinPreGameScreenController::_promptForXBLSignIn::__l5::<lambda_df34f8976fe36144931864476a9d9544>
{
};

```

### `LateJoinPreGameScreenController::_checkPremiumAccessAndShowUpsell::__l2::<lambda_2760d6c2b2b29a79ae8f23ce45c3a731>::()::__l13::<lambda_fba2d11ecdbb6d3e527c8ed17d1e13c9>`
```
struct __cppobj LateJoinPreGameScreenController::_checkPremiumAccessAndShowUpsell::__l2::<lambda_2760d6c2b2b29a79ae8f23ce45c3a731>::()::__l13::<lambda_fba2d11ecdbb6d3e527c8ed17d1e13c9>
{
  std::function<void __cdecl(bool)> callback;
};

```

### `LateJoinPreGameScreenController::_promptForPlatformConnection::__l5::<lambda_11ededcc0ecdc0e554d02d3f0cad45f0>`
```
struct __cppobj LateJoinPreGameScreenController::_promptForPlatformConnection::__l5::<lambda_11ededcc0ecdc0e554d02d3f0cad45f0>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l24::<lambda_fa7ba01f28dd7b30e619b7a7a3868da8>`
```
struct __cppobj LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l24::<lambda_fa7ba01f28dd7b30e619b7a7a3868da8>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l10::<lambda_3c9f9995d67fce18f2bf3e46bc5b70cf>`
```
struct __cppobj LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l10::<lambda_3c9f9995d67fce18f2bf3e46bc5b70cf>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l8::<lambda_d8c4c23fdf45a0d6db35f16bc1d463da>`
```
struct __cppobj LateJoinPreGameScreenController::_handleUserReadyToJoinGame::__l8::<lambda_d8c4c23fdf45a0d6db35f16bc1d463da>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_tickUserState::__l57::<lambda_119962919777b57b4e564f544aadbe2d>`
```
struct __cppobj LateJoinPreGameScreenController::_tickUserState::__l57::<lambda_119962919777b57b4e564f544aadbe2d>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_tickUserState::__l57::<lambda_1a10213e3c09240800599327c4c141c2>`
```
struct __cppobj LateJoinPreGameScreenController::_tickUserState::__l57::<lambda_1a10213e3c09240800599327c4c141c2>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>`
```
struct __cppobj LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>::()::__l5::<lambda_945543d829378eec2113aad8e7fb2137>`
```
struct __cppobj LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>::()::__l5::<lambda_945543d829378eec2113aad8e7fb2137>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>::()::__l5::<lambda_3fb86b5128e8375f8cefd08fd1a96017>`
```
struct __cppobj LateJoinPreGameScreenController::_tickUserState::__l50::<lambda_5040f9d2caee16f9898a9a6c180a0744>::()::__l5::<lambda_3fb86b5128e8375f8cefd08fd1a96017>
{
  std::weak_ptr<LateJoinPreGameScreenController> weakThis;
};

```

### `LateJoinPreGameScreenController::_registerBindings::__l2::<lambda_5951322b3af1fcd4613a60e8db986b39>`
```
struct __cppobj LateJoinPreGameScreenController::_registerBindings::__l2::<lambda_5951322b3af1fcd4613a60e8db986b39>
{
  LateJoinPreGameScreenController *const __this;
};

```

### `LateJoinPreGameScreenController::_registerBindings::__l2::<lambda_ad0506e389c52452432310d87eea53d1>`
```
struct __cppobj LateJoinPreGameScreenController::_registerBindings::__l2::<lambda_ad0506e389c52452432310d87eea53d1>
{
  LateJoinPreGameScreenController *const __this;
};

```

### `LateJoinPreGameScreenController::_registerEventHandlers::__l2::<lambda_d11fdb5ae823c967517c6f51d11fbe2d>`
```
struct __cppobj LateJoinPreGameScreenController::_registerEventHandlers::__l2::<lambda_d11fdb5ae823c967517c6f51d11fbe2d>
{
  LateJoinPreGameScreenController *const __this;
};

```

### `LibraryItemScreenController::_registerSubControllers::__l2::<lambda_8ae0bfb7c7b89f1a91e50295c6c13497>`
```
struct __cppobj LibraryItemScreenController::_registerSubControllers::__l2::<lambda_8ae0bfb7c7b89f1a91e50295c6c13497>
{
  LibraryItemScreenController *const __this;
};

```

### `LevelContainerManagerModel`
```
struct __cppobj __declspec(align(8)) LevelContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  ActorUniqueID mEntityUniqueID;
  BlockActorType mBlockActorType;
};

```

### `LevelContainerManagerModel_vtbl`
```
struct /*VFT*/ LevelContainerManagerModel_vtbl
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

### `LayoutVariables::invalidateDependencies::__l5::<lambda_e07b7deff4995bf8bd69bba837bd8c55>`
```
struct __cppobj LayoutVariables::invalidateDependencies::__l5::<lambda_e07b7deff4995bf8bd69bba837bd8c55>
{
  LayoutVariables *const __this;
};

```

### `LayoutVariables::invalidate::__l5::<lambda_b407bc94efcada76e00e0c86eee9e18a>`
```
struct __cppobj LayoutVariables::invalidate::__l5::<lambda_b407bc94efcada76e00e0c86eee9e18a>
{
  LayoutVariables *const __this;
};

```

### `LayoutVariable::addPostComputationalNeeds::__l12::<lambda_9681c2640052c89a49869a8acee0ff4e>`
```
struct __cppobj LayoutVariable::addPostComputationalNeeds::__l12::<lambda_9681c2640052c89a49869a8acee0ff4e>
{
  LayoutVariable *const __this;
  VariableRef var;
};

```

### `LayoutVariable::addPostComputationalNeeds::__l8::<lambda_d5f578f60651d527eac6c074ba6fbc90>`
```
struct __cppobj LayoutVariable::addPostComputationalNeeds::__l8::<lambda_d5f578f60651d527eac6c074ba6fbc90>
{
  LayoutVariable *const __this;
  VariableRef var;
};

```

### `LayoutVariable::overrideRenderableLayoutRule::__l2::<lambda_fdcd53cd549c0efcb3113306a5f2b5ff>`
```
struct __cppobj LayoutVariable::overrideRenderableLayoutRule::__l2::<lambda_fdcd53cd549c0efcb3113306a5f2b5ff>
{
  const LayoutVariableType *type;
  float *overrideValue;
  bool *hasOverride;
};

```

### `LayoutRule::addStackPanelItemRemainderSizeTerms::__l2::<lambda_a7a1569b1f1accbf7feb1785883dbd6f>`
```
struct __cppobj __declspec(align(8)) LayoutRule::addStackPanelItemRemainderSizeTerms::__l2::<lambda_a7a1569b1f1accbf7feb1785883dbd6f>
{
  UIControl *parent;
  UIControl *control;
  const LayoutVariableType sizeType;
};

```

### `LayoutManager::_update::__l2::<lambda_14197656028e6e2a39273b46fbee8311>`
```
struct __cppobj LayoutManager::_update::__l2::<lambda_14197656028e6e2a39273b46fbee8311>
{
};

```

### `LayoutRule::addFillGridDimensionTerm::__l2::<lambda_5c4d56ce84a9d367db2a6bbb1aa4ff51>`
```
struct __cppobj __declspec(align(4)) LayoutRule::addFillGridDimensionTerm::__l2::<lambda_5c4d56ce84a9d367db2a6bbb1aa4ff51>
{
  ui::OrientationType rescalingType;
  LayoutVariableType dimensionType;
};

```

### `LayoutRule::addRescalingGridDimensionTerm::__l2::<lambda_e2b9bd49291b78dd9523e89aa06e496e>`
```
struct __cppobj __declspec(align(4)) LayoutRule::addRescalingGridDimensionTerm::__l2::<lambda_e2b9bd49291b78dd9523e89aa06e496e>
{
  std::weak_ptr<UIControl> weakControl;
  ui::OrientationType rescalingType;
  LayoutVariableType dimensionType;
};

```

### `LayoutRule::addGridItemSizeTerms::__l2::<lambda_6805c03e4c85f3b7ce1f7d54eaa2d6c1>`
```
struct __cppobj LayoutRule::addGridItemSizeTerms::__l2::<lambda_6805c03e4c85f3b7ce1f7d54eaa2d6c1>
{
};

```

### `LayoutRule::addGridItemPositionTerms::__l15::<lambda_f27ec7ee38cb33031bbaa23767312977>`
```
struct __cppobj LayoutRule::addGridItemPositionTerms::__l15::<lambda_f27ec7ee38cb33031bbaa23767312977>
{
};

```

### `LayoutRule::addGridItemPositionTerms::__l13::<lambda_f954b369726128e1a26f9745705bfd06>`
```
struct __cppobj LayoutRule::addGridItemPositionTerms::__l13::<lambda_f954b369726128e1a26f9745705bfd06>
{
};

```

### `LayoutRule::addAxisOffsetTerms::__l33::<lambda_50705c4513fadd86996a53c169f1338a>`
```
struct __cppobj LayoutRule::addAxisOffsetTerms::__l33::<lambda_50705c4513fadd86996a53c169f1338a>
{
};

```

### `LayoutRule::addAxisOffsetTerms::__l28::<lambda_91dac979fa969834c8a6db500143ca61>`
```
struct __cppobj LayoutRule::addAxisOffsetTerms::__l28::<lambda_91dac979fa969834c8a6db500143ca61>
{
};

```

### `LeadItem`
```
struct __cppobj LeadItem : Item
{
};

```

### `LeashFenceKnotActor`
```
struct __cppobj LeashFenceKnotActor : HangingActor
{
};

```

### `LeashFenceKnotActor_vtbl`
```
struct /*VFT*/ LeashFenceKnotActor_vtbl
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
  void (__fastcall *setDir)(HangingActor *this, int);
  int (__fastcall *getWidth)(HangingActor *this);
  int (__fastcall *getHeight)(HangingActor *this);
  void (__fastcall *dropItem)(HangingActor *this);
  bool (__fastcall *placeHangingEntity)(HangingActor *this, BlockSource *, int);
  bool (__fastcall *wouldSurvive)(HangingActor *this, BlockSource *);
};

```

### `LegacySkinImporter`
```
struct __cppobj LegacySkinImporter
{
};

```

### `Legacy::ConvertWorldProcessRequest`
```
struct __cppobj Legacy::ConvertWorldProcessRequest : Legacy::WorldProcessRequest
{
  const Core::PathBuffer<std::string > mOutputPath;
};

```

### `Legacy::ConvertWorldProcessRequest_vtbl`
```
struct /*VFT*/ Legacy::ConvertWorldProcessRequest_vtbl
{
  void (__fastcall *~WorldProcessRequest)(Legacy::WorldProcessRequest *this);
  Legacy::WorldProcessingType (__fastcall *getProcessingType)(Legacy::WorldProcessRequest *this);
  Core::PathBuffer<std::string > *(__fastcall *getOutputPath)(Legacy::WorldProcessRequest *this, Core::PathBuffer<std::string > *result);
};

```

### `LegacyWorldConversionManager::tryAcquireMissingDlc::__l13::<lambda_c59ca1f0521e57b0b8cb56bd175b7c0d>`
```
struct __cppobj LegacyWorldConversionManager::tryAcquireMissingDlc::__l13::<lambda_c59ca1f0521e57b0b8cb56bd175b7c0d>
{
  std::function<void __cdecl(bool)> downloadCompleteCallback;
};

```

### `LoginScreenModel`
```
struct __cppobj __declspec(align(2)) LoginScreenModel : MinecraftScreenModel
{
  int _offline_step;
  bool misLocalVerified;
  bool mShowOfflinePanel;
  bool mShowBlockPanel;
};

```

### `LoginScreenModel_vtbl`
```
struct /*VFT*/ LoginScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `LoginScreenController`
```
struct __cppobj LoginScreenController : MinecraftScreenController
{
  std::shared_ptr<LoginScreenModel> mModel;
  std::string strCmd;
};

```

### `LoginScreenController_vtbl`
```
struct /*VFT*/ LoginScreenController_vtbl
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

### `LogoScreenController`
```
struct __cppobj __declspec(align(8)) LogoScreenController : MinecraftScreenController
{
  int mTickCount;
};

```

### `LogoScreenController_vtbl`
```
struct /*VFT*/ LogoScreenController_vtbl
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

### `Legacy::MockWorldConverter`
```
struct __cppobj Legacy::MockWorldConverter : Legacy::WorldConverter
{
  std::vector<std::shared_future<void>> mBlobRequests;
  std::unique_ptr<std::promise<void>> mAddPromise;
  std::unique_ptr<std::promise<Legacy::WorldConversionReport>> mCompletionPromise;
};

```

### `Legacy::MockWorldConverter_vtbl`
```
struct /*VFT*/ Legacy::MockWorldConverter_vtbl
{
  void (__fastcall *~WorldConverter)(Legacy::WorldConverter *this);
  std::shared_future<void> *(__fastcall *addBlob)(Legacy::WorldConverter *this, std::shared_future<void> *result, const std::string *, Legacy::WorldConverterBlobType, std::vector<unsigned char> *);
  std::future<Legacy::WorldConversionReport> *(__fastcall *complete)(Legacy::WorldConverter *this, std::future<Legacy::WorldConversionReport> *result);
  void (__fastcall *setEstimatedBlobCount)(Legacy::WorldConverter *this, unsigned __int64);
  void (__fastcall *setBlobNames)(Legacy::WorldConverter *this, const std::vector<std::string> *);
};

```

### `LegacyOptionsConverterInternal::ControlConversionRule`
```
struct LegacyOptionsConverterInternal::ControlConversionRule
{
  LegacyOption mSourceOption;
  Remapping::ActionEnum mTargetOption;
};

```

### `Legacy::WorldImporterNull`
```
struct __cppobj Legacy::WorldImporterNull : Legacy::WorldImporter
{
};

```

### `Legacy::WorldImporterNull_vtbl`
```
struct /*VFT*/ Legacy::WorldImporterNull_vtbl
{
  void (__fastcall *~WorldImporter)(Legacy::WorldImporter *this);
  void (__fastcall *deleteWorld)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, const std::string *, std::function<void __cdecl(void)>);
  void (__fastcall *_doRetrieve)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> > >);
  void (__fastcall *_doImport)(Legacy::WorldImporter *this, std::shared_ptr<Social::User>, const LegacyWorldInfo *, const Core::Path *, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> > >);
};

```

### `Legacy::MockWorldConverter::addBlob::__l2::<lambda_d798fe43560fed98984479fd716ec9a4>`
```
struct __cppobj Legacy::MockWorldConverter::addBlob::__l2::<lambda_d798fe43560fed98984479fd716ec9a4>
{
  Legacy::MockWorldConverter *const __this;
};

```

### `Legacy::MockWorldConverter::complete::__l2::<lambda_6225b4d1cc004d91aa6f5d2ac62a66a2>`
```
struct __cppobj Legacy::MockWorldConverter::complete::__l2::<lambda_6225b4d1cc004d91aa6f5d2ac62a66a2>
{
  Legacy::MockWorldConverter *const __this;
};

```

### `Legacy::WorldImporterNull::_doRetrieve::__l2::<lambda_5fd84d04f4d9e18dde859c83a7aeea8c>`
```
struct __cppobj Legacy::WorldImporterNull::_doRetrieve::__l2::<lambda_5fd84d04f4d9e18dde859c83a7aeea8c>
{
  std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> > > context;
};

```

### `Legacy::WorldImporter::importWorld::__l2::<lambda_366519f82ad483b9658c695262c21046>::()::__l2::<lambda_029db122c2aba31f880589b4e73532c2>`
```
struct __cppobj __declspec(align(8)) Legacy::WorldImporter::importWorld::__l2::<lambda_366519f82ad483b9658c695262c21046>::()::__l2::<lambda_029db122c2aba31f880589b4e73532c2>
{
  std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> > > context;
  float percentDone;
};

```

### `LegacyOptionsConverterInternal::_negatedBoolSetter::__l2::<lambda_b4747c6076915628af900f4b75083eb0>`
```
struct __cppobj LegacyOptionsConverterInternal::_negatedBoolSetter::__l2::<lambda_b4747c6076915628af900f4b75083eb0>
{
};

```

### `LegacyOptionsConverterInternal::_percentageFloatSetter::__l2::<lambda_e887955fbe7612448a5f2a759da3961f>`
```
struct __cppobj LegacyOptionsConverterInternal::_percentageFloatSetter::__l2::<lambda_e887955fbe7612448a5f2a759da3961f>
{
  bool requiresInputMode;
  const float min;
  const float max;
};

```

### `LegacyOptionsConverterInternal::_inGameSensitivitySetter::__l2::<lambda_72df878e104f4ab4b8d6fe67024baa56>`
```
struct __cppobj LegacyOptionsConverterInternal::_inGameSensitivitySetter::__l2::<lambda_72df878e104f4ab4b8d6fe67024baa56>
{
};

```

### `LegacyOptionsConverterInternal::_makeSplitScreenRecipe::__l2::<lambda_5b304ff6f5a9c619b90fe260b81fee93>`
```
struct __cppobj LegacyOptionsConverterInternal::_makeSplitScreenRecipe::__l2::<lambda_5b304ff6f5a9c619b90fe260b81fee93>
{
};

```

### `LegacyOptionsConverterInternal::_genericOptionSetter::__l2::<lambda_a3c38dbff1e05b52f7304b834d586c65>`
```
struct __cppobj LegacyOptionsConverterInternal::_genericOptionSetter::__l2::<lambda_a3c38dbff1e05b52f7304b834d586c65>
{
  bool isInputModeType;
};

```

### `LibraryRepository::_setBaseCategories::__l5::<lambda_2066f59cd6c06baa6bbdf9824299fff4>`
```
struct __cppobj LibraryRepository::_setBaseCategories::__l5::<lambda_2066f59cd6c06baa6bbdf9824299fff4>
{
};

```

### `LibraryRepository::_setBaseCategories::__l5::<lambda_787f1a273d7eb8bfb0c708bd7f6fefb2>`
```
struct __cppobj LibraryRepository::_setBaseCategories::__l5::<lambda_787f1a273d7eb8bfb0c708bd7f6fefb2>
{
};

```

### `LibraryDeeplinkListener::_popTopRedundantScreensForLink::__l2::<lambda_92e18333a64979893b240d0e28eda47b>`
```
struct __cppobj LibraryDeeplinkListener::_popTopRedundantScreensForLink::__l2::<lambda_92e18333a64979893b240d0e28eda47b>
{
  int *popCount;
  const LibraryDeeplink *link;
};

```

### `LibraryDeeplinkListener::_navigateToLink::__l2::<lambda_c9dd85ac71e71bb44e446e8aa86a665c>`
```
struct __cppobj LibraryDeeplinkListener::_navigateToLink::__l2::<lambda_c9dd85ac71e71bb44e446e8aa86a665c>
{
  std::shared_ptr<SearchResult> searchResult;
};

```

### `LibraryDeeplinkListener::tick::__l10::<lambda_7c8013903e6c620252792920307d3a88>`
```
struct __cppobj LibraryDeeplinkListener::tick::__l10::<lambda_7c8013903e6c620252792920307d3a88>
{
  LibraryDeeplinkListener *const __this;
};

```

### `LevelStorageWriteBatch::PerfContext`
```
struct __cppobj LevelStorageWriteBatch::PerfContext
{
  unsigned __int64 mOperation;
  unsigned __int64 mSize;
  std::string mKey;
  const char *mReason;
};

```

### `LabTableReactionComponent`
```
struct __cppobj LabTableReactionComponent
{
  LabTableReactionComponent_vtbl *__vftable /*VFT*/;
};

```

### `LabTableReaction`
```
struct __cppobj __declspec(align(8)) LabTableReaction
{
  LabTableReaction_vtbl *__vftable /*VFT*/;
  int mLifetime;
  int mMaxLifetime;
  int mStartDelay;
  std::unique_ptr<ItemStack> mResultItem;
  std::unique_ptr<BlockPos> mPos;
  std::unique_ptr<Random> mRandom;
  std::vector<std::unique_ptr<LabTableReactionComponent>> mComponents;
  LabTableReactionType mType;
  bool mIsClientSide;
};

```

### `LabTableReaction_vtbl`
```
struct /*VFT*/ LabTableReaction_vtbl
{
  void (__fastcall *~LabTableReaction)(LabTableReaction *this);
};

```

### `LabTableReactionComponent_vtbl`
```
struct /*VFT*/ LabTableReactionComponent_vtbl
{
  void (__fastcall *~LabTableReactionComponent)(LabTableReactionComponent *this);
  void (__fastcall *_onStart)(LabTableReactionComponent *this, LabTableReaction *, BlockSource *);
  void (__fastcall *_onTick)(LabTableReactionComponent *this, LabTableReaction *, BlockSource *);
  void (__fastcall *_onEnd)(LabTableReactionComponent *this, LabTableReaction *, BlockSource *);
};

```

### `LevelChunkPacketHandler`
```
struct __cppobj __declspec(align(8)) LevelChunkPacketHandler
{
  std::unique_ptr<LevelChunk> mChunk;
  std::shared_ptr<ClientBlobCache::Cache> mCache;
  std::shared_ptr<LevelChunkPacket> mPacket;
  std::shared_ptr<MPMCQueue<unsigned __int64> > mCacheMissesSender;
  std::shared_ptr<MPMCQueue<unsigned __int64> > mCacheHitsSender;
  std::queue<std::vector<std::function<TaskResult __cdecl(void)>>> mSteps;
  std::function<void __cdecl(void)> mMainThreadCallback;
  std::string mCacheBuffer;
  unsigned __int64 mReused;
  const unsigned __int64 mSequenceId;
  unsigned __int64 mDeserializeStepID;
  ReadOnlyBinaryStream mInputStream;
  bool mCacheEnabled;
};

```

### `LegacyClientNetworkHandler::handle::__l5::<lambda_50d3db24a5bec797058b2c78ad99f47c>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l5::<lambda_50d3db24a5bec797058b2c78ad99f47c>
{
  std::shared_ptr<ClientCacheMissResponsePacket> packet;
  std::weak_ptr<ClientBlobCache::Cache> weakCache;
};

```

### `LegacyClientNetworkHandler::handle::__l5::<lambda_e5fb10c013ff0013c5f4f6e683e20f5e>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l5::<lambda_e5fb10c013ff0013c5f4f6e683e20f5e>
{
  std::shared_ptr<LevelChunkPacketHandler> handler;
};

```

### `LegacyClientNetworkHandler::handle::__l8::<lambda_4527d45382e962cb3d399b4de6ee053d>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l8::<lambda_4527d45382e962cb3d399b4de6ee053d>
{
  LegacyClientNetworkHandler *const __this;
  GameType *oldGameType;
  const SetDefaultGameTypePacket *packet;
};

```

### `LegacyClientNetworkHandler::handle::__l30::<lambda_5bbdb8ecc7b00ebae4d53327f056c63c>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l30::<lambda_5bbdb8ecc7b00ebae4d53327f056c63c>
{
  const AnimatePacket *packet;
  Actor **actor;
};

```

### `LegacyClientNetworkHandler::handle::__l8::<lambda_18a1f2295913ecc0708303e695387a34>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l8::<lambda_18a1f2295913ecc0708303e695387a34>
{
  ActorUniqueID actorID;
};

```

### `LegacyClientNetworkHandler::handle::__l2::<lambda_60c978a53a5fe45c288483d97f872bc7>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l2::<lambda_60c978a53a5fe45c288483d97f872bc7>
{
  std::shared_ptr<BlockActorDataPacket> packet;
};

```

### `LegacyClientNetworkHandler::_handleUpdateBlockPacketCommon::__l2::<lambda_0ac3299732fa6b5afee2093497510e87>`
```
struct __cppobj LegacyClientNetworkHandler::_handleUpdateBlockPacketCommon::__l2::<lambda_0ac3299732fa6b5afee2093497510e87>
{
  LegacyClientNetworkHandler *const __this;
  std::shared_ptr<UpdateBlockPacket> packet;
  const ActorBlockSyncMessage *syncMsg;
};

```

### `LegacyClientNetworkHandler::handle::__l16::<lambda_3ce999330be42e727157d222c2549fe1>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l16::<lambda_3ce999330be42e727157d222c2549fe1>
{
  std::unique_ptr<Actor> *actor;
};

```

### `LegacyClientNetworkHandler::handle::__l13::<lambda_6bdbd85477b87c3c976119e6dc58a2c6>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l13::<lambda_6bdbd85477b87c3c976119e6dc58a2c6>
{
  Actor **actorPtr;
};

```

### `LegacyClientNetworkHandler::handle::__l79::<lambda_01023bcc68158513be1b945f962111f7>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l79::<lambda_01023bcc68158513be1b945f962111f7>
{
  Player **newPlayer;
};

```

### `LegacyClientNetworkHandler::handle::__l73::<lambda_2d31bee4ec57d2ac4f70c1fb047a841e>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l73::<lambda_2d31bee4ec57d2ac4f70c1fb047a841e>
{
  Player **newPlayer;
};

```

### `LegacyClientNetworkHandler::handle::__l80::<lambda_bd67e2cdad03d9a8e3ff6597cb9546e0>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l80::<lambda_bd67e2cdad03d9a8e3ff6597cb9546e0>
{
  Actor *e;
  const AddActorPacket *packet;
};

```

### `LegacyClientNetworkHandler::handle::__l14::<lambda_c81464e57e27a752f526241c77eb712d>`
```
struct __cppobj LegacyClientNetworkHandler::handle::__l14::<lambda_c81464e57e27a752f526241c77eb712d>
{
  Actor *e;
};

```

### `LevelChunkPacketHandler::{ctor}::__l2::<lambda_01b139c4196b261d5ccde8d6a94cde0b>`
```
struct __cppobj LevelChunkPacketHandler::{ctor}::__l2::<lambda_01b139c4196b261d5ccde8d6a94cde0b>
{
  LevelChunkPacketHandler *const __this;
};

```

### `LevelChunkPacketHandler::{ctor}::__l5::<lambda_745e17290d2e5fd570c2fbe56c36a69c>`
```
struct __cppobj LevelChunkPacketHandler::{ctor}::__l5::<lambda_745e17290d2e5fd570c2fbe56c36a69c>
{
  LevelChunkPacketHandler *const __this;
};

```

### `LevelChunkPacketHandler::{ctor}::__l25::<lambda_676b75949d35579bbaf125e1c21542f7>`
```
struct __cppobj LevelChunkPacketHandler::{ctor}::__l25::<lambda_676b75949d35579bbaf125e1c21542f7>
{
  LevelChunkPacketHandler *const __this;
  unsigned __int64 i;
};

```

### `LevelChunkPacketHandler::{ctor}::__l2::<lambda_8b9953b041846740f45b6457b5ad7f05>`
```
struct __cppobj LevelChunkPacketHandler::{ctor}::__l2::<lambda_8b9953b041846740f45b6457b5ad7f05>
{
  LevelChunkPacketHandler *const __this;
  Dimension *dimension;
};

```

### `LiquidBlock`
```
struct __cppobj LiquidBlock : BlockLegacy
{
};

```

### `LiquidBlock_vtbl`
```
struct /*VFT*/ LiquidBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `LavaParticle`
```
struct __cppobj __declspec(align(8)) LavaParticle : Particle
{
  float oSize;
};

```

### `LavaParticle_vtbl`
```
struct /*VFT*/ LavaParticle_vtbl
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

### `LevelSoundEventMap`
```
struct __cppobj LevelSoundEventMap
{
};

```

### `loadSkinImage::__l20::<lambda_30762dfb3a744678726a5d657f2e6492>`
```
struct __cppobj loadSkinImage::__l20::<lambda_30762dfb3a744678726a5d657f2e6492>
{
  std::weak_ptr<FileWatcherUpdate> fileWatcherUpdate;
};

```

### `LocalPlayer::changeDimension::__l2::<lambda_a055da54da88576cc7150c596c08db5b>`
```
struct __cppobj LocalPlayer::changeDimension::__l2::<lambda_a055da54da88576cc7150c596c08db5b>
{
  LocalPlayer *const __this;
  AutomaticID<Dimension,int> *fromId;
  AutomaticID<Dimension,int> *toId;
  const ChangeDimensionPacket *packet;
};

```

### `LocalPlayer::_sendClientAuthPlayerActions::__l2::<lambda_6ebef926ab90091319f9af2eb20602f6>`
```
struct __cppobj LocalPlayer::_sendClientAuthPlayerActions::__l2::<lambda_6ebef926ab90091319f9af2eb20602f6>
{
  PacketSender *packetSender;
};

```

### `LocalPlayer::normalTick::__l43::<lambda_1c7c59adf65d7bd18b6fc05fa9067a13>`
```
struct __cppobj LocalPlayer::normalTick::__l43::<lambda_1c7c59adf65d7bd18b6fc05fa9067a13>
{
  const ItemStack *offhandItem;
};

```

### `LocalPlayer::normalTick::__l37::<lambda_412280d90323b2c3367ab255026d5d95>`
```
struct __cppobj LocalPlayer::normalTick::__l37::<lambda_412280d90323b2c3367ab255026d5d95>
{
  const ItemStack *selectedItem;
};

```

### `LocalPlayer::normalTick::__l37::<lambda_f770b27f9a6723b8f794240b0e693940>`
```
struct __cppobj LocalPlayer::normalTick::__l37::<lambda_f770b27f9a6723b8f794240b0e693940>
{
  const ItemStack *selectedItem;
};

```

### `LightningBoltRenderer`
```
struct __cppobj LightningBoltRenderer : ActorRenderer
{
  mce::MaterialPtr mLightningMat;
};

```

### `LightningBoltRenderer_vtbl`
```
struct /*VFT*/ LightningBoltRenderer_vtbl
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

### `LightningBolt`
```
struct __cppobj __declspec(align(4)) LightningBolt : Actor
{
  unsigned int mSeed;
  int mLife;
  int mFlashes;
  bool mCanHurt;
  bool mHasTriedToHurt;
};

```

### `LightningBolt_vtbl`
```
struct /*VFT*/ LightningBolt_vtbl
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
  bool (__fastcall *shouldAlwaysRender)(LightningBolt *this);
};

```

### `LeafBlock`
```
struct __cppobj LeafBlock : BlockLegacy
{
  bool mHasTransparentLeaves;
  bool mHasFastAlphaTest;
  WeakPtr<BlockLegacy> mSapling;
};

```

### `LeafBlock_vtbl`
```
struct /*VFT*/ LeafBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  ItemInstance *(__fastcall *getExtraResourceItem)(LeafBlock *this, ItemInstance *result, const Block *);
};

```

### `LecternRenderer`
```
struct __cppobj LecternRenderer : BlockActorRenderer
{
  mce::TexturePtr mBookTex;
  EnchantingBookModel mBook;
};

```

### `LecternRenderer_vtbl`
```
struct /*VFT*/ LecternRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `LevelCullerCachedBase::ChangeElement`
```
struct LevelCullerCachedBase::ChangeElement
{
  LevelCullerCachedBase::ChangeID mChangeType;
  unsigned __int64 mListIdx;
};

```

### `LevelCullerCachedBase::ResetCullingWorldDimensions`
```
struct __cppobj LevelCullerCachedBase::ResetCullingWorldDimensions
{
  int mViewSideSize;
  DimensionHeightRange mHeightRange;
  int mMaxCullingSteps;
};

```

### `LevelCullerCachedBase`
```
struct __cppobj LevelCullerCachedBase : LevelCullerBase
{
  std::unique_ptr<ChunkVisibilityCache> mChunkVisibilityCache;
  int mChunkViewAreaSide;
  std::optional<DimensionHeightRange> mHeightRange;
  int mMaxCullingSteps;
  ChunkPos mLastCullingChunkPos;
  unsigned __int8 mChunkVisibilityFrameID;
  std::vector<LevelCullerCachedBase::ChangeElement> mChangeList;
  std::vector<SubChunkPos> mApplyInvalidateList;
  std::vector<LevelCullerCachedBase::UpdateChunkData> mApplyUpdatesList;
  std::vector<LevelCullerCachedBase::ResetCullingWorldDimensions> mApplyResetCullingWorldDataList;
  std::vector<Bounds> mChangeValidAreaList;
  Bounds mValidArea;
  SpinLock mApplyChangesSpinLock;
};

```

### `LevelCullerCachedBase_vtbl`
```
struct /*VFT*/ LevelCullerCachedBase_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
};

```

### `LevelCullerDistanceField`
```
struct __cppobj __declspec(align(8)) LevelCullerDistanceField : LevelCullerCachedBase, std::enable_shared_from_this<LevelCullerDistanceField>
{
  std::vector<DistanceFieldCullingStep> mNarrowPhaseHeap;
  SpinLock mRenderChunksVisibleFromCullingPointSpinLock;
  std::vector<SubChunkPos> mRenderChunksVisibleFromCullingPoint[2];
  unsigned __int64 mActiveRenderChunksVisibleList;
  unsigned __int64 mWorldingRenderChunksVisibleList;
  std::atomic<unsigned int> mTasksCount;
  std::atomic<unsigned int> mCullIteration;
  bool mCullNextFrame;
  Vec3 mCullingOrigin;
  ChunkPos mCullingOriginCP;
  DistanceFieldCullingStep mSwapTemp;
  std::atomic<bool> mTaskScheduled;
  Vec3 mCurrentCameraPos;
  Vec3 mCurrentCameraForward;
  Vec3 mNextCameraPos;
  Vec3 mNextCameraForward;
  int mSteps;
  float mTotalTime;
};

```

### `LevelCullerDistanceField_vtbl`
```
struct /*VFT*/ LevelCullerDistanceField_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
  void (__fastcall *_prepareForCulling)(LevelCullerDistanceField *this, LevelRendererCamera *);
  float (__fastcall *_computeLinearDistance)(LevelCullerDistanceField *this, const Vec3 *);
  bool (__fastcall *_doesRenderDistanceApply)(LevelCullerDistanceField *this);
  bool (__fastcall *_checkPositionAgainstBounds)(LevelCullerDistanceField *this, const SubChunkPos *);
  bool (__fastcall *_checkDistanceDelta)(LevelCullerDistanceField *this, float);
};

```

### `LevelCullerDistanceFieldOrthographic`
```
struct __cppobj LevelCullerDistanceFieldOrthographic : LevelCullerDistanceField
{
  Bounds mBounds;
  glm::tvec4<float,0> mSidePlanes[4];
};

```

### `LevelCullerDistanceFieldOrthographic_vtbl`
```
struct /*VFT*/ LevelCullerDistanceFieldOrthographic_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
  void (__fastcall *_prepareForCulling)(LevelCullerDistanceField *this, LevelRendererCamera *);
  float (__fastcall *_computeLinearDistance)(LevelCullerDistanceField *this, const Vec3 *);
  bool (__fastcall *_doesRenderDistanceApply)(LevelCullerDistanceField *this);
  bool (__fastcall *_checkPositionAgainstBounds)(LevelCullerDistanceField *this, const SubChunkPos *);
  bool (__fastcall *_checkDistanceDelta)(LevelCullerDistanceField *this, float);
};

```

### `LevelCullerDistanceFieldPerspective`
```
struct __cppobj LevelCullerDistanceFieldPerspective : LevelCullerDistanceField
{
};

```

### `LevelCullerDistanceFieldPerspective_vtbl`
```
struct /*VFT*/ LevelCullerDistanceFieldPerspective_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
  void (__fastcall *_prepareForCulling)(LevelCullerDistanceField *this, LevelRendererCamera *);
  float (__fastcall *_computeLinearDistance)(LevelCullerDistanceField *this, const Vec3 *);
  bool (__fastcall *_doesRenderDistanceApply)(LevelCullerDistanceField *this);
  bool (__fastcall *_checkPositionAgainstBounds)(LevelCullerDistanceField *this, const SubChunkPos *);
  bool (__fastcall *_checkDistanceDelta)(LevelCullerDistanceField *this, float);
};

```

### `LevelCullerSunShadow`
```
struct __cppobj LevelCullerSunShadow : LevelCullerCachedBase
{
  bool mCullNextFrame;
  SpinLock mRenderChunksVisibleFromCullingPointSpinLock;
  std::vector<SubChunkPos> mRenderChunksVisibleFromCullingPoint[2];
  unsigned __int64 mActiveRenderChunksVisibleList;
  unsigned __int64 mWorldingRenderChunksVisibleList;
  Vec3 mCurrentCameraPos;
  Vec3 mCullingOrigin;
  ChunkPos mCullingOriginCP;
  std::atomic<unsigned int> mCullIteration;
  Bounds mBounds;
  glm::tvec4<float,0> mSidePlanes[4];
  std::atomic<bool> mTaskScheduled;
  std::atomic<unsigned int> mTasksCount;
  Vec3 mNextCameraPos;
};

```

### `LevelCullerSunShadow_vtbl`
```
struct /*VFT*/ LevelCullerSunShadow_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
};

```

### `LevelCullerNone`
```
struct __cppobj LevelCullerNone : LevelCullerBase
{
  std::vector<SubChunkPos> mVisibleSubChunks;
};

```

### `LevelCullerNone_vtbl`
```
struct /*VFT*/ LevelCullerNone_vtbl
{
  void (__fastcall *~LevelCullerBase)(LevelCullerBase *this);
  void (__fastcall *handleCullingDutiesThisUpdate)(LevelCullerBase *this, const Vec3 *, const Vec3 *, LevelRendererCamera *);
  void (__fastcall *triggerCull)(LevelCullerBase *this, bool);
  void (__fastcall *getVisibleSubchunks)(LevelCullerBase *this, std::vector<SubChunkPos> *);
  void (__fastcall *resetCullingWorldDimensions)(LevelCullerBase *this, int, const DimensionHeightRange *, int);
  void (__fastcall *changeValidArea)(LevelCullerBase *this, const Bounds *);
  void (__fastcall *updateChunkData)(LevelCullerBase *this, const RenderChunkShared *);
  bool (__fastcall *isBlockPositionVisible)(LevelCullerBase *this, const BlockPos *);
  void (__fastcall *invalidateChunk)(LevelCullerBase *this, const SubChunkPos *);
  void (__fastcall *setEmpty)(LevelCullerBase *this, const SubChunkPos *, bool);
  bool (__fastcall *isBusy)(LevelCullerBase *this);
  bool (__fastcall *shouldRecullAfterChunkChange)(LevelCullerBase *this, const RenderChunkShared *);
  unsigned int (__fastcall *getCullIteration)(LevelCullerBase *this);
};

```

### `LevelBuilder::scheduleChunkSort::__l2::<lambda_ca9f475f5abe9fd2bd8d315c3e337e8a>`
```
struct __cppobj LevelBuilder::scheduleChunkSort::__l2::<lambda_ca9f475f5abe9fd2bd8d315c3e337e8a>
{
  const std::shared_ptr<RenderChunkInstanced> renderChunkInstanced;
  std::shared_ptr<SortTaskContext> sortTaskContext;
  LevelBuilder *const __this;
};

```

### `LevelBuilder::scheduleChunkSort::__l2::<lambda_0213a46f6c28c89d46d5304ec9dc3af0>`
```
struct __cppobj LevelBuilder::scheduleChunkSort::__l2::<lambda_0213a46f6c28c89d46d5304ec9dc3af0>
{
  const std::shared_ptr<RenderChunkInstanced> renderChunkInstanced;
  std::shared_ptr<SortTaskContext> sortTaskContext;
};

```

### `LevelBuilder::scheduleChunkSort::__l19::<lambda_645c2dfcf2f77d157bab94892f7fdf5b>`
```
struct __cppobj LevelBuilder::scheduleChunkSort::__l19::<lambda_645c2dfcf2f77d157bab94892f7fdf5b>
{
  LevelBuilder *const __this;
};

```

### `LevelBuilder::scheduleChunkBuild::__l11::<lambda_1a475e5ac8540ac7cb31a3455a6528d7>`
```
struct __cppobj LevelBuilder::scheduleChunkBuild::__l11::<lambda_1a475e5ac8540ac7cb31a3455a6528d7>
{
  LevelBuilder *const __this;
};

```

### `LevelBuilder::scheduleChunkBuild::__l2::<lambda_781943cdbadde60e3ecf438faf85c914>`
```
struct __cppobj LevelBuilder::scheduleChunkBuild::__l2::<lambda_781943cdbadde60e3ecf438faf85c914>
{
  LevelBuilder *const __this;
  ClientBlockPipeline::TessellatorContext *pipelineContext;
  BlockSource **region;
};

```

### `LevelBuilder::recreateBuilders::__l13::<lambda_f7e2fe60366fd092cba4f0d948a03be6>`
```
struct __cppobj LevelBuilder::recreateBuilders::__l13::<lambda_f7e2fe60366fd092cba4f0d948a03be6>
{
  LevelBuilder *const __this;
};

```

### `LevelBuilder::recreateBuilders::__l13::<lambda_ea2e2c03424d2e9ca36c3a4505d717b2>`
```
struct __cppobj LevelBuilder::recreateBuilders::__l13::<lambda_ea2e2c03424d2e9ca36c3a4505d717b2>
{
  MinecraftGameplayGraphicsResources *minecraftGameplayGraphicsResources;
  ClientBlockPipeline::TessellatorContext *pipelineContext;
  BlockSource **region;
};

```

### `LevelBuilder::_buildRenderChunks::__l2::<lambda_a08ac9d83425319e6a6e10392713a815>`
```
struct __cppobj LevelBuilder::_buildRenderChunks::__l2::<lambda_a08ac9d83425319e6a6e10392713a815>
{
  LevelBuilder *const __this;
  const Vec3 cameraPos;
  Vec3 cameraForward;
};

```

### `LevelRenderer::takePicture::__l25::<lambda_966f471d8bd52e85682cd189483f4859>`
```
struct __cppobj LevelRenderer::takePicture::__l25::<lambda_966f471d8bd52e85682cd189483f4859>
{
  LevelRenderer *const __this;
};

```

### `LevelRendererCamera::createViewRenderObject::__l2::<lambda_06c0d9ebcdc7bb0d6b8014e75fd06a48>`
```
struct __cppobj LevelRendererCamera::createViewRenderObject::__l2::<lambda_06c0d9ebcdc7bb0d6b8014e75fd06a48>
{
  ScreenContext *screenContext;
  unsigned __int8 *oldScreenContextSubClientId;
};

```

### `LevelRendererCamera::queueChunk::__l14::<lambda_2ad54a24c26a56bab19ead12d48483ee>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l14::<lambda_2ad54a24c26a56bab19ead12d48483ee>
{
};

```

### `LevelRendererCamera::queueChunk::__l14::<lambda_1c7bae9e0e8e75154218cbbb1a06b46f>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l14::<lambda_1c7bae9e0e8e75154218cbbb1a06b46f>
{
};

```

### `LevelRendererCamera::queueChunk::__l14::<lambda_e3ecd698544eea2955d458a6197fb71e>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l14::<lambda_e3ecd698544eea2955d458a6197fb71e>
{
};

```

### `LevelRendererCamera::queueChunk::__l17::<lambda_f80110362d34345c177c11033da0fab1>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l17::<lambda_f80110362d34345c177c11033da0fab1>
{
};

```

### `LevelRendererCamera::queueChunk::__l17::<lambda_a5f77baf381576dd0df113ed6627093f>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l17::<lambda_a5f77baf381576dd0df113ed6627093f>
{
};

```

### `LevelRendererCamera::queueChunk::__l17::<lambda_5f1fe1d401ded85d05fced13872eea5b>`
```
struct __cppobj LevelRendererCamera::queueChunk::__l17::<lambda_5f1fe1d401ded85d05fced13872eea5b>
{
};

```

### `LevelRendererCamera::updateEditViewArea::__l12::<lambda_783b19e5ed4e5307f406058f5c908b18>`
```
struct __cppobj __declspec(align(8)) LevelRendererCamera::updateEditViewArea::__l12::<lambda_783b19e5ed4e5307f406058f5c908b18>
{
  LevelRendererCamera *const __this;
  bool isOrthoCamera;
};

```

### `LevelRendererCamera::render::__l136::<lambda_95f9375e63923262021f4f30b6a3d7f7>`
```
struct __cppobj LevelRendererCamera::render::__l136::<lambda_95f9375e63923262021f4f30b6a3d7f7>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
};

```

### `LevelRendererCamera::render::__l133::<lambda_4764c359c2ec24a8a0939836d0dd3563>`
```
struct __cppobj LevelRendererCamera::render::__l133::<lambda_4764c359c2ec24a8a0939836d0dd3563>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l123::<lambda_9d443ce3f6a4f06289231c5ca55306cc>`
```
struct __cppobj LevelRendererCamera::render::__l123::<lambda_9d443ce3f6a4f06289231c5ca55306cc>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
  FontHandle *fontHandle;
};

```

### `LevelRendererCamera::render::__l117::<lambda_318f9183abd68b382aa93085aacaff59>`
```
struct __cppobj LevelRendererCamera::render::__l117::<lambda_318f9183abd68b382aa93085aacaff59>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l109::<lambda_e354dc0c7e5eadaff08b5d6664232090>`
```
struct __cppobj LevelRendererCamera::render::__l109::<lambda_e354dc0c7e5eadaff08b5d6664232090>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l105::<lambda_4fe7d505b0540ad3ff640da8f3a8c852>`
```
struct __cppobj LevelRendererCamera::render::__l105::<lambda_4fe7d505b0540ad3ff640da8f3a8c852>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l102::<lambda_8eaadf639f8a587c43525cc3ddbd5cc3>`
```
struct __cppobj LevelRendererCamera::render::__l102::<lambda_8eaadf639f8a587c43525cc3ddbd5cc3>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l99::<lambda_b77b8e6ba7ca21f3c605c9c0aa5a50de>`
```
struct __cppobj LevelRendererCamera::render::__l99::<lambda_b77b8e6ba7ca21f3c605c9c0aa5a50de>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l93::<lambda_f3cc7f48a90c411b5548465bf4eb0500>`
```
struct __cppobj LevelRendererCamera::render::__l93::<lambda_f3cc7f48a90c411b5548465bf4eb0500>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l90::<lambda_8ef8c01b7db41447ee8f6790dba84dc2>`
```
struct __cppobj LevelRendererCamera::render::__l90::<lambda_8ef8c01b7db41447ee8f6790dba84dc2>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l86::<lambda_92c4a9c5072df1bf21f23835db0b55b3>`
```
struct __cppobj LevelRendererCamera::render::__l86::<lambda_92c4a9c5072df1bf21f23835db0b55b3>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
};

```

### `LevelRendererCamera::render::__l83::<lambda_570d4a787024f68a608698b74170fdba>`
```
struct __cppobj LevelRendererCamera::render::__l83::<lambda_570d4a787024f68a608698b74170fdba>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l80::<lambda_63d7ae77897f6b7eed49e76ef924ebca>`
```
struct __cppobj LevelRendererCamera::render::__l80::<lambda_63d7ae77897f6b7eed49e76ef924ebca>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l76::<lambda_716be9c58d56683595928c27d77b513c>`
```
struct __cppobj LevelRendererCamera::render::__l76::<lambda_716be9c58d56683595928c27d77b513c>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
};

```

### `LevelRendererCamera::render::__l73::<lambda_d57d135460e5fe98e6080c441bc8e7e1>`
```
struct __cppobj LevelRendererCamera::render::__l73::<lambda_d57d135460e5fe98e6080c441bc8e7e1>
{
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::render::__l67::<lambda_7b9c96c25bd51daa0708c6f6129d6813>`
```
struct __cppobj LevelRendererCamera::render::__l67::<lambda_7b9c96c25bd51daa0708c6f6129d6813>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l2::<lambda_e5cf65af315eee176ad31648f3749adc>`
```
struct __cppobj LevelRendererCamera::render::__l2::<lambda_e5cf65af315eee176ad31648f3749adc>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
};

```

### `LevelRendererCamera::render::__l2::<lambda_528f95f81012b8c94d11f5be3db617db>`
```
struct __cppobj LevelRendererCamera::render::__l2::<lambda_528f95f81012b8c94d11f5be3db617db>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
  const ViewRenderObject *renderObj;
  bool *drawSky;
};

```

### `LevelRendererCamera::render::__l55::<lambda_c69ba69cc2350aedc765efc2f688c073>`
```
struct __cppobj LevelRendererCamera::render::__l55::<lambda_c69ba69cc2350aedc765efc2f688c073>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l51::<lambda_98cf3401a20e8e5843b28a87774a2606>`
```
struct __cppobj LevelRendererCamera::render::__l51::<lambda_98cf3401a20e8e5843b28a87774a2606>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
};

```

### `LevelRendererCamera::render::__l44::<lambda_3a2cf6803c057b1f0eedb96b6c8e35ae>`
```
struct __cppobj LevelRendererCamera::render::__l44::<lambda_3a2cf6803c057b1f0eedb96b6c8e35ae>
{
  LevelRendererCamera *const __this;
  ScreenContext *screenContext;
};

```

### `LevelRendererCamera::render::__l41::<lambda_67ec6388db038753bb187b676b98ee9d>`
```
struct __cppobj LevelRendererCamera::render::__l41::<lambda_67ec6388db038753bb187b676b98ee9d>
{
  LevelRendererCamera *const __this;
  BaseActorRenderContext *baseEntityRenderContext;
  IClientInstance *ci;
  const ViewRenderObject *renderObj;
};

```

### `LevelRendererCamera::updatePerChunkFaceSortState::__l10::<lambda_ad3c5498b074c18dbed9687ee13fd757>`
```
struct __cppobj LevelRendererCamera::updatePerChunkFaceSortState::__l10::<lambda_ad3c5498b074c18dbed9687ee13fd757>
{
  std::shared_ptr<GridArea<std::shared_ptr<RenderChunkInstanced> > > bufferedarea;
};

```

### `LevelRendererCamera::updateViewArea::__l15::<lambda_9e7cacf76a280e28aa6f2804db39f29f>`
```
struct __cppobj __declspec(align(8)) LevelRendererCamera::updateViewArea::__l15::<lambda_9e7cacf76a280e28aa6f2804db39f29f>
{
  LevelRendererCamera *const __this;
  bool isOrthoCamera;
  const Vec3 cameraPos;
  const Vec3 cameraForward;
};

```

### `LevelRendererCamera::tickClouds::__l16::<lambda_c498a643277d80fd7defa07ea47ad7b1>`
```
struct __cppobj __declspec(align(4)) LevelRendererCamera::tickClouds::__l16::<lambda_c498a643277d80fd7defa07ea47ad7b1>
{
  LevelRendererCamera *const __this;
  const Vec3 cloudCenterPos;
  unsigned __int8 cloudSide;
};

```

### `LevelRendererCamera::tickClouds::__l16::<lambda_0fcd12c8aea96aebe4424114849d6276>`
```
struct __cppobj __declspec(align(4)) LevelRendererCamera::tickClouds::__l16::<lambda_0fcd12c8aea96aebe4424114849d6276>
{
  LevelRendererCamera *const __this;
  std::weak_ptr<cg::ImageBuffer> weakCloudsImage;
  const Vec3 cloudCenterPos;
  unsigned __int8 cloudSide;
  const bool tessellateBothSides;
};

```

### `LevelRendererCamera::{ctor}::__l2::<lambda_2b79d398d8ef1477337b0f5b1b355659>`
```
struct __cppobj LevelRendererCamera::{ctor}::__l2::<lambda_2b79d398d8ef1477337b0f5b1b355659>
{
  LevelRendererCamera *const __this;
};

```

### `LevelRenderer::_initPipelineTessellatorResources::__l2::<lambda_9b5a046e70bef75fe559e6f2f6d097f3>`
```
struct __cppobj LevelRenderer::_initPipelineTessellatorResources::__l2::<lambda_9b5a046e70bef75fe559e6f2f6d097f3>
{
  EntityRegistryOwned *registry;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_f701b1f8a7c0d93b2005ab7edabc9284>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_f701b1f8a7c0d93b2005ab7edabc9284>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_335d2fb1dc9014b3677a9cffb46c1dff>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_335d2fb1dc9014b3677a9cffb46c1dff>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_1b526a2d8548c21b383a97342d5ad487>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_1b526a2d8548c21b383a97342d5ad487>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l12::<lambda_9fcbb6855f88afb816127fda2a20d74b>`
```
struct __cppobj __declspec(align(8)) LevelRenderer::frameUpdate::__l12::<lambda_9fcbb6855f88afb816127fda2a20d74b>
{
  Tessellator *tessellator;
  int i;
};

```

### `LevelRenderer::frameUpdate::__l7::<lambda_ea844ceccd1de22890beb07c0e8397bd>`
```
struct __cppobj LevelRenderer::frameUpdate::__l7::<lambda_ea844ceccd1de22890beb07c0e8397bd>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l4::<lambda_f01a01cf11ce104a02ae2020719b2211>`
```
struct __cppobj __declspec(align(8)) LevelRenderer::frameUpdate::__l4::<lambda_f01a01cf11ce104a02ae2020719b2211>
{
  Tessellator *tessellator;
  int i;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_758885b258945a6ca5117dcdf942ff98>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_758885b258945a6ca5117dcdf942ff98>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_0a9ac793f429e4a5f673b4e4d4c70978>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_0a9ac793f429e4a5f673b4e4d4c70978>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_71f033f9b3e4d327aca2e59532492b67>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_71f033f9b3e4d327aca2e59532492b67>
{
  Tessellator *tessellator;
};

```

### `LevelRenderer::frameUpdate::__l2::<lambda_acf188f954ccaf27d95c5bbd57ac08c6>`
```
struct __cppobj LevelRenderer::frameUpdate::__l2::<lambda_acf188f954ccaf27d95c5bbd57ac08c6>
{
  ClientFrameUpdateContext *clientFrameUpdateContext;
};

```

### `LevelRenderer::{ctor}::__l2::<lambda_85bf7fc9e6a1eeb9e971efa9bf3ba2ca>`
```
struct __cppobj LevelRenderer::{ctor}::__l2::<lambda_85bf7fc9e6a1eeb9e971efa9bf3ba2ca>
{
  LevelRenderer *const __this;
};

```

### `LevelRenderer::{ctor}::__l2::<lambda_f4d845fc283e1eef5eaad1dddf1583e3>`
```
struct __cppobj LevelRenderer::{ctor}::__l2::<lambda_f4d845fc283e1eef5eaad1dddf1583e3>
{
  LevelRenderer *const __this;
};

```

### `LevelRenderer::{ctor}::__l2::<lambda_1c42f68ee32956de6883e2d635c9f079>`
```
struct __cppobj LevelRenderer::{ctor}::__l2::<lambda_1c42f68ee32956de6883e2d635c9f079>
{
  LevelRenderer *const __this;
};

```

### `LevelCullerSunShadow::handleCullingDutiesThisUpdate::__l5::<lambda_16329a48841731d4df3946d7f44c0fbf>`
```
struct __cppobj LevelCullerSunShadow::handleCullingDutiesThisUpdate::__l5::<lambda_16329a48841731d4df3946d7f44c0fbf>
{
  LevelCullerSunShadow *const __this;
  LevelRendererCamera *levelRendererCamera;
};

```

### `LevelCullerDistanceField::handleCullingDutiesThisUpdate::__l5::<lambda_fde9076c36ef6dc7b65d1999d984afcb>`
```
struct __cppobj LevelCullerDistanceField::handleCullingDutiesThisUpdate::__l5::<lambda_fde9076c36ef6dc7b65d1999d984afcb>
{
  std::weak_ptr<LevelCullerDistanceField> weakThis;
  LevelRendererCamera *levelRendererCamera;
};

```

### `LevelRendererCamera::setupViewArea::__l2::<lambda_d53e0703952e2c097317ba99365db65e>`
```
struct __cppobj LevelRendererCamera::setupViewArea::__l2::<lambda_d53e0703952e2c097317ba99365db65e>
{
  LevelRendererCamera *const __this;
};

```

### `LessonActionRequest`
```
struct __cppobj __declspec(align(8)) LessonActionRequest : RequestHandler
{
  const LessonProgressionService *mService;
  const std::string mHostUrl;
  LessonInfo mLessonInfo;
  LessonActionData mRequestData;
  std::function<void __cdecl(bool,std::string const &)> mResponseCallback;
  std::string mStatus;
  bool mSuccess;
};

```

### `LessonActionRequest_vtbl`
```
struct /*VFT*/ LessonActionRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `LessonStatusRequest`
```
struct __cppobj LessonStatusRequest : RequestHandler
{
  const LessonProgressionService *mService;
  const std::string mHostUrl;
  LessonInfo mLessonInfo;
  std::function<void __cdecl(bool,enum CompletionState::Value,std::optional<std::string >)> mResponseCallback;
  std::string mStatus;
  bool mSuccess;
  CompletionState::Value mLessonState;
  std::optional<std::string > mQuizUrl;
};

```

### `LessonStatusRequest_vtbl`
```
struct /*VFT*/ LessonStatusRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `LibrarySearchRequest::CacheMetadata`
```
struct __cppobj LibrarySearchRequest::CacheMetadata
{
  std::string mCacheWriteDate;
  std::string mAcceptLanguage;
  std::string mRequestedBy;
  std::string mClientVersion;
};

```

### `LibrarySearchRequest`
```
struct __cppobj LibrarySearchRequest : CachedRequest
{
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  const std::string mHostUrl;
  const std::string mAcceptLanguage;
  const std::string mDateCreated;
  LibrarySearchQuery mQuery;
  std::string mGetQuery;
  std::function<void __cdecl(std::vector<std::shared_ptr<LibraryItem>> &,std::vector<std::string> &,bool)> mResponseCallback;
  LibrarySearchRequest::CacheMetadata mCacheMetadata;
  unsigned int mCacheMaxAgeHours;
  std::vector<std::shared_ptr<LibraryItem>> mResults;
  std::vector<std::string> mBadProductIds;
  bool mHasMorePages;
  std::string mCorrelationVector;
};

```

### `LibrarySearchRequest_vtbl`
```
struct /*VFT*/ LibrarySearchRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `LibraryImageRequest`
```
struct __cppobj LibraryImageRequest : FileDataRequest
{
};

```

### `LibraryImageRequest_vtbl`
```
struct /*VFT*/ LibraryImageRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `LodestoneBlock`
```
struct __cppobj LodestoneBlock : ActorBlock
{
};

```

### `LodestoneBlock_vtbl`
```
struct /*VFT*/ LodestoneBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  ItemInstance *(__fastcall *getEntityResourceItem)(ActorBlock *this, ItemInstance *result, Random *, const BlockActor *, int);
};

```

### `LayerDetails::Storage`
```
struct __cppobj LayerDetails::Storage
{
  unsigned __int64 mReadableBytes;
  unsigned __int64 mWriteableBytes;
  std::unique_ptr<char [0]> mReadStorage;
  std::unique_ptr<char [0]> mWriteStorage;
};

```

### `LayerDetails::LayerBase_vtbl`
```
struct /*VFT*/ LayerDetails::LayerBase_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
};

```

### `LayerDetails::TransferData<float>`
```
struct __cppobj LayerDetails::TransferData<float> : LayerDetails::Storage
{
};

```

### `Layer<float>`
```
struct __cppobj Layer<float> : LayerDetails::LayerBase
{
};

```

### `Layer<float>_vtbl`
```
struct /*VFT*/ Layer<float>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<float> *(__fastcall *_allocateAndFill)(Layer<float> *this, LayerDetails::TransferData<float> *result, unsigned __int64, int, int, unsigned int, unsigned int);
};

```

### `LayerDetails::BufferAccessor<char>`
```
const struct __cppobj LayerDetails::BufferAccessor<char>
{
  char *mStorage;
  unsigned __int64 mCount;
};

```

### `LayerDetails::BufferAccessor<float>`
```
struct __cppobj LayerDetails::BufferAccessor<float>
{
  char *mStorage;
  unsigned __int64 mCount;
};

```

### `LayerDetails::WorkingData<float,char>`
```
struct __cppobj LayerDetails::WorkingData<float,char> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<char> mParentArea;
  LayerDetails::BufferAccessor<float> mResult;
};

```

### `LayerDetails::TransferData<char>`
```
struct __cppobj LayerDetails::TransferData<char> : LayerDetails::Storage
{
};

```

### `LayerDetails::BufferAccessor<float>::TypedBits`
```
struct __cppobj LayerDetails::BufferAccessor<float>::TypedBits
{
  char *mLocation;
};

```

### `LootTableContext::Builder`
```
struct __cppobj LootTableContext::Builder
{
  Level *mLevel;
  BlockSource *mRegion;
  float mLuck;
  Actor *mThisEntity;
  Player *mKillerPlayer;
  const ActorDamageSource *mDeathSource;
  float mExplosionRadius;
  std::string mOriginalItemName;
};

```

### `LeashableDefinition`
```
struct __cppobj __declspec(align(8)) LeashableDefinition
{
  float mSoftDistance;
  float mHardDistance;
  float mMaxDistance;
  DefinitionTrigger mOnLeash;
  DefinitionTrigger mOnUnleash;
  bool mCanBeStolen;
};

```

### `LeashableComponent`
```
struct __cppobj LeashableComponent : IEntityComponent
{
};

```

### `LegacyTradeableDefinition`
```
struct __cppobj __declspec(align(8)) LegacyTradeableDefinition
{
  std::string mDisplayName;
  std::string mTradeTablePath;
  bool mUseNewTradeScreen;
  bool mPersistTrades;
  bool mConvertTradesEconomy;
};

```

### `LookAtComponent`
```
struct __cppobj LookAtComponent : IEntityComponent
{
  bool mSetTarget;
  float mSearchRadius;
  bool mAllowInvulnerable;
  int mCoolingTime;
};

```

### `LookControl`
```
struct __cppobj LookControl : Control
{
};

```

### `LookControl_vtbl`
```
struct /*VFT*/ LookControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(LookControl *this, Mob *);
  void (__fastcall *tick)(LookControl *this, Mob *);
};

```

### `LegacyTradeableComponent::getInteraction::__l17::<lambda_92c5888b87b9a838aa19e047a1eced20>`
```
struct __cppobj __declspec(align(8)) LegacyTradeableComponent::getInteraction::__l17::<lambda_92c5888b87b9a838aa19e047a1eced20>
{
  Player *player;
  Actor *owner;
  const bool useNewTradeScreen;
};

```

### `LeashableComponent::getInteraction::__l22::<lambda_702674731951615cfb31cf33ab54eea3>`
```
struct __cppobj LeashableComponent::getInteraction::__l22::<lambda_702674731951615cfb31cf33ab54eea3>
{
  Actor *owner;
  Player *player;
  LeashableComponent *const __this;
};

```

### `LeashableComponent::getInteraction::__l11::<lambda_bfec5b7a45ae662edfa6da94275f0ae2>`
```
struct __cppobj LeashableComponent::getInteraction::__l11::<lambda_bfec5b7a45ae662edfa6da94275f0ae2>
{
  Actor *owner;
  LeashableComponent *const __this;
};

```

### `LeashableDefinition::buildSchema::__l2::<lambda_3ad7096af803fcc3f75cab3f5e6e033d>`
```
struct __cppobj LeashableDefinition::buildSchema::__l2::<lambda_3ad7096af803fcc3f75cab3f5e6e033d>
{
};

```

### `LookAtPosGoal`
```
struct __cppobj LookAtPosGoal : Goal
{
  BlockPos mLookAt;
  bool mIsLooking;
  bool mRejectOther;
  int mAngleOfViewX;
  int mAngleOfViewY;
  int mLookTime;
  int mMinLookTime;
  int mMaxLookTime;
  float mProbability;
  Mob *mMob;
};

```

### `LookAtPosGoal_vtbl`
```
struct /*VFT*/ LookAtPosGoal_vtbl
{
  void (__fastcall *~Goal)(Goal *this);
  bool (__fastcall *canUse)(Goal *this);
  bool (__fastcall *canContinueToUse)(Goal *this);
  bool (__fastcall *canBeInterrupted)(Goal *this);
  void (__fastcall *start)(Goal *this);
  void (__fastcall *stop)(Goal *this);
  void (__fastcall *tick)(Goal *this);
  void (__fastcall *appendDebugInfo)(Goal *this, std::string *);
  bool (__fastcall *isTargetGoal)(Goal *this);
  void (__fastcall *onPlayerDimensionChanged)(Goal *this, Player *, AutomaticID<Dimension,int>);
};

```

### `LookAtSystem`
```
struct __cppobj LookAtSystem : ITickingSystem
{
};

```

### `LookAtSystem_vtbl`
```
struct /*VFT*/ LookAtSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `LookControlSystem`
```
struct __cppobj LookControlSystem : ITickingSystem
{
};

```

### `LookControlSystem_vtbl`
```
struct /*VFT*/ LookControlSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `LevelDbSequentialFile`
```
struct __cppobj LevelDbSequentialFile : leveldb::SequentialFile
{
  Core::File mFile;
};

```

### `LevelDbSequentialFile_vtbl`
```
struct /*VFT*/ LevelDbSequentialFile_vtbl
{
  void (__fastcall *~SequentialFile)(leveldb::SequentialFile *this);
  leveldb::Status *(__fastcall *Read)(leveldb::SequentialFile *this, leveldb::Status *result, unsigned __int64, leveldb::Slice *, char *);
  leveldb::Status *(__fastcall *Skip)(leveldb::SequentialFile *this, leveldb::Status *result, unsigned __int64);
};

```

### `LevelDbRandomAccessFile`
```
struct __cppobj LevelDbRandomAccessFile : leveldb::RandomAccessFile
{
  Core::File mFile;
  std::mutex mMutex;
};

```

### `LevelDbRandomAccessFile_vtbl`
```
struct /*VFT*/ LevelDbRandomAccessFile_vtbl
{
  void (__fastcall *~RandomAccessFile)(leveldb::RandomAccessFile *this);
  leveldb::Status *(__fastcall *Read)(leveldb::RandomAccessFile *this, leveldb::Status *result, unsigned __int64, unsigned __int64, leveldb::Slice *, char *);
};

```

### `LevelDbWritableFile`
```
struct __cppobj LevelDbWritableFile : leveldb::WritableFile
{
  Core::File mFile;
  std::string mFilenameHackForManifestSync;
};

```

### `LevelDbWritableFile_vtbl`
```
struct /*VFT*/ LevelDbWritableFile_vtbl
{
  void (__fastcall *~WritableFile)(leveldb::WritableFile *this);
  leveldb::Status *(__fastcall *Append)(leveldb::WritableFile *this, leveldb::Status *result, const leveldb::Slice *);
  leveldb::Status *(__fastcall *Close)(leveldb::WritableFile *this, leveldb::Status *result);
  leveldb::Status *(__fastcall *Flush)(leveldb::WritableFile *this, leveldb::Status *result);
  leveldb::Status *(__fastcall *Sync)(leveldb::WritableFile *this, leveldb::Status *result);
};

```

### `LevelDbFileLock`
```
struct __cppobj LevelDbFileLock : leveldb::FileLock
{
};

```

### `LevelDbFileLock_vtbl`
```
struct /*VFT*/ LevelDbFileLock_vtbl
{
  void (__fastcall *~FileLock)(leveldb::FileLock *this);
};

```

### `LevelDbLogger`
```
struct __cppobj LevelDbLogger : leveldb::Logger
{
};

```

### `LevelDbLogger_vtbl`
```
struct /*VFT*/ LevelDbLogger_vtbl
{
  void (__fastcall *~Logger)(leveldb::Logger *this);
  void (__fastcall *Logv)(leveldb::Logger *this, const char *, char *);
};

```

### `LevelDbEnv::Schedule::__l2::<lambda_f49969aee8341d0263f8b75ad776edc4>`
```
struct __cppobj LevelDbEnv::Schedule::__l2::<lambda_f49969aee8341d0263f8b75ad776edc4>
{
  void (__fastcall *function)(void *);
  void *arg;
};

```

### `leveldb::ZlibCompressorBase_vtbl`
```
struct /*VFT*/ leveldb::ZlibCompressorBase_vtbl
{
  void (__fastcall *~Compressor)(leveldb::Compressor *this);
  void (__fastcall *compressImpl)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
  bool (__fastcall *decompress)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
};

```

### `leveldb::ZlibCompressor`
```
struct __cppobj leveldb::ZlibCompressor : leveldb::ZlibCompressorBase
{
};

```

### `leveldb::ZlibCompressor_vtbl`
```
struct /*VFT*/ leveldb::ZlibCompressor_vtbl
{
  void (__fastcall *~Compressor)(leveldb::Compressor *this);
  void (__fastcall *compressImpl)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
  bool (__fastcall *decompress)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
};

```

### `leveldb::ZlibCompressorRaw`
```
struct __cppobj leveldb::ZlibCompressorRaw : leveldb::ZlibCompressorBase
{
};

```

### `leveldb::ZlibCompressorRaw_vtbl`
```
struct /*VFT*/ leveldb::ZlibCompressorRaw_vtbl
{
  void (__fastcall *~Compressor)(leveldb::Compressor *this);
  void (__fastcall *compressImpl)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
  bool (__fastcall *decompress)(leveldb::Compressor *this, const char *, unsigned __int64, std::string *);
};

```

### `LocalConnector::onRemoteDisconnected::__l5::<lambda_f93dfeaa3e76b9e290819e2fab7d0ef9>`
```
struct __cppobj LocalConnector::onRemoteDisconnected::__l5::<lambda_f93dfeaa3e76b9e290819e2fab7d0ef9>
{
  NetworkIdentifier otherId;
  LocalConnector *const __this;
};

```

### `ListCommand`
```
struct __cppobj ListCommand : ServerCommand
{
};

```

### `ListCommand_vtbl`
```
struct /*VFT*/ ListCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ListDCommand`
```
struct __cppobj __declspec(align(8)) ListDCommand : ServerCommand
{
  _BYTE mDetails[4];
};

```

### `ListDCommand_vtbl`
```
struct /*VFT*/ ListDCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `LocateCommand`
```
struct __cppobj __declspec(align(8)) LocateCommand : Command
{
  StructureFeatureType mFeature;
};

```

### `LocateCommand_vtbl`
```
struct /*VFT*/ LocateCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ListCommand::execute::__l15::<lambda_0d606404f3730d0f1e0a107965271e32>`
```
struct __cppobj ListCommand::execute::__l15::<lambda_0d606404f3730d0f1e0a107965271e32>
{
  std::vector<Player const *> *players;
};

```

### `ListCommand::execute::__l13::<lambda_2e7f0392e569b6bdc30e6bc9305fa0a4>`
```
struct __cppobj ListCommand::execute::__l13::<lambda_2e7f0392e569b6bdc30e6bc9305fa0a4>
{
  std::vector<Player const *> *players;
  std::string *resultList;
};

```

### `LootTableDefinition`
```
struct __cppobj LootTableDefinition
{
  std::string mFilePath;
};

```

### `LegacyBodyControl`
```
struct __cppobj LegacyBodyControl : BodyControl
{
};

```

### `LegacyBodyControl_vtbl`
```
struct /*VFT*/ LegacyBodyControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *clientTick)(BodyControl *this, Mob *);
};

```

### `Llama`
```
struct __cppobj Llama : Animal
{
};

```

### `LookAtBlockNode`
```
struct __cppobj __declspec(align(8)) LookAtBlockNode : BehaviorNode
{
  BlockPos mBlockPos;
  int mDelayTicks;
  int mDelayCounter;
};

```

### `LookAtBlockNode_vtbl`
```
struct /*VFT*/ LookAtBlockNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `LookAtBlockDefinition`
```
struct __cppobj LookAtBlockDefinition : BehaviorDefinition
{
  BlockPos mBlockPos;
  std::string mBlockPosId;
};

```

### `LookAtBlockDefinition_vtbl`
```
struct /*VFT*/ LookAtBlockDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `LookAtActorNode`
```
struct __cppobj LookAtActorNode : BehaviorNode
{
  int mDelayTicks;
  int mDelayCounter;
  ActorType mEntityType;
  int mSearchRadius;
};

```

### `LookAtActorNode_vtbl`
```
struct /*VFT*/ LookAtActorNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `LookAtActorDefinition`
```
struct __cppobj LookAtActorDefinition : BehaviorDefinition
{
  std::string mEntityName;
  std::string mEntityType;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `LookAtActorDefinition_vtbl`
```
struct /*VFT*/ LookAtActorDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `LeashFenceKnotActor::getInteraction::__l5::<lambda_fba8b1fcb26f3ee345fc375a962d8254>`
```
struct __cppobj LeashFenceKnotActor::getInteraction::__l5::<lambda_fba8b1fcb26f3ee345fc375a962d8254>
{
  LeashFenceKnotActor *const __this;
};

```

### `LeashFenceKnotActor::numberofAnimalsAttached::__l2::<lambda_48e561cf7a23ad8053577180ab266e54>`
```
struct __cppobj LeashFenceKnotActor::numberofAnimalsAttached::__l2::<lambda_48e561cf7a23ad8053577180ab266e54>
{
  int *count;
};

```

### `LeashFenceKnotActor::removeAnimals::__l2::<lambda_3bbb238cec2a42e346a1795feb7cd16f>`
```
struct __cppobj LeashFenceKnotActor::removeAnimals::__l2::<lambda_3bbb238cec2a42e346a1795feb7cd16f>
{
  Player *player;
};

```

### `LavaSlime`
```
struct __cppobj LavaSlime : Slime
{
};

```

### `LargeFireball`
```
struct __cppobj __declspec(align(8)) LargeFireball : Fireball
{
  int mExplosionPower;
};

```

### `LargeFireball_vtbl`
```
struct /*VFT*/ LargeFireball_vtbl
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
  float (__fastcall *getInertia)(Fireball *this);
  void (__fastcall *onHit)(Fireball *this, const HitResult *);
  ParticleType (__fastcall *getTrailParticle)(Fireball *this);
  bool (__fastcall *shouldBurn)(Fireball *this);
};

```

### `LlamaSpit`
```
struct __cppobj LlamaSpit : PredictableProjectile
{
  ActorUniqueID ownerId;
  MovementInterpolator mInterpolation;
};

```

### `LlamaSpit_vtbl`
```
struct /*VFT*/ LlamaSpit_vtbl
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

### `LevelContainerModel`
```
struct __cppobj LevelContainerModel : ContainerModel
{
  Player *mPlayer;
  BlockPos mBlockPos;
  BlockActorType mBlockEntityType;
  ActorUniqueID mEntityUniqueId;
  std::vector<Container *> initContainerList;
};

```

### `LevelContainerModel_vtbl`
```
struct /*VFT*/ LevelContainerModel_vtbl
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
};

```

### `LevelContainerManagerModel::_postInit::__l2::<lambda_3dd4d1f2c36000a64e678bfd6b26033b>`
```
struct __cppobj LevelContainerManagerModel::_postInit::__l2::<lambda_3dd4d1f2c36000a64e678bfd6b26033b>
{
  LevelContainerManagerModel *const __this;
};

```

### `LevelEventCoordinator::sendLevelBiomesRegistered::__l2::<lambda_ddc846bd8e8a8ff1387a315cf3b7d60c>`
```
struct __cppobj LevelEventCoordinator::sendLevelBiomesRegistered::__l2::<lambda_ddc846bd8e8a8ff1387a315cf3b7d60c>
{
  BiomeRegistry *biomeRegistry;
};

```

### `LevelEventCoordinator::sendLevelTick::__l2::<lambda_ec1aec075e5a64d264e03959a3191abd>`
```
struct __cppobj LevelEventCoordinator::sendLevelTick::__l2::<lambda_ec1aec075e5a64d264e03959a3191abd>
{
};

```

### `LevelEventCoordinator::sendLevelAddedActor::__l2::<lambda_2070b6ba94f287344509b3253827d448>`
```
struct __cppobj LevelEventCoordinator::sendLevelAddedActor::__l2::<lambda_2070b6ba94f287344509b3253827d448>
{
  Level *level;
  Actor *actor;
};

```

### `LevelEventCoordinator::sendLevelRemovedActor::__l2::<lambda_e9c3114ff799af2f6b051c7a5dd1a2a5>`
```
struct __cppobj LevelEventCoordinator::sendLevelRemovedActor::__l2::<lambda_e9c3114ff799af2f6b051c7a5dd1a2a5>
{
  Level *level;
  Actor *actor;
};

```

### `LevelEventCoordinator::sendLevelInitialized::__l2::<lambda_a4358936410fc0ba7f7d64f32435908c>`
```
struct __cppobj LevelEventCoordinator::sendLevelInitialized::__l2::<lambda_a4358936410fc0ba7f7d64f32435908c>
{
  Level *level;
};

```

### `LootEnchant`
```
struct __cppobj LootEnchant : Enchant
{
};

```

### `LootEnchant_vtbl`
```
struct /*VFT*/ LootEnchant_vtbl
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

### `LingeringPotionItem`
```
struct __cppobj __declspec(align(8)) LingeringPotionItem : PotionItem
{
  TextureUVCoordinateSet mLingeringIcons[17];
  _BYTE mLingeringPotionVariants[68];
};

```

### `LeafBlockItem`
```
struct __cppobj LeafBlockItem : BlockItem
{
  const Block *m_parentBlock;
};

```

### `LayerDetails::TransferData<Biome *>`
```
struct __cppobj LayerDetails::TransferData<Biome *> : LayerDetails::Storage
{
};

```

### `Layer<Biome *>_vtbl`
```
struct /*VFT*/ Layer<Biome *>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<Biome *> *(__fastcall *_allocateAndFill)(Layer<Biome *> *this, LayerDetails::TransferData<Biome *> *result, unsigned __int64, int, int, unsigned int, unsigned int);
};

```

### `LayerBiomeSource_vtbl`
```
struct /*VFT*/ LayerBiomeSource_vtbl
{
  void (__fastcall *~BiomeSource)(BiomeSource *this);
  void (__fastcall *fillBiomes)(BiomeSource *this, LevelChunk *);
  BiomeArea *(__fastcall *getBiomeArea)(BiomeSource *this, BiomeArea *result, const BoundingBox *, unsigned int);
  bool (__fastcall *containsOnly)(BiomeSource *this, int, int, int, gsl::span<int const ,-1>);
  const Biome *(__fastcall *getBiome)(BiomeSource *this, int, int);
};

```

### `LecternBlock`
```
const struct __cppobj LecternBlock : ActorBlock
{
};

```

### `LecternBlock_vtbl`
```
struct /*VFT*/ LecternBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  ItemInstance *(__fastcall *getEntityResourceItem)(ActorBlock *this, ItemInstance *result, Random *, const BlockActor *, int);
};

```

### `LootComponent`
```
struct __cppobj LootComponent
{
  std::string mLootTable;
};

```

### `ListenOnRemoveComponentDescription`
```
struct __cppobj __declspec(align(8)) ListenOnRemoveComponentDescription : BlockComponentDescription
{
  bool mValue;
};

```

### `ListenOnRemoveComponentDescription_vtbl`
```
struct /*VFT*/ ListenOnRemoveComponentDescription_vtbl
{
  void (__fastcall *~BlockComponentDescription)(BlockComponentDescription *this);
  const std::string *(__fastcall *getName)(BlockComponentDescription *this);
  void (__fastcall *initializeComponent)(BlockComponentDescription *this, EntityContext *);
  void (__fastcall *buildSchema)(BlockComponentDescription *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,BlockComponentGroupDescription> > *, const BlockComponentFactory *);
  bool (__fastcall *isNetworkComponent)(BlockComponentDescription *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(BlockComponentDescription *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(BlockComponentDescription *this, const CompoundTag *);
};

```

### `ListenOnRemoveComponent`
```
struct __cppobj ListenOnRemoveComponent
{
  bool mValue;
};

```

### `LootComponentDescription`
```
struct __cppobj LootComponentDescription : BlockComponentDescription
{
  std::string mLootTable;
};

```

### `LootComponentDescription_vtbl`
```
struct /*VFT*/ LootComponentDescription_vtbl
{
  void (__fastcall *~BlockComponentDescription)(BlockComponentDescription *this);
  const std::string *(__fastcall *getName)(BlockComponentDescription *this);
  void (__fastcall *initializeComponent)(BlockComponentDescription *this, EntityContext *);
  void (__fastcall *buildSchema)(BlockComponentDescription *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,BlockComponentGroupDescription> > *, const BlockComponentFactory *);
  bool (__fastcall *isNetworkComponent)(BlockComponentDescription *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(BlockComponentDescription *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(BlockComponentDescription *this, const CompoundTag *);
};

```

### `LootComponentDescription::buildSchema::__l2::<lambda_3945d8a3b1d9e1908875af1d7a69fb2d>`
```
struct __cppobj LootComponentDescription::buildSchema::__l2::<lambda_3945d8a3b1d9e1908875af1d7a69fb2d>
{
  const BlockComponentFactory *factory;
};

```

### `LadderBlock`
```
struct __cppobj LadderBlock : BlockLegacy
{
};

```

### `LadderBlock_vtbl`
```
struct /*VFT*/ LadderBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `LanternBlock`
```
struct __cppobj LanternBlock : BlockLegacy
{
};

```

### `LanternBlock_vtbl`
```
struct /*VFT*/ LanternBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `LeverBlock`
```
struct __cppobj LeverBlock : BlockLegacy
{
};

```

### `LeverBlock_vtbl`
```
struct /*VFT*/ LeverBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *updateShape)(LeverBlock *this, BlockSource *, const BlockPos *);
};

```

### `LightBlock`
```
struct __cppobj LightBlock : AirBlock
{
};

```

### `LightBlock_vtbl`
```
struct /*VFT*/ LightBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `LightGemBlock`
```
struct __cppobj LightGemBlock : BlockLegacy
{
};

```

