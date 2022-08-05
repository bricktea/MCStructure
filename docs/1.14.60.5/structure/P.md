# P
### `ProfilerLite::ScopedData`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mName
8 | (4) `ProfilerLite::ScopeTag` | mScope
12 | (4) `ProfilerLite::ScopeTag` | mBaseScope
16 | (8) `ProfilerLite::ScopedData *` | mParent
24 | (4) `int` | mTabCount
32 | (24) `std::vector<ProfilerLite::ScopedData *>` | mChildren
56 | (4) `int` | mHitCount
64 | (8) `double` | mTotalTime
72 | (8) `double` | mTotalInclusiveTime
80 | (8) `double` | mMaxTimePerLoop


### `PropertiesSettings`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mLevelSeed
32 | (32) `std::string` | mLevelName
64 | (32) `std::string` | mLevelType
96 | (32) `std::string` | mServerName
128 | (40) `NetworkAddress` | mRemoteServerCommunicationEndpoint
168 | (40) `NetworkAddress` | mClacksEndpoint
208 | (2) `uint16_t` | mServerPort
210 | (2) `uint16_t` | mServerPortv6
212 | (4) `int` | mMaxPlayers
216 | (4) `int` | mOpPermissionLevel
224 | (32) `std::string` | mDifficulty
256 | (32) `std::string` | mServerType
288 | (32) `std::string` | mGameMode
320 | (32) `std::string` | mLanguage
352 | (32) `std::string` | mServerId
384 | (4) `uint32_t` | mMaxThreads
388 | (4) `int` | mServerTickRange
392 | (24) `std::vector<std::string>` | mExtraTrustedKeys
416 | (1) `bool` | mUseWhitelist
417 | (1) `bool` | mIsOnlineMode
418 | (1) `bool` | mForceGameMode
419 | (1) `bool` | mAllowCheats
420 | (1) `bool` | mTexturePackRequired
421 | (1) `bool` | mUseMsaGamertagsOnly
422 | (1) `bool` | mIsContentLogFileEnabled
424 | (4) `int` | mMaxViewDistanceChunks
432 | (8) `std::chrono::minutes` | mMaxIdleTime
440 | (32) `std::string` | mDefaultPlayerPermissionLevel
472 | (4) `int` | mServerWakeupFrequency
476 | (1) `bool` | mServerAuthoritativeMovement
480 | (4) `float` | mPlayerMovementDistanceThreshold
488 | (8) `std::chrono::milliseconds` | mPlayerMovementDurationThreshold
496 | (4) `float` | mPlayerMovementScoreThreshold
500 | (1) `bool` | mShouldCorrectPlayerMovement
504 | (4) `float` | mWebsocketRetryTime
508 | (1) `bool` | mUseWebsocketEncryption
510 | (2) `uint16_t` | mCompressionThreshold
512 | (56) `std::unordered_map<std::string,std::string>` | mCustomProperties


### `PackManifestFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `IPackTelemetry *` | mEventing


### `PackSourceFactory`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<ContentCatalogPackSource>>` | mContentCatalogPackSources
24 | (24) `std::vector<std::unique_ptr<TreatmentPackSource>>` | mTreatmentPackSources
48 | (24) `std::vector<std::unique_ptr<DirectoryPackSource>>` | mDirectoryPackSources
72 | (24) `std::vector<std::unique_ptr<InPackagePackSource>>` | mInPackagePackSources
96 | (24) `std::vector<std::unique_ptr<WorldHistoryPackSource>>` | mWorldHistoryPackSources
120 | (24) `std::vector<std::unique_ptr<WorldTemplatePackSource>>` | mWorldTemplatePackSources
144 | (16) `PackSourceFactory::RealmsUnknownPackSources` | mRealmsUnknownPackSources
160 | (16) `std::shared_ptr<IInPackagePacks>` | mInPackagePacksProvider


### `PackSourceFactory::RealmsUnknownPackSources`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<RealmsUnknownPackSource>` | realmsUnknownResourcePackSource
8 | (8) `std::unique_ptr<RealmsUnknownPackSource>` | realmsUnknownBehaviorPackSource


### `PackManifest`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$PackManifest
8 | (56) `ResourceLocation` | mLocation
64 | (136) `PackIdVersion` | mIdentity
200 | (24) `ContentIdentity` | mContentIdentity
224 | (112) `SemVersion` | mMinEngineVersion
336 | (112) `BaseGameVersion` | mRequiredBaseGameVersion
448 | (56) `std::unordered_set<std::string>` | mCapabilities
504 | (56) `std::unordered_set<std::string>` | mTrustedCapabilities
560 | (32) `std::string` | mName
592 | (32) `std::string` | mDescription
624 | (1) `bool` | mExpired
632 | (56) `ResourceLocation` | mPackIconLocation
688 | (24) `std::vector<ResourceInformation>` | mModules
712 | (24) `std::vector<PackIdVersion>` | mPackDependencies
736 | (24) `std::vector<LegacyPackIdVersion>` | mLegacyModuleDependencies
760 | (16) `Json::Value` | mSettings
776 | (88) `ResourceMetadata` | mMetadata
864 | (1) `PackType` | mPackType
868 | (4) `PackCategory` | mPackCategory
872 | (4) `PackOrigin` | mPackOrigin
876 | (1) `ManifestOrigin` | mManifestOrigin
877 | (1) `ManifestType` | mManifestType
878 | (1) `bool` | mIsHidden
880 | (8) `uint64_t` | mSize
888 | (32) `std::string` | mLastModifiedDate
920 | (1) `bool` | mHasValidUUID
921 | (1) `bool` | mHasPlugins
922 | (1) `bool` | mHasClientData
923 | (1) `bool` | mHasEducationMetadata
924 | (1) `bool` | mIsPlatformLocked
925 | (1) `bool` | mIsTitleLocked
926 | (1) `bool` | mCanUseTrustedPackCapabilities
927 | (1) `TemplateLockState` | mTemplateOptionLockState
928 | (1) `PackScope` | mScope
936 | (24) `ContentIdentity` | mSourceIdentity
960 | (24) `std::vector<std::string>` | mLanguageCodesForPackKeywords
984 | (4) `PackManifest::PackRedownloadableState` | mPackRedownloadableState
988 | (1) `PackManifestFormat` | mFormatVersion
989 | (1) `PackManifestFormat` | mOriginalFormatVersion


### `PackIdVersion`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mId
16 | (112) `SemVersion` | mVersion
128 | (1) `PackType` | mPackType


### `Packet:288`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Packet
8 | (4) `PacketPriority` | mPriority
12 | (4) `NetworkPeer::Reliability` | mReliability
16 | (1) `SubClientId` | mClientSubId
17 | (7) `_BYTE[7]` | gap11
24 | (8) `const IPacketHandlerDispatcher *` | mHandler
32 | (4) `Compressibility` | mCompressible


### `Packet`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Packet
8 | (4) `PacketPriority` | mPriority
12 | (4) `NetworkPeer::Reliability` | mReliability
16 | (1) `SubClientId` | mClientSubId
24 | (8) `const IPacketHandlerDispatcher *` | mHandler
32 | (4) `Compressibility` | mCompressible


### `PostprocessingManager::Owns`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos` | mPosition
8 | (8) `PostprocessingManager *` | mPpm


### `PropertyList`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<std::string,Social::Events::Property>::_Hashtable` | _M_h


