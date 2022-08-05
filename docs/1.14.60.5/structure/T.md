# T
### `Tick`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | tickID


### `Tag`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Tag


### `TagMap`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,CompoundTagVariant>::_Rep_type` | _M_t


### `typeid_t<CommandRegistry>`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mID


### `TextPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `TextPacketType` | mType
40 | (32) `std::string` | mAuthor
72 | (32) `std::string` | mMessage
104 | (24) `std::vector<std::string>` | params
128 | (1) `bool` | mLocalize
136 | (32) `std::string` | mXuid
168 | (32) `std::string` | mPlatformId


### `Trade`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMaxUses
4 | (1) `bool` | mRewardExperience
8 | (4) `int` | mWeight
12 | (4) `unsigned int` | mTraderExperience
16 | (24) `std::vector<std::vector<TradeItem>>` | mOffer
40 | (24) `std::vector<std::vector<TradeItem>>` | mReceive


### `typeid_t<IDefinitionInstance>`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mID


### `TextObjectRoot`
Offset | Type | Name
-|-|-|-
0 | (8) `ITextObject` | baseclass_0
8 | (24) `std::vector<std::unique_ptr<ITextObject>>` | mChildren


### `TargetNearbyComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mWasSeenLastTick
1 | (1) `bool` | mWasInsideRange
2 | (1) `bool` | mWasOutsideRange
4 | (4) `float` | mPreviousDistance


### `TeleportComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mRandomTeleports
4 | (4) `int` | mMinTeleportTime
8 | (4) `int` | mMaxTeleportTime
12 | (12) `Vec3` | mRandomTeleportCube
24 | (4) `float` | mTargetDistance
28 | (4) `float` | mTargetTeleportChance
32 | (4) `float` | mLightTeleportChance
36 | (4) `float` | mDarkTeleportChance
40 | (4) `int` | mTeleportTime


### `TimerComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTime
8 | (8) `uint64_t` | mTimeStamp
16 | (1) `bool` | mHasExecuted
17 | (1) `bool` | mLooping
20 | (4) `int` | mStartTime
24 | (1) `bool` | mRandomInterval
28 | (4) `int` | mMinTime
32 | (4) `int` | mMaxTime
40 | (128) `DefinitionTrigger` | mOnTimeDown
168 | (24) `WeightedChoices<float>` | mTimeChoices


### `TrailSystem::BlockPositions`
Offset | Type | Name
-|-|-|-
0 | (48) `BlockPos[4]` | mBlockPos


### `TrailComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockLegacy *` | mBlockType
8 | (12) `Vec3` | mSpawnOffset


### `TransformationComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDelayTicks


### `TagMemoryChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mElements
8 | (8) `size_t` | mSize
16 | (8) `std::unique_ptr<unsigned char []>` | mBuffer


### `ThirdPartyInfo`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<std::string>` | mWhitelistUrls
56 | (32) `std::string` | mCreatorId
88 | (32) `std::string` | mCreatorName
120 | (1) `bool` | mRequireXBL


### `TaskStartInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `string_span` | name
16 | (8) `std::thread::id` | affinity
24 | (4) `uint32_t` | priority
28 | (4) `int` | priorityBackDown
32 | (4) `TaskOptions` | options
40 | (8) `std::chrono::_V2::steady_clock::time_point` | startAtTime
48 | (16) `Bedrock::Threading::IAsyncResult<void>::Handle` | predecessor


### `TransferPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mServerAddress
72 | (4) `int` | mServerPort


### `TickSyncPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `int64_t` | mClientRequestTimestamp
48 | (8) `int64_t` | mServerReceptionResponseTimestamp


### `TintMapColor`
Offset | Type | Name
-|-|-|-
0 | (64) `std::array<Color,4>` | colors


### `ThreadConfiguration`
Offset | Type | Name
-|-|-|-
0 | (4) `Bedrock::Threading::OSThreadPriority` | Priority
8 | (16) `std::optional<unsigned long>` | CoreAffinityMask
24 | (4) `int32_t` | IdealCore


### `ThreadConfiguration:224`
Offset | Type | Name
-|-|-|-
0 | (4) `Bedrock::Threading::OSThreadPriority` | Priority
4 | (4) `_BYTE[4]` | gap4
8 | (16) `std::optional<unsigned long>` | CoreAffinityMask
24 | (4) `int32_t` | IdealCore


### `typeid_t<ScriptBinderComponent>`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mID


### `TeleportDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (1) `bool` | mRandomTeleports
12 | (4) `float` | mMinTeleportTime
16 | (4) `float` | mMaxTeleportTime
20 | (12) `Vec3` | mRandomTeleportCube
32 | (4) `float` | mTargetDistance
36 | (4) `float` | mTargetTeleportChance
40 | (4) `float` | mLightTeleportChance
44 | (4) `float` | mDarkTeleportChance


### `TickingAreaDescription`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mOrigin
12 | (12) `BlockPos` | mMax
24 | (4) `uint32_t` | mRadius
32 | (32) `std::string` | mName
64 | (1) `bool` | mIsCircle


### `TagsDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0


