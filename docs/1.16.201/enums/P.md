# P
### `ProfanityFilterContext`
Name | Value
-|-


### `PackListType`
Name | Value
-|-


### `personaScreen::NavigateToPersonaFrom`
Name | Value
-|-
Store | `0`
DressingRoom | `1`


### `ParticleLayer`
Name | Value
-|-
Standard | `0`
SingleTriggerGearVR | `1`
GearVR | `2`
MotionController | `3`
_count | `4`


### `persona::PieceSide`
Name | Value
-|-


### `persona::PieceType`
Name | Value
-|-


### `persona::Rarity`
Name | Value
-|-


### `PurchasePath`
Name | Value
-|-


### `PacketPriority`
Name | Value
-|-
IMMEDIATE_PRIORITY | `0`
HIGH_PRIORITY | `1`
MEDIUM_PRIORITY | `2`
LOW_PRIORITY | `3`
NUMBER_OF_PRIORITIES | `4`


### `PackManifestFormat`
Name | Value
-|-
V0 | `0`
V1 | `1`
V2 | `2`


### `PackType`
Name | Value
-|-


### `PackOrigin`
Name | Value
-|-
NotInstalled | `0`
Installed | `1`
UpdateAvailable | `2`
_Unknown | `3`


### `Projection`
Name | Value
-|-


### `PostProcessSettings`
Name | Value
-|-


### `PlayerScoreSetFunction`
Name | Value
-|-
Add | `0`
PlayerAdded | `1`
Remove | `2`
PlayerRemoved | `3`
Update_Percent | `4`
Update_Name | `5`
Update_Properties | `6`
Update_Style | `7`


### `PathCompletionType`
Name | Value
-|-
EMPTY | `0`
PARTIAL | `1`
FULL | `2`


### `PacketReliability`
Name | Value
-|-
UNRELIABLE | `0`
UNRELIABLE_SEQUENCED | `1`
RELIABLE | `2`
RELIABLE_ORDERED | `3`
RELIABLE_SEQUENCED | `4`
UNRELIABLE_WITH_ACK_RECEIPT | `5`
RELIABLE_WITH_ACK_RECEIPT | `6`
RELIABLE_ORDERED_WITH_ACK_RECEIPT | `7`
NUMBER_OF_RELIABILITIES | `8`


### `persona::ProfileType`
Name | Value
-|-


### `PlayerTickConfig::TickPolicy`
Name | Value
-|-
Greedy | `0`
Throttled | `1`


### `persona::OwnershipFilterType`
Name | Value
-|-
OwnedOnly | `0`
Everything | `1`
FilteredOwnToBack | `2`
FilterOwnedToFront | `3`
UnownedOnly | `4`
OwnedCapes | `5`


### `persona::AnimatedTextureType`
Name | Value
-|-


### `PlayerPermissionLevel`
Name | Value
-|-
Visitor | `0`
Member | `1`
Operator | `2`
Custom | `3`


### `PlayScreenDefaultTab`
Name | Value
-|-


### `PlayScreenController::ServerCollectionName`
Name | Value
-|-


### `PlayScreenController::ConvertProgressState`
Name | Value
-|-


### `PackSelectResult`
Name | Value
-|-


### `PackCategory`
Name | Value
-|-


### `persona::ReactAnimationType`
Name | Value
-|-
idle | `0`
idle_torso | `1`
idle_head | `2`
idle_bottom | `3`
idle_arm | `4`
idle_back | `5`
react_head | `6`
react_torso | `7`
react_bottom | `8`
react_arm | `9`
react_back | `10`
react_confirm | `11`
react_bored | `12`
react_bored_torso | `13`
react_bored_head | `14`
react_bored_bottom | `15`
react_bored_arm | `16`
react_bored_back | `17`
react_offer | `18`
react_offer_torso | `19`
react_offer_head | `20`
react_offer_bottom | `21`
react_offer_arm | `22`
react_offer_back | `23`
zoom | `24`


### `ParticleType`
Name | Value
-|-


### `PersonaRepository::PendingPersonaAppearanceStatus`
Name | Value
-|-
DownloadingPiecesInProgress | `0`
LoadingPiecesInProgress | `1`
LoadingPiecesComplete | `2`
Processing | `3`
ReadyToRemove | `4`


### `persona::PersonaError`
Name | Value
-|-
NoError | `0`
ControllerRequired | `1`
InvalidConfiguration | `2`
AdhocOverWirelessConnectionLimit | `3`
AdhocInvalidConfiguration | `4`


### `PackAccessStrategyType`
Name | Value
-|-


### `PackStorage::PendingTask::Type`
Name | Value
-|-
File | `1`
Deleted | `18446744073709551488`


### `ProjectileAnchor`
Name | Value
-|-


### `persona::AnimationExpression`
Name | Value
-|-


### `PlayerSuspension::State`
Name | Value
-|-
Suspend | `0`
Resume | `1`


### `POIType`
Name | Value
-|-


### `PlayerArmorExchangeEventTriggeredLocation`
Name | Value
-|-
ServerPlayerSetArmor | `0`
MobHurtArmor | `1`


### `Potion::PotionType`
Name | Value
-|-


### `PistonBlock::Type`
Name | Value
-|-


### `PressurePlateBlock::Sensitivity`
Name | Value
-|-
EVERYTHING | `0`
MOBS | `1`
PLAYERS | `2`


### `PrismarineBlockType`
Name | Value
-|-


### `PillarAxis`
Name | Value
-|-


### `PortalAxis`
```
typedef cg::ColorSpace PortalAxis;

```

### `PaletteColor`
```
typedef DimensionId PaletteColor;

```

### `PermissionRequestReason`
```
enum PermissionRequestReason : __int32
{
  ImportSkin = 0x0,
  ImportPack = 0x1,
  ChangeStorageLocation = 0x2,
  DebugCopySettingsFile = 0x3,
  ExportPDF = 0x4,
  ExpansionFile = 0x5,
};

```

### `PlatformType`
```
typedef UIScalingRules PlatformType;

```

### `PacketViolationResponse`
```
typedef Rotation PacketViolationResponse;

```

### `Player::DimensionState`
```
enum Player::DimensionState : __int32
{
  Ready = 0x0,
  Pending = 0x1,
  WaitingServerResponse = 0x2,
  WaitingArea = 0x3,
};

```

### `Player::PositionMode`
```
typedef MinecraftPacketIds Player::PositionMode;

```

### `PlayerUISlot`
```
typedef VRControllerType PlayerUISlot;

```

### `Player::SpawnPositionState`
```
typedef MinecraftPacketIds Player::SpawnPositionState;

```

### `Player::SpawnPositionSource`
```
typedef MinecraftPacketIds Player::SpawnPositionSource;

```

### `PlayerRespawnState`
```
enum PlayerRespawnState : __int8
{
  SearchingForSpawn = 0x0,
  ReadyToSpawn = 0x1,
  ClientReadyToSpawn = 0x2,
};

```

### `persona::PersonaPieceCollectionModel::RetrievalType`
```
typedef cg::ColorSpace persona::PersonaPieceCollectionModel::RetrievalType;

```

### `persona::PieceSubType`
```
typedef cg::ColorSpace persona::PieceSubType;

```

### `PackErrorType`
```
typedef Rotation PackErrorType;

```

### `PlayerListPacketType`
```
typedef BossEventUpdateType PlayerListPacketType;

```

### `PredictedMovementComponent::HistoryItem::ItemType`
```
typedef MovePredictionType PredictedMovementComponent::HistoryItem::ItemType;

```

### `ProgressAnimation`
```
typedef Rotation ProgressAnimation;

```

### `ProgressHandlerType`
```
typedef Rotation ProgressHandlerType;

```

### `personaScreen::CustomizationState`
```
typedef Rotation personaScreen::CustomizationState;

```

### `PackManifest::PackRedownloadableState`
```
typedef cg::ColorSpace PackManifest::PackRedownloadableState;

```

### `PackScope`
```
typedef BedrockLog::LogChannel PackScope;

```

### `PDPSectionType`
```
typedef DimensionId PDPSectionType;

```

### `PersonaCharacter::Status`
```
typedef Rotation PersonaCharacter::Status;

```

### `persona::PersonaColorOption`
```
typedef ActorLocation persona::PersonaColorOption;

```

### `PersonaPieceHandle::DeserializedPieceMetaData::PieceIdType`
```
typedef cg::ColorSpace PersonaPieceHandle::DeserializedPieceMetaData::PieceIdType;

```

### `personaScreen::ClassicSkinState`
```
enum personaScreen::ClassicSkinState : __int8
{
  OwnedPacks = 0x0,
  PurchasablePacks = 0x1,
  RealmsPlusPacks = 0x2,
  Category = 0x3,
  Skins = 0x4,
};

```

### `personaScreen::TabState`
```
typedef Rotation personaScreen::TabState;

```

### `persona::SelectedOfferSectionType`
```
typedef Rotation persona::SelectedOfferSectionType;

```

### `PurchaseEnabledScreenController::PurchaseStatus`
```
enum PurchaseEnabledScreenController::PurchaseStatus : __int32
{
  NoPurchaseAttemptActive = 0x0,
  CoinPurchaseInProgress = 0x1,
  DownloadInProgress = 0x2,
  InsufficientFundsInProgress = 0x3,
  PurchaseAttemptFinished = 0x4,
  PurchaseInProgress = 0x5,
};

```

### `personaScreen::ClassicSkinPackOrigin`
```
enum personaScreen::ClassicSkinPackOrigin : __int8
{
  Owned = 0x0,
  Purchaseable = 0x1,
  RealmsPlus = 0x2,
};

```

### `PackReportState`
```
typedef ChunkState PackReportState;

```

### `PlayerActionType`
```
typedef cg::ColorSpace PlayerActionType;

```

### `PlayerAuthInputPacket::InputData`
```
typedef Frustum::FrustumSide PlayerAuthInputPacket::InputData;

```

### `PlayerSnapshotStateFlag`
```
typedef DimensionId PlayerSnapshotStateFlag;

```

### `ParticleRenderData::FaceCameraMode`
```
typedef Rotation ParticleRenderData::FaceCameraMode;

```

### `PackIconType`
```
typedef TaskOptions PackIconType;

```

### `PIDMSI_STATUS_VALUE`
```
enum PIDMSI_STATUS_VALUE : __int32
{
  PIDMSI_STATUS_NORMAL = 0x0,
  PIDMSI_STATUS_NEW = 0x1,
  PIDMSI_STATUS_PRELIM = 0x2,
  PIDMSI_STATUS_DRAFT = 0x3,
  PIDMSI_STATUS_INPROGRESS = 0x4,
  PIDMSI_STATUS_EDIT = 0x5,
  PIDMSI_STATUS_REVIEW = 0x6,
  PIDMSI_STATUS_PROOF = 0x7,
  PIDMSI_STATUS_FINAL = 0x8,
  PIDMSI_STATUS_OTHER = 0x7FFF,
};

```

