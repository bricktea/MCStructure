# E
### `EducationLocalLevelSettings`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | hasQuiz


### `ExternalFileLevelStorageSource`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelStorageSource` | baseclass_0
8 | (16) `std::shared_ptr<SaveTransactionManager>` | msptSaveTransactionManager
24 | (8) `Core::FilePathManager *` | mFilePathManager


### `EntityId`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mRawId


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
4 | (1) `Util::Byte` | mUsePlayerID
8 | (32) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB` | _anon_0
40 | (32) `std::string` | mEntityName
72 | (32) `std::string` | mCommandName
104 | (32) `std::string` | mResultKey
136 | (32) `std::string` | mResultString
168 | (32) `std::string` | mErrorList


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB`
Offset | Type | Name
-|-|-|-
0 | (4) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$103E0A04995712B8D39AE343EA50817C` | Achievement
1 | (16) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$3EA7AF8D67CA2C237D54EACA0411C0BB` | Interaction
2 | (4) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$CFC5415F71714946B1482A4EA070D3F8` | PortalCreated
3 | (8) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$731817FF9A1D8A7F7DE35EC2646A852E` | PortalUsed
4 | (32) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$43709AFFC502E7A13BA1073C610D8549` | PetDied
5 | (32) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$3E28A071213A0B2BC357FB8DFB040ECA` | MobKilled
6 | (12) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$8DB381A6CBFA50BDCCF821038DD76269` | CauldronUsed
7 | (16) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$FF0AE4D4703BAEB84232F79BCFC2EBCD` | PlayerDied
8 | (24) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$63ED5E6F79A5C5C3A74CFCAA908DF8F1` | BossKilled
9 | (8) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$92C02C0BC48AA2105788421214C7C1B7` | AgentCommand
10 | (20) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$A01EA2DF6590CA7397A67CCFB21A7F86` | PatternRemoved
11 | (8) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$EA4713E4A3566411BE29AE280F22E9DF` | SlashCommand
12 | (16) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$E47DE5B305D15144F0589DE3337858CF` | FishBucketed
13 | (12) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$FEA48FE64DE27FADBA89F8BAEC4B7A9C` | MobBorn
14 | (8) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$A05CE60CF11B1B9B38674E8A09580618` | POICauldronUsed
15 | (8) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$A05CE60CF11B1B9B38674E8A09580618` | ComposterUsed
16 | (2) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$5B316CCC98B60A95F92E231D823C7BE3` | BellUsed
17 | (12) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$30DBAAB0C52B2A0F9E419B4088A015FC` | RaidUpdate
18 | (20) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$61A09D83502661C769654363F1382707` | PlayerMovementCorrected
19 | (24) `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$922D880B3EFBF7F2063214579535BD95` | PlayerMovementAnomaly


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$103E0A04995712B8D39AE343EA50817C`
Offset | Type | Name
-|-|-|-
0 | (4) `MinecraftEventing::AchievementIds` | mAchievementId


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$3EA7AF8D67CA2C237D54EACA0411C0BB`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mInteractedEntityType
4 | (4) `MinecraftEventing::InteractionType` | mInteractionType
8 | (4) `int` | mInteractedEntityVariant
12 | (1) `unsigned __int8` | mInteractedEntityColor


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$CFC5415F71714946B1482A4EA070D3F8`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mBuiltInDimension


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$731817FF9A1D8A7F7DE35EC2646A852E`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFromDimension
4 | (4) `int` | mToDimension


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$43709AFFC502E7A13BA1073C610D8549`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mKilledByOwner
8 | (8) `int64_t` | mKillerEntityId
16 | (8) `int64_t` | mKilledMobId
24 | (4) `int32_t` | mDamageSource
28 | (4) `ActorType` | mKilledMobType


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$3E28A071213A0B2BC357FB8DFB040ECA`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | mKillerEntityId
8 | (8) `int64_t` | mKilledMobId
16 | (4) `ActorType` | mDamageChildType
20 | (4) `int32_t` | mDamageSource
24 | (4) `int` | mTraderTier


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$8DB381A6CBFA50BDCCF821038DD76269`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mContentsType
4 | (4) `uint32_t` | mContentsColor
8 | (2) `__int16` | mFillLevel


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$FF0AE4D4703BAEB84232F79BCFC2EBCD`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mKillerId
4 | (4) `int` | mKillerVariant
8 | (4) `int32_t` | mDamageSource
12 | (1) `bool` | mInRaid


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$63ED5E6F79A5C5C3A74CFCAA908DF8F1`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mPartySize
8 | (8) `int64_t` | mBossUniqueId
16 | (4) `int32_t` | mBossType


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$92C02C0BC48AA2105788421214C7C1B7`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mResult
4 | (4) `int32_t` | mResultNumber


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$A01EA2DF6590CA7397A67CCFB21A7F86`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mItemId
4 | (4) `int32_t` | mItemAux
8 | (4) `int32_t` | mLayerIndex
12 | (4) `int32_t` | mPatternId
16 | (4) `int32_t` | mPatternColor


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$EA4713E4A3566411BE29AE280F22E9DF`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mSuccessCount
4 | (4) `int32_t` | mErrorCount


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$E47DE5B305D15144F0589DE3337858CF`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mPattern
4 | (4) `int32_t` | mPreset
8 | (4) `int32_t` | mType
12 | (1) `bool` | mRelease


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$FEA48FE64DE27FADBA89F8BAEC4B7A9C`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mBabyType
4 | (4) `int` | mBabyVariant
8 | (1) `unsigned __int8` | mBabyColor


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$A05CE60CF11B1B9B38674E8A09580618`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mItemId
4 | (4) `MinecraftEventing::POIBlockInteractionType` | mInteractionType


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$5B316CCC98B60A95F92E231D823C7BE3`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mItemId


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$30DBAAB0C52B2A0F9E419B4088A015FC`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCurrentWave
4 | (4) `int` | mTotalWaves
8 | (1) `bool` | mSuccess


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$61A09D83502661C769654363F1382707`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mPositionDelta
4 | (4) `float` | mObservedScore
8 | (4) `float` | mThresholdDistance
12 | (4) `float` | mThresholdScore
16 | (4) `int` | mThresholdDuration_ms


### `EventPacket::Data::$A9B56BB2A8A14AFA32257D71180A3DDB::$922D880B3EFBF7F2063214579535BD95`
Offset | Type | Name
-|-|-|-
0 | (1) `MovementEventType` | mEventType
4 | (4) `float` | mObservedScore
8 | (4) `float` | mAveragePosDelta
12 | (4) `float` | mTotalPosDelta
16 | (4) `float` | mMinPosDelta
20 | (4) `float` | mMaxPosDelta


### `EnchantResult`
Offset | Type | Name
-|-|-|-
0 | (1) `EnchantResultType` | result
8 | (8) `size_t` | enchantIdx
16 | (4) `int` | level


### `EntityContext`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContextBase` | baseclass_0


