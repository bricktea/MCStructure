# A
### `Abilities`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<PermissionsHandler>` | mPermissions
8 | (216) `std::array<Ability,18>` | mAbilities
224 | (96) `std::array<Ability,8>` | mCustomAbilityCache


### `Ability::Value`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mBoolVal
1 | (4) `float` | mFloatVal


### `AdventureSettings`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | noPvM
1 | (1) `bool` | noMvP
2 | (1) `bool` | immutableWorld
3 | (1) `bool` | showNameTags
4 | (1) `bool` | autoJump


### `AdventureSettingsPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `uint32_t` | mFlags
40 | (1) `CommandPermissionLevel` | mUserPermissions
44 | (4) `uint32_t` | mPermissionsFlags
48 | (1) `PlayerPermissionLevel` | mPlayerPermissions
56 | (8) `ActorUniqueID` | mSyncPlayerId
64 | (1) `bool` | mDefaultLevelAbilities
68 | (4) `uint32_t` | mCustomAbilityCache


### `ActorUniqueID`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | rawID


### `AABB`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | min
12 | (12) `Vec3` | max
24 | (1) `bool` | empty


### `ActorList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<Actor *>` | baseclass_0


### `AppendOnlyAtomicLookupTable<SubChunk,16>`
Offset | Type | Name
-|-|-|-
0 | (896) `std::aligned_storage<56,8>::type[16]` | mArray
896 | (8) `std::atomic_size_t` | mSize
904 | (32) `SpinLock` | mAppendLock


### `ActorEventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (1) `ActorEvent` | mEventId
52 | (4) `int` | mData


### `ActorRuntimeID`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | rawID


### `ActorServerCommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (40) `ActorCommandOrigin` | baseclass_0


### `ActorCommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (24) `CommandOrigin` | baseclass_0
24 | (8) `ActorUniqueID` | mEntityId
32 | (8) `Level *` | mLevel


### `ActorComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor


### `AgeableComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mAge


### `AgentCommandComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<AgentCommands::Command>` | mCurrentCommand
8 | (4) `int` | mWaitForNextCommandTicks


### `AngryComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDuration
4 | (4) `int` | mDurationDelta
8 | (1) `bool` | mHasTicked
9 | (1) `bool` | mBroadcastAnger
12 | (4) `int` | mBroadcastRange
16 | (64) `ActorFilterGroup` | mBroadcastFilter


### `ActorFilterGroup`
Offset | Type | Name
-|-|-|-
0 | (64) `FilterGroup` | baseclass_0


### `ActorDamageByActorSource`
Offset | Type | Name
-|-|-|-
0 | (16) `ActorDamageSource` | baseclass_0
16 | (8) `BlockSource *` | mRegion
24 | (1) `bool` | mIsWorldBuilder
25 | (1) `bool` | mIsCreative
32 | (8) `ActorUniqueID` | mEntityID
40 | (4) `ActorType` | mEntityType
44 | (4) `ActorCategory` | mEntityCategories
48 | (32) `std::string` | mEntityNameTag


### `ActorDamageSource`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ActorDamageSource
8 | (4) `ActorDamageCause` | mCause


### `AreaAttackComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mDamageRange
4 | (4) `int` | mDamagePerTick
8 | (4) `ActorDamageCause` | mDamageCause
16 | (64) `ActorFilterGroup` | mEntityFilter


### `ActorFlagComponent<BurnsInDaylightFlag>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `ActorFlagComponent<EnvironmentSensorFlag>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `ActorDefinitionIdentifier`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mNamespace
32 | (32) `std::string` | mIdentifier
64 | (32) `std::string` | mInitEvent
96 | (32) `std::string` | mFullName
128 | (40) `HashedString` | mCanonicalName


### `ActorLink`
Offset | Type | Name
-|-|-|-
0 | (1) `ActorLinkType` | type
8 | (8) `ActorUniqueID` | A
16 | (8) `ActorUniqueID` | B
24 | (1) `bool` | mImmediate


### `ActorInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRuntimeId
8 | (168) `ActorDefinitionIdentifier` | mIdentifier
176 | (168) `ActorDefinitionIdentifier` | mBaseIdentifier
344 | (1) `bool` | mHasSpawnEgg
345 | (1) `bool` | mIsSummonable
346 | (1) `bool` | mIsExperimental


### `AvailableCommandsPacket::CommandData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | description
64 | (1) `uint8_t` | flags
65 | (1) `CommandPermissionLevel` | permission
72 | (24) `std::vector<AvailableCommandsPacket::OverloadData>` | overloads
96 | (4) `int` | aliasEnum


### `AvailableCommandsPacket::OverloadData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<AvailableCommandsPacket::ParamData>` | params


### `AvailableCommandsPacket::ConstrainedValueData`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | enumValueSymbol
4 | (4) `uint32_t` | enumSymbol
8 | (24) `std::vector<unsigned char>` | constraints


### `AvailableCommandsPacket::ParamData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (4) `uint32_t` | parseSymbol
36 | (1) `bool` | optional
37 | (1) `uint8_t` | paramOptions


### `AllWorkerConfigurations`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadConfiguration` | MainThread
32 | (32) `ThreadConfiguration` | ServerThread
64 | (40) `WorkerConfiguration` | Async
104 | (40) `WorkerConfiguration` | Disk
144 | (40) `WorkerConfiguration` | Network
184 | (40) `WorkerConfiguration` | Rendering
224 | (40) `WorkerConfiguration` | LevelDB
264 | (40) `WorkerConfiguration` | LevelDBCompaction
304 | (40) `WorkerConfiguration` | ConnectedStorage
344 | (40) `WorkerConfiguration` | Watchdog


### `AnimatePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (4) `AnimatePacket::Action` | mAction
52 | (4) `float` | mData


### `AutoCompleteOption`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | visualText
32 | (32) `std::string` | tabCompleteText
64 | (32) `std::string` | description
96 | (4) `AutoCompleteOption::CursorPos` | matchStart
100 | (4) `AutoCompleteOption::CursorPos` | matchLength
104 | (4) `AutoCompleteOption::CursorPos` | commandLineMatchStart
108 | (4) `AutoCompleteOption::CursorPos` | commandLineMatchOffset
112 | (8) `CommandItem` | item
120 | (1) `bool` | highlight


### `AutomaticID<Dimension,int>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | runtimeID


### `ActorDamageByBlockSource`
Offset | Type | Name
-|-|-|-
0 | (16) `ActorDamageSource` | baseclass_0
16 | (8) `const Block *` | mBlock


### `ActorDefinitionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorDefinitionGroup *` | mGroup
8 | (8) `ActorDefinition *` | mPtr


### `ActorLink::List`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<ActorLink>` | baseclass_0


### `ActorFallPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mEntityID
48 | (4) `float` | mDistance
52 | (1) `bool` | mOutOfWorld


### `ActionEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mActionId
4 | (4) `ActionEvent::ActionState` | mActionState
8 | (1) `bool` | mIsExclusive
9 | (1) `FocusImpact` | mFocusImpact


### `ActorFlagComponent<PersistentFlag>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `ActorDefinition::parseAttributes::$6BAFC40004D8C3E8E3A064C81F470774`
Offset | Type | Name
-|-|-|-
0 | (8) `__gnu_cxx::__normal_iterator<std::string *,std::vector<std::string> > *` | iter
8 | (8) `ActorDefinition *` | this
16 | (8) `ActorDefinitionDescriptor *` | desc


### `ActorDefinition::parse::$AAE48C984D581248ECCF7B3C863DEC20`
Offset | Type | Name
-|-|-|-
0 | (8) `std::string *` | name
8 | (8) `Json::Value *` | root
16 | (8) `ActorDefinition *` | this
24 | (8) `ActorDefinitionDescriptor *` | desc


### `ActorDefinitionAttribute`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (4) `float` | min
36 | (4) `float` | max
40 | (8) `FloatRange` | value


