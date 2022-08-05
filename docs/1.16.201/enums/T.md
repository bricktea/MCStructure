# T
### `TransformSpace`
Name | Value
-|-
Invalid | `0`
MinecraftAbsoluteSpace | `1`
MinecraftSteveRelativeSpace | `2`
MinecraftViewSpace | `3`
MinecraftProjSpace | `4`
UIPixelSpace | `5`
UINormalizedSpace | `6`
HoloLivingRoomScreenAnchorSpace | `7`
HoloUIAnchorSpace | `8`
HoloHeadlockedSpace | `9`
HoloAugmentedScreenAnchorSpace | `10`
HoloViewerAnchorSpace | `11`
HoloRealWorldAbsoluteSpace | `12`
HoloSRAnchorSpace | `13`
HoloRealityAnchorSpace | `14`
HoloPoseSpace | `15`
HoloHeadGazeSpace | `16`
HoloLeftHandSpace | `17`
HoloRightHandSpace | `18`
HoloAimSpace | `19`
HoloHeadCameraSpace | `20`
HoloLeftViewSpace | `21`
HoloRightViewSpace | `22`
HoloLeftProjSpace | `23`
HoloRightProjSpace | `24`
HoloLeftEarSpace | `25`
HoloRightEarSpace | `26`


### `TrustedSkinFlag`
Name | Value
-|-
Unset | `0`
False | `1`
True | `2`


### `TickingQueueType`
Name | Value
-|-
Internal | `0`


### `TransferRoomPrivacy`
Name | Value
-|-
PUBLIC | `0`
FRIENDS_ONLY | `1`
PRIVATE | `2`
NOT_READY | `3`


### `TransferRoomPlatform`
Name | Value
-|-
PC_AND_PE | `0`
ONLY_PE | `16`
ONLY_PC | `32`


### `T1_FieldLocation_`
Name | Value
-|-
T1_FIELD_LOCATION_CID_INFO | `0`
T1_FIELD_LOCATION_FONT_DICT | `1`
T1_FIELD_LOCATION_FONT_EXTRA | `2`
T1_FIELD_LOCATION_FONT_INFO | `3`
T1_FIELD_LOCATION_PRIVATE | `4`
T1_FIELD_LOCATION_BBOX | `5`
T1_FIELD_LOCATION_LOADER | `6`
T1_FIELD_LOCATION_FACE | `7`
T1_FIELD_LOCATION_BLEND | `8`
T1_FIELD_LOCATION_MAX | `9`


### `T1_FieldType_`
Name | Value
-|-
T1_FIELD_TYPE_NONE | `0`
T1_FIELD_TYPE_BOOL | `1`
T1_FIELD_TYPE_INTEGER | `2`
T1_FIELD_TYPE_FIXED | `3`
T1_FIELD_TYPE_FIXED_1000 | `4`
T1_FIELD_TYPE_STRING | `5`
T1_FIELD_TYPE_KEY | `6`
T1_FIELD_TYPE_BBOX | `7`
T1_FIELD_TYPE_MM_BBOX | `8`
T1_FIELD_TYPE_INTEGER_ARRAY | `9`
T1_FIELD_TYPE_FIXED_ARRAY | `10`
T1_FIELD_TYPE_CALLBACK | `11`
T1_FIELD_TYPE_MAX | `12`


### `TorchFacing`
Name | Value
-|-


### `TextureLoadState`
Name | Value
-|-
UnloadedBit | `0`
PendingBit | `1`
LoadedBit | `2`
PendingMetadata | `4`
LoadedMetadata | `8`


### `TaskOptions`
Name | Value
-|-


### `TouchState`
Name | Value
-|-
Clicked | `0`
Pressed | `1`
Released | `2`


### `TouchEventResult`
Name | Value
-|-
NotHandled | `0`
Handled | `1`
HandledNotConsumed | `2`


### `TextPacketType`
Name | Value
-|-
AppendedFiles | `0`
Raw | `1`


### `TabbedUpsellScreenDefaultTab`
Name | Value
-|-


### `TTSEnabledStatus`
Name | Value
-|-
NotEnabled | `0`
EnabledByDefault | `1`
EnabledByPlatform | `2`
EnabledByXBL | `3`
EnabledPreviously | `4`


### `TerrainVariation`
Name | Value
-|-


### `TextureSetHelpers::TextureSetDefinitionLoader::LoadMode`
Name | Value
-|-
ExplicitDefinitionOnly | `0`
ImageDescription | `1`
AllLayers | `2`


### `TextureSetHelpers::TextureSetDefinitionLoader::ColorPipeline`
Name | Value
-|-
Classic | `0`
Snap | `1`
Wheel | `2`
SnapWheel | `3`


### `TextureLoadMode`
Name | Value
-|-
TextureDescriptionOnly | `0`
FullTexture | `1`


### `TreeHelper::AttachableDecoration::GrowthDirection`
Name | Value
-|-
Up | `0`
Down | `1`


### `Token::Type`
Name | Value
-|-


### `TargetSelectionMethod`
Name | Value
-|-


### `TallGrassType`
Name | Value
-|-


### `TUNNEL_TYPE`
Name | Value
-|-
TUNNEL_TYPE_NONE | `0`
TUNNEL_TYPE_OTHER | `1`
TUNNEL_TYPE_DIRECT | `2`
TUNNEL_TYPE_6TO4 | `11`
TUNNEL_TYPE_ISATAP | `13`
TUNNEL_TYPE_TEREDO | `14`
TUNNEL_TYPE_IPHTTPS | `15`


### `TouchStateRequirement::<unnamed_enum_Pressed>`
Name | Value
-|-


### `T1_ParseState_`
Name | Value
-|-
T1_Parse_Start | `0`
T1_Parse_Have_Width | `1`
T1_Parse_Have_Moveto | `2`
T1_Parse_Have_Path | `3`


### `T1_TokenType_`
Name | Value
-|-
T1_TOKEN_TYPE_NONE | `0`
T1_TOKEN_TYPE_ANY | `1`
T1_TOKEN_TYPE_STRING | `2`
T1_TOKEN_TYPE_ARRAY | `3`
T1_TOKEN_TYPE_KEY | `4`
T1_TOKEN_TYPE_MAX | `5`


### `TStates_`
Name | Value
-|-
Unknown_State | `0`
Ascending_State | `1`
Descending_State | `2`
Flat_State | `3`


### `tagAR_STATE`
```
enum tagAR_STATE : __int32
{
  AR_ENABLED = 0x0,
  AR_DISABLED = 0x1,
  AR_SUPPRESSED = 0x2,
  AR_REMOTESESSION = 0x4,
  AR_MULTIMON = 0x8,
  AR_NOSENSOR = 0x10,
  AR_NOT_SUPPORTED = 0x20,
  AR_DOCKED = 0x40,
  AR_LAPTOP = 0x80,
};

```

### `TrackType`
```
enum TrackType : __int8
{
  THIRD_BEZIER = 0x0,
  FOURTH_BEZIER = 0x1,
  FIXED = 0x2,
};

```

### `TaskStatus::Value`
```
typedef Bedrock::Threading::AsyncStatus TaskStatus::Value;

```

### `TaskGroupState`
```
typedef Core::FileAccessType TaskGroupState;

```

### `TaskRunResult`
```
enum TaskRunResult : __int32
{
  Requeue = 0x0,
  Done = 0x1,
  Noop = 0x2,
};

```

### `TransactionStatus`
```
enum TransactionStatus : __int32
{
  PurchaseStarted = 0x0,
  PurchaseSuccess = 0x1,
  PurchaseFailed = 0x2,
  PurchaseFailed_InsufficientFunds = 0x3,
  PurchaseFailed_PriceMismatch = 0x4,
  PurchaseCanceled = 0x5,
  FulfillmentStarted = 0x6,
  FulfillmentSuccess = 0x7,
  FulfillmentFailed = 0x8,
  FulfillmentFailed_ProfanityName = 0x9,
  CheckFulfillmentComplete = 0xA,
};

```

### `TransferState`
```
typedef cg::ColorSpace TransferState;

```

