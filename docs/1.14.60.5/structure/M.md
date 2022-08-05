# M
### `mce::UUID`
Offset | Type | Name
-|-|-|-
0 | (16) `uint64_t[2]` | Data


### `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >::Base` | mC


### `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >::Base`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<BlockTickingQueue::BlockTick>` | baseclass_0


### `MixerLayer<LayerValues::Terrain,LayerValues::Terrain>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<LayerValues::Terrain>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<LayerValues::Terrain>` | mResult


### `MixerLayer<LayerValues::PreBiome,LayerValues::Terrain>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<LayerValues::Terrain>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<LayerValues::PreBiome>` | mResult


### `MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<LayerValues::PreBiome>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<LayerValues::PreBiome>` | mResult


### `MixerLayer<Biome *,LayerValues::PreBiome>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<LayerValues::PreBiome>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<Biome *>` | mResult


### `MixerLayer<Biome *,Biome *>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<Biome *>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<Biome *>` | mResult


### `MixerLayer<int,Biome *>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<Biome *>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<int>` | mResult


### `MixerLayer<int,int>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<int>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<int>` | mResult


### `MixerLayer<bool,int>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<int>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<bool>` | mResult


### `MixerLayer<bool,bool>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<bool>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<bool>` | mResult


### `MixerLayer<Biome *,Biome *,bool>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<Biome *>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<Biome *>` | mResult


### `MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<BiomeTemperatureCategory>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<BiomeTemperatureCategory>` | mResult


### `MobSpawnRules`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMinBrightness
4 | (4) `int` | mMaxBrightness
8 | (4) `float` | mMinMoonBrightness
12 | (4) `float` | mMaxMoonBrightness
16 | (1) `bool` | mAdjustForWeather
20 | (4) `int` | mMinHeight
24 | (4) `int` | mMaxHeight
28 | (4) `int` | mRarity
32 | (4) `int` | mSurfaceCap
36 | (4) `int` | mUndergroundCap
40 | (4) `Difficulty` | mMinDifficulty
44 | (4) `Difficulty` | mMaxDifficulty
48 | (4) `int` | mSpawnDistanceCap
52 | (4) `int` | mMinSpawnDistance
56 | (4) `int` | mMaxSpawnDistance
60 | (1) `bool` | mSurfaceSpawner
61 | (1) `bool` | mUndergroundSpawner
62 | (1) `bool` | mWaterSpawner
63 | (1) `bool` | mLavaSpawner
64 | (4) `unsigned int` | mPlayerInVillageDistance
68 | (4) `unsigned int` | mPlayerInVillageBorderTolerance
72 | (1) `bool` | mExperimentalSpawner
80 | (8) `uint64_t` | mMinWorldAge
88 | (8) `uint64_t` | mMaxWorldAge
96 | (4) `int` | mMinDelay
100 | (4) `int` | mMaxDelay
104 | (24) `HerdList` | mHerdList
128 | (24) `MobPermutationList` | mPermutationList
152 | (32) `std::string` | mMobEventName
184 | (56) `std::unordered_set<const BlockLegacy *>` | mSpawnOnBlockList
240 | (24) `MobGuaranteedPermutationList` | mGuaranteedList
264 | (32) `std::string` | mMobToDelayId
296 | (4) `int` | mDelaySpawnChance
300 | (1) `bool` | mPersistence


### `MobPermutationList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobSpawnerPermutation>` | baseclass_0


### `MobGuaranteedPermutationList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobSpawnerPermutation>` | baseclass_0


### `MinecraftEventing::fireEventMultiplayerSessionUpdate::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `MeasurementList`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,Social::Events::Measurement>::_Hashtable` | _M_h


### `MerchantRecipe`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemInstance` | mBuyA
136 | (136) `ItemInstance` | mBuyB
272 | (136) `ItemInstance` | mSell
408 | (4) `int` | mTier
412 | (4) `int` | mUses
416 | (4) `int` | mMaxUses
420 | (4) `unsigned int` | mTraderExp
424 | (1) `bool` | mRewardExp
428 | (4) `int` | mDemand
432 | (4) `int` | mBuyCountA
436 | (4) `int` | mBuyCountB
440 | (4) `float` | mPriceMultiplierA
444 | (4) `float` | mPriceMultiplierB


### `MobEffectComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mEffectRange
4 | (4) `unsigned int` | mEffectId
8 | (4) `int` | mEffectTime
16 | (64) `ActorFilterGroup` | mEntityFilter


### `MountTamingComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTemper
4 | (4) `int` | mCounter
8 | (4) `int` | mTemperMod
12 | (4) `int` | mWaitCount


### `MoveControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHasWanted
4 | (12) `Vec3` | mWantedPosition
16 | (1) `bool` | mShouldBreach
20 | (4) `float` | mMaxTurn
24 | (4) `float` | mSpeedModifier
32 | (16) `Shared<MoveControl>` | mMoveControl


### `mce::Image`
Offset | Type | Name
-|-|-|-
0 | (4) `mce::ImageFormat` | imageFormat
4 | (4) `uint32_t` | mWidth
8 | (4) `uint32_t` | mHeight
12 | (1) `mce::ImageUsage` | mUsage
16 | (16) `mce::Image::Storage` | mImageBytes


### `mce::Image::Storage`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<unsigned char []>` | mBlob
8 | (8) `size_t` | mSize


### `MobEquipmentPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (136) `ItemStack` | mItem
184 | (4) `int` | mSlot
188 | (4) `int` | mSelectedSlot
192 | (1) `bool` | mIsServerSide
193 | (1) `ContainerID` | mContainerId
194 | (1) `byte` | mSlotByte
195 | (1) `byte` | mSelectedSlotByte
196 | (1) `byte` | mContainerIdByte


### `MobArmorEquipmentPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (136) `ItemStack` | mHead
184 | (136) `ItemStack` | mTorso
320 | (136) `ItemStack` | mLegs
456 | (136) `ItemStack` | mFeet
592 | (1) `bool` | mIsServerSide


### `MovePlayerPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mPlayerID
48 | (12) `Vec3` | mPos
60 | (8) `Vec2` | mRot
68 | (4) `float` | mYHeadRot
72 | (1) `Player::PositionMode` | mResetPosition
73 | (1) `bool` | mOnGround
80 | (8) `ActorRuntimeID` | mRidingID
88 | (4) `int` | mCause
92 | (4) `int` | mSourceEntityType


### `MoveActorAbsoluteData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorRuntimeID` | mRuntimeId
8 | (1) `MoveActorAbsoluteData::Header` | mHeader
12 | (12) `Vec3` | mPos
24 | (1) `int8_t` | mRotX
25 | (1) `int8_t` | mRotY
26 | (1) `int8_t` | mRotYHead


### `MoveActorAbsoluteData::Header`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | mRaw
1 | (1) `MoveActorAbsoluteData::Header::$1C528A707D3385C2A7E4697785F3087B` | _anon_0


### `MoveActorAbsoluteData::Header::$1C528A707D3385C2A7E4697785F3087B`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `MoveActorDeltaData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorRuntimeID` | mRuntimeId
8 | (2) `MoveActorDeltaData::Header` | mHeader
12 | (4) `int32_t` | mDeltaPositionX
16 | (4) `int32_t` | mDeltaPositionY
20 | (4) `int32_t` | mDeltaPositionZ
24 | (1) `int8_t` | mRotX
25 | (1) `int8_t` | mRotY
26 | (1) `int8_t` | mRotYHead
32 | (32) `MoveActorAbsoluteData` | mPreviousData


### `MoveActorDeltaData::Header`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mRaw
1 | (2) `MoveActorDeltaData::Header::$37FEEDC365990D64A8C0F1A90869C4B6` | _anon_0


### `MoveActorDeltaData::Header::$37FEEDC365990D64A8C0F1A90869C4B6`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0
1 | (1) `__int8` | _bf_1


### `MoveActorDeltaPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (64) `MoveActorDeltaData` | mMoveData


### `MoveActorAbsolutePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `MoveActorAbsoluteData` | mMoveData


### `MapItemTrackedActor::UniqueId`
Offset | Type | Name
-|-|-|-
0 | (4) `MapItemTrackedActor::Type` | type
8 | (8) `ActorUniqueID` | keyEntityId
16 | (12) `BlockPos` | keyBlockPos


### `MessageMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<int,std::string>::_Hashtable` | _M_h


### `MobEffectPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (4) `int` | mEffectDurationTicks
52 | (1) `MobEffectPacket::Event` | mEventId
56 | (4) `int` | mEffectId
60 | (4) `int` | mEffectAmplifier
64 | (1) `bool` | mShowParticles


### `MCRESULT`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSuccess
1 | (1) `MCCATEGORY` | mCategory
2 | (2) `uint16_t` | mCode


### `MolangVariableMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned long,MolangVariable>` | mVariables


### `Matrix`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::mat4x4` | _m


