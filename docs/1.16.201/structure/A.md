# A
### `AmbientSoundHelpers::SoundDelayInterval`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | min
4 | (4) `int` | max


### `AvoidanceBehavior::sortAvoidanceRays::__l2::<lambda_5abb5a0b7fec49761736b4b2bb029d6b>`
Offset | Type | Name
-|-|-|-


### `AllowList`
Offset | Type | Name
-|-|-|-
0 | (8) `IJsonSerializable` | baseclass_0
8 | (24) `std::vector<AllowListEntry>` | mEntries
32 | (64) `std::function<void __cdecl(void)>` | mSyncCallback


### `AsynchronousIPResolver`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUrl
32 | (16) `std::shared_ptr<AsynchronousIPResolver::ResolvedIp>` | mResolvedIpPtr


### `ActorUniqueID`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | rawID


### `AABB`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | min
12 | (12) `Vec3` | max
24 | (1) `bool` | empty


### `AllWorkerConfigurations`
Offset | Type | Name
-|-|-|-
0 | (32) `ThreadConfiguration` | MainThread
32 | (32) `ThreadConfiguration` | ServerThread
64 | (32) `ThreadConfiguration` | AudioThreads
96 | (40) `WorkerConfiguration` | Async
136 | (40) `WorkerConfiguration` | Disk
176 | (40) `WorkerConfiguration` | Network
216 | (40) `WorkerConfiguration` | Rendering
256 | (40) `WorkerConfiguration` | LevelDB
296 | (40) `WorkerConfiguration` | LevelDBCompaction
336 | (40) `WorkerConfiguration` | ConnectedStorage
376 | (40) `WorkerConfiguration` | Watchdog
416 | (40) `WorkerConfiguration` | AssetIO
456 | (40) `WorkerConfiguration` | AssetIOCallback
496 | (40) `WorkerConfiguration` | VR


### `ActorDefinitionIdentifier`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mNamespace
32 | (32) `std::string` | mIdentifier
64 | (32) `std::string` | mInitEvent
96 | (32) `std::string` | mFullName
128 | (48) `HashedString` | mCanonicalName


### `Actor::fetchNearbyActorsSorted::__l5::<lambda_95e74715c50799f2d4ed26f9fb2d44e9>`
Offset | Type | Name
-|-|-|-


### `AttributeCollection`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<HashedString,Attribute *>` | mAttributesMap
64 | (4) `unsigned int` | mIDValueIndex


### `AutomaticID<Dimension,int>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | runtimeID


### `AppPkgUpdateMgr::_parseAppPkgVerList::__l2::<lambda_c04fed226f49063013522b190f66e4b3>`
Offset | Type | Name
-|-|-|-
0 | (8) `AppPkgUpdateMgr *const` | __this


### `AppPkgUpdateMgr`
Offset | Type | Name
-|-|-|-
0 | (8) `AppPkgUpdateMgr_vtbl *` | __vftable
8 | (32) `std::string` | mCdnPkgListUrl
40 | (32) `std::string` | mCdnCpsPkgListUrl
72 | (4) `int` | mErrorCode
76 | (4) `ePkgUpdateStatus` | mStatus
80 | (64) `std::function<void __cdecl(void)>` | mSuccCallback
144 | (64) `std::function<void __cdecl(int)>` | mFailCallback
208 | (24) `std::vector<tAppPkgInfo>` | mAppPkgList


### `arraydescr`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | typecode
4 | (4) `int` | itemsize
8 | (8) `_object *(__fastcall *)(arrayobject *, __int64)` | getitem
16 | (8) `int (__fastcall *)(arrayobject *, __int64, _object *)` | setitem


### `arc`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | a_lbl
2 | (2) `__int16` | a_arrow


### `AF_StyleClassRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `AF_Style_` | style
4 | (4) `AF_WritingSystem_` | writing_system
8 | (4) `AF_Script_` | script
12 | (4) `AF_Blue_Stringset_` | blue_stringset
16 | (4) `AF_Coverage_` | coverage


### `AF_Script_UniRangeRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | first
4 | (4) `unsigned int` | last


### `AF_ScriptClassRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `AF_Script_` | script
8 | (8) `const AF_Script_UniRangeRec_ *` | script_uni_ranges
16 | (8) `const AF_Script_UniRangeRec_ *` | script_uni_nonbase_ranges
24 | (1) `unsigned __int8` | top_to_bottom_hinting
32 | (8) `const char *` | standard_charstring


### `Attribute`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mEncode
1 | (1) `RedefinitionMode` | mRedefinitionMode
2 | (1) `bool` | mSyncable
4 | (4) `unsigned int` | mIDValue
8 | (48) `HashedString` | mName


### `AppPlatformListener`
Offset | Type | Name
-|-|-|-
0 | (8) `AppPlatformListener_vtbl *` | __vftable
8 | (1) `bool` | mListenerRegistered


### `ArmorStand::Pose`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mHeadPose
12 | (12) `Vec3` | mBodyPose
24 | (12) `Vec3` | mRightArmPose
36 | (12) `Vec3` | mLeftArmPose
48 | (12) `Vec3` | mRightLegPose
60 | (12) `Vec3` | mLeftLegPose
72 | (12) `Vec3` | mRightItemPose


### `AF_WritingSystemClassRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `AF_WritingSystem_` | writing_system
8 | (8) `unsigned __int64` | style_metrics_size
16 | (8) `int (__fastcall *)(AF_StyleMetricsRec_ *, FT_FaceRec_ *)` | style_metrics_init
24 | (8) `void (__fastcall *)(AF_StyleMetricsRec_ *, AF_ScalerRec_ *)` | style_metrics_scale
32 | (8) `void (__fastcall *)(AF_StyleMetricsRec_ *)` | style_metrics_done
40 | (8) `void (__fastcall *)(AF_StyleMetricsRec_ *, int *, int *)` | style_metrics_getstdw
48 | (8) `int (__fastcall *)(AF_GlyphHintsRec_ *, AF_StyleMetricsRec_ *)` | style_hints_init
56 | (8) `int (__fastcall *)(unsigned int, AF_GlyphHintsRec_ *, FT_Outline_ *, AF_StyleMetricsRec_ *)` | style_hints_apply


### `ArmorItem::ArmorMaterial`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDurabilityMultiplier
4 | (16) `int[4]` | slotProtections
20 | (4) `int` | mEnchantmentValue
24 | (4) `float` | mKnockbackResistance


### `ActorAnimationControllerPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ActorAnimationControllerInfo>` | mActorAnimationControllerInfoPtr


### `AttributeInstance`
Offset | Type | Name
-|-|-|-
0 | (8) `AttributeInstance_vtbl *` | __vftable
8 | (1) `bool` | ?
16 | (48) `param_encode::EAttributeInstance` | ?
64 | (8) `BaseAttributeMap *` | mAttributeMap
72 | (8) `const Attribute *` | mAttribute
80 | (24) `std::vector<AttributeModifier>` | mModifierList
104 | (24) `std::vector<TemporalAttributeBuff>` | mTemporalBuffs
128 | (24) `std::vector<AttributeInstanceHandle>` | mListeners
152 | (16) `std::shared_ptr<AttributeInstanceDelegate>` | mDelegate
168 | (12) `$A8BD9ADF93FC6667E74883A931BC6A1A` | ___u9
184 | (24) `?` | mCurrentValues


### `ActorDefinitionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorDefinitionGroup *` | mGroup
8 | (8) `ActorDefinition *` | mPtr


### `AF_Blue_StringRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `AF_Blue_String_` | string
4 | (2) `unsigned __int16` | properties


### `ActivationUri`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mVerb
32 | (64) `std::unordered_map<std::string,std::string>` | mArguments


### `AFM_Parser_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(AFM_ParserRec_ *, FT_MemoryRec_ *, unsigned __int8 *, unsigned __int8 *)` | init
8 | (8) `void (__fastcall *)(AFM_ParserRec_ *)` | done
16 | (8) `int (__fastcall *)(AFM_ParserRec_ *)` | parse


### `ActorSkeletalAnimationPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ActorAnimationInfo>` | mActorAnimationInfoPtr


### `ActorMapping`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mNamespace
32 | (32) `std::string` | mPrimaryName
64 | (32) `std::string` | mAlternateName
96 | (48) `HashedString` | mCanonicalName


### `AttributeBuff`
Offset | Type | Name
-|-|-|-
0 | (8) `AttributeBuff_vtbl *` | __vftable
8 | (4) `float` | mAmount
16 | (16) `AttributeBuffInfo` | mInfo
32 | (16) `std::shared_ptr<Amplifier>` | mValueAmplifier
48 | (16) `std::shared_ptr<Amplifier>` | mDurationAmplifier
64 | (4) `float` | mScale
68 | (4) `int` | mAmplification
72 | (8) `unsigned __int64` | mId
80 | (4) `int` | mOperand


### `AttributeBuffInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | type
8 | (8) `ActorUniqueID` | source


### `AdventureSettingsPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `unsigned int` | mFlags
44 | (1) `_BYTE[1]` | mUserPermissions
48 | (4) `unsigned int` | mPermissionsFlags
52 | (1) `PlayerPermissionLevel` | mPlayerPermissions
56 | (8) `ActorUniqueID` | mSyncPlayerId
64 | (1) `bool` | mDefaultLevelAbilities
68 | (4) `unsigned int` | mCustomAbilityCache


### `AABBShapeComponent`
Offset | Type | Name
-|-|-|-
0 | (28) `AABB` | mAABB
28 | (8) `Vec2` | mBBDim


### `Abilities`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<PermissionsHandler>` | mPermissions
8 | (1872) `std::array<Ability,18>` | mAbilities
1880 | (832) `std::array<Ability,8>` | mCustomAbilityCache


### `Ability`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | mType
8 | (88) `Ability::Value` | mValue
96 | (1) `Ability::Options` | mOptions


### `Ability::Value`
Offset | Type | Name
-|-|-|-
0 | (80) `param_encode::EBool` | mBoolVal
80 | (4) `float` | mFloatVal


### `AdventureSettings`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | noPvM
1 | (1) `bool` | noMvP
2 | (1) `bool` | immutableWorld
3 | (1) `bool` | showNameTags
4 | (1) `bool` | autoJump


### `ActorRuntimeID`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | rawID


### `ActorLink`
Offset | Type | Name
-|-|-|-
0 | (1) `ActorLinkType` | type
8 | (8) `ActorUniqueID` | A
16 | (8) `ActorUniqueID` | B
24 | (1) `bool` | mImmediate
25 | (1) `bool` | mRiderInitiated


### `AnimationEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id


### `AnimationComponentID`
Offset | Type | Name
-|-|-|-
0 | (8) `AnimationComponentID::<unnamed_type_mData>` | mData


### `AnimationComponentID::<unnamed_type_mData>`
Offset | Type | Name
-|-|-|-
0 | (8) `$8F86E27B5AF650152C94327AD03C4682` | __s0
1 | (8) `unsigned __int64` | mAllBits


### `ActorRenderData`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (12) `Vec3` | position
20 | (8) `Vec2` | rotation
28 | (8) `Vec2` | mHeadRot
36 | (1) `bool` | glint
37 | (1) `bool` | mIgnoreLighting
38 | (1) `bool` | mIsInUI
40 | (4) `float` | mDeltaTime
44 | (4) `int` | mModelObjId
48 | (4) `float` | mModelSize
56 | (8) `AnimationComponent *` | mAnimationComponent
64 | (8) `MolangVariableMap *` | mVariables


### `AbstractSceneProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::string __cdecl(void)>` | mGetScreenName
64 | (64) `std::function<ScreenControllerProxy * __cdecl(void)>` | mGetController
128 | (64) `std::function<ScreenViewProxy * __cdecl(void)>` | mGetScreenView


### `AutoPlaceResult`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | collectionName
32 | (4) `int` | collectionIndex


### `AdhocHelper::enableAdhoc::__l2::<lambda_aba39049fa0e3ca97d3203a68e527456>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerServiceManager *` | serviceManager
8 | (64) `std::function<void __cdecl(enum Social::EnableResult)>` | onComplete


### `AdhocHelper::disableAdhoc::__l2::<lambda_86963609ec95398d55f0ac9393b52cdd>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerServiceManager *` | serviceManager
8 | (64) `std::function<void __cdecl(bool)>` | onComplete


### `ActorUseItemEvent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (240) `const ItemInstance` | mItemUsed
248 | (4) `_BYTE[4]` | mItemUseMethod


### `ActorAcquiredItemEvent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (240) `const ItemInstance` | mItem
248 | (4) `int` | mAmountAcquired
252 | (4) `_BYTE[4]` | mAcquireMethod
256 | (24) `WeakRefT<EntityRefTraits>` | mSecondaryActorContext


### `AdhocHelper::enableAdhoc::__l2::<lambda_aba39049fa0e3ca97d3203a68e527456>::()::__l2::<lambda_c603c240f2cd5ff102a2b4d97e390069>::()::__l15::<lambda_c93f288b8e68d10ea5dd1aed57267bd4>::()::__l2::<lambda_f95b7f9cf0ee963b1d1c1746b6e3c536>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum Social::EnableResult)>` | onComplete


### `AdhocHelper::enableAdhoc::__l2::<lambda_aba39049fa0e3ca97d3203a68e527456>::()::__l2::<lambda_c603c240f2cd5ff102a2b4d97e390069>::()::__l15::<lambda_c93f288b8e68d10ea5dd1aed57267bd4>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerServiceManager *` | serviceManager
8 | (64) `std::function<void __cdecl(enum Social::EnableResult)>` | onComplete


### `AdhocHelper::enableAdhoc::__l2::<lambda_aba39049fa0e3ca97d3203a68e527456>::()::__l2::<lambda_c603c240f2cd5ff102a2b4d97e390069>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerServiceManager *` | serviceManager
8 | (64) `std::function<void __cdecl(enum Social::EnableResult)>` | onComplete


### `AdhocHelper::disableAdhoc::__l2::<lambda_86963609ec95398d55f0ac9393b52cdd>::()::__l2::<lambda_52889d99e5c23e56b4ce5cb7cf7de074>::()::__l2::<lambda_3e26e6762b43495938e8f429dcf00915>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | onComplete


### `AdhocHelper::disableAdhoc::__l2::<lambda_86963609ec95398d55f0ac9393b52cdd>::()::__l2::<lambda_52889d99e5c23e56b4ce5cb7cf7de074>`
Offset | Type | Name
-|-|-|-
0 | (8) `Social::MultiplayerServiceManager *` | serviceManager
8 | (64) `std::function<void __cdecl(bool)>` | onComplete


### `ActorDamageSource`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorDamageSource_vtbl *` | __vftable
8 | (4) `_BYTE[4]` | mCause


### `AnimatedImageData`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mType
4 | (4) `_BYTE[4]` | mAnimationExpression
8 | (80) `mce::Image` | mImage
88 | (4) `float` | mFrames


### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l2::ResourcePath`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | path


### `ActorResourceDefinitionGroup::loadBuiltInActorResourceDefinitions::__l2::<lambda_0e471e1648006f725df7e5d623467c20>::()::__l5::<lambda_b84a94f1803599b1b95844ebd97e820b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > >` | loadTask
16 | (32) `Core::PathBuffer<std::string >` | filename
48 | (112) `const SemVersion` | engineVersion
160 | (8) `ParticleEffectGroup *` | particleEffectGroup
168 | (8) `ActorResourceDefinitionGroup *const` | __this


### `ActorResourceDefinition`
Offset | Type | Name
-|-|-|-
0 | (200) `CommonResourceDefinitionMap` | baseclass_0
200 | (1) `const bool` | mIsAttachable
201 | (1) `bool` | mIsOverriden
202 | (1) `bool` | mIsOverridePersona
208 | (48) `HashedString` | mName
256 | (112) `const SemVersion` | mEngineVersion
368 | (112) `const SemVersion` | mMinEngineVersion
480 | (48) `HashedString` | mQueryableGeometryName
528 | (64) `std::unordered_map<std::string,GeometryPtr>` | mGeometryMap
592 | (64) `std::unordered_map<std::string,ActorTextureInfo>` | mTextureMap
656 | (64) `std::unordered_map<std::string,MaterialVariants>` | mMaterialVariantMap
720 | (64) `std::unordered_map<HashedString,ParticleEffectPtr>` | mActorParticleEffectMap
784 | (24) `std::vector<std::pair<RenderControllerPtr,ExpressionNode>>` | mRenderControllerPtrArray
808 | (64) `std::unordered_map<HashedString,ExpressionNode>` | mActorScripts
872 | (64) `std::unordered_map<HashedString,std::string>` | mSoundEffectMap
936 | (1) `bool` | mEnableAttachables
944 | (64) `std::unordered_map<HashedString,std::string>` | mAttachableOverrideMap
1008 | (88) `SpawnEggInfo` | mSpawnEgg


### `AmbientOcclusionCalculator`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mTintSides
1 | (1) `bool` | mDoSeasons
2 | (1) `bool` | mTouchEdge
4 | (24) `float[6]` | mFaceShading
32 | (8) `BlockTessellatorCache *` | mCache
40 | (8) `const BlockPos *` | mCenterPos
48 | (8) `const Block *` | mCenterBlock
56 | (16) `mce::Color` | mBaseColor
72 | (8) `BrightnessPair *` | mOutputLightTexturePositons
80 | (8) `mce::Color *` | mOutputColors


### `ActorTerrainInterlockData`
Offset | Type | Name
-|-|-|-
0 | (1) `ActorTerrainInterlockData::VisibilityState` | mRenderVisibilityState
8 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mCreationTime
16 | (1) `bool` | mHasBeenDelayedDeleted


### `AirAndSimpleBlockBits`
Offset | Type | Name
-|-|-|-
0 | (12) `const BlockPos` | mOriginPos
16 | (736) `RenderChunkBits` | mAirBlocks
752 | (736) `RenderChunkBits` | mSimpleBlocks


### `ActorShadowRenderObjectCollection`
Offset | Type | Name
-|-|-|-
0 | (40) `std::vector<ActorShadowRenderObject,LinearAllocator<ActorShadowRenderObject> >` | mEntityShadows
40 | (16) `std::shared_ptr<mce::Mesh>` | mShadowCylinder
56 | (16) `std::shared_ptr<mce::Mesh>` | mShadowOverlayCube
72 | (8) `const mce::MaterialPtr *` | mShadowVolumeFront
80 | (8) `const mce::MaterialPtr *` | mShadowVolumeBack
88 | (8) `const mce::MaterialPtr *` | mShadowOverlayMat
96 | (16) `mce::Color` | mShadowColor


### `ActorShadowRenderObject`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mPos
12 | (4) `float` | mRadius


### `AtlasParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mPadSize
4 | (4) `int` | mReductionMips
8 | (4) `unsigned int` | mColorMipCount


### `ActorFilterGroup`
Offset | Type | Name
-|-|-|-
0 | (64) `FilterGroup` | baseclass_0


### `ActorHistory::Snapshot`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<IReplayableActorState>>` | mState
24 | (24) `std::vector<std::shared_ptr<IReplayableActorInput>>` | mInputs


### `ActorAnimationChangedEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mActor
24 | (4) `AnimationEventType` | mType
28 | (4) `AnimationEventState` | mState


### `AdmireItemComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsAdmiring
8 | (248) `ItemStack` | mAdmireItem
256 | (8) `Tick` | mAdmireUntil
264 | (8) `Actor *` | mItemOwner


### `ActorDamageByChildActorSource`
Offset | Type | Name
-|-|-|-
0 | (80) `ActorDamageByActorSource` | baseclass_0
80 | (1) `bool` | mDamagingActorIsWorldBuilder
81 | (1) `bool` | mDamagingActorIsCreative
88 | (8) `ActorUniqueID` | mDamagingActorId
96 | (4) `ActorType` | mDamagingActorType
100 | (4) `_BYTE[4]` | mDamagingActorCategories
104 | (32) `std::string` | mDamagingActorNameTag


### `ActorDamageByActorSource`
Offset | Type | Name
-|-|-|-
0 | (16) `ActorDamageSource` | baseclass_0
16 | (8) `BlockSource *` | mRegion
24 | (1) `bool` | mIsWorldBuilder
25 | (1) `bool` | mIsCreative
32 | (8) `ActorUniqueID` | mEntityID
40 | (4) `ActorType` | mEntityType
44 | (4) `_BYTE[4]` | mEntityCategories
48 | (32) `std::string` | mEntityNameTag


### `AngrySystem::tick::__l2::<lambda_6446fd130cdc64a998bc057d1c0ea84e>`
Offset | Type | Name
-|-|-|-
0 | (8) `AngrySystem *const` | __this


### `AreaAttackSystem::tick::__l2::<lambda_5a169b8cd04693a3eddf8bca8f651cc9>`
Offset | Type | Name
-|-|-|-
0 | (8) `AreaAttackSystem *const` | __this


### `AngryComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDuration
4 | (1) `bool` | mHasTicked
5 | (1) `bool` | mBroadcastAnger
6 | (1) `bool` | mBroadcastOnAttack
7 | (1) `bool` | mBroadcastOnBeingAttacked
8 | (4) `int` | mBroadcastRange
16 | (64) `ActorFilterGroup` | mBroadcastFilter
80 | (64) `ActorFilterGroup` | mSubjectFilter
144 | (8) `Tick` | mNextSoundEventTick


### `ActorEventListener`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorEventListener_vtbl *` | __vftable


### `Automation::Response`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | mType
8 | (32) `const std::string` | mMessage
40 | (32) `const std::string` | mId


### `ActorInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRuntimeId
8 | (176) `ActorDefinitionIdentifier` | mIdentifier
184 | (176) `ActorDefinitionIdentifier` | mBaseIdentifier
360 | (1) `bool` | mHasSpawnEgg
361 | (1) `bool` | mIsSummonable
364 | (8) `std::optional<int>` | mExperimentIndex
376 | (32) `std::string` | mExtensionBase
408 | (4) `ActorType` | mCustomEntityType


### `AvailableCommandsPacket::EnumData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (24) `std::vector<unsigned int>` | values


### `AvailableCommandsPacket::ParamData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (4) `unsigned int` | parseSymbol
36 | (1) `bool` | optional
37 | (1) `unsigned __int8` | paramOptions


### `AvailableCommandsPacket::OverloadData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<AvailableCommandsPacket::ParamData>` | params


### `AvailableCommandsPacket::CommandData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | description
64 | (1) `unsigned __int8` | flags
65 | (1) `_BYTE[1]` | permission
72 | (24) `std::vector<AvailableCommandsPacket::OverloadData>` | overloads
96 | (4) `int` | aliasEnum


### `AvailableCommandsPacket::SoftEnumData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (24) `std::vector<std::string>` | values


### `AvailableCommandsPacket::ConstrainedValueData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | enumValueSymbol
4 | (4) `unsigned int` | enumSymbol
8 | (24) `std::vector<unsigned char>` | constraints


### `AvailableCommandsPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<std::string>` | mEnumValues
64 | (24) `std::vector<std::string>` | mPostfixes
88 | (24) `std::vector<AvailableCommandsPacket::EnumData>` | mEnums
112 | (24) `std::vector<AvailableCommandsPacket::CommandData>` | mCommands
136 | (24) `std::vector<AvailableCommandsPacket::SoftEnumData>` | mSoftEnums
160 | (24) `std::vector<AvailableCommandsPacket::ConstrainedValueData>` | mConstraints


### `AllowListEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `IJsonSerializable` | baseclass_0
8 | (32) `std::string` | mName
40 | (16) `mce::UUID` | mUuid
56 | (32) `std::string` | mXuid
88 | (1) `bool` | mIgnoresPlayerLimit


### `AutoCompleteOption`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | visualText
32 | (32) `std::string` | tabCompleteText
64 | (32) `std::string` | description
96 | (4) `unsigned int` | matchStart
100 | (4) `unsigned int` | matchLength
104 | (4) `unsigned int` | commandLineMatchStart
108 | (4) `unsigned int` | commandLineMatchOffset
112 | (8) `CommandItem` | item
120 | (1) `bool` | highlight


### `Automation::MessageHeader`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mRequestId
32 | (1) `Automation::MessagePurpose` | mMessagePurpose
36 | (4) `int` | mVersion


### `ActorDefinitionEvent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (32) `const std::string` | mEvent


### `ActorDefinitionDescriptor`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_set<HashedString>` | mComponentNames
64 | (40) `IdentifierDescription` | mIdentifier
104 | (40) `RuntimeIdentifierDescription` | mRuntimeIdentifier
144 | (16) `IsSpawnableDescription` | mIsSpawnable
160 | (16) `IsSummonableDescription` | mIsSummonable
176 | (72) `AnimationsDescription` | mAnimationsDescription
248 | (32) `AnimationScriptsDescription` | mAnimationScriptsDescription
280 | (24) `std::vector<GoalDefinition>` | mGoalDefinitions
304 | (24) `std::vector<ActorDefinitionAttribute>` | mAttributes
328 | (64) `std::unordered_map<std::string,DefinitionEvent>` | mEventHandlers
392 | (152) `DefinitionInstanceGroup` | mDefinitionGroup
544 | (152) `DefinitionInstanceGroup` | mGoalDefinitionGroup
696 | (8) `Description *` | mStoryline
704 | (8) `Description *` | mCustomEntityType
712 | (8) `Description *` | mPickupItem
720 | (8) `Description *` | mAttack
728 | (8) `Description *` | mMobEffects
736 | (8) `Description *` | mAmphibiousMoveControl
744 | (8) `Description *` | mBehavior
752 | (8) `Description *` | mBreakBlocks
760 | (8) `Description *` | mBreakDoorAnnotation
768 | (8) `Description *` | mBucketable
776 | (8) `Description *` | mCommandBlock
784 | (8) `Description *` | mContainer
792 | (8) `Description *` | mDweller
800 | (8) `Description *` | mGenericMoveControl
808 | (8) `Description *` | mGlideMoveControl
816 | (8) `Description *` | mHide
824 | (8) `Description *` | mIllagerBeastBlocked
832 | (8) `Description *` | mManagedWanderingTrader
840 | (8) `Description *` | mMoveControl
848 | (8) `Description *` | mDolphinSwimControl
856 | (8) `Description *` | mFlyControl
864 | (8) `Description *` | mHopControl
872 | (8) `Description *` | mHoverControl
880 | (8) `Description *` | mSwimControl
888 | (8) `Description *` | mWallClimberNavigation
896 | (8) `Description *` | mFloatNavigation
904 | (8) `Description *` | mFlyingNavigation
912 | (8) `Description *` | mHoverNavigation
920 | (8) `Description *` | mGenericNavigation
928 | (8) `Description *` | mWaterboundNavigation
936 | (8) `Description *` | mNavigation
944 | (8) `Description *` | mPersistent
952 | (8) `Description *` | mPreferredPath
960 | (8) `Description *` | mProjectile
968 | (8) `Description *` | mPushable
976 | (8) `Description *` | mRaidTrigger
984 | (8) `Description *` | mSlimeMoveControl
992 | (8) `Description *` | mStrength
1000 | (8) `Description *` | mTrail
1008 | (8) `Description *` | mTargetNearby
1016 | (8) `Description *` | mTeleport
1024 | (8) `Description *` | mTickWorld
1032 | (8) `Description *` | mTradeResupply
1040 | (8) `Description *` | mTrust
1048 | (8) `Description *` | mEconomyTradeable
1056 | (8) `Description *` | mTransformation
1064 | (8) `Description *` | mWaterMovement
1072 | (8) `Description *` | mDynamicJumpControl
1080 | (8) `Description *` | mJumpControl
1088 | (8) `Description *` | mOpenDoorAnnotation
1096 | (8) `Description *` | mTripodCamera


### `AnimationsDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (64) `std::unordered_map<HashedString,HashedString>` | mActorAnimationMap


### `AnimationScriptsDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (24) `std::vector<NamedMolangScript>` | mAnimateScript


### `ActorHurtEvent`
Offset | Type | Name
-|-|-|-
0 | (8) `Actor *` | mActor
8 | (8) `gsl::not_null<ActorDamageSource const *>` | mSource
16 | (4) `int` | mDamage
20 | (4) `int` | mAbsorbedDamage


### `ActorDefinitionGroup::_getResources::__l2::PackTask`
Offset | Type | Name
-|-|-|-
0 | (8) `PackInstance *` | mPack
8 | (24) `std::vector<std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<std::pair<Json::Value,Core::PathBuffer<std::string > > > >>` | jsonLoadTasks


### `ActorDefinitionGroup::_getResources::__l8::<lambda_d64fe27ef6da0a56cad972a0ec1d52ab>`
Offset | Type | Name
-|-|-|-
0 | (8) `PackInstance *` | packInstance
8 | (32) `Core::PathBuffer<std::string >` | res


### `ActorDefinitionGroup::LoadActorResult`
Offset | Type | Name
-|-|-|-
0 | (4) `ActorDefinitionGroup::LoadStatus` | mLoadStatus
4 | (1) `bool` | mIsVanillaOverride


### `ActorFilterGroup::LegacyMapping`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterGroup::CollectionType` | mType
8 | (8) `const FilterTest::Definition *` | mFilterDef
16 | (2) `_BYTE[2]` | mSubject
18 | (2) `FilterOperator` | mOperator
20 | (4) `ActorFilterGroup::Processing` | mProcess


### `AttackCooldownComponent`
Offset | Type | Name
-|-|-|-
0 | (328) `AttackCooldownComponent::AttackCooldownDefinition` | mDefinition
328 | (8) `Tick` | mCompleteTick
336 | (1) `bool` | mHasExecuted


### `AttackCooldownComponent::AttackCooldownDefinition`
Offset | Type | Name
-|-|-|-
0 | (8) `FloatRange` | mCooldownTime
8 | (320) `DefinitionTrigger` | mOnAttackCooldownComplete


### `AttributeModifier`
Offset | Type | Name
-|-|-|-
0 | (8) `AttributeModifier_vtbl *` | __vftable
8 | (4) `float` | mAmount
12 | (4) `AttributeModifierOperation` | mOperation
16 | (4) `AttributeOperands` | mOperand
24 | (32) `std::string` | mName
56 | (16) `mce::UUID` | mId
72 | (1) `bool` | mSerialize


### `AudioEmitterComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mNewEventsToPlay


### `ActorParticleEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (320) `ActorParticleEffect` | mParticleEffect
320 | (4) `float` | mTime


### `ActorParticleEffect`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mParticleEffectName
48 | (48) `HashedString` | mLocatorName
96 | (216) `ExpressionNode` | mInitializationScripts
312 | (1) `bool` | mBindToActor


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l19::<lambda_f463c7f69e96408b25842593aed256a2>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l19::<lambda_c341de787fdc48a2e7d910ecf4a22a0a>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_058fc17591cd0bd6a0f83d3b263166d2>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_fb53a5a49dc70756315c0992afebf9b5>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_74ac4a6a93eb10d1347a9cdf648b096b>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_b730125b3c7101955e1af535390e025e>`
Offset | Type | Name
-|-|-|-


### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_8612c98d7f0c815faee88190a6dab7c7>`
Offset | Type | Name
-|-|-|-


### `AutoPlaceItem`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | collection
32 | (1) `bool` | stopWhenPlaced


### `ActorKilledEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mActorContext
24 | (8) `gsl::not_null<ActorDamageSource const *>` | mSource


### `ActorAddEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mActor
24 | (36) `const MobEffectInstance` | mMobEffect
60 | (1) `ActorAddEffectEvent::EffectState` | mEffectState


### `ActorRemoveEffectEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mActor
24 | (36) `const MobEffectInstance` | mMobEffect


### `ActorHasComponentTest`
Offset | Type | Name
-|-|-|-
0 | (64) `SimpleHashStringFilterTest` | baseclass_0


### `ActorIsFamilyTest`
Offset | Type | Name
-|-|-|-
0 | (64) `SimpleHashStringFilterTest` | baseclass_0


### `ActorHasAbilityTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorHasDamageTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorIsColorTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorIsOwnerTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsTargetTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsImmobileTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasTargetTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasRangedWeaponTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsLeashedToTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsMovingTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsSneakingTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsClimbingTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsRidingTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorRiderCountTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorInCaravanTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsLeashedTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsVariantTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorIsMarkVariantTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorIsSkinIDTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `ActorHasTagTest`
Offset | Type | Name
-|-|-|-
0 | (64) `SimpleHashStringFilterTest` | baseclass_0


### `ActorTrustsSubjectTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsAvoidingMobsTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorInVillageTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorIsVisibleTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `ActorHasMobEffect`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (8) `MobEffect *` | mMobEffect


### `ActorIsSleepingTest`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `AppendOnlyAtomicLookupTable<SubChunk,32>`
Offset | Type | Name
-|-|-|-
0 | (1792) `std::_Align_type<double,56>[32]` | mArray
1792 | (8) `std::atomic<unsigned __int64>` | mSize
1800 | (32) `SpinLock` | mAppendLock


### `AABBContactPoint`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mNormalIndex
4 | (4) `float` | mSignedPenetration
8 | (12) `Vec3` | mNormal


### `AppPlatform::sendMessageToJs::__l2::<lambda_369424be6eec29044240c817c2cdbc0c>`
Offset | Type | Name
-|-|-|-
0 | (8) `AppPlatform *const` | __this
8 | (32) `const std::string` | str


### `ActorShaderManager`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorShaderManager_vtbl *` | __vftable
8 | (16) `mce::MaterialPtr` | mEntityMaterial
24 | (16) `mce::MaterialPtr` | mTransparentEntityMaterial
40 | (16) `mce::MaterialPtr` | mStaticMaterial


### `AABBComponentNode`
Offset | Type | Name
-|-|-|-
0 | (28) `AABB` | aabb
32 | (216) `ExpressionNode` | condition


### `AddClientData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isConfirmation


### `ADDRINFOA`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | ai_flags
4 | (4) `int` | ai_family
8 | (4) `int` | ai_socktype
12 | (4) `int` | ai_protocol
16 | (8) `unsigned __int64` | ai_addrlen
24 | (8) `char *` | ai_canonname
32 | (8) `sockaddr *` | ai_addr
40 | (8) `addrinfo *` | ai_next


### `AF_GlyphHintsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_MemoryRec_ *` | memory
8 | (4) `int` | x_scale
12 | (4) `int` | x_delta
16 | (4) `int` | y_scale
20 | (4) `int` | y_delta
24 | (4) `int` | max_points
28 | (4) `int` | num_points
32 | (8) `AF_PointRec_ *` | points
40 | (4) `int` | max_contours
44 | (4) `int` | num_contours
48 | (8) `AF_PointRec_ **` | contours
56 | (4400) `AF_AxisHintsRec_[2]` | axis
4456 | (4) `unsigned int` | scaler_flags
4460 | (4) `unsigned int` | other_flags
4464 | (8) `AF_StyleMetricsRec_ *` | metrics
4472 | (4) `int` | xmin_delta
4476 | (4) `int` | xmax_delta
4480 | (4672) `struct {AF_PointRec_ *contours[8];AF_PointRec_ points[96];}` | embedded


### `AF_AxisHintsRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | num_segments
4 | (4) `int` | max_segments
8 | (8) `AF_SegmentRec_ *` | segments
16 | (4) `int` | num_edges
20 | (4) `int` | max_edges
24 | (8) `AF_EdgeRec_ *` | edges
32 | (4) `AF_Direction_` | major_dir
40 | (2160) `struct {AF_SegmentRec_ segments[18];AF_EdgeRec_ edges[12];}` | embedded


### `AF_SegmentRec_`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | flags
1 | (1) `char` | dir
2 | (2) `__int16` | pos
4 | (2) `__int16` | delta
6 | (2) `__int16` | min_coord
8 | (2) `__int16` | max_coord
10 | (2) `__int16` | height
16 | (8) `AF_EdgeRec_ *` | edge
24 | (8) `AF_SegmentRec_ *` | edge_next
32 | (8) `AF_SegmentRec_ *` | link
40 | (8) `AF_SegmentRec_ *` | serif
48 | (4) `int` | score
52 | (4) `int` | len
56 | (8) `AF_PointRec_ *` | first
64 | (8) `AF_PointRec_ *` | last


