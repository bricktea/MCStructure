# R
### `RealmsAllowListScreenController::_sortListModel::__l2::<lambda_c248b0cdd9fa8d24f3e9885441a6b79f>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsAllowListScreenController *const` | __this


### `ResourceLocation`
Offset | Type | Name
-|-|-|-
0 | (4) `ResourceFileSystem` | mFileSystem
8 | (32) `Core::PathBuffer<std::string >` | mPath
40 | (8) `unsigned __int64` | mPathHash
48 | (8) `unsigned __int64` | mFullHash


### `RectangleArea`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | _x0
4 | (4) `float` | _x1
8 | (4) `float` | _y0
12 | (4) `float` | _y1


### `RakNet::SystemAddress`
Offset | Type | Name
-|-|-|-
0 | (128) `RakNet::SystemAddress::<unnamed_type_address>` | address
128 | (2) `unsigned __int16` | debugPort
130 | (2) `unsigned __int16` | systemIndex


### `RakNet::SystemAddress::<unnamed_type_address>`
Offset | Type | Name
-|-|-|-
0 | (128) `sockaddr_storage` | sa_stor
1 | (28) `sockaddr_in6` | addr6
2 | (16) `sockaddr_in` | addr4


### `RakNet::RakNetGUID`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | g
8 | (2) `unsigned __int16` | systemIndex


### `RealmsSettingsScreenController::_gatherSelectedContent::__l2::<lambda_cfa2356ba834150166845153293b2230>`
Offset | Type | Name
-|-|-|-


### `recreateCubemapTexture::__l2::<lambda_e7cd2127989a43aef6f308a4e684b501>`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | stillValid


### `Remapping::Action`
Offset | Type | Name
-|-|-|-
0 | (4) `Remapping::ActionEnum` | mAction
8 | (8) `const char *` | mActionName


### `RenderChunkSorter::sortAndCullFaces::__l67::<lambda_8ad1514ed4cd016d6dc6c8ad4a7c706b>`
Offset | Type | Name
-|-|-|-


### `RatingData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mAverageRating
4 | (4) `int` | mTotalRatingsCount
8 | (4) `int` | mFiveStarCount
12 | (4) `int` | mFourStarCount
16 | (4) `int` | mThreeStarCount
20 | (4) `int` | mTwoStarCount
24 | (4) `int` | mOneStarCount


### `ReviewModel`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ReviewSummaryData>` | mReviewSummary
8 | (8) `std::unique_ptr<ReviewData>` | mReviewByUser
16 | (28) `RatingData` | mPrefetchedRatingData
44 | (4) `int` | mLocalUserRating


### `RenderParams`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseActorRenderContext *` | mBaseActorRenderContext
8 | (8) `MolangVariableMap *` | mVariables
16 | (8) `AnimationComponent *` | mAnimationComponent
24 | (8) `AnimationComponent *` | mRootAnimationComponent
32 | (16) `std::shared_ptr<DataDrivenModel>` | mModel
48 | (4) `_BYTE[4]` | mSourceContext
56 | (8) `Actor *` | mActor
64 | (8) `Actor *` | mOther
72 | (8) `Actor *` | mPlayer
80 | (8) `Actor *` | mTarget
88 | (8) `Actor *` | mParent
96 | (8) `Actor *` | mBaby
104 | (8) `Actor *` | mDamager
112 | (8) `Level *` | mLevel
120 | (8) `ItemStackBase *` | mItemStackBasePtr
128 | (8) `const Block *` | mBlock
136 | (12) `BlockPos` | mBlockPos
152 | (8) `BlockSource *` | mBlockSource
160 | (8) `ActorRenderData *` | mActorRenderData
168 | (8) `ParticleSystem::ParticleEmitter *` | mParticleEmitter
176 | (8) `IBlockWorldGenAPI *` | mBlockPlacementTarget
184 | (4) `int` | mVertexCount
188 | (2) `unsigned __int16` | mSubRenderLayerIndex
192 | (64) `std::function<float __cdecl(void)>` | mRandomFunction
256 | (4) `float` | mCameraDistance
260 | (32) `float[8]` | mParams
296 | (88) `MolangScriptArg` | mThisValue
384 | (88) `MolangScriptArg` | mScratchValue
472 | (4) `RenderParams::<unnamed_type_mFlags>` | mFlags
476 | (12) `Vec3` | mClickPos
488 | (8) `?` | mBlockCache
496 | (16) `RenderParams::<unnamed_type_mModParams>` | mModParams


### `RenderParams::<unnamed_type_mFlags>`
Offset | Type | Name
-|-|-|-
0 | (4) `$E505BEC45AB602A133511C2B9263C9DC` | __s0
1 | (4) `unsigned int` | _data


### `RenderParams::<unnamed_type_mModParams>`
Offset | Type | Name
-|-|-|-
0 | (16) `$8EE7526571220F033655C348230167E3` | __s0


### `ResourcePackRepository::_loadPacks::__l2::<lambda_2e98b8efac21cbcaf57148d7907a3e04>`
Offset | Type | Name
-|-|-|-


### `Random`
Offset | Type | Name
-|-|-|-
0 | (2516) `Bedrock::Application::ThreadOwner<Core::Random>` | mRandom


### `Recipes::sortRecipesByPriority::__l2::<lambda_fa6c4c313829428246aceaa48580a04c>`
Offset | Type | Name
-|-|-|-


### `Range<int,1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mBeginIDX
4 | (4) `const int` | mEndIDX


### `Range<int,-1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mBeginIDX
4 | (4) `const int` | mEndIDX


### `RuntimeLightingManager::_sortChunksToProcessByDistance::__l2::<lambda_833755c377e78ca9d63b7ad5a536fa2f>`
Offset | Type | Name
-|-|-|-


### `ResetEventObj`
Offset | Type | Name
-|-|-|-
0 | (72) `std::condition_variable` | mCondition
72 | (80) `std::mutex` | mMutex
152 | (1) `std::atomic<bool>` | mSet
153 | (1) `bool` | mAutoReset


### `RakNet::TCPInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::TCPInterface_vtbl *` | __vftable
8 | (16) `DataStructures::List<RakNet::PluginInterface2 *>` | messageHandlerList
24 | (4) `RakNet::LocklessUint32_t` | isStarted
28 | (4) `RakNet::LocklessUint32_t` | threadRunning
32 | (8) `unsigned __int64` | listenSocket
40 | (2) `unsigned __int16` | listenPort
42 | (2) `unsigned __int16` | listenMaxIncomingConnections
44 | (2) `unsigned __int16` | listenSocketFamily
48 | (8) `char *` | listenHostAddress
56 | (24) `DataStructures::Queue<RakNet::Packet *>` | headPush
80 | (24) `DataStructures::Queue<RakNet::Packet *>` | tailPush
104 | (8) `RakNet::RemoteClient *` | remoteClients
112 | (4) `int` | remoteClientsLength
120 | (144) `DataStructures::ThreadsafeAllocatingQueue<RakNet::Packet>` | incomingMessages
264 | (144) `DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>` | newIncomingConnections
408 | (144) `DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>` | lostConnections
552 | (144) `DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>` | requestedCloseConnections
696 | (144) `DataStructures::ThreadsafeAllocatingQueue<RakNet::RemoteClient *>` | newRemoteClients
840 | (40) `RakNet::SimpleMutex` | completedConnectionAttemptMutex
880 | (40) `RakNet::SimpleMutex` | failedConnectionAttemptMutex
920 | (24) `DataStructures::Queue<RakNet::SystemAddress>` | completedConnectionAttempts
944 | (24) `DataStructures::Queue<RakNet::SystemAddress>` | failedConnectionAttempts
968 | (4) `int` | threadPriority
976 | (16) `DataStructures::List<unsigned __int64>` | blockingSocketList
992 | (40) `RakNet::SimpleMutex` | blockingSocketListMutex


### `RakNet::LocklessUint32_t`
Offset | Type | Name
-|-|-|-
0 | (4) `volatile int` | value


### `RakNet::SimpleMutex`
Offset | Type | Name
-|-|-|-
0 | (40) `_RTL_CRITICAL_SECTION` | criticalSection


### `RakNet::RakNetRandom`
Offset | Type | Name
-|-|-|-
0 | (2500) `unsigned int[625]` | state
2504 | (8) `unsigned int *` | next
2512 | (4) `int` | left


### `RakStringCleanup`
Offset | Type | Name
-|-|-|-


### `RakNet::RakNetStatistics`
Offset | Type | Name
-|-|-|-
0 | (56) `unsigned __int64[7]` | valueOverLastSecond
56 | (56) `unsigned __int64[7]` | runningTotal
112 | (8) `unsigned __int64` | connectionStartTime
120 | (1) `bool` | isLimitedByCongestionControl
128 | (8) `unsigned __int64` | BPSLimitByCongestionControl
136 | (1) `bool` | isLimitedByOutgoingBandwidthLimit
144 | (8) `unsigned __int64` | BPSLimitByOutgoingBandwidthLimit
152 | (16) `unsigned int[4]` | messageInSendBuffer
168 | (32) `long double[4]` | bytesInSendBuffer
200 | (4) `unsigned int` | messagesInResendBuffer
208 | (8) `unsigned __int64` | bytesInResendBuffer
216 | (4) `float` | packetlossLastSecond
220 | (4) `float` | packetlossTotal


### `RecipeIngredient`
Offset | Type | Name
-|-|-|-
0 | (88) `ItemDescriptorCount` | baseclass_0


### `RenderControllerPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<RenderControllerInfo>` | mRenderControllerInfoPtr


### `ResourcePackListener`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackListener_vtbl *` | __vftable


### `Realms::ConfigInfo::Version`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | branch
32 | (32) `std::string` | reference
64 | (8) `unsigned __int64` | releaseDate


### `ReplayStateConfig`
Offset | Type | Name
-|-|-|-
0 | (16) `ReplayStateConfigThresholds` | mSupportedThresholds
16 | (16) `ReplayStateConfigThresholds` | mUnsupportedThresholds
32 | (1) `_BYTE[1]` | mMode
36 | (4) `int` | mMinCorrectionDelay
40 | (4) `int` | mHistorySize
44 | (1) `bool` | mWriteLog


### `ReplayStateConfigThresholds`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mPositionThreshold
4 | (4) `float` | mVelocityThreshold
8 | (4) `float` | mPositionAcceptance
12 | (4) `float` | mPositionPersuasion


### `RakNet::RakString::SharedString`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::SimpleMutex *` | refCountMutex
8 | (4) `unsigned int` | refCount
16 | (8) `unsigned __int64` | bytesUsed
24 | (8) `char *` | bigString
32 | (8) `char *` | c_str
40 | (100) `char[100]` | smallString


### `RUNTIME_FUNCTION`
Offset | Type | Name
-|-|-|-
0 | (4) `` | FunctionStart
4 | (4) `` | FunctionEnd
8 | (4) `` | UnwindInfo


### `ResourcePath`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPackId
32 | (32) `std::string` | mPath


### `RealmsAllowListScreenController::_initializeLinkedAccounts::__l7::<lambda_441d0914016a9b6c305a20f36bc5f2f0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAllowListScreenController>` | weakThis
16 | (24) `const std::vector<Social::PlatformUserProfileData>` | platformProfiles


### `Realms::Player`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | xuid
64 | (32) `std::string` | realName
96 | (16) `Social::UserPicturePath` | gamerpicLocation
112 | (1) `bool` | isOperator
113 | (1) `bool` | hasAccepted
114 | (1) `bool` | isOnline
115 | (1) `PlayerPermissionLevel` | permission


### `RealmPlayer`
Offset | Type | Name
-|-|-|-
0 | (120) `Realms::Player` | baseclass_0
120 | (4) `RealmsAPI::InviteAction` | mInviteAction
124 | (4) `RealmsAPI::InviteAction` | mOperatorAction
128 | (1) `bool` | mInviteStatusChanged
129 | (1) `bool` | mOperatorStatusChanged
130 | (1) `bool` | mHasPlatformProfile


### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ffa8c62518328c288fb5859793a18aa7>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsAllowListScreenController *const` | __this


### `RealmsAllowListScreenController::_handleUpdateFailed::__l7::<lambda_23eaf5da90f5d5b82364d0cdbe959780>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAllowListScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | callback


### `RealmsAllowListScreenController::_clearMemberList::__l2::<lambda_695f03986dde6d536e9984c5aa9486cd>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAllowListScreenController>` | weakThis
16 | (16) `std::map<std::string,enum RealmsAPI::InviteAction>` | inviteActions
32 | (4) `int` | numbersCleared


### `RealmsAllowListScreenController::sendInvites::__l2::<lambda_ca52ab4501a534a33414fe996c204035>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAllowListScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | callback
80 | (16) `std::map<std::string,enum RealmsAPI::InviteAction>` | inviteActions
96 | (16) `std::shared_ptr<MainMenuScreenModel>` | capturedModel


### `RealmsAllowListScreenController::sendInvites::__l2::<lambda_ca52ab4501a534a33414fe996c204035>::()::__l20::<lambda_8f0c218e3b3b6347718eea49b1047da9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAllowListScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | callback


### `Realms::InviteLink`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | linkId
32 | (32) `std::string` | profileUuid
64 | (32) `std::string` | type
96 | (8) `__int64` | timestamp
104 | (32) `std::string` | url


### `Realms::World`
Offset | Type | Name
-|-|-|-
0 | (8) `Realms::RealmId` | id
8 | (4) `Realms::World::State` | state
16 | (32) `std::string` | name
48 | (32) `std::string` | description
80 | (32) `std::string` | ownerXuid
112 | (32) `std::string` | ownerName
144 | (32) `std::string` | clubId
176 | (4) `int` | daysLeft
180 | (1) `bool` | expired
184 | (4) `int` | maxPlayers
188 | (1) `bool` | newWorld
192 | (4) `int` | gameMode
196 | (1) `bool` | gracePeriod
200 | (4) `int` | difficulty
204 | (1) `bool` | cheatsEnabled
205 | (1) `bool` | full
206 | (1) `bool` | isMember
207 | (1) `bool` | texturePacksRequired
208 | (1) `PlayerPermissionLevel` | defaultPermission
216 | (24) `std::vector<Realms::Player>` | players
240 | (1) `bool` | mValid


### `Realms::RealmId`
Offset | Type | Name
-|-|-|-
0 | (8) `NewType<__int64>` | baseclass_0


### `ReplayStateComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ActorHistory>` | mHistory
8 | (8) `std::unique_ptr<IReplayStatePolicy>` | mPolicy
16 | (8) `unsigned __int64` | mCurrentTick


### `RenderChunkBuilder`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ChunkViewSource>` | mLocalSource
16 | (8) `std::unique_ptr<BlockTessellator>` | mBlockTessellator
24 | (1) `bool` | mAllDark
25 | (1) `bool` | mSkyLit
26 | (1) `bool` | mBlendCanRenderAsOpaque
28 | (4) `float` | mAverageSkyLight
32 | (168) `std::array<std::vector<RenderChunkQuadInfo>,7>` | mFaceMetadata
200 | (112) `std::array<RangeIndices,14>` | mRenderLayerRanges
312 | (8) `std::vector<BlockQueueEntry> *` | mQueues
320 | (8) `std::vector<BlockQueueEntry> *` | mSimpleOpaqueBlockQueue
328 | (112) `unsigned __int64[14]` | mQueueIndexCounts
440 | (8) `std::unique_ptr<Tessellator>` | mOwnedTessellator
448 | (16) `std::shared_ptr<ClientBlockPipeline::MaterialRepository>` | mMaterialRepository
464 | (8) `std::unique_ptr<ClientBlockPipeline::BlockTessellatorPipeline>` | mPipelineTessellator
472 | (8) `std::unique_ptr<ClientBlockPipeline::Description>` | mPipelineDescription
480 | (8) `Tessellator *` | mTessellator
488 | (8) `std::unique_ptr<mce::Mesh>` | mBuiltMesh
496 | (8) `std::unique_ptr<mce::MeshData>` | mMeshData
504 | (1) `bool` | mGUIRendering
508 | (28) `AABB` | mBuildBoundingBox


### `RangeIndices`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mStart
4 | (4) `int` | mCount


### `RenderChunkInstanced`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mDistanceFromCamera2
4 | (4) `float` | mChunkBuildPriority
8 | (1) `__int8` | _bf_8
9 | (1) `std::atomic<enum RenderChunkInstanced::SortState>` | mSortState
10 | (1) `unsigned __int8` | mLastSortRenderChunkGeometryVersion
12 | (4) `float` | mAverageBrightness
16 | (16) `std::shared_ptr<RenderChunkShared>` | mRenderChunkShared
32 | (16) `std::shared_ptr<RenderChunkGeometry>` | mCurrentRenderChunkGeometry
48 | (24) `std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >` | mCurrentIndices
72 | (8) `std::unique_ptr<std::array<RangeIndices,18>>` | mCurrentIndexRanges
80 | (16) `std::shared_ptr<RenderChunkGeometry>` | mSortingRenderChunkGeometry
96 | (16) `std::shared_ptr<RenderChunkGeometry>` | mNextRenderChunkGeometry
112 | (24) `std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >` | mNextIndices
136 | (8) `std::unique_ptr<std::array<RangeIndices,18>>` | mNextIndexRanges
144 | (12) `glm::tvec3<int,0>` | mLastSortCameraDelta
156 | (12) `glm::tvec3<int,0>` | mCurrentIndexBufferCameraDelta
168 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mGuaranteedPromoteTime
176 | (16) `std::weak_ptr<mce::BufferResourceService>` | mBufferResourceService


### `RenderChunkSorter`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | mRawIndexBytes
24 | (112) `std::array<RangeIndices,14>` | mSortedLayers
136 | (112) `std::array<RangeIndices,14>` | mLayers
248 | (24) `std::vector<RenderChunkSorter::FaceInfo>` | mFaceInfo
272 | (4) `unsigned int` | mIndexSize
276 | (12) `glm::tvec3<int,0>` | mCameraDelta
288 | (16) `std::shared_ptr<RenderChunkSorterSharedInfo>` | mSharedInfo
304 | (1) `bool` | mForceDisableCulling


### `RetryDelay`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDelayMs
4 | (4) `int` | mMaxDelayMs
8 | (4) `int` | mRetryCount
12 | (4) `int` | mPreviousTriggerMs
16 | (1) `bool` | mActive
17 | (1) `bool` | mEnabled
18 | (1) `bool` | mNoDelay


### `ResourceLoaderLocationExpander`
Offset | Type | Name
-|-|-|-
0 | (8) `IResourceLocationExpander` | baseclass_0
8 | (8) `const ResourceLoader *` | mResourceLoader


### `ResourceLocationPair`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | mResourceLocation
56 | (136) `PackIdVersion` | mPackId
192 | (4) `int` | mPackPosition


### `RawInputScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | id
4 | (1) `RawInputType` | keyType
5 | (1) `ButtonState` | state
6 | (1) `bool` | allowRemapping


### `RenderChunkRenderQueueParameters`
Offset | Type | Name
-|-|-|-
0 | (8) `const TerrainLayer *` | mTerrainLayer
8 | (8) `const std::vector<mce::ServerTexture> *` | mTextures
16 | (2) `const unsigned __int16` | mInstanceCount


### `RopeAABB`
Offset | Type | Name
-|-|-|-
0 | (28) `AABB` | mBB
28 | (1) `bool` | mDenyListed


### `ResourcePackCopyProgressHandler::onStart::__l2::<lambda_d96584963d966b1b2f694c214afd8640>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *` | minecraftScreenModel
8 | (24) `const std::vector<PackInstance>` | resourcePackStack
32 | (24) `const std::vector<PackInstance>` | behaviorPackStack
56 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | worldPath
1096 | (16) `std::shared_ptr<std::promise<void> >` | promise


### `ResourceSignature`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,std::string>` | mSignatureFileContents


### `RealmsPurchaseDetails`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | foundPayload
4 | (4) `RealmsOfferTier` | offerTier
8 | (32) `std::string` | productSku
40 | (32) `std::string` | originalXuid
72 | (32) `std::string` | originalWorldName
104 | (32) `std::string` | originalSubscriptionId
136 | (16) `std::weak_ptr<Purchase>` | purchase


### `RealmsCreateScreenController::_verifyAppStoreReady::__l10::<lambda_a9a82af7daade8e888113d0905d8b9e8>::()::__l2::<lambda_7bbfac4acde520e62dcdb5f5174dc939>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsCreateScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | readyCallback


### `RealmsCreateScreenController::_promptPrepareAppStore::__l2::<lambda_f91a03e943035590cb0def0c73cd449a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback


### `RealmsStoreOffer`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mPrice
8 | (32) `std::string` | mProductId
40 | (32) `std::string` | mSalesDocId


### `RealmsCreateScreenController::_promptForCoinsPurchaseFulfillment::__l2::<lambda_19594e823628c853cfd91f333e3e6917>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsCreateScreenController>` | weakThis
16 | (72) `RealmsStoreOffer` | realmsStoreOffer


### `Realms::SubscriptionInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `Realms::SubscriptionInfo::PurchaseType` | purchaseType
8 | (32) `std::string` | id
40 | (32) `std::string` | storeId
72 | (4) `int` | renewalPeriod
76 | (4) `int` | daysLeft


### `RealmsPlusPDPScreenController::_getRealmSubscriptionFromWorld::__l2::<lambda_47ea2d851de30b3b20023f023d182025>`
Offset | Type | Name
-|-|-|-
0 | (8) `Realms::RealmId` | realmId
8 | (16) `std::weak_ptr<RealmsPlusPDPScreenController>` | weakThis


### `RealmsSettingsScreenController::_updateWorld::__l2::<lambda_171cf9e84184033586cecc5fe1a1d0c1>::()::__l5::<lambda_87a6a684392dd938b2301e6a1aa7a585>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (24) `std::vector<std::string>` | allXuids
40 | (24) `std::vector<std::string>` | blockList


### `RealmsSettingsScreenController::_saveSettings::__l8::<lambda_5835d7f80d46f0f2012ffe2740db5e4d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | actionAfterSave


### `RealmsSettingsScreenController::_saveSettings::__l8::<lambda_5835d7f80d46f0f2012ffe2740db5e4d>::()::__l5::<lambda_80f517ed39e6e005aef8071f0428f0d6>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | actionAfterSave


### `RealmsSettingsScreenController::_applyPacks::__l8::<lambda_61191b8658ecd12074656f8fe5f60426>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(std::vector<Realms::Content>)>` | applyContentAction
80 | (24) `std::vector<PackContentItem *>` | selectedContent


### `Realms::Content`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | type
8 | (32) `std::string` | contentId
40 | (32) `std::string` | parentPackId


### `RealmsSettingsScreenController::_addContentToBeAppliedAndUploadIfNeeded::__l31::<lambda_2b270bcc608b43c1b68344f25db856b1>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (16) `std::shared_ptr<std::vector<Realms::Content> >` | contentToApply
32 | (32) `Core::PathBuffer<std::string >` | contentPath
64 | (1) `_BYTE[1]` | contentPackType
72 | (32) `std::string` | contentId
104 | (24) `std::vector<PackContentItem *>` | contentToUpload
128 | (4) `int` | index
136 | (64) `std::function<void __cdecl(std::vector<Realms::Content>)>` | completeUploadCallback
200 | (64) `std::function<void __cdecl(std::vector<PackContentItem *>,int)>` | failedUploadCallback


### `RealmsSettingsScreenController::_addContentToBeAppliedAndUploadIfNeeded::__l31::<lambda_2b270bcc608b43c1b68344f25db856b1>::()::__l10::<lambda_d0af041332319da85b8df0317b569e64>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (16) `std::shared_ptr<std::vector<Realms::Content> >` | contentToApply
32 | (1) `_BYTE[1]` | contentPackType
40 | (32) `std::string` | contentId
72 | (24) `std::vector<PackContentItem *>` | contentToUpload
96 | (4) `int` | index
104 | (64) `std::function<void __cdecl(std::vector<Realms::Content>)>` | completeUploadCallback
168 | (64) `std::function<void __cdecl(std::vector<PackContentItem *>,int)>` | failedUploadCallback


### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_843dae073ea86557239b208b1e8c37d9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (16) `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_fd3ade5acd31013d2ac4022ef1975c3c>` | progressScreenTickCallback
32 | (80) `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_c8677b5df21d203ed2364daaaae69e34>` | completedCallback
112 | (16) `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_f585f21c4e3e0ed09f0ca83ec317010c>` | progressScreenOnCancelCallback


### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_fd3ade5acd31013d2ac4022ef1975c3c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_c8677b5df21d203ed2364daaaae69e34>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | packApplyCallback


### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_f585f21c4e3e0ed09f0ca83ec317010c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_bdc441493f82719fda019cf5b35f47e9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (48) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_6f6d2264a14d664e267a21913c18593c>` | progressScreenTickCallback
64 | (16) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_63c1c7606b648a8dc2ea0f9d90b31639>` | completedCallback
80 | (16) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_ff7ea9bb12e7c65d2ee5ac36aa3d43b4>` | retryCallback
96 | (16) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_a1aec860c88407b4bb33eccf58e4b486>` | progressScreenOnCancelCallback


### `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_6f6d2264a14d664e267a21913c18593c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (16) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_63c1c7606b648a8dc2ea0f9d90b31639>` | completedCallback
32 | (16) `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_ff7ea9bb12e7c65d2ee5ac36aa3d43b4>` | retryCallback


### `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_63c1c7606b648a8dc2ea0f9d90b31639>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_ff7ea9bb12e7c65d2ee5ac36aa3d43b4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_resetRealm::__l2::<lambda_a1aec860c88407b4bb33eccf58e4b486>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_90f93503afcb2150f364e9799f89ed0c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (1) `bool` | isRequestToOpen
24 | (64) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_b71d30541d1b0e7712c9c0fe81f5c831>` | progressScreenTickCallback
88 | (16) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_891faa9bc01efec95ba1d04b372bca1e>` | progressScreenOnCancelCallback
104 | (24) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_7c914378f6e8cb75fbd63a0b27decab4>` | completedCallback
128 | (16) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_fbeb9486a735f4eed9eccef9c594350d>` | retryCallback


### `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_b71d30541d1b0e7712c9c0fe81f5c831>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (24) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_7c914378f6e8cb75fbd63a0b27decab4>` | completedCallback
40 | (16) `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_fbeb9486a735f4eed9eccef9c594350d>` | retryCallback
56 | (1) `bool` | isRequestToOpen


### `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_7c914378f6e8cb75fbd63a0b27decab4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (1) `bool` | isRequestToOpen


### `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_fbeb9486a735f4eed9eccef9c594350d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_openCloseRealm::__l2::<lambda_891faa9bc01efec95ba1d04b372bca1e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_5adb1e206583e30faad1b80412e5fcaf>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (80) `const Realms::Backup` | realmBackup
96 | (16) `RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_289f928b773cf1c3b7290561b1cf78a1>` | downloadFile


### `Realms::Backup`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | id
32 | (8) `__int64` | timestamp
40 | (8) `__int64` | worldSizeBytes
48 | (32) `std::string` | version


### `RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_289f928b773cf1c3b7290561b1cf78a1>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis


### `RealmsSettingsScreenController::_handleRealmBackupDownloadButtonClick::__l5::<lambda_c0ed1b3a441903df14dc6937b1f396b3>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (80) `const Realms::Backup` | realmBackup
96 | (8) `const __int64` | time


### `RealmsSettingsScreenController::_handleRealmBackupDownloadButtonClick::__l5::<lambda_c0ed1b3a441903df14dc6937b1f396b3>::()::__l5::<lambda_39edf9bcf95b2d1e730007042025a413>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsSettingsScreenController>` | weakThis
16 | (80) `const Realms::Backup` | realmBackup
96 | (8) `const __int64` | time


### `RealmsSettingsScreenController::_displayModalPopup::__l2::<lambda_75ea1a14d1c1a37dbf0107105d586bf3>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback


### `ResourcePacksScreenController::_launchPlatformLockedDialog::__l5::<lambda_251eb84df17d9be97deade058ed4f799>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ResourcePacksScreenController>` | weakThis
16 | (8) `ContentView *` | contentView
24 | (4) `int` | collectionIndex
28 | (4) `_BYTE[4]` | fromType
32 | (1) `bool` | moveDependencies
33 | (1) `bool` | forceMove
40 | (64) `std::function<void __cdecl(void)>` | moveCallback


### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b2fce6e6e34fd54c73ef0abd93d8e65a>`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePacksScreenController *const` | __this


### `ResourceMetadata`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mAuthors
24 | (32) `std::string` | mUrl
56 | (32) `std::string` | mLicense


### `ResourcePacksScreenController::_handleSelectedPackMoveClicked::__l25::<lambda_221c7c165bbd12366fc736ee34526b21>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ResourcePacksScreenController>` | weakThis
16 | (1008) `const PackManifest` | manifest
1024 | (8) `ContentView *` | contentView


### `ResourcePackStack`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackStack_vtbl *` | __vftable
8 | (24) `std::vector<PackInstance>` | mStack
32 | (8) `std::unique_ptr<PackSourceReport>` | mPackSourceReport


### `RealmsFileUploader::RealmUploadInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | worldId
32 | (32) `std::string` | token
64 | (32) `std::string` | uploadUrl
96 | (4) `int` | chunkSize
104 | (64) `RealmsFileUploader::UploadResultBuilder` | resultBuilder
168 | (4) `IFileChunkUploader::UploadStatus` | status
172 | (4) `IFileChunkUploader::UploadStreamResult` | result
176 | (32) `std::string` | cancelUrl
208 | (4) `float` | progress
212 | (1) `bool` | tryWriteStream
213 | (1) `bool` | tryReadStream
214 | (1) `bool` | receivedResponseEnd
216 | (24) `std::vector<unsigned char>` | dataCache
240 | (64) `std::function<bool __cdecl(unsigned __int64 &,std::vector<unsigned char> &)>` | fetchDataCallback
304 | (64) `std::function<void __cdecl(RealmsFileUploader::UploadResult)>` | eventCallback
368 | (64) `std::function<void __cdecl(void)>` | endCallback


### `RealmsFileUploader::UploadResultBuilder`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | eventLine
32 | (32) `std::string` | dataLine


### `ResourceInformation`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mDescription
32 | (112) `SemVersion` | mVersion
144 | (16) `mce::UUID` | mUUID
160 | (4) `ResourceInformation::ResourceType` | mType
168 | (32) `std::string` | mEntry


### `RealmsCreateParams`
Offset | Type | Name
-|-|-|-
0 | (4) `const RealmsPurchaseIntent` | mPurchaseIntent
8 | (32) `const std::string` | mWorldName
40 | (32) `const std::string` | mSubscriptionId
72 | (4) `const RealmsOfferTier` | mOfferTier
76 | (1) `const bool` | mExpired
77 | (1) `const bool` | mTrialAvailable
78 | (1) `const bool` | mHasClub
79 | (1) `const bool` | mIsRealmsPDP
80 | (64) `std::function<void __cdecl(Realms::World &)>` | mOnCreateCallback


### `RenderControlMetadata`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<UIControl>` | control
16 | (40) `BatchClippingState` | clippingState
56 | (8) `BatchVisualState` | visualState


### `ReadOnlyBinaryStream`
Offset | Type | Name
-|-|-|-
0 | (8) `ReadOnlyBinaryStream_vtbl *` | __vftable
8 | (8) `unsigned __int64` | mReadPointer
16 | (1) `bool` | mHasOverflowed
24 | (32) `const std::string` | mOwnedBuffer
56 | (8) `const std::string *` | mBuffer


### `ResourcePackDataInfoPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mResourceName
72 | (4) `unsigned int` | mChunkSize
76 | (4) `int` | mNbChunks
80 | (8) `unsigned __int64` | mFileSize
88 | (32) `std::string` | mFileHash
120 | (1) `_BYTE[1]` | mPackType
121 | (1) `bool` | mIsPremium


### `RealmsAPI::initializeRealmsUserEventHandler::__l2::<lambda_fa9eb312a75ee33babb6c8319da8da7d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAPI>` | weakThis
16 | (80) `RealmsAPI::initializeRealmsUserEventHandler::__l2::<lambda_b76fcd16b74697c64f8abe7e1fbd1833>` | trialCallback


### `RealmsAPI::initializeRealmsUserEventHandler::__l2::<lambda_b76fcd16b74697c64f8abe7e1fbd1833>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<RealmsAPI>` | weakThis
16 | (64) `std::function<std::shared_ptr<Social::User> __cdecl(void)>` | _getPrimaryUser


### `Realms::SubscriptionService::SubscriptionQuery`
Offset | Type | Name
-|-|-|-
0 | (8) `Realms::RealmId` | realmId
8 | (4) `unsigned int` | queryAttemptsMade
16 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | lastRefreshAttemptTime
24 | (8) `std::chrono::duration<__int64,std::ratio<1,1000> >` | timeBetweenAttempts
32 | (1) `bool` | queryInProgress
40 | (24) `std::vector<std::function<void __cdecl(enum Realms::SubscriptionService::SubscriptionQueryStatus,Realms::SubscriptionInfo)>>` | listeners


### `Realms::SubscriptionService::_performSubscriptionQuery::__l5::<lambda_6eeb4d705739d17df69ee46630d45e14>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Realms::SubscriptionService>` | weakThis
16 | (8) `Realms::RealmId` | realmId


### `Realms::SubscriptionService::CachedSubscription`
Offset | Type | Name
-|-|-|-
0 | (8) `Realms::RealmId` | realmId
8 | (80) `Realms::SubscriptionInfo` | subscriptionInfo
88 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | expirationTime


### `RemappingLayout`
Offset | Type | Name
-|-|-|-
0 | (8) `RemappingLayout_vtbl *` | __vftable
8 | (24) `std::vector<Keymapping>` | mKeymappings
32 | (24) `std::vector<Keymapping>` | mDefaultMappings


### `RemotePlayer::playEmote::__l18::<lambda_32ca8873dc8d58447c91938030c4f9b9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<bool>` | weakExistence
16 | (8) `PersonaRepository *` | personaRepository
24 | (32) `const std::string` | pieceId


### `RopeWave`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mForce
12 | (4) `float` | mSpeed
16 | (4) `float` | mDamping
24 | (8) `unsigned __int64` | mCurNode
32 | (4) `float` | mDistAlongNode
36 | (4) `RopeWave::Direction` | mDir


### `Range<int,-1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mIndex


### `RenderChunkBits`
Offset | Type | Name
-|-|-|-
0 | (736) `std::bitset<5832>` | mBits


### `RenderChunkCoordinator::DirtyChunkData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mImmediate
1 | (1) `bool` | mChangesVisibility
4 | (4) `std::bitset<6>` | mInterlockBitField


### `RenderChunkVisibilityBuilder`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAllDark
1 | (1) `bool` | mSkyLit
2 | (6) `VisibilityNode` | mVisibility
8 | (1) `bool` | mEmpty
16 | (8) `BlockSource *` | mSource


### `RenderChunkInstanced::createLayerRenderObject::__l2::<lambda_7625e103360d3e551555490519cd97c2>`
Offset | Type | Name
-|-|-|-


### `RenderChunkInstanced::createLayerRenderObject::__l2::<lambda_a9ff2fc524dc959b011c3f226a1ef25b>`
Offset | Type | Name
-|-|-|-


### `RenderChunkInstanced::promoteSortedGeometry::__l2::<lambda_5f8c4a4c624541123271290ae21b2013>`
Offset | Type | Name
-|-|-|-


### `RenderChunkInstanced::promoteSortedGeometry::__l2::<lambda_b559a75f772e7c4c981d41b43e1aabbe>`
Offset | Type | Name
-|-|-|-


### `RenderChunkInstanced::prefetchIndexBufferPtr::__l2::<lambda_e40dd031a90a08d6d5d2f9c21e88995c>`
Offset | Type | Name
-|-|-|-


### `RenderChunkInstanced::prefetchIndexBufferPtr::__l2::<lambda_8249f339d7b54daa285aa378ab1a26f3>`
Offset | Type | Name
-|-|-|-


### `RenderChunkShared::BlockActorBlockSyncMessageWithVersion`
Offset | Type | Name
-|-|-|-
0 | (16) `BlockActorBlockSyncMessage` | mBlockEntityBlockSyncMessage
16 | (1) `unsigned __int8` | mRenderChunkGeometryVersion


### `rendergraph::RenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseActorRenderContext *` | mEntityContext
8 | (8) `const FrameRenderObject *` | mFrameRenderObject


### `rendergraph::DeclarationInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `rendergraph::RenderOrder *` | mOwner


### `rendergraph::ResourceBinding`
Offset | Type | Name
-|-|-|-
0 | (4) `rendergraph::ResourceBinding::AccessType` | mAccessType
4 | (4) `rendergraph::ResourceBinding::ResourceType` | mResourceType
8 | (4) `rendergraph::ResourceBinding::ShaderStage` | mShaderStage
12 | (4) `int` | mIndex


