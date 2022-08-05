# K
### `KTX::KTXInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | glInterFormat
8 | (24) `std::vector<int>` | imageSizeList
32 | (1) `unsigned __int8` | mipmapCount
36 | (4) `unsigned int` | storageSize


### `KickCommandData`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | requiredPermissionLevel
8 | (16) `gsl::basic_string_span<char const ,-1>` | name
24 | (16) `gsl::basic_string_span<char const ,-1>` | description
40 | (16) `gsl::basic_string_span<char const ,-1>` | reason
56 | (16) `gsl::basic_string_span<char const ,-1>` | success
72 | (16) `gsl::basic_string_span<char const ,-1>` | alias
88 | (16) `gsl::basic_string_span<char const ,-1>` | targetParamTitle
104 | (16) `gsl::basic_string_span<char const ,-1>` | reasonDescription


### `KillStrings`
Offset | Type | Name
-|-|-|-
0 | (16) `gsl::basic_string_span<char const ,-1>` | name
16 | (16) `gsl::basic_string_span<char const ,-1>` | description
32 | (16) `gsl::basic_string_span<char const ,-1>` | success
48 | (16) `gsl::basic_string_span<char const ,-1>` | alias


### `Keymapping`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mAction
32 | (24) `std::vector<int>` | mKeys
56 | (1) `bool` | mAllowRemap


### `KeyManager`
Offset | Type | Name
-|-|-|-
0 | (8) `KeyManager_vtbl *` | __vftable
8 | (32) `std::string` | mPublicKey
40 | (8) `std::unique_ptr<Crypto::Asymmetric::Asymmetric>` | mInstance


### `KeyboardAction`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | state
4 | (1) `unsigned __int8` | key
8 | (4) `int` | controllerId


### `KeyOrNameResult`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mString
32 | (4) `KeyOrNameResult::ResultType` | mType


### `KeyFrameTransform`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<KeyFrameTransformData>` | mPrePost
24 | (16) `KeyFrameLerpMode` | mLerpMode
40 | (4) `float` | mKeyFrameTimeStamp


### `KeyFrameLerpMode`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<glm::tmat4x4<float,0>>` | mPrecomputedCubicCoeffs
8 | (4) `_BYTE[4]` | mLerpStyle


### `KnockBackEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mActor


### `KNOWNFOLDERID`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Data1
4 | (2) `unsigned __int16` | Data2
6 | (2) `unsigned __int16` | Data3
8 | (8) `unsigned __int8[8]` | Data4


### `KeyboardInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<KeyboardKeyBinding>` | keyBindings


### `KeyboardMapper::KeyboardKeyButtonDetails`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | nameId
4 | (1) `FocusImpact` | focusImpact


### `KeyboardMapper::KeyboardMappingData`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_multimap<int,KeyboardMapper::KeyboardKeyButtonDetails>` | mKeyboardKeyToButtonDetailsMap


### `KeyboardRemappingLayout`
```
struct __cppobj __declspec(align(8)) KeyboardRemappingLayout : RemappingLayout
{
  const KeyboardType mKeyboardType;
};

```

### `KeyboardRemappingLayout_vtbl`
```
struct /*VFT*/ KeyboardRemappingLayout_vtbl
{
  void (__fastcall *~RemappingLayout)(RemappingLayout *this);
  void (__fastcall *setMappingWithRawInput)(RemappingLayout *this, const std::string *, int, RawInputType);
  int (__fastcall *getAdjustedKey)(RemappingLayout *this, int);
  std::string *(__fastcall *getSaveString)(RemappingLayout *this, std::string *result, const std::string *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int, bool);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, int);
  int (__fastcall *_rawKeyToKey)(RemappingLayout *this, int, RawInputType);
};

```

### `KeyManager_vtbl`
```
struct /*VFT*/ KeyManager_vtbl
{
  void (__fastcall *~KeyManager)(KeyManager *this);
  bool (__fastcall *isValid)(KeyManager *this);
};

```

