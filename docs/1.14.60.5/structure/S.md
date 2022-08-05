# S
### `SemVersion`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mMajor
2 | (2) `uint16_t` | mMinor
4 | (2) `uint16_t` | mPatch
8 | (32) `std::string` | mPreRelease
40 | (32) `std::string` | mBuildMeta
72 | (32) `std::string` | mFullVersionString
104 | (1) `bool` | mValidVersion
105 | (1) `bool` | mAnyVersion


### `Shared<CommandContext>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<CommandContext,__gnu_cxx::_S_atomic>` | baseclass_0


### `sysinfo`
Offset | Type | Name
-|-|-|-
0 | (8) `__kernel_long_t` | uptime
8 | (24) `__kernel_ulong_t[3]` | loads
32 | (8) `__kernel_ulong_t` | totalram
40 | (8) `__kernel_ulong_t` | freeram
48 | (8) `__kernel_ulong_t` | sharedram
56 | (8) `__kernel_ulong_t` | bufferram
64 | (8) `__kernel_ulong_t` | totalswap
72 | (8) `__kernel_ulong_t` | freeswap
80 | (2) `__u16` | procs
82 | (2) `__u16` | pad
88 | (8) `__kernel_ulong_t` | totalhigh
96 | (8) `__kernel_ulong_t` | freehigh
104 | (4) `__u32` | mem_unit
108 | (0) `char[]` | _f


### `string_span`
Offset | Type | Name
-|-|-|-
0 | (16) `gsl::basic_string_span<const char,-1>::impl_type` | span_


### `StringKey`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | baseclass_0
40 | (8) `const StringKey *` | mMatch


### `SHPortalRoom::postProcess::$A4BF091F36AB25C4BAD93320DD623D59`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | endPortalEye
8 | (8) `const Block **` | endPortalNoEye


### `SelectorIterator<Player>`
Offset | Type | Name
-|-|-|-
0 | (16) `CommandResultVector` | mTargets
16 | (8) `std::vector<Actor *>::iterator` | mIndex


### `StackRefResultT<FeatureRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `FeatureRefTraits::StackResultStorage` | baseclass_0


### `ShouldTransformData`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `SpinLock`
Offset | Type | Name
-|-|-|-
0 | (1) `std::hash<std::thread::id>` | mThreadHasher
8 | (8) `const size_t` | mNoThreadId
16 | (8) `std::atomic<unsigned long>` | mOwnerThread
24 | (4) `uint32_t` | mOwnerRefCount


### `StrongholdFeature::StrongholdResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | success
8 | (8) `ChunkPos` | location


### `statvfs`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | f_bsize
8 | (8) `unsigned __int64` | f_frsize
16 | (8) `__fsblkcnt_t` | f_blocks
24 | (8) `__fsblkcnt_t` | f_bfree
32 | (8) `__fsblkcnt_t` | f_bavail
40 | (8) `__fsfilcnt_t` | f_files
48 | (8) `__fsfilcnt_t` | f_ffree
56 | (8) `__fsfilcnt_t` | f_favail
64 | (8) `unsigned __int64` | f_fsid
72 | (8) `unsigned __int64` | f_flag
80 | (8) `unsigned __int64` | f_namemax
88 | (24) `int[6]` | __f_spare


### `Social::Events::Event`
Offset | Type | Name
-|-|-|-
0 | (4) `const Social::LocalUserId` | mUserId
8 | (32) `const std::string` | mName
40 | (1) `bool` | mShouldAggregate
44 | (4) `uint32_t` | mCustomAggregationTime
48 | (8) `std::chrono::_V2::steady_clock::time_point` | mEventCreationTime
56 | (4) `int` | mEventTags
64 | (56) `PropertyList` | mProperties
120 | (56) `MeasurementList` | mMeasurements
176 | (1) `bool` | mRecordStamped


### `Social::Events::Property`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (16) `Json::Value` | mValue


### `Social::Events::Measurement`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (16) `Json::Value` | mValue
48 | (4) `int` | mValueDivisorForAverage
52 | (4) `Social::Events::Measurement::AggregationType` | mType


### `SkinData`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<int>` | mVariant
8 | (8) `std::optional<int>` | mMarkVariant


### `Shared<MoveControl>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<MoveControl,__gnu_cxx::_S_atomic>` | baseclass_0


### `ScaffoldingClimberComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `ScaleByAgeComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mStartScale
4 | (4) `float` | mEndScale


### `SchedulerComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCurrentEventIndex


### `SensingComponent`
Offset | Type | Name
-|-|-|-
0 | (56) `SensingComponent::ActorSet` | mSeen
56 | (56) `SensingComponent::ActorSet` | mUnseen


### `SensingComponent::ActorSet`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<ActorUniqueID>::_Hashtable` | _M_h


### `SpawnActorParameters`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSpawnsItemStack
4 | (4) `int` | mSpawnTimeMin
8 | (4) `int` | mSpawnTimeMax
12 | (4) `int` | mSpawnTimer
16 | (4) `LevelSoundEvent` | mSpawnSound
24 | (8) `const Item *` | mItem
32 | (32) `std::string` | mEntityDefinition
64 | (32) `std::string` | mSpawnMethod
96 | (64) `ActorFilterGroup` | mFilters
160 | (1) `bool` | mSingleUse
161 | (1) `bool` | mShouldLeash
164 | (4) `int` | mNumToSpawn


### `SpawnActorComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SpawnActorEntry>` | mSpawnEntries


### `sockaddr_storage`
Offset | Type | Name
-|-|-|-
0 | (2) `sa_family_t` | ss_family
2 | (118) `char[118]` | __ss_padding
120 | (8) `unsigned __int64` | __ss_align


### `Social::GameConnectionInfo`
Offset | Type | Name
-|-|-|-
0 | (2) `Social::ConnectionType` | mType
8 | (32) `std::string` | mHostIpAddress
40 | (32) `std::string` | mUnresolvedUrl
72 | (4) `int` | mPort
80 | (32) `std::string` | mRakNetGUID
112 | (128) `ThirdPartyInfo` | mThirdPartyServerInfo


### `sockaddr_in6`
Offset | Type | Name
-|-|-|-
0 | (2) `sa_family_t` | sin6_family
2 | (2) `in_port_t` | sin6_port
4 | (4) `uint32_t` | sin6_flowinfo
8 | (16) `in6_addr` | sin6_addr
24 | (4) `uint32_t` | sin6_scope_id


### `sockaddr_in`
Offset | Type | Name
-|-|-|-
0 | (2) `sa_family_t` | sin_family
2 | (2) `in_port_t` | sin_port
4 | (4) `in_addr` | sin_addr
8 | (8) `unsigned __int8[8]` | sin_zero


### `ServerToClientHandshakePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mData


### `ServerNetworkHandler::handle::$3CDCE61CA261A057C80CC046802E365C`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *` | this
8 | (8) `const NetworkIdentifier *` | source
16 | (8) `std::set<std::string> *` | downloading


### `StartGamePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (704) `LevelSettings_0` | mSettings
744 | (8) `ActorUniqueID` | mEntityId
752 | (8) `ActorRuntimeID` | mRuntimeId
760 | (4) `GameType` | mEntityGameType
764 | (12) `Vec3` | mPos
776 | (8) `Vec2` | mRot
784 | (32) `std::string` | mLevelId
816 | (32) `std::string` | mLevelName
848 | (24) `ContentIdentity` | mTemplateContentIdentity
872 | (1) `bool` | mIsTrial
873 | (1) `bool` | mIsServerAuthoritativeMovement
880 | (8) `uint64_t` | mLevelCurrentTime
888 | (4) `int` | mEnchantmentSeed
896 | (32) `std::string` | mMultiplayerCorrelationId
928 | (8) `const BlockPalette *` | mBlockPalette
936 | (8) `std::unique_ptr<Tag>` | mBlockPaletteList
944 | (24) `std::vector<ItemData>` | mItemData


### `SetSpawnPositionPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos
48 | (4) `SpawnPositionType` | mSpawnPosType
52 | (1) `bool` | mForcedSpawnPos


### `SetTimePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mTime


### `SetDifficultyPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `Difficulty` | mDifficulty


### `SetCommandsEnabledPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `bool` | mCommandsEnabled


### `ServerNetworkHandler::handle::$088F7A8FB772A70189C6E679C36D5276`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *` | this
8 | (152) `const NetworkIdentifier` | source
160 | (16) `std::shared_ptr<BlockActorDataPacket>` | packet
176 | (1) `const bool` | shouldFilterText


### `ServerNetworkHandler::handle::$ED428D87CD11B947B517AB43C0D6E540`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *` | this
8 | (152) `const NetworkIdentifier` | source


### `ServerPlayer::OnPlayerLoadedCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (ServerPlayer &)>::_Invoker_type` | _M_invoker


### `SerializedSkin`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mId
32 | (32) `std::string` | fullId
64 | (32) `std::string` | mResourcePatch
96 | (32) `std::string` | mDefaultGeometryName
128 | (32) `mce::Image` | mSkinImage
160 | (32) `mce::Image` | mCapeImage
192 | (24) `std::vector<AnimatedImageData>` | mSkinAnimatedImages
216 | (16) `Json::Value` | mGeometryData
232 | (16) `Json::Value` | mGeometryDataMutable
248 | (32) `std::string` | mAnimationData
280 | (32) `std::string` | mCapeId
312 | (1) `bool` | mIsPremium
313 | (1) `bool` | mIsPersona
314 | (1) `bool` | mIsPersonaCapeOnClassicSkin
315 | (1) `TrustedSkinFlag` | mIsTrustedSkin
320 | (24) `std::vector<SerializedPersonaPieceHandle>` | mPersonaPieces
344 | (32) `std::string` | mArmSize
376 | (56) `std::unordered_map<persona::PieceType,TintMapColor>` | mPieceTintColors
432 | (16) `Color` | mSkinColor


### `StructureTemplateDataResponsePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mStructureName
72 | (8) `std::unique_ptr<CompoundTag>` | mStructureTag
80 | (1) `StructureTemplateResponseType_0` | mResponseType


### `StructureTemplate`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (168) `StructureTemplateData` | mStructureTemplateData


### `StructureTemplateData`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$StructureTemplateData
8 | (4) `int` | mFormatVersion
12 | (12) `BlockPos` | mSize
24 | (12) `BlockPos` | mStructureWorldOrigin
40 | (24) `std::vector<int>` | mBlockIndices
64 | (24) `std::vector<int>` | mExtraBlockIndices
88 | (56) `std::unordered_map<std::string,StructureBlockPalette>` | mPalettes
144 | (24) `std::vector<std::unique_ptr<CompoundTag>>` | mEntityData


### `ServerNetworkHandler::_onClientAuthenticated::$40782884DF021EB8A0B68AECF65B4504`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerNetworkHandler *` | this


### `ServerNetworkHandler::_getActiveAndInProgressPlayerCount::$0EBB06E09BB4D485483DF06B22BB4AE5`
Offset | Type | Name
-|-|-|-
0 | (8) `const ServerNetworkHandler *` | this
8 | (8) `mce::UUID *` | excludePlayer
16 | (8) `int *` | numPlayers


### `StringByteInput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataInput` | baseclass_0
8 | (8) `size_t` | mIdx
16 | (16) `string_span` | mBuffer


### `StringByteOutput`
Offset | Type | Name
-|-|-|-
0 | (8) `BytesDataOutput` | baseclass_0
8 | (8) `std::string *` | mBuffer


### `SyncedAttribute`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `float` | mMinValue
36 | (4) `float` | mCurrentValue
40 | (4) `float` | mMaxValue


### `SynchedActorData::DataList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<DataItem>>` | baseclass_0


### `ScoreboardId`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | mRawID
8 | (8) `IdentityDefinition *` | mIdentityDef


### `ScoreboardIdentityPacketInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (8) `PlayerScoreboardId` | mPlayerId


### `StartGamePacket::write::$5498B64B1945F9BCA5158804213C50F5`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ListTag> *` | blockPaletteList


### `StructureEditorData_0`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mStructureName
32 | (32) `std::string` | mDataField
64 | (1) `bool` | mIncludePlayers
65 | (1) `bool` | mShowBoundingBox
66 | (1) `StructureRedstoneSaveMode` | mRedstoneSaveMode
68 | (4) `StructureBlockType` | mType
72 | (96) `StructureSettings_0` | mSettings


### `StructureSettings_0`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPaletteName
32 | (1) `bool` | mIgnoreEntities
33 | (1) `bool` | mIgnoreBlocks
36 | (12) `BlockPos` | mStructureSize
48 | (12) `BlockPos` | mStructureOffset
60 | (12) `Vec3` | mPivot
72 | (8) `ActorUniqueID` | mLastTouchedByPlayer
80 | (1) `Rotation` | mRotation
81 | (1) `Mirror` | mMirror
84 | (4) `float` | mIntegrityValue
88 | (4) `RandomSeed_0` | mIntegritySeed


### `SubpackInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mFolderName
32 | (32) `std::string` | mName
64 | (4) `MemoryTier` | mMemoryTier


### `stdext::reference_wrapper<const Localization>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Localization *` | ptr


### `Stopwatch`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Stopwatch
8 | (8) `double` | _st
16 | (8) `double` | _tt
24 | (8) `double` | _last
32 | (8) `double` | _max
40 | (4) `int` | _count
44 | (4) `int` | _printcounter


### `ServerInstance::initializeServer::$1AF53268373D8F94D8C5F1843C50C698`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unordered_map<PackIdVersion,std::string> *` | packIdToContentKey
8 | (8) `ResourcePackRepository *` | resourcePackRepository


### `Semaphore`
Offset | Type | Name
-|-|-|-
0 | (48) `Bedrock::Threading::ConditionVariable` | mCondition
48 | (40) `Bedrock::Threading::Mutex` | mMutex
88 | (4) `std::atomic<unsigned int>` | mCount


### `ScopedAutoreleasePool`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SimpleEventPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `SimpleEventPacket::Subtype` | mSubtype


### `SetActorLinkPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `ActorLink` | mLink


### `ServerPlayer::recoverR5LostInventoryAndXP::$566869B8F3A3697DD8479CC05753D205`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BlockPos>` | chestPositions


### `ShowCreditsPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mPlayerID
48 | (4) `ShowCreditsPacket::CreditsState` | mCreditsState


### `SetPlayerGameTypePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `GameType` | mPlayerGameType


### `SelectorIterator<Actor>`
Offset | Type | Name
-|-|-|-
0 | (16) `CommandResultVector` | mTargets
16 | (8) `std::vector<Actor *>::iterator` | mIndex


### `ScriptApi::ScriptObjectHandle`
Offset | Type | Name
-|-|-|-
0 | (1) `ScriptApi::EMPTYObjectHandle` | baseclass_0


### `ScriptApi::EMPTYObjectHandle`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ScriptEngineWithContext<ScriptServerContext>::createEntity::$C3475C4D5343D48D4C7832305B127EAE`
Offset | Type | Name
-|-|-|-
0 | (8) `ScriptEngineWithContext<ScriptServerContext> *` | this
8 | (8) `ScriptApi::ScriptObjectHandle *` | entityHandle
16 | (8) `const std::string *` | templateName
24 | (8) `const ScriptApi::ScriptVersionInfo *` | info


### `ScriptCommandCallbackData`
Offset | Type | Name
-|-|-|-
0 | (1) `ScriptApi::ScriptObjectHandle` | mFunction
8 | (32) `std::string` | mCommand
40 | (1) `bool` | mCallbackReceived
48 | (16) `Json::Value` | mData


### `ScriptOnlyComponents<ScriptServerContext>::ScriptOnly`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,Json::Value>` | mLookup


### `ShooterDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (168) `ActorDefinitionIdentifier` | mActorDef
176 | (4) `int` | mAuxValue


### `SpawnActorDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (24) `std::vector<SpawnActorParameters>` | mSpawnParameters


### `ScriptServerActorAttackEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (8) `ActorUniqueID` | mTargetID


### `ScriptEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ScriptEventData
8 | (32) `std::string` | mEventName


### `ScriptServerPlayerAttackedActorEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mPlayerID
48 | (8) `ActorUniqueID` | mAttackedActorID


### `ScriptServerActorHurtEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (4) `int` | mHurtBy
44 | (4) `int` | mDamage
48 | (4) `int` | mAbosrbedDamage
56 | (8) `ActorUniqueID` | mActorID
64 | (8) `ActorUniqueID` | mAttackerID
72 | (12) `BlockPos` | mPos
88 | (32) `std::string` | mCause
120 | (32) `std::string` | mProjectileType


### `ScriptServerActorTickEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID


### `ScriptServerActorSneakChangedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (1) `bool` | mIsSneaking


### `ScriptServerActorStartRidingEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (8) `ActorUniqueID` | mRideID


### `ScriptServerActorStopRidingEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (1) `bool` | mExitFromRider
49 | (1) `bool` | mEntityIsBeingDestroyed
50 | (1) `bool` | mSwitchingRides


### `ScriptServerActorDeathEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (1) `bool` | mKiller
56 | (8) `ActorUniqueID` | mKillerID
64 | (1) `bool` | mBlock
68 | (12) `BlockPos` | mPos
80 | (32) `std::string` | mCause
112 | (1) `bool` | mProjectile
120 | (32) `std::string` | mProjectileType


### `ScriptServerActorRemovedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID


### `ScriptServerActorDefinitionEventTriggeredEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (32) `std::string` | mEvent


### `ScriptServerActorCreatedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID


### `ScriptServerActorUseItemEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (136) `ItemInstance` | mItemUsed
184 | (4) `ItemUseMethod_0` | mUseMethod


### `ScriptServerActorAcquiredItemEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (8) `ActorUniqueID` | mSecondaryActorID
56 | (136) `ItemInstance` | mItem
192 | (4) `int32_t` | mAcquiredAmount
196 | (4) `ItemAcquisitionMethod_0` | mAcquisitionMethod


### `ScriptServerActorDroppedItemEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (136) `ItemInstance` | mItem


### `ScriptServerActorCarriedItemChangedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (136) `ItemInstance` | mPreviousCarriedItem
184 | (136) `ItemInstance` | mCarriedItem
320 | (4) `HandSlot` | mHand


### `ScriptServerActorEquippedArmorEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorId
48 | (136) `ItemInstance` | mItem
184 | (4) `ArmorSlot` | mSlot


### `ScriptServerProjectileHitEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mProjectileID
48 | (8) `ActorUniqueID` | mOwnerID
56 | (8) `ActorUniqueID` | mHitID
64 | (12) `Vec3` | mPosition


### `ScriptServerPlayerPlacedBlockEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (12) `BlockPos` | mPos


### `ScriptServerPlayerDestroyedBlockEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (12) `BlockPos` | mPos
64 | (32) `std::string` | mBlockIdentifier


### `ScriptServerBlockMovedByPistonEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (12) `BlockPos` | mPistonPos
52 | (12) `BlockPos` | mBlockPos
64 | (32) `std::string` | mAction


### `ScriptServerBlockDestructionStoppedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (12) `BlockPos` | mPos
60 | (4) `float` | mProgress


### `ScriptServerBlockDestructionStartedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (12) `BlockPos` | mPos


### `ScriptServerBlockInteractedWithEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (8) `ActorUniqueID` | mActorID
48 | (12) `BlockPos` | mPos


### `ScriptServerBlockExplodedEvent`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (1) `bool` | mActor
48 | (8) `ActorUniqueID` | mActorID
56 | (32) `std::string` | mCause
88 | (32) `std::string` | mIdentifier
120 | (12) `BlockPos` | mPos


### `ScriptCustomEventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mEventName
72 | (16) `Json::Value` | mData


### `SaveTransactionManager::ShowIconFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (bool)>::_Invoker_type` | _M_invoker


### `SetActorDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mId
48 | (24) `SynchedActorData::DataList` | mPackedItems


### `SetActorMotionPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (12) `Vec3` | mMotion


### `ShooterComponent`
Offset | Type | Name
-|-|-|-
0 | (168) `ActorDefinitionIdentifier` | mActorDef
168 | (4) `int` | mAuxValue


### `SitComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `StackStats`
Offset | Type | Name
-|-|-|-
0 | (1) `PackType` | mStackType
4 | (4) `uint32_t` | mPackCount
8 | (8) `double` | mParseTime


### `ScopedLock`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `SummonSpellData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | minActivationRange
4 | (4) `float` | maxActivationRange
8 | (4) `int` | cooldownTime
12 | (4) `float` | weight
16 | (64) `ActorFilterGroup` | targetFilter
80 | (4) `float` | castDuration
84 | (1) `bool` | doCastingAnimation
88 | (4) `int` | particleColor
96 | (24) `std::vector<SummonSpellStage>` | stages
120 | (4) `LevelSoundEvent` | startSound


### `SummonSpellStage`
Offset | Type | Name
-|-|-|-
0 | (4) `SummonShape` | shape
4 | (4) `SummonTarget` | target
8 | (4) `float` | size
12 | (4) `int` | baseDelay
16 | (4) `int` | delayPerSummoning
20 | (4) `int` | summonCap
24 | (4) `float` | summonCapRadius
28 | (4) `ActorType` | entityType
32 | (168) `ActorDefinitionIdentifier` | entityIdentifier
200 | (4) `int` | entityLifespan
204 | (4) `int` | entityCount
208 | (4) `LevelSoundEvent` | stageSoundEvent


### `SendEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | minActivationRange
4 | (4) `float` | maxActivationRange
8 | (4) `int` | cooldownTime
12 | (4) `int` | castDuration
16 | (4) `float` | weight
20 | (1) `bool` | doCastingAnimation
24 | (4) `int` | particleColor
32 | (64) `ActorFilterGroup` | targetFilter
96 | (4) `LevelSoundEvent` | startSound
104 | (24) `std::vector<SendEventStage>` | stages


### `SendEventStage`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | delay
8 | (32) `std::string` | eventName
40 | (4) `LevelSoundEvent` | stageSoundEvent


### `Shared<Village>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Village,__gnu_cxx::_S_atomic>` | baseclass_0


### `Shared<POIInstance>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<POIInstance,__gnu_cxx::_S_atomic>` | baseclass_0


### `SolidityChecker`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (BlockPos &)>::_Invoker_type` | _M_invoker


### `Shared<Village>_0`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Village,__gnu_cxx::_S_atomic>_0` | baseclass_0


### `SlotDropChance`
Offset | Type | Name
-|-|-|-
0 | (4) `EquipmentSlot` | mSlot
4 | (4) `float` | mDropChance


### `Shared<const Potion>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<const Potion,__gnu_cxx::_S_atomic>` | baseclass_0


### `SkinHash`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | geoLength
8 | (64) `uint64_t[8]` | shaData


### `SetLastHurtByPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `ActorType` | mLastHurtBy


### `SetHealthPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mHealth


### `SpawnExperienceOrbPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `Vec3` | mPos
48 | (4) `int` | mCount


### `SlotData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mCollectionName
32 | (4) `int` | mCollectionIndex


### `ScriptServerWeatherEventData`
Offset | Type | Name
-|-|-|-
0 | (40) `ScriptEventData` | baseclass_0
40 | (32) `std::string` | mDimension
72 | (1) `bool` | mRaining
73 | (1) `bool` | mLightning


### `SharedPtr<AirBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<AirBlockItem> *` | pc


### `SharedPtr<Item>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<Item> *` | pc


### `SharedPtr<BlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockItem> *` | pc


### `SuspiciousStewItem::StewEffects`
Offset | Type | Name
-|-|-|-
0 | (280) `std::__array_traits<MobEffectInstance,10>::_Type` | _M_elems


### `SharedPtr<ShovelItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShovelItem> *` | pc


### `SharedPtr<PickaxeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PickaxeItem> *` | pc


### `SharedPtr<HatchetItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HatchetItem> *` | pc


### `SharedPtr<FlintAndSteelItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FlintAndSteelItem> *` | pc


### `SharedPtr<BowItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BowItem> *` | pc


### `SharedPtr<ArrowItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArrowItem> *` | pc


### `SharedPtr<CoalItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoalItem> *` | pc


### `SharedPtr<WeaponItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WeaponItem> *` | pc


### `SharedPtr<BlockPlanterItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockPlanterItem> *` | pc


### `SharedPtr<HoeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HoeItem> *` | pc


### `SharedPtr<ArmorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArmorItem> *` | pc


### `SharedPtr<ShieldItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShieldItem> *` | pc


### `SharedPtr<HangingActorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HangingActorItem> *` | pc


### `SharedPtr<SignItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SignItem> *` | pc


### `SharedPtr<DoorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DoorItem> *` | pc


### `SharedPtr<BucketItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BucketItem> *` | pc


### `SharedPtr<MinecartItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MinecartItem> *` | pc


### `SharedPtr<RedStoneDustItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedStoneDustItem> *` | pc


### `SharedPtr<SnowballItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SnowballItem> *` | pc


### `SharedPtr<BoatItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BoatItem> *` | pc


### `SharedPtr<EnchantedBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnchantedBookItem> *` | pc


### `SharedPtr<EggItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EggItem> *` | pc