### `TransformEnum`
```
enum TransformEnum : __int32
{
  TransformSkin = 0x1,
  TransformHorse = 0x2,
  TransformWeapon = 0x4,
};

```

### `TaskType`
```
enum TaskType : __int32
{
  Flushable = 0x0,
};

```

### `Tag::Type`
```
typedef OptionType Tag::Type;

```

### `TravelType`
```
typedef MaterialType TravelType;

```

### `typeid_t<IScreenCapabilities>::NewIDType`
```
enum typeid_t<IScreenCapabilities>::NewIDType : __int32
{
  New = 0x0,
};

```

### `TrialUpgradePurchaseTier`
```
enum TrialUpgradePurchaseTier : __int32
{
  FullGame = 0x0,
  StarterCollection = 0x1,
  MasterCollection = 0x2,
};

```

### `ToastMessageType`
```
typedef cg::ColorSpace ToastMessageType;

```

### `TriggerIndiciesEnum`
```
typedef ResourcePackStackType TriggerIndiciesEnum;

```

### `TestCommandType`
```
enum TestCommandType : __int32
{
};

```

### `TestAssetCommandType`
```
enum TestAssetCommandType : __int32
{
};

```

### `TextCharEventResult`
```
typedef Rotation TextCharEventResult;

```

### `TemplateLockState`
```
typedef DimensionId TemplateLockState;

```

### `TitleInfo::TitleId`
```
typedef cg::ColorSpace TitleInfo::TitleId;

```

### `ToggleManagerBehavior`
```
enum ToggleManagerBehavior : __int32
{
  ClearAll = 0x0,
  SelectAll = 0x1,
  GatherAll = 0x2,
  DefaultAll = 0x3,
};

```

### `TimerType`
```
typedef NavButtonLinksTo TimerType;

```

### `TextureAtlasItemTextureSetTranslation::Channel`
```
enum TextureAtlasItemTextureSetTranslation::Channel : __int8
{
  Red = 0x0,
  Green = 0x1,
  Blue = 0x2,
  Alpha = 0x3,
  X = 0x0,
  Y = 0x1,
  Z = 0x2,
  W = 0x3,
};

```

### `TerrainLayer::Transparency`
```
typedef Rotation TerrainLayer::Transparency;

```

### `TerrainLayer::Detail`
```
enum TerrainLayer::Detail : __int32
{
  Near = 0x0,
  Far = 0x1,
};

```

### `TrackerType`
```
typedef DimensionId TrackerType;

```

### `tagBINDSTRING`
```
enum tagBINDSTRING : __int32
{
  BINDSTRING_HEADERS = 0x1,
  BINDSTRING_ACCEPT_MIMES = 0x2,
  BINDSTRING_EXTRA_URL = 0x3,
  BINDSTRING_LANGUAGE = 0x4,
  BINDSTRING_USERNAME = 0x5,
  BINDSTRING_PASSWORD = 0x6,
  BINDSTRING_UA_PIXELS = 0x7,
  BINDSTRING_UA_COLOR = 0x8,
  BINDSTRING_OS = 0x9,
  BINDSTRING_USER_AGENT = 0xA,
  BINDSTRING_ACCEPT_ENCODINGS = 0xB,
  BINDSTRING_POST_COOKIE = 0xC,
  BINDSTRING_POST_DATA_MIME = 0xD,
  BINDSTRING_URL = 0xE,
  BINDSTRING_IID = 0xF,
  BINDSTRING_FLAG_BIND_TO_OBJECT = 0x10,
  BINDSTRING_PTR_BIND_CONTEXT = 0x11,
  BINDSTRING_XDR_ORIGIN = 0x12,
  BINDSTRING_DOWNLOADPATH = 0x13,
  BINDSTRING_ROOTDOC_URL = 0x14,
  BINDSTRING_INITIAL_FILENAME = 0x15,
  BINDSTRING_PROXY_USERNAME = 0x16,
  BINDSTRING_PROXY_PASSWORD = 0x17,
  BINDSTRING_ENTERPRISE_ID = 0x18,
  BINDSTRING_DOC_URL = 0x19,
  BINDSTRING_SAMESITE_COOKIE_LEVEL = 0x1A,
};

```

### `tagRPCOPT_PROPERTIES`
```
enum tagRPCOPT_PROPERTIES : __int32
{
  COMBND_RPCTIMEOUT = 0x1,
  COMBND_SERVER_LOCALITY = 0x2,
  COMBND_RESERVED1 = 0x4,
  COMBND_RESERVED2 = 0x5,
  COMBND_RESERVED3 = 0x8,
  COMBND_RESERVED4 = 0x10,
};

```

### `tagVARKIND`
```
enum tagVARKIND : __int32
{
  VAR_PERINSTANCE = 0x0,
  VAR_STATIC = 0x1,
  VAR_CONST = 0x2,
  VAR_DISPATCH = 0x3,
};

```

### `tagDVASPECT`
```
enum tagDVASPECT : __int32
{
  DVASPECT_CONTENT = 0x1,
  DVASPECT_THUMBNAIL = 0x2,
  DVASPECT_ICON = 0x4,
  DVASPECT_DOCPRINT = 0x8,
};

```

### `tagCOMSD`
```
enum tagCOMSD : __int32
{
  SD_LAUNCHPERMISSIONS = 0x0,
  SD_ACCESSPERMISSIONS = 0x1,
  SD_LAUNCHRESTRICTIONS = 0x2,
  SD_ACCESSRESTRICTIONS = 0x3,
};

```

