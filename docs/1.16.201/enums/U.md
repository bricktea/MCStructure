# U
### `ui::ChildInsertPosition`
Name | Value
-|-
Right | `0`
Left | `1`
Bottom | `2`
Top | `3`
Back | `4`
Front | `5`
NumFrustumPlanes | `6`


### `ui::OrientationType`
Name | Value
-|-
Vertical | `1`
Horizontal | `2`


### `UpdateVersionScreenContext`
Name | Value
-|-
UpdateClientPrompt | `0`
StoreNotSupported | `1`


### `ui::TextAlignment`
Name | Value
-|-


### `ui::LayoutAxisOffsetContainerType`
Name | Value
-|-


### `ui::CardinalDirection`
Name | Value
-|-


### `ui::LayoutAxisOperation`
Name | Value
-|-


### `ui::NameResolutionScope`
Name | Value
-|-


### `ui::DirtyFlag`
Name | Value
-|-


### `UIBatchType`
Name | Value
-|-


### `UIOperation`
Name | Value
-|-


### `UseAnimation`
Name | Value
-|-


### `Util::XXHash::XXH_errorcode`
```
enum Util::XXHash::XXH_errorcode : __int32
{
  XXH_OK = 0x0,
  XXH_ERROR = 0x1,
};

```

### `Util::XXHash::XXH_endianess`
```
enum Util::XXHash::XXH_endianess : __int32
{
  XXH_bigEndian = 0x0,
  XXH_littleEndian = 0x1,
};

```

### `Util::XXHash::XXH_alignment`
```
enum Util::XXHash::XXH_alignment : __int32
{
  XXH_aligned = 0x0,
  XXH_unaligned = 0x1,
};

```

### `UIRenderMode`
```
enum UIRenderMode : __int8
{
  ToScreen = 0x0,
  ToTexture = 0x1,
  VROverlay = 0x2,
};

```

### `ui::GameEventNotification`
```
enum ui::GameEventNotification : __int32
{
  Empty = 0x0,
  PlayerDeath = 0x1,
  PlayerListChanged = 0x2,
  PlayerSignedIn = 0x3,
  PlayerSignedOut = 0x4,
  PlayerDisconnected = 0x5,
  NewMessage = 0x6,
  NewConsoleMessage = 0x7,
  ResourcePackConfirmation = 0x8,
  ResourcePackDownloadFinished = 0x9,
  PlayerExperienceChanged = 0xA,
  TitleChanged = 0xB,
  SubtitleChanged = 0xC,
  ServerSettingsChanged = 0xD,
  ActionBarMessageChanged = 0xE,
  StoreUpdated = 0xF,
  StoreSalesUpdated = 0x10,
  LanguageChanged = 0x11,
  ScreenPushed = 0x12,
  ScreenPopped = 0x13,
  SavingStart = 0x14,
  SavingFinished = 0x15,
  StructureRendered = 0x16,
  StructureNotRendered = 0x17,
  VoiceBegin = 0x18,
  VoiceEnd = 0x19,
  RnClosed = 0x1A,
  VoiceRecordFinish = 0x1B,
  VoiceUploadFinish = 0x1C,
  VoiceTranslatedFinish = 0x1D,
  VoiceRequestPermission = 0x1E,
  AnimationsEnabledChanged = 0x1F,
  CurrencyPurchaseMinecoinPackFound = 0x20,
  NewContentLogMessage = 0x21,
  NewPerfTurtleMessage = 0x22,
  IdentityGained = 0x23,
  PersonaSynced = 0x24,
  StructureDataExportSuccess = 0x25,
  StructureDataExportFailed = 0x26,
  StructureDataQuerySuccess = 0x27,
  StructureDataQueryFailed = 0x28,
  WebviewDismissed = 0x29,
  EntitlementsChanged = 0x2A,
  PlayerRespawnBlocked = 0x2B,
  PlayerReadyToRespawn = 0x2C,
  FilteredTextReady = 0x2D,
};

```

