# I
### `InputMode`
Name | Value
-|-


### `IconBlitGlint`
Name | Value
-|-
NoGlint | `0`
Glint | `1`
UnGlint | `2`


### `ItemContextFlags`
Name | Value
-|-


### `IMinecraftEventing::PurchaseResult`
Name | Value
-|-
Started | `0`
Completed | `1`
Canceled | `2`
Error | `3`


### `IMinecraftEventing::PromotionType`
Name | Value
-|-


### `IMinecraftEventing::StoreType`
Name | Value
-|-


### `IMinecraftEventing::SignInStage`
Name | Value
-|-


### `IMinecraftEventing::EducationLessonAction`
Name | Value
-|-
Start | `0`
Continue | `1`
Restart | `2`
Host | `3`
Join | `4`
Finish | `5`


### `IntellisenseUtils::MatcherOptions`
Name | Value
-|-


### `ItemAcquisitionMethod`
Name | Value
-|-


### `ItemColor`
Name | Value
-|-


### `IsMissingTexture`
Name | Value
-|-
Yes | `0`
No | `1`


### `ItemUseInventoryTransaction::ActionType`
Name | Value
-|-


### `InventoryTipId`
Name | Value
-|-
SHOW_SELECTWOOD_FOR_MAKEPLANK_TIP | `0`
SHOW_SELECTGRID_FOR_MAKEPLANK_TIP | `1`
SHOW_SELECT_OUTPUTSLOT_FOR_PLANK_TIP | `2`
SHOW_SELECT_INVENTORY_FOR_PLANK_TIP | `3`
SHOW_OPEN_RECIPE_BOOK | `4`
SHOW_MAKE_CRAFTING_TABLE | `5`
SHOW_SELECT_OUTPUTSLOT_CRAFTING_TABLE | `6`
SHOW_SELECT_HOTBAR_CRAFTING_TABLE | `7`
SHOW_CLOSE_INVENTORY | `8`
SHOW_NEED_PLANKS_AND_STICKS | `9`
SHOW_OPEN_SEARCH_TAB | `10`
SHOW_SELECT_WOODEN_PICKAXE | `11`
SHOW_SELECT_OUTPUTSLOT_FOR_WOODEN_PICKAXE | `12`
SHOW_SELECT_HOTBAR_WOODEN_PICKAXE | `13`


### `InventoryTipStatus`
Name | Value
-|-
TIP_AVAILABLE | `0`
TIP_HIDDEN | `1`
TIP_IS_VISIBLE | `2`
TIP_COMPLETED | `3`


### `IMinecraftEventing::RealmConnectionFlow`
Name | Value
-|-
PlayScreen | `0`
PauseScreen | `1`


### `IMinecraftEventing::RealmConnectionResult`
Name | Value
-|-
Success | `0`
Failed | `1`
AccountRequired | `2`


### `IFileChunkUploader::UploadStatus`
Name | Value
-|-
Initialized | `0`
ArchivingStarted | `1`
ArchivingFailed | `2`
ArchivingSucceeded | `3`
UploadFailed | `4`
ValidationStarted | `5`
ValidationProgress | `6`
ValidationFailed | `7`
ValidationCancelled | `8`
ValidationSucceeded | `9`
UnknownError | `10`


### `IFileChunkUploader::UploadStreamResult`
Name | Value
-|-


### `InventorySourceType`
Name | Value
-|-
ContainerInventory | `0`
GlobalInventory | `1`
WorldInteraction | `2`
CreativeInventory | `3`
NonImplementedFeatureTODO | `99999`
InvalidInventory | `18446744073709551615`


### `InventorySource::InventorySourceFlags`
Name | Value
-|-
NoFlag | `0`
WorldInteraction_Random | `1`


### `ItemCreativeRegistrationMode`
Name | Value
-|-


### `ItemTransferAmount::ItemTransferAmountTag`
Name | Value
-|-
RequestAmount | `0`
TakeType | `1`
PlaceType | `2`


### `ItemTakeType`
Name | Value
-|-
All | `0`
One | `1`


### `ItemPlaceType`
Name | Value
-|-


### `IF_OPER_STATUS`
Name | Value
-|-
IfOperStatusUp | `1`
IfOperStatusDown | `2`
IfOperStatusTesting | `3`
IfOperStatusUnknown | `4`
IfOperStatusDormant | `5`
IfOperStatusNotPresent | `6`
IfOperStatusLowerLayerDown | `7`


### `InputEventType`
Name | Value
-|-
Button | `0`
OnClose | `1`


### `InputBindingMode`
Name | Value
-|-


### `ISA_AVAILABILITY`
```
enum ISA_AVAILABILITY : __int32
{
  __ISA_AVAILABLE_X86 = 0x0,
  __ISA_AVAILABLE_SSE2 = 0x1,
  __ISA_AVAILABLE_SSE42 = 0x2,
  __ISA_AVAILABLE_AVX = 0x3,
  __ISA_AVAILABLE_ENFSTRG = 0x4,
  __ISA_AVAILABLE_AVX2 = 0x5,
  __ISA_AVAILABLE_ARMNT = 0x0,
  __ISA_AVAILABLE_NEON = 0x1,
  __ISA_AVAILABLE_NEON_ARM64 = 0x2,
};

```

### `ItemUseMethod`
```
typedef cg::ColorSpace ItemUseMethod;

```

### `IMinecraftEventing::ConnectionFailureReason`
```
typedef cg::ColorSpace IMinecraftEventing::ConnectionFailureReason;

```

### `IMinecraftEventing::SignInAccountType`
```
typedef cg::ColorSpace IMinecraftEventing::SignInAccountType;

```

### `IMinecraftEventing::SignInTrigger`
```
typedef cg::ColorSpace IMinecraftEventing::SignInTrigger;

```

### `IMinecraftEventing::DeviceAccountFailurePhase`
```
typedef cg::ColorSpace IMinecraftEventing::DeviceAccountFailurePhase;

```

### `IMinecraftEventing::EduSignInStage`
```
typedef cg::ColorSpace IMinecraftEventing::EduSignInStage;

```

### `IMinecraftEventing::NetworkType`
```
typedef RealmsEnvironment IMinecraftEventing::NetworkType;

```

