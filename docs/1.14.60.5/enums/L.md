# L
### `Lockless::MemoryOrder`
Name | Value
-|-
Relaxed | `0`
Acquire | `1`
Release | `2`
AcqRel | `3`
SeqCst | `4`
Sync | `4`


### `LogArea`
Name | Value
-|-
Actor | `0`
Addon_0 | `1`
AI | `2`
Animation | `3`
AutomatedTests | `4`
BiomeRegistry | `5`
Blocks | `6`
Camera | `7`
Commands | `8`
Components | `9`
Effects | `10`
Entity | `11`
FeatureRegistry | `12`
Geometry | `13`
Item | `14`
Json | `15`
LevelStorage | `16`
Log | `17`
Molang | `18`
Recipes | `19`
Rendering | `20`
Scripting | `21`
Sound | `22`
Structure | `23`
UI | `24`
COUNT_0 | `25`


### `LevelEvent`
Name | Value
-|-
Undefined_4 | `0`
SoundClick | `1000`
SoundClickFail | `1001`
SoundLaunch | `1002`
SoundOpenDoor | `1003`
SoundFizz | `1004`
SoundFuse | `1005`
SoundPlayRecording | `1006`
SoundGhastWarning | `1007`
SoundGhastFireball | `1008`
SoundBlazeFireball | `1009`
SoundZombieWoodenDoor | `1010`
SoundZombieDoorCrash | `1012`
SoundZombieInfected | `1016`
SoundZombieConverted | `1017`
SoundEndermanTeleport | `1018`
SoundAnvilBroken | `1020`
SoundAnvilUsed | `1021`
SoundAnvilLand | `1022`
SoundInfinityArrowPickup | `1030`
SoundTeleportEnderPearl | `1032`
SoundAddItem | `1040`
SoundItemFrameBreak | `1041`
SoundItemFramePlace | `1042`
SoundItemFrameRemoveItem | `1043`
SoundItemFrameRotateItem | `1044`
SoundExperienceOrbPickup | `1051`
SoundTotemUsed | `1052`
SoundArmorStandBreak | `1060`
SoundArmorStandHit | `1061`
SoundArmorStandLand | `1062`
SoundArmorStandPlace | `1063`
ParticlesShoot | `2000`
ParticlesDestroyBlock | `2001`
ParticlesPotionSplash | `2002`
ParticlesEyeOfEnderDeath | `2003`
ParticlesMobBlockSpawn | `2004`
ParticleCropGrowth | `2005`
ParticleSoundGuardianGhost | `2006`
ParticleDeathSmoke | `2007`
ParticleDenyBlock | `2008`
ParticleGenericSpawn | `2009`
ParticlesDragonEgg | `2010`
ParticlesCropEaten | `2011`
ParticlesCrit | `2012`
ParticlesTeleport | `2013`
ParticlesCrackBlock | `2014`
ParticlesBubble | `2015`
ParticlesEvaporate | `2016`
ParticlesDestroyArmorStand | `2017`
ParticlesBreakingEgg | `2018`
ParticleDestroyEgg | `2019`
ParticlesEvaporateWater | `2020`
ParticlesDestroyBlockNoSound | `2021`
ParticlesKnockbackRoar | `2022`
ParticlesTeleportTrail | `2023`
ParticlesPointCloud | `2024`
ParticlesExplosion | `2025`
ParticlesBlockExplosion | `2026`
StartRaining | `3001`
StartThunderstorm | `3002`
StopRaining | `3003`
StopThunderstorm | `3004`
GlobalPause | `3005`
SimTimeStep | `3006`
SimTimeScale | `3007`
ActivateBlock | `3500`
CauldronExplode | `3501`
CauldronDyeArmor | `3502`
CauldronCleanArmor | `3503`
CauldronFillPotion | `3504`
CauldronTakePotion | `3505`
CauldronFillWater | `3506`
CauldronTakeWater | `3507`
CauldronAddDye | `3508`
CauldronCleanBanner | `3509`
CauldronFlush | `3510`
AgentSpawnEffect | `3511`
CauldronFillLava | `3512`
CauldronTakeLava | `3513`
StartBlockCracking | `3600`
StopBlockCracking | `3601`
UpdateBlockCracking | `3602`
AllPlayersSleeping | `9800`
JumpPrevented | `9810`
ParticleLegacyEvent | `16384`


