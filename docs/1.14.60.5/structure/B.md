# B
### `BlockPos`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (4) `int` | z


### `BaseGameVersion`
Offset | Type | Name
-|-|-|-
0 | (112) `SemVersion` | mSemVersion


### `Bedrock::Threading::Mutex`
Offset | Type | Name
-|-|-|-
0 | (40) `std::__mutex_base` | baseclass_0


### `BedrockEngine::AppIsland`
Offset | Type | Name
-|-|-|-
0 | (8) `BedrockEngine::IIslandCore` | baseclass_0


### `BedrockEngine::IIslandCore`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IIslandCore


### `BaseGamePackSlices`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BaseGamePackSlices::BaseGameVersionPack>` | mBaseGameVersionPacks
24 | (24) `std::vector<BaseGamePackSlices::BaseGameVersionPack>` | mBaseGameVersionTestPacks


### `BoundingBox`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | min
12 | (12) `BlockPos` | max


### `Bedrock::Application::ThreadOwner<Core::Random>`
Offset | Type | Name
-|-|-|-
0 | (2516) `Core::Random` | mObject


### `BlockSource`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockSource
8 | (8) `const std::thread::id` | mOwnerThreadID
16 | (1) `const bool` | mAllowUnpopulatedChunks
17 | (1) `const bool` | mPublicSource
24 | (8) `Level *` | mLevel
32 | (8) `ChunkSource *` | mChunkSource
40 | (8) `Dimension *` | mDimension
48 | (2) `const Height` | mMaxHeight
56 | (24) `std::vector<BlockFetchResult>` | mTempBlockFetchResult
80 | (12) `BlockPos` | mPlaceChunkPos
96 | (24) `BlockSource::ListenerVector` | mListeners
120 | (8) `ChunkPos` | mLastChunkPos
128 | (8) `LevelChunk *` | mLastChunk
136 | (8) `BlockTickingQueue *` | mRandomTickQueue
144 | (8) `BlockTickingQueue *` | mTickQueue
152 | (2) `const BrightnessPair` | mDefaultBrightness
160 | (24) `ActorList` | mTempEntityList
184 | (24) `BlockActorList` | mTempBlockEntityList
208 | (24) `std::vector<AABB>` | mTempCubeList


### `BlockSource::ListenerVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<BlockSourceListener *>` | baseclass_0


### `BrightnessPair`
Offset | Type | Name
-|-|-|-
0 | (1) `Brightness` | sky
1 | (1) `Brightness` | block


### `Brightness`
Offset | Type | Name
-|-|-|-
0 | (1) `NewType<unsigned char>` | baseclass_0


### `BlockActorList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<BlockActor *>` | baseclass_0


### `BlockTickingQueue`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelChunk *` | mOwningChunk
8 | (8) `Tick` | mCurrentTick
16 | (24) `BlockTickingQueue::TickDataSet` | mNextTickQueue
40 | (24) `BlockTickingQueue::TickDataSet` | mActiveTickQueue
64 | (1) `TickingQueueType` | mQueueType
65 | (1) `bool` | mInstaTick


### `BlockTickingQueue::TickDataSet`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >` | baseclass_0


### `Bedrock::Threading::LockGuard<Bedrock::Threading::Mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `buffer_span<ChunkPos>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ChunkPos *` | mBegin
8 | (8) `const ChunkPos *` | mEnd


### `BiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BiomeSource


### `BlockVolume`
Offset | Type | Name
-|-|-|-
0 | (16) `buffer_span_mut<const Block *>` | blocks
16 | (4) `uint32_t` | mWidth
20 | (4) `uint32_t` | mHeight
24 | (4) `uint32_t` | mDepth


### `buffer_span_mut<const Block *>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | mBegin
8 | (8) `const Block **` | mEnd


### `BiomeArea`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mStride
8 | (24) `std::vector<const Biome *>` | mBiomes


### `BonusChestFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `BlockPosIterator`
Offset | Type | Name
-|-|-|-
0 | (12) `const BlockPos` | mMinCorner
12 | (12) `const BlockPos` | mMaxCorner
24 | (12) `BlockPos` | mCurrentPos
36 | (1) `bool` | mDone


### `buffer_span<std::pair<gsl::basic_string_span<const char,-1>,gsl::basic_string_span<const char,-1> > >`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::pair<gsl::basic_string_span<const char,-1>,gsl::basic_string_span<const char,-1> > *` | mBegin
8 | (8) `const std::pair<gsl::basic_string_span<const char,-1>,gsl::basic_string_span<const char,-1> > *` | mEnd


### `buffer_span<std::pair<gsl::basic_string_span<const char,-1>,gsl::basic_string_span<const char,-1> > >::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::pair<gsl::basic_string_span<const char,-1>,gsl::basic_string_span<const char,-1> > *` | mPtr


### `Bedrock::Threading::LockGuard<Core::SingleThreadedLock>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<Core::SingleThreadedLock>::mutex_type *` | _M_device


### `BalloonComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mAttachedID
8 | (4) `float` | mMaxHeight
12 | (1) `bool` | mShouldDropAttached


### `BehaviorComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `BehaviorTreeDefinitionPtr` | mTreeDefinition
16 | (8) `Unique<BehaviorNode>` | mRoot
24 | (80) `BehaviorData` | mBehaviorData


### `BehaviorTreeDefinitionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `BehaviorTreeGroup *` | mGroup
8 | (8) `BehaviorTreeDefinition *` | mPtr


### `BehaviorData`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,std::unique_ptr<BehaviorData::DataProxy>>` | mData
56 | (24) `std::vector<std::unique_ptr<BehaviorData::DataProxy>>` | mDataStack


### `BlockBreakSensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mSensorRadius
4 | (12) `Vec3` | mSensorPos
16 | (16) `BlockEventDispatcherToken` | mListener
32 | (24) `std::vector<BlockListEventMap>` | mBlockSets


### `BlockEventDispatcherToken`
Offset | Type | Name
-|-|-|-
0 | (4) `ListenerHandle` | mHandle
8 | (8) `BlockEventDispatcher *` | mDispatcher


### `BodyControlComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<BodyControl>` | mBodyControl


### `BoostableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsBoosting
4 | (4) `int` | mBoostTime
8 | (4) `int` | mBoostTimeTotal
12 | (4) `float` | mFovMod


### `BossComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (1) `bool` | mHealthBarVisible
36 | (4) `float` | mHealthPercent
40 | (1) `bool` | mShouldDarkenSky
41 | (1) `bool` | mCreateWorldFog
44 | (4) `BossBarColor` | mColor
48 | (4) `BossBarOverlay` | mOverlay
52 | (4) `int` | mPlayersRegistered
56 | (4) `int` | mLastHealth
60 | (4) `int` | mHudRangeSquared
64 | (8) `std::chrono::_V2::steady_clock::time_point` | mLastPlayerUpdate
72 | (56) `std::unordered_map<mce::UUID,int>` | mPlayerParty


### `BreakBlocksComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `BreakDoorAnnotationComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mBreakTicks
4 | (4) `Difficulty` | mMinDifficulty
8 | (8) `ActorUniqueID` | mTargetID
16 | (4) `int` | mBreakingTime
20 | (16) `std::optional<BlockPos>` | mObstructionPos
40 | (8) `size_t` | mLastPathIndex


### `BreathableComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSuffocateTime
4 | (4) `float` | mInhaleTime
8 | (4) `int` | mAirRegenPerTick
12 | (1) `bool` | mBreathesAir
13 | (1) `bool` | mBreathesWater
14 | (1) `bool` | mBreathesLava
15 | (1) `bool` | mBreathesSolids
16 | (1) `bool` | mGeneratesBubbles
18 | (2) `__int16` | mAirSupply
20 | (2) `__int16` | mAirSupplyMax
24 | (48) `std::set<const Block *>` | mBreathableBlocks
72 | (48) `std::set<const Block *>` | mNonBreathableBlocks
120 | (4) `BreathableComponent::BreathableState` | mBreathableState


### `BreedableComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `const BreedableDefinition *` | mStaticData
8 | (4) `int` | mLoveTimer
12 | (4) `int` | mBreedCooldown
16 | (4) `int` | mBreedCooldownTime
20 | (1) `bool` | mInheritTamed
21 | (1) `bool` | mCausesPregnancy
24 | (8) `ActorUniqueID` | mLoveCause


### `BribeableComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `const BribeableDefinition *` | mStaticData
8 | (4) `int` | mBribeTimer
12 | (4) `int` | mBribeCooldown
16 | (4) `int` | mBribeCooldownTime


### `BaseCommandBlock`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mLastOutputId
32 | (24) `std::vector<std::string>` | mLastOutputParams
56 | (32) `std::string` | mCommand
88 | (32) `std::string` | mName
120 | (8) `std::unique_ptr<Command>` | mCompiledCommand
128 | (8) `uint64_t` | mLastExecution
136 | (4) `int` | mVersion
140 | (4) `int` | mSuccessCount
144 | (4) `int` | mTickDelay
148 | (1) `bool` | mExecuteOnFirstTick
149 | (1) `bool` | mTrackOutput


### `Bedrock::Threading::$<23596803,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::UniqueLock<Bedrock::Threading::SharedMutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::shared_timed_mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `Bedrock::Threading::SharedLock<Bedrock::Threading::SharedMutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_lock<std::shared_timed_mutex>::mutex_type *` | _M_pm
8 | (1) `bool` | _M_owns


### `BinaryDataOutput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataOutput` | baseclass_0
8 | (8) `BinaryStream *` | mStream


### `BytesDataOutput`
Offset | Type | Name
-|-|-|-
0 | (8) `IDataOutput` | baseclass_0


### `BinaryDataInput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataInput` | baseclass_0
8 | (8) `ReadOnlyBinaryStream *` | mStream


### `BytesDataInput`
Offset | Type | Name
-|-|-|-
0 | (8) `IDataInput` | baseclass_0


### `Bedrock::Threading::IAsyncResult<void>::Handle`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Bedrock::Threading::IAsyncResult<void>,__gnu_cxx::_S_atomic>` | baseclass_0


### `Bedrock::Threading::UniqueLock<Bedrock::Threading::RecursiveMutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::recursive_mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `Bedrock::Threading::$<25190359,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Blacklist::Entry`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mUuid
16 | (32) `std::string` | mXuid
48 | (32) `std::string` | mBlockedMessage
80 | (4) `Blacklist::Duration` | mDuration


### `BiomeDefinitionListPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (56) `CompoundTag` | mBiomeData


### `Bedrock::Threading::UniqueLock<Bedrock::Threading::Mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `BookEditPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `BookEditAction` | mAction
40 | (4) `int` | mBookSlot
44 | (4) `int` | mPageIndex1
48 | (4) `int` | mPageIndex2
56 | (32) `std::string` | mText1
88 | (32) `std::string` | mText2
120 | (32) `std::string` | mText3


### `buffer_span<unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned int *` | mBegin
8 | (8) `const unsigned int *` | mEnd