### `AF_EdgeRec_`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | fpos
4 | (4) `int` | opos
8 | (4) `int` | pos
12 | (1) `unsigned __int8` | flags
13 | (1) `char` | dir
16 | (4) `int` | scale
24 | (8) `AF_WidthRec_ *` | blue_edge
32 | (8) `AF_EdgeRec_ *` | link
40 | (8) `AF_EdgeRec_ *` | serif
48 | (4) `int` | score
56 | (8) `AF_SegmentRec_ *` | first
64 | (8) `AF_SegmentRec_ *` | last


### `AF_PointRec_`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | flags
2 | (1) `char` | in_dir
3 | (1) `char` | out_dir
4 | (4) `int` | ox
8 | (4) `int` | oy
12 | (2) `__int16` | fx
14 | (2) `__int16` | fy
16 | (4) `int` | x
20 | (4) `int` | y
24 | (4) `int` | u
28 | (4) `int` | v
32 | (8) `AF_PointRec_ *` | next
40 | (8) `AF_PointRec_ *` | prev


### `AF_WarperRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x1
4 | (4) `int` | x2
8 | (4) `int` | t1
12 | (4) `int` | t2
16 | (4) `int` | x1min
20 | (4) `int` | x1max
24 | (4) `int` | x2min
28 | (4) `int` | x2max
32 | (4) `int` | w0
36 | (4) `int` | wmin
40 | (4) `int` | wmax
44 | (4) `int` | best_scale
48 | (4) `int` | best_delta
52 | (4) `int` | best_score
56 | (4) `int` | best_distort


### `AF_LoaderRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_FaceRec_ *` | face
8 | (8) `AF_FaceGlobalsRec_ *` | globals
16 | (8) `AF_GlyphHintsRec_ *` | hints
24 | (8) `AF_StyleMetricsRec_ *` | metrics
32 | (1) `unsigned __int8` | transformed
36 | (16) `FT_Matrix_` | trans_matrix
52 | (8) `FT_Vector_` | trans_delta
60 | (8) `FT_Vector_` | pp1
68 | (8) `FT_Vector_` | pp2


### `AFM_ValueRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `AFM_ValueType_` | type
8 | (8) `union {char *s;int f;int i;unsigned int u;unsigned __int8 b;}` | u


### `AutoNumber`
Offset | Type | Name
-|-|-|-
0 | (4) `AutoNumberState` | an_state
4 | (4) `int` | an_field_number


### `assembler`
Offset | Type | Name
-|-|-|-
0 | (8) `_object *` | a_bytecode
8 | (4) `int` | a_offset
12 | (4) `int` | a_nblocks
16 | (8) `basicblock_ **` | a_postorder
24 | (8) `_object *` | a_lnotab
32 | (4) `int` | a_lnotab_off
36 | (4) `int` | a_lineno
40 | (4) `int` | a_lineno_off


### `AddRiderComponent`
Offset | Type | Name
-|-|-|-
0 | (176) `ActorDefinitionIdentifier` | mRiderType


### `AttributeInstance_vtbl`
```
struct /*VFT*/ AttributeInstance_vtbl
{
  void (__fastcall *~AttributeInstance)(AttributeInstance *this);
  void (__fastcall *tick)(AttributeInstance *this, Actor *);
};

```

### `AttributeInstanceHandle`
```
struct AttributeInstanceHandle
{
  unsigned int mAttributeID;
  BaseAttributeMap *mAttributeMap;
};

```

### `AttributeModifier_vtbl`
```
struct /*VFT*/ AttributeModifier_vtbl
{
  void (__fastcall *~AttributeModifier)(AttributeModifier *this);
  bool (__fastcall *isInstantaneous)(AttributeModifier *this);
};

```

### `Amplifier`
```
struct __cppobj Amplifier
{
  Amplifier_vtbl *__vftable /*VFT*/;
};

```

### `Amplifier_vtbl`
```
struct /*VFT*/ Amplifier_vtbl
{
  void (__fastcall *~Amplifier)(Amplifier *this);
  float (__fastcall *getAmount)(Amplifier *this, int, float);
  bool (__fastcall *shouldBuff)(Amplifier *this, int, int);
  int (__fastcall *getTickInterval)(Amplifier *this, int);
};

```

### `AttributeBuff_vtbl`
```
struct /*VFT*/ AttributeBuff_vtbl
{
  void (__fastcall *~AttributeBuff)(AttributeBuff *this);
  bool (__fastcall *isInstantaneous)(AttributeBuff *this);
  bool (__fastcall *isSerializable)(AttributeBuff *this);
  void (__fastcall *setDurationAmplifier)(AttributeBuff *this, std::shared_ptr<Amplifier>);
};

```

### `AttributeInstanceDelegate`
```
struct __cppobj AttributeInstanceDelegate
{
  AttributeInstanceDelegate_vtbl *__vftable /*VFT*/;
  AttributeInstanceHandle mAttributeHandle;
};

```

### `AttributeInstanceDelegate_vtbl`
```
struct /*VFT*/ AttributeInstanceDelegate_vtbl
{
  void (__fastcall *~AttributeInstanceDelegate)(AttributeInstanceDelegate *this);
  void (__fastcall *tick)(AttributeInstanceDelegate *this);
  void (__fastcall *notify)(AttributeInstanceDelegate *this, __int64);
  bool (__fastcall *change)(AttributeInstanceDelegate *this, float, float, AttributeBuffInfo);
  float (__fastcall *getBuffValue)(AttributeInstanceDelegate *this, const AttributeBuff *);
};

```

### `ActorDamageSource_vtbl`
```
struct /*VFT*/ ActorDamageSource_vtbl
{
  void (__fastcall *~ActorDamageSource)(ActorDamageSource *this);
  bool (__fastcall *isEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isChildEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isBlockSource)(ActorDamageSource *this);
  bool (__fastcall *isFire)(ActorDamageSource *this);
  std::pair<std::string,std::vector<std::string> > *(__fastcall *getDeathMessage)(ActorDamageSource *this, std::pair<std::string,std::vector<std::string> > *result, std::string, Actor *);
  bool (__fastcall *getIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getEntityCategories)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getDamagingEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getDamagingEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getDamagingEntityCategories)(ActorDamageSource *this);
  std::unique_ptr<ActorDamageSource> *(__fastcall *clone)(ActorDamageSource *this, std::unique_ptr<ActorDamageSource> *result);
};

```

### `AsynchronousIPResolver::ResolvedIp`
```
struct __cppobj __declspec(align(8)) AsynchronousIPResolver::ResolvedIp
{
  std::string ip;
  std::atomic<bool> ready;
};

```

### `AsyncTracker`
```
struct __cppobj AsyncTracker
{
  bool isCurrentWaitingOnCall;
  bool mWasCallAborted;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > operationStartTime;
  std::chrono::duration<__int64,std::ratio<1,1> > timeLimit;
  bool mHasRetryBeenRequested;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mRetryTime;
};

```

### `AnimateEntityPacket`
```
const struct __cppobj __declspec(align(8)) AnimateEntityPacket : Packet
{
  std::vector<ActorRuntimeID> mRuntimeIds;
  std::string mAnimation;
  std::string mNextState;
  std::string mStopExpression;
  std::string mController;
  float mBlendOutTime;
};

```

### `AnimateEntityPacket_vtbl`
```
struct /*VFT*/ AnimateEntityPacket_vtbl
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

### `AnvilDamagePacket`
```
const struct __cppobj AnvilDamagePacket : Packet
{
  int mDamage;
  NetworkBlockPosition mPosition;
};

```

### `AnvilDamagePacket_vtbl`
```
struct /*VFT*/ AnvilDamagePacket_vtbl
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

### `AvailableActorIdentifiersPacket`
```
const struct __cppobj AvailableActorIdentifiersPacket : Packet
{
  std::vector<ActorInfo> mIdentifierList;
};

```

### `AvailableActorIdentifiersPacket_vtbl`
```
struct /*VFT*/ AvailableActorIdentifiersPacket_vtbl
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

### `AutomationClientConnectPacket`
```
const struct __cppobj AutomationClientConnectPacket : Packet
{
  WebSocketPacketData mWebSocketData;
};

```

### `AutomationClientConnectPacket_vtbl`
```
struct /*VFT*/ AutomationClientConnectPacket_vtbl
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

### `AddBehaviorTreePacket`
```
const struct __cppobj AddBehaviorTreePacket : Packet
{
  std::string mJsonInput;
};

```

### `AddBehaviorTreePacket_vtbl`
```
struct /*VFT*/ AddBehaviorTreePacket_vtbl
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

### `AvailableCommandsPacket_vtbl`
```
struct /*VFT*/ AvailableCommandsPacket_vtbl
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

### `AnimatePacket`
```
const struct __cppobj AnimatePacket : Packet
{
  ActorRuntimeID mRuntimeId;
  ActorUniqueID mAttackId;
  AnimatePacket::Action mAction;
  float mData;
};

```

### `AnimatePacket_vtbl`
```
struct /*VFT*/ AnimatePacket_vtbl
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

### `AdventureSettingsPacket_vtbl`
```
struct /*VFT*/ AdventureSettingsPacket_vtbl
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

### `ActorEventPacket`
```
const struct __cppobj ActorEventPacket : Packet
{
  ActorRuntimeID mRuntimeId;
  ActorEvent mEventId;
  int mData;
};

```

### `ActorEventPacket_vtbl`
```
struct /*VFT*/ ActorEventPacket_vtbl
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

### `ActorPickRequestPacket`
```
const struct __cppobj __declspec(align(8)) ActorPickRequestPacket : Packet
{
  __int64 mID;
  unsigned __int8 mMaxSlots;
};

```

### `ActorPickRequestPacket_vtbl`
```
struct /*VFT*/ ActorPickRequestPacket_vtbl
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

### `ActorBlockSyncMessage`
```
struct __cppobj __declspec(align(8)) ActorBlockSyncMessage
{
  ActorUniqueID mEntityUniqueID;
  _BYTE mMessage[4];
};

```

### `AddActorBasePacket`
```
struct __cppobj AddActorBasePacket : Packet
{
};

```

### `AddActorBasePacket_vtbl`
```
struct /*VFT*/ AddActorBasePacket_vtbl
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

### `AddPlayerPacket`
```
const struct __cppobj AddPlayerPacket : AddActorBasePacket
{
  std::vector<ActorLink> mLinks;
  std::string mName;
  mce::UUID mUuid;
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  std::string mPlatformOnlineId;
  Vec3 mPos;
  Vec3 mVelocity;
  Vec2 mRot;
  float mYHeadRot;
  ItemStack mCarriedItem;
  std::vector<std::unique_ptr<DataItem>> mUnpack;
  Abilities mAbilities;
  std::string mDeviceId;
  std::string mModelName;
  std::string mModelTexture;
  bool mUseModelSkin;
  bool sendNotify;
  BuildPlatform mBuildPlatform;
  const SynchedActorData *mEntityData;
};

```

### `AddPlayerPacket_vtbl`
```
struct /*VFT*/ AddPlayerPacket_vtbl
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

### `AddEntityPacket`
```
const struct __cppobj AddEntityPacket : EntityServerPacket
{
};

```

### `AddEntityPacket_vtbl`
```
struct /*VFT*/ AddEntityPacket_vtbl
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

### `AddActorPacket`
```
const struct __cppobj AddActorPacket : AddActorBasePacket
{
  std::vector<ActorLink> mLinks;
  Vec3 mPos;
  Vec3 mVelocity;
  Vec2 mRot;
  float mYHeadRotation;
  std::string mScriptId;
  std::string mModelName;
  std::string mModelTexture;
  bool mUseModelSkin;
  bool mIsAiClosed;
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  SynchedActorData *mEntityData;
  std::vector<std::unique_ptr<DataItem>> mData;
  ActorDefinitionIdentifier mType;
  std::vector<AttributeInstanceHandle> mAttributeHandles;
  std::vector<SyncedAttribute> mAttributes;
};

```

### `AddActorPacket_vtbl`
```
struct /*VFT*/ AddActorPacket_vtbl
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

### `AddPaintingPacket`
```
const struct __cppobj AddPaintingPacket : AddActorBasePacket
{
  ActorUniqueID mEntityId;
  ActorRuntimeID mRuntimeId;
  Vec3 mPos;
  int mDir;
  std::string mMotive;
};

```

### `AddPaintingPacket_vtbl`
```
struct /*VFT*/ AddPaintingPacket_vtbl
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

### `AddItemActorPacket`
```
const struct __cppobj __declspec(align(8)) AddItemActorPacket : AddActorBasePacket
{
  std::vector<std::unique_ptr<DataItem>> mData;
  SynchedActorData *mEntityData;
  ActorUniqueID mId;
  ActorRuntimeID mRuntimeId;
  ItemStack mItem;
  Vec3 mPos;
  Vec3 mVelocity;
  bool mIsFromFishing;
};

```

### `AddItemActorPacket_vtbl`
```
struct /*VFT*/ AddItemActorPacket_vtbl
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

### `AppPlatformListener_vtbl`
```
struct /*VFT*/ AppPlatformListener_vtbl
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
};

```

### `AchievementData`
```
struct __cppobj AchievementData
{
  std::string mId;
  std::string mAchievementName;
  std::string mDescription;
  std::string mGamerScore;
  std::vector<std::string> mInGameRewardIds;
  __int64 mDateUnlocked;
  Core::PathBuffer<std::string > mImagePath;
  bool mIsLocked;
  bool mIsSecret;
  int mWorldScore;
  float mProgressCompleted;
  float mProgressTarget;
  __int64 _mDateUnlocked;
};

```

### `ArmorStand`
```
const struct __cppobj ArmorStand : Mob
{
  unsigned __int64 mLastHit;
  int mPoseIndex;
  int mLastCircuitStrength;
};

```

### `ActorGriefingBlockEvent`
```
const struct __cppobj __declspec(align(8)) ActorGriefingBlockEvent
{
  WeakRefT<EntityRefTraits> mActorContext;
  gsl::not_null<Block const *> mBlock;
  Vec3 mPos;
};

```

### `ActorEventListener_vtbl`
```
struct /*VFT*/ ActorEventListener_vtbl
{
  void (__fastcall *~ActorEventListener)(ActorEventListener *this);
  EventResult (__fastcall *onActorAttack)(ActorEventListener *this, Actor *, Actor *, int);
  EventResult (__fastcall *onActorHit)(ActorEventListener *this, Actor *, const ActorDamageSource *, int *, bool *, bool *);
  EventResult (__fastcall *onActorHurt)(ActorEventListener *this, const ActorHurtEvent *);
  EventResult (__fastcall *onActorMove)(ActorEventListener *this, Actor *, const Vec3 *);
  EventResult (__fastcall *onActorPredictedMove)(ActorEventListener *this, Actor *, MovePredictionType, const Vec3 *);
  EventResult (__fastcall *onActorTick)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorSneakChanged)(ActorEventListener *this, Actor *, bool);
  EventResult (__fastcall *onActorStartRiding)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorStopRiding)(ActorEventListener *this, Actor *, bool, bool, bool);
  EventResult (__fastcall *onActorDeath)(ActorEventListener *this, Actor *, const ActorDamageSource *, ActorType);
  EventResult (__fastcall *onActorDefinitionEventTriggered)(ActorEventListener *this, const ActorDefinitionEvent *);
  EventResult (__fastcall *onActorUseItem)(ActorEventListener *this, const ActorUseItemEvent *);
  EventResult (__fastcall *onActorUseItemOn)(ActorEventListener *this, Actor *, const ItemStack *, const BlockPos *, unsigned __int8);
  EventResult (__fastcall *onActorCreated)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onProjectileHit)(ActorEventListener *this, const ProjectileHitEvent *);
  EventResult (__fastcall *onActorTeleported)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorAttackedActor)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorAcquiredItem)(ActorEventListener *this, const ActorAcquiredItemEvent *);
  EventResult (__fastcall *onActorPlacedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorDroppedItem)(ActorEventListener *this, Actor *, const ItemInstance *);
  EventResult (__fastcall *onActorCarriedItemChanged)(ActorEventListener *this, Actor *, const ItemInstance *, const ItemInstance *, HandSlot);
  EventResult (__fastcall *onActorEquippedArmor)(ActorEventListener *this, Actor *, const ItemInstance *, ArmorSlot);
  EventResult (__fastcall *onActorRemoved)(ActorEventListener *this, Actor *);
  EventResult (__fastcall *onActorMobInteraction)(ActorEventListener *this, Actor *, MinecraftEventing::InteractionType, ActorType);
  EventResult (__fastcall *onActorTargetAcquired)(ActorEventListener *this, Actor *, Actor *);
  EventResult (__fastcall *onActorGriefingBlock)(ActorEventListener *this, const ActorGriefingBlockEvent *);
  EventResult (__fastcall *onActorAddEffect)(ActorEventListener *this, const ActorAddEffectEvent *);
  EventResult (__fastcall *onActorKilled)(ActorEventListener *this, const ActorKilledEvent *);
  EventResult (__fastcall *onActorRemoveEffect)(ActorEventListener *this, const ActorRemoveEffectEvent *);
  EventResult (__fastcall *onKnockBack)(ActorEventListener *this, const KnockBackEvent *);
  EventResult (__fastcall *onMountTaming)(ActorEventListener *this, const MountTamingEvent *);
  EventResult (__fastcall *onActorAnimationChanged)(ActorEventListener *this, const ActorAnimationChangedEvent *);
  EventResult (__fastcall *onSendActorAddBuff)(ActorEventListener *this, Actor *, const AttributeInstance *, const std::string *, int, bool, int, int, int);
};

```

### `AllowListEntry_vtbl`
```
struct /*VFT*/ AllowListEntry_vtbl
{
  void (__fastcall *~IJsonSerializable)(IJsonSerializable *this);
  void (__fastcall *serialize)(IJsonSerializable *this, Json::Value *);
  void (__fastcall *deserialize)(IJsonSerializable *this, Json::Value *);
};

```

### `AllowList_vtbl`
```
struct /*VFT*/ AllowList_vtbl
{
  void (__fastcall *~IJsonSerializable)(IJsonSerializable *this);
  void (__fastcall *serialize)(IJsonSerializable *this, Json::Value *);
  void (__fastcall *deserialize)(IJsonSerializable *this, Json::Value *);
};

```

### `AutomationCmdOutput`
```
struct __cppobj AutomationCmdOutput
{
  mce::UUID mUUID;
  Json::Value mJsonOutput;
  bool mContainsErrors;
  std::vector<std::string> mErrorMessages;
};

```

### `Automation::AutomationObserver`
```
struct __cppobj Automation::AutomationObserver : Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>
{
};

```

### `Automation::AutomationObserver_vtbl`
```
struct /*VFT*/ Automation::AutomationObserver_vtbl
{
  void (__fastcall *~Observer<Automation::AutomationObserver,Core::SingleThreadedLock>)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onConnected)(Automation::AutomationObserver *this, const std::string *);
  void (__fastcall *onConnectionFailed)(Automation::AutomationObserver *this, const std::string *);
  void (__fastcall *onConnectionClosed)(Automation::AutomationObserver *this);
  void (__fastcall *onDuplicateRequestCancel)(Automation::AutomationObserver *this);
};

```

### `Automation::AutomationClient`
```
struct __cppobj Automation::AutomationClient : UriListener, LevelListener
{
  IMinecraftApp *mApp;
  MPMCQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value> > mSlashQueue;
  unsigned __int64 mMaxQueueSize;
  int mMaxRetries;
  bool mIsEncryptionRequired;
  float mServerRetryTime;
  bool mIsInGame;
  std::vector<std::weak_ptr<Automation::AutomationSession>> mSessions;
  std::shared_ptr<Automation::AutomationSession> mDefaultSession;
  std::unordered_map<std::string,unsigned __int64> mRequestIdToSession;
  std::recursive_mutex mSessionMutex;
};

```

### `Automation::AutomationSession`
```
struct __cppobj Automation::AutomationSession : WebviewObserver, std::enable_shared_from_this<Automation::AutomationSession>
{
  RakWebSocketClient mClient;
  std::set<std::string> mSubscribedEvents;
  std::unordered_set<std::string> mPendingCommands;
  Core::Subject<Automation::AutomationObserver,Core::SingleThreadedLock> mEventSubject;
  std::string mLastServerUri;
  bool mWasLastConnectionLost;
  int mReconnAttempts;
  float mElapsed;
  std::atomic<bool> mIsConnecting;
  std::unique_ptr<Crypto::Symmetric::Symmetric> mEncryption;
  std::string mEncryptionRequestId;
  std::function<void __cdecl(std::string const &)> mLocalConnectionHandler;
  Automation::AutomationClient *mOwner;
};

```

### `Automation::AutomationSession_vtbl`
```
struct /*VFT*/ Automation::AutomationSession_vtbl
{
  void (__fastcall *~Observer<WebviewObserver,Core::SingleThreadedLock>)(Core::Observer<WebviewObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<WebviewObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onLoadingBegin)(WebviewObserver *this);
  void (__fastcall *onLoadingEnd)(WebviewObserver *this);
  void (__fastcall *onError)(WebviewObserver *this, const WebviewError *);
  void (__fastcall *onDownloadBegin)(WebviewObserver *this, const WebviewDownloadInfo *);
  void (__fastcall *onDownloadUpdate)(WebviewObserver *this, const WebviewDownloadInfo *);
  void (__fastcall *onDownloadComplete)(WebviewObserver *this, const WebviewDownloadInfo *);
  void (__fastcall *onDownloadCanceled)(WebviewObserver *this, const WebviewDownloadInfo *);
  void (__fastcall *onMessageRecieved)(WebviewObserver *this, const std::string *);
};

```

### `Automation::AutomationClient_vtbl`
```
struct /*VFT*/ Automation::AutomationClient_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `AchievementOfferInfo`
```
struct __cppobj AchievementOfferInfo
{
  _BYTE mAchievementTitleId[4];
};

```

### `AnimatedTextureDefinition`
```
struct __cppobj __declspec(align(8)) AnimatedTextureDefinition
{
  _BYTE mType[4];
  _BYTE mAnimationExpression[4];
  std::string mGeoID;
  std::string mTextureID;
  unsigned int mTextureWidth;
  unsigned int mTextureHeight;
  float mFrames;
};

```

### `AtlasItemManager`
```
struct __cppobj AtlasItemManager
{
  std::unordered_map<std::string,TextureAtlasItem> mTextureAtlasItems;
  std::vector<TextureAtlasItemTextureSetTranslation> mTextureAtlasItemTextureSetTranslations;
};

```

### `AsepriteFrameInformation`
```
struct __cppobj AsepriteFrameInformation
{
  int xSource;
  int ySource;
  int msDuration;
};

```

### `AbstractScene`
```
struct __cppobj AbstractScene
{
  AbstractScene_vtbl *__vftable /*VFT*/;
};

```

### `AllocatorData`
```
struct __cppobj AllocatorData
{
  unsigned __int64 mTotalBlocks;
  unsigned __int64 mTotalCapacity;
  unsigned __int64 mTotalSize;
  std::forward_list<MemBlock> mBlocks;
};

```

### `AbstractSceneProxy`
```
struct __cppobj AbstractSceneProxy
{
  const AbstractSceneProxyCallbacks mCallbacks;
};

```

### `AbstractScene_vtbl`
```
struct /*VFT*/ AbstractScene_vtbl
{
  void (__fastcall *~AbstractScene)(AbstractScene *this);
  void (__fastcall *OnMessage)(AbstractScene *this, UIMessage, std::string, std::vector<std::shared_ptr<MessageParam>>);
  std::shared_ptr<UIControl> *(__fastcall *getRootControl)(AbstractScene *this, std::shared_ptr<UIControl> *result);
  std::shared_ptr<UIControlFactory> *(__fastcall *getControlFactory)(AbstractScene *this, std::shared_ptr<UIControlFactory> *result);
  bool (__fastcall *isShowingModUI)(AbstractScene *this);
  void (__fastcall *setIsShowingModUI)(AbstractScene *this, bool);
  bool (__fastcall *isUIScene)(AbstractScene *this);
  void (__fastcall *init)(AbstractScene *this, const ScreenSizeData *);
  void (__fastcall *setSize)(AbstractScene *this, const ScreenSizeData *);
  void (__fastcall *onSetKeyboardHeight)(AbstractScene *this, float);
  void (__fastcall *onInternetUpdate)(AbstractScene *this);
  std::vector<RectangleArea> *(__fastcall *getInputAreas)(AbstractScene *this, std::vector<RectangleArea> *result);
  void (__fastcall *onFocusGained)(AbstractScene *this);
  void (__fastcall *onFocusLost)(AbstractScene *this);
  void (__fastcall *terminate)(AbstractScene *this);
  void (__fastcall *onCreation)(AbstractScene *this);
  void (__fastcall *onLeave)(AbstractScene *this);
  void (__fastcall *onGameEventNotification)(AbstractScene *this, ui::GameEventNotification);
  void (__fastcall *_handleDirtyVisualTree)(AbstractScene *this, bool);
  void (__fastcall *leaveScreen)(AbstractScene *this);
  void (__fastcall *tick)(AbstractScene *this, int, int);
  void (__fastcall *updateEvents)(AbstractScene *this);
  void (__fastcall *applyInput)(AbstractScene *this, float);
  void (__fastcall *update)(AbstractScene *this, long double);
  void (__fastcall *frameUpdate)(AbstractScene *this, MinecraftUIFrameUpdateContext *);
  void (__fastcall *preRenderUpdate)(AbstractScene *this, ScreenContext *);
  void (__fastcall *prepareFrame)(AbstractScene *this, ScreenContext *);
  void (__fastcall *render)(AbstractScene *this, ScreenContext *, const FrameRenderObject *);
  void (__fastcall *postRenderUpdate)(AbstractScene *this, ScreenContext *);
  void (__fastcall *setupAndRender)(AbstractScene *this, ScreenContext *);
  void (__fastcall *handleInputModeChanged)(AbstractScene *this, InputMode);
  void (__fastcall *handleHoloInputModeChanged)(AbstractScene *this, HoloUIInputMode);
  void (__fastcall *handleButtonPress)(AbstractScene *this, unsigned int, FocusImpact);
  void (__fastcall *handleButtonRelease)(AbstractScene *this, unsigned int, FocusImpact);
  void (__fastcall *handleRawInputEvent)(AbstractScene *this, int, RawInputType, ButtonState, bool);
  bool (__fastcall *handlePointerLocation)(AbstractScene *this, const PointerLocationEventData *, FocusImpact);
  void (__fastcall *handlePointerPressed)(AbstractScene *this, bool);
  void (__fastcall *handleDirection)(AbstractScene *this, DirectionId, float, float, FocusImpact);
  bool (__fastcall *handleBackEvent)(AbstractScene *this, bool);
  void (__fastcall *handleTextChar)(AbstractScene *this, const std::string *, bool, FocusImpact);
  void (__fastcall *handleCaretLocation)(AbstractScene *this, int, FocusImpact);
  void (__fastcall *setTextboxText)(AbstractScene *this, const std::string *);
  void (__fastcall *onKeyboardDismissed)(AbstractScene *this);
  void (__fastcall *onKeyboardDisabled)(AbstractScene *this);
  void (__fastcall *handleLicenseChanged)(AbstractScene *this);
  void (__fastcall *handleIdentityGained)(AbstractScene *this);
  void (__fastcall *handleIdentityLost)(AbstractScene *this);
  void (__fastcall *handleGazeGestureInput)(AbstractScene *this, __int16, float, float, float, FocusImpact);
  void (__fastcall *handleDictationEvent)(AbstractScene *this, const std::string *);
  void (__fastcall *handleCommandEvent)(AbstractScene *this, const VoiceCommand *);
  bool (__fastcall *renderGameBehind)(AbstractScene *this);
  bool (__fastcall *absorbsInput)(AbstractScene *this);
  bool (__fastcall *closeOnPlayerHurt)(AbstractScene *this);
  bool (__fastcall *isModal)(AbstractScene *this);
  bool (__fastcall *isShowingMenu)(AbstractScene *this);
  bool (__fastcall *shouldStealMouse)(AbstractScene *this);
  bool (__fastcall *screenIsNotFlushable)(AbstractScene *this);
  bool (__fastcall *alwaysAcceptsInput)(AbstractScene *this);
  bool (__fastcall *screenDrawsLast)(AbstractScene *this);
  bool (__fastcall *isPlayScreen)(AbstractScene *this);
  bool (__fastcall *renderOnlyWhenTopMost)(AbstractScene *this);
  bool (__fastcall *lowFreqRendering)(AbstractScene *this);
  bool (__fastcall *ignoreAsTop)(AbstractScene *this);
  bool (__fastcall *screenHandlesGamepadMenuButton)(AbstractScene *this);
  bool (__fastcall *shouldUpdateWhenSuspended)(AbstractScene *this);
  int (__fastcall *getWidth)(AbstractScene *this);
  int (__fastcall *getHeight)(AbstractScene *this);
  void (__fastcall *reload)(AbstractScene *this);
  const RectangleArea *(__fastcall *getRenderingAABB)(AbstractScene *this);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScene *this);
  ui::SceneType (__fastcall *getSceneType)(AbstractScene *this);
  std::string *(__fastcall *getScreenName)(AbstractScene *this, std::string *result);
  std::string *(__fastcall *getRoute)(AbstractScene *this, std::string *result);
  std::string *(__fastcall *getScreenTelemetryName)(AbstractScene *this, std::string *result);
  void (__fastcall *addEventProperties)(AbstractScene *this, std::unordered_map<std::string,std::string> *);
  int (__fastcall *getScreenVersion)(AbstractScene *this);
  void (__fastcall *processBufferedTextCharEvents)(AbstractScene *this, const std::vector<TextCharEventData> *);
  bool (__fastcall *getShouldSendEvents)(AbstractScene *this);
  void (__fastcall *setShouldSendEvents)(AbstractScene *this, bool);
  bool (__fastcall *getWantsTextOnly)(AbstractScene *this);
  void (__fastcall *setWantsTextOnly)(AbstractScene *this, bool);
  void (__fastcall *onDelete)(AbstractScene *this, CachedScenes *, TaskGroup *);
  bool (__fastcall *isGamepadCursorEnabled)(AbstractScene *this);
  bool (__fastcall *isGamepadDeflectionModeEnabled)(AbstractScene *this);
  const glm::tvec2<float,0> *(__fastcall *getGamepadCursorPosition)(AbstractScene *this);
  void (__fastcall *cleanInputComponents)(AbstractScene *this);
  std::weak_ptr<AbstractSceneProxy> *(__fastcall *getProxy)(AbstractScene *this, std::weak_ptr<AbstractSceneProxy> *result);
  bool (__fastcall *canBePushed)(AbstractScene *this);
  bool (__fastcall *canBePopped)(AbstractScene *this);
  bool (__fastcall *canBeTransitioned)(AbstractScene *this);
  void (__fastcall *onScreenExit)(AbstractScene *this, bool, bool);
  void (__fastcall *onScreenEntrance)(AbstractScene *this, bool, bool);
  bool (__fastcall *isEntering)(AbstractScene *this);
  bool (__fastcall *isExiting)(AbstractScene *this);
  void (__fastcall *schedulePop)(AbstractScene *this);
  bool (__fastcall *isTerminating)(AbstractScene *this);
  bool (__fastcall *loadScreenImmediately)(AbstractScene *this);
  bool (__fastcall *forceUpdateActiveSceneStackWhenPushed)(AbstractScene *this);
  bool (__fastcall *hasFinishedLoading)(AbstractScene *this);
  void (__fastcall *sendScreenEvent)(AbstractScene *this, const std::string *, const std::string *);
  void (__fastcall *setDebugFeature)(AbstractScene *this, UIDebugCommandFeature, bool);
  void (__fastcall *setScreenState)(AbstractScene *this, const std::vector<std::pair<std::string,std::string >> *);
};

```

### `AbstractScreenSetupCleanupStrategy`
```
struct __cppobj AbstractScreenSetupCleanupStrategy
{
  AbstractScreenSetupCleanupStrategy_vtbl *__vftable /*VFT*/;
};

```

### `AbstractScreenSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ AbstractScreenSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
};

```

### `ActorShaderManager_vtbl`
```
struct /*VFT*/ ActorShaderManager_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
};

```

### `ActorSoundEffect`
```
struct __cppobj ActorSoundEffect
{
  HashedString mSoundEffectName;
};

```

### `ActorSoundEffectEvent`
```
struct __cppobj __declspec(align(8)) ActorSoundEffectEvent
{
  ActorSoundEffect mSoundEffect;
  float mTime;
};

```

### `ActorAnimationEvent`
```
struct __cppobj __declspec(align(8)) ActorAnimationEvent
{
  ExpressionNode mExpression;
  HashedString mCommand;
  CurrentCmdVersion mCommandVersion;
  std::string mEvent;
  float mTime;
};

```

### `ActorSkeletalAnimation`
```
struct __cppobj ActorSkeletalAnimation
{
  HashedString mName;
  float mAnimationLength;
  AnimationLoopMode mLoopMode;
  bool mOverridePreviousAnimation;
  ExpressionNode mBlendWeight;
  ExpressionNode mStartDelayExpr;
  ExpressionNode mLoopDelayExpr;
  ExpressionNode mAnimTimeUpdate;
  std::vector<BoneAnimation> mBoneAnimations;
  std::vector<ActorParticleEffectEvent> mParticleEffectEvents;
  std::vector<ActorSoundEffectEvent> mSoundEffectEvents;
  std::vector<ActorAnimationEvent> mEvents;
  std::string mSourceFilePathWithExtension;
};

```

### `ActorAnimationInfo`
```
struct __cppobj ActorAnimationInfo
{
  HashedString mName;
  std::unique_ptr<ActorSkeletalAnimation> mPtr;
};

```

### `ActorAnimationGroup`
```
struct __cppobj ActorAnimationGroup
{
  std::unordered_map<HashedString,std::shared_ptr<ActorAnimationInfo>> mAnimations;
  std::mutex mActorAnimationMutex;
};

```

### `ActorAnimationBase`
```
struct __cppobj ActorAnimationBase
{
};

```

### `AnimationValueCurveKeyFrame`
```
struct __cppobj AnimationValueCurveKeyFrame
{
  float mInputValue;
  float mOutputValue;
};

```

### `ActorAnimationControllerStateTransition`
```
struct __cppobj ActorAnimationControllerStateTransition
{
  std::string mTargetStateName;
  unsigned __int64 mTargetStateIndex;
  ExpressionNode mTransitionExpression;
};

```

### `ActorAnimationControllerState`
```
struct __cppobj ActorAnimationControllerState : ActorAnimationBase
{
  HashedString mName;
  std::vector<StateAnimationVariable> mVariables;
  std::vector<std::pair<HashedString,ExpressionNode>> mAnimations;
  std::vector<ActorParticleEffect> mParticleEffects;
  std::vector<ActorAnimationEvent> mEvents[2];
  std::vector<ActorAnimationControllerStateTransition> mTransitions;
  std::vector<ActorSoundEffect> mSoundEffects;
  bool mBlendViaShortestPath;
  std::vector<AnimationValueCurveKeyFrame> mBlendTransitionKeyFrames;
};

```

### `ActorAnimationController`
```
struct __cppobj ActorAnimationController
{
  HashedString mName;
  unsigned __int64 mInitialStateIndex;
  std::vector<std::shared_ptr<ActorAnimationControllerState>> mStates;
  std::string mSourceFilePathWithExtension;
};

```

### `ActorAnimationControllerInfo`
```
struct __cppobj ActorAnimationControllerInfo
{
  HashedString mName;
  std::unique_ptr<ActorAnimationController> mPtr;
};

```

### `ActorAnimationControllerGroup`
```
struct __cppobj ActorAnimationControllerGroup
{
  std::unordered_map<HashedString,std::shared_ptr<ActorAnimationControllerInfo>> mAnimationControllers;
};

```

### `ActorTextureInfo`
```
struct __cppobj ActorTextureInfo
{
  ResourceLocation mResourceLocation;
  mce::TexturePtr mClientTexture;
};

```

### `AttachableItemOverride`
```
struct __cppobj AttachableItemOverride
{
  std::shared_ptr<ActorResourceDefinition> mAttachableResourceDefinition;
  ExpressionNode mFilterExpression;
};