### `SharedPtr<CompassItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CompassItem> *` | pc


### `SharedPtr<FishingRodItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FishingRodItem> *` | pc


### `SharedPtr<ClockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClockItem> *` | pc


### `SharedPtr<DyePowderItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DyePowderItem> *` | pc


### `SharedPtr<BedItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BedItem> *` | pc


### `SharedPtr<MapItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MapItem> *` | pc


### `SharedPtr<ShearsItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShearsItem> *` | pc


### `SharedPtr<EnderpearlItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnderpearlItem> *` | pc


### `SharedPtr<PotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PotionItem> *` | pc


### `SharedPtr<BottleItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BottleItem> *` | pc


### `SharedPtr<EnderEyeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnderEyeItem> *` | pc


### `SharedPtr<MobPlacerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MobPlacerItem> *` | pc


### `SharedPtr<ExperiencePotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ExperiencePotionItem> *` | pc


### `SharedPtr<FireChargeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireChargeItem> *` | pc


### `SharedPtr<WritableBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WritableBookItem> *` | pc


### `SharedPtr<WrittenBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WrittenBookItem> *` | pc


### `SharedPtr<EmptyMapItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EmptyMapItem> *` | pc


### `SharedPtr<SkullItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SkullItem> *` | pc


### `SharedPtr<CarrotOnAStickItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CarrotOnAStickItem> *` | pc


### `SharedPtr<FireworksItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireworksItem> *` | pc


### `SharedPtr<FireworkChargeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireworkChargeItem> *` | pc


### `SharedPtr<HorseArmorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HorseArmorItem> *` | pc


### `SharedPtr<RecordItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RecordItem> *` | pc


### `SharedPtr<TridentItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TridentItem> *` | pc


### `SharedPtr<LeadItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LeadItem> *` | pc


### `SharedPtr<ArmorStandItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArmorStandItem> *` | pc


### `SharedPtr<EndCrystalItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndCrystalItem> *` | pc


### `SharedPtr<SplashPotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SplashPotionItem> *` | pc


### `SharedPtr<LingeringPotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LingeringPotionItem> *` | pc


### `SharedPtr<BannerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BannerItem> *` | pc


### `SharedPtr<CrossbowItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CrossbowItem> *` | pc


### `SharedPtr<BannerPatternItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BannerPatternItem> *` | pc


### `SharedPtr<SuspiciousStewItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SuspiciousStewItem> *` | pc


### `SharedPtr<CameraItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CameraItem> *` | pc


### `SharedPtr<CompoundItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CompoundItem> *` | pc


### `SharedPtr<IceBombItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<IceBombItem> *` | pc


### `SharedPtr<ChemistryItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChemistryItem> *` | pc


### `SharedPtr<RapidFertilizerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RapidFertilizerItem> *` | pc


### `SharedPtr<BalloonItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BalloonItem> *` | pc


### `SharedPtr<MedicineItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MedicineItem> *` | pc


### `SharedPtr<SparklerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SparklerItem> *` | pc


### `SharedPtr<GlowStickItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GlowStickItem> *` | pc


### `SharedPtr<AuxDataBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<AuxDataBlockItem> *` | pc


### `SharedPtr<ClothBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClothBlockItem> *` | pc


### `SharedPtr<StoneSlabBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlockItem> *` | pc


### `SharedPtr<CoralFanBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoralFanBlockItem> *` | pc


### `SharedPtr<SeaPickleBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SeaPickleBlockItem> *` | pc


### `SharedPtr<SaplingBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SaplingBlockItem> *` | pc


### `SharedPtr<LeafBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LeafBlockItem> *` | pc


### `SharedPtr<WoodSlabBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoodSlabBlockItem> *` | pc


### `SharedPtr<WaterLilyBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WaterLilyBlockItem> *` | pc


### `SharedPtr<TopSnowBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TopSnowBlockItem> *` | pc


### `SharedPtr<ShulkerBoxBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShulkerBoxBlockItem> *` | pc


### `SharedPtr<BambooBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BambooBlockItem> *` | pc


### `SharedPtr<ScaffoldingBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ScaffoldingBlockItem> *` | pc


### `SharedPtr<BellBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BellBlockItem> *` | pc


### `SharedPtr<ChemistryAuxDataBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChemistryAuxDataBlockItem> *` | pc


### `SharedPtr<ElementBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ElementBlockItem> *` | pc


### `ShapedRecipeConstructor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<ShapedRecipe> (std::string,int,int,const std::vector<RecipeIngredient> &,const std::vector<ItemInstance> &,Util::HashString)>::_Invoker_type` | _M_invoker


### `ShapelessRecipeConstructor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<ShapelessRecipe> (std::string,const std::vector<RecipeIngredient> &,const std::vector<ItemInstance> &,Util::HashString)>::_Invoker_type` | _M_invoker


### `static_vector<Actor *,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::aligned_storage<8,8>::type[1]` | mArray
8 | (8) `size_t` | mSize


### `serialize<EducationLevelSettings>::write::$5D3ECE175654F4C4336B6523D3249746`
Offset | Type | Name
-|-|-|-
0 | (8) `const EducationLevelSettings *` | val


### `SpawnParticleEffectPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `unsigned __int8` | mVanillaDimensionId
40 | (8) `ActorUniqueID` | mActorId
48 | (12) `Vec3` | mPos
64 | (32) `std::string` | mEffectName


### `SmallSet<Actor *>::const_iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *const *` | _M_current


### `SpawnConditions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isOnSurface
1 | (1) `bool` | isInWater
2 | (1) `bool` | isInLava
3 | (1) `bool` | isUnderground
8 | (8) `uint64_t` | delayEndWorldAge
16 | (4) `int` | rawBrightness
20 | (12) `BlockPos` | pos


### `SurfaceBuilderComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ISurfaceBuilder *` | mSurfaceBuilder


### `SurfaceMaterialAttributes`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mTop
8 | (8) `const Block *` | mMid
16 | (8) `const Block *` | mFloor
24 | (8) `const Block *` | mFoundation
32 | (4) `int` | mFloorDepth


### `SurfaceMaterialAdjustmentAttributes`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<SurfaceMaterialAdjustmentAttributes::Element>` | mAdjustments


### `ScatterParams::ScatteredPositions`
Offset | Type | Name
-|-|-|-
0 | (8) `RenderParams *` | mMolangParams
8 | (8) `Random *` | mRandom
16 | (8) `const ScatterParams *` | mScatterParams
24 | (12) `BlockPos` | mOrigin
36 | (4) `uint32_t` | mIterations


### `SlabBlockItem::_useOn::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SmallSet<ActorUniqueID>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ActorUniqueID>` | c


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


### `SharedPtr<BlockLegacy>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockLegacy> *` | pc


### `SharedPtr<AirBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<AirBlock> *` | pc


### `SharedPtr<StoneBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneBlock> *` | pc


### `SharedPtr<GrassBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GrassBlock> *` | pc


### `SharedPtr<DirtBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DirtBlock> *` | pc


### `SharedPtr<PlanksBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PlanksBlock> *` | pc


### `SharedPtr<Sapling>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<Sapling> *` | pc


### `SharedPtr<BedrockBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BedrockBlock> *` | pc


### `SharedPtr<LiquidBlockDynamic>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LiquidBlockDynamic> *` | pc


### `SharedPtr<LiquidBlockStatic>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LiquidBlockStatic> *` | pc


### `SharedPtr<SandBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SandBlock> *` | pc


### `SharedPtr<GravelBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GravelBlock> *` | pc


### `SharedPtr<OreBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<OreBlock> *` | pc


### `SharedPtr<OldLogBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<OldLogBlock> *` | pc


### `SharedPtr<OldLeafBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<OldLeafBlock> *` | pc


### `SharedPtr<SpongeBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SpongeBlock> *` | pc


### `SharedPtr<GlassBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GlassBlock> *` | pc


### `SharedPtr<DispenserBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DispenserBlock> *` | pc


### `SharedPtr<SandStoneBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SandStoneBlock> *` | pc


### `SharedPtr<NoteBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<NoteBlock> *` | pc


### `SharedPtr<BedBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BedBlock> *` | pc


### `SharedPtr<PoweredRailBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PoweredRailBlock> *` | pc


### `SharedPtr<DetectorRailBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DetectorRailBlock> *` | pc


### `SharedPtr<PistonBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PistonBlock> *` | pc


### `SharedPtr<WebBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WebBlock> *` | pc


### `SharedPtr<TallGrass>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TallGrass> *` | pc


### `SharedPtr<DeadBush>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DeadBush> *` | pc


### `SharedPtr<PistonArmBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PistonArmBlock> *` | pc


### `SharedPtr<ClothBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClothBlock> *` | pc


### `SharedPtr<FlowerBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FlowerBlock> *` | pc


### `SharedPtr<MushroomBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MushroomBlock> *` | pc


### `SharedPtr<MetalBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MetalBlock> *` | pc


### `SharedPtr<StoneSlabBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlock> *` | pc


### `SharedPtr<TntBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TntBlock> *` | pc


### `SharedPtr<BookshelfBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BookshelfBlock> *` | pc


### `SharedPtr<ObsidianBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ObsidianBlock> *` | pc


### `SharedPtr<TorchBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TorchBlock> *` | pc


### `SharedPtr<MobSpawnerBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MobSpawnerBlock> *` | pc


### `SharedPtr<StairBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StairBlock> *` | pc


### `SharedPtr<ChestBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChestBlock> *` | pc


### `SharedPtr<RedStoneWireBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedStoneWireBlock> *` | pc


### `SharedPtr<WorkbenchBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WorkbenchBlock> *` | pc


### `SharedPtr<CropBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CropBlock> *` | pc


### `SharedPtr<FarmBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FarmBlock> *` | pc


### `SharedPtr<FurnaceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FurnaceBlock> *` | pc


### `SharedPtr<SignBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SignBlock> *` | pc


### `SharedPtr<DoorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DoorBlock> *` | pc


### `SharedPtr<LadderBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LadderBlock> *` | pc


### `SharedPtr<RailBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RailBlock> *` | pc


### `SharedPtr<LeverBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LeverBlock> *` | pc


### `SharedPtr<PressurePlateBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PressurePlateBlock> *` | pc


### `SharedPtr<RedStoneOreBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedStoneOreBlock> *` | pc


### `SharedPtr<RedstoneTorchBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedstoneTorchBlock> *` | pc


### `SharedPtr<StoneButtonBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneButtonBlock> *` | pc


### `SharedPtr<TopSnowBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TopSnowBlock> *` | pc


### `SharedPtr<IceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<IceBlock> *` | pc


### `SharedPtr<SnowBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SnowBlock> *` | pc


### `SharedPtr<CactusBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CactusBlock> *` | pc


### `SharedPtr<ClayBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClayBlock> *` | pc


### `SharedPtr<ReedBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ReedBlock> *` | pc


### `SharedPtr<JukeboxBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<JukeboxBlock> *` | pc


### `SharedPtr<FenceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FenceBlock> *` | pc


### `SharedPtr<PumpkinBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PumpkinBlock> *` | pc


### `SharedPtr<SoulSandBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SoulSandBlock> *` | pc


### `SharedPtr<LightGemBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LightGemBlock> *` | pc


### `SharedPtr<PortalBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PortalBlock> *` | pc


### `SharedPtr<CakeBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CakeBlock> *` | pc


### `SharedPtr<RepeaterBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RepeaterBlock> *` | pc


### `SharedPtr<InvisibleBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<InvisibleBlock> *` | pc


### `SharedPtr<TrapDoorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TrapDoorBlock> *` | pc


### `SharedPtr<MonsterEggBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MonsterEggBlock> *` | pc


### `SharedPtr<StoneBrickBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneBrickBlock> *` | pc


### `SharedPtr<HugeMushroomBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HugeMushroomBlock> *` | pc


### `SharedPtr<ThinFenceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ThinFenceBlock> *` | pc


### `SharedPtr<MelonBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MelonBlock> *` | pc


### `SharedPtr<StemBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StemBlock> *` | pc


### `SharedPtr<VineBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<VineBlock> *` | pc


### `SharedPtr<FenceGateBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FenceGateBlock> *` | pc


### `SharedPtr<MyceliumBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MyceliumBlock> *` | pc


### `SharedPtr<WaterlilyBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WaterlilyBlock> *` | pc


### `SharedPtr<NetherWartBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<NetherWartBlock> *` | pc


### `SharedPtr<EnchantingTableBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnchantingTableBlock> *` | pc


### `SharedPtr<BrewingStandBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BrewingStandBlock> *` | pc


### `SharedPtr<CauldronBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CauldronBlock> *` | pc


### `SharedPtr<EndPortalBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndPortalBlock> *` | pc


### `SharedPtr<EndPortalFrameBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndPortalFrameBlock> *` | pc


### `SharedPtr<DragonEggBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DragonEggBlock> *` | pc


### `SharedPtr<RedstoneLampBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedstoneLampBlock> *` | pc


### `SharedPtr<DropperBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DropperBlock> *` | pc


### `SharedPtr<ActivatorRailBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ActivatorRailBlock> *` | pc


### `SharedPtr<CocoaBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CocoaBlock> *` | pc


### `SharedPtr<EnderChestBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnderChestBlock> *` | pc


### `SharedPtr<TripWireHookBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TripWireHookBlock> *` | pc


### `SharedPtr<TripWireBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TripWireBlock> *` | pc


### `SharedPtr<CommandBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CommandBlock> *` | pc


### `SharedPtr<BeaconBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BeaconBlock> *` | pc


### `SharedPtr<WallBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WallBlock> *` | pc


### `SharedPtr<FlowerPotBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FlowerPotBlock> *` | pc


### `SharedPtr<CarrotBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CarrotBlock> *` | pc


### `SharedPtr<PotatoBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PotatoBlock> *` | pc


### `SharedPtr<WoodButtonBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoodButtonBlock> *` | pc


### `SharedPtr<SkullBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SkullBlock> *` | pc


### `SharedPtr<AnvilBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<AnvilBlock> *` | pc


### `SharedPtr<WeightedPressurePlateBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WeightedPressurePlateBlock> *` | pc


### `SharedPtr<ComparatorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ComparatorBlock> *` | pc


### `SharedPtr<DaylightDetectorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DaylightDetectorBlock> *` | pc


### `SharedPtr<RedstoneBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedstoneBlock> *` | pc


### `SharedPtr<HopperBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HopperBlock> *` | pc


### `SharedPtr<QuartzBlockBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<QuartzBlockBlock> *` | pc


### `SharedPtr<WoodSlabBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoodSlabBlock> *` | pc


### `SharedPtr<ColoredBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ColoredBlock> *` | pc


### `SharedPtr<StainedGlassPaneBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StainedGlassPaneBlock> *` | pc


### `SharedPtr<NewLeafBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<NewLeafBlock> *` | pc


### `SharedPtr<NewLogBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<NewLogBlock> *` | pc


### `SharedPtr<SlimeBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SlimeBlock> *` | pc


### `SharedPtr<PrismarineBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PrismarineBlock> *` | pc


### `SharedPtr<SeaLanternBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SeaLanternBlock> *` | pc


### `SharedPtr<HayBlockBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HayBlockBlock> *` | pc


### `SharedPtr<WoolCarpetBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoolCarpetBlock> *` | pc


### `SharedPtr<DoublePlantBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DoublePlantBlock> *` | pc


### `SharedPtr<BannerBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BannerBlock> *` | pc


### `SharedPtr<StoneSlabBlock2>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlock2> *` | pc


### `SharedPtr<GrassPathBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GrassPathBlock> *` | pc


### `SharedPtr<ItemFrameBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ItemFrameBlock> *` | pc


### `SharedPtr<ChorusFlowerBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChorusFlowerBlock> *` | pc


### `SharedPtr<UndyedShulkerBoxBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<UndyedShulkerBoxBlock> *` | pc


### `SharedPtr<FrostedIceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FrostedIceBlock> *` | pc


### `SharedPtr<EndRodBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndRodBlock> *` | pc


### `SharedPtr<EndGatewayBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EndGatewayBlock> *` | pc


### `SharedPtr<MagmaBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MagmaBlock> *` | pc


### `SharedPtr<RotatedPillarBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RotatedPillarBlock> *` | pc


### `SharedPtr<StructureVoid>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StructureVoid> *` | pc


### `SharedPtr<ShulkerBoxBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShulkerBoxBlock> *` | pc


### `SharedPtr<GlazedTerracottaBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GlazedTerracottaBlock> *` | pc


### `SharedPtr<ConcreteBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ConcreteBlock> *` | pc


### `SharedPtr<ConcretePowderBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ConcretePowderBlock> *` | pc


### `SharedPtr<ChorusPlantBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChorusPlantBlock> *` | pc


### `SharedPtr<StainedGlassBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StainedGlassBlock> *` | pc


### `SharedPtr<CameraBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CameraBlock> *` | pc


### `SharedPtr<PodzolBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PodzolBlock> *` | pc


### `SharedPtr<BeetrootBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BeetrootBlock> *` | pc


### `SharedPtr<StonecutterBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StonecutterBlock> *` | pc


### `SharedPtr<NetherReactorBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<NetherReactorBlock> *` | pc


### `SharedPtr<MovingBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MovingBlock> *` | pc


### `SharedPtr<ObserverBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ObserverBlock> *` | pc


### `SharedPtr<StructureBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StructureBlock> *` | pc


### `SharedPtr<StrippedLogBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StrippedLogBlock> *` | pc


### `SharedPtr<BlueIceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlueIceBlock> *` | pc


### `SharedPtr<FireBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireBlock> *` | pc


### `SharedPtr<ChemistryTableBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChemistryTableBlock> *` | pc


### `SharedPtr<UnderwaterTorchBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<UnderwaterTorchBlock> *` | pc


### `SharedPtr<ChemicalHeatBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChemicalHeatBlock> *` | pc


### `SharedPtr<ColoredTorchBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ColoredTorchBlock> *` | pc


### `SharedPtr<ElementBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ElementBlock> *` | pc


### `SharedPtr<Coral>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<Coral> *` | pc


### `SharedPtr<CoralBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoralBlock> *` | pc


### `SharedPtr<CoralFan>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoralFan> *` | pc


### `SharedPtr<CoralFanHang>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoralFanHang> *` | pc


### `SharedPtr<KelpBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<KelpBlock> *` | pc


### `SharedPtr<DriedKelpBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DriedKelpBlock> *` | pc


### `SharedPtr<SeaGrass>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SeaGrass> *` | pc


### `SharedPtr<SeaPickle>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SeaPickle> *` | pc


### `SharedPtr<ConduitBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ConduitBlock> *` | pc


### `SharedPtr<BubbleColumnBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BubbleColumnBlock> *` | pc


### `SharedPtr<TurtleEggBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TurtleEggBlock> *` | pc


### `SharedPtr<BarrierBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BarrierBlock> *` | pc


### `SharedPtr<ScaffoldingBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ScaffoldingBlock> *` | pc


### `SharedPtr<BambooBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BambooBlock> *` | pc


### `SharedPtr<BambooSapling>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BambooSapling> *` | pc


### `SharedPtr<StoneSlabBlock3>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlock3> *` | pc


### `SharedPtr<StoneSlabBlock4>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlock4> *` | pc


### `SharedPtr<LecternBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LecternBlock> *` | pc


### `SharedPtr<GrindstoneBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GrindstoneBlock> *` | pc


### `SharedPtr<BlastFurnaceBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlastFurnaceBlock> *` | pc


### `SharedPtr<SmokerBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SmokerBlock> *` | pc


### `SharedPtr<CartographyTableBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CartographyTableBlock> *` | pc


### `SharedPtr<BarrelBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BarrelBlock> *` | pc


### `SharedPtr<LoomBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LoomBlock> *` | pc


### `SharedPtr<BellBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BellBlock> *` | pc


### `SharedPtr<SweetBerryBushBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SweetBerryBushBlock> *` | pc


### `SharedPtr<LanternBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LanternBlock> *` | pc


### `SharedPtr<CampfireBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CampfireBlock> *` | pc


### `SharedPtr<JigsawBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<JigsawBlock> *` | pc


### `SharedPtr<WoodBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoodBlock> *` | pc


### `SharedPtr<ComposterBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ComposterBlock> *` | pc


### `SharedPtr<LightBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LightBlock> *` | pc


### `SharedPtr<WitherRoseBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WitherRoseBlock> *` | pc


### `SharedPtr<BeehiveBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BeehiveBlock> *` | pc


### `SharedPtr<HoneyBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HoneyBlock> *` | pc


### `SharedPtr<HoneycombBlock>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HoneycombBlock> *` | pc


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
30776 | (8) `size_t` | mCenterSubChunkIndex
30784 | (8) `BlockSource *` | mSource
30792 | (1) `bool` | mOriginalLighting
30793 | (1) `SubChunkRelighter::LightPair` | mDefaultLightPair
30800 | (8) `const Block *` | mDefaultBlock


### `SubChunkRelighter::LightPair`
Offset | Type | Name
-|-|-|-
0 | (1) `SubChunkBrightnessStorage::LightPair::$C82CAE701F9C96804622E94D041F6011` | _anon_0


### `SubChunkBrightnessStorage::LightPair::$C82CAE701F9C96804622E94D041F6011`
Offset | Type | Name
-|-|-|-
0 | (1) `SubChunkBrightnessStorage::LightPair::$C82CAE701F9C96804622E94D041F6011::$FEA8D14758525B4BCA5C0100E71C9EA7` | _anon_0
1 | (1) `uint8_t` | raw


### `SubChunkBrightnessStorage::LightPair::$C82CAE701F9C96804622E94D041F6011::$FEA8D14758525B4BCA5C0100E71C9EA7`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `SubChunkBrightnessStorage::LightPair`
Offset | Type | Name
-|-|-|-
0 | (1) `SubChunkBrightnessStorage::LightPair::$C82CAE701F9C96804622E94D041F6011` | _anon_0


### `SubChunkBlockPos`
Offset | Type | Name
-|-|-|-
0 | (4) `SubChunkBlockPos::$F507DBCC95B5F1F0349D6A6FBF2E560F` | _anon_0


### `SubChunkBlockPos::$F507DBCC95B5F1F0349D6A6FBF2E560F`
Offset | Type | Name
-|-|-|-
0 | (3) `SubChunkBlockPos::$F507DBCC95B5F1F0349D6A6FBF2E560F::$E23C018BDD51DA9542B42FDC09D6AA49` | _anon_0
1 | (4) `uint32_t` | packed


### `SubChunkBlockPos::$F507DBCC95B5F1F0349D6A6FBF2E560F::$E23C018BDD51DA9542B42FDC09D6AA49`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | x
1 | (1) `uint8_t` | y
2 | (1) `uint8_t` | z


### `static_vector<const Block *,4096>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | mPtr


### `SubChunkBlockStorage::GenericPalette`
Offset | Type | Name
-|-|-|-
0 | (32768) `std::aligned_storage<8,8>::type[4096]` | mArray
32768 | (8) `size_t` | mSize


### `SubChunkStorageFormat`
Offset | Type | Name
-|-|-|-
0 | (1) `SubChunkStorageFormat::$4A48E9E2C062D44B94D66378C25E9D86` | _anon_0
1 | (1) `char` | raw


