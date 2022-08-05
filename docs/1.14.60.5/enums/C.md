# C
### `ConnectionDefinition::PortBusyFallbackPolicy`
Name | Value
-|-
UseRandom | `0`
Fail | `1`


### `CommandPermissionLevel`
Name | Value
-|-
Any | `0`
GameMasters | `1`
Admin | `2`
Host | `3`
Owner | `4`
Internal | `5`


### `CommandParameterDataType`
Name | Value
-|-
Basic | `0`
Enum | `1`
SoftEnum | `2`
Postfix | `3`


### `CommandVisibilityFlag`
Name | Value
-|-
Visible | `0`
HiddenFromCommandBlockOrigin | `2`
HiddenFromPlayerOrigin | `4`
Hidden | `6`


### `com::mojang::clacks::protocol::SaveState`
Name | Value
-|-
IDLE | `0`
SAVING | `1`
COMPLETE | `2`
SaveState_INT_MAX_SENTINEL_DO_NOT_USE_ | `2147483647`
SaveState_INT_MIN_SENTINEL_DO_NOT_USE_ | `18446744071562067968`


### `com::mojang::clacks::protocol::PlayerType`
Name | Value
-|-
PRIMARY_PLAYER | `0`
SPLIT_SCREEN_PLAYER | `1`
PlayerType_INT_MAX_SENTINEL_DO_NOT_USE_ | `2147483647`
PlayerType_INT_MIN_SENTINEL_DO_NOT_USE_ | `18446744071562067968`


### `Compressibility`
Name | Value
-|-
Compressible | `0`
Incompressible | `1`


### `ChunkState`
Name | Value
-|-
Unloaded | `0`
Generating | `1`
Generated | `2`
PostProcessing | `3`
PostProcessed | `4`
CheckingForReplacementData | `5`
NeedsLighting | `6`
Lighting_0 | `7`
Loaded | `8`


### `ChunkTerrainDataState`
Name | Value
-|-
NoData_0 | `0`
NeedsFixup | `1`
ReadyForGeneration | `2`
Generated_0 | `3`
PostProcessed_0 | `4`
Ready | `5`


### `ChunkDebugDisplaySavedState`
Name | Value
-|-
Generated_1 | `0`
Saved | `1`


### `ChunkCachedDataState`
Name | Value
-|-
NotGenerated | `0`
Generating_0 | `1`
Generated_2 | `2`


### `CommandBlockMode`
Name | Value
-|-
Normal_3 | `0`
Repeating | `1`
Chain | `2`


### `ChalkboardSize`
Name | Value
-|-
OnebyOne | `0`
TwobyOne | `1`
ThreebyTwo | `2`
Invalid_11 | `3`


### `Crypto::Asymmetric::System`
Name | Value
-|-
RSA_1024 | `0`
RSA_2048 | `1`
RSA_4096 | `2`
EC_prime256v1 | `3`
EC_secp256k1 | `4`
EC_secp384r1 | `5`
EC_secp521r1 | `6`


### `ContainerID`
Name | Value
-|-
CONTAINER_ID_INVENTORY | `0`
CONTAINER_ID_FIRST | `1`
CONTAINER_ID_LAST | `100`
CONTAINER_ID_OFFHAND | `119`
CONTAINER_ID_ARMOR | `120`
CONTAINER_ID_CREATIVE | `121`
CONTAINER_ID_SELECTION_SLOTS | `122`
CONTAINER_ID_PLAYER_ONLY_UI | `124`
CONTAINER_ID_NONE | `18446744073709551615`


### `CommandOutputType`
Name | Value
-|-
None_7 | `0`
LastOutput | `1`
Silent | `2`
AllOutput | `3`
DataSet | `4`


### `CraftingDataEntryType`
Name | Value
-|-
ShapelessRecipe | `0`
ShapedRecipe | `1`
FurnaceRecipe | `2`
FurnaceAuxRecipe | `3`
MultiRecipe | `4`
ShulkerBoxRecipe | `5`
ShapelessChemistryRecipe | `6`
ShapedChemistryRecipe | `7`


### `ClientboundMapItemDataPacket::Type`
Name | Value
-|-
Invalid_16 | `0`
TextureUpdate | `2`
DecorationUpdate | `4`
Creation | `8`


### `CommandOutputMessageType`
Name | Value
-|-
Success_0 | `0`
Error_1 | `1`


### `CommandOriginType`
Name | Value
-|-
Player_4 | `0`
CommandBlock_0 | `1`
MinecartCommandBlock_0 | `2`
DevConsole | `3`
Test_0 | `4`
AutomationPlayer | `5`
ClientAutomation | `6`
Entity_4 | `8`
Virtual | `9`
GameArgument | `10`
EntityServer | `11`
Precompiled | `12`
GameMasterEntityServer | `13`
Scripting_1 | `14`


### `ContainerType`
Name | Value
-|-
CONTAINER | `0`
WORKBENCH | `1`
FURNACE | `2`
ENCHANTMENT | `3`
BREWING_STAND | `4`
ANVIL | `5`
DISPENSER | `6`
DROPPER | `7`
HOPPER | `8`
CAULDRON | `9`
MINECART_CHEST | `10`
MINECART_HOPPER | `11`
HORSE | `12`
BEACON | `13`
STRUCTURE_EDITOR | `14`
TRADE | `15`
COMMAND_BLOCK | `16`
JUKEBOX | `17`
ARMOR | `18`
HAND | `19`
COMPOUND_CREATOR | `20`
ELEMENT_CONSTRUCTOR | `21`
MATERIAL_REDUCER | `22`
LAB_TABLE | `23`
LOOM | `24`
LECTERN | `25`
GRINDSTONE | `26`
BLAST_FURNACE | `27`
SMOKER | `28`
STONECUTTER | `29`
CARTOGRAPHY | `30`
NONE_2 | `18446744073709551607`
INVENTORY | `18446744073709551615`


