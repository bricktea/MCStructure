# F
### `FileReadResult`
Name | Value
-|-
SUCCESS | `0`
FAILED_TO_OPEN_FILE | `1`
MALFORMED | `2`


### `FilterGroup::CollectionType`
Name | Value
-|-
AND | `0`
OR | `1`
NOT | `2`


### `flag_type`
Name | Value
-|-


### `FilterSubject`
Name | Value
-|-
Self | `0`
Other | `1`
Player | `2`
Target | `3`
Parent | `4`
Baby | `5`
Block | `6`
COUNT_1 | `7`


### `Facing::Name`
Name | Value
-|-
DOWN | `0`
UP | `1`
NORTH_0 | `2`
SOUTH_0 | `3`
WEST_0 | `4`
EAST_0 | `5`
MAX | `6`
NOT_DEFINED | `6`
NUM_CULLING_IDS | `7`


### `FeatureOptionID`
Name | Value
-|-
None_25 | `0`
NetworkLogAllPackets | `1`
Scoreboards | `2`
Functions | `3`
UIAsyncLoadingAndAnimations | `4`
Allow3rdPartyServerSplitscreen | `5`
ExperimentalGameplayInAllWorlds | `6`
Hummingbird | `7`
HummingbirdDebugging | `8`
UIRefresh | `9`
Scripting_0 | `10`
Realms_1 | `11`
RealmsContent | `12`
EnableLoadTimer | `13`
ExternalWorldTemplatePackSources | `14`
Win10Subscriptions | `15`
PlayerRenaming | `16`
PersonaBackend | `17`
PersonaSkin | `18`
PlayFabInsightsTelemetry | `19`
PersonaEnabled | `20`
PersonaServiceEnabled | `21`
PersonaTestCatalog | `22`
PersonaCape | `23`
PersonaEmotes | `24`
StorefrontTestLayouts | `25`
RenderDragonRenderPath | `26`
BaseGameVersioniningTestPacks | `27`
LevelStoragePerfLog | `28`
TrueTypeFontLoading | `29`
PauseMenuOnFocusLost | `30`
Count_14 | `31`


### `FunctionState`
Name | Value
-|-
Uninitialized_0 | `1`
EngineVersionNotInitialized | `2`
Valid_1 | `3`


### `FileArchiver::Outcome`
Name | Value
-|-
Success_11 | `0`
FailureUnknown | `1`
FailureNoFile | `2`
FailureZipError | `3`
FailurePremiumContent | `4`
FailureEditionMismatch | `5`


### `FocusImpact`
Name | Value
-|-
Neutral | `0`
ActivateFocus | `1`
DeactivateFocus | `2`


### `FilterOperator`
Name | Value
-|-
Equal | `0`
NotEqual | `1`
GreaterThan_0 | `2`
LessThan_0 | `3`
GreaterThanOrEqual | `4`
LessThanOrEqual | `5`


### `FilterParamType`
Name | Value
-|-
Bool_1 | `0`
Int_5 | `1`
Float_6 | `2`
String_4 | `3`


### `FishPattern`
Name | Value
-|-
PATTERN_1 | `0`
PATTERN_2 | `1`
PATTERN_3 | `2`
PATTERN_4 | `3`
PATTERN_5 | `4`
PATTERN_6 | `5`
COUNT_8 | `6`


### `FurnaceContainerData`
Name | Value
-|-
SetTickCount | `0`
SetLitTime | `1`
SetLitDuration | `2`
SetStoredXP | `3`


### `FilterResult`
Name | Value
-|-
ShowPrioritized | `0`
Show | `1`
Disable | `2`
Hide | `3`


### `FilterParamRequirement`
Name | Value
-|-
Required | `0`
Optional | `1`


### `FilterParamOption`
Name | Value
-|-
None_42 | `0`
EmptyDefaultString | `1`


### `FertilizerType`
Name | Value
-|-
Bonemeal | `0`
Rapid | `1`


### `FireworkChargeItem::Shape`
Name | Value
-|-
SHAPE_NONE | `0`
SHAPE_LARGE_BALL | `1`
SHAPE_STAR | `2`
SHAPE_HEAD_CREEPER | `3`
SHAPE_BURST | `4`
SHAPE_COUNT | `5`


### `FlowerType`
Name | Value
-|-
Poppy_0 | `0`
Orchid | `1`
Allium_0 | `2`
Houstonia | `3`
TulipRed | `4`
TulipOrange | `5`
TulipWhite | `6`
TulipPink | `7`
Oxeye | `8`
Cornflower_0 | `9`
LilyOfTheValley_0 | `10`
_count_37 | `11`


### `FileArchiver::ExportType`
Name | Value
-|-
Level_0 | `0`
Template | `1`


### `FileType`
Name | Value
-|-
Invalid_28 | `0`
Zip_0 | `1`
EncryptedZip | `2`
Other_2 | `3`


### `FilePickerSettings::PickerType`
Name | Value
-|-
Invalid_26 | `0`
Open_1 | `1`
Save_1 | `2`


### `Facing::Rotation`
Name | Value
-|-
NONE | `0`
CCW | `1`
OPP | `2`
CW | `3`


### `Flip`
Name | Value
-|-
None_50 | `0`
RotateCW | `1`
RotateCCW | `2`
Rotate180_0 | `3`
MirrorX | `4`
DontRotate | `5`


### `FlowerBlock::Type`
Name | Value
-|-
Yellow_3 | `0`
Red_5 | `1`
WitherRose_0 | `2`


### `FullscreenMode`
Name | Value
-|-
Windowed | `0`
Fullscreen | `1`


### `FileSystemMode`
Name | Value
-|-
ReadWrite_0 | `0`
ReadOnly_0 | `1`


### `FileArchiver::State`
Name | Value
-|-
Idle_0 | `0`
Importing | `1`
Exporting_0 | `2`


### `FillCommand::FillMode`
Name | Value
-|-
Replace_1 | `0`
Destroy_0 | `1`
Hollow_0 | `2`
Outline | `3`
Keep | `4`


### `FallingBlock::State`
```
enum FallingBlock::State : __int32
{
  Falling = 0x0,
  WaitRemoval = 0x1,
};

```

### `FoodItemComponent::OnUseAction`
```
enum FoodItemComponent::OnUseAction : __int32
{
  NONE_11 = 0xFFFFFFFF,
  CHORUS_TELEPORT = 0x0,
  SUSPICIOUS_STEW_EFFECT = 0x1,
};

```

### `FreezeOnHitSubcomponent::Shape`
```
enum FreezeOnHitSubcomponent::Shape : __int8
{
  Cube = 0x0,
  Sphere = 0x1,
};

```

### `FurnaceBlockActor::$78D9F25919EA3E1AC07246132E3A6E19`
```
enum FurnaceBlockActor::$78D9F25919EA3E1AC07246132E3A6E19 : __int32
{
  SLOT_INGREDIENT_0 = 0x0,
  SLOT_FUEL_0 = 0x1,
  SLOT_RESULT = 0x2,
  NUM_ITEMS = 0x3,
};

```

