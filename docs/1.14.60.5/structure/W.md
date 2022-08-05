# W
### `WhitelistFile`
Offset | Type | Name
-|-|-|-
0 | (32) `const Core::HeapPathBuffer` | mFilePath
32 | (8) `std::unique_ptr<Whitelist>` | mWhitelist


### `WorldTemplateManager`
Offset | Type | Name
-|-|-|-
0 | (8) `PackManifestFactory *` | mPackManifestFactory
8 | (8) `const IContentKeyProvider *` | mKeyProvider
16 | (8) `PackSourceFactory *` | mPackSourceFactory
24 | (8) `const Core::FilePathManager *` | mFilePathManager
32 | (8) `std::unique_ptr<PackSource>` | mLocalWorldSources
40 | (24) `std::vector<std::unique_ptr<WorldTemplateInfo>>` | mWorldTemplates
64 | (24) `std::vector<PackIdVersion>` | mLocalPremiumPackIds
88 | (40) `Bedrock::Threading::Mutex` | mInitializeMutex
128 | (1) `std::atomic<bool>` | mInitialized
129 | (1) `std::atomic<bool>` | mStorageDirectoryChangeRequest
136 | (1000) `WorldTemplatePackManifest` | mInvalidManifest
1136 | (264) `WorldTemplateInfo` | mInvalidWorldTemplate
1400 | (8) `std::unique_ptr<WorldTemplateManagerProxy>` | mProxy
1408 | (8) `std::unique_ptr<TaskGroup>` | mInitTaskGroup
1416 | (32) `WorldTemplateManager::SortMethod` | mSort


### `WorldTemplatePackManifest`
Offset | Type | Name
-|-|-|-
0 | (992) `PackManifest` | baseclass_0
992 | (4) `GameType` | mGameType


### `WorldTemplateInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mDescription
64 | (32) `std::string` | mAuthors
96 | (32) `std::string` | mVersion
128 | (32) `Core::HeapPathBuffer` | mPath
160 | (32) `std::string` | mGameType
192 | (32) `Core::HeapPathBuffer` | mWorldIconPath
224 | (1) `bool` | mWorldIconOverride
232 | (8) `const WorldTemplatePackManifest *` | mManifest
240 | (24) `std::vector<std::reference_wrapper<WorldTemplatePackSource>>` | mPacksInWorldTemplate


### `WorldTemplateManager::SortMethod`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (const std::unique_ptr<WorldTemplateInfo> &,const std::unique_ptr<WorldTemplateInfo> &)>::_Invoker_type` | _M_invoker


### `WorldTemplateLevelData`
Offset | Type | Name
-|-|-|-
0 | (24) `ContentIdentity` | mPremiumTemplateContentIdentity
24 | (136) `PackIdVersion` | mWorldTemplateIdentity
160 | (112) `BaseGameVersion` | mBaseGameVersion
272 | (1) `bool` | mIsFromWorldTemplate
273 | (1) `bool` | mIsWorldTemplateOptionLocked


### `WhitelistEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `IJsonSerializable` | baseclass_0
8 | (32) `std::string` | mName
40 | (16) `mce::UUID` | mUuid
56 | (32) `std::string` | mXuid
88 | (1) `bool` | mIgnoresPlayerLimit


### `WeakPtr<Item>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<Item> *` | pc


### `WeakRef<IFeature>`
Offset | Type | Name
-|-|-|-
0 | (24) `FeatureRefTraits::WeakStorage` | baseclass_0


### `WeakPtr<BlockLegacy>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockLegacy> *` | pc


### `WorldBlockTarget`
Offset | Type | Name
-|-|-|-
0 | (8) `IBlockPlacementTarget` | baseclass_0
8 | (8) `BlockSource *` | mBlockSource


### `WebToken`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mHeader
32 | (16) `Json::Value` | mHeaderInfo
48 | (32) `std::string` | mData
80 | (16) `Json::Value` | mDataInfo
96 | (32) `std::string` | mSignature


### `Weak<Village>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__weak_ptr<Village,__gnu_cxx::_S_atomic>` | baseclass_0


### `WeightedChoices<float>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<WeightedChoice<float>>` | mChoices


### `WebSocketPacketData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mIP


### `WorkerConfiguration`
Offset | Type | Name
-|-|-|-
0 | (28) `ThreadConfiguration:224` | baseclass_0
28 | (4) `uint32_t` | NumWorkers
32 | (1) `bool` | SuppressProfiling


### `WorldPackHistory`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mPackIdVersion
136 | (32) `std::string` | mUnlocalizedName
168 | (56) `std::unordered_map<std::string,std::string>` | mLocalizedNames
224 | (4) `int` | mSubpackCount
228 | (1) `bool` | mCanBeRedownloaded
232 | (16) `mce::UUID` | mSourceUUID