### `ComplexInventoryTransaction::Type`
Name | Value
-|-
NormalTransaction | `0`
InventoryMismatch_0 | `1`
ItemUseTransaction | `2`
ItemUseOnEntityTransaction | `3`
ItemReleaseTransaction | `4`


### `ClientPlayMode`
Name | Value
-|-
Normal_5 | `0`
Teaser | `1`
Screen | `2`
Viewer | `3`
Reality | `4`
Placement | `5`
LivingRoom | `6`
ExitLevel | `7`
ExitLevelLivingRoom | `8`
NumModes | `9`


### `Core::DirectoryIterationFlags`
Name | Value
-|-
None_34 | `1`
FullPathName | `2`
Name | `4`
FileSize | `8`
Type | `16`
CreateTime | `32`
ModifyTime | `64`
CreateAndModifyTime | `96`
Files | `128`
Directories | `256`
FilesAndDirectories | `384`
Recursive | `512`
TreatFlatFileAsFile | `1024`
FileSizeAllocationOnDisk | `2048`


### `Core::ZipUtils::UnzipResult`
Name | Value
-|-
OK_0 | `0`
UnzipError | `1`
ParamError | `2`
BadZipFile | `3`
InternalError | `4`
CRCError | `5`


### `Core::ZipUtils::ZipResult`
Name | Value
-|-
OK_1 | `0`
ZipError | `1`
ParamError_0 | `2`
BadZipFile_0 | `3`
InternalError_0 | `4`


### `ContentTierIncompatibleReason_0`
Name | Value
-|-
None_32 | `0`
Memory | `1`


### `Core::LevelStorageState`
Name | Value
-|-
Open_0 | `0`
Corrupted | `1`
NotFound | `2`
IOError | `3`
NotSupported | `4`
InvalidArguments | `5`
Unknown_31 | `6`


### `CompactionStatus`
Name | Value
-|-
Starting_0 | `0`
Finished_1 | `1`


### `CommandOriginSystem`
Name | Value
-|-
AnimationTimelineSystem | `0`


### `CurrentCmdVersion`
Name | Value
-|-
Initial | `1`
TpRotationClamping | `2`
NewBedrockCmdSystem | `3`
ExecuteUsesVec3 | `4`
CloneFixes | `5`
UpdateAquatic | `6`
EntitySelectorUsesVec3 | `7`
ContainersDontDropItemsAnymore | `8`
FiltersObeyDimensions | `9`
ExecuteAndBlockCommandAndSelfSelectorFixes | `10`
Invalid_5 | `18446744073709551615`


### `CommandOutputParameter::NoCountType`
Name | Value
-|-
NoCount | `0`


### `CommandRegistry::HardTerminal`
Name | Value
-|-
Error_0 | `0`
Integer | `1`
NInteger | `2`
Identifier | `3`
Selector | `4`
Slash | `5`
Value | `6`
RValue | `7`
LValue | `8`
Equals | `9`
Comma | `10`
Colon | `11`
Not | `12`
Asterisk | `13`
Hash | `14`
OpenBracket | `15`
CloseBracket | `16`
OpenBrace | `17`
CloseBrace | `18`
String | `19`
Range | `20`
LessThan | `21`
GreaterThan | `22`
PlusEquals | `23`
MinusEquals | `24`
TimesEquals | `25`
DivideEquals | `26`
ModEquals | `27`
GreaterThanLessThan | `28`
Unknown_1 | `29`
End | `30`


### `CommandRegistry::HardNonTerminal`
Name | Value
-|-
Epsilon | `1048576`
Int_0 | `1048577`
Val | `1048578`
RVal | `1048579`
WildcardInt | `1048580`
Operator_0 | `1048581`
Selection | `1048582`
WildcardSelection | `1048583`
NonIdSelector | `1048584`
ScoresArg | `1048585`
ScoresArgs | `1048586`
ScoreSelectParam | `1048587`
ScoreSelector | `1048588`
TagSelector | `1048589`
FilePath | `1048590`
FilePathVal | `1048591`
FilePathCont | `1048592`
IntegerRangeVal | `1048593`
IntegerRangePostVal | `1048594`
IntegerRange | `1048595`
FullIntegerRange | `1048596`
SelArgs | `1048597`
Args | `1048598`
Arg | `1048599`
MArg | `1048600`
MValue | `1048601`
NameArg | `1048602`
TypeArg | `1048603`
TagArg | `1048604`
Id | `1048605`
IdCont | `1048606`
CoordXInt | `1048607`
CoordYInt | `1048608`
CoordZInt | `1048609`
CoordXFloat | `1048610`
CoordYFloat | `1048611`
CoordZFloat | `1048612`
Position | `1048613`
PositionFloat | `1048614`
MessageExp | `1048615`
Message_0 | `1048616`
MessageRoot | `1048617`
PostSelector | `1048618`
RawText | `1048619`
RawTextCont | `1048620`
JsonValue | `1048621`
JsonField | `1048622`
JsonObject | `1048623`
JsonObjectFields | `1048624`
JsonObjectCont | `1048625`
JsonArray | `1048626`
JsonArrayValues | `1048627`
JsonArrayCont | `1048628`
Command | `1048629`
SlashCommand | `1048630`


### `CommandParameterOption`
Name | Value
-|-
None_1 | `0`
EnumAutocompleteExpansion | `1`
HasSemanticConstraint | `2`


### `CommandLexer::TokenType`
Name | Value
-|-


