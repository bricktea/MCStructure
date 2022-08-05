# I
### `IJsonSerializable`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IJsonSerializable


### `IMinecraftApp`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IMinecraftApp


### `ItemStack`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemStackBase` | baseclass_0


### `ItemStackBase`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ItemStackBase
8 | (8) `WeakPtr<Item>` | mItem
16 | (8) `Unique<CompoundTag>` | mUserData
24 | (8) `const Block *` | mBlock
32 | (2) `__int16` | mAuxValue
34 | (1) `byte` | mCount
35 | (1) `bool` | mValid
40 | (8) `std::chrono::_V2::steady_clock::time_point` | mPickupTime
48 | (1) `bool` | mShowPickUp
56 | (24) `std::vector<const BlockLegacy *>` | mCanPlaceOn
80 | (8) `size_t` | mCanPlaceOnHash
88 | (24) `std::vector<const BlockLegacy *>` | mCanDestroy
112 | (8) `size_t` | mCanDestroyHash
120 | (8) `Tick` | mBlockingTick
128 | (8) `Unique<ItemInstance>` | mChargedItem


### `IBlockPlacementTarget`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IBlockPlacementTarget


### `IFeature`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IFeature


### `ItemEnchants`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSlot
8 | (72) `std::vector<EnchantmentInstance>[3]` | mItemEnchants


### `ItemInstance`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemStackBase` | baseclass_0


### `ITextObject`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ITextObject


### `IEntityComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `InsomniaComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTimeSinceRest
4 | (4) `float` | mDaysUntilInsomnia
8 | (4) `int` | mTicksUntilInsomnia


### `InteractComponent`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mCoolDownCounter


### `IDataOutput`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IDataOutput


### `IDataInput`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IDataInput


### `in6_addr`
Offset | Type | Name
-|-|-|-
0 | (16) `in6_addr::$FA2BBAF2C6BC03A9E0081A5D902744A5` | __in6_u


### `in6_addr::$FA2BBAF2C6BC03A9E0081A5D902744A5`
Offset | Type | Name
-|-|-|-
0 | (16) `uint8_t[16]` | __u6_addr8
1 | (16) `uint16_t[8]` | __u6_addr16
2 | (16) `uint32_t[4]` | __u6_addr32


### `in_addr`
Offset | Type | Name
-|-|-|-
0 | (4) `in_addr_t` | s_addr


### `InventoryContentPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mInventoryId
40 | (24) `std::vector<ItemStack>` | mSlots


### `InventorySource`
Offset | Type | Name
-|-|-|-
0 | (4) `InventorySourceType` | mType
4 | (1) `ContainerID` | mContainerId
8 | (4) `InventorySource::InventorySourceFlags` | mFlags


### `InputModeValueChangedCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (Option *,InputMode)>::_Invoker_type` | _M_invoker


### `IntOption::_validate::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `iterator`
Offset | Type | Name
-|-|-|-
0 | (16) `std::_Bit_iterator_base` | baseclass_0


### `InventoryTransactionPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `Unique<ComplexInventoryTransaction>` | mTransaction


### `InventorySlotPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mInventoryId
40 | (4) `uint32_t` | mSlot
48 | (136) `ItemStack` | mItem


### `InvertableFilter<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | value
32 | (1) `bool` | inverted


### `InteractDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Interaction>` | mInteractions


### `InteractPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `InteractPacket::Action` | mAction
40 | (8) `ActorRuntimeID` | mTargetId
48 | (12) `Vec3` | mPos


### `IsotropicFaceData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mFaceTextureIsotropic
4 | (4) `unsigned int` | mIsotropicFaceEnabled


### `IllagerBeastBlockedComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `IntRange`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | rangeMin
4 | (4) `int` | rangeMax


### `IdentifierDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (32) `std::string` | mId


### `IsSpawnableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (1) `bool` | mIsSpawnable


### `IsSummonableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (1) `bool` | mIsSummonable


### `IsExperimentalDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription` | baseclass_0
8 | (1) `bool` | mIsExperimental


### `ItemDescriptor`
Offset | Type | Name
-|-|-|-
0 | (8) `WeakPtr<Item>` | mItem
8 | (8) `const Block *` | mBlock
16 | (2) `__int16` | mAuxValue
18 | (1) `bool` | mValid