### `IMinecraftEventing::FileTransmissionDirection`
```
enum IMinecraftEventing::FileTransmissionDirection : __int32
{
  Download = 0x0,
  Upload = 0x1,
};

```

### `IMinecraftEventing::FileTransmissionState`
```
typedef Bedrock::Threading::AsyncStatus IMinecraftEventing::FileTransmissionState;

```

### `IMinecraftEventing::FileTransmissionType`
```
enum IMinecraftEventing::FileTransmissionType : __int32
{
  Realm_file = 0x1,
  Dlc = 0x2,
  Remix3D_DEPRECATED = 0x3,
  DlcUpdate_Auto = 0x4,
  DlcUpdate_User = 0x5,
};

```

### `IMinecraftEventing::PurchaseStage`
```
typedef cg::ColorSpace IMinecraftEventing::PurchaseStage;

```

### `IMinecraftEventing::ShareMode`
```
enum IMinecraftEventing::ShareMode : __int32
{
  Share = 0x1,
  Copy = 0x2,
};

```

### `IMinecraftEventing::AuthenticationOutcome`
```
enum IMinecraftEventing::AuthenticationOutcome : __int32
{
  Success = 0x0,
  Failed = 0x1,
  AccountRequired = 0x2,
};

```

### `IMinecraftEventing::ExportOutcome`
```
typedef IMinecraftEventing::AuthenticationOutcome IMinecraftEventing::ExportOutcome;

```

### `IMinecraftEventing::ExportStage`
```
typedef Bedrock::Threading::AsyncStatus IMinecraftEventing::ExportStage;

```

### `IMinecraftEventing::ServerConnectionOutcome`
```
typedef IMinecraftEventing::AuthenticationOutcome IMinecraftEventing::ServerConnectionOutcome;

```

### `IMinecraftEventing::ClubsFeedScreenSource`
```
enum IMinecraftEventing::ClubsFeedScreenSource : __int32
{
  PlayScreen = 0x0,
  PauseScreen = 0x1,
};

```

### `IMinecraftEventing::ClubsEngagementAction`
```
enum IMinecraftEventing::ClubsEngagementAction : __int32
{
  Like = 0x0,
  Unlike = 0x1,
  Post = 0x2,
  Delete = 0x3,
  Report = 0x4,
  Comment = 0x5,
};

```

### `IMinecraftEventing::ClubsEngagementTargetType`
```
typedef cg::ColorSpace IMinecraftEventing::ClubsEngagementTargetType;

```

### `IMinecraftEventing::DayOneExperienceState`
```
typedef Bedrock::Threading::AsyncStatus IMinecraftEventing::DayOneExperienceState;

```

### `IMinecraftEventing::ElementConstructorUseType`
```
enum IMinecraftEventing::ElementConstructorUseType : __int32
{
  Created = 0x0,
  Entered = 0x1,
};

```

### `IMinecraftEventing::RealmConnectionLambda`
```
enum IMinecraftEventing::RealmConnectionLambda : __int32
{
  CompletedCallback = 0x0,
  RetryCallback = 0x1,
  ProgressScreenTickCallback = 0x2,
  ProgressScreenOnCancelCallback = 0x3,
  GameServerConnectProgressCallback = 0x4,
};

```

### `IMinecraftEventing::MultiplayerSessionUpdateTrigger`
```
typedef Rotation IMinecraftEventing::MultiplayerSessionUpdateTrigger;

```

### `IMinecraftEventing::OpenCodeMethod`
```
enum IMinecraftEventing::OpenCodeMethod : __int32
{
  TouchHUD = 0x0,
  Keypress = 0x1,
  Command = 0x2,
};

```

### `IMinecraftEventing::PetDeathContext`
```
enum IMinecraftEventing::PetDeathContext : __int32
{
  DiedOfOtherCause = 0x0,
  PlayerMurdered = 0x1,
  OwnerMurdered = 0x2,
  MobMurdered = 0x3,
};

```

### `IMinecraftEventing::StructureBlockActionType`
```
typedef cg::ColorSpace IMinecraftEventing::StructureBlockActionType;

```

### `IMinecraftEventing::ChunkCacheResultType`
```
enum IMinecraftEventing::ChunkCacheResultType : __int32
{
  SuccessFromCache = 0x0,
  SuccessFromNetwork = 0x1,
  Failure = 0x2,
};

```

### `ItemInstallState`
```
enum ItemInstallState : __int32
{
  NotInstalled = 0x0,
  Installed = 0x1,
  UpdateAvailable = 0x2,
  _Unknown = 0x3,
};

```

### `InitiatorCategory`
```
typedef cg::ColorSpace InitiatorCategory;

```

### `ItemType`
```
enum ItemType : __int32
{
  Legacy = 0x0,
  DataDriven = 0x1,
};

```

### `InventoryTransactionError`
```
typedef cg::ColorSpace InventoryTransactionError;

```

### `ICameraBehavior::UpdateOrder`
```
enum ICameraBehavior::UpdateOrder : __int32
{
  First = 0x0,
  Second = 0x1,
  Third = 0x2,
  Fourth = 0x3,
  Fifth = 0x4,
  Sixth = 0x5,
  Seventh = 0x6,
  Eighth = 0x7,
  Ninth = 0x8,
  Tenth = 0x9,
  Eleventh = 0xA,
};

```

### `InHandUpdateType`
```
typedef ActorEvent InHandUpdateType;

```

### `ItemSpecialLocation`
```
typedef TransformSpace ItemSpecialLocation;

```

### `ItemSetType`
```
typedef MinecraftEventing::ItemInteractMethod ItemSetType;

```

### `ItemAddType`
```
typedef ItemPlaceType ItemAddType;

```