### `WorldTemplateManagerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (32) `std::function<int (const std::string &)>` | mFindTemplateIndexWithName


### `Whitelist::WhitelistEntryMatcher`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mXuid


### `WaterMovementComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mDragFactor


### `Weak<POIInstance>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__weak_ptr<POIInstance,__gnu_cxx::_S_atomic>` | baseclass_0


### `Weak<Village>_0`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__weak_ptr<Village,__gnu_cxx::_S_atomic>_0` | baseclass_0


### `WitherBoss::canDestroy::$FE6D2CA3CB829B3D63F7D33F5A8B933E`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockLegacy *` | legacyBlock


### `WeakPtr<BlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockItem> *` | pc


### `WeighedRandom::WeighedRandomItem`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRandomWeight


### `WeightedBiomeVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::pair<Biome *,unsigned int>>` | baseclass_0


### `WeightedBiomeAttributes<HillsTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `WeightedBiomeVector` | mBiomes


### `WeightedBiomeAttributes<MutateBiomeTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `WeightedBiomeVector` | mBiomes


### `WorldGenClimateMappingAttributes`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<WorldGenClimateMappingAttributes::WeightedTemperatureCategory>` | mClimateMappings


### `WeightedBiomeAttributes<RiverTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `WeightedBiomeVector` | mBiomes


### `WeightedBiomeAttributes<ShoreTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `WeightedBiomeVector` | mBiomes


### `WorldChangeTransaction`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mSource
8 | (8) `std::unique_ptr<WorldChangeTransaction::Data>` | mData


### `WeakRef<PerlinSimplexNoise>`
Offset | Type | Name
-|-|-|-
0 | (16) `SharePtrRefTraits<PerlinSimplexNoise>::WeakStorage` | baseclass_0


### `WoodlandMansionPieces::PlacementData`
Offset | Type | Name
-|-|-|-
0 | (1) `Rotation_0` | mRotation
4 | (12) `BlockPos` | mPosition
16 | (32) `std::string` | mWallType


### `WellKnownBiomeTags`
Offset | Type | Name
-|-|-|-
0 | (16) `WellKnownTagID` | MONSTER_TAG_ID
16 | (16) `WellKnownTagID` | ANIMAL_TAG_ID
32 | (16) `WellKnownTagID` | OCEAN_TAG_ID
48 | (16) `WellKnownTagID` | NETHER_TAG_ID
64 | (16) `WellKnownTagID` | END_TAG_ID
80 | (16) `WellKnownTagID` | MOOSHROOM_TAG_ID
96 | (16) `WellKnownTagID` | PLAINS_TAG_ID
112 | (16) `WellKnownTagID` | DESERT_TAG_ID
128 | (16) `WellKnownTagID` | JUNGLE_TAG_ID
144 | (16) `WellKnownTagID` | BAMBOO_JUNGLE_TAG_ID
160 | (16) `WellKnownTagID` | TAIGA_TAG_ID
176 | (16) `WellKnownTagID` | EXTREME_HILLS_TAG_ID
192 | (16) `WellKnownTagID` | SAVANNA_TAG_ID
208 | (16) `WellKnownTagID` | FROZEN_TAG_ID
224 | (16) `WellKnownTagID` | COLD_TAG_ID
240 | (16) `WellKnownTagID` | LUKEWARM_TAG_ID
256 | (16) `WellKnownTagID` | WARM_TAG_ID
272 | (16) `WellKnownTagID` | RIVER_TAG_ID
288 | (16) `WellKnownTagID` | SWAMP_TAG_ID
304 | (16) `WellKnownTagID` | BEACH_TAG_ID
320 | (16) `WellKnownTagID` | FLOWER_FOREST_TAG_ID
336 | (16) `WellKnownTagID` | FOREST_TAG_ID
352 | (16) `WellKnownTagID` | BIRCH_TAG_ID
368 | (16) `WellKnownTagID` | HILLS_TAG_ID
384 | (16) `WellKnownTagID` | MUTATED_TAG_ID
400 | (16) `WellKnownTagID` | EDGE_TAG_ID
416 | (16) `WellKnownTagID` | PLATEAU_TAG_ID
432 | (16) `WellKnownTagID` | DEEP_TAG_ID
448 | (16) `WellKnownTagID` | MESA_TAG_ID
464 | (16) `WellKnownTagID` | ICE_PLAINS_TAG_ID
480 | (16) `WellKnownTagID` | ICE_TAG_ID
496 | (16) `WellKnownTagID` | MOUNTAIN_TAG_ID
512 | (16) `WellKnownTagID` | SHORE_TAG_ID
528 | (16) `WellKnownTagID` | STONE_TAG_ID
544 | (16) `WellKnownTagID` | ROOFED_TAG_ID
560 | (16) `WellKnownTagID` | MEGA_TAG_ID
576 | (16) `WellKnownTagID` | RARE_TAG_ID
592 | (16) `WellKnownTagID` | NO_LEGACY_WORLDGEN_TAG_ID
608 | (16) `WellKnownTagID` | OVERWORLD_TAG_ID
624 | (16) `WellKnownTagID` | OVERWORLD_GEN_TAG_ID
640 | (16) `WellKnownTagID` | FOREST_GEN_TAG_ID