### `InventoryAction`
Offset | Type | Name
-|-|-|-
0 | (12) `InventorySource` | mSource
12 | (4) `uint32_t` | mSlot
16 | (136) `ItemStack` | mFromItem
152 | (136) `ItemStack` | mToItem


### `ItemTransferAmount`
Offset | Type | Name
-|-|-|-
0 | (4) `const ItemTransferAmount::ItemTransferAmountTag` | mTag
4 | (4) `ItemTransferAmount::$8A9EA68892D5133F1EC35B6C915D03B5` | mData
8 | (1) `const bool` | mFromMax


### `ItemTransferAmount::$8A9EA68892D5133F1EC35B6C915D03B5`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | requestAmount
1 | (4) `ItemTakeType` | takeType
2 | (4) `ItemPlaceType` | placeType


### `InstantaneousAttributeBuff`
Offset | Type | Name
-|-|-|-
0 | (88) `AttributeBuff` | baseclass_0


### `ItemUseInventoryTransaction::resendBlocksAroundArea::$AAED32D802A7A0D4B8CDA03B8D4F5BA0`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | player
8 | (8) `BlockSource *` | region


### `ItemOffsetsJsonMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackMergeStrategy` | baseclass_0
8 | (32) `std::string` | mFileName
40 | (8) `Json::Value *` | mRoot
48 | (32) `ItemOffsetsJsonMergeStrategy::PreMergeCallback` | mPreMergeCallback


### `ItemOffsetsJsonMergeStrategy::PreMergeCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (Json::Value &,const Json::Value &)>::_Invoker_type` | _M_invoker


### `ItemStackBase::_loadComponents::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ItemDescriptorCount`
Offset | Type | Name
-|-|-|-
0 | (20) `ItemDescriptor:160` | baseclass_0
20 | (2) `uint16_t` | mStackSize


### `ItemDescriptor:160`
Offset | Type | Name
-|-|-|-
0 | (8) `WeakPtr<Item>` | mItem
8 | (8) `const Block *` | mBlock
16 | (2) `__int16` | mAuxValue
18 | (1) `bool` | mValid


### `InheritanceTree<BiomeRegistry::BiomeParent>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,InheritanceTree<BiomeRegistry::BiomeParent>::InheritanceTreeNode,std::hash<std::string>,std::equal_to<std::string >,std::allocator<std::pair<const std::string,InheritanceTree<BiomeRegistry::BiomeParent>::InheritanceTreeNode> > >` | mNodes
56 | (40) `Bedrock::Threading::Mutex` | mNodeLock


### `ItemFrameDropItemPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos


### `IndexSet`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned long>` | mPacked
24 | (24) `std::vector<unsigned long>` | mSparse


### `ifconf`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | ifc_len
8 | (8) `ifconf::$CB4E2310AA03783056CB5D3719B31C2A` | ifc_ifcu


### `ifconf::$CB4E2310AA03783056CB5D3719B31C2A`
Offset | Type | Name
-|-|-|-
0 | (8) `__caddr_t` | ifcu_buf
1 | (8) `ifreq *` | ifcu_req


### `IdentifierResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
8 | (32) `std::string` | mIdentifier
40 | (32) `std::string` | mNamespace


### `IdentityDefinition::PlayerNameResolver`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<const std::string &(ActorUniqueID)>::_Invoker_type` | _M_invoker


### `Item::Tier`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mLevel
4 | (4) `const int` | mUses
8 | (4) `const float` | mSpeed
12 | (4) `const int` | mDamage
16 | (4) `const int` | mEnchantmentValue


### `IdentityDefinition`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (1) `bool` | mIsHiddenFakePlayer
24 | (8) `PlayerScoreboardId` | mPlayerId
32 | (8) `ActorUniqueID` | mEntityId
40 | (32) `std::string` | mPlayerName
72 | (1) `IdentityDefinition::Type` | mIdentityType


### `ifreq`
Offset | Type | Name
-|-|-|-
0 | (16) `ifreq::$EC3FB77B1F5CBB3C6B6AB4B4CE5B261D` | ifr_ifrn
16 | (24) `ifreq::$3766CEB1D20AE6FB37CD7F05C4AF9C4E` | ifr_ifru


### `ifreq::$EC3FB77B1F5CBB3C6B6AB4B4CE5B261D`
Offset | Type | Name
-|-|-|-
0 | (16) `char[16]` | ifrn_name