### `IPPROTO`
```
enum IPPROTO : __int32
{
  IPPROTO_HOPOPTS = 0x0,
  IPPROTO_ICMP = 0x1,
  IPPROTO_IGMP = 0x2,
  IPPROTO_GGP = 0x3,
  IPPROTO_IPV4 = 0x4,
  IPPROTO_ST = 0x5,
  IPPROTO_TCP = 0x6,
  IPPROTO_CBT = 0x7,
  IPPROTO_EGP = 0x8,
  IPPROTO_IGP = 0x9,
  IPPROTO_PUP = 0xC,
  IPPROTO_UDP = 0x11,
  IPPROTO_IDP = 0x16,
  IPPROTO_RDP = 0x1B,
  IPPROTO_IPV6 = 0x29,
  IPPROTO_ROUTING = 0x2B,
  IPPROTO_FRAGMENT = 0x2C,
  IPPROTO_ESP = 0x32,
  IPPROTO_AH = 0x33,
  IPPROTO_ICMPV6 = 0x3A,
  IPPROTO_NONE = 0x3B,
  IPPROTO_DSTOPTS = 0x3C,
  IPPROTO_ND = 0x4D,
  IPPROTO_ICLFXBM = 0x4E,
  IPPROTO_PIM = 0x67,
  IPPROTO_PGM = 0x71,
  IPPROTO_L2TP = 0x73,
  IPPROTO_SCTP = 0x84,
  IPPROTO_RAW = 0xFF,
  IPPROTO_MAX = 0x100,
  IPPROTO_RESERVED_RAW = 0x101,
  IPPROTO_RESERVED_IPSEC = 0x102,
  IPPROTO_RESERVED_IPSECOFFLOAD = 0x103,
  IPPROTO_RESERVED_WNV = 0x104,
  IPPROTO_RESERVED_MAX = 0x105,
};

```

### `IMPORT_OBJECT_TYPE`
```
enum IMPORT_OBJECT_TYPE : __int32
{
  IMPORT_OBJECT_CODE = 0x0,
  IMPORT_OBJECT_DATA = 0x1,
  IMPORT_OBJECT_CONST = 0x2,
};

```

### `IMPORT_OBJECT_NAME_TYPE`
```
enum IMPORT_OBJECT_NAME_TYPE : __int32
{
  IMPORT_OBJECT_ORDINAL = 0x0,
  IMPORT_OBJECT_NAME = 0x1,
  IMPORT_OBJECT_NAME_NO_PREFIX = 0x2,
  IMPORT_OBJECT_NAME_UNDECORATE = 0x3,
  IMPORT_OBJECT_NAME_EXPORTAS = 0x4,
};

```

### `IMAGE_AUX_SYMBOL_TYPE`
```
enum IMAGE_AUX_SYMBOL_TYPE : __int32
{
  IMAGE_AUX_SYMBOL_TYPE_TOKEN_DEF = 0x1,
};

```

### `ImageCacheMode`
```
typedef HolographicPlatform::GestureMode ImageCacheMode;

```

### `ItemRenderChunkType`
```
typedef MaterialType ItemRenderChunkType;

```

### `InteractPacket::Action`
```
typedef TransformSpace InteractPacket::Action;

```

### `ItemLockMode`
```
typedef Rotation ItemLockMode;

```

### `InputComponent::PressType`
```
enum InputComponent::PressType : __int32
{
  Single = 0x0,
  Double = 0x1,
};

```

### `ImportSuccess`
```
typedef TaskOptions ImportSuccess;

```

### `ImportFailure`
```
typedef TaskOptions ImportFailure;

```

### `InteractionModel`
```
enum InteractionModel : __int32
{
  CombinedInventory = 0x0,
  SeparateInventoryAndHotbar = 0x1,
};

```

### `ItemTransferType`
```
typedef MinecraftEventing::ItemInteractMethod ItemTransferType;

```

### `ItemCraftType`
```
typedef ItemPlaceType ItemCraftType;

```

### `InventoryLeftTabIndex`
```
typedef Rotation InventoryLeftTabIndex;

```

### `InventoryRightTabIndex`
```
typedef Rotation InventoryRightTabIndex;

```

### `InventoryLayout`
```
typedef Rotation InventoryLayout;

```

### `InstantiationResult`
```
typedef IMinecraftEventing::AuthenticationOutcome InstantiationResult;

```

### `IdentityDefinition::Type`
```
typedef TransformSpace IdentityDefinition::Type;

```

### `ImmersiveReaderScreenController::ImmersiveReaderErrorType`
```
enum ImmersiveReaderScreenController::ImmersiveReaderErrorType : __int8
{
  WebviewFailure = 0x0,
  IdentityFailure = 0x1,
};

```

### `ImmersiveReaderScreenController::ImmersiveReaderStatusCodes`
```
typedef ChunkState ImmersiveReaderScreenController::ImmersiveReaderStatusCodes;

```

### `ImmersiveReaderScreenController::ImmersiveReaderStage`
```
typedef UIAnim::State ImmersiveReaderScreenController::ImmersiveReaderStage;

```

### `IPJoinScreenController::JoinRequest`
```
typedef StartIntent IPJoinScreenController::JoinRequest;

```

### `Inputs`
```
typedef Rotation Inputs;

```

### `IGPSTurningMode`
```
enum IGPSTurningMode : __int32
{
  STANDARD = 0x0,
  STUTTER = 0x1,
  DIRECT = 0x2,
  ROLL = 0x4,
  STUTTER_DIRECT = 0x3,
  STUTTER_ROLL = 0x5,
  DIRECT_ROLL = 0x6,
  STUTTER_DIRECT_ROLL = 0x7,
};

```

### `InGameRealityModeScreen::VROptionPresetMode`
```
typedef Realms::World::State InGameRealityModeScreen::VROptionPresetMode;

```

### `ImGuiItemFlags_`
```
enum ImGuiItemFlags_ : __int32
{
  ImGuiItemFlags_NoTabStop = 0x1,
  ImGuiItemFlags_ButtonRepeat = 0x2,
  ImGuiItemFlags_Disabled = 0x4,
  ImGuiItemFlags_NoNav = 0x8,
  ImGuiItemFlags_NoNavDefaultFocus = 0x10,
  ImGuiItemFlags_SelectableDontClosePopup = 0x20,
  ImGuiItemFlags_Default_ = 0x0,
};

```

### `ImGuiLayoutType_`
```
enum ImGuiLayoutType_ : __int32
{
  ImGuiLayoutType_Vertical = 0x0,
  ImGuiLayoutType_Horizontal = 0x1,
};

```

### `ImGuiNavForward`
```
enum ImGuiNavForward : __int32
{
  ImGuiNavForward_None = 0x0,
  ImGuiNavForward_ForwardQueued = 0x1,
  ImGuiNavForward_ForwardActive = 0x2,
};

```

