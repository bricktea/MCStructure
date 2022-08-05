# R
### `ResourceFileSystem`
Name | Value
-|-


### `ResourcePacksScreenController::PackRestriction`
Name | Value
-|-
Unrestricted | `0`
Low | `1`
Medium | `2`
High | `3`


### `Remapping::ActionEnum`
Name | Value
-|-
Use | `0`
Place | `1`


### `RealmsOfferTier`
Name | Value
-|-
Offer2Player | `0`
Offer10Player | `1`
Offer16Player | `2`


### `RealmsOfferNumber`
Name | Value
-|-


### `RedefinitionMode`
Name | Value
-|-
KeepCurrent | `0`
UpdateToNewDefault | `1`


### `RakNet::DynDnsResultCode`
Name | Value
-|-
RC_SUCCESS | `0`
RC_DNS_ALREADY_SET | `1`
RC_NO_CHANGE | `2`
RC_NOT_DONATOR | `3`
RC_NO_HOST | `4`
RC_BAD_AUTH | `5`
RC_NOT_YOURS | `6`
RC_ABUSE | `7`
RC_TCP_FAILED_TO_START | `8`
RC_TCP_DID_NOT_CONNECT | `9`
RC_UNKNOWN_RESULT | `10`
RC_PARSING_FAILURE | `11`
RC_CONNECTION_LOST_WITHOUT_RESPONSE | `12`
RC_BAD_AGENT | `13`
RC_BAD_SYS | `14`
RC_DNS_ERROR | `15`
RC_NOT_FQDN | `16`
RC_NUM_HOST | `17`
RC_911 | `18`
RC_DYNDNS_TIMEOUT | `19`


### `RealmsAPI::InviteAction`
Name | Value
-|-


### `Realms::World::State`
Name | Value
-|-
Uninitialized | `0`
Closed | `1`
Open | `2`
End | `3`


### `RawInputType`
Name | Value
-|-


### `RealmsAPI::Compatibility`
Name | Value
-|-
Xbl | `1`
Guest | `2`
Other | `3`


### `Realms::SubscriptionInfo::PurchaseType`
Name | Value
-|-
Consumable | `0`
Subscription | `1`


### `ResourceInformation::ResourceType`
Name | Value
-|-


### `RealmsPurchaseIntent`
Name | Value
-|-
CreateRealm | `0`
ExtendRealm | `1`
RenewRealm | `2`


### `RealmsPlusTabIndex`
Name | Value
-|-


### `RopeWave::Direction`
Name | Value
-|-
StartToEnd | `0`
EndToStart | `1`


### `rendergraph::ResourceBinding::AccessType`
Name | Value
-|-
UNSPECIFIED | `0`
BUFFER | `2`


### `rendergraph::ResourceBinding::ResourceType`
Name | Value
-|-


### `rendergraph::ResourceBinding::ShaderStage`
Name | Value
-|-


### `RealmsOfferType`
Name | Value
-|-
OfferConsumable | `0`
OfferSubscription | `1`


### `RealmsOfferPeriod`
Name | Value
-|-
Offer30Days | `0`
Offer180Days | `1`
OfferMonthly | `2`


### `ResourceLoadType`
Name | Value
-|-


### `rapidjson::ParseErrorCode`
Name | Value
-|-
kParseErrorNone | `0`
kParseErrorDocumentEmpty | `1`
kParseErrorDocumentRootNotSingular | `2`
kParseErrorValueInvalid | `3`
kParseErrorObjectMissName | `4`
kParseErrorObjectMissColon | `5`
kParseErrorObjectMissCommaOrCurlyBracket | `6`
kParseErrorArrayMissCommaOrSquareBracket | `7`
kParseErrorStringUnicodeEscapeInvalidHex | `8`
kParseErrorStringUnicodeSurrogateInvalid | `9`
kParseErrorStringEscapeInvalid | `10`
kParseErrorStringMissQuotationMark | `11`
kParseErrorStringInvalidEncoding | `12`
kParseErrorNumberTooBig | `13`
kParseErrorNumberMissFraction | `14`
kParseErrorNumberMissExponent | `15`
kParseErrorTermination | `16`
kParseErrorUnspecificSyntaxError | `17`


### `rapidjson::UTFType`
Name | Value
-|-
kUTF8 | `0`
kUTF16LE | `1`
kUTF16BE | `2`
kUTF32LE | `3`
kUTF32BE | `4`


### `rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::IterativeParsingState`
Name | Value
-|-
IterativeParsingFinishState | `0`
IterativeParsingErrorState | `1`
IterativeParsingStartState | `2`
IterativeParsingObjectInitialState | `3`
IterativeParsingMemberKeyState | `4`
IterativeParsingMemberValueState | `5`
IterativeParsingObjectFinishState | `6`
IterativeParsingArrayInitialState | `7`
IterativeParsingElementState | `8`
IterativeParsingArrayFinishState | `9`
IterativeParsingValueState | `10`
IterativeParsingElementDelimiterState | `11`
IterativeParsingMemberDelimiterState | `12`
IterativeParsingKeyValueDelimiterState | `13`
cIterativeParsingStateCount | `14`


### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::IterativeParsingState`
Name | Value
-|-


### `ReplacesCorHdrNumericDefines`
```
enum ReplacesCorHdrNumericDefines : __int32
{
  COMIMAGE_FLAGS_ILONLY = 0x1,
  COMIMAGE_FLAGS_32BITREQUIRED = 0x2,
  COMIMAGE_FLAGS_IL_LIBRARY = 0x4,
  COMIMAGE_FLAGS_STRONGNAMESIGNED = 0x8,
  COMIMAGE_FLAGS_NATIVE_ENTRYPOINT = 0x10,
  COMIMAGE_FLAGS_TRACKDEBUGDATA = 0x10000,
  COMIMAGE_FLAGS_32BITPREFERRED = 0x20000,
  COR_VERSION_MAJOR_V2 = 0x2,
  COR_VERSION_MAJOR = 0x2,
  COR_VERSION_MINOR = 0x5,
  COR_DELETED_NAME_LENGTH = 0x8,
  COR_VTABLEGAP_NAME_LENGTH = 0x8,
  NATIVE_TYPE_MAX_CB = 0x1,
  COR_ILMETHOD_SECT_SMALL_MAX_DATASIZE = 0xFF,
  IMAGE_COR_MIH_METHODRVA = 0x1,
  IMAGE_COR_MIH_EHRVA = 0x2,
  IMAGE_COR_MIH_BASICBLOCK = 0x8,
  COR_VTABLE_32BIT = 0x1,
  COR_VTABLE_64BIT = 0x2,
  COR_VTABLE_FROM_UNMANAGED = 0x4,
  COR_VTABLE_FROM_UNMANAGED_RETAIN_APPDOMAIN = 0x8,
  COR_VTABLE_CALL_MOST_DERIVED = 0x10,
  IMAGE_COR_EATJ_THUNK_SIZE = 0x20,
  MAX_CLASS_NAME = 0x400,
  MAX_PACKAGE_NAME = 0x400,
};

```