### `BaseGamePackSlices::applyPackSlices::$407E69F49D83A976B60EB7804F48E5FB`
Offset | Type | Name
-|-|-|-
0 | (1) `const bool` | shouldApplyAllSlices
8 | (8) `const BaseGameVersion *` | baseGameVersion


### `BaseGameVersion::any_version_constructor`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BehaviorPackContents`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mEntities
4 | (4) `uint32_t` | mLoots
8 | (4) `uint32_t` | mTrades
12 | (4) `uint32_t` | mPlugins


### `Bedrock::Threading::Thread`
Offset | Type | Name
-|-|-|-
0 | (8) `std::thread::id` | _M_id


### `Blacklist::LockGuard`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::recursive_mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::ConditionVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `std::condition_variable::__native_type` | _M_cond


### `BucketableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `BucketableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0


### `BoneAnimationChannel::sortKeyFrames::KeyFrameCompare`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BoneOrientation`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mParentBoneIndex
4 | (4) `SkeletalHierarchyIndex` | mParentSkeletalHierarchyIndex
8 | (40) `HashedString` | mName
48 | (64) `Matrix` | mLocalPreTransformMatrix
112 | (64) `Matrix` | mMatrix
176 | (4) `BoneAnimationRelativeMode` | mRotationRelativeMode
180 | (36) `BoneOrientationTransform` | mTransform
216 | (36) `BoneOrientationTransform` | mDefaultTransform
252 | (12) `Vec3` | mPivot
264 | (1) `bool` | mOverrideStackMatrix
265 | (1) `bool` | mApplyLocalPreTransformMatrix


### `BoneOrientationTransform`
Offset | Type | Name
-|-|-|-
0 | (36) `Vec3[3]` | mData


### `Bedrock::Threading::RecursiveMutex`
Offset | Type | Name
-|-|-|-
0 | (40) `std::__recursive_mutex_base` | baseclass_0


### `Bedrock::Threading::LockGuard<Bedrock::Threading::RecursiveMutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::recursive_mutex>::mutex_type *` | _M_device


### `buffer_span_mut<std::shared_ptr<LevelChunk> >`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<LevelChunk> *` | mBegin
8 | (8) `std::shared_ptr<LevelChunk> *` | mEnd


### `buffer_span<unsigned int>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned int *` | mPtr


### `BlockActorDataPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos
48 | (56) `CompoundTag` | mData


### `buffer_span_mut<unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int *` | mBegin
8 | (8) `unsigned int *` | mEnd


### `BlockPalette::ConstructorToken`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BlockID`
Offset | Type | Name
-|-|-|-
0 | (1) `NewType<unsigned char>` | baseclass_0


### `buffer_span<BlockID>`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockID *` | mBegin
8 | (8) `const BlockID *` | mEnd


### `buffer_span<NibblePair>`
Offset | Type | Name
-|-|-|-
0 | (8) `const NibblePair *` | mBegin
8 | (8) `const NibblePair *` | mEnd


### `BlockFetchResult`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<const Block>` | mBlock
8 | (12) `BlockPos` | mBlockPos
20 | (4) `uint32_t` | mDistanceSquared


### `buffer_span<SubChunk>`
Offset | Type | Name
-|-|-|-
0 | (8) `const SubChunk *` | mBegin
8 | (8) `const SubChunk *` | mEnd


### `buffer_span<Actor *>`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *const *` | mBegin
8 | (8) `Actor *const *` | mEnd


### `buffer_span<Actor *>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *const *` | mPtr


### `BlockTickingQueue::BlockTick`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsRemoved
8 | (40) `TickNextTickData` | mData


### `BlockTickingQueue::getTickDelaysInArea::$8CF75821B5BA7DD28C0CF4A48A9CB9FA`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | boundingBox
8 | (8) `std::unordered_multimap<BlockPos,TickDelayBlock> *` | ticks
16 | (8) `const BlockTickingQueue *` | this


### `BlockPosSet`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<BlockPos>::_Hashtable` | _M_h


### `BiomeComponentLoading::ComponentAccessor<WeightedBiomeAttributes<HillsTransformation> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<HillsTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<WeightedBiomeAttributes<MutateBiomeTransformation> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<MutateBiomeTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<WeightedBiomeAttributes<RiverTransformation> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<RiverTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<WeightedBiomeAttributes<ShoreTransformation> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<ShoreTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<IgnoreAutomaticFeatureRules> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<IgnoreAutomaticFeatureRules> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<DataDrivenBiomeSurface> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<DataDrivenBiomeSurface> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<SwampBiomeSurface> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<SwampBiomeSurface> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<OceanFrozenBiomeSurface> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<OceanFrozenBiomeSurface> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<NetherBiomeSurface> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<NetherBiomeSurface> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<FlagComponent<TheEndBiomeSurface> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FlagComponent<TheEndBiomeSurface> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<HillsTransformationAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<HillsTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<MutateTransformationAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<MutateBiomeTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<PreHillsEdgeAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FilteredTransformationAttributes<PreHillsEdgeTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<PostShoreEdgeAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FilteredTransformationAttributes<PostShoreEdgeTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<RiverTransformationAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<RiverTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<ShoreAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WeightedBiomeAttributes<ShoreTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<LegacyPreHillsEdgeAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeFilterGroup`
Offset | Type | Name
-|-|-|-
0 | (64) `FilterGroup` | baseclass_0


### `BiomeHeight`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | depth
4 | (4) `float` | scale


### `BiomeDecorationAttributes<ListedFeatures>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BiomeDecorationAttributes<ListedFeatures>::Element,std::allocator<BiomeDecorationAttributes<ListedFeatures>::Element> >` | mFeatures


### `BiomeComponentLoading::_buildSchema<BiomeDecorationAttributes<ListedFeatures> >::$2658D4B1BE3081384A926FB0E5D18BAF`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeComponentLoading::BiomeSchemaNode *` | schemaNode
8 | (32) `BiomeComponentLoading::ComponentAccessor<ListedFeaturesDecorationAttributes>` | componentAccessor


### `BiomeComponentLoading::ComponentAccessor<ListedFeaturesDecorationAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<BiomeDecorationAttributes<ListedFeatures> &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<ClimateAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<ClimateAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<SurfaceMaterialAdjustmentAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<SurfaceMaterialAdjustmentAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<SurfaceMaterialAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<SurfaceMaterialAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<WorldGenClimateMappingAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<WorldGenClimateMappingAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<MesaSurfaceAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<MesaSurfaceAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::ComponentAccessor<OverworldHeightAttributes>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<OverworldHeightAttributes &(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>::_Invoker_type` | _M_invoker


### `BiomeComponentLoading::BiomeParseContext`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<Biome>` | first
8 | (8) `std::reference_wrapper<IWorldRegistriesProvider>` | second


### `BiomeMetadata`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mInherits
64 | (16) `Json::Value` | mLocalComponents


### `BiomeRegistryMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackMergeStrategy` | baseclass_0
8 | (32) `Core::HeapPathBuffer` | mBiomePath
40 | (8) `Json::Value *` | mRoot


### `BaseRailBlock::Rail`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mRegion
8 | (12) `BlockPos` | mPos
20 | (1) `bool` | mUsesDataBit
24 | (24) `std::vector<BlockPos>` | mConnections


### `BlockLegacy::createBlockPermutations::$033A5A72970D0569F1B4E5782E3E5F13`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockLegacy *` | this


### `Bedrock::Threading::UniqueLock<Mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::shared_timed_mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `Bedrock::Threading::SharedLock<Mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_lock<std::shared_timed_mutex>::mutex_type *` | _M_pm
8 | (1) `bool` | _M_owns


### `buffer_span_mut<long>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64 *` | mBegin
8 | (8) `__int64 *` | mEnd


### `buffer_span_mut<const Block *>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | mPtr


### `BeaconBeamSection`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mHeight
4 | (16) `Color` | mColor


### `BlockDescriptionFactoryFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<BlockComponentDescription> ()>::_Invoker_type` | _M_invoker


### `BlockDescription`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mIdentifier
32 | (1) `bool` | mRegisterToCreativeMenu
33 | (1) `bool` | mIsExperimental


### `BlockDefinition`
Offset | Type | Name
-|-|-|-
0 | (112) `SemVersion` | mFormatVersion
112 | (40) `BlockDescription` | mDescription
152 | (24) `std::vector<std::shared_ptr<BlockComponentDescription>>` | mDescriptions


### `Bedrock::Threading::LockGuard<SpinLock>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<SpinLock>::mutex_type *` | _M_device


### `buffer_span<Pos>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Pos *` | mBegin
8 | (8) `const Pos *` | mEnd


### `buffer_span<const Block *>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *const *` | mBegin
8 | (8) `const Block *const *` | mEnd


### `buffer_span_mut<SubChunk>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `SubChunk *` | mPtr


### `BiomeChunkData`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | biome


### `buffer_span_mut<SubChunk>`
Offset | Type | Name
-|-|-|-
0 | (8) `SubChunk *` | mBegin
8 | (8) `SubChunk *` | mEnd


### `BiomeChunkDataLegacy`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | biome
1 | (1) `unsigned __int8` | r
2 | (1) `unsigned __int8` | g
3 | (1) `unsigned __int8` | b


### `BlockEventPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos
48 | (4) `int` | mB0
52 | (4) `int` | mB1


### `BuildMatch`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mMatched
1 | (1) `FacingID` | mForward
2 | (1) `FacingID` | mUp
4 | (4) `int` | mNumPatterns
8 | (4) `int` | mPatternSize
12 | (4) `int` | mSubPatternIndex
16 | (4) `int` | mRowIndex
20 | (12) `BlockPos` | mPattern
32 | (12) `Vec3` | mObjectPos


### `BiomeDecorationAttributes<ImplicitFeatures>::Element`
Offset | Type | Name
-|-|-|-
0 | (1064) `ScatterParams` | mScatter
1064 | (24) `WeakRef<IFeature>` | mFeature
1088 | (48) `StringKey` | mIdentifier


### `BiomeDecorationAttributes<ImplicitFeatures>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BiomeDecorationAttributes<ImplicitFeatures>::Element,std::allocator<BiomeDecorationAttributes<ImplicitFeatures>::Element> >` | mFeatures


### `BonusChestFeature::place::$FD274EF55AC88BD6B944C809A18A5641`
Offset | Type | Name
-|-|-|-
0 | (8) `const BonusChestFeature *` | this
8 | (8) `BlockSource *` | region
16 | (8) `Random *` | newRandom


### `BlockLayer`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mBlock
8 | (4) `int` | mNumLayers


### `BlockSerializationUtils::NbtToBlockCache`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<unsigned long,const Block *>` | mCache
48 | (40) `Bedrock::Threading::Mutex` | mMutex


### `buffer_span<ChunkPos>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const ChunkPos *` | mPtr


### `BigEndianStringByteInput`
Offset | Type | Name
-|-|-|-
0 | (32) `StringByteInput` | baseclass_0


### `BinaryStream`
Offset | Type | Name
-|-|-|-
0 | (56) `ReadOnlyBinaryStream` | baseclass_0
56 | (32) `std::string` | mOwnedBuffer
88 | (8) `std::string *` | mBuffer


