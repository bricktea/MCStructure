# L
### `LevelSettings`
Offset | Type | Name
-|-|-|-
0 | (4) `RandomSeed` | mSeed
4 | (4) `GameType` | mGameType
8 | (4) `Difficulty` | mGameDifficulty
12 | (1) `bool` | mForceGameType
16 | (4) `GeneratorType` | mGenerator
20 | (1) `bool` | mAchievementsDisabled
24 | (4) `DimensionType` | mDimension
28 | (4) `int` | mTime
32 | (4) `EducationEditionOffer` | mEducationEditionOffer
36 | (1) `bool` | mEducationFeaturesEnabled
37 | (1) `bool` | mImmutableWorld
40 | (4) `float` | mRainLevel
44 | (4) `float` | mLightningLevel
48 | (1) `bool` | mConfirmedPlatformLockedContent
49 | (1) `bool` | mMultiplayerGameIntent
50 | (1) `bool` | mLANBroadcastIntent
52 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
56 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
60 | (1) `bool` | mCommandsEnabled
61 | (1) `bool` | mTexturePacksRequired
62 | (1) `bool` | mHasLockedBehaviorPack
63 | (1) `bool` | mHasLockedResourcePack
64 | (1) `bool` | mIsFromLockedTemplate
65 | (1) `bool` | mUseMsaGamertagsOnly
66 | (1) `bool` | mOverrideSettings
67 | (1) `bool` | mBonusChestEnabled
68 | (1) `bool` | mStartWithMapEnabled
72 | (4) `int` | mServerChunkTickRange
76 | (1) `bool` | mForceExperimentalGameplay
77 | (1) `bool` | mIsFromWorldTemplate
78 | (1) `bool` | mIsWorldTemplateOptionLocked
79 | (1) `bool` | mSpawnV1Villagers
80 | (320) `Abilities` | mDefaultAbilities
400 | (12) `BlockPos` | mDefaultSpawn
416 | (24) `std::vector<PackInstanceId>` | mNewWorldBehaviorPackIdentities
440 | (24) `std::vector<PackInstanceId>` | mNewWorldResourcePackIdentities
464 | (24) `GameRules` | mGameRules
488 | (112) `BaseGameVersion` | mBaseGameVersion
600 | (104) `std::optional<EducationLevelSettings>` | mEducationLevelSettings


### `LevelStorageSource`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$LevelStorageSource


### `LevelData`
Offset | Type | Name
-|-|-|-
0 | (5) `AdventureSettings` | mAdventureSettings
8 | (280) `WorldTemplateLevelData` | mWorldTemplateLevelData
288 | (24) `GameRules` | mGameRules
312 | (320) `Abilities` | mDefaultAbilities
632 | (32) `std::string` | mLevelName
664 | (4) `StorageVersion` | mStorageVersion
672 | (56) `GameVersion` | mMinCompatibleClientVersion
728 | (4) `int` | mNetworkVersion
736 | (112) `SemVersion` | mInventoryVersion
848 | (8) `Tick` | mCurrentTick
856 | (4) `RandomSeed` | mSeed
860 | (12) `BlockPos` | mSpawnPos
872 | (1) `bool` | mHasSpawnPos
876 | (12) `BlockPos` | mLimitedWorldOrigin
888 | (4) `int` | mTime
896 | (8) `time_t` | mLastPlayed
904 | (56) `CompoundTag` | mLoadedPlayerTag
960 | (4) `uint32_t` | mServerTickRange
964 | (4) `float` | mRainLevel
968 | (4) `int` | mRainTime
972 | (4) `float` | mLightningLevel
976 | (4) `int` | mLightningTime
980 | (4) `int` | mNetherScale
984 | (56) `GameVersion` | mLastOpenedWithVersion
1040 | (4) `GameType` | mGameType
1044 | (4) `Difficulty` | mGameDifficulty
1048 | (1) `bool` | mForceGameType
1049 | (1) `bool` | mSpawnMobs
1052 | (4) `GeneratorType` | mGenerator
1056 | (16) `Json::Value` | mFlatworldGeneratorOptions
1072 | (4) `uint32_t` | mWorldStartCount
1076 | (1) `bool` | mAchievementsDisabled
1080 | (4) `EducationEditionOffer` | mEducationEditionOffer
1084 | (1) `bool` | mEducationFeaturesEnabled
1085 | (1) `bool` | mConfirmedPlatformLockedContent
1086 | (1) `bool` | mMultiplayerGameIntent
1087 | (1) `bool` | mMultiplayerGame
1088 | (1) `bool` | mLANBroadcastIntent
1089 | (1) `bool` | mLANBroadcast
1092 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
1096 | (4) `Social::GamePublishSetting` | mXBLBroadcastMode
1100 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
1104 | (4) `Social::GamePublishSetting` | mPlatformBroadcastMode
1108 | (1) `bool` | mCommandsEnabled
1109 | (1) `bool` | mTexturePacksRequired
1110 | (1) `bool` | mHasLockedBehaviorPack
1111 | (1) `bool` | mHasLockedResourcePack
1112 | (1) `bool` | mIsFromLockedTemplate
1120 | (32) `std::string` | mEducationOid
1152 | (32) `std::string` | mEducationProductId
1184 | (1) `bool` | mUseMsaGamertagsOnly
1185 | (1) `bool` | mBonusChestEnabled
1186 | (1) `bool` | mBonusChestSpawned
1187 | (1) `bool` | mStartWithMapEnabled
1188 | (1) `bool` | mMapsCenteredToOrigin
1189 | (1) `bool` | mRequiresCopiedPackRemovalCheck
1190 | (1) `bool` | mSpawnV1Villagers


### `locale_type`
Offset | Type | Name
-|-|-|-
0 | (8) `std::locale::_Impl *` | _M_impl


### `LayerDetails::Storage`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | mReadableBytes
8 | (8) `size_t` | mWriteableBytes
16 | (8) `std::unique_ptr<char []>` | mReadStorage
24 | (8) `std::unique_ptr<char []>` | mWriteStorage


### `LayerBiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeSource` | baseclass_0
8 | (16) `ConstLayerPtr<Biome *>` | mBlockResolutionLayer


### `LakeFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock
32 | (8) `const Block *` | mEmptyBlock


### `LayerPtr<LayerValues::Terrain>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<LayerValues::Terrain>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<LayerValues::PreBiome>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<LayerValues::PreBiome>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<Biome *>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<LayerValues::RiverData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<int>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<bool>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<bool>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<BiomeTemperatureCategory>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerPtr<int>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<Layer<int>,__gnu_cxx::_S_atomic>` | baseclass_0


### `LayerDetails::BufferAccessor<char>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerDetails::BufferAccessor<LayerValues::Terrain>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::RandomProviderArray`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__array_traits<LayerDetails::RandomProviderT<(lambda at _Minecraftpe_handheld_project_dedicated_server_______src_common_world_level_newbiome_LayerDetails_h:221:34)>,1>::_Type` | _M_elems


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::ResultPatch<LayerValues::Terrain>`
Offset | Type | Name
-|-|-|-
0 | (4) `std::__array_traits<LayerValues::Terrain,4>::_Type` | _M_elems


### `LayerDetails::BufferAccessor<LayerValues::PreBiome>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerValues::PreBiome`
Offset | Type | Name
-|-|-|-
0 | (1) `LayerValues::Terrain` | mTerrain
1 | (1) `BiomeTemperatureCategory` | mTemperature


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::ResultPatch<LayerValues::PreBiome>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::__array_traits<LayerValues::PreBiome,4>::_Type` | _M_elems


### `LayerDetails::BufferAccessor<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerDetails::BufferAccessor<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::ResultPatch<int>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__array_traits<int,4>::_Type` | _M_elems


### `LayerDetails::BufferAccessor<bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerFilters::FilterBase<3,3,bool,bool>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::FilterBase<3,3,Biome *,Biome *>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::ResultPatch<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (32) `std::__array_traits<Biome *,4>::_Type` | _M_elems


### `LayerResult<bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `Layer<Biome *>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerDetails::BufferAccessor<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mStorage
8 | (8) `size_t` | mCount


### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::ResultPatch<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (4) `std::__array_traits<BiomeTemperatureCategory,4>::_Type` | _M_elems


### `LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>::RandomProviderArray`
Offset | Type | Name
-|-|-|-
0 | (64) `std::__array_traits<LayerDetails::RandomProviderT<(lambda at _Minecraftpe_handheld_project_dedicated_server_______src_common_world_level_newbiome_LayerDetails_h:221:34)>,4>::_Type` | _M_elems


### `LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>::ResultPatch<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (128) `std::__array_traits<Biome *,16>::_Type` | _M_elems


### `LevelChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (8) `Dimension *` | mDimension
16 | (12) `BlockPos` | mMin
28 | (12) `BlockPos` | mMax
40 | (8) `ChunkPos` | mPosition
48 | (1) `bool` | mLightingFixupDone
49 | (1) `std::atomic<bool>` | mLightingTaskActive
50 | (1) `bool` | mReadOnly
56 | (8) `ChunkSource *` | mGenerator
64 | (1) `LevelChunkFormat` | mLoadedFormat
72 | (32) `std::string` | mSerializedEntitiesBuffer
104 | (1) `std::atomic<ChunkState>` | mLoadState
105 | (1) `ChunkTerrainDataState` | mTerrainDataState
106 | (1) `ChunkDebugDisplaySavedState` | mDebugDisplaySavedState
107 | (1) `ChunkCachedDataState` | mCachedDataState
112 | (32) `SpinLock` | mCachedDataStateSpinLock
144 | (8) `Tick` | mLastTick
152 | (8) `std::unique_ptr<BlockTickingQueue>` | mTickQueue
160 | (8) `std::unique_ptr<BlockTickingQueue>` | mRandomTickQueue
168 | (936) `AppendOnlyAtomicLookupTable<SubChunk,16>` | mSubChunks
1104 | (512) `std::array<SpinLock,16>` | mSubChunkSpinLocks
1616 | (256) `std::array<BiomeChunkData,256>` | mBiomes
1872 | (2048) `std::array<ColumnCachedData,256>` | mCachedData
3920 | (512) `std::array<short,256>` | mHeightmap
4432 | (8) `std::unique_ptr<std::vector<short>>` | mPreWorldGenHeightmap
4440 | (56) `std::unordered_map<unsigned char,BiomeChunkState>` | mBiomeStates
4496 | (1) `bool` | mHasCachedTemperatureNoise
4497 | (256) `std::array<unsigned char,256>` | mBorderBlockMap
4756 | (4) `LevelChunk::Finalization` | mFinalized
4760 | (1) `bool` | mIsRedstoneLoaded
4761 | (1) `bool` | mOwnedByTickingThread
4764 | (48) `DirtyTicksCounter[6]` | mFullChunkDirtyTicksCounters
4812 | (512) `std::array<short,256>` | mRainHeights
5328 | (24) `OwnedActorSet` | mEntities
5352 | (56) `LevelChunk::OwnedBlockActorMap` | mBlockEntities
5408 | (24) `LevelChunk::BlockActorVector` | mDeletedBlockEntities
5432 | (2) `BrightnessPair` | mDefaultBrightness
5440 | (24) `std::vector<LevelChunk::HardcodedSpawningArea>` | mHardcodedSpawningAreas
5464 | (4) `uint8_t[2][2]` | mbChunkInterpolants
5468 | (1) `bool` | mbChunkHasConverterTag
5469 | (1) `bool` | mDBChunkSurroundedByNeighbors


### `LevelChunk::OwnedBlockActorMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ChunkBlockPos,std::shared_ptr<BlockActor>>::_Hashtable` | _M_h


### `LevelChunk::BlockActorVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::shared_ptr<BlockActor>>` | baseclass_0


### `LegacyStructureSettings`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mIntegrity
4 | (4) `RandomSeed` | mSeed
8 | (4) `Projection` | mProjection
12 | (1) `Mirror_0` | mMirror
13 | (1) `Rotation_0` | mRotation
14 | (1) `bool` | mIgnoreStructureBlocks
15 | (1) `bool` | mIgnoreJigsawBlocks
16 | (1) `bool` | mWaterBelowSeaLevel
24 | (8) `const Block *` | mIgnoreBlock
32 | (8) `ChunkPos` | mChunkPos
40 | (24) `BoundingBox` | mBoundingBox
64 | (56) `std::unordered_map<unsigned char,unsigned char>` | mSwapAuxValues
120 | (8) `const StructurePoolBlockRuleList *` | mBlockRules
128 | (8) `const StructurePoolBlockTagRuleList *` | mBlockTagRules


### `LockGuard`
Offset | Type | Name
-|-|-|-
0 | (8) `std::lock_guard<std::mutex>::mutex_type *` | _M_device


### `LootTableContext`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mLuck
8 | (8) `Level *` | mLevel
16 | (8) `Actor *` | mThisEntity
24 | (8) `Player *` | mKillerPlayer
32 | (8) `const ActorDamageSource *` | mDeathSource
40 | (56) `std::unordered_set<const LootTable *>` | mVisitedTables
96 | (4) `float` | mExplosionRadius