### `KeyboardManager`
```
struct __cppobj KeyboardManager
{
  KeyboardManager_vtbl *__vftable /*VFT*/;
};

```

### `KeyboardManager_vtbl`
```
struct /*VFT*/ KeyboardManager_vtbl
{
  void (__fastcall *~KeyboardManager)(KeyboardManager *this);
  bool (__fastcall *tryEnableKeyboard)(KeyboardManager *this, const std::string *, int, bool, bool, bool, const Vec2 *, float);
  bool (__fastcall *isFullScreenKeyboard)(KeyboardManager *this);
  void (__fastcall *disableKeyboard)(KeyboardManager *this);
  void (__fastcall *setKeyboardActive)(KeyboardManager *this, bool);
  bool (__fastcall *canActivateKeyboard)(KeyboardManager *this);
  bool (__fastcall *isKeyboardEnabled)(KeyboardManager *this);
  bool (__fastcall *isKeyboardActive)(KeyboardManager *this);
  bool (__fastcall *wasEnabledWithMultiline)(KeyboardManager *this);
  int (__fastcall *getMaxLength)(KeyboardManager *this);
  float (__fastcall *getKeyboardHeight)(KeyboardManager *this);
  void (__fastcall *setForcedHeight)(KeyboardManager *this, float);
  bool (__fastcall *tryClaimKeyboardOwnership)(KeyboardManager *this);
  void (__fastcall *releaseKeyboardOwnership)(KeyboardManager *this);
  bool (__fastcall *getKeyboardClosedEvent)(KeyboardManager *this);
  void (__fastcall *clearKeyboardClosedEvent)(KeyboardManager *this);
  void (__fastcall *updateTextEditBoxPosition)(KeyboardManager *this, const RectangleArea *, const Vec2 *, const Vec2 *);
};

```

### `KeyFrameTransformData`
```
struct __cppobj KeyFrameTransformData
{
  std::vector<ChannelTransform> mChannelTransforms;
  std::vector<ChannelTransform_Float> mChannelTransforms_Floats;
};

```

### `KeyboardKeyBinding`
```
struct __cppobj __declspec(align(4)) KeyboardKeyBinding
{
  std::string buttonName;
  int keyNum;
  FocusImpact focusImpact;
};

```

### `KnockbackArmorUpdater`
```
struct __cppobj KnockbackArmorUpdater : ActorEventListener
{
};

```

