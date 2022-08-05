# D
### `DimensionType`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | runtimeID


### `DedicatedServer`
Offset | Type | Name
-|-|-|-
0 | (8) `IMinecraftApp` | baseclass_0
8 | (8) `BedrockEngine::AppIsland` | baseclass_8
16 | (8) `AppPlatform *` | mPlatform
24 | (8) `Minecraft *` | mMinecraft
32 | (8) `Unique<Automation::AutomationClient>` | mAutomationClient
40 | (8) `std::unique_ptr<ServerInstanceEventCoordinator>` | mServerInstanceEventCoordinator
48 | (1) `std::atomic<bool>` | mWantsToQuit
56 | (8) `std::unique_ptr<ConsoleInputReader>` | mConsoleInputReader
64 | (8) `std::unique_ptr<AppConfigs>` | mAppConfig
72 | (8) `std::unique_ptr<IGameModuleShared>` | mGameModule


### `DebugLogScope`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mPopScope


### `DirtyTicksCounter`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | totalTime
4 | (4) `int` | lastChange


### `DataTypeMap::typeFor<long>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<int>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DamageOverTimeComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mHurtValue
4 | (4) `int` | mDamageTimeInterval
8 | (4) `int` | mDamageTime


### `DanceComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<DanceComponentListener>` | mListener


### `DespawnComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `DwellerComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mCanFindPOI
1 | (1) `bool` | mCanMigrate
2 | (1) `bool` | mHasJoinedDwelling
3 | (1) `bool` | mFixUpRole
4 | (1) `bool` | mRewardPlayersOnFirstFounding
8 | (40) `HashedString` | mPreferredProfession
48 | (4) `int` | mFirstFoundingReward
52 | (4) `int` | mUpdateIntervalVariant
56 | (8) `size_t` | mDwellingUpdateInterval
64 | (8) `size_t` | mUpdateIntervalBase
72 | (4) `float` | mDwellingBoundsTolerance
76 | (4) `DwellerComponent::DwellingType` | mType
80 | (4) `DwellerRole` | mRole
88 | (16) `mce::UUID` | mDwellingUniqueID


### `DefinitionTrigger`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mType
32 | (32) `std::string` | mTarget
64 | (64) `ActorFilterGroup` | mFilter


### `DisconnectPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `bool` | mSkipMessage
40 | (32) `std::string` | mMessage


### `DefaultDataLoadHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `DataLoadHelper` | baseclass_0


### `DataLoadHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$DataLoadHelper


### `Description`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Description


### `DamageSensorDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<DamageSensorTrigger>` | mTriggers


### `DistanceSortedActor`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (4) `float` | mDistanceSquared


### `DistanceSortedActorList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<DistanceSortedActor>` | baseclass_0


### `DataTypeMap::typeFor<short>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<float>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<signed char>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<Vec3>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DefintionDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$DefintionDescription


### `DefinitionInstanceGroup`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<IDefinitionInstance>>` | mDefinitionList
24 | (56) `std::unordered_map<std::string,std::shared_ptr<IDefinitionInstance>>` | mDefinitionMap
80 | (56) `std::unordered_map<unsigned short,std::string>` | mTypeIdToDefinitionName


### `DefinitionEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mProbability
8 | (64) `ActorFilterGroup` | mFilter
72 | (32) `std::string` | mName
104 | (4) `DefinitionEventType` | mType
112 | (24) `std::vector<std::string>` | mGroups
136 | (24) `std::vector<std::string>` | mRemoveGroups
160 | (24) `std::vector<DefinitionEvent>` | mChildren


### `DefinitionModifier`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mAddGroups
24 | (24) `std::vector<std::string>` | mRemoveGroups


### `DrinkPotionData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mPotionId
4 | (4) `float` | mChance
8 | (64) `ActorFilterGroup` | mFilter


### `DataTypeMap::typeFor<BlockPos>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DataTypeMap::typeFor<CompoundTag>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `DBStorageConfig`
Offset | Type | Name
-|-|-|-
0 | (8) `Scheduler *` | scheduler
8 | (32) `Core::HeapPathBuffer` | fullPath
40 | (32) `Core::HeapPathBuffer` | dbSubfolder
72 | (8) `const ContentIdentity *` | contentIdentity
80 | (8) `const IContentKeyProvider *` | keyProvider
88 | (16) `Shared<SaveTransactionManager>` | saveTransactionManager
104 | (8) `std::chrono::_V2::steady_clock::duration` | compactionInterval
112 | (16) `Shared<Core::FileStorageArea>` | storageArea
128 | (1) `bool` | enableCompactionListener
129 | (1) `bool` | enableSnapshots


### `DisplayObjective`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `ObjectiveSortOrder` | mSortOrder


### `DistanceConstraint`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mConstraintMass
4 | (12) `Vec3` | mConstraintAxis
16 | (4) `float` | mBias
20 | (1) `bool` | mShouldEnforce
24 | (4) `float` | mMassA
28 | (4) `float` | mMassB
32 | (4) `float` | mDesiredDistance


### `DenySameParentsVariantData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
4 | (4) `int` | mVariantRangeMin
8 | (4) `int` | mVariantRangeMax


### `DamageSensorTrigger`
Offset | Type | Name
-|-|-|-
0 | (128) `DefinitionTrigger` | mOnDamage
128 | (1) `bool` | mDealsDamage
132 | (4) `ActorDamageCause` | mCause
136 | (4) `float` | mDamageMultipler
144 | (32) `std::string` | mOnDamageSound


### `DefinitionEventLoader::loadEvent::$308FE320F1A5CE0A1A20921AD32B0459`
Offset | Type | Name
-|-|-|-
0 | (8) `DefinitionEvent *` | defEvent


### `DefinitionSerializer<AddRiderDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<AddRiderDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<AgeableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<AgeableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<AreaAttackDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<AreaAttackDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BoostableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BoostableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BossDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BossDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BreathableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BreathableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BreedableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BreedableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BribeableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BribeableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BurnsInDaylightDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BurnsInDaylightDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<DamageOverTimeDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<DamageOverTimeDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<DamageSensorDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<DamageSensorDefinition> > ()>::_Invoker_type` | _M_invoker


### `DamageSensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDamageAmount
4 | (1) `bool` | mDamageIsFatal
8 | (4) `int` | mDamageCause
16 | (24) `std::vector<DamageSensorTrigger>` | mTriggers
40 | (4) `float` | mDamageMultipler


### `DefinitionSerializer<EntitySensorDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<EntitySensorDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<EnvironmentSensorDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<EnvironmentSensorDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<EquippableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<EquippableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<ExperienceRewardDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<ExperienceRewardDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<ExplodeDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<ExplodeDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<FlockingDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<FlockingDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<GeneticsDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<GeneticsDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<GiveableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<GiveableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<HealableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<HealableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<HomeDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<HomeDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<HurtOnConditionDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<HurtOnConditionDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<InsomniaDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<InsomniaDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<InteractDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<InteractDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<HopperDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<HopperDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<LeashableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<LeashableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<LegacyTradeableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<LegacyTradeableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<LookAtDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<LookAtDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<MobEffectDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<MobEffectDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<MountTameableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<MountTameableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<PeekDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<PeekDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<PhysicsDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<PhysicsDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<RailMovementDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<RailMovementDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<ScaffoldingClimberDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<ScaffoldingClimberDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<ScaleByAgeDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<ScaleByAgeDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<SchedulerDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<SchedulerDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BlockBreakSensorDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BlockBreakSensorDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<ShareableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<ShareableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<GrowsCropDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<GrowsCropDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BalloonDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BalloonDefinition> > ()>::_Invoker_type` | _M_invoker


### `DefinitionSerializer<BalloonableDefinition>::DefinitionInitializer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::shared_ptr<DefinitionInstanceTyped<BalloonableDefinition> > ()>::_Invoker_type` | _M_invoker


### `DiggerItem::BlockList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<const Block *>` | baseclass_0


### `DBStorage::DBStorageToken`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<int> *` | mRefCounter


### `DamageCondition`
Offset | Type | Name
-|-|-|-
0 | (64) `ActorFilterGroup` | mDamageFilters
64 | (32) `std::string` | mCause
96 | (4) `int` | mDamagePerTick


### `DBChunkStorageKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const ChunkPos` | pos
8 | (4) `const DimensionType` | id