### `ifreq::$3766CEB1D20AE6FB37CD7F05C4AF9C4E`
Offset | Type | Name
-|-|-|-
0 | (16) `sockaddr` | ifru_addr
1 | (16) `sockaddr` | ifru_dstaddr
2 | (16) `sockaddr` | ifru_broadaddr
3 | (16) `sockaddr` | ifru_netmask
4 | (16) `sockaddr` | ifru_hwaddr
5 | (2) `__int16` | ifru_flags
6 | (4) `int` | ifru_ivalue
7 | (4) `int` | ifru_mtu
8 | (24) `ifmap` | ifru_map
9 | (16) `char[16]` | ifru_slave
10 | (16) `char[16]` | ifru_newname
11 | (8) `__caddr_t` | ifru_data


### `ifmap`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mem_start
8 | (8) `unsigned __int64` | mem_end
16 | (2) `unsigned __int16` | base_addr
18 | (1) `unsigned __int8` | irq
19 | (1) `unsigned __int8` | dma
20 | (1) `unsigned __int8` | port


### `ipv6_mreq`
Offset | Type | Name
-|-|-|-
0 | (16) `in6_addr` | ipv6mr_multiaddr
16 | (4) `unsigned int` | ipv6mr_interface


### `IFileAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IFileAccess


### `IFileReadAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IFileReadAccess


### `IFileWriteAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IFileWriteAccess


### `iovec`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | iov_base
8 | (8) `size_t` | iov_len


### `ItemRegistry::ItemRegistryMap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<SharedPtr<Item>>` | baseclass_0


### `InternalTaskGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `ITaskGroup` | baseclass_0


### `ITaskGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ITaskGroup


### `ItemStateVariant<bool>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemState`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ItemState
8 | (8) `const size_t` | mID
16 | (8) `const size_t` | mVariationCount
24 | (32) `const std::string` | mName
56 | (24) `ItemState::StateListNode` | mNode


### `ItemState::StateListNode`
Offset | Type | Name
-|-|-|-
0 | (8) `ItemState::StateListNode *` | mNext
8 | (8) `ItemState::StateListNode *` | mPrev
16 | (8) `ItemState *` | mState


### `ItemStateVariant<int>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<PortalAxis>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<AnvilDamage>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<SaplingType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<TorchFacing>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<EggCount>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<HatchLevel>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<BlockColor>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StalkThickness>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<LeafSize>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<WoodType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<DirtType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<SandType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<OldLogType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<NewLogType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<ChiselType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<OldLeafType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<NewLeafType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<SpongeType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<SandStoneType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<TallGrassType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<FlowerType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneSlabType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneSlabType2>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneSlabType3>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneSlabType4>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<MonsterEggStoneType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StoneBrickType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<WallBlockType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<PrismarineBlockType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<DoublePlantType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<ChemistryTableType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<SeaGrassType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<CoralColor>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<CauldronLiquidType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<AttachmentType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StructureVoidType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<StructureBlockType>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<LeverDirection>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `ItemStateVariant<PillarAxis>`
Offset | Type | Name
-|-|-|-
0 | (80) `ItemState` | baseclass_0


### `IMinecraftEventing`
Offset | Type | Name
-|-|-|-
0 | (8) `IPackTelemetry` | baseclass_0
8 | (24) `IWebviewTelemetry` | baseclass_8


### `IPackTelemetry`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$IPackTelemetry


### `IWebviewTelemetry`
Offset | Type | Name
-|-|-|-
0 | (16) `WebviewObserver` | baseclass_0
16 | (8) `const IMinecraftEventing *` | mEventing


### `ItemData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (2) `__int16` | mId


### `IronGolem::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ItemGroup`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemInstance` | mItemTemplate
136 | (4) `int` | mCount


### `IDType<TagIDType>`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mID


### `InventoryTransactionItemGroup`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mItemId
4 | (4) `int` | mItemAux
8 | (8) `Unique<CompoundTag>` | mTag
16 | (4) `int32_t` | mCount
20 | (1) `bool` | mOverflow


### `InheritanceTree<BiomeRegistry::BiomeParent>::InheritanceTreeNode`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (48) `BiomeRegistry::BiomeParent` | val
80 | (24) `std::vector<InheritanceTree<BiomeRegistry::BiomeParent>::InheritanceTreeNode *,std::allocator<InheritanceTree<BiomeRegistry::BiomeParent>::InheritanceTreeNode *> >` | child
104 | (1) `bool` | isVisited