### `Rotation`
```
enum Rotation : __int8
{
  None = 0x0,
  Rotate90 = 0x1,
  Rotate180 = 0x2,
  Rotate270 = 0x3,
  Total = 0x4,
};

```

### `RealmsEnvironment`
```
enum RealmsEnvironment : __int32
{
  Production = 0x0,
  Staging = 0x1,
  Dev = 0x2,
  Local = 0x3,
  EnvironmentCount = 0x4,
};

```

### `RenderCapability`
```
typedef OptionID RenderCapability;

```

### `ResourcePackStackType`
```
enum ResourcePackStackType : __int32
{
  LEVEL = 0x0,
  ADDON = 0x1,
  GLOBAL = 0x2,
  TREATMENT = 0x3,
  BASE_GAME = 0x4,
  SIZE = 0x5,
};

```

### `Realms::GenericStatus`
```
typedef IMinecraftEventing::AuthenticationOutcome Realms::GenericStatus;

```

### `ResourcePackResponse`
```
enum ResourcePackResponse : __int8
{
  Cancel = 0x1,
  Downloading = 0x2,
  DownloadingFinished = 0x3,
  ResourcePackStackFinished = 0x4,
};

```

### `RelationshipStatus`
```
typedef cg::ColorSpace RelationshipStatus;

```

### `RealmsAPI::JoinStatus`
```
typedef IMinecraftEventing::AuthenticationOutcome RealmsAPI::JoinStatus;

```

### `RealmsAPI::FailureReason`
```
typedef Rotation RealmsAPI::FailureReason;

```

### `RealmsStartPurchaseResult`
```
typedef IMinecraftEventing::AuthenticationOutcome RealmsStartPurchaseResult;

```

### `RequirementCategory`
```
typedef ResourcePackStackType RequirementCategory;

```

### `RequestEventPriority`
```
typedef Rotation RequestEventPriority;

```

### `RealmsPlusSectionType`
```
typedef NavButtonLinksTo RealmsPlusSectionType;

```

### `Realms::ContentType`
```
typedef cg::ColorSpace Realms::ContentType;

```

### `RealmsAllowListScreenController::SearchState`
```
enum RealmsAllowListScreenController::SearchState : __int32
{
  NotInitialized = 0xFFFFFFFF,
  NotFound = 0x0,
  Found = 0x1,
};

```

### `RealmsAllowListScreenController::RealmPlayerList`
```
enum RealmsAllowListScreenController::RealmPlayerList : __int32
{
  InvalidMemberList = 0xFFFFFFFF,
  MembersList = 0x0,
  InvitedFriendsList = 0x1,
  UninvitedFriendsList = 0x2,
  BlockedPlayersList = 0x3,
};

```

### `RequestHandler::WaitForSignIn`
```
typedef Rotation RequestHandler::WaitForSignIn;

```

### `ReplayStateMode`
```
typedef AutoUpdateMode ReplayStateMode;

```

### `ResponseParameterContext`
```
typedef Rotation ResponseParameterContext;

```

### `RenderControllerArrayType`
```
typedef DimensionId RenderControllerArrayType;

```

### `RenderControllerColorChannels`
```
typedef DimensionId RenderControllerColorChannels;

```

### `RenderControllerUVAnimChannels`
```
typedef DimensionId RenderControllerUVAnimChannels;

```

### `RenderContextType`
```
typedef cg::ColorSpace RenderContextType;

```

### `RenderParam`
```
typedef cg::ColorSpace RenderParam;

```

### `RpcProxyPerfCounters`
```
enum RpcProxyPerfCounters : __int32
{
  RpcCurrentUniqueUser = 0x1,
  RpcBackEndConnectionAttempts = 0x2,
  RpcBackEndConnectionFailed = 0x3,
  RpcRequestsPerSecond = 0x4,
  RpcIncomingConnections = 0x5,
  RpcIncomingBandwidth = 0x6,
  RpcOutgoingBandwidth = 0x7,
  RpcAttemptedLbsDecisions = 0x8,
  RpcFailedLbsDecisions = 0x9,
  RpcAttemptedLbsMessages = 0xA,
  RpcFailedLbsMessages = 0xB,
  RpcLastCounter = 0xC,
};

```

### `RPC_ADDRESS_CHANGE_TYPE`
```
enum RPC_ADDRESS_CHANGE_TYPE : __int32
{
  PROTOCOL_NOT_LOADED = 0x1,
  PROTOCOL_LOADED = 0x2,
  PROTOCOL_ADDRESS_CHANGE = 0x3,
};

```

### `RO_INIT_TYPE`
```
enum RO_INIT_TYPE : __int32
{
  RO_INIT_SINGLETHREADED = 0x0,
  RO_INIT_MULTITHREADED = 0x1,
};

```

### `RakNet::ConnectionState`
```
enum RakNet::ConnectionState : __int32
{
  IS_PENDING = 0x0,
  IS_CONNECTING = 0x1,
  IS_CONNECTED = 0x2,
  IS_DISCONNECTING = 0x3,
  IS_SILENTLY_DISCONNECTING = 0x4,
  IS_DISCONNECTED = 0x5,
  IS_NOT_CONNECTED = 0x6,
};

```

### `RakNet::ConnectionAttemptResult`
```
enum RakNet::ConnectionAttemptResult : __int32
{
  CONNECTION_ATTEMPT_STARTED = 0x0,
  INVALID_PARAMETER = 0x1,
  CANNOT_RESOLVE_DOMAIN_NAME = 0x2,
  ALREADY_CONNECTED_TO_ENDPOINT = 0x3,
  CONNECTION_ATTEMPT_ALREADY_IN_PROGRESS = 0x4,
  SECURITY_INITIALIZATION_FAILED = 0x5,
};

```

### `RakNet::StartupResult`
```
enum RakNet::StartupResult : __int32
{
  RAKNET_STARTED = 0x0,
  RAKNET_ALREADY_STARTED = 0x1,
  INVALID_SOCKET_DESCRIPTORS = 0x2,
  INVALID_MAX_CONNECTIONS = 0x3,
  SOCKET_FAMILY_NOT_SUPPORTED = 0x4,
  SOCKET_PORT_ALREADY_IN_USE = 0x5,
  SOCKET_FAILED_TO_BIND = 0x6,
  SOCKET_FAILED_TEST_SEND = 0x7,
  PORT_CANNOT_BE_ZERO = 0x8,
  FAILED_TO_CREATE_NETWORK_THREAD = 0x9,
  COULD_NOT_GENERATE_GUID = 0xA,
  STARTUP_OTHER_FAILURE = 0xB,
};

```