### `ui::SceneType`
```
typedef ActorEvent ui::SceneType;

```

### `UIProfile`
```
typedef VRCameraMovement UIProfile;

```

### `UIScalingRules`
```
enum UIScalingRules : __int32
{
  Desktop = 0x0,
  PocketApple = 0x1,
  PocketAndroid = 0x2,
  PocketWindows = 0x3,
  Console = 0x4,
  HandheldConsole = 0x5,
};

```

### `ui::VisibilityFlag`
```
typedef Rotation ui::VisibilityFlag;

```

### `ui::FontSize`
```
enum ui::FontSize : __int32
{
  Small = 0x0,
  Normal = 0x1,
  Large = 0x2,
  ExtraLarge = 0x3,
};

```

### `UpnpState`
```
typedef TransformSpace UpnpState;

```

### `UIMessage`
```
enum UIMessage : __int32
{
  SET_SCROLL_VIEW_POS = 0x0,
  SET_SCROLL_VIEW_PLAY_NEW_PAGE_AMINATION = 0x1,
  EDIT_APPEND_TEXT = 0x2,
};

```

### `UIDebugCommandFeature`
```
enum UIDebugCommandFeature : __int8
{
};

```

### `ui::ViewRequest`
```
typedef Rotation ui::ViewRequest;

```

### `ui::ClipDirection`
```
typedef Rotation ui::ClipDirection;

```

### `UploadState`
```
typedef TaskRunResult UploadState;

```

### `UIDefType`
```
typedef PlayerPermissionLevel UIDefType;

```

### `ui::LayoutAxisType`
```
typedef Rotation ui::LayoutAxisType;

```

### `ui::AnchorPoint`
```
typedef SplitScreenPosition ui::AnchorPoint;

```

### `ui::AnimationType`
```
typedef cg::ColorSpace ui::AnimationType;

```

### `ui::Draggable`
```
typedef MinecraftEventing::SplitScreenMode ui::Draggable;

```

### `ui::TileDirection`
```
typedef Rotation ui::TileDirection;

```

### `Util::NumberConversionResult`
```
typedef TransformSpace Util::NumberConversionResult;

```

### `Urho3D::Intersection`
```
enum Urho3D::Intersection : __int32
{
  OUTSIDE = 0x0,
  INTERSECTS = 0x1,
  INSIDE = 0x2,
};

```

### `Urho3D::EmitDirType`
```
enum Urho3D::EmitDirType : __int32
{
  EMIT_INWARDS = 0x0,
  EMIT_OUTWARDS = 0x1,
  EMIT_DIRECTION = 0x2,
};

```

### `Urho3D::EmitterType`
```
enum Urho3D::EmitterType : __int32
{
  EMITTER_SPHERE = 0x0,
  EMITTER_HEMISPHERE = 0x1,
  EMITTER_CYLINDER = 0x2,
  EMITTER_BOX = 0x3,
  EMITTER_CONE = 0x4,
};

```

### `Urho3D::FaceCameraMode`
```
enum Urho3D::FaceCameraMode : __int32
{
  FC_NONE = 0x0,
  FC_ROTATE_XYZ = 0x1,
  FC_ROTATE_Y = 0x2,
  FC_LOOKAT_XYZ = 0x3,
  FC_LOOKAT_Y = 0x4,
  FC_LOOKAT_MIXED = 0x5,
  FC_DIRECTION = 0x6,
  FC_DIRECTION_HORIZONTAL = 0x7,
  FC_HORIZONTAL = 0x8,
  FC_AXIS_X = 0x9,
  FC_AXIS_Y = 0xA,
  FC_AXIS_Z = 0xB,
};

```

### `Urho3D::AutoRemoveMode`
```
enum Urho3D::AutoRemoveMode : __int32
{
  REMOVE_DISABLED = 0x0,
  REMOVE_COMPONENT = 0x1,
  REMOVE_NODE = 0x2,
};

```

