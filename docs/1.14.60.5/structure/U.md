# U
### `Unique<AppPlatform_linux>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<AppPlatform_linux,std::default_delete<AppPlatform_linux> >` | _M_t


### `Unique<Automation::AutomationClient>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Automation::AutomationClient,std::default_delete<Automation::AutomationClient> >` | _M_t


### `utsname`
Offset | Type | Name
-|-|-|-
0 | (65) `char[65]` | sysname
65 | (65) `char[65]` | nodename
130 | (65) `char[65]` | release
195 | (65) `char[65]` | version
260 | (65) `char[65]` | machine
325 | (65) `char[65]` | domainname


### `Unique<CompoundTag>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<CompoundTag,std::default_delete<CompoundTag> >` | _M_t


### `Unique<ItemInstance>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ItemInstance,std::default_delete<ItemInstance> >` | _M_t


### `UniqueLock`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_lock<std::shared_timed_mutex>::mutex_type *` | _M_device
8 | (1) `bool` | _M_owns


### `Unique<UnverifiedCertificate>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<UnverifiedCertificate,std::default_delete<UnverifiedCertificate> >` | _M_t


### `Unique<Certificate>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Certificate,std::default_delete<Certificate> >` | _M_t


### `UnverifiedCertificate`
Offset | Type | Name
-|-|-|-
0 | (128) `const WebToken` | mRawToken
128 | (8) `Unique<UnverifiedCertificate>` | mParentUnverifiedCertificate


### `Unique<Crypto::Asymmetric::Asymmetric>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Crypto::Asymmetric::Asymmetric,std::default_delete<Crypto::Asymmetric::Asymmetric> >` | _M_t


### `Unique<AgentCommands::Command>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<AgentCommands::Command,std::default_delete<AgentCommands::Command> >` | _M_t


### `Unique<BehaviorNode>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BehaviorNode,std::default_delete<BehaviorNode> >` | _M_t


### `Unique<DanceComponentListener>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<DanceComponentListener,std::default_delete<DanceComponentListener> >` | _M_t


### `Unique<JumpControl>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<JumpControl,std::default_delete<JumpControl> >` | _M_t


### `Unique<LookControl>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LookControl,std::default_delete<LookControl> >` | _M_t


### `Unique<PathNavigation>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<PathNavigation,std::default_delete<PathNavigation> >` | _M_t


### `Unique<Path>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Path,std::default_delete<Path> >` | _M_t


### `Unique<Tag>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Tag,std::default_delete<Tag> >` | _M_t


### `UpdateBlockPropertiesPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `Unique<CompoundTag>` | mBlockProperties


### `UpdateAttributesPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (24) `std::vector<UpdateAttributesPacket::AttributeData>` | mAttributeData


### `Unique<Recipe>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Recipe,std::default_delete<Recipe> >` | _M_t


### `Util::HashString`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mText
32 | (8) `uint64_t` | mHash


### `Unique<CommandContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<CommandContext,std::default_delete<CommandContext> >` | _M_t


### `Unique<WebToken>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<WebToken,std::default_delete<WebToken> >` | _M_t


### `UPNPInterface::UPNPCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (UPNPResult)>::_Invoker_type` | _M_invoker


### `UPNPResult`
Offset | Type | Name
-|-|-|-
0 | (257) `UPNPExternalIPResult` | externalIP
1 | (262) `UPNPPortMappingResult` | portMapping


### `UPNPExternalIPResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | bUPNPSupported
1 | (256) `char[256]` | hostIPAddress


### `UPNPPortMappingResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | bUPNPSupported
1 | (256) `char[256]` | hostIPAddress
258 | (2) `unsigned __int16` | externalPort
260 | (2) `unsigned __int16` | internalPort


### `UPNPInterface::UPNPNotification`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void ()>::_Invoker_type` | _M_invoker


### `Unique<ListTag>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ListTag,std::default_delete<ListTag> >` | _M_t


### `Unique<CommandOrigin>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<CommandOrigin,std::default_delete<CommandOrigin> >` | _M_t


### `Unique<ComplexInventoryTransaction>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ComplexInventoryTransaction,std::default_delete<ComplexInventoryTransaction> >` | _M_t


### `UpdateAttributesPacket::AttributeData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mCurrentValue
4 | (4) `float` | mMinValue
8 | (4) `float` | mMaxValue
12 | (4) `float` | mDefaultValue
16 | (40) `HashedString` | mName


### `Unique<BlockComponentFactory>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BlockComponentFactory,std::default_delete<BlockComponentFactory> >` | _M_t


### `Unique<BlockDefinitionGroup>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BlockDefinitionGroup,std::default_delete<BlockDefinitionGroup> >` | _M_t


### `UpdateEquipPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mContainerId
37 | (1) `ContainerType` | mType
40 | (4) `int` | mSize
48 | (8) `ActorUniqueID` | mEntityUniqueID
56 | (56) `CompoundTag` | mData


### `UpdateTradePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mContainerId
37 | (1) `ContainerType` | mType
40 | (32) `std::string` | mDisplayName
72 | (4) `int` | mSize
76 | (4) `int` | mTraderTier
80 | (8) `ActorUniqueID` | mEntityUniqueID
88 | (8) `ActorUniqueID` | mLastTradingPlayer
96 | (56) `CompoundTag` | mData
152 | (1) `bool` | mUseNewTradeScreen
153 | (1) `bool` | mUsingEconomyTrade


### `Unique<ChangeDimensionRequest>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ChangeDimensionRequest,std::default_delete<ChangeDimensionRequest> >` | _M_t


### `Unique<Actor>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Actor,std::default_delete<Actor> >` | _M_t


### `Util::isValidIP::$012BCF0047B80F8DCFFA921910E94D35`
Offset | Type | Name
-|-|-|-
0 | (32) `int[8]` | ipv6
1 | (16) `int[4]` | ipv4


### `Util::isValidIP::$A5E8C83C2C9C7045BF6C6CE6AD4B8468`
Offset | Type | Name
-|-|-|-
0 | (5) `char[5]` | ipv6
1 | (4) `char[4]` | ipv4


