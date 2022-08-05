# R
### `ResourcePackRepository`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FilePathManager *` | mFilePathManager
8 | (24) `std::vector<std::unique_ptr<ResourcePack>>` | mAllResourcePacks
32 | (8) `std::unique_ptr<CompositePackSource>` | mPackSource
40 | (8) `std::unique_ptr<CompositePackSource>` | mCachePackSource
48 | (8) `std::unique_ptr<CompositePackSource>` | mWorldPackSource
56 | (8) `std::unique_ptr<CompositePackSource>` | mPremiumWorldTemplatePackSource
64 | (8) `std::unique_ptr<PackSourceReport>` | mPackSourceReport
72 | (8) `ResourcePack *` | mVanillaPack
80 | (8) `ResourcePack *` | mChemistryPack
88 | (8) `ResourcePack *` | mChemistryServerPack
96 | (24) `std::vector<ResourceLocation>` | mInvalidPackLocation
120 | (24) `std::vector<ResourceLocation>` | mInvalidBehaviorPackLocation
144 | (24) `std::vector<ResourceLocation>` | mInvalidResourcePackLocation
168 | (24) `std::vector<ResourceLocation>` | mInvalidTemplatePackLocation
192 | (8) `IMinecraftEventing *` | mEventing
200 | (8) `PackManifestFactory *` | mManifestFactory
208 | (8) `IContentAccessibilityProvider *` | mContentAccessibility
216 | (32) `Core::HeapPathBuffer` | mCurrentWorldPath
248 | (32) `Core::HeapPathBuffer` | mCurrentPremiumWorldTemplatePath
280 | (56) `ContentKeyMap` | mTempCacheContentKeys
336 | (4) `const int` | mKnownPacksFileVerison
344 | (8) `std::unique_ptr<PackSettingsFactory>` | mPackSettingsFactory
352 | (8) `PackSourceFactory *` | mPackSourceFactory
360 | (24) `ResourcePackRepository::KnownPackContainer` | mCachedValidUserPacks
384 | (24) `ResourcePackRepository::KnownPackContainer` | mCachedInvalidUserPacks
408 | (48) `std::map<void *,std::function<void (ResourcePack *)>>` | mRemoveResourcePackCallback
456 | (8) `std::unique_ptr<TaskGroup>` | mInitTaskGroup
464 | (40) `Bedrock::Threading::Mutex` | mInitializeMutex
504 | (1) `std::atomic<bool>` | mInitialized
505 | (1) `std::atomic<bool>` | mReloadUserPacksRequested
506 | (1) `std::atomic<bool>` | mRefreshPacksRequested
512 | (24) `ContentIdentity` | mCurrentPremiumWorldTemplateIdentity


### `ResourcePackRepository::KnownPackContainer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ResourcePackRepository::KnownPackInfo>` | mPacks


### `ResourceLocation`
Offset | Type | Name
-|-|-|-
0 | (4) `ResourceFileSystem` | mFileSystem
8 | (32) `Core::HeapPathBuffer` | mPath
40 | (8) `HashType64` | mPathHash
48 | (8) `size_t` | mFullHash


### `ResourceMetadata`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mAuthors
24 | (32) `std::string` | mUrl
56 | (32) `std::string` | mLicense


### `ResourcePackStack`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ResourcePackStack
8 | (24) `ResourcePackStack::PackInstanceStack` | mStack
32 | (8) `std::unique_ptr<PackSourceReport>` | mPackSourceReport


### `ResourcePackStack::PackInstanceStack`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<PackInstance>` | baseclass_0


### `Random`
Offset | Type | Name
-|-|-|-
0 | (2516) `Bedrock::Application::ThreadOwner<Core::Random>` | mRandom


### `Range<int,-1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mIndex


### `Range<int,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mIndex


### `Range<unsigned int,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mIndex


### `RootLayer<LayerValues::Terrain>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<char>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<LayerValues::Terrain>` | mResult


### `RootLayer<BiomeTemperatureCategory>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<char>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<BiomeTemperatureCategory>` | mResult


### `Realms::RealmId`
Offset | Type | Name
-|-|-|-
0 | (8) `NewType<long>` | baseclass_0


### `RaidBossComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `Weak<Village>` | mVillage
16 | (8) `ActorUniqueID` | mOwnerID
24 | (32) `std::string` | mName
56 | (32) `std::string` | mProgress
88 | (4) `int` | mPlayersRegistered
92 | (1) `bool` | mWaveStarted
93 | (1) `bool` | mRaidInProgress
94 | (1) `bool` | mHealthBarVisible
96 | (4) `float` | mHealthPercent
100 | (28) `AABB` | mBossBarVisibleBounds
128 | (8) `std::chrono::_V2::steady_clock::time_point` | mLastPlayerUpdate


### `RailActivatorComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `RakNet::RakNetGUID`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | g
8 | (2) `RakNet::SystemIndex` | systemIndex


### `ReadOnlyBinaryStream`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ReadOnlyBinaryStream
8 | (8) `size_t` | mReadPointer
16 | (32) `const std::string` | mOwnedBuffer
48 | (8) `const std::string *` | mBuffer


### `Range<unsigned long,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mIndex


### `RakNet::RakNetStatistics`
Offset | Type | Name
-|-|-|-
0 | (56) `uint64_t[7]` | valueOverLastSecond
56 | (56) `uint64_t[7]` | runningTotal
112 | (8) `RakNet::TimeUS` | connectionStartTime
120 | (1) `bool` | isLimitedByCongestionControl
128 | (8) `uint64_t` | BPSLimitByCongestionControl
136 | (1) `bool` | isLimitedByOutgoingBandwidthLimit
144 | (8) `uint64_t` | BPSLimitByOutgoingBandwidthLimit
152 | (16) `unsigned int[4]` | messageInSendBuffer
168 | (32) `double[4]` | bytesInSendBuffer
200 | (4) `unsigned int` | messagesInResendBuffer
208 | (8) `uint64_t` | bytesInResendBuffer
216 | (4) `float` | packetlossLastSecond
220 | (4) `float` | packetlossTotal


### `RakNet::SystemAddress`
Offset | Type | Name
-|-|-|-
0 | (128) `RakNet::SystemAddress::$17DEBC484162A322D6AFC648B0CB992A` | address
128 | (2) `unsigned __int16` | debugPort
130 | (2) `RakNet::SystemIndex` | systemIndex


### `RakNet::SystemAddress::$17DEBC484162A322D6AFC648B0CB992A`
Offset | Type | Name
-|-|-|-
0 | (128) `sockaddr_storage` | sa_stor
1 | (28) `sockaddr_in6` | addr6
2 | (16) `sockaddr_in` | addr4


### `RakNetInstance::_storeLocalIP::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `RakNetInstance::NatConnectionInfo`
Offset | Type | Name
-|-|-|-
0 | (136) `RakNet::SystemAddress` | remoteAddress
136 | (4) `RakNet::TimeMS` | lastNatPingSendTime
140 | (4) `uint32_t` | natPingSendCount
144 | (1) `bool` | pongReceived


### `RakNet::BitStream`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::BitSize_t` | numberOfBitsUsed
4 | (4) `RakNet::BitSize_t` | numberOfBitsAllocated
8 | (4) `RakNet::BitSize_t` | readOffset
16 | (8) `unsigned __int8 *` | data
24 | (1) `bool` | copyData
25 | (256) `unsigned __int8[256]` | stackData


### `RakNet::RakString`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakString::SharedString *` | sharedString


### `RakNetServerLocator::ScopeLock`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::recursive_mutex>::mutex_type *` | _M_device


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


### `ResourcePackStackPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<PackInstanceId>` | mAddOnIdsAndVersions
64 | (24) `std::vector<PackInstanceId>` | mTexturePackIdsAndVersions
88 | (112) `BaseGameVersion` | mBaseGameVersion
200 | (1) `bool` | mTexturePackRequired
201 | (1) `bool` | mExperimental


### `Recipes::FurnaceRecipeKey`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mID
8 | (40) `Util::HashString` | mTag


### `ResourcePacksInfoPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (56) `ResourcePacksInfoData` | mData


### `ResourcePacksInfoData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mTexturePackRequired
1 | (1) `bool` | mHasScripts
2 | (1) `bool` | mHasExceptions
8 | (24) `std::vector<ResourcePackInfoData>` | mAddOnPacks
32 | (24) `std::vector<ResourcePackInfoData>` | mTexturePacks


### `Recipe::ResultList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<ItemInstance>` | baseclass_0


### `ResourceInformation`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mDescription
32 | (112) `SemVersion` | mVersion
144 | (16) `mce::UUID` | mUUID
160 | (4) `ResourceInformation::ResourceType` | mType
168 | (32) `std::string` | mEntry


### `ResourceTaskCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<TaskResult ()>::_Invoker_type` | _M_invoker


### `ResourceMainThreadCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void ()>::_Invoker_type` | _M_invoker


### `ResourcePack::Callback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Core::Path &)>::_Invoker_type` | _M_invoker


### `ResourcePackContents`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mUIJson
4 | (4) `uint32_t` | mUITextures
8 | (4) `uint32_t` | mSound
12 | (4) `uint32_t` | mBlockJson
16 | (4) `uint32_t` | mBlockTextures
20 | (4) `uint32_t` | mItemTextures
24 | (4) `uint32_t` | mEntityTextures
28 | (4) `uint32_t` | mModelGeometry
32 | (4) `uint32_t` | mAnimations
36 | (4) `uint32_t` | mMaterials
40 | (4) `uint32_t` | mLanguages