### `ActorDefinitionDescriptor`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<Util::HashString,Util::HashString::HashFunc,std::equal_to<Util::HashString>,std::allocator<Util::HashString> >` | mComponentNames
56 | (40) `IdentifierDescription` | mIdentifier
96 | (40) `RuntimeIdentifierDescription` | mRuntimeIdentifier
136 | (16) `IsSpawnableDescription` | mIsSpawnable
152 | (16) `IsSummonableDescription` | mIsSummonable
168 | (16) `IsExperimentalDescription` | mIsExperimental
184 | (64) `AnimationsDescription` | mAnimationsDescription
248 | (32) `AnimationScriptsDescription` | mAnimationScriptsDescription
280 | (24) `std::vector<GoalDefinition>` | mGoalDefinitions
304 | (24) `std::vector<ActorDefinitionAttribute>` | mAttributes
328 | (56) `std::unordered_map<std::string,DefinitionEvent>` | mEventHandlers
384 | (136) `DefinitionInstanceGroup` | mComponentDefinitionGroup
520 | (8) `Description *` | mAttack
528 | (8) `Description *` | mMobEffects
536 | (8) `Description *` | mAmbientSoundInterval
544 | (8) `Description *` | mCanClimb
552 | (8) `Description *` | mCanFly
560 | (8) `Description *` | mCanPowerJump
568 | (8) `Description *` | mCollisionBox
576 | (8) `Description *` | mColor2
584 | (8) `Description *` | mColor
592 | (8) `Description *` | mDefaultLookAngle
600 | (8) `Description *` | mDyeable
608 | (8) `Description *` | mEquipmentTable
616 | (8) `Description *` | mFamilyTypes
624 | (8) `Description *` | mFireImmune
632 | (8) `Description *` | mFloatsInLiquid
640 | (8) `Description *` | mFlyingSpeed
648 | (8) `Description *` | mFootSize
656 | (8) `Description *` | mFrictionModifier
664 | (8) `Description *` | mSurfaceOffset
672 | (8) `Description *` | mIsBaby
680 | (8) `Description *` | mIsCharged
688 | (8) `Description *` | mIsChested
696 | (8) `Description *` | mIsHiddenWhenInvisible
704 | (8) `Description *` | mIsIgnited
712 | (8) `Description *` | mIsIllagerCaptain
720 | (8) `Description *` | mIsSaddled
728 | (8) `Description *` | mIsShaking
736 | (8) `Description *` | mIsSheared
744 | (8) `Description *` | mIsStunned
752 | (8) `Description *` | mIsStackable
760 | (8) `Description *` | mIsTamed
768 | (8) `Description *` | mItemControllable
776 | (8) `Description *` | mLootTable
784 | (8) `Description *` | mPushthrough
792 | (8) `Description *` | mScale
800 | (8) `Description *` | mSoundVolume
808 | (8) `Description *` | mWalkAnimSpeedMultiplier
816 | (8) `Description *` | mWantsJockey
824 | (8) `Description *` | mWASDControlled
832 | (8) `Description *` | mOnDeath
840 | (8) `Description *` | mOnFriendlyAnger
848 | (8) `Description *` | mOnHurtByPlayer
856 | (8) `Description *` | mOnHurt
864 | (8) `Description *` | mOnIgnite
872 | (8) `Description *` | mOnStartLanding
880 | (8) `Description *` | mOnStartTakeoff
888 | (8) `Description *` | mOnTargetAcquired
896 | (8) `Description *` | mOnTargetEscape
904 | (8) `Description *` | mOnWakeWithOwner
912 | (8) `Description *` | mAmphibiousMoveControl
920 | (8) `Description *` | mAngry
928 | (8) `Description *` | mBehavior
936 | (8) `Description *` | mBreakBlocks
944 | (8) `Description *` | mBreakDoorAnnotation
952 | (8) `Description *` | mBucketable
960 | (8) `Description *` | mCommandBlock
968 | (8) `Description *` | mContainer
976 | (8) `Description *` | mDespawn
984 | (8) `Description *` | mDweller
992 | (8) `Description *` | mGenericMoveControl
1000 | (8) `Description *` | mGlideMoveControl
1008 | (8) `Description *` | mHide
1016 | (8) `Description *` | mIllagerBeastBlocked
1024 | (8) `Description *` | mManagedWanderingTrader
1032 | (8) `Description *` | mMarkVariant
1040 | (8) `Description *` | mMoveControl
1048 | (8) `Description *` | mDolphinSwimControl
1056 | (8) `Description *` | mFlyControl
1064 | (8) `Description *` | mHopControl
1072 | (8) `Description *` | mHoverControl
1080 | (8) `Description *` | mSwimControl
1088 | (8) `Description *` | mNameable
1096 | (8) `Description *` | mWallClimberNavigation
1104 | (8) `Description *` | mFloatNavigation
1112 | (8) `Description *` | mFlyingNavigation
1120 | (8) `Description *` | mHoverNavigation
1128 | (8) `Description *` | mGenericNavigation
1136 | (8) `Description *` | mWaterboundNavigation
1144 | (8) `Description *` | mNavigation
1152 | (8) `Description *` | mPersistent
1160 | (8) `Description *` | mPreferredPath
1168 | (8) `Description *` | mProjectile
1176 | (8) `Description *` | mPushable
1184 | (8) `Description *` | mRaidTrigger
1192 | (8) `Description *` | mRailActivator
1200 | (8) `Description *` | mRideable
1208 | (8) `Description *` | mShooter
1216 | (8) `Description *` | mSittable
1224 | (8) `Description *` | mSkinID
1232 | (8) `Description *` | mSlimeMoveControl
1240 | (8) `Description *` | mSpawnEntity
1248 | (8) `Description *` | mStrength
1256 | (8) `Description *` | mTags
1264 | (8) `Description *` | mTameable
1272 | (8) `Description *` | mTrail
1280 | (8) `Description *` | mTrusting
1288 | (8) `Description *` | mTargetNearby
1296 | (8) `Description *` | mTeleport
1304 | (8) `Description *` | mTickWorld
1312 | (8) `Description *` | mTimer
1320 | (8) `Description *` | mTradeResupply
1328 | (8) `Description *` | mTrust
1336 | (8) `Description *` | mEconomyTradeable
1344 | (8) `Description *` | mTransformation
1352 | (8) `Description *` | mVariant
1360 | (8) `Description *` | mWaterMovement
1368 | (8) `Description *` | mDynamicJumpControl
1376 | (8) `Description *` | mJumpControl
1384 | (8) `Description *` | mOpenDoorAnnotation
1392 | (8) `Description *` | mNpc
1400 | (8) `Description *` | mTripodCamera


### `AnimationsDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (56) `std::unordered_map<HashedString,HashedString>` | mActorAnimationMap


### `AnimationScriptsDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (24) `std::vector<std::pair<HashedString,ExpressionNode>>` | mAnimateScript


### `ActorSkeletalAnimationPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ActorAnimationInfo>` | mActorAnimationInfoPtr


### `ActorAnimationControllerPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ActorAnimationControllerInfo>` | mActorAnimationControllerInfoPtr


### `ActorFactoryData`
Offset | Type | Name
-|-|-|-
0 | (168) `ActorDefinitionIdentifier` | mIdentifier
168 | (168) `ActorDefinitionIdentifier` | mBaseIdentifier
336 | (1) `bool` | mAllowSummon
344 | (8) `ActorFactoryFunction` | mFactory
352 | (1) `bool` | mIsExperimental
356 | (4) `ActorType` | mActorType
360 | (4) `float` | mWalkAnimSpeed


### `ActorInteraction::OnInteraction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void ()>::_Invoker_type` | _M_invoker


### `ActorDataMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,ActorFactoryData>::_Hashtable` | _M_h


### `ActorDamageByChildActorSource`
Offset | Type | Name
-|-|-|-
0 | (80) `ActorDamageByActorSource` | baseclass_0
80 | (1) `bool` | mDamagingActorIsWorldBuilder
81 | (1) `bool` | mDamagingActorIsCreative
88 | (8) `ActorUniqueID` | mDamagingActorId
96 | (4) `ActorType` | mDamagingActorType
100 | (4) `ActorCategory` | mDamagingActorCategories
104 | (32) `std::string` | mDamagingActorNameTag


### `ActorParticleEffect`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | mParticleEffectName
40 | (40) `HashedString` | mLocatorName
80 | (128) `ExpressionNode` | mInitializationScripts
208 | (1) `bool` | mBindToActor


### `ActorSoundEffect`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | mSoundEffectName


### `ActorParticleEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (216) `ActorParticleEffect` | mParticleEffect
216 | (4) `float` | mTime


### `ActorSoundEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ActorSoundEffect` | mSoundEffect
40 | (4) `float` | mTime


### `ActorAnimationEvent`
Offset | Type | Name
-|-|-|-
0 | (128) `ExpressionNode` | mExpression
128 | (40) `HashedString` | mCommand
168 | (4) `CurrentCmdVersion` | mCommandVersion
176 | (32) `std::string` | mEvent
208 | (4) `float` | mTime


### `ActorAnimationControllerGroupParseMetaData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorAnimationControllerGroup *` | mActorAnimationControllerGroup
8 | (4) `CurrentCmdVersion` | mCurrentCommandVersion


### `ActorAnimationGroupParseMetaData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorAnimationGroup *` | mActorAnimationGroup
8 | (4) `CurrentCmdVersion` | mCurrentCommandVersion


### `AnimationComponentID`
Offset | Type | Name
-|-|-|-
0 | (8) `AnimationComponentID::$9FA17E7D7DCEEBB7713B7193F23D45BD` | mData


### `AnimationComponentID::$9FA17E7D7DCEEBB7713B7193F23D45BD`
Offset | Type | Name
-|-|-|-
0 | (8) `AnimationComponentID::$9FA17E7D7DCEEBB7713B7193F23D45BD::$65CCC15F238CE74967BBE3340E99BC94` | _anon_0
1 | (8) `uint64_t` | mAllBits


### `AnimationComponentID::$9FA17E7D7DCEEBB7713B7193F23D45BD::$65CCC15F238CE74967BBE3340E99BC94`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | _bf_0


### `ActorBlockSyncMessage`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mEntityUniqueID
8 | (4) `ActorBlockSyncMessage::MessageId` | mMessage


### `AttributeInstance`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$AttributeInstance
8 | (8) `BaseAttributeMap *` | mAttributeMap
16 | (8) `const Attribute *` | mAttribute
24 | (24) `std::vector<AttributeModifier>` | mModifierList
48 | (24) `std::vector<TemporalAttributeBuff>` | mTemporalBuffs
72 | (24) `std::vector<AttributeInstanceHandle>` | mListeners
96 | (16) `std::shared_ptr<AttributeInstanceDelegate>` | mDelegate
112 | (12) `AttributeInstance::$DA28B55148B6D6964D71615272628344` | _anon_0
124 | (12) `AttributeInstance::$DA28B55148B6D6964D71615272628344` | _anon_1