### `ManagedWanderingTraderComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `MobEffectInstance`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mId
4 | (4) `int` | mDuration
8 | (4) `int` | mDurationEasy
12 | (4) `int` | mDurationNormal
16 | (4) `int` | mDurationHard
20 | (4) `int` | mAmplifier
24 | (1) `bool` | mDisplayOnScreenTextureAnimation
25 | (1) `bool` | mAmbient
26 | (1) `bool` | mNoCounter
27 | (1) `bool` | mEffectVisible


### `Mob::hurtEffects::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Mob::JumpPreventionResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mJumpIsPrevented
4 | (12) `BlockPos` | mPreventingBlockBlockPos


### `MobDescriptor`
Offset | Type | Name
-|-|-|-
0 | (64) `ActorFilterGroup` | mTargetFilter
64 | (4) `float` | mMaxDist
68 | (4) `float` | mMaxHeight
72 | (4) `float` | mMaxFlee
76 | (4) `float` | mWalkSpeedModifier
80 | (4) `float` | mSprintSpeedModifier
84 | (1) `bool` | mOverrideMustSee
85 | (1) `bool` | mMustSee
88 | (4) `int` | mMustSeeForgetTicks
92 | (4) `int` | mPriority


### `MingleComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `MingleComponent::MingleState` | mMingleState
8 | (8) `ActorUniqueID` | mPartnerId
16 | (8) `ActorUniqueID` | mPreviousPartnerId


### `MoveControlDolphinDescription`
Offset | Type | Name
-|-|-|-
0 | (16) `MoveControlDescription` | baseclass_0


### `MoveControlDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (4) `float` | mMaxTurn


### `MolangScriptArg`
Offset | Type | Name
-|-|-|-
0 | (56) `MolangScriptArgData` | mData


### `MolangScriptArgData`
Offset | Type | Name
-|-|-|-
0 | (56) `std::__detail::__variant::_Variant_base<float,HashedString,MolangArrayVariable,MolangEntityVariable,MolangGeometryVariable,MolangMaterialVariable,MolangTempVariable,MolangTextureVariable,MaterialVariants,MolangDataDrivenGeometry,MolangQueryFunctionPtr,MolangGenericQueryFunctionPtr,std::vector<ExpressionNode> *>` | baseclass_0


### `MaterialVariants`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::MaterialPtr` | mSkinningMaterialPtr
1 | (1) `mce::MaterialPtr` | mSkinningColorMaterialPtr


### `mce::MaterialPtr`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `mce::Image_0`
Offset | Type | Name
-|-|-|-
0 | (4) `mce::ImageFormat` | imageFormat
4 | (4) `uint32_t` | mWidth
8 | (4) `uint32_t` | mHeight
12 | (1) `mce::ImageUsage_0` | mUsage
16 | (16) `mce::Image::Storage` | mImageBytes


### `MobEffectInstanceList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobEffectInstance>` | baseclass_0


### `MapItemSavedData::ChunkBounds`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | x0
4 | (4) `uint32_t` | z0
8 | (4) `uint32_t` | x1
12 | (4) `uint32_t` | z1


### `MapSample`
Offset | Type | Name
-|-|-|-
0 | (16) `Color` | mColor
16 | (8) `const Block *` | mBlock
24 | (2) `Height` | mHeight


### `MobList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobSpawnerData>` | baseclass_0


### `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >::const_iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockTickingQueue::BlockTick *` | _M_current


### `MapInfoRequestPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mMapId


### `MapCreateLockedCopyPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mOriginalMapId
48 | (8) `ActorUniqueID` | mNewMapId


### `MobSpawnerPermutation`
Offset | Type | Name
-|-|-|-
0 | (4) `WeighedRandom::WeighedRandomItem` | baseclass_0
8 | (168) `ActorDefinitionIdentifier` | mId


### `MobSpawnHerdInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mMinCount
4 | (4) `uint32_t` | mMaxCount
8 | (4) `uint32_t` | mHerdEventSkipCount
12 | (4) `uint32_t` | mInitialEventCount
16 | (32) `std::string` | mInitialEvent
48 | (32) `std::string` | mHerdEvent


### `MesaSurfaceAttributes`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mClayMaterial
8 | (8) `const Block *` | mHardClayMaterial
16 | (1) `bool` | mBrycePillars
17 | (1) `bool` | mHasForest


### `MineshaftData`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mWoodBlock
8 | (8) `const Block *` | mFenceBlock
16 | (4) `float` | roomChance


### `MixerLayer<Biome *,Biome *,BiomeTemperatureCategory>::LayerData`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0
32 | (16) `const LayerDetails::BufferAccessor<Biome *>` | mParentArea
48 | (16) `LayerDetails::BufferAccessor<Biome *>` | mResult


### `MutationFactorData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mVariant
4 | (4) `float` | mExtraVariant
8 | (4) `float` | mColor


### `MobSpawnerData`
Offset | Type | Name
-|-|-|-
0 | (4) `WeighedRandom::WeighedRandomItem` | baseclass_0
8 | (168) `ActorDefinitionIdentifier` | mIdentifier
176 | (304) `MobSpawnRules` | mSpawnRules
480 | (32) `MobSpawnerData::OnSpawnHerd` | mOnSpawnHerd
512 | (32) `MobSpawnerData::OnSelectActor` | mOnSelectEntity


### `MobSpawnerData::OnSpawnHerd`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (std::vector<Mob *> &,Random &)>::_Invoker_type` | _M_invoker


### `MobSpawnerData::OnSelectActor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<ActorDefinitionIdentifier (Random &)>::_Invoker_type` | _M_invoker


### `mce::Radian`
Offset | Type | Name
-|-|-|-
0 | (4) `type_safe::strong_typedef<mce::Radian,float>` | baseclass_0


### `mce::Blob`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<unsigned char []>` | mBlob
8 | (8) `size_t` | mSize


### `mce::Degree`
Offset | Type | Name
-|-|-|-
0 | (4) `type_safe::strong_typedef<mce::Degree,float>` | baseclass_0


### `mcontext_t`
Offset | Type | Name
-|-|-|-
0 | (184) `gregset_t` | gregs
184 | (8) `fpregset_t` | fpregs
192 | (64) `unsigned __int64[8]` | __reserved1


### `MDLocationDescriptor`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | data_size
4 | (4) `MDRVA` | rva


### `MDRawDirectory`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | stream_type
4 | (8) `MDLocationDescriptor` | location


### `MDRawThread`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | thread_id
4 | (4) `uint32_t` | suspend_count
8 | (4) `uint32_t` | priority_class
12 | (4) `uint32_t` | priority
16 | (8) `uint64_t` | teb
24 | (16) `MDMemoryDescriptor` | stack
40 | (8) `MDLocationDescriptor` | thread_context


### `MDMemoryDescriptor`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | start_of_memory_range
8 | (8) `MDLocationDescriptor` | memory


### `MDRawContextAMD64`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | p1_home
8 | (8) `uint64_t` | p2_home
16 | (8) `uint64_t` | p3_home
24 | (8) `uint64_t` | p4_home
32 | (8) `uint64_t` | p5_home
40 | (8) `uint64_t` | p6_home
48 | (4) `uint32_t` | context_flags
52 | (4) `uint32_t` | mx_csr
56 | (2) `uint16_t` | _cs
58 | (2) `uint16_t` | _ds
60 | (2) `uint16_t` | _es
62 | (2) `uint16_t` | _fs
64 | (2) `uint16_t` | _gs
66 | (2) `uint16_t` | _ss
68 | (4) `uint32_t` | eflags
72 | (8) `uint64_t` | dr0
80 | (8) `uint64_t` | dr1
88 | (8) `uint64_t` | dr2
96 | (8) `uint64_t` | dr3
104 | (8) `uint64_t` | dr6
112 | (8) `uint64_t` | dr7
120 | (8) `uint64_t` | _rax
128 | (8) `uint64_t` | _rcx
136 | (8) `uint64_t` | _rdx
144 | (8) `uint64_t` | _rbx
152 | (8) `uint64_t` | _rsp
160 | (8) `uint64_t` | _rbp
168 | (8) `uint64_t` | _rsi
176 | (8) `uint64_t` | _rdi
184 | (8) `uint64_t` | _r8
192 | (8) `uint64_t` | _r9
200 | (8) `uint64_t` | _r10
208 | (8) `uint64_t` | _r11
216 | (8) `uint64_t` | _r12
224 | (8) `uint64_t` | _r13
232 | (8) `uint64_t` | _r14
240 | (8) `uint64_t` | _r15
248 | (8) `uint64_t` | _rip
256 | (512) `MDRawContextAMD64::$D520141881593523D1DB94D2DAC55DA9` | _anon_0
768 | (416) `uint128_struct[26]` | vector_register
1184 | (8) `uint64_t` | vector_control
1192 | (8) `uint64_t` | debug_control
1200 | (8) `uint64_t` | last_branch_to_rip
1208 | (8) `uint64_t` | last_branch_from_rip
1216 | (8) `uint64_t` | last_exception_to_rip
1224 | (8) `uint64_t` | last_exception_from_rip


