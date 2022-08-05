# J
### `JigsawJointType`
Name | Value
-|-
ROLLABLE | `0`
ALIGNED | `1`


### `JournaledFile::Progression`
Name | Value
-|-
NeverWritten | `0`
WriteFailed | `1`
WriteSuccess | `2`


### `Json::Reader::TokenType`
Name | Value
-|-
tokenEndOfStream | `0`
tokenObjectBegin | `1`
tokenObjectEnd | `2`
tokenArrayBegin | `3`
tokenArrayEnd | `4`
tokenString | `5`
tokenNumber | `6`
tokenTrue | `7`
tokenFalse | `8`
tokenNull | `9`
tokenArraySeparator | `10`
tokenMemberSeparator | `11`
tokenComment | `12`
tokenError | `13`


### `JOB_OBJECT_NET_RATE_CONTROL_FLAGS`
```
enum JOB_OBJECT_NET_RATE_CONTROL_FLAGS : __int32
{
  JOB_OBJECT_NET_RATE_CONTROL_ENABLE = 0x1,
  JOB_OBJECT_NET_RATE_CONTROL_MAX_BANDWIDTH = 0x2,
  JOB_OBJECT_NET_RATE_CONTROL_DSCP_TAG = 0x4,
  JOB_OBJECT_NET_RATE_CONTROL_VALID_FLAGS = 0x7,
};

```

### `JOB_OBJECT_IO_RATE_CONTROL_FLAGS`
```
enum JOB_OBJECT_IO_RATE_CONTROL_FLAGS : __int32
{
  JOB_OBJECT_IO_RATE_CONTROL_ENABLE = 0x1,
  JOB_OBJECT_IO_RATE_CONTROL_STANDALONE_VOLUME = 0x2,
  JOB_OBJECT_IO_RATE_CONTROL_VALID_FLAGS = 0x3,
};

```

### `Json::ValueType`
```
enum Json::ValueType : __int32
{
  nullValue = 0x0,
  intValue = 0x1,
  uintValue = 0x2,
  realValue = 0x3,
  stringValue = 0x4,
  booleanValue = 0x5,
  arrayValue = 0x6,
  objectValue = 0x7,
};

```

### `Json::CommentPlacement`
```
enum Json::CommentPlacement : __int32
{
  commentBefore = 0x0,
  commentAfterOnSameLine = 0x1,
  commentAfter = 0x2,
  numberOfCommentPlacement = 0x3,
};

```

### `JOBOBJECT_IO_ATTRIBUTION_CONTROL_FLAGS`
```
enum JOBOBJECT_IO_ATTRIBUTION_CONTROL_FLAGS : __int32
{
  JOBOBJECT_IO_ATTRIBUTION_CONTROL_ENABLE = 0x1,
  JOBOBJECT_IO_ATTRIBUTION_CONTROL_DISABLE = 0x2,
  JOBOBJECT_IO_ATTRIBUTION_CONTROL_VALID_FLAGS = 0x3,
};

```

### `Json::PathArgument::Kind`
```
enum Json::PathArgument::Kind : __int32
{
  kindNone = 0x0,
  kindIndex = 0x1,
  kindKey = 0x2,
};

```

### `Json::Value::CZString::DuplicationPolicy`
```
enum Json::Value::CZString::DuplicationPolicy : __int32
{
  noDuplication = 0x0,
  duplicate = 0x1,
  duplicateOnCopy = 0x2,
};

```

### `JoincodeEntryScreenController::ActiveScreen`
```
typedef Rotation JoincodeEntryScreenController::ActiveScreen;

```

### `JumpType`
```
typedef ActorEvent JumpType;

```

### `J_DCT_METHOD`
```
enum J_DCT_METHOD : __int32
{
  JDCT_ISLOW = 0x0,
  JDCT_IFAST = 0x1,
  JDCT_FLOAT = 0x2,
};

```

### `J_COLOR_SPACE`
```
enum J_COLOR_SPACE : __int32
{
  JCS_UNKNOWN = 0x0,
  JCS_GRAYSCALE = 0x1,
  JCS_RGB = 0x2,
  JCS_YCbCr = 0x3,
  JCS_CMYK = 0x4,
  JCS_YCCK = 0x5,
  JCS_BG_RGB = 0x6,
  JCS_BG_YCC = 0x7,
};

```

### `J_COLOR_TRANSFORM`
```
enum J_COLOR_TRANSFORM : __int32
{
  JCT_NONE = 0x0,
  JCT_SUBTRACT_GREEN = 0x1,
};

```

### `Json::<unnamed_enum_uintToStringBufferSize>`
```
enum Json::<unnamed_enum_uintToStringBufferSize> : __int32
{
  uintToStringBufferSize = 0x19,
};

```

