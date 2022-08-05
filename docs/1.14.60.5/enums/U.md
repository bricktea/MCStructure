# U
### `UpnpState`
Name | Value
-|-
Startup | `0`
UpnpRequested | `1`
UpnpStarted | `2`
UpnpSucceeded | `3`
UpnpFailed | `4`
Invalid_13 | `5`


### `UIPackErrorType`
Name | Value
-|-
None_35 | `0`
InvalidChildNames | `1`
ParseError_0 | `2`
MissingControl | `3`
MissingControlTarget | `4`
MissingArrayName | `5`
MissingCondition | `6`
MissingValue | `7`
MissingOperation | `8`
InvalidOperationName | `9`


### `Util::NumberConversionResult`
Name | Value
-|-
Succeed | `0`
Invalid_20 | `1`
TooSmall | `2`
TooLarge | `3`
Count_22 | `4`


### `Util::removeAllColorCodes::RemoveAllColorCodesState`
Name | Value
-|-
Output | `0`
SawCodeByte1 | `1`
SawCodeByte2 | `2`


### `UseAnimation`
Name | Value
-|-
None_10 | `0`
Eat | `1`
Drink | `2`
Block_0 | `3`
Bow | `4`
Camera_0 | `5`
Spear | `6`
GlowStick | `7`
Sparkler | `8`
Crossbow | `9`


### `UIScalingRules`
Name | Value
-|-
Desktop | `0`
PocketApple | `1`
PocketAndroid | `2`
PocketWindows | `3`
Console | `4`
HandheldConsole | `5`


### `UploadState`
```
enum UploadState : __int32
{
  Uninitialized_1 = 0x0,
  Initializing = 0x1,
  Progress = 0x2,
  Exporting = 0x3,
  Done_0 = 0x4,
  Failed_6 = 0x5,
};

```

### `UploadError`
```
enum UploadError : __int32
{
  None_36 = 0x0,
  ForbiddenContent = 0x1,
  Unknown_35 = 0x2,
};

```

### `UIProfile`
```
enum UIProfile : __int32
{
  Classic_0 = 0x0,
  Pocket_0 = 0x1,
  Count_30 = 0x2,
};

```