### `PeekComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHadTarget
4 | (4) `int` | mDuration


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
104 | (96) `HitResult` | mHitResult
200 | (1) `FacingID` | mHitFacing
201 | (1) `bool` | mReflect
204 | (4) `float` | mPower
208 | (4) `float` | mDamage
212 | (12) `Vec3` | mOffset
224 | (4) `ParticleType` | mHitParticle
228 | (4) `float` | mGravity
232 | (4) `float` | mUpwardsAngleOffset
240 | (24) `std::vector<OnHitSubcomponent *>` | mOnHitCommands
264 | (128) `DefinitionTrigger` | mOnHitEvent
392 | (4) `float` | mUncertaintyBase
396 | (4) `float` | mUncertaintyMultiplier
400 | (4) `ActorType` | mFilterType
404 | (4) `float` | mOnFireTime
408 | (4) `int` | mPotionEffect
412 | (4) `float` | mSplashRange
416 | (1) `bool` | mKnockback
420 | (4) `float` | mKnockbackForce
424 | (1) `bool` | mCatchFire
425 | (1) `bool` | mChanneling
426 | (1) `bool` | mIsSplash
428 | (4) `float` | mInertiaMod
432 | (4) `float` | mLiquidInertia
436 | (1) `bool` | mSemiRandomDiffDamage
440 | (4) `ProjectileAnchor` | mSpawnPosAnchor
444 | (4) `LevelSoundEvent` | mHitEntitySound
448 | (4) `LevelSoundEvent` | mHitGroundSound
452 | (4) `LevelSoundEvent` | mShootSound
456 | (1) `bool` | mIsDangerous
457 | (1) `bool` | mShootTarget
458 | (1) `bool` | mDamageOwner
459 | (1) `bool` | mReflectOnHurt
460 | (1) `bool` | mDestroyOnHurt
461 | (1) `bool` | mStopOnHit
462 | (1) `bool` | mCritParticleOnHurt
463 | (1) `bool` | mHitWater
464 | (1) `bool` | mHitActor
465 | (1) `bool` | mMultipleHits
468 | (4) `int` | mPiercingEnchantLevel
472 | (4) `int` | mActorHitCount
476 | (1) `bool` | mIsHoming
480 | (8) `ActorUniqueID` | mPendingTargetID
488 | (8) `Actor *` | mTarget
496 | (8) `ActorUniqueID` | mTargetID
504 | (12) `Vec3` | mTargetDelta
516 | (4) `int` | mFlightSteps
520 | (4) `ProjectileComponent::EAxis` | mCurrentMoveDirection
524 | (1) `bool` | mShouldBounce
528 | (4) `unsigned int` | mCurrentDelay
532 | (1) `bool` | mWaitingForServer
533 | (1) `bool` | mWaitingForServerHitGround
536 | (96) `HitResult` | mCachedHitResult
632 | (1) `bool` | mDelayOneFrame


### `PacketHeader`
Offset | Type | Name
-|-|-|-
0 | (4) `PacketHeader::$1CBC6A59FA6FE466C7E4A934B3AAA5AD` | mData


### `PacketHeader::$1CBC6A59FA6FE466C7E4A934B3AAA5AD`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mRaw
1 | (4) `PacketHeader::$1CBC6A59FA6FE466C7E4A934B3AAA5AD::$51D560F567CE4629B2B28E9C1CA63A03` | mBits


### `PacketHeader::$1CBC6A59FA6FE466C7E4A934B3AAA5AD::$51D560F567CE4629B2B28E9C1CA63A03`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | _bf_0


### `PacketHandlerDispatcherInstance<LoginPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayStatusPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ServerToClientHandshakePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientToServerHandshakePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientCacheStatusPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientCacheBlobStatusPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientCacheMissResponsePacket,true>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePacksInfoPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackStackPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackClientResponsePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<DisconnectPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetTimePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<TextPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<StartGamePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddActorPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddEntityPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddItemActorPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<TakeItemActorPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddPlayerPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MoveActorAbsolutePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MoveActorDeltaPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MovePlayerPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RiderJumpPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RespawnPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RemoveActorPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RemoveEntityPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateBlockPacket,true>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateBlockSyncedPacket,true>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SpawnParticleEffectPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelSoundEventPacketV2,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelSoundEventPacketV1,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelSoundEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelEventGenericPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockPickRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ActorPickRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<GuiDataPickItemPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ActorEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MobEffectPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MobEquipmentPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MobArmorEquipmentPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<InteractPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerActionPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ActorFallPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<HurtArmorPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorDataPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorMotionPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetHealthPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetSpawnPositionPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AnimatePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<InventoryTransactionPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ItemFrameDropItemPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerOpenPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerClosePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ContainerSetDataPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerHotbarPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<InventoryContentPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<InventorySlotPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CraftingDataPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CraftingEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddPaintingPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AdventureSettingsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetActorLinkPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BlockActorDataPacket,true>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerInputPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerAuthInputPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LevelChunkPacket,true>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetCommandsEnabledPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDifficultyPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ChangeDimensionPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetPlayerGameTypePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDefaultGameTypePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateAttributesPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerListPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SimpleEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<EventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SpawnExperienceOrbPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RequestChunkRadiusPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ChunkRadiusUpdatedPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ClientboundMapItemDataPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MapCreateLockedCopyPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MapInfoRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateTradePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateEquipPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BossEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AvailableCommandsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandOutputPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CommandBlockUpdatePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CameraPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<GameRulesChangedPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowCreditsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackDataInfoPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackChunkDataPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ResourcePackChunkRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkChunkPublisherUpdatePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureBlockUpdatePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureTemplateDataRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<StructureTemplateDataResponsePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<TransferPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AddBehaviorTreePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetTitlePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlaySoundPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<StopSoundPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowStoreOfferPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<RemoveObjectivePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetDisplayObjectivePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PurchaseReceiptPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PlayerSkinPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetScorePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetScoreboardIdentityPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SubClientLoginPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetLastHurtByPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BookEditPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<NpcRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AutomationClientConnectPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<VideoStreamConnectPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ModalFormRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ModalFormResponsePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<OnScreenTextureAnimationPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ServerSettingsRequestPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ServerSettingsResponsePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<PhotoTransferPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ShowProfilePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LabTablePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkStackLatencyPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateSoftEnumPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SetLocalPlayerAsInitializedPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<ScriptCustomEventPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<BiomeDefinitionListPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AvailableActorIdentifiersPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<LecternUpdatePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<UpdateBlockPropertiesPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<EducationSettingsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<SettingsCommandPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<EmotePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<MultiplayerSettingsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<AnvilDamagePacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<TickSyncPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<NetworkSettingsPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


### `PacketHandlerDispatcherInstance<CompletedUsingItemPacket,false>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0


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
280 | (4) `RakNet::TimeMS` | pingTime
284 | (4) `float` | pingLatency
288 | (16) `RakNet::RakNetGUID` | hostGuid


### `PlayerStorageIds`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | MsaId
32 | (32) `std::string` | PlatformId
64 | (32) `std::string` | PlatformOnlineId
96 | (32) `std::string` | PlatformOfflineId
128 | (32) `std::string` | SelfSignedId
160 | (32) `std::string` | RandomClientId


### `PlayerListPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<PlayerListEntry>` | mEntries
64 | (1) `PlayerListPacketType` | mAction


### `PotionMixDataEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | fromPotionId
4 | (4) `int` | reagentItemId
8 | (4) `int` | toPotionId


### `PlayerHotbarPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `uint32_t` | mSelectedSlot
40 | (1) `bool` | mShouldSelectSlot
41 | (1) `ContainerID` | mContainerId


### `PlayerSkinPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (16) `mce::UUID` | mUUID
56 | (448) `SerializedSkin` | mSkin
504 | (32) `std::string` | mLocalizedNewSkinName
536 | (32) `std::string` | mLocalizedOldSkinName


### `PageContent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mText
32 | (32) `std::string` | mParsedText
64 | (32) `std::string` | mPhotoName