### `TextureUVCoordinateSet`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | weight
4 | (4) `float` | _u0
8 | (4) `float` | _v0
12 | (4) `float` | _u1
16 | (4) `float` | _v1
20 | (2) `uint16_t` | _texSizeW
22 | (2) `uint16_t` | _texSizeH
24 | (56) `ResourceLocation` | sourceFileLocation
80 | (8) `IsotropicFaceData` | mIsotropicFaceData


### `TrustComponent`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<ActorUniqueID>` | mTrustedPlayerIDs


### `TagsComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `TagSetID` | mTagSetID


### `TagSetID`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mID


### `TameableComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
8 | (48) `std::set<const Item *>` | mTameItems


### `TickWorldComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mChunkRadius
4 | (4) `float` | mMaxDistToPlayers
8 | (1) `bool` | mAlwaysActive
9 | (1) `bool` | mChanged
16 | (16) `std::weak_ptr<ITickingArea>` | mTickingArea


### `TrustingComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
8 | (48) `std::set<const Item *>` | mTrustItems


### `TradeResupplyComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHasResupplied


### `Token::List`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<Token>` | baseclass_0


### `TargetDescriptorList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobDescriptor>` | baseclass_0


### `TripodCameraComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `TakeItemActorPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mItemId
48 | (8) `ActorRuntimeID` | mPlayerId


### `TemporalAttributeBuff`
Offset | Type | Name
-|-|-|-
0 | (84) `AttributeBuff:672` | baseclass_0
84 | (4) `int` | mDuration
88 | (4) `int` | mLifeTimer
92 | (4) `float` | mBaseAmount
96 | (1) `bool` | mIsSerializable


### `TextureAtlasItem`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `int` | mParsedNodeIndex
40 | (24) `std::vector<std::vector<TextureUVCoordinateSet>>` | mTextureUVs


### `TradeTier`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mExpToUnlock
8 | (24) `std::vector<TradeGroup>` | mGroups


### `TradeGroup`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mNumToSelect
8 | (24) `std::vector<Trade>` | mTrades


### `TradeItem`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | itemId
4 | (4) `int` | itemAux
8 | (4) `int` | count_min
12 | (4) `int` | count_max
16 | (4) `float` | price_multiplier
24 | (24) `std::vector<std::unique_ptr<LootItemFunction>>` | functions


### `TickNextTickData`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | pos
16 | (8) `const Block *` | mBlock
24 | (8) `Tick` | tick
32 | (4) `int` | priorityOffset


### `tm`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | tm_sec
4 | (4) `int` | tm_min
8 | (4) `int` | tm_hour
12 | (4) `int` | tm_mday
16 | (4) `int` | tm_mon
20 | (4) `int` | tm_year
24 | (4) `int` | tm_wday
28 | (4) `int` | tm_yday
32 | (4) `int` | tm_isdst
40 | (8) `__int64` | tm_gmtoff
48 | (8) `const char *` | tm_zone


### `TrackedUniqueChunkPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LevelChunk,LevelChunkFinalDeleter>` | _M_t


### `TagRegistry`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<StringKey,unsigned int>` | mTagIndexMap
56 | (24) `std::vector<std::string>` | mTags
80 | (24) `std::vector<IndexSet>` | mSets
104 | (24) `std::vector<std::string>` | mTagsScratchpad
128 | (24) `std::vector<IDType<TagIDType>>` | mTagIDScratchpad
152 | (48) `IndexSet` | mIndexSetScratchpad
200 | (8) `TagSetID` | mEmptyTagSet


### `TagID`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mID


### `TickingAreasList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::shared_ptr<ITickingArea>>` | baseclass_0


### `TextureItem`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | defaultName
32 | (32) `std::string` | carriedName
64 | (64) `TextureAtlasItem` | defaultItem
128 | (64) `TextureAtlasItem` | carriedItem


### `typeid_t<ContextAccessor>`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mID


### `TagCommand::ActorRefList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::reference_wrapper<Actor>>` | baseclass_0


### `TagCommand::_listTags::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Token`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mText
32 | (4) `Token::$8E444B718253266053441DBC27016FD8` | _anon_0
36 | (4) `Token::Type` | mType
40 | (1) `bool` | mIsDefault


### `Token::$8E444B718253266053441DBC27016FD8`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mIntValue
1 | (1) `bool` | mBoolValue


### `type_safe::strong_typedef<mce::Radian,float>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | value_


### `TaskResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsDone
8 | (8) `std::chrono::_V2::steady_clock::time_point` | mRunAtTime
16 | (16) `Bedrock::Threading::IAsyncResult<void>::Handle` | mWaitOperation
32 | (1) `bool` | mLinkWaitOperation


### `timeval`
Offset | Type | Name
-|-|-|-
0 | (8) `__time_t` | tv_sec
8 | (8) `__suseconds_t` | tv_usec


### `timespec`
Offset | Type | Name
-|-|-|-
0 | (8) `__time_t` | tv_sec
8 | (8) `__syscall_slong_t` | tv_nsec


### `tm_unz`
Offset | Type | Name
-|-|-|-
0 | (4) `uInt` | tm_sec
4 | (4) `uInt` | tm_min
8 | (4) `uInt` | tm_hour
12 | (4) `uInt` | tm_mday
16 | (4) `uInt` | tm_mon
20 | (4) `uInt` | tm_year


