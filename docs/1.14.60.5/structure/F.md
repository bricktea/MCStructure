# F
### `FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PosibleTransformation>` | mTransformations


### `Factory<Dimension,Level &,Scheduler &>::TypeCreator`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::unique_ptr<Dimension> (Level &,Scheduler &)>::_Invoker_type` | _M_invoker


### `FeatureRefTraits::StackResultStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<std::reference_wrapper<FeatureRegistry> >` | mRegistry
16 | (8) `size_t` | mIndex


### `FeatureRefTraits::WeakStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<std::reference_wrapper<FeatureRegistry> >` | mRegistry
16 | (8) `size_t` | mIndex


### `Feature`
Offset | Type | Name
-|-|-|-
0 | (8) `IFeature` | baseclass_0
8 | (8) `Actor *` | mPlacer
16 | (8) `WorldChangeTransaction *` | mTransaction


### `FlowerFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock


### `FixedBiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeSource` | baseclass_0
8 | (8) `const Biome *` | mFixedBiome


### `FilterLayer<LayerFilters::AddIsland>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::Terrain> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::RemoveTooMuchOcean>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::Terrain> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddSnow>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::Terrain> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddIslandWithTemperature>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::PreBiome> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddEdgeCoolWarm>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::PreBiome> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddEdgeHeatIce>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::PreBiome> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddEdgeSpecial>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::PreBiome> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::BiomeInit>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<LayerValues::PreBiome> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddMushroomIsland>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::PromoteCenter>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::RiverInit>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::River>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<int> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::Smooth<bool> >::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<bool> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::RareBiomeSpot>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterContextSet`
Offset | Type | Name
-|-|-|-
0 | (616) `std::__array_traits<FilterContext,7>::_Type` | _M_elems


### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddBiomeIsland>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::Shore>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::Smooth<Biome *> >::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<Biome *> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FilterLayer<LayerFilters::AddOceanEdge>::ReaderType`
Offset | Type | Name
-|-|-|-
0 | (8) `const LayerDetails::BufferAccessor<BiomeTemperatureCategory> *` | mSourceData
8 | (4) `int32_t` | mTopLeft
12 | (4) `int32_t` | mW


### `FlagComponent<ActorTickedFlag>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FilterGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FilterGroup
8 | (4) `FilterGroup::CollectionType` | mCollectionType
16 | (24) `std::vector<std::shared_ptr<FilterGroup>>` | mChildren
40 | (24) `std::vector<std::shared_ptr<FilterTest>>` | mMembers


### `FlockingComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ActorUniqueID>` | mNeighborhood
24 | (12) `Vec3` | mCenterOfMass
36 | (12) `Vec3` | mGroupVelocity
48 | (12) `Vec3` | mGoalHeading
60 | (12) `Vec3` | mCurrentHeading
72 | (1) `bool` | mInWater
73 | (1) `bool` | mMatchVariant
74 | (1) `bool` | mUseCenterOfMass
75 | (1) `bool` | mIsLeader
76 | (1) `bool` | mInFlock
77 | (1) `bool` | mIsEnabled
78 | (1) `bool` | mHasTargetGoal
79 | (1) `bool` | mUsingDirection
80 | (4) `int` | mFlockLimit
84 | (4) `float` | mLonerChance
88 | (4) `float` | mGoalWeight
92 | (4) `float` | mInfluenceRadius
96 | (4) `float` | mBreachInfluence
100 | (4) `float` | mSeparationWeight
104 | (4) `float` | mSeparationThreshold
108 | (4) `float` | mCohesionWeight
112 | (4) `float` | mCohesionThreshold
116 | (4) `float` | mInnerCohesionThreshold
120 | (4) `float` | mMinHeight
124 | (4) `float` | mMaxHeight
128 | (4) `float` | mBlockDist
132 | (4) `float` | mBlockWeight
136 | (1) `bool` | mOverspeedRequired


### `FeatureToggles::SetupFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (Option *)>::_Invoker_type` | _M_invoker


### `FeatureToggles::LockFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool ()>::_Invoker_type` | _M_invoker


### `FeatureToggles::FeatureToggle`
Offset | Type | Name
-|-|-|-
0 | (4) `FeatureOptionID` | featureID
4 | (4) `FeatureOptionID` | dependencyFeatureID
8 | (8) `std::unique_ptr<Option>` | option
16 | (32) `FeatureToggles::SetupFunction` | setup
48 | (32) `FeatureToggles::LockFunction` | lock


### `FunctionManager::QueuedCommand`
Offset | Type | Name
-|-|-|-
0 | (8) `IFunctionEntry *` | mFunction
8 | (8) `const CommandOrigin *` | mOrigin


### `FloatRange`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | rangeMin
4 | (4) `float` | rangeMax


### `FileInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | filePath
32 | (8) `uint64_t` | fileSize
40 | (32) `std::string` | fileHash


### `FileChunkInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | chunkID
8 | (8) `uint64_t` | startByte
16 | (8) `uint64_t` | endByte


### `FileChunk`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | data
24 | (24) `FileChunkInfo` | info


### `FileArchiver::Result`
Offset | Type | Name
-|-|-|-
0 | (4) `FileArchiver::Outcome` | outcome
8 | (32) `Core::HeapPathBuffer` | fileName


### `FilterInputs`
Offset | Type | Name
-|-|-|-
0 | (2) `FilterSubject` | mSubject
8 | (48) `FilterInput` | mDomain
56 | (2) `FilterOperator` | mOperator
64 | (48) `FilterInput` | mValue


### `FilterInput`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterParamType` | mType
8 | (32) `std::string` | mString
40 | (4) `int` | mIValue
44 | (4) `float` | mFValue


### `floatArray`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<float>` | baseclass_0


### `FilterStringMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,FilterInputDefinition>` | baseclass_0


### `FilterGroup::Ptr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<FilterGroup,__gnu_cxx::_S_atomic>` | baseclass_0


### `FoodItemComponent::Effect`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | descriptionId
8 | (4) `int` | id
12 | (4) `int` | duration
16 | (4) `int` | amplifier
20 | (4) `float` | chance