### `EntityContextBase`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistryBase *` | mRegistry
8 | (4) `const EntityId` | mEntity


### `EntitySensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mSensorRange
4 | (4) `int` | mMinimumCount
8 | (4) `int` | mMaximumCount
12 | (1) `bool` | mRequireAll
16 | (64) `ActorFilterGroup` | mEventCondition
80 | (32) `std::string` | mEventName


### `ExplodeComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFuseLength
4 | (4) `int` | mInitialFuseLength
8 | (4) `float` | mExplosionPower
12 | (4) `float` | mMaxResistance
16 | (1) `bool` | mIsFuseLit
17 | (1) `bool` | mCausesFire
18 | (1) `bool` | mBreaksBlocks
19 | (1) `bool` | mFireAffectedByGriefing
20 | (1) `bool` | mDestroyAffectedByGriefing
21 | (1) `bool` | mAllowUnderwater


### `EmotePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (32) `std::string` | mEmote
80 | (1) `uint8_t` | mFlags


### `EducationLevelSettings`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | codeBuilderDefaultUri
32 | (56) `std::unordered_map<std::string,CommandFlag>` | hiddenPlayerCommands
88 | (1) `EducationLocalLevelSettings` | localSettings


### `ErrorPathStack`
Offset | Type | Name
-|-|-|-
0 | (8) `std::vector<std::string> *` | mErrorPath


### `EventInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mEventName


### `EquipmentTableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `PropertyDescription` | baseclass_0
8 | (32) `std::string` | mFilePath
40 | (24) `std::vector<SlotDropChance>` | mDropChancesPerSlot


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


### `EquippableComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SlotDescriptor>` | mSlots


### `ExpressionNode`
Offset | Type | Name
-|-|-|-
0 | (4) `ExpressionOp` | mOp
8 | (56) `MolangScriptArg` | mValue
64 | (24) `std::vector<ExpressionNode>` | mChildren
88 | (8) `uint64_t` | mUsedTokenFlags
96 | (32) `std::string` | _mExpressionString


### `ExpandoContainerModel::OnItemExpandedCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const std::string &,int,int)>::_Invoker_type` | _M_invoker


### `EnchantmentInstance`
Offset | Type | Name
-|-|-|-
0 | (4) `Enchant::Type` | mEnchantType
4 | (4) `int` | mLevel


### `EntityNetId`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mRawId


### `EntityRefTraits::OwnerStorage`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<OwnerStorageEntity::EntityContextOwned>` | mContext


### `Explosion`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (4) `float` | mRadius
16 | (56) `BlockPosSet` | mToBlow
72 | (1) `bool` | mFire
73 | (1) `bool` | mBreaking
74 | (1) `bool` | mAllowUnderwater
80 | (8) `Actor *` | mSource
88 | (8) `BlockSource *` | mRegion
96 | (4) `float` | mMaxResistance
100 | (2516) `Random` | mRandom


### `ExpressionNode::QueryLookupFunc`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<const std::function<float (RenderParams &,const std::vector<float> &)> *(const std::string &,bool)>::_Invoker_type` | _M_invoker


### `EndGatewayFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `EndPodiumFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (1) `bool` | mActive


### `EndDragonFight::GateWayGenerator`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mPlaceNewBlocks
8 | (8) `Unique<ChunkViewSource>` | mSource
16 | (12) `BlockPos` | mPosition


### `EndIslandFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `EndDragonFight::_setEndGatewayBlockActorExitPosition::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `EnvironmentRequirement`
Offset | Type | Name
-|-|-|-
0 | (48) `std::set<const Block *>` | mBlockTypes
48 | (4) `unsigned int` | mNumBlocksRequired
52 | (4) `unsigned int` | mSearchRadius


