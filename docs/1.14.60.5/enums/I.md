# I
### `ItemUseMethod`
Name | Value
-|-


### `ItemAcquisitionMethod`
Name | Value
-|-


### `InventorySourceType`
Name | Value
-|-
ContainerInventory | `0`
GlobalInventory | `1`
WorldInteraction | `2`
CreativeInventory | `3`
UntrackedInteractionUI | `100`
NonImplementedFeatureTODO | `99999`
InvalidInventory | `18446744073709551615`


### `InventorySource::InventorySourceFlags`
Name | Value
-|-
NoFlag | `0`
WorldInteraction_Random | `1`


### `IMinecraftEventing::EducationLessonAction`
Name | Value
-|-
Start | `0`
Continue | `1`
Restart | `2`
Host_0 | `3`
Join | `4`
Finish | `5`


### `ItemAcquisitionMethod_0`
Name | Value
-|-
None_16 | `0`
PickedUp | `1`
Crafted_0 | `2`
TakenFromChest | `3`
TakenFromEnderchest | `4`
Bought | `5`
Anvil | `6`
Smelted | `7`
Brewed | `8`
Filled_0 | `9`
Trading_0 | `10`
Fishing | `11`
Container | `13`
Unknown_8 | `18446744073709551615`


### `ItemUseMethod_0`
Name | Value
-|-
EquipArmor | `0`
Eat_1 | `1`
Attack_0 | `2`
Consume | `3`
Throw_0 | `4`
Shoot_0 | `5`
Place_0 | `6`
FillBottle | `7`
FillBucket | `8`
PourBucket | `9`
UseTool | `10`
Interact | `11`
Retrieved | `12`
Dyed | `13`
Traded | `14`
_Count_0 | `15`
Unknown_6 | `18446744073709551615`


### `IMinecraftEventing::FileTransmissionDirection`
Name | Value
-|-
Download | `0`
Upload | `1`


### `IMinecraftEventing::FileTransmissionState`
Name | Value
-|-
Failed_4 | `0`
Started_0 | `1`
Completed | `2`
Resumed | `3`
Canceled_0 | `18446744073709551615`


### `IMinecraftEventing::FileTransmissionType`
Name | Value
-|-
Realm_file | `1`
Dlc | `2`
Remix3D_DEPRECATED | `3`
DlcUpdate_Auto | `4`
DlcUpdate_User | `5`


### `IMinecraftEventing::ConnectionFailureReason`
Name | Value
-|-
MismatchedMinecraftProtocol | `1`
MismatchedRaknetVersion | `2`
Unknown_19 | `18446744073709551615`


### `IMinecraftEventing::SignInStage`
Name | Value
-|-
Unknown_16 | `0`
Starting | `1`
Failed_3 | `2`
Canceled | `3`
Succeeded | `4`
Succeeded_New_Account | `5`
Failed_Create | `6`


### `IMinecraftEventing::EduSignInStage`
Name | Value
-|-
Unknown_20 | `0`
AttemptingActiveDirectory | `1`
FailedActiveDirectory | `2`
AttemptingMuts | `3`
FailedMuts | `4`
PresentingingEula | `5`
Success_7 | `6`
RefreshingActiveDirectory | `7`
RefreshActiveDirectorySuccess | `8`
RefreshActiveDirectoryFailed | `9`


### `IMinecraftEventing::ServerConnectionOutcome`
Name | Value
-|-
Success_4 | `0`
Failed_2 | `1`
Failed_UserOffline | `2`
Failed_ServerFull | `3`
Failed_ServerOffline | `4`


### `IMinecraftEventing::StructureBlockActionType`
Name | Value
-|-
Save | `0`
Load | `1`
Export | `2`
Export3D | `3`
LeaveScreen | `4`
Unknown_11 | `18446744073709551615`


### `IMinecraftEventing::NetworkType`
Name | Value
-|-
Local_2 | `0`
LAN | `1`
External | `2`
Friend | `3`
Realm | `4`
ThirdParty | `5`


### `IMinecraftEventing::PurchaseResult`
Name | Value
-|-
Canceled_1 | `0`
Success_6 | `1`
Failed_5 | `18446744073709551615`


### `IMinecraftEventing::StoreType`
Name | Value
-|-
Store | `0`
DressingRoom | `1`


### `InputMode`
Name | Value
-|-
Undefined_7 | `0`
Mouse | `1`
Touch | `2`
GamePad | `3`
MotionController_0 | `4`
Count_5 | `5`


### `IMinecraftEventing::DeviceAccountFailurePhase`
Name | Value
-|-
Unknown_18 | `0`
SignIn | `1`
LoadCredentials | `2`
TitleKey | `3`
StoreVerify | `4`
PlayFabCreate_Configured | `5`
PlayFabCreate | `6`


### `IMinecraftEventing::OpenCodeMethod`
Name | Value
-|-
TouchHUD | `0`
Keypress | `1`
Command_1 | `2`


### `IMinecraftEventing::ExportOutcome`
Name | Value
-|-
Failed_1 | `0`
Success_3 | `1`


### `IMinecraftEventing::ExportStage`
Name | Value
-|-
Initiated | `0`
Completed_0 | `1`