### `MDRawContextAMD64::$D520141881593523D1DB94D2DAC55DA9`
Offset | Type | Name
-|-|-|-
0 | (512) `MDXmmSaveArea32AMD64` | flt_save
1 | (416) `MDRawContextAMD64::$D520141881593523D1DB94D2DAC55DA9::$9C157CD774907A924DA545D68DEB0CD6` | sse_registers


### `MDXmmSaveArea32AMD64`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | control_word
2 | (2) `uint16_t` | status_word
4 | (1) `uint8_t` | tag_word
5 | (1) `uint8_t` | reserved1
6 | (2) `uint16_t` | error_opcode
8 | (4) `uint32_t` | error_offset
12 | (2) `uint16_t` | error_selector
14 | (2) `uint16_t` | reserved2
16 | (4) `uint32_t` | data_offset
20 | (2) `uint16_t` | data_selector
22 | (2) `uint16_t` | reserved3
24 | (4) `uint32_t` | mx_csr
28 | (4) `uint32_t` | mx_csr_mask
32 | (128) `uint128_struct[8]` | float_registers
160 | (256) `uint128_struct[16]` | xmm_registers
416 | (96) `uint8_t[96]` | reserved4


### `MDRawContextAMD64::$D520141881593523D1DB94D2DAC55DA9::$9C157CD774907A924DA545D68DEB0CD6`
Offset | Type | Name
-|-|-|-
0 | (32) `uint128_struct[2]` | header
32 | (128) `uint128_struct[8]` | legacy
160 | (16) `uint128_struct` | _xmm0
176 | (16) `uint128_struct` | _xmm1
192 | (16) `uint128_struct` | _xmm2
208 | (16) `uint128_struct` | _xmm3
224 | (16) `uint128_struct` | _xmm4
240 | (16) `uint128_struct` | _xmm5
256 | (16) `uint128_struct` | _xmm6
272 | (16) `uint128_struct` | _xmm7
288 | (16) `uint128_struct` | _xmm8
304 | (16) `uint128_struct` | _xmm9
320 | (16) `uint128_struct` | _xmm10
336 | (16) `uint128_struct` | _xmm11
352 | (16) `uint128_struct` | _xmm12
368 | (16) `uint128_struct` | _xmm13
384 | (16) `uint128_struct` | _xmm14
400 | (16) `uint128_struct` | _xmm15


### `MDRawModule`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | base_of_image
8 | (4) `uint32_t` | size_of_image
12 | (4) `uint32_t` | checksum
16 | (4) `uint32_t` | time_date_stamp
20 | (4) `MDRVA` | module_name_rva
24 | (52) `MDVSFixedFileInfo` | version_info
76 | (8) `MDLocationDescriptor` | cv_record
84 | (8) `MDLocationDescriptor` | misc_record
92 | (8) `uint32_t[2]` | reserved0
100 | (8) `uint32_t[2]` | reserved1


### `MDVSFixedFileInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | signature
4 | (4) `uint32_t` | struct_version
8 | (4) `uint32_t` | file_version_hi
12 | (4) `uint32_t` | file_version_lo
16 | (4) `uint32_t` | product_version_hi
20 | (4) `uint32_t` | product_version_lo
24 | (4) `uint32_t` | file_flags_mask
28 | (4) `uint32_t` | file_flags
32 | (4) `uint32_t` | file_os
36 | (4) `uint32_t` | file_type
40 | (4) `uint32_t` | file_subtype
44 | (4) `uint32_t` | file_date_hi
48 | (4) `uint32_t` | file_date_lo


### `MDException`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | exception_code
4 | (4) `uint32_t` | exception_flags
8 | (8) `uint64_t` | exception_record
16 | (8) `uint64_t` | exception_address
24 | (4) `uint32_t` | number_parameters
28 | (4) `uint32_t` | __align
32 | (120) `uint64_t[15]` | exception_information


### `MDRawSystemInfo`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | processor_architecture
2 | (2) `uint16_t` | processor_level
4 | (2) `uint16_t` | processor_revision
6 | (1) `uint8_t` | number_of_processors
7 | (1) `uint8_t` | product_type
8 | (4) `uint32_t` | major_version
12 | (4) `uint32_t` | minor_version
16 | (4) `uint32_t` | build_number
20 | (4) `uint32_t` | platform_id
24 | (4) `MDRVA` | csd_version_rva
28 | (2) `uint16_t` | suite_mask
30 | (2) `uint16_t` | reserved2
32 | (24) `MDCPUInformation` | cpu


### `MDCPUInformation`
Offset | Type | Name
-|-|-|-
0 | (24) `MDCPUInformation::$506F9874F29A8F83AA6970C5F347F260` | x86_cpu_info
1 | (8) `MDCPUInformation::$67D17742F1A1285D3D22720ACA1D139F` | arm_cpu_info
2 | (16) `MDCPUInformation::$0748DD84010D68691F5D57D46D5A06CC` | other_cpu_info


### `MDCPUInformation::$506F9874F29A8F83AA6970C5F347F260`
Offset | Type | Name
-|-|-|-
0 | (12) `uint32_t[3]` | vendor_id
12 | (4) `uint32_t` | version_information
16 | (4) `uint32_t` | feature_information
20 | (4) `uint32_t` | amd_extended_cpu_features


### `MDCPUInformation::$67D17742F1A1285D3D22720ACA1D139F`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | cpuid
4 | (4) `uint32_t` | elf_hwcaps


### `MDCPUInformation::$0748DD84010D68691F5D57D46D5A06CC`
Offset | Type | Name
-|-|-|-
0 | (16) `uint64_t[2]` | processor_features


### `MDRawLinkMap64`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | addr
8 | (4) `MDRVA` | name
16 | (8) `uint64_t` | ld


### `MDGUID`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | data1
4 | (2) `uint16_t` | data2
6 | (2) `uint16_t` | data3
8 | (8) `uint8_t[8]` | data4


### `Motive`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | mName
32 | (4) `const int` | mWidth
36 | (4) `const int` | mHeight
40 | (4) `const int` | mUo
44 | (4) `const int` | mVo
48 | (1) `const bool` | mIsPublic


### `MolangArrayVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangEntityVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangGeometryVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangMaterialVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangTempVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangTextureVariable`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0


### `MolangDataDrivenGeometry`
Offset | Type | Name
-|-|-|-
0 | (8) `DataDrivenGeometry *` | mGeometry
8 | (40) `HashedString` | mName


### `MolangQueryFunctionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `const QueryFunctionAccessor *` | mQueryFunctionPtr
8 | (40) `HashedString` | mName


### `MolangGenericQueryFunctionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `const GenericQueryFunctionAccessor *` | mGenericQueryFunctionPtr
8 | (40) `HashedString` | mName


### `mce::`anonymous namespace'::MathInitializer`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `MinecraftEventing`
Offset | Type | Name
-|-|-|-
0 | (32) `IMinecraftEventing` | baseclass_0
32 | (8) `std::unique_ptr<Social::Events::EventManager>` | mEventManager
40 | (8) `std::unique_ptr<TelemetryInfo>` | mTelemetryInfo
48 | (8) `Social::IUserManager *` | mUserManager
56 | (4) `Social::LocalUserId` | mPrimaryLocalUserId
64 | (8) `uint_fast64_t` | mSessionTickCount
72 | (32) `Core::HeapPathBuffer` | mSettingsDir
104 | (32) `std::string` | mPlayerSessionID
136 | (32) `std::string` | mAppSessionID
168 | (1) `bool` | mShouldHaveAchievementsEnabled
169 | (1) `bool` | mAchievementsAlwaysEnabled
176 | (32) `std::function<void ()>` | mUnregisterOptionsObserver
208 | (1) `bool` | mIsHost
216 | (8) `double` | mLastScreenTimestamp
224 | (1) `bool` | mFlagPlayerGameTypeDefault
225 | (1) `bool` | mFlagDeepLink


### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport,std::default_delete<com::mojang::clacks::protocol::MetricReport> >,moodycamel::ConcurrentQueueDefaultTraits>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *>` | producerListTail
8 | (4) `std::atomic<unsigned int>` | producerCount
16 | (8) `std::atomic<unsigned long>` | initialBlockPoolIndex
24 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *` | initialBlockPool
32 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t` | initialBlockPoolSize
40 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block>` | freeList
48 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *>` | implicitProducerHash
56 | (8) `std::atomic<unsigned long>` | implicitProducerHashCount
64 | (24) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash` | initialImplicitProducerHash
88 | (512) `std::array<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32>` | initialImplicitProducerHashEntries
600 | (1) `std::atomic_flag` | implicitProducerHashResizeInProgress
604 | (4) `std::atomic<unsigned int>` | nextExplicitConsumerId
608 | (4) `std::atomic<unsigned int>` | globalExplicitConsumerOffset


### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport,std::default_delete<com::mojang::clacks::protocol::MetricReport> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport,std::default_delete<com::mojang::clacks::protocol::MetricReport> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *>` | freeListHead


### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport,std::default_delete<com::mojang::clacks::protocol::MetricReport> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
Offset | Type | Name
-|-|-|-
0 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t` | capacity
8 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *` | entries
16 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *` | prev


### `msghdr`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | msg_name
8 | (4) `socklen_t` | msg_namelen
16 | (8) `iovec *` | msg_iov
24 | (8) `size_t` | msg_iovlen
32 | (8) `void *` | msg_control
40 | (8) `size_t` | msg_controllen
48 | (4) `int` | msg_flags


### `MPMCQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter> >`
Offset | Type | Name
-|-|-|-
0 | (616) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>` | mQueue


### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *>` | producerListTail
8 | (4) `std::atomic<unsigned int>` | producerCount
16 | (8) `std::atomic<unsigned long>` | initialBlockPoolIndex
24 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *` | initialBlockPool
32 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t` | initialBlockPoolSize
40 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block>` | freeList
48 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *>` | implicitProducerHash
56 | (8) `std::atomic<unsigned long>` | implicitProducerHashCount
64 | (24) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash` | initialImplicitProducerHash
88 | (512) `std::array<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32>` | initialImplicitProducerHashEntries
600 | (1) `std::atomic_flag` | implicitProducerHashResizeInProgress
604 | (4) `std::atomic<unsigned int>` | nextExplicitConsumerId
608 | (4) `std::atomic<unsigned int>` | globalExplicitConsumerOffset


### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *>` | freeListHead


### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
Offset | Type | Name
-|-|-|-
0 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t` | capacity
8 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *` | entries
16 | (8) `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *` | prev


### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>::Base`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::shared_ptr<BackgroundTask>>` | baseclass_0


### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>::Base`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::shared_ptr<BackgroundTask>>` | baseclass_0


### `MapItemSavedData`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mUpdateInterval
8 | (8) `ActorUniqueID` | mMapId
16 | (8) `ActorUniqueID` | mParentMapId
24 | (1) `bool` | mIsFullyExplored
25 | (1) `bool` | mPreviewIncomplete
28 | (12) `BlockPos` | mOrigin
40 | (4) `DimensionType` | mDimension
44 | (1) `int8_t` | mScale
48 | (24) `std::vector<unsigned int>` | mPixels
72 | (24) `std::vector<std::shared_ptr<MapItemTrackedActor>>` | mTrackedEntities
96 | (1) `bool` | mUnlimitedTracking
97 | (1) `bool` | mDirty
98 | (1) `bool` | mLocked
104 | (24) `MapItemSavedData::DecorationCollection` | mDecorations


### `MapItemSavedData::DecorationCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::pair<MapItemTrackedActor::UniqueId,std::shared_ptr<MapDecoration> >>` | baseclass_0


### `MapDecoration`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mLabel
32 | (1) `MapDecoration::Type` | mImage
33 | (1) `int8_t` | mX
34 | (1) `int8_t` | mY
35 | (1) `int8_t` | mRotation
36 | (16) `Color` | mColor


### `MinecraftServerScriptEngine`
Offset | Type | Name
-|-|-|-
0 | (1184) `ScriptEngineWithContext<ScriptServerContext>` | baseclass_0
1184 | (8) `ServerInstanceEventListener` | baseclass_4a0
1192 | (8) `std::unique_ptr<ScriptServerActorEventListener>` | mEntityEventListener
1200 | (8) `std::unique_ptr<ScriptServerBlockEventListener>` | mBlockEventListener
1208 | (8) `std::unique_ptr<ScriptServerPacketEventListener>` | mPacketEventListener
1216 | (8) `std::unique_ptr<ScriptTelemetryEventListener>` | mTelemetryListener
1224 | (8) `std::unique_ptr<ScriptServerLevelEventListener>` | mLevelListener
1232 | (8) `std::unique_ptr<ScriptLevelWeatherEventListener>` | mWeatherListener
1240 | (8) `std::unique_ptr<entt::Registry<unsigned int>>` | mRegistry
1248 | (8) `ServerInstance *` | mServerInstance


### `Mob::tickEffects::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Mob::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `MovingBlockActor`
Offset | Type | Name
-|-|-|-
0 | (208) `BlockActor` | baseclass_0
208 | (8) `const Block *` | mBlock
216 | (8) `const Block *` | mExtraBlock
224 | (12) `BlockPos` | mPistonBlockPos
240 | (16) `std::shared_ptr<BlockActor>` | mBlockEntity


### `MossStoneSelector`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSelector` | baseclass_0


### `MobEventCommand::InitProxy`
Offset | Type | Name
-|-|-|-
0 | (8) `MobEvents *` | mMobEvents


### `MolangQueryFunction`
Offset | Type | Name
-|-|-|-
0 | (32) `QueryFunctionAccessor` | mAccessor
32 | (32) `std::string` | mDocumentation
64 | (8) `size_t` | mMinArgumentCount
72 | (8) `size_t` | mMaxArgumentCount


### `MolangGenericQueryFunction`
Offset | Type | Name
-|-|-|-
0 | (32) `GenericQueryFunctionAccessor` | mAccessor
32 | (32) `std::string` | mDocumentation
64 | (8) `size_t` | mMinArgumentCount
72 | (8) `size_t` | mMaxArgumentCount


### `MemoryMappedFileAccess::StreamHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `MemoryMappedFileAccess::StreamDetails *` | mStream
8 | (8) `size_t` | mPosition


### `MemoryMappedFileAccess::StreamDetails`
Offset | Type | Name
-|-|-|-
0 | (24) `ByteVector` | mStream
24 | (1) `bool` | mReadAllowed
25 | (1) `bool` | mWriteAllowed
26 | (1) `bool` | mAlwaysWriteAtEnd
27 | (1) `bool` | mDirty


### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>::Base` | mC


### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>::Base` | mC


### `mbstate_t`
```
typedef __mbstate_t mbstate_t;

```

### `max_align_t`
```
struct max_align_t
{
  __int64 __clang_max_align_nonce1;
  long double __clang_max_align_nonce2;
};

```

### `Minecraft`
```
struct __cppobj Minecraft : IEntityRegistryOwner
{
  GameCallbacks *mGameCallbacks;
  IMinecraftEventing *mEventing;
  Unique<ResourcePackManager> mResourceLoader;
  Unique<StructureManager> mStructureManager;
  std::shared_ptr<GameModuleServer> mGameModuleServer;
  Whitelist *mWhitelist;
  PermissionsFile *mPermissionsFile;
  Unique<PrivateKeyManager> mServerKeys;
  const std::string mSaveGamePath;
  Core::FilePathManager *mFilePathManager;
  ServerMetrics *mServerMetrics;
  bool mLevelIsCorrupted;
  double mFrameDuration;
  double mLastFrameStart;
  std::chrono::seconds mMaxPlayerIdleTime;
  Unique<MinecraftCommands> mCommands;
  Unique<GameSession> mGameSession;
  Timer *mSimTimer;
  Timer *mRealTimer;
  NetworkHandler *mNetworkHandler;
  PacketSender *mPacketSender;
  IMinecraftApp *mApp;
  SubClientId mClientSubId;
  OwnerPtr<EntityRegistry> mEntityRegistry;
};

```

### `MinecraftCommands`
```
struct __attribute__((aligned(8))) MinecraftCommands
{
  Unique<CommandOutputSender> mOutputSender;
  Unique<CommandRegistry> mRegistry;
  CommandPermissionLevel mOpPermissionLevel;
  Minecraft *mMinecraft;
  std::function<bool ()> mChatPermissionsCallback;
  std::unordered_map<HashedString,std::unique_ptr<Command>> mCompiledCommandMap;
  bool mExperimentalGameplay;
};

```

### `mce::Math`
```
struct mce::Math
{
  __int8 gap0[1];
};

```

### `MPMCQueue<std::function<void ()> >`
```
struct MPMCQueue<std::function<void ()> >
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __attribute__((aligned(8))) moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned long> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned long> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  int (**_vptr$ProducerBase)(void);
  std::atomic<unsigned long> tailIndex;
  std::atomic<unsigned long> headIndex;
  std::atomic<unsigned long> dequeueOptimisticCount;
  std::atomic<unsigned long> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::details::ConcurrentQueueProducerTypelessBase`
```
struct moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::details::ConcurrentQueueProducerTypelessBase *next;
  std::atomic<bool> inactive;
  moodycamel::ProducerToken *token;
};

```

### `moodycamel::ProducerToken`
```
struct moodycamel::ProducerToken
{
  moodycamel::details::ConcurrentQueueProducerTypelessBase *producer;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __attribute__((aligned(16))) moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block::$3295407E46A0F788D2E71668977F845E _anon_0;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned long> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::details::std_max_align_t`