### `POWER_INFORMATION_LEVEL`
```
enum POWER_INFORMATION_LEVEL : __int32
{
  SystemPowerPolicyAc = 0x0,
  SystemPowerPolicyDc = 0x1,
  VerifySystemPolicyAc = 0x2,
  VerifySystemPolicyDc = 0x3,
  SystemPowerCapabilities = 0x4,
  SystemBatteryState = 0x5,
  SystemPowerStateHandler = 0x6,
  ProcessorStateHandler = 0x7,
  SystemPowerPolicyCurrent = 0x8,
  AdministratorPowerPolicy = 0x9,
  SystemReserveHiberFile = 0xA,
  ProcessorInformation = 0xB,
  SystemPowerInformation = 0xC,
  ProcessorStateHandler2 = 0xD,
  LastWakeTime = 0xE,
  LastSleepTime = 0xF,
  SystemExecutionState = 0x10,
  SystemPowerStateNotifyHandler = 0x11,
  ProcessorPowerPolicyAc = 0x12,
  ProcessorPowerPolicyDc = 0x13,
  VerifyProcessorPowerPolicyAc = 0x14,
  VerifyProcessorPowerPolicyDc = 0x15,
  ProcessorPowerPolicyCurrent = 0x16,
  SystemPowerStateLogging = 0x17,
  SystemPowerLoggingEntry = 0x18,
  SetPowerSettingValue = 0x19,
  NotifyUserPowerSetting = 0x1A,
  PowerInformationLevelUnused0 = 0x1B,
  SystemMonitorHiberBootPowerOff = 0x1C,
  SystemVideoState = 0x1D,
  TraceApplicationPowerMessage = 0x1E,
  TraceApplicationPowerMessageEnd = 0x1F,
  ProcessorPerfStates = 0x20,
  ProcessorIdleStates = 0x21,
  ProcessorCap = 0x22,
  SystemWakeSource = 0x23,
  SystemHiberFileInformation = 0x24,
  TraceServicePowerMessage = 0x25,
  ProcessorLoad = 0x26,
  PowerShutdownNotification = 0x27,
  MonitorCapabilities = 0x28,
  SessionPowerInit = 0x29,
  SessionDisplayState = 0x2A,
  PowerRequestCreate = 0x2B,
  PowerRequestAction = 0x2C,
  GetPowerRequestList = 0x2D,
  ProcessorInformationEx = 0x2E,
  NotifyUserModeLegacyPowerEvent = 0x2F,
  GroupPark = 0x30,
  ProcessorIdleDomains = 0x31,
  WakeTimerList = 0x32,
  SystemHiberFileSize = 0x33,
  ProcessorIdleStatesHv = 0x34,
  ProcessorPerfStatesHv = 0x35,
  ProcessorPerfCapHv = 0x36,
  ProcessorSetIdle = 0x37,
  LogicalProcessorIdling = 0x38,
  UserPresence = 0x39,
  PowerSettingNotificationName = 0x3A,
  GetPowerSettingValue = 0x3B,
  IdleResiliency = 0x3C,
  SessionRITState = 0x3D,
  SessionConnectNotification = 0x3E,
  SessionPowerCleanup = 0x3F,
  SessionLockState = 0x40,
  SystemHiberbootState = 0x41,
  PlatformInformation = 0x42,
  PdcInvocation = 0x43,
  MonitorInvocation = 0x44,
  FirmwareTableInformationRegistered = 0x45,
  SetShutdownSelectedTime = 0x46,
  SuspendResumeInvocation = 0x47,
  PlmPowerRequestCreate = 0x48,
  ScreenOff = 0x49,
  CsDeviceNotification = 0x4A,
  PlatformRole = 0x4B,
  LastResumePerformance = 0x4C,
  DisplayBurst = 0x4D,
  ExitLatencySamplingPercentage = 0x4E,
  RegisterSpmPowerSettings = 0x4F,
  PlatformIdleStates = 0x50,
  ProcessorIdleVeto = 0x51,
  PlatformIdleVeto = 0x52,
  SystemBatteryStatePrecise = 0x53,
  ThermalEvent = 0x54,
  PowerRequestActionInternal = 0x55,
  BatteryDeviceState = 0x56,
  PowerInformationInternal = 0x57,
  ThermalStandby = 0x58,
  SystemHiberFileType = 0x59,
  PhysicalPowerButtonPress = 0x5A,
  QueryPotentialDripsConstraint = 0x5B,
  EnergyTrackerCreate = 0x5C,
  EnergyTrackerQuery = 0x5D,
  UpdateBlackBoxRecorder = 0x5E,
  SessionAllowExternalDmaDevices = 0x5F,
  PowerInformationLevelMaximum = 0x60,
};

```

### `POWER_ACTION`
```
enum POWER_ACTION : __int32
{
  PowerActionNone = 0x0,
  PowerActionReserved = 0x1,
  PowerActionSleep = 0x2,
  PowerActionHibernate = 0x3,
  PowerActionShutdown = 0x4,
  PowerActionShutdownReset = 0x5,
  PowerActionShutdownOff = 0x6,
  PowerActionWarmEject = 0x7,
  PowerActionDisplayOff = 0x8,
};

```

### `POWER_MONITOR_REQUEST_REASON`
```
enum POWER_MONITOR_REQUEST_REASON : __int32
{
  MonitorRequestReasonUnknown = 0x0,
  MonitorRequestReasonPowerButton = 0x1,
  MonitorRequestReasonRemoteConnection = 0x2,
  MonitorRequestReasonScMonitorpower = 0x3,
  MonitorRequestReasonUserInput = 0x4,
  MonitorRequestReasonAcDcDisplayBurst = 0x5,
  MonitorRequestReasonUserDisplayBurst = 0x6,
  MonitorRequestReasonPoSetSystemState = 0x7,
  MonitorRequestReasonSetThreadExecutionState = 0x8,
  MonitorRequestReasonFullWake = 0x9,
  MonitorRequestReasonSessionUnlock = 0xA,
  MonitorRequestReasonScreenOffRequest = 0xB,
  MonitorRequestReasonIdleTimeout = 0xC,
  MonitorRequestReasonPolicyChange = 0xD,
  MonitorRequestReasonSleepButton = 0xE,
  MonitorRequestReasonLid = 0xF,
  MonitorRequestReasonBatteryCountChange = 0x10,
  MonitorRequestReasonGracePeriod = 0x11,
  MonitorRequestReasonPnP = 0x12,
  MonitorRequestReasonDP = 0x13,
  MonitorRequestReasonSxTransition = 0x14,
  MonitorRequestReasonSystemIdle = 0x15,
  MonitorRequestReasonNearProximity = 0x16,
  MonitorRequestReasonThermalStandby = 0x17,
  MonitorRequestReasonResumePdc = 0x18,
  MonitorRequestReasonResumeS4 = 0x19,
  MonitorRequestReasonTerminal = 0x1A,
  MonitorRequestReasonPdcSignal = 0x1B,
  MonitorRequestReasonAcDcDisplayBurstSuppressed = 0x1C,
  MonitorRequestReasonSystemStateEntered = 0x1D,
  MonitorRequestReasonWinrt = 0x1E,
  MonitorRequestReasonUserInputKeyboard = 0x1F,
  MonitorRequestReasonUserInputMouse = 0x20,
  MonitorRequestReasonUserInputTouch = 0x21,
  MonitorRequestReasonUserInputPen = 0x22,
  MonitorRequestReasonUserInputAccelerometer = 0x23,
  MonitorRequestReasonUserInputHid = 0x24,
  MonitorRequestReasonUserInputPoUserPresent = 0x25,
  MonitorRequestReasonUserInputSessionSwitch = 0x26,
  MonitorRequestReasonUserInputInitialization = 0x27,
  MonitorRequestReasonPdcSignalWindowsMobilePwrNotif = 0x28,
  MonitorRequestReasonPdcSignalWindowsMobileShell = 0x29,
  MonitorRequestReasonPdcSignalHeyCortana = 0x2A,
  MonitorRequestReasonPdcSignalHolographicShell = 0x2B,
  MonitorRequestReasonPdcSignalFingerprint = 0x2C,
  MonitorRequestReasonDirectedDrips = 0x2D,
  MonitorRequestReasonDim = 0x2E,
  MonitorRequestReasonBuiltinPanel = 0x2F,
  MonitorRequestReasonDisplayRequiredUnDim = 0x30,
  MonitorRequestReasonBatteryCountChangeSuppressed = 0x31,
  MonitorRequestReasonResumeModernStandby = 0x32,
  MonitorRequestReasonMax = 0x33,
};

```

### `POWER_USER_PRESENCE_TYPE`
```
enum POWER_USER_PRESENCE_TYPE : __int32
{
  UserNotPresent = 0x0,
  UserPresent = 0x1,
  UserUnknown = 0xFF,
};

```

### `PROXY_PHASE`
```
enum PROXY_PHASE : __int32
{
  PROXY_CALCSIZE = 0x0,
  PROXY_GETBUFFER = 0x1,
  PROXY_MARSHAL = 0x2,
  PROXY_SENDRECEIVE = 0x3,
  PROXY_UNMARSHAL = 0x4,
};

```

### `PlayerViewMode`
```
typedef DimensionId PlayerViewMode;

```

### `persona::SyncType`
```
typedef cg::ColorSpace persona::SyncType;

```

### `PistonBlockActor::PistonState`
```
enum PistonBlockActor::PistonState : __int8
{
  Retracted = 0x0,
  Expanding = 0x1,
  Expanded = 0x2,
  Retracting = 0x3,
};

```

### `ProfilerLite::ScopeTag`
```
typedef Rotation ProfilerLite::ScopeTag;

```

### `PackStorage::PackStorageMode`
```
enum PackStorage::PackStorageMode : __int8
{
  AppendedFiles = 0x0,
  Raw = 0x1,
};

```

### `persona::StatusCode`
```
typedef Rotation persona::StatusCode;

```

### `PatchRequestSource`
```
typedef DimensionId PatchRequestSource;

```

### `ProductType`
```
typedef Realms::SubscriptionInfo::PurchaseType ProductType;

```

### `PurchaseResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PurchaseResult;

```

### `PackAccessAssetGenerationResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PackAccessAssetGenerationResult;

```

### `PerfContextEvent`
```
typedef OptionID PerfContextEvent;

```

### `ParticleSystem::EffectComponentBase::EffectComponentType`
```
typedef TransformSpace ParticleSystem::EffectComponentBase::EffectComponentType;

```

### `PanoramaRenderer::RotationStyle`
```
typedef Rotation PanoramaRenderer::RotationStyle;

```

### `PaperDollRenderer::RotationStyle`
```
typedef Rotation PaperDollRenderer::RotationStyle;

```

### `PanButtonState`
```
enum PanButtonState : __int32
{
  PanNone = 0x0,
  PanLeft = 0x1,
  PanRight = 0x2,
};

```

### `PageContent::PageType`
```
typedef MinecraftPacketIds PageContent::PageType;

```

### `PositionTrackingDB::ResultCode`
```
typedef BedSleepingResult PositionTrackingDB::ResultCode;

```

### `PositionTrackingDB::TrackingRecord::RecordStatus`
```
typedef BedSleepingResult PositionTrackingDB::TrackingRecord::RecordStatus;

```

### `PickCustomSkinResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PickCustomSkinResult;

```

### `PackParseErrorType`
```
typedef Rotation PackParseErrorType;

```

### `ProcessState`
```
typedef ResourcePackResponse ProcessState;

```

### `PortfolioScreenController::CaptionState`
```
typedef ChunkState PortfolioScreenController::CaptionState;

```

### `ProcessSortOrder`
```
typedef cg::ColorSpace ProcessSortOrder;

```

### `PostCreateWorldAction`
```
typedef IMinecraftEventing::EducationLessonAction PostCreateWorldAction;

```

### `PushNotificationType`
```
typedef cg::ColorSpace PushNotificationType;

```

### `PlayStatus`
```
enum PlayStatus : __int32
{
  LoginSuccess = 0x0,
  LoginFailed_ClientOld = 0x1,
  LoginFailed_ServerOld = 0x2,
  PlayerSpawn = 0x3,
  LoginFailed_InvalidTenant = 0x4,
  LoginFailed_EditionMismatchEduToVanilla = 0x5,
  LoginFailed_EditionMismatchVanillaToEdu = 0x6,
  LoginFailed_ServerFullSubClient = 0x7,
};

```

### `PositionTrackingDBServerBroadcastPacket::Action`
```
typedef RealmsAllowListScreenController::SearchState PositionTrackingDBServerBroadcastPacket::Action;

```

### `PositionTrackingDBClientRequestPacket::Action`
```
enum PositionTrackingDBClientRequestPacket::Action : __int8
{
  Query = 0x0,
};

```

### `PacketViolationSeverity`
```
typedef cg::ColorSpace PacketViolationSeverity;

```

### `PacketViolationType`
```
typedef cg::ColorSpace PacketViolationType;

```

### `ParticleSystem::ParticleAppearanceBillboardBaseComponent::DirectionSettings::Mode`
```
typedef PlayerPermissionLevel ParticleSystem::ParticleAppearanceBillboardBaseComponent::DirectionSettings::Mode;

```

### `ParticleSystem::ParticleVisualEffectEvent::ParticleEffectType`
```
typedef Rotation ParticleSystem::ParticleVisualEffectEvent::ParticleEffectType;

```

### `ProjectileComponent::EAxis`
```
typedef ActorEvent ProjectileComponent::EAxis;