### `Urho3D::CullType`
```
enum Urho3D::CullType : __int32
{
  RNDER = 0x0,
  TICK = 0x1,
};

```

### `uicontrolid_t<UIComponent>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType uicontrolid_t<UIComponent>::NewIDType;

```

### `Urho3D::ModelRenderLayer`
```
enum Urho3D::ModelRenderLayer : __int32
{
  Opaque = 0x1,
  Blend = 0x2,
  Bloom = 0x4,
};

```

### `UIMaterialType`
```
typedef Rotation UIMaterialType;

```

### `Urho3D::ModelRenderType`
```
typedef glTF::Texture::Format Urho3D::ModelRenderType;

```

### `ui::AnimationStatus`
```
typedef cg::ColorSpace ui::AnimationStatus;

```

### `UIAnim::State`
```
enum UIAnim::State : __int32
{
  Running = 0x0,
  Waiting = 0x1,
};

```

### `UIAnimationController::tickType`
```
typedef VRHUDPosition UIAnimationController::tickType;

```

### `UIAnimLayout::ApplyTo`
```
enum UIAnimLayout::ApplyTo : __int32
{
  Offset = 0x0,
  Size = 0x1,
};

```

### `UploadError`
```
typedef Rotation UploadError;

```

### `UIPackErrorType`
```
typedef Rotation UIPackErrorType;

```

### `UDPProxyMessages`
```
enum UDPProxyMessages : __int32
{
  ID_UDP_PROXY_FORWARDING_SUCCEEDED = 0x0,
  ID_UDP_PROXY_FORWARDING_NOTIFICATION = 0x1,
  ID_UDP_PROXY_NO_SERVERS_ONLINE = 0x2,
  ID_UDP_PROXY_RECIPIENT_GUID_NOT_CONNECTED_TO_COORDINATOR = 0x3,
  ID_UDP_PROXY_ALL_SERVERS_BUSY = 0x4,
  ID_UDP_PROXY_IN_PROGRESS = 0x5,
  ID_UDP_PROXY_FORWARDING_REQUEST_FROM_CLIENT_TO_COORDINATOR = 0x6,
  ID_UDP_PROXY_PING_SERVERS_FROM_COORDINATOR_TO_CLIENT = 0x7,
  ID_UDP_PROXY_PING_SERVERS_REPLY_FROM_CLIENT_TO_COORDINATOR = 0x8,
  ID_UDP_PROXY_FORWARDING_REQUEST_FROM_COORDINATOR_TO_SERVER = 0x9,
  ID_UDP_PROXY_FORWARDING_REPLY_FROM_SERVER_TO_COORDINATOR = 0xA,
  ID_UDP_PROXY_LOGIN_REQUEST_FROM_SERVER_TO_COORDINATOR = 0xB,
  ID_UDP_PROXY_LOGIN_SUCCESS_FROM_COORDINATOR_TO_SERVER = 0xC,
  ID_UDP_PROXY_ALREADY_LOGGED_IN_FROM_COORDINATOR_TO_SERVER = 0xD,
  ID_UDP_PROXY_NO_PASSWORD_SET_FROM_COORDINATOR_TO_SERVER = 0xE,
  ID_UDP_PROXY_WRONG_PASSWORD_FROM_COORDINATOR_TO_SERVER = 0xF,
};

```

### `Util::Url::QueryParametersParsingToken`
```
enum Util::Url::QueryParametersParsingToken : __int32
{
  Key = 0x0,
  Value = 0x1,
};

```

### `Util::removeAllColorCodes::__l2::RemoveAllColorCodesState`
```
enum Util::removeAllColorCodes::__l2::RemoveAllColorCodesState : __int32
{
  Output = 0x0,
  SawCodeByte1 = 0x1,
  SawCodeByte2 = 0x2,
};

```