### `FileArchiver::OperationCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (FileArchiver::Result &)>::_Invoker_type` | _M_invoker


### `FlagComponent<IgnoreAutomaticFeatureRules>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FlagComponent<DataDrivenBiomeSurface>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FlagComponent<SwampBiomeSurface>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FlagComponent<OceanFrozenBiomeSurface>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FlagComponent<NetherBiomeSurface>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FlagComponent<TheEndBiomeSurface>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FilteredTransformationAttributes<PreHillsEdgeTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PosibleTransformation>` | mTransformations


### `FilteredTransformationAttributes<PostShoreEdgeTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PosibleTransformation>` | mTransformations


### `FlagComponent<NoiseBasedColorPalette>`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `FeatureLoading::FeatureRootParseContext`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<std::string >` | mFeatureName
8 | (8) `std::reference_wrapper<IWorldRegistriesProvider>` | mRegistryProvider
16 | (8) `std::unique_ptr<FeatureLoading::AbstractFeatureHolder>` | mFeatureHolder


### `FlatWorldGeneratorOptions`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mEncodingVersion
8 | (24) `std::vector<BlockLayer>` | mBlockLayers
32 | (4) `int` | mBiomeId
40 | (16) `Json::Value` | mStructureOptions
56 | (4) `int` | mTotalLayers


### `FeedItem`
Offset | Type | Name
-|-|-|-
0 | (8) `const Item *` | mItem
8 | (4) `int` | mValue
16 | (24) `std::vector<FeedItem::Effect>` | mEffects


### `FeedItem::Effect`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | descriptionId
32 | (4) `int` | id
36 | (4) `int` | duration
40 | (4) `int` | amplifier
44 | (4) `float` | chance


### `FullPlayerInventoryWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayerInventoryProxy *` | mPlayerInventory
8 | (8) `SimpleContainer *` | mArmorInventory
16 | (8) `SimpleContainer *` | mHandInventory
24 | (8) `InventoryTransactionManager *` | mTransactionManager
32 | (8) `Player *` | mPlayer


### `FoliageColor::Palette`
Offset | Type | Name
-|-|-|-
0 | (262144) `std::__array_traits<int,65536>::_Type` | _M_elems


### `fd_set`
Offset | Type | Name
-|-|-|-
0 | (128) `__fd_mask[16]` | fds_bits


### `FileSystemFileAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `IFileAccess` | baseclass_0
8 | (4) `FileSystemMode` | mMode
16 | (8) `FileSystemFileAccess::FileSystemFileReadAccess` | mReadInterface
24 | (8) `FileSystemFileAccess::FileSystemFileWriteAccess` | mWriteInterface


### `FileSystemFileAccess::FileSystemFileReadAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `IFileReadAccess` | baseclass_0


### `FileSystemFileAccess::FileSystemFileWriteAccess`
Offset | Type | Name
-|-|-|-
0 | (8) `IFileWriteAccess` | baseclass_0


### `FilterParamDefinition`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterParamType` | mType
4 | (4) `FilterParamRequirement` | mRequirement
8 | (32) `std::string` | mDescription
40 | (48) `FilterInput` | mDefault
88 | (56) `FilterStringMap` | mStringMap
144 | (1) `FilterParamOption` | mParamOption


### `FileAccessTransforms`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FileAccessTransforms


### `FilterInputDefinition`
Offset | Type | Name
-|-|-|-
0 | (48) `FilterInput` | mInput
48 | (32) `std::string` | mDescription


### `FriendlySize`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | bytes


### `FileArchiver`
Offset | Type | Name
-|-|-|-
0 | (16) `std::enable_shared_from_this<FileArchiver>` | baseclass_0
16 | (12) `Core::ZipUtils::ZipProgress` | mProgress
32 | (24) `std::promise<FileArchiver::Result>` | mLastResult
56 | (4) `FileArchiver::State` | mCurrentState
64 | (8) `Core::FilePathManager *` | mFilePathManager
72 | (32) `std::function<void (const std::string &)>` | mDisplayMessageCallback
104 | (8) `ResourcePackRepository *` | mResourcePackRepository
112 | (8) `std::unique_ptr<TaskGroup>` | mIOTaskGroup


### `FishingHook::_fishPosEvent::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `FishingHook::_fishhookEvent::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `FishingHook::_fishTeaseEvent::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Fish::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `FilterTest::Definition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mDescription
64 | (8) `const FilterParamDefinition *` | mSubjectDefinition
72 | (8) `const FilterParamDefinition *` | mDomainDefinition
80 | (8) `const FilterParamDefinition *` | mOperatorDefinition
88 | (8) `const FilterParamDefinition *` | mValueDefinition
96 | (32) `std::function<std::shared_ptr<FilterTest> ()>` | mFactory


### `FilterTestDaytime`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `FilterTest:96`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FilterTest
8 | (2) `FilterSubject` | mSubject
10 | (2) `FilterOperator` | mOperator


### `FilterTestClock`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestMoonIntensity`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestMoonPhase`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestDistanceToNearestPlayer`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTest`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FilterTest
8 | (2) `FilterSubject` | mSubject
10 | (2) `FilterOperator` | mOperator


### `FilterTestDifficulty`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `FilterTestGameRule`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (32) `std::string` | mGameRule
48 | (1) `bool` | mValue


### `FilterTestHourlyClock`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0
16 | (4) `int` | mValue


### `FilterTestBiome`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `FilterTestBiomeHasTag`
Offset | Type | Name
-|-|-|-
0 | (72) `SimpleTagIDFilterTest` | baseclass_0


### `FilterTestBiomeSnowCovered`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `FilterTestBiomeHumid`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `FilterTestTemperatureType`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `FilterTestTemperatureValue`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestBrightness`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestAltitude`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleIntFilterTest` | baseclass_0


### `FilterTestHasTradeSupply`
Offset | Type | Name
-|-|-|-
0 | (16) `SimpleBoolFilterTest` | baseclass_0


### `FancyTreeFeature::FoliageCoords`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | baseclass_0
12 | (4) `int` | mBranchBase