```

### `PersonaValidationResponse::PieceCreationStatus`
```
typedef IMinecraftEventing::AuthenticationOutcome PersonaValidationResponse::PieceCreationStatus;

```

### `Potion::PotionVariant`
```
typedef ActorEvent Potion::PotionVariant;

```

### `PermissionCommand::Action`
```
enum PermissionCommand::Action : __int32
{
  List = 0x0,
  Reload = 0x1,
  Set = 0x2,
};

```

### `PermissionCommand::AvailableCommandPermissionPresets`
```
typedef PlayerPermissionLevel PermissionCommand::AvailableCommandPermissionPresets;

```

### `PandaVariant`
```
typedef Skeleton::SkeletonType PandaVariant;

```

### `Profession`
```
enum Profession : __int32
{
};

```

### `PlaceType`
```
typedef mce::SwapEffect PlaceType;

```

### `PositionTrackingDB::AsyncOperationBase::InternalState`
```
typedef FlightingService::FetchState PositionTrackingDB::AsyncOperationBase::InternalState;

```

### `PLACEHOLDER_STATES`
```
enum PLACEHOLDER_STATES : __int32
{
  PS_NONE = 0x0,
  PS_MARKED_FOR_OFFLINE_AVAILABILITY = 0x1,
  PS_FULL_PRIMARY_STREAM_AVAILABLE = 0x2,
  PS_CREATE_FILE_ACCESSIBLE = 0x4,
  PS_CLOUDFILE_PLACEHOLDER = 0x8,
  PS_DEFAULT = 0x7,
  PS_ALL = 0xF,
};

```

### `PKA_FLAGS`
```
enum PKA_FLAGS : __int32
{
  PKA_SET = 0x0,
  PKA_APPEND = 0x1,
  PKA_DELETE = 0x2,
};

```

### `PyTypeTraits<char const *>::<unnamed_enum_type_desc>`
```
enum PyTypeTraits<char const *>::<unnamed_enum_type_desc> : __int32
{
  type_desc = 0x73,
};

```

### `PyTypeTraits<float>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<float>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<_object *>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<_object *>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<int>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<int>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<unsigned int>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<unsigned int>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<PyStringObject const *>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<PyStringObject const *>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<long>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<long>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<unsigned long>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<unsigned long>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<double>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<double>::<unnamed_enum_type_desc>;

```

### `PyTypeTraits<char>::<unnamed_enum_type_desc>`
```
typedef PyTypeTraits<char const *>::<unnamed_enum_type_desc> PyTypeTraits<char>::<unnamed_enum_type_desc>;

```

### `PatchUpdater::State`
```
enum PatchUpdater::State : __int32
{
  INIT = 0x0,
  UNCHECKED = 0x1,
  CHECKING = 0x2,
  NEED_UPDATE = 0x3,
  UPDATING = 0x4,
  UP_TO_DATE = 0x5,
  UPDATE_FAILURE = 0x6,
  UPDATE_ERROR = 0x7,
  ENGINE_VERSION_ERROR = 0x8,
  VERIFY = 0x9,
  APPLY = 0xA,
};