### `EntityRegistryRefTraits::StackResultStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<EntityRegistry>` | mValue


### `ExpressionNode::GenericQueryLookupFunc`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<const std::function<MolangScriptArg (RenderParams &,const std::vector<MolangScriptArg> &)> *(const std::string &,bool)>::_Invoker_type` | _M_invoker


### `ExperienceRewardComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ExpressionNode>` | mOnBred
24 | (24) `std::vector<ExpressionNode>` | mOnDeath


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
48 | (24) `std::vector<std::vector<const Block *>>` | mPortalPattern


### `EndCityPieces::Generators`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<EndCityPieces::SectionGenerator>>` | baseclass_0


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
156 | (4) `EducationMetadata::UserType` | mRole


### `EducationOptions`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackListener` | baseclass_0
8 | (8) `ResourcePackManager *` | mPackMan
16 | (1) `EducationFeature` | mFeatureFlags


### `epoll_event`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | events
4 | (8) `epoll_data_t` | data


### `epoll_data_t`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ptr
1 | (4) `int` | fd
2 | (4) `uint32_t` | u32
3 | (8) `uint64_t` | u64


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BalloonComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BossComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DanceComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,DwellerComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HopperComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,InsomniaComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MobEffectComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,MountTamingComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,PeekComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,RaidBossComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SchedulerComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SensingComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>`
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


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,LegacyTradeableComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TrailComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EntityRegistryBase::View<EntityContext,EntityRegistry,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EducationLevelSettings::CommandOverrideFunctor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (CommandFlag &,const std::string &)>::_Invoker_type` | _M_invoker


### `EnumBitset<ScriptLogType,3>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<3>` | mBitset


### `EntityComponentFactory:464`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<HashedString,std::unique_ptr<IDefinitionSerializer>>` | mDefinitionSerializers
56 | (1) `bool` | mErrorOnDuplicateAdd
57 | (1) `bool` | mErrorOnAbsentRemove


### `EntityCanonicalName::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `EyeOfEnder::normalTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ExpandoModelElement`
Offset | Type | Name
-|-|-|-
0 | (272) `ContainerItemStack` | item
272 | (4) `ContainerExpandStatus` | status
280 | (32) `std::string` | groupName


### `EntityRefTraits::StackResultStorage`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<EntityContext>` | mContext


### `EntityRegistryBase::View<EntityContext,EntityRegistry,SurfaceBuilderComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EndGatewayBlockActor`
Offset | Type | Name
-|-|-|-
0 | (204) `BlockActor:1632` | baseclass_0
204 | (4) `int` | mAge
208 | (4) `int` | mTeleportCooldown
212 | (12) `BlockPos` | mExitPortal
224 | (1) `bool` | mNeedsExitGeneration
225 | (1) `bool` | mTeleportTriggered
226 | (1) `bool` | mNeedsExitPositionVerification
227 | (1) `bool` | mExitPositionVerified


### `EntityRegistry`
Offset | Type | Name
-|-|-|-
0 | (32) `EntityRegistryBase` | baseclass_0
32 | (16) `std::enable_shared_from_this<EntityRegistry>` | baseclass_20


### `EntityRegistryBase`
Offset | Type | Name
-|-|-|-
0 | (8) `entt::Registry<EntityId> *` | mRegistry
8 | (8) `std::optional<EntityId>` | mViewedEntity
16 | (8) `std::unique_ptr<EntityRegistryBase::ICanModifyComponentPoolDuringView>` | mCanModifyDuringView
24 | (1) `bool` | mViewUsesViewedContext


### `EntityRegistryRefTraits::WeakStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<EntityRegistry>` | mHandle


### `EntityRegistryBase::View<EntityContext,EntityRegistry,ActorComponent,RailMovementComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `EntityRegistry *` | mRegistry


### `EducationMetadataError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `EndGatewayBlock::animateTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `EnumBitset<RenderCapability,14>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<14>` | mBitset


### `EndermanTakeBlockGoal`
Offset | Type | Name
-|-|-|-
0 | (16) `Goal` | baseclass_0
16 | (8) `EnderMan *` | mEnderman


### `EventCoordinator<ServerInstanceEventListener>`
```
struct EventCoordinator<ServerInstanceEventListener>
{
  std::vector<ServerInstanceEventListener *> mListeners;
  std::vector<std::function<EventResult (ServerInstanceEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `ExtendedCertificate`
```
struct ExtendedCertificate
{
  __int8 gap0[1];
};

```

### `EncryptedNetworkPeer`
```
struct __cppobj EncryptedNetworkPeer : NetworkPeer
{
  Unique<Crypto::Symmetric::Symmetric> mDecryption;
  Unique<Crypto::Hash::HMAC> mEncryptionMAC;
  Unique<Crypto::Symmetric::Symmetric> mEncryption;
  Unique<Crypto::Hash::HMAC> mDecryptionMAC;
  uint64_t mSendCounter;
  uint64_t mReceiveCounter;
  std::string mSendEncryptedDataBuffer;
  std::string mSendSignedDataBuffer;
  std::string mRecvEncryptedDataBuffer;
  std::string mRecvSignedDataBuffer;
  std::string mRecvDecryptedDataBuffer;
};

