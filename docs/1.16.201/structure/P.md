# P
### `PromotionItem`
Offset | Type | Name
-|-|-|-
0 | (8) `const StoreCatalogItem *` | mCatalogItem
8 | (36) `tm` | mDate
44 | (1) `bool` | mIsWorld


### `ProfilerLite::ScopedData`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mName
8 | (4) `_BYTE[4]` | mScope
12 | (4) `_BYTE[4]` | mBaseScope
16 | (8) `ProfilerLite::ScopedData *` | mParent
24 | (4) `int` | mTabCount
32 | (24) `std::vector<ProfilerLite::ScopedData *>` | mChildren
56 | (4) `int` | mHitCount
64 | (8) `long double` | mTotalTime
72 | (8) `long double` | mTotalInclusiveTime
80 | (8) `long double` | mMaxTimePerLoop


### `PingedCompatibleServer`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | worldName
64 | (4) `GameType` | gameType
68 | (4) `int` | protocol
72 | (32) `std::string` | version
104 | (4) `int` | players
108 | (4) `int` | maxPlayers
112 | (32) `std::string` | originalAddress
144 | (136) `RakNet::SystemAddress` | address
280 | (4) `unsigned int` | pingTime
284 | (4) `float` | pingLatency
288 | (16) `RakNet::RakNetGUID` | hostGuid


### `PackManagerContentSource::repopulateReports::__l2::<lambda_337d7aae86f31fb18650be877a88b9d8>`
Offset | Type | Name
-|-|-|-


### `PackManagerContentSource::getSortedSelectedContent::__l2::<lambda_652fef03625f9a78b56bfe609d670c34>`
Offset | Type | Name
-|-|-|-


### `PackManagerContentSource::save::__l6::<lambda_ae6c280b23486c64081274d9f2bdbc9d>`
Offset | Type | Name
-|-|-|-


### `Pack::findBestPackMatchForPackIdVersion::__l2::<lambda_4d53c0240e5e0df9199466a39d524e5a>`
Offset | Type | Name
-|-|-|-


### `PlayScreenModel::updateNetworkWorldSorting::__l5::<lambda_1672d07fe5d156b3dc1ebf6bd11eaad8>`
Offset | Type | Name
-|-|-|-


### `PlayScreenModel::_populateNetworkWorlds::__l2::<lambda_91707d2b3e5424cd8b21495881c74abd>`
Offset | Type | Name
-|-|-|-


### `PlayScreenModel::_populateNetworkWorlds::__l2::<lambda_b9ddb615a14c453c5a1781ad05d43070>`
Offset | Type | Name
-|-|-|-


### `PlayerAchievementData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mAchievementsUnlocked
4 | (4) `int` | mMaxAchievements
8 | (4) `int` | mTimePlayed
12 | (4) `int` | mCurrGamerScore
16 | (4) `int` | mMaxGamerScore
24 | (24) `std::vector<AchievementData>` | mAchievementData


### `personaScreen::PersonaScreenContext`
Offset | Type | Name
-|-|-|-
0 | (4) `personaScreen::NavigateToPersonaFrom` | mNavigatedFrom


### `ParticleSystem::ParticleAppearanceTintingComponent::_parseGradientBlock::__l16::<lambda_fa2dbc4ac937d455d7eeece644aa1252>`
Offset | Type | Name
-|-|-|-


### `ParticleSystem::_extractNodeParseData::__l5::<lambda_72a7caeb89192be025a5a79dbdf13bc2>`
Offset | Type | Name
-|-|-|-


### `ParticleSystem::ParticleMotionCollisionComponent::_processSweepList::__l2::<lambda_7bae63051b9a62f39823770b1b66d941>`
Offset | Type | Name
-|-|-|-


### `ParticleSystem::ParticleEffect::_sortEffectComponentsForExecutionOrder::__l2::<lambda_05527d0929d9b57df2fc474f5615a770>`
Offset | Type | Name
-|-|-|-


### `PackIdVersion`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mId
16 | (112) `SemVersion` | mVersion
128 | (1) `_BYTE[1]` | mPackType


### `PacketHandlerDispatcherInstance<ActorEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ActorPickRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AddBehaviorTreePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AddPaintingPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AdventureSettingsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AnimateEntityPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AnimatePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AnvilDamagePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AutomationClientConnectPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AvailableActorIdentifiersPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<AvailableCommandsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BiomeDefinitionListPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockActorDataPacket,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockPickRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BookEditPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<BossEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CameraPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CameraShakePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeDimensionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeModelBindPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeModelOffsetPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeModelPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeModelTexturePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ChunkRadiusUpdatedPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientboundMapItemDataPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CodeBuilderPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CombinePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandBlockUpdatePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandOutputPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CompletedUsingItemPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ConfirmSkinPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerClosePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerOpenPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerSetDataPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CorrectPlayerMovePredictionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CraftingDataPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CraftingEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CreativeContentPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<CustomPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<DebugInfoPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<EducationSettingsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<EmoteListPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<EmotePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<EventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<FilterTextPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<GameRulesChangedPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<GuiDataPickItemPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<HungerAttrPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<HurtArmorPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<InteractPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<InventoryContentPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<InventorySlotPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<InventoryTransactionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ItemComponentPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ItemFrameDropItemPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ItemStackRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ItemStackResponsePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<LabTablePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<LecternUpdatePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelChunkPacket,1>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MapCreateLockedCopyPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MapInfoRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MobArmorEquipmentPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MobEffectPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MobEquipmentPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ModalFormRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ModalFormResponsePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MotionPredictionHintsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<MultiplayerSettingsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkChunkPublisherUpdatePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkSettingsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkStackLatencyPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<NpcRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<OnScreenTextureAnimationPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PacketViolationWarningPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PhotoTransferPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlaySoundPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerActionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerArmorDamagePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerAuthInputPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerEnchantOptionsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerFogPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerHotbarPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerInputPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerListPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerSkinPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<PurchaseReceiptPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<RemoveObjectivePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<RequestChunkRadiusPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackChunkDataPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackChunkRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackDataInfoPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackStackPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ScriptCustomEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ServerSettingsRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ServerSettingsResponsePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorDataPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorLinkPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorMotionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetCommandsEnabledPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDefaultGameTypePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDifficultyPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDisplayObjectivePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetHealthPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetLastHurtByPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetLocalPlayerAsInitializedPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetPlayerGameTypePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetScorePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetScoreboardIdentityPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetSpawnPositionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SetTitlePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SettingsCommandPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowCreditsPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowProfilePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowStoreOfferPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SimpleEventPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SpawnExperienceOrbPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<StopSoundPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<StoreBuySuccPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureBlockUpdatePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureTemplateDataRequestPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureTemplateDataResponsePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<SubClientLoginPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<TickSyncPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<TransferPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<TransportNoCompressPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<TransportPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateAttributesPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateEquipPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdatePlayerGameTypePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateSoftEnumPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateTradePacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<VConnectionPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PacketHandlerDispatcherInstance<WithdrawFurnaceXpPacket,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `IPacketHandlerDispatcher` | baseclass_0


### `PackManifest::CapabilityRegisterer`
Offset | Type | Name
-|-|-|-


### `PackManifest::CapabilityRegistry`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_0
16 | (64) `std::unordered_map<std::string,std::function<bool __cdecl(PackManifest &,PackReport &,bool)>>` | mTrustedCapabilities
80 | (64) `std::unordered_map<std::string,std::function<bool __cdecl(PackManifest &,PackReport &,bool)>>` | mCapabilities


### `Pack::findBestPackMatchForPackIdVersion::__l2::<lambda_bd0e0325e88bc51d1e177e0241bc2b0f>`
Offset | Type | Name
-|-|-|-


### `Pack::findBestPackMatchForPackIdVersion::__l2::<lambda_8031843fcdefed2514241fd882f3d70f>`
Offset | Type | Name
-|-|-|-


### `PrecompiledCommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (24) `CommandOrigin` | baseclass_0


### `PerfContextTracker`
Offset | Type | Name
-|-|-|-
0 | (80) `std::mutex` | mInternalLock
80 | (1) `bool` | mActive
88 | (32) `std::string` | mActiveContext
120 | (32) `PerfContextTracker::Timer` | mContextTimer
152 | (96) `std::array<PerfContextTracker::Duration,6>` | mEventDurations
248 | (104) `PerfContextTrackerReport` | mReport
352 | (4) `unsigned int` | mClientCount
356 | (4) `unsigned int` | mRenderDistance
360 | (4) `unsigned int` | mSimDistance


### `PerfContextTracker::Timer`
Offset | Type | Name
-|-|-|-
0 | (16) `PerfContextTracker::Duration` | baseclass_0
16 | (1) `bool` | mRunning
24 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mStart


### `PerfContextTracker::Duration`
Offset | Type | Name
-|-|-|-
0 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | mDuration
8 | (8) `unsigned __int64` | mCount


### `PerfContextTrackerReport`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mContext
32 | (4) `float` | mContextSeconds
40 | (8) `long double` | mAppUptimeSeconds
48 | (8) `unsigned __int64` | mUsedMemoryKB
56 | (8) `unsigned __int64` | mMaxMemoryKB
64 | (4) `float` | mAvgFPS
68 | (4) `unsigned int` | mClientCount
72 | (4) `unsigned int` | mRenderDistance
76 | (4) `unsigned int` | mSimDistance
80 | (24) `std::array<float,6>` | mEventAvgMS


### `PistonBlockActor::_sortAttachedBlocks::__l2::<lambda_9b8dda18c825c80ce3baffb224a5ea51>`
Offset | Type | Name
-|-|-|-
0 | (8) `Vec3 *` | pistonDirection


### `PerlinSimplexNoise`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mLevels
8 | (24) `std::vector<SimplexNoise>` | mNoiseLevels
32 | (4) `float` | mNormalizationFactor


### `PreferredPathDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (4) `float` | mDefaultBlockCost
12 | (4) `float` | mJumpCost
16 | (4) `int` | mMaxFallBlocks
24 | (24) `std::vector<BlockSet>` | mPreferredPathGroup


### `png_xy`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | redx
4 | (4) `int` | redy
8 | (4) `int` | greenx
12 | (4) `int` | greeny
16 | (4) `int` | bluex
20 | (4) `int` | bluey
24 | (4) `int` | whitex
28 | (4) `int` | whitey


### `PFR_ExtraItemRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | type
8 | (8) `int (__fastcall *)(unsigned __int8 *, unsigned __int8 *, void *)` | parser


### `PSAux_ServiceRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `const PS_Table_FuncsRec_ *` | ps_table_funcs
8 | (8) `const PS_Parser_FuncsRec_ *` | ps_parser_funcs
16 | (8) `const T1_Builder_FuncsRec_ *` | t1_builder_funcs
24 | (8) `const T1_Decoder_FuncsRec_ *` | t1_decoder_funcs
32 | (8) `void (__fastcall *)(unsigned __int8 *, unsigned __int64, unsigned __int16)` | t1_decrypt
40 | (8) `unsigned int (__fastcall *)(unsigned int)` | cff_random
48 | (8) `void (__fastcall *)(PS_Decoder_ *, void *, unsigned __int8)` | ps_decoder_init
56 | (8) `void (__fastcall *)(FT_FaceRec_ *, PS_PrivateRec_ *, CFF_SubFontRec_ *)` | t1_make_subfont
64 | (8) `const T1_CMap_ClassesRec_ *` | t1_cmap_classes
72 | (8) `const AFM_Parser_FuncsRec_ *` | afm_parser_funcs
80 | (8) `const CFF_Decoder_FuncsRec_ *` | cff_decoder_funcs


### `PSHinter_Interface_`
Offset | Type | Name
-|-|-|-
0 | (8) `PSH_Globals_FuncsRec_ *(__fastcall *)(FT_ModuleRec_ *)` | get_globals_funcs
8 | (8) `const T1_Hints_FuncsRec_ *(__fastcall *)(FT_ModuleRec_ *)` | get_t1_funcs
16 | (8) `const T2_Hints_FuncsRec_ *(__fastcall *)(FT_ModuleRec_ *)` | get_t2_funcs


### `PS_Parser_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(PS_ParserRec_ *, unsigned __int8 *, unsigned __int8 *, FT_MemoryRec_ *)` | init
8 | (8) `void (__fastcall *)(PS_ParserRec_ *)` | done
16 | (8) `void (__fastcall *)(PS_ParserRec_ *)` | skip_spaces
24 | (8) `void (__fastcall *)(PS_ParserRec_ *)` | skip_PS_token
32 | (8) `int (__fastcall *)(PS_ParserRec_ *)` | to_int
40 | (8) `int (__fastcall *)(PS_ParserRec_ *, int)` | to_fixed
48 | (8) `int (__fastcall *)(PS_ParserRec_ *, unsigned __int8 *, unsigned __int64, unsigned int *, unsigned __int8)` | to_bytes
56 | (8) `int (__fastcall *)(PS_ParserRec_ *, int, __int16 *)` | to_coord_array
64 | (8) `int (__fastcall *)(PS_ParserRec_ *, int, int *, int)` | to_fixed_array
72 | (8) `void (__fastcall *)(PS_ParserRec_ *, T1_TokenRec_ *)` | to_token
80 | (8) `void (__fastcall *)(PS_ParserRec_ *, T1_TokenRec_ *, unsigned int, int *)` | to_token_array
88 | (8) `int (__fastcall *)(PS_ParserRec_ *, T1_FieldRec_ *const, void **, unsigned int, unsigned int *)` | load_field
96 | (8) `int (__fastcall *)(PS_ParserRec_ *, T1_FieldRec_ *const, void **, unsigned int, unsigned int *)` | load_field_table


### `PropertyBag`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::Value` | mJsonValue
16 | (4) `int` | mChangeVersion


### `PersonaPieceHandle`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mPieceType
8 | (16) `mce::UUID` | mPackId
24 | (32) `std::string` | mPieceId
56 | (32) `std::string` | mPersonaCharacter
88 | (1) `bool` | mDefaultPiece
96 | (32) `std::string` | mProductId
128 | (72) `PersonaPieceHandle::SerializedExcessData` | mSerializedExcessData
200 | (3) `persona::FreeItemState` | mFreeItemState


### `PersonaPieceHandle::SerializedExcessData`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mPieceSide
4 | (64) `TintMapColor` | mTintingData
68 | (1) `bool` | mUseTintColor


### `persona::FreeItemState`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsFreeItem
1 | (1) `bool` | mIsAchievementItem
2 | (1) `bool` | mIsRedeemable


### `persona::PersonaCharacterHandle`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mSkinName
32 | (4) `persona::ProfileType` | mType


### `PS_Builder_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(PS_Builder_ *, void *, unsigned __int8)` | init
8 | (8) `void (__fastcall *)(PS_Builder_ *)` | done


### `param_encode::EByte`
Offset | Type | Name
-|-|-|-
0 | (40) `param_encode::EValue` | baseclass_0
40 | (2) `__int16` | id
48 | (8) `char *` | data0
56 | (8) `char *` | data1
64 | (8) `char *` | data2
72 | (8) `char *` | data3


### `param_encode::EValue`
Offset | Type | Name
-|-|-|-
0 | (8) `param_encode::EValue_vtbl *` | __vftable
8 | (16) `std::shared_ptr<std::mutex>` | m_lock
24 | (16) `std::shared_ptr<std::vector<char *> >` | m_buffer


### `PersonaAppearance`
Offset | Type | Name
-|-|-|-
0 | (8) `PersonaAppearance_vtbl *` | __vftable
8 | (24) `std::vector<PersonaPieceHandle>` | mPieceVector
32 | (24) `std::vector<std::string>` | mUnsupportedPieces
56 | (1248) `std::array<PersonaPieceHandle,6>` | mEmoteWheel
1304 | (1) `bool` | mUseClassicSkin
1305 | (1) `bool` | mAllowUnownedPieces
1312 | (32) `std::string` | mArmSize
1344 | (64) `std::unordered_map<enum persona::PieceType,TintMapColor>` | mPieceTintColors
1408 | (16) `mce::Color` | mSkinColor
1424 | (4) `persona::ProfileType` | mType
1428 | (1) `bool` | mSaveSerializedLockedClassicSkin
1429 | (1) `bool` | mSaveSerializedUseClassicSkin
1430 | (1) `bool` | mSerializedUseClassicSkin
1432 | (32) `std::string` | mSerializedLockedClassicSkin


### `param_encode::EAttributeInstance`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<float>` | ?
8 | (8) `std::unique_ptr<float>` | ?
16 | (8) `std::unique_ptr<float>` | ?
24 | (8) `std::unique_ptr<float>` | ?
32 | (8) `std::unique_ptr<float>` | ?
40 | (8) `std::unique_ptr<float>` | ?


### `PlayerScoreboardId`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | mActorUniqueId


### `PersonaCharacter`
Offset | Type | Name
-|-|-|-
0 | (112) `SkinHandle` | mCurrentSkinHandle
112 | (32) `std::string` | mSkinName
144 | (32) `std::string` | mGeoID
176 | (32) `std::string` | mTextureID
208 | (32) `std::string` | mCapeTextureID
240 | (32) `std::string` | mBodySize
272 | (4) `persona::ProfileType` | mProfileType
276 | (16) `mce::Color` | mSavedSkinColor
296 | (1464) `PersonaAppearance` | mLastSavedAppearance
1760 | (1464) `PersonaAppearance` | mCurrentAppearance
3224 | (4) `int` | mSkinIndex
3228 | (1) `bool` | mWearingCape
3229 | (1) `bool` | mInitialized
3230 | (1) `bool` | mIsUpdating
3232 | (4) `_BYTE[4]` | mStatus
3240 | (64) `std::unordered_map<enum persona::AnimatedTextureType,AnimatedTextureDefinition>` | mAnimatedTextures
3304 | (4) `unsigned int` | mSkinAnimationAdjustments
3308 | (4) `unsigned int` | mLastSavedSkinAnimationAdjustments
3312 | (24) `std::vector<TextureTintCollection>` | mPieceTextures
3336 | (64) `std::unordered_map<std::string,unsigned int>` | mPieceTextureMap
3400 | (16) `std::shared_ptr<mce::Image>` | mPersonaTexture
3416 | (208) `TextureTint` | mSkinComplexion
3624 | (208) `TextureTint` | mFaceSkinComplexion
3832 | (16) `std::shared_ptr<TextureAtlas>` | mTextureAtlas
3848 | (64) `std::unordered_set<ResourceLocation>` | mPieceTexLocations
3912 | (64) `std::unordered_set<std::string>` | mPieceIds


### `PersonaPiece`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPieceId
32 | (16) `mce::UUID` | mPieceIdUUID
48 | (16) `mce::UUID` | mPackId
64 | (4) `_BYTE[4]` | mPieceType
68 | (4) `_BYTE[4]` | mPieceSubType
72 | (1) `bool` | mPlatformLocked
73 | (1) `bool` | mTitleLocked
74 | (1) `bool` | mDefaultPiece
80 | (32) `std::string` | mRelativeLocation
112 | (32) `std::string` | mPieceName
144 | (32) `std::string` | mBodyVariant
176 | (32) `std::string` | mMetaFileName
208 | (32) `std::string` | mThumbnailPath
240 | (16) `Json::Value` | mMetaFileJson
256 | (32) `std::string` | mGeometryFileName
288 | (16) `Json::Value` | mGeometryFileJson
304 | (24) `std::vector<PersonaAnimationDefinition>` | mAnimations
328 | (24) `std::vector<enum persona::PersonaColorOption>` | mPieceColorOptions
352 | (8) `Pack *` | mSourcePack


### `PS_Table_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(PS_TableRec_ *, int, FT_MemoryRec_ *)` | init
8 | (8) `void (__fastcall *)(PS_TableRec_ *)` | done
16 | (8) `int (__fastcall *)(PS_TableRec_ *, int, const void *, unsigned int)` | add
24 | (8) `void (__fastcall *)(PS_TableRec_ *)` | release


### `PredictedMovementComponent::RuntimePredictionData`
Offset | Type | Name
-|-|-|-
0 | (8) `PredictedMovementComponent::RuntimePredictionData_vtbl *` | __vftable
8 | (4) `unsigned int` | mTotalHistoryItems
16 | (8) `unsigned __int64` | mLastDataTickInterval
24 | (8) `unsigned __int64` | mLastMoveDataTickInterval
32 | (8) `unsigned __int64` | mLastMotionDataTickInterval
40 | (4) `float` | mLastMoveTickIntervalMilliseconds
44 | (4) `float` | mLastMotionDataTickIntervalMilliseconds
48 | (16) `std::shared_ptr<PredictedMovementComponent::HistoryItem const >` | mLastMoveData
64 | (16) `std::shared_ptr<PredictedMovementComponent::HistoryItem const >` | mLastMotionData
80 | (32) `unsigned int[8]` | mStats
112 | (8) `PredictedMovementComponent *` | mPredictedMovementComponent


### `ProfilerLite`
Offset | Type | Name
-|-|-|-
0 | (128) `std::array<ProfilerLite::ScopedData *,16>` | mCustomScopeDatas
128 | (88) `ProfilerLite::ScopedData` | mUninitializedScopedData
216 | (32) `Core::PathBuffer<std::string >` | mLogFileName
248 | (296) `Core::OutputFileStream` | mLogFile
544 | (32) `Core::PathBuffer<std::string >` | mScreenLoadLogFileName
576 | (296) `Core::OutputFileStream` | mScreenLoadLogFile
872 | (32) `Core::PathBuffer<std::string >` | mEventLogFileName
904 | (296) `Core::OutputFileStream` | mEventLogFile
1200 | (32) `Core::PathBuffer<std::string >` | mSecondaryLogFileName
1232 | (296) `Core::OutputFileStream` | mSecondaryLogFile
1528 | (32) `Core::PathBuffer<std::string >` | mSecondaryScreenLoadLogFileName
1560 | (296) `Core::OutputFileStream` | mSecondaryScreenLoadLogFile
1856 | (32) `Core::PathBuffer<std::string >` | mSecondaryEventLogFileName
1888 | (296) `Core::OutputFileStream` | mSecondaryEventLogFile
2184 | (8) `long double` | mTime
2192 | (8) `long double` | mStartTime
2200 | (8) `long double` | mNextUpdateTime
2208 | (8) `long double` | mLastUpdateTime
2216 | (8) `long double` | mBenchmarkModeTime
2224 | (1) `bool` | mBenchmarkModeDone
2225 | (1) `bool` | mIsProfilingEnabled
2226 | (1) `bool` | mShouldCheckTreatments
2227 | (1) `bool` | mCanLogToSecondaryFile
2232 | (8) `_ProfilerLiteTimer *` | mActiveScope
2240 | (16) `std::map<std::thread::id,_ProfilerLiteTimer *>` | mThreadedActiveScopes
2256 | (32) `std::string` | mCurrentGamestate
2288 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | mDebugServerTickTime
2296 | (36) `ProfilerLiteTelemetry` | mTelemetry
2336 | (32) `std::string` | mCachedProfileString
2368 | (16) `std::array<unsigned int,4>` | mLastNetworkStatSampleNum
2384 | (8) `unsigned __int64` | mPrevTotalBytesWritten
2392 | (8) `unsigned __int64` | mPrevTotalBytesRead
2400 | (32) `ProfilerLite::RealtimeFrameData` | mFrameData


### `ProfilerLiteTelemetry`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mAvgFps
4 | (4) `float` | mAvgServerSimTickTimeMS
8 | (4) `float` | mAvgClientSimTickTimeMS
12 | (4) `float` | mAvgBeginFrameTimeMS
16 | (4) `float` | mAvgInputTimeMS
20 | (4) `float` | mAvgRenderTimeMS
24 | (4) `float` | mAvgEndFrameTimeMS
28 | (4) `float` | mAvgRemainderTimePercent
32 | (4) `float` | mAvgUnaccountedTimePercent


### `ProfilerLite::RealtimeFrameData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mFrames
4 | (4) `float` | mFPS
8 | (4) `float` | mFrameTime
16 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | mLastFrame
24 | (1) `bool` | mFirstFrame


### `PageContent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mText
32 | (32) `std::string` | mParsedText
64 | (32) `std::string` | mPhotoName


### `PositionTrackingId`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `PlayerMovementSettings`
Offset | Type | Name
-|-|-|-
0 | (1) `ServerAuthMovementMode` | AuthorityMode
1 | (1) `bool` | CorrectionEnabled
4 | (4) `float` | ScoreThreshold
8 | (4) `float` | DistanceThreshold
12 | (4) `float` | DistanceThresholdSqr
16 | (8) `std::chrono::duration<__int64,std::ratio<1,1000> >` | DurationThreshold
24 | (48) `ReplayStateConfig` | mReplay
72 | (16) `PlayerTickConfig` | mPlayerTickConfig
88 | (1) `bool` | ServerAuthBlockBreaking
92 | (4) `float` | mServerPlayerPickRangeScalar


### `PlayerTickConfig`
Offset | Type | Name
-|-|-|-
0 | (1) `PlayerTickConfig::TickPolicy` | mPolicy
1 | (1) `unsigned __int8` | mMaxBatchedTicks
8 | (8) `unsigned __int64` | mMaxTickCredits


### `persona::PersonaSubCategory`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mTitle
32 | (32) `std::string` | mDescription
64 | (32) `std::string` | mImagePath
96 | (32) `std::string` | mSelectedImagePath
128 | (320) `persona::CategoryCollectorInfo` | mMainContentInfo
448 | (320) `persona::CategoryCollectorInfo` | mFeaturedInfo
768 | (1) `bool` | mIsSelected
769 | (1) `bool` | mHasNewOffers
770 | (1) `bool` | mIsPaused


### `persona::CategoryCollectorInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mHeader
32 | (216) `persona::PersonaStoreItemCollector` | mCollector
248 | (64) `std::unordered_map<mce::UUID,StoreCatalogItem *>` | mAchievementOffers
312 | (1) `bool` | mShowDefaultOffers


### `persona::PersonaStoreItemCollector`
Offset | Type | Name
-|-|-|-
0 | (8) `persona::PersonaStoreItemCollector_vtbl *` | __vftable
8 | (24) `std::vector<persona::PersonaStoreItemCollector::QueryInfo>` | mQueries
32 | (24) `std::vector<StoreCatalogItem *>` | mDiscoveredItems
56 | (24) `std::vector<persona::PieceOfferWrapper>` | mPieceOffers
80 | (24) `std::vector<std::shared_ptr<persona::DlcImportTracker>>` | mTrackedImports
104 | (16) `std::shared_ptr<persona::DlcImportTracker>` | mImportWaitingCallback
120 | (16) `std::set<mce::UUID>` | mImportedPacks
136 | (16) `std::set<mce::UUID>` | mDiscoveredOfferIds
152 | (16) `std::shared_ptr<bool>` | mWeakExistence
168 | (16) `std::shared_ptr<persona::PersonaPieceCollectionEventManager>` | mCollectionEventManager
184 | (4) `int` | mVisibleRangeStart
188 | (4) `int` | mVisibleRangeEnd
192 | (4) `int` | mCycleAmount
196 | (4) `int` | mCycleOffset
200 | (8) `unsigned __int64` | mQueryIndex
208 | (4) `persona::OwnershipFilterType` | mOwnershipFilterType
212 | (1) `bool` | mSearchActive
213 | (1) `bool` | mDirty


### `ParticleEffectPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ParticleEffectInfo>` | mParticleEffectInfoPtr


### `persona::PieceOfferWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `const StoreCatalogItem *` | mCatalogOffer
8 | (8) `const PersonaPiece *` | mPersonaPiece


### `persona::PersonaCategory`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mTitle
32 | (32) `std::string` | mDescription
64 | (32) `std::string` | mImagePath
96 | (320) `persona::CategoryCollectorInfo` | mFeaturedInfo
416 | (24) `std::vector<persona::PersonaSubCategory>` | mSubCategories
440 | (1) `bool` | mIsSelected


### `PersonaAnimationDefinition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mAnimationName
32 | (32) `std::string` | mAnimationFile
64 | (16) `Json::Value` | mAnimationFileJson


### `Potion`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mId
8 | (32) `std::string` | mNameId
40 | (32) `std::string` | mPrefix
72 | (24) `std::vector<MobEffectInstance>` | mEffects
96 | (24) `std::vector<std::string>` | mDescriptionIds
120 | (4) `_BYTE[4]` | mVar


### `Packet`
Offset | Type | Name
-|-|-|-
0 | (8) `Packet_vtbl *` | __vftable
8 | (4) `PacketPriority` | mPriority
12 | (4) `NetworkPeer::Reliability` | mReliability
16 | (1) `unsigned __int8` | mClientSubId
17 | (1) `bool` | mIsHandled
24 | (8) `const IPacketHandlerDispatcher *` | mHandler
32 | (4) `Compressibility` | mCompressible


### `PlayerSnapshot`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mGravity
4 | (4) `float` | mLevelGravity
8 | (8) `std::optional<float>` | mWaterSpeed
16 | (4) `std::bitset<27>` | mStateBools
24 | (24) `std::vector<AABB>` | mOnewayPhysicsBlocks
48 | (24) `std::vector<AABB>` | mSubBBs
72 | (24) `std::vector<ActorUniqueID>` | mRiderIDs
96 | (8) `Vec2` | mSlideOffset
104 | (8) `Vec2` | mRot
112 | (8) `Vec2` | mRotPrev
120 | (8) `Vec2` | mCurrentLocalMoveVelocity
128 | (12) `Vec3` | mBlockMovementSlowdownMultiplier
140 | (4) `float` | mSwimAmount
144 | (4) `float` | mYRotA
148 | (4) `float` | mYHeadRot
152 | (4) `float` | mYHeadRotOld
156 | (4) `float` | mSwimSpeedMultiplier
160 | (4) `float` | mFlyingSpeed
164 | (4) `float` | mFrictionModifier
168 | (4) `float` | mVRMoveAdjAngle
172 | (4) `float` | mJumpRidingScale
176 | (8) `std::array<float,2>` | mPaddleForces
184 | (24) `std::vector<MobEffectInstance>` | mMobEffects
208 | (88) `BaseAttributeMap` | mAttributes
296 | (32) `SynchedActorData` | mActorData
328 | (36) `StateVectorComponent` | mStateVectorComponent
364 | (36) `AABBShapeComponent` | mAABBShapeComponent
400 | (2712) `Abilities` | mAbilities
3112 | (5) `AdventureSettings` | mAdventureSettings
3120 | (4) `int` | mNoJumpDelay
3124 | (4) `int` | mJumpTicks
3128 | (4) `int` | mNoActionTime
3132 | (4) `int` | mGlidingTicks
3136 | (12) `Vec3` | mJumpStartPos
3148 | (12) `Vec3` | mLocalMoveVelocity
3160 | (12) `Vec3` | mLastPos
3172 | (12) `Vec3` | mLastDelta


### `param_encode::EBool`
Offset | Type | Name
-|-|-|-
0 | (40) `param_encode::EValue` | baseclass_0
40 | (2) `__int16` | id
48 | (8) `char *` | data0
56 | (8) `char *` | data1
64 | (8) `char *` | data2
72 | (8) `char *` | data3


### `PlayerActionComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `std::bitset<28>` | mPlayerActions
8 | (448) `std::optional<PackedItemUseLegacyInventoryTransaction>` | mItemUseTransaction
456 | (8) `std::unique_ptr<ItemStackRequestData>` | mItemStackRequest
464 | (24) `PlayerBlockActions` | mPlayerBlockActions


### `PackedItemUseLegacyInventoryTransaction`
Offset | Type | Name
-|-|-|-
0 | (4) `TypedClientNetId<ItemStackLegacyRequestIdTag,int,0>` | mID
8 | (24) `std::vector<std::pair<enum ContainerEnumName,std::vector<unsigned char> >>` | mSlots
32 | (408) `ItemUseInventoryTransaction` | mTransaction


### `PlayerBlockActions`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PlayerBlockActionData>` | mActions


### `Pos`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (4) `int` | z


### `PlayScreenModel::navigateToWorldSyncModalScreen::__l2::<lambda_5b1bdbb1f29c7cc64448708ddd70e61f>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (32) `const std::string` | levelId
48 | (64) `std::function<void __cdecl(Core::Result)>` | onCompleteCallback


### `ParticleTrackingSystem::tick::__l5::<lambda_9fa7a61bdfe457f6a795012b6e580c85>`
Offset | Type | Name
-|-|-|-
0 | (8) `ParticleSystemEngine *` | engine


### `PixelCalc`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mPixelsPerMillimeter
4 | (4) `float` | mMillimetersPerPixel


### `PointerLocationEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `InputMode` | inputMode
4 | (2) `__int16` | x
6 | (2) `__int16` | y
8 | (1) `bool` | forceMotionlessPointer


### `PlayerBlockActionData`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mPlayerActionType
4 | (12) `BlockPos` | mPos
16 | (4) `int` | mFacing


### `PerfContextTracker::EventScope`
Offset | Type | Name
-|-|-|-
0 | (8) `_BYTE[8]` | mEventType
8 | (32) `PerfContextTracker::Timer` | mTimer


### `PackInstance`
Offset | Type | Name
-|-|-|-
0 | (432) `PackReport` | mPackReport
432 | (8) `PackSettings *` | mPackSettings
440 | (8) `ResourcePack *` | mPack
448 | (16) `PackStats` | mStats
464 | (4) `int` | mSubpackIndex
472 | (16) `std::weak_ptr<IPackStorage>` | mPackStorage


### `PackReport`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | mLocation
56 | (1) `bool` | mWasUpgraded
57 | (1) `bool` | mAttemptedUpgrade
64 | (24) `std::vector<std::shared_ptr<PackError>>` | mErrors
88 | (24) `std::vector<std::shared_ptr<PackError>>` | mWarnings
112 | (112) `SemVersion` | mRequiredBaseGameVersion
224 | (32) `std::string` | mOriginalName
256 | (32) `std::string` | mOriginalVersion
288 | (136) `PackIdVersion` | mIdentity
424 | (1) `_BYTE[1]` | mPackType


### `PackStats`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mOverriddenEntityCount
4 | (4) `unsigned int` | mCustomEntityCount
8 | (4) `unsigned int` | mCustomAnimationCount
12 | (4) `unsigned int` | mCustomEffectCount


### `PendingScreenshotRequest`
Offset | Type | Name
-|-|-|-
0 | (224) `ScreenshotOptions` | mOptions
224 | (64) `std::function<void __cdecl(Core::PathBuffer<std::string >)>` | mCallback


### `PointerMoveScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | cursorPosition
8 | (8) `float[2]` | deltaPosition


### `PointerHeldScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | position
8 | (8) `float[2]` | relativePosition
16 | (1) `bool` | moved


### `PointerHeldEdge`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(PointerHeldScreenEventData const &,std::string const &,int)>` | mRequirement
64 | (4) `_BYTE[4]` | mTargetNode
68 | (4) `int` | mPriority


### `PlatformStoreIconModel`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mSubClientId
8 | (8) `std::unique_ptr<PlatformStoreIconModel::PlatformStoreIconVisibility>` | mIconVisibility


### `PlayScreenController::_registerBindings::__l2::<lambda_85a8ad764f0e7933a7cfd34d077466ab>`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayScreenController *const` | __this


### `PlayerInventory::SlotData`
Offset | Type | Name
-|-|-|-
0 | (1) `ContainerID` | mContainerId
4 | (4) `int` | mSlot


### `PackDiscoveryError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `PackError`
Offset | Type | Name
-|-|-|-
0 | (8) `PackError_vtbl *` | __vftable
8 | (24) `std::vector<std::string>` | mErrorParameters
32 | (4) `int` | mErrorValue
36 | (4) `_BYTE[4]` | mPackErrorType


### `PlayerListInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPlayerName
32 | (8) `ActorUniqueID` | mId
40 | (16) `mce::UUID` | mUUID
56 | (32) `std::string` | mXUID
88 | (32) `std::string` | mPlatformOnlineId
120 | (32) `std::string` | mVipFormatName
152 | (32) `std::string` | mNameTagName
184 | (4) `unsigned int` | mGrowthLevel
188 | (1) `bool` | mIsOnXBL
189 | (1) `bool` | mIsPlatformIconVisible
190 | (1) `bool` | mIsPlatformProfileCardVisible
191 | (1) `bool` | mHasPlatformGamerpic
192 | (1) `bool` | mAllowGamerPics
200 | (56) `ResourceLocation` | mGamerPicLocation
256 | (8) `const Social::XboxLiveUserProfileData *` | mUser
264 | (1) `bool` | mIsTeacher
265 | (1) `bool` | mIsHost


### `PermissionsScreenController::_registerEventHandlers::__l11::<lambda_7bebacee89ad03baefca936fb00946f8>::()::__l5::<lambda_e19bed6ef6721cd8c8d72df4c9ef2e82>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PermissionsScreenController>` | weakThis
16 | (272) `PlayerListInfo` | selectedPlayerInfo


### `PermissionsScreenController::_setPermissionLevelRealms::__l5::<lambda_c26cca5b4e31faad9e5e4836632d6c70>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PermissionsScreenController>` | weakThis
16 | (272) `PlayerListInfo` | selectedPlayerInfo


### `PersonaScreenController::_revertOrSavePersona::__l2::<lambda_aa432b6c09e50a5595f08013064f446a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<bool>` | weakExistance
16 | (8) `PersonaScreenController *const` | __this
24 | (64) `std::function<void __cdecl(void)>` | cb


### `PersonaScreenController::_revertOrSavePersona::__l2::<lambda_bd60443a777f97abf702ab299a33f4ba>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<bool>` | weakExistance
16 | (8) `PersonaScreenController *const` | __this
24 | (64) `std::function<void __cdecl(void)>` | cb


### `PlayScreenController::_handleLeaveRealm::__l2::<lambda_502388f85e522d9c6bce8473494dad69>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (8) `Realms::RealmId` | worldId


### `PlayScreenController::_startLocalWorld::__l11::<lambda_3acae3efd1e785f91a99c085cf8db20c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (568) `const LocalWorldInfo` | world
584 | (8) `PlayScreenController::_startLocalWorld::__l2::<lambda_8e203efbf34e225efaac2cacba79e4c8>` | startWorldCallback


### `PlayScreenController::_startLocalWorld::__l2::<lambda_8e203efbf34e225efaac2cacba79e4c8>`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayScreenController *const` | __this


### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4c1ee076854f4c52b98eb2d53121b50>`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayScreenController *const` | __this


### `PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l2::<lambda_a157bd2ea0807ff315c63e17e3e505e7>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (32) `const std::string` | collectionName
48 | (4) `int` | index


### `PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l11::<lambda_d34e92e1cd8e92307f5ea4b07ef8fb7b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (64) `std::function<enum ui::ViewRequest __cdecl(void)>` | connectToSelectedThirdPartyServer


### `PlayScreenController::_registerBindings::__l2::<lambda_c2f73915e27e1708fdaf341c0a14446c>`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayScreenController *const` | __this


### `PlayScreenController::_registerBindings::__l5::<lambda_8f6b09fc8bb044637e9ccae013e4c3e4>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64 *` | totalStorageSize


### `PlayScreenController`
Offset | Type | Name
-|-|-|-
0 | (2672) `MainMenuScreenController` | baseclass_0
2672 | (16) `std::shared_ptr<PlayScreenModel>` | mPlayScreenModel
2688 | (8) `std::unique_ptr<DlcUIWrapper>` | mDlcUIWrapper
2696 | (4) `PlayScreenDefaultTab` | mActiveTabIndex
2700 | (1) `bool` | mForceRefreshRealmsOnOpen
2701 | (1) `bool` | mForceRefreshThirdPartyServersOnOpen
2702 | (1) `bool` | mRealmsBindingsDirty
2703 | (1) `bool` | mCheckUGCOnTabChange
2704 | (1) `bool` | mRealmsCompatibilityCheckComplete
2708 | (4) `RealmsAPI::Compatibility` | mRealmsCompatibility
2712 | (1) `bool` | mStorageDropdownActive
2713 | (1) `bool` | mUseTabs
2716 | (4) `unsigned int` | mIconBouncesInProgress
2720 | (1) `bool` | mFriendsIconBouncing
2728 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mBounceCooldownTimer
2736 | (8) `const std::chrono::duration<__int64,std::ratio<1,1> >` | mBounceCooldownTimerDuration
2744 | (1) `bool` | mPlatformRestrictsMultiplayer
2752 | (8) `std::unique_ptr<PlatformMultiplayerRestrictions>` | mPlatformMultiplayerRestrictions
2760 | (32) `std::string` | mInviteCode
2792 | (4) `PlayScreenController::ServerCollectionName` | mCurrentServerCollectionName
2796 | (4) `PlayScreenController::ConvertProgressState` | mProgressScreenState
2800 | (32) `std::string` | mDirtyLevelId
2832 | (1) `bool` | mLayoutDirty
2836 | (4) `int` | mCurrentServerIndex
2840 | (4) `int` | mCurrentScreenshotIndex
2844 | (1) `bool` | mIsDescriptionExpanded
2845 | (1) `bool` | mIsNewsExpanded
2846 | (1) `bool` | mAddServerInfoVisible
2847 | (1) `bool` | mNavigatedToAddServer


### `PlayScreenController::_getLegacyWorldConvertCallback::__l2::<lambda_7826e9c004e3684a81279305594feaf8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (608) `const LegacyWorldInfo` | worldInfo
624 | (32) `const std::string` | levelId


### `PlayScreenController::_onWorldConversionCompleted::__l2::<lambda_811b7a987c7c8d68d8053c7372993a82>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenController>` | weakThis
16 | (32) `const std::string` | levelId
48 | (16) `std::shared_ptr<ImportResult>` | result


### `PurchaseEnabledScreenController::_verifyAppStoreReady::__l10::<lambda_19652c0eb9195c6244670c4762c9adea>::()::__l5::<lambda_49a623e247def4af82a019dba1499aa0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PurchaseEnabledScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | readyCallback


### `PurchaseEnabledScreenController::_promptPrepareAppStore::__l2::<lambda_cb9ae027d0cc494abd24ed13191d6b4a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(void)>` | callback


### `PortfolioScreenController::PhotoRecord`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | path
32 | (32) `std::string` | desc
64 | (4) `_BYTE[4]` | state


### `PortalComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mParticleEastWest
32 | (32) `std::string` | mParticleNorthSouth
64 | (4) `int` | mTargetDimension


### `PackSettingsInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<PackManifest>` | mPackManifest
8 | (24) `SubpackInfoCollection` | mSubpackInfoCollection
32 | (4) `int` | mSubpackIndex
40 | (64) `std::function<void __cdecl(PackSettingsInfo const &)>` | mCallback


### `PackMoveResult`
Offset | Type | Name
-|-|-|-
0 | (4) `PackSelectResult` | mState
8 | (32) `std::string` | mMovedPack


### `PackManifest`
Offset | Type | Name
-|-|-|-
0 | (8) `PackManifest_vtbl *` | __vftable
8 | (56) `ResourceLocation` | mLocation
64 | (136) `PackIdVersion` | mIdentity
200 | (24) `ContentIdentity` | mContentIdentity
224 | (112) `SemVersion` | mMinEngineVersion
336 | (112) `BaseGameVersion` | mRequiredBaseGameVersion
448 | (64) `std::unordered_set<std::string>` | mCapabilities
512 | (64) `std::unordered_set<std::string>` | mTrustedCapabilities
576 | (32) `std::string` | mName
608 | (32) `std::string` | mDescription
640 | (1) `bool` | mExpired
648 | (56) `ResourceLocation` | mPackIconLocation
704 | (24) `std::vector<ResourceInformation>` | mModules
728 | (24) `std::vector<PackIdVersion>` | mPackDependencies
752 | (24) `std::vector<LegacyPackIdVersion>` | mLegacyModuleDependencies
776 | (16) `Json::Value` | mSettings
792 | (88) `ResourceMetadata` | mMetadata
880 | (1) `_BYTE[1]` | mPackType
884 | (4) `PackCategory` | mPackCategory
888 | (4) `PackOrigin` | mPackOrigin
892 | (1) `ManifestOrigin` | mManifestOrigin
893 | (1) `ManifestType` | mManifestType
894 | (1) `bool` | mIsHidden
896 | (8) `unsigned __int64` | mSize
904 | (32) `std::string` | mLastModifiedDate
936 | (1) `bool` | mHasValidUUID
937 | (1) `bool` | mHasPlugins
938 | (1) `bool` | mHasClientData
939 | (1) `bool` | mHasEducationMetadata
940 | (1) `bool` | mIsPlatformLocked
941 | (1) `bool` | mIsTitleLocked
942 | (1) `bool` | mCanUseTrustedPackCapabilities
943 | (1) `_BYTE[1]` | mTemplateOptionLockState
944 | (1) `_BYTE[1]` | mScope
952 | (24) `ContentIdentity` | mSourceIdentity
976 | (24) `std::vector<std::string>` | mLanguageCodesForPackKeywords
1000 | (4) `_BYTE[4]` | mPackRedownloadableState
1004 | (1) `PackManifestFormat` | mFormatVersion
1005 | (1) `PackManifestFormat` | mOriginalFormatVersion


### `PlayerScore`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (4) `int` | mScore


### `PostOperation`
Offset | Type | Name
-|-|-|-
0 | (8) `LayoutComponent *` | mLayout
8 | (8) `VariableRef *` | mVariableRef
16 | (64) `std::function<void __cdecl(void)>` | mOperation


### `PatchNotesSearchResults`
Offset | Type | Name
-|-|-|-
0 | (12) `CommonSearchResults` | baseclass_0
16 | (24) `std::vector<PatchNotesDocument>` | mDocuments


### `PatchNotesDocument`
Offset | Type | Name
-|-|-|-
0 | (584) `CommonDocument` | mCommon
584 | (88) `PatchNotesCustom` | mCustom


### `PatchNotesCustom`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mRevision
32 | (24) `std::vector<std::string>` | mOffers
56 | (32) `std::string` | mShowUpdatePromptDate


### `PackInstanceId`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mPackId
136 | (32) `std::string` | mSubpackName


### `PDFOptions`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Core::PathBuffer<std::string >>` | orderedFilenames
24 | (32) `Core::PathBuffer<std::string >` | destination
56 | (32) `std::string` | title


### `ProductSku`
Offset | Type | Name
-|-|-|-
0 | (32) `NewType<std::string >` | baseclass_0


### `PackSourceReport`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<PackIdVersion,PackReport>` | mReports


### `PackModel`
Offset | Type | Name
-|-|-|-
0 | (8) `const Pack *` | mPack
8 | (32) `std::string` | mDateAvailable
40 | (432) `PackReport` | mPackReport
472 | (1) `bool` | mHasWarnings
476 | (4) `int` | mSubpackIndex


### `persona::SubCategoryDocument`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mTitle
32 | (32) `std::string` | mDescription
64 | (32) `std::string` | mImagePath
96 | (472) `persona::CategoryQueryDocument` | mContentQueryDocument
568 | (472) `persona::CategoryQueryDocument` | mFeaturedQueryDocument
1040 | (1) `bool` | mSubCategoryInitialToggleState


### `persona::CategoryQueryDocument`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mHeader
32 | (4) `persona::OwnershipFilterType` | mOwnershipFilterType
36 | (4) `int` | mCycleAmount
40 | (432) `QueryDocument` | mQueryDoc


### `persona::PersonaSizeInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mSizeString
32 | (32) `std::string` | mSizeImage


### `persona::PersonaStoreItemCollector::QueryInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<SearchQuery>` | mQuery
16 | (4) `int` | mPossiblePackCount
20 | (4) `int` | mNumPacksCollected
24 | (4) `int` | mFilteredOutContent
28 | (4) `int` | mCatalogTotal


### `PlayScreenModel::navigateToWorldSyncModalScreen::__l2::<lambda_5b1bdbb1f29c7cc64448708ddd70e61f>::()::__l2::<lambda_5de8426d871a2cae8cea91a51c9b89f9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (64) `std::function<void __cdecl(Core::Result)>` | onCompleteCallback
80 | (64) `std::function<void __cdecl(Core::Result)>` | progressSyncCallback
144 | (32) `const std::string` | levelId


### `PlayScreenModel::navigateToWorldSyncModalScreen::__l2::<lambda_5b1bdbb1f29c7cc64448708ddd70e61f>::()::__l5::<lambda_367a2d7801f77691f9aab18191bd527b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (1) `bool` | priorManifestSyncRequiresWorldSync
24 | (32) `const std::string` | levelId
56 | (64) `std::function<void __cdecl(Core::Result)>` | onWorldSyncComplete


### `PlayScreenModel::navigateToEditWorldScreen::__l14::<lambda_4d403d0c32019894b8c87b1125371cda>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (8) `LocalWorldInfo *` | info
24 | (64) `std::function<void __cdecl(Core::Path const &)>` | onErrorCallback


### `PlayScreenModel::_populateNetworkWorlds::__l97::<lambda_d572a438a99a6f2e256eb026276c41b8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (32) `const std::string` | ownerId


### `PlayScreenModel::_populateNetworkWorlds::__l99::<lambda_3868ce00ebe4bccdda287e34680d826b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (32) `const std::string` | ownerId


### `PlayScreenModel::_startLocalWorld::__l2::<lambda_ad0b048280eff8b14b8fe6a7d3d7d687>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PlayScreenModel>` | weakThis
16 | (384) `LevelSummary` | levelSummary
400 | (3360) `LevelSettings` | levelSettings


### `PotionBrewing::Ingredient`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mItemId
4 | (4) `int` | mData


### `PlayerListEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mId
8 | (16) `mce::UUID` | mUUID
24 | (32) `std::string` | mName
56 | (32) `std::string` | mXUID
88 | (32) `std::string` | mPlatformOnlineId
120 | (4) `BuildPlatform` | mBuildPlatform
128 | (640) `SerializedSkin` | mSkin
768 | (640) `SerializedSkin` | mPendingSkin
1408 | (1) `bool` | mIsTeacher
1409 | (1) `bool` | mIsHost
1416 | (24) `std::vector<unsigned char>` | mBloomData
1440 | (168) `NameTagInfo` | mNameTagInfo
1608 | (168) `NameTagInfo` | mVipNameTagInfo
1776 | (4) `unsigned int` | mGrowthLevel
1780 | (1) `bool` | mServerSkinConfirmed


### `ParticleRenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenContext *` | mScreenContext
8 | (8) `Tessellator *` | mTessellator
16 | (8) `const Vec3 *` | mCameraTargetPosition
24 | (8) `const Vec3 *` | mCameraPosition
32 | (4) `const float` | mMinDistSquare
40 | (8) `const ParticleEngine *` | mParticleEngine
48 | (4) `const float` | a


### `ParticleTypeRenderObject`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::Mesh>` | mLayerMesh
16 | (72) `mce::TexturePtr` | mLayerTexture
88 | (1) `bool` | mBlend


### `ParticleSystem::ParticleAppearanceTintingComponent::ColorFrame`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mValue
8 | (864) `std::array<ExpressionNode,4>` | mColorExpr


### `ParticleSystem::NodeParseData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<float,ParticleSystem::NodeParseData::Node>>` | mNodeList


### `ParticleSystem::ParticleEvent`
Offset | Type | Name
-|-|-|-
0 | (272) `ParticleSystem::ParticleVisualEffectEvent` | mVisualEffect
272 | (4) `ParticleSystem::ParticleSoundEffectEvent` | mSoundEffect
280 | (216) `ExpressionNode` | mEventExpression
496 | (32) `std::string` | mLogMessage


### `ParticleSystem::ParticleVisualEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mParticleEffectType
8 | (48) `HashedString` | mEffect
56 | (216) `ExpressionNode` | mEffectExpression


### `ParticleSystem::ParticleSoundEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `LevelSoundEvent` | mEvent


### `ParticleSystem::ParticleEventNode`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<ParticleSystem::ParticleEventNode>>` | mSequenceNodes
24 | (24) `std::vector<std::pair<float,std::unique_ptr<ParticleSystem::ParticleEventNode> >>` | mRandomNodes
48 | (8) `std::unique_ptr<ParticleSystem::ParticleEvent>` | mEvent
56 | (4) `float` | mRandomNodesWeightSum


### `ParticleSystem::ComponentAccessParticleEmitter::CollisionHelper`
Offset | Type | Name
-|-|-|-
0 | (28) `AABB` | mHitShape
28 | (4) `float` | mHitAlpha
32 | (1) `unsigned __int8` | mHitAxis


### `PersonaRepository::_updatePersonaCharacter::__l5::<lambda_0dc42af7a8c769c98155089844906880>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | cb
80 | (32) `std::string` | skinName


### `PersonaRepository::_updatePersonaCharacter::__l5::<lambda_0dc42af7a8c769c98155089844906880>::()::__l5::<lambda_744f5289394d3fc121cddf3fc7d76391>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (32) `std::string` | skinName
48 | (1) `bool` | parsedTexturesResult
56 | (64) `std::function<void __cdecl(bool)>` | callback


### `PersonaRepository::createPersonaOnUser::__l2::<lambda_fa698ab5277b725707db41b1f541b00b>`
Offset | Type | Name
-|-|-|-
0 | (8) `PersonaRepository *const` | __this
8 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
24 | (32) `std::string` | newSkinName
56 | (4) `persona::ProfileType` | profileType
64 | (64) `std::function<void __cdecl(std::string const &)>` | cb


### `PersonaRepository::PendingPersonaAppearance`
Offset | Type | Name
-|-|-|-
0 | (1464) `PersonaAppearance` | mItems
1464 | (64) `std::function<void __cdecl(std::string const &)>` | mCallback
1528 | (4) `PersonaRepository::PendingPersonaAppearanceStatus` | mStatus
1536 | (16) `std::shared_ptr<DlcBatchModel>` | mDlcDownloader
1552 | (32) `std::string` | mCharacterName
1584 | (1) `bool` | mUseCaching
1585 | (1) `bool` | mDownloadFailed


### `PersonaRepository::changePiece::__l2::<lambda_a434f4b7e65f777a66b06a869c83a78c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (64) `std::function<void __cdecl(bool)>` | loadCallback
80 | (40) `const persona::PersonaCharacterHandle` | currentCharacter


### `persona::PieceToChange`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mId
16 | (4) `_BYTE[4]` | mPieceType
20 | (4) `_BYTE[4]` | mSide
24 | (32) `std::string` | mProductId
56 | (3) `persona::FreeItemState` | mFreeItemState


### `PersonaRepository::_parseTextures::__l2::<lambda_10f0bd2c25131a7c83c7167248bb7003>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (32) `std::string` | skinName
48 | (64) `std::function<void __cdecl(bool)>` | cb


### `PersonaRepository::_parseTextures::__l2::<lambda_10f0bd2c25131a7c83c7167248bb7003>::()::__l5::<lambda_c799a6325396d5ef75f2a146eb9d922f>`
Offset | Type | Name
-|-|-|-
0 | (64) `PersonaRepository::_parseTextures::__l2::<lambda_10f0bd2c25131a7c83c7167248bb7003>::()::__l2::<lambda_5d85ab44a3be28060ce8c604d35e3e70>` | callCallback
64 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
80 | (32) `std::string` | textureId
112 | (32) `std::string` | characterName


### `PersonaRepository::_parseTextures::__l2::<lambda_10f0bd2c25131a7c83c7167248bb7003>::()::__l2::<lambda_5d85ab44a3be28060ce8c604d35e3e70>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback


### `PersonaRepository::_createPersona::__l2::<lambda_1ac8df20115d23db4b78209d5ba2109e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (1) `bool` | useCaching
24 | (64) `std::function<void __cdecl(std::string const &)>` | newPersonaCallback
88 | (64) `std::function<void __cdecl(void)>` | appearanceCb
152 | (32) `std::string` | skinName


### `PersonaRepository::_createPersona::__l2::<lambda_1ca4cb5ef36f499cc6568a184177d332>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (184) `PersonaRepository::_createPersona::__l2::<lambda_1ac8df20115d23db4b78209d5ba2109e>` | updateCb
200 | (32) `std::string` | skinName
232 | (3976) `PersonaCharacter` | character
4208 | (1) `bool` | async


### `PersonaRepository::_registerPersonaUserPieceTextures::__l9::<lambda_9ba0fc83626afbe85d07dc9acfc80a7a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<PersonaRepository>` | weakThis
16 | (56) `const ResourceLocation` | resLoc
72 | (40) `persona::PersonaCharacterHandle` | characterHandle


### `PolygonOperatorPool<RenderChunkSorter>::PoolEntry`
Offset | Type | Name
-|-|-|-
0 | (1) `const bool` | mIsImmediate
8 | (8) `std::unique_ptr<RenderChunkSorter>` | mEntry


### `ParticleRenderObjectCollection`
Offset | Type | Name
-|-|-|-
0 | (48) `ParticleLayerRenderObject` | mAlphaTested
48 | (48) `ParticleLayerRenderObject` | mBlended
96 | (48) `ParticleLayerRenderObject` | mOpaque


### `ParticleLayerRenderObject`
Offset | Type | Name
-|-|-|-
0 | (40) `std::vector<ParticleTypeRenderObject,LinearAllocator<ParticleTypeRenderObject> >` | mLayers
40 | (8) `const mce::MaterialPtr *` | mLayerMaterial


### `ParsedAtlasData`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | mMetaLocation
56 | (152) `PageSettings` | mPageSettings
208 | (4) `int` | mJsonPadSize
212 | (4) `unsigned int` | mJsonNumberOfMips
216 | (24) `std::vector<ParsedAtlasNode>` | mAtlasNodesList


### `PageSettings`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mResourceName
32 | (32) `std::string` | mJsonKey
64 | (32) `std::string` | mFileSuffix
96 | (32) `std::string` | mDefaultTexture
128 | (16) `mce::Color` | mDefaultColor
144 | (1) `bool` | mFadeMip
145 | (1) `bool` | mApplyTint
146 | (1) `bool` | mApplyOverlay


### `ParsedAtlasNodeElement`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | mLocation
56 | (56) `ResourceLocation` | mTintMapLocation
112 | (4) `int` | mPackIndex
116 | (16) `mce::Color` | mOverlay
136 | (96) `TextureUVCoordinateSet` | mUv
232 | (4) `float` | mMipFadeAmount
236 | (16) `mce::Color` | mMipFadeColor
252 | (16) `mce::Color` | mTintColor
268 | (64) `TintMapColor` | mMultiChannelTintBaseColor
332 | (64) `TintMapColor` | mMultiChannelTintColor
396 | (4) `float` | mWeight
400 | (1) `bool` | mIsAdditive
401 | (1) `bool` | mMultiChannelTint
404 | (4) `cg::TextureSetLayerType` | mTextureSetLayerType


### `PackLoadError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `PersonaPieceHandle::DeserializedPieceMetaData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mActualId
32 | (4) `_BYTE[4]` | mPieceType
36 | (4) `_BYTE[4]` | mPieceSide
40 | (1) `bool` | mFreeItem


### `PersonaService::getAppearances::__l24::<lambda_c8daa739e4f3ac4f5212d25a433c3ba8>`
Offset | Type | Name
-|-|-|-
0 | (8) `PersonaService *const` | __this
8 | (4) `const unsigned int` | userId
16 | (64) `std::function<void __cdecl(enum persona::ProfileType)>` | xforgeRequestStartCallback
80 | (16) `std::shared_ptr<Social::User>` | sharedUser
96 | (24) `std::vector<int>` | loadOrder
120 | (64) `std::function<void __cdecl(PersonaAppearance const &,enum persona::ProfileType)>` | onAppearanceValidate
184 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | startTime


### `PersonaService::getAppearances::__l28::<lambda_152ab41b6be6d97a049b15ad7e5edf2b>`
Offset | Type | Name
-|-|-|-
0 | (8) `PersonaService *const` | __this
8 | (4) `const unsigned int` | userId
16 | (16) `std::shared_ptr<Social::User>` | sharedUser
32 | (24) `std::vector<int>` | loadOrder
56 | (64) `std::function<void __cdecl(enum persona::ProfileType)>` | xforgeRequestStartCallback
120 | (64) `std::function<void __cdecl(PersonaAppearance const &,enum persona::ProfileType)>` | cb


### `PersonaService::getAppearances::__l24::<lambda_c8daa739e4f3ac4f5212d25a433c3ba8>::()::__l5::<lambda_3dc4c4d1c65fd2c738b5436343eb9d08>`
Offset | Type | Name
-|-|-|-
0 | (8) `PersonaService *const` | __this
8 | (4) `const unsigned int` | userId
16 | (64) `std::function<void __cdecl(enum persona::ProfileType)>` | xforgeRequestStartCallback
80 | (16) `std::shared_ptr<Social::User>` | sharedUser
96 | (24) `std::vector<int>` | loadOrder
120 | (16) `Json::Value` | result2
136 | (64) `std::function<void __cdecl(PersonaAppearance const &,enum persona::ProfileType)>` | appearanceValidateCallback


### `PushNotificationMessage`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | m_Type
8 | (32) `std::string` | m_Title
40 | (32) `std::string` | m_Description
72 | (16) `Json::Value` | m_PropertyBag


### `PromotionToastDocument`
Offset | Type | Name
-|-|-|-
0 | (584) `CommonDocument` | mCommon
584 | (208) `PromotionToastCustom` | mCustom


### `PromotionToastCustom`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mToastMessageType
32 | (32) `std::string` | mToastMessageData
64 | (32) `std::string` | mTelemetryId
96 | (32) `std::string` | mStartDate
128 | (32) `std::string` | mEndDate
160 | (32) `std::string` | mImageType
192 | (4) `unsigned int` | mDaysBeforeReminding
196 | (4) `unsigned int` | mMaxNumberOfTimesToShow
200 | (1) `bool` | mIgnoreImage
201 | (1) `bool` | mDisplaySubtitle


### `PlayerTickComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mLatestClientTick
8 | (8) `unsigned __int64` | mLatestProcessedTick
16 | (1) `unsigned __int8` | mCurrentProcessedTicks
24 | (8) `unsigned __int64` | mSystemTicksSinceProcessedTick
32 | (8) `std::unique_ptr<IPlayerTickPolicy>` | mPolicy


### `PackSettingsError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `PackStackStorage::PackEntry`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mID
136 | (16) `std::shared_ptr<IPackStorage>` | mStorage


### `PackStackStorage::onLoadSessionEnd::__l9::<lambda_f4caca1443c325a114dd6c3c07cc7928>`
Offset | Type | Name
-|-|-|-
0 | (8) `PackStackStorage *const` | __this
8 | (152) `PackStackStorage::PackEntry` | pack
160 | (16) `std::shared_ptr<IPackStorageFallback>` | packAccess


### `PackStackStorage::deleteStorage::__l9::<lambda_8036390ddfa8710f80ed365a0d137936>`
Offset | Type | Name
-|-|-|-
0 | (8) `PackStackStorage *const` | __this
8 | (152) `PackStackStorage::PackEntry` | pack


### `PackStorage::PackStorageImpl::<lambda_6e112b5c324bd97586ed3abeec7fc3ff>`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>` | self


### `PackStorage::PackStorageImpl::<lambda_43012a4723de9ee562d8876adc0e2feb>`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>` | self


### `PackStorage::PendingTask`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<std::string > >` | mAsyncHandle
16 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> >` | mIsFileUpToDate
32 | (40) `std::optional<std::string >` | mFileContents
72 | (16) `std::shared_ptr<IPackStorageFallback const >` | mFallback
88 | (32) `Core::Path` | mFilename
120 | (1) `PackStorage::PendingTask::Type` | mType
128 | (64) `std::function<void __cdecl(void)>` | mCallback


### `PackStorage::PackStorageImpl::writeOptimizedPack::__l2::<lambda_1f5ae5da0c0ce39014e2fca1b82c114b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ICRCDataOutput>` | out
16 | (16) `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>` | self
32 | (16) `std::shared_ptr<IPackStorageFallback const >` | readFromPack


### `PackStorage::PackStorageImpl::readOptimizedPack::__l2::<lambda_aa328192fb3f8fe908cc2fcdfa50f1ef>`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>` | self
16 | (16) `std::shared_ptr<std::unique_ptr<ICRCDataInput> >` | crcStream


### `PackStorage::FileEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mOffset
8 | (8) `unsigned __int64` | mSize
16 | (4) `unsigned int` | mCRC


### `PackStorage::PackStorageImpl::closePackStream::__l2::<lambda_f027d1e8730ed88e2be3e5721291af42>`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>` | self
16 | (16) `std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> >` | result


### `ProjectileComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mWasOnGround
1 | (1) `bool` | mNoPhysics
8 | (8) `ActorUniqueID` | mOwnerId
16 | (12) `Vec3` | mThrownPos
28 | (12) `Vec3` | mApexPos
40 | (1) `bool` | mFoundApex
44 | (4) `int` | mLife
48 | (4) `int` | mFlightTime
52 | (4) `int` | mOnGroundTime
56 | (4) `int` | mShakeTime
60 | (12) `BlockPos` | mBlock
72 | (12) `BlockPos` | mStuckToBlockPos
84 | (12) `Vec3` | mCollisionPos
96 | (4) `int` | mEnchantPower
100 | (4) `int` | mEnchantImpaler
104 | (112) `HitResult` | mHitResult
216 | (4) `float` | mScriptDmg
220 | (1) `unsigned __int8` | mHitFacing
221 | (1) `bool` | mReflect
224 | (4) `float` | mPower
228 | (4) `float` | mDamage
232 | (12) `Vec3` | mOffset
244 | (4) `ParticleType` | mHitParticle
248 | (4) `float` | mGravity
252 | (4) `float` | mUpwardsAngleOffset
256 | (24) `std::vector<OnHitSubcomponent *>` | mOnHitCommands
280 | (320) `DefinitionTrigger` | mOnHitEvent
600 | (4) `float` | mUncertaintyBase
604 | (4) `float` | mUncertaintyMultiplier
608 | (4) `ActorType` | mFilterType
612 | (4) `float` | mOnFireTime
616 | (4) `int` | mPotionEffect
620 | (4) `float` | mSplashRange
624 | (1) `bool` | mKnockback
628 | (4) `float` | mKnockbackForce
632 | (1) `bool` | mCatchFire
633 | (1) `bool` | mChanneling
634 | (1) `bool` | mIsSplash
636 | (4) `float` | mInertiaMod
640 | (4) `float` | mLiquidInertia
644 | (1) `bool` | mSemiRandomDiffDamage
648 | (4) `ProjectileAnchor` | mSpawnPosAnchor
652 | (4) `LevelSoundEvent` | mHitEntitySound
656 | (4) `LevelSoundEvent` | mHitGroundSound
660 | (4) `LevelSoundEvent` | mShootSound
664 | (1) `bool` | mIsDangerous
665 | (1) `bool` | mShootTarget
666 | (1) `bool` | mDamageOwner
667 | (1) `bool` | mReflectOnHurt
668 | (1) `bool` | mDestroyOnHurt
669 | (1) `bool` | mStopOnHit
670 | (1) `bool` | mCritParticleOnHurt
671 | (1) `bool` | mHitWater
672 | (1) `bool` | mHitActor
673 | (1) `bool` | mMultipleHits
676 | (4) `int` | mPiercingEnchantLevel
680 | (4) `int` | mActorHitCount
684 | (1) `bool` | mIsHoming
688 | (8) `ActorUniqueID` | mPendingTargetID
696 | (8) `Actor *` | mTarget
704 | (8) `ActorUniqueID` | mTargetID
712 | (12) `Vec3` | mTargetDelta
724 | (4) `int` | mFlightSteps
728 | (4) `_BYTE[4]` | mCurrentMoveDirection
732 | (1) `bool` | mShouldBounce
736 | (4) `unsigned int` | mCurrentDelay
740 | (1) `bool` | mWaitingForServer
741 | (1) `bool` | mWaitingForServerHitGround
744 | (112) `HitResult` | mCachedHitResult
856 | (1) `bool` | mDelayOneFrame


### `PrioritizedGoal`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Goal>` | mGoal
8 | (4) `int` | mPriority
12 | (1) `bool` | mUsed
13 | (1) `bool` | mToStart


### `PathFinder`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mRegion
8 | (32) `BinaryHeap` | mOpenSet
40 | (64) `std::unordered_map<BlockPos,PathfinderNode>` | mNodes
104 | (256) `std::array<PathfinderNode *,32>` | mNeighbors
360 | (1) `bool` | mCanPassDoors
361 | (1) `bool` | mCanOpenDoors
362 | (1) `bool` | mCanOpenIronDoors
363 | (1) `bool` | mAvoidWater
364 | (1) `bool` | mAvoidDamageBlocks
365 | (1) `bool` | mCanFloat
366 | (1) `bool` | mCanPathOverLava
367 | (1) `bool` | mIsAmphibious
368 | (1) `bool` | mAvoidPortals
369 | (1) `bool` | mCanBreach
370 | (1) `bool` | mCanJump
371 | (1) `bool` | mEntityIsSwimmer
372 | (1) `bool` | mEntityIsFlyer
373 | (1) `bool` | mEntityIsFireImmune
374 | (1) `bool` | mEntityIsOnHotBlock
375 | (1) `bool` | mEntityIsWalker
376 | (1) `bool` | mEntityIsDoorOpener
377 | (1) `bool` | mEntityIsDoorBreaker
378 | (1) `bool` | mAllowBlockBreaking
384 | (8) `const PreferredPathDescription *` | mPathPrefs
392 | (4) `int` | mMaxIteration
396 | (1) `bool` | mConfirmDest


### `ProjectileHitEvent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mProjectile
8 | (112) `const HitResult` | mHitResult


### `ParticlesTeleportTrailEvent`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mStart
12 | (12) `Vec3` | mEnd
24 | (8) `Vec2` | mVariation
32 | (4) `float` | mDirScale
36 | (4) `int` | mCount


### `PacketViolationDetectedTelemetryData`
Offset | Type | Name
-|-|-|-
0 | (40) `ExtendedStreamReadResult` | mExtendedReadResult
40 | (4) `_BYTE[4]` | mViolationResponse
44 | (4) `MinecraftPacketIds` | mViolatingPacketId
48 | (152) `NetworkIdentifier` | mNetId


### `PotionMixDataEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | fromItemId
4 | (4) `int` | fromItemAux
8 | (4) `int` | reagentItemId
12 | (4) `int` | reagentItemAux
16 | (4) `int` | toItemId
20 | (4) `int` | toItemAux


### `PacketViolationHandler::PacketViolation`
Offset | Type | Name
-|-|-|-
0 | (152) `NetworkIdentifier` | mNetId
152 | (4) `unsigned int` | mTotalCount
156 | (4) `float` | mTotalScore
160 | (4) `MinecraftPacketIds` | mLastPacketId
164 | (4) `StreamReadResult` | mLastResult
168 | (4) `_BYTE[4]` | mLastResponse
176 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mLastViolationTime


### `PackAccessStrategyFactory::createForZip::__l10::<lambda_efd3edd89f95cae6f703fa58a12bab2a>`
Offset | Type | Name
-|-|-|-
0 | (56) `const ResourceLocation` | location
56 | (8) `unsigned __int64 *` | currentManifestPathDepth
64 | (8) `std::vector<Core::PathBuffer<std::string >> *` | subPaths


### `PackMover::copyPack::__l2::<lambda_efa97ea215b0ec3ccc21c2ccfa0a00f4>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback
64 | (16) `std::shared_ptr<bool>` | importSuccess


### `PackMover::copyPack::__l2::<lambda_d0dea2db41fda175eebc6788cb5f1044>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<bool>` | importSuccess
16 | (56) `const ResourceLocation` | srcLocation
72 | (1) `bool` | srcPackIsZipped
80 | (32) `Core::PathBuffer<std::string >` | destPath
112 | (1) `bool` | zipDestination
120 | (24) `const std::vector<std::string>` | excludeDirs
144 | (8) `Core::ZipUtils::ZipProgressList *` | progressList
152 | (1) `bool` | enableExternalWorldTemplatePackSources
153 | (1) `bool` | unzipAsFlatFile


### `PackMover::copyPack::__l2::<lambda_d0dea2db41fda175eebc6788cb5f1044>::()::__l31::<lambda_5f399ab693cf08c0b37e8740c385d58d>`
Offset | Type | Name
-|-|-|-
0 | (24) `const std::vector<std::string>` | excludeDirs
24 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | uniqueDestinationDir


### `PrivateKeyManager`
Offset | Type | Name
-|-|-|-
0 | (48) `KeyManager` | baseclass_0
48 | (32) `std::string` | mPrivateKey


### `PlayerDamageEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (8) `std::unique_ptr<ActorDamageSource>` | mDamageSource


### `PlayerAddExpEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (4) `int` | mExp


### `PlayerArmorExchangeEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (4) `ArmorSlot` | mArmorSlot
32 | (248) `ItemStack` | mOldItem
280 | (248) `ItemStack` | mItem
528 | (4) `PlayerArmorExchangeEventTriggeredLocation` | mTriggeredLocation


### `PlayerGetExperienceOrbEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (4) `int` | mExperienceValue


### `PlayerEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer


### `PlayerEventCoordinator::sendPlayerCraftedItem::__l2::<lambda_42ff3f701c9b46b37c70e4fa14201c5a>`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | player
8 | (8) `const ItemInstance *` | item
16 | (8) `bool *` | recipeBook
24 | (8) `bool *` | hadSearchString
32 | (8) `bool *` | craftedAutomatically
40 | (8) `int *` | startingTabId
48 | (8) `int *` | endingTabId
56 | (8) `int *` | numTabsChanged
64 | (8) `bool *` | filterOn
72 | (8) `bool *` | recipeBookShown
80 | (8) `const std::vector<short> *` | ingredientItemIDs


### `PlayerAddLevelEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (4) `int` | mAddLevel
28 | (4) `int` | mNewLevel


### `PlayerDestroyBlockEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (12) `BlockPos` | mBlockPos
36 | (1) `unsigned __int8` | mFace
40 | (8) `gsl::not_null<Block const *>` | mBlock


### `PlayerSayCommandEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (32) `std::string` | mMessage


### `PlayerUseNameTagEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mPlayer
24 | (248) `ItemStack` | mItem


### `PortalShape`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mAxis
4 | (1) `Facing::Name` | mRightDir
5 | (1) `Facing::Name` | mLeftDir
8 | (4) `int` | mNumPortalBlocks
12 | (12) `BlockPos` | mBottomLeft
24 | (1) `bool` | mBottomLeftValid
28 | (4) `int` | mHeight
32 | (4) `int` | mWidth


### `PostprocessingManager::Owns`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos` | mPosition
8 | (8) `PostprocessingManager *` | mPpm
16 | (24) `std::vector<PostprocessingManager::LockedChunk>` | mLockedChunks


### `ParticlesBlockExplosionEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mRadius
4 | (12) `Vec3` | mOrigin
16 | (24) `std::vector<Vec3>` | mPositions


### `PendingArea`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mUID
16 | (32) `std::string` | mName
48 | (8) `ActorUniqueID` | mEntityId
56 | (48) `Bounds` | mBounds
104 | (4) `float` | mMaxDistToPlayers
108 | (1) `bool` | mIsCircle
109 | (1) `bool` | mAlwaysActive
110 | (1) `bool` | mCreated


### `PlayerListPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<PlayerListEntry>` | mEntries
64 | (1) `_BYTE[1]` | mAction


### `PathfinderNode`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | heapIdx
4 | (4) `float` | g
8 | (4) `float` | h
12 | (4) `float` | f
16 | (4) `float` | mCostMalus
20 | (4) `float` | mMoveMalus
24 | (4) `float` | mTargetDist
28 | (4) `NodeType` | mType
32 | (8) `PathfinderNode *` | cameFrom
40 | (12) `BlockPos` | pos
52 | (1) `bool` | closed


### `PositionTrackingDB::PositionTrackingDBServer`
Offset | Type | Name
-|-|-|-
0 | (16) `std::enable_shared_from_this<PositionTrackingDB::PositionTrackingDBServer>` | baseclass_0
16 | (8) `Level *` | mLevel
24 | (8) `Scheduler *` | mCallbackContext
32 | (8) `LevelStorage *` | mLevelStorage
40 | (8) `std::unique_ptr<TaskGroup>` | mAsyncTaskGroup
48 | (8) `std::unique_ptr<PositionTrackingDB::CacheManager>` | mLocalCache
56 | (24) `std::vector<PositionTrackingDB::TrackingRecord *>` | mPendingUpdateQueue


### `PackIdAndItemId`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mId
16 | (32) `std::string` | mItemId


### `png_struct_def`
Offset | Type | Name
-|-|-|-
0 | (256) `_SETJMP_FLOAT128[16]` | jmp_buf_local
256 | (8) `void (__fastcall *)(_SETJMP_FLOAT128 *, int)` | longjmp_fn
264 | (8) `_SETJMP_FLOAT128 (*)[16]` | jmp_buf_ptr
272 | (8) `unsigned __int64` | jmp_buf_size
280 | (8) `void (__fastcall *)(png_struct_def *, const char *)` | error_fn
288 | (8) `void (__fastcall *)(png_struct_def *, const char *)` | warning_fn
296 | (8) `void *` | error_ptr
304 | (8) `void (__fastcall *)(png_struct_def *, unsigned __int8 *, unsigned __int64)` | write_data_fn
312 | (8) `void (__fastcall *)(png_struct_def *, unsigned __int8 *, unsigned __int64)` | read_data_fn
320 | (8) `void *` | io_ptr
328 | (8) `void (__fastcall *)(png_struct_def *, png_row_info_struct *, unsigned __int8 *)` | read_user_transform_fn
336 | (8) `void (__fastcall *)(png_struct_def *, png_row_info_struct *, unsigned __int8 *)` | write_user_transform_fn
344 | (8) `void *` | user_transform_ptr
352 | (1) `unsigned __int8` | user_transform_depth
353 | (1) `unsigned __int8` | user_transform_channels
356 | (4) `unsigned int` | mode
360 | (4) `unsigned int` | flags
364 | (4) `unsigned int` | transformations
368 | (4) `unsigned int` | zowner
376 | (88) `z_stream_s` | zstream
464 | (8) `png_compression_buffer *` | zbuffer_list
472 | (4) `unsigned int` | zbuffer_size
476 | (4) `int` | zlib_level
480 | (4) `int` | zlib_method
484 | (4) `int` | zlib_window_bits
488 | (4) `int` | zlib_mem_level
492 | (4) `int` | zlib_strategy
496 | (4) `int` | zlib_text_level
500 | (4) `int` | zlib_text_method
504 | (4) `int` | zlib_text_window_bits
508 | (4) `int` | zlib_text_mem_level
512 | (4) `int` | zlib_text_strategy
516 | (4) `int` | zlib_set_level
520 | (4) `int` | zlib_set_method
524 | (4) `int` | zlib_set_window_bits
528 | (4) `int` | zlib_set_mem_level
532 | (4) `int` | zlib_set_strategy
536 | (4) `unsigned int` | width
540 | (4) `unsigned int` | height
544 | (4) `unsigned int` | num_rows
548 | (4) `unsigned int` | usr_width
552 | (8) `unsigned __int64` | rowbytes
560 | (4) `unsigned int` | iwidth
564 | (4) `unsigned int` | row_number
568 | (4) `unsigned int` | chunk_name
576 | (8) `unsigned __int8 *` | prev_row
584 | (8) `unsigned __int8 *` | row_buf
592 | (8) `unsigned __int8 *` | try_row
600 | (8) `unsigned __int8 *` | tst_row
608 | (8) `unsigned __int64` | info_rowbytes
616 | (4) `unsigned int` | idat_size
620 | (4) `unsigned int` | crc
624 | (8) `png_color_struct *` | palette
632 | (2) `unsigned __int16` | num_palette
636 | (4) `int` | num_palette_max
640 | (2) `unsigned __int16` | num_trans
642 | (1) `unsigned __int8` | compression
643 | (1) `unsigned __int8` | filter
644 | (1) `unsigned __int8` | interlaced
645 | (1) `unsigned __int8` | pass
646 | (1) `unsigned __int8` | do_filter
647 | (1) `unsigned __int8` | color_type
648 | (1) `unsigned __int8` | bit_depth
649 | (1) `unsigned __int8` | usr_bit_depth
650 | (1) `unsigned __int8` | pixel_depth
651 | (1) `unsigned __int8` | channels
652 | (1) `unsigned __int8` | usr_channels
653 | (1) `unsigned __int8` | sig_bytes
654 | (1) `unsigned __int8` | maximum_pixel_depth
655 | (1) `unsigned __int8` | transformed_pixel_depth
656 | (1) `unsigned __int8` | zstream_start
658 | (2) `unsigned __int16` | filler
660 | (1) `unsigned __int8` | background_gamma_type
664 | (4) `int` | background_gamma
668 | (10) `png_color_16_struct` | background
678 | (10) `png_color_16_struct` | background_1
688 | (8) `void (__fastcall *)(png_struct_def *)` | output_flush_fn
696 | (4) `unsigned int` | flush_dist
700 | (4) `unsigned int` | flush_rows
704 | (4) `int` | gamma_shift
708 | (4) `int` | screen_gamma
712 | (8) `unsigned __int8 *` | gamma_table
720 | (8) `wchar_t **` | gamma_16_table
728 | (8) `unsigned __int8 *` | gamma_from_1
736 | (8) `unsigned __int8 *` | gamma_to_1
744 | (8) `wchar_t **` | gamma_16_from_1
752 | (8) `wchar_t **` | gamma_16_to_1
760 | (5) `png_color_8_struct` | sig_bit
765 | (5) `png_color_8_struct` | shift
776 | (8) `unsigned __int8 *` | trans_alpha
784 | (10) `png_color_16_struct` | trans_color
800 | (8) `void (__fastcall *)(png_struct_def *, unsigned int, int)` | read_row_fn
808 | (8) `void (__fastcall *)(png_struct_def *, unsigned int, int)` | write_row_fn
816 | (8) `void (__fastcall *)(png_struct_def *, png_info_def *)` | info_fn
824 | (8) `void (__fastcall *)(png_struct_def *, unsigned __int8 *, unsigned int, int)` | row_fn
832 | (8) `void (__fastcall *)(png_struct_def *, png_info_def *)` | end_fn
840 | (8) `unsigned __int8 *` | save_buffer_ptr
848 | (8) `unsigned __int8 *` | save_buffer
856 | (8) `unsigned __int8 *` | current_buffer_ptr
864 | (8) `unsigned __int8 *` | current_buffer
872 | (4) `unsigned int` | push_length
876 | (4) `unsigned int` | skip_length
880 | (8) `unsigned __int64` | save_buffer_size
888 | (8) `unsigned __int64` | save_buffer_max
896 | (8) `unsigned __int64` | buffer_size
904 | (8) `unsigned __int64` | current_buffer_size
912 | (4) `int` | process_mode
916 | (4) `int` | cur_palette
920 | (8) `unsigned __int8 *` | palette_lookup
928 | (8) `unsigned __int8 *` | quantize_index
936 | (4) `unsigned int` | options
940 | (29) `char[29]` | time_buffer
972 | (4) `unsigned int` | free_me
976 | (8) `void *` | user_chunk_ptr
984 | (8) `int (__fastcall *)(png_struct_def *, png_unknown_chunk_t *)` | read_user_chunk_fn
992 | (4) `int` | unknown_default
996 | (4) `unsigned int` | num_chunk_list
1000 | (8) `unsigned __int8 *` | chunk_list
1008 | (1) `unsigned __int8` | rgb_to_gray_status
1009 | (1) `unsigned __int8` | rgb_to_gray_coefficients_set
1010 | (2) `unsigned __int16` | rgb_to_gray_red_coeff
1012 | (2) `unsigned __int16` | rgb_to_gray_green_coeff
1016 | (4) `unsigned int` | mng_features_permitted
1020 | (1) `unsigned __int8` | filter_type
1024 | (8) `void *` | mem_ptr
1032 | (8) `void *(__fastcall *)(png_struct_def *, unsigned __int64)` | malloc_fn
1040 | (8) `void (__fastcall *)(png_struct_def *, void *)` | free_fn
1048 | (8) `unsigned __int8 *` | big_row_buf
1056 | (8) `unsigned __int8 *` | quantize_sort
1064 | (8) `unsigned __int8 *` | index_to_palette
1072 | (8) `unsigned __int8 *` | palette_to_index
1080 | (1) `unsigned __int8` | compression_type
1084 | (4) `unsigned int` | user_width_max
1088 | (4) `unsigned int` | user_height_max
1092 | (4) `unsigned int` | user_chunk_cache_max
1096 | (8) `unsigned __int64` | user_chunk_malloc_max
1104 | (32) `png_unknown_chunk_t` | unknown_chunk
1136 | (8) `unsigned __int64` | old_big_row_buf_size
1144 | (8) `unsigned __int8 *` | read_buffer
1152 | (8) `unsigned __int64` | read_buffer_size
1160 | (4) `unsigned int` | IDAT_read_size
1164 | (4) `unsigned int` | io_state
1168 | (8) `unsigned __int8 *` | big_prev_row
1176 | (32) `void (__fastcall *[4])(png_row_info_struct *, unsigned __int8 *, const unsigned __int8 *)` | read_filter
1208 | (76) `png_colorspace` | colorspace


### `png_color_16_struct`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | index
2 | (2) `unsigned __int16` | red
4 | (2) `unsigned __int16` | green
6 | (2) `unsigned __int16` | blue
8 | (2) `unsigned __int16` | gray


### `png_color_8_struct`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | red
1 | (1) `unsigned __int8` | green
2 | (1) `unsigned __int8` | blue
3 | (1) `unsigned __int8` | gray
4 | (1) `unsigned __int8` | alpha


### `png_unknown_chunk_t`
Offset | Type | Name
-|-|-|-
0 | (5) `unsigned __int8[5]` | name
8 | (8) `unsigned __int8 *` | data
16 | (8) `unsigned __int64` | size
24 | (1) `unsigned __int8` | location


### `png_colorspace`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | gamma
4 | (32) `png_xy` | end_points_xy
36 | (36) `png_XYZ` | end_points_XYZ
72 | (2) `unsigned __int16` | rendering_intent
74 | (2) `unsigned __int16` | flags


### `png_XYZ`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | red_X
4 | (4) `int` | red_Y
8 | (4) `int` | red_Z
12 | (4) `int` | green_X
16 | (4) `int` | green_Y
20 | (4) `int` | green_Z
24 | (4) `int` | blue_X
28 | (4) `int` | blue_Y
32 | (4) `int` | blue_Z


### `png_row_info_struct`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | width
8 | (8) `unsigned __int64` | rowbytes
16 | (1) `unsigned __int8` | color_type
17 | (1) `unsigned __int8` | bit_depth
18 | (1) `unsigned __int8` | channels
19 | (1) `unsigned __int8` | pixel_depth


### `PS_PrivateRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | unique_id
4 | (4) `int` | lenIV
8 | (1) `unsigned __int8` | num_blue_values
9 | (1) `unsigned __int8` | num_other_blues
10 | (1) `unsigned __int8` | num_family_blues
11 | (1) `unsigned __int8` | num_family_other_blues
12 | (28) `__int16[14]` | blue_values
40 | (20) `__int16[10]` | other_blues
60 | (28) `__int16[14]` | family_blues
88 | (20) `__int16[10]` | family_other_blues
108 | (4) `int` | blue_scale
112 | (4) `int` | blue_shift
116 | (4) `int` | blue_fuzz
120 | (2) `unsigned __int16[1]` | standard_width
122 | (2) `unsigned __int16[1]` | standard_height
124 | (1) `unsigned __int8` | num_snap_widths
125 | (1) `unsigned __int8` | num_snap_heights
126 | (1) `unsigned __int8` | force_bold
127 | (1) `unsigned __int8` | round_stem_up
128 | (26) `__int16[13]` | snap_widths
154 | (26) `__int16[13]` | snap_heights
180 | (4) `int` | expansion_factor
184 | (4) `int` | language_group
188 | (4) `int` | password
192 | (4) `__int16[2]` | min_feature


### `PS_ParserRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | cursor
8 | (8) `unsigned __int8 *` | base
16 | (8) `unsigned __int8 *` | limit
24 | (4) `int` | error
32 | (8) `FT_MemoryRec_ *` | memory
40 | (104) `PS_Parser_FuncsRec_` | funcs


### `PSH_GlyphRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | num_points
4 | (4) `unsigned int` | num_contours
8 | (8) `PSH_PointRec_ *` | points
16 | (8) `PSH_ContourRec_ *` | contours
24 | (8) `FT_MemoryRec_ *` | memory
32 | (8) `FT_Outline_ *` | outline
40 | (8) `PSH_GlobalsRec_ *` | globals
48 | (144) `PSH_Hint_TableRec_[2]` | hint_tables
192 | (1) `unsigned __int8` | vertical
196 | (4) `int` | major_dir
200 | (4) `int` | minor_dir
204 | (1) `unsigned __int8` | do_horz_hints
205 | (1) `unsigned __int8` | do_vert_hints
206 | (1) `unsigned __int8` | do_horz_snapping
207 | (1) `unsigned __int8` | do_vert_snapping
208 | (1) `unsigned __int8` | do_stem_adjust


### `PSH_Hint_TableRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | max_hints
4 | (4) `unsigned int` | num_hints
8 | (8) `PSH_HintRec_ *` | hints
16 | (8) `PSH_HintRec_ **` | sort
24 | (8) `PSH_HintRec_ **` | sort_global
32 | (4) `unsigned int` | num_zones
40 | (8) `PSH_ZoneRec_ *` | zones
48 | (8) `PSH_ZoneRec_ *` | zone
56 | (8) `PS_Mask_TableRec_ *` | hint_masks
64 | (8) `PS_Mask_TableRec_ *` | counter_masks


### `perrdetail`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | error
8 | (8) `const char *` | filename
16 | (4) `int` | lineno
20 | (4) `int` | offset
24 | (8) `char *` | text
32 | (4) `int` | token
36 | (4) `int` | expected


### `PredictedMovementValues`
```
const struct __cppobj PredictedMovementValues
{
  bool mUseAggressiveTickInterval;
  unsigned __int64 mInterpolationWindowSizeInTicks;
};

```

### `PrintStream`
```
struct __cppobj PrintStream
{
  PrintStream_vtbl *__vftable /*VFT*/;
};

```

### `PrintStream_vtbl`
```
struct /*VFT*/ PrintStream_vtbl
{
  void (__fastcall *~PrintStream)(PrintStream *this);
  void (__fastcall *print)(PrintStream *this, const std::string *);
};

```

### `PolygonQuad`
```
struct __cppobj PolygonQuad
{
  VertexPT mVertices[4];
};

```

### `PacketObserver`
```
struct __cppobj PacketObserver
{
  PacketObserver_vtbl *__vftable /*VFT*/;
};

```

### `Packet_vtbl`
```
struct /*VFT*/ Packet_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `Player`
```
const struct __cppobj __declspec(align(8)) Player : Mob
{
  int mCastawayTimer;
  bool mAteKelp;
  int mLastBiome;
  std::vector<int> mOceanBiomes;
  bool castawaySent;
  bool sailseasSent;
  Player::DimensionState mDimensionState;
  bool mServerHasMovementAuthority;
  char mUserType;
  int mScore;
  float mOBob;
  float mBob;
  bool mHandsBusy;
  std::string mName;
  BuildPlatform mBuildPlatform;
  Abilities mAbilities;
  const NetworkIdentifier mOwner;
  std::string mUniqueName;
  std::string mServerId;
  std::string mSelfSignedId;
  std::string mPlatformOfflineId;
  unsigned __int64 mClientRandomId;
  const mce::UUID mClientUUID;
  std::unique_ptr<Certificate> mCertificate;
  std::string mPlatformId;
  ActorUniqueID mPendingRideID;
  ActorUniqueID mPendingLeftShoulderRiderID;
  ActorUniqueID mPendingRightShoulderRiderID;
  ActorUniqueID mInteractTarget;
  Vec3 mInteractTargetPos;
  bool mHasFakeInventory;
  bool mIsRegionSuspended;
  std::shared_ptr<ChunkViewSource> mChunkSource;
  std::shared_ptr<ChunkViewSource> mSpawnChunkSource;
  std::unique_ptr<BlockSource> mOwnedBlockSource;
  bool mUpdateMobs;
  Vec3 mFirstPersonLatestHandOffset;
  Vec3 mCapePosO;
  Vec3 mCapePos;
  float mPaddleForces[2];
  bool mIsPaddling[2];
  float mDistanceSinceTravelledEvent;
  float mDistanceSinceTransformEvent;
  std::shared_ptr<IContainerManager> mContainerManager;
  std::unique_ptr<PlayerInventory> mInventory;
  SerializedSkin mSkin;
  std::vector<ItemInstance> mCreativeItemList;
  SerializedSkin mPrevSkin;
  bool mSetLockRotation;
  std::array<std::vector<ItemGroup>,8> mFilteredCreativeItemList;
  unsigned __int8 mClientSubId;
  std::string mPlatformOnlineId;
  Player::SpawnPositionState mSpawnPositionState;
  Player::SpawnPositionSource mSpawnPositionSource;
  Vec3 mSpawnPositioningTestPosition;
  bool mBlockRespawnUntilClientMessage;
  unsigned int mRespawnChunkBuilderPolicyHandle;
  Player::CachedSpawnData mCachedSpawnData;
  std::unique_ptr<BlockSource> mSpawnBlockSource;
  bool mHasSeenCredits;
  Stopwatch mRespawnStopwatch_Searching;
  Vec3 mRespawnOriginalPosition;
  AutomaticID<Dimension,int> mRespawnOriginalDimension;
  bool mRespawnReady;
  std::string mRespawnMessage;
  bool mCheckBed;
  bool mIsInitialSpawnDone;
  bool mRespawningFromTheEnd;
  bool mPositionLoadedFromSave;
  int mFixStartSpawnFailures;
  ItemStack mItemInUse;
  PlayerInventory::SlotData mItemInUseSlot;
  int mItemInUseDuration;
  __int16 mSleepCounter;
  __int16 mPrevSleepCounter;
  bool mInteractDataDirty;
  ActorUniqueID mPreviousInteractEntity;
  int mPreviousCarriedItem;
  ItemStack mPreviousCarriedItemStack;
  bool mAutoJumping;
  int mEmoteTicks;
  PacketSender *mPacketSender;
  BlockPos mBounceStartPos;
  const Block *mBounceBlock;
  float mFOVModifier;
  std::shared_ptr<HudContainerManagerModel> mHudContainerManagerModel;
  std::unique_ptr<EnderChestContainer> mEnderChestInventory;
  std::vector<ActorUniqueID> mTrackedBossIDs;
  _BYTE mPositionMode[1];
  ActorType mLastHurtBy;
  ItemGroup mCursorSelectedItemGroup;
  PlayerUIContainer mPlayerUIContainer;
  InventoryTransactionManager mTransactionManager;
  std::shared_ptr<GameMode> mGameMode;
  long double mExpMultiplier;
  long double mBlockMultiplier;
  long double mAccumulatedXP;
  PlayerRespawnRandomizer mSpawnRandomizer;
  std::unique_ptr<ItemStackNetManagerBase> mItemStackNetManager;
  float mVRMoveAdjAngle;
  std::shared_ptr<AnimationComponent> mUIAnimationComponent;
  std::shared_ptr<AnimationComponent> mMapAnimationComponent;
  Player::PlayerSpawnPoint mPlayerRespawnPoint;
  bool mUseUIAnimationComponent;
  bool mUseMapAnimationComponent;
  std::vector<PlayerListener *> mListeners;
  int mLastLevelUpTime;
  bool mPlayerLevelChanged;
  int mPreviousLevelRequirement;
  Vec3 mRespawnPositionCandidate;
  bool mPlayerIsSleeping;
  bool mAllPlayersSleeping;
  bool mDestroyingBlock;
  Vec3 mSurvivalViewerPosition;
  std::vector<unsigned int> mOnScreenAnimationTextures;
  int mOnScreenAnimationTicks;
  GameType mPlayerGameType;
  int mEnchantmentSeed;
  unsigned int mChunkRadius;
  int mMapIndex;
  unsigned __int64 mElytraLoop;
  float mElytraVolume;
  float mUnderwaterLightLevel;
  std::unordered_map<std::string,int> mCooldowns;
  __int64 mStartedBlockingTimeStamp;
  __int64 mBlockedUsingShieldTimeStamp;
  __int64 mBlockedUsingDamagedShieldTimeStamp;
  bool mPrevBlockedUsingShield;
  bool mPrevBlockedUsingDamagedShield;
  bool mUsedPotion;
  int mBounceHeight;
  SkinAdjustments mSkinAdjustments;
  SerializedSkin mSerializedSkin;
  int mScanForDolphinTimer;
  AABB *mHead;
  AABB *mOther;
  float mWidth;
  float mHeight;
  bool mCanMove;
  bool mCanAttack;
  bool mCanJump;
  bool mCollisionTest;
  float mCollisionTestPrecision;
  float mRotateVelocity;
  bool mSetRotateVelocity;
  Vec3 mExtendDistance;
  std::string mVipFormatName;
  NameTagInfo mVipNameTagInfo;
  std::string mNameTagName;
  NameTagInfo mNameTagNameInfo;
  float mMaxExhaustionValue;
  int mHealthTick;
  int mHealthLevel;
  bool mNaturalRegen;
  int mStarveTick;
  int mStarveLevel;
  bool mNaturalStarve;
  unsigned int mGrowthLevel;
  bool mR5DataRecoverComplete;
  std::string mDeviceId;
  bool mUsingModSkin;
  bool mFlagClientForBAIReset;
  bool mOverrideHeightToWidth;
  BedHelper mBedHelper;
};

```

### `PlayerFogPacket`
```
const struct __cppobj PlayerFogPacket : Packet
{
  std::vector<std::string> mFogStack;
};

```

### `PlayerFogPacket_vtbl`
```
struct /*VFT*/ PlayerFogPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerEnchantOptionsPacket`
```
const struct __cppobj PlayerEnchantOptionsPacket : Packet
{
  std::vector<ItemEnchantOption> mOptions;
};

```

### `PlayerEnchantOptionsPacket_vtbl`
```
struct /*VFT*/ PlayerEnchantOptionsPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PhotoTransferPacket`
```
const struct __cppobj PhotoTransferPacket : Packet
{
  std::string mPhotoName;
  std::string mPhotoData;
  std::string mBookId;
};

```

### `PhotoTransferPacket_vtbl`
```
struct /*VFT*/ PhotoTransferPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerSkinPacket`
```
const struct __cppobj PlayerSkinPacket : Packet
{
  mce::UUID mUUID;
  SerializedSkin mSkin;
  std::string mLocalizedNewSkinName;
  std::string mLocalizedOldSkinName;
};

```

### `PlayerSkinPacket_vtbl`
```
struct /*VFT*/ PlayerSkinPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PurchaseReceiptPacket`
```
const struct __cppobj PurchaseReceiptPacket : Packet
{
  std::vector<std::string> mPurchaseRecipts;
};

```

### `PurchaseReceiptPacket_vtbl`
```
struct /*VFT*/ PurchaseReceiptPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlaySoundPacket`
```
const struct __cppobj __declspec(align(8)) PlaySoundPacket : Packet
{
  std::string mName;
  NetworkBlockPosition mPos;
  float mVolume;
  float mPitch;
};

```

### `PlaySoundPacket_vtbl`
```
struct /*VFT*/ PlaySoundPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerListPacket_vtbl`
```
struct /*VFT*/ PlayerListPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerInputPacket`
```
const struct __cppobj __declspec(align(8)) PlayerInputPacket : Packet
{
  Vec2 mMov;
  bool mIsJumping;
  bool mIsSneaking;
};

```

### `PlayerInputPacket_vtbl`
```
struct /*VFT*/ PlayerInputPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerAuthInputPacket`
```
const struct __cppobj PlayerAuthInputPacket : Packet
{
  Vec2 mRot;
  Vec3 mPos;
  float mYHeadRot;
  Vec3 mPosDelta;
  bool mCameraDeparted;
  bool mThirdPersonPerspective;
  Vec2 mPlayerRotationToCamera;
  Vec2 mMove;
  Vec3 mGazeDir;
  std::bitset<37> mInputData;
  InputMode mInputMode;
  ClientPlayMode mPlayMode;
  unsigned __int64 mClientTick;
  std::unique_ptr<PackedItemUseLegacyInventoryTransaction> mItemUseTransaction;
  std::unique_ptr<ItemStackRequestData> mItemStackRequest;
  PlayerBlockActions mPlayerBlockActions;
};

```

### `PlayerAuthInputPacket_vtbl`
```
struct /*VFT*/ PlayerAuthInputPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerHotbarPacket`
```
const struct __cppobj __declspec(align(4)) PlayerHotbarPacket : Packet
{
  unsigned int mSelectedSlot;
  bool mShouldSelectSlot;
  ContainerID mContainerId;
};

```

### `PlayerHotbarPacket_vtbl`
```
struct /*VFT*/ PlayerHotbarPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerArmorDamagePacket`
```
const struct __cppobj __declspec(align(8)) PlayerArmorDamagePacket : Packet
{
  std::bitset<4> mSlots;
  std::array<short,4> mDamages;
};

```

### `PlayerArmorDamagePacket_vtbl`
```
struct /*VFT*/ PlayerArmorDamagePacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PlayerActionPacket`
```
const struct __cppobj PlayerActionPacket : Packet
{
  NetworkBlockPosition mPos;
  int mFace;
  _BYTE mAction[4];
  ActorRuntimeID mRuntimeId;
};

```

### `PlayerActionPacket_vtbl`
```
struct /*VFT*/ PlayerActionPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `param_encode::EValue_vtbl`
```
struct /*VFT*/ param_encode::EValue_vtbl
{
  void (__fastcall *~EValue)(param_encode::EValue *this);
};

```

### `param_encode::EByte_vtbl`
```
struct /*VFT*/ param_encode::EByte_vtbl
{
  void (__fastcall *~EValue)(param_encode::EValue *this);
};

```

### `PermissionsHandler`
```
struct __cppobj PermissionsHandler
{
  _BYTE mCommandPermissions[1];
  param_encode::EByte mPlayerPermissions;
};

```

### `param_encode::EBool_vtbl`
```
struct /*VFT*/ param_encode::EBool_vtbl
{
  void (__fastcall *~EValue)(param_encode::EValue *this);
};

```

### `PlayStatusPacket`
```
const struct __cppobj __declspec(align(8)) PlayStatusPacket : Packet
{
  PlayStatus mStatus;
};

```

### `PlayStatusPacket_vtbl`
```
struct /*VFT*/ PlayStatusPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PositionTrackingDBServerBroadcastPacket`
```
const struct __cppobj PositionTrackingDBServerBroadcastPacket : Packet
{
  _BYTE mAction[1];
  PositionTrackingId mId;
  CompoundTag mData;
};

```

### `PositionTrackingDBServerBroadcastPacket_vtbl`
```
struct /*VFT*/ PositionTrackingDBServerBroadcastPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PositionTrackingDBClientRequestPacket`
```
const struct __cppobj PositionTrackingDBClientRequestPacket : Packet
{
  PositionTrackingDBClientRequestPacket::Action mAction;
  PositionTrackingId mId;
};

```

### `PositionTrackingDBClientRequestPacket_vtbl`
```
struct /*VFT*/ PositionTrackingDBClientRequestPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PacketViolationWarningPacket`
```
const struct __cppobj PacketViolationWarningPacket : Packet
{
  _BYTE mViolationType[4];
  _BYTE mViolationSeverity[4];
  MinecraftPacketIds mViolatingPacketId;
  std::string mViolationContext;
};

```

### `PacketViolationWarningPacket_vtbl`
```
struct /*VFT*/ PacketViolationWarningPacket_vtbl
{
  void (__fastcall *~Packet)(Packet *this);
  MinecraftPacketIds (__fastcall *getId)(Packet *this);
  std::string *(__fastcall *getName)(Packet *this, std::string *result);
  void (__fastcall *write)(Packet *this, BinaryStream *);
  StreamReadResult (__fastcall *read)(Packet *this, ReadOnlyBinaryStream *);
  ExtendedStreamReadResult *(__fastcall *readExtended)(Packet *this, ExtendedStreamReadResult *result, ReadOnlyBinaryStream *);
  bool (__fastcall *disallowBatching)(Packet *this);
};

```

### `PacketObserver_vtbl`
```
struct /*VFT*/ PacketObserver_vtbl
{
  void (__fastcall *~PacketObserver)(PacketObserver *this);
  void (__fastcall *packetSentTo)(PacketObserver *this, const NetworkIdentifier *, const Packet *, unsigned int);
  void (__fastcall *packetReceivedFrom)(PacketObserver *this, const NetworkIdentifier *, const Packet *, unsigned int);
  void (__fastcall *dataSentTo)(PacketObserver *this, const NetworkIdentifier *, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *dataReceivedFrom)(PacketObserver *this, const NetworkIdentifier *, const std::string *);
};

```

### `PacketSender`
```
struct __cppobj __declspec(align(8)) PacketSender
{
  PacketSender_vtbl *__vftable /*VFT*/;
  unsigned __int8 mSenderSubId;
};

```

### `PacketSender_vtbl`
```
struct /*VFT*/ PacketSender_vtbl
{
  void (__fastcall *~PacketSender)(PacketSender *this);
  void (__fastcall *send)(PacketSender *this, Packet *);
  void (__fastcall *sendToServer)(PacketSender *this, Packet *);
  void (__fastcall *sendToClient)(PacketSender *this, const NetworkIdentifier *, const Packet *, unsigned __int8);
  void (__fastcall *sendToClients)(PacketSender *this, const std::vector<NetworkIdentifierWithSubId> *, const Packet *);
  void (__fastcall *sendBroadcast)(PacketSender *this, const NetworkIdentifier *, unsigned __int8, const Packet *);
  void (__fastcall *sendBroadcast)(PacketSender *this, const Packet *);
  void (__fastcall *flush)(PacketSender *this, const NetworkIdentifier *, std::function<void __cdecl(void)> *);
};

```

### `PackManifest_vtbl`
```
struct /*VFT*/ PackManifest_vtbl
{
  void (__fastcall *~PackManifest)(PackManifest *this);
  std::unique_ptr<PackManifest> *(__fastcall *clone)(PackManifest *this, std::unique_ptr<PackManifest> *result);
};

```

### `PackAccessStrategy`
```
struct __cppobj PackAccessStrategy
{
  PackAccessStrategy_vtbl *__vftable /*VFT*/;
  bool isVipTransformSkin;
  bool mAssetSetPopulated;
  std::unordered_set<Core::PathBuffer<std::string >> mAssetSet;
};

```

### `PackAccessStrategy_vtbl`
```
struct /*VFT*/ PackAccessStrategy_vtbl
{
  void (__fastcall *~PackAccessStrategy)(PackAccessStrategy *this);
  unsigned __int64 (__fastcall *getPackSize)(PackAccessStrategy *this);
  const ResourceLocation *(__fastcall *getPackLocation)(PackAccessStrategy *this);
  const std::string *(__fastcall *getPackName)(PackAccessStrategy *this);
  bool (__fastcall *isWritable)(PackAccessStrategy *this);
  void (__fastcall *setIsTrusted)(PackAccessStrategy *this, bool);
  bool (__fastcall *isTrusted)(PackAccessStrategy *this);
  bool (__fastcall *hasAsset)(PackAccessStrategy *this, const Core::Path *, bool);
  bool (__fastcall *hasFolder)(PackAccessStrategy *this, const Core::Path *);
  bool (__fastcall *getAsset)(PackAccessStrategy *this, const Core::Path *, std::string *, bool);
  bool (__fastcall *deleteAsset)(PackAccessStrategy *this, const Core::PathBuffer<std::string > *);
  bool (__fastcall *writeAsset)(PackAccessStrategy *this, const Core::Path *, const std::string *);
  void (__fastcall *forEachIn)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>, bool);
  void (__fastcall *forEachInAssetSet)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>);
  PackAccessStrategyType (__fastcall *getStrategyType)(PackAccessStrategy *this);
  const Core::PathBuffer<std::string > *(__fastcall *getSubPath)(PackAccessStrategy *this);
  std::unique_ptr<PackAccessStrategy> *(__fastcall *createSubPack)(PackAccessStrategy *this, std::unique_ptr<PackAccessStrategy> *result, const Core::Path *);
  PackAccessAssetGenerationResult (__fastcall *generateAssetSet)(PackAccessStrategy *this);
  bool (__fastcall *canRecurse)(PackAccessStrategy *this);
  void (__fastcall *unload)(PackAccessStrategy *this);
  __int64 (__fastcall *getLastModifiedTime)(PackAccessStrategy *this, const Core::Path *);
  std::unique_ptr<IDataOutput> *(__fastcall *createEncryptor)(PackAccessStrategy *this, std::unique_ptr<IDataOutput> *result, std::unique_ptr<IDataOutput>);
  std::unique_ptr<IDataInput> *(__fastcall *createDecryptor)(PackAccessStrategy *this, std::unique_ptr<IDataInput> *result, std::unique_ptr<IDataInput>);
  bool (__fastcall *hasUpgradeFiles)(PackAccessStrategy *this);
  ContentIdentity *(__fastcall *readContentIdentity)(PackAccessStrategy *this, ContentIdentity *result);
  bool (__fastcall *hasFile)(PackAccessStrategy *this, const Core::Path *);
  void (__fastcall *setSubPathAsPackName)(PackAccessStrategy *this);
};

```

### `PackMetadata`
```
struct __cppobj PackMetadata
{
  std::unique_ptr<EducationMetadata> mEducationMetadata;
};

```

### `Pack`
```
struct __cppobj Pack
{
  std::unique_ptr<PackManifest> mManifest;
  std::unique_ptr<PackAccessStrategy> mAccessStrategy;
  std::unique_ptr<SubpackInfoCollection> mSubpackInfoStack;
  std::unique_ptr<PackMetadata> mMetadata;
  std::map<void *,std::function<void __cdecl(Pack &)>> mPackUpdatedCallbacks;
  std::map<void *,std::function<void __cdecl(Pack &)>> mPackDeletedCallbacks;
};

```

### `PackError_vtbl`
```
struct /*VFT*/ PackError_vtbl
{
  void (__fastcall *~PackError)(PackError *this);
  std::string *(__fastcall *getLocErrorMessage)(PackError *this, std::string *result);
  const std::unordered_map<int,std::string> *(__fastcall *getLocErrorMessageMap)(PackError *this);
  const std::unordered_map<int,std::string> *(__fastcall *getEventErrorMessageMap)(PackError *this);
};

```

### `PackSource`
```
struct __cppobj PackSource
{
  PackSource_vtbl *__vftable /*VFT*/;
};

```

### `PackManifestFactory`
```
struct __cppobj PackManifestFactory
{
  IPackTelemetry *mEventing;
};

```

### `PackSource_vtbl`
```
struct /*VFT*/ PackSource_vtbl
{
  void (__fastcall *~PackSource)(PackSource *this);
  void (__fastcall *forEachPackConst)(PackSource *this, std::function<void __cdecl(Pack const &)>);
  void (__fastcall *forEachPack)(PackSource *this, std::function<void __cdecl(Pack &)>);
  PackOrigin (__fastcall *getPackOrigin)(PackSource *this);
  PackType (__fastcall *getPackType)(PackSource *this);
  PackSourceReport *(__fastcall *load)(PackSource *this, PackSourceReport *result, PackManifestFactory *, const IContentKeyProvider *);
  void (__fastcall *addPackSource)(PackSource *this, PackSource *);
};

```

### `PackSettingObserver`
```
struct __cppobj PackSettingObserver
{
  void *mToken;
  std::function<void __cdecl(Json::Value const &)> mChangeCallback;
};

```

### `PackSetting`
```
struct __cppobj PackSetting
{
  Json::Value *mValue;
  std::vector<PackSettingObserver> mObservers;
};

```

### `PackSettings`
```
struct __cppobj PackSettings
{
  Json::Value mSettings;
  std::unordered_map<std::string,PackSetting> mPackSettings;
};

```

### `PackStorageMetrics`
```
struct __cppobj __declspec(align(8)) PackStorageMetrics
{
  unsigned __int64 mMisses;
  unsigned __int64 mHits;
  unsigned __int64 mBadFiles;
  unsigned __int64 mFiles;
  bool mHasStream;
  bool mWantsToWrite;
};

```

### `PlayerRespawnTelemetryData`
```
const struct __cppobj __declspec(align(4)) PlayerRespawnTelemetryData
{
  unsigned int mSearchTimeMS;
  unsigned int mLongJumpCount;
  unsigned int mShortJumpCount;
  long double mJumpDistance;
  unsigned int mPositionSourceType;
  bool mChangedDimension;
};

```

### `ProductInfo`
```
struct __cppobj ProductInfo
{
  ProductSku mSku;
  std::string mPriceInCurrency;
  std::string mCurrencyCode;
  std::string mUnformattedPriceInCurrency;
};

```

### `PurchaseInfo`
```
struct __cppobj __declspec(align(4)) PurchaseInfo
{
  ProductSku mProductSku;
  std::string mPlatformPurchaseId;
  std::string mReceipt;
  std::string mCorrelationId;
  _BYTE mPurchasePath[4];
  bool mActive;
  bool mRenewal;
};

```

### `Purchase`
```
struct __cppobj Purchase
{
  PurchaseInfo mInfo;
  Fulfillment mFulfillment;
  int mFulfillmentAttempts;
};

```

### `Particle`
```
struct __cppobj __declspec(align(8)) Particle
{
  Particle_vtbl *__vftable /*VFT*/;
  float mCameraOffset;
  int mLifetime;
  TextureUVCoordinateSet mTex;
  float mU0;
  float mV0;
  int mAge;
  int mTicksSinceLastUpdate;
  float size;
  float mGravity;
  mce::Color mColor;
  mce::Color mLightColor;
  ParticleType mType;
  ParticleLayer mLayer;
  bool mUnlit;
  float mRoll;
  float mORoll;
  float mXa;
  float mZa;
  float mXa2;
  float mZa2;
  float mYa;
  BlockSource *mRegion;
  Vec3 mPosDelta;
  Vec3 mPos;
  Vec3 mPosOld;
  bool mNoPhysics;
  bool mOnGround;
  bool mVertexDataInitialized;
  AABB mBB;
};

```

### `ParticleEngine`
```
struct __cppobj ParticleEngine
{
  std::vector<std::unique_ptr<Particle>> mInactiveParticlesPool[73];
  Level *mLevel;
  std::unordered_map<mce::TexturePtr,std::vector<std::unique_ptr<Particle>>> mActiveParticles[73];
  std::vector<std::unique_ptr<CustomParticle>> customParticles;
  std::vector<std::unique_ptr<Particle>> mNewParticles;
  SeasonsRenderer *mSeasons;
  LightTexture *mLightTexture;
  Random random;
  mce::MaterialPtr opaqueMat;
  mce::MaterialPtr alphaTestMat;
  mce::MaterialPtr blendMat;
  unsigned int maxParticleCount[73];
  unsigned int particleCount[73];
  bool mTemporaryCameraActive;
  std::unordered_map<enum ParticleType,HashedString> mNewParticleSystemJsonLookup;
  std::unordered_map<enum ParticleType,int> mNewParticleSystemMap;
};

```

### `PacketHeader::<unnamed_type_mData>::<unnamed_type_mBits>`
```
struct PacketHeader::<unnamed_type_mData>::<unnamed_type_mBits>
{
  unsigned __int32 mPacketId : 10;
  unsigned __int32 mSenderSubId : 2;
  unsigned __int32 mClientSubId : 2;
};

```

### `PacketHeader`
```
const struct __cppobj PacketHeader
{
  PacketHeader::<unnamed_type_mData> mData;
};

```

### `PrivateKeyManager_vtbl`
```
struct /*VFT*/ PrivateKeyManager_vtbl
{
  void (__fastcall *~KeyManager)(KeyManager *this);
  bool (__fastcall *isValid)(KeyManager *this);
};

```

### `PermissionsFile`
```
struct __cppobj PermissionsFile
{
  const Core::PathBuffer<std::string > mFilePath;
  std::unordered_map<std::string,enum PlayerPermissionLevel> mPermissions;
};

```

### `PackSourceFactory::RealmsUnknownPackSources`
```
struct __cppobj PackSourceFactory::RealmsUnknownPackSources
{
  std::unique_ptr<RealmsUnknownPackSource> realmsUnknownResourcePackSource;
  std::unique_ptr<RealmsUnknownPackSource> realmsUnknownBehaviorPackSource;
};

```

### `PackSourceFactory`
```
struct __cppobj PackSourceFactory : IPackSourceFactory
{
  std::vector<std::unique_ptr<ContentCatalogPackSource>> mContentCatalogPackSources;
  std::vector<std::unique_ptr<TreatmentPackSource>> mTreatmentPackSources;
  std::vector<std::unique_ptr<DirectoryPackSource>> mDirectoryPackSources;
  std::vector<std::unique_ptr<InPackagePackSource>> mInPackagePackSources;
  std::vector<std::unique_ptr<WorldHistoryPackSource>> mWorldHistoryPackSources;
  std::vector<std::unique_ptr<WorldTemplatePackSource>> mWorldTemplatePackSources;
  std::vector<std::unique_ptr<InPackagePackSource>> mDynamicPackagePackSources;
  PackSourceFactory::RealmsUnknownPackSources mRealmsUnknownPackSources;
  std::shared_ptr<IInPackagePacks> mInPackagePacksProvider;
  std::shared_ptr<IDynamicPackagePacks> mDynamicPackagePacksProvider;
};

```

### `PackSourceFactory_vtbl`
```
struct /*VFT*/ PackSourceFactory_vtbl
{
  void (__fastcall *~IPackSourceFactory)(IPackSourceFactory *this);
  ContentCatalogPackSource *(__fastcall *createContentCatalogPackSource)(IPackSourceFactory *this, const gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > *, IEntitlementManager *, bool, std::function<void __cdecl(bool)>);
  ContentCatalogPackSource *(__fastcall *getContentCatalogPackSource)(IPackSourceFactory *this);
  TreatmentPackSource *(__fastcall *createTreatmentPackSource)(IPackSourceFactory *this, const Core::Path *, PackType);
  TreatmentPackSource *(__fastcall *getTreatmentPackSource)(IPackSourceFactory *this, const Core::Path *, PackType);
  void (__fastcall *removeFromTreatmentPackSource)(IPackSourceFactory *this, const Core::Path *);
  WorldTemplatePackSource *(__fastcall *createWorldTemplatePackSource)(IPackSourceFactory *this, const WorldTemplateManager *, const mce::UUID *, PackType, PackOrigin);
  WorldTemplatePackSource *(__fastcall *getWorldTemplatePackSource)(IPackSourceFactory *this, const mce::UUID *, PackType);
  DirectoryPackSource *(__fastcall *createDirectoryPackSource)(IPackSourceFactory *this, const Core::Path *, PackType, PackOrigin, bool);
  DirectoryPackSource *(__fastcall *getDirectoryPackSource)(IPackSourceFactory *this, const Core::Path *, PackType);
  InPackagePackSource *(__fastcall *createInPackagePackSource)(IPackSourceFactory *this, PackType);
  InPackagePackSource *(__fastcall *getInPackagePackSource)(IPackSourceFactory *this, PackType);
  WorldHistoryPackSource *(__fastcall *createWorldHistoryPackSource)(IPackSourceFactory *this, const Core::Path *, PackType);
  WorldHistoryPackSource *(__fastcall *getWorldHistoryPackSource)(IPackSourceFactory *this, const Core::Path *, PackType);
  DirectoryPackSource *(__fastcall *getDirectoryPackSourceContaining)(IPackSourceFactory *this, const PackIdVersion *);
  void (__fastcall *removeFromDirectoryPackSource)(IPackSourceFactory *this, const Core::Path *);
  InPackagePackSource *(__fastcall *createDynamicPackagePackSource)(IPackSourceFactory *this, PackType);
  InPackagePackSource *(__fastcall *getDynamicPackagePackSource)(IPackSourceFactory *this, PackType);
  void (__fastcall *setDynamicPackagePacks)(IPackSourceFactory *this, const std::shared_ptr<IDynamicPackagePacks> *);
  void (__fastcall *setDynamicPackageRoot)(IPackSourceFactory *this, Core::PathBuffer<std::string >);
};

```

### `PromoInfo`
```
struct __cppobj PromoInfo
{
  unsigned int mNumberOfOffers;
  std::string mComingSoon;
  std::string mNoPromoOffersLeft;
  std::string mPromoOfferOpened;
  std::string mPromoOfferUnopened;
  std::string mUnlockDate;
};

```

### `PromoComponent`
```
struct __cppobj PromoComponent : StoreUIComponent
{
  PromoInfo mPromoInfo;
};

```

### `PromoComponent_vtbl`
```
struct /*VFT*/ PromoComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `PackIdentityUUIDHash`
```
struct __cppobj PackIdentityUUIDHash
{
};

```

### `PackIdentityUUIDEquality`
```
struct __cppobj PackIdentityUUIDEquality
{
};

```

### `PlayerAutomationObserver`
```
struct __cppobj PlayerAutomationObserver : Automation::AutomationObserver
{
  LocalPlayer *mPlayer;
};

```

### `PlayerAutomationObserver_vtbl`
```
struct /*VFT*/ PlayerAutomationObserver_vtbl
{
  void (__fastcall *~Observer<Automation::AutomationObserver,Core::SingleThreadedLock>)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onConnected)(Automation::AutomationObserver *this, const std::string *);
  void (__fastcall *onConnectionFailed)(Automation::AutomationObserver *this, const std::string *);
  void (__fastcall *onConnectionClosed)(Automation::AutomationObserver *this);
  void (__fastcall *onDuplicateRequestCancel)(Automation::AutomationObserver *this);
};

```

### `ParticleEffectGroup`
```
struct __cppobj ParticleEffectGroup
{
  std::mutex mParticleEffectInfoLock;
};

```

### `PatchInfo`
```
struct __cppobj __declspec(align(8)) PatchInfo
{
  Core::PathBuffer<std::string > mPatchImagePath;
  std::unordered_map<std::string,std::string> mPatchTitles;
  Core::PathBuffer<std::string > mPatchNotesLocation;
  std::string mOfferProductId;
  std::string mOfferName;
  Core::PathBuffer<std::string > mOfferImagePath;
  std::string mVersionString;
  bool mLoadedDescription;
  bool mLoadOnlyDescription;
  bool mSkipped;
  bool mHasFailed;
  bool mCanDisplayOffer;
  bool mFound;
  PatchRequestSource mSource;
};

```

### `PatchNotesManager`
```
struct __cppobj PatchNotesManager
{
  bool mShowPatchNotesScreenNeeded;
  bool mHasFetched;
  bool mFinishedPatchNotesQuery;
  std::shared_ptr<Options> mOptions;
  std::shared_ptr<CatalogInfo> mCatalogInfo;
  std::unique_ptr<ContentCatalogService> mContentCatalogService;
  std::vector<PatchInfo> mPatchNotes;
  std::string mLatestVersion;
  std::string mLatestPatchRevision;
  std::string mDocumentId;
};

```

### `PersonaRepository`
```
struct __cppobj PersonaRepository : std::enable_shared_from_this<PersonaRepository>
{
  bool mInitialized;
  MinecraftGraphics *mMinecraftGraphics;
  std::shared_ptr<SkinRepository> mSkinRepository;
  IPackSourceFactory *mPackSourceFactory;
  IMinecraftGame *mMinecraft;
  std::unique_ptr<SkinPackKeyProvider> mKeyProvider;
  std::shared_ptr<GeometryGroup> mSkinGeometryGroup;
  ResourcePackManager *mResourcePackManager;
  ResourcePackRepository *mResourcePackRepository;
  PackManifestFactory *mPackManifestFactory;
  std::unique_ptr<TextureHotReloader> mTextureHotReloader;
  std::unique_ptr<mce::TextureGroup> mTextureGroup;
  std::map<std::string,std::shared_ptr<PersonaPiece>> mPersonaPieceRepo;
  std::mutex mPersonaPieceRepoLock;
  std::vector<std::vector<std::string>> mPersonaPieceByType;
  persona::PersonaPieceCollectionEventManager *mCollectionEventManager;
  std::mutex mEmoteParseLock;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::deque<Pack *> mPendingLoadsQueue;
  std::set<mce::UUID> mPendingLoadsLookup;
  std::set<mce::UUID> mLoadingPacks;
  std::set<mce::UUID> mAllEmotePieceIds;
  std::unordered_map<unsigned int,PersonaRepository::PendingPersonaAppearance> mLoadingPersonaAppearances;
  std::mutex mLoadingPersonaAppearancesLock;
  std::unordered_map<HashedString,PersonaCharacter> mPersonaCharacters;
  std::unordered_map<HashedString,PersonaCharacter> mCachedCharacters;
  std::unordered_map<mce::UUID,SemVersion> mKnownPersonaPiecePackIdentities;
  std::unique_ptr<PackSource> mAllPersonaPiecePacksSource;
  unsigned int mPersonaSkinCount;
  std::vector<PersonaRepository::PendingPieceDownloadBatch> mPendingPieceDownloadBatches;
  std::unordered_set<mce::UUID> mAllQueuedPieceDownloads;
  bool mInitializationEventFired;
  std::array<PersonaAppearance,2> mDefaultPersonas;
  std::unordered_map<ResourceLocation,std::string> mLocationPieceIdMap;
  std::set<std::string> mLoadedTexturePieces;
  std::vector<std::string> mPendingLoadTexturePieces;
  std::set<std::string> mLoadingTexturePieces;
};

```

### `persona::PersonaStoreItemCollector_vtbl`
```
struct /*VFT*/ persona::PersonaStoreItemCollector_vtbl
{
  void (__fastcall *~PersonaStoreItemCollector)(persona::PersonaStoreItemCollector *this);
  void (__fastcall *start)(persona::PersonaStoreItemCollector *this, const gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > *, const gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > *, std::vector<persona::PieceOfferWrapper> *, const bool);
  bool (__fastcall *isExhausted)(persona::PersonaStoreItemCollector *this);
  void (__fastcall *handleVisibleRange)(persona::PersonaStoreItemCollector *this, const gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > *, const gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > *);
  void (__fastcall *checkDownloadStatus)(persona::PersonaStoreItemCollector *this, const PersonaRepository *);
  void (__fastcall *clearSelectionCallback)(persona::PersonaStoreItemCollector *this);
  void (__fastcall *collect)(persona::PersonaStoreItemCollector *this, PersonaRepository *, DlcBatchCacheModel *, std::unordered_map<mce::UUID,StoreCatalogItem *> *);
  bool (__fastcall *collectOffer)(persona::PersonaStoreItemCollector *this, PersonaRepository *, DlcBatchCacheModel *, const persona::PieceOfferWrapper *, std::function<void __cdecl(bool)>);
  bool (__fastcall *isDirty)(persona::PersonaStoreItemCollector *this);
};

```

### `persona::DlcImportTracker`
```
struct __cppobj persona::DlcImportTracker
{
  std::unique_ptr<DlcBatchModel> mBatchModel;
  std::function<void __cdecl(bool)> mCallback;
  mce::UUID mPieceId;
};

```

### `persona::PersonaPieceCollectionEventManager`
```
struct __cppobj persona::PersonaPieceCollectionEventManager
{
  std::unordered_map<persona::PersonaStoreItemCollector const *,persona::PersonaPieceCollectionEventManager::LoadingStats> mLoadingStats;
  IMinecraftEventing *mEventing;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  PersonaRepository *mPersonaRepository;
};

```

### `persona::PersonaPieceCollectionEventManager::LoadingStats`
```
struct __cppobj __declspec(align(8)) persona::PersonaPieceCollectionEventManager::LoadingStats
{
  std::vector<mce::UUID> mExpectedItemsToLoad;
  __int64 mStartLoadingTime;
  long double mTotalTimeSpentLoading;
  unsigned int mTotalPiecesLoaded;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  bool mEventTriggered;
};

```

### `PersonaAppearance_vtbl`
```
struct /*VFT*/ PersonaAppearance_vtbl
{
  void (__fastcall *~PersonaAppearance)(PersonaAppearance *this);
};

```

### `ParsedAtlasNode`
```
struct __cppobj ParsedAtlasNode
{
  std::string mName;
  bool mQuad;
  std::vector<std::vector<ParsedAtlasNodeElement>> mElementCollections;
};

```

### `PersonaRepository::PendingPieceDownloadBatch`
```
struct __cppobj PersonaRepository::PendingPieceDownloadBatch
{
  std::vector<std::string> mPieceIds;
  std::shared_ptr<DlcBatchModel> mDlcBatch;
};

```

### `PlayerCommandOrigin`
```
struct __cppobj PlayerCommandOrigin : CommandOrigin
{
  ActorUniqueID mPlayerId;
  Level *mLevel;
};

```

### `PlatformUpsellDialog`
```
struct __cppobj PlatformUpsellDialog
{
  PlatformUpsellDialog_vtbl *__vftable /*VFT*/;
};

```

### `PlatformUpsellDialog_vtbl`
```
struct /*VFT*/ PlatformUpsellDialog_vtbl
{
  void (__fastcall *~PlatformUpsellDialog)(PlatformUpsellDialog *this);
  void (__fastcall *show)(PlatformUpsellDialog *this, const std::shared_ptr<Social::User>, std::function<void __cdecl(bool)>);
};

```

### `PlatformStoreIconModel::PlatformStoreIconVisibility`
```
struct __cppobj PlatformStoreIconModel::PlatformStoreIconVisibility
{
  bool mIsInGameBrowsing;
  bool mIsCheckoutInProgress;
};

```

### `PlayerListener`
```
struct __cppobj PlayerListener
{
  PlayerListener_vtbl *__vftable /*VFT*/;
};

```

### `PlayerListener_vtbl`
```
struct /*VFT*/ PlayerListener_vtbl
{
  void (__fastcall *~PlayerListener)(PlayerListener *this);
  void (__fastcall *onWillChangeDimension)(PlayerListener *this, Player *);
  void (__fastcall *onDimensionChanged)(PlayerListener *this, Player *);
  void (__fastcall *onPlayerDestruction)(PlayerListener *this, Player *);
};

```

### `ParticleSystem::EffectComponentBase`
```
struct __cppobj ParticleSystem::EffectComponentBase
{
  ParticleSystem::EffectComponentBase_vtbl *__vftable /*VFT*/;
  HashedString mName;
};

```

### `ParticleSystem::EffectComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::EffectComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
};

```

### `ParticleSystem::ParticleEmitter`
```
struct __cppobj ParticleSystem::ParticleEmitter
{
  ParticleSystem::ParticleEmitter_vtbl *__vftable /*VFT*/;
};

```

### `ParticleRenderData::ParticleData`
```
struct __cppobj ParticleRenderData::ParticleData
{
  mce::Color mColor;
  Vec2 mUV0;
  Vec2 mUV1;
  Vec3 mWorldPos;
  Vec3 mParticleDirection;
  Vec2 mSize;
  Vec4 mRandomNumbers;
  float mRotation;
  unsigned __int16 mTextureIdx;
  unsigned __int16 mMaterialIdx;
  _BYTE mFaceCameraMode[4];
  Matrix mCustomOrientation;
};

```

### `ParticleRenderData`
```
struct __cppobj ParticleRenderData
{
  std::vector<ParticleRenderData::ParticleData> mParticles;
  std::vector<mce::TexturePtr> mTexturesList;
  std::vector<mce::MaterialPtr> mMaterialsList;
  std::unordered_map<HashedString,unsigned short> mTexturesMap;
  std::unordered_map<HashedString,unsigned short> mMaterialsMap;
};

```

### `ParticleSystem::ActorBindInfo`
```
struct __cppobj __declspec(align(8)) ParticleSystem::ActorBindInfo
{
  ActorUniqueID mActorId;
  HashedString mLocator;
  Dimension *mDimension;
  Vec3 mOffset;
};

```

### `ParticleSystem::ParticleEmitter_vtbl`
```
struct /*VFT*/ ParticleSystem::ParticleEmitter_vtbl
{
  void (__fastcall *~ParticleEmitter)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *setActorBindInfo)(ParticleSystem::ParticleEmitter *this, Dimension *, ActorUniqueID, const HashedString *, const Vec3 *);
  void (__fastcall *setEnableUpdate)(ParticleSystem::ParticleEmitter *this, bool);
  void (__fastcall *setEnableRender)(ParticleSystem::ParticleEmitter *this, bool);
  void (__fastcall *runInitializationScript)(ParticleSystem::ParticleEmitter *this, const ExpressionNode *);
  void (__fastcall *onBlockChanged)(ParticleSystem::ParticleEmitter *this, const BlockPos *);
  void (__fastcall *expire)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *emitParticleManually)(ParticleSystem::ParticleEmitter *this, const Vec3 *, const Vec3 *, const float);
  bool (__fastcall *isValid)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *isManualEmitter)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *expirationRequested)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *hasExpired)(ParticleSystem::ParticleEmitter *this);
  const AABB *(__fastcall *getAABB)(ParticleSystem::ParticleEmitter *this);
  const ParticleEffectPtr *(__fastcall *getEffect)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getParticleCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getEffectEmitterCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getEffectParticleCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getTotalEmitterCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getTotalParticleCount)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *handleExpireManually)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *tick)(ParticleSystem::ParticleEmitter *this, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *, const float);
  void (__fastcall *frameUpdate)(ParticleSystem::ParticleEmitter *this, ClientFrameUpdateContext *);
  void (__fastcall *extractForRendering)(ParticleSystem::ParticleEmitter *this, ParticleRenderData *, float);
  void (__fastcall *setManualParticleEmission)(ParticleSystem::ParticleEmitter *this, bool);
  ParticleSystem::ActorBindInfo *(__fastcall *getActorBindInfo)(ParticleSystem::ParticleEmitter *this, ParticleSystem::ActorBindInfo *result);
};

```

### `ParticleSystem::ComponentAccessParticleEmitter`
```
struct __cppobj ParticleSystem::ComponentAccessParticleEmitter : ParticleSystem::ParticleEmitter
{
  float mEmissionAccumulator;
  float mCurrentEmitRate;
};

```

### `ParticleSystem::CommonParticle`
```
struct __cppobj ParticleSystem::CommonParticle
{
  Vec3 mPosition;
  Vec3 mVelocity;
  Vec3 mDirection;
  float mRotation;
  float mRotationSpeed;
  Vec2 mRenderSize;
  Vec2 mUV[2];
  float mScale;
  mce::Color mColor;
  Vec3 mPositionPrev;
  Vec3 mVelocityPrev;
  Vec3 mDirectionPrev;
  float mRotationPrev;
  bool mDynamicPreviousDataValid;
  Vec2 mRenderSizePrev;
  float mScalePrev;
  mce::Color mColorPrev;
  bool mRenderPreviousDataValid;
  Vec4 mRandom;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mParticleLifetime;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mParticleAge;
};

```

### `ParticleSystem::ComponentAccessParticleEmitter_vtbl`
```
struct /*VFT*/ ParticleSystem::ComponentAccessParticleEmitter_vtbl
{
  void (__fastcall *~ParticleEmitter)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *setActorBindInfo)(ParticleSystem::ParticleEmitter *this, Dimension *, ActorUniqueID, const HashedString *, const Vec3 *);
  void (__fastcall *setEnableUpdate)(ParticleSystem::ParticleEmitter *this, bool);
  void (__fastcall *setEnableRender)(ParticleSystem::ParticleEmitter *this, bool);
  void (__fastcall *runInitializationScript)(ParticleSystem::ParticleEmitter *this, const ExpressionNode *);
  void (__fastcall *onBlockChanged)(ParticleSystem::ParticleEmitter *this, const BlockPos *);
  void (__fastcall *expire)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *emitParticleManually)(ParticleSystem::ParticleEmitter *this, const Vec3 *, const Vec3 *, const float);
  bool (__fastcall *isValid)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *isManualEmitter)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *expirationRequested)(ParticleSystem::ParticleEmitter *this);
  bool (__fastcall *hasExpired)(ParticleSystem::ParticleEmitter *this);
  const AABB *(__fastcall *getAABB)(ParticleSystem::ParticleEmitter *this);
  const ParticleEffectPtr *(__fastcall *getEffect)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getParticleCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getEffectEmitterCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getEffectParticleCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getTotalEmitterCount)(ParticleSystem::ParticleEmitter *this);
  unsigned __int64 (__fastcall *getTotalParticleCount)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *handleExpireManually)(ParticleSystem::ParticleEmitter *this);
  void (__fastcall *tick)(ParticleSystem::ParticleEmitter *this, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *, const float);
  void (__fastcall *frameUpdate)(ParticleSystem::ParticleEmitter *this, ClientFrameUpdateContext *);
  void (__fastcall *extractForRendering)(ParticleSystem::ParticleEmitter *this, ParticleRenderData *, float);
  void (__fastcall *setManualParticleEmission)(ParticleSystem::ParticleEmitter *this, bool);
  ParticleSystem::ActorBindInfo *(__fastcall *getActorBindInfo)(ParticleSystem::ParticleEmitter *this, ParticleSystem::ActorBindInfo *result);
  const Vec3 *(__fastcall *getPosition)(ParticleSystem::ComponentAccessParticleEmitter *this);
  const Matrix *(__fastcall *getTransform)(ParticleSystem::ComponentAccessParticleEmitter *this);
  const Vec3 *(__fastcall *getWorldPosition)(ParticleSystem::ComponentAccessParticleEmitter *this);
  const Vec3 *(__fastcall *getWorldVelocity)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *setMaxNumParticles)(ParticleSystem::ComponentAccessParticleEmitter *this, unsigned __int64);
  unsigned __int64 (__fastcall *getMaxNumParticles)(ParticleSystem::ComponentAccessParticleEmitter *this);
  unsigned __int64 (__fastcall *getNumParticles)(ParticleSystem::ComponentAccessParticleEmitter *this);
  unsigned __int64 (__fastcall *getNumParticlesEmitted)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *setActorFrameOfReference)(ParticleSystem::ComponentAccessParticleEmitter *this, bool, bool, bool);
  void (__fastcall *setEmitRate)(ParticleSystem::ComponentAccessParticleEmitter *this, float);
  float (__fastcall *getEmitRate)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *setEmissionDuration)(ParticleSystem::ComponentAccessParticleEmitter *this, float);
  float *(__fastcall *getEmissionAccumulator)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *setSleepDuration)(ParticleSystem::ComponentAccessParticleEmitter *this, float);
  void (__fastcall *setFacing)(ParticleSystem::ComponentAccessParticleEmitter *this, const HashedString *);
  bool (__fastcall *blockListInitialized)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *initializeBlockList)(ParticleSystem::ComponentAccessParticleEmitter *this, buffer_span<std::string >);
  bool (__fastcall *blockAtPositionIsInList)(ParticleSystem::ComponentAccessParticleEmitter *this, const BlockPos *);
  mce::Color *(__fastcall *getGamePlayLightAtBlock)(ParticleSystem::ComponentAccessParticleEmitter *this, mce::Color *result, const BlockPos *);
  const std::vector<AABB> *(__fastcall *getCollisionShapesForBlockPosition)(ParticleSystem::ComponentAccessParticleEmitter *this, const BlockPos *);
  std::vector<AABB> *(__fastcall *getCollisionAabbList)(ParticleSystem::ComponentAccessParticleEmitter *this);
  std::vector<ParticleSystem::ComponentAccessParticleEmitter::CollisionHelper> *(__fastcall *getCollisionSweepList)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *fireEvent)(ParticleSystem::ComponentAccessParticleEmitter *this, const HashedString *, const Matrix *, const Vec3 *);
  void (__fastcall *fireEvent)(ParticleSystem::ComponentAccessParticleEmitter *this, const HashedString *, const Vec3 *, const Vec3 *);
  bool (__fastcall *getUseActorPosition)(ParticleSystem::ComponentAccessParticleEmitter *this);
  bool (__fastcall *getUseActorRotation)(ParticleSystem::ComponentAccessParticleEmitter *this);
  void (__fastcall *getParticleWorldPositionAndVelocity)(ParticleSystem::ComponentAccessParticleEmitter *this, ParticleSystem::CommonParticle *, Vec3 *, Vec3 *);
};

```

### `ParticleSystem::EmitterInitialComponentBase`
```
struct __cppobj ParticleSystem::EmitterInitialComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::EmitterInitialComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::EmitterInitialComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *setupInitial)(ParticleSystem::EmitterInitialComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *);
  void (__fastcall *update)(ParticleSystem::EmitterInitialComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *);
};

```

### `ParticleSystem::EmitterLifetimeComponentBase`
```
struct __cppobj ParticleSystem::EmitterLifetimeComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::EmitterRateComponentBase`
```
struct __cppobj ParticleSystem::EmitterRateComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::EmitterRateComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::EmitterRateComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  unsigned __int64 (__fastcall *getNumberOfParticlesToEmit)(ParticleSystem::EmitterRateComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *);
  unsigned __int64 (__fastcall *getNumberOfManualParticlesAllowed)(ParticleSystem::EmitterRateComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *);
};

```

### `ParticleSystem::EmitterShapeComponentBase`
```
struct __cppobj ParticleSystem::EmitterShapeComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::EmitterShapeComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::EmitterShapeComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *getNextParticleSpawnOffsetAndDirection)(ParticleSystem::EmitterShapeComponentBase *this, Vec3 *, Vec3 *, const ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *);
};

```

### `ParticleSystem::ParticleAppearanceComponentBase`
```
struct __cppobj ParticleSystem::ParticleAppearanceComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::ParticleAppearanceComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::ParticleAppearanceComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *setInitialState)(ParticleSystem::ParticleAppearanceComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, ParticleSystem::CommonParticle *, RenderParams *, const Vec3 *);
  void (__fastcall *updateParticleAppearance)(ParticleSystem::ParticleAppearanceComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, ParticleSystem::CommonParticle *, RenderParams *);
  void (__fastcall *updateEmitterAppearance)(ParticleSystem::ParticleAppearanceComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, RenderParams *);
};

```

### `ParticleSystem::ParticleInitialComponentBase`
```
struct __cppobj ParticleSystem::ParticleInitialComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::ParticleInitialComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::ParticleInitialComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *setInitialState)(ParticleSystem::ParticleInitialComponentBase *this, ParticleSystem::CommonParticle *, RenderParams *);
  void (__fastcall *update)(ParticleSystem::ParticleInitialComponentBase *this, RenderParams *);
  void (__fastcall *renderPreparation)(ParticleSystem::ParticleInitialComponentBase *this, RenderParams *);
};

```

### `ParticleSystem::ParticleLifetimeComponentBase`
```
struct __cppobj ParticleSystem::ParticleLifetimeComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::ParticleMotionComponentBase`
```
struct __cppobj ParticleSystem::ParticleMotionComponentBase : ParticleSystem::EffectComponentBase
{
};

```

### `ParticleSystem::ParticleMotionComponentBase_vtbl`
```
struct /*VFT*/ ParticleSystem::ParticleMotionComponentBase_vtbl
{
  void (__fastcall *~EffectComponentBase)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *parseJson)(ParticleSystem::EffectComponentBase *this, const ConstDeserializeDataParams *);
  ParticleSystem::EffectComponentBase::EffectComponentType (__fastcall *getParticleComponentType)(ParticleSystem::EffectComponentBase *this);
  int (__fastcall *getSortOrderNumber)(ParticleSystem::EffectComponentBase *this);
  void (__fastcall *updateParticleMotion)(ParticleSystem::ParticleMotionComponentBase *this, ParticleSystem::ComponentAccessParticleEmitter *, ParticleSystem::CommonParticle *, RenderParams *, const std::chrono::duration<__int64,std::ratio<1,1000000000> > *);
};

```

### `ParticleSystem::ParticleCurveBase`
```
struct __cppobj ParticleSystem::ParticleCurveBase
{
  ParticleSystem::ParticleCurveBase_vtbl *__vftable /*VFT*/;
};

```

### `ParticleSystem::ParticleCurveBase_vtbl`
```
struct /*VFT*/ ParticleSystem::ParticleCurveBase_vtbl
{
  void (__fastcall *~ParticleCurveBase)(ParticleSystem::ParticleCurveBase *this);
  void (__fastcall *parseJson)(ParticleSystem::ParticleCurveBase *this, const ConstDeserializeDataParams *, const HashedString *);
  void (__fastcall *evaluateCurve)(ParticleSystem::ParticleCurveBase *this, RenderParams *);
};

```

### `ParticleSystem::ParticleEffect`
```
struct __cppobj __declspec(align(8)) ParticleSystem::ParticleEffect
{
  std::vector<std::unique_ptr<ParticleSystem::EmitterInitialComponentBase>> mEmitterInitialComponents;
  std::vector<std::unique_ptr<ParticleSystem::EmitterLifetimeComponentBase>> mEmitterLifetimeComponents;
  std::vector<std::unique_ptr<ParticleSystem::EmitterRateComponentBase>> mEmitterRateComponents;
  std::vector<std::unique_ptr<ParticleSystem::EmitterShapeComponentBase>> mEmitterShapeComponents;
  std::vector<std::unique_ptr<ParticleSystem::ParticleAppearanceComponentBase>> mParticleAppearanceComponents;
  std::vector<std::unique_ptr<ParticleSystem::ParticleInitialComponentBase>> mParticleInitialComponents;
  std::vector<std::unique_ptr<ParticleSystem::ParticleLifetimeComponentBase>> mParticleLifetimeComponents;
  std::vector<std::unique_ptr<ParticleSystem::ParticleMotionComponentBase>> mParticleMotionComponents;
  std::vector<std::unique_ptr<ParticleSystem::ParticleCurveBase>> mParticleCurves;
  std::unordered_map<HashedString,std::unique_ptr<ParticleSystem::ParticleEventNode>> mParticleEvents;
  std::string mName;
  std::string mContainerName;
  HashedString mMaterialNameHash;
  std::string mTextureName;
  bool mParseSuccessful;
};

```

### `ParticleEffectInfo`
```
struct __cppobj ParticleEffectInfo : std::enable_shared_from_this<ParticleEffectInfo>
{
  HashedString mName;
  HashedString mContainerName;
  std::unique_ptr<ParticleSystem::ParticleEffect> mPtr;
};

```

### `ParticleRenderer`
```
struct __cppobj ParticleRenderer
{
  std::unordered_map<unsigned int,std::vector<unsigned __int64>> mBuckets;
  mce::MaterialPtr mBlendMat;
};

```

### `ParticleSystemEngine`
```
struct __cppobj __declspec(align(8)) ParticleSystemEngine
{
  std::unordered_map<int,std::unique_ptr<ParticleSystem::ParticleEmitter>> mEmitterMap;
  ParticleRenderer mParticleRenderer;
  bool mLastTickTimeValid;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastTickTime;
  ParticleEffectGroup *mParticleEffectGroup;
  BlockSource *mBlockSource;
  LightTexture *mLightTexture;
  std::array<std::array<mce::Color,16>,16> mLightTextureData;
  int mFramesToInterpolate;
  bool mBeingDestroyed;
  unsigned __int64 mTotalParticleCount;
  std::unordered_map<HashedString,unsigned __int64> mEffectEmitterCounts;
  std::unordered_map<HashedString,unsigned __int64> mEffectParticleCounts;
  Vec3 mLastCameraPosition;
};

```

### `PolygonOperatorPool<RenderChunkBuilder>`
```
struct __cppobj PolygonOperatorPool<RenderChunkBuilder>
{
  std::mutex mMutex;
  const unsigned __int64 mImmediateSize;
  const unsigned __int64 mDeferredSize;
  std::atomic<unsigned __int64> mUsedImmediate;
  std::atomic<unsigned __int64> mUsedDeferred;
  std::vector<std::unique_ptr<RenderChunkBuilder>> mPool;
};

```

### `PolygonOperatorPool<RenderChunkSorter>`
```
struct __cppobj PolygonOperatorPool<RenderChunkSorter>
{
  std::mutex mMutex;
  const unsigned __int64 mImmediateSize;
  const unsigned __int64 mDeferredSize;
  std::atomic<unsigned __int64> mUsedImmediate;
  std::atomic<unsigned __int64> mUsedDeferred;
  std::vector<std::unique_ptr<RenderChunkSorter>> mPool;
};

```

### `PlayerRenderingParameters`
```
struct __cppobj PlayerRenderingParameters
{
  glm::tmat4x4<float,0> mView;
  glm::tmat4x4<float,0> mProjection;
  glm::tmat4x4<float,0> mItemInHandView;
  glm::tmat4x4<float,0> mItemInHandProjection;
  glm::tvec3<float,0> mWorldOrigin;
};

```

### `PlayerRenderView`
```
struct __cppobj __declspec(align(8)) PlayerRenderView
{
  rendergraph::APIResourcePool mAPIResourcePool;
  rendergraph::RenderOrder mPlayerRenderOrder;
  LevelRendererPlayer *mPlayerView;
  optional_ref<PlayerRenderView::LegacyPlayerRenderPass> mLegacyPassRuntimeData;
  PlayerRenderView::PostInitInfo mPostInitInfo;
  mce::Texture mGameplayColorBackingTexture;
  mce::Texture mGameplayDepthBackingTexture;
  mce::Texture mResolvedColorTexture;
  mce::Texture mResolvedDepthTexture;
  PostprocessRenderModule mPostprocessing;
};

```

### `PlayerRenderView::LegacyPlayerRenderPass`
```
struct __cppobj PlayerRenderView::LegacyPlayerRenderPass
{
  optional_ref<PlayerRenderView> mModule;
};

```

### `PlayerRenderView::PostInitInfo`
```
struct __cppobj PlayerRenderView::PostInitInfo
{
  bool mInitialized;
  bool mNeedResolveBeforePostProcess;
  bool mRequiresBackingTextures;
};

```

### `PostprocessRenderModule`
```
struct __cppobj PostprocessRenderModule
{
};

```

### `PackImportStateObject`
```
struct __cppobj __declspec(align(8)) PackImportStateObject
{
  const std::string mProductId;
  const PackManifest *mPackManifest;
  const bool mSuccess;
};

```

### `PathNavigation`
```
struct __cppobj PathNavigation
{
  PathNavigation_vtbl *__vftable /*VFT*/;
};

```

### `Path::Node`
```
struct __cppobj Path::Node
{
  BlockPos pos;
  NodeType type;
};

```

### `Path`
```
struct __cppobj __declspec(align(8)) Path
{
  std::vector<Path::Node> mNodes;
  unsigned __int64 mIndex;
  PathCompletionType mCompletionType;
};

```

### `PathNavigation_vtbl`
```
struct /*VFT*/ PathNavigation_vtbl
{
  void (__fastcall *~PathNavigation)(PathNavigation *this);
  void (__fastcall *initializeInternal)(PathNavigation *this, Mob *, NavigationDescription *);
  void (__fastcall *tick)(PathNavigation *this, NavigationComponent *, Mob *);
  Vec3 *(__fastcall *getTempMobPos)(PathNavigation *this, Vec3 *result, const Mob *);
  std::unique_ptr<Path> *(__fastcall *createPath)(PathNavigation *this, std::unique_ptr<Path> *result, NavigationComponent *, Mob *, Actor *);
  std::unique_ptr<Path> *(__fastcall *createPath)(PathNavigation *this, std::unique_ptr<Path> *result, NavigationComponent *, Mob *, const Vec3 *);
  bool (__fastcall *moveTo)(PathNavigation *this, NavigationComponent *, Mob *, std::unique_ptr<Path>, float);
  bool (__fastcall *moveTo)(PathNavigation *this, NavigationComponent *, Mob *, Actor *, float);
  bool (__fastcall *moveTo)(PathNavigation *this, NavigationComponent *, Mob *, const Vec3 *, float);
  void (__fastcall *stop)(PathNavigation *this, NavigationComponent *, Mob *);
  bool (__fastcall *travel)(PathNavigation *this, NavigationComponent *, Mob *, float *, float *, float *);
  bool (__fastcall *canUpdatePath)(PathNavigation *this, const Mob *);
  void (__fastcall *updatePath)(PathNavigation *this, NavigationComponent *, Mob *);
};

```

### `PauseScreenCapabilities`
```
struct __cppobj __declspec(align(4)) PauseScreenCapabilities : TypedScreenCapabilities<PauseScreenCapabilities>
{
  bool mQuizIgnored;
  bool mEduPermissionsIgnored;
  bool mEduPauseIgnored;
  bool mMultiplayerTabIgnored;
  bool mAccessibilityIsDefaultPauseSettingsTab;
};

```

### `PauseScreenCapabilities_vtbl`
```
struct /*VFT*/ PauseScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `PlayingSoundAttributes`
```
struct __cppobj __declspec(align(4)) PlayingSoundAttributes
{
  float mVolume;
  float mPitch;
  bool mIsMuted;
  bool mIs3D;
};

```

### `ProfilingManager::Impl`
```
struct __cppobj ProfilingManager::Impl
{
  std::set<std::string> mConfigEnabledGroups;
  bool mGroupEnabledDefaultSetting;
  std::mutex mGroupsMutex;
  Bedrock::PubSub::ScopedSubscription mNewGroupSubscription;
};

```

### `ProfilingManager`
```
struct __cppobj ProfilingManager : Bedrock::EnableNonOwnerReferences
{
  std::unique_ptr<ProfilingManager::Impl> mImpl;
};

```

### `PurchaseCache`
```
struct __cppobj __declspec(align(8)) PurchaseCache
{
  const Core::PathBuffer<std::string > mFilePath;
  const std::string mKey;
  std::vector<TransactionRecord> mTransactionRecords;
  std::atomic<bool> mLoadComplete;
};

```

### `PersonaProfile`
```
struct __cppobj __declspec(align(8)) PersonaProfile : Social::IUserDataObject
{
  SemVersion mVersion;
  persona::ProfileType mType;
  std::string mGameTitleIdString;
  std::map<std::string,PersonaAppearance> mTitlePlatformLockedAppearances;
  std::map<std::string,PersonaAppearance> mTitleLockedAppearances;
  std::map<std::string,PersonaAppearance> mPlatformLockedAppearances;
  PersonaAppearance mUniversalAppearance;
  PersonaAppearance mLastSavedAppearance;
  PersonaRepository *mPersonaRepository;
  LegacySkinSerialization mLegacyAppearance;
  LegacySkinSerialization mLastSavedLegacyAppearance;
  bool mLoadingFailed;
  bool mCanSave;
};

```

### `PersonaProfile_vtbl`
```
struct /*VFT*/ PersonaProfile_vtbl
{
  void (__fastcall *~IUserDataObject)(Social::IUserDataObject *this);
  const std::string *(__fastcall *getObjectName)(Social::IUserDataObject *this);
  bool (__fastcall *fillFromJSON)(Social::IUserDataObject *this, const Json::Value *);
  Json::Value *(__fastcall *toJSONObject)(Social::IUserDataObject *this, Json::Value *result);
};

```

### `PersonaService`
```
struct __cppobj __declspec(align(8)) PersonaService : ServiceClient, Bedrock::EnableNonOwnerReferences
{
  std::unordered_map<unsigned int,std::array<std::shared_ptr<PersonaProfile>,6>> mProfiles;
  std::unordered_set<enum persona::ProfileType> mForceFailedProfileTypes;
  std::set<int> mFailedAppearances;
  std::mutex mProfileLock;
  std::unique_ptr<ContentCatalogService> mCatalogService;
  std::shared_ptr<SkinRepository> mSkinRepository;
  std::shared_ptr<PersonaProfile> mInvalidProfile;
  PersonaRepository *mPersonaRepository;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  __int64 mSaveInitiatedTime;
  __int64 mSavingInterval;
  bool mSaveInitiated;
};

```

### `PersonaService_vtbl`
```
struct /*VFT*/ PersonaService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `ParticleSystem::ParticleEffectComponentRegistry`
```
struct __cppobj ParticleSystem::ParticleEffectComponentRegistry
{
  std::unordered_map<HashedString,std::function<std::unique_ptr<ParticleSystem::EffectComponentBase> __cdecl(void)>> mComponentRegistry;
};

```

### `persona::PersonaPieceCollectionModel`
```
struct __cppobj persona::PersonaPieceCollectionModel
{
  persona::PersonaPieceCollectionModel_vtbl *__vftable /*VFT*/;
  int mSelectedCategoryIndex;
  int mSelectedSubCategoryIndex;
  int mLastSelectedSubcategoryIndex;
  _BYTE mSelectedRetrievalType[4];
  _BYTE mLastSelectedRetrievalType[4];
  persona::PersonaSubCategory mCustomSubCategory;
  persona::PersonaSubCategory mEmoteCategory;
  persona::PersonaSubCategory mCapeCategory;
  std::shared_ptr<persona::PersonaPieceCollectionEventManager> mCollectionEventManager;
  std::shared_ptr<DlcBatchCacheModel> mDlcBatchCacheModel;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  IMinecraftEventing *mEventing;
  PersonaRepository *mPersonaRepository;
  gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > mStoreRepository;
  std::shared_ptr<DressingRoomTreatmentQuery> mDressingRoomQueryManifest;
  persona::CategoryCollectorInfo mDressingRoomMainFeaturedInfo;
  persona::CategoryCollectorInfo mProfileFeaturedInfo;
  persona::CategoryCollectorInfo mPersonaAchievementInfo;
  persona::SkinPackCollectorInfo mSkinPackFeaturedInfo;
  std::shared_ptr<CatalogCollection> mSkinPackCatalogCollection;
  std::vector<persona::PersonaCategory> mCategories;
  std::vector<persona::PersonaSizeInfo> mBodySizes;
  std::vector<persona::PersonaSizeInfo> mArmSizes;
  std::function<void __cdecl(void)> mOnManifestFetchFinishedCallback;
  std::shared_ptr<bool> mExistanceTracker;
  FlightingService *mFlightingService;
};

```

### `persona::PersonaPieceCollectionModel_vtbl`
```
struct /*VFT*/ persona::PersonaPieceCollectionModel_vtbl
{
  void (__fastcall *~PersonaPieceCollectionModel)(persona::PersonaPieceCollectionModel *this);
};

```

### `persona::CategoryDocument`
```
struct __cppobj __declspec(align(8)) persona::CategoryDocument
{
  std::string mTitle;
  std::string mImagePath;
  std::string mDescription;
  persona::CategoryQueryDocument mFeaturedQueryDocument;
  std::vector<persona::SubCategoryDocument> mSubCategories;
  bool mIsSelected;
};

```

### `persona::SkinPackCollectorInfo`
```
struct __cppobj persona::SkinPackCollectorInfo
{
  std::string mHeader;
  std::shared_ptr<StoreSearchQuery> mQuery;
};

```

### `Particle_vtbl`
```
struct /*VFT*/ Particle_vtbl
{
  void (__fastcall *init)(Particle *this, const Vec3 *, const Vec3 *, int, ParticleEngine *);
  void (__fastcall *addTagData)(Particle *this, const CompoundTag *);
  void (__fastcall *~Particle)(Particle *this);
  void (__fastcall *normalTick)(Particle *this);
  void (__fastcall *tessellate)(Particle *this, const ParticleRenderContext *);
  const mce::TexturePtr *(__fastcall *getParticleTexture)(Particle *this);
  mce::Color *(__fastcall *getParticleLightColor)(Particle *this, mce::Color *result, float, const LightTexture *);
  void (__fastcall *setEmittingEntity)(Particle *this, Actor *);
  bool (__fastcall *_shouldUpdateVertexData)(Particle *this, float);
};

```

### `PostprocessingManager`
```
struct __cppobj PostprocessingManager
{
  std::mutex mManagerMutex;
  std::unordered_set<ChunkPos> mAcquired;
};

```

### `POIInstance`
```
struct __cppobj __declspec(align(8)) POIInstance
{
  HashedString mName;
  HashedString mInitEvent;
  HashedString mEndEvent;
  Village *mVillage;
  BlockPos mPosition;
  unsigned __int64 mOwnerCount;
  unsigned __int64 mOwnerCapacity;
  unsigned __int64 mWeight;
  float mRadius;
  POIType mType;
  HashedString mSoundEvent;
  __int16 mArrivalFailuresCount;
  bool mUseBoundingBox;
};

```

### `POIBlueprint`
```
struct __cppobj __declspec(align(8)) POIBlueprint
{
  HashedString mName;
  HashedString mInitEvent;
  HashedString mEndEvent;
  POIType mType;
  float mRadius;
  unsigned __int64 mCapacity;
  unsigned __int64 mWeight;
  HashedString mSoundEvent;
  bool mUseBoundingBox;
};

```

### `PositionTrackingDB::OperationBase`
```
struct __cppobj PositionTrackingDB::OperationBase
{
  PositionTrackingDB::OperationBase_vtbl *__vftable /*VFT*/;
};

```

### `PositionTrackingDB::TrackingRecord`
```
struct __cppobj PositionTrackingDB::TrackingRecord
{
  PositionTrackingId mId;
  BlockPos mPosition;
  AutomaticID<Dimension,int> mDimensionType;
  _BYTE mStatus[1];
  bool mDirty;
  std::vector<std::unique_ptr<PositionTrackingDB::OperationBase>> mPendingOperations;
  OwnerPtrT<EntityRefTraits> mEntity;
};

```

### `PositionTrackingDB::OperationBase_vtbl`
```
struct /*VFT*/ PositionTrackingDB::OperationBase_vtbl
{
  void (__fastcall *~OperationBase)(PositionTrackingDB::OperationBase *this);
  bool (__fastcall *tick)(PositionTrackingDB::OperationBase *this, std::weak_ptr<PositionTrackingDB::PositionTrackingDBServer>, PositionTrackingDB::TrackingRecord *);
  const char *(__fastcall *getDescription)(PositionTrackingDB::OperationBase *this);
  bool (__fastcall *isAsync)(PositionTrackingDB::OperationBase *this);
  bool (__fastcall *isComplete)(PositionTrackingDB::OperationBase *this);
};

```

### `PositionTrackingDB::CacheManager`
```
struct __cppobj PositionTrackingDB::CacheManager
{
  Level *mLevel;
  std::map<PositionTrackingId,std::unique_ptr<PositionTrackingDB::TrackingRecord>> mLocalCache;
};

```

### `PackSettingsFactory`
```
struct __cppobj PackSettingsFactory
{
  std::unordered_map<PackIdVersion,std::unique_ptr<PackSettings>> mPackSettings;
};

```

### `PacketViolationHandlerSettings`
```
struct __cppobj PacketViolationHandlerSettings
{
  bool mPacketViolationHandlingEnabled;
  float mFinalWarningThreshold;
  float mTerminateConnectionThreshold;
  float mCountToScoreFactor;
  float mPacketViolationScore;
  float mDefaultScore;
  float mMalformedPacketScore;
  float mScoreDropOffDecayRate;
};

```

### `PacketViolationHandler`
```
struct __cppobj PacketViolationHandler
{
  PacketViolationHandlerSettings mSettings;
  std::map<unsigned __int64,PacketViolationHandler::PacketViolation> mViolations;
};

```

### `PlayerEventListener`
```
struct __cppobj PlayerEventListener
{
  PlayerEventListener_vtbl *__vftable /*VFT*/;
};

```

### `PlayerShootArrowEvent`
```
const struct __cppobj PlayerShootArrowEvent
{
  WeakRefT<EntityRefTraits> mPlayer;
  WeakRefT<EntityRefTraits> mArrow;
  ItemStack mWeaponItem;
  ItemStack mArrowItem;
};

```

### `PlayerEventListener_vtbl`
```
struct /*VFT*/ PlayerEventListener_vtbl
{
  void (__fastcall *~PlayerEventListener)(PlayerEventListener *this);
  EventResult (__fastcall *onPlayerAwardAchievement)(PlayerEventListener *this, Player *, MinecraftEventing::AchievementIds);
  EventResult (__fastcall *onPlayerPortalBuilt)(PlayerEventListener *this, Player *, AutomaticID<Dimension,int>);
  EventResult (__fastcall *onPlayerPortalUsed)(PlayerEventListener *this, Player *, AutomaticID<Dimension,int>, AutomaticID<Dimension,int>);
  EventResult (__fastcall *onPlayerCaravanChanged)(PlayerEventListener *this, const Actor *, int);
  EventResult (__fastcall *onPlayerSaved)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerInput)(PlayerEventListener *this, IPlayerMovementProxy *, MoveInputHandler *);
  EventResult (__fastcall *onPlayerAuthInputReceived)(PlayerEventListener *this, Player *, const PlayerAuthInputPacket *);
  EventResult (__fastcall *onPlayerAuthInputApplied)(PlayerEventListener *this, Player *, const PlayerAuthInputPacket *);
  EventResult (__fastcall *onPlayerTurn)(PlayerEventListener *this, Player *, Vec2 *);
  EventResult (__fastcall *onCameraSetPlayerRot)(PlayerEventListener *this, Player *, const Camera *);
  EventResult (__fastcall *onStartDestroyBlock)(PlayerEventListener *this, Player *, const BlockPos *, unsigned __int8 *);
  EventResult (__fastcall *onPlayerAction)(PlayerEventListener *this, Player *, PlayerActionType, const BlockPos *, int);
  EventResult (__fastcall *onPlayerHurt)(PlayerEventListener *this, const PlayerDamageEvent *);
  EventResult (__fastcall *onLocalPlayerDeath)(PlayerEventListener *this, IClientInstance *, LocalPlayer *);
  EventResult (__fastcall *onLocalPlayerRespawn)(PlayerEventListener *this, IClientInstance *, LocalPlayer *);
  EventResult (__fastcall *onPlayerMove)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerSlide)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerTargetBlockHit)(PlayerEventListener *this, Player *, const int);
  EventResult (__fastcall *onPlayerAIStepBegin)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerTick)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerStartRiding)(PlayerEventListener *this, Player *, Actor *);
  EventResult (__fastcall *onPlayerStopRiding)(PlayerEventListener *this, Player *, bool, bool, bool);
  EventResult (__fastcall *onPlayerCreated)(PlayerEventListener *this, LocalPlayer *, const std::string *, const std::string *, bool);
  EventResult (__fastcall *onPlayerTeleported)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerAttackedActor)(PlayerEventListener *this, Player *, Actor *);
  EventResult (__fastcall *onPlayerMovementCorrected)(PlayerEventListener *this, Player *, const Vec3 *, const float, const float);
  EventResult (__fastcall *onPlayerMovementAnomaly)(PlayerEventListener *this, Player *, const Vec3 *, const float, const float);
  EventResult (__fastcall *onPlayerDestroyedBlock)(PlayerEventListener *this, Player *, const BlockLegacy *);
  EventResult (__fastcall *onPlayerDestroyedBlock)(PlayerEventListener *this, Player *, int, int, int);
  EventResult (__fastcall *onPlayerOnGround)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerEquippedArmor)(PlayerEventListener *this, Player *, const ItemDescriptor *);
  EventResult (__fastcall *onPlayerEnchantedItem)(PlayerEventListener *this, Player *, const ItemStack *, const ItemEnchants *);
  EventResult (__fastcall *onPlayerNamedItem)(PlayerEventListener *this, Player *, const ItemDescriptor *);
  EventResult (__fastcall *onPlayerItemUseInteraction)(PlayerEventListener *this, Player *, const ItemInstance *);
  EventResult (__fastcall *onPlayerItemPlaceInteraction)(PlayerEventListener *this, Player *, const ItemInstance *);
  EventResult (__fastcall *onPlayerStartUsingItem)(PlayerEventListener *this, const Player *, const ItemStack *);
  EventResult (__fastcall *onPlayerStopUsingItem)(PlayerEventListener *this, const Player *, const ItemStack *);
  EventResult (__fastcall *onPlayerCraftedItem)(PlayerEventListener *this, Player *, const ItemInstance *, bool, bool, bool, int, int, int, bool, bool, const std::vector<short> *);
  EventResult (__fastcall *onPlayerItemEquipped)(PlayerEventListener *this, Player *, const ItemInstance *, int);
  EventResult (__fastcall *onPlayerJumped)(PlayerEventListener *this, const Player *);
  EventResult (__fastcall *onPlayerOpenContainer)(PlayerEventListener *this, Player *, ContainerType, const BlockPos *, ActorUniqueID);
  EventResult (__fastcall *onPlayerPiglinBarter)(PlayerEventListener *this, Player *, const std::string *, bool);
  EventResult (__fastcall *onPlayerAddExp)(PlayerEventListener *this, const PlayerAddExpEvent *);
  EventResult (__fastcall *onPlayerAddLevel)(PlayerEventListener *this, const PlayerAddLevelEvent *);
  EventResult (__fastcall *onPlayerArmorExchange)(PlayerEventListener *this, const PlayerArmorExchangeEvent *);
  EventResult (__fastcall *onPlayerDestroyBlock)(PlayerEventListener *this, const PlayerDestroyBlockEvent *);
  EventResult (__fastcall *onPlayerDie)(PlayerEventListener *this, const PlayerDamageEvent *);
  EventResult (__fastcall *onPlayerGetExperienceOrb)(PlayerEventListener *this, const PlayerGetExperienceOrbEvent *);
  EventResult (__fastcall *onPlayerSayCommand)(PlayerEventListener *this, const PlayerSayCommandEvent *);
  EventResult (__fastcall *onPlayerShootArrow)(PlayerEventListener *this, const PlayerShootArrowEvent *);
  EventResult (__fastcall *onPlayerStopLoading)(PlayerEventListener *this, const PlayerEvent *);
  EventResult (__fastcall *onPlayerUseNameTag)(PlayerEventListener *this, const PlayerUseNameTagEvent *);
};

```

### `PlayerGameplayHandler`
```
struct __cppobj PlayerGameplayHandler : GameplayHandler
{
};

```

### `PlayerGameplayHandler_vtbl`
```
struct /*VFT*/ PlayerGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  HandlerResult (__fastcall *handleAddExp)(PlayerGameplayHandler *this, const PlayerAddExpEvent *);
  HandlerResult (__fastcall *handleAddLevel)(PlayerGameplayHandler *this, const PlayerAddLevelEvent *);
  HandlerResult (__fastcall *handleArmorExchange)(PlayerGameplayHandler *this, const PlayerArmorExchangeEvent *);
  HandlerResult (__fastcall *handleDestroyBlock)(PlayerGameplayHandler *this, const PlayerDestroyBlockEvent *);
  HandlerResult (__fastcall *handleDie)(PlayerGameplayHandler *this, const PlayerDamageEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleGetExperienceOrb)(PlayerGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const PlayerGetExperienceOrbEvent *);
  HandlerResult (__fastcall *handleHurt)(PlayerGameplayHandler *this, const PlayerDamageEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleSayCommand)(PlayerGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const PlayerSayCommandEvent *);
  HandlerResult (__fastcall *handleShootArrow)(PlayerGameplayHandler *this, const PlayerShootArrowEvent *);
  HandlerResult (__fastcall *handleStopLoading)(PlayerGameplayHandler *this, const PlayerEvent *);
  HandlerResult (__fastcall *handleUseNameTag)(PlayerGameplayHandler *this, const PlayerUseNameTagEvent *);
};

```

### `PlayerEventCoordinator`
```
struct __cppobj PlayerEventCoordinator : EventCoordinator<PlayerEventListener>
{
  std::unique_ptr<PlayerGameplayHandler> mPlayerGameplayHandler;
};

```

### `PlayerInventory`
```
struct __cppobj PlayerInventory : ContainerSizeChangeListener, ContainerContentChangeListener
{
  int mSelected;
  ItemStack mInfiniteItem;
  ContainerID mSelectedContainerId;
  std::unique_ptr<Inventory> mInventory;
  std::vector<ItemStack> mComplexItems;
  std::weak_ptr<HudContainerManagerModel> mHudContainerManager;
};

```

### `PlayerInventory_vtbl`
```
struct /*VFT*/ PlayerInventory_vtbl
{
  void (__fastcall *containerSizeChanged)(ContainerSizeChangeListener *this, int);
  void (__fastcall *~ContainerSizeChangeListener)(ContainerSizeChangeListener *this);
  void (__fastcall *createTransactionContext)(PlayerInventory *this, std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>, std::function<void __cdecl(void)>);
};

```

### `Player::CachedSpawnData`
```
struct __cppobj Player::CachedSpawnData
{
  AutomaticID<Dimension,int> mRespawnDimensionId;
  Vec3 mActualRespawnPosition;
  BlockPos mRequestedRespawnPosition;
  bool mHasRespawnPosition;
  BlockPos mSharedSpawnPosition;
  bool mRespawnReady;
  Vec3 mPlayerPos;
  bool mIsForcedRespawn;
  bool mIsAdventure;
  bool mIsFlyingOrNotOverworld;
  bool mPositionLoadedFromSave;
};

```

### `PlayerUIContainer`
```
struct __cppobj PlayerUIContainer : SimpleContainer
{
};

```

### `PlayerUIContainer_vtbl`
```
struct /*VFT*/ PlayerUIContainer_vtbl
{
  void (__fastcall *~Container)(Container *this);
  void (__fastcall *init)(Container *this);
  void (__fastcall *serverInitItemStackIds)(Container *this, int, int, std::function<void __cdecl(int,ItemStack const &)>);
  void (__fastcall *addContentChangeListener)(Container *this, ContainerContentChangeListener *);
  void (__fastcall *removeContentChangeListener)(Container *this, ContainerContentChangeListener *);
  const ItemStack *(__fastcall *getItem)(Container *this, int);
  bool (__fastcall *hasRoomForItem)(Container *this, const ItemStack *);
  void (__fastcall *addItem)(Container *this, ItemStack *);
  bool (__fastcall *addItemToFirstEmptySlot)(Container *this, ItemStack *);
  void (__fastcall *setItem)(Container *this, int, const ItemStack *);
  void (__fastcall *setItemWithForceBalance)(Container *this, int, const ItemStack *, bool);
  void (__fastcall *removeItem)(Container *this, int, int);
  void (__fastcall *removeAllItems)(Container *this);
  void (__fastcall *dropContents)(Container *this, BlockSource *, const Vec3 *, bool);
  int (__fastcall *getContainerSize)(Container *this);
  int (__fastcall *getMaxStackSize)(Container *this);
  void (__fastcall *startOpen)(Container *this, Player *);
  void (__fastcall *stopOpen)(Container *this, Player *);
  std::vector<ItemStack> *(__fastcall *getSlotCopies)(Container *this, std::vector<ItemStack> *result);
  const std::vector<ItemStack const *> *(__fastcall *getSlots)(Container *this, const std::vector<ItemStack const *> *result);
  int (__fastcall *getItemCount)(Container *this, const ItemStack *);
  int (__fastcall *findFirstSlotForItem)(Container *this, const ItemStack *);
  bool (__fastcall *canPushInItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  bool (__fastcall *canPullOutItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  void (__fastcall *setContainerChanged)(Container *this, int);
  void (__fastcall *setContainerMoved)(Container *this);
  void (__fastcall *setCustomName)(Container *this, const std::string *);
  bool (__fastcall *hasCustomName)(Container *this);
  void (__fastcall *readAdditionalSaveData)(Container *this, const CompoundTag *);
  void (__fastcall *addAdditionalSaveData)(Container *this, CompoundTag *);
  void (__fastcall *createTransactionContext)(Container *this, std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>, std::function<void __cdecl(void)>);
  void (__fastcall *initializeContainerContents)(Container *this, BlockSource *);
  bool (__fastcall *reviewItems)(Container *this, Level *);
};

```

### `PlayerRespawnBlockRadiusRandomizer`
```
struct __cppobj PlayerRespawnBlockRadiusRandomizer
{
  unsigned int mSpawnRadius;
  unsigned int mPossibleOrigins;
  unsigned int mLargestPrime;
  unsigned int mStartOrigin;
  unsigned int mCurrentOrigin;
  unsigned int mIterationCount;
};

```

### `PlayerRespawnRandomizer`
```
struct __cppobj PlayerRespawnRandomizer
{
  Random mRandom;
  unsigned int mSpawnRadius;
  unsigned int mSquaredRadius;
  PlayerRespawnBlockRadiusRandomizer mPrimaryRandomizer;
  PlayerRespawnBlockRadiusRandomizer mSecondaryRandomizer;
  Vec3 mSpawnCenter;
  Vec3 mPrimaryOffset;
  Vec3 mPrimaryScale;
};

```

### `Player::PlayerSpawnPoint`
```
struct __cppobj Player::PlayerSpawnPoint
{
  BlockPos mSpawnBlockPos;
  BlockPos mPlayerPosition;
  AutomaticID<Dimension,int> mDimension;
};

```

### `PistonBlockActor`
```
struct __cppobj PistonBlockActor : BlockActor
{
  bool mSticky;
  float mProgress;
  float mLastProgress;
  bool mWasPushedBackwardByANonStickyPiston;
  bool mWasPulledForwardByAStickyPiston;
  PistonBlockActor::PistonState mOldState;
  PistonBlockActor::PistonState mState;
  PistonBlockActor::PistonState mNewState;
  bool mVerifyArm;
  bool mShouldVerifyArmType;
  std::vector<BlockPos> mAttachedBlocks;
  std::vector<BlockPos> mBreakBlocks;
};

```

### `PlayerSuspension`
```
struct __cppobj __declspec(align(8)) PlayerSuspension
{
  mce::UUID mId;
  PlayerSuspension::State mSuspensionState;
};

```

### `PhotoStorage`
```
struct __cppobj PhotoStorage
{
  Core::PathBuffer<std::string > mBaseDir;
  Core::PathBuffer<std::string > mBookDir;
  Core::PathBuffer<std::string > mPhotoDir;
  Core::PathBuffer<std::string > mManifestDir;
  std::unordered_set<std::string> mChecksums;
};

```

### `PickupItemDefinition`
```
struct __cppobj PickupItemDefinition : ComponentDescription
{
  int mFavoredSlot;
  std::string mItemName;
};

```

### `PickupItemDefinition_vtbl`
```
struct /*VFT*/ PickupItemDefinition_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `PersistentDescription`
```
struct __cppobj PersistentDescription : ComponentDescription
{
};

```

### `PersistentDescription_vtbl`
```
struct /*VFT*/ PersistentDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `PreferredPathDescription_vtbl`
```
struct /*VFT*/ PreferredPathDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ProjectileDescription`
```
struct __cppobj __declspec(align(8)) ProjectileDescription : ComponentDescription
{
  Vec3 mProjectileOffset;
  float mProjectilePower;
  bool mKnockback;
  bool mIgniteOnHit;
  bool mLightingOnHit;
  float mGravity;
  float mUpwardsAngleOffset;
  ParticleType mHitParticle;
  float mUncertaintyBase;
  float mUncertaintyMultiplier;
  float mOnFireTime;
  int mPotionEffect;
  float mSplashRange;
  ActorType mFilter;
  bool mCatchFire;
  bool mIsSplash;
  float mInertiaMod;
  float mLiquidInertia;
  bool mSemiRandomDiffDamage;
  std::string mHitEntitySound;
  std::string mHitGroundSound;
  std::string mShootSound;
  ProjectileAnchor mAnchor;
  std::vector<std::unique_ptr<OnHitSubcomponent>> mOnHitCommands;
  DefinitionTrigger mOnHitEvent;
  bool mIsDangerous;
  bool mReflectOnHurt;
  bool mDestroyOnHurt;
  bool mStopOnHurt;
  bool mCritParticleOnHurt;
  bool mShootTarget;
  bool mIsHoming;
  bool mShouldBounce;
  bool mFireAffectedByGriefing;
  bool mHitWater;
  bool mMultipleHits;
};

```

### `ProjectileDescription_vtbl`
```
struct /*VFT*/ ProjectileDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `PushableDescription`
```
struct __cppobj __declspec(align(8)) PushableDescription : ComponentDescription
{
  bool mIsPushable;
  bool mIsPushableByPiston;
};

```

### `PushableDescription_vtbl`
```
struct /*VFT*/ PushableDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ProjectileFactory`
```
struct __cppobj ProjectileFactory
{
  Level *mLevel;
};

```

### `PortalRecord`
```
struct __cppobj __declspec(align(2)) PortalRecord
{
  BlockPos mBaseBlockPos;
  char mSpan;
  char mXInc;
  char mZInc;
};

```

### `PortalForcer`
```
struct __cppobj PortalForcer : SavedData
{
  Level *mLevel;
  Random mRandom;
  std::unordered_map<AutomaticID<Dimension,int>,std::unordered_set<PortalRecord>,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::unordered_set<PortalRecord> > > > mPortalRecords;
};

```

### `PortalForcer_vtbl`
```
struct /*VFT*/ PortalForcer_vtbl
{
  void (__fastcall *~SavedData)(SavedData *this);
  void (__fastcall *deserialize)(SavedData *this, const CompoundTag *);
  void (__fastcall *serialize)(SavedData *this, CompoundTag *);
};

```

### `PendingRemovalInfo`
```
struct __cppobj __declspec(align(8)) PendingRemovalInfo
{
  std::unique_ptr<Actor> e;
  int ticks;
};

```

### `PlayerInteractionSystem::InteractionMappingBase`
```
struct __cppobj PlayerInteractionSystem::InteractionMappingBase
{
  PlayerInteractionSystem::InteractionMappingBase_vtbl *__vftable /*VFT*/;
};

```

### `PlayerInteractionSystem::InteractionMappingBase_vtbl`
```
struct /*VFT*/ PlayerInteractionSystem::InteractionMappingBase_vtbl
{
  void (__fastcall *~InteractionMappingBase)(PlayerInteractionSystem::InteractionMappingBase *this);
  bool (__fastcall *getInteraction)(PlayerInteractionSystem::InteractionMappingBase *this, Actor *, Player *, ActorInteraction *);
};

```

### `PlayerInteractionSystem`
```
struct __cppobj PlayerInteractionSystem
{
  std::vector<std::unique_ptr<PlayerInteractionSystem::InteractionMappingBase>> mInteractionMappings;
};

```

### `PositionTrackingDB::PositionTrackingDBClient`
```
struct __cppobj PositionTrackingDB::PositionTrackingDBClient
{
  Level *mLevel;
  std::unique_ptr<PositionTrackingDB::CacheManager> mLocalCache;
};

```

### `PredictedMovementComponent::RuntimePredictionData_vtbl`
```
struct /*VFT*/ PredictedMovementComponent::RuntimePredictionData_vtbl
{
  void (__fastcall *~RuntimePredictionData)(PredictedMovementComponent::RuntimePredictionData *this);
};

```

### `PredictedMovementComponent::HistoryItem`
```
const struct __cppobj __declspec(align(8)) PredictedMovementComponent::HistoryItem
{
  PredictedMovementComponent::HistoryItem_vtbl *__vftable /*VFT*/;
  const PredictedMovementComponent::HistoryTimestamp mTimestamp;
  const PredictedMovementComponent::HistoryItem::ItemType mType;
};

```

### `PredictedMovementComponent::HistoryItem_vtbl`
```
struct /*VFT*/ PredictedMovementComponent::HistoryItem_vtbl
{
  void (__fastcall *~HistoryItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isValidStartItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isAddedActorItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isMotionHintItem)(PredictedMovementComponent::HistoryItem *this);
  const Vec3 *(__fastcall *getPos)(PredictedMovementComponent::HistoryItem *this);
  const Vec2 *(__fastcall *getRot)(PredictedMovementComponent::HistoryItem *this);
  float (__fastcall *getYHeadRot)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isOnGround)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isTeleported)(PredictedMovementComponent::HistoryItem *this);
};

```

### `PredictedMovementComponent::HistoryTimestamp`
```
const struct __cppobj __declspec(align(8)) PredictedMovementComponent::HistoryTimestamp
{
  unsigned __int64 mServerTick;
  unsigned int mSequenceId;
};

```

### `PredictedMovementComponent`
```
struct __cppobj PredictedMovementComponent
{
  Actor *mActor;
  PredictedMovementComponent::RuntimePredictionData mRuntimePredictionData;
  unsigned __int64 mLastServerTick;
  std::shared_ptr<PredictedMovementComponent::HistoryItem const > mLastStartItem;
  PredictedMovementComponent::HistoryCache mHistoryCache;
};

```

### `PredictedMovementComponent::MoveHistoryItem`
```
const struct __cppobj __declspec(align(8)) PredictedMovementComponent::MoveHistoryItem : PredictedMovementComponent::HistoryItem
{
  const Vec3 mPos;
  const Vec2 mRot;
  const float mYHeadRot;
  const bool mOnGround;
  const bool mTeleported;
  const bool mIsAddedActorItem;
};

```

### `PredictedMovementComponent::MoveHistoryItem_vtbl`
```
struct /*VFT*/ PredictedMovementComponent::MoveHistoryItem_vtbl
{
  void (__fastcall *~HistoryItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isValidStartItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isAddedActorItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isMotionHintItem)(PredictedMovementComponent::HistoryItem *this);
  const Vec3 *(__fastcall *getPos)(PredictedMovementComponent::HistoryItem *this);
  const Vec2 *(__fastcall *getRot)(PredictedMovementComponent::HistoryItem *this);
  float (__fastcall *getYHeadRot)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isOnGround)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isTeleported)(PredictedMovementComponent::HistoryItem *this);
};

```

### `PredictedMovementComponent::MotionHistoryItem`
```
const struct __cppobj __declspec(align(2)) PredictedMovementComponent::MotionHistoryItem : PredictedMovementComponent::HistoryItem
{
  const Vec3 mMotion;
  const Vec3 mCumulativeMotion;
  const bool mOnGround;
  const Vec3 mPos;
  const Vec2 mRot;
  const float mYHeadRot;
  const bool mIsValidStartItem;
  const bool mIsAddedActorItem;
  const bool mIsMotionHintItem;
};

```

### `PredictedMovementComponent::MotionHistoryItem_vtbl`
```
struct /*VFT*/ PredictedMovementComponent::MotionHistoryItem_vtbl
{
  void (__fastcall *~HistoryItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isValidStartItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isAddedActorItem)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isMotionHintItem)(PredictedMovementComponent::HistoryItem *this);
  const Vec3 *(__fastcall *getPos)(PredictedMovementComponent::HistoryItem *this);
  const Vec2 *(__fastcall *getRot)(PredictedMovementComponent::HistoryItem *this);
  float (__fastcall *getYHeadRot)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isOnGround)(PredictedMovementComponent::HistoryItem *this);
  bool (__fastcall *isTeleported)(PredictedMovementComponent::HistoryItem *this);
};

```

### `PredictedMovementComponent::HistoryCache`
```
struct __cppobj PredictedMovementComponent::HistoryCache
{
  std::deque<std::shared_ptr<PredictedMovementComponent::HistoryItem const >> mHistory;
  std::shared_ptr<PredictedMovementComponent::MoveHistoryItem const > mLastMoveItem;
  std::shared_ptr<PredictedMovementComponent::MotionHistoryItem const > mLastMotionItem;
};

```

### `PDFError`
```
struct __cppobj PDFError
{
  std::string reason;
};

```

### `PDFWriter`
```
struct __cppobj PDFWriter : std::enable_shared_from_this<PDFWriter>
{
  PDFWriter_vtbl *__vftable /*VFT*/;
};

```

### `PDFWriter_vtbl`
```
struct /*VFT*/ PDFWriter_vtbl
{
  void (__fastcall *exportImagesToAlbum)(PDFWriter *this, PDFOptions, std::function<void __cdecl(std::optional<PDFError>)>);
  void (__fastcall *~PDFWriter)(PDFWriter *this);
};

```

### `ProgressHandler`
```
struct __cppobj __declspec(align(8)) ProgressHandler
{
  ProgressHandler_vtbl *__vftable /*VFT*/;
  _BYTE mType[4];
  std::string mProgressName;
  _BYTE mProgressAnimation[4];
};

```

### `ProgressHandler_vtbl`
```
struct /*VFT*/ ProgressHandler_vtbl
{
  void (__fastcall *~ProgressHandler)(ProgressHandler *this);
  void (__fastcall *onStart)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *tick)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onCancel)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onExit)(ProgressHandler *this, MinecraftScreenModel *);
  LoadingState (__fastcall *getLoadingState)(ProgressHandler *this, MinecraftScreenModel *);
  float (__fastcall *getLoadingProgress)(ProgressHandler *this, MinecraftScreenModel *);
  std::string *(__fastcall *getProgressMessage)(ProgressHandler *this, std::string *result, MinecraftScreenModel *);
  void (__fastcall *addEventProperties)(ProgressHandler *this, std::unordered_map<std::string,std::string> *);
  std::string *(__fastcall *getTTSProgressMessage)(ProgressHandler *this, std::string *result);
  std::string *(__fastcall *getTitleText)(ProgressHandler *this, std::string *result);
  ProgressAnimation (__fastcall *showLoadingBar)(ProgressHandler *this);
};

```

### `PreCacheScreenProgressHandler`
```
struct __cppobj __declspec(align(8)) PreCacheScreenProgressHandler : ProgressHandler
{
  _BYTE mState[4];
};

```

### `PreCacheScreenProgressHandler_vtbl`
```
struct /*VFT*/ PreCacheScreenProgressHandler_vtbl
{
  void (__fastcall *~ProgressHandler)(ProgressHandler *this);
  void (__fastcall *onStart)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *tick)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onCancel)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onExit)(ProgressHandler *this, MinecraftScreenModel *);
  LoadingState (__fastcall *getLoadingState)(ProgressHandler *this, MinecraftScreenModel *);
  float (__fastcall *getLoadingProgress)(ProgressHandler *this, MinecraftScreenModel *);
  std::string *(__fastcall *getProgressMessage)(ProgressHandler *this, std::string *result, MinecraftScreenModel *);
  void (__fastcall *addEventProperties)(ProgressHandler *this, std::unordered_map<std::string,std::string> *);
  std::string *(__fastcall *getTTSProgressMessage)(ProgressHandler *this, std::string *result);
  std::string *(__fastcall *getTitleText)(ProgressHandler *this, std::string *result);
  ProgressAnimation (__fastcall *showLoadingBar)(ProgressHandler *this);
};

```

### `PDPSection`
```
struct __cppobj PDPSection
{
  PDPSection_vtbl *__vftable /*VFT*/;
  PDPSectionType mType;
  std::string mSectionTitle;
};

```

### `PDPSection_vtbl`
```
struct /*VFT*/ PDPSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `PDPData`
```
struct __cppobj PDPData
{
  const StoreCatalogItem *item;
  std::map<enum PDPSectionType,std::unique_ptr<PDPSection>> sections;
};

```

### `PackContentItem`
```
struct __cppobj PackContentItem : ManifestContentItem
{
  _BYTE mListType[4];
  PackReport mPackReport;
  PackReport mLoadingReport;
  std::string mDateAvailable;
  unsigned __int64 mPosition;
  int mSubpackIndex;
  PackReportState mReportState;
  SubpackInfoCollection mSubpackInfo;
  PackSettings *mPackSettings;
  std::vector<PackContentItem *> mDependencies;
  std::vector<PackContentItem *> mDependentContent;
};

```

### `PackContentItem_vtbl`
```
struct /*VFT*/ PackContentItem_vtbl
{
  void (__fastcall *~ContentItem)(ContentItem *this);
};

```

### `PromotionToastSearchResults`
```
const struct __cppobj PromotionToastSearchResults : CommonSearchResults
{
  std::vector<PromotionToastDocument> mDocuments;
};

```

### `PersonaNewOffersQuery`
```
struct __cppobj PersonaNewOffersQuery : NewOffersQuery
{
};

```

### `PersonaScreenModel::ReactAnimationTypeHash`
```
struct __cppobj PersonaScreenModel::ReactAnimationTypeHash
{
};

```

### `PersonaScreenModel::ReactAnimationData`
```
struct __cppobj PersonaScreenModel::ReactAnimationData
{
  std::string animationName;
  std::string soundEventName;
};

```

### `PersonaScreenModelCommon`
```
struct __cppobj PersonaScreenModelCommon
{
  PersonaScreenModelCommon_vtbl *__vftable /*VFT*/;
  IMinecraftGame *mMinecraft;
  IClientInstance *mClient;
  SkinRepositoryClientInterface *mSkinRepoClientInterface;
  IMinecraftEventing *mEventing;
  PreviewedItemEventInformation mPreviewedItemInfo;
  __int64 mNextPossibleEventTime;
  bool mIsCurrentSkinPackOwned;
  std::shared_ptr<bool> mExistanceTracker;
};

```

### `PersonaScreenModelCommon_vtbl`
```
struct /*VFT*/ PersonaScreenModelCommon_vtbl
{
  void (__fastcall *~PersonaScreenModelCommon)(PersonaScreenModelCommon *this);
  void (__fastcall *updateSkin)(PersonaScreenModelCommon *this, SkinHandle);
};

```

### `PreviewedItemEventInformation`
```
struct __cppobj __declspec(align(8)) PreviewedItemEventInformation
{
  int mPieceIndex;
  mce::UUID mPieceId;
  std::string mProductId;
  std::string mCreatorId;
  std::string mCreatorName;
  IMinecraftEventing::PromotionType mPromotionType;
  persona::ProfileType mProfileType;
  int mRow;
  int mCol;
  long double mSecondsToLoad;
  bool mIsOwned;
  bool mEventSent;
};

```

### `PersonaScreenControllerCommon`
```
struct __cppobj PersonaScreenControllerCommon
{
  const std::string COLOR_COLLECTION_NAME;
  const std::string COLOR_COLLECTION_INDEX;
  persona::SelectedOfferSectionType mCurrentEquippedOfferSection;
  persona::SelectedOfferSectionType mCurrentPreviewedOfferSection;
  __declspec(align(4)) _BYTE mPieceSide[4];
  std::string mInitiallyEquippedId;
  std::string mCurrentlyEquippedId;
  std::string mCurrentlyEquippedHeight;
  std::string mCurrentlyEquippedArmSize;
  std::string mCurrentlyPreviewedId;
  persona::PieceOfferWrapper mCurrentlyEquippedOffer;
  std::string mCurrentRightTitle;
  std::string mCurrentRightTitleRarity;
  std::string mCurrentRightDescription;
  std::shared_ptr<bool> mExistanceTracker;
  int mSelectedEmoteSlot;
  persona::PersonaPieceCollectionModel *mPersonaPieceCollectionModel;
  bool mShowColorPicker;
  bool mPreviewAppearance;
  bool mResetRotationFullPreview;
  std::shared_ptr<PersonaScreenModelCommon> mPersonaScreenModelCommon;
  std::vector<std::pair<mce::Color,std::string >> mCurrentColorSwatches;
  std::vector<enum persona::PersonaColorOption> mCurrentColorOptions;
  unsigned __int16 mCurrentColorChannel;
  unsigned __int16 mCurrentColorPageIndex;
  _BYTE mCurrentColorOption[1];
  mce::Color mCurrentlyEquippedColor;
  std::string mCurrentlyPreviewedColorName;
  std::string mCurrentColorTitle;
};

```

### `PurchaseEnabledScreenController`
```
struct __cppobj PurchaseEnabledScreenController : StoreBaseScreenController
{
  std::unique_ptr<OfferCollectionComponent> mBundleCollection;
  MinecoinModel *mRealMoneyButtonModel;
  std::function<void __cdecl(bool)> mBoughtEnoughCoinsCallback;
  std::function<void __cdecl(void)> mOnPurchaseSuccessCallback;
  MinecoinCatalogStatus mCatalogStatus;
  PurchaseEnabledScreenController::PurchaseStatus mPurchaseStatus;
  int mNeededCoins;
  IMinecraftEventing::StoreType mStoreType;
  const StoreCatalogItem *mActiveOffer;
  std::vector<std::string> mItemsToDownloadOnSuccess;
  int mWorldCount;
  int mResourcePackCount;
  bool mHasWorldTemplates;
  bool mRealMoneyPurchase;
  bool mCoinPurchase;
  bool mPrevCoinPurchaseInProgressState;
  bool mPrevDownloadState;
  bool mSkinsVisible;
  std::shared_ptr<PurchaseEnabledScreenController::PurchaseEnabledEntitlementChangeListener> mEntitlementChangeListener;
};

```

### `PurchaseEnabledScreenController::PurchaseEnabledEntitlementChangeListener`
```
struct __cppobj __declspec(align(8)) PurchaseEnabledScreenController::PurchaseEnabledEntitlementChangeListener : EntitlementChangeListener
{
  bool mDirty;
};

```

### `PurchaseEnabledScreenController::PurchaseEnabledEntitlementChangeListener_vtbl`
```
struct /*VFT*/ PurchaseEnabledScreenController::PurchaseEnabledEntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `PurchaseEnabledScreenController_vtbl`
```
struct /*VFT*/ PurchaseEnabledScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
  int (__fastcall *_getRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getColIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getLastRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getRemainderOffers)(StoreBaseScreenController *this, const int);
  void (__fastcall *onCatalogStatusUpdated)(PurchaseEnabledScreenController *this);
};

```

### `PersonaScreenModel`
```
struct __cppobj PersonaScreenModel : MainMenuScreenModel, PersonaScreenModelCommon
{
  const float DEFAULT_PAPERDOLL_ROTATION;
  const float PAPERDOLL_BACK_ROTATION;
  std::unordered_map<enum persona::ReactAnimationType,std::vector<PersonaScreenModel::ReactAnimationData>,PersonaScreenModel::ReactAnimationTypeHash,std::equal_to<enum persona::ReactAnimationType>,std::allocator<std::pair<enum persona::ReactAnimationType const ,std::vector<PersonaScreenModel::ReactAnimationData> > > > mReactAnimations;
  persona::ReactAnimationType mAnimationReactState;
  persona::ReactAnimationType mAnimationIdleState;
  persona::ReactAnimationType mAnimationBoredState;
  bool mForceUpdateAnimation;
  float mLastBored;
  float mLastFrameTime;
  std::optional<float> mStartingRotation;
  std::string mEmoteAnimationToPlay;
  SkinHandle mSelectedSkinHandle;
  SkinPackCollectionModel *mClassicOwnedSkinPackCollection;
  SkinPackCollectionModel *mClassicPurchasableSkinPackCollection;
  SkinPackCollectionModel *mClassicRealmsPlusSkinPackCollection;
  personaScreen::ClassicSkinPackOrigin mSelectedSkinPackState;
  std::shared_ptr<bool> mExistanceTracker;
};

```

### `PersonaScreenModel_vtbl`
```
struct /*VFT*/ PersonaScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `PersonaScreenController`
```
struct __cppobj PersonaScreenController : PurchaseEnabledScreenController, PersonaScreenControllerCommon
{
  SkinHandle mPersonaSkinHandle;
  personaScreen::TabState mTabState;
  std::vector<enum personaScreen::CustomizationState> mPreviousCustomizeStates;
  personaScreen::CustomizationState mCustomizeState;
  personaScreen::ClassicSkinState mClassicSkinState;
  SkinHandle mCustomSkinHandleFat;
  SkinHandle mCustomSkinHandleSkinny;
  SkinHandle mLastOwnedSkinEquipped;
  int mCurrentOfferSkinPackIndex;
  int mSelectedSkinHandlePackIndex;
  int mSelectedSkinIndexInPack;
  std::string mSelectedSkinTitle;
  bool mAppearanceStatusHovered;
  Stopwatch mAppearanceStatusStopwatch;
  bool mUpdateCustomSkinModel;
  bool mCustomSkinPopupVisible;
  personaScreen::NavigateToPersonaFrom mNavigatedFrom;
  std::string mMostRecentlySelectedSize;
  std::string mToastMessage;
  _BYTE mDirtyFlags[4];
  bool mHasPendingPurchasedPackToRemove;
  PackIdVersion mPurchasedPack;
  PersonaAppearance mInitialAppearance;
  int mHoverSkinPackIndex;
  int mHoverSkinIndex;
  std::string mInitialSkinName;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mInitialPersonaLastUpdatedTime;
  std::map<mce::UUID,AchievementData> mUnlockedAchievements;
  std::map<mce::UUID,AchievementData> mLockedAchievements;
  StoreCatalogItem *mLastValidActiveOffer;
  bool mIsUsingGamepad;
  bool mHasInitialized;
  bool mPersonaIsUpdating;
  bool mUnselectingOffer;
  bool mLeaveDressingRoom;
  std::function<void __cdecl(void)> mDelayedScreenViewCommandCallback;
  std::shared_ptr<PersonaScreenModel> mPersonaScreenModel;
  std::vector<std::pair<persona::PersonaCharacterHandle,std::function<void __cdecl(void)> >> mPendingCharactersToRevertOrSave;
  persona::PieceOfferWrapper mPendingOffer;
};

```

### `PersonaScreenController_vtbl`
```
struct /*VFT*/ PersonaScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
  int (__fastcall *_getRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getColIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getLastRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getRemainderOffers)(StoreBaseScreenController *this, const int);
  void (__fastcall *onCatalogStatusUpdated)(PurchaseEnabledScreenController *this);
};

```

### `PlatformMultiplayerRestrictions`
```
struct __cppobj PlatformMultiplayerRestrictions
{
  PlatformMultiplayerRestrictions_vtbl *__vftable /*VFT*/;
};

```

### `PlatformMultiplayerRestrictions_vtbl`
```
struct /*VFT*/ PlatformMultiplayerRestrictions_vtbl
{
  void (__fastcall *~PlatformMultiplayerRestrictions)(PlatformMultiplayerRestrictions *this);
  bool (__fastcall *platformRestrictsMultiplayer)(PlatformMultiplayerRestrictions *this);
  void (__fastcall *displayPlatformRestrictsMultiplayerModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)>);
  void (__fastcall *displayPlatformRestrictsUserGeneratedContentModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)> *);
  void (__fastcall *displayPlatformRestrictsChatModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)> *);
};

```

### `PermissionsScreenControllerHelper`
```
struct __cppobj PermissionsScreenControllerHelper
{
};

```

### `PackManagerContentSource::PackData`
```
struct __cppobj __declspec(align(8)) PackManagerContentSource::PackData
{
  Core::PathBuffer<std::string > mPath;
  _BYTE mContentType[8];
  std::unique_ptr<CompositePackSource> mPackSource;
  std::vector<PackContentItem *> mPackContent;
  std::vector<PackIdVersion> mSelectedPacksCache;
  std::vector<PackInstanceId> mCachedInstanceIds;
  bool mLoadedInstanceIds;
};

```

### `PackManagerContentSource`
```
struct __cppobj PackManagerContentSource : ContentSource
{
  _BYTE mContentType[8];
  _BYTE mFlags[8];
  ResourcePackManager *mPackManager;
  ResourcePackRepository *mResourceRepository;
  PackManifestFactory *mManifestFactory;
  PackSettingsFactory *mSettingsFactory;
  const IContentKeyProvider *mKeyProvider;
  IEntitlementManager *mEntitlementManager;
  gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > mStoreCatalog;
  const ContentTierManager *mContentTierManager;
  std::vector<PackManagerContentSource::PackData> mPackData;
  std::vector<std::unique_ptr<PackContentItem>> mPackDataContent;
};

```

### `PackManagerContentSource_vtbl`
```
struct /*VFT*/ PackManagerContentSource_vtbl
{
  void (__fastcall *~ContentSource)(ContentSource *this);
  void (__fastcall *load)(ContentSource *this);
  void (__fastcall *generateItems)(ContentSource *this, std::vector<std::unique_ptr<ContentItem>> *);
  void (__fastcall *save)(ContentSource *this);
  void (__fastcall *deleteContentFiles)(ContentSource *this, std::vector<ContentItem const *>);
  void (__fastcall *postDeleteContent)(ContentSource *this, std::vector<ContentItem const *>);
};

```

### `PlayerRewindContext`
```
struct __cppobj PlayerRewindContext : IPlayerMovementProxy
{
  LocalPlayer *mPlayer;
  PlayerSnapshot mSnapshot;
  std::shared_ptr<IActorMovementProxy> mRide;
  std::unique_ptr<IClientInstanceProxy> mClient;
  std::vector<std::shared_ptr<IActorMovementProxy>> mFetchResults;
  std::unique_ptr<MoveInputHandler> mInput;
};

```

### `PolygonOperatorPool<RenderChunkBuilder>::PoolEntry`
```
struct __cppobj PolygonOperatorPool<RenderChunkBuilder>::PoolEntry
{
  const bool mIsImmediate;
  std::unique_ptr<RenderChunkBuilder> mEntry;
};

```

### `PersonaBackendProvider`
```
struct __cppobj PersonaBackendProvider : CatalogBackend
{
};

```

### `PersonaBackendProvider_vtbl`
```
struct /*VFT*/ PersonaBackendProvider_vtbl
{
  void (__fastcall *~CatalogBackend)(CatalogBackend *this);
  const std::string *(__fastcall *getCachedFilePrefix)(CatalogBackend *this);
  bool (__fastcall *usePascalCase)(CatalogBackend *this);
};

```

### `PlayFabEntitlementManager`
```
struct __cppobj PlayFabEntitlementManager : IEntitlementManager, ServiceClient, std::enable_shared_from_this<PlayFabEntitlementManager>
{
  IMinecraftEventing *mEventing;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mEntitlementChangeListeners;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mEntitlementChangeListenersToAdd;
  std::mutex mEntitlementChangeListenerToAddMutex;
  std::unordered_map<ContentIdentity,Entitlement> mInventory;
  std::mutex mInventoryChangeMutex;
  std::unordered_map<enum VirtualCurrencyType,unsigned int> mWallet;
  std::shared_mutex mWalletMutex;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mInventoryEntitlementListeners;
  std::vector<std::weak_ptr<EntitlementChangeListener>> mInventoryEntitlementListenersToAdd;
  std::mutex mInventoryEntitlementListenerToAddMutex;
  std::atomic<bool> mInventoryRefreshStarted;
  std::atomic<bool> mInventoryRefreshed;
  int mNumberOfActiveCoinPurchaseProcesses;
  bool mHaveCachedLegacyOfferInfo;
  std::string mCurrentPurchaseID;
  std::string mPlatformStoreName;
  std::vector<PurchaseInfo> mLegacyDurables;
  std::string mReceipt;
  std::shared_ptr<AccountTransferHandler> mAccountTransferHandler;
  std::unique_ptr<TaskGroup> mAccountTransferTaskGroup;
  std::shared_ptr<PlayFabInventoryVerifier> mInventoryVerifier;
};

```

### `PlayFabEntitlementManager_vtbl`
```
struct /*VFT*/ PlayFabEntitlementManager_vtbl
{
  void (__fastcall *~IEntitlementManager)(IEntitlementManager *this);
  void (__fastcall *tick)(IEntitlementManager *this);
  void (__fastcall *refreshBalance)(IEntitlementManager *this);
  void (__fastcall *refreshInventory)(IEntitlementManager *this);
  std::string *(__fastcall *getInventoryId)(IEntitlementManager *this, std::string *result);
  std::string *(__fastcall *getWalletId)(IEntitlementManager *this, std::string *result);
  std::string *(__fastcall *getCommerceUserID)(IEntitlementManager *this, std::string *result);
  void (__fastcall *processLegacyOfferOwnership)(IEntitlementManager *this, const std::string *, bool, const std::vector<PurchaseInfo> *, const std::string *);
  void (__fastcall *purchaseCoinOffer)(IEntitlementManager *this, const std::string *, const PurchaseInfo *, const std::string *, std::function<void __cdecl(bool)>);
  const std::string *(__fastcall *getTenant)(IEntitlementManager *this);
  void (__fastcall *processExternalStorePurchases)(IEntitlementManager *this, StorePlatform, const std::string *);
  void (__fastcall *processRealmsCoinOfferPurchase)(IEntitlementManager *this, const std::string *, const std::string *, const std::string *, bool, const std::string *, std::function<void __cdecl(enum SendReceiptRealmsResult,Realms::World)>);
  int (__fastcall *getBalance)(IEntitlementManager *this);
  bool (__fastcall *supportsDeviceAccounts)(IEntitlementManager *this);
  bool (__fastcall *hasAnActiveDeviceAccount)(IEntitlementManager *this);
  bool (__fastcall *hasDeviceAccountBeenUsed)(IEntitlementManager *this);
  void (__fastcall *refreshEntitlements)(IEntitlementManager *this);
  void (__fastcall *setRetainedCacheMode)(IEntitlementManager *this, bool);
  StorePlatform (__fastcall *getCommerceStoreNameFromPlatformStoreName)(IEntitlementManager *this, const std::string *);
  Entitlement *(__fastcall *getEntitlement)(IEntitlementManager *this, const ContentIdentity *);
  std::vector<mce::UUID> *(__fastcall *getOwnedEntitlementIds)(IEntitlementManager *this, std::vector<mce::UUID> *result);
  void (__fastcall *getEntitlementsByCreator)(IEntitlementManager *this, const std::string *, std::vector<Entitlement> *);
  void (__fastcall *purchaseCatalogOffer)(IEntitlementManager *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::StoreType, const std::string *, const std::string *, std::function<void __cdecl(enum TransactionStatus)>);
  bool (__fastcall *iapSyncAvailable)(IEntitlementManager *this);
  void (__fastcall *syncIAPs)(IEntitlementManager *this, std::function<void __cdecl(bool)>);
  void (__fastcall *transferDeviceAccountToXboxLive)(IEntitlementManager *this, std::function<void __cdecl(bool)>);
  void (__fastcall *setDeviceEntitlements)(IEntitlementManager *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *addEntitlementChangeListener)(IEntitlementManager *this, std::weak_ptr<EntitlementChangeListener>);
  void (__fastcall *addEntitlementInventoryRefreshListener)(IEntitlementManager *this, std::weak_ptr<EntitlementChangeListener>);
  int (__fastcall *getTransferStatusCode)(IEntitlementManager *this);
  const std::string *(__fastcall *getTransferErrorCorrelationId)(IEntitlementManager *this, const std::string *result);
  bool (__fastcall *hasAccountTransferError)(IEntitlementManager *this);
  bool (__fastcall *hasUnresolvedAccountTransfer)(IEntitlementManager *this);
  bool (__fastcall *hasShownAccountTransferErrorDialog)(IEntitlementManager *this);
  void (__fastcall *setAccountTransferErrorDialogAsShown)(IEntitlementManager *this);
  bool (__fastcall *findLegacyUID)(IEntitlementManager *this, const std::string *, std::vector<std::string> *);
  bool (__fastcall *isProcessingStoreCoinPurchase)(IEntitlementManager *this);
};

```

### `PlayFabEntitlementManager::PrivateInitToken`
```
struct __cppobj PlayFabEntitlementManager::PrivateInitToken
{
};

```

### `PPM_PERFSTATE_DOMAIN_EVENT`
```
struct PPM_PERFSTATE_DOMAIN_EVENT
{
  unsigned int State;
  unsigned int Latency;
  unsigned int Speed;
  unsigned __int64 Processors;
};

```

### `POWER_ACTION_POLICY`
```
struct POWER_ACTION_POLICY
{
  POWER_ACTION Action;
  unsigned int Flags;
  unsigned int EventCode;
};

```

### `PPM_WMI_IDLE_STATE`
```
struct PPM_WMI_IDLE_STATE
{
  unsigned int Latency;
  unsigned int Power;
  unsigned int TimeCheck;
  unsigned __int8 PromotePercent;
  unsigned __int8 DemotePercent;
  unsigned __int8 StateType;
  unsigned __int8 Reserved;
  unsigned int StateFlags;
  unsigned int Context;
  unsigned int IdleHandler;
  unsigned int Reserved1;
};

```

### `PPM_WMI_IDLE_STATES_EX`
```
struct PPM_WMI_IDLE_STATES_EX
{
  unsigned int Type;
  unsigned int Count;
  unsigned int TargetState;
  unsigned int OldState;
  void *TargetProcessors;
  PPM_WMI_IDLE_STATE State[1];
};

```

### `pvalueW`
```
struct __declspec(align(8)) pvalueW
{
  wchar_t *pv_valuename;
  int pv_valuelen;
  void *pv_value_context;
  unsigned int pv_type;
};

```

### `provider_info`
```
struct provider_info
{
  unsigned int (__fastcall *pi_R0_1val)(void *, val_context *, unsigned int, void *, unsigned int *, unsigned int);
  unsigned int (__fastcall *pi_R0_allvals)(void *, val_context *, unsigned int, void *, unsigned int *, unsigned int);
  unsigned int (__fastcall *pi_R3_1val)(void *, val_context *, unsigned int, void *, unsigned int *, unsigned int);
  unsigned int (__fastcall *pi_R3_allvals)(void *, val_context *, unsigned int, void *, unsigned int *, unsigned int);
  unsigned int pi_flags;
  void *pi_key_context;
};

```

### `PPM_WMI_PERF_STATE`
```
struct PPM_WMI_PERF_STATE
{
  unsigned int Frequency;
  unsigned int Power;
  unsigned __int8 PercentFrequency;
  unsigned __int8 IncreaseLevel;
  unsigned __int8 DecreaseLevel;
  unsigned __int8 Type;
  unsigned int IncreaseTime;
  unsigned int DecreaseTime;
  unsigned __int64 Control;
  unsigned __int64 Status;
  unsigned int HitCount;
  unsigned int Reserved1;
  unsigned __int64 Reserved2;
  unsigned __int64 Reserved3;
};

```

### `pollfd`
```
struct __declspec(align(8)) pollfd
{
  unsigned __int64 fd;
  __int16 events;
  __int16 revents;
};

```

### `protoent`
```
struct __declspec(align(8)) protoent
{
  char *p_name;
  char **p_aliases;
  __int16 p_proto;
};

```

### `PPM_WMI_PERF_STATES_EX`
```
struct PPM_WMI_PERF_STATES_EX
{
  unsigned int Count;
  unsigned int MaxFrequency;
  unsigned int CurrentState;
  unsigned int MaxPerfState;
  unsigned int MinPerfState;
  unsigned int LowestPerfState;
  unsigned int ThermalConstraint;
  unsigned __int8 BusyAdjThreshold;
  unsigned __int8 PolicyType;
  unsigned __int8 Type;
  unsigned __int8 Reserved;
  unsigned int TimerInterval;
  void *TargetProcessors;
  unsigned int PStateHandler;
  unsigned int PStateContext;
  unsigned int TStateHandler;
  unsigned int TStateContext;
  unsigned int FeedbackHandler;
  unsigned int Reserved1;
  unsigned __int64 Reserved2;
  PPM_WMI_PERF_STATE State[1];
};

```

### `PROCESSOR_IDLESTATE_INFO`
```
struct PROCESSOR_IDLESTATE_INFO
{
  unsigned int TimeCheck;
  unsigned __int8 DemotePercent;
  unsigned __int8 PromotePercent;
  unsigned __int8 Spare[2];
};

```

### `PPM_PERFSTATE_EVENT`
```
struct PPM_PERFSTATE_EVENT
{
  unsigned int State;
  unsigned int Status;
  unsigned int Latency;
  unsigned int Speed;
  unsigned int Processor;
};

```

### `pvalueA`
```
struct __declspec(align(8)) pvalueA
{
  char *pv_valuename;
  int pv_valuelen;
  void *pv_value_context;
  unsigned int pv_type;
};

```

### `PPM_IDLE_STATE_BUCKET_EX`
```
struct __declspec(align(8)) PPM_IDLE_STATE_BUCKET_EX
{
  unsigned __int64 TotalTimeUs;
  unsigned int MinTimeUs;
  unsigned int MaxTimeUs;
  unsigned int Count;
};

```

### `PPM_IDLE_STATE_ACCOUNTING_EX`
```
struct PPM_IDLE_STATE_ACCOUNTING_EX
{
  unsigned __int64 TotalTime;
  unsigned int IdleTransitions;
  unsigned int FailedTransitions;
  unsigned int InvalidBucketIndex;
  unsigned int MinTimeUs;
  unsigned int MaxTimeUs;
  unsigned int CancelledTransitions;
  PPM_IDLE_STATE_BUCKET_EX IdleTimeBuckets[16];
};

```

### `PPM_THERMAL_POLICY_EVENT`
```
struct PPM_THERMAL_POLICY_EVENT
{
  unsigned __int8 Mode;
  unsigned __int64 Processors;
};

```

### `PPM_THERMALCHANGE_EVENT`
```
struct PPM_THERMALCHANGE_EVENT
{
  unsigned int ThermalConstraint;
  unsigned __int64 Processors;
};

```

### `PPM_IDLE_STATE_ACCOUNTING`
```
struct PPM_IDLE_STATE_ACCOUNTING
{
  unsigned int IdleTransitions;
  unsigned int FailedTransitions;
  unsigned int InvalidBucketIndex;
  unsigned __int64 TotalTime;
  unsigned int IdleTimeBuckets[6];
};

```

### `POWERBROADCAST_SETTING`
```
struct __declspec(align(4)) POWERBROADCAST_SETTING
{
  _GUID PowerSetting;
  unsigned int DataLength;
  unsigned __int8 Data[1];
};

```

### `PROCESS_PROTECTION_LEVEL_INFORMATION`
```
struct PROCESS_PROTECTION_LEVEL_INFORMATION
{
  unsigned int ProtectionLevel;
};

```

### `PPM_WMI_LEGACY_PERFSTATE`
```
struct PPM_WMI_LEGACY_PERFSTATE
{
  unsigned int Frequency;
  unsigned int Flags;
  unsigned int PercentFrequency;
};

```

### `PPM_WMI_IDLE_STATES`
```
struct PPM_WMI_IDLE_STATES
{
  unsigned int Type;
  unsigned int Count;
  unsigned int TargetState;
  unsigned int OldState;
  unsigned __int64 TargetProcessors;
  PPM_WMI_IDLE_STATE State[1];
};

```

### `PPM_WMI_PERF_STATES`
```
struct PPM_WMI_PERF_STATES
{
  unsigned int Count;
  unsigned int MaxFrequency;
  unsigned int CurrentState;
  unsigned int MaxPerfState;
  unsigned int MinPerfState;
  unsigned int LowestPerfState;
  unsigned int ThermalConstraint;
  unsigned __int8 BusyAdjThreshold;
  unsigned __int8 PolicyType;
  unsigned __int8 Type;
  unsigned __int8 Reserved;
  unsigned int TimerInterval;
  unsigned __int64 TargetProcessors;
  unsigned int PStateHandler;
  unsigned int PStateContext;
  unsigned int TStateHandler;
  unsigned int TStateContext;
  unsigned int FeedbackHandler;
  unsigned int Reserved1;
  unsigned __int64 Reserved2;
  PPM_WMI_PERF_STATE State[1];
};

```

### `PPM_IDLE_ACCOUNTING`
```
struct PPM_IDLE_ACCOUNTING
{
  unsigned int StateCount;
  unsigned int TotalTransitions;
  unsigned int ResetCount;
  unsigned __int64 StartTime;
  PPM_IDLE_STATE_ACCOUNTING State[1];
};

```

### `PPM_IDLE_ACCOUNTING_EX`
```
struct PPM_IDLE_ACCOUNTING_EX
{
  unsigned int StateCount;
  unsigned int TotalTransitions;
  unsigned int ResetCount;
  unsigned int AbortCount;
  unsigned __int64 StartTime;
  PPM_IDLE_STATE_ACCOUNTING_EX State[1];
};

```

### `PPM_IDLESTATE_EVENT`
```
struct PPM_IDLESTATE_EVENT
{
  unsigned int NewState;
  unsigned int OldState;
  unsigned __int64 Processors;
};

```

### `PROCESSOR_IDLESTATE_POLICY`
```
struct PROCESSOR_IDLESTATE_POLICY
{
  unsigned __int16 Revision;
  PROCESSOR_IDLESTATE_POLICY::<unnamed_type_Flags> Flags;
  unsigned int PolicyCount;
  PROCESSOR_IDLESTATE_INFO Policy[3];
};

```

### `PROCESSOR_PERFSTATE_POLICY`
```
struct PROCESSOR_PERFSTATE_POLICY
{
  unsigned int Revision;
  unsigned __int8 MaxThrottle;
  unsigned __int8 MinThrottle;
  unsigned __int8 BusyAdjThreshold;
  $59563F0AC150289665E230792CDDE314 ___u4;
  unsigned int TimeCheck;
  unsigned int IncreaseTime;
  unsigned int DecreaseTime;
  unsigned int IncreasePercent;
  unsigned int DecreasePercent;
};

```

### `PortalBehavior`
```
struct __cppobj PortalBehavior : CameraBehavior<PortalBehavior>
{
};

```

### `PortalBehavior_vtbl`
```
struct /*VFT*/ PortalBehavior_vtbl
{
  void (__fastcall *~ICameraBehavior)(ICameraBehavior *this);
  void (__fastcall *onSetup)(ICameraBehavior *this, IClientInstance *, CameraDirector *);
  void (__fastcall *onStart)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *update)(ICameraBehavior *this, IClientInstance *, float, float, CameraDirector *);
  void (__fastcall *handleLookInput)(ICameraBehavior *this, Vec2 *, CameraDirector *);
  void (__fastcall *renderDebug)(ICameraBehavior *this, IClientInstance *, float, CameraDirector *);
  bool (__fastcall *handleCameraSetRot)(ICameraBehavior *this, const Vec2 *, CameraDirector *);
  HashedString *(__fastcall *getId)(ICameraBehavior *this, HashedString *result);
  ICameraBehavior::UpdateOrder (__fastcall *getUpdateOrder)(ICameraBehavior *this);
};

```

### `PortalBehaviorLoader`
```
struct __cppobj PortalBehaviorLoader : CameraBehaviorLoader
{
};

```

### `PortalBehaviorLoader_vtbl`
```
struct /*VFT*/ PortalBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `ParticleSystem::ParticleEmitterActual::AABBCacheElement`
```
struct __cppobj __declspec(align(8)) ParticleSystem::ParticleEmitterActual::AABBCacheElement
{
  std::vector<AABB> mAABBList;
  unsigned int mLastAccessedFrame;
};

```

### `ParticleTrackingSystem`
```
struct __cppobj ParticleTrackingSystem : ITickingSystem
{
  IClientInstance *mClientInstance;
};

```

### `ParticleTrackingSystem_vtbl`
```
struct /*VFT*/ ParticleTrackingSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `ParticleInitializationData`
```
struct __cppobj __declspec(align(8)) ParticleInitializationData
{
  HashedString mAnimationControllerName;
  ParticleEffectPtr mEffect;
  HashedString mLocator;
  ExpressionNode mInitializationScript;
  bool mBind;
};

```

### `ParticleRenderer::BucketKey`
```
struct __cppobj ParticleRenderer::BucketKey
{
  $F1DA7A447DB928EE5362B747D1C23332 ___u0;
};

```

### `ParticleRenderer::RenderBucketData`
```
struct __cppobj ParticleRenderer::RenderBucketData
{
  buffer_span<unsigned __int64> mParticleIndexList;
  ScreenContext *mScreenContext;
  const Vec3 *mCameraTargetPos;
  const Vec3 *mCameraPos;
  const ParticleRenderData *mParticleRenderData;
  unsigned __int64 mTextureIdx;
  unsigned __int64 mMaterialIdx;
};

```

### `PlayerMovementTelemetryData`
```
struct __cppobj PlayerMovementTelemetryData
{
  int mCount;
  float mTotalPosDelta;
  float mMinPosDelta;
  float mMaxPosDelta;
};

```

### `PlayScreenModel`
```
struct __cppobj PlayScreenModel : MainMenuScreenModel, ILocalWorldsProvider
{
  bool mIsDirty;
  std::vector<LocalWorldInfo> mLocalWorldList;
  std::vector<LocalWorldInfo> mBetaRetailLocalWorldList;
  std::vector<WorldTemplateInfo> mWorldTemplates;
  std::vector<NetworkWorldInfo> mFriendsNetworkWorldList;
  std::vector<NetworkWorldInfo> mCrossPlatformFriendsNetworkWorldList;
  std::vector<NetworkWorldInfo> mLANNetworkWorldList;
  std::vector<NetworkWorldInfo> mServerNetworkWorldList;
  std::vector<RealmsWorldInfo> mRealmWorldList;
  std::vector<std::shared_ptr<NetworkWorldInfo>> mThirdPartyServerWorldList;
  std::vector<LegacyWorldInfo> mLegacyWorldList;
  std::vector<LegacyWorldInfo> mBetaRetailLegacyWorldList;
  std::unordered_map<std::string,Social::UserPicturePath> mNetworkedFriendsGamerpicMap;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mUpdateTimes[9];
  std::vector<Realms::World> mWorlds;
  int mRealmWorldPartitionIndex;
  bool mHasPendingInvites;
  int mPendingInviteCount;
  bool mFetchingInvites;
  bool mOwnsRealm;
  bool mFetchingRealmsWorlds;
  bool mFetchingLegacyWorldsInProgress;
  bool mLegacyWorldsFetched;
  bool mFoundLegacyWorlds;
  LegacyWorldConversionManager mLegacyWorldConversionManager;
  bool mFetchingPlayerCounts;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastRealmsUpdate;
  bool mJoiningRealm;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastTryJoin;
  std::chrono::duration<__int64,std::ratio<1,1> > mRetryJoinInterval;
  int mRetryTime;
  std::unique_ptr<PackSource> mWorldTemplateSource;
  std::unique_ptr<Legacy::WorldImporter> mLegacyWorldImporter;
  CallbackToken mRetrieveCallbackToken;
  CallbackToken mImportCallbackToken;
  bool mFirstRealmsFetchComplete;
  Realms::GenericStatus mRealmsStatus;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPlayerCountUpdate;
  PlayScreenModel::LevelListCacheObserver mLevelListCacheObserver;
};

```

### `PlayScreenModel::LevelListCacheObserver`
```
struct __cppobj PlayScreenModel::LevelListCacheObserver : LevelLocationObserver
{
  PlayScreenModel *mModel;
};

```

### `PlayScreenModel::LevelListCacheObserver_vtbl`
```
struct /*VFT*/ PlayScreenModel::LevelListCacheObserver_vtbl
{
  void (__fastcall *~Observer<LevelLocationObserver,Core::SingleThreadedLock>)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onLevelAdded)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelUpdated)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelDeleted)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onStorageChanged)(LevelLocationObserver *this);
};

```

### `PlayScreenModel_vtbl`
```
struct /*VFT*/ PlayScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `PlayScreenModel::LiveServer`
```
struct __cppobj __declspec(align(8)) PlayScreenModel::LiveServer
{
  std::unique_ptr<Social::MultiplayerGameInfo> server;
  bool found;
  long double lastFoundTime;
  bool dead;
};

```

### `ParameterStringify`
```
struct __cppobj ParameterStringify
{
};

```

### `PerfTimer::Node`
```
struct __cppobj PerfTimer::Node
{
  const char *name;
  const char *function;
  int line;
  unsigned __int16 elementCount;
  long double inclusiveTime;
  long double startTime;
  PerfTimer::Node *elements;
};

```

### `PerfTimer`
```
struct __cppobj PerfTimer
{
  std::map<std::string,double> mLogEventMap;
  std::vector<gsl::not_null<PerfTimer::Node *>> mNodeStack;
  std::array<std::vector<PerfTimer::Node *>,14> mIdleNodes;
  std::vector<std::unique_ptr<PerfTimer::Node [0]>> mAllocations;
  int mCurrentStackLevel;
  Core::OutputFileStream mOutputStream;
  std::unordered_map<char const *,int> mStringLookupMap;
  int mCurrentString;
  std::unique_ptr<RakNet::BitStream> mBitStream;
  std::thread::id mCurrentThreadId;
  unsigned int mNumberOfRootObjects;
};

```

### `ProfilerResourceUsage`
```
struct __cppobj ProfilerResourceUsage
{
  __int64 totalUsedMemory;
  __int64 maxUsedMemory;
  __int64 bufferUsedMemory;
  __int64 bufferCount;
  __int64 textureUsedMemory;
  __int64 textureCount;
};

```

### `Parser`
```
struct __cppobj Parser
{
};

```

### `ProjectileItemComponent`
```
struct __cppobj ProjectileItemComponent : ItemComponent
{
  float mMinCriticalPower;
  ActorDefinitionIdentifier mActorIdentifier;
};

```

### `ProjectileItemComponent_vtbl`
```
struct /*VFT*/ ProjectileItemComponent_vtbl
{
  void (__fastcall *~ItemComponent)(ItemComponent *this);
  bool (__fastcall *checkComponentDataForContentErrors)(ItemComponent *this);
  void (__fastcall *writeSettings)(ItemComponent *this);
  bool (__fastcall *useOn)(ItemComponent *this, ItemStack *, Actor *, const BlockPos *, unsigned __int8, const Vec3 *);
  bool (__fastcall *isNetworkComponent)(ItemComponent *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(ItemComponent *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(ItemComponent *this, const CompoundTag *);
};

```

### `PlanterItemComponent`
```
struct __cppobj PlanterItemComponent : ItemComponent
{
  BlockLegacyPtr mBlock;
  std::vector<BlockDescriptor> mAllowedUseBlocks;
};

```

### `PlanterItemComponent_vtbl`
```
struct /*VFT*/ PlanterItemComponent_vtbl
{
  void (__fastcall *~ItemComponent)(ItemComponent *this);
  bool (__fastcall *checkComponentDataForContentErrors)(ItemComponent *this);
  void (__fastcall *writeSettings)(ItemComponent *this);
  bool (__fastcall *useOn)(ItemComponent *this, ItemStack *, Actor *, const BlockPos *, unsigned __int8, const Vec3 *);
  bool (__fastcall *isNetworkComponent)(ItemComponent *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(ItemComponent *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(ItemComponent *this, const CompoundTag *);
};

```

### `PotionTypeEnumHasher`
```
struct __cppobj PotionTypeEnumHasher
{
};

```

### `PotionBrewing`
```
struct __cppobj PotionBrewing
{
};

```

### `PotionBrewing::Mix<ItemDescriptor>`
```
struct __cppobj PotionBrewing::Mix<ItemDescriptor>
{
  ItemDescriptor mFrom;
  PotionBrewing::Ingredient mIngredient;
  ItemDescriptor mTo;
};

```

### `PotionBrewing::Mix<Item const &>`
```
struct __cppobj PotionBrewing::Mix<Item const &>
{
  const Item *mFrom;
  PotionBrewing::Ingredient mIngredient;
  const Item *mTo;
};

```

### `PotionBrewing::Mix<ItemInstance>`
```
struct __cppobj PotionBrewing::Mix<ItemInstance>
{
  ItemInstance mFrom;
  PotionBrewing::Ingredient mIngredient;
  ItemInstance mTo;
};

```

### `PatchListStage`
```
struct __cppobj __declspec(align(8)) PatchListStage : BaseStage
{
  int mErrorCode;
};

```

### `PatchListStage_vtbl`
```
struct /*VFT*/ PatchListStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `PatchUpdateStage`
```
struct __cppobj PatchUpdateStage : BaseStage
{
  bool mUpdateWithContent;
  int mErrorCode;
};

```

### `PatchUpdateStage_vtbl`
```
struct /*VFT*/ PatchUpdateStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `PythonRuntime_vtbl`
```
struct /*VFT*/ PythonRuntime_vtbl
{
  void (__fastcall *~ScriptRuntime)(ScriptRuntime *this);
  bool (__fastcall *startUp)(ScriptRuntime *this, const std::string *);
  void (__fastcall *cleanUp)(ScriptRuntime *this);
  bool (__fastcall *init)(ScriptRuntime *this);
  bool (__fastcall *start)(ScriptRuntime *this);
  bool (__fastcall *test)(ScriptRuntime *this);
  ScriptInstance *(__fastcall *createInstance)(ScriptRuntime *this, void *);
  ScriptInstance *(__fastcall *createInstance)(ScriptRuntime *this, const std::string *);
  void (__fastcall *destroyInstance)(ScriptRuntime *this, ScriptInstance *);
  const std::string *(__fastcall *getScriptPath)(ScriptRuntime *this);
};

```

### `PanoramaRenderer`
```
struct __cppobj __declspec(align(4)) PanoramaRenderer : MinecraftUICustomRenderer
{
  _BYTE mRotationStyle[4];
  float mUVxOffset;
  float mGestureVel;
  bool mHasSetStartingPosition;
};

```

### `PanoramaRenderer_vtbl`
```
struct /*VFT*/ PanoramaRenderer_vtbl
{
  void (__fastcall *~UICustomRenderer)(UICustomRenderer *this);
  void (__fastcall *preRenderSetup)(UICustomRenderer *this, UIRenderContext *);
  std::shared_ptr<UICustomRenderer> *(__fastcall *clone)(UICustomRenderer *this, std::shared_ptr<UICustomRenderer> *result);
  bool (__fastcall *update)(UICustomRenderer *this, IClientInstance *, UIControl *, const UIScene *);
  void (__fastcall *frameUpdate)(UICustomRenderer *this, UIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(UICustomRenderer *this, UIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  UIBatchType (__fastcall *getBatchType)(UICustomRenderer *this);
  int (__fastcall *getCustomId)(UICustomRenderer *this);
  int (__fastcall *getNumRenderPasses)(UICustomRenderer *this);
  ResourceLocation *(__fastcall *getResourceLocation)(UICustomRenderer *this, ResourceLocation *result, int, int);
  UIMaterialType (__fastcall *getUIMaterialType)(UICustomRenderer *this, int);
  bool (__fastcall *getRequiresPreRenderSetup)(UICustomRenderer *this, int);
  void (__fastcall *onVisibilityChanged)(UICustomRenderer *this, bool);
  void (__fastcall *collectScreenEvents)(UICustomRenderer *this, std::queue<ScreenEvent> *);
  void (__fastcall *frameUpdate)(MinecraftUICustomRenderer *this, MinecraftUIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  void (__fastcall *preRenderSetup)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *);
};

```

### `PaperDollRenderer_vtbl`
```
struct /*VFT*/ PaperDollRenderer_vtbl
{
  void (__fastcall *~UICustomRenderer)(UICustomRenderer *this);
  void (__fastcall *preRenderSetup)(UICustomRenderer *this, UIRenderContext *);
  std::shared_ptr<UICustomRenderer> *(__fastcall *clone)(UICustomRenderer *this, std::shared_ptr<UICustomRenderer> *result);
  bool (__fastcall *update)(UICustomRenderer *this, IClientInstance *, UIControl *, const UIScene *);
  void (__fastcall *frameUpdate)(UICustomRenderer *this, UIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(UICustomRenderer *this, UIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  UIBatchType (__fastcall *getBatchType)(UICustomRenderer *this);
  int (__fastcall *getCustomId)(UICustomRenderer *this);
  int (__fastcall *getNumRenderPasses)(UICustomRenderer *this);
  ResourceLocation *(__fastcall *getResourceLocation)(UICustomRenderer *this, ResourceLocation *result, int, int);
  UIMaterialType (__fastcall *getUIMaterialType)(UICustomRenderer *this, int);
  bool (__fastcall *getRequiresPreRenderSetup)(UICustomRenderer *this, int);
  void (__fastcall *onVisibilityChanged)(UICustomRenderer *this, bool);
  void (__fastcall *collectScreenEvents)(UICustomRenderer *this, std::queue<ScreenEvent> *);
  void (__fastcall *frameUpdate)(MinecraftUICustomRenderer *this, MinecraftUIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  void (__fastcall *preRenderSetup)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *);
};

```

### `ProgressBarRenderer`
```
struct __cppobj ProgressBarRenderer : MinecraftUICustomRenderer
{
  mce::Color mPrimaryColor;
  mce::Color mSecondaryColor;
};

```

### `ProgressBarRenderer_vtbl`
```
struct /*VFT*/ ProgressBarRenderer_vtbl
{
  void (__fastcall *~UICustomRenderer)(UICustomRenderer *this);
  void (__fastcall *preRenderSetup)(UICustomRenderer *this, UIRenderContext *);
  std::shared_ptr<UICustomRenderer> *(__fastcall *clone)(UICustomRenderer *this, std::shared_ptr<UICustomRenderer> *result);
  bool (__fastcall *update)(UICustomRenderer *this, IClientInstance *, UIControl *, const UIScene *);
  void (__fastcall *frameUpdate)(UICustomRenderer *this, UIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(UICustomRenderer *this, UIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  UIBatchType (__fastcall *getBatchType)(UICustomRenderer *this);
  int (__fastcall *getCustomId)(UICustomRenderer *this);
  int (__fastcall *getNumRenderPasses)(UICustomRenderer *this);
  ResourceLocation *(__fastcall *getResourceLocation)(UICustomRenderer *this, ResourceLocation *result, int, int);
  UIMaterialType (__fastcall *getUIMaterialType)(UICustomRenderer *this, int);
  bool (__fastcall *getRequiresPreRenderSetup)(UICustomRenderer *this, int);
  void (__fastcall *onVisibilityChanged)(UICustomRenderer *this, bool);
  void (__fastcall *collectScreenEvents)(UICustomRenderer *this, std::queue<ScreenEvent> *);
  void (__fastcall *frameUpdate)(MinecraftUICustomRenderer *this, MinecraftUIFrameUpdateContext *, UIControl *);
  void (__fastcall *render)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *, IClientInstance *, UIControl *, int, RectangleArea *);
  void (__fastcall *preRenderSetup)(MinecraftUICustomRenderer *this, MinecraftUIRenderContext *);
};

```

### `PDPSummaryScreenController`
```
struct __cppobj __declspec(align(8)) PDPSummaryScreenController : MainMenuScreenController
{
  const StoreCatalogItem *mItem;
  int mCollectionIndexOffset;
};

```

### `PDPSummaryScreenController_vtbl`
```
struct /*VFT*/ PDPSummaryScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PackMover`
```
struct __cppobj PackMover
{
};

```

### `PurchaseProgressHandler`
```
struct __cppobj __declspec(align(8)) PurchaseProgressHandler : EmptyProgressHandler
{
  std::function<void __cdecl(void)> mOnTick;
  bool mShowTitle;
};

```

### `PurchaseProgressHandler_vtbl`
```
struct /*VFT*/ PurchaseProgressHandler_vtbl
{
  void (__fastcall *~ProgressHandler)(ProgressHandler *this);
  void (__fastcall *onStart)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *tick)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onCancel)(ProgressHandler *this, MinecraftScreenModel *);
  void (__fastcall *onExit)(ProgressHandler *this, MinecraftScreenModel *);
  LoadingState (__fastcall *getLoadingState)(ProgressHandler *this, MinecraftScreenModel *);
  float (__fastcall *getLoadingProgress)(ProgressHandler *this, MinecraftScreenModel *);
  std::string *(__fastcall *getProgressMessage)(ProgressHandler *this, std::string *result, MinecraftScreenModel *);
  void (__fastcall *addEventProperties)(ProgressHandler *this, std::unordered_map<std::string,std::string> *);
  std::string *(__fastcall *getTTSProgressMessage)(ProgressHandler *this, std::string *result);
  std::string *(__fastcall *getTitleText)(ProgressHandler *this, std::string *result);
  ProgressAnimation (__fastcall *showLoadingBar)(ProgressHandler *this);
};

```

### `ptr_move<std::shared_ptr<LevelChunk> >`
```
struct __cppobj ptr_move<std::shared_ptr<LevelChunk> >
{
};

```

### `ProgressiveTakeButtonData`
```
struct __cppobj ProgressiveTakeButtonData
{
  SlotData mSlotData;
  int mHeldTime;
  int mStartHeldTime;
};

```

### `PauseScreenModel`
```
struct __cppobj PauseScreenModel : ClientInstanceScreenModel
{
};

```

### `PauseScreenModel_vtbl`
```
struct /*VFT*/ PauseScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `PlayScreenController_vtbl`
```
struct /*VFT*/ PlayScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PackErrorInfo`
```
struct __cppobj PackErrorInfo
{
  std::string type;
  std::string file;
  std::string text;
};

```

### `PackAccessStrategyFactory`
```
struct __cppobj PackAccessStrategyFactory
{
};

```

### `PackDiscoveryError_vtbl`
```
struct /*VFT*/ PackDiscoveryError_vtbl
{
  void (__fastcall *~PackError)(PackError *this);
  std::string *(__fastcall *getLocErrorMessage)(PackError *this, std::string *result);
  const std::unordered_map<int,std::string> *(__fastcall *getLocErrorMessageMap)(PackError *this);
  const std::unordered_map<int,std::string> *(__fastcall *getEventErrorMessageMap)(PackError *this);
};

```

### `PackSettingsScreenController`
```
struct __cppobj PackSettingsScreenController : MainMenuScreenController
{
  bool mHasOpened;
  PackSettingsInfo mPackSettingsInfo;
  PackSettings *mPackSettings;
  DynamicFormScreenController *mDynamicFormScreenController;
};

```

### `PackSettingsScreenController_vtbl`
```
struct /*VFT*/ PackSettingsScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PackSettingsJsonValidator`
```
struct __cppobj PackSettingsJsonValidator
{
};

```

### `PatchNotesScreenController`
```
struct __cppobj PatchNotesScreenController : MainMenuScreenController
{
};

```

### `PatchNotesScreenController_vtbl`
```
struct /*VFT*/ PatchNotesScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PatchNoticeScreenController`
```
struct __cppobj PatchNoticeScreenController : MinecraftScreenController
{
};

```

### `PatchNoticeScreenController_vtbl`
```
struct /*VFT*/ PatchNoticeScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PermissionsScreenController`
```
struct __cppobj PermissionsScreenController : ClientInstanceScreenController
{
  bool mEDUPermissionsPopupActive;
  bool mPermissionDropdownActive;
  Abilities mStartAbilityCache;
  Abilities mAbilities;
  ActorUniqueID mDefaultPlayerId;
  unsigned __int64 mSelectedPlayerIndex;
  bool mCanEdit;
  bool mPlayerListInitialized;
  bool mContentAreaActive;
  std::vector<std::string> mPermissionNames;
  std::vector<ActorUniqueID> mClientIds;
  std::weak_ptr<UserDataScreenController> mUserDataScreenController;
};

```

### `PermissionsScreenController_vtbl`
```
struct /*VFT*/ PermissionsScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PauseScreenController`
```
struct __cppobj __declspec(align(8)) PauseScreenController : ClientInstanceScreenController
{
  std::vector<ActorUniqueID> mClientIds;
  ActorUniqueID mCurrentClientId;
  bool mPlayerListInitialized;
  std::weak_ptr<UserDataScreenController> mUserDataScreenController;
  std::weak_ptr<PermissionsScreenController> mPermissionsScreenController;
  std::shared_ptr<PauseScreenModel> mPauseScreenModel;
  bool mScoreboardShowing;
  bool mPersonaEnabled;
};

```

### `PauseScreenController_vtbl`
```
struct /*VFT*/ PauseScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PauseScreenController::_feedbackDialogConsoleLinks::__l2::<lambda_6983acf81e2e294b2465996da9164bdc>`
```
struct __cppobj PauseScreenController::_feedbackDialogConsoleLinks::__l2::<lambda_6983acf81e2e294b2465996da9164bdc>
{
  std::weak_ptr<PauseScreenController> weakThis;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_1ab64bfa275f701c324202dda32e7ec1>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_1ab64bfa275f701c324202dda32e7ec1>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_3570b20128fb96748cc88f2fa8e2a714>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_3570b20128fb96748cc88f2fa8e2a714>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_a42fe3e74a759970304d53292e03e7de>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_a42fe3e74a759970304d53292e03e7de>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_665ebaeea45a24be7ac9e038911bc390>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_665ebaeea45a24be7ac9e038911bc390>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_dccd54d8e060885f3df3798a6c1de04d>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_dccd54d8e060885f3df3798a6c1de04d>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_a43f4e3a3fe659b764eba52714de24ae>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_a43f4e3a3fe659b764eba52714de24ae>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_cd11df4a4a6e085c878abcd40c5f1e37>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_cd11df4a4a6e085c878abcd40c5f1e37>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_ffd644ed4c0291435d2ca042a71f98c7>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_ffd644ed4c0291435d2ca042a71f98c7>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_43725c5329a6e394999d95bac5abff78>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_43725c5329a6e394999d95bac5abff78>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_d551def9ac34f081615a4067cba76cc1>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_d551def9ac34f081615a4067cba76cc1>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_65c36989270c79713eb9a0a81afe2f27>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_65c36989270c79713eb9a0a81afe2f27>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_05a01a67eeaaee782a66ed38aa8636ad>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_05a01a67eeaaee782a66ed38aa8636ad>
{
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_01fb71e1299d9f539d3e10ad8331d133>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_01fb71e1299d9f539d3e10ad8331d133>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_e71b9be4cbd92e9f42e70a2456781580>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_e71b9be4cbd92e9f42e70a2456781580>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_c9d6d13f9371dbb3ab0329bb2caeeed4>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_c9d6d13f9371dbb3ab0329bb2caeeed4>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_09870e6cbdd38363ace19553534555fe>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_09870e6cbdd38363ace19553534555fe>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_0c10bf3190864049a0ad6185b6159801>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_0c10bf3190864049a0ad6185b6159801>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_3ed685128599b73261c99ee5d074feb3>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_3ed685128599b73261c99ee5d074feb3>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_6854126c9995451a9731eb68bb022e3a>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_6854126c9995451a9731eb68bb022e3a>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_16103ca310f5f041630d386d772eba7b>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_16103ca310f5f041630d386d772eba7b>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_07a5ef2dbee44b10f1afd7361a21807e>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_07a5ef2dbee44b10f1afd7361a21807e>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerBindings::__l2::<lambda_a6c3a974438ac8450ccacc46f2cd427d>`
```
struct __cppobj PauseScreenController::_registerBindings::__l2::<lambda_a6c3a974438ac8450ccacc46f2cd427d>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_5ea56c82dc980967d8e7db6ad049ba4f>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_5ea56c82dc980967d8e7db6ad049ba4f>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_6b4973623e6f3c610bf16cb8c5ed30fd>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_6b4973623e6f3c610bf16cb8c5ed30fd>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_3f73144bed79cbd982fe42aa9784451a>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_3f73144bed79cbd982fe42aa9784451a>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_127372b64b9b232b57aea1ab94b0f046>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_127372b64b9b232b57aea1ab94b0f046>
{
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_4d4987cf5d16d2e8fd05fce9c8f0ca19>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_4d4987cf5d16d2e8fd05fce9c8f0ca19>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_e87163e72e7effd7742fdc1c4590a4f9>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_e87163e72e7effd7742fdc1c4590a4f9>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_913f753c8e051e2976f10d2893333e42>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_913f753c8e051e2976f10d2893333e42>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_913f753c8e051e2976f10d2893333e42>::()::__l8::<lambda_6b1d53f398d5188a9cccd6b25493d19f>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_913f753c8e051e2976f10d2893333e42>::()::__l8::<lambda_6b1d53f398d5188a9cccd6b25493d19f>
{
  std::weak_ptr<PauseScreenController> weakThis;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_94380f3f256ebc1733a1bfc8e6bd65ce>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_94380f3f256ebc1733a1bfc8e6bd65ce>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_2b588935c21d5bd1f61b85b39adf2889>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_2b588935c21d5bd1f61b85b39adf2889>
{
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_a44eaa5e9d9563bb2f0885eac8433a99>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_a44eaa5e9d9563bb2f0885eac8433a99>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_a44eaa5e9d9563bb2f0885eac8433a99>::()::__l2::<lambda_5c145f3bc2225c86042525a239871cd9>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_a44eaa5e9d9563bb2f0885eac8433a99>::()::__l2::<lambda_5c145f3bc2225c86042525a239871cd9>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_fc4d9e4d2acd1230b79af0a2cf3da90e>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_fc4d9e4d2acd1230b79af0a2cf3da90e>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_7bcbfdc98351ce459edd60da7d37445c>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_7bcbfdc98351ce459edd60da7d37445c>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_496d22333626e0af5bcafb90dc268f42>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_496d22333626e0af5bcafb90dc268f42>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_8c24fbc10f8e01e1dbd1d6f4e1164a35>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_8c24fbc10f8e01e1dbd1d6f4e1164a35>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_62c5e01370a2e4961d3de04e3a239714>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_62c5e01370a2e4961d3de04e3a239714>
{
  PauseScreenController *const __this;
};

```

### `PauseScreenController::_registerEventHandlers::__l2::<lambda_ae46f317fd53a7d0dd001416bb9fc29b>`
```
struct __cppobj PauseScreenController::_registerEventHandlers::__l2::<lambda_ae46f317fd53a7d0dd001416bb9fc29b>
{
  PauseScreenController *const __this;
};

```

### `PatchNoticeScreenController::_registerBindings::__l2::<lambda_0b0eb55ab895f84e805b220087a9cf49>`
```
struct __cppobj PatchNoticeScreenController::_registerBindings::__l2::<lambda_0b0eb55ab895f84e805b220087a9cf49>
{
};

```

### `PatchNoticeScreenController::_registerBindings::__l2::<lambda_b509981d15b4e61625db1e48d7b94e20>`
```
struct __cppobj PatchNoticeScreenController::_registerBindings::__l2::<lambda_b509981d15b4e61625db1e48d7b94e20>
{
};

```

### `PatchNoticeScreenController::_registerBindings::__l2::<lambda_f54d55899770a58de2ef552ee06a2a8f>`
```
struct __cppobj PatchNoticeScreenController::_registerBindings::__l2::<lambda_f54d55899770a58de2ef552ee06a2a8f>
{
  PatchNoticeScreenController *const __this;
};

```

### `PatchNoticeScreenController::_registerBindings::__l2::<lambda_4d202f178ffac9194b711d9668c2d928>`
```
struct __cppobj PatchNoticeScreenController::_registerBindings::__l2::<lambda_4d202f178ffac9194b711d9668c2d928>
{
};

```

### `PatchNoticeScreenController::_registerEventHandlers::__l2::<lambda_828b56f6f9a309ef3c287b4b3da8f2dd>`
```
struct __cppobj PatchNoticeScreenController::_registerEventHandlers::__l2::<lambda_828b56f6f9a309ef3c287b4b3da8f2dd>
{
  PatchNoticeScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerEventHandlers::__l2::<lambda_f36b53935b8c93d674206fabaecdac2a>`
```
struct __cppobj PatchNotesScreenController::_registerEventHandlers::__l2::<lambda_f36b53935b8c93d674206fabaecdac2a>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_06755f36dae4473cb7a15f3feac38b3b>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_06755f36dae4473cb7a15f3feac38b3b>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_5e92e9c8751a82e449d558c490384f6b>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_5e92e9c8751a82e449d558c490384f6b>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_31acf288a3be7a33dbb85540e6915488>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_31acf288a3be7a33dbb85540e6915488>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_be1d335473d57c8939b502c1ff78e6b6>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_be1d335473d57c8939b502c1ff78e6b6>
{
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_19c38c7e1f993fbde2ff2391200436f6>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_19c38c7e1f993fbde2ff2391200436f6>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_02d82b4e398cbc7a6e703b85cb1f85b9>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_02d82b4e398cbc7a6e703b85cb1f85b9>
{
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_bfd9aa45e678f0947584edcbdd8f527f>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_bfd9aa45e678f0947584edcbdd8f527f>
{
  PatchNotesScreenController *const __this;
};

```

### `PatchNotesScreenController::_registerBindings::__l2::<lambda_7e5f455a5ae88f4cbf4e43f787608fee>`
```
struct __cppobj PatchNotesScreenController::_registerBindings::__l2::<lambda_7e5f455a5ae88f4cbf4e43f787608fee>
{
  PatchNotesScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_06218cdc35f2bdbd8622cc4945fda584>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_06218cdc35f2bdbd8622cc4945fda584>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_3f463c890de16617e456ab3b8cc4a581>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_3f463c890de16617e456ab3b8cc4a581>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_1fd7e7ca27e011de948abd546615e4e7>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_1fd7e7ca27e011de948abd546615e4e7>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_5c24a33841cc439661a9b5946311fa51>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_5c24a33841cc439661a9b5946311fa51>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_64d009cc6f1b16b6a9a90060760b8c87>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_64d009cc6f1b16b6a9a90060760b8c87>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_696043a0fc8f101e7ced49428bdc5302>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_696043a0fc8f101e7ced49428bdc5302>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_0464bc14b9ef31e2d8c2fdc5848aa642>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_0464bc14b9ef31e2d8c2fdc5848aa642>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_b02c86ede247cc19602a633a9d960f93>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_b02c86ede247cc19602a633a9d960f93>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_6d45616cc35894e74eb47dcbe4decdc4>`
```
struct __cppobj PackSettingsScreenController::_registerEventHandlers::__l2::<lambda_6d45616cc35894e74eb47dcbe4decdc4>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::_registerBindings::__l2::<lambda_68e1ed7e113c154466eec7edeb61535f>`
```
struct __cppobj PackSettingsScreenController::_registerBindings::__l2::<lambda_68e1ed7e113c154466eec7edeb61535f>
{
  PackSettingsScreenController *const __this;
};

```

### `PackSettingsScreenController::{ctor}::__l2::<lambda_b9d760795b67cd7e5cdcae356e7bf2c4>`
```
struct __cppobj PackSettingsScreenController::{ctor}::__l2::<lambda_b9d760795b67cd7e5cdcae356e7bf2c4>
{
  PackSettingsScreenController *const __this;
};

```

### `PauseScreenController::_registerSubControllers::__l5::<lambda_2257142b302a3c4f4470225e4671d7d6>`
```
struct __cppobj PauseScreenController::_registerSubControllers::__l5::<lambda_2257142b302a3c4f4470225e4671d7d6>
{
  PauseScreenController *const __this;
};

```

### `PerfTurtleScreenController`
```
struct __cppobj PerfTurtleScreenController : MinecraftScreenController
{
  std::string mCurrentText;
  std::string mNextText;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNextUpdate;
};

```

### `PerfTurtleScreenController_vtbl`
```
struct /*VFT*/ PerfTurtleScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PersonaScreenControllerProxyCallbacks`
```
struct __cppobj PersonaScreenControllerProxyCallbacks
{
  std::function<void __cdecl(UIPropertyBag const &,std::string const &)> mDisplayJsonDefinedControlPopup;
};

```

### `PersonaScreenControllerProxy`
```
struct __cppobj PersonaScreenControllerProxy : ScreenControllerProxy
{
  const PersonaScreenControllerProxyCallbacks mCallbacks;
};

```

### `PersonaScreenControllerProxy_vtbl`
```
struct /*VFT*/ PersonaScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `persona::PersonaColors`
```
struct __cppobj persona::PersonaColors
{
};

```

### `PlayScreenControllerProxyCallbacks`
```
struct __cppobj PlayScreenControllerProxyCallbacks
{
  std::function<void __cdecl(SelectNavigationTabCommand &)> mSelectTab;
  std::function<enum PlayScreenDefaultTab __cdecl(void)> mGetActiveTabIndex;
};

```

### `PlayScreenControllerProxy`
```
struct __cppobj PlayScreenControllerProxy : ScreenControllerProxy
{
  const PlayScreenControllerProxyCallbacks mCallbacks;
};

```

### `PlayScreenControllerProxy_vtbl`
```
struct /*VFT*/ PlayScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `PortfolioScreenController`
```
struct __cppobj __declspec(align(8)) PortfolioScreenController : ClientInstanceScreenController
{
  std::vector<PortfolioScreenController::PhotoRecord> mPhotoRecords;
  int mCurrentPage;
  int mLastPage;
  int mCaptionCount;
};

```

### `PortfolioScreenController_vtbl`
```
struct /*VFT*/ PortfolioScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PostRatingScreenController`
```
struct __cppobj PostRatingScreenController : MainMenuScreenController
{
  bool mRatingDropDownActive;
  const StoreCatalogItem *mStoreItem;
  std::function<void __cdecl(void)> mSubmitRatingCallback;
  int mRating;
  int mInitialRating;
  long double mTimeOpened;
};

```

### `PostRatingScreenController_vtbl`
```
struct /*VFT*/ PostRatingScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PDP::EnumClassHash`
```
struct __cppobj PDP::EnumClassHash
{
};

```

### `ProductDetailScreenController`
```
struct __cppobj ProductDetailScreenController : PurchaseEnabledScreenController
{
  std::vector<std::unique_ptr<PDPSection>> mSections;
  std::unordered_map<enum PDPSectionType,std::string,PDP::EnumClassHash,std::equal_to<enum PDPSectionType>,std::allocator<std::pair<enum PDPSectionType const ,std::string > > > mSectionNames;
  StoreNavigationOrigin mOrigin;
  const StoreCatalogItem *mCatalogItem;
  bool mHasScreenshots;
  Social::UserPicturePath mGamerProfilePicPath;
  bool mDirty;
  bool mLayoutChanged;
  bool mFetchedReviewData;
  bool mShowRecentlyViewed;
  bool mRecentlyViewedClipped;
  bool mRelatedItemsClipped;
  bool mUpdateRelatedItems;
  bool mIsDescriptionExpanded;
  bool mBuyDropdown;
  bool mRealmsIncompatibleButtonHovered;
  int mRating;
  int mInitialRating;
  long double mTimeOpened;
  std::vector<bool> mUserRating;
  bool mWasDescriptionExpanded;
  const bool mAllowSeeMoreBy;
  std::shared_ptr<bool> mExistenceTracker;
  int mResourcePackCount;
  int mWorldTemplateCount;
  std::unique_ptr<OfferCollectionComponent> mRecentlyViewed;
  std::unique_ptr<OfferCollectionComponent> mRelatedItems;
  std::unique_ptr<OfferCollectionComponent> mBundlesContainingOffer;
  Realms::ContentService *mRealmsContentService;
};

```

### `ProductDetailScreenController_vtbl`
```
struct /*VFT*/ ProductDetailScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
  int (__fastcall *_getRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getColIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getLastRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getRemainderOffers)(StoreBaseScreenController *this, const int);
  void (__fastcall *onCatalogStatusUpdated)(PurchaseEnabledScreenController *this);
};

```

### `ProfileScreenController`
```
struct __cppobj __declspec(align(8)) ProfileScreenController : StoreBaseScreenController
{
  persona::PersonaPieceCollectionModel *mPersonaPieceCollectionModel;
  std::shared_ptr<bool> mExistanceTracker;
  bool mManageOptionsActive;
  bool mWaitingForNewPersona;
  std::string mToastMessage;
  persona::ProfileType mInitialProfile;
  bool mFirstLoading;
  std::string mInitialSkinName;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mInitialPersonaLastUpdatedTime;
  std::shared_ptr<PersonaScreenModel> mPersonaScreenModel;
  bool mPlayConfirmAnimation;
};

```

### `ProfileScreenController_vtbl`
```
struct /*VFT*/ ProfileScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
  int (__fastcall *_getRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getColIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getLastRowIndex)(StoreBaseScreenController *this, const int);
  int (__fastcall *_getRemainderOffers)(StoreBaseScreenController *this, const int);
};

```

### `ProgressScreenController`
```
struct __cppobj __declspec(align(4)) ProgressScreenController : MinecraftScreenController
{
  bool mInitiated;
  bool mNext;
  bool mForceRenderBelow;
  float mBackgroundFillAlpha;
  __int64 mLocatingStartTime;
  std::string mCalledFrom;
  std::unique_ptr<ProgressHandler> mProgressHandler;
  std::deque<std::unique_ptr<ProgressHandler>> mProgressHandlerList;
  std::unique_ptr<ContentManagerContext> mContentManagerContext;
  ContentView *mRealmsContentView;
  bool mUseRandomProgressMessage;
  bool mRealmsPlusExpired;
  bool mLoadedRandomProgressMessage;
  std::vector<std::string> mRandomProgressMessageList;
  int mCurrentRandomProgressMessage;
  __int64 mLastRandomProgressMessageUpdate;
  const __int64 mProgressMessageInterval;
  __int64 mLastAudioProgressNotificationUpdate;
  bool mResourcePackPacketReceived;
  std::vector<std::string> mRequiredPackList;
  std::vector<std::string> mOptionalPackList;
  std::vector<bool> mOptionalPackSelected;
  ScopedCPUBoost mCPUBoost;
  bool mHasTicked;
  bool mIsCancellable;
  bool mAllowSmallDownloads;
  bool mPrecachedGameplayScreens;
  bool mDisconnectScreenDisplayed;
};

```

### `ProgressScreenController_vtbl`
```
struct /*VFT*/ ProgressScreenController_vtbl
{
  void (__fastcall *~IScreenController)(IScreenController *this);
  ui::DirtyFlag (__fastcall *tick)(IScreenController *this);
  ui::ViewRequest (__fastcall *handleEvent)(IScreenController *this, ScreenEvent *);
  std::optional<std::string > *(__fastcall *getRoute)(IScreenController *this, std::optional<std::string > *result);
  void (__fastcall *setScreenState)(IScreenController *this, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *onOpen)(ScreenController *this);
  void (__fastcall *onTerminate)(ScreenController *this);
  void (__fastcall *onInit)(ScreenController *this);
  void (__fastcall *onDelete)(ScreenController *this);
  bool (__fastcall *canExit)(ScreenController *this);
  ui::ViewRequest (__fastcall *tryExit)(ScreenController *this);
  bool (__fastcall *areControllerTabsEnabled)(ScreenController *this);
  void (__fastcall *onCreation)(ScreenController *this);
  void (__fastcall *logCreationTime)(ScreenController *this, const std::string *, long double, long double, unsigned __int8);
  void (__fastcall *onLeave)(ScreenController *this);
  void (__fastcall *leaveScreen)(ScreenController *this);
  ui::DirtyFlag (__fastcall *handleGameEventNotification)(ScreenController *this, ui::GameEventNotification);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  bool (__fastcall *bind)(ScreenController *this, const std::string *, unsigned int, int, const std::string *, unsigned int, const std::string *, UIPropertyBag *);
  void (__fastcall *handleLicenseChanged)(ScreenController *this);
  void (__fastcall *onDictationEvent)(ScreenController *this, const std::string *);
  void (__fastcall *setAssociatedBlockPos)(ScreenController *this, const BlockPos *);
  void (__fastcall *setAssociatedEntityUniqueID)(ScreenController *this, const ActorUniqueID);
  void (__fastcall *setSuspendInput)(ScreenController *this, bool);
  float (__fastcall *getCallbackInterval)(ScreenController *this);
  void (__fastcall *onRender)(ScreenController *this);
  void (__fastcall *addStaticScreenVars)(ScreenController *this, Json::Value *);
  std::string *(__fastcall *getAdditionalScreenInfo)(ScreenController *this, std::string *result);
  std::string *(__fastcall *getTelemetryOverride)(ScreenController *this, std::string *result);
  void (__fastcall *addEventProperties)(ScreenController *this, std::unordered_map<std::string,std::string> *);
  ui::SceneType (__fastcall *getSceneType)(ScreenController *this);
  int (__fastcall *getScreenVersion)(ScreenController *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(ScreenController *this);
  ScreenControllerProxy *(__fastcall *getProxy)(ScreenController *this);
  void (__fastcall *onEntered)(ScreenController *this);
  unsigned int (__fastcall *getNameId)(ScreenController *this, const std::string *);
  bool (__fastcall *verifySceneStack)(ScreenController *this, SceneStack *);
  bool (__fastcall *_doesScreenHaveExitBehavior)(ScreenController *this);
  bool (__fastcall *_isStillValid)(MinecraftScreenController *this);
  bool (__fastcall *_getGamepadHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getMixedHelperVisible)(MinecraftScreenController *this);
  bool (__fastcall *_getKeyboardHelperVisible)(MinecraftScreenController *this);
  std::string *(__fastcall *_getButtonADescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonBDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonXDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonYDescription)(MinecraftScreenController *this, std::string *result);
  std::string *(__fastcall *_getButtonKeyboardDescription)(MinecraftScreenController *this, std::string *result);
};

```

### `PurchaseEnabledScreenController::_onNotSignedIn::__l2::<lambda_e7c3b1dd182dda4069c4eb3431f4622f>::()::__l8::<lambda_e9d9a196c9ff705353d867b1f4cb99f7>`
```
struct __cppobj PurchaseEnabledScreenController::_onNotSignedIn::__l2::<lambda_e7c3b1dd182dda4069c4eb3431f4622f>::()::__l8::<lambda_e9d9a196c9ff705353d867b1f4cb99f7>
{
  std::weak_ptr<PurchaseEnabledScreenController> weakThis;
};

```

### `PurchaseEnabledScreenController::_verifyAppStoreReady::__l10::<lambda_19652c0eb9195c6244670c4762c9adea>`
```
struct __cppobj PurchaseEnabledScreenController::_verifyAppStoreReady::__l10::<lambda_19652c0eb9195c6244670c4762c9adea>
{
  std::weak_ptr<PurchaseEnabledScreenController> weakThis;
  std::function<void __cdecl(void)> readyCallback;
};

```

### `PurchaseEnabledScreenController::_fulfillPriorMinecoinPurchase::__l2::<lambda_acf37118c518e07c55eb7cecd4d2bea0>`
```
struct __cppobj PurchaseEnabledScreenController::_fulfillPriorMinecoinPurchase::__l2::<lambda_acf37118c518e07c55eb7cecd4d2bea0>
{
  std::weak_ptr<PurchaseEnabledScreenController> weakThis;
  std::weak_ptr<Purchase> purchase;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l23::<lambda_3ac2c833a4085d766f369b5e2fc01b38>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l23::<lambda_3ac2c833a4085d766f369b5e2fc01b38>
{
  const unsigned __int64 texturePackSize;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l16::<lambda_e5c27e836508193727b377650361f727>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l16::<lambda_e5c27e836508193727b377650361f727>
{
  const unsigned __int64 dataPackSize;
  const unsigned __int64 texturePackSize;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l14::<lambda_a18d9bbcd1e92377040ceaa328b37d3d>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l14::<lambda_a18d9bbcd1e92377040ceaa328b37d3d>
{
  const unsigned __int64 dataPackSize;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l14::<lambda_a6f9377545e9dd95ecc955d5d32f068a>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l14::<lambda_a6f9377545e9dd95ecc955d5d32f068a>
{
  const unsigned __int64 dataPackSize;
  const unsigned __int64 texturePackSize;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l14::<lambda_8062522742fd6951ef39a332b21a1df4>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l14::<lambda_8062522742fd6951ef39a332b21a1df4>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l2::<lambda_b4fddf92bb8978d019fe2c1e4b37e408>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l2::<lambda_b4fddf92bb8978d019fe2c1e4b37e408>
{
};

```

### `ProgressScreenController::_openConfirmationDialog::__l2::<lambda_1af3dcfec7ff21b12d02ed0dc6cc25cf>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l2::<lambda_1af3dcfec7ff21b12d02ed0dc6cc25cf>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l2::<lambda_78f5287b57d3ade535d9e75484617412>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l2::<lambda_78f5287b57d3ade535d9e75484617412>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_openConfirmationDialog::__l2::<lambda_780896ccc21c34df95f6335abce48b56>`
```
struct __cppobj ProgressScreenController::_openConfirmationDialog::__l2::<lambda_780896ccc21c34df95f6335abce48b56>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_6906f8cb5ecd6054ad16fc479db76768>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_6906f8cb5ecd6054ad16fc479db76768>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_425002169a7ad2d19052170b628ca3e2>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_425002169a7ad2d19052170b628ca3e2>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_00719d41afb21b232e3eff220c2cf722>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_00719d41afb21b232e3eff220c2cf722>
{
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_9fe12f6f69bb0a5ea6105b6d102dce01>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_9fe12f6f69bb0a5ea6105b6d102dce01>
{
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_69a04e8ac09c8354dd59b0a9d568eda0>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_69a04e8ac09c8354dd59b0a9d568eda0>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_d87713c07f03500b6b2d13c719496164>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_d87713c07f03500b6b2d13c719496164>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_0a45a0df8e21cf296b5f5b2b10c3c747>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_0a45a0df8e21cf296b5f5b2b10c3c747>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_80d71de63f747b3f02365174e616efe4>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_80d71de63f747b3f02365174e616efe4>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_74253f92313513bd85e4aba38b2d847e>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_74253f92313513bd85e4aba38b2d847e>
{
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_bd7e313587866909c46550db9abde7de>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_bd7e313587866909c46550db9abde7de>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_f636b6a03147383e548893e039f2f0a9>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_f636b6a03147383e548893e039f2f0a9>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerProgressBindings::__l2::<lambda_105f999b37e81b5fab1993a19b50b292>`
```
struct __cppobj ProgressScreenController::_registerProgressBindings::__l2::<lambda_105f999b37e81b5fab1993a19b50b292>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::_registerEventHandlers::__l2::<lambda_560ce387313d116f2c7166671076c5d7>`
```
struct __cppobj ProgressScreenController::_registerEventHandlers::__l2::<lambda_560ce387313d116f2c7166671076c5d7>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::onCreation::__l2::<lambda_f240a8bdbf499207891120b6f019bf85>`
```
struct __cppobj ProgressScreenController::onCreation::__l2::<lambda_f240a8bdbf499207891120b6f019bf85>
{
  ProgressScreenController *const __this;
};

```

### `ProgressScreenController::onCreation::__l2::<lambda_21033af868e346bf57d56f9335c68835>`
```
struct __cppobj ProgressScreenController::onCreation::__l2::<lambda_21033af868e346bf57d56f9335c68835>
{
  std::weak_ptr<ProgressScreenController> weakThis;
};

```

### `ProfileScreenController::_editCharacter::__l5::<lambda_dc96102e9ad312412a9048cc1c0e3f0a>`
```
struct __cppobj ProfileScreenController::_editCharacter::__l5::<lambda_dc96102e9ad312412a9048cc1c0e3f0a>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_55bb42552d8f3ffb1cd089e0fcbe9912>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_55bb42552d8f3ffb1cd089e0fcbe9912>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_80306b7e9c9e550e878d632bd62b98be>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_80306b7e9c9e550e878d632bd62b98be>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_83fdff57d416910e0b1e12da4bc9d2e9>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_83fdff57d416910e0b1e12da4bc9d2e9>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_3e783f87350ec1482b61774637bb6a4a>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_3e783f87350ec1482b61774637bb6a4a>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_8623245c8ff4af3611ae436504cb2083>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_8623245c8ff4af3611ae436504cb2083>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_09b5f4edc7dfca1a68d51170e5abaa91>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_09b5f4edc7dfca1a68d51170e5abaa91>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_7e1eb6828117e6dd728b7693aa309384>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_7e1eb6828117e6dd728b7693aa309384>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_366ac71bc91f1a6eef0f996c74e52f09>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_366ac71bc91f1a6eef0f996c74e52f09>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_f383c536bc70311403cb4f06049a307a>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_f383c536bc70311403cb4f06049a307a>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_39862d95eec4637240bcb1ea4f6090b0>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_39862d95eec4637240bcb1ea4f6090b0>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_e6d5bfd7a8e475567deff072f6dff035>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_e6d5bfd7a8e475567deff072f6dff035>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_0aaaf0bb714eefb04193463935e399da>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_0aaaf0bb714eefb04193463935e399da>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_9a9c10583b52d88003fe1877fac6f548>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_9a9c10583b52d88003fe1877fac6f548>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_0f6fe33083365512cedfc33a29fc27d1>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_0f6fe33083365512cedfc33a29fc27d1>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_1a986c54c23368768d03098952e9d859>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_1a986c54c23368768d03098952e9d859>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_2fbfe2890be196ffafa043da432f41f6>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_2fbfe2890be196ffafa043da432f41f6>
{
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_d22800cba2615d8a2e880374a6aa0531>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_d22800cba2615d8a2e880374a6aa0531>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_af1ba217793978f71e43ce8785f03653>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_af1ba217793978f71e43ce8785f03653>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_registerEventHandlers::__l2::<lambda_3205066b7b91e8f6342c330868576c2c>`
```
struct __cppobj ProfileScreenController::_registerEventHandlers::__l2::<lambda_3205066b7b91e8f6342c330868576c2c>
{
  ProfileScreenController *const __this;
};

```

### `ProfileScreenController::_navigateToProfilePieceListScreen::__l5::<lambda_fce6073ad6c501a2d30ecc186d85d200>`
```
struct __cppobj ProfileScreenController::_navigateToProfilePieceListScreen::__l5::<lambda_fce6073ad6c501a2d30ecc186d85d200>
{
  ProfileScreenController *const __this;
  const persona::PieceOfferWrapper *pieceOffer;
};

```

### `ProfileScreenController::_createNewPersona::__l2::<lambda_90c7f2834cef6b116927e26c049382b2>`
```
struct __cppobj ProfileScreenController::_createNewPersona::__l2::<lambda_90c7f2834cef6b116927e26c049382b2>
{
  std::weak_ptr<bool> weakExistance;
  ProfileScreenController *const __this;
  std::function<void __cdecl(void)> onPersonaCreateCallback;
};

```

### `ProfileScreenController::{ctor}::__l2::<lambda_dee70dc5f8b4f5c2ab494caa8465613f>`
```
struct __cppobj ProfileScreenController::{ctor}::__l2::<lambda_dee70dc5f8b4f5c2ab494caa8465613f>
{
  std::weak_ptr<bool> weakExistance;
  ProfileScreenController *const __this;
};

```

### `ProductDetailScreenController::_fetchGamerPic::__l2::<lambda_8ff7580f219b5825ea142a7d31deef12>`
```
struct __cppobj ProductDetailScreenController::_fetchGamerPic::__l2::<lambda_8ff7580f219b5825ea142a7d31deef12>
{
  std::weak_ptr<ProductDetailScreenController> weakThis;
};

```

### `ProductDetailScreenController::_handleApplyToRealmClick::__l2::<lambda_62614eccfdad4c869a4868024624fde4>::()::__l5::<lambda_dcbbea16852e7aa860a18dee2d977eea>`
```
struct __cppobj ProductDetailScreenController::_handleApplyToRealmClick::__l2::<lambda_62614eccfdad4c869a4868024624fde4>::()::__l5::<lambda_dcbbea16852e7aa860a18dee2d977eea>
{
  std::weak_ptr<ProductDetailScreenController> weakThis;
  Realms::World world;
};

```

### `ProductDetailScreenController::_handleApplyToRealmClick::__l2::<lambda_62614eccfdad4c869a4868024624fde4>::()::__l5::<lambda_dcbbea16852e7aa860a18dee2d977eea>::()::__l8::<lambda_3c42120adbf169e1ca16dba2bcdccfeb>`
```
struct __cppobj ProductDetailScreenController::_handleApplyToRealmClick::__l2::<lambda_62614eccfdad4c869a4868024624fde4>::()::__l5::<lambda_dcbbea16852e7aa860a18dee2d977eea>::()::__l8::<lambda_3c42120adbf169e1ca16dba2bcdccfeb>
{
  std::weak_ptr<ProductDetailScreenController> weakThis;
  ModalScreenButtonId modalResult;
  Realms::World world;
};

```

### `PortfolioScreenController::_handlePortfolioExport::__l9::<lambda_8b3d0eb72e9722ddbd41669035466131>`
```
struct __cppobj PortfolioScreenController::_handlePortfolioExport::__l9::<lambda_8b3d0eb72e9722ddbd41669035466131>
{
  unsigned __int64 photoCount;
  int captionCount;
  std::weak_ptr<ClientInstanceScreenModel> weakModel;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_6ba530dd0d3c4e62ef6508496d516a92>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_6ba530dd0d3c4e62ef6508496d516a92>
{
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_8db6f9601dfa315f1520d202a143335a>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_8db6f9601dfa315f1520d202a143335a>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_c9246a712665e6f9e346519297aa2650>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_c9246a712665e6f9e346519297aa2650>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_a656977b25eb728384c81db34aee3b50>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_a656977b25eb728384c81db34aee3b50>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_0e659c83ebb06f4394b76d37ca060bee>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_0e659c83ebb06f4394b76d37ca060bee>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_af340e9bb685cdf40e974eca56b9670f>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_af340e9bb685cdf40e974eca56b9670f>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_0454c3a2b410ae481bac6cedd684dc15>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_0454c3a2b410ae481bac6cedd684dc15>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_94983daa80de815e9385a211da1cf22f>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_94983daa80de815e9385a211da1cf22f>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_836e72cd62a403ff0a11cd83b2342ca7>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_836e72cd62a403ff0a11cd83b2342ca7>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_ea2d68082adeabb6edfdfde70cf31672>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_ea2d68082adeabb6edfdfde70cf31672>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerBindings::__l2::<lambda_06a9d163f0c54045cfd015b969d853d7>`
```
struct __cppobj PortfolioScreenController::_registerBindings::__l2::<lambda_06a9d163f0c54045cfd015b969d853d7>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_524c036b1931dd38d182e6171056532f>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_524c036b1931dd38d182e6171056532f>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_052f208ee3af0874783e3c88154d9fd1>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_052f208ee3af0874783e3c88154d9fd1>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_a015db2ebed5594b7d9283d72a2a1b11>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_a015db2ebed5594b7d9283d72a2a1b11>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_0b9263f767f05dbc3a0b89e52d1f0225>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_0b9263f767f05dbc3a0b89e52d1f0225>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_8e291fbdb1b824c1bb8021fb2327513d>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_8e291fbdb1b824c1bb8021fb2327513d>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_4ba9117a879d119f3d7105a52fda0e1c>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_4ba9117a879d119f3d7105a52fda0e1c>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_50ba87151f9f04a7ef809e82b25a0623>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_50ba87151f9f04a7ef809e82b25a0623>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_5461caee329821194ed257f49341518e>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_5461caee329821194ed257f49341518e>
{
  PortfolioScreenController *const __this;
};

```

### `PortfolioScreenController::_registerEventHandlers::__l2::<lambda_5461caee329821194ed257f49341518e>::()::__l2::<lambda_fb207da5f82df5a1a9a24796bd611e5b>`
```
struct __cppobj PortfolioScreenController::_registerEventHandlers::__l2::<lambda_5461caee329821194ed257f49341518e>::()::__l2::<lambda_fb207da5f82df5a1a9a24796bd611e5b>
{
  PortfolioScreenController *const __this;
};

```

### `PlayScreenController::_displayImportRetailWorldModal::__l2::<lambda_0919622d08ccb9f63aaf667f38e80b33>`
```
struct __cppobj PlayScreenController::_displayImportRetailWorldModal::__l2::<lambda_0919622d08ccb9f63aaf667f38e80b33>
{
  std::weak_ptr<PlayScreenController> weakThis;
  unsigned __int64 worldSize;
  std::function<void __cdecl(enum ModalScreenButtonId)> callback;
};

```

### `PlayScreenController::_displayImportRetailWorldModal::__l2::<lambda_0919622d08ccb9f63aaf667f38e80b33>::()::__l5::<lambda_20af2f3d072dbaa538412f29dcab17f8>`
```
struct __cppobj PlayScreenController::_displayImportRetailWorldModal::__l2::<lambda_0919622d08ccb9f63aaf667f38e80b33>::()::__l5::<lambda_20af2f3d072dbaa538412f29dcab17f8>
{
  bool *bIsLowDiskSpaceWarning;
  unsigned __int64 worldSize;
};

```

### `PlayScreenController::_isRealmExpiringForPlatform::__l10::<lambda_88ac48851502a7345398d4b8513621b1>`
```
struct __cppobj PlayScreenController::_isRealmExpiringForPlatform::__l10::<lambda_88ac48851502a7345398d4b8513621b1>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_onWorldConversionCompleted::__l2::<lambda_811b7a987c7c8d68d8053c7372993a82>::()::__l5::<lambda_58a8237bddcd4c72d83a464e56ff4423>`
```
struct __cppobj PlayScreenController::_onWorldConversionCompleted::__l2::<lambda_811b7a987c7c8d68d8053c7372993a82>::()::__l5::<lambda_58a8237bddcd4c72d83a464e56ff4423>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_getConvertStateCallback::__l2::<lambda_d7ef6ddca12767f1aa41a1432ed49edd>`
```
struct __cppobj PlayScreenController::_getConvertStateCallback::__l2::<lambda_d7ef6ddca12767f1aa41a1432ed49edd>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_getConvertProgressHandlerCallback::__l2::<lambda_3742aa0d726b92438a085ae7186b1563>`
```
struct __cppobj PlayScreenController::_getConvertProgressHandlerCallback::__l2::<lambda_3742aa0d726b92438a085ae7186b1563>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fe4b5f3b85a87050a93a1b2db95691a8>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fe4b5f3b85a87050a93a1b2db95691a8>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_40ac74a34f363819b33b9cf0a625151f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_40ac74a34f363819b33b9cf0a625151f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_357c5fb07605395b60c4f71b5c9efb4e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_357c5fb07605395b60c4f71b5c9efb4e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f949c67d6d17446d596c88482af61c4f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f949c67d6d17446d596c88482af61c4f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_1e4021deafc03579cee0576dc1e4c76d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_1e4021deafc03579cee0576dc1e4c76d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_84d6e1cd520e1f10a2e6f8e331496123>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_84d6e1cd520e1f10a2e6f8e331496123>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_20fb5280bb543a6bb7d7bde19a088cda>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_20fb5280bb543a6bb7d7bde19a088cda>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fbb55fd66cd77933699ce086e4c5a11c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fbb55fd66cd77933699ce086e4c5a11c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e8dc474767beaeda08184b28df89adc9>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e8dc474767beaeda08184b28df89adc9>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_600817b49fff217dd6152e14b53960da>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_600817b49fff217dd6152e14b53960da>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8ec3a818949dd3381192ab6a3fef83a3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8ec3a818949dd3381192ab6a3fef83a3>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e322a4a351b20b7e92b92780e91e6c7b>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e322a4a351b20b7e92b92780e91e6c7b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8da24a33a245351500180266ebcfc631>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8da24a33a245351500180266ebcfc631>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d188bbc33db094bad06a690fd91b8365>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d188bbc33db094bad06a690fd91b8365>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c3eccc349cf4cb13a6c2fa2d2b811962>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c3eccc349cf4cb13a6c2fa2d2b811962>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_bbccf21c75b408d5051b785e45ad71d6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_bbccf21c75b408d5051b785e45ad71d6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_924031f9bce4c8745ce7265d8c185e8f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_924031f9bce4c8745ce7265d8c185e8f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_866e28c73c69df7e8c28b9b50e8084f0>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_866e28c73c69df7e8c28b9b50e8084f0>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_109e0e9edd1214ae806586cae8cfb309>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_109e0e9edd1214ae806586cae8cfb309>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2c5e1f90ae8bbc80f45a499ab42c8bea>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2c5e1f90ae8bbc80f45a499ab42c8bea>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_619880eb25f0db9f1aea395213c8e1a0>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_619880eb25f0db9f1aea395213c8e1a0>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2dce02b09b23142429d8d56d9f5528c6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2dce02b09b23142429d8d56d9f5528c6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_bb8a96234bc50af1c0421a55aa4d0e4d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_bb8a96234bc50af1c0421a55aa4d0e4d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_bf27b07cdd27131756c212415165fe96>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_bf27b07cdd27131756c212415165fe96>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b82b61bcf880903d34ab2cb7a4c1ee20>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b82b61bcf880903d34ab2cb7a4c1ee20>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d62600219d737181db012fbab249692c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d62600219d737181db012fbab249692c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_184e7c5d85c7859308f5c8d595495595>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_184e7c5d85c7859308f5c8d595495595>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_58bf55eee9162aa62b142774c0811177>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_58bf55eee9162aa62b142774c0811177>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_aae93bf881c8ec218ecaa62b9967f4ed>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_aae93bf881c8ec218ecaa62b9967f4ed>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_968616fd95eb18240b6892993c345b5b>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_968616fd95eb18240b6892993c345b5b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_af30226fef8f642809d2944d47501d7e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_af30226fef8f642809d2944d47501d7e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_dd9a0bd8476dc25053671fdcf50c3cc6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_dd9a0bd8476dc25053671fdcf50c3cc6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_82a5c6594f603d3a66bed5b4b901decd>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_82a5c6594f603d3a66bed5b4b901decd>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8992bc3912377db307c8ac7841ecff19>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8992bc3912377db307c8ac7841ecff19>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_0347b0da6e12c1fc75a8c38380c9aa37>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_0347b0da6e12c1fc75a8c38380c9aa37>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8646fbc76db9b2d398b9c1db642625df>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8646fbc76db9b2d398b9c1db642625df>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8945c5ecd4fa53e9889c8c0597704a41>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8945c5ecd4fa53e9889c8c0597704a41>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c33a3cfef61b0fb84c9f0a4a4c8205f8>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c33a3cfef61b0fb84c9f0a4a4c8205f8>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e36845e363c5d04aca1e440374f4e5fd>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e36845e363c5d04aca1e440374f4e5fd>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d1dc9d038d2d2e5af15522ca0467fe8f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d1dc9d038d2d2e5af15522ca0467fe8f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4c8dbbced5cbd7618745306da8926946>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4c8dbbced5cbd7618745306da8926946>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_869eeb445dff46a957467623ac290ee6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_869eeb445dff46a957467623ac290ee6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9024aeed45fbf0476baf3a5618bd3fb8>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9024aeed45fbf0476baf3a5618bd3fb8>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_22ded813d5f711fe85724750a4fe14a2>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_22ded813d5f711fe85724750a4fe14a2>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_209d875ce2766eb6d90a8e798e1687c0>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_209d875ce2766eb6d90a8e798e1687c0>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b7a8310893dc1694c437b2b19b7ced38>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b7a8310893dc1694c437b2b19b7ced38>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7e66aa214997bb675840e080dd62bd56>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7e66aa214997bb675840e080dd62bd56>
{
  PlayScreenController *const __this;
  const char *const thirdParty;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d40d8a90c36ef1b537684706b175e2e3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d40d8a90c36ef1b537684706b175e2e3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_5f56c0ea062cccbf002a92a286e4d2cd>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_5f56c0ea062cccbf002a92a286e4d2cd>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_94493d6ade8d93cdc8929b1fe742e92d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_94493d6ade8d93cdc8929b1fe742e92d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_bebc3d6343e01705eec4ad025dccb7b0>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_bebc3d6343e01705eec4ad025dccb7b0>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2bb2650520bba7fe5cb232d7f82974fd>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2bb2650520bba7fe5cb232d7f82974fd>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fb81f9524892a0116d44fa65a7c77cda>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fb81f9524892a0116d44fa65a7c77cda>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_5735634f453cd52dfad61421f06a03dc>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_5735634f453cd52dfad61421f06a03dc>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_3f25d1128666b0eafded34bc7999ae23>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_3f25d1128666b0eafded34bc7999ae23>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c2a63cdee00ae0a02fa809dc9e66dc06>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c2a63cdee00ae0a02fa809dc9e66dc06>
{
  PlayScreenController *const __this;
  const char *const thirdParty;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_a50551e3567c23d31428685958a568e3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_a50551e3567c23d31428685958a568e3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_3008e51487e4e5c81e41cc337099ee2d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_3008e51487e4e5c81e41cc337099ee2d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f0ef474cc4e6756eceee9e9f136cf49c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f0ef474cc4e6756eceee9e9f136cf49c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fe820080e6ff1f90b2b807799cc28c3c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fe820080e6ff1f90b2b807799cc28c3c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b5803cf42a917c4088fdf42ff367459f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b5803cf42a917c4088fdf42ff367459f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_94a5148d51fafe0161635d27f3650952>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_94a5148d51fafe0161635d27f3650952>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_230d50a73475532cea04085220fe939e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_230d50a73475532cea04085220fe939e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9c6d3aab488e3247df70dfdacaa1d842>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9c6d3aab488e3247df70dfdacaa1d842>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_189890409e3d4ed66ba2738d3efd178c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_189890409e3d4ed66ba2738d3efd178c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_66628e507905495789e4422a93854911>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_66628e507905495789e4422a93854911>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_732ec99fad775b065cba9f22943b902d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_732ec99fad775b065cba9f22943b902d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e20726d828cdf9f018854d3889170a44>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e20726d828cdf9f018854d3889170a44>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_1cd24bc6370e3bf217674ed0ad75deba>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_1cd24bc6370e3bf217674ed0ad75deba>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_17b55ac73527de30287f36c09fc4d604>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_17b55ac73527de30287f36c09fc4d604>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_6468ef81abfeae2130ecdff35839a3c7>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_6468ef81abfeae2130ecdff35839a3c7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_5611d0e7c992196477c51e5a07c86a5e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_5611d0e7c992196477c51e5a07c86a5e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d3ce5c4bc73fc0afa28fcc7dbd7f40a5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d3ce5c4bc73fc0afa28fcc7dbd7f40a5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8f0c439305c819490c727384ec132fee>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8f0c439305c819490c727384ec132fee>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_96f424962d3fd2a022608ed5eaee4061>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_96f424962d3fd2a022608ed5eaee4061>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_191fab318f09a52b7467d373eec8dc8c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_191fab318f09a52b7467d373eec8dc8c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9060ff371287027a3e89a18d60d91d06>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9060ff371287027a3e89a18d60d91d06>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_16c646ef419beabcd4bd8be3c028c137>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_16c646ef419beabcd4bd8be3c028c137>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_de584659bde12e923cb033dd179a896c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_de584659bde12e923cb033dd179a896c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d54ec6c7fe78567f81f6eda9bbc850c1>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d54ec6c7fe78567f81f6eda9bbc850c1>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9a5f8c812ce79aed6e3da276cfb947b4>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9a5f8c812ce79aed6e3da276cfb947b4>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4c647da354784062adb6b366fab913b6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4c647da354784062adb6b366fab913b6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_500c54395c134ece892db2d4641ceb14>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_500c54395c134ece892db2d4641ceb14>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_ae2791db9204882b09b1bd6fdc4ec2a5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_ae2791db9204882b09b1bd6fdc4ec2a5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_6efa9476b8cf00bb7bb1c3e185665269>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_6efa9476b8cf00bb7bb1c3e185665269>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_64bcb979092aa7860cdb39b2b46783b4>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_64bcb979092aa7860cdb39b2b46783b4>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_3a7b7f647f199329e42bbd322387e842>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_3a7b7f647f199329e42bbd322387e842>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9a7e58f2509f007e01ea90eb62b41776>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9a7e58f2509f007e01ea90eb62b41776>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_739486f0b8ee67dd3b4d0cafffd2f8b9>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_739486f0b8ee67dd3b4d0cafffd2f8b9>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f93e9601a38cf73f2e83e19809069323>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f93e9601a38cf73f2e83e19809069323>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_1e293ea21a5904d033831419b09b04e1>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_1e293ea21a5904d033831419b09b04e1>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9b465f8bfcde8d303ed726cc226efd32>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9b465f8bfcde8d303ed726cc226efd32>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9ec391a6d9f581e93cf59e19fe16d15b>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9ec391a6d9f581e93cf59e19fe16d15b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7061639af95a6b4338cb06fe31d65655>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7061639af95a6b4338cb06fe31d65655>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_971b8ed2c59bf66fb956c99cdfbbea40>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_971b8ed2c59bf66fb956c99cdfbbea40>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_1faa8b1a4ee1c87b29789c1501c414bc>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_1faa8b1a4ee1c87b29789c1501c414bc>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8a51e4ca3d238fccc82d77d41a4a1474>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8a51e4ca3d238fccc82d77d41a4a1474>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_638f66a80891763b7dfb7dc6525ed4f5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_638f66a80891763b7dfb7dc6525ed4f5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7c1f3cdc38e291bd8c2275edce1c185c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7c1f3cdc38e291bd8c2275edce1c185c>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_11df31fd6d939591feaf8048f4a46b33>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_11df31fd6d939591feaf8048f4a46b33>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d73897ae993508ec508ae70916c35b26>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d73897ae993508ec508ae70916c35b26>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_18309a19f133bab25a86ec261a824d2a>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_18309a19f133bab25a86ec261a824d2a>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8a65840076d78d809e7cdeb156ab4a0a>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8a65840076d78d809e7cdeb156ab4a0a>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_3408bfe7f10651714938e6a33a11cc9d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_3408bfe7f10651714938e6a33a11cc9d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_5f54ee2832127c943273e08ec9fde039>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_5f54ee2832127c943273e08ec9fde039>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_164f1ad76b0d37022c1be4fabbe8ee24>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_164f1ad76b0d37022c1be4fabbe8ee24>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_a640d5a3c819498deee0a04d8e775743>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_a640d5a3c819498deee0a04d8e775743>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2a51143ed1a6076fb56481f3359a6eb1>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2a51143ed1a6076fb56481f3359a6eb1>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b16e83f79486502561dfe23479ec8635>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b16e83f79486502561dfe23479ec8635>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_06a35d1969f8e4d1153d6da2378824c9>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_06a35d1969f8e4d1153d6da2378824c9>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_ea599af26bb19824ecd002236c0742ea>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_ea599af26bb19824ecd002236c0742ea>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4aaa48e666906e689ab0f6cd823dc74f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4aaa48e666906e689ab0f6cd823dc74f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_13080d6d185c585e4007d8a45cd2dc59>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_13080d6d185c585e4007d8a45cd2dc59>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_15d60963e87badc9e14af3a56c333eab>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_15d60963e87badc9e14af3a56c333eab>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_54b75588a9444c93dbc061eda2aeefc4>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_54b75588a9444c93dbc061eda2aeefc4>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2e904b4943593f5430746c29a69d4281>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2e904b4943593f5430746c29a69d4281>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d49c4371ae471c6395cf27dd0511ceda>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d49c4371ae471c6395cf27dd0511ceda>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_ff0fdea31705855a39f87f0242a8108e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_ff0fdea31705855a39f87f0242a8108e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c1be30e1a253082faf19c8180ced3459>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c1be30e1a253082faf19c8180ced3459>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_492ba79fe1f4ba9668af85bbb86a09a3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_492ba79fe1f4ba9668af85bbb86a09a3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fdcb6adf71eb298408f4b70fd245524f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fdcb6adf71eb298408f4b70fd245524f>
{
  PlayScreenController::_registerBindings::__l2::<lambda_85a8ad764f0e7933a7cfd34d077466ab> getNetworkWorldGamerPicFileSystem;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_cad8065384005bb98ed78eea43fb25a6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_cad8065384005bb98ed78eea43fb25a6>
{
  PlayScreenController::_registerBindings::__l2::<lambda_85a8ad764f0e7933a7cfd34d077466ab> getNetworkWorldGamerPicFileSystem;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_43fdd97d62c89da5d4e7f926d7182db3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_43fdd97d62c89da5d4e7f926d7182db3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f9656b5d280b7cb9ac61547571112941>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f9656b5d280b7cb9ac61547571112941>
{
  PlayScreenController::_registerBindings::__l2::<lambda_43fdd97d62c89da5d4e7f926d7182db3> getNetworkWorldGamerPicPath;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9b9fb9160bd57154977cd91e9c123d66>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9b9fb9160bd57154977cd91e9c123d66>
{
  PlayScreenController::_registerBindings::__l2::<lambda_43fdd97d62c89da5d4e7f926d7182db3> getNetworkWorldGamerPicPath;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4d55e6c28ef41eb1f9147afc19a4111f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4d55e6c28ef41eb1f9147afc19a4111f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_bc4f1a79f7e87a7babdeb3b0dc3c242e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_bc4f1a79f7e87a7babdeb3b0dc3c242e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_304ab655dcd9b4dfc88fd2ccd88ba0bd>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_304ab655dcd9b4dfc88fd2ccd88ba0bd>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4e79b83c75c1deedfd924eee75e14999>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4e79b83c75c1deedfd924eee75e14999>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d13dd7516999144320925828a5abe28c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d13dd7516999144320925828a5abe28c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_6b86bca16dc3eb21e89e63c353130f7a>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_6b86bca16dc3eb21e89e63c353130f7a>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_ddba0fccce7df45ce6b0ae7599aad5f7>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_ddba0fccce7df45ce6b0ae7599aad5f7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e92da742b5d5452891279c94d2491ac5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e92da742b5d5452891279c94d2491ac5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b32a7c8823cd53ca7af64c36254c33f9>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b32a7c8823cd53ca7af64c36254c33f9>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_192456246d31c06d4199f0a1b6fcc338>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_192456246d31c06d4199f0a1b6fcc338>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_88ae1469106dfb64786234f1622ecd42>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_88ae1469106dfb64786234f1622ecd42>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d4dbd3823274f546695be6efe8d5b505>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d4dbd3823274f546695be6efe8d5b505>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2c64a7d009b682979bd601cd92963b5c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2c64a7d009b682979bd601cd92963b5c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_efe4825c98a77edc1f4b4dbea9315327>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_efe4825c98a77edc1f4b4dbea9315327>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9102e600b536ede9eb140cc21454af29>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9102e600b536ede9eb140cc21454af29>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_70f7d1a565cf9e2885125f6d999cd13b>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_70f7d1a565cf9e2885125f6d999cd13b>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_edef7a3159f3fe7ac7779ac571cdd58c>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_edef7a3159f3fe7ac7779ac571cdd58c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7bb736134be19d117eb45da4fff4f3d3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7bb736134be19d117eb45da4fff4f3d3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_83bb986c26a2f96a817a223a0d940d9f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_83bb986c26a2f96a817a223a0d940d9f>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d5e228d7c81647f40411b8987ec4017b>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d5e228d7c81647f40411b8987ec4017b>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_58fb6b434d26c1c65bbe1b1afecec58a>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_58fb6b434d26c1c65bbe1b1afecec58a>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_5649553a8b9bfcd9e38d381e22728670>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_5649553a8b9bfcd9e38d381e22728670>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_6bee39f82445be2e552c73bf3fe017ae>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_6bee39f82445be2e552c73bf3fe017ae>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_9cb6003d815f8869badda6d7639032dc>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_9cb6003d815f8869badda6d7639032dc>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_009d95eecbef5167accafb2e4dac37bf>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_009d95eecbef5167accafb2e4dac37bf>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_21185986cbf1fbeb167d61e674d29811>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_21185986cbf1fbeb167d61e674d29811>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_10d8003527959c593edb084e5fc10846>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_10d8003527959c593edb084e5fc10846>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c99c28e69655415d33ba0b1a9086a818>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c99c28e69655415d33ba0b1a9086a818>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f82cfcec5dd7a6c2f8a2a22c1e33de39>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f82cfcec5dd7a6c2f8a2a22c1e33de39>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_80df1e0cf14733100e803a7aec1dcfb7>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_80df1e0cf14733100e803a7aec1dcfb7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_95938211bfee329bfa57ed9d65887e05>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_95938211bfee329bfa57ed9d65887e05>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8ab562823e7caf61211cbb6a12cb92ff>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8ab562823e7caf61211cbb6a12cb92ff>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_15c0ad880a64f2743cb8643b13eef4e1>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_15c0ad880a64f2743cb8643b13eef4e1>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_502ff12360d54fc1d8d7a222df3235b9>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_502ff12360d54fc1d8d7a222df3235b9>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_3f5ae8094fc8532929bbdcdfdebd6359>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_3f5ae8094fc8532929bbdcdfdebd6359>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_463669e37e1517ffc79b3030d732e854>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_463669e37e1517ffc79b3030d732e854>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_130350d4c267189164ccf310cc49daa5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_130350d4c267189164ccf310cc49daa5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_17b7f06d52c0a4da4f06dc7de07f361f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_17b7f06d52c0a4da4f06dc7de07f361f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8b73d732850b72b29256b04632a23839>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8b73d732850b72b29256b04632a23839>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_c755b388e3bc6fbe92f48c982f356eae>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_c755b388e3bc6fbe92f48c982f356eae>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_fa417a6268bffda9c714aa2b92d36875>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_fa417a6268bffda9c714aa2b92d36875>
{
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7299ca456569ca89878b8d994a48ae08>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7299ca456569ca89878b8d994a48ae08>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l5::<lambda_24e37a25881529092a0a6981c741c34d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l5::<lambda_24e37a25881529092a0a6981c741c34d>
{
  PlayScreenController *const __this;
  unsigned __int64 totalStorageSize;
};

```

### `PlayScreenController::_registerBindings::__l5::<lambda_f43f8635b720b7a11607e50bcbec5218>`
```
struct __cppobj PlayScreenController::_registerBindings::__l5::<lambda_f43f8635b720b7a11607e50bcbec5218>
{
  PlayScreenController *const __this;
  unsigned __int64 totalStorageSize;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e8db3b10a11e83d7ebdd8f639b3fa127>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e8db3b10a11e83d7ebdd8f639b3fa127>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_0b749821dbbc484d36b112e8da50116a>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_0b749821dbbc484d36b112e8da50116a>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_43859a7fab7c6e9d30e84f319a7b28b3>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_43859a7fab7c6e9d30e84f319a7b28b3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4322ab5e69408397b2e29b208581f518>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4322ab5e69408397b2e29b208581f518>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_89b9112fbb9b0cf330222f12aeefb6c5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_89b9112fbb9b0cf330222f12aeefb6c5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_b91026f68c1d69e4e773636329897c6d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_b91026f68c1d69e4e773636329897c6d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_d409b6d4eb6cb6b72f1c3be5bd91af78>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_d409b6d4eb6cb6b72f1c3be5bd91af78>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_e5e1fbb4f1a47bac59b91dd4a91021f1>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_e5e1fbb4f1a47bac59b91dd4a91021f1>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_4b4754c02d8c9b4b7fe23eab4545d05d>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_4b4754c02d8c9b4b7fe23eab4545d05d>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_52db1c23a876b2cb6378e420ed896db6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_52db1c23a876b2cb6378e420ed896db6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8d99fbfb8e663b0da98ba23c9f8dc9f5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8d99fbfb8e663b0da98ba23c9f8dc9f5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8fb3472234d2520647589e0064998ec5>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8fb3472234d2520647589e0064998ec5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_50860c2228c93ad7e0400e4ae834a55f>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_50860c2228c93ad7e0400e4ae834a55f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_f5c6b2756334d6ccccee1aacacc7635e>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_f5c6b2756334d6ccccee1aacacc7635e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_999402b621aa1e83363e716fbcbb97d4>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_999402b621aa1e83363e716fbcbb97d4>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_486c97e387e8aa8a3bdb679e17176950>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_486c97e387e8aa8a3bdb679e17176950>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_27c9d5a0e2414a82a4a8732d1c312eb7>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_27c9d5a0e2414a82a4a8732d1c312eb7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_8cc29ccea9ec65748d3398cf45bd06e8>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_8cc29ccea9ec65748d3398cf45bd06e8>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_6d7104aecbff518bdae3cbc363c2a2f8>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_6d7104aecbff518bdae3cbc363c2a2f8>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_1c16eaf1d3efa5105e7c0adbd81b7c26>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_1c16eaf1d3efa5105e7c0adbd81b7c26>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_7ab18f8590a21981ba3da3c71facfd54>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_7ab18f8590a21981ba3da3c71facfd54>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_2133a56ae57fbb30cece840df2ecaec6>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_2133a56ae57fbb30cece840df2ecaec6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_eb06b4c00a952afcfc817cbc01bf7c43>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_eb06b4c00a952afcfc817cbc01bf7c43>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerBindings::__l2::<lambda_12393306fd84ed370cef0cdbad2ff8b7>`
```
struct __cppobj PlayScreenController::_registerBindings::__l2::<lambda_12393306fd84ed370cef0cdbad2ff8b7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_7b9efc174862f13ea9611b224958e3b6>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_7b9efc174862f13ea9611b224958e3b6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_8e7d22f27533a9cfea27f6dc592030d2>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_8e7d22f27533a9cfea27f6dc592030d2>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l15::<lambda_90e99c56189d98eec5515743c6e31e6d>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l15::<lambda_90e99c56189d98eec5515743c6e31e6d>
{
  std::function<void __cdecl(int)> setValue;
  std::pair<std::string const ,int> nameValuePair;
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l15::<lambda_3709dd803c2a86885cea3f66ae064ee6>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l15::<lambda_3709dd803c2a86885cea3f66ae064ee6>
{
  std::function<int __cdecl(void)> getValue;
  std::pair<std::string const ,int> nameValuePair;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_376a4fc70175734b632435841d492b78>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_376a4fc70175734b632435841d492b78>
{
  std::unordered_map<int,std::string> valueLabelPairs;
  std::function<int __cdecl(void)> getValue;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b5dabc3d879e3039854319a6f67fc59c>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b5dabc3d879e3039854319a6f67fc59c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_ad9954f9b1742307ed2849c65be3855b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_ad9954f9b1742307ed2849c65be3855b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_48facb672868b5b78f42e343010440e6>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_48facb672868b5b78f42e343010440e6>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_f27a311b17df92daab1c57437bfd5c6a>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_f27a311b17df92daab1c57437bfd5c6a>
{
  std::function<bool __cdecl(void)> isEnabled;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_a1c020377ca7f634bfddf4f8c16ecf25>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_a1c020377ca7f634bfddf4f8c16ecf25>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_a729e52000527d24b84264ec9e5e9f37>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_a729e52000527d24b84264ec9e5e9f37>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_04ad8305788979f30ad569cdd7a3197b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_04ad8305788979f30ad569cdd7a3197b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4ad5d9f684c5b88c08a385550cb70b2>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4ad5d9f684c5b88c08a385550cb70b2>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_5baca981e78a5278fbc97b542dafd392>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_5baca981e78a5278fbc97b542dafd392>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_5baca981e78a5278fbc97b542dafd392>::()::__l2::<lambda_b8e49ea5392977c4ade7d8c9b2c96626>`
```
struct __cppobj __declspec(align(8)) PlayScreenController::_registerEventHandlers::__l2::<lambda_5baca981e78a5278fbc97b542dafd392>::()::__l2::<lambda_b8e49ea5392977c4ade7d8c9b2c96626>
{
  std::weak_ptr<PlayScreenController> weakThis;
  int index;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_ff2c1ac7f06e1573fa2a5770310ffa6b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_ff2c1ac7f06e1573fa2a5770310ffa6b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_27d5c1e69f6da31a185f36056c60ad93>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_27d5c1e69f6da31a185f36056c60ad93>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_4a1073ffc54e121d9b392207d2714bbe>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_4a1073ffc54e121d9b392207d2714bbe>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_40ccf56db74661a0f172c14dfac4ff6b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_40ccf56db74661a0f172c14dfac4ff6b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_f6f712184d4794a47040ea45c93969e3>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_f6f712184d4794a47040ea45c93969e3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_3538155d77d5cf1dc5b526d8802290fb>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_3538155d77d5cf1dc5b526d8802290fb>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b54835e6397ce5da5566225bcb801fef>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b54835e6397ce5da5566225bcb801fef>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b54835e6397ce5da5566225bcb801fef>::()::__l2::<lambda_65fd24a904f543e58c8e21c86f9717f0>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b54835e6397ce5da5566225bcb801fef>::()::__l2::<lambda_65fd24a904f543e58c8e21c86f9717f0>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_registerEventHandlers::__l11::<lambda_82e79dd95a512eea246357b45d431295>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l11::<lambda_82e79dd95a512eea246357b45d431295>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l11::<lambda_82e79dd95a512eea246357b45d431295>::()::__l2::<lambda_c9836bc1418862e7429b4b39ed95c90b>`
```
struct __cppobj __declspec(align(8)) PlayScreenController::_registerEventHandlers::__l11::<lambda_82e79dd95a512eea246357b45d431295>::()::__l2::<lambda_c9836bc1418862e7429b4b39ed95c90b>
{
  std::weak_ptr<PlayScreenController> weakThis;
  const int index;
};

```

### `PlayScreenController::_registerEventHandlers::__l11::<lambda_cdf9cba58f0f31c5998cbdf02d780624>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l11::<lambda_cdf9cba58f0f31c5998cbdf02d780624>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l11::<lambda_cdf9cba58f0f31c5998cbdf02d780624>::()::__l2::<lambda_5bddc6ca37a8f9dc40c7d65e14817c1e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l11::<lambda_cdf9cba58f0f31c5998cbdf02d780624>::()::__l2::<lambda_5bddc6ca37a8f9dc40c7d65e14817c1e>
{
  std::weak_ptr<PlayScreenController> weakThis;
  std::string worldId;
};

```

### `PlayScreenController::_registerEventHandlers::__l8::<lambda_528e4feb743eae35d73043dac576bde7>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l8::<lambda_528e4feb743eae35d73043dac576bde7>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_e90c3f53c394e00596e10d689ad7b5fa>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_e90c3f53c394e00596e10d689ad7b5fa>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_e90c3f53c394e00596e10d689ad7b5fa>::()::__l2::<lambda_c5f0a182078f83a3877875505c62562e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_e90c3f53c394e00596e10d689ad7b5fa>::()::__l2::<lambda_c5f0a182078f83a3877875505c62562e>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>::()::__l12::<lambda_d4b4acd3b770aedc60c234b87dcebf2b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>::()::__l12::<lambda_d4b4acd3b770aedc60c234b87dcebf2b>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>::()::__l8::<lambda_5a064455ee23925ceb10376c0df7950a>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l11::<lambda_ade182cca1fe276058da9f4e3ddfa8c8>::()::__l8::<lambda_5a064455ee23925ceb10376c0df7950a>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l5::<lambda_5c4f8aa0caa6e7ad613000e3405bbe7d>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b4d47d06cc35f06a3c77e9ac3e4c7b1a>::()::__l5::<lambda_5c4f8aa0caa6e7ad613000e3405bbe7d>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_ad12c9d0a0356528d5d842767e0c0a5e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_ad12c9d0a0356528d5d842767e0c0a5e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_b5081f9dd4e78198118babdd0a40ca9f>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_b5081f9dd4e78198118babdd0a40ca9f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l18::<lambda_05c7254c8e1b80844766eb3a834dac35>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l18::<lambda_05c7254c8e1b80844766eb3a834dac35>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l18::<lambda_05c7254c8e1b80844766eb3a834dac35>::()::__l10::<lambda_04622a2f9ead9a36d61cf8bfeec9497b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l18::<lambda_05c7254c8e1b80844766eb3a834dac35>::()::__l10::<lambda_04622a2f9ead9a36d61cf8bfeec9497b>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>::()::__l8::<lambda_da30f5c8f3ccf03d45adeb8d288b5526>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>::()::__l8::<lambda_da30f5c8f3ccf03d45adeb8d288b5526>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>::()::__l8::<lambda_da30f5c8f3ccf03d45adeb8d288b5526>::()::__l13::<lambda_85dc052716261f992c276ca88eb9ad68>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d0a544a4a019b517235ded740b881a79>::()::__l11::<lambda_db704efc0cfec4aa1b48d56cdc95ca29>::()::__l8::<lambda_da30f5c8f3ccf03d45adeb8d288b5526>::()::__l13::<lambda_85dc052716261f992c276ca88eb9ad68>
{
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_aab9d1b500ae54a7598c58c6f3094d15>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_aab9d1b500ae54a7598c58c6f3094d15>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d251aa8e224fa08cf15a3045751cb51e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d251aa8e224fa08cf15a3045751cb51e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_a71a31ac168dffa79f29901fbba59d99>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_a71a31ac168dffa79f29901fbba59d99>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_6f4a477a521961b7da445a2cff83cc43>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_6f4a477a521961b7da445a2cff83cc43>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_badd045ca170ea75a76a4ff9e6245f4e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_badd045ca170ea75a76a4ff9e6245f4e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_cf57b1117fc7aa9f196bdc6da19e282e>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_cf57b1117fc7aa9f196bdc6da19e282e>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_88ec58468bd5c83184eda66b1924681b>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_88ec58468bd5c83184eda66b1924681b>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_d95779f5605b45268b012733fe56959c>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_d95779f5605b45268b012733fe56959c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_85226656f8da177ac938d10751ed3315>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_85226656f8da177ac938d10751ed3315>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_00473e6ae399516c48bdcf1535dc4d61>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_00473e6ae399516c48bdcf1535dc4d61>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_00473e6ae399516c48bdcf1535dc4d61>::()::__l2::<lambda_ea78fd3cd1090dad9c8d66e9288d7683>`
```
struct __cppobj __declspec(align(8)) PlayScreenController::_registerEventHandlers::__l2::<lambda_00473e6ae399516c48bdcf1535dc4d61>::()::__l2::<lambda_ea78fd3cd1090dad9c8d66e9288d7683>
{
  std::weak_ptr<PlayScreenController> weakThis;
  int index;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_bcc37397c1bb4abd73e6c37a935c8709>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_bcc37397c1bb4abd73e6c37a935c8709>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_bcc37397c1bb4abd73e6c37a935c8709>::()::__l2::<lambda_aa72b1814e1e5853b84f86949d49b214>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_bcc37397c1bb4abd73e6c37a935c8709>::()::__l2::<lambda_aa72b1814e1e5853b84f86949d49b214>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_87e606e0c34b5901f202d95a257c676f>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_87e606e0c34b5901f202d95a257c676f>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_87e606e0c34b5901f202d95a257c676f>::()::__l2::<lambda_086afb692fa9ff05ba6969c8b8a127b7>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_87e606e0c34b5901f202d95a257c676f>::()::__l2::<lambda_086afb692fa9ff05ba6969c8b8a127b7>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_ea2698b1d85c175ddbacb33a0b2f96de>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_ea2698b1d85c175ddbacb33a0b2f96de>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_ea2698b1d85c175ddbacb33a0b2f96de>::()::__l2::<lambda_0c17704a50ccab4eb58a620bf658f0cb>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_ea2698b1d85c175ddbacb33a0b2f96de>::()::__l2::<lambda_0c17704a50ccab4eb58a620bf658f0cb>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_7fa48011f28978d11b4372b93972b457>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_7fa48011f28978d11b4372b93972b457>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l14::<lambda_f2a4ee8e86226dc5acaa01d4354e34e5>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l14::<lambda_f2a4ee8e86226dc5acaa01d4354e34e5>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l2::<lambda_945ba34b78c3e0b7a06c9b2c699aeb27>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_45df4ea451acfc299137b2ae2281b9d3>::()::__l2::<lambda_945ba34b78c3e0b7a06c9b2c699aeb27>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>::()::__l8::<lambda_00767ba11ac5eb7a7347442702401819>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>::()::__l8::<lambda_00767ba11ac5eb7a7347442702401819>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>::()::__l2::<lambda_b8025d7ed80dc5fe242d113c186176bb>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_acc3369389f20dacb0d4ebc89ea4c416>::()::__l2::<lambda_b8025d7ed80dc5fe242d113c186176bb>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_54de84865128fdeb41729ad70bcbb05c>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_54de84865128fdeb41729ad70bcbb05c>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l2::<lambda_edbda56587dc37c5b1df71cfcb526645>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l2::<lambda_edbda56587dc37c5b1df71cfcb526645>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l5::<lambda_b3549b38b8ef669502a6d96fcccd2961>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l5::<lambda_b3549b38b8ef669502a6d96fcccd2961>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>::()::__l2::<lambda_932676f73c2e30fc920007986b4973a5>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>::()::__l2::<lambda_932676f73c2e30fc920007986b4973a5>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>::()::__l2::<lambda_edd0755e12edacc7f98c69f0f896ea35>`
```
struct __cppobj PlayScreenController::_registerEventHandlers::__l5::<lambda_f904001157c4cc319537738b47211352>::()::__l2::<lambda_edd0755e12edacc7f98c69f0f896ea35>
{
  bool *bIsLowDiskSpaceWarning;
};

```

### `PlayScreenController::_handleLeaveRealm::__l2::<lambda_502388f85e522d9c6bce8473494dad69>::()::__l8::<lambda_b82d00b4b68792cb23973ebf006dcdd5>`
```
struct __cppobj PlayScreenController::_handleLeaveRealm::__l2::<lambda_502388f85e522d9c6bce8473494dad69>::()::__l8::<lambda_b82d00b4b68792cb23973ebf006dcdd5>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::_handleStartRealm::__l16::<lambda_d70dfdc9f0eba75c735a22cea2270556>`
```
struct __cppobj PlayScreenController::_handleStartRealm::__l16::<lambda_d70dfdc9f0eba75c735a22cea2270556>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PlayScreenController::{ctor}::__l2::<lambda_e0f6f76a0e19e610ae74bd70f8888fbc>`
```
struct __cppobj PlayScreenController::{ctor}::__l2::<lambda_e0f6f76a0e19e610ae74bd70f8888fbc>
{
  PlayScreenController *const __this;
};

```

### `PlayScreenController::{ctor}::__l2::<lambda_ee0d3a065dd06691409a1e5f27cba237>`
```
struct __cppobj PlayScreenController::{ctor}::__l2::<lambda_ee0d3a065dd06691409a1e5f27cba237>
{
  PlayScreenController *const __this;
};

```

### `PersonaScreenControllerCommon::{ctor}::__l2::<lambda_5708514e361315d6933e85775690f40f>`
```
struct __cppobj PersonaScreenControllerCommon::{ctor}::__l2::<lambda_5708514e361315d6933e85775690f40f>
{
  std::weak_ptr<bool> weakExistance;
  PersonaScreenControllerCommon *const __this;
};

```

### `PersonaScreenController::_getOnPersonaPiecePurchasedCallback::__l2::<lambda_c9f67eac58aaa72dd91659caed91d07b>`
```
struct __cppobj PersonaScreenController::_getOnPersonaPiecePurchasedCallback::__l2::<lambda_c9f67eac58aaa72dd91659caed91d07b>
{
};

```

### `PersonaScreenController::_getOnPersonaPieceAppliedCallback::__l2::<lambda_cd137830e91fafd99e715b686283f68c>`
```
struct __cppobj PersonaScreenController::_getOnPersonaPieceAppliedCallback::__l2::<lambda_cd137830e91fafd99e715b686283f68c>
{
  std::weak_ptr<PersonaScreenController> weakThis;
  bool isOwned;
  __declspec(align(4)) _BYTE pieceType[4];
};

```

### `PersonaScreenController::_pickCustomSkin::__l2::<lambda_6e09e6db2b5174cecddda50cc3d63553>`
```
struct __cppobj PersonaScreenController::_pickCustomSkin::__l2::<lambda_6e09e6db2b5174cecddda50cc3d63553>
{
  std::weak_ptr<PersonaScreenController> weakThis;
};

```

### `PersonaScreenController::_ensureSkinPackIsLoaded::__l2::<lambda_abeb3de15768ea8f71711fcf515e615e>`
```
struct __cppobj PersonaScreenController::_ensureSkinPackIsLoaded::__l2::<lambda_abeb3de15768ea8f71711fcf515e615e>
{
  std::weak_ptr<PersonaScreenController> weakThis;
  mce::UUID uuid;
};

```

### `PersonaScreenController::_unselectActiveOffer::__l2::<lambda_56f827425d30039c3475a817286bacf3>`
```
struct __cppobj PersonaScreenController::_unselectActiveOffer::__l2::<lambda_56f827425d30039c3475a817286bacf3>
{
  std::weak_ptr<PersonaScreenController> weakThis;
  std::function<void __cdecl(void)> cb;
};

```

### `PersonaScreenController::_unselectSubCategory::__l5::<lambda_1180534521e4dd1a88bf3d0426253722>`
```
struct __cppobj PersonaScreenController::_unselectSubCategory::__l5::<lambda_1180534521e4dd1a88bf3d0426253722>
{
  std::weak_ptr<PersonaScreenController> weakThis;
};

```

### `PersonaScreenController::_switchToPersonaSkin::__l7::<lambda_d31ad24e7e451b30bf3779996c113293>`
```
struct __cppobj PersonaScreenController::_switchToPersonaSkin::__l7::<lambda_d31ad24e7e451b30bf3779996c113293>
{
  PersonaScreenController *const __this;
  std::weak_ptr<PersonaScreenController> weakThis;
};

```

### `PersonaScreenController::_createProxy::__l2::<lambda_b860f6d30379807a40efe3edf37be124>`
```
struct __cppobj PersonaScreenController::_createProxy::__l2::<lambda_b860f6d30379807a40efe3edf37be124>
{
  PersonaScreenController *const __this;
};

```

### `PermissionsScreenController::_handleOperatorAbility::__l2::<lambda_8ca40d6e93d98a0ecb278474e31671ef>`
```
struct __cppobj PermissionsScreenController::_handleOperatorAbility::__l2::<lambda_8ca40d6e93d98a0ecb278474e31671ef>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_9ef73a27b0ff79adfbc429e8945667cb>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_9ef73a27b0ff79adfbc429e8945667cb>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_c52814f5e834d31df38c3757358e73f6>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_c52814f5e834d31df38c3757358e73f6>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_956b92f5f4c58b901f6f2704d2e7d1b6>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_956b92f5f4c58b901f6f2704d2e7d1b6>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_9e49cc828386989ccddf74020bf594a3>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_9e49cc828386989ccddf74020bf594a3>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_b3494452536d3b4ecb28b6eefbf6f9c4>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_b3494452536d3b4ecb28b6eefbf6f9c4>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_423969ff362202740ad9e56040e1d5e6>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_423969ff362202740ad9e56040e1d5e6>
{
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_a6be3ebd1c4e42cbe95f4337431896fe>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_a6be3ebd1c4e42cbe95f4337431896fe>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l9::<lambda_3cb7edad092389d885645da1fa98ec1e>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l9::<lambda_3cb7edad092389d885645da1fa98ec1e>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_e05b15d5ba1f91ec79aaf3db8261c692>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_e05b15d5ba1f91ec79aaf3db8261c692>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_fd00941f8b0b8614cd98a8e0582ca2e1>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_fd00941f8b0b8614cd98a8e0582ca2e1>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_1959c0a09325c681dff5485c021762d6>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_1959c0a09325c681dff5485c021762d6>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_9388ff69547df82a4d5ff3236d24323e>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_9388ff69547df82a4d5ff3236d24323e>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_b890b9f1ba29b89f8ae32540bbc0cdb0>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_b890b9f1ba29b89f8ae32540bbc0cdb0>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_a934ef1921e08497e69f351a4ffe6399>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_a934ef1921e08497e69f351a4ffe6399>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_ff56abee9593a2ae1f5132351cfc0064>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_ff56abee9593a2ae1f5132351cfc0064>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_65a360a78b781eb1b84931f8d840ff23>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_65a360a78b781eb1b84931f8d840ff23>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_085221c0b7aaecceaea9b378a6e00a3e>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_085221c0b7aaecceaea9b378a6e00a3e>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_40445976d8ad786f8cd7de0b64dae041>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_40445976d8ad786f8cd7de0b64dae041>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_1cfe0d08f088dd2284ed12ba7117e696>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_1cfe0d08f088dd2284ed12ba7117e696>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l6::<lambda_124c4bb36ef89e4f1d070ab6a2de49c5>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l6::<lambda_124c4bb36ef89e4f1d070ab6a2de49c5>
{
  PermissionsScreenController *const __this;
  const std::pair<std::string const ,int> nameValuePair;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_5d0edff7689549aa7a61e4031d1ab5c0>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_5d0edff7689549aa7a61e4031d1ab5c0>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_63ff0261c11c2fdbf511ec85d8c2f67e>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_63ff0261c11c2fdbf511ec85d8c2f67e>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_cd34f01f7283c0554a1e08947d0f3b3b>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_cd34f01f7283c0554a1e08947d0f3b3b>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_70834b5ecd3bde472bc6eae8ce3a6b2c>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_70834b5ecd3bde472bc6eae8ce3a6b2c>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_2a37cd075393af1101288544fb3998d6>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_2a37cd075393af1101288544fb3998d6>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_b6fcae1c09acd5a92924acfd2c3e8abb>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_b6fcae1c09acd5a92924acfd2c3e8abb>
{
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_36e15c411c4741ff477017cdd0dd482d>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_36e15c411c4741ff477017cdd0dd482d>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerBindings::__l2::<lambda_177fb8b82847d4501e8a35ee1aa615e8>`
```
struct __cppobj PermissionsScreenController::_registerBindings::__l2::<lambda_177fb8b82847d4501e8a35ee1aa615e8>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l11::<lambda_7bebacee89ad03baefca936fb00946f8>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l11::<lambda_7bebacee89ad03baefca936fb00946f8>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l11::<lambda_7bebacee89ad03baefca936fb00946f8>::()::__l5::<lambda_e19bed6ef6721cd8c8d72df4c9ef2e82>::()::__l11::<lambda_f61a2d45a379aa29bfa8f9d58d311604>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l11::<lambda_7bebacee89ad03baefca936fb00946f8>::()::__l5::<lambda_e19bed6ef6721cd8c8d72df4c9ef2e82>::()::__l11::<lambda_f61a2d45a379aa29bfa8f9d58d311604>
{
};

```

### `PermissionsScreenController::_registerEventHandlers::__l11::<lambda_a04a36aa5554b94dd1c0329bd451095c>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l11::<lambda_a04a36aa5554b94dd1c0329bd451095c>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l11::<lambda_a04a36aa5554b94dd1c0329bd451095c>::()::__l5::<lambda_e158c3af67f9b2f24be4b01f6a1d640f>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l11::<lambda_a04a36aa5554b94dd1c0329bd451095c>::()::__l5::<lambda_e158c3af67f9b2f24be4b01f6a1d640f>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
  PlayerListInfo selectedPlayerInfo;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l9::<lambda_fe726f5f1c98d05329b456fe85ababf2>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l9::<lambda_fe726f5f1c98d05329b456fe85ababf2>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l9::<lambda_fe726f5f1c98d05329b456fe85ababf2>::()::__l2::<lambda_8fc21cdfed38209f92fe856b88abf54c>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l9::<lambda_fe726f5f1c98d05329b456fe85ababf2>::()::__l2::<lambda_8fc21cdfed38209f92fe856b88abf54c>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_e804333a5fb196ccf63a6939b8e6e792>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_e804333a5fb196ccf63a6939b8e6e792>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_e804333a5fb196ccf63a6939b8e6e792>::()::__l2::<lambda_8978a657ef4ee5f8a72814161f5b1ca7>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_e804333a5fb196ccf63a6939b8e6e792>::()::__l2::<lambda_8978a657ef4ee5f8a72814161f5b1ca7>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
  ToggleChangeEventData toggleData;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>
{
  const std::pair<std::string const ,int> nameValuePair;
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>::()::__l23::<lambda_21a846838783de0a4ca53db7bb9e8b1b>`
```
struct __cppobj __declspec(align(8)) PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>::()::__l23::<lambda_21a846838783de0a4ca53db7bb9e8b1b>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
  PlayerPermissionLevel level;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>::()::__l8::<lambda_4508d25ce1aec5cb573adff1fcbbb358>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l6::<lambda_12ca00f27baf5af8b787e48c89a72caa>::()::__l8::<lambda_4508d25ce1aec5cb573adff1fcbbb358>
{
  std::weak_ptr<PermissionsScreenController> weakThis;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_c039e74a36950455b7adc331301132ad>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_c039e74a36950455b7adc331301132ad>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_8a677980bd1bf614f101f9c43d547104>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_8a677980bd1bf614f101f9c43d547104>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_3319f8676780be35c421ac58af6b5c6b>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_3319f8676780be35c421ac58af6b5c6b>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_d37894c362a21485949af312a8861881>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_d37894c362a21485949af312a8861881>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::_registerEventHandlers::__l2::<lambda_8908df2c1244723f679618c849a5460d>`
```
struct __cppobj PermissionsScreenController::_registerEventHandlers::__l2::<lambda_8908df2c1244723f679618c849a5460d>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::handleGameEventNotification::__l5::<lambda_b6cb2be06a66b08858d4f26c6f052644>`
```
struct __cppobj PermissionsScreenController::handleGameEventNotification::__l5::<lambda_b6cb2be06a66b08858d4f26c6f052644>
{
  PermissionsScreenController *const __this;
};

```

### `PermissionsScreenController::tick::__l5::<lambda_6259efd28d1dcc3054917f423c834d5a>`
```
struct __cppobj PermissionsScreenController::tick::__l5::<lambda_6259efd28d1dcc3054917f423c834d5a>
{
  PermissionsScreenController *const __this;
};

```

### `PerfTurtleScreenController::_registerBindings::__l2::<lambda_cfce8e6046c8280a5d1668602d3c6f43>`
```
struct __cppobj PerfTurtleScreenController::_registerBindings::__l2::<lambda_cfce8e6046c8280a5d1668602d3c6f43>
{
};

```

### `PerfTurtleScreenController::_registerBindings::__l2::<lambda_28b790cb8005a9bc26e86025535c60da>`
```
struct __cppobj PerfTurtleScreenController::_registerBindings::__l2::<lambda_28b790cb8005a9bc26e86025535c60da>
{
};

```

### `PlayScreenController::_importRetailWorld::__l2::<lambda_23409e892628734f95cd60e9f1f0b661>`
```
struct __cppobj PlayScreenController::_importRetailWorld::__l2::<lambda_23409e892628734f95cd60e9f1f0b661>
{
  std::weak_ptr<PlayScreenController> weakThis;
};

```

### `PurchaseEnabledScreenController::_getMinecoinTransactionContext::__l2::<lambda_49aff632b28769508f577595198d9f7b>`
```
struct __cppobj __declspec(align(8)) PurchaseEnabledScreenController::_getMinecoinTransactionContext::__l2::<lambda_49aff632b28769508f577595198d9f7b>
{
  std::weak_ptr<PurchaseEnabledScreenController> weakThis;
  const int coinCount;
};

```

### `PersonaScreenController::_scrollAndSetFocusToCollectionItem::__l2::<lambda_18fc0a79fe9b1854cc27a65bcdf26f58>::()::__l5::<lambda_49b603cfbecf08a90f5a82e9dee4ad6c>`
```
struct __cppobj __declspec(align(8)) PersonaScreenController::_scrollAndSetFocusToCollectionItem::__l2::<lambda_18fc0a79fe9b1854cc27a65bcdf26f58>::()::__l5::<lambda_49b603cfbecf08a90f5a82e9dee4ad6c>
{
  PersonaScreenController *const __this;
  std::string pieceCollectionNameStr;
  unsigned __int64 i;
  _BYTE retrievalType[4];
};

```

### `PersonaScreenController::_scrollAndSetFocusToCollectionItem::__l2::<lambda_18fc0a79fe9b1854cc27a65bcdf26f58>::()::__l5::<lambda_49b603cfbecf08a90f5a82e9dee4ad6c>::()::__l2::<lambda_f59c5b14e9a69e65f90304d27c66ee18>`
```
struct __cppobj PersonaScreenController::_scrollAndSetFocusToCollectionItem::__l2::<lambda_18fc0a79fe9b1854cc27a65bcdf26f58>::()::__l5::<lambda_49b603cfbecf08a90f5a82e9dee4ad6c>::()::__l2::<lambda_f59c5b14e9a69e65f90304d27c66ee18>
{
  PersonaScreenController *const __this;
  std::string pieceCollectionNameStr;
  unsigned __int64 i;
};

```

### `PlatformMultiplayerRestrictions::<lambda_57b7e6fa42a36ab891a47324c480d2dc>`
```
struct __cppobj PlatformMultiplayerRestrictions::<lambda_57b7e6fa42a36ab891a47324c480d2dc>
{
};

```

### `PatchNotesManager::_processItemResponse::__l16::<lambda_6e8cc23b1ed13b347f8f5416418af98c>`
```
struct __cppobj __declspec(align(8)) PatchNotesManager::_processItemResponse::__l16::<lambda_6e8cc23b1ed13b347f8f5416418af98c>
{
  PatchNotesManager *const __this;
  int patchIndex;
};

```

### `PatchNotesManager::_processItemResponse::__l11::<lambda_0c9678014be5d562f4585223dc5368f7>`
```
struct __cppobj __declspec(align(8)) PatchNotesManager::_processItemResponse::__l11::<lambda_0c9678014be5d562f4585223dc5368f7>
{
  PatchNotesManager *const __this;
  int patchIndex;
};

```

### `PatchNotesManager::_processItemResponse::__l8::<lambda_1c52e53eb7fbd7981843de30131a89f7>`
```
struct __cppobj PatchNotesManager::_processItemResponse::__l8::<lambda_1c52e53eb7fbd7981843de30131a89f7>
{
  PatchNotesManager *const __this;
  PatchInfo *patch;
};

```

### `PatchNotesManager::_processItemResponse::__l8::<lambda_1c52e53eb7fbd7981843de30131a89f7>::()::__l12::<lambda_f7f2dc9d04e0ac8e3a0792e711d5ba29>`
```
struct __cppobj PatchNotesManager::_processItemResponse::__l8::<lambda_1c52e53eb7fbd7981843de30131a89f7>::()::__l12::<lambda_f7f2dc9d04e0ac8e3a0792e711d5ba29>
{
  PatchInfo *patch;
};

```

### `PatchNotesManager::_processSearchResults::__l2::<lambda_22c49ea0279dd0943d3745509c29d87a>`
```
struct __cppobj __declspec(align(8)) PatchNotesManager::_processSearchResults::__l2::<lambda_22c49ea0279dd0943d3745509c29d87a>
{
  PatchNotesManager *const __this;
  unsigned int patchIndex;
};

```

### `PatchNotesManager::fetch::__l15::<lambda_c5d04ecc90bd84e1bddc37b184c6bb75>`
```
struct __cppobj __declspec(align(8)) PatchNotesManager::fetch::__l15::<lambda_c5d04ecc90bd84e1bddc37b184c6bb75>
{
  PatchNotesManager *const __this;
  bool forceHydrate;
};

```

### `PacksModelFactory`
```
struct __cppobj PacksModelFactory
{
};

```

### `PackManagerContentSource::repopulateReports::__l2::<lambda_d69fe51ea9222ba24c9aaf35c39a94db>`
```
struct __cppobj PackManagerContentSource::repopulateReports::__l2::<lambda_d69fe51ea9222ba24c9aaf35c39a94db>
{
  std::vector<PackInstanceId> stackIdentities;
  PackManagerContentSource *const __this;
};

```

### `PatchNotesModel`
```
struct __cppobj PatchNotesModel
{
  std::unique_ptr<CatalogInfo> mCatalogInfo;
};

```

### `PremiumCachePackCollector`
```
struct __cppobj __declspec(align(8)) PremiumCachePackCollector : SkinPackCollector
{
  SkinRepository *mSkinRepo;
  int mPremiumCachePacks;
};

```

### `PremiumCachePackCollector_vtbl`
```
struct /*VFT*/ PremiumCachePackCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `PlayScreenModel::_sortRealmsWorlds::__l2::<lambda_c5843e26263a2730f8cb735bbde07f0c>`
```
struct __cppobj PlayScreenModel::_sortRealmsWorlds::__l2::<lambda_c5843e26263a2730f8cb735bbde07f0c>
{
  const std::string currentUserXUID;
};

```

### `PlayScreenModel::fetchRealmsPlayerCounts::__l2::<lambda_4ead667a602684ee6e041b02d3503be4>`
```
struct __cppobj PlayScreenModel::fetchRealmsPlayerCounts::__l2::<lambda_4ead667a602684ee6e041b02d3503be4>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::_fetchTrialAvailability::__l2::<lambda_e7e01ac61a94ca844a87812e11ed7b80>`
```
struct __cppobj PlayScreenModel::_fetchTrialAvailability::__l2::<lambda_e7e01ac61a94ca844a87812e11ed7b80>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::_fetchInviteCount::__l2::<lambda_8e71c1eeb87930cfb216cda7c112a695>`
```
struct __cppobj PlayScreenModel::_fetchInviteCount::__l2::<lambda_8e71c1eeb87930cfb216cda7c112a695>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::fetchLegacyWorldsForPlayScreen::__l24::<lambda_ec3ea1f8c324ee2ad65519b80d1c2fae>`
```
struct __cppobj PlayScreenModel::fetchLegacyWorldsForPlayScreen::__l24::<lambda_ec3ea1f8c324ee2ad65519b80d1c2fae>
{
  std::weak_ptr<PlayScreenModel> weakThis;
  std::function<void __cdecl(void)> noWorldsFoundCallback;
};

```

### `PlayScreenModel::fetchThirdPartyServerWorlds::__l2::<lambda_a7d387fa25f9f4baef1c63ab142a3b6b>`
```
struct __cppobj PlayScreenModel::fetchThirdPartyServerWorlds::__l2::<lambda_a7d387fa25f9f4baef1c63ab142a3b6b>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::fetchThirdPartyServerWorlds::__l2::<lambda_7c673ac97056226e0a43fd8faab41a06>`
```
struct __cppobj PlayScreenModel::fetchThirdPartyServerWorlds::__l2::<lambda_7c673ac97056226e0a43fd8faab41a06>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::fetchRealmsWorldsForPlayScreen::__l2::<lambda_c47d849dac614a01dfa44cacfc5879e4>`
```
struct __cppobj PlayScreenModel::fetchRealmsWorldsForPlayScreen::__l2::<lambda_c47d849dac614a01dfa44cacfc5879e4>
{
  std::weak_ptr<PlayScreenModel> weakThis;
  const std::string currentUserXUID;
};

```

### `PlayScreenModel::fetchRealmsWorldsForPlayScreen::__l2::<lambda_c47d849dac614a01dfa44cacfc5879e4>::()::__l5::<lambda_7aa983d74909281d2a9b69114dbf0328>`
```
struct __cppobj PlayScreenModel::fetchRealmsWorldsForPlayScreen::__l2::<lambda_c47d849dac614a01dfa44cacfc5879e4>::()::__l5::<lambda_7aa983d74909281d2a9b69114dbf0328>
{
  std::string xuid;
};

```

### `PlayScreenModel::_updateOwnerInfo::__l15::<lambda_ee2f51179cadf67af15ab078b919172a>`
```
struct __cppobj PlayScreenModel::_updateOwnerInfo::__l15::<lambda_ee2f51179cadf67af15ab078b919172a>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::createUniquePathForWorld::__l2::<lambda_7499ed9cc7b3abfadf9e28b635fa0110>`
```
struct __cppobj PlayScreenModel::createUniquePathForWorld::__l2::<lambda_7499ed9cc7b3abfadf9e28b635fa0110>
{
};

```

### `PlayScreenModel::generateFilePickerSettingsForImport::__l2::<lambda_1a8f60f8c0b42d9b5365e4817e18c91c>::()::__l5::<lambda_6136301d55e329c417bd204600755605>`
```
struct __cppobj PlayScreenModel::generateFilePickerSettingsForImport::__l2::<lambda_1a8f60f8c0b42d9b5365e4817e18c91c>::()::__l5::<lambda_6136301d55e329c417bd204600755605>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::_populateNetworkWorlds::__l2::<lambda_783b941f78d1f9f640c2ed663931aa7c>`
```
struct __cppobj PlayScreenModel::_populateNetworkWorlds::__l2::<lambda_783b941f78d1f9f640c2ed663931aa7c>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `PlayScreenModel::_populateNetworkWorlds::__l84::<lambda_3af18e8e7ea6cc263b873e0a67716faa>`
```
struct __cppobj PlayScreenModel::_populateNetworkWorlds::__l84::<lambda_3af18e8e7ea6cc263b873e0a67716faa>
{
  std::weak_ptr<PlayScreenModel> weakThis;
  std::vector<std::string> ownerIds;
};

```

### `PlayScreenModel::deleteLegacyWorld::__l2::<lambda_56eb86b7e178ab067b3ba5b934bfdd71>`
```
struct __cppobj __declspec(align(8)) PlayScreenModel::deleteLegacyWorld::__l2::<lambda_56eb86b7e178ab067b3ba5b934bfdd71>
{
  std::weak_ptr<PlayScreenModel> weakThis;
  const unsigned int legacyWorldIndex;
};

```

### `PacksModelFactory::loadPacks::__l2::<lambda_53d14b67f6833d8dc2b9a2ea3b413111>`
```
struct __cppobj PacksModelFactory::loadPacks::__l2::<lambda_53d14b67f6833d8dc2b9a2ea3b413111>
{
  std::vector<PackModel> *availablePacks;
  PackSourceReport *loadingReport;
  std::vector<Pack const *> *notAvailablePacks;
};

```

### `PacksModelFactory::loadPacks::__l6::<lambda_55602f7931c3f5531555ed27057c9eaa>`
```
struct __cppobj PacksModelFactory::loadPacks::__l6::<lambda_55602f7931c3f5531555ed27057c9eaa>
{
  std::vector<std::pair<Pack *,PackIdVersion>> *packs;
  const PackInstanceId *each;
  std::vector<std::pair<Pack *,PackIdVersion>> *historyPacks;
};

```

### `PlayScreenModel::_startRemoteNetworkWorld::__l2::<lambda_9eeb01beb5086f5390d81cee8de261ad>`
```
struct __cppobj PlayScreenModel::_startRemoteNetworkWorld::__l2::<lambda_9eeb01beb5086f5390d81cee8de261ad>
{
  PingedCompatibleServer remoteServer;
  PlayScreenModel *const __this;
};

```

### `PlayScreenModel::generateFilePickerSettingsForImport::__l2::<lambda_1a8f60f8c0b42d9b5365e4817e18c91c>`
```
struct __cppobj PlayScreenModel::generateFilePickerSettingsForImport::__l2::<lambda_1a8f60f8c0b42d9b5365e4817e18c91c>
{
  std::weak_ptr<PlayScreenModel> weakThis;
};

```

### `persona::PersonaPieceCollectionModel::_initializeDressingRoomQueryManifest::__l2::<lambda_47f527e37023106ec5159456dcc9ca63>`
```
struct __cppobj persona::PersonaPieceCollectionModel::_initializeDressingRoomQueryManifest::__l2::<lambda_47f527e37023106ec5159456dcc9ca63>
{
  std::weak_ptr<bool> weakExistance;
  persona::PersonaPieceCollectionModel *const __this;
};

```

### `PackReportInfo`
```
struct __cppobj PackReportInfo
{
  PackReport *packReport;
  const std::string *fileName;
  const std::string *controlName;
};

```

### `PlayFabGetUserDataRequest`
```
struct __cppobj PlayFabGetUserDataRequest : RequestHandler
{
  std::function<void __cdecl(Json::Value)> mCallback;
  Json::Value mResult;
};

```

### `PlayFabGetUserDataRequest_vtbl`
```
struct /*VFT*/ PlayFabGetUserDataRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `PlayFabUpdateUserDataRequest`
```
struct __cppobj __declspec(align(8)) PlayFabUpdateUserDataRequest : RequestHandler
{
  std::string mKey;
  std::string mValue;
  std::function<void __cdecl(bool)> mCallback;
  bool mResult;
};

```

### `PlayFabUpdateUserDataRequest_vtbl`
```
struct /*VFT*/ PlayFabUpdateUserDataRequest_vtbl
{
  void (__fastcall *~RequestHandler)(RequestHandler *this);
  void (__fastcall *send)(RequestHandler *this);
  void (__fastcall *sendCachedRequest)(RequestHandler *this);
  bool (__fastcall *update)(RequestHandler *this);
  bool (__fastcall *isDone)(RequestHandler *this);
  void (__fastcall *onComplete)(RequestHandler *this);
  bool (__fastcall *canSendRequest)(RequestHandler *this);
  void (__fastcall *fireTelemetry)(RequestHandler *this, IMinecraftEventing *);
};

```

### `PistonArmModel`
```
struct __cppobj PistonArmModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mArmBase;
  ModelPart mArm;
  ModelPart mFront;
};

```

### `PistonArmModel_vtbl`
```
struct /*VFT*/ PistonArmModel_vtbl
{
  void (__fastcall *~AppPlatformListener)(AppPlatformListener *this);
  void (__fastcall *onLowMemory)(AppPlatformListener *this);
  void (__fastcall *onAppPaused)(AppPlatformListener *this);
  void (__fastcall *onAppUnpaused)(AppPlatformListener *this);
  void (__fastcall *onAppPreSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppResumed)(AppPlatformListener *this);
  void (__fastcall *onAppFocusLost)(AppPlatformListener *this);
  void (__fastcall *onAppFocusGained)(AppPlatformListener *this);
  void (__fastcall *onAppTerminated)(AppPlatformListener *this);
  void (__fastcall *onOperationModeChanged)(AppPlatformListener *this, const OperationMode);
  void (__fastcall *onPerformanceModeChanged)(AppPlatformListener *this, const bool);
  void (__fastcall *onPushNotificationReceived)(AppPlatformListener *this, const PushNotificationMessage *);
  void (__fastcall *onResizeBegin)(AppPlatformListener *this);
  void (__fastcall *onResizeEnd)(AppPlatformListener *this);
  void (__fastcall *onDeviceLost)(AppPlatformListener *this);
  void (__fastcall *clear)(Model *this);
  void (__fastcall *preDraw)(Model *this, ScreenContext *);
  void (__fastcall *postDraw)(Model *this, ScreenContext *);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *);
  void (__fastcall *render)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, ScreenContext *);
  void (__fastcall *setupAnim)(Model *this);
  void (__fastcall *setupAnim)(Model *this, float, float, float, float, float, float);
  void (__fastcall *prepareMobModel)(Model *this, Mob *, float, float, float);
  Vec3 *(__fastcall *getLeashOffsetPosition)(Model *this, Vec3 *result, bool);
  void (__fastcall *renderAniModel)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  void (__fastcall *renderMod)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *youngTransform)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  float (__fastcall *getHeightAdjustment)(Model *this);
  AABB *(__fastcall *buildAABB)(Model *this, AABB *result);
};

```

### `Painting`
```
struct __cppobj Painting : HangingActor
{
  const Motive *mMotive;
};

```

### `Painting_vtbl`
```
struct /*VFT*/ Painting_vtbl
{
  bool (__fastcall *hasComponent)(Actor *this, const HashedString *);
  void (__fastcall *reloadHardcoded)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadHardcodedClient)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *initializeComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *_serverInitItemStackIds)(Actor *this);
  void (__fastcall *_doInitialMove)(Actor *this);
  bool (__fastcall *checkAllSensitiveWords)(Actor *this);
  bool (__fastcall *checkNameTag)(Actor *this);
  void (__fastcall *~Actor)(Actor *this);
  void (__fastcall *reset)(Actor *this);
  int (__fastcall *getOnDeathExperience)(Actor *this);
  ActorType (__fastcall *getOwnerEntityType)(Actor *this);
  void (__fastcall *remove)(Actor *this);
  void (__fastcall *setPos)(Actor *this, const Vec3 *);
  const PredictedMovementValues *(__fastcall *getPredictedMovementValues)(Actor *this);
  const Vec3 *(__fastcall *getPos)(Actor *this);
  const Vec3 *(__fastcall *getPosOld)(Actor *this);
  const Vec3 *(__fastcall *getPosExtrapolated)(Actor *this, const Vec3 *result, float);
  Vec3 *(__fastcall *getAttachPos)(Actor *this, Vec3 *result, ActorLocation, float);
  Vec3 *(__fastcall *getFiringPos)(Actor *this, Vec3 *result);
  void (__fastcall *setRot)(Actor *this, const Vec2 *);
  void (__fastcall *move)(Actor *this, IActorMovementProxy *, const Vec3 *);
  void (__fastcall *move)(Actor *this, const Vec3 *);
  Vec3 *(__fastcall *getInterpolatedRidingPosition)(Actor *this, Vec3 *result, float);
  float (__fastcall *getInterpolatedBodyRot)(Actor *this, float);
  float (__fastcall *getInterpolatedHeadRot)(Actor *this, float);
  float (__fastcall *getInterpolatedBodyYaw)(Actor *this, float);
  float (__fastcall *getYawSpeedInDegreesPerSecond)(Actor *this);
  float (__fastcall *getInterpolatedWalkAnimSpeed)(Actor *this, float);
  Vec3 *(__fastcall *getInterpolatedRidingOffset)(Actor *this, Vec3 *result, float);
  void (__fastcall *checkBlockCollisions)(Actor *this);
  void (__fastcall *checkBlockCollisions)(Actor *this, const AABB *, std::function<void __cdecl(BlockSource &,Block const &,BlockPos const &,Actor &)>);
  bool (__fastcall *isFireImmune)(Actor *this);
  bool (__fastcall *breaksFallingBlocks)(Actor *this);
  void (__fastcall *blockedByShield)(Actor *this, const ActorDamageSource *, Actor *);
  void (__fastcall *teleportTo)(Actor *this, const Vec3 *, bool, int, int, const ActorUniqueID *);
  bool (__fastcall *tryTeleportTo)(Actor *this, const Vec3 *, bool, bool, int, int);
  void (__fastcall *chorusFruitTeleport)(Actor *this, Vec3 *);
  void (__fastcall *lerpTo)(Actor *this, const Vec3 *, const Vec2 *, int);
  void (__fastcall *lerpMotion)(Actor *this, const Vec3 *);
  std::unique_ptr<AddActorBasePacket> *(__fastcall *getAddPacket)(Actor *this, std::unique_ptr<AddActorBasePacket> *result);
  void (__fastcall *normalTick)(Actor *this);
  void (__fastcall *baseTick)(Actor *this);
  void (__fastcall *rideTick)(Actor *this);
  void (__fastcall *positionRider)(Actor *this, Actor *, float);
  float (__fastcall *getRidingHeight)(Actor *this);
  bool (__fastcall *startRiding)(Actor *this, Actor *);
  void (__fastcall *addRider)(Actor *this, Actor *);
  void (__fastcall *flagRiderToRemove)(Actor *this, Actor *);
  std::string *(__fastcall *getExitTip)(Actor *this, std::string *result, const std::string *, InputMode);
  bool (__fastcall *intersects)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *, float);
  bool (__fastcall *isInWall)(Actor *this);
  bool (__fastcall *isInvisible)(Actor *this);
  bool (__fastcall *canShowNameTag)(Actor *this);
  bool (__fastcall *canExistInPeaceful)(Actor *this);
  void (__fastcall *setNameTagVisible)(Actor *this, bool);
  const std::string *(__fastcall *getNameTag)(Actor *this);
  unsigned __int64 (__fastcall *getNameTagAsHash)(Actor *this);
  std::string *(__fastcall *getFormattedNameTag)(Actor *this, std::string *result);
  void (__fastcall *filterFormattedNameTag)(Actor *this, const UIProfanityContext *);
  void (__fastcall *setNameTag)(Actor *this, const std::string *);
  bool (__fastcall *getAlwaysShowNameTag)(Actor *this);
  void (__fastcall *setScoreTag)(Actor *this, const std::string *);
  const std::string *(__fastcall *getScoreTag)(Actor *this);
  bool (__fastcall *isInWater)(Actor *this);
  bool (__fastcall *hasEnteredWater)(Actor *this);
  bool (__fastcall *isImmersedInWater)(Actor *this);
  bool (__fastcall *isInWaterOrRain)(Actor *this);
  bool (__fastcall *isInLava)(Actor *this);
  bool (__fastcall *isUnderLiquid)(Actor *this, MaterialType);
  bool (__fastcall *isOverWater)(Actor *this);
  void (__fastcall *makeStuckInBlock)(Actor *this, const Vec3 *);
  float (__fastcall *getCameraOffset)(Actor *this);
  float (__fastcall *getShadowHeightOffs)(Actor *this);
  float (__fastcall *getShadowRadius)(Actor *this);
  Vec3 *(__fastcall *getHeadLookVector)(Actor *this, Vec3 *result, float);
  bool (__fastcall *canSeeInvisible)(Actor *this);
  bool (__fastcall *canSee)(Actor *this, const Vec3 *);
  bool (__fastcall *canSee)(Actor *this, const Actor *);
  bool (__fastcall *isSkyLit)(Actor *this, float);
  float (__fastcall *getBrightness)(Actor *this, float);
  bool (__fastcall *interactPreventDefault)(Actor *this);
  void (__fastcall *playerTouch)(Actor *this, Player *);
  void (__fastcall *onAboveBubbleColumn)(Actor *this, const bool);
  void (__fastcall *onInsideBubbleColumn)(Actor *this, const bool);
  bool (__fastcall *isImmobile)(Actor *this);
  bool (__fastcall *isSilent)(Actor *this);
  bool (__fastcall *isPickable)(Actor *this);
  bool (__fastcall *isFishable)(Actor *this);
  bool (__fastcall *isSleeping)(Actor *this);
  bool (__fastcall *isShootable)(Actor *this);
  void (__fastcall *setSneaking)(Actor *this, bool);
  bool (__fastcall *isBlocking)(Actor *this);
  bool (__fastcall *isDamageBlocked)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *isAlive)(Actor *this);
  bool (__fastcall *isOnFire)(Actor *this);
  bool (__fastcall *isOnHotBlock)(Actor *this);
  bool (__fastcall *isCreativeModeAllowed)(Actor *this);
  bool (__fastcall *isSurfaceMob)(Actor *this);
  bool (__fastcall *isTargetable)(Actor *this);
  bool (__fastcall *isLocalPlayer)(Actor *this);
  bool (__fastcall *isPlayer)(Actor *this);
  bool (__fastcall *canAttack)(Actor *this, Actor *, bool);
  void (__fastcall *setTarget)(Actor *this, Actor *);
  Actor *(__fastcall *findAttackTarget)(Actor *this);
  bool (__fastcall *isValidTarget)(Actor *this, Actor *);
  bool (__fastcall *attack)(Actor *this, Actor *);
  void (__fastcall *performRangedAttack)(Actor *this, Actor *, float);
  void (__fastcall *adjustDamageAmount)(Actor *this, int *);
  int (__fastcall *getEquipmentCount)(Actor *this);
  void (__fastcall *setOwner)(Actor *this, const ActorUniqueID);
  void (__fastcall *setSitting)(Actor *this, bool);
  void (__fastcall *onTame)(Actor *this);
  void (__fastcall *onFailedTame)(Actor *this);
  int (__fastcall *getInventorySize)(Actor *this);
  int (__fastcall *getEquipSlots)(Actor *this);
  int (__fastcall *getChestSlots)(Actor *this);
  void (__fastcall *setStanding)(Actor *this, bool);
  bool (__fastcall *canPowerJump)(Actor *this);
  void (__fastcall *setCanPowerJump)(Actor *this, bool);
  bool (__fastcall *isJumping)(Actor *this);
  bool (__fastcall *isEnchanted)(Actor *this);
  void (__fastcall *rideJumped)(Actor *this);
  void (__fastcall *rideLanded)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *shouldRender)(Actor *this);
  bool (__fastcall *isInvulnerableTo)(Actor *this, const ActorDamageSource *);
  ActorDamageCause (__fastcall *getBlockDamageCause)(Actor *this, const Block *);
  void (__fastcall *actuallyHurt)(Actor *this, int, const ActorDamageSource *, bool);
  void (__fastcall *animateHurt)(Actor *this);
  bool (__fastcall *doFireHurt)(Actor *this, int);
  void (__fastcall *onLightningHit)(Actor *this);
  void (__fastcall *onBounceStarted)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *feed)(Actor *this, int);
  void (__fastcall *handleEntityEvent)(Actor *this, ActorEvent, int);
  float (__fastcall *getPickRadius)(Actor *this);
  const HashedString *(__fastcall *getActorRendererId)(Actor *this);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const ItemStack *, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int);
  void (__fastcall *despawn)(Actor *this);
  void (__fastcall *killed)(Actor *this, Actor *);
  void (__fastcall *awardKillScore)(Actor *this, Actor *, int);
  void (__fastcall *setArmor)(Actor *this, ArmorSlot, const ItemStack *);
  const ItemStack *(__fastcall *getArmor)(Actor *this, ArmorSlot);
  ArmorMaterialType (__fastcall *getArmorMaterialTypeInSlot)(Actor *this, ArmorSlot);
  ArmorTextureType (__fastcall *getArmorMaterialTextureTypeInSlot)(Actor *this, ArmorSlot);
  float (__fastcall *getArmorColorInSlot)(Actor *this, ArmorSlot, int);
  const ItemStack *(__fastcall *getEquippedSlot)(Actor *this, EquipmentSlot);
  void (__fastcall *setEquippedSlot)(Actor *this, EquipmentSlot, const ItemStack *);
  const ItemStack *(__fastcall *getCarriedItem)(Actor *this);
  void (__fastcall *setCarriedItem)(Actor *this, const ItemStack *);
  void (__fastcall *setOffhandSlot)(Actor *this, const ItemStack *);
  const ItemStack *(__fastcall *getEquippedTotem)(Actor *this);
  bool (__fastcall *consumeTotem)(Actor *this);
  bool (__fastcall *save)(Actor *this, CompoundTag *);
  void (__fastcall *saveWithoutId)(Actor *this, CompoundTag *);
  bool (__fastcall *load)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *loadLinks)(Actor *this, const CompoundTag *, std::vector<ActorLink> *, DataLoadHelper *);
  ActorType (__fastcall *getEntityTypeId)(Actor *this);
  const HashedString *(__fastcall *queryEntityRenderer)(Actor *this);
  ActorUniqueID *(__fastcall *getSourceUniqueID)(Actor *this, ActorUniqueID *result);
  void (__fastcall *setOnFire)(Actor *this, int);
  AABB *(__fastcall *getHandleWaterAABB)(Actor *this, AABB *result);
  void (__fastcall *handleInsidePortal)(Actor *this, const BlockPos *);
  int (__fastcall *getPortalCooldown)(Actor *this);
  int (__fastcall *getPortalWaitTime)(Actor *this);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(Actor *this, AutomaticID<Dimension,int> *result);
  bool (__fastcall *canChangeDimensions)(Actor *this);
  void (__fastcall *changeDimension)(Actor *this, const ChangeDimensionPacket *);
  void (__fastcall *changeDimension)(Actor *this, AutomaticID<Dimension,int>, bool);
  ActorUniqueID *(__fastcall *getControllingPlayer)(Actor *this, ActorUniqueID *result);
  void (__fastcall *checkFallDamage)(Actor *this, float, bool);
  void (__fastcall *causeFallDamage)(Actor *this, float);
  void (__fastcall *handleFallDistanceOnServer)(Actor *this, float, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, int, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, const Block *, bool);
  void (__fastcall *onSynchedDataUpdate)(Actor *this, int);
  bool (__fastcall *canAddRider)(Actor *this, Actor *);
  bool (__fastcall *canPickupItem)(Actor *this, const ItemStack *);
  bool (__fastcall *canBePulledIntoVehicle)(Actor *this);
  bool (__fastcall *inCaravan)(Actor *this);
  bool (__fastcall *isLeashableType)(Actor *this);
  void (__fastcall *tickLeash)(Actor *this);
  void (__fastcall *sendMotionPacketIfNeeded)(Actor *this);
  bool (__fastcall *canSynchronizeNewEntity)(Actor *this);
  bool (__fastcall *stopRiding)(Actor *this, bool, bool, bool, bool);
  void (__fastcall *startSwimming)(Actor *this);
  void (__fastcall *stopSwimming)(Actor *this);
  void (__fastcall *buildDebugInfo)(Actor *this, std::string *);
  CommandPermissionLevel (__fastcall *getCommandPermissionLevel)(Actor *this);
  AttributeInstance *(__fastcall *getMutableAttribute)(Actor *this, const Attribute *);
  const AttributeInstance *(__fastcall *getAttribute)(Actor *this, const Attribute *);
  int (__fastcall *getDeathTime)(Actor *this);
  void (__fastcall *heal)(Actor *this, int);
  bool (__fastcall *isInvertedHealAndHarm)(Actor *this);
  bool (__fastcall *canBeAffected)(Actor *this, const MobEffectInstance *);
  bool (__fastcall *canBeAffected)(Actor *this, int);
  bool (__fastcall *canBeAffectedByArrow)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectAdded)(Actor *this, MobEffectInstance *);
  void (__fastcall *onEffectUpdated)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectRemoved)(Actor *this, MobEffectInstance *);
  AnimationComponent *(__fastcall *getAnimationComponent)(Actor *this);
  void (__fastcall *openContainerComponent)(Actor *this, Player *);
  void (__fastcall *swing)(Actor *this);
  void (__fastcall *useItem)(Actor *this, ItemStackBase *, ItemUseMethod, bool);
  bool (__fastcall *hasOutputSignal)(Actor *this, unsigned __int8);
  int (__fastcall *getOutputSignal)(Actor *this);
  void (__fastcall *getDebugText)(Actor *this, std::vector<std::string> *);
  float (__fastcall *getMapDecorationRotation)(Actor *this);
  float (__fastcall *getRiderYRotation)(Actor *this, const Actor *);
  float (__fastcall *getYHeadRot)(Actor *this);
  bool (__fastcall *isWorldBuilder)(Actor *this);
  bool (__fastcall *isCreative)(Actor *this);
  bool (__fastcall *isAdventure)(Actor *this);
  bool (__fastcall *add)(Actor *this, ItemStack *);
  bool (__fastcall *drop)(Actor *this, const ItemStack *, bool);
  bool (__fastcall *getInteraction)(Actor *this, Player *, ActorInteraction *, const Vec3 *);
  bool (__fastcall *canDestroyBlock)(Actor *this, const Block *);
  void (__fastcall *setAuxValue)(Actor *this, int);
  void (__fastcall *setSize)(Actor *this, float, float);
  int (__fastcall *getLifeSpan)(Actor *this);
  void (__fastcall *onOrphan)(Actor *this);
  void (__fastcall *wobble)(Actor *this);
  bool (__fastcall *wasHurt)(Actor *this);
  void (__fastcall *startSpinAttack)(Actor *this);
  void (__fastcall *stopSpinAttack)(Actor *this);
  void (__fastcall *setDamageNearbyMobs)(Actor *this, bool);
  bool (__fastcall *hasCritBox)(Actor *this);
  bool (__fastcall *isCritHit)(Actor *this);
  void (__fastcall *renderDebugServerState)(Actor *this, const Options *);
  void (__fastcall *reloadLootTable)(Actor *this, const EquipmentTableDefinition *);
  void (__fastcall *reloadLootTable)(Actor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(Actor *this);
  void (__fastcall *kill)(Actor *this);
  void (__fastcall *die)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *shouldTick)(Actor *this);
  std::shared_ptr<IActorMovementProxy> *(__fastcall *createMovementProxy)(Actor *this, std::shared_ptr<IActorMovementProxy> *result);
  void (__fastcall *updateEntitySpecificMolangVariables)(Actor *this, RenderParams *);
  bool (__fastcall *shouldTryMakeStepSound)(Actor *this);
  float (__fastcall *getNextStep)(Actor *this, const float);
  bool (__fastcall *canMakeStepSound)(Actor *this);
  void (__fastcall *outOfWorld)(Actor *this);
  bool (__fastcall *_hurt)(Actor *this, const ActorDamageSource *, int, bool, bool);
  void (__fastcall *markHurt)(Actor *this);
  void (__fastcall *readAdditionalSaveData)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *addAdditionalSaveData)(Actor *this, CompoundTag *);
  void (__fastcall *_playStepSound)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *_playFlySound)(Actor *this, const BlockPos *, const Block *);
  bool (__fastcall *_makeFlySound)(Actor *this);
  void (__fastcall *checkInsideBlocks)(Actor *this, float);
  void (__fastcall *pushOutOfBlocks)(Actor *this, const Vec3 *);
  bool (__fastcall *updateWaterState)(Actor *this);
  void (__fastcall *doWaterSplashEffect)(Actor *this);
  void (__fastcall *spawnTrailBubbles)(Actor *this);
  void (__fastcall *updateInsideBlock)(Actor *this);
  LootTable *(__fastcall *getLootTable)(Actor *this);
  LootTable *(__fastcall *getDefaultLootTable)(Actor *this);
  void (__fastcall *_removeRider)(Actor *this, const ActorUniqueID *, bool, bool, bool);
  void (__fastcall *_onSizeUpdated)(Actor *this);
  void (__fastcall *_doAutoAttackOnTouch)(Actor *this, Actor *);
  void (__fastcall *setDir)(HangingActor *this, int);
  int (__fastcall *getWidth)(HangingActor *this);
  int (__fastcall *getHeight)(HangingActor *this);
  void (__fastcall *dropItem)(HangingActor *this);
  bool (__fastcall *placeHangingEntity)(HangingActor *this, BlockSource *, int);
  bool (__fastcall *wouldSurvive)(HangingActor *this, BlockSource *);
};

```

### `PlayerModel`
```
struct __cppobj __declspec(align(8)) PlayerModel : HumanoidModel
{
  mce::MaterialPtr mDefaultMaterial;
  mce::MaterialPtr mAlphaTestMaterial;
  glm::tvec4<float,0> mOldFogColor;
  glm::tvec2<float,0> mOldFogControl;
  ModelPart mRightSleeve;
  ModelPart mLeftSleeve;
  ModelPart mLeftPants;
  ModelPart mLeftLegging;
  ModelPart mLeftSock;
  ModelPart mLeftBoot;
  ModelPart mRightPants;
  ModelPart mRightLegging;
  ModelPart mRightSock;
  ModelPart mRightBoot;
  ModelPart mJacket;
  ModelPart mBelt;
  ModelPart mCape;
  ModelPart mHelmet;
  ModelPart mBodyArmor;
  ModelPart mLeftArmArmor;
  ModelPart mRightArmArmor;
  bool mSlimSteve;
};

```

### `PlayerModel_vtbl`
```
struct /*VFT*/ PlayerModel_vtbl
{
  void (__fastcall *~AppPlatformListener)(AppPlatformListener *this);
  void (__fastcall *onLowMemory)(AppPlatformListener *this);
  void (__fastcall *onAppPaused)(AppPlatformListener *this);
  void (__fastcall *onAppUnpaused)(AppPlatformListener *this);
  void (__fastcall *onAppPreSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppSuspended)(AppPlatformListener *this);
  void (__fastcall *onAppResumed)(AppPlatformListener *this);
  void (__fastcall *onAppFocusLost)(AppPlatformListener *this);
  void (__fastcall *onAppFocusGained)(AppPlatformListener *this);
  void (__fastcall *onAppTerminated)(AppPlatformListener *this);
  void (__fastcall *onOperationModeChanged)(AppPlatformListener *this, const OperationMode);
  void (__fastcall *onPerformanceModeChanged)(AppPlatformListener *this, const bool);
  void (__fastcall *onPushNotificationReceived)(AppPlatformListener *this, const PushNotificationMessage *);
  void (__fastcall *onResizeBegin)(AppPlatformListener *this);
  void (__fastcall *onResizeEnd)(AppPlatformListener *this);
  void (__fastcall *onDeviceLost)(AppPlatformListener *this);
  void (__fastcall *clear)(Model *this);
  void (__fastcall *preDraw)(Model *this, ScreenContext *);
  void (__fastcall *postDraw)(Model *this, ScreenContext *);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, BaseActorRenderContext *);
  void (__fastcall *render)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *render)(Model *this, ScreenContext *);
  void (__fastcall *setupAnim)(Model *this);
  void (__fastcall *setupAnim)(Model *this, float, float, float, float, float, float);
  void (__fastcall *prepareMobModel)(Model *this, Mob *, float, float, float);
  Vec3 *(__fastcall *getLeashOffsetPosition)(Model *this, Vec3 *result, bool);
  void (__fastcall *renderAniModel)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  void (__fastcall *renderMod)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float);
  void (__fastcall *youngTransform)(Model *this, ScreenContext *, Actor *, float, float, float, float, float, float, MatrixStack::MatrixStackRef *);
  float (__fastcall *getHeightAdjustment)(Model *this);
  AABB *(__fastcall *buildAABB)(Model *this, AABB *result);
  void (__fastcall *renderAniModel)(HumanoidModel *this, ScreenContext *, int, float, float);
  void (__fastcall *renderGui)(PlayerModel *this, ScreenContext *, Actor *, float, bool, float, float, int, float);
};

```

### `PredictableProjectile`
```
struct __cppobj PredictableProjectile : Actor
{
};

```

### `PredictableProjectile_vtbl`
```
struct /*VFT*/ PredictableProjectile_vtbl
{
  bool (__fastcall *hasComponent)(Actor *this, const HashedString *);
  void (__fastcall *reloadHardcoded)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadHardcodedClient)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *initializeComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *_serverInitItemStackIds)(Actor *this);
  void (__fastcall *_doInitialMove)(Actor *this);
  bool (__fastcall *checkAllSensitiveWords)(Actor *this);
  bool (__fastcall *checkNameTag)(Actor *this);
  void (__fastcall *~Actor)(Actor *this);
  void (__fastcall *reset)(Actor *this);
  int (__fastcall *getOnDeathExperience)(Actor *this);
  ActorType (__fastcall *getOwnerEntityType)(Actor *this);
  void (__fastcall *remove)(Actor *this);
  void (__fastcall *setPos)(Actor *this, const Vec3 *);
  const PredictedMovementValues *(__fastcall *getPredictedMovementValues)(Actor *this);
  const Vec3 *(__fastcall *getPos)(Actor *this);
  const Vec3 *(__fastcall *getPosOld)(Actor *this);
  const Vec3 *(__fastcall *getPosExtrapolated)(Actor *this, const Vec3 *result, float);
  Vec3 *(__fastcall *getAttachPos)(Actor *this, Vec3 *result, ActorLocation, float);
  Vec3 *(__fastcall *getFiringPos)(Actor *this, Vec3 *result);
  void (__fastcall *setRot)(Actor *this, const Vec2 *);
  void (__fastcall *move)(Actor *this, IActorMovementProxy *, const Vec3 *);
  void (__fastcall *move)(Actor *this, const Vec3 *);
  Vec3 *(__fastcall *getInterpolatedRidingPosition)(Actor *this, Vec3 *result, float);
  float (__fastcall *getInterpolatedBodyRot)(Actor *this, float);
  float (__fastcall *getInterpolatedHeadRot)(Actor *this, float);
  float (__fastcall *getInterpolatedBodyYaw)(Actor *this, float);
  float (__fastcall *getYawSpeedInDegreesPerSecond)(Actor *this);
  float (__fastcall *getInterpolatedWalkAnimSpeed)(Actor *this, float);
  Vec3 *(__fastcall *getInterpolatedRidingOffset)(Actor *this, Vec3 *result, float);
  void (__fastcall *checkBlockCollisions)(Actor *this);
  void (__fastcall *checkBlockCollisions)(Actor *this, const AABB *, std::function<void __cdecl(BlockSource &,Block const &,BlockPos const &,Actor &)>);
  bool (__fastcall *isFireImmune)(Actor *this);
  bool (__fastcall *breaksFallingBlocks)(Actor *this);
  void (__fastcall *blockedByShield)(Actor *this, const ActorDamageSource *, Actor *);
  void (__fastcall *teleportTo)(Actor *this, const Vec3 *, bool, int, int, const ActorUniqueID *);
  bool (__fastcall *tryTeleportTo)(Actor *this, const Vec3 *, bool, bool, int, int);
  void (__fastcall *chorusFruitTeleport)(Actor *this, Vec3 *);
  void (__fastcall *lerpTo)(Actor *this, const Vec3 *, const Vec2 *, int);
  void (__fastcall *lerpMotion)(Actor *this, const Vec3 *);
  std::unique_ptr<AddActorBasePacket> *(__fastcall *getAddPacket)(Actor *this, std::unique_ptr<AddActorBasePacket> *result);
  void (__fastcall *normalTick)(Actor *this);
  void (__fastcall *baseTick)(Actor *this);
  void (__fastcall *rideTick)(Actor *this);
  void (__fastcall *positionRider)(Actor *this, Actor *, float);
  float (__fastcall *getRidingHeight)(Actor *this);
  bool (__fastcall *startRiding)(Actor *this, Actor *);
  void (__fastcall *addRider)(Actor *this, Actor *);
  void (__fastcall *flagRiderToRemove)(Actor *this, Actor *);
  std::string *(__fastcall *getExitTip)(Actor *this, std::string *result, const std::string *, InputMode);
  bool (__fastcall *intersects)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *, float);
  bool (__fastcall *isInWall)(Actor *this);
  bool (__fastcall *isInvisible)(Actor *this);
  bool (__fastcall *canShowNameTag)(Actor *this);
  bool (__fastcall *canExistInPeaceful)(Actor *this);
  void (__fastcall *setNameTagVisible)(Actor *this, bool);
  const std::string *(__fastcall *getNameTag)(Actor *this);
  unsigned __int64 (__fastcall *getNameTagAsHash)(Actor *this);
  std::string *(__fastcall *getFormattedNameTag)(Actor *this, std::string *result);
  void (__fastcall *filterFormattedNameTag)(Actor *this, const UIProfanityContext *);
  void (__fastcall *setNameTag)(Actor *this, const std::string *);
  bool (__fastcall *getAlwaysShowNameTag)(Actor *this);
  void (__fastcall *setScoreTag)(Actor *this, const std::string *);
  const std::string *(__fastcall *getScoreTag)(Actor *this);
  bool (__fastcall *isInWater)(Actor *this);
  bool (__fastcall *hasEnteredWater)(Actor *this);
  bool (__fastcall *isImmersedInWater)(Actor *this);
  bool (__fastcall *isInWaterOrRain)(Actor *this);
  bool (__fastcall *isInLava)(Actor *this);
  bool (__fastcall *isUnderLiquid)(Actor *this, MaterialType);
  bool (__fastcall *isOverWater)(Actor *this);
  void (__fastcall *makeStuckInBlock)(Actor *this, const Vec3 *);
  float (__fastcall *getCameraOffset)(Actor *this);
  float (__fastcall *getShadowHeightOffs)(Actor *this);
  float (__fastcall *getShadowRadius)(Actor *this);
  Vec3 *(__fastcall *getHeadLookVector)(Actor *this, Vec3 *result, float);
  bool (__fastcall *canSeeInvisible)(Actor *this);
  bool (__fastcall *canSee)(Actor *this, const Vec3 *);
  bool (__fastcall *canSee)(Actor *this, const Actor *);
  bool (__fastcall *isSkyLit)(Actor *this, float);
  float (__fastcall *getBrightness)(Actor *this, float);
  bool (__fastcall *interactPreventDefault)(Actor *this);
  void (__fastcall *playerTouch)(Actor *this, Player *);
  void (__fastcall *onAboveBubbleColumn)(Actor *this, const bool);
  void (__fastcall *onInsideBubbleColumn)(Actor *this, const bool);
  bool (__fastcall *isImmobile)(Actor *this);
  bool (__fastcall *isSilent)(Actor *this);
  bool (__fastcall *isPickable)(Actor *this);
  bool (__fastcall *isFishable)(Actor *this);
  bool (__fastcall *isSleeping)(Actor *this);
  bool (__fastcall *isShootable)(Actor *this);
  void (__fastcall *setSneaking)(Actor *this, bool);
  bool (__fastcall *isBlocking)(Actor *this);
  bool (__fastcall *isDamageBlocked)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *isAlive)(Actor *this);
  bool (__fastcall *isOnFire)(Actor *this);
  bool (__fastcall *isOnHotBlock)(Actor *this);
  bool (__fastcall *isCreativeModeAllowed)(Actor *this);
  bool (__fastcall *isSurfaceMob)(Actor *this);
  bool (__fastcall *isTargetable)(Actor *this);
  bool (__fastcall *isLocalPlayer)(Actor *this);
  bool (__fastcall *isPlayer)(Actor *this);
  bool (__fastcall *canAttack)(Actor *this, Actor *, bool);
  void (__fastcall *setTarget)(Actor *this, Actor *);
  Actor *(__fastcall *findAttackTarget)(Actor *this);
  bool (__fastcall *isValidTarget)(Actor *this, Actor *);
  bool (__fastcall *attack)(Actor *this, Actor *);
  void (__fastcall *performRangedAttack)(Actor *this, Actor *, float);
  void (__fastcall *adjustDamageAmount)(Actor *this, int *);
  int (__fastcall *getEquipmentCount)(Actor *this);
  void (__fastcall *setOwner)(Actor *this, const ActorUniqueID);
  void (__fastcall *setSitting)(Actor *this, bool);
  void (__fastcall *onTame)(Actor *this);
  void (__fastcall *onFailedTame)(Actor *this);
  int (__fastcall *getInventorySize)(Actor *this);
  int (__fastcall *getEquipSlots)(Actor *this);
  int (__fastcall *getChestSlots)(Actor *this);
  void (__fastcall *setStanding)(Actor *this, bool);
  bool (__fastcall *canPowerJump)(Actor *this);
  void (__fastcall *setCanPowerJump)(Actor *this, bool);
  bool (__fastcall *isJumping)(Actor *this);
  bool (__fastcall *isEnchanted)(Actor *this);
  void (__fastcall *rideJumped)(Actor *this);
  void (__fastcall *rideLanded)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *shouldRender)(Actor *this);
  bool (__fastcall *isInvulnerableTo)(Actor *this, const ActorDamageSource *);
  ActorDamageCause (__fastcall *getBlockDamageCause)(Actor *this, const Block *);
  void (__fastcall *actuallyHurt)(Actor *this, int, const ActorDamageSource *, bool);
  void (__fastcall *animateHurt)(Actor *this);
  bool (__fastcall *doFireHurt)(Actor *this, int);
  void (__fastcall *onLightningHit)(Actor *this);
  void (__fastcall *onBounceStarted)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *feed)(Actor *this, int);
  void (__fastcall *handleEntityEvent)(Actor *this, ActorEvent, int);
  float (__fastcall *getPickRadius)(Actor *this);
  const HashedString *(__fastcall *getActorRendererId)(Actor *this);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const ItemStack *, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int);
  void (__fastcall *despawn)(Actor *this);
  void (__fastcall *killed)(Actor *this, Actor *);
  void (__fastcall *awardKillScore)(Actor *this, Actor *, int);
  void (__fastcall *setArmor)(Actor *this, ArmorSlot, const ItemStack *);
  const ItemStack *(__fastcall *getArmor)(Actor *this, ArmorSlot);
  ArmorMaterialType (__fastcall *getArmorMaterialTypeInSlot)(Actor *this, ArmorSlot);
  ArmorTextureType (__fastcall *getArmorMaterialTextureTypeInSlot)(Actor *this, ArmorSlot);
  float (__fastcall *getArmorColorInSlot)(Actor *this, ArmorSlot, int);
  const ItemStack *(__fastcall *getEquippedSlot)(Actor *this, EquipmentSlot);
  void (__fastcall *setEquippedSlot)(Actor *this, EquipmentSlot, const ItemStack *);
  const ItemStack *(__fastcall *getCarriedItem)(Actor *this);
  void (__fastcall *setCarriedItem)(Actor *this, const ItemStack *);
  void (__fastcall *setOffhandSlot)(Actor *this, const ItemStack *);
  const ItemStack *(__fastcall *getEquippedTotem)(Actor *this);
  bool (__fastcall *consumeTotem)(Actor *this);
  bool (__fastcall *save)(Actor *this, CompoundTag *);
  void (__fastcall *saveWithoutId)(Actor *this, CompoundTag *);
  bool (__fastcall *load)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *loadLinks)(Actor *this, const CompoundTag *, std::vector<ActorLink> *, DataLoadHelper *);
  ActorType (__fastcall *getEntityTypeId)(Actor *this);
  const HashedString *(__fastcall *queryEntityRenderer)(Actor *this);
  ActorUniqueID *(__fastcall *getSourceUniqueID)(Actor *this, ActorUniqueID *result);
  void (__fastcall *setOnFire)(Actor *this, int);
  AABB *(__fastcall *getHandleWaterAABB)(Actor *this, AABB *result);
  void (__fastcall *handleInsidePortal)(Actor *this, const BlockPos *);
  int (__fastcall *getPortalCooldown)(Actor *this);
  int (__fastcall *getPortalWaitTime)(Actor *this);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(Actor *this, AutomaticID<Dimension,int> *result);
  bool (__fastcall *canChangeDimensions)(Actor *this);
  void (__fastcall *changeDimension)(Actor *this, const ChangeDimensionPacket *);
  void (__fastcall *changeDimension)(Actor *this, AutomaticID<Dimension,int>, bool);
  ActorUniqueID *(__fastcall *getControllingPlayer)(Actor *this, ActorUniqueID *result);
  void (__fastcall *checkFallDamage)(Actor *this, float, bool);
  void (__fastcall *causeFallDamage)(Actor *this, float);
  void (__fastcall *handleFallDistanceOnServer)(Actor *this, float, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, int, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, const Block *, bool);
  void (__fastcall *onSynchedDataUpdate)(Actor *this, int);
  bool (__fastcall *canAddRider)(Actor *this, Actor *);
  bool (__fastcall *canPickupItem)(Actor *this, const ItemStack *);
  bool (__fastcall *canBePulledIntoVehicle)(Actor *this);
  bool (__fastcall *inCaravan)(Actor *this);
  bool (__fastcall *isLeashableType)(Actor *this);
  void (__fastcall *tickLeash)(Actor *this);
  void (__fastcall *sendMotionPacketIfNeeded)(Actor *this);
  bool (__fastcall *canSynchronizeNewEntity)(Actor *this);
  bool (__fastcall *stopRiding)(Actor *this, bool, bool, bool, bool);
  void (__fastcall *startSwimming)(Actor *this);
  void (__fastcall *stopSwimming)(Actor *this);
  void (__fastcall *buildDebugInfo)(Actor *this, std::string *);
  CommandPermissionLevel (__fastcall *getCommandPermissionLevel)(Actor *this);
  AttributeInstance *(__fastcall *getMutableAttribute)(Actor *this, const Attribute *);
  const AttributeInstance *(__fastcall *getAttribute)(Actor *this, const Attribute *);
  int (__fastcall *getDeathTime)(Actor *this);
  void (__fastcall *heal)(Actor *this, int);
  bool (__fastcall *isInvertedHealAndHarm)(Actor *this);
  bool (__fastcall *canBeAffected)(Actor *this, const MobEffectInstance *);
  bool (__fastcall *canBeAffected)(Actor *this, int);
  bool (__fastcall *canBeAffectedByArrow)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectAdded)(Actor *this, MobEffectInstance *);
  void (__fastcall *onEffectUpdated)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectRemoved)(Actor *this, MobEffectInstance *);
  AnimationComponent *(__fastcall *getAnimationComponent)(Actor *this);
  void (__fastcall *openContainerComponent)(Actor *this, Player *);
  void (__fastcall *swing)(Actor *this);
  void (__fastcall *useItem)(Actor *this, ItemStackBase *, ItemUseMethod, bool);
  bool (__fastcall *hasOutputSignal)(Actor *this, unsigned __int8);
  int (__fastcall *getOutputSignal)(Actor *this);
  void (__fastcall *getDebugText)(Actor *this, std::vector<std::string> *);
  float (__fastcall *getMapDecorationRotation)(Actor *this);
  float (__fastcall *getRiderYRotation)(Actor *this, const Actor *);
  float (__fastcall *getYHeadRot)(Actor *this);
  bool (__fastcall *isWorldBuilder)(Actor *this);
  bool (__fastcall *isCreative)(Actor *this);
  bool (__fastcall *isAdventure)(Actor *this);
  bool (__fastcall *add)(Actor *this, ItemStack *);
  bool (__fastcall *drop)(Actor *this, const ItemStack *, bool);
  bool (__fastcall *getInteraction)(Actor *this, Player *, ActorInteraction *, const Vec3 *);
  bool (__fastcall *canDestroyBlock)(Actor *this, const Block *);
  void (__fastcall *setAuxValue)(Actor *this, int);
  void (__fastcall *setSize)(Actor *this, float, float);
  int (__fastcall *getLifeSpan)(Actor *this);
  void (__fastcall *onOrphan)(Actor *this);
  void (__fastcall *wobble)(Actor *this);
  bool (__fastcall *wasHurt)(Actor *this);
  void (__fastcall *startSpinAttack)(Actor *this);
  void (__fastcall *stopSpinAttack)(Actor *this);
  void (__fastcall *setDamageNearbyMobs)(Actor *this, bool);
  bool (__fastcall *hasCritBox)(Actor *this);
  bool (__fastcall *isCritHit)(Actor *this);
  void (__fastcall *renderDebugServerState)(Actor *this, const Options *);
  void (__fastcall *reloadLootTable)(Actor *this, const EquipmentTableDefinition *);
  void (__fastcall *reloadLootTable)(Actor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(Actor *this);
  void (__fastcall *kill)(Actor *this);
  void (__fastcall *die)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *shouldTick)(Actor *this);
  std::shared_ptr<IActorMovementProxy> *(__fastcall *createMovementProxy)(Actor *this, std::shared_ptr<IActorMovementProxy> *result);
  void (__fastcall *updateEntitySpecificMolangVariables)(Actor *this, RenderParams *);
  bool (__fastcall *shouldTryMakeStepSound)(Actor *this);
  float (__fastcall *getNextStep)(Actor *this, const float);
  bool (__fastcall *canMakeStepSound)(Actor *this);
  void (__fastcall *outOfWorld)(Actor *this);
  bool (__fastcall *_hurt)(Actor *this, const ActorDamageSource *, int, bool, bool);
  void (__fastcall *markHurt)(Actor *this);
  void (__fastcall *readAdditionalSaveData)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *addAdditionalSaveData)(Actor *this, CompoundTag *);
  void (__fastcall *_playStepSound)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *_playFlySound)(Actor *this, const BlockPos *, const Block *);
  bool (__fastcall *_makeFlySound)(Actor *this);
  void (__fastcall *checkInsideBlocks)(Actor *this, float);
  void (__fastcall *pushOutOfBlocks)(Actor *this, const Vec3 *);
  bool (__fastcall *updateWaterState)(Actor *this);
  void (__fastcall *doWaterSplashEffect)(Actor *this);
  void (__fastcall *spawnTrailBubbles)(Actor *this);
  void (__fastcall *updateInsideBlock)(Actor *this);
  LootTable *(__fastcall *getLootTable)(Actor *this);
  LootTable *(__fastcall *getDefaultLootTable)(Actor *this);
  void (__fastcall *_removeRider)(Actor *this, const ActorUniqueID *, bool, bool, bool);
  void (__fastcall *_onSizeUpdated)(Actor *this);
  void (__fastcall *_doAutoAttackOnTouch)(Actor *this, Actor *);
};

```

### `PrimedTnt`
```
struct __cppobj __declspec(align(8)) PrimedTnt : PredictableProjectile
{
  ActorUniqueID mOwnerID;
  ActorType mOwnerEntityType;
};

```

### `PrimedTnt_vtbl`
```
struct /*VFT*/ PrimedTnt_vtbl
{
  bool (__fastcall *hasComponent)(Actor *this, const HashedString *);
  void (__fastcall *reloadHardcoded)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadHardcodedClient)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *initializeComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *reloadComponents)(Actor *this, Actor::InitializationMethod, const VariantParameterList *);
  void (__fastcall *_serverInitItemStackIds)(Actor *this);
  void (__fastcall *_doInitialMove)(Actor *this);
  bool (__fastcall *checkAllSensitiveWords)(Actor *this);
  bool (__fastcall *checkNameTag)(Actor *this);
  void (__fastcall *~Actor)(Actor *this);
  void (__fastcall *reset)(Actor *this);
  int (__fastcall *getOnDeathExperience)(Actor *this);
  ActorType (__fastcall *getOwnerEntityType)(Actor *this);
  void (__fastcall *remove)(Actor *this);
  void (__fastcall *setPos)(Actor *this, const Vec3 *);
  const PredictedMovementValues *(__fastcall *getPredictedMovementValues)(Actor *this);
  const Vec3 *(__fastcall *getPos)(Actor *this);
  const Vec3 *(__fastcall *getPosOld)(Actor *this);
  const Vec3 *(__fastcall *getPosExtrapolated)(Actor *this, const Vec3 *result, float);
  Vec3 *(__fastcall *getAttachPos)(Actor *this, Vec3 *result, ActorLocation, float);
  Vec3 *(__fastcall *getFiringPos)(Actor *this, Vec3 *result);
  void (__fastcall *setRot)(Actor *this, const Vec2 *);
  void (__fastcall *move)(Actor *this, IActorMovementProxy *, const Vec3 *);
  void (__fastcall *move)(Actor *this, const Vec3 *);
  Vec3 *(__fastcall *getInterpolatedRidingPosition)(Actor *this, Vec3 *result, float);
  float (__fastcall *getInterpolatedBodyRot)(Actor *this, float);
  float (__fastcall *getInterpolatedHeadRot)(Actor *this, float);
  float (__fastcall *getInterpolatedBodyYaw)(Actor *this, float);
  float (__fastcall *getYawSpeedInDegreesPerSecond)(Actor *this);
  float (__fastcall *getInterpolatedWalkAnimSpeed)(Actor *this, float);
  Vec3 *(__fastcall *getInterpolatedRidingOffset)(Actor *this, Vec3 *result, float);
  void (__fastcall *checkBlockCollisions)(Actor *this);
  void (__fastcall *checkBlockCollisions)(Actor *this, const AABB *, std::function<void __cdecl(BlockSource &,Block const &,BlockPos const &,Actor &)>);
  bool (__fastcall *isFireImmune)(Actor *this);
  bool (__fastcall *breaksFallingBlocks)(Actor *this);
  void (__fastcall *blockedByShield)(Actor *this, const ActorDamageSource *, Actor *);
  void (__fastcall *teleportTo)(Actor *this, const Vec3 *, bool, int, int, const ActorUniqueID *);
  bool (__fastcall *tryTeleportTo)(Actor *this, const Vec3 *, bool, bool, int, int);
  void (__fastcall *chorusFruitTeleport)(Actor *this, Vec3 *);
  void (__fastcall *lerpTo)(Actor *this, const Vec3 *, const Vec2 *, int);
  void (__fastcall *lerpMotion)(Actor *this, const Vec3 *);
  std::unique_ptr<AddActorBasePacket> *(__fastcall *getAddPacket)(Actor *this, std::unique_ptr<AddActorBasePacket> *result);
  void (__fastcall *normalTick)(Actor *this);
  void (__fastcall *baseTick)(Actor *this);
  void (__fastcall *rideTick)(Actor *this);
  void (__fastcall *positionRider)(Actor *this, Actor *, float);
  float (__fastcall *getRidingHeight)(Actor *this);
  bool (__fastcall *startRiding)(Actor *this, Actor *);
  void (__fastcall *addRider)(Actor *this, Actor *);
  void (__fastcall *flagRiderToRemove)(Actor *this, Actor *);
  std::string *(__fastcall *getExitTip)(Actor *this, std::string *result, const std::string *, InputMode);
  bool (__fastcall *intersects)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *);
  bool (__fastcall *isFree)(Actor *this, const Vec3 *, float);
  bool (__fastcall *isInWall)(Actor *this);
  bool (__fastcall *isInvisible)(Actor *this);
  bool (__fastcall *canShowNameTag)(Actor *this);
  bool (__fastcall *canExistInPeaceful)(Actor *this);
  void (__fastcall *setNameTagVisible)(Actor *this, bool);
  const std::string *(__fastcall *getNameTag)(Actor *this);
  unsigned __int64 (__fastcall *getNameTagAsHash)(Actor *this);
  std::string *(__fastcall *getFormattedNameTag)(Actor *this, std::string *result);
  void (__fastcall *filterFormattedNameTag)(Actor *this, const UIProfanityContext *);
  void (__fastcall *setNameTag)(Actor *this, const std::string *);
  bool (__fastcall *getAlwaysShowNameTag)(Actor *this);
  void (__fastcall *setScoreTag)(Actor *this, const std::string *);
  const std::string *(__fastcall *getScoreTag)(Actor *this);
  bool (__fastcall *isInWater)(Actor *this);
  bool (__fastcall *hasEnteredWater)(Actor *this);
  bool (__fastcall *isImmersedInWater)(Actor *this);
  bool (__fastcall *isInWaterOrRain)(Actor *this);
  bool (__fastcall *isInLava)(Actor *this);
  bool (__fastcall *isUnderLiquid)(Actor *this, MaterialType);
  bool (__fastcall *isOverWater)(Actor *this);
  void (__fastcall *makeStuckInBlock)(Actor *this, const Vec3 *);
  float (__fastcall *getCameraOffset)(Actor *this);
  float (__fastcall *getShadowHeightOffs)(Actor *this);
  float (__fastcall *getShadowRadius)(Actor *this);
  Vec3 *(__fastcall *getHeadLookVector)(Actor *this, Vec3 *result, float);
  bool (__fastcall *canSeeInvisible)(Actor *this);
  bool (__fastcall *canSee)(Actor *this, const Vec3 *);
  bool (__fastcall *canSee)(Actor *this, const Actor *);
  bool (__fastcall *isSkyLit)(Actor *this, float);
  float (__fastcall *getBrightness)(Actor *this, float);
  bool (__fastcall *interactPreventDefault)(Actor *this);
  void (__fastcall *playerTouch)(Actor *this, Player *);
  void (__fastcall *onAboveBubbleColumn)(Actor *this, const bool);
  void (__fastcall *onInsideBubbleColumn)(Actor *this, const bool);
  bool (__fastcall *isImmobile)(Actor *this);
  bool (__fastcall *isSilent)(Actor *this);
  bool (__fastcall *isPickable)(Actor *this);
  bool (__fastcall *isFishable)(Actor *this);
  bool (__fastcall *isSleeping)(Actor *this);
  bool (__fastcall *isShootable)(Actor *this);
  void (__fastcall *setSneaking)(Actor *this, bool);
  bool (__fastcall *isBlocking)(Actor *this);
  bool (__fastcall *isDamageBlocked)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *isAlive)(Actor *this);
  bool (__fastcall *isOnFire)(Actor *this);
  bool (__fastcall *isOnHotBlock)(Actor *this);
  bool (__fastcall *isCreativeModeAllowed)(Actor *this);
  bool (__fastcall *isSurfaceMob)(Actor *this);
  bool (__fastcall *isTargetable)(Actor *this);
  bool (__fastcall *isLocalPlayer)(Actor *this);
  bool (__fastcall *isPlayer)(Actor *this);
  bool (__fastcall *canAttack)(Actor *this, Actor *, bool);
  void (__fastcall *setTarget)(Actor *this, Actor *);
  Actor *(__fastcall *findAttackTarget)(Actor *this);
  bool (__fastcall *isValidTarget)(Actor *this, Actor *);
  bool (__fastcall *attack)(Actor *this, Actor *);
  void (__fastcall *performRangedAttack)(Actor *this, Actor *, float);
  void (__fastcall *adjustDamageAmount)(Actor *this, int *);
  int (__fastcall *getEquipmentCount)(Actor *this);
  void (__fastcall *setOwner)(Actor *this, const ActorUniqueID);
  void (__fastcall *setSitting)(Actor *this, bool);
  void (__fastcall *onTame)(Actor *this);
  void (__fastcall *onFailedTame)(Actor *this);
  int (__fastcall *getInventorySize)(Actor *this);
  int (__fastcall *getEquipSlots)(Actor *this);
  int (__fastcall *getChestSlots)(Actor *this);
  void (__fastcall *setStanding)(Actor *this, bool);
  bool (__fastcall *canPowerJump)(Actor *this);
  void (__fastcall *setCanPowerJump)(Actor *this, bool);
  bool (__fastcall *isJumping)(Actor *this);
  bool (__fastcall *isEnchanted)(Actor *this);
  void (__fastcall *rideJumped)(Actor *this);
  void (__fastcall *rideLanded)(Actor *this, const Vec3 *, const Vec3 *);
  bool (__fastcall *shouldRender)(Actor *this);
  bool (__fastcall *isInvulnerableTo)(Actor *this, const ActorDamageSource *);
  ActorDamageCause (__fastcall *getBlockDamageCause)(Actor *this, const Block *);
  void (__fastcall *actuallyHurt)(Actor *this, int, const ActorDamageSource *, bool);
  void (__fastcall *animateHurt)(Actor *this);
  bool (__fastcall *doFireHurt)(Actor *this, int);
  void (__fastcall *onLightningHit)(Actor *this);
  void (__fastcall *onBounceStarted)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *feed)(Actor *this, int);
  void (__fastcall *handleEntityEvent)(Actor *this, ActorEvent, int);
  float (__fastcall *getPickRadius)(Actor *this);
  const HashedString *(__fastcall *getActorRendererId)(Actor *this);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const ItemStack *, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, const Block *, int);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int, float);
  ItemActor *(__fastcall *spawnAtLocation)(Actor *this, int, int);
  void (__fastcall *despawn)(Actor *this);
  void (__fastcall *killed)(Actor *this, Actor *);
  void (__fastcall *awardKillScore)(Actor *this, Actor *, int);
  void (__fastcall *setArmor)(Actor *this, ArmorSlot, const ItemStack *);
  const ItemStack *(__fastcall *getArmor)(Actor *this, ArmorSlot);
  ArmorMaterialType (__fastcall *getArmorMaterialTypeInSlot)(Actor *this, ArmorSlot);
  ArmorTextureType (__fastcall *getArmorMaterialTextureTypeInSlot)(Actor *this, ArmorSlot);
  float (__fastcall *getArmorColorInSlot)(Actor *this, ArmorSlot, int);
  const ItemStack *(__fastcall *getEquippedSlot)(Actor *this, EquipmentSlot);
  void (__fastcall *setEquippedSlot)(Actor *this, EquipmentSlot, const ItemStack *);
  const ItemStack *(__fastcall *getCarriedItem)(Actor *this);
  void (__fastcall *setCarriedItem)(Actor *this, const ItemStack *);
  void (__fastcall *setOffhandSlot)(Actor *this, const ItemStack *);
  const ItemStack *(__fastcall *getEquippedTotem)(Actor *this);
  bool (__fastcall *consumeTotem)(Actor *this);
  bool (__fastcall *save)(Actor *this, CompoundTag *);
  void (__fastcall *saveWithoutId)(Actor *this, CompoundTag *);
  bool (__fastcall *load)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *loadLinks)(Actor *this, const CompoundTag *, std::vector<ActorLink> *, DataLoadHelper *);
  ActorType (__fastcall *getEntityTypeId)(Actor *this);
  const HashedString *(__fastcall *queryEntityRenderer)(Actor *this);
  ActorUniqueID *(__fastcall *getSourceUniqueID)(Actor *this, ActorUniqueID *result);
  void (__fastcall *setOnFire)(Actor *this, int);
  AABB *(__fastcall *getHandleWaterAABB)(Actor *this, AABB *result);
  void (__fastcall *handleInsidePortal)(Actor *this, const BlockPos *);
  int (__fastcall *getPortalCooldown)(Actor *this);
  int (__fastcall *getPortalWaitTime)(Actor *this);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(Actor *this, AutomaticID<Dimension,int> *result);
  bool (__fastcall *canChangeDimensions)(Actor *this);
  void (__fastcall *changeDimension)(Actor *this, const ChangeDimensionPacket *);
  void (__fastcall *changeDimension)(Actor *this, AutomaticID<Dimension,int>, bool);
  ActorUniqueID *(__fastcall *getControllingPlayer)(Actor *this, ActorUniqueID *result);
  void (__fastcall *checkFallDamage)(Actor *this, float, bool);
  void (__fastcall *causeFallDamage)(Actor *this, float);
  void (__fastcall *handleFallDistanceOnServer)(Actor *this, float, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, int, bool);
  void (__fastcall *playSynchronizedSound)(Actor *this, LevelSoundEvent, const Vec3 *, const Block *, bool);
  void (__fastcall *onSynchedDataUpdate)(Actor *this, int);
  bool (__fastcall *canAddRider)(Actor *this, Actor *);
  bool (__fastcall *canPickupItem)(Actor *this, const ItemStack *);
  bool (__fastcall *canBePulledIntoVehicle)(Actor *this);
  bool (__fastcall *inCaravan)(Actor *this);
  bool (__fastcall *isLeashableType)(Actor *this);
  void (__fastcall *tickLeash)(Actor *this);
  void (__fastcall *sendMotionPacketIfNeeded)(Actor *this);
  bool (__fastcall *canSynchronizeNewEntity)(Actor *this);
  bool (__fastcall *stopRiding)(Actor *this, bool, bool, bool, bool);
  void (__fastcall *startSwimming)(Actor *this);
  void (__fastcall *stopSwimming)(Actor *this);
  void (__fastcall *buildDebugInfo)(Actor *this, std::string *);
  CommandPermissionLevel (__fastcall *getCommandPermissionLevel)(Actor *this);
  AttributeInstance *(__fastcall *getMutableAttribute)(Actor *this, const Attribute *);
  const AttributeInstance *(__fastcall *getAttribute)(Actor *this, const Attribute *);
  int (__fastcall *getDeathTime)(Actor *this);
  void (__fastcall *heal)(Actor *this, int);
  bool (__fastcall *isInvertedHealAndHarm)(Actor *this);
  bool (__fastcall *canBeAffected)(Actor *this, const MobEffectInstance *);
  bool (__fastcall *canBeAffected)(Actor *this, int);
  bool (__fastcall *canBeAffectedByArrow)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectAdded)(Actor *this, MobEffectInstance *);
  void (__fastcall *onEffectUpdated)(Actor *this, const MobEffectInstance *);
  void (__fastcall *onEffectRemoved)(Actor *this, MobEffectInstance *);
  AnimationComponent *(__fastcall *getAnimationComponent)(Actor *this);
  void (__fastcall *openContainerComponent)(Actor *this, Player *);
  void (__fastcall *swing)(Actor *this);
  void (__fastcall *useItem)(Actor *this, ItemStackBase *, ItemUseMethod, bool);
  bool (__fastcall *hasOutputSignal)(Actor *this, unsigned __int8);
  int (__fastcall *getOutputSignal)(Actor *this);
  void (__fastcall *getDebugText)(Actor *this, std::vector<std::string> *);
  float (__fastcall *getMapDecorationRotation)(Actor *this);
  float (__fastcall *getRiderYRotation)(Actor *this, const Actor *);
  float (__fastcall *getYHeadRot)(Actor *this);
  bool (__fastcall *isWorldBuilder)(Actor *this);
  bool (__fastcall *isCreative)(Actor *this);
  bool (__fastcall *isAdventure)(Actor *this);
  bool (__fastcall *add)(Actor *this, ItemStack *);
  bool (__fastcall *drop)(Actor *this, const ItemStack *, bool);
  bool (__fastcall *getInteraction)(Actor *this, Player *, ActorInteraction *, const Vec3 *);
  bool (__fastcall *canDestroyBlock)(Actor *this, const Block *);
  void (__fastcall *setAuxValue)(Actor *this, int);
  void (__fastcall *setSize)(Actor *this, float, float);
  int (__fastcall *getLifeSpan)(Actor *this);
  void (__fastcall *onOrphan)(Actor *this);
  void (__fastcall *wobble)(Actor *this);
  bool (__fastcall *wasHurt)(Actor *this);
  void (__fastcall *startSpinAttack)(Actor *this);
  void (__fastcall *stopSpinAttack)(Actor *this);
  void (__fastcall *setDamageNearbyMobs)(Actor *this, bool);
  bool (__fastcall *hasCritBox)(Actor *this);
  bool (__fastcall *isCritHit)(Actor *this);
  void (__fastcall *renderDebugServerState)(Actor *this, const Options *);
  void (__fastcall *reloadLootTable)(Actor *this, const EquipmentTableDefinition *);
  void (__fastcall *reloadLootTable)(Actor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(Actor *this);
  void (__fastcall *kill)(Actor *this);
  void (__fastcall *die)(Actor *this, const ActorDamageSource *);
  bool (__fastcall *shouldTick)(Actor *this);
  std::shared_ptr<IActorMovementProxy> *(__fastcall *createMovementProxy)(Actor *this, std::shared_ptr<IActorMovementProxy> *result);
  void (__fastcall *updateEntitySpecificMolangVariables)(Actor *this, RenderParams *);
  bool (__fastcall *shouldTryMakeStepSound)(Actor *this);
  float (__fastcall *getNextStep)(Actor *this, const float);
  bool (__fastcall *canMakeStepSound)(Actor *this);
  void (__fastcall *outOfWorld)(Actor *this);
  bool (__fastcall *_hurt)(Actor *this, const ActorDamageSource *, int, bool, bool);
  void (__fastcall *markHurt)(Actor *this);
  void (__fastcall *readAdditionalSaveData)(Actor *this, const CompoundTag *, DataLoadHelper *);
  void (__fastcall *addAdditionalSaveData)(Actor *this, CompoundTag *);
  void (__fastcall *_playStepSound)(Actor *this, const BlockPos *, const Block *);
  void (__fastcall *_playFlySound)(Actor *this, const BlockPos *, const Block *);
  bool (__fastcall *_makeFlySound)(Actor *this);
  void (__fastcall *checkInsideBlocks)(Actor *this, float);
  void (__fastcall *pushOutOfBlocks)(Actor *this, const Vec3 *);
  bool (__fastcall *updateWaterState)(Actor *this);
  void (__fastcall *doWaterSplashEffect)(Actor *this);
  void (__fastcall *spawnTrailBubbles)(Actor *this);
  void (__fastcall *updateInsideBlock)(Actor *this);
  LootTable *(__fastcall *getLootTable)(Actor *this);
  LootTable *(__fastcall *getDefaultLootTable)(Actor *this);
  void (__fastcall *_removeRider)(Actor *this, const ActorUniqueID *, bool, bool, bool);
  void (__fastcall *_onSizeUpdated)(Actor *this);
  void (__fastcall *_doAutoAttackOnTouch)(Actor *this, Actor *);
};

```