```

### `PlayFab::PlayFabErrorCode`
```
enum PlayFab::PlayFabErrorCode : __int32
{
  PlayFabErrorHostnameNotFound = 0x1,
  PlayFabErrorConnectionTimeout = 0x2,
  PlayFabErrorConnectionRefused = 0x3,
  PlayFabErrorSocketError = 0x4,
  PlayFabErrorSuccess = 0x0,
  PlayFabErrorUnkownError = 0x1F4,
  PlayFabErrorInvalidParams = 0x3E8,
  PlayFabErrorAccountNotFound = 0x3E9,
  PlayFabErrorAccountBanned = 0x3EA,
  PlayFabErrorInvalidUsernameOrPassword = 0x3EB,
  PlayFabErrorInvalidTitleId = 0x3EC,
  PlayFabErrorInvalidEmailAddress = 0x3ED,
  PlayFabErrorEmailAddressNotAvailable = 0x3EE,
  PlayFabErrorInvalidUsername = 0x3EF,
  PlayFabErrorInvalidPassword = 0x3F0,
  PlayFabErrorUsernameNotAvailable = 0x3F1,
  PlayFabErrorInvalidSteamTicket = 0x3F2,
  PlayFabErrorAccountAlreadyLinked = 0x3F3,
  PlayFabErrorLinkedAccountAlreadyClaimed = 0x3F4,
  PlayFabErrorInvalidFacebookToken = 0x3F5,
  PlayFabErrorAccountNotLinked = 0x3F6,
  PlayFabErrorFailedByPaymentProvider = 0x3F7,
  PlayFabErrorCouponCodeNotFound = 0x3F8,
  PlayFabErrorInvalidContainerItem = 0x3F9,
  PlayFabErrorContainerNotOwned = 0x3FA,
  PlayFabErrorKeyNotOwned = 0x3FB,
  PlayFabErrorInvalidItemIdInTable = 0x3FC,
  PlayFabErrorInvalidReceipt = 0x3FD,
  PlayFabErrorReceiptAlreadyUsed = 0x3FE,
  PlayFabErrorReceiptCancelled = 0x3FF,
  PlayFabErrorGameNotFound = 0x400,
  PlayFabErrorGameModeNotFound = 0x401,
  PlayFabErrorInvalidGoogleToken = 0x402,
  PlayFabErrorUserIsNotPartOfDeveloper = 0x403,
  PlayFabErrorInvalidTitleForDeveloper = 0x404,
  PlayFabErrorTitleNameConflicts = 0x405,
  PlayFabErrorUserisNotValid = 0x406,
  PlayFabErrorValueAlreadyExists = 0x407,
  PlayFabErrorBuildNotFound = 0x408,
  PlayFabErrorPlayerNotInGame = 0x409,
  PlayFabErrorInvalidTicket = 0x40A,
  PlayFabErrorInvalidDeveloper = 0x40B,
  PlayFabErrorInvalidOrderInfo = 0x40C,
  PlayFabErrorRegistrationIncomplete = 0x40D,
  PlayFabErrorInvalidPlatform = 0x40E,
  PlayFabErrorUnknownError = 0x40F,
  PlayFabErrorSteamApplicationNotOwned = 0x410,
  PlayFabErrorWrongSteamAccount = 0x411,
  PlayFabErrorTitleNotActivated = 0x412,
  PlayFabErrorRegistrationSessionNotFound = 0x413,
  PlayFabErrorNoSuchMod = 0x414,
  PlayFabErrorFileNotFound = 0x415,
  PlayFabErrorDuplicateEmail = 0x416,
  PlayFabErrorItemNotFound = 0x417,
  PlayFabErrorItemNotOwned = 0x418,
  PlayFabErrorItemNotRecycleable = 0x419,
  PlayFabErrorItemNotAffordable = 0x41A,
  PlayFabErrorInvalidVirtualCurrency = 0x41B,
  PlayFabErrorWrongVirtualCurrency = 0x41C,
  PlayFabErrorWrongPrice = 0x41D,
  PlayFabErrorNonPositiveValue = 0x41E,
  PlayFabErrorInvalidRegion = 0x41F,
  PlayFabErrorRegionAtCapacity = 0x420,
  PlayFabErrorServerFailedToStart = 0x421,
  PlayFabErrorNameNotAvailable = 0x422,
  PlayFabErrorInsufficientFunds = 0x423,
  PlayFabErrorInvalidDeviceID = 0x424,
  PlayFabErrorInvalidPushNotificationToken = 0x425,
  PlayFabErrorNoRemainingUses = 0x426,
  PlayFabErrorInvalidPaymentProvider = 0x427,
  PlayFabErrorPurchaseInitializationFailure = 0x428,
  PlayFabErrorDuplicateUsername = 0x429,
  PlayFabErrorInvalidBuyerInfo = 0x42A,
  PlayFabErrorNoGameModeParamsSet = 0x42B,
  PlayFabErrorBodyTooLarge = 0x42C,
  PlayFabErrorReservedWordInBody = 0x42D,
  PlayFabErrorInvalidTypeInBody = 0x42E,
  PlayFabErrorInvalidRequest = 0x42F,
  PlayFabErrorReservedEventName = 0x430,
  PlayFabErrorInvalidUserStatistics = 0x431,
  PlayFabErrorNotAuthenticated = 0x432,
  PlayFabErrorStreamAlreadyExists = 0x433,
  PlayFabErrorErrorCreatingStream = 0x434,
  PlayFabErrorStreamNotFound = 0x435,
  PlayFabErrorInvalidAccount = 0x436,
  PlayFabErrorPurchaseDoesNotExist = 0x438,
  PlayFabErrorInvalidPurchaseTransactionStatus = 0x439,
  PlayFabErrorAPINotEnabledForGameClientAccess = 0x43A,
  PlayFabErrorNoPushNotificationARNForTitle = 0x43B,
  PlayFabErrorBuildAlreadyExists = 0x43C,
  PlayFabErrorBuildPackageDoesNotExist = 0x43D,
  PlayFabErrorCustomAnalyticsEventsNotEnabledForTitle = 0x43F,
  PlayFabErrorInvalidSharedGroupId = 0x440,
  PlayFabErrorNotAuthorized = 0x441,
  PlayFabErrorMissingTitleGoogleProperties = 0x442,
  PlayFabErrorInvalidItemProperties = 0x443,
  PlayFabErrorInvalidPSNAuthCode = 0x444,
  PlayFabErrorInvalidItemId = 0x445,
  PlayFabErrorPushNotEnabledForAccount = 0x446,
  PlayFabErrorPushServiceError = 0x447,
  PlayFabErrorReceiptDoesNotContainInAppItems = 0x448,
  PlayFabErrorReceiptContainsMultipleInAppItems = 0x449,
  PlayFabErrorInvalidBundleID = 0x44A,
  PlayFabErrorJavascriptException = 0x44B,
  PlayFabErrorInvalidSessionTicket = 0x44C,
  PlayFabErrorUnableToConnectToDatabase = 0x44D,
  PlayFabErrorInternalServerError = 0x456,
  PlayFabErrorInvalidReportDate = 0x457,
  PlayFabErrorReportNotAvailable = 0x458,
  PlayFabErrorDatabaseThroughputExceeded = 0x459,
  PlayFabErrorInvalidGameTicket = 0x45B,
  PlayFabErrorExpiredGameTicket = 0x45C,
  PlayFabErrorGameTicketDoesNotMatchLobby = 0x45D,
  PlayFabErrorLinkedDeviceAlreadyClaimed = 0x45E,
  PlayFabErrorDeviceAlreadyLinked = 0x45F,
  PlayFabErrorDeviceNotLinked = 0x460,
  PlayFabErrorPartialFailure = 0x461,
  PlayFabErrorPublisherNotSet = 0x462,
  PlayFabErrorServiceUnavailable = 0x463,
  PlayFabErrorVersionNotFound = 0x464,
  PlayFabErrorRevisionNotFound = 0x465,
  PlayFabErrorInvalidPublisherId = 0x466,
  PlayFabErrorDownstreamServiceUnavailable = 0x467,
  PlayFabErrorAPINotIncludedInTitleUsageTier = 0x468,
  PlayFabErrorDAULimitExceeded = 0x469,
  PlayFabErrorAPIRequestLimitExceeded = 0x46A,
  PlayFabErrorInvalidAPIEndpoint = 0x46B,
  PlayFabErrorBuildNotAvailable = 0x46C,
  PlayFabErrorConcurrentEditError = 0x46D,
  PlayFabErrorContentNotFound = 0x46E,
  PlayFabErrorCharacterNotFound = 0x46F,
  PlayFabErrorCloudScriptNotFound = 0x470,
  PlayFabErrorContentQuotaExceeded = 0x471,
  PlayFabErrorInvalidCharacterStatistics = 0x472,
  PlayFabErrorPhotonNotEnabledForTitle = 0x473,
  PlayFabErrorPhotonApplicationNotFound = 0x474,
  PlayFabErrorPhotonApplicationNotAssociatedWithTitle = 0x475,
  PlayFabErrorInvalidEmailOrPassword = 0x476,
  PlayFabErrorFacebookAPIError = 0x477,
  PlayFabErrorInvalidContentType = 0x478,
  PlayFabErrorKeyLengthExceeded = 0x479,
  PlayFabErrorDataLengthExceeded = 0x47A,
  PlayFabErrorTooManyKeys = 0x47B,
  PlayFabErrorFreeTierCannotHaveVirtualCurrency = 0x47C,
  PlayFabErrorMissingAmazonSharedKey = 0x47D,
  PlayFabErrorAmazonValidationError = 0x47E,
  PlayFabErrorInvalidPSNIssuerId = 0x47F,
  PlayFabErrorPSNInaccessible = 0x480,
  PlayFabErrorExpiredAuthToken = 0x481,
  PlayFabErrorFailedToGetEntitlements = 0x482,
  PlayFabErrorFailedToConsumeEntitlement = 0x483,
  PlayFabErrorTradeAcceptingUserNotAllowed = 0x484,
  PlayFabErrorTradeInventoryItemIsAssignedToCharacter = 0x485,
  PlayFabErrorTradeInventoryItemIsBundle = 0x486,
  PlayFabErrorTradeStatusNotValidForCancelling = 0x487,
  PlayFabErrorTradeStatusNotValidForAccepting = 0x488,
  PlayFabErrorTradeDoesNotExist = 0x489,
  PlayFabErrorTradeCancelled = 0x48A,
  PlayFabErrorTradeAlreadyFilled = 0x48B,
  PlayFabErrorTradeWaitForStatusTimeout = 0x48C,
  PlayFabErrorTradeInventoryItemExpired = 0x48D,
  PlayFabErrorTradeMissingOfferedAndAcceptedItems = 0x48E,
  PlayFabErrorTradeAcceptedItemIsBundle = 0x48F,
  PlayFabErrorTradeAcceptedItemIsStackable = 0x490,
  PlayFabErrorTradeInventoryItemInvalidStatus = 0x491,
  PlayFabErrorTradeAcceptedCatalogItemInvalid = 0x492,
  PlayFabErrorTradeAllowedUsersInvalid = 0x493,
  PlayFabErrorTradeInventoryItemDoesNotExist = 0x494,
  PlayFabErrorTradeInventoryItemIsConsumed = 0x495,
  PlayFabErrorTradeInventoryItemIsStackable = 0x496,
  PlayFabErrorTradeAcceptedItemsMismatch = 0x497,
  PlayFabErrorInvalidKongregateToken = 0x498,
  PlayFabErrorFeatureNotConfiguredForTitle = 0x499,
  PlayFabErrorNoMatchingCatalogItemForReceipt = 0x49A,
  PlayFabErrorInvalidCurrencyCode = 0x49B,
  PlayFabErrorNoRealMoneyPriceForCatalogItem = 0x49C,
  PlayFabErrorTradeInventoryItemIsNotTradable = 0x49D,
  PlayFabErrorTradeAcceptedCatalogItemIsNotTradable = 0x49E,
  PlayFabErrorUsersAlreadyFriends = 0x49F,
  PlayFabErrorLinkedIdentifierAlreadyClaimed = 0x4A0,
  PlayFabErrorCustomIdNotLinked = 0x4A1,
  PlayFabErrorTotalDataSizeExceeded = 0x4A2,
  PlayFabErrorDeleteKeyConflict = 0x4A3,
  PlayFabErrorInvalidXboxLiveToken = 0x4A4,
  PlayFabErrorExpiredXboxLiveToken = 0x4A5,
  PlayFabErrorResettableStatisticVersionRequired = 0x4A6,
  PlayFabErrorNotAuthorizedByTitle = 0x4A7,
  PlayFabErrorNoPartnerEnabled = 0x4A8,
  PlayFabErrorInvalidPartnerResponse = 0x4A9,
  PlayFabErrorAPINotEnabledForGameServerAccess = 0x4AA,
  PlayFabErrorStatisticNotFound = 0x4AB,
  PlayFabErrorStatisticNameConflict = 0x4AC,
  PlayFabErrorStatisticVersionClosedForWrites = 0x4AD,
  PlayFabErrorStatisticVersionInvalid = 0x4AE,
  PlayFabErrorAPIClientRequestRateLimitExceeded = 0x4AF,
  PlayFabErrorInvalidJSONContent = 0x4B0,
  PlayFabErrorInvalidDropTable = 0x4B1,
  PlayFabErrorStatisticVersionAlreadyIncrementedForScheduledInterval = 0x4B2,
  PlayFabErrorStatisticCountLimitExceeded = 0x4B3,
  PlayFabErrorStatisticVersionIncrementRateExceeded = 0x4B4,
  PlayFabErrorContainerKeyInvalid = 0x4B5,
  PlayFabErrorCloudScriptExecutionTimeLimitExceeded = 0x4B6,
  PlayFabErrorNoWritePermissionsForEvent = 0x4B7,
  PlayFabErrorCloudScriptFunctionArgumentSizeExceeded = 0x4B8,
  PlayFabErrorCloudScriptAPIRequestCountExceeded = 0x4B9,
  PlayFabErrorCloudScriptAPIRequestError = 0x4BA,
  PlayFabErrorCloudScriptHTTPRequestError = 0x4BB,
  PlayFabErrorInsufficientGuildRole = 0x4BC,
  PlayFabErrorGuildNotFound = 0x4BD,
  PlayFabErrorOverLimit = 0x4BE,
  PlayFabErrorEventNotFound = 0x4BF,
  PlayFabErrorInvalidEventField = 0x4C0,
  PlayFabErrorInvalidEventName = 0x4C1,
  PlayFabErrorCatalogNotConfigured = 0x4C2,
  PlayFabErrorOperationNotSupportedForPlatform = 0x4C3,
  PlayFabErrorSegmentNotFound = 0x4C4,
  PlayFabErrorStoreNotFound = 0x4C5,
  PlayFabErrorInvalidStatisticName = 0x4C6,
  PlayFabErrorTitleNotQualifiedForLimit = 0x4C7,
  PlayFabErrorInvalidServiceLimitLevel = 0x4C8,
  PlayFabErrorServiceLimitLevelInTransition = 0x4C9,
  PlayFabErrorCouponAlreadyRedeemed = 0x4CA,
  PlayFabErrorGameServerBuildSizeLimitExceeded = 0x4CB,
  PlayFabErrorGameServerBuildCountLimitExceeded = 0x4CC,
  PlayFabErrorVirtualCurrencyCountLimitExceeded = 0x4CD,
  PlayFabErrorVirtualCurrencyCodeExists = 0x4CE,
  PlayFabErrorTitleNewsItemCountLimitExceeded = 0x4CF,
  PlayFabErrorInvalidTwitchToken = 0x4D0,
  PlayFabErrorTwitchResponseError = 0x4D1,
  PlayFabErrorProfaneDisplayName = 0x4D2,
  PlayFabErrorUserAlreadyAdded = 0x4D3,
  PlayFabErrorInvalidVirtualCurrencyCode = 0x4D4,
  PlayFabErrorVirtualCurrencyCannotBeDeleted = 0x4D5,
  PlayFabErrorIdentifierAlreadyClaimed = 0x4D6,
  PlayFabErrorIdentifierNotLinked = 0x4D7,
  PlayFabErrorInvalidContinuationToken = 0x4D8,
  PlayFabErrorExpiredContinuationToken = 0x4D9,
  PlayFabErrorInvalidSegment = 0x4DA,
  PlayFabErrorInvalidSessionId = 0x4DB,
  PlayFabErrorSessionLogNotFound = 0x4DC,
  PlayFabErrorInvalidSearchTerm = 0x4DD,
  PlayFabErrorTwoFactorAuthenticationTokenRequired = 0x4DE,
  PlayFabErrorGameServerHostCountLimitExceeded = 0x4DF,
  PlayFabErrorPlayerTagCountLimitExceeded = 0x4E0,
  PlayFabErrorRequestAlreadyRunning = 0x4E1,
  PlayFabErrorActionGroupNotFound = 0x4E2,
  PlayFabErrorMaximumSegmentBulkActionJobsRunning = 0x4E3,
  PlayFabErrorNoActionsOnPlayersInSegmentJob = 0x4E4,
  PlayFabErrorDuplicateStatisticName = 0x4E5,
  PlayFabErrorScheduledTaskNameConflict = 0x4E6,
  PlayFabErrorScheduledTaskCreateConflict = 0x4E7,
  PlayFabErrorInvalidScheduledTaskName = 0x4E8,
  PlayFabErrorInvalidTaskSchedule = 0x4E9,
  PlayFabErrorSteamNotEnabledForTitle = 0x4EA,
  PlayFabErrorLimitNotAnUpgradeOption = 0x4EB,
  PlayFabErrorNoSecretKeyEnabledForCloudScript = 0x4EC,
  PlayFabErrorTaskNotFound = 0x4ED,
  PlayFabErrorTaskInstanceNotFound = 0x4EE,
  PlayFabErrorInvalidIdentityProviderId = 0x4EF,
  PlayFabErrorMisconfiguredIdentityProvider = 0x4F0,
  PlayFabErrorInvalidScheduledTaskType = 0x4F1,
  PlayFabErrorBillingInformationRequired = 0x4F2,
  PlayFabErrorLimitedEditionItemUnavailable = 0x4F3,
  PlayFabErrorInvalidAdPlacementAndReward = 0x4F4,
  PlayFabErrorAllAdPlacementViewsAlreadyConsumed = 0x4F5,
  PlayFabErrorGoogleOAuthNotConfiguredForTitle = 0x4F6,
  PlayFabErrorGoogleOAuthError = 0x4F7,
  PlayFabErrorUserNotFriend = 0x4F8,
  PlayFabErrorInvalidSignature = 0x4F9,
  PlayFabErrorInvalidPublicKey = 0x4FA,
  PlayFabErrorGoogleOAuthNoIdTokenIncludedInResponse = 0x4FB,
  PlayFabErrorStatisticUpdateInProgress = 0x4FC,
  PlayFabErrorLeaderboardVersionNotAvailable = 0x4FD,
  PlayFabErrorStatisticAlreadyHasPrizeTable = 0x4FF,
  PlayFabErrorPrizeTableHasOverlappingRanks = 0x500,
  PlayFabErrorPrizeTableHasMissingRanks = 0x501,
  PlayFabErrorPrizeTableRankStartsAtZero = 0x502,
  PlayFabErrorInvalidStatistic = 0x503,
  PlayFabErrorExpressionParseFailure = 0x504,
  PlayFabErrorExpressionInvokeFailure = 0x505,
  PlayFabErrorExpressionTooLong = 0x506,
  PlayFabErrorDataUpdateRateExceeded = 0x507,
  PlayFabErrorRestrictedEmailDomain = 0x508,
  PlayFabErrorEncryptionKeyDisabled = 0x509,
  PlayFabErrorEncryptionKeyMissing = 0x50A,
  PlayFabErrorEncryptionKeyBroken = 0x50B,
  PlayFabErrorNoSharedSecretKeyConfigured = 0x50C,
  PlayFabErrorSecretKeyNotFound = 0x50D,
  PlayFabErrorPlayerSecretAlreadyConfigured = 0x50E,
  PlayFabErrorAPIRequestsDisabledForTitle = 0x50F,
  PlayFabErrorInvalidSharedSecretKey = 0x510,
  PlayFabErrorPrizeTableHasNoRanks = 0x511,
  PlayFabErrorProfileDoesNotExist = 0x512,
  PlayFabErrorContentS3OriginBucketNotConfigured = 0x513,
  PlayFabErrorInvalidEnvironmentForReceipt = 0x514,
  PlayFabErrorEncryptedRequestNotAllowed = 0x515,
  PlayFabErrorSignedRequestNotAllowed = 0x516,
  PlayFabErrorRequestViewConstraintParamsNotAllowed = 0x517,
  PlayFabErrorBadPartnerConfiguration = 0x518,
  PlayFabErrorXboxBPCertificateFailure = 0x519,
  PlayFabErrorXboxXASSExchangeFailure = 0x51A,
  PlayFabErrorInvalidEntityId = 0x51B,
  PlayFabErrorStatisticValueAggregationOverflow = 0x51C,
  PlayFabErrorEmailMessageFromAddressIsMissing = 0x51D,
  PlayFabErrorEmailMessageToAddressIsMissing = 0x51E,
  PlayFabErrorSmtpServerAuthenticationError = 0x51F,
  PlayFabErrorSmtpServerLimitExceeded = 0x520,
  PlayFabErrorSmtpServerInsufficientStorage = 0x521,
  PlayFabErrorSmtpServerCommunicationError = 0x522,
  PlayFabErrorSmtpServerGeneralFailure = 0x523,
  PlayFabErrorEmailClientTimeout = 0x524,
  PlayFabErrorEmailClientCanceledTask = 0x525,
  PlayFabErrorEmailTemplateMissing = 0x526,
  PlayFabErrorInvalidHostForTitleId = 0x527,
  PlayFabErrorEmailConfirmationTokenDoesNotExist = 0x528,
  PlayFabErrorEmailConfirmationTokenExpired = 0x529,
  PlayFabErrorAccountDeleted = 0x52A,
  PlayFabErrorPlayerSecretNotConfigured = 0x52B,
  PlayFabErrorInvalidSignatureTime = 0x52C,
  PlayFabErrorNoContactEmailAddressFound = 0x52D,
  PlayFabErrorInvalidAuthToken = 0x52E,
  PlayFabErrorAuthTokenDoesNotExist = 0x52F,
  PlayFabErrorAuthTokenExpired = 0x530,
  PlayFabErrorAuthTokenAlreadyUsedToResetPassword = 0x531,
  PlayFabErrorMembershipNameTooLong = 0x532,
  PlayFabErrorMembershipNotFound = 0x533,
  PlayFabErrorGoogleServiceAccountInvalid = 0x534,
  PlayFabErrorGoogleServiceAccountParseFailure = 0x535,
  PlayFabErrorEntityTokenMissing = 0x536,
  PlayFabErrorEntityTokenInvalid = 0x537,
  PlayFabErrorEntityTokenExpired = 0x538,
  PlayFabErrorEntityTokenRevoked = 0x539,
  PlayFabErrorInvalidProductForSubscription = 0x53A,
  PlayFabErrorXboxInaccessible = 0x53B,
  PlayFabErrorSubscriptionAlreadyTaken = 0x53C,
  PlayFabErrorSmtpAddonNotEnabled = 0x53D,
  PlayFabErrorAPIConcurrentRequestLimitExceeded = 0x53E,
  PlayFabErrorXboxRejectedXSTSExchangeRequest = 0x53F,
  PlayFabErrorVariableNotDefined = 0x540,
  PlayFabErrorTemplateVersionNotDefined = 0x541,
  PlayFabErrorFileTooLarge = 0x542,
  PlayFabErrorTitleDeleted = 0x543,
  PlayFabErrorTitleContainsUserAccounts = 0x544,
  PlayFabErrorTitleDeletionPlayerCleanupFailure = 0x545,
  PlayFabErrorEntityFileOperationPending = 0x546,
  PlayFabErrorNoEntityFileOperationPending = 0x547,
  PlayFabErrorEntityProfileVersionMismatch = 0x548,
  PlayFabErrorTemplateVersionTooOld = 0x549,
  PlayFabErrorMembershipDefinitionInUse = 0x54A,
  PlayFabErrorPaymentPageNotConfigured = 0x54B,
  PlayFabErrorFailedLoginAttemptRateLimitExceeded = 0x54C,
  PlayFabErrorEntityBlockedByGroup = 0x54D,
  PlayFabErrorRoleDoesNotExist = 0x54E,
  PlayFabErrorEntityIsAlreadyMember = 0x54F,
  PlayFabErrorDuplicateRoleId = 0x550,
  PlayFabErrorGroupInvitationNotFound = 0x551,
  PlayFabErrorGroupApplicationNotFound = 0x552,
  PlayFabErrorOutstandingInvitationAcceptedInstead = 0x553,
  PlayFabErrorOutstandingApplicationAcceptedInstead = 0x554,
  PlayFabErrorRoleIsGroupDefaultMember = 0x555,
  PlayFabErrorRoleIsGroupAdmin = 0x556,
  PlayFabErrorRoleNameNotAvailable = 0x557,
  PlayFabErrorGroupNameNotAvailable = 0x558,
  PlayFabErrorEmailReportAlreadySent = 0x559,
  PlayFabErrorEmailReportRecipientBlacklisted = 0x55A,
  PlayFabErrorEventNamespaceNotAllowed = 0x55B,
  PlayFabErrorEventEntityNotAllowed = 0x55C,
  PlayFabErrorInvalidEntityType = 0x55D,
  PlayFabErrorNullTokenResultFromAad = 0x55E,
  PlayFabErrorInvalidTokenResultFromAad = 0x55F,
  PlayFabErrorNoValidCertificateForAad = 0x560,
  PlayFabErrorInvalidCertificateForAad = 0x561,
  PlayFabErrorDuplicateDropTableId = 0x562,
  PlayFabErrorMultiplayerServerError = 0x563,
  PlayFabErrorMultiplayerServerTooManyRequests = 0x564,
  PlayFabErrorMultiplayerServerNoContent = 0x565,
  PlayFabErrorMultiplayerServerBadRequest = 0x566,
  PlayFabErrorMultiplayerServerUnauthorized = 0x567,
  PlayFabErrorMultiplayerServerForbidden = 0x568,
  PlayFabErrorMultiplayerServerNotFound = 0x569,
  PlayFabErrorMultiplayerServerConflict = 0x56A,
  PlayFabErrorMultiplayerServerInternalServerError = 0x56B,
  PlayFabErrorMultiplayerServerUnavailable = 0x56C,
  PlayFabErrorExplicitContentDetected = 0x56D,
  PlayFabErrorPIIContentDetected = 0x56E,
  PlayFabErrorInvalidScheduledTaskParameter = 0x56F,
  PlayFabErrorPerEntityEventRateLimitExceeded = 0x570,
  PlayFabErrorTitleDefaultLanguageNotSet = 0x571,
  PlayFabErrorEmailTemplateMissingDefaultVersion = 0x572,
  PlayFabErrorFacebookInstantGamesIdNotLinked = 0x573,
  PlayFabErrorInvalidFacebookInstantGamesSignature = 0x574,
  PlayFabErrorFacebookInstantGamesAuthNotConfiguredForTitle = 0x575,
  PlayFabErrorEntityProfileConstraintValidationFailed = 0x576,
  PlayFabErrorTelemetryIngestionKeyPending = 0x577,
  PlayFabErrorTelemetryIngestionKeyNotFound = 0x578,
  PlayFabErrorStatisticTagRequired = 0x579,
  PlayFabErrorStatisticTagInvalid = 0x57A,
  PlayFabErrorDataIntegrityError = 0x57B,
  PlayFabErrorVirtualCurrencyCannotBeSetToOlderVersion = 0x57C,
  PlayFabErrorVirtualCurrencyMustBeWithinIntegerRange = 0x57D,
  PlayFabErrorEmailTemplateInvalidSyntax = 0x57E,
  PlayFabErrorEmailTemplateMissingCallback = 0x57F,
  PlayFabErrorPushNotificationTemplateInvalidPayload = 0x580,
  PlayFabErrorInvalidLocalizedPushNotificationLanguage = 0x581,
  PlayFabErrorMissingLocalizedPushNotificationMessage = 0x582,
  PlayFabErrorPushNotificationTemplateMissingPlatformPayload = 0x583,
  PlayFabErrorPushNotificationTemplatePayloadContainsInvalidJson = 0x584,
  PlayFabErrorPushNotificationTemplateContainsInvalidIosPayload = 0x585,
  PlayFabErrorPushNotificationTemplateContainsInvalidAndroidPayload = 0x586,
  PlayFabErrorPushNotificationTemplateIosPayloadMissingNotificationBody = 0x587,
  PlayFabErrorPushNotificationTemplateAndroidPayloadMissingNotificationBody = 0x588,
  PlayFabErrorPushNotificationTemplateNotFound = 0x589,
  PlayFabErrorPushNotificationTemplateMissingDefaultVersion = 0x58A,
  PlayFabErrorPushNotificationTemplateInvalidSyntax = 0x58B,
  PlayFabErrorPushNotificationTemplateNoCustomPayloadForV1 = 0x58C,
  PlayFabErrorNoLeaderboardForStatistic = 0x58D,
  PlayFabErrorTitleNewsMissingDefaultLanguage = 0x58E,
  PlayFabErrorTitleNewsNotFound = 0x58F,
  PlayFabErrorTitleNewsDuplicateLanguage = 0x590,
  PlayFabErrorTitleNewsMissingTitleOrBody = 0x591,
  PlayFabErrorTitleNewsInvalidLanguage = 0x592,
  PlayFabErrorEmailRecipientBlacklisted = 0x593,
  PlayFabErrorInvalidGameCenterAuthRequest = 0x594,
  PlayFabErrorGameCenterAuthenticationFailed = 0x595,
  PlayFabErrorCannotEnablePartiesForTitle = 0x596,
  PlayFabErrorPartyError = 0x597,
  PlayFabErrorPartyRequests = 0x598,
  PlayFabErrorPartyNoContent = 0x599,
  PlayFabErrorPartyBadRequest = 0x59A,
  PlayFabErrorPartyUnauthorized = 0x59B,
  PlayFabErrorPartyForbidden = 0x59C,
  PlayFabErrorPartyNotFound = 0x59D,
  PlayFabErrorPartyConflict = 0x59E,
  PlayFabErrorPartyInternalServerError = 0x59F,
  PlayFabErrorPartyUnavailable = 0x5A0,
  PlayFabErrorPartyTooManyRequests = 0x5A1,
  PlayFabErrorPushNotificationTemplateMissingName = 0x5A2,
  PlayFabErrorCannotEnableMultiplayerServersForTitle = 0x5A3,
  PlayFabErrorWriteAttemptedDuringExport = 0x5A4,
  PlayFabErrorMatchmakingEntityInvalid = 0x7D1,
  PlayFabErrorMatchmakingPlayerAttributesInvalid = 0x7D2,
  PlayFabErrorMatchmakingCreateTicketRequestMissing = 0x7D3,
  PlayFabErrorMatchmakingCreateTicketCreatorMissing = 0x7D4,
  PlayFabErrorMatchmakingCreateTicketCreatorIdMissing = 0x7D5,
  PlayFabErrorMatchmakingCreateTicketMemberListMissing = 0x7D6,
  PlayFabErrorMatchmakingCreateTicketGiveUpAfterInvalid = 0x7D7,
  PlayFabErrorMatchmakingTicketIdMissing = 0x7D8,
  PlayFabErrorMatchmakingMatchIdMissing = 0x7D9,
  PlayFabErrorMatchmakingMatchIdIdMissing = 0x7DA,
  PlayFabErrorMatchmakingQueueNameMissing = 0x7DB,
  PlayFabErrorMatchmakingTitleIdMissing = 0x7DC,
  PlayFabErrorMatchmakingTicketIdIdMissing = 0x7DD,
  PlayFabErrorMatchmakingPlayerIdMissing = 0x7DE,
  PlayFabErrorMatchmakingJoinTicketPlayerMissing = 0x7DF,
  PlayFabErrorMatchmakingQueueConfigNotFound = 0x7E0,
  PlayFabErrorMatchmakingMatchNotFound = 0x7E1,
  PlayFabErrorMatchmakingTicketNotFound = 0x7E2,
  PlayFabErrorMatchmakingCreateTicketServerIdentityInvalid = 0x7E3,
  PlayFabErrorMatchmakingCreateTicketClientIdentityInvalid = 0x7E4,
  PlayFabErrorMatchmakingGetTicketPlayerMismatch = 0x7E5,
  PlayFabErrorMatchmakingJoinTicketServerIdentityInvalid = 0x7E6,
  PlayFabErrorMatchmakingJoinTicketPlayerIdentityMismatch = 0x7E7,
  PlayFabErrorMatchmakingCancelTicketServerIdentityInvalid = 0x7E8,
  PlayFabErrorMatchmakingCancelTicketPlayerIdentityMismatch = 0x7E9,
  PlayFabErrorMatchmakingGetMatchIdentityMismatch = 0x7EA,
  PlayFabErrorMatchmakingPlayerIdentityMismatch = 0x7EB,
  PlayFabErrorMatchmakingAlreadyJoinedTicket = 0x7EC,
  PlayFabErrorMatchmakingTicketAlreadyCompleted = 0x7ED,
  PlayFabErrorMatchmakingClientTimeout = 0x7EE,
  PlayFabErrorMatchmakingQueueConfigInvalid = 0x7EF,
  PlayFabErrorMatchmakingMemberProfileInvalid = 0x7F0,
  PlayFabErrorNintendoSwitchDeviceIdNotLinked = 0x7F2,
  PlayFabErrorMatchmakingNotEnabled = 0x7F3,
  PlayFabErrorMatchmakingGetStatisticsIdentityInvalid = 0x7F4,
  PlayFabErrorMatchmakingBucketOwnerNotFound = 0x7F5,
  PlayFabErrorMatchmakingCancelAllTicketsUnauthorized = 0x7F9,
  PlayFabErrorMatchmakingListTicketsUnauthorized = 0x7FA,
  PlayFabErrorMatchmakingPlayerAttributesTooLarge = 0x7FB,
  PlayFabErrorMatchmakingNumberOfPlayersInTicketTooLarge = 0x7FC,
  PlayFabErrorMatchmakingMatchTotalAttributeIsNegative = 0x7FD,
  PlayFabErrorMatchmakingAttributeTypeInvalid = 0x7FE,
  PlayFabErrorMatchmakingMatchTotalAttributeTooLarge = 0x7FF,
  PlayFabErrorMatchmakingMatchTotalAttributeSumTooLarge = 0x800,
  PlayFabErrorMatchmakingTicketUnmatchable = 0x801,
  PlayFabErrorMatchmakingCommonRegionMissing = 0x802,
  PlayFabErrorMatchmakingLatencyMeasurementMissing = 0x803,
  PlayFabErrorMatchmakingStatisticsNotFound = 0x804,
  PlayFabErrorMatchmakingPlayerHasNotJoinedTicket = 0x805,
  PlayFabErrorMatchmakingRateLimitExceeded = 0x806,
  PlayFabErrorMatchmakingTicketMembershipLimitExceeded = 0x807,
  PlayFabErrorTitleConfigNotFound = 0xBB9,
  PlayFabErrorTitleConfigUpdateConflict = 0xBBA,
  PlayFabErrorTitleConfigSerializationError = 0xBBB,
  PlayFabErrorCatalogEntityInvalid = 0xFA1,
  PlayFabErrorCatalogTitleIdMissing = 0xFA2,
  PlayFabErrorCatalogPlayerIdMissing = 0xFA3,
  PlayFabErrorCatalogClientIdentityInvalid = 0xFA4,
  PlayFabErrorCatalogOneOrMoreFilesInvalid = 0xFA5,
  PlayFabErrorCatalogItemMetadataInvalid = 0xFA6,
  PlayFabErrorCatalogItemIdInvalid = 0xFA7,
  PlayFabErrorCatalogSearchParameterInvalid = 0xFA8,
  PlayFabErrorCatalogFeatureDisabled = 0xFA9,
  PlayFabErrorCatalogConfigMissing = 0x1004,
  PlayFabErrorCatalogConfigTooManyContentTypes = 0x1005,
  PlayFabErrorCatalogConfigContentTypeTooLong = 0x1006,
  PlayFabErrorCatalogConfigTooManyTags = 0x1007,
  PlayFabErrorCatalogConfigTagTooLong = 0x1008,
};