```

### `EntityRegistryBase::ICanModifyComponentPoolDuringView`
```
struct EntityRegistryBase::ICanModifyComponentPoolDuringView
{
  __int8 gap0[1];
};

```

### `EnableGetWeakRef<EntityRegistryRefTraits>`
```
struct EnableGetWeakRef<EntityRegistryRefTraits>
{
  __int8 gap0[1];
};

```

### `EntityRegistryOwned`
```
struct __cppobj EntityRegistryOwned : EntityRegistry
{
  entt::Registry<EntityId> mOwnedRegistry;
};

```

### `EnableGetWeakRef<EntityRefTraits>`
```
struct EnableGetWeakRef<EntityRefTraits>
{
  __int8 gap0[1];
};

```

### `EnvironmentSensorSystem`
```
struct __cppobj EnvironmentSensorSystem : ITickingSystem
{
};

```

### `ExplodeSystem`
```
struct __cppobj ExplodeSystem : ITickingSystem
{
};

```

### `EntitySensorSystem`
```
struct __cppobj EntitySensorSystem : ITickingSystem
{
};

```

### `EntityRegistryRefTraits`
```
struct EntityRegistryRefTraits
{
  __int8 gap0[1];
};

```

### `EntityRegistryRefTraits::OwnerStorage`
```
typedef OwnerStorageSharePtr<EntityRegistryOwned> EntityRegistryRefTraits::OwnerStorage;

```

### `EntityRegistryRefTraits::OwnerStackRef`
```
typedef EntityRegistryOwned EntityRegistryRefTraits::OwnerStackRef;

```

### `EntityRefTraits`
```
struct EntityRefTraits
{
  __int8 gap0[1];
};

```

### `EntityRefTraits::WeakStorage`
```
typedef WeakStorageEntity EntityRefTraits::WeakStorage;

```

### `EntityRefTraits::OwnerStackRef`
```
typedef EntityRefTraits::StackRef EntityRefTraits::OwnerStackRef;

```

### `EntityRefTraits::StackRef`
```
typedef EntityContext EntityRefTraits::StackRef;

```

### `EntitySystems`
```
struct EntitySystems
{
  std::vector<std::unique_ptr<ITickingSystem>> mTickingSystems;
  Unique<PlayerInteractionSystem> mPlayerInteractionSystem;
};