### `WellKnownTagID`
Offset | Type | Name
-|-|-|-
0 | (8) `TagID` | mTagID
8 | (8) `TagRegistry *` | mTagRegistry


### `Weak<RopeSystem>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__weak_ptr<RopeSystem,__gnu_cxx::_S_atomic>` | baseclass_0


### `WebviewObserver`
Offset | Type | Name
-|-|-|-
0 | (16) `Core::Observer<WebviewObserver,Core::SingleThreadedLock>` | baseclass_0


### `WeakRefT<FeatureRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `FeatureRefTraits::WeakStorage` | baseclass_0


### `WanderingTraderScheduler`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (8) `uint64_t` | mTickToCheckIfSpawning
16 | (1) `bool` | mSpawnWanderingTrader
20 | (4) `int` | mDaysSinceLastSpawn
24 | (8) `ActorUniqueID` | mWanderingTraderUUID


### `WorkerPool`
Offset | Type | Name
-|-|-|-
0 | (1) `const bool` | mAsync
8 | (24) `std::vector<std::unique_ptr<BackgroundWorker>>` | mWorkers
32 | (32) `std::string` | mName
64 | (64) `BackgroundWorkerPerfInfo` | mPerfInfo
128 | (8) `std::chrono::_V2::system_clock::time_point` | mLastPerfInfoUpdate
136 | (8) `Scheduler *` | mOwnerScheduler
144 | (40) `Bedrock::Threading::Mutex` | mSuspendLock
184 | (4) `Bedrock::Threading::OSThreadPriority` | mPoolPriority
188 | (4) `float` | mMinBacklogDurationSeconds
192 | (32) `SpinLock` | mPendingWorkQueueLock
224 | (24) `WorkerPool::PendingJobQueue` | mPendingWorkQueue
248 | (8) `std::chrono::_V2::steady_clock::time_point` | mNextPendingWorkTime
256 | (248) `BackgroundTaskQueue` | mTaskQueue


### `WorkerPool::PendingJobQueue`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<std::shared_ptr<BackgroundTask>,BackgroundTask::PendingComparer>::Base` | mC


### `Wolf::normalTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `WitherBoss::aiStep::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `WeightedChoice<DefinitionTrigger>`
Offset | Type | Name
-|-|-|-
0 | (128) `DefinitionTrigger` | mValue
128 | (4) `WeighedRandom::WeighedRandomItem` | mRandomItem


### `Witch::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `WeakPtr<ShovelItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShovelItem> *` | pc


### `WeakPtr<PickaxeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PickaxeItem> *` | pc


### `WeakPtr<HatchetItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HatchetItem> *` | pc


### `WeakPtr<FlintAndSteelItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FlintAndSteelItem> *` | pc


### `WeakPtr<BowItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BowItem> *` | pc


### `WeakPtr<ArrowItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArrowItem> *` | pc


### `WeakPtr<CoalItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoalItem> *` | pc


### `WeakPtr<WeaponItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WeaponItem> *` | pc


### `WeakPtr<BlockPlanterItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BlockPlanterItem> *` | pc


### `WeakPtr<HoeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<HoeItem> *` | pc


### `WeakPtr<ShieldItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShieldItem> *` | pc


### `WeakPtr<BucketItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BucketItem> *` | pc


### `WeakPtr<MinecartItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MinecartItem> *` | pc


### `WeakPtr<RedStoneDustItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<RedStoneDustItem> *` | pc


### `WeakPtr<SnowballItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SnowballItem> *` | pc


### `WeakPtr<BoatItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BoatItem> *` | pc


### `WeakPtr<EnchantedBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnchantedBookItem> *` | pc


### `WeakPtr<EggItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EggItem> *` | pc


### `WeakPtr<CompassItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CompassItem> *` | pc


### `WeakPtr<FishingRodItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FishingRodItem> *` | pc


### `WeakPtr<ClockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClockItem> *` | pc


### `WeakPtr<DyePowderItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DyePowderItem> *` | pc


### `WeakPtr<BedItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BedItem> *` | pc


### `WeakPtr<MapItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MapItem> *` | pc


### `WeakPtr<ShearsItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShearsItem> *` | pc