### `KnockbackArmorUpdater_vtbl`
```
struct /*VFT*/ KnockbackArmorUpdater_vtbl
{
  void (__fastcall *~ActorEventListener)(ActorEventListener *this);
  EventResult (__fastcall *onActorAttack)(ActorEventListener *this, Actor *, Actor *, int);
  EventResult (__fastcall *onActorHit)(ActorEventListener *this, Actor *, const ActorDamageSource *, int *, bool *, bool *);
  EventResult (__fastcall *onActorHurt)(ActorEventListener *this, const ActorHurtEvent *);
  EventResult (__fastcall *onActorMove)(ActorEventListener *this, Actor *, const Vec3 *);
  EventResult (__fastcall *onActorPredictedMove)(ActorEventListener *this, Actor *, MovePredictionType, const Vec3 *);
  EventResult (__fastcall *onActorTick)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorSneakChanged)(ActorEventListener *this, Actor *, bool);
  EventResult (__fastcall *onActorStartRiding)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorStopRiding)(ActorEventListener *this, Actor *, bool, bool, bool);
  EventResult (__fastcall *onActorDeath)(ActorEventListener *this, Actor *, const ActorDamageSource *, ActorType);
  EventResult (__fastcall *onActorDefinitionEventTriggered)(ActorEventListener *this, const ActorDefinitionEvent *);
  EventResult (__fastcall *onActorUseItem)(ActorEventListener *this, const ActorUseItemEvent *);
  EventResult (__fastcall *onActorUseItemOn)(ActorEventListener *this, Actor *, const ItemStack *, const BlockPos *, unsigned __int8);
  EventResult (__fastcall *onActorCreated)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onProjectileHit)(ActorEventListener *this, const ProjectileHitEvent *);
  EventResult (__fastcall *onActorTeleported)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorAttackedActor)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorAcquiredItem)(ActorEventListener *this, const ActorAcquiredItemEvent *);
  EventResult (__fastcall *onActorPlacedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorDroppedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorCarriedItemChanged)(ActorEventListener *this, Actor *, const ItemInstance *, const ItemInstance *, HandSlot);
  EventResult (__fastcall *onActorEquippedArmor)(ActorEventListener *this, Actor *, const ItemInstance *, ArmorSlot);
  EventResult (__fastcall *onActorRemoved)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorMobInteraction)(ActorEventListener *this, Actor *, MinecraftEventing::InteractionType, ActorType);
  EventResult (__fastcall *onActorTargetAcquired)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorGriefingBlock)(ActorEventListener *this, const ActorGriefingBlockEvent *);
  EventResult (__fastcall *onActorAddEffect)(ActorEventListener *this, const ActorAddEffectEvent *);
  EventResult (__fastcall *onActorKilled)(ActorEventListener *this, const ActorKilledEvent *);
  EventResult (__fastcall *onActorRemoveEffect)(ActorEventListener *this, const ActorRemoveEffectEvent *);
  EventResult (__fastcall *onKnockBack)(ActorEventListener *this, const KnockBackEvent *);
  EventResult (__fastcall *onMountTaming)(ActorEventListener *this, const MountTamingEvent *);
  EventResult (__fastcall *onActorAnimationChanged)(ActorEventListener *this, const ActorAnimationChangedEvent *);
  EventResult (__fastcall *onSendActorAddBuff)(ActorEventListener *this, Actor *, const AttributeInstance *, const std::string *, int, bool, int, int, int);
};

```

### `KeySpan`
```
struct __cppobj KeySpan
{
  const std::string name;
  const int start;
  int end;
};

```

### `KeyboardLayout`
```
struct __cppobj KeyboardLayout
{
};

```

### `KnockbackResistanceItemComponent`
```
struct __cppobj __declspec(align(8)) KnockbackResistanceItemComponent : ItemComponent
{
  float mProtection;
};

```

### `KnockbackResistanceItemComponent_vtbl`
```
struct /*VFT*/ KnockbackResistanceItemComponent_vtbl
{
  void (__fastcall *~ItemComponent)(ItemComponent *this);
  bool (__fastcall *checkComponentDataForContentErrors)(ItemComponent *this);
  void (__fastcall *writeSettings)(ItemComponent *this);
  bool (__fastcall *useOn)(ItemComponent *this, ItemStack *, Actor *, const BlockPos *, unsigned __int8, const Vec3 *);
  bool (__fastcall *isNetworkComponent)(ItemComponent *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(ItemComponent *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(ItemComponent *this, const CompoundTag *);
};

```

### `Keyboard`
```
struct __cppobj Keyboard
{
};

```

### `KeyboardMapper`
```
struct __cppobj KeyboardMapper : InputDeviceMapper
{
  std::unordered_map<int,KeyboardMapper::KeyboardMappingData> mPerIdMappings;
};

```

### `KeyboardMapper_vtbl`
```
struct /*VFT*/ KeyboardMapper_vtbl
{
  void (__fastcall *~InputDeviceMapper)(InputDeviceMapper *this);
  void (__fastcall *setMapping)(InputDeviceMapper *this, InputEventQueue *, const BindingFactory *, const InputMapping *, int);
  void (__fastcall *clearMapping)(InputDeviceMapper *this, int);
  void (__fastcall *clearInputDeviceQueue)(InputDeviceMapper *this);
  void (__fastcall *clearInputDeviceQueueForFrame)(InputDeviceMapper *this);
  void (__fastcall *hardResetInputDeviceQueue)(InputDeviceMapper *this);
  bool (__fastcall *tick)(InputDeviceMapper *this, InputEventQueue *, ControllerIDtoClientMap *);
  InputMode (__fastcall *getInputMode)(InputDeviceMapper *this);
  void (__fastcall *getCursorPos)(InputDeviceMapper *this, float *, float *);
  void (__fastcall *render)(InputDeviceMapper *this, InputRenderContext *);
  void (__fastcall *setWindowSize)(InputDeviceMapper *this, int, int);
  void (__fastcall *setBindingMode)(InputDeviceMapper *this, InputBindingMode, int);
  InputBindingMode (__fastcall *getBindingMode)(InputDeviceMapper *this, int);
  void (__fastcall *changeControllerId)(InputDeviceMapper *this, int, int);
};

```