### `ImGuiInputSource`
```
enum ImGuiInputSource : __int32
{
  ImGuiInputSource_None = 0x0,
  ImGuiInputSource_Mouse = 0x1,
  ImGuiInputSource_Nav = 0x2,
  ImGuiInputSource_NavKeyboard = 0x3,
  ImGuiInputSource_NavGamepad = 0x4,
  ImGuiInputSource_COUNT = 0x5,
};

```

### `ImGuiColorEditFlags_`
```
enum ImGuiColorEditFlags_ : __int32
{
  ImGuiColorEditFlags_None = 0x0,
  ImGuiColorEditFlags_NoAlpha = 0x2,
  ImGuiColorEditFlags_NoPicker = 0x4,
  ImGuiColorEditFlags_NoOptions = 0x8,
  ImGuiColorEditFlags_NoSmallPreview = 0x10,
  ImGuiColorEditFlags_NoInputs = 0x20,
  ImGuiColorEditFlags_NoTooltip = 0x40,
  ImGuiColorEditFlags_NoLabel = 0x80,
  ImGuiColorEditFlags_NoSidePreview = 0x100,
  ImGuiColorEditFlags_NoDragDrop = 0x200,
  ImGuiColorEditFlags_AlphaBar = 0x10000,
  ImGuiColorEditFlags_AlphaPreview = 0x20000,
  ImGuiColorEditFlags_AlphaPreviewHalf = 0x40000,
  ImGuiColorEditFlags_HDR = 0x80000,
  ImGuiColorEditFlags_RGB = 0x100000,
  ImGuiColorEditFlags_HSV = 0x200000,
  ImGuiColorEditFlags_HEX = 0x400000,
  ImGuiColorEditFlags_Uint8 = 0x800000,
  ImGuiColorEditFlags_Float = 0x1000000,
  ImGuiColorEditFlags_PickerHueBar = 0x2000000,
  ImGuiColorEditFlags_PickerHueWheel = 0x4000000,
  ImGuiColorEditFlags__InputsMask = 0x700000,
  ImGuiColorEditFlags__DataTypeMask = 0x1800000,
  ImGuiColorEditFlags__PickerMask = 0x6000000,
  ImGuiColorEditFlags__OptionsDefault = 0x2900000,
};

```

### `ImGuiMouseCursor_`
```
enum ImGuiMouseCursor_ : __int32
{
  ImGuiMouseCursor_None = 0xFFFFFFFF,
  ImGuiMouseCursor_Arrow = 0x0,
  ImGuiMouseCursor_TextInput = 0x1,
  ImGuiMouseCursor_ResizeAll = 0x2,
  ImGuiMouseCursor_ResizeNS = 0x3,
  ImGuiMouseCursor_ResizeEW = 0x4,
  ImGuiMouseCursor_ResizeNESW = 0x5,
  ImGuiMouseCursor_ResizeNWSE = 0x6,
  ImGuiMouseCursor_Hand = 0x7,
  ImGuiMouseCursor_COUNT = 0x8,
  ImGuiMouseCursor_Count_ = 0x8,
};

```

### `ImGuiDir_`
```
enum ImGuiDir_ : __int32
{
  ImGuiDir_None = 0xFFFFFFFF,
  ImGuiDir_Left = 0x0,
  ImGuiDir_Right = 0x1,
  ImGuiDir_Up = 0x2,
  ImGuiDir_Down = 0x3,
  ImGuiDir_COUNT = 0x4,
};

```

### `ImGuiPopupPositionPolicy`
```
enum ImGuiPopupPositionPolicy : __int32
{
  ImGuiPopupPositionPolicy_Default = 0x0,
  ImGuiPopupPositionPolicy_ComboBox = 0x1,
};

```

### `ImGuiWindowFlags_`
```
enum ImGuiWindowFlags_ : __int32
{
  ImGuiWindowFlags_None = 0x0,
  ImGuiWindowFlags_NoTitleBar = 0x1,
  ImGuiWindowFlags_NoResize = 0x2,
  ImGuiWindowFlags_NoMove = 0x4,
  ImGuiWindowFlags_NoScrollbar = 0x8,
  ImGuiWindowFlags_NoScrollWithMouse = 0x10,
  ImGuiWindowFlags_NoCollapse = 0x20,
  ImGuiWindowFlags_AlwaysAutoResize = 0x40,
  ImGuiWindowFlags_NoBackground = 0x80,
  ImGuiWindowFlags_NoSavedSettings = 0x100,
  ImGuiWindowFlags_NoMouseInputs = 0x200,
  ImGuiWindowFlags_MenuBar = 0x400,
  ImGuiWindowFlags_HorizontalScrollbar = 0x800,
  ImGuiWindowFlags_NoFocusOnAppearing = 0x1000,
  ImGuiWindowFlags_NoBringToFrontOnFocus = 0x2000,
  ImGuiWindowFlags_AlwaysVerticalScrollbar = 0x4000,
  ImGuiWindowFlags_AlwaysHorizontalScrollbar = 0x8000,
  ImGuiWindowFlags_AlwaysUseWindowPadding = 0x10000,
  ImGuiWindowFlags_NoNavInputs = 0x40000,
  ImGuiWindowFlags_NoNavFocus = 0x80000,
  ImGuiWindowFlags_NoNav = 0xC0000,
  ImGuiWindowFlags_NoDecoration = 0x2B,
  ImGuiWindowFlags_NoInputs = 0xC0200,
  ImGuiWindowFlags_NavFlattened = 0x800000,
  ImGuiWindowFlags_ChildWindow = 0x1000000,
  ImGuiWindowFlags_Tooltip = 0x2000000,
  ImGuiWindowFlags_Popup = 0x4000000,
  ImGuiWindowFlags_Modal = 0x8000000,
  ImGuiWindowFlags_ChildMenu = 0x10000000,
};

```

### `ImGuiNavHighlightFlags_`
```
enum ImGuiNavHighlightFlags_ : __int32
{
  ImGuiNavHighlightFlags_None = 0x0,
  ImGuiNavHighlightFlags_TypeDefault = 0x1,
  ImGuiNavHighlightFlags_TypeThin = 0x2,
  ImGuiNavHighlightFlags_AlwaysDraw = 0x4,
  ImGuiNavHighlightFlags_NoRounding = 0x8,
};

```