### `PlayerListEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mId
8 | (16) `mce::UUID` | mUUID
24 | (32) `std::string` | mName
56 | (32) `std::string` | mXUID
88 | (32) `std::string` | mPlatformOnlineId
120 | (4) `BuildPlatform` | mBuildPlatform
128 | (448) `SerializedSkin` | mSkin
576 | (1) `bool` | mIsTeacher
577 | (1) `bool` | mIsHost


### `PackInstanceId`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mPackId
136 | (32) `std::string` | mSubpackName


### `PlayerScoreboardId`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | mActorUniqueId


### `PropertyFile::Property`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | first
32 | (32) `std::string` | second


### `PackManifest::CapabilityRegistry`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_set<std::string>` | mTrustedCapabilities
56 | (56) `std::unordered_set<std::string>` | mCapabilities


### `PackReport`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | mLocation
56 | (1) `bool` | mWasUpgraded
57 | (1) `bool` | mAttemptedUpgrade
64 | (24) `PackErrors` | mErrors
88 | (24) `PackErrors` | mWarnings
112 | (112) `SemVersion` | mRequiredBaseGameVersion
224 | (32) `std::string` | mOriginalName
256 | (32) `std::string` | mOriginalVersion
288 | (136) `PackIdVersion` | mIdentity
424 | (1) `PackType` | mPackType


### `PackErrors`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::shared_ptr<PackError>>` | baseclass_0


### `PackSourceReport`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<PackIdVersion,PackReport>` | mReports


### `PackMover::PackMoverCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (bool)>::_Invoker_type` | _M_invoker


### `PackCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (Pack &)>::_Invoker_type` | _M_invoker


### `PackParseErrorTypeEventMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<int,std::string>::_Hashtable` | _M_h


### `PackParseErrorTypeLOCMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<int,std::string>::_Hashtable` | _M_h


### `PackInstance::Callback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Core::Path &)>::_Invoker_type` | _M_invoker


### `PackInstance`
Offset | Type | Name
-|-|-|-
0 | (432) `PackReport` | mPackReport
432 | (8) `PackSettings *` | mPackSettings
440 | (8) `ResourcePack *` | mPack
448 | (16) `PackStats` | mStats
464 | (4) `int` | mSubpackIndex


### `PackStats`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mOverriddenEntityCount
4 | (4) `uint32_t` | mCustomEntityCount
8 | (4) `uint32_t` | mCustomAnimationCount
12 | (4) `uint32_t` | mCustomEffectCount


### `PlayerInventoryProxy::SlotData`
Offset | Type | Name
-|-|-|-
0 | (1) `ContainerID` | mContainerId
4 | (4) `int` | mSlot


### `PrecompiledCommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (24) `CommandOrigin` | baseclass_0


### `PropertyDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `Description` | baseclass_0


### `PlaySoundPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mName
72 | (12) `NetworkBlockPosition` | mPos
84 | (4) `float` | mVolume
88 | (4) `float` | mPitch


### `PackSettingsJsonValidator::getValidator::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PreferredPathComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `PushableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsPushable
1 | (1) `bool` | mIsPushableByPiston
4 | (4) `float` | mPushthrough


### `pair_type`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | first
8 | (8) `unsigned __int64` | second


### `PushableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (1) `bool` | mIsPushable
9 | (1) `bool` | mIsPushableByPiston


### `PathfinderNode`
Offset | Type | Name
-|-|-|-
0 | (12) `const BlockPos` | pos
12 | (4) `int` | heapIdx
16 | (4) `float` | g
20 | (4) `float` | h
24 | (4) `float` | f
28 | (4) `float` | mCostMalus
32 | (4) `float` | mMoveMalus
36 | (4) `float` | mTargetDist
40 | (4) `NodeType` | mType
48 | (8) `PathfinderNode *` | cameFrom
56 | (1) `bool` | closed


### `Path::NodeArray`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<Path::Node>` | baseclass_0


### `PlayerActionPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `NetworkBlockPosition` | mPos
48 | (4) `int` | mFace
52 | (4) `PlayerActionType_0` | mAction
56 | (8) `ActorRuntimeID` | mRuntimeId


### `Player::take::$1BEE5056AEB754170F0D74900712D0BE`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | this


### `PlayerRespawnTelemetryData`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mSearchTimeMS
4 | (4) `uint32_t` | mLongJumpCount
8 | (4) `uint32_t` | mShortJumpCount
16 | (8) `double` | mJumpDistance
24 | (4) `uint32_t` | mPositionSourceType
28 | (1) `bool` | mChangedDimension


### `PlayerRespawnBlockRadiusRandomizer`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | mSpawnRadius
4 | (4) `uint32_t` | mPossibleOrigins
8 | (4) `uint32_t` | mLargestPrime
12 | (4) `uint32_t` | mStartOrigin
16 | (4) `uint32_t` | mCurrentOrigin
20 | (4) `uint32_t` | mIterationCount


### `Player::checkNeedAutoJump::$B52B8B35601F6FAF57FCDEA392569712`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | region
8 | (8) `AABB *` | bufferAABB
16 | (8) `Player *` | this


### `Player::checkNeedAutoJump::$6915C98F38B5DDADCE093124C9EFBE13`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockPos *` | obstacleBlockPos
8 | (8) `BlockSource *` | region
16 | (8) `AABB *` | bufferAABB
24 | (8) `Player *` | this
32 | (8) `float *` | obstacleHeight
40 | (8) `const AABB *` | playerAABB


### `PotionBrewing::Ingredient`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mItemId
4 | (4) `int` | mData


### `Platform::RandomDevice`
Offset | Type | Name
-|-|-|-
0 | (5000) `std::random_device::$C8F4996271C64D14C79A59260E815DB5` | _anon_0


### `PortalShape`
Offset | Type | Name
-|-|-|-
0 | (4) `PortalAxis` | mAxis
4 | (1) `Facing::Name` | mRightDir
5 | (1) `Facing::Name` | mLeftDir
8 | (4) `int` | mNumPortalBlocks
12 | (12) `BlockPos` | mBottomLeft
24 | (1) `bool` | mBottomLeftValid
28 | (4) `int` | mHeight
32 | (4) `int` | mWidth


### `PortalRecord`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mBaseBlockPos
12 | (1) `char` | mSpan
13 | (1) `char` | mXInc
14 | (1) `char` | mZInc


### `PerlinSimplexNoise`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mLevels
8 | (24) `std::vector<SimplexNoise>` | mNoiseLevels
32 | (4) `float` | mNormalizationFactor


### `PosibleTransformation`
Offset | Type | Name
-|-|-|-
0 | (24) `WeightedBiomeVector` | mTransformsInto
24 | (64) `BiomeFilterGroup` | mCondition
88 | (4) `uint32_t` | mMinPassingNeighbors


### `PushableComponent::PushVectors`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | first
12 | (12) `Vec3` | second


### `ParticlesTeleportTrailEvent`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mStart
12 | (12) `Vec3` | mEnd
24 | (8) `Vec2` | mVariation
32 | (4) `float` | mDirScale
36 | (4) `int` | mCount


### `PackAccessStrategy::EnumerationCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Core::Path &)>::_Invoker_type` | _M_invoker


### `PhysicsComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `IEntityComponent` | baseclass_0


### `PathFinder`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mRegion
8 | (32) `BinaryHeap` | mOpenSet
40 | (56) `std::unordered_map<BlockPos,PathfinderNode>` | mNodes
96 | (256) `std::array<PathfinderNode *,32>` | mNeighbors
352 | (1) `bool` | mCanPassDoors
353 | (1) `bool` | mCanOpenDoors
354 | (1) `bool` | mAvoidWater
355 | (1) `bool` | mAvoidDamageBlocks
356 | (1) `bool` | mCanFloat
357 | (1) `bool` | mIsAmphibious
358 | (1) `bool` | mAvoidPortals
359 | (1) `bool` | mCanBreach
360 | (1) `bool` | mCanJump
361 | (1) `bool` | mEntityIsSwimmer
362 | (1) `bool` | mEntityIsFlyer
363 | (1) `bool` | mEntityIsFireImmune
364 | (1) `bool` | mEntityIsOnHotBlock
365 | (1) `bool` | mEntityIsWalker
366 | (1) `bool` | mEntityIsDoorOpener
367 | (1) `bool` | mEntityIsDoorBreaker
368 | (1) `bool` | mAllowBlockBreaking
376 | (8) `const PreferredPathDescription *` | mPathPrefs