### `ResourcePackRepository::KnownPackInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mDiscoveredOnDisk
8 | (56) `ResourceLocation` | mResourceLocation
64 | (24) `std::vector<std::string>` | mPastHashes
88 | (136) `PackIdVersion` | mIdentity


### `RemoveActorPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mEntityId


### `RotationDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `Description` | baseclass_0
8 | (8) `Vec2` | mRot


### `Range<unsigned short,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mIndex


### `ResourcePackDataInfoPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mResourceName
72 | (4) `uint32_t` | mChunkSize
76 | (4) `int` | mNbChunks
80 | (8) `uint64_t` | mFileSize
88 | (32) `std::string` | mFileHash
120 | (1) `PackType` | mPackType
121 | (1) `bool` | mIsPremium


### `ResourcePackChunkDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mResourceName
72 | (4) `int` | mChunkID
80 | (8) `uint64_t` | mByteOffset
88 | (24) `std::vector<unsigned char>` | mData


### `Range<short,1>::iterator`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mIndex


### `RopeParams`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mNodeDist
4 | (4) `float` | mNodeSize
8 | (4) `float` | mGravity
12 | (4) `float` | mSlack
16 | (4) `float` | mMaxTension
20 | (4) `float` | mVelDamping
24 | (4) `float` | mRelaxation
28 | (4) `float` | mFriction
32 | (12) `Vec3` | mStartPin
44 | (12) `Vec3` | mEndPin
56 | (8) `size_t` | mIterations
64 | (8) `size_t` | mDestroyDelay
72 | (4) `int` | mFlags
76 | (4) `float` | mLength
80 | (4) `float` | mOriginalNodeDist


### `RideableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `RaidTriggerComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `RuntimeIdentifierDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (32) `std::string` | mRuntimeId


### `Raid::ActorIDCollection`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<ActorUniqueID>::_Hashtable` | _M_h


### `ReverseableIterator::Iterator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mI
4 | (1) `bool` | mReversed


### `ResourcePackMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ResourcePackMergeStrategy


### `RecipeIngredient`
Offset | Type | Name
-|-|-|-
0 | (24) `ItemDescriptorCount` | baseclass_0


### `RecipeMap`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,std::unique_ptr<Recipe>>::_Rep_type` | _M_t


### `Range<unsigned char,'_x01'>::iterator`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mIndex


### `Recipes::addShapedRecipe::Map`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<char,RecipeIngredient>::_Rep_type` | _M_t


### `Recipes::addShapedRecipe::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Recipe::Ingredients`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<RecipeIngredient>` | baseclass_0


### `Recipes::TypeList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<Recipes::Type>` | baseclass_0


### `RowList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::string>` | baseclass_0


### `Recipes::addShapelessRecipe::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `RakDataInput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataInput` | baseclass_0
8 | (8) `RakNet::BitStream *` | mBitStream


### `RenderParams`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseActorRenderContext *` | mBaseActorRenderContext
8 | (8) `MolangVariableMap *` | mVariables
16 | (8) `AnimationComponent *` | mAnimationComponent
24 | (8) `AnimationComponent *` | mRootAnimationComponent
32 | (8) `DataDrivenModel *` | mRootModel
40 | (8) `DataDrivenModel *` | mModel
48 | (8) `Actor *` | mActor
56 | (8) `BlockSource *` | mBlockSource
64 | (8) `ActorRenderData *` | mActorRenderData
72 | (4) `int32_t` | mVertexCount
76 | (2) `uint16_t` | mSubRenderLayerIndex
80 | (32) `std::function<float ()>` | mRandomFunction
112 | (4) `float` | mCameraDistance
116 | (32) `float[8]` | mParams
148 | (4) `RenderParams::$3D9EB0E7A2790D70080124A37CC6ABC8` | mFlags


### `RenderParams::$3D9EB0E7A2790D70080124A37CC6ABC8`
Offset | Type | Name
-|-|-|-
0 | (4) `RenderParams::$3D9EB0E7A2790D70080124A37CC6ABC8::$7CDB70B13784CF5DCA20C1417F11D194` | _anon_0
1 | (4) `uint32_t` | _data


### `RenderParams::$3D9EB0E7A2790D70080124A37CC6ABC8::$7CDB70B13784CF5DCA20C1417F11D194`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `RoomDefinition`
Offset | Type | Name
-|-|-|-
0 | (16) `std::enable_shared_from_this<RoomDefinition>` | baseclass_0
16 | (4) `int` | mIndex
24 | (24) `std::vector<std::shared_ptr<RoomDefinition>>` | mConnections
48 | (40) `std::vector<bool>` | mHasOpening
88 | (1) `bool` | mClaimed
89 | (1) `bool` | mIsSource
92 | (4) `int` | mScanIndex


### `RakDataOutput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataOutput` | baseclass_0
8 | (8) `RakNet::BitStream *` | mBitStream


### `RandomValueBounds`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mMin
4 | (4) `float` | mMax


### `RequeueAreaFunc`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const ITickingArea &)>::_Invoker_type` | _M_invoker


### `RopeWave`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mForce
12 | (4) `float` | mSpeed
16 | (4) `float` | mDamping
24 | (8) `size_t` | mCurNode
32 | (4) `float` | mDistAlongNode
36 | (4) `RopeWave::Direction` | mDir


### `RailMovementComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mMaxSpeed


### `ResourceSignature`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,std::string>` | mSignatureFileContents


### `ResourcePackChunkRequestPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mResourceName
72 | (4) `int` | mChunk


### `RegisteredTagFilter`
Offset | Type | Name
-|-|-|-
0 | (8) `TagSetID` | mIncludeSet
8 | (8) `TagSetID` | mExcludeSet


### `RuntimeLightingManager::RelightingChunkElement`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mDist
8 | (8) `ChunkPos` | mChunkPos
16 | (8) `size_t` | mSubChunkIndex
24 | (8) `std::vector<SubChunkLightUpdate> *` | mAlteredBlockList


### `RoleChecker::OnRoleAcquired`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (ADRole,const std::string &,const std::string &)>::_Invoker_type` | _M_invoker


### `RakNet::RNS2_SendParameters`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | data
8 | (4) `int` | length
16 | (136) `RakNet::SystemAddress` | systemAddress
152 | (4) `int` | ttl


### `RakNet::RNS2_BerkleyBindParameters`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | port
8 | (8) `char *` | hostAddress
16 | (2) `unsigned __int16` | addressFamily
20 | (4) `int` | type
24 | (4) `int` | protocol
28 | (1) `bool` | nonBlockingSocket
32 | (4) `int` | setBroadcast
36 | (4) `int` | setIPHdrIncl
40 | (4) `int` | doNotFragment
44 | (4) `int` | pollingThreadPriority
48 | (8) `RakNet::RNS2EventHandler *` | eventHandler
56 | (2) `unsigned __int16` | remotePortRakNetWasStartedOn_PS3_PS4_PSP2


### `RakNet::AddressOrGUID`
Offset | Type | Name
-|-|-|-
0 | (16) `RakNet::RakNetGUID` | rakNetGuid
16 | (136) `RakNet::SystemAddress` | systemAddress


### `RakNet::SimpleMutex`
Offset | Type | Name
-|-|-|-
0 | (40) `pthread_mutex_t` | hMutex


### `RakNet::uint24_t`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | val


### `RakNet::MessageNumberType`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | val


### `RakNet::OrderingIndexType`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | val


### `RakNet::InternalPacket`
Offset | Type | Name
-|-|-|-
0 | (32) `RakNet::InternalPacketFixedSizeTransmissionHeader` | baseclass_0
32 | (4) `RakNet::MessageNumberType` | messageInternalOrder
36 | (1) `bool` | messageNumberAssigned
40 | (8) `RakNet::TimeUS` | creationTime
48 | (8) `RakNet::TimeUS` | nextActionTime
56 | (8) `RakNet::TimeUS` | retransmissionTime
64 | (4) `RakNet::BitSize_t` | headerLength
72 | (8) `unsigned __int8 *` | data
80 | (4) `RakNet::InternalPacket::AllocationScheme` | allocationScheme
88 | (8) `RakNet::InternalPacketRefCountedData *` | refCountedData
96 | (1) `unsigned __int8` | timesSent
100 | (4) `PacketPriority` | priority
104 | (4) `uint32_t` | sendReceiptSerial
112 | (8) `RakNet::InternalPacket *` | resendPrev
120 | (8) `RakNet::InternalPacket *` | resendNext
128 | (8) `RakNet::InternalPacket *` | unreliablePrev
136 | (8) `RakNet::InternalPacket *` | unreliableNext
144 | (128) `unsigned __int8[128]` | stackData


### `RakNet::InternalPacketFixedSizeTransmissionHeader`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::MessageNumberType` | reliableMessageNumber
4 | (4) `RakNet::OrderingIndexType` | orderingIndex
8 | (4) `RakNet::OrderingIndexType` | sequencingIndex
12 | (1) `unsigned __int8` | orderingChannel
14 | (2) `RakNet::SplitPacketIdType` | splitPacketId
16 | (4) `RakNet::SplitPacketIndexType` | splitPacketIndex
20 | (4) `RakNet::SplitPacketIndexType` | splitPacketCount
24 | (4) `RakNet::BitSize_t` | dataBitLength
28 | (4) `PacketReliability` | reliability


