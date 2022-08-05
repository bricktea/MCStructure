# O
### `OverworldGenerator::_makeLayers::$2867EA52F754A99BBF15CBCDF29DF3E2`
Offset | Type | Name
-|-|-|-
0 | (8) `const BiomeRegistry *` | biomeRegistry


### `OwnedActorSet`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<Actor>>` | c


### `OwnerStorageEntity::EntityContextOwned`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0


### `OpenDoorAnnotationComponent`
Offset | Type | Name
-|-|-|-
0 | (80) `std::queue<BlockPos>` | mPassedDoorPositions


### `OptionalString`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | valid
8 | (32) `std::string` | string


### `Option::StringFilter`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::string (const std::string &)>::_Invoker_type` | _M_invoker


### `Option::BoolFilter`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (bool)>::_Invoker_type` | _M_invoker


### `Option::SaveIntCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<int (int)>::_Invoker_type` | _M_invoker


### `OnScreenTextureAnimationPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `unsigned int` | mEffectID


### `OwnerPtr<EntityId>`
Offset | Type | Name
-|-|-|-
0 | (24) `EntityRefTraits::OwnerStorage` | baseclass_0


### `OverworldHeightAttributes`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeHeight` | mHeightParams


### `OceanMixerLayer::OceanData`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<char []>` | mResult


### `optional_ref<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `int *` | ptr


### `OverworldDimension`
Offset | Type | Name
-|-|-|-
0 | (1216) `Dimension` | baseclass_0


### `OceanRuinConfiguration`
Offset | Type | Name
-|-|-|-
0 | (4) `OceanTempCategory` | type
4 | (4) `float` | largeProbability
8 | (4) `float` | clusterProbability


### `OwnerPtr<PerlinSimplexNoise>`
Offset | Type | Name
-|-|-|-
0 | (16) `SharePtrRefTraits<PerlinSimplexNoise>::OwnerStorage` | baseclass_0


### `optional_ref<const Localization>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Localization *` | ptr


### `Ocelot::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `OwnerPtrT<FeatureRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `FeatureRefTraits::OwnerStorage` | baseclass_0


### `ObjectiveCriteria`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | mName
32 | (1) `const bool` | mReadOnly
33 | (1) `const ObjectiveRenderType_0` | mRenderType


### `OpenDoorAnnotationSystem`
```
struct __cppobj OpenDoorAnnotationSystem : ITickingSystem
{
};

```

### `OwnerStorageSharePtr<EntityRegistryOwned>`
```
struct OwnerStorageSharePtr<EntityRegistryOwned>
{
  std::shared_ptr<EntityRegistryOwned> mValue;
};

```

### `OwnerPtrT<EntityRegistryRefTraits>`
```
struct __cppobj OwnerPtrT<EntityRegistryRefTraits> : EntityRegistryRefTraits::OwnerStorage
{
};

```

### `OwnerPtrT<EntityRegistryRefTraits>::OwnerStackRef`
```
typedef EntityRegistryRefTraits::OwnerStackRef OwnerPtrT<EntityRegistryRefTraits>::OwnerStackRef;

```

### `OwnerStorageEntity`
```
struct OwnerStorageEntity
{
  std::optional<OwnerStorageEntity::EntityContextOwned> mContext;
};

```

### `OwnerPtrT<EntityRefTraits>`
```
struct __cppobj OwnerPtrT<EntityRefTraits> : EntityRefTraits::OwnerStorage
{
};

```

### `OwnerPtrT<EntityRefTraits>::OwnerStackRef`
```
typedef EntityRefTraits::OwnerStackRef OwnerPtrT<EntityRefTraits>::OwnerStackRef;

```

### `OwnerStorageFeature`
```
struct OwnerStorageFeature
{
  std::optional<std::reference_wrapper<FeatureRegistry> > mRegistry;
  size_t mIndex;
};

```

### `OreFeature`
```
struct __cppobj OreFeature : IFeature
{
  int mCount;
  float mCountf;
  float mCountfInv;
  const Block *mBlock;
  std::vector<const Block *> mMayReplace;
};

```