### `IMinecraftEventing::DayOneExperienceState`
Name | Value
-|-
Started | `0`
CompletedWithoutWorlds | `1`
CompletedWithImportSkipped | `2`
CompletedWithImport | `3`


### `IMinecraftEventing::RealmConnectionFlow`
Name | Value
-|-
PlayScreen_0 | `0`
SettingsScreen | `1`
InviteLink | `2`
WhiteList | `3`
Marketplace | `4`
CreateScreen | `5`


### `IMinecraftEventing::RealmConnectionLambda`
Name | Value
-|-
CompletedCallback | `0`
RetryCallback | `1`
ProgressScreenTickCallback | `2`
ProgressScreenOnCancelCallback | `3`
GameServerConnectProgressCallback | `4`


### `IMinecraftEventing::RealmConnectionResult`
Name | Value
-|-
Success_5 | `0`
SuccessWithWarning | `1`
FailWithUnnassignedDevVersion | `2`
Fail_1 | `3`
Retry | `4`
CancelByUser | `5`
InvalidCallback | `6`
Unknown_17 | `7`
TimedOut | `8`


### `IMinecraftEventing::ClubsFeedScreenSource`
Name | Value
-|-
PlayScreen | `0`
PauseScreen | `1`


### `IMinecraftEventing::ClubsEngagementAction`
Name | Value
-|-
Like | `0`
Unlike | `1`
Post | `2`
Delete | `3`
Report | `4`
Comment | `5`


### `IMinecraftEventing::ClubsEngagementTargetType`
Name | Value
-|-
Unknown_12 | `0`
ImageFeedPost | `1`
TextFeedPost | `2`
Comment_0 | `3`


### `IMinecraftEventing::ElementConstructorUseType`
Name | Value
-|-
Created | `0`
Entered | `1`


### `IMinecraftEventing::PromotionType`
Name | Value
-|-
Featured | `0`
Default_6 | `1`
None_19 | `2`


### `IMinecraftEventing::PetDeathContext`
Name | Value
-|-
DiedOfOtherCause | `0`
PlayerMurdered | `1`
OwnerMurdered | `2`
MobMurdered | `3`


### `InventoryTransactionError`
Name | Value
-|-
Unknown_4 | `0`
NoError | `1`
BalanceMismatch | `2`
SourceItemMismatch | `3`
InventoryMismatch | `4`
SizeMismatch | `5`
AuthorityMismatch | `6`
StateMismatch | `7`
ApiDenied | `8`


### `InteractPacket::Action`
Name | Value
-|-
StopRiding | `3`
InteractUpdate | `4`
NpcOpen | `5`
OpenInventory | `6`


### `IdentityDefinition::Type`
Name | Value
-|-
Invalid_14 | `0`
Player_2 | `1`
Entity_2 | `2`
FakePlayer | `3`


### `IntellisenseUtils::MatcherOptions`
Name | Value
-|-
NONE_7 | `0`
HIGHLIGHT | `1`
CASE_SENSITIVE | `2`


### `IFileChunkUploader::UploadStreamResult`
Name | Value
-|-
Success_10 | `0`
Failure | `1`
FailureForbidden | `2`
None_37 | `3`


### `ItemReleaseInventoryTransaction::ActionType`
Name | Value
-|-
Release_0 | `0`
Use_0 | `1`


### `ItemTakeType`
Name | Value
-|-
All_5 | `0`
Half | `1`
One | `2`


### `ItemPlaceType`
Name | Value
-|-
All_6 | `0`
One_0 | `1`


### `ItemAddType`
Name | Value
-|-
All_7 | `0`
Partial_0 | `1`
None_49 | `2`


### `ItemTransferAmount::ItemTransferAmountTag`
Name | Value
-|-
RequestAmount | `0`
TakeType | `1`
PlaceType | `2`


### `ItemSetType`
Name | Value
-|-
Place_3 | `0`
Swap_0 | `1`
Add_5 | `2`
None_48 | `3`


### `ItemUseOnActorInventoryTransaction::ActionType`
Name | Value
-|-
Interact_1 | `0`
Attack_2 | `1`
ItemInteract | `2`


### `ItemUseInventoryTransaction::ActionType`
Name | Value
-|-
Place_4 | `0`
Use_1 | `1`
Destroy | `2`


### `ItemColor`
Name | Value
-|-
Black_1 | `0`
Red_3 | `1`
Green_1 | `2`
Brown_1 | `3`
Blue_1 | `4`
Purple_1 | `5`
Cyan_1 | `6`
Silver_1 | `7`
Gray_1 | `8`
Pink_1 | `9`
Lime_0 | `10`
Yellow_1 | `11`
LightBlue_0 | `12`
Magenta_1 | `13`
Orange_1 | `14`
White_1 | `15`
_count_26 | `16`


### `InMemoryAccessMode`
Name | Value
-|-
Read | `0`
Write | `1`


### `IMinecraftEventing::ShareMode`
```
enum IMinecraftEventing::ShareMode : __int32
{
  Share = 0x1,
  Copy = 0x2,
};

```

### `InHandUpdateType`
```
enum InHandUpdateType : __int8
{
  NONE_13 = 0x0,
  UPDATE = 0x1,
  SWAP = 0x2,
};

```