```
typedef max_align_t moodycamel::details::std_max_align_t;

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t capacity;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned long> key;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t capacity;
  std::atomic<unsigned long> tail;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry *entries;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry **index;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *prev;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry
{
  std::atomic<unsigned long> key;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> value;
};

```

### `moodycamel::ConcurrentQueueDefaultTraits`
```
struct moodycamel::ConcurrentQueueDefaultTraits
{
  __int8 gap0[1];
};

```

### `moodycamel::ConsumerToken`
```
struct moodycamel::ConsumerToken
{
  uint32_t initialOffset;
  uint32_t lastKnownGlobalOffset;
  uint32_t itemsConsumedFromCurrent;
  moodycamel::details::ConcurrentQueueProducerTypelessBase *currentProducer;
  moodycamel::details::ConcurrentQueueProducerTypelessBase *desiredProducer;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  int (**_vptr$ProducerBase)(void);
  std::atomic<unsigned long> tailIndex;
  std::atomic<unsigned long> headIndex;
  std::atomic<unsigned long> dequeueOptimisticCount;
  std::atomic<unsigned long> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __attribute__((aligned(16))) moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block::$64D1B972AE0AB987F85AF31DA57DF7B7 _anon_0;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned long> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __attribute__((aligned(8))) moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned long> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned long> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t capacity;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned long> key;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t capacity;
  std::atomic<unsigned long> tail;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry *entries;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry **index;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *prev;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry
{
  std::atomic<unsigned long> key;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> value;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t size;
  std::atomic<unsigned long> front;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *entries;
  void *prev;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry
{
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::index_t base;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::Block *block;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer : moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader *> blockIndex;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSlotsUsed;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSize;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexFront;
  moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *pr_blockIndexEntries;
  void *pr_blockIndexRaw;
};

```

### `moodycamel::details::_hash_32_or_64<true>`
```
struct moodycamel::details::_hash_32_or_64<true>
{
  __int8 gap0[1];
};

```

### `moodycamel::details::thread_id_converter<unsigned long>`
```
struct moodycamel::details::thread_id_converter<unsigned long>
{
  __int8 gap0[1];
};

```

### `MoveControlSystem`
```
struct __cppobj MoveControlSystem : ITickingSystem
{
};

```

### `MountTamingSystem`
```
struct __cppobj MountTamingSystem : ITickingSystem
{
};

```

### `MobEffectSystem`
```
struct __cppobj MobEffectSystem : ITickingSystem
{
};

```

### `MoveInputHandler`
```
struct __cppobj __attribute__((aligned(8))) MoveInputHandler : MoveInput:672
{
  bool mAscend;
  bool mDescend;
  bool mNorthJump;
  bool mJumpDown;
  bool mSprintDown;
  bool mChangeHeight;
  bool mPersistSneak;
  bool mUp;
  bool mDown;
  bool mLeft;
  bool mRight;
  bool mUpLeft;
  bool mUpRight;
  Vec2 mAnalogMoveVector;
  Vec3 mGazeDir;
  bool mLookCenter;
  uint8_t mLookSlightDirField;
  uint8_t mLookNormalDirField;
  uint8_t mLookSmoothDirField;
};

```

### `MegaPineTreeFeature`
```
struct __cppobj __attribute__((aligned(4))) MegaPineTreeFeature : MegaTreeFeature:416
{
  bool mIsSpruce;
};

```

### `MegaJungleTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) MegaJungleTreeFeature : MegaTreeFeature
{
};

```

### `MelonFeature`
```
struct __cppobj MelonFeature : Feature
{
};

```

### `MobSpawnerBlockActor`
```
struct __cppobj MobSpawnerBlockActor : BlockActor
{
  Unique<BaseMobSpawner> mSpawner;
};

```

### `MolangVariable`
```
struct __attribute__((aligned(8))) MolangVariable
{
  std::string mName;
  float mValue;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  int (**_vptr$ProducerBase)(void);
  std::atomic<unsigned long> tailIndex;
  std::atomic<unsigned long> headIndex;
  std::atomic<unsigned long> dequeueOptimisticCount;
  std::atomic<unsigned long> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __attribute__((aligned(16))) moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block::$64D1B972AE0AB987F85AF31DA57DF7B7 _anon_0;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned long> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned long> key;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `MixerLayer<LayerValues::Terrain,LayerValues::Terrain>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<LayerValues::Terrain,LayerValues::Terrain> : Layer<LayerValues::Terrain>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<LayerValues::PreBiome,LayerValues::Terrain>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<LayerValues::PreBiome,LayerValues::Terrain> : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<Biome *,LayerValues::PreBiome>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<Biome *,LayerValues::PreBiome> : Layer<Biome *>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<Biome *,Biome *>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<Biome *,Biome *> : Layer<Biome *>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<int,Biome *>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<int,Biome *> : Layer<int>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<int,int>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<int,int> : Layer<int>
{
  LayerPtr<int> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<bool,int>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<bool,int> : Layer<bool>
{
  LayerPtr<int> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<bool,bool>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<bool,bool> : Layer<bool>
{
  LayerPtr<bool> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MixerLayer<Biome *,Biome *,bool>`
```
struct __cppobj MixerLayer<Biome *,Biome *,bool> : Layer<Biome *>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<std::shared_ptr<Layer<bool> > > mMoreParents;
};

```

### `MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>`
```
struct __cppobj __attribute__((aligned(8))) MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory> : Layer<BiomeTemperatureCategory>
{
  LayerPtr<BiomeTemperatureCategory> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `MineshaftFeature`
```
struct __cppobj MineshaftFeature : StructureFeature
{
};

```

### `MonsterRoomFeature`
```
struct __cppobj MonsterRoomFeature : Feature
{
};

```

### `MixerLayer<LayerValues::Terrain,LayerValues::Terrain>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<LayerValues::Terrain,LayerValues::Terrain>::ParentUnpacker;

```

### `MixerLayer<LayerValues::PreBiome,LayerValues::Terrain>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<LayerValues::PreBiome,LayerValues::Terrain>::ParentUnpacker;

```

### `MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome>::ParentUnpacker;

```

### `MixerLayer<Biome *,LayerValues::PreBiome>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<Biome *,LayerValues::PreBiome>::ParentUnpacker;

```

### `MixerLayer<Biome *,Biome *>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<Biome *,Biome *>::ParentUnpacker;

```

### `MixerLayer<int,Biome *>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<int,Biome *>::ParentUnpacker;

```

### `MixerLayer<int,int>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<int,int>::ParentUnpacker;

```

### `MixerLayer<bool,int>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<bool,int>::ParentUnpacker;

```

### `MixerLayer<bool,bool>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<bool,bool>::ParentUnpacker;

```

### `MixerLayer<Biome *,Biome *,bool>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)>_0 MixerLayer<Biome *,Biome *,bool>::ParentUnpacker;

```

### `MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)> MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>::ParentUnpacker;

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t size;
  std::atomic<unsigned long> front;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *entries;
  void *prev;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry
{
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::index_t base;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::Block *block;
};

```

### `moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer : moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader *> blockIndex;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSlotsUsed;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSize;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexFront;
  moodycamel::ConcurrentQueue<std::function<void ()>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *pr_blockIndexEntries;
  void *pr_blockIndexRaw;
};

```

### `MerchantRecipeList`
```
struct MerchantRecipeList
{
  int (**_vptr$MerchantRecipeList)(void);
  std::vector<MerchantRecipe> mRecipeList;
  std::vector<unsigned int> mTierExpRequirements;
};

```

### `MobEffect`
```
struct MobEffect
{
  int (**_vptr$MobEffect)(void);
  const unsigned int mId;
  bool mIsHarmful;
  Color mColor;
  std::string mDescriptionId;
  int mIcon;
  float mDurationModifier;
  bool mIsDisabled;
  std::string mResourceName;
  std::string mIconName;
  bool mEffectVisible;
  Util::HashString mComponentName;
  std::shared_ptr<Amplifier> mValueAmplifier;
  std::shared_ptr<Amplifier> mDurationAmplifier;
  std::vector<std::pair<const Attribute *,std::shared_ptr<AttributeBuff> >> mAttributeBuffs;
  std::vector<std::pair<const Attribute *,std::shared_ptr<AttributeModifier> >> mAttributeModifiers;
};