### `CommandOperator_0`
Name | Value
-|-
Invalid_19 | `0`
Equals_0 | `1`
PlusEquals_0 | `2`
MinusEquals_0 | `3`
TimesEquals_0 | `4`
DivideEquals_0 | `5`
ModEquals_0 | `6`
MinEquals | `7`
MaxEquals | `8`
Swap | `9`


### `CommandCheatFlag`
Name | Value
-|-
Cheat | `0`
NotCheat | `64`


### `CommandTypeFlag`
Name | Value
-|-
None_5 | `0`
Message | `32`


### `CommandUsageFlag`
Name | Value
-|-
Normal_1 | `0`
Test | `1`


### `CommandSyncFlag`
Name | Value
-|-
Synced | `0`
Local | `8`


### `CommandSelectionType`
Name | Value
-|-
Self_0 | `0`
Entities | `1`
Players | `2`
DefaultPlayers | `3`
OwnedAgent | `4`
Agents | `5`


### `CommandSelectionOrder`
Name | Value
-|-
Sorted | `0`
InverseSorted | `1`


### `CommandStatus`
Name | Value
-|-
Invalid_6 | `0`
Local_0 | `1`
Remote | `2`


### `ChannelTransformAxisType`
Name | Value
-|-
Uniform | `0`
XYZ | `1`
Arbitrary | `2`
_Count_3 | `3`


### `CooldownType`
Name | Value
-|-
ChorusFruit_0 | `0`
EnderPearl | `1`
IceBomb_1 | `2`
Count_24 | `3`
TypeNone | `18446744073709551615`


### `CreativeItemCategory`
Name | Value
-|-
All_3 | `0`
Construction | `1`
Nature | `2`
Equipment | `3`
Items | `4`
ItemCommandOnly | `5`
Undefined_10 | `6`
NUM_CATEGORIES | `7`


### `ContainerBackgroundStyle`
Name | Value
-|-
Classic | `0`
Normal_10 | `1`
Invert | `2`
Red_2 | `3`
Selected | `4`
RedButton | `5`
Hint | `6`
Count_25 | `7`


### `ContainerEnumName`
Name | Value
-|-
AnvilInputContainer | `0`
AnvilMaterialContainer | `1`
AnvilResultPreviewContainer | `2`
ArmorContainer | `3`
LevelEntityContainer | `4`
BeaconPaymentContainer | `5`
BrewingStandInputContainer | `6`
BrewingStandResultContainer | `7`
BrewingStandFuelContainer | `8`
CombinedHotbarAndInventoryContainer | `9`
CraftingInputContainer | `10`
CraftingOutputPreviewContainer | `11`
RecipeConstructionContainer | `12`
RecipeNatureContainer | `13`
RecipeItemsContainer | `14`
RecipeSearchContainer | `15`
RecipeSearchBarContainer | `16`
RecipeEquipmentContainer | `17`
EnchantingInputContainer | `18`
EnchantingMaterialContainer | `19`
FurnaceFuelContainer | `20`
FurnaceIngredientContainer | `21`
FurnaceResultContainer | `22`
HorseEquipContainer | `23`
HotbarContainer | `24`
HudContainer | `25`
InventoryContainer | `26`
ShulkerBoxContainer | `27`
TradeIngredient1Container | `28`
TradeIngredient2Container | `29`
TradeResultPreviewContainer | `30`
OffhandContainer | `31`
CompoundCreatorInput | `32`
CompoundCreatorOutputPreview | `33`
ElementConstructorOutputPreview | `34`
MaterialReducerInput_0 | `35`
MaterialReducerOutput | `36`
LabTableInput | `37`
LoomInputContainer | `38`
LoomDyeContainer | `39`
LoomMaterialContainer | `40`
LoomResultPreviewContainer | `41`
BlastFurnaceIngredientContainer | `42`
SmokerIngredientContainer | `43`
Trade2Ingredient1Container | `44`
Trade2Ingredient2Container | `45`
Trade2ResultPreviewContainer | `46`
GrindstoneInputContainer | `47`
GrindstoneAdditionalContainer | `48`
GrindstoneResultPreviewContainer | `49`
StonecutterInputContainer | `50`
StonecutterResultPreviewContainer | `51`
CartographyInputContainer | `52`
CartographyAdditionalContainer | `53`
CartographyResultPreviewContainer | `54`
BarrelContainer | `55`
CursorContainer | `56`
CreatedOutputContainer | `57`


### `ContainerCategory`
Name | Value
-|-
Default_12 | `0`
PlayerInventory | `1`
Intermediary | `2`
Output_0 | `3`
Unknown_42 | `4`


### `ContainerExpandStatus`
Name | Value
-|-
Normal_11 | `0`
Expanded_0 | `1`
Contracted | `2`
Child | `3`
Count_26 | `4`


### `CompoundType`
Name | Value
-|-
Salt | `0`
SodiumOxide | `1`
SodiumHydroxide | `2`
MagnesiumNitrate | `3`
IronSulfide | `4`
LithiumHydride | `5`
SodiumHydride | `6`
CalciumBromide | `7`
MagnesiumOxide | `8`
SodiumAcetate | `9`
Luminol | `10`
Charcoal | `11`
Sugar | `12`
AluminumOxide | `13`
BoronTrioxide | `14`
Soap | `15`
Polyethylene | `16`
Garbage | `17`
MagnesiumSalts_0 | `18`
Sulfate | `19`
BariumSulfate | `20`
PotassiumChloride | `21`
MercuricChloride | `22`
CeriumChloride | `23`
TungstenChloride | `24`
CalciumChloride | `25`
Water_3 | `26`
Glue | `27`
Hypochlorite | `28`
CrudeOil | `29`
Latex | `30`
PotassiumIodide | `31`
SodiumFluoride | `32`
Benzene | `33`
Ink_0 | `34`
HydrogenPeroxide | `35`
Ammonia | `36`
SodiumHypochlorite | `37`
Invalid_23 | `38`