### `OakFeature`
```
struct __cppobj __attribute__((aligned(8))) OakFeature : TreeFeature
{
};

```

### `OwnerPtrT<FeatureRefTraits>::OwnerStackRef`
```
typedef FeatureRefTraits::OwnerStackRef OwnerPtrT<FeatureRefTraits>::OwnerStackRef;

```

### `OverworldGenerator`
```
struct __cppobj OverworldGenerator : ChunkSource, WorldGenerator
{
  const bool legacyDevice;
  BeardKernel mBeardKernel;
  PerlinNoisePtr minLimitPerlinNoise;
  PerlinNoisePtr maxLimitPerlinNoise;
  PerlinNoisePtr mainPerlinNoise;
  Unique<PerlinSimplexNoise> surfaceNoise;
  PerlinNoisePtr scaleNoise;
  PerlinNoisePtr depthNoise;
  PerlinNoisePtr forestNoise;
  float biomeWeights[25];
  ThreadLocal<OverworldGenerator::ThreadData> generatorHelpersPool;
  VillageFeature villageFeature;
  StrongholdFeature strongholdFeature;
  RandomScatteredLargeFeature scatteredFeature;
  MineshaftFeature mineshaftFeature;
  MonsterRoomFeature monsterRoomFeature;
  OceanMonumentFeature oceanMonumentFeature;
  OceanRuinFeature oceanRuinFeature;
  WoodlandMansionFeature woodlandMansionFeature;
  ShipwreckFeature shipwreckFeature;
  BuriedTreasureFeature buriedChestFeature;
  LargeCaveFeature caveFeature;
  CanyonFeature canyonFeature;
  UnderwaterLargeCaveFeature underwaterCaveFeature;
  UnderwaterCanyonFeature underwaterCanyonFeature;
  PillagerOutpostFeature pillagerOutpostFeature;
  ConstLayerPtr<Biome *> mBlockResolutionLayer;
  ConstLayerPtr<Biome *> m4x4ResolutionLayer;
  std::shared_ptr<BiomeSourceGetBiomeCache> mBiomeSourceCache;
};

```

### `OverworldGenerator::ThreadData`
```
struct __attribute__((aligned(8))) OverworldGenerator::ThreadData
{
  float buffer[1024];
  float depthBuffer[256];
  float dataBuffer[256];
  std::array<long,32768> blockBuffer;
  float *fi;
  float *fis;
  Random random;
};

```

### `OceanMixerLayer`
```
struct __cppobj OceanMixerLayer : MixerLayer<Biome *,Biome *,BiomeTemperatureCategory>
{
  Biome *mGenericShallowOcean;
  Biome *mGenericDeepOcean;
  std::vector<std::pair<Biome *,unsigned int>> mShallowOceanBiomes[5];
  std::vector<std::pair<Biome *,unsigned int>> mDeepOceanBiomes[5];
};

```

### `OceanMonumentFeature`
```
struct __cppobj OceanMonumentFeature : StructureFeature:1760
{
  int mMonumentSpacing;
  int mMinMonumentSeparation;
  std::vector<int> allowedBiomes;
  std::vector<int> allowedSpawnBiomes;
};

```

### `OceanRuinFeature`
```
struct __cppobj OceanRuinFeature : StructureFeature:1760
{
  int mRuinSpacing;
  int mMinRuinSeparation;
  std::vector<int> allowedBiomes;
  OverworldGenerator *mLevelSource;
  OceanMonumentFeature *mMonument;
};

```

### `OceanRuinStart`
```
struct __cppobj __attribute__((aligned(8))) OceanRuinStart : StructureStart
{
  OceanRuinConfiguration mConfig;
};

```

### `OceanRuinPieces::OceanRuinPiece`
```
struct __cppobj OceanRuinPieces::OceanRuinPiece : TemplateStructurePiece
{
  StructureManager *mStructureManager;
  std::string mTemplateName;
  OceanTempCategory mBiomeType;
  float mIntegrity;
  bool mIsLarge;
  Rotation_0 mRotation;
  BlockPos mPosition;
};

```