### `LeashableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `LookAtComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSetTarget
4 | (4) `float` | mSearchRadius
8 | (1) `bool` | mAllowInvulnerable
12 | (4) `int` | mCoolingTime


### `LookControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHasWantedPosition
1 | (1) `bool` | mHasWantedRotation
4 | (4) `float` | mYMax
8 | (4) `float` | mXMax
12 | (12) `Vec3` | mWantedPosition
24 | (12) `Vec3` | mWantedRotation
40 | (8) `Unique<LookControl>` | mLookControl


### `LegacyTradeableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAddRecipeOnUpdate
1 | (1) `bool` | mResetLockedOnFirstTrade
2 | (1) `bool` | mWillingToBreed
4 | (4) `int` | mRiches
8 | (4) `int` | mTradeTier
12 | (4) `int` | mUpdateMerchantTimer
16 | (8) `Player *` | mLastPlayerTradeName
24 | (8) `std::unique_ptr<MerchantRecipeList>` | mOffers
32 | (32) `std::string` | mDisplayName
64 | (24) `std::vector<int>` | mTradeRecipeFirstTime


### `leveldb::Status`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | state_


### `leveldb::Slice`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | data_
8 | (8) `size_t` | size_


### `LevelSettings_0`
Offset | Type | Name
-|-|-|-
0 | (4) `RandomSeed_0` | mSeed
4 | (4) `GameType` | mGameType
8 | (4) `Difficulty` | mGameDifficulty
12 | (1) `bool` | mForceGameType
16 | (4) `GeneratorType` | mGenerator
20 | (1) `bool` | mAchievementsDisabled
24 | (4) `DimensionType` | mDimension
28 | (4) `int` | mTime
32 | (4) `EducationEditionOffer` | mEducationEditionOffer
36 | (1) `bool` | mEducationFeaturesEnabled
37 | (1) `bool` | mImmutableWorld
40 | (4) `float` | mRainLevel
44 | (4) `float` | mLightningLevel
48 | (1) `bool` | mConfirmedPlatformLockedContent
49 | (1) `bool` | mMultiplayerGameIntent
50 | (1) `bool` | mLANBroadcastIntent
52 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
56 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
60 | (1) `bool` | mCommandsEnabled
61 | (1) `bool` | mTexturePacksRequired
62 | (1) `bool` | mHasLockedBehaviorPack
63 | (1) `bool` | mHasLockedResourcePack
64 | (1) `bool` | mIsFromLockedTemplate
65 | (1) `bool` | mUseMsaGamertagsOnly
66 | (1) `bool` | mOverrideSettings
67 | (1) `bool` | mBonusChestEnabled
68 | (1) `bool` | mStartWithMapEnabled
72 | (4) `int` | mServerChunkTickRange
76 | (1) `bool` | mForceExperimentalGameplay
77 | (1) `bool` | mIsFromWorldTemplate
78 | (1) `bool` | mIsWorldTemplateOptionLocked
79 | (1) `bool` | mSpawnV1Villagers
80 | (320) `Abilities` | mDefaultAbilities
400 | (12) `BlockPos` | mDefaultSpawn
416 | (24) `std::vector<PackInstanceId>` | mNewWorldBehaviorPackIdentities
440 | (24) `std::vector<PackInstanceId>` | mNewWorldResourcePackIdentities
464 | (24) `GameRules` | mGameRules
488 | (112) `BaseGameVersion` | mBaseGameVersion
600 | (104) `std::optional<EducationLevelSettings>` | mEducationLevelSettings


### `LevelEventPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mEventId
40 | (12) `Vec3` | mPos
52 | (4) `int` | mData


### `Literal`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelData_0`
Offset | Type | Name
-|-|-|-
0 | (5) `AdventureSettings` | mAdventureSettings
8 | (280) `WorldTemplateLevelData` | mWorldTemplateLevelData
288 | (24) `GameRules` | mGameRules
312 | (320) `Abilities` | mDefaultAbilities
632 | (32) `std::string` | mLevelName
664 | (4) `StorageVersion` | mStorageVersion
672 | (56) `GameVersion` | mMinCompatibleClientVersion
728 | (4) `int` | mNetworkVersion
736 | (112) `SemVersion` | mInventoryVersion
848 | (8) `Tick` | mCurrentTick
856 | (4) `RandomSeed_0` | mSeed
860 | (12) `BlockPos` | mSpawnPos
872 | (1) `bool` | mHasSpawnPos
876 | (12) `BlockPos` | mLimitedWorldOrigin
888 | (4) `int` | mTime
896 | (8) `time_t` | mLastPlayed
904 | (56) `CompoundTag` | mLoadedPlayerTag
960 | (4) `uint32_t` | mServerTickRange
964 | (4) `float` | mRainLevel
968 | (4) `int` | mRainTime
972 | (4) `float` | mLightningLevel
976 | (4) `int` | mLightningTime
980 | (4) `int` | mNetherScale
984 | (56) `GameVersion` | mLastOpenedWithVersion
1040 | (4) `GameType` | mGameType
1044 | (4) `Difficulty` | mGameDifficulty
1048 | (1) `bool` | mForceGameType
1049 | (1) `bool` | mSpawnMobs
1052 | (4) `GeneratorType` | mGenerator
1056 | (16) `Json::Value` | mFlatworldGeneratorOptions
1072 | (4) `uint32_t` | mWorldStartCount
1076 | (1) `bool` | mAchievementsDisabled
1080 | (4) `EducationEditionOffer` | mEducationEditionOffer
1084 | (1) `bool` | mEducationFeaturesEnabled
1085 | (1) `bool` | mConfirmedPlatformLockedContent
1086 | (1) `bool` | mMultiplayerGameIntent
1087 | (1) `bool` | mMultiplayerGame
1088 | (1) `bool` | mLANBroadcastIntent
1089 | (1) `bool` | mLANBroadcast
1092 | (4) `Social::GamePublishSetting` | mXBLBroadcastIntent
1096 | (4) `Social::GamePublishSetting` | mXBLBroadcastMode
1100 | (4) `Social::GamePublishSetting` | mPlatformBroadcastIntent
1104 | (4) `Social::GamePublishSetting` | mPlatformBroadcastMode
1108 | (1) `bool` | mCommandsEnabled
1109 | (1) `bool` | mTexturePacksRequired
1110 | (1) `bool` | mHasLockedBehaviorPack
1111 | (1) `bool` | mHasLockedResourcePack
1112 | (1) `bool` | mIsFromLockedTemplate
1120 | (32) `std::string` | mEducationOid
1152 | (32) `std::string` | mEducationProductId
1184 | (1) `bool` | mUseMsaGamertagsOnly
1185 | (1) `bool` | mBonusChestEnabled
1186 | (1) `bool` | mBonusChestSpawned
1187 | (1) `bool` | mStartWithMapEnabled
1188 | (1) `bool` | mMapsCenteredToOrigin
1189 | (1) `bool` | mRequiresCopiedPackRemovalCheck
1190 | (1) `bool` | mSpawnV1Villagers


### `LookAtDefinition`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSetTarget
4 | (4) `float` | mSearchRadius
8 | (1) `bool` | mAllowInvulnerable
12 | (8) `FloatRange` | mLookCooldown
24 | (64) `ActorFilterGroup` | mFilter
88 | (128) `DefinitionTrigger` | mOnLookAt


### `ListTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (24) `ListTag::List` | mList
32 | (1) `Tag::Type` | mType


### `ListTag::List`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<Tag>>` | baseclass_0


### `LootTableContext::Builder`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | mLevel
8 | (4) `float` | mLuck
16 | (8) `Actor *` | mThisEntity
24 | (8) `Player *` | mKillerPlayer
32 | (8) `const ActorDamageSource *` | mDeathSource
40 | (4) `float` | mExplosionRadius


### `LONG_DOUBLE_16`
Offset | Type | Name
-|-|-|-
0 | (10) `` | value
10 | (6) `` | padding


### `Level::CompareLevelChunkQueuedSavingElement`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Level::LevelChunkQueuedSavingElement`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDist
8 | (8) `ChunkPos` | mPosition
16 | (4) `DimensionType` | mDimensionId


### `LevelEventGenericPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mEventId
40 | (8) `Unique<CompoundTag>` | mData


### `LevelSoundEventPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `LevelSoundEvent` | mEventId
40 | (12) `Vec3` | mPos
52 | (4) `int` | mData
56 | (32) `std::string` | mEntityIdentifier
88 | (1) `bool` | mIsBabyMob
89 | (1) `bool` | mIsGlobal


### `LayerResult<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `LabTablePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `LabTablePacket::Type` | mType
40 | (12) `BlockPos` | mPos
52 | (1) `LabTableReactionType` | mReaction


### `LecternUpdatePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mPage
40 | (4) `int` | mTotalPages
44 | (1) `bool` | mShouldDropBook
48 | (12) `NetworkBlockPosition` | mPos


### `LevelChunkBuilderData::ChunkReadyForProcessingElement`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos` | mCP
8 | (4) `int32_t` | mPriority


### `LevelChunkBlockActorAccessToken`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelChunkPhase1Deleter`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelChunk::HardcodedSpawningArea`
Offset | Type | Name
-|-|-|-
0 | (24) `BoundingBox` | aabb
24 | (1) `HardcodedSpawnAreaType` | type


### `LegacyBlockPlacementProcessor`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
4 | (2516) `Random` | mRandom
2520 | (1) `bool` | mHasGravity
2528 | (8) `const StructurePoolBlockRuleList *` | mBlockRules
2536 | (8) `const StructurePoolBlockTagRuleList *` | mBlockTagRules


### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `Layer<BiomeTemperatureCategory>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::`anonymous namespace'::BackCompatSorter`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LayerFilters::FilterBase<1,1,Biome *,LayerValues::PreBiome>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `Layer<LayerValues::Terrain>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerResult<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `LayerFilters::FilterBase<1,1,Biome *,Biome *>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerResult<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `LayerFilters::FilterBase<1,1,int,Biome *>::RandomProvider`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerFilters::River::operator()::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelChunkPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `bool` | mCacheEnabled
40 | (8) `ChunkPos` | mPos
48 | (32) `std::string` | mSerializedChunk
80 | (8) `size_t` | mSubChunksCount
88 | (24) `std::vector<LevelChunkPacket::SubChunkMetadata>` | mCacheMetadata


### `linger`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | l_onoff
4 | (4) `int` | l_linger


### `leveldb::Options`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::Comparator *` | comparator
8 | (1) `bool` | create_if_missing
9 | (1) `bool` | error_if_exists
10 | (1) `bool` | paranoid_checks
16 | (8) `leveldb::Env *` | env
24 | (8) `leveldb::Logger *` | info_log
32 | (8) `size_t` | write_buffer_size
40 | (4) `int` | max_open_files
48 | (8) `leveldb::Cache *` | block_cache
56 | (8) `size_t` | block_size
64 | (4) `int` | block_restart_interval
72 | (8) `size_t` | max_file_size
80 | (2048) `leveldb::Compressor *[256]` | compressors
2128 | (1) `bool` | reuse_logs
2136 | (8) `const leveldb::FilterPolicy *` | filter_policy


### `leveldb::VersionEdit`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | comparator_
32 | (8) `uint64_t` | log_number_
40 | (8) `uint64_t` | prev_log_number_
48 | (8) `uint64_t` | next_file_number_
56 | (8) `leveldb::SequenceNumber` | last_sequence_
64 | (1) `bool` | has_comparator_
65 | (1) `bool` | has_log_number_
66 | (1) `bool` | has_prev_log_number_
67 | (1) `bool` | has_next_file_number_
68 | (1) `bool` | has_last_sequence_
72 | (24) `std::vector<std::pair<int,leveldb::InternalKey>>` | compact_pointers_
96 | (48) `leveldb::VersionEdit::DeletedFileSet` | deleted_files_
144 | (24) `std::vector<std::pair<int,leveldb::FileMetaData>>` | new_files_


### `leveldb::VersionEdit::DeletedFileSet`
Offset | Type | Name
-|-|-|-
0 | (48) `std::set<std::pair<int,unsigned long>>::_Rep_type` | _M_t


### `leveldb::log::Writer`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::WritableFile *` | dest_
8 | (4) `int` | block_offset_
12 | (20) `uint32_t[5]` | type_crc_


### `leveldb::DBImpl::RecoverLogFile::LogReporter`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::log::Reader::Reporter` | baseclass_0
8 | (8) `leveldb::Env *` | env
16 | (8) `leveldb::Logger *` | info_log
24 | (8) `const char *` | fname
32 | (8) `leveldb::Status *` | status


### `leveldb::log::Reader::Reporter`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Reporter