### `PatternEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | mBlock
8 | (32) `PatternEntry::BlockEntryTester` | mBlockEntryTester


### `PatternEntry::BlockEntryTester`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (BlockSource &,const BlockPos &,const Block &)>::_Invoker_type` | _M_invoker


### `ParticlesBlockExplosionEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mRadius
4 | (12) `Vec3` | mOrigin
16 | (24) `std::vector<Vec3>` | mPositions


### `PistonArmBlock::neighborChanged::$20F33069935F666947F060F39ADB7AD4`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockActor *` | blockActor
8 | (8) `BlockPos *` | pistonBasePos
16 | (8) `BlockSource *` | region
24 | (8) `const BlockPos *` | pos


### `PieceList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<StructurePiece>>` | baseclass_0


### `pthread_mutex_t`
Offset | Type | Name
-|-|-|-
0 | (40) `__pthread_mutex_s` | __data
1 | (40) `char[40]` | __size
2 | (8) `__int64` | __align


### `pthread_attr_t_0`
Offset | Type | Name
-|-|-|-
0 | (56) `char[56]` | __size
1 | (8) `__int64` | __align


### `pthread_cond_t`
Offset | Type | Name
-|-|-|-
0 | (48) `__pthread_cond_s` | __data
1 | (48) `char[48]` | __size
2 | (8) `__int64` | __align


### `PackTypeToStringMap_t`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<PackType,std::string>::_Hashtable` | _M_h


### `pthread_rwlock_t`
Offset | Type | Name
-|-|-|-
0 | (56) `__pthread_rwlock_arch_t` | __data
1 | (56) `char[56]` | __size
2 | (8) `__int64` | __align


### `ProfilerLite`
Offset | Type | Name
-|-|-|-
0 | (120) `std::array<ProfilerLite::ScopedData *,15>` | mCustomScopeDatas
120 | (88) `ProfilerLite::ScopedData` | mUninitializedScopedData
208 | (32) `Core::HeapPathBuffer` | mLogFileName
240 | (416) `Core::OutputFileStream` | mLogFile
656 | (32) `Core::HeapPathBuffer` | mScreenLoadLogFileName
688 | (416) `Core::OutputFileStream` | mScreenLoadLogFile
1104 | (32) `Core::HeapPathBuffer` | mEventLogFileName
1136 | (416) `Core::OutputFileStream` | mEventLogFile
1552 | (32) `Core::HeapPathBuffer` | mSecondaryLogFileName
1584 | (416) `Core::OutputFileStream` | mSecondaryLogFile
2000 | (32) `Core::HeapPathBuffer` | mSecondaryScreenLoadLogFileName
2032 | (416) `Core::OutputFileStream` | mSecondaryScreenLoadLogFile
2448 | (32) `Core::HeapPathBuffer` | mSecondaryEventLogFileName
2480 | (416) `Core::OutputFileStream` | mSecondaryEventLogFile
2896 | (8) `double` | mTime
2904 | (8) `double` | mStartTime
2912 | (8) `double` | mNextUpdateTime
2920 | (8) `double` | mLastUpdateTime
2928 | (8) `double` | mBenchmarkModeTime
2936 | (1) `bool` | mBenchmarkModeDone
2937 | (1) `bool` | mBenchmarkModeIsSetup
2938 | (1) `bool` | mIsProfilingEnabled
2939 | (1) `bool` | mShouldCheckTreatments
2940 | (1) `bool` | mCanLogToSecondaryFile
2944 | (8) `_ProfilerLiteTimer *` | mActiveScope
2952 | (48) `std::map<std::thread::id,_ProfilerLiteTimer *>` | mThreadedActiveScopes
3000 | (32) `std::string` | mCurrentGamestate
3032 | (8) `std::chrono::nanoseconds` | mDebugServerTickTime
3040 | (8) `TreatmentService *` | mTreatmentService
3048 | (36) `ProfilerLiteTelemetry` | mTelemetry
3088 | (32) `std::string` | mCachedProfileString
3120 | (16) `std::array<unsigned int,4>` | mLastNetworkStatSampleNum
3136 | (8) `Core::FileSize` | mPrevTotalBytesWritten
3144 | (8) `Core::FileSize` | mPrevTotalBytesRead
3152 | (32) `ProfilerLite::RealtimeFrameData` | mFrameData


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
16 | (8) `std::chrono::nanoseconds` | mLastFrame
24 | (1) `bool` | mFirstFrame


### `PreferredPathDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (4) `float` | mDefaultBlockCost
12 | (4) `float` | mJumpCost
16 | (4) `int` | mMaxFallBlocks
24 | (24) `std::vector<BlockSet>` | mPreferredPathGroup


### `PropertyBag`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::Value` | mJsonValue
16 | (4) `int` | mChangeVersion


### `PackManifest::CapabilityRegisterer`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `persona::PersonaCharacterHandle`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mSkinName
32 | (4) `persona::ProfileType` | mType


### `Potion`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mId
8 | (32) `std::string` | mNameId
40 | (32) `std::string` | mPrefix
72 | (24) `std::vector<MobEffectInstance>` | mEffects
96 | (24) `std::vector<std::string>` | mDescriptionIds
120 | (4) `Potion::PotionVariant` | mVar


### `protobuf_main_2fproto_2fshared_2eproto::StaticDescriptorInitializer`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PieceWeight`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | pieceClass
32 | (4) `int` | weight
36 | (4) `int` | placeCount
40 | (4) `int` | maxPlaceCount
44 | (4) `int` | minDepth
48 | (1) `bool` | allowInRow


### `PackDiscoveryError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `PackError`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$PackError
8 | (24) `std::vector<std::string>` | mErrorParameters
32 | (4) `int` | mErrorValue
36 | (4) `PackErrorType` | mPackErrorType


### `PackAccessStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$PackAccessStrategy
8 | (1) `bool` | mAssetSetPopulated
16 | (56) `std::unordered_set<Core::PathBuffer<std::string >>` | mAssetSet


### `PackSetting`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value *` | mValue
8 | (24) `std::vector<PackSettingObserver>` | mObservers


### `PerfTimer::Node`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (8) `const char *` | function
16 | (4) `int` | line
20 | (2) `unsigned __int16` | elementCount
24 | (8) `double` | inclusiveTime
32 | (8) `double` | startTime
40 | (8) `PerfTimer::Node *` | elements


### `PacketSender`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$PacketSender
8 | (1) `SubClientId` | mSenderSubId


### `Pufferfish::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Phantom::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Pillager::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PermissionsHandler`
Offset | Type | Name
-|-|-|-
0 | (1) `CommandPermissionLevel` | mCommandPermissions
1 | (1) `PlayerPermissionLevel` | mPlayerPermissions


### `Player::Player::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PlayerInventoryProxy`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerSizeChangeListener` | baseclass_0
8 | (8) `ContainerContentChangeListener` | baseclass_8
16 | (4) `int` | mSelected
24 | (136) `ItemStack` | mInfiniteItem
160 | (1) `ContainerID` | mSelectedContainerId
168 | (8) `Unique<Inventory>` | mInventory
176 | (24) `std::vector<ItemStack>` | mComplexItems
200 | (16) `std::weak_ptr<HudContainerManagerModel>` | mHudContainerManager