### `tagBINDSTATUS`
```
enum tagBINDSTATUS : __int32
{
  BINDSTATUS_FINDINGRESOURCE = 0x1,
  BINDSTATUS_CONNECTING = 0x2,
  BINDSTATUS_REDIRECTING = 0x3,
  BINDSTATUS_BEGINDOWNLOADDATA = 0x4,
  BINDSTATUS_DOWNLOADINGDATA = 0x5,
  BINDSTATUS_ENDDOWNLOADDATA = 0x6,
  BINDSTATUS_BEGINDOWNLOADCOMPONENTS = 0x7,
  BINDSTATUS_INSTALLINGCOMPONENTS = 0x8,
  BINDSTATUS_ENDDOWNLOADCOMPONENTS = 0x9,
  BINDSTATUS_USINGCACHEDCOPY = 0xA,
  BINDSTATUS_SENDINGREQUEST = 0xB,
  BINDSTATUS_CLASSIDAVAILABLE = 0xC,
  BINDSTATUS_MIMETYPEAVAILABLE = 0xD,
  BINDSTATUS_CACHEFILENAMEAVAILABLE = 0xE,
  BINDSTATUS_BEGINSYNCOPERATION = 0xF,
  BINDSTATUS_ENDSYNCOPERATION = 0x10,
  BINDSTATUS_BEGINUPLOADDATA = 0x11,
  BINDSTATUS_UPLOADINGDATA = 0x12,
  BINDSTATUS_ENDUPLOADDATA = 0x13,
  BINDSTATUS_PROTOCOLCLASSID = 0x14,
  BINDSTATUS_ENCODING = 0x15,
  BINDSTATUS_VERIFIEDMIMETYPEAVAILABLE = 0x16,
  BINDSTATUS_CLASSINSTALLLOCATION = 0x17,
  BINDSTATUS_DECODING = 0x18,
  BINDSTATUS_LOADINGMIMEHANDLER = 0x19,
  BINDSTATUS_CONTENTDISPOSITIONATTACH = 0x1A,
  BINDSTATUS_FILTERREPORTMIMETYPE = 0x1B,
  BINDSTATUS_CLSIDCANINSTANTIATE = 0x1C,
  BINDSTATUS_IUNKNOWNAVAILABLE = 0x1D,
  BINDSTATUS_DIRECTBIND = 0x1E,
  BINDSTATUS_RAWMIMETYPE = 0x1F,
  BINDSTATUS_PROXYDETECTING = 0x20,
  BINDSTATUS_ACCEPTRANGES = 0x21,
  BINDSTATUS_COOKIE_SENT = 0x22,
  BINDSTATUS_COMPACT_POLICY_RECEIVED = 0x23,
  BINDSTATUS_COOKIE_SUPPRESSED = 0x24,
  BINDSTATUS_COOKIE_STATE_UNKNOWN = 0x25,
  BINDSTATUS_COOKIE_STATE_ACCEPT = 0x26,
  BINDSTATUS_COOKIE_STATE_REJECT = 0x27,
  BINDSTATUS_COOKIE_STATE_PROMPT = 0x28,
  BINDSTATUS_COOKIE_STATE_LEASH = 0x29,
  BINDSTATUS_COOKIE_STATE_DOWNGRADE = 0x2A,
  BINDSTATUS_POLICY_HREF = 0x2B,
  BINDSTATUS_P3P_HEADER = 0x2C,
  BINDSTATUS_SESSION_COOKIE_RECEIVED = 0x2D,
  BINDSTATUS_PERSISTENT_COOKIE_RECEIVED = 0x2E,
  BINDSTATUS_SESSION_COOKIES_ALLOWED = 0x2F,
  BINDSTATUS_CACHECONTROL = 0x30,
  BINDSTATUS_CONTENTDISPOSITIONFILENAME = 0x31,
  BINDSTATUS_MIMETEXTPLAINMISMATCH = 0x32,
  BINDSTATUS_PUBLISHERAVAILABLE = 0x33,
  BINDSTATUS_DISPLAYNAMEAVAILABLE = 0x34,
  BINDSTATUS_SSLUX_NAVBLOCKED = 0x35,
  BINDSTATUS_SERVER_MIMETYPEAVAILABLE = 0x36,
  BINDSTATUS_SNIFFED_CLASSIDAVAILABLE = 0x37,
  BINDSTATUS_64BIT_PROGRESS = 0x38,
  BINDSTATUS_LAST = 0x38,
  BINDSTATUS_RESERVED_0 = 0x39,
  BINDSTATUS_RESERVED_1 = 0x3A,
  BINDSTATUS_RESERVED_2 = 0x3B,
  BINDSTATUS_RESERVED_3 = 0x3C,
  BINDSTATUS_RESERVED_4 = 0x3D,
  BINDSTATUS_RESERVED_5 = 0x3E,
  BINDSTATUS_RESERVED_6 = 0x3F,
  BINDSTATUS_RESERVED_7 = 0x40,
  BINDSTATUS_RESERVED_8 = 0x41,
  BINDSTATUS_RESERVED_9 = 0x42,
  BINDSTATUS_RESERVED_A = 0x43,
  BINDSTATUS_RESERVED_B = 0x44,
  BINDSTATUS_RESERVED_C = 0x45,
  BINDSTATUS_RESERVED_D = 0x46,
  BINDSTATUS_RESERVED_E = 0x47,
  BINDSTATUS_RESERVED_F = 0x48,
  BINDSTATUS_RESERVED_10 = 0x49,
  BINDSTATUS_RESERVED_11 = 0x4A,
  BINDSTATUS_RESERVED_12 = 0x4B,
  BINDSTATUS_RESERVED_13 = 0x4C,
  BINDSTATUS_LAST_PRIVATE = 0x4C,
};

```

### `tagDOMNodeType`
```
enum tagDOMNodeType : __int32
{
  NODE_INVALID = 0x0,
  NODE_ELEMENT = 0x1,
  NODE_ATTRIBUTE = 0x2,
  NODE_TEXT = 0x3,
  NODE_CDATA_SECTION = 0x4,
  NODE_ENTITY_REFERENCE = 0x5,
  NODE_ENTITY = 0x6,
  NODE_PROCESSING_INSTRUCTION = 0x7,
  NODE_COMMENT = 0x8,
  NODE_DOCUMENT = 0x9,
  NODE_DOCUMENT_TYPE = 0xA,
  NODE_DOCUMENT_FRAGMENT = 0xB,
  NODE_NOTATION = 0xC,
};

```

### `tagGLOBALOPT_RO_FLAGS`
```
enum tagGLOBALOPT_RO_FLAGS : __int32
{
  COMGLB_STA_MODALLOOP_REMOVE_TOUCH_MESSAGES = 0x1,
  COMGLB_STA_MODALLOOP_SHARED_QUEUE_REMOVE_INPUT_MESSAGES = 0x2,
  COMGLB_STA_MODALLOOP_SHARED_QUEUE_DONOT_REMOVE_INPUT_MESSAGES = 0x4,
  COMGLB_FAST_RUNDOWN = 0x8,
  COMGLB_RESERVED1 = 0x10,
  COMGLB_RESERVED2 = 0x20,
  COMGLB_RESERVED3 = 0x40,
  COMGLB_STA_MODALLOOP_SHARED_QUEUE_REORDER_POINTER_MESSAGES = 0x80,
  COMGLB_RESERVED4 = 0x100,
  COMGLB_RESERVED5 = 0x200,
  COMGLB_RESERVED6 = 0x400,
};

```

### `tagOLEMISC`
```
enum tagOLEMISC : __int32
{
  OLEMISC_RECOMPOSEONRESIZE = 0x1,
  OLEMISC_ONLYICONIC = 0x2,
  OLEMISC_INSERTNOTREPLACE = 0x4,
  OLEMISC_STATIC = 0x8,
  OLEMISC_CANTLINKINSIDE = 0x10,
  OLEMISC_CANLINKBYOLE1 = 0x20,
  OLEMISC_ISLINKOBJECT = 0x40,
  OLEMISC_INSIDEOUT = 0x80,
  OLEMISC_ACTIVATEWHENVISIBLE = 0x100,
  OLEMISC_RENDERINGISDEVICEINDEPENDENT = 0x200,
  OLEMISC_INVISIBLEATRUNTIME = 0x400,
  OLEMISC_ALWAYSRUN = 0x800,
  OLEMISC_ACTSLIKEBUTTON = 0x1000,
  OLEMISC_ACTSLIKELABEL = 0x2000,
  OLEMISC_NOUIACTIVATE = 0x4000,
  OLEMISC_ALIGNABLE = 0x8000,
  OLEMISC_SIMPLEFRAME = 0x10000,
  OLEMISC_SETCLIENTSITEFIRST = 0x20000,
  OLEMISC_IMEMODE = 0x40000,
  OLEMISC_IGNOREACTIVATEWHENVISIBLE = 0x80000,
  OLEMISC_WANTSTOMENUMERGE = 0x100000,
  OLEMISC_SUPPORTSMULTILEVELUNDO = 0x200000,
};

```

### `tagTYMED`
```
enum tagTYMED : __int32
{
  TYMED_HGLOBAL = 0x1,
  TYMED_FILE = 0x2,
  TYMED_ISTREAM = 0x4,
  TYMED_ISTORAGE = 0x8,
  TYMED_GDI = 0x10,
  TYMED_MFPICT = 0x20,
  TYMED_ENHMF = 0x40,
  TYMED_NULL = 0x0,
};

```

### `tagCHANGEKIND`
```
enum tagCHANGEKIND : __int32
{
  CHANGEKIND_ADDMEMBER = 0x0,
  CHANGEKIND_DELETEMEMBER = 0x1,
  CHANGEKIND_SETNAMES = 0x2,
  CHANGEKIND_SETDOCUMENTATION = 0x3,
  CHANGEKIND_GENERAL = 0x4,
  CHANGEKIND_INVALIDATE = 0x5,
  CHANGEKIND_CHANGEFAILED = 0x6,
  CHANGEKIND_MAX = 0x7,
};

```

### `tagMSHLFLAGS`
```
enum tagMSHLFLAGS : __int32
{
  MSHLFLAGS_NORMAL = 0x0,
  MSHLFLAGS_TABLESTRONG = 0x1,
  MSHLFLAGS_TABLEWEAK = 0x2,
  MSHLFLAGS_NOPING = 0x4,
  MSHLFLAGS_RESERVED1 = 0x8,
  MSHLFLAGS_RESERVED2 = 0x10,
  MSHLFLAGS_RESERVED3 = 0x20,
  MSHLFLAGS_RESERVED4 = 0x40,
};

```

