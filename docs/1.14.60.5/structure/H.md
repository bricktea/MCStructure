# H
### `HashedString`
Offset | Type | Name
-|-|-|-
0 | (8) `HashType64` | mStrHash
8 | (32) `std::string` | mStr


### `HellSpringFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock
32 | (1) `bool` | mInsideRock


### `HellFireFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `HerdList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<MobSpawnHerdInfo>` | baseclass_0


### `HopperComponent`
Offset | Type | Name
-|-|-|-
0 | (12) `Hopper` | baseclass_0
12 | (12) `BlockPos` | mLastPosition


### `Hopper`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCooldownTime
4 | (1) `bool` | mTransferedFromChestMinecart
5 | (1) `bool` | mIsEntity
8 | (4) `int` | mMoveItemSpeed


### `HurtOnConditionComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `HitResult`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mStartPos
12 | (12) `Vec3` | mRayDir
24 | (4) `HitResultType` | mType
28 | (1) `FacingID` | mFacing
32 | (12) `BlockPos` | mBlock
44 | (12) `Vec3` | mPos
56 | (8) `Actor *` | mEntity
64 | (1) `bool` | mIsHitLiquid
65 | (1) `FacingID` | mLiquidFacing
68 | (12) `BlockPos` | mLiquid
80 | (12) `Vec3` | mLiquidPos
92 | (1) `bool` | mIndirectHit


### `HurtArmorPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mDmg


### `HealableDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<FeedItem>` | mHealItems
24 | (1) `bool` | mForceUse
32 | (64) `ActorFilterGroup` | mFilter


### `HideComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsInRaid
1 | (1) `bool` | mReactToBell


### `HealableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `HomeComponent`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mHomePos
12 | (4) `DimensionType` | mDimensionId


### `HugeMushroomFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (4) `int` | mForcedType


### `HurtOnConditionDefinition::deserializeData::$B7C8591B4983496A0E79D8038F2BDAD9`
Offset | Type | Name
-|-|-|-
0 | (8) `HurtOnConditionDefinition *` | this


### `HeavyBlock::animateTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `HopperSystem`
```
struct __cppobj HopperSystem : ITickingSystem
{
};

```

### `HurtOnConditionSystem`
```
struct __cppobj HurtOnConditionSystem : ITickingSystem
{
};

```

### `HardcodedSpawnAreaRegistry`
```
struct HardcodedSpawnAreaRegistry
{
  std::unordered_map<HardcodedSpawnAreaType,std::vector<MobSpawnerData>> mMap;
};

```

### `HurtOnConditionDefinition`
```
struct HurtOnConditionDefinition
{
  DamageConditionList mDamageConditions;
};

```

### `HeavyBlock`
```
struct __cppobj HeavyBlock : BlockLegacy
{
};

```

### `HudContainerManagerModel`
```
struct __cppobj HudContainerManagerModel : ContainerManagerModel
{
  HudContainerManagerModel::ItemInstanceVector mLastSlots;
};

```

### `HideDescription`
```
struct __cppobj HideDescription : ComponentDescription
{
};

```

### `HopperContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) HopperContainerManagerModel : LevelContainerManagerModel
{
};

```

### `HorseContainerManagerModel`
```
struct __cppobj HorseContainerManagerModel : LevelContainerManagerModel
{
  std::weak_ptr<ContainerModel> mEquipContainerModel;
};

```

### `HomeDefinition`
```
struct HomeDefinition
{
  __int8 gap0[1];
};

```

### `Horse`
```
struct __cppobj __attribute__((aligned(8))) Horse : Animal
{
  std::string layerTextureHashName;
  std::string layerTextureLayers[3];
  bool mHasReproduced;
  float mEatAnim;
  float mEatAnimO;
  float mStandAnim;
  float mStandAnimO;
  float mMouthAnim;
  float mMouthAnimO;
  int mCountEating;
  int mMouthCounter;
  int mStandCounter;
  int mSprintCounter;
  int mGallopSoundCounter;
  int mTailCounter;
};

```

### `HangingActor`
```
struct __cppobj HangingActor : Actor
{
  int mDir;
  int mCheckInterval;
};

```

### `HopperBlockActor`
```
struct __cppobj HopperBlockActor : BlockActor, Container:1952, Hopper
{
  ItemStack mItems[5];
  Tick mLastTick;
};

```

### `HopMoveControl`
```
struct __cppobj __attribute__((aligned(8))) HopMoveControl : MoveControl
{
  int mJumpDelayTicks;
};

```

### `HoverMoveControl`
```
struct __cppobj HoverMoveControl : MoveControl
{
};

```

### `HoverPathNavigation`
```
struct __cppobj __attribute__((aligned(8))) HoverPathNavigation : PathNavigation
{
  bool mCanPathFromAir;
};