### `FeatureRefTraits::OwnerStorage`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<std::reference_wrapper<FeatureRegistry> >` | mRegistry
16 | (8) `size_t` | mIndex


### `FILE`
```
typedef _IO_FILE FILE;

```

### `FlockingSystem`
```
struct __cppobj FlockingSystem : ITickingSystem
{
};

```

### `Factory<Dimension,Level &,Scheduler &>`
```
struct Factory<Dimension,Level &,Scheduler &>
{
  Factory<Dimension,Level &,Scheduler &>::FactoryMap mFactoryMap;
};

```

### `Factory<Dimension,Level &,Scheduler &>::FactoryMap`
```
typedef std::unordered_map<std::string,std::function<std::unique_ptr<Dimension> (Level &,Scheduler &)>> Factory<Dimension,Level &,Scheduler &>::FactoryMap;

```

### `FeatureRegistry`
```
struct FeatureRegistry
{
  std::vector<std::unique_ptr<IFeature>> mFeatureRegistry;
  std::vector<OwnerPtrT<FeatureRefTraits>> mFeatureSlots;
  std::unordered_map<StringKey,unsigned long> mFeatureLookupMap;
};

```

### `FeatureLoading::AbstractFeatureHolder`
```
struct FeatureLoading::AbstractFeatureHolder
{
  __int8 gap0[1];
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Arbitrary> >`
```
struct FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Arbitrary> >
{
  AggregateFeature<PlaceType::Arbitrary> *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Sequential> >`
```
struct FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Sequential> >
{
  AggregateFeature<PlaceType::Sequential> *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<OreFeature>`
```
struct FeatureLoading::ConcreteFeatureHolder<OreFeature>
{
  OreFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<ScatterFeature>`
```
struct FeatureLoading::ConcreteFeatureHolder<ScatterFeature>
{
  ScatterFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature>`
```
struct FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature>
{
  SingleBlockFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature>`
```
struct FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature>
{
  StructureTemplateFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature>`
```
struct FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature>
{
  WeightedRandomFeature *mFeaturePtr;
};

```

### `FossilFeature`
```
struct __cppobj FossilFeature : Feature
{
};

```

### `FancyTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) FancyTreeFeature : TreeFeature:288
{
  const int mHeightVariance;
  const float mTrunkHeightScale;
  const float mBranchSlope;
  const float mWidthScale;
  const float mFoliageDensity;
  const int mTrunkWidth;
  const int mFoliageHeight;
  const int mMinAllowedHeight;
};

```

### `FeatureRefTraits::OwnerStackRef`
```
typedef FeatureRefTraits::StackRef FeatureRefTraits::OwnerStackRef;

```

### `FeatureRefTraits::StackRef`
```
typedef IFeature FeatureRefTraits::StackRef;

```

### `FeatureRefTraits`
```
struct FeatureRefTraits
{
  __int8 gap0[1];
};

```

### `FeatureTypeFactory`
```
struct FeatureTypeFactory
{
  JsonUtil::JsonSchemaRoot<FeatureLoading::FeatureRootParseContext> mSchema;
};

```

### `Facing`
```
struct Facing
{
  __int8 gap0[1];
};

```

### `FlatWorldGenerator`
```
struct __cppobj FlatWorldGenerator : ChunkSource, WorldGenerator
{
  std::vector<const Block *> mPrototypeBlocks;
  Height mPrototypeHeight;
  const Biome *mBiome;
  const PerlinSimplexNoise noise;
  std::unique_ptr<RandomScatteredLargeFeature> mScatteredFeature;
  std::unique_ptr<OceanMonumentFeature> mOceanMonumentFeature;
};

```

### `FeaturePoolElement`
```
struct __cppobj FeaturePoolElement : StructurePoolElement
{
  const Feature *mFeature;
};

```

### `FilterLayer<LayerFilters::AddIsland>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddIsland> : UnaryLayer<typename AddIsland::OutputType,typename AddIsland::InputType>:328
{
  LayerFilters::AddIsland mFilter;
};

```

### `FilterLayer<LayerFilters::RemoveTooMuchOcean>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::RemoveTooMuchOcean> : UnaryLayer<typename RemoveTooMuchOcean::OutputType,typename RemoveTooMuchOcean::InputType>:328
{
  LayerFilters::RemoveTooMuchOcean mFilter;
};

```

### `FilterLayer<LayerFilters::AddSnow>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddSnow> : UnaryLayer<typename AddSnow::OutputType,typename AddSnow::InputType>:328
{
  LayerFilters::AddSnow mFilter;
};

```

### `FilterLayer<LayerFilters::AddIslandWithTemperature>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddIslandWithTemperature> : UnaryLayer<typename AddIslandWithTemperature::OutputType,typename AddIslandWithTemperature::InputType>:328
{
  LayerFilters::AddIslandWithTemperature mFilter;
};

```

### `FilterLayer<LayerFilters::AddEdgeCoolWarm>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddEdgeCoolWarm> : UnaryLayer<typename AddEdgeCoolWarm::OutputType,typename AddEdgeCoolWarm::InputType>:328
{
  LayerFilters::AddEdgeCoolWarm mFilter;
};

```

### `FilterLayer<LayerFilters::AddEdgeHeatIce>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddEdgeHeatIce> : UnaryLayer<typename AddEdgeHeatIce::OutputType,typename AddEdgeHeatIce::InputType>:328
{
  LayerFilters::AddEdgeHeatIce mFilter;
};

```

### `FilterLayer<LayerFilters::AddEdgeSpecial>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddEdgeSpecial> : UnaryLayer<typename AddEdgeSpecial::OutputType,typename AddEdgeSpecial::InputType>:328
{
  LayerFilters::AddEdgeSpecial mFilter;
};

```

### `FilterLayer<LayerFilters::BiomeInit>`
```
struct __cppobj FilterLayer<LayerFilters::BiomeInit> : UnaryLayer<typename BiomeInit::OutputType,typename BiomeInit::InputType>
{
  LayerFilters::BiomeInit mFilter;
};