### `tm_zip`
Offset | Type | Name
-|-|-|-
0 | (4) `uInt` | tm_sec
4 | (4) `uInt` | tm_min
8 | (4) `uInt` | tm_hour
12 | (4) `uInt` | tm_mday
16 | (4) `uInt` | tm_mon
20 | (4) `uInt` | tm_year


### `type_safe::strong_typedef<mce::Degree,float>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | value_


### `ThreadLocal<ResourceLoadManager::ResourceLoadTaskGroup *>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<ResourceLoadManager::ResourceLoadTaskGroup *>::Creator` | mCreator
32 | (24) `ThreadLocal<ResourceLoadManager::ResourceLoadTaskGroup *>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<ResourceLoadManager::ResourceLoadTaskGroup *>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<ResourceLoadManager::ResourceLoadTaskGroup *> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<ResourceLoadManager::ResourceLoadTaskGroup *>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<ResourceLoadManager::ResourceLoadTaskGroup *>>` | baseclass_0


### `ThreadLocal<PerfTimer>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<PerfTimer>::Creator` | mCreator
32 | (24) `ThreadLocal<PerfTimer>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<PerfTimer>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<PerfTimer> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<PerfTimer>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<PerfTimer>>` | baseclass_0


### `ThreadLocal<EvalParams>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<EvalParams>::Creator` | mCreator
32 | (24) `ThreadLocal<EvalParams>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<EvalParams>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<EvalParams> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<EvalParams>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<EvalParams>>` | baseclass_0


### `ThreadLocal<Random>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<Random>::Creator` | mCreator
32 | (24) `ThreadLocal<Random>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<Random>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<Random> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<Random>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<Random>>` | baseclass_0


### `ThreadLocal<DBStorageWriteBatch>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<DBStorageWriteBatch>::Creator` | mCreator
32 | (24) `ThreadLocal<DBStorageWriteBatch>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<DBStorageWriteBatch>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<DBStorageWriteBatch> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<DBStorageWriteBatch>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<DBStorageWriteBatch>>` | baseclass_0


### `ThreadLocal<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<std::string >::Creator` | mCreator
32 | (24) `ThreadLocal<std::string >::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<std::string> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<std::string>>` | baseclass_0


### `ThreadLocal<Core::Random>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<Core::Random>::Creator` | mCreator
32 | (24) `ThreadLocal<Core::Random>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<Core::Random>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<Core::Random> ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<Core::Random>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<Core::Random>>` | baseclass_0


### `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>::Creator` | mCreator
32 | (24) `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>::Pool` | mPool
56 | (40) `Bedrock::Threading::Mutex` | mCreatorLock
96 | (1) `bool` | mInitialized
100 | (4) `pthread_key_t` | mKey


### `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>::Creator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool),std::default_delete<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)> > ()>::_Invoker_type` | _M_invoker


### `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>::Pool`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool),std::default_delete<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)> >>` | baseclass_0


### `TaskGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `ITaskGroup` | baseclass_0
8 | (8) `Scheduler *` | mScheduler
16 | (8) `WorkerPool *` | mWorkers
24 | (32) `std::string` | mName
56 | (1) `bool` | mCheckOwnerThread
64 | (40) `Bedrock::Threading::Mutex` | mLock
104 | (4) `std::atomic<TaskGroupState>` | mState
112 | (16) `std::shared_ptr<BackgroundTask>` | mTasks
128 | (8) `size_t` | mTaskCount
136 | (16) `std::shared_ptr<BackgroundTask>` | mEnumCurr
152 | (16) `std::shared_ptr<BackgroundTask>` | mEnumNext


### `type_safe::strong_typedef_op::unary_minus<mce::Radian>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `TropicalFish::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `TripodCamera::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `TickDelayBlock`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTickDelay
8 | (8) `const Block *` | mBlock


### `type_safe::strong_typedef_op::relational_comparison<mce::Degree>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `type_safe::strong_typedef_op::addition<mce::Degree>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ThreadLocal<ThreadSpecificData>`
```
struct ThreadLocal<ThreadSpecificData>
{
  ThreadLocal<ThreadSpecificData>::Creator mCreator;
  ThreadLocal<ThreadSpecificData>::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<ThreadSpecificData>::Creator`
```
typedef std::function<std::unique_ptr<ThreadSpecificData> ()> ThreadLocal<ThreadSpecificData>::Creator;

```

### `ThreadLocal<ThreadSpecificData>::Pool`
```
typedef std::vector<std::unique_ptr<ThreadSpecificData>> ThreadLocal<ThreadSpecificData>::Pool;

```

### `ThreadSpecificData`
```
struct ThreadSpecificData
{
  std::vector<std::string> mScope;
  std::vector<ContextMessageLogger *> mMessageLoggers;
};

```

### `TestDedicatedServerCommands`
```
struct TestDedicatedServerCommands
{
  __int8 gap0[1];
};

```

### `TradeableSystem`
```
struct __cppobj TradeableSystem : ITickingSystem
{
};

```

### `TeleportSystem`
```
struct __cppobj TeleportSystem : ITickingSystem
{
};

```

### `TimerSystem`
```
struct __cppobj TimerSystem : ITickingSystem
{
};

```

### `TransformationSystem`
```
struct __cppobj TransformationSystem : ITickingSystem
{
};

```

### `TrailSystem`
```
struct __cppobj TrailSystem : ITickingSystem
{
};

```