### `AttributeInstance::$DA28B55148B6D6964D71615272628344`
Offset | Type | Name
-|-|-|-
0 | (12) `AttributeInstance::$DA28B55148B6D6964D71615272628344::$CBA65015C8EB93BF42E3CAB5E288923D` | _anon_0
1 | (12) `AttributeInstance::$DA28B55148B6D6964D71615272628344::$F2BAED747831077325874A72B2A106F3` | _anon_1


### `AttributeInstance::$DA28B55148B6D6964D71615272628344::$CBA65015C8EB93BF42E3CAB5E288923D`
Offset | Type | Name
-|-|-|-
0 | (12) `float[3]` | mDefaultValues


### `AttributeInstance::$DA28B55148B6D6964D71615272628344::$F2BAED747831077325874A72B2A106F3`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mDefaultMinValue
4 | (4) `float` | mDefaultMaxValue
8 | (4) `float` | mDefaultValue


### `ActorInteraction`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mInteractText
32 | (32) `ActorInteraction::OnInteraction` | mInteraction
64 | (1) `bool` | mNoCapture


### `AttributeCollection`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<StringKey,Attribute *>` | mAttributesMap
56 | (4) `uint32_t` | mIDValueIndex


### `AttributeInstance::ModifierVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<AttributeModifier>` | baseclass_0


### `AttributeInstanceHandle`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mAttributeID
8 | (8) `BaseAttributeMap *` | mAttributeMap


### `AttributeBuffInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `AttributeBuffType` | type
8 | (8) `ActorUniqueID` | source


### `AttributeBuff:672`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$AttributeBuff
8 | (4) `float` | mAmount
12 | (4) `_BYTE[4]` | gapC
16 | (16) `AttributeBuffInfo` | mInfo
32 | (16) `std::shared_ptr<Amplifier>` | mValueAmplifier
48 | (16) `std::shared_ptr<Amplifier>` | mDurationAmplifier
64 | (4) `float` | mScale
68 | (4) `int` | mAmplification
72 | (8) `size_t` | mId
80 | (4) `int` | mOperand


### `AnvilDamagePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mDamage
40 | (12) `NetworkBlockPosition` | mPosition


### `AttributeBuff`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$AttributeBuff
8 | (4) `float` | mAmount
16 | (16) `AttributeBuffInfo` | mInfo
32 | (16) `std::shared_ptr<Amplifier>` | mValueAmplifier
48 | (16) `std::shared_ptr<Amplifier>` | mDurationAmplifier
64 | (4) `float` | mScale
68 | (4) `int` | mAmplification
72 | (8) `size_t` | mId
80 | (4) `int` | mOperand


### `ActorMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ActorUniqueID,Actor *>::_Hashtable` | _M_h


### `ArbitraryBiomeComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (16) `Json::Value` | mPayload


### `AABBContactPoint`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mNormalIndex
4 | (4) `float` | mSignedPenetration
8 | (12) `Vec3` | mNormal


### `ActorDefinitionFeedItem`
Offset | Type | Name
-|-|-|-
0 | (8) `const Item *` | mItem
8 | (4) `float` | mGrowth


### `AppConfigs::LeaveGameCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (SceneStack &,SceneFactory &)>::_Invoker_type` | _M_invoker


### `AutomationClientConnectPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `WebSocketPacketData` | mWebSocketData


### `AddRiderComponent`
Offset | Type | Name
-|-|-|-
0 | (168) `ActorDefinitionIdentifier` | mRiderType


### `AnimationValueCurveKeyFrame`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mInputValue
4 | (4) `float` | mOutputValue


### `AgentCommand::AgentCommandFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<AgentCommands::Command> (Player &)>::_Invoker_type` | _M_invoker


### `ActorSpawnRuleBase::SpawnRulesHandler`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const std::string &,int,BiomeFilterGroup &,MobSpawnRules &)>::_Invoker_type` | _M_invoker


### `addrinfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | ai_flags
4 | (4) `int` | ai_family
8 | (4) `int` | ai_socktype
12 | (4) `int` | ai_protocol
16 | (4) `socklen_t` | ai_addrlen
24 | (8) `sockaddr *` | ai_addr
32 | (8) `char *` | ai_canonname
40 | (8) `addrinfo *` | ai_next


### `ArmorStand::Pose`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mHeadPose
12 | (12) `Vec3` | mBodyPose
24 | (12) `Vec3` | mRightArmPose
36 | (12) `Vec3` | mLeftArmPose
48 | (12) `Vec3` | mRightLegPose
60 | (12) `Vec3` | mLeftLegPose
72 | (12) `Vec3` | mRightItemPose


### `Attribute`
Offset | Type | Name
-|-|-|-
0 | (1) `RedefinitionMode` | mRedefinitionMode
1 | (1) `bool` | mSyncable
4 | (4) `uint32_t` | mIDValue
8 | (40) `HashedString` | mName


### `ArmorItem::ArmorMaterial`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDurabilityMultiplier
4 | (16) `int[4]` | slotProtections
20 | (4) `int` | mEnchantmentValue


### `ActorMapping`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mNamespace
32 | (32) `std::string` | mPrimaryName
64 | (32) `std::string` | mAlternateName
96 | (40) `HashedString` | mCanonicalName


### `AvailableCommandsPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<std::string>` | mEnumValues
64 | (24) `std::vector<std::string>` | mPostfixes
88 | (24) `std::vector<AvailableCommandsPacket::EnumData>` | mEnums
112 | (24) `std::vector<AvailableCommandsPacket::CommandData>` | mCommands
136 | (24) `std::vector<AvailableCommandsPacket::SoftEnumData>` | mSoftEnums
160 | (24) `std::vector<AvailableCommandsPacket::ConstrainedValueData>` | mConstraints


### `AvailableActorIdentifiersPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<ActorInfo>` | mIdentifierList


### `AvailableCommandsPacket::EnumData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (24) `std::vector<unsigned int>` | values


### `AvailableCommandsPacket::SoftEnumData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (24) `std::vector<std::string>` | values


### `Automation::AutomationClient`
Offset | Type | Name
-|-|-|-
0 | (8) `UriListener` | baseclass_0


### `ActorDefinitionDiffList`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorDefinitionGroup *` | mDefinitions
8 | (24) `std::vector<std::pair<bool,ActorDefinitionPtr>>` | mDefinitionStack
32 | (8) `Unique<ActorDefinitionDescriptor>` | mChangedDescription
40 | (1) `bool` | mChanged
48 | (136) `DefinitionInstanceGroup` | mAddedDefinitionGroup
184 | (136) `DefinitionInstanceGroup` | mRemovedDefinitionGroup


### `Actor::baseTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Actor::spawnDeathParticles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Actor::spawnTrailBubbles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ActorFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (16) `std::shared_ptr<IEntityInitializer>` | mEntityInitializer
24 | (64) `ActorComponentFactory` | mComponentFactory


### `ActorComponentFactory`
Offset | Type | Name
-|-|-|-
0 | (58) `EntityComponentFactory:464` | baseclass_0
58 | (1) `bool` | mGenerateDoc


### `ActorFilterGroup::LegacyMapping`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterGroup::CollectionType` | mType
8 | (8) `const FilterTest::Definition *` | mFilterDef
16 | (2) `FilterSubject` | mSubject
18 | (2) `FilterOperator` | mOperator
20 | (4) `ActorFilterGroup::Processing` | mProcess


### `ArmorStand::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Agent::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ActorAnimationControllerGroup`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<HashedString,std::shared_ptr<ActorAnimationControllerInfo>>` | mAnimationControllers


### `ActorAnimationGroup`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<HashedString,std::shared_ptr<ActorAnimationInfo>>` | mAnimations
56 | (40) `Bedrock::Threading::Mutex` | mActorAnimationLock
96 | (1) `bool` | mIsExperimental


### `AnimationComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mLastReloadInitTimeStamp
8 | (8) `const ActorAnimationControllerStatePlayer *` | mCurrentAnimationControllerStatePlayer
16 | (24) `std::vector<std::unique_ptr<ActorAnimationPlayer>>` | mComponentAnimationPlayers
40 | (24) `std::vector<std::shared_ptr<ActorAnimationControllerInfo>>` | mOwnedAnimationControllers
64 | (8) `std::unique_ptr<std::unordered_map<HashedString,ModelPartLocator>>` | mModelPartLocators
72 | (152) `RenderParams` | mRenderParams
224 | (8) `ActorAnimationPlayer *` | mPlaySingleAnimation
232 | (8) `AnimationResourceDefinitionMap *` | mAnimationResourceDefinitionMap
240 | (8) `const ActorParticleEffectMap *` | mParticleEffectMap
248 | (32) `std::function<void (ActorAnimationPlayer &)>` | mAnimationComponentInitFunction
280 | (24) `std::vector<AnimationComponent::ChildAnimationComponentInfo>` | mChildAnimationComponents
304 | (4) `int` | mBoneOrientationGroupIndexToUseForPosing
312 | (56) `std::unordered_map<SkeletalHierarchyIndex,std::vector<BoneOrientation>>` | mBoneOrientations
368 | (1) `bool` | mAnimationComponentInitialized
372 | (4) `AnimationComponentGroup` | mAnimationComponentGroup
376 | (8) `AnimationComponentID` | mOwnerUUID
384 | (8) `int64_t` | mLastUpdateFrame