### `tagEOLE_AUTHENTICATION_CAPABILITIES`
```
enum tagEOLE_AUTHENTICATION_CAPABILITIES : __int32
{
  EOAC_NONE = 0x0,
  EOAC_MUTUAL_AUTH = 0x1,
  EOAC_STATIC_CLOAKING = 0x20,
  EOAC_DYNAMIC_CLOAKING = 0x40,
  EOAC_ANY_AUTHORITY = 0x80,
  EOAC_MAKE_FULLSIC = 0x100,
  EOAC_DEFAULT = 0x800,
  EOAC_SECURE_REFS = 0x2,
  EOAC_ACCESS_CONTROL = 0x4,
  EOAC_APPID = 0x8,
  EOAC_DYNAMIC = 0x10,
  EOAC_REQUIRE_FULLSIC = 0x200,
  EOAC_AUTO_IMPERSONATE = 0x400,
  EOAC_DISABLE_AAA = 0x1000,
  EOAC_NO_CUSTOM_MARSHAL = 0x2000,
  EOAC_RESERVED1 = 0x4000,
};

```

### `tagINPUT_MESSAGE_DEVICE_TYPE`
```
enum tagINPUT_MESSAGE_DEVICE_TYPE : __int32
{
  IMDT_UNAVAILABLE = 0x0,
  IMDT_KEYBOARD = 0x1,
  IMDT_MOUSE = 0x2,
  IMDT_TOUCH = 0x4,
  IMDT_PEN = 0x8,
};

```

### `tagMKREDUCE`
```
enum tagMKREDUCE : __int32
{
  MKRREDUCE_ONE = 0x30000,
  MKRREDUCE_TOUSER = 0x20000,
  MKRREDUCE_THROUGHUSER = 0x10000,
  MKRREDUCE_ALL = 0x0,
};

```

### `tagREGKIND`
```
enum tagREGKIND : __int32
{
  REGKIND_DEFAULT = 0x0,
  REGKIND_REGISTER = 0x1,
  REGKIND_NONE = 0x2,
};

```

### `tagFUNCKIND`
```
enum tagFUNCKIND : __int32
{
  FUNC_VIRTUAL = 0x0,
  FUNC_PUREVIRTUAL = 0x1,
  FUNC_NONVIRTUAL = 0x2,
  FUNC_STATIC = 0x3,
  FUNC_DISPATCH = 0x4,
};

```

### `tagLOCKTYPE`
```
enum tagLOCKTYPE : __int32
{
  LOCK_WRITE = 0x1,
  LOCK_EXCLUSIVE = 0x2,
  LOCK_ONLYONCE = 0x4,
};

```

### `tagExtendedErrorParamTypes`
```
enum tagExtendedErrorParamTypes : __int32
{
  eeptAnsiString = 0x1,
  eeptUnicodeString = 0x2,
  eeptLongVal = 0x3,
  eeptShortVal = 0x4,
  eeptPointerVal = 0x5,
  eeptNone = 0x6,
  eeptBinary = 0x7,
};

```

### `tagCOINITBASE`
```
enum tagCOINITBASE : __int32
{
  COINITBASE_MULTITHREADED = 0x0,
};

```

### `tagSF_TYPE`
```
enum tagSF_TYPE : __int32
{
  SF_ERROR = 0xA,
  SF_I1 = 0x10,
  SF_I2 = 0x2,
  SF_I4 = 0x3,
  SF_I8 = 0x14,
  SF_BSTR = 0x8,
  SF_UNKNOWN = 0xD,
  SF_DISPATCH = 0x9,
  SF_VARIANT = 0xC,
  SF_RECORD = 0x24,
  SF_HAVEIID = 0x800D,
};

```

### `tagADVF`
```
enum tagADVF : __int32
{
  ADVF_NODATA = 0x1,
  ADVF_PRIMEFIRST = 0x2,
  ADVF_ONLYONCE = 0x4,
  ADVF_DATAONSTOP = 0x40,
  ADVFCACHE_NOHANDLER = 0x8,
  ADVFCACHE_FORCEBUILTIN = 0x10,
  ADVFCACHE_ONSAVE = 0x20,
};

```

### `tagDESCKIND`
```
enum tagDESCKIND : __int32
{
  DESCKIND_NONE = 0x0,
  DESCKIND_FUNCDESC = 0x1,
  DESCKIND_VARDESC = 0x2,
  DESCKIND_TYPECOMP = 0x3,
  DESCKIND_IMPLICITAPPOBJ = 0x4,
  DESCKIND_MAX = 0x5,
};

```

### `tagTYPEFLAGS`
```
enum tagTYPEFLAGS : __int32
{
  TYPEFLAG_FAPPOBJECT = 0x1,
  TYPEFLAG_FCANCREATE = 0x2,
  TYPEFLAG_FLICENSED = 0x4,
  TYPEFLAG_FPREDECLID = 0x8,
  TYPEFLAG_FHIDDEN = 0x10,
  TYPEFLAG_FCONTROL = 0x20,
  TYPEFLAG_FDUAL = 0x40,
  TYPEFLAG_FNONEXTENSIBLE = 0x80,
  TYPEFLAG_FOLEAUTOMATION = 0x100,
  TYPEFLAG_FRESTRICTED = 0x200,
  TYPEFLAG_FAGGREGATABLE = 0x400,
  TYPEFLAG_FREPLACEABLE = 0x800,
  TYPEFLAG_FDISPATCHABLE = 0x1000,
  TYPEFLAG_FREVERSEBIND = 0x2000,
  TYPEFLAG_FPROXY = 0x4000,
};

```

### `tagFUNCFLAGS`
```
enum tagFUNCFLAGS : __int32
{
  FUNCFLAG_FRESTRICTED = 0x1,
  FUNCFLAG_FSOURCE = 0x2,
  FUNCFLAG_FBINDABLE = 0x4,
  FUNCFLAG_FREQUESTEDIT = 0x8,
  FUNCFLAG_FDISPLAYBIND = 0x10,
  FUNCFLAG_FDEFAULTBIND = 0x20,
  FUNCFLAG_FHIDDEN = 0x40,
  FUNCFLAG_FUSESGETLASTERROR = 0x80,
  FUNCFLAG_FDEFAULTCOLLELEM = 0x100,
  FUNCFLAG_FUIDEFAULT = 0x200,
  FUNCFLAG_FNONBROWSABLE = 0x400,
  FUNCFLAG_FREPLACEABLE = 0x800,
  FUNCFLAG_FIMMEDIATEBIND = 0x1000,
};

```

### `tagMKSYS`
```
enum tagMKSYS : __int32
{
  MKSYS_NONE = 0x0,
  MKSYS_GENERICCOMPOSITE = 0x1,
  MKSYS_FILEMONIKER = 0x2,
  MKSYS_ANTIMONIKER = 0x3,
  MKSYS_ITEMMONIKER = 0x4,
  MKSYS_POINTERMONIKER = 0x5,
  MKSYS_CLASSMONIKER = 0x7,
  MKSYS_OBJREFMONIKER = 0x8,
  MKSYS_SESSIONMONIKER = 0x9,
  MKSYS_LUAMONIKER = 0xA,
};

```