### `TargetNearbySystem`
```
struct __cppobj TargetNearbySystem : ITickingSystem
{
};

```

### `TheEndDimension`
```
struct __cppobj TheEndDimension : Dimension
{
  Unique<EndDragonFight> mDragonFight;
};

```

### `TreeFeature`
```
struct __cppobj __attribute__((aligned(8))) TreeFeature : Feature
{
  int mTrunkType;
  int mLeafType;
  bool mAddJungleFeatures;
  bool mHasBeehive;
};

```

### `TallGrassFeature`
```
struct __cppobj TallGrassFeature : Feature
{
  const Block *mGrass;
};

```

### `TickingAreaList`
```
struct __cppobj TickingAreaList : TickingAreaListBase
{
};

```

### `TickingAreaListBase`
```
struct TickingAreaListBase
{
  TickingAreasList mTickingAreas;
};

```

### `ThreadLocal<NetherGenerator::ThreadData>`
```
struct ThreadLocal<NetherGenerator::ThreadData>
{
  ThreadLocal<NetherGenerator::ThreadData>::Creator mCreator;
  ThreadLocal<NetherGenerator::ThreadData>::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<NetherGenerator::ThreadData>::Creator`
```
typedef std::function<std::unique_ptr<NetherGenerator::ThreadData> ()> ThreadLocal<NetherGenerator::ThreadData>::Creator;

```

### `ThreadLocal<NetherGenerator::ThreadData>::Pool`
```
typedef std::vector<std::unique_ptr<NetherGenerator::ThreadData>> ThreadLocal<NetherGenerator::ThreadData>::Pool;

```

### `TransformationMixerLayer<WeightedBiomeAttributes<RiverTransformation> >`
```
struct __cppobj TransformationMixerLayer<WeightedBiomeAttributes<RiverTransformation> > : MixerLayer<Biome *,Biome *,bool>
{
  Biome *mDefaultTransformation;
};

```

### `ThreadLocal<OverworldGenerator::ThreadData>`
```
struct ThreadLocal<OverworldGenerator::ThreadData>
{
  ThreadLocal<OverworldGenerator::ThreadData>::Creator mCreator;
  ThreadLocal<OverworldGenerator::ThreadData>::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<OverworldGenerator::ThreadData>::Creator`
```
typedef std::function<std::unique_ptr<OverworldGenerator::ThreadData> ()> ThreadLocal<OverworldGenerator::ThreadData>::Creator;

```

### `ThreadLocal<OverworldGenerator::ThreadData>::Pool`
```
typedef std::vector<std::unique_ptr<OverworldGenerator::ThreadData>> ThreadLocal<OverworldGenerator::ThreadData>::Pool;

```

### `TemplateStructurePiece`
```
struct __cppobj __attribute__((aligned(8))) TemplateStructurePiece : StructurePiece
{
  LegacyStructureTemplate *mTemplate;
  LegacyStructureSettings mSettings;
  BlockPos mTemplatePosition;
};

```

### `TelemetryInfo`
```
struct __attribute__((aligned(4))) TelemetryInfo
{
  PropertyBag mOldInfo;
  PropertyBag mNewPendingInfo;
  Core::HeapPathBuffer mFilePath;
  int mPropertyChangeVersion;
  bool mTampered;
  bool mFirstSession;
};

```

### `TradeTable`
```
struct TradeTable
{
  Core::HeapPathBuffer mPath;
  std::vector<TradeTier> mTiers;
};

```

### `TradeTables`
```
struct TradeTables
{
  std::unordered_map<std::string,std::unique_ptr<TradeTable>> mTradeTables;
};

```

### `TargetNearbyDescription`
```
struct __cppobj TargetNearbyDescription : ComponentDescription
{
  float mInsideRange;
  float mOutsideRange;
  bool mMustSee;
  DefinitionTrigger mInsideRangeTrigger;
  DefinitionTrigger mOutsideRangeTrigger;
  DefinitionTrigger mLostVisionTrigger;
};

```

### `TrailDescription`
```
struct __cppobj __attribute__((aligned(8))) TrailDescription : ComponentDescription
{
  ActorFilterGroup mSpawnCondition;
  std::string mBlockType;
  Vec3 mSpawnOffset;
};

```

### `TransformationDescription`
```
struct __cppobj __attribute__((aligned(8))) TransformationDescription : ComponentDescription
{
  ActorDefinitionIdentifier mEntityName;
  int mDelayTicks;
  bool mDropEquipment;
  std::vector<LevelSoundEvent> mBeginTransformSound;
  std::vector<LevelSoundEvent> mTransformSound;
  float mBlockAssistChance;
  int mBlockRadius;
  int mBlockMax;
  float mBlockChance;
  std::vector<std::string> mBlockTypes;
  std::vector<std::string> mAddComponentGroups;
  bool mMaintainOwner;
  bool mMaintainTradeLevel;
};

```

### `TrackerStat`
```
struct TrackerStat
{
  unsigned int sentCount;
  unsigned int sentBytes;
  unsigned int receivedCount;
  unsigned int receivedBytes;
  uint32_t sampleNum;
};

```