### `DBChunkStorage::UpgradeFixHandler`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (LevelChunk &,BlockSource &)>::_Invoker_type` | _M_invoker


### `DataStructures::List<RakNet::SystemAddress>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::SystemAddress *` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DataStructures::List<RakNet::RakNetGUID>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakNetGUID *` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DataStructures::Queue<RakNet::RakPeer::RequestedConnectionStruct *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakPeer::RequestedConnectionStruct **` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::List<RakNet::RakNetSocket2 *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakNetSocket2 **` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DatagramSequenceNumberType`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | val


### `DatagramHeaderFormat`
Offset | Type | Name
-|-|-|-
0 | (4) `DatagramSequenceNumberType` | datagramNumber
4 | (4) `float` | AS
8 | (1) `bool` | isACK
9 | (1) `bool` | isNAK
10 | (1) `bool` | isPacketPair
11 | (1) `bool` | hasBAndAS
12 | (1) `bool` | isContinuousSend
13 | (1) `bool` | needsBAndAs
14 | (1) `bool` | isValid


### `DataStructures::RangeList<RakNet::uint24_t>`
Offset | Type | Name
-|-|-|-
0 | (16) `DataStructures::OrderedList<RakNet::uint24_t,DataStructures::RangeNode<RakNet::uint24_t>,&DataStructures::RangeNodeComp>` | ranges


### `DataStructures::OrderedList<RakNet::uint24_t,DataStructures::RangeNode<RakNet::uint24_t>,&DataStructures::RangeNodeComp>`
Offset | Type | Name
-|-|-|-
0 | (16) `DataStructures::List<DataStructures::RangeNode<RakNet::uint24_t> >` | orderedList


### `DataStructures::List<DataStructures::RangeNode<RakNet::uint24_t> >`
Offset | Type | Name
-|-|-|-
0 | (8) `DataStructures::RangeNode<RakNet::uint24_t> *` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>::HeapNode`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | weight
8 | (8) `RakNet::InternalPacket *` | data


### `DataStructures::Queue<HuffmanEncodingTreeNode *>`
Offset | Type | Name
-|-|-|-
0 | (8) `HuffmanEncodingTreeNode **` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::LinkedList<HuffmanEncodingTreeNode *>`
Offset | Type | Name
-|-|-|-
0 | (24) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>` | baseclass_0


### `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | list_size
8 | (8) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *` | root
16 | (8) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *` | position


### `DelayedDeleter<SubChunkBlockStorage>`
Offset | Type | Name
-|-|-|-
0 | (32) `DelayedDeleter<SubChunkBlockStorage>::EntryQueue` | mEntries
32 | (40) `Bedrock::Threading::Mutex` | mEntriesMutex


### `DelayedDeleter<SubChunkBlockStorage>::EntryQueue`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBlockStorage> >>` | c
24 | (1) `std::greater<std::pair<std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBlockStorage> > >` | comp


### `DelayedDeleter<SubChunkBrightnessStorage>`
Offset | Type | Name
-|-|-|-
0 | (32) `DelayedDeleter<SubChunkBrightnessStorage>::EntryQueue` | mEntries
32 | (40) `Bedrock::Threading::Mutex` | mEntriesMutex


### `DelayedDeleter<SubChunkBrightnessStorage>::EntryQueue`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBrightnessStorage> >>` | c
24 | (1) `std::greater<std::pair<std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBrightnessStorage> > >` | comp


### `DataStructures::List<RakNet::RakString::SharedString *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakString::SharedString **` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DimensionConversionData`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mOverworldSpawnPoint
12 | (4) `int` | mNetherScale


### `Dimension`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelListener` | baseclass_0
8 | (48) `SavedData` | baseclass_8
56 | (8) `Level *` | mLevel
64 | (2) `Height` | mSeaLevel
72 | (8) `std::unique_ptr<BlockSource>` | mBlockSource
80 | (28) `float[7]` | mMobsPerChunkSurface
108 | (28) `float[7]` | mMobsPerChunkUnderground
136 | (2) `BrightnessPair` | mDefaultBrightness
144 | (32) `std::string` | mName
176 | (4) `DimensionType` | mId
180 | (1) `bool` | mUltraWarm
181 | (1) `bool` | mHasCeiling
182 | (1) `bool` | mHasWeather
183 | (1) `bool` | mHasSkylight
184 | (1) `Brightness` | mSkyDarken
186 | (2) `Height` | mHeight
188 | (64) `float[16]` | mBrightnessRamp
256 | (8) `std::unique_ptr<BlockEventDispatcher>` | mDispatcher
264 | (8) `std::unique_ptr<TaskGroup>` | mTaskGroup
272 | (8) `std::unique_ptr<PostprocessingManager>` | mPostProcessingManager
280 | (8) `std::unique_ptr<ChunkSource>` | mChunkSource
288 | (8) `WorldGenerator *` | mWorldGenerator
296 | (8) `std::unique_ptr<Weather>` | mWeather
304 | (8) `std::unique_ptr<Seasons>` | mSeasons
312 | (8) `Unique<CircuitSystem>` | mCircuitSystem
320 | (4) `const int` | CIRCUIT_TICK_RATE
324 | (4) `int` | mCircuitSystemTickRate
328 | (56) `ActorMap` | mEntityIdLookup
384 | (56) `Dimension::ChunkPosToActorListMap` | mLimboEntities
440 | (24) `ActorList` | mEntitiesToMoveChunks
464 | (8) `Unique<TickingAreaList>` | mTickingAreaList
472 | (632) `LevelChunkGarbageCollector` | mLevelChunkGarbageCollector
1104 | (48) `std::set<ActorUniqueID>` | mWitherIDs
1152 | (8) `std::unique_ptr<RuntimeLightingManager>` | mRuntimeLightingManager
1160 | (8) `std::unique_ptr<LevelChunkBuilderData>` | mLevelChunkBuilderData
1168 | (8) `std::chrono::_V2::steady_clock::time_point` | mLastPruneTime
1176 | (8) `std::unique_ptr<ChunkBuildOrderPolicyBase>` | mChunkBuildOrderPolicy
1184 | (8) `Unique<VillageManager>` | mVillageManager
1192 | (24) `std::vector<NetworkIdentifierWithSubId>` | mTemporaryPlayerIds


### `Dimension::ChunkPosToActorListMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ChunkPos,std::vector<std::unique_ptr<CompoundTag>>>::_Hashtable` | _M_h


### `DataStructures::Queue<RakNet::BPSTracker::TimeAndValue2>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::BPSTracker::TimeAndValue2 *` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::RangeNode<RakNet::uint24_t>`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::uint24_t` | minIndex
4 | (4) `RakNet::uint24_t` | maxIndex


### `DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mapNodeKey
8 | (8) `RakNet::HuffmanEncodingTree *` | mapNodeData


### `DirectoryPackSource`
```
struct __cppobj DirectoryPackSource : PackSource
{
  Core::HeapPathBuffer mPath;
  PackType mPackType;
  PackOrigin mPackOrigin;
  bool mDiscovered;
  bool mIsRediscoverable;
  bool mIsDevDirectory;
  std::vector<std::unique_ptr<Pack>> mPacks;
  PackSourceReport mReport;
};

```

### `DedicatedServerCommands`
```
struct DedicatedServerCommands
{
  __int8 gap0[1];
};

```

### `DedicatedWSServerCommand`
```
struct __cppobj DedicatedWSServerCommand : Command
{
  CommandMessage mServer;
};

```

### `DwellerSystem`
```
struct __cppobj DwellerSystem : ITickingSystem
{
};

```

### `DamageOverTimeSystem`
```
struct __cppobj DamageOverTimeSystem : ITickingSystem
{
};

```

### `DanceSystem`
```
struct __cppobj DanceSystem : ITickingSystem
{
};

```

### `DespawnSystem`
```
struct __cppobj DespawnSystem : ITickingSystem
{
};

```

### `DeadBushFeature`
```
struct __cppobj DeadBushFeature : Feature
{
};

```

### `DesertWellFeature`
```
struct __cppobj DesertWellFeature : Feature
{
};

```

### `DoublePlantFeature`
```
struct __cppobj DoublePlantFeature : Feature
{
};

```

### `Direction`
```
struct Direction
{
  __int8 gap0[1];
};

```

### `DataItem2<long>`
```
struct __cppobj DataItem2<long> : DataItem
{
  __int64 mData;
};

```