### `leveldb::log::Reader`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::SequentialFile *const` | file_
8 | (8) `leveldb::log::Reader::Reporter *const` | reporter_
16 | (1) `const bool` | checksum_
24 | (8) `char *const` | backing_store_
32 | (16) `leveldb::Slice` | buffer_
48 | (1) `bool` | eof_
56 | (8) `uint64_t` | last_record_offset_
64 | (8) `uint64_t` | end_of_buffer_offset_
72 | (8) `const uint64_t` | initial_offset_
80 | (1) `bool` | resyncing_


### `leveldb::WriteBatch`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | rep_


### `leveldb::FileMetaData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | refs
4 | (4) `int` | allowed_seeks
8 | (8) `uint64_t` | number
16 | (8) `uint64_t` | file_size
24 | (32) `leveldb::InternalKey` | smallest
56 | (32) `leveldb::InternalKey` | largest


### `leveldb::InternalKey`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | rep_


### `leveldb::DBImpl::CompactionStats`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | micros
8 | (8) `int64_t` | bytes_read
16 | (8) `int64_t` | bytes_written


### `leveldb::MutexLock`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::port::Mutex *const` | mu_


### `leveldb::DBImpl::ManualCompaction`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | level
4 | (1) `bool` | done
8 | (8) `const leveldb::InternalKey *` | begin
16 | (8) `const leveldb::InternalKey *` | end
24 | (32) `leveldb::InternalKey` | tmp_storage


### `leveldb::VersionSet::LevelSummaryStorage`
Offset | Type | Name
-|-|-|-
0 | (100) `char[100]` | buffer


### `leveldb::ParsedInternalKey`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::Slice` | user_key
16 | (8) `leveldb::SequenceNumber` | sequence
24 | (4) `leveldb::ValueType` | type


### `leveldb::DBImpl::CompactionState::Output`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | number
8 | (8) `uint64_t` | file_size
16 | (32) `leveldb::InternalKey` | smallest
48 | (32) `leveldb::InternalKey` | largest


### `leveldb::Version::GetStats`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::FileMetaData *` | seek_file
8 | (4) `int` | seek_file_level


### `leveldb::LookupKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | start_
8 | (8) `const char *` | kstart_
16 | (8) `const char *` | end_
24 | (200) `char[200]` | space_


### `leveldb::DBImpl::Writer`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Status` | status
8 | (8) `leveldb::WriteBatch *` | batch
16 | (1) `bool` | sync
17 | (1) `bool` | done
24 | (56) `leveldb::port::CondVar` | cv


### `leveldb::port::CondVar`
Offset | Type | Name
-|-|-|-
0 | (48) `pthread_cond_t` | cv_
48 | (8) `leveldb::port::Mutex *` | mu_


### `leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator> *` | list_
8 | (8) `leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Node *` | node_


### `leveldb::`anonymous namespace'::Repairer`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | dbname_
32 | (8) `leveldb::Env *const` | env_
40 | (16) `const leveldb::InternalKeyComparator` | icmp_
56 | (16) `const leveldb::InternalFilterPolicy` | ipolicy_
72 | (2144) `const leveldb::Options` | options_
2216 | (1) `bool` | owns_info_log_
2217 | (1) `bool` | owns_cache_
2224 | (8) `leveldb::TableCache *` | table_cache_
2232 | (168) `leveldb::VersionEdit` | edit_
2400 | (24) `std::vector<std::string>` | manifests_
2424 | (24) `std::vector<unsigned long>` | table_numbers_
2448 | (24) `std::vector<unsigned long>` | logs_
2472 | (24) `std::vector<leveldb::(anonymous namespace)::Repairer::TableInfo,std::allocator<leveldb::(anonymous namespace)::Repairer::TableInfo> >` | tables_
2496 | (8) `uint64_t` | next_file_number_


### `leveldb::InternalKeyComparator`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Comparator` | baseclass_0
8 | (8) `const leveldb::Comparator *` | user_comparator_


### `leveldb::Comparator`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Comparator


### `leveldb::InternalFilterPolicy`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::FilterPolicy` | baseclass_0
8 | (8) `const leveldb::FilterPolicy *const` | user_policy_


### `leveldb::FilterPolicy`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FilterPolicy


### `leveldb::`anonymous namespace'::Repairer::ConvertLogToTable::LogReporter`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::log::Reader::Reporter` | baseclass_0
8 | (8) `leveldb::Env *` | env
16 | (8) `leveldb::Logger *` | info_log
24 | (8) `uint64_t` | lognum


### `leveldb::`anonymous namespace'::Repairer::TableInfo`
Offset | Type | Name
-|-|-|-
0 | (88) `leveldb::FileMetaData` | meta
88 | (8) `leveldb::SequenceNumber` | max_sequence


### `leveldb::ReadOptions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | verify_checksums
1 | (1) `bool` | fill_cache
8 | (8) `const leveldb::Snapshot *` | snapshot
16 | (8) `leveldb::DecompressAllocator *` | decompress_allocator


### `leveldb::VersionSet::Builder::BySmallestKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::InternalKeyComparator *` | internal_comparator


### `leveldb::Version::RecordReadSample::State`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::Version::GetStats` | stats
16 | (4) `int` | matches


### `leveldb::`anonymous namespace'::Saver`
Offset | Type | Name
-|-|-|-
0 | (4) `leveldb::`anonymous namespace'::SaverState` | state
8 | (8) `const leveldb::Comparator *` | ucmp
16 | (16) `leveldb::Slice` | user_key
32 | (8) `std::string *` | value


### `leveldb::VersionSet::Builder`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::VersionSet *` | vset_
8 | (8) `leveldb::Version *` | base_
16 | (392) `leveldb::VersionSet::Builder::LevelState[7]` | levels_


### `leveldb::VersionSet::Builder::LevelState`
Offset | Type | Name
-|-|-|-
0 | (48) `std::set<unsigned long>` | deleted_files
48 | (8) `leveldb::VersionSet::Builder::FileSet *` | added_files


### `leveldb::VersionSet::Recover::LogReporter`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::log::Reader::Reporter` | baseclass_0
8 | (8) `leveldb::Status *` | status


### `leveldb::`anonymous namespace'::MemTableInserter`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::WriteBatch::Handler` | baseclass_0
8 | (8) `leveldb::SequenceNumber` | sequence_
16 | (8) `leveldb::MemTable *` | mem_


### `leveldb::WriteBatch::Handler`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Handler


### `leveldb::Footer`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::BlockHandle` | metaindex_handle_
16 | (16) `leveldb::BlockHandle` | index_handle_


### `leveldb::BlockHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | offset_
8 | (8) `uint64_t` | size_


### `leveldb::BlockContents`
Offset | Type | Name
-|-|-|-
0 | (16) `leveldb::Slice` | data
16 | (1) `bool` | cachable
17 | (1) `bool` | heap_allocated


### `leveldb::BlockBuilder`
Offset | Type | Name
-|-|-|-
0 | (8) `const leveldb::Options *` | options_
8 | (32) `std::string` | buffer_
40 | (24) `std::vector<unsigned int>` | restarts_
64 | (4) `int` | counter_
68 | (1) `bool` | finished_
72 | (32) `std::string` | last_key_


### `linkedlist_data`
Offset | Type | Name
-|-|-|-
0 | (8) `linkedlist_datablock_internal *` | first_block
8 | (8) `linkedlist_datablock_internal *` | last_block


### `link_map`
Offset | Type | Name
-|-|-|-
0 | (8) `Elf64_Addr` | l_addr
8 | (8) `char *` | l_name
16 | (8) `Elf64_Dyn_0 *` | l_ld
24 | (8) `link_map *` | l_next
32 | (8) `link_map *` | l_prev


### `LocalConnectivitySystem`
Offset | Type | Name
-|-|-|-
0 | (8) `LocalConnector *` | mHostConnector


### `leveldb::Logger`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Logger


### `LevelListener`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSourceListener` | baseclass_0


### `LevelChunkGarbageCollector`
Offset | Type | Name
-|-|-|-
0 | (8) `Dimension *` | mDimension
8 | (616) `MPMCQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter> >` | mLevelChunksToDiscard
624 | (8) `std::atomic_size_t` | mPendingDeletes


### `LayerDetails::TransferData<LayerValues::Terrain>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `LayerDetails::BufferAccessor<LayerValues::Terrain>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LayerDetails::RandomProviderT<(lambda at _Minecraftpe_handheld_project_dedicated_server_______src_common_world_level_newbiome_LayerDetails_h:221:34)>`
Offset | Type | Name
-|-|-|-
0 | (8) `$9B9F62DABB3B3036AEF15BA6ABCB0C35` | mNextRandom
8 | (8) `int64_t` | mRval


### `LayerDetails::BufferAccessor<LayerValues::PreBiome>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LayerDetails::TransferData<LayerValues::PreBiome>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `LayerDetails::BufferAccessor<Biome *>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LayerDetails::TransferData<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `LayerDetails::BufferAccessor<int>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LayerDetails::TransferData<int>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `LayerDetails::BufferAccessor<bool>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LayerDetails::TransferData<bool>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `Layer<bool>`
Offset | Type | Name
-|-|-|-
0 | (24) `LayerDetails::LayerBase` | baseclass_0


### `LayerDetails::LayerBase`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$LayerBase
8 | (8) `int64_t` | mSeed
16 | (8) `int64_t` | mSeedMixup


### `LayerDetails::TransferData<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (32) `LayerDetails::Storage` | baseclass_0


### `LayerDetails::BufferAccessor<BiomeTemperatureCategory>::TypedBits`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | mLocation


### `LegacyStructureTemplate`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mAuthor
32 | (12) `BlockPos` | mSize
48 | (56) `LegacyStructureBlockPalette` | mPalette
104 | (56) `LegacyStructureBlockPalette` | mExtraBlockPalette
160 | (24) `std::vector<LegacyStructureBlockInfo>` | mBlockInfo
184 | (24) `std::vector<LegacyStructureActorInfo>` | mEntityInfo


### `LegacyStructureBlockPalette`
Offset | Type | Name
-|-|-|-
0 | (56) `BlockMap` | mMapper


### `LocalConnector::ConnectionCallbacks`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ConnectionCallbacks


### `Lockless::WeakAtomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<SPSCQueue<std::shared_ptr<BackgroundTask>,512>::Block *>` | mValue


### `LegacyPackIdVersion`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mId
32 | (32) `std::string` | mVersion


### `leveldb::ZlibCompressor`
Offset | Type | Name
-|-|-|-
0 | (40) `leveldb::ZlibCompressorBase` | baseclass_0


### `leveldb::ZlibCompressorBase`
Offset | Type | Name
-|-|-|-
0 | (28) `__int8[28]` | baseclass_0
28 | (4) `const int` | compressionLevel
32 | (1) `const bool` | raw


### `ListTagFloatAdder`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<ListTag>` | mTag


### `Llama::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Layer<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (24) `LayerDetails::LayerBase` | baseclass_0


### `ListTagIntAdder`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<ListTag>` | mTag


### `LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>>` | mChunkElemMap
56 | (32) `SpinLock` | mSpinLock


### `LevelChunk::_createSubChunk::$31B85587540760296E2FBFD5D423D7F3`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelChunk *` | this
8 | (1) `bool` | initSkyLight
12 | (4) `SubChunkInitMode` | initBlocks
16 | (8) `size_t` | idx


### `LevelChunk::tick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelChunk::setUnsaved::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `LevelChunk::needsSaving::$0DAA62F87AF08124C8B5CE4526C39CCA`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | shouldSave
8 | (4) `int` | wait
12 | (4) `int` | maxWait


### `LevelChunk::setSaved::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Layer<BiomeTemperatureCategory>`
Offset | Type | Name
-|-|-|-
0 | (24) `LayerDetails::LayerBase` | baseclass_0


### `ListenerSet`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<int,std::unique_ptr<ListenerInfo>>::_Hashtable` | _M_h


### `leveldb::Env`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Env


### `leveldb::SequentialFileEncrypted`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::SequentialFile` | baseclass_0
8 | (8) `leveldb::SequentialFile *` | _file
16 | (16) `std::shared_ptr<Crypto::Symmetric::Symmetric>` | _encryption


### `leveldb::SequentialFile`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$SequentialFile