### `BlockGraphics::ModelItem`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (8) `const BlockGeometry::TessellatedModel *` | model
40 | (24) `std::vector<unsigned long>` | textureIndices


### `BlockGraphics::ConstructorToken`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BlockListEventMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<const BlockLegacy *>` | mBlockList
56 | (32) `std::string` | mEventName


### `BoostItem`
Offset | Type | Name
-|-|-|-
0 | (8) `const Item *` | mItem
8 | (8) `const Item *` | mReplacement
16 | (4) `int` | mDamageAmount


### `BossEventPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `const int` | FLAG_DARKEN
40 | (4) `const int` | FLAG_FOG
48 | (8) `ActorUniqueID` | mBossID
56 | (8) `ActorUniqueID` | mPlayerID
64 | (4) `BossEventUpdateType` | mEventType
72 | (32) `std::string` | mName
104 | (4) `float` | mHealthPercent
108 | (4) `BossBarColor` | mColor
112 | (4) `BossBarOverlay` | mOverlay
116 | (1) `Util::Byte` | mDarkenScreen
117 | (1) `Util::Byte` | mCreateWorldFog


### `BreedableType`
Offset | Type | Name
-|-|-|-
0 | (168) `ActorDefinitionIdentifier` | mMateType
168 | (168) `ActorDefinitionIdentifier` | mBabyType
336 | (128) `DefinitionTrigger` | mOnBred


### `BatchedNetworkPeer::DataCallback`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | data
32 | (4) `Compressibility` | compressible
40 | (32) `std::function<void ()>` | callback


### `ByteVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<unsigned char>` | baseclass_0


### `BalloonableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `BinaryHeap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PathfinderNode *>` | heap
24 | (4) `int` | sizeVar


### `BehaviorFactory::DefinitionCreator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<BehaviorDefinition> ()>::_Invoker_type` | _M_invoker


### `BehaviorFactory::NodeCreator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<BehaviorNode> ()>::_Invoker_type` | _M_invoker


### `BlockPatternBuilder::BlockEntryTester`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (BlockSource &,const BlockPos &,const Block &)>::_Invoker_type` | _M_invoker


### `Bedrock::Threading::$<268754422,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::$<269227119,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::LockGuard<decltype(mIdMutex)>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::LockGuard<std::mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::$<281360972,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `BedrockLog::LogDetails::_appendLogEntryMetadata::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BedrockLog::LogAreaFilter`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<34>` | baseclass_0


### `Bedrock::Threading::$<282285601,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::recursive_mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::LockGuard<decltype(sStorageAreaLock)>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::$<282285612,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::recursive_mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `Bedrock::Threading::LockGuard<decltype(FileImpl::sAllFilesLock)>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::$<282952368,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::$<283102713,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `Bedrock::Threading::`anonymous namespace'::AsyncErrorCategory`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `Bedrock::Threading::IAsyncResult<void>::CompletionHandler`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Bedrock::Threading::IAsyncResult<void> &)>::_Invoker_type` | _M_invoker


### `Bedrock::Threading::UniqueLockReleaseWindow<std::mutex>`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Threading::UniqueLock<std::mutex> *` | mLock


### `BackgroundTask::PendingComparer`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `buffer_span<bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `const bool *` | mBegin
8 | (8) `const bool *` | mEnd


### `buffer_span<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `const int *` | mBegin
8 | (8) `const int *` | mEnd


### `buffer_span<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | mBegin
8 | (8) `const std::string *` | mEnd


### `BackgroundTask::PriorityComparer`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Bedrock::Threading::SharedMutex`
Offset | Type | Name
-|-|-|-
0 | (56) `std::__shared_timed_mutex_base` | baseclass_0


### `BidirectionalUnorderedMap<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> >,ActorDamageCause>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,ActorDamageCause>` | mRight
56 | (56) `std::unordered_map<ActorDamageCause,std::string>` | mLeft


### `BidirectionalUnorderedMap<ItemUseMethod,std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ItemUseMethod,std::string>` | mRight
56 | (56) `std::unordered_map<std::string,ItemUseMethod>` | mLeft


### `BidirectionalUnorderedMap<ItemAcquisitionMethod,std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ItemAcquisitionMethod,std::string>` | mRight
56 | (56) `std::unordered_map<std::string,ItemAcquisitionMethod>` | mLeft


### `BidirectionalUnorderedMap<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> >,LevelSoundEvent>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,LevelSoundEvent>` | mRight
56 | (56) `std::unordered_map<LevelSoundEvent,std::string>` | mLeft


### `BlockActor::MapIdType`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,BlockActorType>::_Rep_type` | _M_t


### `BlockActor::MapTypeId`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<BlockActorType,std::string>::_Rep_type` | _M_t


### `BlockTypeRegistry::BlockLookupMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,SharedPtr<BlockLegacy>>::_Hashtable` | _M_h


### `BidirectionalUnorderedMap<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> >,AutomaticID<Dimension,int> >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,AutomaticID<Dimension,int>>` | mRight
56 | (56) `std::unordered_map<AutomaticID<Dimension,int>,std::string>` | mLeft


### `BidirectionalUnorderedMap<ContainerType,std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ContainerType,std::string>` | mRight
56 | (56) `std::unordered_map<std::string,ContainerType>` | mLeft


### `BidirectionalUnorderedMap<ParticleType,std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ParticleType,std::string>` | mRight
56 | (56) `std::unordered_map<std::string,ParticleType>` | mLeft


### `BedrockLog::CategoryLogs`
Offset | Type | Name
-|-|-|-
0 | (504) `std::array<BedrockLog::CategoryLogFile,7>` | baseclass_0


### `BackwardsCompatTextureGroup`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ResourceLocation,BackwardsCompatTextureInfo>` | mBackCompatMap


### `BlockSelector`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockSelector


### `BlockSourceListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockSourceListener


### `Biome`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Biome
8 | (32) `std::string` | mName
40 | (4) `int` | mDebugMapColor
44 | (4) `int` | mDebugMapOddColor
48 | (4) `float` | mTemperature
52 | (4) `float` | mDownfall
56 | (4) `float` | mSnowAccumulation
60 | (4) `float` | mFoliageSnow
64 | (4) `float` | mMinSnowLevel
68 | (4) `float` | mMaxSnowLevel
72 | (4) `float` | mDepth
76 | (4) `float` | mScale
80 | (16) `Color` | mWaterColor
96 | (4) `float` | mWaterTranparency
100 | (16) `Color` | mUnderWaterColor
116 | (1) `bool` | mRain
120 | (4) `int` | mId
124 | (4) `float` | mFogDist
128 | (12) `OceanRuinConfiguration` | mOceanRuinConfig
144 | (24) `MobList` | mMobs
168 | (8) `Unique<PerlinSimplexNoise>` | mTemperatureNoise
176 | (8) `std::unique_ptr<PerlinSimplexNoise>` | mFrozenTemperatureNoise
184 | (24) `OwnerPtr<EntityId>` | mEntity
208 | (16) `OwnerPtr<PerlinSimplexNoise>` | mBiomeInfoNoise


### `BlockMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<int,const Block *>::_Hashtable` | _M_h


### `BackgroundWorkerPerfInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const BackgroundWorker *` | mUpdaterWorker
8 | (8) `std::atomic<unsigned long>` | mTotalRunTasks
16 | (8) `std::atomic<unsigned long>` | mTotalRunTasksTicks
24 | (4) `std::atomic<unsigned int>` | mTotalWakeUps
32 | (8) `std::atomic<double>` | mAverageTaskDuration
40 | (4) `std::atomic<unsigned int>` | mWakeUpsPerSecond
48 | (8) `std::chrono::_V2::system_clock::time_point` | mLastPerfInfoUpdate
56 | (8) `std::chrono::_V2::system_clock::time_point` | mNextPerfInfoUpdate


### `BackgroundTaskQueue`
Offset | Type | Name
-|-|-|-
0 | (40) `Bedrock::Threading::Mutex` | mIngressLock
40 | (40) `Bedrock::Threading::Mutex` | mEgressLock
80 | (80) `BackgroundTaskQueue::TaskPipe` | mTasks
160 | (8) `std::atomic_size_t` | mQueuedTasksCount
168 | (1) `std::atomic<bool>` | mResortQueue
176 | (40) `Bedrock::Threading::Mutex` | mQueueLock
216 | (24) `BackgroundTaskQueue::SortingJobQueue` | mLocalPriorityQueue
240 | (4) `std::atomic<int>` | mNextItemPriority


### `BackgroundTaskQueue::TaskPipe`
Offset | Type | Name
-|-|-|-
0 | (8) `Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *>` | mFrontBlock
8 | (56) `char[56]` | mCachelineFiller
64 | (8) `Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *>` | mTailBlock
72 | (8) `size_t` | mLargestBlockSize


### `BackgroundTaskQueue::SortingJobQueue`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>::Base` | mC


### `BlockLegacy`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockLegacy
8 | (32) `std::string` | mDescriptionId
40 | (32) `std::string` | mRawNameId
72 | (32) `std::string` | mNamespace
104 | (32) `std::string` | mFullName
136 | (1) `bool` | mFancy
140 | (4) `BlockRenderLayer` | mRenderLayer
144 | (1) `bool` | mRenderLayerCanRenderAsOpaque
152 | (8) `BlockProperty` | mProperties
160 | (4) `BlockActorType` | mBlockEntityType
164 | (1) `bool` | mAnimatedTexture
168 | (4) `float` | mBrightnessGamma
172 | (4) `float` | mThickness
176 | (1) `bool` | mCanSlide
177 | (1) `bool` | mCanInstatick
178 | (1) `bool` | mIsInteraction
180 | (4) `float` | mGravity
184 | (8) `const Material *` | mMaterial
192 | (16) `Color` | mMapColor
208 | (4) `float` | mFriction
212 | (1) `bool` | mHeavy
216 | (4) `float` | mParticleQuantityScalar
220 | (4) `float` | mDestroySpeed
224 | (4) `float` | mExplosionResistance
228 | (4) `CreativeItemCategory` | mCreativeCategory
232 | (1) `bool` | mAllowsRunes
233 | (1) `bool` | mCanBeBrokenFromFalling
234 | (1) `bool` | mSolid
235 | (1) `bool` | mPushesOutItems
236 | (1) `bool` | mIgnoreBlockForInsideCubeRenderer
237 | (1) `bool` | mIsTrapdoor
238 | (1) `bool` | mIsDoor
240 | (4) `float` | mTranslucency
244 | (1) `Brightness` | mLightBlock
245 | (1) `Brightness` | mLightEmission
246 | (1) `bool` | mShouldRandomTick
247 | (1) `bool` | mShouldRandomTickExtraLayer
248 | (4) `int` | mFlameOdds
252 | (4) `int` | mBurnOdds
256 | (1) `bool` | mIsMobPiece
257 | (1) `bool` | mCanBeExtraBlock
258 | (1) `bool` | mCanPropagateBrightness
260 | (2) `NewBlockID` | mID
264 | (112) `BaseGameVersion` | mMinRequiredBaseGameVersion
376 | (1) `bool` | mExperimental
377 | (1) `bool` | mIsVanilla
384 | (8) `Unique<LootComponent>` | mLootComponent
392 | (28) `AABB` | mVisualShape
420 | (4) `unsigned int` | mBitsUsed
424 | (4) `unsigned int` | mTotalBitsUsed
432 | (3360) `std::array<ItemStateInstance,105>` | mStates
3792 | (24) `std::vector<std::unique_ptr<Block>>` | mBlockPermutations
3816 | (8) `const Block *` | mDefaultState
3824 | (56) `Bedrock::Threading::SharedMutex` | mLegacyDataLookupTableMutex
3880 | (24) `std::vector<long>` | mLegacyDataLookupTable