### `Unique<Level>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Level,std::default_delete<Level> >` | _M_t


### `Unique<NetEventCallback>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<NetEventCallback,std::default_delete<NetEventCallback> >` | _M_t


### `Unique<Container>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Container,std::default_delete<Container> >` | _M_t


### `Unique<ActorDefinitionDescriptor>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ActorDefinitionDescriptor,std::default_delete<ActorDefinitionDescriptor> >` | _M_t


### `Unique<ActorDefinition>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ActorDefinition,std::default_delete<ActorDefinition> >` | _M_t


### `Unique<Goal>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Goal,std::default_delete<Goal> >` | _M_t


### `Unique<BehaviorTreeDefinition>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BehaviorTreeDefinition,std::default_delete<BehaviorTreeDefinition> >` | _M_t


### `Unique<BehaviorDefinition>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BehaviorDefinition,std::default_delete<BehaviorDefinition> >` | _M_t


### `Unique<LavaSlime>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LavaSlime,std::default_delete<LavaSlime> >` | _M_t


### `Unique<FillingContainer>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<FillingContainer,std::default_delete<FillingContainer> >` | _M_t


### `Unique<Inventory>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Inventory,std::default_delete<Inventory> >` | _M_t


### `Unique<OnHitSubcomponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<OnHitSubcomponent,std::default_delete<OnHitSubcomponent> >` | _M_t


### `UpdateBlockPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos
48 | (4) `uint32_t` | mLayer
52 | (1) `byte` | mUpdateFlags
56 | (4) `BlockRuntimeId` | mRuntimeId


### `Unique<TradeTable>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<TradeTable,std::default_delete<TradeTable> >` | _M_t


### `Unique<LootItemFunction>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootItemFunction,std::default_delete<LootItemFunction> >` | _M_t


### `Unique<LevelStorage>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LevelStorage,std::default_delete<LevelStorage> >` | _M_t


### `Unique<Player>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Player,std::default_delete<Player> >` | _M_t


### `Unique<ChalkboardBlockActor>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ChalkboardBlockActor,std::default_delete<ChalkboardBlockActor> >` | _M_t


### `Unique<BlockComponentDescription>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BlockComponentDescription,std::default_delete<BlockComponentDescription> >` | _M_t


### `Unique<ChunkSource>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ChunkSource,std::default_delete<ChunkSource> >` | _M_t


### `Unique<ChunkViewSource>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ChunkViewSource,std::default_delete<ChunkViewSource> >` | _M_t


### `Unique<LegacyStructureTemplate>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LegacyStructureTemplate,std::default_delete<LegacyStructureTemplate> >` | _M_t


### `Unique<GameRulesChangedPacket>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<GameRulesChangedPacket,std::default_delete<GameRulesChangedPacket> >` | _M_t


### `Unique<Objective>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<Objective,std::default_delete<Objective> >` | _M_t


### `Unique<ObjectiveCriteria>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ObjectiveCriteria,std::default_delete<ObjectiveCriteria> >` | _M_t


### `Unique<CommandArea>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<CommandArea,std::default_delete<CommandArea> >` | _M_t


### `Unique<SpawnGroupData>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<SpawnGroupData,std::default_delete<SpawnGroupData> >` | _M_t


### `Unique<BlockPatternBuilder>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BlockPatternBuilder,std::default_delete<BlockPatternBuilder> >` | _M_t


### `Unique<BedBlockActor>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BedBlockActor,std::default_delete<BedBlockActor> >` | _M_t


### `Unique<LootPoolTiers>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootPoolTiers,std::default_delete<LootPoolTiers> >` | _M_t


### `Unique<LootPoolEntry>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootPoolEntry,std::default_delete<LootPoolEntry> >` | _M_t


### `Unique<LootTable>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootTable,std::default_delete<LootTable> >` | _M_t


### `Unique<EnchantBookForTradingFunction>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<EnchantBookForTradingFunction,std::default_delete<EnchantBookForTradingFunction> >` | _M_t


### `Unique<ExplorationMapFunction>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ExplorationMapFunction,std::default_delete<ExplorationMapFunction> >` | _M_t


### `Unique<BehaviorData::DataProxy>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BehaviorData::DataProxy,std::default_delete<BehaviorData::DataProxy> >` | _M_t


### `Unique<LootItemCondition>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootItemCondition,std::default_delete<LootItemCondition> >` | _M_t


### `unz_file_info`
Offset | Type | Name
-|-|-|-
0 | (8) `uLong` | version
8 | (8) `uLong` | version_needed
16 | (8) `uLong` | flag
24 | (8) `uLong` | compression_method
32 | (8) `uLong` | dosDate
40 | (8) `uLong` | crc
48 | (8) `uLong` | compressed_size
56 | (8) `uLong` | uncompressed_size
64 | (8) `uLong` | size_filename
72 | (8) `uLong` | size_file_extra
80 | (8) `uLong` | size_file_comment
88 | (8) `uLong` | disk_num_start
96 | (8) `uLong` | internal_fa
104 | (8) `uLong` | external_fa
112 | (24) `tm_unz` | tmu_date


### `unz_global_info64`
Offset | Type | Name
-|-|-|-
0 | (8) `ZPOS64_T` | number_entry
8 | (8) `uLong` | size_comment


### `unz_global_info`
Offset | Type | Name
-|-|-|-
0 | (8) `uLong` | number_entry
8 | (8) `uLong` | size_comment


### `utimbuf`
Offset | Type | Name
-|-|-|-
0 | (8) `__time_t` | actime
8 | (8) `__time_t` | modtime


### `Util::swapEndian<int>::$11F1BAB51A7F6778145096AE6C662BB5`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | u
1 | (4) `unsigned __int8[4]` | u8