### `WeakPtr<EnderpearlItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnderpearlItem> *` | pc


### `WeakPtr<PotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<PotionItem> *` | pc


### `WeakPtr<BottleItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BottleItem> *` | pc


### `WeakPtr<EnderEyeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EnderEyeItem> *` | pc


### `WeakPtr<MobPlacerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MobPlacerItem> *` | pc


### `WeakPtr<ExperiencePotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ExperiencePotionItem> *` | pc


### `WeakPtr<FireChargeItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireChargeItem> *` | pc


### `WeakPtr<WritableBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WritableBookItem> *` | pc


### `WeakPtr<WrittenBookItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WrittenBookItem> *` | pc


### `WeakPtr<EmptyMapItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<EmptyMapItem> *` | pc


### `WeakPtr<SkullItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SkullItem> *` | pc


### `WeakPtr<CarrotOnAStickItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CarrotOnAStickItem> *` | pc


### `WeakPtr<FireworksItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<FireworksItem> *` | pc


### `WeakPtr<TridentItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TridentItem> *` | pc


### `WeakPtr<ArmorStandItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArmorStandItem> *` | pc


### `WeakPtr<DoorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<DoorItem> *` | pc


### `WeakPtr<SplashPotionItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SplashPotionItem> *` | pc


### `WeakPtr<ArmorItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ArmorItem> *` | pc


### `WeakPtr<BannerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BannerItem> *` | pc


### `WeakPtr<SuspiciousStewItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SuspiciousStewItem> *` | pc


### `WeakPtr<CameraItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CameraItem> *` | pc


### `WeakPtr<CompoundItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CompoundItem> *` | pc


### `WeakPtr<IceBombItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<IceBombItem> *` | pc


### `WeakPtr<BalloonItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BalloonItem> *` | pc


### `WeakPtr<MedicineItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<MedicineItem> *` | pc


### `WeakPtr<SparklerItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SparklerItem> *` | pc


### `WeakPtr<GlowStickItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<GlowStickItem> *` | pc


### `WeakPtr<AuxDataBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<AuxDataBlockItem> *` | pc


### `WeakPtr<ClothBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ClothBlockItem> *` | pc


### `WeakPtr<StoneSlabBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<StoneSlabBlockItem> *` | pc


### `WeakPtr<CoralFanBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<CoralFanBlockItem> *` | pc


### `WeakPtr<SeaPickleBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SeaPickleBlockItem> *` | pc


### `WeakPtr<SaplingBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<SaplingBlockItem> *` | pc


### `WeakPtr<LeafBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<LeafBlockItem> *` | pc


### `WeakPtr<WoodSlabBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WoodSlabBlockItem> *` | pc


### `WeakPtr<WaterLilyBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<WaterLilyBlockItem> *` | pc


### `WeakPtr<TopSnowBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<TopSnowBlockItem> *` | pc


### `WeakPtr<ShulkerBoxBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ShulkerBoxBlockItem> *` | pc


### `WeakPtr<BambooBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BambooBlockItem> *` | pc


### `WeakPtr<ScaffoldingBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ScaffoldingBlockItem> *` | pc


### `WeakPtr<BellBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<BellBlockItem> *` | pc


### `WeakPtr<ChemistryAuxDataBlockItem>`
Offset | Type | Name
-|-|-|-
0 | (8) `SharedCounter<ChemistryAuxDataBlockItem> *` | pc


### `WeakRefT<SharePtrRefTraits<PerlinSimplexNoise> >`
Offset | Type | Name
-|-|-|-
0 | (16) `SharePtrRefTraits<PerlinSimplexNoise>::WeakStorage` | baseclass_0


### `WeightedRandomFeature::WeightedFeatureReference`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRef<IFeature>` | mFeature
24 | (4) `float` | mWeight


### `WeightedChoice<float>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mValue
4 | (4) `WeighedRandom::WeighedRandomItem` | mRandomItem


### `WeakRefT<EntityRegistryRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityRegistryRefTraits::WeakStorage` | baseclass_0


### `WildcardCommandSelector<Actor>`
Offset | Type | Name
-|-|-|-
0 | (168) `CommandSelectorBase` | baseclass_0


### `WanderingTrader::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `WorldTemplateManagerProxy`
```
struct WorldTemplateManagerProxy
{
  const WorldTemplateManagerProxyCallbacks mCallbacks;
};

```

### `Whitelist`
```
struct __cppobj Whitelist : IJsonSerializable
{
  std::vector<WhitelistEntry> mEntries;
  std::function<void ()> mSyncCallback;
};

```

### `WorldTemplatePackSource`
```
struct __cppobj __attribute__((aligned(8))) WorldTemplatePackSource : DirectoryPackSource
{
  const WorldTemplateManager *mWorldTemplateManager;
  mce::UUID mWorldTemplateId;
  bool mHasValidPathSet;
};

```