### `BaseAttributeMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned int,AttributeInstance>` | mInstanceMap
56 | (24) `std::vector<AttributeInstanceHandle>` | mDirtyAttributes


### `BaseMoveToGoal`
Offset | Type | Name
-|-|-|-
0 | (12) `Goal:96` | baseclass_0
12 | (4) `int` | mTravelTicks
16 | (4) `int` | mNextStartTick
20 | (4) `int` | mGiveUpTicks
24 | (4) `int` | mStayTicks
28 | (4) `int` | mMaxStayTicks
32 | (1) `bool` | mReachedTarget
36 | (4) `float` | mSpeedMod
40 | (4) `float` | mGoalRadiusSq
48 | (8) `uint64_t` | mCooldownCounter
56 | (8) `const uint64_t` | mCooldownTimeoutTime
64 | (12) `BlockPos` | mStartPos
76 | (12) `Vec3` | mBlockPos
88 | (12) `Vec3` | mTargetPositionOffset
100 | (4) `float` | mChanceToStart
104 | (8) `Mob *` | mMob
112 | (4) `int` | mInterval


### `Boat::onAboveBubbleColumn::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BlockSource::fetchBlocksInCylinder::$BFF6684F24A24DAB087E11B4105C16CA`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | this
8 | (8) `const BlockPos *` | centerPos
16 | (4) `uint32_t` | radius
20 | (4) `uint32_t` | height
24 | (8) `std::function<bool (const Block &)> *` | predicate


### `BlockSource::fetchBlocksInBox::$74F335EC098D670C69AD7D2E598E74BF`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | this
8 | (8) `const BoundingBox *` | box
16 | (8) `std::function<bool (const Block &)> *` | predicate


### `BiomeRegistry::BiomeParent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | parentName
32 | (16) `Json::Value` | json


### `BiomeDecorationSystem::decorate::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BlockLegacy::initFromDefinition::$033A5A72970D0569F1B4E5782E3E5F13`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockLegacy *` | this


### `BlockActor`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockActor
8 | (4) `int` | mTickCount
16 | (8) `const Block *` | mBlock
24 | (4) `float` | mDestroyTimer
28 | (12) `Vec3` | mDestroyDirection
40 | (4) `float` | mDestroyProgress
44 | (12) `BlockPos` | mPosition
56 | (28) `AABB` | mBB
84 | (4) `const BlockActorType` | mType
88 | (4) `BlockActorRendererId` | mRendererId
96 | (32) `std::string` | mCustomName
128 | (32) `std::string` | mFilteredCustomName
160 | (4) `int` | mRepairCost
164 | (1) `bool` | mClientSideOnly
165 | (1) `bool` | mIsMovable
166 | (1) `bool` | mSaveCustomName
167 | (1) `bool` | mCanRenderCustomName
168 | (4) `const float` | signShadowRadius
176 | (24) `ActorTerrainInterlockData` | mTerrainInterlockData
200 | (1) `bool` | mChanged


### `BurstReactionComponent::_onEnd::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `BiomeChunkState`
Offset | Type | Name
-|-|-|-
0 | (1) `byte` | snowLevel


### `BlockActor:1632`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BlockActor
8 | (4) `int` | mTickCount
12 | (4) `_BYTE[4]` | gapC
16 | (8) `const Block *` | mBlock
24 | (4) `float` | mDestroyTimer
28 | (12) `Vec3` | mDestroyDirection
40 | (4) `float` | mDestroyProgress
44 | (12) `BlockPos` | mPosition
56 | (28) `AABB` | mBB
84 | (4) `const BlockActorType` | mType
88 | (4) `BlockActorRendererId` | mRendererId
92 | (4) `_BYTE[4]` | gap5C
96 | (32) `std::string` | mCustomName
128 | (32) `std::string` | mFilteredCustomName
160 | (4) `int` | mRepairCost
164 | (1) `bool` | mClientSideOnly
165 | (1) `bool` | mIsMovable
166 | (1) `bool` | mSaveCustomName
167 | (1) `bool` | mCanRenderCustomName
168 | (4) `const float` | signShadowRadius
172 | (4) `_BYTE[4]` | gapAC
176 | (24) `ActorTerrainInterlockData` | mTerrainInterlockData
200 | (1) `bool` | mChanged


### `BehaviorTreeGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackManager *` | mResourcePackManager
8 | (8) `BehaviorFactory *` | mFactory
16 | (56) `BehaviorTreeGroup::BehaviorDefinitionMap` | mDefinitions
72 | (56) `std::unordered_set<BehaviorTreeDefinitionPtr *>` | mRegisteredPtrs


### `BehaviorTreeGroup::BehaviorDefinitionMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,std::unique_ptr<BehaviorTreeDefinition>>::_Hashtable` | _M_h


### `BlockEventDispatcher`
Offset | Type | Name
-|-|-|-
0 | (56) `ListenerSet` | mRegisteredListeners
56 | (4) `ListenerHandle` | mHandleCounter


### `BlockChange`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mUpdateFlags
8 | (8) `const Block *` | mOldBlock
16 | (8) `const Block *` | mNewBlock


### `BehaviorDefinition`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$BehaviorDefinition
8 | (32) `std::string` | mName
40 | (16) `BehaviorTreeDefinitionPtr` | mTreeDefinition


### `BehaviorFactory`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,std::pair<std::function<std::unique_ptr<BehaviorDefinition> ()>,std::function<std::unique_ptr<BehaviorNode> ()> >>` | mFactoryPairs


### `BubbleColumnBlock::entityInside::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Bedrock::Threading::ConditionVariableAny`
Offset | Type | Name
-|-|-|-
0 | (48) `std::condition_variable` | _M_cond
48 | (16) `std::shared_ptr<std::mutex>` | _M_mutex


### `Bedrock::Threading::AsyncBase`
Offset | Type | Name
-|-|-|-
0 | (16) `std::enable_shared_from_this<Bedrock::Threading::AsyncBase>` | baseclass_0


### `BackgroundTask`
Offset | Type | Name
-|-|-|-
0 | (24) `Bedrock::Threading::IAsyncResult<void>` | baseclass_0
24 | (8) `ITaskGroup *` | mGroup
32 | (8) `BackgroundTask *` | mPrevTask
40 | (16) `std::shared_ptr<BackgroundTask>` | mNextTask
56 | (32) `std::function<TaskResult ()>` | mTask
88 | (8) `std::chrono::_V2::steady_clock::time_point` | mStartAfterTime
96 | (4) `int` | mPriority
104 | (8) `std::thread::id` | mAffinity
112 | (4) `int` | mBackDownPriorityAmount
120 | (40) `Bedrock::Threading::Mutex` | mLock
160 | (4) `BackgroundTask::TaskStatus` | mStatus
164 | (1) `bool` | mIsAsync
168 | (24) `std::vector<std::function<void (const Bedrock::Threading::IAsyncResult<void> &)>>` | mComplete
192 | (16) `Bedrock::Threading::IAsyncResult<void>::Handle` | mPredecessor


### `Bedrock::Threading::IAsyncResult<void>`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IAsyncResult
8 | (16) `Bedrock::Threading::AsyncBase` | baseclass_8


### `buffer_span<WorkerPool *>`
Offset | Type | Name
-|-|-|-
0 | (8) `WorkerPool *const *` | mBegin
8 | (8) `WorkerPool *const *` | mEnd


### `BackgroundWorker`
```
struct __cppobj BackgroundWorker : ITaskExecutionContext
{
  const bool mAsync;
  Bedrock::Threading::OSThreadPriority mPriority;
  std::optional<unsigned long> mCoreAffinity;
  std::string mName;
  Bedrock::Threading::Thread mThread;
  std::thread::id mWorkerThreadID;
  std::atomic<BackgroundWorker::State> mState;
  ResetEventObj mResetEvent;
  std::atomic<bool> mIdle;
  std::chrono::_V2::system_clock::time_point mIdleSinceTime;
  std::shared_ptr<BackgroundTask> mCurrentTask;
  WorkerPool *mWorkerPool;
  std::chrono::_V2::system_clock::duration mMaxSpinlockDuration;
  std::shared_ptr<ThreadLocal<BackgroundWorker *> > mLocalWorkerMapping;
  BackgroundTaskQueue mTaskQueue;
};

```

### `BedrockEngine::PlatformRuntimeInfo`
```
struct BedrockEngine::PlatformRuntimeInfo
{
  int (**_vptr$PlatformRuntimeInfo)(void);
  std::string mDeviceModelName;
  std::string mOSVersion;
  std::string mCPUType;
  std::string mCPUName;
  std::string mCPUFeatures;
  std::string mSecureId;
  std::string mSerial;
  std::string mBoard;
  std::string mInstallerPackageName;
  std::string mRegion;
  PlatformType mPlatformType;
  uint64_t mCachedFreeStorageSpace_Internal;
  uint64_t mCachedFreeStorageSpace_External;
  uint64_t mCachedFreeStorageSpace_Cloud;
  uint64_t mTotalPhysicalMemory;
  uint64_t mTotalVirtualMemory;
  uint64_t mUsedMemory;
  size_t mPhysicalMemorySize;
  uint32_t mOptimalLDBSize;
  float mWidth;
  float mHeight;
  float mDPI;
  DisplayOrientation mOrientation;
  int mSignaturesHash;
  bool mGraphicsTearingSupport;
  bool mAllowSplitScreen;
  bool mSupportsMSAA;
  bool mHasFastAlphaTest;
  bool mSupportsVibration;
  bool mSupportsTextToSpeech;
  bool mSupportsClipboard;
  bool mSupportsFilePicking;
  bool mAllowContentLogWrite;
  bool mIsRooted;
  bool mCanSelfTerminate;
  bool mCanLaunchUri;
  uint8_t mCoreCount;
  uint8_t mThreadCount;
  uint8_t mHighPerfThreadCount;
  uint8_t mProcessorGrade;
  uint8_t mGraphicsGrade;
  uint8_t mMemoryGrade;
  uint8_t mStorageGrade;
  uint8_t mPowerSupplyGrade;
  Core::HeapPathBuffer mAssetStoragePath;
  Core::HeapPathBuffer mCurrentStoragePath;
  Core::HeapPathBuffer mExternalStoragePath;
  Core::HeapPathBuffer mInternalStoragePath;
  Core::HeapPathBuffer mLoggingPath;
  Core::HeapPathBuffer mPackagePath;
  Core::HeapPathBuffer mUserDataPath;
  Core::HeapPathBuffer mCacheStoragePath;
};

```