### `Util::compareNoCase::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Util::toLower::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Util::toUpper::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Util::toLowerInPlace::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Util::toUpperInPlace::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `unz64_s`
Offset | Type | Name
-|-|-|-
0 | (88) `zlib_filefunc64_32_def` | z_filefunc
88 | (4) `int` | is64bitOpenFunction
96 | (8) `voidpf` | filestream
104 | (16) `unz_global_info64` | gi
120 | (8) `ZPOS64_T` | byte_before_the_zipfile
128 | (8) `ZPOS64_T` | num_file
136 | (8) `ZPOS64_T` | pos_in_central_dir
144 | (8) `ZPOS64_T` | current_file_ok
152 | (8) `ZPOS64_T` | central_pos
160 | (8) `ZPOS64_T` | size_central_dir
168 | (8) `ZPOS64_T` | offset_central_dir
176 | (136) `unz_file_info64` | cur_file_info
312 | (8) `unz_file_info64_internal` | cur_file_info_internal
320 | (8) `file_in_zip64_read_info_s *` | pfile_in_zip_read
328 | (4) `int` | encrypted
332 | (4) `int` | isZip64


### `unz_file_info64`
Offset | Type | Name
-|-|-|-
0 | (8) `uLong` | version
8 | (8) `uLong` | version_needed
16 | (8) `uLong` | flag
24 | (8) `uLong` | compression_method
32 | (8) `uLong` | dosDate
40 | (8) `uLong` | crc
48 | (8) `ZPOS64_T` | compressed_size
56 | (8) `ZPOS64_T` | uncompressed_size
64 | (8) `uLong` | size_filename
72 | (8) `uLong` | size_file_extra
80 | (8) `uLong` | size_file_comment
88 | (8) `uLong` | disk_num_start
96 | (8) `uLong` | internal_fa
104 | (8) `uLong` | external_fa
112 | (24) `tm_unz` | tmu_date


### `unz_file_info64_internal`
Offset | Type | Name
-|-|-|-
0 | (8) `ZPOS64_T` | offset_curfile


### `unz64_file_pos`
Offset | Type | Name
-|-|-|-
0 | (8) `ZPOS64_T` | pos_in_zip_directory
8 | (8) `ZPOS64_T` | num_of_file


### `ucontext_t_0`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | uc_flags
8 | (8) `ucontext_t *` | uc_link
16 | (24) `stack_t` | uc_stack
40 | (256) `mcontext_t` | uc_mcontext
296 | (128) `sigset_t` | uc_sigmask
424 | (512) `_libc_fpstate` | __fpregs_mem


### `uint128_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | high
8 | (8) `uint64_t` | low


### `user_regs_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | _r15
8 | (8) `unsigned __int64` | _r14
16 | (8) `unsigned __int64` | _r13
24 | (8) `unsigned __int64` | _r12
32 | (8) `unsigned __int64` | _rbp
40 | (8) `unsigned __int64` | _rbx
48 | (8) `unsigned __int64` | _r11
56 | (8) `unsigned __int64` | _r10
64 | (8) `unsigned __int64` | _r9
72 | (8) `unsigned __int64` | _r8
80 | (8) `unsigned __int64` | _rax
88 | (8) `unsigned __int64` | _rcx
96 | (8) `unsigned __int64` | _rdx
104 | (8) `unsigned __int64` | _rsi
112 | (8) `unsigned __int64` | _rdi
120 | (8) `unsigned __int64` | orig_rax
128 | (8) `unsigned __int64` | _rip
136 | (8) `unsigned __int64` | _cs
144 | (8) `unsigned __int64` | eflags
152 | (8) `unsigned __int64` | _rsp
160 | (8) `unsigned __int64` | _ss
168 | (8) `unsigned __int64` | fs_base
176 | (8) `unsigned __int64` | gs_base
184 | (8) `unsigned __int64` | _ds
192 | (8) `unsigned __int64` | _es
200 | (8) `unsigned __int64` | _fs
208 | (8) `unsigned __int64` | _gs


### `user_fpregs_struct`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | cwd
2 | (2) `unsigned __int16` | swd
4 | (2) `unsigned __int16` | ftw
6 | (2) `unsigned __int16` | fop
8 | (8) `unsigned __int64` | _rip
16 | (8) `unsigned __int64` | rdp
24 | (4) `unsigned int` | _mxcsr
28 | (4) `unsigned int` | mxcr_mask
32 | (128) `unsigned int[32]` | st_space
160 | (256) `unsigned int[64]` | xmm_space
416 | (96) `unsigned int[24]` | padding


### `Unique<MobEffect>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<MobEffect,std::default_delete<MobEffect> >` | _M_t


### `Unique<BlockGraphics>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<BlockGraphics,std::default_delete<BlockGraphics> >` | _M_t


### `utf8proc_property_t`
Offset | Type | Name
-|-|-|-
0 | (2) `utf8proc_propval_t` | category
2 | (2) `utf8proc_propval_t` | combining_class
4 | (2) `utf8proc_propval_t` | bidi_class
6 | (2) `utf8proc_propval_t` | decomp_type
8 | (8) `const int32_t *` | decomp_mapping
16 | (1) `__int8` | _bf_10
20 | (4) `int32_t` | uppercase_mapping
24 | (4) `int32_t` | lowercase_mapping
28 | (4) `int32_t` | titlecase_mapping
32 | (4) `int32_t` | comb1st_index
36 | (4) `int32_t` | comb2nd_index
40 | (1) `__int8` | _bf_28
48 | (8) `const int32_t *` | casefold_mapping


### `Unique<StructureTemplatePool>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<StructureTemplatePool,std::default_delete<StructureTemplatePool> >` | _M_t


### `Unique<CircuitSystem>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<CircuitSystem,std::default_delete<CircuitSystem> >` | _M_t


### `Unique<TickingAreaList>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<TickingAreaList,std::default_delete<TickingAreaList> >` | _M_t


### `Unique<VillageManager>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<VillageManager,std::default_delete<VillageManager> >` | _M_t


### `Unique<PerlinSimplexNoise>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<PerlinSimplexNoise,std::default_delete<PerlinSimplexNoise> >` | _M_t


### `UniqueRakPeer`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__uniq_ptr_impl<RakNet::RakPeerInterface,void (*)(RakNet::RakPeerInterface *)>` | _M_t


### `Unique<RakNetInstance>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<RakNetInstance,std::default_delete<RakNetInstance> >` | _M_t