### `ImGuiCol_`
```
enum ImGuiCol_ : __int32
{
  ImGuiCol_Text = 0x0,
  ImGuiCol_TextDisabled = 0x1,
  ImGuiCol_WindowBg = 0x2,
  ImGuiCol_ChildBg = 0x3,
  ImGuiCol_PopupBg = 0x4,
  ImGuiCol_Border = 0x5,
  ImGuiCol_BorderShadow = 0x6,
  ImGuiCol_FrameBg = 0x7,
  ImGuiCol_FrameBgHovered = 0x8,
  ImGuiCol_FrameBgActive = 0x9,
  ImGuiCol_TitleBg = 0xA,
  ImGuiCol_TitleBgActive = 0xB,
  ImGuiCol_TitleBgCollapsed = 0xC,
  ImGuiCol_MenuBarBg = 0xD,
  ImGuiCol_ScrollbarBg = 0xE,
  ImGuiCol_ScrollbarGrab = 0xF,
  ImGuiCol_ScrollbarGrabHovered = 0x10,
  ImGuiCol_ScrollbarGrabActive = 0x11,
  ImGuiCol_CheckMark = 0x12,
  ImGuiCol_SliderGrab = 0x13,
  ImGuiCol_SliderGrabActive = 0x14,
  ImGuiCol_Button = 0x15,
  ImGuiCol_ButtonHovered = 0x16,
  ImGuiCol_ButtonActive = 0x17,
  ImGuiCol_Header = 0x18,
  ImGuiCol_HeaderHovered = 0x19,
  ImGuiCol_HeaderActive = 0x1A,
  ImGuiCol_Separator = 0x1B,
  ImGuiCol_SeparatorHovered = 0x1C,
  ImGuiCol_SeparatorActive = 0x1D,
  ImGuiCol_ResizeGrip = 0x1E,
  ImGuiCol_ResizeGripHovered = 0x1F,
  ImGuiCol_ResizeGripActive = 0x20,
  ImGuiCol_PlotLines = 0x21,
  ImGuiCol_PlotLinesHovered = 0x22,
  ImGuiCol_PlotHistogram = 0x23,
  ImGuiCol_PlotHistogramHovered = 0x24,
  ImGuiCol_TextSelectedBg = 0x25,
  ImGuiCol_DragDropTarget = 0x26,
  ImGuiCol_NavHighlight = 0x27,
  ImGuiCol_NavWindowingHighlight = 0x28,
  ImGuiCol_NavWindowingDimBg = 0x29,
  ImGuiCol_ModalWindowDimBg = 0x2A,
  ImGuiCol_COUNT = 0x2B,
  ImGuiCol_ChildWindowBg = 0x3,
  ImGuiCol_Column = 0x1B,
  ImGuiCol_ColumnHovered = 0x1C,
  ImGuiCol_ColumnActive = 0x1D,
  ImGuiCol_ModalWindowDarkening = 0x2A,
};

```

### `ImGuiNavInput_`
```
enum ImGuiNavInput_ : __int32
{
  ImGuiNavInput_Activate = 0x0,
  ImGuiNavInput_Cancel = 0x1,
  ImGuiNavInput_Input = 0x2,
  ImGuiNavInput_Menu = 0x3,
  ImGuiNavInput_DpadLeft = 0x4,
  ImGuiNavInput_DpadRight = 0x5,
  ImGuiNavInput_DpadUp = 0x6,
  ImGuiNavInput_DpadDown = 0x7,
  ImGuiNavInput_LStickLeft = 0x8,
  ImGuiNavInput_LStickRight = 0x9,
  ImGuiNavInput_LStickUp = 0xA,
  ImGuiNavInput_LStickDown = 0xB,
  ImGuiNavInput_FocusPrev = 0xC,
  ImGuiNavInput_FocusNext = 0xD,
  ImGuiNavInput_TweakSlow = 0xE,
  ImGuiNavInput_TweakFast = 0xF,
  ImGuiNavInput_KeyMenu_ = 0x10,
  ImGuiNavInput_KeyLeft_ = 0x11,
  ImGuiNavInput_KeyRight_ = 0x12,
  ImGuiNavInput_KeyUp_ = 0x13,
  ImGuiNavInput_KeyDown_ = 0x14,
  ImGuiNavInput_COUNT = 0x15,
  ImGuiNavInput_InternalStart_ = 0x10,
};

```

### `ImGuiDragDropFlags_`
```
enum ImGuiDragDropFlags_ : __int32
{
  ImGuiDragDropFlags_None = 0x0,
  ImGuiDragDropFlags_SourceNoPreviewTooltip = 0x1,
  ImGuiDragDropFlags_SourceNoDisableHover = 0x2,
  ImGuiDragDropFlags_SourceNoHoldToOpenOthers = 0x4,
  ImGuiDragDropFlags_SourceAllowNullID = 0x8,
  ImGuiDragDropFlags_SourceExtern = 0x10,
  ImGuiDragDropFlags_SourceAutoExpirePayload = 0x20,
  ImGuiDragDropFlags_AcceptBeforeDelivery = 0x400,
  ImGuiDragDropFlags_AcceptNoDrawDefaultRect = 0x800,
  ImGuiDragDropFlags_AcceptNoPreviewTooltip = 0x1000,
  ImGuiDragDropFlags_AcceptPeekOnly = 0xC00,
};

```

### `ImGuiHoveredFlags_`
```
enum ImGuiHoveredFlags_ : __int32
{
  ImGuiHoveredFlags_None = 0x0,
  ImGuiHoveredFlags_ChildWindows = 0x1,
  ImGuiHoveredFlags_RootWindow = 0x2,
  ImGuiHoveredFlags_AnyWindow = 0x4,
  ImGuiHoveredFlags_AllowWhenBlockedByPopup = 0x8,
  ImGuiHoveredFlags_AllowWhenBlockedByActiveItem = 0x20,
  ImGuiHoveredFlags_AllowWhenOverlapped = 0x40,
  ImGuiHoveredFlags_AllowWhenDisabled = 0x80,
  ImGuiHoveredFlags_RectOnly = 0x68,
  ImGuiHoveredFlags_RootAndChildWindows = 0x3,
};

```