### `AnimationComponent::setInitializedScriptsRun::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Ability`
Offset | Type | Name
-|-|-|-
0 | (1) `Ability::Type` | mType
4 | (4) `Ability::Value` | mValue
8 | (1) `Ability::Options` | mOptions


### `Arrow::normalTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `AttributeModifier`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$AttributeModifier
8 | (4) `float` | mAmount
12 | (4) `int` | mOperation
16 | (4) `int` | mOperand
24 | (32) `std::string` | mName
56 | (16) `mce::UUID` | mId
72 | (1) `bool` | mSerialize


### `ActorHasEquipmentTest`
Offset | Type | Name
-|-|-|-
0 | (12) `FilterTest:96` | baseclass_0
12 | (4) `int` | mEquipmentSlot
16 | (4) `int` | mItemID
20 | (4) `int` | mItemAux


### `ActorUndergroundTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorUnderwaterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorInWaterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorInWaterOrRainTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorOnGroundTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorInLavaTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorInCloudsTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorOnLadderTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasComponentTest`
Offset | Type | Name
-|-|-|-
0 | (56) `SimpleHashStringFilterTest` | baseclass_0


### `ActorIsFamilyTest`
Offset | Type | Name
-|-|-|-
0 | (56) `SimpleHashStringFilterTest` | baseclass_0


### `ActorHasAbilityTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorHasDamageTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorIsColorTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorIsOwnerTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsTargetTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsImmobileTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasTargetTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsLeashedToTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsMovingTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsSneakingTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsClimbingTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsRidingTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorRiderCountTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorInCaravanTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsLeashedTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsVariantTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorIsMarkVariantTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorIsSkinIDTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `ActorHasTagTest`
Offset | Type | Name
-|-|-|-
0 | (56) `SimpleHashStringFilterTest` | baseclass_0


### `ActorTrustsSubjectTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsAvoidingMobsTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorInVillageTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsVisibleTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasMobEffect`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (8) `MobEffect *` | mMobEffect


### `ActorIsSleepingTest`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `AutomaticID<Dimension,int>::SELF`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | runtimeID


### `ActorTerrainInterlockData`
Offset | Type | Name
-|-|-|-
0 | (1) `ActorTerrainInterlockData::VisibilityState` | mRenderVisibilityState
8 | (8) `std::chrono::time_point<std::chrono::_V2::system_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >` | mCreationTime
16 | (1) `bool` | mHasBeenDelayedDeleted


### `Automation::Response`
Offset | Type | Name
-|-|-|-
0 | (1) `const Automation::Response::Type` | mType
8 | (32) `const std::string` | mMessage
40 | (32) `const std::string` | mId


### `Automation::MessageHeader`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mRequestId
32 | (1) `Automation::MessagePurpose` | mMessagePurpose
36 | (4) `int` | mVersion


### `AppConfigs`
```
struct AppConfigs
{
  int (**_vptr$AppConfigs)(void);
  AppConfigs::LeaveGameCallback mLeaveGameCallback;
};

```

### `Actor`
```
struct Actor
{
  int (**_vptr$Actor)(void);
  OwnerPtr<EntityId> mEntity;
  Actor::InitializationMethod mInitMethod;
  std::string mCustomInitEventName;
  VariantParameterList mInitParams;
  bool mForceInitMethodToSpawnOnReload;
  bool mRequiresReload;
  DimensionType mDimensionId;
  bool mAdded;
  ActorDefinitionGroup *mDefinitions;
  Unique<ActorDefinitionDescriptor> mCurrentDescription;
  ActorUniqueID mUniqueID;
  Shared<RopeSystem> mLeashRopeSystem;
  Vec2 mRot;
  Vec2 mRotPrev;
  float mSwimAmount;
  float mSwimPrev;
  ChunkPos mChunkPos;
  Vec3 mRenderPos;
  Vec2 mRenderRot;
  int mAmbientSoundTime;
  int mLastHurtByPlayerTime;
  ActorCategory mCategories;
  SynchedActorData mEntityData;
  Unique<SpatialActorNetworkData> mNetworkData;
  Vec3 mSentDelta;
  float mScale;
  float mScalePrev;
  HashType64 mNameTagHash;
  bool mOnGround;
  bool mWasOnGround;
  bool mHorizontalCollision;
  bool mVerticalCollision;
  bool mCollision;
  const Block *mInsideBlock;
  BlockPos mInsideBlockPos;
  float mFallDistance;
  bool mIgnoreLighting;
  bool mFilterLighting;
  Color mTintColor;
  Color mTintColor2;
  float mStepSoundVolume;
  float mStepSoundPitch;
  AABB *mLastHitBB;
  std::vector<AABB> mSubBBs;
  float mTerrainSurfaceOffset;
  float mHeightOffset;
  float mExplosionOffset;
  float mShadowOffset;
  float mMaxAutoStep;
  float mPushthrough;
  float mWalkDistPrev;
  float mWalkDist;
  float mMoveDist;
  int mNextStep;
  float mBlockMovementSlowdownMultiplier;
  bool mImmobile;
  bool mWasInWater;
  bool mHasEnteredWater;
  bool mHeadInWater;
  bool mIsWet;
  Vec2 mSlideOffset;
  Vec3 mHeadOffset;
  Vec3 mEyeOffset;
  Vec3 mBreathingOffset;
  Vec3 mMouthOffset;
  Vec3 mDropOffset;
  bool mFirstTick;
  int mTickCount;
  int mInvulnerableTime;
  int mLastHealth;
  bool mFallDamageImmune;
  bool mHurtMarked;
  bool mWasHurtLastFrame;
  bool mInvulnerable;
  bool mAlwaysFireImmune;
  int mOnFire;
  int mFlameTexFrameIndex;
  float mFlameFrameIncrementTime;
  bool mOnHotBlock;
  int mClientSideFireTransitionStartTick;
  bool mClientSideFireTransitionLatch;
  int mPortalCooldown;
  BlockPos mPortalBlockPos;
  PortalAxis mPortalEntranceAxis;
  int mInsidePortalTime;
  std::vector<ActorUniqueID> mRiderIDs;
  std::vector<ActorUniqueID> mRiderIDsToRemove;
  ActorUniqueID mRidingID;
  ActorUniqueID mRidingPrevID;
  ActorUniqueID mPushedByID;
  bool mInheritRotationWhenRiding;
  bool mRidersChanged;
  bool mBlocksBuilding;
  bool mUsesOneWayCollision;
  bool mForcedLoading;
  bool mPrevPosRotSetThisTick;
  bool mTeleportedThisTick;
  bool mForceSendMotionPacket;
  float mSoundVolume;
  int mShakeTime;
  float mWalkAnimSpeedMultiplier;
  float mWalkAnimSpeedO;
  float mWalkAnimSpeed;
  float mWalkAnimPos;
  ActorUniqueID mLegacyUniqueID;
  bool mHighlightedThisFrame;
  bool mInitialized;
  BlockSource *mRegion;
  Dimension *mDimension;
  Level *mLevel;
  HashedString mActorRendererId;
  HashedString mActorRendererIdThatAnimationComponentWasInitializedWith;
  bool mChanged;
  bool mRemoved;
  bool mGlobal;
  bool mAutonomous;
  ActorType mActorType;
  ActorDefinitionIdentifier mActorIdentifier;
  std::unique_ptr<BaseAttributeMap> mAttributes;
  Unique<EconomyTradeableComponent> mEconomyTradeableComponent;
  std::shared_ptr<AnimationComponent> mAnimationComponent;
  AABBShapeComponent mAABBComponent;
  StateVectorComponent mStateVectorComponent;
  ActorUniqueID mTargetId;
  bool mLootDropped;
  float mRestrictRadius;
  BlockPos mRestrictCenter;
  ActorUniqueID mInLovePartner;
  MobEffectInstanceList mMobEffects;
  bool mEffectsDirty;
  bool mPersistingTrade;
  Unique<CompoundTag> mPersistingTradeOffers;
  int mPersistingTradeRiches;
  ActorRuntimeID mRuntimeID;
  Color mHurtColor;
  bool mEnforceRiderRotationLimit;
  std::unique_ptr<ActorDefinitionDiffList> mDefinitionList;
  bool mHasLimitedLife;
  int mLimitedLifeTicks;
  int mForceVisibleTimerTicks;
  std::string mFilteredNameTag;
  bool mIsStuckItem;
  float mRidingExitDistance;
  bool mIsSafeToSleepNear;
  ActorTerrainInterlockData mTerrainInterlockData;
  SimpleContainer mArmor;
  float mArmorDropChance[4];
  SimpleContainer mHand;
  float mHandDropChance[2];
  bool mIsKnockedBackOnDeath;
  std::vector<AABB> mOnewayPhysicsBlocks;
  bool mStuckInCollider;
  float mLastPenetration;
  bool mCollidableMobNear;
  bool mCollidableMob;
  bool mChainedDamageEffects;
  int mDamageNearbyMobsTick;
  bool mWasInBubbleColumn;
  bool mWasInWallLastTick;
  int mTicksInWall;
  bool mIsExperimental;
  Unique<ActionQueue> mActionQueue;
  MolangVariableMap mMolangVariables;
  CompoundTag mCachedComponentData;
  ActorUniqueID mFishingHookID;
};

```