### `Unique<LocalConnector>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LocalConnector,std::default_delete<LocalConnector> >` | _M_t


### `Unique<RakNetServerLocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<RakNetServerLocator,std::default_delete<RakNetServerLocator> >` | _M_t


### `Unique<UPNPInterface>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<UPNPInterface,std::default_delete<UPNPInterface> >` | _M_t


### `Unique<NetworkHandler::IncomingPacketQueue>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<NetworkHandler::IncomingPacketQueue,std::default_delete<NetworkHandler::IncomingPacketQueue> >` | _M_t


### `Unique<ShapedRecipe>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ShapedRecipe,std::default_delete<ShapedRecipe> >` | _M_t


### `Unique<ShapelessRecipe>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ShapelessRecipe,std::default_delete<ShapelessRecipe> >` | _M_t


### `Unique<MultiRecipe>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<MultiRecipe,std::default_delete<MultiRecipe> >` | _M_t


### `Unique<LootComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<LootComponent,std::default_delete<LootComponent> >` | _M_t


### `UpdateAttributesPacket::AttributeData::AttributeData::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `UpdateBlockPropertiesPacket::UpdateBlockPropertiesPacket::$5D452180F6FD32FDE19EF7DE5EC88D21`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<CompoundTag> *` | defTag


### `UpdateSoftEnumPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mEnumName
72 | (24) `std::vector<std::string>` | mValues
96 | (1) `SoftEnumUpdateType` | mType


### `UriListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$UriListener


### `Unique<MoveControl>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<MoveControl,std::default_delete<MoveControl> >` | _M_t


### `Unique<SpawnData>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<SpawnData,std::default_delete<SpawnData> >` | _M_t


### `UpdateBlockSyncedPacket`
Offset | Type | Name
-|-|-|-
0 | (64) `UpdateBlockPacket` | baseclass_0
64 | (16) `ActorBlockSyncMessage` | mEntityBlockSyncMessage


### `Unique<ITickingArea>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__uniq_ptr_impl<ITickingArea,std::default_delete<ITickingArea> >` | _M_t


### `UnderwaterTorchBlock::animateTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Unique<CommandOutputSender>`
```
typedef std::unique_ptr<CommandOutputSender> Unique<CommandOutputSender>;

```

### `Unique<CommandRegistry>`
```
typedef std::unique_ptr<CommandRegistry> Unique<CommandRegistry>;

```

### `Unique<PlayerInteractionSystem>`
```
typedef std::unique_ptr<PlayerInteractionSystem> Unique<PlayerInteractionSystem>;

```

### `Unique<StructurePiece>`
```
typedef std::unique_ptr<StructurePiece> Unique<StructurePiece>;

```

### `Unique<IntArrayTag>`
```
typedef std::unique_ptr<IntArrayTag> Unique<IntArrayTag>;

```

### `Unique<StrongholdPiece>`
```
typedef std::unique_ptr<StrongholdPiece> Unique<StrongholdPiece>;

```

### `Unique<StructurePoolBlockRuleList>`
```
typedef std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockRule>>> Unique<StructurePoolBlockRuleList>;

```

### `Unique<StructurePoolBlockTagRuleList>`
```
typedef std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockTagRule>>> Unique<StructurePoolBlockTagRuleList>;

```

### `Unique<StructurePoolActorRuleList>`
```
typedef std::unique_ptr<std::vector<std::unique_ptr<StructurePoolActorRule>>> Unique<StructurePoolActorRuleList>;

```

### `Unique<StructurePoolElement>`
```
typedef std::unique_ptr<StructurePoolElement> Unique<StructurePoolElement>;

```

### `Unique<InventoryTransaction>`
```
typedef std::unique_ptr<InventoryTransaction> Unique<InventoryTransaction>;

```

### `UniqueChunkPointer`
```
typedef std::unique_ptr<LevelChunk,LevelChunkPhase1Deleter> UniqueChunkPointer;

```

### `Unique<IStructurePoolActorPredicate>`
```
typedef std::unique_ptr<IStructurePoolActorPredicate> Unique<IStructurePoolActorPredicate>;

```

### `Unique<IStructurePoolBlockPredicate>`
```
typedef std::unique_ptr<IStructurePoolBlockPredicate> Unique<IStructurePoolBlockPredicate>;

```

### `Unique<IStructurePoolBlockTagPredicate>`
```
typedef std::unique_ptr<IStructurePoolBlockTagPredicate> Unique<IStructurePoolBlockTagPredicate>;

```

### `UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>`
```
typedef MixerLayer<LayerValues::Terrain,LayerValues::Terrain> UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>;

```

### `UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>:328 : Layer<LayerValues::Terrain>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddIsland::OutputType,typename AddIsland::InputType>`
```
typedef MixerLayer<LayerValues::Terrain,LayerValues::Terrain> UnaryLayer<typename AddIsland::OutputType,typename AddIsland::InputType>;

```

### `UnaryLayer<typename AddIsland::OutputType,typename AddIsland::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddIsland::OutputType,typename AddIsland::InputType>:328 : Layer<LayerValues::Terrain>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename RemoveTooMuchOcean::OutputType,typename RemoveTooMuchOcean::InputType>`
```
typedef MixerLayer<LayerValues::Terrain,LayerValues::Terrain> UnaryLayer<typename RemoveTooMuchOcean::OutputType,typename RemoveTooMuchOcean::InputType>;

```

### `UnaryLayer<typename RemoveTooMuchOcean::OutputType,typename RemoveTooMuchOcean::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename RemoveTooMuchOcean::OutputType,typename RemoveTooMuchOcean::InputType>:328 : Layer<LayerValues::Terrain>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddSnow::OutputType,typename AddSnow::InputType>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::Terrain> UnaryLayer<typename AddSnow::OutputType,typename AddSnow::InputType>;

```

### `UnaryLayer<typename AddSnow::OutputType,typename AddSnow::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddSnow::OutputType,typename AddSnow::InputType>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::Terrain> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddIslandWithTemperature::OutputType,typename AddIslandWithTemperature::InputType>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> UnaryLayer<typename AddIslandWithTemperature::OutputType,typename AddIslandWithTemperature::InputType>;