### `SubChunkStorageFormat::$4A48E9E2C062D44B94D66378C25E9D86`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::makePrunedCopy::$5C37BA6189407DC409FF9D08D5F65A9E`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,2> *` | remappingLookup


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::makePrunedCopy::$97D49D667F65B59D64A1CF6C21EF1D86`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,4> *` | remappingLookup


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::makePrunedCopy::$9D7F1A052824D1DF666118F69FC3070A`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,8> *` | remappingLookup


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::makePrunedCopy::$05DA6B700FA0222B559606B9A00A1F7D`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,16> *` | remappingLookup


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::makePrunedCopy::$CC93A48B8F76E12549E857D7142C04AB`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,32> *` | remappingLookup


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::makePrunedCopy::$B8D88B99E42BC318262126A78F11A7E5`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,64> *` | remappingLookup


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::makePrunedCopy::$3817DFAD228892A6745DC344E6C4662F`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,256> *` | remappingLookup


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::SubChunkBlockStoragePaletted::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::makePrunedCopy::$2185D287A3144BABD0B238662BD24236`
Offset | Type | Name
-|-|-|-
0 | (8) `std::array<unsigned long,4096> *` | remappingLookup


### `SubChunkBrightnessStorage::reset::$7B0383690E49E4B7542F6080AC16EED4`
Offset | Type | Name
-|-|-|-
0 | (1) `SubChunkBrightnessStorage::LightPair` | lp
1 | (1) `uint8_t` | b


### `SubChunkLightIndex`
Offset | Type | Name
-|-|-|-
0 | (4) `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF` | _anon_0


### `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF`
Offset | Type | Name
-|-|-|-
0 | (4) `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF::$C5E0CE72C99D254AFB51B3E72BF5B343` | _anon_0
1 | (4) `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF::$1B14A3B4ACC00D53AE1F0B03F21ED5AD` | _anon_1
2 | (4) `uint32_t` | mData


### `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF::$C5E0CE72C99D254AFB51B3E72BF5B343`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | _bf_0
2 | (1) `__int8` | _bf_2
3 | (1) `__int8` | _padding_3


### `SubChunkLightIndex::$D642419CEF3A4ECC892D938F72F5EEEF::$1B14A3B4ACC00D53AE1F0B03F21ED5AD`
Offset | Type | Name
-|-|-|-
0 | (4) `__int32` | _bf_0


### `SpikeFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const SpikeFeature::EndSpike *` | mSpike
32 | (12) `BlockPos` | mCrystalBeamTarget
44 | (1) `bool` | mCrystalInvulnerable


### `ScatterParams`
Offset | Type | Name
-|-|-|-
0 | (264) `ScatterParams::CoordinateRange` | mX
264 | (264) `ScatterParams::CoordinateRange` | mZ
528 | (264) `ScatterParams::CoordinateRange` | mHeight
792 | (4) `ScatterParams::CoordinateEvaluationOrder` | mEvalOrder
800 | (136) `ScatterParams::ChanceInformation` | mScatterChance
936 | (128) `ExpressionNode` | mIterations


### `ScatterParams::CoordinateRange`
Offset | Type | Name
-|-|-|-
0 | (128) `ExpressionNode` | mMinOrSingleValue
128 | (128) `ExpressionNode` | mMax
256 | (4) `uint32_t` | mGridStepCount
260 | (4) `ScatterParams::RandomDistributionType` | mDistribution


### `ScatterParams::ChanceInformation`
Offset | Type | Name
-|-|-|-
0 | (128) `ExpressionNode` | mChancePercent
128 | (4) `int` | mNumerator
132 | (4) `int` | mDenominator


### `SharePtrRefTraits<PerlinSimplexNoise>::WeakStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PerlinSimplexNoise>` | mHandle


### `StackRefResultT<SharePtrRefTraits<PerlinSimplexNoise> >`
Offset | Type | Name
-|-|-|-
0 | (16) `SharePtrRefTraits<PerlinSimplexNoise>::StackResultStorage` | baseclass_0


### `SharePtrRefTraits<PerlinSimplexNoise>::StackResultStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<PerlinSimplexNoise>` | mValue


### `StackRefResult<IFeature>`
Offset | Type | Name
-|-|-|-
0 | (24) `FeatureRefTraits::StackResultStorage` | baseclass_0


### `Shared<RoomDefinition>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<RoomDefinition,__gnu_cxx::_S_atomic>` | baseclass_0


### `SharedLock`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_lock<std::shared_timed_mutex>::mutex_type *` | _M_pm
8 | (1) `bool` | _M_owns


### `StructureIntegrityProcessor`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mIntegrity
4 | (4) `RandomSeed` | mStartSeed


### `StructureBlockPalette`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<CompoundTag>>` | mStructurePaletteIdToSerializationId
24 | (56) `std::unordered_map<unsigned long,StructureBlockPalette::BlockPositionData>` | mBlockPositionData


### `StructureTemplate::_fillBlockInfo::$2FA47CEBC638377704193C5643AD3DC1`
Offset | Type | Name
-|-|-|-
0 | (8) `std::map<const Block *,int> *` | blockToIndex
8 | (8) `StructureBlockPalette *` | structureBlockPalette
16 | (8) `const Block *` | voidBlock


### `StructureBlockPalette::BlockPositionData`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<CompoundTag>` | mBlockEntityData
8 | (24) `std::vector<StructureBlockPalette::TickingQueueData>` | mTickData


### `StructureDataLoadHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `DataLoadHelper` | baseclass_0
8 | (12) `BlockPos` | mStructurePlacementLocation
20 | (12) `BlockPos` | mStructureWorldOrigin
32 | (12) `Vec3` | mPivot
48 | (8) `ActorUniqueID` | mOwner
56 | (1) `Rotation_0` | mRotation
57 | (1) `Mirror_0` | mMirror
64 | (8) `Level *` | mLevel
72 | (56) `std::unordered_map<ActorUniqueID,ActorUniqueID>` | mOldIDToNewID


### `Shared<SaveTransactionManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<SaveTransactionManager,__gnu_cxx::_S_atomic>` | baseclass_0


### `Shared<Core::FileStorageArea>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Core::FileStorageArea,__gnu_cxx::_S_atomic>` | baseclass_0


### `SpecificEnchantFunction::EnchantInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `Enchant::Type` | enchantment
4 | (4) `int` | level


### `Shared<RopeSystem>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<RopeSystem,__gnu_cxx::_S_atomic>` | baseclass_0


### `ScoreInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `bool` | mValid
12 | (4) `int` | mValue


### `ScoreInfoRef`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `bool` | mValid
16 | (8) `int *` | mValue


### `ServerScoreboard::unit_test_ctor_t`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ServerScoreboard::ScoreChangedLevelCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const ScoreboardId &)>::_Invoker_type` | _M_invoker


### `ServerScoreboard::ScoreRemovedLevelCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const ScoreboardId &)>::_Invoker_type` | _M_invoker


### `ServerScoreboard::SetDisplayObjectiveLevelCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const std::string &,const DisplayObjective &)>::_Invoker_type` | _M_invoker


### `ServerScoreboard::ClearDisplayObjectiveLevelCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const std::string &,const DisplayObjective &)>::_Invoker_type` | _M_invoker


### `ServerScoreboard::IdentityUpdatedLevelCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const ScoreboardId &)>::_Invoker_type` | _M_invoker


### `SlotDescriptor`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSlot
8 | (24) `std::vector<ItemInstance>` | mAcceptedItems
32 | (8) `const Item *` | mItem
40 | (32) `std::string` | mInteractText
72 | (128) `DefinitionTrigger` | mOnEquip
200 | (128) `DefinitionTrigger` | mOnUnequip


### `SeatDescription`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPosition
12 | (4) `int` | mMinSeatCount
16 | (4) `int` | mMaxSeatCount
20 | (4) `float` | mSeatRotation
24 | (1) `bool` | mLockRiderRotation
28 | (4) `float` | mLockRiderRotationDegrees


### `Shareable`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | itemId
4 | (4) `int` | itemAux
8 | (4) `int` | wantAmount
12 | (4) `int` | surplusAmount
16 | (4) `int` | maxAmount
20 | (4) `int` | craftIntoItem
24 | (4) `int` | craftIntoItemAux
28 | (4) `int` | itemPriority


### `StackRefResultT<EntityRegistryRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityRegistryRefTraits::StackResultStorage` | baseclass_0


### `StackedGraphBars`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::array<float,2>>` | mData
24 | (24) `std::vector<StackedGraphBars::ColorKey>` | mColors
48 | (4) `float` | mHeight
56 | (32) `std::string` | mGraphName
88 | (4) `int` | mMaxBars


### `ScriptApi::ScriptVersionInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int32_t` | mMajorVersion
4 | (4) `int32_t` | mMinVerssion


### `ScriptApi::EventTracking`
Offset | Type | Name
-|-|-|-
0 | (1) `ScriptApi::ScriptObjectHandle` | mFunctionObject


### `ScriptCommand`
Offset | Type | Name
-|-|-|-
0 | (4) `ScriptCommandId` | mId
8 | (32) `std::string` | mCommand
40 | (1) `ScriptApi::ScriptObjectHandle` | mCallback


### `ScriptApi::ScriptSystemInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mInitialized
8 | (32) `std::string` | mSystemName
40 | (1) `ScriptApi::ScriptObjectHandle` | mSystemObject
44 | (8) `ScriptApi::ScriptVersionInfo` | mVersionInfo


### `ScriptEngine::ScriptQueueData`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mScriptPath
32 | (32) `std::string` | mScriptName
64 | (32) `std::string` | mScriptContent
96 | (32) `std::string` | mPackID
128 | (32) `std::string` | mPackVersion
160 | (8) `uint64_t` | mScriptHash


### `ScriptQueryComponent`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<std::string>` | mFilters
56 | (4) `ScriptQueryComponent::ViewType` | mType
64 | (32) `std::string` | mSpatialTag
96 | (96) `std::string[3]` | mCoordinateTags


### `ScriptApi::WORKAROUNDS::tempActorComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mID


### `ScriptApi::WORKAROUNDS::tempLevelComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ScoreboardCommand::SetScoreOutput`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSuccessCount
4 | (4) `int` | mFirstNewScore
8 | (32) `std::string` | mFirstSuccess


### `StopSoundPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mName
72 | (1) `bool` | mStopAll


### `SetTitlePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `SetTitlePacket::TitleType` | mType
40 | (32) `std::string` | mTitleText
72 | (4) `int` | mFadeInTime
76 | (4) `int` | mStayTime
80 | (4) `int` | mFadeOutTime


### `ShareableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `StompBlockGoal::OptionalBlockPos`
Offset | Type | Name
-|-|-|-
0 | (16) `std::_Optional_base<BlockPos>` | baseclass_0


### `SubtreeDefinition::load::$2A59718DDDE9B252D2E2D9E1042A23A6`
Offset | Type | Name
-|-|-|-
0 | (8) `SubtreeDefinition *` | this


### `StructureBlockPalette::TickingQueueData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTickDelay


### `sched_param`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | sched_priority


### `sockaddr`
Offset | Type | Name
-|-|-|-
0 | (2) `sa_family_t` | sa_family
2 | (14) `char[14]` | sa_data


### `StrAndBool`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | str
8 | (1) `bool` | b


### `stat`
Offset | Type | Name
-|-|-|-
0 | (8) `__dev_t` | st_dev
8 | (8) `__ino_t` | st_ino
16 | (8) `__nlink_t` | st_nlink
24 | (4) `__mode_t` | st_mode
28 | (4) `__uid_t` | st_uid
32 | (4) `__gid_t` | st_gid
36 | (4) `int` | __pad0
40 | (8) `__dev_t` | st_rdev
48 | (8) `__off_t` | st_size
56 | (8) `__blksize_t` | st_blksize
64 | (8) `__blkcnt_t` | st_blocks
72 | (16) `timespec` | st_atim
88 | (16) `timespec` | st_mtim
104 | (16) `timespec` | st_ctim
120 | (24) `__syscall_slong_t[3]` | __glibc_reserved


### `StringToPackTypeMap_t`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,PackType>::_Hashtable` | _M_h


### `SemVersion::any_version_constructor`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ScheduledCallback`
Offset | Type | Name
-|-|-|-
0 | (8) `time_t` | mTime
8 | (16) `std::weak_ptr<bool>` | mExistenceTracker
24 | (32) `std::function<void ()>` | mCallback
56 | (1) `bool` | mShouldCheckExistence


### `stack_t`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ss_sp
8 | (4) `int` | ss_flags
16 | (8) `size_t` | ss_size


### `sigaction`
Offset | Type | Name
-|-|-|-
0 | (8) `sigaction::$A264F945D93E77C42166F8517888D535` | __sigaction_handler
8 | (128) `__sigset_t` | sa_mask
136 | (4) `int` | sa_flags
144 | (8) `void (*)(void)` | sa_restorer


### `sigaction::$A264F945D93E77C42166F8517888D535`
Offset | Type | Name
-|-|-|-
0 | (8) `__sighandler_t` | sa_handler
1 | (8) `void (*)(int, siginfo_t *, void *)` | sa_sigaction


### `siginfo_t`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | si_signo
4 | (4) `int` | si_errno
8 | (4) `int` | si_code
12 | (4) `int` | __pad0
16 | (112) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A` | _sifields


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A`
Offset | Type | Name
-|-|-|-
0 | (112) `int[28]` | _pad
1 | (8) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$34A68472B6FD99AB74EBE1055AA656AE` | _kill
2 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$CCD53A48A999AABAD7234802D7894EC3` | _timer
3 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$1083567770C9944ECE9586E3D60D7164` | _rt
4 | (32) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$269BD37B8033F496E0DA26224222815C` | _sigchld
5 | (32) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB` | _sigfault
6 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$8332D0DE0C0D8B400D7F5CB203041E7E` | _sigpoll
7 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$5BF7061F11A02461448786E25380AC9A` | _sigsys


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$34A68472B6FD99AB74EBE1055AA656AE`
Offset | Type | Name
-|-|-|-
0 | (4) `__pid_t` | si_pid
4 | (4) `__uid_t` | si_uid


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$CCD53A48A999AABAD7234802D7894EC3`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | si_tid
4 | (4) `int` | si_overrun
8 | (8) `__sigval_t` | si_sigval


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$1083567770C9944ECE9586E3D60D7164`
Offset | Type | Name
-|-|-|-
0 | (4) `__pid_t` | si_pid
4 | (4) `__uid_t` | si_uid
8 | (8) `__sigval_t` | si_sigval


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$269BD37B8033F496E0DA26224222815C`
Offset | Type | Name
-|-|-|-
0 | (4) `__pid_t` | si_pid
4 | (4) `__uid_t` | si_uid
8 | (4) `int` | si_status
16 | (8) `__clock_t` | si_utime
24 | (8) `__clock_t` | si_stime


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | si_addr
8 | (2) `__int16` | si_addr_lsb
16 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB::$5BC825E6F32707B864090E1402CAE52B` | _bounds


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB::$5BC825E6F32707B864090E1402CAE52B`
Offset | Type | Name
-|-|-|-
0 | (16) `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB::$5BC825E6F32707B864090E1402CAE52B::$500E99076578AD283C95318D41ACB4BA` | _addr_bnd
1 | (4) `__uint32_t` | _pkey


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$9E99AB014780417E3FB416F9C93D05FB::$5BC825E6F32707B864090E1402CAE52B::$500E99076578AD283C95318D41ACB4BA`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | _lower
8 | (8) `void *` | _upper


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$8332D0DE0C0D8B400D7F5CB203041E7E`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | si_band
8 | (4) `int` | si_fd


### `siginfo_t::$9514A1E9F77EB70C94BB89C64268A47A::$5BF7061F11A02461448786E25380AC9A`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | _call_addr
8 | (4) `int` | _syscall
12 | (4) `unsigned int` | _arch


### `sigset_t`
Offset | Type | Name
-|-|-|-
0 | (128) `unsigned __int64[16]` | __val


### `SubChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `DirtyTicksCounter` | mDirtyTicksCounter
8 | (8) `std::unique_ptr<SubChunkBrightnessStorage>` | mLight
16 | (16) `std::unique_ptr<SubChunkBlockStorage>[2]` | mBlocks
32 | (16) `SubChunkBlockStorage *[2]` | mBlocksReadPtr
48 | (8) `SpinLock *` | mWriteLock


### `ScoreboardIdentityRef`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mObjectiveReferences
8 | (16) `ScoreboardId` | mScoreboardId


### `SparklerItem::ColorInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `ItemColor` | mDyeId
1 | (1) `CompoundType` | mColorCompound
4 | (4) `int` | mVariantIndex
8 | (4) `int` | mRGB


### `SmallSet<WorkerPool *>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<WorkerPool *>` | c


### `ServiceOverrider<bool (*)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>`
Offset | Type | Name
-|-|-|-
0 | (104) `ThreadLocal<bool (**)(const char *,const char *,const char *,bool,int,const char *,const char *,bool)>` | mService
104 | (8) `bool (**)(const char *, const char *, const char *, bool, int, const char *, const char *, bool)` | mDefaultService


### `ServerMetricsImpl`
Offset | Type | Name
-|-|-|-
0 | (8) `ServerMetrics` | baseclass_0
8 | (8) `std::chrono::_V2::steady_clock::time_point` | mLastPeriodicSend
16 | (56) `std::unordered_map<NetworkIdentifier,ServerMetricsImpl::DataTransferred>` | mLastMeasured
72 | (8) `ServerCommunicationInterface *` | mServerCommunicationInterface
80 | (1) `bool` | mEnableMetricQueuing
88 | (616) `moodycamel::ConcurrentQueue<std::unique_ptr<com::mojang::clacks::protocol::MetricReport>,moodycamel::ConcurrentQueueDefaultTraits>` | mMetricsQueue


### `ServerMetrics`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ServerMetrics


### `SmoothStoneSelector`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSelector` | baseclass_0


### `SavedData`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$SavedData
8 | (1) `bool` | mDirty
16 | (32) `std::string` | mId


### `StructureManager`
Offset | Type | Name
-|-|-|-
0 | (56) `SharedMutex` | mRepositoryMutex
56 | (56) `std::unordered_map<std::string,std::unique_ptr<LegacyStructureTemplate>>` | mLegacyStructureRepository
112 | (56) `std::unordered_map<std::string,std::unique_ptr<StructureTemplate>>` | mStructureRepository
168 | (8) `LevelStorage *` | mLevelStorage
176 | (8) `ResourcePackManager *` | mPackManager


### `SharedMutex`
Offset | Type | Name
-|-|-|-
0 | (56) `std::__shared_timed_mutex_base` | baseclass_0


### `SharePtrRefTraits<PerlinSimplexNoise>::OwnerStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<PerlinSimplexNoise>` | mValue


### `Scheduler`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mTotalFrames
4 | (4) `uint32_t` | mStarvedFrames
8 | (4) `uint32_t` | mPromotionFrames
12 | (4) `uint32_t` | mTargetFPS
16 | (4) `uint32_t` | mEffectiveFPS
20 | (4) `uint32_t` | mFramesOverBound
24 | (8) `double` | mAverageCallbackDuration
32 | (8) `double` | mTotalCoroutineDuration
40 | (8) `size_t` | mTotalRunCoroutines
48 | (8) `double` | mCoroutineTimeLimit
56 | (8) `std::unique_ptr<WorkerPool>` | mCoroutinePool
64 | (8) `std::chrono::time_point<std::chrono::_V2::system_clock,std::chrono::duration<long,std::ratio<1,1000000000> > >` | mNextStarveCheckTime
72 | (8) `std::thread::id` | mThreadID


### `SubClientConnectionRequest`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<UnverifiedCertificate>` | mCertificateData
8 | (8) `Unique<Certificate>` | mCertificate
16 | (8) `Unique<WebToken>` | mRawToken


### `ScorePacketInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (32) `std::string` | mObjectiveName
48 | (4) `int` | mScoreValue
52 | (1) `IdentityDefinition::Type` | mIdentityType
56 | (8) `PlayerScoreboardId` | mPlayerId
64 | (8) `ActorUniqueID` | mEntityId
72 | (32) `std::string` | mFakePlayerName


### `ScriptEngineWithContext<ScriptServerContext>`
Offset | Type | Name
-|-|-|-
0 | (416) `ScriptEngine` | baseclass_0
416 | (16) `const string_span` | SCRIPT_FILE_EXTENSION
432 | (32) `const std::string` | SCRIPT_ENTITY_TYPE
464 | (32) `const std::string` | SCRIPT_ITEM_ENTITY_TYPE
496 | (40) `ScriptServerContext` | mContext
536 | (296) `ScriptTemplateFactory<ScriptServerContext>` | mFactory
832 | (48) `ScriptOnlyComponents<ScriptServerContext>` | mScriptComponents
880 | (48) `ScriptOnlyEventsData<ScriptServerContext>` | mScriptEvents
928 | (80) `std::deque<std::unique_ptr<const ScriptEventData>>` | mEventQueue
1008 | (56) `ScriptCommandCallbackQueue` | mCommandPendingCallbackQueue
1064 | (112) `ScriptQueries` | mQueries
1176 | (1) `bool` | mWorkaroundViewUpdate


### `ScriptEngine`
Offset | Type | Name
-|-|-|-
0 | (48) `ScriptApi::ScriptFramework` | baseclass_0
48 | (8) `ScriptApi::ScriptCallbackInterface` | baseclass_30
56 | (56) `std::unordered_map<std::string,std::vector<ScriptApi::EventTracking>>` | mListeningEvents
112 | (80) `std::deque<ScriptCommand>` | mCommandRequestQueue
192 | (8) `std::unique_ptr<ScriptBinderTemplateController>` | mBinderFactory
200 | (1) `bool` | mInitialized
204 | (4) `const ScriptApi::ApiScriptType` | mApiScriptType
208 | (56) `ScriptEngine::ScriptSet_t` | mRunningScripts
264 | (80) `ScriptEngine::ScriptQueue_t` | mPendingScriptQueue
344 | (56) `std::unordered_map<std::string,EventInfo>` | mMapEventInfo
400 | (8) `std::unique_ptr<ScriptEventCoordinator>` | mScriptEventCoordinator
408 | (8) `ScriptLoggerConfig` | mLoggerConfig


### `ScriptApi::ScriptFramework`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ScriptFramework
8 | (8) `std::unique_ptr<ScriptApi::ScriptLanguageInterface>` | mLanguageInterface
16 | (24) `std::vector<ScriptApi::ScriptSystemInfo>` | mScriptSystems
40 | (8) `std::unique_ptr<ScriptApi::ScriptReport>` | mScriptReportQueue


### `ScriptApi::ScriptCallbackInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ScriptCallbackInterface


### `ScriptEngine::ScriptSet_t`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<std::string>::_Hashtable` | _M_h


### `ScriptEngine::ScriptQueue_t`
Offset | Type | Name
-|-|-|-
0 | (80) `std::deque<ScriptEngine::ScriptQueueData>` | c


### `ScriptLoggerConfig`
Offset | Type | Name
-|-|-|-
0 | (8) `EnumBitset<ScriptLogType,3>` | baseclass_0


### `ScriptServerContext`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (8) `Minecraft *` | mMinecraft
16 | (8) `PacketSender *` | mPacketSender
24 | (8) `entt::DefaultRegistry *` | mRegistry
32 | (8) `ScriptApi::ScriptReport *` | mScriptReport


### `ScriptTemplateFactory<ScriptServerContext>`
Offset | Type | Name
-|-|-|-
0 | (56) `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity>` | mEntities
56 | (56) `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity>` | mItemEntities
112 | (56) `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Component>` | mComponents
168 | (56) `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>` | mReceivedEvents
224 | (56) `ScriptTemplateFactory<ScriptServerContext>::HashedEntries` | mScriptEventDatas
280 | (16) `ScriptTemplateFactory<ScriptServerContext>::Entry<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>` | mBroadcastEvent


### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Entity>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned long,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::Entity>>` | mTemplates


### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::Component>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned long,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::Component>>` | mTemplates


### `ScriptTemplateFactory<ScriptServerContext>::Entries<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned long,std::shared_ptr<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>>` | mTemplates


### `ScriptTemplateFactory<ScriptServerContext>::HashedEntries`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<unsigned long>` | mHashes


### `ScriptTemplateFactory<ScriptServerContext>::Entry<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent,__gnu_cxx::_S_atomic>` | baseclass_0


### `ScriptOnlyComponents<ScriptServerContext>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,Json::Value>` | mScriptOnlyComponentDefs


### `ScriptOnlyEventsData<ScriptServerContext>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<std::string,Json::Value>` | mScriptOnlyEventsData


### `ScriptCommandCallbackQueue`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<unsigned int,ScriptCommandCallbackData>::_Hashtable` | _M_h


### `ScriptQueries`
Offset | Type | Name
-|-|-|-
0 | (112) `entt::DefaultRegistry` | mRegistryView


### `ServerInstanceEventListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ServerInstanceEventListener


### `Squid::spawnInkParticles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Squid::aiStep::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Squid::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Shulker::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Silverfish::spawnAnim::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SynchedActorData`
Offset | Type | Name
-|-|-|-
0 | (24) `SynchedActorData::DataList` | mItemsArray
24 | (2) `SynchedActorData::ID` | minIdxDirty
26 | (2) `SynchedActorData::ID` | maxIdxDirty


### `SimpleContainer`
Offset | Type | Name
-|-|-|-
0 | (244) `__int8[244]` | baseclass_0
244 | (4) `int` | mSize
248 | (24) `std::vector<ItemStack>` | mItems


### `SimpleBoolFilterTest`
Offset | Type | Name
-|-|-|-
0 | (12) `FilterTest:96` | baseclass_0
12 | (1) `bool` | mValue


### `SimpleFloatFilterTest`
Offset | Type | Name
-|-|-|-
0 | (12) `FilterTest:96` | baseclass_0
12 | (4) `float` | mValue


### `SimpleHashStringFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (40) `Util::HashString` | mValueString


### `SimpleIntFilterTest`
Offset | Type | Name
-|-|-|-
0 | (12) `FilterTest:96` | baseclass_0
12 | (4) `int` | mValue


### `SimpleTagIDFilterTest`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (16) `std::optional<IDType<TagIDType> >` | mCachedIDValue
32 | (40) `Util::HashString` | mValueString


### `SortItemInstanceIdAux`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SpawnData`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$SpawnData
8 | (4) `WeighedRandom::WeighedRandomItem` | baseclass_8
16 | (168) `ActorDefinitionIdentifier` | mActorId
184 | (8) `std::unique_ptr<CompoundTag>` | mTag


### `StackRefResultT<EntityRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `EntityRefTraits::StackResultStorage` | baseclass_0