### `RakNet::RNS2Type`
```
enum RakNet::RNS2Type : __int32
{
  RNS2T_WINDOWS_STORE_8 = 0x0,
  RNS2T_PS3 = 0x1,
  RNS2T_PS4 = 0x2,
  RNS2T_CHROME = 0x3,
  RNS2T_VITA = 0x4,
  RNS2T_XBOX_360 = 0x5,
  RNS2T_XBOX_720 = 0x6,
  RNS2T_WINDOWS = 0x7,
  RNS2T_LINUX = 0x8,
};

```

### `RakNet::AdapterAttributes`
```
enum RakNet::AdapterAttributes : __int32
{
  NO_ATTRIBUTES = 0x0,
  IS_MULTICAST = 0x1,
  IS_LOOPBACK = 0x2,
  HAS_NO_GATEWAY = 0x4,
};

```

### `RakNet::PublicKeyMode`
```
enum RakNet::PublicKeyMode : __int32
{
  PKM_INSECURE_CONNECTION = 0x0,
  PKM_ACCEPT_ANY_PUBLIC_KEY = 0x1,
  PKM_USE_KNOWN_PUBLIC_KEY = 0x2,
  PKM_USE_TWO_WAY_AUTHENTICATION = 0x3,
};

```

### `RakNet::RNS2RecvFromResultCheck`
```
enum RakNet::RNS2RecvFromResultCheck : __int32
{
  RFRC_PASS_RECEIVED_DATA_TO_APP = 0x1,
  RFRC_HANDLE_RECEIVED_EMPTY_UDP_PACKET = 0x0,
  RFRC_HANDLE_GRACEFULLY_CLOSED_TCP_CONN = 0xFFFFFFFF,
  RFRC_HANDLE_ENETDOWN_NETERROR = 0xFFFFFFFE,
  RFRC_HANDLE_OTHER_NETERRORS = 0xFFFFFF9B,
};

```

### `RakNet::RNS2BindResult`
```
enum RakNet::RNS2BindResult : __int32
{
  BR_SUCCESS = 0x0,
  BR_REQUIRES_RAKNET_SUPPORT_IPV6_DEFINE = 0x1,
  BR_FAILED_TO_BIND_SOCKET = 0x2,
  BR_FAILED_SEND_TEST = 0x3,
};

```

### `rendergraph::ValidationResult`
```
enum rendergraph::ValidationResult : __int32
{
  VALID = 0x0,
  UNREACHABLE_PASS = 0x1,
  BEGIN_FAILURE = 0x2,
  CRITICAL_FAILURE = 0x3,
  EXTERNAL_RESOURCE_NOT_FOUND = 0x4,
  EXTERNAL_RESOURCE_MISMATCH = 0x5,
  TRANSIENT_RESOURCE_NOT_FOUND = 0x6,
  INVALID_RESOURCE_ACCESS = 0x7,
  INVALID_RESOURCE_TARGET_LINK = 0x8,
  INVALID_RESOURCE_VIEW_LINK = 0x9,
  DUPLICATE_RESOURCE_BINDING = 0xA,
  DUPLICATE_FRAMEBUFFER_BINDING = 0xB,
  INVALID_FRAMEBUFFER_LINK = 0xC,
  INVALID_FRAMEBUFFER_REQUIREMENT = 0xD,
  END_FAILURE = 0xE,
};

```

### `rendergraph::PassBuilderInterface::ClearTarget`
```
typedef Rotation rendergraph::PassBuilderInterface::ClearTarget;

```

### `rendergraph::RenderOrder::PassRegistry::FrameBufferRequirement`
```
typedef rendergraph::ResourceBinding::ResourceType rendergraph::RenderOrder::PassRegistry::FrameBufferRequirement;

```

### `RenderChunkInstanced::SortState`
```
typedef ClientInstanceState RenderChunkInstanced::SortState;

```

### `RenderChunkShared::VisibilityBuildState`
```
typedef Player::DimensionState RenderChunkShared::VisibilityBuildState;

```

### `RenderChunkShared::DataState`
```
typedef SerializerDirection RenderChunkShared::DataState;

```

### `RenderChunkShared::BuildState`
```
enum RenderChunkShared::BuildState : __int32
{
  Building = 0x0,
  NotBuldingOrSorting = 0x1,
};

```

### `RakWebSocket::PacketDirection`
```
enum RakWebSocket::PacketDirection : __int32
{
  INWARD = 0x1,
  OUTWARD = 0x2,
  BOTHWAYS = 0x3,
};

```

### `RakNet::PluginReceiveResult`
```
enum RakNet::PluginReceiveResult : __int32
{
  RR_STOP_PROCESSING_AND_DEALLOCATE = 0x0,
  RR_CONTINUE_PROCESSING = 0x1,
  RR_STOP_PROCESSING = 0x2,
};

```

### `RakNet::RNSPerSecondMetrics`
```
enum RakNet::RNSPerSecondMetrics : __int32
{
  USER_MESSAGE_BYTES_PUSHED = 0x0,
  USER_MESSAGE_BYTES_SENT = 0x1,
  USER_MESSAGE_BYTES_RESENT = 0x2,
  USER_MESSAGE_BYTES_RECEIVED_PROCESSED = 0x3,
  USER_MESSAGE_BYTES_RECEIVED_IGNORED = 0x4,
  ACTUAL_BYTES_SENT = 0x5,
  ACTUAL_BYTES_RECEIVED = 0x6,
  RNS_PER_SECOND_METRICS_COUNT = 0x7,
};

```

### `RakPeerHelper::IPVersion`
```
typedef OptionID RakPeerHelper::IPVersion;

```

### `RakNetInstance::NATState`
```
typedef FlightingService::FetchState RakNetInstance::NATState;

```

### `RakNetServerLocator::protocolVersion`
```
enum RakNetServerLocator::protocolVersion : __int32
{
  ipv4 = 0x4,
  ipv6 = 0x6,
};

```

### `RakWebSocket::ConnectionState`
```
enum RakWebSocket::ConnectionState : __int32
{
  CS_NONE = 0x0,
  CS_CLOSE_HANDSHAKE = 0x1,
  CS_STARTING = 0x2,
  CS_CONNECTING = 0x3,
  CS_OPEN_HANDSHAKE_INIT = 0x4,
  CS_OPEN_HANDSHAKE_AWAIT = 0x5,
  CS_OPEN_AND_PROCESSING = 0x6,
};

```