### `AppPlatform`
```
struct __cppobj AppPlatform : IAppPlatform
{
  bool mRequestedRestart;
  bool mPointerFocusLost;
  bool mKeyboardVisible;
  bool mOnInitUriListenerRegDone;
  VRControllerType mVRControllerType;
  std::multimap<float,AppPlatformListener *> mListeners;
  Core::Observer<NetworkChangeObserver,std::mutex>::SubjectType mNetworkChangeSubject;
  std::function<void (StoragePermissionResult)> mStoragePermissionRequestResultCallback;
  AppLifecycleContext mAppLifecycleContext;
  AppFocusState mFocusState;
  std::string mShareTitle;
  std::string mShareText;
  std::string mShareUri;
  ARVRPlatform mHMDPlatform;
  std::unique_ptr<IFileAccess> mDefaultFileAccess;
  std::unique_ptr<IFileAccess> mPackageFileAccess;
  int64_t mMaximumMemoryUsage;
  BedrockEngine::CommonPlatform *mCommonPlatformShim;
  bool mMockMultiplayerActive;
  std::string mLocale;
  std::atomic<bool> mTerminating;
  int mForcedDpi;
  UIScalingRules mForcedUIScalingRules;
  bool mForceUIScalingRules;
  bool mShowLostFocusToasts;
  bool mAllowLostFocusToasts;
  bool mAreThreadsFrozen;
  bool mIsLowMemoryDevice;
  Core::HeapPathBuffer mScratchPath;
  Bedrock::Threading::Mutex mScratchPathMutex;
  std::string mDeviceID;
  std::string mDeviceIDWarning;
  std::string mLastDeviceSessionId;
  BedrockEngine::PlatformRuntimeInfo mPlatformRuntimeInfo;
  BedrockEngine::PlatformBuildInfo mPlatformBuildInfo;
};

```

### `AutoCompleteInformation`
```
struct AutoCompleteInformation
{
  std::vector<AutoCompleteOption> possibilities;
};

```

### `Automation::AutomationSession`
```
struct Automation::AutomationSession
{
  __int8 gap0[1];
};

```

### `AppPlatform_linux`
```
struct __cppobj AppPlatform_linux : AppPlatform
{
  Core::HeapPathBuffer mExternalPath;
  Core::HeapPathBuffer mHomePath;
  std::string mSystemRegion;
  std::string mGraphicsVersion;
  std::string mGraphicsRenderer;
  std::string mGraphicsVendor;
  std::string mGraphicsExtensions;
  std::string mDeviceId;
  MPMCQueue<std::function<void ()> > mMainThreadQueue;
};

```

### `AppLifecycleContext`
```
struct AppLifecycleContext
{
  bool mAppliedHasGraphicsContext;
  bool mAppliedIsCurrentlyResumed;
  bool mHasGraphicsContext;
  bool mIsCurrentlyResumed;
};

```

### `ActorEventListener`
```
struct ActorEventListener
{
  int (**_vptr$ActorEventListener)(void);
};

```

### `AgeableSystem`
```
struct __cppobj AgeableSystem : ITickingSystem
{
};

```

### `AngrySystem`
```
struct __cppobj AngrySystem : ITickingSystem
{
};

```

### `AgentCommandSystem`
```
struct __cppobj AgentCommandSystem : ITickingSystem
{
};

```

### `AreaAttackSystem`
```
struct __cppobj AreaAttackSystem : ITickingSystem
{
};

```

### `ActorDefinitionGroup`
```
struct ActorDefinitionGroup
{
  int (**_vptr$ActorDefinitionGroup)(void);
  std::unordered_set<ActorDefinitionPtr *> mRegisteredPtrs;
  ActorDefinitionGroup::ActorDefinitionList mDefinitions;
  std::unordered_map<std::string,ActorDefinitionGroup::EDLWrapper> mTemplateMap;
  ResourcePackManager *mResourcePackManager;
  Bedrock::Threading::Mutex mReferenceMutex;
  IMinecraftEventing *mEventing;
  bool mExperimentalEnabled;
  ActorComponentFactory *mComponentFactory;
};

```

### `AggregateFeature<PlaceType::Arbitrary>`
```
struct __cppobj __attribute__((aligned(8))) AggregateFeature<PlaceType::Arbitrary> : IFeature
{
  std::vector<WeakRefT<FeatureRefTraits>> mFeatureReferences;
  AggregateFeature<PlaceType::Arbitrary>::EarlyOut mEarlyOut;
};

```

### `AggregateFeature<PlaceType::Sequential>`
```
struct __cppobj __attribute__((aligned(8))) AggregateFeature<PlaceType::Sequential> : IFeature
{
  std::vector<WeakRefT<FeatureRefTraits>> mFeatureReferences;
  AggregateFeature<PlaceType::Sequential>::EarlyOut mEarlyOut;
};

```

### `AddOceanTemperatureLayer`
```
struct __cppobj AddOceanTemperatureLayer : RootLayer<BiomeTemperatureCategory>
{
};

```

### `ArmorStand`
```
struct __cppobj ArmorStand : Mob
{
  uint64_t mLastHit;
  int mPoseIndex;
  int mLastCircuitStrength;
};

```

### `AgeableDefinition`
```
struct AgeableDefinition
{
  float mSecondsAsBaby;
  std::vector<ActorDefinitionFeedItem> mFeedItems;
  std::vector<const Item *> mDropItems;
  DefinitionTrigger mOnGrowUp;
};

```

### `AgentCommands::Command`
```
struct __attribute__((aligned(8))) AgentCommands::Command
{
  int (**_vptr$Command)(void);
  Actor *mTarget;
  Player *mCommander;
  std::string mCommandName;
  bool mResult;
  bool mIsQueryResult;
};

```

### `AngryDescription`
```
struct __cppobj AngryDescription : ComponentDescription
{
  int mDuration;
  int mDurationDelta;
  bool mBroadcastAnger;
  int mBroadcastRange;
  ActorFilterGroup mBroadcastFilter;
  DefinitionTrigger mOnCalm;
  std::vector<Util::HashString> mBroadcastTargets;
};

```

### `AABBShapeComponent`
```
struct AABBShapeComponent
{
  AABB mAABB;
  Vec2 mBBDim;
};

```

### `ActorTickedComponent`
```
typedef FlagComponent<ActorTickedFlag> ActorTickedComponent;

```

### `AsyncTracker`
```
struct AsyncTracker
{
  bool isCurrentWaitingOnCall;
  bool mWasCallAborted;
  std::chrono::_V2::steady_clock::time_point operationStartTime;
  std::chrono::seconds timeLimit;
  bool mHasRetryBeenRequested;
  std::chrono::_V2::steady_clock::time_point mRetryTime;
};

```

### `AddActorPacket`
```
struct __cppobj AddActorPacket : Packet
{
  ActorLink::List mLinks;
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  SynchedActorData *mEntityData;
  SynchedActorData::DataList mData;
  ActorDefinitionIdentifier mType;
  Vec3 mPos;
  Vec3 mVelocity;
  Vec2 mRot;
  float mYHeadRotation;
  std::vector<AttributeInstanceHandle> mAttributeHandles;
  std::vector<SyncedAttribute> mAttributes;
};

```

### `AddEntityPacket`
```
struct __cppobj AddEntityPacket : EntityServerPacket
{
};

```

### `AddItemActorPacket`
```
struct __cppobj __attribute__((aligned(8))) AddItemActorPacket : Packet
{
  SynchedActorData::DataList mData;
  SynchedActorData *mEntityData;
  ActorUniqueID mId;
  ActorRuntimeID mRuntimeId;
  ItemStack mItem;
  Vec3 mPos;
  Vec3 mVelocity;
  bool mIsFromFishing;
};

```

### `AddPlayerPacket`
```
struct __cppobj AddPlayerPacket : Packet
{
  ActorLink::List mLinks;
  std::string mName;
  mce::UUID mUuid;
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  std::string mPlatformOnlineId;
  Vec3 mPos;
  Vec3 mVelocity;
  Vec2 mRot;
  float mYHeadRot;
  ItemStack mCarriedItem;
  SynchedActorData::DataList mUnpack;
  Abilities mAbilities;
  std::string mDeviceId;
  BuildPlatform mBuildPlatform;
  const SynchedActorData *mEntityData;
};

```

### `ActorPickRequestPacket`
```
struct __cppobj __attribute__((aligned(8))) ActorPickRequestPacket : Packet
{
  int64_t mID;
  byte mMaxSlots;
};

```

### `AddPaintingPacket`
```
struct __cppobj AddPaintingPacket : Packet
{
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  Vec3 mPos;
  int mDir;
  std::string mMotive;
};

```

### `AddBehaviorTreePacket`
```
struct __cppobj AddBehaviorTreePacket : Packet
{
  std::string mJsonInput;
};

```

### `AsynchronousIPResolver::ResolvedIp`
```
struct __attribute__((aligned(8))) AsynchronousIPResolver::ResolvedIp
{
  std::string ip;
  std::atomic<bool> ready;
};

```