### `SubChunkBlockStorage`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$SubChunkBlockStorage


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::findUsedIndices::$89D4AD7C0CE71E5C121270538A6F6D8C`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<2> *` | existing


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$242ED9D411BD064A57C4553B835CD0FE`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<2> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$633D66453D3F5664A26EE59CDFD22959`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<2> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::findUsedIndices::$D3A89A71AD77E1A6A761C588139D92F8`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<4> *` | existing


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$66FA6D0B33FF0D79D1FAEF5E715B6A50`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$5D469001403E80B2A426E4718973955B`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::findUsedIndices::$5D1D4294B57C53DD4C7D10D4AE89381A`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<8> *` | existing


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$C26F408D3D152A4098209C2CE9387EF2`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<8> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$09FE199C713A938B3B17002F6F47058A`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<8> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::findUsedIndices::$900FAD5FCE8D58777B797CA0B7FA2138`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<16> *` | existing


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$4917742FCBCB7D234EAD1B5E3DA1DE4E`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<16> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$28E5234A30BDDE39C7BEB7FA929ADF5A`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<16> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::findUsedIndices::$C463AA8D3B7416B6EACBAB570E768265`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<32> *` | existing


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$AAA3ED88E6F951360D315A860A822F3A`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<32> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$ED58595EF437FEAFABE4C940374EA69A`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<32> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::findUsedIndices::$2990B7D608F6D64D2C15233EADEB07CB`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<64> *` | existing


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$B5E2A92EF98D0403FD7DBC5576FA3DFE`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<64> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$704CDF7438A6CF9DB4A498AA560B0A22`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<64> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::findUsedIndices::$34AB7F28A08EB8CC59CD205CAB614B75`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<256> *` | existing


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$1AEE232A0E96F160F80275F43A812658`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<256> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$40981709DD800CB46A7EC240DF9DEAFC`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<256> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | height
4 | (4) `uint32_t` | radius
8 | (8) `const BlockPos *` | pos


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC`
Offset | Type | Name
-|-|-|-
0 | (8) `const BoundingBox *` | box


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::findUsedIndices::$6336BD0E2483FB0EFB3F76DC3EBC5309`
Offset | Type | Name
-|-|-|-
0 | (8) `std::bitset<4096> *` | existing


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:357:64)>::$6F135F9B09AF7761430A35C180173A8C`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4096> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::fetchBlocksInCylinder::$40F19BD02D6D15FED988956B86A67BFC *` | shapePredicate


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::_fetchBlocksInShape<(lambda at _Minecraftpe_handheld_src_common_world_level_chunk_SubChunkBlockStoragePaletted_h:371:67)>::$290B4DE2DB2BE431220A17F6F7E7C4F0`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::bitset<4096> *` | indices
8 | (8) `const BlockPos *` | positionOfChunk
16 | (8) `const BlockPos *` | pos
24 | (8) `uint16_t *` | index
32 | (8) `const buffer_span<const Block *> *` | palette
40 | (8) `std::vector<BlockFetchResult> *` | output
48 | (8) `const SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::fetchBlocksInBox::$C6B2610503636021CCB9EBE3476F26BC *` | shapePredicate


### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::_zeroIndicesGreaterEqualThan::$BF7C779BDE86076AE2754C92A6BC7645`
Offset | Type | Name
-|-|-|-
0 | (8) `uint16_t *` | max
8 | (8) `std::vector<unsigned short> *` | outOfBoundSlots
16 | (8) `size_t *` | idx


### `StructurePoolElement`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$StructurePoolElement
8 | (4) `std::once_flag` | mTemplateOnceFlag
16 | (40) `std::optional<StructurePoolElement::LazyTemplate>` | mTemplate
56 | (32) `std::string` | mLocation
88 | (8) `StructureManager *` | mManager
96 | (1) `bool` | mValid
100 | (4) `Projection` | mProjection
104 | (8) `const StructurePoolBlockRuleList *` | mBlockRules
112 | (8) `const StructurePoolBlockTagRuleList *` | mBlockTagRules
120 | (8) `const StructurePoolActorRuleList *` | mActorRules


### `SetScorePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ScorePacketType` | mType
40 | (24) `std::vector<ScorePacketInfo>` | mScoreInfo


### `SetScoreboardIdentityPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ScoreboardIdentityPacketType` | mType
40 | (24) `std::vector<ScoreboardIdentityPacketInfo>` | mIdentityInfo


### `SetDisplayObjectivePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mDisplaySlotName
72 | (32) `std::string` | mObjectiveName
104 | (32) `std::string` | mObjectiveDisplayName
136 | (32) `std::string` | mCriteriaName
168 | (1) `ObjectiveSortOrder` | mSortOrder


### `ServerScoreboard`
Offset | Type | Name
-|-|-|-
0 | (472) `Scoreboard` | baseclass_0
472 | (8) `std::unique_ptr<BasicTimer>` | mSaveTimer
480 | (8) `LevelStorage *` | mLevelStorage
488 | (1) `bool` | mIsDirty
496 | (32) `ServerScoreboard::ScoreChangedLevelCallback` | mScoreChangedLevelCallback
528 | (32) `ServerScoreboard::ScoreRemovedLevelCallback` | mScoreRemovedLevelCallback
560 | (32) `ServerScoreboard::SetDisplayObjectiveLevelCallback` | mSetDisplayObjectiveLevelCallback
592 | (32) `ServerScoreboard::ClearDisplayObjectiveLevelCallback` | mClearDisplayObjectiveLevelCallback
624 | (32) `ServerScoreboard::IdentityUpdatedLevelCallback` | mIdentityUpdatedLevelCallback
656 | (24) `std::vector<const Objective *>` | mTrackedObjectives
680 | (8) `PacketSender *` | mPacketSender
688 | (16) `ScoreboardId` | mLastUniqueSBID


### `Scoreboard`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Scoreboard
8 | (8) `CommandSoftEnumRegistry` | mRegistry
16 | (56) `std::unordered_map<std::string,DisplayObjective>` | mDisplayObjectives
72 | (224) `IdentityDictionary` | mIdentityDict
296 | (56) `std::unordered_map<ScoreboardId,ScoreboardIdentityRef>` | mIdentityRefs
352 | (1) `bool` | mShouldUpdateUI
360 | (56) `std::unordered_map<std::string,std::unique_ptr<Objective>>` | mObjectives
416 | (56) `std::unordered_map<std::string,std::unique_ptr<ObjectiveCriteria>>` | mCriteria


### `ScoreboardCommand::InitProxy`
Offset | Type | Name
-|-|-|-
0 | (8) `Scoreboard *` | mScoreboard


### `ScatterParams::_getPos::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ScatterParams::initMolangParams::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SpongeBlock::_spawnAbsorbParticles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `SnapshotEnv::DeleteFileEntry`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mFileName
32 | (1) `bool` | mWasRename


### `SPSCQueue<std::string,512>::Block`
```
struct SPSCQueue<std::string,512>::Block
{
  Lockless::WeakAtomic<unsigned long> front;
  size_t localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned long> tail;
  size_t localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *> next;
  char *data;
  const size_t sizeMask;
  char *rawThis;
};

```

### `SPSCQueue<std::string,512>`
```
struct SPSCQueue<std::string,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *> mTailBlock;
  size_t mLargestBlockSize;
};

```

### `ServerInstanceEventCoordinator`
```
struct __cppobj ServerInstanceEventCoordinator : EventCoordinator<ServerInstanceEventListener>
{
};

```

### `ServerContentKeyProvider`
```
struct __cppobj ServerContentKeyProvider : IContentAccessibilityProvider
{
};

```

### `SaveTransactionManager`
```
struct SaveTransactionManager
{
  SaveTransactionManager::ShowIconFunction mShowIconFunction;
};

```

### `ServerCommandOrigin`
```
struct __cppobj __attribute__((aligned(8))) ServerCommandOrigin : CommandOrigin
{
  ServerLevel *mServerLevel;
  std::string mRequestId;
  CommandPermissionLevel mCommandPermissionLevel;
};

```

### `ServerCommunicationInterface`
```
struct ServerCommunicationInterface
{
  std::unique_ptr<RakNet::TCPInterface> mTCPConnection;
  RakNet::SystemAddress mHostAddress;
};

```

### `ServerInstance`
```
struct __cppobj ServerInstance : AppPlatformListener, GameCallbacks
{
  const IMinecraftApp *mApp;
  Unique<Minecraft> mMinecraft;
  Unique<NetworkHandler> mNetwork;
  Unique<LoopbackPacketSender> mPacketSender;
  Unique<Timer> mSimTimer;
  Unique<Timer> mRealTimer;
  std::unique_ptr<Scheduler> mScheduler;
  std::unique_ptr<EducationOptions> mEducationOptions;
  LevelStorage *mStorage;
  RakNet::RakNetGUID mNetworkGUID;
  std::atomic_bool mInUpdate;
  std::atomic<int> mWriteRefCounter;
  std::atomic_bool mThreadShouldJoin;
  ServerInstanceEventCoordinator *mEventCoordinator;
  std::atomic<ServerInstance::InstanceState> mInstanceState;
  SPSCQueue<std::function<void ()>,512> mCommandQueue;
  Bedrock::Threading::Thread mServerInstanceThread;
  Bedrock::Threading::Mutex mResumeMutex;
  Bedrock::Threading::ConditionVariable mResumeSignal;
  std::unique_ptr<MinecraftServerScriptEngine> mScriptEngine;
  std::function<void ()> mLevelCorruptCallback;
  bool mHandledLevelCorruption;
  std::unique_ptr<TextFilteringProcessor> mTextFilteringProcessor;
  std::chrono::microseconds mWakeupInterval;
  std::chrono::_V2::steady_clock::time_point mLastPingTime;
  std::string mLevelId;
  std::unique_ptr<WorldSessionEndPoint> mWorldSessionEndPoint;
  std::shared_ptr<Core::FileStorageArea> mStorageAreaForLevel;
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
  ServerLevel::TagCache mTagCache;
};

```

### `ServiceLocator<AppPlatform>`
```
struct ServiceLocator<AppPlatform>
{
  __int8 gap0[1];
};

```

### `ServiceLocator<AppConfigs>`
```
struct ServiceLocator<AppConfigs>
{
  __int8 gap0[1];
};

```

### `ServiceLocator<ContentLog>`
```
struct ServiceLocator<ContentLog>
{
  __int8 gap0[1];
};

```

### `SubpackInfoCollection`
```
struct SubpackInfoCollection
{
  std::vector<SubpackInfo> mSubpackInfo;
};

```

### `ServerCommand`
```
struct __cppobj ServerCommand : Command
{
};

```

### `SnapshotFilenameAndLength`
```
struct SnapshotFilenameAndLength
{
  std::string filename;
  uint64_t filesize;
};

```

### `SaveCommand`
```
struct __cppobj __attribute__((aligned(8))) SaveCommand : ServerCommand
{
  SaveCommand::Mode mMode;
};

```

### `StopCommand`
```
struct __cppobj StopCommand : Command
{
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
  bool mUseWhitelist;
  Whitelist *mWhitelist;
  PermissionsFile *mPermissionsFile;
  Blacklist mServerBlacklist;
  bool mRequireTrustedAuthentication;
  bool mHasDisplayedPackErrors;
  NetworkIdentifier mMyId;
  const int mMaxChunkRadius;
  MinecraftCommands *mMinecraftCommands;
  IMinecraftApp *mApp;
  TextFilteringProcessor *mTextFilteringProcessor;
  ServerMetrics *mServerMetrics;
  std::unique_ptr<ClientBlobCache::Server::ActiveTransfersManager> mClientCacheManager;
  Unique<ClassroomModeNetworkHandler> mCompanionHandler;
  std::string mTenantId;
  std::string mShareableIdentityToken;
  Bedrock::Threading::Mutex mValidatePlayerMutex;
  bool mAllowIncoming;
  mce::UUID mHostPlayerId;
  std::string mServerName;
  std::string mServerType;
  std::string mMultiplayerCorrelationId;
  std::vector<std::string> mTrustedKeys;
  int mMaxNumPlayers;
  std::unordered_map<NetworkIdentifier,std::unique_ptr<ServerNetworkHandler::Client>> mClients;
  bool mIsTrial;
  std::unordered_map<PackIdVersion,std::string> mPackIdToContentKey;
};

```

### `ServerMetricsImpl::DataTransferred`
```
struct ServerMetricsImpl::DataTransferred
{
  uint64_t totalBytesReceived;
  uint64_t totalBytesSent;
};

```

### `SensingSystem`
```
struct __cppobj SensingSystem : ITickingSystem
{
};

```

### `ScaleByAgeSystem`
```
struct __cppobj ScaleByAgeSystem : ITickingSystem
{
};

```

### `SpawnActorSystem`
```
struct __cppobj SpawnActorSystem : ITickingSystem
{
};

```

### `ScaffoldingClimberSystem`
```
struct __cppobj ScaffoldingClimberSystem : ITickingSystem
{
};

```

### `SchedulerSystem`
```
struct __cppobj SchedulerSystem : ITickingSystem
{
};

```

### `StackResultStorageSharePtr<EntityRegistry>`
```
struct StackResultStorageSharePtr<EntityRegistry>
{
  std::shared_ptr<EntityRegistry> mValue;
};

```

### `StackResultStorageEntity`
```
struct StackResultStorageEntity
{
  std::optional<EntityContext> mContext;
};

```

### `SharedCounter<Item>`
```
struct SharedCounter<Item>
{
  Item *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BlockLegacy>`
```
struct SharedCounter<BlockLegacy>
{
  BlockLegacy *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ScatterFeature`
```
struct __cppobj __attribute__((aligned(8))) ScatterFeature : IFeature
{
  WeakRef<IFeature> mFeatureToScatter;
  ScatterParams mScatterParams;
  bool mProjectInputToFloor;
};

```

### `SingleBlockFeature`
```
struct __cppobj SingleBlockFeature : IFeature
{
  const Block *mBlock;
  bool mEnforcePlacementRules;
  bool mEnforceSurvivabilityRules;
  std::vector<const Block *> mMayPlaceOn;
  std::vector<const Block *> mMayReplace;
};

```

### `StructureTemplateFeature`
```
struct __cppobj StructureTemplateFeature : IFeature
{
  LegacyStructureTemplate *mStructure;
  StructureTemplateFeature::BoundingBox2D mPlacementRange;
  FacingID mFaceDirection;
  std::vector<std::unique_ptr<IStructureConstraint>> mConstraints;
};

```

### `SandFeature`
```
struct __cppobj __attribute__((aligned(8))) SandFeature : Feature
{
  const Block *mBlock;
  int mRadius;
};

```

### `SpringFeature`
```
struct __cppobj SpringFeature : Feature
{
  const Block *mBlock;
};

```

### `SpruceFeature`
```
struct __cppobj __attribute__((aligned(8))) SpruceFeature : TreeFeature
{
};

```

### `SwampTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) SwampTreeFeature : TreeFeature
{
};

```

### `SavannaTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) SavannaTreeFeature : TreeFeature
{
};

```

### `SeaAnemoneFeature`
```
struct __cppobj SeaAnemoneFeature : Feature
{
};

```

### `SeagrassFeature`
```
struct __cppobj SeagrassFeature : Feature
{
};

```

### `SeaPickleFeature`
```
struct __cppobj SeaPickleFeature : Feature
{
};

```

### `StackResultStorageFeature`
```
struct StackResultStorageFeature
{
  std::optional<std::reference_wrapper<FeatureRegistry> > mRegistry;
  size_t mIndex;
};

```

### `StackRefResultT<FeatureRefTraits>::StackRef`
```
typedef FeatureRefTraits::StackRef StackRefResultT<FeatureRefTraits>::StackRef;

```

### `StructurePiece`
```
struct StructurePiece
{
  int (**_vptr$StructurePiece)(void);
  BoundingBox mBoundingBox;
  int mOrientation;
  int mGenDepth;
};

```

### `StrongholdPiece`
```
struct __cppobj __attribute__((aligned(8))) StrongholdPiece : StructurePiece
{
  StrongholdPiece::SmallDoorType entryDoor;
};

```

### `SHFillerCorridor`
```
struct __cppobj SHFillerCorridor : StrongholdPiece:352
{
  int steps;
};

```

### `StrongholdPiece:352`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) StrongholdPiece:352 : StructurePiece
{
  StrongholdPiece::SmallDoorType entryDoor;
};

```

### `SHStairsDown`
```
struct __cppobj __attribute__((aligned(4))) SHStairsDown : StrongholdPiece:352
{
  bool isSource;
};

```

### `SHChestCorridor`
```
struct __cppobj __attribute__((aligned(4))) SHChestCorridor : StrongholdPiece:352
{
  bool hasPlacedChest;
};

```

### `SHFiveCrossing`
```
struct __cppobj SHFiveCrossing : StrongholdPiece:352
{
  bool leftHigh;
  bool leftLow;
  bool rightHigh;
  bool rightLow;
};

```

### `SHLeftTurn`
```
struct __cppobj __attribute__((aligned(8))) SHLeftTurn : StrongholdPiece
{
};

```

### `SHRightTurn`
```
struct __cppobj __attribute__((aligned(8))) SHRightTurn : StrongholdPiece
{
};

```

### `SHLibrary`
```
struct __cppobj __attribute__((aligned(4))) SHLibrary : StrongholdPiece:352
{
  bool isTall;
};

```

### `SHPortalRoom`
```
struct __cppobj __attribute__((aligned(4))) SHPortalRoom : StrongholdPiece:352
{
  bool hasPlacedMobSpawner;
};

```

### `SHPrisonHall`
```
struct __cppobj __attribute__((aligned(8))) SHPrisonHall : StrongholdPiece
{
};

```

### `SHRoomCrossing`
```
struct __cppobj SHRoomCrossing : StrongholdPiece:352
{
  int type;
};

```

### `SHStraight`
```
struct __cppobj __attribute__((aligned(4))) SHStraight : StrongholdPiece:352
{
  bool leftChild;
  bool rightChild;
};

```

### `SHStraightStairsDown`
```
struct __cppobj __attribute__((aligned(8))) SHStraightStairsDown : StrongholdPiece
{
};

```

### `SHStartPiece`
```
struct __cppobj SHStartPiece : SHStairsDown
{
  ReferencedPieceList pendingChildren;
  SHPortalRoom *portalRoom;
  std::string imposedPiece;
  std::string previousPiece;
  PieceWeightList pieceWeights;
};

```

### `StructureTemplatePool`
```
struct StructureTemplatePool
{
  std::string mName;
  std::vector<const StructurePoolElement *> mTemplates;
  std::string mFallback;
};

```

### `StructurePoolBlockRuleList`
```
typedef std::vector<std::unique_ptr<StructurePoolBlockRule>> StructurePoolBlockRuleList;

```

### `StructurePoolBlockTagRuleList`
```
typedef std::vector<std::unique_ptr<StructurePoolBlockTagRule>> StructurePoolBlockTagRuleList;

```

### `StructurePoolActorRuleList`
```
typedef std::vector<std::unique_ptr<StructurePoolActorRule>> StructurePoolActorRuleList;

```

### `SubChunkBrightnessStorage`
```
struct SubChunkBrightnessStorage
{
  std::array<SubChunkBrightnessStorage::LightPair,4096> mLight;
};

```

### `SubChunkLightUpdate`
```
struct __attribute__((aligned(4))) SubChunkLightUpdate
{
  SubChunkBlockPos mPos;
  Brightness mOldBrightness;
  Brightness mNewBrightness;
  Brightness mOldAbsorption;
  Brightness mNewAbsorption;
  bool mIsSkyLight;
};

```

### `Seasons`
```
struct Seasons
{
  Dimension *mDimension;
  PerlinSimplexNoise mSnowNoise;
};

```

### `SimplexNoise`
```
struct SimplexNoise
{
  Vec3 mOrigin;
  int mNoiseMap[512];
};

```

### `SmallSet<std::unique_ptr<Actor> >`
```
struct SmallSet<std::unique_ptr<Actor> >
{
  std::vector<std::unique_ptr<Actor>> c;
};

```

### `SmallSet<std::unique_ptr<Actor> >::const_iterator`
```
typedef std::vector<std::unique_ptr<Actor>>::const_iterator SmallSet<std::unique_ptr<Actor> >::const_iterator;

```

### `SmallSet<std::unique_ptr<Actor> >::iterator`
```
typedef std::vector<std::unique_ptr<Actor>>::iterator SmallSet<std::unique_ptr<Actor> >::iterator;

```

### `ScreenshotOptions`
```
struct ScreenshotOptions
{
  bool mCropToRatio;
  int mWidthRatio;
  int mHeightRatio;
  uint32_t mMaxWidth;
  uint32_t mMaxHeight;
  bool mRestrictScreenshotSize;
  bool mApplySquareFrame;
  Core::HeapPathBuffer mRequestedFileName;
  Core::HeapPathBuffer mRequestedFilePath;
  Core::HeapPathBuffer mRequestedExtension;
  bool mReplaceImage;
  bool mUseScreenshotsFolder;
  bool mHideUI;
  bool mLogRequest;
  bool mWriteScreenshotToFile;
  bool mIsSavegameScreenshot;
  Core::HeapPathBuffer mOutFileName;
  Core::HeapPathBuffer mOutFileDir;
  Core::HeapPathBuffer mOutExtension;
};

```

### `StructurePoolActorRule`
```
struct StructurePoolActorRule
{
  const Unique<IStructurePoolActorPredicate> mSourcePredicate;
  const std::string mResultActor;
};

```

### `StructurePoolActorPredicateActorMatch`
```
struct __cppobj StructurePoolActorPredicateActorMatch : IStructurePoolActorPredicate
{
  const std::string mActor;
};

```

### `StructurePoolBlockRule`
```
struct StructurePoolBlockRule
{
  const Unique<IStructurePoolBlockPredicate> mSourcePredicate;
  const Unique<IStructurePoolBlockPredicate> mTargetPredicate;
  const Block *mResultBlock;
};

```

### `StructurePoolBlockPredicateBlockMatchRandom`
```
struct __cppobj __attribute__((aligned(8))) StructurePoolBlockPredicateBlockMatchRandom : IStructurePoolBlockPredicate
{
  const Block *mBlock;
  const float mProbability;
};

```

### `StructurePoolBlockPredicateAlwaysTrue`
```
struct __cppobj StructurePoolBlockPredicateAlwaysTrue : IStructurePoolBlockPredicate
{
};

```

### `StructurePoolBlockPredicateBlockMatch`
```
struct __cppobj StructurePoolBlockPredicateBlockMatch : IStructurePoolBlockPredicate
{
  const Block *mBlock;
};

```

### `StructurePoolBlockTagRule`
```
struct StructurePoolBlockTagRule
{
  const Unique<IStructurePoolBlockTagPredicate> mSourcePredicate;
  const std::string mResultKey;
  const std::string mResultValue;
};

```

### `StructurePoolBlockTagPredicateBlockTagStringMatches`
```
struct __cppobj StructurePoolBlockTagPredicateBlockTagStringMatches : IStructurePoolBlockTagPredicate
{
  const Block *mBlock;
  const std::string mTagKey;
  const std::string mTagValue;
};

```

### `StructureFeature`
```
struct __attribute__((aligned(8))) StructureFeature
{
  int (**_vptr$StructureFeature)(void);
  StructureFeature::StructureMap cachedStructures;
  SharedMutex cacheMutex;
  std::unordered_set<ChunkPos> visitedPositions;
  SpinLock visitedPositionsMutex;
  uint32_t mRadius;
  int mXScale;
  int mZScale;
};

```

### `StructureFeature::StructureMap`
```
typedef std::unordered_map<ChunkPos,std::unique_ptr<StructureStart>> StructureFeature::StructureMap;

```

### `StructureStart`
```
struct StructureStart
{
  int (**_vptr$StructureStart)(void);
  BoundingBox boundingBox;
  int chunkX;
  int chunkZ;
  PieceList pieces;
};

```

### `StrongholdFeature`
```
struct __cppobj StrongholdFeature : StructureFeature:1760
{
  bool isSpotSelected;
  ChunkPos selectedChunks[3];
  VillageFeature *villages;
  Bedrock::Threading::Mutex positionMutex;
  const int TOTAL_VILLAGE_STRONGHOLDS;
  const int GRID_SIZE;
  const int GRID_INSET;
  const int MIN_STRONGHOLD_DISTANCE;
  const float STRONGHOLD_CHANCE;
  const int MAX_GRID_SEARCH_DISTANCE;
};

```

### `ShipwreckFeature`
```
struct __cppobj ShipwreckFeature : StructureFeature:1760
{
  int mSpacing;
  int mMinSeparation;
  OceanMonumentFeature *mMonument;
  std::vector<int> mAllowedBiomes;
};

```

### `StructureFeature:1760`
```
struct __attribute__((packed)) __attribute__((aligned(4))) StructureFeature:1760
{
  int (**_vptr$StructureFeature)(void);
  StructureFeature::StructureMap cachedStructures;
  SharedMutex cacheMutex;
  std::unordered_set<ChunkPos> visitedPositions;
  SpinLock visitedPositionsMutex;
  uint32_t mRadius;
  int mXScale;
  int mZScale;
};

```

### `ShipwreckStart`
```
struct __cppobj ShipwreckStart : StructureStart
{
};

```

### `ShipwreckPiece`
```
struct __cppobj ShipwreckPiece : StructurePiece
{
};

```