### `leveldb::DBImpl`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::DB` | baseclass_0
8 | (8) `leveldb::Env *const` | env_
16 | (16) `const leveldb::InternalKeyComparator` | internal_comparator_
32 | (16) `const leveldb::InternalFilterPolicy` | internal_filter_policy_
48 | (2144) `const leveldb::Options` | options_
2192 | (1) `bool` | owns_info_log_
2193 | (1) `bool` | owns_cache_
2200 | (32) `const std::string` | dbname_
2232 | (8) `leveldb::TableCache *` | table_cache_
2240 | (8) `leveldb::FileLock *` | db_lock_
2248 | (40) `leveldb::port::Mutex` | mutex_
2288 | (8) `leveldb::port::AtomicPointer` | shutting_down_
2296 | (56) `leveldb::port::CondVar` | bg_cv_
2352 | (8) `leveldb::MemTable *` | mem_
2360 | (8) `leveldb::MemTable *` | imm_
2368 | (8) `leveldb::port::AtomicPointer` | has_imm_
2376 | (8) `leveldb::WritableFile *` | logfile_
2384 | (8) `uint64_t` | logfile_number_
2392 | (8) `leveldb::log::Writer *` | log_
2400 | (4) `uint32_t` | seed_
2408 | (80) `std::deque<leveldb::DBImpl::Writer *>` | writers_
2488 | (8) `leveldb::WriteBatch *` | tmp_batch_
2496 | (40) `leveldb::SnapshotList` | snapshots_
2536 | (48) `std::set<unsigned long>` | pending_outputs_
2584 | (1) `bool` | bg_compaction_scheduled_
2592 | (8) `leveldb::port::AtomicPointer` | suspending_compaction_
2600 | (8) `leveldb::DBImpl::ManualCompaction *` | manual_compaction_
2608 | (8) `leveldb::VersionSet *` | versions_
2616 | (8) `leveldb::Status` | bg_error_
2624 | (168) `leveldb::DBImpl::CompactionStats[7]` | stats_


### `leveldb::DB`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$DB


### `leveldb::port::Mutex`
Offset | Type | Name
-|-|-|-
0 | (40) `pthread_mutex_t` | mu_


### `leveldb::port::AtomicPointer`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | rep_


### `leveldb::SnapshotList`
Offset | Type | Name
-|-|-|-
0 | (40) `leveldb::SnapshotImpl` | list_


### `leveldb::SnapshotImpl`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Snapshot` | baseclass_0
8 | (8) `leveldb::SequenceNumber` | number_
16 | (8) `leveldb::SnapshotImpl *` | prev_
24 | (8) `leveldb::SnapshotImpl *` | next_
32 | (8) `leveldb::SnapshotList *` | list_


### `leveldb::Snapshot`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Snapshot


### `leveldb::VersionSet`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Env *const` | env_
8 | (32) `const std::string` | dbname_
40 | (8) `const leveldb::Options *const` | options_
48 | (8) `leveldb::TableCache *const` | table_cache_
56 | (16) `const leveldb::InternalKeyComparator` | icmp_
72 | (8) `uint64_t` | next_file_number_
80 | (8) `uint64_t` | manifest_file_number_
88 | (8) `uint64_t` | last_sequence_
96 | (8) `uint64_t` | log_number_
104 | (8) `uint64_t` | prev_log_number_
112 | (8) `leveldb::WritableFile *` | descriptor_file_
120 | (8) `leveldb::log::Writer *` | descriptor_log_
128 | (232) `leveldb::Version` | dummy_versions_
360 | (8) `leveldb::Version *` | current_
368 | (224) `std::string[7]` | compact_pointer_


### `leveldb::Version`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::VersionSet *` | vset_
8 | (8) `leveldb::Version *` | next_
16 | (8) `leveldb::Version *` | prev_
24 | (4) `int` | refs_
32 | (168) `std::vector<leveldb::FileMetaData *>[7]` | files_
200 | (8) `leveldb::FileMetaData *` | file_to_compact_
208 | (4) `int` | file_to_compact_level_
216 | (8) `double` | compaction_score_
224 | (4) `int` | compaction_level_


### `leveldb::WriteOptions`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | sync


### `leveldb::TableBuilder`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::TableBuilder::Rep *` | rep_


### `leveldb::MemTable::KeyComparator`
Offset | Type | Name
-|-|-|-
0 | (16) `const leveldb::InternalKeyComparator` | comparator


### `leveldb::Table`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Table::Rep *` | rep_


### `leveldb::TableCache`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Env *const` | env_
8 | (32) `const std::string` | dbname_
40 | (8) `const leveldb::Options *` | options_
48 | (8) `leveldb::Cache *` | cache_


### `leveldb::IteratorWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Iterator *` | iter_
8 | (1) `bool` | valid_
16 | (16) `leveldb::Slice` | key_


### `leveldb::RandomAccessFile`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$RandomAccessFile


### `Lockless::WeakAtomic<unsigned long>`
```
struct Lockless::WeakAtomic<unsigned long>
{
  std::atomic<unsigned long> mValue;
};

```

### `Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *>`
```
struct Lockless::WeakAtomic<SPSCQueue<std::string,512>::Block *>
{
  std::atomic<SPSCQueue<std::string,512>::Block *> mValue;
};

```

### `ldiv_t`
```
struct ldiv_t
{
  __int64 quot;
  __int64 rem;
};

```

### `lldiv_t`
```
struct lldiv_t
{
  __int64 quot;
  __int64 rem;
};

```

### `LevelStorage`
```
struct LevelStorage
{
  int (**_vptr$LevelStorage)(void);
};

```

### `Level`
```
struct __cppobj Level : BlockSourceListener, IWorldRegistriesProvider
{
  std::vector<ChunkPos> mTickingChunksOffset;
  std::vector<ChunkPos> mClientTickingChunksOffset;
  std::vector<std::unique_ptr<Player>> mPlayers;
  PlayerList mActivePlayers;
  PlayerList mSuspendedPlayers;
  std::vector<PlayerSuspension> mSuspendResumeList;
  TagRegistry mTagRegistry;
  Shared<ActorInfoRegistry> mActorInfoRegistry;
  SoundPlayer *mSoundPlayer;
  bool mIsFindingSpawn;
  bool mSpawnEntities;
  ActorUniqueID mLastUniqueID;
  ActorRuntimeID mLastRuntimeID;
  std::unordered_map<ActorRuntimeID,ActorUniqueID> mRuntimeIdMap;
  ListenerList mListeners;
  Unique<LevelStorage> mLevelStorage;
  Unique<SavedDataStorage> mSavedDataStorage;
  Unique<PhotoStorage> mPhotoStorage;
  LevelDataWrapper mLevelData;
  Level::RegionSet mRegions;
  Unique<ActorDefinitionGroup> mEntityDefinitions;
  Unique<ActorAnimationGroup> mActorAnimationGroup;
  Unique<ActorAnimationControllerGroup> mActorAnimationControllerGroup;
  Unique<BlockComponentFactory> mBlockComponentFactory;
  Unique<BlockDefinitionGroup> mBlockDefinitions;
  Unique<ActorSpawnRuleGroup> mActorSpawnRules;
  Unique<SpawnGroupRegistry> mSpawnGroupRegistry;
  Unique<Spawner> mMobSpawner;
  Unique<ProjectileFactory> mProjectileFactory;
  Unique<BehaviorFactory> mBehaviorFactory;
  Unique<BehaviorTreeGroup> mBehaviorTreeDefinitions;
  Unique<BlockPalette> mGlobalBlockPalette;
  Unique<Recipes> mRecipes;
  DimensionMap mDimensions;
  Unique<PortalForcer> mPortalForcer;
  Level::BossEventListenerList mBossEventListeners;
  Level::ChangeDimensionRequestMap mChangeDimensionRequests;
  PlayerListEntries mPlayerList;
  PacketSender *mPacketSender;
  HitResult mHitResult;
  HitResult mLiquidHitResult;
  Random mRandom;
  Random mAnimateRandom;
  NetEventCallback *mNetEventCallback;
  OwnedActorSet mPendingEntitiesToRemove;
  bool mUpdatingBlockEntities;
  GlobalActorList mGlobalEntities;
  AutonomousActorList mAutonomousEntities;
  OwnedActorList mAutonomousLoadedEntities;
  const bool mIsClientSide;
  bool mIsExporting;
  std::vector<PendingRemovalInfo> mPendingPlayerRemovals;
  int64_t mLastTimePacketSent;
  bool mChunkSaveInProgress;
  bool mSimPaused;
  std::unique_ptr<TaskGroup> mMainThreadTaskGroup;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  Scheduler *mScheduler;
  std::string mLevelId;
  std::priority_queue<Level::LevelChunkQueuedSavingElement,std::vector<Level::LevelChunkQueuedSavingElement>,Level::CompareLevelChunkQueuedSavingElement> mLevelChunkSaveQueue;
  Unique<TickingAreasManager> mTickingAreasMgr;
  std::unordered_set<_TickPtr *> mTempTickPointers;
  std::unordered_map<ActorUniqueID,std::unique_ptr<MapItemSavedData>> mMapData;
  std::unordered_map<ActorUniqueID,Abilities> mAbilitiesData;
  bool mTearingDown;
  IMinecraftEventing *mEventing;
  std::unique_ptr<PlayerEventCoordinator> mRemotePlayerEventCoordinator;
  std::unique_ptr<ServerPlayerEventCoordinator> mServerPlayerEventCoordinator;
  std::unique_ptr<ClientPlayerEventCoordinator> mClientPlayerEventCoordinator;
  std::unique_ptr<ActorEventCoordinator> mActorEventCoordinator;
  std::unique_ptr<ClientLevelEventCoordinator> mClientLevelEventCoordinator;
  std::unique_ptr<ServerLevelEventCoordinator> mServerLevelEventCoordinator;
  std::unique_ptr<BlockEventCoordinator> mBlockEventCoordinator;
  std::unique_ptr<ItemEventCoordinator> mItemEventCoordinator;
  StructureManager *mStructureManager;
  ActorUniqueID mParentMapId;
  bool mIsFinishedInitializing;
  std::chrono::_V2::steady_clock::time_point mNextSaveDataTime;
  std::chrono::_V2::steady_clock::time_point mNextStorageCheckTime;
  bool mStorageActionsDeferred;
  LootTables mLootTables;
  uint32_t mMobTickCount;
  uint32_t mMobTickCountPrevious;
  std::unique_ptr<Scoreboard> mScoreboard;
  const BlockLegacy *mRegisteredBorderBlock;
  ActorFactory mActorFactory;
  IEntityRegistryOwner *mEntityRegistryOwner;
  EntitySystems mEntitySystems;
  std::unordered_map<EntityNetId,EntityOptionalOwnerRef> mSimulatedEntities;
  std::unique_ptr<FeatureRegistry> mFeatureRegistry;
  std::unique_ptr<FeatureTypeFactory> mFeatureTypeFactory;
  JigsawStructureRegistry mJigsawStructureRegistry;
  std::unique_ptr<BiomeRegistry> mBiomes;
  std::unique_ptr<BiomeComponentFactory> mBiomeComponentFactory;
  std::unique_ptr<SurfaceBuilderRegistry> mSurfaceBuilders;
  Factory<Dimension,Level &,Scheduler &> mDimensionFactory;
  std::optional<EducationLevelSettings> mEducationLevelSettings;
  WireframeQueue mWireframeQueue;
  BlockActorLevelListener mBlockActorLevelListener;
  bool mServerAuthoritativeMovement;
  bool mShouldCorrectPlayerMovement;
  float mPlayerMovementScoreThreshold;
  float mPlayerMovementDistanceThreshold;
  float mPlayerMovementDistanceThresholdSqr;
  std::chrono::milliseconds mPlayerMovementDurationThreshold;
};

```

### `LevelSummary`
```
struct LevelSummary
{
  std::string mId;
  std::string mName;
  time_t mLastPlayed;
  GameType mGameType;
  Difficulty mGameDifficulty;
  int mSeed;
  int mNetworkProtocolVersion;
  uint64_t mSizeOnDisk;
  bool mConfirmedPlatformLockedContent;
  bool mLANBroadcastIntent;
  Social::GamePublishSetting mXBLBroadcastIntent;
  bool mCommandsEnabled;
  EducationEditionOffer mEducationEditionOffer;
  GameVersion mLastLoadedGameVersion;
  GameVersion mMinCompatibleClientVersion;
  StorageVersion mStorageVersion;
  Core::HeapPathBuffer mWorldIconPath;
  Core::HeapPathBuffer mWorldIconTargetPath;
  ContentIdentity mPremiumTemplateContentIdentity;
};

```

### `LookControlSystem`
```
struct __cppobj LookControlSystem : ITickingSystem
{
};

```

### `LeashableSystem`
```
struct __cppobj LeashableSystem : ITickingSystem
{
};

```

### `LookAtSystem`
```
struct __cppobj LookAtSystem : ITickingSystem
{
};

```

### `LevelEventListener`
```
struct LevelEventListener
{
  int (**_vptr$LevelEventListener)(void);
};

```

### `LegacyForestFoliageFeature`
```
struct __cppobj LegacyForestFoliageFeature : Feature
{
  LegacyForestFoliageFeature::Type mForestType;
  WeakRef<IFeature> mHugeMushroomFeature;
  WeakRef<IFeature> mTallGrassFeature;
  WeakRef<IFeature> mDoublePlantFeature;
  WeakRef<IFeature> mRoofTreeFeature;
  WeakRef<IFeature> mBirchFeature;
  WeakRef<IFeature> mFancyTreeFeature;
  WeakRef<IFeature> mOakFeature;
};

```