### `DataItem`
```
struct __attribute__((aligned(4))) DataItem
{
  int (**_vptr$DataItem)(void);
  const DataItemType mType;
  const DataItem::ID mId;
  bool mDirty;
};

```

### `DefinitionInstanceTyped<LegacyTradeableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<LegacyTradeableDefinition> : IDefinitionInstance
{
  std::unique_ptr<LegacyTradeableDefinition> mDefinition;
};

```

### `DataItem2<int>`
```
struct __cppobj __attribute__((aligned(8))) DataItem2<int> : DataItem
{
  int mData;
};

```

### `DataTypeMap::copyFor<long>`
```
struct DataTypeMap::copyFor<long>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::neqFor<int>`
```
struct DataTypeMap::neqFor<int>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<int>`
```
struct DataTypeMap::copyFor<int>
{
  __int8 gap0[1];
};

```

### `DataItem2<std::string >`
```
struct __cppobj DataItem2<std::string > : DataItem
{
  std::string mData;
};

```

### `DataTypeMap::typeFor<std::string >`
```
struct DataTypeMap::typeFor<std::string >
{
  __int8 gap0[1];
};

```

### `DataItem2<signed char>`
```
struct __cppobj __attribute__((aligned(4))) DataItem2<signed char> : DataItem:104
{
  char mData;
};

```

### `DataTypeMap::neqFor<signed char>`
```
struct DataTypeMap::neqFor<signed char>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<signed char>`
```
struct DataTypeMap::copyFor<signed char>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::neqFor<std::string >`
```
struct DataTypeMap::neqFor<std::string >
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<std::string >`
```
struct DataTypeMap::copyFor<std::string >
{
  __int8 gap0[1];
};

```

### `DefinitionInstanceTyped<AgeableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<AgeableDefinition> : IDefinitionInstance
{
  std::unique_ptr<AgeableDefinition> mDefinition;
};

```

### `DataItem2<short>`
```
struct __cppobj DataItem2<short> : DataItem:112
{
  __int16 mData;
};

```

### `DataTypeMap::neqFor<short>`
```
struct DataTypeMap::neqFor<short>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<short>`
```
struct DataTypeMap::copyFor<short>
{
  __int8 gap0[1];
};

```

### `DanceComponentListener`
```
struct __cppobj __attribute__((aligned(8))) DanceComponentListener : LevelListener
{
  ActorUniqueID mOwnerID;
  float mListenDistance;
  Level *mLevel;
  Vec3 mSoundPos;
};

```

### `DespawnDescription`
```
struct __cppobj __attribute__((aligned(8))) DespawnDescription : ComponentDescription
{
  ActorFilterGroup mFilter;
  bool mRemoveChildActors;
};