### `AsynchronousIPResolver`
```
struct AsynchronousIPResolver
{
  std::string mUrl;
  std::shared_ptr<AsynchronousIPResolver::ResolvedIp> mResolvedIpPtr;
};

```

### `AttributeInstanceDelegate`
```
struct AttributeInstanceDelegate
{
  int (**_vptr$AttributeInstanceDelegate)(void);
  AttributeInstanceHandle mAttributeHandle;
};

```

### `AttributeInstance::$A0656A567348DC83B4AF251F24308A0F::$C619D87F19D17294536CF8D7230526DE`
```
struct AttributeInstance::$A0656A567348DC83B4AF251F24308A0F::$C619D87F19D17294536CF8D7230526DE
{
  float mCurrentValues[3];
};

```

### `AttributeInstance::$A0656A567348DC83B4AF251F24308A0F::$A2CB89779BDC0E5E7A2DBCEC2E3DC5D0`
```
struct AttributeInstance::$A0656A567348DC83B4AF251F24308A0F::$A2CB89779BDC0E5E7A2DBCEC2E3DC5D0
{
  float mCurrentMinValue;
  float mCurrentMaxValue;
  float mCurrentValue;
};

```

### `AnimatedImageData`
```
struct __attribute__((aligned(8))) AnimatedImageData
{
  persona::AnimatedTextureType mType;
  mce::Image mImage;
  float mFrames;
};

```

### `ActorInfoRegistry`
```
struct __attribute__((aligned(8))) ActorInfoRegistry
{
  std::unordered_map<std::string,unsigned int> mActorInfoNameMap;
  std::unordered_map<unsigned int,ActorInfo> mActorInfoMap;
  unsigned int mLastId;
};

```

### `AppConfigsFactory`
```
struct AppConfigsFactory
{
  __int8 gap0[1];
};

```

### `AppPlatformListener`
```
struct AppPlatformListener
{
  int (**_vptr$AppPlatformListener)(void);
  AppPlatform *platform;
};

```

### `ActorSpawnRuleGroup`
```
struct __cppobj ActorSpawnRuleGroup : ActorSpawnRuleBase
{
  std::unordered_map<std::string,int> mCategoryLookup;
};

```

### `AutonomousActorList`
```
typedef SmallSet<Actor *> AutonomousActorList;

```

### `ActorEventCoordinator`
```
struct __cppobj ActorEventCoordinator : EventCoordinator<ActorEventListener>
{
};

```

### `ActorAnimationControllerStatePlayer`
```
struct __cppobj ActorAnimationControllerStatePlayer : ActorAnimationPlayer
{
  ActorAnimationControllerPlayer *mOwner;
  std::shared_ptr<ActorAnimationControllerState> mControllerState;
  std::vector<std::unique_ptr<ActorAnimationPlayer>> mAnimationPlayers;
  const Core::Profile::CPUProfileToken mProfileToken;
};

```

### `ActorAnimationControllerInfo`
```
struct ActorAnimationControllerInfo
{
  HashedString mName;
  std::unique_ptr<ActorAnimationController> mPtr;
};

```

### `ActorAnimationPlayer`
```
struct __attribute__((aligned(8))) ActorAnimationPlayer
{
  int (**_vptr$ActorAnimationPlayer)(void);
  const HashedString mFriendlyName;
  const ExpressionNode mBlendExpression;
  bool mExpanded;
  bool mAnimationFinished;
};

```

### `AnimationResourceDefinitionMap`
```
struct AnimationResourceDefinitionMap
{
  ActorAnimationMap mActorAnimationMap;
  ActorAnimationControllerMap mActorAnimationControllerMap;
  ActorAnimateScriptArray mActorAnimateScriptArray;
};

```

### `AnimationComponent::ChildAnimationComponentInfo`
```
struct AnimationComponent::ChildAnimationComponentInfo
{
  const void *mChildObjectKey;
  MolangVariableMap mMolangVariableMap;
  std::shared_ptr<AnimationComponent> mChildAnimationComponent;
};

```

### `AABBBucket`
```
struct __attribute__((aligned(8))) AABBBucket
{
  AABB mBucketBounds;
  int mCachedTicks;
  std::vector<RopeAABB> mBBs;
  bool mDirty;
  bool mNeedsFinalize;
};

```

### `AABBPred`
```
struct AABBPred
{
  __int8 gap0[1];
};

```

### `ActorAnimationMap`
```
typedef std::unordered_map<StringKey,ActorSkeletalAnimationPtr> ActorAnimationMap;

```

### `ActorAnimationControllerMap`
```
typedef std::unordered_map<StringKey,ActorAnimationControllerPtr> ActorAnimationControllerMap;

```

### `ActorAnimateScriptArray`
```
typedef std::vector<std::pair<HashedString,ExpressionNode>> ActorAnimateScriptArray;

```

### `ActorDefinition`
```
struct ActorDefinition
{
  ActorDefinitionDescriptor mDescription;
  IdentifierDescription mIdentifier;
  RuntimeIdentifierDescription mRuntimeIdentifier;
  IsSpawnableDescription mIsSpawnable;
  IsSummonableDescription mIsSummonable;
  IsExperimentalDescription mIsExperimental;
  AnimationsDescription mAnimationsDescription;
  AnimationScriptsDescription mAnimationScriptsDescription;
  std::vector<GoalDefinition> mGoalDefinitions;
  std::vector<ActorDefinitionAttribute> mAttributes;
  std::unordered_map<std::string,DefinitionEvent> mEventHandlers;
  AnimationResourceDefinitionMap mAnimationResourceDefinitionMap;
  AttackDescription mAttack;
  MobEffectChangeDescription mMobEffects;
  AmbientSoundIntervalDescription mAmbientSoundInterval;
  CanClimbDescription mCanClimb;
  CanFlyDescription mCanFly;
  CanPowerJumpDescription mCanPowerJump;
  CollisionBoxDescription mCollisionBox;
  Color2Description mColor2;
  ColorDescription mColor;
  DefaultLookAngleDescription mDefaultLookAngle;
  DyeableDescription mDyeable;
  EquipmentTableDescription mEquipmentTable;
  FamilyTypeDescription mFamilyTypes;
  FireImmuneDescription mFireImmune;
  FloatsInLiquidDescription mFloatsInLiquid;
  FlyingSpeedDescription mFlyingSpeed;
  FootSizeDescription mFootSize;
  FrictionModifierDescription mFrictionModifier;
  GroundOffsetDescription mSurfaceOffset;
  IsBabyDescription mIsBaby;
  IsChargedDescription mIsCharged;
  IsChestedDescription mIsChested;
  IsHiddenWhenInvisibleDescription mIsHiddenWhenInvisible;
  IsIgnitedDescription mIsIgnited;
  IsIllagerCaptainDescription mIsIllagerCaptain;
  IsSaddledDescription mIsSaddled;
  IsShakingDescription mIsShaking;
  IsShearedDescription mIsSheared;
  IsStunnedDescription mIsStunned;
  IsStackableDescription mIsStackable;
  IsTamedDescription mIsTamed;
  ItemControlDescription mItemControllable;
  LootTableDescription mLootTable;
  PushThroughDescription mPushthrough;
  ScaleDescription mScale;
  SoundVolumeDescription mSoundVolume;
  WalkAnimationSpeedDescription mWalkAnimSpeedMultiplier;
  WantsJockeyDescription mWantsJockey;
  WASDControlledDescription mWASDControlled;
  OnDeathDescription mOnDeath;
  OnFriendlyAngerDescription mOnFriendlyAnger;
  OnHurtByPlayerDescription mOnHurtByPlayer;
  OnHurtDescription mOnHurt;
  OnIgniteDescription mOnIgnite;
  OnStartLandingDescription mOnStartLanding;
  OnStartTakeoffDescription mOnStartTakeoff;
  OnTargetAcquiredDescription mOnTargetAcquired;
  OnTargetEscapeDescription mOnTargetEscape;
  OnWakeWithOwnerDescription mOnWakeWithOwner;
  AmphibiousMoveControlDescription mAmphibiousMoveControl;
  AngryDescription mAngry;
  BehaviorTreeDescription mBehavior;
  BreakBlocksDescription mBreakBlocks;
  BreakDoorAnnotationDescription mBreakDoorAnnotation;
  BucketableDescription mBucketable;
  CommandBlockDescription mCommandBlock;
  ContainerDescription mContainer;
  DespawnDescription mDespawn;
  DwellerDescription mDweller;
  GenericMoveControlDescription mGenericMoveControl;
  GlideMoveControlDescription mGlideMoveControl;
  HideDescription mHide;
  IllagerBeastBlockedDescription mIllagerBeastBlocked;
  ManagedWanderingTraderDescription mManagedWanderingTrader;
  MarkVariantDescription mMarkVariant;
  MoveControlBasicDescription mMoveControl;
  MoveControlDolphinDescription mDolphinSwimControl;
  MoveControlFlyDescription mFlyControl;
  MoveControlSkipDescription mHopControl;
  MoveControlHoverDescription mHoverControl;
  MoveControlSwayDescription mSwimControl;
  NameableDescription mNameable;
  NavigationClimbDescription mWallClimberNavigation;
  NavigationFloatDescription mFloatNavigation;
  NavigationFlyDescription mFlyingNavigation;
  NavigationHoverDescription mHoverNavigation;
  NavigationGenericDescription mGenericNavigation;
  NavigationSwimDescription mWaterboundNavigation;
  NavigationWalkDescription mNavigation;
  PersistentDescription mPersistent;
  PreferredPathDescription mPreferredPath;
  ProjectileDescription mProjectile;
  PushableDescription mPushable;
  RaidTriggerDescription mRaidTrigger;
  RailActivatorDescription mRailActivator;
  RideableDescription mRideable;
  ShooterDescription mShooter;
  SittableDescription mSittable;
  SkinIDDescription mSkinID;
  SlimeMoveControlDescription mSlimeMoveControl;
  SpawnActorDescription mSpawnEntity;
  StrengthDescription mStrength;
  TagsDescription mTags;
  TameableDescription mTameable;
  TrailDescription mTrail;
  TrustingDescription mTrusting;
  TargetNearbyDescription mTargetNearby;
  TeleportDescription mTeleport;
  TickWorldDescription mTickWorld;
  TimerDescription mTimer;
  TradeResupplyDescription mTradeResupply;
  TrustDescription mTrust;
  EconomyTradeableDescription mEconomyTradeable;
  TransformationDescription mTransformation;
  VariantDescription mVariant;
  WaterMovementDescription mWaterMovement;
  DynamicJumpControlDescription mDynamicJumpControl;
  JumpControlDescription mJumpControl;
  OpenDoorAnnotationDescription mOpenDoorAnnotation;
  NpcDescription mNpc;
  TripodCameraDescription mTripodCamera;
};

```