### `IdentityDictionary`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<PlayerScoreboardId,ScoreboardId>` | mPlayers
56 | (56) `std::unordered_map<ActorUniqueID,ScoreboardId>` | mEntities
112 | (56) `std::unordered_map<std::string,ScoreboardId>` | mFakes
168 | (56) `std::unordered_map<ScoreboardId,IdentityDefinition>` | mIdentityDefs


### `ItemDefinition`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | itemId
4 | (4) `int` | auxValue


### `IDType<TagSetIDType>`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mID


### `InMemoryFile`
Offset | Type | Name
-|-|-|-
0 | (40) `Bedrock::Threading::Mutex` | mMutex
40 | (24) `std::vector<char>` | mBuffer
64 | (32) `Core::HeapPathBuffer` | mFilename
96 | (1) `bool` | mOpenForWrite
100 | (4) `int` | mOpenReadHandles
104 | (1) `bool` | mMarkedForDelete
105 | (1) `bool` | mMarkedDirty


### `IInPackagePacks`
```
struct IInPackagePacks
{
  int (**_vptr$IInPackagePacks)(void);
};

```

### `IGameModuleShared`
```
struct IGameModuleShared
{
  int (**_vptr$IGameModuleShared)(void);
};

```

### `IContentAccessibilityProvider`
```
struct __cppobj IContentAccessibilityProvider : IContentKeyProvider
{
};

```

### `IContentKeyProvider`
```
struct IContentKeyProvider
{
  int (**_vptr$IContentKeyProvider)(void);
};

```

### `InvertableFilter<std::string >`
```
struct __attribute__((aligned(8))) InvertableFilter<std::string >
{
  std::string value;
  bool inverted;
};

```

### `InPackagePackSource`
```
struct __cppobj InPackagePackSource : PackSource
{
  std::shared_ptr<IInPackagePacks> mPacksProvider;
  PackType mPackType;
  bool mDiscovered;
  std::vector<std::unique_ptr<Pack>> mPacks;
  PackSourceReport mReport;
};

```

### `InvalidPacksFilterGroup`
```
struct InvalidPacksFilterGroup
{
  std::vector<PackType> packFilters;
};

```

### `IAppPlatform`
```
struct IAppPlatform
{
  int (**_vptr$IAppPlatform)(void);
};

```

### `IInPackagePacks::MetaData`
```
struct IInPackagePacks::MetaData
{
  Core::HeapPathBuffer mPath;
  bool mIsHidden;
  PackCategory mPackCategory;
};

```

### `IDefinitionSerializer`
```
struct IDefinitionSerializer
{
  int (**_vptr$IDefinitionSerializer)(void);
  std::string mName;
};

```

### `IDefinitionInstance`
```
struct __attribute__((aligned(8))) IDefinitionInstance
{
  int (**_vptr$IDefinitionInstance)(void);
  std::string mName;
  uint16_t mTypeId;
};

```

### `ITickingSystem`
```
struct ITickingSystem
{
  int (**_vptr$ITickingSystem)(void);
};

```

### `InsomniaSystem`
```
struct __cppobj InsomniaSystem : ITickingSystem
{
};

```

### `InteractSystem`
```
struct __cppobj InteractSystem : ITickingSystem
{
};

```

### `IWorldRegistriesProvider`
```
struct IWorldRegistriesProvider
{
  int (**_vptr$IWorldRegistriesProvider)(void);
};

```