### `rendergraph::FrameBufferBuilder`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<rendergraph::FrameBufferBuilder::Packet>` | mColorAttachmentCreations
24 | (16) `rendergraph::FrameBufferBuilder::Packet` | mDepthStencilAttachmentCreation


### `rendergraph::FrameBufferBuilder::Packet`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Texture *` | mAttachmentTexture
8 | (1) `unsigned __int8` | mMipLevel
9 | (1) `unsigned __int8` | mArrayIndex


### `rendergraph::PassBuilderInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `rendergraph::RenderOrder *` | mOwner
8 | (8) `rendergraph::Pass *` | mPass


### `ResourcePackMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackMergeStrategy_vtbl *` | __vftable


### `RealmsTransactionHandler::_checkReceiptFulfillment_WindowsOneStore::__l2::<lambda_6790c76a3f29e4af615f0784be2d3342>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsTransactionHandler *const` | __this
8 | (24) `const std::vector<std::weak_ptr<Purchase>>` | unknownPurchases


### `ReceiptData_Google`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPackageName
32 | (32) `std::string` | mPurchaseToken
64 | (32) `std::string` | mProductId


### `RealmsTransactionHandler::_checkReceiptFulfillment_GooglePlayStore::__l2::<lambda_4fafaee95a15d3a567fa229153ed742a>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsTransactionHandler *const` | __this
8 | (24) `const std::vector<std::weak_ptr<Purchase>>` | unknownPurchases


### `RealmsTransactionHandler::_checkReceiptFulfillment_AmazonAppStore::__l2::<lambda_e6db3824fe4812753fdb4658578d9e35>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsTransactionHandler *const` | __this
8 | (24) `const std::vector<std::weak_ptr<Purchase>>` | unknownPurchases


### `RealmsTransactionHandler::_checkReceiptFulfillment_iOSAppStore::__l2::<lambda_110fe8f5092e23faf87fb453e1367a4e>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsTransactionHandler *const` | __this
8 | (24) `const std::vector<std::weak_ptr<Purchase>>` | unknownPurchases


### `ReceiptData_ps4`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mEnvironment
8 | (32) `std::string` | mUserId
40 | (32) `std::string` | mAuthCode
72 | (32) `std::string` | mOfflineAuthCode
104 | (32) `std::string` | mRedirectUri
136 | (32) `std::string` | mServiceLabel


### `RealmsTransactionHandler::_checkReceiptFulfillment_ps4Store::__l2::<lambda_8daddbaa5ebef602c18ed584dd01d91c>`
Offset | Type | Name
-|-|-|-
0 | (8) `RealmsTransactionHandler *const` | __this
8 | (24) `const std::vector<std::weak_ptr<Purchase>>` | unknownPurchases


### `RegistryKey`
Offset | Type | Name
-|-|-|-
0 | (8) `HKEY__ *` | mHandle
8 | (4) `unsigned int` | mAccess


### `RECT`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | left
4 | (4) `int` | top
8 | (4) `int` | right
12 | (4) `int` | bottom


### `Renderers::InsertChunkLayer::__l14::<lambda_1c11bfcb28a4a2848ad13caa46ffc263>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::FrameBuilder *` | frameBuilder
8 | (8) `const std::vector<ChunkLayerRenderObject> *` | queue
16 | (8) `const ChunkRenderObjectCollection *` | chunkState
24 | (8) `__int64` | batchBegin
32 | (8) `__int64` | batchEnd
40 | (4) `const int` | direction
48 | (8) `const TerrainLayer *` | layer
56 | (8) `const std::vector<mce::ServerTexture> *` | layerTextures
64 | (24) `std::vector<unsigned char,mce::AlignmentHelper::AlignmentAllocator<unsigned char,16> >` | perFrameConstantsMemory
88 | (4) `const float` | renderchunkFadeInTime
92 | (2) `const dragon::frameobject::components::ViewSetId` | viewId
96 | (12) `glm::tvec3<float,0>` | targetPos
108 | (1) `bool` | showChunkMap


### `rapidjson::GenericMemberIterator<0,rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::GenericMember<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *` | ptr_


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >`
Offset | Type | Name
-|-|-|-
0 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Data` | data_


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Data`
Offset | Type | Name
-|-|-|-
0 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::String` | s
1 | (14) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ShortString` | _ss
2 | (8) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number` | n
3 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ObjectData` | o
4 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ArrayData` | a
5 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Flag` | f


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::String`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | length
4 | (4) `unsigned int` | hashcode
8 | (8) `const char *` | str


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ShortString`
Offset | Type | Name
-|-|-|-
0 | (14) `char[14]` | str


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number::I` | i
1 | (8) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number::U` | u
2 | (8) `__int64` | i64
3 | (8) `unsigned __int64` | u64
4 | (8) `long double` | d


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number::I`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | i
4 | (4) `char[4]` | padding


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Number::U`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | u
4 | (4) `char[4]` | padding2


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ObjectData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | size
4 | (4) `unsigned int` | capacity
8 | (8) `rapidjson::GenericMember<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *` | members


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ArrayData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | size
4 | (4) `unsigned int` | capacity
8 | (8) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *` | elements


### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::Flag`
Offset | Type | Name
-|-|-|-
0 | (14) `char[14]` | payload
14 | (2) `unsigned __int16` | flags


### `reflection::factory<ArmorItemComponent>`
Offset | Type | Name
-|-|-|-


### `rapidjson::GenericStringStream<rapidjson::UTF8<char> >`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | src_
8 | (8) `const char *` | head_


### `reflection::factory<CooldownItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<DyePowderItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<EntityPlacerItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<FuelItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<IconItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<KnockbackResistanceItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<OnUseItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<OnUseOnItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<PlanterItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<ProjectileItemComponent>`
Offset | Type | Name
-|-|-|-


### `RepairItemEntry`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ItemDescriptor>` | mItems
24 | (216) `ExpressionNode` | mRepairAmount
240 | (320) `DefinitionTrigger` | mOnRepaired


### `reflection::factory<ThrowableItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<WeaponItemComponent>`
Offset | Type | Name
-|-|-|-


### `reflection::factory<WearableItemComponent>`
Offset | Type | Name
-|-|-|-


### `RakNet::AddressOrGUID`
Offset | Type | Name
-|-|-|-
0 | (16) `RakNet::RakNetGUID` | rakNetGuid
16 | (136) `RakNet::SystemAddress` | systemAddress


### `Recipe`
Offset | Type | Name
-|-|-|-
0 | (8) `Recipe_vtbl *` | __vftable
8 | (32) `std::string` | mRecipeId
40 | (64) `ItemPack` | mMyItems
104 | (16) `mce::UUID` | mMyId
120 | (4) `int` | mWidth
124 | (4) `int` | mHeight
128 | (4) `int` | mPriority
132 | (4) `TypedServerNetId<RecipeNetIdTag,unsigned int,0>` | mRecipeNetId
136 | (24) `std::vector<RecipeIngredient>` | mMyIngredients
160 | (48) `HashedString` | mTag


### `RakNet::BitStream`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | numberOfBitsUsed
4 | (4) `unsigned int` | numberOfBitsAllocated
8 | (4) `unsigned int` | readOffset
16 | (8) `unsigned __int8 *` | data
24 | (1) `bool` | copyData
25 | (256) `unsigned __int8[256]` | stackData


### `RakNetInstance::PingCallbackData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mAddress
32 | (64) `std::function<void __cdecl(unsigned int)>` | mAction


### `RakNet::RakString`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakString::SharedString *` | sharedString


### `RakNet::SocketDescriptor`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | port
2 | (32) `char[32]` | hostAddress
34 | (2) `__int16` | socketFamily
36 | (2) `unsigned __int16` | remotePortRakNetWasStartedOn_PS3_PSP2
40 | (4) `int` | chromeInstance
44 | (1) `bool` | blockingSocket
48 | (4) `unsigned int` | extraSocketOptions


### `RaidBossComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Village>` | mVillage
16 | (8) `ActorUniqueID` | mOwnerID
24 | (32) `std::string` | mName
56 | (32) `std::string` | mProgress
88 | (4) `int` | mPlayersRegistered
92 | (1) `bool` | mWaveStarted
93 | (1) `bool` | mRaidInProgress
94 | (1) `bool` | mHealthBarVisible
96 | (4) `float` | mHealthPercent
100 | (28) `AABB` | mBossBarVisibleBounds
128 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mLastPlayerUpdate


### `ResourcePackManager::loadTextureAsync::__l2::<lambda_d648c6709fc7e9b003b9f23a71bf9694>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<std::shared_ptr<mce::Image> > >` | resultTask
16 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > >` | ioTask
32 | (56) `const ResourceLocation` | resourceLocation


### `ResourcePackManager::findAllTexturesInUse::__l16::<lambda_20abcbdebb5959da404419a98c2c5015>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unordered_map<ResourceLocation,std::pair<PackIdVersion,int>> *` | resourceLocations
8 | (8) `const mce::UUID *` | uuid
16 | (8) `const SemVersion *` | version
24 | (8) `std::vector<std::string> *` | textureSetLayers
32 | (8) `std::vector<std::string> *` | orphanedTextures
40 | (8) `const std::vector<std::string> *` | imageExtensions
48 | (4) `int` | index


### `ResourcePackRepository::KnownPackContainer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ResourcePackRepository::KnownPackInfo>` | mPacks


### `ResourcePackRepository::KnownPackInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mDiscoveredOnDisk
8 | (56) `ResourceLocation` | mResourceLocation
64 | (24) `std::vector<std::string>` | mPastHashes
88 | (136) `PackIdVersion` | mIdentity


### `ResolvedTextObject`
Offset | Type | Name
-|-|-|-
0 | (16) `const Json::Value` | mResolvedTextObjectJson


### `ResourcePackFileDownloaderManager::chunkReceived::__l5::<lambda_32b39bae93a8eaf436cc6bd68d71d7d7>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ResourcePackFileDownloaderManager>` | weak_this
16 | (24) `const FileChunkInfo` | chunkInfo
40 | (24) `const std::vector<unsigned char>` | data


### `ResourcePackFileUploadManager::_uploadResourcePackFolder::__l2::<lambda_5f2dbbb69b6702709f27fe51108f8156>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this
16 | (32) `const std::string` | resourcePack
48 | (56) `const ResourceLocation` | resourcePackLocation
104 | (32) `Core::PathBuffer<std::string >` | resourceZipPath
136 | (1) `bool` | hasClientData
144 | (16) `const Json::Value` | uploadOptions


### `ResourcePackFileUploadManager::_uploadResourcePackFolder::__l2::<lambda_5f2dbbb69b6702709f27fe51108f8156>::()::__l5::<lambda_f7032ed69da7612d4ac394703c48ab55>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this
16 | (32) `const std::string` | resourcePack
48 | (32) `Core::PathBuffer<std::string >` | resourceZipPath
80 | (16) `const Json::Value` | uploadOptions


### `ResourcePackFileUploadManager::_uploadPackToRealmStorage::__l13::<lambda_d92af86e17aab0123f091326a380549e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weakThis
16 | (32) `const std::string` | uploadId


### `ResourcePackFileUploadManager::_uploadPackToRealmStorage::__l13::<lambda_d92af86e17aab0123f091326a380549e>::()::__l8::<lambda_d3574ee4bb62746b42fd7d072130a453>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weakThis
16 | (32) `const std::string` | uploadId
48 | (40) `FileArchiver::Result` | result


### `RuntimeIdentifierDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (32) `std::string` | mRuntimeId


### `RecipeSearchResult`
Offset | Type | Name
-|-|-|-
0 | (8) `const Recipe *` | mRecipe
8 | (24) `std::vector<SearchInfo>` | mSearchList
32 | (24) `std::vector<RecipeIngredient>` | mIngredients
56 | (4) `int` | mCraftableCount


### `Recipes::Type`
Offset | Type | Name
-|-|-|-
0 | (8) `Item *` | mItem
8 | (8) `const Block *` | mBlock
16 | (88) `RecipeIngredient` | mIngredient
104 | (1) `char` | mC


### `Range<unsigned char,1>`
Offset | Type | Name
-|-|-|-
0 | (1) `const unsigned __int8` | mBeginIDX
1 | (1) `const unsigned __int8` | mEndIDX


### `Range<unsigned char,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mIndex


### `Recipes::FurnaceRecipeKey`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mID
8 | (48) `HashedString` | mTag


### `Recipes::NormalizedRectangularRecipeResults`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mWidth
4 | (4) `int` | mHeight
8 | (32) `std::string` | mNormalizedResult
40 | (32) `std::string` | mWarning


### `RopeNode`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (12) `Vec3` | mPrevPos
24 | (1) `char` | mFrictionAxis


### `rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator>`
Offset | Type | Name
-|-|-|-
0 | (16) `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >` | baseclass_0
16 | (8) `rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> *` | allocator_
24 | (8) `rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> *` | ownAllocator_
32 | (48) `rapidjson::internal::Stack<rapidjson::CrtAllocator>` | stack_
80 | (16) `rapidjson::ParseResult` | parseResult_


### `rapidjson::internal::Stack<rapidjson::CrtAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::CrtAllocator *` | allocator_
8 | (8) `rapidjson::CrtAllocator *` | ownAllocator_
16 | (8) `char *` | stack_
24 | (8) `char *` | stackTop_
32 | (8) `char *` | stackEnd_
40 | (8) `unsigned __int64` | initialCapacity_


### `rapidjson::ParseResult`
Offset | Type | Name
-|-|-|-
0 | (4) `rapidjson::ParseErrorCode` | code_
8 | (8) `unsigned __int64` | offset_


### `rendergraph::BindInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `rendergraph::RenderOrder *` | mOwner
8 | (8) `rendergraph::RenderContext *` | mRenderContext
16 | (8) `rendergraph::ResourceEvent *` | mResourceEvent
24 | (8) `optional_ref<rendergraph::FrameBufferBuilder>` | mFrameBufferBuilder


### `RestClient::Response`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | code
8 | (32) `std::string` | body
40 | (64) `std::unordered_map<std::string,std::string>` | headers
104 | (4) `HTTPResponse::Status` | status


### `rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream>`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::MemoryStream *` | is_
8 | (4) `rapidjson::UTFType` | type_
12 | (4) `unsigned int` | current_
16 | (8) `unsigned int (__fastcall *)(rapidjson::MemoryStream *)` | takeFunc_
24 | (1) `bool` | hasBOM_


### `rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>`
Offset | Type | Name
-|-|-|-
0 | (48) `rapidjson::internal::Stack<rapidjson::CrtAllocator>` | stack_
48 | (16) `rapidjson::ParseResult` | parseResult_
64 | (4) `rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::IterativeParsingState` | state_


### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::StackStream<char>`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::internal::Stack<rapidjson::CrtAllocator> *` | stack_
8 | (4) `unsigned int` | length_


### `RailActivatorSystem::tick::__l2::<lambda_15ae3a1350f7883c8ebb00e0aabbf4ab>`
Offset | Type | Name
-|-|-|-
0 | (8) `RailActivatorSystem *const` | __this


### `Range<unsigned int,1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | mBeginIDX
4 | (4) `const unsigned int` | mEndIDX


### `RawInputEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | id
4 | (1) `ButtonState` | state
5 | (1) `RawInputType` | keyType
6 | (1) `bool` | allowRemapping


### `RakNet::NetworkAdapter`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | attributeFlags
4 | (4) `int` | interfaceIndex
8 | (1) `bool` | isDisabled
16 | (2856) `RakNet::SystemAddress[21]` | addresses


### `RakNet::RNS2_SendParameters`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | data
8 | (4) `int` | length
16 | (136) `RakNet::SystemAddress` | systemAddress
152 | (4) `int` | ttl


### `RakNet::uint24_t`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | val


### `RakNet::ReliabilityLayer::DatagramHistoryNode`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::ReliabilityLayer::MessageNumberNode *` | head
8 | (8) `unsigned __int64` | timeSent


### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>`
Offset | Type | Name
-|-|-|-
0 | (48) `rapidjson::internal::Stack<rapidjson::CrtAllocator>` | stack_
48 | (16) `rapidjson::ParseResult` | parseResult_
64 | (4) `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::IterativeParsingState` | state_


### `rapidjson::BasicIStreamWrapper<std::basic_istream<char,std::char_traits<char> > >`
Offset | Type | Name
-|-|-|-
0 | (8) `std::istream *` | stream_
8 | (4) `char[4]` | peekBuffer_
16 | (8) `char *` | buffer_
24 | (8) `unsigned __int64` | bufferSize_
32 | (8) `char *` | bufferLast_
40 | (8) `char *` | current_
48 | (8) `unsigned __int64` | readCount_
56 | (8) `unsigned __int64` | count_
64 | (1) `bool` | eof_


### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::ClearStackOnExit`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator> *` | r_


### `rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator>::ClearStackOnExit`
Offset | Type | Name
-|-|-|-
0 | (8) `rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator> *` | d_


### `rapidjson::internal::StreamLocalCopy<rapidjson::GenericStringStream<rapidjson::UTF8<char> >,1>`
Offset | Type | Name
-|-|-|-
0 | (16) `rapidjson::GenericStringStream<rapidjson::UTF8<char> >` | s
16 | (8) `rapidjson::GenericStringStream<rapidjson::UTF8<char> > *` | original_


### `rangeobject`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | ob_refcnt
8 | (8) `_typeobject *` | ob_type
16 | (4) `int` | start
20 | (4) `int` | step
24 | (4) `int` | len


### `RenderController`
```
const struct __cppobj RenderController
{
  HashedString mName;
  std::unordered_map<HashedString,ExpressionNode> mArrays[3];
  ExpressionNode mGeometry;
  ExpressionNode mTintColor[4];
  ExpressionNode mOverlayColor[4];
  ExpressionNode mOnFireColor[4];
  ExpressionNode mIsHurtColor[4];
  ExpressionNode mUVAnim[4];
  std::vector<std::pair<std::string,ExpressionNode>> mPartVisibility;
  std::vector<std::pair<std::string,ExpressionNode>> mMaterials;
  std::vector<ExpressionNode> mTextures;
  bool mShouldRebuildAnimationMatrices;
  bool mIgnoreLighting;
  bool mFilterLighting;
  ExpressionNode mLightColorMultiplier;
};

```

### `RakNetInstance::ConnectionCallbacks`
```
struct __cppobj RakNetInstance::ConnectionCallbacks
{
  RakNetInstance::ConnectionCallbacks_vtbl *__vftable /*VFT*/;
};

```

### `RakNetInstance::ConnectionCallbacks_vtbl`
```
struct /*VFT*/ RakNetInstance::ConnectionCallbacks_vtbl
{
  void (__fastcall *~ConnectionCallbacks)(RakNetInstance::ConnectionCallbacks *this);
  void (__fastcall *onNewIncomingConnection)(RakNetInstance::ConnectionCallbacks *this, const NetworkIdentifier *, std::shared_ptr<NetworkPeer>);
  void (__fastcall *onNewOutgoingConnection)(RakNetInstance::ConnectionCallbacks *this, const NetworkIdentifier *, std::shared_ptr<NetworkPeer>);
  void (__fastcall *onConnectionClosed)(RakNetInstance::ConnectionCallbacks *this, const NetworkIdentifier *, const std::string *, bool);
  void (__fastcall *onAllConnectionsClosed)(RakNetInstance::ConnectionCallbacks *this, const std::string *, bool);
  void (__fastcall *onAllRemoteConnectionsClosed)(RakNetInstance::ConnectionCallbacks *this, const std::string *, bool);
  void (__fastcall *onOutgoingConnectionFailed)(RakNetInstance::ConnectionCallbacks *this);
  void (__fastcall *onWebsocketRequest)(RakNetInstance::ConnectionCallbacks *this, const std::string *, const std::string *, std::function<void __cdecl(void)>);
};

```

### `RakPeerHelper::IPSupportInterface`
```
struct __cppobj RakPeerHelper::IPSupportInterface
{
  RakPeerHelper::IPSupportInterface_vtbl *__vftable /*VFT*/;
};

```

### `RakPeerHelper::IPSupportInterface_vtbl`
```
struct /*VFT*/ RakPeerHelper::IPSupportInterface_vtbl
{
  void (__fastcall *~IPSupportInterface)(RakPeerHelper::IPSupportInterface *this);
  bool (__fastcall *useIPv4Only)(RakPeerHelper::IPSupportInterface *this);
  bool (__fastcall *useIPv6Only)(RakPeerHelper::IPSupportInterface *this);
  unsigned __int16 (__fastcall *getDefaultGamePort)(RakPeerHelper::IPSupportInterface *this);
  unsigned __int16 (__fastcall *getDefaultGamePortv6)(RakPeerHelper::IPSupportInterface *this);
};

```

### `RakNet::RakPeerInterface`
```
struct __cppobj RakNet::RakPeerInterface
{
  RakNet::RakPeerInterface_vtbl *__vftable /*VFT*/;
};

```

### `RakNet::PublicKey`
```
struct RakNet::PublicKey
{
  RakNet::PublicKeyMode publicKeyMode;
  char *remoteServerPublicKey;
  char *myPublicKey;
  char *myPrivateKey;
};

```

### `RakNet::RakNetSocket2`
```
struct __cppobj __declspec(align(8)) RakNet::RakNetSocket2
{
  RakNet::RakNetSocket2_vtbl *__vftable /*VFT*/;
  RakNet::RNS2EventHandler *eventHandler;
  RakNet::RNS2Type socketType;
  int socketProtocolType;
  RakNet::SystemAddress boundAddress;
  unsigned int userConnectionSocketIndex;
};

```

### `RakNet::RakNetSocket2_vtbl`
```
struct /*VFT*/ RakNet::RakNetSocket2_vtbl
{
  void (__fastcall *~RakNetSocket2)(RakNet::RakNetSocket2 *this);
  int (__fastcall *Send)(RakNet::RakNetSocket2 *this, RakNet::RNS2_SendParameters *, const char *, unsigned int);
  void (__fastcall *SetMulticastInterface)(RakNet::RakNetSocket2 *this, int);
};

```

### `RakNet::RNS2EventHandler`
```
struct __cppobj RakNet::RNS2EventHandler
{
  RakNet::RNS2EventHandler_vtbl *__vftable /*VFT*/;
};

```

### `RakNet::RNS2RecvStruct`
```
struct __cppobj RakNet::RNS2RecvStruct
{
  char data[1600];
  int bytesRead;
  RakNet::SystemAddress systemAddress;
  unsigned __int64 timeRead;
  RakNet::RakNetSocket2 *socket;
};

```

### `RakNet::RNS2EventHandler_vtbl`
```
struct /*VFT*/ RakNet::RNS2EventHandler_vtbl
{
  void (__fastcall *~RNS2EventHandler)(RakNet::RNS2EventHandler *this);
  void (__fastcall *OnRNS2Recv)(RakNet::RNS2EventHandler *this, RakNet::RNS2RecvStruct *);
  void (__fastcall *DeallocRNS2RecvStruct)(RakNet::RNS2EventHandler *this, RakNet::RNS2RecvStruct *, const char *, unsigned int);
  RakNet::RNS2RecvStruct *(__fastcall *AllocRNS2RecvStruct)(RakNet::RNS2EventHandler *this, const char *, unsigned int);
};

```

### `RakNet::Packet`
```
struct __cppobj __declspec(align(8)) RakNet::Packet
{
  RakNet::SystemAddress systemAddress;
  RakNet::RakNetGUID guid;
  unsigned int length;
  unsigned int bitSize;
  unsigned __int8 *data;
  bool deleteData;
  bool wasGeneratedLocally;
};

```

### `RakNet::PluginInterface2`
```
struct __cppobj RakNet::PluginInterface2
{
  RakNet::PluginInterface2_vtbl *__vftable /*VFT*/;
  RakNet::RakPeerInterface *rakPeerInterface;
  RakNet::TCPInterface *tcpInterface;
};

```

### `RakNet::InternalPacketFixedSizeTransmissionHeader`
```
struct __cppobj RakNet::InternalPacketFixedSizeTransmissionHeader
{
  RakNet::uint24_t reliableMessageNumber;
  RakNet::uint24_t orderingIndex;
  RakNet::uint24_t sequencingIndex;
  unsigned __int8 orderingChannel;
  unsigned __int16 splitPacketId;
  unsigned int splitPacketIndex;
  unsigned int splitPacketCount;
  unsigned int dataBitLength;
  PacketReliability reliability;
};

```

### `RakNet::InternalPacketRefCountedData`
```
struct __declspec(align(8)) RakNet::InternalPacketRefCountedData
{
  unsigned __int8 *sharedDataBlock;
  unsigned int refCount;
};

```

### `RakNet::InternalPacket`
```
struct __cppobj RakNet::InternalPacket : RakNet::InternalPacketFixedSizeTransmissionHeader
{
  RakNet::uint24_t messageInternalOrder;
  bool messageNumberAssigned;
  unsigned __int64 creationTime;
  unsigned __int64 nextActionTime;
  unsigned __int64 retransmissionTime;
  unsigned int headerLength;
  unsigned __int8 *data;
  _BYTE allocationScheme[4];
  RakNet::InternalPacketRefCountedData *refCountedData;
  unsigned __int8 timesSent;
  PacketPriority priority;
  unsigned int sendReceiptSerial;
  RakNet::InternalPacket *resendPrev;
  RakNet::InternalPacket *resendNext;
  RakNet::InternalPacket *unreliablePrev;
  RakNet::InternalPacket *unreliableNext;
  unsigned __int8 stackData[128];
};

```

### `RakNet::PluginInterface2_vtbl`
```
struct /*VFT*/ RakNet::PluginInterface2_vtbl
{
  void (__fastcall *~PluginInterface2)(RakNet::PluginInterface2 *this);
  void (__fastcall *OnAttach)(RakNet::PluginInterface2 *this);
  void (__fastcall *OnDetach)(RakNet::PluginInterface2 *this);
  void (__fastcall *Update)(RakNet::PluginInterface2 *this);
  RakNet::PluginReceiveResult (__fastcall *OnReceive)(RakNet::PluginInterface2 *this, RakNet::Packet *);
  void (__fastcall *OnRakPeerStartup)(RakNet::PluginInterface2 *this);
  void (__fastcall *OnRakPeerShutdown)(RakNet::PluginInterface2 *this);
  void (__fastcall *OnClosedConnection)(RakNet::PluginInterface2 *this, const RakNet::SystemAddress *, RakNet::RakNetGUID, RakNet::PI2_LostConnectionReason);
  void (__fastcall *OnNewConnection)(RakNet::PluginInterface2 *this, const RakNet::SystemAddress *, RakNet::RakNetGUID, bool);
  void (__fastcall *OnFailedConnectionAttempt)(RakNet::PluginInterface2 *this, RakNet::Packet *, RakNet::PI2_FailedConnectionAttemptReason);
  bool (__fastcall *UsesReliabilityLayer)(RakNet::PluginInterface2 *this);
  void (__fastcall *OnDirectSocketSend)(RakNet::PluginInterface2 *this, const char *, const unsigned int, RakNet::SystemAddress);
  void (__fastcall *OnDirectSocketReceive)(RakNet::PluginInterface2 *this, const char *, const unsigned int, RakNet::SystemAddress);
  void (__fastcall *OnReliabilityLayerNotification)(RakNet::PluginInterface2 *this, const char *, const unsigned int, RakNet::SystemAddress, bool);
  void (__fastcall *OnInternalPacket)(RakNet::PluginInterface2 *this, RakNet::InternalPacket *, unsigned int, RakNet::SystemAddress, unsigned int, int);
  void (__fastcall *OnAck)(RakNet::PluginInterface2 *this, unsigned int, RakNet::SystemAddress, unsigned int);
  void (__fastcall *OnPushBackPacket)(RakNet::PluginInterface2 *this, const char *, const unsigned int, RakNet::SystemAddress);
};

```

### `RakNet::TCPInterface_vtbl`
```
struct /*VFT*/ RakNet::TCPInterface_vtbl
{
  void (__fastcall *~TCPInterface)(RakNet::TCPInterface *this);
  void (__fastcall *Send)(RakNet::TCPInterface *this, const char *, unsigned int, const RakNet::SystemAddress *, bool);
  bool (__fastcall *SendList)(RakNet::TCPInterface *this, const char **, const unsigned int *, const int, const RakNet::SystemAddress *, bool);
  bool (__fastcall *ReceiveHasPackets)(RakNet::TCPInterface *this);
  RakNet::Packet *(__fastcall *Receive)(RakNet::TCPInterface *this);
  void (__fastcall *PushBackPacket)(RakNet::TCPInterface *this, RakNet::Packet *, bool);
};

```

### `RakNet::RemoteClient`
```
struct __cppobj RakNet::RemoteClient
{
  unsigned __int64 socket;
  RakNet::SystemAddress systemAddress;
  DataStructures::ByteQueue outgoingData;
  bool isActive;
  RakNet::SimpleMutex outgoingDataMutex;
  RakNet::SimpleMutex isActiveMutex;
};

```

### `RakNet::RakPeerInterface_vtbl`
```
struct /*VFT*/ RakNet::RakPeerInterface_vtbl
{
  void (__fastcall *~RakPeerInterface)(RakNet::RakPeerInterface *this);
  RakNet::StartupResult (__fastcall *Startup)(RakNet::RakPeerInterface *this, unsigned int, RakNet::SocketDescriptor *, unsigned int, int);
  bool (__fastcall *InitializeSecurity)(RakNet::RakPeerInterface *this, const char *, const char *, bool);
  void (__fastcall *DisableSecurity)(RakNet::RakPeerInterface *this);
  void (__fastcall *AddToSecurityExceptionList)(RakNet::RakPeerInterface *this, const char *);
  void (__fastcall *RemoveFromSecurityExceptionList)(RakNet::RakPeerInterface *this, const char *);
  bool (__fastcall *IsInSecurityExceptionList)(RakNet::RakPeerInterface *this, const char *);
  void (__fastcall *SetMaximumIncomingConnections)(RakNet::RakPeerInterface *this, unsigned __int16);
  unsigned int (__fastcall *GetMaximumIncomingConnections)(RakNet::RakPeerInterface *this);
  unsigned __int16 (__fastcall *NumberOfConnections)(RakNet::RakPeerInterface *this);
  void (__fastcall *SetIncomingPassword)(RakNet::RakPeerInterface *this, const char *, int);
  void (__fastcall *GetIncomingPassword)(RakNet::RakPeerInterface *this, char *, int *);
  RakNet::ConnectionAttemptResult (__fastcall *Connect)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, const char *, int, RakNet::PublicKey *, unsigned int, unsigned int, unsigned int, unsigned int);
  RakNet::ConnectionAttemptResult (__fastcall *ConnectWithSocket)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, const char *, int, RakNet::RakNetSocket2 *, RakNet::PublicKey *, unsigned int, unsigned int, unsigned int);
  void (__fastcall *Shutdown)(RakNet::RakPeerInterface *this, unsigned int, unsigned __int8, PacketPriority);
  bool (__fastcall *IsActive)(RakNet::RakPeerInterface *this);
  bool (__fastcall *GetConnectionList)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *, unsigned __int16 *);
  unsigned int (__fastcall *GetNextSendReceipt)(RakNet::RakPeerInterface *this);
  unsigned int (__fastcall *IncrementNextSendReceipt)(RakNet::RakPeerInterface *this);
  unsigned int (__fastcall *Send)(RakNet::RakPeerInterface *this, const RakNet::BitStream *, PacketPriority, PacketReliability, char, const RakNet::AddressOrGUID, bool, unsigned int);
  unsigned int (__fastcall *Send)(RakNet::RakPeerInterface *this, const char *, const int, PacketPriority, PacketReliability, char, const RakNet::AddressOrGUID, bool, unsigned int);
  void (__fastcall *SendLoopback)(RakNet::RakPeerInterface *this, const char *, const int);
  unsigned int (__fastcall *SendList)(RakNet::RakPeerInterface *this, const char **, const int *, const int, PacketPriority, PacketReliability, char, const RakNet::AddressOrGUID, bool, unsigned int);
  RakNet::Packet *(__fastcall *Receive)(RakNet::RakPeerInterface *this);
  void (__fastcall *DeallocatePacket)(RakNet::RakPeerInterface *this, RakNet::Packet *);
  unsigned int (__fastcall *GetMaximumNumberOfPeers)(RakNet::RakPeerInterface *this);
  void (__fastcall *CloseConnection)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID, bool, unsigned __int8, PacketPriority);
  RakNet::ConnectionState (__fastcall *GetConnectionState)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID);
  void (__fastcall *CancelConnectionAttempt)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  int (__fastcall *GetIndexFromSystemAddress)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  RakNet::SystemAddress *(__fastcall *GetSystemAddressFromIndex)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *result, unsigned int);
  RakNet::RakNetGUID *(__fastcall *GetGUIDFromIndex)(RakNet::RakPeerInterface *this, RakNet::RakNetGUID *result, unsigned int);
  void (__fastcall *GetSystemList)(RakNet::RakPeerInterface *this, DataStructures::List<RakNet::SystemAddress> *, DataStructures::List<RakNet::RakNetGUID> *);
  void (__fastcall *AddToBanList)(RakNet::RakPeerInterface *this, const char *, unsigned int);
  void (__fastcall *RemoveFromBanList)(RakNet::RakPeerInterface *this, const char *);
  void (__fastcall *ClearBanList)(RakNet::RakPeerInterface *this);
  bool (__fastcall *IsBanned)(RakNet::RakPeerInterface *this, const char *);
  void (__fastcall *SetLimitIPConnectionFrequency)(RakNet::RakPeerInterface *this, bool);
  bool (__fastcall *Ping)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, bool, unsigned int);
  void (__fastcall *Ping)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  void (__fastcall *SendNatTraversalMessage)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  int (__fastcall *GetAveragePing)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID);
  int (__fastcall *GetLastPing)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID);
  int (__fastcall *GetLowestPing)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID);
  void (__fastcall *SetOccasionalPing)(RakNet::RakPeerInterface *this, bool);
  unsigned __int64 (__fastcall *GetClockDifferential)(RakNet::RakPeerInterface *this, const RakNet::AddressOrGUID);
  void (__fastcall *SetOfflinePingResponse)(RakNet::RakPeerInterface *this, const char *, const unsigned int);
  void (__fastcall *GetOfflinePingResponse)(RakNet::RakPeerInterface *this, char **, unsigned int *);
  RakNet::SystemAddress *(__fastcall *GetInternalID)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *result, const RakNet::SystemAddress, const int);
  void (__fastcall *SetInternalID)(RakNet::RakPeerInterface *this, RakNet::SystemAddress, int);
  RakNet::SystemAddress *(__fastcall *GetExternalID)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *result, const RakNet::SystemAddress);
  const RakNet::RakNetGUID *(__fastcall *GetMyGUID)(RakNet::RakPeerInterface *this, const RakNet::RakNetGUID *result);
  void (__fastcall *resetMyGUID)(RakNet::RakPeerInterface *this);
  RakNet::SystemAddress *(__fastcall *GetMyBoundAddress)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *result, const int);
  const RakNet::RakNetGUID *(__fastcall *GetGuidFromSystemAddress)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  RakNet::SystemAddress *(__fastcall *GetSystemAddressFromGuid)(RakNet::RakPeerInterface *this, RakNet::SystemAddress *result, const RakNet::RakNetGUID);
  bool (__fastcall *GetClientPublicKeyFromSystemAddress)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress, char *);
  void (__fastcall *SetTimeoutTime)(RakNet::RakPeerInterface *this, unsigned int, const RakNet::SystemAddress);
  unsigned int (__fastcall *GetTimeoutTime)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  int (__fastcall *GetMTUSize)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  unsigned int (__fastcall *GetNumberOfAdapters)(RakNet::RakPeerInterface *this);
  RakNet::NetworkAdapter *(__fastcall *GetLocalAdapter)(RakNet::RakPeerInterface *this, unsigned int);
  unsigned int (__fastcall *GetNumberOfAddresses)(RakNet::RakPeerInterface *this);
  const char *(__fastcall *GetLocalIP)(RakNet::RakPeerInterface *this, unsigned int);
  bool (__fastcall *IsLocalIP)(RakNet::RakPeerInterface *this, const char *);
  void (__fastcall *AllowConnectionResponseIPMigration)(RakNet::RakPeerInterface *this, bool);
  bool (__fastcall *AdvertiseSystem)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, const char *, int, unsigned int);
  void (__fastcall *SetSplitMessageProgressInterval)(RakNet::RakPeerInterface *this, int);
  int (__fastcall *GetSplitMessageProgressInterval)(RakNet::RakPeerInterface *this);
  void (__fastcall *SetUnreliableTimeout)(RakNet::RakPeerInterface *this, unsigned int);
  void (__fastcall *SendTTL)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, int, unsigned int);
  void (__fastcall *AttachPlugin)(RakNet::RakPeerInterface *this, RakNet::PluginInterface2 *);
  void (__fastcall *DetachPlugin)(RakNet::RakPeerInterface *this, RakNet::PluginInterface2 *);
  void (__fastcall *PushBackPacket)(RakNet::RakPeerInterface *this, RakNet::Packet *, bool);
  void (__fastcall *ChangeSystemAddress)(RakNet::RakPeerInterface *this, RakNet::RakNetGUID, const RakNet::SystemAddress *);
  RakNet::Packet *(__fastcall *AllocatePacket)(RakNet::RakPeerInterface *this, unsigned int);
  RakNet::RakNetSocket2 *(__fastcall *GetSocket)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress);
  void (__fastcall *GetSockets)(RakNet::RakPeerInterface *this, DataStructures::List<RakNet::RakNetSocket2 *> *);
  void (__fastcall *ReleaseSockets)(RakNet::RakPeerInterface *this, DataStructures::List<RakNet::RakNetSocket2 *> *);
  void (__fastcall *WriteOutOfBandHeader)(RakNet::RakPeerInterface *this, RakNet::BitStream *);
  void (__fastcall *SetUserUpdateThread)(RakNet::RakPeerInterface *this, void (__fastcall *)(RakNet::RakPeerInterface *, void *), void *);
  void (__fastcall *SetIncomingDatagramEventHandler)(RakNet::RakPeerInterface *this, bool (__fastcall *)(RakNet::RNS2RecvStruct *));
  void (__fastcall *ApplyNetworkSimulator)(RakNet::RakPeerInterface *this, float, unsigned __int16, unsigned __int16);
  void (__fastcall *SetPerConnectionOutgoingBandwidthLimit)(RakNet::RakPeerInterface *this, unsigned int);
  bool (__fastcall *IsNetworkSimulatorActive)(RakNet::RakPeerInterface *this);
  bool (__fastcall *GetStatistics)(RakNet::RakPeerInterface *this, const unsigned int, RakNet::RakNetStatistics *);
  RakNet::RakNetStatistics *(__fastcall *GetStatistics)(RakNet::RakPeerInterface *this, const RakNet::SystemAddress, RakNet::RakNetStatistics *);
  void (__fastcall *GetStatisticsList)(RakNet::RakPeerInterface *this, DataStructures::List<RakNet::SystemAddress> *, DataStructures::List<RakNet::RakNetGUID> *, DataStructures::List<RakNet::RakNetStatistics> *);
  unsigned int (__fastcall *GetReceiveBufferSize)(RakNet::RakPeerInterface *this);
  bool (__fastcall *RunUpdateCycle)(RakNet::RakPeerInterface *this, RakNet::BitStream *);
  bool (__fastcall *SendOutOfBand)(RakNet::RakPeerInterface *this, const char *, unsigned __int16, const char *, unsigned int, unsigned int);
};

```