```

### `FilterLayer<LayerFilters::AddMushroomIsland>`
```
struct __cppobj FilterLayer<LayerFilters::AddMushroomIsland> : UnaryLayer<typename AddMushroomIsland::OutputType,typename AddMushroomIsland::InputType>
{
  LayerFilters::AddMushroomIsland mFilter;
};

```

### `FilterLayer<LayerFilters::PromoteCenter>`
```
struct __cppobj FilterLayer<LayerFilters::PromoteCenter> : UnaryLayer<typename PromoteCenter::OutputType,typename PromoteCenter::InputType>
{
  LayerFilters::PromoteCenter mFilter;
};

```

### `FilterLayer<LayerFilters::RiverInit>`
```
struct __cppobj FilterLayer<LayerFilters::RiverInit> : UnaryLayer<typename RiverInit::OutputType,typename RiverInit::InputType>
{
  LayerFilters::RiverInit mFilter;
};

```

### `FilterLayer<LayerFilters::River>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::River> : UnaryLayer<typename River::OutputType,typename River::InputType>:328
{
  LayerFilters::River mFilter;
};

```

### `FilterLayer<LayerFilters::Smooth<bool> >`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::Smooth<bool> > : UnaryLayer<typename Smooth<bool>::OutputType,typename Smooth<bool>::InputType>:328
{
  LayerFilters::Smooth<bool> mFilter;
};

```

### `FilterLayer<LayerFilters::RareBiomeSpot>`
```
struct __cppobj FilterLayer<LayerFilters::RareBiomeSpot> : UnaryLayer<typename RareBiomeSpot::OutputType,typename RareBiomeSpot::InputType>
{
  LayerFilters::RareBiomeSpot mFilter;
};

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >`
```
struct __cppobj FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > > : UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >::InputType>
{
  LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > mFilter;
};

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >`
```
struct __cppobj FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > > : UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >::InputType>
{
  LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > mFilter;
};

```

### `FilterLayer<LayerFilters::AddBiomeIsland>`
```
struct __cppobj FilterLayer<LayerFilters::AddBiomeIsland> : UnaryLayer<typename AddBiomeIsland::OutputType,typename AddBiomeIsland::InputType>
{
  LayerFilters::AddBiomeIsland mFilter;
};

```

### `FilterLayer<LayerFilters::Shore>`
```
struct __cppobj FilterLayer<LayerFilters::Shore> : UnaryLayer<typename Shore::OutputType,typename Shore::InputType>
{
  LayerFilters::Shore mFilter;
};

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >`
```
struct __cppobj FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > > : UnaryLayer<typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::OutputType,typename FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >::InputType>
{
  LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > mFilter;
};

```

### `FilterLayer<LayerFilters::Smooth<Biome *> >`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::Smooth<Biome *> > : UnaryLayer<typename Smooth<Biome *>::OutputType,typename Smooth<Biome *>::InputType>:328
{
  LayerFilters::Smooth<Biome *> mFilter;
};

```

### `FilterLayer<LayerFilters::AddOceanEdge>`
```
struct __cppobj __attribute__((aligned(8))) FilterLayer<LayerFilters::AddOceanEdge> : UnaryLayer<typename AddOceanEdge::OutputType,typename AddOceanEdge::InputType>:328
{
  LayerFilters::AddOceanEdge mFilter;
};

```

### `FilterContext`
```
struct FilterContext
{
  const Actor *mHost;
  const Actor *mSubject;
  const VariantParameterList *mParams;
  const BlockSource *mRegion;
  const Dimension *mDimension;
  const Level *mLevel;
  const Biome *mBiome;
  BlockPos mPos;
  const Block *mBlock;
  const TagRegistry *mTagRegistry;
};

```

### `FilterLayer<LayerFilters::AddIsland>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain> FilterLayer<LayerFilters::AddIsland>::LayerData;

```

### `FilterLayer<LayerFilters::RemoveTooMuchOcean>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain> FilterLayer<LayerFilters::RemoveTooMuchOcean>::LayerData;

```

### `FilterLayer<LayerFilters::AddSnow>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::Terrain> FilterLayer<LayerFilters::AddSnow>::LayerData;

```

### `FilterLayer<LayerFilters::AddIslandWithTemperature>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> FilterLayer<LayerFilters::AddIslandWithTemperature>::LayerData;

```

### `FilterLayer<LayerFilters::AddEdgeCoolWarm>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> FilterLayer<LayerFilters::AddEdgeCoolWarm>::LayerData;

```

### `FilterLayer<LayerFilters::AddEdgeHeatIce>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> FilterLayer<LayerFilters::AddEdgeHeatIce>::LayerData;

```

### `FilterLayer<LayerFilters::AddEdgeSpecial>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> FilterLayer<LayerFilters::AddEdgeSpecial>::LayerData;

```

### `FilterLayer<LayerFilters::BiomeInit>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,LayerValues::PreBiome> FilterLayer<LayerFilters::BiomeInit>::LayerData;

```

### `FilterLayer<LayerFilters::AddMushroomIsland>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::AddMushroomIsland>::LayerData;

```

### `FilterLayer<LayerFilters::PromoteCenter>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::PromoteCenter>::LayerData;

```

### `FilterLayer<LayerFilters::RiverInit>::LayerData`
```
typedef LayerDetails::WorkingData<int,Biome *> FilterLayer<LayerFilters::RiverInit>::LayerData;

```

### `FilterLayer<LayerFilters::River>::LayerData`
```
typedef LayerDetails::WorkingData<bool,int> FilterLayer<LayerFilters::River>::LayerData;

```

### `FilterLayer<LayerFilters::Smooth<bool> >::LayerData`
```
typedef LayerDetails::WorkingData<bool,bool> FilterLayer<LayerFilters::Smooth<bool> >::LayerData;

```

### `FilterLayer<LayerFilters::RareBiomeSpot>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::RareBiomeSpot>::LayerData;

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >::LayerData;

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >::LayerData;

```

### `FilterLayer<LayerFilters::AddBiomeIsland>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::AddBiomeIsland>::LayerData;

```

### `FilterLayer<LayerFilters::Shore>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::Shore>::LayerData;