### `ImGuiFocusedFlags_`
```
enum ImGuiFocusedFlags_ : __int32
{
  ImGuiFocusedFlags_None = 0x0,
  ImGuiFocusedFlags_ChildWindows = 0x1,
  ImGuiFocusedFlags_RootWindow = 0x2,
  ImGuiFocusedFlags_AnyWindow = 0x4,
  ImGuiFocusedFlags_RootAndChildWindows = 0x3,
};

```

### `ImGuiComboFlags_`
```
enum ImGuiComboFlags_ : __int32
{
  ImGuiComboFlags_None = 0x0,
  ImGuiComboFlags_PopupAlignLeft = 0x1,
  ImGuiComboFlags_HeightSmall = 0x2,
  ImGuiComboFlags_HeightRegular = 0x4,
  ImGuiComboFlags_HeightLarge = 0x8,
  ImGuiComboFlags_HeightLargest = 0x10,
  ImGuiComboFlags_NoArrowButton = 0x20,
  ImGuiComboFlags_NoPreview = 0x40,
  ImGuiComboFlags_HeightMask_ = 0x1E,
};

```

### `ImGuiCond_`
```
enum ImGuiCond_ : __int32
{
  ImGuiCond_Always = 0x1,
  ImGuiCond_Once = 0x2,
  ImGuiCond_FirstUseEver = 0x4,
  ImGuiCond_Appearing = 0x8,
  ImGuiSetCond_Always = 0x1,
  ImGuiSetCond_Once = 0x2,
  ImGuiSetCond_FirstUseEver = 0x4,
  ImGuiSetCond_Appearing = 0x8,
};

```

### `ImGuiKey_`
```
enum ImGuiKey_ : __int32
{
  ImGuiKey_Tab = 0x0,
  ImGuiKey_LeftArrow = 0x1,
  ImGuiKey_RightArrow = 0x2,
  ImGuiKey_UpArrow = 0x3,
  ImGuiKey_DownArrow = 0x4,
  ImGuiKey_PageUp = 0x5,
  ImGuiKey_PageDown = 0x6,
  ImGuiKey_Home = 0x7,
  ImGuiKey_End = 0x8,
  ImGuiKey_Insert = 0x9,
  ImGuiKey_Delete = 0xA,
  ImGuiKey_Backspace = 0xB,
  ImGuiKey_Space = 0xC,
  ImGuiKey_Enter = 0xD,
  ImGuiKey_Escape = 0xE,
  ImGuiKey_A = 0xF,
  ImGuiKey_C = 0x10,
  ImGuiKey_V = 0x11,
  ImGuiKey_X = 0x12,
  ImGuiKey_Y = 0x13,
  ImGuiKey_Z = 0x14,
  ImGuiKey_COUNT = 0x15,
};

```

### `ImGuiStyleVar_`
```
enum ImGuiStyleVar_ : __int32
{
  ImGuiStyleVar_Alpha = 0x0,
  ImGuiStyleVar_WindowPadding = 0x1,
  ImGuiStyleVar_WindowRounding = 0x2,
  ImGuiStyleVar_WindowBorderSize = 0x3,
  ImGuiStyleVar_WindowMinSize = 0x4,
  ImGuiStyleVar_WindowTitleAlign = 0x5,
  ImGuiStyleVar_ChildRounding = 0x6,
  ImGuiStyleVar_ChildBorderSize = 0x7,
  ImGuiStyleVar_PopupRounding = 0x8,
  ImGuiStyleVar_PopupBorderSize = 0x9,
  ImGuiStyleVar_FramePadding = 0xA,
  ImGuiStyleVar_FrameRounding = 0xB,
  ImGuiStyleVar_FrameBorderSize = 0xC,
  ImGuiStyleVar_ItemSpacing = 0xD,
  ImGuiStyleVar_ItemInnerSpacing = 0xE,
  ImGuiStyleVar_IndentSpacing = 0xF,
  ImGuiStyleVar_ScrollbarSize = 0x10,
  ImGuiStyleVar_ScrollbarRounding = 0x11,
  ImGuiStyleVar_GrabMinSize = 0x12,
  ImGuiStyleVar_GrabRounding = 0x13,
  ImGuiStyleVar_ButtonTextAlign = 0x14,
  ImGuiStyleVar_COUNT = 0x15,
  ImGuiStyleVar_Count_ = 0x15,
  ImGuiStyleVar_ChildWindowRounding = 0x6,
};

```

### `ImDrawCornerFlags_`
```
enum ImDrawCornerFlags_ : __int32
{
  ImDrawCornerFlags_TopLeft = 0x1,
  ImDrawCornerFlags_TopRight = 0x2,
  ImDrawCornerFlags_BotLeft = 0x4,
  ImDrawCornerFlags_BotRight = 0x8,
  ImDrawCornerFlags_Top = 0x3,
  ImDrawCornerFlags_Bot = 0xC,
  ImDrawCornerFlags_Left = 0x5,
  ImDrawCornerFlags_Right = 0xA,
  ImDrawCornerFlags_All = 0xF,
};

```

### `ImGuiTreeNodeFlags_`
```
enum ImGuiTreeNodeFlags_ : __int32
{
  ImGuiTreeNodeFlags_None = 0x0,
  ImGuiTreeNodeFlags_Selected = 0x1,
  ImGuiTreeNodeFlags_Framed = 0x2,
  ImGuiTreeNodeFlags_AllowItemOverlap = 0x4,
  ImGuiTreeNodeFlags_NoTreePushOnOpen = 0x8,
  ImGuiTreeNodeFlags_NoAutoOpenOnLog = 0x10,
  ImGuiTreeNodeFlags_DefaultOpen = 0x20,
  ImGuiTreeNodeFlags_OpenOnDoubleClick = 0x40,
  ImGuiTreeNodeFlags_OpenOnArrow = 0x80,
  ImGuiTreeNodeFlags_Leaf = 0x100,
  ImGuiTreeNodeFlags_Bullet = 0x200,
  ImGuiTreeNodeFlags_FramePadding = 0x400,
  ImGuiTreeNodeFlags_NavLeftJumpsBackHere = 0x2000,
  ImGuiTreeNodeFlags_CollapsingHeader = 0x1A,
  ImGuiTreeNodeFlags_AllowOverlapMode = 0x4,
};

```