### `RakNet::PI2_LostConnectionReason`
```
enum RakNet::PI2_LostConnectionReason : __int32
{
  LCR_CLOSED_BY_USER = 0x0,
  LCR_DISCONNECTION_NOTIFICATION = 0x1,
  LCR_CONNECTION_LOST = 0x2,
};

```

### `RakNet::PI2_FailedConnectionAttemptReason`
```
enum RakNet::PI2_FailedConnectionAttemptReason : __int32
{
  FCAR_CONNECTION_ATTEMPT_FAILED = 0x0,
  FCAR_ALREADY_CONNECTED = 0x1,
  FCAR_NO_FREE_INCOMING_CONNECTIONS = 0x2,
  FCAR_SECURITY_PUBLIC_KEY_MISMATCH = 0x3,
  FCAR_CONNECTION_BANNED = 0x4,
  FCAR_INVALID_PASSWORD = 0x5,
  FCAR_INCOMPATIBLE_PROTOCOL = 0x6,
  FCAR_IP_RECENTLY_CONNECTED = 0x7,
  FCAR_REMOTE_SYSTEM_REQUIRES_PUBLIC_KEY = 0x8,
  FCAR_OUR_SYSTEM_REQUIRES_SECURITY = 0x9,
  FCAR_PUBLIC_KEY_MISMATCH = 0xA,
};

```

### `RegistrationType`
```
typedef ActorEvent RegistrationType;

```

### `Realms::SubscriptionService::SubscriptionQueryStatus`
```
typedef SerializerDirection Realms::SubscriptionService::SubscriptionQueryStatus;

```

### `RemoteStorageProviderSyncProgressHandler::State`
```
typedef ClientInstanceState RemoteStorageProviderSyncProgressHandler::State;

```

### `RopeParams::Flags`
```
typedef Rotation RopeParams::Flags;

```

### `RealmsCreateScreenController::State`
```
enum RealmsCreateScreenController::State : __int32
{
  INITIAL = 0x0,
  PROCESSING = 0x1,
  FAIL = 0x2,
  SUCCESS = 0x3,
};

```

### `RecipeContainerBackgroundStyle`
```
typedef TaskOptions RecipeContainerBackgroundStyle;

```

### `RealmsSubscriptionsLoadingState`
```
typedef SerializerDirection RealmsSubscriptionsLoadingState;

```

### `RealmType`
```
enum RealmType : __int32
{
  Personal = 0x0,
  Friends = 0x1,
};

```

### `RealmsSettingsScreenController::PurchaseIntent`
```
typedef mce::Font::Type RealmsSettingsScreenController::PurchaseIntent;

```

### `Realms::Invite::State`
```
typedef Realms::World::State Realms::Invite::State;

```

### `RealmsPlusUpgradeNoticeState`
```
typedef IsMissingTexture RealmsPlusUpgradeNoticeState;

```

### `RenderingProfileOption`
```
typedef mce::RenderingProfile RenderingProfileOption;

```

### `RailType`
```
typedef DimensionId RailType;

```

### `ResourceLoaders::ResourceFileType`
```
typedef OptionID ResourceLoaders::ResourceFileType;

```

### `RideCommand::RideAction`
```
enum RideCommand::RideAction : __int8
{
  StartRiding = 0x0,
  StopRiding = 0x1,
  EvictRiders = 0x2,
  SummonRider = 0x3,
  SummonRide = 0x4,
};

```

### `RideCommand::TeleportRules`
```
enum RideCommand::TeleportRules : __int8
{
  TeleportRider = 0x0,
  TeleportRide = 0x1,
};

```

### `RideCommand::RideFillType`
```
enum RideCommand::RideFillType : __int8
{
  UntilFull = 0x0,
  IfGroupFits = 0x1,
};

```

### `RideCommand::RideRules`
```
enum RideCommand::RideRules : __int8
{
  NoRideChange = 0x0,
  ReassignRides = 0x1,
  SkipRiders = 0x2,
};

```

### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ShortString::<unnamed_enum_MaxChars>`
```
enum rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::ShortString::<unnamed_enum_MaxChars> : __int32
{
  MaxChars = 0xE,
  MaxSize = 0xD,
  LenPos = 0xD,
};

```

### `rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::<unnamed_enum_kBoolFlag>`
```
enum rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> >::<unnamed_enum_kBoolFlag> : __int32
{
  kBoolFlag = 0x8,
  kNumberFlag = 0x10,
  kIntFlag = 0x20,
  kUintFlag = 0x40,
  kInt64Flag = 0x80,
  kUint64Flag = 0x100,
  kDoubleFlag = 0x200,
  kStringFlag = 0x400,
  kCopyFlag = 0x800,
  kInlineStrFlag = 0x1000,
  kNullFlag = 0x0,
  kTrueFlag = 0xA,
  kFalseFlag = 0x9,
  kNumberIntFlag = 0xB6,
  kNumberUintFlag = 0x1D6,
  kNumberInt64Flag = 0x96,
  kNumberUint64Flag = 0x116,
  kNumberDoubleFlag = 0x216,
  kNumberAnyFlag = 0x3F6,
  kConstStringFlag = 0x405,
  kCopyStringFlag = 0xC05,
  kShortStringFlag = 0x1C05,
  kObjectFlag = 0x3,
  kArrayFlag = 0x4,
  kTypeMask = 0x7,
};

```

### `rapidjson::Type`
```
enum rapidjson::Type : __int32
{
  kNullType = 0x0,
  kFalseType = 0x1,
  kTrueType = 0x2,
  kObjectType = 0x3,
  kArrayType = 0x4,
  kStringType = 0x5,
  kNumberType = 0x6,
};

```

### `rapidjson::ParseFlag`
```
enum rapidjson::ParseFlag : __int32
{
  kParseNoFlags = 0x0,
  kParseInsituFlag = 0x1,
  kParseValidateEncodingFlag = 0x2,
  kParseIterativeFlag = 0x4,
  kParseStopWhenDoneFlag = 0x8,
  kParseFullPrecisionFlag = 0x10,
  kParseCommentsFlag = 0x20,
  kParseNumbersAsStringsFlag = 0x40,
  kParseTrailingCommasFlag = 0x80,
  kParseNanAndInfFlag = 0x100,
  kParseDefaultFlags = 0x0,
};

```

### `rapidjson::UTF8<char>::<unnamed_enum_supportUnicode>`
```
enum rapidjson::UTF8<char>::<unnamed_enum_supportUnicode> : __int32
{
  supportUnicode = 0x1,
};

```

### `Raid::RaidState`
```
typedef CompactionStatus Raid::RaidState;

```

### `ReplaceItemCommand::ReplaceMode`
```
enum ReplaceItemCommand::ReplaceMode : __int32
{
  Destroy = 0x0,
  Keep = 0x1,
};

```