### `tagCLSCTX`
```
enum tagCLSCTX : __int32
{
  CLSCTX_INPROC_SERVER = 0x1,
  CLSCTX_INPROC_HANDLER = 0x2,
  CLSCTX_LOCAL_SERVER = 0x4,
  CLSCTX_INPROC_SERVER16 = 0x8,
  CLSCTX_REMOTE_SERVER = 0x10,
  CLSCTX_INPROC_HANDLER16 = 0x20,
  CLSCTX_RESERVED1 = 0x40,
  CLSCTX_RESERVED2 = 0x80,
  CLSCTX_RESERVED3 = 0x100,
  CLSCTX_RESERVED4 = 0x200,
  CLSCTX_NO_CODE_DOWNLOAD = 0x400,
  CLSCTX_RESERVED5 = 0x800,
  CLSCTX_NO_CUSTOM_MARSHAL = 0x1000,
  CLSCTX_ENABLE_CODE_DOWNLOAD = 0x2000,
  CLSCTX_NO_FAILURE_LOG = 0x4000,
  CLSCTX_DISABLE_AAA = 0x8000,
  CLSCTX_ENABLE_AAA = 0x10000,
  CLSCTX_FROM_DEFAULT_CONTEXT = 0x20000,
  CLSCTX_ACTIVATE_X86_SERVER = 0x40000,
  CLSCTX_ACTIVATE_32_BIT_SERVER = 0x40000,
  CLSCTX_ACTIVATE_64_BIT_SERVER = 0x80000,
  CLSCTX_ENABLE_CLOAKING = 0x100000,
  CLSCTX_APPCONTAINER = 0x400000,
  CLSCTX_ACTIVATE_AAA_AS_IU = 0x800000,
  CLSCTX_RESERVED6 = 0x1000000,
  CLSCTX_ACTIVATE_ARM32_SERVER = 0x2000000,
  CLSCTX_PS_DLL = 0x80000000,
};

```

### `tagURLZONE`
```
enum tagURLZONE : __int32
{
  URLZONE_INVALID = 0xFFFFFFFF,
  URLZONE_PREDEFINED_MIN = 0x0,
  URLZONE_LOCAL_MACHINE = 0x0,
  URLZONE_INTRANET = 0x1,
  URLZONE_TRUSTED = 0x2,
  URLZONE_INTERNET = 0x3,
  URLZONE_UNTRUSTED = 0x4,
  URLZONE_PREDEFINED_MAX = 0x3E7,
  URLZONE_USER_MIN = 0x3E8,
  URLZONE_USER_MAX = 0x2710,
};

```

### `tagINVOKEKIND`
```
enum tagINVOKEKIND : __int32
{
  INVOKE_FUNC = 0x1,
  INVOKE_PROPERTYGET = 0x2,
  INVOKE_PROPERTYPUT = 0x4,
  INVOKE_PROPERTYPUTREF = 0x8,
};

```

### `tagRPCOPT_SERVER_LOCALITY_VALUES`
```
enum tagRPCOPT_SERVER_LOCALITY_VALUES : __int32
{
  SERVER_LOCALITY_PROCESS_LOCAL = 0x0,
  SERVER_LOCALITY_MACHINE_LOCAL = 0x1,
  SERVER_LOCALITY_REMOTE = 0x2,
};

```

### `tagOLECONTF`
```
enum tagOLECONTF : __int32
{
  OLECONTF_EMBEDDINGS = 0x1,
  OLECONTF_LINKS = 0x2,
  OLECONTF_OTHERS = 0x4,
  OLECONTF_ONLYUSER = 0x8,
  OLECONTF_ONLYIFRUNNING = 0x10,
};

```

### `tagPENDINGMSG`
```
enum tagPENDINGMSG : __int32
{
  PENDINGMSG_CANCELCALL = 0x0,
  PENDINGMSG_WAITNOPROCESS = 0x1,
  PENDINGMSG_WAITDEFPROCESS = 0x2,
};

```

### `tagSERVERCALL`
```
enum tagSERVERCALL : __int32
{
  SERVERCALL_ISHANDLED = 0x0,
  SERVERCALL_REJECTED = 0x1,
  SERVERCALL_RETRYLATER = 0x2,
};

```

### `tagGLOBALOPT_PROPERTIES`
```
enum tagGLOBALOPT_PROPERTIES : __int32
{
  COMGLB_EXCEPTION_HANDLING = 0x1,
  COMGLB_APPID = 0x2,
  COMGLB_RPC_THREADPOOL_SETTING = 0x3,
  COMGLB_RO_SETTINGS = 0x4,
  COMGLB_UNMARSHALING_POLICY = 0x5,
  COMGLB_PROPERTIES_RESERVED1 = 0x6,
  COMGLB_PROPERTIES_RESERVED2 = 0x7,
  COMGLB_PROPERTIES_RESERVED3 = 0x8,
};

```

### `tagVARFLAGS`
```
enum tagVARFLAGS : __int32
{
  VARFLAG_FREADONLY = 0x1,
  VARFLAG_FSOURCE = 0x2,
  VARFLAG_FBINDABLE = 0x4,
  VARFLAG_FREQUESTEDIT = 0x8,
  VARFLAG_FDISPLAYBIND = 0x10,
  VARFLAG_FDEFAULTBIND = 0x20,
  VARFLAG_FHIDDEN = 0x40,
  VARFLAG_FRESTRICTED = 0x80,
  VARFLAG_FDEFAULTCOLLELEM = 0x100,
  VARFLAG_FUIDEFAULT = 0x200,
  VARFLAG_FNONBROWSABLE = 0x400,
  VARFLAG_FREPLACEABLE = 0x800,
  VARFLAG_FIMMEDIATEBIND = 0x1000,
};

```

### `tagSTGC`
```
enum tagSTGC : __int32
{
  STGC_DEFAULT = 0x0,
  STGC_OVERWRITE = 0x1,
  STGC_ONLYIFCURRENT = 0x2,
  STGC_DANGEROUSLYCOMMITMERELYTODISKCACHE = 0x4,
  STGC_CONSOLIDATE = 0x8,
};

```

### `tagOLEGETMONIKER`
```
enum tagOLEGETMONIKER : __int32
{
  OLEGETMONIKER_ONLYIFTHERE = 0x1,
  OLEGETMONIKER_FORCEASSIGN = 0x2,
  OLEGETMONIKER_UNASSIGN = 0x3,
  OLEGETMONIKER_TEMPFORUSER = 0x4,
};

```

### `tagCALLCONV`
```
enum tagCALLCONV : __int32
{
  CC_FASTCALL = 0x0,
  CC_CDECL = 0x1,
  CC_MSCPASCAL = 0x2,
  CC_PASCAL = 0x2,
  CC_MACPASCAL = 0x3,
  CC_STDCALL = 0x4,
  CC_FPFASTCALL = 0x5,
  CC_SYSCALL = 0x6,
  CC_MPWCDECL = 0x7,
  CC_MPWPASCAL = 0x8,
  CC_MAX = 0x9,
};

```

### `tagShutdownType`
```
enum tagShutdownType : __int32
{
  IdleShutdown = 0x0,
  ForcedShutdown = 0x1,
};

```

### `tagRpcLocalAddressFormat`
```
enum tagRpcLocalAddressFormat : __int32
{
  rlafInvalid = 0x0,
  rlafIPv4 = 0x1,
  rlafIPv6 = 0x2,
};

```

### `tagLIBFLAGS`
```
enum tagLIBFLAGS : __int32
{
  LIBFLAG_FRESTRICTED = 0x1,
  LIBFLAG_FCONTROL = 0x2,
  LIBFLAG_FHIDDEN = 0x4,
  LIBFLAG_FHASDISKIMAGE = 0x8,
};

```

### `tagGLOBALOPT_RPCTP_VALUES`
```
enum tagGLOBALOPT_RPCTP_VALUES : __int32
{
  COMGLB_RPC_THREADPOOL_SETTING_DEFAULT_POOL = 0x0,
  COMGLB_RPC_THREADPOOL_SETTING_PRIVATE_POOL = 0x1,
};

```

### `tagINPUT_MESSAGE_ORIGIN_ID`
```
enum tagINPUT_MESSAGE_ORIGIN_ID : __int32
{
  IMO_UNAVAILABLE = 0x0,
  IMO_HARDWARE = 0x1,
  IMO_INJECTED = 0x2,
  IMO_SYSTEM = 0x4,
};

```

### `tagCOWAIT_FLAGS`
```
enum tagCOWAIT_FLAGS : __int32
{
  COWAIT_DEFAULT = 0x0,
  COWAIT_WAITALL = 0x1,
  COWAIT_ALERTABLE = 0x2,
  COWAIT_INPUTAVAILABLE = 0x4,
  COWAIT_DISPATCH_CALLS = 0x8,
  COWAIT_DISPATCH_WINDOW_MESSAGES = 0x10,
};

```