### `LevelSoundEvent`
Name | Value
-|-
ItemUseOn | `0`
Hit | `1`
Step | `2`
Fly | `3`
Jump | `4`
Break | `5`
Place | `6`
HeavyStep | `7`
Gallop | `8`
Fall | `9`
Ambient_0 | `10`
AmbientBaby | `11`
AmbientInWater | `12`
Breathe | `13`
Death | `14`
DeathInWater | `15`
DeathToZombie | `16`
Hurt | `17`
HurtInWater | `18`
Mad | `19`
Boost | `20`
Bow_0 | `21`
SquishBig | `22`
SquishSmall | `23`
FallBig | `24`
FallSmall | `25`
Splash | `26`
Fizz | `27`
Flap | `28`
Swim | `29`
Drink_0 | `30`
Eat_0 | `31`
Takeoff | `32`
Shake | `33`
Plop | `34`
Land | `35`
Saddle | `36`
Armor | `37`
ArmorPlace | `38`
AddChest | `39`
Throw | `40`
Attack | `41`
AttackNoDamage | `42`
AttackStrong | `43`
Warn | `44`
Shear | `45`
Milk | `46`
Thunder | `47`
Explode_0 | `48`
Fire | `49`
Ignite | `50`
Fuse | `51`
Stare | `52`
Spawn | `53`
Shoot | `54`
BreakBlock | `55`
Launch | `56`
Blast | `57`
LargeBlast | `58`
Twinkle | `59`
Remedy | `60`
Unfect | `61`
LevelUp | `62`
BowHit | `63`
BulletHit | `64`
ExtinguishFire | `65`
ItemFizz | `66`
ChestOpen | `67`
ChestClosed | `68`
ShulkerBoxOpen | `69`
ShulkerBoxClosed | `70`
EnderChestOpen | `71`
EnderChestClosed | `72`
PowerOn | `73`
PowerOff | `74`
Attach | `75`
Detach | `76`
Deny | `77`
Tripod | `78`
Pop | `79`
DropSlot | `80`
Note_0 | `81`
Thorns | `82`
PistonIn | `83`
PistonOut | `84`
Portal_0 | `85`
Water | `86`
LavaPop | `87`
Lava_0 | `88`
Burp | `89`
BucketFillWater | `90`
BucketFillLava | `91`
BucketEmptyWater | `92`
BucketEmptyLava | `93`
EquipChain | `94`
EquipDiamond | `95`
EquipGeneric | `96`
EquipGold | `97`
EquipIron | `98`
EquipLeather | `99`
EquipElytra | `100`
Record13 | `101`
RecordCat | `102`
RecordBlocks | `103`
RecordChirp | `104`
RecordFar | `105`
RecordMall | `106`
RecordMellohi | `107`
RecordStal | `108`
RecordStrad | `109`
RecordWard | `110`
Record11 | `111`
RecordWait | `112`
RecordNull | `113`
Flop | `114`
GuardianCurse | `115`
MobWarning | `116`
MobWarningBaby | `117`
Teleport_0 | `118`
ShulkerOpen | `119`
ShulkerClose | `120`
Haggle | `121`
HaggleYes | `122`
HaggleNo | `123`
HaggleIdle | `124`
ChorusGrow | `125`
ChorusDeath | `126`
Glass | `127`
PotionBrewed | `128`
CastSpell | `129`
PrepareAttackSpell | `130`
PrepareSummon | `131`
PrepareWololo | `132`
Fang | `133`
Charge | `134`
TakePicture | `135`
PlaceLeashKnot | `136`
BreakLeashKnot | `137`
AmbientGrowl | `138`
AmbientWhine | `139`
AmbientPant | `140`
AmbientPurr | `141`
AmbientPurreow | `142`
DeathMinVolume | `143`
DeathMidVolume | `144`
ImitateBlaze | `145`
ImitateCaveSpider | `146`
ImitateCreeper | `147`
ImitateElderGuardian | `148`
ImitateEnderDragon | `149`
ImitateEnderman | `150`
ImitateEndermite | `151`
ImitateEvocationIllager | `152`
ImitateGhast | `153`
ImitateHusk | `154`
ImitateIllusionIllager | `155`
ImitateMagmaCube | `156`
ImitatePolarBear | `157`
ImitateShulker | `158`
ImitateSilverfish | `159`
ImitateSkeleton | `160`
ImitateSlime | `161`
ImitateSpider | `162`
ImitateStray | `163`
ImitateVex | `164`
ImitateVindicationIllager | `165`
ImitateWitch | `166`
ImitateWither | `167`
ImitateWitherSkeleton | `168`
ImitateWolf | `169`
ImitateZombie | `170`
ImitateZombiePigman | `171`
ImitateZombieVillager | `172`
EnderEyePlaced | `173`
EndPortalCreated | `174`
AnvilUse | `175`
BottleDragonBreath | `176`
PortalTravel | `177`
TridentHit | `178`
TridentReturn | `179`
TridentRiptide_1 | `180`
TridentRiptide_2 | `181`
TridentRiptide_3 | `182`
TridentThrow | `183`
TridentThunder | `184`
TridentHitGround | `185`
Default_4 | `186`
FletchingTableUse | `187`
ElemConstructOpen | `188`
IceBombHit | `189`
BalloonPop | `190`
LTReactionIceBomb | `191`
LTReactionBleach | `192`
LTReactionElephantToothpaste | `193`
LTReactionElephantToothpaste2 | `194`
LTReactionGlowStick | `195`
LTReactionGlowStick2 | `196`
LTReactionLuminol | `197`
LTReactionSalt | `198`
LTReactionFertilizer | `199`
LTReactionFireball | `200`
LTReactionMagnesiumSalt | `201`
LTReactionMiscFire | `202`
LTReactionFire | `203`
LTReactionMiscExplosion | `204`
LTReactionMiscMystical | `205`
LTReactionMiscMystical2 | `206`
LTReactionProduct | `207`
SparklerUse | `208`
GlowStickUse | `209`
SparklerActive | `210`
ConvertToDrowned | `211`
BucketFillFish | `212`
BucketEmptyFish | `213`
BubbleColumnUpwards | `214`
BubbleColumnDownwards | `215`
BubblePop | `216`
BubbleUpInside | `217`
BubbleDownInside | `218`
HurtBaby | `219`
DeathBaby | `220`
StepBaby | `221`
SpawnBaby | `222`
Born | `223`
TurtleEggBreak | `224`
TurtleEggCrack | `225`
TurtleEggHatched | `226`
LayEgg | `227`
TurtleEggAttacked | `228`
BeaconActivate | `229`
BeaconAmbient | `230`
BeaconDeactivate | `231`
BeaconPower | `232`
ConduitActivate | `233`
ConduitAmbient | `234`
ConduitAttack | `235`
ConduitDeactivate | `236`
ConduitShort | `237`
Swoop | `238`
BambooSaplingPlace | `239`
PreSneeze | `240`
Sneeze_0 | `241`
AmbientTame | `242`
Scared | `243`
ScaffoldingClimb | `244`
CrossbowLoadingStart | `245`
CrossbowLoadingMiddle | `246`
CrossbowLoadingEnd | `247`
CrossbowShoot | `248`
CrossbowQuickChargeStart | `249`
CrossbowQuickChargeMiddle | `250`
CrossbowQuickChargeEnd | `251`
AmbientAggressive | `252`
AmbientWorried | `253`
CantBreed | `254`
ShieldBlock | `255`
LecternBookPlace | `256`
GrindstoneUse | `257`
Bell | `258`
CampfireCrackle | `259`
Roar | `260`
Stun | `261`
SweetBerryBushHurt | `262`
SweetBerryBushPick | `263`
CartographyTableUse | `264`
StonecutterUse | `265`
ComposterEmpty | `266`
ComposterFill | `267`
ComposterFillLayer | `268`
ComposterReady | `269`
BarrelOpen | `270`
BarrelClose | `271`
RaidHorn | `272`
LoomUse | `273`
AmbientInRaid | `274`
UICartographyTableUse | `275`
UIStonecutterUse | `276`
UILoomUse | `277`
SmokerUse | `278`
BlastFurnaceUse | `279`
SmithingTableUse | `280`
Screech | `281`
Sleep | `282`
FurnaceUse | `283`
MooshroomConvert | `284`
MilkSuspiciously | `285`
Celebrate | `286`
JumpPrevent | `287`
AmbientPollinate | `288`
BeehiveDrip | `289`
BeehiveEnter | `290`
BeehiveExit | `291`
BeehiveWork | `292`
BeehiveShear | `293`
HoneybottleDrink | `294`
Undefined_5 | `295`