### `RakNet::Packet`
Offset | Type | Name
-|-|-|-
0 | (136) `RakNet::SystemAddress` | systemAddress
136 | (16) `RakNet::RakNetGUID` | guid
152 | (4) `unsigned int` | length
156 | (4) `RakNet::BitSize_t` | bitSize
160 | (8) `unsigned __int8 *` | data
168 | (1) `bool` | deleteData
169 | (1) `bool` | wasGeneratedLocally


### `RakNet::NetworkAdapter`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | attributeFlags
4 | (4) `int` | interfaceIndex
8 | (1) `bool` | isDisabled
16 | (2856) `RakNet::SystemAddress[21]` | addresses


### `r_debug`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | r_version
8 | (8) `link_map *` | r_map
16 | (8) `Elf64_Addr` | r_brk
24 | (4) `r_debug::$779A3ED0FCC279D8F3DE0A4A7B5F9A6A` | r_state
32 | (8) `Elf64_Addr` | r_ldbase


### `ResourcePackListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ResourcePackListener


### `RakNet::RakNetRandom`
Offset | Type | Name
-|-|-|-
0 | (2500) `unsigned int[625]` | state
2504 | (8) `unsigned int *` | next
2512 | (4) `int` | left


### `RakNet::RakString::SharedString`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::SimpleMutex *` | refCountMutex
8 | (4) `unsigned int` | refCount
16 | (8) `size_t` | bytesUsed
24 | (8) `char *` | bigString
32 | (8) `char *` | c_str
40 | (100) `char[100]` | smallString


### `RakStringCleanup`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Range<int,-1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mBeginIDX
4 | (4) `const int` | mEndIDX


### `Range<int,1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mBeginIDX
4 | (4) `const int` | mEndIDX


### `Range<unsigned int,1>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | mBeginIDX
4 | (4) `const unsigned int` | mEndIDX


### `ResourceLoadManager`
Offset | Type | Name
-|-|-|-
0 | (8) `Scheduler *` | mScheduler
8 | (8) `WorkerPool *` | mWorkerPool
16 | (48) `std::map<ResourceLoadType,std::unique_ptr<ResourceLoadManager::ResourceLoadTaskGroup>>` | mResourceLoadTaskGroups
64 | (8) `size_t` | mAppSuspended


### `RakNetInstance::ConnectionCallbacks`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ConnectionCallbacks


### `RakNetInstance`
Offset | Type | Name
-|-|-|-
0 | (8) `Connector` | baseclass_0
8 | (8) `RakNetInstance::ConnectionCallbacks *` | mCallbacks
16 | (152) `NetworkIdentifier` | mNATPunchServerId
168 | (240) `Social::GameConnectionInfo` | mBackupGameConnection
408 | (1) `bool` | mTryBackupConnection
416 | (16) `UniqueRakPeer` | mRakPeer
432 | (152) `NetworkIdentifier` | mServerId
584 | (160) `Connector::NatPunchInfo` | mNatPunchInfo
744 | (4) `RakNetInstance::NATState` | mNatState
752 | (24) `std::vector<RakNetInstance::NatConnectionInfo>` | mNatList
776 | (24) `RakPeerHelper` | mPeerHelper
800 | (8) `RakPeerHelper::IPSupportInterface *` | mIPSupportInterface
808 | (1) `bool` | mIsAwaitingNatClient
809 | (1) `bool` | mIsServer
810 | (1) `bool` | mIsDisconnecting
811 | (1) `bool` | mConnectingToClient
816 | (240) `Social::GameConnectionInfo` | mConnectedGameInfo
1056 | (56) `std::unordered_map<NetworkIdentifier,std::weak_ptr<RakNetInstance::RakNetNetworkPeer>>` | mPeers
1112 | (24) `std::vector<Connector::ConnectionStateListener *>` | mConnectionStateListeners
1136 | (1) `bool` | mWasHostWhenSuspended
1140 | (16) `ConnectionDefinition` | mPreviousConnectionDefinition
1160 | (32) `std::string` | mResolvedIP
1192 | (24) `std::vector<RakNetInstance::PingCallbackData>` | mPingTimeCallbacks


### `RakPeerHelper`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::StartupResult` | mResult
4 | (8) `int[2]` | mConnectionIndices
12 | (4) `uint16_t[2]` | mBoundPorts
16 | (8) `RakPeerHelper::IPSupportInterface *` | mIPSupportInterface


### `Range<unsigned long,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int64` | mBeginIDX
8 | (8) `const unsigned __int64` | mEndIDX


### `RakPeerHelper::IPSupportInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IPSupportInterface


### `ResourcePackInfoData`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mPackIdVersion
136 | (8) `uint64_t` | mPackSize
144 | (32) `std::string` | mContentKey
176 | (32) `std::string` | mSubpackName
208 | (24) `ContentIdentity` | mContentIdentity
232 | (1) `bool` | mHasScripts
233 | (1) `bool` | mHasExceptions


### `ResourceLoadManager::ResourceLoadTaskGroup`
Offset | Type | Name
-|-|-|-
0 | (4) `ResourceLoadType` | mLoadType
8 | (8) `std::unique_ptr<TaskGroup>` | mTaskGroup
16 | (24) `std::vector<ResourceLoadType>` | mDependencies
40 | (16) `ResourceLoadManager::TaskGroupState` | mTaskGroupState
56 | (1) `bool` | mTaskGroupPaused


### `ResourceLoadManager::TaskGroupState`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mRunning
8 | (8) `size_t` | mPaused


### `ResourcePath`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPackId
32 | (32) `std::string` | mPath


### `Range<unsigned short,1>`
Offset | Type | Name
-|-|-|-
0 | (2) `const unsigned __int16` | mBeginIDX
2 | (2) `const unsigned __int16` | mEndIDX


### `Range<short,1>`
Offset | Type | Name
-|-|-|-
0 | (2) `const __int16` | mBeginIDX
2 | (2) `const __int16` | mEndIDX


### `RandomHoverGoal`
Offset | Type | Name
-|-|-|-
0 | (16) `Goal` | baseclass_0
16 | (8) `Mob *` | mMob
24 | (4) `const float` | mSpeedModifier
28 | (4) `const int` | mInterval
32 | (4) `const float` | mXZDist
36 | (4) `const float` | mYDist
40 | (4) `float` | mYOffset
44 | (8) `IntRange` | mHoverHeight
56 | (8) `Unique<Path>` | mPath


### `Raid`
Offset | Type | Name
-|-|-|-
0 | (4) `Raid::RaidState` | mCurrentRaidState
4 | (1) `Raid::GroupNumberType` | mCurrentGroupNumber
5 | (1) `Raid::GroupNumberType` | mNumGroupsInRaid
8 | (8) `Tick` | mTicksInState
16 | (4) `const Raid::DurationType` | mRaidPreparationTime
20 | (4) `const Raid::DurationType` | mGroupCompleteDelay
24 | (4) `Raid::DurationType` | mTicksUntilGroupComplete
28 | (4) `const Raid::DurationType` | mLocationHelpDelay
32 | (4) `Raid::DurationType` | mTicksUntilLocationHelp
36 | (12) `Vec3` | mCurrentGroupSpawnPoint
48 | (56) `Raid::ActorIDCollection` | mRaiders
104 | (1) `Raid::RaiderCountType` | mNumRaidersSpawnedInCurrentGroup
105 | (1) `const Raid::FailureCountType` | mAllowedSpawnFailures
106 | (1) `Raid::FailureCountType` | mSpawnFailures
112 | (32) `const Raid::PickSpawnPointCallback` | mPickSpawnPointCallback
144 | (32) `const Raid::SpawnGroupCallback` | mSpawnGroupCallback
176 | (32) `const Raid::DoesActorExistCallback` | mDoesActorExistCallback
208 | (32) `Raid::NotificationCallback` | mOnSpawnPointChosenCallback
240 | (32) `Raid::NotificationCallback` | mOnGroupSpawnedCallback
272 | (32) `Raid::NotificationCallback` | mOnAwardRewardsCallback
304 | (32) `Raid::NotificationCallback` | mOnHelpLocateRaidersCallback


### `Raid::PickSpawnPointCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (unsigned long,Vec3 &)>::_Invoker_type` | _M_invoker


### `Raid::SpawnGroupCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (unsigned long,Vec3,unsigned char,std::unordered_set<ActorUniqueID> &)>::_Invoker_type` | _M_invoker


### `Raid::DoesActorExistCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (const ActorUniqueID &)>::_Invoker_type` | _M_invoker


### `Raid::NotificationCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Raid &)>::_Invoker_type` | _M_invoker


### `Rabbit::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `RespawnPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `Vec3` | mPos
48 | (1) `PlayerRespawnState` | mState
56 | (8) `ActorRuntimeID` | mRuntimeId


### `ReverseableIterator`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mStartValue
4 | (4) `const int` | mEndValue
8 | (1) `const bool` | mReversed


### `Recipes::Type`
Offset | Type | Name
-|-|-|-
0 | (8) `Item *` | mItem
8 | (8) `const Block *` | mBlock
16 | (24) `RecipeIngredient` | mIngredient
40 | (1) `char` | mC