### `LegacyTreeFeature`
```
struct __cppobj LegacyTreeFeature : Feature
{
  std::unique_ptr<PerlinSimplexNoise> mBiomeInfoNoise;
  WeakRef<IFeature> mTallGrassFeature;
  float mTreeCount;
  std::vector<WeakRefT<FeatureRefTraits>> mFeatureRefs;
  std::function<WeakRefT<FeatureRefTraits> (Random &)> mGetTreeFeature;
};

```

### `LegacySwampFoliageFeature`
```
struct __cppobj LegacySwampFoliageFeature : Feature
{
  std::function<WeakRefT<FeatureRefTraits> (Random &)> mGetTreeFeature;
  WeakRef<IFeature> mSeagrassFeature;
  WeakRef<IFeature> mTallGrassFeature;
  WeakRef<IFeature> mHugeMushroomFeature;
  WeakRef<IFeature> mSwampTreeFeature;
};

```

### `LegacyFlowerFeature`
```
struct __cppobj LegacyFlowerFeature : Feature
{
  LegacyFlowerFeature::Type mPlacementType;
  OwnerPtr<PerlinSimplexNoise> mBiomeInfoNoise;
};

```

### `LegacySpringsFeature`
```
struct __cppobj LegacySpringsFeature : Feature
{
  WeakRef<IFeature> mWaterSpringFeature;
  WeakRef<IFeature> mLavaSpringFeature;
};

```

### `LegacyEmeraldOreFeature`
```
struct __cppobj LegacyEmeraldOreFeature : Feature
{
};

```

### `LegacyForestRockFeature`
```
struct __cppobj LegacyForestRockFeature : Feature
{
  WeakRef<IFeature> mForestRockFeature;
};

```

### `LegacySmallMushroomsFeature`
```
struct __cppobj LegacySmallMushroomsFeature : Feature
{
  WeakRef<IFeature> mBrownMushroomFeature;
  WeakRef<IFeature> mRedMushroomFeature;
};

```

### `LegacyIceFeature`
```
struct __cppobj LegacyIceFeature : Feature
{
  WeakRef<IFeature> mIcebergFeature;
  WeakRef<IFeature> mBlueIceFeature;
};

```

### `LevelChunkBuilderData`
```
struct LevelChunkBuilderData
{
  SpinLock mChunkGenerationGridMapSpinLock;
  std::unordered_map<ChunkPos,std::shared_ptr<LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> > >> mChunkGenerationGridMap;
  SpinLock mChunksToAddToProcessingSpinLock;
  std::vector<ChunkPos> mChunksToAddToProcessing;
  SpinLock mChunksReadyForProcessingSpinLock;
  std::unordered_set<ChunkPos> mChunksReadyForProcessing;
  std::vector<LevelChunkBuilderData::ChunkReadyForProcessingElement> mChunkSortVector;
  std::atomic<int> mChunkGenerationTasksInFlight;
  SpinLock mSpawnTasksLock;
};

```

### `LargeHellCaveFeature`
```
struct LargeHellCaveFeature
{
  __int8 gap0[1];
};

```

### `Layer<LayerValues::Terrain>`
```
struct __cppobj Layer<LayerValues::Terrain> : LayerDetails::LayerBase
{
};

```

### `LayerZooms::Zoom2xFuzzy`
```
struct __cppobj LayerZooms::Zoom2xFuzzy : LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>
{
};

```

### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>`
```
struct LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>
{
  __int8 gap0[1];
};

```

### `LayerFilters::AddIsland`
```
struct __cppobj LayerFilters::AddIsland : LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>
{
};

```

### `LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>`
```
struct LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>
{
  __int8 gap0[1];
};

```

### `LayerZooms::Zoom2x`
```
struct __cppobj LayerZooms::Zoom2x : LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>
{
};

```

### `LayerFilters::RemoveTooMuchOcean`
```
struct __cppobj LayerFilters::RemoveTooMuchOcean : LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>
{
};

```

### `Layer<LayerValues::PreBiome>`
```
struct __cppobj Layer<LayerValues::PreBiome> : LayerDetails::LayerBase
{
};

```

### `LayerFilters::AddSnow`
```
struct __cppobj LayerFilters::AddSnow : LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>
{
};

```

### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>`
```
struct LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>
{
  __int8 gap0[1];
};

```

### `LayerFilters::AddIslandWithTemperature`
```
struct __cppobj LayerFilters::AddIslandWithTemperature : LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>
{
};

```

### `LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>`
```
struct LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>
{
  __int8 gap0[1];
};

```

### `LayerFilters::AddEdgeCoolWarm`
```
struct __cppobj LayerFilters::AddEdgeCoolWarm : LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>
{
};

```

### `LayerFilters::AddEdgeHeatIce`
```
struct __cppobj LayerFilters::AddEdgeHeatIce : LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>
{
};

```

### `LayerFilters::AddEdgeSpecial`
```
struct __cppobj LayerFilters::AddEdgeSpecial : LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>
{
};

```

### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>`
```
struct LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>
{
  __int8 gap0[1];
};

```

### `LayerFilters::BiomeInit`
```
struct LayerFilters::BiomeInit
{
  Biome *mFallbackBiome;
  Biome *mDefaultOcean;
  std::vector<std::pair<Biome *,unsigned int>> mRegularBiomes[5];
  std::vector<std::pair<Biome *,unsigned int>> mSpecialBiomes[5];
};

```

### `LayerFilters::FilterBase<1,1,Biome *,LayerValues::PreBiome>`
```
struct LayerFilters::FilterBase<1,1,Biome *,LayerValues::PreBiome>
{
  __int8 gap0[1];
};

```

### `LayerFilters::AddMushroomIsland`
```
struct LayerFilters::AddMushroomIsland
{
  Biome *mMushroomBiome;
  const BiomeRegistry *mBiomeRegistry;
};

```

### `LayerFilters::FilterBase<3,3,Biome *,Biome *>`
```
struct LayerFilters::FilterBase<3,3,Biome *,Biome *>
{
  __int8 gap0[1];
};

```

### `LayerFilters::PromoteCenter`
```
struct LayerFilters::PromoteCenter
{
  Biome *mFrom;
  Biome *mTo;
};

```

### `Layer<int>`
```
struct __cppobj Layer<int> : LayerDetails::LayerBase
{
};

```

### `LayerFilters::RiverInit`
```
struct LayerFilters::RiverInit
{
  std::vector<Biome *> mNoRiverBiomes;
};

```

### `LayerFilters::FilterBase<1,1,int,Biome *>`
```
struct LayerFilters::FilterBase<1,1,int,Biome *>
{
  __int8 gap0[1];
};

```

### `LayerFilters::River`
```
struct __cppobj LayerFilters::River : LayerFilters::FilterBase<3,3,bool,int>
{
};

```

### `LayerFilters::FilterBase<3,3,bool,int>`
```
struct LayerFilters::FilterBase<3,3,bool,int>
{
  __int8 gap0[1];
};

```

### `LayerFilters::Smooth<bool>`
```
struct __cppobj LayerFilters::Smooth<bool> : LayerFilters::FilterBase<3,3,bool,bool>
{
};

```

### `LayerFilters::FilterBase<3,3,bool,bool>`
```
struct LayerFilters::FilterBase<3,3,bool,bool>
{
  __int8 gap0[1];
};

```

### `LayerFilters::RareBiomeSpot`
```
struct LayerFilters::RareBiomeSpot
{
  uint32_t mChance;
  Biome *mFromBiome;
  Biome *mToBiome;
};

```

### `LayerFilters::FilterBase<1,1,Biome *,Biome *>`
```
struct LayerFilters::FilterBase<1,1,Biome *,Biome *>
{
  __int8 gap0[1];
};

```

### `LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >`
```
struct LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> >
{
  const TagRegistry *mTagRegistry;
};

```

### `LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >`
```
struct LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> >
{
  const TagRegistry *mTagRegistry;
};

```

### `LayerFilters::AddBiomeIsland`
```
struct LayerFilters::AddBiomeIsland
{
  Biome *mDefaultIsland;
  Biome *mSpecialIsland;
  std::vector<Biome *> mShallowOceanBiomes;
};

```

### `LayerFilters::Shore`
```
struct LayerFilters::Shore
{
  Biome *mDefaultShore;
  std::vector<Biome *> mOceanBiomes;
};

```

### `LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >`
```
struct LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> >
{
  const TagRegistry *mTagRegistry;
};

```

### `LayerFilters::Smooth<Biome *>`
```
struct __cppobj LayerFilters::Smooth<Biome *> : LayerFilters::FilterBase<3,3,Biome *,Biome *>
{
};

```

### `LayerFilters::AddOceanEdge`
```
struct __cppobj LayerFilters::AddOceanEdge : LayerFilters::FilterBase<3,3,BiomeTemperatureCategory,BiomeTemperatureCategory>
{
};

```

### `LayerFilters::FilterBase<3,3,BiomeTemperatureCategory,BiomeTemperatureCategory>`
```
struct LayerFilters::FilterBase<3,3,BiomeTemperatureCategory,BiomeTemperatureCategory>
{
  __int8 gap0[1];
};

```

### `LayerZooms::Zoom4xVoronoi`
```
struct __cppobj LayerZooms::Zoom4xVoronoi : LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>
{
};

```

### `LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>`
```
struct LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>
{
  __int8 gap0[1];
};

```

### `LayerDetails::WorkingData<LayerValues::Terrain,char>`
```
struct __cppobj LayerDetails::WorkingData<LayerValues::Terrain,char> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<char> mParentArea;
  LayerDetails::BufferAccessor<LayerValues::Terrain> mResult;
};

```

### `LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain>`
```
struct __cppobj LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<LayerValues::Terrain> mParentArea;
  LayerDetails::BufferAccessor<LayerValues::Terrain> mResult;
};

```

### `LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::Terrain>`
```
struct __cppobj LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::Terrain> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<LayerValues::Terrain> mParentArea;
  LayerDetails::BufferAccessor<LayerValues::PreBiome> mResult;
};

```

### `LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome>`
```
struct __cppobj LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<LayerValues::PreBiome> mParentArea;
  LayerDetails::BufferAccessor<LayerValues::PreBiome> mResult;
};

```

### `LayerDetails::WorkingData<Biome *,LayerValues::PreBiome>`
```
struct __cppobj LayerDetails::WorkingData<Biome *,LayerValues::PreBiome> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<LayerValues::PreBiome> mParentArea;
  LayerDetails::BufferAccessor<Biome *> mResult;
};

```

### `LayerDetails::WorkingData<Biome *,Biome *>`
```
struct __cppobj LayerDetails::WorkingData<Biome *,Biome *> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<Biome *> mParentArea;
  LayerDetails::BufferAccessor<Biome *> mResult;
};

```

### `LayerDetails::WorkingData<int,Biome *>`
```
struct __cppobj LayerDetails::WorkingData<int,Biome *> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<Biome *> mParentArea;
  LayerDetails::BufferAccessor<int> mResult;
};

```

### `LayerDetails::WorkingData<int,int>`
```
struct __cppobj LayerDetails::WorkingData<int,int> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<int> mParentArea;
  LayerDetails::BufferAccessor<int> mResult;
};

```

### `LayerDetails::WorkingData<bool,int>`
```
struct __cppobj LayerDetails::WorkingData<bool,int> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<int> mParentArea;
  LayerDetails::BufferAccessor<bool> mResult;
};

```

### `LayerDetails::WorkingData<bool,bool>`
```
struct __cppobj LayerDetails::WorkingData<bool,bool> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<bool> mParentArea;
  LayerDetails::BufferAccessor<bool> mResult;
};

```

### `LayerDetails::WorkingData<BiomeTemperatureCategory,char>`
```
struct __cppobj LayerDetails::WorkingData<BiomeTemperatureCategory,char> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<char> mParentArea;
  LayerDetails::BufferAccessor<BiomeTemperatureCategory> mResult;
};

```

### `LayerDetails::WorkingData<BiomeTemperatureCategory,BiomeTemperatureCategory>`
```
struct __cppobj LayerDetails::WorkingData<BiomeTemperatureCategory,BiomeTemperatureCategory> : LayerDetails::Storage
{
  const LayerDetails::BufferAccessor<BiomeTemperatureCategory> mParentArea;
  LayerDetails::BufferAccessor<BiomeTemperatureCategory> mResult;
};

```

### `LargeCaveFeature`
```
struct LargeCaveFeature
{
  int (**_vptr$LargeCaveFeature)(void);
};

```

### `LayerDetails::RandomProvider`
```
typedef LayerDetails::RandomProviderT<(lambda at _Minecraftpe_handheld_project_dedicated_server_______src_common_world_level_newbiome_LayerDetails_h:221:34)> LayerDetails::RandomProvider;

```

### `LayerDetails::NeighborhoodReader<LayerValues::Terrain,1,1>`
```
struct LayerDetails::NeighborhoodReader<LayerValues::Terrain,1,1>
{
  const LayerDetails::BufferAccessor<LayerValues::Terrain> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<LayerValues::Terrain,0,0>`
```
struct LayerDetails::NeighborhoodReader<LayerValues::Terrain,0,0>
{
  const LayerDetails::BufferAccessor<LayerValues::Terrain> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<LayerValues::PreBiome,1,1>`
