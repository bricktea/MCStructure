# G
### `glTF::Primitive::ComponentType`
Name | Value
-|-
BYTE | `5120`
UNSIGNED_BYTE | `5121`
SHORT | `5122`
UNSIGNED_SHORT | `5123`
FLOAT | `5126`


### `glTF::Accessor::Type`
Name | Value
-|-
SCALAR | `0`
VEC2 | `1`
VEC3 | `2`
VEC4 | `3`
MAT2 | `4`
MAT3 | `5`
MAT4 | `6`


### `GameType`
Name | Value
-|-


### `GeneratorType`
Name | Value
-|-


### `GameRule::Type`
Name | Value
-|-


### `GameModuleClient::ResourceLoadingPhase`
Name | Value
-|-
AppStartup | `0`
Frontend | `1`
InGame | `2`


### `GamePlayTipId`
Name | Value
-|-
SHOW_CAMERA_TIP | `0`
SHOW_MOVE_TIP | `1`
SHOW_JUMP_TIP | `2`
SHOW_JUMP_FORWARD_TIP | `3`
SHOW_FIND_A_TREE_TIP | `4`
SHOW_BREAK_A_WOOD_TIP | `5`
SHOW_OPEN_INVENTORY_TIP | `6`
SHOW_NEED_MORE_MATERIALS_TIP | `7`
SHOW_SELECT_CRAFTTABLE_IN_HOTBAR_TIP | `8`
SHOW_PLACE_CRAFTING_TABLE_TIP | `9`
SHOW_USE_CRAFTING_TABLE_TIP | `10`
SHOW_SELECT_PICKAXE_IN_HOTBAR_TIP | `11`
SHOW_HINTS_DONE_TIP | `12`


### `glTF::Image::ImageMimeType`
Name | Value
-|-
PNG | `0`


### `glTF::Texture::Format`
Name | Value
-|-
ALPHA | `6406`
RGB | `6407`
RGBA | `6408`
LUMINANCE | `6409`
LUMINANCE_ALPHA | `6410`


### `glTF::Texture::Target`
Name | Value
-|-
TEXTURE_2D | `3553`


### `glTF::Texture::Type`
Name | Value
-|-


### `glTF::Material::AlphaMode`
Name | Value
-|-
OPAQUE_MODE | `0`
MASK | `1`
BLEND | `2`


### `glTF::Mesh::Primitive::Mode`
Name | Value
-|-
POINT | `0`
LINES | `1`
LINE_LOOP | `2`
LINE_STRIP | `3`
TRIANGLES | `4`
TRIANGLE_STRIP | `5`
TRIANGLE_FAN | `6`


### `GGInput::Event`
Name | Value
-|-
VECTOR_GAZE_RAW_POSITION | `0`
VECTOR_GAZE_RAW_DIRECTION | `1`
VECTOR_GAZE_RAW_DELTA_POS | `2`
VECTOR_GAZE_RAW_DELTA_DIR | `3`
VECTOR_GAZE_HOLOSCREEN_POSITION | `4`
VECTOR_GAZE_HOLOSCREEN_DIRECTION | `5`
VECTOR_GAZE_HOLOVIEWER_POSITION | `6`
VECTOR_GAZE_HOLOVIEWER_DIRECTION | `7`
VECTOR_HAND1_WORLD_POSITION | `8`
VECTOR_HAND1_WORLD_DELTA_POS | `9`
VECTOR_HAND2_WORLD_POSITION | `10`
VECTOR_HAND2_WORLD_DELTA_POS | `11`
VECTOR_EVENTS_END | `12`
GESTURE_HAND_DETECTED | `13`
GESTURE_HAND_LOST | `14`
GESTURE_FINGER_PRESSED | `15`
GESTURE_FINGER_RELEASED | `16`
GESTURE_HAND_TAP | `17`
GESTURE_HAND_CIRCLE | `18`
GESTURE_HAND_SWIPE_LEFT | `19`
GESTURE_HAND_SWIPE_RIGHT | `20`
GESTURE_EVENTS_END | `21`


### `GameControllerButtonState`
Name | Value
-|-


### `glm::ctor`
```
enum glm::ctor : __int32
{
  uninitialize = 0x0,
};

```

### `GameRules::GameRulesIndex`
```
enum GameRules::GameRulesIndex : __int32
{
  INVALID_GAME_RULE = 0xFFFFFFFF,
  COMMAND_BLOCK_OUTPUT = 0x0,
  DO_DAYLIGHT_CYCLE = 0x1,
  DO_ENTITY_DROPS = 0x2,
  DO_FIRE_TICK = 0x3,
  DO_MOB_LOOT = 0x4,
  DO_MOB_SPAWNING = 0x5,
  DO_TILE_DROPS = 0x6,
  DO_WEATHER_CYCLE = 0x7,
  DROWNING_DAMAGE = 0x8,
  FALL_DAMAGE = 0x9,
  FIRE_DAMAGE = 0xA,
  KEEP_INVENTORY = 0xB,
  MOB_GRIEFING = 0xC,
  PVP = 0xD,
  SHOW_COORDINATES = 0xE,
  DO_NATURAL_REGENERATION = 0xF,
  DO_TNT_EXPLODE = 0x10,
  SEND_COMMAND_FEEDBACK = 0x11,
  MAX_COMMAND_CHAIN_LENGTH = 0x12,
  DO_INSOMNIA = 0x13,
  COMMAND_BLOCKS_ENABLED = 0x14,
  RANDOM_TICK_SPEED = 0x15,
  DO_IMMEDIATE_RESPAWN = 0x16,
  SHOW_DEATH_MESSAGES = 0x17,
  FUNCTION_COMMAND_LIMIT = 0x18,
  PLAYER_SPAWN_RADIUS = 0x19,
  SHOW_TAGS = 0x1A,
  VANILLA_GAME_RULE_COUNT = 0x1B,
  GLOBAL_MUTE = 0x1B,
  ALLOW_DESTRUCTIVE_OBJECTS = 0x1C,
  ALLOW_MOBS = 0x1D,
  CODE_BUILDER = 0x1E,
  EDU_GAME_RULE_COUNT = 0x1F,
};

```