### `J_MESSAGE_CODE`
```
enum J_MESSAGE_CODE : __int32
{
  JMSG_NOMESSAGE = 0x0,
  JERR_BAD_ALIGN_TYPE = 0x1,
  JERR_BAD_ALLOC_CHUNK = 0x2,
  JERR_BAD_BUFFER_MODE = 0x3,
  JERR_BAD_COMPONENT_ID = 0x4,
  JERR_BAD_CROP_SPEC = 0x5,
  JERR_BAD_DCT_COEF = 0x6,
  JERR_BAD_DCTSIZE = 0x7,
  JERR_BAD_DROP_SAMPLING = 0x8,
  JERR_BAD_HUFF_TABLE = 0x9,
  JERR_BAD_IN_COLORSPACE = 0xA,
  JERR_BAD_J_COLORSPACE = 0xB,
  JERR_BAD_LENGTH = 0xC,
  JERR_BAD_LIB_VERSION = 0xD,
  JERR_BAD_MCU_SIZE = 0xE,
  JERR_BAD_POOL_ID = 0xF,
  JERR_BAD_PRECISION = 0x10,
  JERR_BAD_PROGRESSION = 0x11,
  JERR_BAD_PROG_SCRIPT = 0x12,
  JERR_BAD_SAMPLING = 0x13,
  JERR_BAD_SCAN_SCRIPT = 0x14,
  JERR_BAD_STATE = 0x15,
  JERR_BAD_STRUCT_SIZE = 0x16,
  JERR_BAD_VIRTUAL_ACCESS = 0x17,
  JERR_BUFFER_SIZE = 0x18,
  JERR_CANT_SUSPEND = 0x19,
  JERR_CCIR601_NOTIMPL = 0x1A,
  JERR_COMPONENT_COUNT = 0x1B,
  JERR_CONVERSION_NOTIMPL = 0x1C,
  JERR_DAC_INDEX = 0x1D,
  JERR_DAC_VALUE = 0x1E,
  JERR_DHT_INDEX = 0x1F,
  JERR_DQT_INDEX = 0x20,
  JERR_EMPTY_IMAGE = 0x21,
  JERR_EMS_READ = 0x22,
  JERR_EMS_WRITE = 0x23,
  JERR_EOI_EXPECTED = 0x24,
  JERR_FILE_READ = 0x25,
  JERR_FILE_WRITE = 0x26,
  JERR_FRACT_SAMPLE_NOTIMPL = 0x27,
  JERR_HUFF_CLEN_OVERFLOW = 0x28,
  JERR_HUFF_MISSING_CODE = 0x29,
  JERR_IMAGE_TOO_BIG = 0x2A,
  JERR_INPUT_EMPTY = 0x2B,
  JERR_INPUT_EOF = 0x2C,
  JERR_MISMATCHED_QUANT_TABLE = 0x2D,
  JERR_MISSING_DATA = 0x2E,
  JERR_MODE_CHANGE = 0x2F,
  JERR_NOTIMPL = 0x30,
  JERR_NOT_COMPILED = 0x31,
  JERR_NO_ARITH_TABLE = 0x32,
  JERR_NO_BACKING_STORE = 0x33,
  JERR_NO_HUFF_TABLE = 0x34,
  JERR_NO_IMAGE = 0x35,
  JERR_NO_QUANT_TABLE = 0x36,
  JERR_NO_SOI = 0x37,
  JERR_OUT_OF_MEMORY = 0x38,
  JERR_QUANT_COMPONENTS = 0x39,
  JERR_QUANT_FEW_COLORS = 0x3A,
  JERR_QUANT_MANY_COLORS = 0x3B,
  JERR_SOF_BEFORE = 0x3C,
  JERR_SOF_DUPLICATE = 0x3D,
  JERR_SOF_NO_SOS = 0x3E,
  JERR_SOF_UNSUPPORTED = 0x3F,
  JERR_SOI_DUPLICATE = 0x40,
  JERR_TFILE_CREATE = 0x41,
  JERR_TFILE_READ = 0x42,
  JERR_TFILE_SEEK = 0x43,
  JERR_TFILE_WRITE = 0x44,
  JERR_TOO_LITTLE_DATA = 0x45,
  JERR_UNKNOWN_MARKER = 0x46,
  JERR_VIRTUAL_BUG = 0x47,
  JERR_WIDTH_OVERFLOW = 0x48,
  JERR_XMS_READ = 0x49,
  JERR_XMS_WRITE = 0x4A,
  JMSG_COPYRIGHT = 0x4B,
  JMSG_VERSION = 0x4C,
  JTRC_16BIT_TABLES = 0x4D,
  JTRC_ADOBE = 0x4E,
  JTRC_APP0 = 0x4F,
  JTRC_APP14 = 0x50,
  JTRC_DAC = 0x51,
  JTRC_DHT = 0x52,
  JTRC_DQT = 0x53,
  JTRC_DRI = 0x54,
  JTRC_EMS_CLOSE = 0x55,
  JTRC_EMS_OPEN = 0x56,
  JTRC_EOI = 0x57,
  JTRC_HUFFBITS = 0x58,
  JTRC_JFIF = 0x59,
  JTRC_JFIF_BADTHUMBNAILSIZE = 0x5A,
  JTRC_JFIF_EXTENSION = 0x5B,
  JTRC_JFIF_THUMBNAIL = 0x5C,
  JTRC_MISC_MARKER = 0x5D,
  JTRC_PARMLESS_MARKER = 0x5E,
  JTRC_QUANTVALS = 0x5F,
  JTRC_QUANT_3_NCOLORS = 0x60,
  JTRC_QUANT_NCOLORS = 0x61,
  JTRC_QUANT_SELECTED = 0x62,
  JTRC_RECOVERY_ACTION = 0x63,
  JTRC_RST = 0x64,
  JTRC_SMOOTH_NOTIMPL = 0x65,
  JTRC_SOF = 0x66,
  JTRC_SOF_COMPONENT = 0x67,
  JTRC_SOI = 0x68,
  JTRC_SOS = 0x69,
  JTRC_SOS_COMPONENT = 0x6A,
  JTRC_SOS_PARAMS = 0x6B,
  JTRC_TFILE_CLOSE = 0x6C,
  JTRC_TFILE_OPEN = 0x6D,
  JTRC_THUMB_JPEG = 0x6E,
  JTRC_THUMB_PALETTE = 0x6F,
  JTRC_THUMB_RGB = 0x70,
  JTRC_UNKNOWN_IDS = 0x71,
  JTRC_XMS_CLOSE = 0x72,
  JTRC_XMS_OPEN = 0x73,
  JWRN_ADOBE_XFORM = 0x74,
  JWRN_ARITH_BAD_CODE = 0x75,
  JWRN_BOGUS_PROGRESSION = 0x76,
  JWRN_EXTRANEOUS_DATA = 0x77,
  JWRN_HIT_MARKER = 0x78,
  JWRN_HUFF_BAD_CODE = 0x79,
  JWRN_JFIF_MAJOR = 0x7A,
  JWRN_JPEG_EOF = 0x7B,
  JWRN_MUST_RESYNC = 0x7C,
  JWRN_NOT_SEQUENTIAL = 0x7D,
  JWRN_TOO_MUCH_DATA = 0x7E,
  JMSG_LASTMSGCODE = 0x7F,
};

```