```

### `Mob`
```
struct __cppobj Mob : Actor
{
  float mYBodyRot;
  float mYBodyRotO;
  float mYHeadRot;
  float mYHeadRotO;
  int mHurtTime;
  int mHurtDuration;
  float mHurtDir;
  int mAttackTime;
  float mOTilt;
  float mTilt;
  int mLookTime;
  float mFallTime;
  bool mFloatsInLiquid;
  int mJumpTicks;
  Vec3 mElytraRot;
  CompassSpriteCalculator mCompassSpriteCalc;
  ClockSpriteCalculator mClockSpriteCalc;
  float mXxa;
  float mYya;
  float mZza;
  float mYRotA;
  bool mHasMoveInput;
  float mAttackAnim;
  float mORun;
  float mRun;
  bool mSwinging;
  int mSwingTime;
  int mNoActionTime;
  int mNoJumpDelay;
  float mDefaultLookAngle;
  float mFrictionModifier;
  float mFlyingSpeed;
  float mSwimSpeedMultiplier;
  int mDeathTime;
  int mDeathScore;
  float mAnimStep;
  float mAnimStepO;
  float mLockedBodyYRot;
  float mRiderYRotLimit;
  MovementInterpolator mInterpolation;
  int mLastHurt;
  ActorDamageCause mLastHurtCause;
  int mDmgSpill;
  int mDmgPartial;
  bool mJumping;
  bool mJumpVelRedux;
  float mPlayerJumpPendingScale;
  bool mAllowStandSliding;
  Vec3 mJumpStartPos;
  float mSpeed;
  bool mSurfaceMob;
  bool mNaturallySpawned;
  bool mDead;
  Weak<VillageLegacy> mVillageLegacy;
  bool mWantsToBeJockey;
  int mAmbientPlayBackInterval;
  bool mSpawnedXP;
  int mRollCounter;
  ActorUniqueID mLookingAtId;
  ActorUniqueID mLastHurtMobId;
  ActorUniqueID mLastHurtByMobId;
  ActorUniqueID mLastHurtByPlayerId;
  ActorUniqueID mCaravanHead;
  ActorUniqueID mCaravanTail;
  int mLastHurtMobTimestamp;
  int mLastHurtByMobTime;
  float mOAttackAnim;
  int mArrowCount;
  int mRemoveArrowTime;
  int mFallFlyTicks;
  bool mHasBoundOrigin;
  BlockPos mBoundOrigin;
  MobSpawnMethod mSpawnMethod;
  bool mCreateAiOnReload;
  ActorUniqueID mTargetCaptainId;
};

```

### `MountTameableDefinition`
```
struct MountTameableDefinition
{
  int mMinTemper;
  int mMaxTemper;
  int mAttemptTemperMod;
  std::string mFeedText;
  std::string mRideText;
  DefinitionTrigger mOnTame;
  std::vector<FeedItem> mFeedItems;
  std::vector<const Item *> mAutoRejectItems;
};

```

### `MoveControl`
```
struct __cppobj MoveControl : Control
{
};

```

### `ModalFormRequestPacket`
```
struct __cppobj ModalFormRequestPacket : Packet:288
{
  uint32_t mFormId;
  std::string mFormJSON;
};

```

### `ModalFormResponsePacket`
```
struct __cppobj ModalFormResponsePacket : Packet:288
{
  uint32_t mFormId;
  std::string mJSONResponse;
};

```

### `MultiplayerSettingsPacket`
```
struct __cppobj MultiplayerSettingsPacket : Packet:288
{
  MultiplayerSettingsPacketType mPacketType;
};

```

### `MinecraftPackets`
```
struct MinecraftPackets
{
  __int8 gap0[1];
};

```

### `MapItemTrackedActor`
```
struct MapItemTrackedActor
{
  MapItemTrackedActor::UniqueId mUniqueId;
  int mStep;
  bool mNeedsResend;
  uint32_t mMinDirtyX;
  uint32_t mMinDirtyY;
  uint32_t mMaxDirtyX;
  uint32_t mMaxDirtyY;
  int mTick;
  float mLastRotation;
  MapDecoration::Type mDecorationType;
  DimensionType mDimensionId;
  std::unique_ptr<ChunkViewSource> mChunkViewSource;
};

```

### `MultiRecipe`
```
struct __cppobj MultiRecipe : Recipe
{
};

```

### `MapExtendingRecipe`
```
struct __cppobj MapExtendingRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
  Level *mLevel;
};

```

### `MapLockingRecipe`
```
struct __cppobj MapLockingRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
  ActorUniqueID mOriginalMapId;
  Level *mLevel;
};

```

### `MapCloningRecipe`
```
struct __cppobj MapCloningRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `MapUpgradingRecipe`
```
struct __cppobj MapUpgradingRecipe : MultiRecipe
{
  Recipe::ResultList mResults;
};

```

### `MinecraftScheduler`
```
struct MinecraftScheduler
{
  __int8 gap0[1];
};

```

### `MinecraftWorkerPool`
```
struct MinecraftWorkerPool
{
  __int8 gap0[1];
};

```

### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>::const_iterator`
```
typedef std::vector<std::shared_ptr<BackgroundTask>>::const_iterator MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>::const_iterator;

```

### `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>::const_iterator`
```
typedef std::vector<std::shared_ptr<BackgroundTask>>::const_iterator MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PriorityComparer>::const_iterator;

```

### `MobEvents`
```
struct __attribute__((aligned(8))) MobEvents
{
  int (**_vptr$MobEvents)(void);
  std::array<MobEvent,2> mMobEvents;
  BasicTimer mSaveTimer;
  LevelStorage *mLevelStorage;
  bool mEventsEnabled;
  bool mNeedsToSave;
};

```

### `MovementInterpolator`
```
struct __attribute__((aligned(4))) MovementInterpolator
{
  Vec3 mPos;
  Vec2 mRot;
  float mHeadYaw;
  int mPositionSteps;
  int mRotationSteps;
  int mHeadYawSteps;
  bool mInterpolationActive;
};

```

### `MobEffectChangeDescription`
```
struct __cppobj MobEffectChangeDescription : AttributeDescription
{
  std::vector<MobEffectInstance> mAddEffects;
  std::vector<std::string> mRemoveEffects;
};

```

### `ManagedWanderingTraderDescription`
```
struct __cppobj ManagedWanderingTraderDescription : ComponentDescription
{
};

```

### `MarkVariantDescription`
```
struct __cppobj __attribute__((aligned(8))) MarkVariantDescription : PropertyDescription
{
  int mMarkVariantChoice;
};

```

### `MoveControlBasicDescription`
```
struct __cppobj __attribute__((aligned(8))) MoveControlBasicDescription : MoveControlDescription
{
};

```

### `MoveControlFlyDescription`
```
struct __cppobj __attribute__((aligned(8))) MoveControlFlyDescription : MoveControlDescription
{
};

```

### `MoveControlSkipDescription`
```
struct __cppobj __attribute__((aligned(8))) MoveControlSkipDescription : MoveControlDescription
{
};

```

### `MoveControlHoverDescription`
```
struct __cppobj __attribute__((aligned(8))) MoveControlHoverDescription : MoveControlDescription
{
};

```

### `MoveControlSwayDescription`
```
struct __cppobj __attribute__((aligned(8))) MoveControlSwayDescription : MoveControlDescription:96
{
  float mSwayFrequency;
  float mSwayAmplitude;
};

```

### `MoveControlDescription:96`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) MoveControlDescription:96 : ComponentDescription
{
  float mMaxTurn;
};

```

### `MaterialReducerContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) MaterialReducerContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `MinecartBlockCommandOrigin`
```
struct __cppobj MinecartBlockCommandOrigin : BlockCommandOrigin
{
  ActorUniqueID mMinecartEntityID;
};

```

### `MovePriorityQueue<FileChunk,std::less<FileChunk> >`
```
struct MovePriorityQueue<FileChunk,std::less<FileChunk> >
{
  MovePriorityQueue<FileChunk,std::less<FileChunk> >::Base mC;
};

```

### `MovePriorityQueue<FileChunk,std::less<FileChunk> >::Base`
```
typedef std::vector<FileChunk> MovePriorityQueue<FileChunk,std::less<FileChunk> >::Base;

```

### `MovePriorityQueue<FileChunk,std::less<FileChunk> >::const_iterator`
```
typedef std::vector<FileChunk>::const_iterator MovePriorityQueue<FileChunk,std::less<FileChunk> >::const_iterator;

```

### `ModelPartLocator`
```
struct __attribute__((aligned(8))) ModelPartLocator
{
  SkeletalHierarchyIndex mSkeletalHierarchyIndex;
  int mBoneMapping;
  HashedString mBoneName;
  HashedString mName;
  Vec3 mOffset;
  Vec3 mPosition;
  Vec3 mRotation;
  Matrix mWorldAbsoluteTransform;
};

```

### `Material`
```
struct Material
{
  MaterialType mType;
  bool mFlammable;
  bool mNeverBuildable;
  bool mAlwaysDestroyable;
  bool mReplaceable;
  bool mLiquid;
  float mTranslucency;
  bool mBlocksMotion;
  bool mBlocksPrecipitation;
  bool mSolid;
  bool mSuperHot;
  Color mMaterialColor;
};

```

### `MushroomCow`
```
struct __cppobj MushroomCow : Animal
{
};

```