### `RakNetInstance::AtomicNatPunchInfo`
```
struct __cppobj RakNetInstance::AtomicNatPunchInfo
{
  Connector::NatPunchInfo mInfo;
  std::shared_mutex mMutex;
};

```

### `RakNetInstance::NatConnectionInfo`
```
struct __cppobj __declspec(align(8)) RakNetInstance::NatConnectionInfo
{
  RakNet::SystemAddress remoteAddress;
  unsigned int lastNatPingSendTime;
  unsigned int natPingSendCount;
  bool pongReceived;
};

```

### `RakPeerHelper`
```
struct __cppobj RakPeerHelper
{
  RakNet::StartupResult mResult;
  int mConnectionIndices[2];
  unsigned __int16 mBoundPorts[2];
  RakPeerHelper::IPSupportInterface *mIPSupportInterface;
};

```

### `RakNetNetworkPeer`
```
struct __cppobj RakNetNetworkPeer : NetworkPeer
{
  RakNet::RakPeerInterface *mRakPeer;
  NetworkIdentifier mId;
  std::string mSendBuffer;
  std::string mSendBufferOrigin;
  std::queue<std::string> mReadBuffers;
  int mApproximateMaxBps;
  int mLastPing;
  int mAveragePing;
  std::shared_mutex mMutex;
  std::shared_mutex mSendBufferMutex;
  std::vector<std::tuple<std::string,enum NetworkPeer::Reliability,int>> mSendPacketVec;
  bool mCacheSend;
  int mBatchSendTick;
};

```

### `RakNetNetworkPeer_vtbl`
```
struct /*VFT*/ RakNetNetworkPeer_vtbl
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

### `RakNetInstance`
```
struct __cppobj RakNetInstance : Connector, NetworkSuspendResumeListener
{
  RakNetInstance::ConnectionCallbacks *mCallbacks;
  NetworkIdentifier mNATPunchServerId;
  Social::GameConnectionInfo mBackupGameConnection;
  bool mTryBackupConnection;
  std::unique_ptr<RakNet::RakPeerInterface,void (__cdecl*)(RakNet::RakPeerInterface *)> mRakPeer;
  NetworkIdentifier mServerId;
  RakNetInstance::AtomicNatPunchInfo mNatPunchInfo;
  RakNetInstance::NATState mNatState;
  std::vector<RakNetInstance::NatConnectionInfo> mNatList;
  RakPeerHelper mPeerHelper;
  RakPeerHelper::IPSupportInterface *mIPSupportInterface;
  bool mIsAwaitingNatClient;
  bool mIsServer;
  bool mIsDisconnecting;
  bool mConnectingToClient;
  Social::GameConnectionInfo mConnectedGameInfo;
  std::unordered_map<NetworkIdentifier,std::weak_ptr<RakNetNetworkPeer>> mPeers;
  std::vector<Connector::ConnectionStateListener *> mConnectionStateListeners;
  bool mWasHostWhenSuspended;
  ConnectionDefinition mPreviousConnectionDefinition;
  std::string mResolvedIP;
  std::vector<RakNetInstance::PingCallbackData> mPingTimeCallbacks;
  std::unique_ptr<MPMCQueue<std::function<void __cdecl(void)> >> mOwnedThreadWork;
};

```

### `RakNetInstance_vtbl`
```
struct /*VFT*/ RakNetInstance_vtbl
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

### `RakNetServerLocator::PingRateRecorder`
```
struct __cppobj __declspec(align(8)) RakNetServerLocator::PingRateRecorder
{
  std::vector<unsigned __int64> mPingTimes;
  unsigned int mAveragingWindowSize;
  float mAverageTime;
  float mLastPingTime;
  unsigned int mStartTime;
  unsigned int mPingTimesIndex;
  int mIpVersion;
  bool mPingStarted;
  bool mAveraging;
};

```

### `RakNetServerLocator::NatHolePuncherFunctor`
```
struct __cppobj RakNetServerLocator::NatHolePuncherFunctor
{
  bool mSucceeded;
};

```

### `RakNetServerLocator::AnnounceServerData`
```
struct __cppobj __declspec(align(4)) RakNetServerLocator::AnnounceServerData
{
  std::string mPlayerName;
  std::string mWorldName;
  GameType mGameType;
  int mNumPlayers;
  int mMaxNumPlayers;
  bool mIsJoinableThroughServerScreen;
};

```

### `RakNetServerLocator::SuspendStateData`
```
struct __cppobj __declspec(align(8)) RakNetServerLocator::SuspendStateData
{
  RakNetServerLocator::AnnounceServerData mAnnounceServerData;
  bool mAnnoucedServer;
  bool mIsPingingForServers;
  int mPingPort;
  int mPingPortv6;
};

```

### `RakNetServerLocator`
```
struct __cppobj RakNetServerLocator : ServerLocator
{
  std::unordered_map<std::string,std::string> mOriginalAddresses;
  std::unordered_map<std::string,RakNetServerLocator::PingRateRecorder> mPingTimeRecorders;
  std::unordered_map<std::string,std::string> mGuidCache;
  std::function<RakNet::RakNetGUID __cdecl(void)> mGetHostGUID;
  RakNetInstance *mRaknetInstance;
  std::unique_ptr<RakNet::RakPeerInterface,void (__cdecl*)(RakNet::RakPeerInterface *)> mFinderPeer;
  RakPeerHelper mFinderPeerHelper;
  std::vector<PingedCompatibleServer> mAvailableServers;
  bool mIsPingingForServers;
  const bool mIsServer;
  int mPingPort;
  int mPingPortv6;
  unsigned int mLastPingTime;
  unsigned int mLastHolePunchTime;
  std::vector<std::string> mBroadcastAddresses;
  std::vector<std::string> mMulticastAddressesV6;
  std::queue<std::pair<AsynchronousIPResolver,int>> mPingQueue;
  RakNetServerLocator::NatHolePuncherFunctor mHolePuncher;
  bool mAnnouncedServer;
  std::function<void __cdecl(bool)> mServerValidationCallback;
  std::string mServerWaitingToValidate;
  unsigned int mLastPingToServerWaitingToValidateTime;
  std::recursive_mutex mServerListLock;
  std::recursive_mutex mFinderPeerLock;
  RakNetServerLocator::SuspendStateData mSuspendStateData;
};

```

### `RakNetServerLocator_vtbl`
```
struct /*VFT*/ RakNetServerLocator_vtbl
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

### `ReadOnlyBinaryStream_vtbl`
```
struct /*VFT*/ ReadOnlyBinaryStream_vtbl
{
  void (__fastcall *~ReadOnlyBinaryStream)(ReadOnlyBinaryStream *this);
  bool (__fastcall *read)(ReadOnlyBinaryStream *this, void *, unsigned __int64);
};

```

### `ResourcePackClientResponsePacket`
```
const struct __cppobj __declspec(align(8)) ResourcePackClientResponsePacket : Packet
{
  std::set<std::string> mDownloadingPacks;
  ResourcePackResponse mResponse;
};

```

### `ResourcePackClientResponsePacket_vtbl`
```
struct /*VFT*/ ResourcePackClientResponsePacket_vtbl
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

### `RespawnPacket`
```
const struct __cppobj RespawnPacket : Packet
{
  Vec3 mPos;
  PlayerRespawnState mState;
  ActorRuntimeID mRuntimeId;
};

```

### `RespawnPacket_vtbl`
```
struct /*VFT*/ RespawnPacket_vtbl
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

### `RemoveObjectivePacket`
```
const struct __cppobj RemoveObjectivePacket : Packet
{
  std::string mObjectiveName;
};

```

### `RemoveObjectivePacket_vtbl`
```
struct /*VFT*/ RemoveObjectivePacket_vtbl
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

### `ResourcePackChunkRequestPacket`
```
const struct __cppobj __declspec(align(8)) ResourcePackChunkRequestPacket : Packet
{
  std::string mResourceName;
  int mChunk;
};

```

### `ResourcePackChunkRequestPacket_vtbl`
```
struct /*VFT*/ ResourcePackChunkRequestPacket_vtbl
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

### `ResourcePackChunkDataPacket`
```
const struct __cppobj ResourcePackChunkDataPacket : Packet
{
  std::string mResourceName;
  int mChunkID;
  unsigned __int64 mByteOffset;
  std::vector<unsigned char> mData;
};

```

### `ResourcePackChunkDataPacket_vtbl`
```
struct /*VFT*/ ResourcePackChunkDataPacket_vtbl
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

### `ResourcePackDataInfoPacket_vtbl`
```
struct /*VFT*/ ResourcePackDataInfoPacket_vtbl
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

### `RequestChunkRadiusPacket`
```
const struct __cppobj __declspec(align(8)) RequestChunkRadiusPacket : Packet
{
  int mChunkRadius;
};

```

### `RequestChunkRadiusPacket_vtbl`
```
struct /*VFT*/ RequestChunkRadiusPacket_vtbl
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

### `Recipe_vtbl`
```
struct /*VFT*/ Recipe_vtbl
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

### `RiderJumpPacket`
```
const struct __cppobj __declspec(align(8)) RiderJumpPacket : Packet
{
  int mJumpScale;
};

```

### `RiderJumpPacket_vtbl`
```
struct /*VFT*/ RiderJumpPacket_vtbl
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

### `RemoveEntityPacket`
```
const struct __cppobj RemoveEntityPacket : EntityServerPacket
{
};

```

### `RemoveEntityPacket_vtbl`
```
struct /*VFT*/ RemoveEntityPacket_vtbl
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

### `RemoveActorPacket`
```
const struct __cppobj RemoveActorPacket : Packet
{
  ActorUniqueID mEntityId;
};

```

### `RemoveActorPacket_vtbl`
```
struct /*VFT*/ RemoveActorPacket_vtbl
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

### `ResourcePackStackPacket_vtbl`
```
struct /*VFT*/ ResourcePackStackPacket_vtbl
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

### `ResourcePackInfoData`
```
struct __cppobj __declspec(align(8)) ResourcePackInfoData
{
  PackIdVersion mPackIdVersion;
  unsigned __int64 mPackSize;
  std::string mContentKey;
  std::string mSubpackName;
  ContentIdentity mContentIdentity;
  bool mHasScripts;
  bool mIsRayTracingCapable;
  bool mHasExceptions;
};

```

### `ResourcePacksInfoData`
```
struct __cppobj ResourcePacksInfoData
{
  bool mTexturePackRequired;
  bool mHasScripts;
  bool mHasExceptions;
  std::vector<ResourcePackInfoData> mAddOnPacks;
  std::vector<ResourcePackInfoData> mTexturePacks;
};

```

### `ResourcePacksInfoPacket`
```
const struct __cppobj ResourcePacksInfoPacket : Packet
{
  ResourcePacksInfoData mData;
};

```

### `ResourcePacksInfoPacket_vtbl`
```
struct /*VFT*/ ResourcePacksInfoPacket_vtbl
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

### `ResourcePackFileDownloaderManager`
```
struct __cppobj ResourcePackFileDownloaderManager : std::enable_shared_from_this<ResourcePackFileDownloaderManager>
{
  ResourcePackFileDownloaderManager_vtbl *__vftable /*VFT*/;
  PacketSender *mPacketSender;
  std::string mResourceName;
  std::string mFileHash;
  bool mChunkWriteSuccess;
  Core::PathBuffer<std::string > mZipFilePath;
  Core::PathBuffer<std::string > mResourcePath;
  FileChunkManager mChunkManager;
  std::function<void __cdecl(bool,Core::Path const &)> mCompletionCallback;
  std::function<void __cdecl(float)> mProgressCallback;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  TaskGroup *mIOTaskGroup;
};

```

### `ResourcePackFileDownloaderManager_vtbl`
```
struct /*VFT*/ ResourcePackFileDownloaderManager_vtbl
{
  void (__fastcall *~ResourcePackFileDownloaderManager)(ResourcePackFileDownloaderManager *this);
};

```

### `ResourcePack`
```
struct __cppobj ResourcePack
{
  bool mHidden;
  bool mError;
  Pack *mPack;
  std::unique_ptr<PackAccessStrategy> mSubpackAccessStrategy;
  PackReport mPackReport;
  std::vector<std::unique_ptr<Pack>> mSubPacks;
  std::vector<std::unique_ptr<ResourcePack>> mSubResourcePacks;
  Core::PathBuffer<std::string > mIconPath;
  long double mLoadTime;
  bool mIsBaseGamePack;
  bool mIsSlicePack;
  ResourceSignature mResourceSignature;
};

```

### `RemappingLayout_vtbl`
```
struct /*VFT*/ RemappingLayout_vtbl
{
  void (__fastcall *~RemappingLayout)(RemappingLayout *this);
  void (__fastcall *setMappingWithRawInput)(RemappingLayout *this, const std::string *, int, RawInputType);
  int (__fastcall *getAdjustedKey)(RemappingLayout *this, int);
  std::string *(__fastcall *getSaveString)(RemappingLayout *this, std::string *result, const std::string *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int, bool);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, int);
  int (__fastcall *_rawKeyToKey)(RemappingLayout *this, int, RawInputType);
};

```

### `RequestTelemetry`
```
struct __cppobj RequestTelemetry
{
  unsigned __int16 mStatusCode;
  long double mStartTime;
  long double mEndTime;
};

```

### `ResourceLoader`
```
struct __cppobj ResourceLoader : Bedrock::EnableNonOwnerReferences
{
  ResourceLoader_vtbl *__vftable /*VFT*/;
  std::function<Core::PathBuffer<std::string > __cdecl(void)> mGetPath;
};

```

### `ResourcePackListener_vtbl`
```
struct /*VFT*/ ResourcePackListener_vtbl
{
  void (__fastcall *~ResourcePackListener)(ResourcePackListener *this);
  void (__fastcall *onActiveResourcePacksChanged)(ResourcePackListener *this, ResourcePackManager *);
  void (__fastcall *onFullPackStackInvalid)(ResourcePackListener *this);
  void (__fastcall *onBaseGamePackDownloadComplete)(ResourcePackListener *this);
  void (__fastcall *onLanguageSubpacksChanged)(ResourcePackListener *this);
  void (__fastcall *onResourceManagerDestroyed)(ResourcePackListener *this, ResourcePackManager *);
};

```

### `ResourcePackMergeStrategy_vtbl`
```
struct /*VFT*/ ResourcePackMergeStrategy_vtbl
{
  void (__fastcall *~ResourcePackMergeStrategy)(ResourcePackMergeStrategy *this);
  void (__fastcall *mergeFiles)(ResourcePackMergeStrategy *this, const std::vector<LoadedResourceData> *);
};

```

### `ResourcePackStack_vtbl`
```
struct /*VFT*/ ResourcePackStack_vtbl
{
  void (__fastcall *~ResourcePackStack)(ResourcePackStack *this);
  bool (__fastcall *loadAllVersionsOf)(ResourcePackStack *this, const ResourceLocation *, ResourcePackMergeStrategy *);
  std::vector<ResourcePath> *(__fastcall *loadAllVersionsOf)(ResourcePackStack *this, std::vector<ResourcePath> *result, const ResourceLocation *);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *(__fastcall *loadAllVersionsOfAsync)(ResourcePackStack *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > *result, const ResourceLocation *, std::shared_ptr<ResourcePackMergeStrategy>);
};

```

### `rapidjson::GenericMember<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >`
```
struct __cppobj rapidjson::GenericMember<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >
{
  rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > name;
  rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > value;
};

```

### `rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>::ChunkHeader`
```
struct rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>::ChunkHeader
{
  unsigned __int64 capacity;
  unsigned __int64 size;
  rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>::ChunkHeader *next;
};

```

### `rapidjson::CrtAllocator`
```
struct __cppobj rapidjson::CrtAllocator
{
};

```

### `rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>`
```
struct __cppobj rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>
{
  rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>::ChunkHeader *chunkHead_;
  unsigned __int64 chunk_capacity_;
  void *userBuffer_;
  rapidjson::CrtAllocator *baseAllocator_;
  rapidjson::CrtAllocator *ownBaseAllocator_;
};

```

### `RakWebSocket`
```
struct __cppobj __declspec(align(8)) RakWebSocket
{
  RakWebSocket_vtbl *__vftable /*VFT*/;
  std::unique_ptr<TcpProxy> mTcpProxy;
  RakNet::SystemAddress mServerConnection;
  RakNet::BitStream mIncomingData;
  std::string mLastErrorResponse;
  CloseStatusCode mLastCloseCode;
  bool mClosedOnError;
  unsigned int mMaxFrameSize;
  RakWebSocketDataFrameParser mDataFrameParser;
  std::string mActiveSubProtocol;
  std::function<void __cdecl(RakWebSocketDataFrame const &)> mMessageReceivedHandler;
  std::function<void __cdecl(enum CloseStatusCode,std::string const &)> mCloseHandler;
  std::function<void __cdecl(std::string const &)> mConnectedHandler;
  std::string mUri;
  std::string mScheme;
  std::string mDomain;
  std::string mDomainNoPort;
  std::string mResource;
  unsigned __int16 mPort;
  bool mIsSecure;
  std::string mBase64Key;
  std::string mOpenHandshakeRequest;
  std::string mHandshakeCode;
  HttpHeaders mHandshakeFields;
  std::unique_ptr<AsyncTracker> mAsyncTracker;
  std::vector<std::string> mSubProtocols;
  RakWebSocket::ConnectionState mConnectionState;
};

```

### `RakWebSocketDataFrameHeader`
```
struct __cppobj RakWebSocketDataFrameHeader
{
  unsigned __int8 mHeaderByte0;
  unsigned __int8 mHeaderByte1;
};

```

### `RakWebSocketDataFrame`
```
const struct __cppobj RakWebSocketDataFrame
{
  RakWebSocketDataFrameHeader mHeader;
  RakNet::BitStream mPayload;
  unsigned __int64 mPayloadLength;
  unsigned int mMaskedKey;
  unsigned __int16 mCloseStatus;
  unsigned __int8 mBytesForPayloadLength;
  unsigned __int8 mBytesForMaskedKey;
  unsigned __int8 mBytesForStatusCode;
  RakWebSocketDataFrame::ParseState mParseState;
};

```

### `RakWebSocket_vtbl`
```
struct /*VFT*/ RakWebSocket_vtbl
{
  void (__fastcall *~RakWebSocket)(RakWebSocket *this);
  WSConnectionResult (__fastcall *connect)(RakWebSocket *this, const std::string *);
  WSConnectionResult (__fastcall *connect)(RakWebSocket *this, const std::string *, const std::vector<std::string> *);
  void (__fastcall *setOnMessageReceivedHandler)(RakWebSocket *this, const std::function<void __cdecl(RakWebSocketDataFrame const &)> *);
  void (__fastcall *setOnCloseHandler)(RakWebSocket *this, const std::function<void __cdecl(enum CloseStatusCode,std::string const &)> *);
  void (__fastcall *setOnConnectedHandler)(RakWebSocket *this, const std::function<void __cdecl(std::string const &)> *);
  void (__fastcall *tick)(RakWebSocket *this);
  void (__fastcall *_updateState)(RakWebSocket *this);
  unsigned int (__fastcall *_genMaskingKey)(RakWebSocket *this);
};

```

### `RakWebSocketDataFrameParser`
```
struct __cppobj RakWebSocketDataFrameParser
{
  std::shared_ptr<RakWebSocketDataFrame> mFragmentedFramePtr;
  std::shared_ptr<RakWebSocketDataFrame> mFramePtr;
  std::function<void __cdecl(std::string const &,enum CloseStatusCode)> mOnFailHandler;
  bool mParsingServerFrame;
  unsigned int mMaskingIndexOffset;
};

```

### `RakWebSocketClient`
```
struct __cppobj RakWebSocketClient : RakWebSocket
{
};

```

### `RakWebSocketClient_vtbl`
```
struct /*VFT*/ RakWebSocketClient_vtbl
{
  void (__fastcall *~RakWebSocket)(RakWebSocket *this);
  WSConnectionResult (__fastcall *connect)(RakWebSocket *this, const std::string *);
  WSConnectionResult (__fastcall *connect)(RakWebSocket *this, const std::string *, const std::vector<std::string> *);
  void (__fastcall *setOnMessageReceivedHandler)(RakWebSocket *this, const std::function<void __cdecl(RakWebSocketDataFrame const &)> *);
  void (__fastcall *setOnCloseHandler)(RakWebSocket *this, const std::function<void __cdecl(enum CloseStatusCode,std::string const &)> *);
  void (__fastcall *setOnConnectedHandler)(RakWebSocket *this, const std::function<void __cdecl(std::string const &)> *);
  void (__fastcall *tick)(RakWebSocket *this);
  void (__fastcall *_updateState)(RakWebSocket *this);
  unsigned int (__fastcall *_genMaskingKey)(RakWebSocket *this);
};

```

### `RoleCheckerCallback`
```
struct __cppobj RoleCheckerCallback
{
  std::function<void __cdecl(enum ADRole,std::string const &,std::string const &)> mCallback;
};

```

### `RoleChecker`
```
struct __cppobj RoleChecker
{
  std::weak_ptr<RoleCheckerCallback> mPendingCallback;
};

```

### `ResourceLoadManager::TaskGroupState`
```
struct __cppobj ResourceLoadManager::TaskGroupState
{
  bool mRunning;
  unsigned __int64 mPaused;
};

```

### `ResourceLoadManager::ResourceLoadTaskGroup`
```
struct __cppobj __declspec(align(8)) ResourceLoadManager::ResourceLoadTaskGroup
{
  _BYTE mLoadType[4];
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::vector<enum ResourceLoadType> mDependencies;
  ResourceLoadManager::TaskGroupState mTaskGroupState;
  bool mTaskGroupPaused;
};

```

### `ResourceLoadManager`
```
struct __cppobj ResourceLoadManager : Bedrock::EnableNonOwnerReferences
{
  int mRepeatedHitcountHACK;
  Scheduler *mScheduler;
  WorkerPool *mWorkerPool;
  std::map<enum ResourceLoadType,std::unique_ptr<ResourceLoadManager::ResourceLoadTaskGroup>> mResourceLoadTaskGroups;
  unsigned __int64 mAppSuspended;
};

```

### `RequestHandler`
```
struct __cppobj __declspec(align(8)) RequestHandler : std::enable_shared_from_this<RequestHandler>
{
  RequestHandler_vtbl *__vftable /*VFT*/;
  const ServiceClient *mOwner;
  unsigned int mConcurrencyId;
  unsigned int mMaxConcurrent;
  unsigned int mLogId;
  std::chrono::duration<__int64,std::ratio<1,1> > mRequestTimeLimit;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mRequestStartTime;
  bool mNetworkAllowed;
  bool mWorkComplete;
  __declspec(align(4)) _BYTE mPreferWaitForSignIn[4];
  _BYTE mPriority[4];
};

```

### `RequestHandler_vtbl`
```
struct /*VFT*/ RequestHandler_vtbl
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

### `RealmsUnknownPackSource`
```
struct __cppobj RealmsUnknownPackSource : PackSource
{
  _BYTE mPackType[1];
  PackOrigin mPackOrigin;
  std::vector<std::unique_ptr<Pack>> mPacks;
  PackSourceReport mReport;
};

```

### `RealmsUnknownPackSource_vtbl`
```
struct /*VFT*/ RealmsUnknownPackSource_vtbl
{
  void (__fastcall *~PackSource)(PackSource *this);
  void (__fastcall *forEachPackConst)(PackSource *this, std::function<void __cdecl(Pack const &)>);
  void (__fastcall *forEachPack)(PackSource *this, std::function<void __cdecl(Pack &)>);
  PackOrigin (__fastcall *getPackOrigin)(PackSource *this);
  PackType (__fastcall *getPackType)(PackSource *this);
  PackSourceReport *(__fastcall *load)(PackSource *this, PackSourceReport *result, PackManifestFactory *, const IContentKeyProvider *);
  void (__fastcall *addPackSource)(PackSource *this, PackSource *);
};

```

### `ReviewData`
```
struct __cppobj __declspec(align(8)) ReviewData
{
  std::string mTitle;
  std::string mReviewText;
  std::string mItemVersion;
  std::string mReviewId;
  std::string mItemId;
  std::string mGamerTag;
  std::string mLocale;
  std::string mSubmitted;
  unsigned __int64 mXuid;
  int mRating;
  int mHelpfulnessVotes;
  int mHelpfulPositive;
  int mHelpfulNegative;
  bool mIsInstalled;
};

```

### `ReviewSummaryData`
```
struct __cppobj ReviewSummaryData
{
  std::string mItemId;
  float mAverageRating;
  int mTotalRatingsCount;
  int mReviewsCount;
  int mStar5Count;
  int mStar4Count;
  int mStar3Count;
  int mStar2Count;
  int mStar1Count;
  ReviewData mMostFavorable;
  ReviewData mMostCritical;
};

```

### `RecentlyViewedComponent`
```
struct __cppobj RecentlyViewedComponent : StoreUIComponent
{
};

```

### `RecentlyViewedComponent_vtbl`
```
struct /*VFT*/ RecentlyViewedComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `RealmsPlusSection`
```
struct __cppobj RealmsPlusSection
{
  RealmsPlusSectionType mSectionType;
  std::string mSectionText;
  std::string mImageId;
};

```

### `RealmsPlusComponent`
```
struct __cppobj __declspec(align(8)) RealmsPlusComponent : StoreUIComponent
{
  std::vector<RealmsPlusSection> mContentTabSection;
  std::shared_ptr<SearchQuery> mViewPacksQuery;
  int mExpirationTimerDays;
};

```

### `RealmsPlusComponent_vtbl`
```
struct /*VFT*/ RealmsPlusComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `Realms::IContentApi`
```
struct __cppobj Realms::IContentApi
{
  Realms::IContentApi_vtbl *__vftable /*VFT*/;
};

```

### `Realms::IContentApi_vtbl`
```
struct /*VFT*/ Realms::IContentApi_vtbl
{
  void (__fastcall *~IContentApi)(Realms::IContentApi *this);
  void (__fastcall *applyContentOnRealm)(Realms::IContentApi *this, const Realms::RealmId, const std::vector<Realms::Content> *, std::function<void __cdecl(enum Realms::GenericStatus)>);
  void (__fastcall *fetchAppliedPacks)(Realms::IContentApi *this, const Realms::RealmId, std::function<void __cdecl(enum Realms::GenericStatus,std::vector<Realms::Content>)>);
  void (__fastcall *checkForExistingPack)(Realms::IContentApi *this, const std::string *, const std::string *, std::function<void __cdecl(enum Realms::GenericStatus,bool)>);
};

```

### `Realms::ISubscriptionApi`
```
struct __cppobj Realms::ISubscriptionApi
{
  Realms::ISubscriptionApi_vtbl *__vftable /*VFT*/;
};

```

### `Realms::ISubscriptionApi_vtbl`
```
struct /*VFT*/ Realms::ISubscriptionApi_vtbl
{
  void (__fastcall *~ISubscriptionApi)(Realms::ISubscriptionApi *this);
  void (__fastcall *getSubscriptionDetails)(Realms::ISubscriptionApi *this, Realms::RealmId, std::function<void __cdecl(enum Realms::GenericStatus,Realms::SubscriptionInfo)>);
};

```

### `Realms::GenericRequestServiceHandler`
```
struct __cppobj Realms::GenericRequestServiceHandler : ServiceClient
{
};

```

### `Realms::GenericRequestServiceHandler_vtbl`
```
struct /*VFT*/ Realms::GenericRequestServiceHandler_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `RealmsAPI`
```
struct __cppobj RealmsAPI : Realms::IContentApi, Realms::ISubscriptionApi, std::enable_shared_from_this<RealmsAPI>
{
  bool mFeatureFlagsFetched;
  __declspec(align(4)) RetryDelay mFeatureFlagRetry;
  bool mInitialized;
  std::weak_ptr<Realms::GenericRequestServiceHandler> mGenericRequestServiceClient;
  Realms::GenericStatus mCompatibilityStatus;
  RealmsAPI::Compatibility mCompatibility;
  bool mCompatibilityCheckCompleted;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mStatusUpdateTime;
  std::shared_ptr<MPMCQueue<std::function<void __cdecl(void)> > > mExecutionQueue;
  std::string mRealmsEndpoint;
  std::string mRelyingParty;
  std::weak_ptr<Options> mWeakOptions;
  Bedrock::PubSub::ScopedSubscription mRealmsOptionSubscription;
  std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionFlow)> _broadcastConnectionEventRealmsRequest;
  std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionFlow,unsigned short)> _broadcastConnectionEventRealmsResponse;
  bool mRealmsTrialAvailable;
  std::mutex mXBLSignInMutex;
};

```

### `RealmsAPI_vtbl`
```
struct /*VFT*/ RealmsAPI_vtbl
{
  void (__fastcall *~IContentApi)(Realms::IContentApi *this);
  void (__fastcall *applyContentOnRealm)(Realms::IContentApi *this, const Realms::RealmId, const std::vector<Realms::Content> *, std::function<void __cdecl(enum Realms::GenericStatus)>);
  void (__fastcall *fetchAppliedPacks)(Realms::IContentApi *this, const Realms::RealmId, std::function<void __cdecl(enum Realms::GenericStatus,std::vector<Realms::Content>)>);
  void (__fastcall *checkForExistingPack)(Realms::IContentApi *this, const std::string *, const std::string *, std::function<void __cdecl(enum Realms::GenericStatus,bool)>);
};

```

### `Realms::ContentService`
```
struct __cppobj Realms::ContentService
{
  std::weak_ptr<Realms::IContentApi> mContentApi;
};

```

### `RenderableComponent`
```
struct __cppobj __declspec(align(8)) RenderableComponent : UIComponent
{
  float mPropagatedAlpha;
};

```

### `RenderableComponent_vtbl`
```
struct /*VFT*/ RenderableComponent_vtbl
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

### `RenderChunkDirectIndexData`
```
struct __cppobj __declspec(align(8)) RenderChunkDirectIndexData
{
  const std::optional<dragon::RenderMetadata> mRenderMetadata;
  std::optional<mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler> > mIndexData;
  int mIterationCount;
};

```

### `RenderChunkDirectVertexData`
```
struct __cppobj RenderChunkDirectVertexData
{
  const std::optional<dragon::RenderMetadata> mRenderMetadata;
  std::optional<mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler> > mVertexData;
  unsigned __int64 mVertexCount;
};

```

### `RecentFocusVector`
```
struct __cppobj __declspec(align(4)) RecentFocusVector
{
  std::vector<std::weak_ptr<UIControl>> mRecentControlVector;
  int mNextInsert;
  bool mIncludeMagnetControls;
};

```

### `rendergraph::Pass`
```
const struct __cppobj rendergraph::Pass
{
  rendergraph::Pass_vtbl *__vftable /*VFT*/;
};

```

### `rendergraph::Pass_vtbl`
```
struct /*VFT*/ rendergraph::Pass_vtbl
{
  void (__fastcall *~Pass)(rendergraph::Pass *this);
  void (__fastcall *execute)(rendergraph::Pass *this, rendergraph::RenderContext *);
};

```

### `rendergraph::Resource`
```
const struct __cppobj rendergraph::Resource
{
  rendergraph::Resource_vtbl *__vftable /*VFT*/;
};

```

### `rendergraph::ResourceViewInterface`
```
const struct __cppobj rendergraph::ResourceViewInterface
{
  rendergraph::ResourceViewInterface_vtbl *__vftable /*VFT*/;
};

```

### `rendergraph::RenderOrder`
```
struct __cppobj rendergraph::RenderOrder
{
  rendergraph::RenderOrder *mOwner;
  rendergraph::RenderOrder::PassStorage mPassStorage;
  rendergraph::RenderOrder::ResourceStorage mResourceStorage;
  rendergraph::RenderOrder::PassRegistry mPassRegistry;
  rendergraph::RenderOrder::ResourceEventRegistry mResourceEventRegistry;
};

```

### `rendergraph::RenderOrder::PassStorage`
```
struct __cppobj rendergraph::RenderOrder::PassStorage
{
  std::vector<std::shared_ptr<rendergraph::Pass>> mPasses;
  std::vector<rendergraph::Pass *> mLinkedPasses;
};

```

### `rendergraph::RenderOrder::ResourceStorage`
```
struct __cppobj rendergraph::RenderOrder::ResourceStorage
{
  std::vector<std::shared_ptr<rendergraph::Resource>> mResources;
  std::unordered_map<std::string,rendergraph::Resource *> mNamedResources;
};

```

### `rendergraph::RenderOrder::PassRegistry::FrameBufferTextureBinding`
```
struct __cppobj __declspec(align(4)) rendergraph::RenderOrder::PassRegistry::FrameBufferTextureBinding
{
  int mResourceEventIndex;
  unsigned __int8 mMipLevel;
  unsigned __int8 mArrayIndex;
};

```

### `rendergraph::RenderOrder::PassRegistry::PassAttributes`
```
struct __cppobj rendergraph::RenderOrder::PassRegistry::PassAttributes
{
  std::string mName;
  std::vector<int> mResourceEventIndices;
  rendergraph::PassBuilderInterface::ClearTarget mClearTarget;
  mce::Color mClearColor;
  mce::FrameBufferDescription mFrameBufferDescription;
  rendergraph::RenderOrder::PassRegistry::FrameBufferRequirement mFrameBufferRequirement;
  std::map<rendergraph::Resource *,rendergraph::RenderOrder::PassRegistry::FrameBufferTextureBinding> mFrameBufferTextureBindings;
  std::multimap<mce::TextureDescription,rendergraph::Resource *> mReferencedTransientTextures;
};

```

### `rendergraph::RenderOrder::PassRegistry`
```
struct __cppobj rendergraph::RenderOrder::PassRegistry
{
  std::unordered_map<rendergraph::Pass const *,rendergraph::RenderOrder::PassRegistry::PassAttributes> mPassAttributes;
};

```

### `rendergraph::ResourceEvent`
```
struct __cppobj __declspec(align(8)) rendergraph::ResourceEvent
{
  rendergraph::Resource *mResource;
  optional_ref<rendergraph::Pass> mPass;
  rendergraph::ResourceBinding mBinding;
  int mNextEventIndex;
};

```

### `rendergraph::RenderOrder::ResourceEventRegistry`
```
struct __cppobj rendergraph::RenderOrder::ResourceEventRegistry
{
  std::vector<rendergraph::ResourceEvent> mResourceEventList;
  std::unordered_map<rendergraph::Resource *,std::pair<int,int>> mResourceLifetimes;
};