```

### `PlayFab::PlayFabEventType`
```
typedef TaskOptions PlayFab::PlayFabEventType;

```

### `PlayFab::EmitEventResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PlayFab::EmitEventResult;

```

### `PlayFab::PlayFabEventBuffer::EventProducingResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PlayFab::PlayFabEventBuffer::EventProducingResult;

```

### `PlayFab::PlayFabEventBuffer::EventConsumingResult`
```
typedef IMinecraftEventing::AuthenticationOutcome PlayFab::PlayFabEventBuffer::EventConsumingResult;

```

### `PlayFab::PlayFabPluginContract`
```
enum PlayFab::PlayFabPluginContract : __int32
{
  PlayFab_Serializer = 0x0,
  PlayFab_Transport = 0x1,
};

```

### `PlayFab::ClientModels::Currency`
```
enum PlayFab::ClientModels::Currency : __int32
{
  CurrencyAED = 0x0,
  CurrencyAFN = 0x1,
  CurrencyALL = 0x2,
  CurrencyAMD = 0x3,
  CurrencyANG = 0x4,
  CurrencyAOA = 0x5,
  CurrencyARS = 0x6,
  CurrencyAUD = 0x7,
  CurrencyAWG = 0x8,
  CurrencyAZN = 0x9,
  CurrencyBAM = 0xA,
  CurrencyBBD = 0xB,
  CurrencyBDT = 0xC,
  CurrencyBGN = 0xD,
  CurrencyBHD = 0xE,
  CurrencyBIF = 0xF,
  CurrencyBMD = 0x10,
  CurrencyBND = 0x11,
  CurrencyBOB = 0x12,
  CurrencyBRL = 0x13,
  CurrencyBSD = 0x14,
  CurrencyBTN = 0x15,
  CurrencyBWP = 0x16,
  CurrencyBYR = 0x17,
  CurrencyBZD = 0x18,
  CurrencyCAD = 0x19,
  CurrencyCDF = 0x1A,
  CurrencyCHF = 0x1B,
  CurrencyCLP = 0x1C,
  CurrencyCNY = 0x1D,
  CurrencyCOP = 0x1E,
  CurrencyCRC = 0x1F,
  CurrencyCUC = 0x20,
  CurrencyCUP = 0x21,
  CurrencyCVE = 0x22,
  CurrencyCZK = 0x23,
  CurrencyDJF = 0x24,
  CurrencyDKK = 0x25,
  CurrencyDOP = 0x26,
  CurrencyDZD = 0x27,
  CurrencyEGP = 0x28,
  CurrencyERN = 0x29,
  CurrencyETB = 0x2A,
  CurrencyEUR = 0x2B,
  CurrencyFJD = 0x2C,
  CurrencyFKP = 0x2D,
  CurrencyGBP = 0x2E,
  CurrencyGEL = 0x2F,
  CurrencyGGP = 0x30,
  CurrencyGHS = 0x31,
  CurrencyGIP = 0x32,
  CurrencyGMD = 0x33,
  CurrencyGNF = 0x34,
  CurrencyGTQ = 0x35,
  CurrencyGYD = 0x36,
  CurrencyHKD = 0x37,
  CurrencyHNL = 0x38,
  CurrencyHRK = 0x39,
  CurrencyHTG = 0x3A,
  CurrencyHUF = 0x3B,
  CurrencyIDR = 0x3C,
  CurrencyILS = 0x3D,
  CurrencyIMP = 0x3E,
  CurrencyINR = 0x3F,
  CurrencyIQD = 0x40,
  CurrencyIRR = 0x41,
  CurrencyISK = 0x42,
  CurrencyJEP = 0x43,
  CurrencyJMD = 0x44,
  CurrencyJOD = 0x45,
  CurrencyJPY = 0x46,
  CurrencyKES = 0x47,
  CurrencyKGS = 0x48,
  CurrencyKHR = 0x49,
  CurrencyKMF = 0x4A,
  CurrencyKPW = 0x4B,
  CurrencyKRW = 0x4C,
  CurrencyKWD = 0x4D,
  CurrencyKYD = 0x4E,
  CurrencyKZT = 0x4F,
  CurrencyLAK = 0x50,
  CurrencyLBP = 0x51,
  CurrencyLKR = 0x52,
  CurrencyLRD = 0x53,
  CurrencyLSL = 0x54,
  CurrencyLYD = 0x55,
  CurrencyMAD = 0x56,
  CurrencyMDL = 0x57,
  CurrencyMGA = 0x58,
  CurrencyMKD = 0x59,
  CurrencyMMK = 0x5A,
  CurrencyMNT = 0x5B,
  CurrencyMOP = 0x5C,
  CurrencyMRO = 0x5D,
  CurrencyMUR = 0x5E,
  CurrencyMVR = 0x5F,
  CurrencyMWK = 0x60,
  CurrencyMXN = 0x61,
  CurrencyMYR = 0x62,
  CurrencyMZN = 0x63,
  CurrencyNAD = 0x64,
  CurrencyNGN = 0x65,
  CurrencyNIO = 0x66,
  CurrencyNOK = 0x67,
  CurrencyNPR = 0x68,
  CurrencyNZD = 0x69,
  CurrencyOMR = 0x6A,
  CurrencyPAB = 0x6B,
  CurrencyPEN = 0x6C,
  CurrencyPGK = 0x6D,
  CurrencyPHP = 0x6E,
  CurrencyPKR = 0x6F,
  CurrencyPLN = 0x70,
  CurrencyPYG = 0x71,
  CurrencyQAR = 0x72,
  CurrencyRON = 0x73,
  CurrencyRSD = 0x74,
  CurrencyRUB = 0x75,
  CurrencyRWF = 0x76,
  CurrencySAR = 0x77,
  CurrencySBD = 0x78,
  CurrencySCR = 0x79,
  CurrencySDG = 0x7A,
  CurrencySEK = 0x7B,
  CurrencySGD = 0x7C,
  CurrencySHP = 0x7D,
  CurrencySLL = 0x7E,
  CurrencySOS = 0x7F,
  CurrencySPL = 0x80,
  CurrencySRD = 0x81,
  CurrencySTD = 0x82,
  CurrencySVC = 0x83,
  CurrencySYP = 0x84,
  CurrencySZL = 0x85,
  CurrencyTHB = 0x86,
  CurrencyTJS = 0x87,
  CurrencyTMT = 0x88,
  CurrencyTND = 0x89,
  CurrencyTOP = 0x8A,
  CurrencyTRY = 0x8B,
  CurrencyTTD = 0x8C,
  CurrencyTVD = 0x8D,
  CurrencyTWD = 0x8E,
  CurrencyTZS = 0x8F,
  CurrencyUAH = 0x90,
  CurrencyUGX = 0x91,
  CurrencyUSD = 0x92,
  CurrencyUYU = 0x93,
  CurrencyUZS = 0x94,
  CurrencyVEF = 0x95,
  CurrencyVND = 0x96,
  CurrencyVUV = 0x97,
  CurrencyWST = 0x98,
  CurrencyXAF = 0x99,
  CurrencyXCD = 0x9A,
  CurrencyXDR = 0x9B,
  CurrencyXOF = 0x9C,
  CurrencyXPF = 0x9D,
  CurrencyYER = 0x9E,
  CurrencyZAR = 0x9F,
  CurrencyZMW = 0xA0,
  CurrencyZWD = 0xA1,
};