### `MinecartRideable`
```
struct __cppobj MinecartRideable : Minecart
{
};

```

### `MinecartHopper`
```
struct __cppobj __attribute__((aligned(8))) MinecartHopper : Minecart
{
  BlockPos mLastPosition;
};

```

### `MinecartTNT`
```
struct __cppobj MinecartTNT : Minecart
{
};

```

### `MinecartChest`
```
struct __cppobj MinecartChest : Minecart
{
};

```

### `MinecartCommandBlock`
```
struct __cppobj MinecartCommandBlock : Minecart
{
};

```

### `MoveToWaterGoal`
```
struct __cppobj MoveToWaterGoal : BaseMoveToBlockGoal
{
};

```

### `MoveToVillageGoal`
```
struct __attribute__((aligned(8))) MoveToVillageGoal
{
  __int8 baseclass_0[116];
  int mVillageSearchRangeBlocks;
  bool mReachedVillage;
};

```

### `MoveToLandGoal`
```
struct __cppobj MoveToLandGoal : BaseMoveToBlockGoal
{
};

```

### `MoveToPOIGoal`
```
struct MoveToPOIGoal
{
  __int8 baseclass_0[116];
  POIType mPOIType;
  AABB mPOIBoundingBox;
  bool mUsingBoundingBox;
  bool mRequireSameY;
  Unique<Path> mPath;
};

```

### `MoveToBlockGoal`
```
struct __cppobj __attribute__((aligned(8))) MoveToBlockGoal : Goal:96
{
  int mGiveUpTicks;
  int mStayDurationTicks;
  float mSpeedMod;
  float mGoalRadiusSq;
  BlockPos mTargetBlockPos;
  Vec3 mTargetPositionOffset;
  float mChanceToStart;
  int mInterval;
  int mSearchRange;
  int mSearchHeight;
  const TargetSelectionMethod_0 mMethod;
  const std::vector<DefinitionTrigger> mOnReachTriggers;
  const std::vector<DefinitionTrigger> mOnStayCompletedTriggers;
  const std::vector<ItemDescriptor> mTargetBlockDescriptors;
  uint64_t mCooldownCounter;
  const uint64_t mCooldownTimeoutTime;
  bool mReachedTarget;
  int mNextStartTick;
  int mStayTicks;
  int mTravelTicks;
  BlockPos mStartPos;
  Mob *mMob;
  bool mHasSentOnReachEvent;
};

```

### `MoveToRandomBlockGoal`
```
struct __cppobj MoveToRandomBlockGoal : Goal
{
  Mob *mMob;
  Vec3 mDestination;
  Vec3 mLastPos;
  int mFailedPathing;
  int mTotalFailedPathing;
  float mSpeedModifier;
  float mRadiusSq;
  float mBlockDistance;
  int mCooldownTimer;
};

```

### `MountPathingGoal`
```
struct __cppobj MountPathingGoal : Goal
{
  TempEPtr<Actor> mTarget;
  float mSpeed;
  float mTargetDistSqr;
  bool mTrackTarget;
  int mTimeToRecalcPath;
  Mob *mMob;
};

```

### `MoveIndoorsGoal`
```
struct __cppobj MoveIndoorsGoal : Goal:96
{
  bool mUsingPOI;
  bool mPathingInvalid;
  BlockPos mInsidePos;
  BlockPos mStartPos;
  AABB mPOIBoundingBox;
  Tick mCooldownTimer;
  const Tick mCooldownTimeoutTime;
  float mSpeedModifier;
  Mob *mMob;
};

```

### `MoveThroughVillageGoal`
```
struct __cppobj MoveThroughVillageGoal : Goal:96
{
  float mSpeedModifier;
  Unique<Path> mPath;
  Mob *mMob;
};

```

### `MoveTowardsRestrictionGoal`
```
struct __cppobj MoveTowardsRestrictionGoal : Goal
{
  Mob *mMob;
  float mSpeedModifier;
  Vec3 mWantedPosition;
};

```

### `MoveTowardsTargetGoal`
```
struct __cppobj __attribute__((aligned(8))) MoveTowardsTargetGoal : Goal
{
  TempEPtr<Actor> mTarget;
  Mob *mMob;
  float mSpeedModifier;
  float mWithin;
  Vec3 mWantedPosition;
};

```

### `MakeLoveGoal`
```
struct __cppobj __attribute__((aligned(8))) MakeLoveGoal : Goal
{
  VillagerBase *mVillager;
  int mLoveMakingTime;
};

```

### `MeleeAttackGoal`
```
struct __cppobj MeleeAttackGoal : Goal
{
  Mob *mMob;
  TempEPtr<Actor> mTarget;
  int mAttackTime;
  float mSpeedModifier;
  bool mTrackTarget;
  bool mAttackOnce;
  bool mHasAttacked;
  Unique<Path> mPath;
  ActorCategory mAttackTypes;
  int mRandomStopInterval;
  float mReachMultiplier;
  int mTimeToRecalcPath;
  float mPathedTargetX;
  float mPathedTargetY;
  float mPathedTargetZ;
  float mFOV;
  bool mRequireCompletePath;
  DefinitionTrigger mOnAttacked;
};

```

### `MingleGoal`
```
struct __cppobj __attribute__((aligned(8))) MingleGoal : MoveToPOIGoal
{
  int mCooldownTicks;
  int mCooldownTicksMax;
  int mMingleTicks;
  int mMingleTicksMax;
  int mAvailableTicks;
  int mAvailableTicksMax;
  int mSpeakInterval;
  ActorDefinitionIdentifier mDesiredPartnerType;
  float mMingleDistanceSquared;
};

```

### `Monster`
```
struct __cppobj Monster : Mob
{
  ActorUniqueID mLastHurtByMobId;
};

```

### `MoveToVillageGoal:992`
```
struct __attribute__((aligned(4))) MoveToVillageGoal:992
{
  __int8 baseclass_0[116];
  int mVillageSearchRangeBlocks;
  bool mReachedVillage;
};

```

### `Minecart`
```
struct __cppobj Minecart : Actor
{
  bool mFlipped;
  std::string mName;
  MovementInterpolator mInterpolation;
  Actor *mLastRidingEntity;
  LoopingSoundHandle mBaseLoop;
  LoopingSoundHandle mRidingLoop;
  float mSmoothSpeed;
  std::unique_ptr<CompoundTag> mDisplayBlockSerId;
};

```

### `MarketplaceSkinValidator`
```
struct MarketplaceSkinValidator
{
  __int8 gap0[1];
};

```

### `MobEffectSubcomponent`
```
struct __cppobj MobEffectSubcomponent : OnHitSubcomponent
{
  std::vector<MobEffectInstance> mMobEffects;
};

```

### `MultiplyValueAmplifier`
```
struct __cppobj __attribute__((aligned(8))) MultiplyValueAmplifier : Amplifier
{
  float mScalar;
};

```

### `MapItem`
```
struct __cppobj MapItem : ComplexItem
{
  TextureAtlasItem m_uvTextureItem;
};

```

### `MobPlacerItem`
```
struct __cppobj MobPlacerItem : Item
{
  ActorInfoRegistry *mActorInfoRegistry;
  const ActorResourceDefinitionGroup *mActorResourceGroup;
  TextureUVCoordinateSet m_uvNullEgg;
  TextureUVCoordinateSet m_uvEggMask;
  std::unordered_map<StringKey,const TextureUVCoordinateSet *> mUVTextureMap;
};

```

### `MinecartItem`
```
struct __cppobj __attribute__((aligned(8))) MinecartItem : Item
{
  MinecartType mCartType;
};

```

### `MedicineItem`
```
struct __cppobj MedicineItem : ChemistryItem
{
};

```

### `MeleeWeaponEnchant`
```
struct __cppobj MeleeWeaponEnchant : Enchant
{
};

```

### `MendingEnchant`
```
struct __cppobj MendingEnchant : Enchant
{
};

```

### `MobEvent`
```
struct __attribute__((aligned(8))) MobEvent
{
  std::string mName;
  std::string mLocalizableName;
  bool mEnabled;
  bool mIsDefaultSet;
};

```

### `MobSpawnInfo`
```
struct MobSpawnInfo
{
  __int8 gap0[1];
};

```

### `MutateTransformationAttributes`
```
typedef WeightedBiomeAttributes<MutateBiomeTransformation> MutateTransformationAttributes;

```

### `MonsterEggBlock`
```
struct __cppobj MonsterEggBlock : BlockLegacy
{
};

```

### `MusicBlockActor`
```
struct __cppobj __attribute__((aligned(8))) MusicBlockActor : BlockActor:1608
{
  byte mNote;
  bool mOn;
};

```

### `MushroomBlock`
```
struct __cppobj MushroomBlock : BushBlock
{
};

```

### `MetalBlock`
```
struct __cppobj MetalBlock : BlockLegacy
{
};

```