### `ThirdPartyServer`
```
struct __attribute__((aligned(8))) ThirdPartyServer
{
  std::string mCreatorName;
  std::string mProductId;
  std::string mCreatorId;
  std::string mTitle;
  std::string mDescription;
  std::string mWhitelistUrl;
  Core::HeapPathBuffer mImagePath;
  std::string mServerUrl;
  uint16_t mServerPort;
  bool mRequireXBL;
  bool mIsImageFinished;
};

```

### `TreatmentPackSource`
```
struct __cppobj TreatmentPackSource : PackSource
{
  bool mDiscovered;
  Core::HeapPathBuffer mPath;
  PackType mPackType;
  std::vector<std::unique_ptr<Pack>> mPacks;
};

```

### `Timer`
```
struct Timer
{
  float mTicksPerSecond;
  int mTicks;
  float mAlpha;
  float mTimeScale;
  float mPassedTime;
  float mFrameStepAlignmentRemainder;
  float mLastTimeSeconds;
  float mLastTimestep;
  int mLastMs;
  int mLastMsSysTime;
  float mAdjustTime;
  int mSteppingTick;
  std::function<int ()> mGetTimeMSCallback;
};

```

### `TickingAreasManager`
```
struct TickingAreasManager
{
  const DimensionMap *mDimensions;
  std::unordered_map<AutomaticID<Dimension,int>,std::vector<PendingArea>> mPendingAreas;
};

```

### `TameableDescription`
```
struct __cppobj TameableDescription : ComponentDescription
{
  float mTameChance;
  std::set<const Item *> mTameItems;
  DefinitionTrigger mOnTame;
};

```

### `TrustingDescription`
```
struct __cppobj TrustingDescription : ComponentDescription
{
  float mTrustChance;
  std::set<const Item *> mTrustItems;
  DefinitionTrigger mOnTrust;
};

```

### `TickWorldDescription`
```
struct __cppobj __attribute__((aligned(8))) TickWorldDescription : ComponentDescription
{
  uint32_t mChunkRadius;
  float mMaxDistToPlayers;
  bool mAlwaysActive;
};

```

### `TimerDescription`
```
struct __cppobj TimerDescription : ComponentDescription
{
  bool mLooping;
  bool mRandomInterval;
  FloatRange mTime;
  DefinitionTrigger mOnTimeDown;
  WeightedChoices<float> mTimeChoices;
};

```

### `TradeResupplyDescription`
```
struct __cppobj TradeResupplyDescription : ComponentDescription
{
};

```

### `TrustDescription`
```
struct __cppobj TrustDescription : ComponentDescription
{
};

```

### `TripodCameraDescription`
```
struct __cppobj TripodCameraDescription : ComponentDescription
{
};

```

### `TriggerDescription`
```
struct __cppobj TriggerDescription : Description
{
  DefinitionTrigger mTrigger;
};

```

### `TradeContainerManagerModel`
```
struct __cppobj TradeContainerManagerModel : LevelContainerManagerModel:1312
{
  int mCurrentIndex;
};

```

### `TestCommandOrigin`
```
struct __cppobj __attribute__((aligned(8))) TestCommandOrigin : CommandOrigin
{
  ActorUniqueID mPlayerId;
  Level *mLevel;
  NetworkIdentifier mSourceId;
  uint8_t mSourceSubId;
};

```

### `TextObjectText`
```
struct __cppobj TextObjectText : ITextObject
{
  std::string mText;
};

```

### `TextObjectLocalizedText`
```
struct __cppobj TextObjectLocalizedText : ITextObject
{
  std::string mText;
};

```

### `TextObjectLocalizedTextWithParams`
```
struct __cppobj TextObjectLocalizedTextWithParams : ITextObject
{
  std::string mText;
  std::vector<std::string> mParams;
};

```

### `TextObjectParser`
```
struct TextObjectParser
{
  __int8 gap0[1];
};

```

### `TimeStamp`
```
struct TimeStamp
{
  __int8 gap0[1];
};

```

### `TropicalFish`
```
struct __cppobj TropicalFish : WaterAnimal
{
  float mAnimationAmount;
  float mAnimationAmountPrev;
};

```

### `Turtle`
```
struct __cppobj __attribute__((aligned(8))) Turtle : Animal
{
  int mLayEggCounter;
};

```

### `ThrownEgg`
```
struct __cppobj ThrownEgg : Throwable
{
};

```

### `ThrownTrident`
```
struct __cppobj ThrownTrident : AbstractArrow
{
  bool mDealtDamage;
  int mClientSideReturnTridentTickCount;
  ItemStack mTrident;
};

```

### `ThrownPotion`
```
struct __cppobj ThrownPotion : Throwable
{
};

```

### `ThrownEnderpearl`
```
struct __cppobj ThrownEnderpearl : Throwable
{
};

```

### `ThrownIceBomb`
```
struct __cppobj ThrownIceBomb : Throwable
{
};

```

### `TripodCamera`
```
struct __cppobj TripodCamera : Mob
{
  TempEPtr<Player> mPlayer;
  bool mActivated;
  int mCountdown;
};

```