### `tagSYSKIND`
```
enum tagSYSKIND : __int32
{
  SYS_WIN16 = 0x0,
  SYS_WIN32 = 0x1,
  SYS_MAC = 0x2,
  SYS_WIN64 = 0x3,
};

```

### `tagREGCLS`
```
enum tagREGCLS : __int32
{
  REGCLS_SINGLEUSE = 0x0,
  REGCLS_MULTIPLEUSE = 0x1,
  REGCLS_MULTI_SEPARATE = 0x2,
  REGCLS_SUSPENDED = 0x4,
  REGCLS_SURROGATE = 0x8,
};

```

### `tagTYPEKIND`
```
enum tagTYPEKIND : __int32
{
  TKIND_ENUM = 0x0,
  TKIND_RECORD = 0x1,
  TKIND_MODULE = 0x2,
  TKIND_INTERFACE = 0x3,
  TKIND_DISPATCH = 0x4,
  TKIND_COCLASS = 0x5,
  TKIND_ALIAS = 0x6,
  TKIND_UNION = 0x7,
  TKIND_MAX = 0x8,
};

```

### `tagRpcCallType`
```
enum tagRpcCallType : __int32
{
  rctInvalid = 0x0,
  rctNormal = 0x1,
  rctTraining = 0x2,
  rctGuaranteed = 0x3,
};

```

### `tagMSHCTX`
```
enum tagMSHCTX : __int32
{
  MSHCTX_LOCAL = 0x0,
  MSHCTX_NOSHAREDMEM = 0x1,
  MSHCTX_DIFFERENTMACHINE = 0x2,
  MSHCTX_INPROC = 0x3,
  MSHCTX_CROSSCTX = 0x4,
  MSHCTX_RESERVED1 = 0x5,
};

```

### `tagBIND_FLAGS`
```
enum tagBIND_FLAGS : __int32
{
  BIND_MAYBOTHERUSER = 0x1,
  BIND_JUSTTESTEXISTENCE = 0x2,
};

```

### `tagGLOBALOPT_EH_VALUES`
```
enum tagGLOBALOPT_EH_VALUES : __int32
{
  COMGLB_EXCEPTION_HANDLE = 0x0,
  COMGLB_EXCEPTION_DONOT_HANDLE_FATAL = 0x1,
  COMGLB_EXCEPTION_DONOT_HANDLE = 0x1,
  COMGLB_EXCEPTION_DONOT_HANDLE_ANY = 0x2,
};

```

### `tagDISCARDCACHE`
```
enum tagDISCARDCACHE : __int32
{
  DISCARDCACHE_SAVEIFDIRTY = 0x0,
  DISCARDCACHE_NOSAVE = 0x1,
};

```

### `tagPENDINGTYPE`
```
enum tagPENDINGTYPE : __int32
{
  PENDINGTYPE_TOPLEVEL = 0x1,
  PENDINGTYPE_NESTED = 0x2,
};

```

### `tagACTIVATIONTYPE`
```
enum tagACTIVATIONTYPE : __int32
{
  ACTIVATIONTYPE_UNCATEGORIZED = 0x0,
  ACTIVATIONTYPE_FROM_MONIKER = 0x1,
  ACTIVATIONTYPE_FROM_DATA = 0x2,
  ACTIVATIONTYPE_FROM_STORAGE = 0x4,
  ACTIVATIONTYPE_FROM_STREAM = 0x8,
  ACTIVATIONTYPE_FROM_FILE = 0x10,
};

```

### `tagSTATFLAG`
```
enum tagSTATFLAG : __int32
{
  STATFLAG_DEFAULT = 0x0,
  STATFLAG_NONAME = 0x1,
  STATFLAG_NOOPEN = 0x2,
};

```

### `tagCOINIT`
```
enum tagCOINIT : __int32
{
  COINIT_APARTMENTTHREADED = 0x2,
  COINIT_MULTITHREADED = 0x0,
  COINIT_DISABLE_OLE1DDE = 0x4,
  COINIT_SPEED_OVER_MEMORY = 0x8,
};

```

### `tagOLEWHICHMK`
```
enum tagOLEWHICHMK : __int32
{
  OLEWHICHMK_CONTAINER = 0x1,
  OLEWHICHMK_OBJREL = 0x2,
  OLEWHICHMK_OBJFULL = 0x3,
};

```

### `tagTYSPEC`
```
enum tagTYSPEC : __int32
{
  TYSPEC_CLSID = 0x0,
  TYSPEC_FILEEXT = 0x1,
  TYSPEC_MIMETYPE = 0x2,
  TYSPEC_FILENAME = 0x3,
  TYSPEC_PROGID = 0x4,
  TYSPEC_PACKAGENAME = 0x5,
  TYSPEC_OBJECTID = 0x6,
};

```

### `TrustLevel`
```
enum TrustLevel : __int32
{
  BaseTrust = 0x0,
  PartialTrust = 0x1,
  FullTrust = 0x2,
};

```

### `tagSTREAM_SEEK`
```
enum tagSTREAM_SEEK : __int32
{
  STREAM_SEEK_SET = 0x0,
  STREAM_SEEK_CUR = 0x1,
  STREAM_SEEK_END = 0x2,
};

```

### `tagBINDSPEED`
```
enum tagBINDSPEED : __int32
{
  BINDSPEED_INDEFINITE = 0x1,
  BINDSPEED_MODERATE = 0x2,
  BINDSPEED_IMMEDIATE = 0x3,
};

```

### `tagGLOBALOPT_UNMARSHALING_POLICY_VALUES`
```
enum tagGLOBALOPT_UNMARSHALING_POLICY_VALUES : __int32
{
  COMGLB_UNMARSHALING_POLICY_NORMAL = 0x0,
  COMGLB_UNMARSHALING_POLICY_STRONG = 0x1,
  COMGLB_UNMARSHALING_POLICY_HYBRID = 0x2,
};

```

### `tagRpcCallClientLocality`
```
enum tagRpcCallClientLocality : __int32
{
  rcclInvalid = 0x0,
  rcclLocal = 0x1,
  rcclRemote = 0x2,
  rcclClientUnknownLocality = 0x3,
};

```

### `tagURLTEMPLATE`
```
enum tagURLTEMPLATE : __int32
{
  URLTEMPLATE_CUSTOM = 0x0,
  URLTEMPLATE_PREDEFINED_MIN = 0x10000,
  URLTEMPLATE_LOW = 0x10000,
  URLTEMPLATE_MEDLOW = 0x10500,
  URLTEMPLATE_MEDIUM = 0x11000,
  URLTEMPLATE_MEDHIGH = 0x11500,
  URLTEMPLATE_HIGH = 0x12000,
  URLTEMPLATE_PREDEFINED_MAX = 0x20000,
};

```

### `tagCALLTYPE`
```
enum tagCALLTYPE : __int32
{
  CALLTYPE_TOPLEVEL = 0x1,
  CALLTYPE_NESTED = 0x2,
  CALLTYPE_ASYNC = 0x3,
  CALLTYPE_TOPLEVEL_CALLPENDING = 0x4,
  CALLTYPE_ASYNC_CALLPENDING = 0x5,
};

```

### `tagSTGTY`
```
enum tagSTGTY : __int32
{
  STGTY_STORAGE = 0x1,
  STGTY_STREAM = 0x2,
  STGTY_LOCKBYTES = 0x3,
  STGTY_PROPERTY = 0x4,
};

```

### `tagXMLEMEM_TYPE`
```
enum tagXMLEMEM_TYPE : __int32
{
  XMLELEMTYPE_ELEMENT = 0x0,
  XMLELEMTYPE_TEXT = 0x1,
  XMLELEMTYPE_COMMENT = 0x2,
  XMLELEMTYPE_DOCUMENT = 0x3,
  XMLELEMTYPE_DTD = 0x4,
  XMLELEMTYPE_PI = 0x5,
  XMLELEMTYPE_OTHER = 0x6,
};

```