### `glm::precision`
```
enum glm::precision : __int32
{
  packed_highp = 0x0,
  packed_mediump = 0x1,
  packed_lowp = 0x2,
  aligned_highp = 0x3,
  aligned_mediump = 0x4,
  aligned_lowp = 0x5,
  aligned = 0x3,
  highp = 0x0,
  mediump = 0x1,
  lowp = 0x2,
  packed = 0x0,
  defaultp = 0x0,
};

```

### `GameVersion::Octet`
```
typedef Actor::InitializationMethod GameVersion::Octet;

```

### `GameControllerErrorType`
```
enum GameControllerErrorType : __int8
{
  NoError = 0x0,
  ControllerRequired = 0x1,
  InvalidConfiguration = 0x2,
  AdhocOverWirelessConnectionLimit = 0x3,
  AdhocInvalidConfiguration = 0x4,
};

```

### `GameUserType`
```
typedef Rotation GameUserType;

```

### `glm::detail::is_int<unsigned __int64>::test`
```
typedef moodycamel::details::static_is_lock_free_num<long>::<unnamed_enum_value> glm::detail::is_int<unsigned __int64>::test;

```

### `glm::detail::is_int<int>::test`
```
typedef moodycamel::details::static_is_lock_free_num<long>::<unnamed_enum_value> glm::detail::is_int<int>::test;

```

### `glm::detail::is_int<__int64>::test`
```
typedef moodycamel::details::static_is_lock_free_num<long>::<unnamed_enum_value> glm::detail::is_int<__int64>::test;

```

### `glm::detail::is_int<unsigned int>::test`
```
typedef moodycamel::details::static_is_lock_free_num<long>::<unnamed_enum_value> glm::detail::is_int<unsigned int>::test;

```

### `glTF::Sampler::MagFilter`
```
enum glTF::Sampler::MagFilter : __int32
{
  NEAREST = 0x2600,
  LINEAR = 0x2601,
};

```

### `glTF::Sampler::MinFilter`
```
typedef glTF::Sampler::MagFilter glTF::Sampler::MinFilter;

```

### `glTF::Sampler::WrapS`
```
enum glTF::Sampler::WrapS : __int32
{
  CLAMP_TO_EDGE = 0x812F,
  MIRRORED_REPEAT = 0x8370,
  REPEAT = 0x2901,
};

```

### `glTF::Sampler::WrapT`
```
typedef glTF::Sampler::WrapS glTF::Sampler::WrapT;

```

### `glTF::Shader::Type`
```
enum glTF::Shader::Type : __int32
{
  FRAGMENT_SHADER = 0x8B30,
  VERTEX_SHADER = 0x8B31,
};

```

### `GuiMessage::MessageType`
```
typedef Rotation GuiMessage::MessageType;

```

### `GameControllerStickState`
```
typedef Lockless::MemoryOrder GameControllerStickState;

```

### `GameConnectionType`
```
typedef RealmsEnvironment GameConnectionType;

```

### `GameStore::State`
```
typedef ClientInstanceState GameStore::State;

```

### `GradientRenderer::GradientDirection`
```
typedef MinecraftEventing::SplitScreenMode GradientRenderer::GradientDirection;

```

### `GameControllerEventType`
```
enum GameControllerEventType : __int32
{
  ButtonEvent = 0x0,
  StickEvent = 0x1,
  TriggerEvent = 0x2,
  JoinGameEvent = 0x3,
  ChangeUserEvent = 0x4,
  ConnectionStateChangeEvent = 0x5,
};

```

### `GamePlayTipStatus`
```
typedef InventoryTipStatus GamePlayTipStatus;

```

### `GeneralMultiplayerWarningState`
```
typedef Rotation GeneralMultiplayerWarningState;

```

### `glm::detail::is_int<float>::test`
```
typedef moodycamel::details::static_is_lock_free_num<long>::<unnamed_enum_value> glm::detail::is_int<float>::test;

```

### `GrindstoneScreenController::SlotIndex`
```
typedef AnvilScreenController::SlotIndex GrindstoneScreenController::SlotIndex;

```

### `GX_TupleCountFlags_`
```
enum GX_TupleCountFlags_ : __int32
{
  GX_TC_TUPLES_SHARE_POINT_NUMBERS = 0x8000,
  GX_TC_RESERVED_TUPLE_FLAGS = 0x7000,
  GX_TC_TUPLE_COUNT_MASK = 0xFFF,
};

```

### `GX_TupleIndexFlags_`
```
enum GX_TupleIndexFlags_ : __int32
{
  GX_TI_EMBEDDED_TUPLE_COORD = 0x8000,
  GX_TI_INTERMEDIATE_TUPLE = 0x4000,
  GX_TI_PRIVATE_POINT_NUMBERS = 0x2000,
  GX_TI_RESERVED_TUPLE_FLAG = 0x1000,
  GX_TI_TUPLE_INDEX_MASK = 0xFFF,
};

```