### `ReplaceItemCommand::TargetType`
```
typedef LevelChunkTag ReplaceItemCommand::TargetType;

```

### `ReadMode_t`
```
enum ReadMode_t : __int32
{
  READ_METADATA = 0x1,
  READ_IMAGE = 0x2,
  READ_ALL = 0x3,
  READ_ANY = 0x5,
};

```

### `RakWebSocketDataFrame::ParseState`
```
typedef HttpHeaders::ParseState RakWebSocketDataFrame::ParseState;

```

### `RepeaterCapacitor::States`
```
typedef DevConnectionQuality RepeaterCapacitor::States;

```

### `RailDirection`
```
enum RailDirection : __int32
{
  NorthSouth = 0x0,
  EastWest = 0x1,
  AscendingEast = 0x2,
  AscendingWest = 0x3,
  AscendingNorth = 0x4,
  AscendingSouth = 0x5,
  SouthEast = 0x6,
  SouthWest = 0x7,
  NorthWest = 0x8,
  NorthEast = 0x9,
};

```

### `ReceiverId`
```
enum ReceiverId : __int16
{
  RECEIVER_NONE = 0x0,
  ISLAND_ID_PLATFORM = 0x1,
  ISLAND_ID_APP = 0x2,
  ISLAND_ID_USERMANAGER = 0x3,
  ISLAND_ID_INPUT = 0x4,
  ISLAND_ID_THREADING = 0x5,
  ISLAND_ID_FILELOCAL = 0x6,
  ISLAND_ID_FILECLOUD = 0x7,
  ISLAND_ID_NETWORK = 0x8,
  ISLAND_ID_AUDIO = 0x9,
  ISLAND_ID_LOGGING = 0xA,
  ISLAND_ID_TELEMETRY = 0xB,
  FIRST_USER_RECEIVER = 0xC,
};

```

### `RespawnAnimation`
```
typedef ActorEvent RespawnAnimation;

```

### `RO_ERROR_REPORTING_FLAGS`
```
enum RO_ERROR_REPORTING_FLAGS : __int32
{
  RO_ERROR_REPORTING_NONE = 0x0,
  RO_ERROR_REPORTING_SUPPRESSEXCEPTIONS = 0x1,
  RO_ERROR_REPORTING_FORCEEXCEPTIONS = 0x2,
  RO_ERROR_REPORTING_USESETERRORINFO = 0x4,
  RO_ERROR_REPORTING_SUPPRESSSETERRORINFO = 0x8,
};

```

### `rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization>`
```
enum rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization> : __int32
{
  copyOptimization = 0x0,
};

```

### `rapidjson::AutoUTF<unsigned int>::<unnamed_enum_supportUnicode>`
```
typedef rapidjson::UTF8<char>::<unnamed_enum_supportUnicode> rapidjson::AutoUTF<unsigned int>::<unnamed_enum_supportUnicode>;

```

### `rapidjson::UTF16<unsigned int>::<unnamed_enum_supportUnicode>`
```
typedef rapidjson::UTF8<char>::<unnamed_enum_supportUnicode> rapidjson::UTF16<unsigned int>::<unnamed_enum_supportUnicode>;

```

### `rapidjson::UTF8<unsigned int>::<unnamed_enum_supportUnicode>`
```
typedef rapidjson::UTF8<char>::<unnamed_enum_supportUnicode> rapidjson::UTF8<unsigned int>::<unnamed_enum_supportUnicode>;

```

### `rapidjson::UTF32<unsigned int>::<unnamed_enum_supportUnicode>`
```
typedef rapidjson::UTF8<char>::<unnamed_enum_supportUnicode> rapidjson::UTF32<unsigned int>::<unnamed_enum_supportUnicode>;

```

### `rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token`
```
enum rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token : __int32
{
  LeftBracketToken = 0x0,
  RightBracketToken = 0x1,
  LeftCurlyBracketToken = 0x2,
  RightCurlyBracketToken = 0x3,
  CommaToken = 0x4,
  ColonToken = 0x5,
  StringToken = 0x6,
  FalseToken = 0x7,
  TrueToken = 0x8,
  NullToken = 0x9,
  NumberToken = 0xA,
  kTokenCount = 0xB,
};

```

### `RedstoneScreenType`
```
typedef MinecartType RedstoneScreenType;

```

### `RakNet::DynDNS::ConnectPhase`
```
enum RakNet::DynDNS::ConnectPhase : __int32
{
  CP_CONNECTING_TO_CHECKIP = 0x0,
  CP_WAITING_FOR_CHECKIP_RESPONSE = 0x1,
  CP_CONNECTING_TO_DYNDNS = 0x2,
  CP_WAITING_FOR_DYNDNS_RESPONSE = 0x3,
  CP_IDLE = 0x4,
};

```

### `RakNet::FullyConnectedMesh2::JoinInProgressState`
```
enum RakNet::FullyConnectedMesh2::JoinInProgressState : __int32
{
  JIPS_PROCESSING = 0x0,
  JIPS_FAILED = 0x1,
  JIPS_CONNECTED = 0x2,
  JIPS_UNNECESSARY = 0x3,
};

```

### `RakNet::HTTPConnection::ResponseCodes`
```
typedef BedSleepingResult RakNet::HTTPConnection::ResponseCodes;

```

### `RakNet::HTTPConnection::ConnectionState`
```
typedef RakWebSocket::ConnectionState RakNet::HTTPConnection::ConnectionState;

```

### `RakNet::NATTypeDetectionResult`
```
enum RakNet::NATTypeDetectionResult : __int32
{
  NAT_TYPE_NONE = 0x0,
  NAT_TYPE_FULL_CONE = 0x1,
  NAT_TYPE_ADDRESS_RESTRICTED = 0x2,
  NAT_TYPE_PORT_RESTRICTED = 0x3,
  NAT_TYPE_SYMMETRIC = 0x4,
  NAT_TYPE_UNKNOWN = 0x5,
  NAT_TYPE_DETECTION_IN_PROGRESS = 0x6,
  NAT_TYPE_SUPPORTS_UPNP = 0x7,
  NAT_TYPE_COUNT = 0x8,
};

```

### `RakNet::NatPunchthroughClient::<unnamed_type_hasPortStride>`
```
enum RakNet::NatPunchthroughClient::<unnamed_type_hasPortStride> : __int32
{
  HAS_PORT_STRIDE = 0x0,
  UNKNOWN_PORT_STRIDE = 0x1,
  CALCULATING_PORT_STRIDE = 0x2,
  INCAPABLE_PORT_STRIDE = 0x3,
};

```