### `StrongholdStart`
```
struct __cppobj __attribute__((aligned(8))) StrongholdStart : StructureStart
{
  bool valid;
};

```

### `StairBlock`
```
struct __cppobj StairBlock : BlockLegacy
{
  const BlockLegacy *mBase;
};

```

### `Social::Events::EventManager`
```
struct __attribute__((aligned(4))) Social::Events::EventManager
{
  std::vector<std::unique_ptr<Social::Events::IEventListener>> mEventListeners;
  PropertyList mGlobalProperties;
  PropertyList mCommonProperties;
  PropertyListMap mPlayerCommonProperties;
  PropertyListMap mPlayerGlobalProperties;
  SharedMutex mGlobalPropertiesMutex;
  SharedMutex mCommonPropertiesMutex;
  SharedMutex mPlayerCommonPropertiesMutex;
  SharedMutex mPlayerGlobalPropertiesMutex;
  Bedrock::Threading::Mutex mListenersMutex;
  uint32_t mGlobalSeqNum;
  bool mAcceptNewEvents;
};

```

### `Social::UserPicturePath`
```
struct Social::UserPicturePath
{
  std::shared_ptr<ResourceLocation> mLocation;
};

```

### `StructureEditorData`
```
struct StructureEditorData
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

### `StructureSettings`
```
struct __attribute__((aligned(8))) StructureSettings
{
  std::string mPaletteName;
  bool mIgnoreEntities;
  bool mIgnoreBlocks;
  BlockPos mStructureSize;
  BlockPos mStructureOffset;
  Vec3 mPivot;
  ActorUniqueID mLastTouchedByPlayer;
  Rotation_0 mRotation;
  Mirror_0 mMirror;
  float mIntegrityValue;
  RandomSeed mIntegritySeed;
};

```

### `StructureTelemetryClientData`
```
struct StructureTelemetryClientData
{
  uint32_t mSizeEditCount;
  uint32_t mOffsetEditCount;
  uint32_t mRotationEditCount;
  uint32_t mMirrorEditCount;
};

```

### `ServiceLocator<IMinecraftEventing>`
```
struct ServiceLocator<IMinecraftEventing>
{
  __int8 gap0[1];
};

```

### `StateVectorComponent`
```
struct StateVectorComponent
{
  Vec3 mPos;
  Vec3 mPosPrev;
  Vec3 mPosDelta;
};

```

### `SynchedActorData::TypeVec3`
```
typedef Vec3 SynchedActorData::TypeVec3;

```

### `SynchedActorData::TypeString`
```
typedef std::string SynchedActorData::TypeString;

```

### `SchedulerDefinition`
```
struct SchedulerDefinition
{
  std::vector<DefinitionTrigger> mTriggerDefs;
  unsigned int mMinDelayTicks;
  unsigned int mMaxDelayTicks;
};

```

### `SpawnActorEntry`
```
struct __attribute__((aligned(4))) SpawnActorEntry
{
  SpawnActorParameters mParams;
  int mSpawnTimer;
  bool mStopSpawning;
};

```

### `ShortTag`
```
struct __cppobj __attribute__((aligned(8))) ShortTag : Tag
{
  __int16 data;
};

```

### `StringTag`
```
struct __cppobj StringTag : Tag
{
  std::string data;
};

```

### `serialize<CompoundTag>`
```
struct serialize<CompoundTag>
{
  __int8 gap0[1];
};

```

### `ServerLocator`
```
struct ServerLocator
{
  int (**_vptr$ServerLocator)(void);
};

```

### `ServiceLocator<NetworkDebugManager>`
```
struct ServiceLocator<NetworkDebugManager>
{
  __int8 gap0[1];
};

```

### `SetDefaultGameTypePacket`
```
struct __cppobj SetDefaultGameTypePacket : Packet:288
{
  GameType mDefaultGameType;
};

```

### `StructureBlockUpdatePacket`
```
struct __cppobj __attribute__((aligned(8))) StructureBlockUpdatePacket : Packet:288
{
  NetworkBlockPosition mBlockPos;
  StructureEditorData_0 mData;
  bool mTrigger;
};

```

### `StructureTemplateDataRequestPacket`
```
struct __cppobj __attribute__((aligned(8))) StructureTemplateDataRequestPacket : Packet
{
  std::string mStructureName;
  NetworkBlockPosition mStructureBlockPos;
  StructureSettings_0 mStructureSettings;
  StructureTemplateRequestOperation mRequestOperation;
};

```

### `ShowStoreOfferPacket`
```
struct __cppobj __attribute__((aligned(8))) ShowStoreOfferPacket : Packet
{
  std::string mOfferId;
  std::string mContentType;
  bool mShowAll;
};

```

### `SubClientLoginPacket`
```
struct __cppobj SubClientLoginPacket : Packet
{
  Unique<SubClientConnectionRequest> mConnectionRequest;
};

```

### `ServerSettingsRequestPacket`
```
struct __cppobj ServerSettingsRequestPacket : Packet
{
};

```

### `ServerSettingsResponsePacket`
```
struct __cppobj ServerSettingsResponsePacket : Packet:288
{
  uint32_t mFormId;
  std::string mFormJSON;
};

```

### `ShowProfilePacket`
```
struct __cppobj ShowProfilePacket : Packet
{
  std::string mPlayerXUID;
};

```

### `SetLocalPlayerAsInitializedPacket`
```
struct __cppobj SetLocalPlayerAsInitializedPacket : Packet
{
  ActorRuntimeID mPlayerID;
};

```

### `SettingsCommandPacket`
```
struct __cppobj __attribute__((aligned(8))) SettingsCommandPacket : Packet
{
  std::string mCommandString;
  bool mSupressOutput;
};

```

### `ServerNetworkHandler::Client`
```
struct ServerNetworkHandler::Client
{
  std::unique_ptr<ConnectionRequest> mPrimaryRequest;
  std::unordered_map<unsigned char,std::unique_ptr<SubClientConnectionRequest>> mSubClientRequests;
};

```

### `SerializedPersonaPieceHandle`
```
struct SerializedPersonaPieceHandle
{
  std::string mPieceId;
  persona::PieceType mPieceType;
  mce::UUID mPackId;
  bool mIsDefaultPiece;
  std::string mProductId;
};

```

### `Social::XboxLiveUserObserver`
```
struct __cppobj Social::XboxLiveUserObserver : Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
};

```

### `Social::MultiplayerServiceObserver`
```
struct __cppobj Social::MultiplayerServiceObserver : Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
};

```

### `ServerPlayer`
```
struct __cppobj ServerPlayer : Player
{
  NetworkHandler *mNetworkHandler;
  ServerPlayer::OnPlayerLoadedCallback mOnPlayerLoadedCallback;
  NetworkChunkPublisher mChunkPublisherView;
  InventoryMenu mInventoryMenu;
  ContainerID mContainerCounter;
  uint32_t mMaxChunkRadius;
  bool mLoading;
  bool mIsTeacher;
  bool mTeleportedThisTick;
  bool mLocalPlayerInitialized;
  Tick mPrevShieldBlockingTick;
  std::unique_ptr<CompoundTag> mLostDataTag;
  uint32_t mClientViewRadius;
  uint32_t mClientRequestedRadius;
  int mRemainingStructureRefreshTicks;
  StructureFeatureType mCurrentStructureFeature;
  std::chrono::_V2::steady_clock::time_point mLastKnownSyncTime;
  std::chrono::_V2::steady_clock::time_point mLastKnownDesyncTime;
  float mCheatingStrikeScore;
  std::unordered_map<ActorUniqueID,ServerPlayer::NearbyActor> mNearbyActors;
  Unique<ServerMoveInputHandler> mMoveInputHandler;
  InputMode mCurrentInputMode;
  ClientPlayMode mPlayMode;
  PlayerMovementTelemetryData mMovementData;
};

```

### `StackRefResult<EntityId>`
```
typedef StackRefResultT<EntityRefTraits> StackRefResult<EntityId>;

```

### `StackRefResultT<EntityRefTraits>::StackRef`
```
typedef EntityRefTraits::StackRef StackRefResultT<EntityRefTraits>::StackRef;

```

### `ServiceLocator<FeatureToggles>`
```
struct ServiceLocator<FeatureToggles>
{
  __int8 gap0[1];
};

```

### `StructureBlockActor`
```
struct __cppobj __attribute__((aligned(8))) StructureBlockActor : BlockActor
{
  StructureEditorData_1 mStructureEditorData;
  StructureTelemetryServerData mTelemetryServerData;
  bool mIsPowered;
};

```

### `StructureTelemetryServerData`
```
struct StructureTelemetryServerData
{
  bool mHasBeenActivatedByRedstone;
  bool mHasLoadedIntoUnloadedChunks;
  BlockPos mLastOffsetWhenLoadingIntoUnloadedChunks;
};

```

### `SpatialActorNetworkData`
```
struct SpatialActorNetworkData
{
  Actor *mEntity;
  bool mHasInitializedLastSent;
  bool mAutoSend;
  MoveActorAbsoluteData mLastSentMoveData;
  MoveActorAbsoluteData mLastReceivedMoveData;
};

```

### `serialize<ActorRuntimeID>`
```
struct serialize<ActorRuntimeID>
{
  __int8 gap0[1];
};

```

### `serialize<ActorUniqueID>`
```
struct serialize<ActorUniqueID>
{
  __int8 gap0[1];
};

```

### `serialize<Vec3>`
```
struct serialize<Vec3>
{
  __int8 gap0[1];
};

```

### `serialize<Vec2>`
```
struct serialize<Vec2>
{
  __int8 gap0[1];
};

```

### `serialize<std::vector<std::unique_ptr<DataItem>> >`
```
struct serialize<std::vector<std::unique_ptr<DataItem>> >
{
  __int8 gap0[1];
};

```

### `serialize<ActorLink>`
```
struct serialize<ActorLink>
{
  __int8 gap0[1];
};

```

### `serialize<mce::UUID>`
```
struct serialize<mce::UUID>
{
  __int8 gap0[1];
};

```

### `serialize<NetworkBlockPosition>`
```
struct serialize<NetworkBlockPosition>
{
  __int8 gap0[1];
};

```

### `serialize<BlockPos>`
```
struct serialize<BlockPos>
{
  __int8 gap0[1];
};

```

### `serialize<MapItemTrackedActor::UniqueId>`
```
struct serialize<MapItemTrackedActor::UniqueId>
{
  __int8 gap0[1];
};

```

### `serialize<MapDecoration>`
```
struct serialize<MapDecoration>
{
  __int8 gap0[1];
};

```

### `serialize<CommandOriginData>`
```
struct serialize<CommandOriginData>
{
  __int8 gap0[1];
};

```

### `ShapedRecipe`
```
struct __cppobj ShapedRecipe : Recipe
{
  Recipe::Ingredients mIngredients;
  Recipe::ResultList mResults;
};

```

### `ShapelessRecipe`
```
struct __cppobj ShapelessRecipe : Recipe
{
  const Recipe::Ingredients mIngredients;
  const Recipe::ResultList mResult;
};

```

### `ShulkerBoxRecipe`
```
struct __cppobj ShulkerBoxRecipe : ShapelessRecipe
{
  Recipe::ResultList mResults;
};

```

### `ShapelessChemistryRecipe`
```
struct __cppobj ShapelessChemistryRecipe : ShapelessRecipe
{
};

```

### `ShapedChemistryRecipe`
```
struct __cppobj ShapedChemistryRecipe : ShapedRecipe
{
};

```

### `serialize<ShapedRecipe>`
```
struct serialize<ShapedRecipe>
{
  __int8 gap0[1];
};

```

### `serialize<ShapelessRecipe>`
```
struct serialize<ShapelessRecipe>
{
  __int8 gap0[1];
};

```

### `serialize<ShulkerBoxRecipe>`
```
struct serialize<ShulkerBoxRecipe>
{
  __int8 gap0[1];
};

```

### `serialize<ShapelessChemistryRecipe>`
```
struct serialize<ShapelessChemistryRecipe>
{
  __int8 gap0[1];
};

```

### `serialize<ShapedChemistryRecipe>`
```
struct serialize<ShapedChemistryRecipe>
{
  __int8 gap0[1];
};

```

### `serialize<EducationLevelSettings>`
```
struct serialize<EducationLevelSettings>
{
  __int8 gap0[1];
};

```

### `serialize<EntityNetId>`
```
struct serialize<EntityNetId>
{
  __int8 gap0[1];
};

```

### `serialize<GameRulesChangedPacketData>`
```
struct serialize<GameRulesChangedPacketData>
{
  __int8 gap0[1];
};

```

### `serialize<InventoryTransaction>`
```
struct serialize<InventoryTransaction>
{
  __int8 gap0[1];
};

```

### `serialize<InventoryAction>`
```
struct serialize<InventoryAction>
{
  __int8 gap0[1];
};

```

### `serialize<InventorySource>`
```
struct serialize<InventorySource>
{
  __int8 gap0[1];
};

```

### `serialize<ChunkPos>`
```
struct serialize<ChunkPos>
{
  __int8 gap0[1];
};

```

### `serialize<MoveActorAbsoluteData>`
```
struct serialize<MoveActorAbsoluteData>
{
  __int8 gap0[1];
};

```

### `serialize<MoveActorDeltaData>`
```
struct serialize<MoveActorDeltaData>
{
  __int8 gap0[1];
};

```

### `serialize<BaseGameVersion>`
```
struct serialize<BaseGameVersion>
{
  __int8 gap0[1];
};

```

### `serialize<ScoreboardId>`
```
struct serialize<ScoreboardId>
{
  __int8 gap0[1];
};

```

### `serialize<IdentityDefinition::Type>`
```
struct serialize<IdentityDefinition::Type>
{
  __int8 gap0[1];
};

```

### `serialize<LevelSettings>`
```
struct serialize<LevelSettings>
{
  __int8 gap0[1];
};

```

### `serialize<ItemData>`
```
struct serialize<ItemData>
{
  __int8 gap0[1];
};

```

### `serialize<StructureEditorData>`
```
struct serialize<StructureEditorData>
{
  __int8 gap0[1];
};

```

### `serialize<StructureSettings>`
```
struct serialize<StructureSettings>
{
  __int8 gap0[1];
};

```

### `serialize<ItemStack>`
```
struct serialize<ItemStack>
{
  __int8 gap0[1];
};

```

### `serialize<ItemInstance>`
```
struct serialize<ItemInstance>
{
  __int8 gap0[1];
};

```

### `ServiceLocator<EducationOptions>`
```
struct ServiceLocator<EducationOptions>
{
  __int8 gap0[1];
};

```

### `StringOption`
```
struct __cppobj StringOption : Option
{
  std::string mValue;
  std::string mDefaultValue;
  Option::StringFilter mCoerceValueCallback;
};

```

### `SPSCQueue<std::shared_ptr<BackgroundTask>,512>`
```
struct SPSCQueue<std::shared_ptr<BackgroundTask>,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *> mTailBlock;
  size_t mLargestBlockSize;
};

```

### `SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block`
```
struct SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block
{
  Lockless::WeakAtomic<unsigned long> front;
  size_t localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned long> tail;
  size_t localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *> next;
  char *data;
  const size_t sizeMask;
  char *rawThis;
};

```

### `ServiceLocator<PackManifest::CapabilityRegistry>`
```
struct ServiceLocator<PackManifest::CapabilityRegistry>
{
  __int8 gap0[1];
};

```

### `SPSCQueue<std::function<void ()>,512>`
```
struct SPSCQueue<std::function<void ()>,512>
{
  Lockless::WeakAtomic<SPSCQueue<std::function<void ()>,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<std::function<void ()>,512>::Block *> mTailBlock;
  size_t mLargestBlockSize;
};

```

### `SPSCQueue<std::function<void ()>,512>::Block`
```
struct SPSCQueue<std::function<void ()>,512>::Block
{
  Lockless::WeakAtomic<unsigned long> front;
  size_t localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned long> tail;
  size_t localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<std::function<void ()>,512>::Block *> next;
  char *data;
  const size_t sizeMask;
  char *rawThis;
};

```

### `ServiceLocator<ServerInstance>`
```
struct ServiceLocator<ServerInstance>
{
  __int8 gap0[1];
};

```

### `ServerLevel::TagCache`
```
typedef std::unordered_map<StringKey,unsigned int> ServerLevel::TagCache;

```

### `Shared<ActorInfoRegistry>`
```
typedef std::shared_ptr<ActorInfoRegistry> Shared<ActorInfoRegistry>;

```

### `SavedDataStorage`
```
struct SavedDataStorage
{
  int (**_vptr$SavedDataStorage)(void);
  LevelStorage *levelStorage;
  std::unordered_map<std::string,SavedData *> savedDatas;
};

```

### `SpawnGroupRegistry`
```
struct __cppobj SpawnGroupRegistry : ActorSpawnRuleBase
{
  SpawnGroupRegistry::SpawnGroupRegistryMap mSpawnGroupRegistry;
  SpawnGroupRegistry::SpawnGroupLookupMap mSpawnGroupLookupMap;
};

```

### `Spawner`
```
struct __attribute__((aligned(8))) Spawner
{
  Level *mLevel;
  int mBaseTypeCount[2][7];
  std::unordered_map<StringKey,int> mEntityTypeCount[2];
  int mTotalEntityCount;
};