### `Range<unsigned char,'_x01'>`
Offset | Type | Name
-|-|-|-
0 | (1) `const unsigned __int8` | mBeginIDX
1 | (1) `const unsigned __int8` | mEndIDX


### `ResourcePackManager`
Offset | Type | Name
-|-|-|-
0 | (40) `ResourceLoader` | baseclass_0
40 | (56) `std::unordered_set<ResourcePackListener *>` | mListeners
96 | (8) `std::unique_ptr<ResourcePackStack>` | mAddonStack
104 | (8) `std::unique_ptr<ResourcePackStack>` | mLevelStack
112 | (8) `std::unique_ptr<ResourcePackStack>` | mGlobalStack
120 | (8) `std::unique_ptr<ResourcePackStack>` | mTreatmentStack
128 | (8) `std::unique_ptr<ResourcePackStack>` | mBaseGameStack
136 | (8) `std::unique_ptr<ResourcePackStack>` | mFullStack
144 | (8) `std::unique_ptr<PackSourceReport>` | mLoadingReport
152 | (32) `std::string` | mLocaleCode
184 | (1) `bool` | mInitializing
185 | (1) `bool` | mPendingRestack
186 | (1) `bool` | mUseGlobalPackStack
187 | (1) `bool` | mExperimentalGameplay
192 | (56) `SharedMutex` | mFullStackAccess
248 | (8) `const ContentTierManager *` | mContentTierManager
256 | (112) `SemVersion` | mFullStackMinEngineVersion


### `ResourceLoader`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ResourceLoader
8 | (32) `std::function<Core::PathBuffer<std::string > ()>` | mGetPath


### `RopePoint`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mOldPos
12 | (12) `Vec3` | mToNewPos


### `RopeNode`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (12) `Vec3` | mPrevPos
24 | (1) `char` | mFrictionAxis


### `RopeAABB`
Offset | Type | Name
-|-|-|-
0 | (28) `AABB` | mBB
28 | (1) `bool` | mBlacklisted


### `RemoveObjectivePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mObjectiveName


### `RelativeFloat`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mOffset
4 | (1) `bool` | mRelative


### `RakNet::CCRakNetSlidingWindow`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | MAXIMUM_MTU_INCLUDING_UDP_HEADER
8 | (8) `double` | cwnd
16 | (8) `double` | ssThresh
24 | (8) `CCTimeType` | oldestUnsentAck
32 | (4) `DatagramSequenceNumberType` | nextDatagramSequenceNumber
36 | (4) `DatagramSequenceNumberType` | nextCongestionControlBlock
40 | (1) `bool` | backoffThisBlock
41 | (1) `bool` | speedUpThisBlock
44 | (4) `DatagramSequenceNumberType` | expectedNextSequenceNumber
48 | (1) `bool` | _isContinuousSend
56 | (8) `double` | lastRtt
64 | (8) `double` | estimatedRTT
72 | (8) `double` | deviationRtt


### `RakNet::ReliabilityLayer::DatagramHistoryNode`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::ReliabilityLayer::MessageNumberNode *` | head
8 | (8) `CCTimeType` | timeSent


### `RakNet::BPSTracker::TimeAndValue2`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | value1
8 | (8) `CCTimeType` | time


### `RealmsUnknownPackSource`
```
struct __cppobj RealmsUnknownPackSource : PackSource
{
  PackType mPackType;
  PackOrigin mPackOrigin;
  std::vector<std::unique_ptr<Pack>> mPacks;
  PackSourceReport mReport;
};

```

### `ResourcePack`
```
struct ResourcePack
{
  bool mHidden;
  bool mError;
  Pack *mPack;
  std::unique_ptr<PackAccessStrategy> mSubpackAccessStrategy;
  PackReport mPackReport;
  std::vector<std::unique_ptr<Pack>> mSubPacks;
  std::vector<std::unique_ptr<ResourcePack>> mSubResourcePacks;
  Core::HeapPathBuffer mIconPath;
  double mLoadTime;
  bool mIsBaseGamePack;
  bool mIsSlicePack;
  ResourceSignature mResourceSignature;
};

```

### `RakNet::TCPInterface`
```
struct RakNet::TCPInterface
{
  int (**_vptr$TCPInterface)(void);
  DataStructures::List<RakNet::PluginInterface2 *> messageHandlerList;
  RakNet::LocklessUint32_t isStarted;
  RakNet::LocklessUint32_t threadRunning;
  __TCPSOCKET__ listenSocket;
  unsigned __int16 listenPort;
  unsigned __int16 listenMaxIncomingConnections;
  unsigned __int16 listenSocketFamily;
  char *listenHostAddress;
  DataStructures::Queue<RakNet::Packet *> headPush;
  DataStructures::Queue<RakNet::Packet *> tailPush;
  RakNet::RemoteClient *remoteClients;
  int remoteClientsLength;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::Packet> incomingMessages;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress> newIncomingConnections;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress> lostConnections;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress> requestedCloseConnections;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::RemoteClient *> newRemoteClients;
  RakNet::SimpleMutex completedConnectionAttemptMutex;
  RakNet::SimpleMutex failedConnectionAttemptMutex;
  DataStructures::Queue<RakNet::SystemAddress> completedConnectionAttempts;
  DataStructures::Queue<RakNet::SystemAddress> failedConnectionAttempts;
  int threadPriority;
  DataStructures::List<int> blockingSocketList;
  RakNet::SimpleMutex blockingSocketListMutex;
};

```

### `ResetEventObj`
```
struct __attribute__((aligned(8))) ResetEventObj
{
  Bedrock::Threading::ConditionVariable mCondition;
  Bedrock::Threading::Mutex mMutex;
  std::atomic<bool> mSet;
  bool mAutoReset;
};

```

### `RaidBossSystem`
```
struct __cppobj RaidBossSystem : ITickingSystem
{
};

```

### `RailActivatorSystem`
```
struct __cppobj RailActivatorSystem : ITickingSystem
{
};

```

### `ReedsFeature`
```
struct __cppobj ReedsFeature : Feature
{
};

```

### `RoofTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) RoofTreeFeature : TreeFeature
{
};

```

### `ReferencedPieceList`
```
typedef std::vector<StructurePiece *> ReferencedPieceList;

```

### `RuntimeLightingManager`
```
struct RuntimeLightingManager
{
  std::unordered_map<ChunkPos,RuntimeLightingManager::RuntimeLightingSubchunkList> mLevelChunksToLight;
  std::vector<RuntimeLightingManager::RelightingChunkElement> mListOfChunksToProcess;
  std::vector<BlockPos> mProcessedSubchunks;
  std::vector<BlockPos> mBrightnessChangedList;
  Dimension *mDimension;
  bool mWorkerScheduled;
  float mLightingTimeboxTime;
};

```

### `RegionHillsLayer`
```
struct __cppobj RegionHillsLayer : UnaryLayer<Biome *,Biome *>
{
  LayerPtr<LayerValues::RiverData> mRiverLayer;
  const BiomeRegistry *mBiomeRegistry;
};

```

### `RandomScatteredLargeFeature`
```
struct __cppobj RandomScatteredLargeFeature : StructureFeature
{
  std::vector<int> allowedBiomes;
  int mSpacing;
  int mMinSeparation;
};

```

### `RootLayer<LayerValues::Terrain>`
```
struct __cppobj RootLayer<LayerValues::Terrain> : Layer<LayerValues::Terrain>
{
};

```

### `RootLayer<BiomeTemperatureCategory>`
```
struct __cppobj RootLayer<BiomeTemperatureCategory> : Layer<BiomeTemperatureCategory>
{
};

```

### `Realms::Player`
```
struct __attribute__((aligned(8))) Realms::Player
{
  std::string name;
  std::string xuid;
  std::string realName;
  Social::UserPicturePath gamerpicLocation;
  bool isOperator;
  bool hasAccepted;
  bool isOnline;
  PlayerPermissionLevel permission;
};

```

### `Realms::World`
```
struct __attribute__((aligned(8))) Realms::World
{
  Realms::RealmId id;
  Realms::World::State state;
  std::string name;
  std::string description;
  std::string ownerXuid;
  std::string ownerName;
  std::string clubId;
  int daysLeft;
  bool expired;
  int maxPlayers;
  bool newWorld;
  int gameMode;
  bool gracePeriod;
  int difficulty;
  bool cheatsEnabled;
  bool full;
  bool isMember;
  bool texturePacksRequired;
  PlayerPermissionLevel defaultPermission;
  std::vector<Realms::Player> players;
  bool mValid;
};

```

### `reverse_iterator`
```
typedef std::reverse_iterator<std::_Bit_iterator> reverse_iterator;

```

### `reference`
```
typedef std::_Bit_reference reference;

```

### `RailActivatorDescription`
```
struct __cppobj __attribute__((aligned(4))) RailActivatorDescription : ComponentDescription
{
  DefinitionTrigger mOnActivate;
  DefinitionTrigger mOnDeactivate;
  bool mCheckBlockTypes;
  bool mTickCommandBlockOnActivate;
  bool mTickCommandBlockOnDeactivate;
  bool mEjectOnActivate;
  bool mEjectOnDeactivate;
};

```

### `ResourceLoadManager::LoadOrder`
```
struct ResourceLoadManager::LoadOrder
{
  __int8 gap0[1];
};