```

### `PlayFab::ClientModels::CountryCode`
```
enum PlayFab::ClientModels::CountryCode : __int32
{
  CountryCodeAF = 0x0,
  CountryCodeAX = 0x1,
  CountryCodeAL = 0x2,
  CountryCodeDZ = 0x3,
  CountryCodeAS = 0x4,
  CountryCodeAD = 0x5,
  CountryCodeAO = 0x6,
  CountryCodeAI = 0x7,
  CountryCodeAQ = 0x8,
  CountryCodeAG = 0x9,
  CountryCodeAR = 0xA,
  CountryCodeAM = 0xB,
  CountryCodeAW = 0xC,
  CountryCodeAU = 0xD,
  CountryCodeAT = 0xE,
  CountryCodeAZ = 0xF,
  CountryCodeBS = 0x10,
  CountryCodeBH = 0x11,
  CountryCodeBD = 0x12,
  CountryCodeBB = 0x13,
  CountryCodeBY = 0x14,
  CountryCodeBE = 0x15,
  CountryCodeBZ = 0x16,
  CountryCodeBJ = 0x17,
  CountryCodeBM = 0x18,
  CountryCodeBT = 0x19,
  CountryCodeBO = 0x1A,
  CountryCodeBQ = 0x1B,
  CountryCodeBA = 0x1C,
  CountryCodeBW = 0x1D,
  CountryCodeBV = 0x1E,
  CountryCodeBR = 0x1F,
  CountryCodeIO = 0x20,
  CountryCodeBN = 0x21,
  CountryCodeBG = 0x22,
  CountryCodeBF = 0x23,
  CountryCodeBI = 0x24,
  CountryCodeKH = 0x25,
  CountryCodeCM = 0x26,
  CountryCodeCA = 0x27,
  CountryCodeCV = 0x28,
  CountryCodeKY = 0x29,
  CountryCodeCF = 0x2A,
  CountryCodeTD = 0x2B,
  CountryCodeCL = 0x2C,
  CountryCodeCN = 0x2D,
  CountryCodeCX = 0x2E,
  CountryCodeCC = 0x2F,
  CountryCodeCO = 0x30,
  CountryCodeKM = 0x31,
  CountryCodeCG = 0x32,
  CountryCodeCD = 0x33,
  CountryCodeCK = 0x34,
  CountryCodeCR = 0x35,
  CountryCodeCI = 0x36,
  CountryCodeHR = 0x37,
  CountryCodeCU = 0x38,
  CountryCodeCW = 0x39,
  CountryCodeCY = 0x3A,
  CountryCodeCZ = 0x3B,
  CountryCodeDK = 0x3C,
  CountryCodeDJ = 0x3D,
  CountryCodeDM = 0x3E,
  CountryCodeDO = 0x3F,
  CountryCodeEC = 0x40,
  CountryCodeEG = 0x41,
  CountryCodeSV = 0x42,
  CountryCodeGQ = 0x43,
  CountryCodeER = 0x44,
  CountryCodeEE = 0x45,
  CountryCodeET = 0x46,
  CountryCodeFK = 0x47,
  CountryCodeFO = 0x48,
  CountryCodeFJ = 0x49,
  CountryCodeFI = 0x4A,
  CountryCodeFR = 0x4B,
  CountryCodeGF = 0x4C,
  CountryCodePF = 0x4D,
  CountryCodeTF = 0x4E,
  CountryCodeGA = 0x4F,
  CountryCodeGM = 0x50,
  CountryCodeGE = 0x51,
  CountryCodeDE = 0x52,
  CountryCodeGH = 0x53,
  CountryCodeGI = 0x54,
  CountryCodeGR = 0x55,
  CountryCodeGL = 0x56,
  CountryCodeGD = 0x57,
  CountryCodeGP = 0x58,
  CountryCodeGU = 0x59,
  CountryCodeGT = 0x5A,
  CountryCodeGG = 0x5B,
  CountryCodeGN = 0x5C,
  CountryCodeGW = 0x5D,
  CountryCodeGY = 0x5E,
  CountryCodeHT = 0x5F,
  CountryCodeHM = 0x60,
  CountryCodeVA = 0x61,
  CountryCodeHN = 0x62,
  CountryCodeHK = 0x63,
  CountryCodeHU = 0x64,
  CountryCodeIS = 0x65,
  CountryCodeIN = 0x66,
  CountryCodeID = 0x67,
  CountryCodeIR = 0x68,
  CountryCodeIQ = 0x69,
  CountryCodeIE = 0x6A,
  CountryCodeIM = 0x6B,
  CountryCodeIL = 0x6C,
  CountryCodeIT = 0x6D,
  CountryCodeJM = 0x6E,
  CountryCodeJP = 0x6F,
  CountryCodeJE = 0x70,
  CountryCodeJO = 0x71,
  CountryCodeKZ = 0x72,
  CountryCodeKE = 0x73,
  CountryCodeKI = 0x74,
  CountryCodeKP = 0x75,
  CountryCodeKR = 0x76,
  CountryCodeKW = 0x77,
  CountryCodeKG = 0x78,
  CountryCodeLA = 0x79,
  CountryCodeLV = 0x7A,
  CountryCodeLB = 0x7B,
  CountryCodeLS = 0x7C,
  CountryCodeLR = 0x7D,
  CountryCodeLY = 0x7E,
  CountryCodeLI = 0x7F,
  CountryCodeLT = 0x80,
  CountryCodeLU = 0x81,
  CountryCodeMO = 0x82,
  CountryCodeMK = 0x83,
  CountryCodeMG = 0x84,
  CountryCodeMW = 0x85,
  CountryCodeMY = 0x86,
  CountryCodeMV = 0x87,
  CountryCodeML = 0x88,
  CountryCodeMT = 0x89,
  CountryCodeMH = 0x8A,
  CountryCodeMQ = 0x8B,
  CountryCodeMR = 0x8C,
  CountryCodeMU = 0x8D,
  CountryCodeYT = 0x8E,
  CountryCodeMX = 0x8F,
  CountryCodeFM = 0x90,
  CountryCodeMD = 0x91,
  CountryCodeMC = 0x92,
  CountryCodeMN = 0x93,
  CountryCodeME = 0x94,
  CountryCodeMS = 0x95,
  CountryCodeMA = 0x96,
  CountryCodeMZ = 0x97,
  CountryCodeMM = 0x98,
  CountryCodeNA = 0x99,
  CountryCodeNR = 0x9A,
  CountryCodeNP = 0x9B,
  CountryCodeNL = 0x9C,
  CountryCodeNC = 0x9D,
  CountryCodeNZ = 0x9E,
  CountryCodeNI = 0x9F,
  CountryCodeNE = 0xA0,
  CountryCodeNG = 0xA1,
  CountryCodeNU = 0xA2,
  CountryCodeNF = 0xA3,
  CountryCodeMP = 0xA4,
  CountryCodeNO = 0xA5,
  CountryCodeOM = 0xA6,
  CountryCodePK = 0xA7,
  CountryCodePW = 0xA8,
  CountryCodePS = 0xA9,
  CountryCodePA = 0xAA,
  CountryCodePG = 0xAB,
  CountryCodePY = 0xAC,
  CountryCodePE = 0xAD,
  CountryCodePH = 0xAE,
  CountryCodePN = 0xAF,
  CountryCodePL = 0xB0,
  CountryCodePT = 0xB1,
  CountryCodePR = 0xB2,
  CountryCodeQA = 0xB3,
  CountryCodeRE = 0xB4,
  CountryCodeRO = 0xB5,
  CountryCodeRU = 0xB6,
  CountryCodeRW = 0xB7,
  CountryCodeBL = 0xB8,
  CountryCodeSH = 0xB9,
  CountryCodeKN = 0xBA,
  CountryCodeLC = 0xBB,
  CountryCodeMF = 0xBC,
  CountryCodePM = 0xBD,
  CountryCodeVC = 0xBE,
  CountryCodeWS = 0xBF,
  CountryCodeSM = 0xC0,
  CountryCodeST = 0xC1,
  CountryCodeSA = 0xC2,
  CountryCodeSN = 0xC3,
  CountryCodeRS = 0xC4,
  CountryCodeSC = 0xC5,
  CountryCodeSL = 0xC6,
  CountryCodeSG = 0xC7,
  CountryCodeSX = 0xC8,
  CountryCodeSK = 0xC9,
  CountryCodeSI = 0xCA,
  CountryCodeSB = 0xCB,
  CountryCodeSO = 0xCC,
  CountryCodeZA = 0xCD,
  CountryCodeGS = 0xCE,
  CountryCodeSS = 0xCF,
  CountryCodeES = 0xD0,
  CountryCodeLK = 0xD1,
  CountryCodeSD = 0xD2,
  CountryCodeSR = 0xD3,
  CountryCodeSJ = 0xD4,
  CountryCodeSZ = 0xD5,
  CountryCodeSE = 0xD6,
  CountryCodeCH = 0xD7,
  CountryCodeSY = 0xD8,
  CountryCodeTW = 0xD9,
  CountryCodeTJ = 0xDA,
  CountryCodeTZ = 0xDB,
  CountryCodeTH = 0xDC,
  CountryCodeTL = 0xDD,
  CountryCodeTG = 0xDE,
  CountryCodeTK = 0xDF,
  CountryCodeTO = 0xE0,
  CountryCodeTT = 0xE1,
  CountryCodeTN = 0xE2,
  CountryCodeTR = 0xE3,
  CountryCodeTM = 0xE4,
  CountryCodeTC = 0xE5,
  CountryCodeTV = 0xE6,
  CountryCodeUG = 0xE7,
  CountryCodeUA = 0xE8,
  CountryCodeAE = 0xE9,
  CountryCodeGB = 0xEA,
  CountryCodeUS = 0xEB,
  CountryCodeUM = 0xEC,
  CountryCodeUY = 0xED,
  CountryCodeUZ = 0xEE,
  CountryCodeVU = 0xEF,
  CountryCodeVE = 0xF0,
  CountryCodeVN = 0xF1,
  CountryCodeVG = 0xF2,
  CountryCodeVI = 0xF3,
  CountryCodeWF = 0xF4,
  CountryCodeEH = 0xF5,
  CountryCodeYE = 0xF6,
  CountryCodeZM = 0xF7,
  CountryCodeZW = 0xF8,
};