```

### `rendergraph::LinkInterface`
```
struct __cppobj rendergraph::LinkInterface
{
  rendergraph::RenderOrder *mOwner;
  int mResourceEventIndex;
  rendergraph::ResourceEvent *mResourceEvent;
};

```

### `rendergraph::ResourceViewInterface_vtbl`
```
struct /*VFT*/ rendergraph::ResourceViewInterface_vtbl
{
  void (__fastcall *~ResourceViewInterface)(rendergraph::ResourceViewInterface *this);
  rendergraph::ValidationResult (__fastcall *linkResourceView)(rendergraph::ResourceViewInterface *this, rendergraph::LinkInterface *);
  void (__fastcall *bindResourceView)(rendergraph::ResourceViewInterface *this, rendergraph::BindInterface *);
};

```

### `rendergraph::ResourceTargetInterface`
```
const struct __cppobj rendergraph::ResourceTargetInterface
{
  rendergraph::ResourceTargetInterface_vtbl *__vftable /*VFT*/;
};

```

### `rendergraph::ResourceTargetInterface_vtbl`
```
struct /*VFT*/ rendergraph::ResourceTargetInterface_vtbl
{
  void (__fastcall *~ResourceTargetInterface)(rendergraph::ResourceTargetInterface *this);
  rendergraph::ValidationResult (__fastcall *linkResourceTarget)(rendergraph::ResourceTargetInterface *this, rendergraph::LinkInterface *);
  void (__fastcall *bindResourceTarget)(rendergraph::ResourceTargetInterface *this, rendergraph::BindInterface *);
};

```

### `rendergraph::APIResourcePool`
```
struct __cppobj rendergraph::APIResourcePool
{
  mce::RenderContext *mRawRenderContext;
  std::unordered_map<rendergraph::Pass const *,std::unique_ptr<mce::FrameBufferObject>> mLinkedFrameBuffers;
  std::vector<std::unique_ptr<mce::Texture>> mTransientTexturePool;
  std::map<mce::TextureDescription,std::vector<mce::Texture *>> mFreeTransientTextures;
  std::unordered_map<rendergraph::Resource const *,mce::Texture *> mLinkedTransientTextures;
};

```

### `rendergraph::Resource_vtbl`
```
struct /*VFT*/ rendergraph::Resource_vtbl
{
  void (__fastcall *~Resource)(rendergraph::Resource *this);
  optional_ref<rendergraph::ResourceViewInterface const > *(__fastcall *getViewInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceViewInterface const > *result);
  optional_ref<rendergraph::ResourceTargetInterface const > *(__fastcall *getTargetInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceTargetInterface const > *result);
  rendergraph::ValidationResult (__fastcall *acquireAPIResources)(rendergraph::Resource *this, rendergraph::APIResourcePool *);
  rendergraph::ValidationResult (__fastcall *enterRenderScope)(rendergraph::Resource *this);
  rendergraph::ValidationResult (__fastcall *exitRenderScope)(rendergraph::Resource *this);
  void (__fastcall *bind)(rendergraph::Resource *this, rendergraph::BindInterface *);
  rendergraph::ResourceBinding::ResourceType (__fastcall *getBindingType)(rendergraph::Resource *this);
};

```

### `RenderChunkQuadInfo`
```
struct __cppobj RenderChunkQuadInfo
{
  unsigned __int32 index : 31;
  unsigned __int32 reverse : 1;
  Vec3 centroid;
};

```

### `RenderChunkGeometry`
```
struct __cppobj RenderChunkGeometry
{
  float mAverageSkyLight;
  bool mImmediateChange;
  bool mBlendCanRenderAsOpaque;
  Tick mLastChangeTick;
  Tick mFirstChangeTick;
  std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> > mMeshData;
  bool mCanRender;
  bool mBuilt;
  bool mRayTracingModeOnAtBuildStart;
  bool mRayTracingModeOnAtBuildEnd;
  long double mReadyTime;
  int mBuildIterationCount;
  BlockPos mPosition;
  BlockPos mCenter;
  Bounds mDataBounds;
  std::array<RangeIndices,18> mUnsortedIndexRange;
  bool mHasSortedLayers;
  std::array<std::vector<RenderChunkQuadInfo>,7> mFaceMetadata;
  std::array<RangeIndices,14> mRenderLayerIndexRanges;
  unsigned __int8 mBuildVersionNumber;
  std::bitset<6> mInterlockBitField;
  std::array<unsigned char,6> mInterlockNeighborVersionNumbers;
  std::vector<mce::PointLight> mPointLights;
};

```

### `RenderChunkShared::ActorBlockSyncMessageWithVersion`
```
struct __cppobj __declspec(align(8)) RenderChunkShared::ActorBlockSyncMessageWithVersion
{
  ActorBlockSyncMessage mEntityBlockSyncMessage;
  unsigned __int8 mRenderChunkGeometryVersion;
};

```

### `RenderChunkShared`
```
struct __cppobj RenderChunkShared
{
  bool mEmpty;
  std::atomic<enum RenderChunkShared::BuildState> mBuildState;
  BlockPos mCenter;
  BlockPos mPosition;
  std::atomic<enum RenderChunkShared::VisibilityBuildState> mVisibilityBuildState;
  std::shared_ptr<RenderChunkGeometry> mCurrentRenderChunkGeometry;
  VisibilityNode mVisibility;
  bool mVisibilityMatrixChanged;
  bool mSkyLit;
  bool mAllDark;
  bool mImmediateChangeRequested;
  std::shared_ptr<RenderChunkGeometry> mBuildingRenderChunkGeometry;
  std::vector<RenderChunkShared::ActorBlockSyncMessageWithVersion> mEntityBlockMessageList;
  std::vector<RenderChunkShared::BlockActorBlockSyncMessageWithVersion> mBlockEntityBlockMessageList;
  dragon::RenderMetadata mRenderMetadata;
};

```

### `RenderChunkCoordinatorProxyCallbacks`
```
struct __cppobj RenderChunkCoordinatorProxyCallbacks
{
  std::function<unsigned __int64 __cdecl(void)> mGetRenderChunkSharedCount;
  std::function<mce::Color & __cdecl(void)> getFogColor;
  std::function<float __cdecl(void)> getFogDistance;
};

```

### `RenderChunkCoordinatorProxy`
```
struct __cppobj RenderChunkCoordinatorProxy
{
  RenderChunkCoordinatorProxyCallbacks mCallbacks;
};

```

### `RenderChunkCoordinator`
```
struct __cppobj RenderChunkCoordinator : LevelListener
{
  float mSweepAndPruneRatio;
  std::_List_const_iterator<std::_List_val<std::_List_simple_types<std::pair<SubChunkPos const ,std::weak_ptr<RenderChunkShared> > > > > mSweepAndPruneIterator;
  std::unordered_map<SubChunkPos,std::weak_ptr<RenderChunkShared>> mRenderChunkSharedMap;
  Level *mLevel;
  LevelRenderer *mLevelRenderer;
  std::vector<LevelRendererCamera *> mLevelRendererCameraListenerList;
  AutomaticID<Dimension,int> mDimensionId;
  std::unordered_map<SubChunkPos,RenderChunkCoordinator::DirtyChunkData> mVisibilityDirtyRenderChunkMap;
  std::unordered_map<SubChunkPos,std::vector<ActorBlockSyncMessage>> mRenderChunkChangedEntityNotificationMap;
  std::unordered_map<SubChunkPos,std::vector<BlockActorBlockSyncMessage>> mRenderChunkChangedBlockEntityNotificationMap;
  std::unique_ptr<RenderChunkCoordinatorProxy> mProxy;
};

```

### `RenderControllerGroup`
```
struct __cppobj RenderControllerGroup
{
};

```

### `RenderControllerInfo`
```
struct __cppobj RenderControllerInfo
{
  HashedString mName;
  std::unique_ptr<RenderController> mPtr;
};

```

### `RenderChunkSorter::FaceInfo`
```
struct __cppobj RenderChunkSorter::FaceInfo
{
  float distance;
  unsigned __int32 index : 31;
  unsigned __int32 reverse : 1;
};

```

### `RenderChunkSorterSharedInfo`
```
struct __cppobj __declspec(align(4)) RenderChunkSorterSharedInfo
{
  std::atomic<float> x;
  std::atomic<float> y;
  std::atomic<float> z;
  std::atomic<float> dx;
  std::atomic<float> dy;
  std::atomic<float> dz;
  std::atomic<bool> cameraIsOrthographic;
};

```

### `ResourcePackTreatmentQuery`
```
struct __cppobj ResourcePackTreatmentQuery : std::enable_shared_from_this<ResourcePackTreatmentQuery>
{
  TreatmentPackDownloadMonitor *mMonitor;
  ContentCatalogService *mCatalogService;
};

```

### `ResponseVerifier`
```
struct __cppobj ResponseVerifier
{
  ResponseVerifier_vtbl *__vftable /*VFT*/;
};

```

### `ResponseVerifier_vtbl`
```
struct /*VFT*/ ResponseVerifier_vtbl
{
  void (__fastcall *~ResponseVerifier)(ResponseVerifier *this);
};

```

### `RealmsPaymentService`
```
struct __cppobj RealmsPaymentService : ServiceClient
{
  Options *mOptions;
  Bedrock::PubSub::ScopedSubscription mRealmsOptionSubscription;
  std::string mPaymentEndpoint;
  std::string mPaymentRelyingParty;
};

```

### `RealmsPaymentService_vtbl`
```
struct /*VFT*/ RealmsPaymentService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `RealmsTransactionHandler`
```
struct __cppobj RealmsTransactionHandler : TransactionHandler
{
  GameStore *mGameStore;
  PurchaseCache *mPurchaseCache;
  std::unique_ptr<RealmsPaymentService> mPaymentService;
};

```

### `RealmsTransactionHandler_vtbl`
```
struct /*VFT*/ RealmsTransactionHandler_vtbl
{
  void (__fastcall *~TransactionHandler)(TransactionHandler *this);
  void (__fastcall *update)(TransactionHandler *this);
  void (__fastcall *transactPurchase)(TransactionHandler *this, Offer *, TransactionContext *, PurchasePath);
  bool (__fastcall *transactFulfillment)(TransactionHandler *this, Offer *, std::shared_ptr<Purchase>, std::unique_ptr<TransactionContext>, PurchasePath);
};

```

### `Realms::SubscriptionService`
```
struct __cppobj Realms::SubscriptionService : std::enable_shared_from_this<Realms::SubscriptionService>
{
  std::weak_ptr<Realms::ISubscriptionApi> mSubscriptionApi;
  std::vector<Realms::SubscriptionService::CachedSubscription> mSubscriptionCache;
  std::vector<Realms::SubscriptionService::SubscriptionQuery> mSubscriptionQueries;
  const std::chrono::duration<__int64,std::ratio<1,1000> > mCacheValidityDuration;
  const std::chrono::duration<__int64,std::ratio<1,1000> > mRetryTimeout;
  const unsigned int mMaxRetryAttempts;
  const std::function<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > __cdecl(void)> _getTimeNowInMilliseconds;
};

```

### `Realms::RealmsServices`
```
struct __cppobj Realms::RealmsServices
{
  std::unique_ptr<Realms::ContentService> mContentService;
  std::shared_ptr<Realms::SubscriptionService> mSubscriptionService;
  std::unique_ptr<ClubsService> mClubsService;
  std::shared_ptr<Realms::GenericRequestServiceHandler> mGenericRequestService;
};

```

### `ResetCallbackObject`
```
struct __cppobj __declspec(align(8)) ResetCallbackObject
{
  ResetCallbackObject_vtbl *__vftable /*VFT*/;
  bool mCallbackReady;
};

```

### `ResetCallbackObject_vtbl`
```
struct /*VFT*/ ResetCallbackObject_vtbl
{
  void (__fastcall *~ResetCallbackObject)(ResetCallbackObject *this);
  void (__fastcall *resetCallback)(ResetCallbackObject *this);
};

```

### `RenderControllerToProcess`
```
struct __cppobj RenderControllerToProcess
{
  RenderController *mRenderController;
  DataDrivenGeometry *mGeo;
  unsigned __int64 mSortIndex;
};

```

### `RandomizableBlockActorContainerBase`
```
struct __cppobj __declspec(align(8)) RandomizableBlockActorContainerBase : BlockActor
{
  std::string mLootTable;
  int mLootTableSeed;
};

```

### `RandomizableBlockActorFillingContainer`
```
struct __cppobj RandomizableBlockActorFillingContainer : RandomizableBlockActorContainerBase, FillingContainer
{
};

```

### `RayTracingOptions`
```
struct __cppobj RayTracingOptions : ResourcePackListener, IRayTracingOptions
{
  bool mAttachedListener;
  bool mRayTracingHardware;
  bool mRayTracingResourcesAvailable;
  ServiceRegistrationToken<IRayTracingOptions> mServiceRegistrationToken;
};

```

### `RayTracingOptions_vtbl`
```
struct /*VFT*/ RayTracingOptions_vtbl
{
  void (__fastcall *~ResourcePackListener)(ResourcePackListener *this);
  void (__fastcall *onActiveResourcePacksChanged)(ResourcePackListener *this, ResourcePackManager *);
  void (__fastcall *onFullPackStackInvalid)(ResourcePackListener *this);
  void (__fastcall *onBaseGamePackDownloadComplete)(ResourcePackListener *this);
  void (__fastcall *onLanguageSubpacksChanged)(ResourcePackListener *this);
  void (__fastcall *onResourceManagerDestroyed)(ResourcePackListener *this, ResourcePackManager *);
};

```

### `RuntimeLightingManager::RuntimeLightingSubchunkList`
```
struct __cppobj RuntimeLightingManager::RuntimeLightingSubchunkList
{
  std::array<std::vector<SubChunkLightUpdate>,32> mAlteredSubchunkBlockList;
};

```

### `RuntimeLightingManager::RelightingChunkElement`
```
struct __cppobj RuntimeLightingManager::RelightingChunkElement
{
  float mDist;
  ChunkPos mChunkPos;
  unsigned __int64 mSubChunkIndex;
  std::vector<SubChunkLightUpdate> *mAlteredBlockList;
};

```

### `RuntimeLightingManager`
```
struct __cppobj RuntimeLightingManager
{
  std::unordered_map<ChunkPos,RuntimeLightingManager::RuntimeLightingSubchunkList> mLevelChunksToLight;
  std::vector<RuntimeLightingManager::RelightingChunkElement> mListOfChunksToProcess;
  std::vector<SubChunkPos> mProcessedSubchunks;
  std::vector<BlockPos> mBrightnessChangedList;
  Dimension *mDimension;
  bool mWorkerScheduled;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mLightingTimeboxTime;
};

```

### `Raid`
```
struct __cppobj Raid
{
  Raid::RaidState mCurrentRaidState;
  unsigned __int8 mCurrentGroupNumber;
  unsigned __int8 mNumGroupsInRaid;
  Tick mTicksInState;
  const int mRaidPreparationTime;
  const int mGroupCompleteDelay;
  int mTicksUntilGroupComplete;
  const int mLocationHelpDelay;
  int mTicksUntilLocationHelp;
  Vec3 mCurrentGroupSpawnPoint;
  std::unordered_set<ActorUniqueID> mRaiders;
  unsigned __int8 mNumRaidersSpawnedInCurrentGroup;
  const unsigned __int8 mAllowedSpawnFailures;
  unsigned __int8 mSpawnFailures;
  const std::function<bool __cdecl(unsigned __int64,Vec3 &)> mPickSpawnPointCallback;
  const std::function<bool __cdecl(unsigned __int64,Vec3,unsigned char,std::unordered_set<ActorUniqueID> &)> mSpawnGroupCallback;
  const std::function<bool __cdecl(ActorUniqueID const &)> mDoesActorExistCallback;
  std::function<void __cdecl(Raid const &)> mOnSpawnPointChosenCallback;
  std::function<void __cdecl(Raid const &)> mOnGroupSpawnedCallback;
  std::function<void __cdecl(Raid const &)> mOnAwardRewardsCallback;
  std::function<void __cdecl(Raid const &)> mOnHelpLocateRaidersCallback;
};

```

### `RandomValueBounds`
```
struct __cppobj RandomValueBounds
{
  float mMin;
  float mMax;
};

```

### `ResolveData`
```
const struct __cppobj ResolveData
{
  const gsl::not_null<Actor const *> mActor;
  const gsl::not_null<Scoreboard const *> mScoreboard;
};

```

### `ResourcePackFileUploadManager`
```
struct __cppobj ResourcePackFileUploadManager : FileUploadManager
{
  std::vector<Core::PathBuffer<std::string >> mZipPaths;
  std::vector<Core::PathBuffer<std::string >> mTempDirPaths;
};

```

### `ResourcePackFileUploadManager_vtbl`
```
struct /*VFT*/ ResourcePackFileUploadManager_vtbl
{
  void (__fastcall *~FileUploadManager)(FileUploadManager *this);
  float (__fastcall *getUploadProgress)(FileUploadManager *this);
  void (__fastcall *uploadFileToRealmStorage)(FileUploadManager *this, const std::string *, const Core::Path *, const std::string *);
};

```

### `ResourcePackTransmissionManager`
```
struct __cppobj ResourcePackTransmissionManager
{
  std::unordered_map<unsigned __int64,std::unordered_map<std::string,std::shared_ptr<ResourcePackFileDownloaderManager>>> mResourceDownloadManagers;
  std::unordered_map<unsigned __int64,std::unordered_map<std::string,std::shared_ptr<ResourcePackFileUploadManager>>> mResourceUploadManagers;
  std::unordered_set<unsigned __int64> mRemovedResourceDownloadManagers;
  std::unordered_set<unsigned __int64> mRemovedResourceUploadManagers;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
};

```

### `RuntimeIdentifierDescription_vtbl`
```
struct /*VFT*/ RuntimeIdentifierDescription_vtbl
{
  void (__fastcall *~DefintionDescription)(DefintionDescription *this);
  const char *(__fastcall *getJsonName)(DefintionDescription *this);
};

```

### `RaidTriggerDescription`
```
struct __cppobj RaidTriggerDescription : ComponentDescription
{
  DefinitionTrigger mOnTriggered;
};

```

### `RaidTriggerDescription_vtbl`
```
struct /*VFT*/ RaidTriggerDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `Recipes`
```
struct __cppobj Recipes
{
  ResourcePackManager *mResourcePackManager;
  std::map<HashedString,std::map<std::string,std::shared_ptr<Recipe>>> mRecipes;
  std::map<Recipes::FurnaceRecipeKey,ItemInstance> mFurnaceRecipes;
  bool mInitializing;
  std::map<ItemInstance,std::unordered_map<std::string,Recipe *>,SortItemInstanceIdAux,std::allocator<std::pair<ItemInstance const ,std::unordered_map<std::string,Recipe *> > > > mRecipesByOutput;
  std::unordered_map<TypedServerNetId<RecipeNetIdTag,unsigned int,0>,Recipe *,std::hash<TypedServerNetId<RecipeNetIdTag,unsigned int,0> >,std::equal_to<TypedServerNetId<RecipeNetIdTag,unsigned int,0> >,std::allocator<std::pair<TypedServerNetId<RecipeNetIdTag,unsigned int,0> const ,Recipe *> > > mRecipesByNetId;
  std::unordered_set<std::string> mRecipeIds;
  std::vector<std::pair<std::weak_ptr<bool>,std::function<void __cdecl(void)> >> mListeners;
  Level *mLevel;
};

```

### `RopePoint`
```
struct __cppobj RopePoint
{
  Vec3 mOldPos;
  Vec3 mToNewPos;
};

```

### `RopePoints`
```
struct __cppobj RopePoints
{
  unsigned __int64 mSize;
  std::vector<RopePoint> mPoints;
};

```

### `RopeParams`
```
struct __cppobj __declspec(align(8)) RopeParams
{
  float mNodeDist;
  float mNodeSize;
  float mGravity;
  float mSlack;
  float mMaxTension;
  float mVelDamping;
  float mRelaxation;
  float mFriction;
  Vec3 mStartPin;
  Vec3 mEndPin;
  unsigned __int64 mIterations;
  unsigned __int64 mDestroyDelay;
  int mFlags;
  float mLength;
  float mOriginalNodeDist;
};

```

### `RopeSystem`
```
struct __cppobj RopeSystem
{
  bool mWaveApplied;
  RopePoints mQueuedRenderPoints;
  RopePoints mRenderPoints;
  std::vector<RopeNode> mNodes;
  std::vector<AABBBucket> mColliderBuckets;
  std::vector<RopeWave> mWaves;
  RopeParams mParams;
  std::set<AABB,AABBPred,std::allocator<AABB> > mDenyListedColliders;
  Vec3 mPrevStartPin;
  Vec3 mPrevEndPin;
  unsigned __int64 mCutNode;
  unsigned __int64 mCutRenderNode;
  unsigned __int64 mMinNodes;
  unsigned __int64 mCutTicks;
  ActorUniqueID mEndPinEntity;
  std::atomic_flag mTicking;
  std::mutex mRenderMutex;
  bool mAbandonCollision;
  Vec3 mStartPin;
  Vec3 mEndPin;
  unsigned __int64 mToCutNode;
};

```

### `RandomThreadCheckManager`
```
struct __cppobj __declspec(align(8)) RandomThreadCheckManager : AppPlatformListener
{
  std::atomic<unsigned int> mSuspendResumeIndex;
};

```

### `RandomThreadCheckManager_vtbl`
```
struct /*VFT*/ RandomThreadCheckManager_vtbl
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

### `RegisteredTagFilter`
```
struct __cppobj RegisteredTagFilter
{
  IDType<TagSetIDType> mIncludeSet;
  IDType<TagSetIDType> mExcludeSet;
};

```

### `Range<short,1>::iterator`
```
struct __cppobj Range<short,1>::iterator
{
  __int16 mIndex;
};

```

### `Range<short,1>`
```
struct __cppobj Range<short,1>
{
  const __int16 mBeginIDX;
  const __int16 mEndIDX;
};

```

### `Range<unsigned int,1>::iterator`
```
struct __cppobj Range<unsigned int,1>::iterator
{
  unsigned int mIndex;
};

```

### `ResourcePackContents`
```
struct __cppobj ResourcePackContents
{
  unsigned int mUIJson;
  unsigned int mUITextures;
  unsigned int mSound;
  unsigned int mBlockJson;
  unsigned int mBlockTextures;
  unsigned int mItemTextures;
  unsigned int mEntityTextures;
  unsigned int mModelGeometry;
  unsigned int mAnimations;
  unsigned int mMaterials;
  unsigned int mLanguages;
};

```

### `Realms::ConfigInfo`
```
struct __cppobj Realms::ConfigInfo
{
  std::string versionReference;
  std::vector<Realms::ConfigInfo::Version> versions;
};

```

### `Realms::InviteId`
```
struct __cppobj Realms::InviteId : NewType<std::string >
{
};

```

### `Realms::Invite`
```
struct __cppobj __declspec(align(8)) Realms::Invite
{
  Realms::InviteId id;
  Realms::Invite::State state;
  std::string worldName;
  std::string worldDescription;
  std::string ownerXuid;
  std::string ownerName;
  int date;
};

```

### `ResourcePackProgressHandler`
```
struct __cppobj __declspec(align(8)) ResourcePackProgressHandler : ProgressHandler
{
  bool mDone;
  std::string mPackProgress;
  float mProgress;
  std::string mProgressMessage;
  _BYTE mLoadingState[4];
  bool mDisconnected;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mStartTimestamp;
  bool mLocalServer;
  bool mCanceled;
};

```

### `ResourcePackProgressHandler_vtbl`
```
struct /*VFT*/ ResourcePackProgressHandler_vtbl
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

### `RealmsAPI::FeatureFlagPair`
```
struct __cppobj __declspec(align(8)) RealmsAPI::FeatureFlagPair
{
  std::string feature;
  bool flag;
};

```

### `RealmsTransactionContext`
```
struct __cppobj __declspec(align(8)) RealmsTransactionContext : TransactionContext
{
  std::string mWorldName;
  std::string mSubscriptionId;
  Realms::World mRealmWorld;
  bool mDevSkipPurchase;
};

```

### `RatingsSection`
```
struct __cppobj RatingsSection : PDPSection
{
};

```

### `RatingsSection_vtbl`
```
struct /*VFT*/ RatingsSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `RecentlyViewedSection`
```
struct __cppobj RecentlyViewedSection : PDPSection
{
};

```

### `RecentlyViewedSection_vtbl`
```
struct /*VFT*/ RecentlyViewedSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `RelatedItemsSection`
```
struct __cppobj RelatedItemsSection : PDPSection
{
};

```

### `RelatedItemsSection_vtbl`
```
struct /*VFT*/ RelatedItemsSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `ResponseCallbackHandler`
```
struct __cppobj ResponseCallbackHandler
{
  ResponseCallbackHandler_vtbl *__vftable /*VFT*/;
};

```

### `ResponseCallbackHandler_vtbl`
```
struct /*VFT*/ ResponseCallbackHandler_vtbl
{
  void (__fastcall *~ResponseCallbackHandler)(ResponseCallbackHandler *this);
  bool (__fastcall *parseResponse)(ResponseCallbackHandler *this, const struct web::json::array *, int, const CatalogBackend *, SearchRequestURLType);
  bool (__fastcall *parseResponse)(ResponseCallbackHandler *this, const struct web::json::value *);
  void (__fastcall *handleResponseCallback)(ResponseCallbackHandler *this);
};

```

### `RealmsCustom`
```
struct __cppobj RealmsCustom
{
  int mPrice;
  std::string mSKU;
};

```

### `RealmsDocument`
```
struct __cppobj RealmsDocument
{
  CommonDocument mCommon;
  RealmsCustom mCustom;
};

```

### `RealmsSearchResults`
```
const struct __cppobj RealmsSearchResults : CommonSearchResults
{
  std::vector<RealmsDocument> mDocuments;
};

```

### `ResourcePackTreatmentCustom`
```
struct __cppobj ResourcePackTreatmentCustom
{
  std::vector<PackIdVersion> mPackIdentities;
  DateRange mDateRange;
  std::string mRequiredTreatmentTag;
  int mPriority;
  int mMinPerformanceTier;
};

```

### `ResourcePackTreatmentDocument`
```
struct __cppobj ResourcePackTreatmentDocument
{
  CommonDocument mCommon;
  ResourcePackTreatmentCustom mCustom;
};

```

### `ResourcePackTreatmentSearchResults`
```
const struct __cppobj ResourcePackTreatmentSearchResults : CommonSearchResults
{
  std::vector<ResourcePackTreatmentDocument> mDocuments;
};

```

### `ReviewByUserParams`
```
struct __cppobj ReviewByUserParams
{
  std::string mUserId;
  std::string mProductId;
};

```

### `ReviewByUserResponse`
```
struct __cppobj ReviewByUserResponse
{
  std::unique_ptr<ReviewData> mReviewData;
};

```

### `ReviewSummaryParams`
```
struct __cppobj ReviewSummaryParams
{
  std::string mProductId;
};

```

### `ReviewSummaryResponse`
```
struct __cppobj ReviewSummaryResponse
{
  std::unique_ptr<ReviewSummaryData> mReviewSummaryData;
};

```

### `RealmsAllowListScreenController`
```
struct __cppobj __declspec(align(4)) RealmsAllowListScreenController : MainMenuScreenController
{
  bool mCalledAddFriendTCUI;
  RealmPlayer EMPTY_PLAYER;
  bool mLoading;
  bool mListsLoaded;
  bool mFromExistingWorld;
  std::function<void __cdecl(void)> mFollowUpActionAfterCreation;
  Realms::InviteLink mInviteLink;
  std::string mInviteUrlShort;
  bool mLoadingLink;
  bool mRefreshUI;
  bool mClickedRefresh;
  Realms::World mWorld;
  bool mInvitesSent;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastUpdate;
  bool mNewWorld;
  bool mReadyForCopy;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastTryJoin;
  std::unique_ptr<ProgressHandler> mProgressHandler;
  std::unique_ptr<PlatformMultiplayerRestrictions> mPlatformMultiplayerRestrictions;
  std::shared_ptr<DropdownScreenController> mMembersDropdownController;
  std::shared_ptr<DropdownScreenController> mInvitedFriendsDropdownController;
  int mUninvitedFriendsPageIndex;
  int mInvitedFriendsPageIndex;
  int mMembersPageIndex;
  int mBlockedPlayersPageIndex;
  PlayerPermissionLevel mDefaultPermission;
  PlayerPermissionLevel mDefaultPermissionOld;
  std::string mUninvitedFriendsLastFilter;
  std::string mInvitedFriendsLastFilter;
  std::string mMembersLastFilter;
  std::string mBlockedPlayersLastFilter;
  int mPreviousMembersPageIndex;
  int mPreviousInvitedFriendsPageIndex;
  int mPreviousUninvitedFriendsPageIndex;
  int mPreviousBlockedPlayersPageIndex;
  std::unordered_map<std::string,RealmPlayer> mCompleteWorldPlayerList;
  std::unordered_map<std::string,Social::PlatformUserProfileData> mLinkedPlatformAccounts;
  std::atomic<unsigned int> mLinkedAccountLoadCounter;
  std::vector<std::string> mCurrentMembersList;
  std::vector<std::string> mFullMembersList;
  std::vector<std::string> mFilteredMembersList;
  std::vector<std::string> mCurrentInvitedFriendsList;
  std::vector<std::string> mFullInvitedFriendsList;
  std::vector<std::string> mFilteredInvitedFriendsList;
  std::vector<std::string> mCurrentUninvitedFriendsList;
  std::vector<std::string> mFullUninvitedFriendsList;
  std::vector<std::string> mFilteredUninvitedFriendsList;
  std::vector<std::string> mCurrentBlockedPlayersList;
  std::vector<std::string> mFullBlockedPlayersList;
  std::vector<std::string> mFilteredBlockedPlayersList;
  std::vector<std::string> mPendingXuidsForLinkedAccounts;
  std::string mSharePopupBButtonDescription;
  unsigned int mCurrentUpdatedPlayers;
  bool mShowLinkedAccounts;
};

```

### `RealmsAllowListScreenController_vtbl`
```
struct /*VFT*/ RealmsAllowListScreenController_vtbl
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

### `RealmsProgressHandler`
```
struct __cppobj RealmsProgressHandler : ProgressHandler
{
  std::function<void __cdecl(void)> mOnStart;
  std::function<void __cdecl(void)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  std::string mTitleText;
};

```

### `RealmsProgressHandler_vtbl`
```
struct /*VFT*/ RealmsProgressHandler_vtbl
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

### `RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_1bbd9e1028777db9a54aba1753ac7873>`
```
struct __cppobj RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_1bbd9e1028777db9a54aba1753ac7873>
{
  const std::string xuid;
};

```

### `RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_b2566be69e596f95870dc527d93f4445>`
```
struct __cppobj RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_b2566be69e596f95870dc527d93f4445>
{
  const std::string xuid;
};

```

### `RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_a0672ba7342fef56ddaa7f52e7b03788>`
```
struct __cppobj RealmsAllowListScreenController::_clearFromFriendLists::__l2::<lambda_a0672ba7342fef56ddaa7f52e7b03788>
{
  const std::string xuid;
};

```

### `RealmsAllowListScreenController::_joinRealm::__l2::<lambda_4259dbfb7ddcebe1da890dec377a5f9f>`
```
struct __cppobj RealmsAllowListScreenController::_joinRealm::__l2::<lambda_4259dbfb7ddcebe1da890dec377a5f9f>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_updatePlayerlistModel::__l2::<lambda_fd50b47007fce5a5fbb3c39c818428c6>`
```
struct __cppobj RealmsAllowListScreenController::_updatePlayerlistModel::__l2::<lambda_fd50b47007fce5a5fbb3c39c818428c6>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_handlePlayerInvite::__l5::<lambda_329f000d0c240fa929b926f7dbce85af>`
```
struct __cppobj RealmsAllowListScreenController::_handlePlayerInvite::__l5::<lambda_329f000d0c240fa929b926f7dbce85af>
{
};

```

### `RealmsAllowListScreenController::_fetchInviteLink::__l2::<lambda_4f98088c2cdc53cfad06308499f91c4b>`
```
struct __cppobj RealmsAllowListScreenController::_fetchInviteLink::__l2::<lambda_4f98088c2cdc53cfad06308499f91c4b>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_regenerateInviteLink::__l2::<lambda_d389fd6031d885e93175d2f1bae78d56>`
```
struct __cppobj RealmsAllowListScreenController::_regenerateInviteLink::__l2::<lambda_d389fd6031d885e93175d2f1bae78d56>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::sendDefaultPermission::__l2::<lambda_4b01f3257c4e7d10ffa40608ae5a889b>`
```
struct __cppobj RealmsAllowListScreenController::sendDefaultPermission::__l2::<lambda_4b01f3257c4e7d10ffa40608ae5a889b>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::sendUserPermission::__l2::<lambda_778056cc072ba4beb6e77d67c80ca3aa>`
```
struct __cppobj __declspec(align(8)) RealmsAllowListScreenController::sendUserPermission::__l2::<lambda_778056cc072ba4beb6e77d67c80ca3aa>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  const std::string xuid;
  const PlayerPermissionLevel oldPermission;
};

```

### `RealmsAllowListScreenController::_requestPlatformGamerpic::__l2::<lambda_4ffbbdb0d5c680757322234803ce3f1b>`
```
struct __cppobj RealmsAllowListScreenController::_requestPlatformGamerpic::__l2::<lambda_4ffbbdb0d5c680757322234803ce3f1b>
{
  std::string id;
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_getBlocklistProfiles::__l2::<lambda_b260cb933b54af63cd24f86d910dbaeb>`
```
struct __cppobj RealmsAllowListScreenController::_getBlocklistProfiles::__l2::<lambda_b260cb933b54af63cd24f86d910dbaeb>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::vector<std::string> blockList;
};

```

### `RealmsAllowListScreenController::_clearMemberList::__l2::<lambda_695f03986dde6d536e9984c5aa9486cd>::()::__l5::<lambda_e7adc9c988d5a33ac6bdb76352f4c7e6>`
```
struct __cppobj RealmsAllowListScreenController::_clearMemberList::__l2::<lambda_695f03986dde6d536e9984c5aa9486cd>::()::__l5::<lambda_e7adc9c988d5a33ac6bdb76352f4c7e6>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::vector<std::string> playerXuids;
};

```