```

### `FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >::LayerData;

```

### `FilterLayer<LayerFilters::Smooth<Biome *> >::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> FilterLayer<LayerFilters::Smooth<Biome *> >::LayerData;

```

### `FilterLayer<LayerFilters::AddOceanEdge>::LayerData`
```
typedef LayerDetails::WorkingData<BiomeTemperatureCategory,BiomeTemperatureCategory> FilterLayer<LayerFilters::AddOceanEdge>::LayerData;

```

### `FloatTag`
```
struct __cppobj __attribute__((aligned(8))) FloatTag : Tag
{
  float data;
};

```

### `FeatureToggles`
```
struct FeatureToggles
{
  FeatureToggles::FeatureTogglesArray mFeatures;
  Core::HeapPathBuffer mFilePath;
};

```

### `FeatureToggles::FeatureTogglesArray`
```
typedef std::vector<FeatureToggles::FeatureToggle> FeatureToggles::FeatureTogglesArray;

```

### `FireworksRecipe`
```
struct __cppobj FireworksRecipe : MultiRecipe
{
  Recipe::ResultList mResult;
};

```

### `FloatOption`
```
struct __cppobj __attribute__((aligned(8))) FloatOption : Option
{
  const float VALUE_MIN;
  const float VALUE_MAX;
  float mValue;
  float mDefaultValue;
  const float DELTA;
};

```

### `FunctionManager`
```
struct FunctionManager
{
  int (**_vptr$FunctionManager)(void);
  const GameRule *mGameRule;
  bool mIsProcessingStack;
  std::vector<FunctionManager::QueuedCommand> mCommandList;
  std::unordered_map<const CommandOrigin *,FunctionManager::OriginMapping> mOriginMap;
  std::unique_ptr<ICommandDispatcher> mCommandDispatcher;
  std::unique_ptr<CommandOrigin> mTickOrigin;
  std::unordered_map<std::string,std::unique_ptr<FunctionEntry>> mFunctions;
  std::vector<FunctionEntry *> mTickFunctions;
};

```

### `FamilyTypeDescription`
```
struct __cppobj FamilyTypeDescription : PropertyDescription
{
  Util::hashStringSet mFamilySet;
};

```

### `FireImmuneDescription`
```
struct __cppobj FireImmuneDescription : PropertyDescription
{
};

```

### `FloatsInLiquidDescription`
```
struct __cppobj FloatsInLiquidDescription : PropertyDescription
{
};

```

### `FlyingSpeedDescription`
```
struct __cppobj __attribute__((aligned(8))) FlyingSpeedDescription : PropertyDescription
{
  float mValue;
};

```

### `FootSizeDescription`
```
struct __cppobj __attribute__((aligned(8))) FootSizeDescription : PropertyDescription
{
  float mValue;
};

```

### `FrictionModifierDescription`
```
struct __cppobj __attribute__((aligned(8))) FrictionModifierDescription : PropertyDescription
{
  float mValue;
};

```

### `FurnaceContainerManagerModel`
```
struct __cppobj FurnaceContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  int mLastTickCount;
  int mLastLitTime;
  int mLastLitDuration;
  int mLastStoredXP;
  int mLastInputId;
  int mLastInputAux;
  std::string mLastOutputName;
  int mLastResultDisplayId;
  const BlockActorType mBlockActorType;
  const ContainerEnumName mIngredientContainerName;
  const Util::HashString mRecipeTag;
};

```

### `FillingContainer`
```
struct __cppobj FillingContainer : Container
{
  FillingContainer::ItemList mItems;
  Player *mPlayer;
};

```

### `FunctionManager::OriginMapping`
```
struct __attribute__((aligned(8))) FunctionManager::OriginMapping
{
  std::unique_ptr<CommandOrigin> mOrigin;
  uint32_t mRefCount;
};

```

### `FunctionEntry`
```
struct __cppobj __attribute__((aligned(8))) FunctionEntry : IFunctionEntry
{
  std::vector<std::unique_ptr<IFunctionEntry>> mCommandList;
  FunctionState mState;
};

```

### `FileUploadManager`
```
struct __cppobj FileUploadManager : std::enable_shared_from_this<FileUploadManager>
{
  int (**_vptr$FileUploadManager)(void);
  FileInfo mFile;
  FileUploadManager::MultiPartStreamHelper mMultiPartHelper;
  UploadState mState;
  UploadError mUploadError;
  std::shared_ptr<IFilePicker> mFilePicker;
  std::shared_ptr<IFileChunkUploader> mFileUploader;
  TaskGroup *mIOTaskGroup;
  std::weak_ptr<FileArchiver> mFileArchiver;
  bool mUploadAllAtOnce;
  bool mContinueOnReception;
  bool mUseStream;
  MPMCQueue<std::function<void ()> > mCallbackQueue;
};

```

### `FileUploadManager::MultiPartStreamHelper`
```
struct FileUploadManager::MultiPartStreamHelper
{
  bool needHeader;
  bool needTrailer;
  std::string header;
  std::string trailer;
  uint64_t currentFileByte;
  uint64_t totalFileByte;
  uint64_t totalStreamSize;
};

```

### `FileChunkManager`
```
struct FileChunkManager
{
  uint64_t mTotalSize;
  uint32_t mChunkSize;
  int mTotalNbChunks;
  int mRequestedChunks;
  int mReceivedChunks;
  int mWrittenChunks;
  std::vector<FileChunkInfo> mChunkInfo;
  MovePriorityQueue<FileChunk,std::less<FileChunk> > mChunkQueue;
};

```

### `FishingHook`
```
struct __cppobj FishingHook : Actor
{
  const float SHOOT_SPEED;
  const float SHOOT_POWER;
  const int NUM_PERCENTAGE_STEPS;
  bool mInGround;
  BlockPos mBlockPos;
  float mFishAngle;
  int mLife;
  int mFlightTime;
  int mTimeUntilHooked;
  int mTimeUntilLured;
  int mTimeUntilNibble;
  int mFishingSpeed;
  int mLerpSteps;
  Vec3 mLerpPos;
  Vec3 mLerpDir;
  float mLerpRotX;
  float mLerpRotY;
  double mBobTimer;
};