### `ChiselType`
Name | Value
-|-
Default_14 | `0`
Chiseled_0 | `1`
Lines | `2`
Smooth_0 | `3`
_count_30 | `4`


### `CoralColor`
Name | Value
-|-
Blue_2 | `0`
Pink_2 | `1`
Purple_2 | `2`
Red_4 | `3`
Yellow_2 | `4`
_count_35 | `5`


### `CauldronLiquidType`
Name | Value
-|-
Water_1 | `0`
Lava_3 | `1`
_count_22 | `2`


### `ChemistryTableType`
Name | Value
-|-
CompoundCreator | `0`
MaterialReducer | `1`
ElementConstructor | `2`
LabTable_0 | `3`
_count_25 | `4`


### `ChunkSource::LoadMode`
Name | Value
-|-
None_47 | `0`
Deferred | `1`


### `ComparatorCapacitor::Mode`
Name | Value
-|-
COMPARE_MODE | `0`
SUBTRACT_MODE | `1`


### `Crypto::Hash::HashType`
Name | Value
-|-
MD5 | `0`
SHA1 | `1`
SHA256 | `2`
SHA384 | `3`
SHA512 | `4`


### `CommonDirection`
Name | Value
-|-
North_2 | `0`
East_2 | `1`
South_2 | `2`
West_2 | `3`
DownNorthSouth_0 | `4`
DownEastWest_0 | `5`
UpNorthSouth_0 | `6`
UpEastWest_0 | `7`
AscendingEast | `8`
AscendingWest | `9`
AscendingNorth | `10`
AscendingSouth | `11`
SouthEast | `12`
SouthWest | `13`
NorthWest | `14`
NorthEast | `15`
None_54 | `16`


### `Core::FileBufferingMode`
Name | Value
-|-
Buffered | `0`
Unbuffered | `1`


### `CommandExecuteFlag`
Name | Value
-|-
Allowed | `0`
Disallowed | `16`


### `CompoundContainerType`
Name | Value
-|-
Jar | `0`
Beaker | `1`
Flask | `2`
Invalid_22 | `3`


### `CameraItemComponent::UseAction`
Name | Value
-|-
None_58 | `0`
Place_5 | `1`
Use_2 | `2`


### `ChestBlock::ChestType`
Name | Value
-|-
TYPE_BASIC | `0`
TYPE_TRAP | `1`
TYPE_ENDER | `2`


### `ColoredTorchColor`
Name | Value
-|-
Red_7 | `0`
Green_2 | `1`
Blue_3 | `2`
Purple_3 | `3`
Invalid_27 | `4`


### `CoralDirection`
Name | Value
-|-
West_3 | `0`
East_3 | `1`
North_3 | `2`
South_3 | `3`


### `CSHA1::REPORT_TYPE`
Name | Value
-|-
REPORT_HEX | `0`
REPORT_DIGIT | `1`
REPORT_HEX_SHORT | `2`


### `Core::FileAccessType`
Name | Value
-|-
ReadOnly | `0`
ReadWrite | `1`
Flush | `2`


### `Core::FileType`
Name | Value
-|-
File | `0`
Directory_1 | `1`
None_33 | `2`


### `Core::ZipUtils::ZipCompressionLevel`
Name | Value
-|-
Default_10 | `0`
NoCompression | `1`
BestSpeed | `2`
BestCompression | `3`


### `Core::Profile::CounterFormat`
Name | Value
-|-
Default_8 | `0`
Bytes | `1`


### `Core::Profile::CounterFlags`
Name | Value
-|-
None_62 | `0`
Detailed | `1`
DetailedGraph | `2`


### `Core::Profile::FileExtension`
Name | Value
-|-
HTML | `0`
CSV | `1`
BOTH | `2`