```

### `UnaryLayer<typename AddIslandWithTemperature::OutputType,typename AddIslandWithTemperature::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddIslandWithTemperature::OutputType,typename AddIslandWithTemperature::InputType>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddEdgeCoolWarm::OutputType,typename AddEdgeCoolWarm::InputType>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> UnaryLayer<typename AddEdgeCoolWarm::OutputType,typename AddEdgeCoolWarm::InputType>;

```

### `UnaryLayer<typename AddEdgeCoolWarm::OutputType,typename AddEdgeCoolWarm::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddEdgeCoolWarm::OutputType,typename AddEdgeCoolWarm::InputType>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddEdgeHeatIce::OutputType,typename AddEdgeHeatIce::InputType>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> UnaryLayer<typename AddEdgeHeatIce::OutputType,typename AddEdgeHeatIce::InputType>;

```

### `UnaryLayer<typename AddEdgeHeatIce::OutputType,typename AddEdgeHeatIce::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddEdgeHeatIce::OutputType,typename AddEdgeHeatIce::InputType>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddEdgeSpecial::OutputType,typename AddEdgeSpecial::InputType>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> UnaryLayer<typename AddEdgeSpecial::OutputType,typename AddEdgeSpecial::InputType>;

```

### `UnaryLayer<typename AddEdgeSpecial::OutputType,typename AddEdgeSpecial::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddEdgeSpecial::OutputType,typename AddEdgeSpecial::InputType>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<LayerValues::PreBiome,LayerValues::PreBiome>`
```
typedef MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> UnaryLayer<LayerValues::PreBiome,LayerValues::PreBiome>;