```
struct LayerDetails::NeighborhoodReader<LayerValues::PreBiome,1,1>
{
  const LayerDetails::BufferAccessor<LayerValues::PreBiome> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<LayerValues::PreBiome,0,0>`
```
struct LayerDetails::NeighborhoodReader<LayerValues::PreBiome,0,0>
{
  const LayerDetails::BufferAccessor<LayerValues::PreBiome> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<Biome *,1,1>`
```
struct LayerDetails::NeighborhoodReader<Biome *,1,1>
{
  const LayerDetails::BufferAccessor<Biome *> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<Biome *,0,0>`
```
struct LayerDetails::NeighborhoodReader<Biome *,0,0>
{
  const LayerDetails::BufferAccessor<Biome *> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<int,1,1>`
```
struct LayerDetails::NeighborhoodReader<int,1,1>
{
  const LayerDetails::BufferAccessor<int> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<bool,1,1>`
```
struct LayerDetails::NeighborhoodReader<bool,1,1>
{
  const LayerDetails::BufferAccessor<bool> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerDetails::NeighborhoodReader<BiomeTemperatureCategory,1,1>`
```
struct LayerDetails::NeighborhoodReader<BiomeTemperatureCategory,1,1>
{
  const LayerDetails::BufferAccessor<BiomeTemperatureCategory> *mSourceData;
  int32_t mTopLeft;
  int32_t mW;
};

```

### `LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<LayerValues::Terrain,1,1> LayerFilters::FilterBase<3,3,LayerValues::Terrain,LayerValues::Terrain>::ReaderType;

```

### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<LayerValues::Terrain,0,0> LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::Terrain>::ReaderType;

```

### `LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<LayerValues::PreBiome,1,1> LayerFilters::FilterBase<3,3,LayerValues::PreBiome,LayerValues::PreBiome>::ReaderType;

```

### `LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<LayerValues::PreBiome,0,0> LayerFilters::FilterBase<1,1,LayerValues::PreBiome,LayerValues::PreBiome>::ReaderType;

```

### `LayerFilters::FilterBase<1,1,Biome *,LayerValues::PreBiome>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<LayerValues::PreBiome,0,0> LayerFilters::FilterBase<1,1,Biome *,LayerValues::PreBiome>::ReaderType;

```

### `LayerFilters::FilterBase<3,3,Biome *,Biome *>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<Biome *,1,1> LayerFilters::FilterBase<3,3,Biome *,Biome *>::ReaderType;

```

### `LayerFilters::FilterBase<1,1,int,Biome *>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<Biome *,0,0> LayerFilters::FilterBase<1,1,int,Biome *>::ReaderType;

```

### `LayerFilters::FilterBase<3,3,bool,int>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<int,1,1> LayerFilters::FilterBase<3,3,bool,int>::ReaderType;

```

### `LayerFilters::FilterBase<3,3,bool,bool>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<bool,1,1> LayerFilters::FilterBase<3,3,bool,bool>::ReaderType;

```

### `LayerFilters::FilterBase<1,1,Biome *,Biome *>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<Biome *,0,0> LayerFilters::FilterBase<1,1,Biome *,Biome *>::ReaderType;

```

### `LayerFilters::FilterBase<3,3,BiomeTemperatureCategory,BiomeTemperatureCategory>::ReaderType`
```
typedef LayerDetails::NeighborhoodReader<BiomeTemperatureCategory,1,1> LayerFilters::FilterBase<3,3,BiomeTemperatureCategory,BiomeTemperatureCategory>::ReaderType;

```

### `LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::RandomArrayUnpacker`
```
typedef std::make_index_sequence<RANDOM_ARRAY_SIZE> LayerZooms::ZoomBase<1,LayerZooms::Alignment::Min>::RandomArrayUnpacker;

```

### `LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>::RandomArrayUnpacker`
```
typedef std::make_index_sequence<RANDOM_ARRAY_SIZE>_0 LayerZooms::ZoomBase<2,LayerZooms::Alignment::Center>::RandomArrayUnpacker;

```

### `LayerPtr<FilterLayer<LayerFilters::AddIsland>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::Terrain> > LayerPtr<FilterLayer<LayerFilters::AddIsland>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::RemoveTooMuchOcean>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::Terrain> > LayerPtr<FilterLayer<LayerFilters::RemoveTooMuchOcean>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddSnow>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::Terrain> > LayerPtr<FilterLayer<LayerFilters::AddSnow>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddIslandWithTemperature>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::PreBiome> > LayerPtr<FilterLayer<LayerFilters::AddIslandWithTemperature>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddEdgeCoolWarm>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::PreBiome> > LayerPtr<FilterLayer<LayerFilters::AddEdgeCoolWarm>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddEdgeHeatIce>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::PreBiome> > LayerPtr<FilterLayer<LayerFilters::AddEdgeHeatIce>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddEdgeSpecial>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::PreBiome> > LayerPtr<FilterLayer<LayerFilters::AddEdgeSpecial>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::BiomeInit>::InputType>`
```
typedef std::shared_ptr<Layer<LayerValues::PreBiome> > LayerPtr<FilterLayer<LayerFilters::BiomeInit>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddMushroomIsland>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::AddMushroomIsland>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::PromoteCenter>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::PromoteCenter>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::RiverInit>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::RiverInit>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::River>::InputType>`
```
typedef std::shared_ptr<Layer<int> > LayerPtr<FilterLayer<LayerFilters::River>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::Smooth<bool> >::InputType>`
```
typedef std::shared_ptr<Layer<bool> > LayerPtr<FilterLayer<LayerFilters::Smooth<bool> >::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::RareBiomeSpot>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::RareBiomeSpot>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PreHillsEdgeTransformation> > >::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> > >::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddBiomeIsland>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::AddBiomeIsland>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::Shore>::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::Shore>::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::FilteredTransformation<FilteredTransformationAttributes<PostShoreEdgeTransformation> > >::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::Smooth<Biome *> >::InputType>`
```
typedef std::shared_ptr<Layer<Biome *> > LayerPtr<FilterLayer<LayerFilters::Smooth<Biome *> >::InputType>;

```

### `LayerPtr<FilterLayer<LayerFilters::AddOceanEdge>::InputType>`
```
typedef std::shared_ptr<Layer<BiomeTemperatureCategory> > LayerPtr<FilterLayer<LayerFilters::AddOceanEdge>::InputType>;

```

### `LegacyStructureBlockInfo`
```
struct LegacyStructureBlockInfo
{
  BlockPos mPos;
  const Block *mBlock;
  const Block *mExtraBlock;
  Unique<CompoundTag> mTag;
};

```

### `LegacyStructureActorInfo`
```
struct LegacyStructureActorInfo
{
  Vec3 mPos;
  BlockPos mBlockPos;
  CompoundTag mTag;
};

```

### `LootTable`
```
struct LootTable
{
  std::string mDir;
  std::vector<std::unique_ptr<LootPool>> mPools;
};

```

### `LootItemFunction`
```
struct LootItemFunction
{
  int (**_vptr$LootItemFunction)(void);
  std::vector<std::unique_ptr<LootItemCondition>> mPredicates;
};

```

### `LegacyTradeableDefinition`
```
struct __attribute__((aligned(8))) LegacyTradeableDefinition
{
  std::string mDisplayName;
  std::string mTradeTablePath;
  bool mUseNewTradeScreen;
  bool mPersistTrades;
  bool mConvertTradesEconomy;
};

```

### `LeashFenceKnotActor`
```
struct __cppobj LeashFenceKnotActor : HangingActor
{
};

```

### `LeashableDefinition`
```
struct __attribute__((aligned(8))) LeashableDefinition
{
  float mSoftDistance;
  float mHardDistance;
  float mMaxDistance;
  DefinitionTrigger mOnLeash;
  DefinitionTrigger mOnUnleash;
  bool mCanBeStolen;
};

```

### `LookControl`
```
struct __cppobj LookControl : Control
{
};

```

### `LevelDbEnv`
```
struct __cppobj LevelDbEnv : leveldb::Env
{
  std::unique_ptr<TaskGroup> mLevelDBTasks;
};

```

### `leveldb::WritableFile`
```
struct leveldb::WritableFile
{
  int (**_vptr$WritableFile)(void);
};

```

### `leveldb::FileLock`
```
struct leveldb::FileLock
{
  int (**_vptr$FileLock)(void);
};

```

### `LevelDbFileLock`
```
struct __cppobj LevelDbFileLock : leveldb::FileLock
{
};

```

### `LevelDbLogger`
```
struct __cppobj LevelDbLogger : leveldb::Logger
{
};

```

### `LevelDbRandomAccessFile`
```
struct __cppobj LevelDbRandomAccessFile : leveldb::RandomAccessFile
{
  Core::File mFile;
  Bedrock::Threading::Mutex mMutex;
};

```

### `LevelDbSequentialFile`
```
struct __cppobj LevelDbSequentialFile : leveldb::SequentialFile
{
  Core::File mFile;
};

```

### `LevelDbWritableFile`
```
struct __cppobj LevelDbWritableFile : leveldb::WritableFile
{
  Core::File mFile;
  std::string mFilenameHackForManifestSync;
};

```

### `Localization`
```
struct Localization
{
  bool mCommaSeperator;
  const std::string mCode;
  Localization::Map mStrings;
};

```

### `Localization::Map`
```
typedef std::map<std::string,std::string> Localization::Map;

```

### `Localization::StoreLocMap`
```
typedef std::unordered_multimap<std::string,std::pair<std::string,std::string >> Localization::StoreLocMap;

```

### `LocalConnector`
```
struct __cppobj LocalConnector : Connector
{
  LocalConnector::ConnectionCallbacks *mCallbacks;
  NetworkIdentifier mLocalId;
  std::vector<LocalConnector::LocalConnection> mConnections;
  std::vector<std::function<void ()>> mCallbackQueue;
};

```

### `LoginPacket`
```
struct __cppobj LoginPacket : Packet:288
{
  int mClientNetworkVersion;
  Unique<ConnectionRequest> mConnectionRequest;
};

```

### `LevelSoundEventPacketV2`
```
struct __cppobj __attribute__((aligned(8))) LevelSoundEventPacketV2 : Packet:288
{
  LevelSoundEvent mEventId;
  Vec3 mPos;
  int mData;
  std::string mEntityIdentifier;
  bool mIsBabyMob;
  bool mIsGlobal;
};

```

### `LevelSoundEventPacketV1`
```
struct __cppobj __attribute__((aligned(4))) LevelSoundEventPacketV1 : Packet:288
{
  LevelSoundEvent mEventId;
  Vec3 mPos;
  int mData;
  ActorType mEntityType;
  bool mIsBabyMob;
  bool mIsGlobal;
};

```

### `LecternBlockActor`
```
struct __cppobj LecternBlockActor : BlockActor, Container:1952
{
  int mPage;
  int mTotalPages;
  ItemStack mBook;
};

```

### `LevelChunkPacket::SubChunkMetadata`
```
struct LevelChunkPacket::SubChunkMetadata
{
  uint64_t blobId;
};

```

### `LoadedResourceData`
```
struct LoadedResourceData
{
  int mIndex;
  std::string mContent;
};

```

### `LoopingSoundState`
```
struct LoopingSoundState
{
  glm::vec3 position;
  float pitch;
  float volume;
};

```

### `LoopbackPacketSender`
```
struct __cppobj LoopbackPacketSender : PacketSender
{
  NetworkHandler *mNetwork;
  std::vector<NetEventCallback *> mLoopbackCallbacks;
  const std::vector<std::unique_ptr<Player>> *mUserList;
  std::vector<NetworkIdentifierWithSubId> mTempUserIds;
};

```

### `Lockless::WeakAtomic<SPSCQueue<std::function<void ()>,512>::Block *>`
```
struct Lockless::WeakAtomic<SPSCQueue<std::function<void ()>,512>::Block *>
{
  std::atomic<SPSCQueue<std::function<void ()>,512>::Block *> mValue;
};

```

### `ListenerList`
```
typedef std::vector<LevelListener *> ListenerList;

```

### `LevelDataWrapper`
```
struct LevelDataWrapper
{
  LevelData *mLevelDataFromLevel;
  LevelData mLevelDataFromDisk;
};

```

### `Level::RegionSet`
```
typedef std::unordered_set<BlockSource *> Level::RegionSet;

```

### `Level::BossEventListenerList`
```
typedef std::vector<BossEventListener *> Level::BossEventListenerList;

```

### `Level::ChangeDimensionRequestMap`
```
typedef std::unordered_map<Player *,std::unique_ptr<ChangeDimensionRequest>> Level::ChangeDimensionRequestMap;

```

### `LevelEventCoordinator`
```
struct __cppobj LevelEventCoordinator : EventCoordinator<LevelEventListener>
{
};

```

### `LootTables`
```
struct LootTables
{
  LootTableMap mLootTables;
  Bedrock::Threading::Mutex mLootTableMutex;
};