```

### `Fish`
```
struct __cppobj Fish : WaterAnimal
{
  float mAnimationAmount;
  float mAnimationAmountPrev;
};

```

### `FallingBlock`
```
struct __cppobj __attribute__((aligned(8))) FallingBlock : Actor
{
  bool mCreative;
  FallingBlock::State mState;
  int mWaitTicks;
  int mTime;
  bool mCancelDrop;
  bool mHurtEntities;
  int mFallDamageMax;
  float mFallDamageAmount;
  std::unique_ptr<CompoundTag> mFallingBlockSerId;
  NewBlockID mFallingBlockId;
  DataID mFallingBlockData;
};

```

### `FireworksRocketActor`
```
struct __cppobj __attribute__((aligned(8))) FireworksRocketActor : Actor
{
  int mLife;
  int mLifeTime;
  bool mDispensed;
};

```

### `FurnaceBlockActor`
```
struct __cppobj __attribute__((aligned(8))) FurnaceBlockActor : BlockActor, Container:1952
{
  int mLitTime;
  int mLitDuration;
  int mCookingProgress;
  unsigned int mStoredXP;
  ItemStack mItems[3];
  bool mDirty[3];
  std::unordered_set<ActorUniqueID> mPlayers;
  const Util::HashString mRecipeTag;
  const int mBurnInterval;
  LevelSoundEvent mSmeltSoundEvent;
  int mSoundTick;
  int mSoundTickTarget;
  Random mRandom;
  const Block *mUnlitFurnace;
  const Block *mLitFurnace;
  ItemInstance mLastFuelItem;
  bool mCanBeFinished;
  bool mFinished;
  bool mNoDrop;
};

```

### `FlyMoveControl`
```
struct __cppobj FlyMoveControl : MoveControl
{
};

```

### `FloatNavigation`
```
struct __cppobj FloatNavigation : PathNavigation
{
};

```

### `FlyingPathNavigation`
```
struct __cppobj __attribute__((aligned(8))) FlyingPathNavigation : PathNavigation
{
  bool mHadGravity;
  bool mCanPathFromAir;
};

```

### `FindUnderwaterTreasureGoal`
```
struct __cppobj __attribute__((aligned(8))) FindUnderwaterTreasureGoal : Goal
{
  Mob *mMob;
  BlockPos mDestination;
  Vec3 mLastPos;
  int mBlocksCounter;
  int mBlocksToTravel;
  int mTimeToRecalcPath;
  int mFailedPathing;
  int mTotalFailedPathing;
  float mSpeed;
  int mSearchArea;
};

```

### `FindCoverGoal`
```
struct __cppobj __attribute__((aligned(8))) FindCoverGoal : Goal
{
  Mob *mMob;
  float mSpeed;
  int mCooldownTicks;
  Tick mCooldownTimer;
  Vec3 mWantedPosition;
};

```

### `FleeSunGoal`
```
struct __cppobj FleeSunGoal : FindCoverGoal
{
};

```

### `FloatGoal`
```
struct __cppobj FloatGoal : Goal
{
  Mob *mMob;
};

```

### `FollowOwnerGoal`
```
struct __cppobj __attribute__((aligned(8))) FollowOwnerGoal : Goal
{
  Mob *mMob;
  TempEPtr<Mob> mOwner;
  float mSpeed;
  int mTimeToRecalcPath;
  float mStartDistance;
  float mStopDistance;
  bool mOldAvoidWater;
  bool mOldAvoidPortals;
};

```

### `FollowParentGoal`
```
struct __cppobj FollowParentGoal : Goal
{
  Mob *mMob;
  TempEPtr<Mob> mParent;
  float mSpeed;
  int mTimeToRecalcPath;
};

```

### `FollowCaravanGoal`
```
struct __cppobj FollowCaravanGoal : Goal
{
  Mob *mMob;
  TempEPtr<Mob> mParent;
  float mSpeedModifier;
  float mSpeedModifierO;
  int mDistanceCheckCounter;
  int mCaravanSize;
  const std::vector<MobDescriptor> mTargetTypes;
};

```

### `FollowMobGoal`
```
struct __cppobj FollowMobGoal : Goal
{
  Mob *mMob;
  TempEPtr<Mob> mFollowingMob;
  float mSpeed;
  int mTimeToRecalcPath;
  float mStopDistance;
  int mSearchArea;
};

```

### `FollowTargetCaptainGoal`
```
struct __cppobj __attribute__((aligned(8))) FollowTargetCaptainGoal : MoveTowardsTargetGoal:672
{
  __int16 mLocateAttempts;
  float mFollowDistSq;
};

```

### `FindMountGoal`
```
struct __cppobj FindMountGoal : Goal
{
  TempEPtr<Actor> mTarget;
  float mTargetDist;
  int mTimeToRecalcPath;
  int mStartCounter;
  int mStartDelay;
  bool mAvoidWater;
  bool mTargetNeeded;
  float mMountDistance;
  int mFailedAttemptsCounter;
  int mMaxFailedAttempts;
  Mob *mMob;
  Unique<Path> mPath;
};

```

### `FloatWanderGoal`
```
struct __cppobj FloatWanderGoal : Goal
{
  Mob *mMob;
  Vec3 mTargetPos;
  int mFloatDuration;
  float mFloatXZDist;
  float mFloatYDist;
  float mYOffset;
  bool mMustReach;
  bool mRandomReselect;
  FloatRange mFloatDurationRange;
};

```

### `FollowFlockGoal`
```
struct __cppobj __attribute__((aligned(8))) FollowFlockGoal : Goal
{
  Mob *mMob;
  int mCooldownTicks;
  int mNotInFlockTicks;
  float mSpeed;
};

```

### `FireworkChargeItem`
```
struct __cppobj FireworkChargeItem : Item
{
};

```

### `FillingContainer::ItemList`
```
typedef std::vector<ItemStack> FillingContainer::ItemList;