```

### `ResourcePackFileDownloaderManager`
```
struct __cppobj ResourcePackFileDownloaderManager : std::enable_shared_from_this<ResourcePackFileDownloaderManager>
{
  int (**_vptr$ResourcePackFileDownloaderManager)(void);
  PacketSender *mPacketSender;
  std::string mResourceName;
  std::string mFileHash;
  bool mChunkWriteSuccess;
  Core::HeapPathBuffer mZipFilePath;
  Core::HeapPathBuffer mResourcePath;
  FileChunkManager mChunkManager;
  std::function<void (bool,const Core::Path &)> mCompletionCallback;
  std::function<void (float)> mProgressCallback;
  MPMCQueue<std::function<void ()> > mCallbackQueue;
  TaskGroup *mIOTaskGroup;
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

### `RakNetServerLocator`
```
struct __cppobj RakNetServerLocator : ServerLocator
{
  std::unordered_map<std::string,std::string> originalAddresses;
  std::unordered_map<std::string,RakNetServerLocator::PingRateRecorder> pingTimeRecorders;
  std::unordered_map<std::string,std::string> guidCache;
  std::function<RakNet::RakNetGUID ()> mGetHostGUID;
  RakNetInstance *mRaknetInstance;
  UniqueRakPeer mFinderPeer;
  RakPeerHelper mFinderPeerHelper;
  std::vector<PingedCompatibleServer> mAvailableServers;
  bool mIsPingingForServers;
  const bool mIsServer;
  int mPingPort;
  int mPingPortv6;
  RakNet::TimeMS mLastPingTime;
  std::vector<std::string> mBroadcastAddresses;
  std::vector<std::string> mMulticastAddressesV6;
  std::queue<std::pair<AsynchronousIPResolver,int>> mPingQueue;
  std::function<void (bool)> mServerValidationCallback;
  std::string mServerWaitingToValidate;
  RakNet::TimeMS mLastPingToServerWaitingToValidateTime;
  Bedrock::Threading::RecursiveMutex mServerListLock;
};

```

### `ResourcePackTransmissionManager`
```
struct ResourcePackTransmissionManager
{
  std::unordered_map<unsigned long,std::unordered_map<std::string,std::shared_ptr<ResourcePackFileDownloaderManager>>> mResourceDownloadManagers;
  std::unordered_map<unsigned long,std::unordered_map<std::string,std::shared_ptr<ResourcePackFileUploadManager>>> mResourceUploadManagers;
  std::unordered_set<unsigned long> mRemovedResourceDownloadManagers;
  std::unordered_set<unsigned long> mRemovedResourceUploadManagers;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
};

```

### `RakNet::RakPeerInterface`
```
struct RakNet::RakPeerInterface
{
  int (**_vptr$RakPeerInterface)(void);
};

```

### `ResourcePackClientResponsePacket`
```
struct __cppobj __attribute__((aligned(8))) ResourcePackClientResponsePacket : Packet
{
  std::set<std::string> mDownloadingPacks;
  ResourcePackResponse mResponse;
};

```

### `RiderJumpPacket`
```
struct __cppobj RiderJumpPacket : Packet:288
{
  int mJumpScale;
};

```

### `RemoveEntityPacket`
```
struct __cppobj RemoveEntityPacket : EntityServerPacket
{
};

```

### `RequestChunkRadiusPacket`
```
struct __cppobj RequestChunkRadiusPacket : Packet:288
{
  int mChunkRadius;
};

```

### `RakNetInstance::RakNetNetworkPeer`
```
struct __cppobj __attribute__((aligned(8))) RakNetInstance::RakNetNetworkPeer : NetworkPeer
{
  RakNet::RakPeerInterface *mRakPeer;
  NetworkIdentifier mId;
  std::string mSendBuffer;
  std::vector<std::string> mReadBuffers;
  int mApproximateMaxBps;
  int mLastPing;
  int mAveragePing;
};

```

### `RakNetInstance::PingCallbackData`
```
struct RakNetInstance::PingCallbackData
{
  std::string mAddress;
  std::function<void (unsigned int)> mAction;
};

```

### `RakNetServerLocator::PingRateRecorder`
```
struct __attribute__((aligned(8))) RakNetServerLocator::PingRateRecorder
{
  std::vector<unsigned long> mPingTimes;
  unsigned int mAveragingWindowSize;
  float mAverageTime;
  float mLastPingTime;
  RakNet::TimeMS mStartTime;
  unsigned int mPingTimesIndex;
  int mIpVersion;
  bool mPingStarted;
  bool mAveraging;
};

```

### `Recipe`
```
struct Recipe
{
  int (**_vptr$Recipe)(void);
  std::string mRecipeId;
  ItemPack mMyItems;
  mce::UUID mMyId;
  int mWidth;
  int mHeight;
  int mPriority;
  Recipe::Ingredients mMyIngredients;
  Util::HashString mTag;
};

```

### `Recipes`
```
struct Recipes
{
  ResourcePackManager *mResourcePackManager;
  std::map<Util::HashString,std::map<std::string,std::unique_ptr<Recipe>>> mRecipes;
  std::map<Recipes::FurnaceRecipeKey,ItemInstance> mFurnaceRecipes;
  bool mInitializing;
  std::map<ItemInstance,std::unordered_map<std::string,Recipe *>,SortItemInstanceIdAux,std::allocator<std::pair<const ItemInstance,std::unordered_map<std::string,Recipe *> > > > mRecipesByOutput;
  RecipeListenerList mListeners;
};

```

### `RecipeListenerList`
```
typedef std::vector<std::pair<std::weak_ptr<bool>,std::function<void ()> >> RecipeListenerList;

```

### `RepairItemRecipe`
```
struct __cppobj RepairItemRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `ResourceLocationPair`
```
struct __attribute__((aligned(8))) ResourceLocationPair
{
  ResourceLocation mResourceLocation;
  PackIdVersion mPackId;
  int mPackPosition;
};

```

### `RandomThreadCheckManager`
```
struct __cppobj __attribute__((aligned(8))) RandomThreadCheckManager : AppPlatformListener
{
  std::atomic_uint mSuspendResumeIndex;
};

```

### `RopeSystem`
```
struct RopeSystem
{
  bool mWaveApplied;
  RopePoints mQueuedRenderPoints;
  RopePoints mRenderPoints;
  std::vector<RopeNode> mNodes;
  std::vector<AABBBucket> mColliderBuckets;
  std::vector<RopeWave> mWaves;
  RopeParams mParams;
  std::set<AABB,AABBPred,std::allocator<AABB> > mBlacklistedColliders;
  Vec3 mPrevStartPin;
  Vec3 mPrevEndPin;
  size_t mCutNode;
  size_t mCutRenderNode;
  size_t mMinNodes;
  size_t mCutTicks;
  ActorUniqueID mEndPinEntity;
  std::atomic_flag mTicking;
  Bedrock::Threading::Mutex mRenderMutex;
  bool mAbandonCollision;
  Vec3 mStartPin;
  Vec3 mEndPin;
  size_t mToCutNode;
};

```

### `RopePoints`
```
struct RopePoints
{
  size_t mSize;
  std::vector<RopePoint> mPoints;
};

```

### `RaidTriggerDescription`
```
struct __cppobj RaidTriggerDescription : ComponentDescription
{
  DefinitionTrigger mOnTriggered;
};

```

### `RideableDescription`
```
struct __cppobj __attribute__((aligned(8))) RideableDescription : ComponentDescription
{
  int mSeatCount;
  int mControllingSeat;
  bool mSkipInteractIfCrouching;
  std::vector<SeatDescription> mSeats;
  Util::hashStringSet mFamilyTypes;
  std::string mInteractText;
  bool mPullInEntities;
  bool mRiderCanPick;
};

```

### `RopePointsRef`
```
struct RopePointsRef
{
  const RopePoints *mPoints;
  Bedrock::Threading::Mutex *mPointMutex;
};

```

### `RemovedActorDamageByType`
```
struct __cppobj RemovedActorDamageByType : ActorDamageSource:96
{
  ActorType mEntityType;
};

```

### `Rabbit`
```
struct __cppobj Rabbit : Animal
{
  int mMoreCarrotTicks;
  int mCarrotsEaten;
};

```

### `RaiderCelebrationGoal`
```
struct __cppobj RaiderCelebrationGoal : Goal
{
  Mob *mMob;
  LevelSoundEvent mSoundEvent;
  FloatRange mSoundIntervalRange;
  FloatRange mJumpIntervalRange;
  int mNextJumpTickTimer;
  int mNextSoundTickTimer;
  int mDurationInTicks;
  int mRuntimeTicks;
  const DefinitionTrigger mOnEndEvent;
};

```

### `RunAroundLikeCrazyGoal`
```
struct __cppobj RunAroundLikeCrazyGoal : Goal
{
  Mob *mMob;
  float mSpeedModifier;
  Vec3 mPos;
};

```

### `RestrictSunGoal`
```
struct __cppobj RestrictSunGoal : Goal
{
  Mob *mMob;
};

```

### `RestrictOpenDoorGoal`
```
struct __cppobj RestrictOpenDoorGoal : Goal
{
  Mob *mMob;
};

```

### `RandomLookAroundGoal`
```
struct __cppobj RandomLookAroundGoal : Goal:96
{
  float mRelX;
  float mRelZ;
  int mTotalLookTime;
  int mMinLookTime;
  int mMaxLookTime;
  float mProbability;
  Mob *mMob;
};

```

### `RandomSitGoal`
```
struct __cppobj __attribute__((aligned(8))) RandomSitGoal : Goal
{
  Mob *mMob;
  const float mStartChance;
  const float mStopChance;
  uint64_t mCooldown;
  const int mSitCooldownTotal;
  const int mMinSitTick;
  int mCurrentSitTick;
};

```

### `RandomLookAroundAndSitGoal`
```
struct __cppobj __attribute__((aligned(8))) RandomLookAroundAndSitGoal : RandomLookAroundGoal
{
  int mMinLookCount;
  int mMaxLookCount;
  int mTotalLookCount;
};

```

### `RangedAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) RangedAttackGoal : Goal
{
  Mob *mMob;
  TempEPtr<Actor> mTarget;
  int mAttackTime;
  float mSpeedModifier;
  int mSeeTime;
  int mAttackIntervalMin;
  int mAttackIntervalMax;
  float mAttackRadius;
  float mAttackRadiusSqr;
  float mFOV;
  bool mIsChargedAttack;
  int mChargeShootTrigger;
  int mChargeChargedTrigger;
  int mCharge;
  int mBurstShots;
  int mBurstShotsLeft;
  int mBurstInterval;
  int mBurstTime;
  bool mUsingChargedItem;
};