```

### `ActorResourceDefinitionGroup`
```
const struct __cppobj ActorResourceDefinitionGroup
{
  GeometryGroup *mGeometryGroup;
  mce::TextureGroup *mTextureGroup;
  ActorAnimationGroup *mActorAnimationGroup;
  ActorAnimationControllerGroup *mActorAnimationControllerGroup;
  RenderControllerGroup *mRenderControllerGroup;
  std::unordered_map<HashedString,std::shared_ptr<ActorResourceDefinition>> _mEntityResourceDefinitions;
  std::unordered_map<HashedString,std::vector<AttachableItemOverride>> _mAttachableResourceOverridesByItemId;
};

```

### `AmbientSoundController`
```
struct __cppobj __declspec(align(8)) AmbientSoundController
{
  AmbientSoundController_vtbl *__vftable /*VFT*/;
  Actor *mActor;
  int mDelayUntilNextMoodSound;
};

```

### `AmbientSoundController_vtbl`
```
struct /*VFT*/ AmbientSoundController_vtbl
{
  void (__fastcall *~AmbientSoundController)(AmbientSoundController *this);
};

```

### `ActorHistory`
```
struct __cppobj ActorHistory
{
  const unsigned __int64 mHistoryWindow;
  std::deque<ActorHistory::Snapshot> mSnapshots;
  std::vector<std::unique_ptr<IReplayableActorStateSource>> mStateSources;
  unsigned __int64 mOldestFrame;
};

```

### `App`
```
struct __cppobj __declspec(align(8)) App : IApp, AppPlatformListener
{
  bool _inited;
  bool _finished;
};

```

### `App_vtbl`
```
struct /*VFT*/ App_vtbl
{
  void (__fastcall *~IApp)(IApp *this);
  void (__fastcall *quit)(IApp *this, const std::string *, const std::string *);
  bool (__fastcall *wantToQuit)(IApp *this);
  void (__fastcall *setUISizeAndScale)(IApp *this, int, int, float);
  void (__fastcall *muteAudio)(IApp *this);
  void (__fastcall *unMuteAudio)(IApp *this);
  void (__fastcall *audioEngineOn)(App *this);
  void (__fastcall *audioEngineOff)(App *this);
  void (__fastcall *destroy)(App *this);
  bool (__fastcall *useTouchscreen)(App *this);
  void (__fastcall *draw)(App *this);
  void (__fastcall *update)(App *this);
  void (__fastcall *setRenderingSize)(App *this, int, int);
  void (__fastcall *initImpl)(App *this);
};

```

### `ActiveDirectoryIdentityObserver`
```
struct __cppobj ActiveDirectoryIdentityObserver : Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>
{
};

```

### `AccessTokenInfo`
```
struct __cppobj AccessTokenInfo
{
  std::string email;
  __int64 expiration;
};

```

### `ActiveDirectoryPopup`
```
struct __cppobj __declspec(align(8)) ActiveDirectoryPopup
{
  std::string mId;
  std::string mTitle;
  std::string mPopupText;
  std::string mHyperlinkIntroText;
  std::string mHyperlinkLabelText;
  std::string mHyperlinkUri;
  ActiveDirectoryAction mPostPopupAction;
  ActiveDirectoryExperience mExperienceType;
};

```

### `ActiveDirectoryIdentity::ServiceResponse`
```
struct __cppobj __declspec(align(8)) ActiveDirectoryIdentity::ServiceResponse
{
  bool mIsValid;
  bool mHasAcceptedEula;
  bool mIsLicensed;
  bool mIsNewUser;
  ADRole mRole;
  std::string mName;
  std::string mSkin;
  std::string mTenantId;
  std::string mOid;
  std::string mNickname;
  std::string mShareableIdentityToken;
  std::string mDemoSessionId;
  AccessTokenInfo mAccessTokenInfo;
  std::optional<ActiveDirectoryPopup> mPopup;
  int mTrialsRemaining;
};

```

### `ActiveDirectoryPolicy`
```
struct __cppobj ActiveDirectoryPolicy
{
  ActiveDirectoryPolicy_vtbl *__vftable /*VFT*/;
};

```

### `ActiveDirectoryPolicy_vtbl`
```
struct /*VFT*/ ActiveDirectoryPolicy_vtbl
{
  void (__fastcall *~ActiveDirectoryPolicy)(ActiveDirectoryPolicy *this);
  ADDialogMode (__fastcall *getDialogMode)(ActiveDirectoryPolicy *this);
  EducationEditionOffer (__fastcall *getEducationOffer)(ActiveDirectoryPolicy *this);
  bool (__fastcall *shouldAttemptTokenRefresh)(ActiveDirectoryPolicy *this, const AccessTokenInfo *);
  void (__fastcall *onTokenRefreshAction)(ActiveDirectoryPolicy *this, ADTokenRefreshAction);
  void (__fastcall *onSignInAttempt)(ActiveDirectoryPolicy *this);
  void (__fastcall *onSignInSuccess)(ActiveDirectoryPolicy *this);
  void (__fastcall *resetAuthenticationState)(ActiveDirectoryPolicy *this);
};

```

### `ActiveDirectoryIdentity`
```
const struct __cppobj ActiveDirectoryIdentity : Bedrock::Threading::EnableQueueForMainThread
{
  ActiveDirectoryAuthenticationState mCurrentAuthenticationState;
  ActiveDirectoryIdentity::ServiceResponse mResponse;
  std::unique_ptr<ActiveDirectoryPolicy> mPolicy;
  std::unique_ptr<Core::Subject<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>> mSubject;
  std::unique_ptr<IActiveDirectoryIdentityTelemetry> mEventing;
  std::unique_ptr<ResponseVerifier> mVerifier;
};

```

### `ActiveDirectoryIdentity_vtbl`
```
struct /*VFT*/ ActiveDirectoryIdentity_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `ActiveDirectoryIdentityObserver_vtbl`
```
struct /*VFT*/ ActiveDirectoryIdentityObserver_vtbl
{
  void (__fastcall *~Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onIdentityGained)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityRefreshed)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityLost)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityExpired)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onConfigFetched)(ActiveDirectoryIdentityObserver *this, const EDUConfigData *);
};

```

### `AppConfigs`
```
struct __cppobj AppConfigs : Bedrock::EnableNonOwnerReferences
{
  AppConfigs_vtbl *__vftable /*VFT*/;
  std::function<bool __cdecl(LevelSummary const &)> mCanAccessWorldCallback;
  std::unique_ptr<ScreenCapabilitiesRepo> mScreenCapabilities;
  std::function<void __cdecl(SceneStack &,SceneFactory &)> mLeaveGameCallback;
};

```

### `AppConfigs_vtbl`
```
struct /*VFT*/ AppConfigs_vtbl
{
  void (__fastcall *~AppConfigs)(AppConfigs *this);
  void (__fastcall *loadFromData)(AppConfigs *this, const IAppConfigData *);
  bool (__fastcall *areResourcePacksAllowed)(AppConfigs *this);
  bool (__fastcall *isPlayScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isChatScreenAllowed)(AppConfigs *this);
  bool (__fastcall *isGameTabShownInSettings)(AppConfigs *this);
  bool (__fastcall *areQuizzesSupported)(AppConfigs *this);
  bool (__fastcall *isLessonProgressionSupported)(AppConfigs *this);
  bool (__fastcall *useNormalizedFontSize)(AppConfigs *this);
  bool (__fastcall *useFullScreenByDefault)(AppConfigs *this);
  bool (__fastcall *muteByDefault)(AppConfigs *this);
  bool (__fastcall *isCoursesCacheEnabled)(AppConfigs *this);
  bool (__fastcall *shouldPromptBeforeExit)(AppConfigs *this);
  bool (__fastcall *gameArgumentsNeedAuthentication)(AppConfigs *this);
  bool (__fastcall *worldBuilderDisabled)(AppConfigs *this);
  bool (__fastcall *worldsAreSingleUse)(AppConfigs *this);
  EducationEditionOffer (__fastcall *getEducationEditionOffering)(AppConfigs *this);
  bool (__fastcall *requireTrustedContent)(AppConfigs *this);
  ConnectionDefinition *(__fastcall *getConnectionDefinition)(AppConfigs *this, ConnectionDefinition *result);
  bool (__fastcall *supportsChangingMultiplayerDuringPlay)(AppConfigs *this);
  bool (__fastcall *webSocketsDisabled)(AppConfigs *this);
  bool (__fastcall *sendPermissionsTelemetry)(AppConfigs *this);
  void (__fastcall *setCanAccessWorldCallback)(AppConfigs *this, IMinecraftGame *);
  std::vector<PackIdVersion> *(__fastcall *getAdditionalClientPacks)(AppConfigs *this, std::vector<PackIdVersion> *result, bool);
  std::unique_ptr<IScreenCapabilities> *(__fastcall *getScreenCapabilities)(AppConfigs *this, std::unique_ptr<IScreenCapabilities> *result, const std::string *);
  std::unique_ptr<IContentAccessibilityProvider> *(__fastcall *createContentAccessibility)(AppConfigs *this, std::unique_ptr<IContentAccessibilityProvider> *result, IEntitlementManager *);
  std::string *(__fastcall *getFeedbackURL)(AppConfigs *this, std::string *result);
  void (__fastcall *applyLevelDataOverride)(AppConfigs *this, LevelData *);
};

```

### `ActivationRule`
```
struct __cppobj ActivationRule
{
  ActivationRule_vtbl *__vftable /*VFT*/;
  HashedString mId;
};

```

### `ActivationRule_vtbl`
```
struct /*VFT*/ ActivationRule_vtbl
{
  void (__fastcall *~ActivationRule)(ActivationRule *this);
  std::unique_ptr<ActivationRule> *(__fastcall *create)(ActivationRule *this, std::unique_ptr<ActivationRule> *result, Json::Value *);
  bool (__fastcall *evaluate)(ActivationRule *this, const IClientInstance *, float, const Camera *);
};

```

### `ActorRenderDispatcher`
```
struct __cppobj __declspec(align(8)) ActorRenderDispatcher
{
  ActorRenderDispatcher_vtbl *__vftable /*VFT*/;
  std::unordered_map<HashedString,std::unique_ptr<ActorRenderer>> mNonDataDrivenRenderers;
  std::unordered_map<HashedString,std::unique_ptr<DataDrivenRenderer>> mDataDrivenRenderers;
  std::vector<std::function<void __cdecl(ActorResourceDefinitionGroup const &,mce::TextureGroup *)>> mGameSpecificRegistrationCallbacks;
  unsigned __int8 mClientSubId;
};

```

### `ActorRenderDispatcher_vtbl`
```
struct /*VFT*/ ActorRenderDispatcher_vtbl
{
  void (__fastcall *~ActorRenderDispatcher)(ActorRenderDispatcher *this);
};

```

### `ActorAnimationPlayer`
```
struct __cppobj __declspec(align(8)) ActorAnimationPlayer
{
  ActorAnimationPlayer_vtbl *__vftable /*VFT*/;
  const HashedString mFriendlyName;
  const ExpressionNode mBlendExpression;
  bool mExpanded;
  bool mAnimationFinished;
};

```

### `AnimationComponent`
```
struct __cppobj __declspec(align(8)) AnimationComponent
{
  bool mKeepStates;
  const ActorAnimationControllerStatePlayer *mCurrentAnimationControllerStatePlayer;
  std::vector<std::unique_ptr<ActorAnimationPlayer>> mComponentAnimationPlayers;
  std::vector<std::shared_ptr<ActorAnimationControllerInfo>> mOwnedAnimationControllers;
  std::unordered_map<HashedString,ModelPartLocator> mModelPartLocators;
  RenderParams mRenderParams;
  ActorAnimationPlayer *mPlaySingleAnimation;
  void *mModelRenderControllerCacheWasBuiltFrom;
  std::shared_ptr<CommonResourceDefinitionMap> mCommonResourceDefinitionMap;
  const std::unordered_map<HashedString,ParticleEffectPtr> *mParticleEffectMap;
  std::function<void __cdecl(ActorAnimationPlayer &)> mAnimationComponentInitFunction;
  std::vector<AnimationComponent::ChildAnimationComponentInfo> mChildAnimationComponents;
  std::unordered_map<enum SkeletalHierarchyIndex,std::vector<BoneOrientation>> mBoneOrientations;
  bool mAnimationComponentInitialized;
  AnimationComponentGroup mAnimationComponentGroup;
  AnimationComponentID mOwnerUUID;
  __int64 mLastUpdateFrame;
  unsigned __int64 mLastReloadInitTimeStampClient;
  std::vector<RenderControllerToProcess> mRenderControllersToProcess;
  std::vector<enum SkeletalHierarchyIndex> mSkeletalHierarchiesToProcess;
  std::vector<Matrix> mQueryableBoneOrientations;
  bool mAreRenderControllersConstant;
  std::weak_ptr<DataDrivenModel const > mLastModelInitializedWith;
  bool mApplyAnimations;
  bool mNeedToUpdateQueryableBoneOrientations;
};

```

### `ActorAnimationPlayer_vtbl`
```
struct /*VFT*/ ActorAnimationPlayer_vtbl
{
  void (__fastcall *~ActorAnimationPlayer)(ActorAnimationPlayer *this);
  void (__fastcall *applyToPose)(ActorAnimationPlayer *this, RenderParams *, std::unordered_map<enum SkeletalHierarchyIndex,std::vector<BoneOrientation>> *, float);
  void (__fastcall *resetAnimation)(ActorAnimationPlayer *this);
  void (__fastcall *buildBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
  void (__fastcall *bindParticleEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,ParticleEffectPtr> *);
  void (__fastcall *bindSoundEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,std::string> *);
  bool (__fastcall *hasAnimationFinished)(ActorAnimationPlayer *this);
  ActorAnimationPlayer *(__fastcall *findAnimation)(ActorAnimationPlayer *this, const HashedString *);
  ActorAnimationType (__fastcall *getAnimationType)(ActorAnimationPlayer *this);
  void (__fastcall *updateBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
};

```

### `ActorAnimationControllerStatePlayer`
```
const struct __cppobj ActorAnimationControllerStatePlayer : ActorAnimationPlayer
{
  ActorAnimationControllerPlayer *mOwner;
  std::shared_ptr<ActorAnimationControllerState> mControllerState;
  std::vector<std::unique_ptr<ActorAnimationPlayer>> mAnimationPlayers;
  const Core::Profile::CPUProfileTokenMicroProfile mProfileToken;
};

```

### `ActorAnimationControllerPlayer`
```
struct __cppobj ActorAnimationControllerPlayer : ActorAnimationPlayer
{
  ActorAnimationControllerPtr mAnimationControllerPtr;
  int mCurrStateIndex;
  int mLastStateIndex;
  int mNextStateIndex;
  int mBlendTransitionStateIndex;
  float mBlendTransitionTime;
  std::vector<std::unique_ptr<ActorAnimationControllerStatePlayer>> mAnimationControllerStatePlayers;
  const std::unordered_map<HashedString,ParticleEffectPtr> *mActorParticleEffectMap;
  const std::unordered_map<HashedString,std::string> *mActorSoundEffectMap;
};

```

### `ActorAnimationControllerPlayer_vtbl`
```
struct /*VFT*/ ActorAnimationControllerPlayer_vtbl
{
  void (__fastcall *~ActorAnimationPlayer)(ActorAnimationPlayer *this);
  void (__fastcall *applyToPose)(ActorAnimationPlayer *this, RenderParams *, std::unordered_map<enum SkeletalHierarchyIndex,std::vector<BoneOrientation>> *, float);
  void (__fastcall *resetAnimation)(ActorAnimationPlayer *this);
  void (__fastcall *buildBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
  void (__fastcall *bindParticleEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,ParticleEffectPtr> *);
  void (__fastcall *bindSoundEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,std::string> *);
  bool (__fastcall *hasAnimationFinished)(ActorAnimationPlayer *this);
  ActorAnimationPlayer *(__fastcall *findAnimation)(ActorAnimationPlayer *this, const HashedString *);
  ActorAnimationType (__fastcall *getAnimationType)(ActorAnimationPlayer *this);
  void (__fastcall *updateBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
};

```

### `ActorAnimationControllerStatePlayer_vtbl`
```
struct /*VFT*/ ActorAnimationControllerStatePlayer_vtbl
{
  void (__fastcall *~ActorAnimationPlayer)(ActorAnimationPlayer *this);
  void (__fastcall *applyToPose)(ActorAnimationPlayer *this, RenderParams *, std::unordered_map<enum SkeletalHierarchyIndex,std::vector<BoneOrientation>> *, float);
  void (__fastcall *resetAnimation)(ActorAnimationPlayer *this);
  void (__fastcall *buildBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
  void (__fastcall *bindParticleEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,ParticleEffectPtr> *);
  void (__fastcall *bindSoundEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,std::string> *);
  bool (__fastcall *hasAnimationFinished)(ActorAnimationPlayer *this);
  ActorAnimationPlayer *(__fastcall *findAnimation)(ActorAnimationPlayer *this, const HashedString *);
  ActorAnimationType (__fastcall *getAnimationType)(ActorAnimationPlayer *this);
  void (__fastcall *updateBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
};

```

### `AnimationComponent::ChildAnimationComponentInfo`
```
struct __cppobj AnimationComponent::ChildAnimationComponentInfo
{
  const void *mChildObjectKey;
  MolangVariableMap mMolangVariableMap;
  std::shared_ptr<AnimationComponent> mChildAnimationComponent;
};

```

### `ActorRenderer`
```
struct __cppobj ActorRenderer : BaseActorRenderer
{
  bool mRenderingInventory;
  const bool mHasWaterHole;
  float mMinimumVRRenderDistance;
  mce::MaterialPtr mEntityAlphatestMaterial;
  mce::MaterialPtr mEntityAlphatestGlintMaterial;
  mce::MaterialPtr mModEntityAlphatestGlintMaterial;
  mce::TexturePtr mGlintTexture;
  mce::TexturePtr mAtlasTexture;
  mce::TextureGroup *mTextureGroup;
  AABB mBaseRenderBounds;
  std::shared_ptr<Model> mModel;
  mce::MaterialPtr mLeashMat;
};

```

### `ActorRenderer_vtbl`
```
struct /*VFT*/ ActorRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderDebug)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderEffects)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderTrading)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *, float);
  void (__fastcall *renderFlame)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderLeash)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderWaterHole)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *addAdditionalRenderingIfNeeded)(ActorRenderer *this, mce::TextureGroup *);
  void (__fastcall *renderWeaponEffect)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  void (__fastcall *renderBindEffects)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  AABB *(__fastcall *getRenderBounds)(ActorRenderer *this, AABB *result, const Actor *);
  Vec3 *(__fastcall *getLeashOffset)(ActorRenderer *this, Vec3 *result, Actor *, float, float, float, bool, bool);
  void (__fastcall *setIsOnScreen)(ActorRenderer *this, Actor *, const bool, float);
  bool (__fastcall *shouldUpdateBonesAndEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  bool (__fastcall *shouldUpdateEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  void (__fastcall *_bindModelEffectRender)(ActorRenderer *this, BaseActorRenderContext *, Mob *);
};

```

### `ActorBlockRenderer`
```
struct __cppobj ActorBlockRenderer
{
  std::unique_ptr<ChestBlockActor> mChest;
  std::unique_ptr<ChestBlockActor> mEnderChest;
  std::unique_ptr<ShulkerBoxBlockActor> mShulkerBox;
  std::unique_ptr<ChestBlockActor> mTrappedChest;
};

```

### `ActiveDirectorySystem`
```
struct __cppobj ActiveDirectorySystem : ActiveDirectoryIdentityObserver
{
  std::function<void __cdecl(void)> mRebuildPackStack;
  std::unique_ptr<DemoConfig> mDemoConfig;
  std::function<std::vector<std::string> __cdecl(void)> mDeleteSingleUseWorlds;
  IMinecraftEventing *mEventing;
  ActiveDirectoryIdentity *mIdentity;
  std::unique_ptr<TaskGroup> mTaskGroup;
};

```

### `ActiveDirectorySystem_vtbl`
```
struct /*VFT*/ ActiveDirectorySystem_vtbl
{
  void (__fastcall *~Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onIdentityGained)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityRefreshed)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityLost)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onIdentityExpired)(ActiveDirectoryIdentityObserver *this, const ActiveDirectoryIdentity *);
  void (__fastcall *onConfigFetched)(ActiveDirectoryIdentityObserver *this, const EDUConfigData *);
};

```

### `ActorInfoRegistry`
```
struct __cppobj __declspec(align(8)) ActorInfoRegistry
{
  std::unordered_map<unsigned __int64,unsigned int> mActorInfoNameMap;
  std::unordered_map<unsigned int,ActorInfo> mActorInfoMap;
  unsigned int mLastId;
};

```

### `ActorDefinitionGroup`
```
struct __cppobj ActorDefinitionGroup : Bedrock::EnableNonOwnerReferences
{
  ActorDefinitionGroup_vtbl *__vftable /*VFT*/;
  std::unordered_set<ActorDefinitionPtr *> mRegisteredPtrs;
  std::unordered_map<std::string,std::unique_ptr<ActorDefinition>> mDefinitions;
  std::unordered_map<std::string,ActorDefinitionGroup::EDLWrapper> mTemplateMap;
  ResourcePackManager *mResourcePackManager;
  std::mutex mReferenceMutex;
  IMinecraftEventing *mEventing;
  ActorComponentFactory *mComponentFactory;
  std::unique_ptr<ActorEventResponseFactory> mResponseFactory;
};

```

### `ActorDefinitionGroup_vtbl`
```
struct /*VFT*/ ActorDefinitionGroup_vtbl
{
  void (__fastcall *~ActorDefinitionGroup)(ActorDefinitionGroup *this);
};

```

### `AnimationsDescription_vtbl`
```
struct /*VFT*/ AnimationsDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `AnimationScriptsDescription_vtbl`
```
struct /*VFT*/ AnimationScriptsDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ActorDefinitionAttribute`
```
struct __cppobj ActorDefinitionAttribute
{
  std::string name;
  float min;
  float max;
  FloatRange value;
};

```

### `AttributeDescription`
```
struct __cppobj AttributeDescription : Description
{
};

```

### `AttributeDescription_vtbl`
```
struct /*VFT*/ AttributeDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `AttackDescription`
```
struct __cppobj __declspec(align(8)) AttackDescription : AttributeDescription
{
  FloatRange mDamage;
  std::string mEffectName;
  float mEffectDuration;
};

```

### `AttackDescription_vtbl`
```
struct /*VFT*/ AttackDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `AmphibiousMoveControlDescription`
```
struct __cppobj AmphibiousMoveControlDescription : MoveControlDescription
{
};

```

### `AmphibiousMoveControlDescription_vtbl`
```
struct /*VFT*/ AmphibiousMoveControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ActorDefinition`
```
struct __cppobj ActorDefinition
{
  ActorDefinitionDescriptor mDescription;
  IdentifierDescription mIdentifier;
  RuntimeIdentifierDescription mRuntimeIdentifier;
  IsSpawnableDescription mIsSpawnable;
  IsSummonableDescription mIsSummonable;
  AnimationsDescription mAnimationsDescription;
  AnimationScriptsDescription mAnimationScriptsDescription;
  std::vector<ActorDefinitionAttribute> mAttributes;
  std::unordered_map<std::string,DefinitionEvent> mEventHandlers;
  std::shared_ptr<CommonResourceDefinitionMap> mCommonResourceDefinitionMap;
  std::string mRelativeResourceFilepath;
  CurrentCmdVersion mCommandVersion;
  StorylineDescription mStoryline;
  CustomEntityTypeDescription mCustomEntityType;
  PickupItemDefinition mPickupItem;
  AttackDescription mAttack;
  MobEffectChangeDescription mMobEffects;
  AmphibiousMoveControlDescription mAmphibiousMoveControl;
  BehaviorTreeDescription mBehavior;
  BreakBlocksDescription mBreakBlocks;
  BreakDoorAnnotationDescription mBreakDoorAnnotation;
  BucketableDescription mBucketable;
  CommandBlockDescription mCommandBlock;
  ContainerDescription mContainer;
  DwellerDescription mDweller;
  GenericMoveControlDescription mGenericMoveControl;
  GlideMoveControlDescription mGlideMoveControl;
  HideDescription mHide;
  IllagerBeastBlockedDescription mIllagerBeastBlocked;
  ManagedWanderingTraderDescription mManagedWanderingTrader;
  MoveControlBasicDescription mMoveControl;
  MoveControlDolphinDescription mDolphinSwimControl;
  MoveControlFlyDescription mFlyControl;
  MoveControlSkipDescription mHopControl;
  MoveControlHoverDescription mHoverControl;
  MoveControlSwayDescription mSwimControl;
  NavigationClimbDescription mWallClimberNavigation;
  NavigationFloatDescription mFloatNavigation;
  NavigationFlyDescription mFlyingNavigation;
  NavigationHoverDescription mHoverNavigation;
  NavigationGenericDescription mGenericNavigation;
  NavigationSwimDescription mWaterboundNavigation;
  NavigationWalkDescription mNavigation;
  PersistentDescription mPersistent;
  PreferredPathDescription mPreferredPath;
  ProjectileDescription mProjectile;
  PushableDescription mPushable;
  RaidTriggerDescription mRaidTrigger;
  SlimeMoveControlDescription mSlimeMoveControl;
  StrengthDescription mStrength;
  TrailDescription mTrail;
  TargetNearbyDescription mTargetNearby;
  TeleportDescription mTeleport;
  TickWorldDescription mTickWorld;
  TradeResupplyDescription mTradeResupply;
  TrustDescription mTrust;
  EconomyTradeableDescription mEconomyTradeable;
  TransformationDescription mTransformation;
  WaterMovementDescription mWaterMovement;
  DynamicJumpControlDescription mDynamicJumpControl;
  JumpControlDescription mJumpControl;
  OpenDoorAnnotationDescription mOpenDoorAnnotation;
  TripodCameraDescription mTripodCamera;
};

```

### `ActorDefinitionGroup::EDLWrapper`
```
struct __cppobj ActorDefinitionGroup::EDLWrapper
{
  std::unordered_map<std::string,std::unique_ptr<ActorDefinition>> mList;
};

```

### `ActorComponentFactory`
```
struct __cppobj ActorComponentFactory : EntityComponentFactory
{
};

```

### `ActorEventResponseFactory`
```
struct __cppobj ActorEventResponseFactory : EventResponseFactory
{
};

```

### `ActorEventResponseFactory_vtbl`
```
struct /*VFT*/ ActorEventResponseFactory_vtbl
{
  void (__fastcall *~EventResponseFactory)(EventResponseFactory *this);
  void (__fastcall *initializeFactory)(EventResponseFactory *this, const Experiments *);
};

```

### `ActorSpawnRuleBase`
```
struct __cppobj ActorSpawnRuleBase
{
  ActorSpawnRuleBase_vtbl *__vftable /*VFT*/;
  std::unordered_map<std::string,int> mSpawnDelayStartMap;
};

```

### `ActorSpawnRuleBase_vtbl`
```
struct /*VFT*/ ActorSpawnRuleBase_vtbl
{
  void (__fastcall *~ActorSpawnRuleBase)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getRootKey)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getFileType)(ActorSpawnRuleBase *this);
  bool (__fastcall *processPopulationControl)(ActorSpawnRuleBase *this, const std::string *, Json::Value *);
  void (__fastcall *readResourceFiles)(ActorSpawnRuleBase *this, ResourcePackManager *, std::unordered_map<std::string,std::string> *);
};

```

### `ActorSpawnRuleGroup`
```
struct __cppobj ActorSpawnRuleGroup : ActorSpawnRuleBase
{
  std::unordered_map<std::string,int> mCategoryLookup;
};

```

### `ActorSpawnRuleGroup_vtbl`
```
struct /*VFT*/ ActorSpawnRuleGroup_vtbl
{
  void (__fastcall *~ActorSpawnRuleBase)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getRootKey)(ActorSpawnRuleBase *this);
  const std::string *(__fastcall *getFileType)(ActorSpawnRuleBase *this);
  bool (__fastcall *processPopulationControl)(ActorSpawnRuleBase *this, const std::string *, Json::Value *);
  void (__fastcall *readResourceFiles)(ActorSpawnRuleBase *this, ResourcePackManager *, std::unordered_map<std::string,std::string> *);
};

```

### `ActorGameplayHandler`
```
struct __cppobj ActorGameplayHandler : GameplayHandler
{
};

```

### `ActorGameplayHandler_vtbl`
```
struct /*VFT*/ ActorGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleActorGriefingBlock)(ActorGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ActorGriefingBlockEvent *);
  HandlerResult (__fastcall *handleActorAcquiredItem)(ActorGameplayHandler *this, const ActorAcquiredItemEvent *);
  HandlerResult (__fastcall *handleActorAddEffect)(ActorGameplayHandler *this, const ActorAddEffectEvent *);
  HandlerResult (__fastcall *handleActorAnimationChanged)(ActorGameplayHandler *this, const ActorAnimationChangedEvent *);
  HandlerResult (__fastcall *handleActorDefinitionEventTriggered)(ActorGameplayHandler *this, const ActorDefinitionEvent *);
  HandlerResult (__fastcall *handleActorHurt)(ActorGameplayHandler *this, const ActorHurtEvent *);
  HandlerResult (__fastcall *handleActorKilled)(ActorGameplayHandler *this, const ActorKilledEvent *);
  HandlerResult (__fastcall *handleActorRemoveEffect)(ActorGameplayHandler *this, const ActorRemoveEffectEvent *);
  HandlerResult (__fastcall *handleActorUseItem)(ActorGameplayHandler *this, const ActorUseItemEvent *);
  HandlerResult (__fastcall *handleKnockBack)(ActorGameplayHandler *this, const KnockBackEvent *);
  HandlerResult (__fastcall *handleMountTaming)(ActorGameplayHandler *this, const MountTamingEvent *);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleProjectileHit)(ActorGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ProjectileHitEvent *);
};

```

### `ActorEventCoordinator`
```
struct __cppobj ActorEventCoordinator : EventCoordinator<ActorEventListener>
{
  std::unique_ptr<ActorGameplayHandler> mActorGameplayHandler;
};

```

### `ActorFactoryData`
```
struct __cppobj ActorFactoryData
{
  ActorDefinitionIdentifier mIdentifier;
  ActorDefinitionIdentifier mBaseIdentifier;
  bool mAllowSummon;
  std::unique_ptr<Actor> *(__fastcall *mFactory)(std::unique_ptr<Actor> *result, ActorDefinitionGroup *, const ActorDefinitionIdentifier *);
  std::optional<int> mExperimentIndex;
  ActorType mActorType;
  float mWalkAnimSpeed;
};

```

### `ActorGoalFactory`
```
struct __cppobj __declspec(align(8)) ActorGoalFactory : EntityGoalFactory
{
  bool mGenerateDoc;
};

```

### `ActorFactory`
```
struct __cppobj ActorFactory
{
  gsl::not_null<Bedrock::NonOwnerPointer<Level> > mLevel;
  std::shared_ptr<IEntityInitializer> mEntityInitializer;
  Bedrock::NonOwnerPointer<ActorDefinitionGroup> mDefinitions;
  std::unordered_map<std::string,ActorFactoryData> mFactoryFunctions;
  std::set<std::string> mExperimentalEntities;
  ActorComponentFactory mComponentFactory;
  ActorGoalFactory mGoalFactory;
};

```

### `ActorInteraction`
```
struct __cppobj __declspec(align(8)) ActorInteraction
{
  std::string mInteractText;
  std::function<void __cdecl(void)> mInteraction;
  bool mNoCapture;
};

```

### `Actor_vtbl`
```
struct /*VFT*/ Actor_vtbl
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

### `AABBBucket`
```
struct __cppobj __declspec(align(8)) AABBBucket
{
  AABB mBucketBounds;
  int mCachedTicks;
  std::vector<RopeAABB> mBBs;
  bool mDirty;
  bool mNeedsFinalize;
};

```

### `AABBPred`
```
struct __cppobj AABBPred
{
};

```

### `ActorDefinitionDiffList`
```
struct __cppobj ActorDefinitionDiffList
{
  ActorDefinitionGroup *mDefinitions;
  std::vector<std::pair<bool,ActorDefinitionPtr>> mDefinitionStack;
  std::unique_ptr<ActorDefinitionDescriptor> mChangedDescription;
  bool mChanged;
  DefinitionInstanceGroup mAddedDefinitionGroup;
  DefinitionInstanceGroup mRemovedDefinitionGroup;
  bool mLockedChanges;
  std::vector<std::pair<bool,std::string >> mPendingChanges;
};

```

### `ActionEvent`
```
struct __cppobj __declspec(align(4)) ActionEvent
{
  int mActionId;
  ActionEvent::ActionState mActionState;
  bool mIsExclusive;
  FocusImpact mFocusImpact;
};

```

### `ActionQueue`
```
struct __cppobj ActionQueue
{
  std::deque<ActionEvent> mQueue;
};

```

### `ApplicationSignal::ClipboardData`
```
struct __cppobj ApplicationSignal::ClipboardData
{
  std::wstring mData;
};

```

### `ApplicationSignal::ClipboardPaste`
```
struct __cppobj ApplicationSignal::ClipboardPaste : Bedrock::Signal<ApplicationSignal::ClipboardPaste>
{
  ApplicationSignal::ClipboardData mClipboard;
};

```

### `ApplicationSignal::ClipboardPaste_vtbl`
```
struct /*VFT*/ ApplicationSignal::ClipboardPaste_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `ApplicationSignal::ClipboardCopyData`
```
struct __cppobj ApplicationSignal::ClipboardCopyData
{
  std::string mData;
};

```

### `ApplicationSignal::ClipboardCopy`
```
struct __cppobj ApplicationSignal::ClipboardCopy : Bedrock::Signal<ApplicationSignal::ClipboardCopy>
{
  ApplicationSignal::ClipboardCopyData mClipboard;
};

```

### `ApplicationSignal::ClipboardCopy_vtbl`
```
struct /*VFT*/ ApplicationSignal::ClipboardCopy_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `AppPlatform::MobileInformation`
```
struct __cppobj __declspec(align(4)) AppPlatform::MobileInformation
{
  std::string mSecureId;
  std::string mSerial;
  std::string mBoard;
  std::string mInstallerPackageName;
  int mSignaturesHash;
  bool mIsRooted;
};

```

### `AppPlatform::HardwareInformation`
```
struct __cppobj AppPlatform::HardwareInformation
{
  std::string mDeviceModelName;
  std::string mOSVersion;
  std::string mCPUType;
  std::string mCPUName;
  std::string mCPUFeatures;
  unsigned int mNumCores;
  unsigned __int64 mPhysicalMemorySize;
  bool mGraphicsTearingSupport;
  unsigned int mScreenWidth;
  unsigned int mScreenHeight;
  unsigned int mCPUBits;
};

```

### `AppPlatform::GraphicsPlatformProvider`
```
struct __cppobj AppPlatform::GraphicsPlatformProvider : cg::IGraphicsDevicePlatformProvider
{
};

```

### `AppPlatform::GraphicsPlatformProvider_vtbl`
```
struct /*VFT*/ AppPlatform::GraphicsPlatformProvider_vtbl
{
  void (__fastcall *~IGraphicsDevicePlatformProvider)(cg::IGraphicsDevicePlatformProvider *this);
  std::string *(__fastcall *getDriverVersion)(cg::IGraphicsDevicePlatformProvider *this, std::string *result);
  Json::Value *(__fastcall *getDeviceInfoJson)(cg::IGraphicsDevicePlatformProvider *this, Json::Value *result);
};

```

### `AppLifecycleContext`
```
struct __cppobj AppLifecycleContext
{
  bool mAppliedHasGraphicsContext;
  bool mAppliedIsCurrentlyResumed;
  bool mHasGraphicsContext;
  bool mIsCurrentlyResumed;
};

```

### `ApplicationSignal::ClipboardPasteRequest`
```
struct __cppobj ApplicationSignal::ClipboardPasteRequest : Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>
{
};

```

### `ApplicationSignal::ClipboardPasteRequest_vtbl`
```
struct /*VFT*/ ApplicationSignal::ClipboardPasteRequest_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `AgentRenderData`
```
struct __cppobj AgentRenderData
{
  float mEaseIn;
  __int64 mOldTime;
};