```

### `PlayFab::ClientModels::SubscriptionProviderStatus`
```
enum PlayFab::ClientModels::SubscriptionProviderStatus : __int32
{
  SubscriptionProviderStatusNoError = 0x0,
  SubscriptionProviderStatusCancelled = 0x1,
  SubscriptionProviderStatusUnknownError = 0x2,
  SubscriptionProviderStatusBillingError = 0x3,
  SubscriptionProviderStatusProductUnavailable = 0x4,
  SubscriptionProviderStatusCustomerDidNotAcceptPriceChange = 0x5,
  SubscriptionProviderStatusFreeTrial = 0x6,
  SubscriptionProviderStatusPaymentPending = 0x7,
};

```

### `PlayFab::ClientModels::UserOrigination`
```
enum PlayFab::ClientModels::UserOrigination : __int32
{
  UserOriginationOrganic = 0x0,
  UserOriginationSteam = 0x1,
  UserOriginationGoogle = 0x2,
  UserOriginationAmazon = 0x3,
  UserOriginationFacebook = 0x4,
  UserOriginationKongregate = 0x5,
  UserOriginationGamersFirst = 0x6,
  UserOriginationUnknown = 0x7,
  UserOriginationIOS = 0x8,
  UserOriginationLoadTest = 0x9,
  UserOriginationAndroid = 0xA,
  UserOriginationPSN = 0xB,
  UserOriginationGameCenter = 0xC,
  UserOriginationCustomId = 0xD,
  UserOriginationXboxLive = 0xE,
  UserOriginationParse = 0xF,
  UserOriginationTwitch = 0x10,
  UserOriginationWindowsHello = 0x11,
  UserOriginationServerCustomId = 0x12,
  UserOriginationNintendoSwitchDeviceId = 0x13,
  UserOriginationFacebookInstantGamesId = 0x14,
  UserOriginationOpenIdConnect = 0x15,
};

```

### `PlayFab::ClientModels::TransactionStatus`
```
enum PlayFab::ClientModels::TransactionStatus : __int32
{
  TransactionStatusCreateCart = 0x0,
  TransactionStatusInit = 0x1,
  TransactionStatusApproved = 0x2,
  TransactionStatusSucceeded = 0x3,
  TransactionStatusFailedByProvider = 0x4,
  TransactionStatusDisputePending = 0x5,
  TransactionStatusRefundPending = 0x6,
  TransactionStatusRefunded = 0x7,
  TransactionStatusRefundFailed = 0x8,
  TransactionStatusChargedBack = 0x9,
  TransactionStatusFailedByUber = 0xA,
  TransactionStatusFailedByPlayFab = 0xB,
  TransactionStatusRevoked = 0xC,
  TransactionStatusTradePending = 0xD,
  TransactionStatusTraded = 0xE,
  TransactionStatusUpgraded = 0xF,
  TransactionStatusStackPending = 0x10,
  TransactionStatusStacked = 0x11,
  TransactionStatusOther = 0x12,
  TransactionStatusFailed = 0x13,
};

```

### `PlayFab::ClientModels::MatchmakeStatus`
```
enum PlayFab::ClientModels::MatchmakeStatus : __int32
{
  MatchmakeStatusComplete = 0x0,
  MatchmakeStatusWaiting = 0x1,
  MatchmakeStatusGameNotFound = 0x2,
  MatchmakeStatusNoAvailableSlots = 0x3,
  MatchmakeStatusSessionClosed = 0x4,
};

```

### `PlayFab::ClientModels::Region`
```
enum PlayFab::ClientModels::Region : __int32
{
  RegionUSCentral = 0x0,
  RegionUSEast = 0x1,
  RegionEUWest = 0x2,
  RegionSingapore = 0x3,
  RegionJapan = 0x4,
  RegionBrazil = 0x5,
  RegionAustralia = 0x6,
};