### `BedrockEngine::PlatformBuildInfo`
```
struct __attribute__((aligned(8))) BedrockEngine::PlatformBuildInfo
{
  std::string mInstallerPackageName;
  Core::HeapPathBuffer mPlatformTempPath;
  Core::HeapPathBuffer mOnDiskScratchPath;
  Core::HeapPathBuffer mDataUrl;
  Core::HeapPathBuffer mAltDataUrl;
  std::string mFeedbackURL;
  bool mHasBuyButtonWhenLicenseInvalid;
};

```

### `BatchedNetworkPeer`
```
struct __cppobj __attribute__((aligned(8))) BatchedNetworkPeer : NetworkPeer
{
  BinaryStream mOutgoingData;
  size_t mCompressibleBytes;
  std::string mIncomingDataBuffer;
  std::unique_ptr<ReadOnlyBinaryStream> mIncomingData;
  std::unique_ptr<TaskGroup> mTaskGroup;
  SPSCQueue<BatchedNetworkPeer::DataCallback,512> mSendQueue;
  std::atomic_bool mTaskRunning;
  std::atomic<unsigned long> mQueuedPackets;
  uint64_t mSentPackets;
  uint16_t mCompressionThreshold;
  bool mAsyncEnabled;
};

```

### `BaseGamePackSlices::BaseGameVersionPack`
```
struct BaseGamePackSlices::BaseGameVersionPack
{
  BaseGameVersion mBaseGameVersion;
  ResourcePack *mPack;
};

```

### `BlockEventListener`
```
struct BlockEventListener
{
  int (**_vptr$BlockEventListener)(void);
};

```

### `BurnsInDaylightSystem`
```
struct __cppobj BurnsInDaylightSystem : ITickingSystem
{
};

```

### `BodyControlSystem`
```
struct __cppobj BodyControlSystem : ITickingSystem
{
};

```

### `BossSystem`
```
struct __cppobj BossSystem : ITickingSystem
{
};

```

### `BreedableSystem`
```
struct __cppobj BreedableSystem : ITickingSystem
{
};

```

### `BribeableSystem`
```
struct __cppobj BribeableSystem : ITickingSystem
{
};

```

### `BreathableSystem`
```
struct __cppobj BreathableSystem : ITickingSystem
{
};

```

### `BoostableSystem`
```
struct __cppobj BoostableSystem : ITickingSystem
{
};

```

### `BalloonSystem`
```
struct __cppobj BalloonSystem : ITickingSystem
{
};

```

### `BehaviorSystem`
```
struct __cppobj BehaviorSystem : ITickingSystem
{
};

```

### `BreakBlocksSystem`
```
struct __cppobj BreakBlocksSystem : ITickingSystem
{
};

```

### `BreakDoorAnnotationSystem`
```
struct __cppobj BreakDoorAnnotationSystem : ITickingSystem
{
};

```

### `BlockBreakSensorSystem`
```
struct __cppobj BlockBreakSensorSystem : ITickingSystem
{
};

```

### `Block`
```
struct __attribute__((aligned(4))) Block
{
  int (**_vptr$Block)(void);
  const DataID mData;
  WeakPtr<BlockLegacy> mLegacyBlock;
  BlockSerializationId mSerializationId;
  BlockRuntimeId mRuntimeId;
  bool mHasRuntimeId;
};

```

### `BlockDefinitionGroup`
```
struct __attribute__((aligned(8))) BlockDefinitionGroup
{
  std::unordered_map<std::string,std::unique_ptr<BlockDefinition>> mBlockDefinitions;
  int mLastBlockId;
};

```

### `BlockComponentFactory`
```
struct BlockComponentFactory
{
  BlockFactoryMap mFactoryMap;
};

```

### `BirchFeature`
```
struct __cppobj __attribute__((aligned(8))) BirchFeature : TreeFeature:272
{
  bool mSuperBirch;
};

```

### `BlueIceFeature`
```
struct __cppobj BlueIceFeature : Feature
{
};

```

### `BlockBlobFeature`
```
struct __cppobj __attribute__((aligned(8))) BlockBlobFeature : Feature
{
  const Block *mBlock;
  int mStartRadius;
};

```

### `BambooFeature`
```
struct __cppobj BambooFeature : Feature
{
};

```

### `BlockPileFeature`
```
struct __cppobj BlockPileFeature : Feature
{
  const Block *mBlock;
};

```

### `BaseCircuitComponent`
```
struct __attribute__((aligned(8))) BaseCircuitComponent
{
  int (**_vptr$BaseCircuitComponent)(void);
  CircuitComponentList mSources;
  bool mIgnoreFirstUpdate;
  bool mIsFirstTime;
  bool mNeedsUpdate;
  BlockPos mChunkPosition;
  bool mShouldEvaluate;
  int mStrength;
  FacingID mDirection;
  bool mAllowPowerUp;
  bool mAllowPowerDown;
  bool mRemoved;
};

```

### `BlockPalette`
```
struct BlockPalette
{
  Bedrock::Threading::Mutex mLegacyBlockStatesConversionWarningMutex;
  std::set<std::pair<int,int>> mLegacyBlockStatesConversionWarningSet;
  std::map<std::string,const BlockLegacy *> mNameLookup;
  std::map<CompoundTag,const Block *> mBlockFromSerId;
  std::vector<const Block *> mBlockFromRuntimeId;
  Level *mLevel;
};

```

### `BlockVolume::BlockVolumeIter`
```
struct BlockVolume::BlockVolumeIter
{
  Pos pos;
  BlockPos dims;
  buffer_span_mut<const Block *>::iterator blockIter;
};

```

### `BushBlock`
```
struct __cppobj BushBlock : BlockLegacy
{
};

```

### `Bounds`
```
struct Bounds
{
  Pos mMin;
  Pos mMax;
  Pos mDim;
  int mArea;
  int mVolume;
  int mSide;
};

```

### `Bounds::Iterator`
```
struct __cppobj __attribute__((aligned(8))) Bounds::Iterator : Pos
{
  const Bounds *mBounds;
  int mIdx;
};

```

### `BiomeSourceGetBiomeCache`
```
struct BiomeSourceGetBiomeCache
{
  std::unordered_map<BlockPos,const Biome *> mMap;
  SpinLock mLock;
};

```

### `BiomeRegistry`
```
struct __cppobj BiomeRegistry : IEntityRegistryOwner
{
  WellKnownBiomeTags mWellKnownBiomeTags;
  BiomeRegistry::BiomeLookupVector mBiomes;
  OwnerPtr<EntityRegistry> mEntities;
  uint32_t mNextId;
  std::atomic<bool> mClosedForRegistration;
  bool mLoadFromPacks;
  TagRegistry mTagRegistry;
};

```

### `BeardKernel`
```
struct BeardKernel
{
  const std::array<float,13824> mKernel;
};

```

### `BuriedTreasureFeature`
```
struct __cppobj BuriedTreasureFeature : StructureFeature:1760
{
  int mSpacing;
  int mMinSeparation;
  std::vector<int> mAllowedBiomes;
};

```

### `BuriedTreasureStart`
```
struct __cppobj BuriedTreasureStart : StructureStart
{
};

```

### `BuriedTreasurePiece`
```
struct __cppobj __attribute__((aligned(8))) BuriedTreasurePiece : StructurePiece
{
  int mRadius;
};

```

### `buffer_span<std::string >`
```
struct buffer_span<std::string >
{
  const std::string *mBegin;
  const std::string *mEnd;
};

```

### `BehaviorNode`
```
struct __attribute__((aligned(8))) BehaviorNode
{
  int (**_vptr$BehaviorNode)(void);
  const BehaviorDefinition *mNodeDefinition;
  BehaviorTreeDefinitionPtr mTreeDefinition;
  BehaviorNode *mParent;
  BehaviorComponent *mComponent;
  BehaviorData *mTreeData;
  BehaviorStatus mStatus;
};

```

### `BehaviorData::DataProxy`
```
struct __attribute__((aligned(8))) BehaviorData::DataProxy
{
  int (**_vptr$DataProxy)(void);
  std::string mId;
  BehaviorData::DataType mType;
};

```

### `BehaviorTreeDefinition`
```
struct BehaviorTreeDefinition
{
  std::string mTreeName;
  std::string mStringInput;
  Unique<BehaviorDefinition> mRoot;
};

```

### `BodyControl`
```
struct __cppobj BodyControl : Control
{
  int mTimeStill;
  float mLastHeadY;
};

```

### `BreedableDefinition`
```
struct __attribute__((aligned(8))) BreedableDefinition
{
  bool mTame;
  bool mBlendAttributes;
  float mExtraChance;
  float mBreedCooldownTimeSeconds;
  bool mInheritTamed;
  bool mAllowSitting;
  std::vector<ItemDescriptor> mBreedItems;
  std::vector<EnvironmentRequirement> mEnvironmentRequirements;
  ActorFilterGroup mLoveFilter;
  std::vector<BreedableType> mBreedTypes;
  MutationFactorData mMutationFactors;
  DenySameParentsVariantData mDenyParentsVariant;
  bool mCausesPregnancy;
};

```

### `BribeableDefinition`
```
struct BribeableDefinition
{
  float mBribeCooldown;
  std::set<const Item *> mBribeItems;
};

```

### `BurnsInDaylightComponent`
```
typedef ActorFlagComponent<BurnsInDaylightFlag> BurnsInDaylightComponent;

```

### `ByteTag`
```
struct __cppobj __attribute__((aligned(8))) ByteTag : Tag
{
  uint8_t data;
};

```

### `ByteArrayTag`
```
struct __cppobj ByteArrayTag : Tag
{
  TagMemoryChunk data;
};

```

### `BlockPickRequestPacket`
```
struct __cppobj __attribute__((aligned(8))) BlockPickRequestPacket : Packet:288
{
  BlockPos mPos;
  bool mWithData;
  byte mMaxSlots;
};

```

### `Blacklist`
```
struct Blacklist
{
  std::vector<Blacklist::Entry> mEntries;
  Bedrock::Threading::RecursiveMutex mEntriesMutex;
};

```

### `Boat`
```
struct __cppobj Boat : Actor
{
  bool mFlipped;
  std::string mName;
  MovementInterpolator mInterpolation;
  Boat::Paddle mPaddles[2];
  int mOutOfControlTicks;
  float mYRotD;
  float mInvFriction;
  double mTimer;
  bool mAboveBubbleColumn;
  bool mBubbleColumnDown;
  bool insideBubbleColumn;
  float mBubbleMultiplier;
  float mBubbleAngle;
  float mBubbleAngleOld;
};

```

### `BlockSerializationId`
```
typedef CompoundTag BlockSerializationId;

```

### `BookCloningRecipe`
```
struct __cppobj BookCloningRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `BannerDuplicateRecipe`
```
struct __cppobj BannerDuplicateRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `BannerAddPatternRecipe`
```
struct __cppobj BannerAddPatternRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `BlockComponentDescription`
```
struct BlockComponentDescription
{
  int (**_vptr$BlockComponentDescription)(void);
};