### `PlayerUIContainer`
Offset | Type | Name
-|-|-|-
0 | (272) `SimpleContainer` | baseclass_0


### `Player::updateSkin::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PerlinNoise`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mLevels
4 | (4) `const int` | mMinLevel
8 | (24) `std::vector<ImprovedNoise>` | mNoiseLevels


### `PortalBlock::animateTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ptr_move<std::shared_ptr<LevelChunk> >`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `PlayerScore`
Offset | Type | Name
-|-|-|-
0 | (16) `ScoreboardId` | mScoreboardId
16 | (4) `int` | mScore


### `pthread_condattr_t`
Offset | Type | Name
-|-|-|-
0 | (4) `char[4]` | __size
1 | (4) `int` | __align


### `pthread_attr_t`
Offset | Type | Name
-|-|-|-
0 | (56) `char[56]` | __size
1 | (8) `__int64` | __align


### `PackSettings`
```
struct PackSettings
{
  Json::Value mSettings;
  std::unordered_map<std::string,PackSetting> mPackSettings;
};

```

### `PermissionsFile`
```
struct PermissionsFile
{
  const Core::HeapPathBuffer mFilePath;
  std::unordered_map<std::string,PlayerPermissionLevel> mPermissions;
};

```

### `PackSettingsFactory`
```
struct PackSettingsFactory
{
  std::unordered_map<PackIdVersion,std::unique_ptr<PackSettings>> mPackSettings;
};

```

### `PackSource`
```
struct PackSource
{
  int (**_vptr$PackSource)(void);
};

```

### `Pack`
```
struct Pack
{
  std::unique_ptr<PackManifest> mManifest;
  std::unique_ptr<PackAccessStrategy> mAccessStrategy;
  std::unique_ptr<SubpackInfoCollection> mSubpackInfoStack;
  std::unique_ptr<PackMetadata> mMetadata;
  std::map<void *,std::function<void (Pack &)>> mPackUpdatedCallbacks;
  std::map<void *,std::function<void (Pack &)>> mPackDeletedCallbacks;
};

```

### `ProfilerLite::NetworkStats`
```
struct ProfilerLite::NetworkStats
{
  uint32_t sentPackets;
  uint32_t sentBytes;
  uint32_t receivedPackets;
  uint32_t receivedBytes;
};

```

### `Player`
```
struct __cppobj __attribute__((aligned(8))) Player : Mob
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
  uint64_t mClientRandomId;
  const mce::UUID mClientUUID;
  Unique<Certificate> mCertificate;
  std::string mPlatformId;
  ActorUniqueID mPendingRideID;
  ActorUniqueID mPendingLeftShoulderRiderID;
  ActorUniqueID mPendingRightShoulderRiderID;
  ActorUniqueID mInteractTarget;
  Vec3 mInteractTargetPos;
  bool mHasFakeInventory;
  bool mIsRegionSuspended;
  GridArea<std::shared_ptr<LevelChunk> >::AddCallback mAddCallback;
  Unique<ChunkViewSource> mChunkSource;
  Unique<ChunkViewSource> mSpawnChunkSource;
  Unique<BlockSource> mOwnedBlockSource;
  BlockPos mBedPosition;
  Vec3 mTeleportDestPos;
  bool mUpdateMobs;
  Vec3 mFirstPersonLatestHandOffset;
  Vec3 mCapePosO;
  Vec3 mCapePos;
  float mPaddleForces[2];
  bool mIsPaddling[2];
  float mDistanceSinceTravelledEvent;
  float mDistanceSinceTransformEvent;
  std::shared_ptr<IContainerManager> mContainerManager;
  Unique<PlayerInventoryProxy> mInventoryProxy;
  SerializedSkin mSkin;
  std::vector<ItemInstance> mCreativeItemList;
  std::array<std::vector<ItemGroup>,4> mFilteredCreativeItemList;
  SubClientId mClientSubId;
  std::string mPlatformOnlineId;
  Player::SpawnPositionState mSpawnPositionState;
  Player::SpawnPositionSource mSpawnPositionSource;
  Vec3 mSpawnPositioningTestPosition;
  bool mBlockRespawnUntilClientMessage;
  uint32_t mRespawnChunkBuilderPolicyHandle;
  Player::CachedSpawnData mCachedSpawnData;
  Unique<BlockSource> mSpawnBlockSource;
  bool mHasSeenCredits;
  Stopwatch mRespawnStopwatch_Searching;
  Vec3 mRespawnOriginalPosition;
  DimensionType mRespawnOriginalDimension;
  bool mRespawnReady;
  bool mRespawnBlocked;
  DimensionType mRespawnDimensionId;
  bool mCheckBed;
  bool mIsInitialSpawnDone;
  bool mPositionLoadedFromSave;
  int mFixStartSpawnFailures;
  ItemStack mItemInUse;
  PlayerInventoryProxy::SlotData mItemInUseSlot;
  int mItemInUseDuration;
  __int16 mSleepCounter;
  __int16 mPrevSleepCounter;
  bool mInteractDataDirty;
  ActorUniqueID mPreviousInteractEntity;
  int mPreviousCarriedItem;
  bool mAutoJumping;
  int mEmoteTicks;
  PacketSender *mPacketSender;
  BlockPos mBounceStartPos;
  const Block *mBounceBlock;
  float mFOVModifier;
  std::shared_ptr<HudContainerManagerModel> mHudContainerManagerModel;
  Unique<EnderChestContainer> mEnderChestInventory;
  std::vector<ActorUniqueID> mTrackedBossIDs;
  Player::PositionMode mPositionMode;
  ActorType mLastHurtBy;
  ItemGroup mCursorSelectedItemGroup;
  PlayerUIContainer mPlayerUIContainer;
  InventoryTransactionManager mTransactionManager;
  Unique<GameMode> mGameMode;
  PlayerRespawnRandomizer mSpawnRandomizer;
  float mVRMoveAdjAngle;
  bool mUseUIAnimationComponent;
  std::shared_ptr<AnimationComponent> mUIAnimationComponent;
  Player::PlayerListenerList mListeners;
  int mLastLevelUpTime;
  bool mPlayerLevelChanged;
  int mPreviousLevelRequirement;
  BlockPos mRespawnPosition;
  bool mIsForcedRespawnPos;
  bool mPlayerIsSleeping;
  bool mAllPlayersSleeping;
  bool mDestroyingBlock;
  Vec3 mSurvivalViewerPosition;
  std::vector<unsigned int> mOnScreenAnimationTextures;
  int mOnScreenAnimationTicks;
  GameType mPlayerGameType;
  int mEnchantmentSeed;
  uint32_t mChunkRadius;
  int mMapIndex;
  LoopingSoundHandle mElytraLoop;
  float mUnderwaterLightLevel;
  std::vector<int> mCooldowns;
  int64_t mStartedBlockingTimeStamp;
  int64_t mBlockedUsingShieldTimeStamp;
  int64_t mBlockedUsingDamagedShieldTimeStamp;
  bool mPrevBlockedUsingShield;
  bool mPrevBlockedUsingDamagedShield;
  bool mUsedPotion;
  int mBounceHeight;
  SkinAdjustments mSkinAdjustments;
  SerializedSkin mSerializedSkin;
  int mScanForDolphinTimer;
  bool mR5DataRecoverComplete;
  std::string mDeviceId;
  bool mFlagClientForBAIReset;
  BedHelper mBedHelper;
};

```

### `PackMetadata`
```
struct PackMetadata
{
  std::unique_ptr<EducationMetadata> mEducationMetadata;
};

```

### `Pos`
```
struct Pos
{
  int x;
  int y;
  int z;
};

```

### `producer_token_t`
```
typedef moodycamel::ProducerToken producer_token_t;

```

### `PrivateKeyManager`
```
struct __cppobj PrivateKeyManager : KeyManager
{
  std::string mPrivateKey;
};

```

