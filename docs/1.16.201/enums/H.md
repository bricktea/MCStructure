# H
### `HoloUIInputMode`
Name | Value
-|-
Unknown | `0`
sRGB | `1`
Linear | `2`


### `hbui::RouteMode`
Name | Value
-|-


### `HolosceneRenderer::InWorldCursorMode`
Name | Value
-|-
Interactible | `0`
NoHit | `1`
EntityTooFar | `2`
ForceFull | `3`


### `HandSlot`
Name | Value
-|-
Drift | `0`
Fixed | `1`
Offhand | `2`


### `HTTPRequest::Method`
Name | Value
-|-
Like | `0`
Unlike | `1`
Post | `2`
Delete | `3`
Report | `4`
Comment | `5`


### `HitResultType`
Name | Value
-|-
TILE | `0`
ENTITY_OUT_OF_RANGE | `2`
NO_HIT | `3`


### `HoloUIToPoseSource`
Name | Value
-|-
NonVR | `0`
MainMenu | `1`
LivingRoom | `2`
VRTransition | `3`
VRHeadlocked | `4`
VRFloatingHUD | `5`
VRHandheldHUD | `6`


### `hbui::RouteType`
Name | Value
-|-
Gameface | `0`
Bedrock | `1`


### `hbui::HybridResourceFileSystem`
Name | Value
-|-
AppPackage | `0`
TrustedPack | `1`


### `hbui::Router::QueuedRouteAction`
Name | Value
-|-
Push | `0`
IgnoreStackPop | `1`
ReplaceOnPop | `2`
GoBackAndReplaceOnPop | `3`
Replace | `4`
ReplaceWithNonGameface | `5`


### `HudScreenController::Tooltip::Type`
Name | Value
-|-
KeyboardOnly | `0`
GamepadOnly | `1`
Mixed | `2`


### `HowToPlayTopicIndex`
Name | Value
-|-
COMMAND_BLOCK_OUTPUT | `0`
DO_DAYLIGHT_CYCLE | `1`
DO_ENTITY_DROPS | `2`
DO_FIRE_TICK | `3`
DO_MOB_LOOT | `4`
DO_MOB_SPAWNING | `5`
DO_TILE_DROPS | `6`
DO_WEATHER_CYCLE | `7`
DROWNING_DAMAGE | `8`
FALL_DAMAGE | `9`
FIRE_DAMAGE | `10`
KEEP_INVENTORY | `11`
MOB_GRIEFING | `12`
PVP | `13`
SHOW_COORDINATES | `14`
DO_NATURAL_REGENERATION | `15`
DO_TNT_EXPLODE | `16`
SEND_COMMAND_FEEDBACK | `17`
MAX_COMMAND_CHAIN_LENGTH | `18`
DO_INSOMNIA | `19`
COMMAND_BLOCKS_ENABLED | `20`
RANDOM_TICK_SPEED | `21`
DO_IMMEDIATE_RESPAWN | `22`
SHOW_DEATH_MESSAGES | `23`
FUNCTION_COMMAND_LIMIT | `24`
PLAYER_SPAWN_RADIUS | `25`
SHOW_TAGS | `26`
VANILLA_GAME_RULE_COUNT | `27`
GLOBAL_MUTE | `27`
ALLOW_DESTRUCTIVE_OBJECTS | `28`
ALLOW_MOBS | `29`
CODE_BUILDER | `30`
EDU_GAME_RULE_COUNT | `31`
INVALID_GAME_RULE | `18446744073709551615`


### `HorseArmorItem::Tier`
Name | Value
-|-


### `HugeMushroomBlock::Type`
Name | Value
-|-


### `HardcodedSpawnAreaType`
Name | Value
-|-


### `HTTPResponse::Status`
Name | Value
-|-


### `HolographicPlatform::MCLocation`
```
enum HolographicPlatform::MCLocation : __int32
{
  Pose = 0x0,
  FocusScreen = 0x1,
  Holoviewer = 0x2,
  Reality = 0x3,
  Logo = 0x4,
  EnvironmentScan = 0x5,
};

```

### `HolographicPlatform::GestureMode`
```
enum HolographicPlatform::GestureMode : __int32
{
  Disabled = 0x0,
  Pan = 0x1,
  Rotate = 0x2,
  Tilt = 0x3,
  Pivot = 0x4,
  Zoom = 0x5,
  GazeOffset = 0x6,
  Joystick = 0x7,
  Abstract = 0x8,
};

```