```

### `BoolOption`
```
struct __cppobj BoolOption : Option
{
  bool mValue;
  bool mDefaultValue;
  Option::BoolFilter mCoerceValueCallback;
};

```

### `BlockFactoryMap`
```
typedef std::unordered_map<std::string,std::function<std::unique_ptr<BlockComponentDescription> ()>> BlockFactoryMap;

```

### `BlockEventCoordinator`
```
struct __cppobj BlockEventCoordinator : EventCoordinator<BlockEventListener>
{
};

```

### `BiomeComponentFactory`
```
struct __attribute__((aligned(4))) BiomeComponentFactory
{
  JsonUtil::JsonSchemaRoot<BiomeComponentLoading::BiomeParseContext> mSchema;
  std::vector<std::function<void (CompoundTag &,EntityContext &,IWorldRegistriesProvider &)>> mExtraSerialization;
  BiomeComponentFactory::FactoryScope mScope;
  bool mClosedForRegistration;
};

```

### `BlockActorLevelListener`
```
struct __cppobj BlockActorLevelListener : LevelListener
{
};

```

### `BedHelper`
```
struct BedHelper
{
  float mNorthDir;
  float mSouthDir;
  float mWestDir;
  float mEastDir;
  float mBedOffsetX;
  float mBedOffsetZ;
  float mMobOffsetWestX;
  float mMobOffsetEastX;
  float mMobOffsetSouthZ;
  float mMobOffsetNorthZ;
};

```

### `BehaviorTreeDescription`
```
struct __cppobj BehaviorTreeDescription : ComponentDescription
{
  std::string mBehaviorTreeId;
};

```

### `BreakBlocksDescription`
```
struct __cppobj BreakBlocksDescription : ComponentDescription
{
  std::unordered_set<const BlockLegacy *> mBreakableBlocks;
};

```

### `BreakDoorAnnotationDescription`
```
struct __cppobj BreakDoorAnnotationDescription : ComponentDescription
{
  int mBreakTicks;
  Difficulty mMinDifficulty;
};

```

### `BlockSet`
```
struct BlockSet
{
  float cost;
  std::unordered_set<const BlockLegacy *> blocks;
};

```

### `BaseContainerMenu`
```
struct __cppobj __attribute__((aligned(8))) BaseContainerMenu : ContainerContentChangeListener, IContainerManager
{
  Player *mPlayer;
  std::vector<ItemStack> mLastSlots;
  ContainerID mContainerId;
  ContainerType mContainerType;
};

```

### `BlastFurnaceContainerManagerModel`
```
struct __cppobj BlastFurnaceContainerManagerModel : FurnaceContainerManagerModel
{
};

```

### `BrewingStandContainerManagerModel`
```
struct __cppobj BrewingStandContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  int mLastTickCount;
  int mLastFuelAmount;
  int mLastFuelTotal;
};

```

### `BeaconContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) BeaconContainerManagerModel : LevelContainerManagerModel
{
  std::weak_ptr<ContainerModel> mPaymentContainerModel;
  int mPrimaryEffectPreviousId;
  int mSecondaryEffectPreviousId;
  int mSelectedPrimaryEffectId;
  int mSelectedSecondaryEffectId;
  bool mEffectSelectionsChanged;
};

```

### `BlockCommandOrigin`
```
struct __cppobj __attribute__((aligned(8))) BlockCommandOrigin : CommandOrigin
{
  BlockSource *mRegion;
  BlockPos mPosition;
};

```

### `Bedrock::LogEndPoint`
```
struct Bedrock::LogEndPoint
{
  int (**_vptr$LogEndPoint)(void);
};

```

### `BalloonDefinition`
```
struct BalloonDefinition
{
  Vec3 mLiftForce;
};

```

### `BreathableDefinition`
```
struct BreathableDefinition
{
  int mTotalSupply;
  int mSuffocateTime;
  float mInhaleTime;
  bool mBreathesAir;
  bool mBreathesWater;
  bool mBreathesLava;
  bool mBreathesSolids;
  bool mGeneratesBubbles;
  std::set<const Block *> mBreathableBlocks;
  std::set<const Block *> mNonBreathableBlocks;
};

```

### `BidirectionalUnorderedMap<std::string,ActorDamageCause>`
```
struct BidirectionalUnorderedMap<std::string,ActorDamageCause>
{
  std::unordered_map<std::string,ActorDamageCause> mRight;
  std::unordered_map<ActorDamageCause,std::string> mLeft;
};

```

### `Bat`
```
struct __cppobj Bat : Mob
{
  bool mWasResting;
  Vec3 mTargetPosition;
};

```

### `Blaze`
```
struct __cppobj Blaze : Monster
{
  float mAllowedHeightOffset;
  int mNextHeightOffsetChangeTick;
};

```

### `Balloon`
```
struct __cppobj Balloon : Actor
{
  std::unique_ptr<MovementInterpolator> mInterpolator;
};

```

### `BrewingStandBlockActor`
```
struct __cppobj __attribute__((aligned(8))) BrewingStandBlockActor : BlockActor, Container:1952
{
  int mBrewTime;
  int mFuelAmount;
  int mFuelTotal;
  bool mFinished;
  const Item *mIngredient;
  ItemStack mItems[5];
  bool mNotifyPlayersOnChange;
};

```

### `BarrelBlockActor`
```
struct __cppobj __attribute__((aligned(8))) BarrelBlockActor : ChestBlockActor
{
};

```

### `BlockGraphics`
```
struct BlockGraphics
{
  int (**_vptr$BlockGraphics)(void);
  IsotropicFaceData mIsotropicFaceData;
  const Block *mBlock;
  BlockRenderLayer mRenderLayer;
  BlockShape mBlockShape;
  bool mAnimatedTexture;
  float mBrightnessGamma;
  Color mMapColor;
  bool mFancy;
  bool mAllowSame;
  BlockSoundType mSoundType;
  AABB mVisualShape;
  std::vector<TextureItem> mTextureItems;
  size_t mIconTextureIndex;
  std::vector<std::vector<const BlockGeometry::Model *>> mBlockModelVariants;
  std::vector<std::vector<BlockGraphics::ModelItem>> mTessellatedModelParts;
};

```

### `BegGoal`
```
struct __cppobj BegGoal : Goal
{
  Mob *mMob;
  float mLookDistance;
  int mLookTime;
  int mMinLookTime;
  int mMaxLookTime;
  TempEPtr<Player> mPlayer;
  std::vector<ItemDescriptor> mItems;
};

```

### `BreakDoorGoal`
```
struct __cppobj BreakDoorGoal : DoorInteractGoal
{
  int mBreakTime;
  const int mBreakDoorTime;
  int mLastBreakProgress;
  Mob *mMob;
};

```

### `BreedGoal`
```
struct __cppobj BreedGoal : Goal
{
  Mob *mOwner;
  TempEPtr<Mob> mPartner;
  int mLoveTime;
  float mSpeed;
};

```

### `BaseMoveToBlockGoal`
```
struct BaseMoveToBlockGoal
{
  __int8 baseclass_0[116];
  int mSearchRange;
  int mSearchHeight;
  int mSearchCount;
};

```

### `BedBlockActor`
```
struct __cppobj BedBlockActor : BlockActor:1632
{
  int mDyeColor;
  bool mDirty;
  ActorUniqueID mPetSleepingOnBed;
};

```

### `BellBlockActor`
```
struct __cppobj BellBlockActor : BlockActor:1608
{
  bool mRinging;
  Direction::Type mMovementDirection;
  bool mPowered;
  int mAlarmCooldown;
};

```

### `BreatheAirGoal`
```
struct __cppobj __attribute__((aligned(8))) BreatheAirGoal : Goal
{
  Mob *mMob;
  Vec3 mWanted;
  float mSpeedMod;
  int mRadius;
  int mStartBreath;
  bool mEndsInAir;
};

```

### `BoneAnimation`
```
struct __attribute__((aligned(8))) BoneAnimation
{
  HashedString mBoneName;
  std::vector<BoneAnimationChannel> mAnimationChannels;
  BoneAnimationRelativeMode mRotationRelativeMode;
};

```

### `BoneAnimationChannel`
```
struct BoneAnimationChannel
{
  BoneTransformType mBoneTransformType;
  std::vector<KeyFrameTransform> mKeyFrames;
};

```

### `BlockPatternBuilder`
```
struct __attribute__((aligned(8))) BlockPatternBuilder
{
  BlockSource *mRegion;
  std::vector<std::string> mPattern;
  std::map<char,PatternEntry> mLookup;
  bool mReadyForMatch;
  int mNumPatterns;
  int mPatternLength;
};

```

### `Boat::Paddle`
```
struct Boat::Paddle
{
  int mOldPressTime;
  int mPressTime;
  float mOldRowingTime;
  float mRowingTime;
  float mForce;
};

```

### `Bee`
```
struct __cppobj __attribute__((aligned(8))) Bee : Animal
{
  LoopingSoundHandle mNormalLoop;
  LoopingSoundHandle mAggressiveLoop;
  float mLoopSoundSpeed;
};

```

### `BeaconBlockActor`
```
struct __cppobj BeaconBlockActor : BlockActor, Container
{
  BeaconBlockActor::BeaconBeamSections mBeamSections;
  float mBeamRot;
  int mNumLevels;
  int mNumLevelsSet;
  int mBlockRefreshCounter;
  int mPrimaryEffectId;
  int mSecondaryEffectId;
  int mPrimaryEffectTier;
  int mSecondaryEffectTier;
  std::vector<MobEffect *> mBeaconEffects;
  std::vector<std::vector<MobEffect *>> mTierEffects;
};

```

### `BlockIsNameTest`
```
struct __cppobj BlockIsNameTest : SimpleHashStringFilterTest
{
};

```

### `BedrockItems`
```
struct BedrockItems
{
  __int8 gap0[1];
};

```

### `BidirectionalUnorderedMap<ItemUseMethod,std::string >`
```
struct BidirectionalUnorderedMap<ItemUseMethod,std::string >
{
  std::unordered_map<ItemUseMethod,std::string> mRight;
  std::unordered_map<std::string,ItemUseMethod> mLeft;
};

```

### `BidirectionalUnorderedMap<ItemAcquisitionMethod,std::string >`
```
struct BidirectionalUnorderedMap<ItemAcquisitionMethod,std::string >
{
  std::unordered_map<ItemAcquisitionMethod,std::string> mRight;
  std::unordered_map<std::string,ItemAcquisitionMethod> mLeft;
};

```

### `BlockItem`
```
struct __cppobj BlockItem : Item
{
};

```

### `BannerPatternItem`
```
struct __cppobj BannerPatternItem : Item
{
};

```

### `BowItem`
```
struct __cppobj BowItem : RangedWeaponItem
{
  TextureUVCoordinateSet mFrame[3];
};

```

### `BlockPlanterItem`
```
struct __cppobj BlockPlanterItem : Item
{
  const Block *mBlock;
};

