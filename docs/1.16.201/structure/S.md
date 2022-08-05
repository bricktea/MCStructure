# S
### `sockaddr_storage`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | ss_family
2 | (6) `char[6]` | __ss_pad1
8 | (8) `__int64` | __ss_align
16 | (112) `char[112]` | __ss_pad2


### `sockaddr_in6`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | sin6_family
2 | (2) `unsigned __int16` | sin6_port
4 | (4) `unsigned int` | sin6_flowinfo
8 | (16) `in6_addr` | sin6_addr
24 | (4) `$FFF57C54CBA81593691E4AEB54295E0F` | ___u4


### `SCOPE_ID`
Offset | Type | Name
-|-|-|-
0 | (4) `$530EFB6A1D65251AD0979CDC2CB9746C` | ___u0


### `sockaddr_in`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | sin_family
2 | (2) `unsigned __int16` | sin_port
4 | (4) `in_addr` | sin_addr
8 | (8) `char[8]` | sin_zero


### `Social::MultiplayerGameInfo`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Social::GameConnectionInfo>` | supportedConnections
24 | (32) `std::string` | ownerId
56 | (24) `std::vector<unsigned __int64>` | playerIds
80 | (32) `std::string` | ownerNickname
112 | (32) `std::string` | handleId
144 | (32) `std::string` | levelId
176 | (32) `std::string` | sessionId
208 | (32) `std::string` | rakNetGUID
240 | (32) `std::string` | worldName
272 | (32) `std::string` | gameType
304 | (32) `std::string` | version
336 | (8) `__int64` | realmId
344 | (32) `std::string` | thirdPartyServerId
376 | (32) `std::string` | thirdPartyServerIp
408 | (4) `int` | thirdPartyServerPort
412 | (4) `int` | protocol
416 | (4) `int` | maxMemberCount
420 | (4) `int` | memberCount
424 | (4) `Social::MultiplayerServiceIdentifier` | serviceProvider
432 | (32) `Core::Path` | serviceIconPath
464 | (4) `Social::GamePublishSetting` | broadcastSetting
468 | (1) `bool` | lanGame
469 | (1) `bool` | onlineCrossPlatformGame


### `ScoreboardScreenController::_generatePlayerLists::__l9::<lambda_c30327f16354614b4afd1e568442035f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const __int64` | localId


### `StorageManagementScreenController::_registerBindings::__l2::<lambda_2b4e32f678902a37655dae31890e7661>::()::__l2::<lambda_e8ef8c4786064a9115d51b6c5376d6f0>`
Offset | Type | Name
-|-|-|-


### `StorageManagementScreenController::_registerBindings::__l2::<lambda_55a97dd0adea2a21290bc7f05a124545>::()::__l2::<lambda_efaf8c6a77e10d7cc7313ebe36397c81>`
Offset | Type | Name
-|-|-|-


### `Stopwatch`
Offset | Type | Name
-|-|-|-
0 | (8) `Stopwatch_vtbl *` | __vftable
8 | (8) `long double` | _st
16 | (8) `long double` | _tt
24 | (8) `long double` | _last
32 | (8) `long double` | _max
40 | (4) `int` | _count
44 | (4) `int` | _printcounter


### `ScreenRenderBatch::_sortRenderControlsCollection::__l2::<lambda_3bc987c7d55656a61929d19e67d0bc15>`
Offset | Type | Name
-|-|-|-


### `ScreenView::_prepResevedButtonUpLists::__l15::<lambda_52074e29716179749e6c979bfd9e3b6c>`
Offset | Type | Name
-|-|-|-


### `SemVersion`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mMajor
2 | (2) `unsigned __int16` | mMinor
4 | (2) `unsigned __int16` | mPatch
8 | (32) `std::string` | mPreRelease
40 | (32) `std::string` | mBuildMeta
72 | (32) `std::string` | mFullVersionString
104 | (1) `bool` | mValidVersion
105 | (1) `bool` | mAnyVersion


### `Skin`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | mSkinTextureName
32 | (8) `SkinPack *` | mSkinPack
40 | (16) `std::shared_ptr<FileWatcherUpdate>` | mFileWatcherUpdate
56 | (32) `std::string` | mName
88 | (32) `std::string` | mLocName
120 | (32) `std::string` | mSerializableName
152 | (32) `std::string` | mSerializableLegacyName
184 | (32) `Core::PathBuffer<std::string >` | mCapeTextureName
216 | (32) `Core::PathBuffer<std::string >` | mBloomTextureName
248 | (56) `ResourceLocation` | mBloomImageLocation
304 | (32) `std::string` | mIID
336 | (56) `ResourceLocation` | mSkinImageLocation
392 | (56) `ResourceLocation` | mCapeImageLocation
448 | (56) `ResourceLocation` | mAnimationsLocation
504 | (56) `ResourceLocation` | mAnimationControllersLocation
560 | (4) `Skin::SkinType` | mSkinType
568 | (16) `mce::FileWatcherHandle` | mSkinFileWatcherHanedle
584 | (16) `mce::FileWatcherHandle` | mCapeFileWatcherHanedle
600 | (4) `int` | mSkinIndex
608 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mLastUpdated
616 | (1) `bool` | mIsCapeOnClassicSkin
624 | (32) `std::string` | mCapeId
656 | (640) `SerializedSkin` | mSerializedSkin


### `SerializedSkin`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mId
32 | (32) `std::string` | fullId
64 | (32) `std::string` | mResourcePatch
96 | (32) `std::string` | mDefaultGeometryName
128 | (80) `mce::Image` | mSkinImage
208 | (80) `mce::Image` | mCapeImage
288 | (80) `mce::Image` | mBloomImage
368 | (24) `std::vector<AnimatedImageData>` | mSkinAnimatedImages
392 | (16) `Json::Value` | mGeometryData
408 | (16) `Json::Value` | mGeometryDataMutable
424 | (32) `std::string` | mAnimationData
456 | (32) `std::string` | mCapeId
488 | (1) `bool` | mIsPremium
489 | (1) `bool` | mIsPersona
490 | (1) `bool` | mIsPersonaCapeOnClassicSkin
496 | (24) `std::vector<SerializedPersonaPieceHandle>` | mPersonaPieces
520 | (32) `std::string` | mArmSize
552 | (64) `std::unordered_map<enum persona::PieceType,TintMapColor>` | mPieceTintColors
616 | (16) `mce::Color` | mSkinColor
632 | (1) `TrustedSkinFlag` | mIsTrustedSkin
633 | (1) `bool` | mIsPreview
636 | (4) `unsigned int` | mSkinVersion


### `SkinHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mPackId
16 | (24) `ContentIdentity` | mContentIdentity
40 | (4) `int` | mSkinIndex
48 | (32) `std::string` | mSkinName
80 | (32) `std::string` | mCapeId


### `StoreCatalogItem`
Offset | Type | Name
-|-|-|-
0 | (8) `IStoreCatalogItem` | baseclass_0
8 | (32) `const std::string` | mProductId
40 | (32) `std::string` | mPriceInCoinsStr
72 | (32) `std::string` | mDiscountPriceStr
104 | (4) `int` | mDiscountPrice
108 | (4) `int` | mTotalMSRP
112 | (4) `float` | mDiscount
120 | (32) `std::string` | mSalesDocId
152 | (8) `__int64` | mDiscountEndTimeInSeconds
160 | (4) `StoreCatalogCategory` | mStoreCategory
164 | (4) `_BYTE[4]` | mMinPerfTier
168 | (368) `DurableCustom` | mDurableCustom
536 | (584) `CommonDocument` | mCommon
1120 | (8) `std::unique_ptr<StoreCatalogItemCollectionInfo>` | mOfferCollectionInfo
1128 | (24) `std::vector<StoreItemPDPData>` | mMashupSections
1152 | (24) `std::vector<std::string>` | mPackIcons
1176 | (1) `bool` | mIsFeatured
1177 | (1) `bool` | mIsHydrating
1184 | (24) `std::vector<Entitlement const *>` | mEntitlements
1208 | (48) `ReviewModel` | mReviewModel
1256 | (24) `std::vector<StoreCatalogItem::ImageInfo>` | mImageInfoList
1280 | (64) `std::unordered_map<std::string,std::string>` | mTitleDictionary
1344 | (64) `std::unordered_map<std::string,std::string>` | mDescriptionDictionary
1408 | (64) `std::function<void __cdecl(void)>` | mRefreshBindsCallback
1472 | (64) `std::function<enum ItemInstallState __cdecl(std::vector<PackIdVersion> const &)>` | mGetItemInstallStateCallback
1536 | (1) `bool` | mIsValid
1537 | (1) `bool` | mVersionCompatible
1538 | (1) `bool` | mCreatedFromSearchResults
1539 | (1) `bool` | mIsOnSale
1540 | (1) `bool` | mExpired
1544 | (16) `std::shared_ptr<bool>` | mExistenceTracker
1560 | (16) `std::shared_ptr<StoreVisualStyle>` | mRelatedItemsRow


### `StoreFilter::Toggle`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mLabel
32 | (32) `std::string` | mTag
64 | (16) `SearchQuery::Range` | mRange
80 | (1) `bool` | mDefaultState
81 | (1) `bool` | mState


### `SearchQuery::Range`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mLowSet
4 | (4) `float` | mLow
8 | (1) `bool` | mHighSet
12 | (4) `float` | mHigh


### `ServiceRegistrationToken<AppPlatform>`
Offset | Type | Name
-|-|-|-
0 | (8) `AppPlatform *` | mService


### `SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>`
Offset | Type | Name
-|-|-|-
0 | (8) `Lockless::WeakAtomic<SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>::Block *>` | mFrontBlock
8 | (56) `char[56]` | mCachelineFiller
64 | (8) `Lockless::WeakAtomic<SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>::Block *>` | mTailBlock
72 | (8) `unsigned __int64` | mLargestBlockSize


### `SerializerEnumMapping`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,unsigned int>` | mNameToID
64 | (64) `std::unordered_map<unsigned int,std::string>` | mIDToName
128 | (8) `unsigned __int64` | mSizeOf


### `SkinData`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<int>` | mVariant
8 | (8) `std::optional<int>` | mMarkVariant


### `ScoreboardCommand::listObjectives::__l2::<lambda_4f79f5ac9079702c990b557428a715f7>`
Offset | Type | Name
-|-|-|-


### `SoundPlayerInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `SoundPlayerInterface_vtbl *` | __vftable
8 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_8


### `SlotData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mCollectionName
32 | (4) `int` | mCollectionIndex


### `ScatterParamsMolangVariableIndices`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mVariableOriginXIndex
2 | (2) `_BYTE[2]` | mVariableOriginYIndex
4 | (2) `_BYTE[2]` | mVariableOriginZIndex
6 | (6) `_BYTE[6]` | mVariableWorldIndex


### `ServiceRegistrationToken<AppConfigs>`
Offset | Type | Name
-|-|-|-
0 | (8) `AppConfigs *` | mService


### `ServiceRegistrationToken<DataUtils::MiscData>`
Offset | Type | Name
-|-|-|-
0 | (8) `DataUtils::MiscData *` | mService


### `ScriptUtility`
Offset | Type | Name
-|-|-|-
0 | (8) `ScriptInstance *` | m_instance


### `Semaphore`
Offset | Type | Name
-|-|-|-
0 | (72) `std::condition_variable` | mCondition
72 | (80) `std::mutex` | mMutex
152 | (4) `std::atomic<unsigned int>` | mCount


### `SPSCQueue<unsigned int,512>`
Offset | Type | Name
-|-|-|-
0 | (8) `Lockless::WeakAtomic<SPSCQueue<unsigned int,512>::Block *>` | mFrontBlock
8 | (56) `char[56]` | mCachelineFiller
64 | (8) `Lockless::WeakAtomic<SPSCQueue<unsigned int,512>::Block *>` | mTailBlock
72 | (8) `unsigned __int64` | mLargestBlockSize


### `static_tree_desc_s`
Offset | Type | Name
-|-|-|-
0 | (8) `const ct_data_s *` | static_tree
8 | (8) `const int *` | extra_bits
16 | (4) `int` | extra_base
20 | (4) `int` | elems
24 | (4) `int` | max_length


### `stbi_io_callbacks`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(void *, char *, int)` | read
8 | (8) `void (__fastcall *)(void *, int)` | skip
16 | (8) `int (__fastcall *)(void *)` | eof


### `stbir__filter_info`
Offset | Type | Name
-|-|-|-
0 | (8) `float (__fastcall *)(float, float)` | kernel
8 | (8) `float (__fastcall *)(float)` | support


### `SFNT_Interface_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, FT_StreamRec_ *, unsigned int *)` | goto_table
8 | (8) `int (__fastcall *)(FT_StreamRec_ *, TT_FaceRec_ *, int, int, FT_Parameter_ *)` | init_face
16 | (8) `int (__fastcall *)(FT_StreamRec_ *, TT_FaceRec_ *, int, int, FT_Parameter_ *)` | load_face
24 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | done_face
32 | (8) `void *(__fastcall *)(FT_ModuleRec_ *, const char *)` | get_interface
40 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, int, unsigned __int8 *, unsigned int *)` | load_any
48 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_head
56 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *, unsigned __int8)` | load_hhea
64 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_cmap
72 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_maxp
80 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_os2
88 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_post
96 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_name
104 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | free_name
112 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_kern
120 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_gasp
128 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_pclt
136 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_bhed
144 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, unsigned int, unsigned int, FT_StreamRec_ *, FT_Bitmap_ *, TT_SBit_MetricsRec_ *)` | load_sbit_image
152 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, char **)` | get_psname
160 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | free_psnames
168 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, unsigned int)` | get_kerning
176 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_font_dir
184 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *, unsigned __int8)` | load_hmtx
192 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_eblc
200 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | free_eblc
208 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_Size_RequestRec_ *, unsigned int *)` | set_sbit_strike
216 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, FT_Size_Metrics_ *)` | load_strike_metrics
224 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_cpal
232 | (8) `int (__fastcall *)(TT_FaceRec_ *, FT_StreamRec_ *)` | load_colr
240 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | free_cpal
248 | (8) `void (__fastcall *)(TT_FaceRec_ *)` | free_colr
256 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int)` | set_palette
264 | (8) `unsigned __int8 (__fastcall *)(TT_FaceRec_ *, unsigned int, unsigned int *, unsigned int *, FT_LayerIterator_ *)` | get_colr_layer
272 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned int, FT_GlyphSlotRec_ *, FT_GlyphSlotRec_ *)` | colr_blend
280 | (8) `void (__fastcall *)(TT_FaceRec_ *, unsigned __int8, unsigned int, __int16 *, wchar_t *)` | get_metrics
288 | (8) `int (__fastcall *)(TT_FaceRec_ *, unsigned __int16, char **)` | get_name
296 | (8) `unsigned __int8 (__fastcall *)(TT_FaceRec_ *, unsigned __int16, int *, int *)` | get_name_id


### `state`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | s_narcs
8 | (8) `arc *` | s_arc
16 | (4) `int` | s_lower
20 | (4) `int` | s_upper
24 | (8) `int *` | s_accel
32 | (4) `int` | s_accept


### `ScoreboardIdentityRef`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mObjectiveReferences
8 | (16) `ScoreboardId` | mScoreboardId


### `ScoreboardId`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | mRawID
8 | (8) `IdentityDefinition *` | mIdentityDef


### `SubChunkPos`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (4) `int` | z


### `Social::GameConnectionInfo`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mType
8 | (32) `std::string` | mHostIpAddress
40 | (32) `std::string` | mUnresolvedUrl
72 | (4) `int` | mPort
80 | (32) `std::string` | mRakNetGUID
112 | (136) `ThirdPartyInfo` | mThirdPartyServerInfo
248 | (1) `bool` | mAllowSmallDownloads


### `SparklerItem::ColorInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | mDyeId
1 | (1) `_BYTE[1]` | mColorCompound
4 | (4) `int` | mVariantIndex
8 | (4) `int` | mRGB


### `SpatialActorNetworkData::DebugSendRateModifiers`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSendEveryNPackets
4 | (4) `int` | mDropPacketChance
8 | (1) `bool` | mDrawDebugLines


### `SmallSet<WorkerPool *>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<WorkerPool *>` | c


### `ServiceRegistrationToken<EducationOptions>`
Offset | Type | Name
-|-|-|-
0 | (8) `EducationOptions *` | mService


### `SpinLock`
Offset | Type | Name
-|-|-|-
8 | (8) `const unsigned __int64` | mNoThreadId
16 | (8) `std::atomic<unsigned __int64>` | mOwnerThread
24 | (4) `unsigned int` | mOwnerRefCount


### `ServiceOverrider<bool (__cdecl*)(AssertHandlerContext const &)>`
Offset | Type | Name
-|-|-|-
0 | (168) `Bedrock::Threading::InstancedThreadLocal<bool (__cdecl**)(AssertHandlerContext const &),std::allocator<bool (__cdecl**)(AssertHandlerContext const &)> >` | mService
168 | (8) `bool (__fastcall **)(const AssertHandlerContext *)` | mDefaultService


### `SubChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `DirtyTicksCounter` | mDirtyTicksCounter
8 | (8) `std::unique_ptr<SubChunkBrightnessStorage>` | mLight
16 | (16) `std::unique_ptr<SubChunkBlockStorage>[2]` | mBlocks
32 | (16) `SubChunkBlockStorage *[2]` | mBlocksReadPtr
48 | (8) `SpinLock *` | mWriteLock


### `Social::XboxLiveUserProfileData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mXuid
32 | (4) `_BYTE[4]` | mFetchedData
40 | (32) `std::string` | mGamertag
72 | (32) `std::string` | mDisplayName
104 | (16) `Social::UserPicturePath` | mGamerPicPath
120 | (32) `std::string` | mTitleName
152 | (4) `int` | mTitleId
160 | (32) `std::string` | mGamerScore
192 | (1) `bool` | mNarratorEnabled
193 | (1) `bool` | mIsProfileValid
200 | (32) `std::string` | mPresenceMessage
232 | (4) `_BYTE[4]` | mPresence
236 | (4) `_BYTE[4]` | mIsMuted
240 | (4) `_BYTE[4]` | mIsBlocked
244 | (4) `_BYTE[4]` | mIsFriend
248 | (4) `_BYTE[4]` | mIsFavorite
252 | (4) `_BYTE[4]` | mIsFollowingMe
256 | (24) `std::vector<Social::XboxLivePermission>` | mPermissions


### `Social::UserPicturePath`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ResourceLocation>` | mLocation


### `StopwatchHandler`
Offset | Type | Name
-|-|-|-
0 | (16) `std::map<std::string,std::unique_ptr<Stopwatch>>` | _map
16 | (4) `int` | _printcounter


### `SpatialActorNetworkData::DebugSpatialPacketModifiers`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mCurrentSentSpatialPackets
8 | (8) `unsigned __int64` | mExpectedSentSpatialPackets
16 | (8) `unsigned __int64` | mCurrentSentMotionPredictionHintsPackets
24 | (1) `bool` | mUseValueOverrides
25 | (1) `bool` | mUseScoreOverride
28 | (4) `float` | mOverridemMaxOptimizedDistance
32 | (8) `unsigned __int64` | mOverridemMaxDroppedTicks
40 | (8) `unsigned __int64` | mOverrideScoreValue
48 | (1) `bool` | mOverridemUseMotionPredictionHints


### `Social::XboxLiveLimits`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | burstLimit
4 | (4) `unsigned int` | sustainLimit


### `ServiceReference<AppPlatform>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<AppPlatform>` | mService


### `Social::PlatformUserProfileData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUuid
32 | (32) `std::string` | mDisplayName
64 | (32) `std::string` | mTitleName
96 | (4) `_BYTE[4]` | mPresence
104 | (16) `Social::UserPicturePath` | mProfilePicturePath
120 | (32) `std::string` | mProfilePictureUrl


### `StringHash`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | m_hash


### `ServiceReference<IMinecraftEventing>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<IMinecraftEventing>` | mService


### `SynchedActorData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<DataItem>>` | mItemsArray
24 | (2) `unsigned __int16` | minIdxDirty
26 | (2) `unsigned __int16` | maxIdxDirty


### `StateVectorComponent`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (12) `Vec3` | mPosPrev
24 | (12) `Vec3` | mPosDelta


### `ServiceReference<ContentLog>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<ContentLog>` | mService


### `static_vector<ClientBlockPipeline::SmoothLightBakingStep::VisibleCellData,27>`
Offset | Type | Name
-|-|-|-
0 | (648) `std::_Align_type<double,24>[27]` | mArray
648 | (8) `unsigned __int64` | mSize


### `ServiceReference<FeatureToggles>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<FeatureToggles>` | mService


### `SoundOptions::VolumeSlider`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | sound
32 | (4) `float` | volume
40 | (8) `unsigned __int64` | soundHandle


### `ServiceReference<OfferRepository>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<OfferRepository>` | mService


### `SPIEntitlementManager::purchaseCoinOffer::__l5::<lambda_243221c31ed258c47641733602b06e40>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | resultCallback


### `SPIEntitlementManager::purchaseCatalogOffer::__l5::<lambda_4bb8df429293c8353616859f9c956b6d>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum TransactionStatus)>` | callback


### `SPIEntitlementManager::transferDeviceAccountToXboxLive::__l5::<lambda_83b624fc21278211102362b27549b1e2>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | resultCallback


### `ScreenContext`
Offset | Type | Name
-|-|-|-
0 | (12) `UIScreenContext` | baseclass_0
16 | (112) `mce::MeshContext` | baseclass_10
128 | (8) `mce::RenderDevice *` | renderDevice
136 | (8) `mce::RendererSettings *` | rendererSettings
144 | (8) `mce::FrameBufferObject *` | frameBufferObject
152 | (8) `const mce::ViewportInfo *` | viewport
160 | (8) `const GuiData *` | guiData
168 | (8) `const mce::Clock *` | clock
176 | (8) `Tessellator *` | tessellator
184 | (8) `MinecraftGraphicsPipeline *` | minecraftGraphicsPipeline
192 | (8) `MinecraftGraphics *` | minecraftGraphics
200 | (8) `const UIProfanityContext *` | uiProfanityContext
208 | (8) `CommandListQueue *` | commandListQueue
216 | (8) `LinearAllocator<FrameRenderObject> *` | frameAllocator


### `StructureBlockPalette::TickingQueueData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTickDelay


### `Spherical`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mRadius
4 | (4) `float` | mAzimuth
8 | (4) `float` | mPolarAngle


### `SpecificEnchantFunction::EnchantInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `Enchant::Type` | enchantment
4 | (8) `IntRange` | levelRange


### `ServiceReference<AppConfigs>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<AppConfigs>` | mService


### `ServiceReference<DataUtils::MiscData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<DataUtils::MiscData>` | mService


### `ServiceReference<mce::framebuilder::FrameBuilder>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<mce::framebuilder::FrameBuilder>` | mService


### `StoreSearchQuery`
Offset | Type | Name
-|-|-|-
0 | (576) `SearchQuery` | baseclass_0
576 | (32) `std::string` | mTelemetryId
608 | (4) `_BYTE[4]` | mFlags


### `SearchQuery`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mContentTypes
24 | (24) `std::vector<std::string>` | mSelectedFields
48 | (32) `std::string` | mSearchString
80 | (32) `std::string` | mStartDateFrom
112 | (32) `std::string` | mStartDateTo
144 | (32) `std::string` | mPlatform
176 | (32) `std::string` | mTitleTag
208 | (24) `std::vector<std::string>` | mAndTags
232 | (24) `std::vector<std::string>` | mOrTags
256 | (24) `std::vector<std::string>` | mNotTags
280 | (24) `std::vector<std::string>` | mSaleTags
304 | (24) `std::vector<std::string>` | mProductIdOrder
328 | (24) `std::vector<std::string>` | mCreatorIds
352 | (24) `std::vector<std::string>` | mNotCreatorIds
376 | (24) `std::vector<std::string>` | mPackIds
400 | (24) `std::vector<std::string>` | mPieceTypeFilters
424 | (24) `std::vector<std::string>` | mNotPieceTypeFilters
448 | (24) `std::vector<std::string>` | mRarityFilters
472 | (24) `std::vector<SearchQuery::Range>` | mPriceRangeFilters
496 | (16) `SearchQuery::Range` | mRatingFilter
512 | (4) `SearchQuery::SortBy` | mSortBy
516 | (4) `SearchQuery::SortDirection` | mSortDirection
520 | (4) `int` | mSkip
524 | (4) `int` | mTop
528 | (1) `SearchQuery::InventoryFilter` | mClientSideInventoryFilter
536 | (32) `std::string` | mClientSortType
568 | (1) `bool` | mFilterPastRealmsPlus
569 | (1) `bool` | mFilterCurrentRealmsPlus
570 | (1) `bool` | mClientSideInventorySearchEnabled
571 | (1) `bool` | mIncludeBundles


### `SubChunkLightIndex`
Offset | Type | Name
-|-|-|-
0 | (4) `$1CD88F237A8B1E43A1194E114715C208` | ___u0


### `SkinInfoData`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinInfoData_vtbl *` | __vftable
8 | (32) `std::string` | mDefaultMeshName
40 | (1) `bool` | mIsAlphaTest
41 | (1) `bool` | mIsDirty
48 | (640) `SerializedSkin` | mSkin


### `SpawnSettings`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | type
8 | (32) `std::string` | userDefinedBiomeName
40 | (4) `AutomaticID<Dimension,int>` | dimId
44 | (4) `AutomaticID<Dimension,int>` | dimension


### `ServiceReference<Social::UserManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<Social::UserManager>` | mService


### `ServiceRegistrationToken<ProfilingManager>`
Offset | Type | Name
-|-|-|-
0 | (8) `ProfilingManager *` | mService


### `ServiceRegistrationToken<Bedrock::Threading::PendingConditionals>`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Threading::PendingConditionals *` | mService


### `ServiceRegistrationToken<ChunkPerformanceData>`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPerformanceData *` | mService


### `ServiceReference<Core::LoadTimeProfiler>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<Core::LoadTimeProfiler>` | mService


### `ServiceRegistrationToken<ResourceLoadManager>`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourceLoadManager *` | mService


### `ServiceRegistrationToken<mce::FileWatcherNull>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::FileWatcherNull *` | mService


### `ServiceRegistrationToken<DateManager>`
Offset | Type | Name
-|-|-|-
0 | (8) `DateManager *` | mService


### `ServiceRegistrationToken<ContentLog>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentLog *` | mService


### `SoundSystemGUID`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Data1
4 | (2) `unsigned __int16` | Data2
6 | (2) `unsigned __int16` | Data3
8 | (8) `unsigned __int8[8]` | Data4


### `ServiceReference<BasicTestProfileStats>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<BasicTestProfileStats>` | mService


### `ServiceReference<IRayTracingOptions>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<IRayTracingOptions>` | mService


### `ServiceRegistrationToken<mce::framebuilder::FrameBuilder>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::FrameBuilder *` | mService


### `ScreenshotOptions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mCropToRatio
4 | (4) `int` | mWidthRatio
8 | (4) `int` | mHeightRatio
12 | (4) `unsigned int` | mMaxWidth
16 | (4) `unsigned int` | mMaxHeight
20 | (1) `bool` | mRestrictScreenshotSize
21 | (1) `bool` | mApplySquareFrame
24 | (32) `Core::PathBuffer<std::string >` | mRequestedFileName
56 | (32) `Core::PathBuffer<std::string >` | mRequestedFilePath
88 | (32) `Core::PathBuffer<std::string >` | mRequestedExtension
120 | (1) `bool` | mReplaceImage
121 | (1) `bool` | mUseScreenshotsFolder
122 | (1) `bool` | mHideUI
123 | (1) `bool` | mLogRequest
124 | (1) `bool` | mWriteScreenshotToFile
125 | (1) `bool` | mIsSavegameScreenshot
128 | (32) `Core::PathBuffer<std::string >` | mOutFileName
160 | (32) `Core::PathBuffer<std::string >` | mOutFileDir
192 | (32) `Core::PathBuffer<std::string >` | mOutExtension


### `ServiceReference<GameStore>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<GameStore>` | mService


### `SerialWorkList::WorkItem`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (64) `std::function<enum SerialWorkList::WorkResult __cdecl(void)>` | func
72 | (8) `unsigned __int64` | callCount
80 | (4) `float` | maxSessionTime
84 | (4) `float` | totalExclusiveTime
88 | (4) `float` | totalInclusiveTime


### `ServiceReference<IEntitlementManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<IEntitlementManager>` | mService


### `ScreenEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `ScreenEventType` | type
8 | (56) `ScreenEventData` | data
64 | (1) `ScreenEventScope` | scope
65 | (1) `bool` | localEvent
66 | (1) `bool` | handleMapping
67 | (1) `bool` | swallowTouch


### `ScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (56) `ButtonScreenEventData` | button
1 | (32) `TextEditScreenEventData` | textEdit
2 | (16) `HoverScreenEventData` | hover
3 | (16) `PointerMoveScreenEventData` | pointerMove
4 | (20) `PointerHeldScreenEventData` | pointerHeld
5 | (8) `FocusMoveScreenEventData` | focusMove
6 | (4) `InputModeChangeScreenEventData` | inputMode
7 | (4) `HoloInputModeChangeScreenEventData` | holoInputMode
8 | (8) `ScrollRequestScreenEventData` | scrollRequest
9 | (16) `ScrollDirectionEventData` | scrollDirectionRequest
10 | (32) `ToggleChangeEventData` | toggle
11 | (12) `ControllerDirectionEventData` | controllerDirectionEventData
12 | (8) `RawInputScreenEventData` | rawInput
13 | (24) `SliderChangeEventData` | slider
14 | (4) `AnimationEventData` | animEventData
15 | (1) `LockedStateEventData` | locked
16 | (24) `ClippedCollectionEventData` | clippedCollection
17 | (24) `ClipStateChangeEventData` | clipStateChangeEventData
18 | (12) `TextEditSelectedStateChangeEventData` | textEditSelectedStateChangeEventData
19 | (4) `CustomRendererEventData` | customRendererEventData


### `ScrollRequestScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | delta


### `ScrollDirectionEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | cursorPosition
8 | (8) `float[2]` | deltaPosition


### `SliderChangeEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `int` | index
8 | (4) `float` | value
12 | (1) `bool` | finalized
16 | (8) `UIPropertyBag *` | properties


### `StrongholdFeature::StrongholdResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | success
8 | (8) `ChunkPos` | location


### `ServiceReference<ResourceLoadManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<ResourceLoadManager>` | mService


### `stbtt__buf`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | data
8 | (4) `int` | cursor
12 | (4) `int` | size


### `stbtt__csctx`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | bounds
4 | (4) `int` | started
8 | (4) `float` | first_x
12 | (4) `float` | first_y
16 | (4) `float` | x
20 | (4) `float` | y
24 | (4) `int` | min_x
28 | (4) `int` | max_x
32 | (4) `int` | min_y
36 | (4) `int` | max_y
40 | (8) `stbtt_vertex *` | pvertices
48 | (4) `int` | num_vertices


### `stbtt__bitmap`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | w
4 | (4) `int` | h
8 | (4) `int` | stride
16 | (8) `unsigned __int8 *` | pixels


### `stbtt_fontinfo`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | userdata
8 | (8) `unsigned __int8 *` | data
16 | (4) `int` | fontstart
20 | (4) `int` | numGlyphs
24 | (4) `int` | loca
28 | (4) `int` | head
32 | (4) `int` | glyf
36 | (4) `int` | hhea
40 | (4) `int` | hmtx
44 | (4) `int` | kern
48 | (4) `int` | gpos
52 | (4) `int` | index_map
56 | (4) `int` | indexToLocFormat
64 | (16) `stbtt__buf` | cff
80 | (16) `stbtt__buf` | charstrings
96 | (16) `stbtt__buf` | gsubrs
112 | (16) `stbtt__buf` | subrs
128 | (16) `stbtt__buf` | fontdicts
144 | (16) `stbtt__buf` | fdselect


### `stbtt_packedchar`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | x0
2 | (2) `unsigned __int16` | y0
4 | (2) `unsigned __int16` | x1
6 | (2) `unsigned __int16` | y1
8 | (4) `float` | xoff
12 | (4) `float` | yoff
16 | (4) `float` | xadvance
20 | (4) `float` | xoff2
24 | (4) `float` | yoff2


### `stbtt_pack_context`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | user_allocator_context
8 | (8) `void *` | pack_info
16 | (4) `int` | width
20 | (4) `int` | height
24 | (4) `int` | stride_in_bytes
28 | (4) `int` | padding
32 | (4) `unsigned int` | h_oversample
36 | (4) `unsigned int` | v_oversample
40 | (8) `unsigned __int8 *` | pixels
48 | (8) `void *` | nodes


### `stbtt_pack_range`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | font_size
4 | (4) `int` | first_unicode_codepoint_in_range
8 | (8) `int *` | array_of_unicode_codepoints
16 | (4) `int` | num_chars
24 | (8) `stbtt_packedchar *` | chardata_for_range
32 | (1) `unsigned __int8` | h_oversample
33 | (1) `unsigned __int8` | v_oversample


### `SelectedSlotInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const SlotData *` | mSlot
8 | (4) `const int` | mProgressiveTake


### `ScreenController`
Offset | Type | Name
-|-|-|-
0 | (8) `IScreenController` | baseclass_0
8 | (64) `std::function<void __cdecl(std::string const &,UIPropertyBag const &)>` | mControlCreateCallback
72 | (64) `std::function<void __cdecl(std::string const &,std::string const &)>` | mControlDestroyCallback
136 | (64) `std::function<void __cdecl(std::string const &)>` | mControlDestroyAllCallback
200 | (64) `std::function<void __cdecl(std::string const &)>` | mScreenViewSendManualInputEventCallback
264 | (8) `std::unique_ptr<ScreenControllerProxy>` | mProxy
272 | (1) `bool` | mCreateInitialized
273 | (1) `bool` | mInitialized
280 | (1024) `ScreenViewCommand` | mScreenViewCommand
1304 | (64) `std::unordered_map<std::tuple<unsigned int,enum ButtonState>,std::vector<std::tuple<enum ScreenController::PreviousButtonStateRequirement,std::function<enum ui::ViewRequest __cdecl(UIPropertyBag *)> >>,ScreenController::ButtonEventCallbackKeyHasher,std::equal_to<std::tuple<unsigned int,enum ButtonState> >,std::allocator<std::pair<std::tuple<unsigned int,enum ButtonState> const ,std::vector<std::tuple<enum ScreenController::PreviousButtonStateRequirement,std::function<enum ui::ViewRequest __cdecl(UIPropertyBag *)> >> > > >` | mButtonEventCallbackMap
1368 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(UIPropertyBag *)>>>` | mButtonInteractedEventCallbackMap
1432 | (64) `std::function<enum ui::ViewRequest __cdecl(RawInputScreenEventData &)>` | mRawInputEventHandlerCallback
1496 | (24) `std::vector<std::function<enum ui::ViewRequest __cdecl(FocusMoveScreenEventData &)>>` | mFocusMoveEventCallbacks
1520 | (24) `std::vector<std::function<enum ui::ViewRequest __cdecl(InputModeChangeScreenEventData &)>>` | mInputModeChangedEventCallbacks
1544 | (24) `std::vector<std::function<enum ui::ViewRequest __cdecl(HoloInputModeChangeScreenEventData &)>>` | mHoloInputModeChangedEventCallbacks
1568 | (24) `std::vector<std::function<enum ui::ViewRequest __cdecl(PointerHeldScreenEventData &)>>` | mPointerHeldEventCallbacks
1592 | (64) `std::unordered_map<unsigned int,std::vector<std::tuple<bool,std::function<enum ui::ViewRequest __cdecl(TextEditScreenEventData &,int)> >>>` | mTextEditEventCallbackMap
1656 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(ToggleChangeEventData &)>>>` | mToggleChangeEventCallbackMap
1720 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(TextEditSelectedStateChangeEventData &)>>>` | mTextEditSelectedStateChangeEventCallbackMap
1784 | (24) `std::vector<std::shared_ptr<ScreenController>>` | mSubControllers
1808 | (64) `std::unordered_map<unsigned int,std::vector<std::tuple<bool,std::function<enum ui::ViewRequest __cdecl(int,float)> >>>` | mSliderChangeEventCallbackMap
1872 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(void)>>>` | mAnimationEventCallbackMap
1936 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(int,int,UIPropertyBag &)>>>` | mClippedCollectionEventCallbackMap
2000 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(bool,UIPropertyBag &)>>>` | mClipStateChangeEventCallbackMap
2064 | (64) `std::unordered_map<unsigned int,std::vector<std::function<enum ui::ViewRequest __cdecl(void)>>>` | mCustomRendererEventHandlerCallbackMap
2128 | (64) `std::unordered_map<unsigned int,std::function<void __cdecl(std::string const &,UIPropertyBag &)>>` | mBindCallbacks
2192 | (64) `std::unordered_map<unsigned int,std::function<void __cdecl(int,std::string const &,UIPropertyBag &)>>` | mCollectionBindCallbacks
2256 | (64) `std::unordered_map<unsigned int,std::function<void __cdecl(std::string const &,int,std::string const &,UIPropertyBag &)>>` | mAnyCollectionBindCallbacks
2320 | (8) `std::unique_ptr<TaskGroup>` | mTaskGroup


### `ScreenViewCommand`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(FlyingItemCommand &)>` | sendFlyingItems
64 | (64) `std::function<void __cdecl(SelectNavigationTabCommand &)>` | selectNavigationTab
128 | (64) `std::function<void __cdecl(void)>` | openKeyboard
192 | (64) `std::function<void __cdecl(void)>` | closeKeyboard
256 | (64) `std::function<void __cdecl(std::string const &)>` | selectControl
320 | (64) `std::function<void __cdecl(std::string const &,bool)>` | focusControl
384 | (64) `std::function<void __cdecl(std::string const &)>` | setFocusedTextBoxText
448 | (64) `std::function<bool __cdecl(std::string const &)>` | isFocusWithin
512 | (64) `std::function<bool __cdecl(std::string const &)>` | isSelected
576 | (64) `std::function<void __cdecl(std::string const &,bool)>` | scrollToControl
640 | (64) `std::function<void __cdecl(std::string const &)>` | scrollToControlAndSelect
704 | (64) `std::function<void __cdecl(std::string const &,int)>` | focusCollectionItem
768 | (64) `std::function<bool __cdecl(std::string const &,int,int)>` | scrollToGridItemOffset
832 | (64) `std::function<void __cdecl(std::string const &)>` | resetScrollWithin
896 | (64) `std::function<void __cdecl(std::string const &,std::string const &,int)>` | setFocusToFocusIdWhenVisible
960 | (64) `std::function<void __cdecl(void)>` | prepareFocusForModalPopup


### `ScoreInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `bool` | mValid
12 | (4) `int` | mValue


### `ServiceReference<DateManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<DateManager>` | mService


### `SubpackInfoCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SubpackInfo>` | mSubpackInfo


### `ScoreboardCacheData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (8) `__int64` | mId
40 | (4) `int` | mScore
44 | (1) `_BYTE[1]` | mType


### `ServerFormScreenController::{ctor}::__l2::<lambda_c420b3d9dde99628d68fd9f5e707e82a>::()::__l2::<lambda_281d68185358cc0fc73ff3ed393d8320>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ServerFormScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(Core::Path const &)>` | callback


### `SettingsScreenControllerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(int)>` | mSelectTab
64 | (64) `std::function<std::string __cdecl(void)>` | mGetAdditionalScreenInfo
128 | (64) `std::function<GeneralSettingsScreenControllerProxy * __cdecl(void)>` | mGetGeneralSettingsScreenController
192 | (64) `std::function<std::string __cdecl(void)>` | mGetCurrentTabTitle
256 | (64) `std::function<WorldSettingsScreenControllerProxy * __cdecl(void)>` | mGetWorldSettingsScreenController


### `SettingsScreenController::_registerEventHandlers::__l2::<lambda_e7cffde8d07f346efec15a9f629adc2d>`
Offset | Type | Name
-|-|-|-
0 | (8) `SettingsScreenController *const` | __this
8 | (40) `const SettingsScreenCapabilities` | capabilities


### `SettingsScreenCapabilities`
Offset | Type | Name
-|-|-|-
0 | (8) `TypedScreenCapabilities<SettingsScreenCapabilities>` | baseclass_0
8 | (1) `bool` | mWorldSectionIgnored
9 | (1) `bool` | mGlobalResourcesSectionIgnored
10 | (1) `bool` | mStorageSectionIgnored
11 | (1) `bool` | mControllerLayoutIgnored
12 | (1) `bool` | mSwitchAccountsButtonIgnored
13 | (1) `bool` | mSSOToggleIgnored
14 | (1) `bool` | mChatScreenInputsIgnored
16 | (24) `std::vector<std::string>` | mDisabledInputMappings


### `SettingsScreenControllerBase::setupCallbacksForStringOption::__l2::<lambda_b07a1af5566bb31a8be96ce36d1c76fc>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::string __cdecl(void)>` | getValue


### `SettingsScreenControllerBase::setupCallbacksForStringOption::__l2::<lambda_7e24beb4c048526995bf6b613ba977e4>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(std::string const &)>` | setValue
64 | (64) `std::function<bool __cdecl(std::string const &)>` | changedValidator
128 | (64) `std::function<bool __cdecl(void)>` | isEnabled


### `SettingsScreenControllerBase::setUpCallbacksForBooleanOption::__l2::<lambda_649d2d084df48e8c21a2219060ac83ac>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | option
8 | (32) `const std::string` | toggleName


### `SettingsScreenControllerBase::setUpCallbacksForBooleanOption::__l2::<lambda_13beeeda3122f2d8143eb7d4a2012b88>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(void)>` | getValue


### `StorageManagementScreenController::ContentTab`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | prefix
32 | (8) `ContentView *` | view
40 | (1) `bool` | expanded


### `StorageManagementScreenController::_registerBindings::__l10::<lambda_e36cc80f2a5d6c86836293d3d7a510d9>`
Offset | Type | Name
-|-|-|-
0 | (8) `StorageManagementScreenController::ContentTab *` | tab


### `StorageDependencyScreenController::createDepdendencyPopup::__l5::<lambda_852e9a4d9eb0d18e43dff83399d74bbf>`
Offset | Type | Name
-|-|-|-
0 | (8) `StorageDependencyScreenController *const` | __this
8 | (64) `std::function<void __cdecl(enum ModalScreenButtonId)>` | callback


### `SubscriptionsScreenController::_getRealmSubscriptionFromWorld::__l2::<lambda_5cdf67128f3bea6159dd8fc163d38d57>`
Offset | Type | Name
-|-|-|-
0 | (8) `Realms::RealmId` | realmId
8 | (1) `bool` | realmsPlusWorld
16 | (16) `std::weak_ptr<SubscriptionsScreenController>` | weakThis


### `ScreenViewProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<VisualTreeProxy * __cdecl(void)>` | mGetVisualTree
64 | (64) `std::function<FocusManagerProxy * __cdecl(void)>` | mGetFocusManager
128 | (64) `std::function<bool __cdecl(void)>` | mIsInitialized
192 | (64) `std::function<bool __cdecl(std::string const &,ScreenEvent &)>` | mTestAutomationHandleRawInputEvent


### `SweepResult`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<UIControl>` | collision


### `SweepDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,0>` | origin
8 | (8) `glm::tvec2<float,0>` | dirOrigin
16 | (4) `float` | halfAngleCos
20 | (1) `ui::CardinalDirection` | direction
24 | (16) `std::shared_ptr<UIControl>` | ignoreControl
40 | (1) `bool` | canWrap
41 | (1) `bool` | respectClipping
44 | (16) `RectangleArea` | controlBoundary
60 | (16) `RectangleArea` | sweepBoundary


### `ScreenCuller`
Offset | Type | Name
-|-|-|-
0 | (192) `Frustum` | mFrustum


### `SkinRepository::loadSkinPackAsync::__l2::<lambda_4884fa209f3dd3288358f533e94823d9>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepository *const` | __this
8 | (16) `const mce::UUID` | packId
24 | (960) `const SkinPackMeta` | metadata


### `SkinPackMeta`
Offset | Type | Name
-|-|-|-
0 | (584) `CommonDocument` | mCommon
584 | (368) `DurableCustom` | mCustom
952 | (1) `bool` | isHidden


### `SkinRepositoryClientInterface::pickCustomSkin::__l2::<lambda_ebc291d69d17bbd2739c441c4eab9845>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (64) `std::function<void __cdecl(enum PickCustomSkinResult)>` | onPickCustomSkin


### `SceneFactory::createUIScene::__l18::<lambda_ad9193836c0ea19e914606f0c72a1f8e>`
Offset | Type | Name
-|-|-|-
0 | (8) `VisualTree *` | visualTree
8 | (16) `std::shared_ptr<UIControlFactory>` | controlFactory
24 | (32) `const std::string` | screenName
56 | (8) `LayoutManager *` | layout
64 | (24) `ScreenSizeData` | size
88 | (8) `UIMeasureStrategy *` | uiMeasureStrategy
96 | (32) `SceneFactory::createUIScene::__l2::<lambda_bdf3b827e5dc52ddbb6699b3cb5b3ebe>` | textureLoadSpiner


### `ScreenSizeData`
Offset | Type | Name
-|-|-|-
0 | (8) `Vec2` | totalScreenSize
8 | (8) `Vec2` | clientScreenSize
16 | (8) `Vec2` | clientUIScreenSize


### `SceneFactory::createUIScene::__l2::<lambda_bdf3b827e5dc52ddbb6699b3cb5b3ebe>`
Offset | Type | Name
-|-|-|-
0 | (8) `SceneFactory *const` | __this
8 | (16) `std::shared_ptr<gsl::final_action<std::function<void __cdecl(void)> > >` | finalAction
24 | (8) `IMinecraftGame *` | mc


### `SceneFactory::createUIScene::__l2::<lambda_f7b87fe8f31baed6fb7df6e9fc16ea4c>`
Offset | Type | Name
-|-|-|-
0 | (1) `const bool` | loadScreenNow
8 | (64) `std::function<TaskResult __cdecl(bool)>` | task


### `SceneFactoryProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateAchievementsScreen
64 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateAddEditExternalServerScreen
128 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(LevelSummary const &)>` | mCreateEditWorldScreen
192 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateHowToPlayScreen
256 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(enum CraftingType)>` | mCreateInventoryScreen
320 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateNewRealmScreen
384 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateNXSignInScreen
448 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(enum SettingsTabIndex)>` | mCreateOptionsScreen
512 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(enum PlayScreenDefaultTab)>` | mCreatePlayScreen
576 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateSkinPickerScreen
640 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(bool)>` | mCreateStartMenuScreen
704 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(std::string const &)>` | mCreateStoreHomeScreen
768 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreatePauseScreen
832 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateWorldScreen
896 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateWorldTemplateScreen
960 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateWorldUpsellScreen
1024 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateXboxSignInScreen
1088 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateChatScreen
1152 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateDeathScreen
1216 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateCreditsScreen
1280 | (64) `std::function<std::shared_ptr<AbstractScene> __cdecl(void)>` | mCreateGlobalPauseScreen
1344 | (64) `std::function<std::shared_ptr<MainMenuScreenModel> __cdecl(void)>` | mCreateMainMenuScreenModel


### `SceneFactory::createAchievementScreen::__l2::<lambda_75466363780256f04be3b12cd4862d30>`
Offset | Type | Name
-|-|-|-
0 | (8) `SceneFactory *const` | __this
8 | (8) `ISceneStack *` | stack
16 | (32) `const std::string` | achievementDeepLinkId


### `SceneFactory::createSceneFromUrl::__l2::<lambda_7a50495d96f6fa0223db03711ef77471>`
Offset | Type | Name
-|-|-|-
0 | (8) `SceneFactory *const` | __this


### `SceneFactory::createSceneFromUrl::__l2::<lambda_2c129547f4eb785503e32024ad3cea47>`
Offset | Type | Name
-|-|-|-
0 | (8) `SceneFactory *const` | __this


### `SceneFactory::_preCacheScreen::__l5::<lambda_5475fd3f06752852ce17dc9fafaae368>`
Offset | Type | Name
-|-|-|-
0 | (40) `SceneFactory::_preCacheScreen::__l5::<lambda_eb0418b1e2b48e33230d326c46b49fe8>` | asyncTask
40 | (24) `SceneFactory::_preCacheScreen::__l5::<lambda_26218586035ff86053a04bccb33794fe>` | callback


### `SceneFactory::_preCacheScreen::__l5::<lambda_eb0418b1e2b48e33230d326c46b49fe8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SceneFactory::PreCachePackage>` | weakPackage
16 | (24) `ScreenSizeData` | size


### `SceneFactory::_preCacheScreen::__l5::<lambda_26218586035ff86053a04bccb33794fe>`
Offset | Type | Name
-|-|-|-
0 | (8) `SceneFactory *const` | __this
8 | (16) `std::weak_ptr<SceneFactory::PreCachePackage>` | weakPackage


### `SceneStackProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(std::function<void __cdecl(AbstractScene &)>)>` | mForEachAlwaysAcceptInputScreenWithTop
64 | (64) `std::function<std::weak_ptr<AbstractSceneProxy> __cdecl(void)>` | mGetScreen
128 | (64) `std::function<std::string __cdecl(void)>` | mGetScreenName
192 | (64) `std::function<bool __cdecl(void)>` | mHasScheduledScreens
256 | (64) `std::function<void __cdecl(std::shared_ptr<AbstractScene>,bool)>` | mPushScreen
320 | (64) `std::function<void __cdecl(void)>` | mSchedulePopScreen
384 | (64) `std::function<bool __cdecl(std::string)>` | mScreenOnStack
448 | (64) `std::function<bool __cdecl(void)>` | mGetScreenTicking
512 | (64) `std::function<void __cdecl(bool)>` | mSetScreenTicking
576 | (64) `std::function<bool __cdecl(void)>` | mUpdate


### `ScreenController::bindString::__l2::<lambda_637346be989b4c387b25a023e4c50a19>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<std::string __cdecl(void)>` | callback


### `ScreenController::bindBool::__l2::<lambda_98a591b06e11514cd0729875041c2864>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<bool __cdecl(void)>` | callback


### `ScreenController::bindInt::__l2::<lambda_65b8f135cfd9eee96e8adc74ceb3a47b>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<int __cdecl(void)>` | callback


### `ScreenController::bindFloat::__l2::<lambda_0fb14b10bd2d4d05590cce0a8f71cea9>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<float __cdecl(void)>` | callback


### `ScreenController::bindGridSize::__l2::<lambda_44781a3a7259cd73563916bd500c22a3>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<glm::tvec2<int,0> __cdecl(void)>` | callback


### `ScreenController::bindColor::__l2::<lambda_71daed87eaabe04495df376596f58d57>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(void)>` | condition
64 | (64) `const std::function<mce::Color __cdecl(void)>` | callback


### `ScreenController::bindFloatForCollection::__l2::<lambda_223083f257fe3cccc2536db1405cc5e0>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<float __cdecl(int)>` | callback


### `ScreenController::bindStringForAnyCollection::__l2::<lambda_31cbdbd7cec8ef564e716a4e0237f5e4>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<std::string __cdecl(std::string const &,int)>` | callback


### `ScreenController::bindBoolForAnyCollection::__l2::<lambda_ae59d9ba61e4ce0a8046dc3649d21f6f>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | callback


### `ScreenController::bindIntForAnyCollection::__l2::<lambda_be6a73063a11417ea19dc8f0e00c7d4f>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<int __cdecl(std::string const &,int)>` | callback


### `ScreenController::bindFloatForAnyCollection::__l2::<lambda_d0cd1827bf2646dcfecdabd3c03663fc>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<float __cdecl(std::string const &,int)>` | callback


### `ScreenController::bindForAnyCollection::__l2::<lambda_3e00cdd5c08afa9bc2f2639ee2ff40c2>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<void __cdecl(int,std::string const &,UIPropertyBag &)>` | callback


### `ScreenController::bindForAnyCollection::__l2::<lambda_e0768ab872b28fe3baa25f2a9efb0443>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(std::string const &,int)>` | condition
64 | (64) `const std::function<void __cdecl(std::string const &,int,std::string const &,UIPropertyBag &)>` | callback


### `ScreenInputContext`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ScreenEvent>` | mEvents
24 | (24) `std::vector<ButtonUpRightOfFirstRefusalRequest>` | mButtonUpRightOfFirstRefusalRequests


### `ScreenView::_passViewCommand::__l2::<lambda_93c65d98a224a7189057352f2adde7a9>::()::__l2::<lambda_2d32da526ec4782697106d510a4cf701>`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,0> *` | originPosition
8 | (8) `glm::tvec2<float,0> *` | destinationPosition
16 | (8) `bool *` | originFound
24 | (8) `bool *` | destinationFound
32 | (8) `float *` | originScale
40 | (8) `float *` | destinationScale
48 | (8) `FlyingItemCommand *` | command


### `ScreenView::_passViewCommand::__l2::<lambda_ac84362c2fc48afe21d9ba36b9bee780>::()::__l7::<lambda_19ffe1652e69a43d03797558e1bfa97c>`
Offset | Type | Name
-|-|-|-
0 | (40) `ScreenView::_passViewCommand::__l2::<lambda_ac84362c2fc48afe21d9ba36b9bee780>::()::__l2::<lambda_ec6a1eeb66f00bc93da838a31f086452>` | focusCommand


### `ScreenView::_passViewCommand::__l2::<lambda_ac84362c2fc48afe21d9ba36b9bee780>::()::__l2::<lambda_ec6a1eeb66f00bc93da838a31f086452>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenView *const` | __this
8 | (32) `const std::string` | controlName


### `ScreenView::_passViewCommand::__l2::<lambda_8531114544531f8d9afa78ddfccd4350>::()::__l5::<lambda_4a6597b1821b24edfbbf4b4ee4b10bc7>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenView::_passViewCommand::__l2::<lambda_8531114544531f8d9afa78ddfccd4350>::()::__l2::<lambda_b59ab18380bd03e7578d33d6d3a7ab61>` | tabNavigationCallback
8 | (48) `SelectNavigationTabCommand` | command


### `ScreenView::_passViewCommand::__l2::<lambda_8531114544531f8d9afa78ddfccd4350>::()::__l2::<lambda_b59ab18380bd03e7578d33d6d3a7ab61>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenView *const` | __this


### `SelectNavigationTabCommand`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | navigationTabIndex
8 | (32) `std::string` | navigationTabName
40 | (1) `bool` | success
41 | (1) `bool` | maintainOldFocus


### `ScreenController::bindIntForCollection::__l2::<lambda_f9e2e2e7b8304f39ac84a40451779042>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<bool __cdecl(int)>` | condition
64 | (64) `const std::function<int __cdecl(int)>` | callback


### `ScreenView::_passViewCommand::__l2::<lambda_727b71b870d5f42264879f25630d1d44>::()::__l2::<lambda_d32be51470d88502a92d141e471d9e09>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenView::_passViewCommand::__l2::<lambda_19b77a382f571e532765a35e4fd287ea>` | scrollToGridItemOffset
8 | (32) `const std::string` | collectionName
40 | (4) `int` | collectionIndex
44 | (4) `int` | numItems


### `ScreenView::_passViewCommand::__l2::<lambda_19b77a382f571e532765a35e4fd287ea>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenView *const` | __this


### `Social::XboxLiveIdentity::signIn::__l17::<lambda_9f7d45a869e41ae635151b0458651e01>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::XboxLiveIdentity>` | weakThis
16 | (64) `std::function<void __cdecl(Social::SingleIdentitySignInResult)>` | callback


### `Social::XboxLiveIdentity::signIn::__l19::<lambda_67943a87e469b1364289dddd8839232e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::XboxLiveIdentity>` | weakThis
16 | (64) `std::function<void __cdecl(Social::SingleIdentitySignInResult)>` | callback


### `Social::XboxLiveIdentity::signOut::__l5::<lambda_d7f005516538f9b78b33e93a1bef05bd>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::XboxLiveIdentity>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | callback


### `ScreenRenderer`
Offset | Type | Name
-|-|-|-


### `StackRefResultT<EntityRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `StackResultStorageEntity` | baseclass_0


### `StackResultStorageEntity`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<EntityContext>` | mContext


### `ServiceReference<Social::MultiplayerServiceManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<Social::MultiplayerServiceManager>` | mService


### `ServiceReference<ChunkPerformanceData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<ChunkPerformanceData>` | mService


### `ServiceReference<GameRelightingTestData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<GameRelightingTestData>` | mService


### `Social::Events::Property`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (16) `Json::Value` | mValue


### `ServiceReference<mce::FileWatcherNull>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<mce::FileWatcherNull>` | mService


### `SkinRepository::loadSkinPack::__l2::<lambda_8c1eeeeaa04463bff8a93f30eef087af>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepository *const` | __this
8 | (16) `const mce::UUID` | packId
24 | (8) `bool *` | successfulLoad
32 | (64) `std::function<void __cdecl(void)>` | callback


### `SkinRepositoryClientInterface::_getReloadCallback::__l2::<lambda_846de32044adc214daef4861df24efff>`
Offset | Type | Name
-|-|-|-
0 | (8) `const SkinRepositoryClientInterface *const` | __this
8 | (4) `persona::ProfileType` | profileType
16 | (64) `std::function<void __cdecl(SkinHandle)>` | cb


### `SkinRepositoryClientInterface::tryFullPersonaReload::__l5::<lambda_1ed64e594555dfc39033a7d296bb8ee4>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (64) `std::function<void __cdecl(SkinHandle)>` | cb


### `SkinRepositoryClientInterface::updatePersonaFromAppearance::__l2::<lambda_b3352670756ecc0ec5561e2be7c4a035>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (16) `std::weak_ptr<bool>` | weakExistance
24 | (40) `const persona::PersonaCharacterHandle` | personaToUpdateHandle
64 | (64) `std::function<void __cdecl(SkinHandle)>` | syncCompletedCallback


### `SkinRepositoryClientInterface::_setSelectedAppearance::__l2::<lambda_8e0eea89dcb2aebf5e193f6af928111b>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (16) `std::weak_ptr<bool>` | weakExistance
24 | (64) `std::function<void __cdecl(SkinHandle)>` | requestCallback
88 | (112) `SkinHandle` | newAppearanceHandle


### `SkinRepositoryClientInterface::_setPendingAppearance::__l2::<lambda_2cbdc008895cad531a7677657fc5960b>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (64) `std::function<void __cdecl(SkinHandle)>` | callback


### `SkinRepositoryClientInterface::createPersona::__l2::<lambda_d54e64862f49427c8dc912d11abd5afc>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (4) `persona::ProfileType` | profileType
16 | (16) `std::weak_ptr<bool>` | weakExistance
32 | (64) `std::function<void __cdecl(void)>` | cb


### `SkinRepositoryClientInterface::tryFullPersonaReload::__l5::<lambda_1ed64e594555dfc39033a7d296bb8ee4>::()::__l2::<lambda_85e6ae7f28a76659b894f16127b59f1c>`
Offset | Type | Name
-|-|-|-
0 | (8) `SkinRepositoryClientInterface *const` | __this
8 | (4) `persona::ProfileType` | profileType
16 | (64) `std::function<void __cdecl(SkinHandle)>` | syncCb


### `SpawnEggInfo`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mTextureName
48 | (4) `unsigned int` | mTextureIndex
52 | (16) `mce::Color` | mEggBaseTint
68 | (16) `mce::Color` | mEggOverlayTint


### `SignBlockActor::CachedMessageData`
Offset | Type | Name
-|-|-|-
0 | (160) `SignBlockActor::CachedLineData[4]` | lineData
160 | (4) `unsigned int` | numLines
168 | (32) `std::string` | filteredMessage
200 | (8) `const void *` | cachedFontCompare
208 | (1) `bool` | dirty


### `SignBlockActor::CachedLineData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | text
32 | (4) `int` | lineLength


### `SubChunkBrightnessStorage::LightPair`
Offset | Type | Name
-|-|-|-
0 | (1) `$CE66EAFC7D8A60AB08C0D612611BAB18` | ___u0


### `SubChunkBlockPos`
Offset | Type | Name
-|-|-|-
0 | (4) `$F965259FE24EEE58D216369F5461A2B9` | ___u0


### `SkyRenderObject`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::Mesh>` | mSkyMesh
16 | (16) `std::shared_ptr<mce::Mesh>` | mStarsMesh
32 | (16) `std::shared_ptr<mce::Mesh>` | mSunMesh
48 | (16) `std::shared_ptr<mce::Mesh>` | mMoonMesh
64 | (72) `mce::TexturePtr` | mEndSkyTex
136 | (72) `mce::TexturePtr` | mSunTex
208 | (72) `mce::TexturePtr` | mMoonTex
280 | (16) `std::shared_ptr<mce::Mesh>` | mMilkyWayMesh
296 | (72) `mce::TexturePtr` | mMilkyWayTex
368 | (16) `std::shared_ptr<mce::Mesh>` | mMeteorMesh
384 | (72) `mce::TexturePtr` | mMeteorTex
456 | (4) `int` | mTime
464 | (40) `std::vector<mce::TexturePtr,LinearAllocator<mce::TexturePtr> >` | mCubemapTextures
504 | (16) `mce::ServerTexture` | mCubemapTexture
520 | (8) `const mce::MaterialPtr *` | mCubemapMaterial
528 | (8) `const mce::MaterialPtr *` | mSkyMaterial
536 | (8) `const mce::MaterialPtr *` | mStarsMaterial
544 | (8) `const mce::MaterialPtr *` | mSunMoonMaterial
552 | (4) `float` | mStarBrightness
556 | (4) `float` | mSunAngleOne
560 | (4) `float` | mSunAngleA
564 | (4) `float` | mFogLevel
568 | (4) `float` | mAmbientBrightness
572 | (4) `float` | mSkyDarken


### `Sound`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `float` | mVolumeMin
36 | (4) `float` | mPitchMin
40 | (4) `float` | mVolumeMax
44 | (4) `float` | mPitchMax


### `stbi__context`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | img_x
4 | (4) `unsigned int` | img_y
8 | (4) `int` | img_n
12 | (4) `int` | img_out_n
16 | (24) `stbi_io_callbacks` | io
40 | (8) `void *` | io_user_data
48 | (4) `int` | read_from_callbacks
52 | (4) `int` | buflen
56 | (128) `unsigned __int8[128]` | buffer_start
184 | (8) `unsigned __int8 *` | img_buffer
192 | (8) `unsigned __int8 *` | img_buffer_end
200 | (8) `unsigned __int8 *` | img_buffer_original
208 | (8) `unsigned __int8 *` | img_buffer_original_end


### `ScriptApi::ScriptObjectHandle`
Offset | Type | Name
-|-|-|-


### `ScriptApi::EMPTYObjectHandle`
Offset | Type | Name
-|-|-|-


### `ScriptEngineWithContext<ScriptServerContext>::createEntity::__l2::<lambda_5a64297f6fe45bc0c8cf434a3b0c3a8e>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScriptEngineWithContext<ScriptServerContext> *const` | __this
8 | (8) `ScriptApi::ScriptObjectHandle *` | entityHandle
16 | (8) `const std::string *` | templateName
24 | (8) `const ScriptApi::ScriptVersionInfo *` | info


### `ScriptOnlyComponents<ScriptServerContext>::ScriptOnly`
Offset | Type | Name
-|-|-|-
0 | (16) `std::map<std::string,Json::Value>` | mLookup


### `ScheduledCallback`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | mTime
8 | (16) `std::weak_ptr<bool>` | mExistenceTracker
24 | (64) `std::function<void __cdecl(void)>` | mCallback
88 | (1) `bool` | mShouldCheckExistence


### `ServiceReference<Social::IUserManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<Social::IUserManager>` | mService


### `Social::MultiplayerService::disable::__l2::<lambda_31436da694b5c017c7d349683e2977e2>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerService *const` | __this
8 | (64) `std::function<void __cdecl(bool)>` | callback


### `Social::User::_finalizeSignIn::__l2::<lambda_5696a71c87ad7a8bea0790eaa1d241d0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::User>` | weakThis
16 | (24) `std::vector<std::pair<enum Social::IdentityType,std::function<void __cdecl(Social::MultiIdentitySigninResult const &)> >>` | finishCallbacks
40 | (56) `Social::MultiIdentitySigninResult` | overallResult
96 | (24) `std::vector<enum Social::IdentityType>` | signedInTypes
120 | (16) `std::set<enum Social::IdentityType>` | attemptedTypes


### `Social::MultiIdentitySigninResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSuccess
1 | (1) `bool` | mIsNewAccount
8 | (32) `std::string` | mGamertagHint
40 | (8) `_BYTE[8]` | mFailingType
48 | (4) `_BYTE[4]` | mFailureReason


### `Social::User::signOut::__l5::<lambda_ac64b0e11f97b4360e14fc032f1729bc>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::User>` | weakThis
16 | (8) `_BYTE[8]` | identitySignOut
24 | (64) `std::function<void __cdecl(bool)>` | callback


### `Social::User::signOut::__l5::<lambda_ac64b0e11f97b4360e14fc032f1729bc>::()::__l5::<lambda_f18b942071897347fd596a3a2426c05c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::User>` | weakThis
16 | (8) `_BYTE[8]` | identitySignOut
24 | (64) `std::function<void __cdecl(bool)>` | callback


### `ServiceRegistrationToken<Social::UserManager>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::UserManager *` | mService


### `Social::UserManager::addSecondaryUserAsync::__l2::<lambda_f5201caa93f780558c3e4fa920a2799b>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::UserManager *const` | __this
8 | (16) `std::shared_ptr<Social::UserCreationData>` | secondaryUserCreationData
24 | (64) `std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>` | callback


### `Social::UserManager::_notifyIdentityListenerList::__l9::<lambda_08b4e833884a368042d959555106c693>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<void __cdecl(unsigned int,enum Social::IdentityType)>` | listener
64 | (4) `unsigned int` | userId
72 | (8) `_BYTE[8]` | identity


### `Social::User::connectAsync::__l2::<lambda_5089e7f6c48e2348c0833f193542bf3a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>` | callback
64 | (8) `Social::User *const` | __this


### `Social::XboxLiveUserInfo::XboxLiveLimitTimer`
Offset | Type | Name
-|-|-|-
0 | (80) `BasicTimer` | mBurstTimer
80 | (80) `BasicTimer` | mSustainTimer
160 | (4) `unsigned int` | mBurstRequests
164 | (4) `unsigned int` | mSustainRequests


### `SoundItem`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mLoadFromMemory
8 | (32) `std::string` | mResourceStream
40 | (32) `Core::PathBuffer<std::string >` | mSoundName
72 | (4) `float` | mVolume
76 | (4) `float` | mPitch
80 | (4) `float` | mMinDistance
84 | (4) `float` | mMaxDistance
88 | (1) `bool` | mStream
89 | (1) `bool` | mIs3D
90 | (1) `bool` | mInterruptible
91 | (1) `bool` | mUseLegacyMaxDistance


### `SoundEngine::_loadSoundItemAsync::__l2::<lambda_4daf6abd0616190312d5e6f10b63bbb4>`
Offset | Type | Name
-|-|-|-
0 | (8) `SoundEngine *const` | __this
8 | (96) `const SoundItem` | soundItem


### `SoundEngine::load::__l2::<lambda_c9086c560484b97729a5fad5c773e501>`
Offset | Type | Name
-|-|-|-
0 | (8) `SoundEngine *const` | __this
8 | (16) `std::shared_ptr<std::vector<std::pair<std::string,std::shared_ptr<SoundEvent> >> >` | soundEvents
24 | (32) `std::string` | currentMusicEventName
56 | (32) `Core::PathBuffer<std::string >` | currentMusicItemName
88 | (16) `std::shared_ptr<bool>` | fadeOutMusic


### `SoundDefinitionsJsonMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (112) `JsonMergeStrategy` | baseclass_0


### `ServiceRegistrationToken<OfferRepository>`
Offset | Type | Name
-|-|-|-
0 | (8) `OfferRepository *` | mService


### `StoreCatalogRepository::fetchRealmsCoinOffers::__l2::<lambda_4414f3671be2def991047236b7ca18b5>`
Offset | Type | Name
-|-|-|-
0 | (8) `StoreCatalogRepository *const` | __this
8 | (64) `std::function<void __cdecl(void)>` | fetchCompleteCallback


### `SearchQuery::SortParams`
Offset | Type | Name
-|-|-|-
0 | (4) `const SearchQuery::SortBy` | mSortBy
4 | (4) `const SearchQuery::SortDirection` | mSortByDir


### `StoreSearchObject::registerEventHandlers::__l2::<lambda_307276f4b78df759eec4cfa8d3251d68>::()::__l2::<lambda_c330bcbc9013ca66f9d3f3ae637c31f8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<StoreSearchObject>` | weakThis
16 | (616) `StoreSearchQuery` | copyBaseQuery


### `StoreSearchObject::_createAndSendSearchQuery::__l2::<lambda_27308452179dc61d81a0e9047a1dad48>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<StoreSearchObject>` | weakThis
16 | (616) `StoreSearchQuery` | searchQuery


### `StoreSearchObject::_createAndSendSearchQuery::__l2::<lambda_ca3540f5454877ae825cd4cf75c35a2a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<StoreSearchObject>` | weakThis
16 | (616) `StoreSearchQuery` | searchQuery


### `StoreSearchSort::SortToggleInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | mLabel
32 | (8) `const SearchQuery::SortParams` | mSortParams
40 | (1) `bool` | mIsActiveSort


### `SaveContainer::queryIsContainerOutOfDate::__l7::<lambda_cfa8e7d91bf2acf9de79c49b366008ca>`
Offset | Type | Name
-|-|-|-
0 | (8) `SaveContainer *const` | __this
8 | (64) `std::function<void __cdecl(Core::Result)>` | onComplete
72 | (16) `std::weak_ptr<bool>` | weakTracker


### `ServerPlayerMovementComponent`
Offset | Type | Name
-|-|-|-
0 | (40) `std::deque<PlayerAuthInputPacket>` | mQueuedUpdates


### `Social::Events::Event`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | mUserId
8 | (32) `const std::string` | mName
40 | (1) `bool` | mShouldAggregate
44 | (4) `unsigned int` | mCustomAggregationTime
48 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mEventCreationTime
56 | (4) `int` | mEventTags
64 | (64) `std::unordered_map<std::string,Social::Events::Property>` | mProperties
128 | (64) `std::unordered_map<std::string,Social::Events::Measurement>` | mMeasurements
192 | (1) `bool` | mRecordStamped


### `Social::Events::Measurement`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (16) `Json::Value` | mValue
48 | (4) `int` | mValueDivisorForAverage
52 | (4) `_BYTE[4]` | mType


### `SharedPtr<Item>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<Item> *` | pc


### `SerializerTraits`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isRequired
1 | (1) `bool` | isPrimary
8 | (32) `std::string` | jsonName
40 | (32) `std::string` | nbtName
72 | (8) `unsigned __int64` | arrayLengthConstraintMin
80 | (8) `unsigned __int64` | arrayLengthConstraintMax
88 | (8) `entt::meta_any *(__fastcall *)(entt::meta_any *result, const std::string *)` | construct
96 | (8) `entt::meta_any *(__fastcall *)(entt::meta_any *result, const std::string *, void *)` | getAny
104 | (8) `void (__fastcall *)(entt::meta_any)` | serializeBegin
112 | (8) `void (__fastcall *)(entt::meta_any)` | serializeEnd
120 | (64) `std::function<bool __cdecl(entt::meta_any &,Serializer &)>` | validate
184 | (8) `const SerializerEnumMapping *` | mEnumMapping
192 | (32) `std::string` | documentation


### `Serializer`
Offset | Type | Name
-|-|-|-
0 | (8) `Serializer_vtbl *` | __vftable
8 | (4) `SerializerDirection` | mDirection
16 | (48) `SerializerContext` | mContext


### `SerializerContext`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mContextStack
24 | (24) `std::vector<std::string>` | mErrorMessages


### `SharedPtr<BlockLegacy>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockLegacy> *` | pc


### `StackRefResultT<SharePtrRefTraits<FogDefinition const > >`
Offset | Type | Name
-|-|-|-
0 | (16) `StackResultStorageSharePtr<FogDefinition const >` | baseclass_0


### `StackResultStorageSharePtr<FogDefinition const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<FogDefinition const >` | mValue


### `SlotDescriptor`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSlot
8 | (24) `std::vector<ItemDescriptor>` | mAcceptedItems
32 | (80) `ItemDescriptor` | mItemDescriptor
112 | (32) `std::string` | mInteractText
144 | (320) `DefinitionTrigger` | mOnEquip
464 | (320) `DefinitionTrigger` | mOnUnequip


### `SeatDescription`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPosition
12 | (4) `int` | mMinSeatCount
16 | (4) `int` | mMaxSeatCount
24 | (216) `ExpressionNode` | mSeatRotation
240 | (1) `bool` | mLockRiderRotation
244 | (4) `float` | mLockRiderRotationDegrees


### `SpawnActorParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSpawnTimeMin
4 | (4) `int` | mSpawnTimeMax
8 | (4) `LevelSoundEvent` | mSpawnSound
16 | (80) `ItemDescriptor` | mItemDescriptor
96 | (32) `std::string` | mEntityDefinition
128 | (32) `std::string` | mSpawnMethod
160 | (64) `ActorFilterGroup` | mFilters
224 | (1) `bool` | mSingleUse
225 | (1) `bool` | mShouldLeash
228 | (4) `int` | mNumToSpawn


### `Social::Events::EventManager::recordEvent::__l2::<lambda_19d1731b0844f50611fd86fdcc1079df>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::Events::EventManager *const` | __this
8 | (200) `Social::Events::Event` | event


### `ServiceRegistrationToken<IMinecraftEventing>`
Offset | Type | Name
-|-|-|-
0 | (8) `IMinecraftEventing *` | mService


### `ShortTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (2) `__int16` | data


### `StringTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (32) `std::string` | data


### `sockaddr`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | sa_family
2 | (14) `char[14]` | sa_data


### `SyncedAttribute`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `float` | mMinValue
36 | (4) `float` | mCurrentValue
40 | (4) `float` | mMaxValue


### `ShapedRecipe`
Offset | Type | Name
-|-|-|-
0 | (208) `Recipe` | baseclass_0
208 | (24) `std::vector<RecipeIngredient>` | mIngredients
232 | (24) `std::vector<ItemInstance>` | mResults


### `ScoreboardIdentityPacketInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (8) `PlayerScoreboardId` | mPlayerId


### `ScorePacketInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (32) `std::string` | mObjectiveName
48 | (4) `int` | mScoreValue
52 | (1) `_BYTE[1]` | mIdentityType
56 | (8) `PlayerScoreboardId` | mPlayerId
64 | (8) `ActorUniqueID` | mEntityId
72 | (32) `std::string` | mFakePlayerName


### `SubClientConnectionRequest`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<UnverifiedCertificate>` | mCertificateData
8 | (8) `std::unique_ptr<Certificate>` | mCertificate
16 | (8) `std::unique_ptr<WebToken>` | mRawToken


### `ServerNetworkHandler::disconnectClient::__l2::<lambda_8ab8e04d16e80d5ccda0091a8639a009>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *const` | __this
8 | (152) `const NetworkIdentifier` | id
160 | (1) `unsigned __int8` | subId
168 | (32) `std::string` | messageCopy
200 | (1) `bool` | skipMessage


### `ServerNetworkHandler::handle::__l36::<lambda_d652cba9d3ff6790348d747c18e71ce4>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *const` | __this
8 | (168) `const CommandBlockUpdatePacket` | packet


### `StructureTemplate`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (176) `StructureTemplateData` | mStructureTemplateData
208 | (1) `unsigned __int8` | mStructureVersion


### `StructureTemplateData`
Offset | Type | Name
-|-|-|-
0 | (8) `StructureTemplateData_vtbl *` | __vftable
8 | (4) `int` | mFormatVersion
12 | (12) `BlockPos` | mSize
24 | (12) `BlockPos` | mStructureWorldOrigin
40 | (24) `std::vector<int>` | mBlockIndices
64 | (24) `std::vector<int>` | mExtraBlockIndices
88 | (64) `std::unordered_map<std::string,StructureBlockPalette>` | mPalettes
152 | (24) `std::vector<std::unique_ptr<CompoundTag>>` | mEntityData


### `StructureTemplateDataResponsePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mStructureName
72 | (8) `std::unique_ptr<CompoundTag>` | mStructureTag
80 | (1) `StructureTemplateResponseType` | mResponseType


### `ServiceReference<ServerInstance>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<ServerInstance>` | mService


### `ServerNetworkHandler::handle::__l2::<lambda_9d52b3aa3d855da2c243e137c204abab>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *const` | __this
8 | (152) `const NetworkIdentifier` | source
160 | (16) `std::shared_ptr<BlockActorDataPacket>` | packet
176 | (1) `const bool` | shouldFilterText


### `ServerNetworkHandler::handle::__l8::<lambda_b228fbb676f614edf5a86d27a92c8ccc>`
Offset | Type | Name
-|-|-|-
0 | (160) `ServerNetworkHandler::handle::__l2::<lambda_ace92a5bcd49f90761b20503b23bdc43>` | callback
160 | (152) `BookEditPacket` | packet


### `ServerNetworkHandler::handle::__l2::<lambda_ace92a5bcd49f90761b20503b23bdc43>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *const` | __this
8 | (152) `const NetworkIdentifier` | source


### `StartGamePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (3360) `LevelSettings` | mSettings
3400 | (8) `ActorUniqueID` | mEntityId
3408 | (8) `ActorRuntimeID` | mRuntimeId
3416 | (4) `GameType` | mEntityGameType
3420 | (12) `Vec3` | mPos
3432 | (8) `Vec2` | mRot
3440 | (32) `std::string` | mLevelId
3472 | (32) `std::string` | mLevelName
3504 | (24) `ContentIdentity` | mTemplateContentIdentity
3528 | (1) `bool` | mIsTrial
3532 | (12) `SyncedPlayerMovementSettings` | mMovementSettings
3544 | (8) `unsigned __int64` | mLevelCurrentTime
3552 | (4) `int` | mEnchantmentSeed
3560 | (32) `std::string` | mMultiplayerCorrelationId
3592 | (32) `std::string` | mModelName
3624 | (32) `std::string` | mModelTexture
3656 | (1) `bool` | mUseModelSkin
3657 | (1) `bool` | mDisalbeHunger
3658 | (1) `bool` | mDisableDropItem
3659 | (1) `bool` | mDisableContainers
3660 | (1) `bool` | mDisableSolidify
3661 | (1) `bool` | mDisableGravityInLiquid
3662 | (1) `bool` | mIsNetWorkOptimize
3663 | (1) `bool` | mIsLoadSubChunkFromClient
3664 | (4) `int` | mLevelVersion
3668 | (1) `bool` | mLockDifficulty
3672 | (64) `std::unordered_map<unsigned __int64,float>` | mShearsDestorySpeed
3736 | (8) `const BlockPalette *` | mBlockPalette
3744 | (8) `std::unique_ptr<Tag>` | mBlockPaletteList
3752 | (24) `std::vector<ItemData>` | mItemData
3776 | (1) `bool` | mEnableItemStackNetManager
3777 | (1) `bool` | mUselimitArea
3780 | (12) `Vec3` | mLimitAreaCenter
3792 | (4) `int` | mLimitAreaOffsetX
3796 | (4) `int` | mLimitAreaOffsetZ
3800 | (1) `bool` | mDisableItemUse
3801 | (1) `bool` | mDisableItemUseOnBlock
3808 | (24) `std::vector<std::pair<std::string,CompoundTag>>` | mBlockProperties


### `SyncedPlayerMovementSettings`
Offset | Type | Name
-|-|-|-
0 | (1) `ServerAuthMovementMode` | AuthorityMode
4 | (4) `int` | mRewindHistorySize
8 | (1) `bool` | ServerAuthBlockBreaking


### `ServiceReference<EducationOptions>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<EducationOptions>` | mService


### `ServiceReference<ContentTierManager::ValidatorRegistry>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<ContentTierManager::ValidatorRegistry>` | mService


### `ServiceReference<PackManifest::CapabilityRegistry>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<PackManifest::CapabilityRegistry>` | mService


### `SubpackInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mFolderName
32 | (32) `std::string` | mName
64 | (4) `int` | mMemoryTier


### `ScriptApi::ScriptVersionInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMajorVersion
4 | (4) `int` | mMinVerssion


### `ScriptApi::EventTracking`
Offset | Type | Name
-|-|-|-


### `ScriptEngine::ScriptQueueData`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | mScriptPath
32 | (32) `std::string` | mScriptName
64 | (32) `std::string` | mScriptContent
96 | (32) `std::string` | mPackID
128 | (32) `std::string` | mPackVersion
160 | (8) `unsigned __int64` | mScriptHash


### `ScoreboardCommand::SetScoreOutput`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSuccessCount
4 | (4) `int` | mFirstNewScore
8 | (32) `std::string` | mFirstSuccess


### `SetTitlePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `_BYTE[4]` | mType
48 | (32) `std::string` | mTitleText
80 | (4) `int` | mFadeInTime
84 | (4) `int` | mStayTime
88 | (4) `int` | mFadeOutTime


### `SpawnActorDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SpawnActorParameters>` | mSpawnParameters


### `ScriptEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `ScriptEventData_vtbl *` | __vftable
8 | (32) `std::string` | mEventName


### `ScriptCommandCallbackData`
Offset | Type | Name
-|-|-|-
8 | (32) `std::string` | mCommand
40 | (1) `bool` | mCallbackReceived
48 | (16) `Json::Value` | mData


### `ServerInstance::initializeServer::__l55::<lambda_fdcfded2c4d317134dd5efe145374f82>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerInstance *const` | __this
8 | (64) `std::function<void __cdecl(void)>` | compactionCallback
72 | (32) `std::string` | levelId


### `ServiceRegistrationToken<ServerInstance>`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerInstance *` | mService


### `SaveTransactionManager::_showGlobalSaveIcon::__l5::<lambda_abfa177dbfd7bc38eb8ac17f971ba81f>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | showIconFunction


### `SaveTransactionManager::_hideGlobalSaveIcon::__l5::<lambda_9b3c9db278eb340d00c6747c3b07b14a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | showIconFunction


### `SetActorDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mId
48 | (8) `unsigned __int64` | mTick
56 | (24) `std::vector<std::unique_ptr<DataItem>>` | mPackedItems


### `SimpleBoolFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (1) `bool` | mValue


### `SimpleHashStringFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (48) `HashedString` | mValueString


### `SimpleIntFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (4) `int` | mValue


### `SimpleTagIDFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (16) `IDType<BiomeTagIDType>` | mCachedIDValue
32 | (48) `HashedString` | mValueString


### `SimpleFloatFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (4) `float` | mValue


### `Spawner`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (56) `int[2][7]` | mBaseTypeCount
64 | (128) `std::unordered_map<HashedString,int>[2]` | mEntityTypeCount
192 | (4) `int` | mTotalEntityCount
196 | (4) `int` | mEntityLimit


### `ScatterParams::_buildSchema::__l2::<lambda_a76daf2e558065fdf74a6ef87fdf0cfb>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(BiomeDecorationFeature * *)>` | scatterAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_3364f33938454b38ac82d4e8cb5ca9ef>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(BiomeDecorationFeature * *)>` | scatterAccessor


### `SharedPtr<HorseArmorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HorseArmorItem> *` | pc


### `SharedPtr<GlowStickItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GlowStickItem> *` | pc


### `ScatterParams::_buildSchema::__l2::<lambda_51c888921c5363d51df6b2151f3d1065>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(BiomeDecorationFeature * *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_ad1c76902e674cf57d5e4282dadb34e2>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(BiomeDecorationFeature * *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_da11a43e5689853c53722bcf1dd03017>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(BiomeDecorationFeature * *)>` | coordAccessor


### `SurfaceMaterialAdjustmentEvaluated::Element`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mHeightMin
4 | (4) `int` | mHeightMax
8 | (48) `SurfaceMaterialBlocks` | mSurfaceMaterialBlocks


### `SurfaceMaterialBlocks`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mTop
8 | (8) `const Block *` | mMid
16 | (8) `const Block *` | mSeaFloor
24 | (8) `const Block *` | mFoundation
32 | (8) `const Block *` | mSea
40 | (4) `int` | mSeaFloorDepth


### `SurfaceMaterialAttributes`
Offset | Type | Name
-|-|-|-
0 | (112) `BlockDescriptor` | mTop
112 | (112) `BlockDescriptor` | mMid
224 | (112) `BlockDescriptor` | mSeaFloor
336 | (112) `BlockDescriptor` | mFoundation
448 | (112) `BlockDescriptor` | mSea
560 | (4) `int` | mSeaFloorDepth


### `ScatterParams::ScatteredPositions`
Offset | Type | Name
-|-|-|-
0 | (8) `RenderParams *` | mMolangParams
8 | (8) `Random *` | mRandom
16 | (8) `const ScatterParams *` | mScatterParams
24 | (12) `BlockPos` | mOrigin
36 | (4) `unsigned int` | mIterations


### `SharedPtr<StairBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StairBlock> *` | pc


### `SharedPtr<RespawnAnchorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RespawnAnchorBlock> *` | pc


### `SharedPtr<StoneButtonBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneButtonBlock> *` | pc


### `SubChunkRelighter`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mNeedToResetToDoBits
8 | (24576) `std::bitset<196608>` | mToDo
24584 | (4096) `std::array<unsigned char,4096>` | mOldAbsorption
28680 | (768) `std::vector<SubChunkLightIndex>[2][16]` | mAdditiveBlocksToProcess
29448 | (384) `std::vector<SubChunkLightIndex>[16]` | mEdgeBlocksToProcess
29832 | (384) `std::vector<SubChunkLightIndex>[16]` | mBlocksToProcess
30216 | (24) `std::vector<SubChunkLightIndex>` | mAbsorptionBlocksToProcess
30240 | (48) `std::vector<SubtractiveLightInfo>[2]` | mSubtractiveBlocks
30288 | (384) `SubChunk *[3][4][4]` | mSubChunkPtrArray
30672 | (48) `bool[3][4][4]` | mSubChunkPtrArrayValid
30720 | (48) `bool[3][4][4]` | mSubChunkTouched
30768 | (8) `ChunkPos` | mCenterChunkPos
30776 | (8) `unsigned __int64` | mCenterSubChunkIndex
30784 | (8) `BlockSource *` | mSource
30792 | (1) `bool` | mOriginalLighting
30793 | (1) `SubChunkBrightnessStorage::LightPair` | mDefaultLightPair
30800 | (8) `const Block *` | mDefaultBlock


### `SubChunkBlockStoragePaletted<1,1>::_fetchBlocksInShape::__l2::<lambda_4fadbc1be99a51583b3494c5343adb80>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<2> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<1,1>::fetchBlocksInBox::__l2::<lambda_3a25f8be0adce3e4613c2792bb15ad32> *` | shapePredicate


### `SubChunkBlockStoragePaletted<1,1>::_fetchBlocksInShape::__l2::<lambda_148186354e0804acaf9ad78f0fb1d814>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<2> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<1,1>::fetchBlocksInCylinder::__l2::<lambda_6eff12cf755cbc8df5ad19484681e643> *` | shapePredicate


### `SubChunkBlockStoragePaletted<16,16>::_fetchBlocksInShape::__l2::<lambda_c5b0b12ce6e93dc7dd5633d9ae774d30>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4096> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<16,16>::fetchBlocksInBox::__l2::<lambda_81f82229aefcc027330dfa10aa9c846d> *` | shapePredicate


### `SubChunkBlockStoragePaletted<16,16>::_fetchBlocksInShape::__l2::<lambda_35cfabd93918b52980c17471ad686c94>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4096> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<16,16>::fetchBlocksInCylinder::__l2::<lambda_7ad7ae9e0b04fad7956ba5c2462033f8> *` | shapePredicate


### `SubChunkBlockStoragePaletted<8,8>::_fetchBlocksInShape::__l2::<lambda_529262d6459d4c3a8c51f9d45d61b780>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<256> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<8,8>::fetchBlocksInBox::__l2::<lambda_f43d19be392b01ec54de03992e19bbb7> *` | shapePredicate


### `SubChunkBlockStoragePaletted<8,8>::_fetchBlocksInShape::__l2::<lambda_a0ffaf3ba0872261bc60c010a84dbded>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<256> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<8,8>::fetchBlocksInCylinder::__l2::<lambda_2f8920f8aed8669ce026a439bb206b81> *` | shapePredicate


### `SubChunkBlockStoragePaletted<6,6>::_fetchBlocksInShape::__l2::<lambda_54a4a943a27f5378148b6cba582fd961>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<64> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<6,6>::fetchBlocksInBox::__l2::<lambda_997cfac59e34b9c498561474fd5a53aa> *` | shapePredicate


### `SubChunkBlockStoragePaletted<6,6>::_fetchBlocksInShape::__l2::<lambda_cf11aac42eade1f5d742417c3b6f63b7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<64> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<6,6>::fetchBlocksInCylinder::__l2::<lambda_8505f348207d8ed882a967b263f00729> *` | shapePredicate


### `SubChunkBlockStoragePaletted<5,5>::_fetchBlocksInShape::__l2::<lambda_46acb9a0372b6a308bbfed44681f55ce>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<32> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<5,5>::fetchBlocksInBox::__l2::<lambda_edcd7c6147545643dd4f557b53945643> *` | shapePredicate


### `SubChunkBlockStoragePaletted<5,5>::_fetchBlocksInShape::__l2::<lambda_e8c68019feae5bf749b86ced1f4ef924>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<32> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<5,5>::fetchBlocksInCylinder::__l2::<lambda_2225f5dd488587be97d5ef16dbb05a4e> *` | shapePredicate


### `SubChunkBlockStoragePaletted<4,4>::_fetchBlocksInShape::__l2::<lambda_38c371ccdcab6ebab3fef2d49dc63d2f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<16> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<4,4>::fetchBlocksInBox::__l2::<lambda_6805beeeeb20926306bc087a374beb00> *` | shapePredicate


### `SubChunkBlockStoragePaletted<4,4>::_fetchBlocksInShape::__l2::<lambda_f968d5dbf19fb99c82f711db78303527>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<16> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<4,4>::fetchBlocksInCylinder::__l2::<lambda_31ae1f2113d30483dfa86a8979a4b0c4> *` | shapePredicate


### `SubChunkBlockStoragePaletted<3,3>::_fetchBlocksInShape::__l2::<lambda_cfed23f71127b6b4785eeefce13b38fd>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<8> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<3,3>::fetchBlocksInBox::__l2::<lambda_333c91ec917de2d00c7d7b20be94f138> *` | shapePredicate


### `SubChunkBlockStoragePaletted<3,3>::_fetchBlocksInShape::__l2::<lambda_b35f173d4742f344d961487cc1dada02>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<8> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<3,3>::fetchBlocksInCylinder::__l2::<lambda_69eb90666f66735dbbd3c93a3c693a3d> *` | shapePredicate


### `SubChunkBlockStoragePaletted<2,2>::_fetchBlocksInShape::__l2::<lambda_396c2787970d1a7a1021db67118b181b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<2,2>::fetchBlocksInBox::__l2::<lambda_05dcea0d077ab08977860bf1536271dc> *` | shapePredicate


### `SubChunkBlockStoragePaletted<2,2>::_fetchBlocksInShape::__l2::<lambda_5f6af89c1e23d982784687a904482cf6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `unsigned __int16 *` | index
32 | (8) `const gsl::span<Block const * const,-1> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<2,2>::fetchBlocksInCylinder::__l2::<lambda_92f021db926b66e17c3d1841e8d27176> *` | shapePredicate


### `ScatterParams`
Offset | Type | Name
-|-|-|-
0 | (1368) `ScatterParams::CoordinateRange[3]` | mCoordinateRanges
1368 | (4) `ScatterParams::CoordinateEvaluationOrder` | mEvalOrder
1376 | (224) `ScatterParams::ChanceInformation` | mScatterChance
1600 | (216) `ExpressionNode` | mIterations


### `ScatterParams::CoordinateRange`
Offset | Type | Name
-|-|-|-
0 | (216) `ExpressionNode` | mMinOrSingleValue
216 | (216) `ExpressionNode` | mMax
432 | (4) `unsigned int` | mGridStepSize
436 | (4) `unsigned int` | mGridOffset
440 | (4) `ScatterParams::RandomDistributionType` | mDistribution
444 | (12) `std::optional<IntRange>` | mFastPathRange


### `ScatterParams::ChanceInformation`
Offset | Type | Name
-|-|-|-
0 | (216) `ExpressionNode` | mChancePercent
216 | (4) `int` | mNumerator
220 | (4) `int` | mDenominator


### `ScatterParams::_buildSchema::__l2::<lambda_7b9a05a1953b3fb60663dfc73543637b>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(AutomaticFeatureRules::AutomaticFeatureRule *)>` | scatterAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_7c5ad3777ba8587cfd702cc22d87f118>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(AutomaticFeatureRules::AutomaticFeatureRule *)>` | scatterAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_d143a5e36f9b278f892d0e584fe33c9f>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(AutomaticFeatureRules::AutomaticFeatureRule *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_c9df66ead2a74545562a76e1b7eb86e7>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(AutomaticFeatureRules::AutomaticFeatureRule *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_e47c948e79de08d4acbaa398984b3d18>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(AutomaticFeatureRules::AutomaticFeatureRule *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_983896843df920686e72abccc67e9696>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(FeatureLoading::ConcreteFeatureHolder<ScatterFeature> *)>` | scatterAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_90f750ba7b8940727bed6ecc9dcf9c82>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams & __cdecl(FeatureLoading::ConcreteFeatureHolder<ScatterFeature> *)>` | scatterAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_3aba8ead7a73cbf3eda52d898512bb18>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(FeatureLoading::ConcreteFeatureHolder<ScatterFeature> *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_33bb36551c13b4cec4c75593d0698498>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(FeatureLoading::ConcreteFeatureHolder<ScatterFeature> *)>` | coordAccessor


### `ScatterParams::_buildSchema::__l2::<lambda_2a19592188c209f1439b9279b6397a8a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ScatterParams::CoordinateRange & __cdecl(FeatureLoading::ConcreteFeatureHolder<ScatterFeature> *)>` | coordAccessor


### `StructureFeature::findFarAwayStructures::__l2::StructureInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos` | min
8 | (8) `ChunkPos` | max
16 | (8) `ChunkPos` | id


### `StringByteInput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataInput` | baseclass_0
8 | (8) `unsigned __int64` | mIdx
16 | (16) `gsl::basic_string_span<char const ,-1>` | mBuffer


### `StructureBlockPalette`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<CompoundTag>>` | mStructurePaletteIdToSerializationId
24 | (64) `std::unordered_map<unsigned __int64,StructureBlockPalette::BlockPositionData>` | mBlockPositionData


### `StructureIntegrityProcessor`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mIntegrity
4 | (4) `unsigned int` | mStartSeed


### `SpawnConditions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isOnSurface
1 | (1) `bool` | isInWater
2 | (1) `bool` | isInLava
3 | (1) `bool` | isUnderground
8 | (8) `unsigned __int64` | delayEndWorldAge
16 | (4) `int` | rawBrightness
20 | (12) `BlockPos` | pos


### `SmallSet<std::unique_ptr<Actor,std::default_delete<Actor> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<Actor>>` | c


### `ScoreInfoRef`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `bool` | mValid
16 | (8) `int *` | mValue


### `SetScorePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `_BYTE[1]` | mType
48 | (24) `std::vector<ScorePacketInfo>` | mScoreInfo


### `SetDisplayObjectivePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mDisplaySlotName
72 | (32) `std::string` | mObjectiveName
104 | (32) `std::string` | mObjectiveDisplayName
136 | (32) `std::string` | mCriteriaName
168 | (1) `_BYTE[1]` | mSortOrder


### `ServiceRegistrationToken<FeatureToggles>`
Offset | Type | Name
-|-|-|-
0 | (8) `FeatureToggles *` | mService


### `ServiceRegistrationToken<Core::LoadTimeProfiler>`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::LoadTimeProfiler *` | mService


### `SkinHelper::PersonaInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | base
32 | (32) `std::string` | armSize
64 | (32) `std::string` | height
96 | (32) `std::string` | skinColor
128 | (24) `std::vector<SkinHelper::PersonaInfo::PieceInfo>` | pieceInfos
152 | (24) `std::vector<SkinHelper::PersonaInfo::ResetPieceInfo>` | resetPieceInfos
176 | (24) `std::vector<SkinHelper::PersonaInfo::ResetTintInfo>` | resetTintInfos


### `SkinHelper::PersonaInfo::PieceInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | path
32 | (4) `_BYTE[4]` | side
36 | (68) `std::optional<TintMapColor>` | colors


### `SharedPtr<CustomProjectileItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CustomProjectileItem> *` | pc


### `SurfaceMaterialAdjustmentAttributes`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SurfaceMaterialAdjustmentAttributes::Element>` | mAdjustments


### `SpikeFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const SpikeFeature::EndSpike *` | mSpike
32 | (12) `BlockPos` | mCrystalBeamTarget
44 | (1) `bool` | mCrystalInvulnerable


### `StackResultStorageFeature`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<std::reference_wrapper<FeatureRegistry> >` | mRegistry
16 | (8) `unsigned __int64` | mIndex


### `SimpleTreeCanopy::_buildSchema::__l5::<lambda_ce902fcfd1b27af12f7a6a7e2b717c31>`
Offset | Type | Name
-|-|-|-


### `StructurePiece`
Offset | Type | Name
-|-|-|-
0 | (8) `StructurePiece_vtbl *` | __vftable
8 | (24) `BoundingBox` | mBoundingBox
32 | (4) `int` | mOrientation
36 | (4) `int` | mGenDepth


### `StructurePoolElementSettings`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::vector<std::unique_ptr<StructurePoolBlockRule>> *` | mBlockRules
8 | (8) `const std::vector<std::unique_ptr<StructurePoolBlockTagRule>> *` | mBlockTagRules
16 | (8) `const std::vector<std::unique_ptr<StructurePoolActorRule>> *` | mActorRules
24 | (4) `Projection` | mProjection
28 | (1) `PostProcessSettings` | mPostProcessSettings
29 | (1) `bool` | mReloadActorLootTables


### `StrongholdPiece`
Offset | Type | Name
-|-|-|-
0 | (40) `StructurePiece` | baseclass_0
40 | (4) `StrongholdPiece::SmallDoorType` | entryDoor


### `SharedPtr<EndGatewayBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndGatewayBlock> *` | pc


### `SoundSystemFMOD::_addToSoundCache::__l5::<lambda_cae3fd833bb655085bfe054d224c3470>`
Offset | Type | Name
-|-|-|-
0 | (8) `FMOD::System *` | system
8 | (32) `const Core::Path` | soundName
40 | (8) `FMOD::Sound *` | sound


### `SoundSystemFMOD::_playEvent::__l2::<lambda_a5fe321c266b84f7a30b4afdfac3c78e>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | eventName
8 | (8) `float *` | x
16 | (8) `float *` | y
24 | (8) `float *` | z
32 | (8) `const SoundItem *` | soundItem
40 | (8) `float *` | volumeScalar
48 | (8) `float *` | pitchScalar


### `SoundEvent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mCategory
32 | (32) `std::string` | mExternalEventName
64 | (24) `std::vector<SoundItem>` | mAllSoundItems
88 | (24) `std::vector<SoundAction>` | mSoundActions
112 | (24) `std::vector<SoundParameter>` | mExternalEventParameters


### `SoundSystemFMOD::_playEvent::__l2::<lambda_3a661bdd2d6abbebd48e1676efdccb3d>`
Offset | Type | Name
-|-|-|-
0 | (8) `SoundSystemFMOD *const` | __this
8 | (96) `const SoundItem` | soundItem
104 | (136) `const SoundEvent` | soundEvent
240 | (32) `const std::string` | eventName
272 | (8) `const unsigned __int64` | soundHandle
280 | (4) `float` | x
284 | (4) `float` | y
288 | (4) `float` | z
292 | (4) `float` | volumeScalar
296 | (4) `float` | pitchScalar
300 | (1) `bool` | is2D


### `SoundInstanceProperties`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mPosition
16 | (24) `std::vector<SoundParameter>` | mParameters


### `SoundSystemFMOD::playMusic::__l2::<lambda_a39fa897d000379322180842f3fea207>`
Offset | Type | Name
-|-|-|-
0 | (8) `SoundSystemFMOD *const` | __this
8 | (96) `const SoundItem` | soundItem
104 | (32) `const std::string` | eventName


### `SOCKADDR`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | sa_family
2 | (14) `char[14]` | sa_data


### `SoundListener`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mForward
12 | (12) `glm::tvec3<float,0>` | mUp
24 | (12) `glm::tvec3<float,0>` | mPos
36 | (12) `glm::tvec3<float,0>` | mVel


### `stbi__png`
Offset | Type | Name
-|-|-|-
0 | (8) `stbi__context *` | s
8 | (8) `unsigned __int8 *` | idata
16 | (8) `unsigned __int8 *` | expanded
24 | (8) `unsigned __int8 *` | out
32 | (4) `int` | depth


### `stbi__result_info`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | bits_per_channel
4 | (4) `int` | num_channels
8 | (4) `int` | channel_order


### `stbi__zhuffman`
Offset | Type | Name
-|-|-|-
0 | (1024) `unsigned __int16[512]` | fast
1024 | (32) `unsigned __int16[16]` | firstcode
1056 | (68) `int[17]` | maxcode
1124 | (32) `unsigned __int16[16]` | firstsymbol
1156 | (288) `unsigned __int8[288]` | size
1444 | (576) `unsigned __int16[288]` | value


### `stbi__zbuf`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | zbuffer
8 | (8) `unsigned __int8 *` | zbuffer_end
16 | (4) `int` | num_bits
20 | (4) `unsigned int` | code_buffer
24 | (8) `char *` | zout
32 | (8) `char *` | zout_start
40 | (8) `char *` | zout_end
48 | (4) `int` | z_expandable
52 | (2020) `stbi__zhuffman` | z_length
2072 | (2020) `stbi__zhuffman` | z_distance


### `stbi__bmp_data`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | bpp
4 | (4) `int` | offset
8 | (4) `int` | hsz
12 | (4) `unsigned int` | mr
16 | (4) `unsigned int` | mg
20 | (4) `unsigned int` | mb
24 | (4) `unsigned int` | ma
28 | (4) `unsigned int` | all_a


### `stbi__gif`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | w
4 | (4) `int` | h
8 | (8) `unsigned __int8 *` | out
16 | (8) `unsigned __int8 *` | background
24 | (8) `unsigned __int8 *` | history
32 | (4) `int` | flags
36 | (4) `int` | bgindex
40 | (4) `int` | ratio
44 | (4) `int` | transparent
48 | (4) `int` | eflags
52 | (1024) `unsigned __int8[256][4]` | pal
1076 | (1024) `unsigned __int8[256][4]` | lpal
2100 | (32768) `stbi__gif_lzw[8192]` | codes
34872 | (8) `unsigned __int8 *` | color_table
34880 | (4) `int` | parse
34884 | (4) `int` | step
34888 | (4) `int` | lflags
34892 | (4) `int` | start_x
34896 | (4) `int` | start_y
34900 | (4) `int` | max_x
34904 | (4) `int` | max_y
34908 | (4) `int` | cur_x
34912 | (4) `int` | cur_y
34916 | (4) `int` | line_size
34920 | (4) `int` | delay


### `stbi__gif_lzw`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | prefix
2 | (1) `unsigned __int8` | first
3 | (1) `unsigned __int8` | suffix


### `stbir__info`
Offset | Type | Name
-|-|-|-
0 | (8) `const void *` | input_data
8 | (4) `int` | input_w
12 | (4) `int` | input_h
16 | (4) `int` | input_stride_bytes
24 | (8) `void *` | output_data
32 | (4) `int` | output_w
36 | (4) `int` | output_h
40 | (4) `int` | output_stride_bytes
44 | (4) `float` | s0
48 | (4) `float` | t0
52 | (4) `float` | s1
56 | (4) `float` | t1
60 | (4) `float` | horizontal_shift
64 | (4) `float` | vertical_shift
68 | (4) `float` | horizontal_scale
72 | (4) `float` | vertical_scale
76 | (4) `int` | channels
80 | (4) `int` | alpha_channel
84 | (4) `unsigned int` | flags
88 | (4) `stbir_datatype` | type
92 | (4) `stbir_filter` | horizontal_filter
96 | (4) `stbir_filter` | vertical_filter
100 | (4) `stbir_edge` | edge_horizontal
104 | (4) `stbir_edge` | edge_vertical
108 | (4) `stbir_colorspace` | colorspace
112 | (8) `stbir__contributors *` | horizontal_contributors
120 | (8) `float *` | horizontal_coefficients
128 | (8) `stbir__contributors *` | vertical_contributors
136 | (8) `float *` | vertical_coefficients
144 | (4) `int` | decode_buffer_pixels
152 | (8) `float *` | decode_buffer
160 | (8) `float *` | horizontal_buffer
168 | (4) `int` | horizontal_coefficient_width
172 | (4) `int` | vertical_coefficient_width
176 | (4) `int` | horizontal_filter_pixel_width
180 | (4) `int` | vertical_filter_pixel_width
184 | (4) `int` | horizontal_filter_pixel_margin
188 | (4) `int` | vertical_filter_pixel_margin
192 | (4) `int` | horizontal_num_contributors
196 | (4) `int` | vertical_num_contributors
200 | (4) `int` | ring_buffer_length_bytes
204 | (4) `int` | ring_buffer_num_entries
208 | (4) `int` | ring_buffer_first_scanline
212 | (4) `int` | ring_buffer_last_scanline
216 | (4) `int` | ring_buffer_begin_index
224 | (8) `float *` | ring_buffer
232 | (8) `float *` | encode_buffer
240 | (4) `int` | horizontal_contributors_size
244 | (4) `int` | horizontal_coefficients_size
248 | (4) `int` | vertical_contributors_size
252 | (4) `int` | vertical_coefficients_size
256 | (4) `int` | decode_buffer_size
260 | (4) `int` | horizontal_buffer_size
264 | (4) `int` | ring_buffer_size
268 | (4) `int` | encode_buffer_size


### `ServiceReference<cg::IGraphicsDevicePlatformProvider>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<cg::IGraphicsDevicePlatformProvider>` | mService


### `ServiceReference<cg::IGraphicsDeviceVendorProvider>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_lock<std::shared_mutex>` | mLock
16 | (16) `Bedrock::NonOwnerPointer<cg::IGraphicsDeviceVendorProvider>` | mService


### `Serializer::serializeFields::__l2::<lambda_22057146df6c65ed81db23a915e61f14>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | kAttributesId
8 | (8) `entt::meta_any *` | any
16 | (8) `Serializer *const` | __this


### `SRE_STATE`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ptr
8 | (8) `void *` | beginning
16 | (8) `void *` | start
24 | (8) `void *` | end
32 | (8) `_object *` | string
40 | (8) `__int64` | pos
48 | (8) `__int64` | endpos
56 | (4) `int` | charsize
64 | (8) `__int64` | lastindex
72 | (8) `__int64` | lastmark
80 | (1600) `void *[200]` | mark
1680 | (8) `char *` | data_stack
1688 | (8) `unsigned __int64` | data_stack_size
1696 | (8) `unsigned __int64` | data_stack_base
1704 | (8) `SRE_REPEAT_T *` | repeat
1712 | (8) `unsigned int (__fastcall *)(unsigned int)` | lower


### `s_MergeState`
Offset | Type | Name
-|-|-|-
0 | (8) `_object *` | compare
8 | (8) `__int64` | min_gallop
16 | (8) `_object **` | a
24 | (8) `__int64` | alloced
32 | (4) `int` | n
40 | (1360) `s_slice[85]` | pending
1400 | (2048) `_object *[256]` | temparray


### `s_slice`
Offset | Type | Name
-|-|-|-
0 | (8) `_object **` | base
8 | (8) `__int64` | len


### `setentry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | hash
8 | (8) `_object *` | key


### `SubString`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | ptr
8 | (8) `char *` | end


### `ShortTag_vtbl`
```
struct /*VFT*/ ShortTag_vtbl
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

### `StringTag_vtbl`
```
struct /*VFT*/ StringTag_vtbl
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

### `SkinnedMesh`
```
struct __cppobj __declspec(align(8)) SkinnedMesh
{
  bool mShouldDrawThisFrame;
  std::vector<ModelPart *> mSkinnedParts;
  mce::Mesh mSkinnedMeshQuads;
  mce::Mesh mSkinnedMeshTris;
  std::vector<glm::tmat4x4<float,0>> mBoneMatrices;
  int mVertexCount;
  int mTotalVertices;
  bool mUseBones;
};

```

### `SkinnedMeshGroup`
```
struct __cppobj SkinnedMeshGroup
{
  std::unordered_map<RenderController const *,ExpressionNode> mVisibilityExpressionMap;
  std::unordered_map<RenderController const *,ExpressionNode> mMaterialExpressionMap;
  bool mShouldDrawThisFrame;
  bool mIsUniqueGroup;
  int mSkinnedMeshGroupIdentifier;
  std::vector<std::shared_ptr<SkinnedMesh>> mSkinnedMeshes;
};

```

### `SkinAdjustments`
```
struct __cppobj SkinAdjustments
{
  unsigned int mAnimOverrideBitmask;
};

```

### `ShaderColor`
```
struct __cppobj __declspec(align(4)) ShaderColor
{
  mce::Color color;
  bool dirty;
};

```

### `SortedMeshDrawList`
```
struct __cppobj SortedMeshDrawList
{
  std::vector<DrawsByRenderController> mDrawsByRenderController;
};

```

### `Social::IGameConnectionInfoProvider`
```
struct __cppobj Social::IGameConnectionInfoProvider
{
  Social::IGameConnectionInfoProvider_vtbl *__vftable /*VFT*/;
};

```

### `Social::IGameConnectionInfoProvider_vtbl`
```
struct /*VFT*/ Social::IGameConnectionInfoProvider_vtbl
{
  void (__fastcall *~IGameConnectionInfoProvider)(Social::IGameConnectionInfoProvider *this);
  const Social::GameConnectionInfo *(__fastcall *getConnectionInfo)(Social::IGameConnectionInfoProvider *this);
};

```

### `ServerLocator`
```
struct __cppobj ServerLocator : NetworkSuspendResumeListener
{
};

```

### `ServerLocator_vtbl`
```
struct /*VFT*/ ServerLocator_vtbl
{
  void (__fastcall *~NetworkSuspendResumeListener)(NetworkSuspendResumeListener *this);
  void (__fastcall *onSuspend)(NetworkSuspendResumeListener *this);
  void (__fastcall *onResume)(NetworkSuspendResumeListener *this);
  void (__fastcall *announceServer)(ServerLocator *this, const std::string *, const std::string *, GameType, int, int, bool);
  void (__fastcall *stopAnnouncingServer)(ServerLocator *this);
  void (__fastcall *findServers)(ServerLocator *this, int, int);
  void (__fastcall *addCustomServer)(ServerLocator *this, const std::string *, int);
  void (__fastcall *addCustomServer)(ServerLocator *this, const AsynchronousIPResolver *, int);
  void (__fastcall *stopFindingServers)(ServerLocator *this);
  std::vector<PingedCompatibleServer> *(__fastcall *getServerList)(ServerLocator *this, std::vector<PingedCompatibleServer> *result);
  void (__fastcall *clearServerList)(ServerLocator *this);
  bool (__fastcall *isIPv4Supported)(ServerLocator *this);
  bool (__fastcall *isIPv6Supported)(ServerLocator *this);
  void (__fastcall *setHostGUID)(ServerLocator *this, std::function<RakNet::RakNetGUID __cdecl(void)>);
  float (__fastcall *getPingTimeForGUID)(ServerLocator *this, const std::string *);
  void (__fastcall *checkCanConnectToCustomServerAsync)(ServerLocator *this, std::string, int, std::function<void __cdecl(bool)>);
};

```

### `SPSCQueue<BatchedNetworkPeer::DataCallback,512>`
```
struct __cppobj SPSCQueue<BatchedNetworkPeer::DataCallback,512>
{
  Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mTailBlock;
  unsigned __int64 mLargestBlockSize;
};

```

### `SettingsCommandPacket`
```
const struct __cppobj __declspec(align(8)) SettingsCommandPacket : Packet
{
  std::string mCommandString;
  bool mSupressOutput;
};

```

### `SettingsCommandPacket_vtbl`
```
struct /*VFT*/ SettingsCommandPacket_vtbl
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

### `ScriptCustomEventPacket`
```
const struct __cppobj ScriptCustomEventPacket : Packet
{
  std::string mEventName;
  Json::Value mData;
};

```

### `ScriptCustomEventPacket_vtbl`
```
struct /*VFT*/ ScriptCustomEventPacket_vtbl
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

### `SetLocalPlayerAsInitializedPacket`
```
const struct __cppobj SetLocalPlayerAsInitializedPacket : Packet
{
  ActorRuntimeID mPlayerID;
};

```

### `SetLocalPlayerAsInitializedPacket_vtbl`
```
struct /*VFT*/ SetLocalPlayerAsInitializedPacket_vtbl
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

### `StoreBuySuccPacket`
```
const struct __cppobj StoreBuySuccPacket : Packet
{
  std::string mContent;
};

```

### `StoreBuySuccPacket_vtbl`
```
struct /*VFT*/ StoreBuySuccPacket_vtbl
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

### `SetLastHurtByPacket`
```
const struct __cppobj __declspec(align(8)) SetLastHurtByPacket : Packet
{
  ActorType mLastHurtBy;
};

```

### `SetLastHurtByPacket_vtbl`
```
struct /*VFT*/ SetLastHurtByPacket_vtbl
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

### `SerializedPersonaPieceHandle`
```
struct __cppobj SerializedPersonaPieceHandle
{
  std::string mPieceId;
  _BYTE mPieceType[4];
  mce::UUID mPackId;
  bool mIsDefaultPiece;
  std::string mProductId;
};

```

### `ShowCreditsPacket`
```
const struct __cppobj __declspec(align(8)) ShowCreditsPacket : Packet
{
  ActorRuntimeID mPlayerID;
  ShowCreditsPacket::CreditsState mCreditsState;
};

```

### `ShowCreditsPacket_vtbl`
```
struct /*VFT*/ ShowCreditsPacket_vtbl
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

### `SetScoreboardIdentityPacket`
```
const struct __cppobj SetScoreboardIdentityPacket : Packet
{
  _BYTE mType[1];
  std::vector<ScoreboardIdentityPacketInfo> mIdentityInfo;
};

```

### `SetScoreboardIdentityPacket_vtbl`
```
struct /*VFT*/ SetScoreboardIdentityPacket_vtbl
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

### `SetScorePacket_vtbl`
```
struct /*VFT*/ SetScorePacket_vtbl
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

### `ShowProfilePacket`
```
const struct __cppobj ShowProfilePacket : Packet
{
  std::string mPlayerXUID;
};

```

### `ShowProfilePacket_vtbl`
```
struct /*VFT*/ ShowProfilePacket_vtbl
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

### `ServerSettingsResponsePacket`
```
const struct __cppobj ServerSettingsResponsePacket : Packet
{
  unsigned int mFormId;
  std::string mFormJSON;
};

```

### `ServerSettingsResponsePacket_vtbl`
```
struct /*VFT*/ ServerSettingsResponsePacket_vtbl
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

### `ServerSettingsRequestPacket`
```
const struct __cppobj ServerSettingsRequestPacket : Packet
{
};

```

### `ServerSettingsRequestPacket_vtbl`
```
struct /*VFT*/ ServerSettingsRequestPacket_vtbl
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

### `SetDisplayObjectivePacket_vtbl`
```
struct /*VFT*/ SetDisplayObjectivePacket_vtbl
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

### `ShowStoreOfferPacket`
```
const struct __cppobj __declspec(align(8)) ShowStoreOfferPacket : Packet
{
  std::string mOfferId;
  std::string mContentType;
  bool mShowAll;
};

```

### `ShowStoreOfferPacket_vtbl`
```
struct /*VFT*/ ShowStoreOfferPacket_vtbl
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

### `SetTitlePacket_vtbl`
```
struct /*VFT*/ SetTitlePacket_vtbl
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

### `StopSoundPacket`
```
const struct __cppobj __declspec(align(8)) StopSoundPacket : Packet
{
  std::string mName;
  bool mStopAll;
};

```

### `StopSoundPacket_vtbl`
```
struct /*VFT*/ StopSoundPacket_vtbl
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

### `StructureTemplateDataResponsePacket_vtbl`
```
struct /*VFT*/ StructureTemplateDataResponsePacket_vtbl
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

### `StructureSettings`
```
struct __cppobj StructureSettings
{
  std::string mPaletteName;
  bool mIgnoreEntities;
  bool mReloadActorEquipment;
  bool mIgnoreBlocks;
  bool mIgnoreJigsawBlocks;
  BlockPos mStructureSize;
  BlockPos mStructureOffset;
  Vec3 mPivot;
  ActorUniqueID mLastTouchedByPlayer;
  Rotation mRotation;
  Mirror mMirror;
  AnimationMode mAnimationMode;
  unsigned int mAnimationTicks;
  float mIntegrityValue;
  unsigned int mIntegritySeed;
};

```

### `StructureTemplateDataRequestPacket`
```
const struct __cppobj __declspec(align(8)) StructureTemplateDataRequestPacket : Packet
{
  std::string mStructureName;
  NetworkBlockPosition mStructureBlockPos;
  StructureSettings mStructureSettings;
  StructureTemplateRequestOperation mRequestOperation;
};

```

### `StructureTemplateDataRequestPacket_vtbl`
```
struct /*VFT*/ StructureTemplateDataRequestPacket_vtbl
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

### `StructureEditorData`
```
struct __cppobj StructureEditorData
{
  std::string mStructureName;
  std::string mDataField;
  bool mIncludePlayers;
  bool mShowBoundingBox;
  StructureRedstoneSaveMode mRedstoneSaveMode;
  StructureBlockType mType;
  StructureSettings mSettings;
};

```

### `StructureBlockUpdatePacket`
```
const struct __cppobj __declspec(align(8)) StructureBlockUpdatePacket : Packet
{
  NetworkBlockPosition mBlockPos;
  StructureEditorData mData;
  bool mTrigger;
};

```

### `StructureBlockUpdatePacket_vtbl`
```
struct /*VFT*/ StructureBlockUpdatePacket_vtbl
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

### `SpawnExperienceOrbPacket`
```
const struct __cppobj SpawnExperienceOrbPacket : Packet
{
  Vec3 mPos;
  int mCount;
};

```

### `SpawnExperienceOrbPacket_vtbl`
```
struct /*VFT*/ SpawnExperienceOrbPacket_vtbl
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

### `SimpleEventPacket`
```
const struct __cppobj __declspec(align(8)) SimpleEventPacket : Packet
{
  SimpleEventPacket::Subtype mSubtype;
};

```

### `SimpleEventPacket_vtbl`
```
struct /*VFT*/ SimpleEventPacket_vtbl
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

### `SetDifficultyPacket`
```
const struct __cppobj __declspec(align(8)) SetDifficultyPacket : Packet
{
  Difficulty mDifficulty;
};

```

### `SetDifficultyPacket_vtbl`
```
struct /*VFT*/ SetDifficultyPacket_vtbl
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

### `SetCommandsEnabledPacket`
```
const struct __cppobj __declspec(align(8)) SetCommandsEnabledPacket : Packet
{
  bool mCommandsEnabled;
};

```

### `SetCommandsEnabledPacket_vtbl`
```
struct /*VFT*/ SetCommandsEnabledPacket_vtbl
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

### `SharedCounter<Item>`
```
struct __cppobj SharedCounter<Item>
{
  Item *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SetSpawnPositionPacket`
```
const struct __cppobj SetSpawnPositionPacket : Packet
{
  NetworkBlockPosition mPos;
  SpawnPositionType mSpawnPosType;
  AutomaticID<Dimension,int> mDimensionType;
  NetworkBlockPosition mSpawnBlockPos;
};

```

### `SetSpawnPositionPacket_vtbl`
```
struct /*VFT*/ SetSpawnPositionPacket_vtbl
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

### `SetActorLinkPacket`
```
const struct __cppobj SetActorLinkPacket : Packet
{
  ActorLink mLink;
};

```

### `SetActorLinkPacket_vtbl`
```
struct /*VFT*/ SetActorLinkPacket_vtbl
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

### `SetHealthPacket`
```
const struct __cppobj __declspec(align(8)) SetHealthPacket : Packet
{
  int mHealth;
};

```

### `SetHealthPacket_vtbl`
```
struct /*VFT*/ SetHealthPacket_vtbl
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

### `SetActorMotionPacket`
```
const struct __cppobj __declspec(align(8)) SetActorMotionPacket : Packet
{
  ActorRuntimeID mRuntimeId;
  Vec3 mMotion;
};

```

### `SetActorMotionPacket_vtbl`
```
struct /*VFT*/ SetActorMotionPacket_vtbl
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

### `SetActorDataPacket_vtbl`
```
struct /*VFT*/ SetActorDataPacket_vtbl
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

### `SpawnParticleEffectPacket`
```
const struct __cppobj SpawnParticleEffectPacket : Packet
{
  unsigned __int8 mVanillaDimensionId;
  ActorUniqueID mActorId;
  Vec3 mPos;
  std::string mEffectName;
};

```

### `SpawnParticleEffectPacket_vtbl`
```
struct /*VFT*/ SpawnParticleEffectPacket_vtbl
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

### `SetDefaultGameTypePacket`
```
const struct __cppobj __declspec(align(8)) SetDefaultGameTypePacket : Packet
{
  GameType mDefaultGameType;
};

```

### `SetDefaultGameTypePacket_vtbl`
```
struct /*VFT*/ SetDefaultGameTypePacket_vtbl
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

### `SetPlayerGameTypePacket`
```
const struct __cppobj __declspec(align(8)) SetPlayerGameTypePacket : Packet
{
  GameType mPlayerGameType;
};

```

### `SetPlayerGameTypePacket_vtbl`
```
struct /*VFT*/ SetPlayerGameTypePacket_vtbl
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

### `StartGamePacket_vtbl`
```
struct /*VFT*/ StartGamePacket_vtbl
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

### `SetDimensionLocalTimePacket`
```
const struct __cppobj __declspec(align(8)) SetDimensionLocalTimePacket : Packet
{
  bool mIsLocal;
  int mTime;
  bool mDoDayNightCycle;
};

```

### `SetDimensionLocalTimePacket_vtbl`
```
struct /*VFT*/ SetDimensionLocalTimePacket_vtbl
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

### `SetTimePacket`
```
const struct __cppobj __declspec(align(8)) SetTimePacket : Packet
{
  int mTime;
};

```

### `SetTimePacket_vtbl`
```
struct /*VFT*/ SetTimePacket_vtbl
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

### `ServerToClientHandshakePacket`
```
const struct __cppobj ServerToClientHandshakePacket : Packet
{
  std::string mData;
};

```

### `ServerToClientHandshakePacket_vtbl`
```
struct /*VFT*/ ServerToClientHandshakePacket_vtbl
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

### `SubClientLoginPacket`
```
const struct __cppobj SubClientLoginPacket : Packet
{
  std::unique_ptr<SubClientConnectionRequest> mConnectionRequest;
};

```

### `SubClientLoginPacket_vtbl`
```
struct /*VFT*/ SubClientLoginPacket_vtbl
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

### `SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>`
```
struct __cppobj SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *> mTailBlock;
  unsigned __int64 mLargestBlockSize;
};

```

### `Scheduler`
```
struct __cppobj __declspec(align(8)) Scheduler : Bedrock::EnableNonOwnerReferences
{
  unsigned int mTotalFrames;
  unsigned int mStarvedFrames;
  unsigned int mPromotionFrames;
  unsigned int mTargetFPS;
  unsigned int mEffectiveFPS;
  unsigned int mFramesOverBound;
  long double mAverageCallbackDuration;
  long double mTotalCoroutineDuration;
  unsigned __int64 mTotalRunCoroutines;
  long double mCoroutineTimeLimit;
  std::unique_ptr<WorkerPool> mCoroutinePool;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNextStarveCheckTime;
  std::thread::id mThreadID;
};

```

### `Social::Events::IEventListener`
```
struct __cppobj Social::Events::IEventListener
{
  Social::Events::IEventListener_vtbl *__vftable /*VFT*/;
};

```

### `Social::Events::IEventListener_vtbl`
```
struct /*VFT*/ Social::Events::IEventListener_vtbl
{
  void (__fastcall *~IEventListener)(Social::Events::IEventListener *this);
  void (__fastcall *recordEvent)(Social::Events::IEventListener *this, const Social::Events::Event *);
  void (__fastcall *sendEvents)(Social::Events::IEventListener *this, bool);
  int (__fastcall *getEventTagsFilter)(Social::Events::IEventListener *this);
  void (__fastcall *stopDebugEventLogging)(Social::Events::IEventListener *this);
};

```

### `Social::Events::EventManager`
```
struct __cppobj Social::Events::EventManager
{
  std::vector<std::unique_ptr<Social::Events::IEventListener>> mEventListeners;
  std::unordered_map<std::string,Social::Events::Property> mGlobalProperties;
  std::unordered_map<std::string,Social::Events::Property> mCommonProperties;
  std::unordered_map<unsigned int,std::unordered_map<std::string,Social::Events::Property>> mPlayerCommonProperties;
  std::unordered_map<unsigned int,std::unordered_map<std::string,Social::Events::Property>> mPlayerGlobalProperties;
  std::shared_mutex mGlobalPropertiesMutex;
  std::shared_mutex mCommonPropertiesMutex;
  std::shared_mutex mPlayerCommonPropertiesMutex;
  std::shared_mutex mPlayerGlobalPropertiesMutex;
  std::shared_mutex mListenersMutex;
  unsigned int mGlobalSeqNum;
  bool mAcceptNewEvents;
  std::unique_ptr<TaskGroup> mRecordEventTaskGroup;
};

```

### `Social::XboxLiveUser`
```
const struct __cppobj __declspec(align(8)) Social::XboxLiveUser : AppPlatformListener, std::enable_shared_from_this<Social::XboxLiveUser>
{
  IMinecraftEventing *mEventing;
  PlayerAchievementData mCachedAchievementData;
  std::shared_ptr<Social::XboxLiveUserInfo> mXboxLiveUserInfo;
  Social::XsapiHandle<XalUser *> mCurrentUser;
  Social::XsapiHandle<XblContext *> mXblContext;
  bool mIsPlayerBan;
  std::chrono::duration<__int64,std::ratio<1,1> > mPrivacyListsRefreshInterval;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeMarkOfPrivacyListsRefresh;
  std::vector<int> mUserVisitedBiomes;
  std::unordered_map<std::string,std::unique_ptr<Social::XboxLiveUserProfileData>> mXuidProfileMap;
  std::vector<Social::XboxLiveUserProfileData const *> mFriendList;
  std::vector<Social::XboxLiveUserProfileData *> mProfileQueries;
  std::vector<Social::XboxLiveUserProfileData *> mPermissionQueries;
  bool mTelemetryIsActive;
  std::string mRichPresence;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mUsersUpdateTime;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  bool mAppIsActive;
  std::string mXuid;
  Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock> mObserverSubject;
  BasicTimer mProfileRequestTimer;
  BasicTimer mPermissionRequestTimer;
  std::vector<Social::XboxLiveUser::ProfileCallback> mProfileCallbacks;
  Core::PathBuffer<std::string > mStorageAreaPathOverride;
  bool mIsRealTimeActivityAllowed;
};

```

### `Social::XboxLiveUserInfo`
```
struct __cppobj Social::XboxLiveUserInfo : std::enable_shared_from_this<Social::XboxLiveUserInfo>
{
  Social::XboxLiveUser *mUser;
  std::vector<std::string> mXboxLiveBlockList;
  std::mutex mBlockListMutex;
  std::mutex mWritingFriendInfo;
  std::mutex mContextChange;
  std::unordered_map<enum Social::XboxLiveUserProfileData::FetchedData,Social::XboxLiveUserInfo::XboxLiveLimitTimer> mLimitTimers;
};

```

### `Social::XsapiHandle<XalUser *>`
```
struct __cppobj Social::XsapiHandle<XalUser *>
{
  struct XalUser *mHandle;
  std::function<void __cdecl(XalUser *)> mCloseFn;
  std::function<int __cdecl(XalUser *,XalUser * *)> mDuplicateFn;
};

```

### `Social::XsapiHandle<XblContext *>`
```
struct __cppobj Social::XsapiHandle<XblContext *>
{
  struct XblContext *mHandle;
  std::function<void __cdecl(XblContext *)> mCloseFn;
  std::function<int __cdecl(XblContext *,XblContext * *)> mDuplicateFn;
};

```

### `Social::XboxLivePermission`
```
struct __cppobj __declspec(align(4)) Social::XboxLivePermission
{
  _BYTE mPermission[4];
  bool mIsAllowed;
};

```

### `Social::XboxLiveUserObserver`
```
struct __cppobj Social::XboxLiveUserObserver : Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
};

```

### `Social::XboxLiveUserObserver_vtbl`
```
struct /*VFT*/ Social::XboxLiveUserObserver_vtbl
{
  void (__fastcall *~Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>)(Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onXboxUserBlocked)(Social::XboxLiveUserObserver *this, const std::string *);
  void (__fastcall *onXboxUserUnblocked)(Social::XboxLiveUserObserver *this, const std::string *);
};

```

### `Social::XboxLiveUser::ProfileCallback`
```
struct __cppobj Social::XboxLiveUser::ProfileCallback
{
  std::function<void __cdecl(std::vector<Social::XboxLiveUserProfileData const *> const &)> mAction;
  std::vector<std::string> mXuids;
};

```

### `Social::XboxLiveUser_vtbl`
```
struct /*VFT*/ Social::XboxLiveUser_vtbl
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
};

```

### `SearchRequestTelemetry`
```
const struct __cppobj SearchRequestTelemetry : RequestTelemetry
{
  bool mSendCV;
  std::string mCVHeader;
};

```

### `Scoreboard`
```
const struct __cppobj Scoreboard
{
  Scoreboard_vtbl *__vftable /*VFT*/;
  CommandSoftEnumRegistry mRegistry;
  std::unordered_map<std::string,DisplayObjective> mDisplayObjectives;
  IdentityDictionary mIdentityDict;
  std::unordered_map<ScoreboardId,ScoreboardIdentityRef> mIdentityRefs;
  bool mShouldUpdateUI;
  std::unordered_map<std::string,std::unique_ptr<Objective>> mObjectives;
  std::unordered_map<std::string,std::unique_ptr<ObjectiveCriteria>> mCriteria;
};

```

### `SensitiveWordsManager::HashRecord`
```
struct __cppobj __declspec(align(4)) SensitiveWordsManager::HashRecord
{
  unsigned __int64 hash;
  int touchMarker;
  __int16 version;
};

```

### `SensitiveWordsLog`
```
struct __cppobj __declspec(align(8)) SensitiveWordsLog
{
  SensitiveWordsLog::ContentType contentType;
  std::string playerName;
  std::string content;
  std::string playerUid;
  bool isShield;
};

```

### `SensitiveWordsManager`
```
struct __cppobj SensitiveWordsManager
{
  std::list<SensitiveWordsManager::HashRecord> mValidHashList;
  std::unordered_map<unsigned __int64,std::_List_iterator<std::_List_val<std::_List_simple_types<SensitiveWordsManager::HashRecord> > >> mValidHashMap;
  std::vector<SensitiveWordsLog> mPendingSalog;
  std::vector<SensitiveWordsLog> mSendingSalog;
  int mTouchMarker;
  bool cacheHashDirty;
  bool salogDirty;
  BinaryStream mSaveStream;
  Level *mLevel;
};

```

### `Scoreboard_vtbl`
```
struct /*VFT*/ Scoreboard_vtbl
{
  void (__fastcall *~Scoreboard)(Scoreboard *this);
  const DisplayObjective *(__fastcall *setDisplayObjective)(Scoreboard *this, const std::string *, const Objective *, const ObjectiveSortOrder);
  Objective *(__fastcall *clearDisplayObjective)(Scoreboard *this, const std::string *);
  const ScoreboardId *(__fastcall *createScoreboardId)(Scoreboard *this, const std::string *);
  const ScoreboardId *(__fastcall *createScoreboardId)(Scoreboard *this, const Actor *);
  const ScoreboardId *(__fastcall *createScoreboardId)(Scoreboard *this, const Player *);
  void (__fastcall *onObjectiveAdded)(Scoreboard *this, const Objective *);
  void (__fastcall *onObjectiveRemoved)(Scoreboard *this, Objective *);
  void (__fastcall *onScoreChanged)(Scoreboard *this, const ScoreboardId *, const Objective *);
  void (__fastcall *onPlayerScoreRemoved)(Scoreboard *this, const ScoreboardId *, const Objective *);
  void (__fastcall *onPlayerJoined)(Scoreboard *this, const Player *);
  void (__fastcall *onPlayerIdentityUpdated)(Scoreboard *this, const PlayerScoreboardId *);
  void (__fastcall *tick)(Scoreboard *this);
  void (__fastcall *setPacketSender)(Scoreboard *this, PacketSender *);
  void (__fastcall *writeToLevelStorage)(Scoreboard *this);
  void (__fastcall *sensitiveCheckScoreboard)(Scoreboard *this, SensitiveWordsManager *);
  bool (__fastcall *isClientSide)(Scoreboard *this);
};

```

### `SeasonsRenderer`
```
struct __cppobj __declspec(align(8)) SeasonsRenderer
{
  unsigned int mTick;
  std::unique_ptr<TaskGroup> mMainThreadTaskGroup;
  std::shared_ptr<mce::Image> mSeasonsImage;
  std::shared_ptr<mce::ClientTexture> mSeasonsTexture;
  bool mSeasonsTextureDirty;
};

```

### `StructureTemplateData_vtbl`
```
struct /*VFT*/ StructureTemplateData_vtbl
{
  void (__fastcall *~StructureTemplateData)(StructureTemplateData *this);
};

```

### `StructureBlockPalette::BlockPositionData`
```
struct __cppobj StructureBlockPalette::BlockPositionData
{
  std::unique_ptr<CompoundTag> mBlockEntityData;
  std::vector<StructureBlockPalette::TickingQueueData> mTickData;
};

```

### `SmallSet<std::unique_ptr<Actor> >`
```
struct __cppobj SmallSet<std::unique_ptr<Actor> >
{
  std::vector<std::unique_ptr<Actor>> c;
};

```

### `StructureAnimationData`
```
struct __cppobj __declspec(align(8)) StructureAnimationData
{
  unsigned __int64 mTickQueued;
  std::string mStructureName;
  StructureSettings mStructureSettings;
  unsigned int mBlocksPlaced;
  unsigned int mTotalBlocks;
  unsigned __int8 mInitialStructureVersion;
  std::unique_ptr<CommandArea> mCmdArea;
  BlockPos mPlacementPos;
  unsigned int mQueueID;
  AutomaticID<Dimension,int> mTargetDimension;
};

```

### `StructureManager`
```
struct __cppobj __declspec(align(8)) StructureManager
{
  std::shared_mutex mTryGetMutex;
  std::shared_mutex mRepositoryMutex;
  std::unordered_map<std::string,std::unique_ptr<LegacyStructureTemplate>> mLegacyStructureRepository;
  std::unordered_map<std::string,std::unique_ptr<StructureTemplate>> mStructureRepository;
  std::vector<std::unique_ptr<StructureAnimationData>> mStructurePlacementQueue;
  unsigned int mStructurePlacementSaveCounter;
};

```

### `SnapshotFilenameAndLength`
```
struct __cppobj SnapshotFilenameAndLength
{
  std::string filename;
  unsigned __int64 filesize;
};

```

### `SPSCQueue<std::function<void __cdecl(void)>,512>`
```
struct __cppobj SPSCQueue<std::function<void __cdecl(void)>,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *> mTailBlock;
  unsigned __int64 mLargestBlockSize;
};

```

### `ScriptApi::ScriptFramework`
```
struct __cppobj ScriptApi::ScriptFramework
{
  ScriptApi::ScriptFramework_vtbl *__vftable /*VFT*/;
  std::unique_ptr<ScriptApi::ScriptLanguageInterface> mLanguageInterface;
  std::vector<ScriptApi::ScriptSystemInfo> mScriptSystems;
  std::unique_ptr<ScriptApi::ScriptReport> mScriptReportQueue;
};

```

### `ScriptApi::ScriptFramework_vtbl`
```
struct /*VFT*/ ScriptApi::ScriptFramework_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
};

```

### `ScriptApi::ScriptLanguageInterface`
```
struct __cppobj ScriptApi::ScriptLanguageInterface
{
  ScriptApi::ScriptLanguageInterface_vtbl *__vftable /*VFT*/;
};

```

### `ScriptApi::JavaScriptErrorHandler`
```
struct __cppobj ScriptApi::JavaScriptErrorHandler
{
  ScriptApi::JavaScriptErrorHandler_vtbl *__vftable /*VFT*/;
  std::string mFullErrorMessage;
  std::string mFilename;
};

```

### `ScriptApi::JavaScriptErrorHandler_vtbl`
```
struct /*VFT*/ ScriptApi::JavaScriptErrorHandler_vtbl
{
  void (__fastcall *~JavaScriptErrorHandler)(ScriptApi::JavaScriptErrorHandler *this);
  const std::string *(__fastcall *getFullErrorMessage)(ScriptApi::JavaScriptErrorHandler *this);
  const std::string *(__fastcall *getFilename)(ScriptApi::JavaScriptErrorHandler *this);
  void (__fastcall *_generateFullErrorMessage)(ScriptApi::JavaScriptErrorHandler *this);
};

```

### `ScriptApi::ScriptReportItem`
```
struct __cppobj ScriptApi::ScriptReportItem
{
  std::string mMessage;
  ScriptApi::ScriptReportItemType mType;
  std::unique_ptr<ScriptApi::JavaScriptErrorHandler> mErrorHandler;
};

```

### `ScriptApi::ScriptReport`
```
struct __cppobj ScriptApi::ScriptReport
{
  std::vector<std::shared_ptr<ScriptApi::ScriptReportItem>> mReportItems;
};

```

### `ScriptApi::ScriptCallbackInterface`
```
struct __cppobj ScriptApi::ScriptCallbackInterface
{
  ScriptApi::ScriptCallbackInterface_vtbl *__vftable /*VFT*/;
};

```

### `ScriptApi::ScriptCallbackInterface_vtbl`
```
struct /*VFT*/ ScriptApi::ScriptCallbackInterface_vtbl
{
  void (__fastcall *~ScriptCallbackInterface)(ScriptApi::ScriptCallbackInterface *this);
  void (__fastcall *makeErrorResultObject)(ScriptApi::ScriptCallbackInterface *this, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processLogCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processRegisterEventDataCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processCreateEventDataCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processListenForEventCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processBroadcastEventCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processCreateEntityCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processDestroyEntityCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processIsValidEntityCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processRegisterComponentCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processCreateComponentCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processDestroyComponentCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processHasComponentCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processGetComponentCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processApplyComponentChangesCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processRegisterQueryCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processAddFilterToQueryCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processGetEntitiesFromQueryCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processGetBlockCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processGetBlocksCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processExecuteCommandCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processRegisterSystemCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processInfoCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processWarningCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *processErrorCallback)(ScriptApi::ScriptCallbackInterface *this, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptApi::ScriptLanguageInterface_vtbl`
```
struct /*VFT*/ ScriptApi::ScriptLanguageInterface_vtbl
{
  void (__fastcall *~ScriptLanguageInterface)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *initialized)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *runScript)(ScriptApi::ScriptLanguageInterface *this, const std::string *, const std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *createObject)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createArray)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, const int *, ScriptApi::ScriptReport *);
  bool (__fastcall *cloneObject)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *hasMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *hasMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *setMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *setMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, bool, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, long double, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, int, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, long double *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, int *, ScriptApi::ScriptReport *);
  bool (__fastcall *callObjectFunction)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *callGlobalFunction)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getHandleType)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptObjectType *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMemberNames)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, std::vector<std::string> *, ScriptApi::ScriptReport *);
  bool (__fastcall *getArrayLength)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, int *, ScriptApi::ScriptReport *);
  bool (__fastcall *getGlobalObject)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createUndefined)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createNull)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineGlobalCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineConsoleCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemSharedCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemServerCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemClientCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
};

```

### `ScriptApi::ScriptSystemInfo`
```
struct __cppobj __declspec(align(8)) ScriptApi::ScriptSystemInfo
{
  bool mInitialized;
  std::string mSystemName;
  ScriptApi::ScriptObjectHandle mSystemObject;
  ScriptApi::ScriptVersionInfo mVersionInfo;
};

```

### `ScriptEngine`
```
struct __cppobj __declspec(align(8)) ScriptEngine : ScriptApi::ScriptFramework, ScriptApi::ScriptCallbackInterface
{
  std::unordered_map<std::string,std::vector<ScriptApi::EventTracking>> mListeningEvents;
  std::deque<ScriptCommand> mCommandRequestQueue;
  std::unique_ptr<ScriptBinderTemplateController> mBinderFactory;
  bool mInitialized;
  const ScriptApi::ApiScriptType mApiScriptType;
  std::unordered_set<std::string> mRunningScripts;
  std::queue<ScriptEngine::ScriptQueueData> mPendingScriptQueue;
  std::unordered_map<std::string,EventInfo> mMapEventInfo;
  std::unique_ptr<ScriptEventCoordinator> mScriptEventCoordinator;
  ScriptLoggerConfig mLoggerConfig;
};

```

### `ScriptBinderComponent`
```
struct __cppobj ScriptBinderComponent
{
  ScriptBinderComponent_vtbl *__vftable /*VFT*/;
};

```

### `ScriptBinderComponent_vtbl`
```
struct /*VFT*/ ScriptBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptObjectBinder`
```
const struct __cppobj ScriptObjectBinder
{
  const std::string mTypeIdentifier;
  unsigned int mComponentsInUse;
  std::vector<std::unique_ptr<ScriptBinderComponent>> mComponents;
};

```

### `ScriptCommand`
```
struct __cppobj __declspec(align(8)) ScriptCommand
{
  unsigned int mId;
  std::string mCommand;
  ScriptApi::ScriptObjectHandle mCallback;
};

```

### `ScriptBinderTemplate`
```
struct __cppobj ScriptBinderTemplate
{
  ScriptBinderTemplate_vtbl *__vftable /*VFT*/;
};

```

### `ScriptBinderTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderTemplateController`
```
struct __cppobj ScriptBinderTemplateController
{
  std::unordered_map<std::string,std::unique_ptr<ScriptBinderTemplate>> mTemplates;
};

```

### `ScriptEventListener`
```
struct __cppobj ScriptEventListener
{
  ScriptEventListener_vtbl *__vftable /*VFT*/;
};

```

### `ScriptEventListener_vtbl`
```
struct /*VFT*/ ScriptEventListener_vtbl
{
  void (__fastcall *~ScriptEventListener)(ScriptEventListener *this);
  EventResult (__fastcall *onScriptGetComponent)(ScriptEventListener *this, const std::string *, RegistrationType, bool);
  EventResult (__fastcall *onScriptListenForEvent)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptBroadcastEvent)(ScriptEventListener *this, const std::string *, RegistrationType, bool);
  EventResult (__fastcall *onScriptRegisterView)(ScriptEventListener *this);
  EventResult (__fastcall *onScriptRegisterSpatialView)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptAddFilterToView)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptLoaded)(ScriptEventListener *this, const std::string *, unsigned __int64);
  EventResult (__fastcall *onScriptRan)(ScriptEventListener *this, const std::string *, const std::string *, bool);
  EventResult (__fastcall *onScriptError)(ScriptEventListener *this, const std::string *, const std::string *);
  EventResult (__fastcall *onScriptInternalError)(ScriptEventListener *this, const std::string *);
};

```

### `ScriptEventCoordinator`
```
struct __cppobj ScriptEventCoordinator : EventCoordinator<ScriptEventListener>
{
};

```

### `ScriptLoggerConfig`
```
struct __cppobj ScriptLoggerConfig : EnumBitset<enum ScriptLogType,3>
{
};

```

### `ScriptEngine_vtbl`
```
struct /*VFT*/ ScriptEngine_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *onLogReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onInfoReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onWarnReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onErrorReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const ActorUniqueID *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetActor)(ScriptEngine *this, const ScriptObjectBinder *, Actor **);
  bool (__fastcall *helpGetBlockSource)(ScriptEngine *this, const ScriptObjectBinder *, BlockSource **);
  bool (__fastcall *helpGetBlock)(ScriptEngine *this, const ScriptObjectBinder *, const Block **, const BlockSource *);
  bool (__fastcall *helpGetBlockPos)(ScriptEngine *this, const ScriptObjectBinder *, BlockPos *);
  bool (__fastcall *helpDefineLevel)(ScriptEngine *this, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetLevel)(ScriptEngine *this, const ScriptObjectBinder *, Level **);
  bool (__fastcall *helpDefineItemStack)(ScriptEngine *this, const ItemInstance *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *helpPopulateEcsID)(ScriptEngine *this, Json::Value *);
  bool (__fastcall *setupInterface)(ScriptEngine *this);
  bool (__fastcall *registerEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *onEventReceivedFromScriptEngine)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *destroyEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *isValidEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, bool *);
  bool (__fastcall *registerComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *);
  bool (__fastcall *destroyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *applyComponentChanges)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerScriptOnlyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const long double, const long double, const long double, const long double, const long double, const long double, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *addFilter)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *getBlock)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const BlockPos *, const ScriptApi::ScriptObjectHandle *, const ScriptObjectBinder *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ActorUniqueID *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ITickingArea *);
  void (__fastcall *onExecuteCommandCalled)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptCommand *);
  bool (__fastcall *executeCommand)(ScriptEngine *this, const ScriptCommand *);
  bool (__fastcall *onCommandOutputCallback)(ScriptEngine *this, unsigned int, Json::Value *);
  bool (__fastcall *_registerSystemObjects)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *_hasEvent)(ScriptEngine *this, const std::string *);
  bool (__fastcall *_helpRegisterSystemCallbacks)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  void (__fastcall *_handleError)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  void (__fastcall *_handleWarning)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
};

```

### `ScriptServerContext`
```
struct __cppobj ScriptServerContext
{
  Level *mLevel;
  Minecraft *mMinecraft;
  PacketSender *mPacketSender;
  entt::basic_registry<enum entt::entity> *mRegistry;
  ScriptApi::ScriptReport *mScriptReport;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entity`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::Entity
{
  ScriptTemplateFactory<ScriptServerContext>::Entity_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entity_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptServerContext>::Entity_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptServerContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptServerContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor **, const std::string *);
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity>`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::Entity>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Component`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::Component
{
  ScriptTemplateFactory<ScriptServerContext>::Component_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Component_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptServerContext>::Component_vtbl
{
  void (__fastcall *~Component)(ScriptTemplateFactory<ScriptServerContext>::Component *this);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, ITickingArea *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const Block *, BlockSource *, const BlockPos *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Level *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, ITickingArea *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const Block *, BlockSource *, const BlockPos *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Level *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const ITickingArea *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const Block *, BlockSource *, const BlockPos *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Level *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptServerContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor *, bool *);
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Component>`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Component>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::Component>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent
{
  ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent_vtbl
{
  void (__fastcall *~ReceivedEvent)(ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent *this);
  bool (__fastcall *receivedEvent)(ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEventData)(ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, const std::string *, ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::HashedEntries`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>::HashedEntries
{
  std::unordered_set<unsigned __int64> mHashes;
};

```

### `ScriptTemplateFactory<ScriptServerContext>`
```
struct __cppobj ScriptTemplateFactory<ScriptServerContext>
{
  ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity> mEntities;
  ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity> mItemEntities;
  ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Component> mComponents;
  ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent> mReceivedEvents;
  ScriptTemplateFactory<ScriptServerContext>::HashedEntries mScriptEventDatas;
  std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent> mBroadcastEvent;
};

```

### `ScriptOnlyComponents<ScriptServerContext>`
```
struct __cppobj ScriptOnlyComponents<ScriptServerContext>
{
  std::map<std::string,Json::Value> mScriptOnlyComponentDefs;
};

```

### `ScriptOnlyEventsData<ScriptServerContext>`
```
struct __cppobj ScriptOnlyEventsData<ScriptServerContext>
{
  std::map<std::string,Json::Value> mScriptOnlyEventsData;
};

```

### `ScriptEventData_vtbl`
```
struct /*VFT*/ ScriptEventData_vtbl
{
  void (__fastcall *~ScriptEventData)(ScriptEventData *this);
  bool (__fastcall *_serialize)(ScriptEventData *this, ScriptEngine *, ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptQueries`
```
struct __cppobj ScriptQueries
{
  entt::basic_registry<enum entt::entity> mRegistryView;
};

```

### `ScriptEngineWithContext<ScriptServerContext>`
```
struct __cppobj __declspec(align(8)) ScriptEngineWithContext<ScriptServerContext> : ScriptEngine
{
  const gsl::basic_string_span<char const ,-1> SCRIPT_FILE_EXTENSION;
  const std::string SCRIPT_ENTITY_TYPE;
  const std::string SCRIPT_ITEM_ENTITY_TYPE;
  ScriptServerContext mContext;
  ScriptTemplateFactory<ScriptServerContext> mFactory;
  ScriptOnlyComponents<ScriptServerContext> mScriptComponents;
  ScriptOnlyEventsData<ScriptServerContext> mScriptEvents;
  std::deque<std::unique_ptr<ScriptEventData const >> mEventQueue;
  std::unordered_map<unsigned int,ScriptCommandCallbackData> mCommandPendingCallbackQueue;
  ScriptQueries mQueries;
  bool mWorkaroundViewUpdate;
};

```

### `ScriptEngineWithContext<ScriptServerContext>_vtbl`
```
struct /*VFT*/ ScriptEngineWithContext<ScriptServerContext>_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *onLogReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onInfoReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onWarnReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onErrorReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const ActorUniqueID *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetActor)(ScriptEngine *this, const ScriptObjectBinder *, Actor **);
  bool (__fastcall *helpGetBlockSource)(ScriptEngine *this, const ScriptObjectBinder *, BlockSource **);
  bool (__fastcall *helpGetBlock)(ScriptEngine *this, const ScriptObjectBinder *, const Block **, const BlockSource *);
  bool (__fastcall *helpGetBlockPos)(ScriptEngine *this, const ScriptObjectBinder *, BlockPos *);
  bool (__fastcall *helpDefineLevel)(ScriptEngine *this, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetLevel)(ScriptEngine *this, const ScriptObjectBinder *, Level **);
  bool (__fastcall *helpDefineItemStack)(ScriptEngine *this, const ItemInstance *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *helpPopulateEcsID)(ScriptEngine *this, Json::Value *);
  bool (__fastcall *setupInterface)(ScriptEngine *this);
  bool (__fastcall *registerEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *onEventReceivedFromScriptEngine)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *destroyEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *isValidEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, bool *);
  bool (__fastcall *registerComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *);
  bool (__fastcall *destroyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *applyComponentChanges)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerScriptOnlyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const long double, const long double, const long double, const long double, const long double, const long double, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *addFilter)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *getBlock)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const BlockPos *, const ScriptApi::ScriptObjectHandle *, const ScriptObjectBinder *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ActorUniqueID *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ITickingArea *);
  void (__fastcall *onExecuteCommandCalled)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptCommand *);
  bool (__fastcall *executeCommand)(ScriptEngine *this, const ScriptCommand *);
  bool (__fastcall *onCommandOutputCallback)(ScriptEngine *this, unsigned int, Json::Value *);
  bool (__fastcall *_registerSystemObjects)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *_hasEvent)(ScriptEngine *this, const std::string *);
  bool (__fastcall *_helpRegisterSystemCallbacks)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  void (__fastcall *_handleError)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  void (__fastcall *_handleWarning)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
};

```

### `ServerInstanceEventListener`
```
struct __cppobj ServerInstanceEventListener
{
  ServerInstanceEventListener_vtbl *__vftable /*VFT*/;
};

```

### `ServerInstance`
```
struct __cppobj ServerInstance : AppPlatformListener, GameCallbacks, Core::StorageAreaStateListener, Bedrock::EnableNonOwnerReferences
{
  const IMinecraftApp *mApp;
  std::unique_ptr<Minecraft> mMinecraft;
  std::unique_ptr<NetworkHandler> mNetwork;
  std::unique_ptr<LoopbackPacketSender> mPacketSender;
  std::unique_ptr<Timer> mSimTimer;
  std::unique_ptr<Timer> mRealTimer;
  std::unique_ptr<Scheduler> mScheduler;
  std::unique_ptr<EducationOptions> mEducationOptions;
  LevelStorage *mStorage;
  RakNet::RakNetGUID mNetworkGUID;
  std::atomic<bool> mInUpdate;
  std::atomic<int> mWriteRefCounter;
  std::atomic<bool> mThreadShouldJoin;
  std::atomic<bool> mServerThreadActive;
  gsl::not_null<Bedrock::NonOwnerPointer<ServerInstanceEventCoordinator> > mEventCoordinator;
  std::atomic<enum ServerInstance::InstanceState> mInstanceState;
  SPSCQueue<std::function<void __cdecl(void)>,512> mCommandQueue;
  std::thread mServerInstanceThread;
  std::mutex mResumeMutex;
  std::condition_variable mResumeSignal;
  std::unique_ptr<MinecraftServerScriptEngine> mScriptEngine;
  std::function<void __cdecl(void)> mLevelCorruptCallback;
  bool mHandledLevelCorruption;
  bool mSendFinishEvent;
  bool mLoadScriptFinshed;
  std::vector<std::string> mAddOnList;
  bool mDisableHealth;
  bool mHasRemoveEntityEvent;
  bool mIsUpdateAnim;
  std::string mMapIid;
  std::string mRoomId;
  std::string mRoomName;
  std::string mServerId;
  std::string mServerName;
  std::string mHostnum;
  std::string mOwnerId;
  bool mRentalVerboseFlag;
  bool mServerCloseNameTag;
  std::unique_ptr<TextFilteringProcessor> mTextFilteringProcessor;
  std::chrono::duration<__int64,std::ratio<1,1000000> > mWakeupInterval;
  std::string mLevelId;
  std::unique_ptr<WorldSessionEndPoint> mWorldSessionEndPoint;
  std::shared_ptr<Core::FileStorageArea> mStorageAreaForLevel;
  bool mEnableItemStackNetManager;
  bool mbInitialized;
  bool mbFlaggedForEarlyDestruction;
  ServiceRegistrationToken<ServerInstance> mServiceRegistrationToken;
};

```

### `ServerInstanceEventListener_vtbl`
```
struct /*VFT*/ ServerInstanceEventListener_vtbl
{
  void (__fastcall *~ServerInstanceEventListener)(ServerInstanceEventListener *this);
  EventResult (__fastcall *onServerInitializeStart)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerInitializeEnd)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerMinecraftInitialized)(ServerInstanceEventListener *this, ServerInstance *, Minecraft *);
  EventResult (__fastcall *onServerLevelInitialized)(ServerInstanceEventListener *this, ServerInstance *, Level *);
  EventResult (__fastcall *onServerUpdateStart)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerUpdateEnd)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerSuspend)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerResume)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerThreadStarted)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onServerThreadStopped)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onStartLeaveGame)(ServerInstanceEventListener *this, ServerInstance *);
  EventResult (__fastcall *onLeaveGameDone)(ServerInstanceEventListener *this, ServerInstance *);
};

```

### `ScriptServerActorEventListener`
```
struct __cppobj ScriptServerActorEventListener : ActorEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerActorEventListener_vtbl`
```
struct /*VFT*/ ScriptServerActorEventListener_vtbl
{
  void (__fastcall *~ActorEventListener)(ActorEventListener *this);
  EventResult (__fastcall *onActorAttack)(ActorEventListener *this, Actor *, Actor *, int);
  EventResult (__fastcall *onActorHit)(ActorEventListener *this, Actor *, const ActorDamageSource *, int *, bool *, bool *);
  EventResult (__fastcall *onActorHurt)(ActorEventListener *this, const ActorHurtEvent *);
  EventResult (__fastcall *onActorMove)(ActorEventListener *this, Actor *, const Vec3 *);
  EventResult (__fastcall *onActorPredictedMove)(ActorEventListener *this, Actor *, MovePredictionType, const Vec3 *);
  EventResult (__fastcall *onActorTick)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorSneakChanged)(ActorEventListener *this, Actor *, bool);
  EventResult (__fastcall *onActorStartRiding)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorStopRiding)(ActorEventListener *this, Actor *, bool, bool, bool);
  EventResult (__fastcall *onActorDeath)(ActorEventListener *this, Actor *, const ActorDamageSource *, ActorType);
  EventResult (__fastcall *onActorDefinitionEventTriggered)(ActorEventListener *this, const ActorDefinitionEvent *);
  EventResult (__fastcall *onActorUseItem)(ActorEventListener *this, const ActorUseItemEvent *);
  EventResult (__fastcall *onActorUseItemOn)(ActorEventListener *this, Actor *, const ItemStack *, const BlockPos *, unsigned __int8);
  EventResult (__fastcall *onActorCreated)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onProjectileHit)(ActorEventListener *this, const ProjectileHitEvent *);
  EventResult (__fastcall *onActorTeleported)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorAttackedActor)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorAcquiredItem)(ActorEventListener *this, const ActorAcquiredItemEvent *);
  EventResult (__fastcall *onActorPlacedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorDroppedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorCarriedItemChanged)(ActorEventListener *this, Actor *, const ItemInstance *, const ItemInstance *, HandSlot);
  EventResult (__fastcall *onActorEquippedArmor)(ActorEventListener *this, Actor *, const ItemInstance *, ArmorSlot);
  EventResult (__fastcall *onActorRemoved)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorMobInteraction)(ActorEventListener *this, Actor *, MinecraftEventing::InteractionType, ActorType);
  EventResult (__fastcall *onActorTargetAcquired)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorGriefingBlock)(ActorEventListener *this, const ActorGriefingBlockEvent *);
  EventResult (__fastcall *onActorAddEffect)(ActorEventListener *this, const ActorAddEffectEvent *);
  EventResult (__fastcall *onActorKilled)(ActorEventListener *this, const ActorKilledEvent *);
  EventResult (__fastcall *onActorRemoveEffect)(ActorEventListener *this, const ActorRemoveEffectEvent *);
  EventResult (__fastcall *onKnockBack)(ActorEventListener *this, const KnockBackEvent *);
  EventResult (__fastcall *onMountTaming)(ActorEventListener *this, const MountTamingEvent *);
  EventResult (__fastcall *onActorAnimationChanged)(ActorEventListener *this, const ActorAnimationChangedEvent *);
  EventResult (__fastcall *onSendActorAddBuff)(ActorEventListener *this, Actor *, const AttributeInstance *, const std::string *, int, bool, int, int, int);
};

```

### `ScriptServerBlockEventListener`
```
struct __cppobj ScriptServerBlockEventListener : BlockEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerBlockEventListener_vtbl`
```
struct /*VFT*/ ScriptServerBlockEventListener_vtbl
{
  void (__fastcall *~BlockEventListener)(BlockEventListener *this);
  EventResult (__fastcall *onBlockPlacedByPlayer)(BlockEventListener *this, Player *, const Block *, const BlockPos *, bool);
  EventResult (__fastcall *onBlockDestroyedByPlayer)(BlockEventListener *this, Player *, const std::string, const BlockPos *);
  EventResult (__fastcall *onBlockMovedByPiston)(BlockEventListener *this, const BlockPos *, const BlockPos *, const PistonBlockActor::PistonState);
  EventResult (__fastcall *onBlockDestructionStopped)(BlockEventListener *this, Player *, const BlockPos *, int);
  EventResult (__fastcall *onBlockDestructionStarted)(BlockEventListener *this, Player *, const BlockPos *);
  EventResult (__fastcall *onBlockInteractedWith)(BlockEventListener *this, Player *, const BlockPos *);
  EventResult (__fastcall *onBlockExploded)(BlockEventListener *this, const BlockPos *, const Block *, Actor *);
  EventResult (__fastcall *onBlockModified)(BlockEventListener *this, const BlockPos *, const Block *, const Block *);
  EventResult (__fastcall *onChestBlockTryPaired)(BlockEventListener *this, const ChestBlockTryPairEvent *);
  EventResult (__fastcall *onUnknownBlockReceived)(BlockEventListener *this, Level *, const NewBlockID *, unsigned __int16);
};

```

### `ScriptServerPacketEventListener`
```
struct __cppobj ScriptServerPacketEventListener : NetworkPacketEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerPacketEventListener_vtbl`
```
struct /*VFT*/ ScriptServerPacketEventListener_vtbl
{
  void (__fastcall *~NetworkPacketEventListener)(NetworkPacketEventListener *this);
  EventResult (__fastcall *onPacketReceivedFrom)(NetworkPacketEventListener *this, const PacketHeader *, const Packet *);
};

```

### `ScriptTelemetryEventListener`
```
struct __cppobj __declspec(align(8)) ScriptTelemetryEventListener : ScriptEventListener
{
  IMinecraftEventing *mEventing;
  const bool mClientside;
};

```

### `ScriptTelemetryEventListener_vtbl`
```
struct /*VFT*/ ScriptTelemetryEventListener_vtbl
{
  void (__fastcall *~ScriptEventListener)(ScriptEventListener *this);
  EventResult (__fastcall *onScriptGetComponent)(ScriptEventListener *this, const std::string *, RegistrationType, bool);
  EventResult (__fastcall *onScriptListenForEvent)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptBroadcastEvent)(ScriptEventListener *this, const std::string *, RegistrationType, bool);
  EventResult (__fastcall *onScriptRegisterView)(ScriptEventListener *this);
  EventResult (__fastcall *onScriptRegisterSpatialView)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptAddFilterToView)(ScriptEventListener *this, const std::string *);
  EventResult (__fastcall *onScriptLoaded)(ScriptEventListener *this, const std::string *, unsigned __int64);
  EventResult (__fastcall *onScriptRan)(ScriptEventListener *this, const std::string *, const std::string *, bool);
  EventResult (__fastcall *onScriptError)(ScriptEventListener *this, const std::string *, const std::string *);
  EventResult (__fastcall *onScriptInternalError)(ScriptEventListener *this, const std::string *);
};

```

### `SimplexNoise`
```
struct __cppobj SimplexNoise
{
  Vec3 mOrigin;
  int mNoiseMap[512];
};

```

### `ScriptServerLevelEventListener`
```
struct __cppobj ScriptServerLevelEventListener : LevelEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerLevelEventListener_vtbl`
```
struct /*VFT*/ ScriptServerLevelEventListener_vtbl
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

### `ScriptLevelWeatherEventListener`
```
struct __cppobj ScriptLevelWeatherEventListener : LevelEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptLevelWeatherEventListener_vtbl`
```
struct /*VFT*/ ScriptLevelWeatherEventListener_vtbl
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

### `ServerInstance_vtbl`
```
struct /*VFT*/ ServerInstance_vtbl
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
};

```

### `Social::MultiplayerServiceObserver`
```
struct __cppobj Social::MultiplayerServiceObserver : Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
};

```

### `Social::MultiplayerServiceObserver_vtbl`
```
struct /*VFT*/ Social::MultiplayerServiceObserver_vtbl
{
  void (__fastcall *~Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>)(Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onInvalidPlayerJoinedLobby)(Social::MultiplayerServiceObserver *this, const mce::UUID *, const std::string *);
  void (__fastcall *onUserDisconnectedBecauseConcurrentLogin)(Social::MultiplayerServiceObserver *this, const std::string *);
};

```

### `ServerNetworkHandler::Client`
```
struct __cppobj ServerNetworkHandler::Client
{
  std::unique_ptr<ConnectionRequest> mPrimaryRequest;
  std::unordered_map<unsigned char,std::unique_ptr<SubClientConnectionRequest>> mSubClientRequests;
};

```

### `ServerNetworkHandler`
```
struct __cppobj ServerNetworkHandler : NetEventCallback, LevelListener, Social::MultiplayerServiceObserver, Social::XboxLiveUserObserver
{
  GameCallbacks *mGameCallbacks;
  Level *mLevel;
  NetworkHandler *mNetworkHandler;
  PrivateKeyManager *mServerKeys;
  ServerLocator *mServerLocator;
  PacketSender *mPacketSender;
  bool mUseAllowList;
  AllowList *mAllowList;
  PermissionsFile *mPermissionsFile;
  DenyList mServerDenyList;
  bool mRequireTrustedAuthentication;
  bool mHasDisplayedPackErrors;
  NetworkIdentifier mMyId;
  const int mMaxChunkRadius;
  MinecraftCommands *mMinecraftCommands;
  IMinecraftApp *mApp;
  Bedrock::NonOwnerPointer<TextFilteringProcessor> mTextFilteringProcessor;
  std::unique_ptr<ClientBlobCache::Server::ActiveTransfersManager> mClientCacheManager;
  std::unique_ptr<ClassroomModeNetworkHandler> mCompanionHandler;
  std::string mTenantId;
  std::string mShareableIdentityToken;
  std::mutex mValidatePlayerMutex;
  bool mAllowIncoming;
  mce::UUID mHostPlayerId;
  std::string mServerName;
  std::string mServerType;
  std::string mMultiplayerCorrelationId;
  std::vector<std::string> mTrustedKeys;
  int mMaxNumPlayers;
  std::unordered_set<mce::UUID> mKnownEmotePieceIdLookup;
  std::vector<mce::UUID> mKnownEmotePieceIds;
  std::unordered_map<NetworkIdentifier,std::unique_ptr<ServerNetworkHandler::Client>> mClients;
  __int64 GameOpChangeTime;
  bool mIsTrial;
  std::unordered_map<PackIdVersion,std::string> mPackIdToContentKey;
  std::unique_ptr<GameSpecificNetEventCallback> mGameSpecificNetEventCallback;
};

```

### `ServerMetrics`
```
struct __cppobj ServerMetrics
{
  ServerMetrics_vtbl *__vftable /*VFT*/;
};

```

### `ServerMetrics_vtbl`
```
struct /*VFT*/ ServerMetrics_vtbl
{
  void (__fastcall *~ServerMetrics)(ServerMetrics *this);
  void (__fastcall *sendPeriodicMetrics)(ServerMetrics *this, ServerInstance *);
  void (__fastcall *sendServerTickTime)(ServerMetrics *this, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *);
};

```

### `ServiceClient`
```
struct __cppobj ServiceClient
{
  ServiceClient_vtbl *__vftable /*VFT*/;
  ServiceReference<IMinecraftEventing> mEventing;
  ServiceReference<Social::IUserManager> mUserManager;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mStartTime;
  bool mHasTriedSigningIn;
  bool mHasStoppedSignIn;
  std::vector<std::shared_ptr<RequestHandler>> mSubmittedRequests;
  std::vector<std::shared_ptr<RequestHandler>> mSentRequests;
};

```

### `ServiceClient_vtbl`
```
struct /*VFT*/ ServiceClient_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `StoreUIComponent`
```
struct __cppobj StoreUIComponent
{
  StoreUIComponent_vtbl *__vftable /*VFT*/;
};

```

### `StoreUIComponent_vtbl`
```
struct /*VFT*/ StoreUIComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `StoreCatalogItemCollectionInfo`
```
struct __cppobj StoreCatalogItemCollectionInfo
{
  StoreSearchQuery mSearchQuery;
  const unsigned int mMaxOfferCount;
  const int mSalesRecentDocumentValue;
  int mLowDiscount;
  int mHighDiscount;
};

```

### `StoreItemPDPData`
```
struct __cppobj StoreItemPDPData
{
  PDPSectionType mSectionType;
  std::string mUUID;
};

```

### `StoreCatalogItem::ImageInfo`
```
struct __cppobj __declspec(align(8)) StoreCatalogItem::ImageInfo
{
  _BYTE mId[4];
  std::string mUrl;
  glm::tvec2<int,0> mDimensions;
  std::unique_ptr<ResourceLocation> mResourceLocation;
  bool mFetching;
};

```

### `StoreCatalogItem_vtbl`
```
struct /*VFT*/ StoreCatalogItem_vtbl
{
  void (__fastcall *~IStoreCatalogItem)(IStoreCatalogItem *this);
  const std::vector<PackIdVersion> *(__fastcall *getPackIdentities)(IStoreCatalogItem *this);
};

```

### `StoreActiveSaleInfo`
```
struct __cppobj StoreActiveSaleInfo
{
  float mLowDiscount;
  float mHighDiscount;
  __int64 mEndDate;
  std::vector<std::string> mProductIds;
};

```

### `StoreCatalogRepository::StoreCatalogRepoEntitlementChangeListener`
```
struct __cppobj StoreCatalogRepository::StoreCatalogRepoEntitlementChangeListener : EntitlementChangeListener
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
};

```

### `StoreCatalogRepository::StoreCatalogRepoEntitlementChangeListener_vtbl`
```
struct /*VFT*/ StoreCatalogRepository::StoreCatalogRepoEntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `StoreCatalogRepository`
```
struct __cppobj StoreCatalogRepository : Bedrock::EnableNonOwnerReferences
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  IEntitlementManager *mEntitlementManager;
  ResourcePackRepository *mResourcePackRepository;
  WorldTemplateManager *mWorldTemplateManager;
  CatalogInfo mCatalogInfo;
  std::unordered_map<std::string,std::unique_ptr<StoreCatalogItem>> mStoreCatalogItems;
  std::unordered_set<std::string> mRealmsPlusOfferPackIds;
  bool mRealmsPlusOffersFetched;
  std::function<void __cdecl(void)> mRefreshBindsCallback;
  std::function<enum ItemInstallState __cdecl(std::vector<PackIdVersion> const &)> mGetItemInstallStateCallback;
  ui::GameEventNotification mRefreshStore;
  ui::GameEventNotification mRefreshSales;
  bool mQueryingStorePromotionToast;
  unsigned int mToastQueryDocumentCount;
  _BYTE mDeviceTier[4];
  std::unordered_set<std::string> mAvailableUpdatesSet;
  std::unordered_map<std::string,RealmsStoreOffer> mRealmsCoinOffers;
  std::set<StoreCatalogItem *> mSaleOfferCollections;
  std::map<__int64,StoreActiveSaleInfo,std::greater<__int64>,std::allocator<std::pair<__int64 const ,StoreActiveSaleInfo> > > mItemsWithSaleInfo;
  __int64 mNextSaleTime;
  __int64 mSaleExpireTime;
  __int64 mSalePromotionExpireTime;
  std::shared_ptr<bool> mExistenceTracker;
  std::shared_ptr<StoreCatalogRepository::StoreCatalogRepoEntitlementChangeListener> mEntitlementChangeListener;
};

```

### `SaleComponent`
```
struct __cppobj __declspec(align(8)) SaleComponent : StoreUIComponent
{
  bool mShowOnlyDuringSale;
};

```

### `SaleComponent_vtbl`
```
struct /*VFT*/ SaleComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `SearchTermComponent`
```
struct __cppobj SearchTermComponent : StoreUIComponent
{
  std::vector<std::string> mSearchTerms;
};

```

### `SearchTermComponent_vtbl`
```
struct /*VFT*/ SearchTermComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `StoreVisualStyle`
```
struct __cppobj StoreVisualStyle
{
  StoreVisualStyleCategory mStyleType;
  std::vector<std::shared_ptr<SearchQuery>> mSearchQueries;
  std::string mTelemetryId;
  NavButtonLinksTo mNavButtonLinksTo;
  std::string mControlId;
  std::unique_ptr<HeaderComponent> mHeaderComponent;
  std::unique_ptr<NavButtonComponent> mNavButtonComponent;
  std::unique_ptr<NavButtonSectionComponent> mNavButtonSectionComponent;
  std::unique_ptr<OfferCollectionComponent> mOfferCollectionComponent;
  std::unique_ptr<PromoComponent> mPromoComponent;
  std::unique_ptr<SaleComponent> mSaleComponent;
  std::unique_ptr<SearchTermComponent> mSearchTermsComponent;
  std::unique_ptr<TreatmentComponent> mTreatmentPackComponent;
  std::unique_ptr<DocumentComponent> mDocumentReferenceComponent;
  std::unique_ptr<WorldListComponent> mWorldListComponent;
  std::unique_ptr<RecentlyViewedComponent> mRecentlyViewedComponent;
  std::unique_ptr<RealmsPlusComponent> mRealmsPlusComponent;
  std::unique_ptr<CarouselComponent> mCarouselComponent;
};

```

### `SmoothFloat`
```
struct __cppobj SmoothFloat
{
  float mTargetValue;
  float mRemainingValue;
  float mLastAmount;
};

```

### `Social::MultiplayerService`
```
struct __cppobj Social::MultiplayerService : UPNPInterface::ConnectionStateListener, Connector::ConnectionStateListener
{
  Social::MultiplayerGameInfo mCurrentGame;
  Connector *mConnector;
  Level *mLevel;
  bool mNeedRoundStartEvent;
  std::function<void __cdecl(enum Social::JoinGameStatus,Social::MultiplayerGameInfo const &,bool)> mJoinCallback;
  std::atomic<enum Social::GamePublishSetting> mPublishSetting;
  std::mutex mPlayerAddedMutex;
  Social::PresenceManager *mPresenceManager;
  IMinecraftEventing *mEventing;
  _BYTE mMultiplayerState[4];
  Social::ServiceState mServiceState;
  std::mutex mServiceStateChangeMutex;
  Social::MultiplayerServiceManager *mServiceManager;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  std::shared_ptr<std::function<void __cdecl(std::string)> > mDisplaySystemMessage;
  NetworkHandler *mNetworkHandler;
  UPNPInterface *mUPnPInterface;
  bool mIsHosting;
  std::vector<Social::GameConnectionInfo> mLocalConnectionInfo;
  std::unordered_map<std::string,Social::ClientConnectionState> mClientsConnecting;
  std::vector<Social::MultiplayerGameInfo> mCurrentList;
  std::mutex mCurrentListMutex;
  bool mIsLANConnection;
  bool mNeedToAdvertise;
  int mNeedToAdvertiseInNumFrames;
  bool mIsInitialized;
  bool mUseNetworking;
  bool mWasSessionCreated;
  const bool mEnabledAtStart;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeOfStateStart;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeOfLevelEntered;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeOfLastGameListRefresh;
  const Social::MultiplayerServiceIdentifier mServiceId;
  const Core::Path mIconPath;
  std::string mNATAddress;
};

```

### `Social::User`
```
struct __cppobj Social::User : std::enable_shared_from_this<Social::User>
{
  Social::User_vtbl *__vftable /*VFT*/;
  _BYTE mType[4];
  int mControllerId;
  const unsigned int mLocalUserId;
  bool mShouldTransferDeviceAccountToXboxLive;
  Social::UserPlatformConnectionState mPlatformConnectionState;
  bool mNeedsPlatformReconnect;
  std::mutex mUserManagerMutex;
  Bedrock::NonOwnerPointer<Social::UserManager> mUserManager;
  std::weak_ptr<IClientInstance> mAssociatedClientInstance;
  std::unique_ptr<Social::IdentityManager> mIdentities;
  std::shared_mutex mSignInMutex;
  bool mSigningIn;
  std::atomic<bool> mFinalized;
  std::vector<std::pair<enum Social::IdentityType,std::function<void __cdecl(Social::MultiIdentitySigninResult const &)> >> mSignInCallbacks;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mSignInListeners;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mSignOutListeners;
  std::mutex mSignListenerToAddMutex;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mSignInListenersToAdd;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mSignOutListenersToAdd;
  bool mEnteringOfflineMode;
  std::unique_ptr<Social::PlatformImageService> mPlatformFriendsImageService;
  std::shared_ptr<Core::FileStorageArea> mStorageArea;
  Core::PathBuffer<std::string > mSettingsDirectoryPath;
  std::unique_ptr<CloudSaveSystemWrapper> mCloudSaveSystem;
  std::shared_ptr<Options> mOptions;
};

```

### `Social::User_vtbl`
```
struct /*VFT*/ Social::User_vtbl
{
  void (__fastcall *~User)(Social::User *this);
  void (__fastcall *initStorageAreas)(Social::User *this);
  bool (__fastcall *isConnected)(Social::User *this);
  void (__fastcall *checkPrivilegeWithUIAsync)(Social::User *this, int, const std::string *, std::function<void __cdecl(enum Social::UserPermissionCheckResult)>);
  Social::UserPermissionCheckResult (__fastcall *isMultiplayerAllowed)(Social::User *this);
  Social::UserPermissionCheckResult (__fastcall *isChatAllowed)(Social::User *this);
  Social::UserPermissionCheckResult (__fastcall *isAddFriendAllowed)(Social::User *this);
  Social::UserPermissionCheckResult (__fastcall *isUserGeneratedContentAllowed)(Social::User *this);
  bool (__fastcall *isRemotePlatformUser)(Social::User *this);
  bool (__fastcall *shouldClearChatOnJoinGame)(Social::User *this);
  std::string *(__fastcall *getPlatformID)(Social::User *this, std::string *result);
  bool (__fastcall *hasPremiumPlatformAccess)(Social::User *this);
  void (__fastcall *checkPremiumPlatformStatusAsync)(Social::User *this, std::function<void __cdecl(bool)>);
  bool (__fastcall *hasPlatformIcons)(Social::User *this);
  bool (__fastcall *hasPlatformProfileCards)(Social::User *this);
  void (__fastcall *getLinkedXuids)(Social::User *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  void (__fastcall *getLinkedPlatformIds)(Social::User *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  std::string *(__fastcall *getPlatformOfflineID)(Social::User *this, std::string *result);
  std::string *(__fastcall *getPlatformOnlineID)(Social::User *this, std::string *result);
  bool (__fastcall *getLegacyOptionsData)(Social::User *this, std::vector<unsigned char> *);
  void (__fastcall *onAppResumed)(Social::User *this);
  void (__fastcall *_onGameControllerIdChanged)(Social::User *this, int, int);
  void (__fastcall *refreshPlatformParentalControlsSetting)(Social::User *this);
  void (__fastcall *_doFinalize)(Social::User *this);
  void (__fastcall *_doDisconnect)(Social::User *this);
  void (__fastcall *_doConnectAsync)(Social::User *this, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(enum Social::UserPlatformConnectionResult)> > >, bool);
  void (__fastcall *_doTick)(Social::User *this);
  const std::string *(__fastcall *_getPlatformDisplayName)(Social::User *this);
  bool (__fastcall *_checkPlatformUserXBLSignInConstraints)(Social::User *this);
  bool (__fastcall *_isPlatformParentalControlsEnabled)(Social::User *this);
  void (__fastcall *onLevelAdded)(Social::User *this, const std::string *);
  void (__fastcall *onLevelUpdated)(Social::User *this, const std::string *);
  void (__fastcall *onLevelDeleted)(Social::User *this, const std::string *);
};

```

### `Social::Identity`
```
struct __cppobj Social::Identity : std::enable_shared_from_this<Social::Identity>
{
  Social::Identity_vtbl *__vftable /*VFT*/;
  Social::UserProfile mUserProfile;
  std::weak_ptr<Options> mOwnerOptions;
  bool mInitialized;
  std::string mId;
  Social::AuthToken mAuthToken;
  IMinecraftEventing *mEventing;
};

```

### `Social::SingleIdentitySignInResult`
```
struct __cppobj Social::SingleIdentitySignInResult
{
  _BYTE mResult[4];
  bool mNewAccount;
  std::string mGamertagHint;
};

```

### `Social::AuthToken`
```
struct __cppobj Social::AuthToken : NewType<std::string >
{
};

```

### `Social::IUserDataObject`
```
struct __cppobj Social::IUserDataObject
{
  Social::IUserDataObject_vtbl *__vftable /*VFT*/;
};

```

### `Social::IUserDataObject_vtbl`
```
struct /*VFT*/ Social::IUserDataObject_vtbl
{
  void (__fastcall *~IUserDataObject)(Social::IUserDataObject *this);
  const std::string *(__fastcall *getObjectName)(Social::IUserDataObject *this);
  bool (__fastcall *fillFromJSON)(Social::IUserDataObject *this, const Json::Value *);
  Json::Value *(__fastcall *toJSONObject)(Social::IUserDataObject *this, Json::Value *result);
};

```

### `Social::UserData`
```
const struct __cppobj Social::UserData
{
  const bool mIsValid;
  std::string mValue;
};

```

### `Social::Identity_vtbl`
```
struct /*VFT*/ Social::Identity_vtbl
{
  void (__fastcall *~Identity)(Social::Identity *this);
  Social::IdentityEventResponse (__fastcall *initialize)(Social::Identity *this, std::weak_ptr<Options>, const Core::PathBuffer<std::string > *);
  Social::IdentityType (__fastcall *getType)(Social::Identity *this);
  void (__fastcall *tick)(Social::Identity *this);
  void (__fastcall *signIn)(Social::Identity *this, Social::User *, bool, std::function<void __cdecl(Social::SingleIdentitySignInResult)>, std::function<void __cdecl(std::string,std::string)>);
  void (__fastcall *cancelSignIn)(Social::Identity *this);
  void (__fastcall *signOut)(Social::Identity *this, std::function<void __cdecl(bool)>);
  void (__fastcall *doDisconnect)(Social::Identity *this);
  bool (__fastcall *isSignedIn)(Social::Identity *this);
  bool (__fastcall *isNewAccount)(Social::Identity *this);
  bool (__fastcall *signinInProgress)(Social::Identity *this);
  void (__fastcall *onDisplayNameUpdate)(Social::Identity *this, const std::string *);
  const std::unordered_set<enum Social::IdentityType> *(__fastcall *getDependencies)(Social::Identity *this);
  Social::IdentityEventResponse (__fastcall *onIdentitySignIn)(Social::Identity *this, Social::Identity *);
  Social::IdentityEventResponse (__fastcall *onIdentitySignOut)(Social::Identity *this, Social::IdentityType);
  const std::string *(__fastcall *getId)(Social::Identity *this);
  void (__fastcall *getAuthToken)(Social::Identity *this, const std::string *, std::function<void __cdecl(Social::AuthToken)>);
  void (__fastcall *getUserDataObject)(Social::Identity *this, Social::IUserDataObject *);
  void (__fastcall *setUserDataObject)(Social::Identity *this, const Social::IUserDataObject *);
  const Social::UserData *(__fastcall *getUserData)(Social::Identity *this, const Social::UserData *result, const std::string *);
  void (__fastcall *setUserData)(Social::Identity *this, const std::string *, const Social::UserData *);
  void (__fastcall *executeCloudScript)(Social::Identity *this, const std::string *, const Json::Value *, bool, int, std::function<void __cdecl(bool,Json::Value)>);
  bool (__fastcall *hasCachedCredentials)(Social::Identity *this);
  void (__fastcall *clearCachedCredentials)(Social::Identity *this);
  const std::string *(__fastcall *getDisplayName)(Social::Identity *this);
  void (__fastcall *setPresence)(Social::Identity *this, const std::string *);
  void (__fastcall *clearPresence)(Social::Identity *this);
  bool (__fastcall *hasPlayedLegacyGame)(Social::Identity *this, std::shared_ptr<Social::User const >);
  bool (__fastcall *hasPremiumPlatformAccess)(Social::Identity *this);
  void (__fastcall *checkPremiumPlatformStatusAsync)(Social::Identity *this, std::function<void __cdecl(bool)>);
  bool (__fastcall *hasPlatformIcons)(Social::Identity *this);
  bool (__fastcall *hasPlatformProfileCards)(Social::Identity *this);
  void (__fastcall *setMinecraftEventing)(Social::Identity *this, IMinecraftEventing *);
};

```

### `Social::UserProfile`
```
struct __cppobj Social::UserProfile
{
  std::string mDisplayName;
};

```

### `Social::IdentityManager`
```
struct __cppobj Social::IdentityManager
{
  std::unordered_map<enum Social::IdentityType,std::shared_ptr<Social::Identity>> mIdentityMap;
};

```

### `Social::PlatformImageService`
```
struct __cppobj Social::PlatformImageService
{
  bool mCacheAvailable;
  Core::PathBuffer<std::string > mImageCache;
};

```

### `SaveContainer`
```
struct __cppobj __declspec(align(8)) SaveContainer : Core::FileStorageAreaObserver
{
  GameSaveSystem *mSaveSystem;
  std::shared_ptr<Core::FileStorageArea> mObservedStorageArea;
  std::string mContainerName;
  std::string mLevelId;
  SpinLock mLock;
  SpinLock mDelayLock;
  std::atomic<bool> mIsActive;
  std::atomic<bool> mIsAwaitingTask;
  std::atomic<bool> mEnableAutomaticCommits;
  std::atomic<bool> mIsNewWorld;
  bool mShouldObserveStorage;
  __declspec(align(4)) RetryDelay mDelayTimer;
  std::shared_ptr<bool> mExistenceTracker;
  std::set<std::string> mFilesToAdd;
  std::set<std::string> mFilesToDelete;
  __int64 mLastCheckpointTimestamp;
  std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > > mManifestSyncContext;
  std::set<std::string> hack_stagedFilesToDelete;
  bool hack_IsEmbeddedContainer;
};

```

### `SaveContainer_vtbl`
```
struct /*VFT*/ SaveContainer_vtbl
{
  void (__fastcall *~Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onBeginWrites)(Core::FileStorageAreaObserver *this);
  void (__fastcall *_onEndWrites)(Core::FileStorageAreaObserver *this);
  void (__fastcall *_onWriteFile)(Core::FileStorageAreaObserver *this, Core::Path);
  void (__fastcall *_onDeleteFile)(Core::FileStorageAreaObserver *this, Core::Path);
};

```

### `Social::ClientConnectionState`
```
struct __cppobj Social::ClientConnectionState
{
  _BYTE mState[4];
  Social::GameConnectionInfo mConnectionInfo;
};

```

### `Social::PresenceTickable`
```
struct __cppobj __declspec(align(8)) Social::PresenceTickable
{
  Social::PresenceTickable_vtbl *__vftable /*VFT*/;
  int mState;
  bool mDoTick;
  std::chrono::duration<__int64,std::ratio<1,1000> > mTickInterval;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastUpdate;
  Social::PresenceTickableType mType;
};

```

### `Social::PresenceTickable_vtbl`
```
struct /*VFT*/ Social::PresenceTickable_vtbl
{
  void (__fastcall *~PresenceTickable)(Social::PresenceTickable *this);
  std::shared_ptr<RequestHandler> *(__fastcall *getPresenceRequest)(Social::PresenceTickable *this, std::shared_ptr<RequestHandler> *result, const ServiceClient *, const std::string *);
};

```

### `Social::PresenceManager`
```
struct __cppobj Social::PresenceManager : ServiceClient
{
  std::map<enum Social::PresenceTickableType,std::unique_ptr<Social::PresenceTickable>> mTickables;
};

```

### `Social::PresenceManager_vtbl`
```
struct /*VFT*/ Social::PresenceManager_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `Social::MultiplayerServiceManager`
```
struct __cppobj Social::MultiplayerServiceManager : Bedrock::EnableNonOwnerReferences
{
  std::vector<std::shared_ptr<Social::MultiplayerService>> mServices;
  std::atomic<bool> mServiceGameListUpdated;
  std::vector<Social::MultiplayerGameInfo> mGameList;
  std::mutex mGameListMutex;
  UPNPInterface *mUPnPInterface;
  Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> mObserverSubject;
  ServiceRegistrationToken<Social::MultiplayerServiceManager> mServiceRegistrationToken;
};

```

### `Social::MultiplayerService_vtbl`
```
struct /*VFT*/ Social::MultiplayerService_vtbl
{
  void (__fastcall *~ConnectionStateListener)(UPNPInterface::ConnectionStateListener *this);
  void (__fastcall *onConnectionStateChanged)(UPNPInterface::ConnectionStateListener *this, const std::string *, const std::string *, unsigned int, unsigned int, unsigned int, const std::string *);
  void (__fastcall *finalize)(Social::MultiplayerService *this);
  bool (__fastcall *isFinalizationComplete)(Social::MultiplayerService *this);
  void (__fastcall *login)(Social::MultiplayerService *this, const bool);
  void (__fastcall *logoff)(Social::MultiplayerService *this);
  void (__fastcall *onPrimaryUserConnectComplete)(Social::MultiplayerService *this, const Social::UserPlatformConnectionResult, const bool);
  void (__fastcall *getFriendProfiles)(Social::MultiplayerService *this, std::function<void __cdecl(std::vector<Social::PlatformUserProfileData> &)>, const bool);
  void (__fastcall *getPlatformProfile)(Social::MultiplayerService *this, const std::string *, std::function<void __cdecl(Social::PlatformUserProfileData &)>, bool);
  void (__fastcall *getPlatformProfiles)(Social::MultiplayerService *this, const std::vector<std::string> *, std::function<void __cdecl(std::vector<Social::PlatformUserProfileData> &&)>, bool);
  void (__fastcall *setInviteHandle)(Social::MultiplayerService *this, const std::string *, const bool);
  void (__fastcall *clearInviteHandle)(Social::MultiplayerService *this);
  Social::InviteHandleCheck (__fastcall *checkIsInviteForCurrentGame)(Social::MultiplayerService *this);
  bool (__fastcall *needToHandleInvite)(Social::MultiplayerService *this);
  bool (__fastcall *isInviteEnabled)(Social::MultiplayerService *this);
  void (__fastcall *invitePlayers)(Social::MultiplayerService *this, const std::vector<std::string> *);
  const std::string *(__fastcall *getInviteHandle)(Social::MultiplayerService *this, const std::string *result);
  unsigned int (__fastcall *getMaxInvitablePlayers)(Social::MultiplayerService *this);
  bool (__fastcall *isPlayerOnline)(Social::MultiplayerService *this, const std::string *);
  void (__fastcall *showPlayerProfile)(Social::MultiplayerService *this, const std::string *);
  std::vector<std::string> *(__fastcall *getPlayerUidsInLobby)(Social::MultiplayerService *this, std::vector<std::string> *result);
  RelationshipStatus (__fastcall *mayChatWith)(Social::MultiplayerService *this, const std::string *);
  bool (__fastcall *hasID)(Social::MultiplayerService *this, const std::string *);
  std::string *(__fastcall *getXBLInfo)(Social::MultiplayerService *this, std::string *result);
  bool (__fastcall *enforcePlatformIdentification)(Social::MultiplayerService *this);
  void (__fastcall *setRealmToJoin)(Social::MultiplayerService *this, const Realms::World *);
  void (__fastcall *clearRealmToJoin)(Social::MultiplayerService *this);
  bool (__fastcall *isInRealm)(Social::MultiplayerService *this);
  Realms::World *(__fastcall *getRealmWorld)(Social::MultiplayerService *this);
  void (__fastcall *sendRealmsAllowListNotification)(Social::MultiplayerService *this, std::vector<std::string>);
  void (__fastcall *setRealmGameInfo)(Social::MultiplayerService *this, Level *);
  bool (__fastcall *isInSession)(Social::MultiplayerService *this);
  bool (__fastcall *isInThirdPartyServer)(Social::MultiplayerService *this);
  bool (__fastcall *isInSiftConnectedService)(Social::MultiplayerService *this);
  const std::string *(__fastcall *getErrorMessage)(Social::MultiplayerService *this, Social::JoinGameStatus);
  bool (__fastcall *isLoggedIn)(Social::MultiplayerService *this);
  bool (__fastcall *isServiceAvailable)(Social::MultiplayerService *this);
  bool (__fastcall *isServiceAllowed)(Social::MultiplayerService *this);
  void (__fastcall *_initialize)(Social::MultiplayerService *this);
  void (__fastcall *_enable)(Social::MultiplayerService *this, std::function<void __cdecl(enum Social::EnableResult)>);
  void (__fastcall *_disable)(Social::MultiplayerService *this, std::function<void __cdecl(bool)>);
  void (__fastcall *_advertiseGame)(Social::MultiplayerService *this);
  void (__fastcall *_onExitLevel)(Social::MultiplayerService *this, Social::User *);
  void (__fastcall *_joinGame)(Social::MultiplayerService *this, const std::string *, std::function<void __cdecl(enum Social::JoinGameStatus,Social::MultiplayerGameInfo const &,bool)>);
  bool (__fastcall *_canJoin)(Social::MultiplayerService *this);
  void (__fastcall *_leaveSession)(Social::MultiplayerService *this);
  bool (__fastcall *_shouldAddGameToGameList)(Social::MultiplayerService *this, const Social::MultiplayerGameInfo *);
  const std::string *(__fastcall *_getPrimaryUserNickname)(Social::MultiplayerService *this, const std::string *result);
  const std::string *(__fastcall *_getPrimaryUserId)(Social::MultiplayerService *this, const std::string *result);
  void (__fastcall *_onMultiplayerStateChange)(Social::MultiplayerService *this, Social::MultiplayerState, Social::MultiplayerState);
  void (__fastcall *_setLobbyProperties)(Social::MultiplayerService *this);
  void (__fastcall *_processExecutionQueue)(Social::MultiplayerService *this);
  bool (__fastcall *_buildGameListIfNeeded)(Social::MultiplayerService *this, bool);
  void (__fastcall *_buildGameList)(Social::MultiplayerService *this, bool);
  void (__fastcall *_getAllActiveSessions)(Social::MultiplayerService *this, bool);
  void (__fastcall *_updatePlayerStatus)(Social::MultiplayerService *this, const std::string *);
  std::vector<Social::GameConnectionInfo> *(__fastcall *_getLocalConnectionInfo)(Social::MultiplayerService *this, std::vector<Social::GameConnectionInfo> *result);
  void (__fastcall *_findOrCreateRealmLobby)(Social::MultiplayerService *this);
  void (__fastcall *_tickMultiplayerManager)(Social::MultiplayerService *this, bool);
  void (__fastcall *_setMemberProperties)(Social::MultiplayerService *this, Social::ClientConnectionState *);
  void (__fastcall *_removePrimaryUserFromSession)(Social::MultiplayerService *this);
  void (__fastcall *_defaultRichPresence)(Social::MultiplayerService *this, Social::User *);
  void (__fastcall *_updateRichPresence)(Social::MultiplayerService *this, Social::User *, const Level *);
  void (__fastcall *_createSession)(Social::MultiplayerService *this);
  void (__fastcall *_updateLobby)(Social::MultiplayerService *this, bool);
  bool (__fastcall *_isMutedPlayer)(Social::MultiplayerService *this, const std::string *);
  bool (__fastcall *_isBlockedPlayer)(Social::MultiplayerService *this, const std::string *);
  RelationshipStatus (__fastcall *_hasChatPrivileges)(Social::MultiplayerService *this, const std::string *);
  void (__fastcall *_onClientEnteredInGame)(Social::MultiplayerService *this, const std::string *);
  Social::GamePublishSetting (__fastcall *_getGamePublishSettingFromLevel)(Social::MultiplayerService *this, const Level *);
  bool (__fastcall *_getShouldBroadcastFromLevel)(Social::MultiplayerService *this, const Level *);
  void (__fastcall *_onMaxPlayerCountUpdated)(Social::MultiplayerService *this, const int);
  void (__fastcall *_onJoinGameCancelled)(Social::MultiplayerService *this);
};

```

### `ServiceRegistrationToken<Social::MultiplayerServiceManager>`
```
struct __cppobj ServiceRegistrationToken<Social::MultiplayerServiceManager>
{
  Social::MultiplayerServiceManager *mService;
};

```

### `SkinPackKeyProvider`
```
struct __cppobj SkinPackKeyProvider : IContentKeyProvider
{
};

```

### `SkinPackKeyProvider_vtbl`
```
struct /*VFT*/ SkinPackKeyProvider_vtbl
{
  void (__fastcall *~IContentKeyProvider)(IContentKeyProvider *this);
  std::string *(__fastcall *getContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  std::string *(__fastcall *getAlternateContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  bool (__fastcall *requireEncryptedReads)(IContentKeyProvider *this);
  void (__fastcall *setTempContentKeys)(IContentKeyProvider *this, const std::unordered_map<ContentIdentity,std::string> *);
  void (__fastcall *clearTempContentKeys)(IContentKeyProvider *this);
};

```

### `SkinPack`
```
struct __cppobj SkinPack
{
  bool isDeleteed;
  Pack *mPack;
  std::string mName;
  std::string mLocName;
  std::string mSerializableName;
  Json::Value mGeometryData;
  bool mRequireTrustedContent;
  std::vector<Skin> mSkins;
};

```

### `SkinRepository::LoadListener`
```
struct __cppobj SkinRepository::LoadListener
{
  std::weak_ptr<bool> mExistenceTracker;
  std::function<void __cdecl(mce::UUID const &)> mCallback;
};

```

### `SkinRepositoryProxyCallbacks`
```
struct __cppobj SkinRepositoryProxyCallbacks
{
  std::function<bool __cdecl(void)> mIsContentLoading;
};

```

### `SkinRepositoryProxy`
```
struct __cppobj SkinRepositoryProxy
{
  SkinRepositoryProxyCallbacks mCallbacks;
};

```

### `SkinRepository`
```
struct __cppobj __declspec(align(8)) SkinRepository : ImagePickingCallback, std::enable_shared_from_this<SkinRepository>
{
  mce::TextureGroup *mTextureGroup;
  PackManifestFactory *mManifestFactory;
  IPackSourceFactory *mPackSourceFactory;
  IEntitlementManager *mEntitlementManager;
  std::unique_ptr<TaskGroup> mTaskGroup;
  SkinPackKeyProvider mKeyProvider;
  std::unordered_map<mce::UUID,SemVersion> mKnownSkinPackIdentities;
  std::vector<mce::UUID> mUntrustedSkinPackIdentities;
  std::unique_ptr<PackSource> mAllSkinPacksSource;
  Pack *mLoadingPack;
  std::vector<Pack *> mPendingLoads;
  std::vector<std::unique_ptr<SkinPack>> mLoadedSkinPacks;
  std::function<void __cdecl(bool,std::string)> mOnPickSkin;
  bool mIsPickingSkin;
  std::shared_ptr<bool> mExistenceTracker;
  std::vector<SkinRepository::LoadListener> mLoadListeners;
  std::unique_ptr<SkinRepositoryProxy> mProxy;
  bool mInitialized;
};

```

### `SkinRepository_vtbl`
```
struct /*VFT*/ SkinRepository_vtbl
{
  void (__fastcall *~ImagePickingCallback)(ImagePickingCallback *this);
  void (__fastcall *onImagePickingSuccess)(ImagePickingCallback *this, const std::string *);
  void (__fastcall *onImagePickingCanceled)(ImagePickingCallback *this);
};

```

### `SharedImageBufferTracker`
```
struct __cppobj SharedImageBufferTracker
{
  const ImageBufferResourceManager *mImageBufferResourceManager;
};

```

### `ServiceDrivenImageRepository`
```
struct __cppobj __declspec(align(8)) ServiceDrivenImageRepository
{
  std::unordered_map<std::string,ResourceLocation> mImages;
  bool mIsReady;
  std::shared_ptr<TaskGroup> mIOTaskGroup;
  std::unordered_set<Core::PathBuffer<std::string >> mFilePathsParsed;
  Core::PathBuffer<Core::StackString<char,1024> > mFolderPath;
  std::shared_ptr<bool> mExistenceTracker;
  int mNumAttempts;
};

```

### `ScreenControllerProxy`
```
struct __cppobj __declspec(align(8)) ScreenControllerProxy
{
  ScreenControllerProxy_vtbl *__vftable /*VFT*/;
  const ScreenControllerProxyType mType;
};

```

### `ScreenControllerProxy_vtbl`
```
struct /*VFT*/ ScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `ScreenViewProxy`
```
struct __cppobj ScreenViewProxy
{
  const ScreenViewProxyCallbacks mCallbacks;
};

```

### `SceneStack::SceneStackEvent`
```
struct __cppobj __declspec(align(8)) SceneStack::SceneStackEvent
{
  SceneStack::SceneStackEvent_vtbl *__vftable /*VFT*/;
  SceneStack::SceneStackEvent::EventType mType;
};

```

### `SceneStack::SceneStackEvent_vtbl`
```
struct /*VFT*/ SceneStack::SceneStackEvent_vtbl
{
  void (__fastcall *~SceneStackEvent)(SceneStack::SceneStackEvent *this);
};

```

### `ScreenThreshold`
```
struct ScreenThreshold
{
  _BYTE mSceneType[4];
  _BYTE mSceneTypeToExclude[4];
  int mThresholdNumberOfScreens;
};

```

### `SceneStackProxy`
```
struct __cppobj SceneStackProxy
{
  const SceneStackProxyCallbacks mCallbacks;
};

```

### `SceneStack`
```
struct __cppobj SceneStack : ISceneStack
{
  std::vector<std::shared_ptr<AbstractScene>> mScreenStack;
  CachedScenes *mCachedScreens;
  std::vector<std::unique_ptr<SceneStack::SceneStackEvent>> mStackEvents;
  std::vector<std::unique_ptr<SceneStack::SceneStackEvent>> mQueuedStackEvents;
  std::vector<ScreenThreshold> mScreenThresholds;
  std::unique_ptr<TaskGroup> mDestroyScreenTaskGroup;
  int mActiveStackSize;
  int mScheduledScreenPushCount;
  int mScheduledScreenPopCount;
  bool mScreenNeedsEntrance;
  std::string mLastPoppedScreenName;
  bool mChangedThisFrame;
  bool mScreenIsTicking;
  bool mReloadScenesOnNextPop;
  bool mDeferUpdatesUntilNextTick;
  bool mBufferTextCharEvents;
  std::vector<TextCharEventData> mBufferedTextCharEventData;
  std::weak_ptr<Options> mOptions;
  Bedrock::PubSub::ScopedSubscription mAsyncLoadOptionSubscription;
  std::vector<std::pair<void *,std::function<void __cdecl(AbstractScene &)> >> mPrePushSceneCallbacks;
  std::vector<std::pair<void *,std::function<void __cdecl(std::shared_ptr<AbstractScene>)> >> mPushSceneCallbacks;
  std::vector<std::pair<void *,std::function<void __cdecl(AbstractScene &)> >> mPrePopSceneCallbacks;
  std::vector<std::pair<void *,std::function<void __cdecl(std::shared_ptr<AbstractScene>,bool)> >> mPopSceneCallbacks;
  std::unique_ptr<SceneStackProxy> mProxy;
  gsl::not_null<Bedrock::NonOwnerPointer<UIEventCoordinator> > mUIEventCoordinator;
};

```

### `SceneStack_vtbl`
```
struct /*VFT*/ SceneStack_vtbl
{
  void (__fastcall *~ISceneStack)(ISceneStack *this);
  void (__fastcall *registerPrePushSceneCallback)(ISceneStack *this, void *, std::function<void __cdecl(AbstractScene &)>);
  void (__fastcall *unregisterPrePushSceneCallback)(ISceneStack *this, void *);
  void (__fastcall *registerPushSceneCallback)(ISceneStack *this, void *, std::function<void __cdecl(std::shared_ptr<AbstractScene>)>);
  void (__fastcall *unregisterPushSceneCallback)(ISceneStack *this, void *);
  void (__fastcall *registerPrePopSceneCallback)(ISceneStack *this, void *, std::function<void __cdecl(AbstractScene &)>);
  void (__fastcall *unregisterPrePopSceneCallback)(ISceneStack *this, void *);
  void (__fastcall *registerPopSceneCallback)(ISceneStack *this, void *, std::function<void __cdecl(std::shared_ptr<AbstractScene>,bool)>);
  void (__fastcall *unregisterPopSceneCallback)(ISceneStack *this, void *);
  const AbstractScene *(__fastcall *getTopScene)(ISceneStack *this);
  AbstractScene *(__fastcall *getTopScene)(ISceneStack *this);
  std::shared_ptr<AbstractScene> *(__fastcall *getTopSceneShared)(ISceneStack *this, std::shared_ptr<AbstractScene> *result);
  void (__fastcall *schedulePopScreen)(ISceneStack *this, int);
  void (__fastcall *pushScreen)(ISceneStack *this, std::shared_ptr<AbstractScene>, bool);
};

```

### `SceneFactory`
```
struct __cppobj SceneFactory
{
  SceneFactory_vtbl *__vftable /*VFT*/;
  IClientInstance *mClient;
  IMinecraftGame *mMinecraft;
  std::unique_ptr<TaskGroup> mTaskGroup;
  bool mUseClientInstanceStack;
  hbui::SceneProvider *mSceneProvider;
  std::unique_ptr<UISoundPlayer> mSoundPlayer;
  CachedScenes *mCachedScenes;
  std::vector<std::shared_ptr<SceneFactory::PreCachePackage>> mPreCachePackages;
  std::unique_ptr<SceneFactoryProxy> mProxy;
  std::unordered_map<HashedString,std::pair<std::string,std::function<std::shared_ptr<UIScene> __cdecl(SceneFactory &,IMinecraftGame &,IClientInstance &,std::string const &,Player &,BlockPos const &,ActorUniqueID)> >> mRegisteredInGameScreens;
};

```

### `SceneFactory_vtbl`
```
struct /*VFT*/ SceneFactory_vtbl
{
  void (__fastcall *~SceneFactory)(SceneFactory *this);
  Json::Value *(__fastcall *createGlobalVars)(SceneFactory *this, Json::Value *result, UIDefRepository *);
};

```

### `SceneFactory::PreCachePackage`
```
struct __cppobj SceneFactory::PreCachePackage
{
  std::string screenName;
  std::shared_ptr<UIControlFactory> controlFactory;
  std::unique_ptr<VisualTree> visualTree;
  std::unique_ptr<LayoutManager> layoutManager;
  std::shared_ptr<UIControl> rootControl;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > taskHandle;
};

```

### `SceneFactoryProxy`
```
struct __cppobj SceneFactoryProxy
{
  const SceneFactoryProxyCallbacks mCallbacks;
};

```

### `ScreenController::ButtonEventCallbackKeyHasher`
```
struct __cppobj ScreenController::ButtonEventCallbackKeyHasher
{
};

```

### `ScreenController_vtbl`
```
struct /*VFT*/ ScreenController_vtbl
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
};

```

### `SpriteComponent`
```
struct __cppobj SpriteComponent : RenderableComponent
{
  ResourceLocation mResourceLocation;
  UITextureInfoPtr mUITextureInfo;
  UITextureInfoPtr mBackCompatUITexture;
  mce::TexturePtr mTexture;
  _BYTE mUIMaterialType[4];
  glm::tvec2<float,0> mUV;
  glm::tvec2<float,0> mUVSize;
  mce::Color mColor;
  ui::SliceSize mNineSliceSize;
  ui::ClipDirection mClipDirection;
  glm::tvec2<float,0> mTiledScale;
  glm::tvec2<float,0> mInvTextureSize;
  _BYTE mTiled[4];
  float mClipRatio;
  __int8 mClipPixelPerfect : 1;
  __int8 mHasNineSlice : 1;
  __int8 mPixelPerfect : 1;
  __int8 mKeepRatio : 1;
  __int8 mFilled : 1;
  __int8 mEnableGrayscale : 1;
  __int8 mEnableBilinear : 1;
  __int8 mTriggerDebugLog : 1;
  __int8 mForceReloadTexture : 1;
  __int8 mTextureLoaded : 1;
  __int8 mAllowDebugTextureReplacement : 1;
  __int8 mIsNewNineSlice : 1;
  float mNewNineSliceTop;
  float mNewNineSliceBottom;
  float mNewNineSliceLeft;
  float mNewNineSliceRight;
  int mBright;
  int mRot_NE;
  Core::PathBuffer<std::string > mZipFolder;
};

```

### `SpriteComponent_vtbl`
```
struct /*VFT*/ SpriteComponent_vtbl
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
  void (__fastcall *updateUI)(RenderableComponent *this, const UIMeasureStrategy *);
  bool (__fastcall *overridesLayoutAxisOffset)(RenderableComponent *this, const LayoutVariableType);
  float (__fastcall *getLayoutAxisOffsetOverride)(RenderableComponent *this, const LayoutVariableType);
};

```

### `ScreenRenderBatch`
```
struct __cppobj ScreenRenderBatch
{
  std::vector<RenderControlMetadata> mRenderControls;
  std::vector<ComponentRenderBatch> mRenderBatches;
  std::unordered_map<unsigned __int64,TextureState> mTextureStates;
};

```

### `ScreenView::DelayedCommand`
```
struct __cppobj __declspec(align(8)) ScreenView::DelayedCommand
{
  std::function<std::pair<enum ui::DirtyFlag,bool> __cdecl(void)> mAction;
  ScreenView::DelayedCommandLocation location;
};

```

### `ScreenView`
```
struct __cppobj ScreenView
{
  float mLastTime;
  float mTickTime;
  long double mLastRawJoystickEventTime;
  glm::tvec2<float,0> mSize;
  int mMenuUpButtonId;
  int mMenuDownButtonId;
  int mMenuLeftButtonId;
  int mMenuRightButtonId;
  int mMenuTabLeftButtonId;
  int mMenuTabRightButtonId;
  std::array<unsigned int,2> mPointerButtonIds;
  std::shared_ptr<ScreenController> mController;
  std::unique_ptr<VisualTree> mVisualTree;
  std::vector<std::shared_ptr<UIControl>> mAlwaysBindControls;
  std::vector<std::shared_ptr<UIControl>> mInputControls;
  std::vector<std::shared_ptr<UIControl>> mScrollViewControls;
  std::vector<std::shared_ptr<UIControl>> mOutOfModalScopeScrollViewControls;
  std::vector<std::shared_ptr<UIControl>> mAnimationControls;
  std::vector<std::shared_ptr<UIControl>> mFactoryControls;
  std::vector<std::shared_ptr<UIControl>> mTextEditBoxControls;
  std::vector<std::shared_ptr<UIControl>> mAlwaysListeningInputControls;
  std::vector<std::shared_ptr<UIControl>> mRenderableControls;
  std::vector<std::shared_ptr<UIControl>> mFlyingItemRendererControls;
  std::vector<std::shared_ptr<UIControl>> mSliderControls;
  std::vector<std::shared_ptr<UIControl>> mCustomRendererControls;
  std::map<std::vector<std::shared_ptr<UIControl>> *,std::vector<std::shared_ptr<UIControl>>,std::less<std::vector<std::shared_ptr<UIControl>> *>,std::allocator<std::pair<std::vector<std::shared_ptr<UIControl>> * const,std::vector<std::shared_ptr<UIControl>> > > > mControlsToRemove;
  std::unique_ptr<ScreenRenderBatch> mRootRenderBatch;
  std::unique_ptr<UIAnimationController> mAnimationController;
  std::unordered_map<unsigned int,std::vector<std::weak_ptr<UIControl>>> mReservedButtonUpEvents;
  std::weak_ptr<UIControl> mSelectedControl;
  InputMode mInputMode;
  _BYTE mHoloInputMode[4];
  std::unique_ptr<LayoutManager> mLayoutManager;
  std::unique_ptr<FocusManager> mFocusManager;
  std::weak_ptr<UIControl> mFocusedControl;
  std::weak_ptr<ITTSEventManager> mTTSEventManager;
  bool mTextToSpeechEnabled;
  std::string mTTSSectionHeader;
  std::unordered_map<int,enum ui::CardinalDirection> mControllerStickDirections;
  int mControllerLastMoved;
  int mCursorTick;
  const float mControllerXThreshold;
  const float mControllerYThreshold;
  glm::tvec2<float,0> mControllerStickValues[4];
  GamepadCursorData mGamepadCursorData;
  glm::tvec2<float,0> mGamepadCursorPosition;
  bool mHasSetInitialPosition;
  bool mGamepadCursorFocusModeEnabled;
  bool mGamepadCursorMagnetEnabled;
  std::weak_ptr<UIControl> mGamepadMagnetControl;
  float mGamepadMoveTime;
  glm::tvec2<float,0> mGamepadTrackedDirection;
  bool mGamepadHasTapped;
  glm::tvec2<float,0> mPointerLocationPrevious;
  glm::tvec2<float,0> mTouchesPositionsPrevious[20];
  bool exitBlockHoverEvent;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPointInTime;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mCurrentTime;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mTimeAccumulator;
  const std::chrono::duration<float,std::ratio<1,1> > mFixedAnimationUpdateRate;
  float mKeyboardHeight;
  bool mShouldShowKeyboard;
  bool mInitKeyboard;
  KeyboardManager *mKeyboardManager;
  RectangleArea mRenderingAABB;
  std::vector<RectangleArea> mInputAreas;
  UIMeasureStrategy *mMeasureStrategy;
  bool mCanMoveFocus;
  bool mIsActived;
  FocusImpact mNextFocusAction;
  std::shared_ptr<UIControlFactory> mControlFactory;
  std::queue<ScreenEvent> mAnimationEvents;
  std::queue<ScreenEvent> mCustomRendererEvents;
  glm::tvec2<float,0> mStartLocation;
  float mTimeUntilNextPointerHeldEvent;
  float mDelayBetweenEachPointerHeldEvent;
  bool mShouldSendPointerHeldEvents;
  std::vector<ScreenView::DelayedCommand> mDelayedCommands;
  std::unique_ptr<ScreenViewProxy> mProxy;
  bool mIsExiting;
  bool mIsEntering;
  bool mIsInitialized;
  bool mHasHadFocus;
  bool mIsTerminating;
  bool mDirectionalButtonWasPressed;
  bool mDelayedFocusRefresh;
  TextEditFocusedListener mTextEditFocusedListener;
};

```

### `SkinRepositoryClientInterface`
```
struct __cppobj __declspec(align(8)) SkinRepositoryClientInterface
{
  bool mConsumeEntitlementsForSignIn;
  std::shared_ptr<SkinRepository> mSkinRepository;
  IClientInstance *mClient;
  PersonaRepository *mPersonaRepository;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  gsl::not_null<Bedrock::NonOwnerPointer<PersonaService> > mPersonaService;
  std::weak_ptr<Options> mOptions;
  std::function<void __cdecl(void)> mOnPersonaSyncedCallback;
  Bedrock::PubSub::ScopedSubscription mStorageOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mSkinIdOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mXuidOptionSubscription;
  SkinHandle mSelectedSkinHandle;
  SkinHandle mPendingSelectedSkin;
  bool mSelectedSkinInitialized;
  std::string mLastCustomSkinId;
  std::vector<std::string> mRecentSkinSerializableNames;
  unsigned int mUserId;
  ResourceLocation mCustomSkinLocation;
  SkinRepositoryClientInterface::SyncState mSyncState;
  unsigned int mLatestSyncId;
  __int64 mTimeStamp;
  int mSyncingCount;
  std::shared_ptr<SkinRepositoryClientInterface::SkinEntitlementChangeListener> mEntitlementChangeListener;
  std::shared_ptr<bool> mExistanceTracker;
  bool mUserUpdateInProcess;
  __int64 mPersonaSyncStartTime;
  bool mPersonaSyncInitialized;
  bool mSelectedSkinInitializedNotTimedOut;
  bool mLoadingTimeoutEventFired;
  std::vector<enum persona::ProfileType> mProfileTypesToRetry;
  std::mutex mProfileTypesToRetryLock;
  std::unordered_set<enum persona::ProfileType> mProcessingProfileTypes;
  std::mutex mProcessingProfileTypesLock;
  std::array<SkinRepositoryClientInterface::PersonaProfileLoadingState,6> mPersonaProfileLoadingStates;
  int mPersonaProfileLoadingStatesUnknownProfileCount;
  persona::ProfileType mCurrentProfileType;
  persona::ProfileType mSelectedSlot;
  std::array<persona::PersonaCharacterHandle,6> mPersonaCharacterHandles;
  bool mShouldTickAchievementCollector;
};

```

### `SkinRepositoryClientInterface::SkinEntitlementChangeListener`
```
struct __cppobj SkinRepositoryClientInterface::SkinEntitlementChangeListener : EntitlementChangeListener
{
  SkinRepositoryClientInterface *mOwner;
};

```

### `SkinRepositoryClientInterface::SkinEntitlementChangeListener_vtbl`
```
struct /*VFT*/ SkinRepositoryClientInterface::SkinEntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `SkinRepositoryClientInterface::PersonaProfileLoadingState`
```
struct __cppobj SkinRepositoryClientInterface::PersonaProfileLoadingState
{
  _BYTE mState[4];
  persona::ProfileType mProfileType;
  __int64 mTimeStarted;
};

```

### `SkinPackCollector`
```
struct __cppobj __declspec(align(4)) SkinPackCollector
{
  SkinPackCollector_vtbl *__vftable /*VFT*/;
  std::shared_ptr<bool> mExistenceTracker;
  int mNumPacksCollected;
  bool mSearchWhileCollectedPacksEmpty;
};

```

### `SkinPackModel`
```
struct __cppobj __declspec(align(8)) SkinPackModel
{
  SkinRepositoryClientInterface *mSkinRepositoryClientInterface;
  Entitlement *mEntitlement;
  PackIdVersion mPackIdentity;
  SkinPackMeta mSkinPackMetaData;
  int mFirstVisibleSkinIndex;
};

```

### `SkinPackCollector_vtbl`
```
struct /*VFT*/ SkinPackCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `SkinPackCollectionModel::SkinPackCollectionEntitlementChangeListener`
```
struct __cppobj SkinPackCollectionModel::SkinPackCollectionEntitlementChangeListener : EntitlementChangeListener
{
  SkinPackCollectionStatus *mCollectionStatus;
};

```

### `SkinPackCollectionModel::SkinPackCollectionEntitlementChangeListener_vtbl`
```
struct /*VFT*/ SkinPackCollectionModel::SkinPackCollectionEntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `SkinPackCollectionModel`
```
struct __cppobj SkinPackCollectionModel
{
  MainMenuScreenModel *mMainMenu;
  IEntitlementManager *mEntitlementManager;
  std::shared_ptr<SkinRepository> mSkinRepository;
  SkinRepositoryClientInterface *mSkinRepositoryClientInterface;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  std::shared_ptr<bool> mExistenceTracker;
  SkinPackCollectionStatus mCollectionStatus;
  int mVisibleCollectionStartIndex;
  int mVisibleCollectionEndIndex;
  bool mTryAcquireNextPage;
  std::unordered_set<mce::UUID> mHandledPackSet;
  std::vector<std::unique_ptr<SkinPackCollector>> mCollectors;
  std::shared_ptr<SkinPackModel> mVanillaSkinPack;
  std::vector<std::shared_ptr<SkinPackModel>> mSkinPacks;
  SkinPackModel mInvalidSkinPackModel;
  SkinHandle mPreviewSkin;
  std::unordered_map<mce::UUID,std::unique_ptr<IDlcBatchModel>> mTrackedImports;
  std::shared_ptr<SkinPackCollectionModel::SkinPackCollectionEntitlementChangeListener> mEntitlementChangeListener;
};

```

### `Social::UserListObserver`
```
struct __cppobj Social::UserListObserver : Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>
{
};

```

### `Social::UserListObserver_vtbl`
```
struct /*VFT*/ Social::UserListObserver_vtbl
{
  void (__fastcall *~Observer<Social::UserListObserver,Core::SingleThreadedLock>)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onUserAdded)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *);
  void (__fastcall *onUserRemoved)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *);
  void (__fastcall *onUserStorageAreaChanged)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *, std::shared_ptr<Core::FileStorageArea> *);
};

```

### `StateAnimationVariable`
```
struct __cppobj StateAnimationVariable
{
  MolangEntityVariable mVariableName;
  ExpressionNode mInput;
  std::vector<AnimationValueCurveKeyFrame> mKeyFrames;
};

```

### `SoundMapping`
```
const struct __cppobj SoundMapping
{
  SoundMapping_vtbl *__vftable /*VFT*/;
  std::unordered_map<enum LevelSoundEvent,Sound> mEventSounds;
  std::unordered_map<std::string,std::unique_ptr<std::unordered_map<enum LevelSoundEvent,Sound>>> mEntitySounds;
  std::unordered_map<enum BlockSoundType,std::unique_ptr<std::unordered_map<enum LevelSoundEvent,Sound>>> mBlockSounds;
  SoundMapping::ActorInteractiveSounds mEntityInteractiveSounds;
};

```

### `SoundMapping_vtbl`
```
struct /*VFT*/ SoundMapping_vtbl
{
  void (__fastcall *~SoundMapping)(SoundMapping *this);
};

```

### `SoundMapping::ActorInteractiveSounds`
```
struct __cppobj SoundMapping::ActorInteractiveSounds
{
  std::unordered_map<enum BlockSoundType,std::unique_ptr<std::unordered_map<enum LevelSoundEvent,Sound>>> mDefaultBlockSounds;
  std::unordered_map<std::string,std::unique_ptr<EventToSoundListMap>> mEntitySoundLists;
};

```

### `StartScreenCapabilities`
```
struct __cppobj __declspec(align(2)) StartScreenCapabilities : TypedScreenCapabilities<StartScreenCapabilities>
{
  bool mFeedbackButtonIgnored;
  bool mEduSwitchAccountsIgnored;
  bool mCoursesIgnored;
  bool mTutorialIgnored;
  bool mFeaturedWorldIgnored;
  bool mBuyGameAlwaysVisible;
  StartScreenCapabilities::PlayButtonTarget mPlayButtonTarget;
};

```

### `StartScreenCapabilities_vtbl`
```
struct /*VFT*/ StartScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `SettingsScreenCapabilities_vtbl`
```
struct /*VFT*/ SettingsScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `ScreenCapabilitiesRepo`
```
struct __cppobj ScreenCapabilitiesRepo
{
  StartScreenCapabilities mStart;
  PauseScreenCapabilities mPause;
  SettingsScreenCapabilities mGameSettings;
  EDUWorldsScreenCapabilities mEduWorlds;
  HudScreenCapabilities mHud;
  LibraryItemScreenCapabilities mLibraryItem;
};

```

### `SoundParameter`
```
struct __cppobj SoundParameter
{
  std::string mName;
  int mIndex;
  float mValue;
};

```

### `SoundEngine`
```
struct __cppobj SoundEngine : SoundPlayerInterface
{
  SoundSystemFMOD mSoundSystem;
  std::unordered_set<unsigned __int64> mFrameUniqueSoundSet;
  SoundEventRepository mSoundEventRepository;
  std::shared_ptr<Options> mOptions;
  Bedrock::PubSub::ScopedSubscription mMainVolumeOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mSoundVolumeOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mMusicVolumeOptionSubscription;
  std::vector<Bedrock::PubSub::ScopedSubscription> mSoundCategoryVolumeOptionSubscriptions;
  Bedrock::NonOwnerPointer<ResourcePackManager> mResourceManager;
  std::mutex mDelayedActionMutex;
  std::vector<SoundAction> mDelayedSoundActions;
  float mMusicVolumeMultiplier;
  bool mMuted;
  bool mFadeToStopMusic;
  SoundMapping mSounds;
  IFileAccess *mFileAccess;
  Core::PathBuffer<std::string > mDataPath;
  std::shared_mutex mResourceLoadManagerMutex;
  Bedrock::NonOwnerPointer<ResourceLoadManager> mResourceLoadManager;
  Bedrock::NonOwnerPointer<hbui::ILibrary> mUILibrary;
};

```

### `SoundSystemBase`
```
struct __cppobj SoundSystemBase
{
  SoundSystemBase_vtbl *__vftable /*VFT*/;
  float DISTANCEFACTOR;
  std::unordered_map<int,SoundListener> mSoundListeners;
};

```

### `SoundAction`
```
struct __cppobj SoundAction
{
  unsigned __int64 mActionHandle;
  SoundActionType mSoundActionType;
  std::string mOwnerEventName;
  std::string mName;
  std::string mTarget;
  float mActionParam;
  float mDelaySeconds;
  float mElapsedSeconds;
  bool mEnabled;
  bool mIsActionDelayed;
  SoundInstanceProperties mCachedProperties;
  std::function<void __cdecl(SoundInstanceProperties &)> mSoundPropertiesDelegate;
};

```

### `SoundSystemBase_vtbl`
```
struct /*VFT*/ SoundSystemBase_vtbl
{
  void (__fastcall *~SoundSystemBase)(SoundSystemBase *this);
  bool (__fastcall *preinit)(SoundSystemBase *this);
  void (__fastcall *init)(SoundSystemBase *this);
  void (__fastcall *destroy)(SoundSystemBase *this);
  void (__fastcall *setOutputDevice)(SoundSystemBase *this, SoundSystemGUID *);
  void (__fastcall *setAsyncLoadFunction)(SoundSystemBase *this, std::function<void __cdecl(SoundItem const &,std::function<void __cdecl(void)>)>);
  void (__fastcall *enable)(SoundSystemBase *this, bool);
  void (__fastcall *mute)(SoundSystemBase *this, bool);
  bool (__fastcall *addListener)(SoundSystemBase *this, const int);
  void (__fastcall *removeListener)(SoundSystemBase *this, const int);
  void (__fastcall *setListenerDirection)(SoundSystemBase *this, const int, const glm::tvec3<float,0> *, const glm::tvec3<float,0> *);
  void (__fastcall *setListenerPos)(SoundSystemBase *this, const int, float, float, float);
  void (__fastcall *setListenerVelocity)(SoundSystemBase *this, const int, float, float, float);
  void (__fastcall *setMainVolume)(SoundSystemBase *this, float);
  void (__fastcall *setMusicVolume)(SoundSystemBase *this, float);
  void (__fastcall *setSoundVolume)(SoundSystemBase *this, float);
  void (__fastcall *setSoundCategoryVolume)(SoundSystemBase *this, const std::string *, float);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *(__fastcall *loadAsync)(SoundSystemBase *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *result, const Core::Path *, bool, bool, float, float, bool);
  bool (__fastcall *loadRawFromMemory)(SoundSystemBase *this, const Core::Path *, const char *, unsigned __int64, int, int, SoundFormat);
  bool (__fastcall *loadFromMemory)(SoundSystemBase *this, const Core::Path *, const char *, unsigned __int64);
  bool (__fastcall *loadExternalEvent)(SoundSystemBase *this, const std::string *);
  void (__fastcall *unload)(SoundSystemBase *this, const Core::Path *);
  void (__fastcall *unloadAll)(SoundSystemBase *this);
  bool (__fastcall *isSoundLoaded)(SoundSystemBase *this, const Core::Path *);
  bool (__fastcall *usesSoundBanks)(SoundSystemBase *this);
  void (__fastcall *loadSoundBank)(SoundSystemBase *this, const std::string *, bool);
  void (__fastcall *unloadSoundBank)(SoundSystemBase *this, const std::string *);
  void (__fastcall *play)(SoundSystemBase *this, const std::string *);
  void (__fastcall *pause)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stop)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *stop)(SoundSystemBase *this, const std::string *);
  unsigned __int64 (__fastcall *playEvent)(SoundSystemBase *this, const SoundEvent *, const std::string *, float, float);
  unsigned __int64 (__fastcall *playEventAt)(SoundSystemBase *this, const SoundEvent *, const std::string *, float, float, float, float, float);
  unsigned __int64 (__fastcall *playAt)(SoundSystemBase *this, const Core::Path *, const SoundEvent *, const std::string *, unsigned __int64, float, float, float, float, float, bool, float, float, bool);
  unsigned __int64 (__fastcall *playEventAttached)(SoundSystemBase *this, const SoundEvent *, const std::string *, std::function<void __cdecl(SoundInstanceProperties &)> *);
  bool (__fastcall *isPlayingSound)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *fadeOut)(SoundSystemBase *this, unsigned __int64, float);
  void (__fastcall *playMusic)(SoundSystemBase *this, const std::string *, const SoundItem *);
  bool (__fastcall *isPlayingMusicEvent)(SoundSystemBase *this, const std::string *);
  bool (__fastcall *isPlayingMusic)(SoundSystemBase *this, const Core::Path *);
  bool (__fastcall *isLoadingMusic)(SoundSystemBase *this);
  const Core::PathBuffer<std::string > *(__fastcall *getCurrentlyPlayingMusicName)(SoundSystemBase *this);
  std::string *(__fastcall *getCurrentlyPlayingEventName)(SoundSystemBase *this, std::string *result);
  void (__fastcall *stopMusic)(SoundSystemBase *this);
  void (__fastcall *stopRecords)(SoundSystemBase *this);
  void (__fastcall *stopAllSounds)(SoundSystemBase *this);
  void (__fastcall *fadeMusicOut)(SoundSystemBase *this, float);
  bool (__fastcall *isMusicChannelPlaying)(SoundSystemBase *this);
  void (__fastcall *pauseMusic)(SoundSystemBase *this, bool);
  void (__fastcall *update)(SoundSystemBase *this, float);
  unsigned __int64 (__fastcall *registerLoop)(SoundSystemBase *this, const SoundItem *, const std::weak_ptr<SoundEvent>, const std::string *, std::function<void __cdecl(LoopingSoundState &)>);
  void (__fastcall *unregisterLoop)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *setUserDataUrl)(SoundSystemBase *this, const std::string *);
  void (__fastcall *enableLRU)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *disableLRU)(SoundSystemBase *this);
  void (__fastcall *setLRULSize)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *setDyLoadSet)(SoundSystemBase *this, const std::vector<std::string> *);
  void (__fastcall *clearDyLoadSet)(SoundSystemBase *this);
  int (__fastcall *getCurSoundMemory)(SoundSystemBase *this, bool);
  void (__fastcall *displayDebugStats)(SoundSystemBase *this, std::string *);
  void (__fastcall *startSnapshot)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stopSnapshot)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stopAllSnapshots)(SoundSystemBase *this);
  unsigned __int64 (__fastcall *getNewSoundHandle)(SoundSystemBase *this);
  std::optional<PlayingSoundAttributes> *(__fastcall *tryGetPlayingSoundAttributes)(SoundSystemBase *this, std::optional<PlayingSoundAttributes> *result, unsigned __int64);
};

```

### `SoundSystemFMOD::SoundInfo`
```
struct __cppobj SoundSystemFMOD::SoundInfo
{
  std::string eventName;
  std::string soundName;
  FMOD::Channel *channel;
  unsigned __int64 handle;
};

```

### `SoundSystemFMOD::LoopInfo`
```
struct __cppobj SoundSystemFMOD::LoopInfo : SoundSystemFMOD::SoundInfo
{
  float time;
  SoundItem soundItem;
  LoopingSoundState state;
  std::weak_ptr<SoundEvent> soundEvent;
  unsigned __int64 handle;
  std::function<void __cdecl(LoopingSoundState &)> getSoundState;
};

```

### `SoundDyLoadInfo`
```
struct __cppobj __declspec(align(8)) SoundDyLoadInfo
{
  std::string soundName;
  bool is3D;
  float minDistance;
  float maxDistance;
};

```

### `SoundSystemFMOD_vtbl`
```
struct /*VFT*/ SoundSystemFMOD_vtbl
{
  void (__fastcall *~SoundSystemBase)(SoundSystemBase *this);
  bool (__fastcall *preinit)(SoundSystemBase *this);
  void (__fastcall *init)(SoundSystemBase *this);
  void (__fastcall *destroy)(SoundSystemBase *this);
  void (__fastcall *setOutputDevice)(SoundSystemBase *this, SoundSystemGUID *);
  void (__fastcall *setAsyncLoadFunction)(SoundSystemBase *this, std::function<void __cdecl(SoundItem const &,std::function<void __cdecl(void)>)>);
  void (__fastcall *enable)(SoundSystemBase *this, bool);
  void (__fastcall *mute)(SoundSystemBase *this, bool);
  bool (__fastcall *addListener)(SoundSystemBase *this, const int);
  void (__fastcall *removeListener)(SoundSystemBase *this, const int);
  void (__fastcall *setListenerDirection)(SoundSystemBase *this, const int, const glm::tvec3<float,0> *, const glm::tvec3<float,0> *);
  void (__fastcall *setListenerPos)(SoundSystemBase *this, const int, float, float, float);
  void (__fastcall *setListenerVelocity)(SoundSystemBase *this, const int, float, float, float);
  void (__fastcall *setMainVolume)(SoundSystemBase *this, float);
  void (__fastcall *setMusicVolume)(SoundSystemBase *this, float);
  void (__fastcall *setSoundVolume)(SoundSystemBase *this, float);
  void (__fastcall *setSoundCategoryVolume)(SoundSystemBase *this, const std::string *, float);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *(__fastcall *loadAsync)(SoundSystemBase *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *result, const Core::Path *, bool, bool, float, float, bool);
  bool (__fastcall *loadRawFromMemory)(SoundSystemBase *this, const Core::Path *, const char *, unsigned __int64, int, int, SoundFormat);
  bool (__fastcall *loadFromMemory)(SoundSystemBase *this, const Core::Path *, const char *, unsigned __int64);
  bool (__fastcall *loadExternalEvent)(SoundSystemBase *this, const std::string *);
  void (__fastcall *unload)(SoundSystemBase *this, const Core::Path *);
  void (__fastcall *unloadAll)(SoundSystemBase *this);
  bool (__fastcall *isSoundLoaded)(SoundSystemBase *this, const Core::Path *);
  bool (__fastcall *usesSoundBanks)(SoundSystemBase *this);
  void (__fastcall *loadSoundBank)(SoundSystemBase *this, const std::string *, bool);
  void (__fastcall *unloadSoundBank)(SoundSystemBase *this, const std::string *);
  void (__fastcall *play)(SoundSystemBase *this, const std::string *);
  void (__fastcall *pause)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stop)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *stop)(SoundSystemBase *this, const std::string *);
  unsigned __int64 (__fastcall *playEvent)(SoundSystemBase *this, const SoundEvent *, const std::string *, float, float);
  unsigned __int64 (__fastcall *playEventAt)(SoundSystemBase *this, const SoundEvent *, const std::string *, float, float, float, float, float);
  unsigned __int64 (__fastcall *playAt)(SoundSystemBase *this, const Core::Path *, const SoundEvent *, const std::string *, unsigned __int64, float, float, float, float, float, bool, float, float, bool);
  unsigned __int64 (__fastcall *playEventAttached)(SoundSystemBase *this, const SoundEvent *, const std::string *, std::function<void __cdecl(SoundInstanceProperties &)> *);
  bool (__fastcall *isPlayingSound)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *fadeOut)(SoundSystemBase *this, unsigned __int64, float);
  void (__fastcall *playMusic)(SoundSystemBase *this, const std::string *, const SoundItem *);
  bool (__fastcall *isPlayingMusicEvent)(SoundSystemBase *this, const std::string *);
  bool (__fastcall *isPlayingMusic)(SoundSystemBase *this, const Core::Path *);
  bool (__fastcall *isLoadingMusic)(SoundSystemBase *this);
  const Core::PathBuffer<std::string > *(__fastcall *getCurrentlyPlayingMusicName)(SoundSystemBase *this);
  std::string *(__fastcall *getCurrentlyPlayingEventName)(SoundSystemBase *this, std::string *result);
  void (__fastcall *stopMusic)(SoundSystemBase *this);
  void (__fastcall *stopRecords)(SoundSystemBase *this);
  void (__fastcall *stopAllSounds)(SoundSystemBase *this);
  void (__fastcall *fadeMusicOut)(SoundSystemBase *this, float);
  bool (__fastcall *isMusicChannelPlaying)(SoundSystemBase *this);
  void (__fastcall *pauseMusic)(SoundSystemBase *this, bool);
  void (__fastcall *update)(SoundSystemBase *this, float);
  unsigned __int64 (__fastcall *registerLoop)(SoundSystemBase *this, const SoundItem *, const std::weak_ptr<SoundEvent>, const std::string *, std::function<void __cdecl(LoopingSoundState &)>);
  void (__fastcall *unregisterLoop)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *setUserDataUrl)(SoundSystemBase *this, const std::string *);
  void (__fastcall *enableLRU)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *disableLRU)(SoundSystemBase *this);
  void (__fastcall *setLRULSize)(SoundSystemBase *this, unsigned __int64);
  void (__fastcall *setDyLoadSet)(SoundSystemBase *this, const std::vector<std::string> *);
  void (__fastcall *clearDyLoadSet)(SoundSystemBase *this);
  int (__fastcall *getCurSoundMemory)(SoundSystemBase *this, bool);
  void (__fastcall *displayDebugStats)(SoundSystemBase *this, std::string *);
  void (__fastcall *startSnapshot)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stopSnapshot)(SoundSystemBase *this, const std::string *);
  void (__fastcall *stopAllSnapshots)(SoundSystemBase *this);
  unsigned __int64 (__fastcall *getNewSoundHandle)(SoundSystemBase *this);
  std::optional<PlayingSoundAttributes> *(__fastcall *tryGetPlayingSoundAttributes)(SoundSystemBase *this, std::optional<PlayingSoundAttributes> *result, unsigned __int64);
  void (__fastcall *playSound)(SoundSystemFMOD *this, float, float, float, float, float, FMOD::ChannelGroup *, FMOD::Channel **, FMOD::Sound **, bool, float, float, bool);
  FMOD::Sound *(__fastcall *getSubSound)(SoundSystemFMOD *this, std::shared_ptr<FMOD::Sound> *);
  bool (__fastcall *_createSystem)(SoundSystemFMOD *this);
  bool (__fastcall *_initSystem)(SoundSystemFMOD *this);
  void (__fastcall *_updateSystem)(SoundSystemFMOD *this, float);
  void (__fastcall *_destroySystem)(SoundSystemFMOD *this);
  void (__fastcall *_updateListenerAttributes)(SoundSystemFMOD *this);
  void (__fastcall *_setPositionalAttributes)(SoundSystemFMOD *this, FMOD::Channel *, FMOD::Sound *, FMOD::Sound *, float, float, float, float);
};

```

### `SoundEventRepository`
```
struct __cppobj SoundEventRepository
{
  std::mutex mSoundMapLock;
  std::unordered_map<std::string,std::shared_ptr<SoundEvent>> mSoundEventMap;
};

```

### `StoreListener`
```
struct __cppobj StoreListener
{
  StoreListener_vtbl *__vftable /*VFT*/;
};

```

### `StoreListener_vtbl`
```
struct /*VFT*/ StoreListener_vtbl
{
  void (__fastcall *~StoreListener)(StoreListener *this);
  void (__fastcall *onStoreInitialized)(StoreListener *this, bool);
  void (__fastcall *setStoreAvailable)(StoreListener *this, bool);
  void (__fastcall *onQueryProductsSuccess)(StoreListener *this, const std::vector<ProductInfo> *);
  void (__fastcall *onQueryProductsFail)(StoreListener *this);
  void (__fastcall *onPurchaseSuccessful)(StoreListener *this, const PurchaseInfo *);
  void (__fastcall *onPurchaseCanceled)(StoreListener *this, const ProductSku *);
  void (__fastcall *onPurchaseFailed)(StoreListener *this, const ProductSku *);
  void (__fastcall *onQueryPurchasesSuccess)(StoreListener *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFail)(StoreListener *this);
  void (__fastcall *onAppPurchaseSuccess)(StoreListener *this);
  void (__fastcall *onAppPurchaseFailed)(StoreListener *this);
  void (__fastcall *onAppPurchaseCanceled)(StoreListener *this);
};

```

### `StoreListenerMultistore`
```
struct __cppobj StoreListenerMultistore : StoreListener
{
};

```

### `StoreListenerMultistore_vtbl`
```
struct /*VFT*/ StoreListenerMultistore_vtbl
{
  void (__fastcall *~StoreListener)(StoreListener *this);
  void (__fastcall *onStoreInitialized)(StoreListener *this, bool);
  void (__fastcall *setStoreAvailable)(StoreListener *this, bool);
  void (__fastcall *onQueryProductsSuccess)(StoreListener *this, const std::vector<ProductInfo> *);
  void (__fastcall *onQueryProductsFail)(StoreListener *this);
  void (__fastcall *onPurchaseSuccessful)(StoreListener *this, const PurchaseInfo *);
  void (__fastcall *onPurchaseCanceled)(StoreListener *this, const ProductSku *);
  void (__fastcall *onPurchaseFailed)(StoreListener *this, const ProductSku *);
  void (__fastcall *onQueryPurchasesSuccess)(StoreListener *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFail)(StoreListener *this);
  void (__fastcall *onAppPurchaseSuccess)(StoreListener *this);
  void (__fastcall *onAppPurchaseFailed)(StoreListener *this);
  void (__fastcall *onAppPurchaseCanceled)(StoreListener *this);
  void (__fastcall *onQueryPurchasesSuccessMultistore)(StoreListenerMultistore *this, const std::string *, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFailMultistore)(StoreListenerMultistore *this, const std::string *);
};

```

### `Store`
```
struct __cppobj Store
{
  Store_vtbl *__vftable /*VFT*/;
};

```

### `Store_vtbl`
```
struct /*VFT*/ Store_vtbl
{
  void (__fastcall *~Store)(Store *this);
  bool (__fastcall *isReadyToMakePurchases)(Store *this);
  bool (__fastcall *requiresRestorePurchasesButton)(Store *this);
  bool (__fastcall *allowsSubscriptions)(Store *this);
  std::string *(__fastcall *getStoreId)(Store *this, std::string *result);
  std::string *(__fastcall *getCatalogPlatformId)(Store *this, std::string *result);
  std::string *(__fastcall *getProductSkuPrefix)(Store *this, std::string *result);
  std::string *(__fastcall *getRealmsSkuPrefix)(Store *this, std::string *result);
  void (__fastcall *queryProducts)(Store *this, const std::vector<ProductSku> *);
  bool (__fastcall *purchase)(Store *this, const ProductSku *, ProductType, const std::string *, PurchasePath);
  void (__fastcall *acknowledgePurchase)(Store *this, const PurchaseInfo *, ProductType);
  void (__fastcall *queryPurchases)(Store *this, bool);
  void (__fastcall *restorePurchases)(Store *this);
  bool (__fastcall *isTrial)(Store *this);
  void (__fastcall *purchaseGame)(Store *this, const TrialUpgradePurchaseTier);
  bool (__fastcall *isGameLicensed)(Store *this);
  bool (__fastcall *receivedLicenseResponse)(Store *this);
  bool (__fastcall *isIapSyncAvailable)(Store *this);
  ExtraLicenseData *(__fastcall *getExtraLicenseData)(Store *this, ExtraLicenseData *result);
  std::string *(__fastcall *getAppReceipt)(Store *this, std::string *result);
  void (__fastcall *registerLicenseChangeCallback)(Store *this, std::function<void __cdecl(void)>);
  void (__fastcall *handleLicenseChange)(Store *this);
  void (__fastcall *restoreFromCache)(Store *this, PurchaseCache *);
  void (__fastcall *getUserAccessTokenAsync)(Store *this, const std::string *, std::function<void __cdecl(bool,std::string)>);
  std::string *(__fastcall *getFullSKUWithMetadataFromProductSku)(Store *this, std::string *result, const std::string *);
  std::string *(__fastcall *getFullGameProductSku)(Store *this, std::string *result, const TrialUpgradePurchaseTier);
  std::string *(__fastcall *getLanguageCode)(Store *this, std::string *result);
  std::string *(__fastcall *getRegionCode)(Store *this, std::string *result);
  void (__fastcall *refreshLicenses)(Store *this);
  void (__fastcall *updateXUID)(Store *this, const std::string *);
  void (__fastcall *onNewPrimaryUser)(Store *this, const Social::User *);
  void (__fastcall *onPrimaryUserConnectedToPlatform)(Store *this, const Social::User *);
  void (__fastcall *getPurchases)(Store *this);
  void (__fastcall *showPlatformEmptyStoreDialog)(Store *this, std::function<void __cdecl(bool)> *);
  const std::string *(__fastcall *getPremiumCurrencyOfferType)(Store *this);
  const std::vector<std::string> *(__fastcall *getPremiumCurrencySkus)(Store *this, const std::vector<std::string> *result);
  const std::string *(__fastcall *buildRealmsProductSku)(Store *this, const std::string *result, RealmsOfferType, RealmsOfferPeriod, RealmsOfferTier, RealmsOfferNumber);
};

```

### `StoreSynchronizer`
```
struct __cppobj StoreSynchronizer
{
  Store *mStoreOriginator;
  Store *mStoreReceiver;
  std::unique_ptr<OculusSyncService> mServiceClient;
};

```

### `ServiceRegistrationToken<GameStore>`
```
struct __cppobj ServiceRegistrationToken<GameStore>
{
  GameStore *mService;
};

```

### `StoreFilter::CatalogCollectionInfo`
```
struct __cppobj StoreFilter::CatalogCollectionInfo
{
  std::string mPrefix;
  StoreFilter::MenuScreenType mScreenType;
  bool mOneFilterSelection;
  bool mShowInStore;
  bool mShowInInventory;
  std::vector<StoreFilter::Toggle> mToggleCollection;
};

```

### `StoreSearchInfo`
```
struct __cppobj __declspec(align(8)) StoreSearchInfo
{
  std::vector<StoreFilter::CatalogCollectionInfo> mCatalogFilterCollections;
  std::vector<std::shared_ptr<StoreVisualStyle>> mTrendingRowQueries;
  std::vector<std::string> mSkinPackSearchTerms;
  std::vector<std::string> mTexturePackSearchTerms;
  std::vector<std::string> mWorldTemplateSearchTerms;
  std::vector<std::string> mMashupPackSearchTerms;
  int mTrendingQueryOfferCount;
};

```

### `StoreConfigCustom`
```
struct __cppobj StoreConfigCustom
{
  int mStoreVersion;
  std::vector<std::string> mGlobalNotTags;
  std::vector<std::pair<enum PDPSectionType,std::string >> mPDPLayout;
  std::vector<std::shared_ptr<StoreVisualStyle>> mUpsellVisualStyles;
  StoreSearchInfo mSearchInfo;
  std::string mLatestTextureVersion;
};

```

### `StoreConfigDocument`
```
struct __cppobj StoreConfigDocument
{
  CommonDocument mCommon;
  StoreConfigCustom mCustom;
};

```

### `StoreConfigSearchResults`
```
const struct __cppobj StoreConfigSearchResults : CommonSearchResults
{
  std::vector<StoreConfigDocument> mDocuments;
};

```

### `StoreCatalogConfig`
```
struct __cppobj StoreCatalogConfig : TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>, Bedrock::EnableNonOwnerReferences
{
  StoreConfigCustom mConfigInfo;
  unsigned int mTotalSearchTermCount;
  std::mutex mCallbackMutex;
  std::vector<std::function<void __cdecl(void)>> mConfigCallbacks;
  std::mutex mStateMutex;
  StoreCatalogConfig::State mState;
  bool mDirty;
  ServiceDrivenImageRepository *mImageRepository;
  CatalogInfo mCatalogInfo;
  int mAttemptsToFetchImageBinary;
  std::string mDocumentId;
};

```

### `StoreCatalogConfig_vtbl`
```
struct /*VFT*/ StoreCatalogConfig_vtbl
{
  void (__fastcall *~TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this, const StoreConfigSearchResults *, const std::vector<std::string> *);
};

```

### `Social::InteractivityManager`
```
struct __cppobj Social::InteractivityManager
{
};

```

### `Social::InviteUriListener`
```
struct __cppobj Social::InviteUriListener : UriListener
{
  Social::MultiplayerServiceManager *mMuSeM;
};

```

### `Social::InviteUriListener_vtbl`
```
struct /*VFT*/ Social::InviteUriListener_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `Social::RealmsUriListener`
```
struct __cppobj Social::RealmsUriListener : UriListener
{
  std::shared_ptr<Options> mOptions;
};

```

### `Social::RealmsUriListener_vtbl`
```
struct /*VFT*/ Social::RealmsUriListener_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `ServiceClientScheduler`
```
struct __cppobj ServiceClientScheduler : Bedrock::EnableNonOwnerReferences
{
  ServiceClientScheduler_vtbl *__vftable /*VFT*/;
  IMinecraftEventing *mEventing;
  std::vector<std::shared_ptr<RequestHandler>> mSubmittedRequests;
  std::vector<std::shared_ptr<RequestHandler>> mSentRequests;
  ServiceRegistrationToken<ServiceClientScheduler> mServiceRegistrationToken;
};

```

### `ServiceClientScheduler_vtbl`
```
struct /*VFT*/ ServiceClientScheduler_vtbl
{
  void (__fastcall *~ServiceClientScheduler)(ServiceClientScheduler *this);
};

```

### `ServiceRegistrationToken<ServiceClientScheduler>`
```
struct __cppobj ServiceRegistrationToken<ServiceClientScheduler>
{
  ServiceClientScheduler *mService;
};

```

### `ShulkerBoxBlockActor`
```
struct __cppobj __declspec(align(8)) ShulkerBoxBlockActor : ChestBlockActor
{
  unsigned __int8 mFacing;
  bool mFacingChanged;
};

```

### `SkullBlockActor`
```
struct __cppobj SkullBlockActor : BlockActor
{
  SkullBlockActor::SkullType mSkullType;
  float mRotation;
  bool mIsMovingMouth;
  int mMouthTickCount;
};

```

### `ScriptClientContext`
```
struct __cppobj ScriptClientContext
{
  ClientInstance *mInstance;
  Level *mLevel;
  Minecraft *mMinecraft;
  PacketSender *mPacketSender;
  entt::basic_registry<enum entt::entity> *mRegistry;
  ScriptApi::ScriptReport *mScriptReport;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Entity`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::Entity
{
  ScriptTemplateFactory<ScriptClientContext>::Entity_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Entity_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptClientContext>::Entity_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptClientContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptClientContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor **, const std::string *);
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Entity>`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Entity>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptClientContext>::Entity>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Component`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::Component
{
  ScriptTemplateFactory<ScriptClientContext>::Component_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Component_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptClientContext>::Component_vtbl
{
  void (__fastcall *~Component)(ScriptTemplateFactory<ScriptClientContext>::Component *this);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, ITickingArea *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const Block *, BlockSource *, const BlockPos *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Level *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *applyComponentTo)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, ITickingArea *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const Block *, BlockSource *, const BlockPos *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Level *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *retrieveComponentFrom)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const ITickingArea *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const Block *, BlockSource *, const BlockPos *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Level *, bool *);
  bool (__fastcall *hasComponent)(ScriptTemplateFactory<ScriptClientContext>::Component *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor *, bool *);
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Component>`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Component>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptClientContext>::Component>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent
{
  ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent_vtbl *__vftable /*VFT*/;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent_vtbl`
```
struct /*VFT*/ ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent_vtbl
{
  void (__fastcall *~ReceivedEvent)(ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent *this);
  bool (__fastcall *receivedEvent)(ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEventData)(ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, const std::string *, ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent>`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent>
{
  std::unordered_map<unsigned __int64,std::shared_ptr<ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent>> mTemplates;
};

```

### `ScriptTemplateFactory<ScriptClientContext>::HashedEntries`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>::HashedEntries
{
  std::unordered_set<unsigned __int64> mHashes;
};

```

### `ScriptTemplateFactory<ScriptClientContext>`
```
struct __cppobj ScriptTemplateFactory<ScriptClientContext>
{
  ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Entity> mEntities;
  ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Entity> mItemEntities;
  ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::Component> mComponents;
  ScriptTemplateFactory<ScriptClientContext>::Entries<ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent> mReceivedEvents;
  ScriptTemplateFactory<ScriptClientContext>::HashedEntries mScriptEventDatas;
  std::shared_ptr<ScriptTemplateFactory<ScriptClientContext>::ReceivedEvent> mBroadcastEvent;
};

```

### `ScriptOnlyComponents<ScriptClientContext>`
```
struct __cppobj ScriptOnlyComponents<ScriptClientContext>
{
  std::map<std::string,Json::Value> mScriptOnlyComponentDefs;
};

```

### `ScriptOnlyEventsData<ScriptClientContext>`
```
struct __cppobj ScriptOnlyEventsData<ScriptClientContext>
{
  std::map<std::string,Json::Value> mScriptOnlyEventsData;
};

```

### `ScriptEngineWithContext<ScriptClientContext>`
```
struct __cppobj __declspec(align(8)) ScriptEngineWithContext<ScriptClientContext> : ScriptEngine
{
  const gsl::basic_string_span<char const ,-1> SCRIPT_FILE_EXTENSION;
  const std::string SCRIPT_ENTITY_TYPE;
  const std::string SCRIPT_ITEM_ENTITY_TYPE;
  ScriptClientContext mContext;
  ScriptTemplateFactory<ScriptClientContext> mFactory;
  ScriptOnlyComponents<ScriptClientContext> mScriptComponents;
  ScriptOnlyEventsData<ScriptClientContext> mScriptEvents;
  std::deque<std::unique_ptr<ScriptEventData const >> mEventQueue;
  std::unordered_map<unsigned int,ScriptCommandCallbackData> mCommandPendingCallbackQueue;
  ScriptQueries mQueries;
  bool mWorkaroundViewUpdate;
};

```

### `ScriptEngineWithContext<ScriptClientContext>_vtbl`
```
struct /*VFT*/ ScriptEngineWithContext<ScriptClientContext>_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *onLogReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onInfoReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onWarnReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onErrorReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const ActorUniqueID *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetActor)(ScriptEngine *this, const ScriptObjectBinder *, Actor **);
  bool (__fastcall *helpGetBlockSource)(ScriptEngine *this, const ScriptObjectBinder *, BlockSource **);
  bool (__fastcall *helpGetBlock)(ScriptEngine *this, const ScriptObjectBinder *, const Block **, const BlockSource *);
  bool (__fastcall *helpGetBlockPos)(ScriptEngine *this, const ScriptObjectBinder *, BlockPos *);
  bool (__fastcall *helpDefineLevel)(ScriptEngine *this, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetLevel)(ScriptEngine *this, const ScriptObjectBinder *, Level **);
  bool (__fastcall *helpDefineItemStack)(ScriptEngine *this, const ItemInstance *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *helpPopulateEcsID)(ScriptEngine *this, Json::Value *);
  bool (__fastcall *setupInterface)(ScriptEngine *this);
  bool (__fastcall *registerEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *onEventReceivedFromScriptEngine)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *destroyEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *isValidEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, bool *);
  bool (__fastcall *registerComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *);
  bool (__fastcall *destroyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *applyComponentChanges)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerScriptOnlyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const long double, const long double, const long double, const long double, const long double, const long double, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *addFilter)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *getBlock)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const BlockPos *, const ScriptApi::ScriptObjectHandle *, const ScriptObjectBinder *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ActorUniqueID *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ITickingArea *);
  void (__fastcall *onExecuteCommandCalled)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptCommand *);
  bool (__fastcall *executeCommand)(ScriptEngine *this, const ScriptCommand *);
  bool (__fastcall *onCommandOutputCallback)(ScriptEngine *this, unsigned int, Json::Value *);
  bool (__fastcall *_registerSystemObjects)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *_hasEvent)(ScriptEngine *this, const std::string *);
  bool (__fastcall *_helpRegisterSystemCallbacks)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  void (__fastcall *_handleError)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  void (__fastcall *_handleWarning)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
};

```

### `ScriptClientPacketEventListener`
```
struct __cppobj ScriptClientPacketEventListener : NetworkPacketEventListener
{
  unsigned __int8 mSubClientId;
  MinecraftClientScriptEngine *mScriptEngine;
};

```

### `ScriptClientPacketEventListener_vtbl`
```
struct /*VFT*/ ScriptClientPacketEventListener_vtbl
{
  void (__fastcall *~NetworkPacketEventListener)(NetworkPacketEventListener *this);
  EventResult (__fastcall *onPacketReceivedFrom)(NetworkPacketEventListener *this, const PacketHeader *, const Packet *);
};

```

### `ScriptClientInstanceEventListener`
```
struct __cppobj ScriptClientInstanceEventListener : ClientInstanceEventListener
{
  MinecraftClientScriptEngine *mScriptEngine;
};

```

### `ScriptClientLevelEventListener`
```
struct __cppobj ScriptClientLevelEventListener : LevelEventListener
{
  MinecraftClientScriptEngine *mScriptEngine;
};

```

### `ScriptClientLevelEventListener_vtbl`
```
struct /*VFT*/ ScriptClientLevelEventListener_vtbl
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

### `ScriptHitDetectEventListener`
```
struct __cppobj ScriptHitDetectEventListener : ClientHitDetectListener
{
  MinecraftClientScriptEngine *mScriptEngine;
};

```

### `ScriptHitDetectEventListener_vtbl`
```
struct /*VFT*/ ScriptHitDetectEventListener_vtbl
{
  void (__fastcall *~ClientHitDetectListener)(ClientHitDetectListener *this);
  EventResult (__fastcall *onChangedHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onContinuousHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onChangedPickHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onContinuousPickHitResult)(ClientHitDetectListener *this, HitResult *);
};

```

### `ServerInstanceEventCoordinator`
```
struct __cppobj ServerInstanceEventCoordinator : EventCoordinator<ServerInstanceEventListener>
{
};

```

### `SerialWorkList`
```
struct __cppobj __declspec(align(8)) SerialWorkList
{
  std::string mSeriesTitle;
  _BYTE mCDStringID[2];
  std::deque<SerialWorkList::WorkItem> mModalWorkList;
  std::vector<SerialWorkList::WorkItem> mModalWorkLog;
  long double mModalWorkItemStartTime;
  long double mSeriesStartTime;
  bool mStepWatchdogEnabled;
};

```

### `ScreenshotRecorder`
```
struct __cppobj ScreenshotRecorder
{
  bool mEnabled;
  cg::ImageBuffer mLastBackBuffer;
};

```

### `SnapshotEnv::DeleteFileEntry`
```
struct __cppobj __declspec(align(8)) SnapshotEnv::DeleteFileEntry
{
  Core::PathBuffer<std::string > mFileName;
  bool mWasRename;
};

```

### `SnapshotEnv`
```
struct __cppobj SnapshotEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  std::mutex mCreationLock;
  std::shared_mutex mWriteLock;
  std::mutex mOpenReadFileLock;
  std::mutex mPauseLock;
  std::atomic<bool> mPaused;
  std::vector<SnapshotEnv::DeleteFileEntry> mQueuedActions;
  std::mutex mQueueMutex;
};

```

### `SnapshotEnv_vtbl`
```
struct /*VFT*/ SnapshotEnv_vtbl
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

### `SaveTransactionManager`
```
struct __cppobj SaveTransactionManager
{
  std::mutex mLock;
  TaskGroup mTaskGroup;
  std::function<void __cdecl(bool)> mShowIconFunction;
};

```

### `SmallSet<DBChunkStorage *>`
```
struct __cppobj SmallSet<DBChunkStorage *>
{
  std::vector<DBChunkStorage *> c;
};

```

### `Stopwatch_vtbl`
```
struct /*VFT*/ Stopwatch_vtbl
{
  void (__fastcall *~Stopwatch)(Stopwatch *this);
  long double (__fastcall *stop)(Stopwatch *this);
  long double (__fastcall *stopContinue)(Stopwatch *this);
  void (__fastcall *print)(Stopwatch *this, const std::string *);
};

```

### `Social::MultiplayerEDU::Credentials`
```
struct __cppobj __declspec(align(8)) Social::MultiplayerEDU::Credentials
{
  std::string accessToken;
  ADRole role;
  bool expired;
};

```

### `Social::MultiplayerEDU`
```
struct __cppobj Social::MultiplayerEDU : Social::MultiplayerService, IEDUDiscoveryService, ActiveDirectoryIdentityObserver
{
  std::unique_ptr<EDUDiscovery::JoinCode> mCode;
  Core::Subject<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> mSubject;
  std::unique_ptr<EDUDiscovery::ServerID> mServer;
  std::unique_ptr<Stopwatch> mStopwatch;
  std::unique_ptr<EDUDiscovery::ServerDetails> mLastJoinedServer;
  std::unique_ptr<DiscoveryConfig> mConfig;
  std::shared_ptr<MPMCQueue<std::function<void __cdecl(Social::MultiplayerEDU &)> > > mMainThreadQueue;
  EDUDiscovery::ServerStatus mStatus;
  bool mClientNeedsToPostAddress;
  int mLastMaxPlayerCount;
  int mConsecutiveFailedHeartbeats;
  std::function<int __cdecl(void)> mGetCurrentTime;
  Social::MultiplayerEDU::Credentials mCredentials;
  std::deque<std::unique_ptr<EDUDiscovery::Dialog>> mPendingDialogs;
  __int64 mBlockedUntilTime;
};

```

### `Social::MultiplayerEDU_vtbl`
```
struct /*VFT*/ Social::MultiplayerEDU_vtbl
{
  void (__fastcall *~ConnectionStateListener)(UPNPInterface::ConnectionStateListener *this);
  void (__fastcall *onConnectionStateChanged)(UPNPInterface::ConnectionStateListener *this, const std::string *, const std::string *, unsigned int, unsigned int, unsigned int, const std::string *);
  void (__fastcall *finalize)(Social::MultiplayerService *this);
  bool (__fastcall *isFinalizationComplete)(Social::MultiplayerService *this);
  void (__fastcall *login)(Social::MultiplayerService *this, const bool);
  void (__fastcall *logoff)(Social::MultiplayerService *this);
  void (__fastcall *onPrimaryUserConnectComplete)(Social::MultiplayerService *this, const Social::UserPlatformConnectionResult, const bool);
  void (__fastcall *getFriendProfiles)(Social::MultiplayerService *this, std::function<void __cdecl(std::vector<Social::PlatformUserProfileData> &)>, const bool);
  void (__fastcall *getPlatformProfile)(Social::MultiplayerService *this, const std::string *, std::function<void __cdecl(Social::PlatformUserProfileData &)>, bool);
  void (__fastcall *getPlatformProfiles)(Social::MultiplayerService *this, const std::vector<std::string> *, std::function<void __cdecl(std::vector<Social::PlatformUserProfileData> &&)>, bool);
  void (__fastcall *setInviteHandle)(Social::MultiplayerService *this, const std::string *, const bool);
  void (__fastcall *clearInviteHandle)(Social::MultiplayerService *this);
  Social::InviteHandleCheck (__fastcall *checkIsInviteForCurrentGame)(Social::MultiplayerService *this);
  bool (__fastcall *needToHandleInvite)(Social::MultiplayerService *this);
  bool (__fastcall *isInviteEnabled)(Social::MultiplayerService *this);
  void (__fastcall *invitePlayers)(Social::MultiplayerService *this, const std::vector<std::string> *);
  const std::string *(__fastcall *getInviteHandle)(Social::MultiplayerService *this, const std::string *result);
  unsigned int (__fastcall *getMaxInvitablePlayers)(Social::MultiplayerService *this);
  bool (__fastcall *isPlayerOnline)(Social::MultiplayerService *this, const std::string *);
  void (__fastcall *showPlayerProfile)(Social::MultiplayerService *this, const std::string *);
  std::vector<std::string> *(__fastcall *getPlayerUidsInLobby)(Social::MultiplayerService *this, std::vector<std::string> *result);
  RelationshipStatus (__fastcall *mayChatWith)(Social::MultiplayerService *this, const std::string *);
  bool (__fastcall *hasID)(Social::MultiplayerService *this, const std::string *);
  std::string *(__fastcall *getXBLInfo)(Social::MultiplayerService *this, std::string *result);
  bool (__fastcall *enforcePlatformIdentification)(Social::MultiplayerService *this);
  void (__fastcall *setRealmToJoin)(Social::MultiplayerService *this, const Realms::World *);
  void (__fastcall *clearRealmToJoin)(Social::MultiplayerService *this);
  bool (__fastcall *isInRealm)(Social::MultiplayerService *this);
  Realms::World *(__fastcall *getRealmWorld)(Social::MultiplayerService *this);
  void (__fastcall *sendRealmsAllowListNotification)(Social::MultiplayerService *this, std::vector<std::string>);
  void (__fastcall *setRealmGameInfo)(Social::MultiplayerService *this, Level *);
  bool (__fastcall *isInSession)(Social::MultiplayerService *this);
  bool (__fastcall *isInThirdPartyServer)(Social::MultiplayerService *this);
  bool (__fastcall *isInSiftConnectedService)(Social::MultiplayerService *this);
  const std::string *(__fastcall *getErrorMessage)(Social::MultiplayerService *this, Social::JoinGameStatus);
  bool (__fastcall *isLoggedIn)(Social::MultiplayerService *this);
  bool (__fastcall *isServiceAvailable)(Social::MultiplayerService *this);
  bool (__fastcall *isServiceAllowed)(Social::MultiplayerService *this);
  void (__fastcall *_initialize)(Social::MultiplayerService *this);
  void (__fastcall *_enable)(Social::MultiplayerService *this, std::function<void __cdecl(enum Social::EnableResult)>);
  void (__fastcall *_disable)(Social::MultiplayerService *this, std::function<void __cdecl(bool)>);
  void (__fastcall *_advertiseGame)(Social::MultiplayerService *this);
  void (__fastcall *_onExitLevel)(Social::MultiplayerService *this, Social::User *);
  void (__fastcall *_joinGame)(Social::MultiplayerService *this, const std::string *, std::function<void __cdecl(enum Social::JoinGameStatus,Social::MultiplayerGameInfo const &,bool)>);
  bool (__fastcall *_canJoin)(Social::MultiplayerService *this);
  void (__fastcall *_leaveSession)(Social::MultiplayerService *this);
  bool (__fastcall *_shouldAddGameToGameList)(Social::MultiplayerService *this, const Social::MultiplayerGameInfo *);
  const std::string *(__fastcall *_getPrimaryUserNickname)(Social::MultiplayerService *this, const std::string *result);
  const std::string *(__fastcall *_getPrimaryUserId)(Social::MultiplayerService *this, const std::string *result);
  void (__fastcall *_onMultiplayerStateChange)(Social::MultiplayerService *this, Social::MultiplayerState, Social::MultiplayerState);
  void (__fastcall *_setLobbyProperties)(Social::MultiplayerService *this);
  void (__fastcall *_processExecutionQueue)(Social::MultiplayerService *this);
  bool (__fastcall *_buildGameListIfNeeded)(Social::MultiplayerService *this, bool);
  void (__fastcall *_buildGameList)(Social::MultiplayerService *this, bool);
  void (__fastcall *_getAllActiveSessions)(Social::MultiplayerService *this, bool);
  void (__fastcall *_updatePlayerStatus)(Social::MultiplayerService *this, const std::string *);
  std::vector<Social::GameConnectionInfo> *(__fastcall *_getLocalConnectionInfo)(Social::MultiplayerService *this, std::vector<Social::GameConnectionInfo> *result);
  void (__fastcall *_findOrCreateRealmLobby)(Social::MultiplayerService *this);
  void (__fastcall *_tickMultiplayerManager)(Social::MultiplayerService *this, bool);
  void (__fastcall *_setMemberProperties)(Social::MultiplayerService *this, Social::ClientConnectionState *);
  void (__fastcall *_removePrimaryUserFromSession)(Social::MultiplayerService *this);
  void (__fastcall *_defaultRichPresence)(Social::MultiplayerService *this, Social::User *);
  void (__fastcall *_updateRichPresence)(Social::MultiplayerService *this, Social::User *, const Level *);
  void (__fastcall *_createSession)(Social::MultiplayerService *this);
  void (__fastcall *_updateLobby)(Social::MultiplayerService *this, bool);
  bool (__fastcall *_isMutedPlayer)(Social::MultiplayerService *this, const std::string *);
  bool (__fastcall *_isBlockedPlayer)(Social::MultiplayerService *this, const std::string *);
  RelationshipStatus (__fastcall *_hasChatPrivileges)(Social::MultiplayerService *this, const std::string *);
  void (__fastcall *_onClientEnteredInGame)(Social::MultiplayerService *this, const std::string *);
  Social::GamePublishSetting (__fastcall *_getGamePublishSettingFromLevel)(Social::MultiplayerService *this, const Level *);
  bool (__fastcall *_getShouldBroadcastFromLevel)(Social::MultiplayerService *this, const Level *);
  void (__fastcall *_onMaxPlayerCountUpdated)(Social::MultiplayerService *this, const int);
  void (__fastcall *_onJoinGameCancelled)(Social::MultiplayerService *this);
};

```

### `ServiceRegistrationToken<IRayTracingOptions>`
```
struct __cppobj ServiceRegistrationToken<IRayTracingOptions>
{
  IRayTracingOptions *mService;
};

```

### `ServerInitData`
```
struct __cppobj ServerInitData
{
  ContentIdentity mPremiumTemplateContentIdentity;
  LevelSettings mSettings;
  StartIntent mStartIntent;
  std::string mLevelId;
  std::string mLevelName;
  std::string mErrorMessage;
};

```

### `SplitscreenJoinListener::SplitscreenJoinTracker`
```
struct __cppobj SplitscreenJoinListener::SplitscreenJoinTracker
{
  _BYTE mState[4];
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mSplitscreenJoinExpiration;
};

```

### `SplitscreenJoinListener`
```
struct __cppobj SplitscreenJoinListener
{
  SplitscreenJoinListener::SplitscreenJoinTracker mJoinTracker;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastToastTime;
};

```

### `SavedData`
```
struct __cppobj SavedData
{
  SavedData_vtbl *__vftable /*VFT*/;
  bool mDirty;
  std::string mId;
};

```

### `SavedData_vtbl`
```
struct /*VFT*/ SavedData_vtbl
{
  void (__fastcall *~SavedData)(SavedData *this);
  void (__fastcall *deserialize)(SavedData *this, const CompoundTag *);
  void (__fastcall *serialize)(SavedData *this, CompoundTag *);
};

```

### `Seasons`
```
struct __cppobj Seasons
{
  Dimension *mDimension;
  PerlinSimplexNoise mSnowNoise;
};

```

### `SubChunkLightUpdate`
```
struct __cppobj __declspec(align(4)) SubChunkLightUpdate
{
  SubChunkBlockPos mPos;
  Brightness mOldBrightness;
  Brightness mNewBrightness;
  Brightness mOldAbsorption;
  Brightness mNewAbsorption;
  bool mIsSkyLight;
};

```

### `ServerLevel`
```
struct __cppobj ServerLevel : Level
{
  bool mAllPlayersAreSleeping;
  bool mShouldSendSleepMessage;
  ResourcePackManager *mServerResourcePackManager;
  ResourcePackManager *mClientResourcePackManager;
  MinecraftCommands *mCommands;
  TradeTables mTradeTable;
  std::unique_ptr<FunctionManager> mFunctionManager;
  std::unique_ptr<MobEvents> mMobEvents;
  std::unordered_map<HashedString,unsigned int> mTagCache;
  std::shared_ptr<PositionTrackingDB::PositionTrackingDBServer> mServerPositionTrackerDB;
  BossbarManager mBossbarManager;
};

```

### `StackStats`
```
const struct __cppobj StackStats
{
  _BYTE mStackType[1];
  unsigned int mPackCount;
  long double mParseTime;
};

```

### `StoreSearchTelemetryData`
```
const struct __cppobj StoreSearchTelemetryData
{
  unsigned int mSearchCorrelationId;
  std::string mSearchString;
  unsigned int mResultCount;
  unsigned int mRowCount;
  int mFilterRating;
  std::string mFilterCreators;
  std::string mAndFilters;
  std::string mOrFilters;
  std::string mFilterSubType;
  std::string mSortType;
};

```

### `StructureTelemetryClientData`
```
const struct __cppobj StructureTelemetryClientData
{
  unsigned int mSizeEditCount;
  unsigned int mOffsetEditCount;
  unsigned int mRotationEditCount;
  unsigned int mMirrorEditCount;
};

```

### `SplitScreenInfo`
```
struct SplitScreenInfo
{
  int mSplitScreenPosition;
  int mActivePlayers;
  SplitScreenDirection mSplitScreenDirection;
};

```

### `StructurePoolElement`
```
const struct __cppobj StructurePoolElement
{
  StructurePoolElement_vtbl *__vftable /*VFT*/;
  std::once_flag mTemplateOnceFlag;
  std::optional<StructurePoolElement::LazyTemplate> mTemplate;
  std::string mLocation;
  StructureManager *mManager;
  bool mValid;
  __declspec(align(8)) StructurePoolElementSettings mSettings;
};

```

### `StructurePoolBlockRule`
```
struct __cppobj StructurePoolBlockRule
{
  const std::unique_ptr<IStructurePoolBlockPredicate> mSourcePredicate;
  const std::unique_ptr<IStructurePoolBlockPredicate> mTargetPredicate;
  const std::unique_ptr<IStructurePoolBlockPredicate> mPositionPredicate;
  const Block *mResultBlock;
};

```

### `StructurePoolBlockTagRule`
```
struct __cppobj StructurePoolBlockTagRule
{
  const std::unique_ptr<IStructurePoolBlockTagPredicate> mSourcePredicate;
  const std::string mResultKey;
  const std::string mResultValue;
};

```

### `StructurePoolElement_vtbl`
```
struct /*VFT*/ StructurePoolElement_vtbl
{
  BlockPos *(__fastcall *getSize)(StructurePoolElement *this, BlockPos *result, Rotation);
  std::vector<JigsawBlockInfo> *(__fastcall *getJigsawMarkers)(StructurePoolElement *this, std::vector<JigsawBlockInfo> *result, BlockPos, LegacyStructureSettings *, BlockSource *);
  std::vector<JigsawBlockInfo> *(__fastcall *getJigsawMarkers)(StructurePoolElement *this, std::vector<JigsawBlockInfo> *result, BlockPos, Rotation);
  BoundingBox *(__fastcall *getBoundingBox)(StructurePoolElement *this, BoundingBox *result, BlockPos, Rotation);
  void (__fastcall *setProjection)(StructurePoolElement *this, Projection);
  Projection (__fastcall *getProjection)(StructurePoolElement *this);
  PostProcessSettings (__fastcall *getPostProcessSettings)(StructurePoolElement *this);
  bool (__fastcall *place)(StructurePoolElement *this, BlockSource *, BlockPos, Rotation, BoundingBox, Random *, std::unordered_map<BlockPos,std::optional<ActorDefinitionIdentifier>> *, BlockPos);
  void (__fastcall *placeActors)(StructurePoolElement *this, BlockSource *, BlockPos, Rotation, Random *);
  void (__fastcall *handleJigsawBlock)(StructurePoolElement *this, BlockSource *, JigsawBlockInfo *, LegacyStructureSettings *);
  void (__fastcall *handleDataMarker)(StructurePoolElement *this, BlockSource *, BlockPos, std::string, std::unordered_map<BlockPos,std::optional<ActorDefinitionIdentifier>> *);
  bool (__fastcall *isValid)(StructurePoolElement *this);
  void (__fastcall *~StructurePoolElement)(StructurePoolElement *this);
};

```

### `StructurePoolElement::LazyTemplate`
```
struct __cppobj StructurePoolElement::LazyTemplate
{
  std::vector<JigsawBlockInfo> mJigsawMarkers;
  std::variant<std::reference_wrapper<StructureTemplate>,std::reference_wrapper<LegacyStructureTemplate> > mStructureVariant;
};

```

### `StructurePoolActorRule`
```
struct __cppobj StructurePoolActorRule
{
  const std::unique_ptr<IStructurePoolActorPredicate> mSourcePredicate;
  const std::string mResultActor;
};

```

### `StructureTemplatePool`
```
struct __cppobj StructureTemplatePool
{
  std::string mName;
  std::vector<StructurePoolElement const *> mTemplates;
  std::string mFallback;
};

```

### `SurfaceBuilderRegistry::Element`
```
struct __cppobj SurfaceBuilderRegistry::Element
{
  std::unique_ptr<ISurfaceBuilder> mBuilder;
  unsigned __int64 (__fastcall *mScoringFunc)(EntityContext *);
};

```

### `SurfaceBuilderRegistry`
```
struct __cppobj SurfaceBuilderRegistry
{
  std::vector<SurfaceBuilderRegistry::Element> mSurfaceBuilders;
};

```

### `SharedCounter<BlockLegacy>`
```
struct __cppobj SharedCounter<BlockLegacy>
{
  BlockLegacy *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SeedItemComponentLegacy`
```
struct __cppobj __declspec(align(8)) SeedItemComponentLegacy
{
  Item *mOwner;
  const Block *mResult;
  std::vector<BlockDescriptor> mTargetLandBlocks;
  bool mIsPlanting;
};

```

### `SparseContainer`
```
struct __cppobj SparseContainer : Container, ContainerContentChangeListener
{
  std::unordered_map<enum ContainerEnumName,std::function<void __cdecl(int,ItemStack const &,ItemStack const &)>> mItemNetworkChangedCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<bool __cdecl(int,ItemStackBase const &,int)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<bool __cdecl(int,ItemStackBase const &,int)> > > > mItemAllowedInSlotCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<bool __cdecl(ItemStackBase const &)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<bool __cdecl(ItemStackBase const &)> > > > mItemAllowedToAddCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<int __cdecl(int,ItemStackBase const &)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<int __cdecl(int,ItemStackBase const &)> > > > mAvailableSetCountCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<bool __cdecl(int)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<bool __cdecl(int)> > > > mValidSlotForContainerCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<bool __cdecl(ItemStackBase const &)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<bool __cdecl(ItemStackBase const &)> > > > mItemAllowedToRemoveCallbacks;
  std::unordered_map<enum ContainerEnumName,std::function<bool __cdecl(ItemStackBase const &)>,ContainerEnumNameHasher,std::equal_to<enum ContainerEnumName>,std::allocator<std::pair<enum ContainerEnumName const ,std::function<bool __cdecl(ItemStackBase const &)> > > > mItemAllowedInContainerCallbacks;
  const SparseContainerBackingSetType mBackingSetType;
  Container *mBackingContainer;
  ItemStackNetManagerBase *mItemStackNetManager;
  std::unordered_map<int,ItemStack> mItems;
};

```

### `SparseContainer_vtbl`
```
struct /*VFT*/ SparseContainer_vtbl
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
};

```

### `SimpleContainer`
```
struct __cppobj SimpleContainer : Container
{
  int mSize;
  std::vector<ItemStack> mItems;
};

```

### `SimpleContainer_vtbl`
```
struct /*VFT*/ SimpleContainer_vtbl
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
};

```

### `SavedDataStorage`
```
struct __cppobj SavedDataStorage
{
  SavedDataStorage_vtbl *__vftable /*VFT*/;
  LevelStorage *levelStorage;
  std::unordered_map<std::string,SavedData *> savedDatas;
};

```

### `SavedDataStorage_vtbl`
```
struct /*VFT*/ SavedDataStorage_vtbl
{
  void (__fastcall *~SavedDataStorage)(SavedDataStorage *this);
};

```

### `SummonSpellStage`
```
struct __cppobj __declspec(align(8)) SummonSpellStage
{
  SummonShape shape;
  SummonTarget target;
  float size;
  int baseDelay;
  int delayPerSummoning;
  int summonCap;
  float summonCapRadius;
  ActorDefinitionIdentifier entityIdentifier;
  int entityLifespan;
  int entityCount;
  LevelSoundEvent stageSoundEvent;
};

```

### `SummonSpellData`
```
struct __cppobj __declspec(align(8)) SummonSpellData
{
  float minActivationRange;
  float maxActivationRange;
  int cooldownTime;
  float weight;
  ActorFilterGroup targetFilter;
  float castDuration;
  bool doCastingAnimation;
  int particleColor;
  std::vector<SummonSpellStage> stages;
  LevelSoundEvent startSound;
};

```

### `SendEventStage`
```
struct __cppobj __declspec(align(8)) SendEventStage
{
  int delay;
  std::string eventName;
  LevelSoundEvent stageSoundEvent;
};

```

### `SendEventData`
```
struct __cppobj SendEventData
{
  float minActivationRange;
  float maxActivationRange;
  int cooldownTime;
  int castDuration;
  float weight;
  bool doCastingAnimation;
  bool lookAtTarget;
  int particleColor;
  ActorFilterGroup targetFilter;
  LevelSoundEvent startSound;
  std::vector<SendEventStage> stages;
};

```

### `StorylineDescription`
```
struct __cppobj __declspec(align(8)) StorylineDescription : ComponentDescription
{
  std::string mStoryline;
  int mRunState;
};

```

### `StorylineDescription_vtbl`
```
struct /*VFT*/ StorylineDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `SlimeMoveControlDescription`
```
struct __cppobj SlimeMoveControlDescription : MoveControlDescription
{
  FloatRange mJumpDelayTicks;
};

```

### `SlimeMoveControlDescription_vtbl`
```
struct /*VFT*/ SlimeMoveControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `StrengthDescription`
```
struct __cppobj __declspec(align(8)) StrengthDescription : AttributeDescription
{
  bool mHasComponent;
  int mStrength;
  int mMaxStrength;
};

```

### `StrengthDescription_vtbl`
```
struct /*VFT*/ StrengthDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `SpawnGroupData`
```
struct __cppobj SpawnGroupData
{
  std::string mIdentifier;
  std::vector<MobSpawnRules> mSpawnRules;
};

```

### `SpawnGroupRegistry`
```
struct __cppobj SpawnGroupRegistry : ActorSpawnRuleBase
{
  std::vector<std::unique_ptr<SpawnGroupData>> mSpawnGroupRegistry;
  std::unordered_map<std::string,SpawnGroupData *> mSpawnGroupLookupMap;
};

```

### `SpawnGroupRegistry_vtbl`
```
struct /*VFT*/ SpawnGroupRegistry_vtbl
{
  void (__fastcall *~ActorSpawnRuleBase)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getRootKey)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getFileType)(ActorSpawnRuleBase *this);
  bool (__fastcall *processPopulationControl)(ActorSpawnRuleBase *this, const std::string *, Json::Value *);
  void (__fastcall *readResourceFiles)(ActorSpawnRuleBase *this, ResourcePackManager *, std::unordered_map<std::string,std::string> *);
};

```

### `SortItemInstanceIdAux`
```
struct __cppobj SortItemInstanceIdAux
{
};

```

### `ServerPlayerEventCoordinator`
```
struct __cppobj ServerPlayerEventCoordinator : PlayerEventCoordinator
{
};

```

### `ServerLevelEventCoordinator`
```
struct __cppobj ServerLevelEventCoordinator : LevelEventCoordinator
{
};

```

### `SlotDropChance`
```
struct __cppobj SlotDropChance
{
  EquipmentSlot mSlot;
  float mDropChance;
};

```

### `SpatialActorNetworkData`
```
struct __cppobj SpatialActorNetworkData
{
  Actor *mEntity;
  bool mHasInitializedLastSent;
  bool mAutoSend;
  MoveActorAbsoluteData mLastSentMoveData;
  MoveActorAbsoluteData mLastReceivedMoveData;
  std::unordered_map<ActorUniqueID,Tick> mLastSpatialUpdateTicks;
};

```

### `StorylineComponent`
```
struct __cppobj __declspec(align(4)) StorylineComponent
{
  Actor *mEntity;
  std::string mStoryline;
  int mRunState;
  bool mCreated;
};

```

### `SurroundHitTest`
```
struct __cppobj SurroundHitTest
{
  float mRadius;
  float mSquaredRadius;
  Vec3 mPos;
  std::unordered_set<ActorUniqueID> mLastHitEntities;
  std::unordered_set<ActorUniqueID> mHitEntities;
};

```

### `serialize<BlockPos>`
```
struct __cppobj serialize<BlockPos>
{
};

```

### `StackResultStorageSharePtr<EntityRegistry>`
```
struct __cppobj StackResultStorageSharePtr<EntityRegistry>
{
  std::shared_ptr<EntityRegistry> mValue;
};

```

### `StackRefResultT<EntityRegistryRefTraits>`
```
struct __cppobj StackRefResultT<EntityRegistryRefTraits> : StackResultStorageSharePtr<EntityRegistry>
{
};

```

### `Scheduler::ScopedChangeScheduler`
```
struct __cppobj Scheduler::ScopedChangeScheduler
{
  BackgroundWorker *mParent;
};

```

### `SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block`
```
struct __cppobj SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block
{
  Lockless::WeakAtomic<unsigned __int64> front;
  unsigned __int64 localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned __int64> tail;
  unsigned __int64 localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512>::Block *> next;
  char *data;
  const unsigned __int64 sizeMask;
  char *rawThis;
};

```

### `SemVersion::any_version_constructor`
```
struct __cppobj SemVersion::any_version_constructor
{
};

```

### `Serializer_vtbl`
```
struct /*VFT*/ Serializer_vtbl
{
  void (__fastcall *~Serializer)(Serializer *this);
  bool (__fastcall *isBool)(Serializer *this);
  bool (__fastcall *isInt)(Serializer *this);
  bool (__fastcall *isString)(Serializer *this);
  bool (__fastcall *isObject)(Serializer *this);
  bool (__fastcall *isArray)(Serializer *this);
  bool (__fastcall *serializeBool)(Serializer *this, bool *);
  bool (__fastcall *serializeS8)(Serializer *this, char *);
  bool (__fastcall *serializeU8)(Serializer *this, unsigned __int8 *);
  bool (__fastcall *serializeS16)(Serializer *this, __int16 *);
  bool (__fastcall *serializeU16)(Serializer *this, unsigned __int16 *);
  bool (__fastcall *serializeS32)(Serializer *this, int *);
  bool (__fastcall *serializeU32)(Serializer *this, unsigned int *);
  bool (__fastcall *serializeFloat)(Serializer *this, float *);
  bool (__fastcall *serializeString)(Serializer *this, std::string *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned int *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int16 *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int8 *, const SerializerTraits *);
  bool (__fastcall *beginMember)(Serializer *this, unsigned __int64, std::string *);
  bool (__fastcall *beginMember)(Serializer *this, const char *, bool);
  bool (__fastcall *endMember)(Serializer *this);
  bool (__fastcall *beginArray)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginArrayItem)(Serializer *this, unsigned __int64);
  bool (__fastcall *endArrayItem)(Serializer *this);
  bool (__fastcall *endArray)(Serializer *this);
  bool (__fastcall *beginObject)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginObject)(Serializer *this);
  bool (__fastcall *endObject)(Serializer *this);
};

```

### `SecureStorageKey`
```
struct __cppobj __declspec(align(8)) SecureStorageKey
{
  std::string key;
  bool isEncoded;
};

```

### `SwStartStopper`
```
struct __cppobj SwStartStopper
{
  Stopwatch *_stopwatch;
};

```

### `SwStopper`
```
struct __cppobj SwStopper
{
  Stopwatch *_stopwatch;
};

```

### `SecureStorage`
```
struct __cppobj SecureStorage
{
  SecureStorage_vtbl *__vftable /*VFT*/;
  Core::PathBuffer<std::string > mSettingsPath;
};

```

### `SecureStorage_vtbl`
```
struct /*VFT*/ SecureStorage_vtbl
{
  void (__fastcall *~SecureStorage)(SecureStorage *this);
  bool (__fastcall *add)(SecureStorage *this, const std::string *, const std::string *);
  bool (__fastcall *addOrUpdate)(SecureStorage *this, const std::string *, const std::string *);
  bool (__fastcall *remove)(SecureStorage *this, const std::string *);
  bool (__fastcall *get)(SecureStorage *this, const std::string *, std::string *);
};

```

### `ServiceRegistrationToken<NetworkDebugManager>`
```
struct __cppobj ServiceRegistrationToken<NetworkDebugManager>
{
  NetworkDebugManager *mService;
};

```

### `ServiceRegistrationToken<Bedrock::IApplicationDataStores>`
```
struct __cppobj ServiceRegistrationToken<Bedrock::IApplicationDataStores>
{
  Bedrock::IApplicationDataStores *mService;
};

```

### `ServiceRegistrationToken<cg::IGraphicsDevicePlatformProvider>`
```
struct __cppobj ServiceRegistrationToken<cg::IGraphicsDevicePlatformProvider>
{
  cg::IGraphicsDevicePlatformProvider *mService;
};

```

### `ShieldItem`
```
struct __cppobj ShieldItem : Item
{
};

```

### `SubChunkBrightnessStorage`
```
struct __cppobj SubChunkBrightnessStorage
{
  std::array<SubChunkBrightnessStorage::LightPair,4096> mLight;
};

```

### `SubChunkBlockStorage`
```
struct __cppobj SubChunkBlockStorage
{
  SubChunkBlockStorage_vtbl *__vftable /*VFT*/;
};

```

### `SubChunkBlockStorage_vtbl`
```
struct /*VFT*/ SubChunkBlockStorage_vtbl
{
  void (__fastcall *~SubChunkBlockStorage)(SubChunkBlockStorage *this);
  bool (__fastcall *isUniform)(SubChunkBlockStorage *this, const Block *);
  const Block *(__fastcall *getBlock)(SubChunkBlockStorage *this, unsigned __int16);
  bool (__fastcall *setBlock)(SubChunkBlockStorage *this, unsigned __int16, const Block *);
  unsigned __int64 (__fastcall *getBlockTypeCapacity)(SubChunkBlockStorage *this);
  SubChunkBlockStorage::Type (__fastcall *getType)(SubChunkBlockStorage *this);
  std::unique_ptr<SubChunkBlockStorage> *(__fastcall *makePrunedCopy)(SubChunkBlockStorage *this, std::unique_ptr<SubChunkBlockStorage> *result, SubChunkBlockStorage::PruneType);
  bool (__fastcall *hasModFlag)(SubChunkBlockStorage *this);
  void (__fastcall *setModFlag)(SubChunkBlockStorage *this, bool);
  const ISubChunkBlockStoragePaletted *(__fastcall *asPalettedStorage)(SubChunkBlockStorage *this);
  ISubChunkBlockStoragePaletted *(__fastcall *asPalettedStorage)(SubChunkBlockStorage *this);
  void (__fastcall *fetchBlocksInCylinder)(SubChunkBlockStorage *this, const BlockPos *, const BlockPos *, unsigned int, unsigned int, const std::function<bool __cdecl(Block const &)> *, std::vector<BlockFetchResult> *);
  void (__fastcall *fetchBlocksInBox)(SubChunkBlockStorage *this, const BlockPos *, const BoundingBox *, const std::function<bool __cdecl(Block const &)> *, std::vector<BlockFetchResult> *);
  void (__fastcall *_serialize)(SubChunkBlockStorage *this, IDataOutput *, bool);
};

```

### `SharePtrRefTraits<FogDefinition>`
```
struct __cppobj SharePtrRefTraits<FogDefinition>
{
};

```

### `serialize<EntityNetId>`
```
struct __cppobj serialize<EntityNetId>
{
};

```

### `ServiceLocator<AppPlatform>`
```
struct __cppobj ServiceLocator<AppPlatform>
{
};

```

### `SharePtrRefTraits<PerlinSimplexNoise>`
```
struct __cppobj SharePtrRefTraits<PerlinSimplexNoise>
{
};

```

### `StackResultStorageSharePtr<PerlinSimplexNoise>`
```
struct __cppobj StackResultStorageSharePtr<PerlinSimplexNoise>
{
  std::shared_ptr<PerlinSimplexNoise> mValue;
};

```

### `SimpleBoolFilterTest_vtbl`
```
struct /*VFT*/ SimpleBoolFilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `SimpleIntFilterTest_vtbl`
```
struct /*VFT*/ SimpleIntFilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `SimpleFloatFilterTest_vtbl`
```
struct /*VFT*/ SimpleFloatFilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `SimpleHashStringFilterTest_vtbl`
```
struct /*VFT*/ SimpleHashStringFilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `SimpleTagIDFilterTest_vtbl`
```
struct /*VFT*/ SimpleTagIDFilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ServiceLocator<ContentLog>`
```
struct __cppobj ServiceLocator<ContentLog>
{
};

```

### `serialize<NetworkBlockPosition>`
```
struct __cppobj serialize<NetworkBlockPosition>
{
};

```

### `serialize<Vec2>`
```
struct __cppobj serialize<Vec2>
{
};

```

### `serialize<Vec3>`
```
struct __cppobj serialize<Vec3>
{
};

```

### `serialize<std::vector<std::unique_ptr<DataItem>> >`
```
struct __cppobj serialize<std::vector<std::unique_ptr<DataItem>> >
{
};

```

### `serialize<ActorUniqueID>`
```
struct __cppobj serialize<ActorUniqueID>
{
};

```

### `serialize<ActorRuntimeID>`
```
struct __cppobj serialize<ActorRuntimeID>
{
};

```

### `serialize<PositionTrackingId>`
```
struct __cppobj serialize<PositionTrackingId>
{
};

```

### `serialize<mce::UUID>`
```
struct __cppobj serialize<mce::UUID>
{
};

```

### `serialize<ActorLink>`
```
struct __cppobj serialize<ActorLink>
{
};

```

### `serialize<ChunkPos>`
```
struct __cppobj serialize<ChunkPos>
{
};

```

### `serialize<BaseGameVersion>`
```
struct __cppobj serialize<BaseGameVersion>
{
};

```

### `serialize<SubChunkPos>`
```
struct __cppobj serialize<SubChunkPos>
{
};

```

### `serialize<SpawnSettings>`
```
struct __cppobj serialize<SpawnSettings>
{
};

```

### `serialize<EducationLevelSettings>`
```
struct __cppobj serialize<EducationLevelSettings>
{
};

```

### `serialize<std::optional<EducationLevelSettings> >`
```
struct __cppobj serialize<std::optional<EducationLevelSettings> >
{
};

```

### `Social::Events::AchievementEventing`
```
struct __cppobj Social::Events::AchievementEventing
{
  std::vector<std::string> mExcludeCommonProperties;
};

```

### `Social::IUserManager`
```
struct __cppobj Social::IUserManager : Bedrock::EnableNonOwnerReferences
{
  Social::IUserManager_vtbl *__vftable /*VFT*/;
};

```

### `Social::IUserManager_vtbl`
```
struct /*VFT*/ Social::IUserManager_vtbl
{
  void (__fastcall *~IUserManager)(Social::IUserManager *this);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *createPrimaryUserAsync)(Social::IUserManager *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, IMinecraftEventing *, std::shared_ptr<Options>);
  void (__fastcall *initPrimaryIdentity)(Social::IUserManager *this, std::weak_ptr<FlightingService>);
  std::shared_ptr<Social::User> *(__fastcall *getPrimaryUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result);
  bool (__fastcall *isSecondaryUserCreationAllowed)(Social::IUserManager *this, int);
  void (__fastcall *setSecondaryUserCreationAllowed)(Social::IUserManager *this, int);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *addSecondaryUserAsync)(Social::IUserManager *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, int, IMinecraftEventing *, std::shared_ptr<Options>, std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>);
  bool (__fastcall *controllerChanged)(Social::IUserManager *this, int *, int *);
  bool (__fastcall *canChangePrimaryUserFromStartMenuScreen)(Social::IUserManager *this);
  void (__fastcall *getAsyncUserSelection)(Social::IUserManager *this, std::function<void __cdecl(int)>, int);
  void (__fastcall *getAsyncUserSelectionForNewPrimaryUser)(Social::IUserManager *this, int, bool);
  void (__fastcall *forceCloudSaveOnWorld)(Social::IUserManager *this, const std::string *);
  Core::Subject<Social::UserListObserver,Core::SingleThreadedLock> *(__fastcall *getUserListSubject)(Social::IUserManager *this);
  bool (__fastcall *isPrimaryUserReady)(Social::IUserManager *this);
  bool (__fastcall *canAccessPlayScreen)(Social::IUserManager *this);
  bool (__fastcall *needToShowPlatformStoreConnectConfirmationScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessSettingsScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessAchievementsScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessSkinScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessStoreScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessRealmsPendingInvitesScreen)(Social::IUserManager *this);
  bool (__fastcall *canHandleInvites)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionBeforeXBLSignIn)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionForMultiplayer)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionForSplitScreenMultiplayer)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionBeforeServerSearch)(Social::IUserManager *this);
  bool (__fastcall *needsAsyncUserSelection)(Social::IUserManager *this, int, bool);
  void (__fastcall *onFullGameUnlock)(Social::IUserManager *this);
  bool (__fastcall *hasPlatformIcons)(Social::IUserManager *this);
  bool (__fastcall *hasPlatformProfileCards)(Social::IUserManager *this);
  void (__fastcall *getLinkedXuids)(Social::IUserManager *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  void (__fastcall *getLinkedPlatformIds)(Social::IUserManager *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  void (__fastcall *onAppResumed)(Social::IUserManager *this);
  void (__fastcall *onAppSuspended)(Social::IUserManager *this);
  void (__fastcall *onAppFocusLost)(Social::IUserManager *this);
  void (__fastcall *removeUser)(Social::IUserManager *this, int, bool);
  void (__fastcall *removeClient)(Social::IUserManager *this, std::shared_ptr<IClientInstance>);
  void (__fastcall *removeUserClient)(Social::IUserManager *this, int);
  void (__fastcall *setUserClient)(Social::IUserManager *this, int, const std::shared_ptr<IClientInstance> *);
  bool (__fastcall *userHasClient)(Social::IUserManager *this, int);
  ControllerIDtoClientMap *(__fastcall *retrieveCIDToClientMap)(Social::IUserManager *this);
  int (__fastcall *getClientCID)(Social::IUserManager *this, const IClientInstance *);
  void (__fastcall *registerSignOutListener)(Social::IUserManager *this, const Core::CallbackListeners<int,enum Social::SignInResult>::Listener *);
  void (__fastcall *registerSignInListener)(Social::IUserManager *this, const Core::CallbackListeners<int,enum Social::SignInResult>::Listener *);
  void (__fastcall *registerIdentitySignInListener)(Social::IUserManager *this, Social::IdentityType, std::function<void __cdecl(unsigned int,enum Social::IdentityType)>);
  void (__fastcall *registerIdentitySignOutListener)(Social::IUserManager *this, Social::IdentityType, std::function<void __cdecl(unsigned int,enum Social::IdentityType)>);
  bool (__fastcall *needGamepadDisconnectScreen)(Social::IUserManager *this, int);
  void (__fastcall *tick)(Social::IUserManager *this, IMinecraftGame *);
  void (__fastcall *updateMapping)(Social::IUserManager *this, bool, bool);
  void (__fastcall *saveUserEventInformation)(Social::IUserManager *this);
  std::shared_ptr<Social::User> *(__fastcall *getUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, const Social::XboxLiveUser *);
  std::shared_ptr<Social::User> *(__fastcall *getUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, const IClientInstance *);
  const std::shared_ptr<Social::User const > *(__fastcall *getUserFromUserId)(Social::IUserManager *this, const std::shared_ptr<Social::User const > *result, unsigned int);
  std::shared_ptr<Social::User> *(__fastcall *getUserFromUserId)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, unsigned int);
  GameUserType (__fastcall *getUserTypeFromUserId)(Social::IUserManager *this, unsigned int);
  bool (__fastcall *isChatAllowedWhenBlockedByPlatform)(Social::IUserManager *this);
  const std::vector<std::shared_ptr<Social::User>> *(__fastcall *getUsers)(Social::IUserManager *this);
  bool (__fastcall *isUserSignedIn)(Social::IUserManager *this, unsigned int);
  void (__fastcall *registerLevelLocationObserver)(Social::IUserManager *this, LevelListCache *);
  Social::MultiplayerServiceObserver *(__fastcall *getMultiplayerServiceObserver)(Social::IUserManager *this);
};

```

### `serialize<InventorySource>`
```
struct __cppobj serialize<InventorySource>
{
};

```

### `serialize<InventoryAction>`
```
struct __cppobj serialize<InventoryAction>
{
};

```

### `serialize<DataItem>`
```
struct __cppobj serialize<DataItem>
{
};

```

### `serialize<std::unique_ptr<DataItem> >`
```
struct __cppobj serialize<std::unique_ptr<DataItem> >
{
};

```

### `serialize<ItemStack>`
```
struct __cppobj serialize<ItemStack>
{
};

```

### `ShakeBehavior`
```
struct __cppobj __declspec(align(8)) ShakeBehavior : CameraBehavior<ShakeBehavior>
{
  float mFrequency;
  float mAmplitude;
  float mNoiseMultiplier;
};

```

### `ShakeBehavior_vtbl`
```
struct /*VFT*/ ShakeBehavior_vtbl
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

### `ShakeBehaviorLoader`
```
struct __cppobj ShakeBehaviorLoader : CameraBehaviorLoader
{
};

```

### `ShakeBehaviorLoader_vtbl`
```
struct /*VFT*/ ShakeBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `ScopedCPUBoost`
```
struct __cppobj __declspec(align(8)) ScopedCPUBoost
{
  Bedrock::NonOwnerPointer<AppPlatform> mAppPlatform;
  bool mCPUBoostEnabled;
};

```

### `Social::DeviceId`
```
struct __cppobj Social::DeviceId : NewType<std::string >
{
};

```

### `Social::EmailAddress`
```
struct __cppobj Social::EmailAddress : NewType<std::string >
{
};

```

### `SoundLRUCache::CacheEntry`
```
struct __cppobj __declspec(align(8)) SoundLRUCache::CacheEntry
{
  std::string mSoundName;
  unsigned int mTouchMarker;
};

```

### `SoundLRUCache`
```
struct __cppobj SoundLRUCache
{
  unsigned __int64 mMemoryLimit;
  unsigned int mTouchMarker;
  std::list<SoundLRUCache::CacheEntry> mLRUEntryList;
  std::unordered_map<std::string,std::_List_iterator<std::_List_val<std::_List_simple_types<SoundLRUCache::CacheEntry> > >> mLRULookupMap;
  std::function<bool __cdecl(std::string const &)> mUnloader;
};

```

### `SceneStack::PushScreenEvent`
```
struct __cppobj SceneStack::PushScreenEvent : SceneStack::SceneStackEvent
{
  std::shared_ptr<AbstractScene> mScene;
};

```

### `SceneStack::PushScreenEvent_vtbl`
```
struct /*VFT*/ SceneStack::PushScreenEvent_vtbl
{
  void (__fastcall *~SceneStackEvent)(SceneStack::SceneStackEvent *this);
};

```

### `SceneStack::PopScreenEvent`
```
struct __cppobj __declspec(align(8)) SceneStack::PopScreenEvent : SceneStack::SceneStackEvent
{
  int mPopCount;
};

```

### `SceneStack::PopScreenEvent_vtbl`
```
struct /*VFT*/ SceneStack::PopScreenEvent_vtbl
{
  void (__fastcall *~SceneStackEvent)(SceneStack::SceneStackEvent *this);
};

```

### `SceneStack::PopRangeOfTypeScreenEvent`
```
struct __cppobj __declspec(align(8)) SceneStack::PopRangeOfTypeScreenEvent : SceneStack::SceneStackEvent
{
  _BYTE mSceneType[4];
  _BYTE mSceneTypeExclusions[4];
  int mPopCount;
};

```

### `SceneStack::PopRangeOfTypeScreenEvent_vtbl`
```
struct /*VFT*/ SceneStack::PopRangeOfTypeScreenEvent_vtbl
{
  void (__fastcall *~SceneStackEvent)(SceneStack::SceneStackEvent *this);
};

```

### `SceneStack::FlushScreenEvent`
```
struct __cppobj __declspec(align(8)) SceneStack::FlushScreenEvent : SceneStack::SceneStackEvent
{
  bool mIgnoreNotFlushableFlag;
  bool mIgnoreTransitions;
};

```

### `SceneStack::FlushScreenEvent_vtbl`
```
struct /*VFT*/ SceneStack::FlushScreenEvent_vtbl
{
  void (__fastcall *~SceneStackEvent)(SceneStack::SceneStackEvent *this);
};

```

### `StoreHomeRowsTreatmentQuery`
```
struct __cppobj __declspec(align(8)) StoreHomeRowsTreatmentQuery : TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>
{
  std::function<void __cdecl(std::vector<std::shared_ptr<StoreVisualStyle>> &)> mCallback;
  std::unordered_map<std::string,std::shared_ptr<StoreVisualStyle>> mContentQueryList;
  std::shared_ptr<StoreVisualStyle> mPromoStyle;
  bool mLocalizationReady;
};

```

### `StoreHomeRowsTreatmentQuery_vtbl`
```
struct /*VFT*/ StoreHomeRowsTreatmentQuery_vtbl
{
  void (__fastcall *~TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this, const QueryManifestSearchResults *, const std::vector<std::string> *);
};

```

### `SalesCustom`
```
struct __cppobj SalesCustom
{
  float mPercentageDiscounted;
  std::string mStartDate;
  std::string mEndDate;
  std::vector<std::string> mOfferIds;
  std::unordered_map<std::string,int> mOffers;
};

```

### `SalesDocument`
```
struct __cppobj SalesDocument
{
  CommonDocument mCommon;
  SalesCustom mCustom;
};

```

### `SalesSearchResults`
```
const struct __cppobj SalesSearchResults : CommonSearchResults
{
  std::vector<SalesDocument> mDocuments;
};

```

### `SalesDocData`
```
struct __cppobj SalesDocData
{
  const SalesDocument *mSalesDoc;
  __int64 mStartTimeUTC;
  __int64 mEndTimeUTC;
};

```

### `StoreSalesTreatmentQuery`
```
struct __cppobj __declspec(align(8)) StoreSalesTreatmentQuery : TreatmentQuery<SalesSearchResults,SalesDocument>
{
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  std::shared_ptr<bool> mExistenceTracker;
  const std::string mStoreId;
  std::function<void __cdecl(std::vector<SalesDocData> const &,__int64,__int64)> mCallback;
  bool mIsFetching;
};

```

### `StoreSalesTreatmentQuery_vtbl`
```
struct /*VFT*/ StoreSalesTreatmentQuery_vtbl
{
  void (__fastcall *~TreatmentQuery<SalesSearchResults,SalesDocument>)(TreatmentQuery<SalesSearchResults,SalesDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<SalesSearchResults,SalesDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<SalesSearchResults,SalesDocument> *this, const SalesSearchResults *, const std::vector<std::string> *);
};

```

### `SkinPickerUpsellTreatmentQuery`
```
struct __cppobj SkinPickerUpsellTreatmentQuery : TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>
{
  std::function<void __cdecl(SearchQuery const *)> mCallback;
};

```

### `SkinPickerUpsellTreatmentQuery_vtbl`
```
struct /*VFT*/ SkinPickerUpsellTreatmentQuery_vtbl
{
  void (__fastcall *~TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this, const QueryManifestSearchResults *, const std::vector<std::string> *);
};

```

### `SkinPackSection`
```
struct __cppobj SkinPackSection : PDPSection
{
  const StoreCatalogItem *mItem;
};

```

### `SkinPackSection_vtbl`
```
struct /*VFT*/ SkinPackSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `ScreenshotSection`
```
struct __cppobj __declspec(align(8)) ScreenshotSection : PDPSection
{
  ScreenshotSectionType mType;
};

```

### `ScreenshotSection_vtbl`
```
struct /*VFT*/ ScreenshotSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `StoreOfferSearchResults`
```
const struct __cppobj StoreOfferSearchResults : CommonSearchResults
{
  std::vector<DurableDocument> mDurableDocuments;
  std::vector<OfferCollectionDocument> mOfferCollectionDocuments;
};

```

### `StoreNewOffersQuery`
```
struct __cppobj StoreNewOffersQuery : NewOffersQuery
{
};

```

### `Social::UserCreationData`
```
struct __cppobj __declspec(align(8)) Social::UserCreationData
{
  _BYTE mUserType[4];
  int mControllerId;
  IMinecraftEventing *mMinecraftEventing;
  std::shared_ptr<Options> mOptions;
  unsigned int mId;
};

```

### `ScreenSettings`
```
struct __cppobj __declspec(align(8)) ScreenSettings : UIComponent, IScreenSettings
{
  __int8 mNotFlushable : 1;
  __int8 mAlwaysAcceptsInput : 1;
  __int8 mRenderGameBehind : 1;
  __int8 mAbsorbsInput : 1;
  __int8 mIsShowingMenu : 1;
  __int8 mIsModal : 1;
  __int8 mShouldStealMouse : 1;
  __int8 mDrawsLast : 1;
  __int8 mIsVRMode : 1;
  __int8 mForceRenderBelow : 1;
  __int8 mSendEvents : 1;
  __int8 mLowFreqRendering : 1;
  __int8 mCloseOnPlayerHurt : 1;
  __int8 mCacheScreen : 1;
  __int8 mGamepadCursor : 1;
  __int8 mGamepadCursorDeflectionMode : 1;
  __int8 mLoadImmediately : 1;
  __int8 mRenderOnlyWhenTopmost : 1;
  float mVerticalScrollDelta;
  _BYTE mSceneType[4];
};

```

### `ScreenSettings_vtbl`
```
struct /*VFT*/ ScreenSettings_vtbl
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

### `Social::<lambda_70e164e4d03fc91491731259b37366c5>`
```
struct __cppobj Social::<lambda_70e164e4d03fc91491731259b37366c5>
{
};

```

### `Social::<lambda_489514820f4eef331228db74af9bf498>`
```
struct __cppobj Social::<lambda_489514820f4eef331228db74af9bf498>
{
};

```

### `Social::UserManager`
```
struct __cppobj Social::UserManager : Social::IUserManager, LevelLocationObserver, Social::MultiplayerServiceObserver
{
  std::vector<std::shared_ptr<Social::User>> mUsers;
  Core::CallbackListeners<int,enum Social::SignInResult> mSignOutListeners;
  Core::CallbackListeners<int,enum Social::SignInResult> mSignInListeners;
  int mCurrentPrimaryUserControllerId;
  ControllerIDtoClientMap mCidToClientMap;
  int mAutoLoginTime;
  bool mClearedUserCredentials;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  std::mutex mIdentityListenerLock;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mIdentitySignInListeners;
  std::unordered_map<enum Social::IdentityType,std::vector<std::function<void __cdecl(unsigned int,enum Social::IdentityType)>>> mIdentitySignOutListeners;
  unsigned int mNextId;
  Core::Subject<Social::UserListObserver,Core::SingleThreadedLock> mUserListSubject;
  std::shared_ptr<Social::TitleIdentityInfo> mTitleIdentityInfo;
  std::recursive_mutex mUserArrayLock;
  std::unique_ptr<TaskGroup> mTaskGroup;
  ServiceRegistrationToken<Social::UserManager> mServiceRegistrationToken;
};

```

### `Social::TitleIdentityInfo`
```
struct __cppobj Social::TitleIdentityInfo
{
  Social::TitleIdentityInfo_vtbl *__vftable /*VFT*/;
  Social::PlayFabEnvironment mEnvironment;
  int mTreatmentMonitorHandle;
  std::weak_ptr<FlightingService> mFlightingService;
  std::weak_ptr<Options> mPrimaryUserOptions;
};

```

### `Social::TitleIdentityInfo_vtbl`
```
struct /*VFT*/ Social::TitleIdentityInfo_vtbl
{
  void (__fastcall *~TitleIdentityInfo)(Social::TitleIdentityInfo *this);
  void (__fastcall *setEnvironment)(Social::TitleIdentityInfo *this, Social::PlayFabEnvironment);
  bool (__fastcall *isPlayFabCommerceEnabled)(Social::TitleIdentityInfo *this);
  VirtualCurrencyType (__fastcall *getPrimaryCurrencyType)(Social::TitleIdentityInfo *this);
  const gsl::basic_string_span<char const ,-1> *(__fastcall *getPlayFabTitleId)(Social::TitleIdentityInfo *this, const gsl::basic_string_span<char const ,-1> *result);
  const std::string *(__fastcall *getPlayfabSharedSecret)(Social::TitleIdentityInfo *this);
  bool (__fastcall *isSignInToPlayFabWithAnonymousAuthEnabled)(Social::TitleIdentityInfo *this);
  bool (__fastcall *getIsAccountRelinkingRestricted)(Social::TitleIdentityInfo *this);
  bool (__fastcall *isXboxLiveTitleIdAnyPlatform)(Social::TitleIdentityInfo *this, unsigned int);
  unsigned int (__fastcall *getXboxLiveFlags)(Social::TitleIdentityInfo *this);
  const std::string *(__fastcall *getXboxLiveClientId)(Social::TitleIdentityInfo *this);
  int (__fastcall *getXboxLiveTitleId)(Social::TitleIdentityInfo *this);
  const std::string *(__fastcall *getXboxLiveRedirectUri)(Social::TitleIdentityInfo *this);
  const std::string *(__fastcall *getXboxLiveScid)(Social::TitleIdentityInfo *this);
  const std::string *(__fastcall *getXboxLiveTelemetryAppId)(Social::TitleIdentityInfo *this);
};

```

### `Social::UserManager_vtbl`
```
struct /*VFT*/ Social::UserManager_vtbl
{
  void (__fastcall *~IUserManager)(Social::IUserManager *this);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *createPrimaryUserAsync)(Social::IUserManager *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, IMinecraftEventing *, std::shared_ptr<Options>);
  void (__fastcall *initPrimaryIdentity)(Social::IUserManager *this, std::weak_ptr<FlightingService>);
  std::shared_ptr<Social::User> *(__fastcall *getPrimaryUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result);
  bool (__fastcall *isSecondaryUserCreationAllowed)(Social::IUserManager *this, int);
  void (__fastcall *setSecondaryUserCreationAllowed)(Social::IUserManager *this, int);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *addSecondaryUserAsync)(Social::IUserManager *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, int, IMinecraftEventing *, std::shared_ptr<Options>, std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>);
  bool (__fastcall *controllerChanged)(Social::IUserManager *this, int *, int *);
  bool (__fastcall *canChangePrimaryUserFromStartMenuScreen)(Social::IUserManager *this);
  void (__fastcall *getAsyncUserSelection)(Social::IUserManager *this, std::function<void __cdecl(int)>, int);
  void (__fastcall *getAsyncUserSelectionForNewPrimaryUser)(Social::IUserManager *this, int, bool);
  void (__fastcall *forceCloudSaveOnWorld)(Social::IUserManager *this, const std::string *);
  Core::Subject<Social::UserListObserver,Core::SingleThreadedLock> *(__fastcall *getUserListSubject)(Social::IUserManager *this);
  bool (__fastcall *isPrimaryUserReady)(Social::IUserManager *this);
  bool (__fastcall *canAccessPlayScreen)(Social::IUserManager *this);
  bool (__fastcall *needToShowPlatformStoreConnectConfirmationScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessSettingsScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessAchievementsScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessSkinScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessStoreScreen)(Social::IUserManager *this);
  bool (__fastcall *canAccessRealmsPendingInvitesScreen)(Social::IUserManager *this);
  bool (__fastcall *canHandleInvites)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionBeforeXBLSignIn)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionForMultiplayer)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionForSplitScreenMultiplayer)(Social::IUserManager *this);
  bool (__fastcall *needPlatformConnectionBeforeServerSearch)(Social::IUserManager *this);
  bool (__fastcall *needsAsyncUserSelection)(Social::IUserManager *this, int, bool);
  void (__fastcall *onFullGameUnlock)(Social::IUserManager *this);
  bool (__fastcall *hasPlatformIcons)(Social::IUserManager *this);
  bool (__fastcall *hasPlatformProfileCards)(Social::IUserManager *this);
  void (__fastcall *getLinkedXuids)(Social::IUserManager *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  void (__fastcall *getLinkedPlatformIds)(Social::IUserManager *this, std::function<void __cdecl(std::string,std::string)>, const std::vector<std::string> *);
  void (__fastcall *onAppResumed)(Social::IUserManager *this);
  void (__fastcall *onAppSuspended)(Social::IUserManager *this);
  void (__fastcall *onAppFocusLost)(Social::IUserManager *this);
  void (__fastcall *removeUser)(Social::IUserManager *this, int, bool);
  void (__fastcall *removeClient)(Social::IUserManager *this, std::shared_ptr<IClientInstance>);
  void (__fastcall *removeUserClient)(Social::IUserManager *this, int);
  void (__fastcall *setUserClient)(Social::IUserManager *this, int, const std::shared_ptr<IClientInstance> *);
  bool (__fastcall *userHasClient)(Social::IUserManager *this, int);
  ControllerIDtoClientMap *(__fastcall *retrieveCIDToClientMap)(Social::IUserManager *this);
  int (__fastcall *getClientCID)(Social::IUserManager *this, const IClientInstance *);
  void (__fastcall *registerSignOutListener)(Social::IUserManager *this, const Core::CallbackListeners<int,enum Social::SignInResult>::Listener *);
  void (__fastcall *registerSignInListener)(Social::IUserManager *this, const Core::CallbackListeners<int,enum Social::SignInResult>::Listener *);
  void (__fastcall *registerIdentitySignInListener)(Social::IUserManager *this, Social::IdentityType, std::function<void __cdecl(unsigned int,enum Social::IdentityType)>);
  void (__fastcall *registerIdentitySignOutListener)(Social::IUserManager *this, Social::IdentityType, std::function<void __cdecl(unsigned int,enum Social::IdentityType)>);
  bool (__fastcall *needGamepadDisconnectScreen)(Social::IUserManager *this, int);
  void (__fastcall *tick)(Social::IUserManager *this, IMinecraftGame *);
  void (__fastcall *updateMapping)(Social::IUserManager *this, bool, bool);
  void (__fastcall *saveUserEventInformation)(Social::IUserManager *this);
  std::shared_ptr<Social::User> *(__fastcall *getUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, const Social::XboxLiveUser *);
  std::shared_ptr<Social::User> *(__fastcall *getUser)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, const IClientInstance *);
  const std::shared_ptr<Social::User const > *(__fastcall *getUserFromUserId)(Social::IUserManager *this, const std::shared_ptr<Social::User const > *result, unsigned int);
  std::shared_ptr<Social::User> *(__fastcall *getUserFromUserId)(Social::IUserManager *this, std::shared_ptr<Social::User> *result, unsigned int);
  GameUserType (__fastcall *getUserTypeFromUserId)(Social::IUserManager *this, unsigned int);
  bool (__fastcall *isChatAllowedWhenBlockedByPlatform)(Social::IUserManager *this);
  const std::vector<std::shared_ptr<Social::User>> *(__fastcall *getUsers)(Social::IUserManager *this);
  bool (__fastcall *isUserSignedIn)(Social::IUserManager *this, unsigned int);
  void (__fastcall *registerLevelLocationObserver)(Social::IUserManager *this, LevelListCache *);
  Social::MultiplayerServiceObserver *(__fastcall *getMultiplayerServiceObserver)(Social::IUserManager *this);
  bool (__fastcall *hasPlatformPremiumAccess)(Social::UserManager *this);
  void (__fastcall *_forceCloudSaveOnWorld)(Social::UserManager *this, const std::string *);
  void (__fastcall *_onAppResumed)(Social::UserManager *this);
  void (__fastcall *_onAppSuspended)(Social::UserManager *this);
  std::shared_ptr<Social::UserCreationData> *(__fastcall *_prepareUserCreationData)(Social::UserManager *this, std::shared_ptr<Social::UserCreationData> *result, GameUserType, int, IMinecraftEventing *, std::shared_ptr<Options>, unsigned int);
  void (__fastcall *_onUserAdded)(Social::UserManager *this, const std::shared_ptr<Social::User> *);
};

```

### `StoreBaseScreenController`
```
struct __cppobj StoreBaseScreenController : MainMenuScreenController
{
  std::string mTitle;
  std::unique_ptr<DlcUIWrapper> mDlcUIWrapper;
  std::vector<std::shared_ptr<StoreVisualStyle>> mLayoutList;
  StoreUIStyleContainer mSections;
  bool mCoinPurchaseInProgress;
  bool mWasDownloadActive;
  bool mDirty;
  Social::UserPicturePath mGamerProfilePicPath;
};

```

### `StoreUIStyleContainer`
```
struct __cppobj StoreUIStyleContainer
{
  std::vector<std::shared_ptr<StoreVisualStyle>> mStyles;
};

```

### `StoreBaseScreenController_vtbl`
```
struct /*VFT*/ StoreBaseScreenController_vtbl
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
};

```

### `StoreBaseScreenController::StoreRow`
```
struct __cppobj StoreBaseScreenController::StoreRow
{
  std::string mRowName;
  std::string mTelemetryId;
  std::shared_ptr<CatalogCollection> mCollection;
  StoreSearchQuery mRowQuery;
};

```

### `serialize<JigsawEditorData>`
```
struct __cppobj serialize<JigsawEditorData>
{
};

```

### `serialize<StructureSettings>`
```
struct __cppobj serialize<StructureSettings>
{
};

```

### `serialize<StructureEditorData>`
```
struct __cppobj serialize<StructureEditorData>
{
};

```

### `SyncedPhotoView`
```
struct __cppobj SyncedPhotoView
{
  std::unordered_map<std::string,enum SyncedPhotoView::PhotoStatus> mPhotoStatus;
  PhotoStorage *mStorage;
  std::string mBookId;
  PacketSender *mPacketSender;
};

```

### `StructureTelemetryServerData`
```
struct __cppobj StructureTelemetryServerData
{
  bool mHasBeenActivatedByRedstone;
  bool mHasLoadedIntoUnloadedChunks;
  BlockPos mLastOffsetWhenLoadingIntoUnloadedChunks;
};

```

### `StructureBlockActor`
```
struct __cppobj __declspec(align(8)) StructureBlockActor : BlockActor
{
  StructureEditorData mStructureEditorData;
  StructureTelemetryServerData mTelemetryServerData;
  bool mIsPowered;
};

```

### `StructureBlockActor_vtbl`
```
struct /*VFT*/ StructureBlockActor_vtbl
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

### `SoundUtils::EventSound`
```
const struct __cppobj SoundUtils::EventSound
{
  std::string eventName;
  std::string soundName;
  float pitch;
  float volume;
};

```

### `StoreCatalogRepository::StoreQueryCallback`
```
struct __cppobj StoreCatalogRepository::StoreQueryCallback
{
  std::function<void __cdecl(std::vector<StoreCatalogItem *>,int,int,int)> mOnItemsRetrieved;
  std::function<void __cdecl(StoreCatalogItem const *)> mOnImageFetched;
};

```

### `StoreGiftPromotionScreenController::PersonaImportTracker`
```
struct __cppobj StoreGiftPromotionScreenController::PersonaImportTracker
{
  std::unique_ptr<DlcBatchModel> mDlcBatchModel;
  mce::UUID mPackId;
  std::function<void __cdecl(void)> mOnImportCompleteCallback;
};

```

### `StoreGiftPromotionScreenController`
```
struct __cppobj __declspec(align(8)) StoreGiftPromotionScreenController : PurchaseEnabledScreenController
{
  std::shared_ptr<PersonaScreenModel> mPersonaScreenModel;
  std::shared_ptr<DlcBatchCacheModel> mDlcBatchCacheModel;
  std::shared_ptr<GiftPromotionQuery> mGiftPromotionQuery;
  std::vector<std::shared_ptr<PromotionItem>> mItemsList;
  std::set<mce::UUID> mImportedPacks;
  std::vector<std::shared_ptr<StoreGiftPromotionScreenController::PersonaImportTracker>> mTrackedImports;
  std::shared_ptr<StoreGiftPromotionScreenController::PersonaImportTracker> mCurrentImportTracker;
  std::function<void __cdecl(void)> mOnCharacterUpdated;
  std::shared_ptr<PromotionItem> mCurrentPromoItem;
  unsigned int mCurrentItemIndex;
  unsigned int mCarouselPageOffset;
  int mCurrentScreenshotIndex;
  _BYTE mDirtyFlag[4];
  bool mHasRecievedCatalogContent;
  bool mIsUpdatingPersona;
  bool mNeedToRevertPersona;
};

```

### `StoreGiftPromotionScreenController_vtbl`
```
struct /*VFT*/ StoreGiftPromotionScreenController_vtbl
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

### `SunsettingScreenController`
```
struct __cppobj SunsettingScreenController : MainMenuScreenController
{
  std::string mTitleText;
  bool mDirty;
  Bedrock::PubSub::ScopedSubscription mSunsetOptionSubscription;
};

```

### `SunsettingScreenController_vtbl`
```
struct /*VFT*/ SunsettingScreenController_vtbl
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

### `SunsettingScreenController::_registerEventHandlers::__l2::<lambda_807310196f6c0920e12b4c0463f922e7>`
```
struct __cppobj SunsettingScreenController::_registerEventHandlers::__l2::<lambda_807310196f6c0920e12b4c0463f922e7>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::_registerEventHandlers::__l2::<lambda_c099f805792d83fcf651eb1d18e9ad85>`
```
struct __cppobj SunsettingScreenController::_registerEventHandlers::__l2::<lambda_c099f805792d83fcf651eb1d18e9ad85>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::_registerBindings::__l2::<lambda_854513f2c137812c296c23656504166e>`
```
struct __cppobj SunsettingScreenController::_registerBindings::__l2::<lambda_854513f2c137812c296c23656504166e>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::_registerBindings::__l2::<lambda_a7bf1e2cd0fa4bc2c22e86aee7204fca>`
```
struct __cppobj SunsettingScreenController::_registerBindings::__l2::<lambda_a7bf1e2cd0fa4bc2c22e86aee7204fca>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::_registerBindings::__l2::<lambda_4e984e9f76b3e0c38c1a70d5a3423e36>`
```
struct __cppobj SunsettingScreenController::_registerBindings::__l2::<lambda_4e984e9f76b3e0c38c1a70d5a3423e36>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::_registerBindings::__l2::<lambda_7df8f25723093e9e016fef7a49761d9d>`
```
struct __cppobj SunsettingScreenController::_registerBindings::__l2::<lambda_7df8f25723093e9e016fef7a49761d9d>
{
};

```

### `SunsettingScreenController::_registerBindings::__l2::<lambda_a909d5c6ce90698639eda46ea5d3ecfa>`
```
struct __cppobj SunsettingScreenController::_registerBindings::__l2::<lambda_a909d5c6ce90698639eda46ea5d3ecfa>
{
  SunsettingScreenController *const __this;
};

```

### `SunsettingScreenController::onCreation::__l2::<lambda_4f419ba9854ba4eca64d973bbc79fe9a>`
```
struct __cppobj SunsettingScreenController::onCreation::__l2::<lambda_4f419ba9854ba4eca64d973bbc79fe9a>
{
  std::weak_ptr<SunsettingScreenController> weakThis;
};

```

### `Social::<lambda_090c7f881592f8538412bd6421d0c576>`
```
struct __cppobj Social::<lambda_090c7f881592f8538412bd6421d0c576>
{
};

```

### `Social::<lambda_e5e1c1da8e49460c5125e0ca36e062c4>`
```
struct __cppobj Social::<lambda_e5e1c1da8e49460c5125e0ca36e062c4>
{
};

```

### `StoreProgressHandler`
```
struct __cppobj __declspec(align(8)) StoreProgressHandler : ProgressHandler
{
  std::function<void __cdecl(bool &)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  std::string mTitleText;
  bool mDone;
};

```

### `StoreProgressHandler_vtbl`
```
struct /*VFT*/ StoreProgressHandler_vtbl
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

### `ServiceLocator<IMinecraftEventing>`
```
struct __cppobj ServiceLocator<IMinecraftEventing>
{
};

```

### `Social::XboxLiveServices`
```
struct __cppobj Social::XboxLiveServices
{
};

```

### `Social::XboxLiveSignInHandler`
```
struct __cppobj Social::XboxLiveSignInHandler : std::enable_shared_from_this<Social::XboxLiveSignInHandler>
{
  Social::XboxLiveSignInHandler_vtbl *__vftable /*VFT*/;
  std::atomic<bool> mAttemptingSignIn;
  XalPlatformOperationToken *mRemoteConnectOperation;
};

```

### `Social::XboxLiveSignInHandler_vtbl`
```
struct /*VFT*/ Social::XboxLiveSignInHandler_vtbl
{
  void (__fastcall *~XboxLiveSignInHandler)(Social::XboxLiveSignInHandler *this);
  void (__fastcall *interactiveSignIn)(Social::XboxLiveSignInHandler *this, std::weak_ptr<Social::XboxLiveUser>, std::function<void __cdecl(enum Social::SignInResult,std::string const &,bool)>, std::function<void __cdecl(std::string,std::string)>);
  void (__fastcall *silentSignIn)(Social::XboxLiveSignInHandler *this, std::weak_ptr<Social::XboxLiveUser>, std::function<void __cdecl(enum Social::SignInResult,std::string const &,bool)>);
};

```

### `serialize<SyncedPlayerMovementSettings>`
```
struct __cppobj serialize<SyncedPlayerMovementSettings>
{
};

```

### `SyncChunkPosPacket`
```
struct __cppobj __declspec(align(8)) SyncChunkPosPacket
{
  ChunkPos chunkPos;
  AutomaticID<Dimension,int> dimensionType;
};

```

### `serialize<MoveActorAbsoluteData>`
```
struct __cppobj serialize<MoveActorAbsoluteData>
{
};

```

### `SendEventGoal`
```
struct __cppobj SendEventGoal : Goal
{
  Mob *mCaster;
  TempEPtr<Actor> mTarget;
  std::vector<SendEventData> mSpells;
  int mCurrentTick;
  int mCastTicksRemaining;
  int mCurrentSpellIndex;
  int mCurrentSpellStage;
  unsigned __int64 mCooldownStopTick;
};

```

### `SendEventGoal_vtbl`
```
struct /*VFT*/ SendEventGoal_vtbl
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

### `SummonActorGoal`
```
struct __cppobj SummonActorGoal : Goal
{
  Mob *mCaster;
  std::vector<SummonSpellData> mSpells;
  int mCurrentTick;
  int mCastTicksRemaining;
  int mCurrentSpellIndex;
  int mCurrentSpellStage;
  int mCurrentSummonCount;
  unsigned __int64 mCooldownStopTick;
  Vec3 mTargetPos;
  Vec3 mCasterPos;
};

```

### `SummonActorGoal_vtbl`
```
struct /*VFT*/ SummonActorGoal_vtbl
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

### `SharedAttributes`
```
struct __cppobj SharedAttributes
{
};

```

### `Social::<lambda_a803a48e30207c340f5fec77f07e2189>`
```
struct __cppobj Social::<lambda_a803a48e30207c340f5fec77f07e2189>
{
};

```

### `Social::<lambda_443f693452a8e8e74994b9939143d69f>`
```
struct __cppobj Social::<lambda_443f693452a8e8e74994b9939143d69f>
{
};

```

### `static_vector<Pos,27>`
```
struct __cppobj static_vector<Pos,27>
{
  std::_Align_type<int,12> mArray[27];
  unsigned __int64 mSize;
};

```

### `ServiceLocator<FeatureToggles>`
```
struct __cppobj ServiceLocator<FeatureToggles>
{
};

```

### `Social::PlayFabApi`
```
struct __cppobj Social::PlayFabApi
{
};

```

### `SoulsandValleyMoodSoundPlayer`
```
struct __cppobj SoulsandValleyMoodSoundPlayer
{
};

```

### `SoundOptions`
```
struct __cppobj SoundOptions
{
  std::unordered_map<std::string,SoundOptions::VolumeSlider> mVolumeSliders;
  Bedrock::NonOwnerPointer<SoundPlayerInterface> mSoundEngine;
};

```

### `SPIEntitlementManager`
```
struct __cppobj __declspec(align(8)) SPIEntitlementManager : IEntitlementManager, ServiceClient, std::enable_shared_from_this<SPIEntitlementManager>
{
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  bool mInitialized;
  IMinecraftEventing *mEventing;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  std::shared_ptr<CommerceIdentity> mCommerceIdentity;
  std::atomic<unsigned int> mCoinBalance;
  std::atomic<unsigned int> mNumberOfActiveCoinPurchaseProcesses;
  std::unordered_map<ContentIdentity,Entitlement> mInventory;
  std::mutex mInventoryChangeMutex;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mEntitlementChangeListeners;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mEntitlementChangeListenersToAdd;
  std::mutex mEntitlementChangeListenerToAddMutex;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mInventoryEntitlementListeners;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mInventoryEntitlementListenersToAdd;
  std::mutex mInventoryEntitlementListenerToAddMutex;
  std::atomic<bool> mInventoryRefreshStarted;
  std::atomic<bool> mInventoryRefreshed;
  std::atomic<bool> mRetainCacheMode;
  bool mHaveCachedLegacyOfferInfo;
  std::string mPlatformStoreName;
  std::vector<PurchaseInfo> mLegacyDurables;
  std::string mReceipt;
  std::string mImposterXUID;
  bool mEntitlementManagerNeedsToBeRebooted;
};

```

### `SPIEntitlementManager_vtbl`
```
struct /*VFT*/ SPIEntitlementManager_vtbl
{
  void (__fastcall *~IEntitlementManager)(IEntitlementManager *this);
  void (__fastcall *tick)(IEntitlementManager *this);
  void (__fastcall *refreshBalance)(IEntitlementManager *this);
  void (__fastcall *refreshInventory)(IEntitlementManager *this);
  std::string *(__fastcall *getInventoryId)(IEntitlementManager *this, std::string *result);
  std::string *(__fastcall *getWalletId)(IEntitlementManager *this, std::string *result);
  std::string *(__fastcall *getCommerceUserID)(IEntitlementManager *this, std::string *result);
  void (__fastcall *processLegacyOfferOwnership)(IEntitlementManager *this, const std::string *, bool, const std::vector<PurchaseInfo> *, const std::string *);
  void (__fastcall *purchaseCoinOffer)(IEntitlementManager *this, const std::string *, const PurchaseInfo *, const std::string *, std::function<void __cdecl(bool)>);
  const std::string *(__fastcall *getTenant)(IEntitlementManager *this);
  void (__fastcall *processExternalStorePurchases)(IEntitlementManager *this, StorePlatform, const std::string *);
  void (__fastcall *processRealmsCoinOfferPurchase)(IEntitlementManager *this, const std::string *, const std::string *, const std::string *, bool, const std::string *, std::function<void __cdecl(enum SendReceiptRealmsResult,Realms::World)>);
  int (__fastcall *getBalance)(IEntitlementManager *this);
  bool (__fastcall *supportsDeviceAccounts)(IEntitlementManager *this);
  bool (__fastcall *hasAnActiveDeviceAccount)(IEntitlementManager *this);
  bool (__fastcall *hasDeviceAccountBeenUsed)(IEntitlementManager *this);
  void (__fastcall *refreshEntitlements)(IEntitlementManager *this);
  void (__fastcall *setRetainedCacheMode)(IEntitlementManager *this, bool);
  StorePlatform (__fastcall *getCommerceStoreNameFromPlatformStoreName)(IEntitlementManager *this, const std::string *);
  Entitlement *(__fastcall *getEntitlement)(IEntitlementManager *this, const ContentIdentity *);
  std::vector<mce::UUID> *(__fastcall *getOwnedEntitlementIds)(IEntitlementManager *this, std::vector<mce::UUID> *result);
  void (__fastcall *getEntitlementsByCreator)(IEntitlementManager *this, const std::string *, std::vector<Entitlement> *);
  void (__fastcall *purchaseCatalogOffer)(IEntitlementManager *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::StoreType, const std::string *, const std::string *, std::function<void __cdecl(enum TransactionStatus)>);
  bool (__fastcall *iapSyncAvailable)(IEntitlementManager *this);
  void (__fastcall *syncIAPs)(IEntitlementManager *this, std::function<void __cdecl(bool)>);
  void (__fastcall *transferDeviceAccountToXboxLive)(IEntitlementManager *this, std::function<void __cdecl(bool)>);
  void (__fastcall *setDeviceEntitlements)(IEntitlementManager *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *addEntitlementChangeListener)(IEntitlementManager *this, std::weak_ptr<EntitlementChangeListener>);
  void (__fastcall *addEntitlementInventoryRefreshListener)(IEntitlementManager *this, std::weak_ptr<EntitlementChangeListener>);
  int (__fastcall *getTransferStatusCode)(IEntitlementManager *this);
  const std::string *(__fastcall *getTransferErrorCorrelationId)(IEntitlementManager *this, const std::string *result);
  bool (__fastcall *hasAccountTransferError)(IEntitlementManager *this);
  bool (__fastcall *hasUnresolvedAccountTransfer)(IEntitlementManager *this);
  bool (__fastcall *hasShownAccountTransferErrorDialog)(IEntitlementManager *this);
  void (__fastcall *setAccountTransferErrorDialogAsShown)(IEntitlementManager *this);
  bool (__fastcall *findLegacyUID)(IEntitlementManager *this, const std::string *, std::vector<std::string> *);
  bool (__fastcall *isProcessingStoreCoinPurchase)(IEntitlementManager *this);
};

```

### `Social::<lambda_44bf41d6c9ba9067506f842c2e0a499c>`
```
struct __cppobj Social::<lambda_44bf41d6c9ba9067506f842c2e0a499c>
{
};

```

### `Social::<lambda_6c873b302b7bcb7495bf50180e322504>`
```
struct __cppobj Social::<lambda_6c873b302b7bcb7495bf50180e322504>
{
};

```

### `ServiceLocator<OfferRepository>`
```
struct __cppobj ServiceLocator<OfferRepository>
{
};

```

### `Social::<lambda_39274a8fc71db3380c3a9fc4843b4d4e>`
```
struct __cppobj Social::<lambda_39274a8fc71db3380c3a9fc4843b4d4e>
{
};

```

### `Social::<lambda_fd5784e2faa2ea9d78446f613f7052b5>`
```
struct __cppobj Social::<lambda_fd5784e2faa2ea9d78446f613f7052b5>
{
};

```

### `Social::<lambda_a457e57f728e2ec329a262fb7b132d64>`
```
struct __cppobj Social::<lambda_a457e57f728e2ec329a262fb7b132d64>
{
};

```

### `Social::<lambda_9c90971a3871e9509edf0acb985f462c>`
```
struct __cppobj Social::<lambda_9c90971a3871e9509edf0acb985f462c>
{
};

```

### `StackedGraphBars::ColorKey`
```
struct __cppobj StackedGraphBars::ColorKey
{
  char colorTag;
  std::string name;
};

```

### `StackedGraphBars`
```
struct __cppobj __declspec(align(8)) StackedGraphBars
{
  std::vector<std::array<float,2>> mData;
  std::vector<StackedGraphBars::ColorKey> mColors;
  float mHeight;
  std::string mGraphName;
  int mMaxBars;
};

```

### `SHELLHOOKINFO`
```
struct SHELLHOOKINFO
{
  HWND__ *hwnd;
  tagRECT rc;
};

```

### `sockaddr_in6_old`
```
struct sockaddr_in6_old
{
  __int16 sin6_family;
  unsigned __int16 sin6_port;
  unsigned int sin6_flowinfo;
  in6_addr sin6_addr;
};

```

### `SC_HANDLE__`
```
struct SC_HANDLE__
{
  int unused;
};

```

### `SYSTEM_POWER_LEVEL`
```
struct SYSTEM_POWER_LEVEL
{
  unsigned __int8 Enable;
  unsigned __int8 Spare[3];
  unsigned int BatteryLevel;
  POWER_ACTION_POLICY PowerPolicy;
  _SYSTEM_POWER_STATE MinSystemState;
};

```

### `sockaddr_in6_w2ksp1`
```
struct sockaddr_in6_w2ksp1
{
  __int16 sin6_family;
  unsigned __int16 sin6_port;
  unsigned int sin6_flowinfo;
  in6_addr sin6_addr;
  unsigned int sin6_scope_id;
};

```

### `sockaddr_storage_xp`
```
struct sockaddr_storage_xp
{
  __int16 ss_family;
  char __ss_pad1[6];
  __int64 __ss_align;
  char __ss_pad2[112];
};

```

### `sockproto`
```
struct sockproto
{
  unsigned __int16 sp_family;
  unsigned __int16 sp_protocol;
};

```

### `servent`
```
struct __declspec(align(8)) servent
{
  char *s_name;
  char **s_aliases;
  char *s_proto;
  __int16 s_port;
};

```

### `SERVICE_STATUS_HANDLE__`
```
struct SERVICE_STATUS_HANDLE__
{
  int unused;
};

```

### `SERVICE_TRIGGER_CUSTOM_STATE_ID`
```
struct SERVICE_TRIGGER_CUSTOM_STATE_ID
{
  unsigned int Data[2];
};

```

### `stat`
```
struct stat
{
  unsigned int st_dev;
  unsigned __int16 st_ino;
  unsigned __int16 st_mode;
  __int16 st_nlink;
  __int16 st_uid;
  __int16 st_gid;
  unsigned int st_rdev;
  int st_size;
  __int64 st_atime;
  __int64 st_mtime;
  __int64 st_ctime;
};

```

### `SYSTEM_BATTERY_STATE`
```
struct SYSTEM_BATTERY_STATE
{
  unsigned __int8 AcOnLine;
  unsigned __int8 BatteryPresent;
  unsigned __int8 Charging;
  unsigned __int8 Discharging;
  unsigned __int8 Spare1[3];
  unsigned __int8 Tag;
  unsigned int MaxCapacity;
  unsigned int RemainingCapacity;
  unsigned int Rate;
  unsigned int EstimatedTime;
  unsigned int DefaultAlert1;
  unsigned int DefaultAlert2;
};

```

### `SET_POWER_SETTING_VALUE`
```
struct __declspec(align(4)) SET_POWER_SETTING_VALUE
{
  unsigned int Version;
  _GUID Guid;
  SYSTEM_POWER_CONDITION PowerCondition;
  unsigned int DataLength;
  unsigned __int8 Data[1];
};

```

### `SYSTEM_POWER_CAPABILITIES`
```
struct SYSTEM_POWER_CAPABILITIES
{
  unsigned __int8 PowerButtonPresent;
  unsigned __int8 SleepButtonPresent;
  unsigned __int8 LidPresent;
  unsigned __int8 SystemS1;
  unsigned __int8 SystemS2;
  unsigned __int8 SystemS3;
  unsigned __int8 SystemS4;
  unsigned __int8 SystemS5;
  unsigned __int8 HiberFilePresent;
  unsigned __int8 FullWake;
  unsigned __int8 VideoDimPresent;
  unsigned __int8 ApmPresent;
  unsigned __int8 UpsPresent;
  unsigned __int8 ThermalControl;
  unsigned __int8 ProcessorThrottle;
  unsigned __int8 ProcessorMinThrottle;
  unsigned __int8 ProcessorMaxThrottle;
  unsigned __int8 FastSystemS4;
  unsigned __int8 Hiberboot;
  unsigned __int8 WakeAlarmPresent;
  unsigned __int8 AoAc;
  unsigned __int8 DiskSpinDown;
  unsigned __int8 spare3[8];
  unsigned __int8 SystemBatteriesPresent;
  unsigned __int8 BatteriesAreShortTerm;
  BATTERY_REPORTING_SCALE BatteryScale[3];
  _SYSTEM_POWER_STATE AcOnLineWake;
  _SYSTEM_POWER_STATE SoftLidWake;
  _SYSTEM_POWER_STATE RtcWake;
  _SYSTEM_POWER_STATE MinDeviceWakeState;
  _SYSTEM_POWER_STATE DefaultLowLatencyWake;
};

```

### `SChannelHookCallInfo`
```
struct SChannelHookCallInfo
{
  _GUID iid;
  unsigned int cbSize;
  _GUID uCausality;
  unsigned int dwServerPid;
  unsigned int iMethod;
  void *pObject;
};

```

### `sockaddr_dl`
```
struct sockaddr_dl
{
  unsigned __int16 sdl_family;
  unsigned __int8 sdl_data[8];
  unsigned __int8 sdl_zero[4];
};

```

### `SleepActivationRule`
```
struct __cppobj SleepActivationRule : ActivationRule
{
};

```

### `SleepActivationRule_vtbl`
```
struct /*VFT*/ SleepActivationRule_vtbl
{
  void (__fastcall *~ActivationRule)(ActivationRule *this);
  std::unique_ptr<ActivationRule> *(__fastcall *create)(ActivationRule *this, std::unique_ptr<ActivationRule> *result, Json::Value *);
  bool (__fastcall *evaluate)(ActivationRule *this, const IClientInstance *, float, const Camera *);
};

```

### `StartServerResult`
```
struct __cppobj StartServerResult : Bedrock::Threading::IAsyncResult<void>
{
  std::atomic<enum Bedrock::Threading::AsyncStatus> mStatus;
  std::error_code mErrorCode;
  std::exception_ptr mExceptionPtr;
};

```

### `StartServerResult_vtbl`
```
struct /*VFT*/ StartServerResult_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `SkinInfoData_vtbl`
```
struct /*VFT*/ SkinInfoData_vtbl
{
  void (__fastcall *~SkinInfoData)(SkinInfoData *this);
  void (__fastcall *updateSkin)(SkinInfoData *this, const SerializedSkin *, const mce::Image *, const mce::Image *);
  void (__fastcall *updateSkinNe)(SkinInfoData *this, const SerializedSkin *, const mce::Image *, const mce::Image *, const mce::Image *);
  bool (__fastcall *hasValidTexture)(SkinInfoData *this);
  bool (__fastcall *validateAndResizeSkinData)(SkinInfoData *this, mce::Image *, bool);
};

```

### `SleepBehavior`
```
struct __cppobj __declspec(align(8)) SleepBehavior : CameraBehavior<SleepBehavior>
{
  std::function<float __cdecl(float,float,float)> mEase;
  Vec3 mPreRotationOffset;
  Vec3 mPreRotationOffsetVR;
  Vec3 mPostRotationOffset;
};

```

### `SleepBehavior_vtbl`
```
struct /*VFT*/ SleepBehavior_vtbl
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

### `SneakBehavior`
```
struct __cppobj SneakBehavior : CameraBehavior<SneakBehavior>
{
  float mCameraInterpolationRate;
  float mSneakOffset;
};

```

### `SneakBehavior_vtbl`
```
struct /*VFT*/ SneakBehavior_vtbl
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

### `SplineBehavior`
```
struct __cppobj SplineBehavior : CameraBehavior<SplineBehavior>
{
  CriticallyDampedSpring<Vec3> mSmoothingSpring;
  float mSplineVelocity;
  float mSplineDistance;
  Vec3 mSpringVelocity;
  CatmullRomSpline mSpline;
};

```

### `SplineBehavior_vtbl`
```
struct /*VFT*/ SplineBehavior_vtbl
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

### `SleepBehaviorLoader`
```
struct __cppobj SleepBehaviorLoader : CameraBehaviorLoader
{
};

```

### `SleepBehaviorLoader_vtbl`
```
struct /*VFT*/ SleepBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `SneakBehaviorLoader`
```
struct __cppobj SneakBehaviorLoader : CameraBehaviorLoader
{
};

```

### `SneakBehaviorLoader_vtbl`
```
struct /*VFT*/ SneakBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `SplineBehaviorLoader`
```
struct __cppobj SplineBehaviorLoader : CameraBehaviorLoader
{
};

```

### `SplineBehaviorLoader_vtbl`
```
struct /*VFT*/ SplineBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `serialize<CommandOriginData>`
```
struct __cppobj serialize<CommandOriginData>
{
};

```

### `SkinAnimationMapping`
```
struct __cppobj SkinAnimationMapping
{
  std::string shortName;
  std::string identifier;
};

```

### `ServiceLocator<AppConfigs>`
```
struct __cppobj ServiceLocator<AppConfigs>
{
};

```

### `SPSCQueue<std::function<void __cdecl(void)>,512>::Block`
```
struct __cppobj SPSCQueue<std::function<void __cdecl(void)>,512>::Block
{
  Lockless::WeakAtomic<unsigned __int64> front;
  unsigned __int64 localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned __int64> tail;
  unsigned __int64 localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<std::function<void __cdecl(void)>,512>::Block *> next;
  char *data;
  const unsigned __int64 sizeMask;
  char *rawThis;
};

```

### `ServerPlayer::NearbyActor`
```
struct __cppobj __declspec(align(8)) ServerPlayer::NearbyActor
{
  bool isAutonomous;
  __declspec(align(4)) _BYTE state[4];
  Actor *tempActor;
  bool isKeepInClient;
};

```

### `ServerMoveInputHandler`
```
struct __cppobj ServerMoveInputHandler : MoveInputHandler
{
};

```

### `ServerMoveInputHandler_vtbl`
```
struct /*VFT*/ ServerMoveInputHandler_vtbl
{
  void (__fastcall *~MoveInput)(MoveInput *this);
  void (__fastcall *tick)(MoveInput *this, IPlayerMovementProxy *);
  void (__fastcall *render)(MoveInput *this, float);
  void (__fastcall *setKey)(MoveInput *this, int, bool);
  void (__fastcall *clearInputState)(MoveInput *this);
  void (__fastcall *clearMovementState)(MoveInput *this);
  bool (__fastcall *allowPicking)(MoveInput *this, float, float);
  void (__fastcall *setJumping)(MoveInput *this, bool);
  void (__fastcall *setAutoJumpingInWater)(MoveInput *this, bool);
  bool (__fastcall *isChangeHeight)(MoveInput *this);
  void (__fastcall *setSneakDown)(MoveInput *this, bool);
  bool (__fastcall *isPlayerMoving)(MoveInput *this);
  const Vec3 *(__fastcall *getGazeDirection)(MoveInput *this);
  void (__fastcall *fillInputPacket)(MoveInputHandler *this, PlayerAuthInputPacket *);
  void (__fastcall *registerInputHandlers)(MoveInputHandler *this, InputHandler *);
  std::unique_ptr<IReplayableActorInput> *(__fastcall *createSnapshot)(MoveInputHandler *this, std::unique_ptr<IReplayableActorInput> *result);
};

```

### `ServerPlayer`
```
struct __cppobj ServerPlayer : Player
{
  NetworkHandler *mNetworkHandler;
  std::function<void __cdecl(ServerPlayer &)> mOnPlayerLoadedCallback;
  NetworkChunkPublisher mChunkPublisherView;
  InventoryMenu mInventoryMenu;
  ContainerID mContainerCounter;
  unsigned int mMaxChunkRadius;
  bool mLoading;
  bool mIsTeacher;
  bool mTeleportedThisTick;
  bool mLocalPlayerInitialized;
  Tick mPrevShieldBlockingTick;
  std::unique_ptr<CompoundTag> mLostDataTag;
  unsigned int mClientViewRadius;
  unsigned int mClientRequestedRadius;
  int mRemainingStructureRefreshTicks;
  StructureFeatureType mCurrentStructureFeature;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastKnownSyncTime;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastKnownDesyncTime;
  float mCheatingStrikeScore;
  std::unordered_map<ActorUniqueID,ServerPlayer::NearbyActor> mNearbyActors;
  std::unique_ptr<ServerMoveInputHandler> mMoveInputHandler;
  InputMode mCurrentInputMode;
  ClientPlayMode mPlayMode;
  PlayerMovementTelemetryData mMovementData;
  CallbackToken mCloseContainerToken;
  std::string mLoginUid;
  Vec3 mLastValidRecvPos;
  bool mLastRecvOnground;
  bool mCameraDeparted;
  bool mThirdPersonPerspective;
  Vec2 mRotationToCamera;
};

```

### `ServiceLocator<DataUtils::MiscData>`
```
struct __cppobj ServiceLocator<DataUtils::MiscData>
{
};

```

### `ServiceLocator<IRayTracingOptions>`
```
struct __cppobj ServiceLocator<IRayTracingOptions>
{
};

```

### `ServiceReference<NetworkDebugManager>`
```
struct __cppobj ServiceReference<NetworkDebugManager>
{
  std::shared_lock<std::shared_mutex> mLock;
  Bedrock::NonOwnerPointer<NetworkDebugManager> mService;
};

```

### `ServiceLocator<NetworkDebugManager>`
```
struct __cppobj ServiceLocator<NetworkDebugManager>
{
};

```

### `ScriptApi::EmptyScriptInterface`
```
struct __cppobj ScriptApi::EmptyScriptInterface : ScriptApi::ScriptLanguageInterface
{
};

```

### `ScriptApi::EmptyScriptInterface_vtbl`
```
struct /*VFT*/ ScriptApi::EmptyScriptInterface_vtbl
{
  void (__fastcall *~ScriptLanguageInterface)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *initialized)(ScriptApi::ScriptLanguageInterface *this);
  bool (__fastcall *runScript)(ScriptApi::ScriptLanguageInterface *this, const std::string *, const std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *createObject)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createArray)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, const int *, ScriptApi::ScriptReport *);
  bool (__fastcall *cloneObject)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *hasMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *hasMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *setMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *setMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const int *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMember)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, bool, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, long double, ScriptApi::ScriptReport *);
  bool (__fastcall *setValue)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, int, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, bool *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, std::string *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, long double *, ScriptApi::ScriptReport *);
  bool (__fastcall *getValue)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, int *, ScriptApi::ScriptReport *);
  bool (__fastcall *callObjectFunction)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::string *, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *callGlobalFunction)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, const std::vector<ScriptApi::ScriptObjectHandle> *, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *getHandleType)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptObjectType *, ScriptApi::ScriptReport *);
  bool (__fastcall *getMemberNames)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, std::vector<std::string> *, ScriptApi::ScriptReport *);
  bool (__fastcall *getArrayLength)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, int *, ScriptApi::ScriptReport *);
  bool (__fastcall *getGlobalObject)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createUndefined)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *createNull)(ScriptApi::ScriptLanguageInterface *this, ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineGlobalCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineConsoleCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemSharedCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemServerCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
  bool (__fastcall *defineSystemClientCallbacks)(ScriptApi::ScriptLanguageInterface *this, const ScriptApi::ScriptObjectHandle *, ScriptApi::ScriptCallbackInterface *, ScriptApi::ScriptReport *);
};

```

### `ScriptApi::WORKAROUNDS::tempActorComponent`
```
struct __cppobj ScriptApi::WORKAROUNDS::tempActorComponent
{
  ActorUniqueID mID;
};

```

### `ScriptApi::WORKAROUNDS::tempLevelComponent`
```
struct __cppobj ScriptApi::WORKAROUNDS::tempLevelComponent
{
};

```

### `Social::<lambda_4951989daa4d24f0a9e4e63253abd18e>`
```
struct __cppobj Social::<lambda_4951989daa4d24f0a9e4e63253abd18e>
{
};

```

### `Social::<lambda_1b3578b298c639bea154403ee0cec1d9>`
```
struct __cppobj Social::<lambda_1b3578b298c639bea154403ee0cec1d9>
{
};

```

### `SPSCQueue<std::string,512>`
```
struct __cppobj SPSCQueue<std::string,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *> mTailBlock;
  unsigned __int64 mLargestBlockSize;
};

```

### `StringByteOutput`
```
struct __cppobj StringByteOutput : BytesDataOutput
{
  std::string *mBuffer;
};

```

### `StringByteOutput_vtbl`
```
struct /*VFT*/ StringByteOutput_vtbl
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

### `StringByteInput_vtbl`
```
struct /*VFT*/ StringByteInput_vtbl
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

### `SPSCQueue<unsigned int,512>::Block`
```
struct __cppobj SPSCQueue<unsigned int,512>::Block
{
  Lockless::WeakAtomic<unsigned __int64> front;
  unsigned __int64 localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned __int64> tail;
  unsigned __int64 localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<unsigned int,512>::Block *> next;
  char *data;
  const unsigned __int64 sizeMask;
  char *rawThis;
};

```

### `ServiceLocator<mce::framebuilder::FrameBuilder>`
```
struct __cppobj ServiceLocator<mce::framebuilder::FrameBuilder>
{
};

```

### `ScriptLevelAreaBinderComponent`
```
struct __cppobj ScriptLevelAreaBinderComponent : ScriptBinderComponent
{
  mce::UUID mUUID;
};

```

### `ScriptLevelAreaBinderComponent_vtbl`
```
struct /*VFT*/ ScriptLevelAreaBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptActorAreaBinderComponent`
```
struct __cppobj ScriptActorAreaBinderComponent : ScriptBinderComponent
{
  ActorUniqueID mActorId;
};

```

### `ScriptActorAreaBinderComponent_vtbl`
```
struct /*VFT*/ ScriptActorAreaBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptOnlyComponents<ScriptClientContext>::ScriptOnly`
```
struct __cppobj ScriptOnlyComponents<ScriptClientContext>::ScriptOnly
{
  std::map<std::string,Json::Value> mLookup;
};

```

### `StoreSalesOffersQuery`
```
struct __cppobj StoreSalesOffersQuery : SearchQuery
{
};

```

### `StorePromoSearchQuery`
```
struct __cppobj StorePromoSearchQuery : StoreSearchQuery
{
  const int mNumberOfOffers;
  std::string mRowNameOfferUnopened;
  std::string mRowNameOfferOpened;
  std::string mRowNameNoOffersLeft;
  std::string mRowNameComingSoon;
  std::string mUnlockDate;
};

```

### `StoreSearchQueryFactory`
```
struct __cppobj StoreSearchQueryFactory
{
};

```

### `ScriptBinderItemStackTemplate`
```
struct __cppobj ScriptBinderItemStackTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderItemStackTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderItemStackTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptLevelBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptLevelBinderComponent : ScriptBinderComponent
{
  entt::entity mEcsId;
};

```

### `ScriptLevelBinderComponent_vtbl`
```
struct /*VFT*/ ScriptLevelBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptBinderLevelTemplate`
```
struct __cppobj ScriptBinderLevelTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderLevelTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderLevelTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBlockPositionBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptBlockPositionBinderComponent : ScriptBinderComponent
{
  BlockPos mPosition;
};

```

### `ScriptBlockPositionBinderComponent_vtbl`
```
struct /*VFT*/ ScriptBlockPositionBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptTickingAreaBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptTickingAreaBinderComponent : ScriptBinderComponent
{
  ScriptApi::ScriptObjectHandle mData;
};

```

### `ScriptTickingAreaBinderComponent_vtbl`
```
struct /*VFT*/ ScriptTickingAreaBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptActorUniqueIdBinderComponent`
```
struct __cppobj ScriptActorUniqueIdBinderComponent : ScriptBinderComponent
{
  ActorUniqueID mActorId;
};

```

### `ScriptActorUniqueIdBinderComponent_vtbl`
```
struct /*VFT*/ ScriptActorUniqueIdBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptBinderItemActorTemplate`
```
struct __cppobj ScriptBinderItemActorTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderItemActorTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderItemActorTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderActorTemplate`
```
struct __cppobj ScriptBinderActorTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderActorTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderActorTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptQueryBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptQueryBinderComponent : ScriptBinderComponent
{
  entt::entity mEcsId;
};

```

### `ScriptQueryBinderComponent_vtbl`
```
struct /*VFT*/ ScriptQueryBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptBinderQueryTemplate`
```
struct __cppobj ScriptBinderQueryTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderQueryTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderQueryTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderActorTickingAreaTemplate`
```
struct __cppobj ScriptBinderActorTickingAreaTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderActorTickingAreaTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderActorTickingAreaTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderLevelTickingAreaTemplate`
```
struct __cppobj ScriptBinderLevelTickingAreaTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderLevelTickingAreaTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderLevelTickingAreaTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderBlockTemplate`
```
struct __cppobj ScriptBinderBlockTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderBlockTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderBlockTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptComponentBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptComponentBinderComponent : ScriptBinderComponent
{
  ScriptApi::ScriptObjectHandle mData;
};

```

### `ScriptComponentBinderComponent_vtbl`
```
struct /*VFT*/ ScriptComponentBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptIdentifierBinderComponent`
```
struct __cppobj ScriptIdentifierBinderComponent : ScriptBinderComponent
{
  std::string mIdentifier;
};

```

### `ScriptIdentifierBinderComponent_vtbl`
```
struct /*VFT*/ ScriptIdentifierBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptBinderComponentTemplate`
```
struct __cppobj ScriptBinderComponentTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderComponentTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderComponentTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptEcsBinderComponent`
```
struct __cppobj __declspec(align(8)) ScriptEcsBinderComponent : ScriptBinderComponent
{
  entt::entity mEcsId;
};

```

### `ScriptEcsBinderComponent_vtbl`
```
struct /*VFT*/ ScriptEcsBinderComponent_vtbl
{
  void (__fastcall *~ScriptBinderComponent)(ScriptBinderComponent *this);
  bool (__fastcall *serialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *deserialize)(ScriptBinderComponent *this, ScriptEngine *, const ScriptApi::ScriptObjectHandle *);
};

```

### `ScriptBinderPureEcsTemplate`
```
struct __cppobj ScriptBinderPureEcsTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderPureEcsTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderPureEcsTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ScriptBinderEventDataTemplate`
```
struct __cppobj ScriptBinderEventDataTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderEventDataTemplate_vtbl`
```
struct /*VFT*/ ScriptBinderEventDataTemplate_vtbl
{
  void (__fastcall *~ScriptBinderTemplate)(ScriptBinderTemplate *this);
  const std::string *(__fastcall *getTemplateIdentifier)(ScriptBinderTemplate *this);
  void (__fastcall *applyTemplate)(ScriptBinderTemplate *this, ScriptObjectBinder *);
};

```

### `ShooterItemComponent::ShooterAmmunitionEntry`
```
struct __cppobj __declspec(align(8)) ShooterItemComponent::ShooterAmmunitionEntry
{
  ItemDescriptor itemDesc;
  bool useOffhand;
  bool searchInventory;
  bool useInCreative;
};

```

### `ShooterItemComponent::DrawDuration`
```
struct __cppobj ShooterItemComponent::DrawDuration
{
  float mDuration;
};

```

### `ShooterItemComponent`
```
struct __cppobj __declspec(align(8)) ShooterItemComponent : ItemComponent
{
  std::vector<ShooterItemComponent::ShooterAmmunitionEntry> mAmmunition;
  ShooterItemComponent::DrawDuration mDrawDuration;
  float mLaunchPowerScale;
  float mMaxLaunchPower;
  bool mScalePowerByDrawDuration;
  bool mChargeOnDraw;
  const float kMultishotAngleDelta;
};

```

### `ShooterItemComponent_vtbl`
```
struct /*VFT*/ ShooterItemComponent_vtbl
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

### `Social::<lambda_acbc67f15aaf0ba128bb83c5c6c80707>`
```
struct __cppobj Social::<lambda_acbc67f15aaf0ba128bb83c5c6c80707>
{
};

```

### `Social::<lambda_1ba478ff8211129fbe885f139a38480a>`
```
struct __cppobj Social::<lambda_1ba478ff8211129fbe885f139a38480a>
{
};

```

### `serialize<GameRulesChangedPacketData>`
```
struct __cppobj serialize<GameRulesChangedPacketData>
{
};

```

### `ScreenRenderer::QuadBuffer`
```
struct __cppobj ScreenRenderer::QuadBuffer : std::vector<Vec2>
{
};

```

### `ScriptRuntime`
```
struct __cppobj ScriptRuntime
{
  ScriptRuntime_vtbl *__vftable /*VFT*/;
};

```

### `ScriptInstance`
```
struct __cppobj ScriptInstance
{
  ScriptInstance_vtbl *__vftable /*VFT*/;
};

```

### `ScriptInstance_vtbl`
```
struct /*VFT*/ ScriptInstance_vtbl
{
  void (__fastcall *~ScriptInstance)(ScriptInstance *this);
  void (__fastcall *bindInternalObject)(ScriptInstance *this, void *);
  void (__fastcall *unbindInternalObject)(ScriptInstance *this);
  void (__fastcall *callVoidFunction)(ScriptInstance *this, const char *);
  void (__fastcall *callIntFunction)(ScriptInstance *this, const char *, int);
  void (__fastcall *callStringFunction)(ScriptInstance *this, const char *, const std::string *);
  int (__fastcall *callStringFunctionInt)(ScriptInstance *this, const char *, const std::string *);
  void (__fastcall *callString2Function)(ScriptInstance *this, const char *, const std::string *, const std::string *);
  void (__fastcall *callProtocolFunction)(ScriptInstance *this, const char *, const std::string *, const std::string *);
};

```

### `ScriptRuntime_vtbl`
```
struct /*VFT*/ ScriptRuntime_vtbl
{
  void (__fastcall *~ScriptRuntime)(ScriptRuntime *this);
  bool (__fastcall *startUp)(ScriptRuntime *this, const std::string *);
  void (__fastcall *cleanUp)(ScriptRuntime *this);
  bool (__fastcall *init)(ScriptRuntime *this);
  bool (__fastcall *start)(ScriptRuntime *this);
  bool (__fastcall *test)(ScriptRuntime *this);
  ScriptInstance *(__fastcall *createInstance)(ScriptRuntime *this, void *);
  ScriptInstance *(__fastcall *createInstance)(ScriptRuntime *this, const std::string *);
  void (__fastcall *destroyInstance)(ScriptRuntime *this, ScriptInstance *);
  const std::string *(__fastcall *getScriptPath)(ScriptRuntime *this);
};

```

### `ShowLoginViewStage`
```
struct __cppobj ShowLoginViewStage : BaseStage
{
};

```

### `ShowLoginViewStage_vtbl`
```
struct /*VFT*/ ShowLoginViewStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `Social::Events::AggregationEventListener`
```
struct __cppobj Social::Events::AggregationEventListener : Social::Events::IEventListener
{
  Core::PathBuffer<std::string > mLogFileName;
  Core::FileStream mLogFile;
  unsigned int mMaxSecondsBetweenSends;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeOfLastSend;
  bool mSendDebugEventsToFile;
  std::mutex mEventQueueMutex;
  std::unordered_map<std::string,std::deque<Social::Events::Event>> mNonAggregatedEventQueue;
  std::unordered_map<std::string,std::deque<Social::Events::Event>> mAggregatedEventQueue;
  std::unordered_map<std::string,std::deque<Social::Events::Event>> mCustomAggregatedEventQueue;
  unsigned int mCurrentEventQueueCount;
  unsigned int mRegularMaxBatchSize;
  unsigned int mThrottledMaxBatchSize;
  unsigned int mMaxEventsInBatch;
  unsigned int mRegularSendIntervalSecs;
  unsigned int mThrottledSendIntervalSecs;
};

```

### `Social::Events::AggregationEventListener_vtbl`
```
struct /*VFT*/ Social::Events::AggregationEventListener_vtbl
{
  void (__fastcall *~IEventListener)(Social::Events::IEventListener *this);
  void (__fastcall *recordEvent)(Social::Events::IEventListener *this, const Social::Events::Event *);
  void (__fastcall *sendEvents)(Social::Events::IEventListener *this, bool);
  int (__fastcall *getEventTagsFilter)(Social::Events::IEventListener *this);
  void (__fastcall *stopDebugEventLogging)(Social::Events::IEventListener *this);
  void (__fastcall *sendEvent)(Social::Events::AggregationEventListener *this, const Social::Events::Event *);
  bool (__fastcall *_checkAgainstEventAllowlist)(Social::Events::AggregationEventListener *this, const Social::Events::Event *);
  bool (__fastcall *_isListenerReadyForEvents)(Social::Events::AggregationEventListener *this);
};

```

### `Social::Events::FileEventLogger`
```
struct __cppobj Social::Events::FileEventLogger : Social::Events::AggregationEventListener
{
};

```

### `Social::Events::FileEventLogger_vtbl`
```
struct /*VFT*/ Social::Events::FileEventLogger_vtbl
{
  void (__fastcall *~IEventListener)(Social::Events::IEventListener *this);
  void (__fastcall *recordEvent)(Social::Events::IEventListener *this, const Social::Events::Event *);
  void (__fastcall *sendEvents)(Social::Events::IEventListener *this, bool);
  int (__fastcall *getEventTagsFilter)(Social::Events::IEventListener *this);
  void (__fastcall *stopDebugEventLogging)(Social::Events::IEventListener *this);
  void (__fastcall *sendEvent)(Social::Events::AggregationEventListener *this, const Social::Events::Event *);
  bool (__fastcall *_checkAgainstEventAllowlist)(Social::Events::AggregationEventListener *this, const Social::Events::Event *);
  bool (__fastcall *_isListenerReadyForEvents)(Social::Events::AggregationEventListener *this);
};

```

### `ServiceLocator<Social::UserManager>`
```
struct __cppobj ServiceLocator<Social::UserManager>
{
};

```

### `ServiceLocator<ProfilingManager>`
```
struct __cppobj ServiceLocator<ProfilingManager>
{
};

```

### `ServiceLocator<Bedrock::Threading::PendingConditionals>`
```
struct __cppobj ServiceLocator<Bedrock::Threading::PendingConditionals>
{
};

```

### `ServiceLocator<ChunkPerformanceData>`
```
struct __cppobj ServiceLocator<ChunkPerformanceData>
{
};

```

### `ServiceLocator<Core::LoadTimeProfiler>`
```
struct __cppobj ServiceLocator<Core::LoadTimeProfiler>
{
};

```

### `ServiceLocator<ResourceLoadManager>`
```
struct __cppobj ServiceLocator<ResourceLoadManager>
{
};

```

### `ServiceLocator<mce::FileWatcherNull>`
```
struct __cppobj ServiceLocator<mce::FileWatcherNull>
{
};

```

### `ServiceLocator<DateManager>`
```
struct __cppobj ServiceLocator<DateManager>
{
};

```

### `ScreenshotLoader`
```
struct __cppobj ScreenshotLoader : AppResourceLoader
{
  IMinecraftGame *mMinecraft;
};

```

### `ServiceLocator<IEntitlementManager>`
```
struct __cppobj ServiceLocator<IEntitlementManager>
{
};

```

### `stdext::reference_wrapper<Localization const >`
```
struct __cppobj stdext::reference_wrapper<Localization const >
{
  const Localization *ptr;
};

```

### `Social::Events::AutomationEventLogger`
```
struct __cppobj __declspec(align(8)) Social::Events::AutomationEventLogger : Social::Events::IEventListener
{
  Automation::AutomationClient *mAutomationClient;
  std::unordered_map<std::string,std::deque<Social::Events::Event>> mEventQueue;
  long double mSecondsBetweenSends;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeOfLastSend;
  bool mSendDebugEventsToFile;
};

```

### `Social::Events::AutomationEventLogger_vtbl`
```
struct /*VFT*/ Social::Events::AutomationEventLogger_vtbl
{
  void (__fastcall *~IEventListener)(Social::Events::IEventListener *this);
  void (__fastcall *recordEvent)(Social::Events::IEventListener *this, const Social::Events::Event *);
  void (__fastcall *sendEvents)(Social::Events::IEventListener *this, bool);
  int (__fastcall *getEventTagsFilter)(Social::Events::IEventListener *this);
  void (__fastcall *stopDebugEventLogging)(Social::Events::IEventListener *this);
};

```

### `ServiceLocator<BasicTestProfileStats>`
```
struct __cppobj ServiceLocator<BasicTestProfileStats>
{
};

```

### `SimpleCallProgressHandler`
```
struct __cppobj SimpleCallProgressHandler : ProgressHandler
{
  std::string mProgressTitle;
  std::string mProgressMessage;
  std::function<void __cdecl(void)> mStartCallback;
};

```

### `SimpleCallProgressHandler_vtbl`
```
struct /*VFT*/ SimpleCallProgressHandler_vtbl
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

### `ScreenshotUtils`
```
struct __cppobj ScreenshotUtils
{
};

```

### `ServiceLocator<GameStore>`
```
struct __cppobj ServiceLocator<GameStore>
{
};

```

### `ScrollbarDynamics::TargetPosDeltaSim`
```
struct __cppobj ScrollbarDynamics::TargetPosDeltaSim
{
  float mAccumulatedDelta;
  float mTimeAccumulator;
  float mInterpStart;
  float mInterpEnd;
};

```

### `ScrollbarDynamics`
```
struct __cppobj ScrollbarDynamics
{
  float mCurrentPosition;
  float mLastPosition;
  float mCurrentVelocity;
  float mForces;
  float mMinRange;
  float mMaxRange;
  float mMaxDisplacementPastMinMax;
  float mTargetPosition;
  float mTargetVelocity;
  float mTargetPosDelta;
  bool mTargetPositionActive;
  ScrollbarDynamics::TargetPosDeltaSim mPosDeltaSim;
  bool mFinishFlick;
  float mTargetPntMovedDist;
};

```

### `ScrollViewComponent`
```
struct __cppobj __declspec(align(8)) ScrollViewComponent : UIComponent
{
  std::weak_ptr<UIControl> mScrollViewPort;
  std::weak_ptr<UIControl> mScrollContent;
  std::weak_ptr<UIControl> mScrollTrack;
  std::weak_ptr<UIControl> mScrollBox;
  std::weak_ptr<UIControl> mBoxAndTrackPanel;
  unsigned int mTrackScrollButtonId;
  unsigned int mTouchScrollButtonId;
  unsigned int mScrollingActiveEventId;
  unsigned int mScrollBarReleasedEventId;
  unsigned int mScrollBarBottomEventId;
  ButtonState mLastTouchButtonState;
  ButtonState mLastScrollBoxPressedState;
  float mDistanceForScrollEventsToPassOn;
  float mScrollSpeed;
  bool mGestureControlMode;
  bool mAlwaysHandleScrolling;
  bool mTouchMode;
  float lastPosition;
  float lastMaxRange;
  __int16 mId;
  bool mCanScroll;
  ScrollbarDynamics mScrollbarDynamics;
  bool mTouchScrollBarVisible;
  float mTouchScrollBarIntensity;
  bool mJumpToBottomOnUpdate;
  float mContentSize;
};

```

### `ScrollViewComponent_vtbl`
```
struct /*VFT*/ ScrollViewComponent_vtbl
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

### `StackGridComponent`
```
struct __cppobj StackGridComponent : UIComponent
{
  std::shared_ptr<UIControlFactory> mControlFactory;
  int mItemCount;
  int mCurItemCount;
  std::string mCollectionName;
  int mId;
  std::vector<std::shared_ptr<UIControl>> templates;
};

```

### `StackGridComponent_vtbl`
```
struct /*VFT*/ StackGridComponent_vtbl
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

### `SliderComponent`
```
struct __cppobj SliderComponent : UIComponent
{
  std::weak_ptr<UIControl> mSliderBoxControl;
  unsigned int mTrackScrollButtonId;
  unsigned int mSmallDecreaseButtonId;
  unsigned int mSmallIncreaseButtonId;
  unsigned int mSelectedButtonId;
  unsigned int mDeselectedButtonId;
  bool mTrackActive;
  ui::OrientationType mSliderDirection;
  bool mInverted;
  float mPercentage;
  int mCurrentStep;
  int mNumberSteps;
  float mSliderSpeed;
  float mSliderTimeout;
  long double mLastRefreshTime;
  __int8 mStepSlider : 1;
  __int8 mHover : 1;
  __int8 mSelectOnHover : 1;
  unsigned int mSliderNameId;
  std::string mSliderCollectionName;
  ui::CardinalDirection mLastDirection;
  std::weak_ptr<UIControl> mBackground;
  std::weak_ptr<UIControl> mBackgroundHover;
  std::weak_ptr<UIControl> mProgress;
  std::weak_ptr<UIControl> mProgressHover;
  std::weak_ptr<UIControl> mDefaultControl;
  std::weak_ptr<UIControl> mHoverControl;
  std::string mTTSSliderValue;
};

```

### `SliderComponent_vtbl`
```
struct /*VFT*/ SliderComponent_vtbl
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

### `serialize<GameRulesChangedPacketData>::read::__l2::<lambda_aaff50ed8a818a81e48a044a84e500e1>`
```
struct __cppobj serialize<GameRulesChangedPacketData>::read::__l2::<lambda_aaff50ed8a818a81e48a044a84e500e1>
{
};

```

### `serialize<GameRulesChangedPacketData>::write::__l2::<lambda_e674b880044a51647f8a817da1ced75b>`
```
struct __cppobj serialize<GameRulesChangedPacketData>::write::__l2::<lambda_e674b880044a51647f8a817da1ced75b>
{
};

```

### `ShapedRecipe_vtbl`
```
struct /*VFT*/ ShapedRecipe_vtbl
{
  void (__fastcall *~Recipe)(Recipe *this);
  const std::vector<ItemInstance> *(__fastcall *assemble)(Recipe *this, CraftingContainer *);
  int (__fastcall *getCraftingSize)(Recipe *this);
  const RecipeIngredient *(__fastcall *getIngredient)(Recipe *this, int, int);
  const std::vector<ItemInstance> *(__fastcall *getResultItem)(Recipe *this);
  bool (__fastcall *isShapeless)(Recipe *this);
  bool (__fastcall *matches)(Recipe *this, CraftingContainer *, Level *);
  int (__fastcall *size)(Recipe *this);
  const mce::UUID *(__fastcall *getId)(Recipe *this);
  const ItemPack *(__fastcall *getItemPack)(Recipe *this);
  bool (__fastcall *isMultiRecipe)(Recipe *this);
  std::string *(__fastcall *getTypeString)(Recipe *this, std::string *result);
  bool (__fastcall *itemValidForRecipe)(Recipe *this, const ItemDescriptor *, const ItemStack *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, int, int, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *);
};

```

### `ShapelessRecipe`
```
struct __cppobj ShapelessRecipe : Recipe
{
  std::vector<RecipeIngredient> mIngredients;
  std::vector<ItemInstance> mResult;
};

```

### `ShapelessRecipe_vtbl`
```
struct /*VFT*/ ShapelessRecipe_vtbl
{
  void (__fastcall *~Recipe)(Recipe *this);
  const std::vector<ItemInstance> *(__fastcall *assemble)(Recipe *this, CraftingContainer *);
  int (__fastcall *getCraftingSize)(Recipe *this);
  const RecipeIngredient *(__fastcall *getIngredient)(Recipe *this, int, int);
  const std::vector<ItemInstance> *(__fastcall *getResultItem)(Recipe *this);
  bool (__fastcall *isShapeless)(Recipe *this);
  bool (__fastcall *matches)(Recipe *this, CraftingContainer *, Level *);
  int (__fastcall *size)(Recipe *this);
  const mce::UUID *(__fastcall *getId)(Recipe *this);
  const ItemPack *(__fastcall *getItemPack)(Recipe *this);
  bool (__fastcall *isMultiRecipe)(Recipe *this);
  std::string *(__fastcall *getTypeString)(Recipe *this, std::string *result);
  bool (__fastcall *itemValidForRecipe)(Recipe *this, const ItemDescriptor *, const ItemStack *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, int, int, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *);
};

```

### `SplashTextRenderer`
```
struct __cppobj SplashTextRenderer : MinecraftUICustomRenderer
{
  int mCurrentSplash;
  long double mElapsedTime;
  bool mLoadedSplashes;
  bool mTreatmentsLoaded;
  std::vector<std::string> mSplashes;
};

```

### `SplashTextRenderer_vtbl`
```
struct /*VFT*/ SplashTextRenderer_vtbl
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

### `StructureVolumeRenderer`
```
struct __cppobj StructureVolumeRenderer : MinecraftUICustomRenderer, BlockSourceListener, AppPlatformListener
{
  bool mInitialize;
  bool mListenerInitialized;
  bool mRendered;
  Vec2 mRotation;
  AABB mLastArea;
  std::unique_ptr<RenderChunkBuilder> mChunkBuilder;
  std::unordered_map<BlockPos,std::unique_ptr<RenderChunkInstanced>> mRenderChunkInstances;
  Tick mRenderTick;
  Vec2 mLastSortRotation;
  Vec3 mSortingCameraPos;
  bool mResort;
  BlockSource *mUnsafeSourcePointer;
  std::shared_ptr<RenderChunkSorterSharedInfo> mSharedSortInfo;
  RenderChunkSorter mChunkSorter;
  mce::MaterialPtr mAxesMaterial;
};

```

### `StructureVolumeRenderer_vtbl`
```
struct /*VFT*/ StructureVolumeRenderer_vtbl
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

### `ScrollbarBoxComponent`
```
struct __cppobj ScrollbarBoxComponent : UIComponent
{
  std::weak_ptr<UIControl> mScrollView;
};

```

### `ScrollbarBoxComponent_vtbl`
```
struct /*VFT*/ ScrollbarBoxComponent_vtbl
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

### `ScrollTrackComponent`
```
struct __cppobj ScrollTrackComponent : UIComponent
{
  std::weak_ptr<UIControl> mScrollView;
};

```

### `ScrollTrackComponent_vtbl`
```
struct /*VFT*/ ScrollTrackComponent_vtbl
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

### `SelectionWheelComponent`
```
struct __cppobj __declspec(align(8)) SelectionWheelComponent : UIComponent
{
  std::weak_ptr<UIControl> mWeakScreenControl;
  std::vector<std::weak_ptr<UIControl>> mStateControls;
  bool mConsumeEvents;
  int mSliceCount;
  int mHoverSlice;
  int mLastValidHoverSlice;
  float mInnerRadius;
  float mOuterRadius;
  unsigned int mButtonNameId;
  unsigned int mIterateLeftNameId;
  unsigned int mIterateRightNameId;
  std::vector<unsigned int> mSelectSlotNameIds;
  InputMode mInputMode;
};

```

### `SelectionWheelComponent_vtbl`
```
struct /*VFT*/ SelectionWheelComponent_vtbl
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

### `SliderBoxComponent`
```
struct __cppobj SliderBoxComponent : UIComponent
{
  bool mHover;
  bool mSelected;
  std::weak_ptr<UIControl> mSliderControl;
  std::weak_ptr<UIControl> mDefaultControl;
  std::weak_ptr<UIControl> mHoverControl;
  std::weak_ptr<UIControl> mIndentControl;
  std::weak_ptr<UIControl> mLockedControl;
};

```

### `SliderBoxComponent_vtbl`
```
struct /*VFT*/ SliderBoxComponent_vtbl
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

### `SliderManagerComponent`
```
struct __cppobj SliderManagerComponent : UIComponent
{
  SliderManagerBehavior mBehavior;
  std::vector<unsigned int> mSliderCollectionName;
};

```

### `SliderManagerComponent_vtbl`
```
struct /*VFT*/ SliderManagerComponent_vtbl
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

### `SliderChangeSoundEventConditions`
```
struct __cppobj SliderChangeSoundEventConditions
{
};

```

### `SoundComponent::SoundEventInfo`
```
struct __cppobj __declspec(align(8)) SoundComponent::SoundEventInfo
{
  std::string mSoundName;
  float mVolume;
  float mPitch;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPlayTime;
  std::chrono::duration<__int64,std::ratio<1,1000> > mMinTimeBetweenPlays;
  ScreenEventType mScreenEventType;
  SoundEventConditions mEventConditions;
};

```

### `SoundComponent`
```
struct __cppobj SoundComponent : UIComponent
{
  const UISoundPlayer *mSoundPlayer;
  float mVolume;
  float mPitch;
  std::string mSoundName;
  std::vector<SoundComponent::SoundEventInfo> mSoundEvents;
};

```

### `SoundComponent_vtbl`
```
struct /*VFT*/ SoundComponent_vtbl
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

### `StackPanelComponent`
```
struct __cppobj __declspec(align(8)) StackPanelComponent : UIComponent
{
  ui::OrientationType mOrientation;
  int mFirstRenderedChild;
  bool mShouldUsePriority;
};

```

### `StackPanelComponent_vtbl`
```
struct /*VFT*/ StackPanelComponent_vtbl
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

### `SpriteComponent::_drawTiled::__l2::<lambda_46892d663261051bb3234571806a4048>`
```
struct __cppobj SpriteComponent::_drawTiled::__l2::<lambda_46892d663261051bb3234571806a4048>
{
  std::vector<ImageInfo> *imagesToDraw;
};

```

### `SpriteComponent::_drawTiled::__l2::<lambda_dca1b89cc5ad2343102b882bd8381752>`
```
struct __cppobj SpriteComponent::_drawTiled::__l2::<lambda_dca1b89cc5ad2343102b882bd8381752>
{
  SpriteComponent *const __this;
  UIRenderContext *context;
};

```

### `SpriteComponent::_drawTiledClipped::__l2::<lambda_416a48418e413e3fae37fa1fc52a70a8>`
```
struct __cppobj SpriteComponent::_drawTiledClipped::__l2::<lambda_416a48418e413e3fae37fa1fc52a70a8>
{
  SpriteComponent *const __this;
  UIRenderContext *context;
};

```

### `SpriteComponent::_drawTiledClipped::__l2::<lambda_1afa1fd32fa7e2e08e8255091cc99e81>`
```
struct __cppobj SpriteComponent::_drawTiledClipped::__l2::<lambda_1afa1fd32fa7e2e08e8255091cc99e81>
{
  std::vector<ImageInfo> *imagesToDraw;
};

```

### `SpriteComponent::_drawClipped::__l2::<lambda_af79c45a1301355ef63a198b004e9edc>`
```
struct __cppobj SpriteComponent::_drawClipped::__l2::<lambda_af79c45a1301355ef63a198b004e9edc>
{
  std::vector<ImageInfo> *imagesToDraw;
};

```

### `SpriteComponent::_drawClipped::__l2::<lambda_7a52305ee0f60ae55853c1e0d96cb84c>`
```
struct __cppobj SpriteComponent::_drawClipped::__l2::<lambda_7a52305ee0f60ae55853c1e0d96cb84c>
{
  SpriteComponent *const __this;
  UIRenderContext *context;
};

```

### `SliderManagerComponent::_gatherSliderGroupState::__l9::<lambda_3f4eb6fd3624d8099f02098c2e2309a9>`
```
struct __cppobj SliderManagerComponent::_gatherSliderGroupState::__l9::<lambda_3f4eb6fd3624d8099f02098c2e2309a9>
{
  unsigned int sliderGroup;
};

```

### `SixteenNineComponent`
```
struct __cppobj SixteenNineComponent : RenderableComponent
{
};

```

### `SixteenNineComponent_vtbl`
```
struct /*VFT*/ SixteenNineComponent_vtbl
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
  void (__fastcall *updateUI)(RenderableComponent *this, const UIMeasureStrategy *);
  bool (__fastcall *overridesLayoutAxisOffset)(RenderableComponent *this, const LayoutVariableType);
  float (__fastcall *getLayoutAxisOffsetOverride)(RenderableComponent *this, const LayoutVariableType);
};

```

### `SkinPackPurchaseScreenController`
```
struct __cppobj SkinPackPurchaseScreenController : MainMenuScreenController
{
  const StoreCatalogItem *mCatalogItem;
  SkinPackCollectionModel *mSkinPackCollection;
  PackIdVersion mSkinPackIdentity;
  StoreScreenType mScreenType;
  bool mCheckSkinPack;
  int mMaxSkinsInGrid;
  int mSkinIndex;
  int mPreviewSkinIndex;
  int mHoverSkinIndex;
  const SkinHandle mInitialSkinHandle;
};

```

### `SkinPackPurchaseScreenController_vtbl`
```
struct /*VFT*/ SkinPackPurchaseScreenController_vtbl
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

### `Social::<lambda_c6d983a1676b2f8fec8e673417febd7a>`
```
struct __cppobj Social::<lambda_c6d983a1676b2f8fec8e673417febd7a>
{
};

```

### `Social::<lambda_35d5f2e216aff30c7b5c9c3e72c65aee>`
```
struct __cppobj Social::<lambda_35d5f2e216aff30c7b5c9c3e72c65aee>
{
};

```

### `SearchingForSessionProgressHandler`
```
struct __cppobj SearchingForSessionProgressHandler : ProgressHandler
{
};

```

### `SearchingForSessionProgressHandler_vtbl`
```
struct /*VFT*/ SearchingForSessionProgressHandler_vtbl
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

### `stbtt_vertex`
```
struct stbtt_vertex
{
  __int16 x;
  __int16 y;
  __int16 cx;
  __int16 cy;
  __int16 cx1;
  __int16 cy1;
  unsigned __int8 type;
  unsigned __int8 padding;
};

```

### `stbtt__hheap_chunk`
```
struct stbtt__hheap_chunk
{
  stbtt__hheap_chunk *next;
};

```

### `stbtt__hheap`
```
struct __declspec(align(8)) stbtt__hheap
{
  stbtt__hheap_chunk *head;
  void *first_free;
  int num_remaining_in_head_chunk;
};

```

### `stbtt__active_edge`
```
struct stbtt__active_edge
{
  stbtt__active_edge *next;
  float fx;
  float fdx;
  float fdy;
  float direction;
  float sy;
  float ey;
};

```

### `stbtt__edge`
```
struct stbtt__edge
{
  float x0;
  float y0;
  float x1;
  float y1;
  int invert;
};

```

### `stbtt__point`
```
struct stbtt__point
{
  float x;
  float y;
};

```

### `stbtt_bakedchar`
```
struct stbtt_bakedchar
{
  unsigned __int16 x0;
  unsigned __int16 y0;
  unsigned __int16 x1;
  unsigned __int16 y1;
  float xoff;
  float yoff;
  float xadvance;
};

```

### `stbtt_aligned_quad`
```
struct stbtt_aligned_quad
{
  float x0;
  float y0;
  float s0;
  float t0;
  float x1;
  float y1;
  float s1;
  float t1;
};

```

### `stbrp_context`
```
struct stbrp_context
{
  int width;
  int height;
  int x;
  int y;
  int bottom_y;
};

```

### `stbrp_node`
```
struct stbrp_node
{
  unsigned __int8 x;
};

```

### `stbrp_rect`
```
struct stbrp_rect
{
  int x;
  int y;
  int id;
  int w;
  int h;
  int was_packed;
};

```

### `stbi__write_context`
```
struct stbi__write_context
{
  void (__fastcall *func)(void *, void *, int);
  void *context;
};

```

### `Social::<lambda_2c831ce4442218888aff3b1b9505d5ec>`
```
struct __cppobj Social::<lambda_2c831ce4442218888aff3b1b9505d5ec>
{
};

```

### `Social::<lambda_5f8dcdce88ac115102b5fb0b8b14fdcd>`
```
struct __cppobj Social::<lambda_5f8dcdce88ac115102b5fb0b8b14fdcd>
{
};

```

### `ScriptApi::ScriptEngineFacet`
```
struct __cppobj ScriptApi::ScriptEngineFacet : hbui::FacetBase<ScriptApi::ScriptEngineFacet>
{
  MinecraftClientScriptEngine *mScriptEngine;
};

```

### `ScriptApi::ScriptEngineFacet_vtbl`
```
struct /*VFT*/ ScriptApi::ScriptEngineFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