### `RakNet::NatPunchthroughClient::SendPing::TestMode`
```
enum RakNet::NatPunchthroughClient::SendPing::TestMode : __int32
{
  TESTING_INTERNAL_IPS = 0x0,
  WAITING_FOR_INTERNAL_IPS_RESPONSE = 0x1,
  TESTING_EXTERNAL_IPS_FACILITATOR_PORT_TO_FACILITATOR_PORT = 0x2,
  TESTING_EXTERNAL_IPS_1024_TO_FACILITATOR_PORT = 0x3,
  TESTING_EXTERNAL_IPS_FACILITATOR_PORT_TO_1024 = 0x4,
  TESTING_EXTERNAL_IPS_1024_TO_1024 = 0x5,
  WAITING_AFTER_ALL_ATTEMPTS = 0x6,
  PUNCHING_FIXED_PORT = 0x7,
};

```

### `RakNet::NatTypeDetectionServer::NATDetectionState`
```
enum RakNet::NatTypeDetectionServer::NATDetectionState : __int32
{
  STATE_NONE = 0x0,
  STATE_TESTING_NONE_1 = 0x1,
  STATE_TESTING_NONE_2 = 0x2,
  STATE_TESTING_FULL_CONE_1 = 0x3,
  STATE_TESTING_FULL_CONE_2 = 0x4,
  STATE_TESTING_ADDRESS_RESTRICTED_1 = 0x5,
  STATE_TESTING_ADDRESS_RESTRICTED_2 = 0x6,
  STATE_TESTING_PORT_RESTRICTED_1 = 0x7,
  STATE_TESTING_PORT_RESTRICTED_2 = 0x8,
  STATE_DONE = 0x9,
};

```

### `RakNet::NatPunchthroughServer::ConnectionAttempt::<unnamed_type_attemptPhase>`
```
enum RakNet::NatPunchthroughServer::ConnectionAttempt::<unnamed_type_attemptPhase> : __int32
{
  NAT_ATTEMPT_PHASE_NOT_STARTED = 0x0,
  NAT_ATTEMPT_PHASE_GETTING_RECENT_PORTS = 0x1,
};

```

### `RakNet::RackspaceOperationType`
```
enum RakNet::RackspaceOperationType : __int32
{
  RO_CONNECT_AND_AUTHENTICATE = 0x0,
  RO_LIST_SERVERS = 0x1,
  RO_LIST_SERVERS_WITH_DETAILS = 0x2,
  RO_CREATE_SERVER = 0x3,
  RO_GET_SERVER_DETAILS = 0x4,
  RO_UPDATE_SERVER_NAME_OR_PASSWORD = 0x5,
  RO_DELETE_SERVER = 0x6,
  RO_LIST_SERVER_ADDRESSES = 0x7,
  RO_SHARE_SERVER_ADDRESS = 0x8,
  RO_DELETE_SERVER_ADDRESS = 0x9,
  RO_REBOOT_SERVER = 0xA,
  RO_REBUILD_SERVER = 0xB,
  RO_RESIZE_SERVER = 0xC,
  RO_CONFIRM_RESIZED_SERVER = 0xD,
  RO_REVERT_RESIZED_SERVER = 0xE,
  RO_LIST_FLAVORS = 0xF,
  RO_GET_FLAVOR_DETAILS = 0x10,
  RO_LIST_IMAGES = 0x11,
  RO_CREATE_IMAGE = 0x12,
  RO_GET_IMAGE_DETAILS = 0x13,
  RO_DELETE_IMAGE = 0x14,
  RO_LIST_SHARED_IP_GROUPS = 0x15,
  RO_LIST_SHARED_IP_GROUPS_WITH_DETAILS = 0x16,
  RO_CREATE_SHARED_IP_GROUP = 0x17,
  RO_GET_SHARED_IP_GROUP_DETAILS = 0x18,
  RO_DELETE_SHARED_IP_GROUP = 0x19,
  RO_NONE = 0x1A,
};

```

### `RakNet::RackspaceEventType`
```
enum RakNet::RackspaceEventType : __int32
{
  RET_Success_200 = 0x0,
  RET_Success_201 = 0x1,
  RET_Success_202 = 0x2,
  RET_Success_203 = 0x3,
  RET_Success_204 = 0x4,
  RET_Cloud_Servers_Fault_500 = 0x5,
  RET_Service_Unavailable_503 = 0x6,
  RET_Unauthorized_401 = 0x7,
  RET_Bad_Request_400 = 0x8,
  RET_Over_Limit_413 = 0x9,
  RET_Bad_Media_Type_415 = 0xA,
  RET_Item_Not_Found_404 = 0xB,
  RET_Build_In_Progress_409 = 0xC,
  RET_Resize_Not_Allowed_403 = 0xD,
  RET_Connection_Closed_Without_Reponse = 0xE,
  RET_Unknown_Failure = 0xF,
};

```

### `RakNet::InternalPacket::AllocationScheme`
```
typedef CloseStatusCode RakNet::InternalPacket::AllocationScheme;

```

### `RakNet::RakPeer::RemoteSystemStruct::ConnectMode`
```
typedef DataStructures::BPlusTree<unsigned int,DataStructures::Table::Row *,16>::ReturnAction::<unnamed_type_action> RakNet::RakPeer::RemoteSystemStruct::ConnectMode;

```

### `RakNet::RakPeer::<unnamed_enum_requestedConnectionList_Mutex>`
```
enum RakNet::RakPeer::<unnamed_enum_requestedConnectionList_Mutex> : __int32
{
  requestedConnectionList_Mutex = 0x0,
  offlinePingResponse_Mutex = 0x1,
  NUMBER_OF_RAKPEER_MUTEXES = 0x2,
};

```

### `RakNet::RakPeer::BufferedCommandStruct::<unnamed_type_command>`
```
enum RakNet::RakPeer::BufferedCommandStruct::<unnamed_type_command> : __int32
{
  BCS_SEND = 0x0,
  BCS_CLOSE_CONNECTION = 0x1,
  BCS_GET_SOCKET = 0x2,
  BCS_CHANGE_SYSTEM_ADDRESS = 0x3,
  BCS_DO_NOTHING = 0x4,
};

```

### `RakNet::RakPeer::RequestedConnectionStruct::<unnamed_type_actionToTake>`
```
enum RakNet::RakPeer::RequestedConnectionStruct::<unnamed_type_actionToTake> : __int32
{
  CONNECT = 0x1,
};

```

### `Router2MessageIdentifiers`
```
enum Router2MessageIdentifiers : __int32
{
  ID_ROUTER_2_QUERY_FORWARDING = 0x0,
  ID_ROUTER_2_REPLY_FORWARDING = 0x1,
  ID_ROUTER_2_REQUEST_FORWARDING = 0x2,
  ID_ROUTER_2_INCREASE_TIMEOUT = 0x3,
};

```