```

### `BucketItem`
```
struct __cppobj BucketItem : Item
{
  TextureUVCoordinateSet m_uvBucketEmpty;
  TextureUVCoordinateSet m_uvBucketLava;
  TextureUVCoordinateSet m_uvBucketMilk;
  TextureUVCoordinateSet m_uvBucketWater;
  TextureUVCoordinateSet m_uvBucketFish;
  TextureUVCoordinateSet m_uvBucketSalmon;
  TextureUVCoordinateSet m_uvBucketTropical;
  TextureUVCoordinateSet m_uvBucketPuffer;
};

```

### `BoatItem`
```
struct __cppobj BoatItem : Item
{
  TextureAtlasItem m_uvTextureItem;
};

```

### `BedItem`
```
struct __cppobj BedItem : Item
{
  TextureAtlasItem m_uvTextureItem;
};

```

### `BottleItem`
```
struct __cppobj BottleItem : Item
{
};

```

### `BannerItem`
```
struct __cppobj BannerItem : Item
{
};

```

### `BalloonItem`
```
struct __cppobj BalloonItem : ChemistryItem
{
};

```

### `BambooBlockItem`
```
struct __cppobj BambooBlockItem : BlockItem
{
};

```

### `BellBlockItem`
```
struct __cppobj BellBlockItem : BlockItem
{
};

```

### `BannerPattern`
```
struct __attribute__((aligned(8))) BannerPattern
{
  uint8_t mID;
  RowList mPattern;
  ItemStack mIngredientItem;
  std::string mName;
  std::string mNameID;
  __int16 mPatternItemType;
  bool mIgnoreAux;
};

```

### `BannerRecipes`
```
struct BannerRecipes
{
  __int8 gap0[1];
};

```

### `BowEnchant`
```
struct __cppobj BowEnchant : Enchant
{
};

```

### `BaseMobSpawner`
```
struct BaseMobSpawner
{
  int (**_vptr$BaseMobSpawner)(void);
  int mSpawnDelay;
  float mSpin;
  float mOSpin;
  ActorDefinitionIdentifier mActorId;
  SpawnDataList mSpawnPotentials;
  Unique<SpawnData> mNextSpawnData;
  int mMinSpawnDelay;
  int mMaxSpawnDelay;
  int mSpawnCount;
  Unique<Mob> mDisplayEntity;
  int mMaxNearbyEntities;
  int mRequiredPlayerRange;
  int mSpawnRange;
  float mDisplayEntityWidth;
  float mDisplayEntityHeight;
  float mDisplayEntityScale;
};

```

### `BlockSource::Listener`
```
typedef BlockSourceListener BlockSource::Listener;

```

### `BlockTickingQueue::HashBlockTick`
```
struct BlockTickingQueue::HashBlockTick
{
  __int8 gap0[1];
};

```

### `BasicTimer`
```
struct BasicTimer
{
  double mTimeDelay;
  double mStartTime;
  std::function<double ()> mGetCurrentTimeCallback;
};

```

### `BiomeDecorationAttributes<ListedFeatures>::Element`
```
struct BiomeDecorationAttributes<ListedFeatures>::Element
{
  ScatterParams mScatter;
  WeakRef<IFeature> mFeature;
  StringKey mIdentifier;
};

```

### `BiomeComponentLoading::BiomeSchemaNode`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > >,std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > > BiomeComponentLoading::BiomeSchemaNode;

```

### `BiomeRegistry::BiomeLookupVector`
```
typedef std::vector<std::unique_ptr<Biome>> BiomeRegistry::BiomeLookupVector;

```

### `BaseRailTransporter`
```
struct __cppobj BaseRailTransporter : BaseCircuitComponent:480
{
  BaseRailTransporter::RailType mRailType;
};

```

### `BaseRailBlock`
```
struct __cppobj __attribute__((aligned(8))) BaseRailBlock : BlockLegacy
{
  const bool mUsesDataBit;
};

```

### `BedBlock`
```
struct __cppobj BedBlock : BlockLegacy
{
};

```

### `buffer_span<std::unique_ptr<Block> >`
```
struct buffer_span<std::unique_ptr<Block> >
{
  const std::unique_ptr<Block> *mBegin;
  const std::unique_ptr<Block> *mEnd;
};

```

### `BeehiveBlock`
```
struct __cppobj BeehiveBlock : ActorBlock
{
};

```

### `BidirectionalUnorderedMap<std::string,LevelSoundEvent>`
```
struct BidirectionalUnorderedMap<std::string,LevelSoundEvent>
{
  std::unordered_map<std::string,LevelSoundEvent> mRight;
  std::unordered_map<LevelSoundEvent,std::string> mLeft;
};

```

### `BannerBlockActor`
```
struct __attribute__((aligned(8))) BannerBlockActor
{
  __int8 baseclass_0[201];
  bool mDirtyBounds;
  uint8_t mBaseColor;
  std::vector<unsigned char> mPatterns;
  std::vector<unsigned char> mColors;
  BannerBlockType mType;
};

```

### `BeaconBlockActor::BeaconBeamSections`
```
typedef std::vector<BeaconBeamSection> BeaconBlockActor::BeaconBeamSections;

```

### `BlockActor:1608`
```
struct __attribute__((packed)) __attribute__((aligned(1))) BlockActor:1608
{
  int (**_vptr$BlockActor)(void);
  int mTickCount;
  _BYTE gapC[4];
  const Block *mBlock;
  float mDestroyTimer;
  Vec3 mDestroyDirection;
  float mDestroyProgress;
  BlockPos mPosition;
  AABB mBB;
  const BlockActorType mType;
  BlockActorRendererId mRendererId;
  _BYTE gap5C[4];
  std::string mCustomName;
  std::string mFilteredCustomName;
  int mRepairCost;
  bool mClientSideOnly;
  bool mIsMovable;
  bool mSaveCustomName;
  bool mCanRenderCustomName;
  const float signShadowRadius;
  _BYTE gapAC[4];
  ActorTerrainInterlockData mTerrainInterlockData;
  bool mChanged;
};

```

### `BlastFurnaceBlockActor`
```
struct __cppobj __attribute__((aligned(8))) BlastFurnaceBlockActor : FurnaceBlockActor
{
};

```

### `BeehiveBlockActor`
```
struct __cppobj __attribute__((aligned(8))) BeehiveBlockActor : BlockActor
{
  std::vector<BeehiveBlockActor::Occupant> mOccupants;
  bool mShouldSpawnBees;
};

```

### `BlockActorFactory`
```
struct BlockActorFactory
{
  __int8 gap0[1];
};

```

### `BurstReactionComponent`
```
struct __cppobj __attribute__((aligned(4))) BurstReactionComponent : LabTableReactionComponent
{
  ParticleType mParticleType;
  HashedString mNewParticleType;
  Vec3 mDims;
  Vec3 mDirRange;
  int mCount;
  int mDataMin;
  int mDataMax;
  bool mDirOneWay;
};

```

### `BlockDestroyTimeDescription`
```
struct __cppobj __attribute__((aligned(8))) BlockDestroyTimeDescription : BlockComponentDescription
{
  float mDestroyTime;
};

```

### `BlockExplodeableDescription`
```
struct __cppobj __attribute__((aligned(8))) BlockExplodeableDescription : BlockComponentDescription
{
  float mExplosionResistance;
};

```

### `BlockFrictionDescription`
```
struct __cppobj __attribute__((aligned(8))) BlockFrictionDescription : BlockComponentDescription
{
  float mFriction;
};

```

### `BlockFlammableDescription`
```
struct __cppobj BlockFlammableDescription : BlockComponentDescription
{
  int mFlameOdds;
  int mBurnOdds;
};

```

### `BlockMapColorDescription`
```
struct __cppobj __attribute__((aligned(8))) BlockMapColorDescription : BlockComponentDescription
{
  bool mEnabled;
  Color mMapColor;
};

```

### `BlockLightDescription`
```
struct __cppobj __attribute__((aligned(8))) BlockLightDescription : BlockComponentDescription
{
  bool mEnabled;
  Brightness mLightLevel;
};

```

### `BlockLightEmissionDescription`
```
struct __cppobj BlockLightEmissionDescription : BlockComponentDescription
{
  bool mEnabled;
  float mLightEmission;
};

```

### `BlockDefinitionGroup::loadResources::BlockResource`
```
struct BlockDefinitionGroup::loadResources::BlockResource
{
  SemVersion mVersion;
  BlockDescription mDescription;
  Json::Value mRoot;
};

```

### `BlockTypeRegistry`
```
struct BlockTypeRegistry
{
  __int8 gap0[1];
};

```

### `BedrockBlock`
```
struct __cppobj BedrockBlock : BlockLegacy
{
};

```

### `BookshelfBlock`
```
struct __cppobj BookshelfBlock : BlockLegacy
{
};

```

### `BrewingStandBlock`
```
struct __cppobj BrewingStandBlock : ActorBlock
{
};

```

### `BeaconBlock`
```
struct __cppobj BeaconBlock : ActorBlock
{
};

```

### `BannerBlock`
```
struct __cppobj __attribute__((aligned(8))) BannerBlock : ActorBlock
{
  bool mOnGround;
};

```

### `BeetrootBlock`
```
struct __cppobj BeetrootBlock : CropBlock
{
};

```

### `BlueIceBlock`
```
struct __cppobj BlueIceBlock : BlockLegacy
{
};

```

### `BubbleColumnBlock`
```
struct __cppobj __attribute__((aligned(8))) BubbleColumnBlock : BlockLegacy
{
  bool mFancyBubbles;
};

```

### `BarrierBlock`
```
struct __cppobj BarrierBlock : BlockLegacy
{
};

```

### `BambooBlock`
```
struct __cppobj BambooBlock : BlockLegacy
{
};

```

### `BambooSapling`
```
struct __cppobj BambooSapling : Sapling
{
};

```

### `BlastFurnaceBlock`
```
struct __cppobj __attribute__((aligned(8))) BlastFurnaceBlock : FurnaceBlock
{
};

```

### `BarrelBlock`
```
struct __cppobj BarrelBlock : FaceDirectionalBlock
{
};

```

### `BellBlock`
```
struct __cppobj BellBlock : ActorBlock
{
};

```

### `BidirectionalUnorderedMap<std::string,AutomaticID<Dimension,int> >`
```
struct BidirectionalUnorderedMap<std::string,AutomaticID<Dimension,int> >
{
  std::unordered_map<std::string,AutomaticID<Dimension,int>> mRight;
  std::unordered_map<AutomaticID<Dimension,int>,std::string> mLeft;
};

```

### `BlockIntersectionConstraint`
```
struct __cppobj BlockIntersectionConstraint : IStructureConstraint
{
  std::vector<BlockPos> mVolumeOffsets;
  std::unordered_map<std::string,const Block *> mBlockWhitelist;
};

```

### `BaseCircuitComponent:480`
```
struct __attribute__((packed)) __attribute__((aligned(4))) BaseCircuitComponent:480
{
  int (**_vptr$BaseCircuitComponent)(void);
  CircuitComponentList mSources;
  bool mIgnoreFirstUpdate;
  bool mIsFirstTime;
  bool mNeedsUpdate;
  __attribute__((aligned(2))) BlockPos mChunkPosition;
  bool mShouldEvaluate;
  __attribute__((aligned(4))) int mStrength;
  FacingID mDirection;
  bool mAllowPowerUp;
  bool mAllowPowerDown;
  bool mRemoved;
};

```

