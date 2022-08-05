# N
### `NetworkPeer::Reliability`
Name | Value
-|-
Reliable | `0`
ReliableOrdered | `1`
Unreliable | `2`
UnreliableSequenced | `3`


### `NetworkIdentifier::Type`
Name | Value
-|-
RakNet | `0`
Address | `1`
Address6 | `2`
Generic | `3`


### `NewLogType`
Name | Value
-|-


### `NewLeafType`
Name | Value
-|-


### `NodeType`
Name | Value
-|-


### `NVSDK_NGX_ToneMapperType`
Name | Value
-|-
NVSDK_NGX_TONEMAPPER_STRING | `0`
NVSDK_NGX_TONEMAPPER_REINHARD | `1`
NVSDK_NGX_TONEMAPPER_ONEOVERLUMA | `2`
NVSDK_NGX_TONEMAPPER_ACES | `3`
NVSDK_NGX_TONEMAPPERTYPE_NUM | `4`


### `NVSDK_NGX_PerfQuality_Value`
Name | Value
-|-
NVSDK_NGX_PerfQuality_Value_MaxPerf | `0`
NVSDK_NGX_PerfQuality_Value_Balanced | `1`
NVSDK_NGX_PerfQuality_Value_MaxQuality | `2`
NVSDK_NGX_PerfQuality_Value_UltraPerformance | `3`
NVSDK_NGX_PerfQuality_Value_UltraQuality | `4`


### `NetworkPeer::DataStatus`
```
enum NetworkPeer::DataStatus : __int32
{
  HasData = 0x0,
  NoData = 0x1,
  BrokenData = 0x2,
};

```

### `NetworkPeer::NetworkLoad`
```
enum NetworkPeer::NetworkLoad : __int32
{
  Unrestricted = 0x0,
  Low = 0x1,
  Medium = 0x2,
  High = 0x3,
};

```

### `NetworkSuspendResumeListener::State`
```
enum NetworkSuspendResumeListener::State : __int32
{
  Resumed = 0x0,
  Suspended = 0x1,
};

```

### `NetherWorldType`
```
typedef ui::FontSize NetherWorldType;

```

### `NetworkFilter`
```
enum NetworkFilter : __int32
{
  OnlyOnWifi = 0x0,
  WifiOrMobileData = 0x1,
};

```

### `NavButtonLinksTo`
```
enum NavButtonLinksTo : __int32
{
  NOT_SPECIFIED = 0x0,
  DURABLE = 0x1,
  QUERY_MANIFEST = 0x2,
  SEARCH = 0x3,
};

```

### `NetworkHandler::NetworkStatisticsConfig`
```
typedef Rotation NetworkHandler::NetworkStatisticsConfig;

```

### `NetworkWorldType`
```
typedef Rotation NetworkWorldType;

```

### `NetworkHandler::Connection::Type`
```
typedef RealmsEnvironment NetworkHandler::Connection::Type;

```

### `NodeId`
```
typedef Rotation NodeId;

```

### `NpcActionType`
```
enum NpcActionType : __int8
{
  UrlAction = 0x0,
  CommandAction = 0x1,
  InvalidAction = 0x2,
};

```

### `NpcActionMode`
```
enum NpcActionMode : __int8
{
  Button = 0x0,
  OnClose = 0x1,
};

```

### `NpcInteractScreenController::NpcTextEdit`
```
enum NpcInteractScreenController::NpcTextEdit : __int32
{
  Name = 0x0,
  InteractText = 0x1,
  ActionButtonName = 0x2,
  ActionText = 0x3,
};

```

### `NpcInteractScreenController::Section`
```
enum NpcInteractScreenController::Section : __int8
{
  Basic = 0x0,
  Advanced = 0x1,
  MaximizedActionEdit = 0x2,
  Student = 0x3,
};

```

### `NpcRequestPacket::RequestType`
```
enum NpcRequestPacket::RequestType : __int8
{
  SetActions = 0x0,
  ExecuteAction = 0x1,
  ExecuteClosingCommands = 0x2,
  SetName = 0x3,
  SetSkin = 0x4,
  SetInteractText = 0x5,
};

```

### `NL_PREFIX_ORIGIN`
```
enum NL_PREFIX_ORIGIN : __int32
{
  IpPrefixOriginOther = 0x0,
  IpPrefixOriginManual = 0x1,
  IpPrefixOriginWellKnown = 0x2,
  IpPrefixOriginDhcp = 0x3,
  IpPrefixOriginRouterAdvertisement = 0x4,
  IpPrefixOriginUnchanged = 0x10,
};

```

### `NL_SUFFIX_ORIGIN`
```
enum NL_SUFFIX_ORIGIN : __int32
{
  NlsoOther = 0x0,
  NlsoManual = 0x1,
  NlsoWellKnown = 0x2,
  NlsoDhcp = 0x3,
  NlsoLinkLayerAddress = 0x4,
  NlsoRandom = 0x5,
  IpSuffixOriginOther = 0x0,
  IpSuffixOriginManual = 0x1,
  IpSuffixOriginWellKnown = 0x2,
  IpSuffixOriginDhcp = 0x3,
  IpSuffixOriginLinkLayerAddress = 0x4,
  IpSuffixOriginRandom = 0x5,
  IpSuffixOriginUnchanged = 0x10,
};

```

### `NL_DAD_STATE`
```
enum NL_DAD_STATE : __int32
{
  NldsInvalid = 0x0,
  NldsTentative = 0x1,
  NldsDuplicate = 0x2,
  NldsDeprecated = 0x3,
  NldsPreferred = 0x4,
  IpDadStateInvalid = 0x0,
  IpDadStateTentative = 0x1,
  IpDadStateDuplicate = 0x2,
  IpDadStateDeprecated = 0x3,
  IpDadStatePreferred = 0x4,
};

```