### `CURLcode`
Name | Value
-|-
CURLE_OK | `0`
CURLE_UNSUPPORTED_PROTOCOL | `1`
CURLE_FAILED_INIT | `2`
CURLE_URL_MALFORMAT | `3`
CURLE_OBSOLETE4 | `4`
CURLE_COULDNT_RESOLVE_PROXY | `5`
CURLE_COULDNT_RESOLVE_HOST | `6`
CURLE_COULDNT_CONNECT | `7`
CURLE_FTP_WEIRD_SERVER_REPLY | `8`
CURLE_REMOTE_ACCESS_DENIED | `9`
CURLE_OBSOLETE10 | `10`
CURLE_FTP_WEIRD_PASS_REPLY | `11`
CURLE_OBSOLETE12 | `12`
CURLE_FTP_WEIRD_PASV_REPLY | `13`
CURLE_FTP_WEIRD_227_FORMAT | `14`
CURLE_FTP_CANT_GET_HOST | `15`
CURLE_OBSOLETE16 | `16`
CURLE_FTP_COULDNT_SET_TYPE | `17`
CURLE_PARTIAL_FILE | `18`
CURLE_FTP_COULDNT_RETR_FILE | `19`
CURLE_OBSOLETE20 | `20`
CURLE_QUOTE_ERROR | `21`
CURLE_HTTP_RETURNED_ERROR | `22`
CURLE_WRITE_ERROR | `23`
CURLE_OBSOLETE24 | `24`
CURLE_UPLOAD_FAILED | `25`
CURLE_READ_ERROR | `26`
CURLE_OUT_OF_MEMORY | `27`
CURLE_OPERATION_TIMEDOUT | `28`
CURLE_OBSOLETE29 | `29`
CURLE_FTP_PORT_FAILED | `30`
CURLE_FTP_COULDNT_USE_REST | `31`
CURLE_OBSOLETE32 | `32`
CURLE_RANGE_ERROR | `33`
CURLE_HTTP_POST_ERROR | `34`
CURLE_SSL_CONNECT_ERROR | `35`
CURLE_BAD_DOWNLOAD_RESUME | `36`
CURLE_FILE_COULDNT_READ_FILE | `37`
CURLE_LDAP_CANNOT_BIND | `38`
CURLE_LDAP_SEARCH_FAILED | `39`
CURLE_OBSOLETE40 | `40`
CURLE_FUNCTION_NOT_FOUND | `41`
CURLE_ABORTED_BY_CALLBACK | `42`
CURLE_BAD_FUNCTION_ARGUMENT | `43`
CURLE_OBSOLETE44 | `44`
CURLE_INTERFACE_FAILED | `45`
CURLE_OBSOLETE46 | `46`
CURLE_TOO_MANY_REDIRECTS | `47`
CURLE_UNKNOWN_TELNET_OPTION | `48`
CURLE_TELNET_OPTION_SYNTAX | `49`
CURLE_OBSOLETE50 | `50`
CURLE_PEER_FAILED_VERIFICATION | `51`
CURLE_GOT_NOTHING | `52`
CURLE_SSL_ENGINE_NOTFOUND | `53`
CURLE_SSL_ENGINE_SETFAILED | `54`
CURLE_SEND_ERROR | `55`
CURLE_RECV_ERROR | `56`
CURLE_OBSOLETE57 | `57`
CURLE_SSL_CERTPROBLEM | `58`
CURLE_SSL_CIPHER | `59`
CURLE_SSL_CACERT | `60`
CURLE_BAD_CONTENT_ENCODING | `61`
CURLE_LDAP_INVALID_URL | `62`
CURLE_FILESIZE_EXCEEDED | `63`
CURLE_USE_SSL_FAILED | `64`
CURLE_SEND_FAIL_REWIND | `65`
CURLE_SSL_ENGINE_INITFAILED | `66`
CURLE_LOGIN_DENIED | `67`
CURLE_TFTP_NOTFOUND | `68`
CURLE_TFTP_PERM | `69`
CURLE_REMOTE_DISK_FULL | `70`
CURLE_TFTP_ILLEGAL | `71`
CURLE_TFTP_UNKNOWNID | `72`
CURLE_REMOTE_FILE_EXISTS | `73`
CURLE_TFTP_NOSUCHUSER | `74`
CURLE_CONV_FAILED | `75`
CURLE_CONV_REQD | `76`
CURLE_SSL_CACERT_BADFILE | `77`
CURLE_REMOTE_FILE_NOT_FOUND | `78`
CURLE_SSH | `79`
CURLE_SSL_SHUTDOWN_FAILED | `80`
CURLE_AGAIN | `81`
CURLE_SSL_CRL_BADFILE | `82`
CURLE_SSL_ISSUER_ERROR | `83`
CURL_LAST | `84`


### `ConversionResult`
Name | Value
-|-
conversionOK | `0`
sourceExhausted | `1`
targetExhausted | `2`
sourceIllegal | `3`


### `ConversionFlags`
Name | Value
-|-
strictConversion_0 | `0`
lenientConversion_0 | `1`


### `com::mojang::clacks::protocol::DifficultySetting`
Name | Value
-|-
PEACEFUL | `0`
EASY | `1`
NORMAL | `2`
HARD | `3`
DifficultySetting_INT_MAX_SENTINEL_DO_NOT_USE_ | `2147483647`
DifficultySetting_INT_MIN_SENTINEL_DO_NOT_USE_ | `18446744071562067968`


### `com::mojang::clacks::protocol::CheatsSetting`
Name | Value
-|-
ALLOW | `0`
DISALLOW | `1`
CheatsSetting_INT_MAX_SENTINEL_DO_NOT_USE_ | `2147483647`
CheatsSetting_INT_MIN_SENTINEL_DO_NOT_USE_ | `18446744071562067968`


### `ChangeSettingCommand::Setting`
Name | Value
-|-
AllowCheats | `0`


### `Crypto::Symmetric::OperationMode`
Name | Value
-|-
ECB | `0`
CBC | `1`
CFB | `2`
OFB | `3`


### `Crypto::Symmetric::System`
Name | Value
-|-
AES_128 | `0`
AES_256 | `1`


### `CloneCommand::MaskMode`
Name | Value
-|-
Replace_0 | `0`
Filtered | `1`
Masked | `2`


### `CloneCommand::CloneMode`
Name | Value
-|-
Normal_15 | `0`
Force | `1`
Move | `2`


### `CommandOperator`
```
enum CommandOperator : __int8
{
};

```

### `ContentTierIncompatibleReason`
```
enum ContentTierIncompatibleReason : __int32
{
};

```

### `com::mojang::clacks::protocol::Settings::SettingsCase`
```
enum com::mojang::clacks::protocol::Settings::SettingsCase : __int32
{
  kDifficultySetting = 0x1,
  kCheatsSetting = 0x2,
  SETTINGS_NOT_SET = 0x0,
};

```

### `com::mojang::clacks::protocol::MetricReport::MetricCase`
```
enum com::mojang::clacks::protocol::MetricReport::MetricCase : __int32
{
  kBandwith = 0x1,
  kLatency = 0x2,
  kTickTime = 0x3,
  METRIC_NOT_SET = 0x0,
};

```

### `CompoundTagUpdaterResult`
```
enum CompoundTagUpdaterResult : __int32
{
  Success_2 = 0x0,
  NoUpdateNeeded = 0x1,
  Failed_0 = 0x2,
};

```