### `OceanRuinPieces`
```
struct OceanRuinPieces
{
  __int8 gap0[1];
};

```

### `Option`
```
struct Option
{
  int (**_vptr$Option)(void);
  std::unique_ptr<OptionLock> mLock;
  std::vector<OptionObserver> mObservers;
  std::string mSaveTag;
  std::string mTelemetryProperty;
  const OptionID mID;
  const OptionOwnerType mOwnerType;
  OptionType mOptionType;
  const std::string mCaptionId;
  const OptionResetFlags mOptionResetFlags;
  Option *mOverrideSource;
  std::function<void (bool)> mRequestSaveCallback;
};

```

### `OnFriendlyAngerDescription`
```
struct __cppobj OnFriendlyAngerDescription : TriggerDescription
{
};

```

### `OnHitSubcomponent`
```
struct OnHitSubcomponent
{
  int (**_vptr$OnHitSubcomponent)(void);
};

```

### `OwnerPtr<EntityRegistry>`
```
typedef OwnerPtrT<EntityRegistryRefTraits> OwnerPtr<EntityRegistry>;

```

### `Objective`
```
struct Objective
{
  std::unordered_map<ScoreboardId,int> mScores;
  const std::string mName;
  std::string mDisplayName;
  const ObjectiveCriteria *mCriteria;
};

```

### `OptionObserver`
```
struct OptionObserver
{
  void *mToken;
  ValueChangedCallback mOnValueChangeCallback;
  InputModeValueChangedCallback mOnInputModeValueChangeCallback;
};

```

### `OptionLock`
```
struct OptionLock
{
  std::function<bool ()> isModifiableCondition;
  void *mToken;
};

```

### `OwnedActorList`
```
typedef std::vector<std::unique_ptr<Actor>> OwnedActorList;

```

### `OnDeathDescription`
```
struct __cppobj OnDeathDescription : TriggerDescription
{
};

```

### `OnHurtByPlayerDescription`
```
struct __cppobj OnHurtByPlayerDescription : TriggerDescription
{
};

```

### `OnHurtDescription`
```
struct __cppobj OnHurtDescription : TriggerDescription
{
};

```

### `OnIgniteDescription`
```
struct __cppobj OnIgniteDescription : TriggerDescription
{
};

```

### `OnStartLandingDescription`
```
struct __cppobj OnStartLandingDescription : TriggerDescription
{
};

```

### `OnStartTakeoffDescription`
```
struct __cppobj OnStartTakeoffDescription : TriggerDescription
{
};

```

### `OnTargetAcquiredDescription`
```
struct __cppobj OnTargetAcquiredDescription : TriggerDescription
{
};

```

### `OnTargetEscapeDescription`
```
struct __cppobj OnTargetEscapeDescription : TriggerDescription
{
};

```

### `OnWakeWithOwnerDescription`
```
struct __cppobj OnWakeWithOwnerDescription : TriggerDescription
{
};

```

### `OpenDoorAnnotationDescription`
```
struct __cppobj OpenDoorAnnotationDescription : ComponentDescription
{
};

```

### `OverloadSyntaxInformation`
```
struct OverloadSyntaxInformation
{
  std::string text;
  OverloadSyntaxInformation::CursorPos start;
  OverloadSyntaxInformation::CursorPos length;
};

```

### `Ocelot`
```
struct __cppobj Ocelot : Animal
{
};

```

### `OwnerHurtByTargetGoal`
```
struct __cppobj OwnerHurtByTargetGoal : TargetGoal
{
  TempEPtr<Mob> mOwnerHurtBy;
  Mob *mMob;
};

```

### `OwnerHurtTargetGoal`
```
struct __cppobj __attribute__((aligned(8))) OwnerHurtTargetGoal : TargetGoal
{
  TempEPtr<Mob> mLastOwnerHurt;
  Mob *mMob;
  int mTimestamp;
};

```