### `BlockGeometry::Model`
```
struct BlockGeometry::Model
{
  GameVersion mVersion;
  std::string mName;
  std::string mParent;
  std::vector<BlockGeometry::Element> mElements;
  std::unordered_map<std::string,std::string> mTextureMap;
  std::vector<std::string> mTextureList;
  std::vector<std::string> mTextureStack;
};

```

### `BlockGeometry::Element`
```
struct BlockGeometry::Element
{
  std::string mName;
  std::string mParent;
  glm::vec3 mPivot;
  glm::vec3 mRotation;
  std::vector<BlockGeometry::ElementBox> mBoxes;
};

```

### `BlockGeometry::ElementBox`
```
struct BlockGeometry::ElementBox
{
  glm::vec3 mOrigin;
  glm::vec3 mSize;
  std::array<BlockGeometry::Face,6> mFaces;
};

```

### `BlockGeometry::Face`
```
struct __attribute__((aligned(4))) BlockGeometry::Face
{
  float u0;
  float v0;
  float u1;
  float v1;
  int rotation;
  std::string texture;
  int textureIndex;
  bool enabled;
};

```

### `BlockGeometry::TessellatedModel`
```
struct BlockGeometry::TessellatedModel
{
  std::array<AABB,4> mAABoxes;
  std::array<std::vector<BlockGeometry::AlignedFace>,6> mEdgeSet;
  std::array<std::vector<BlockGeometry::AlignedFace>,6> mAlignedSet;
  BlockGeometry::OrientedFaceVector mOrientedSet;
  std::array<BlockGeometry::TessellatedModel::Occlusion,6> mOcclusion;
  std::array<BlockGeometry::TessellatedModel::Occlusion,3> mTopOcclusionRot;
  std::array<BlockGeometry::TessellatedModel::Occlusion,3> mBotOcclusionRot;
  std::vector<std::string> mTextureNames;
};

```

### `BlockGeometry::AlignedFace`
```
struct BlockGeometry::AlignedFace
{
  std::array<Vec3,4> verts;
  std::array<Vec2,4> uvs;
  size_t textureIndex;
};

```

### `BlockGeometry::OrientedFaceVector`
```
typedef std::vector<BlockGeometry::OrientedFace> BlockGeometry::OrientedFaceVector;

```

### `BlockGeometry::OrientedFace`
```
struct BlockGeometry::OrientedFace
{
  std::array<Vec3,4> verts;
  std::array<Vec2,4> uvs;
  Vec3 norm;
  size_t textureIndex;
};

```

### `BlockGeometry::TessellatedModel::Occlusion`
```
struct BlockGeometry::TessellatedModel::Occlusion
{
  std::array<unsigned char,8> blocking;
  std::array<unsigned char,8> visible;
};

```

### `BalloonableDefinition`
```
struct BalloonableDefinition
{
  float mSoftDistance;
  float mMaxDistance;
  float mInvMass;
  DefinitionTrigger mOnBalloon;
  DefinitionTrigger mOnUnballoon;
};

```

### `BlockBreakSensorDefinition`
```
struct BlockBreakSensorDefinition
{
  float mSensorRadius;
  std::vector<BlockListEventMap> mBlockSets;
};

```

### `BoostableDefinition`
```
struct __attribute__((aligned(8))) BoostableDefinition
{
  std::vector<BoostItem> mBoostItems;
  float mMaxBoostTime;
  float mSpeedModifier;
  float mFovMod;
};

```

### `BossDefinition`
```
struct BossDefinition
{
  std::string mName;
  bool mShouldDarkenSky;
  int mHudRange;
};

```

### `BlockListSerializer`
```
struct BlockListSerializer
{
  __int8 gap0[1];
};

```

### `BlockUtils`
```
struct BlockUtils
{
  __int8 gap0[1];
};

```

### `BidirectionalUnorderedMap<ContainerType,std::string >`
```
struct BidirectionalUnorderedMap<ContainerType,std::string >
{
  std::unordered_map<ContainerType,std::string> mRight;
  std::unordered_map<std::string,ContainerType> mLeft;
};

```

### `BurnsInDaylightDefinition`
```
struct BurnsInDaylightDefinition
{
  __int8 gap0[1];
};

```

### `BidirectionalUnorderedMap<ParticleType,std::string >`
```
struct BidirectionalUnorderedMap<ParticleType,std::string >
{
  std::unordered_map<ParticleType,std::string> mRight;
  std::unordered_map<std::string,ParticleType> mLeft;
};

```

### `BreakBlockDefinition`
```
struct __cppobj BreakBlockDefinition : BehaviorDefinition
{
  BlockPos mBlockPos;
  std::string mBlockPosId;
  int mNumTicksToBreak;
  std::string mNumTicksToBreakId;
};

```

### `BreakBlockNode`
```
struct __cppobj __attribute__((aligned(4))) BreakBlockNode : BehaviorNode:480
{
  BlockPos mBlockPos;
  int mNumTicksToBreak;
  const Block *mStartingBlock;
  int mNumTicksBreaking;
  bool mPreActionDone;
};

```

### `BehaviorData::Data<BlockPos>`
```
struct __cppobj BehaviorData::Data<BlockPos> : BehaviorData::DataProxy:352
{
  BlockPos mData;
};

```

### `BehaviorNode:480`
```
struct __attribute__((packed)) __attribute__((aligned(4))) BehaviorNode:480
{
  int (**_vptr$BehaviorNode)(void);
  const BehaviorDefinition *mNodeDefinition;
  BehaviorTreeDefinitionPtr mTreeDefinition;
  BehaviorNode *mParent;
  BehaviorComponent *mComponent;
  BehaviorData *mTreeData;
  BehaviorStatus mStatus;
};

```

### `BehaviorData::Data<int>`
```
struct __cppobj BehaviorData::Data<int> : BehaviorData::DataProxy:352
{
  int mData;
};

```

### `BehaviorData::Data<std::string >`
```
struct __cppobj BehaviorData::Data<std::string > : BehaviorData::DataProxy
{
  std::string mData;
};

```

### `BehaviorData::Data<bool>`
```
struct __cppobj __attribute__((aligned(8))) BehaviorData::Data<bool> : BehaviorData::DataProxy:328
{
  bool mData;
};

```

### `BehaviorData::Data<Vec3>`
```
struct __cppobj BehaviorData::Data<Vec3> : BehaviorData::DataProxy:352
{
  Vec3 mData;
};

```

### `BeaconPaymentContainerController`
```
struct __cppobj BeaconPaymentContainerController : ContainerController
{
};

```

### `BrewingStandInputContainerController`
```
struct __cppobj BrewingStandInputContainerController : ContainerController
{
};

```

### `BrewingStandResultContainerController`
```
struct __cppobj BrewingStandResultContainerController : ContainerController
{
};

```

### `BrewingStandFuelContainerController`
```
struct __cppobj BrewingStandFuelContainerController : ContainerController
{
};

```

### `BlockReducer`
```
struct BlockReducer
{
  int (**_vptr$BlockReducer)(void);
  std::unordered_map<int,std::vector<ItemStack>> mBlockToElements;
};

```

### `BasePressurePlateBlock`
```
struct __cppobj BasePressurePlateBlock : BlockLegacy
{
  std::string texture;
};

```

### `ButtonBlock`
```
struct __cppobj __attribute__((aligned(8))) ButtonBlock : BlockLegacy
{
  const bool mSensitive;
};

```

### `BeehiveBlockActor::Occupant`
```
struct __attribute__((aligned(8))) BeehiveBlockActor::Occupant
{
  ActorDefinitionIdentifier mActorIdentifier;
  CompoundTag mSaveData;
  unsigned int mTicksLeftToStay;
};

```

### `BehaviorData::DataProxy:352`
```
struct __attribute__((packed)) __attribute__((aligned(4))) BehaviorData::DataProxy:352
{
  int (**_vptr$DataProxy)(void);
  std::string mId;
  BehaviorData::DataType mType;
};

```

### `BehaviorData::Data<float>`
```
struct __cppobj BehaviorData::Data<float> : BehaviorData::DataProxy:352
{
  float mData;
};

```

### `BehaviorData::DataProxy:328`
```
struct __attribute__((packed)) __attribute__((aligned(1))) BehaviorData::DataProxy:328
{
  int (**_vptr$DataProxy)(void);
  std::string mId;
  BehaviorData::DataType mType;
};

```

### `BedrockLog::CategoryLogFile`
```
struct __attribute__((aligned(8))) BedrockLog::CategoryLogFile
{
  std::unordered_map<BedrockLog::LogChannel,std::unique_ptr<BedrockLog::LogDetails>,std::enum_hash<BedrockLog::LogChannel>,std::equal_to<BedrockLog::LogChannel>,std::allocator<std::pair<const BedrockLog::LogChannel,std::unique_ptr<BedrockLog::LogDetails> > > > mChannel;
  std::bitset<3> mCombinedChannelMask;
  int mMessageCount;
};

```

### `BedrockLog::LogDetails`
```
struct __attribute__((packed)) __attribute__((aligned(8))) BedrockLog::LogDetails
{
  SpinLock mLogMutex;
  bool mUseLogFile;
  bool mLogFileCreated;
  __attribute__((aligned(8))) Core::HeapPathBuffer mDebugLogFileName;
  Core::HeapPathBuffer mLogFilePath;
  Core::OutputFileStream mLogFile;
  bool mFlushImmediate;
  bool mTimestamp;
  bool mTrace;
  bool mPriority;
  bool mArea;
  bool mThreadId;
  bool mAppend;
  bool mProcessId;
  bool mMessageId;
  bool mSilent;
  __attribute__((aligned(4))) unsigned int mPriorityFilter;
  BedrockLog::LogAreaFilter mAreaFilter;
  double mFlushDelayTime;
  bool mCycleLog;
  __attribute__((aligned(8))) double mLastOpenTime;
  double mCycleTime;
  BedrockLog::LogChannel mChannel;
};

```

### `BackwardsCompatTextureInfo`
```
struct BackwardsCompatTextureInfo
{
  bool mUse;
  glm::vec2 mUVSize;
  glm::vec2 mUV;
  glm::vec2 mBaseSize;
  Core::HeapPathBuffer mBackCompatTexture;
};

```

### `Bedrock::Threading::AsyncResult::CompleteResult<void>`
```
struct __cppobj Bedrock::Threading::AsyncResult::CompleteResult<void> : Bedrock::Threading::IAsyncResult<void>
{
};

```

### `Bedrock::Threading::UniqueLock<std::mutex>`
```
typedef std::unique_lock<std::mutex> Bedrock::Threading::UniqueLock<std::mutex>;

```

### `Bedrock::Threading::ThreadUtil`
```
struct Bedrock::Threading::ThreadUtil
{
  __int8 gap0[1];
};

```