```

### `LootTableMap`
```
typedef std::unordered_map<std::string,std::unique_ptr<LootTable>> LootTableMap;

```

### `LootTableDescription`
```
struct __cppobj LootTableDescription : PropertyDescription
{
  std::string mFilePath;
};

```

### `LabTableContainerManagerModel`
```
struct __cppobj LabTableContainerManagerModel : LevelContainerManagerModel:1312
{
  BlockPos mBlockPos;
};

```

### `leveldb::Compressor`
```
struct __attribute__((aligned(8))) leveldb::Compressor
{
  int (**_vptr$Compressor)(void);
  uint64_t inputBytes;
  uint64_t compressedBytes;
  const char uniqueCompressionID;
};

```

### `LootPool`
```
struct LootPool
{
  std::vector<std::unique_ptr<LootPoolEntry>> mEntries;
  std::vector<std::unique_ptr<LootItemCondition>> mConditions;
  Unique<LootPoolTiers> mTiers;
  RandomValueBounds mRolls;
  RandomValueBounds mBonusRolls;
};

```

### `LootPoolEntry`
```
struct LootPoolEntry
{
  int (**_vptr$LootPoolEntry)(void);
  int mWeight;
  int mQuality;
  std::vector<std::unique_ptr<LootItemCondition>> mConditions;
  Unique<LootPoolEntry> mSubTable;
};

```

### `LootItemCondition`
```
struct LootItemCondition
{
  int (**_vptr$LootItemCondition)(void);
};

```

### `LootPoolTiers`
```
struct LootPoolTiers
{
  int mRangeForInitialTier;
  int mBonusRolls;
  float mBonusRollChance;
};

```

### `Llama`
```
struct __cppobj Llama : Animal
{
};

```

### `LavaSlime`
```
struct __cppobj LavaSlime : Slime
{
};

```

### `LargeFireball`
```
struct __cppobj LargeFireball : Fireball:17696
{
  int mExplosionPower;
};

```

### `LightningBolt`
```
struct __cppobj __attribute__((aligned(4))) LightningBolt : Actor
{
  RandomSeed_0 mSeed;
  int mLife;
  int mFlashes;
  bool mCanHurt;
  bool mHasTriedToHurt;
};

```

### `LlamaSpit`
```
struct __cppobj LlamaSpit : Actor
{
  ActorUniqueID ownerId;
  MovementInterpolator mInterpolation;
};

```

### `LayEggGoal`
```
struct __cppobj LayEggGoal : BaseMoveToBlockGoal
{
  int mLayEggCounter;
  const DefinitionTrigger mOnLay;
};

```

### `LookAtActorGoal`
```
struct __cppobj LookAtActorGoal : Goal
{
  TempEPtr<Actor> mLookAt;
  float mLookDistance;
  int mAngleOfViewX;
  int mAngleOfViewY;
  int mLookTime;
  int mMinLookTime;
  int mMaxLookTime;
  float mProbability;
  ActorFilterGroup mTargetFilter;
  Mob *mMob;
};

```

### `LayDownGoal`
```
struct __cppobj LayDownGoal : Goal
{
  Mob *mMob;
  int mInterval;
  int mEndInterval;
};

```

### `LeapAtTargetGoal`
```
struct __cppobj LeapAtTargetGoal : Goal
{
  TempEPtr<Actor> mTarget;
  float mYd;
  bool mMustBeOnGround;
  Mob *mMob;
};

```

### `LookAtTradingPlayerGoal`
```
struct __cppobj LookAtTradingPlayerGoal : LookAtActorGoal
{
  Mob *mMob;
};

```

### `LegacyBodyControl`
```
struct __cppobj LegacyBodyControl : BodyControl
{
};

```

### `LevelContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) LevelContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  ActorUniqueID mEntityUniqueID;
  BlockActorType mBlockActorType;
};

```

### `LevelContainerModel`
```
struct __cppobj LevelContainerModel : ContainerModel
{
  Player *mPlayer;
  bool mPlayerClientSide;
  BlockPos mBlockPos;
  BlockActorType mBlockEntityType;
  ActorUniqueID mEntityUniqueId;
};

```

### `LevelContainerManagerModel:1312`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(4))) LevelContainerManagerModel:1312 : ContainerManagerModel
{
  BlockPos mBlockPos;
  _BYTE gap94[4];
  ActorUniqueID mEntityUniqueID;
  BlockActorType mBlockActorType;
};

```

### `ListenerInfo`
```
struct ListenerInfo
{
  std::function<void (const Block &)> mCallback;
  Vec3 mPosition;
  float mRadiusSqr;
};

```

### `LeadItem`
```
struct __cppobj LeadItem : Item
{
};

```

### `LingeringPotionItem`
```
struct __cppobj __attribute__((aligned(8))) LingeringPotionItem : PotionItem
{
  TextureUVCoordinateSet mLingeringIcons[17];
  Potion::PotionVariant mLingeringPotionVariants[17];
};

```

### `LeafBlockItem`
```
struct __cppobj LeafBlockItem : BlockItem
{
  const Block *m_parentBlock;
};

```

### `LootEnchant`
```
struct __cppobj LootEnchant : Enchant
{
};

```

### `LegacyPreHillsEdgeAttributes`
```
typedef FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation> LegacyPreHillsEdgeAttributes;

```

### `ListedFeaturesDecorationAttributes`
```
typedef BiomeDecorationAttributes<ListedFeatures> ListedFeaturesDecorationAttributes;

```

### `LootComponent`
```
struct LootComponent
{
  BlockLegacy *mBlockLegacy;
  std::string mLootTable;
};

```

### `LootComponentDescription`
```
struct __cppobj LootComponentDescription : BlockComponentDescription
{
  std::string mLootTable;
};

```

### `LevelSoundEventMap`
```
struct LevelSoundEventMap
{
  __int8 gap0[1];
};

```

### `LiquidBlock`
```
struct __cppobj LiquidBlock : BlockLegacy
{
};

```

### `LabTableReaction`
```
struct __attribute__((aligned(8))) LabTableReaction
{
  int (**_vptr$LabTableReaction)(void);
  int mLifetime;
  int mMaxLifetime;
  int mStartDelay;
  std::unique_ptr<ItemStack> mResultItem;
  std::unique_ptr<BlockPos> mPos;
  std::unique_ptr<Random> mRandom;
  std::vector<std::unique_ptr<LabTableReactionComponent>> mComponents;
  LabTableReactionType mType;
  bool mIsClientSide;
};

```

### `LabTableReactionComponent`
```
struct LabTableReactionComponent
{
  int (**_vptr$LabTableReactionComponent)(void);
};

```

### `LecternBlock`
```
struct __cppobj LecternBlock : ActorBlock
{
};

```

### `LiquidBlockDynamic`
```
struct __cppobj LiquidBlockDynamic : LiquidBlock
{
};

```

### `LiquidBlockStatic`
```
struct __cppobj LiquidBlockStatic : LiquidBlock
{
};

```

### `LadderBlock`
```
struct __cppobj LadderBlock : BlockLegacy
{
};

```

### `LeverBlock`
```
struct __cppobj LeverBlock : BlockLegacy
{
};

```

### `LightGemBlock`
```
struct __cppobj LightGemBlock : BlockLegacy
{
};

```

### `LoomBlock`
```
struct __cppobj LoomBlock : FaceDirectionalBlock
{
};

```

### `LanternBlock`
```
struct __cppobj LanternBlock : BlockLegacy
{
};

```

### `LightBlock`
```
struct __cppobj LightBlock : AirBlock
{
};

```

### `LevelChunkFinalDeleter`
```
struct LevelChunkFinalDeleter
{
  __int8 gap0[1];
};

```

### `LevelChunkGridAreaWeakPointer`
```
typedef LevelChunkGridAreaElement<std::weak_ptr<LevelChunk> > LevelChunkGridAreaWeakPointer;

```

### `LevelDataWrapper_0`
```
struct LevelDataWrapper_0
{
  LevelData_0 *mLevelDataFromLevel;
  LevelData_0 mLevelDataFromDisk;
};

```

### `LevelStorage::Batch`
```
struct LevelStorage::Batch
{
  int (**_vptr$Batch)(void);
};

```

### `LootingEnchantFunction`
```
struct __cppobj LootingEnchantFunction : LootItemFunction
{
  RandomValueBounds mValue;
};

```

### `LinuxStackTrace`
```
struct LinuxStackTrace
{
  __int8 gap0[1];
};

```

### `Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *>`
```
struct Lockless::WeakAtomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *>
{
  std::atomic<SPSCQueue<BatchedNetworkPeer::DataCallback,512>::Block *> mValue;
};

```

### `LocalConnector::LocalConnection`
```
struct LocalConnector::LocalConnection
{
  LocalConnector *mConnector;
  NetworkIdentifier mId;
};

```

### `LocalNetworkPeer`
```
struct __cppobj LocalNetworkPeer : NetworkPeer
{
  std::weak_ptr<LocalNetworkPeer> mOtherPeer;
  std::unique_ptr<SPSCQueue<std::string,512>> mIncomingData;
};

```

### `ListCommand`
```
struct __cppobj ListCommand : ServerCommand
{
};

```

### `ListDCommand`
```
struct __cppobj __attribute__((aligned(8))) ListDCommand : ServerCommand
{
  ListDCommand::DetailMode mDetails;
};

```

### `LocateCommand`
```
struct __cppobj __attribute__((aligned(2))) LocateCommand : Command:240
{
  StructureFeatureType mFeature;
};

```

### `LookAtBlockDefinition`
```
struct __cppobj LookAtBlockDefinition : BehaviorDefinition
{
  BlockPos mBlockPos;
  std::string mBlockPosId;
};

```

### `LookAtBlockNode`
```
struct __cppobj LookAtBlockNode : BehaviorNode:480
{
  BlockPos mBlockPos;
  int mDelayTicks;
  int mDelayCounter;
};

```

### `LookAtActorDefinition`
```
struct __cppobj LookAtActorDefinition : BehaviorDefinition
{
  std::string mEntityName;
  std::string mEntityType;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `LookAtActorNode`
```
struct __cppobj __attribute__((aligned(8))) LookAtActorNode : BehaviorNode:480
{
  int mDelayTicks;
  int mDelayCounter;
  ActorType mEntityType;
  int mSearchRadius;
};

```

### `LabTableInputContainerController`
```
struct __cppobj LabTableInputContainerController : ContainerController
{
};

```

### `LoomBannerContainerController`
```
struct __cppobj LoomBannerContainerController : ContainerController
{
};

```

### `LoomDyeContainerController`
```
struct __cppobj LoomDyeContainerController : ContainerController
{
};

```

### `LoomMaterialContainerController`
```
struct __cppobj LoomMaterialContainerController : ContainerController
{
};

```

### `LeafBlock`
```
struct __cppobj LeafBlock : BlockLegacy
{
  bool mHasTransparentLeaves;
  bool mHasFastAlphaTest;
  WeakPtr<BlockLegacy> mSapling;
};

```

### `LogBlock`
```
struct __cppobj LogBlock : RotatedPillarBlock
{
};

```

### `leveldb::Cache`
```
struct leveldb::Cache
{
  int (**_vptr$Cache)(void);
  leveldb::Cache::Rep *rep_;
};

```

### `leveldb::DecompressAllocator`
```
struct leveldb::DecompressAllocator
{
  int (**_vptr$DecompressAllocator)(void);
  std::mutex mutex;
  std::vector<std::string> stack;
};

```

### `LevelStorageObserver`
```
struct LevelStorageObserver
{
  std::function<void (const std::string &)> mOnSaveCallback;
};

```

### `leveldb::Iterator`
```
struct leveldb::Iterator
{
  int (**_vptr$Iterator)(void);
  leveldb::Iterator::Cleanup cleanup_;
};

```

### `leveldb::ZlibCompressorRaw`
```
struct __cppobj leveldb::ZlibCompressorRaw : leveldb::ZlibCompressorBase
{
};

```

### `LegacyChunkStorage`
```
struct __cppobj LegacyChunkStorage : ChunkSource
{
  bool mDone;
  const PerlinSimplexNoise mGrassNoise;
  const Core::HeapPathBuffer mLevelPath;
  const Core::HeapPathBuffer mImportedChunksPath;
  Unique<RegionFile> mRegionFile;
  Unique<RegionFile> mEntitiesFile;
  StorageVersion mLoadedStorageVersion;
  Biome *mDefaultBiome;
  std::unordered_map<ChunkPos,std::string> mChunkEntities;
  std::unordered_map<ChunkPos,std::string> mChunkBlockEntities;
  Bedrock::Threading::Mutex mRegionFileMutex;
  Bedrock::Threading::Mutex mChunkMapMutex;
};

```

### `leveldb::EnvWrapper`
```
struct __cppobj leveldb::EnvWrapper : leveldb::Env
{
  leveldb::Env *target_;
};