### `HolographicPlatform::HolographicFeatures`
```
enum HolographicPlatform::HolographicFeatures : __int32
{
  LivingRoomFeature = 0x1,
  HoloViewerFeature = 0x2,
  HoloScreenFeature = 0x4,
  VirtualRealityFeature = 0x8,
  RealityModeFeature = 0x10,
  TransitionInsideBlocksEnabled = 0x20,
  HeadInsideBlocksEnabled = 0x40,
  GazeOverridesMouse = 0x80,
  MouseEnabled = 0x100,
  PauseMenuOnFocusLostDisabled = 0x200,
  FilePickingSupported = 0x400,
  ImagePickingSupported = 0x800,
  RollTurningSupported = 0x1000,
  IsRecenterable = 0x2000,
  HandControllersEnabled = 0x4000,
};

```

### `HolographicPlatform::AimFromSpace`
```
enum HolographicPlatform::AimFromSpace : __int32
{
  Gaze = 0x0,
  LeftHand = 0x1,
  RightHand = 0x2,
};

```

### `hbui::RoutePrerequisiteState`
```
enum hbui::RoutePrerequisiteState : __int32
{
  InvalidInput_Route = 0x0,
  RouteHasNoPrerequisites = 0x1,
  AllConditionsMet_NoFurtherActionsNeeded = 0x2,
  ConditionsNotMet_NewScreenPushed = 0x3,
};

```

### `hbui::RouterAction`
```
typedef hbui::Router::QueuedRouteAction hbui::RouterAction;

```

### `HandlerResult`
```
enum HandlerResult : __int32
{
  BypassListeners = 0x0,
  NotifyListeners = 0x1,
};

```

### `hbui::Scene::ScreenState`
```
typedef cg::ColorSpace hbui::Scene::ScreenState;

```

### `HttpHeaders::ParseState`
```
enum HttpHeaders::ParseState : __int32
{
  PS_PROCESS_STATUS_LINE = 0x0,
  PS_STATUS_LINE_DONE = 0x1,
  PS_NEW_FIELD = 0x2,
  PS_NAME = 0x3,
  PS_VALUE = 0x4,
  PS_ADD_FIELD = 0x5,
  PS_PROCESS_FIELDS = 0x6,
  PS_DONE = 0x7,
  PS_ABORT = 0x8,
};

```

### `hbui::ResourceRegistry::RegisterResult`
```
typedef IMinecraftEventing::AuthenticationOutcome hbui::ResourceRegistry::RegisterResult;

```

### `hbui::ScreenScope`
```
typedef Rotation hbui::ScreenScope;

```

### `HudCameraRenderer::State`
```
typedef Rotation HudCameraRenderer::State;

```

### `hbui::AchievementsFacet::AchievementFacetStatus`
```
typedef Actor::InitializationMethod hbui::AchievementsFacet::AchievementFacetStatus;

```

### `hbui::DeviceInformationFacet::Platform`
```
typedef VRControllerType hbui::DeviceInformationFacet::Platform;

```

### `hbui::InputMethod`
```
typedef VRControllerType hbui::InputMethod;

```

### `hbui::ScreenReaderFacetInterruptibleFlag`
```
enum hbui::ScreenReaderFacetInterruptibleFlag : __int32
{
  NotInterruptible = 0x0,
  Interruptible = 0x1,
};

```

### `hbui::ScreenReaderFacetRequiredFlag`
```
typedef FilterParamRequirement hbui::ScreenReaderFacetRequiredFlag;

```

### `hbui::ScreenReaderFacetPlayInBackgroundFlag`
```
enum hbui::ScreenReaderFacetPlayInBackgroundFlag : __int32
{
  DoNotPlayInBackground = 0x0,
  PlayInBackground = 0x1,
};

```

### `hbui::IFacetRegistry::Error`
```
enum hbui::IFacetRegistry::Error : __int32
{
  ALREADY_ACTIVE = 0x0,
  ALREADY_INACTIVE = 0x1,
  ACTIVATE_NOT_FOUND = 0x2,
  DEACTIVATE_NOT_FOUND = 0x3,
};

```

### `hbui::TouchEventData::EventType`
```
enum hbui::TouchEventData::EventType : __int32
{
  TouchMove = 0x0,
  TouchDown = 0x1,
  TouchUp = 0x2,
};

```

### `hbui::GestureEventData::EventType`
```
typedef cg::ColorSpace hbui::GestureEventData::EventType;

```