### `ItemStackRequestScreen`
```
typedef Frustum::FrustumSide ItemStackRequestScreen;

```

### `ItemStackNetResult`
```
typedef IMinecraftEventing::AuthenticationOutcome ItemStackNetResult;

```

### `ImportContextType`
```
typedef Skeleton::SkeletonType ImportContextType;

```

### `ItemStackRequestActionType`
```
typedef MinecraftEventing::ItemInteractMethod ItemStackRequestActionType;

```

### `IPlayerTickPolicy::TickAction`
```
typedef EventResult IPlayerTickPolicy::TickAction;

```

### `ItemStackNetManagerServer::TextFilterState`
```
typedef Rotation ItemStackNetManagerServer::TextFilterState;

```

### `ItemStackRequestActionMineBlock::PreValidationStatus`
```
typedef StreamReadResult ItemStackRequestActionMineBlock::PreValidationStatus;

```

### `IPackStoragePolicy::CacheInvalidationMode`
```
typedef Rotation IPackStoragePolicy::CacheInvalidationMode;

```

### `IChunkLoadedAction::ChunkLoadedActionType`
```
enum IChunkLoadedAction::ChunkLoadedActionType : __int8
{
  FunctionAction = 0x0,
  TestAction = 0x1,
  StructureAnimationAction = 0x2,
};

```

### `ItemReleaseInventoryTransaction::ActionType`
```
typedef Lockless::MemoryOrder ItemReleaseInventoryTransaction::ActionType;

```

### `ItemUseOnActorInventoryTransaction::ActionType`
```
typedef MinecraftPacketIds ItemUseOnActorInventoryTransaction::ActionType;

```

### `InMemoryAccessMode`
```
enum InMemoryAccessMode : __int32
{
  Read = 0x0,
  Write = 0x1,
};

```

### `IEObjectType`
```
enum IEObjectType : __int32
{
  IE_EPM_OBJECT_EVENT = 0x0,
  IE_EPM_OBJECT_MUTEX = 0x1,
  IE_EPM_OBJECT_SEMAPHORE = 0x2,
  IE_EPM_OBJECT_SHARED_MEMORY = 0x3,
  IE_EPM_OBJECT_WAITABLE_TIMER = 0x4,
  IE_EPM_OBJECT_FILE = 0x5,
  IE_EPM_OBJECT_NAMED_PIPE = 0x6,
  IE_EPM_OBJECT_REGISTRY = 0x7,
};

```

### `InnerAssetInstaller::eInstallStatus`
```
enum InnerAssetInstaller::eInstallStatus : __int32
{
  INSTALL_NONE = 0x0,
  INSTALL_START = 0x1,
  INSTALL_WAIT = 0x2,
  INSTALL_DONE = 0x3,
  INSTALL_FAIL = 0x4,
};

```

### `inflate_codes_mode`
```
typedef Category inflate_codes_mode;

```

### `inflate_block_mode`
```
typedef codetype inflate_block_mode;

```

### `ImGuiItemStatusFlags_`
```
enum ImGuiItemStatusFlags_ : __int32
{
  ImGuiItemStatusFlags_None = 0x0,
  ImGuiItemStatusFlags_HoveredRect = 0x1,
  ImGuiItemStatusFlags_HasDisplayRect = 0x2,
  ImGuiItemStatusFlags_Edited = 0x4,
};

```

### `ImGuiConfigFlags_`
```
enum ImGuiConfigFlags_ : __int32
{
  ImGuiConfigFlags_None = 0x0,
  ImGuiConfigFlags_NavEnableKeyboard = 0x1,
  ImGuiConfigFlags_NavEnableGamepad = 0x2,
  ImGuiConfigFlags_NavEnableSetMousePos = 0x4,
  ImGuiConfigFlags_NavNoCaptureKeyboard = 0x8,
  ImGuiConfigFlags_NoMouse = 0x10,
  ImGuiConfigFlags_NoMouseCursorChange = 0x20,
  ImGuiConfigFlags_IsSRGB = 0x100000,
  ImGuiConfigFlags_IsTouchScreen = 0x200000,
};

```

### `ImGuiInputReadMode`
```
enum ImGuiInputReadMode : __int32
{
  ImGuiInputReadMode_Down = 0x0,
  ImGuiInputReadMode_Pressed = 0x1,
  ImGuiInputReadMode_Released = 0x2,
  ImGuiInputReadMode_Repeat = 0x3,
  ImGuiInputReadMode_RepeatSlow = 0x4,
  ImGuiInputReadMode_RepeatFast = 0x5,
};

```

### `ImGuiButtonFlags_`
```
enum ImGuiButtonFlags_ : __int32
{
  ImGuiButtonFlags_None = 0x0,
  ImGuiButtonFlags_Repeat = 0x1,
  ImGuiButtonFlags_PressedOnClickRelease = 0x2,
  ImGuiButtonFlags_PressedOnClick = 0x4,
  ImGuiButtonFlags_PressedOnRelease = 0x8,
  ImGuiButtonFlags_PressedOnDoubleClick = 0x10,
  ImGuiButtonFlags_FlattenChildren = 0x20,
  ImGuiButtonFlags_AllowItemOverlap = 0x40,
  ImGuiButtonFlags_DontClosePopups = 0x80,
  ImGuiButtonFlags_Disabled = 0x100,
  ImGuiButtonFlags_AlignTextBaseLine = 0x200,
  ImGuiButtonFlags_NoKeyModifiers = 0x400,
  ImGuiButtonFlags_NoHoldingActiveID = 0x800,
  ImGuiButtonFlags_PressedOnDragDropHold = 0x1000,
  ImGuiButtonFlags_NoNavFocus = 0x2000,
};

```

### `ImGuiBackendFlags_`
```
enum ImGuiBackendFlags_ : __int32
{
  ImGuiBackendFlags_None = 0x0,
  ImGuiBackendFlags_HasGamepad = 0x1,
  ImGuiBackendFlags_HasMouseCursors = 0x2,
  ImGuiBackendFlags_HasSetMousePos = 0x4,
};

```