### `WorldHistoryPackSource`
```
struct __cppobj __attribute__((aligned(8))) WorldHistoryPackSource : PackSource
{
  Core::HeapPathBuffer mPathToHistoryFile;
  PackType mPackType;
  std::vector<std::unique_ptr<Pack>> mPacks;
  WorldPacksHistoryFile mWorldHistoryPacksFile;
  bool mDiscovered;
  bool mNeedsSaving;
};

```

### `WhitelistCommand`
```
struct __cppobj WhitelistCommand : Command
{
  WhitelistCommand::Action mAction;
  std::string mName;
};

```

### `WeakStorageEntity`
```
struct WeakStorageEntity
{
  WeakRefT<EntityRegistryRefTraits> mRegistry;
  std::optional<EntityId> mEntity;
};

```

### `WeakStorageSharePtr<EntityRegistry>`
```
struct WeakStorageSharePtr<EntityRegistry>
{
  std::weak_ptr<EntityRegistry> mHandle;
};

```

### `WeakRefT<EntityRefTraits>`
```
struct __cppobj WeakRefT<EntityRefTraits> : EntityRefTraits::WeakStorage
{
};

```

### `WeightedRandomFeature`
```
struct __cppobj WeightedRandomFeature : IFeature
{
  std::vector<WeightedRandomFeature::WeightedFeatureReference> mFeatureReferences;
};

```

### `WaterlilyFeature`
```
struct __cppobj WaterlilyFeature : Feature
{
};

```

### `WorldChangeTransaction::Data`
```
struct WorldChangeTransaction::Data
{
  std::unordered_map<BlockPos,BlockChange> changes;
};

```

### `WeakStorageFeature`
```
struct WeakStorageFeature
{
  std::optional<std::reference_wrapper<FeatureRegistry> > mRegistry;
  size_t mIndex;
};

```

### `WorldGenerator`
```
struct WorldGenerator
{
  int (**_vptr$WorldGenerator)(void);
  std::unique_ptr<HardcodedSpawnAreaRegistry> mHardcodedSpawnTypes;
};

```

### `Weather`
```
struct __cppobj Weather : LevelListener
{
  PerlinSimplexNoise mNoise;
  int mTick;
  float mORainLevel;
  float mRainLevel;
  float mTargetRainLevel;
  float mOLightningLevel;
  float mLightningLevel;
  float mTargetLightningLevel;
  float mFogLevel;
  int mSkyFlashTime;
  Dimension *mDimension;
};

```

### `WeighedRandom`
```
struct WeighedRandom
{
  __int8 gap0[1];
};

```

### `WoodlandMansionFeature`
```
struct __cppobj WoodlandMansionFeature : StructureFeature:1760
{
  int mFeatureSpacing;
  int mMinFeatureSeparation;
  std::vector<int> mAllowedBiomes;
  OverworldGenerator *mLevelSource;
};

```

### `WoodlandMansionStart`
```
struct __cppobj WoodlandMansionStart : StructureStart
{
  Rotation_0 mRotationGenerated;
  BlockPos mPositionGenerated;
};

```

### `WebviewDownloadInfo`
```
struct WebviewDownloadInfo
{
  std::string mContentDisposition;
  std::string mMimeType;
  std::string mOriginalURL;
  std::string mURL;
  uint32_t mId;
  std::string mSuggestedFileName;
  std::string mFullPath;
  int64_t mReceivedBytes;
  int64_t mTotalBytes;
  int64_t mCurrentSpeed;
  int mPercentComplete;
  time_t mStartTime;
  time_t mEndTime;
};

```

### `WeightedChoices<DefinitionTrigger>`
```
struct WeightedChoices<DefinitionTrigger>
{
  std::vector<WeightedChoice<DefinitionTrigger>> mChoices;
};

```

### `WorldPacksHistoryFile`
```
struct WorldPacksHistoryFile
{
  std::vector<WorldPackHistory> mPacks;
};

```

### `WorldSessionEndPoint`
```
struct __cppobj __attribute__((aligned(8))) WorldSessionEndPoint : ContentLogEndPoint
{
  IMinecraftEventing *mEventing;
  bool mIsEnabled;
};

```

### `WireframeQueue`
```
struct WireframeQueue
{
  std::unordered_map<BlockPos,Wireframe> mQueue;
};

```

### `Weak<VillageLegacy>`
```
typedef std::weak_ptr<VillageLegacy> Weak<VillageLegacy>;

```

### `WalkAnimationSpeedDescription`
```
struct __cppobj __attribute__((aligned(8))) WalkAnimationSpeedDescription : PropertyDescription
{
  float mValue;
};

```