```

### `SmallSet<Actor *>`
```
struct SmallSet<Actor *>
{
  std::vector<Actor *> c;
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

### `SurfaceBuilderRegistry`
```
struct SurfaceBuilderRegistry
{
  std::vector<SurfaceBuilderRegistry::Element> mSurfaceBuilders;
};

```

### `SurfaceBuilderRegistry::Element`
```
struct SurfaceBuilderRegistry::Element
{
  std::unique_ptr<ISurfaceBuilder> mBuilder;
  SurfaceBuilderRegistry::ScoringFunc mScoringFunc;
};

```

### `ServerMoveInputHandler`
```
struct __cppobj __attribute__((aligned(8))) ServerMoveInputHandler : MoveInputHandler
{
};

```

### `SkinAdjustments`
```
struct SkinAdjustments
{
  unsigned int mAnimOverrideBitmask;
};

```

### `ScaleDescription`
```
struct __cppobj __attribute__((aligned(8))) ScaleDescription : PropertyDescription
{
  float mValue;
};

```

### `SoundVolumeDescription`
```
struct __cppobj __attribute__((aligned(8))) SoundVolumeDescription : PropertyDescription
{
  float mValue;
};

```

### `SittableDescription`
```
struct __cppobj SittableDescription : ComponentDescription
{
  DefinitionTrigger mOnSit;
  DefinitionTrigger mOnStand;
};

```

### `SkinIDDescription`
```
struct __cppobj __attribute__((aligned(8))) SkinIDDescription : PropertyDescription
{
  int mSkinIDChoice;
};

```

### `SlimeMoveControlDescription`
```
struct __cppobj __attribute__((aligned(8))) SlimeMoveControlDescription : MoveControlDescription:96
{
  FloatRange mJumpDelayTicks;
};

```

### `StrengthDescription`
```
struct __cppobj __attribute__((aligned(8))) StrengthDescription : AttributeDescription
{
  bool mHasComponent;
  int mStrength;
  int mMaxStrength;
};

```

### `ServerPlayer::NearbyActor`
```
struct ServerPlayer::NearbyActor
{
  bool isAutonomous;
  ServerPlayer::NearbyActor::State state;
  Actor *tempActor;
};

```

### `SmokerContainerManagerModel`
```
struct __cppobj SmokerContainerManagerModel : FurnaceContainerManagerModel
{
};

```

### `ScriptApi::ScriptReportItem`
```
struct ScriptApi::ScriptReportItem
{
  std::string mMessage;
  ScriptApi::ScriptReportItemType mType;
  std::unique_ptr<ScriptApi::JavaScriptErrorHandler> mErrorHandler;
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Entity`
```
struct ScriptTemplateFactory<ScriptServerContext>::Entity
{
  int (**_vptr$Entity)(void);
};

```

### `ScriptTemplateFactory<ScriptServerContext>::Component`
```
struct ScriptTemplateFactory<ScriptServerContext>::Component
{
  int (**_vptr$Component)(void);
};

```

### `ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent`
```
struct ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent
{
  int (**_vptr$ReceivedEvent)(void);
};

```

### `ScriptBinderTemplate`
```
struct ScriptBinderTemplate
{
  int (**_vptr$ScriptBinderTemplate)(void);
};

```

### `ScriptBinderComponent`
```
struct ScriptBinderComponent
{
  int (**_vptr$ScriptBinderComponent)(void);
};

```

### `ScriptObjectBinder`
```
struct ScriptObjectBinder
{
  const std::string mTypeIdentifier;
  unsigned int mComponentsInUse;
  std::vector<std::unique_ptr<ScriptBinderComponent>> mComponents;
};

```

### `ScriptServerActorEventListener`
```
struct __cppobj ScriptServerActorEventListener : ActorEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerBlockEventListener`
```
struct __cppobj ScriptServerBlockEventListener : BlockEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptServerPacketEventListener`
```
struct __cppobj ScriptServerPacketEventListener : NetworkPacketEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptTelemetryEventListener`
```
struct __cppobj __attribute__((aligned(8))) ScriptTelemetryEventListener : ScriptEventListener
{
  IMinecraftEventing *mEventing;
  const bool mClientside;
};

```

### `ScriptServerLevelEventListener`
```
struct __cppobj ScriptServerLevelEventListener : LevelEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptLevelWeatherEventListener`
```
struct __cppobj ScriptLevelWeatherEventListener : LevelEventListener
{
  MinecraftServerScriptEngine *mScriptEngine;
};

```

### `ScriptArmorContainerComponent`
```
struct __cppobj ScriptArmorContainerComponent : ScriptContainerComponentBase
{
};

```

### `ScriptAttackComponent`
```
struct __cppobj ScriptAttackComponent : ScriptServerComponent
{
};

```

### `ScriptBlockContainerComponent`
```
struct __cppobj ScriptBlockContainerComponent : ScriptContainerComponentBase
{
};

```

### `ScriptBlockStateComponent`
```
struct __cppobj ScriptBlockStateComponent : ScriptServerComponent
{
};

```

### `ScriptCollisionBoxComponent`
```
struct __cppobj ScriptCollisionBoxComponent : ScriptServerComponent
{
};

```

### `ScriptDamageSensorComponent`
```
struct __cppobj ScriptDamageSensorComponent : ScriptServerComponent
{
};

```

### `ScriptEquipmentComponent`
```
struct __cppobj ScriptEquipmentComponent : ScriptServerComponent
{
};

```

### `ScriptEquippableComponent`
```
struct __cppobj ScriptEquippableComponent : ScriptServerComponent
{
};

```

### `ScriptExplodeComponent`
```
struct __cppobj ScriptExplodeComponent : ScriptServerComponent
{
};

```

### `ScriptHandContainerComponent`
```
struct __cppobj ScriptHandContainerComponent : ScriptContainerComponentBase
{
};

```

### `ScriptHealableComponent`
```
struct __cppobj ScriptHealableComponent : ScriptServerComponent
{
};

```

### `ScriptHealthComponent`
```
struct __cppobj ScriptHealthComponent : ScriptServerComponent
{
};

```

### `ScriptHotbarContainerComponent`
```
struct __cppobj ScriptHotbarContainerComponent : ScriptContainerComponentBase
{
};

```

### `ScriptInteractComponent`
```
struct __cppobj ScriptInteractComponent : ScriptServerComponent
{
};

```

### `ScriptInventoryComponent`
```
struct __cppobj ScriptInventoryComponent : ScriptServerComponent
{
};

```

### `ScriptInventoryContainerComponent`
```
struct __cppobj ScriptInventoryContainerComponent : ScriptContainerComponentBase
{
};

```

### `ScriptLookAtComponent`
```
struct __cppobj ScriptLookAtComponent : ScriptServerComponent
{
};

```

### `ScriptNameableComponent`
```
struct __cppobj ScriptNameableComponent : ScriptServerComponent
{
};

```

### `ScriptPositionComponent`
```
struct __cppobj ScriptPositionComponent : ScriptServerComponent
{
};

```

### `ScriptRotationComponent`
```
struct __cppobj ScriptRotationComponent : ScriptServerComponent
{
};

```

### `ScriptShooterComponent`
```
struct __cppobj ScriptShooterComponent : ScriptServerComponent
{
};

```

### `ScriptSpawnActorComponent`
```
struct __cppobj ScriptSpawnActorComponent : ScriptServerComponent
{
};

```

### `ScriptTagComponent`
```
struct __cppobj ScriptTagComponent : ScriptServerComponent
{
};

```

### `ScriptTeleportComponent`
```
struct __cppobj ScriptTeleportComponent : ScriptServerComponent
{
};

```

### `ScriptTickingAreaDescriptionComponent`
```
struct __cppobj ScriptTickingAreaDescriptionComponent : ScriptServerComponent
{
};

```

### `ScriptTickWorldComponent`
```
struct __cppobj ScriptTickWorldComponent : ScriptServerComponent
{
};

```

### `ScriptLevelWeatherComponent`
```
struct __cppobj ScriptLevelWeatherComponent : ScriptServerComponent
{
};

```

### `ScriptLevelTickingAreasComponent`
```
struct __cppobj ScriptLevelTickingAreasComponent : ScriptServerComponent
{
};

```

### `ScriptServerBroadcastActorDefinitionEvent`
```
struct __cppobj ScriptServerBroadcastActorDefinitionEvent : ScriptServerReceiveEvent
{
};

```

### `ScriptServerChatReceived`
```
struct __cppobj ScriptServerChatReceived : ScriptServerReceiveEvent
{
};

```

### `ScriptServerCommandReceived`
```
struct __cppobj ScriptServerCommandReceived : ScriptServerReceiveEvent
{
};

```

### `ScriptServerLoggerConfigReceivedEvent`
```
struct __cppobj ScriptServerLoggerConfigReceivedEvent : ScriptServerReceiveEvent
{
};

```

### `ScriptServerPlaySoundEvent`
```
struct __cppobj ScriptServerPlaySoundEvent : ScriptServerReceiveEvent
{
};

```

### `ScriptServerSpawnParticleAttachedToActor`
```
struct __cppobj ScriptServerSpawnParticleAttachedToActor : ScriptServerReceiveEvent
{
};

```

### `ScriptServerSpawnParticleInWorldEvent`
```
struct __cppobj ScriptServerSpawnParticleInWorldEvent : ScriptServerReceiveEvent
{
};

```

### `ScriptServerBroadcastReceived`
```
struct __cppobj ScriptServerBroadcastReceived : ScriptServerReceiveEvent
{
};

```

### `ScriptCommandOrigin`
```
struct __cppobj ScriptCommandOrigin : CommandOrigin
{
  ServerLevel *mServerLevel;
  const bool mHandleCommandOutput;
  const ScriptCommandId mScriptCommandId;
  ScriptEngine *mEngine;
};

```

### `ScriptEventListener`
```
struct ScriptEventListener
{
  int (**_vptr$ScriptEventListener)(void);
};

```

### `ScriptApi::ScriptLanguageInterface`
```
struct ScriptApi::ScriptLanguageInterface
{
  int (**_vptr$ScriptLanguageInterface)(void);
};

```

### `ScriptBinderTemplateController`
```
struct ScriptBinderTemplateController
{
  std::unordered_map<std::string,std::unique_ptr<ScriptBinderTemplate>> mTemplates;
};

```

### `ScriptApi::ScriptReport`
```
struct ScriptApi::ScriptReport
{
  std::vector<std::shared_ptr<ScriptApi::ScriptReportItem>> mReportItems;
};

```

### `ScriptEventCoordinator`
```
struct __cppobj ScriptEventCoordinator : EventCoordinator<ScriptEventListener>
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

### `ScriptActorAreaBinderComponent`
```
struct __cppobj ScriptActorAreaBinderComponent : ScriptBinderComponent
{
  ActorUniqueID mActorId;
};

```

### `ScriptActorUniqueIdBinderComponent`
```
struct __cppobj ScriptActorUniqueIdBinderComponent : ScriptBinderComponent
{
  ActorUniqueID mActorId;
};

```

### `ScriptTickingAreaBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptTickingAreaBinderComponent : ScriptBinderComponent
{
  ScriptApi::ScriptObjectHandle mData;
};

```

### `ScriptBlockPositionBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptBlockPositionBinderComponent : ScriptBinderComponent
{
  BlockPos mPosition;
};

```

### `ScriptLevelBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptLevelBinderComponent : ScriptBinderComponent
{
  uint32_t mEcsId;
};

```

### `ScriptEcsBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptEcsBinderComponent : ScriptBinderComponent
{
  uint32_t mEcsId;
};

```

### `ScriptComponentBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptComponentBinderComponent : ScriptBinderComponent
{
  ScriptApi::ScriptObjectHandle mData;
};

```

### `ScriptIdentifierBinderComponent`
```
struct __cppobj ScriptIdentifierBinderComponent : ScriptBinderComponent
{
  std::string mIdentifier;
};

```

### `ScriptQueryBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptQueryBinderComponent : ScriptBinderComponent
{
  uint32_t mEcsId;
};

```

### `ScriptServerActorMoveEvent`
```
struct __cppobj ScriptServerActorMoveEvent : ScriptEventData
{
  ActorUniqueID mActorID;
};

```

### `ScriptContainerComponentBase`
```
struct __cppobj ScriptContainerComponentBase : ScriptServerComponent
{
};

```

### `ScriptServerComponent`
```
typedef ScriptTemplateFactory<ScriptServerContext>::Component ScriptServerComponent;

```

### `Shared<ITickingArea>`
```
typedef std::shared_ptr<ITickingArea> Shared<ITickingArea>;

```

### `ScriptServerEntity`
```
typedef ScriptTemplateFactory<ScriptServerContext>::Entity ScriptServerEntity;

```

### `ScriptServerReceiveEvent`
```
typedef ScriptTemplateFactory<ScriptServerContext>::ReceivedEvent ScriptServerReceiveEvent;

```

### `SystemFilePicker`
```
struct __cppobj SystemFilePicker : IFilePicker, std::enable_shared_from_this<SystemFilePicker>
{
};

```

### `ScopedProfileTag`
```
struct ScopedProfileTag
{
  __int8 gap0[1];
};

```

### `ServerFileChunkUploader`
```
struct __cppobj ServerFileChunkUploader : IFileChunkUploader, std::enable_shared_from_this<ServerFileChunkUploader>
{
  PacketSender *mPacketSender;
  const NetworkIdentifier *mSource;
  bool mInitialized;
  std::string mName;
  std::string mFileHash;
  FileChunkManager mChunkManager;
};

```

### `ScaleByAgeDefinition`
```
struct ScaleByAgeDefinition
{
  float mStartScale;
  float mEndScale;
};

```

### `Sheep`
```
struct __cppobj __attribute__((aligned(8))) Sheep : Animal
{
  int mEatAnimationTick;
};

```

### `Squid`
```
struct __cppobj Squid : Mob
{
  float mSpeed;
  float mTentacleSpeed;
  float mRotateSpeed;
  float mXBodyRot;
  float mXBodyRotO;
  float mZBodyRot;
  float mZBodyRotO;
  float mTx;
  float mTy;
  float mTz;
  float mTentacleMovement;
  float mOldTentacleMovement;
  float mTentacleAngle;
  float mOldTentacleAngle;
};

```

### `Salmon`
```
struct __cppobj Salmon : Fish
{
};

```

### `Skeleton`
```
struct __cppobj Skeleton : HumanoidMonster
{
  WitherBoss *mParentWither;
};

```

### `Spider`
```
struct __cppobj Spider : Monster
{
};

```

### `Slime`
```
struct __cppobj Slime : Monster
{
  float mTargetSquish;
  ParticleType mParticleType;
  float mSquish;
  float mOldSquish;
};

```

### `Silverfish`
```
struct __cppobj Silverfish : Monster
{
};

```

### `Shulker`
```
struct __cppobj Shulker : Mob
{
  const int TELEPORT_STEPS;
  float mCurrentPeekAmountO;
  float mCurrentPeekAmount;
  BlockPos mOldAttachPosition;
  bool mIsAttached;
  bool mWasAttached;
  int mClientSideTeleportInterpolation;
};

```

### `ShulkerBullet`
```
struct __cppobj ShulkerBullet : Actor
{
};

```

### `Snowball`
```
struct __cppobj Snowball : Throwable
{
};

```

### `SmallFireball`
```
struct __cppobj SmallFireball : Fireball
{
};

```

### `ShulkerBoxBlockActor`
```
struct __cppobj __attribute__((aligned(8))) ShulkerBoxBlockActor : ChestBlockActor:5192
{
  FacingID mFacing;
  bool mFacingChanged;
};

```

### `SwimMoveControl`
```
struct __cppobj SwimMoveControl : MoveControl
{
};

```

### `SlimeMoveControl`
```
struct __cppobj __attribute__((aligned(8))) SlimeMoveControl : MoveControl
{
  int mJumpDelayTicks;
};

```

### `ShareableDefinition`
```
struct ShareableDefinition
{
  std::vector<Shareable> mItems;
  bool mShareAllItems;
  int mAllItemWantAmount;
  int mAllItemSurplusAmount;
  int mAllItemMaxAmount;
};

```

### `serialize<DataItem>`
```
struct serialize<DataItem>
{
  __int8 gap0[1];
};

```

### `serialize<std::unique_ptr<DataItem> >`
```
struct serialize<std::unique_ptr<DataItem> >
{
  __int8 gap0[1];
};

```

### `StompEggGoal`
```
struct __cppobj __attribute__((aligned(8))) StompEggGoal : StompBlockGoal
{
};

```

### `StrollTowardsVillageGoal`
```
struct __cppobj StrollTowardsVillageGoal : MoveToVillageGoal:992
{
  float mStartChance;
};

```

### `ScaredGoal`
```
struct __cppobj __attribute__((aligned(8))) ScaredGoal : Goal
{
  Mob *mMob;
  int mInterval;
};

```

### `SilverfishMergeWithStoneGoal`
```
struct __cppobj __attribute__((aligned(4))) SilverfishMergeWithStoneGoal : RandomStrollGoal
{
  Silverfish *mSilverfish;
  int mSelectedFace;
  bool mDoMerge;
};

```

### `SilverfishWakeUpFriendsGoal`
```
struct __cppobj __attribute__((aligned(8))) SilverfishWakeUpFriendsGoal : Goal
{
  Silverfish *mSilverfish;
  int mLookForFriends;
};

```

### `SitGoal`
```
struct __cppobj SitGoal : Goal
{
  Mob *mMob;
};

```

### `SnackGoal`
```
struct __cppobj SnackGoal : Goal
{
  Mob *mMob;
  std::vector<ItemDescriptor> mItems;
  uint64_t mCooldown;
  const int mSnackCooldownTotal;
  const int mCooldownMin;
  const int mStopChance;
  TempEPtr<Actor> mTarget;
  Unique<Path> mPath;
};

```

### `StompAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) StompAttackGoal : MeleeAttackGoal
{
  int mAttackDelay;
};

```

### `SwimWanderGoal`
```
struct __cppobj __attribute__((aligned(8))) SwimWanderGoal : Goal:96
{
  float mSpeed;
  float mLookAhead;
  int mTicks;
  int mInterval;
  Mob *mMob;
  Vec3 mWanted;
};

```

### `SwimIdleGoal`
```
struct __cppobj SwimIdleGoal : Goal
{
  Mob *mMob;
  int mTicks;
  Vec3 mWantedPosition;
};

```

### `ShulkerPeekGoal`
```
struct __cppobj ShulkerPeekGoal : Goal:96
{
  int mPeekTime;
  Mob *mMob;
};

```

### `StalkAndPounceOnTargetGoal`
```
struct __cppobj StalkAndPounceOnTargetGoal : Goal:96
{
  float mStalkSpeed;
  float mStalkingMaxDistanceSqr;
  float mLeapHeight;
  float mLeapDistance;
  float mMaxPounceDistanceSqr;
  float mStrikeDistanceSqr;
  int mInterestedTicks;
  int mStuckTicks;
  Tick mEndTimestamp;
  ActorFilterGroup mStuckBlockList;
  StalkAndPounceOnTargetGoal::StalkAndPounceState mState;
  Mob *mMob;
};

```

### `SquidIdleGoal`
```
struct __cppobj __attribute__((aligned(8))) SquidIdleGoal : Goal
{
  Squid *mSquid;
  int mNumIdleTicks;
};

```

### `SquidFleeGoal`
```
struct __cppobj __attribute__((aligned(8))) SquidFleeGoal : Goal
{
  Squid *mSquid;
  int mNumFleeTicks;
};

```

### `SquidMoveAwayFromGroundGoal`
```
struct __cppobj SquidMoveAwayFromGroundGoal : Goal
{
  Squid *mSquid;
};

```

### `SquidOutOfWaterGoal`
```
struct __cppobj SquidOutOfWaterGoal : Goal
{
  Squid *mSquid;
};

```

### `SquidDiveGoal`
```
struct __cppobj SquidDiveGoal : Goal
{
  Squid *mSquid;
};

```

### `SkeletonHorseTrapGoal`
```
struct __cppobj SkeletonHorseTrapGoal : Goal
{
  Horse *mHorse;
  int mTrapLifeTicks;
  float mTriggerDistance;
};

```

### `SwellGoal`
```
struct __cppobj SwellGoal : Goal
{
  Creeper *mCreeper;
  float mStartSwellDist;
  float mStopSwellDist;
  TempEPtr<Actor> mTarget;
};

```

### `SlimeFloatGoal`
```
struct __cppobj SlimeFloatGoal : Goal
{
  Mob *mMob;
};

```

### `SlimeKeepOnJumpingGoal`
```
struct __cppobj SlimeKeepOnJumpingGoal : Goal
{
  Mob *mMob;
};

```

### `SlimeRandomDirectionGoal`
```
struct __cppobj SlimeRandomDirectionGoal : Goal
{
  Mob *mMob;
  float mChosenDegrees;
  int mNextRandomizeTime;
};

```

### `SlimeAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) SlimeAttackGoal : Goal
{
  Mob *mMob;
  int mGrowTiredTimer;
};

```

### `SwoopAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) SwoopAttackGoal : Goal
{
  Mob *mMob;
  float mSpeedMod;
  FloatRange mDelayRange;
  int mNextStartTick;
  bool mHurtTarget;
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
  uint64_t mCooldownStopTick;
  Vec3 mTargetPos;
  Vec3 mCasterPos;
};

```

### `SleepGoal`
```
struct __cppobj __attribute__((aligned(8))) SleepGoal : MoveToPOIGoal
{
  Mob *mMob;
  BedHelper mBedHelper;
  BlockPos mBedPos;
  Vec3 mSleepPos;
  Vec3 mBedOffset;
  Vec3 mExitPos;
  int mBedDir;
  float mBodyRot;
  const float mSleepYOffset;
  const float mSleepColliderHeight;
  const float mSleepColliderWidth;
  Vec2 mDefaultColliderDim;
  const Tick mGoalCooldownMax;
  Tick mCooldownTick;
  bool mWoken;
  bool mGoalEndedEarly;
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
  uint64_t mCooldownStopTick;
};

```

### `ShareItemsGoal`
```
struct __cppobj ShareItemsGoal : Goal
{
  Mob *mMob;
  int mThrowCountdown;
  int mSearchRange;
  float mSpeedModifier;
  float mGoalRadiusSq;
  int mTimeToRecalcPath;
  std::vector<MobDescriptor> mMobFilters;
  ItemStack mItemToShare;
  Unique<Path> mPath;
};

```

### `SneezeGoal`
```
struct __cppobj SneezeGoal : Goal:96
{
  int mCooldown;
  int mCooldownTimer;
  float mProbability;
  int mPreSneezeTimer;
  float mDropItemChance;
  std::string mLootTable;
  LevelSoundEvent mSneezeSound;
  LevelSoundEvent mPreSneezeSound;
  float mPrepareTime;
  const std::vector<MobDescriptor> mReactMobFilters;
  float mReactWithin;
  Mob *mMob;
};

```

### `StompBlockGoal`
```
struct __cppobj __attribute__((aligned(8))) StompBlockGoal : BaseMoveToBlockGoal
{
  const Block *mBlockToRemove;
  int mTicksSinceReachedGoal;
};

```

### `Spawner::MobSpawnedCallback`
```
typedef std::function<void (Mob &)> Spawner::MobSpawnedCallback;

```

### `SwimWithMobGoal`
```
struct __cppobj __attribute__((aligned(8))) SwimWithMobGoal : Goal
{
  Mob *mMob;
  TempEPtr<Actor> mFollowing;
  int mTimeToRecalcPath;
  MobGoals mCurrentGoal;
  const std::vector<MobDescriptor> mTargetTypes;
  float mSpeed;
  float mStopDistance;
  int mSearchArea;
};

```

### `StateAnimationVariable`
```
struct StateAnimationVariable
{
  HashedString mVariableName;
  ExpressionNode mInput;
  std::vector<AnimationValueCurveKeyFrame> mKeyFrames;
};

```

### `SkullBlockActor`
```
struct __cppobj __attribute__((aligned(8))) SkullBlockActor : BlockActor:1632
{
  SkullBlockActor::SkullType mSkullType;
  float mRotation;
  bool mIsMovingMouth;
  int mMouthTickCount;
};

```

### `SplashPotionItem`
```
struct __cppobj SplashPotionItem : PotionItem
{
  TextureUVCoordinateSet mSplashIcons[26];
  Potion::PotionVariant mSplashPotionVariants[26];
};

```

### `SurvivalMode`
```
struct __cppobj SurvivalMode : GameMode:1312
{
  bool mIsTrialMode;
  bool mHasDisplayedIntro;
  int mTrialEndedReminder;
  std::function<void (bool)> mShowUpsellScreenCallback;
};

```

### `ShieldItem`
```
struct __cppobj ShieldItem : Item
{
};

```

### `SerializedSkin_0`
```
struct SerializedSkin_0
{
  std::string mId;
  std::string fullId;
  std::string mResourcePatch;
  std::string mDefaultGeometryName;
  mce::Image_0 mSkinImage;
  mce::Image_0 mCapeImage;
  std::vector<AnimatedImageData>_0 mSkinAnimatedImages;
  Json::Value mGeometryData;
  Json::Value mGeometryDataMutable;
  std::string mAnimationData;
  std::string mCapeId;
  bool mIsPremium;
  bool mIsPersona;
  bool mIsPersonaCapeOnClassicSkin;
  TrustedSkinFlag mIsTrustedSkin;
  std::vector<SerializedPersonaPieceHandle> mPersonaPieces;
  std::string mArmSize;
  std::unordered_map<persona::PieceType,TintMapColor> mPieceTintColors;
  Color mSkinColor;
};

```

### `SkinInfoData`
```
struct SkinInfoData
{
  int (**_vptr$SkinInfoData)(void);
  std::string mDefaultMeshName;
  bool mIsAlphaTest;
  bool mIsDirty;
  SerializedSkin mSkin;
};

```

### `StickInGroundSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) StickInGroundSubcomponent : OnHitSubcomponent
{
  int mShakeTime;
};

```

### `SpawnChanceSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) SpawnChanceSubcomponent : OnHitSubcomponent
{
  float mFirstSpawnChance;
  float mSecondSpawnChance;
  int mFirstSpawnCount;
  int mSecondSpawnCount;
  ActorDefinitionIdentifier mSpawnDefinition;
  bool mSpawnBaby;
};

```

### `SpawnAoECloudSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) SpawnAoECloudSubcomponent : OnHitSubcomponent
{
  int mPotionId;
  int mDuration;
  int mParticle;
  int mReapplicationDelay;
  float mRadius;
  float mRadiusOnUse;
  Color mParticleColor;
  bool mAffectOwner;
};

```

### `ShiftedValueAmplifier`
```
struct __cppobj ShiftedValueAmplifier : Amplifier
{
  int mShiftedValue;
  float mScalar;
};

```

### `ShiftedDurationAmplifier`
```
struct __cppobj __attribute__((aligned(8))) ShiftedDurationAmplifier : Amplifier
{
  int mShiftedValue;
};

```

### `SharedAttributes`
```
struct SharedAttributes
{
  __int8 gap0[1];
};

```

### `SharedAmplifiers`
```
struct SharedAmplifiers
{
  __int8 gap0[1];
};

```

### `SharedBuffs`
```
struct SharedBuffs
{
  __int8 gap0[1];
};

```

### `SharedModifiers`
```
struct SharedModifiers
{
  __int8 gap0[1];
};

```

### `SeedItemComponent`
```
struct __attribute__((aligned(8))) SeedItemComponent
{
  Item *mOwner;
  const Block *mResult;
  std::vector<const Block *> mTargetLandBlocks;
  bool mIsPlanting;
};