### `KickCommand`
```
struct __cppobj KickCommand : ServerCommand
{
  CommandSelector<Player> mPlayers;
  CommandMessage mMessage;
};

```

### `KickCommand_vtbl`
```
struct /*VFT*/ KickCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `KillCommand`
```
struct __cppobj KillCommand : Command
{
  CommandSelector<Actor> mTargets;
};

```

### `KillCommand_vtbl`
```
struct /*VFT*/ KillCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `KillCommand::{ctor}::__l2::<lambda_cb2bf1939a96fa330fd7ec1c15d0e65d>`
```
struct __cppobj KillCommand::{ctor}::__l2::<lambda_cb2bf1939a96fa330fd7ec1c15d0e65d>
{
};

```

### `KelpBlock`
```
struct __cppobj KelpBlock : BlockLegacy
{
};

```

### `KelpBlock_vtbl`
```
struct /*VFT*/ KelpBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `KNOWNFOLDER_DEFINITION`
```
struct KNOWNFOLDER_DEFINITION
{
  KF_CATEGORY category;
  wchar_t *pszName;
  wchar_t *pszDescription;
  _GUID fidParent;
  wchar_t *pszRelativePath;
  wchar_t *pszParsingName;
  wchar_t *pszTooltip;
  wchar_t *pszLocalizedName;
  wchar_t *pszIcon;
  wchar_t *pszSecurity;
  unsigned int dwAttributes;
  unsigned int kfdFlags;
  _GUID ftidType;
};

```

### `KEncrypt::_ValueInfo`
```
struct KEncrypt::_ValueInfo
{
  unsigned int KeyHash;
  unsigned int Value;
};

```

### `KnockbackRoarGoal`
```
struct __cppobj __declspec(align(8)) KnockbackRoarGoal : Goal
{
  const int mDuration;
  const int mAttackTime;
  const int mKnockbackDamage;
  const int mKnockbackStrength;
  const int mKnockbackRange;
  ActorFilterGroup mKnockbackFilter;
  ActorFilterGroup mDamageFilter;
  const DefinitionTrigger mOnRoarEnd;
  const int mCooldownTime;
  int mCurrentCooldown;
  Mob *mMob;
  int mRoarTime;
};

```

### `KnockbackRoarGoal_vtbl`
```
struct /*VFT*/ KnockbackRoarGoal_vtbl
{
  void (__fastcall *~Goal)(Goal *this);
  bool (__fastcall *canUse)(Goal *this);
  bool (__fastcall *canContinueToUse)(Goal *this);
  bool (__fastcall *canBeInterrupted)(Goal *this);
  void (__fastcall *start)(Goal *this);
  void (__fastcall *stop)(Goal *this);
  void (__fastcall *tick)(Goal *this);
  void (__fastcall *appendDebugInfo)(Goal *this, std::string *);
  bool (__fastcall *isTargetGoal)(Goal *this);
  void (__fastcall *onPlayerDimensionChanged)(Goal *this, Player *, AutomaticID<Dimension,int>);
};

```

### `KelpFeature`
```
struct __cppobj KelpFeature : Feature
{
};

```

### `KelpFeature_vtbl`
```
struct /*VFT*/ KelpFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `KeyFrameTransform::computeCubicPolynomial::__l9::<lambda_8345864a9afa0c4a53458247a6c1a2c5>`
```
struct __cppobj KeyFrameTransform::computeCubicPolynomial::__l9::<lambda_8345864a9afa0c4a53458247a6c1a2c5>
{
};

```