```

### `UnaryLayer<LayerValues::PreBiome,LayerValues::PreBiome>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<LayerValues::PreBiome,LayerValues::PreBiome>:328 : Layer<LayerValues::PreBiome>
{
  LayerPtr<LayerValues::PreBiome> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename BiomeInit::OutputType,typename BiomeInit::InputType>`
```
typedef MixerLayer<Biome *,LayerValues::PreBiome> UnaryLayer<typename BiomeInit::OutputType,typename BiomeInit::InputType>;

```

### `UnaryLayer<typename AddMushroomIsland::OutputType,typename AddMushroomIsland::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename AddMushroomIsland::OutputType,typename AddMushroomIsland::InputType>;

```

### `UnaryLayer<typename PromoteCenter::OutputType,typename PromoteCenter::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename PromoteCenter::OutputType,typename PromoteCenter::InputType>;

```

### `UnaryLayer<typename RiverInit::OutputType,typename RiverInit::InputType>`
```
typedef MixerLayer<int,Biome *> UnaryLayer<typename RiverInit::OutputType,typename RiverInit::InputType>;

```

### `UnaryLayer<int,int>`
```
typedef MixerLayer<int,int> UnaryLayer<int,int>;

```

### `UnaryLayer<int,int>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<int,int>:328 : Layer<int>
{
  LayerPtr<int> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename River::OutputType,typename River::InputType>`
```
typedef MixerLayer<bool,int> UnaryLayer<typename River::OutputType,typename River::InputType>;

```

### `UnaryLayer<typename River::OutputType,typename River::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename River::OutputType,typename River::InputType>:328 : Layer<bool>
{
  LayerPtr<int> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename Smooth<bool>::OutputType,typename Smooth<bool>::InputType>`
```
typedef MixerLayer<bool,bool> UnaryLayer<typename Smooth<bool>::OutputType,typename Smooth<bool>::InputType>;

```

### `UnaryLayer<typename Smooth<bool>::OutputType,typename Smooth<bool>::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename Smooth<bool>::OutputType,typename Smooth<bool>::InputType>:328 : Layer<bool>
{
  LayerPtr<bool> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename RareBiomeSpot::OutputType,typename RareBiomeSpot::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename RareBiomeSpot::OutputType,typename RareBiomeSpot::InputType>;

```

### `UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::InputType>;

```

### `UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::InputType>;

```

### `UnaryLayer<Biome *,Biome *>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<Biome *,Biome *>;

```

### `UnaryLayer<Biome *,Biome *>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<Biome *,Biome *>:328 : Layer<Biome *>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddBiomeIsland::OutputType,typename AddBiomeIsland::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename AddBiomeIsland::OutputType,typename AddBiomeIsland::InputType>;

```

### `UnaryLayer<typename Shore::OutputType,typename Shore::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename Shore::OutputType,typename Shore::InputType>;

```

### `UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::InputType>;

```

### `UnaryLayer<typename Smooth<Biome *>::OutputType,typename Smooth<Biome *>::InputType>`
```
typedef MixerLayer<Biome *,Biome *> UnaryLayer<typename Smooth<Biome *>::OutputType,typename Smooth<Biome *>::InputType>;

```

### `UnaryLayer<typename Smooth<Biome *>::OutputType,typename Smooth<Biome *>::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename Smooth<Biome *>::OutputType,typename Smooth<Biome *>::InputType>:328 : Layer<Biome *>
{
  LayerPtr<Biome *> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<typename AddOceanEdge::OutputType,typename AddOceanEdge::InputType>`
```
typedef MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory> UnaryLayer<typename AddOceanEdge::OutputType,typename AddOceanEdge::InputType>;

```

### `UnaryLayer<typename AddOceanEdge::OutputType,typename AddOceanEdge::InputType>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<typename AddOceanEdge::OutputType,typename AddOceanEdge::InputType>:328 : Layer<BiomeTemperatureCategory>
{
  LayerPtr<BiomeTemperatureCategory> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnaryLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>`
```
typedef MixerLayer<BiomeTemperatureCategory,BiomeTemperatureCategory> UnaryLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>;

```

### `UnaryLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>:328`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) UnaryLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>:328 : Layer<BiomeTemperatureCategory>
{
  LayerPtr<BiomeTemperatureCategory> mFirstParent;
  std::tuple<> mMoreParents;
};

```

### `UnderwaterLargeCaveFeature`
```
struct __cppobj UnderwaterLargeCaveFeature : LargeCaveFeature
{
};

```

### `UnderwaterCanyonFeature`
```
struct __cppobj UnderwaterCanyonFeature : CanyonFeature
{
};

```

### `Unique<StructureStart>`
```
typedef std::unique_ptr<StructureStart> Unique<StructureStart>;

```

### `Unique<NetherFortressPiece>`
```
typedef std::unique_ptr<NetherFortressPiece> Unique<NetherFortressPiece>;

```

### `Util::HashString::HashFunc`
```
struct Util::HashString::HashFunc
{
  __int8 gap0[1];
};

```

### `Unique<DataItem>`
```
typedef std::unique_ptr<DataItem> Unique<DataItem>;

```

### `Util::hashStringSet`
```
typedef std::set<Util::HashString,Util::HashString::HashFunc,std::allocator<Util::HashString> > Util::hashStringSet;

```

### `Unique<NpcAction>`
```
typedef std::unique_ptr<NpcAction> Unique<NpcAction>;

```

### `UPNPInterface`
```
struct UPNPInterface
{
  std::vector<UPNPInterface::ConnectionStateListener *> mConnectionStateListeners;
  UPnPResultState<UPNPPortMappingResult> mUPnPPortMappingv4;
  UPnPResultState<UPNPPortMappingResult> mUPnPPortMappingv6;
  UPnPResultState<UPNPExternalIPResult> mUPnPExternalIP;
  MPMCQueue<std::function<void ()> > mCompletedQueue;
};

```

### `UPnPResultState<UPNPPortMappingResult>`
```
struct UPnPResultState<UPNPPortMappingResult>
{
  UPNPPortMappingResult result;
  UpnpState state;
  bool isValid;
  AsyncTracker tracker;
};

```

### `UPnPResultState<UPNPExternalIPResult>`
```
struct UPnPResultState<UPNPExternalIPResult>
{
  UPNPExternalIPResult result;
  UpnpState state;
  bool isValid;
  AsyncTracker tracker;
};

```

### `Unique<ClassroomModeNetworkHandler>`
```
typedef std::unique_ptr<ClassroomModeNetworkHandler> Unique<ClassroomModeNetworkHandler>;

```

### `Unique<RepairItemRecipe>`
```
typedef std::unique_ptr<RepairItemRecipe> Unique<RepairItemRecipe>;

```

### `Unique<ConnectionRequest>`
```
typedef std::unique_ptr<ConnectionRequest> Unique<ConnectionRequest>;

```

### `Unique<SubClientConnectionRequest>`
```
typedef std::unique_ptr<SubClientConnectionRequest> Unique<SubClientConnectionRequest>;

```

### `UIPackError`
```
struct __cppobj UIPackError : PackError
{
};

```

### `Unique<Minecraft>`
```
typedef std::unique_ptr<Minecraft> Unique<Minecraft>;

```

### `Unique<NetworkHandler>`
```
typedef std::unique_ptr<NetworkHandler> Unique<NetworkHandler>;

```

### `Unique<LoopbackPacketSender>`
```
typedef std::unique_ptr<LoopbackPacketSender> Unique<LoopbackPacketSender>;

```

### `Unique<Timer>`
```
typedef std::unique_ptr<Timer> Unique<Timer>;

```

### `Unique<SavedDataStorage>`
```
typedef std::unique_ptr<SavedDataStorage> Unique<SavedDataStorage>;

```

### `Unique<PhotoStorage>`
```
typedef std::unique_ptr<PhotoStorage> Unique<PhotoStorage>;

```

### `Unique<ActorDefinitionGroup>`
```
typedef std::unique_ptr<ActorDefinitionGroup> Unique<ActorDefinitionGroup>;

```

### `Unique<ActorAnimationGroup>`
```
typedef std::unique_ptr<ActorAnimationGroup> Unique<ActorAnimationGroup>;

```

### `Unique<ActorAnimationControllerGroup>`
```
typedef std::unique_ptr<ActorAnimationControllerGroup> Unique<ActorAnimationControllerGroup>;

```

### `Unique<ActorSpawnRuleGroup>`
```
typedef std::unique_ptr<ActorSpawnRuleGroup> Unique<ActorSpawnRuleGroup>;

```

### `Unique<SpawnGroupRegistry>`
```
typedef std::unique_ptr<SpawnGroupRegistry> Unique<SpawnGroupRegistry>;

```

### `Unique<Spawner>`
```
typedef std::unique_ptr<Spawner> Unique<Spawner>;

```

### `Unique<ProjectileFactory>`
```
typedef std::unique_ptr<ProjectileFactory> Unique<ProjectileFactory>;

```

### `Unique<BehaviorFactory>`
```
typedef std::unique_ptr<BehaviorFactory> Unique<BehaviorFactory>;

```

### `Unique<BehaviorTreeGroup>`
```
typedef std::unique_ptr<BehaviorTreeGroup> Unique<BehaviorTreeGroup>;

```

### `Unique<BlockPalette>`
```
typedef std::unique_ptr<BlockPalette> Unique<BlockPalette>;

```

### `Unique<Recipes>`
```
typedef std::unique_ptr<Recipes> Unique<Recipes>;

```

### `Unique<PortalForcer>`
```
typedef std::unique_ptr<PortalForcer> Unique<PortalForcer>;

```

### `Unique<TickingAreasManager>`
```
typedef std::unique_ptr<TickingAreasManager> Unique<TickingAreasManager>;

```

### `Unique<ServerMoveInputHandler>`
```
typedef std::unique_ptr<ServerMoveInputHandler> Unique<ServerMoveInputHandler>;

```

### `Unique<BlockSource>`
```
typedef std::unique_ptr<BlockSource> Unique<BlockSource>;

```

### `Unique<PlayerInventoryProxy>`
```
typedef std::unique_ptr<PlayerInventoryProxy> Unique<PlayerInventoryProxy>;

```

### `Unique<EnderChestContainer>`
```
typedef std::unique_ptr<EnderChestContainer> Unique<EnderChestContainer>;

```

### `Unique<GameMode>`
```
typedef std::unique_ptr<GameMode> Unique<GameMode>;

```

### `Unique<SpatialActorNetworkData>`
```
typedef std::unique_ptr<SpatialActorNetworkData> Unique<SpatialActorNetworkData>;

```

### `Unique<EconomyTradeableComponent>`
```
typedef std::unique_ptr<EconomyTradeableComponent> Unique<EconomyTradeableComponent>;

```

### `Unique<ActionQueue>`
```
typedef std::unique_ptr<ActionQueue> Unique<ActionQueue>;

```

### `Unique<RakNet::BitStream>`
```
typedef std::unique_ptr<RakNet::BitStream> Unique<RakNet::BitStream>;

```

### `Util::CaseInsensitiveHash`
```
struct Util::CaseInsensitiveHash
{
  __int8 gap0[1];
};

```

### `Util::CaseInsensitiveCompare`
```
struct Util::CaseInsensitiveCompare
{
  __int8 gap0[1];
};

```

### `Util::ProfanityExactMap`
```
typedef std::unordered_map<std::string,int> Util::ProfanityExactMap;

```

### `Util::ProfanityContainsSet`
```
typedef std::unordered_set<std::string> Util::ProfanityContainsSet;

```

### `Unique<ResourcePackManager>`
```
typedef std::unique_ptr<ResourcePackManager> Unique<ResourcePackManager>;

```

### `Unique<StructureManager>`
```
typedef std::unique_ptr<StructureManager> Unique<StructureManager>;

```

### `Unique<PrivateKeyManager>`
```
typedef std::unique_ptr<PrivateKeyManager> Unique<PrivateKeyManager>;

```

### `Unique<MinecraftCommands>`
```
typedef std::unique_ptr<MinecraftCommands> Unique<MinecraftCommands>;

```

### `Unique<GameSession>`
```
typedef std::unique_ptr<GameSession> Unique<GameSession>;

```

### `Unique<Packet>`
```
typedef std::unique_ptr<Packet> Unique<Packet>;

```

### `UIProfanityContext`
```
struct UIProfanityContext
{
  int (**_vptr$UIProfanityContext)(void);
  ProfanityFilterContext mFilterMask;
  std::unordered_map<std::string,int> mProfanityExactMap;
  std::unordered_set<std::string> mProfanityContainsSet;
};

```

### `Unique<BodyControl>`
```
typedef std::unique_ptr<BodyControl> Unique<BodyControl>;

```

### `Unique<MakeLoveGoal>`
```
typedef std::unique_ptr<MakeLoveGoal> Unique<MakeLoveGoal>;

```

### `Unique<PlayGoal>`
```
typedef std::unique_ptr<PlayGoal> Unique<PlayGoal>;

```

### `Unique<ReceiveLoveGoal>`
```
typedef std::unique_ptr<ReceiveLoveGoal> Unique<ReceiveLoveGoal>;

```

### `Unique<HarvestFarmBlockGoal>`
```
typedef std::unique_ptr<HarvestFarmBlockGoal> Unique<HarvestFarmBlockGoal>;

```

### `Unique<SquidIdleGoal>`
```
typedef std::unique_ptr<SquidIdleGoal> Unique<SquidIdleGoal>;

```

### `Unique<SquidFleeGoal>`
```
typedef std::unique_ptr<SquidFleeGoal> Unique<SquidFleeGoal>;

```

### `Unique<SquidMoveAwayFromGroundGoal>`
```
typedef std::unique_ptr<SquidMoveAwayFromGroundGoal> Unique<SquidMoveAwayFromGroundGoal>;

```

### `Unique<SquidOutOfWaterGoal>`
```
typedef std::unique_ptr<SquidOutOfWaterGoal> Unique<SquidOutOfWaterGoal>;

```

### `Unique<SquidDiveGoal>`
```
typedef std::unique_ptr<SquidDiveGoal> Unique<SquidDiveGoal>;

```

### `Unique<SkeletonHorseTrapGoal>`
```
typedef std::unique_ptr<SkeletonHorseTrapGoal> Unique<SkeletonHorseTrapGoal>;

```

### `Unique<SwellGoal>`
```
typedef std::unique_ptr<SwellGoal> Unique<SwellGoal>;

```

### `Unique<EndermanLeaveBlockGoal>`
```
typedef std::unique_ptr<EndermanLeaveBlockGoal> Unique<EndermanLeaveBlockGoal>;

```

### `Unique<EndermanTakeBlockGoal>`
```
typedef std::unique_ptr<EndermanTakeBlockGoal> Unique<EndermanTakeBlockGoal>;

```

### `Unique<GuardianAttackGoal>`
```
typedef std::unique_ptr<GuardianAttackGoal> Unique<GuardianAttackGoal>;

```

### `Unique<Slime>`
```
typedef std::unique_ptr<Slime> Unique<Slime>;

```

### `Unique<Mob>`
```
typedef std::unique_ptr<Mob> Unique<Mob>;

```

### `Unique<Block>`
```
typedef std::unique_ptr<Block> Unique<Block>;

```

### `Unique<ChestBlockActor>`
```
typedef std::unique_ptr<ChestBlockActor> Unique<ChestBlockActor>;

```

### `Unique<EnderChestBlockActor>`
```
typedef std::unique_ptr<EnderChestBlockActor> Unique<EnderChestBlockActor>;

```

### `Unique<BaseMobSpawner>`
```
typedef std::unique_ptr<BaseMobSpawner> Unique<BaseMobSpawner>;

```

### `Unique<ShulkerBoxBlockActor>`
```
typedef std::unique_ptr<ShulkerBoxBlockActor> Unique<ShulkerBoxBlockActor>;

```

### `UndyedShulkerBoxBlock`
```
struct __cppobj __attribute__((aligned(8))) UndyedShulkerBoxBlock : ShulkerBoxBlock
{
};

```

### `UnderwaterTorchBlock`
```
struct __cppobj UnderwaterTorchBlock : TorchBlock
{
};

```

### `Unique<EndDragonFight>`
```
typedef std::unique_ptr<EndDragonFight> Unique<EndDragonFight>;

```

### `UnburiedConstraint`
```
struct __cppobj UnburiedConstraint : IStructureConstraint
{
  std::vector<BlockPos> mCeilingOffsets;
};

```

### `Unique<OceanMonumentPiece>`
```
typedef std::unique_ptr<OceanMonumentPiece> Unique<OceanMonumentPiece>;

```

### `Unique<WoodlandMansionPieces::SimpleGrid>`
```
typedef std::unique_ptr<WoodlandMansionPieces::SimpleGrid> Unique<WoodlandMansionPieces::SimpleGrid>;

```

### `Unique<Crypto::Symmetric::Symmetric>`
```
typedef std::unique_ptr<Crypto::Symmetric::Symmetric> Unique<Crypto::Symmetric::Symmetric>;

```

### `Unique<Crypto::Hash::HMAC>`
```
typedef std::unique_ptr<Crypto::Hash::HMAC> Unique<Crypto::Hash::HMAC>;

```

### `Util::LootTableUtils`
```
struct Util::LootTableUtils
{
  __int8 gap0[1];
};

```

### `UseActorDefinition`
```
struct __cppobj UseActorDefinition : BehaviorDefinition
{
};

```

### `UseActorNode`
```
struct __cppobj __attribute__((aligned(8))) UseActorNode : BehaviorNode:480
{
  int mDelayCounter;
  bool mRightMouseDown;
  bool mPreActionDone;
};

```

### `Unique<EndCityPieces::EndCityPiece>`
```
typedef std::unique_ptr<EndCityPieces::EndCityPiece> Unique<EndCityPieces::EndCityPiece>;

```

### `Unique<DBStorageEnvironmentChain>`
```
typedef std::unique_ptr<DBStorageEnvironmentChain> Unique<DBStorageEnvironmentChain>;

```

### `Unique<leveldb::Cache>`
```
typedef std::unique_ptr<leveldb::Cache> Unique<leveldb::Cache>;

```

### `Unique<const leveldb::FilterPolicy>`
```
typedef std::unique_ptr<const leveldb::FilterPolicy> Unique<const leveldb::FilterPolicy>;

```

### `Unique<leveldb::Compressor>`
```
typedef std::unique_ptr<leveldb::Compressor> Unique<leveldb::Compressor>;

```

### `Unique<DBStorage::Options>`
```
typedef std::unique_ptr<DBStorage::Options> Unique<DBStorage::Options>;

```

### `Unique<leveldb::DecompressAllocator>`
```
typedef std::unique_ptr<leveldb::DecompressAllocator> Unique<leveldb::DecompressAllocator>;

```

### `Unique<leveldb::DB>`
```
typedef std::unique_ptr<leveldb::DB> Unique<leveldb::DB>;

```

### `Unique<TaskGroup>`
```
typedef std::unique_ptr<TaskGroup> Unique<TaskGroup>;

```

### `Unique<RegionFile>`
```
typedef std::unique_ptr<RegionFile> Unique<RegionFile>;

```

### `unz_file_info_s`
```
struct unz_file_info_s
{
  uLong version;
  uLong version_needed;
  uLong flag;
  uLong compression_method;
  uLong dosDate;
  uLong crc;
  uLong compressed_size;
  uLong uncompressed_size;
  uLong size_filename;
  uLong size_file_extra;
  uLong size_file_comment;
  uLong disk_num_start;
  uLong internal_fa;
  uLong external_fa;
  tm_unz tmu_date;
};

```

### `unz_global_info64_s`
```
struct unz_global_info64_s
{
  ZPOS64_T number_entry;
  uLong size_comment;
};

```

### `unz_global_info_s`
```
struct unz_global_info_s
{
  uLong number_entry;
  uLong size_comment;
};

```

### `Util::CodePageMap`
```
typedef std::unordered_map<unsigned char,std::string> Util::CodePageMap;

```

### `utf8proc_property_struct`
```
struct utf8proc_property_struct
{
  utf8proc_propval_t category;
  utf8proc_propval_t combining_class;
  utf8proc_propval_t bidi_class;
  utf8proc_propval_t decomp_type;
  const int32_t *decomp_mapping;
  unsigned __int32 bidi_mirrored : 1;
  int32_t uppercase_mapping;
  int32_t lowercase_mapping;
  int32_t titlecase_mapping;
  int32_t comb1st_index;
  int32_t comb2nd_index;
  unsigned __int32 comp_exclusion : 1;
  unsigned __int32 ignorable : 1;
  unsigned __int32 control_boundary : 1;
  unsigned __int32 extend : 1;
  const int32_t *casefold_mapping;
};

```

### `unz_file_info64_s`
```
struct unz_file_info64_s
{
  uLong version;
  uLong version_needed;
  uLong flag;
  uLong compression_method;
  uLong dosDate;
  uLong crc;
  ZPOS64_T compressed_size;
  ZPOS64_T uncompressed_size;
  uLong size_filename;
  uLong size_file_extra;
  uLong size_file_comment;
  uLong disk_num_start;
  uLong internal_fa;
  uLong external_fa;
  tm_unz tmu_date;
};

```

### `unz_file_info64_internal_s`
```
struct unz_file_info64_internal_s
{
  ZPOS64_T offset_curfile;
};

```

### `unz64_file_pos_s`
```
struct unz64_file_pos_s
{
  ZPOS64_T pos_in_zip_directory;
  ZPOS64_T num_of_file;
};

```

### `unz_file_pos`
```
typedef unz_file_pos_s unz_file_pos;

```

### `unz_file_pos_s`
```
struct unz_file_pos_s
{
  uLong pos_in_zip_directory;
  uLong num_of_file;
};

```

### `ucontext_t`
```
struct ucontext_t
{
  unsigned __int64 uc_flags;
  ucontext_t *uc_link;
  stack_t uc_stack;
  mcontext_t uc_mcontext;
  sigset_t uc_sigmask;
  _libc_fpstate __fpregs_mem;
};

```