### `tagApplicationType`
```
enum tagApplicationType : __int32
{
  ServerApplication = 0x0,
  LibraryApplication = 0x1,
};

```

### `tagMEMCTX`
```
enum tagMEMCTX : __int32
{
  MEMCTX_TASK = 0x1,
  MEMCTX_SHARED = 0x2,
  MEMCTX_MACSYSTEM = 0x3,
  MEMCTX_UNKNOWN = 0xFFFFFFFF,
  MEMCTX_SAME = 0xFFFFFFFE,
};

```

### `tagOLERENDER`
```
enum tagOLERENDER : __int32
{
  OLERENDER_NONE = 0x0,
  OLERENDER_DRAW = 0x1,
  OLERENDER_FORMAT = 0x2,
  OLERENDER_ASIS = 0x3,
};

```

### `tagEXTCONN`
```
enum tagEXTCONN : __int32
{
  EXTCONN_STRONG = 0x1,
  EXTCONN_WEAK = 0x2,
  EXTCONN_CALLABLE = 0x4,
};

```

### `tagSTGMOVE`
```
enum tagSTGMOVE : __int32
{
  STGMOVE_MOVE = 0x0,
  STGMOVE_COPY = 0x1,
  STGMOVE_SHALLOWCOPY = 0x2,
};

```

### `tagDCOM_CALL_STATE`
```
enum tagDCOM_CALL_STATE : __int32
{
  DCOM_NONE = 0x0,
  DCOM_CALL_COMPLETE = 0x1,
  DCOM_CALL_CANCELED = 0x2,
};

```

### `tagOLEUPDATE`
```
enum tagOLEUPDATE : __int32
{
  OLEUPDATE_ALWAYS = 0x1,
  OLEUPDATE_ONCALL = 0x3,
};

```

### `tagOLECLOSE`
```
enum tagOLECLOSE : __int32
{
  OLECLOSE_SAVEIFDIRTY = 0x0,
  OLECLOSE_NOSAVE = 0x1,
  OLECLOSE_PROMPTSAVE = 0x2,
};

```

### `tagDATADIR`
```
enum tagDATADIR : __int32
{
  DATADIR_GET = 0x1,
  DATADIR_SET = 0x2,
};

```

### `tagUSERCLASSTYPE`
```
enum tagUSERCLASSTYPE : __int32
{
  USERCLASSTYPE_FULL = 0x1,
  USERCLASSTYPE_SHORT = 0x2,
  USERCLASSTYPE_APPNAME = 0x3,
};

```

### `tagOLELINKBIND`
```
enum tagOLELINKBIND : __int32
{
  OLELINKBIND_EVENIFCLASSDIFF = 0x1,
};

```

### `tagSTDMSHLFLAGS`
```
enum tagSTDMSHLFLAGS : __int32
{
  SMEXF_SERVER = 0x1,
  SMEXF_HANDLER = 0x2,
};

```

### `tagOLEVERBATTRIB`
```
enum tagOLEVERBATTRIB : __int32
{
  OLEVERBATTRIB_NEVERDIRTIES = 0x1,
  OLEVERBATTRIB_ONCONTAINERMENU = 0x2,
};

```

### `tagExtentMode`
```
enum tagExtentMode : __int32
{
  DVEXTENT_CONTENT = 0x0,
  DVEXTENT_INTEGRAL = 0x1,
};

```

### `Tessellator::UploadMode`
```
typedef Core::FileBufferingMode Tessellator::UploadMode;

```

### `TextureAtlasStatus`
```
enum TextureAtlasStatus : __int32
{
  MipLevelDropped = 0x0,
  ResolutionDropped = 0x1,
};

```

### `TextureHotReloaderMode`
```
enum TextureHotReloaderMode : __int32
{
  RELOAD_NONE = 0x0,
  RELOAD_ALL = 0x1,
};

```

### `typeid_t<CommandRegistry>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<CommandRegistry>::NewIDType;

```

### `typeid_t<ScriptBinderComponent>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<ScriptBinderComponent>::NewIDType;

```

### `typeid_t<IAppConfigData>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<IAppConfigData>::NewIDType;

```

### `TransferProtoID`
```
typedef Direction::Type TransferProtoID;

```

### `TextType`
```
enum TextType : __int32
{
  ExtendedASCII = 0x0,
  IdentifierChars = 0x1,
  NumberChars = 0x2,
};

```

### `TreatmentPackDownloadMonitor::FetchState`
```
typedef FlightingService::FetchState TreatmentPackDownloadMonitor::FetchState;

```

### `ToneMapTechnique`
```
typedef Rotation ToneMapTechnique;

```

### `Typeface`
```
typedef DimensionId Typeface;

```

### `typeid_t<ContentLog>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<ContentLog>::NewIDType;

```

### `TypeInContainer`
```
typedef Rotation TypeInContainer;

```

### `Trade2ScreenController::LeftTabIndex`
```
typedef CraftingType Trade2ScreenController::LeftTabIndex;

```

### `Trade2ContainerManagerModel::Slot`
```
typedef VRControllerType Trade2ContainerManagerModel::Slot;

```

### `TermEvaluationType`
```
enum TermEvaluationType : __int32
{
  Constant = 0x0,
  ProductOfVariablesAndFactor = 0x1,
  ProductOfVariablesFactorAndLambda = 0x2,
  Lambda = 0x3,
};

```

### `ThrownTrident::Data`
```
typedef AbstractArrow::Data ThrownTrident::Data;

```

### `TextureSetHelpers::TextureSetDefinitionLoader::LoadImageLayerResult`
```
typedef BedSleepingResult TextureSetHelpers::TextureSetDefinitionLoader::LoadImageLayerResult;

```

### `TextEditContext::CaretUpdate`
```
typedef Frustum::FrustumSide TextEditContext::CaretUpdate;

```

### `TextEditContext::TextEditAction`
```
typedef IMinecraftEventing::ShareMode TextEditContext::TextEditAction;

```

### `typeid_t<IDefinitionInstance>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<IDefinitionInstance>::NewIDType;

```

### `TypeExecutingEvent`
```
typedef ActorEvent TypeExecutingEvent;

```

### `TraderMaterialTypeFunction::VillagerBiome`
```
typedef SignBlockActor::SignType TraderMaterialTypeFunction::VillagerBiome;

```

### `typeid_t<EntityGoalFactory>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<EntityGoalFactory>::NewIDType;

```

### `typeid_t<ContextAccessor>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<ContextAccessor>::NewIDType;

```

### `TagCommand::Action`
```
typedef BossEventUpdateType TagCommand::Action;

```

### `TeleportCommand::FacingResult`
```
typedef Bedrock::Threading::AsyncStatus TeleportCommand::FacingResult;

```

### `TeleportCommand::TeleportAnalysis`
```
enum TeleportCommand::TeleportAnalysis : __int32
{
  WontClip = 0x0,
  WillClip = 0x1,
  ChunksUnloaded = 0x2,
};

```

### `TestForBlocksCommand::Mode`
```
typedef ItemPlaceType TestForBlocksCommand::Mode;

```

### `TickingAreaCommand::Mode`
```
typedef BossEventUpdateType TickingAreaCommand::Mode;

```

### `TickingAreaCommand::AddAreaType`
```
typedef AreaType TickingAreaCommand::AddAreaType;

```

### `TickingAreaCommand::TargetDimensions`
```
enum TickingAreaCommand::TargetDimensions : __int32
{
  CurrentDimension = 0x0,
  AllDimensions = 0x1,
};

```

### `TimeCommand::Mode`
```
typedef PermissionCommand::Action TimeCommand::Mode;

```

### `TimeCommand::Query`
```
enum TimeCommand::Query : __int32
{
  DayTime = 0x0,
  GameTime = 0x1,
  Day = 0x2,
};

```

### `TimeCommand::TimeSpec`
```
typedef TimeCommand::Query TimeCommand::TimeSpec;

```

### `TitleCommand::Mode`
```
typedef LabTablePacket::Type TitleCommand::Mode;

```

### `TitleRawCommand::Mode`
```
typedef LabTablePacket::Type TitleRawCommand::Mode;