```

### `SharedCounter<AirBlockItem>`
```
struct SharedCounter<AirBlockItem>
{
  AirBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BlockItem>`
```
struct SharedCounter<BlockItem>
{
  BlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ShieldItemUtils`
```
struct ShieldItemUtils
{
  __int8 gap0[1];
};

```

### `SuspiciousStewItem`
```
struct __cppobj SuspiciousStewItem : Item
{
};

```

### `SignBlockActor`
```
struct __cppobj __attribute__((aligned(8))) SignBlockActor : BlockActor
{
  std::string mOwnerID;
  std::string mMessage;
  std::string mTextObjectString;
  TextObjectRoot mTextObjectMessage;
  SignBlockActor::CachedMessageData mCachedMessage;
  SignBlockActor::SignType mType;
};

```

### `SharedCounter<ShovelItem>`
```
struct SharedCounter<ShovelItem>
{
  ShovelItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ShovelItem`
```
struct __cppobj ShovelItem : DiggerItem
{
};

```

### `SharedCounter<PickaxeItem>`
```
struct SharedCounter<PickaxeItem>
{
  PickaxeItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HatchetItem>`
```
struct SharedCounter<HatchetItem>
{
  HatchetItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FlintAndSteelItem>`
```
struct SharedCounter<FlintAndSteelItem>
{
  FlintAndSteelItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BowItem>`
```
struct SharedCounter<BowItem>
{
  BowItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ArrowItem>`
```
struct SharedCounter<ArrowItem>
{
  ArrowItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CoalItem>`
```
struct SharedCounter<CoalItem>
{
  CoalItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WeaponItem>`
```
struct SharedCounter<WeaponItem>
{
  WeaponItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BlockPlanterItem>`
```
struct SharedCounter<BlockPlanterItem>
{
  BlockPlanterItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HoeItem>`
```
struct SharedCounter<HoeItem>
{
  HoeItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ArmorItem>`
```
struct SharedCounter<ArmorItem>
{
  ArmorItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ShieldItem>`
```
struct SharedCounter<ShieldItem>
{
  ShieldItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HangingActorItem>`
```
struct SharedCounter<HangingActorItem>
{
  HangingActorItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SignItem>`
```
struct SharedCounter<SignItem>
{
  SignItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SignItem`
```
struct __cppobj __attribute__((aligned(8))) SignItem : Item
{
  std::map<SignBlockActor::SignType,std::pair<const Block *,const Block *>> mConvertMap;
  SignBlockActor::SignType mType;
};

```

### `SharedCounter<DoorItem>`
```
struct SharedCounter<DoorItem>
{
  DoorItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BucketItem>`
```
struct SharedCounter<BucketItem>
{
  BucketItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MinecartItem>`
```
struct SharedCounter<MinecartItem>
{
  MinecartItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedStoneDustItem>`
```
struct SharedCounter<RedStoneDustItem>
{
  RedStoneDustItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SnowballItem>`
```
struct SharedCounter<SnowballItem>
{
  SnowballItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SnowballItem`
```
struct __cppobj SnowballItem : Item
{
};

```

### `SharedCounter<BoatItem>`
```
struct SharedCounter<BoatItem>
{
  BoatItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EnchantedBookItem>`
```
struct SharedCounter<EnchantedBookItem>
{
  EnchantedBookItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EggItem>`
```
struct SharedCounter<EggItem>
{
  EggItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CompassItem>`
```
struct SharedCounter<CompassItem>
{
  CompassItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FishingRodItem>`
```
struct SharedCounter<FishingRodItem>
{
  FishingRodItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ClockItem>`
```
struct SharedCounter<ClockItem>
{
  ClockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DyePowderItem>`
```
struct SharedCounter<DyePowderItem>
{
  DyePowderItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BedItem>`
```
struct SharedCounter<BedItem>
{
  BedItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MapItem>`
```
struct SharedCounter<MapItem>
{
  MapItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ShearsItem>`
```
struct SharedCounter<ShearsItem>
{
  ShearsItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ShearsItem`
```
struct __cppobj ShearsItem : Item
{
};

```

### `SharedCounter<EnderpearlItem>`
```
struct SharedCounter<EnderpearlItem>
{
  EnderpearlItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PotionItem>`
```
struct SharedCounter<PotionItem>
{
  PotionItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BottleItem>`
```
struct SharedCounter<BottleItem>
{
  BottleItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EnderEyeItem>`
```
struct SharedCounter<EnderEyeItem>
{
  EnderEyeItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MobPlacerItem>`
```
struct SharedCounter<MobPlacerItem>
{
  MobPlacerItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ExperiencePotionItem>`
```
struct SharedCounter<ExperiencePotionItem>
{
  ExperiencePotionItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FireChargeItem>`
```
struct SharedCounter<FireChargeItem>
{
  FireChargeItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WritableBookItem>`
```
struct SharedCounter<WritableBookItem>
{
  WritableBookItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WrittenBookItem>`
```
struct SharedCounter<WrittenBookItem>
{
  WrittenBookItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EmptyMapItem>`
```
struct SharedCounter<EmptyMapItem>
{
  EmptyMapItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SkullItem>`
```
struct SharedCounter<SkullItem>
{
  SkullItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SkullItem`
```
struct __cppobj SkullItem : Item
{
};

```

### `SharedCounter<CarrotOnAStickItem>`
```
struct SharedCounter<CarrotOnAStickItem>
{
  CarrotOnAStickItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FireworksItem>`
```
struct SharedCounter<FireworksItem>
{
  FireworksItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FireworkChargeItem>`
```
struct SharedCounter<FireworkChargeItem>
{
  FireworkChargeItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HorseArmorItem>`
```
struct SharedCounter<HorseArmorItem>
{
  HorseArmorItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RecordItem>`
```
struct SharedCounter<RecordItem>
{
  RecordItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TridentItem>`
```
struct SharedCounter<TridentItem>
{
  TridentItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LeadItem>`
```
struct SharedCounter<LeadItem>
{
  LeadItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ArmorStandItem>`
```
struct SharedCounter<ArmorStandItem>
{
  ArmorStandItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EndCrystalItem>`
```
struct SharedCounter<EndCrystalItem>
{
  EndCrystalItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SplashPotionItem>`
```
struct SharedCounter<SplashPotionItem>
{
  SplashPotionItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LingeringPotionItem>`
```
struct SharedCounter<LingeringPotionItem>
{
  LingeringPotionItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BannerItem>`
```
struct SharedCounter<BannerItem>
{
  BannerItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CrossbowItem>`
```
struct SharedCounter<CrossbowItem>
{
  CrossbowItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BannerPatternItem>`
```
struct SharedCounter<BannerPatternItem>
{
  BannerPatternItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SuspiciousStewItem>`
```
struct SharedCounter<SuspiciousStewItem>
{
  SuspiciousStewItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CameraItem>`
```
struct SharedCounter<CameraItem>
{
  CameraItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CompoundItem>`
```
struct SharedCounter<CompoundItem>
{
  CompoundItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<IceBombItem>`
```
struct SharedCounter<IceBombItem>
{
  IceBombItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChemistryItem>`
```
struct SharedCounter<ChemistryItem>
{
  ChemistryItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RapidFertilizerItem>`
```
struct SharedCounter<RapidFertilizerItem>
{
  RapidFertilizerItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BalloonItem>`
```
struct SharedCounter<BalloonItem>
{
  BalloonItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MedicineItem>`
```
struct SharedCounter<MedicineItem>
{
  MedicineItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SparklerItem>`
```
struct SharedCounter<SparklerItem>
{
  SparklerItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SparklerItem`
```
struct __cppobj __attribute__((aligned(8))) SparklerItem : ChemistryStickItem
{
};

```

### `SharedCounter<GlowStickItem>`
```
struct SharedCounter<GlowStickItem>
{
  GlowStickItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<AuxDataBlockItem>`
```
struct SharedCounter<AuxDataBlockItem>
{
  AuxDataBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ClothBlockItem>`
```
struct SharedCounter<ClothBlockItem>
{
  ClothBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneSlabBlockItem>`
```
struct SharedCounter<StoneSlabBlockItem>
{
  StoneSlabBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneSlabBlockItem`
```
struct __cppobj StoneSlabBlockItem : SlabBlockItem
{
};

```

### `SlabBlockItem`
```
struct __cppobj SlabBlockItem : BlockItem
{
};

```

### `SharedCounter<CoralFanBlockItem>`
```
struct SharedCounter<CoralFanBlockItem>
{
  CoralFanBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SeaPickleBlockItem>`
```
struct SharedCounter<SeaPickleBlockItem>
{
  SeaPickleBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SeaPickleBlockItem`
```
struct __cppobj SeaPickleBlockItem : BlockItem
{
};

```

### `SharedCounter<SaplingBlockItem>`
```
struct SharedCounter<SaplingBlockItem>
{
  SaplingBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SaplingBlockItem`
```
struct __cppobj SaplingBlockItem : BlockItem
{
};

```

### `SharedCounter<LeafBlockItem>`
```
struct SharedCounter<LeafBlockItem>
{
  LeafBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WoodSlabBlockItem>`
```
struct SharedCounter<WoodSlabBlockItem>
{
  WoodSlabBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WaterLilyBlockItem>`
```
struct SharedCounter<WaterLilyBlockItem>
{
  WaterLilyBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TopSnowBlockItem>`
```
struct SharedCounter<TopSnowBlockItem>
{
  TopSnowBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ShulkerBoxBlockItem>`
```
struct SharedCounter<ShulkerBoxBlockItem>
{
  ShulkerBoxBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ShulkerBoxBlockItem`
```
struct __cppobj ShulkerBoxBlockItem : AuxDataBlockItem
{
};

```

### `SharedCounter<BambooBlockItem>`
```
struct SharedCounter<BambooBlockItem>
{
  BambooBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ScaffoldingBlockItem>`
```
struct SharedCounter<ScaffoldingBlockItem>
{
  ScaffoldingBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ScaffoldingBlockItem`
```
struct __cppobj ScaffoldingBlockItem : BlockItem
{
};

```

### `SharedCounter<BellBlockItem>`
```
struct SharedCounter<BellBlockItem>
{
  BellBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChemistryAuxDataBlockItem>`
```
struct SharedCounter<ChemistryAuxDataBlockItem>
{
  ChemistryAuxDataBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ElementBlockItem>`
```
struct SharedCounter<ElementBlockItem>
{
  ElementBlockItem *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `serialize<RecipeIngredient>`
```
struct serialize<RecipeIngredient>
{
  __int8 gap0[1];
};

```

### `SwimEnchant`
```
struct __cppobj SwimEnchant : Enchant
{
};

```

### `SpawnDataList`
```
typedef std::vector<SpawnData> SpawnDataList;

```

### `SmallSet<Actor *>::iterator`
```
typedef std::vector<Actor *>::iterator SmallSet<Actor *>::iterator;

```

### `SpawnGroupData`
```
struct SpawnGroupData
{
  std::string mIdentifier;
  std::vector<MobSpawnRules> mSpawnRules;
};

```

### `SharePtrRefTraits<PerlinSimplexNoise>::OwnerStackRef`
```
typedef SharePtrRefTraits<PerlinSimplexNoise>::StackRef SharePtrRefTraits<PerlinSimplexNoise>::OwnerStackRef;

```

### `SharePtrRefTraits<PerlinSimplexNoise>::StackRef`
```
typedef PerlinSimplexNoise SharePtrRefTraits<PerlinSimplexNoise>::StackRef;

```

### `SharePtrRefTraits<PerlinSimplexNoise>`
```
struct SharePtrRefTraits<PerlinSimplexNoise>
{
  __int8 gap0[1];
};

```

### `StackResultStorageSharePtr<PerlinSimplexNoise>`
```
struct StackResultStorageSharePtr<PerlinSimplexNoise>
{
  std::shared_ptr<PerlinSimplexNoise> mValue;
};

```

### `SurfaceMaterialAdjustmentAttributes::Element`
```
struct SurfaceMaterialAdjustmentAttributes::Element
{
  float mLowerBound;
  float mUpperBound;
  SurfaceMaterialAttributes mAdjustedMaterials;
};

```

### `ShoreAttributes`
```
typedef WeightedBiomeAttributes<ShoreTransformation> ShoreAttributes;

```

### `SmokerBlockActor`
```
struct __cppobj __attribute__((aligned(8))) SmokerBlockActor : FurnaceBlockActor
{
};

```

### `SetBlockReactionComponent`
```
struct __cppobj SetBlockReactionComponent : LabTableReactionComponent
{
  std::unique_ptr<BlockPos> mPos;
  const Block *mBlock;
};

```

### `SmallSet<ActorUniqueID>::const_iterator`
```
typedef std::vector<ActorUniqueID>::const_iterator SmallSet<ActorUniqueID>::const_iterator;

```

### `SmallSet<ActorUniqueID>::iterator`
```
typedef std::vector<ActorUniqueID>::iterator SmallSet<ActorUniqueID>::iterator;

```

### `StructureEditorData_1`
```
struct StructureEditorData_1
{
  std::string mStructureName;
  std::string mDataField;
  bool mIncludePlayers;
  bool mShowBoundingBox;
  StructureRedstoneSaveMode mRedstoneSaveMode;
  StructureBlockType mType;
  StructureSettings_1 mSettings;
};

```

### `StructureSettings_1`
```
struct __attribute__((aligned(8))) StructureSettings_1
{
  std::string mPaletteName;
  bool mIgnoreEntities;
  bool mIgnoreBlocks;
  BlockPos mStructureSize;
  BlockPos mStructureOffset;
  Vec3 mPivot;
  ActorUniqueID mLastTouchedByPlayer;
  Rotation_0 mRotation;
  Mirror_0 mMirror;
  float mIntegrityValue;
  RandomSeed_0 mIntegritySeed;
};

```

### `SharedCounter<AirBlock>`
```
struct SharedCounter<AirBlock>
{
  AirBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneBlock>`
```
struct SharedCounter<StoneBlock>
{
  StoneBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneBlock`
```
struct __cppobj StoneBlock : BlockLegacy
{
};

```

### `SharedCounter<GrassBlock>`
```
struct SharedCounter<GrassBlock>
{
  GrassBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DirtBlock>`
```
struct SharedCounter<DirtBlock>
{
  DirtBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PlanksBlock>`
```
struct SharedCounter<PlanksBlock>
{
  PlanksBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<Sapling>`
```
struct SharedCounter<Sapling>
{
  Sapling *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `Sapling`
```
struct __cppobj Sapling : BushBlock
{
};

```

### `SharedCounter<BedrockBlock>`
```
struct SharedCounter<BedrockBlock>
{
  BedrockBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LiquidBlockDynamic>`
```
struct SharedCounter<LiquidBlockDynamic>
{
  LiquidBlockDynamic *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LiquidBlockStatic>`
```
struct SharedCounter<LiquidBlockStatic>
{
  LiquidBlockStatic *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SandBlock>`
```
struct SharedCounter<SandBlock>
{
  SandBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SandBlock`
```
struct __cppobj SandBlock : HeavyBlock
{
};

```

### `SharedCounter<GravelBlock>`
```
struct SharedCounter<GravelBlock>
{
  GravelBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<OreBlock>`
```
struct SharedCounter<OreBlock>
{
  OreBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<OldLogBlock>`
```
struct SharedCounter<OldLogBlock>
{
  OldLogBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<OldLeafBlock>`
```
struct SharedCounter<OldLeafBlock>
{
  OldLeafBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SpongeBlock>`
```
struct SharedCounter<SpongeBlock>
{
  SpongeBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SpongeBlock`
```
struct __cppobj SpongeBlock : BlockLegacy
{
};

```

### `SharedCounter<GlassBlock>`
```
struct SharedCounter<GlassBlock>
{
  GlassBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DispenserBlock>`
```
struct SharedCounter<DispenserBlock>
{
  DispenserBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SandStoneBlock>`
```
struct SharedCounter<SandStoneBlock>
{
  SandStoneBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SandStoneBlock`
```
struct __cppobj SandStoneBlock : BlockLegacy
{
};

```

### `SharedCounter<NoteBlock>`
```
struct SharedCounter<NoteBlock>
{
  NoteBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BedBlock>`
```
struct SharedCounter<BedBlock>
{
  BedBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PoweredRailBlock>`
```
struct SharedCounter<PoweredRailBlock>
{
  PoweredRailBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DetectorRailBlock>`
```
struct SharedCounter<DetectorRailBlock>
{
  DetectorRailBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PistonBlock>`
```
struct SharedCounter<PistonBlock>
{
  PistonBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WebBlock>`
```
struct SharedCounter<WebBlock>
{
  WebBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TallGrass>`
```
struct SharedCounter<TallGrass>
{
  TallGrass *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DeadBush>`
```
struct SharedCounter<DeadBush>
{
  DeadBush *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PistonArmBlock>`
```
struct SharedCounter<PistonArmBlock>
{
  PistonArmBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ClothBlock>`
```
struct SharedCounter<ClothBlock>
{
  ClothBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FlowerBlock>`
```
struct SharedCounter<FlowerBlock>
{
  FlowerBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MushroomBlock>`
```
struct SharedCounter<MushroomBlock>
{
  MushroomBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MetalBlock>`
```
struct SharedCounter<MetalBlock>
{
  MetalBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneSlabBlock>`
```
struct SharedCounter<StoneSlabBlock>
{
  StoneSlabBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneSlabBlock`
```
struct __cppobj StoneSlabBlock : SlabBlock
{
};

```

### `SharedCounter<TntBlock>`
```
struct SharedCounter<TntBlock>
{
  TntBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BookshelfBlock>`
```
struct SharedCounter<BookshelfBlock>
{
  BookshelfBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ObsidianBlock>`
```
struct SharedCounter<ObsidianBlock>
{
  ObsidianBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TorchBlock>`
```
struct SharedCounter<TorchBlock>
{
  TorchBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MobSpawnerBlock>`
```
struct SharedCounter<MobSpawnerBlock>
{
  MobSpawnerBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StairBlock>`
```
struct SharedCounter<StairBlock>
{
  StairBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChestBlock>`
```
struct SharedCounter<ChestBlock>
{
  ChestBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedStoneWireBlock>`
```
struct SharedCounter<RedStoneWireBlock>
{
  RedStoneWireBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WorkbenchBlock>`
```
struct SharedCounter<WorkbenchBlock>
{
  WorkbenchBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CropBlock>`
```
struct SharedCounter<CropBlock>
{
  CropBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FarmBlock>`
```
struct SharedCounter<FarmBlock>
{
  FarmBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FurnaceBlock>`
```
struct SharedCounter<FurnaceBlock>
{
  FurnaceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SignBlock>`
```
struct SharedCounter<SignBlock>
{
  SignBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SignBlock`
```
struct __cppobj __attribute__((aligned(4))) SignBlock : ActorBlock
{
  SignBlockActor::SignType mSignType;
  bool mOnGround;
};

```

### `SharedCounter<DoorBlock>`
```
struct SharedCounter<DoorBlock>
{
  DoorBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LadderBlock>`
```
struct SharedCounter<LadderBlock>
{
  LadderBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RailBlock>`
```
struct SharedCounter<RailBlock>
{
  RailBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LeverBlock>`
```
struct SharedCounter<LeverBlock>
{
  LeverBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PressurePlateBlock>`
```
struct SharedCounter<PressurePlateBlock>
{
  PressurePlateBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedStoneOreBlock>`
```
struct SharedCounter<RedStoneOreBlock>
{
  RedStoneOreBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedstoneTorchBlock>`
```
struct SharedCounter<RedstoneTorchBlock>
{
  RedstoneTorchBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneButtonBlock>`
```
struct SharedCounter<StoneButtonBlock>
{
  StoneButtonBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneButtonBlock`
```
struct __cppobj __attribute__((aligned(8))) StoneButtonBlock : ButtonBlock
{
};

```

### `SharedCounter<TopSnowBlock>`
```
struct SharedCounter<TopSnowBlock>
{
  TopSnowBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<IceBlock>`
```
struct SharedCounter<IceBlock>
{
  IceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SnowBlock>`
```
struct SharedCounter<SnowBlock>
{
  SnowBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SnowBlock`
```
struct __cppobj SnowBlock : BlockLegacy
{
};

```

### `SharedCounter<CactusBlock>`
```
struct SharedCounter<CactusBlock>
{
  CactusBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ClayBlock>`
```
struct SharedCounter<ClayBlock>
{
  ClayBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ReedBlock>`
```
struct SharedCounter<ReedBlock>
{
  ReedBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<JukeboxBlock>`
```
struct SharedCounter<JukeboxBlock>
{
  JukeboxBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FenceBlock>`
```
struct SharedCounter<FenceBlock>
{
  FenceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PumpkinBlock>`
```
struct SharedCounter<PumpkinBlock>
{
  PumpkinBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SoulSandBlock>`
```
struct SharedCounter<SoulSandBlock>
{
  SoulSandBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SoulSandBlock`
```
struct __cppobj SoulSandBlock : BlockLegacy
{
};

```

### `SharedCounter<LightGemBlock>`
```
struct SharedCounter<LightGemBlock>
{
  LightGemBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PortalBlock>`
```
struct SharedCounter<PortalBlock>
{
  PortalBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CakeBlock>`
```
struct SharedCounter<CakeBlock>
{
  CakeBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RepeaterBlock>`
```
struct SharedCounter<RepeaterBlock>
{
  RepeaterBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<InvisibleBlock>`
```
struct SharedCounter<InvisibleBlock>
{
  InvisibleBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TrapDoorBlock>`
```
struct SharedCounter<TrapDoorBlock>
{
  TrapDoorBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MonsterEggBlock>`
```
struct SharedCounter<MonsterEggBlock>
{
  MonsterEggBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneBrickBlock>`
```
struct SharedCounter<StoneBrickBlock>
{
  StoneBrickBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneBrickBlock`
```
struct __cppobj StoneBrickBlock : BlockLegacy
{
};

```

### `SharedCounter<HugeMushroomBlock>`
```
struct SharedCounter<HugeMushroomBlock>
{
  HugeMushroomBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ThinFenceBlock>`
```
struct SharedCounter<ThinFenceBlock>
{
  ThinFenceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MelonBlock>`
```
struct SharedCounter<MelonBlock>
{
  MelonBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StemBlock>`
```
struct SharedCounter<StemBlock>
{
  StemBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StemBlock`
```
struct __cppobj StemBlock : BushBlock
{
  const BlockLegacy *mFruit;
};

```

### `SharedCounter<VineBlock>`
```
struct SharedCounter<VineBlock>
{
  VineBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FenceGateBlock>`
```
struct SharedCounter<FenceGateBlock>
{
  FenceGateBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MyceliumBlock>`
```
struct SharedCounter<MyceliumBlock>
{
  MyceliumBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WaterlilyBlock>`
```
struct SharedCounter<WaterlilyBlock>
{
  WaterlilyBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<NetherWartBlock>`
```
struct SharedCounter<NetherWartBlock>
{
  NetherWartBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EnchantingTableBlock>`
```
struct SharedCounter<EnchantingTableBlock>
{
  EnchantingTableBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BrewingStandBlock>`
```
struct SharedCounter<BrewingStandBlock>
{
  BrewingStandBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CauldronBlock>`
```
struct SharedCounter<CauldronBlock>
{
  CauldronBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EndPortalBlock>`
```
struct SharedCounter<EndPortalBlock>
{
  EndPortalBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EndPortalFrameBlock>`
```
struct SharedCounter<EndPortalFrameBlock>
{
  EndPortalFrameBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DragonEggBlock>`
```
struct SharedCounter<DragonEggBlock>
{
  DragonEggBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedstoneLampBlock>`
```
struct SharedCounter<RedstoneLampBlock>
{
  RedstoneLampBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DropperBlock>`
```
struct SharedCounter<DropperBlock>
{
  DropperBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ActivatorRailBlock>`
```
struct SharedCounter<ActivatorRailBlock>
{
  ActivatorRailBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CocoaBlock>`
```
struct SharedCounter<CocoaBlock>
{
  CocoaBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EnderChestBlock>`
```
struct SharedCounter<EnderChestBlock>
{
  EnderChestBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TripWireHookBlock>`
```
struct SharedCounter<TripWireHookBlock>
{
  TripWireHookBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TripWireBlock>`
```
struct SharedCounter<TripWireBlock>
{
  TripWireBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CommandBlock>`
```
struct SharedCounter<CommandBlock>
{
  CommandBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BeaconBlock>`
```
struct SharedCounter<BeaconBlock>
{
  BeaconBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WallBlock>`
```
struct SharedCounter<WallBlock>
{
  WallBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FlowerPotBlock>`
```
struct SharedCounter<FlowerPotBlock>
{
  FlowerPotBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CarrotBlock>`
```
struct SharedCounter<CarrotBlock>
{
  CarrotBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PotatoBlock>`
```
struct SharedCounter<PotatoBlock>
{
  PotatoBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WoodButtonBlock>`
```
struct SharedCounter<WoodButtonBlock>
{
  WoodButtonBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SkullBlock>`
```
struct SharedCounter<SkullBlock>
{
  SkullBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SkullBlock`
```
struct __cppobj SkullBlock : ActorBlock
{
};

```

### `SharedCounter<AnvilBlock>`
```
struct SharedCounter<AnvilBlock>
{
  AnvilBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WeightedPressurePlateBlock>`
```
struct SharedCounter<WeightedPressurePlateBlock>
{
  WeightedPressurePlateBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ComparatorBlock>`
```
struct SharedCounter<ComparatorBlock>
{
  ComparatorBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DaylightDetectorBlock>`
```
struct SharedCounter<DaylightDetectorBlock>
{
  DaylightDetectorBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RedstoneBlock>`
```
struct SharedCounter<RedstoneBlock>
{
  RedstoneBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HopperBlock>`
```
struct SharedCounter<HopperBlock>
{
  HopperBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<QuartzBlockBlock>`
```
struct SharedCounter<QuartzBlockBlock>
{
  QuartzBlockBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WoodSlabBlock>`
```
struct SharedCounter<WoodSlabBlock>
{
  WoodSlabBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ColoredBlock>`
```
struct SharedCounter<ColoredBlock>
{
  ColoredBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StainedGlassPaneBlock>`
```
struct SharedCounter<StainedGlassPaneBlock>
{
  StainedGlassPaneBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StainedGlassPaneBlock`
```
struct __cppobj __attribute__((aligned(8))) StainedGlassPaneBlock : ThinFenceBlock
{
};

```

### `SharedCounter<NewLeafBlock>`
```
struct SharedCounter<NewLeafBlock>
{
  NewLeafBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<NewLogBlock>`
```
struct SharedCounter<NewLogBlock>
{
  NewLogBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SlimeBlock>`
```
struct SharedCounter<SlimeBlock>
{
  SlimeBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SlimeBlock`
```
struct __cppobj SlimeBlock : BlockLegacy
{
};

```

### `SharedCounter<PrismarineBlock>`
```
struct SharedCounter<PrismarineBlock>
{
  PrismarineBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SeaLanternBlock>`
```
struct SharedCounter<SeaLanternBlock>
{
  SeaLanternBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SeaLanternBlock`
```
struct __cppobj SeaLanternBlock : BlockLegacy
{
};

```

### `SharedCounter<HayBlockBlock>`
```
struct SharedCounter<HayBlockBlock>
{
  HayBlockBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WoolCarpetBlock>`
```
struct SharedCounter<WoolCarpetBlock>
{
  WoolCarpetBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DoublePlantBlock>`
```
struct SharedCounter<DoublePlantBlock>
{
  DoublePlantBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BannerBlock>`
```
struct SharedCounter<BannerBlock>
{
  BannerBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneSlabBlock2>`
```
struct SharedCounter<StoneSlabBlock2>
{
  StoneSlabBlock2 *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneSlabBlock2`
```
struct __cppobj StoneSlabBlock2 : SlabBlock
{
};

```

### `SharedCounter<GrassPathBlock>`
```
struct SharedCounter<GrassPathBlock>
{
  GrassPathBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ItemFrameBlock>`
```
struct SharedCounter<ItemFrameBlock>
{
  ItemFrameBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChorusFlowerBlock>`
```
struct SharedCounter<ChorusFlowerBlock>
{
  ChorusFlowerBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<UndyedShulkerBoxBlock>`
```
struct SharedCounter<UndyedShulkerBoxBlock>
{
  UndyedShulkerBoxBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FrostedIceBlock>`
```
struct SharedCounter<FrostedIceBlock>
{
  FrostedIceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EndRodBlock>`
```
struct SharedCounter<EndRodBlock>
{
  EndRodBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<EndGatewayBlock>`
```
struct SharedCounter<EndGatewayBlock>
{
  EndGatewayBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MagmaBlock>`
```
struct SharedCounter<MagmaBlock>
{
  MagmaBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<RotatedPillarBlock>`
```
struct SharedCounter<RotatedPillarBlock>
{
  RotatedPillarBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StructureVoid>`
```
struct SharedCounter<StructureVoid>
{
  StructureVoid *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StructureVoid`
```
struct __cppobj StructureVoid : BlockLegacy
{
};

```

### `SharedCounter<ShulkerBoxBlock>`
```
struct SharedCounter<ShulkerBoxBlock>
{
  ShulkerBoxBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ShulkerBoxBlock`
```
struct __cppobj __attribute__((aligned(8))) ShulkerBoxBlock : ChestBlock
{
};

```

### `SharedCounter<GlazedTerracottaBlock>`
```
struct SharedCounter<GlazedTerracottaBlock>
{
  GlazedTerracottaBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ConcreteBlock>`
```
struct SharedCounter<ConcreteBlock>
{
  ConcreteBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ConcretePowderBlock>`
```
struct SharedCounter<ConcretePowderBlock>
{
  ConcretePowderBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChorusPlantBlock>`
```
struct SharedCounter<ChorusPlantBlock>
{
  ChorusPlantBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StainedGlassBlock>`
```
struct SharedCounter<StainedGlassBlock>
{
  StainedGlassBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StainedGlassBlock`
```
struct __cppobj __attribute__((aligned(8))) StainedGlassBlock : BlockLegacy
{
  bool mDoesDrops;
  bool mCanBeUsedInCommands;
};

```

### `SharedCounter<CameraBlock>`
```
struct SharedCounter<CameraBlock>
{
  CameraBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<PodzolBlock>`
```
struct SharedCounter<PodzolBlock>
{
  PodzolBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BeetrootBlock>`
```
struct SharedCounter<BeetrootBlock>
{
  BeetrootBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StonecutterBlock>`
```
struct SharedCounter<StonecutterBlock>
{
  StonecutterBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StonecutterBlock`
```
struct __cppobj StonecutterBlock : BlockLegacy
{
};

```

### `SharedCounter<NetherReactorBlock>`
```
struct SharedCounter<NetherReactorBlock>
{
  NetherReactorBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<MovingBlock>`
```
struct SharedCounter<MovingBlock>
{
  MovingBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ObserverBlock>`
```
struct SharedCounter<ObserverBlock>
{
  ObserverBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StructureBlock>`
```
struct SharedCounter<StructureBlock>
{
  StructureBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StructureBlock`
```
struct __cppobj StructureBlock : ActorBlock
{
};

```

### `SharedCounter<StrippedLogBlock>`
```
struct SharedCounter<StrippedLogBlock>
{
  StrippedLogBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StrippedLogBlock`
```
struct __cppobj StrippedLogBlock : RotatedPillarBlock
{
};

```

### `SharedCounter<BlueIceBlock>`
```
struct SharedCounter<BlueIceBlock>
{
  BlueIceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<FireBlock>`
```
struct SharedCounter<FireBlock>
{
  FireBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChemistryTableBlock>`
```
struct SharedCounter<ChemistryTableBlock>
{
  ChemistryTableBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<UnderwaterTorchBlock>`
```
struct SharedCounter<UnderwaterTorchBlock>
{
  UnderwaterTorchBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ChemicalHeatBlock>`
```
struct SharedCounter<ChemicalHeatBlock>
{
  ChemicalHeatBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ColoredTorchBlock>`
```
struct SharedCounter<ColoredTorchBlock>
{
  ColoredTorchBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ElementBlock>`
```
struct SharedCounter<ElementBlock>
{
  ElementBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<Coral>`
```
struct SharedCounter<Coral>
{
  Coral *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CoralBlock>`
```
struct SharedCounter<CoralBlock>
{
  CoralBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CoralFan>`
```
struct SharedCounter<CoralFan>
{
  CoralFan *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CoralFanHang>`
```
struct SharedCounter<CoralFanHang>
{
  CoralFanHang *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<KelpBlock>`
```
struct SharedCounter<KelpBlock>
{
  KelpBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<DriedKelpBlock>`
```
struct SharedCounter<DriedKelpBlock>
{
  DriedKelpBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SeaGrass>`
```
struct SharedCounter<SeaGrass>
{
  SeaGrass *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SeaGrass`
```
struct __cppobj SeaGrass : BlockLegacy
{
};

```

### `SharedCounter<SeaPickle>`
```
struct SharedCounter<SeaPickle>
{
  SeaPickle *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SeaPickle`
```
struct __cppobj SeaPickle : BushBlock
{
};

```

### `SharedCounter<ConduitBlock>`
```
struct SharedCounter<ConduitBlock>
{
  ConduitBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BubbleColumnBlock>`
```
struct SharedCounter<BubbleColumnBlock>
{
  BubbleColumnBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<TurtleEggBlock>`
```
struct SharedCounter<TurtleEggBlock>
{
  TurtleEggBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BarrierBlock>`
```
struct SharedCounter<BarrierBlock>
{
  BarrierBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ScaffoldingBlock>`
```
struct SharedCounter<ScaffoldingBlock>
{
  ScaffoldingBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `ScaffoldingBlock`
```
struct __cppobj ScaffoldingBlock : HeavyBlock
{
};

```

### `SharedCounter<BambooBlock>`
```
struct SharedCounter<BambooBlock>
{
  BambooBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BambooSapling>`
```
struct SharedCounter<BambooSapling>
{
  BambooSapling *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<StoneSlabBlock3>`
```
struct SharedCounter<StoneSlabBlock3>
{
  StoneSlabBlock3 *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneSlabBlock3`
```
struct __cppobj StoneSlabBlock3 : SlabBlock
{
};

```

### `SharedCounter<StoneSlabBlock4>`
```
struct SharedCounter<StoneSlabBlock4>
{
  StoneSlabBlock4 *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `StoneSlabBlock4`
```
struct __cppobj StoneSlabBlock4 : SlabBlock
{
};

```

### `SharedCounter<LecternBlock>`
```
struct SharedCounter<LecternBlock>
{
  LecternBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<GrindstoneBlock>`
```
struct SharedCounter<GrindstoneBlock>
{
  GrindstoneBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BlastFurnaceBlock>`
```
struct SharedCounter<BlastFurnaceBlock>
{
  BlastFurnaceBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SmokerBlock>`
```
struct SharedCounter<SmokerBlock>
{
  SmokerBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SmokerBlock`
```
struct __cppobj __attribute__((aligned(8))) SmokerBlock : FurnaceBlock
{
};

```

### `SharedCounter<CartographyTableBlock>`
```
struct SharedCounter<CartographyTableBlock>
{
  CartographyTableBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BarrelBlock>`
```
struct SharedCounter<BarrelBlock>
{
  BarrelBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LoomBlock>`
```
struct SharedCounter<LoomBlock>
{
  LoomBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BellBlock>`
```
struct SharedCounter<BellBlock>
{
  BellBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<SweetBerryBushBlock>`
```
struct SharedCounter<SweetBerryBushBlock>
{
  SweetBerryBushBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SweetBerryBushBlock`
```
struct __cppobj SweetBerryBushBlock : BushBlock
{
};

```

### `SharedCounter<LanternBlock>`
```
struct SharedCounter<LanternBlock>
{
  LanternBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<CampfireBlock>`
```
struct SharedCounter<CampfireBlock>
{
  CampfireBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<JigsawBlock>`
```
struct SharedCounter<JigsawBlock>
{
  JigsawBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WoodBlock>`
```
struct SharedCounter<WoodBlock>
{
  WoodBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<ComposterBlock>`
```
struct SharedCounter<ComposterBlock>
{
  ComposterBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<LightBlock>`
```
struct SharedCounter<LightBlock>
{
  LightBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<WitherRoseBlock>`
```
struct SharedCounter<WitherRoseBlock>
{
  WitherRoseBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<BeehiveBlock>`
```
struct SharedCounter<BeehiveBlock>
{
  BeehiveBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HoneyBlock>`
```
struct SharedCounter<HoneyBlock>
{
  HoneyBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SharedCounter<HoneycombBlock>`
```
struct SharedCounter<HoneycombBlock>
{
  HoneycombBlock *ptr;
  std::atomic<int> share_count;
  std::atomic<int> weak_count;
};

```

### `SubtractiveLightInfo`
```
struct SubtractiveLightInfo
{
  SubtractiveLightInfo::$6B0E6A960ECE12370BB5BB4D4B3FBF4C _anon_0;
};

```

### `SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<1,SubChunkBlockStorage::Type::Paletted1>::PACKED_WORD mBlocks[128];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[2];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<2,SubChunkBlockStorage::Type::Paletted2>::PACKED_WORD mBlocks[256];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[4];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<3,SubChunkBlockStorage::Type::Paletted3>::PACKED_WORD mBlocks[410];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[8];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<4,SubChunkBlockStorage::Type::Paletted4>::PACKED_WORD mBlocks[512];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[16];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<5,SubChunkBlockStorage::Type::Paletted5>::PACKED_WORD mBlocks[683];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[32];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<6,SubChunkBlockStorage::Type::Paletted6>::PACKED_WORD mBlocks[820];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[64];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<8,SubChunkBlockStorage::Type::Paletted8>::PACKED_WORD mBlocks[1024];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[256];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>`
```
struct __cppobj __attribute__((aligned(8))) SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16> : ISubChunkBlockStoragePaletted
{
  SubChunkBlockStoragePaletted<16,SubChunkBlockStorage::Type::Paletted16>::PACKED_WORD mBlocks[2048];
  ISubChunkBlockStoragePaletted::PaletteEntry mPalette[4096];
  std::atomic<unsigned short> mPaletteSize;
};

```

### `static_vector<const Block *,4096>`
```
struct static_vector<const Block *,4096>
{
  std::aligned_storage<8,8>::type mArray[4096];
  size_t mSize;
};

```

### `SubtractiveLightInfo::$6B0E6A960ECE12370BB5BB4D4B3FBF4C::$8A8F0A98EC9223C9E9CC01AC2399BC8B`
```
struct __attribute__((aligned(4))) SubtractiveLightInfo::$6B0E6A960ECE12370BB5BB4D4B3FBF4C::$8A8F0A98EC9223C9E9CC01AC2399BC8B
{
  SubChunkLightIndex mCoordIndex;
  Brightness mOldBrightness;
};

```

### `SpikeFeature::EndSpike`
```
struct SpikeFeature::EndSpike
{
  const int mCenterX;
  const int mCenterZ;
  const int mRadius;
  const int mHeight;
  const bool mGuarded;
  const AABB mTopBoundingBox;
};

```

### `StackRefResultT<SharePtrRefTraits<PerlinSimplexNoise> >::StackRef`
```
typedef SharePtrRefTraits<PerlinSimplexNoise>::StackRef StackRefResultT<SharePtrRefTraits<PerlinSimplexNoise> >::StackRef;

```

### `StructureTemplateFeature::BoundingBox2D`
```
struct StructureTemplateFeature::BoundingBox2D
{
  Vec2 min;
  Vec2 max;
};

```

### `SwamplandHut`
```
struct __cppobj __attribute__((aligned(8))) SwamplandHut : ScatteredFeaturePiece
{
  bool mSpawnedWitch;
};

```

### `ScatteredFeatureStart`
```
struct __cppobj ScatteredFeatureStart : StructureStart
{
};

```

### `ScatteredFeaturePiece`
```
struct __cppobj ScatteredFeaturePiece : StructurePiece
{
  int mWidth;
  int mHeight;
  int mDepth;
  int mHeightPosition;
};

```

### `StructureFeature::findFarAwayStructures::StructureInfo`
```
struct StructureFeature::findFarAwayStructures::StructureInfo
{
  ChunkPos min;
  ChunkPos max;
  ChunkPos id;
};

```

### `StructureHelpers`
```
struct StructureHelpers
{
  __int8 gap0[1];
};

```

### `StructurePoolElement::LazyTemplate`
```
struct StructurePoolElement::LazyTemplate
{
  LegacyStructureTemplate *mStructure;
  std::vector<JigsawBlockInfo> mJigsawMarkers;
};

```

### `StructurePoolActorPredicateAlwaysTrue`
```
struct __cppobj StructurePoolActorPredicateAlwaysTrue : IStructurePoolActorPredicate
{
};

```

### `StructurePoolBlockPredicateStateMatch`
```
struct __cppobj StructurePoolBlockPredicateStateMatch : IStructurePoolBlockPredicate
{
  const Block *mBlock;
};

```

### `StructurePoolBlockPredicateStateMatchRandom`
```
struct __cppobj __attribute__((aligned(8))) StructurePoolBlockPredicateStateMatchRandom : IStructurePoolBlockPredicate
{
  const Block *mBlock;
  const float mProbability;
};

```

### `StructurePoolBlockTagPredicateAlwaysTrue`
```
struct __cppobj StructurePoolBlockTagPredicateAlwaysTrue : IStructurePoolBlockTagPredicate
{
};

```

### `StructurePoolBlockTagPredicateBlockTagMatch`
```
struct __cppobj StructurePoolBlockTagPredicateBlockTagMatch : IStructurePoolBlockTagPredicate
{
  const Block *mBlock;
  const CompoundTag *mTag;
};

```

### `SimplexNoisePtr`
```
typedef std::unique_ptr<SimplexNoise> SimplexNoisePtr;

```

### `SetDataFromColorIndexFunction`
```
struct __cppobj SetDataFromColorIndexFunction : LootItemFunction
{
};

```

### `SetBannerDetailsFunction`
```
struct __cppobj __attribute__((aligned(8))) SetBannerDetailsFunction : LootItemFunction
{
  BannerBlockType mBannerType;
};

```

### `SetBookContentsFunction`
```
struct __cppobj SetBookContentsFunction : LootItemFunction
{
  std::string mTitle;
  std::string mAuthor;
  std::vector<std::string> mPages;
};

```

### `SetItemCountFunction`
```
struct __cppobj SetItemCountFunction : LootItemFunction
{
  RandomValueBounds mValue;
};

```

### `SetItemDamageFunction`
```
struct __cppobj SetItemDamageFunction : LootItemFunction
{
  RandomValueBounds mDamage;
};

```

### `SetItemDataFunction`
```
struct __cppobj SetItemDataFunction : LootItemFunction
{
  RandomValueBounds mValue;
};

```

### `SetItemLoreFunction`
```
struct __cppobj SetItemLoreFunction : LootItemFunction
{
  std::vector<std::string> mLore;
};

```

### `SetItemNameFunction`
```
struct __cppobj SetItemNameFunction : LootItemFunction
{
  std::string mName;
};

```

### `SetSpawnEggFunction`
```
struct __cppobj SetSpawnEggFunction : LootItemFunction
{
  ActorDefinitionIdentifier mActor;
};

```

### `SmeltItemFunction`
```
struct __cppobj SmeltItemFunction : LootItemFunction
{
};

```

### `SpecificEnchantFunction`
```
struct __cppobj SpecificEnchantFunction : LootItemFunction
{
  std::vector<SpecificEnchantFunction::EnchantInfo> mEnchantments;
};

```

### `ServerScoreboard::setDisplayObjective::MapValue`
```
typedef std::unordered_map<std::string,DisplayObjective>::value_type ServerScoreboard::setDisplayObjective::MapValue;

```

### `SplashPotionEffectSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) SplashPotionEffectSubcomponent : OnHitSubcomponent
{
  int mPotionEffect;
};

```

### `ScaffoldingClimberDefinition`
```
struct ScaffoldingClimberDefinition
{
  __int8 gap0[1];
};

```

### `StackRefResultT<EntityRegistryRefTraits>::StackRef`
```
typedef EntityRegistryRefTraits::StackRef StackRefResultT<EntityRegistryRefTraits>::StackRef;

```

### `SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block`
```
struct SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block
{
  Lockless::WeakAtomic<unsigned long> front;
  size_t localTail;
  char cachelineFiller0[48];
  Lockless::WeakAtomic<unsigned long> tail;
  size_t localFront;
  char cachelineFiller1[48];
  Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> next;
  char *data;
  const size_t sizeMask;
  char *rawThis;
};

```

### `SPSCQueue<BatchedNetworkPeer::DataCallback,512>`
```
struct SPSCQueue<BatchedNetworkPeer::DataCallback,512>
{
  Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mFrontBlock;
  char mCachelineFiller[56];
  Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mTailBlock;
  size_t mLargestBlockSize;
};

```

### `StackedGraphBars::ColorKey`
```
struct StackedGraphBars::ColorKey
{
  char colorTag;
  std::string name;
};

```

### `StackedGraphBars::Bar`
```
typedef std::array<float,2> StackedGraphBars::Bar;

```

### `ScriptBinderActorTemplate`
```
struct __cppobj ScriptBinderActorTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderBlockTemplate`
```
struct __cppobj ScriptBinderBlockTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderComponentTemplate`
```
struct __cppobj ScriptBinderComponentTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderItemActorTemplate`
```
struct __cppobj ScriptBinderItemActorTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderLevelTemplate`
```
struct __cppobj ScriptBinderLevelTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderPureEcsTemplate`
```
struct __cppobj ScriptBinderPureEcsTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderQueryTemplate`
```
struct __cppobj ScriptBinderQueryTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderActorTickingAreaTemplate`
```
struct __cppobj ScriptBinderActorTickingAreaTemplate : ScriptBinderTemplate
{
};

```

### `ScriptBinderLevelTickingAreaTemplate`
```
struct __cppobj ScriptBinderLevelTickingAreaTemplate : ScriptBinderTemplate
{
};

```

### `ScriptEventDataBinderComponent`
```
struct __cppobj __attribute__((aligned(8))) ScriptEventDataBinderComponent : ScriptBinderComponent
{
  ScriptApi::ScriptObjectHandle mData;
};

```

### `ScriptBinderEventDataTemplate`
```
struct __cppobj ScriptBinderEventDataTemplate : ScriptBinderTemplate
{
};

```

### `ScriptItemStackBinderComponent`
```
struct __cppobj ScriptItemStackBinderComponent : ScriptBinderComponent
{
  uint32_t mEcsId;
  int32_t mCount;
  std::string mItemIdentifier;
};

```

### `ScriptBinderItemStackTemplate`
```
struct __cppobj ScriptBinderItemStackTemplate : ScriptBinderTemplate
{
};

```

### `ServerCommand:240`
```
struct __cppobj ServerCommand:240 : Command:240
{
};

```

### `SayCommand`
```
struct __cppobj SayCommand : MessagingCommand
{
  CommandMessage mMessage;
};

```

### `ScoreboardCommand`
```
struct __cppobj __attribute__((aligned(8))) ScoreboardCommand : Command
{
  ScoreboardCommand::Category mCategory;
  ScoreboardCommand::Action mAction;
  std::string mObjective;
  std::string mSourceObjective;
  ObjectiveSortOrder mOrder;
  std::string mCriteria;
  std::string mName;
  std::string mDisplayName;
  WildcardActorSelector mTargets;
  WildcardActorSelector mSources;
  CommandOperator_0 mOperator;
  CommandWildcardInt mMin;
  CommandWildcardInt mMax;
  int mRandMin;
  int mRandMax;
  int mValue;
  bool mTargetsSet;
};

```

### `SetBlockCommand`
```
struct __cppobj SetBlockCommand : Command
{
  CommandPosition mPosition;
  const Block *mBlock;
  int mData;
  SetBlockCommand::SetBlockMode mMode;
};

```

### `SetMaxPlayersCommand`
```
struct __cppobj __attribute__((aligned(8))) SetMaxPlayersCommand : ServerCommand
{
  int mMaxPlayers;
};

```

### `SetWorldSpawnCommand`
```
struct __cppobj __attribute__((aligned(8))) SetWorldSpawnCommand : Command
{
  CommandPositionFloat mSpawnPoint;
  bool mSpawnPointSet;
};

```

### `SpawnPointCommand`
```
struct __cppobj __attribute__((aligned(8))) SpawnPointCommand : Command
{
  PlayerSelector mTargets;
  CommandPositionFloat mSpawnPos;
  bool mSpawnPosSet;
};

```

### `SpreadPlayersCommand`
```
struct __cppobj SpreadPlayersCommand : Command
{
  ActorSelector mTargets;
  RelativeFloat mX;
  RelativeFloat mZ;
  float mDistance;
  float mMaxRange;
};

```

### `StopSoundCommand`
```
struct __cppobj StopSoundCommand : Command
{
  PlayerSelector mTargets;
  std::string mSound;
};

```

### `SummonCommand`
```
struct __cppobj __attribute__((aligned(8))) SummonCommand : Command
{
  const ActorDefinitionIdentifier *mActorId;
  CommandPositionFloat mPosition;
  std::string mEventName;
  std::string mActorName;
  bool mNameSet;
};

```

### `SequenceDefinition`
```
struct __cppobj SequenceDefinition : CompositeDefinition
{
};

```

### `SequenceBehaviorNode`
```
struct __cppobj SequenceBehaviorNode : BehaviorNode
{
  Unique<BehaviorNode> mActiveChild;
  size_t mCurrentIndex;
};

```

### `SelectorDefinition`
```
struct __cppobj SelectorDefinition : CompositeDefinition
{
};

```

### `SelectorBehaviorNode`
```
struct __cppobj SelectorBehaviorNode : BehaviorNode
{
  Unique<BehaviorNode> mActiveChild;
  size_t mCurrentIndex;
};

```

### `SubtreeDefinition`
```
struct __cppobj SubtreeDefinition : BehaviorDefinition
{
  std::string mSubtreeId;
  std::vector<std::pair<std::string,std::string >> mBehaviorDataItems;
};

```

### `SubtreeNode`
```
struct __cppobj SubtreeNode : BehaviorNode
{
  BehaviorTreeDefinitionPtr mSubtreePtr;
  Unique<BehaviorNode> mSubtreeHead;
  BehaviorData mSubtreeData;
};

```

### `ShootBowDefinition`
```
struct __cppobj ShootBowDefinition : BehaviorDefinition
{
  int mNumOfShots;
  std::string mNumOfShotsId;
};

```

### `ShootBowNode`
```
struct __cppobj __attribute__((aligned(8))) ShootBowNode : BehaviorNode:480
{
  int mNumTimesToShoot;
  int mNumTimesShot;
  int mTicksLeftToShoot;
  bool mDone;
};

```

### `SpawnGroupRegistry::SpawnGroupRegistryMap`
```
typedef std::vector<std::unique_ptr<SpawnGroupData>> SpawnGroupRegistry::SpawnGroupRegistryMap;

```

### `SpawnGroupRegistry::SpawnGroupLookupMap`
```
typedef std::unordered_map<std::string,SpawnGroupData *> SpawnGroupRegistry::SpawnGroupLookupMap;

```

### `ShulkerBoxContainerController`
```
struct __cppobj ShulkerBoxContainerController : ContainerController
{
};

```

### `Shared<BlockActor>`
```
typedef std::shared_ptr<BlockActor> Shared<BlockActor>;

```

### `SlabBlock`
```
struct __cppobj SlabBlock : BlockLegacy
{
  SlabBlock::SlabType mSlabType;
  bool fullSize;
  WeakPtr<BlockLegacy> mBaseSlab;
};

```

### `StructureIntegrityProcessor_0`
```
struct StructureIntegrityProcessor_0
{
  float mIntegrity;
  RandomSeed_0 mStartSeed;
};

```

### `SnapshotEnv`
```
struct __cppobj SnapshotEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  Bedrock::Threading::Mutex mCreationLock;
  SharedMutex mWriteLock;
  Bedrock::Threading::Mutex mOpenReadFileLock;
  Bedrock::Threading::Mutex mPauseLock;
  std::atomic<bool> mPaused;
  std::vector<SnapshotEnv::DeleteFileEntry> mQueuedActions;
  Bedrock::Threading::Mutex mQueueMutex;
};

```

### `SmallSet<DBChunkStorage *>`
```
struct SmallSet<DBChunkStorage *>
{
  std::vector<DBChunkStorage *> c;
};

```

### `SmallSet<DBChunkStorage *>::const_iterator`
```
typedef std::vector<DBChunkStorage *>::const_iterator SmallSet<DBChunkStorage *>::const_iterator;

```

### `SmallSet<DBChunkStorage *>::iterator`
```
typedef std::vector<DBChunkStorage *>::iterator SmallSet<DBChunkStorage *>::iterator;

```

### `SnapshotWritableFile`
```
struct __cppobj SnapshotWritableFile : leveldb::WritableFile
{
  gsl::owner<leveldb::WritableFile *> mLeveldbWritableFile;
  SharedMutex *mCreationAndWriteLock;
};

```

### `Shared<LevelChunk>`
```
typedef std::shared_ptr<LevelChunk> Shared<LevelChunk>;

```

### `ScriptCommandFactory`
```
struct ScriptCommandFactory
{
  __int8 gap0[1];
};

```

### `SecureStorage`
```
struct SecureStorage
{
  int (**_vptr$SecureStorage)(void);
};

```

### `Social::XboxLiveSignInHandler`
```
struct __cppobj Social::XboxLiveSignInHandler : std::enable_shared_from_this<Social::XboxLiveSignInHandler>
{
  int (**_vptr$XboxLiveSignInHandler)(void);
};

```

### `StringVector`
```
typedef std::vector<std::string> StringVector;

```

### `SecureStorageKey`
```
struct __attribute__((aligned(8))) SecureStorageKey
{
  std::string key;
  bool isEncoded;
};

```

### `ServiceLocator<Core::LoadTimeProfiler>`
```
struct ServiceLocator<Core::LoadTimeProfiler>
{
  __int8 gap0[1];
};

```

### `Scheduler::ScopedChangeScheduler`
```
struct Scheduler::ScopedChangeScheduler
{
  BackgroundWorker *mParent;
};

```

### `SmallSet<WorkerPool *>::const_iterator`
```
typedef std::vector<WorkerPool *>::const_iterator SmallSet<WorkerPool *>::const_iterator;

```

### `SmallSet<WorkerPool *>::iterator`
```
typedef std::vector<WorkerPool *>::iterator SmallSet<WorkerPool *>::iterator;

```

### `StopwatchNLast`
```
struct __cppobj StopwatchNLast : Stopwatch
{
  int n;
  int k;
  std::vector<double> t;
  double sum;
  Stopwatch sw;
};

```

### `StopwatchHandler`
```
struct __attribute__((aligned(8))) StopwatchHandler
{
  StopwatchHandler::Map _map;
  int _printcounter;
};

```

### `StopwatchHandler::Map`
```
typedef std::map<std::string,std::unique_ptr<Stopwatch>> StopwatchHandler::Map;

```

### `ScriptApi::EmptyScriptInterface`
```
struct __cppobj ScriptApi::EmptyScriptInterface : ScriptApi::ScriptLanguageInterface
{
};

```