### `J_BUF_MODE`
```
enum J_BUF_MODE : __int32
{
  JBUF_PASS_THRU = 0x0,
  JBUF_SAVE_SOURCE = 0x1,
  JBUF_CRANK_DEST = 0x2,
  JBUF_SAVE_AND_PASS = 0x3,
};

```

### `JPEG_MARKER`
```
enum JPEG_MARKER : __int32
{
  M_SOF0 = 0xC0,
  M_SOF1 = 0xC1,
  M_SOF2 = 0xC2,
  M_SOF3 = 0xC3,
  M_SOF5 = 0xC5,
  M_SOF6 = 0xC6,
  M_SOF7 = 0xC7,
  M_JPG = 0xC8,
  M_SOF9 = 0xC9,
  M_SOF10 = 0xCA,
  M_SOF11 = 0xCB,
  M_SOF13 = 0xCD,
  M_SOF14 = 0xCE,
  M_SOF15 = 0xCF,
  M_DHT = 0xC4,
  M_DAC = 0xCC,
  M_RST0 = 0xD0,
  M_RST1 = 0xD1,
  M_RST2 = 0xD2,
  M_RST3 = 0xD3,
  M_RST4 = 0xD4,
  M_RST5 = 0xD5,
  M_RST6 = 0xD6,
  M_RST7 = 0xD7,
  M_SOI = 0xD8,
  M_EOI = 0xD9,
  M_SOS = 0xDA,
  M_DQT = 0xDB,
  M_DNL = 0xDC,
  M_DRI = 0xDD,
  M_DHP = 0xDE,
  M_EXP = 0xDF,
  M_APP0 = 0xE0,
  M_APP1 = 0xE1,
  M_APP2 = 0xE2,
  M_APP3 = 0xE3,
  M_APP4 = 0xE4,
  M_APP5 = 0xE5,
  M_APP6 = 0xE6,
  M_APP7 = 0xE7,
  M_APP8 = 0xE8,
  M_APP9 = 0xE9,
  M_APP10 = 0xEA,
  M_APP11 = 0xEB,
  M_APP12 = 0xEC,
  M_APP13 = 0xED,
  M_APP14 = 0xEE,
  M_APP15 = 0xEF,
  M_JPG0 = 0xF0,
  M_JPG8 = 0xF8,
  M_JPG13 = 0xFD,
  M_COM = 0xFE,
  M_TEM = 0x1,
  M_ERROR = 0x100,
};

```

### `J_DITHER_MODE`
```
enum J_DITHER_MODE : __int32
{
  JDITHER_NONE = 0x0,
  JDITHER_ORDERED = 0x1,
  JDITHER_FS = 0x2,
};

```