```

### `typeid_t<Goal>::NewIDType`
```
typedef typeid_t<IScreenCapabilities>::NewIDType typeid_t<Goal>::NewIDType;

```

### `TradeContainerSlot`
```
enum TradeContainerSlot : __int32
{
  ITEM_A_SLOT = 0x0,
  ITEM_B_SLOT = 0x1,
  SELL_SLOT = 0x2,
  MAX_SLOTS = 0x3,
};

```

### `TemperatureCategory`
```
enum TemperatureCategory : __int32
{
  Frozen = 0x0,
};

```

### `TrapDoorBlock::TrapDoorDir`
```
enum TrapDoorBlock::TrapDoorDir : __int8
{
  DIR_EAST = 0x0,
  DIR_WEST = 0x1,
  DIR_SOUTH = 0x2,
  DIR_NORTH = 0x3,
};

```

### `tagCONDITION_OPERATION`
```
enum tagCONDITION_OPERATION : __int32
{
  COP_IMPLICIT = 0x0,
  COP_EQUAL = 0x1,
  COP_NOTEQUAL = 0x2,
  COP_LESSTHAN = 0x3,
  COP_GREATERTHAN = 0x4,
  COP_LESSTHANOREQUAL = 0x5,
  COP_GREATERTHANOREQUAL = 0x6,
  COP_VALUE_STARTSWITH = 0x7,
  COP_VALUE_ENDSWITH = 0x8,
  COP_VALUE_CONTAINS = 0x9,
  COP_VALUE_NOTCONTAINS = 0xA,
  COP_DOSWILDCARDS = 0xB,
  COP_WORD_EQUAL = 0xC,
  COP_WORD_STARTSWITH = 0xD,
  COP_APPLICATION_SPECIFIC = 0xE,
};

```

### `tagCONDITION_TYPE`
```
enum tagCONDITION_TYPE : __int32
{
  CT_AND_CONDITION = 0x0,
  CT_OR_CONDITION = 0x1,
  CT_NOT_CONDITION = 0x2,
  CT_LEAF_CONDITION = 0x3,
};

```

### `tagMENUPOPUPSELECT`
```
enum tagMENUPOPUPSELECT : __int32
{
  MPOS_EXECUTE = 0x0,
  MPOS_FULLCANCEL = 0x1,
  MPOS_CANCELLEVEL = 0x2,
  MPOS_SELECTLEFT = 0x3,
  MPOS_SELECTRIGHT = 0x4,
  MPOS_CHILDTRACKING = 0x5,
};

```

### `tagBANDSITECID`
```
enum tagBANDSITECID : __int32
{
  BSID_BANDADDED = 0x0,
  BSID_BANDREMOVED = 0x1,
};

```

### `TouchTurnState`
```
enum TouchTurnState : __int32
{
  Inactive = 0x0,
  Deciding = 0x1,
  Turn = 0x2,
  Hold = 0x3,
  Tap = 0x4,
  PreDeciding = 0x5,
};

```

### `TouchControlFlags`
```
enum TouchControlFlags : __int32
{
  PermanentlyHandled = 0x1,
  Captured = 0x2,
  StartedInactive = 0x4,
};

```

### `TeamManagerOperations`
```
enum TeamManagerOperations : __int32
{
  ID_RUN_UpdateListsToNoTeam = 0x0,
  ID_RUN_UpdateTeamsRequestedToAny = 0x1,
  ID_RUN_JoinAnyTeam = 0x2,
  ID_RUN_JoinRequestedTeam = 0x3,
  ID_RUN_UpdateTeamsRequestedToNoneAndAddTeam = 0x4,
  ID_RUN_RemoveFromTeamsRequestedAndAddTeam = 0x5,
  ID_RUN_AddToRequestedTeams = 0x6,
  ID_RUN_LeaveTeam = 0x7,
  ID_RUN_SetMemberLimit = 0x8,
  ID_RUN_SetJoinPermissions = 0x9,
  ID_RUN_SetBalanceTeams = 0xA,
  ID_RUN_SetBalanceTeamsInitial = 0xB,
  ID_RUN_SerializeWorld = 0xC,
};

```

### `TeamBalancerOperations`
```
enum TeamBalancerOperations : __int32
{
  ID_STATUS_UPDATE_TO_NEW_HOST = 0x0,
  ID_CANCEL_TEAM_REQUEST = 0x1,
  ID_REQUEST_ANY_TEAM = 0x2,
  ID_REQUEST_SPECIFIC_TEAM = 0x3,
};

```

### `TT_SbitTableType_`
```
enum TT_SbitTableType_ : __int32
{
  TT_SBIT_TABLE_TYPE_NONE = 0x0,
  TT_SBIT_TABLE_TYPE_EBLC = 0x1,
  TT_SBIT_TABLE_TYPE_CBLC = 0x2,
  TT_SBIT_TABLE_TYPE_SBIX = 0x3,
  TT_SBIT_TABLE_TYPE_MAX = 0x4,
};

```

### `T1_Operator_`
```
enum T1_Operator_ : __int32
{
  op_none = 0x0,
  op_endchar = 0x1,
  op_hsbw = 0x2,
  op_seac = 0x3,
  op_sbw = 0x4,
  op_closepath = 0x5,
  op_hlineto = 0x6,
  op_hmoveto = 0x7,
  op_hvcurveto = 0x8,
  op_rlineto = 0x9,
  op_rmoveto = 0xA,
  op_rrcurveto = 0xB,
  op_vhcurveto = 0xC,
  op_vlineto = 0xD,
  op_vmoveto = 0xE,
  op_dotsection = 0xF,
  op_hstem = 0x10,
  op_hstem3 = 0x11,
  op_vstem = 0x12,
  op_vstem3 = 0x13,
  op_div = 0x14,
  op_callothersubr = 0x15,
  op_callsubr = 0x16,
  op_pop = 0x17,
  op_return = 0x18,
  op_setcurrentpoint = 0x19,
  op_unknown15 = 0x1A,
  op_max = 0x1B,
};

```

### `T1_EncodingType_`
```
enum T1_EncodingType_ : __int32
{
  T1_ENCODING_TYPE_NONE = 0x0,
  T1_ENCODING_TYPE_ARRAY = 0x1,
  T1_ENCODING_TYPE_STANDARD = 0x2,
  T1_ENCODING_TYPE_ISOLATIN1 = 0x3,
  T1_ENCODING_TYPE_EXPERT = 0x4,
};

```

### `TT_CodeRange_Tag_`
```
enum TT_CodeRange_Tag_ : __int32
{
  tt_coderange_none = 0x0,
  tt_coderange_font = 0x1,
  tt_coderange_cvt = 0x2,
  tt_coderange_glyph = 0x3,
};

```

### `T42_Load_Status_`
```
enum T42_Load_Status_ : __int32
{
  BEFORE_START = 0x0,
  BEFORE_TABLE_DIR = 0x1,
  OTHER_TABLES = 0x2,
};

```

### `ToggleComponent::_updateControlVisibility::__l2::ToggleControlState`
```
enum ToggleComponent::_updateControlVisibility::__l2::ToggleControlState : __int32
{
  Unchecked = 0x1,
  Checked = 0x2,
  Hover = 0x4,
  Locked = 0x8,
  UncheckedHover = 0x5,
  UncheckedLocked = 0x9,
  UncheckedHoverLocked = 0xD,
  CheckedHover = 0x6,
  CheckedLocked = 0xA,
  CheckedHoverLocked = 0xE,
};

```

### `TextureSetHelpers::TextureSetDefinitionLoader::_loadImageLayers::__l17::ColorChannels`
```
typedef glTF::Texture::Format TextureSetHelpers::TextureSetDefinitionLoader::_loadImageLayers::__l17::ColorChannels;

```

### `Token::tokenize::__l2::<unnamed_type_state>`
```
enum Token::tokenize::__l2::<unnamed_type_state> : __int32
{
  S_NONE = 0x0,
  S_TOKEN = 0x1,
  S_QUOTES = 0x2,
};

```