### `RealmsAllowListScreenController::_clearMemberList::__l2::<lambda_7918c6dfd19f57b2ac12f5824cf1546c>`
```
struct __cppobj RealmsAllowListScreenController::_clearMemberList::__l2::<lambda_7918c6dfd19f57b2ac12f5824cf1546c>
{
  RealmsAllowListScreenController *const __this;
  std::map<std::string,enum RealmsAPI::InviteAction> *inviteActions;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_6cac18bf96ac164bd270065ac95ea716>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_6cac18bf96ac164bd270065ac95ea716>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_8dc03758634f3b3c05a862aa15d60805>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_8dc03758634f3b3c05a862aa15d60805>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7ad24b30a475bbd123b428347bb33364>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7ad24b30a475bbd123b428347bb33364>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_34dec0d9bc462838c3e7382deedf93b3>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_34dec0d9bc462838c3e7382deedf93b3>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b22ad6adee5c2e237081128b8c13a630>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b22ad6adee5c2e237081128b8c13a630>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a561ffbc6850faad0707f9f32e74b392>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a561ffbc6850faad0707f9f32e74b392>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d0d53a878c990b1f4d9925cb002e59be>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d0d53a878c990b1f4d9925cb002e59be>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c1a358d689e3e1cb95a79a8c4a5f9944>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c1a358d689e3e1cb95a79a8c4a5f9944>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7edd97882f9aedd0e4fc0aa408ea6c9a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7edd97882f9aedd0e4fc0aa408ea6c9a>
{
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_311c7e1199c4323b4af1425ba3ebb84e>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_311c7e1199c4323b4af1425ba3ebb84e>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b15706b30d80fc5cc05b93c6eae4be82>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b15706b30d80fc5cc05b93c6eae4be82>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f33d3f2214e92946d91ed0a1b6fa8e17>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f33d3f2214e92946d91ed0a1b6fa8e17>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_27fdf94c6abe8b194f738f79ebcf3bdb>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_27fdf94c6abe8b194f738f79ebcf3bdb>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_aac6da44ee645518a5ff7093e3fc6b24>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_aac6da44ee645518a5ff7093e3fc6b24>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9228add5fc0efc98e86012ab41b1801d>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9228add5fc0efc98e86012ab41b1801d>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b19b2cdcff7b1f6ddeab77be0710ae7b>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b19b2cdcff7b1f6ddeab77be0710ae7b>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bf29e180c83e0e9992e4ffdefd5bd8ca>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bf29e180c83e0e9992e4ffdefd5bd8ca>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b445e48e37e56e5157166e23b2f8a699>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b445e48e37e56e5157166e23b2f8a699>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a0fd4585e6b9f02d8af0a81d176465d5>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a0fd4585e6b9f02d8af0a81d176465d5>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2ae33f68615505a0de5654222532a134>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2ae33f68615505a0de5654222532a134>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b03db9a4412bcacc35797c35c32f62ce>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b03db9a4412bcacc35797c35c32f62ce>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_e8350ed0d117f2e8f0c60e5c9e60bf13>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_e8350ed0d117f2e8f0c60e5c9e60bf13>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7a311a6153c4f4253911111c61126d93>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7a311a6153c4f4253911111c61126d93>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c2c014237611279377229555118cf5e8>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c2c014237611279377229555118cf5e8>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_dab1bb4d892ee65f6de573b3986cdf15>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_dab1bb4d892ee65f6de573b3986cdf15>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b132a41278fb8262cedde6df9ba71917>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b132a41278fb8262cedde6df9ba71917>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_55a42be718248fb5e133b2b3b56a4a3b>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_55a42be718248fb5e133b2b3b56a4a3b>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1abcdd5d4ea01c36de27501e3c439bd2>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1abcdd5d4ea01c36de27501e3c439bd2>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_31ec87a9f01fe2d356c177031ac1bda3>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_31ec87a9f01fe2d356c177031ac1bda3>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_773d4031204efb4836024f9bdcbec02a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_773d4031204efb4836024f9bdcbec02a>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_32ea8f2e0be50e45b71458b68223a670>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_32ea8f2e0be50e45b71458b68223a670>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1c0049c6c833bd1f9c2720b924665a6a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1c0049c6c833bd1f9c2720b924665a6a>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_514b4f99a3771467b277d19376d2fc64>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_514b4f99a3771467b277d19376d2fc64>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a2527938c294f7a968a7215b9bc1019a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_a2527938c294f7a968a7215b9bc1019a>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9f8d62eb4ed08d290f9a63e41b83f88f>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9f8d62eb4ed08d290f9a63e41b83f88f>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_e0ab122a1aafdf105b44155ef20eb2f1>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_e0ab122a1aafdf105b44155ef20eb2f1>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_dc3af545498fed980a56a42b58e33c5f>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_dc3af545498fed980a56a42b58e33c5f>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ca9732309a346999240527f9e4a8ebf1>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ca9732309a346999240527f9e4a8ebf1>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_88a15a45a6013e9a28404a79836258fa>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_88a15a45a6013e9a28404a79836258fa>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2b83d75035538fc5f15ba2c53ae150db>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2b83d75035538fc5f15ba2c53ae150db>
{
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_75096b1fd9d5ef652b8bf0c28d1789b0>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_75096b1fd9d5ef652b8bf0c28d1789b0>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b63828d127a5767df44702b82366be16>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_b63828d127a5767df44702b82366be16>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2edc2ed88ac4b9fd875c5c4a9bd98a4a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2edc2ed88ac4b9fd875c5c4a9bd98a4a>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_57aff02e6f4c5c08218d369d41881129>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_57aff02e6f4c5c08218d369d41881129>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ba3aa42712025e9ad99cef2ea2ee574d>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ba3aa42712025e9ad99cef2ea2ee574d>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_df5ee9234360832005bead72b0e80418>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_df5ee9234360832005bead72b0e80418>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_47f7db5f46440a50e4c1334a2a60e795>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_47f7db5f46440a50e4c1334a2a60e795>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ea9436fc718368a9338dce486ca65389>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ea9436fc718368a9338dce486ca65389>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_cef83c738c7391a4d9f33f38d9c7c812>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_cef83c738c7391a4d9f33f38d9c7c812>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1cc4659684778627817255f83f358efe>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1cc4659684778627817255f83f358efe>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_512789b6c1f30cafa1fa7bd18e5fec6d>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_512789b6c1f30cafa1fa7bd18e5fec6d>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_21af57391babf24e24607eebcf5a2f13>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_21af57391babf24e24607eebcf5a2f13>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2c6b55e0b0bde2b34f626cf66cedb881>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2c6b55e0b0bde2b34f626cf66cedb881>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9d9fadbf4c4ff9627b97aa35e0a348dc>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_9d9fadbf4c4ff9627b97aa35e0a348dc>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_4dc523e6e96f6001448f5407d3a9fe94>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_4dc523e6e96f6001448f5407d3a9fe94>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_3ef5022029f5eed01a57ce2b891f0934>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_3ef5022029f5eed01a57ce2b891f0934>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7caff5b237418e160773fcd5e14bcc00>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_7caff5b237418e160773fcd5e14bcc00>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_be1dda67bc84fea1f4398b5e29023740>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_be1dda67bc84fea1f4398b5e29023740>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f1bc5aff9d0aa33c8ff8e8d1a41ff4cb>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f1bc5aff9d0aa33c8ff8e8d1a41ff4cb>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_edd30fadfaafa53f6e5550209db44b74>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_edd30fadfaafa53f6e5550209db44b74>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_48819d367b0e8f5b8af09068ffe473d7>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_48819d367b0e8f5b8af09068ffe473d7>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c5d1c5d80a93c6c7dd1ddfb25cef2b62>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c5d1c5d80a93c6c7dd1ddfb25cef2b62>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_50fd85eeda43a1b0d2a9f87ca547f08c>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_50fd85eeda43a1b0d2a9f87ca547f08c>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2de692d0825e9a9514b4fa305de93c32>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2de692d0825e9a9514b4fa305de93c32>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_5c0f143773dd206d30ebcd115f4c6305>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_5c0f143773dd206d30ebcd115f4c6305>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_96d0b08d2b5a5c89613498ba1d59eb3b>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_96d0b08d2b5a5c89613498ba1d59eb3b>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1255bc99059d6069feb2533fa09e520e>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_1255bc99059d6069feb2533fa09e520e>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f8c7823dc7dda3f873e509757258f9e0>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f8c7823dc7dda3f873e509757258f9e0>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_511ab7c0f8fae3608584db64b2fb6ff2>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_511ab7c0f8fae3608584db64b2fb6ff2>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d4dc744181b7201fc714db3fcca2d7c4>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d4dc744181b7201fc714db3fcca2d7c4>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_71dac4dad6f19448359ed6fb9bcc5728>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_71dac4dad6f19448359ed6fb9bcc5728>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f66a2cc155a25d6ee7c2fab08a7685e3>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f66a2cc155a25d6ee7c2fab08a7685e3>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_adeffdf61cd3671d20f710c63c3cbb63>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_adeffdf61cd3671d20f710c63c3cbb63>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_849e39203bedd7b7a2fdcd2bed1adada>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_849e39203bedd7b7a2fdcd2bed1adada>
{
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_3e9fab0670f392ab9bef7b308be8352d>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_3e9fab0670f392ab9bef7b308be8352d>
{
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_61ed82b14eca700b3f55b314cc097833>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_61ed82b14eca700b3f55b314cc097833>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bce05cce3f240ec9212fc2f49773b9c3>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bce05cce3f240ec9212fc2f49773b9c3>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2bd7619b537ab53090334e1261394fa3>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2bd7619b537ab53090334e1261394fa3>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_711402cc3fd2b80a6955dbe2d6dbad1a>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_711402cc3fd2b80a6955dbe2d6dbad1a>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_572d3deba83802bc10085d4427d8e8e1>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_572d3deba83802bc10085d4427d8e8e1>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_0a7e1f1587bfdb8f36231b431ec291e8>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_0a7e1f1587bfdb8f36231b431ec291e8>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d2b5e83543d3165d2302e7909cc59760>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_d2b5e83543d3165d2302e7909cc59760>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c543bc83f7a3deea6ef0f86961f5f163>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c543bc83f7a3deea6ef0f86961f5f163>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ba83c9a4e5b87daaafeab2229c18d929>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_ba83c9a4e5b87daaafeab2229c18d929>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bf762cddc7a06b80941b19ae474173cc>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_bf762cddc7a06b80941b19ae474173cc>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_322b9245db294c1cbd58010b89226c45>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_322b9245db294c1cbd58010b89226c45>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_685ec9b42ec5c32b3f00f184332b2208>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_685ec9b42ec5c32b3f00f184332b2208>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c468a5acfa739a5957163f7e374b371b>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_c468a5acfa739a5957163f7e374b371b>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2a664425d3690a1efee875c655d4bc32>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_2a664425d3690a1efee875c655d4bc32>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f641d6d82486d185d7a386009a6c016e>`
```
struct __cppobj RealmsAllowListScreenController::_registerBindings::__l2::<lambda_f641d6d82486d185d7a386009a6c016e>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_835cf01e9b35f3ae5c73d44e853d3245>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_835cf01e9b35f3ae5c73d44e853d3245>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_322f4c12f959a76d3cd1080c8ddcf69f>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_322f4c12f959a76d3cd1080c8ddcf69f>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_c1f4774a3f50d123e2516a50354a4d8d>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_c1f4774a3f50d123e2516a50354a4d8d>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_82722cc7c3ab429ec8e49f36616ed073>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_82722cc7c3ab429ec8e49f36616ed073>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_448c927186c5b709407c3794118ebaaf>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_448c927186c5b709407c3794118ebaaf>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_57b493dd8e11f9ec7b2cfe89916ce4ba>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_57b493dd8e11f9ec7b2cfe89916ce4ba>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eb2ac3865f3d9a3456e673d4f19600ae>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eb2ac3865f3d9a3456e673d4f19600ae>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_5df825147952c78e5d74a6b1ff09058c>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_5df825147952c78e5d74a6b1ff09058c>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_817f7e2b6c14ee63ffdf87e7c531b87d>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_817f7e2b6c14ee63ffdf87e7c531b87d>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_555e55ff9fa5077a73c83d7c3c12b00f>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_555e55ff9fa5077a73c83d7c3c12b00f>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_42c63db9efa761c7ce39e91ef5ab7c07>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_42c63db9efa761c7ce39e91ef5ab7c07>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8135ad7a09ccaaeed634c56f3c3cf92e>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8135ad7a09ccaaeed634c56f3c3cf92e>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eb9c22d55d0f1aca1e7cde3a30d7a5ec>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eb9c22d55d0f1aca1e7cde3a30d7a5ec>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_0457167a3e1d55be5dc879acb180058f>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_0457167a3e1d55be5dc879acb180058f>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_72fe8a77d49490aafeaae0da533292d4>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_72fe8a77d49490aafeaae0da533292d4>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_4d3dbbd6f4e6faa6f90f83a4647972fa>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_4d3dbbd6f4e6faa6f90f83a4647972fa>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_144189ef867f62d65fd24fbc12b65a30>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_144189ef867f62d65fd24fbc12b65a30>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_dffb3e861ed0840a00a9780d88e65845>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_dffb3e861ed0840a00a9780d88e65845>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>::()::__l5::<lambda_488c1c54c019eaab5170715498d78b0e>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>::()::__l5::<lambda_488c1c54c019eaab5170715498d78b0e>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  int bagIndex;
  RealmsAllowListScreenController::RealmPlayerList listType;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>::()::__l5::<lambda_488c1c54c019eaab5170715498d78b0e>::()::__l18::<lambda_ede6175f005cf295a64dc34231e9dd18>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_54df864d97304a9fd7002809f95393fe>::()::__l5::<lambda_488c1c54c019eaab5170715498d78b0e>::()::__l18::<lambda_ede6175f005cf295a64dc34231e9dd18>
{
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_731a5c426e5a914fef7fc6e3df44a5e6>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_731a5c426e5a914fef7fc6e3df44a5e6>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_c2f714838fa1f1b03b29948639ce4617>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_c2f714838fa1f1b03b29948639ce4617>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eccd8ba0fb2baae06d8af8dd3a5a6413>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eccd8ba0fb2baae06d8af8dd3a5a6413>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eccd8ba0fb2baae06d8af8dd3a5a6413>::()::__l11::<lambda_311f8d71e4fb977bfb9634197db72530>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_eccd8ba0fb2baae06d8af8dd3a5a6413>::()::__l11::<lambda_311f8d71e4fb977bfb9634197db72530>
{
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_fda1008fe5931cbdec8cde035f8377ab>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_fda1008fe5931cbdec8cde035f8377ab>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_1137d2b6a49e66e7278ab3771af4b1df>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_1137d2b6a49e66e7278ab3771af4b1df>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8ae78f2a97ef1de97dd5b9e8e24015ef>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8ae78f2a97ef1de97dd5b9e8e24015ef>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8ae78f2a97ef1de97dd5b9e8e24015ef>::()::__l2::<lambda_de73895f4e3d1b555a7be97ccbc23d82>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_8ae78f2a97ef1de97dd5b9e8e24015ef>::()::__l2::<lambda_de73895f4e3d1b555a7be97ccbc23d82>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_3c2f9a0b11f0f5a42f22491b4e5bafed>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_3c2f9a0b11f0f5a42f22491b4e5bafed>
{
  RealmsAllowListScreenController *const __this;
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_6b6ed0be2e45c5aac5e2253780fd7282>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_6b6ed0be2e45c5aac5e2253780fd7282>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_195292b40f5d5070237b8ebf0424db13>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_195292b40f5d5070237b8ebf0424db13>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_79412a890d866e0720253fbf45b5162e>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l17::<lambda_79412a890d866e0720253fbf45b5162e>
{
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_8da930830e43e1e4f88dab1c5dbb5f28>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_8da930830e43e1e4f88dab1c5dbb5f28>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_6a4de5ae2294d58ad77fd5ca27ccaf97>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_6a4de5ae2294d58ad77fd5ca27ccaf97>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_979bc35294ec731eeb170d10f134a4b2>`
```
struct __cppobj RealmsAllowListScreenController::_sortPlayerList::__l12::<lambda_979bc35294ec731eeb170d10f134a4b2>
{
};

```

### `RealmsAllowListScreenController::_finalizeLinkedAccountLoading::__l5::<lambda_0d58d8466bcc1ced57228b8af60ceeb2>`
```
struct __cppobj RealmsAllowListScreenController::_finalizeLinkedAccountLoading::__l5::<lambda_0d58d8466bcc1ced57228b8af60ceeb2>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_updateLinkedAccountLoading::__l17::<lambda_0eb2995aed2642734fcab67ba790dc96>`
```
struct __cppobj RealmsAllowListScreenController::_updateLinkedAccountLoading::__l17::<lambda_0eb2995aed2642734fcab67ba790dc96>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_updateLinkedAccountLoading::__l17::<lambda_0eb2995aed2642734fcab67ba790dc96>::()::__l8::<lambda_fca957ac3c685e72f323764af8260295>`
```
struct __cppobj RealmsAllowListScreenController::_updateLinkedAccountLoading::__l17::<lambda_0eb2995aed2642734fcab67ba790dc96>::()::__l8::<lambda_fca957ac3c685e72f323764af8260295>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::string xuid;
};

```

### `RealmsAllowListScreenController::_initializePlayerList::__l5::<lambda_a4bcc8b3adf225baab8d30b5192e1574>`
```
struct __cppobj RealmsAllowListScreenController::_initializePlayerList::__l5::<lambda_a4bcc8b3adf225baab8d30b5192e1574>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::function<void __cdecl(void)> callback;
};

```

### `RealmsAllowListScreenController::sendInvites::__l2::<lambda_347f6d7e263536d529b69d49ed424793>`
```
struct __cppobj RealmsAllowListScreenController::sendInvites::__l2::<lambda_347f6d7e263536d529b69d49ed424793>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::function<void __cdecl(void)> callback;
};

```

### `RealmsAllowListScreenController::sendInvites::__l2::<lambda_c9167752c1d17d05f3d22429ee8b6e55>`
```
struct __cppobj RealmsAllowListScreenController::sendInvites::__l2::<lambda_c9167752c1d17d05f3d22429ee8b6e55>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
  std::function<void __cdecl(void)> callback;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>::()::__l8::<lambda_a6c708320a2beeb0b91162f69aa4dd4b>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>::()::__l8::<lambda_a6c708320a2beeb0b91162f69aa4dd4b>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>::()::__l8::<lambda_04870789ed606a5a4bef27ef85193c0b>`
```
struct __cppobj RealmsAllowListScreenController::_registerEventHandlers::__l2::<lambda_48bf5f817448d327fa232f4db8da89b4>::()::__l2::<lambda_7f3208798e6dfb7fbdc14ac96afe0f80>::()::__l8::<lambda_04870789ed606a5a4bef27ef85193c0b>
{
  std::weak_ptr<RealmsAllowListScreenController> weakThis;
};

```

### `RealmPackManagerContentSource`
```
struct __cppobj RealmPackManagerContentSource : PackManagerContentSource
{
  __int64 mRealmId;
};

```

### `RealmPackManagerContentSource_vtbl`
```
struct /*VFT*/ RealmPackManagerContentSource_vtbl
{
  void (__fastcall *~ContentSource)(ContentSource *this);
  void (__fastcall *load)(ContentSource *this);
  void (__fastcall *generateItems)(ContentSource *this, std::vector<std::unique_ptr<ContentItem>> *);
  void (__fastcall *save)(ContentSource *this);
  void (__fastcall *deleteContentFiles)(ContentSource *this, std::vector<ContentItem const *>);
  void (__fastcall *postDeleteContent)(ContentSource *this, std::vector<ContentItem const *>);
};

```

### `RenderContextHelper<Actor>`
```
struct __cppobj RenderContextHelper<Actor>
{
};

```

### `RenderContextHelper<ActorRenderData>`
```
struct __cppobj RenderContextHelper<ActorRenderData>
{
};

```

### `RenderContextHelper<BlockSource>`
```
struct __cppobj RenderContextHelper<BlockSource>
{
};

```

### `RenderContextHelper<IBlockWorldGenAPI>`
```
struct __cppobj RenderContextHelper<IBlockWorldGenAPI>
{
};

```

### `RPC_DISPATCH_TABLE`
```
struct RPC_DISPATCH_TABLE
{
  unsigned int DispatchTableCount;
  void (__fastcall **DispatchTable)(_RPC_MESSAGE *);
  __int64 Reserved;
};

```

### `ResourceUtil`
```
struct __cppobj ResourceUtil
{
};

```

### `RPC_IMPORT_CONTEXT_P`
```
struct RPC_IMPORT_CONTEXT_P
{
  void *LookupContext;
  void *ProposedHandle;
  _RPC_BINDING_VECTOR *Bindings;
};

```

### `RakNet::RNS2_BerkleyBindParameters`
```
struct __declspec(align(8)) RakNet::RNS2_BerkleyBindParameters
{
  unsigned __int16 port;
  char *hostAddress;
  unsigned __int16 addressFamily;
  int type;
  int protocol;
  bool nonBlockingSocket;
  int setBroadcast;
  int setIPHdrIncl;
  int doNotFragment;
  int pollingThreadPriority;
  RakNet::RNS2EventHandler *eventHandler;
  unsigned __int16 remotePortRakNetWasStartedOn_PS3_PS4_PSP2;
};

```

### `RakNet::IRNS2_Berkley`
```
struct __cppobj RakNet::IRNS2_Berkley : RakNet::RakNetSocket2
{
};

```

### `RakNet::IRNS2_Berkley_vtbl`
```
struct /*VFT*/ RakNet::IRNS2_Berkley_vtbl
{
  void (__fastcall *~RakNetSocket2)(RakNet::RakNetSocket2 *this);
  int (__fastcall *Send)(RakNet::RakNetSocket2 *this, RakNet::RNS2_SendParameters *, const char *, unsigned int);
  void (__fastcall *SetMulticastInterface)(RakNet::RakNetSocket2 *this, int);
  RakNet::RNS2BindResult (__fastcall *Bind)(RakNet::IRNS2_Berkley *this, RakNet::RNS2_BerkleyBindParameters *, const char *, unsigned int);
};

```

### `RakNet::RakNetSocket2Allocator`
```
struct __cppobj RakNet::RakNetSocket2Allocator
{
};

```

### `RakNet::RakWString`
```
struct __cppobj RakNet::RakWString
{
  wchar_t *c_str;
  unsigned __int64 c_strCharLength;
};

```

### `RakNet::ReferenceCounter`
```
struct __cppobj RakNet::ReferenceCounter
{
  int refCount;
};

```

### `RakNet::SocketLayerOverride`
```
struct __cppobj RakNet::SocketLayerOverride
{
  RakNet::SocketLayerOverride_vtbl *__vftable /*VFT*/;
};

```

### `RakNet::SocketLayerOverride_vtbl`
```
struct /*VFT*/ RakNet::SocketLayerOverride_vtbl
{
  void (__fastcall *~SocketLayerOverride)(RakNet::SocketLayerOverride *this);
  int (__fastcall *RakNetSendTo)(RakNet::SocketLayerOverride *this, const char *, int, const RakNet::SystemAddress *);
  int (__fastcall *RakNetRecvFrom)(RakNet::SocketLayerOverride *this, char *, RakNet::SystemAddress *, bool);
};

```

### `RakNet::RNS2_Berkley`
```
struct __cppobj __declspec(align(4)) RakNet::RNS2_Berkley : RakNet::IRNS2_Berkley
{
  int rns2Socket;
  RakNet::RNS2_BerkleyBindParameters binding;
  RakNet::LocklessUint32_t isRecvFromLoopThreadActive;
  volatile bool endThreads;
};

```

### `RakNet::RNS2_Berkley_vtbl`
```
struct /*VFT*/ RakNet::RNS2_Berkley_vtbl
{
  void (__fastcall *~RakNetSocket2)(RakNet::RakNetSocket2 *this);
  int (__fastcall *Send)(RakNet::RakNetSocket2 *this, RakNet::RNS2_SendParameters *, const char *, unsigned int);
  void (__fastcall *SetMulticastInterface)(RakNet::RakNetSocket2 *this, int);
  RakNet::RNS2BindResult (__fastcall *Bind)(RakNet::IRNS2_Berkley *this, RakNet::RNS2_BerkleyBindParameters *, const char *, unsigned int);
};

```

### `RakNet::RNS2_Windows_Linux_360`
```
struct __cppobj RakNet::RNS2_Windows_Linux_360
{
};

```

### `RakNet::RNS2_Windows`
```
struct __cppobj RakNet::RNS2_Windows : RakNet::RNS2_Berkley, RakNet::RNS2_Windows_Linux_360
{
  RakNet::SocketLayerOverride *slo;
};

```

### `RakNet::RNS2_Windows_vtbl`
```
struct /*VFT*/ RakNet::RNS2_Windows_vtbl
{
  void (__fastcall *~RakNetSocket2)(RakNet::RakNetSocket2 *this);
  int (__fastcall *Send)(RakNet::RakNetSocket2 *this, RakNet::RNS2_SendParameters *, const char *, unsigned int);
  void (__fastcall *SetMulticastInterface)(RakNet::RakNetSocket2 *this, int);
  RakNet::RNS2BindResult (__fastcall *Bind)(RakNet::IRNS2_Berkley *this, RakNet::RNS2_BerkleyBindParameters *, const char *, unsigned int);
};

```

### `RakNet::RakThread`
```
struct __cppobj RakNet::RakThread
{
};

```

### `RPC_CLIENT_INFORMATION1`
```
struct RPC_CLIENT_INFORMATION1
{
  unsigned __int8 *UserName;
  unsigned __int8 *ComputerName;
  unsigned __int16 Privilege;
  unsigned int AuthFlags;
};

```

### `RPC_STATS_VECTOR`
```
struct RPC_STATS_VECTOR
{
  unsigned int Count;
  unsigned int Stats[1];
};

```

### `RPC_IF_ID_VECTOR`
```
struct RPC_IF_ID_VECTOR
{
  unsigned int Count;
  _RPC_IF_ID *IfId[1];
};

```

### `rendergraph::RenderPass`
```
struct __cppobj rendergraph::RenderPass : rendergraph::Pass
{
};

```

### `rendergraph::RenderPass_vtbl`
```
struct /*VFT*/ rendergraph::RenderPass_vtbl
{
  void (__fastcall *~Pass)(rendergraph::Pass *this);
  void (__fastcall *execute)(rendergraph::Pass *this, rendergraph::RenderContext *);
  void (__fastcall *render)(rendergraph::RenderPass *this, rendergraph::RenderContext *);
};

```

### `rendergraph::CustomRenderPass<void>`
```
struct __cppobj rendergraph::CustomRenderPass<void> : rendergraph::RenderPass
{
  std::function<void __cdecl(rendergraph::RenderContext &)> mCallback;
};

```

### `rendergraph::CustomRenderPass<void>_vtbl`
```
struct /*VFT*/ rendergraph::CustomRenderPass<void>_vtbl
{
  void (__fastcall *~Pass)(rendergraph::Pass *this);
  void (__fastcall *execute)(rendergraph::Pass *this, rendergraph::RenderContext *);
  void (__fastcall *render)(rendergraph::RenderPass *this, rendergraph::RenderContext *);
};

```

### `RideRotationBehavior`
```
struct __cppobj RideRotationBehavior : CameraBehavior<RideRotationBehavior>
{
};

```

### `RideRotationBehavior_vtbl`
```
struct /*VFT*/ RideRotationBehavior_vtbl
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

### `RideRotationBehaviorLoader`
```
struct __cppobj RideRotationBehaviorLoader : CameraBehaviorLoader
{
};

```

### `RideRotationBehaviorLoader_vtbl`
```
struct /*VFT*/ RideRotationBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `ResourceLoadManager::LoadOrder`
```
struct __cppobj ResourceLoadManager::LoadOrder
{
};

```

### `Rect2D`
```
struct __cppobj Rect2D
{
  int x;
  int y;
  int width;
  int height;
  int offsetX;
  int offsetY;
};

```

### `Range<int,1>::iterator`
```
struct __cppobj Range<int,1>::iterator
{
  int mIndex;
};

```

### `RealmsWorldInfo`
```
struct __cppobj RealmsWorldInfo : WorldInfo
{
  int mPlayerCount;
  std::string mOwnerName;
  std::string mOwnerXuid;
  std::string mWorldName;
  bool mOwner;
  bool mExpired;
  bool mFull;
  Realms::World *mWorld;
};

```

### `RakNet::TCPInterface::ThisPtrPlusSysAddr`
```
struct __cppobj __declspec(align(8)) RakNet::TCPInterface::ThisPtrPlusSysAddr
{
  RakNet::TCPInterface *tcpInterface;
  RakNet::SystemAddress systemAddress;
  bool useSSL;
  char bindAddress[64];
  unsigned __int16 socketFamily;
};

```

### `ResourceLoadProgressHandler`
```
struct __cppobj ResourceLoadProgressHandler : EmptyProgressHandler
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastResourceLoadManagerCheck;
};

```

### `ResourceLoadProgressHandler_vtbl`
```
struct /*VFT*/ ResourceLoadProgressHandler_vtbl
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

### `RecordItemComponent`
```
struct __cppobj __declspec(align(8)) RecordItemComponent : ItemComponent
{
  LevelSoundEvent mSoundEvent;
  float mDuration;
  int mComparatorSignal;
};

```

### `RecordItemComponent_vtbl`
```
struct /*VFT*/ RecordItemComponent_vtbl
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

### `RepairableItemComponent`
```
struct __cppobj RepairableItemComponent : ItemComponent
{
  std::vector<RepairItemEntry> mRepairItems;
  DefinitionTrigger mOnRepaired;
};

```

### `RepairableItemComponent_vtbl`
```
struct /*VFT*/ RepairableItemComponent_vtbl
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

### `reflection::factory<ItemComponent>`
```
struct reflection::factory<ItemComponent>
{
  entt::meta_factory<ItemComponent> mFactory;
};

```

### `ReqServerlistStage`
```
struct __cppobj ReqServerlistStage : BaseStage
{
};

```

### `ReqServerlistStage_vtbl`
```
struct /*VFT*/ ReqServerlistStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReqH5VersionStage`
```
struct __cppobj ReqH5VersionStage : BaseStage
{
};

```

### `ReqH5VersionStage_vtbl`
```
struct /*VFT*/ ReqH5VersionStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReloadRNStage`
```
struct __cppobj ReloadRNStage : BaseStage
{
};

```

### `ReloadRNStage_vtbl`
```
struct /*VFT*/ ReloadRNStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReqTransferSrvStage`
```
struct __cppobj __declspec(align(8)) ReqTransferSrvStage : BaseStage
{
  Random mRandom;
};

```

### `ReqTransferSrvStage_vtbl`
```
struct /*VFT*/ ReqTransferSrvStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReqChatServerStage`
```
struct __cppobj ReqChatServerStage : BaseStage
{
};

```

### `ReqChatServerStage_vtbl`
```
struct /*VFT*/ ReqChatServerStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReQWebGrayStage`
```
struct __cppobj ReQWebGrayStage : BaseStage
{
};

```

### `ReQWebGrayStage_vtbl`
```
struct /*VFT*/ ReQWebGrayStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `ReqAppleReviewServerlistStage`
```
struct __cppobj ReqAppleReviewServerlistStage : BaseStage
{
};

```

### `ReqAppleReviewServerlistStage_vtbl`
```
struct /*VFT*/ ReqAppleReviewServerlistStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `Range<unsigned __int64,1>::iterator`
```
struct __cppobj Range<unsigned __int64,1>::iterator
{
  unsigned __int64 mIndex;
};

```

### `Range<unsigned __int64,1>`
```
struct __cppobj Range<unsigned __int64,1>
{
  const unsigned __int64 mBeginIDX;
  const unsigned __int64 mEndIDX;
};

```

### `RemoteStorageProviderSyncProgressHandler`
```
struct __cppobj __declspec(align(8)) RemoteStorageProviderSyncProgressHandler : ProgressHandler
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mStartTimestamp;
  CallbackToken mSyncToken;
  std::function<CallbackToken __cdecl(std::function<void __cdecl(Core::Result)>)> mActionCallback;
  std::function<void __cdecl(Core::Result)> mCompletedCallback;
  std::atomic<bool> mCompletedCallbackCalled;
  Core::Result mCachedErrorResult;
  std::atomic<enum RemoteStorageProviderSyncProgressHandler::State> mState;
};

```

### `RemoteStorageProviderSyncProgressHandler_vtbl`
```
struct /*VFT*/ RemoteStorageProviderSyncProgressHandler_vtbl
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

### `RopePointsRef`
```
struct __cppobj RopePointsRef
{
  const RopePoints *mPoints;
  std::mutex *mPointMutex;
};

```

### `ResourceLoaderLocationExpander_vtbl`
```
struct /*VFT*/ ResourceLoaderLocationExpander_vtbl
{
  void (__fastcall *~IResourceLocationExpander)(IResourceLocationExpander *this);
  ResourceLocation *(__fastcall *getFullPath)(IResourceLocationExpander *this, ResourceLocation *result, const ResourceLocation *, const std::vector<std::string> *);
};

```

### `RenderHelper`
```
struct __cppobj RenderHelper
{
};

```

### `RealmsConnectProgressHandler`
```
struct __cppobj __declspec(align(8)) RealmsConnectProgressHandler : ProgressHandler
{
  std::function<bool __cdecl(void)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  std::string mTitleText;
  bool mConnected;
};

```

### `RealmsConnectProgressHandler_vtbl`
```
struct /*VFT*/ RealmsConnectProgressHandler_vtbl
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

### `RealmsApplyContentProgressHandler`
```
struct __cppobj __declspec(align(8)) RealmsApplyContentProgressHandler : ProgressHandler
{
  std::function<bool __cdecl(void)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  std::string mTitleText;
  bool mDone;
};

```

### `RealmsApplyContentProgressHandler_vtbl`
```
struct /*VFT*/ RealmsApplyContentProgressHandler_vtbl
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

### `RealmsLoadingLevelProgressHandler`
```
struct __cppobj RealmsLoadingLevelProgressHandler : ProgressHandler
{
  std::function<void __cdecl(void)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  std::string mTitleText;
};

```

### `RealmsLoadingLevelProgressHandler_vtbl`
```
struct /*VFT*/ RealmsLoadingLevelProgressHandler_vtbl
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

### `ResourcePackCopyProgressHandler`
```
struct __cppobj ResourcePackCopyProgressHandler : ProgressHandler
{
  std::string mLevelID;
  std::future<void> mFuture;
  std::function<void __cdecl(void)> mCallback;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
};

```

### `ResourcePackCopyProgressHandler_vtbl`
```
struct /*VFT*/ ResourcePackCopyProgressHandler_vtbl
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

### `RTCReconnectHandler`
```
struct __cppobj RTCReconnectHandler : EmptyProgressHandler
{
};

```

### `RTCReconnectHandler_vtbl`
```
struct /*VFT*/ RTCReconnectHandler_vtbl
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

### `RemoteStorageProviderSyncProgressHandler::onStart::__l2::<lambda_802c14b612ba89aa0eb1f60f22a3a7c7>`
```
struct __cppobj RemoteStorageProviderSyncProgressHandler::onStart::__l2::<lambda_802c14b612ba89aa0eb1f60f22a3a7c7>
{
  RemoteStorageProviderSyncProgressHandler *const __this;
};

```

### `RealmsCreateScreenController`
```
struct __cppobj RealmsCreateScreenController : MainMenuScreenController
{
  bool mDirty;
  bool mCheckedTOS;
  bool mIsValidRealmName;
  bool mCheckUnfulfilledPurchase;
  bool mOverridePurchaseIntent;
  bool mPurchaseInProgress;
  bool mCoinPurchaseInProgress;
  const bool mIsSubController;
  const RealmsPurchaseIntent mPurchaseIntent;
  std::string mWorldName;
  std::string mSubscriptionId;
  const RealmsOfferType mOfferType;
  RealmsOfferPeriod mOfferPeriod;
  RealmsOfferTier mOfferTier;
  bool mPurchaseDisabledDueToStoreVersion;
  const bool mTrialAvailable;
  const bool mHasClub;
  const bool mIsFromRealmsPDP;
  std::function<void __cdecl(void)> mActionAfterCreate;
  Realms::World mNewWorld;
  std::function<void __cdecl(Realms::World &)> mRealmCreatedCallback;
};

```

### `RealmsCreateScreenController_vtbl`
```
struct /*VFT*/ RealmsCreateScreenController_vtbl
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

### `RecipeIngredientSet`
```
struct __cppobj RecipeIngredientSet
{
  std::unordered_map<int,int> mSet;
};

```

### `ResourcePacksScreenController`
```
struct __cppobj ResourcePacksScreenController : SettingsScreenControllerBase
{
  ContentManager *mContentManager;
  ContentView *mSelectedContentView;
  ContentView *mAvailableContentView;
  ContentView *mRealmsContentView;
  ContentView *mInvalidContentView;
  ContentView *mUnownedContentView;
  _BYTE mScope[1];
  unsigned __int64 mSelectedId;
  std::shared_ptr<bool> mExistanceTracker;
  ResourcePacksScreenController *mOtherPacksTabController;
  _BYTE mContentType[8];
  unsigned int mIconIndex;
  bool mChooseFromActive;
  InvalidPacksFilterGroup mInvalidPacksFilter;
  std::vector<ResourceLocation> mInvalidPacks;
  std::unique_ptr<DlcUIWrapper> mDlcUIWrapper;
  MultiplayerLockState *mMultiplayerState;
  const std::chrono::duration<__int64,std::ratio<1,1> > mTwoSecondInterval;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastIconCycle;
  _BYTE mReloadFlag[4];
  bool mRepopulateReports;
  bool mRepopulatingReports;
  bool mSelectedExpanded;
  bool mAvailableExpanded;
  bool mRealmsExpanded;
  bool mUnownedExpanded;
  bool mShowedDataWarning;
  bool mGetInitialSelectedPacks;
  std::vector<PackIdVersion> mInitialSelectedPacks;
  bool mShowedAchiementWarning;
  std::function<bool __cdecl(void)> mIsWorldTemplateOptionLockedCallback;
};

```

### `ResourcePacksScreenController_vtbl`
```
struct /*VFT*/ ResourcePacksScreenController_vtbl
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

### `RandomizableBlockActorContainer`
```
struct __cppobj RandomizableBlockActorContainer : RandomizableBlockActorContainerBase, Container
{
};

```

### `ReceiptData_Amazon`
```
struct __cppobj ReceiptData_Amazon
{
  std::string mUserId;
  std::string mReceiptId;
};

```

### `ReceiptData_Apple`
```
struct __cppobj ReceiptData_Apple
{
  std::string mTransactionId;
  std::string mReceiptData;
};

```

### `ReceiptFulfillment::ReceiptData`
```
struct __cppobj __declspec(align(8)) ReceiptFulfillment::ReceiptData
{
  ReceiptData_Google mGoogle;
  ReceiptData_Amazon mAmazon;
  ReceiptData_Apple miOS;
  bool mIsFulfilled;
};

```

### `ReceiptFulfillment`
```
struct __cppobj ReceiptFulfillment
{
  std::vector<ReceiptFulfillment::ReceiptData> mReceipts;
};

```

### `RatingPromptController`
```
struct __cppobj RatingPromptController : ClientInstanceScreenController
{
  const std::string mTitleId;
  const std::string mImage;
  const std::string mButtonName;
};

```

### `RatingPromptController_vtbl`
```
struct /*VFT*/ RatingPromptController_vtbl
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

### `ReceiptDetailsAmazonAppStore`
```
struct __cppobj ReceiptDetailsAmazonAppStore : SendReceiptDetails
{
  const std::string mUserId;
  const std::string mReceiptId;
};

```

### `ReceiptDetailsAmazonAppStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsAmazonAppStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsGooglePlayStore`
```
struct __cppobj ReceiptDetailsGooglePlayStore : SendReceiptDetails
{
  const std::string mPackageName;
  const std::string mPurchaseToken;
};

```

### `ReceiptDetailsGooglePlayStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsGooglePlayStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsAppleAppStore`
```
struct __cppobj ReceiptDetailsAppleAppStore : SendReceiptDetails
{
  const std::string mTransactionId;
  const std::string mAppReceipt;
};

```

### `ReceiptDetailsAppleAppStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsAppleAppStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsOculusStore`
```
struct __cppobj ReceiptDetailsOculusStore : SendReceiptDetails
{
  const std::string mUserToken;
  const unsigned __int64 mPurchaseId;
  const std::string mPlatform;
};

```

### `ReceiptDetailsOculusStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsOculusStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsWindowsStore`
```
struct __cppobj ReceiptDetailsWindowsStore : SendReceiptDetails
{
  const std::string mTransactionId;
  const std::string mAppReceipt;
};

```

### `ReceiptDetailsWindowsStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsWindowsStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsSwitch`
```
struct __cppobj __declspec(align(8)) ReceiptDetailsSwitch : SendReceiptDetails
{
  const std::string mPrice;
  const std::string mProductId;
  const std::string mTenant;
  const std::string mInventory;
  const CoinReceiptValidationEndpoint mEndpoint;
};

```

### `ReceiptDetailsSwitch_vtbl`
```
struct /*VFT*/ ReceiptDetailsSwitch_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsOneStore`
```
struct __cppobj __declspec(align(8)) ReceiptDetailsOneStore : SendReceiptDetails
{
  const std::string mActor;
  const std::string mInventory;
  const std::string mAccessToken;
  const std::string mWSIDKey;
  const bool mSubscription;
};

```

### `ReceiptDetailsOneStore_vtbl`
```
struct /*VFT*/ ReceiptDetailsOneStore_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `ReceiptDetailsPS4Store`
```
struct __cppobj ReceiptDetailsPS4Store : SendReceiptDetails
{
  const int mEnvironment;
  const std::string mUserId;
  const std::string mAuthCode;
  const std::string mOfflineAuthCode;
  const std::string mRedirectUri;
  const std::string mServiceLabel;
};

```

### `ReceiptDetailsPS4Store_vtbl`
```
struct /*VFT*/ ReceiptDetailsPS4Store_vtbl
{
  void (__fastcall *~SendReceiptDetails)(SendReceiptDetails *this);
};

```

### `RealmsIsDisabledScreenController`
```
struct __cppobj __declspec(align(8)) RealmsIsDisabledScreenController : MinecraftScreenController
{
  bool mHasShownPopup;
};

```

### `RealmsIsDisabledScreenController_vtbl`
```
struct /*VFT*/ RealmsIsDisabledScreenController_vtbl
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

### `RealmsIsDisabledScreenController::onOpen::__l5::<lambda_91b9ff23160b4f3da9aab74dddb27186>`
```
struct __cppobj RealmsIsDisabledScreenController::onOpen::__l5::<lambda_91b9ff23160b4f3da9aab74dddb27186>
{
  std::weak_ptr<RealmsIsDisabledScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_dialogNotSignedIn::__l2::<lambda_49c4de3d144526248868f5a46965bb4e>`
```
struct __cppobj RealmsCreateScreenController::_dialogNotSignedIn::__l2::<lambda_49c4de3d144526248868f5a46965bb4e>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_promptForCoinsPurchaseFulfillment::__l2::<lambda_19594e823628c853cfd91f333e3e6917>::()::__l8::<lambda_6758755b2194d589eb256ffff48ea360>`
```
struct __cppobj RealmsCreateScreenController::_promptForCoinsPurchaseFulfillment::__l2::<lambda_19594e823628c853cfd91f333e3e6917>::()::__l8::<lambda_6758755b2194d589eb256ffff48ea360>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_promptForUnknownIntentOverrideAndFulfillment::__l2::<lambda_37443944b81aba01a2a71a7abe4683e0>`
```
struct __cppobj RealmsCreateScreenController::_promptForUnknownIntentOverrideAndFulfillment::__l2::<lambda_37443944b81aba01a2a71a7abe4683e0>
{
  RealmsCreateScreenController *const __this;
  std::weak_ptr<Purchase> purchase;
};

```

### `RealmsCreateScreenController::_promptForXuidOverrideAndFulfillment::__l2::<lambda_6169e7c135f3a9b162b5092011e1ee52>`
```
struct __cppobj RealmsCreateScreenController::_promptForXuidOverrideAndFulfillment::__l2::<lambda_6169e7c135f3a9b162b5092011e1ee52>
{
  RealmsCreateScreenController *const __this;
  std::weak_ptr<Purchase> purchase;
};

```

### `RealmsCreateScreenController::_promptForAutoFulfillment::__l2::<lambda_01d23886e2383bbaadc1a2bb2ab844d7>`
```
struct __cppobj RealmsCreateScreenController::_promptForAutoFulfillment::__l2::<lambda_01d23886e2383bbaadc1a2bb2ab844d7>
{
  RealmsCreateScreenController *const __this;
  std::weak_ptr<Purchase> purchase;
};

```

### `RealmsCreateScreenController::_promptForIntentMismatchOverride::__l2::<lambda_c8e5752f6e8beaed2bb48fafbca96f5b>`
```
struct __cppobj RealmsCreateScreenController::_promptForIntentMismatchOverride::__l2::<lambda_c8e5752f6e8beaed2bb48fafbca96f5b>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>`
```
struct __cppobj RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>::()::__l5::<lambda_e19a722957cb00f37fd0b160b6fd8089>`
```
struct __cppobj RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>::()::__l5::<lambda_e19a722957cb00f37fd0b160b6fd8089>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>`
```
struct __cppobj RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
  RealmsStoreOffer realmsStoreOffer;
};

```

### `RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>::()::__l20::<lambda_11590451ccabfaec39636f272c4ed76b>`
```
struct __cppobj RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>::()::__l20::<lambda_11590451ccabfaec39636f272c4ed76b>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>::()::__l12::<lambda_52edd7fc4f405b8d2e227d918cc230fc>`
```
struct __cppobj RealmsCreateScreenController::purchasesRealmsFromMarketplace::__l14::<lambda_86b57457307602f0ce18c0cc5f63a472>::()::__l12::<lambda_52edd7fc4f405b8d2e227d918cc230fc>
{
  std::shared_ptr<RealmsCreateScreenController> sharedThis;
};

```

### `RealmsCreateScreenController::_fulfillPriorRealmPurchase::__l2::<lambda_f13f0a2afb32cc0e58703534f5540fa8>`
```
struct __cppobj RealmsCreateScreenController::_fulfillPriorRealmPurchase::__l2::<lambda_f13f0a2afb32cc0e58703534f5540fa8>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
  std::weak_ptr<Purchase> purchase;
};

```

### `RealmsCreateScreenController::_verifyAppStoreReady::__l10::<lambda_a9a82af7daade8e888113d0905d8b9e8>`
```
struct __cppobj RealmsCreateScreenController::_verifyAppStoreReady::__l10::<lambda_a9a82af7daade8e888113d0905d8b9e8>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
  std::function<void __cdecl(void)> readyCallback;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_7cb1556f90d57147fdd7fcf1d97c6179>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_7cb1556f90d57147fdd7fcf1d97c6179>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_e9c9e93930d2ba4bb8f0b5e1c32b56db>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_e9c9e93930d2ba4bb8f0b5e1c32b56db>
{
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_dbf6ed11597cf0ca1f0874647e83e901>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_dbf6ed11597cf0ca1f0874647e83e901>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_8dee04cc31005a0bd01040df2e55910f>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_8dee04cc31005a0bd01040df2e55910f>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_eb6d102e4876bf77e7b6320b57ff7b9c>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_eb6d102e4876bf77e7b6320b57ff7b9c>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_32323263c8f5ba33afde27a17911e4e0>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_32323263c8f5ba33afde27a17911e4e0>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_f5ae2cbf6b378a95661dfc6c16d462be>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_f5ae2cbf6b378a95661dfc6c16d462be>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_95e1f4f89903746bf4d934b566113d25>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_95e1f4f89903746bf4d934b566113d25>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_a96dab5df0360f5429b6ff03af2d6829>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_a96dab5df0360f5429b6ff03af2d6829>
{
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_ff17b8e8868886e16ec163a1181b035e>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_ff17b8e8868886e16ec163a1181b035e>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_1a698fb50414c7da209e8a96ee5f0d5e>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_1a698fb50414c7da209e8a96ee5f0d5e>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_417af8467842cae7352aa84fd662624d>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_417af8467842cae7352aa84fd662624d>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_153309eb31795f88cbd1667b9c2451b2>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_153309eb31795f88cbd1667b9c2451b2>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_1142c2590f4bdeb221955e74799a197f>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_1142c2590f4bdeb221955e74799a197f>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerBindings::__l2::<lambda_a742977d0c3b0608a0f606dcb98d4101>`
```
struct __cppobj RealmsCreateScreenController::_registerBindings::__l2::<lambda_a742977d0c3b0608a0f606dcb98d4101>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l5::<lambda_3e1db9bdc28851e9d6909fccbe8b4e44>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l5::<lambda_3e1db9bdc28851e9d6909fccbe8b4e44>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_8652b58e8e09d949c337a74bcca6d672>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_8652b58e8e09d949c337a74bcca6d672>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_a4bd6024310587f1fe6efb08eca0ffb2>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_a4bd6024310587f1fe6efb08eca0ffb2>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_4699a29b6788367a1e0e6a67f82798a6>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_4699a29b6788367a1e0e6a67f82798a6>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_fcda00fe6c46b76c82d0cec43719f0c1>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_fcda00fe6c46b76c82d0cec43719f0c1>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_78abeb07cdb8590cd50b98cdd0378b6d>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_78abeb07cdb8590cd50b98cdd0378b6d>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_05ceb3ca150a8bdbf72f46a37dcb7965>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_05ceb3ca150a8bdbf72f46a37dcb7965>
{
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_b0b538b8aa9dfd0e212e9c4db5c99469>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_b0b538b8aa9dfd0e212e9c4db5c99469>
{
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_d6b153785a57dbe6e64680084803218a>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_d6b153785a57dbe6e64680084803218a>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_0da9bb956e87b6539e13a89ca4386906>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_0da9bb956e87b6539e13a89ca4386906>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_0da9bb956e87b6539e13a89ca4386906>::()::__l2::<lambda_4c50fe294623491f44cacb2859702340>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_0da9bb956e87b6539e13a89ca4386906>::()::__l2::<lambda_4c50fe294623491f44cacb2859702340>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_37583b8e767d69dcdd346126e3507f12>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_37583b8e767d69dcdd346126e3507f12>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_090840a8d3af2e85b5e2bba80cc973a3>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_090840a8d3af2e85b5e2bba80cc973a3>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l14::<lambda_7defb20c4b34e8b399ae3dca66868335>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l14::<lambda_7defb20c4b34e8b399ae3dca66868335>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l14::<lambda_7defb20c4b34e8b399ae3dca66868335>::()::__l23::<lambda_c16841c8c886a14745e126fde213bd57>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l14::<lambda_7defb20c4b34e8b399ae3dca66868335>::()::__l23::<lambda_c16841c8c886a14745e126fde213bd57>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l12::<lambda_f57b722fc0dc5b648556da9f27bc4f31>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l12::<lambda_f57b722fc0dc5b648556da9f27bc4f31>
{
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l8::<lambda_42f118de637a8da3648514c238d58a21>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_cccf5dd859a6a7636d14756f4863e950>::()::__l17::<lambda_536a4bc437c7156701ef29828a5b124e>::()::__l8::<lambda_42f118de637a8da3648514c238d58a21>
{
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_e6d0aae80acd963f3c6249d432f3c33d>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_e6d0aae80acd963f3c6249d432f3c33d>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_a1624facfb35959883f6da011d1d45f9>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_a1624facfb35959883f6da011d1d45f9>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_1e47e51c2a46c0a8db98d9931a5d6591>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_1e47e51c2a46c0a8db98d9931a5d6591>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_81923b8859ec2d7352f329d8a326d94c>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_81923b8859ec2d7352f329d8a326d94c>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_fe7dfc0099d225fd2652c9455225caf7>`
```
struct __cppobj RealmsCreateScreenController::_registerEventHandlers::__l2::<lambda_fe7dfc0099d225fd2652c9455225caf7>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::onCreation::__l11::<lambda_a994d708157ce6b245abae87ff8cbad5>`
```
struct __cppobj RealmsCreateScreenController::onCreation::__l11::<lambda_a994d708157ce6b245abae87ff8cbad5>
{
  RealmsCreateScreenController *const __this;
};

```

### `RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>::()::__l5::<lambda_e19a722957cb00f37fd0b160b6fd8089>::()::__l5::<lambda_719f5a8f7b7c4ac03d4dc60410855a29>`
```
struct __cppobj RealmsCreateScreenController::_purchaseRealm::__l2::<lambda_0d1ed9e89c860dcdeb08453fdabc0f53>::()::__l5::<lambda_e19a722957cb00f37fd0b160b6fd8089>::()::__l5::<lambda_719f5a8f7b7c4ac03d4dc60410855a29>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_fulfillPriorRealmPurchase::__l2::<lambda_f13f0a2afb32cc0e58703534f5540fa8>::()::__l5::<lambda_fb215fb8eaf50302a85bd2ef537014da>`
```
struct __cppobj RealmsCreateScreenController::_fulfillPriorRealmPurchase::__l2::<lambda_f13f0a2afb32cc0e58703534f5540fa8>::()::__l5::<lambda_fb215fb8eaf50302a85bd2ef537014da>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsCreateScreenController::_handleTransactionEvents::__l43::<lambda_9cdb631ba475e9d821220cd81569b491>`
```
struct __cppobj RealmsCreateScreenController::_handleTransactionEvents::__l43::<lambda_9cdb631ba475e9d821220cd81569b491>
{
  std::weak_ptr<RealmsCreateScreenController> weakThis;
};

```

### `RealmsPackErrorsScreenController`
```
struct __cppobj __declspec(align(8)) RealmsPackErrorsScreenController : MinecraftScreenController
{
  bool mFirstTick;
};

```

### `RealmsPackErrorsScreenController_vtbl`
```
struct /*VFT*/ RealmsPackErrorsScreenController_vtbl
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

### `RealmsPendingInvitationsScreenController`
```
struct __cppobj RealmsPendingInvitationsScreenController : MainMenuScreenController
{
  bool mDirty;
  std::vector<Realms::Invite> mPendingInvitesList;
  bool mPendingAsyncOperation;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastUpdate;
  bool mHasPendingInvites;
  bool mShowOnlyFriendInvites;
  int mFriendInvites;
};

```

### `RealmsPendingInvitationsScreenController_vtbl`
```
struct /*VFT*/ RealmsPendingInvitationsScreenController_vtbl
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

### `RealmsPlusEndedScreenController`
```
struct __cppobj RealmsPlusEndedScreenController : MinecraftScreenController
{
};

```

### `RealmsPlusEndedScreenController_vtbl`
```
struct /*VFT*/ RealmsPlusEndedScreenController_vtbl
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

### `RealmsPlusPDPScreenController::RealmsWorld`
```
struct __cppobj __declspec(align(8)) RealmsPlusPDPScreenController::RealmsWorld
{
  Realms::World world;
  bool doneLoading;
};

```

### `RealmsPlusPDPScreenController`
```
struct __cppobj RealmsPlusPDPScreenController : PurchaseEnabledScreenController
{
  RealmsPlusTabIndex mInitialTab;
  RealmsPlusTabIndex mCurrentTab;
  bool mInitialTabSelected;
  std::string mCurrentFocus;
  std::map<int,std::string> mToggleSectionNames;
  std::unique_ptr<OfferCollectionComponent> mPopularPacksCollection;
  std::shared_ptr<StoreVisualStyle> mRealmsPlusVisualStyle;
  std::string mRealmName;
  std::string mPacksLabel;
  std::string mRealmsPlusPrice;
  bool mRealmsTrialAvailableInStore;
  bool mCheckedTOS;
  bool mDirty;
  std::vector<RealmsPlusPDPScreenController::RealmsWorld> mRealmsPlusWorlds;
};

```

### `RealmsPlusPDPScreenController_vtbl`
```
struct /*VFT*/ RealmsPlusPDPScreenController_vtbl
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

### `RealmsPlusUpgradeNoticeScreenController`
```
struct __cppobj RealmsPlusUpgradeNoticeScreenController : MainMenuScreenController
{
  std::string mShowMsg;
};

```

### `RealmsPlusUpgradeNoticeScreenController_vtbl`
```
struct /*VFT*/ RealmsPlusUpgradeNoticeScreenController_vtbl
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

### `RealmsPlusViewAllPAcksScreenController`
```
struct __cppobj RealmsPlusViewAllPAcksScreenController : StoreDataDrivenScreenController
{
  bool mDirty;
  std::shared_ptr<StoreVisualStyle> mRealmsPlusVisualStyle;
};

```

### `RealmsPlusViewAllPAcksScreenController_vtbl`
```
struct /*VFT*/ RealmsPlusViewAllPAcksScreenController_vtbl
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

### `RealmsSettingsScreenController::SaveStatusTracker`
```
struct RealmsSettingsScreenController::SaveStatusTracker
{
  bool mRealmsSaveFinished;
  bool mRealmsSaveSuccess;
  bool mClubsSaveFinished;
};

```

### `RealmsSettingsScreenController::RealmsVersionState`
```
struct __cppobj RealmsSettingsScreenController::RealmsVersionState
{
  int mPageIndex;
  bool mAwaitingResponse;
  std::string mPendingRef;
  std::string mLastFilter;
  Realms::ConfigInfo mConfigInfo;
  std::vector<Realms::ConfigInfo::Version> mFilteredVersions;
  Realms::ConfigInfo::Version mMatchingVersion;
};

```

### `RealmsSettingsScreenController::DelayedStandardModalScreenData`
```
struct __cppobj RealmsSettingsScreenController::DelayedStandardModalScreenData
{
  ModalScreenData screenData;
  std::function<void __cdecl(enum ModalScreenButtonId)> callback;
};

```

### `RealmsSettingsScreenController`
```
struct __cppobj RealmsSettingsScreenController : SettingsScreenControllerBase
{
  Clubs::ClubModel mClubModel;
  Clubs::ClubModel mUpdatedClubModel;
  Realms::World mWorld;
  Realms::World mUpdatedWorld;
  Realms::SubscriptionInfo mSubscription;
  bool mIsInitialWorldLoadComplete;
  bool mRefreshWorldAndSubscriptionInfoOnOpen;
  RealmsSettingsScreenController::PurchaseIntent mPurchaseIntent;
  std::string mSelectedSectionTitle;
  std::shared_ptr<RealmsAllowListScreenController> mRealmsAllowListScreenController;
  int mActiveTabIndex;
  bool mHasSubscriptionInfoBeenReceived;
  bool mRefreshScreen;
  bool mIsReplacingWithBackup;
  bool mHasLoadedBackups;
  bool mDidBackupsReceiveNetworkError;
  bool mRealmsSelectedContentInitialized;
  bool mDidReplaceWorld;
  bool mRefreshingWorldInfo;
  std::unique_ptr<PlatformMultiplayerRestrictions> mPlatformMultiplayerRestrictions;
  ContentManager *mContentManager;
  Realms::ContentService *mContentService;
  std::unique_ptr<ContentManagerContext> mContentManagerContext;
  MultiplayerLockState mMultiplayerState;
  std::vector<Realms::Content> mAppliedContent;
  PackManagerContentSource *mRealmContentSource;
  unsigned __int64 mLoadedItemsCount;
  RealmsSettingsScreenController::SaveStatusTracker mSaveStatusTracker;
  std::vector<Realms::Backup> mBackups;
  unsigned __int64 mRestoreBackupIndex;
  RealmsSettingsScreenController::RealmsVersionState mRealmsVersionState;
  std::vector<RealmsSettingsScreenController::DelayedStandardModalScreenData> mDelayedStandardModalPopups;
};

```

### `RealmsSettingsScreenController_vtbl`
```
struct /*VFT*/ RealmsSettingsScreenController_vtbl
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

### `RealmsWarningScreenController`
```
struct __cppobj __declspec(align(8)) RealmsWarningScreenController : DisconnectScreenController
{
  Realms::World mWorld;
  std::string mIP;
  int mPort;
};

```

### `RealmsWarningScreenController_vtbl`
```
struct /*VFT*/ RealmsWarningScreenController_vtbl
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
  ui::ViewRequest (__fastcall *_processLeaveScreen)(DisconnectScreenController *this);
};

```

### `ResourcePackApplyingScreenController`
```
struct __cppobj __declspec(align(8)) ResourcePackApplyingScreenController : MainMenuScreenController
{
  std::function<void __cdecl(MinecraftScreenModel &)> mApplyPacks;
  bool mHasTicked;
};

```

### `ResourcePackApplyingScreenController_vtbl`
```
struct /*VFT*/ ResourcePackApplyingScreenController_vtbl
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

### `ResourcePacksScreenController::_showMissingDependencyMessage::__l2::<lambda_68016cd6d4204650a78dc69ac1444e51>`
```
struct __cppobj ResourcePacksScreenController::_showMissingDependencyMessage::__l2::<lambda_68016cd6d4204650a78dc69ac1444e51>
{
  std::weak_ptr<ResourcePacksScreenController> weakThis;
  ContentView *contentView;
  _BYTE fromPacks[4];
  int index;
};

```

### `ResourcePacksScreenController::_handleMovePackResult::__l9::<lambda_4838fa90556d940c60db70883a75e01a>`
```
struct __cppobj ResourcePacksScreenController::_handleMovePackResult::__l9::<lambda_4838fa90556d940c60db70883a75e01a>
{
  std::weak_ptr<ResourcePacksScreenController> weakThis;
  ContentView *contentView;
  int collectionIndex;
  _BYTE packListType[4];
};

```

### `ResourcePacksScreenController::_handleStoreClicked::__l2::<lambda_18a7274252163e040322ba79c64b5c8f>`
```
struct __cppobj ResourcePacksScreenController::_handleStoreClicked::__l2::<lambda_18a7274252163e040322ba79c64b5c8f>
{
  ResourcePacksScreenController *const __this;
  const int index;
  ContentView *const contentView;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_9f1d28b6defac57b4b8fc26b2e90bdeb>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_9f1d28b6defac57b4b8fc26b2e90bdeb>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_cd32d9a7881102aee155e8615b1bc91a>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_cd32d9a7881102aee155e8615b1bc91a>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_82fe605cdb26dfaba82fdce8efc7c35a>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_82fe605cdb26dfaba82fdce8efc7c35a>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_4e326674807790f1ee8c52d682ca04a8>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_4e326674807790f1ee8c52d682ca04a8>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_4379db313652eb9ecabc84fcbf0e58da>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_4379db313652eb9ecabc84fcbf0e58da>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_60d87b2780179b4c39931e532eb71c55>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_60d87b2780179b4c39931e532eb71c55>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_41c50ce286cd02729828100fcdb5dc41>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_41c50ce286cd02729828100fcdb5dc41>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_efb19a72c45695ecd8dee8b0d081f25e>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_efb19a72c45695ecd8dee8b0d081f25e>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_70fa9be510c69ef0a37736ef54aff823>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_70fa9be510c69ef0a37736ef54aff823>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5cd3091eb5d6b1553def9da3de0b7f23>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5cd3091eb5d6b1553def9da3de0b7f23>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_1ef5201307cecae9efaa0ee82454b545>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_1ef5201307cecae9efaa0ee82454b545>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_94615d1a0019cadbaaeaf4384006b596>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_94615d1a0019cadbaaeaf4384006b596>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a40036f68d4d697bd0f1ed7630f2d21b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a40036f68d4d697bd0f1ed7630f2d21b>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_d5ea43dab69aedb0fa8129e5b40913c9>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_d5ea43dab69aedb0fa8129e5b40913c9>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c5972a44cb5dc8b04a3afdcb7c8ebaa9>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c5972a44cb5dc8b04a3afdcb7c8ebaa9>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a7f0c08fc1a6f559c156e311ca622222>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a7f0c08fc1a6f559c156e311ca622222>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6a36165c3e9de924d3c9c78b66eabb79>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6a36165c3e9de924d3c9c78b66eabb79>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a1f76a06f608a02f6c1a4001f92e8128>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a1f76a06f608a02f6c1a4001f92e8128>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_e0d98ff0a17a5b8d338956a95746a891>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_e0d98ff0a17a5b8d338956a95746a891>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2a9ac69a54bc163d2c5f36ee789c1f08>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2a9ac69a54bc163d2c5f36ee789c1f08>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_ff87131b6988e806ca76434b7dc319ee>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_ff87131b6988e806ca76434b7dc319ee>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_e85a86e3cde3bb7b2e9d9f788a859cb4>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_e85a86e3cde3bb7b2e9d9f788a859cb4>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_770198d95e2765972608490591b57eee>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_770198d95e2765972608490591b57eee>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_ffdaa6a541be1b6531f844902b2573e6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_ffdaa6a541be1b6531f844902b2573e6>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_ebeab8e427b8541de748830fb3ffbe26>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_ebeab8e427b8541de748830fb3ffbe26>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_660d36e1b08d7a233a0d2f640c6eccec>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_660d36e1b08d7a233a0d2f640c6eccec>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_ad3cf9fcd844e7db741a73e63cb799cf>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_ad3cf9fcd844e7db741a73e63cb799cf>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_69256562da7be379f0f45afa89f8ec56>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_69256562da7be379f0f45afa89f8ec56>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5c10502b4ce214e8db294b4ecc98ee22>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5c10502b4ce214e8db294b4ecc98ee22>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_0efb9525dda217be6361ddf75e3fb475>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_0efb9525dda217be6361ddf75e3fb475>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_318f49c0311c4d4efa235778bd99cebe>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_318f49c0311c4d4efa235778bd99cebe>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_74ef7c21ca4758b097ae854d2c65d419>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_74ef7c21ca4758b097ae854d2c65d419>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5de8603f24ab2eb57800e26216b8918b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5de8603f24ab2eb57800e26216b8918b>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5efaf7282317d71ff6ce0d615ae08ae4>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5efaf7282317d71ff6ce0d615ae08ae4>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_40b309e61f0adf45764e054ed480bf67>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_40b309e61f0adf45764e054ed480bf67>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b6bd7f2e7f255c959e5fe0ef625947a7>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_b6bd7f2e7f255c959e5fe0ef625947a7>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_398b53872cee422848a3121f69225a21>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_398b53872cee422848a3121f69225a21>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_db84f6846bb10b397979b820371d373b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_db84f6846bb10b397979b820371d373b>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_3b546557dcd05493f7d2576ba76156e8>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_3b546557dcd05493f7d2576ba76156e8>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a3c10bf528a3e924ce3d91e0ae87181d>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a3c10bf528a3e924ce3d91e0ae87181d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_db88ef23ddad990e408365adf1f59d14>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_db88ef23ddad990e408365adf1f59d14>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6b4812b74eba2101bb53e87f7b506d67>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6b4812b74eba2101bb53e87f7b506d67>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a303a18a3815da4d52b9088dcf408865>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a303a18a3815da4d52b9088dcf408865>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_1785cb5b330952533326a2539d30b0ad>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_1785cb5b330952533326a2539d30b0ad>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_9f7d2494829311b5ae29671fca714377>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_9f7d2494829311b5ae29671fca714377>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_546d96c47af02ac256ec29acfb00639f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_546d96c47af02ac256ec29acfb00639f>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_73861affa6a31431d65dbace70921589>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_73861affa6a31431d65dbace70921589>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_498c31185d39c6df67dcce999fd580dd>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_498c31185d39c6df67dcce999fd580dd>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_439fdb6eb1c3d4824eb3a6b584ff46b2>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_439fdb6eb1c3d4824eb3a6b584ff46b2>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c217a578226da2a694f7419575bbd8e1>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c217a578226da2a694f7419575bbd8e1>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b1e5e97b9ead07c7b7664706d7899fa1>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_b1e5e97b9ead07c7b7664706d7899fa1>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_879a788195935f44302f8b705713b5f1>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_879a788195935f44302f8b705713b5f1>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5224da5990e33fbcb76d26069c17b664>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5224da5990e33fbcb76d26069c17b664>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_52ca10f120c2f274ae564a0787258042>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_52ca10f120c2f274ae564a0787258042>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_904418df90733e2e08f2e5fe0621311f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_904418df90733e2e08f2e5fe0621311f>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_9051314bced3810e8bfaf9ead4c7ef89>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_9051314bced3810e8bfaf9ead4c7ef89>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_3cd47e646c3ff2757abdb29a85965e49>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_3cd47e646c3ff2757abdb29a85965e49>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b6448dc5f67d9131527f4ff743a0dc6a>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_b6448dc5f67d9131527f4ff743a0dc6a>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_8c77c198a53343f2cd31d4e6560eb88b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_8c77c198a53343f2cd31d4e6560eb88b>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c05b0755fd1ad56b1d04e9c642d3c0d8>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c05b0755fd1ad56b1d04e9c642d3c0d8>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c890dfa982b0aebb2c6b160426e1ad7f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c890dfa982b0aebb2c6b160426e1ad7f>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_7bed5c883753ba9cade5e527b883b74c>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_7bed5c883753ba9cade5e527b883b74c>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_83977d87385ce27e9284adfb91aabee6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_83977d87385ce27e9284adfb91aabee6>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_f05bc6ae4c9a4c8b128dcd865e78c6e6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_f05bc6ae4c9a4c8b128dcd865e78c6e6>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a5ea4cab85e5a62cbd1cf9b4706f8b6e>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a5ea4cab85e5a62cbd1cf9b4706f8b6e>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_7e82daee93d17aa9d65e0eedd65f6fce>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_7e82daee93d17aa9d65e0eedd65f6fce>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2e9ce180368879791739ed1250fc585f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2e9ce180368879791739ed1250fc585f>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_bdcb751c89308555efdfd5cee70894bf>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_bdcb751c89308555efdfd5cee70894bf>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5ef942544f33d029c9b9bd303176216a>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5ef942544f33d029c9b9bd303176216a>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_9cddcdee142e0a740b167ba4f090ab42>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_9cddcdee142e0a740b167ba4f090ab42>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2f582f149861ac249bac1ee91f7d3aaa>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2f582f149861ac249bac1ee91f7d3aaa>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_31226192161471495ee3811c0b907591>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_31226192161471495ee3811c0b907591>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_e7836f03f810421d4dc5eef735111ae8>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_e7836f03f810421d4dc5eef735111ae8>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_47c8552354789f2197189143edf81bb3>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_47c8552354789f2197189143edf81bb3>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_bbdfc24419e609319fb6ac8767aaafc9>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_bbdfc24419e609319fb6ac8767aaafc9>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c72a721afb13e9bbcf75c371ffc49338>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c72a721afb13e9bbcf75c371ffc49338>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6bf20777a0f863b0b99c6c6d573979f2>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6bf20777a0f863b0b99c6c6d573979f2>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2672e83e262f21d7e950906bae6ca304>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2672e83e262f21d7e950906bae6ca304>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_d6891dadfdbbeb0801d06703c62a711c>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_d6891dadfdbbeb0801d06703c62a711c>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_18e66ef41abea766873edf7303da8a09>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_18e66ef41abea766873edf7303da8a09>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_fcc2dbdeb4a705ff749438e94cb155a0>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_fcc2dbdeb4a705ff749438e94cb155a0>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_f81eef3fccf9c3866500a6ce54b677b2>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_f81eef3fccf9c3866500a6ce54b677b2>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a03e0552884ab980b0d49b6de08d6c27>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a03e0552884ab980b0d49b6de08d6c27>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a928f800fcc923b655b93987d41f1cdb>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a928f800fcc923b655b93987d41f1cdb>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_cdbd24bcd159bde193905cef7247ff40>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_cdbd24bcd159bde193905cef7247ff40>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_d350aa55b8c449f99493847f139a6106>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_d350aa55b8c449f99493847f139a6106>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_e64678245a76b2aaad481df690ce2cfc>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_e64678245a76b2aaad481df690ce2cfc>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_57ca7649c72ebf6de7a95469e089cf66>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_57ca7649c72ebf6de7a95469e089cf66>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_64ff94f80c0a714a19caa82ae859d3e7>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_64ff94f80c0a714a19caa82ae859d3e7>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_74cdc4c423a028b46d35af546488e3dc>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_74cdc4c423a028b46d35af546488e3dc>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_8b0099d4ed05864148b6c231a572a218>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_8b0099d4ed05864148b6c231a572a218>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_04c045e7a7c0fbddbb997af22e41377f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_04c045e7a7c0fbddbb997af22e41377f>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6f8fd6585214237f593debae9ecbdb2b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6f8fd6585214237f593debae9ecbdb2b>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2d8e731fc2b901ff2b3ac779f597a224>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2d8e731fc2b901ff2b3ac779f597a224>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_77d956c16019e5fbba40a3c169617fa0>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_77d956c16019e5fbba40a3c169617fa0>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b498746e8d1bc594264e8c9c887e10cc>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_b498746e8d1bc594264e8c9c887e10cc>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c16fa4938635a723848e23af8f358c25>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c16fa4938635a723848e23af8f358c25>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_817e48594e8e7cd28f96cf772e1fc31e>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_817e48594e8e7cd28f96cf772e1fc31e>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_347fadb171dd9b36cb90cfa66f6677d4>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_347fadb171dd9b36cb90cfa66f6677d4>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_afaa93e8f5f4118961d0d210d447e1fd>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_afaa93e8f5f4118961d0d210d447e1fd>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_b767120acde043a7aa217bd979a8517d>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_b767120acde043a7aa217bd979a8517d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_10b554bd5a694a1a4c18b16bb9db4202>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_10b554bd5a694a1a4c18b16bb9db4202>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_1f1dee47c77bd61ed9deac26108098f6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_1f1dee47c77bd61ed9deac26108098f6>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_c7c57e018cdd293ae934f302354b05a6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_c7c57e018cdd293ae934f302354b05a6>
{
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5dd3068c970b669eaa38a550576af5cc>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5dd3068c970b669eaa38a550576af5cc>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a8c99382a2aecb0f3056bc4232754359>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a8c99382a2aecb0f3056bc4232754359>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_93a614999ac4280907a5d49643d59f8a>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_93a614999ac4280907a5d49643d59f8a>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_bb75d1b09e802b14700da764d03419b2>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_bb75d1b09e802b14700da764d03419b2>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6bea0d6a1622b3ddc37206d62b558b28>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6bea0d6a1622b3ddc37206d62b558b28>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a6076b3cb256b285962c385a533b9f6b>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a6076b3cb256b285962c385a533b9f6b>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6efff4b7548039309e86f06a9d053a22>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6efff4b7548039309e86f06a9d053a22>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_432aa4711d6e4c8c681744d030af8b6f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_432aa4711d6e4c8c681744d030af8b6f>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_893e4eabd2566ac0cd92f57c11f808de>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_893e4eabd2566ac0cd92f57c11f808de>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2388855566e0c1f9d2a75251afa00c17>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2388855566e0c1f9d2a75251afa00c17>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_ee74b22669956b10467469655c1dd82c>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_ee74b22669956b10467469655c1dd82c>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_f0b555414c3418547c2910424fcd44d6>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_f0b555414c3418547c2910424fcd44d6>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_32485be49d39f8501fc0afbea558cb7f>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_32485be49d39f8501fc0afbea558cb7f>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_71a1c8b4627f41e553a555f15b422f4e>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_71a1c8b4627f41e553a555f15b422f4e>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_410fd819828430747692ad438af98eeb>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_410fd819828430747692ad438af98eeb>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_1fb000650eae6403d644c65047fb31d3>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_1fb000650eae6403d644c65047fb31d3>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5a3cc1f793b70610edd40722e0b05885>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5a3cc1f793b70610edd40722e0b05885>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_5514397df07775d916547d6488f8e2e3>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_5514397df07775d916547d6488f8e2e3>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_3fb95a75daf8cb4b57bd953481bb79ee>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_3fb95a75daf8cb4b57bd953481bb79ee>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_a204854407df1ca313ce3b2ce9002d2e>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_a204854407df1ca313ce3b2ce9002d2e>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_62780bc624f29a3c239e1de386e8eff0>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_62780bc624f29a3c239e1de386e8eff0>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_3c6a584a64e2ab864a04e3de051ba425>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_3c6a584a64e2ab864a04e3de051ba425>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_2be56d4227cb7e91678bb529f1c424f9>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_2be56d4227cb7e91678bb529f1c424f9>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_dac3988e41a3151896c29cc644d0bcce>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_dac3988e41a3151896c29cc644d0bcce>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_49071401b604dc81f64d44ffaf15c2ce>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_49071401b604dc81f64d44ffaf15c2ce>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_1f9c10ba2afa7584acb7e9872b052345>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_1f9c10ba2afa7584acb7e9872b052345>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_4c414e92edbc1022149d776d75d4ef20>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_4c414e92edbc1022149d776d75d4ef20>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_6f03304875753f9e0ec08b8ac17995a3>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_6f03304875753f9e0ec08b8ac17995a3>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_8885e86dba9146f8f4fe6d7b2fcb0fe9>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_8885e86dba9146f8f4fe6d7b2fcb0fe9>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_59eb0d3a540847c42601a1be230b7c64>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_59eb0d3a540847c42601a1be230b7c64>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_935ca1203dd3263f55cb9797736f58fe>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_935ca1203dd3263f55cb9797736f58fe>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_8b182ecd67e4f7b32f74d10c9c5367ba>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_8b182ecd67e4f7b32f74d10c9c5367ba>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_0365e5170c0e19294114ee128bb8cc4d>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_0365e5170c0e19294114ee128bb8cc4d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerBindings::__l2::<lambda_280ae34503d590adb08b45522cc86cba>`
```
struct __cppobj ResourcePacksScreenController::_registerBindings::__l2::<lambda_280ae34503d590adb08b45522cc86cba>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>::()::__l2::<lambda_12072569e3382c1abfb4dfb3cdfd4e08>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>::()::__l2::<lambda_12072569e3382c1abfb4dfb3cdfd4e08>
{
  std::weak_ptr<ResourcePacksScreenController> weakThis;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>::()::__l2::<lambda_12072569e3382c1abfb4dfb3cdfd4e08>::()::__l5::<lambda_4559f3748511fc8eabc7559ee2f9c096>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7944559eeacef785a0689e1a09553d2e>::()::__l2::<lambda_12072569e3382c1abfb4dfb3cdfd4e08>::()::__l5::<lambda_4559f3748511fc8eabc7559ee2f9c096>
{
  const PackIdVersion *identity;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_1ca277a2dec80ddb68968ce8fdc5e74d>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_1ca277a2dec80ddb68968ce8fdc5e74d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_47bc20beb178fa6b0822119c1d9ac573>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_47bc20beb178fa6b0822119c1d9ac573>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_d76ad30b9d24973f9847dae8e5605587>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_d76ad30b9d24973f9847dae8e5605587>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_903cbd8b8025a7aea10db065c2a980d2>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_903cbd8b8025a7aea10db065c2a980d2>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_549758c8187bdbc88d90d65b8d61f9ce>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_549758c8187bdbc88d90d65b8d61f9ce>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_84f9a0daf86a63ebcce7225783838cb3>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_84f9a0daf86a63ebcce7225783838cb3>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_b1f2730e58fd4af073cb2498d5393658>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_b1f2730e58fd4af073cb2498d5393658>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_25cf88d6405218db1e343d2ff7c03357>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_25cf88d6405218db1e343d2ff7c03357>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_f7453a74e2832a1e5ab86b52efd72b75>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_f7453a74e2832a1e5ab86b52efd72b75>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_dbfdef4e6d905ac90fd41dd14ae9a2bf>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_dbfdef4e6d905ac90fd41dd14ae9a2bf>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_a9daab373dc7f8a2f9a7964cc32b1571>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_a9daab373dc7f8a2f9a7964cc32b1571>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_3cddd34c999eb7b7b888f35a258575cb>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_3cddd34c999eb7b7b888f35a258575cb>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_a92582f8c1db54b0362ddb398c23706d>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_a92582f8c1db54b0362ddb398c23706d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_3df7e46b0dbefa59d3030d5f16fa1e61>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_3df7e46b0dbefa59d3030d5f16fa1e61>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_763d81f1db552ef67e4110662d402a31>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_763d81f1db552ef67e4110662d402a31>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7c7a4f3ac054b9d612d4364af8d182eb>`