### `LegacyForestFoliageFeature::Type`
Name | Value
-|-
Flower | `0`
Normal_2 | `1`
Roofed | `2`


### `LegacyTreeFeature::Type`
Name | Value
-|-
BambooJungle | `0`
BirchForest | `1`
BirchForestMutated | `2`
ExtremeHillsPlusTrees | `3`
FlowerForest | `4`
Forest | `5`
Ice | `6`
Jungle_1 | `7`
JungleEdge | `8`
MesaForest | `9`
Plains | `10`
Savanna | `11`
SavannaMutated | `12`
Taiga | `13`
TaigaMega | `14`
TaigaMegaSpruce | `15`


### `LayerValues::Terrain`
Name | Value
-|-
Ocean | `0`
Land_0 | `1`
SpecialLand_1 | `2`
SpecialLand_2 | `3`
SpecialLand_3 | `4`
SpecialLand_4 | `5`
SpecialLand_5 | `6`
SpecialLand_6 | `7`
SpecialLand_7 | `8`
SpecialLand_8 | `9`
SpecialLand_9 | `10`
SpecialLand_10 | `11`
SpecialLand_11 | `12`
SpecialLand_12 | `13`
SpecialLand_13 | `14`
SpecialLand_14 | `15`
SpecialLand_15 | `16`
SpecialLand_16 | `17`