```

### `Agent`
```
struct __cppobj Agent : Mob
{
  Vec3 mToTarget;
  int mSwingAnimationTick;
  const int SWING_TICKS;
  int mSelectedSlot;
  bool mHasSetName;
  bool mHasFiredCreationEvent;
  bool mHover;
  AgentRenderData mRenderData;
};

```

### `ActorSkeletalAnimationPlayer`
```
struct __cppobj __declspec(align(8)) ActorSkeletalAnimationPlayer : ActorAnimationPlayer
{
  ActorSkeletalAnimationPtr mAnimationData;
  std::vector<BoneAnimationPlayer> mBoneAnimationPlayers;
  std::unordered_map<enum SkeletalHierarchyIndex,std::vector<int>> mBoneToPartMapping;
  const std::unordered_map<HashedString,ParticleEffectPtr> *mActorParticleEffectMap;
  const std::unordered_map<HashedString,std::string> *mActorSoundEffectMap;
  float mAnimTime;
  float mLastAnimTime;
  float mStartDelay;
};

```

### `ActorSkeletalAnimationPlayer_vtbl`
```
struct /*VFT*/ ActorSkeletalAnimationPlayer_vtbl
{
  void (__fastcall *~ActorAnimationPlayer)(ActorAnimationPlayer *this);
  void (__fastcall *applyToPose)(ActorAnimationPlayer *this, RenderParams *, std::unordered_map<enum SkeletalHierarchyIndex,std::vector<BoneOrientation>> *, float);
  void (__fastcall *resetAnimation)(ActorAnimationPlayer *this);
  void (__fastcall *buildBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
  void (__fastcall *bindParticleEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,ParticleEffectPtr> *);
  void (__fastcall *bindSoundEffects)(ActorAnimationPlayer *this, const std::unordered_map<HashedString,std::string> *);
  bool (__fastcall *hasAnimationFinished)(ActorAnimationPlayer *this);
  ActorAnimationPlayer *(__fastcall *findAnimation)(ActorAnimationPlayer *this, const HashedString *);
  ActorAnimationType (__fastcall *getAnimationType)(ActorAnimationPlayer *this);
  void (__fastcall *updateBoneToPartMapping)(ActorAnimationPlayer *this, AnimationComponent *);
};

```

### `ActiveDirectoryModalArgs`
```
struct __cppobj ActiveDirectoryModalArgs
{
  std::string mTitleText;
  std::string mBodyText;
  std::string mConfirmButtonText;
  std::string mCancelButtonText;
  std::function<void __cdecl(enum ModalScreenButtonId)> mOnComplete;
};

```

### `AchievementScreenController`
```
struct __cppobj __declspec(align(4)) AchievementScreenController : MinecraftScreenController
{
  persona::PersonaPieceCollectionModel *mPersonaPieceCollectionModel;
  PersonaRepository *mPersonaRepository;
  std::string mAchievementDeepLinkId;
  std::vector<FormattedAchievementData> mAchievementData;
  FormattedPlayerStats mHeaderData;
  float mTotalAchievementPercentage;
  bool mDataUpdated;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastRefresh;
  int mToSetFocus;
  bool mNeedsToFocusAfterScrolling;
};

```

### `AchievementScreenController_vtbl`
```
struct /*VFT*/ AchievementScreenController_vtbl
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

### `AccessorTypeEnumHasher`
```
struct __cppobj AccessorTypeEnumHasher
{
};

```

### `AutoPlaceRequest`
```
struct __cppobj AutoPlaceRequest
{
  int mUnplacedAmount;
  ItemTransferRequest mRequest;
};

```

### `AmbientCaveSoundPlayer`
```
struct __cppobj AmbientCaveSoundPlayer
{
};

```

### `AccountTransferHandler`
```
struct __cppobj __declspec(align(8)) AccountTransferHandler : std::enable_shared_from_this<AccountTransferHandler>
{
  std::shared_ptr<CommerceIdentity> mCommerceIdentity;
  IMinecraftEventing *mEventing;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  std::function<void __cdecl(void)> mCallback;
  bool mHasShownAccountTransferErrorDialog;
  bool mResetTransferStateOnNextAttempt;
  int mNumberOfTransferAttempts;
  std::string mLegacyCommerceId;
  std::string mLegacyCommerceAuthToken;
  std::string mCorrelationId;
  _BYTE mCurrentState[4];
  std::vector<std::string> mTransferedAccountsList;
  std::mutex mAttemptingAccountTransfer;
  bool mAccountTransferInProgress;
};

```

### `ANON_OBJECT_HEADER_BIGOBJ`
```
struct ANON_OBJECT_HEADER_BIGOBJ
{
  unsigned __int16 Sig1;
  unsigned __int16 Sig2;
  unsigned __int16 Version;
  unsigned __int16 Machine;
  unsigned int TimeDateStamp;
  _GUID ClassID;
  unsigned int SizeOfData;
  unsigned int Flags;
  unsigned int MetaDataSize;
  unsigned int MetaDataOffset;
  unsigned int NumberOfSections;
  unsigned int PointerToSymbolTable;
  unsigned int NumberOfSymbols;
};

```

### `addrinfo`
```
struct addrinfo
{
  int ai_flags;
  int ai_family;
  int ai_socktype;
  int ai_protocol;
  unsigned __int64 ai_addrlen;
  char *ai_canonname;
  sockaddr *ai_addr;
  addrinfo *ai_next;
};

```

### `AsyncIPipeDouble`
```
struct __cppobj AsyncIPipeDouble : IUnknown
{
};

```

### `AsyncIPipeDouble_vtbl`
```
struct /*VFT*/ AsyncIPipeDouble_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *Begin_Pull)(AsyncIPipeDouble *this, unsigned int);
  HRESULT (__fastcall *Finish_Pull)(AsyncIPipeDouble *this, long double *, unsigned int *);
  HRESULT (__fastcall *Begin_Push)(AsyncIPipeDouble *this, long double *, unsigned int);
  HRESULT (__fastcall *Finish_Push)(AsyncIPipeDouble *this);
};

```

### `addrinfoexA`
```
struct addrinfoexA
{
  int ai_flags;
  int ai_family;
  int ai_socktype;
  int ai_protocol;
  unsigned __int64 ai_addrlen;
  char *ai_canonname;
  sockaddr *ai_addr;
  void *ai_blob;
  unsigned __int64 ai_bloblen;
  _GUID *ai_provider;
  addrinfoexA *ai_next;
};

```

### `addrinfoexW`
```
struct addrinfoexW
{
  int ai_flags;
  int ai_family;
  int ai_socktype;
  int ai_protocol;
  unsigned __int64 ai_addrlen;
  wchar_t *ai_canonname;
  sockaddr *ai_addr;
  void *ai_blob;
  unsigned __int64 ai_bloblen;
  _GUID *ai_provider;
  addrinfoexW *ai_next;
};

```

### `ARRAY_INFO`
```
struct ARRAY_INFO
{
  int Dimension;
  unsigned int *BufferConformanceMark;
  unsigned int *BufferVarianceMark;
  unsigned int *MaxCountArray;
  unsigned int *OffsetArray;
  unsigned int *ActualCountArray;
};

```

### `AsyncIPipeLong`
```
struct __cppobj AsyncIPipeLong : IUnknown
{
};

```

### `AsyncIPipeLong_vtbl`
```
struct /*VFT*/ AsyncIPipeLong_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *Begin_Pull)(AsyncIPipeLong *this, unsigned int);
  HRESULT (__fastcall *Finish_Pull)(AsyncIPipeLong *this, int *, unsigned int *);
  HRESULT (__fastcall *Begin_Push)(AsyncIPipeLong *this, int *, unsigned int);
  HRESULT (__fastcall *Finish_Push)(AsyncIPipeLong *this);
};

```

### `ANON_OBJECT_HEADER`
```
struct ANON_OBJECT_HEADER
{
  unsigned __int16 Sig1;
  unsigned __int16 Sig2;
  unsigned __int16 Version;
  unsigned __int16 Machine;
  unsigned int TimeDateStamp;
  _GUID ClassID;
  unsigned int SizeOfData;
};

```

### `APARTMENT_SHUTDOWN_REGISTRATION_COOKIE__`
```
struct APARTMENT_SHUTDOWN_REGISTRATION_COOKIE__
{
  int unused;
};

```

### `AsyncIAdviseSink`
```
struct __cppobj AsyncIAdviseSink : IUnknown
{
};

```

### `AsyncIAdviseSink_vtbl`
```
struct /*VFT*/ AsyncIAdviseSink_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  void (__fastcall *Begin_OnDataChange)(AsyncIAdviseSink *this, tagFORMATETC *, tagSTGMEDIUM *);
  void (__fastcall *Finish_OnDataChange)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnViewChange)(AsyncIAdviseSink *this, unsigned int, int);
  void (__fastcall *Finish_OnViewChange)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnRename)(AsyncIAdviseSink *this, IMoniker *);
  void (__fastcall *Finish_OnRename)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnSave)(AsyncIAdviseSink *this);
  void (__fastcall *Finish_OnSave)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnClose)(AsyncIAdviseSink *this);
  void (__fastcall *Finish_OnClose)(AsyncIAdviseSink *this);
};

```

### `AsyncIUnknown`
```
struct __cppobj AsyncIUnknown : IUnknown
{
};

```

### `AsyncIUnknown_vtbl`
```
struct /*VFT*/ AsyncIUnknown_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *Begin_QueryInterface)(AsyncIUnknown *this, const _GUID *);
  HRESULT (__fastcall *Finish_QueryInterface)(AsyncIUnknown *this, void **);
  HRESULT (__fastcall *Begin_AddRef)(AsyncIUnknown *this);
  unsigned int (__fastcall *Finish_AddRef)(AsyncIUnknown *this);
  HRESULT (__fastcall *Begin_Release)(AsyncIUnknown *this);
  unsigned int (__fastcall *Finish_Release)(AsyncIUnknown *this);
};

```

### `AsyncIPipeByte`
```
struct __cppobj AsyncIPipeByte : IUnknown
{
};

```

### `AsyncIPipeByte_vtbl`
```
struct /*VFT*/ AsyncIPipeByte_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *Begin_Pull)(AsyncIPipeByte *this, unsigned int);
  HRESULT (__fastcall *Finish_Pull)(AsyncIPipeByte *this, unsigned __int8 *, unsigned int *);
  HRESULT (__fastcall *Begin_Push)(AsyncIPipeByte *this, unsigned __int8 *, unsigned int);
  HRESULT (__fastcall *Finish_Push)(AsyncIPipeByte *this);
};

```

### `APP_LOCAL_DEVICE_ID`
```
struct APP_LOCAL_DEVICE_ID
{
  unsigned __int8 value[32];
};

```

### `addrinfoW`
```
struct addrinfoW
{
  int ai_flags;
  int ai_family;
  int ai_socktype;
  int ai_protocol;
  unsigned __int64 ai_addrlen;
  wchar_t *ai_canonname;
  sockaddr *ai_addr;
  addrinfoW *ai_next;
};

```

### `AsyncIAdviseSink2`
```
struct __cppobj AsyncIAdviseSink2 : AsyncIAdviseSink
{
};

```

### `AsyncIAdviseSink2_vtbl`
```
struct /*VFT*/ AsyncIAdviseSink2_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  void (__fastcall *Begin_OnDataChange)(AsyncIAdviseSink *this, tagFORMATETC *, tagSTGMEDIUM *);
  void (__fastcall *Finish_OnDataChange)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnViewChange)(AsyncIAdviseSink *this, unsigned int, int);
  void (__fastcall *Finish_OnViewChange)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnRename)(AsyncIAdviseSink *this, IMoniker *);
  void (__fastcall *Finish_OnRename)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnSave)(AsyncIAdviseSink *this);
  void (__fastcall *Finish_OnSave)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnClose)(AsyncIAdviseSink *this);
  void (__fastcall *Finish_OnClose)(AsyncIAdviseSink *this);
  void (__fastcall *Begin_OnLinkSrcChange)(AsyncIAdviseSink2 *this, IMoniker *);
  void (__fastcall *Finish_OnLinkSrcChange)(AsyncIAdviseSink2 *this);
};

```

### `ANON_OBJECT_HEADER_V2`
```
struct ANON_OBJECT_HEADER_V2
{
  unsigned __int16 Sig1;
  unsigned __int16 Sig2;
  unsigned __int16 Version;
  unsigned __int16 Machine;
  unsigned int TimeDateStamp;
  _GUID ClassID;
  unsigned int SizeOfData;
  unsigned int Flags;
  unsigned int MetaDataSize;
  unsigned int MetaDataOffset;
};

```

### `ASSOCIATIONELEMENT`
```
struct ASSOCIATIONELEMENT
{
  ASSOCCLASS ac;
  HKEY__ *hkClass;
  const wchar_t *pszClass;
};

```

### `AsyncIMultiQI`
```
struct __cppobj AsyncIMultiQI : IUnknown
{
};

```

### `AsyncIMultiQI_vtbl`
```
struct /*VFT*/ AsyncIMultiQI_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *Begin_QueryMultipleInterfaces)(AsyncIMultiQI *this, unsigned int, tagMULTI_QI *);
  HRESULT (__fastcall *Finish_QueryMultipleInterfaces)(AsyncIMultiQI *this, tagMULTI_QI *);
};

```

### `AttachBehavior`
```
struct __cppobj __declspec(align(8)) AttachBehavior : CameraBehavior<AttachBehavior>
{
  Vec3 mOffset;
};

```

### `AttachBehavior_vtbl`
```
struct /*VFT*/ AttachBehavior_vtbl
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

### `AvoidanceBehavior::AvoidanceRay`
```
struct __cppobj AvoidanceBehavior::AvoidanceRay
{
  float mDistance;
  float mAngle;
  float mWeight;
};

```

### `AvoidanceBehavior`
```
struct __cppobj AvoidanceBehavior : CameraBehavior<AvoidanceBehavior>
{
  CriticallyDampedSpring<float> mRelaxDistanceSmoothingSpring;
  float mDistanceConstraintMin;
  std::vector<AvoidanceBehavior::AvoidanceRay> mAvoidanceRaysHorizontal;
  std::vector<AvoidanceBehavior::AvoidanceRay> mAvoidanceRaysVertical;
  float mRelaxDistanceVelocity;
  float mSmoothedDistanceConstraint;
};

```

### `AvoidanceBehavior_vtbl`
```
struct /*VFT*/ AvoidanceBehavior_vtbl
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

### `AttachBehaviorLoader`
```
struct __cppobj AttachBehaviorLoader : CameraBehaviorLoader
{
};

```

### `AttachBehaviorLoader_vtbl`
```
struct /*VFT*/ AttachBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `AvoidanceBehaviorLoader`
```
struct __cppobj AvoidanceBehaviorLoader : CameraBehaviorLoader
{
};

```

### `AvoidanceBehaviorLoader_vtbl`
```
struct /*VFT*/ AvoidanceBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `AutoCompleteInformation`
```
struct __cppobj AutoCompleteInformation
{
  std::vector<AutoCompleteOption> possibilities;
};

```

### `AllowList::AllowListEntryMatcher`
```
struct __cppobj AllowList::AllowListEntryMatcher
{
  std::string mName;
  std::string mXuid;
};

```

### `ActorComponent`
```
struct __cppobj ActorComponent : IEntityComponent
{
  Actor *mActor;
};

```

### `AudioEmitterSystem`
```
struct __cppobj AudioEmitterSystem : ITickingSystem
{
  IClientInstance *mClientInstance;
};

```

### `AudioEmitterSystem_vtbl`
```
struct /*VFT*/ AudioEmitterSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `AdventureSettingsOverride`
```
struct __cppobj AdventureSettingsOverride
{
  std::optional<bool> mNoPvM;
  std::optional<bool> mNoMvP;
  std::optional<bool> mImmutableWorld;
  std::optional<bool> mShowNameTags;
  std::optional<bool> mAutoJump;
};

```

### `AppConfigData<EduConfigDataWrapper>`
```
struct __cppobj AppConfigData<EduConfigDataWrapper> : IAppConfigData
{
};

```

### `AppConfigData<EduConfigDataWrapper>_vtbl`
```
struct /*VFT*/ AppConfigData<EduConfigDataWrapper>_vtbl
{
  void (__fastcall *~IAppConfigData)(IAppConfigData *this);
  typeid_t<IAppConfigData> *(__fastcall *getType)(IAppConfigData *this, typeid_t<IAppConfigData> *result);
};

```

### `ActorClassTree`
```
struct __cppobj ActorClassTree
{
};

```

### `ActiveDirectorySystem::onIdentityGained::__l2::<lambda_fd751f655986d7672f3b0481780ebe0b>`
```
struct __cppobj ActiveDirectorySystem::onIdentityGained::__l2::<lambda_fd751f655986d7672f3b0481780ebe0b>
{
  std::vector<std::string> worldIds;
};

```

### `ArmorItemComponent`
```
struct __cppobj ArmorItemComponent : ItemComponent
{
  int mProtection;
  _BYTE mTextureType[4];
};

```

### `ArmorItemComponent_vtbl`
```
struct /*VFT*/ ArmorItemComponent_vtbl
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

### `ActorAnimationGroupParseMetaData`
```
struct __cppobj __declspec(align(8)) ActorAnimationGroupParseMetaData
{
  ActorAnimationGroup *mActorAnimationGroup;
  CurrentCmdVersion mCurrentCommandVersion;
};

```

### `ActorAnimationControllerGroupParseMetaData`
```
struct __cppobj __declspec(align(8)) ActorAnimationControllerGroupParseMetaData
{
  ActorAnimationControllerGroup *mActorAnimationControllerGroup;
  CurrentCmdVersion mCurrentCommandVersion;
};

```

### `ActorPlacerItem`
```
struct __cppobj ActorPlacerItem : Item
{
  TextureUVCoordinateSet m_uvNullEgg;
  ActorDefinitionIdentifier mActorID;
};

```

### `AppPkgUpdateStage`
```
struct __cppobj __declspec(align(4)) AppPkgUpdateStage : BaseStage
{
  int mErrorCode;
  bool mIsForceUpdateMsgSend;
};

```

### `AppPkgUpdateStage_vtbl`
```
struct /*VFT*/ AppPkgUpdateStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `AppResourceLoader`
```
struct __cppobj AppResourceLoader : ResourceLoader
{
};

```

### `AppConfigsFactory`
```
struct __cppobj AppConfigsFactory
{
};

```

### `AnchoredOffsetComponent`
```
struct __cppobj AnchoredOffsetComponent : UIComponent
{
  float mLastParentRelativeOffsetValueX;
  float mLastParentRelativeOffsetValueY;
};

```

### `AnchoredOffsetComponent_vtbl`
```
struct /*VFT*/ AnchoredOffsetComponent_vtbl
{
  void (__fastcall *~UIComponent)(UIComponent *this);
  void (__fastcall *OnScreenPop)(UIComponent *this);
  std::unique_ptr<UIComponent> *(__fastcall *clone)(UIComponent *this, std::unique_ptr<UIComponent> *result, UIControl *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, const ScreenEvent *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, VisualTree *, ScreenInputContext *, UIAnimationController *, const ScreenEvent *);
  void (__fastcall *onNotifyChildAdded)(UIComponent *this);
  void (__fastcall *onNotifyChildRemoved)(UIComponent *this);
  void (__fastcall *onRemoved)(UIComponent *this);
  void (__fastcall *onAdded)(UIComponent *this);
  void (__fastcall *onVisibilityChanged)(UIComponent *this, bool);
  void (__fastcall *onEnabledChanged)(UIComponent *this, bool);
  bool (__fastcall *isRenderableComponent)(UIComponent *this);
  bool (__fastcall *onLayoutChange)(UIComponent *this);
  void (__fastcall *reset)(UIComponent *this);
  void (__fastcall *reload)(UIComponent *this, const UIComponent *);
  const std::string *(__fastcall *getTextToSpeechComponentValue)(UIComponent *this);
};

```

### `ActorPortraitRenderer`
```
struct __cppobj __declspec(align(8)) ActorPortraitRenderer : MinecraftUICustomRenderer
{
  float mElapsedTime;
};

```

### `ActorPortraitRenderer_vtbl`
```
struct /*VFT*/ ActorPortraitRenderer_vtbl
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

### `ActorPortraitRenderer::Args`
```
struct __cppobj __declspec(align(8)) ActorPortraitRenderer::Args
{
  glm::tvec3<float,0> mScale;
  glm::tvec3<float,0> mRotate;
  glm::tvec3<float,0> mTranslate;
  ActorUniqueID mActorId;
  bool mUseLiveAnimation;
  ActorPortraitRenderer::RotateMode mRotateMode;
  SkinData mSkin;
};

```

### `ActorPortraitRenderer::render::__l2::<lambda_97b047e51d4b136e01ca63bccb787849>`
```
struct __cppobj __declspec(align(8)) ActorPortraitRenderer::render::__l2::<lambda_97b047e51d4b136e01ca63bccb787849>
{
  Mob *mob;
  const float yBodyRot;
  const float yBodyRotO;
  Vec2 rot;
  Vec2 rotPrev;
  const float yHeadRot;
  const float yHeadRotO;
  SkinData skin;
  float walkAnimPos;
  float walkAnimSpeed;
  float walkAnimSpeedO;
};

```

### `ActorPortraitRenderer::render::__l16::<lambda_772b7a9fa0335f70de52678e999a2dae>`
```
struct __cppobj ActorPortraitRenderer::render::__l16::<lambda_772b7a9fa0335f70de52678e999a2dae>
{
  MobRenderer *mobRenderer;
};

```

### `AnimProcessBar`
```
struct __cppobj AnimProcessBar : RenderableComponent
{
  float mPosition;
  float mAnimPosition;
};

```

### `AnimProcessBar_vtbl`
```
struct /*VFT*/ AnimProcessBar_vtbl
{
  void (__fastcall *~UIComponent)(UIComponent *this);
  void (__fastcall *OnScreenPop)(UIComponent *this);
  std::unique_ptr<UIComponent> *(__fastcall *clone)(UIComponent *this, std::unique_ptr<UIComponent> *result, UIControl *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, const ScreenEvent *);
  ComponentReceiveActionType (__fastcall *receive)(UIComponent *this, VisualTree *, ScreenInputContext *, UIAnimationController *, const ScreenEvent *);
  void (__fastcall *onNotifyChildAdded)(UIComponent *this);
  void (__fastcall *onNotifyChildRemoved)(UIComponent *this);
  void (__fastcall *onRemoved)(UIComponent *this);
  void (__fastcall *onAdded)(UIComponent *this);
  void (__fastcall *onVisibilityChanged)(UIComponent *this, bool);
  void (__fastcall *onEnabledChanged)(UIComponent *this, bool);
  bool (__fastcall *isRenderableComponent)(UIComponent *this);
  bool (__fastcall *onLayoutChange)(UIComponent *this);
  void (__fastcall *reset)(UIComponent *this);
  void (__fastcall *reload)(UIComponent *this, const UIComponent *);
  const std::string *(__fastcall *getTextToSpeechComponentValue)(UIComponent *this);
  void (__fastcall *updateUI)(RenderableComponent *this, const UIMeasureStrategy *);
  bool (__fastcall *overridesLayoutAxisOffset)(RenderableComponent *this, const LayoutVariableType);
  float (__fastcall *getLayoutAxisOffsetOverride)(RenderableComponent *this, const LayoutVariableType);
};

```

### `AsyncTaskProgressHandler`
```
struct __cppobj AsyncTaskProgressHandler : ProgressHandler
{
  std::string mTitle;
  std::shared_ptr<std::function<void __cdecl(void)> > mAsyncTaskWorkCallbackSharedPtr;
  std::unique_ptr<TaskGroup> mAsyncTaskGroup;
};

```

### `AsyncTaskProgressHandler_vtbl`
```
struct /*VFT*/ AsyncTaskProgressHandler_vtbl
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

### `AsyncTaskProgressHandler::onStart::__l2::<lambda_f735ad69df65f21fa84c294d8e5fb527>`
```
struct __cppobj AsyncTaskProgressHandler::onStart::__l2::<lambda_f735ad69df65f21fa84c294d8e5fb527>
{
  AsyncTaskProgressHandler *const __this;
};

```

### `AcceptDeclineInvitationScreenController`
```
struct __cppobj AcceptDeclineInvitationScreenController : MinecraftScreenController
{
  std::string mTitle;
  std::string mSubtitle;
  std::function<void __cdecl(bool)> mCallback;
  _BYTE mState[1];
  bool mAcceptDeclineModalNotCancelled;
  std::unique_ptr<PlatformMultiplayerRestrictions> mPlatformMultiplayerRestrictions;
};

```

### `AcceptDeclineInvitationScreenController_vtbl`
```
struct /*VFT*/ AcceptDeclineInvitationScreenController_vtbl
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

### `AccountTransferErrorScreenController`
```
struct __cppobj __declspec(align(8)) AccountTransferErrorScreenController : MinecraftScreenController
{
  const std::string mHelpUri;
  bool mPlatformCanLaunchHelpUri;
};

```

### `AccountTransferErrorScreenController_vtbl`
```
struct /*VFT*/ AccountTransferErrorScreenController_vtbl
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

### `ActiveDirectoryAuthenticationInterface`
```
struct __cppobj ActiveDirectoryAuthenticationInterface
{
  ActiveDirectoryAuthenticationInterface_vtbl *__vftable /*VFT*/;
};

```

### `ActiveDirectoryAuthenticationInterface_vtbl`
```
struct /*VFT*/ ActiveDirectoryAuthenticationInterface_vtbl
{
  void (__fastcall *~ActiveDirectoryAuthenticationInterface)(ActiveDirectoryAuthenticationInterface *this);
  ActiveDirectoryAuthenticationState (__fastcall *getAuthenticationState)(ActiveDirectoryAuthenticationInterface *this);
  std::optional<ActiveDirectoryPopup> *(__fastcall *getPopup)(ActiveDirectoryAuthenticationInterface *this, std::optional<ActiveDirectoryPopup> *result);
  std::string *(__fastcall *getTrialPopupId)(ActiveDirectoryAuthenticationInterface *this, std::string *result);
  AuthenticationUIState (__fastcall *getSignInUIState)(ActiveDirectoryAuthenticationInterface *this);
  bool (__fastcall *shouldShowPurchaseDialog)(ActiveDirectoryAuthenticationInterface *this);
  bool (__fastcall *shouldAllowExitGame)(ActiveDirectoryAuthenticationInterface *this);
  bool (__fastcall *shouldShowTrialPurchaseLink)(ActiveDirectoryAuthenticationInterface *this);
  AuthenticationUIState (__fastcall *initializeActiveDirectorySignIn)(ActiveDirectoryAuthenticationInterface *this);
  void (__fastcall *setActiveDirectoryAuthenticationOfferPurchase)(ActiveDirectoryAuthenticationInterface *this);
  bool (__fastcall *purchaseEduLicense)(ActiveDirectoryAuthenticationInterface *this, std::unique_ptr<TransactionContext>);
  bool (__fastcall *getUnfulfilledEduPurchase)(ActiveDirectoryAuthenticationInterface *this, EduPurchaseDetails *);
  bool (__fastcall *fulfillPriorEduPurchase)(ActiveDirectoryAuthenticationInterface *this, std::weak_ptr<Purchase>, std::unique_ptr<TransactionContext>);
};

```

### `ActiveDirectoryAuthenticationScreenController`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController : MinecraftScreenController
{
  bool mAuthenticationPendingPresentationHandled;
  std::optional<ActiveDirectoryPopup> mPopup;
  std::string mAuthMessage;
  _BYTE mUIState[4];
  _BYTE mPurchaseState[4];
  bool mCurrentlyAgree;
  std::string mOfferPrice;
  std::unique_ptr<ActiveDirectoryAuthenticationInterface> mAuthentication;
};

```

### `ActiveDirectoryAuthenticationScreenController_vtbl`
```
struct /*VFT*/ ActiveDirectoryAuthenticationScreenController_vtbl
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

### `ActiveDirectoryModalsScreenController`
```
struct __cppobj ActiveDirectoryModalsScreenController : MinecraftScreenController
{
  ActiveDirectoryModalArgs mArgs;
};

```

### `ActiveDirectoryModalsScreenController_vtbl`
```
struct /*VFT*/ ActiveDirectoryModalsScreenController_vtbl
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

### `AddExternalServerScreenController`
```
struct __cppobj AddExternalServerScreenController : MainMenuScreenController
{
  AddExternalServerScreenController::Mode mMode;
  bool mAreInputsAllValid;
  std::string mServerName;
  std::string mIpAddress;
  int mPort;
  int mExternalServerId;
};

```

### `AddExternalServerScreenController_vtbl`
```
struct /*VFT*/ AddExternalServerScreenController_vtbl
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

### `AdhocInProgressScreenController`
```
struct __cppobj __declspec(align(8)) AdhocInProgressScreenController : MinecraftScreenController
{
  const bool mEnableAdhoc;
  bool mHasTriggered;
};

```

### `AdhocInProgressScreenController_vtbl`
```
struct /*VFT*/ AdhocInProgressScreenController_vtbl
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

### `AdhocScreenController`
```
struct __cppobj __declspec(align(8)) AdhocScreenController : MainMenuScreenController
{
  bool mInProgress;
};

```

### `AdhocScreenController_vtbl`
```
struct /*VFT*/ AdhocScreenController_vtbl
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

### `AutoSaveInfoScreenController`
```
struct __cppobj AutoSaveInfoScreenController : MinecraftScreenController
{
};

```

### `AutoSaveInfoScreenController_vtbl`
```
struct /*VFT*/ AutoSaveInfoScreenController_vtbl
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

### `AutoSaveInfoScreenController::_registerEventHandlers::__l2::<lambda_7b66ab5cb62c5989d3f0c1a33043b8ab>`
```
struct __cppobj AutoSaveInfoScreenController::_registerEventHandlers::__l2::<lambda_7b66ab5cb62c5989d3f0c1a33043b8ab>
{
  AutoSaveInfoScreenController *const __this;
};

```

### `AdhocScreenController::_registerEventHandlers::__l2::<lambda_6d08390e1e81ade70ee842f9050e0b33>`
```
struct __cppobj AdhocScreenController::_registerEventHandlers::__l2::<lambda_6d08390e1e81ade70ee842f9050e0b33>
{
  AdhocScreenController *const __this;
};

```

### `AdhocScreenController::_registerEventHandlers::__l2::<lambda_9daf95af8b4035272c47fbd002009d73>`
```
struct __cppobj AdhocScreenController::_registerEventHandlers::__l2::<lambda_9daf95af8b4035272c47fbd002009d73>
{
  AdhocScreenController *const __this;
};

```

### `AdhocInProgressScreenController::_registerBindings::__l2::<lambda_898a369a0613f3d095923eb65564090f>`
```
struct __cppobj AdhocInProgressScreenController::_registerBindings::__l2::<lambda_898a369a0613f3d095923eb65564090f>
{
  AdhocInProgressScreenController *const __this;
};

```

### `AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>`
```
struct __cppobj AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>
{
  AdhocInProgressScreenController *const __this;
};

```

### `AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>::()::__l2::<lambda_b16cccd10e875395291682c7a586aa63>`
```
struct __cppobj AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>::()::__l2::<lambda_b16cccd10e875395291682c7a586aa63>
{
  AdhocInProgressScreenController *const __this;
};

```

### `AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>::()::__l2::<lambda_b16cccd10e875395291682c7a586aa63>::()::__l13::<lambda_93ae71cbb3291f8eb6854d2d8d995f0e>`
```
struct __cppobj AdhocInProgressScreenController::onOpen::__l10::<lambda_e341736a892a3f53119c434cbd02ca85>::()::__l2::<lambda_b16cccd10e875395291682c7a586aa63>::()::__l13::<lambda_93ae71cbb3291f8eb6854d2d8d995f0e>
{
};

```

### `AdhocInProgressScreenController::onOpen::__l8::<lambda_9d4c7cd97c1f74d4826ffb41702c8e67>`
```
struct __cppobj AdhocInProgressScreenController::onOpen::__l8::<lambda_9d4c7cd97c1f74d4826ffb41702c8e67>
{
  AdhocInProgressScreenController *const __this;
};

```

### `AddExternalServerScreenController::_removeServer::__l2::<lambda_30c06750adf499f5d0d289c0997a750f>`
```
struct __cppobj AddExternalServerScreenController::_removeServer::__l2::<lambda_30c06750adf499f5d0d289c0997a750f>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_25c5858f0fc8ae988dd55f9656f5e21a>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_25c5858f0fc8ae988dd55f9656f5e21a>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_3ac9ff54814e36657da0aaa089db3704>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_3ac9ff54814e36657da0aaa089db3704>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_a085e19d35c263fe095caf4f6d7c35aa>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_a085e19d35c263fe095caf4f6d7c35aa>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_122883df80287d264b96b2522759b703>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_122883df80287d264b96b2522759b703>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_57a8dccad55a13442ed53775c26ab5ff>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_57a8dccad55a13442ed53775c26ab5ff>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_7145d8d99ce4b66543ab6310a96a18d3>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_7145d8d99ce4b66543ab6310a96a18d3>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_a3ce4ccbbc7d0fb5f04c5420f85d6559>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_a3ce4ccbbc7d0fb5f04c5420f85d6559>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerBindings::__l2::<lambda_4c09a3cdb9ca908ba64d0b453a891ba1>`
```
struct __cppobj AddExternalServerScreenController::_registerBindings::__l2::<lambda_4c09a3cdb9ca908ba64d0b453a891ba1>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_210b84a3357aff9801c49e6d41bb9d1e>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_210b84a3357aff9801c49e6d41bb9d1e>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_5bef4d6ad8845c54215acbdc9c9c91dc>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_5bef4d6ad8845c54215acbdc9c9c91dc>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_2ee7cdc08f4f1a97143aca7ba737cb07>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_2ee7cdc08f4f1a97143aca7ba737cb07>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_0d1617bb64501056dfa8bb42c837189b>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_0d1617bb64501056dfa8bb42c837189b>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_303e96a5b35fbe966fb028dae4edbc58>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_303e96a5b35fbe966fb028dae4edbc58>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_7865f5372337dbbeb164aee933dfc6f9>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_7865f5372337dbbeb164aee933dfc6f9>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_b3d1651fea36c945da38f4464b0bfd4f>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_b3d1651fea36c945da38f4464b0bfd4f>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_b3d1651fea36c945da38f4464b0bfd4f>::()::__l2::<lambda_6b47134c4ac948ad40ce687f3649d3af>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_b3d1651fea36c945da38f4464b0bfd4f>::()::__l2::<lambda_6b47134c4ac948ad40ce687f3649d3af>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_6a67c2c0d01f6a0a8774fd1ec807fc55>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_6a67c2c0d01f6a0a8774fd1ec807fc55>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_872e21447734c8e261295b49df405ced>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_872e21447734c8e261295b49df405ced>
{
  AddExternalServerScreenController *const __this;
};

```

### `AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_872e21447734c8e261295b49df405ced>::()::__l2::<lambda_97de3fdbeeebbfba5e0e5124aa5e6ac1>`
```
struct __cppobj AddExternalServerScreenController::_registerEventHandlers::__l2::<lambda_872e21447734c8e261295b49df405ced>::()::__l2::<lambda_97de3fdbeeebbfba5e0e5124aa5e6ac1>
{
  AddExternalServerScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_adc00087a4addc07837f75c2bf878f59>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_adc00087a4addc07837f75c2bf878f59>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_23acab4b48b0e89bb2ba847b7fd63339>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_23acab4b48b0e89bb2ba847b7fd63339>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_b6f2f6be136e5e794618db98de623271>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_b6f2f6be136e5e794618db98de623271>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_54ac0f7a06d0c15945d73e43fc8ab813>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerBindings::__l2::<lambda_54ac0f7a06d0c15945d73e43fc8ab813>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerEventHandlers::__l2::<lambda_11fcd74304d80132dee5377b22999b4e>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerEventHandlers::__l2::<lambda_11fcd74304d80132dee5377b22999b4e>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryModalsScreenController::_registerEventHandlers::__l2::<lambda_0d5f5018aefb836a741f09423b29a72a>`
```
struct __cppobj ActiveDirectoryModalsScreenController::_registerEventHandlers::__l2::<lambda_0d5f5018aefb836a741f09423b29a72a>
{
  ActiveDirectoryModalsScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_c3052e7588593ef483ee34d36d2823f1>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_c3052e7588593ef483ee34d36d2823f1>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_a4aeadee608dc88640568af43454006f>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_a4aeadee608dc88640568af43454006f>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_b797ff35791f7bdd32cf1b4f72438acc>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_b797ff35791f7bdd32cf1b4f72438acc>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_4314e38f3b923337622c4a37e8983c5d>::()::__l2::<lambda_b5fecdd292c0551dd59d7e74be7ac51d>`
```
struct __cppobj __declspec(align(8)) ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_4314e38f3b923337622c4a37e8983c5d>::()::__l2::<lambda_b5fecdd292c0551dd59d7e74be7ac51d>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
  _BYTE state[4];
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_f7a4a249834364b72cde345078f19b66>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_f7a4a249834364b72cde345078f19b66>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_09195b7ddac67ec185bb7e6b602d5f82>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_09195b7ddac67ec185bb7e6b602d5f82>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_5e12f522bbc09def8c641756362a2234>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_5e12f522bbc09def8c641756362a2234>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_3be11f7c05ba96dd836dc33d0902e1d8>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_3be11f7c05ba96dd836dc33d0902e1d8>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_315945de9c92561180b8ff2292374c2e>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_315945de9c92561180b8ff2292374c2e>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_eece61d1464a9b9cd0dbc48c3fa1f45b>::()::__l2::<lambda_1ab6c7fefc5522946dbe1fb2d833d12f>`
```
struct __cppobj __declspec(align(8)) ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_eece61d1464a9b9cd0dbc48c3fa1f45b>::()::__l2::<lambda_1ab6c7fefc5522946dbe1fb2d833d12f>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
  _BYTE state[4];
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_9bd4b11f8e04e51999e3c08fbf00aae5>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_9bd4b11f8e04e51999e3c08fbf00aae5>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_572ebddbf17f35733521baf01ad4881c>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_572ebddbf17f35733521baf01ad4881c>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_a555665e65f4a7ff83fe7e1eb5612f7d>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_a555665e65f4a7ff83fe7e1eb5612f7d>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_059d6be1bee1f19346311763485ab577>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_059d6be1bee1f19346311763485ab577>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_fcf61580120093f9633aea94e9f0718d>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_fcf61580120093f9633aea94e9f0718d>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_69f60c5b531f22ec064077f9a84b449a>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_69f60c5b531f22ec064077f9a84b449a>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_65b31b72913d5f3d426981ca09e55a93>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_65b31b72913d5f3d426981ca09e55a93>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_4e7d98532bb2253e9a0ed13c865e278f>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_4e7d98532bb2253e9a0ed13c865e278f>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_5fac8002981c4185a884758fee1a13be>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerBindings::__l2::<lambda_5fac8002981c4185a884758fee1a13be>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_246f809a0a50b6584f64bd944ecc4ae2>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_246f809a0a50b6584f64bd944ecc4ae2>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_6a3c6fe9d9738cc811f06548e7e4c4c6>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_6a3c6fe9d9738cc811f06548e7e4c4c6>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_f8d5733da01bf5b7e2eaec34ccfb14f0>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_f8d5733da01bf5b7e2eaec34ccfb14f0>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_98e29f040ae00cd17fc58401a54686ba>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_98e29f040ae00cd17fc58401a54686ba>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_f1568fde551cdb1620cfa312f35ecea2>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_f1568fde551cdb1620cfa312f35ecea2>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_232ab06bbca77c3a1526320ca864dd4b>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_232ab06bbca77c3a1526320ca864dd4b>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_742c739e58fd50bab8b71f665901ea5d>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_742c739e58fd50bab8b71f665901ea5d>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_7610e4af82e33d9dac8121f70f6ad84f>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_7610e4af82e33d9dac8121f70f6ad84f>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_c0f3190ac353574515633b9ae793129c>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_c0f3190ac353574515633b9ae793129c>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_2e4a8c553805b5cd4cdd13b6fca4977f>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_2e4a8c553805b5cd4cdd13b6fca4977f>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_a1231090b4fe840b1c240280fea62911>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_a1231090b4fe840b1c240280fea62911>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_fe02633477a7c550e4585f446b8dda44>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_registerEventHandlers::__l2::<lambda_fe02633477a7c550e4585f446b8dda44>
{
  ActiveDirectoryAuthenticationScreenController *const __this;
};

```

### `AchievementScreenController::_registerEventHandlers::__l2::<lambda_3f58ef1e180236119d6dd14cd81579f3>`
```
struct __cppobj AchievementScreenController::_registerEventHandlers::__l2::<lambda_3f58ef1e180236119d6dd14cd81579f3>
{
  AchievementScreenController *const __this;
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l10::<lambda_e4fbc38e9dfa17df7f608a96976c42d4>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l10::<lambda_e4fbc38e9dfa17df7f608a96976c42d4>
{
  const std::string correlationId;
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l10::<lambda_9231885270b5f237e6e6454bb16a1bb6>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l10::<lambda_9231885270b5f237e6e6454bb16a1bb6>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_bc28734ee88202a40a65f7a127f26503>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_bc28734ee88202a40a65f7a127f26503>
{
  const int errorCode;
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_8d473079e099b67922947bf39d5b319d>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_8d473079e099b67922947bf39d5b319d>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_d6402ccdc21b5959785ab884a9c70a41>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_d6402ccdc21b5959785ab884a9c70a41>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_b96a8abe92ac7d221a7ad7e9c2cca2fc>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_b96a8abe92ac7d221a7ad7e9c2cca2fc>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l7::<lambda_eb55e5d0dfd04976bc9a7b715452c710>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l7::<lambda_eb55e5d0dfd04976bc9a7b715452c710>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l5::<lambda_c10b09674df1c888b4058d3f60d8886c>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l5::<lambda_c10b09674df1c888b4058d3f60d8886c>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_855866b1c97b7612e28e265b5965c4a4>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_855866b1c97b7612e28e265b5965c4a4>
{
};

```

### `AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_6f6297535003066e574da66dc70e7995>`
```
struct __cppobj AccountTransferErrorScreenController::_registerBindings::__l2::<lambda_6f6297535003066e574da66dc70e7995>
{
  AccountTransferErrorScreenController *const __this;
};

```

### `AccountTransferErrorScreenController::{ctor}::__l2::<lambda_97876c23d33c2aa8288a8349167562ec>`
```
struct __cppobj AccountTransferErrorScreenController::{ctor}::__l2::<lambda_97876c23d33c2aa8288a8349167562ec>
{
  AccountTransferErrorScreenController *const __this;
};

```

### `AcceptDeclineInvitationScreenController::tick::__l6::<lambda_fef57ddce39f9cb463ca08fcaf36ae96>`
```
struct __cppobj AcceptDeclineInvitationScreenController::tick::__l6::<lambda_fef57ddce39f9cb463ca08fcaf36ae96>
{
  std::weak_ptr<AcceptDeclineInvitationScreenController> weakThis;
};

```

### `AcceptDeclineInvitationScreenController::tick::__l5::<lambda_8582705c392678cfaa5662cf4141fa0e>`
```
struct __cppobj AcceptDeclineInvitationScreenController::tick::__l5::<lambda_8582705c392678cfaa5662cf4141fa0e>
{
  std::weak_ptr<AcceptDeclineInvitationScreenController> weakThis;
};

```

### `ActiveDirectoryAuthenticationScreenController::_purchaseLicense::__l2::<lambda_59f5f3778b150a1938675ab8b0af00be>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_purchaseLicense::__l2::<lambda_59f5f3778b150a1938675ab8b0af00be>
{
  std::weak_ptr<ActiveDirectoryAuthenticationScreenController> weak_this;
};

```

### `ActiveDirectoryAuthenticationScreenController::_fulfillPriorPurchase::__l2::<lambda_71b3dc00def4f2cf3c927c167270b77f>`
```
struct __cppobj ActiveDirectoryAuthenticationScreenController::_fulfillPriorPurchase::__l2::<lambda_71b3dc00def4f2cf3c927c167270b77f>
{
  std::weak_ptr<ActiveDirectoryAuthenticationScreenController> weak_this;
};

```

### `ActorBlock`
```
struct __cppobj ActorBlock : BlockLegacy
{
};

```

### `ActorBlock_vtbl`
```
struct /*VFT*/ ActorBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  ItemInstance *(__fastcall *getEntityResourceItem)(ActorBlock *this, ItemInstance *result, Random *, const BlockActor *, int);
};