```
struct __cppobj ResourcePacksScreenController::_registerEventHandlers::__l2::<lambda_7c7a4f3ac054b9d612d4364af8d182eb>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::_determineHasLockedContent::__l2::<lambda_00fb801f86ca375cda21a2613a04acb8>`
```
struct __cppobj ResourcePacksScreenController::_determineHasLockedContent::__l2::<lambda_00fb801f86ca375cda21a2613a04acb8>
{
};

```

### `ResourcePacksScreenController::_confirmationRestrictedPacksOnWorldDialog::__l2::<lambda_a922dc9add7b98afc9f450207ad23c19>`
```
struct __cppobj ResourcePacksScreenController::_confirmationRestrictedPacksOnWorldDialog::__l2::<lambda_a922dc9add7b98afc9f450207ad23c19>
{
  std::weak_ptr<ResourcePacksScreenController> weakThis;
  PackContentItem *packItem;
  ContentView *contentView;
  int collectionIndex;
  _BYTE fromType[4];
};

```

### `ResourcePacksScreenController::_confirmationRestrictedPacksOnWorldDialog::__l2::<lambda_a922dc9add7b98afc9f450207ad23c19>::()::__l13::<lambda_48afa8d627d0cfd9ff5b636ebac4db73>`
```
struct __cppobj ResourcePacksScreenController::_confirmationRestrictedPacksOnWorldDialog::__l2::<lambda_a922dc9add7b98afc9f450207ad23c19>::()::__l13::<lambda_48afa8d627d0cfd9ff5b636ebac4db73>
{
  std::shared_ptr<ResourcePacksScreenController> sharedThis;
  ContentView *contentView;
  int collectionIndex;
  _BYTE fromType[4];
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_0c8a49076c5e1e1b10653570feb33fb5>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_0c8a49076c5e1e1b10653570feb33fb5>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_39402bea2bd8d6a8f7a68540b1cf32d8>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_39402bea2bd8d6a8f7a68540b1cf32d8>
{
  InvalidPacksFilterGroup invalidFilter;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_93ee217164ab14e2c9a467ca628a4f2c>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_93ee217164ab14e2c9a467ca628a4f2c>
{
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_9395e479dc4d168dce57f10abe343f2a>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_9395e479dc4d168dce57f10abe343f2a>
{
  _BYTE type[8];
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_9aadfb2ed97d2f2e092b94f5a56b2975>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_9aadfb2ed97d2f2e092b94f5a56b2975>
{
  _BYTE type[8];
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_99a2771d72f475727d98a5bbf392a9c0>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_99a2771d72f475727d98a5bbf392a9c0>
{
  _BYTE type[8];
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_28419f576369ac8b299b2030b06e469d>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_28419f576369ac8b299b2030b06e469d>
{
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_f98818e38aff844afedd710a8bf99c96>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_f98818e38aff844afedd710a8bf99c96>
{
};

```

### `ResourcePacksScreenController::{ctor}::__l2::<lambda_00e00d17c5a6b7c298def405966c8624>`
```
struct __cppobj ResourcePacksScreenController::{ctor}::__l2::<lambda_00e00d17c5a6b7c298def405966c8624>
{
  _BYTE type[8];
  ResourcePacksScreenController *const __this;
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_87ff81da1f6fefd8c7b0d06b8e579540>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_87ff81da1f6fefd8c7b0d06b8e579540>
{
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_1a883e6ef7e947de64c5b31405006eaa>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_1a883e6ef7e947de64c5b31405006eaa>
{
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_8ad9072212df23d720f8a57a038c3405>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_8ad9072212df23d720f8a57a038c3405>
{
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_628d0c0fbcc96b8be53b389b1e81e314>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_628d0c0fbcc96b8be53b389b1e81e314>
{
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_f5220922bd32baa9c0640be7f7760e0f>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_f5220922bd32baa9c0640be7f7760e0f>
{
};

```

### `ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_0d4c2010fb7fee2c5d39aacc6f8e1deb>`
```
struct __cppobj ResourcePackApplyingScreenController::_registerBindings::__l2::<lambda_0d4c2010fb7fee2c5d39aacc6f8e1deb>
{
};

```

### `RealmsWarningScreenController::_registerEventHandlers::__l2::<lambda_ed05b11ce7a746e52f6c270cb664de5b>`
```
struct __cppobj RealmsWarningScreenController::_registerEventHandlers::__l2::<lambda_ed05b11ce7a746e52f6c270cb664de5b>
{
  RealmsWarningScreenController *const __this;
};

```

### `RealmsWarningScreenController::_registerEventHandlers::__l2::<lambda_9f05ffe502b9a4eed07995e4e9e164a4>`
```
struct __cppobj RealmsWarningScreenController::_registerEventHandlers::__l2::<lambda_9f05ffe502b9a4eed07995e4e9e164a4>
{
  RealmsWarningScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_setAllowCheatsWithConfirmation::__l5::<lambda_5b5604cb329015cbada2a7d2be0b2a06>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_setAllowCheatsWithConfirmation::__l5::<lambda_5b5604cb329015cbada2a7d2be0b2a06>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  bool value;
};

```

### `RealmsSettingsScreenController::_handleRealmBackupDownloadButtonClick::__l5::<lambda_c0ed1b3a441903df14dc6937b1f396b3>::()::__l5::<lambda_1be107764c80df9133b44c5f98758f2f>`
```
struct __cppobj RealmsSettingsScreenController::_handleRealmBackupDownloadButtonClick::__l5::<lambda_c0ed1b3a441903df14dc6937b1f396b3>::()::__l5::<lambda_1be107764c80df9133b44c5f98758f2f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_restoreBackup::__l2::<lambda_20dca6c21ea09b9c8d9ba5445a784a48>`
```
struct __cppobj RealmsSettingsScreenController::_restoreBackup::__l2::<lambda_20dca6c21ea09b9c8d9ba5445a784a48>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_restoreBackup::__l2::<lambda_c79bf9264e7185f9f17ac94057bb16ba>`
```
struct __cppobj RealmsSettingsScreenController::_restoreBackup::__l2::<lambda_c79bf9264e7185f9f17ac94057bb16ba>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_handleRealmBackupButtonClick::__l5::<lambda_dfd2962719ddc89bd2b2af3b7925a8db>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_handleRealmBackupButtonClick::__l5::<lambda_dfd2962719ddc89bd2b2af3b7925a8db>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  const int index;
};

```

### `RealmsSettingsScreenController::_updateRealmBranchConfig::__l2::<lambda_e375c2605621c6b84751423615bec6c5>`
```
struct __cppobj RealmsSettingsScreenController::_updateRealmBranchConfig::__l2::<lambda_e375c2605621c6b84751423615bec6c5>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_queryRealmsConfigInfo::__l2::<lambda_1cbb6b17c905233e5f77f87a28d54f3e>`
```
struct __cppobj RealmsSettingsScreenController::_queryRealmsConfigInfo::__l2::<lambda_1cbb6b17c905233e5f77f87a28d54f3e>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_setGameModeWithConfirmation::__l5::<lambda_8a192b21145b8b2dad203a0feb9c58cd>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_setGameModeWithConfirmation::__l5::<lambda_8a192b21145b8b2dad203a0feb9c58cd>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  int value;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_2347dbe09a7601791c05f4a9073cd4dc>`
```
struct __cppobj RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_2347dbe09a7601791c05f4a9073cd4dc>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_ca2ccb859bf67969182949b621406fa3>`
```
struct __cppobj RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_ca2ccb859bf67969182949b621406fa3>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_6dbb1c08c4ef6e4a55312f47b4f254cc>`
```
struct __cppobj RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_6dbb1c08c4ef6e4a55312f47b4f254cc>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_2347dbe09a7601791c05f4a9073cd4dc>::()::__l2::<lambda_76b9b10bb179a15f18e74f81a3afba8f>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_2347dbe09a7601791c05f4a9073cd4dc>::()::__l2::<lambda_76b9b10bb179a15f18e74f81a3afba8f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  bool required;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_50727df8337d04b6e837ba9b980c7a8a>`
```
struct __cppobj RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_50727df8337d04b6e837ba9b980c7a8a>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_fetchAppliedContent::__l2::<lambda_072bb69b3cfeddfbec106baf4639825a>`
```
struct __cppobj RealmsSettingsScreenController::_fetchAppliedContent::__l2::<lambda_072bb69b3cfeddfbec106baf4639825a>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_5adb1e206583e30faad1b80412e5fcaf>::()::__l5::<lambda_b016da4dccde1ac5fc420312271f7c6c>`
```
struct __cppobj RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_5adb1e206583e30faad1b80412e5fcaf>::()::__l5::<lambda_b016da4dccde1ac5fc420312271f7c6c>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_5adb1e206583e30faad1b80412e5fcaf>::()::__l5::<lambda_0d1ac4eea38fc8306957867b871b6a39>`
```
struct __cppobj RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_5adb1e206583e30faad1b80412e5fcaf>::()::__l5::<lambda_0d1ac4eea38fc8306957867b871b6a39>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  RealmsSettingsScreenController::_downloadWorld::__l2::<lambda_289f928b773cf1c3b7290561b1cf78a1> downloadFile;
};

```

### `RealmsSettingsScreenController::_saveClubInfo::__l2::<lambda_8be1389cbba2bc7185d3290eea0aa38f>`
```
struct __cppobj RealmsSettingsScreenController::_saveClubInfo::__l2::<lambda_8be1389cbba2bc7185d3290eea0aa38f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_querySubscriptionInfo::__l2::<lambda_ecf97686568702388c8771e14fd85042>`
```
struct __cppobj RealmsSettingsScreenController::_querySubscriptionInfo::__l2::<lambda_ecf97686568702388c8771e14fd85042>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_confirmCloseRealm::__l2::<lambda_99e04584aeaf84d019de8eebc705ff6f>`
```
struct __cppobj RealmsSettingsScreenController::_confirmCloseRealm::__l2::<lambda_99e04584aeaf84d019de8eebc705ff6f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_confirmResetRealm::__l2::<lambda_9271375af563a555cc34615c1d200d00>`
```
struct __cppobj RealmsSettingsScreenController::_confirmResetRealm::__l2::<lambda_9271375af563a555cc34615c1d200d00>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_fd3ade5acd31013d2ac4022ef1975c3c>::()::__l8::<lambda_d21704d3666d3599649c32e0b4f71c8f>`
```
struct __cppobj RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_fd3ade5acd31013d2ac4022ef1975c3c>::()::__l8::<lambda_d21704d3666d3599649c32e0b4f71c8f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_c8677b5df21d203ed2364daaaae69e34>::()::__l13::<lambda_5aa61ad18924730c086ad2fdd478f15f>`
```
struct __cppobj RealmsSettingsScreenController::_createApplyContentOnRealmProgressCallbackChain::__l2::<lambda_c8677b5df21d203ed2364daaaae69e34>::()::__l13::<lambda_5aa61ad18924730c086ad2fdd478f15f>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_applyPacks::__l8::<lambda_70b62245653a46e764e48f5cfe99f420>`
```
struct __cppobj RealmsSettingsScreenController::_applyPacks::__l8::<lambda_70b62245653a46e764e48f5cfe99f420>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  std::vector<PackContentItem *> selectedContent;
};

```

### `RealmsSettingsScreenController::_applyPacks::__l8::<lambda_70b62245653a46e764e48f5cfe99f420>::()::__l5::<lambda_e2d0017ea776686b23651620b6585e52>`
```
struct __cppobj RealmsSettingsScreenController::_applyPacks::__l8::<lambda_70b62245653a46e764e48f5cfe99f420>::()::__l5::<lambda_e2d0017ea776686b23651620b6585e52>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_applyPacks::__l8::<lambda_61191b8658ecd12074656f8fe5f60426>::()::__l8::<lambda_a8a4db01a1a957cef8b025611086e908>`
```
struct __cppobj RealmsSettingsScreenController::_applyPacks::__l8::<lambda_61191b8658ecd12074656f8fe5f60426>::()::__l8::<lambda_a8a4db01a1a957cef8b025611086e908>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_joinRealm::__l2::<lambda_35fdbb863980ab78634ca4500bec7f0d>`
```
struct __cppobj RealmsSettingsScreenController::_joinRealm::__l2::<lambda_35fdbb863980ab78634ca4500bec7f0d>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_saveSettingsAndExitScreen::__l2::<lambda_832dfd296551d2bd14133d06635c539b>`
```
struct __cppobj RealmsSettingsScreenController::_saveSettingsAndExitScreen::__l2::<lambda_832dfd296551d2bd14133d06635c539b>
{
};

```

### `RealmsSettingsScreenController::_saveSettingsAndJoinRealm::__l2::<lambda_88f142800fd62dc6db9b0cf3d060a4c9>`
```
struct __cppobj RealmsSettingsScreenController::_saveSettingsAndJoinRealm::__l2::<lambda_88f142800fd62dc6db9b0cf3d060a4c9>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_saveAndJoinRealm::__l2::<lambda_f2f47e11faeb76994b7cad06d1609609>`
```
struct __cppobj RealmsSettingsScreenController::_saveAndJoinRealm::__l2::<lambda_f2f47e11faeb76994b7cad06d1609609>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_fetchWorldBackups::__l2::<lambda_e9658987b3a5af61a85cf0e15089bb2d>`
```
struct __cppobj RealmsSettingsScreenController::_fetchWorldBackups::__l2::<lambda_e9658987b3a5af61a85cf0e15089bb2d>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_updateWorld::__l9::<lambda_d786fc539c8a39a7f88c8316d45d9f9d>`
```
struct __cppobj RealmsSettingsScreenController::_updateWorld::__l9::<lambda_d786fc539c8a39a7f88c8316d45d9f9d>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_updateWorld::__l2::<lambda_171cf9e84184033586cecc5fe1a1d0c1>`
```
struct __cppobj RealmsSettingsScreenController::_updateWorld::__l2::<lambda_171cf9e84184033586cecc5fe1a1d0c1>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  std::vector<std::string> playerXuids;
};

```

### `RealmsSettingsScreenController::_updateWorld::__l2::<lambda_171cf9e84184033586cecc5fe1a1d0c1>::()::__l5::<lambda_87a6a684392dd938b2301e6a1aa7a585>::()::__l5::<lambda_ba4c6226bdf76407e8db388ab671b19c>`
```
struct __cppobj RealmsSettingsScreenController::_updateWorld::__l2::<lambda_171cf9e84184033586cecc5fe1a1d0c1>::()::__l5::<lambda_87a6a684392dd938b2301e6a1aa7a585>::()::__l5::<lambda_ba4c6226bdf76407e8db388ab671b19c>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  std::vector<std::string> blockList;
};

```

### `RealmsSettingsScreenController::_refreshWorldInfo::__l2::<lambda_d41dc312ef79296b2c1c9002453bef46>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_refreshWorldInfo::__l2::<lambda_d41dc312ef79296b2c1c9002453bef46>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  bool refreshSubscriptionInfo;
};

```

### `RealmsSettingsScreenController::_refreshWorldInfo::__l2::<lambda_d41dc312ef79296b2c1c9002453bef46>::()::__l5::<lambda_a7efa21e944ffcccc83d0438d2aa2dd3>`
```
struct __cppobj __declspec(align(8)) RealmsSettingsScreenController::_refreshWorldInfo::__l2::<lambda_d41dc312ef79296b2c1c9002453bef46>::()::__l5::<lambda_a7efa21e944ffcccc83d0438d2aa2dd3>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
  bool refreshSubscriptionInfo;
};