### `AttackDescription`
```
struct __cppobj __attribute__((aligned(8))) AttackDescription : AttributeDescription
{
  FloatRange mDamage;
  std::string mEffectName;
  float mEffectDuration;
};

```

### `AmbientSoundIntervalDescription`
```
struct __cppobj AmbientSoundIntervalDescription : PropertyDescription
{
  float mValue;
  float mRange;
  std::string mEventName;
};

```

### `AmphibiousMoveControlDescription`
```
struct __cppobj __attribute__((aligned(8))) AmphibiousMoveControlDescription : MoveControlDescription
{
};

```

### `AttributeDescription`
```
struct __cppobj AttributeDescription : Description
{
};

```

### `ActionQueue`
```
struct ActionQueue
{
  std::deque<ActionEvent> mQueue;
};

```

### `AnvilContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) AnvilContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `AutomationPlayerCommandOrigin`
```
struct __cppobj AutomationPlayerCommandOrigin : PlayerCommandOrigin
{
  std::string mRequestId;
  CommandPermissionLevel mPlayerPermission;
  NetworkIdentifier mSource;
};

```

### `ApplyItemBinding`
```
struct __cppobj ApplyItemBinding : ScriptServerEntity
{
};

```

### `ApplyLegacyEntityBinding`
```
struct __cppobj ApplyLegacyEntityBinding : ScriptServerEntity
{
};

```

### `AtlasItemManager`
```
struct AtlasItemManager
{
  std::unordered_map<std::string,TextureAtlasItem> mTextureAtlasItems;
};

```

### `ActorAnimationInfo`
```
struct ActorAnimationInfo
{
  HashedString mName;
  std::unique_ptr<ActorSkeletalAnimation> mPtr;
};

```

### `AddRiderDefinition`
```
struct AddRiderDefinition
{
  ActorDefinitionIdentifier mEntityType;
};

```

### `ActorSkeletalAnimation`
```
struct ActorSkeletalAnimation
{
  HashedString mName;
  float mAnimationLength;
  bool mShouldLoop;
  bool mOverridePreviousAnimation;
  ExpressionNode mBlendWeight;
  ExpressionNode mAnimTimeUpdate;
  std::vector<BoneAnimation> mBoneAnimations;
  std::vector<ActorParticleEffectEvent> mParticleEffectEvents;
  std::vector<ActorSoundEffectEvent> mSoundEffectEvents;
  std::vector<ActorAnimationEvent> mEvents;
  bool mIsExperimental;
  std::string mSourceFilePathWithExtension;
};

```

### `ActorAnimationController`
```
struct ActorAnimationController
{
  HashedString mName;
  size_t mInitialStateIndex;
  std::vector<std::shared_ptr<ActorAnimationControllerState>> mStates;
  std::string mSourceFilePathWithExtension;
};

```

### `ActorAnimationControllerPlayer`
```
struct __cppobj ActorAnimationControllerPlayer : ActorAnimationPlayer
{
  ActorAnimationControllerPtr mAnimationControllerPtr;
  int mCurrStateIndex;
  int mLastStateIndex;
  int mNextStateIndex;
  int mBlendTransitionStateIndex;
  float mBlendTransitionTime;
  std::vector<std::unique_ptr<ActorAnimationControllerStatePlayer>> mAnimationControllerStatePlayers;
  const ActorParticleEffectMap *mActorParticleEffectMap;
  const std::unordered_map<StringKey,std::string> *mActorSoundEffectMap;
};

```

### `ActorClassTree`
```
struct ActorClassTree
{
  __int8 gap0[1];
};

```

### `ActorDamageSource:96`
```
struct __attribute__((packed)) __attribute__((aligned(4))) ActorDamageSource:96
{
  int (**_vptr$ActorDamageSource)(void);
  ActorDamageCause mCause;
};

```

### `ActorDefinitionGroup::ActorDefinitionList`
```
typedef std::unordered_map<std::string,std::unique_ptr<ActorDefinition>> ActorDefinitionGroup::ActorDefinitionList;

```

### `ActorDefinitionGroup::EDLWrapper`
```
struct ActorDefinitionGroup::EDLWrapper
{
  ActorDefinitionGroup::ActorDefinitionList mList;
};

```

### `Arrow`
```
struct __cppobj Arrow : AbstractArrow
{
  int mLife;
  int mEnchantFlame;
  int mEnchantInfinity;
  std::vector<MobEffectInstance> mMobEffects;
};

```

### `AreaEffectCloud`
```
struct __cppobj AreaEffectCloud : Actor
{
  ActorUniqueID mOwnerId;
  bool mAffectOwner;
  int64_t mSpawnTickClient;
  int mReapplicationDelay;
  int mDurationOnUse;
  int mLocalPickupCount;
  float mRadiusOnUse;
  MobEffectInstanceList mMobEffects;
  std::unordered_map<ActorUniqueID,int> mVictims;
};

```

### `Agent`
```
struct __cppobj __attribute__((aligned(8))) Agent : Mob
{
  Vec3 mToTarget;
  int mSwingAnimationTick;
  const int SWING_TICKS;
  int mSelectedSlot;
  bool mHasSetName;
  bool mHasFiredCreationEvent;
  bool mHover;
  AgentRenderData mRenderData;
};

```

### `ActorLegacySaveConverter`
```
struct ActorLegacySaveConverter
{
  __int8 gap0[1];
};

```

### `AmphibiousMoveControl`
```
struct __cppobj AmphibiousMoveControl : GenericMoveControl
{
};

```

### `ArmorItem`
```
struct __cppobj ArmorItem : Item
{
  const ArmorSlot mSlot;
  const int mDefense;
  const int mModelIndex;
  const ArmorItem::ArmorMaterial *mArmorType;
  TextureAtlasItem m_uvTextureItem;
};

```

### `AgentLookControl`
```
struct __cppobj AgentLookControl : LookControl
{
};

```

### `AgentCommandExecutionGoal`
```
struct __cppobj AgentCommandExecutionGoal : Goal
{
  Mob *mMob;
};

```

### `AgentBodyControl`
```
struct __cppobj AgentBodyControl : BodyControl
{
};

```

### `AgentRenderData`
```
struct AgentRenderData
{
  float mEaseIn;
  int mOldTime;
};

```

### `AvoidMobTypeGoal`
```
struct __cppobj AvoidMobTypeGoal : AvoidMobGoal
{
  const std::vector<MobDescriptor> mAvoidMobs;
  std::string mAvoidIdentifier;
};

```

### `Animal`
```
struct __cppobj Animal : Mob
{
};

```

### `ActorSkeletalAnimationPlayer`
```
struct __cppobj ActorSkeletalAnimationPlayer : ActorAnimationPlayer
{
  ActorSkeletalAnimationPtr mAnimationData;
  std::unordered_map<SkeletalHierarchyIndex,std::vector<int>> mBoneToPartMapping;
  const ActorParticleEffectMap *mActorParticleEffectMap;
  const std::unordered_map<StringKey,std::string> *mActorSoundEffectMap;
  float mAnimTime;
  float mLastAnimTime;
};

```

### `ActorAnimationControllerState`
```
struct ActorAnimationControllerState
{
  HashedString mName;
  std::vector<StateAnimationVariable> mVariables;
  std::vector<std::pair<HashedString,ExpressionNode>> mAnimations;
  std::vector<ActorParticleEffect> mParticleEffects;
  std::vector<ActorAnimationEvent> mEvents[2];
  std::vector<ActorAnimationControllerStateTransition> mTransitions;
  std::vector<ActorSoundEffect> mSoundEffects;
  bool mBlendViaShortestPath;
  std::vector<AnimationValueCurveKeyFrame> mBlendTransitionKeyFrames;
};

```

### `ActorAnimationBase`
```
struct ActorAnimationBase
{
  __int8 gap0[1];
};

```