### `type_safe::strong_typedef_op::equality_comparison<mce::Degree>`
```
struct type_safe::strong_typedef_op::equality_comparison<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::floating_point_arithmetic<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::floating_point_arithmetic<mce::Degree> : type_safe::strong_typedef_op::unary_plus<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<mce::Degree>`
```
struct type_safe::strong_typedef_op::unary_plus<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::unary_minus<mce::Degree>`
```
struct type_safe::strong_typedef_op::unary_minus<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::subtraction<mce::Degree>`
```
struct type_safe::strong_typedef_op::subtraction<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::multiplication<mce::Degree>`
```
struct type_safe::strong_typedef_op::multiplication<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::division<mce::Degree>`
```
struct type_safe::strong_typedef_op::division<mce::Degree>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::$256B327EE357AF9FCD813216707B60D5`
```
struct type_safe::strong_typedef_op::$256B327EE357AF9FCD813216707B60D5
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::equality_comparison<mce::Radian>`
```
struct type_safe::strong_typedef_op::equality_comparison<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::relational_comparison<mce::Radian>`
```
struct type_safe::strong_typedef_op::relational_comparison<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::floating_point_arithmetic<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::floating_point_arithmetic<mce::Radian> : type_safe::strong_typedef_op::unary_plus<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<mce::Radian>`
```
struct type_safe::strong_typedef_op::unary_plus<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::addition<mce::Radian>`
```
struct type_safe::strong_typedef_op::addition<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::subtraction<mce::Radian>`
```
struct type_safe::strong_typedef_op::subtraction<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::multiplication<mce::Radian>`
```
struct type_safe::strong_typedef_op::multiplication<mce::Radian>
{
  __int8 gap0[1];
};

```

### `type_safe::strong_typedef_op::division<mce::Radian>`
```
struct type_safe::strong_typedef_op::division<mce::Radian>
{
  __int8 gap0[1];
};

```

### `TargetWhenPushedGoal`
```
struct __cppobj TargetWhenPushedGoal : Goal
{
  Mob *mSelf;
  float mPercentChance;
  const TargetDescriptorList mTargetTypes;
};

```

### `TemptGoal`
```
struct __cppobj __attribute__((aligned(8))) TemptGoal : Goal
{
  Mob *mMob;
  float mSpeed;
  TempEPtr<Player> mPlayer;
  Vec3 mOldPlayerPosition;
  Vec2 mOldPlayerRotation;
  bool mCanGetScared;
  int mCalmDown;
  bool mIsRunning;
  bool mOldAvoidWater;
  int mPathfinderWaitTicks;
  float mTemptDistance;
  std::vector<ItemDescriptor> mItems;
  bool mCanTemptVertically;
};

```

### `TradeInterestGoal`
```
struct __cppobj TradeInterestGoal : Goal
{
  Mob *mMob;
  TempEPtr<Player> mPlayer;
  bool mIsRunning;
  bool mIsOnlyTargetItemFound;
  float mInterestDistance;
  size_t mCurrentIndex;
  ItemStack mCarriedItem;
  ItemStack mPlayerItem;
  Tick mCarriedItemSwitchTimer;
  Tick mRemoveItemTimer;
  Tick mInterestTimer;
  Tick mInterestCooldown;
  const Tick mInterestTimeMax;
  const Tick mInterestTimeMaxHalf;
  const Tick mRemoveTimeMax;
  const Tick mCarriedSwitchMax;
  const Tick mInterestCooldownMax;
};

```

### `TakeFlowerGoal`
```
struct __cppobj TakeFlowerGoal : Goal
{
  TempEPtr<IronGolem> mGolem;
  int mPickupTick;
  bool mTakeFlower;
  Mob *mMob;
};

```

### `TradeWithPlayerGoal`
```
struct __cppobj TradeWithPlayerGoal : Goal
{
  Mob *mMob;
};

```

### `TempEPtr<Actor>`
```
struct __cppobj __attribute__((aligned(8))) TempEPtr<Actor> : _TickPtr
{
  Actor *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<Mob>`
```
struct __cppobj __attribute__((aligned(8))) TempEPtr<Mob> : _TickPtr
{
  Mob *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TargetGoal`
```
struct __cppobj TargetGoal : Goal
{
  const std::vector<MobDescriptor> mTargetTypes;
  float mWithinDefault;
  bool mGlobalMustSee;
  int mGlobalMustSeeForgetTicks;
  bool mMustReach;
  int mReachCache;
  int mReachCacheTime;
  int mUnseenTicks;
  bool mAttackOwner;
  int mPersistTargetTicks;
  int mFilterFailureTicks;
  bool mFilterFailure;
  Mob *mMob;
  bool mTargetMustSee;
  int mTargetMustSeeForgetTicks;
};

```

### `TempEPtr<Villager>`
```
struct __cppobj __attribute__((aligned(8))) TempEPtr<Villager> : _TickPtr
{
  Villager *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<IronGolem>`
```
struct __cppobj __attribute__((aligned(8))) TempEPtr<IronGolem> : _TickPtr
{
  IronGolem *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<Player>`
```
struct __cppobj __attribute__((aligned(8))) TempEPtr<Player> : _TickPtr
{
  Player *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TopSnowBlock`
```
struct __cppobj TopSnowBlock : HeavyBlock
{
};

```

### `Throwable`
```
struct __cppobj Throwable : Actor
{
  bool mInGround;
  ActorUniqueID mOwnerId;
  int mShakeTime;
  int mLife;
  MovementInterpolator mInterpolation;
};

```