### `PacketObserver`
```
struct PacketObserver
{
  int (**_vptr$PacketObserver)(void);
};

```

### `PlayerInteractionSystem`
```
struct PlayerInteractionSystem
{
  std::vector<std::unique_ptr<PlayerInteractionSystem::InteractionMappingBase>> mInteractionMappings;
};

```

### `PlayerEventListener`
```
struct PlayerEventListener
{
  int (**_vptr$PlayerEventListener)(void);
};

```

### `ProjectileSystem`
```
struct __cppobj ProjectileSystem : ITickingSystem
{
};

```

### `PeekSystem`
```
struct __cppobj PeekSystem : ITickingSystem
{
};

```

### `PistonBlockActor`
```
struct __cppobj PistonBlockActor : BlockActor:1608
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

### `PineFeature`
```
struct __cppobj __attribute__((aligned(8))) PineFeature : TreeFeature
{
};

```

### `PodzolAreaFeature`
```
struct __cppobj PodzolAreaFeature : Feature
{
};

```

### `PieceWeightList`
```
typedef std::vector<PieceWeight> PieceWeightList;

```

### `PoolElementStructurePiece`
```
struct __cppobj PoolElementStructurePiece : StructurePiece
{
  BoundingBox mCachedPieceBounds;
  int mCachedPieceBaseY;
  int mCachedXCenter;
  int mCachedZCenter;
  float mCachedMaxRadius;
  const StructurePoolElement *mElement;
  BlockPos mPosition;
  Rotation_0 mRotation;
  JigsawJunction mJigsawJunction;
  std::unordered_map<BlockPos,ActorDefinitionIdentifier> mEntitiesToPlace;
};

```

### `PlayerSelector`
```
typedef CommandSelector<Player> PlayerSelector;

```

### `PostprocessingManager`
```
struct PostprocessingManager
{
  Bedrock::Threading::Mutex mManagerMutex;
  std::unordered_set<ChunkPos> mAcquired;
};

```

### `POIInstance`
```
struct __attribute__((aligned(8))) POIInstance
{
  HashedString mName;
  HashedString mInitEvent;
  HashedString mEndEvent;
  Village *mVillage;
  BlockPos mPosition;
  uint64_t mOwnerCount;
  uint64_t mOwnerCapacity;
  uint64_t mWeight;
  float mRadius;
  POIType mType;
  HashedString mSoundEvent;
  __int16 mArrivalFailuresCount;
  bool mUseBoundingBox;
};

```

### `PerlinNoisePtr`
```
typedef std::unique_ptr<PerlinNoise> PerlinNoisePtr;

```

### `PillagerOutpostFeature`
```
struct __cppobj PillagerOutpostFeature : StructureFeature:1760
{
  const int OUTPOST_SPACING;
  const int MIN_OUTPOST_SEPARATION;
  std::vector<int> mAllowedBiomes;
};

```

### `PillagerOutpostStart`
```
struct __cppobj PillagerOutpostStart : StructureStart
{
};

```

### `PillagerOutpostPieces::PillagerOutpostPiece`
```
struct __cppobj __attribute__((aligned(8))) PillagerOutpostPieces::PillagerOutpostPiece : TemplateStructurePiece
{
  std::vector<BlockPos> mPillagerPositions;
  std::vector<BlockPos> mCaptainPositions;
  std::vector<BlockPos> mIronGolemPositions;
  std::string mTemplateName;
  StructureManager *mStructureManager;
  BlockPos mPosition;
  float mIntegrity;
  Rotation_0 mRotation;
  bool mIsSatellite;
  bool mHeightSet;
};

```

### `PillagerOutpostPieces`
```
struct PillagerOutpostPieces
{
  __int8 gap0[1];
};

```

### `PackSettingObserver`
```
struct PackSettingObserver
{
  void *mToken;
  PackSettingChangedCallback mChangeCallback;
};

```

### `PropertyListMap`
```
typedef std::unordered_map<unsigned int,std::unordered_map<std::string,Social::Events::Property>> PropertyListMap;

```

### `PackSettingChangedCallback`
```
typedef std::function<void (const Json::Value &)> PackSettingChangedCallback;

```

### `PurchaseInfo`
```
struct __attribute__((aligned(4))) PurchaseInfo
{
  ProductSku mProductSku;
  std::string mPlatformPurchaseId;
  std::string mReceipt;
  std::string mCorrelationId;
  PurchasePath mPurchasePath;
  bool mActive;
  bool mRenewal;
};

```

### `ProductSku`
```
struct __cppobj ProductSku : NewType<std::string >
{
};

```

### `PushNotificationMessage`
```
struct PushNotificationMessage
{
  PushNotificationType m_Type;
  std::string m_Title;
  std::string m_Description;
  Json::Value m_PropertyBag;
};

```

### `Parser`
```
struct Parser
{
  __int8 gap0[1];
};

```

### `Path`
```
struct __attribute__((aligned(8))) Path
{
  Path::NodeArray mNodes;
  size_t mIndex;
  PathCompletionType mCompletionType;
};

```

### `POIBlueprint`
```
struct __attribute__((aligned(8))) POIBlueprint
{
  HashedString mName;
  HashedString mInitEvent;
  HashedString mEndEvent;
  POIType mType;
  float mRadius;
  uint64_t mCapacity;
  uint64_t mWeight;
  HashedString mSoundEvent;
  bool mUseBoundingBox;
};

```

### `PlayerInteractionSystem::InteractionMappingBase`
```
struct PlayerInteractionSystem::InteractionMappingBase
{
  int (**_vptr$InteractionMappingBase)(void);
};

```

### `PlayerInteractionSystem::InteractionMapping<InteractComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<InteractComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<BucketableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<BucketableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<TameableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<TameableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<TrustingComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<TrustingComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<AgeableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<AgeableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<BalloonableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<BalloonableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<HealableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<HealableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<BreedableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<BreedableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<BribeableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<BribeableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<LeashableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<LeashableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<NameableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<NameableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<MountTamingComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<MountTamingComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<RideableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<RideableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<SitComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<SitComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<NpcComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<NpcComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<TripodCameraComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<TripodCameraComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<LegacyTradeableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<LegacyTradeableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PlayerInteractionSystem::InteractionMapping<GiveableComponent>`
```
struct __cppobj PlayerInteractionSystem::InteractionMapping<GiveableComponent> : PlayerInteractionSystem::InteractionMappingBase
{
};

```

### `PrioritizedGoal`
```
struct __attribute__((aligned(4))) PrioritizedGoal
{
  Unique<Goal> mGoal;
  int mPriority;
  bool mUsed;
  bool mToStart;
};

```

### `PathNavigation`
```
struct PathNavigation
{
  int (**_vptr$PathNavigation)(void);
};

```

### `Path::Node`
```
struct Path::Node
{
  BlockPos pos;
  NodeType type;
};

```

### `PeekDefinition`
```
struct PeekDefinition
{
  DefinitionTrigger mOnOpen;
  DefinitionTrigger mOnClose;
  DefinitionTrigger mOnTargetOpen;
};

```

### `PlayerList`
```
typedef std::vector<Player *> PlayerList;

```

### `PlayStatusPacket`
```
struct __cppobj PlayStatusPacket : Packet:288
{
  PlayStatus mStatus;
};

```

### `PlayerInputPacket`
```
struct __cppobj __attribute__((aligned(4))) PlayerInputPacket : Packet:288
{
  Vec2 mMov;
  bool mIsJumping;
  bool mIsSneaking;
};

```

### `PlayerAuthInputPacket`
```
struct __cppobj PlayerAuthInputPacket : Packet:288
{
  Vec2 mRot;
  Vec3 mPos;
  float mYHeadRot;
  Vec2 mMove;
  Vec3 mGazeDir;
  std::bitset<25> mInputData;
  InputMode mInputMode;
  ClientPlayMode mPlayMode;
};