### `WantsJockeyDescription`
```
struct __cppobj WantsJockeyDescription : PropertyDescription
{
};

```

### `WASDControlledDescription`
```
struct __cppobj WASDControlledDescription : PropertyDescription
{
};

```

### `WaterMovementDescription`
```
struct __cppobj __attribute__((aligned(8))) WaterMovementDescription : ComponentDescription
{
  float mDragFactor;
};

```

### `WorldSystems`
```
struct WorldSystems
{
  __int8 gap0[1];
};

```

### `Wolf`
```
struct __cppobj __attribute__((aligned(8))) Wolf : Animal
{
  float mShakeAnim;
  float mShakeAnimO;
  float mInterestedAngle;
  float mInterestedAngleO;
  bool mIsWet;
  bool mIsShaking;
};

```

### `Witch`
```
struct __cppobj __attribute__((aligned(8))) Witch : HumanoidMonster
{
  int mUsingTime;
};

```

### `WitherBoss`
```
struct __cppobj __attribute__((aligned(8))) WitherBoss : Monster
{
  int MAX_SHIELD_HEALTH;
  int mTimeBeforeMoving;
  float mNewXPos;
  int mShieldHealth;
  Vec2 mHeadRots[3];
  Vec2 mOldHeadRots[3];
  int mNextHeadUpdate[3];
  int mIdleHeadUpdates[3];
  int mDestroyBlocksTick;
  int mHealthThreshold;
  int mPhase;
  bool mWantsToExplode;
  bool mCharging;
  Vec3 mChargeDirection;
  int mChargeFrames;
  int mPreparingCharge;
  int mProjectileCounter;
  int mSpawningFrames;
  int mShieldFlicker;
  int mTimeTillNextShot;
  int mFireRate;
  float mSpinSpeed;
  float mOverlayAlpha;
  int mStunTimer;
  int mFramesTillMove;
  bool mWantsMove;
  bool mIsPathing;
  int mMaxHealth;
  int mNumSkeletons;
  int mMaxSkeletons;
  int mDyingFrames;
  int mMovementTime;
  int mHealthIntervals;
  int mLastHealthValue;
  int mDelayShot;
  int mTimeSinceLastShot;
  float mAttackRange;
  bool mSecondVolley;
  float mSwellAmount;
  float mOldSwellAmount;
  int mMainHeadAttackCountdown;
  std::unique_ptr<ActorDamageSource> mDeathSource;
  int mlastFiredHead;
};

```

### `WitherSkull`
```
struct __cppobj WitherSkull : Fireball:17696
{
  int mLifetime;
};

```

### `WallClimberPathNavigation`
```
struct __cppobj __attribute__((aligned(8))) WallClimberPathNavigation : PathNavigation
{
  BlockPos mPathToPosition;
};

```

### `WaterBoundPathNavigation`
```
struct __cppobj __attribute__((aligned(8))) WaterBoundPathNavigation : PathNavigation
{
  bool mAllowRiverFollow;
  bool mFollowingRiver;
  int mHeadingTicks;
  float mCenteredThreshold;
  float mLookAheadDistance;
  float mMinDepth;
  float mMaxDepth;
  float mSteerDampening;
  float mTerrainAvoidDistance;
  float mXBodyRotation;
  float mYBodyRotation;
  float mZBodyRotation;
};

```

### `WorkGoal`
```
struct __cppobj WorkGoal : MoveToPOIGoal
{
  POIType mPOIType;
  int mGoalCooldownMax;
  int mCooldownTick;
  int mGoalActiveMax;
  int mActiveTick;
  int mSoundIntervalMin;
  int mSoundIntervalMax;
  int mSoundTick;
  int mSoundTickMax;
  bool mCanWorkInRain;
  bool mCanRainAtLocation;
  int mRainCheckCooldownTick;
  int mWorkInRainTolerance;
  const DefinitionTrigger mOnArrival;
  bool mHasEverReachedJobsite;
  LevelSoundEvent mSoundEvent;
};

```

### `WitherRandomAttackPosGoal`
```
struct __cppobj __attribute__((aligned(8))) WitherRandomAttackPosGoal : RandomStrollGoal:528
{
  bool mIsPathing;
};

```

### `WitherTargetHighestDamage`
```
struct __cppobj WitherTargetHighestDamage : TargetGoal
{
  WitherBoss *mWitherBoss;
  Mob *mTarget;
};

```

### `WaterAnimal`
```
struct __cppobj WaterAnimal : Mob
{
};

```

### `WitherDoNothingGoal`
```
struct __cppobj WitherDoNothingGoal : Goal
{
  WitherBoss *mWitherBoss;
};

```

### `WanderingTrader`
```
struct __cppobj __attribute__((aligned(8))) WanderingTrader : Mob
{
  float mRaiseArmValue;
};

```