### `NegotiationIdentifiers`
```
enum NegotiationIdentifiers : __int32
{
  ID_NONCE_REQUEST = 0x0,
  ID_NONCE_REPLY = 0x1,
  ID_HASHED_NONCE_AND_PASSWORD = 0x2,
};

```

### `naivety`
```
enum naivety : __int32
{
  OFFSET_ERROR = 0x0,
  OFFSET_UNKNOWN = 0x1,
  OFFSET_NAIVE = 0x2,
  OFFSET_AWARE = 0x3,
};

```

### `NL_ADDRESS_TYPE`
```
enum NL_ADDRESS_TYPE : __int32
{
  NlatUnspecified = 0x0,
  NlatUnicast = 0x1,
  NlatAnycast = 0x2,
  NlatMulticast = 0x3,
  NlatBroadcast = 0x4,
  NlatInvalid = 0x5,
};

```

### `NVSDK_NGX_Result`
```
enum NVSDK_NGX_Result : __int32
{
  NVSDK_NGX_Result_Success = 0x1,
  NVSDK_NGX_Result_Fail = 0xBAD00000,
  NVSDK_NGX_Result_FAIL_FeatureNotSupported = 0xBAD00001,
  NVSDK_NGX_Result_FAIL_PlatformError = 0xBAD00002,
  NVSDK_NGX_Result_FAIL_FeatureAlreadyExists = 0xBAD00003,
  NVSDK_NGX_Result_FAIL_FeatureNotFound = 0xBAD00004,
  NVSDK_NGX_Result_FAIL_InvalidParameter = 0xBAD00005,
  NVSDK_NGX_Result_FAIL_ScratchBufferTooSmall = 0xBAD00006,
  NVSDK_NGX_Result_FAIL_NotInitialized = 0xBAD00007,
  NVSDK_NGX_Result_FAIL_UnsupportedInputFormat = 0xBAD00008,
  NVSDK_NGX_Result_FAIL_RWFlagMissing = 0xBAD00009,
  NVSDK_NGX_Result_FAIL_MissingInput = 0xBAD0000A,
  NVSDK_NGX_Result_FAIL_UnableToInitializeFeature = 0xBAD0000B,
  NVSDK_NGX_Result_FAIL_OutOfDate = 0xBAD0000C,
  NVSDK_NGX_Result_FAIL_OutOfGPUMemory = 0xBAD0000D,
  NVSDK_NGX_Result_FAIL_UnsupportedFormat = 0xBAD0000E,
  NVSDK_NGX_Result_FAIL_UnableToWriteToAppDataPath = 0xBAD0000F,
  NVSDK_NGX_Result_FAIL_UnsupportedParameter = 0xBAD00010,
};

```

### `NVSDK_NGX_Version`
```
enum NVSDK_NGX_Version : __int32
{
  NVSDK_NGX_Version_API = 0x13,
};

```

### `NVSDK_NGX_Feature`
```
enum NVSDK_NGX_Feature : __int32
{
  NVSDK_NGX_Feature_Reserved0 = 0x0,
  NVSDK_NGX_Feature_SuperSampling = 0x1,
  NVSDK_NGX_Feature_InPainting = 0x2,
  NVSDK_NGX_Feature_ImageSuperResolution = 0x3,
  NVSDK_NGX_Feature_SlowMotion = 0x4,
  NVSDK_NGX_Feature_VideoSuperResolution = 0x5,
  NVSDK_NGX_Feature_Reserved1 = 0x6,
  NVSDK_NGX_Feature_Reserved2 = 0x7,
  NVSDK_NGX_Feature_Reserved3 = 0x8,
  NVSDK_NGX_Feature_ImageSignalProcessing = 0x9,
  NVSDK_NGX_Feature_DeepResolve = 0xA,
  NVSDK_NGX_Feature_Reserved4 = 0xB,
  NVSDK_NGX_Feature_Count = 0xC,
};

```

### `NVSDK_NGX_GBufferType`
```
enum NVSDK_NGX_GBufferType : __int32
{
  NVSDK_NGX_GBUFFER_ALBEDO = 0x0,
  NVSDK_NGX_GBUFFER_ROUGHNESS = 0x1,
  NVSDK_NGX_GBUFFER_METALLIC = 0x2,
  NVSDK_NGX_GBUFFER_SPECULAR = 0x3,
  NVSDK_NGX_GBUFFER_SUBSURFACE = 0x4,
  NVSDK_NGX_GBUFFER_NORMALS = 0x5,
  NVSDK_NGX_GBUFFER_SHADINGMODELID = 0x6,
  NVSDK_NGX_GBUFFER_MATERIALID = 0x7,
  NVSDK_NGX_GBUFFERTYPE_NUM = 0x10,
};

```

### `NVSDK_NGX_DLSS_Feature_Flags`
```
enum NVSDK_NGX_DLSS_Feature_Flags : __int32
{
  NVSDK_NGX_DLSS_Feature_Flags_IsInvalid = 0x80000000,
  NVSDK_NGX_DLSS_Feature_Flags_None = 0x0,
  NVSDK_NGX_DLSS_Feature_Flags_IsHDR = 0x1,
  NVSDK_NGX_DLSS_Feature_Flags_MVLowRes = 0x2,
  NVSDK_NGX_DLSS_Feature_Flags_MVJittered = 0x4,
  NVSDK_NGX_DLSS_Feature_Flags_DepthInverted = 0x8,
  NVSDK_NGX_DLSS_Feature_Flags_Reserved_0 = 0x10,
  NVSDK_NGX_DLSS_Feature_Flags_DoSharpening = 0x20,
};

```