### `RakNet::RelayPluginEnums`
```
enum RakNet::RelayPluginEnums : __int32
{
  RPE_MESSAGE_TO_SERVER_FROM_CLIENT = 0x0,
  RPE_ADD_CLIENT_REQUEST_FROM_CLIENT = 0x1,
  RPE_REMOVE_CLIENT_REQUEST_FROM_CLIENT = 0x2,
  RPE_GROUP_MESSAGE_FROM_CLIENT = 0x3,
  RPE_JOIN_GROUP_REQUEST_FROM_CLIENT = 0x4,
  RPE_LEAVE_GROUP_REQUEST_FROM_CLIENT = 0x5,
  RPE_GET_GROUP_LIST_REQUEST_FROM_CLIENT = 0x6,
  RPE_MESSAGE_TO_CLIENT_FROM_SERVER = 0x7,
  RPE_ADD_CLIENT_NOT_ALLOWED = 0x8,
  RPE_ADD_CLIENT_TARGET_NOT_CONNECTED = 0x9,
  RPE_ADD_CLIENT_NAME_ALREADY_IN_USE = 0xA,
  RPE_ADD_CLIENT_SUCCESS = 0xB,
  RPE_USER_ENTERED_ROOM = 0xC,
  RPE_USER_LEFT_ROOM = 0xD,
  RPE_GROUP_MSG_FROM_SERVER = 0xE,
  RPE_GET_GROUP_LIST_REPLY_FROM_SERVER = 0xF,
  RPE_JOIN_GROUP_SUCCESS = 0x10,
  RPE_JOIN_GROUP_FAILURE = 0x11,
};

```

### `RakNet::UDPForwarderResult`
```
enum RakNet::UDPForwarderResult : __int32
{
  UDPFORWARDER_FORWARDING_ALREADY_EXISTS = 0x0,
  UDPFORWARDER_NO_SOCKETS = 0x1,
  UDPFORWARDER_BIND_FAILED = 0x2,
  UDPFORWARDER_INVALID_PARAMETERS = 0x3,
  UDPFORWARDER_NOT_RUNNING = 0x4,
  UDPFORWARDER_SUCCESS = 0x5,
  UDPFORWARDER_RESULT_COUNT = 0x6,
};

```

### `RakNet::RM3SerializationResult`
```
enum RakNet::RM3SerializationResult : __int32
{
  RM3SR_BROADCAST_IDENTICALLY = 0x0,
  RM3SR_BROADCAST_IDENTICALLY_FORCE_SERIALIZATION = 0x1,
  RM3SR_SERIALIZED_UNIQUELY = 0x2,
  RM3SR_SERIALIZED_ALWAYS = 0x3,
  RM3SR_SERIALIZED_ALWAYS_IDENTICALLY = 0x4,
  RM3SR_DO_NOT_SERIALIZE = 0x5,
  RM3SR_NEVER_SERIALIZE_FOR_THIS_CONNECTION = 0x6,
  RM3SR_MAX = 0x7,
};

```

### `RakNet::RM3ActionOnPopConnection`
```
enum RakNet::RM3ActionOnPopConnection : __int32
{
  RM3AOPC_DO_NOTHING = 0x0,
  RM3AOPC_DELETE_REPLICA = 0x1,
  RM3AOPC_DELETE_REPLICA_AND_BROADCAST_DESTRUCTION = 0x2,
  RM3AOPC_MAX = 0x3,
};

```

### `RakNet::SendSerializeIfChangedResult`
```
enum RakNet::SendSerializeIfChangedResult : __int32
{
  SSICR_SENT_DATA = 0x0,
  SSICR_DID_NOT_SEND_DATA = 0x1,
  SSICR_NEVER_SERIALIZE = 0x2,
};

```

### `RakNet::Replica3P2PMode`
```
enum RakNet::Replica3P2PMode : __int32
{
  R3P2PM_SINGLE_OWNER = 0x0,
  R3P2PM_MULTI_OWNER_CURRENTLY_AUTHORITATIVE = 0x1,
  R3P2PM_MULTI_OWNER_NOT_CURRENTLY_AUTHORITATIVE = 0x2,
  R3P2PM_STATIC_OBJECT_CURRENTLY_AUTHORITATIVE = 0x3,
  R3P2PM_STATIC_OBJECT_NOT_CURRENTLY_AUTHORITATIVE = 0x4,
};

```

### `RakNet::RM3DestructionState`
```
enum RakNet::RM3DestructionState : __int32
{
  RM3DS_SEND_DESTRUCTION = 0x0,
  RM3DS_DO_NOT_QUERY_DESTRUCTION = 0x1,
  RM3DS_NO_ACTION = 0x2,
  RM3DS_MAX = 0x3,
};

```

### `RakNet::ReadyEventSystemStatus`
```
enum RakNet::ReadyEventSystemStatus : __int32
{
  RES_NOT_WAITING = 0x0,
  RES_WAITING = 0x1,
  RES_READY = 0x2,
  RES_ALL_READY = 0x3,
  RES_UNKNOWN_EVENT = 0x4,
};

```

### `RakNet::RPCErrorCodes`
```
enum RakNet::RPCErrorCodes : __int32
{
  RPC_ERROR_FUNCTION_NOT_REGISTERED = 0x0,
};

```

### `RakNet::RM3QuerySerializationResult`
```
enum RakNet::RM3QuerySerializationResult : __int32
{
  RM3QSR_CALL_SERIALIZE = 0x0,
  RM3QSR_DO_NOT_CALL_SERIALIZE = 0x1,
  RM3QSR_NEVER_CALL_SERIALIZE = 0x2,
  RM3QSR_MAX = 0x3,
};

```

### `RakNet::RM3ConstructionState`
```
enum RakNet::RM3ConstructionState : __int32
{
  RM3CS_SEND_CONSTRUCTION = 0x0,
  RM3CS_ALREADY_EXISTS_REMOTELY = 0x1,
  RM3CS_ALREADY_EXISTS_REMOTELY_DO_NOT_CONSTRUCT = 0x2,
  RM3CS_NEVER_CONSTRUCT = 0x3,
  RM3CS_NO_ACTION = 0x4,
  RM3CS_MAX = 0x5,
};

```

### `RPC4Identifiers`
```
enum RPC4Identifiers : __int32
{
  ID_RPC4_CALL = 0x0,
  ID_RPC4_RETURN = 0x1,
  ID_RPC4_SIGNAL = 0x2,
};

```

### `RakNet::Router2::Router2RequestStates`
```
enum RakNet::Router2::Router2RequestStates : __int32
{
  R2RS_REQUEST_STATE_QUERY_FORWARDING = 0x0,
  REQUEST_STATE_REQUEST_FORWARDING = 0x1,
};

```