```

### `leveldb::RandomAccessFileEncrypted`
```
struct __cppobj leveldb::RandomAccessFileEncrypted : leveldb::RandomAccessFile
{
  std::string _fname;
  std::string _plainText;
};

```

### `leveldb::WritableFileEncrypted`
```
struct __cppobj leveldb::WritableFileEncrypted : leveldb::WritableFile
{
  leveldb::WritableFile *_writableFile;
  std::shared_ptr<Crypto::Symmetric::Symmetric> _encryption;
  std::unique_ptr<Crypto::encryptedFileHeader> _header;
};

```

### `LootTableEntry`
```
struct __cppobj LootTableEntry : LootPoolEntry
{
  Unique<LootTable> mTable;
};

```

### `LootTableReference`
```
struct __cppobj LootTableReference : LootPoolEntry
{
  std::string mDir;
};

```

### `LootItemConditions`
```
struct LootItemConditions
{
  __int8 gap0[1];
};

```

### `LootItem`
```
struct __cppobj LootItem : LootPoolEntry
{
  const Item *mItem;
  std::vector<std::unique_ptr<LootItemFunction>> mFunctions;
};

```

### `LootItemFunctions`
```
struct LootItemFunctions
{
  __int8 gap0[1];
};

```

### `LootItemKilledByActorCondition`
```
struct __cppobj LootItemKilledByActorCondition : LootItemCondition
{
  ActorDefinitionIdentifier mActorId;
};

```

### `LootItemKilledByPlayerCondition`
```
struct __cppobj LootItemKilledByPlayerCondition : LootItemCondition
{
};

```

### `LootItemKilledByPlayerOrPetsCondition`
```
struct __cppobj LootItemKilledByPlayerOrPetsCondition : LootItemCondition
{
};

```

### `LootItemRandomChanceCondition`
```
struct __cppobj __attribute__((aligned(8))) LootItemRandomChanceCondition : LootItemCondition
{
  float mChance;
};

```

### `LootItemRandomChanceWithLootingCondition`
```
struct __cppobj LootItemRandomChanceWithLootingCondition : LootItemCondition
{
  float mChance;
  float mLootingMultiplier;
};

```

### `LootItemRandomChanceWithSpecialModifierCondition`
```
struct __cppobj __attribute__((aligned(8))) LootItemRandomChanceWithSpecialModifierCondition : LootItemCondition
{
  float mChance;
};

```

### `LootItemRandomDifficultyChanceCondition`
```
struct __cppobj LootItemRandomDifficultyChanceCondition : LootItemCondition
{
  std::vector<float> mChances;
};

```

### `LootItemActorHasMarkVariantCondition`
```
struct __cppobj __attribute__((aligned(8))) LootItemActorHasMarkVariantCondition : LootItemCondition
{
  int mValue;
};

```

### `leveldb::MemTable`
```
struct leveldb::MemTable
{
  leveldb::MemTable::KeyComparator comparator_;
  int refs_;
  leveldb::Arena arena_;
  leveldb::MemTable::Table table_;
};

```

### `leveldb::Arena`
```
struct leveldb::Arena
{
  char *alloc_ptr_;
  size_t alloc_bytes_remaining_;
  std::vector<char *> blocks_;
  leveldb::port::AtomicPointer memory_usage_;
};

```

### `leveldb::MemTable::Table`
```
typedef leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator> leveldb::MemTable::Table;

```

### `leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>`
```
struct __attribute__((aligned(8))) leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>
{
  const leveldb::MemTable::KeyComparator compare_;
  leveldb::Arena *const arena_;
  leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Node *const head_;
  leveldb::port::AtomicPointer max_height_;
  leveldb::Random rnd_;
};

```

### `leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Node`
```
struct leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Node
{
  const char *const key;
  leveldb::port::AtomicPointer next_[1];
};

```

### `leveldb::Random`
```
struct leveldb::Random
{
  uint32_t seed_;
};

```

### `leveldb::DBImpl::CompactionState`
```
struct leveldb::DBImpl::CompactionState
{
  leveldb::Compaction *const compaction;
  leveldb::SequenceNumber smallest_snapshot;
  std::vector<leveldb::DBImpl::CompactionState::Output> outputs;
  leveldb::WritableFile *outfile;
  leveldb::TableBuilder *builder;
  uint64_t total_bytes;
};

```

### `leveldb::Compaction`
```
struct leveldb::Compaction
{
  int level_;
  uint64_t max_output_file_size_;
  leveldb::Version *input_version_;
  leveldb::VersionEdit edit_;
  std::vector<leveldb::FileMetaData *> inputs_[2];
  std::vector<leveldb::FileMetaData *> grandparents_;
  size_t grandparent_index_;
  bool seen_key_;
  int64_t overlapped_bytes_;
  size_t level_ptrs_[7];
};

```

### `leveldb::TableBuilder::Rep`
```
struct leveldb::TableBuilder::Rep
{
  leveldb::Options options;
  leveldb::Options index_block_options;
  leveldb::WritableFile *file;
  uint64_t offset;
  leveldb::Status status;
  leveldb::BlockBuilder data_block;
  leveldb::BlockBuilder index_block;
  std::string last_key;
  int64_t num_entries;
  bool closed;
  leveldb::FilterBlockBuilder *filter_block;
  bool pending_index_entry;
  leveldb::BlockHandle pending_handle;
  std::string compressed_output;
};

```

### `leveldb::Range`
```
struct leveldb::Range
{
  leveldb::Slice start;
  leveldb::Slice limit;
};

```

### `leveldb::`anonymous namespace'::IterState`
```
struct leveldb::`anonymous namespace'::IterState
{
  leveldb::port::Mutex *mu;
  leveldb::Version *version;
  leveldb::MemTable *mem;
  leveldb::MemTable *imm;
};

```

### `leveldb::WriteBatchInternal`
```
struct leveldb::WriteBatchInternal
{
  __int8 gap0[1];
};

```

### `leveldb::`anonymous namespace'::DBIter`
```
struct __cppobj leveldb::`anonymous namespace'::DBIter : leveldb::Iterator
{
  leveldb::DBImpl *db_;
  const leveldb::Comparator *const user_comparator_;
  leveldb::Iterator *const iter_;
  const leveldb::SequenceNumber sequence_;
  leveldb::Status status_;
  std::string saved_key_;
  std::string saved_value_;
  leveldb::`anonymous namespace'::DBIter::Direction direction_;
  bool valid_;
  leveldb::Random rnd_;
  ssize_t bytes_counter_;
};

```

### `leveldb::Iterator::Cleanup`
```
struct leveldb::Iterator::Cleanup
{
  leveldb::Iterator::CleanupFunction function;
  void *arg1;
  void *arg2;
  leveldb::Iterator::Cleanup *next;
};

```

### `leveldb::MemTableIterator`
```
struct __cppobj leveldb::MemTableIterator : leveldb::Iterator
{
  leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::Iterator iter_;
  std::string tmp_;
};

```

### `leveldb::TableAndFile`
```
struct leveldb::TableAndFile
{
  leveldb::RandomAccessFile *file;
  leveldb::Table *table;
};

```

### `leveldb::Table::Rep`
```
struct leveldb::Table::Rep
{
  leveldb::Options options;
  leveldb::Status status;
  leveldb::RandomAccessFile *file;
  uint64_t cache_id;
  leveldb::FilterBlockReader *filter;
  const char *filter_data;
  leveldb::BlockHandle metaindex_handle;
  leveldb::Block *index_block;
};

```

### `leveldb::Version::LevelFileNumIterator`
```
struct __cppobj __attribute__((aligned(8))) leveldb::Version::LevelFileNumIterator : leveldb::Iterator
{
  const leveldb::InternalKeyComparator icmp_;
  const std::vector<leveldb::FileMetaData *> *const flist_;
  uint32_t index_;
  char value_buf_[16];
};

```

### `leveldb::VersionSet::Builder::FileSet`
```
typedef std::set<leveldb::FileMetaData *,leveldb::VersionSet::Builder::BySmallestKey,std::allocator<leveldb::FileMetaData *> > leveldb::VersionSet::Builder::FileSet;

```

### `leveldb::`anonymous namespace'::EmptyIterator`
```
struct __cppobj leveldb::`anonymous namespace'::EmptyIterator : leveldb::Iterator
{
  leveldb::Status status_;
};

```

### `leveldb::`anonymous namespace'::MergingIterator`
```
struct __cppobj __attribute__((aligned(8))) leveldb::`anonymous namespace'::MergingIterator : leveldb::Iterator
{
  const leveldb::Comparator *comparator_;
  leveldb::IteratorWrapper *children_;
  int n_;
  leveldb::IteratorWrapper *current_;
  leveldb::`anonymous namespace'::MergingIterator::Direction direction_;
};

```

### `leveldb::FilterBlockReader`
```
struct leveldb::FilterBlockReader
{
  const leveldb::FilterPolicy *policy_;
  const char *data_;
  const char *offset_;
  size_t num_;
  size_t base_lg_;
};

```

### `leveldb::Block`
```
struct __attribute__((aligned(4))) leveldb::Block
{
  const char *data_;
  size_t size_;
  uint32_t restart_offset_;
  bool owned_;
};

```

### `leveldb::FilterBlockBuilder`
```
struct leveldb::FilterBlockBuilder
{
  const leveldb::FilterPolicy *policy_;
  std::string keys_;
  std::vector<unsigned long> start_;
  std::string result_;
  std::vector<leveldb::Slice> tmp_keys_;
  std::vector<unsigned int> filter_offsets_;
};

```

### `leveldb::`anonymous namespace'::TwoLevelIterator`
```
struct __cppobj leveldb::`anonymous namespace'::TwoLevelIterator : leveldb::Iterator
{
  leveldb::`anonymous namespace'::BlockFunction block_function_;
  void *arg_;
  const leveldb::ReadOptions options_;
  leveldb::Status status_;
  leveldb::IteratorWrapper index_iter_;
  leveldb::IteratorWrapper data_iter_;
  std::string data_block_handle_;
};

```

### `leveldb::`anonymous namespace'::BloomFilterPolicy`
```
struct __cppobj leveldb::`anonymous namespace'::BloomFilterPolicy : leveldb::FilterPolicy
{
  size_t bits_per_key_;
  size_t k_;
};

```

### `leveldb::`anonymous namespace'::LRUHandle`
```
struct __attribute__((aligned(4))) leveldb::`anonymous namespace'::LRUHandle
{
  void *value;
  void (*deleter)(const leveldb::Slice *, void *);
  leveldb::`anonymous namespace'::LRUHandle *next_hash;
  leveldb::`anonymous namespace'::LRUHandle *next;
  leveldb::`anonymous namespace'::LRUHandle *prev;
  size_t charge;
  size_t key_length;
  bool in_cache;
  uint32_t refs;
  uint32_t hash;
  char key_data[1];
};

```

### `leveldb::`anonymous namespace'::ShardedLRUCache`
```
struct __cppobj leveldb::`anonymous namespace'::ShardedLRUCache : leveldb::Cache
{
  leveldb::`anonymous namespace'::LRUCache shard_[16];
  leveldb::port::Mutex id_mutex_;
  uint64_t last_id_;
};

```

### `leveldb::`anonymous namespace'::LRUCache`
```
struct leveldb::`anonymous namespace'::LRUCache
{
  size_t capacity_;
  leveldb::port::Mutex mutex_;
  size_t usage_;
  leveldb::`anonymous namespace'::LRUHandle lru_;
  leveldb::`anonymous namespace'::LRUHandle in_use_;
  leveldb::`anonymous namespace'::HandleTable table_;
};

```

### `leveldb::`anonymous namespace'::HandleTable`
```
struct leveldb::`anonymous namespace'::HandleTable
{
  uint32_t length_;
  uint32_t elems_;
  leveldb::`anonymous namespace'::LRUHandle **list_;
};

```

### `leveldb::`anonymous namespace'::BytewiseComparatorImpl`
```
struct __cppobj leveldb::`anonymous namespace'::BytewiseComparatorImpl : leveldb::Comparator
{
};

```

### `leveldb::Block::Iter`
```
struct __cppobj leveldb::Block::Iter : leveldb::Iterator
{
  const leveldb::Comparator *const comparator_;
  const char *const data_;
  const uint32_t restarts_;
  const uint32_t num_restarts_;
  uint32_t current_;
  uint32_t restart_index_;
  std::string key_;
  leveldb::Slice value_;
  leveldb::Status status_;
};

```

### `linkedlist_data_s`
```
struct linkedlist_data_s
{
  linkedlist_datablock_internal *first_block;
  linkedlist_datablock_internal *last_block;
};

```

### `linkedlist_datablock_internal`
```
typedef linkedlist_datablock_internal_s linkedlist_datablock_internal;

```

### `linkedlist_datablock_internal_s`
```
struct linkedlist_datablock_internal_s
{
  linkedlist_datablock_internal_s *next_datablock;
  uLong avail_in_this_block;
  uLong filled_in_this_block;
  uLong unused;
  unsigned __int8 data[4080];
};

```