### `OcelotAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) OcelotAttackGoal : Goal:96
{
  int mAttackTime;
  Mob *mMob;
  float mWalkSpeedModifier;
  float mSprintSpeedModifier;
  float mSneakSpeedModifier;
};

```

### `OcelotSitOnBlockGoal`
```
struct __cppobj OcelotSitOnBlockGoal : BaseMoveToBlockGoal
{
  Mob *mMob;
};

```

### `OfferFlowerGoal`
```
struct __cppobj OfferFlowerGoal : Goal
{
  TempEPtr<Mob> mOfferedToMob;
  int mGameTicks;
  IronGolem *mGolem;
};

```

### `OpenDoorGoal`
```
struct __cppobj OpenDoorGoal : DoorInteractGoal
{
  bool mCloseDoor;
  int mForgetTime;
  Mob *mMob;
};

```

### `OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> >`
```
struct __cppobj OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> > : SharePtrRefTraits<PerlinSimplexNoise>::OwnerStorage
{
};

```

### `OwnerStorageSharePtr<PerlinSimplexNoise>`
```
struct OwnerStorageSharePtr<PerlinSimplexNoise>
{
  std::shared_ptr<PerlinSimplexNoise> mValue;
};

```

### `OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> >::OwnerStackRef`
```
typedef SharePtrRefTraits<PerlinSimplexNoise>::OwnerStackRef OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> >::OwnerStackRef;

```

### `OreBlock`
```
struct __cppobj OreBlock : BlockLegacy
{
};

```

### `OldLogBlock`
```
struct __cppobj OldLogBlock : LogBlock
{
};

```

### `OldLeafBlock`
```
struct __cppobj OldLeafBlock : LeafBlock
{
};

```

### `ObsidianBlock`
```
struct __cppobj __attribute__((aligned(8))) ObsidianBlock : BlockLegacy
{
  bool mIsGlowing;
};

```

### `ObserverBlock`
```
struct __cppobj ObserverBlock : FaceDirectionalBlock
{
};

```

### `OceanMonumentStart`
```
struct __cppobj __attribute__((aligned(8))) OceanMonumentStart : StructureStart
{
  bool isCreated;
};

```

### `OceanMonumentPiece`
```
struct __cppobj OceanMonumentPiece : StructurePiece
{
  bool mDoFill;
  Shared<RoomDefinition> mRoomDefinition;
};

```

### `OceanMonumentEntryRoom`
```
struct __cppobj OceanMonumentEntryRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentCoreRoom`
```
struct __cppobj OceanMonumentCoreRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentWingRoom`
```
struct __cppobj __attribute__((aligned(4))) OceanMonumentWingRoom : OceanMonumentPiece
{
  int mMainDesign;
  bool mIsRightWing;
};

```

### `OceanMonumentPenthouse`
```
struct __cppobj OceanMonumentPenthouse : OceanMonumentPiece
{
};

```

### `OceanMonumentSimpleRoom`
```
struct __cppobj __attribute__((aligned(8))) OceanMonumentSimpleRoom : OceanMonumentPiece
{
  int mMainDesign;
};

```

### `OceanMonumentSimpleTopRoom`
```
struct __cppobj OceanMonumentSimpleTopRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleYRoom`
```
struct __cppobj OceanMonumentDoubleYRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleXRoom`
```
struct __cppobj OceanMonumentDoubleXRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleZRoom`
```
struct __cppobj OceanMonumentDoubleZRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleXYRoom`
```
struct __cppobj OceanMonumentDoubleXYRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleYZRoom`
```
struct __cppobj OceanMonumentDoubleYZRoom : OceanMonumentPiece
{
};

```

### `OpCommand`
```
struct __cppobj OpCommand : ServerCommand
{
  PlayerSelector mTargets;
};

```

### `OffhandContainerController`
```
struct __cppobj OffhandContainerController : ContainerController
{
};

```

### `OutputContainerController`
```
struct __cppobj OutputContainerController : ContainerController
{
};

```