```

### `HealthAttributeDelegate`
```
struct __cppobj HealthAttributeDelegate : AttributeInstanceDelegate
{
  int32_t mTickCounter;
  Mob *mMob;
};

```

### `HoverGoal`
```
struct __cppobj HoverGoal : Goal
{
  Mob *mMob;
  float mSpeedMultiplier;
  Vec3 mStartPos;
};

```

### `HurtByTargetGoal`
```
struct __cppobj HurtByTargetGoal : TargetGoal
{
};

```

### `HideGoal`
```
struct __cppobj __attribute__((aligned(8))) HideGoal : MoveToPOIGoal
{
  __int16 mHideAttempts;
};

```

### `HoldGroundGoal`
```
struct __cppobj HoldGroundGoal : Goal
{
  Mob *mMob;
  TempEPtr<Actor> mLookAt;
  float mHostileRadiusSqr;
  bool mBroadcast;
  float mBroadcastRange;
  const DefinitionTrigger mWithinRangeEvent;
  const DefinitionTrigger mHurtByTargetEvent;
};

```

### `HarvestFarmBlockGoal`
```
struct __cppobj HarvestFarmBlockGoal : BaseMoveToBlockGoal
{
  bool mCanPlantStuff;
  bool mWantsToReapStuff;
  HarvestFarmBlockGoal::Task mCurrentTask;
};

```

### `HumanoidMonster`
```
struct __cppobj HumanoidMonster : Monster
{
};

```

### `HungerAttributeDelegate`
```
struct __cppobj HungerAttributeDelegate : AttributeInstanceDelegate
{
  int32_t mActionTickTimer;
  int32_t mTickCounter;
  float mLastFoodLevel;
  Player *mPlayer;
};

```

### `HurtOwnerSubcomponent`
```
struct __cppobj __attribute__((aligned(4))) HurtOwnerSubcomponent : OnHitSubcomponent
{
  float mOwnerDamage;
  bool mKnockback;
  bool mIgnite;
};

```

### `HudContainerModel`
```
struct __cppobj HudContainerModel : ContainerModel
{
  Player *mPlayer;
};

```

### `HudContainerManagerModel::ItemInstanceVector`
```
typedef std::vector<ContainerItemStack> HudContainerManagerModel::ItemInstanceVector;

```

### `HorseArmorItem`
```
struct __cppobj __attribute__((aligned(8))) HorseArmorItem : Item
{
  const int mDefense;
  const int mModelIndex;
  HorseArmorItem::HorseArmorTier mTier;
};

```

### `HatchetItem`
```
struct __cppobj HatchetItem : DiggerItem
{
};

```

### `HoeItem`
```
struct __cppobj __attribute__((aligned(8))) HoeItem : Item
{
  Item::Tier mTier;
};

```

### `HangingActorItem`
```
struct __cppobj __attribute__((aligned(8))) HangingActorItem : Item
{
  ActorType mEntityType;
};

```

### `HillsTransformationAttributes`
```
typedef WeightedBiomeAttributes<HillsTransformation> HillsTransformationAttributes;

```

### `HugeMushroomBlock`
```
struct __cppobj __attribute__((aligned(8))) HugeMushroomBlock : BlockLegacy
{
  HugeMushroomBlock::Type mType;
};

```

### `HopperBlock`
```
struct __cppobj HopperBlock : ActorBlock
{
};

```

### `HayBlockBlock`
```
struct __cppobj HayBlockBlock : RotatedPillarBlock
{
};

```

### `HoneyBlock`
```
struct __cppobj HoneyBlock : BlockLegacy
{
};

```

### `HoneycombBlock`
```
struct __cppobj HoneycombBlock : BlockLegacy
{
};

```

### `HopperDefinition`
```
struct HopperDefinition
{
  __int8 gap0[1];
};

```

### `HelpCommand`
```
struct __cppobj __attribute__((aligned(8))) HelpCommand : Command
{
  std::string mCommand;
  int mPage;
};

```

### `HorseEquipContainerController`
```
struct __cppobj HorseEquipContainerController : ContainerController
{
  std::vector<ItemInstance> mAllowedSaddleItems;
  std::vector<ItemInstance> mAllowedArmorItems;
};

```

### `HuffmanEncodingTreeNode`
```
struct HuffmanEncodingTreeNode
{
  unsigned __int8 value;
  unsigned int weight;
  HuffmanEncodingTreeNode *left;
  HuffmanEncodingTreeNode *right;
  HuffmanEncodingTreeNode *parent;
};

```

### `hostent`
```
struct hostent
{
  char *h_name;
  char **h_aliases;
  int h_addrtype;
  int h_length;
  char **h_addr_list;
};

```

### `HashedString::StringHasher<const char *>`
```
struct HashedString::StringHasher<const char *>
{
  __int8 gap0[1];
};

```