```

### `PlayFab::ClientModels::LoginIdentityProvider`
```
enum PlayFab::ClientModels::LoginIdentityProvider : __int32
{
  LoginIdentityProviderUnknown = 0x0,
  LoginIdentityProviderPlayFab = 0x1,
  LoginIdentityProviderCustom = 0x2,
  LoginIdentityProviderGameCenter = 0x3,
  LoginIdentityProviderGooglePlay = 0x4,
  LoginIdentityProviderSteam = 0x5,
  LoginIdentityProviderXBoxLive = 0x6,
  LoginIdentityProviderPSN = 0x7,
  LoginIdentityProviderKongregate = 0x8,
  LoginIdentityProviderFacebook = 0x9,
  LoginIdentityProviderIOSDevice = 0xA,
  LoginIdentityProviderAndroidDevice = 0xB,
  LoginIdentityProviderTwitch = 0xC,
  LoginIdentityProviderWindowsHello = 0xD,
  LoginIdentityProviderGameServer = 0xE,
  LoginIdentityProviderCustomServer = 0xF,
  LoginIdentityProviderNintendoSwitch = 0x10,
  LoginIdentityProviderFacebookInstantGames = 0x11,
  LoginIdentityProviderOpenIdConnect = 0x12,
};

```

### `PlayFab::ClientModels::ContinentCode`
```
enum PlayFab::ClientModels::ContinentCode : __int32
{
  ContinentCodeAF = 0x0,
  ContinentCodeAN = 0x1,
  ContinentCodeAS = 0x2,
  ContinentCodeEU = 0x3,
  ContinentCodeNA = 0x4,
  ContinentCodeOC = 0x5,
  ContinentCodeSA = 0x6,
};

```

### `PlayFab::ClientModels::SourceType`
```
enum PlayFab::ClientModels::SourceType : __int32
{
  SourceTypeAdmin = 0x0,
  SourceTypeBackEnd = 0x1,
  SourceTypeGameClient = 0x2,
  SourceTypeGameServer = 0x3,
  SourceTypePartner = 0x4,
  SourceTypeCustom = 0x5,
  SourceTypeAPI = 0x6,
};

```

### `PlayFab::ClientModels::TitleActivationStatus`
```
enum PlayFab::ClientModels::TitleActivationStatus : __int32
{
  TitleActivationStatusNone = 0x0,
  TitleActivationStatusActivatedTitleKey = 0x1,
  TitleActivationStatusPendingSteam = 0x2,
  TitleActivationStatusActivatedSteam = 0x3,
  TitleActivationStatusRevokedSteam = 0x4,
};

```

### `PlayFab::ClientModels::GameInstanceState`
```
enum PlayFab::ClientModels::GameInstanceState : __int32
{
  GameInstanceStateOpen = 0x0,
  GameInstanceStateClosed = 0x1,
};

```

### `PlayFab::ClientModels::PushNotificationPlatform`
```
enum PlayFab::ClientModels::PushNotificationPlatform : __int32
{
  PushNotificationPlatformApplePushNotificationService = 0x0,
  PushNotificationPlatformGoogleCloudMessaging = 0x1,
};

```

### `PlayFab::ClientModels::TradeStatus`
```
enum PlayFab::ClientModels::TradeStatus : __int32
{
  TradeStatusInvalid = 0x0,
  TradeStatusOpening = 0x1,
  TradeStatusOpen = 0x2,
  TradeStatusAccepting = 0x3,
  TradeStatusAccepted = 0x4,
  TradeStatusFilled = 0x5,
  TradeStatusCancelled = 0x6,
};

```

### `PlayFab::ClientModels::UserDataPermission`
```
enum PlayFab::ClientModels::UserDataPermission : __int32
{
  UserDataPermissionPrivate = 0x0,
  UserDataPermissionPublic = 0x1,
};

```

### `PlayFab::ClientModels::CloudScriptRevisionOption`
```
enum PlayFab::ClientModels::CloudScriptRevisionOption : __int32
{
  CloudScriptRevisionOptionLive = 0x0,
  CloudScriptRevisionOptionLatest = 0x1,
  CloudScriptRevisionOptionSpecific = 0x2,
};

```

### `PlayFab::ClientModels::EmailVerificationStatus`
```
enum PlayFab::ClientModels::EmailVerificationStatus : __int32
{
  EmailVerificationStatusUnverified = 0x0,
  EmailVerificationStatusPending = 0x1,
  EmailVerificationStatusConfirmed = 0x2,
};

```

### `PlayFab::CloudScriptModels::CloudScriptRevisionOption`
```
typedef PlayFab::ClientModels::CloudScriptRevisionOption PlayFab::CloudScriptModels::CloudScriptRevisionOption;

```

### `PlayFab::DataModels::OperationTypes`
```
enum PlayFab::DataModels::OperationTypes : __int32
{
  OperationTypesCreated = 0x0,
  OperationTypesUpdated = 0x1,
  OperationTypesDeleted = 0x2,
  OperationTypesNone = 0x3,
};

```

### `PlayFab::EventPipelineKey`
```
typedef CatalogProviderId PlayFab::EventPipelineKey;

```

### `PlayFab::GroupsModels::OperationTypes`
```
typedef PlayFab::DataModels::OperationTypes PlayFab::GroupsModels::OperationTypes;

```

### `PlayFab::MultiplayerModels::AzureRegion`
```
enum PlayFab::MultiplayerModels::AzureRegion : __int32
{
  AzureRegionAustraliaEast = 0x0,
  AzureRegionAustraliaSoutheast = 0x1,
  AzureRegionBrazilSouth = 0x2,
  AzureRegionCentralUs = 0x3,
  AzureRegionEastAsia = 0x4,
  AzureRegionEastUs = 0x5,
  AzureRegionEastUs2 = 0x6,
  AzureRegionJapanEast = 0x7,
  AzureRegionJapanWest = 0x8,
  AzureRegionNorthCentralUs = 0x9,
  AzureRegionNorthEurope = 0xA,
  AzureRegionSouthCentralUs = 0xB,
  AzureRegionSoutheastAsia = 0xC,
  AzureRegionWestEurope = 0xD,
  AzureRegionWestUs = 0xE,
  AzureRegionChinaEast2 = 0xF,
  AzureRegionChinaNorth2 = 0x10,
};

```

### `PlayFab::MultiplayerModels::TitleMultiplayerServerEnabledStatus`
```
enum PlayFab::MultiplayerModels::TitleMultiplayerServerEnabledStatus : __int32
{
  TitleMultiplayerServerEnabledStatusInitializing = 0x0,
  TitleMultiplayerServerEnabledStatusEnabled = 0x1,
  TitleMultiplayerServerEnabledStatusDisabled = 0x2,
};

```

### `PlayFab::MultiplayerModels::AzureVmSize`
```
enum PlayFab::MultiplayerModels::AzureVmSize : __int32
{
  AzureVmSizeStandard_D1_v2 = 0x0,
  AzureVmSizeStandard_D2_v2 = 0x1,
  AzureVmSizeStandard_D3_v2 = 0x2,
  AzureVmSizeStandard_D4_v2 = 0x3,
  AzureVmSizeStandard_D5_v2 = 0x4,
  AzureVmSizeStandard_A1_v2 = 0x5,
  AzureVmSizeStandard_A2_v2 = 0x6,
  AzureVmSizeStandard_A4_v2 = 0x7,
  AzureVmSizeStandard_A8_v2 = 0x8,
  AzureVmSizeStandard_F1 = 0x9,
  AzureVmSizeStandard_F2 = 0xA,
  AzureVmSizeStandard_F4 = 0xB,
  AzureVmSizeStandard_F8 = 0xC,
  AzureVmSizeStandard_F16 = 0xD,
  AzureVmSizeStandard_F2s_v2 = 0xE,
  AzureVmSizeStandard_F4s_v2 = 0xF,
  AzureVmSizeStandard_F8s_v2 = 0x10,
  AzureVmSizeStandard_F16s_v2 = 0x11,
  AzureVmSizeStandard_A1 = 0x12,
  AzureVmSizeStandard_A2 = 0x13,
  AzureVmSizeStandard_A3 = 0x14,
  AzureVmSizeStandard_A4 = 0x15,
};

```

### `PlayFab::MultiplayerModels::ProtocolType`
```
enum PlayFab::MultiplayerModels::ProtocolType : __int32
{
  ProtocolTypeTCP = 0x0,
  ProtocolTypeUDP = 0x1,
};

```

### `PlayFab::MultiplayerModels::ContainerFlavor`
```
enum PlayFab::MultiplayerModels::ContainerFlavor : __int32
{
  ContainerFlavorManagedWindowsServerCore = 0x0,
  ContainerFlavorCustomLinux = 0x1,
  ContainerFlavorManagedWindowsServerCorePreview = 0x2,
};

```

### `PlayFab::ProfilesModels::EffectType`
```
enum PlayFab::ProfilesModels::EffectType : __int32
{
  EffectTypeAllow = 0x0,
  EffectTypeDeny = 0x1,
};

```

### `PlayFab::ProfilesModels::OperationTypes`
```
typedef PlayFab::DataModels::OperationTypes PlayFab::ProfilesModels::OperationTypes;

```

### `PS_Dict_Keys_`
```
enum PS_Dict_Keys_ : __int32
{
  PS_DICT_FONT_TYPE = 0x0,
  PS_DICT_FONT_MATRIX = 0x1,
  PS_DICT_FONT_BBOX = 0x2,
  PS_DICT_PAINT_TYPE = 0x3,
  PS_DICT_FONT_NAME = 0x4,
  PS_DICT_UNIQUE_ID = 0x5,
  PS_DICT_NUM_CHAR_STRINGS = 0x6,
  PS_DICT_CHAR_STRING_KEY = 0x7,
  PS_DICT_CHAR_STRING = 0x8,
  PS_DICT_ENCODING_TYPE = 0x9,
  PS_DICT_ENCODING_ENTRY = 0xA,
  PS_DICT_NUM_SUBRS = 0xB,
  PS_DICT_SUBR = 0xC,
  PS_DICT_STD_HW = 0xD,
  PS_DICT_STD_VW = 0xE,
  PS_DICT_NUM_BLUE_VALUES = 0xF,
  PS_DICT_BLUE_VALUE = 0x10,
  PS_DICT_BLUE_FUZZ = 0x11,
  PS_DICT_NUM_OTHER_BLUES = 0x12,
  PS_DICT_OTHER_BLUE = 0x13,
  PS_DICT_NUM_FAMILY_BLUES = 0x14,
  PS_DICT_FAMILY_BLUE = 0x15,
  PS_DICT_NUM_FAMILY_OTHER_BLUES = 0x16,
  PS_DICT_FAMILY_OTHER_BLUE = 0x17,
  PS_DICT_BLUE_SCALE = 0x18,
  PS_DICT_BLUE_SHIFT = 0x19,
  PS_DICT_NUM_STEM_SNAP_H = 0x1A,
  PS_DICT_STEM_SNAP_H = 0x1B,
  PS_DICT_NUM_STEM_SNAP_V = 0x1C,
  PS_DICT_STEM_SNAP_V = 0x1D,
  PS_DICT_FORCE_BOLD = 0x1E,
  PS_DICT_RND_STEM_UP = 0x1F,
  PS_DICT_MIN_FEATURE = 0x20,
  PS_DICT_LEN_IV = 0x21,
  PS_DICT_PASSWORD = 0x22,
  PS_DICT_LANGUAGE_GROUP = 0x23,
  PS_DICT_VERSION = 0x24,
  PS_DICT_NOTICE = 0x25,
  PS_DICT_FULL_NAME = 0x26,
  PS_DICT_FAMILY_NAME = 0x27,
  PS_DICT_WEIGHT = 0x28,
  PS_DICT_IS_FIXED_PITCH = 0x29,
  PS_DICT_UNDERLINE_POSITION = 0x2A,
  PS_DICT_UNDERLINE_THICKNESS = 0x2B,
  PS_DICT_FS_TYPE = 0x2C,
  PS_DICT_ITALIC_ANGLE = 0x2D,
  PS_DICT_MAX = 0x2D,
};

```

### `PS_Hint_Type_`
```
enum PS_Hint_Type_ : __int32
{
  PS_HINT_TYPE_1 = 0x1,
  PS_HINT_TYPE_2 = 0x2,
};

```