### `ChangeDimensionRequest::State`
```
enum ChangeDimensionRequest::State : __int32
{
  PrepareRegion = 0x0,
  WaitingForChunks = 0x1,
  WaitingForRespawn = 0x2,
};

```

### `ColorFormat::ColorEnum::AvailableColors`
```
enum ColorFormat::ColorEnum::AvailableColors : __int32
{
  BLACK = 0x0,
  DARK_BLUE = 0x1,
  DARK_GREEN = 0x2,
  DARK_AQUA = 0x3,
  DARK_RED = 0x4,
  DARK_PURPLE = 0x5,
  GOLD = 0x6,
  GRAY = 0x7,
  DARK_GRAY = 0x8,
  BLUE_0 = 0x9,
  GREEN_0 = 0xA,
  AQUA = 0xB,
  RED_0 = 0xC,
  LIGHT_PURPLE = 0xD,
  YELLOW_0 = 0xE,
  WHITE_0 = 0xF,
  MINECOIN_GOLD = 0x10,
  COUNT_6 = 0x11,
};

```

### `cg::ColorSpace`
```
enum cg::ColorSpace : __int8
{
  Unknown_47 = 0x0,
  sRGB_0 = 0x1,
  Linear_0 = 0x2,
};

```

### `Core::FileStorageArea::FlushableLevelDbEnvType`
```
enum Core::FileStorageArea::FlushableLevelDbEnvType : __int32
{
  None_60 = 0x0,
  InMemory = 0x1,
  StorageArea = 0x2,
};

```

### `CrashDumpLogStringID`
```
enum CrashDumpLogStringID : __int16
{
  None_61 = 0x0,
  HandleBuildAction = 0x1,
  EnterScope = 0x2,
  ExitScope = 0x3,
  AppPlatform_initialize = 0x4,
  MinecraftGame_update = 0x5,
  DataDrivenRenderer_renderModel = 0x6,
  KillMinecraft = 0x7,
  StartMinecraft = 0x8,
  Main = 0x9,
  MakeMinecraftGame = 0xA,
  MainLoop = 0xB,
  AppResetRequested = 0xC,
  Shutdown = 0xD,
  ActorRenderDisplatcher_Render = 0xE,
  AppMain_updateAndRender = 0xF,
  AppPlatformWinrt_Update = 0x10,
  AppView_run = 0x11,
  MinecraftGame_initStep = 0x12,
  MinecraftGame_suspendStep = 0x13,
  MinecraftGame_resumeStep = 0x14,
  AbortedScope = 0x15,
  SaveData_mount = 0x16,
  SaveData_unmount = 0x17,
  SaveData_remount = 0x18,
  SaveData_watchdog = 0x19,
  _count_54 = 0x1A,
};

```

### `Core::FlatFileManifestInfo::FlatFileManifestInfoFlags`
```
enum Core::FlatFileManifestInfo::FlatFileManifestInfoFlags : __int8
{
  File_0 = 0x1,
  Deleted = 0x80,
};

```