```

### `DefinitionInstanceTyped<EnvironmentSensorDefinition>`
```
struct __cppobj DefinitionInstanceTyped<EnvironmentSensorDefinition> : IDefinitionInstance
{
  std::unique_ptr<EnvironmentSensorDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<GrowsCropDefinition>`
```
struct __cppobj DefinitionInstanceTyped<GrowsCropDefinition> : IDefinitionInstance
{
  std::unique_ptr<GrowsCropDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<HurtOnConditionDefinition>`
```
struct __cppobj DefinitionInstanceTyped<HurtOnConditionDefinition> : IDefinitionInstance
{
  std::unique_ptr<HurtOnConditionDefinition> mDefinition;
};

```

### `DamageConditionList`
```
typedef std::vector<DamageCondition> DamageConditionList;

```

### `DefinitionInstanceTyped<LeashableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<LeashableDefinition> : IDefinitionInstance
{
  std::unique_ptr<LeashableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<LookAtDefinition>`
```
struct __cppobj DefinitionInstanceTyped<LookAtDefinition> : IDefinitionInstance
{
  std::unique_ptr<LookAtDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<MountTameableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<MountTameableDefinition> : IDefinitionInstance
{
  std::unique_ptr<MountTameableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<PeekDefinition>`
```
struct __cppobj DefinitionInstanceTyped<PeekDefinition> : IDefinitionInstance
{
  std::unique_ptr<PeekDefinition> mDefinition;
};

```

### `DataItem2<float>`
```
struct __cppobj __attribute__((aligned(8))) DataItem2<float> : DataItem
{
  float mData;
};

```

### `DataTypeMap::neqFor<float>`
```
struct DataTypeMap::neqFor<float>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<float>`
```
struct DataTypeMap::copyFor<float>
{
  __int8 gap0[1];
};

```

### `DefinitionInstanceTyped<SchedulerDefinition>`
```
struct __cppobj DefinitionInstanceTyped<SchedulerDefinition> : IDefinitionInstance
{
  std::unique_ptr<SchedulerDefinition> mDefinition;
};

```

### `DoubleTag`
```
struct __cppobj DoubleTag : Tag
{
  double data;
};

```

### `detail::OptionTypeHelper<bool>::option_type`
```
typedef BoolOption detail::OptionTypeHelper<bool>::option_type;

```

### `detail::OptionTypeHelper<bool>`
```
struct detail::OptionTypeHelper<bool>
{
  __int8 gap0[1];
};

```

### `DateManager`
```
struct DateManager
{
  unsigned int mTimeScale;
  time_t mRealTime;
  time_t mTime;
  Bedrock::Threading::Mutex mScheduledCallbacksMutex;
  std::priority_queue<ScheduledCallback,std::vector<ScheduledCallback>,CompareScheduledCallback> mScheduledCallbacks;
};

```

### `DimensionMap`
```
typedef std::unordered_map<AutomaticID<Dimension,int>,std::unique_ptr<Dimension>> DimensionMap;

```

### `DefaultLookAngleDescription`
```
struct __cppobj __attribute__((aligned(8))) DefaultLookAngleDescription : PropertyDescription
{
  float mValue;
};

```

### `DyeableDescription`
```
struct __cppobj DyeableDescription : PropertyDescription
{
  std::string mInteractText;
};

```

### `DwellerDescription`
```
struct __cppobj __attribute__((aligned(8))) DwellerDescription : ComponentDescription
{
  std::string mType;
  std::string mRole;
  std::string mPreferredProfession;
  int mUpdateBase;
  int mUpdateVariant;
  int mFirstFoundingReward;
  float mDwellingBoundsTolerance;
  bool mCanFindPOI;
  bool mCanMigrate;
};

```

### `DynamicJumpControlDescription`
```
struct __cppobj DynamicJumpControlDescription : ComponentDescription
{
};

```

### `DispenserContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) DispenserContainerManagerModel : LevelContainerManagerModel
{
};

```

### `DropperContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) DropperContainerManagerModel : LevelContainerManagerModel
{
};

```

### `DevConsoleCommandOrigin`
```
struct __cppobj __attribute__((aligned(8))) DevConsoleCommandOrigin : CommandOrigin
{
  ActorUniqueID mPlayerId;
  Level *mLevel;
  NetworkIdentifier mSourceId;
  uint8_t mSourceSubId;
};

```

### `Detail::HashHelper64<std::string >`
```
struct Detail::HashHelper64<std::string >
{
  __int8 gap0[1];
};

```

### `DefinitionInstanceTyped<EquippableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<EquippableDefinition> : IDefinitionInstance
{
  std::unique_ptr<EquippableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<ExplodeDefinition>`
```
struct __cppobj DefinitionInstanceTyped<ExplodeDefinition> : IDefinitionInstance
{
  std::unique_ptr<ExplodeDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<HealableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<HealableDefinition> : IDefinitionInstance
{
  std::unique_ptr<HealableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<InteractDefinition>`
```
struct __cppobj DefinitionInstanceTyped<InteractDefinition> : IDefinitionInstance
{
  std::unique_ptr<InteractDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<DamageSensorDefinition>`
```
struct __cppobj DefinitionInstanceTyped<DamageSensorDefinition> : IDefinitionInstance
{
  std::unique_ptr<DamageSensorDefinition> mDefinition;
};

```

### `DataItem:112`
```
struct __attribute__((packed)) __attribute__((aligned(2))) DataItem:112
{
  int (**_vptr$DataItem)(void);
  const DataItemType mType;
  __attribute__((aligned(2))) const DataItem::ID mId;
  bool mDirty;
};

```

### `DataItem:104`
```
struct __attribute__((packed)) __attribute__((aligned(1))) DataItem:104
{
  int (**_vptr$DataItem)(void);
  const DataItemType mType;
  _BYTE gap9;
  const DataItem::ID mId;
  bool mDirty;
};

```

### `DataItem2<Vec3>`
```
struct __cppobj __attribute__((aligned(8))) DataItem2<Vec3> : DataItem
{
  Vec3 mData;
};

```

### `DefinitionInstanceTyped<BreedableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BreedableDefinition> : IDefinitionInstance
{
  std::unique_ptr<BreedableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<BribeableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BribeableDefinition> : IDefinitionInstance
{
  std::unique_ptr<BribeableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<ScaleByAgeDefinition>`
```
struct __cppobj DefinitionInstanceTyped<ScaleByAgeDefinition> : IDefinitionInstance
{
  std::unique_ptr<ScaleByAgeDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<AddRiderDefinition>`
```
struct __cppobj DefinitionInstanceTyped<AddRiderDefinition> : IDefinitionInstance
{
  std::unique_ptr<AddRiderDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<BalloonDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BalloonDefinition> : IDefinitionInstance
{
  std::unique_ptr<BalloonDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<BreathableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BreathableDefinition> : IDefinitionInstance
{
  std::unique_ptr<BreathableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<DamageOverTimeDefinition>`
```
struct __cppobj DefinitionInstanceTyped<DamageOverTimeDefinition> : IDefinitionInstance
{
  std::unique_ptr<DamageOverTimeDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<GeneticsDefinition>`
```
struct __cppobj DefinitionInstanceTyped<GeneticsDefinition> : IDefinitionInstance
{
  std::unique_ptr<GeneticsDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<HomeDefinition>`
```
struct __cppobj DefinitionInstanceTyped<HomeDefinition> : IDefinitionInstance
{
  std::unique_ptr<HomeDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<InsomniaDefinition>`
```
struct __cppobj DefinitionInstanceTyped<InsomniaDefinition> : IDefinitionInstance
{
  std::unique_ptr<InsomniaDefinition> mDefinition;
};

```

### `DamageOverTimeDefinition`
```
struct DamageOverTimeDefinition
{
  int mDamagePerHurt;
  float mTimeBetweenHurt;
};

```

### `DataItem2<BlockPos>`
```
struct __cppobj __attribute__((aligned(8))) DataItem2<BlockPos> : DataItem
{
  BlockPos mData;
};

```

### `DataTypeMap::copyFor<Vec3>`
```
struct DataTypeMap::copyFor<Vec3>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::neqFor<BlockPos>`
```
struct DataTypeMap::neqFor<BlockPos>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<BlockPos>`
```
struct DataTypeMap::copyFor<BlockPos>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::neqFor<long>`
```
struct DataTypeMap::neqFor<long>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::neqFor<Vec3>`
```
struct DataTypeMap::neqFor<Vec3>
{
  __int8 gap0[1];
};

```

### `Dolphin`
```
struct __cppobj __attribute__((aligned(8))) Dolphin : WaterAnimal
{
  int mBreatheCounter;
};

```

### `DragonFireball`
```
struct __cppobj DragonFireball : Fireball
{
};

```

### `DispenserBlockActor`
```
struct __cppobj __attribute__((aligned(8))) DispenserBlockActor : RandomizableBlockActorContainer
{
  ItemStack mItems[9];
  Random mRandom;
};

```

### `DropperBlockActor`
```
struct __cppobj DropperBlockActor : DispenserBlockActor
{
};

```

### `DolphinMoveControl`
```
struct __cppobj __attribute__((aligned(8))) DolphinMoveControl : MoveControl
{
  bool mBreaching;
};

```

### `DynamicJumpControl`
```
struct __cppobj DynamicJumpControl : JumpControl
{
};

```

### `Degree`
```
typedef mce::Degree Degree;

```

### `DataItem2<CompoundTag>`
```
struct __cppobj DataItem2<CompoundTag> : DataItem
{
  CompoundTag mData;
};

```

### `DataTypeMap::neqFor<CompoundTag>`
```
struct DataTypeMap::neqFor<CompoundTag>
{
  __int8 gap0[1];
};

```

### `DataTypeMap::copyFor<CompoundTag>`
```
struct DataTypeMap::copyFor<CompoundTag>
{
  __int8 gap0[1];
};

```

### `DelayedAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) DelayedAttackGoal : MeleeAttackGoal
{
  int mAttackDuration;
  int mHitDelay;
  ActorFlags mAttackFlag;
  int mCooldownTicks;
  LevelSoundEvent mAttackSound;
};

```

### `DefendVillageTargetGoal`
```
struct __cppobj DefendVillageTargetGoal : TargetGoal
{
  Weak<VillageLegacy> mVillageLegacy;
  Mob *mPotentialTarget;
};

```

### `DoorInteractGoal`
```
struct __cppobj DoorInteractGoal : Goal:96
{
  BlockPos mDoorPos;
  const DoorBlock *mDoorBlock;
  bool mInitialToggledState;
  bool mMobOversized;
  bool mExited;
  float mDoorOpenDirX;
  float mDoorOpenDirZ;
  Direction::Type mEnterDirection;
  Direction::Type mExitDirection;
  Mob *mMob;
};

```

### `DrinkPotionGoal`
```
struct __cppobj DrinkPotionGoal : Goal
{
  Mob *mMob;
  const float mWalkSpeedModifier;
  const std::vector<DrinkPotionData> mDrinkPotionData;
  int mThrottleCooldown;
  int mUsingTime;
  AttributeModifier mSpeedAttributeModifier;
};

```

### `DefendTrustedTargetGoal`
```
struct __cppobj DefendTrustedTargetGoal : NearestAttackableTargetGoal
{
  LevelSoundEvent mAggroSound;
  const DefinitionTrigger mOnStartEvent;
};

```

### `DragonHoldingPatternGoal`
```
struct __cppobj DragonHoldingPatternGoal : Goal
{
  Unique<Path> mCurrentPath;
  bool mClockwise;
  EnderDragon *mDragon;
};

```

### `DragonLandingGoal`
```
struct __cppobj __attribute__((aligned(8))) DragonLandingGoal : Goal
{
  EnderDragon *mDragon;
  Unique<Path> mCurrentPath;
  bool mDone;
};

```

### `DragonScanningGoal`
```
struct __cppobj __attribute__((aligned(8))) DragonScanningGoal : Goal
{
  EnderDragon *mDragon;
  float mScanTime;
};

```

### `DragonFlamingGoal`
```
struct __cppobj DragonFlamingGoal : Goal
{
  EnderDragon *mDragon;
  int mAttackingTicks;
  int mFlameTicks;
};

```

### `DragonTakeoffGoal`
```
struct __cppobj DragonTakeoffGoal : Goal:96
{
  bool mFirstTick;
  Unique<Path> mCurrentPath;
  EnderDragon *mDragon;
};

```

### `DragonChargePlayerGoal`
```
struct __cppobj __attribute__((aligned(8))) DragonChargePlayerGoal : Goal
{
  EnderDragon *mDragon;
  int mTimeSinceCharge;
};

```

### `DragonStrafePlayerGoal`
```
struct __cppobj DragonStrafePlayerGoal : Goal
{
  EnderDragon *mDragon;
  Unique<Path> mCurrentPath;
  int mFireballCharge;
  bool mClockwise;
  bool mDone;
  Actor *mAttackTarget;
};

```

### `DragonDeathGoal`
```
struct __cppobj __attribute__((aligned(8))) DragonDeathGoal : Goal
{
  EnderDragon *mDragon;
  int mTime;
};

```

### `DropItemForGoal`
```
struct __cppobj __attribute__((aligned(8))) DropItemForGoal : BaseMoveToBlockGoal
{
  ActorUniqueID mDropForID;
  const DefinitionTrigger mOnDropAttempt;
  const float mDropItemChance;
  std::string mLootTable;
  FloatRange mTimeOfDayRange;
  bool mHasDroppedItem;
  ActorFilterGroup mTargetFilter;
  const float mPreferredSqDistance;
  const float mTargetRange;
  int mCooldownRemaining;
};

```

### `DebugRenderer`
```
struct DebugRenderer
{
  __int8 gap0[1];
};

```

### `DoorBlock`
```
struct __cppobj __attribute__((aligned(8))) DoorBlock : BlockLegacy
{
  DoorBlock::DoorType mType;
};

```

### `DefinitionInstanceTyped<ShareableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<ShareableDefinition> : IDefinitionInstance
{
  std::unique_ptr<ShareableDefinition> mDefinition;
};

```

### `DefaultEmptyActorAnimationPlayer`
```
struct __cppobj DefaultEmptyActorAnimationPlayer : ActorAnimationPlayer
{
};

```

### `DouseFireSubcomponent`
```
struct __cppobj DouseFireSubcomponent : OnHitSubcomponent
{
};

```

### `DyePowderItem`
```
struct __cppobj DyePowderItem : FertilizerItem
{
  TextureAtlasItem m_uvTextureItem;
};

```

### `DoorItem`
```
struct __cppobj __attribute__((aligned(8))) DoorItem : Item
{
  DoorBlock::DoorType mType;
};

```

### `DiggingEnchant`
```
struct __cppobj DiggingEnchant : Enchant
{
};

```

### `DaylightDetectorBlockActor`
```
struct __cppobj DaylightDetectorBlockActor : BlockActor
{
};

```

### `DaylightDetectorBlock`
```
struct __cppobj __attribute__((aligned(8))) DaylightDetectorBlock : ActorBlock
{
  bool mIsInverted;
};

```

### `DefaultMobSpawner`
```
struct __cppobj DefaultMobSpawner : BaseMobSpawner
{
  MobSpawnerBlockActor *mOwner;
};

```

### `DirtBlock`
```
struct __cppobj DirtBlock : BlockLegacy
{
};

```

### `DispenserBlock`
```
struct __cppobj DispenserBlock : ActorBlock
{
};

```

### `DetectorRailBlock`
```
struct __cppobj __attribute__((aligned(8))) DetectorRailBlock : BaseRailBlock
{
};

```

### `DeadBush`
```
struct __cppobj DeadBush : BushBlock
{
};

```

### `DragonEggBlock`
```
struct __cppobj DragonEggBlock : HeavyBlock
{
};

```

### `DropperBlock`
```
struct __cppobj DropperBlock : DispenserBlock
{
};

```

### `DoublePlantBlock`
```
struct __cppobj __attribute__((aligned(8))) DoublePlantBlock : BushBlock
{
  AABB mBottomVisualShape;
};

```

### `DriedKelpBlock`
```
struct __cppobj DriedKelpBlock : BlockLegacy
{
};

```

### `Dimension::ActorTagList`
```
typedef std::vector<std::unique_ptr<CompoundTag>> Dimension::ActorTagList;

```

### `DesertPyramidPiece`
```
struct __cppobj __attribute__((aligned(8))) DesertPyramidPiece : ScatteredFeaturePiece
{
  bool mHasPlacedChest[4];
};

```

### `DBStorage`
```
struct __cppobj DBStorage : LevelStorage
{
  Unique<DBStorageEnvironmentChain> mEnvChain;
  Unique<leveldb::Cache> mCache;
  Unique<const leveldb::FilterPolicy> mFilterPolicy;
  Unique<leveldb::Compressor> mCompressor;
  Unique<leveldb::Compressor> mLegacyCompressor;
  Unique<DBStorage::Options> mOptions;
  Unique<leveldb::DecompressAllocator> mDecompressAllocator;
  Unique<leveldb::DB> mDb;
  Unique<TaskGroup> mIOTaskGroup;
  Unique<TaskGroup> mCompactionTaskGroup;
  Bedrock::Threading::IAsyncResult<void>::Handle mCompactionTask;
  Core::LevelStorageResult mState;
  Core::HeapPathBuffer mFullPath;
  Core::HeapPathBuffer mDbPath;
  Bedrock::Threading::Mutex mCompactionMutex;
  std::chrono::_V2::steady_clock::time_point mLastCompactionStartTime;
  std::chrono::_V2::steady_clock::duration mCompactionInterval;
  std::atomic<bool> mAllowFlush;
  std::atomic<bool> mSavingInProgress;
  std::atomic<bool> mSnapshotInProgress;
  std::atomic<bool> mShutdownStarted;
  std::atomic<bool> mShutdownDone;
  std::atomic<int> mOutstandingJobs;
  Shared<SaveTransactionManager> msptSaveTransactionManager;
  CriticalSyncSaveCallback mCriticalSyncSaveCallback;
  CompactionCallback mExternallyRegisteredCompactionCallback;
  SmallSet<DBChunkStorage *> mChunkStorages;
  std::vector<std::unique_ptr<LevelStorageObserver>> mObservers;
  std::atomic<bool> mDestructorInProgress;
  bool mForceCorrupt;
  std::map<std::string,DBStorage::PendingWrite> mPendingMap;
  Bedrock::Threading::ConditionVariable mWaitingPendingWrites;
  Bedrock::Threading::SharedMutex mPendingMapLock;
};

```

### `DefinitionInstanceTyped<BalloonableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BalloonableDefinition> : IDefinitionInstance
{
  std::unique_ptr<BalloonableDefinition> mDefinition;
};

```

### `DefinitionInstanceTyped<BoostableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BoostableDefinition> : IDefinitionInstance
{
  std::unique_ptr<BoostableDefinition> mDefinition;
};

```

### `DanceDescription`
```
struct __cppobj __attribute__((aligned(8))) DanceDescription : ComponentDescription
{
  float mListenDistance;
};

```

### `DefinitionInstanceTyped<GiveableDefinition>`
```
struct __cppobj DefinitionInstanceTyped<GiveableDefinition> : IDefinitionInstance
{
  std::unique_ptr<GiveableDefinition> mDefinition;
};

```

### `DirectoryPackAccessStrategy`
```
struct __cppobj __attribute__((aligned(8))) DirectoryPackAccessStrategy : PackAccessStrategy
{
  std::string mPackName;
  ResourceLocation mPackLocation;
  Core::HeapPathBuffer mPackPath;
  bool mRecurse;
};

```

### `DirectoryPackWithEncryptionAccessStrategy`
```
struct __cppobj DirectoryPackWithEncryptionAccessStrategy : PackAccessStrategy
{
  std::string mPackName;
  ResourceLocation mPackLocation;
  Core::HeapPathBuffer mPackPath;
  ResourceLocation mBlobLocation;
  mce::UUID mPackId;
  const IContentKeyProvider *mKeyProvider;
  std::unique_ptr<PackAccessStrategy> mEncryptedBlobAccessStrategy;
};

```

### `DayLockCommand`
```
struct __cppobj __attribute__((aligned(2))) DayLockCommand : Command:240
{
  bool mLock;
};

```

### `DeOpCommand`
```
struct __cppobj DeOpCommand : ServerCommand
{
  PlayerSelector mTargets;
};

```

### `DifficultyCommand`
```
struct __cppobj DifficultyCommand : Command
{
  Difficulty mDifficulty;
  int mId;
};

```

### `DefinitionEventLoader`
```
struct DefinitionEventLoader
{
  __int8 gap0[1];
};

```

### `DefinitionSerializer<AddRiderDefinition>`
```
struct __cppobj DefinitionSerializer<AddRiderDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<AddRiderDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<AddRiderDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent> : DefinitionInstanceTyped<AddRiderDefinition>
{
};

```

### `DefinitionSerializer<AgeableDefinition>`
```
struct __cppobj DefinitionSerializer<AgeableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<AgeableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<AgeableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent> : DefinitionInstanceTyped<AgeableDefinition>
{
};

```

### `DefinitionSerializer<AreaAttackDefinition>`
```
struct __cppobj DefinitionSerializer<AreaAttackDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<AreaAttackDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<AreaAttackDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<AreaAttackDefinition>`
```
struct __cppobj DefinitionInstanceTyped<AreaAttackDefinition> : IDefinitionInstance
{
  std::unique_ptr<AreaAttackDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent> : DefinitionInstanceTyped<AreaAttackDefinition>
{
};

```

### `DefinitionSerializer<BoostableDefinition>`
```
struct __cppobj DefinitionSerializer<BoostableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BoostableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BoostableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent> : DefinitionInstanceTyped<BoostableDefinition>
{
};

```

### `DefinitionSerializer<BossDefinition>`
```
struct __cppobj DefinitionSerializer<BossDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BossDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BossDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<BossDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BossDefinition> : IDefinitionInstance
{
  std::unique_ptr<BossDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,BossDefinition,BossComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BossDefinition,BossComponent> : DefinitionInstanceTyped<BossDefinition>
{
};

```

### `DefinitionSerializer<BreathableDefinition>`
```
struct __cppobj DefinitionSerializer<BreathableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BreathableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BreathableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent> : DefinitionInstanceTyped<BreathableDefinition>
{
};

```

### `DefinitionSerializer<BreedableDefinition>`
```
struct __cppobj DefinitionSerializer<BreedableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BreedableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BreedableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent> : DefinitionInstanceTyped<BreedableDefinition>
{
};

```

### `DefinitionSerializer<BribeableDefinition>`
```
struct __cppobj DefinitionSerializer<BribeableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BribeableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BribeableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent> : DefinitionInstanceTyped<BribeableDefinition>
{
};

```

### `DefinitionSerializer<BurnsInDaylightDefinition>`
```
struct __cppobj DefinitionSerializer<BurnsInDaylightDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BurnsInDaylightDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BurnsInDaylightDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<BurnsInDaylightDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BurnsInDaylightDefinition> : IDefinitionInstance
{
  std::unique_ptr<BurnsInDaylightDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >`
```
struct __cppobj DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > : DefinitionInstanceTyped<BurnsInDaylightDefinition>
{
};

```

### `DefinitionSerializer<DamageOverTimeDefinition>`
```
struct __cppobj DefinitionSerializer<DamageOverTimeDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<DamageOverTimeDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<DamageOverTimeDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent> : DefinitionInstanceTyped<DamageOverTimeDefinition>
{
};

```

### `DefinitionSerializer<DamageSensorDefinition>`
```
struct __cppobj DefinitionSerializer<DamageSensorDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<DamageSensorDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<DamageSensorDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent> : DefinitionInstanceTyped<DamageSensorDefinition>
{
};

```

### `DefinitionSerializer<EntitySensorDefinition>`
```
struct __cppobj DefinitionSerializer<EntitySensorDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<EntitySensorDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<EntitySensorDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<EntitySensorDefinition>`
```
struct __cppobj DefinitionInstanceTyped<EntitySensorDefinition> : IDefinitionInstance
{
  std::unique_ptr<EntitySensorDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent> : DefinitionInstanceTyped<EntitySensorDefinition>
{
};

```

### `DefinitionSerializer<EnvironmentSensorDefinition>`
```
struct __cppobj DefinitionSerializer<EnvironmentSensorDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<EnvironmentSensorDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<EnvironmentSensorDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >`
```
struct __cppobj DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > : DefinitionInstanceTyped<EnvironmentSensorDefinition>
{
};

```

### `DefinitionSerializer<EquippableDefinition>`
```
struct __cppobj DefinitionSerializer<EquippableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<EquippableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<EquippableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent> : DefinitionInstanceTyped<EquippableDefinition>
{
};

```

### `DefinitionSerializer<ExperienceRewardDefinition>`
```
struct __cppobj DefinitionSerializer<ExperienceRewardDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<ExperienceRewardDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<ExperienceRewardDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<ExperienceRewardDefinition>`
```
struct __cppobj DefinitionInstanceTyped<ExperienceRewardDefinition> : IDefinitionInstance
{
  std::unique_ptr<ExperienceRewardDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent> : DefinitionInstanceTyped<ExperienceRewardDefinition>
{
};

```

### `DefinitionSerializer<ExplodeDefinition>`
```
struct __cppobj DefinitionSerializer<ExplodeDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<ExplodeDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<ExplodeDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent> : DefinitionInstanceTyped<ExplodeDefinition>
{
};

```

### `DefinitionSerializer<FlockingDefinition>`
```
struct __cppobj DefinitionSerializer<FlockingDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<FlockingDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<FlockingDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<FlockingDefinition>`
```
struct __cppobj DefinitionInstanceTyped<FlockingDefinition> : IDefinitionInstance
{
  std::unique_ptr<FlockingDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent> : DefinitionInstanceTyped<FlockingDefinition>
{
};

```

### `DefinitionSerializer<GeneticsDefinition>`
```
struct __cppobj DefinitionSerializer<GeneticsDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<GeneticsDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<GeneticsDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent> : DefinitionInstanceTyped<GeneticsDefinition>
{
};

```

### `DefinitionSerializer<GiveableDefinition>`
```
struct __cppobj DefinitionSerializer<GiveableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<GiveableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<GiveableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent> : DefinitionInstanceTyped<GiveableDefinition>
{
};

```

### `DefinitionSerializer<HealableDefinition>`
```
struct __cppobj DefinitionSerializer<HealableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<HealableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<HealableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent> : DefinitionInstanceTyped<HealableDefinition>
{
};

```

### `DefinitionSerializer<HomeDefinition>`
```
struct __cppobj DefinitionSerializer<HomeDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<HomeDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<HomeDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent> : DefinitionInstanceTyped<HomeDefinition>
{
};

```

### `DefinitionSerializer<HurtOnConditionDefinition>`
```
struct __cppobj DefinitionSerializer<HurtOnConditionDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<HurtOnConditionDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<HurtOnConditionDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent> : DefinitionInstanceTyped<HurtOnConditionDefinition>
{
};

```

### `DefinitionSerializer<InsomniaDefinition>`
```
struct __cppobj DefinitionSerializer<InsomniaDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<InsomniaDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<InsomniaDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent> : DefinitionInstanceTyped<InsomniaDefinition>
{
};

```

### `DefinitionSerializer<InteractDefinition>`
```
struct __cppobj DefinitionSerializer<InteractDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<InteractDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<InteractDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent> : DefinitionInstanceTyped<InteractDefinition>
{
};

```

### `DefinitionSerializer<HopperDefinition>`
```
struct __cppobj DefinitionSerializer<HopperDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<HopperDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<HopperDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<HopperDefinition>`
```
struct __cppobj DefinitionInstanceTyped<HopperDefinition> : IDefinitionInstance
{
  std::unique_ptr<HopperDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent> : DefinitionInstanceTyped<HopperDefinition>
{
};

```

### `DefinitionSerializer<LeashableDefinition>`
```
struct __cppobj DefinitionSerializer<LeashableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<LeashableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<LeashableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent> : DefinitionInstanceTyped<LeashableDefinition>
{
};

```

### `DefinitionSerializer<LegacyTradeableDefinition>`
```
struct __cppobj DefinitionSerializer<LegacyTradeableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<LegacyTradeableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<LegacyTradeableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent> : DefinitionInstanceTyped<LegacyTradeableDefinition>
{
};

```

### `DefinitionSerializer<LookAtDefinition>`
```
struct __cppobj DefinitionSerializer<LookAtDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<LookAtDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<LookAtDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent> : DefinitionInstanceTyped<LookAtDefinition>
{
};

```

### `DefinitionSerializer<MobEffectDefinition>`
```
struct __cppobj DefinitionSerializer<MobEffectDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<MobEffectDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<MobEffectDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<MobEffectDefinition>`
```
struct __cppobj DefinitionInstanceTyped<MobEffectDefinition> : IDefinitionInstance
{
  std::unique_ptr<MobEffectDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent> : DefinitionInstanceTyped<MobEffectDefinition>
{
};

```

### `DefinitionSerializer<MountTameableDefinition>`
```
struct __cppobj DefinitionSerializer<MountTameableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<MountTameableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<MountTameableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent> : DefinitionInstanceTyped<MountTameableDefinition>
{
};

```

### `DefinitionSerializer<PeekDefinition>`
```
struct __cppobj DefinitionSerializer<PeekDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<PeekDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<PeekDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent> : DefinitionInstanceTyped<PeekDefinition>
{
};

```

### `DefinitionSerializer<PhysicsDefinition>`
```
struct __cppobj DefinitionSerializer<PhysicsDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<PhysicsDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<PhysicsDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<PhysicsDefinition>`
```
struct __cppobj DefinitionInstanceTyped<PhysicsDefinition> : IDefinitionInstance
{
  std::unique_ptr<PhysicsDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent> : DefinitionInstanceTyped<PhysicsDefinition>
{
};

```

### `DefinitionSerializer<RailMovementDefinition>`
```
struct __cppobj DefinitionSerializer<RailMovementDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<RailMovementDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<RailMovementDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<RailMovementDefinition>`
```
struct __cppobj DefinitionInstanceTyped<RailMovementDefinition> : IDefinitionInstance
{
  std::unique_ptr<RailMovementDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent> : DefinitionInstanceTyped<RailMovementDefinition>
{
};

```

### `DefinitionSerializer<ScaffoldingClimberDefinition>`
```
struct __cppobj DefinitionSerializer<ScaffoldingClimberDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<ScaffoldingClimberDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<ScaffoldingClimberDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<ScaffoldingClimberDefinition>`
```
struct __cppobj DefinitionInstanceTyped<ScaffoldingClimberDefinition> : IDefinitionInstance
{
  std::unique_ptr<ScaffoldingClimberDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent> : DefinitionInstanceTyped<ScaffoldingClimberDefinition>
{
};

```

### `DefinitionSerializer<ScaleByAgeDefinition>`
```
struct __cppobj DefinitionSerializer<ScaleByAgeDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<ScaleByAgeDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<ScaleByAgeDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent> : DefinitionInstanceTyped<ScaleByAgeDefinition>
{
};

```

### `DefinitionSerializer<SchedulerDefinition>`
```
struct __cppobj DefinitionSerializer<SchedulerDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<SchedulerDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<SchedulerDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent> : DefinitionInstanceTyped<SchedulerDefinition>
{
};

```

### `DefinitionSerializer<BlockBreakSensorDefinition>`
```
struct __cppobj DefinitionSerializer<BlockBreakSensorDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BlockBreakSensorDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BlockBreakSensorDefinition> mSchema;
};

```

### `DefinitionInstanceTyped<BlockBreakSensorDefinition>`
```
struct __cppobj DefinitionInstanceTyped<BlockBreakSensorDefinition> : IDefinitionInstance
{
  std::unique_ptr<BlockBreakSensorDefinition> mDefinition;
};

```

### `DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent> : DefinitionInstanceTyped<BlockBreakSensorDefinition>
{
};

```

### `DefinitionSerializer<ShareableDefinition>`
```
struct __cppobj DefinitionSerializer<ShareableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<ShareableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<ShareableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent> : DefinitionInstanceTyped<ShareableDefinition>
{
};

```

### `DefinitionSerializer<GrowsCropDefinition>`
```
struct __cppobj DefinitionSerializer<GrowsCropDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<GrowsCropDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<GrowsCropDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent> : DefinitionInstanceTyped<GrowsCropDefinition>
{
};

```

### `DefinitionSerializer<BalloonDefinition>`
```
struct __cppobj DefinitionSerializer<BalloonDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BalloonDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BalloonDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent> : DefinitionInstanceTyped<BalloonDefinition>
{
};

```

### `DefinitionSerializer<BalloonableDefinition>`
```
struct __cppobj DefinitionSerializer<BalloonableDefinition> : IDefinitionSerializer
{
  DefinitionSerializer<BalloonableDefinition>::DefinitionInitializer mDefinitionInitializer;
  JsonUtil::JsonSchemaRoot<BalloonableDefinition> mSchema;
};

```

### `DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent>`
```
struct __cppobj DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent> : DefinitionInstanceTyped<BalloonableDefinition>
{
};

```

### `DecoratorDefinition`
```
struct __cppobj DecoratorDefinition : BehaviorDefinition
{
  Unique<BehaviorDefinition> mChild;
};

```

### `DiggerItem`
```
struct __cppobj DiggerItem : Item
{
  float mSpeed;
  const Item::Tier *mTier;
  int mAttackDamage;
  DiggerItem::BlockList mBlocks;
  std::set<const BlockLegacy *> m_bBlocks;
};

```

### `DiodeBlock`
```
struct __cppobj __attribute__((aligned(8))) DiodeBlock : BlockLegacy
{
  bool mOn;
};

```

### `DBStorageEnvironmentChain`
```
struct DBStorageEnvironmentChain
{
  std::unique_ptr<EncryptedProxyEnv> mEncryptedEnv;
  std::unique_ptr<FlushableEnv> mFlushableEnv;
  std::unique_ptr<FlushableEnv> mPreSnapshotBufferEnv;
  std::unique_ptr<SnapshotEnv> mSnapshotEnv;
  std::unique_ptr<CompactionListenerEnv> mCompactionListenerEnv;
  leveldb::Env *mWrappedEnv;
  Core::HeapPathBuffer mDbPath;
};

```

### `DBStorage::Options`
```
struct __attribute__((aligned(8))) DBStorage::Options
{
  leveldb::Options options;
  leveldb::ReadOptions read;
  leveldb::WriteOptions write;
};

```

### `DBChunkStorage`
```
struct __cppobj DBChunkStorage : ChunkSource
{
  std::unordered_map<DBChunkStorageKey,DBChunkStorage::ChunkCacheStatus> mHasChunkCache;
  SpinLock mHasChunkCacheMutex;
  DBStorage *mStorage;
  std::vector<std::shared_ptr<DBStorageWriteBatch>> mBufferPool;
  std::vector<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>> mDiscardBatch;
  std::unordered_set<ChunkPos> mLiveChunksBeingSaved;
  std::unordered_map<ChunkPos,std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>> mDiscardedWhileLiveSaved;
  bool mBatch;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  std::vector<std::function<void (LevelChunk &,BlockSource &)>> mUpgradeFixHandlers;
};

```

### `DBStorage::PendingWrite`
```
struct DBStorage::PendingWrite
{
  int mNumPending;
  std::shared_ptr<std::string > mValue;
};

```

### `DBStorageWriteBatch`
```
struct __cppobj DBStorageWriteBatch : LevelStorage::Batch
{
  leveldb::WriteBatch mBatch;
  bool hasPendingActions;
  std::vector<std::function<void ()>> mFlushCallbacks;
};

```

### `DBStorageWriteBatch::PerfContext`
```
struct DBStorageWriteBatch::PerfContext
{
  uint64_t mOperation;
  uint64_t mSize;
  const std::string mKey;
  const char *mReason;
};

```

### `DataStructures::Queue<RakNet::InternalPacket *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::InternalPacket *>
{
  RakNet::InternalPacket **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::Queue<RakNet::ReliabilityLayer::DatagramHistoryNode>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::ReliabilityLayer::DatagramHistoryNode>
{
  RakNet::ReliabilityLayer::DatagramHistoryNode *array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>
{
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page`
```
struct DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page
{
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page *next;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page *prev;
};

```

### `DataStructures::List<RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode>`
```
struct DataStructures::List<RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode>
{
  RakNet::ReliabilityLayer::UnreliableWithAckReceiptNode *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacket>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::InternalPacket>
{
  DataStructures::MemoryPool<RakNet::InternalPacket>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::InternalPacket>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacket>::Page`
```
struct DataStructures::MemoryPool<RakNet::InternalPacket>::Page
{
  DataStructures::MemoryPool<RakNet::InternalPacket>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::InternalPacket>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::InternalPacket>::Page *next;
  DataStructures::MemoryPool<RakNet::InternalPacket>::Page *prev;
};

```

### `DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>`
```
struct __attribute__((aligned(8))) DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>
{
  DataStructures::List<DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>::HeapNode> heap;
  bool optimizeNextSeriesPush;
};

```

### `DataStructures::List<DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>::HeapNode>`
```
struct DataStructures::List<DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>::HeapNode>
{
  DataStructures::Heap<unsigned long,RakNet::InternalPacket *,false>::HeapNode *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::OrderedList<unsigned short,RakNet::SplitPacketChannel *,&RakNet::SplitPacketChannelComp>`
```
struct DataStructures::OrderedList<unsigned short,RakNet::SplitPacketChannel *,&RakNet::SplitPacketChannelComp>
{
  DataStructures::List<RakNet::SplitPacketChannel *> orderedList;
};

```

### `DataStructures::List<RakNet::SplitPacketChannel *>`
```
struct DataStructures::List<RakNet::SplitPacketChannel *>
{
  RakNet::SplitPacketChannel **listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::Queue<bool>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<bool>
{
  bool *array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::List<RakNet::InternalPacket *>`
```
struct DataStructures::List<RakNet::InternalPacket *>
{
  RakNet::InternalPacket **listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::List<bool>`
```
struct DataStructures::List<bool>
{
  bool *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::List<unsigned int>`
```
struct DataStructures::List<unsigned int>
{
  unsigned int *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>
{
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page`
```
struct DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page
{
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page *next;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteSystemIndex>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::RemoteSystemIndex>
{
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page`
```
struct DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page
{
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page *next;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::MemoryWithPage
{
  RakNet::RemoteSystemIndex userMemory;
  DataStructures::MemoryPool<RakNet::RemoteSystemIndex>::Page *parentPage;
};

```

### `DataStructures::List<RakNet::RakPeer::BanStruct *>`
```
struct DataStructures::List<RakNet::RakPeer::BanStruct *>
{
  RakNet::RakPeer::BanStruct **listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::List<RakNet::PluginInterface2 *>`
```
struct DataStructures::List<RakNet::PluginInterface2 *>
{
  RakNet::PluginInterface2 **listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::BufferedCommandStruct>`
```
struct DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::BufferedCommandStruct>
{
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct> memoryPool;
  RakNet::SimpleMutex memoryPoolMutex;
  DataStructures::Queue<RakNet::RakPeer::BufferedCommandStruct *> queue;
  RakNet::SimpleMutex queueMutex;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>
{
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page`
```
struct DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page
{
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page *next;
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::MemoryWithPage
{
  RakNet::RakPeer::BufferedCommandStruct userMemory;
  DataStructures::MemoryPool<RakNet::RakPeer::BufferedCommandStruct>::Page *parentPage;
};

```

### `DataStructures::Queue<RakNet::RakPeer::BufferedCommandStruct *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::RakPeer::BufferedCommandStruct *>
{
  RakNet::RakPeer::BufferedCommandStruct **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::Queue<RakNet::RNS2RecvStruct *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::RNS2RecvStruct *>
{
  RakNet::RNS2RecvStruct **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::SocketQueryOutput>`
```
struct DataStructures::ThreadsafeAllocatingQueue<RakNet::RakPeer::SocketQueryOutput>
{
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput> memoryPool;
  RakNet::SimpleMutex memoryPoolMutex;
  DataStructures::Queue<RakNet::RakPeer::SocketQueryOutput *> queue;
  RakNet::SimpleMutex queueMutex;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>
{
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page`
```
struct DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page
{
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page *next;
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::MemoryWithPage
{
  RakNet::RakPeer::SocketQueryOutput userMemory;
  DataStructures::MemoryPool<RakNet::RakPeer::SocketQueryOutput>::Page *parentPage;
};

```

### `DataStructures::Queue<RakNet::RakPeer::SocketQueryOutput *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::RakPeer::SocketQueryOutput *>
{
  RakNet::RakPeer::SocketQueryOutput **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::List<RakNet::RakString>`
```
struct DataStructures::List<RakNet::RakString>
{
  RakNet::RakString *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::MemoryPool<RakNet::Packet>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::Packet>
{
  DataStructures::MemoryPool<RakNet::Packet>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::Packet>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::Packet>::Page`
```
struct DataStructures::MemoryPool<RakNet::Packet>::Page
{
  DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::Packet>::Page *next;
  DataStructures::MemoryPool<RakNet::Packet>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage
{
  RakNet::Packet userMemory;
  DataStructures::MemoryPool<RakNet::Packet>::Page *parentPage;
};

```

### `DataStructures::Queue<RakNet::Packet *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::Packet *>
{
  RakNet::Packet **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::List<RakNet::RakNetStatistics>`
```
struct DataStructures::List<RakNet::RakNetStatistics>
{
  RakNet::RakNetStatistics *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::MemoryWithPage
{
  RakNet::ReliabilityLayer::MessageNumberNode userMemory;
  DataStructures::MemoryPool<RakNet::ReliabilityLayer::MessageNumberNode>::Page *parentPage;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacket>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::InternalPacket>::MemoryWithPage
{
  RakNet::InternalPacket userMemory;
  DataStructures::MemoryPool<RakNet::InternalPacket>::Page *parentPage;
};

```

### `DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::MemoryWithPage
{
  RakNet::InternalPacketRefCountedData userMemory;
  DataStructures::MemoryPool<RakNet::InternalPacketRefCountedData>::Page *parentPage;
};

```

### `DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>`
```
struct __attribute__((aligned(8))) DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>
{
  DataStructures::OrderedList<int,DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode,&DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::NodeComparisonFunc> mapNodeList;
  unsigned int lastSearchIndex;
  int lastSearchKey;
  bool lastSearchIndexValid;
};

```

### `DataStructures::OrderedList<int,DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode,&DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::NodeComparisonFunc>`
```
struct DataStructures::OrderedList<int,DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode,&DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::NodeComparisonFunc>
{
  DataStructures::List<DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode> orderedList;
};

```

### `DataStructures::List<DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode>`
```
struct DataStructures::List<DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode>
{
  DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison>::MapNode *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::OrderedList<char *,StrAndBool,&RakNet::StrAndBoolComp>`
```
struct DataStructures::OrderedList<char *,StrAndBool,&RakNet::StrAndBoolComp>
{
  DataStructures::List<StrAndBool> orderedList;
};

```

### `DataStructures::List<StrAndBool>`
```
struct DataStructures::List<StrAndBool>
{
  StrAndBool *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::ByteQueue`
```
struct __attribute__((aligned(8))) DataStructures::ByteQueue
{
  char *data;
  unsigned int readOffset;
  unsigned int writeOffset;
  unsigned int lengthAllocated;
};

```

### `DataStructures::ThreadsafeAllocatingQueue<RakNet::Packet>`
```
struct DataStructures::ThreadsafeAllocatingQueue<RakNet::Packet>
{
  DataStructures::MemoryPool<RakNet::Packet> memoryPool;
  RakNet::SimpleMutex memoryPoolMutex;
  DataStructures::Queue<RakNet::Packet *> queue;
  RakNet::SimpleMutex queueMutex;
};

```

### `DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>`
```
struct DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>
{
  DataStructures::MemoryPool<RakNet::SystemAddress> memoryPool;
  RakNet::SimpleMutex memoryPoolMutex;
  DataStructures::Queue<RakNet::SystemAddress *> queue;
  RakNet::SimpleMutex queueMutex;
};

```

### `DataStructures::MemoryPool<RakNet::SystemAddress>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::SystemAddress>
{
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::SystemAddress>::Page`
```
struct DataStructures::MemoryPool<RakNet::SystemAddress>::Page
{
  DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *next;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage
{
  RakNet::SystemAddress userMemory;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *parentPage;
};

```

### `DataStructures::Queue<RakNet::SystemAddress *>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::SystemAddress *>
{
  RakNet::SystemAddress **array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::ThreadsafeAllocatingQueue<RakNet::RemoteClient *>`
```
struct DataStructures::ThreadsafeAllocatingQueue<RakNet::RemoteClient *>
{
  DataStructures::MemoryPool<RakNet::RemoteClient *> memoryPool;
  RakNet::SimpleMutex memoryPoolMutex;
  DataStructures::Queue<RakNet::RemoteClient **> queue;
  RakNet::SimpleMutex queueMutex;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteClient *>`
```
struct __attribute__((aligned(8))) DataStructures::MemoryPool<RakNet::RemoteClient *>
{
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *availablePages;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *unavailablePages;
  int availablePagesSize;
  int unavailablePagesSize;
  int memoryPoolPageSize;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteClient *>::Page`
```
struct DataStructures::MemoryPool<RakNet::RemoteClient *>::Page
{
  DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *next;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage
{
  RakNet::RemoteClient *userMemory;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *parentPage;
};

```

### `DataStructures::Queue<RakNet::RemoteClient **>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::RemoteClient **>
{
  RakNet::RemoteClient ***array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::Queue<RakNet::SystemAddress>`
```
struct __attribute__((aligned(8))) DataStructures::Queue<RakNet::SystemAddress>
{
  RakNet::SystemAddress *array;
  unsigned int head;
  unsigned int tail;
  unsigned int allocation_size;
};

```

### `DataStructures::List<int>`
```
struct DataStructures::List<int>
{
  int *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node`
```
struct DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node
{
  HuffmanEncodingTreeNode *item;
  DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *previous;
  DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *next;
};

```

### `dragon::platform::SurfaceParameters`
```
typedef std::variant<std::monostate> dragon::platform::SurfaceParameters;

```

### `dirent`
```
struct __attribute__((aligned(8))) dirent
{
  __ino_t d_ino;
  __off_t d_off;
  unsigned __int16 d_reclen;
  unsigned __int8 d_type;
  char d_name[256];
};

```

### `DebugAssertException`
```
struct DebugAssertException
{
  __int8 baseclass_0[8];
  std::unique_ptr<char []> mDescription;
  std::unique_ptr<char []> mArgument;
  std::unique_ptr<char []> mInfo;
  int mLine;
  std::unique_ptr<char []> mFile;
  std::unique_ptr<char []> mFunction;
};

```