### `Item`
```
struct Item
{
  int (**_vptr$Item)(void);
  byte m_maxStackSize;
  std::string m_textureAtlasFile;
  int m_frameCount;
  bool m_animatesInToolbar;
  bool mIsMirroredArt;
  UseAnimation mUseAnim;
  const std::string *mHoverTextColorFormat;
  const TextureUVCoordinateSet *mIconTexture;
  const TextureAtlasItem *mIconAtlas;
  bool mUsesRenderingAdjustment;
  Vec3 mRenderingAdjTrans;
  Vec3 mRenderingAdjRot;
  float mRenderingAdjScale;
  __int16 mId;
  std::string mDescriptionId;
  std::string mRawNameId;
  std::string mNamespace;
  HashedString mFullName;
  __int16 mMaxDamage;
  __int8 mIsGlint : 1;
  __int8 mHandEquipped : 1;
  __int8 mIsStackedByData : 1;
  __int8 mRequiresWorldBuilder : 1;
  __int8 mExplodable : 1;
  __int8 mShouldDespawn : 1;
  __int8 mAllowOffhand : 1;
  __int8 mIgnoresPermissions : 1;
  __int8 mExperimental : 1;
  int mMaxUseDuration;
  BaseGameVersion mMinRequiredBaseGameVersion;
  WeakPtr<BlockLegacy> mLegacyBlock;
  CreativeItemCategory mCreativeCategory;
  Item *mCraftingRemainingItem;
  std::unique_ptr<FoodItemComponent> mFoodComponent;
  std::unique_ptr<SeedItemComponent> mSeedComponent;
  std::unique_ptr<CameraItemComponent> mCameraComponent;
  std::vector<std::function<void ()>> mOnResetBAIcallbacks;
};

```

### `IcebergFeature`
```
struct __cppobj IcebergFeature : Feature
{
};

```

### `IceSpikeFeature`
```
struct __cppobj IceSpikeFeature : Feature
{
};

```

### `IcePatchFeature`
```
struct __cppobj __attribute__((aligned(8))) IcePatchFeature : Feature
{
  const Block *mBlock;
  int mRadius;
};

```

### `ItemStateInstance`
```
struct ItemStateInstance
{
  const unsigned int mMaxBits;
  uint32_t mStartBit;
  uint32_t mNumBits;
  uint32_t mVariationCount;
  uint32_t mMask;
  bool mInitialized;
  const ItemState *mState;
};

```

### `InvertableFilter<ActorDefinitionIdentifier>`
```
struct __attribute__((aligned(8))) InvertableFilter<ActorDefinitionIdentifier>
{
  ActorDefinitionIdentifier value;
  bool inverted;
};

```

### `InventoryTransaction`
```
struct InventoryTransaction
{
  std::unordered_map<InventorySource,std::vector<InventoryAction>> mActions;
  std::vector<InventoryTransactionItemGroup> mContents;
};

```

### `InventoryTransactionManager`
```
struct InventoryTransactionManager
{
  Player *mPlayer;
  Unique<InventoryTransaction> mCurrentTransaction;
  std::vector<InventoryAction> mExpectedActions;
};

```

### `ITickingArea`
```
struct ITickingArea
{
  int (**_vptr$ITickingArea)(void);
};

```

### `IStructurePoolActorPredicate`
```
struct IStructurePoolActorPredicate
{
  int (**_vptr$IStructurePoolActorPredicate)(void);
};

```

### `IStructurePoolBlockPredicate`
```
struct IStructurePoolBlockPredicate
{
  int (**_vptr$IStructurePoolBlockPredicate)(void);
};

```

### `IStructurePoolBlockTagPredicate`
```
struct IStructurePoolBlockTagPredicate
{
  int (**_vptr$IStructurePoolBlockTagPredicate)(void);
};

```

### `ImprovedNoise`
```
struct ImprovedNoise
{
  Vec3 mOrigin;
  int mNoiseMap[512];
};

```

### `IslandLayer`
```
struct __cppobj IslandLayer : RootLayer<LayerValues::Terrain>
{
};

```

### `IMinecraftEventing::SignInErrorDetails`
```
typedef std::vector<std::pair<std::string,std::string >> IMinecraftEventing::SignInErrorDetails;

```

### `ItemActor`
```
struct __cppobj __attribute__((aligned(8))) ItemActor : Actor
{
  ItemStack mItem;
  int mAge;
  int mPickupDelay;
  int mThrowTime;
  float mBobOffs;
  int mHealth;
  int mLifeTime;
  bool mIsInItemFrame;
  bool mIsFromFishing;
};

```

### `Interaction`
```
struct Interaction
{
  int mRequiresCoolDown;
  bool mSwing;
  bool mUseItem;
  int mHurtItem;
  ItemDefinition mTransformItem;
  std::string mInteractText;
  std::string mAddItemsTable;
  std::string mSpawnItemsTable;
  ParticleType mParticleOnStartType;
  bool mParticleOffsetTowardsInteractor;
  float mParticleOffsetY;
  std::vector<LevelSoundEvent> mPlaySounds;
  std::vector<ActorDefinitionIdentifier> mSpawnEntities;
  DefinitionTrigger mOnInteraction;
};

```