### `hbui::GestureRecognizerBase::GestureRecognizerState`
```
enum hbui::GestureRecognizerBase::GestureRecognizerState : __int32
{
  Possible = 0x0,
  Began = 0x1,
  CanceledOrDone = 0x2,
  Recognized = 0x3,
  RecognizedAndStillRecognizing = 0x4,
};

```

### `hbui::WebApiButton`
```
enum hbui::WebApiButton : __int8
{
  A_BUTTON = 0x0,
  B_BUTTON = 0x1,
  X_BUTTON = 0x2,
  Y_BUTTON = 0x3,
  DPAD_UP = 0xC,
  DPAD_DOWN = 0xD,
  DPAD_LEFT = 0xE,
  DPAD_RIGHT = 0xF,
  LEFT_STICK = 0xA,
  RIGHT_STICK = 0xB,
  LEFT_SHOULDER = 0x4,
  RIGHT_SOULDER = 0x5,
  BACK_BUTTON = 0x8,
  START_BUTTON = 0x9,
  HEADSET_TAP = 0x10,
  GENERIC_BUTTON_1 = 0x11,
  GENERIC_BUTTON_2 = 0x12,
  GENERIC_BUTTON_3 = 0x13,
  GENERIC_BUTTON_4 = 0x14,
  GENERIC_BUTTON_5 = 0x15,
  GENERIC_BUTTON_6 = 0x16,
  GENERIC_BUTTON_7 = 0x17,
  GENERIC_BUTTON_8 = 0x18,
  GENERIC_BUTTON_9 = 0x19,
  GENERIC_BUTTON_10 = 0x1A,
  GENERIC_BUTTON_11 = 0x1B,
  GENERIC_BUTTON_12 = 0x1C,
  GENERIC_BUTTON_13 = 0x1D,
  GENERIC_BUTTON_14 = 0x1E,
  GENERIC_BUTTON_15 = 0x1F,
};

```

### `hbui::GamepadButtonState`
```
typedef GameControllerButtonState hbui::GamepadButtonState;

```

### `HostOptionStates`
```
typedef Rotation HostOptionStates;

```

### `HandleRangeResult`
```
typedef ButtonHandleResult HandleRangeResult;

```

### `HorseFlags`
```
enum HorseFlags : __int32
{
  FLAG_SADDLE = 0x4,
  FLAG_BRED = 0x10,
  FLAG_EATING = 0x20,
  FLAG_STANDING = 0x40,
  FLAG_OPEN_MOUTH = 0x80,
};

```

### `HorseType`
```
enum HorseType : __int32
{
  TYPE_UNSET = 0xFFFFFFFF,
  TYPE_HORSE = 0x0,
  TYPE_DONKEY = 0x1,
  TYPE_MULE = 0x2,
  TYPE_UNDEAD = 0x3,
  TYPE_SKELETON = 0x4,
  TYPE_COUNT = 0x5,
};

```

### `HorseVariant`
```
enum HorseVariant : __int32
{
  VARIANT_WHITE = 0x0,
  VARIANT_CREAMY = 0x1,
  VARIANT_CHESTNUT = 0x2,
  VARIANT_BROWN = 0x3,
  VARIANT_BLACK = 0x4,
  VARIANT_GRAY = 0x5,
  VARIANT_DARKBROWN = 0x6,
  VARIANT_COUNT = 0x7,
};

```

### `HorseMarkings`
```
enum HorseMarkings : __int32
{
  MARKING_NONE = 0x0,
  MARKING_WHITE_DETAILS = 0x1,
  MARKING_WHITE_FIELDS = 0x2,
  MARKING_WHITE_DOTS = 0x3,
  MARKING_BLACK_DOTS = 0x4,
  MARKING_COUNT = 0x5,
};

```

### `HatchLevel`
```
typedef VRControllerType HatchLevel;

```

### `HurtByType`
```
typedef Direction::Type HurtByType;

```

### `HorseInventoryEnum`
```
enum HorseInventoryEnum : __int32
{
  INV_SLOT_SADDLE = 0x0,
  INV_SLOT_ARMOR = 0x1,
  INV_BASE_COUNT = 0x2,
};

```

### `HorseIds`
```
enum HorseIds : __int32
{
  DATA_ID_HORSE_FLAGS = 0x10,
  DATA_ID_TYPE = 0x13,
  DATA_ID_TYPE_VARIANT = 0x14,
  DATA_ID_OWNER_UUID = 0x15,
};

```

### `HorseTabIndex`
```
typedef Rotation HorseTabIndex;

```

### `HarvestFarmBlockGoal::Task`
```
typedef ActorEvent HarvestFarmBlockGoal::Task;

```