```

### `PurchaseReceiptPacket`
```
struct __cppobj PurchaseReceiptPacket : Packet
{
  std::vector<std::string> mPurchaseRecipts;
};

```

### `PhotoTransferPacket`
```
struct __cppobj PhotoTransferPacket : Packet
{
  std::string mPhotoName;
  std::string mPhotoData;
  std::string mBookId;
};

```

### `PotionBrewing::Mix<std::shared_ptr<const Potion> >`
```
struct PotionBrewing::Mix<std::shared_ptr<const Potion> >
{
  std::shared_ptr<const Potion> mFrom;
  PotionBrewing::Ingredient mIngredient;
  std::shared_ptr<const Potion> mTo;
};

```

### `PotionBrewing::Mix<const Item &>`
```
struct PotionBrewing::Mix<const Item &>
{
  const Item *mFrom;
  PotionBrewing::Ingredient mIngredient;
  const Item *mTo;
};

```

### `PotionBrewing`
```
struct PotionBrewing
{
  __int8 gap0[1];
};

```

### `PotionBrewing::Mix<ItemInstance>`
```
struct PotionBrewing::Mix<ItemInstance>
{
  ItemInstance mFrom;
  PotionBrewing::Ingredient mIngredient;
  ItemInstance mTo;
};

```

### `Painting`
```
struct __cppobj Painting : HangingActor
{
  const Motive *mMotive;
};

```

### `PropertyFile::PropertyVector`
```
typedef std::vector<std::pair<std::string,std::string >> PropertyFile::PropertyVector;

```

### `PropertyFile::PropertyMap`
```
typedef std::map<std::string,std::string> PropertyFile::PropertyMap;

```

### `PackErrorFactory`
```
struct PackErrorFactory
{
  __int8 gap0[1];
};

```

### `PackSettingsError`
```
struct __cppobj PackSettingsError : PackError
{
};

```

### `PackMover`
```
struct PackMover
{
  __int8 gap0[1];
};

```

### `PackLoadError`
```
struct __cppobj PackLoadError : PackError
{
};

```

### `PlayerSuspension`
```
struct __attribute__((aligned(8))) PlayerSuspension
{
  mce::UUID mId;
  PlayerSuspension::State mSuspensionState;
};

```

### `PhotoStorage`
```
struct PhotoStorage
{
  Core::HeapPathBuffer mBaseDir;
  Core::HeapPathBuffer mBookDir;
  Core::HeapPathBuffer mPhotoDir;
  Core::HeapPathBuffer mManifestDir;
  std::unordered_set<std::string> mChecksums;
};

```

### `ProjectileFactory`
```
struct ProjectileFactory
{
  Level *mLevel;
};

```

### `PortalForcer`
```
struct __cppobj PortalForcer : SavedData
{
  Level *mLevel;
  Random mRandom;
  std::unordered_map<AutomaticID<Dimension,int>,std::unordered_set<PortalRecord>> mPortalRecords;
};

```

### `PlayerListEntries`
```
typedef std::unordered_map<mce::UUID,PlayerListEntry> PlayerListEntries;

```

### `PendingRemovalInfo`
```
struct __attribute__((aligned(8))) PendingRemovalInfo
{
  std::unique_ptr<Actor> e;
  int ticks;
};

```

### `PlayerEventCoordinator`
```
struct __cppobj PlayerEventCoordinator : EventCoordinator<PlayerEventListener>
{
};

```

### `PlayerMovementTelemetryData`
```
struct PlayerMovementTelemetryData
{
  int mCount;
  float mTotalPosDelta;
  float mMinPosDelta;
  float mMaxPosDelta;
};