### `ActorAnimationControllerStateTransition`
```
struct ActorAnimationControllerStateTransition
{
  std::string mTargetStateName;
  size_t mTargetStateIndex;
  ExpressionNode mTransitionExpression;
};

```

### `Amplifier`
```
struct Amplifier
{
  int (**_vptr$Amplifier)(void);
};

```

### `AnimatedImageData_0`
```
struct __attribute__((aligned(8))) AnimatedImageData_0
{
  persona::AnimatedTextureType mType;
  mce::Image_0 mImage;
  float mFrames;
};

```

### `AbstractArrow`
```
struct __cppobj AbstractArrow : Actor
{
  int mFavoredSlot;
  bool mIsPlayerOwned;
  bool mIsCreative;
  MovementInterpolator mInterpolation;
};

```

### `ArrowEffectSubcomponent`
```
struct __cppobj ArrowEffectSubcomponent : MobEffectSubcomponent
{
};

```

### `ActorDefinitionEventSubcomponent`
```
struct __cppobj ActorDefinitionEventSubcomponent : OnHitSubcomponent
{
  bool mAffectShooter;
  bool mAffectProjectile;
  bool mAffectTarget;
  bool mAffectSplashArea;
  float mSplashArea;
  DefinitionTrigger mTrigger;
};

```

### `AutoPlaceItem`
```
struct __attribute__((aligned(8))) AutoPlaceItem
{
  std::string collection;
  bool stopWhenPlaced;
};

```

### `AutoPlaceResult`
```
struct __attribute__((aligned(8))) AutoPlaceResult
{
  std::string collectionName;
  int collectionIndex;
};

```

### `AttackDamageMobEffect`
```
struct __cppobj AttackDamageMobEffect : MobEffect
{
};

```

### `AbsorptionMobEffect`
```
struct __cppobj AbsorptionMobEffect : MobEffect
{
};

```

### `ActorInWeatherTest`
```
struct __cppobj ActorInWeatherTest : FilterTest:96
{
  ActorInWeatherTest::WeatherType mWeather;
};

```

### `AirBlockItem`
```
struct __cppobj AirBlockItem : Item
{
};

```

### `ArrowItem`
```
struct __cppobj __attribute__((aligned(8))) ArrowItem : Item
{
  TextureUVCoordinateSet mArrowIcons[17];
  Potion::PotionVariant mArrowVariants[17];
};

```

### `ArmorStandItem`
```
struct __cppobj ArmorStandItem : Item
{
};

```

### `AuxDataBlockItem`
```
struct __cppobj AuxDataBlockItem : BlockItem
{
  const Block *mParentBlock;
};

```

### `ActorBlock`
```
struct __cppobj ActorBlock : BlockLegacy
{
};

```

### `AirBlock`
```
struct __cppobj AirBlock : BlockLegacy
{
};

```

### `ActivatorRailBlock`
```
struct __cppobj __attribute__((aligned(8))) ActivatorRailBlock : BaseRailBlock
{
};

```

### `AnvilBlock`
```
struct __cppobj AnvilBlock : HeavyBlock
{
};

```

### `AbilityCommand`
```
struct __cppobj __attribute__((aligned(8))) AbilityCommand : Command
{
  PlayerSelector mTargets;
  std::string mAbilityName;
  bool mValue;
  bool mHaveValue;
};

```

### `ActorSelector`
```
typedef CommandSelector<Actor> ActorSelector;

```

### `AreaAttackDefinition`
```
struct AreaAttackDefinition
{
  float mDamageRange;
  int mDamagePerTick;
  ActorDamageCause mDamageCause;
  ActorFilterGroup mEntityFilter;
};

```

### `ActorSpawnRuleBase`
```
struct ActorSpawnRuleBase
{
  int (**_vptr$ActorSpawnRuleBase)(void);
  std::unordered_map<std::string,int> mSpawnDelayStartMap;
};

```

### `AvoidMobGoal`
```
struct __cppobj __attribute__((aligned(4))) AvoidMobGoal : Goal
{
  Mob *mMob;
  float mMaxDist;
  float mMaxFlee;
  float mWalkSpeedModifier;
  float mSprintSpeedModifier;
  float mProbabilityPerStrength;
  TempEPtr<Actor> mToAvoid;
  Unique<Path> mPath;
  Vec3 mPos;
  bool mIgnoreVisibility;
};

```

### `ActivateToolDefinition`
```
struct __cppobj ActivateToolDefinition : BehaviorDefinition
{
  BlockPos mBlockPos;
  std::string mBlockPosId;
};

```

### `ActivateToolNode`
```
struct __cppobj __attribute__((aligned(4))) ActivateToolNode : BehaviorNode:480
{
  BlockPos mBlockPos;
  const Block *mStartingBlock;
  bool mRightMouseDown;
  int mDelayTicks;
  int mDelayCounter;
  bool mPreActionDone;
};

```

### `AttackDefinition`
```
struct __cppobj AttackDefinition : BehaviorDefinition
{
  int mAttackTicks;
  std::string mAttackTicksId;
};

```

### `AttackNode`
```
struct __cppobj __attribute__((aligned(4))) AttackNode : BehaviorNode:480
{
  int mNumTicksToAttack;
  int mNumTicksAttacked;
  bool mPreActionDone;
};

```

### `ArmorContainerController`
```
struct __cppobj ArmorContainerController : ContainerController
{
};

```

### `AgentServerCommands`
```
struct AgentServerCommands
{
  __int8 gap0[1];
};

```

### `AgentCommand`
```
struct __cppobj __attribute__((aligned(4))) AgentCommand : Command
{
  AgentCommand::Mode mMode;
  AgentCommands::CollectCommand::CollectionSpecification mCollectMode;
  AgentCommands::Direction mDirection;
  CommandItem mItem;
  int mSlot;
  int mDestination;
  int mQuantity;
  int mAux;
  CommandPosition mPos;
  bool mIsPosSet;
  float mYRot;
  bool mIsYRotSet;
};

```

### `AgentCommands::GetItemCountCommand`
```
struct __cppobj AgentCommands::GetItemCountCommand : AgentCommands::Command:480
{
  int mCount;
};

```

### `AgentCommands::GetItemDetailsCommand`
```
struct __cppobj AgentCommands::GetItemDetailsCommand : AgentCommands::Command
{
  ItemStack mItem;
};

```

### `AgentCommands::GetItemSpaceCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::GetItemSpaceCommand : AgentCommands::Command:480
{
  int mCount;
  int mMaxCount;
};

```

### `AgentCommands::TransferToCommand`
```
struct __cppobj AgentCommands::TransferToCommand : AgentCommands::Command:480
{
  int mSrcSlot;
  int mQuantity;
  int mDestSlot;
};

```

### `AgentCommands::DropCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::DropCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
  int mSlotNum;
  int mQuantity;
};

```

### `AgentCommands::CollectCommand`
```
struct __cppobj __attribute__((aligned(4))) AgentCommands::CollectCommand : AgentCommands::Command:480
{
  int mItemId;
  AgentCommands::CollectCommand::CollectionSpecification mCollecting;
  bool mDone;
};

```

### `AgentCommands::PlaceCommand`
```
struct __cppobj __attribute__((aligned(4))) AgentCommands::PlaceCommand : AgentCommands::Command
{
  ItemStack mItem;
  int mSlot;
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::TurnCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::TurnCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
  float mTurnStep;
  float mRotation;
};

```

### `AgentCommands::AttackCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::AttackCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::DestroyCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::DestroyCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::DetectCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::DetectCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::DetectRedstoneCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::DetectRedstoneCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::DropAllCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::DropAllCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
};

```

### `AgentCommands::InspectCommand`
```
struct __cppobj AgentCommands::InspectCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
  std::string mBlockName;
};

```

### `AgentCommands::InspectDataCommand`
```
struct __cppobj __attribute__((aligned(4))) AgentCommands::InspectDataCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
  const DataID mData;
};

```

### `AgentCommands::MoveCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::MoveCommand : AgentCommands::Command:464
{
  AgentCommands::Direction mDir;
  Vec3 mPosition;
  bool mTicked;
  Vec3 mStartingPosition;
  Vec3 mIdealMovementVector;
};

```

### `AgentCommands::TillCommand`
```
struct __cppobj __attribute__((aligned(8))) AgentCommands::TillCommand : AgentCommands::Command
{
  ItemStack mItem;
  AgentCommands::Direction mDir;
};

```

### `AgentCommand::AgentCommandReturnType`
```
typedef std::unique_ptr<AgentCommands::Command> AgentCommand::AgentCommandReturnType;

```

### `AgentCommands::Command:480`
```
struct __attribute__((packed)) __attribute__((aligned(4))) AgentCommands::Command:480
{
  int (**_vptr$Command)(void);
  Actor *mTarget;
  Player *mCommander;
  std::string mCommandName;
  bool mResult;
  bool mIsQueryResult;
};

```

### `AgentCommands::Command:464`
```
struct __attribute__((packed)) __attribute__((aligned(2))) AgentCommands::Command:464
{
  int (**_vptr$Command)(void);
  Actor *mTarget;
  Player *mCommander;
  std::string mCommandName;
  bool mResult;
  bool mIsQueryResult;
};

```

### `AppPlatform::Listener`
```
typedef AppPlatformListener AppPlatform::Listener;

```