### `CURLoption`
```
enum CURLoption : __int32
{
  CURLOPT_FILE = 0x2711,
  CURLOPT_URL = 0x2712,
  CURLOPT_PORT = 0x3,
  CURLOPT_PROXY = 0x2714,
  CURLOPT_USERPWD = 0x2715,
  CURLOPT_PROXYUSERPWD = 0x2716,
  CURLOPT_RANGE = 0x2717,
  CURLOPT_INFILE = 0x2719,
  CURLOPT_ERRORBUFFER = 0x271A,
  CURLOPT_WRITEFUNCTION = 0x4E2B,
  CURLOPT_READFUNCTION = 0x4E2C,
  CURLOPT_TIMEOUT = 0xD,
  CURLOPT_INFILESIZE = 0xE,
  CURLOPT_POSTFIELDS = 0x271F,
  CURLOPT_REFERER = 0x2720,
  CURLOPT_FTPPORT = 0x2721,
  CURLOPT_USERAGENT = 0x2722,
  CURLOPT_LOW_SPEED_LIMIT = 0x13,
  CURLOPT_LOW_SPEED_TIME = 0x14,
  CURLOPT_RESUME_FROM = 0x15,
  CURLOPT_COOKIE = 0x2726,
  CURLOPT_HTTPHEADER = 0x2727,
  CURLOPT_HTTPPOST = 0x2728,
  CURLOPT_SSLCERT = 0x2729,
  CURLOPT_KEYPASSWD = 0x272A,
  CURLOPT_CRLF = 0x1B,
  CURLOPT_QUOTE = 0x272C,
  CURLOPT_WRITEHEADER = 0x272D,
  CURLOPT_COOKIEFILE = 0x272F,
  CURLOPT_SSLVERSION = 0x20,
  CURLOPT_TIMECONDITION = 0x21,
  CURLOPT_TIMEVALUE = 0x22,
  CURLOPT_CUSTOMREQUEST = 0x2734,
  CURLOPT_STDERR = 0x2735,
  CURLOPT_POSTQUOTE = 0x2737,
  CURLOPT_WRITEINFO = 0x2738,
  CURLOPT_VERBOSE = 0x29,
  CURLOPT_HEADER = 0x2A,
  CURLOPT_NOPROGRESS = 0x2B,
  CURLOPT_NOBODY = 0x2C,
  CURLOPT_FAILONERROR = 0x2D,
  CURLOPT_UPLOAD = 0x2E,
  CURLOPT_POST = 0x2F,
  CURLOPT_DIRLISTONLY = 0x30,
  CURLOPT_APPEND = 0x32,
  CURLOPT_NETRC = 0x33,
  CURLOPT_FOLLOWLOCATION = 0x34,
  CURLOPT_TRANSFERTEXT = 0x35,
  CURLOPT_PUT = 0x36,
  CURLOPT_PROGRESSFUNCTION = 0x4E58,
  CURLOPT_PROGRESSDATA = 0x2749,
  CURLOPT_AUTOREFERER = 0x3A,
  CURLOPT_PROXYPORT = 0x3B,
  CURLOPT_POSTFIELDSIZE = 0x3C,
  CURLOPT_HTTPPROXYTUNNEL = 0x3D,
  CURLOPT_INTERFACE = 0x274E,
  CURLOPT_KRBLEVEL = 0x274F,
  CURLOPT_SSL_VERIFYPEER = 0x40,
  CURLOPT_CAINFO = 0x2751,
  CURLOPT_MAXREDIRS = 0x44,
  CURLOPT_FILETIME = 0x45,
  CURLOPT_TELNETOPTIONS = 0x2756,
  CURLOPT_MAXCONNECTS = 0x47,
  CURLOPT_CLOSEPOLICY = 0x48,
  CURLOPT_FRESH_CONNECT = 0x4A,
  CURLOPT_FORBID_REUSE = 0x4B,
  CURLOPT_RANDOM_FILE = 0x275C,
  CURLOPT_EGDSOCKET = 0x275D,
  CURLOPT_CONNECTTIMEOUT = 0x4E,
  CURLOPT_HEADERFUNCTION = 0x4E6F,
  CURLOPT_HTTPGET = 0x50,
  CURLOPT_SSL_VERIFYHOST = 0x51,
  CURLOPT_COOKIEJAR = 0x2762,
  CURLOPT_SSL_CIPHER_LIST = 0x2763,
  CURLOPT_HTTP_VERSION = 0x54,
  CURLOPT_FTP_USE_EPSV = 0x55,
  CURLOPT_SSLCERTTYPE = 0x2766,
  CURLOPT_SSLKEY = 0x2767,
  CURLOPT_SSLKEYTYPE = 0x2768,
  CURLOPT_SSLENGINE = 0x2769,
  CURLOPT_SSLENGINE_DEFAULT = 0x5A,
  CURLOPT_DNS_USE_GLOBAL_CACHE = 0x5B,
  CURLOPT_DNS_CACHE_TIMEOUT = 0x5C,
  CURLOPT_PREQUOTE = 0x276D,
  CURLOPT_DEBUGFUNCTION = 0x4E7E,
  CURLOPT_DEBUGDATA = 0x276F,
  CURLOPT_COOKIESESSION = 0x60,
  CURLOPT_CAPATH = 0x2771,
  CURLOPT_BUFFERSIZE = 0x62,
  CURLOPT_NOSIGNAL = 0x63,
  CURLOPT_SHARE = 0x2774,
  CURLOPT_PROXYTYPE = 0x65,
  CURLOPT_ENCODING = 0x2776,
  CURLOPT_PRIVATE = 0x2777,
  CURLOPT_HTTP200ALIASES = 0x2778,
  CURLOPT_UNRESTRICTED_AUTH = 0x69,
  CURLOPT_FTP_USE_EPRT = 0x6A,
  CURLOPT_HTTPAUTH = 0x6B,
  CURLOPT_SSL_CTX_FUNCTION = 0x4E8C,
  CURLOPT_SSL_CTX_DATA = 0x277D,
  CURLOPT_FTP_CREATE_MISSING_DIRS = 0x6E,
  CURLOPT_PROXYAUTH = 0x6F,
  CURLOPT_FTP_RESPONSE_TIMEOUT = 0x70,
  CURLOPT_IPRESOLVE = 0x71,
  CURLOPT_MAXFILESIZE = 0x72,
  CURLOPT_INFILESIZE_LARGE = 0x75A3,
  CURLOPT_RESUME_FROM_LARGE = 0x75A4,
  CURLOPT_MAXFILESIZE_LARGE = 0x75A5,
  CURLOPT_NETRC_FILE = 0x2786,
  CURLOPT_USE_SSL = 0x77,
  CURLOPT_POSTFIELDSIZE_LARGE = 0x75A8,
  CURLOPT_TCP_NODELAY = 0x79,
  CURLOPT_FTPSSLAUTH = 0x81,
  CURLOPT_IOCTLFUNCTION = 0x4EA2,
  CURLOPT_IOCTLDATA = 0x2793,
  CURLOPT_FTP_ACCOUNT = 0x2796,
  CURLOPT_COOKIELIST = 0x2797,
  CURLOPT_IGNORE_CONTENT_LENGTH = 0x88,
  CURLOPT_FTP_SKIP_PASV_IP = 0x89,
  CURLOPT_FTP_FILEMETHOD = 0x8A,
  CURLOPT_LOCALPORT = 0x8B,
  CURLOPT_LOCALPORTRANGE = 0x8C,
  CURLOPT_CONNECT_ONLY = 0x8D,
  CURLOPT_CONV_FROM_NETWORK_FUNCTION = 0x4EAE,
  CURLOPT_CONV_TO_NETWORK_FUNCTION = 0x4EAF,
  CURLOPT_CONV_FROM_UTF8_FUNCTION = 0x4EB0,
  CURLOPT_MAX_SEND_SPEED_LARGE = 0x75C1,
  CURLOPT_MAX_RECV_SPEED_LARGE = 0x75C2,
  CURLOPT_FTP_ALTERNATIVE_TO_USER = 0x27A3,
  CURLOPT_SOCKOPTFUNCTION = 0x4EB4,
  CURLOPT_SOCKOPTDATA = 0x27A5,
  CURLOPT_SSL_SESSIONID_CACHE = 0x96,
  CURLOPT_SSH_AUTH_TYPES = 0x97,
  CURLOPT_SSH_PUBLIC_KEYFILE = 0x27A8,
  CURLOPT_SSH_PRIVATE_KEYFILE = 0x27A9,
  CURLOPT_FTP_SSL_CCC = 0x9A,
  CURLOPT_TIMEOUT_MS = 0x9B,
  CURLOPT_CONNECTTIMEOUT_MS = 0x9C,
  CURLOPT_HTTP_TRANSFER_DECODING = 0x9D,
  CURLOPT_HTTP_CONTENT_DECODING = 0x9E,
  CURLOPT_NEW_FILE_PERMS = 0x9F,
  CURLOPT_NEW_DIRECTORY_PERMS = 0xA0,
  CURLOPT_POSTREDIR = 0xA1,
  CURLOPT_SSH_HOST_PUBLIC_KEY_MD5 = 0x27B2,
  CURLOPT_OPENSOCKETFUNCTION = 0x4EC3,
  CURLOPT_OPENSOCKETDATA = 0x27B4,
  CURLOPT_COPYPOSTFIELDS = 0x27B5,
  CURLOPT_PROXY_TRANSFER_MODE = 0xA6,
  CURLOPT_SEEKFUNCTION = 0x4EC7,
  CURLOPT_SEEKDATA = 0x27B8,
  CURLOPT_CRLFILE = 0x27B9,
  CURLOPT_ISSUERCERT = 0x27BA,
  CURLOPT_ADDRESS_SCOPE = 0xAB,
  CURLOPT_CERTINFO = 0xAC,
  CURLOPT_USERNAME = 0x27BD,
  CURLOPT_PASSWORD = 0x27BE,
  CURLOPT_PROXYUSERNAME = 0x27BF,
  CURLOPT_PROXYPASSWORD = 0x27C0,
  CURLOPT_NOPROXY = 0x27C1,
  CURLOPT_TFTP_BLKSIZE = 0xB2,
  CURLOPT_SOCKS5_GSSAPI_SERVICE = 0x27C3,
  CURLOPT_SOCKS5_GSSAPI_NEC = 0xB4,
  CURLOPT_PROTOCOLS = 0xB5,
  CURLOPT_REDIR_PROTOCOLS = 0xB6,
  CURLOPT_SSH_KNOWNHOSTS = 0x27C7,
  CURLOPT_SSH_KEYFUNCTION = 0x4ED8,
  CURLOPT_SSH_KEYDATA = 0x27C9,
  CURLOPT_LASTENTRY = 0x27CA,
};

```