```

### `RandomBreachingGoal`
```
struct RandomBreachingGoal
{
  __int8 baseclass_0[68];
  int mCooldown;
  int mTimer;
  int mAttempts;
};

```

### `RandomStrollGoal`
```
struct __cppobj __attribute__((aligned(8))) RandomStrollGoal : Goal
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

### `RandomSwimmingGoal`
```
struct __cppobj __attribute__((aligned(8))) RandomSwimmingGoal : RandomStrollGoal
{
};

```

### `RandomFlyingGoal`
```
struct __attribute__((aligned(8))) RandomFlyingGoal
{
  __int8 baseclass_0[66];
  bool mCanLandOnTrees;
};

```

### `ReceiveLoveGoal`
```
struct __cppobj ReceiveLoveGoal : Goal
{
  VillagerBase *mVillager;
};

```

### `RollGoal`
```
struct __cppobj __attribute__((aligned(8))) RollGoal : Goal
{
  Mob *mMob;
  float mRollXd;
  float mRollZd;
  float mProbability;
};

```

### `RaidGardenGoal`
```
struct __cppobj RaidGardenGoal : BaseMoveToBlockGoal
{
  int mMaxToEat;
  int mEaten;
  int mEatDelay;
  int mHasEatenFillDelay;
  int mInitialEatDelay;
  int mEatTimer;
  int mHasEatenFillTimer;
  std::set<const Block *> mEatBlocks;
};

```

### `RandomStrollGoal:528`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(2))) RandomStrollGoal:528 : Goal
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

### `RandomPos`
```
struct RandomPos
{
  __int8 gap0[1];
};

```

### `RiverFollowingGoal`
```
struct __cppobj __attribute__((aligned(8))) RiverFollowingGoal : Goal
{
  Mob *mMob;
  Vec3 mHeading;
  float mLookAhead;
  float mSpeed;
};

```

### `RemoveOnHitSubcomponent`
```
struct __cppobj RemoveOnHitSubcomponent : OnHitSubcomponent
{
};

```

### `RapidFertilizerItem`
```
struct __cppobj __attribute__((aligned(8))) RapidFertilizerItem : FertilizerItem
{
};

```

### `RecordItem`
```
struct __cppobj RecordItem : Item
{
  LevelSoundEvent mSoundEvent;
  float mDuration;
};

```

### `RedStoneDustItem`
```
struct __cppobj RedStoneDustItem : Item
{
};

```

### `RecipeListener`
```
typedef std::pair<std::weak_ptr<bool>,std::function<void ()> > RecipeListener;

```

### `RiverTransformationAttributes`
```
typedef WeightedBiomeAttributes<RiverTransformation> RiverTransformationAttributes;

```

### `RepeaterBlock`
```
struct __cppobj __attribute__((aligned(8))) RepeaterBlock : DiodeBlock
{
};

```

### `RandomizableBlockActorFillingContainer`
```
struct __cppobj RandomizableBlockActorFillingContainer : RandomizableBlockActorContainerBase, FillingContainer
{
};

```

### `RandomizableBlockActorContainerBase`
```
struct __cppobj __attribute__((aligned(8))) RandomizableBlockActorContainerBase : BlockActor
{
  std::string mLootTable;
  int mLootTableSeed;
};

```

### `RandomizableBlockActorContainer`
```
struct __cppobj RandomizableBlockActorContainer : RandomizableBlockActorContainerBase, Container
{
};

```

### `RedStoneWireBlock`
```
struct __cppobj RedStoneWireBlock : BlockLegacy
{
};

```

### `RailBlock`
```
struct __cppobj __attribute__((aligned(8))) RailBlock : BaseRailBlock
{
};

```

### `RedStoneOreBlock`
```
struct __cppobj __attribute__((aligned(8))) RedStoneOreBlock : BlockLegacy
{
  bool mLit;
};

```

### `RedstoneTorchBlock`
```
struct __cppobj __attribute__((aligned(8))) RedstoneTorchBlock : TorchBlock
{
  bool mOn;
};

```

### `ReedBlock`
```
struct __cppobj ReedBlock : BlockLegacy
{
};

```

### `RedstoneLampBlock`
```
struct __cppobj __attribute__((aligned(8))) RedstoneLampBlock : BlockLegacy
{
  const bool mIsLit;
};

```

### `RedstoneBlock`
```
struct __cppobj RedstoneBlock : BlockLegacy
{
};

```

### `RotatedPillarBlock`
```
struct __cppobj RotatedPillarBlock : BlockLegacy
{
};

```

### `RuntimeLightingManager::RuntimeLightingSubchunkList`
```
struct RuntimeLightingManager::RuntimeLightingSubchunkList
{
  std::array<std::vector<SubChunkLightUpdate>,16> mAlteredSubchunkBlockList;
};

```

### `RandomAuxValueFunction`
```
struct __cppobj RandomAuxValueFunction : LootItemFunction
{
  RandomValueBounds mValues;
};

```

### `RandomBlockStateFunction`
```
struct __cppobj RandomBlockStateFunction : LootItemFunction
{
  RandomValueBounds mValues;
  std::string mBlockStateName;
};

```

### `RepeaterCapacitor`
```
struct __cppobj RepeaterCapacitor : CapacitorComponent:544
{
  RepeaterCapacitor::States mOnStates[5];
  int mInsertAt;
  bool mPowered;
  bool mNextPower;
  bool mLocked;
  int mPulseCount;
  bool mPulse;
  bool mNextPulse;
  CircuitComponentList mSideComponents;
};

```

### `RedstoneTorchCapacitor`
```
struct __cppobj __attribute__((aligned(8))) RedstoneTorchCapacitor : CapacitorComponent
{
  RedstoneTorchCapacitor *mNextOrder;
  int mSelfPowerCount;
  RedstoneTorchCapacitor::State mState[2];
  bool mCanReigniteFromBurnout;
};

```

### `RailMovementSystem`
```
struct __cppobj RailMovementSystem : ITickingSystem
{
};

```

### `RoleChecker`
```
struct RoleChecker
{
  std::weak_ptr<RoleCheckerCallback> mPendingCallback;
};

```

### `RoleCheckerCallback`
```
struct RoleCheckerCallback
{
  RoleChecker::OnRoleAcquired mCallback;
};

```

### `ReloadCommand`
```
struct __cppobj ReloadCommand : Command
{
};

```

### `ReplaceItemCommand`
```
struct __cppobj __attribute__((aligned(8))) ReplaceItemCommand : Command
{
  ReplaceItemCommand::TargetType mTargetType;
  ActorSelector mTargetEntity;
  CommandPosition mTargetBlock;
  BlockSlot mBlockSlot;
  EquipmentSlot mEquipmentSlot;
  int mSlotId;
  CommandItem mItem;
  int mAmount;
  int mData;
  Json::Value mComponents;
  bool mHaveComponents;
};

```

### `RailMovementDefinition`
```
struct RailMovementDefinition
{
  float mMaxSpeed;
};

```

### `RepeatUntilSuccessDefinition`
```
struct __cppobj RepeatUntilSuccessDefinition : DecoratorDefinition
{
  int mMaxNumberOfAttempts;
  std::string mMaxNumberOfAttemptsId;
};

```

### `RepeatUntilSuccessNode`
```
struct __cppobj RepeatUntilSuccessNode : BehaviorNode
{
  Unique<BehaviorNode> mActiveChild;
  int mMaxNumberOfAttempts;
  int mCurrentAttempt;
};

```

### `RepeatUntilFailureDefinition`
```
struct __cppobj RepeatUntilFailureDefinition : DecoratorDefinition
{
};

```

### `RepeatUntilFailureNode`
```
struct __cppobj RepeatUntilFailureNode : BehaviorNode
{
  Unique<BehaviorNode> mActiveChild;
};

```

### `RangedWeaponItem`
```
struct __cppobj RangedWeaponItem : Item
{
};

```

### `RegionFile`
```
struct RegionFile
{
  int (**_vptr$RegionFile)(void);
  Core::File mFile;
  Core::HeapPathBuffer mFileName;
  std::array<int,1024> mOffsets;
  std::array<int,1024> mEmptyChunk;
  RegionFile::FreeSectorMap mSectorFree;
};

```