### `LevelChunkFormat`
Name | Value
-|-
v9_00 | `0`
v9_02 | `1`
v9_05 | `2`
v17_0 | `3`
v18_0 | `4`
vConsole1_to_v18_0 | `5`
v1_2_0 | `6`
v1_2_0_bis | `7`
v1_3_0 | `8`
v1_8_0 | `9`
v1_9_0 | `10`
v1_10_0 | `11`
v1_11_0 | `12`
v1_11_1 | `13`
v1_11_2 | `14`
v1_12_0 | `15`
v1_14_0 | `16`
Count_3 | `17`


### `LevelChunk::Finalization`
Name | Value
-|-
NeedsInstaticking | `0`
NeedsPopulation | `1`
Done | `2`


### `LoadingState`
Name | Value
-|-


### `Localization::appendTranslations::LangLineState`
Name | Value
-|-
LeadingWhitespace | `0`
Key | `1`
Value_0 | `2`
PostValueWhitespaceOrComment | `3`


### `LabTableReactionType`
Name | Value
-|-
None_28 | `0`
IceBomb_0 | `1`
Bleach_0 | `2`
ElephantToothpaste | `3`
Fertilizer | `4`
HeatBlock | `5`
MagnesiumSalts | `6`
MiscFire | `7`
MiscExplosion | `8`
MiscLava | `9`
MiscMystical | `10`
MiscSmoke | `11`
MiscLargeSmoke | `12`


### `LabTablePacket::Type`
Name | Value
-|-
StartCombine | `0`
StartReaction | `1`
Reset | `2`


### `LogLevel`
Name | Value
-|-
Verbose | `0`
Inform | `1`
Warning | `2`
Error | `3`
COUNT | `4`


### `LeafSize`
Name | Value
-|-
NoLeaves | `0`
SmallLeaves | `1`
LargeLeaves | `2`
_count_47 | `3`


### `LeverDirection`
Name | Value
-|-
DownEastWest | `0`
East_1 | `1`
West_1 | `2`
South_1 | `3`
North_1 | `4`
UpNorthSouth | `5`
UpEastWest | `6`
DownNorthSouth | `7`
_count_50 | `8`


### `LevelChunkDataField`
Name | Value
-|-
BiomeState | `0`
BlockEntity | `1`
Entity_0 | `2`
PendingTicks | `3`
BorderBlocks | `4`
RandomTicks | `5`
_count_9 | `6`


### `LevelChunk::Tag`
Name | Value
-|-
Data2D | `45`
Data2DLegacy | `46`
SubChunkPrefix | `47`
LegacyTerrain | `48`
BlockEntity_1 | `49`
Entity_6 | `50`
PendingTicks_0 | `51`
LegacyBlockExtraData | `52`
BiomeState_0 | `53`
FinalizedState | `54`
ConversionData | `55`
BorderBlocks_0 | `56`
HardcodedSpawners | `57`
RandomTicks_0 | `58`
Version | `118`


### `LimboEntitiesVersion`
Name | Value
-|-
v0 | `0`
v1_8_0_0 | `1`
v1_10_0_0 | `2`
v1_12_0_0 | `3`


### `LegacyFlowerFeature::Type`
Name | Value
-|-
FlowerForest_0 | `0`
Forest_0 | `1`
Overworld_0 | `2`
Plains_0 | `3`
Swamp | `4`


### `leveldb::FileType`
Name | Value
-|-
kLogFile | `0`
kDBLockFile | `1`
kTableFile | `2`
kDescriptorFile | `3`
kCurrentFile | `4`
kTempFile | `5`
kInfoLogFile | `6`


### `leveldb::ValueType`
Name | Value
-|-
kTypeDeletion | `0`
kTypeValue | `1`