```

### `ArmorStandArmorModel`
```
struct __cppobj ArmorStandArmorModel : HumanoidModel
{
};

```

### `ArmorStandArmorModel_vtbl`
```
struct /*VFT*/ ArmorStandArmorModel_vtbl
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
};

```

### `ArmorStandModel`
```
struct __cppobj ArmorStandModel : ArmorStandArmorModel
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mBodyStick1;
  ModelPart mBodyStick2;
  ModelPart mShoulderStick;
  ModelPart mBasePlate;
};

```

### `ArmorStandModel_vtbl`
```
struct /*VFT*/ ArmorStandModel_vtbl
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
};

```

### `Animal`
```
struct __cppobj Animal : Mob
{
};

```

### `ArmorItem`
```
const struct __cppobj ArmorItem : Item
{
  const ArmorSlot mSlot;
  const int mDefense;
  const int mModelIndex;
  const ArmorItem::ArmorMaterial *mArmorType;
  std::unordered_map<int,ItemGraphics> mGraphics;
  std::unordered_map<std::string,ItemGraphics> mExtendGraphics;
  TextureUVCoordinateSet mUV;
  std::unordered_set<int> mModValueSet;
  std::unordered_set<std::string> mModExtendValueSet;
  std::unique_ptr<CustomArmorItemComponent> mCustomArmorComponent;
  TextureAtlasItem m_uvTextureItem;
};

```

### `AbstractArrow`
```
struct __cppobj AbstractArrow : PredictableProjectile
{
  int mFavoredSlot;
  bool mIsPlayerOwned;
  bool mIsCreative;
  MovementInterpolator mInterpolation;
};

```

### `AbstractArrow_vtbl`
```
struct /*VFT*/ AbstractArrow_vtbl
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
  void (__fastcall *shoot)(AbstractArrow *this, const Vec3 *, float, float, const Vec3 *);
  void (__fastcall *_playPickupSound)(AbstractArrow *this);
  ItemStack *(__fastcall *_getPickupItem)(AbstractArrow *this, ItemStack *result);
};

```

### `Arrow`
```
struct __cppobj Arrow : AbstractArrow
{
  int mLife;
  int mEnchantFlame;
  int mEnchantInfinity;
  std::vector<MobEffectInstance> mMobEffects;
};

```

### `Arrow_vtbl`
```
struct /*VFT*/ Arrow_vtbl
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
  void (__fastcall *shoot)(AbstractArrow *this, const Vec3 *, float, float, const Vec3 *);
  void (__fastcall *_playPickupSound)(AbstractArrow *this);
  ItemStack *(__fastcall *_getPickupItem)(AbstractArrow *this, ItemStack *result);
  void (__fastcall *applyParticleColor)(Arrow *this, Particle *);
  mce::Color *(__fastcall *getEffectColor)(Arrow *this, mce::Color *result);
};

```

### `AdhocHelper::enableAdhoc::__l2::<lambda_7b995f6365155ab0e605d2f73edaa8fb>`
```
struct __cppobj AdhocHelper::enableAdhoc::__l2::<lambda_7b995f6365155ab0e605d2f73edaa8fb>
{
};

```

### `AngryVillagerParticle`
```
struct __cppobj AngryVillagerParticle : HeartParticle
{
};

```

### `AngryVillagerParticle_vtbl`
```
struct /*VFT*/ AngryVillagerParticle_vtbl
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

### `AnimatedTextureTintCollection`
```
struct __cppobj __declspec(align(8)) AnimatedTextureTintCollection
{
  TextureTintCollection *mTextureTintCollection;
  unsigned int mUniqueTextureSetIdx;
};

```

### `AnimatedTextureContainer`
```
struct __cppobj AnimatedTextureContainer
{
  AnimatedTextureDefinition mTextureDefinition;
  unsigned int mMaxWidth;
  unsigned int mMaxHeight;
  std::vector<AnimatedTextureTintCollection> mTextureContainerCollection;
  std::vector<std::vector<std::pair<Core::PathBuffer<Core::StackString<char,1024> >,std::unique_ptr<mce::TextureContainer> >>> mUniqueTextureSets;
  std::unique_ptr<mce::TextureContainer> mAnimatedTextureContainer;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>::()::__l2::ResourcePath`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>::()::__l2::ResourcePath
{
  Core::PathBuffer<std::string > path;
};

```

### `ArmorStandRenderer`
```
struct __cppobj ArmorStandRenderer : HumanoidMobRenderer
{
};

```

### `ArmorStandRenderer_vtbl`
```
struct /*VFT*/ ArmorStandRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderDebug)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderEffects)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderTrading)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *, float);
  void (__fastcall *renderFlame)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderLeash)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *renderWaterHole)(ActorRenderer *this, BaseActorRenderContext *, ActorRenderData *);
  void (__fastcall *addAdditionalRenderingIfNeeded)(ActorRenderer *this, mce::TextureGroup *);
  void (__fastcall *renderWeaponEffect)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  void (__fastcall *renderBindEffects)(ActorRenderer *this, BaseActorRenderContext *, Actor *);
  AABB *(__fastcall *getRenderBounds)(ActorRenderer *this, AABB *result, const Actor *);
  Vec3 *(__fastcall *getLeashOffset)(ActorRenderer *this, Vec3 *result, Actor *, float, float, float, bool, bool);
  void (__fastcall *setIsOnScreen)(ActorRenderer *this, Actor *, const bool, float);
  bool (__fastcall *shouldUpdateBonesAndEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  bool (__fastcall *shouldUpdateEffectsIfOffScreen)(ActorRenderer *this, RenderParams *);
  void (__fastcall *_bindModelEffectRender)(ActorRenderer *this, BaseActorRenderContext *, Mob *);
  void (__fastcall *prepareCarriedItem)(MobRenderer *this, Model *, Mob *, const ItemStack *);
  void (__fastcall *setupPosition)(MobRenderer *this, const Actor *, const Vec3 *, Matrix *);
  void (__fastcall *setupRotations)(MobRenderer *this, const Actor *, float, float, Matrix *, float);
  float (__fastcall *getAttackAnim)(MobRenderer *this, Mob *, float);
  float (__fastcall *getBob)(MobRenderer *this, Mob *, float);
  float (__fastcall *getFlipDegrees)(MobRenderer *this, const Mob *);
  void (__fastcall *setupScale)(MobRenderer *this, const Mob *, Matrix *, float);
  void (__fastcall *renderModel)(MobRenderer *this, BaseActorRenderContext *, ActorRenderData *, Model *, const gsl::span<mce::ClientTexture const *,-1>, const unsigned __int64);
  void (__fastcall *additionalRendering)(MobRenderer *this, BaseActorRenderContext *, Model *, Mob *, float, float, float, float, float, float);
  void (__fastcall *renderLayers)(MobRenderer *this, BaseActorRenderContext *, Actor *, float, float, float, float, float);
  void (__fastcall *drawLayers)(MobRenderer *this, ScreenContext *);
  float (__fastcall *getSneakingHeightOffset)(MobRenderer *this);
  float (__fastcall *getSwimmingHeightOffset)(MobRenderer *this);
  MobRenderer::ArmorPrepareResult *(__fastcall *prepareArmor)(MobRenderer *this, MobRenderer::ArmorPrepareResult *result, ScreenContext *, BaseActorRenderContext *, Mob *, ArmorSlot, Model *, float);
  void (__fastcall *prepareCarriedOffhandItem)(HumanoidMobRenderer *this, Model *, Mob *, const ItemStack *);
  void (__fastcall *_bindModelRender)(HumanoidMobRenderer *this, BaseActorRenderContext *, HumanoidModel *, Mob *, float, float);
};

```

### `ActorResourceDefinitionGroup::_buildAnimationResourceDefinitionFileSchema_v1_10::__l2::<lambda_9bc6bbce877e6ff83c7a0a12d5ebd7cd>`
```
struct __cppobj ActorResourceDefinitionGroup::_buildAnimationResourceDefinitionFileSchema_v1_10::__l2::<lambda_9bc6bbce877e6ff83c7a0a12d5ebd7cd>
{
};

```

### `ActorResourceDefinitionGroup::_buildAnimationResourceDefinitionFileSchema_v1_8::__l2::<lambda_04afcfe0a1afae42feee5db077ca10f6>`
```
struct __cppobj ActorResourceDefinitionGroup::_buildAnimationResourceDefinitionFileSchema_v1_8::__l2::<lambda_04afcfe0a1afae42feee5db077ca10f6>
{
};

```

### `ActorResourceDefinitionGroup::loadBuiltInActorResourceDefinitions::__l2::<lambda_0e471e1648006f725df7e5d623467c20>`
```
struct __cppobj ActorResourceDefinitionGroup::loadBuiltInActorResourceDefinitions::__l2::<lambda_0e471e1648006f725df7e5d623467c20>
{
  const SemVersion engineVersion;
  IPackStorage *storage;
  std::vector<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >> *tasks;
  ResourceLoadManager *resourceLoadManager;
  ParticleEffectGroup *particleEffectGroup;
  ActorResourceDefinitionGroup *const __this;
};