### `ThrownPotionEffectSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) ThrownPotionEffectSubcomponent : SplashPotionEffectSubcomponent
{
};

```

### `TeleportToSubcomponent`
```
struct __cppobj TeleportToSubcomponent : OnHitSubcomponent
{
};

```

### `TridentItem`
```
struct __cppobj TridentItem : Item
{
};

```

### `TopSnowBlockItem`
```
struct __cppobj TopSnowBlockItem : BlockItem
{
};

```

### `ToolRecipes`
```
struct ToolRecipes
{
  __int8 gap0[1];
};

```

### `TridentImpalerEnchant`
```
struct __cppobj TridentImpalerEnchant : Enchant
{
};

```

### `TridentRiptideEnchant`
```
struct __cppobj TridentRiptideEnchant : Enchant
{
};

```

### `TridentLoyaltyEnchant`
```
struct __cppobj TridentLoyaltyEnchant : Enchant
{
};

```

### `TridentChannelingEnchant`
```
struct __cppobj TridentChannelingEnchant : Enchant
{
};

```

### `TerrainBurstReactionComponent`
```
struct __cppobj __attribute__((aligned(8))) TerrainBurstReactionComponent : LabTableReactionComponent
{
  int mData;
  Vec3 mDims;
  Vec3 mDirRange;
  int mCount;
  bool mDirOneWay;
};

```

### `TallGrass`
```
struct __cppobj TallGrass : BushBlock
{
};

```

### `TntBlock`
```
struct __cppobj TntBlock : BlockLegacy
{
};

```

### `TorchBlock`
```
struct __cppobj TorchBlock : BlockLegacy
{
};

```

### `TrapDoorBlock`
```
struct __cppobj TrapDoorBlock : BlockLegacy
{
};

```

### `ThinFenceBlock`
```
struct __cppobj __attribute__((aligned(8))) ThinFenceBlock : BlockLegacy
{
  const bool mDropsResources;
  const bool mCanBeUsedInCommands;
};

```

### `TripWireHookBlock`
```
struct __cppobj TripWireHookBlock : BlockLegacy
{
};

```

### `TripWireBlock`
```
struct __cppobj TripWireBlock : BlockLegacy
{
};

```

### `TurtleEggBlock`
```
struct __cppobj __attribute__((aligned(8))) TurtleEggBlock : BlockLegacy
{
  float mShapeOffset;
};

```

### `TheEndGenerator`
```
struct __cppobj TheEndGenerator : ChunkSource, WorldGenerator
{
  PerlinNoisePtr mLPerlinNoise1;
  PerlinNoisePtr mLPerlinNoise2;
  PerlinNoisePtr mPerlinNoise1;
  SimplexNoisePtr mIslandNoise;
  ThreadLocal<TheEndGenerator::ThreadData> generatorHelpersPool;
  EndCityFeature mEndCityFeature;
};

```

### `TreeFeature:272`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(2))) TreeFeature:272 : Feature
{
  int mTrunkType;
  int mLeafType;
  bool mAddJungleFeatures;
  bool mHasBeehive;
};

```

### `TreeFeature:288`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) TreeFeature:288 : Feature
{
  int mTrunkType;
  int mLeafType;
  bool mAddJungleFeatures;
  bool mHasBeehive;
};

```

### `TheEndGenerator::ThreadData`
```
struct TheEndGenerator::ThreadData
{
  std::array<long,32768> blockBuffer;
};