```

### `FoodItemComponent`
```
struct FoodItemComponent
{
  const Item *mOwner;
  int mNutrition;
  float mSaturationModifier;
  std::string mUsingConvertsTo;
  FoodItemComponent::OnUseAction mOnUseAction;
  Vec3 mOnUseRange;
  CooldownType mCoolDownType;
  int mCooldownTime;
  bool mCanAlwaysEat;
  std::vector<FoodItemComponent::Effect> mEffects;
  std::vector<unsigned int> mRemoveEffects;
};

```

### `Fireball`
```
struct __cppobj __attribute__((aligned(8))) Fireball : Actor
{
  ActorUniqueID ownerId;
  bool mInGround;
  MovementInterpolator mInterpolation;
};

```

### `Fireball:17696`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) Fireball:17696 : Actor
{
  ActorUniqueID ownerId;
  bool mInGround;
  __attribute__((aligned(4))) MovementInterpolator mInterpolation;
};

```

### `FreezeOnHitSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) FreezeOnHitSubcomponent : OnHitSubcomponent
{
  FreezeOnHitSubcomponent::Shape mShape;
  float mSize;
  bool mSnapToBlock;
};

```

### `FilteredContainerModel`
```
struct __cppobj FilteredContainerModel : ExpandoContainerModel
{
  bool mDoExpandoGroups;
  bool mIsFiltering;
  int mFilteredItemCount;
  std::vector<ContainerItemStack> mSavedItems;
  std::vector<ContainerItemStack> mActiveFilteredExpandableSetHeads;
  std::function<FilterResult (const ContainerItemStack &)> mFilterRule;
};

```

### `FilterTest::Ptr`
```
typedef std::shared_ptr<FilterTest> FilterTest::Ptr;

```

### `FertilizerItem`
```
struct __cppobj __attribute__((aligned(8))) FertilizerItem : Item
{
  FertilizerType mType;
};

```

### `FireworksItem`
```
struct __cppobj FireworksItem : Item
{
};

```

### `FlintAndSteelItem`
```
struct __cppobj FlintAndSteelItem : Item
{
};

```

### `FishingRodItem`
```
struct __cppobj FishingRodItem : Item
{
  TextureUVCoordinateSet mFrame[2];
};

```

### `FireChargeItem`
```
struct __cppobj FireChargeItem : Item
{
};

```

### `FishingEnchant`
```
struct __cppobj FishingEnchant : Enchant
{
};

```

### `FrostWalkerEnchant`
```
struct __cppobj FrostWalkerEnchant : Enchant
{
};

```

### `FilePickerSettings`
```
struct FilePickerSettings
{
  std::function<void (std::shared_ptr<FilePickerSettings>)> onCancel;
  std::function<void (bool)> onOperationComplete;
  std::function<void (std::shared_ptr<FilePickerSettings>,const Core::Path &)> onPick;
  std::vector<FilePickerSettings::FileDescription> mFileDescriptions;
  size_t mDefaultFileExtensionIndex;
  FilePickerSettings::PickerType mPickerType;
  std::string mDefaultFileName;
  std::string mDefaultAlbumName;
  std::string mFilePickerTitle;
};

```

### `FilePickerSettings::FileDescription`
```
struct FilePickerSettings::FileDescription
{
  std::string Extension;
  std::string Name;
};

```

### `FireBlock`
```
struct __cppobj __attribute__((aligned(8))) FireBlock : BlockLegacy
{
  AABB mAabb;
};

```

### `FarmBlock`
```
struct __cppobj FarmBlock : BlockLegacy
{
};

```

### `FlowerPotBlockActor`
```
struct __cppobj FlowerPotBlockActor : BlockActor
{
  const Block *mPlant;
};

```

### `FlowerBlock`
```
struct __cppobj __attribute__((aligned(8))) FlowerBlock : BushBlock
{
  FlowerBlock::Type mType;
};

```

### `FurnaceBlock`
```
struct __cppobj __attribute__((aligned(8))) FurnaceBlock : ActorBlock
{
  const bool mLit;
};

```

### `FenceBlock`
```
struct __cppobj FenceBlock : BlockLegacy
{
};

```

### `FenceGateBlock`
```
struct __cppobj FenceGateBlock : BlockLegacy
{
};

```

### `FlowerPotBlock`
```
struct __cppobj FlowerPotBlock : ActorBlock
{
};

```

### `FrostedIceBlock`
```
struct __cppobj FrostedIceBlock : BlockLegacy
{
};

```

### `FeatureLoading::FeatureSchemaNode<AggregateFeature<(PlaceType)0> >`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Arbitrary> > > FeatureLoading::FeatureSchemaNode<AggregateFeature<(PlaceType)0> >;

```

### `FeatureLoading::FeatureSchemaNode<AggregateFeature<(PlaceType)1> >`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Sequential> > > FeatureLoading::FeatureSchemaNode<AggregateFeature<(PlaceType)1> >;

```

### `FeatureLoading::FeatureSchemaNode<AggregateFeature<PlaceType::Arbitrary> >`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Arbitrary> > > FeatureLoading::FeatureSchemaNode<AggregateFeature<PlaceType::Arbitrary> >;

```

### `FeatureLoading::FeatureSchemaNode<AggregateFeature<PlaceType::Sequential> >`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<AggregateFeature<PlaceType::Sequential> > > FeatureLoading::FeatureSchemaNode<AggregateFeature<PlaceType::Sequential> >;

```

### `FeatureLoading::FeatureSchemaNode<OreFeature>`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<OreFeature> > FeatureLoading::FeatureSchemaNode<OreFeature>;

```

### `FeatureLoading::FeatureSchemaNode<ScatterFeature>`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<ScatterFeature> > FeatureLoading::FeatureSchemaNode<ScatterFeature>;

```

### `FeatureLoading::FeatureSchemaNode<SingleBlockFeature>`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature> > FeatureLoading::FeatureSchemaNode<SingleBlockFeature>;

```

### `FeatureLoading::FeatureSchemaNode<StructureTemplateFeature>`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature> > FeatureLoading::FeatureSchemaNode<StructureTemplateFeature>;

```

### `FeatureLoading::FeatureSchemaNode<WeightedRandomFeature>`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext>,FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature> > FeatureLoading::FeatureSchemaNode<WeightedRandomFeature>;

```