```

### `RealmsSettingsScreenController::_showErrorPopupAndExitScreenAfterDismissed::__l2::<lambda_c3d224c905036e7b91131a9c0ca2beff>`
```
struct __cppobj RealmsSettingsScreenController::_showErrorPopupAndExitScreenAfterDismissed::__l2::<lambda_c3d224c905036e7b91131a9c0ca2beff>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_renewRealmHandler::__l19::<lambda_491b5ece53d03f31a6c5c8589b089d2a>`
```
struct __cppobj RealmsSettingsScreenController::_renewRealmHandler::__l19::<lambda_491b5ece53d03f31a6c5c8589b089d2a>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0e03b9018e2af109fc9dbbd4b916b0fd>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0e03b9018e2af109fc9dbbd4b916b0fd>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_63d3ba9504494d96358baacd6935b2c2>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_63d3ba9504494d96358baacd6935b2c2>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_254570655998cdb9d2ffb437702ab1a7>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_254570655998cdb9d2ffb437702ab1a7>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0f67862472344be98bc52495c31e16f7>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0f67862472344be98bc52495c31e16f7>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_50e58b0aa5a1e39d5a0bbe3cfb4dfee3>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_50e58b0aa5a1e39d5a0bbe3cfb4dfee3>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_9c0383a8619590fb7a4741d55f84d689>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_9c0383a8619590fb7a4741d55f84d689>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_11fd927f9c3d1bcef21a498450e840a2>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_11fd927f9c3d1bcef21a498450e840a2>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_07dc94f83ddcebf0234269aea5288a0a>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_07dc94f83ddcebf0234269aea5288a0a>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ec46621c6b3277c780ac4031e6ee35c4>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ec46621c6b3277c780ac4031e6ee35c4>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_78ac4a22142f7c93aa47891d8316ee8b>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_78ac4a22142f7c93aa47891d8316ee8b>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ae4a4ac7b10173f281779813f5d8cc10>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ae4a4ac7b10173f281779813f5d8cc10>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_911da65430644ac545f95e6f6d7ef52d>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_911da65430644ac545f95e6f6d7ef52d>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_7e5f17fe2a16eefd3de72db6d9efbd73>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_7e5f17fe2a16eefd3de72db6d9efbd73>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5c7768c342f49d632a3e516b7cc91081>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5c7768c342f49d632a3e516b7cc91081>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2431f3f644d88b5263a40c3a38cc8c38>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2431f3f644d88b5263a40c3a38cc8c38>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_8fec3302b316d9c73770bcc65d61baf1>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_8fec3302b316d9c73770bcc65d61baf1>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_44aa3cb00c45a3d7c5548891cd007330>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_44aa3cb00c45a3d7c5548891cd007330>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_612a4523ad584ff42180eecfa9b55b0e>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_612a4523ad584ff42180eecfa9b55b0e>
{
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5020f8b108e0f62f52c588b416bbea30>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5020f8b108e0f62f52c588b416bbea30>
{
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_472fe9ec135c1f62159dbeaba535a1bb>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_472fe9ec135c1f62159dbeaba535a1bb>
{
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_152ec0d740c406cb6e0561fed439b5fe>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_152ec0d740c406cb6e0561fed439b5fe>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_db75287338658e539289ebce6991622c>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_db75287338658e539289ebce6991622c>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_131be0043d4fef0adade52acefd6cd73>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_131be0043d4fef0adade52acefd6cd73>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2eb66c1097785dec8e8bca3f32b157f1>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2eb66c1097785dec8e8bca3f32b157f1>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_cec16fa0fd3d227638326c2d5d7a2c03>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_cec16fa0fd3d227638326c2d5d7a2c03>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_fea4d21969e8090036fd2a25f05cf803>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_fea4d21969e8090036fd2a25f05cf803>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2e8986c0393dc85630b5cc8ffaba8c13>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_2e8986c0393dc85630b5cc8ffaba8c13>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_e8ee40cb5bdaa554f1e15bab6ee12d3e>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_e8ee40cb5bdaa554f1e15bab6ee12d3e>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5f687dbf271c7c927ff2fd42eb8883e3>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5f687dbf271c7c927ff2fd42eb8883e3>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_6a391bcf23072eabb22448d55afccca5>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_6a391bcf23072eabb22448d55afccca5>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_cad071cd3e2c8ab8f9e28e78f98b9fbb>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_cad071cd3e2c8ab8f9e28e78f98b9fbb>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_f61adeb09109c3a89f10312a7be5d752>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_f61adeb09109c3a89f10312a7be5d752>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_feeefb3c4d426c2fe0b2e3753aeda1d7>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_feeefb3c4d426c2fe0b2e3753aeda1d7>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_4d1c2bdf0b87850685ebfdaa3b6ff6a1>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_4d1c2bdf0b87850685ebfdaa3b6ff6a1>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5515c4f2f67e5512effdbb17b956e810>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_5515c4f2f67e5512effdbb17b956e810>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ef07b696c4da469e635277efbf9eb64e>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_ef07b696c4da469e635277efbf9eb64e>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_61ad9117c26fa2ad85c5de00069a7196>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_61ad9117c26fa2ad85c5de00069a7196>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_73f64529325c942bbca77fd010436314>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_73f64529325c942bbca77fd010436314>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0df43fa42c3614fbee793150fce311ff>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0df43fa42c3614fbee793150fce311ff>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_c4c5d985de7f83894ae0965f76c24982>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_c4c5d985de7f83894ae0965f76c24982>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_fb74ee2613dfe259a2bc9c8c3974c5cb>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_fb74ee2613dfe259a2bc9c8c3974c5cb>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_45a8320176e0800a659ecea2bbac9f47>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_45a8320176e0800a659ecea2bbac9f47>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_574813e37a5587cefcc87bed65926bea>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_574813e37a5587cefcc87bed65926bea>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0b256b4705fe5e9c387fa8efc025f421>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_0b256b4705fe5e9c387fa8efc025f421>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_31b939d5cb30acb5ff44effc6575f71b>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_31b939d5cb30acb5ff44effc6575f71b>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_c334a841d6b6d70b903ab9169bcdf4cd>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_c334a841d6b6d70b903ab9169bcdf4cd>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_4a41c35c9aa6d010a702e8c09eb4e58a>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_4a41c35c9aa6d010a702e8c09eb4e58a>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_abfb3475d98eed0734e63338900f974b>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_abfb3475d98eed0734e63338900f974b>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_73d7fa71be31bba444d72dc675d3276e>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_73d7fa71be31bba444d72dc675d3276e>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerBindings::__l2::<lambda_66a51be67be1c42b9aade377303123c3>`
```
struct __cppobj RealmsSettingsScreenController::_registerBindings::__l2::<lambda_66a51be67be1c42b9aade377303123c3>
{
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_fa98919fd81b32d084957da57f57eab0>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_fa98919fd81b32d084957da57f57eab0>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_4e2c32ddf69f1ffd51ef1fdaa6d6a8fd>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_4e2c32ddf69f1ffd51ef1fdaa6d6a8fd>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_f774d9962f89b0cde0e782909132e600>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_f774d9962f89b0cde0e782909132e600>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9179b875ae42a215a0a0bca3f905a882>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9179b875ae42a215a0a0bca3f905a882>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_0ef10744f0bf3275f7c8eece68cf5ce3>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_0ef10744f0bf3275f7c8eece68cf5ce3>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_683a12f0174a105b1e474c2e13aeb9d8>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_683a12f0174a105b1e474c2e13aeb9d8>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_95e4496cf08990072b9b7df4942f64d5>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_95e4496cf08990072b9b7df4942f64d5>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_ca69df077a1990c00af1f4b736af3f7c>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_ca69df077a1990c00af1f4b736af3f7c>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_71526daec25765ca9057f7fabe8296e4>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_71526daec25765ca9057f7fabe8296e4>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1896b82bc81e6ab9f5c0d4a413f379c6>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1896b82bc81e6ab9f5c0d4a413f379c6>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_cc8b45e438e947befdefb7954c0e909c>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_cc8b45e438e947befdefb7954c0e909c>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3006cfd36ff1d261115ba13818b6b0d0>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3006cfd36ff1d261115ba13818b6b0d0>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1724374d5de458cf6df05629b6bc5ef0>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1724374d5de458cf6df05629b6bc5ef0>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1309620636a401d9a556d58f3955a2d2>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_1309620636a401d9a556d58f3955a2d2>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_90db5d58281c267f1849f402b1594349>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_90db5d58281c267f1849f402b1594349>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_6ab121a5199e6d1ee824cb615bb7cdf5>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_6ab121a5199e6d1ee824cb615bb7cdf5>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>::()::__l2::<lambda_d8aab08faab0c390fcf2945e3bba3c4d>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>::()::__l2::<lambda_d8aab08faab0c390fcf2945e3bba3c4d>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>::()::__l2::<lambda_d8aab08faab0c390fcf2945e3bba3c4d>::()::__l5::<lambda_4cbcee7af5347659cbc7e095dc550653>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_3793cda6b65b95797e9c7a4e4e9f6379>::()::__l2::<lambda_d8aab08faab0c390fcf2945e3bba3c4d>::()::__l5::<lambda_4cbcee7af5347659cbc7e095dc550653>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_c4d5cf591757d73f021b31f1c9fcbaac>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_c4d5cf591757d73f021b31f1c9fcbaac>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_6ead42e8955eeaddff0ec9ead7f7dd70>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_6ead42e8955eeaddff0ec9ead7f7dd70>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_99a25ab9e684f48c84550868ef7c937b>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_99a25ab9e684f48c84550868ef7c937b>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_34c7824a99484f2a423667ed03ec5e55>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_34c7824a99484f2a423667ed03ec5e55>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_a9df756d2958d135ff589112df124cfc>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_a9df756d2958d135ff589112df124cfc>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_293cb6d7b957890ba5535686c61ea1f0>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_293cb6d7b957890ba5535686c61ea1f0>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_293cb6d7b957890ba5535686c61ea1f0>::()::__l2::<lambda_a8b76bf49e5ad39c0a9a3c45b1406883>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_293cb6d7b957890ba5535686c61ea1f0>::()::__l2::<lambda_a8b76bf49e5ad39c0a9a3c45b1406883>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_a372619b97462bccb462f0704d58f928>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_a372619b97462bccb462f0704d58f928>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_ab7a8c4662a0e1b3b0d566ddfa9c8340>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_ab7a8c4662a0e1b3b0d566ddfa9c8340>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_83e7829e6c6f50e878c8ab22b14b2f77>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_83e7829e6c6f50e878c8ab22b14b2f77>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9ca525cee4e39475946166737ef03c59>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9ca525cee4e39475946166737ef03c59>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_d707f6c259a733b05e431e70ef339fcd>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_d707f6c259a733b05e431e70ef339fcd>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>
{
  RealmsSettingsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>::()::__l2::<lambda_7cd0273e1849fd0b2ba12e35035531c5>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>::()::__l2::<lambda_7cd0273e1849fd0b2ba12e35035531c5>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>::()::__l2::<lambda_7cd0273e1849fd0b2ba12e35035531c5>::()::__l5::<lambda_da4faa7510076b487070cb7eb815abd9>`
```
struct __cppobj RealmsSettingsScreenController::_registerEventHandlers::__l2::<lambda_9db30636c1ba95e45d6d93a0befe092c>::()::__l2::<lambda_7cd0273e1849fd0b2ba12e35035531c5>::()::__l5::<lambda_da4faa7510076b487070cb7eb815abd9>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsPlusUpgradeNoticeScreenController::{ctor}::__l2::<lambda_84c875a5c7b0b622701c37b22b189798>`
```
struct __cppobj RealmsPlusUpgradeNoticeScreenController::{ctor}::__l2::<lambda_84c875a5c7b0b622701c37b22b189798>
{
  RealmsPlusUpgradeNoticeScreenController *const __this;
};

```

### `RealmsPlusUpgradeNoticeScreenController::{ctor}::__l2::<lambda_1792228937fa34e2aa083e125d22447b>`
```
struct __cppobj RealmsPlusUpgradeNoticeScreenController::{ctor}::__l2::<lambda_1792228937fa34e2aa083e125d22447b>
{
  RealmsPlusUpgradeNoticeScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerCollection::__l5::<lambda_ac6ca3d8e0b49f94d48023bdbd949d08>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerCollection::__l5::<lambda_ac6ca3d8e0b49f94d48023bdbd949d08>
{
  std::weak_ptr<RealmsPlusPDPScreenController> weakThis;
};

```

### `RealmsPlusPDPScreenController::_registerBuyNowSectionBindings::__l2::<lambda_1af563a4cd97e6fafcc79fa19ec70865>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBuyNowSectionBindings::__l2::<lambda_1af563a4cd97e6fafcc79fa19ec70865>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e690c1b899bde1b8f7807cb8e6166d2c>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e690c1b899bde1b8f7807cb8e6166d2c>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_0d6bb64e29f43c55f72264c47a702b69>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_0d6bb64e29f43c55f72264c47a702b69>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_6187d111c36fb32f73fe8ce1467b82ab>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_6187d111c36fb32f73fe8ce1467b82ab>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_8b422bc694fd21930d482c1d643c3aa7>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_8b422bc694fd21930d482c1d643c3aa7>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_9d73ba3493d0abf0038bd31c94d30fe5>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_9d73ba3493d0abf0038bd31c94d30fe5>
{
  RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_8b422bc694fd21930d482c1d643c3aa7> canBuyMoreSubscriptions;
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_0b7f3f996d0ce155c0ff46617fc65f46>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_0b7f3f996d0ce155c0ff46617fc65f46>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_eeb31a9d5a4cbf27a3ec4af2593d458f>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_eeb31a9d5a4cbf27a3ec4af2593d458f>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_ade4d15a6ba9bdbf254539e64d992c81>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_ade4d15a6ba9bdbf254539e64d992c81>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e47ca508c31fb8cffa085888e94fc1f2>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e47ca508c31fb8cffa085888e94fc1f2>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e882a4c544f0cf48f64eb6c6f233e852>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_e882a4c544f0cf48f64eb6c6f233e852>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_dbf507aa634d1c05a8a59c3a421f6b1e>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_dbf507aa634d1c05a8a59c3a421f6b1e>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_029686a63384684eb6b9d967d8328edb>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_029686a63384684eb6b9d967d8328edb>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_c5e7e4d5ba9f7887502e71d0c2ef6704>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_c5e7e4d5ba9f7887502e71d0c2ef6704>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_50c03e114a00093dec933b27f6eca14a>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_50c03e114a00093dec933b27f6eca14a>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_b6fb789d3b7aef45eb72ee3bd5ebc627>`
```
struct __cppobj RealmsPlusPDPScreenController::_registerBindings::__l2::<lambda_b6fb789d3b7aef45eb72ee3bd5ebc627>
{
  RealmsPlusPDPScreenController *const __this;
};

```

### `RealmsPlusPDPScreenController::onCreation::__l2::<lambda_11d48506b555f2c4d6cca052a2bebb25>`
```
struct __cppobj RealmsPlusPDPScreenController::onCreation::__l2::<lambda_11d48506b555f2c4d6cca052a2bebb25>
{
  std::weak_ptr<RealmsPlusPDPScreenController> weakThis;
};

```

### `RealmsPlusEndedScreenController::_registerEventHandlers::__l2::<lambda_8fe1816fc4fc9fa2b6b41486c071a577>`
```
struct __cppobj RealmsPlusEndedScreenController::_registerEventHandlers::__l2::<lambda_8fe1816fc4fc9fa2b6b41486c071a577>
{
  RealmsPlusEndedScreenController *const __this;
};

```

### `RealmsPlusEndedScreenController::_registerEventHandlers::__l2::<lambda_d0dae4362d0e7ae3abe4dd800831d35b>`
```
struct __cppobj RealmsPlusEndedScreenController::_registerEventHandlers::__l2::<lambda_d0dae4362d0e7ae3abe4dd800831d35b>
{
  RealmsPlusEndedScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_handleInvitationDecline::__l5::<lambda_fff283895957cf045b192a5619019f7f>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_handleInvitationDecline::__l5::<lambda_fff283895957cf045b192a5619019f7f>
{
  int bagIndex;
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>
{
  int bagIndex;
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>::()::__l17::<lambda_784b8a943650b0c0f8b86de6a583f9a2>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>::()::__l17::<lambda_784b8a943650b0c0f8b86de6a583f9a2>
{
};

```

### `RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>::()::__l15::<lambda_0f19f8699bc394a4f148c68ec97875fe>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_handleInvitationAccept::__l10::<lambda_a269b6c60f34dc3c1489035ef20d8a72>::()::__l15::<lambda_0f19f8699bc394a4f148c68ec97875fe>
{
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_34f451295d586c6c2cb58f704658f69c>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_34f451295d586c6c2cb58f704658f69c>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_bdd3fa6a0a8a915154ceee7abd21fe94>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_bdd3fa6a0a8a915154ceee7abd21fe94>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_850e9dcb10fe11e3a6cc79305826ee05>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_850e9dcb10fe11e3a6cc79305826ee05>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_7ec29f0d30df7d9b53b7811c5b1f7991>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_7ec29f0d30df7d9b53b7811c5b1f7991>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_ab69afc9a15087304c500c89bccf9d7b>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_ab69afc9a15087304c500c89bccf9d7b>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_5d800c1278c97b16dd7581af551ccab2>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_5d800c1278c97b16dd7581af551ccab2>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_32841c1660e3675d967d42f4f310d339>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_32841c1660e3675d967d42f4f310d339>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_883224d22760964c2077711299853e77>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerBindings::__l2::<lambda_883224d22760964c2077711299853e77>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_2109e249cd5c8825bab98ba9791df26f>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_2109e249cd5c8825bab98ba9791df26f>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_8836af0e424aeeef2300a38515f6f2bf>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_8836af0e424aeeef2300a38515f6f2bf>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_a9c5bed76924b8e84c37d78206b5d77c>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_registerEventHandlers::__l2::<lambda_a9c5bed76924b8e84c37d78206b5d77c>
{
  RealmsPendingInvitationsScreenController *const __this;
};

```

### `RealmsPendingInvitationsScreenController::_fetchPendingInvites::__l2::<lambda_e6ba7fa5dac6f44deecd421314ed9baf>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_fetchPendingInvites::__l2::<lambda_e6ba7fa5dac6f44deecd421314ed9baf>
{
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPendingInvitationsScreenController::_fetchPendingInvites::__l2::<lambda_e6ba7fa5dac6f44deecd421314ed9baf>::()::__l36::<lambda_22b9b778b6e8d5b7b56c5709ea663e84>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_fetchPendingInvites::__l2::<lambda_e6ba7fa5dac6f44deecd421314ed9baf>::()::__l36::<lambda_22b9b778b6e8d5b7b56c5709ea663e84>
{
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPendingInvitationsScreenController::_initialize::__l2::<lambda_0dec47121f41d03b3aac3daff40863bc>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_initialize::__l2::<lambda_0dec47121f41d03b3aac3daff40863bc>
{
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPendingInvitationsScreenController::_initialize::__l2::<lambda_43436e4d3022bf287ddf41dca9aba5db>`
```
struct __cppobj RealmsPendingInvitationsScreenController::_initialize::__l2::<lambda_43436e4d3022bf287ddf41dca9aba5db>
{
  std::weak_ptr<RealmsPendingInvitationsScreenController> weakThis;
};

```

### `RealmsPackErrorsScreenController::tick::__l5::<lambda_ec2a2de9365ab669603d483ee7acdc37>`
```
struct __cppobj RealmsPackErrorsScreenController::tick::__l5::<lambda_ec2a2de9365ab669603d483ee7acdc37>
{
  RealmsPackErrorsScreenController *const __this;
};

```

### `RealmsSettingsScreenController::_showBackupProgressAndExitScreen::__l2::<lambda_c760341673e3bcb024087d26ff3aa632>`
```
struct __cppobj RealmsSettingsScreenController::_showBackupProgressAndExitScreen::__l2::<lambda_c760341673e3bcb024087d26ff3aa632>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_showBackupProgressAndExitScreen::__l2::<lambda_e7bde36bb7219aae889558d2fa6bcf42>`
```
struct __cppobj RealmsSettingsScreenController::_showBackupProgressAndExitScreen::__l2::<lambda_e7bde36bb7219aae889558d2fa6bcf42>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::tick::__l17::<lambda_8d178f0875a575f1fdc2a15a94f9a001>`
```
struct __cppobj RealmsSettingsScreenController::tick::__l17::<lambda_8d178f0875a575f1fdc2a15a94f9a001>
{
  std::weak_ptr<RealmsSettingsScreenController> weakThis;
};

```

### `RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_647dc77839c6c2dd3c39475f33c87ed0>`
```
struct __cppobj RealmsSettingsScreenController::_setupPacksScreen::__l2::<lambda_647dc77839c6c2dd3c39475f33c87ed0>
{
};

```

### `RealmsFileUploader::UploadResult`
```
struct __cppobj RealmsFileUploader::UploadResult
{
  IFileChunkUploader::UploadStatus status;
  std::string cancelUrl;
  std::string progress;
  std::string message;
};

```

### `RealmsFileUploader`
```
struct __cppobj __declspec(align(8)) RealmsFileUploader : IFileChunkUploader, std::enable_shared_from_this<RealmsFileUploader>
{
  std::weak_ptr<RealmsAPI> mRealmsAPI;
  std::unordered_map<std::string,RealmsFileUploader::RealmUploadInfo> mRealmsMap;
  MPMCQueue<std::function<void __cdecl(void)> > mExecutionQueue;
  bool mIsPack;
};

```

### `RealmsFileUploader_vtbl`
```
struct /*VFT*/ RealmsFileUploader_vtbl
{
  void (__fastcall *~IFileChunkUploader)(IFileChunkUploader *this);
  void (__fastcall *update)(IFileChunkUploader *this);
  void (__fastcall *initFileUploader)(IFileChunkUploader *this, const std::string *, const FileInfo *, int, const Json::Value *, std::function<void __cdecl(bool)>);
  void (__fastcall *getServerMissingChunks)(IFileChunkUploader *this, const FileInfo *, std::function<void __cdecl(std::vector<FileChunkInfo>)>);
  void (__fastcall *confirmChunkReceived)(IFileChunkUploader *this, const FileInfo *, const FileChunkInfo *);
  void (__fastcall *uploadChunk)(IFileChunkUploader *this, const FileInfo *, const FileChunkInfo *, const std::vector<unsigned char> *, std::function<void __cdecl(bool)>);
  void (__fastcall *uploadStream)(IFileChunkUploader *this, const FileInfo *, unsigned __int64, const std::string *, std::function<bool __cdecl(unsigned __int64 &,std::vector<unsigned char> &)>, std::function<void __cdecl(enum IFileChunkUploader::UploadStreamResult)>);
  bool (__fastcall *canCancelUpload)(IFileChunkUploader *this, const FileInfo *);
  void (__fastcall *cancelUpload)(IFileChunkUploader *this, const FileInfo *);
  UploadError (__fastcall *getInitErrorCode)(IFileChunkUploader *this);
  float (__fastcall *getUploadProgress)(IFileChunkUploader *this, const FileInfo *);
  FileChunkInfo *(__fastcall *getChunkInfo)(IFileChunkUploader *this, FileChunkInfo *result, const FileInfo *, int);
};

```

### `RealmsFileDownloader`
```
struct __cppobj RealmsFileDownloader : StreamFileDownloader
{
  std::weak_ptr<RealmsAPI> mRealmsAPI;
};

```

### `RealmsFileDownloader_vtbl`
```
struct /*VFT*/ RealmsFileDownloader_vtbl
{
  void (__fastcall *~IFileChunkDownloader)(IFileChunkDownloader *this);
  void (__fastcall *update)(IFileChunkDownloader *this);
  void (__fastcall *initFileDownloader)(IFileChunkDownloader *this, const std::string *, const std::string *, const FileInfo *, unsigned __int64, const std::string *, std::function<void __cdecl(enum DownloaderResult)>);
  void (__fastcall *downloadFile)(IFileChunkDownloader *this, std::function<void __cdecl(std::vector<unsigned char>,unsigned __int64,unsigned __int64,std::function<void __cdecl(unsigned __int64,bool)>)>, std::function<void __cdecl(enum DownloaderState)>);
  bool (__fastcall *canCancelDownload)(IFileChunkDownloader *this);
  void (__fastcall *cancelDownload)(IFileChunkDownloader *this);
  unsigned __int64 (__fastcall *getDownloadTotalSize)(IFileChunkDownloader *this);
  unsigned __int64 (__fastcall *getDownloadReceivedSize)(IFileChunkDownloader *this);
  float (__fastcall *getDownloadProgress)(IFileChunkDownloader *this);
  void (__fastcall *_retryFileDownloader)(StreamFileDownloader *this, const FileInfo *, std::function<void __cdecl(enum DownloaderResult)>, const std::string *);
};

```

### `RealmsPlusPackCollector`
```
struct __cppobj __declspec(align(8)) RealmsPlusPackCollector : CatalogPackCollector
{
  _BYTE mPerfTier[4];
};

```

### `RealmsPlusPackCollector_vtbl`
```
struct /*VFT*/ RealmsPlusPackCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `RecentlyViewedCollector`
```
struct __cppobj RecentlyViewedCollector : CatalogPackCollector
{
  std::vector<std::string> mOrderedRecentSkinPackIds;
};

```

### `RecentlyViewedCollector_vtbl`
```
struct /*VFT*/ RecentlyViewedCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `RecurseString<1,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60>`
```
struct __cppobj RecurseString<1,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60>
{
};

```

### `RecurseString<1,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5>`
```
struct __cppobj RecurseString<1,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5>
{
};

```

### `ReportCheatConfirmScreenController`
```
struct __cppobj ReportCheatConfirmScreenController : ClientInstanceScreenController
{
};

```

### `ReportCheatConfirmScreenController_vtbl`
```
struct /*VFT*/ ReportCheatConfirmScreenController_vtbl
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

### `ReportScreenController`
```
struct __cppobj ReportScreenController : ClientInstanceScreenController
{
  Abilities mStartAbilityCache;
  Abilities mAbilities;
  ActorUniqueID mDefaultPlayerId;
  unsigned __int64 mSelectedPlayerIndex;
  bool mPlayerListInitialized;
  bool mContentAreaActive;
  bool mFriend;
  std::vector<std::string> mPermissionNames;
  std::vector<ActorUniqueID> mClientIds;
  std::weak_ptr<UserDataScreenController> mUserDataScreenController;
  std::unordered_map<std::string,bool> mShields;
};

```

### `ReportScreenController_vtbl`
```
struct /*VFT*/ ReportScreenController_vtbl
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

### `RecurseString<2,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17>`
```
struct __cppobj RecurseString<2,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17>
{
};

```

### `RecurseString<2,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40>`
```
struct __cppobj RecurseString<2,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40>
{
};

```

### `RecurseString<3,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41>`
```
struct __cppobj RecurseString<3,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41>
{
};

```

### `RecurseString<3,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16>`
```
struct __cppobj RecurseString<3,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16>
{
};

```

### `RecurseString<4,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12>`
```
struct __cppobj RecurseString<4,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12>
{
};

```

### `RecurseString<4,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53>`
```
struct __cppobj RecurseString<4,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53>
{
};

```

### `RecurseString<5,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56>`
```
struct __cppobj RecurseString<5,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56>
{
};

```

### `RecurseString<5,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1>`
```
struct __cppobj RecurseString<5,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1>
{
};

```

### `RecurseString<6,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10>`
```
struct __cppobj RecurseString<6,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10>
{
};

```

### `RecurseString<6,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51>`
```
struct __cppobj RecurseString<6,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51>
{
};

```

### `RecurseString<7,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41>`
```
struct __cppobj RecurseString<7,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41>
{
};

```

### `RecurseString<7,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16>`
```
struct __cppobj RecurseString<7,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16>
{
};

```

### `RecurseString<8,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13>`
```
struct __cppobj RecurseString<8,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13>
{
};

```

### `RecurseString<8,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52>`
```
struct __cppobj RecurseString<8,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52>
{
};

```

### `RecurseString<9,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62>`
```
struct __cppobj RecurseString<9,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62>
{
};

```

### `RecurseString<9,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7>`
```
struct __cppobj RecurseString<9,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7>
{
};

```

### `RecurseString<10,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5>`
```
struct __cppobj RecurseString<10,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5>
{
};

```

### `RecurseString<10,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60>`
```
struct __cppobj RecurseString<10,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60>
{
};

```

### `RecurseString<11,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41>`
```
struct __cppobj RecurseString<11,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41>
{
};

```

### `RecurseString<11,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16>`
```
struct __cppobj RecurseString<11,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16>
{
};

```

### `RecurseString<12,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13>`
```
struct __cppobj RecurseString<12,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13>
{
};

```

### `RecurseString<12,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52>`
```
struct __cppobj RecurseString<12,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52>
{
};

```

### `RecurseString<13,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50>`
```
struct __cppobj RecurseString<13,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50>
{
};

```

### `RecurseString<13,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11>`
```
struct __cppobj RecurseString<13,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11>
{
};

```

### `RecurseString<14,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10>`
```
struct __cppobj RecurseString<14,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10>
{
};

```

### `RecurseString<14,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51>`
```
struct __cppobj RecurseString<14,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51>
{
};

```

### `RecurseString<15,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115>`
```
struct __cppobj RecurseString<15,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115>
{
};

```

### `RecurseString<15,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59>`
```
struct __cppobj RecurseString<15,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59>
{
};

```

### `RecurseString<16,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9>`
```
struct __cppobj RecurseString<16,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9>
{
};

```

### `RecurseString<16,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60>`
```
struct __cppobj RecurseString<16,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60>
{
};

```

### `RecurseString<17,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40>`
```
struct __cppobj RecurseString<17,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40>
{
};

```

### `RecurseString<17,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11>`
```
struct __cppobj RecurseString<17,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11>
{
};

```

### `RecurseString<18,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0>`
```
struct __cppobj RecurseString<18,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0>
{
};

```

### `RecurseString<18,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41>`
```
struct __cppobj RecurseString<18,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41>
{
};

```

### `RecurseString<19,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53>`
```
struct __cppobj RecurseString<19,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53>
{
};

```

### `RecurseString<19,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5>`
```
struct __cppobj RecurseString<19,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5>
{
};

```

### `RecurseString<20,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8>`
```
struct __cppobj RecurseString<20,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8>
{
};

```

### `RecurseString<20,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2>`
```
struct __cppobj RecurseString<20,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2>
{
};

```

### `RecurseString<21,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46>`
```
struct __cppobj RecurseString<21,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46>
{
};

```

### `RecurseString<21,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23>`
```
struct __cppobj RecurseString<21,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23>
{
};

```

### `RecurseString<22,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74>`
```
struct __cppobj RecurseString<22,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74>
{
};

```

### `RecurseString<22,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62>`
```
struct __cppobj RecurseString<22,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62>
{
};

```

### `RecurseString<23,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47>`
```
struct __cppobj RecurseString<23,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47>
{
};

```

### `RecurseString<23,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5>`
```
struct __cppobj RecurseString<23,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5>
{
};

```

### `RecurseString<24,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0>`
```
struct __cppobj RecurseString<24,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0>
{
};

```

### `RecurseString<24,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56>`
```
struct __cppobj RecurseString<24,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56>
{
};

```

### `RecurseString<25,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56>`
```
struct __cppobj RecurseString<25,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56>
{
};

```

### `RecurseString<25,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59>`
```
struct __cppobj RecurseString<25,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59>
{
};

```

### `RecurseString<26,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9>`
```
struct __cppobj RecurseString<26,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9>
{
};

```

### `RecurseString<26,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56,51>`
```
struct __cppobj RecurseString<26,26,`<lambda_adcf6bd9062ebad447b2428204664251>::operator()'::`2'::StrAccessor,93,60,40,41,53,56,51,41,52,62,60,41,52,50,51,115,60,40,41,53,2,46,62,47,56,56,51>
{
};

```

### `RecurseString<27,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11>`
```
struct __cppobj RecurseString<27,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11>
{
};

```

### `RecurseString<28,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0>`
```
struct __cppobj RecurseString<28,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0>
{
};

```

### `RecurseString<29,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5>`
```
struct __cppobj RecurseString<29,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5>
{
};

```

### `RecurseString<30,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8>`
```
struct __cppobj RecurseString<30,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8>
{
};

```

### `RecurseString<31,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59>`
```
struct __cppobj RecurseString<31,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59>
{
};

```

### `RecurseString<32,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0>`
```
struct __cppobj RecurseString<32,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0>
{
};

```

### `RecurseString<33,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13>`
```
struct __cppobj RecurseString<33,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13>
{
};

```

### `RecurseString<34,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5>`
```
struct __cppobj RecurseString<34,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5>
{
};

```

### `RecurseString<35,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8>`
```
struct __cppobj RecurseString<35,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8>
{
};

```

### `RecurseString<36,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11>`
```
struct __cppobj RecurseString<36,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11>
{
};

```

### `RecurseString<37,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11,3>`
```
struct __cppobj RecurseString<37,37,`<lambda_9f02b271ede7732ee4ddc2d56da6dc4c>::operator()'::`2'::StrAccessor,100,5,17,16,12,1,10,16,13,7,5,16,13,11,10,59,9,11,0,5,8,23,74,5,0,59,9,11,0,5,8,59,0,13,5,8,11,3>
{
};

```

### `RandomStrollGoal`
```
struct __cppobj __declspec(align(8)) RandomStrollGoal : Goal
{
  Mob *mMob;
  float mSpeed;
  int mXZDist;
  int mYDist;
  int mInterval;
  Vec3 mWantedPosition;
  BlockPos mChosenEndPos;
  bool mPathingInvalid;
  bool mReachedTarget;
};

```

### `RandomStrollGoal_vtbl`
```
struct /*VFT*/ RandomStrollGoal_vtbl
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
  bool (__fastcall *_setWantedPosition)(RandomStrollGoal *this);
};

```

### `RemotePlayer`
```
struct __cppobj __declspec(align(4)) RemotePlayer : Player, LocalPlayer::RegionListener
{
  std::unique_ptr<BlockSource> mRegion;
  LocalPlayer *mLocalPlayer;
  std::shared_ptr<bool> mExistenceTracker;
  std::string mQueuedEmote;
  int mEmoteQueuedTicks;
  bool mHasStartedUsingItem;
  bool mTicked;
};

```

### `Realms::<lambda_0f2b82658f97b5fd215b5e6f03529d88>`
```
struct __cppobj Realms::<lambda_0f2b82658f97b5fd215b5e6f03529d88>
{
};

```

### `RealmsAPI::initializeRealmsUserEventHandler::__l2::<lambda_3a8e43a94f7a8370352ab147402ac21d>`
```
struct __cppobj RealmsAPI::initializeRealmsUserEventHandler::__l2::<lambda_3a8e43a94f7a8370352ab147402ac21d>
{
  std::weak_ptr<RealmsAPI> weakThis;
};

```

### `Realms::ContentService::fetchAppliedContent::__l5::<lambda_254f8b44945570f656f9d2c6b5f48dc2>`
```
struct __cppobj Realms::ContentService::fetchAppliedContent::__l5::<lambda_254f8b44945570f656f9d2c6b5f48dc2>
{
  std::function<void __cdecl(enum Realms::GenericStatus,std::vector<Realms::Content>)> callback;
};

```

### `RedDustParticle`
```
struct __cppobj __declspec(align(8)) RedDustParticle : Particle
{
  float oSize;
};

```

### `RedDustParticle_vtbl`
```
struct /*VFT*/ RedDustParticle_vtbl
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

### `RisingRedDustParticle`
```
struct __cppobj RisingRedDustParticle : Particle
{
  float mOSize;
  float mRisingVal;
  float risingDir;
  const int maxLifetime;
};

```

### `RisingRedDustParticle_vtbl`
```
struct /*VFT*/ RisingRedDustParticle_vtbl
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

### `RainSplashParticle`
```
struct __cppobj RainSplashParticle : SplashParticle
{
};

```

### `RainSplashParticle_vtbl`
```
struct /*VFT*/ RainSplashParticle_vtbl
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

### `registerBedrockEffectComponents::__l2::<lambda_a54a76c525516fd7a17081a1fa2bc418>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_a54a76c525516fd7a17081a1fa2bc418>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_6b1221a376c8e4c16450e67fd53741a8>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_6b1221a376c8e4c16450e67fd53741a8>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_ac3e8a474c7dfc7b8fc3114a8b3e3d52>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_ac3e8a474c7dfc7b8fc3114a8b3e3d52>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_1d82c934d6eb6db4268ef1754197b95a>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_1d82c934d6eb6db4268ef1754197b95a>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_77a363d082d7cd65b5a2a33f4ff87b7f>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_77a363d082d7cd65b5a2a33f4ff87b7f>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_0c5dc0f1de26508880a2dd32e9e454c6>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_0c5dc0f1de26508880a2dd32e9e454c6>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_0ce0540e789e469262e1fc45ce115156>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_0ce0540e789e469262e1fc45ce115156>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_4f23f01e1f9513213a6a47210a13540e>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_4f23f01e1f9513213a6a47210a13540e>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_0d5709a40ea7e58c5d38031e14206dd8>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_0d5709a40ea7e58c5d38031e14206dd8>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_c661ee64314ee15cea391d78c8c5787f>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_c661ee64314ee15cea391d78c8c5787f>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_15a7b99b35330ab5d44098353c35d3e4>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_15a7b99b35330ab5d44098353c35d3e4>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_01cc91a93afdc74b2efec1b18f59faf1>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_01cc91a93afdc74b2efec1b18f59faf1>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_68007fe23c1a119a364c21a2c8436d6f>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_68007fe23c1a119a364c21a2c8436d6f>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_dc67ecd94f5b5dde8c184d28f3bbbf7c>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_dc67ecd94f5b5dde8c184d28f3bbbf7c>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_80ef6bb7c597143e683d2092af9a8dd1>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_80ef6bb7c597143e683d2092af9a8dd1>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_67ae57e8e14c9805b64d3c51513c2f7a>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_67ae57e8e14c9805b64d3c51513c2f7a>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_f1ffe0dbb209611b34881a45cee26561>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_f1ffe0dbb209611b34881a45cee26561>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_447a27e8589d9bb58f3035ed8f2df570>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_447a27e8589d9bb58f3035ed8f2df570>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_dca6e299d3085208bd0cb5f4eadd00b1>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_dca6e299d3085208bd0cb5f4eadd00b1>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_42d62c21f24516ea5c26a2fd6ea17003>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_42d62c21f24516ea5c26a2fd6ea17003>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_0d5f5c06020c31dd82ed5601212f9799>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_0d5f5c06020c31dd82ed5601212f9799>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_e02c654c265a3ea08208de8a5e01a8bf>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_e02c654c265a3ea08208de8a5e01a8bf>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_1772197dbfa7a4e684211977bab8ca07>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_1772197dbfa7a4e684211977bab8ca07>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_366db911b50dd46d928d472ae16df8e7>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_366db911b50dd46d928d472ae16df8e7>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_3d8e1f36b5ed6dbedcdccefb97229138>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_3d8e1f36b5ed6dbedcdccefb97229138>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_a1ada4a597973def5b89202eb9d288c2>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_a1ada4a597973def5b89202eb9d288c2>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_6cdd9283a1bb4ad4567000ed3e22ecb7>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_6cdd9283a1bb4ad4567000ed3e22ecb7>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_bac734de3624ad98f6c50696bd1cde22>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_bac734de3624ad98f6c50696bd1cde22>
{
};

```

### `registerBedrockEffectComponents::__l2::<lambda_58ca365cef4e3bc271883935968b4629>`
```
struct __cppobj registerBedrockEffectComponents::__l2::<lambda_58ca365cef4e3bc271883935968b4629>
{
};

```

### `RailMovement`
```
struct __cppobj RailMovement
{
};

```

### `RemoveOnHitSubcomponent`
```
struct __cppobj RemoveOnHitSubcomponent : OnHitSubcomponent
{
};

```

### `RemoveOnHitSubcomponent_vtbl`
```
struct /*VFT*/ RemoveOnHitSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `RenderLayerComponentDescription`
```
struct __cppobj __declspec(align(8)) RenderLayerComponentDescription : BlockComponentDescription
{
  std::string mRenderLayerStr;
  bool mAllowSame;
};

```

### `RenderLayerComponentDescription_vtbl`
```
struct /*VFT*/ RenderLayerComponentDescription_vtbl
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

### `RenderLayerComponent`
```
struct __cppobj __declspec(align(8)) RenderLayerComponent
{
  BlockLegacy *mBlockLegacy;
  bool mAllowSame;
};

```

### `RedStoneWireBlock`
```
struct __cppobj RedStoneWireBlock : BlockLegacy
{
};

```

### `RedStoneWireBlock_vtbl`
```
struct /*VFT*/ RedStoneWireBlock_vtbl
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

### `RepeaterBlock`
```
struct __cppobj RepeaterBlock : DiodeBlock
{
};

```

### `RepeaterBlock_vtbl`
```
struct /*VFT*/ RepeaterBlock_vtbl
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
  int (__fastcall *getSignal)(DiodeBlock *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *isLocked)(DiodeBlock *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isSameDiode)(DiodeBlock *this, const Block *);
  bool (__fastcall *shouldPrioritize)(DiodeBlock *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isOn)(DiodeBlock *this);
  bool (__fastcall *shouldTurnOn)(DiodeBlock *this, BlockSource *, const BlockPos *);
  int (__fastcall *getInputSignal)(DiodeBlock *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAlternateInput)(DiodeBlock *this, const Block *);
  int (__fastcall *getAlternateSignal)(DiodeBlock *this, BlockSource *, const BlockPos *);
  int (__fastcall *getOutputSignal)(DiodeBlock *this, const Block *);
  int (__fastcall *getTurnOffDelay)(DiodeBlock *this, const Block *);
  int (__fastcall *getTurnOnDelay)(DiodeBlock *this, const Block *);
  const Block *(__fastcall *getOnBlock)(DiodeBlock *this, const Block *);
  const Block *(__fastcall *getOffBlock)(DiodeBlock *this, const Block *);
};

```

### `RenderChunkGeometry::isMeshValid::__l2::<lambda_5e329e28c3bfb048584d70281e66d7ac>`
```
struct __cppobj RenderChunkGeometry::isMeshValid::__l2::<lambda_5e329e28c3bfb048584d70281e66d7ac>
{
};

```

### `RenderChunkGeometry::isMeshValid::__l2::<lambda_01b39313f0d7f04e2fa783b22b54c850>`
```
struct __cppobj RenderChunkGeometry::isMeshValid::__l2::<lambda_01b39313f0d7f04e2fa783b22b54c850>
{
};

```

### `RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_ab713435ef2faa01d8b65aad97412461>`
```
struct __cppobj RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_ab713435ef2faa01d8b65aad97412461>
{
};

```

### `RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_21619ba291e1eba153356cbc6994c82d>`
```
struct __cppobj RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_21619ba291e1eba153356cbc6994c82d>
{
};

```

### `RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_4ceac7e605773765654d7e544105257d>`
```
struct __cppobj RenderChunkGeometry::prefetchMeshPtr::__l2::<lambda_4ceac7e605773765654d7e544105257d>
{
};

```

### `RenderChunkCoordinator::_launchVisibilityRebuild::__l2::<lambda_1c7fb74c4fe142dd8088acb1f9490938>`
```
struct __cppobj RenderChunkCoordinator::_launchVisibilityRebuild::__l2::<lambda_1c7fb74c4fe142dd8088acb1f9490938>
{
  std::weak_ptr<RenderChunkShared> renderChunkWeakPtr;
  RenderChunkCoordinator *const __this;
};

```

### `RenderChunkCoordinator::_launchVisibilityRebuild::__l2::<lambda_d4f1c471caf19761f18a90ce53f52630>`
```
struct __cppobj RenderChunkCoordinator::_launchVisibilityRebuild::__l2::<lambda_d4f1c471caf19761f18a90ce53f52630>
{
  std::weak_ptr<RenderChunkShared> renderChunkWeakPtr;
  std::shared_ptr<LevelChunk> levelChunkSharedPtr;
};

```

### `RenderChunkCoordinator::{ctor}::__l2::<lambda_0fad7266988335176229be7f5f46bb01>`
```
struct __cppobj RenderChunkCoordinator::{ctor}::__l2::<lambda_0fad7266988335176229be7f5f46bb01>
{
  RenderChunkCoordinator *const __this;
};

```

### `RenderChunkCoordinator::{ctor}::__l2::<lambda_c8b1e557f02b8f054bf55d7d00832401>`
```
struct __cppobj RenderChunkCoordinator::{ctor}::__l2::<lambda_c8b1e557f02b8f054bf55d7d00832401>
{
  RenderChunkCoordinator *const __this;
};

```

### `RenderChunkCoordinator::{ctor}::__l2::<lambda_92d5a6515edb6b15691be04ce93cbf01>`
```
struct __cppobj RenderChunkCoordinator::{ctor}::__l2::<lambda_92d5a6515edb6b15691be04ce93cbf01>
{
  RenderChunkCoordinator *const __this;
};

```

### `RenderChunkBuilder::build::__l2::<lambda_76cc7ed0c1abce2afadfc8a2b43d8ef5>`
```
struct __cppobj RenderChunkBuilder::build::__l2::<lambda_76cc7ed0c1abce2afadfc8a2b43d8ef5>
{
  RenderChunkBuilder *const __this;
};

```

### `RenderChunkInstanced::createLayerRenderObject::__l2::<lambda_646478fcdb2a37f507ae4129658625ce>`
```
struct __cppobj RenderChunkInstanced::createLayerRenderObject::__l2::<lambda_646478fcdb2a37f507ae4129658625ce>
{
};

```

### `RenderChunkInstanced::promoteSortedGeometry::__l2::<lambda_d7940ffb93fe410c58f19e715232b6a2>`
```
struct __cppobj RenderChunkInstanced::promoteSortedGeometry::__l2::<lambda_d7940ffb93fe410c58f19e715232b6a2>
{
};

```

### `RenderChunkInstanced::prefetchIndexBufferPtr::__l2::<lambda_252416c79aa1913095d3ae39c6637066>`
```
struct __cppobj RenderChunkInstanced::prefetchIndexBufferPtr::__l2::<lambda_252416c79aa1913095d3ae39c6637066>
{
};

```

### `RenderControllerGroup::_buildRenderControllerFileSchema::__l2::<lambda_18fd33180b55cc14e2affd942f9f8f53>`
```
struct __cppobj RenderControllerGroup::_buildRenderControllerFileSchema::__l2::<lambda_18fd33180b55cc14e2affd942f9f8f53>
{
  const SemVersion *formatVersion;
};

```

### `RenderControllerGroup::loadRenderControllers::__l2::<lambda_b34267440ea89a3676be64fad9a15bcf>`
```
struct __cppobj RenderControllerGroup::loadRenderControllers::__l2::<lambda_b34267440ea89a3676be64fad9a15bcf>
{
  ResourcePackManager *resourcePackManager;
  RenderControllerGroup *const __this;
};

```

### `RenderControllerGroup::loadRenderControllers::__l2::<lambda_b34267440ea89a3676be64fad9a15bcf>::()::__l4::<lambda_45dc1100dd98337cf63e489de538444e>`
```
struct __cppobj RenderControllerGroup::loadRenderControllers::__l2::<lambda_b34267440ea89a3676be64fad9a15bcf>::()::__l4::<lambda_45dc1100dd98337cf63e489de538444e>
{
  RenderControllerGroup *const __this;
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *rit;
};

```

### `RenderPassContext`
```
struct RenderPassContext
{
  mce::RenderContext *renderContext;
};

```

### `RangedWeaponItem`
```
struct __cppobj RangedWeaponItem : Item
{
};

```

### `rendergraph::BackBufferResource`
```
struct __cppobj rendergraph::BackBufferResource : rendergraph::Resource, rendergraph::ResourceTargetInterface
{
};

```

### `rendergraph::BackBufferResource_vtbl`
```
struct /*VFT*/ rendergraph::BackBufferResource_vtbl
{
  void (__fastcall *~Resource)(rendergraph::Resource *this);
  optional_ref<rendergraph::ResourceViewInterface const > *(__fastcall *getViewInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceViewInterface const > *result);
  optional_ref<rendergraph::ResourceTargetInterface const > *(__fastcall *getTargetInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceTargetInterface const > *result);
  rendergraph::ValidationResult (__fastcall *acquireAPIResources)(rendergraph::Resource *this, rendergraph::APIResourcePool *);
  rendergraph::ValidationResult (__fastcall *enterRenderScope)(rendergraph::Resource *this);
  rendergraph::ValidationResult (__fastcall *exitRenderScope)(rendergraph::Resource *this);
  void (__fastcall *bind)(rendergraph::Resource *this, rendergraph::BindInterface *);
  rendergraph::ResourceBinding::ResourceType (__fastcall *getBindingType)(rendergraph::Resource *this);
};

```

### `rendergraph::ExternalTextureSlice`
```
struct __cppobj __declspec(align(8)) rendergraph::ExternalTextureSlice : rendergraph::Resource, rendergraph::ResourceViewInterface, rendergraph::ResourceTargetInterface
{
  const mce::Texture *mTexture;
  const unsigned __int8 mMipLevel;
  const unsigned __int8 mArrayIndex;
};

```

### `rendergraph::ExternalTextureSlice_vtbl`
```
struct /*VFT*/ rendergraph::ExternalTextureSlice_vtbl
{
  void (__fastcall *~Resource)(rendergraph::Resource *this);
  optional_ref<rendergraph::ResourceViewInterface const > *(__fastcall *getViewInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceViewInterface const > *result);
  optional_ref<rendergraph::ResourceTargetInterface const > *(__fastcall *getTargetInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceTargetInterface const > *result);
  rendergraph::ValidationResult (__fastcall *acquireAPIResources)(rendergraph::Resource *this, rendergraph::APIResourcePool *);
  rendergraph::ValidationResult (__fastcall *enterRenderScope)(rendergraph::Resource *this);
  rendergraph::ValidationResult (__fastcall *exitRenderScope)(rendergraph::Resource *this);
  void (__fastcall *bind)(rendergraph::Resource *this, rendergraph::BindInterface *);
  rendergraph::ResourceBinding::ResourceType (__fastcall *getBindingType)(rendergraph::Resource *this);
};

```

### `rendergraph::TransientTextureSlice`
```
struct __cppobj rendergraph::TransientTextureSlice : rendergraph::Resource, rendergraph::ResourceViewInterface, rendergraph::ResourceTargetInterface
{
  const mce::TextureDescription mTextureDescription;
  const unsigned __int8 mMipLevel;
  const unsigned __int8 mArrayIndex;
  optional_ref<mce::Texture> mTransientTexture;
};

```

### `rendergraph::TransientTextureSlice_vtbl`
```
struct /*VFT*/ rendergraph::TransientTextureSlice_vtbl
{
  void (__fastcall *~Resource)(rendergraph::Resource *this);
  optional_ref<rendergraph::ResourceViewInterface const > *(__fastcall *getViewInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceViewInterface const > *result);
  optional_ref<rendergraph::ResourceTargetInterface const > *(__fastcall *getTargetInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceTargetInterface const > *result);
  rendergraph::ValidationResult (__fastcall *acquireAPIResources)(rendergraph::Resource *this, rendergraph::APIResourcePool *);
  rendergraph::ValidationResult (__fastcall *enterRenderScope)(rendergraph::Resource *this);
  rendergraph::ValidationResult (__fastcall *exitRenderScope)(rendergraph::Resource *this);
  void (__fastcall *bind)(rendergraph::Resource *this, rendergraph::BindInterface *);
  rendergraph::ResourceBinding::ResourceType (__fastcall *getBindingType)(rendergraph::Resource *this);
};

```

### `rendergraph::CustomRenderPass<`PostprocessRenderModule::declareFullscreenPass'::`2'::PostprocessPass>`
```
struct __cppobj rendergraph::CustomRenderPass<`PostprocessRenderModule::declareFullscreenPass'::`2'::PostprocessPass> : rendergraph::RenderPass
{
  std::function<void __cdecl(`PostprocessRenderModule::declareFullscreenPass'::`2'::PostprocessPass const &,rendergraph::RenderContext &)> mCallback;
  PostprocessRenderModule::declareFullscreenPass::__l2::PostprocessPass mData;
};

```

### `rendergraph::CustomRenderPass<`PostprocessRenderModule::declareFullscreenPass'::`2'::PostprocessPass>_vtbl`
```
struct /*VFT*/ rendergraph::CustomRenderPass<`PostprocessRenderModule::declareFullscreenPass'::`2'::PostprocessPass>_vtbl
{
  void (__fastcall *~Pass)(rendergraph::Pass *this);
  void (__fastcall *execute)(rendergraph::Pass *this, rendergraph::RenderContext *);
  void (__fastcall *render)(rendergraph::RenderPass *this, rendergraph::RenderContext *);
};

```

### `rendergraph::RenderStageSelectorResource`
```
struct __cppobj rendergraph::RenderStageSelectorResource : rendergraph::Resource, rendergraph::ResourceTargetInterface
{
  std::function<mce::RenderStage & __cdecl(void)> mStageSelector;
};

```

### `rendergraph::RenderStageSelectorResource_vtbl`
```
struct /*VFT*/ rendergraph::RenderStageSelectorResource_vtbl
{
  void (__fastcall *~Resource)(rendergraph::Resource *this);
  optional_ref<rendergraph::ResourceViewInterface const > *(__fastcall *getViewInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceViewInterface const > *result);
  optional_ref<rendergraph::ResourceTargetInterface const > *(__fastcall *getTargetInterface)(rendergraph::Resource *this, optional_ref<rendergraph::ResourceTargetInterface const > *result);
  rendergraph::ValidationResult (__fastcall *acquireAPIResources)(rendergraph::Resource *this, rendergraph::APIResourcePool *);
  rendergraph::ValidationResult (__fastcall *enterRenderScope)(rendergraph::Resource *this);
  rendergraph::ValidationResult (__fastcall *exitRenderScope)(rendergraph::Resource *this);
  void (__fastcall *bind)(rendergraph::Resource *this, rendergraph::BindInterface *);
  rendergraph::ResourceBinding::ResourceType (__fastcall *getBindingType)(rendergraph::Resource *this);
};

```

### `rendergraph::CustomRenderPass<PlayerRenderView::LegacyPlayerRenderPass>`
```
struct __cppobj rendergraph::CustomRenderPass<PlayerRenderView::LegacyPlayerRenderPass> : rendergraph::RenderPass
{
  std::function<void __cdecl(PlayerRenderView::LegacyPlayerRenderPass const &,rendergraph::RenderContext &)> mCallback;
  PlayerRenderView::LegacyPlayerRenderPass mData;
};

```