```

### `Player::CachedSpawnData`
```
struct Player::CachedSpawnData
{
  DimensionType mRespawnDimensionId;
  Vec3 mTeleportDestPos;
  BlockPos mRespawnPosition;
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

### `PlayerRespawnRandomizer`
```
struct PlayerRespawnRandomizer
{
  Random mRandom;
  uint32_t mSpawnRadius;
  uint32_t mSquaredRadius;
  PlayerRespawnBlockRadiusRandomizer mPrimaryRandomizer;
  PlayerRespawnBlockRadiusRandomizer mSecondaryRandomizer;
  Vec3 mSpawnCenter;
  Vec3 mPrimaryOffset;
  Vec3 mPrimaryScale;
};

```

### `Player::PlayerListenerList`
```
typedef std::vector<PlayerListener *> Player::PlayerListenerList;

```

### `PushThroughDescription`
```
struct __cppobj __attribute__((aligned(8))) PushThroughDescription : PropertyDescription
{
  float mValue;
};

```

### `PersistentDescription`
```
struct __cppobj PersistentDescription : ComponentDescription
{
};

```

### `ProjectileDescription`
```
struct __cppobj __attribute__((aligned(8))) ProjectileDescription : ComponentDescription
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

### `PlayerCommandOrigin`
```
struct __cppobj PlayerCommandOrigin : CommandOrigin
{
  ActorUniqueID mPlayerId;
  Level *mLevel;
};

```

### `PackSettingsJsonValidator`
```
struct PackSettingsJsonValidator
{
  __int8 gap0[1];
};

```

### `PerfTimer`
```
struct __attribute__((packed)) __attribute__((aligned(16))) PerfTimer
{
  std::map<std::string,double> mLogEventMap;
  std::vector<PerfTimer::Node *> mNodeStack;
  std::array<std::vector<PerfTimer::Node *>,14> mIdleNodes;
  std::vector<std::unique_ptr<PerfTimer::Node []>> mAllocations;
  int mCurrentStackLevel;
  __attribute__((aligned(8))) Core::OutputFileStream mOutputStream;
  std::unordered_map<const char *,int> mStringLookupMap;
  int mCurrentString;
  __attribute__((aligned(8))) Unique<RakNet::BitStream> mBitStream;
  std::thread::id mCurrentThreadId;
  unsigned int mNumberOfRootObjects;
};

```

### `Pig`
```
struct __cppobj Pig : Animal
{
};

```

### `PolarBear`
```
struct __cppobj PolarBear : Animal
{
  float clientSideStandAnimationO;
  float clientSideStandAnimation;
};

```

### `Panda`
```
struct __cppobj Panda : Animal
{
  float mRollAmount;
  float mRollAmountO;
  bool mFinishedTransitionLastTick;
  int mSneezeCounter;
};

```

### `Parrot`
```
struct __cppobj __attribute__((aligned(8))) Parrot : Animal
{
  float mFlap;
  float mOFlap;
  float mFlapSpeed;
  float mOFlapSpeed;
  float mFlapping;
};

```

### `Pufferfish`
```
struct __cppobj Pufferfish : Fish
{
};

```

### `PigZombie`
```
struct __cppobj __attribute__((aligned(8))) PigZombie : Zombie
{
  int mAngerTime;
  int mPlayAngrySoundIn;
  int mStunedTime;
};

```

### `Phantom`
```
struct __cppobj Phantom : Monster
{
};

```

### `PrimedTnt`
```
struct __cppobj __attribute__((aligned(8))) PrimedTnt : Actor
{
  ActorUniqueID mOwnerID;
  ActorType mOwnerEntityType;
};

```

### `Pillager`
```
struct __cppobj __attribute__((aligned(8))) Pillager : HumanoidMonster
{
  Pillager::State mState;
};

```

### `PanicGoal`
```
struct __cppobj __attribute__((aligned(8))) PanicGoal : Goal
{
  Mob *mMob;
  bool mIgnoreMobDamage;
  bool mForceUse;
  bool mPreferWater;
  float mSpeedMultipler;
  Vec3 mPosition;
};

```

### `PlayGoal`
```
struct __cppobj PlayGoal : Goal
{
  Villager *mVillager;
  TempEPtr<Villager> mFollowFriend;
  float mSpeedModifier;
  int mPlayTime;
};

```

### `PlayerRideTamedGoal`
```
struct __cppobj PlayerRideTamedGoal : Goal
{
  Mob *mMob;
};

```

### `PickupItemsGoal`
```
struct __cppobj __attribute__((aligned(8))) PickupItemsGoal : Goal
{
  TempEPtr<Actor> mTarget;
  Vec3 mTargetPos;
  Mob *mMob;
  int mSearchRange;
  float mSpeedModifier;
  bool mTrackTarget;
  Unique<Path> mPath;
  int mRandomStopInterval;
  float mGoalRadiusSq;
  int mTimeToRecalcPath;
};

```

### `PetSleepWithOwnerGoal`
```
struct __cppobj __attribute__((aligned(8))) PetSleepWithOwnerGoal : BaseMoveToBlockGoal
{
  int mSettleTicks;
  TempEPtr<Mob> mOwner;
  Vec3 mBedPosition;
};

```

### `ParticleOnHitSubcomponent`
```
struct __cppobj __attribute__((aligned(8))) ParticleOnHitSubcomponent : OnHitSubcomponent
{
  ParticleType mParticleType;
  bool mOnEntityHit;
  bool mOnOtherHit;
  int mNumParticles;
};

```

### `PlayerUIContainerModel`
```
struct __cppobj PlayerUIContainerModel : PlayerUIContainerModelBase
{
};

```

### `PlayerUIContainerModelBase`
```
struct __cppobj PlayerUIContainerModelBase : ContainerModel
{
  Player *mPlayer;
};

```

### `PotionItem`
```
struct __cppobj __attribute__((aligned(8))) PotionItem : Item
{
  TextureUVCoordinateSet mPotionIcons[27];
  Potion::PotionVariant mPotionVariants[27];
};

```

### `PickaxeItem`
```
struct __cppobj PickaxeItem : DiggerItem
{
};

```

### `ProtectionEnchant`
```
struct __cppobj ProtectionEnchant : Enchant
{
};

```

### `PendingArea`
```
struct __attribute__((aligned(2))) PendingArea
{
  mce::UUID mUID;
  std::string mName;
  ActorUniqueID mEntityId;
  Bounds mBounds;
  float mMaxDistToPlayers;
  bool mIsCircle;
  bool mAlwaysActive;
  bool mCreated;
};

```

### `PortalForcer::PortalRecordSet`
```
typedef std::unordered_set<PortalRecord> PortalForcer::PortalRecordSet;

```

### `PortalBlock`
```
struct __cppobj PortalBlock : BlockLegacy
{
};

```

### `PreHillsEdgeAttributes`
```
typedef FilteredTransformationAttributes<PreHillsEdgeTransformation> PreHillsEdgeAttributes;

```

### `PostShoreEdgeAttributes`
```
typedef FilteredTransformationAttributes<PostShoreEdgeTransformation> PostShoreEdgeAttributes;

```

### `PlaySoundReactionComponent`
```
struct __cppobj __attribute__((aligned(8))) PlaySoundReactionComponent : LabTableReactionComponent
{
  LevelSoundEvent mSound;
};

```

### `PistonBlock`
```
struct __cppobj __attribute__((aligned(8))) PistonBlock : ActorBlock
{
  PistonBlock::Type mType;
};

```

### `PressurePlateBlock`
```
struct __cppobj __attribute__((aligned(8))) PressurePlateBlock : BasePressurePlateBlock
{
  PressurePlateBlock::Sensitivity mSensitivity;
};

```

### `PlanksBlock`
```
struct __cppobj PlanksBlock : BlockLegacy
{
};

```

### `PoweredRailBlock`
```
struct __cppobj __attribute__((aligned(8))) PoweredRailBlock : BaseRailBlock
{
};

```

### `PistonArmBlock`
```
struct __cppobj __attribute__((aligned(8))) PistonArmBlock : BlockLegacy
{
  PistonBlock::Type mType;
};

```

### `PumpkinBlock`
```
struct __cppobj __attribute__((aligned(8))) PumpkinBlock : BlockLegacy
{
  bool mLit;
  bool mCarved;
};

```

### `PotatoBlock`
```
struct __cppobj PotatoBlock : CropBlock
{
};

```

### `PrismarineBlock`
```
struct __cppobj PrismarineBlock : BlockLegacy
{
};

```

### `PodzolBlock`
```
struct __cppobj PodzolBlock : BlockLegacy
{
};

```

### `PoweredBlockComponent`
```
struct __cppobj __attribute__((aligned(4))) PoweredBlockComponent : BaseCircuitComponent:480
{
  bool mPromotedToProducer;
  bool mAllowAsPowerSource;
};

```

### `ProducerComponent`
```
struct __cppobj __attribute__((aligned(8))) ProducerComponent : BaseCircuitComponent:480
{
  int mNextStrength;
  bool mAttachedAllowed;
  bool mStopPower;
};

```

### `PhysicsDefinition`
```
struct PhysicsDefinition
{
  bool mHasGravity;
  bool mHasCollision;
};

```

### `PackAccessStrategyFactory`
```
struct PackAccessStrategyFactory
{
  __int8 gap0[1];
};

```

### `ParticleCommand`
```
struct __cppobj ParticleCommand : Command
{
  std::string mEffectName;
  CommandPositionFloat mSpawnPosition;
};

```

### `PermissionCommand`
```
struct __cppobj PermissionCommand : ServerCommand
{
  PermissionCommand::Action mAction;
  PermissionCommand::AvailableCommandPermissionPresets mPermissionLevel;
  PlayerSelector mTargetPlayers;
};

```

### `PlaySoundCommand`
```
struct __cppobj __attribute__((aligned(4))) PlaySoundCommand : Command
{
  std::string mSound;
  PlayerSelector mTargets;
  CommandPositionFloat mPosition;
  float mVolume;
  float mPitch;
  float mMinVolume;
  bool mPositionSet;
};

```

### `Palette`
```
struct Palette
{
  __int8 gap0[1];
};

```

### `ParticleTypeMap`
```
struct ParticleTypeMap
{
  __int8 gap0[1];
};

```

### `PlaceBlockDefinition`
```
struct __cppobj PlaceBlockDefinition : BehaviorDefinition
{
};

```

### `PlaceBlockNode`
```
struct __cppobj __attribute__((aligned(4))) PlaceBlockNode : BehaviorNode:480
{
  bool mRightMouseDown;
  bool mPreActionDone;
};

```

### `PulseCapacitor`
```
struct __cppobj __attribute__((aligned(8))) PulseCapacitor : CapacitorComponent:528
{
  bool mPowered;
  bool mNewPowered;
};

```

### `PistonConsumer`
```
struct __cppobj __attribute__((aligned(8))) PistonConsumer : ConsumerComponent
{
  FacingID mBlockedFace;
};

```

### `ProducerComponent:528`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(2))) ProducerComponent:528 : BaseCircuitComponent:480
{
  int mNextStrength;
  bool mAttachedAllowed;
  bool mStopPower;
};

```

### `ProducerComponent:544`
```
struct __cppobj __attribute__((aligned(4))) ProducerComponent:544 : BaseCircuitComponent:480
{
  int mNextStrength;
  bool mAttachedAllowed;
  bool mStopPower;
};

```

### `PackRenderCapabilitiesBitSet`
```
struct __cppobj PackRenderCapabilitiesBitSet : EnumBitset<RenderCapability,14>
{
};

```

### `protobuf_main_2fproto_2fshared_2eproto::TableStruct`
```
struct protobuf_main_2fproto_2fshared_2eproto::TableStruct
{
  __int8 gap0[1];
};

```