```

### `ThreadLocal<TheEndGenerator::ThreadData>`
```
struct ThreadLocal<TheEndGenerator::ThreadData>
{
  ThreadLocal<TheEndGenerator::ThreadData>::Creator mCreator;
  ThreadLocal<TheEndGenerator::ThreadData>::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<TheEndGenerator::ThreadData>::Creator`
```
typedef std::function<std::unique_ptr<TheEndGenerator::ThreadData> ()> ThreadLocal<TheEndGenerator::ThreadData>::Creator;

```

### `ThreadLocal<TheEndGenerator::ThreadData>::Pool`
```
typedef std::vector<std::unique_ptr<TheEndGenerator::ThreadData>> ThreadLocal<TheEndGenerator::ThreadData>::Pool;

```

### `TickingArea`
```
struct __cppobj TickingArea : ITickingArea
{
  mce::UUID mUID;
  std::string mName;
  ActorUniqueID mEntityId;
  float mMaxDistToPlayers;
  bool mAlwaysActive;
  bool mEntityFound;
  bool mSizeChanged;
  bool mRemoved;
  Vec3 mLastChunkUpdatePos;
  Vec3 mLastPos;
  uint32_t mLastRadius;
  GridArea<std::shared_ptr<LevelChunk> >::AddCallback mAddCallback;
  ChunkViewSource mChunkSource;
  BlockSource mBlockSource;
  TickingAreaView mView;
};

```

### `TransporterComponent`
```
struct __cppobj TransporterComponent : BaseCircuitComponent:480
{
  int mNextStrength;
};

```

### `TestServerCommands`
```
struct TestServerCommands
{
  __int8 gap0[1];
};

```

### `TagCommand`
```
struct __cppobj TagCommand : Command:240
{
  TagCommand::Action mAction;
  WildcardActorSelector mSelector;
  std::string mTagString;
};

```

### `TeleportCommand`
```
struct __cppobj __attribute__((aligned(2))) TeleportCommand : Command
{
  ActorSelector mTargets;
  ActorSelector mDestinationEntity;
  CommandPositionFloat mDestinationPos;
  ActorSelector mFacingEntity;
  CommandPositionFloat mFacingPos;
  RelativeFloat mYRot;
  RelativeFloat mXRot;
  TeleportCommand::FacingResult mHaveFacing;
  bool mDestinationIsPosition;
  bool mFacingIsPosition;
  bool mCheckForBlocks;
};

```

### `TellCommand`
```
struct __cppobj TellCommand : MessagingCommand
{
  PlayerSelector mTargets;
  CommandMessage mMessage;
};

```

### `TellRawCommand`
```
struct __cppobj TellRawCommand : MessagingCommand
{
  PlayerSelector mTargets;
  Json::Value mRawText;
};

```

### `TestForBlockCommand`
```
struct __cppobj __attribute__((aligned(8))) TestForBlockCommand : Command
{
  CommandPosition mPosition;
  const Block *mBlock;
  int mData;
};

```

### `TestForBlocksCommand`
```
struct __cppobj __attribute__((aligned(8))) TestForBlocksCommand : Command
{
  CommandPosition mBegin;
  CommandPosition mEnd;
  CommandPosition mDestination;
  TestForBlocksCommand::Mode mMode;
};

```

### `TestForCommand`
```
struct __cppobj TestForCommand : Command
{
  ActorSelector mTargets;
};

```

### `TickingAreaCommand`
```
struct __cppobj __attribute__((aligned(8))) TickingAreaCommand : Command
{
  TickingAreaCommand::Mode mMode;
  TickingAreaCommand::AddAreaType mAddAreaType;
  TickingAreaCommand::TargetDimensions mTargetDimensions;
  CommandPosition mPosition;
  CommandPosition mMax;
  std::string mName;
  int mRadius;
};

```

### `TimeCommand`
```
struct __cppobj TimeCommand : Command
{
  TimeCommand::Mode mMode;
  TimeCommand::Query mQuery;
  TimeCommand::TimeSpec mSpec;
  int mValue;
};

```

### `TitleCommand`
```
struct __cppobj __attribute__((aligned(8))) TitleCommand : MessagingCommand
{
  TitleCommand::Mode mMode;
  PlayerSelector mTargets;
  CommandMessage mMessage;
  int mFadeIn;
  int mStay;
  int mFadeOut;
};

```

### `TitleRawCommand`
```
struct __cppobj __attribute__((aligned(8))) TitleRawCommand : MessagingCommand
{
  TitleRawCommand::Mode mMode;
  PlayerSelector mTargets;
  Json::Value mMessage;
  int mFadeIn;
  int mStay;
  int mFadeOut;
};

```

### `ToggleDownfallCommand`
```
struct __cppobj ToggleDownfallCommand : Command
{
};

```

### `TradeIngredientContainerController`
```
struct __cppobj TradeIngredientContainerController : ContainerController
{
  ItemStack mItem;
};

```

### `TradeResultContainerController`
```
struct __cppobj TradeResultContainerController : ContainerController
{
};

```

### `TropicalFishInfo`
```
struct TropicalFishInfo
{
  int mColor;
  int mColor2;
  int mVariant;
  int mMarkVariant;
  std::string mName;
};

```

### `TickingAreaView`
```
struct __cppobj __attribute__((aligned(8))) TickingAreaView : ITickingAreaView
{
  ChunkViewSource mTickingArea;
  bool mDoneLoading;
};

```

### `ThreadLocal<std::string >`
```
struct ThreadLocal<std::string >
{
  ThreadLocal<std::string >::Creator mCreator;
  ThreadLocal<std::string >::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<std::string >::Creator`
```
typedef std::function<std::unique_ptr<std::string> ()> ThreadLocal<std::string >::Creator;

```

### `ThreadLocal<std::string >::Pool`
```
typedef std::vector<std::unique_ptr<std::string>> ThreadLocal<std::string >::Pool;

```

### `tm_unz_s`
```
struct tm_unz_s
{
  uInt tm_sec;
  uInt tm_min;
  uInt tm_hour;
  uInt tm_mday;
  uInt tm_mon;
  uInt tm_year;
};

```

### `tm_zip_s`
```
struct tm_zip_s
{
  uInt tm_sec;
  uInt tm_min;
  uInt tm_hour;
  uInt tm_mday;
  uInt tm_mon;
  uInt tm_year;
};

```

### `ThreadLocal<BackgroundWorker *>`
```
struct ThreadLocal<BackgroundWorker *>
{
  ThreadLocal<BackgroundWorker *>::Creator mCreator;
  ThreadLocal<BackgroundWorker *>::Pool mPool;
  Bedrock::Threading::Mutex mCreatorLock;
  bool mInitialized;
  pthread_key_t mKey;
};

```

### `ThreadLocal<BackgroundWorker *>::Creator`
```
typedef std::function<std::unique_ptr<BackgroundWorker *> ()> ThreadLocal<BackgroundWorker *>::Creator;

```

### `ThreadLocal<BackgroundWorker *>::Pool`
```
typedef std::vector<std::unique_ptr<BackgroundWorker *>> ThreadLocal<BackgroundWorker *>::Pool;

```