### `I18n::LanguageChangedListener`
```
struct I18n::LanguageChangedListener
{
  std::weak_ptr<bool> mWeakTracker;
  std::function<void (const std::string &,bool)> mCallback;
};

```

### `I18n`
```
struct I18n
{
  __int8 gap0[1];
};

```

### `IntTag`
```
struct __cppobj __attribute__((aligned(8))) IntTag : Tag
{
  int data;
};

```

### `Int64Tag`
```
struct __cppobj Int64Tag : Tag
{
  int64_t data;
};

```

### `IntArrayTag`
```
struct __cppobj IntArrayTag : Tag
{
  TagMemoryChunk data;
};

```

### `IContainerManager`
```
struct IContainerManager
{
  int (**_vptr$IContainerManager)(void);
};

```

### `ItemFrameBlockActor`
```
struct __cppobj __attribute__((aligned(8))) ItemFrameBlockActor : BlockActor:1632
{
  ClockSpriteCalculator mClockSpriteCalc;
  CompassSpriteCalculator mCompassSpriteCalc;
  ItemInstance mItem;
  float mDropChance;
  float mRotation;
  bool mUpgradeMapBit;
};

```

### `IEntityRegistryOwner`
```
struct IEntityRegistryOwner
{
  int (**_vptr$IEntityRegistryOwner)(void);
};

```

### `InputModeFloatOption`
```
struct __cppobj __attribute__((aligned(8))) InputModeFloatOption : Option
{
  const float VALUE_MIN;
  const float VALUE_MAX;
  std::unordered_map<InputMode,float> mValues;
  std::unordered_map<InputMode,float> mDefaultValues;
  const float DELTA;
};

```

### `InputModeBoolOption`
```
struct __cppobj InputModeBoolOption : Option
{
  std::unordered_map<InputMode,bool> mValues;
  std::unordered_map<InputMode,bool> mDefaultValues;
};

```

### `IntOption`
```
struct __cppobj IntOption : Option
{
  const int VALUE_MAX;
  const int VALUE_MIN;
  int mValue;
  int mDefaultValue;
  bool mClampToRange;
  const std::vector<int> mPossibleValues;
  Option::SaveIntCallback mCoerceSaveValueCallback;
};

```

### `ICommandDispatcher`
```
struct ICommandDispatcher
{
  int (**_vptr$ICommandDispatcher)(void);
};

```

### `ItemEventCoordinator`
```
struct __cppobj ItemEventCoordinator : EventCoordinator<ItemEventListener>
{
};

```

### `ISurfaceBuilder`
```
struct ISurfaceBuilder
{
  int (**_vptr$ISurfaceBuilder)(void);
};

```

### `InventoryMenu`
```
struct __cppobj InventoryMenu : BaseContainerMenu
{
  Container *mContainer;
};

```

### `IsBabyDescription`
```
struct __cppobj IsBabyDescription : PropertyDescription
{
};

```

### `IsChargedDescription`
```
struct __cppobj IsChargedDescription : PropertyDescription
{
};

```

### `IsChestedDescription`
```
struct __cppobj IsChestedDescription : PropertyDescription
{
};

```

### `IsHiddenWhenInvisibleDescription`
```
struct __cppobj IsHiddenWhenInvisibleDescription : PropertyDescription
{
};

```

### `IsIgnitedDescription`
```
struct __cppobj IsIgnitedDescription : PropertyDescription
{
};

```

### `IsIllagerCaptainDescription`
```
struct __cppobj IsIllagerCaptainDescription : PropertyDescription
{
};

```

### `IsSaddledDescription`
```
struct __cppobj IsSaddledDescription : PropertyDescription
{
};

```

### `IsShakingDescription`
```
struct __cppobj IsShakingDescription : PropertyDescription
{
};

```

### `IsShearedDescription`
```
struct __cppobj IsShearedDescription : PropertyDescription
{
};

```

### `IsStunnedDescription`
```
struct __cppobj IsStunnedDescription : PropertyDescription
{
};

```

### `IsStackableDescription`
```
struct __cppobj IsStackableDescription : PropertyDescription
{
};

```

### `IsTamedDescription`
```
struct __cppobj IsTamedDescription : PropertyDescription
{
};

```

### `ItemControlDescription`
```
struct __cppobj ItemControlDescription : PropertyDescription
{
  std::set<const Item *> mControlItems;
};

```

