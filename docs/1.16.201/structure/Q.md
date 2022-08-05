# Q
### `QueryManifestDocument`
Offset | Type | Name
-|-|-|-
0 | (584) `CommonDocument` | mCommon
584 | (24) `QueryManifestCustom` | mCustom


### `QueryManifestCustom`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<StoreVisualStyle>>` | mStoreScreenLayout


### `QueryDocument`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mContentTypes
24 | (32) `std::string` | mSearchString
56 | (24) `std::vector<std::string>` | mOrTags
80 | (24) `std::vector<std::string>` | mAndTags
104 | (24) `std::vector<std::string>` | mNotTags
128 | (24) `std::vector<std::string>` | mRarityFilters
152 | (24) `std::vector<std::string>` | mPieceTypeFilters
176 | (24) `std::vector<std::string>` | mPieceTypeFilterExclusions
200 | (24) `std::vector<std::string>` | mProductIdOrder
224 | (24) `std::vector<std::string>` | mCreatorIds
248 | (24) `std::vector<std::string>` | mProductIdExclusions
272 | (24) `std::vector<std::string>` | mCreatorIdExclusions
296 | (4) `int` | mItemLimit
300 | (4) `int` | mTopCount
304 | (32) `std::string` | mClientSort
336 | (32) `std::string` | mSortBy
368 | (32) `std::string` | mSortDirection
400 | (24) `std::vector<std::string>` | mUpsellQueryTags
424 | (4) `int` | mCarouselRotationTime


### `QueryPurchaseResult`
```
struct __cppobj QueryPurchaseResult
{
  bool success;
  std::vector<PurchaseInfo> purchaseInfo;
};

```

### `QueryManifestSearchResults`
```
const struct __cppobj QueryManifestSearchResults : CommonSearchResults
{
  std::vector<QueryManifestDocument> mDocuments;
};

```

### `QOS_OBJECT_HDR`
```
struct QOS_OBJECT_HDR
{
  unsigned int ObjectType;
  unsigned int ObjectLength;
};

```

### `QueuedSkinUpdate`
```
struct __cppobj QueuedSkinUpdate
{
  std::weak_ptr<IClientInstance> mClient;
  const SerializedSkin mSkin;
  mce::Image mImage;
  mce::Image mCapeImage;
  std::function<void __cdecl(void)> mGeoFinishedCallback;
  mce::Image mBloomImage;
};

```

### `QuizScreenController`
```
struct __cppobj QuizScreenController : MinecraftScreenController
{
  std::optional<std::string > mQuizUrl;
  bool mQuizQueryInProgress;
  bool mRefreshContent;
  std::shared_ptr<LessonProgressionService> mLessonProgressionService;
};

```

### `QuizScreenController_vtbl`
```
struct /*VFT*/ QuizScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `QuizScreenController::_registerEventHandlers::__l2::<lambda_19db060bb133f580aa0ada1b0c788eb3>`
```
struct __cppobj QuizScreenController::_registerEventHandlers::__l2::<lambda_19db060bb133f580aa0ada1b0c788eb3>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerEventHandlers::__l2::<lambda_5ccd21d441fae808a53a99816163fe2f>`
```
struct __cppobj QuizScreenController::_registerEventHandlers::__l2::<lambda_5ccd21d441fae808a53a99816163fe2f>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerEventHandlers::__l2::<lambda_42779dfb5d8240c2eca679c36f0e47ec>`
```
struct __cppobj QuizScreenController::_registerEventHandlers::__l2::<lambda_42779dfb5d8240c2eca679c36f0e47ec>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerEventHandlers::__l2::<lambda_42779dfb5d8240c2eca679c36f0e47ec>::()::__l5::<lambda_b97e973a9c9a256cd35be5d64c92d3bc>`
```
struct __cppobj QuizScreenController::_registerEventHandlers::__l2::<lambda_42779dfb5d8240c2eca679c36f0e47ec>::()::__l5::<lambda_b97e973a9c9a256cd35be5d64c92d3bc>
{
  std::weak_ptr<QuizScreenController> weakThis;
};

```

### `QuizScreenController::_registerBindings::__l2::<lambda_88613c7e5be06e8dd46ac14e04ed9555>`
```
struct __cppobj QuizScreenController::_registerBindings::__l2::<lambda_88613c7e5be06e8dd46ac14e04ed9555>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerBindings::__l2::<lambda_301f24380ff1da8505d841fdf272fca9>`
```
struct __cppobj QuizScreenController::_registerBindings::__l2::<lambda_301f24380ff1da8505d841fdf272fca9>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerBindings::__l2::<lambda_b22d950e82f3710b33fce59b40fe6367>`
```
struct __cppobj QuizScreenController::_registerBindings::__l2::<lambda_b22d950e82f3710b33fce59b40fe6367>
{
  QuizScreenController *const __this;
};

```

### `QuizScreenController::_registerBindings::__l2::<lambda_739ba1f0bcea3bf4f0a39a571fec5161>`
```
struct __cppobj QuizScreenController::_registerBindings::__l2::<lambda_739ba1f0bcea3bf4f0a39a571fec5161>
{
  QuizScreenController *const __this;
};

```

### `QueryTargetCommand`
```
struct __cppobj QueryTargetCommand : Command
{
  CommandSelector<Actor> mTargets;
};

```

### `QueryTargetCommand_vtbl`
```
struct /*VFT*/ QueryTargetCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `QuartzBlockBlock`
```
struct __cppobj QuartzBlockBlock : RotatedPillarBlock
{
};

```

### `QuartzBlockBlock_vtbl`
```
struct /*VFT*/ QuartzBlockBlock_vtbl
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