### `CURLFORMcode`
```
enum CURLFORMcode : __int32
{
  CURL_FORMADD_OK = 0x0,
  CURL_FORMADD_MEMORY = 0x1,
  CURL_FORMADD_OPTION_TWICE = 0x2,
  CURL_FORMADD_NULL = 0x3,
  CURL_FORMADD_UNKNOWN_OPTION = 0x4,
  CURL_FORMADD_INCOMPLETE = 0x5,
  CURL_FORMADD_ILLEGAL_ARRAY = 0x6,
  CURL_FORMADD_DISABLED = 0x7,
  CURL_FORMADD_LAST = 0x8,
};

```

### `CURLINFO`
```
enum CURLINFO : __int32
{
  CURLINFO_NONE = 0x0,
  CURLINFO_EFFECTIVE_URL = 0x100001,
  CURLINFO_RESPONSE_CODE = 0x200002,
  CURLINFO_TOTAL_TIME = 0x300003,
  CURLINFO_NAMELOOKUP_TIME = 0x300004,
  CURLINFO_CONNECT_TIME = 0x300005,
  CURLINFO_PRETRANSFER_TIME = 0x300006,
  CURLINFO_SIZE_UPLOAD = 0x300007,
  CURLINFO_SIZE_DOWNLOAD = 0x300008,
  CURLINFO_SPEED_DOWNLOAD = 0x300009,
  CURLINFO_SPEED_UPLOAD = 0x30000A,
  CURLINFO_HEADER_SIZE = 0x20000B,
  CURLINFO_REQUEST_SIZE = 0x20000C,
  CURLINFO_SSL_VERIFYRESULT = 0x20000D,
  CURLINFO_FILETIME = 0x20000E,
  CURLINFO_CONTENT_LENGTH_DOWNLOAD = 0x30000F,
  CURLINFO_CONTENT_LENGTH_UPLOAD = 0x300010,
  CURLINFO_STARTTRANSFER_TIME = 0x300011,
  CURLINFO_CONTENT_TYPE = 0x100012,
  CURLINFO_REDIRECT_TIME = 0x300013,
  CURLINFO_REDIRECT_COUNT = 0x200014,
  CURLINFO_PRIVATE = 0x100015,
  CURLINFO_HTTP_CONNECTCODE = 0x200016,
  CURLINFO_HTTPAUTH_AVAIL = 0x200017,
  CURLINFO_PROXYAUTH_AVAIL = 0x200018,
  CURLINFO_OS_ERRNO = 0x200019,
  CURLINFO_NUM_CONNECTS = 0x20001A,
  CURLINFO_SSL_ENGINES = 0x40001B,
  CURLINFO_COOKIELIST = 0x40001C,
  CURLINFO_LASTSOCKET = 0x20001D,
  CURLINFO_FTP_ENTRY_PATH = 0x10001E,
  CURLINFO_REDIRECT_URL = 0x10001F,
  CURLINFO_PRIMARY_IP = 0x100020,
  CURLINFO_APPCONNECT_TIME = 0x300021,
  CURLINFO_CERTINFO = 0x400022,
  CURLINFO_CONDITION_UNMET = 0x200023,
  CURLINFO_LASTONE = 0x23,
};

```