### `WeakPtr<AirBlockItem>`
```
struct WeakPtr<AirBlockItem>
{
  SharedCounter<AirBlockItem> *pc;
};

```

### `WeaponItem`
```
struct __cppobj WeaponItem : Item
{
  int mDamage;
  const Item::Tier *mTier;
};

```

### `WeakPtr<HangingActorItem>`
```
struct WeakPtr<HangingActorItem>
{
  SharedCounter<HangingActorItem> *pc;
};

```

### `WeakPtr<SignItem>`
```
struct WeakPtr<SignItem>
{
  SharedCounter<SignItem> *pc;
};

```

### `WritableBookItem`
```
struct __cppobj WritableBookItem : Item
{
};

```

### `WrittenBookItem`
```
struct __cppobj WrittenBookItem : Item
{
};

```

### `WeakPtr<FireworkChargeItem>`
```
struct WeakPtr<FireworkChargeItem>
{
  SharedCounter<FireworkChargeItem> *pc;
};

```

### `WeakPtr<HorseArmorItem>`
```
struct WeakPtr<HorseArmorItem>
{
  SharedCounter<HorseArmorItem> *pc;
};

```

### `WeakPtr<RecordItem>`
```
struct WeakPtr<RecordItem>
{
  SharedCounter<RecordItem> *pc;
};

```

### `WeakPtr<LeadItem>`
```
struct WeakPtr<LeadItem>
{
  SharedCounter<LeadItem> *pc;
};

```

### `WeakPtr<EndCrystalItem>`
```
struct WeakPtr<EndCrystalItem>
{
  SharedCounter<EndCrystalItem> *pc;
};

```

### `WeakPtr<LingeringPotionItem>`
```
struct WeakPtr<LingeringPotionItem>
{
  SharedCounter<LingeringPotionItem> *pc;
};

```

### `WeakPtr<CrossbowItem>`
```
struct WeakPtr<CrossbowItem>
{
  SharedCounter<CrossbowItem> *pc;
};

```

### `WeakPtr<BannerPatternItem>`
```
struct WeakPtr<BannerPatternItem>
{
  SharedCounter<BannerPatternItem> *pc;
};

```

### `WeakPtr<ChemistryItem>`
```
struct WeakPtr<ChemistryItem>
{
  SharedCounter<ChemistryItem> *pc;
};

```

### `WeakPtr<RapidFertilizerItem>`
```
struct WeakPtr<RapidFertilizerItem>
{
  SharedCounter<RapidFertilizerItem> *pc;
};

```

### `WoodSlabBlockItem`
```
struct __cppobj WoodSlabBlockItem : SlabBlockItem
{
};

```

### `WaterLilyBlockItem`
```
struct __cppobj WaterLilyBlockItem : BlockItem
{
};

```

### `WeakPtr<ElementBlockItem>`
```
struct WeakPtr<ElementBlockItem>
{
  SharedCounter<ElementBlockItem> *pc;
};

```

### `WeaponRecipes`
```
struct WeaponRecipes
{
  __int8 gap0[1];
};

```

### `WeakRef<EntityId>`
```
typedef WeakRefT<EntityRefTraits> WeakRef<EntityId>;

```

### `Wireframe`
```
struct Wireframe
{
  BlockPos mPos;
  BlockPos mBox;
  std::array<WireframeQuad,24> mQuadList;
};

```

### `WireframeQuad`
```
struct WireframeQuad
{
  std::array<Vec3,4> mQuad;
  int mColor;
};

```

### `WeakStorageSharePtr<PerlinSimplexNoise>`
```
struct WeakStorageSharePtr<PerlinSimplexNoise>
{
  std::weak_ptr<PerlinSimplexNoise> mHandle;
};

```

### `WorldGenClimateMappingAttributes::WeightedTemperatureCategory`
```
struct WorldGenClimateMappingAttributes::WeightedTemperatureCategory
{
  BiomeTemperatureCategory mTemperature;
  uint32_t mWeight;
};

```

### `WebBlock`
```
struct __cppobj WebBlock : BlockLegacy
{
};

```

### `WorkbenchBlock`
```
struct __cppobj WorkbenchBlock : BlockLegacy
{
};

```

### `WaterlilyBlock`
```
struct __cppobj WaterlilyBlock : BushBlock
{
};

```

### `WallBlock`
```
struct __cppobj WallBlock : BlockLegacy
{
};

```

### `WoodButtonBlock`
```
struct __cppobj __attribute__((aligned(8))) WoodButtonBlock : ButtonBlock
{
};

```

### `WeightedPressurePlateBlock`
```
struct __cppobj __attribute__((aligned(8))) WeightedPressurePlateBlock : BasePressurePlateBlock
{
  const int maxWeight;
};

```