### `leveldb::log::RecordType`
Name | Value
-|-
kZeroType | `0`
kFullType | `1`
kFirstType | `2`
kMiddleType | `3`
kLastType | `4`


### `leveldb::`anonymous namespace'::SaverState`
Name | Value
-|-
kNotFound_0 | `0`
kFound | `1`
kDeleted | `2`
kCorrupt | `3`


### `leveldb::Status::Code`
Name | Value
-|-
kOk | `0`
kNotFound | `1`
kCorruption | `2`
kNotSupported | `3`
kInvalidArgument | `4`
kIOError | `5`


### `LogAreaID`
Name | Value
-|-
LOG_AREA_ALL | `0`
LOG_AREA_PLATFORM | `1`
LOG_AREA_ENTITY | `2`
LOG_AREA_DATABASE | `3`
LOG_AREA_GUI | `4`
LOG_AREA_SYSTEM | `5`
LOG_AREA_NETWORK | `6`
LOG_AREA_RENDER | `7`
LOG_AREA_MEMORY | `8`
LOG_AREA_ANIMATION | `9`
LOG_AREA_INPUT | `10`
LOG_AREA_LEVEL | `11`
LOG_AREA_SERVER | `12`
LOG_AREA_DLC | `13`
LOG_AREA_PHYSICS | `14`
LOG_AREA_FILE | `15`
LOG_AREA_STORAGE | `16`
LOG_AREA_REALMS | `17`
LOG_AREA_REALMSAPI | `18`
LOG_AREA_XBOXLIVE | `19`
LOG_AREA_USERMANAGER | `20`
LOG_AREA_XSAPI | `21`
LOG_AREA_PERF | `22`
LOG_AREA_TELEMETRY | `23`
LOG_AREA_BLOCKS | `24`
LOG_AREA_RAKNET | `25`
LOG_AREA_GAMEFACE | `26`
LOG_AREA_SOUND | `27`
LOG_AREA_INTERACTIVE | `28`
LOG_AREA_SCRIPTING | `29`
LOG_AREA_PLAYFAB | `30`
LOG_AREA_AUTOMATION | `31`
LOG_AREA_PERSONA | `32`
LOG_AREA_UNKNOWN | `33`
NUM_LOG_AREAS | `34`


### `ListDCommand::DetailMode`
Name | Value
-|-
None_55 | `0`
IDs | `1`
UUIDs | `2`
Stats | `3`


### `LayerZooms::Alignment`
```
enum LayerZooms::Alignment : __int32
{
  Min = 0x0,
  Center = 0x1,
  Max = 0x2,
};

```

### `leveldb::`anonymous namespace'::DBIter::Direction`
```
enum leveldb::`anonymous namespace'::DBIter::Direction : __int32
{
  kForward = 0x0,
  kReverse = 0x1,
};

```

### `leveldb::log::Reader::$AB82ADE143F7E099F3CEE06752A0B29A`
```
enum leveldb::log::Reader::$AB82ADE143F7E099F3CEE06752A0B29A : __int32
{
  kEof = 0x5,
  kBadRecord = 0x6,
};

```

### `leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::$F70F27D7DE0A57450B6C283C12496029`
```
enum leveldb::SkipList<const char *,leveldb::MemTable::KeyComparator>::$F70F27D7DE0A57450B6C283C12496029 : __int32
{
  kMaxHeight = 0xC,
};

```

### `leveldb::Tag`
```
enum leveldb::Tag : __int32
{
  kComparator = 0x1,
  kLogNumber = 0x2,
  kNextFileNumber = 0x3,
  kLastSequence = 0x4,
  kCompactPointer = 0x5,
  kDeletedFile = 0x6,
  kNewFile = 0x7,
  kPrevLogNumber = 0x9,
};

```

### `leveldb::BlockHandle::$8E92D724D74F761461F2ECB04E54AD74`
```
enum leveldb::BlockHandle::$8E92D724D74F761461F2ECB04E54AD74 : __int32
{
  kMaxEncodedLength = 0x14,
};

```

### `leveldb::Footer::$89A4D2881D4C3D9D0BE217C870335970`
```
enum leveldb::Footer::$89A4D2881D4C3D9D0BE217C870335970 : __int32
{
  kEncodedLength = 0x30,
};

```

### `leveldb::`anonymous namespace'::MergingIterator::Direction`
```
enum leveldb::`anonymous namespace'::MergingIterator::Direction : __int32
{
  kForward_0 = 0x0,
  kReverse_0 = 0x1,
};

```