### `MobSpawnerBlock`
```
struct __cppobj MobSpawnerBlock : ActorBlock
{
};

```

### `MelonBlock`
```
struct __cppobj MelonBlock : BlockLegacy
{
};

```

### `MyceliumBlock`
```
struct __cppobj MyceliumBlock : BlockLegacy
{
};

```

### `MagmaBlock`
```
struct __cppobj MagmaBlock : BlockLegacy
{
};

```

### `MovingBlock`
```
struct __cppobj MovingBlock : ActorBlock
{
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t capacity;
  std::atomic<unsigned long> tail;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry *entries;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry **index;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *prev;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexEntry
{
  std::atomic<unsigned long> key;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> value;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t size;
  std::atomic<unsigned long> front;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *entries;
  void *prev;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::index_t base;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *block;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer : moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader *> blockIndex;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSlotsUsed;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexSize;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::size_t pr_blockIndexFront;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *pr_blockIndexEntries;
  void *pr_blockIndexRaw;
};

```

### `MainChunkSource`
```
struct __cppobj MainChunkSource : ChunkSource
{
  ChunkSourceLookupMap mChunkMap;
};

```

### `MegaTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) MegaTreeFeature : TreeFeature:288
{
  const int mBaseHeight;
  const int mHeightInterval;
  const int mTrunkType;
  const int mLeafType;
};

```

### `MegaTreeFeature:416`
```
struct __cppobj MegaTreeFeature:416 : TreeFeature:288
{
  const int mBaseHeight;
  const int mHeightInterval;
  const int mTrunkType;
  const int mLeafType;
};

```

### `MineshaftStart`
```
struct __cppobj MineshaftStart : StructureStart
{
};

```

### `MineshaftRoom`
```
struct __cppobj MineshaftRoom : MineshaftPiece
{
  std::vector<BoundingBox> childEntranceBoxes;
};

```

### `MineshaftCrossing`
```
struct __cppobj __attribute__((aligned(4))) MineshaftCrossing : MineshaftPiece
{
  int direction;
  bool isTwoFloored;
};

```

### `MineshaftPiece`
```
struct __cppobj MineshaftPiece : StructurePiece
{
  MineshaftData metadata;
};

```

### `MineshaftStairs`
```
struct __cppobj MineshaftStairs : MineshaftPiece
{
};

```

### `MineshaftCorridor`
```
struct __cppobj MineshaftCorridor : MineshaftPiece
{
  bool hasRails;
  bool spiderCorridor;
  bool hasPlacedSpider;
  int numSections;
};

```

### `MonumentBuilding`
```
struct __cppobj MonumentBuilding : OceanMonumentPiece
{
  std::vector<std::unique_ptr<OceanMonumentPiece>> mChildPieces;
  std::vector<std::shared_ptr<RoomDefinition>> mRoomGrid;
  Shared<RoomDefinition> mSourceRoom;
  Shared<RoomDefinition> mCoreRoom;
};

```

### `MonumentRoomFitter`
```
struct MonumentRoomFitter
{
  int (**_vptr$MonumentRoomFitter)(void);
};

```

### `MixerLayer<Biome *,Biome *,BiomeTemperatureCategory>`
```
struct __cppobj MixerLayer<Biome *,Biome *,BiomeTemperatureCategory> : Layer<Biome *>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<std::shared_ptr<Layer<BiomeTemperatureCategory> > > mMoreParents;
};

```

### `MixerLayer<Biome *,Biome *,BiomeTemperatureCategory>::ParentUnpacker`
```
typedef std::make_index_sequence<sizeof___(MoreParentTypes)>_0 MixerLayer<Biome *,Biome *,BiomeTemperatureCategory>::ParentUnpacker;

```

### `MoveInput`
```
struct __attribute__((aligned(8))) MoveInput
{
  int (**_vptr$MoveInput)(void);
  Vec2 mMove;
  Vec2 mLookDelta;
  Vec3 mGazeDir;
  Vec3 mGazeDirDelta;
  Vec3 mDisplacement;
  Vec3 mDisplacementDelta;
  bool mSneaking;
  bool mSneakDown;
  bool mSprinting;
  bool mWantUp;
  bool mWantDown;
  bool mWantDownSlow;
  bool mWantUpSlow;
  bool mJumping;
  bool mAutoJumpingInWater;
  bool mAscendScaffolding;
  bool mDescendScaffolding;
  bool mSneakToggleDown;
};

```

### `MoveInput:672`
```
struct __attribute__((packed)) __attribute__((aligned(4))) MoveInput:672
{
  int (**_vptr$MoveInput)(void);
  Vec2 mMove;
  Vec2 mLookDelta;
  Vec3 mGazeDir;
  Vec3 mGazeDirDelta;
  Vec3 mDisplacement;
  Vec3 mDisplacementDelta;
  bool mSneaking;
  bool mSneakDown;
  bool mSprinting;
  bool mWantUp;
  bool mWantDown;
  bool mWantDownSlow;
  bool mWantUpSlow;
  bool mJumping;
  bool mAutoJumpingInWater;
  bool mAscendScaffolding;
  bool mDescendScaffolding;
  bool mSneakToggleDown;
};

```

### `MemoryMappedFileAccess`
```
struct __cppobj MemoryMappedFileAccess : IFileAccess
{
  MemoryMappedFileAccess::MemoryMappedFileReadAccess mReadInterface;
  MemoryMappedFileAccess::MemoryMappedFileWriteAccess mWriteInterface;
  std::unique_ptr<FileAccessTransforms> mTransforms;
  std::unordered_map<std::string,MemoryMappedFileAccess::StreamDetails> mStreams;
  Bedrock::Threading::Mutex mStreamsLock;
  std::list<MemoryMappedFileAccess::StreamHandle> mStreamHandles;
  Bedrock::Threading::Mutex mStreamHandlesLock;
  IFileAccess *mInner;
};

```

### `MobEventCommand`
```
struct __cppobj __attribute__((aligned(8))) MobEventCommand : Command
{
  std::string mMobEventName;
  bool mValue;
  bool mValueWasSet;
};

```

### `MeCommand`
```
struct __cppobj MeCommand : MessagingCommand
{
  CommandMessage mMessage;
};

```

### `MessagingCommand`
```
struct __cppobj MessagingCommand : Command:240
{
  bool mRequireChatPerms;
  bool mRequireTellPerms;
};

```

### `MobEffectDefinition`
```
struct MobEffectDefinition
{
  float mEffectRange;
  unsigned int mEffectId;
  int mEffectTime;
  ActorFilterGroup mEntityFilter;
};

```

### `MoveTowardsTargetGoal:672`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) MoveTowardsTargetGoal:672 : Goal
{
  TempEPtr<Actor> mTarget;
  Mob *mMob;
  float mSpeedModifier;
  float mWithin;
  Vec3 mWantedPosition;
};

```

### `MoveDefinition`
```
struct __cppobj MoveDefinition : BehaviorDefinition
{
  std::string mDirectionToMove;
  std::string mDirectionToMoveId;
  std::string mSecondDirectionToMove;
  std::string mSecondDirectionToMoveId;
  int mNumberOfTicksToMove;
  std::string mNumberOfTicksToMoveId;
};

```

### `MoveNode`
```
struct __cppobj MoveNode : BehaviorNode:480
{
  unsigned __int8 mDirectionToMove;
  unsigned __int8 mSecondDirectionToMove;
  int mNumTicksToMove;
  int mNumTicksMoved;
};

```

### `MoveToDefinition`
```
struct __cppobj MoveToDefinition : BehaviorDefinition
{
  Vec3 mPosToMoveTo;
  std::string mPosToMoveToId;
  float mDistanceEpsilon;
  std::string mDistanceEpsilonId;
};

```

### `MoveToNode`
```
struct __cppobj MoveToNode : BehaviorNode:480
{
  Vec3 mPosToMoveTo;
  bool mJumping;
  float mDistanceEpsilon;
};

```

### `MaterialReducerInputContainerController`
```
struct __cppobj MaterialReducerInputContainerController : ContainerController:200
{
  bool mEnabled;
  std::unique_ptr<BlockReducer> mBlockReducer;
  std::unique_ptr<CraftableCompounds> mCraftableCompounds;
};

```

### `MaterialReducerOutputContainerController`
```
struct __cppobj __attribute__((aligned(8))) MaterialReducerOutputContainerController : ContainerController:200
{
  bool mAllowed;
};

```

### `MemoryMappedFileAccess::MemoryMappedFileReadAccess`
```
struct __cppobj MemoryMappedFileAccess::MemoryMappedFileReadAccess : IFileReadAccess
{
};

```

### `MemoryMappedFileAccess::MemoryMappedFileWriteAccess`
```
struct __cppobj MemoryMappedFileAccess::MemoryMappedFileWriteAccess : IFileWriteAccess
{
};

```

### `mce::MathUtility`
```
struct mce::MathUtility
{
  __int8 gap0[1];
};

```