### `RegionFile::FreeSectorMap`
```
typedef std::map<int,bool> RegionFile::FreeSectorMap;

```

### `RedstoneTorchCapacitor::State`
```
struct RedstoneTorchCapacitor::State
{
  bool mOn;
  bool mHalfFrame;
  bool mChanged;
};

```

### `RailMovement`
```
struct RailMovement
{
  __int8 gap0[1];
};

```

### `RakNet::RakPeer`
```
struct __cppobj __attribute__((aligned(8))) RakNet::RakPeer : RakNet::RakPeerInterface, RakNet::RNS2EventHandler
{
  volatile bool endThreads;
  volatile bool isMainLoopThreadActive;
  bool occasionalPing;
  unsigned int maximumNumberOfPeers;
  unsigned int maximumIncomingConnections;
  RakNet::BitStream offlinePingResponse;
  char incomingPassword[256];
  unsigned __int8 incomingPasswordLength;
  RakNet::RakPeer::RemoteSystemStruct *remoteSystemList;
  RakNet::RakPeer::RemoteSystemStruct **activeSystemList;
  unsigned int activeSystemListSize;
  RakNet::RemoteSystemIndex **remoteSystemLookup;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex> remoteSystemIndexPool;
  RakNet::SimpleMutex rakPeerMutexes[2];
  bool updateCycleIsRunning;
  unsigned int bytesSentPerSecond;
  unsigned int bytesReceivedPerSecond;
  unsigned int validationInteger;
  RakNet::SimpleMutex incomingQueueMutex;
  RakNet::SimpleMutex banListMutex;
  DataStructures::List<RakNet::RakPeer::BanStruct *> banList;
  DataStructures::List<RakNet::PluginInterface2 *> pluginListTS;
  DataStructures::List<RakNet::PluginInterface2 *> pluginListNTS;
  DataStructures::Queue<RakNet::RakPeer::RequestedConnectionStruct *> requestedConnectionQueue;
  RakNet::SimpleMutex requestedConnectionQueueMutex;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::BufferedCommandStruct> bufferedCommands;
  DataStructures::Queue<RakNet::RNS2RecvStruct *> bufferedPacketsFreePool;
  RakNet::SimpleMutex bufferedPacketsFreePoolMutex;
  DataStructures::Queue<RakNet::RNS2RecvStruct *> bufferedPacketsQueue;
  RakNet::SimpleMutex bufferedPacketsQueueMutex;
  DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::SocketQueryOutput> socketQueryOutput;
  RakNet::SimpleMutex securityExceptionMutex;
  int defaultMTUSize;
  bool trackFrequencyTable;
  DataStructures::List<RakNet::RakNetSocket2 *> socketList;
  RakNet::BitStream *replyFromTargetBS;
  RakNet::SystemAddress replyFromTargetPlayer;
  bool replyFromTargetBroadcast;
  RakNet::TimeMS defaultTimeoutTime;
  RakNet::RakNetGUID myGuid;
  unsigned int maxOutgoingBPS;
  bool allowConnectionResponseIPMigration;
  RakNet::SystemAddress firstExternalID;
  int splitMessageProgressInterval;
  RakNet::TimeMS unreliableTimeout;
  bool (*incomingDatagramEventHandler)(RakNet::RNS2RecvStruct *);
  DataStructures::List<RakNet::RakString> securityExceptionList;
  RakNet::SystemAddress ipList[21];
  RakNet::NetworkAdapter adapterList[11];
  bool allowInternalRouting;
  void (*userUpdateThreadPtr)(RakNet::RakPeerInterface *, void *);
  void *userUpdateThreadData;
  RakNet::SignaledEvent quitAndDataEvents;
  bool limitConnectionFrequencyFromTheSameIP;
  RakNet::SimpleMutex packetAllocationPoolMutex;
  DataStructures::MemoryPool<RakNet::Packet> packetAllocationPool;
  RakNet::SimpleMutex packetReturnMutex;
  DataStructures::Queue<RakNet::Packet *> packetReturnQueue;
  RakNet::SimpleMutex sendReceiptSerialMutex;
  uint32_t sendReceiptSerial;
};

```

### `RakNet::RNS2EventHandler`
```
struct RakNet::RNS2EventHandler
{
  int (**_vptr$RNS2EventHandler)(void);
};

```

### `RakNet::RakPeer::RemoteSystemStruct`
```
struct RakNet::RakPeer::RemoteSystemStruct
{
  bool isActive;
  RakNet::SystemAddress systemAddress;
  RakNet::SystemAddress myExternalSystemAddress;
  RakNet::SystemAddress theirInternalSystemAddress[20];
  RakNet::ReliabilityLayer reliabilityLayer;
  bool weInitiatedTheConnection;
  RakNet::RakPeer::PingAndClockDifferential pingAndClockDifferential[5];
  RakNet::Time pingAndClockDifferentialWriteIndex;
  unsigned __int16 lowestPing;
  RakNet::Time nextPingTime;
  RakNet::Time lastReliableSend;
  RakNet::Time connectionTime;
  RakNet::RakNetGUID guid;
  int MTUSize;
  RakNet::RakNetSocket2 *rakNetSocket;
  RakNet::SystemIndex remoteSystemIndex;
  RakNet::RakPeer::RemoteSystemStruct::ConnectMode connectMode;
};

```

### `RakNet::ReliabilityLayer`
```
struct RakNet::ReliabilityLayer
{
  DataStructures::Queue<RakNet::InternalPacket *> outputQueue;
  int splitMessageProgressInterval;
  CCTimeType unreliableTimeout;
  DataStructures::Queue<RakNet::ReliabilityLayer::DatagramHistoryNode> datagramHistory;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode> datagramHistoryMessagePool;
  DataStructures::List<RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode> unreliableWithAckReceiptHistory;
  DatagramSequenceNumberType datagramHistoryPopCount;
  DataStructures::MemoryPool<RakNet::InternalPacket> internalPacketPool;
  RakNet::InternalPacket *resendBuffer[512];
  RakNet::InternalPacket *resendLinkedListHead;
  RakNet::InternalPacket *unreliableLinkedListHead;
  RakNet::TimeMS timeLastDatagramArrived;
  DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false> outgoingPacketBuffer;
  RakNet::reliabilityHeapWeightType outgoingPacketBufferNextWeights[4];
  DataStructures::OrderedList<unsigned short,RakNet::SplitPacketChannel *,&RakNet::SplitPacketChannelComp> splitPacketChannelList;
  RakNet::MessageNumberType sendReliableMessageNumberIndex;
  RakNet::MessageNumberType internalOrderIndex;
  bool deadConnection;
  bool cheater;
  RakNet::SplitPacketIdType splitPacketId;
  RakNet::TimeMS timeoutTime;
  RakNet::RakNetStatistics statistics;
  RakNet::OrderingIndexType orderedWriteIndex[32];
  RakNet::OrderingIndexType sequencedWriteIndex[32];
  RakNet::OrderingIndexType orderedReadIndex[32];
  RakNet::OrderingIndexType highestSequencedReadIndex[32];
  DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false> orderingHeaps[32];
  RakNet::OrderingIndexType heapIndexOffsets[32];
  DataStructures::Queue<bool> hasReceivedPacketQueue;
  DatagramSequenceNumberType receivedPacketsBaseIndex;
  bool resetReceivedPackets;
  CCTimeType lastUpdateTime;
  CCTimeType timeBetweenPackets;
  CCTimeType nextSendTime;
  CCTimeType ackPingSum;
  unsigned __int8 ackPingIndex;
  RakNet::RemoteSystemTimeType remoteSystemTime;
  CCTimeType nextAllowedThroughputSample;
  bool bandwidthExceededStatistic;
  __int64 throughputCapCountdown;
  unsigned int receivePacketCount;
  CCTimeType elapsedTimeSinceLastUpdate;
  CCTimeType nextAckTimeToSend;
  RakNet::CCRakNetSlidingWindow congestionManager;
  uint32_t unacknowledgedBytes;
  DataStructures::List<RakNet::InternalPacket *> packetsToSendThisUpdate;
  DataStructures::List<bool> packetsToDeallocThisUpdate;
  DataStructures::List<unsigned int> packetsToSendThisUpdateDatagramBoundaries;
  DataStructures::List<bool> datagramsToSendThisUpdateIsPair;
  DataStructures::List<unsigned int> datagramSizesInBytes;
  RakNet::BitSize_t datagramSizeSoFar;
  RakNet::BitSize_t allDatagramSizesSoFar;
  double totalUserDataBytesAcked;
  CCTimeType timeOfLastContinualSend;
  CCTimeType timeToNextUnreliableCull;
  DataStructures::RangeList<RakNet::uint24_t> incomingAcks;
  int countdownToNextPacketPair;
  DataStructures::RangeList<RakNet::uint24_t> acknowlegements;
  DataStructures::RangeList<RakNet::uint24_t> NAKs;
  bool remoteSystemNeedsBAndAS;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData> refCountedDataPool;
  RakNet::BPSTracker bpsMetrics[7];
  CCTimeType lastBpsClear;
};

```

### `RakNet::InternalPacketRefCountedData`
```
struct __attribute__((aligned(8))) RakNet::InternalPacketRefCountedData
{
  unsigned __int8 *sharedDataBlock;
  unsigned int refCount;
};

```