### `FlatWorldGeneratorOptions::getDefault::$7EF7C94BEAB75C6CEF4ADFB99B570420`
```
struct FlatWorldGeneratorOptions::getDefault::$7EF7C94BEAB75C6CEF4ADFB99B570420
{
  __int8 gap0[1];
};

```

### `FitDoubleXYRoom`
```
struct __cppobj FitDoubleXYRoom : MonumentRoomFitter
{
};

```

### `FitDoubleYZRoom`
```
struct __cppobj FitDoubleYZRoom : MonumentRoomFitter
{
};

```

### `FitDoubleZRoom`
```
struct __cppobj FitDoubleZRoom : MonumentRoomFitter
{
};

```

### `FitDoubleXRoom`
```
struct __cppobj FitDoubleXRoom : MonumentRoomFitter
{
};

```

### `FitDoubleYRoom`
```
struct __cppobj FitDoubleYRoom : MonumentRoomFitter
{
};

```

### `FitSimpleTopRoom`
```
struct __cppobj FitSimpleTopRoom : MonumentRoomFitter
{
};

```

### `FitSimpleRoom`
```
struct __cppobj FitSimpleRoom : MonumentRoomFitter
{
};

```

### `FlockingDefinition`
```
struct FlockingDefinition
{
  bool mInWater;
  bool mMatchVariant;
  bool mUseCenterOfMass;
  int mLowFlockLimit;
  int mHighFlockLimit;
  float mGoalWeight;
  float mLonerChance;
  float mInfluenceRadius;
  float mBreachInfluence;
  float mSeparationWeight;
  float mSeparationThreshold;
  float mCohesionWeight;
  float mCohesionThreshold;
  float mInnerCohesionThres;
  float mMinHeight;
  float mMaxHeight;
  float mBlockDistance;
  float mBlockWeight;
};

```

### `FillCommand`
```
struct __cppobj __attribute__((aligned(8))) FillCommand : Command
{
  CommandPosition mFrom;
  CommandPosition mTo;
  const Block *mBlock;
  const Block *mReplaceBlock;
  FillCommand::FillMode mMode;
  int mBlockData;
  int mReplaceBlockData;
};

```

### `FunctionCommand`
```
struct __cppobj FunctionCommand : Command
{
  CommandFilePath mFilePath;
};

```

### `FormJsonValidator`
```
struct FormJsonValidator
{
  __int8 gap0[1];
};

```

### `Facing::Plane`
```
struct Facing::Plane
{
  __int8 gap0[1];
};

```

### `FindBlockDefinition`
```
struct __cppobj FindBlockDefinition : BehaviorDefinition
{
  std::string mBlockName;
  std::string mBlockNameId;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `FindBlockNode`
```
struct __cppobj __attribute__((aligned(4))) FindBlockNode : BehaviorNode
{
  const Block *mBlock;
  int mSearchRadius;
  bool mJumping;
};

```

### `FindActorDefinition`
```
struct __cppobj FindActorDefinition : BehaviorDefinition
{
  std::string mEntityName;
  std::string mEntityType;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `FindActorNode`
```
struct __cppobj __attribute__((aligned(8))) FindActorNode : BehaviorNode:480
{
  ActorType mActorType;
  int mSearchRadius;
};

```

### `FlyDefinition`
```
struct __cppobj FlyDefinition : BehaviorDefinition
{
  bool mShouldBeFlying;
  std::string mShouldBeFlyingId;
  bool mShouldThrowEventIfNoStateChangeNecessary;
  std::string mShouldThrowEventIfNoStateChangeNecessaryId;
};

```

### `FlyNode`
```
struct __cppobj __attribute__((aligned(8))) FlyNode : BehaviorNode:480
{
  bool mHaveCheckedFlightStatus;
  bool mJumpedLastTick;
  bool mJumpedOnce;
  bool mShouldBeFlying;
  bool mShouldThrowEventIfNoStateChangeNecessary;
};

```

### `FurnaceFuelContainerController`
```
struct __cppobj FurnaceFuelContainerController : ContainerController
{
};

```

### `FurnaceInputContainerController`
```
struct __cppobj FurnaceInputContainerController : ContainerController
{
  Util::HashString mRecipeTag;
};

```

### `FurnaceResultContainerController`
```
struct __cppobj FurnaceResultContainerController : ContainerController
{
};

```

### `FoliageColor`
```
struct FoliageColor
{
  __int8 gap0[1];
};

```

### `FaceDirectionalBlock`
```
struct __cppobj FaceDirectionalBlock : BlockLegacy
{
  bool mHorizontalOnly;
  float mYRotOffset;
};

```

### `FaceDirectionalActorBlock`
```
struct __cppobj FaceDirectionalActorBlock : ActorBlock
{
  bool mHorizontalOnly;
  float mYRotOffset;
};

```

### `FlushableEnv`
```
struct __cppobj FlushableEnv : leveldb::EnvWrapper
{
};

```

### `FlushableStorageAreaEnv`
```
struct __cppobj FlushableStorageAreaEnv : FlushableEnv
{
  std::shared_ptr<Core::FileStorageArea> mStorageArea;
};

```

### `FillContainerFunction`
```
struct __cppobj FillContainerFunction : LootItemFunction
{
  std::string mLootTable;
};

```

### `file_in_zip64_read_info_s`
```
struct __attribute__((aligned(8))) file_in_zip64_read_info_s
{
  char *read_buffer;
  z_stream stream;
  ZPOS64_T pos_in_zipfile;
  uLong stream_initialised;
  ZPOS64_T offset_local_extrafield;
  uInt size_local_extrafield;
  ZPOS64_T pos_local_extrafield;
  ZPOS64_T total_out_64;
  uLong crc32;
  uLong crc32_wait;
  ZPOS64_T rest_read_compressed;
  ZPOS64_T rest_read_uncompressed;
  zlib_filefunc64_32_def z_filefunc;
  voidpf filestream;
  uLong compression_method;
  ZPOS64_T byte_before_the_zipfile;
  int raw;
};

```