### `IllagerBeastBlockedDescription`
```
struct __cppobj __attribute__((aligned(8))) IllagerBeastBlockedDescription : ComponentDescription
{
  WeightedChoices<DefinitionTrigger> mReactionChoices;
  float mKnockbackStrength;
};

```

### `Inventory`
```
struct __cppobj Inventory : FillingContainer
{
};

```

### `IsPlayer<Actor>`
```
struct IsPlayer<Actor>
{
  __int8 gap0[1];
};

```

### `IsPlayer<Player>`
```
struct IsPlayer<Player>
{
  __int8 gap0[1];
};

```

### `IFunctionEntry`
```
struct IFunctionEntry
{
  int (**_vptr$IFunctionEntry)(void);
};

```

### `ITickingAreaView`
```
struct ITickingAreaView
{
  int (**_vptr$ITickingAreaView)(void);
};

```

### `IFilePicker`
```
struct IFilePicker
{
  int (**_vptr$IFilePicker)(void);
};

```

### `IFileChunkUploader`
```
struct IFileChunkUploader
{
  int (**_vptr$IFileChunkUploader)(void);
};

```

### `InsomniaDefinition`
```
struct InsomniaDefinition
{
  float mDaysUntilInsomnia;
};

```

### `IronGolem`
```
struct __cppobj IronGolem : Mob
{
  int mAttackAnimationTick;
  int mOfferFlowerTick;
};

```

### `IllagerBeast`
```
struct __cppobj IllagerBeast : Monster
{
};

```

### `InspectBookshelfGoal`
```
struct __cppobj __attribute__((aligned(4))) InspectBookshelfGoal : BaseMoveToBlockGoal
{
  BlockPos mBookshelfPos;
  bool mRequireSameY;
};

```

### `intArray`
```
typedef std::vector<int> intArray;

```

### `ItemReleaseInventoryTransaction`
```
struct __cppobj __attribute__((aligned(8))) ItemReleaseInventoryTransaction : ComplexInventoryTransaction
{
  ItemReleaseInventoryTransaction::ActionType mActionType;
  int32_t mSlot;
  ItemStack mItem;
  Vec3 mFromPos;
};

```

### `ImpactDamageSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) ImpactDamageSubcomponent : OnHitSubcomponent
{
  bool mCatchFire;
  bool mChanneling;
  FloatRange mProjectileDamage;
  bool mKnockback;
  ActorType mFilter;
  bool mSemiRandomDiffDamage;
  bool mDestroyOnHit;
  int mMaxCriticalDamage;
  int mMinCriticalDamage;
  float mPowMultiplier;
};

```

### `IgniteSubcomponent`
```
struct __cppobj IgniteSubcomponent : OnHitSubcomponent
{
};

```

### `InventoryContainerModel`
```
struct __cppobj InventoryContainerModel : ContainerModel
{
  Player *mPlayer;
};

```

### `ItemIndexPair`
```
struct __attribute__((aligned(8))) ItemIndexPair
{
  ItemStack item;
  int index;
};

```

### `InstantaneousMobEffect`
```
struct __cppobj InstantaneousMobEffect : MobEffect
{
};

```

### `ItemUseOnActorInventoryTransaction`
```
struct __cppobj ItemUseOnActorInventoryTransaction : ComplexInventoryTransaction
{
  ActorRuntimeID mRuntimeId;
  ItemUseOnActorInventoryTransaction::ActionType mActionType;
  int32_t mSlot;
  ItemStack mItem;
  Vec3 mFromPos;
  Vec3 mHitPos;
};

```

### `ItemUseInventoryTransaction`
```
struct __cppobj ItemUseInventoryTransaction : ComplexInventoryTransaction
{
  ItemUseInventoryTransaction::ActionType mActionType;
  NetworkBlockPosition mPos;
  BlockRuntimeId mTargetBlockId;
  FacingID mFace;
  int32_t mSlot;
  ItemStack mItem;
  Vec3 mFromPos;
  Vec3 mClickPos;
};

```

### `ItemRegistry`
```
struct ItemRegistry
{
  __int8 gap0[1];
};

```

### `ItemUseMethodMap`
```
struct ItemUseMethodMap
{
  __int8 gap0[1];
};

```

### `ItemAcquisitionMethodMap`
```
struct ItemAcquisitionMethodMap
{
  __int8 gap0[1];
};