### `RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode`
```
struct RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode
{
  DatagramSequenceNumberType datagramNumber;
  uint32_t sendReceiptSerial;
  RakNet::TimeUS nextActionTime;
};

```

### `RakNet::SplitPacketChannel`
```
struct RakNet::SplitPacketChannel
{
  CCTimeType lastUpdateTime;
  RakNet::SortedSplittedPackets splitPacketList;
  RakNet::InternalPacket *firstPacket;
};

```

### `RakNet::BPSTracker`
```
struct RakNet::BPSTracker
{
  uint64_t total1;
  uint64_t lastSec1;
  DataStructures::Queue<RakNet::BPSTracker::TimeAndValue2> dataQueue;
};

```

### `RakNet::RakPeer::PingAndClockDifferential`
```
struct RakNet::RakPeer::PingAndClockDifferential
{
  unsigned __int16 pingTime;
  RakNet::Time clockDifferential;
};

```

### `RakNet::RakNetSocket2`
```
struct __attribute__((aligned(8))) RakNet::RakNetSocket2
{
  int (**_vptr$RakNetSocket2)(void);
  RakNet::RNS2EventHandler *eventHandler;
  RakNet::RNS2Type socketType;
  RakNet::SystemAddress boundAddress;
  unsigned int userConnectionSocketIndex;
};

```

### `RakNet::RemoteSystemIndex`
```
struct RakNet::RemoteSystemIndex
{
  unsigned int index;
  RakNet::RemoteSystemIndex *next;
};

```

### `RakNet::RakPeer::BanStruct`
```
struct __attribute__((aligned(8))) RakNet::RakPeer::BanStruct
{
  char *IP;
  RakNet::TimeMS timeout;
};

```

### `RakNet::PluginInterface2`
```
struct RakNet::PluginInterface2
{
  int (**_vptr$PluginInterface2)(void);
  RakNet::RakPeerInterface *rakPeerInterface;
  RakNet::TCPInterface *tcpInterface;
};

```

### `RakNet::RakPeer::RequestedConnectionStruct`
```
struct __attribute__((aligned(8))) RakNet::RakPeer::RequestedConnectionStruct
{
  RakNet::SystemAddress systemAddress;
  RakNet::Time nextRequestTime;
  unsigned __int8 requestsMade;
  char *data;
  unsigned __int16 dataLength;
  char outgoingPassword[256];
  unsigned __int8 outgoingPasswordLength;
  unsigned int socketIndex;
  unsigned int extraData;
  unsigned int sendConnectionAttemptCount;
  unsigned int timeBetweenSendConnectionAttemptsMS;
  RakNet::TimeMS timeoutTime;
  RakNet::PublicKeyMode publicKeyMode;
  RakNet::RakNetSocket2 *socket;
  RakNet::RakPeer::RequestedConnectionStruct::$FD3B22BB7AF8A0ABB9D04D1A9E595697 actionToTake;
};

```

### `RakNet::RakPeer::BufferedCommandStruct`
```
struct __attribute__((aligned(8))) RakNet::RakPeer::BufferedCommandStruct
{
  RakNet::BitSize_t numberOfBitsToSend;
  PacketPriority priority;
  PacketReliability reliability;
  char orderingChannel;
  RakNet::AddressOrGUID systemIdentifier;
  bool broadcast;
  RakNet::RakPeer::RemoteSystemStruct::ConnectMode connectionMode;
  RakNet::NetworkID networkID;
  bool blockingCommand;
  char *data;
  bool haveRakNetCloseSocket;
  unsigned int connectionSocketIndex;
  unsigned __int16 remotePortRakNetWasStartedOn_PS3;
  unsigned int extraSocketOptions;
  RakNet::RakNetSocket2 *socket;
  unsigned __int16 port;
  uint32_t receipt;
  RakNet::RakPeer::BufferedCommandStruct::$D8D77DCE4D37D1D6016B84EB664ECA65 command;
};

```

### `RakNet::RNS2RecvStruct`
```
struct RakNet::RNS2RecvStruct
{
  char data[1400];
  int bytesRead;
  RakNet::SystemAddress systemAddress;
  RakNet::TimeUS timeRead;
  RakNet::RakNetSocket2 *socket;
};

```

### `RakNet::RakPeer::SocketQueryOutput`
```
struct RakNet::RakPeer::SocketQueryOutput
{
  DataStructures::List<RakNet::RakNetSocket2 *> sockets;
};

```

### `RakNet::SignaledEvent`
```
struct __attribute__((aligned(8))) RakNet::SignaledEvent
{
  RakNet::SimpleMutex isSignaledMutex;
  bool isSignaled;
  pthread_condattr_t condAttr;
  pthread_cond_t eventList;
  pthread_mutex_t hMutex;
  pthread_mutexattr_t mutexAttr;
};

```

### `RakNet::ReliabilityLayer::MessageNumberNode`
```
struct RakNet::ReliabilityLayer::MessageNumberNode
{
  DatagramSequenceNumberType messageNumber;
  RakNet::ReliabilityLayer::MessageNumberNode *next;
};

```

### `RakNet::RNS2_Berkley`
```
struct __cppobj __attribute__((aligned(4))) RakNet::RNS2_Berkley : RakNet::IRNS2_Berkley:1312
{
  RakNet::RNS2Socket rns2Socket;
  RakNet::RNS2_BerkleyBindParameters binding;
  RakNet::LocklessUint32_t isRecvFromLoopThreadActive;
  volatile bool endThreads;
};

```

### `RakNet::RakThread`
```
struct RakNet::RakThread
{
  __int8 gap0[1];
};

```

### `RakNet::SortedSplittedPackets`
```
struct __attribute__((aligned(8))) RakNet::SortedSplittedPackets
{
  RakNet::InternalPacket **data;
  unsigned int allocation_size;
  unsigned int addedPacketsCount;
  RakNet::SplitPacketIdType packetId;
};

```

### `RakNet::SocketLayer`
```
struct RakNet::SocketLayer
{
  __int8 gap0[1];
};

```

### `RakNet::StringCompressor`
```
struct RakNet::StringCompressor
{
  DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison> huffmanEncodingTrees;
};

```

### `RakNet::HuffmanEncodingTree`
```
struct RakNet::HuffmanEncodingTree
{
  HuffmanEncodingTreeNode *root;
  RakNet::HuffmanEncodingTree::CharacterEncoding encodingTable[256];
};

```

### `RakNet::HuffmanEncodingTree::CharacterEncoding`
```
struct __attribute__((aligned(8))) RakNet::HuffmanEncodingTree::CharacterEncoding
{
  unsigned __int8 *encoding;
  unsigned __int16 bitLength;
};

```

### `RakNet::StringTable`
```
struct RakNet::StringTable
{
  DataStructures::OrderedList<char *,StrAndBool,&RakNet::StrAndBoolComp> orderedStringList;
};

```

### `RakNet::LocklessUint32_t`
```
struct RakNet::LocklessUint32_t
{
  volatile uint32_t value;
};

```

### `RakNet::RemoteClient`
```
struct RakNet::RemoteClient
{
  __TCPSOCKET__ socket;
  RakNet::SystemAddress systemAddress;
  DataStructures::ByteQueue outgoingData;
  bool isActive;
  RakNet::SimpleMutex outgoingDataMutex;
  RakNet::SimpleMutex isActiveMutex;
};

```

### `RakNet::TCPInterface::ThisPtrPlusSysAddr`
```
struct __attribute__((aligned(8))) RakNet::TCPInterface::ThisPtrPlusSysAddr
{
  RakNet::TCPInterface *tcpInterface;
  RakNet::SystemAddress systemAddress;
  bool useSSL;
  char bindAddress[64];
  unsigned __int16 socketFamily;
};

```

### `RakNet::IRNS2_Berkley`
```
struct __cppobj RakNet::IRNS2_Berkley : RakNet::RakNetSocket2
{
};

```

### `RakNet::RakNetSocket2:1312`
```
struct __attribute__((packed)) __attribute__((aligned(4))) RakNet::RakNetSocket2:1312
{
  int (**_vptr$RakNetSocket2)(void);
  RakNet::RNS2EventHandler *eventHandler;
  RakNet::RNS2Type socketType;
  _BYTE gap14[4];
  RakNet::SystemAddress boundAddress;
  unsigned int userConnectionSocketIndex;
};

```

### `RakNet::IRNS2_Berkley:1312`
```
struct __cppobj RakNet::IRNS2_Berkley:1312 : RakNet::RakNetSocket2:1312
{
};

```

### `RakNet::RNS2_Windows_Linux_360`
```
struct RakNet::RNS2_Windows_Linux_360
{
  __int8 gap0[1];
};

```

### `RakNet::RakNetSocket2Allocator`
```
struct RakNet::RakNetSocket2Allocator
{
  __int8 gap0[1];
};

```

### `RakNet::RNS2_Linux`
```
struct __cppobj __attribute__((aligned(4))) RakNet::RNS2_Linux : RakNet::RNS2_Berkley
{
};

```

### `ResourceUtil`
```
struct ResourceUtil
{
  __int8 gap0[1];
};

```

### `RateLimiter`
```
struct RateLimiter
{
  const size_t mLimit;
  const std::chrono::seconds mTimeIntervalSeconds;
  std::vector<std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >> mInstances;
};

```