### `ImGuiColumnsFlags_`
```
enum ImGuiColumnsFlags_ : __int32
{
  ImGuiColumnsFlags_None = 0x0,
  ImGuiColumnsFlags_NoBorder = 0x1,
  ImGuiColumnsFlags_NoResize = 0x2,
  ImGuiColumnsFlags_NoPreserveWidths = 0x4,
  ImGuiColumnsFlags_NoForceWithinWindow = 0x8,
  ImGuiColumnsFlags_GrowParentContentsSize = 0x10,
};

```

### `ImGuiDataType_`
```
enum ImGuiDataType_ : __int32
{
  ImGuiDataType_S32 = 0x0,
  ImGuiDataType_U32 = 0x1,
  ImGuiDataType_S64 = 0x2,
  ImGuiDataType_U64 = 0x3,
  ImGuiDataType_Float = 0x4,
  ImGuiDataType_Double = 0x5,
  ImGuiDataType_COUNT = 0x6,
};

```

### `ImGuiNavMoveFlags_`
```
enum ImGuiNavMoveFlags_ : __int32
{
  ImGuiNavMoveFlags_None = 0x0,
  ImGuiNavMoveFlags_LoopX = 0x1,
  ImGuiNavMoveFlags_LoopY = 0x2,
  ImGuiNavMoveFlags_WrapX = 0x4,
  ImGuiNavMoveFlags_WrapY = 0x8,
  ImGuiNavMoveFlags_AllowCurrentNavId = 0x10,
  ImGuiNavMoveFlags_AlsoScoreVisibleSet = 0x20,
};

```

### `ImGuiNavDirSourceFlags_`
```
enum ImGuiNavDirSourceFlags_ : __int32
{
  ImGuiNavDirSourceFlags_None = 0x0,
  ImGuiNavDirSourceFlags_Keyboard = 0x1,
  ImGuiNavDirSourceFlags_PadDPad = 0x2,
  ImGuiNavDirSourceFlags_PadLStick = 0x4,
};

```

### `ImGuiAxis`
```
enum ImGuiAxis : __int32
{
  ImGuiAxis_None = 0xFFFFFFFF,
  ImGuiAxis_X = 0x0,
  ImGuiAxis_Y = 0x1,
};

```

### `ImDrawListFlags_`
```
enum ImDrawListFlags_ : __int32
{
  ImDrawListFlags_AntiAliasedLines = 0x1,
  ImDrawListFlags_AntiAliasedFill = 0x2,
};

```

### `ImGuiInputTextFlags_`
```
enum ImGuiInputTextFlags_ : __int32
{
  ImGuiInputTextFlags_None = 0x0,
  ImGuiInputTextFlags_CharsDecimal = 0x1,
  ImGuiInputTextFlags_CharsHexadecimal = 0x2,
  ImGuiInputTextFlags_CharsUppercase = 0x4,
  ImGuiInputTextFlags_CharsNoBlank = 0x8,
  ImGuiInputTextFlags_AutoSelectAll = 0x10,
  ImGuiInputTextFlags_EnterReturnsTrue = 0x20,
  ImGuiInputTextFlags_CallbackCompletion = 0x40,
  ImGuiInputTextFlags_CallbackHistory = 0x80,
  ImGuiInputTextFlags_CallbackAlways = 0x100,
  ImGuiInputTextFlags_CallbackCharFilter = 0x200,
  ImGuiInputTextFlags_AllowTabInput = 0x400,
  ImGuiInputTextFlags_CtrlEnterForNewLine = 0x800,
  ImGuiInputTextFlags_NoHorizontalScroll = 0x1000,
  ImGuiInputTextFlags_AlwaysInsertMode = 0x2000,
  ImGuiInputTextFlags_ReadOnly = 0x4000,
  ImGuiInputTextFlags_Password = 0x8000,
  ImGuiInputTextFlags_NoUndoRedo = 0x10000,
  ImGuiInputTextFlags_CharsScientific = 0x20000,
  ImGuiInputTextFlags_CallbackResize = 0x40000,
  ImGuiInputTextFlags_Multiline = 0x100000,
};

```

### `ImGuiSelectableFlags_`
```
enum ImGuiSelectableFlags_ : __int32
{
  ImGuiSelectableFlags_None = 0x0,
  ImGuiSelectableFlags_DontClosePopups = 0x1,
  ImGuiSelectableFlags_SpanAllColumns = 0x2,
  ImGuiSelectableFlags_AllowDoubleClick = 0x4,
  ImGuiSelectableFlags_Disabled = 0x8,
};

```

### `ImFontAtlasFlags_`
```
enum ImFontAtlasFlags_ : __int32
{
  ImFontAtlasFlags_None = 0x0,
  ImFontAtlasFlags_NoPowerOfTwoHeight = 0x1,
  ImFontAtlasFlags_NoMouseCursors = 0x2,
};

```

### `ImGuiSliderFlags_`
```
enum ImGuiSliderFlags_ : __int32
{
  ImGuiSliderFlags_None = 0x0,
  ImGuiSliderFlags_Vertical = 0x1,
};

```

### `ImGuiPlotType`
```
enum ImGuiPlotType : __int32
{
  ImGuiPlotType_Lines = 0x0,
  ImGuiPlotType_Histogram = 0x1,
};

```

### `ImGuiSelectableFlagsPrivate_`
```
enum ImGuiSelectableFlagsPrivate_ : __int32
{
  ImGuiSelectableFlags_NoHoldingActiveID = 0x400,
  ImGuiSelectableFlags_PressedOnClick = 0x800,
  ImGuiSelectableFlags_PressedOnRelease = 0x1000,
  ImGuiSelectableFlags_DrawFillAvailWidth = 0x2000,
};

```

### `ImGuiSeparatorFlags_`
```
enum ImGuiSeparatorFlags_ : __int32
{
  ImGuiSeparatorFlags_None = 0x0,
  ImGuiSeparatorFlags_Horizontal = 0x1,
  ImGuiSeparatorFlags_Vertical = 0x2,
};

```

### `ImGuiDragFlags_`
```
enum ImGuiDragFlags_ : __int32
{
  ImGuiDragFlags_None = 0x0,
  ImGuiDragFlags_Vertical = 0x1,
};

```