### `WoodSlabBlock`
```
struct __cppobj WoodSlabBlock : SlabBlock
{
};

```

### `WoolCarpetBlock`
```
struct __cppobj WoolCarpetBlock : BlockLegacy
{
};

```

### `WoodBlock`
```
struct __cppobj WoodBlock : RotatedPillarBlock
{
};

```

### `WitherRoseBlock`
```
struct __cppobj __attribute__((aligned(8))) WitherRoseBlock : FlowerBlock
{
};

```

### `WorldLimitChunkSource`
```
struct __cppobj WorldLimitChunkSource : ChunkSource
{
  std::shared_ptr<LevelChunk> mInvisibleWallChunk;
  const Bounds mLimitArea;
};

```

### `WoodlandMansionPieces::MansionGrid`
```
struct WoodlandMansionPieces::MansionGrid
{
  Unique<WoodlandMansionPieces::SimpleGrid> mBaseGrid;
  Unique<WoodlandMansionPieces::SimpleGrid> mThirdFloorGrid;
  std::vector<std::unique_ptr<WoodlandMansionPieces::SimpleGrid>> mFloorRooms;
  int mEntranceX;
  int mEntranceY;
  Random *mRandom;
};

```

### `WoodlandMansionPieces::SimpleGrid`
```
struct __attribute__((aligned(8))) WoodlandMansionPieces::SimpleGrid
{
  std::vector<std::vector<int>> mGrid;
  int mWidth;
  int mHeight;
  int mValueIfOutside;
};

```

### `WoodlandMansionPieces::MansionPiecePlacer`
```
struct WoodlandMansionPieces::MansionPiecePlacer
{
  StructureManager *mStructureManager;
  Random *mRandom;
  int mStartX;
  int mStartY;
};

```

### `WoodlandMansionPieces::FloorRoomCollection`
```
struct WoodlandMansionPieces::FloorRoomCollection
{
  int (**_vptr$FloorRoomCollection)(void);
};

```

### `WoodlandMansionPieces::FirstFloorRoomCollection`
```
struct __cppobj WoodlandMansionPieces::FirstFloorRoomCollection : WoodlandMansionPieces::FloorRoomCollection
{
};

```

### `WoodlandMansionPieces::SecondFloorRoomCollection`
```
struct __cppobj WoodlandMansionPieces::SecondFloorRoomCollection : WoodlandMansionPieces::FloorRoomCollection
{
};

```

### `WoodlandMansionPieces::ThirdFloorRoomCollection`
```
struct __cppobj WoodlandMansionPieces::ThirdFloorRoomCollection : WoodlandMansionPieces::SecondFloorRoomCollection
{
};

```

### `WoodlandMansionPieces::WoodlandMansionPiece`
```
struct __cppobj WoodlandMansionPieces::WoodlandMansionPiece : TemplateStructurePiece
{
  StructureManager *mStructureManager;
  std::string mTemplateName;
  Rotation_0 mRotation;
  Mirror_0 mMirror;
  BlockPos mPosition;
  std::vector<BlockPos> mVindicatorPositions;
  std::vector<BlockPos> mEvokerPositions;
};

```

### `WoodlandMansionPieces`
```
struct WoodlandMansionPieces
{
  __int8 gap0[1];
};

```

### `WeightedBiomeReference`
```
typedef std::pair<Biome *,unsigned int> WeightedBiomeReference;

```

### `WorldBuilderCommand`
```
struct __cppobj WorldBuilderCommand : Command
{
};

```

### `WildcardActorSelector`
```
typedef WildcardCommandSelector<Actor> WildcardActorSelector;

```

### `WSServerCommand`
```
struct __cppobj WSServerCommand : Command
{
  CommandRawText mServerIP;
};

```

### `WeatherCommand`
```
struct __cppobj __attribute__((aligned(8))) WeatherCommand : Command
{
  WeatherCommand::WeatherRequest mRequest;
  WeatherCommand::WeatherType mType;
  int mDuration;
};

```

### `WaitDefinition`
```
struct __cppobj WaitDefinition : BehaviorDefinition
{
  int mDuration;
  std::string mDurationId;
};

```

### `WaitNode`
```
struct __cppobj WaitNode : BehaviorNode
{
  std::chrono::seconds mDuration;
  std::chrono::_V2::steady_clock::time_point mStart;
};

```

### `WaitTicksDefinition`
```
struct __cppobj WaitTicksDefinition : BehaviorDefinition
{
  int mTicks;
  std::string mTicksId;
};

```

### `WaitTicksNode`
```
struct __cppobj __attribute__((aligned(8))) WaitTicksNode : BehaviorNode:480
{
  int mMaxTicks;
  int mCurrTicks;
};

```

### `WSAStartupSingleton`
```
struct WSAStartupSingleton
{
  __int8 gap0[1];
};

```