```

### `EntityComponentFactory`
```
struct __attribute__((aligned(8))) EntityComponentFactory
{
  std::unordered_map<HashedString,std::unique_ptr<IDefinitionSerializer>> mDefinitionSerializers;
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EventCoordinator<PlayerEventListener>`
```
struct EventCoordinator<PlayerEventListener>
{
  std::vector<PlayerEventListener *> mListeners;
  std::vector<std::function<EventResult (PlayerEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<ActorEventListener>`
```
struct EventCoordinator<ActorEventListener>
{
  std::vector<ActorEventListener *> mListeners;
  std::vector<std::function<EventResult (ActorEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<BlockEventListener>`
```
struct EventCoordinator<BlockEventListener>
{
  std::vector<BlockEventListener *> mListeners;
  std::vector<std::function<EventResult (BlockEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EnchantCommand`
```
struct __cppobj __attribute__((aligned(8))) EnchantCommand : Command
{
  PlayerSelector mTargets;
  Enchant::Type mType;
  int mId;
  int mLevel;
};

```

### `Enchant`
```
struct __attribute__((aligned(8))) Enchant
{
  int (**_vptr$Enchant)(void);
  const Enchant::Type mEnchantType;
  const Enchant::Frequency mFrequency;
  const bool mIsLootable;
  const int mPrimarySlots;
  const int mSecondarySlots;
  const int mCompatibility;
  const std::string mDescription;
  const Util::HashString mStringId;
  bool mIsExperimental;
  bool mIsDisabled;
};

```

### `ExtraLicenseData`
```
struct ExtraLicenseData
{
  int64_t mValidationTime;
  int64_t mRetryUntilTime;
  int64_t mRetryAttempts;
};

```

### `EconomyTradeableComponent`
```
struct __attribute__((aligned(8))) EconomyTradeableComponent
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
};

```

### `ExperienceOrb`
```
struct __cppobj __attribute__((aligned(8))) ExperienceOrb : Actor
{
  ActorUniqueID mFollowingPlayer;
  int mFollowingTime;
  int mAge;
  int mHealth;
};

```

### `EnvironmentSensorDefinition`
```
struct EnvironmentSensorDefinition
{
  std::vector<DefinitionTrigger> mTriggers;
};

```

### `EndTag`
```
struct __cppobj EndTag : Tag
{
};

```

### `EventCoordinator<NetworkPacketEventListener>`
```
struct EventCoordinator<NetworkPacketEventListener>
{
  std::vector<NetworkPacketEventListener *> mListeners;
  std::vector<std::function<EventResult (NetworkPacketEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EducationSettingsPacket`
```
struct __cppobj EducationSettingsPacket : Packet
{
  EducationLevelSettings mEducationLevelSettings;
};

```

### `EntityClientPacket`
```
struct __cppobj EntityClientPacket : Packet:288
{
  EntityNetId mEntityNetId;
};

```

### `EntityServerPacket`
```
struct __cppobj EntityServerPacket : Packet:288
{
  EntityNetId mEntityNetId;
};

```

### `EnumOption`
```
struct __cppobj EnumOption : IntOption
{
  const std::unordered_map<int,std::string> *ValueNameMap;
};

```

### `EventCoordinator<LevelEventListener>`
```
struct EventCoordinator<LevelEventListener>
{
  std::vector<LevelEventListener *> mListeners;
  std::vector<std::function<EventResult (LevelEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EventCoordinator<ItemEventListener>`
```
struct EventCoordinator<ItemEventListener>
{
  std::vector<ItemEventListener *> mListeners;
  std::vector<std::function<EventResult (ItemEventListener *)>> mEventsToProcess;
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

### `EconomyTradeableDescription`
```
struct __cppobj __attribute__((aligned(8))) EconomyTradeableDescription : ComponentDescription
{
  std::string mDisplayName;
  std::string mTradeTablePath;
  bool mUseNewTradeScreen;
  int mHeroDemandDiscount;
  bool mPersistTrades;
  bool mConvertTradesEconomy;
};

```

### `EnchantingContainerManagerModel`
```
struct __cppobj EnchantingContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  bool mShouldBookBeOpen;
  std::vector<std::pair<int,ItemEnchants>> mEnchants;
  std::vector<std::string> mEnchantNames;
  std::vector<int> mCosts;
};

```

### `ElementConstructorContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) ElementConstructorContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `EventCoordinator<ScriptEventListener>`
```
struct EventCoordinator<ScriptEventListener>
{
  std::vector<ScriptEventListener *> mListeners;
  std::vector<std::function<EventResult (ScriptEventListener *)>> mEventsToProcess;
  std::thread::id mThreadId;
  bool mThreadIdInitialized;
  unsigned int mThreadCheckIndex;
};

```

### `EvalParams`
```
struct EvalParams
{
  MolangVariableMap mTempVariables;
};

```

### `EnderMan`
```
struct __cppobj __attribute__((aligned(8))) EnderMan : Monster
{
  bool mAggroedByPlayer;
  std::unique_ptr<CompoundTag> mCarryBlockSerId;
  NewBlockID mCarryBlockId;
  DataID mCarryBlockData;
};

```

### `EnderDragon`
```
struct __cppobj EnderDragon : Monster
{
  float mFlapTimeO;
  float mFlapTime;
  Unique<Path> mPath;
  std::array<std::array<float,3>,64> mPositions;
  int mPosPointer;
  AABB *mHead;
  AABB *mNeck;
  AABB *mBody;
  AABB *mTail1;
  AABB *mTail2;
  AABB *mTail3;
  AABB *mWing1;
  AABB *mWing2;
  bool mInWall;
  int mGrowlTime;
  int mSittingDamageReceived;
  float mTurnSpeed;
  Vec3 mTargetPos;
  int mFlameAttackCount;
  bool mDeathAnimation;
  bool mNodesFinalized;
  std::vector<PathfinderNode> mNodes;
  intArray mNodeAdjacency;
  BinaryHeap mOpenSet;
  ActorUniqueID mNearestCrystal;
  EndDragonFight *mDragonFight;
};

```

### `Endermite`
```
struct __cppobj __attribute__((aligned(8))) Endermite : Monster
{
  int mLifeTime;
};

```

### `ExperiencePotion`
```
struct __cppobj ExperiencePotion : Throwable
{
};

```

### `EyeOfEnder`
```
struct __cppobj EyeOfEnder : Actor
{
  BlockPos mTarget;
  bool mSurviveAfterDeath;
  int mLife;
  Vec3 mTargetPos;
};

```

### `EnderCrystal`
```
struct __cppobj __attribute__((aligned(8))) EnderCrystal : Actor
{
  uint64_t mTime;
  int mTimeOffset;
};

```

### `EvocationFang`
```
struct __cppobj __attribute__((aligned(8))) EvocationFang : Actor
{
  bool mClientSideAttackStarted;
};

```

### `EvocationIllager`
```
struct __cppobj EvocationIllager : HumanoidMonster
{
};

```

### `EatBlockGoal`
```
struct __cppobj EatBlockGoal : Goal:96
{
  int mEatAnimationTick;
  const DefinitionTrigger mOnEat;
  Mob *mMob;
};

```

### `EatCarriedItemGoal`
```
struct __cppobj EatCarriedItemGoal : Goal
{
  Mob *mMob;
  const uint64_t mStartDelay;
  uint64_t mStartDelayCounter;
};

```

### `ExploreOutskirtsGoal`
```
struct __cppobj ExploreOutskirtsGoal : Goal
{
  Mob *mMob;
  const float mSpeed;
  const float mExploreDist;
  const Tick mWaitTime;
  const Tick mTravelTimeout;
  Tick mWaitTimer;
  Tick mShiftLocationTimer;
  Tick mTravelTimer;
  bool mTraveling;
  bool mFailedToPath;
  Vec3 mWantedPos;
};

```

### `EndermanLeaveBlockGoal`
```
struct __cppobj EndermanLeaveBlockGoal : Goal
{
  EnderMan *mEnderman;
};

```

### `EndDragonFight`
```
struct EndDragonFight
{
  BlockSource *mRegion;
  std::vector<int> mGateways;
  Unique<BlockPatternBuilder> mExitPortalPattern;
  int mCrystalsAlive;
  int mTicksSinceCrystalsScanned;
  int mTicksSincePortalScanned;
  int mTicksSinceLastPlayerScan;
  bool mDragonKilled;
  bool mPreviouslyKilled;
  bool mDragonSpawned;
  ActorUniqueID mDragonUUID;
  BlockPos mPortalLocation;
  const BlockPos mDragonSpawnPos;
  RespawnAnimation mRespawnStage;
  int mRespawnTime;
  std::vector<ActorUniqueID> mRespawnCrystals;
  EndDragonFightVersion mFightVersion;
  EndDragonFight::GateWayGenerator mEntryGenerator;
  EndDragonFight::GateWayGenerator mExitGenerator;
  EndDragonFight::GatewayTask mBuildingOrVerifyingEndGatewayPair;
  std::deque<std::tuple<EndDragonFight::GatewayTask,EndDragonFight::GateWayGenerator,EndDragonFight::GateWayGenerator>> mGatewayTasks;
};

```

### `ExhaustionAttributeDelegate`
```
struct __cppobj ExhaustionAttributeDelegate : AttributeInstanceDelegate
{
};

```

### `ExpandoContainerModel`
```
struct __cppobj ExpandoContainerModel : ContainerModel
{
  std::vector<ExpandoModelElement> mCurrentItems;
  std::vector<ExpandoModelElement> mExpandedItems;
  ExpandoContainerModel::OnItemExpandedCallback mOnItemExpanded;
};

```

### `EmptyMapItem`
```
struct __cppobj EmptyMapItem : ComplexItem
{
};

```

### `EnchantedBookItem`
```
struct __cppobj __attribute__((aligned(8))) EnchantedBookItem : Item
{
  bool mIsGlint;
};

```

### `EggItem`
```
struct __cppobj EggItem : Item
{
};

```

### `EnderpearlItem`
```
struct __cppobj EnderpearlItem : Item
{
};

```

### `EnderEyeItem`
```
struct __cppobj EnderEyeItem : Item
{
};

```

### `ExperiencePotionItem`
```
struct __cppobj ExperiencePotionItem : Item
{
};

```

### `EndCrystalItem`
```
struct __cppobj EndCrystalItem : Item
{
};

```

### `ElementBlockItem`
```
struct __cppobj ElementBlockItem : ChemistryAuxDataBlockItem
{
};

```

### `EnchantUtils`
```
struct EnchantUtils
{
  __int8 gap0[1];
};

```

### `EntityOptionalOwnerRef`
```
struct EntityOptionalOwnerRef
{
  OwnerPtr<EntityId> mOwnedEntity;
  WeakRef<EntityId> mWeakEntity;
};

```

### `ElementBlock`
```
struct __cppobj __attribute__((aligned(8))) ElementBlock : BlockLegacy
{
  ElementType mType;
};

```

### `ElementInfo`
```
struct ElementInfo
{
  ElementCategory mCategory;
  const char *mName;
};

```

### `EnchantingTableBlockActor`
```
struct __cppobj EnchantingTableBlockActor : BlockActor:1632
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

### `EndPortalBlockActor`
```
struct __cppobj EndPortalBlockActor : BlockActor
{
};

```

### `EnderChestBlockActor`
```
struct __cppobj __attribute__((aligned(8))) EnderChestBlockActor : ChestBlockActor
{
};

```

### `EnchantingTableBlock`
```
struct __cppobj EnchantingTableBlock : ActorBlock
{
};

```

### `EndPortalBlock`
```
struct __cppobj EndPortalBlock : ActorBlock
{
};

```

### `EndPortalFrameBlock`
```
struct __cppobj EndPortalFrameBlock : BlockLegacy
{
};

```

### `EnderChestBlock`
```
struct __cppobj __attribute__((aligned(8))) EnderChestBlock : ChestBlock
{
};

```

### `EndRodBlock`
```
struct __cppobj EndRodBlock : BlockLegacy
{
};

```

### `EndGatewayBlock`
```
struct __cppobj EndGatewayBlock : ActorBlock
{
};

```

### `EndCityFeature`
```
struct __cppobj EndCityFeature : StructureFeature
{
  TheEndGenerator *mLevelSource;
};

```

### `EntitySensorDefinition`
```
struct EntitySensorDefinition
{
  float mSensorRange;
  int mMinimumCount;
  int mMaximumCount;
  bool mRequireAll;
  ActorFilterGroup mEventCondition;
  std::string mEventName;
};

```

### `ExperienceRewardDefinition`
```
struct ExperienceRewardDefinition
{
  std::vector<ExpressionNode> mOnBred;
  std::vector<ExpressionNode> mOnDeath;
};

```

### `EntityRegistryRefTraits::StackRef`
```
typedef EntityRegistry EntityRegistryRefTraits::StackRef;

```

### `EncryptedZipTransforms`
```
struct __cppobj EncryptedZipTransforms : FileAccessTransforms
{
  const IContentKeyProvider *mKeyProvider;
};

```

### `EncryptedFileAccessStrategy`
```
struct __cppobj EncryptedFileAccessStrategy : DirectoryPackAccessStrategy
{
  ContentIdentity mContentIdentity;
  const IContentKeyProvider *mKeyProvider;
  std::unordered_map<Core::PathBuffer<std::string >,std::string> mEncryptedAssetSet;
};

```

### `EffectCommand`
```
struct __cppobj __attribute__((aligned(8))) EffectCommand : Command
{
  ActorSelector mTargets;
  EffectCommand::Mode mMode;
  const MobEffect *mEffect;
  int mDuration;
  int mAmplifier;
  bool mHideParticles;
};

```

### `ExecuteCommand`
```
struct __cppobj ExecuteCommand : Command
{
  ActorSelector mTargets;
  CommandPositionFloat mPosition;
  CommandPosition mDetectPosition;
  const Block *mBlock;
  int mBlockData;
  ExecuteCommand::Mode mMode;
  std::unique_ptr<Command> mCommand;
};

```

### `EntityComponentDefinition<AddRiderDefinition,AddRiderComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<AddRiderDefinition,AddRiderComponent> : DefinitionInstance<EntityContext &,AddRiderDefinition,AddRiderComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AgeableDefinition,AgeableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<AgeableDefinition,AgeableComponent> : DefinitionInstance<EntityContext &,AgeableDefinition,AgeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<AreaAttackDefinition,AreaAttackComponent> : DefinitionInstance<EntityContext &,AreaAttackDefinition,AreaAttackComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BoostableDefinition,BoostableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BoostableDefinition,BoostableComponent> : DefinitionInstance<EntityContext &,BoostableDefinition,BoostableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BossDefinition,BossComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BossDefinition,BossComponent> : DefinitionInstance<EntityContext &,BossDefinition,BossComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BreathableDefinition,BreathableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BreathableDefinition,BreathableComponent> : DefinitionInstance<EntityContext &,BreathableDefinition,BreathableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BreedableDefinition,BreedableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BreedableDefinition,BreedableComponent> : DefinitionInstance<EntityContext &,BreedableDefinition,BreedableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BribeableDefinition,BribeableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BribeableDefinition,BribeableComponent> : DefinitionInstance<EntityContext &,BribeableDefinition,BribeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> > : DefinitionInstance<EntityContext &,BurnsInDaylightDefinition,ActorFlagComponent<BurnsInDaylightFlag> >
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<DamageOverTimeDefinition,DamageOverTimeComponent> : DefinitionInstance<EntityContext &,DamageOverTimeDefinition,DamageOverTimeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<DamageSensorDefinition,DamageSensorComponent> : DefinitionInstance<EntityContext &,DamageSensorDefinition,DamageSensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<EntitySensorDefinition,EntitySensorComponent> : DefinitionInstance<EntityContext &,EntitySensorDefinition,EntitySensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> > : DefinitionInstance<EntityContext &,EnvironmentSensorDefinition,ActorFlagComponent<EnvironmentSensorFlag> >
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<EquippableDefinition,EquippableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<EquippableDefinition,EquippableComponent> : DefinitionInstance<EntityContext &,EquippableDefinition,EquippableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<ExperienceRewardDefinition,ExperienceRewardComponent> : DefinitionInstance<EntityContext &,ExperienceRewardDefinition,ExperienceRewardComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ExplodeDefinition,ExplodeComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<ExplodeDefinition,ExplodeComponent> : DefinitionInstance<EntityContext &,ExplodeDefinition,ExplodeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<FlockingDefinition,FlockingComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<FlockingDefinition,FlockingComponent> : DefinitionInstance<EntityContext &,FlockingDefinition,FlockingComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GeneticsDefinition,GeneticsComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<GeneticsDefinition,GeneticsComponent> : DefinitionInstance<EntityContext &,GeneticsDefinition,GeneticsComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GiveableDefinition,GiveableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<GiveableDefinition,GiveableComponent> : DefinitionInstance<EntityContext &,GiveableDefinition,GiveableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HealableDefinition,HealableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<HealableDefinition,HealableComponent> : DefinitionInstance<EntityContext &,HealableDefinition,HealableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HomeDefinition,HomeComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<HomeDefinition,HomeComponent> : DefinitionInstance<EntityContext &,HomeDefinition,HomeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<HurtOnConditionDefinition,HurtOnConditionComponent> : DefinitionInstance<EntityContext &,HurtOnConditionDefinition,HurtOnConditionComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InsomniaDefinition,InsomniaComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<InsomniaDefinition,InsomniaComponent> : DefinitionInstance<EntityContext &,InsomniaDefinition,InsomniaComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<InteractDefinition,InteractComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<InteractDefinition,InteractComponent> : DefinitionInstance<EntityContext &,InteractDefinition,InteractComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<HopperDefinition,HopperComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<HopperDefinition,HopperComponent> : DefinitionInstance<EntityContext &,HopperDefinition,HopperComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LeashableDefinition,LeashableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<LeashableDefinition,LeashableComponent> : DefinitionInstance<EntityContext &,LeashableDefinition,LeashableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<LegacyTradeableDefinition,LegacyTradeableComponent> : DefinitionInstance<EntityContext &,LegacyTradeableDefinition,LegacyTradeableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<LookAtDefinition,LookAtComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<LookAtDefinition,LookAtComponent> : DefinitionInstance<EntityContext &,LookAtDefinition,LookAtComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<MobEffectDefinition,MobEffectComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<MobEffectDefinition,MobEffectComponent> : DefinitionInstance<EntityContext &,MobEffectDefinition,MobEffectComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<MountTameableDefinition,MountTamingComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<MountTameableDefinition,MountTamingComponent> : DefinitionInstance<EntityContext &,MountTameableDefinition,MountTamingComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<PeekDefinition,PeekComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<PeekDefinition,PeekComponent> : DefinitionInstance<EntityContext &,PeekDefinition,PeekComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<PhysicsDefinition,PhysicsComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<PhysicsDefinition,PhysicsComponent> : DefinitionInstance<EntityContext &,PhysicsDefinition,PhysicsComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<RailMovementDefinition,RailMovementComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<RailMovementDefinition,RailMovementComponent> : DefinitionInstance<EntityContext &,RailMovementDefinition,RailMovementComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<ScaffoldingClimberDefinition,ScaffoldingClimberComponent> : DefinitionInstance<EntityContext &,ScaffoldingClimberDefinition,ScaffoldingClimberComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<ScaleByAgeDefinition,ScaleByAgeComponent> : DefinitionInstance<EntityContext &,ScaleByAgeDefinition,ScaleByAgeComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<SchedulerDefinition,SchedulerComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<SchedulerDefinition,SchedulerComponent> : DefinitionInstance<EntityContext &,SchedulerDefinition,SchedulerComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BlockBreakSensorDefinition,BlockBreakSensorComponent> : DefinitionInstance<EntityContext &,BlockBreakSensorDefinition,BlockBreakSensorComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<ShareableDefinition,ShareableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<ShareableDefinition,ShareableComponent> : DefinitionInstance<EntityContext &,ShareableDefinition,ShareableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<GrowsCropDefinition,GrowsCropComponent> : DefinitionInstance<EntityContext &,GrowsCropDefinition,GrowsCropComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BalloonDefinition,BalloonComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BalloonDefinition,BalloonComponent> : DefinitionInstance<EntityContext &,BalloonDefinition,BalloonComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EntityComponentDefinition<BalloonableDefinition,BalloonableComponent>`
```
struct __cppobj __attribute__((aligned(8))) EntityComponentDefinition<BalloonableDefinition,BalloonableComponent> : DefinitionInstance<EntityContext &,BalloonableDefinition,BalloonableComponent>
{
  bool mErrorOnDuplicateAdd;
  bool mErrorOnAbsentRemove;
};

```

### `EnchantingInputContainerController`
```
struct __cppobj EnchantingInputContainerController : ContainerController
{
};

```

### `EnchantingMaterialContainerController`
```
struct __cppobj EnchantingMaterialContainerController : ContainerController
{
};

```

### `EndCityStart`
```
struct __cppobj __attribute__((aligned(8))) EndCityStart : StructureStart
{
  bool mIsValid;
};

```

### `EndCityPieces::EndCityPiece`
```
struct __cppobj EndCityPieces::EndCityPiece : TemplateStructurePiece
{
  StructureManager *mStructureManager;
  std::string mTemplateName;
  Rotation_0 mRotation;
  bool mOverwrite;
  std::vector<BlockPos> mMobPositions;
};

```

### `EndCityPieces::SectionGenerator`
```
struct EndCityPieces::SectionGenerator
{
  int (**_vptr$SectionGenerator)(void);
};

```

### `EndCityPieces::TowerGenerator`
```
struct __cppobj EndCityPieces::TowerGenerator : EndCityPieces::SectionGenerator
{
};

```

### `EndCityPieces::FatTowerGenerator`
```
struct __cppobj EndCityPieces::FatTowerGenerator : EndCityPieces::SectionGenerator
{
};

```

### `EndCityPieces::TowerBridgeGenerator`
```
struct __cppobj __attribute__((aligned(8))) EndCityPieces::TowerBridgeGenerator : EndCityPieces::SectionGenerator
{
  bool mShipCreated;
};

```

### `EndCityPieces::HouseTowerGenerator`
```
struct __cppobj EndCityPieces::HouseTowerGenerator : EndCityPieces::SectionGenerator
{
};

```

### `EndCityPieces`
```
struct EndCityPieces
{
  __int8 gap0[1];
};

```

### `EncryptedProxyEnv`
```
struct __cppobj EncryptedProxyEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  const std::string mContentKey;
  const std::string mProductId;
};

```

### `EmptyLootItem`
```
struct __cppobj EmptyLootItem : LootPoolEntry
{
};

```

### `EnchantBookForTradingFunction`
```
struct __cppobj EnchantBookForTradingFunction : LootItemFunction
{
  int mBaseCost;
  int mRandomBaseCost;
  int mRandomPerLevelCost;
  int mPerLevelCost;
};

```

### `EnchantRandomEquipmentFunction`
```
struct __cppobj __attribute__((aligned(8))) EnchantRandomEquipmentFunction : LootItemFunction
{
  float mChance;
};

```

### `EnchantRandomlyFunction`
```
struct __cppobj __attribute__((aligned(8))) EnchantRandomlyFunction : LootItemFunction
{
  std::vector<EnchantmentInstance> mEnchantments;
  bool mTreasure;
};

```

### `EnchantWithLevelsFunction`
```
struct __cppobj __attribute__((aligned(8))) EnchantWithLevelsFunction : LootItemFunction
{
  RandomValueBounds mLevels;
  bool mTreasure;
};

```

### `ExplorationMapFunction`
```
struct __cppobj ExplorationMapFunction : LootItemFunction
{
  std::string mDestination;
};

```

### `ExplosionDecayFunction`
```
struct __cppobj ExplosionDecayFunction : LootItemFunction
{
};

```