```

### `IceBombItem`
```
struct __cppobj IceBombItem : ChemistryItem
{
};

```

### `ItemPack::KeyHasher`
```
struct ItemPack::KeyHasher
{
  __int8 gap0[1];
};

```

### `ItemPack`
```
struct ItemPack
{
  std::unordered_map<ItemDescriptor,int,ItemPack::KeyHasher,std::equal_to<ItemDescriptor>,std::allocator<std::pair<const ItemDescriptor,int> > > mIngredients;
};

```

### `ItemReactionComponent`
```
struct __cppobj ItemReactionComponent : LabTableReactionComponent
{
  std::unique_ptr<ItemStack> mItem;
};

```

### `IceBlock`
```
struct __cppobj __attribute__((aligned(8))) IceBlock : BlockLegacy
{
  bool mPacked;
};

```

### `InvisibleBlock`
```
struct __cppobj InvisibleBlock : BlockLegacy
{
};

```

### `ItemFrameBlock`
```
struct __cppobj ItemFrameBlock : ActorBlock
{
};

```

### `ISubChunkBlockStoragePaletted`
```
struct __cppobj ISubChunkBlockStoragePaletted : SubChunkBlockStorage
{
};

```

### `IStructureConstraint`
```
struct IStructureConstraint
{
  int (**_vptr$IStructureConstraint)(void);
};

```

### `Igloo`
```
struct __cppobj __attribute__((aligned(8))) Igloo : ScatteredFeaturePiece
{
  LegacyStructureSettings mLabSettings;
  BlockPos mLabPos;
  Vec3 mVillagerPos;
  Vec3 mZombieVillagerPos;
};

```

### `ImmutableWorldCommand`
```
struct __cppobj ImmutableWorldCommand : Command:240
{
  bool mValue;
  bool mHaveValue;
};

```

### `ItemListSerializer`
```
struct ItemListSerializer
{
  __int8 gap0[1];
};

```

### `InverterDefinition`
```
struct __cppobj InverterDefinition : DecoratorDefinition
{
};

```

### `InverterNode`
```
struct __cppobj InverterNode : BehaviorNode
{
  Unique<BehaviorNode> mActiveChild;
};

```

### `InteractActionDefinition`
```
struct __cppobj InteractActionDefinition : BehaviorDefinition
{
  int mInteractTicks;
  std::string mInteractTicksId;
};

```

### `InteractActionNode`
```
struct __cppobj __attribute__((aligned(4))) InteractActionNode : BehaviorNode:480
{
  int mNumTicksToInteract;
  int mDelayCounter;
  bool mRightMouseDown;
  bool mPreActionDone;
};

```

### `InMemoryEnv`
```
struct __cppobj InMemoryEnv : FlushableEnv
{
  leveldb::Env *mTarget;
  Core::HeapPathBuffer mDbPath;
  InMemoryFileStorage mInMemoryStorage;
};

```

### `InMemoryFileStorage`
```
struct InMemoryFileStorage
{
  leveldb::Env *mEnvironment;
  Bedrock::Threading::Mutex mMutex;
  std::vector<std::shared_ptr<InMemoryFile>> mInMemoryFiles;
  std::vector<std::string> mDiskFilesToDelete;
};

```

### `InMemoryRandomAccessFile`
```
struct __cppobj InMemoryRandomAccessFile : leveldb::RandomAccessFile
{
  std::shared_ptr<InMemoryFile> mFile;
};

```

### `InMemorySequentialFile`
```
struct __cppobj InMemorySequentialFile : leveldb::SequentialFile
{
  std::shared_ptr<InMemoryFile> mFile;
  size_t mReadOffset;
};

```

### `InMemoryWritableFile`
```
struct __cppobj InMemoryWritableFile : leveldb::WritableFile
{
  std::shared_ptr<InMemoryFile> mFile;
};

```

### `ifaddrs`
```
struct ifaddrs
{
  ifaddrs *ifa_next;
  char *ifa_name;
  unsigned int ifa_flags;
  sockaddr *ifa_addr;
  sockaddr *ifa_netmask;
  ifaddrs::$84E426BE247030D232EE932B77F5CBF6 ifa_ifu;
  void *ifa_data;
};

```

### `ITaskExecutionContext`
```
struct ITaskExecutionContext
{
  int (**_vptr$ITaskExecutionContext)(void);
};

```