### `RakNet::Connection_RM3::ConstructionMode`
```
enum RakNet::Connection_RM3::ConstructionMode : __int32
{
  QUERY_REPLICA_FOR_CONSTRUCTION = 0x0,
  QUERY_REPLICA_FOR_CONSTRUCTION_AND_DESTRUCTION = 0x1,
  QUERY_CONNECTION_FOR_REPLICA_LIST = 0x2,
};

```

### `RakNet::JoinTeamType`
```
enum RakNet::JoinTeamType : __int32
{
  JOIN_ANY_AVAILABLE_TEAM = 0x0,
  JOIN_SPECIFIC_TEAM = 0x1,
  JOIN_NO_TEAM = 0x2,
};

```

### `RakNet::TMTopology`
```
enum RakNet::TMTopology : __int32
{
  TM_PEER_TO_PEER = 0x0,
  TM_CLIENT_SERVER = 0x1,
};

```

### `RakNet::StatisticsHistory::SHErrorCode`
```
enum RakNet::StatisticsHistory::SHErrorCode : __int32
{
  SH_OK = 0x0,
  SH_UKNOWN_OBJECT = 0x1,
  SH_UKNOWN_KEY = 0x2,
  SH_INVALID_PARAMETER = 0x3,
};

```

### `RakNet::StatisticsHistory::SHSortOperation`
```
enum RakNet::StatisticsHistory::SHSortOperation : __int32
{
  SH_DO_NOT_SORT = 0x0,
  SH_SORT_BY_RECENT_SUM_ASCENDING = 0x1,
  SH_SORT_BY_RECENT_SUM_DESCENDING = 0x2,
  SH_SORT_BY_LONG_TERM_SUM_ASCENDING = 0x3,
  SH_SORT_BY_LONG_TERM_SUM_DESCENDING = 0x4,
  SH_SORT_BY_RECENT_SUM_OF_SQUARES_ASCENDING = 0x5,
  SH_SORT_BY_RECENT_SUM_OF_SQUARES_DESCENDING = 0x6,
  SH_SORT_BY_RECENT_AVERAGE_ASCENDING = 0x7,
  SH_SORT_BY_RECENT_AVERAGE_DESCENDING = 0x8,
  SH_SORT_BY_LONG_TERM_AVERAGE_ASCENDING = 0x9,
  SH_SORT_BY_LONG_TERM_AVERAGE_DESCENDING = 0xA,
  SH_SORT_BY_RECENT_HIGHEST_ASCENDING = 0xB,
  SH_SORT_BY_RECENT_HIGHEST_DESCENDING = 0xC,
  SH_SORT_BY_RECENT_LOWEST_ASCENDING = 0xD,
  SH_SORT_BY_RECENT_LOWEST_DESCENDING = 0xE,
  SH_SORT_BY_LONG_TERM_HIGHEST_ASCENDING = 0xF,
  SH_SORT_BY_LONG_TERM_HIGHEST_DESCENDING = 0x10,
  SH_SORT_BY_LONG_TERM_LOWEST_ASCENDING = 0x11,
  SH_SORT_BY_LONG_TERM_LOWEST_DESCENDING = 0x12,
};

```

### `RakNet::StatisticsHistory::SHDataCategory`
```
enum RakNet::StatisticsHistory::SHDataCategory : __int32
{
  DC_DISCRETE = 0x0,
  DC_CONTINUOUS = 0x1,
};

```

### `RakNet::TeamBalancer::DefaultAssigmentAlgorithm`
```
enum RakNet::TeamBalancer::DefaultAssigmentAlgorithm : __int32
{
  SMALLEST_TEAM = 0x0,
  FILL_IN_ORDER = 0x1,
};

```

### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token`
```
typedef rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token;

```

### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,`Bedrock::JSONObject::Document::loadString'::`5'::DoNotAllocate>::Token`
```
typedef rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::Token rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,`Bedrock::JSONObject::Document::loadString'::`5'::DoNotAllocate>::Token;

```

### `rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,`Bedrock::JSONObject::Document::loadString'::`5'::DoNotAllocate>::IterativeParsingState`
```
typedef rapidjson::GenericReader<rapidjson::AutoUTF<unsigned int>,rapidjson::UTF8<char>,rapidjson::CrtAllocator>::IterativeParsingState rapidjson::GenericReader<rapidjson::UTF8<char>,rapidjson::UTF8<char>,`Bedrock::JSONObject::Document::loadString'::`5'::DoNotAllocate>::IterativeParsingState;

```

### `rapidjson::StreamTraits<rapidjson::GenericStringStream<rapidjson::UTF8<char> > >::<unnamed_enum_copyOptimization>`
```
typedef rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization> rapidjson::StreamTraits<rapidjson::GenericStringStream<rapidjson::UTF8<char> > >::<unnamed_enum_copyOptimization>;

```

### `rapidjson::StreamTraits<rapidjson::BasicIStreamWrapper<std::istream > >::<unnamed_enum_copyOptimization>`
```
typedef rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization> rapidjson::StreamTraits<rapidjson::BasicIStreamWrapper<std::istream > >::<unnamed_enum_copyOptimization>;

```

### `rapidjson::StreamTraits<rapidjson::GenericInsituStringStream<rapidjson::UTF8<char> > >::<unnamed_enum_copyOptimization>`
```
typedef rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization> rapidjson::StreamTraits<rapidjson::GenericInsituStringStream<rapidjson::UTF8<char> > >::<unnamed_enum_copyOptimization>;

```

### `rapidjson::PrettyFormatOptions`
```
enum rapidjson::PrettyFormatOptions : __int32
{
  kFormatDefault = 0x0,
  kFormatSingleLineArray = 0x1,
};

```

### `rapidjson::WriteFlag`
```
enum rapidjson::WriteFlag : __int32
{
  kWriteNoFlags = 0x0,
  kWriteValidateEncodingFlag = 0x1,
  kWriteNanAndInfFlag = 0x2,
  kWriteDefaultFlags = 0x0,
};

```

### `rapidjson::StreamTraits<rapidjson::EncodedInputStream<rapidjson::UTF8<char>,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization>`
```
typedef rapidjson::StreamTraits<rapidjson::AutoUTFInputStream<unsigned int,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization> rapidjson::StreamTraits<rapidjson::EncodedInputStream<rapidjson::UTF8<char>,rapidjson::MemoryStream> >::<unnamed_enum_copyOptimization>;

```

### `RCVALL_VALUE`
```
enum RCVALL_VALUE : __int32
{
  RCVALL_OFF = 0x0,
  RCVALL_ON = 0x1,
  RCVALL_SOCKETLEVELONLY = 0x2,
  RCVALL_IPLEVEL = 0x3,
};

```