```

### `ActorResourceDefinitionGroup::loadBuiltInActorResourceDefinitionsLegacy::__l2::<lambda_70e237b297f530029cf0c3a7f01cbca6>`
```
struct __cppobj ActorResourceDefinitionGroup::loadBuiltInActorResourceDefinitionsLegacy::__l2::<lambda_70e237b297f530029cf0c3a7f01cbca6>
{
  const SemVersion engineVersion;
  ActorResourceDefinitionGroup *const __this;
  ParticleEffectGroup *particleEffectGroup;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>
{
  ResourcePackManager *resourcePackManager;
  ResourceLoadManager *resourceLoadManager;
  ParticleEffectGroup *particleEffectGroup;
  ActorResourceDefinitionGroup *const __this;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l2::<lambda_09d35aee6314a075e4a3c4ae9813fa5b>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l2::<lambda_09d35aee6314a075e4a3c4ae9813fa5b>
{
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_083000e1747704c042ce5a579b73209e>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_083000e1747704c042ce5a579b73209e>
{
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *packIter;
  ResourceLoadManager *resourceLoadManager;
  const SemVersion engineVersion;
  ParticleEffectGroup *particleEffectGroup;
  ActorResourceDefinitionGroup *const __this;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_2c63919812be688e5e6bb507df095e2b>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_2c63919812be688e5e6bb507df095e2b>
{
  std::vector<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >> *allDefinitions;
  ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_083000e1747704c042ce5a579b73209e> *loadDefinition;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_083000e1747704c042ce5a579b73209e>::()::__l2::<lambda_6cdbff212f42135b40c9b964d1bd6670>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_f41878dbc20ba3d482cc3c3ebb110867>::()::__l8::<lambda_083000e1747704c042ce5a579b73209e>::()::__l2::<lambda_6cdbff212f42135b40c9b964d1bd6670>
{
  const Core::Path filenameWithExtension;
  const SemVersion engineVersion;
  ParticleEffectGroup *particleEffectGroup;
  PackStats *packStats;
  const bool isBaseGamePack;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > > ioTask;
  ActorResourceDefinitionGroup *const __this;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_1c54ecd2bdadd1052b2b2b49430ef2af>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_1c54ecd2bdadd1052b2b2b49430ef2af>
{
  std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> > loadBuiltInTask;
  ResourcePackManager *resourcePackManager;
  ActorResourceDefinitionGroup *const __this;
  ParticleEffectGroup *particleEffectGroup;
  ResourceLoadManager *resourceLoadManager;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_1c54ecd2bdadd1052b2b2b49430ef2af>::()::__l2::<lambda_18eed8696fd1b4e920f8dc0f735b7676>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l7::<lambda_1c54ecd2bdadd1052b2b2b49430ef2af>::()::__l2::<lambda_18eed8696fd1b4e920f8dc0f735b7676>
{
  std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> > loadBuiltInTask;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>
{
  ResourcePackManager *resourcePackManager;
  ActorResourceDefinitionGroup *const __this;
  ParticleEffectGroup *particleEffectGroup;
};

```

### `ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>::()::__l11::<lambda_4d72003231351324064f52293d650d0d>`
```
struct __cppobj ActorResourceDefinitionGroup::loadAsync::__l5::<lambda_c8709a315193d64f7619d793d7fa2ca6>::()::__l11::<lambda_4d72003231351324064f52293d650d0d>
{
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *packIter;
  ActorResourceDefinitionGroup *const __this;
  SemVersion *engineVersion;
  ParticleEffectGroup *particleEffectGroup;
};

```

### `ArrowEffectSubcomponent`
```
struct __cppobj ArrowEffectSubcomponent : MobEffectSubcomponent
{
};

```

### `ArrowEffectSubcomponent_vtbl`
```
struct /*VFT*/ ArrowEffectSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `ActorDefinitionEventSubcomponent`
```
struct __cppobj ActorDefinitionEventSubcomponent : OnHitSubcomponent
{
  bool mAffectShooter;
  bool mAffectProjectile;
  bool mAffectTarget;
  bool mAffectSplashArea;
  float mSplashArea;
  DefinitionTrigger mTrigger;
};

```

### `ActorDefinitionEventSubcomponent_vtbl`
```
struct /*VFT*/ ActorDefinitionEventSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `AtlasBuildParams`
```
struct __cppobj __declspec(align(8)) AtlasBuildParams
{
  const PageSettings pageSettings;
  int textureIndex;
  int reductionMips;
  int padSize;
};

```

### `ApplyClientItemBinding`
```
struct __cppobj ApplyClientItemBinding : ScriptTemplateFactory<ScriptClientContext>::Entity
{
};

```

### `ApplyClientItemBinding_vtbl`
```
struct /*VFT*/ ApplyClientItemBinding_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptClientContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptClientContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor **, const std::string *);
};

```

### `ApplyClientLegacyEntityBinding`
```
struct __cppobj ApplyClientLegacyEntityBinding : ScriptTemplateFactory<ScriptClientContext>::Entity
{
};

```

### `ApplyClientLegacyEntityBinding_vtbl`
```
struct /*VFT*/ ApplyClientLegacyEntityBinding_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptClientContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptClientContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptClientContext *, Actor **, const std::string *);
};

```

### `AppPlatformWindows`
```
struct __cppobj AppPlatformWindows : AppPlatform
{
  bool mGraphicsTearingSupport;
  Core::PathBuffer<std::string > mExternalStoragePath;
  Core::PathBuffer<std::string > mPlatformTempPath;
  Core::PathBuffer<std::string > mInternalStoragePath;
  Core::PathBuffer<std::string > mHomePath;
  MPMCQueue<std::function<void __cdecl(void)> > mMainThreadQueue;
};

```

### `AppDump`
```
struct __cppobj AppDump
{
};

```

### `ActivationUriWin32`
```
struct __cppobj ActivationUriWin32
{
};

```

### `AppInfo::AppInfoBase`
```
struct __cppobj AppInfo::AppInfoBase
{
  AppInfo::AppInfoBase_vtbl *__vftable /*VFT*/;
};

```

### `AppInfo::AppInfoBase_vtbl`
```
struct /*VFT*/ AppInfo::AppInfoBase_vtbl
{
  std::string *(__fastcall *GetWindowTitleName)(AppInfo::AppInfoBase *this, std::string *result);
  bool (__fastcall *ShouldDisplayScreenSizeInTitle)(AppInfo::AppInfoBase *this);
  std::string *(__fastcall *GetAppDataFolderName)(AppInfo::AppInfoBase *this, std::string *result);
  HICON__ *(__fastcall *GetIconLoader)(AppInfo::AppInfoBase *this, HINSTANCE__ *);
  glm::tvec2<float,0> *(__fastcall *GetWindowSizeMinimum)(AppInfo::AppInfoBase *this, glm::tvec2<float,0> *result);
};

```

### `AnimationEventComponent::AnimationStateData`
```
struct __cppobj __declspec(align(4)) AnimationEventComponent::AnimationStateData
{
  AnimationEventType mAnimation;
  bool mWasLastTickAnimated;
  bool mIsCurrentTickAnimated;
};

```

### `AnimationEventComponent`
```
struct __cppobj AnimationEventComponent : IEntityComponent
{
  std::vector<AnimationEventComponent::AnimationStateData> mObservedAnimationStates;
};

```

### `AnimationEventSystem`
```
struct __cppobj AnimationEventSystem : ITickingSystem
{
};

```

### `AnimationEventSystem_vtbl`
```
struct /*VFT*/ AnimationEventSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `AnimationEventSystem::getActorStatePollingCallbackFunction::__l2::<lambda_042e8c54b19be422a0fbc9fd39d5323f>`
```
struct __cppobj AnimationEventSystem::getActorStatePollingCallbackFunction::__l2::<lambda_042e8c54b19be422a0fbc9fd39d5323f>
{
};

```

### `AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_b370ed50d467e534fa57e670bf273dc5>`
```
struct __cppobj AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_b370ed50d467e534fa57e670bf273dc5>
{
};

```

### `AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_65ed58fafc12e5084764ad6bf541ec73>`
```
struct __cppobj AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_65ed58fafc12e5084764ad6bf541ec73>
{
};

```

### `AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_dbac4b9d1805f7a2568808d61f7f8bb4>`
```
struct __cppobj AnimationEventSystem::getActorStatePollingCallbackFunction::__l4::<lambda_dbac4b9d1805f7a2568808d61f7f8bb4>
{
};

```

### `AnimateEntityPacket::read::__l2::<lambda_aeb2137e9937c28d4b68be6ad967f904>`
```
struct __cppobj AnimateEntityPacket::read::__l2::<lambda_aeb2137e9937c28d4b68be6ad967f904>
{
};

```

### `AnimateEntityPacket::write::__l2::<lambda_cc13a20d482e302c276616a0b1502546>`
```
struct __cppobj AnimateEntityPacket::write::__l2::<lambda_cc13a20d482e302c276616a0b1502546>
{
};

```

### `ActorPlacerItem::registerCustomEggs::__l2::<lambda_c44bb3bf22736a80395aa3782bcaf1ef>`
```
struct __cppobj ActorPlacerItem::registerCustomEggs::__l2::<lambda_c44bb3bf22736a80395aa3782bcaf1ef>
{
  BaseGameVersion *kHolidayUpdate2020Version;
};

```

### `ActorPlacerItem::spawnOrMoveAgent::__l8::<lambda_43cd74415f19ea58a1fb14989e1abb7c>`
```
struct __cppobj ActorPlacerItem::spawnOrMoveAgent::__l8::<lambda_43cd74415f19ea58a1fb14989e1abb7c>
{
  Agent **existingAgent;
  const Vec3 *spawnPos;
};

```

### `ActorCommandOrigin`
```
struct __cppobj ActorCommandOrigin : CommandOrigin
{
  ActorUniqueID mEntityId;
  Level *mLevel;
};

```

### `ActorCommandOrigin_vtbl`
```
struct /*VFT*/ ActorCommandOrigin_vtbl
{
  void (__fastcall *~CommandOrigin)(CommandOrigin *this);
  const std::string *(__fastcall *getRequestId)(CommandOrigin *this);
  std::string *(__fastcall *getName)(CommandOrigin *this, std::string *result);
  BlockPos *(__fastcall *getBlockPosition)(CommandOrigin *this, BlockPos *result);
  Vec3 *(__fastcall *getWorldPosition)(CommandOrigin *this, Vec3 *result);
  Level *(__fastcall *getLevel)(CommandOrigin *this);
  Dimension *(__fastcall *getDimension)(CommandOrigin *this);
  Actor *(__fastcall *getEntity)(CommandOrigin *this);
  CommandPermissionLevel (__fastcall *getPermissionsLevel)(CommandOrigin *this);
  std::unique_ptr<CommandOrigin> *(__fastcall *clone)(CommandOrigin *this, std::unique_ptr<CommandOrigin> *result);
  std::optional<BlockPos> *(__fastcall *getCursorHitBlockPos)(CommandOrigin *this, std::optional<BlockPos> *result);
  std::optional<Vec3> *(__fastcall *getCursorHitPos)(CommandOrigin *this, std::optional<Vec3> *result);
  bool (__fastcall *hasChatPerms)(CommandOrigin *this);
  bool (__fastcall *hasTellPerms)(CommandOrigin *this);
  bool (__fastcall *canUseAbility)(CommandOrigin *this, AbilitiesIndex);
  bool (__fastcall *isWorldBuilder)(CommandOrigin *this);
  bool (__fastcall *canUseCommandsWithoutCheatsEnabled)(CommandOrigin *this);
  bool (__fastcall *isSelectorExpansionAllowed)(CommandOrigin *this);
  const NetworkIdentifier *(__fastcall *getSourceId)(CommandOrigin *this);
  unsigned __int8 (__fastcall *getSourceSubId)(CommandOrigin *this);
  const CommandOrigin *(__fastcall *getOutputReceiver)(CommandOrigin *this);
  CommandOriginType (__fastcall *getOriginType)(CommandOrigin *this);
  CommandOriginData *(__fastcall *toCommandOriginData)(CommandOrigin *this, CommandOriginData *result);
  const mce::UUID *(__fastcall *getUUID)(CommandOrigin *this);
  void (__fastcall *handleCommandOutputCallback)(CommandOrigin *this, Json::Value *);
  void (__fastcall *_setUUID)(CommandOrigin *this, const mce::UUID *);
};

```

### `ActorServerCommandOrigin`
```
struct __cppobj ActorServerCommandOrigin : ActorCommandOrigin
{
};

```

### `ActorServerCommandOrigin_vtbl`
```
struct /*VFT*/ ActorServerCommandOrigin_vtbl
{
  void (__fastcall *~CommandOrigin)(CommandOrigin *this);
  const std::string *(__fastcall *getRequestId)(CommandOrigin *this);
  std::string *(__fastcall *getName)(CommandOrigin *this, std::string *result);
  BlockPos *(__fastcall *getBlockPosition)(CommandOrigin *this, BlockPos *result);
  Vec3 *(__fastcall *getWorldPosition)(CommandOrigin *this, Vec3 *result);
  Level *(__fastcall *getLevel)(CommandOrigin *this);
  Dimension *(__fastcall *getDimension)(CommandOrigin *this);
  Actor *(__fastcall *getEntity)(CommandOrigin *this);
  CommandPermissionLevel (__fastcall *getPermissionsLevel)(CommandOrigin *this);
  std::unique_ptr<CommandOrigin> *(__fastcall *clone)(CommandOrigin *this, std::unique_ptr<CommandOrigin> *result);
  std::optional<BlockPos> *(__fastcall *getCursorHitBlockPos)(CommandOrigin *this, std::optional<BlockPos> *result);
  std::optional<Vec3> *(__fastcall *getCursorHitPos)(CommandOrigin *this, std::optional<Vec3> *result);
  bool (__fastcall *hasChatPerms)(CommandOrigin *this);
  bool (__fastcall *hasTellPerms)(CommandOrigin *this);
  bool (__fastcall *canUseAbility)(CommandOrigin *this, AbilitiesIndex);
  bool (__fastcall *isWorldBuilder)(CommandOrigin *this);
  bool (__fastcall *canUseCommandsWithoutCheatsEnabled)(CommandOrigin *this);
  bool (__fastcall *isSelectorExpansionAllowed)(CommandOrigin *this);
  const NetworkIdentifier *(__fastcall *getSourceId)(CommandOrigin *this);
  unsigned __int8 (__fastcall *getSourceSubId)(CommandOrigin *this);
  const CommandOrigin *(__fastcall *getOutputReceiver)(CommandOrigin *this);
  CommandOriginType (__fastcall *getOriginType)(CommandOrigin *this);
  CommandOriginData *(__fastcall *toCommandOriginData)(CommandOrigin *this, CommandOriginData *result);
  const mce::UUID *(__fastcall *getUUID)(CommandOrigin *this);
  void (__fastcall *handleCommandOutputCallback)(CommandOrigin *this, Json::Value *);
  void (__fastcall *_setUUID)(CommandOrigin *this, const mce::UUID *);
};

```

### `ActiveDirectoryIdentity::<lambda_ce67a8d6265ddb316cf66ab564733539>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_ce67a8d6265ddb316cf66ab564733539>
{
};

```

### `ActiveDirectoryIdentity::<lambda_667c444597a0187b4830a522ddb23a2a>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_667c444597a0187b4830a522ddb23a2a>
{
};

```

### `ActiveDirectoryIdentity::<lambda_4f7dce98332b2061534d162fd48b4ba4>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_4f7dce98332b2061534d162fd48b4ba4>
{
};

```

### `ActiveDirectoryIdentity::<lambda_27c1fc2a7267eff3e8a34c7cd9c7dc43>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_27c1fc2a7267eff3e8a34c7cd9c7dc43>
{
};

```

### `ActiveDirectoryIdentity::<lambda_c36df1194d513611863029766eb981a7>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_c36df1194d513611863029766eb981a7>
{
};

```

### `ActiveDirectoryIdentity::<lambda_dd7626df76dc434be93e45fba96515b3>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_dd7626df76dc434be93e45fba96515b3>
{
};

```

### `ActiveDirectoryIdentity::<lambda_1b79d4f9d8405d83f86032214b29f9bc>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_1b79d4f9d8405d83f86032214b29f9bc>
{
};

```

### `ActiveDirectoryIdentity::<lambda_a851e8022b0978e869e3fcde18078640>`
```
struct __cppobj ActiveDirectoryIdentity::<lambda_a851e8022b0978e869e3fcde18078640>
{
};

```

### `ActiveDirectoryIdentityTelemetry`
```
struct __cppobj ActiveDirectoryIdentityTelemetry : IActiveDirectoryIdentityTelemetry
{
  IMinecraftEventing *mEventing;
};

```

### `ActiveDirectorySSOPolicy`
```
struct __cppobj ActiveDirectorySSOPolicy : ActiveDirectoryPolicy
{
  Options *mOptions;
  int mFailedRefreshAttempts;
  __int64 mLastRefreshAttempt;
  std::function<__int64 __cdecl(void)> mGetCurrentTime;
};

```

### `ActiveDirectorySSOPolicy_vtbl`
```
struct /*VFT*/ ActiveDirectorySSOPolicy_vtbl
{
  void (__fastcall *~ActiveDirectoryPolicy)(ActiveDirectoryPolicy *this);
  ADDialogMode (__fastcall *getDialogMode)(ActiveDirectoryPolicy *this);
  EducationEditionOffer (__fastcall *getEducationOffer)(ActiveDirectoryPolicy *this);
  bool (__fastcall *shouldAttemptTokenRefresh)(ActiveDirectoryPolicy *this, const AccessTokenInfo *);
  void (__fastcall *onTokenRefreshAction)(ActiveDirectoryPolicy *this, ADTokenRefreshAction);
  void (__fastcall *onSignInAttempt)(ActiveDirectoryPolicy *this);
  void (__fastcall *onSignInSuccess)(ActiveDirectoryPolicy *this);
  void (__fastcall *resetAuthenticationState)(ActiveDirectoryPolicy *this);
};

```

### `ActiveDirectorySSOPolicy::<lambda_677cad9fdee0094a32621e22572ef503>`
```
struct __cppobj ActiveDirectorySSOPolicy::<lambda_677cad9fdee0094a32621e22572ef503>
{
};

```

### `ActiveDirectoryIdentity::_identityGained::__l2::<lambda_4b2742cae1a8c99f03fc99d2800b6419>`
```
struct __cppobj ActiveDirectoryIdentity::_identityGained::__l2::<lambda_4b2742cae1a8c99f03fc99d2800b6419>
{
  ActiveDirectoryIdentity *const __this;
};

```

### `ActiveDirectoryIdentity::resetAuthenticationState::__l2::<lambda_2ad8df763f18006e47abe164b915e4da>`
```
struct __cppobj ActiveDirectoryIdentity::resetAuthenticationState::__l2::<lambda_2ad8df763f18006e47abe164b915e4da>
{
  ActiveDirectoryIdentity *const __this;
};

```

### `AddRiderDefinition`
```
struct __cppobj AddRiderDefinition
{
  ActorDefinitionIdentifier mEntityType;
};

```

### `AdmireItemDefinition`
```
struct __cppobj AdmireItemDefinition
{
  int mDuration;
  int mCooldown;
};

```

### `ActorDefinitionFeedItem`
```
struct __cppobj __declspec(align(8)) ActorDefinitionFeedItem
{
  ItemDescriptor mItemDescriptor;
  float mGrowth;
};

```

### `AgeableDefinition`
```
struct __cppobj AgeableDefinition
{
  float mSecondsAsBaby;
  std::vector<ActorDefinitionFeedItem> mFeedItems;
  std::vector<ItemDescriptor> mDropItems;
  DefinitionTrigger mOnGrowUp;
};

```

### `AgeableComponent`
```
struct __cppobj AgeableComponent : IEntityComponent
{
  int mAge;
};

```

### `AgentCommands::Command`
```
struct __cppobj __declspec(align(8)) AgentCommands::Command
{
  AgentCommands::Command_vtbl *__vftable /*VFT*/;
  Actor *mTarget;
  Player *mCommander;
  std::string mCommandName;
  bool mResult;
  bool mIsQueryResult;
};

```

### `AgentCommandComponent`
```
struct __cppobj __declspec(align(8)) AgentCommandComponent : IEntityComponent
{
  std::unique_ptr<AgentCommands::Command> mCurrentCommand;
  int mWaitForNextCommandTicks;
};

```

### `AngryDefinition`
```
struct __cppobj AngryDefinition
{
  int mDuration;
  int mDurationDelta;
  bool mBroadcastAnger;
  bool mBroadcastOnAttack;
  bool mBroadcastOnBeingAttacked;
  int mBroadcastRange;
  ActorFilterGroup mBroadcastFilter;
  DefinitionTrigger mOnCalm;
  std::vector<HashedString> mBroadcastTargets;
  ActorFilterGroup mSubjectFilter;
  std::string mAngrySound;
  FloatRange mSoundInterval;
};

```

### `AreaAttackDefinition`
```
struct __cppobj AreaAttackDefinition
{
  float mDamageRange;
  int mDamagePerTick;
  _BYTE mDamageCause[4];
  ActorFilterGroup mEntityFilter;
};

```

### `AreaAttackComponent`
```
struct __cppobj AreaAttackComponent : IEntityComponent
{
  float mDamageRange;
  int mDamagePerTick;
  _BYTE mDamageCause[4];
  ActorFilterGroup mEntityFilter;
};

```

### `AgeableComponent::getInteraction::__l17::<lambda_e767bb2a9848be6a0fe0b51e7d80ffb5>`
```
struct __cppobj AgeableComponent::getInteraction::__l17::<lambda_e767bb2a9848be6a0fe0b51e7d80ffb5>
{
  Actor *actor;
  Player *player;
  AgeableComponent *const __this;
  const AgeableDefinition *ageableDef;
  const std::_Vector_const_iterator<std::_Vector_val<std::_Simple_types<ActorDefinitionFeedItem> > > iter;
};

```

### `AddRiderDefinition::buildSchema::__l2::<lambda_de3f784041109f70c0ae01e2dab848cc>`
```
struct __cppobj AddRiderDefinition::buildSchema::__l2::<lambda_de3f784041109f70c0ae01e2dab848cc>
{
};

```

### `AddRiderDefinition::buildSchema::__l2::<lambda_8b5ef7df67cbbf17bc489423c984239d>`
```
struct __cppobj AddRiderDefinition::buildSchema::__l2::<lambda_8b5ef7df67cbbf17bc489423c984239d>
{
};

```

### `AttackCooldownComponent::AttackCooldownDefinition::buildSchema::__l2::<lambda_62d08060130edb2644d349d6471838c7>`
```
struct __cppobj AttackCooldownComponent::AttackCooldownDefinition::buildSchema::__l2::<lambda_62d08060130edb2644d349d6471838c7>
{
  bool cooldownJsonRequired;
  std::string cooldownField;
};

```

### `AttackCooldownComponent::AttackCooldownDefinition::buildSchema::__l2::<lambda_a871b8e52fe3b77a3b0b151d11a00d18>`
```
struct __cppobj AttackCooldownComponent::AttackCooldownDefinition::buildSchema::__l2::<lambda_a871b8e52fe3b77a3b0b151d11a00d18>
{
};

```

### `AmphibiousMoveControl`
```
struct __cppobj AmphibiousMoveControl : GenericMoveControl
{
};

```

### `AmphibiousMoveControl_vtbl`
```
struct /*VFT*/ AmphibiousMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `ActorDamageByActorSource_vtbl`
```
struct /*VFT*/ ActorDamageByActorSource_vtbl
{
  void (__fastcall *~ActorDamageSource)(ActorDamageSource *this);
  bool (__fastcall *isEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isChildEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isBlockSource)(ActorDamageSource *this);
  bool (__fastcall *isFire)(ActorDamageSource *this);
  std::pair<std::string,std::vector<std::string> > *(__fastcall *getDeathMessage)(ActorDamageSource *this, std::pair<std::string,std::vector<std::string> > *result, std::string, Actor *);
  bool (__fastcall *getIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getEntityCategories)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getDamagingEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getDamagingEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getDamagingEntityCategories)(ActorDamageSource *this);
  std::unique_ptr<ActorDamageSource> *(__fastcall *clone)(ActorDamageSource *this, std::unique_ptr<ActorDamageSource> *result);
};

```

### `ActorDamageByChildActorSource_vtbl`
```
struct /*VFT*/ ActorDamageByChildActorSource_vtbl
{
  void (__fastcall *~ActorDamageSource)(ActorDamageSource *this);
  bool (__fastcall *isEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isChildEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isBlockSource)(ActorDamageSource *this);
  bool (__fastcall *isFire)(ActorDamageSource *this);
  std::pair<std::string,std::vector<std::string> > *(__fastcall *getDeathMessage)(ActorDamageSource *this, std::pair<std::string,std::vector<std::string> > *result, std::string, Actor *);
  bool (__fastcall *getIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getEntityCategories)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getDamagingEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getDamagingEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getDamagingEntityCategories)(ActorDamageSource *this);
  std::unique_ptr<ActorDamageSource> *(__fastcall *clone)(ActorDamageSource *this, std::unique_ptr<ActorDamageSource> *result);
};

```

### `AreaEffectCloud`
```
struct __cppobj AreaEffectCloud : Actor
{
  ActorUniqueID mOwnerId;
  bool mAffectOwner;
  __int64 mSpawnTickClient;
  int mReapplicationDelay;
  int mDurationOnUse;
  int mLocalPickupCount;
  float mRadiusOnUse;
  std::vector<MobEffectInstance> mMobAreaEffects;
  std::unordered_map<ActorUniqueID,int> mVictims;
};

```

### `AreaEffectCloud_vtbl`
```
struct /*VFT*/ AreaEffectCloud_vtbl
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

### `AngrySystem`
```
struct __cppobj AngrySystem : ITickingSystem
{
};

```

### `AngrySystem_vtbl`
```
struct /*VFT*/ AngrySystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `AreaAttackSystem`
```
struct __cppobj AreaAttackSystem : ITickingSystem
{
};

```

### `AreaAttackSystem_vtbl`
```
struct /*VFT*/ AreaAttackSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `ActorFlagComponent<EnvironmentSensorFlag>`
```
struct __cppobj ActorFlagComponent<EnvironmentSensorFlag> : IEntityComponent
{
};

```

### `AddActorPacket::read::__l2::<lambda_9c1640eaea0980dfaacbde9d289147d6>`
```
struct __cppobj AddActorPacket::read::__l2::<lambda_9c1640eaea0980dfaacbde9d289147d6>
{
};

```

### `AddActorPacket::read::__l2::<lambda_e7da630dfb9ff6070d9f2fa8bc4ce5b8>`
```
struct __cppobj AddActorPacket::read::__l2::<lambda_e7da630dfb9ff6070d9f2fa8bc4ce5b8>
{
};

```

### `AddActorPacket::write::__l2::<lambda_254c5a822980d3169cda537f925307fd>`
```
struct __cppobj AddActorPacket::write::__l2::<lambda_254c5a822980d3169cda537f925307fd>
{
};

```

### `AddActorPacket::write::__l2::<lambda_3ee8c7b64714874d246a2a524c5ff6d5>`
```
struct __cppobj AddActorPacket::write::__l2::<lambda_3ee8c7b64714874d246a2a524c5ff6d5>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_fddb570a9906ca99920d3760e0bf6181>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_fddb570a9906ca99920d3760e0bf6181>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_fddb570a9906ca99920d3760e0bf6181>::()::__l2::<lambda_58337035f40cdb40a0ad78974caef65d>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_fddb570a9906ca99920d3760e0bf6181>::()::__l2::<lambda_58337035f40cdb40a0ad78974caef65d>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_ebe74b4e5d6d797991571878ebe29051>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_ebe74b4e5d6d797991571878ebe29051>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_ebe74b4e5d6d797991571878ebe29051>::()::__l2::<lambda_34c85e54454e8cb623eb473d21878a16>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_ebe74b4e5d6d797991571878ebe29051>::()::__l2::<lambda_34c85e54454e8cb623eb473d21878a16>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>::()::__l2::<lambda_c0bf90ea14258b2f8991112a700688c4>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>::()::__l2::<lambda_c0bf90ea14258b2f8991112a700688c4>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>::()::__l2::<lambda_c0bf90ea14258b2f8991112a700688c4>::()::__l2::<lambda_1bb57af7bb907097486fe4cf8eb1c348>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_9b734f202ff1643505f9cda9ceaf1f45>::()::__l2::<lambda_c0bf90ea14258b2f8991112a700688c4>::()::__l2::<lambda_1bb57af7bb907097486fe4cf8eb1c348>
{
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_d661de69b42ca92dd49385cac8078d0c>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_d661de69b42ca92dd49385cac8078d0c>
{
  std::function<unsigned int __cdecl(ReadOnlyBinaryStream &)> *getIndex;
};

```

### `AvailableCommandsPacket::read::__l2::<lambda_36acc9cc739092955f5a497ea386b852>`
```
struct __cppobj AvailableCommandsPacket::read::__l2::<lambda_36acc9cc739092955f5a497ea386b852>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_f53ea0273569e5aefcd6fa55e89d3bbb>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_f53ea0273569e5aefcd6fa55e89d3bbb>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_f53ea0273569e5aefcd6fa55e89d3bbb>::()::__l2::<lambda_d3503244fa4efea213b9a788655a0d6e>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_f53ea0273569e5aefcd6fa55e89d3bbb>::()::__l2::<lambda_d3503244fa4efea213b9a788655a0d6e>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_a7740962927915b274e906ab2074fa79>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_a7740962927915b274e906ab2074fa79>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_a7740962927915b274e906ab2074fa79>::()::__l2::<lambda_f04ef0465c9436d39afcb81b12b495e8>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_a7740962927915b274e906ab2074fa79>::()::__l2::<lambda_f04ef0465c9436d39afcb81b12b495e8>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>::()::__l2::<lambda_6e93b29072b86913e00ce56b1487d5c9>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>::()::__l2::<lambda_6e93b29072b86913e00ce56b1487d5c9>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>::()::__l2::<lambda_6e93b29072b86913e00ce56b1487d5c9>::()::__l2::<lambda_d57fae2da5e325078f84e77a43f52c51>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_2da3d927c94b9216824bff6bbfca0ffb>::()::__l2::<lambda_6e93b29072b86913e00ce56b1487d5c9>::()::__l2::<lambda_d57fae2da5e325078f84e77a43f52c51>
{
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_ca9907655a4681d57112e430d7539b84>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_ca9907655a4681d57112e430d7539b84>
{
  std::function<void __cdecl(BinaryStream &,unsigned int const &)> *writeIndex;
};

```

### `AvailableCommandsPacket::write::__l2::<lambda_cde5c298d326b3afdafcf93c4ad4941c>`
```
struct __cppobj AvailableCommandsPacket::write::__l2::<lambda_cde5c298d326b3afdafcf93c4ad4941c>
{
};

```

### `AddPlayerPacket::read::__l2::<lambda_a233cfc2366cb543560d0b07234e2a11>`
```
struct __cppobj AddPlayerPacket::read::__l2::<lambda_a233cfc2366cb543560d0b07234e2a11>
{
};

```

### `AddPlayerPacket::write::__l2::<lambda_4a04fd1700a04dd1ddedfbc3695ecf27>`
```
struct __cppobj AddPlayerPacket::write::__l2::<lambda_4a04fd1700a04dd1ddedfbc3695ecf27>
{
};

```

### `AvailableCommandsPacket::read::__l11::<lambda_6d8f7a554002ce89eecc75743a9df7f2>`
```
struct __cppobj AvailableCommandsPacket::read::__l11::<lambda_6d8f7a554002ce89eecc75743a9df7f2>
{
};

```

### `AvailableCommandsPacket::read::__l9::<lambda_c8d5aa27a7205606f8d21b3a690aca38>`
```
struct __cppobj AvailableCommandsPacket::read::__l9::<lambda_c8d5aa27a7205606f8d21b3a690aca38>
{
};

```

### `AvailableCommandsPacket::read::__l5::<lambda_f60bbcf13875e779b35ca0e753b58446>`
```
struct __cppobj AvailableCommandsPacket::read::__l5::<lambda_f60bbcf13875e779b35ca0e753b58446>
{
};

```

### `AvailableCommandsPacket::write::__l11::<lambda_0bd9c6007b34770ae467d02211cf913f>`
```
struct __cppobj AvailableCommandsPacket::write::__l11::<lambda_0bd9c6007b34770ae467d02211cf913f>
{
};

```

### `AvailableCommandsPacket::write::__l9::<lambda_98418256727ebba2bf000405119fe3fb>`
```
struct __cppobj AvailableCommandsPacket::write::__l9::<lambda_98418256727ebba2bf000405119fe3fb>
{
};

```

### `AvailableCommandsPacket::write::__l5::<lambda_da717ab581dfbdf36924d91eac003090>`
```
struct __cppobj AvailableCommandsPacket::write::__l5::<lambda_da717ab581dfbdf36924d91eac003090>
{
};

```

### `AgentServerCommands`
```
struct __cppobj AgentServerCommands
{
};

```

### `AgentCommand`
```
struct __cppobj __declspec(align(8)) AgentCommand : Command
{
  AgentCommand::Mode mMode;
  _BYTE mCollectMode[4];
  _BYTE mDirection[1];
  CommandItem mItem;
  int mSlot;
  int mDestination;
  int mQuantity;
  int mAux;
  CommandPosition mPos;
  bool mIsPosSet;
  float mYRot;
  bool mIsYRotSet;
};

```

### `AgentCommand_vtbl`
```
struct /*VFT*/ AgentCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `AgentCommand::CommandInfo`
```
struct __cppobj AgentCommand::CommandInfo
{
  AgentCommand::Mode mode;
  const char *name;
  std::function<std::unique_ptr<AgentCommands::Command> __cdecl(Player &)> function;
};

```

### `AutomationPlayerCommandOrigin`
```
struct __cppobj AutomationPlayerCommandOrigin : PlayerCommandOrigin
{
  std::string mRequestId;
  _BYTE mPlayerPermission[1];
  NetworkIdentifier mSource;
};

```

### `AsynchronousIPResolver::_resolve::__l2::<lambda_8b0c693b68d9bca3b3e39ec805ef5d5d>`
```
struct __cppobj AsynchronousIPResolver::_resolve::__l2::<lambda_8b0c693b68d9bca3b3e39ec805ef5d5d>
{
  std::string url;
  std::weak_ptr<AsynchronousIPResolver::ResolvedIp> weakPtr;
};

```

### `AbilityCommand`
```
struct __cppobj __declspec(align(8)) AbilityCommand : Command
{
  CommandSelector<Player> mTargets;
  std::string mAbilityName;
  bool mValue;
  bool mHaveValue;
};

```

### `AbilityCommand_vtbl`
```
struct /*VFT*/ AbilityCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `AgentCommands::CollectCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::CollectCommand : AgentCommands::Command
{
  int mItemId;
  _BYTE mCollecting[4];
  bool mDone;
};

```

### `AgentCommands::GetItemCountCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::GetItemCountCommand : AgentCommands::Command
{
  int mCount;
};

```

### `AgentCommands::GetItemDetailsCommand`
```
struct __cppobj AgentCommands::GetItemDetailsCommand : AgentCommands::Command
{
  ItemStack mItem;
};

```

### `AgentCommands::GetItemSpaceCommand`
```
struct __cppobj AgentCommands::GetItemSpaceCommand : AgentCommands::Command
{
  int mCount;
  int mMaxCount;
};

```

### `AgentCommands::TransferToCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::TransferToCommand : AgentCommands::Command
{
  int mSrcSlot;
  int mQuantity;
  int mDestSlot;
};

```

### `AgentCommands::DropCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::DropCommand : AgentCommands::Command
{
  _BYTE mDir[1];
  int mSlotNum;
  int mQuantity;
};

```

### `AgentCommands::PlaceCommand`
```
struct __cppobj __declspec(align(4)) AgentCommands::PlaceCommand : AgentCommands::Command
{
  ItemStack mItem;
  int mSlot;
  _BYTE mDir[1];
};

```

### `AgentCommands::TurnCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::TurnCommand : AgentCommands::Command
{
  _BYTE mDir[1];
  float mTurnStep;
  float mRotation;
};

```

### `AgentCommands::AttackCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::AttackCommand : AgentCommands::Command
{
  _BYTE mDir[1];
};

```

### `AgentCommands::DestroyCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::DestroyCommand : AgentCommands::Command
{
  _BYTE mDir[1];
};

```

### `AgentCommands::DetectCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::DetectCommand : AgentCommands::Command
{
  _BYTE mDir[1];
};

```

### `AgentCommands::DetectRedstoneCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::DetectRedstoneCommand : AgentCommands::Command
{
  _BYTE mDir[1];
};

```

### `AgentCommands::DropAllCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::DropAllCommand : AgentCommands::Command
{
  _BYTE mDir[1];
};

```

### `AgentCommands::InspectCommand`
```
struct __cppobj AgentCommands::InspectCommand : AgentCommands::Command
{
  _BYTE mDir[1];
  std::string mBlockName;
};

```

### `AgentCommands::InspectDataCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::InspectDataCommand : AgentCommands::Command
{
  _BYTE mDir[1];
  const unsigned __int16 mData;
};

```

### `AgentCommands::MoveCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::MoveCommand : AgentCommands::Command
{
  _BYTE mDir[1];
  Vec3 mPosition;
  bool mTicked;
  Vec3 mStartingPosition;
  Vec3 mIdealMovementVector;
};

```

### `AgentCommands::TillCommand`
```
struct __cppobj __declspec(align(8)) AgentCommands::TillCommand : AgentCommands::Command
{
  ItemStack mItem;
  _BYTE mDir[1];
};

```

### `AgentCommand::getPosition::__l2::<lambda_3e96a3ead17b2ab4ddf8c4a669029e35>`
```
struct __cppobj AgentCommand::getPosition::__l2::<lambda_3e96a3ead17b2ab4ddf8c4a669029e35>
{
  CommandOutput *output;
  bool *success;
};

```

### `AgentCommand::setItem::__l2::<lambda_7dd918dc44ae3ad37a883a65f0ad623a>`
```
struct __cppobj AgentCommand::setItem::__l2::<lambda_7dd918dc44ae3ad37a883a65f0ad623a>
{
  const AgentCommand *const __this;
  bool *success;
};

```

### `AgentCommand::directionCommand::__l2::<lambda_2819147744a005275b35882055941e72>`
```
struct __cppobj AgentCommand::directionCommand::__l2::<lambda_2819147744a005275b35882055941e72>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::place::__l2::<lambda_faaf808e034e491eeae62fc3f702174f>`
```
struct __cppobj AgentCommand::place::__l2::<lambda_faaf808e034e491eeae62fc3f702174f>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::collect::__l2::<lambda_3ac2b88fe6a7fd9299f05b3360d688c3>`
```
struct __cppobj AgentCommand::collect::__l2::<lambda_3ac2b88fe6a7fd9299f05b3360d688c3>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::drop::__l2::<lambda_3cabf26a95b935b0467af9714fc255a0>`
```
struct __cppobj AgentCommand::drop::__l2::<lambda_3cabf26a95b935b0467af9714fc255a0>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::transfer::__l2::<lambda_dd67bbe47f89e02b623f54af5ac5a583>`
```
struct __cppobj AgentCommand::transfer::__l2::<lambda_dd67bbe47f89e02b623f54af5ac5a583>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::itemCommand::__l2::<lambda_991d09b4c3f0608e0ec9c2b5c48a8f49>`
```
struct __cppobj AgentCommand::itemCommand::__l2::<lambda_991d09b4c3f0608e0ec9c2b5c48a8f49>
{
  const AgentCommand *const __this;
};

```

### `AgentCommand::tpAgent::__l8::<lambda_71493e86f13de6b0f95fe7823ff4ff36>`
```
struct __cppobj AgentCommand::tpAgent::__l8::<lambda_71493e86f13de6b0f95fe7823ff4ff36>
{
  Agent **existing;
  Vec3 *tpPos;
};

```

### `AbilityCommand::execute::__l21::<lambda_bd159a685a5298c5a3f1cd6eaae1b722>`
```
struct __cppobj AbilityCommand::execute::__l21::<lambda_bd159a685a5298c5a3f1cd6eaae1b722>
{
  std::string *displayString;
  Json::Value *resultAbilities;
};

```

### `AbilityCommand::setup::__l2::<lambda_b8d60d3e63b89224cdd6873a1542bf34>`
```
struct __cppobj AbilityCommand::setup::__l2::<lambda_b8d60d3e63b89224cdd6873a1542bf34>
{
  std::vector<std::string> *abilityNames;
};

```

### `ApplyItemBinding`
```
struct __cppobj ApplyItemBinding : ScriptTemplateFactory<ScriptServerContext>::Entity
{
};

```

### `ApplyItemBinding_vtbl`
```
struct /*VFT*/ ApplyItemBinding_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptServerContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptServerContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor **, const std::string *);
};

```

### `ApplyLegacyEntityBinding`
```
struct __cppobj ApplyLegacyEntityBinding : ScriptTemplateFactory<ScriptServerContext>::Entity
{
};

```

### `ApplyLegacyEntityBinding_vtbl`
```
struct /*VFT*/ ApplyLegacyEntityBinding_vtbl
{
  void (__fastcall *~Entity)(ScriptTemplateFactory<ScriptServerContext>::Entity *this);
  bool (__fastcall *createAndApplyTemplate)(ScriptTemplateFactory<ScriptServerContext>::Entity *this, const ScriptApi::ScriptVersionInfo *, ScriptEngine *, ScriptServerContext *, Actor **, const std::string *);
};

```

### `AllowListFile`
```
struct __cppobj AllowListFile
{
  const Core::PathBuffer<std::string > mFilePath;
  std::unique_ptr<AllowList> mAllowList;
};

```

### `AllowListFile::<lambda_7ea1983481e1d3d33b61c49f14858a9b>`
```
struct __cppobj AllowListFile::<lambda_7ea1983481e1d3d33b61c49f14858a9b>
{
  AllowListFile *const __this;
};

```

### `ActorTargetFilter`
```
struct __cppobj ActorTargetFilter
{
  ActorTargetFilter::ConditionType mType;
  std::string mKey;
  std::vector<HashedString> mConditions;
  std::vector<ActorTargetFilter> mChildrenConditions;
};

```

### `AzureFileDownloader`
```
struct __cppobj __declspec(align(8)) AzureFileDownloader : FileDownloadManager
{
  Core::PathBuffer<std::string > mDownloadPath;
  std::atomic<bool> mWaitingOnDownload;
};

```

### `AzureFileDownloader_vtbl`
```
struct /*VFT*/ AzureFileDownloader_vtbl
{
  void (__fastcall *~FileDownloadManager)(FileDownloadManager *this);
  void (__fastcall *update)(FileDownloadManager *this);
  void (__fastcall *cancelDownload)(FileDownloadManager *this);
  float (__fastcall *getDownloadProgress)(FileDownloadManager *this);
};

```

### `AzureFileDownloader::downloadSingleFile::__l2::<lambda_40fcf0241377a444d01b8586ed3627c8>::()::__l5::<lambda_c2af21530b352ed75f48d274cdc13a22>`
```
struct __cppobj AzureFileDownloader::downloadSingleFile::__l2::<lambda_40fcf0241377a444d01b8586ed3627c8>::()::__l5::<lambda_c2af21530b352ed75f48d274cdc13a22>
{
  std::weak_ptr<AzureFileDownloader> weakThis;
  const Core::Path filePath;
};

```

### `AzureFileDownloader::downloadSingleFile::__l2::<lambda_40fcf0241377a444d01b8586ed3627c8>::()::__l5::<lambda_18f7f541bb15c23f573d4a5ca4958b2a>`
```
struct __cppobj __declspec(align(8)) AzureFileDownloader::downloadSingleFile::__l2::<lambda_40fcf0241377a444d01b8586ed3627c8>::()::__l5::<lambda_18f7f541bb15c23f573d4a5ca4958b2a>
{
  std::function<void __cdecl(enum DownloaderResult)> onDownloadCompletecallback;
  _BYTE result[4];
};

```

### `AttackDamageMobEffect`
```
struct __cppobj AttackDamageMobEffect : MobEffect
{
};

```

### `AttackDamageMobEffect_vtbl`
```
struct /*VFT*/ AttackDamageMobEffect_vtbl
{
  void (__fastcall *~MobEffect)(MobEffect *this);
  void (__fastcall *applyEffects)(MobEffect *this, Actor *, int, int);
  void (__fastcall *removeEffects)(MobEffect *this, Actor *);
  void (__fastcall *applyInstantaneousEffect)(MobEffect *this, Actor *, Actor *, Actor *, int, float, const MobEffectInstance *, bool);
  bool (__fastcall *isInstantaneous)(MobEffect *this);
  float (__fastcall *getAttributeModifierValue)(MobEffect *this, int, const AttributeModifier *);
};

```

### `ActorFlagComponent<PersistentFlag>`
```
struct __cppobj ActorFlagComponent<PersistentFlag> : IEntityComponent
{
};

```

### `AmbientSoundIntervalDefinition`
```
struct __cppobj AmbientSoundIntervalDefinition
{
  float mValue;
  float mRange;
  std::string mEventName;
};

```

### `ActorLegacySaveConverter`
```
struct __cppobj ActorLegacySaveConverter
{
};

```

### `ActorDamageByBlockSource`
```
struct __cppobj ActorDamageByBlockSource : ActorDamageSource
{
  const Block *mBlock;
};

```

### `ActorDamageByBlockSource_vtbl`
```
struct /*VFT*/ ActorDamageByBlockSource_vtbl
{
  void (__fastcall *~ActorDamageSource)(ActorDamageSource *this);
  bool (__fastcall *isEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isChildEntitySource)(ActorDamageSource *this);
  bool (__fastcall *isBlockSource)(ActorDamageSource *this);
  bool (__fastcall *isFire)(ActorDamageSource *this);
  std::pair<std::string,std::vector<std::string> > *(__fastcall *getDeathMessage)(ActorDamageSource *this, std::pair<std::string,std::vector<std::string> > *result, std::string, Actor *);
  bool (__fastcall *getIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getEntityCategories)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsCreative)(ActorDamageSource *this);
  bool (__fastcall *getDamagingEntityIsWorldBuilder)(ActorDamageSource *this);
  ActorUniqueID *(__fastcall *getDamagingEntityUniqueID)(ActorDamageSource *this, ActorUniqueID *result);
  ActorType (__fastcall *getDamagingEntityType)(ActorDamageSource *this);
  ActorCategory (__fastcall *getDamagingEntityCategories)(ActorDamageSource *this);
  std::unique_ptr<ActorDamageSource> *(__fastcall *clone)(ActorDamageSource *this, std::unique_ptr<ActorDamageSource> *result);
};

```

### `Actor::getInteraction::__l32::<lambda_4350b96e52027121de95bbc7f7bc2df4>`
```
struct __cppobj Actor::getInteraction::__l32::<lambda_4350b96e52027121de95bbc7f7bc2df4>
{
  Actor *const __this;
  Player *pPlayer;
};

```

### `Actor::getInteraction::__l14::<lambda_427a274257fbe116cdaa8945b4460e48>`
```
struct __cppobj __declspec(align(8)) Actor::getInteraction::__l14::<lambda_427a274257fbe116cdaa8945b4460e48>
{
  Actor *const __this;
  Player *player;
  _BYTE newColor[1];
};

```

### `Actor::drop::__l19::<lambda_987acaa92e913f4065378ef6c3770069>`
```
struct __cppobj Actor::drop::__l19::<lambda_987acaa92e913f4065378ef6c3770069>
{
  Actor *const __this;
  ItemActor **thrownItem;
};

```

### `Actor::onEffectRemoved::__l8::<lambda_4b37d6b08e2f81fb8ca4f0938a1034c6>`
```
struct __cppobj Actor::onEffectRemoved::__l8::<lambda_4b37d6b08e2f81fb8ca4f0938a1034c6>
{
  Actor *const __this;
  MobEffectInstance *effect;
};

```

### `Actor::addEffect::__l22::<lambda_6859e42bd581b5f7ab8f72290d114549>`
```
struct __cppobj Actor::addEffect::__l22::<lambda_6859e42bd581b5f7ab8f72290d114549>
{
  Actor *const __this;
  const MobEffectInstance *effect;
};

```

### `Actor::addEffect::__l17::<lambda_fb2b7c8d8a10522d2a36074e8c7c333c>`
```
struct __cppobj Actor::addEffect::__l17::<lambda_fb2b7c8d8a10522d2a36074e8c7c333c>
{
  Actor *const __this;
  const MobEffectInstance *effect;
};

```

### `Actor::addEffect::__l8::<lambda_65347f4a1ce3db960e5fe80b379e1011>`
```
struct __cppobj Actor::addEffect::__l8::<lambda_65347f4a1ce3db960e5fe80b379e1011>
{
  Actor *const __this;
  const MobEffectInstance *effect;
};

```

### `Actor::_sendDirtyActorData::__l17::<lambda_f6cbf93d662f1805df99ec3da008af20>`
```
struct __cppobj Actor::_sendDirtyActorData::__l17::<lambda_f6cbf93d662f1805df99ec3da008af20>
{
  Actor *const __this;
};

```

### `Actor::changeDimension::__l2::<lambda_c9be473a9190878e3fbe351cea6709e9>`
```
struct __cppobj Actor::changeDimension::__l2::<lambda_c9be473a9190878e3fbe351cea6709e9>
{
};

```

### `Actor::_tryPlantWitherRose::__l8::<lambda_f05216a7f5525831ef038bb6dde0ccf1>`
```
struct __cppobj Actor::_tryPlantWitherRose::__l8::<lambda_f05216a7f5525831ef038bb6dde0ccf1>
{
  Actor *const __this;
  const Block *currentBlock;
  const Vec3 *pos;
  BlockSource *region;
};

```

### `Actor::load::__l96::<lambda_2d7d75af98663462b04c83887f36cfae>`
```
struct __cppobj Actor::load::__l96::<lambda_2d7d75af98663462b04c83887f36cfae>
{
  Actor *const __this;
  std::string *scriptData;
};

```

### `Actor::burn::__l11::<lambda_30d955767ba6d61726cf3ba2000d5289>`
```
struct __cppobj Actor::burn::__l11::<lambda_30d955767ba6d61726cf3ba2000d5289>
{
  Actor *const __this;
  long double *fireTime;
  bool *cancel;
};

```

### `Actor::actuallyHurt::__l26::<lambda_5375b3d3c785e36482c98b4ad07cd203>`
```
struct __cppobj Actor::actuallyHurt::__l26::<lambda_5375b3d3c785e36482c98b4ad07cd203>
{
  Actor **srcEntity;
  Actor *const __this;
  int *dmg;
};

```

### `Actor::actuallyHurt::__l14::<lambda_65d6ea4c52e1b6b2b3dc53db143a66d3>`
```
struct __cppobj Actor::actuallyHurt::__l14::<lambda_65d6ea4c52e1b6b2b3dc53db143a66d3>
{
  const ActorDamageSource *source;
  Actor *const __this;
  int *dmg;
};

```

### `Actor::processSurroundHit::__l5::<lambda_1079367dcbf29c8cfac74ff516853b99>`
```
struct __cppobj Actor::processSurroundHit::__l5::<lambda_1079367dcbf29c8cfac74ff516853b99>
{
  Json::FastWriter *writer;
  Json::Value *root;
};

```

### `Actor::doFireHurt::__l11::<lambda_96533e44d455b40dffcbaea218f398d6>`
```
struct __cppobj Actor::doFireHurt::__l11::<lambda_96533e44d455b40dffcbaea218f398d6>
{
  Actor *const __this;
  long double *fireTime;
  bool *cancel;
};

```

### `Actor::tryTeleportTo::__l21::<lambda_68921e8c67232e90d679313755359e2d>`
```
struct __cppobj Actor::tryTeleportTo::__l21::<lambda_68921e8c67232e90d679313755359e2d>
{
  Actor *const __this;
  Vec3 *newPos;
  int *cause;
};

```

### `Actor::stopRiding::__l16::<lambda_5f9ba30a25e2eb23a4e392a7b18921cf>`
```
struct __cppobj Actor::stopRiding::__l16::<lambda_5f9ba30a25e2eb23a4e392a7b18921cf>
{
  Actor *const __this;
  Actor **ride;
  bool *exitFromRider;
  bool *actorIsBeingDestroyed;
  bool *switchingRides;
};

```

### `Actor::stopRiding::__l11::<lambda_9fe6a315db0b4c75cd6e4e23de9652af>`
```
struct __cppobj Actor::stopRiding::__l11::<lambda_9fe6a315db0b4c75cd6e4e23de9652af>
{
  Actor *const __this;
  Actor **ride;
  bool *exitFromRider;
  bool *actorIsBeingDestroyed;
  bool *switchingRides;
};

```

### `Actor::startRiding::__l47::<lambda_79648afca71f4f0e096ad8366d538be2>`
```
struct __cppobj Actor::startRiding::__l47::<lambda_79648afca71f4f0e096ad8366d538be2>
{
  Actor *const __this;
  Actor *ride;
};

```

### `Actor::startRiding::__l45::<lambda_9f3a4c4dc64b2e781d5092fe12aa93c1>`
```
struct __cppobj Actor::startRiding::__l45::<lambda_9f3a4c4dc64b2e781d5092fe12aa93c1>
{
  Actor *const __this;
  Actor *ride;
};

```

### `Actor::startRiding::__l33::<lambda_285584b1e8ec7ea040be7653ac967ce0>`
```
struct __cppobj Actor::startRiding::__l33::<lambda_285584b1e8ec7ea040be7653ac967ce0>
{
  Actor *const __this;
  Actor *ride;
};

```

### `Actor::startRiding::__l28::<lambda_6b914ff44143d00bcc97c1d6ac9cb58b>`
```
struct __cppobj Actor::startRiding::__l28::<lambda_6b914ff44143d00bcc97c1d6ac9cb58b>
{
  Actor *const __this;
  Actor *ride;
};

```

### `Actor::normalTick::__l8::<lambda_1cff64e533ecb175029fee1c4d1d00bd>`
```
struct __cppobj Actor::normalTick::__l8::<lambda_1cff64e533ecb175029fee1c4d1d00bd>
{
  Actor *const __this;
};

```

### `Actor::remove::__l14::<lambda_9fcefacee3ae91a76f43674b69fc9004>`
```
struct __cppobj Actor::remove::__l14::<lambda_9fcefacee3ae91a76f43674b69fc9004>
{
  Actor *const __this;
};

```

### `Actor::_move::__l88::<lambda_7f8c47037bd0bf05fd031b7f456ee565>`
```
struct __cppobj Actor::_move::__l88::<lambda_7f8c47037bd0bf05fd031b7f456ee565>
{
  IActorMovementProxy *actor;
};

```

### `Automation::AutomationSession::_handleOnConnected::__l2::<lambda_b95a8177cd6def7aa664c6cbfc21a418>`
```
struct __cppobj Automation::AutomationSession::_handleOnConnected::__l2::<lambda_b95a8177cd6def7aa664c6cbfc21a418>
{
  std::string *uri;
};

```

### `Automation::AutomationSession::_handleOnClose::__l2::<lambda_bde5dd5cc4208137e610ca15607c2837>`
```
struct __cppobj __declspec(align(8)) Automation::AutomationSession::_handleOnClose::__l2::<lambda_bde5dd5cc4208137e610ca15607c2837>
{
  const std::string *uri;
  bool wasClosed;
};

```

### `Automation::AutomationSession::connect::__l23::<lambda_a7e982d79905fc39f6bd5f7736f6cca5>`
```
struct __cppobj Automation::AutomationSession::connect::__l23::<lambda_a7e982d79905fc39f6bd5f7736f6cca5>
{
};

```

### `Automation::AutomationSession::connect::__l8::<lambda_f2263a8a68cc1d0f91ff67d859feaa26>`
```
struct __cppobj Automation::AutomationSession::connect::__l8::<lambda_f2263a8a68cc1d0f91ff67d859feaa26>
{
};

```

### `Automation::AutomationClient::isSubscribedtoEvent::__l2::<lambda_17c112cc66679954057d008776f47dac>`
```
struct __cppobj Automation::AutomationClient::isSubscribedtoEvent::__l2::<lambda_17c112cc66679954057d008776f47dac>
{
  const std::string *eventName;
  bool *isSubscribed;
};

```

### `Automation::AutomationClient::isReady::__l2::<lambda_c673059335e879e4bece98fc60ced6d7>`
```
struct __cppobj Automation::AutomationClient::isReady::__l2::<lambda_c673059335e879e4bece98fc60ced6d7>
{
  bool *ready;
};

```

### `Automation::AutomationClient::tick::__l2::<lambda_61ff1fdf9f22420a691447f8538cac74>`
```
struct __cppobj Automation::AutomationClient::tick::__l2::<lambda_61ff1fdf9f22420a691447f8538cac74>
{
  float dt;
};

```

### `Automation::AutomationClient::send::__l4::<lambda_fbb0c5a96d1583ce3597a44983535132>`
```
struct __cppobj Automation::AutomationClient::send::__l4::<lambda_fbb0c5a96d1583ce3597a44983535132>
{
  const Automation::Response *response;
};

```

### `Automation::AutomationClient::send::__l4::<lambda_bcc652eab280dcc75bd79c6ac714854d>`
```
struct __cppobj Automation::AutomationClient::send::__l4::<lambda_bcc652eab280dcc75bd79c6ac714854d>
{
  const Automation::Response *response;
};

```

### `Automation::AutomationClient::getSessionForCommand::__l2::<lambda_ed08210d3402bf1af4de59b8d3310e3d>`
```
struct __cppobj Automation::AutomationClient::getSessionForCommand::__l2::<lambda_ed08210d3402bf1af4de59b8d3310e3d>
{
  const CommandOrigin *origin;
  std::shared_ptr<Automation::AutomationSession> *foundSession;
};

```

### `Automation::AutomationClient::{dtor}::__l2::<lambda_f3e0e93b95674b0a36fcdb8b5d6676c1>`
```
struct __cppobj Automation::AutomationClient::{dtor}::__l2::<lambda_f3e0e93b95674b0a36fcdb8b5d6676c1>
{
};

```

### `Actor::checkBlockCollisions::__l5::<lambda_54972524d080960e328684956f9de832>`
```
struct __cppobj Actor::checkBlockCollisions::__l5::<lambda_54972524d080960e328684956f9de832>
{
};

```

### `ActorHasEquipmentTest`
```
struct __cppobj __declspec(align(8)) ActorHasEquipmentTest : FilterTest
{
  int mEquipmentSlot;
  int mItemID;
  int mItemAux;
};

```

### `ActorHasEquipmentTest_vtbl`
```
struct /*VFT*/ ActorHasEquipmentTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorUndergroundTest`
```
struct __cppobj ActorUndergroundTest : SimpleBoolFilterTest
{
};

```

### `ActorUndergroundTest_vtbl`
```
struct /*VFT*/ ActorUndergroundTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorUnderwaterTest`
```
struct __cppobj ActorUnderwaterTest : SimpleBoolFilterTest
{
};

```

### `ActorUnderwaterTest_vtbl`
```
struct /*VFT*/ ActorUnderwaterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInWaterTest`
```
struct __cppobj ActorInWaterTest : SimpleBoolFilterTest
{
};

```

### `ActorInWaterTest_vtbl`
```
struct /*VFT*/ ActorInWaterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInWaterOrRainTest`
```
struct __cppobj ActorInWaterOrRainTest : SimpleBoolFilterTest
{
};

```

### `ActorInWaterOrRainTest_vtbl`
```
struct /*VFT*/ ActorInWaterOrRainTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorOnGroundTest`
```
struct __cppobj ActorOnGroundTest : SimpleBoolFilterTest
{
};

```

### `ActorOnGroundTest_vtbl`
```
struct /*VFT*/ ActorOnGroundTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInLavaTest`
```
struct __cppobj ActorInLavaTest : SimpleBoolFilterTest
{
};

```

### `ActorInLavaTest_vtbl`
```
struct /*VFT*/ ActorInLavaTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInNetherTest`
```
struct __cppobj ActorInNetherTest : SimpleBoolFilterTest
{
};

```

### `ActorInNetherTest_vtbl`
```
struct /*VFT*/ ActorInNetherTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasContainerOpenTest`
```
struct __cppobj ActorHasContainerOpenTest : SimpleBoolFilterTest
{
};

```

### `ActorHasContainerOpenTest_vtbl`
```
struct /*VFT*/ ActorHasContainerOpenTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInCloudsTest`
```
struct __cppobj ActorInCloudsTest : SimpleBoolFilterTest
{
};

```

### `ActorInCloudsTest_vtbl`
```
struct /*VFT*/ ActorInCloudsTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorOnLadderTest`
```
struct __cppobj ActorOnLadderTest : SimpleBoolFilterTest
{
};

```

### `ActorOnLadderTest_vtbl`
```
struct /*VFT*/ ActorOnLadderTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasComponentTest_vtbl`
```
struct /*VFT*/ ActorHasComponentTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsFamilyTest_vtbl`
```
struct /*VFT*/ ActorIsFamilyTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasAbilityTest_vtbl`
```
struct /*VFT*/ ActorHasAbilityTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasDamageTest_vtbl`
```
struct /*VFT*/ ActorHasDamageTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsColorTest_vtbl`
```
struct /*VFT*/ ActorIsColorTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsOwnerTest_vtbl`
```
struct /*VFT*/ ActorIsOwnerTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsTargetTest_vtbl`
```
struct /*VFT*/ ActorIsTargetTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasTargetTest_vtbl`
```
struct /*VFT*/ ActorHasTargetTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasRangedWeaponTest_vtbl`
```
struct /*VFT*/ ActorHasRangedWeaponTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsImmobileTest_vtbl`
```
struct /*VFT*/ ActorIsImmobileTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsLeashedToTest_vtbl`
```
struct /*VFT*/ ActorIsLeashedToTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsMovingTest_vtbl`
```
struct /*VFT*/ ActorIsMovingTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsSneakingTest_vtbl`
```
struct /*VFT*/ ActorIsSneakingTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsClimbingTest_vtbl`
```
struct /*VFT*/ ActorIsClimbingTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsRidingTest_vtbl`
```
struct /*VFT*/ ActorIsRidingTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorRiderCountTest_vtbl`
```
struct /*VFT*/ ActorRiderCountTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInCaravanTest_vtbl`
```
struct /*VFT*/ ActorInCaravanTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsLeashedTest_vtbl`
```
struct /*VFT*/ ActorIsLeashedTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsVariantTest_vtbl`
```
struct /*VFT*/ ActorIsVariantTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsMarkVariantTest_vtbl`
```
struct /*VFT*/ ActorIsMarkVariantTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsSkinIDTest_vtbl`
```
struct /*VFT*/ ActorIsSkinIDTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasTagTest_vtbl`
```
struct /*VFT*/ ActorHasTagTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsAvoidingMobsTest_vtbl`
```
struct /*VFT*/ ActorIsAvoidingMobsTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInVillageTest_vtbl`
```
struct /*VFT*/ ActorInVillageTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsVisibleTest_vtbl`
```
struct /*VFT*/ ActorIsVisibleTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorTrustsSubjectTest_vtbl`
```
struct /*VFT*/ ActorTrustsSubjectTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorHasMobEffect_vtbl`
```
struct /*VFT*/ ActorHasMobEffect_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsSleepingTest_vtbl`
```
struct /*VFT*/ ActorIsSleepingTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInWeatherTest`
```
struct __cppobj __declspec(align(8)) ActorInWeatherTest : FilterTest
{
  ActorInWeatherTest::WeatherType mWeather;
};

```

### `ActorInWeatherTest_vtbl`
```
struct /*VFT*/ ActorInWeatherTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorInactivityTimerTest`
```
struct __cppobj ActorInactivityTimerTest : SimpleIntFilterTest
{
};

```

### `ActorInactivityTimerTest_vtbl`
```
struct /*VFT*/ ActorInactivityTimerTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorRandomChanceTest`
```
struct __cppobj ActorRandomChanceTest : SimpleIntFilterTest
{
};

```

### `ActorRandomChanceTest_vtbl`
```
struct /*VFT*/ ActorRandomChanceTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorSurfaceMobTest`
```
struct __cppobj ActorSurfaceMobTest : SimpleBoolFilterTest
{
};

```

### `ActorSurfaceMobTest_vtbl`
```
struct /*VFT*/ ActorSurfaceMobTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorIsPersistentTest`
```
struct __cppobj ActorIsPersistentTest : SimpleBoolFilterTest
{
};

```

### `ActorIsPersistentTest_vtbl`
```
struct /*VFT*/ ActorIsPersistentTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `ActorGoalDefinition<NearestAttackableTargetDefinition,NearestAttackableTargetGoal>`
```
struct __cppobj __declspec(align(8)) ActorGoalDefinition<NearestAttackableTargetDefinition,NearestAttackableTargetGoal> : DefinitionInstance<EntityContext &,NearestAttackableTargetDefinition,NearestAttackableTargetGoal>
{
  bool mErrorOnAbsentRemove;
};

```

### `ActorGoalDefinition<NearestAttackableTargetDefinition,NearestAttackableTargetGoal>_vtbl`
```
struct /*VFT*/ ActorGoalDefinition<NearestAttackableTargetDefinition,NearestAttackableTargetGoal>_vtbl
{
  void (__fastcall *~IDefinitionInstance)(IDefinitionInstance *this);
  unsigned __int16 (__fastcall *getRuntimeTypeId)(IDefinitionInstance *this);
  void (__fastcall *create)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *initialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *uninitialize)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *destroy)(IDefinitionInstance *this, const ContextAccessor *);
  void (__fastcall *_create)(DefinitionInstance<EntityContext &,NearestAttackableTargetDefinition,NearestAttackableTargetGoal> *this, EntityContext *);
  void (__fastcall *_initialize)(DefinitionInstance<EntityContext &,NearestAttackableTargetDefinition,NearestAttackableTargetGoal> *this, EntityContext *);
  void (__fastcall *_uninitialize)(DefinitionInstance<EntityContext &,NearestAttackableTargetDefinition,NearestAttackableTargetGoal> *this, EntityContext *);
  void (__fastcall *_destroy)(DefinitionInstance<EntityContext &,NearestAttackableTargetDefinition,NearestAttackableTargetGoal> *this, EntityContext *);
};

```

### `ActorFactory::buildSummonEntityTypeEnum::__l2::<lambda_134c3d535d9fb0e25b1786cb945629f4>`
```
struct __cppobj ActorFactory::buildSummonEntityTypeEnum::__l2::<lambda_134c3d535d9fb0e25b1786cb945629f4>
{
  std::vector<std::pair<std::string,ActorDefinitionIdentifier const *>> *results;
};

```

### `ActorFlagComponent<BurnsInDaylightFlag>`
```
struct __cppobj ActorFlagComponent<BurnsInDaylightFlag> : IEntityComponent
{
};

```

### `AgentLookControl`
```
struct __cppobj AgentLookControl : LookControl
{
};

```

### `AgentLookControl_vtbl`
```
struct /*VFT*/ AgentLookControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(LookControl *this, Mob *);
  void (__fastcall *tick)(LookControl *this, Mob *);
};

```

### `AgentCommandExecutionGoal`
```
struct __cppobj AgentCommandExecutionGoal : Goal
{
  Mob *mMob;
};

```

### `AgentCommandExecutionGoal_vtbl`
```
struct /*VFT*/ AgentCommandExecutionGoal_vtbl
{
  void (__fastcall *~Goal)(Goal *this);
  bool (__fastcall *canUse)(Goal *this);
  bool (__fastcall *canContinueToUse)(Goal *this);
  bool (__fastcall *canBeInterrupted)(Goal *this);
  void (__fastcall *start)(Goal *this);
  void (__fastcall *stop)(Goal *this);
  void (__fastcall *tick)(Goal *this);
  void (__fastcall *appendDebugInfo)(Goal *this, std::string *);
  bool (__fastcall *isTargetGoal)(Goal *this);
  void (__fastcall *onPlayerDimensionChanged)(Goal *this, Player *, AutomaticID<Dimension,int>);
};

```

### `AgentBodyControl`
```
struct __cppobj AgentBodyControl : BodyControl
{
};

```

### `AgentBodyControl_vtbl`
```
struct /*VFT*/ AgentBodyControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *clientTick)(BodyControl *this, Mob *);
};

```

### `ActorSpawnRuleGroup::{ctor}::__l2::<lambda_39fbe7a7174c1ef1da6b02000303bca8>`
```
struct __cppobj ActorSpawnRuleGroup::{ctor}::__l2::<lambda_39fbe7a7174c1ef1da6b02000303bca8>
{
  BiomeRegistry *biomeRegistry;
  IWorldRegistriesProvider *registries;
};

```

### `ActorSpawnRuleGroup::{ctor}::__l2::<lambda_39fbe7a7174c1ef1da6b02000303bca8>::()::__l2::<lambda_60d41ca2b8edd9965fc690d489d2db55>`
```
struct __cppobj ActorSpawnRuleGroup::{ctor}::__l2::<lambda_39fbe7a7174c1ef1da6b02000303bca8>::()::__l2::<lambda_60d41ca2b8edd9965fc690d489d2db55>
{
  BiomeRegistry *biomeRegistry;
  BiomeFilterGroup *biomeFilter;
  IWorldRegistriesProvider *registries;
  MobSpawnerData *spawnerData;
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_27234168cfa0d1320611b6327415c402>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_27234168cfa0d1320611b6327415c402>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_9f0f3ac664cea3e1d10231ea53a981e9>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_9f0f3ac664cea3e1d10231ea53a981e9>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l15::<lambda_ae694531796afb0fd242fc25b7f506f1>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l15::<lambda_ae694531796afb0fd242fc25b7f506f1>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l14::<lambda_1875403ab2aa7bcbb14449cd26276284>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l14::<lambda_1875403ab2aa7bcbb14449cd26276284>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l13::<lambda_90728cb354465d19490e35508977f298>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l13::<lambda_90728cb354465d19490e35508977f298>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l12::<lambda_74b7efbca675ad9bf8a5b508a6dcf9ff>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l12::<lambda_74b7efbca675ad9bf8a5b508a6dcf9ff>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_3e6f4ac986b68e92254b9594fe5104b3>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_3e6f4ac986b68e92254b9594fe5104b3>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_393e0199bb1372d5fb300ebb7c4672cf>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_393e0199bb1372d5fb300ebb7c4672cf>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_7050f9d6b006d9e2e374a80f4cc317e7>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_7050f9d6b006d9e2e374a80f4cc317e7>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_0776229c89f377dac713abca45ffdaa9>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l11::<lambda_0776229c89f377dac713abca45ffdaa9>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l10::<lambda_7812cd26f594a9766dc303751fa576c6>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l10::<lambda_7812cd26f594a9766dc303751fa576c6>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_946b57f3d66ef1bacc053d0752d47250>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_946b57f3d66ef1bacc053d0752d47250>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l9::<lambda_bccc1abb5de9c6c95404e8c6869fdf0a>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l9::<lambda_bccc1abb5de9c6c95404e8c6869fdf0a>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_d859e08737e08be15de1a53979a23aba>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_d859e08737e08be15de1a53979a23aba>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_dbbd4b351a17cc4d923e5f19b00c8bf5>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_dbbd4b351a17cc4d923e5f19b00c8bf5>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l8::<lambda_bba0b77306f5e88feea067339677c5ba>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l8::<lambda_bba0b77306f5e88feea067339677c5ba>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l8::<lambda_e2f619e618a9168604b3996e18684320>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l8::<lambda_e2f619e618a9168604b3996e18684320>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l7::<lambda_3dfeef8cadd307ed8d7ff154e0eb15e5>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l7::<lambda_3dfeef8cadd307ed8d7ff154e0eb15e5>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l7::<lambda_8cfba83634c02ff485d10b3390a0da97>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l7::<lambda_8cfba83634c02ff485d10b3390a0da97>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_907ad46b52f4032e1e0f97ba5d8c42ef>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l6::<lambda_907ad46b52f4032e1e0f97ba5d8c42ef>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l5::<lambda_109a42177162ae4d9b379818c8b09439>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l5::<lambda_109a42177162ae4d9b379818c8b09439>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_d6cb09136a9c16d923376463375d7e7e>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l4::<lambda_d6cb09136a9c16d923376463375d7e7e>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l3::<lambda_c01e936b89d63b3acaa96e6613b9bdae>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_10::__l2::<lambda_c71164cef31a93f5de6226c29b3449f3>::()::__l3::<lambda_c01e936b89d63b3acaa96e6613b9bdae>
{
};

```

### `ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_8::__l2::<lambda_c2d0404b5897fd19bafd34874167aee4>`
```
struct __cppobj ActorAnimationControllerGroup::_buildAnimationControllerFileSchema_v1_8::__l2::<lambda_c2d0404b5897fd19bafd34874167aee4>
{
};

```

### `ActorAnimationControllerGroup::loadActorAnimationControllersSync::__l4::<lambda_44e81070060d6cf444adfd9e59e13761>`
```
struct __cppobj ActorAnimationControllerGroup::loadActorAnimationControllersSync::__l4::<lambda_44e81070060d6cf444adfd9e59e13761>
{
  ActorAnimationControllerGroup *const __this;
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *rit;
};

```

### `ActorAnimationControllerGroup::loadActorAnimationControllersAsync::__l2::<lambda_379e87426047a0102f9b049eb17e2d63>`
```
struct __cppobj ActorAnimationControllerGroup::loadActorAnimationControllersAsync::__l2::<lambda_379e87426047a0102f9b049eb17e2d63>
{
  ActorAnimationControllerGroup *const __this;
  ResourcePackManager *resourcePackManager;
};

```

### `ActivateToolNode`
```
struct __cppobj __declspec(align(4)) ActivateToolNode : BehaviorNode
{
  BlockPos mBlockPos;
  const Block *mStartingBlock;
  bool mRightMouseDown;
  int mDelayTicks;
  int mDelayCounter;
  bool mPreActionDone;
};

```

### `ActivateToolNode_vtbl`
```
struct /*VFT*/ ActivateToolNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `ActivateToolDefinition`
```
struct __cppobj ActivateToolDefinition : BehaviorDefinition
{
  BlockPos mBlockPos;
  std::string mBlockPosId;
};

```

### `ActivateToolDefinition_vtbl`
```
struct /*VFT*/ ActivateToolDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `AttackNode`
```
struct __cppobj __declspec(align(8)) AttackNode : BehaviorNode
{
  int mNumTicksToAttack;
  int mNumTicksAttacked;
  bool mPreActionDone;
};

```

### `AttackNode_vtbl`
```
struct /*VFT*/ AttackNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `AttackDefinition`
```
struct __cppobj AttackDefinition : BehaviorDefinition
{
  int mAttackTicks;
  std::string mAttackTicksId;
};

```

### `AttackDefinition_vtbl`
```
struct /*VFT*/ AttackDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `AttackTargetNode`
```
struct __cppobj AttackTargetNode : BehaviorNode
{
};

```

### `AttackTargetNode_vtbl`
```
struct /*VFT*/ AttackTargetNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `ArmorStand::getInteraction::__l48::<lambda_45088cdd3a2c6c32010eb799681f292b>`
```
struct __cppobj __declspec(align(8)) ArmorStand::getInteraction::__l48::<lambda_45088cdd3a2c6c32010eb799681f292b>
{
  Player *player;
  bool playerHasWearableItem;
  ArmorStand *const __this;
  EquipmentSlot heldItemSlot;
  bool playerHasItem;
  EquipmentSlot slotClicked;
};

```

### `ArmorStand::getInteraction::__l14::<lambda_c4d8c48f9e23b7277a2e0a6a67173ea9>`
```
struct __cppobj ArmorStand::getInteraction::__l14::<lambda_c4d8c48f9e23b7277a2e0a6a67173ea9>
{
  Player *player;
  ArmorStand *const __this;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>
{
  bool isPersonaPack;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_ae55eb4313ede5cd6162da7ac336ff42>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_ae55eb4313ede5cd6162da7ac336ff42>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l18::<lambda_e60bc12d016dc5fa5132f3c8a5a3f352>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l18::<lambda_e60bc12d016dc5fa5132f3c8a5a3f352>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l18::<lambda_873331553b1dadac1e59b3f43f9a0c13>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l18::<lambda_873331553b1dadac1e59b3f43f9a0c13>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_9f380b1a6863742835aab457e58d670b>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_9f380b1a6863742835aab457e58d670b>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_d44b967e2a76e7a0b05f01dc1b3e9d26>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_d44b967e2a76e7a0b05f01dc1b3e9d26>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_5f02723e5fe5888bd3c488ee3e7702da>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_5f02723e5fe5888bd3c488ee3e7702da>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_82f76397356e6be6841c8336ffc7e7ea>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l17::<lambda_82f76397356e6be6841c8336ffc7e7ea>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l15::<lambda_cba1b9e805a60d5c400377ce2d93c996>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l15::<lambda_cba1b9e805a60d5c400377ce2d93c996>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l16::<lambda_1be67e5d9e65baab67bdd1f117e99c0c>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l16::<lambda_1be67e5d9e65baab67bdd1f117e99c0c>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l15::<lambda_861ea4f6acc6f38a217809e3cb11509f>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l15::<lambda_861ea4f6acc6f38a217809e3cb11509f>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_be40eeb54437cb8f67c716b7f2307738>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_be40eeb54437cb8f67c716b7f2307738>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_f3f3dd5f9528025fee37e8c1cf2af502>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_f3f3dd5f9528025fee37e8c1cf2af502>
{
  BoneTransformType boneTransformType;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l14::<lambda_4988a3b87d96f770ed35a8aa51e1a059>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l14::<lambda_4988a3b87d96f770ed35a8aa51e1a059>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l12::<lambda_db3ef6efc1017626e618af531e0837ab>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l12::<lambda_db3ef6efc1017626e618af531e0837ab>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l12::<lambda_b0af2c273e75e290bfb68f65b92c78bc>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l12::<lambda_b0af2c273e75e290bfb68f65b92c78bc>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_730ad2fdb9509098c121e4198d2b8a25>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_730ad2fdb9509098c121e4198d2b8a25>
{
  BoneTransformType boneTransformType;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_e97b6743ccaff86b351a6b31dfd47025>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_e97b6743ccaff86b351a6b31dfd47025>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_321c4cbd53501e431f0b931640757ddc>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l8::<lambda_321c4cbd53501e431f0b931640757ddc>
{
  BoneTransformType boneTransformType;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l6::<lambda_19a2dba5010d3771566564b62f97c9dc>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l6::<lambda_19a2dba5010d3771566564b62f97c9dc>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l5::<lambda_b62f9f472c644cc0cee361e28f51f50e>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l5::<lambda_b62f9f472c644cc0cee361e28f51f50e>
{
  bool isPersonaPack;
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_7a61d228c692c8c0fa498ca5cdff41e9>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_7a61d228c692c8c0fa498ca5cdff41e9>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_7fb92e86291256b9c8d318c074b9cd01>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_7fb92e86291256b9c8d318c074b9cd01>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_f0e7256258bc26cd3cef357e56ed2c39>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_f0e7256258bc26cd3cef357e56ed2c39>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_6386d37da9807e0c6c8398682bbbb684>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_6386d37da9807e0c6c8398682bbbb684>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_4c06a057ab93c63e0fc7aaed743a9ab3>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_4c06a057ab93c63e0fc7aaed743a9ab3>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_e70bac23cbb6f55f14c7c370c07e30c5>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_e70bac23cbb6f55f14c7c370c07e30c5>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_524e0568903f119eef2e46fc64ac859b>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_524e0568903f119eef2e46fc64ac859b>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_2e00b30555b1278e9183995a99a86db8>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l4::<lambda_2e00b30555b1278e9183995a99a86db8>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l3::<lambda_be7918f0d53fe7c6831ca4a90156bc04>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l3::<lambda_be7918f0d53fe7c6831ca4a90156bc04>
{
};

```

### `ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l3::<lambda_647dfde46f023b9fd5d1a66e9d0dd0fc>`
```
struct __cppobj ActorAnimationGroup::_buildAnimationFileSchema_v1_8::__l2::<lambda_e922d2f558149c5e333b3cef9f10e8ad>::()::__l3::<lambda_647dfde46f023b9fd5d1a66e9d0dd0fc>
{
};

```

### `ActorAnimationGroup::loadActorAnimationsSync::__l4::<lambda_2e999bf39f1484cb8842d0c936d79580>`
```
struct __cppobj __declspec(align(8)) ActorAnimationGroup::loadActorAnimationsSync::__l4::<lambda_2e999bf39f1484cb8842d0c936d79580>
{
  ActorAnimationGroup *const __this;
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *rit;
  bool isPersonaPack;
};

```

### `ActorAnimationGroup::loadActorAnimationsAsync::__l2::<lambda_74f983507072797d672a2e3cd566fe4e>`
```
struct __cppobj ActorAnimationGroup::loadActorAnimationsAsync::__l2::<lambda_74f983507072797d672a2e3cd566fe4e>
{
  ActorAnimationGroup *const __this;
  ResourcePackManager *resourcePackManager;
};

```

### `AnimationComponent::ensureClientAnimationComponentIsInitialized::__l5::<lambda_24e54a32c4e585e087c1e36b0442ba54>`
```
struct __cppobj AnimationComponent::ensureClientAnimationComponentIsInitialized::__l5::<lambda_24e54a32c4e585e087c1e36b0442ba54>
{
  AnimationComponent *const __this;
  const DataDrivenModel *localModel;
};

```

### `Abilities::<lambda_626723430e05180941b42124d0c52a57>`
```
struct __cppobj Abilities::<lambda_626723430e05180941b42124d0c52a57>
{
};

```

### `Abilities::loadSaveData::__l5::<lambda_63690960c7a54066b8eeedcb8a3c73d4>`
```
struct __cppobj Abilities::loadSaveData::__l5::<lambda_63690960c7a54066b8eeedcb8a3c73d4>
{
  const CompoundTag *tag;
};

```

### `Abilities::addSaveData::__l2::<lambda_679d5926ac440dbb522613fe604efa4d>`
```
struct __cppobj Abilities::addSaveData::__l2::<lambda_679d5926ac440dbb522613fe604efa4d>
{
  std::unique_ptr<CompoundTag> *tag;
};

```

### `AttributeInstance::tick::__l22::<lambda_6d827df9acdfda37ea606dc8f4bbe16b>`
```
struct __cppobj AttributeInstance::tick::__l22::<lambda_6d827df9acdfda37ea606dc8f4bbe16b>
{
  Actor *target;
  int *damage;
  TemporalAttributeBuff *buff;
};

```

### `assignValidForSlotRange::__l2::<lambda_a9361e8e2ae000bf4a28c72c88084f9e>`
```
struct __cppobj assignValidForSlotRange::__l2::<lambda_a9361e8e2ae000bf4a28c72c88084f9e>
{
  int minSlot;
  int maxSlot;
};

```

### `assignValidForSlot::__l2::<lambda_3a2eb4b62752934dceb0d9ea29881bbe>`
```
struct __cppobj assignValidForSlot::__l2::<lambda_3a2eb4b62752934dceb0d9ea29881bbe>
{
  int specificSlot;
};

```

### `ArmorContainerModel`
```
struct __cppobj ArmorContainerModel : ContainerModel
{
  Player *mPlayer;
};

```

### `ArmorContainerModel_vtbl`
```
struct /*VFT*/ ArmorContainerModel_vtbl
{
  void (__fastcall *containerContentChanged)(ContainerContentChangeListener *this, int);
  void (__fastcall *~ContainerContentChangeListener)(ContainerContentChangeListener *this);
  void (__fastcall *containerAddCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *containerRemoveCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *postInit)(ContainerModel *this);
  void (__fastcall *releaseResources)(ContainerModel *this);
  int (__fastcall *getContainerSize)(ContainerModel *this);
  int (__fastcall *getFilteredContainerSize)(ContainerModel *this);
  void (__fastcall *tick)(ContainerModel *this, int);
  ContainerWeakRef *(__fastcall *getContainerWeakRef)(ContainerModel *this, ContainerWeakRef *result);
  const ItemStack *(__fastcall *getItemStack)(ContainerModel *this, int);
  const std::vector<ItemStack> *(__fastcall *getItems)(ContainerModel *this);
  const ItemInstance *(__fastcall *getItemInstance)(ContainerModel *this, int);
  const ItemStackBase *(__fastcall *getItemStackBase)(ContainerModel *this, int);
  bool (__fastcall *isItemInstanceBased)(ContainerModel *this);
  void (__fastcall *setItem)(ContainerModel *this, int, const ItemStack *);
  bool (__fastcall *isValid)(ContainerModel *this);
  bool (__fastcall *isItemFiltered)(ContainerModel *this, const ItemStackBase *);
  bool (__fastcall *isExpanableItemFiltered)(ContainerModel *this, int);
  ContainerExpandStatus (__fastcall *getItemExpandStatus)(ContainerModel *this, int);
  const std::string *(__fastcall *getItemGroupName)(ContainerModel *this, int);
  void (__fastcall *switchItemExpando)(ContainerModel *this, int);
  Container *(__fastcall *_getContainer)(ContainerModel *this);
  int (__fastcall *_getContainerOffset)(ContainerModel *this);
  void (__fastcall *_onItemChanged)(ContainerModel *this, int, const ItemStack *, const ItemStack *);
};

```

### `AbsorptionMobEffect`
```
struct __cppobj AbsorptionMobEffect : MobEffect
{
};

```

### `AbsorptionMobEffect_vtbl`
```
struct /*VFT*/ AbsorptionMobEffect_vtbl
{
  void (__fastcall *~MobEffect)(MobEffect *this);
  void (__fastcall *applyEffects)(MobEffect *this, Actor *, int, int);
  void (__fastcall *removeEffects)(MobEffect *this, Actor *);
  void (__fastcall *applyInstantaneousEffect)(MobEffect *this, Actor *, Actor *, Actor *, int, float, const MobEffectInstance *, bool);
  bool (__fastcall *isInstantaneous)(MobEffect *this);
  float (__fastcall *getAttributeModifierValue)(MobEffect *this, int, const AttributeModifier *);
};

```

### `ActorEventCoordinator::sendActorInteractedWithMob::__l2::<lambda_fcc014254b12400c5742f68f49e6750f>`
```
struct __cppobj ActorEventCoordinator::sendActorInteractedWithMob::__l2::<lambda_fcc014254b12400c5742f68f49e6750f>
{
  Actor *actor;
  MinecraftEventing::InteractionType *interactionType;
  ActorType *interactedActorType;
};

```

### `ActorEventCoordinator::sendActorTeleported::__l2::<lambda_69ca6a24c260330a11fb6b53028073f2>`
```
struct __cppobj ActorEventCoordinator::sendActorTeleported::__l2::<lambda_69ca6a24c260330a11fb6b53028073f2>
{
  Actor *actor;
};

```

### `ActorEventCoordinator::sendActorEquippedArmor::__l2::<lambda_b77e812d805c731e27a2b11ebdafb471>`
```
struct __cppobj __declspec(align(8)) ActorEventCoordinator::sendActorEquippedArmor::__l2::<lambda_b77e812d805c731e27a2b11ebdafb471>
{
  Actor *actor;
  const ItemInstance *armor;
  ArmorSlot slot;
};

```

### `ActorEventCoordinator::sendActorCarriedItemChanged::__l2::<lambda_a05db2b2ddcfc1bfd4875ac2fe740a65>`
```
struct __cppobj __declspec(align(8)) ActorEventCoordinator::sendActorCarriedItemChanged::__l2::<lambda_a05db2b2ddcfc1bfd4875ac2fe740a65>
{
  Actor *actor;
  const ItemInstance *previouslyCarriedItem;
  const ItemInstance *carriedItem;
  HandSlot hand;
};

```

### `ActorEventCoordinator::sendActorTargetAcquired::__l2::<lambda_d920c7ed696a6b3aec4d349e4a2ced7c>`
```
struct __cppobj ActorEventCoordinator::sendActorTargetAcquired::__l2::<lambda_d920c7ed696a6b3aec4d349e4a2ced7c>
{
  Actor *actor;
  Actor *target;
};

```

### `ActorEventCoordinator::sendActorDroppedItem::__l2::<lambda_df1951ff02782776a66ae86c972c3459>`
```
struct __cppobj ActorEventCoordinator::sendActorDroppedItem::__l2::<lambda_df1951ff02782776a66ae86c972c3459>
{
  Actor *actor;
  const ItemInstance *itemDropped;
};

```

### `ActorEventCoordinator::sendActorUseItemOn::__l2::<lambda_0dec4a4ccbd5b3535e18d4debd0dfb89>`
```
struct __cppobj ActorEventCoordinator::sendActorUseItemOn::__l2::<lambda_0dec4a4ccbd5b3535e18d4debd0dfb89>
{
  Actor *actor;
  const ItemStack *itemUsed;
  const BlockPos *blockPos;
  unsigned __int8 *face;
};

```

### `ActorEventCoordinator::sendActorCreated::__l2::<lambda_24926b8afefe4ee502e8f9f7281acdf2>`
```
struct __cppobj ActorEventCoordinator::sendActorCreated::__l2::<lambda_24926b8afefe4ee502e8f9f7281acdf2>
{
  Actor *actor;
};

```

### `ActorEventCoordinator::sendActorRemoved::__l2::<lambda_b83263d581ba691ae13d124ff8aa26a8>`
```
struct __cppobj ActorEventCoordinator::sendActorRemoved::__l2::<lambda_b83263d581ba691ae13d124ff8aa26a8>
{
  Actor *actor;
};

```

### `ActorEventCoordinator::sendActorDeath::__l2::<lambda_381e2bfe1bedc5e6b9b325a1be60774c>`
```
struct __cppobj __declspec(align(8)) ActorEventCoordinator::sendActorDeath::__l2::<lambda_381e2bfe1bedc5e6b9b325a1be60774c>
{
  Actor *actor;
  const ActorDamageSource *source;
  ActorType damageChildType;
};

```

### `ActorEventCoordinator::sendActorStopRiding::__l2::<lambda_36317221bbc9021d13aef750a119c545>`
```
struct __cppobj ActorEventCoordinator::sendActorStopRiding::__l2::<lambda_36317221bbc9021d13aef750a119c545>
{
  Actor *actor;
  bool *exitFromRider;
  bool *actorIsBeingDestroyed;
  bool *switchingRides;
};

```

### `ActorEventCoordinator::sendActorStartRiding::__l2::<lambda_28a545cbbb2abb783b9324ee2808ab93>`
```
struct __cppobj ActorEventCoordinator::sendActorStartRiding::__l2::<lambda_28a545cbbb2abb783b9324ee2808ab93>
{
  Actor *actor;
  Actor *ride;
};

```

### `ActorEventCoordinator::sendActorSneakChanged::__l2::<lambda_3ff337317cabd248fe325d3550e83360>`
```
struct __cppobj ActorEventCoordinator::sendActorSneakChanged::__l2::<lambda_3ff337317cabd248fe325d3550e83360>
{
  Actor *actor;
  bool *isSneaking;
};

```

### `ActorEventCoordinator::sendActorTick::__l2::<lambda_75b7c550f04790ee375b75ae0afc0770>`
```
struct __cppobj ActorEventCoordinator::sendActorTick::__l2::<lambda_75b7c550f04790ee375b75ae0afc0770>
{
  Actor *actor;
};

```

### `ActorEventCoordinator::sendActorPredictedMove::__l2::<lambda_c392fc71d4c65454eae00e1e9fc522dc>`
```
struct __cppobj ActorEventCoordinator::sendActorPredictedMove::__l2::<lambda_c392fc71d4c65454eae00e1e9fc522dc>
{
  Actor *actor;
  MovePredictionType *predictionType;
  const Vec3 *pos;
};

```

### `ActorEventCoordinator::sendActorMove::__l2::<lambda_c10d4be9cad58e7a0afec2bc55878075>`
```
struct __cppobj ActorEventCoordinator::sendActorMove::__l2::<lambda_c10d4be9cad58e7a0afec2bc55878075>
{
  Actor *actor;
  const Vec3 *posIn;
};

```

### `ActorEventCoordinator::sendActorAttack::__l2::<lambda_1536b4b07f770036b9f9033fd3ed68cb>`
```
struct __cppobj __declspec(align(8)) ActorEventCoordinator::sendActorAttack::__l2::<lambda_1536b4b07f770036b9f9033fd3ed68cb>
{
  Actor *actor;
  Actor *target;
  int damage;
};

```

### `ActorEventCoordinator::sendActorHit::__l2::<lambda_97e1347b14b9c4ddde278091b167bdba>`
```
struct __cppobj ActorEventCoordinator::sendActorHit::__l2::<lambda_97e1347b14b9c4ddde278091b167bdba>
{
  Actor *actor;
  std::string *projectileId;
  const ActorDamageSource *source;
  int *damage;
  bool *knock;
  bool *ignite;
};

```

### `ActorEventCoordinator::sendActorHit::__l8::<lambda_b1a534b55a43a76ef765fe0cfcdbc2ed>`
```
struct __cppobj ActorEventCoordinator::sendActorHit::__l8::<lambda_b1a534b55a43a76ef765fe0cfcdbc2ed>
{
  const ActorDamageSource *source;
  Actor *actor;
};

```

### `AuxDataBlockItem`
```
struct __cppobj AuxDataBlockItem : BlockItem
{
  const Block *mParentBlock;
};

```

### `AnvilBlockItem`
```
struct __cppobj AnvilBlockItem : AuxDataBlockItem
{
};

```

### `ArmorBuilder`
```
struct __cppobj ArmorBuilder
{
  int mDurabilityMultiplier;
  std::array<int,4> mProtectionBySlot;
  int mEnchantValue;
  float mKnockBackResistance;
};

```

### `ArmorStandItem`
```
struct __cppobj ArmorStandItem : Item
{
};

```

### `ArrowItem`
```
struct __cppobj __declspec(align(8)) ArrowItem : Item
{
  TextureUVCoordinateSet mArrowIcons[17];
  _BYTE mArrowVariants[68];
};

```

### `AirBlockItem`
```
struct __cppobj AirBlockItem : Item
{
};

```

### `ArbitraryBiomeComponent`
```
struct __cppobj ArbitraryBiomeComponent
{
  std::string mName;
  Json::Value mPayload;
};

```

### `AutomaticFeatureRules::AutomaticFeatureRule`
```
struct __cppobj AutomaticFeatureRules::AutomaticFeatureRule
{
  BiomeDecorationFeature mAutoFeature;
  BiomeFilterGroup mBiomeFilter;
};

```

### `ActivatorRailBlock`
```
struct __cppobj ActivatorRailBlock : BaseRailBlock
{
};

```

### `ActivatorRailBlock_vtbl`
```
struct /*VFT*/ ActivatorRailBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `AirBlock`
```
struct __cppobj AirBlock : BlockLegacy
{
};

```

### `AirBlock_vtbl`
```
struct /*VFT*/ AirBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
};

```

### `AnvilBlock`
```
struct __cppobj AnvilBlock : HeavyBlock
{
};

```

### `AnvilBlock_vtbl`
```
struct /*VFT*/ AnvilBlock_vtbl
{
  void (__fastcall *~BlockLegacy)(BlockLegacy *this);
  const Block *(__fastcall *getStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  const Block *(__fastcall *getModBlockStateFromLegacyData)(BlockLegacy *this, unsigned __int16);
  std::shared_ptr<BlockActor> *(__fastcall *newBlockEntity)(BlockLegacy *this, std::shared_ptr<BlockActor> *result, const BlockPos *, const Block *);
  const Block *(__fastcall *getNextBlockPermutation)(BlockLegacy *this, const Block *);
  bool (__fastcall *hasTag)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *);
  bool (__fastcall *getCollisionShape)(BlockLegacy *this, AABB *, const Block *, BlockSource *, const BlockPos *, Actor *);
  bool (__fastcall *isObstructingChests)(BlockLegacy *this, BlockSource *, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockLegacy *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *addAABBs)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *);
  const AABB *(__fastcall *getAABB)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, AABB *, bool);
  bool (__fastcall *addCollisionShapes)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, const AABB *, std::vector<AABB> *, Actor *);
  const AABB *(__fastcall *getOutline)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  bool (__fastcall *getLiquidClipVolume)(BlockLegacy *this, BlockSource *, const BlockPos *, AABB *);
  void (__fastcall *onProjectileHit)(BlockLegacy *this, BlockSource *, const BlockPos *, const Actor *);
  bool (__fastcall *liquidCanFlowIntoFromDirection)(BlockLegacy *this, unsigned __int8, const std::function<Block const & __cdecl(BlockPos const &)> *, const BlockPos *);
  bool (__fastcall *hasVariableLighting)(BlockLegacy *this);
  bool (__fastcall *isStrippable)(BlockLegacy *this, const Block *);
  const Block *(__fastcall *getStrippedBlock)(BlockLegacy *this, const Block *);
  bool (__fastcall *canProvideSupport)(BlockLegacy *this, const Block *, unsigned __int8, BlockSupportType);
  bool (__fastcall *canConnect)(BlockLegacy *this, const Block *, unsigned __int8, const Block *);
  void (__fastcall *getConnectedDirections)(BlockLegacy *this, const Block *, const BlockPos *, BlockSource *, bool *, bool *, bool *, bool *);
  bool (__fastcall *isStemBlock)(BlockLegacy *this);
  bool (__fastcall *isContainerBlock)(BlockLegacy *this);
  bool (__fastcall *isCraftingBlock)(BlockLegacy *this);
  bool (__fastcall *isWaterBlocking)(BlockLegacy *this);
  bool (__fastcall *isHurtableBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isFenceGateBlock)(BlockLegacy *this);
  bool (__fastcall *isThinFenceBlock)(BlockLegacy *this);
  bool (__fastcall *isWallBlock)(BlockLegacy *this);
  bool (__fastcall *isStairBlock)(BlockLegacy *this);
  bool (__fastcall *isSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoubleSlabBlock)(BlockLegacy *this);
  bool (__fastcall *isDoorBlock)(BlockLegacy *this);
  bool (__fastcall *isRailBlock)(BlockLegacy *this);
  bool (__fastcall *isButtonBlock)(BlockLegacy *this);
  bool (__fastcall *canHurtAndBreakItem)(BlockLegacy *this);
  bool (__fastcall *isSignalSource)(BlockLegacy *this);
  bool (__fastcall *canBeOriginalSurface)(BlockLegacy *this);
  bool (__fastcall *isValidAuxValue)(BlockLegacy *this, int);
  void (__fastcall *setTargetLandBlocks)(BlockLegacy *this, const std::vector<std::string> *);
  bool (__fastcall *canFillAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *sanitizeFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *onFillBlock)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getDirectSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *waterSpreadCausesSpawn)(BlockLegacy *this);
  bool (__fastcall *canContainLiquid)(BlockLegacy *this);
  bool (__fastcall *shouldConnectToRedstone)(BlockLegacy *this, BlockSource *, const BlockPos *, int);
  void (__fastcall *handleRain)(BlockLegacy *this, BlockSource *, const BlockPos *, float);
  bool (__fastcall *canBeUsedInCommands)(BlockLegacy *this, const BaseGameVersion *);
  float (__fastcall *getThickness)(BlockLegacy *this);
  float (__fastcall *getFlexibility)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *checkIsPathable)(BlockLegacy *this, Actor *, const BlockPos *, const BlockPos *);
  bool (__fastcall *shouldDispense)(BlockLegacy *this, BlockSource *, Container *);
  bool (__fastcall *dispense)(BlockLegacy *this, BlockSource *, Container *, int, const Vec3 *, unsigned __int8);
  void (__fastcall *transformOnFall)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *onRedstoneUpdate)(BlockLegacy *this, BlockSource *, const BlockPos *, int, bool);
  void (__fastcall *onMove)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *detachesOnPistonMove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *movedByPiston)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onStructureNeighborBlockPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *setupRedstoneComponent)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *specialUse)(BlockLegacy *this, Player *, const BlockPos *, ItemStack *);
  BlockProperty (__fastcall *getRedstoneProperty)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *updateEntityAfterFallOn)(BlockLegacy *this, IActorMovementProxy *);
  bool (__fastcall *isBounceBlock)(BlockLegacy *this);
  bool (__fastcall *ignoreEntitiesOnPistonMove)(BlockLegacy *this, const Block *);
  bool (__fastcall *onFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, FertilizerType);
  bool (__fastcall *mayConsumeFertilizer)(BlockLegacy *this, BlockSource *);
  bool (__fastcall *canBeFertilized)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *mayPick)(BlockLegacy *this, BlockSource *, const Block *, bool);
  bool (__fastcall *mayPick)(BlockLegacy *this);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *mayPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, unsigned __int8);
  bool (__fastcall *mayPlaceOn)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *tryToPlace)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const ActorBlockSyncMessage *);
  bool (__fastcall *breaksFallingBlocks)(BlockLegacy *this, const Block *);
  void (__fastcall *destroy)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, Actor *);
  bool (__fastcall *playerWillDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  bool (__fastcall *getIgnoresDestroyPermissions)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *neighborChanged)(BlockLegacy *this, BlockSource *, const BlockPos *, const BlockPos *);
  bool (__fastcall *getSecondPart)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  int (__fastcall *getResourceCount)(BlockLegacy *this, Random *, const Block *, int, bool);
  ItemInstance *(__fastcall *getResourceItem)(BlockLegacy *this, ItemInstance *result, Random *, const Block *, int);
  ItemInstance *(__fastcall *asItemInstance)(BlockLegacy *this, ItemInstance *result, BlockSource *, const BlockPos *, const Block *);
  void (__fastcall *spawnResources)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  void (__fastcall *trySpawnResourcesOnExplosion)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, std::vector<Item const *> *, float, int, bool);
  bool (__fastcall *spawnBurnResources)(BlockLegacy *this, BlockSource *, float, float, float);
  const Block *(__fastcall *getPlacementBlock)(BlockLegacy *this, Actor *, const BlockPos *, unsigned __int8, const Vec3 *, int);
  int (__fastcall *calcVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isAttachedTo)(BlockLegacy *this, BlockSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *attack)(BlockLegacy *this, Player *, const BlockPos *);
  void (__fastcall *handleEntityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, Vec3 *);
  void (__fastcall *entityInside)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  int (__fastcall *getExperienceDrop)(BlockLegacy *this, Random *);
  bool (__fastcall *canBeBuiltOver)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *triggerEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, int, int);
  void (__fastcall *executeEvent)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, const std::string *, Actor *);
  void (__fastcall *executeEvent)(BlockLegacy *this, const std::string *, RenderParams *);
  bool (__fastcall *executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  bool (__fastcall *executeTriggerChain)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, RenderParams *);
  const MobSpawnerData *(__fastcall *getMobToSpawn)(BlockLegacy *this, const SpawnConditions *, BlockSource *);
  bool (__fastcall *shouldStopFalling)(BlockLegacy *this, Actor *);
  bool (__fastcall *pushesUpFallingBlocks)(BlockLegacy *this);
  float (__fastcall *calcGroundFriction)(BlockLegacy *this, Mob *, const BlockPos *);
  bool (__fastcall *canHaveExtraData)(BlockLegacy *this);
  bool (__fastcall *hasComparatorSignal)(BlockLegacy *this);
  int (__fastcall *getComparatorSignal)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *, unsigned __int8);
  bool (__fastcall *onDig)(BlockLegacy *this, const Block *, Actor *, ItemStack *, const BlockPos *);
  bool (__fastcall *canSlide)(BlockLegacy *this, BlockSource *, const BlockPos *);
  bool (__fastcall *canSpawnAt)(BlockLegacy *this, const BlockSource *, const BlockPos *);
  void (__fastcall *notifySpawnedAt)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getIconYOffset)(BlockLegacy *this);
  std::string *(__fastcall *buildDescriptionId)(BlockLegacy *this, std::string *result, const Block *);
  bool (__fastcall *isAuxValueRelevantForPicking)(BlockLegacy *this);
  int (__fastcall *getColor)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  int (__fastcall *getColor)(BlockLegacy *this, const Block *);
  int (__fastcall *getColorAtPos)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColorForParticle)(BlockLegacy *this, BlockSource *, const BlockPos *, const Block *);
  bool (__fastcall *isSeasonTinted)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockLegacy *this, const BlockGraphicsModeChangeContext *);
  float (__fastcall *getShadeBrightness)(BlockLegacy *this, const Block *);
  const AABB *(__fastcall *getVisualShapeInWorld)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockLegacy *this, const Block *, AABB *, bool);
  const AABB *(__fastcall *getUIShape)(BlockLegacy *this, const Block *, AABB *);
  int (__fastcall *telemetryVariant)(BlockLegacy *this, BlockSource *, const BlockPos *);
  int (__fastcall *getVariant)(BlockLegacy *this, const Block *);
  bool (__fastcall *canSpawnOn)(BlockLegacy *this);
  const Block *(__fastcall *getRenderBlock)(BlockLegacy *this);
  unsigned __int8 (__fastcall *getMappedFace)(BlockLegacy *this, unsigned __int8, const Block *);
  bool (__fastcall *renderTwoFaced)(BlockLegacy *this);
  Flip (__fastcall *getFaceFlip)(BlockLegacy *this, unsigned __int8, const Block *);
  void (__fastcall *animateTick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  BlockLegacy *(__fastcall *init)(BlockLegacy *this);
  BlockLegacy *(__fastcall *setLightBlock)(BlockLegacy *this, Brightness);
  BlockLegacy *(__fastcall *setLightEmission)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setExplodeable)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFlammable)(BlockLegacy *this, FlameOdds, BurnOdds);
  BlockLegacy *(__fastcall *setDestroyTime)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *setFriction)(BlockLegacy *this, float);
  BlockLegacy *(__fastcall *addProperty)(BlockLegacy *this, BlockProperty);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *, unsigned __int64);
  BlockLegacy *(__fastcall *addState)(BlockLegacy *this, const ItemState *);
  BlockLegacy *(__fastcall *setAllowsRunes)(BlockLegacy *this, bool);
  BlockLegacy *(__fastcall *setMapColor)(BlockLegacy *this, const mce::Color *);
  bool (__fastcall *canBeSilkTouched)(BlockLegacy *this);
  ItemInstance *(__fastcall *getSilkTouchItemInstance)(BlockLegacy *this, ItemInstance *result, const Block *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockLegacy *this, const AABB *);
  const Block *(__fastcall *tryLegacyUpgrade)(BlockLegacy *this, unsigned __int16);
  bool (__fastcall *dealsContactDamage)(BlockLegacy *this, const Actor *, const Block *, bool);
  void (__fastcall *onRemove)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onExploded)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *);
  void (__fastcall *onStandOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOn)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onStepOff)(BlockLegacy *this, Actor *, const BlockPos *);
  void (__fastcall *onPlayerPlacing)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, unsigned __int8);
  void (__fastcall *onPlace)(BlockLegacy *this, BlockSource *, const BlockPos *);
  void (__fastcall *onFallOn)(BlockLegacy *this, BlockSource *, const BlockPos *, Actor *, float);
  void (__fastcall *playerDestroy)(BlockLegacy *this, Player *, const BlockPos *, const Block *);
  void (__fastcall *tick)(BlockLegacy *this, BlockSource *, const BlockPos *, Random *);
  bool (__fastcall *shouldRandomTick)(BlockLegacy *this);
  bool (__fastcall *isInteractiveBlock)(BlockLegacy *this);
  HitResult *(__fastcall *clip)(BlockLegacy *this, HitResult *result, BlockSource *, const BlockPos *, const Vec3 *, const Vec3 *, bool);
  bool (__fastcall *use)(BlockLegacy *this, Player *, const BlockPos *, unsigned __int8);
  bool (__fastcall *canSurvive)(BlockLegacy *this, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this, const Block *, BlockSource *, const BlockPos *);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockLegacy *this);
  int (__fastcall *getExtraRenderLayers)(BlockLegacy *this);
  float (__fastcall *getExplosionResistance)(BlockLegacy *this, Actor *);
  Brightness *(__fastcall *getLightEmission)(BlockLegacy *this, Brightness *result, const Block *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result, BlockSource *, const BlockPos *);
  mce::Color *(__fastcall *getMapColor)(BlockLegacy *this, mce::Color *result);
  bool (__fastcall *isCropBlock)(BlockLegacy *this);
  void (__fastcall *_executeEvent)(BlockLegacy *this, const std::string *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  bool (__fastcall *_executeTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  void (__fastcall *_forceExecuteTrigger)(BlockLegacy *this, const DefinitionTrigger *, std::vector<std::pair<std::string const ,std::string const >> *, RenderParams *);
  mce::Color *(__fastcall *getDustColor)(HeavyBlock *this, mce::Color *result, const Block *);
  std::string *(__fastcall *getDustParticleName)(HeavyBlock *this, std::string *result, const Block *);
  bool (__fastcall *falling)(HeavyBlock *this);
  void (__fastcall *onLand)(HeavyBlock *this, BlockSource *, const BlockPos *);
  bool (__fastcall *isFreeToFall)(HeavyBlock *this, BlockSource *, const BlockPos *);
  void (__fastcall *startFalling)(HeavyBlock *this, BlockSource *, const BlockPos *, const Block *, bool);
};

```

### `AABBComponentDescription`
```
struct __cppobj AABBComponentDescription : BlockComponentDescription
{
  std::vector<AABBComponentNode> mClipAABB;
  std::vector<AABBComponentNode> mCollisionAABB;
};

```

### `AABBComponentDescription_vtbl`
```
struct /*VFT*/ AABBComponentDescription_vtbl
{
  void (__fastcall *~BlockComponentDescription)(BlockComponentDescription *this);
  const std::string *(__fastcall *getName)(BlockComponentDescription *this);
  void (__fastcall *initializeComponent)(BlockComponentDescription *this, EntityContext *);
  void (__fastcall *buildSchema)(BlockComponentDescription *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,BlockComponentGroupDescription> > *, const BlockComponentFactory *);
  bool (__fastcall *isNetworkComponent)(BlockComponentDescription *this);
  std::unique_ptr<CompoundTag> *(__fastcall *buildNetworkTag)(BlockComponentDescription *this, std::unique_ptr<CompoundTag> *result);
  void (__fastcall *initializeFromNetwork)(BlockComponentDescription *this, const CompoundTag *);
};

```

### `AABBComponent`
```
struct __cppobj AABBComponent
{
  BlockLegacy *mBlockLegacy;
  std::vector<AABBComponentNode> mClipAABB;
  std::vector<AABBComponentNode> mCollisionAABB;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,2>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,2>
{
  std::_Align_type<double,8> mArray[2];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `ActorHelper`
```
struct __cppobj ActorHelper
{
};

```

### `AppendOnlyAtomicLookupTable<Block const *,4>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,4>
{
  std::_Align_type<double,8> mArray[4];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,8>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,8>
{
  std::_Align_type<double,8> mArray[8];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,16>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,16>
{
  std::_Align_type<double,8> mArray[16];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,32>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,32>
{
  std::_Align_type<double,8> mArray[32];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,64>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,64>
{
  std::_Align_type<double,8> mArray[64];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,256>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,256>
{
  std::_Align_type<double,8> mArray[256];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AppendOnlyAtomicLookupTable<Block const *,4096>`
```
struct __cppobj AppendOnlyAtomicLookupTable<Block const *,4096>
{
  std::_Align_type<double,8> mArray[4096];
  std::atomic<unsigned __int64> mSize;
  SpinLock mAppendLock;
};

```

### `AggregateFeature<0>`
```
struct __cppobj __declspec(align(8)) AggregateFeature<0> : IFeature
{
  std::vector<WeakRefT<FeatureRefTraits>> mFeatureReferences;
  _BYTE mEarlyOut[4];
};

```

### `AggregateFeature<0>_vtbl`
```
struct /*VFT*/ AggregateFeature<0>_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `AggregateFeature<1>`
```
struct __cppobj __declspec(align(8)) AggregateFeature<1> : IFeature
{
  std::vector<WeakRefT<FeatureRefTraits>> mFeatureReferences;
  _BYTE mEarlyOut[4];
};

```

### `AggregateFeature<1>_vtbl`
```
struct /*VFT*/ AggregateFeature<1>_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `AggregateFeature<0>::_buildSchema::__l6::<lambda_dfdc3da12b7273c86a0eceae8e35d7c2>`
```
struct __cppobj AggregateFeature<0>::_buildSchema::__l6::<lambda_dfdc3da12b7273c86a0eceae8e35d7c2>
{
};

```

### `AggregateFeature<0>::_buildSchema::__l3::<lambda_278064a9384a7a37798efb9f96a62519>`
```
struct __cppobj AggregateFeature<0>::_buildSchema::__l3::<lambda_278064a9384a7a37798efb9f96a62519>
{
};

```

### `AggregateFeature<0>::_buildSchema::__l3::<lambda_839c8aa6352f76d6780c54eeacdafeb4>`
```
struct __cppobj AggregateFeature<0>::_buildSchema::__l3::<lambda_839c8aa6352f76d6780c54eeacdafeb4>
{
};

```

### `AggregateFeature<1>::_buildSchema::__l3::<lambda_0c4bef079f43e68fa5617e8d2581a3a3>`
```
struct __cppobj AggregateFeature<1>::_buildSchema::__l3::<lambda_0c4bef079f43e68fa5617e8d2581a3a3>
{
};

```

### `AggregateFeature<1>::_buildSchema::__l3::<lambda_17509494e3a5018c20bf04448011eb41>`
```
struct __cppobj AggregateFeature<1>::_buildSchema::__l3::<lambda_17509494e3a5018c20bf04448011eb41>
{
};

```

### `AutomaticFeatureRules::attachAutomaticFeatures::__l2::<lambda_1bbeebc3b2e0c6ad7c1df8debab5585e>`
```
struct __cppobj AutomaticFeatureRules::attachAutomaticFeatures::__l2::<lambda_1bbeebc3b2e0c6ad7c1df8debab5585e>
{
  const TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > *tagRegistry;
};

```

### `AutomaticFeatureRules::parseAutomaticFeatures::__l2::<lambda_4ee1bba471f06e68a1ecc2550e0a49cb>`
```
struct __cppobj AutomaticFeatureRules::parseAutomaticFeatures::__l2::<lambda_4ee1bba471f06e68a1ecc2550e0a49cb>
{
  IWorldRegistriesProvider *worldRegistries;
  std::vector<AutomaticFeatureRules::AutomaticFeatureRule> (*bucketedFeatures)[7];
  const std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,std::tuple<std::reference_wrapper<enum AutomaticFeatureRules::PriorityBucket>,std::reference_wrapper<AutomaticFeatureRules::AutomaticFeatureRule>,std::reference_wrapper<IWorldRegistriesProvider> > > > *schema;
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>
{
  const SemVersion *formatVersion;
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l3::<lambda_f85e3c1ac9acdc7ef92b1aa54a1d1a4f>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l3::<lambda_f85e3c1ac9acdc7ef92b1aa54a1d1a4f>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l3::<lambda_2737b7edce4d7e00b7cef73e4cdc9793>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l3::<lambda_2737b7edce4d7e00b7cef73e4cdc9793>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_2d276f174abaf67f58dd35c3c682d761>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_2d276f174abaf67f58dd35c3c682d761>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_1b9f459c75dbed0c2821a2f8e076d99c>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_1b9f459c75dbed0c2821a2f8e076d99c>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_86c34efbb0d8781e97a9430ca91cd3f7>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l5::<lambda_86c34efbb0d8781e97a9430ca91cd3f7>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_40db15e3b36970ad793e6322957e5950>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_40db15e3b36970ad793e6322957e5950>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_837a129d183ac85114be5dba6e72d8f3>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_837a129d183ac85114be5dba6e72d8f3>
{
};

```

### `AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_438362e7871bba6ad67c4b99580fe9d2>`
```
struct __cppobj AutomaticFeatureRules::_buildSchema::__l2::<lambda_c04811c4e7065026e03ba3651c0e408b>::()::__l4::<lambda_438362e7871bba6ad67c4b99580fe9d2>
{
};

```

### `AcaciaTreeCanopy`
```
struct __cppobj AcaciaTreeCanopy : ITreeCanopy
{
  int mCanopySize;
  bool mSimplePattern;
  BlockDescriptor mLeafBlockDescriptor;
};

```

### `AcaciaTreeCanopy_vtbl`
```
struct /*VFT*/ AcaciaTreeCanopy_vtbl
{
  void (__fastcall *~ITreeCanopy)(ITreeCanopy *this);
  std::optional<BlockPos> *(__fastcall *placeCanopy)(ITreeCanopy *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *, const TreeHelper::TreeParams *);
  bool (__fastcall *parseTreeCanopy)(ITreeCanopy *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `AcaciaTreeTrunk`
```
struct __cppobj AcaciaTreeTrunk : ITreeTrunk
{
  int mBaseHeight;
  int mTrunkWidth;
  IntRange mLeanHeight;
  IntRange mLeanSteps;
  bool mAllowDiagonalGrowth;
  IntRange mBranchLength;
  IntRange mBranchPos;
  ChanceInformation mBranchChance;
  BlockDescriptor mTrunkBlockDescriptor;
  ITreeCanopyWrapper mBranchCanopy;
  TreeHelper::AttachableDecoration mDecoration;
  std::vector<int> mHeightIntervals;
};

```

### `AcaciaTreeTrunk_vtbl`
```
struct /*VFT*/ AcaciaTreeTrunk_vtbl
{
  void (__fastcall *~ITreeTrunk)(ITreeTrunk *this);
  std::optional<BlockPos> *(__fastcall *placeTrunk)(ITreeTrunk *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *, const TreeHelper::TreeParams *, const ITreeCanopy *);
  bool (__fastcall *parse)(ITreeTrunk *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `AddOceanTemperatureLayer`
```
struct __cppobj AddOceanTemperatureLayer : RootLayer<enum BiomeTemperatureCategory>
{
};

```

### `AddOceanTemperatureLayer_vtbl`
```
struct /*VFT*/ AddOceanTemperatureLayer_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<enum BiomeTemperatureCategory> *(__fastcall *_allocateAndFill)(Layer<enum BiomeTemperatureCategory> *this, LayerDetails::TransferData<enum BiomeTemperatureCategory> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(RootLayer<enum BiomeTemperatureCategory> *this, LayerDetails::WorkingData<enum BiomeTemperatureCategory,char> *, int, int, int, int);
};

```

### `AppPlatform::onEnterBackground::__l2::<lambda_aa3d6716f2c6f5a342de2a633d269e12>`
```
struct __cppobj AppPlatform::onEnterBackground::__l2::<lambda_aa3d6716f2c6f5a342de2a633d269e12>
{
};

```

### `AppPlatform::runStoragePermissionResultCallback::__l5::<lambda_919435aa1b444aab312ae1198dc2d437>`
```
struct __cppobj __declspec(align(8)) AppPlatform::runStoragePermissionResultCallback::__l5::<lambda_919435aa1b444aab312ae1198dc2d437>
{
  std::function<void __cdecl(enum StoragePermissionResult)> callback;
  StoragePermissionResult result;
};

```

### `AppPlatform::onResumeFromBackground::__l2::<lambda_9fbb645710da4f07e032f88d29456f74>`
```
struct __cppobj AppPlatform::onResumeFromBackground::__l2::<lambda_9fbb645710da4f07e032f88d29456f74>
{
};

```

### `AppPlatform::setReactNativeVisible::__l2::<lambda_44729b74cb4b2e4d21f0af69869b398d>`
```
struct __cppobj __declspec(align(8)) AppPlatform::setReactNativeVisible::__l2::<lambda_44729b74cb4b2e4d21f0af69869b398d>
{
  AppPlatform *const __this;
  bool visible;
};

```

### `AppPlatform::muteOutputWithName::__l2::<lambda_134f005bfabde1f5a2d73c45595fd0a4>`
```
struct __cppobj AppPlatform::muteOutputWithName::__l2::<lambda_134f005bfabde1f5a2d73c45595fd0a4>
{
  std::string str;
};

```

### `AppPlatform::listAssetFilesIn::__l2::<lambda_acef24a08a54f7ddaf68f9dcf6136868>`
```
struct __cppobj AppPlatform::listAssetFilesIn::__l2::<lambda_acef24a08a54f7ddaf68f9dcf6136868>
{
  const std::string *extension;
  std::set<Core::PathBuffer<std::string >> *res;
};

```

### `AppPlatform::muteInput::__l2::<lambda_e03c317a7b712f46f94f40781ff5d7eb>`
```
struct __cppobj AppPlatform::muteInput::__l2::<lambda_e03c317a7b712f46f94f40781ff5d7eb>
{
  std::string str;
};

```

### `AppPlatform::muteOutput::__l2::<lambda_d62705be414232dfd0aa5f27cb25391d>`
```
struct __cppobj AppPlatform::muteOutput::__l2::<lambda_d62705be414232dfd0aa5f27cb25391d>
{
  std::string str;
};

```

### `AppPlatform::_initializeLoadProfiler::__l5::<lambda_4a67df1d1a3f4d5283a59c088020fc0c>`
```
struct __cppobj AppPlatform::_initializeLoadProfiler::__l5::<lambda_4a67df1d1a3f4d5283a59c088020fc0c>
{
};

```

### `AttackTargetDefinition`
```
struct __cppobj AttackTargetDefinition : BehaviorDefinition
{
};

```

### `AttackTargetDefinition_vtbl`
```
struct /*VFT*/ AttackTargetDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `asn1_string_st`
```
struct __declspec(align(8)) asn1_string_st
{
  int length;
  int type;
  unsigned __int8 *data;
  int flags;
};

```

### `asn1_type_st`
```
struct asn1_type_st
{
  int type;
  asn1_type_st::<unnamed_type_value> value;
};

```

### `asn1_string_table_st`
```
struct asn1_string_table_st
{
  int nid;
  int minsize;
  int maxsize;
  unsigned int mask;
  unsigned int flags;
};

```

### `AppPkgUpdateMgr_vtbl`
```
struct /*VFT*/ AppPkgUpdateMgr_vtbl
{
  void (__fastcall *~AppPkgUpdateMgr)(AppPkgUpdateMgr *this);
};

```

### `AppPkgUpdateStage::onAwake::__l2::<lambda_bb35f6356100d334232d94ebdd27f1cd>`
```
struct __cppobj AppPkgUpdateStage::onAwake::__l2::<lambda_bb35f6356100d334232d94ebdd27f1cd>
{
  AppPkgUpdateStage *const __this;
};

```

### `AppPkgUpdateStage::onAwake::__l2::<lambda_b92889fe792a27d09c21180e8cfbfb40>`
```
struct __cppobj AppPkgUpdateStage::onAwake::__l2::<lambda_b92889fe792a27d09c21180e8cfbfb40>
{
  AppPkgUpdateStage *const __this;
};

```

### `AnimationConverter::Animation`
```
struct __cppobj AnimationConverter::Animation
{
  std::string name;
  Json::Value value;
};

```

### `AvoidOwnerFovGoal`
```
struct __cppobj __declspec(align(8)) AvoidOwnerFovGoal : Goal
{
  Mob *mMob;
  int mStayAvoidTime;
  float mAvoidAngle;
  float mAvoidMinDis;
  float mAvoidMaxDis;
  float mAvoidBackAngle;
  float mAvoidBackMinDis;
  float mAvoidBackMaxDis;
  int mStayTicks;
  TempEPtr<Mob> mOwner;
  Vec3 mLastWantedPos;
};

```

### `AvoidOwnerFovGoal_vtbl`
```
struct /*VFT*/ AvoidOwnerFovGoal_vtbl
{
  void (__fastcall *~Goal)(Goal *this);
  bool (__fastcall *canUse)(Goal *this);
  bool (__fastcall *canContinueToUse)(Goal *this);
  bool (__fastcall *canBeInterrupted)(Goal *this);
  void (__fastcall *start)(Goal *this);
  void (__fastcall *stop)(Goal *this);
  void (__fastcall *tick)(Goal *this);
  void (__fastcall *appendDebugInfo)(Goal *this, std::string *);
  bool (__fastcall *isTargetGoal)(Goal *this);
  void (__fastcall *onPlayerDimensionChanged)(Goal *this, Player *, AutomaticID<Dimension,int>);
};

```

### `AvoidOwnerFovDefinition`
```
struct __cppobj __declspec(align(8)) AvoidOwnerFovDefinition : BaseGoalDefinition
{
  int mStayAvoidTime;
  float mAvoidAngle;
  float mAvoidMinDis;
  float mAvoidMaxDis;
  float mAvoidBackAngle;
  float mAvoidBackMinDis;
  float mAvoidBackMaxDis;
};

```

### `AvoidOwnerFovDefinition_vtbl`
```
struct /*VFT*/ AvoidOwnerFovDefinition_vtbl
{
  void (__fastcall *~BaseGoalDefinition)(BaseGoalDefinition *this);
  bool (__fastcall *validateMobType)(BaseGoalDefinition *this, Mob *);
  bool (__fastcall *validate)(BaseGoalDefinition *this, Mob *);
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_b0d7eb646519dd6e0130e6c40e7816cc>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_b0d7eb646519dd6e0130e6c40e7816cc>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_5ae513d9c62a610318f36b939699427c>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_5ae513d9c62a610318f36b939699427c>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_1e6ab9725cd200317cfdbd037c61e8e2>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_1e6ab9725cd200317cfdbd037c61e8e2>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_e582c10449e4e0bb82c0c1bb0b0d5466>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_e582c10449e4e0bb82c0c1bb0b0d5466>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_0d360f5a370690c70e05ce7a30d9e30f>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_0d360f5a370690c70e05ce7a30d9e30f>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_0db27cdcb8175652fe712dcbc73ee3b1>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_0db27cdcb8175652fe712dcbc73ee3b1>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_996361427ebc729ab61533ec363fa5a2>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_996361427ebc729ab61533ec363fa5a2>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_8fc482dee9c02c8ec901704ebfed6297>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_8fc482dee9c02c8ec901704ebfed6297>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_ec908fcd147132fa4c96b9378e4355c3>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_ec908fcd147132fa4c96b9378e4355c3>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_c4e8ed1b07f3d7904d3a821d3e65c2b3>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_c4e8ed1b07f3d7904d3a821d3e65c2b3>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_095a916b2fefeab62402884b112d4c4b>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_095a916b2fefeab62402884b112d4c4b>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_1a1e59d492111f41d24a6f4dfd7592d8>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_1a1e59d492111f41d24a6f4dfd7592d8>
{
};

```

### `AABBComponentDescription::buildSchema::__l2::<lambda_389c08d9cc5cce8132c046360e53bf25>`
```
struct __cppobj AABBComponentDescription::buildSchema::__l2::<lambda_389c08d9cc5cce8132c046360e53bf25>
{
  const BlockComponentFactory *factory;
};

```

### `AnvilContainerManagerModel`
```
struct __cppobj __declspec(align(8)) AnvilContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

