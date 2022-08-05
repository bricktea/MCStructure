# J
### `Json::Value`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value::ValueHolder` | value_
8 | (2) `__int16` | _bf_8


### `Json::Value::ValueHolder`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | int_
1 | (8) `unsigned __int64` | uint_
2 | (8) `long double` | real_
3 | (1) `bool` | bool_
4 | (8) `char *` | string_
5 | (8) `std::map<Json::Value::CZString,Json::Value> *` | map_


### `JWTCrypto`
Offset | Type | Name
-|-|-|-
0 | (4) `Crypto::Asymmetric::System` | mKeyType
8 | (32) `std::string` | mAlgorithm
40 | (4) `Crypto::Hash::HashType` | mHashType
44 | (4) `int` | mSignatureLength


### `JoinCodeIconData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | toolTip
32 | (32) `std::string` | texture


### `Json::Reader`
Offset | Type | Name
-|-|-|-
0 | (40) `std::stack<Json::Value *>` | nodes_
40 | (40) `std::deque<Json::Reader::ErrorInfo>` | errors_
80 | (32) `std::string` | document_
112 | (8) `const char *` | begin_
120 | (8) `const char *` | end_
128 | (8) `const char *` | current_
136 | (8) `const char *` | lastValueEnd_
144 | (8) `Json::Value *` | lastValue_
152 | (32) `std::string` | commentsBefore_
184 | (2) `Json::Features` | features_
186 | (1) `bool` | collectComments_


### `Json::Features`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | allowComments_
1 | (1) `bool` | strictRoot_


### `Json::Value::CZString`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | cstr_
8 | (4) `unsigned int` | index_


### `Json::FastWriter`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Writer` | baseclass_0
8 | (32) `std::string` | document_
40 | (1) `bool` | yamlCompatiblityEnabled_


### `Json::Writer`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Writer_vtbl *` | __vftable


### `JoincodeEntryScreenController::{ctor}::__l2::<lambda_3950b1ac9c64f8a3989189fcb749af71>`
Offset | Type | Name
-|-|-|-
0 | (8) `JoincodeEntryScreenController *const` | __this


### `JoincodeEntryScreenController::_requestJoinServer::__l2::<lambda_ecf16ffa0c4f61ef22be7767f15d5b0a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<JoincodeEntryScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(std::shared_ptr<JoincodeEntryScreenController>,EDUDiscovery::JoinServerQueryState const &)>` | joinCallback


### `JsonValidator::Property`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<enum Json::ValueType>` | mTypes
24 | (1) `bool` | mIsRequired
25 | (1) `bool` | mRequiresConditionalProperty
32 | (32) `std::string` | mDescription
64 | (16) `std::shared_ptr<JsonValidator::Property>` | mChildProperty
80 | (24) `std::vector<std::pair<Json::Value,std::shared_ptr<JsonValidator::Property> >>` | mConditionalPropertiesByValue
104 | (24) `std::vector<std::pair<enum Json::ValueType,std::shared_ptr<JsonValidator::Property> >>` | mConditionalPropertiesByType
128 | (64) `std::unordered_map<std::string,std::shared_ptr<JsonValidator::Property>>` | mPropertyMap


### `Json::ValueIteratorBase`
Offset | Type | Name
-|-|-|-
0 | (8) `std::_Tree_iterator<std::_Tree_val<std::_Tree_simple_types<std::pair<Json::Value::CZString const ,Json::Value> > > >` | current_
8 | (1) `bool` | isNull_


### `Json::StyledStreamWriter`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | childValues_
24 | (8) `std::ostream *` | document_
32 | (32) `std::string` | indentString_
64 | (4) `int` | rightMargin_
72 | (32) `std::string` | indentation_
104 | (1) `bool` | addChildValues_


### `Json::ValueConstIterator`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::ValueIteratorBase` | baseclass_0


### `JsonValueHierarchyNode`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value *` | mValue
8 | (112) `SemVersion` | mVersion
120 | (32) `std::string` | mSourceFileName


### `JsonUtil::SchemaConverterCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<JsonUtil::SchemaConverterNode>` | mCollection


### `JsonValueHierarchy`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<JsonValueHierarchyNode>` | mJson


### `Json::StyledWriter`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Writer` | baseclass_0
8 | (24) `std::vector<std::string>` | childValues_
32 | (32) `std::string` | document_
64 | (32) `std::string` | indentString_
96 | (4) `int` | rightMargin_
100 | (4) `int` | indentSize_
104 | (1) `bool` | addChildValues_


### `JsonMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackMergeStrategy` | baseclass_0
8 | (32) `std::string` | mFileName
40 | (8) `Json::Value *` | mRoot
48 | (64) `std::function<bool __cdecl(Json::Value &,Json::Value const &)>` | mPreMergeCallback


### `JsonLoader`
Offset | Type | Name
-|-|-|-
0 | (64) `Serializer` | baseclass_0
64 | (8) `JsonInternalData *` | mData


### `JigsawPlacement`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | mMaxDepth
4 | (4) `const int` | mGlobalContextSize
8 | (64) `const std::function<std::unique_ptr<PoolElementStructurePiece> __cdecl(StructurePoolElement const &,BlockPos const &,enum Rotation const &,int,JigsawJunction &,BoundingBox const &,BlockPos const &)>` | mFactory
72 | (8) `std::vector<std::unique_ptr<StructurePiece>> *` | mPieceList
80 | (8) `Random *` | mRandom
88 | (8) `const JigsawStructureRegistry *` | mPools
96 | (8) `Dimension *` | mDimension
104 | (64) `std::unordered_map<ChunkPos,std::unique_ptr<std::vector<short>>>` | mChunkHeightCache
168 | (24) `std::vector<std::function<void __cdecl(void)>>` | mPlacingQueue
192 | (24) `std::vector<std::pair<std::vector<BoundingBox>,std::vector<BoundingBox> >>` | mContextStack
216 | (262144) `std::array<Block const *,32768>` | mBlockBuffer
262360 | (32) `BlockVolume` | mBlockBufferBox


### `JigsawEditorData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mTarget
64 | (32) `std::string` | mTargetPool
96 | (32) `std::string` | mFinalBlock
128 | (4) `JigsawJointType` | mJointType


### `JigsawBlockInfo`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mPos
16 | (8) `const Block *` | mBlock
24 | (8) `const Block *` | mFinalBlock
32 | (136) `JigsawEditorData` | mEditorData


### `JsonUtil::addMemberSetter::__l2::<lambda_5e7219008c93c09fe80b5bbb5ba71ef5>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(AreaAttackDefinition *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMember::__l2::<lambda_29fe8bd269779b023f9e609e42ac6518>`
Offset | Type | Name
-|-|-|-
0 | (4) `std::string *__ptr32` | member
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_05c8167d9ccf3715fbba2faa051b0b66>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(DamageSensorTrigger *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_4f729a4716877eb58d39bfea4513dfab>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(DamageSensorTrigger *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_5ede91cee34c3c52fe17f984f217c9d7>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(MobEffectDefinition *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_79c6e42dd0a096560cd10a29e0923ee0>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(Interaction *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_48ff0a5d9661010224ed23056519ffad>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(Interaction *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_0fcae12d2687c2ac4c81468f9a8250a7>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(ShooterDefinition *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_d7fc8ed681bda1a01ddac3af94dcfb24>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(SpawnActorParameters *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JsonUtil::addMemberSetter::__l2::<lambda_47c502abe1c314c21f1d468f91740e7c>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(SpawnActorParameters *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `JumpControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mJumping
1 | (1) `bool` | mSwimming
4 | (4) `float` | mJumpPower
8 | (4) `_BYTE[4]` | mJumpType
12 | (64) `JumpInfo[4]` | mJumpInfo
80 | (8) `std::unique_ptr<JumpControl>` | mJumpControl


### `JumpInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mAnimDuration
4 | (4) `int` | mJumpDelay
8 | (4) `float` | mDistanceScale
12 | (4) `float` | mHeight


### `jpeg_common_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `jpeg_error_mgr *` | err
8 | (8) `jpeg_memory_mgr *` | mem
16 | (8) `jpeg_progress_mgr *` | progress
24 | (8) `void *` | client_data
32 | (1) `unsigned __int8` | is_decompressor
36 | (4) `int` | global_state


### `JsonUtil::addMember::__l2::<lambda_5efc4c547cd8b372b16de44f9629e759>`
Offset | Type | Name
-|-|-|-
0 | (4) `std::string *__ptr32` | member
8 | (32) `const std::string` | defaultValue


### `JournaledFile`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | mFilePath
32 | (16) `Core::File` | mFile
48 | (64) `std::function<Core::Result __cdecl(Core::Path)>` | mValidationCallback
112 | (4) `JournaledFile::Progression` | mFileProgression


### `JsonUtil::addMemberSetter::__l2::<lambda_1cfa46a954465c3ef3ff5c3f6f8a96e0>`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(AvoidBlockGoal::Definition *this, const std::string *)` | memberSetter
8 | (32) `const std::string` | defaultValue


### `Json::Reader::Token`
Offset | Type | Name
-|-|-|-
0 | (4) `Json::Reader::TokenType` | type_
8 | (8) `const char *` | start_
16 | (8) `const char *` | end_


### `jmp_buf`
Offset | Type | Name
-|-|-|-
0 | (16) `unsigned __int64[2]` | Part


### `JsonDefinitionUpgrader::IJsonDefinitionUpgrader`
```
struct __cppobj JsonDefinitionUpgrader::IJsonDefinitionUpgrader
{
  JsonDefinitionUpgrader::IJsonDefinitionUpgrader_vtbl *__vftable /*VFT*/;
};

```

### `JsonUtil::EmptyClass`
```
struct __cppobj JsonUtil::EmptyClass
{
  SemVersion mParseStateSchemaVersion;
};

```

### `JigsawStructureBlockRulesRegistry`
```
struct __cppobj JigsawStructureBlockRulesRegistry
{
  std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockRule>>>> mBlockRulesRegistry;
  std::unordered_map<std::string,std::vector<std::unique_ptr<StructurePoolBlockRule>> const *,std::hash<std::string >,std::equal_to<std::string >,std::allocator<std::pair<std::string const ,std::vector<std::unique_ptr<StructurePoolBlockRule>> const *> > > mBlockRuleLookupMap;
};

```

### `JigsawStructureBlockTagRulesRegistry`
```
struct __cppobj JigsawStructureBlockTagRulesRegistry
{
  std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockTagRule>>>> mBlockTagRulesRegistry;
  std::unordered_map<std::string,std::vector<std::unique_ptr<StructurePoolBlockTagRule>> const *,std::hash<std::string >,std::equal_to<std::string >,std::allocator<std::pair<std::string const ,std::vector<std::unique_ptr<StructurePoolBlockTagRule>> const *> > > mBlockTagRuleLookupMap;
};

```

### `JigsawStructureActorRulesRegistry`
```
struct __cppobj JigsawStructureActorRulesRegistry
{
  std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolActorRule>>>> mActorRulesRegistry;
  std::unordered_map<std::string,std::vector<std::unique_ptr<StructurePoolActorRule>> const *,std::hash<std::string >,std::equal_to<std::string >,std::allocator<std::pair<std::string const ,std::vector<std::unique_ptr<StructurePoolActorRule>> const *> > > mActorRuleLookupMap;
};

```

### `JigsawStructureElementRegistry`
```
struct __cppobj JigsawStructureElementRegistry
{
  std::vector<std::unique_ptr<StructurePoolElement>> mElementRegistry;
  std::unordered_map<std::string,StructurePoolElement const *> mElementLookupMap;
};

```

### `JigsawStructureRegistry`
```
struct __cppobj JigsawStructureRegistry
{
  std::unordered_map<std::string,std::unique_ptr<StructureTemplatePool>> mJigsawPoolLookupMap;
  JigsawStructureBlockRulesRegistry mJigsawBlockRulesRegistry;
  JigsawStructureBlockTagRulesRegistry mJigsawBlockTagRulesRegistry;
  JigsawStructureActorRulesRegistry mJigsawActorRulesRegistry;
  JigsawStructureElementRegistry mJigsawElementRegistry;
};

```

### `JumpControlDescription`
```
struct __cppobj __declspec(align(8)) JumpControlDescription : ComponentDescription
{
  float mJumpPower;
};

```

### `JumpControlDescription_vtbl`
```
struct /*VFT*/ JumpControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `jsonValConversion<bool>`
```
struct __cppobj jsonValConversion<bool>
{
};

```

### `jsonValConversion<int>`
```
struct __cppobj jsonValConversion<int>
{
};

```

### `jsonValConversion<unsigned int>`
```
struct __cppobj jsonValConversion<unsigned int>
{
};

```

### `jsonValConversion<__int64>`
```
struct __cppobj jsonValConversion<__int64>
{
};

```

### `jsonValConversion<unsigned __int64>`
```
struct __cppobj jsonValConversion<unsigned __int64>
{
};

```

### `jsonValConversion<float>`
```
struct __cppobj jsonValConversion<float>
{
};

```

### `jsonValConversion<std::string >`
```
struct __cppobj jsonValConversion<std::string >
{
};

```

### `jsonValConversion<char const *>`
```
struct __cppobj jsonValConversion<char const *>
{
};

```

### `jsonValConversion<Json::Value>`
```
struct __cppobj jsonValConversion<Json::Value>
{
};

```

### `jsonValConversion<std::vector<bool> >`
```
struct __cppobj jsonValConversion<std::vector<bool> >
{
};

```

### `jsonValConversion<std::vector<int> >`
```
struct __cppobj jsonValConversion<std::vector<int> >
{
};

```

### `jsonValConversion<std::vector<std::string> >`
```
struct __cppobj jsonValConversion<std::vector<std::string> >
{
};

```

### `JsonUtil::JsonNamedNodePtr`
```
struct __cppobj JsonUtil::JsonNamedNodePtr
{
  const std::string mNodeName;
  const Json::Value *mValuePtr;
};

```

### `JsonUtil::SchemaConverterNodeEntry`
```
struct __cppobj JsonUtil::SchemaConverterNodeEntry
{
  std::string mName;
  Json::Value *mNode;
  unsigned __int64 mIndex;
};

```

### `JsonUtil::SchemaConverterNode`
```
struct __cppobj JsonUtil::SchemaConverterNode
{
  std::vector<JsonUtil::SchemaConverterNodeEntry> mStack;
};

```

### `JsonMergeStrategy_vtbl`
```
struct /*VFT*/ JsonMergeStrategy_vtbl
{
  void (__fastcall *~ResourcePackMergeStrategy)(ResourcePackMergeStrategy *this);
  void (__fastcall *mergeFiles)(ResourcePackMergeStrategy *this, const std::vector<LoadedResourceData> *);
  void (__fastcall *_preMergeTransform)(JsonMergeStrategy *this, Json::Value *);
};

```

### `jsonValConversion<BlockPos>`
```
struct __cppobj jsonValConversion<BlockPos>
{
};

```

### `jsonValConversion<Vec3>`
```
struct __cppobj jsonValConversion<Vec3>
{
};

```

### `JpegCommentWriter`
```
struct __cppobj JpegCommentWriter
{
  FontHandle mFontHandle;
  cg::ImageBuffer mPolaroidOverlay;
  cg::ImageBuffer mOverlayMask;
  mce::MaterialPtr mTexMaterial;
};

```

### `Json::ValueIterator`
```
struct __cppobj Json::ValueIterator : Json::ValueIteratorBase
{
};

```

### `Json::StaticString`
```
struct __cppobj Json::StaticString
{
  const char *str_;
};

```

### `jsonValConversion<mce::Color>`
```
struct __cppobj jsonValConversion<mce::Color>
{
};

```

### `jsonValConversion<glm::tvec2<int,0> >`
```
struct __cppobj jsonValConversion<glm::tvec2<int,0> >
{
};

```

### `jsonValConversion<ui::LayoutOffset>`
```
struct __cppobj jsonValConversion<ui::LayoutOffset>
{
};

```

### `jsonValConversion<glm::tvec2<float,0> >`
```
struct __cppobj jsonValConversion<glm::tvec2<float,0> >
{
};

```

### `jsonValConversion<enum ui::ClipDirection>`
```
struct __cppobj jsonValConversion<enum ui::ClipDirection>
{
};

```

### `JigsawEditorScreenController`
```
struct __cppobj JigsawEditorScreenController : BlockScreenController
{
  bool mTextBoxEditing;
  JigsawEditorData mTempData;
};

```

### `JigsawEditorScreenController_vtbl`
```
struct /*VFT*/ JigsawEditorScreenController_vtbl
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

### `JigsawBlockActor`
```
struct __cppobj JigsawBlockActor : BlockActor
{
  JigsawEditorData mCurrData;
};

```

### `JigsawBlockActor_vtbl`
```
struct /*VFT*/ JigsawBlockActor_vtbl
{
  void (__fastcall *~BlockActor)(BlockActor *this);
  void (__fastcall *load)(BlockActor *this, Level *, const CompoundTag *, DataLoadHelper *);
  bool (__fastcall *save)(BlockActor *this, CompoundTag *);
  bool (__fastcall *saveItemInstanceData)(BlockActor *this, CompoundTag *);
  void (__fastcall *saveBlockData)(BlockActor *this, CompoundTag *, BlockSource *);
  void (__fastcall *loadBlockData)(BlockActor *this, const CompoundTag *, BlockSource *, DataLoadHelper *);
  void (__fastcall *onCustomTagLoadDone)(BlockActor *this, BlockSource *);
  void (__fastcall *tick)(BlockActor *this, BlockSource *);
  bool (__fastcall *isFinished)(BlockActor *this);
  void (__fastcall *onChanged)(BlockActor *this, BlockSource *);
  bool (__fastcall *isMovable)(BlockActor *this, BlockSource *);
  bool (__fastcall *isCustomNameSaved)(BlockActor *this);
  bool (__fastcall *onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *, const Player *);
  void (__fastcall *onPlace)(BlockActor *this, BlockSource *);
  void (__fastcall *onMove)(BlockActor *this);
  void (__fastcall *onRemoved)(BlockActor *this, BlockSource *);
  void (__fastcall *triggerEvent)(BlockActor *this, int, int);
  void (__fastcall *clearCache)(BlockActor *this);
  void (__fastcall *onNeighborChanged)(BlockActor *this, BlockSource *, const BlockPos *);
  float (__fastcall *getShadowRadius)(BlockActor *this, BlockSource *);
  bool (__fastcall *hasAlphaLayer)(BlockActor *this);
  BlockActor *(__fastcall *getCrackEntity)(BlockActor *this, BlockSource *, const BlockPos *);
  void (__fastcall *getDebugText)(BlockActor *this, std::vector<std::string> *, const BlockPos *);
  const std::string *(__fastcall *getCustomName)(BlockActor *this);
  const std::string *(__fastcall *getFilteredCustomName)(BlockActor *this, const UIProfanityContext *);
  std::string *(__fastcall *getName)(BlockActor *this, std::string *result);
  void (__fastcall *setCustomName)(BlockActor *this, const std::string *);
  std::string *(__fastcall *getImmersiveReaderText)(BlockActor *this, std::string *result, BlockSource *);
  int (__fastcall *getRepairCost)(BlockActor *this);
  PistonBlockActor *(__fastcall *getOwningPiston)(BlockActor *this, BlockSource *);
  const Container *(__fastcall *getContainer)(BlockActor *this);
  Container *(__fastcall *getContainer)(BlockActor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(BlockActor *this);
  void (__fastcall *checkWordsOnChunkLoad)(BlockActor *this, LevelChunk *);
  void (__fastcall *checkWordsOnUpdate)(BlockActor *this, Player *);
  void (__fastcall *onChunkLoaded)(BlockActor *this, LevelChunk *);
  void (__fastcall *onChunkUnloaded)(BlockActor *this, LevelChunk *);
  std::unique_ptr<BlockActorDataPacket> *(__fastcall *_getUpdatePacket)(BlockActor *this, std::unique_ptr<BlockActorDataPacket> *result, BlockSource *);
  void (__fastcall *_onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *);
  bool (__fastcall *_playerCanUpdate)(BlockActor *this, const Player *);
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_62ddcc5d6aed72007e0dd375b3670035>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_62ddcc5d6aed72007e0dd375b3670035>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_4e6c9dd5216ff13092858adddb4221f5>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_4e6c9dd5216ff13092858adddb4221f5>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_61b0d53313a6518e14b4db00d0fd4bf1>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_61b0d53313a6518e14b4db00d0fd4bf1>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_18738adf91b9182307512faa96a83bfb>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_18738adf91b9182307512faa96a83bfb>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_c19cf5bb24bb91524429ca5029d7025e>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_c19cf5bb24bb91524429ca5029d7025e>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_68578185fab31f30ca1c811507ab8e6e>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_68578185fab31f30ca1c811507ab8e6e>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_59f71b495a904841fa87fb53c6e2f363>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_59f71b495a904841fa87fb53c6e2f363>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_b6fb89ad106355dfc631f779b7b34b02>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_b6fb89ad106355dfc631f779b7b34b02>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_d95e0c97ad881e46f8a5bbd7d7be64e6>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_d95e0c97ad881e46f8a5bbd7d7be64e6>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerBindings::__l2::<lambda_b629806ab35cd72f37559a2461b92634>`
```
struct __cppobj JigsawEditorScreenController::_registerBindings::__l2::<lambda_b629806ab35cd72f37559a2461b92634>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_6f2f5971176ea1a22a3fe2cd610fe6e9>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_6f2f5971176ea1a22a3fe2cd610fe6e9>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_9979047eb1eaf00611f60167979bfc00>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_9979047eb1eaf00611f60167979bfc00>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_05d89d2663048e91cd208d11440d423d>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_05d89d2663048e91cd208d11440d423d>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_d778ac1a84d750e074b9496e517ad938>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_d778ac1a84d750e074b9496e517ad938>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_6bab0ca163eab0f6fe95223e3969ae9b>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_6bab0ca163eab0f6fe95223e3969ae9b>
{
  JigsawEditorScreenController *const __this;
};

```

### `JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_c0ade3180c892bf1c1be9138e551af13>`
```
struct __cppobj JigsawEditorScreenController::_registerEventHandlers::__l2::<lambda_c0ade3180c892bf1c1be9138e551af13>
{
  JigsawEditorScreenController *const __this;
};

```

### `jsonValConversion<char [13]>`
```
struct __cppobj jsonValConversion<char [13]>
{
};

```

### `jsonValConversion<char [14]>`
```
struct __cppobj jsonValConversion<char [14]>
{
};

```

### `JOBOBJECT_NET_RATE_CONTROL_INFORMATION`
```
struct __declspec(align(4)) JOBOBJECT_NET_RATE_CONTROL_INFORMATION
{
  unsigned __int64 MaxBandwidth;
  JOB_OBJECT_NET_RATE_CONTROL_FLAGS ControlFlags;
  unsigned __int8 DscpTag;
};

```

### `JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE_V3`
```
struct JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE_V3
{
  __int64 MaxIops;
  __int64 MaxBandwidth;
  __int64 ReservationIops;
  wchar_t *VolumeName;
  unsigned int BaseIoSize;
  JOB_OBJECT_IO_RATE_CONTROL_FLAGS ControlFlags;
  unsigned __int16 VolumeNameLength;
  __int64 CriticalReservationIops;
  __int64 ReservationBandwidth;
  __int64 CriticalReservationBandwidth;
  __int64 MaxTimePercent;
  __int64 ReservationTimePercent;
  __int64 CriticalReservationTimePercent;
  __int64 SoftMaxIops;
  __int64 SoftMaxBandwidth;
  __int64 SoftMaxTimePercent;
  __int64 LimitExcessNotifyIops;
  __int64 LimitExcessNotifyBandwidth;
  __int64 LimitExcessNotifyTimePercent;
};

```

### `Json::PathArgument`
```
struct __cppobj Json::PathArgument
{
  std::string key_;
  unsigned int index_;
  Json::PathArgument::Kind kind_;
};

```

### `Json::Reader::ErrorInfo`
```
struct __cppobj Json::Reader::ErrorInfo
{
  Json::Reader::Token token_;
  std::string message_;
  const char *extra_;
};

```

### `JOBOBJECT_IO_RATE_CONTROL_INFORMATION`
```
struct JOBOBJECT_IO_RATE_CONTROL_INFORMATION
{
  __int64 MaxIops;
  __int64 MaxBandwidth;
  __int64 ReservationIops;
  const wchar_t *VolumeName;
  unsigned int BaseIoSize;
  unsigned int ControlFlags;
};

```

### `JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE`
```
struct __declspec(align(8)) JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE
{
  __int64 MaxIops;
  __int64 MaxBandwidth;
  __int64 ReservationIops;
  wchar_t *VolumeName;
  unsigned int BaseIoSize;
  JOB_OBJECT_IO_RATE_CONTROL_FLAGS ControlFlags;
  unsigned __int16 VolumeNameLength;
};

```

### `Json::Writer_vtbl`
```
struct /*VFT*/ Json::Writer_vtbl
{
  void (__fastcall *~Writer)(Json::Writer *this);
  std::string *(__fastcall *write)(Json::Writer *this, std::string *result, const Json::Value *);
};

```

### `Json::FastWriter_vtbl`
```
struct /*VFT*/ Json::FastWriter_vtbl
{
  void (__fastcall *~Writer)(Json::Writer *this);
  std::string *(__fastcall *write)(Json::Writer *this, std::string *result, const Json::Value *);
};

```

### `Json::Path`
```
struct __cppobj Json::Path
{
  std::vector<Json::PathArgument> args_;
};

```

### `Json::StyledWriter_vtbl`
```
struct /*VFT*/ Json::StyledWriter_vtbl
{
  void (__fastcall *~Writer)(Json::Writer *this);
  std::string *(__fastcall *write)(Json::Writer *this, std::string *result, const Json::Value *);
};

```

### `JOBOBJECT_NOTIFICATION_LIMIT_INFORMATION_2`
```
struct __declspec(align(8)) JOBOBJECT_NOTIFICATION_LIMIT_INFORMATION_2
{
  unsigned __int64 IoReadBytesLimit;
  unsigned __int64 IoWriteBytesLimit;
  _LARGE_INTEGER PerJobUserTimeLimit;
  $864EEC0230CCEC23B20243BD24DC1C56 ___u3;
  $D61F14936F3CA09BB6167DC425663096 ___u4;
  $4176229E216CC8EAE17DC2E3A5F9DE64 ___u5;
  unsigned int LimitFlags;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE IoRateControlTolerance;
  unsigned __int64 JobLowMemoryLimit;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE_INTERVAL IoRateControlToleranceInterval;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE NetRateControlTolerance;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE_INTERVAL NetRateControlToleranceInterval;
};

```

### `JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE_V2`
```
struct JOBOBJECT_IO_RATE_CONTROL_INFORMATION_NATIVE_V2
{
  __int64 MaxIops;
  __int64 MaxBandwidth;
  __int64 ReservationIops;
  wchar_t *VolumeName;
  unsigned int BaseIoSize;
  JOB_OBJECT_IO_RATE_CONTROL_FLAGS ControlFlags;
  unsigned __int16 VolumeNameLength;
  __int64 CriticalReservationIops;
  __int64 ReservationBandwidth;
  __int64 CriticalReservationBandwidth;
  __int64 MaxTimePercent;
  __int64 ReservationTimePercent;
  __int64 CriticalReservationTimePercent;
};

```

### `JOBOBJECT_LIMIT_VIOLATION_INFORMATION_2`
```
struct JOBOBJECT_LIMIT_VIOLATION_INFORMATION_2
{
  unsigned int LimitFlags;
  unsigned int ViolationLimitFlags;
  unsigned __int64 IoReadBytes;
  unsigned __int64 IoReadBytesLimit;
  unsigned __int64 IoWriteBytes;
  unsigned __int64 IoWriteBytesLimit;
  _LARGE_INTEGER PerJobUserTime;
  _LARGE_INTEGER PerJobUserTimeLimit;
  unsigned __int64 JobMemory;
  $864EEC0230CCEC23B20243BD24DC1C56 ___u9;
  $D61F14936F3CA09BB6167DC425663096 ___u10;
  $BCAFF580C2C7801C8349B2B3CBC9C5D9 ___u11;
  unsigned __int64 JobLowMemoryLimit;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE IoRateControlTolerance;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE IoRateControlToleranceLimit;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE NetRateControlTolerance;
  _JOBOBJECT_RATE_CONTROL_TOLERANCE NetRateControlToleranceLimit;
};

```

### `JoystickComponent`
```
struct __cppobj __declspec(align(8)) JoystickComponent : UIComponent
{
  std::weak_ptr<UIControlFactory> mControlFactory;
  std::weak_ptr<UIControl> mDirector;
  bool isDraging;
  bool isEightDirections;
  float mPriorCursorPosition[2];
};

```

### `JoystickComponent_vtbl`
```
struct /*VFT*/ JoystickComponent_vtbl
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

### `jsonValConversion<char [8]>`
```
struct __cppobj jsonValConversion<char [8]>
{
};

```

### `jsonValConversion<char [21]>`
```
struct __cppobj jsonValConversion<char [21]>
{
};

```

### `jsonValConversion<char [15]>`
```
struct __cppobj jsonValConversion<char [15]>
{
};

```

### `jsonValConversion<char [22]>`
```
struct __cppobj jsonValConversion<char [22]>
{
};

```

### `jsonValConversion<char [17]>`
```
struct __cppobj jsonValConversion<char [17]>
{
};

```

### `JsonValidator`
```
struct __cppobj JsonValidator
{
};

```

### `JoincodeEntryScreenController`
```
struct __cppobj __declspec(align(8)) JoincodeEntryScreenController : MinecraftScreenController
{
  std::shared_ptr<EDUDiscovery::QueryContext<EDUDiscovery::JoinServerQueryState> > mJoinContext;
  std::shared_ptr<EDUDiscovery::QueryContext<enum EDUDiscovery::Availability> > mAvailabilityContext;
  EDUDiscovery::Error mJoinError;
  std::string mHostUsername;
  std::string mWorldName;
  _BYTE mActiveScreen[4];
  EDUDiscovery::JoinCode mEnteredJoincode;
  int mHoveredEntry;
  std::function<void __cdecl(std::string)> mUpdateIPHeaderText;
  std::function<bool __cdecl(void)> mCheckForServiceDialog;
  bool mServiceRedirectedToIP;
};

```

### `JoincodeEntryScreenController_vtbl`
```
struct /*VFT*/ JoincodeEntryScreenController_vtbl
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

### `jsonValConversion<char [12]>`
```
struct __cppobj jsonValConversion<char [12]>
{
};

```

### `jsonValConversion<char [9]>`
```
struct __cppobj jsonValConversion<char [9]>
{
};

```

### `jsonValConversion<char [7]>`
```
struct __cppobj jsonValConversion<char [7]>
{
};

```

### `jsonValConversion<char [18]>`
```
struct __cppobj jsonValConversion<char [18]>
{
};

```

### `JukeboxBlockActor`
```
struct __cppobj __declspec(align(8)) JukeboxBlockActor : RandomizableBlockActorContainer
{
  ItemStack mRecord;
  int mCount;
  bool mRecordingFinished;
  int mTicksPlaying;
};

```

### `JoincodePauseMenuScreenController`
```
struct __cppobj JoincodePauseMenuScreenController : ClientInstanceScreenController, EDUDiscovery::DiscoveryObserver
{
  std::shared_ptr<PauseScreenModel> mPauseScreenModel;
  const std::vector<ActorUniqueID> *mClientIds;
  bool mJoinCodeNeedsRefresh;
  int mCurrentJoincodeFetchingAnim;
  int mJoincodeFetchingAnimCount;
  std::function<void __cdecl(void)> mCheckForServiceDialog;
};

```

### `JoincodePauseMenuScreenController_vtbl`
```
struct /*VFT*/ JoincodePauseMenuScreenController_vtbl
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

### `jsonValConversion<char [1]>`
```
struct __cppobj jsonValConversion<char [1]>
{
};

```

### `jsonValConversion<char [10]>`
```
struct __cppobj jsonValConversion<char [10]>
{
};

```

### `jsonValConversion<char [16]>`
```
struct __cppobj jsonValConversion<char [16]>
{
};

```

### `jsonValConversion<char [19]>`
```
struct __cppobj jsonValConversion<char [19]>
{
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_19b510b3e3e560e148e6bf24ee734a37>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_19b510b3e3e560e148e6bf24ee734a37>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_d66a97533289017a9d4184160cefb538>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_d66a97533289017a9d4184160cefb538>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_a6e6e25ebae1f25497f5291fcd917576>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_a6e6e25ebae1f25497f5291fcd917576>
{
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_ac0e1e8bed4f7c85ddd1d6a175b9b9c1>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_ac0e1e8bed4f7c85ddd1d6a175b9b9c1>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_1b4eb6e1bc0925b0848cce6d062fa360>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_1b4eb6e1bc0925b0848cce6d062fa360>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_d549141f79be71e8e0b14bb00c164f45>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_d549141f79be71e8e0b14bb00c164f45>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_4a09fc7aff3d5ebb46787248c84862e1>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_4a09fc7aff3d5ebb46787248c84862e1>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_857bb76f917f37cf24ddb4bd22021444>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_857bb76f917f37cf24ddb4bd22021444>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_aa73ec77b5f3bca16e1960d889c9ffff>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_aa73ec77b5f3bca16e1960d889c9ffff>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_0529820eaa5e2c599660595952e6dc32>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_0529820eaa5e2c599660595952e6dc32>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_7022d0dc00738eae83e1cee92ab76531>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_7022d0dc00738eae83e1cee92ab76531>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_388c1846c6e5bb10d6fe3df144e0f2b7>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_388c1846c6e5bb10d6fe3df144e0f2b7>
{
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_fd50c569b844e1351602cb9f97d9c5e2>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_fd50c569b844e1351602cb9f97d9c5e2>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_ca4dab6679e2cb17b19df8e7ec78804c>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_ca4dab6679e2cb17b19df8e7ec78804c>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_75ee644843718a641d51ff3370f4ce90>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_75ee644843718a641d51ff3370f4ce90>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_6aa5e7f7cdf5fce7bf9065de8d9fb78d>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_6aa5e7f7cdf5fce7bf9065de8d9fb78d>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_4d77bccdfa49585081e11d66c766156c>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_4d77bccdfa49585081e11d66c766156c>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_947f12b40f6b8aaa4d4b763af03618e1>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerBindings::__l2::<lambda_947f12b40f6b8aaa4d4b763af03618e1>
{
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_45e06c01539d2d08f19a2bf60d9c909a>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_45e06c01539d2d08f19a2bf60d9c909a>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_45e06c01539d2d08f19a2bf60d9c909a>::()::__l5::<lambda_a6be52efd9819f20fc63ac36d0025e50>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_45e06c01539d2d08f19a2bf60d9c909a>::()::__l5::<lambda_a6be52efd9819f20fc63ac36d0025e50>
{
  std::weak_ptr<JoincodePauseMenuScreenController> weakThis;
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_506527c1535171b85b756b5f49c12bd2>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_506527c1535171b85b756b5f49c12bd2>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_506527c1535171b85b756b5f49c12bd2>::()::__l5::<lambda_e3ae8facdfdecde10cd106c72b065d7d>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_506527c1535171b85b756b5f49c12bd2>::()::__l5::<lambda_e3ae8facdfdecde10cd106c72b065d7d>
{
  std::weak_ptr<JoincodePauseMenuScreenController> weakThis;
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_47661a53836761adc9009565a017df82>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_47661a53836761adc9009565a017df82>
{
  JoincodePauseMenuScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_47661a53836761adc9009565a017df82>::()::__l5::<lambda_73dfa56787e48312a41b5822d2c5af6e>`
```
struct __cppobj JoincodePauseMenuScreenController::_registerEventHandlers::__l5::<lambda_47661a53836761adc9009565a017df82>::()::__l5::<lambda_73dfa56787e48312a41b5822d2c5af6e>
{
  std::weak_ptr<JoincodePauseMenuScreenController> weakThis;
};

```

### `JoincodeEntryScreenController::_registerIPJoinBindings::__l2::<lambda_57072bf64f84136a1b5c6cc0ca5d5ce1>`
```
struct __cppobj JoincodeEntryScreenController::_registerIPJoinBindings::__l2::<lambda_57072bf64f84136a1b5c6cc0ca5d5ce1>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerFoundServerBindings::__l2::<lambda_19bc163d248c4af85e6f0b63152ff059>`
```
struct __cppobj JoincodeEntryScreenController::_registerFoundServerBindings::__l2::<lambda_19bc163d248c4af85e6f0b63152ff059>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerFoundServerBindings::__l2::<lambda_766c291bc0d822b0a08834de6ede306e>`
```
struct __cppobj JoincodeEntryScreenController::_registerFoundServerBindings::__l2::<lambda_766c291bc0d822b0a08834de6ede306e>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerErrorScreenBindings::__l2::<lambda_6bfa3899f50543e8539f894c1355ba30>`
```
struct __cppobj JoincodeEntryScreenController::_registerErrorScreenBindings::__l2::<lambda_6bfa3899f50543e8539f894c1355ba30>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerErrorScreenBindings::__l2::<lambda_f6c3df08507f9ff8444de11cfdbce804>`
```
struct __cppobj JoincodeEntryScreenController::_registerErrorScreenBindings::__l2::<lambda_f6c3df08507f9ff8444de11cfdbce804>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_98f859a1ea31ced3a57abbf14d099143>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_98f859a1ea31ced3a57abbf14d099143>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_b51db3996d738bb20aa0b6b01ffde9d9>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_b51db3996d738bb20aa0b6b01ffde9d9>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_9721f73a940f37896cb5c1a87b2c323f>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_9721f73a940f37896cb5c1a87b2c323f>
{
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_e6b9c68359a0ee0afc8af4a1f15ff6f1>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_e6b9c68359a0ee0afc8af4a1f15ff6f1>
{
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_eccf9bbeb90f2b55eb195cec3c89005b>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_eccf9bbeb90f2b55eb195cec3c89005b>
{
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_faf68fb482231fc98f02304ab5066350>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_faf68fb482231fc98f02304ab5066350>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_873117e9288038a0cd5c0b3503d04268>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_873117e9288038a0cd5c0b3503d04268>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_08a58042d1fa6e1a4d4a4b7c94ff0819>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_08a58042d1fa6e1a4d4a4b7c94ff0819>
{
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_7e94e6c459a5928bf1614731582d46e4>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_7e94e6c459a5928bf1614731582d46e4>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_7bb79b33bb6a63f566f5bf999a4d220e>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_7bb79b33bb6a63f566f5bf999a4d220e>
{
};

```

### `JoincodeEntryScreenController::_registerBindings::__l2::<lambda_4133d3848baf0d4cc16b1e4111df1e48>`
```
struct __cppobj JoincodeEntryScreenController::_registerBindings::__l2::<lambda_4133d3848baf0d4cc16b1e4111df1e48>
{
};

```

### `JoincodeEntryScreenController::_registerIPJoinHandlers::__l2::<lambda_d5c827b2d8a450e9d2d5ab210d9e49ae>`
```
struct __cppobj JoincodeEntryScreenController::_registerIPJoinHandlers::__l2::<lambda_d5c827b2d8a450e9d2d5ab210d9e49ae>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_b70236001f4d18039354d9b0bccd0892>`
```
struct __cppobj JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_b70236001f4d18039354d9b0bccd0892>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_2d3b9bf51418817c418924f8584802d4>`
```
struct __cppobj JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_2d3b9bf51418817c418924f8584802d4>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_80125f38ad174fccef19a3ea7a188592>`
```
struct __cppobj JoincodeEntryScreenController::_registerFoundServerHandlers::__l2::<lambda_80125f38ad174fccef19a3ea7a188592>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerErrorScreenHandlers::__l2::<lambda_f91bbf550fa95edb2c204985cbb7e7d1>`
```
struct __cppobj JoincodeEntryScreenController::_registerErrorScreenHandlers::__l2::<lambda_f91bbf550fa95edb2c204985cbb7e7d1>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerErrorScreenHandlers::__l2::<lambda_33117e76cee9c79022e33d2a1218ffdd>`
```
struct __cppobj JoincodeEntryScreenController::_registerErrorScreenHandlers::__l2::<lambda_33117e76cee9c79022e33d2a1218ffdd>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerConnectingScreenHandlers::__l2::<lambda_afc651d718c77fc7fa022ddd5528565d>`
```
struct __cppobj JoincodeEntryScreenController::_registerConnectingScreenHandlers::__l2::<lambda_afc651d718c77fc7fa022ddd5528565d>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerConnectingScreenHandlers::__l2::<lambda_40e26c482be6fd9fe0a7ac135d228516>`
```
struct __cppobj JoincodeEntryScreenController::_registerConnectingScreenHandlers::__l2::<lambda_40e26c482be6fd9fe0a7ac135d228516>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_9550b0cd5d6550d34569825e453a6da3>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_9550b0cd5d6550d34569825e453a6da3>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_99328fb740159e286c31b44684f958e1>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_99328fb740159e286c31b44684f958e1>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_f87c3c3f2f126044d7823599265a41c0>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_f87c3c3f2f126044d7823599265a41c0>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_f87c3c3f2f126044d7823599265a41c0>::()::__l2::<lambda_fb949c23ec46956c339fa8b7c2c89225>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_f87c3c3f2f126044d7823599265a41c0>::()::__l2::<lambda_fb949c23ec46956c339fa8b7c2c89225>
{
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_c17531c64411ed317538f72bdedabcc0>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_c17531c64411ed317538f72bdedabcc0>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_8163864582b2816e044236a2f0e101f5>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_8163864582b2816e044236a2f0e101f5>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_180a98c982d2a260422e4c80abbb10ca>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_180a98c982d2a260422e4c80abbb10ca>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_db30b9a3787e505c267a05b2d9d49986>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenHandlers::__l2::<lambda_db30b9a3787e505c267a05b2d9d49986>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_85480f5b24516f2d1aeb92c30c4b76bf>`
```
struct __cppobj JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_85480f5b24516f2d1aeb92c30c4b76bf>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_b6c50970fd50e23c794b64687d266bc2>`
```
struct __cppobj JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_b6c50970fd50e23c794b64687d266bc2>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_b6c50970fd50e23c794b64687d266bc2>::()::__l2::<lambda_02c0be17cc089d27576ee865cffd1d19>`
```
struct __cppobj JoincodeEntryScreenController::_registerEventHandlers::__l2::<lambda_b6c50970fd50e23c794b64687d266bc2>::()::__l2::<lambda_02c0be17cc089d27576ee865cffd1d19>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodePauseMenuScreenController::{ctor}::__l2::<lambda_80b6e65ce4cdfab7952e89df028ec198>`
```
struct __cppobj JoincodePauseMenuScreenController::{ctor}::__l2::<lambda_80b6e65ce4cdfab7952e89df028ec198>
{
  std::weak_ptr<EDUDiscoveryDialogScreenController> discoveryController;
};

```

### `JoincodeEntryScreenController::{ctor}::__l2::<lambda_e6cfa59d7b81dd0d9e36e1fee1bbc081>`
```
struct __cppobj JoincodeEntryScreenController::{ctor}::__l2::<lambda_e6cfa59d7b81dd0d9e36e1fee1bbc081>
{
  std::weak_ptr<EDUDiscoveryDialogScreenController> discoveryController;
};

```

### `JoincodeEntryScreenController::{ctor}::__l2::<lambda_0e06af07cc88e22e521e82c2979af008>`
```
struct __cppobj JoincodeEntryScreenController::{ctor}::__l2::<lambda_0e06af07cc88e22e521e82c2979af008>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::{ctor}::__l2::<lambda_aa7da5a3c681f329347cf3288a461934>`
```
struct __cppobj JoincodeEntryScreenController::{ctor}::__l2::<lambda_aa7da5a3c681f329347cf3288a461934>
{
  JoincodeEntryScreenController *const __this;
};

```

### `JoincodeEntryScreenController::{ctor}::__l2::<lambda_19f3b5769b63a822a2bc2202da7408ba>`
```
struct __cppobj JoincodeEntryScreenController::{ctor}::__l2::<lambda_19f3b5769b63a822a2bc2202da7408ba>
{
  std::shared_ptr<IPJoinScreenController> ipJoinController;
};

```

### `jsonValConversion<char [20]>`
```
struct __cppobj jsonValConversion<char [20]>
{
};

```

### `jsonValConversion<char [25]>`
```
struct __cppobj jsonValConversion<char [25]>
{
};

```

### `jsonValConversion<char [36]>`
```
struct __cppobj jsonValConversion<char [36]>
{
};

```

### `jsonValConversion<char [11]>`
```
struct __cppobj jsonValConversion<char [11]>
{
};

```

### `jsonValConversion<char [6]>`
```
struct __cppobj jsonValConversion<char [6]>
{
};

```

### `jsonValConversion<char [23]>`
```
struct __cppobj jsonValConversion<char [23]>
{
};

```

### `JigsawStructureBlockInfo`
```
struct __cppobj JigsawStructureBlockInfo
{
  BlockPos mPos;
  const Block *mBlock;
  std::unique_ptr<CompoundTag> mTag;
};

```

### `jsonValConversion<char [31]>`
```
struct __cppobj jsonValConversion<char [31]>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_5e05581b3dc4db2a4d1f817985fc6382>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5e05581b3dc4db2a4d1f817985fc6382>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_abb058bdc6e961d24d00fc04ce30557b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_abb058bdc6e961d24d00fc04ce30557b>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_55424b127713ac984a3bf4b0f246c565>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_55424b127713ac984a3bf4b0f246c565>
{
  void (__fastcall *memberSetter)(BuoyancyDefinition *this, const BlockDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_f12c03e0e2ed3a8eea128c42b455176b>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_f12c03e0e2ed3a8eea128c42b455176b>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_ba610a14103f08d81f61c77f2fffedae>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_ba610a14103f08d81f61c77f2fffedae>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_312293d7c528d3342a6060f050e89274>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_312293d7c528d3342a6060f050e89274>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8468ab08f70925d32e36579a71c0e854>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8468ab08f70925d32e36579a71c0e854>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_ad51c8f169566eb97c4cf805ce14ec58>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ad51c8f169566eb97c4cf805ce14ec58>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_b36136475919f2dc59c7ea84261d65ec>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_b36136475919f2dc59c7ea84261d65ec>
{
  void (__fastcall *memberSetter)(ConditionalBandwidthOptimizationDefinition *this, const ConditionalBandwidthOptimization *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_c8f2c52e9b61e7ee9db117b78b5be844>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_c8f2c52e9b61e7ee9db117b78b5be844>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d2ea3557a60794246bb00be768b68f3b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d2ea3557a60794246bb00be768b68f3b>
{
  void (__fastcall *memberSetter)(ConditionalBandwidthOptimizationDefinition *this, const ConditionalBandwidthOptimization *);
};

```

### `JsonUtil::details::BlockReference`
```
struct __cppobj JsonUtil::details::BlockReference
{
  std::string mBlockType;
  CompoundTag mStates;
};

```

### `JsonUtil::addMember::__l2::<lambda_be69145dcabfc8148251e29f267deb8d>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_be69145dcabfc8148251e29f267deb8d>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c602fb05de54e689507dcd52606ca8be>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c602fb05de54e689507dcd52606ca8be>
{
  bool *__ptr32 member;
};

```

### `JsonDefinitionUpgrader::createCompositeUpgrader::__l2::Upgrader`
```
struct __cppobj JsonDefinitionUpgrader::createCompositeUpgrader::__l2::Upgrader : JsonDefinitionUpgrader::IJsonDefinitionUpgrader
{
  std::vector<std::unique_ptr<JsonDefinitionUpgrader::IJsonDefinitionUpgrader>> mUpgraders;
};

```

### `JsonDefinitionUpgrader::createUpgrader::__l2::Upgrader`
```
struct __cppobj JsonDefinitionUpgrader::createUpgrader::__l2::Upgrader : JsonDefinitionUpgrader::IJsonDefinitionUpgrader
{
  const SemVersion mFrom;
  const SemVersion mTo;
  const std::function<void __cdecl(rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator> &)> mUpgrader;
};

```

### `JsonInternalData`
```
struct __cppobj JsonInternalData
{
  rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator> mDocument;
  rapidjson::GenericStringBuffer<rapidjson::UTF8<char>,rapidjson::CrtAllocator> mBuffer;
  rapidjson::PrettyWriter<rapidjson::GenericStringBuffer<rapidjson::UTF8<char>,rapidjson::CrtAllocator>,rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator,0> mWriter;
  rapidjson::Writer<rapidjson::GenericStringBuffer<rapidjson::UTF8<char>,rapidjson::CrtAllocator>,rapidjson::UTF8<char>,rapidjson::UTF8<char>,rapidjson::CrtAllocator,0> mReader;
  std::stack<rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *,std::deque<rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *,std::allocator<rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *> > > mStack;
};

```

### `JsonLoader_vtbl`
```
struct /*VFT*/ JsonLoader_vtbl
{
  void (__fastcall *~Serializer)(Serializer *this);
  bool (__fastcall *isBool)(Serializer *this);
  bool (__fastcall *isInt)(Serializer *this);
  bool (__fastcall *isString)(Serializer *this);
  bool (__fastcall *isObject)(Serializer *this);
  bool (__fastcall *isArray)(Serializer *this);
  bool (__fastcall *serializeBool)(Serializer *this, bool *);
  bool (__fastcall *serializeS8)(Serializer *this, char *);
  bool (__fastcall *serializeU8)(Serializer *this, unsigned __int8 *);
  bool (__fastcall *serializeS16)(Serializer *this, __int16 *);
  bool (__fastcall *serializeU16)(Serializer *this, unsigned __int16 *);
  bool (__fastcall *serializeS32)(Serializer *this, int *);
  bool (__fastcall *serializeU32)(Serializer *this, unsigned int *);
  bool (__fastcall *serializeFloat)(Serializer *this, float *);
  bool (__fastcall *serializeString)(Serializer *this, std::string *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned int *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int16 *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int8 *, const SerializerTraits *);
  bool (__fastcall *beginMember)(Serializer *this, unsigned __int64, std::string *);
  bool (__fastcall *beginMember)(Serializer *this, const char *, bool);
  bool (__fastcall *endMember)(Serializer *this);
  bool (__fastcall *beginArray)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginArrayItem)(Serializer *this, unsigned __int64);
  bool (__fastcall *endArrayItem)(Serializer *this);
  bool (__fastcall *endArray)(Serializer *this);
  bool (__fastcall *beginObject)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginObject)(Serializer *this);
  bool (__fastcall *endObject)(Serializer *this);
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>
{
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_e1ac510360888cb952885b5b815423e4>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_e1ac510360888cb952885b5b815423e4>
{
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_0e8d04c740841fd9cd78f8e42034e246>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_0e8d04c740841fd9cd78f8e42034e246>
{
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_70e7bc903355b7523c79ae8596e2309b>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_70e7bc903355b7523c79ae8596e2309b>
{
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_6502f72ee1fa18dea3b55e5379ad1c23>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_6502f72ee1fa18dea3b55e5379ad1c23>
{
};

```

### `JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_58e2e3281df267ff8ae4dfd704cb4a47>`
```
struct __cppobj JsonUtil::details::_getOrMakeBlockReferenceSchema::__l2::<lambda_ccf6c929f3075b25db9a6d7e5a4eeb79>::()::__l2::<lambda_58e2e3281df267ff8ae4dfd704cb4a47>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2c297f6d0b4b333e3c28188c6bc68d71>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_2c297f6d0b4b333e3c28188c6bc68d71>
{
  void (__fastcall *memberSetter)(BlockPlacementCondition *this, const BlockDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_f46d07358ca6a0dba712f554510d8963>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_f46d07358ca6a0dba712f554510d8963>
{
};

```

### `JigsawJunction`
```
struct __cppobj JigsawJunction
{
  BlockPos mSourceBlockPos;
  int mDeltaSourceY;
  int mDeltaTargetY;
  Projection mSourceProjection;
  Projection mTargetProjection;
};

```

### `JigsawBlock`
```
struct __cppobj JigsawBlock : FaceDirectionalActorBlock
{
};

```

### `JigsawBlock_vtbl`
```
struct /*VFT*/ JigsawBlock_vtbl
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

### `JigsawPlacement::_tryPlacingPiece::__l42::<lambda_1bfb005e911fae2e3edef778c2fe4383>`
```
struct __cppobj JigsawPlacement::_tryPlacingPiece::__l42::<lambda_1bfb005e911fae2e3edef778c2fe4383>
{
  JigsawPlacement *const __this;
  PoolElementStructurePiece *piece;
  BlockPos targetPosition;
  const Rotation rotation;
  const BlockPos *refPos;
  unsigned __int64 contextDepth;
};

```

### `JigsawPlacement::addPieces::__l2::<lambda_ddf4b036c1a3fcbd72bdd8fe7dbac8da>`
```
struct __cppobj __declspec(align(8)) JigsawPlacement::addPieces::__l2::<lambda_ddf4b036c1a3fcbd72bdd8fe7dbac8da>
{
  JigsawPlacement *const __this;
  PoolElementStructurePiece *centerPiece;
  const BlockPos position;
  const int yOffset;
  const Rotation rotation;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_6248eeec99fbdf7a0a784133011e41eb>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_6248eeec99fbdf7a0a784133011e41eb>
{
  void (__fastcall *memberSetter)(CommandResponse *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_23c75cafe28d91c8a439aa1ec40711f1>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_23c75cafe28d91c8a439aa1ec40711f1>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7f7f0f23c5f5872fb227da9e977f3c5e>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7f7f0f23c5f5872fb227da9e977f3c5e>
{
  void (__fastcall *memberSetter)(CommandResponse *this, const std::string *);
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_441cd1880ac15616a9c6f88dd545f4af>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_441cd1880ac15616a9c6f88dd545f4af>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_35ad34843a294e49bd8d9296ef7d99a0>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_35ad34843a294e49bd8d9296ef7d99a0>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_b511cb8fcc2a853006f0611a3faecf0e>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_b511cb8fcc2a853006f0611a3faecf0e>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_db02982b225b7bcb3a2785c6832ec6ce>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_db02982b225b7bcb3a2785c6832ec6ce>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_cd1ef9f7b16d8a790d4cbe69939e4034>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_cd1ef9f7b16d8a790d4cbe69939e4034>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_1661bb6fe4418907da8e0c4f3cbff346>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_1661bb6fe4418907da8e0c4f3cbff346>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_868a2793a9555eff7ff07e7eb65a349d>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_868a2793a9555eff7ff07e7eb65a349d>
{
};

```

### `JsonUtil::addFilterSubject::__l2::<lambda_13a4c32f46492d37e5e76d06d553bea3>`
```
struct __cppobj JsonUtil::addFilterSubject::__l2::<lambda_13a4c32f46492d37e5e76d06d553bea3>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_95cfa2827bd4565e1beb12be3179f2d8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_95cfa2827bd4565e1beb12be3179f2d8>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e92a1854f82fd8dded6366cf7f0e2b03>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e92a1854f82fd8dded6366cf7f0e2b03>
{
  void (__fastcall *memberSetter)(AreaAttackDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_4838adfe17bf45ebbe151250f38e59e3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4838adfe17bf45ebbe151250f38e59e3>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_07df76419bda9ffaed6a197ebdfac328>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_07df76419bda9ffaed6a197ebdfac328>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4f3ae295c87a351303baf484e900e4cb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4f3ae295c87a351303baf484e900e4cb>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_92e9e7ed2fa80cf9818441c988f47bfc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_92e9e7ed2fa80cf9818441c988f47bfc>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1b953485bad14054034cd2f6c1df5032>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1b953485bad14054034cd2f6c1df5032>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_df738ed86875711e22e22f1a03492795>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_df738ed86875711e22e22f1a03492795>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_609214da2f5fb269baaf86778ff561a0>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_609214da2f5fb269baaf86778ff561a0>
{
  void (__fastcall *memberSetter)(AngryDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_08ecd04fd9c2e8474444213735952c23>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_08ecd04fd9c2e8474444213735952c23>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_80cbd856e1181b5b0ba392957395e7c8>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_80cbd856e1181b5b0ba392957395e7c8>
{
  void (__fastcall *memberSetter)(AngryDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_3a87d6a0e0ec2d41eb3325c1543987c5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3a87d6a0e0ec2d41eb3325c1543987c5>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_706738a70112150466a9f96ec6f44e5c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_706738a70112150466a9f96ec6f44e5c>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a285fdf7f273d36f4530dad096fd25b7>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_a285fdf7f273d36f4530dad096fd25b7>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e1016d6665b0a76c0aeca082f6c40609>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e1016d6665b0a76c0aeca082f6c40609>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4961d1ab8dfced61f91df8f06f8ee38e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4961d1ab8dfced61f91df8f06f8ee38e>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_1dddf3f4aa725f2e7cfa03dd65cec76c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1dddf3f4aa725f2e7cfa03dd65cec76c>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a833797d810e61be40afed2f73a3bca8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a833797d810e61be40afed2f73a3bca8>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1ba5443806c1e7783c27c015d166d1aa>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1ba5443806c1e7783c27c015d166d1aa>
{
  void (__fastcall *memberSetter)(AgeableDefinition *this, const ItemDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_e76208c1effffa8669920f22b99d9d12>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_e76208c1effffa8669920f22b99d9d12>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7832c71f1c9f778fca8871e7210293b2>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7832c71f1c9f778fca8871e7210293b2>
{
  void (__fastcall *memberSetter)(AgeableDefinition *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_98b465827dfe0ba72128308991e91680>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_98b465827dfe0ba72128308991e91680>
{
  void (__fastcall *memberSetter)(AgeableDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_24f55621072abfdda3838cbc9596bcaf>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_24f55621072abfdda3838cbc9596bcaf>
{
  std::vector<ActorDefinitionFeedItem> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_e1bc918c0fbfc64c960138dd4e1a0695>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_e1bc918c0fbfc64c960138dd4e1a0695>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_0b4be8f23d76cf8f635e8216d48bb365>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_0b4be8f23d76cf8f635e8216d48bb365>
{
  void (__fastcall *memberSetter)(AgeableDefinition *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_f795ce2199669146fcc49b3e01f9b9e8>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_f795ce2199669146fcc49b3e01f9b9e8>
{
  void (__fastcall *memberSetter)(AgeableDefinition *this, const ActorDefinitionFeedItem *);
};

```

### `JsonUtil::addMember::__l2::<lambda_231dfdea537c372b081ccd888ffe656d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_231dfdea537c372b081ccd888ffe656d>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c204e169a15e4c53f6eea8dc02260baa>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c204e169a15e4c53f6eea8dc02260baa>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1321cb8312a2039290aee7e9a5b0ac7d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1321cb8312a2039290aee7e9a5b0ac7d>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_12cf9180955559bceba5435ea1d0f77e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_12cf9180955559bceba5435ea1d0f77e>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c88371319932b6133230e2e2f1c49e34>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c88371319932b6133230e2e2f1c49e34>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_5c40c137359cbf66179c3c70890310ba>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5c40c137359cbf66179c3c70890310ba>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_3e36eedace6ebe0784b3951a1eab6fb3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3e36eedace6ebe0784b3951a1eab6fb3>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_50e1fa1ddb5f9f16e26b32a02bad3979>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_50e1fa1ddb5f9f16e26b32a02bad3979>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ba8a0fb49622601ea16f8b0478a3e303>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ba8a0fb49622601ea16f8b0478a3e303>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_e0d2dd57ccc61acdafb63a098e0eda6f>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_e0d2dd57ccc61acdafb63a098e0eda6f>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_e8348be1cfffa534b45c2b3527ebb103>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_e8348be1cfffa534b45c2b3527ebb103>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_824221d5b60f06073c99bad03c461fea>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_824221d5b60f06073c99bad03c461fea>
{
  void (__fastcall *memberSetter)(BribeableDefinition *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_605fa86b12379e8294b158ed2bc09cd8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_605fa86b12379e8294b158ed2bc09cd8>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_50368f85cc6a91b1c125aeb7c36f7d20>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_50368f85cc6a91b1c125aeb7c36f7d20>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f2559615149efcde20beda6883e9b682>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f2559615149efcde20beda6883e9b682>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_56b1d9b42c427efb85709cddea225aa7>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_56b1d9b42c427efb85709cddea225aa7>
{
  void (__fastcall *memberSetter)(BreedableDefinition *this, const BreedableType *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_143f05fb17ff405d5530114d25ac281b>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_143f05fb17ff405d5530114d25ac281b>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_995a0997d04576917083c040186b995c>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_995a0997d04576917083c040186b995c>
{
  void (__fastcall *memberSetter)(BreedableDefinition *this, const BreedableType *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_fde943fe48ba2e5d27f8f2c2859473e3>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_fde943fe48ba2e5d27f8f2c2859473e3>
{
  void (__fastcall *memberSetter)(BreedableDefinition *this, const EnvironmentRequirement *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_54afd04375b7ebd0ede789af2c0e56b7>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_54afd04375b7ebd0ede789af2c0e56b7>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_01b4cc18a45a786bc7882bd1e53828d5>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_01b4cc18a45a786bc7882bd1e53828d5>
{
  void (__fastcall *memberSetter)(BreedableDefinition *this, const EnvironmentRequirement *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_2b345bd3bc375f513203ac60fb2f3508>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_2b345bd3bc375f513203ac60fb2f3508>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_62526fbd85ecebae2b350b0bd933198e>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_62526fbd85ecebae2b350b0bd933198e>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_43c3de436fcab3c0338fbcbf72abb343>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_43c3de436fcab3c0338fbcbf72abb343>
{
  void (__fastcall *memberSetter)(BreedableDefinition *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_96d8f44be413f6ef3c70f2d7f8dccd64>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_96d8f44be413f6ef3c70f2d7f8dccd64>
{
  DenySameParentsVariantData *__ptr32 member;
  const DenySameParentsVariantData defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_f123274853b3dc9ea5e54cd2ba68f2eb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f123274853b3dc9ea5e54cd2ba68f2eb>
{
  DenySameParentsVariantData *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f1f13c9906c3004400d630070f3bf554>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f1f13c9906c3004400d630070f3bf554>
{
  MutationFactorData *__ptr32 member;
  const MutationFactorData defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_2dd213fb545938f7853d5bc4fe9073f1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2dd213fb545938f7853d5bc4fe9073f1>
{
  MutationFactorData *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_0337e80ed594dc45e5f2ef1ec8c4e4ff>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0337e80ed594dc45e5f2ef1ec8c4e4ff>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_5fba25f7b29ed81efd7980cda9535b9d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5fba25f7b29ed81efd7980cda9535b9d>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6679caaf45aa92c8b19bc0d21db70464>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_6679caaf45aa92c8b19bc0d21db70464>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4954fef871cd1f73a532878d19559fec>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4954fef871cd1f73a532878d19559fec>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_212e76eadecdda321eb33105bbde9c86>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_212e76eadecdda321eb33105bbde9c86>
{
  void (__fastcall *memberSetter)(BreathableDefinition *this, const BlockDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_519b67c469b02ec18efcff4d3aa17265>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_519b67c469b02ec18efcff4d3aa17265>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_a0c77b53c964e02518cee9f191b859ab>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_a0c77b53c964e02518cee9f191b859ab>
{
  void (__fastcall *memberSetter)(BreathableDefinition *this, const BlockDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_85431181bbe495fa23f5380b3f53fe71>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_85431181bbe495fa23f5380b3f53fe71>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_cc2c0147ee34bdd0624aff1251c151b0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cc2c0147ee34bdd0624aff1251c151b0>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_df59f320194769daf4d2f5d24d61bc8d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_df59f320194769daf4d2f5d24d61bc8d>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_a51f0411845a86dfa3b1608bee42e21c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a51f0411845a86dfa3b1608bee42e21c>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a5e0513f616c421320a9151a4eb18668>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a5e0513f616c421320a9151a4eb18668>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6c712f215d0287bb24c780c1a7085e73>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6c712f215d0287bb24c780c1a7085e73>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_30e43eec027774ac157cb4c78ed88962>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_30e43eec027774ac157cb4c78ed88962>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_f67c204b5f47b93f9db2c87ab7e85bb5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f67c204b5f47b93f9db2c87ab7e85bb5>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_cbc28905cc027a21dbcc449347fb7dff>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_cbc28905cc027a21dbcc449347fb7dff>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_bc342fe12c25c8e562ded013e41e3c2c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_bc342fe12c25c8e562ded013e41e3c2c>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d1cba4ca802030aa8f1a5831a652d66c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d1cba4ca802030aa8f1a5831a652d66c>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_8dca989e87dd1dc4cc0d0353de0409c7>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_8dca989e87dd1dc4cc0d0353de0409c7>
{
  std::vector<BoostItem> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_fdca226cf9abce368e2d1831b8b57106>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_fdca226cf9abce368e2d1831b8b57106>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_91fa21e653cc7aa3ca1201faa1f15810>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_91fa21e653cc7aa3ca1201faa1f15810>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e8c0fe5d06cbe125832a2048d55378a2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e8c0fe5d06cbe125832a2048d55378a2>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_409da2f8fc1cab80bfee61d9b7ba556f>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_409da2f8fc1cab80bfee61d9b7ba556f>
{
  std::vector<BlockListEventMap> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_233352280baf31d19dc455bd51ec7da4>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_233352280baf31d19dc455bd51ec7da4>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_d269dc0d65db53c1e08206ee3b090e63>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d269dc0d65db53c1e08206ee3b090e63>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6b179afa1582b23fe416c7ae258f2d50>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6b179afa1582b23fe416c7ae258f2d50>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_350b46388a0cd000144d5a4861a52b11>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_350b46388a0cd000144d5a4861a52b11>
{
  Vec3 *__ptr32 member;
  const Vec3 defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c2f66596332ef5810b94f5c3926267d7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c2f66596332ef5810b94f5c3926267d7>
{
  Vec3 *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_77f1ef8e9f8e38cbd065f000cada1f5b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_77f1ef8e9f8e38cbd065f000cada1f5b>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_06b9d7328c4f1bb91f4d0410bcacb242>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_06b9d7328c4f1bb91f4d0410bcacb242>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_7ceac62be2887d6eefdae71b5262aac5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7ceac62be2887d6eefdae71b5262aac5>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8ca3b006e0d76d669c113c1eef4fc0a2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8ca3b006e0d76d669c113c1eef4fc0a2>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_0459a3784f05c7ff68f1b665aa42d40f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0459a3784f05c7ff68f1b665aa42d40f>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_0e16ef2dd8193ca56f1084684c4d30c9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0e16ef2dd8193ca56f1084684c4d30c9>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d5dfff98678dc2c0a2ae73951741fea5>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d5dfff98678dc2c0a2ae73951741fea5>
{
  void (__fastcall *memberSetter)(BoostItem *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_18bf929e7c40bb25265f365aacbafc5b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_18bf929e7c40bb25265f365aacbafc5b>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_214dbb2045f6a865b34be8201af3e155>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_214dbb2045f6a865b34be8201af3e155>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_eed5faa1871a60626a087f65b7e7bf6b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_eed5faa1871a60626a087f65b7e7bf6b>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c3656616c585c4528ec6f42158ab8a9c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c3656616c585c4528ec6f42158ab8a9c>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_3b326e4591c509794bab9e6ef621acc4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3b326e4591c509794bab9e6ef621acc4>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_30670819399ee85ba0eeca06cdef7a95>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_30670819399ee85ba0eeca06cdef7a95>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e19d218d7a3d1ea2bffeafc4e636227e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e19d218d7a3d1ea2bffeafc4e636227e>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_4af618010d3b5e8bfe831b25e651c309>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_4af618010d3b5e8bfe831b25e651c309>
{
  void (__fastcall *memberSetter)(EnvironmentRequirement *this, const BlockDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_aa07fa59abb78fb11d2d8462a6f1c83b>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_aa07fa59abb78fb11d2d8462a6f1c83b>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d3b3637bb5b8eeb6202ba86846c4b8b4>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d3b3637bb5b8eeb6202ba86846c4b8b4>
{
  void (__fastcall *memberSetter)(EnvironmentRequirement *this, const BlockDescriptor *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_bc55a3393100382f340ab96f71647b12>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_bc55a3393100382f340ab96f71647b12>
{
  void (__fastcall *memberSetter)(EnvironmentRequirement *this, const BlockDescriptor *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_5b8a6dde06cdfb19d31790d9057a1d94>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_5b8a6dde06cdfb19d31790d9057a1d94>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_84796c7dc242233190a4ab364195a69b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_84796c7dc242233190a4ab364195a69b>
{
  void (__fastcall *memberSetter)(EnvironmentRequirement *this, const BlockDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_d98ad5ef31c94346b5b7102e04e23081>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_d98ad5ef31c94346b5b7102e04e23081>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_eb8ff86a7c46326edd1e4895e5c9d89d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_eb8ff86a7c46326edd1e4895e5c9d89d>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f425fba5252cb98a2ff937c43890f62a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f425fba5252cb98a2ff937c43890f62a>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_3678339c43a61a7049e5a667184812be>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3678339c43a61a7049e5a667184812be>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_9b40b363345a79d0ef635df90b4fdff9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9b40b363345a79d0ef635df90b4fdff9>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2c0766aafb53186f4171573807c89612>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_2c0766aafb53186f4171573807c89612>
{
  void (__fastcall *memberSetter)(ExperienceRewardDefinition *this, const ExpressionNode *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_e404a180f3048ddcc102cf1f02fd13b8>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_e404a180f3048ddcc102cf1f02fd13b8>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_ca50fd071e34a8e06bfd3826dc07f1c4>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_ca50fd071e34a8e06bfd3826dc07f1c4>
{
  void (__fastcall *memberSetter)(ExperienceRewardDefinition *this, const ExpressionNode *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_b08fe1c5d1831debdcc5d135b1ffc8ee>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_b08fe1c5d1831debdcc5d135b1ffc8ee>
{
  std::vector<SlotDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_c3218bd1d9207d1f86179fd466962c8c>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_c3218bd1d9207d1f86179fd466962c8c>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d9cb2c6f905e751d04de0fd56ed7f6f8>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d9cb2c6f905e751d04de0fd56ed7f6f8>
{
  void (__fastcall *memberSetter)(EnvironmentSensorDefinition *this, const DefinitionTrigger *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_8b1e26123a39d6155ed7c8070411f8cd>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_8b1e26123a39d6155ed7c8070411f8cd>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e177078676b6b7b94b1dd17e1c41c894>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e177078676b6b7b94b1dd17e1c41c894>
{
  void (__fastcall *memberSetter)(EnvironmentSensorDefinition *this, const DefinitionTrigger *);
};

```

### `JsonUtil::addMember::__l2::<lambda_68b28af33e63b6832228596294febb71>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_68b28af33e63b6832228596294febb71>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_fb3a81e5d35fea049e778902f138ebff>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fb3a81e5d35fea049e778902f138ebff>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6279886ca2d170a883c1a66d1337b9d2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6279886ca2d170a883c1a66d1337b9d2>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_1f139437ae901a97c38665eb334ee959>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1f139437ae901a97c38665eb334ee959>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_bb923812e53bb57a05a9f1f2f0f46e69>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_bb923812e53bb57a05a9f1f2f0f46e69>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_f240bf12c998bb9368bdb21f932719e1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f240bf12c998bb9368bdb21f932719e1>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d115886b02c1f0a5fd60ffcacd174114>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d115886b02c1f0a5fd60ffcacd174114>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_a7528fe51aca94eda5b578362b902a7e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a7528fe51aca94eda5b578362b902a7e>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_b92e4625310892fe4614aab1ecba2289>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_b92e4625310892fe4614aab1ecba2289>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_ef35ed17236ce0e9c2fba619e6b58663>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ef35ed17236ce0e9c2fba619e6b58663>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_467af11cd64388fe3986b9dbbe865522>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_467af11cd64388fe3986b9dbbe865522>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_266730ecf4e559626e7484eb4d5ea512>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_266730ecf4e559626e7484eb4d5ea512>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c8e86985f6380579347049d5224a8abb>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_c8e86985f6380579347049d5224a8abb>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9e45c67b713c1cc8d6db78ba7399ddda>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9e45c67b713c1cc8d6db78ba7399ddda>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_e1578c7d4df83c7baa83238e64791f67>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e1578c7d4df83c7baa83238e64791f67>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_a749a1f410efee2a3624766505037e71>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_a749a1f410efee2a3624766505037e71>
{
  void (__fastcall *memberSetter)(DamageSensorDefinition *this, const DamageSensorTrigger *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_68437bffe64153648cc387e91d44fa3a>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_68437bffe64153648cc387e91d44fa3a>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_b13d516968cb65f0e1e62db4eec5ac96>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_b13d516968cb65f0e1e62db4eec5ac96>
{
  void (__fastcall *memberSetter)(DamageSensorDefinition *this, const DamageSensorTrigger *);
};

```

### `JsonUtil::addMember::__l2::<lambda_fc8909cb96ebb86763cb80d261506a1e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fc8909cb96ebb86763cb80d261506a1e>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e1f99ed0166b398dd200673f4eff40e7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e1f99ed0166b398dd200673f4eff40e7>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_460d02a3db34797308474b63163a9193>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_460d02a3db34797308474b63163a9193>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_8bd1d5436f117a1b9e748af23d1997e2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8bd1d5436f117a1b9e748af23d1997e2>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f63888d741ead9439e939d754900a4a2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f63888d741ead9439e939d754900a4a2>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_e45971fe56f47772ad4681bb28ac39f6>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e45971fe56f47772ad4681bb28ac39f6>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6c691d2594f21ce7276918db53c0d8de>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6c691d2594f21ce7276918db53c0d8de>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7f17170934ec8cca51f394e9b2e75f7a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7f17170934ec8cca51f394e9b2e75f7a>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_15a4ba3a893885aa7d1ab776cde77fd2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_15a4ba3a893885aa7d1ab776cde77fd2>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7d33e1b3ed50b1b9ca9a37b56ba91c0f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7d33e1b3ed50b1b9ca9a37b56ba91c0f>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ccf7fecbbad4621352be2ac3754522eb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ccf7fecbbad4621352be2ac3754522eb>
{
  std::string *__ptr32 member;
  const std::string defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_1b04fc29522a7668c5dce5987a0ce91f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1b04fc29522a7668c5dce5987a0ce91f>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1994375828f44af42b516d4388c8f605>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1994375828f44af42b516d4388c8f605>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_8e60e8159c454cad188eb404f03b996d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8e60e8159c454cad188eb404f03b996d>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_049ed9aff168ea87b93e9557e58080de>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_049ed9aff168ea87b93e9557e58080de>
{
  void (__fastcall *memberSetter)(DamageSensorTrigger *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_ee832c99cbc95ca9b4d41972fc6f2def>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_ee832c99cbc95ca9b4d41972fc6f2def>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_aefe738125cac0b80fad3ec9c61af182>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_aefe738125cac0b80fad3ec9c61af182>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_70c8823af88577a9139f0a5a81c59ae3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_70c8823af88577a9139f0a5a81c59ae3>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_5fe8e6dcc3177312b4cb1f85324e3ec3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5fe8e6dcc3177312b4cb1f85324e3ec3>
{
  std::string *__ptr32 member;
  const std::string defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_bce94d1d882407f63845a49e51f8dadd>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_bce94d1d882407f63845a49e51f8dadd>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6811a2ddcdeac11b62dedbe3bbde26a1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6811a2ddcdeac11b62dedbe3bbde26a1>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_f8337eb2d514e399550c261a478c34a4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f8337eb2d514e399550c261a478c34a4>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_073fbb00c4315a2fb05e427a5980e304>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_073fbb00c4315a2fb05e427a5980e304>
{
  void (__fastcall *memberSetter)(DamageSensorTrigger *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_a01d433d8cb8ee07a9987d7f9b49f49c>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_a01d433d8cb8ee07a9987d7f9b49f49c>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_be9831fdc79d47fcd3ceb30a11f16f2d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_be9831fdc79d47fcd3ceb30a11f16f2d>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c414dece671bf67896ec9ce12544cce0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c414dece671bf67896ec9ce12544cce0>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6fd36c93cd060c6f03f4f912f35301ea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6fd36c93cd060c6f03f4f912f35301ea>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6de5d1f8d1cb8e165b1a55eaf7b704d0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6de5d1f8d1cb8e165b1a55eaf7b704d0>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_28aaa0379fab7a6cb359a29a1e4c3aac>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_28aaa0379fab7a6cb359a29a1e4c3aac>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_656acebfa4ead926c774c616a675318e>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_656acebfa4ead926c774c616a675318e>
{
  void (__fastcall *memberSetter)(SlotDescriptor *this, const ItemDescriptor *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_6aadbcaa9e0837bb6116474e8247e68f>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_6aadbcaa9e0837bb6116474e8247e68f>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_6708a2f0a38bff77c4b6a58feb78f509>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_6708a2f0a38bff77c4b6a58feb78f509>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_708a7e741962a2b9561e494735fca4cb>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_708a7e741962a2b9561e494735fca4cb>
{
  void (__fastcall *memberSetter)(SlotDescriptor *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_0a50b2105c02db2d831574bdce65b139>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0a50b2105c02db2d831574bdce65b139>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_594b5b841949228b28102969a91d487a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_594b5b841949228b28102969a91d487a>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7c7678990c397bbe6afd26b27843816d>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7c7678990c397bbe6afd26b27843816d>
{
  void (__fastcall *memberSetter)(HurtOnConditionDefinition *this, const DamageCondition *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_58ce0156d492bc4fa6880bbf56287be0>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_58ce0156d492bc4fa6880bbf56287be0>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_9b46ab2da50e578079b5339526ae7820>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_9b46ab2da50e578079b5339526ae7820>
{
  void (__fastcall *memberSetter)(HurtOnConditionDefinition *this, const DamageCondition *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_b72f1d381c5ac4f563b7f401ccd829a0>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_b72f1d381c5ac4f563b7f401ccd829a0>
{
  std::vector<std::string> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_6d6fa9c79c74c1f98dd373d81bb47d5a>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_6d6fa9c79c74c1f98dd373d81bb47d5a>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_741bbf2cf96624cfaac0abf62d824e25>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_741bbf2cf96624cfaac0abf62d824e25>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9fa950c4100979ce6ef3dc8b6abb7d4a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9fa950c4100979ce6ef3dc8b6abb7d4a>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_503655a079d620642bda2d472a84ddaa>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_503655a079d620642bda2d472a84ddaa>
{
  void (__fastcall *memberSetter)(HitboxDefinition *this, const HitboxJson *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_e8fbdd0ad7ff0d6b209a9a4b895d4547>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_e8fbdd0ad7ff0d6b209a9a4b895d4547>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_ba52b69b69746df40063e3d3ce5e620e>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_ba52b69b69746df40063e3d3ce5e620e>
{
  void (__fastcall *memberSetter)(HitboxDefinition *this, const HitboxJson *);
};

```

### `JsonUtil::addMember::__l2::<lambda_c25abae0a349b6b7ed3ce784d5c5f8f9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c25abae0a349b6b7ed3ce784d5c5f8f9>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7fc529560292eb880c1d2bf4d16dc001>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_7fc529560292eb880c1d2bf4d16dc001>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c002bca4a6be51d08a90013de6ff8efc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c002bca4a6be51d08a90013de6ff8efc>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1377fa7d6b81fb8d114cd1735e561ce1>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1377fa7d6b81fb8d114cd1735e561ce1>
{
  void (__fastcall *memberSetter)(HealableDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_9e2c6c0d608c432c1d05cfa6f0446180>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_9e2c6c0d608c432c1d05cfa6f0446180>
{
  std::vector<FeedItem> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_41eb388932b5ec81369a171523967072>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_41eb388932b5ec81369a171523967072>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e35593b75e27aa09460f24db447f9435>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e35593b75e27aa09460f24db447f9435>
{
  void (__fastcall *memberSetter)(HealableDefinition *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2edd177b1f7df763313b1d8fc472a016>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_2edd177b1f7df763313b1d8fc472a016>
{
  void (__fastcall *memberSetter)(HealableDefinition *this, const FeedItem *);
};

```

### `JsonUtil::addMember::__l2::<lambda_7f22105d3d965f11cd7b200c92638c69>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7f22105d3d965f11cd7b200c92638c69>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6cb3f7cb1e7c1d7ea98bb7bf3681ae3f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6cb3f7cb1e7c1d7ea98bb7bf3681ae3f>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c1a40fa0d2e9c27bae085f651a2d66db>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c1a40fa0d2e9c27bae085f651a2d66db>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_080a259d2dd777a9eb8ed424b166cbce>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_080a259d2dd777a9eb8ed424b166cbce>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_e99e0330d171593271ab89e9b3ff983e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e99e0330d171593271ab89e9b3ff983e>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_055ff747ff0564fce823af28740ce572>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_055ff747ff0564fce823af28740ce572>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_9f8281a2ecc968afd9d443519ff157bf>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_9f8281a2ecc968afd9d443519ff157bf>
{
  void (__fastcall *memberSetter)(GiveableDefinition *this, const GiveableTrigger *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_c1f5cb00f48b6b4fb93648b56233fc57>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_c1f5cb00f48b6b4fb93648b56233fc57>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7da7a7c0a2429adaadbf668c0aca4c1a>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7da7a7c0a2429adaadbf668c0aca4c1a>
{
  void (__fastcall *memberSetter)(GiveableDefinition *this, const GiveableTrigger *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_a5396dc6f6c0b8880821058434fadab3>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_a5396dc6f6c0b8880821058434fadab3>
{
  void (__fastcall *memberSetter)(GeneticsDefinition *this, const GeneDefinition *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_e6db5d551c2e1e37cca2446fb7e38285>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_e6db5d551c2e1e37cca2446fb7e38285>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_15b9abb1d9327bab07974f79e0ef89c5>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_15b9abb1d9327bab07974f79e0ef89c5>
{
  void (__fastcall *memberSetter)(GeneticsDefinition *this, const GeneDefinition *);
};

```

### `JsonUtil::addMember::__l2::<lambda_34d0f07789365dce0e37a3b80d25eb95>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_34d0f07789365dce0e37a3b80d25eb95>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_aa63d1dde43996484dd17cb4efbda88f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_aa63d1dde43996484dd17cb4efbda88f>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_10072e99e1d897ad7aa381c611b59f8f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_10072e99e1d897ad7aa381c611b59f8f>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_525f72b56babc9d0c85d924b0a46ddc0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_525f72b56babc9d0c85d924b0a46ddc0>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_3d69ee4221d1214166a439fdaa580e7d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3d69ee4221d1214166a439fdaa580e7d>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4cd5a0794b7ad3b01ed64b999a5fddac>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4cd5a0794b7ad3b01ed64b999a5fddac>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_309168c90af2c5cb64ae415a36f749dd>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_309168c90af2c5cb64ae415a36f749dd>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e9545c30c0136a91fc16861c4a7ae860>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e9545c30c0136a91fc16861c4a7ae860>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7ba1efcea9e716004eff787a20784610>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7ba1efcea9e716004eff787a20784610>
{
  void (__fastcall *memberSetter)(GeneDefinition *this, const GeneticVariant *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_310b7651784245acd0b4d0766bce6af8>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_310b7651784245acd0b4d0766bce6af8>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e0e1688ae98405f6ed3492feb987a769>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e0e1688ae98405f6ed3492feb987a769>
{
  void (__fastcall *memberSetter)(GeneDefinition *this, const GeneticVariant *);
};

```

### `JsonUtil::addMember::__l2::<lambda_f4eccf3521cd8128e6fbc657af9482e7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f4eccf3521cd8128e6fbc657af9482e7>
{
  IntRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_95bad0436558ce01cc9e6e79dd18e6fc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_95bad0436558ce01cc9e6e79dd18e6fc>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_dc4543b1e151c6b9d49f6fcc88d9bc62>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_dc4543b1e151c6b9d49f6fcc88d9bc62>
{
  void (__fastcall *memberSetter)(GeneDefinition *this, const GeneticVariant *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_576c57ec55f345034ae1a2c0aee22f1d>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_576c57ec55f345034ae1a2c0aee22f1d>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_8ae206540332343f812490f9c95f3a77>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_8ae206540332343f812490f9c95f3a77>
{
  void (__fastcall *memberSetter)(GeneDefinition *this, const GeneticVariant *);
};

```

### `JsonUtil::addMember::__l2::<lambda_c05dcc421335f57ca33e22e434c6d566>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c05dcc421335f57ca33e22e434c6d566>
{
  IntRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_04f5940c40241e67595b01ccfdc97dfd>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_04f5940c40241e67595b01ccfdc97dfd>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_466a8d0b1ea1b646b230fb7da714d0b4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_466a8d0b1ea1b646b230fb7da714d0b4>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_dcbdcc71b0ea0197aea293f0fa12b9e3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_dcbdcc71b0ea0197aea293f0fa12b9e3>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_991d1c6fb83b26b7d56f6defbf44cc4b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_991d1c6fb83b26b7d56f6defbf44cc4b>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_8625b46f28fa3665eceab320d10f1679>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_8625b46f28fa3665eceab320d10f1679>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_f63ea75e102bd38f70e9727b29ebeb59>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_f63ea75e102bd38f70e9727b29ebeb59>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_146c802b5771626907855610e67b50ad>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_146c802b5771626907855610e67b50ad>
{
  void (__fastcall *memberSetter)(GiveableTrigger *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMember::__l2::<lambda_52ceb35a4cecae112c8d5ba0e9e2174d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_52ceb35a4cecae112c8d5ba0e9e2174d>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_1461e14e156597f1e5d3e6ffcc5b30b7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1461e14e156597f1e5d3e6ffcc5b30b7>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_2481c8c4d02d9380f596915ff6c29518>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2481c8c4d02d9380f596915ff6c29518>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_ec6de8015426d88090878f738773794b>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_ec6de8015426d88090878f738773794b>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_4058b29188297270b6d725ba5e5f7151>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_4058b29188297270b6d725ba5e5f7151>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_13e5dd2b4bf40c22b8652f0a6a613122>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_13e5dd2b4bf40c22b8652f0a6a613122>
{
  void (__fastcall *memberSetter)(GiveableTrigger *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2ef24a34b3b147a36e8f545aaa128de1>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_2ef24a34b3b147a36e8f545aaa128de1>
{
  void (__fastcall *memberSetter)(FeedItem *this, const FeedItem::Effect *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_f719b919e6726131586968baf8398cad>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_f719b919e6726131586968baf8398cad>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2d741018b12d0c0b2fce0aef63339138>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_2d741018b12d0c0b2fce0aef63339138>
{
  void (__fastcall *memberSetter)(FeedItem *this, const FeedItem::Effect *);
};

```

### `JsonUtil::addMember::__l2::<lambda_218c3219c208091cc2a80734dca0d2d4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_218c3219c208091cc2a80734dca0d2d4>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_2ec8496e4fdb5bc1fbf2899118405341>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2ec8496e4fdb5bc1fbf2899118405341>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c6f055dd25023dc04afd9711135068a5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c6f055dd25023dc04afd9711135068a5>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_ca8450075fb88fbe8100cebfdbdbb324>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_ca8450075fb88fbe8100cebfdbdbb324>
{
  void (__fastcall *memberSetter)(FeedItem *this, const FeedItem::Effect *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_9635c99ef13d4d4866f4a2d61238f050>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_9635c99ef13d4d4866f4a2d61238f050>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_427207befa9e22baefa738ecf4c8b45b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_427207befa9e22baefa738ecf4c8b45b>
{
  void (__fastcall *memberSetter)(FeedItem *this, const FeedItem::Effect *);
};

```

### `JsonUtil::addMember::__l2::<lambda_9f0392ea268b7f2181b47147909add8b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9f0392ea268b7f2181b47147909add8b>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_d0266d57bbc1d8734b08779d0c2e1c43>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d0266d57bbc1d8734b08779d0c2e1c43>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f1b0394491693ce707792c1ef18bed93>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f1b0394491693ce707792c1ef18bed93>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8772c6e9ca3ed7daa29eea9aac25857f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8772c6e9ca3ed7daa29eea9aac25857f>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_9315f5c7d1e13137f728be4efe1b06a5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9315f5c7d1e13137f728be4efe1b06a5>
{
  Vec3 *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_11d659b795ad0d89b7990f6ea389f9a6>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_11d659b795ad0d89b7990f6ea389f9a6>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_28f9dd9cf584ec6aa2442cbba0ed553b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_28f9dd9cf584ec6aa2442cbba0ed553b>
{
  Vec3 *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_16fcd46562031763ce346c20bf76c621>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_16fcd46562031763ce346c20bf76c621>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_db72967ba92a4f2e4a03e5e21b05cd8d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_db72967ba92a4f2e4a03e5e21b05cd8d>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a389151d68fb7403e3c358060ef15b71>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a389151d68fb7403e3c358060ef15b71>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c7ed1c2f66f18e8a9e5782ff85241439>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c7ed1c2f66f18e8a9e5782ff85241439>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_49aec17937301af82da6099f29d54608>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_49aec17937301af82da6099f29d54608>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c72910d91ebd9e6e170d9b6c012c36c5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c72910d91ebd9e6e170d9b6c012c36c5>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f5e1cb8ce3528ab9d435c5775def8cd9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f5e1cb8ce3528ab9d435c5775def8cd9>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8afa64cc8b2ff54ea4488847959b4a46>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8afa64cc8b2ff54ea4488847959b4a46>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_635187f8f5cb94d0e5bde26ee7bb3e06>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_635187f8f5cb94d0e5bde26ee7bb3e06>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_ecba698c3d1afb55a08349cc41eb9580>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ecba698c3d1afb55a08349cc41eb9580>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_cccd33c1ee61bbf8307e0e43c15c82b4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cccd33c1ee61bbf8307e0e43c15c82b4>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_7f1c7724010053e1ea2e837d54ca81a8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7f1c7724010053e1ea2e837d54ca81a8>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7fd3cb674dddb2f63a7c3f0fac2f12c0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7fd3cb674dddb2f63a7c3f0fac2f12c0>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_b058e71fb173a60cd9b0e1672af5361a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_b058e71fb173a60cd9b0e1672af5361a>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6d921c5c458702eab54f53937b19a149>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6d921c5c458702eab54f53937b19a149>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_849e03ad676cced0f50b89801946e37d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_849e03ad676cced0f50b89801946e37d>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_3af838411e6691ad3ead73df5401e2eb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3af838411e6691ad3ead73df5401e2eb>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9dd10f8f5f2fc15863c1faf9ad7e6479>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9dd10f8f5f2fc15863c1faf9ad7e6479>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_820600a5ae73bda3ef6731b37225a173>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_820600a5ae73bda3ef6731b37225a173>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_43477919977b9bf65db788d2d6054a8a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_43477919977b9bf65db788d2d6054a8a>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d4aa58b37b5c0859479dcbdea9ee2751>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d4aa58b37b5c0859479dcbdea9ee2751>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_94a06d3d642c1e6d2804c8e02f08a64d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_94a06d3d642c1e6d2804c8e02f08a64d>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_317859d0a12e8dcfc64133ec87f434ae>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_317859d0a12e8dcfc64133ec87f434ae>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_d06dca2af9fc6250aee70cded45e65ea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d06dca2af9fc6250aee70cded45e65ea>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1839d766ac1fd42873a7d339e8fd08aa>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1839d766ac1fd42873a7d339e8fd08aa>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7fffa91556d0cf7329361ed1862a955d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7fffa91556d0cf7329361ed1862a955d>
{
  IntRange *__ptr32 member;
  const IntRange defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_bf1b6075645d6d295ebb1696108c3c0e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_bf1b6075645d6d295ebb1696108c3c0e>
{
  IntRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_de970443d8c5946d19526a0d0651882f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_de970443d8c5946d19526a0d0651882f>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ddab10aafe26173ec5322ef6f60570c2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ddab10aafe26173ec5322ef6f60570c2>
{
  IntRange *__ptr32 member;
  const IntRange defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_2c09240e11dbfdea4382e7ac9afc3288>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2c09240e11dbfdea4382e7ac9afc3288>
{
  IntRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_531d3320a48bb4f313dc77502b622157>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_531d3320a48bb4f313dc77502b622157>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1b31f14fe5549162d3a0f7b73e71a2f9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1b31f14fe5549162d3a0f7b73e71a2f9>
{
  IntRange *__ptr32 member;
  const IntRange defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_629c507dc5f5d955668e9eca198b8179>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_629c507dc5f5d955668e9eca198b8179>
{
  IntRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_fe664a85132b57e4aa6d6b476e8f360c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fe664a85132b57e4aa6d6b476e8f360c>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_3b188eb3584ad7c08e6eaede9cc6c712>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3b188eb3584ad7c08e6eaede9cc6c712>
{
  IntRange *__ptr32 member;
  const IntRange defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e6d8be54dc0bc2ddbded81f0298beca7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e6d8be54dc0bc2ddbded81f0298beca7>
{
  IntRange *__ptr32 member;
};

```

### `JumpControl`
```
struct __cppobj JumpControl : Control
{
};

```

### `JumpControl_vtbl`
```
struct /*VFT*/ JumpControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(JumpControl *this, Mob *, JumpControlDescription *);
  void (__fastcall *tick)(JumpControl *this, JumpControlComponent *, Mob *);
  int (__fastcall *getJumpDelay)(JumpControl *this, const JumpControlComponent *, const Mob *);
  float (__fastcall *getJumpPower)(JumpControl *this, const JumpControlComponent *, const Mob *);
  JumpType (__fastcall *getJumpType)(JumpControl *this, const JumpControlComponent *, const Mob *);
  void (__fastcall *setJumpType)(JumpControl *this, JumpControlComponent *, Mob *, JumpType);
  void (__fastcall *resetSpeedModifier)(JumpControl *this, const JumpControlComponent *, Mob *);
};

```

### `JsonUtil::addMember::__l2::<lambda_4e64cd76c7046492adff67a525e89a01>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4e64cd76c7046492adff67a525e89a01>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6856523d512524e2ad823b86488e7ce8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6856523d512524e2ad823b86488e7ce8>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ab5a693ad799682c019f44a6fea3eed5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ab5a693ad799682c019f44a6fea3eed5>
{
  ItemDescriptor *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_25856943838bbb2fb249a5f8aec59dea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_25856943838bbb2fb249a5f8aec59dea>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_733128d84699ee0607812f3f712815ad>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_733128d84699ee0607812f3f712815ad>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_252566057f93177952a6e6eb620e422c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_252566057f93177952a6e6eb620e422c>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_85392500b1e75796d63ca021389dbab9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_85392500b1e75796d63ca021389dbab9>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8b952c5edfbd2920510f67a3629c1649>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8b952c5edfbd2920510f67a3629c1649>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_2afd9e243f0c4aef863837945fa75d5a>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_2afd9e243f0c4aef863837945fa75d5a>
{
  void (__fastcall *memberSetter)(MobEffectDefinition *this, const int *);
  const int defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_5e46ca5f3f7c64fb92e8ff314c1c8784>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_5e46ca5f3f7c64fb92e8ff314c1c8784>
{
  void (__fastcall *memberSetter)(MobEffectDefinition *this, const int *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_cd6509c1bb0427d693a9cedb8dfc3557>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_cd6509c1bb0427d693a9cedb8dfc3557>
{
  void (__fastcall *memberSetter)(MobEffectDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_f4dff2b1b6ecc01664dd3bab29a40db1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f4dff2b1b6ecc01664dd3bab29a40db1>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_5860d8af2797b6cf91a3dccb27cb9232>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5860d8af2797b6cf91a3dccb27cb9232>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6097799c871650449256ff476589808d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6097799c871650449256ff476589808d>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c57c0acee5541f1199518e27a0881aa7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c57c0acee5541f1199518e27a0881aa7>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_fe51eb5a2fb7a76fe01ee90de18cb749>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fe51eb5a2fb7a76fe01ee90de18cb749>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_0d19d158399e0a7cbb9e5939518eb32e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0d19d158399e0a7cbb9e5939518eb32e>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9ae918f3a2632a248e84ac0d2e6248b0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9ae918f3a2632a248e84ac0d2e6248b0>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_2d93b24f62779b9894310a32fafd7beb>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_2d93b24f62779b9894310a32fafd7beb>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_5bf062f23fe9480c1e4116be3556c2a4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5bf062f23fe9480c1e4116be3556c2a4>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ce4c37bf47bc94b2a404f890986bef49>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_ce4c37bf47bc94b2a404f890986bef49>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_838bba7c2896982c873b763f8b301036>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_838bba7c2896982c873b763f8b301036>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_58deabb021d760111994dc74edc3b752>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_58deabb021d760111994dc74edc3b752>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_65ae741d9f6eb489206d36f19d37de3e>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_65ae741d9f6eb489206d36f19d37de3e>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4210d0a1ded2bd6d0e26bfee7da11161>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4210d0a1ded2bd6d0e26bfee7da11161>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_31142843aff89b9eff7a60db068d02ea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_31142843aff89b9eff7a60db068d02ea>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_23600ec69a5d186d97625176b824d145>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_23600ec69a5d186d97625176b824d145>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_2c0ec2a1a6c6b95e74843a29bdf9bfff>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2c0ec2a1a6c6b95e74843a29bdf9bfff>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_55b2cb4146fc13ff85fa4ec93c21f36d>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_55b2cb4146fc13ff85fa4ec93c21f36d>
{
  void (__fastcall *memberSetter)(InteractDefinition *this, const Interaction *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_833c06721a80cd8d168c0fa8788d48fe>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_833c06721a80cd8d168c0fa8788d48fe>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_b363fc8114473f918499dff769f9164d>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_b363fc8114473f918499dff769f9164d>
{
  void (__fastcall *memberSetter)(InteractDefinition *this, const Interaction *);
};

```

### `JsonUtil::addMember::__l2::<lambda_0dabaeff15f7ffffffb3e56bdf9eb2fc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0dabaeff15f7ffffffb3e56bdf9eb2fc>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_21f91d203a9ad7d1d12f66b98b6ee242>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_21f91d203a9ad7d1d12f66b98b6ee242>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_af5f097fac42e2ac708e017b83ddbb38>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_af5f097fac42e2ac708e017b83ddbb38>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_85bc13aaa25015ccef06c791c50bc34a>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_85bc13aaa25015ccef06c791c50bc34a>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_50a13dc3c8436a48024fd807eddb0223>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_50a13dc3c8436a48024fd807eddb0223>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_a1016954ee5d933797c3390ec44a2a86>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a1016954ee5d933797c3390ec44a2a86>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_ae727d992d579b4330478edef91e501c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ae727d992d579b4330478edef91e501c>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_2561c26ae1082428a2e5c0691e989063>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_2561c26ae1082428a2e5c0691e989063>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_23d3455772cd9330b90af9b34da3f2ce>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_23d3455772cd9330b90af9b34da3f2ce>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_34968260ea9373337c0680d7b28111bd>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_34968260ea9373337c0680d7b28111bd>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_ebc2c540ee68c809516761b872c0b8db>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ebc2c540ee68c809516761b872c0b8db>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_349021d3d29daaad89215c0851391287>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_349021d3d29daaad89215c0851391287>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_9308687a8f4f3ee1eb262254b4a2aabb>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_9308687a8f4f3ee1eb262254b4a2aabb>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_5036352f64623ddfae952e5876d1aace>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5036352f64623ddfae952e5876d1aace>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_63b4833bdcba7b558cb17e5b8bf30f11>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_63b4833bdcba7b558cb17e5b8bf30f11>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_9480ad70c2fcdb560f033c9017558097>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_9480ad70c2fcdb560f033c9017558097>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_054bd70d7b9e8550e77972714ae1cccb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_054bd70d7b9e8550e77972714ae1cccb>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_cd25d8ba1d535674a7d0292eed38e0d8>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_cd25d8ba1d535674a7d0292eed38e0d8>
{
  void (__fastcall *memberSetter)(Interaction *this, const float *);
  const float defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_bd2cddb04a80729e7a1d44068861a720>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_bd2cddb04a80729e7a1d44068861a720>
{
  void (__fastcall *memberSetter)(Interaction *this, const float *);
};

```

### `JsonUtil::addMember::__l2::<lambda_36a474b05d8b36ac7a094248328906c5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_36a474b05d8b36ac7a094248328906c5>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_4b8123afda2c5d32bcdaddce0d052673>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_4b8123afda2c5d32bcdaddce0d052673>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_3b86ee8982b7ae450b46d68a0ed05981>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_3b86ee8982b7ae450b46d68a0ed05981>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_960619ef9d52a43ae3793ad874eb8651>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_960619ef9d52a43ae3793ad874eb8651>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_36ee21d0c549e35ae8f050b59c9eafa2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_36ee21d0c549e35ae8f050b59c9eafa2>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_de0a7a0dda88266cb5afdbef536bb586>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_de0a7a0dda88266cb5afdbef536bb586>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4a74acbf9e0a14314df887e8087bd5eb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4a74acbf9e0a14314df887e8087bd5eb>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_3c5c8a29a6f1998820451cad79098e14>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_3c5c8a29a6f1998820451cad79098e14>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_9965021a6afbbdd6ee47156d43e2b746>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9965021a6afbbdd6ee47156d43e2b746>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_2e94a9bbfbffeba57f9d9532240ba690>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2e94a9bbfbffeba57f9d9532240ba690>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_4bba8fecc09d1d75ef041801d2d90011>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_4bba8fecc09d1d75ef041801d2d90011>
{
  void (__fastcall *memberSetter)(Interaction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_584f82751f35340cc6c6e9b27cad4bc0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_584f82751f35340cc6c6e9b27cad4bc0>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_0888bf08fe80f730c3a4d2e1573b2a49>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0888bf08fe80f730c3a4d2e1573b2a49>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_58fe8f6772cdadcdb437ed94c6e6e0a4>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_58fe8f6772cdadcdb437ed94c6e6e0a4>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_26e2753c4937c6e539a8246de85b9d19>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_26e2753c4937c6e539a8246de85b9d19>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_5e5c9258e8a905f882eeb7673ea3c850>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_5e5c9258e8a905f882eeb7673ea3c850>
{
  void (__fastcall *memberSetter)(Interaction *this, const float *);
  const float defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_95783c751b453e7c7481792b16f4bf20>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_95783c751b453e7c7481792b16f4bf20>
{
  void (__fastcall *memberSetter)(Interaction *this, const float *);
};

```

### `JsonUtil::addMember::__l2::<lambda_aef2e24cf403904c95d1a77406ff6ac1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_aef2e24cf403904c95d1a77406ff6ac1>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7478041caad17a9a22bcc09378e23e8a>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_7478041caad17a9a22bcc09378e23e8a>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_1065f4dd0194c00d32d117671bba245e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1065f4dd0194c00d32d117671bba245e>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_60f949d5fb908e11c9ecce26d3d2e36f>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_60f949d5fb908e11c9ecce26d3d2e36f>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c4b050cc266c36b6e141194fe5780c4b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c4b050cc266c36b6e141194fe5780c4b>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_33ed8fc256e016b0b4b69a142981fc39>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_33ed8fc256e016b0b4b69a142981fc39>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a826c2428dec2bce1392b7b618a65141>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_a826c2428dec2bce1392b7b618a65141>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_69bfec33327ba0818de9320b08cb544c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_69bfec33327ba0818de9320b08cb544c>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_414b46505ee3a657293c63caf3abaee0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_414b46505ee3a657293c63caf3abaee0>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1e9ea9ec719d142d352665916ad47636>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1e9ea9ec719d142d352665916ad47636>
{
  void (__fastcall *memberSetter)(NameableDefinition *this, const NameAction *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_f48266fd5b370776b2e3e20082571f10>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_f48266fd5b370776b2e3e20082571f10>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_524618b12a302d5c89cb499796334945>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_524618b12a302d5c89cb499796334945>
{
  void (__fastcall *memberSetter)(NameableDefinition *this, const NameAction *);
};

```

### `JsonUtil::addMember::__l2::<lambda_48a73a4b0376921c09c5b33109be839f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_48a73a4b0376921c09c5b33109be839f>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_40fd9129e879665a6b0192d18935dd38>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_40fd9129e879665a6b0192d18935dd38>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_04358e44b0fc053e15b4ed7a2341eb1c>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_04358e44b0fc053e15b4ed7a2341eb1c>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_4042a25cc7803cec3bdbd48accda7878>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_4042a25cc7803cec3bdbd48accda7878>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_02807c4b2ba8fed73604552f2d321c49>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_02807c4b2ba8fed73604552f2d321c49>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_149edb9702b992906e3737377530f630>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_149edb9702b992906e3737377530f630>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_79944877595c303906746d53df7e2ada>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_79944877595c303906746d53df7e2ada>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_855e422163df469e805d91468841b811>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_855e422163df469e805d91468841b811>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_0985f33211ab83dc42d341229de314de>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_0985f33211ab83dc42d341229de314de>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_8423e3a28b8f479d9791fe5d16386b75>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_8423e3a28b8f479d9791fe5d16386b75>
{
  void (__fastcall *memberSetter)(NameAction *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_921edf4bd1f2e333e8628ba6427b08f5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_921edf4bd1f2e333e8628ba6427b08f5>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_abe561704c7e0dac10e326aa32ef9966>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_abe561704c7e0dac10e326aa32ef9966>
{
  void (__fastcall *memberSetter)(TameableDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_a330eb11fc8d356db11a219f265b036a>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_a330eb11fc8d356db11a219f265b036a>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_6c5cb868e967ae5f9c179f06e974d90b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_6c5cb868e967ae5f9c179f06e974d90b>
{
  void (__fastcall *memberSetter)(TameableDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_7cb15bf50fd574722c46a610b9f08ead>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7cb15bf50fd574722c46a610b9f08ead>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_a695578dd65783fa16ad2280b4929dc2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a695578dd65783fa16ad2280b4929dc2>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4654e9ba6ec1ed9330257c4a67efdbb9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4654e9ba6ec1ed9330257c4a67efdbb9>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d6930c5346048b1fc6ed8a8a5e1d8ce0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d6930c5346048b1fc6ed8a8a5e1d8ce0>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_cd8f81f1a054efe90882188620cf3799>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cd8f81f1a054efe90882188620cf3799>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_55e83c3c4bba93f50144acfb9a3ce0fe>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_55e83c3c4bba93f50144acfb9a3ce0fe>
{
  void (__fastcall *memberSetter)(ShooterDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_6bb1cd6a5049feaaa34cbf7225086bfd>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6bb1cd6a5049feaaa34cbf7225086bfd>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_b0c0b68ff8c7967689cd50feaebe2f53>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_b0c0b68ff8c7967689cd50feaebe2f53>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_f3a7cf0e95171ee3394d5d8dbdc62fbb>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_f3a7cf0e95171ee3394d5d8dbdc62fbb>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_cfd9c07871ff2cc9441b1fff121d74a6>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cfd9c07871ff2cc9441b1fff121d74a6>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_a0ebd04b7b80d5f7a693374dde24692b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_a0ebd04b7b80d5f7a693374dde24692b>
{
  void (__fastcall *memberSetter)(ShareableDefinition *this, const Shareable *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_466917e0ffa78cdc0334fbc0cd01ab27>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_466917e0ffa78cdc0334fbc0cd01ab27>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_f0863a80188967b9c6809566bb784225>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_f0863a80188967b9c6809566bb784225>
{
  void (__fastcall *memberSetter)(ShareableDefinition *this, const Shareable *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_fb127a742ce6bd4507d3f5fc9c47494e>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_fb127a742ce6bd4507d3f5fc9c47494e>
{
  void (__fastcall *memberSetter)(ShareableDefinition *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_f34fcf1304a711f77193247269228e45>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_f34fcf1304a711f77193247269228e45>
{
  void (__fastcall *memberSetter)(SchedulerDefinition *this, const float *);
  const float defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_0d4d2dc2133357ecb75d8d029e7b1fb8>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_0d4d2dc2133357ecb75d8d029e7b1fb8>
{
  void (__fastcall *memberSetter)(SchedulerDefinition *this, const float *);
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_1bf5c2de0effa111a83b7a632b42b2d4>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_1bf5c2de0effa111a83b7a632b42b2d4>
{
  std::vector<DefinitionTrigger> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_271b2662609fa04956ce60b3844160bf>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_271b2662609fa04956ce60b3844160bf>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_c733cca285e4011ec19ffa752b61ced7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c733cca285e4011ec19ffa752b61ced7>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_77c07d1de5f7306b57acb77a14a094d6>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_77c07d1de5f7306b57acb77a14a094d6>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d04f360759109d1f7c74d93207e913fb>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d04f360759109d1f7c74d93207e913fb>
{
  void (__fastcall *memberSetter)(RideableDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_0983be73c5e08a40931fde357c021b30>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_0983be73c5e08a40931fde357c021b30>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_52be0f292eb397cc969205b5d7862ebd>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_52be0f292eb397cc969205b5d7862ebd>
{
  void (__fastcall *memberSetter)(RideableDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_36d459b72d1f77def885b3f8c4a1764f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_36d459b72d1f77def885b3f8c4a1764f>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d309a317ab066618e792874f737522f5>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_d309a317ab066618e792874f737522f5>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_078526435b90f4119705249a638d0bca>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_078526435b90f4119705249a638d0bca>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_a3110b29eafb62f60bfe79c674d536d1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a3110b29eafb62f60bfe79c674d536d1>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6dcb18a9d2a2bedd7325d3810db5e4f7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6dcb18a9d2a2bedd7325d3810db5e4f7>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_108f29f3bb559467b551ded0582bf3b2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_108f29f3bb559467b551ded0582bf3b2>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c5bf933e3c5206030151d15f95995cd1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c5bf933e3c5206030151d15f95995cd1>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_729769eb5d1ea3efac18d62b955a837d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_729769eb5d1ea3efac18d62b955a837d>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_951ecf0777063076bc63c7f515a07df3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_951ecf0777063076bc63c7f515a07df3>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_bd95ad84e4ccfb1a6d9b22ce00d1ac95>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_bd95ad84e4ccfb1a6d9b22ce00d1ac95>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_8cfed43906a866208d46d528c935c558>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8cfed43906a866208d46d528c935c558>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_7f0f241741c68981d68ac300b5b3e622>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_7f0f241741c68981d68ac300b5b3e622>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_774cf2b1fa524465134c5047f31739a7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_774cf2b1fa524465134c5047f31739a7>
{
  std::string *__ptr32 member;
  const std::string defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_86e7e5b9592ae35aa5275e297c4bb036>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_86e7e5b9592ae35aa5275e297c4bb036>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_57292b8daf0af33d36fcc5a4b1134331>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_57292b8daf0af33d36fcc5a4b1134331>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_5f87382a6b01c30b2fcaa4e27d94f35a>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_5f87382a6b01c30b2fcaa4e27d94f35a>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_c53617540d05c08fdf0c1fd99a7fe18a>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_c53617540d05c08fdf0c1fd99a7fe18a>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const int *);
  const int defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_3e748983bb036a08953c07de6509d060>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_3e748983bb036a08953c07de6509d060>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const int *);
};

```

### `JsonUtil::addMember::__l2::<lambda_93a04dc376ac843c54743832799348a4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_93a04dc376ac843c54743832799348a4>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c167f45e9565c836a7d0c13991bc6818>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c167f45e9565c836a7d0c13991bc6818>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_97329cc50650dc71d500ade1a1efa358>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_97329cc50650dc71d500ade1a1efa358>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_32e747fcb9829ae35793bb02a054faec>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_32e747fcb9829ae35793bb02a054faec>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_5b298fc7a99bfecadc7783a8183a192e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5b298fc7a99bfecadc7783a8183a192e>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c9f7ab4e225839b23aadefafab6c8721>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c9f7ab4e225839b23aadefafab6c8721>
{
  std::string *__ptr32 member;
  const std::string defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_ec0f27a0d91dbc7c39ae792a5aef9ba6>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ec0f27a0d91dbc7c39ae792a5aef9ba6>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1e44b832139dcb8cdcade6c37d5a1c33>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1e44b832139dcb8cdcade6c37d5a1c33>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const ItemDescriptor *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1c71153a0cc5616f8969818585fd33c5>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1c71153a0cc5616f8969818585fd33c5>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_b741f8afb7bf81b8f78d82fb1dd0840c>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_b741f8afb7bf81b8f78d82fb1dd0840c>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const int *);
  const int defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_7e4c539847bc76105322b95e177c1813>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_7e4c539847bc76105322b95e177c1813>
{
  void (__fastcall *memberSetter)(SpawnActorParameters *this, const int *);
};

```

### `JsonUtil::addMember::__l2::<lambda_cd7cea15c44b700f704f8316675f9a04>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cd7cea15c44b700f704f8316675f9a04>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_f4c5d74cba9f7c10906769461d222439>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_f4c5d74cba9f7c10906769461d222439>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_da1c48cf0929f43f31124094c44b64b8>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_da1c48cf0929f43f31124094c44b64b8>
{
  void (__fastcall *memberSetter)(SeatDescription *this, const ExpressionNode *);
};

```

### `JsonUtil::addMember::__l2::<lambda_730b15e2c6888201917d89716bfcb9ea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_730b15e2c6888201917d89716bfcb9ea>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_feb87ceca7376abcd8f3d0b88f3b7b7e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_feb87ceca7376abcd8f3d0b88f3b7b7e>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_bfa0c352176df206be63b83b3be358d1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_bfa0c352176df206be63b83b3be358d1>
{
  Vec3 *__ptr32 member;
  const Vec3 defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4acee8079fe4d4a817088d99f9722009>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4acee8079fe4d4a817088d99f9722009>
{
  Vec3 *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4d20cf3529fb4d06f67d0d2c383f16f2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4d20cf3529fb4d06f67d0d2c383f16f2>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_77b5231b337f8f341ea94cd03e8496a4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_77b5231b337f8f341ea94cd03e8496a4>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_c4b424ed2a619e0aeb926a5421c1402f>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_c4b424ed2a619e0aeb926a5421c1402f>
{
  void (__fastcall *memberSetter)(SeatDescription *this, const ExpressionNode *);
};

```

### `JsonUtil::addMember::__l2::<lambda_6f1370c98ad821c8c540dd9e24cc81db>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6f1370c98ad821c8c540dd9e24cc81db>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_226534f9758f5808010e60fb3e683656>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_226534f9758f5808010e60fb3e683656>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_56c1a12cd1ad89b132ecde8243a6da2c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_56c1a12cd1ad89b132ecde8243a6da2c>
{
  Vec3 *__ptr32 member;
  const Vec3 defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_d3e91ecbac38452445519541c3ccbd36>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d3e91ecbac38452445519541c3ccbd36>
{
  Vec3 *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_81927ed63080870833807cfaf0bd0585>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_81927ed63080870833807cfaf0bd0585>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_21977c9c296da8660546bcbef096aae2>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_21977c9c296da8660546bcbef096aae2>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_73b5453b8a5b4e1288679eae76cda288>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_73b5453b8a5b4e1288679eae76cda288>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_328dbb14de8da9d902bd25f8f3e16944>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_328dbb14de8da9d902bd25f8f3e16944>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_590ccbc25f2a0cfc03657f5526098a82>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_590ccbc25f2a0cfc03657f5526098a82>
{
  void (__fastcall *memberSetter)(Shareable *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_e196baa6f7d9224aceb3431e227e1d64>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_e196baa6f7d9224aceb3431e227e1d64>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_08da8baee465e52d25b294d3f2bfc2aa>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_08da8baee465e52d25b294d3f2bfc2aa>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_fd09bce24cc4a23620bb014b65531bf3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fd09bce24cc4a23620bb014b65531bf3>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_976f548de3565bc26ec3b8855727bd1d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_976f548de3565bc26ec3b8855727bd1d>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_ced6daeb0bc353303cf3c06246d9ceed>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_ced6daeb0bc353303cf3c06246d9ceed>
{
  void (__fastcall *memberSetter)(Shareable *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_a8bf41bba184ad25a837883ff61a249d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_a8bf41bba184ad25a837883ff61a249d>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_3081e648b8f1d3164cd09ff3d962d4d2>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_3081e648b8f1d3164cd09ff3d962d4d2>
{
  void (__fastcall *memberSetter)(TrustingDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_e8b77becccf9e7a072564f4d45f943c1>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_e8b77becccf9e7a072564f4d45f943c1>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1d7cbd19f9a2b4baa1f2270ab2bb94ed>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1d7cbd19f9a2b4baa1f2270ab2bb94ed>
{
  void (__fastcall *memberSetter)(TrustingDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_ce2d9c7506c36550b1a3a78ffa6752ea>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ce2d9c7506c36550b1a3a78ffa6752ea>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9f9b95a7756376dd01f02826e353597d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9f9b95a7756376dd01f02826e353597d>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_ae4ddfdf5cba85098cd813737ff67bfd>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_ae4ddfdf5cba85098cd813737ff67bfd>
{
  void (__fastcall *memberSetter)(TimerDefinition *this, const WeightChoiceEntry *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_d3c4ced47732a13f4a2c422e4eb6b000>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_d3c4ced47732a13f4a2c422e4eb6b000>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_3b3a702630e74484d78bd25e25bbe0b1>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_3b3a702630e74484d78bd25e25bbe0b1>
{
  DefinitionTrigger *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4fab04c3338e864f44836b29738197a9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4fab04c3338e864f44836b29738197a9>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_5f46b9974b9d301ff3c0b69b386027ea>`
```
struct __cppobj __declspec(align(4)) JsonUtil::addMember::__l2::<lambda_5f46b9974b9d301ff3c0b69b386027ea>
{
  bool *__ptr32 member;
  const bool defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_9dba196f25ca316fe8783ae38c6e4cdc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_9dba196f25ca316fe8783ae38c6e4cdc>
{
  bool *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c112ef30bc1469a8b2ac8d1cbe9c3d80>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c112ef30bc1469a8b2ac8d1cbe9c3d80>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_05311912c851e60e7fa0d2914f7296e9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_05311912c851e60e7fa0d2914f7296e9>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_4906a4d1cab7efa152b6cb40093c3d33>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4906a4d1cab7efa152b6cb40093c3d33>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_61f25333f8afbc62d1ab8431268cb0f9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_61f25333f8afbc62d1ab8431268cb0f9>
{
  float *__ptr32 member;
};

```

### `JumpControlSystem`
```
struct __cppobj JumpControlSystem : ITickingSystem
{
};

```

### `JumpControlSystem_vtbl`
```
struct /*VFT*/ JumpControlSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `JsonValidator::validate::__l2::ValidationState`
```
struct __cppobj JsonValidator::validate::__l2::ValidationState
{
  const JsonValidator::Property *prop;
  const Json::Value *data;
  const Json::Value *parent;
  bool checkType;
  std::string name;
};

```

### `JsonValidator::generateDocs::__l2::DocumentationState`
```
struct JsonValidator::generateDocs::__l2::DocumentationState
{
  const JsonValidator::Property *prop;
  Json::Value *data;
};

```

### `JsonUtil::details::ChanceInfoIntermediate`
```
struct __cppobj JsonUtil::details::ChanceInfoIntermediate
{
  int mNumerator;
  int mDenominator;
};

```

### `JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_c00f4518ea88fe0e5c41c7be747e2cd9>`
```
struct __cppobj JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_c00f4518ea88fe0e5c41c7be747e2cd9>
{
};

```

### `JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_bed4d6375312bf30181ed42d671fb9c1>`
```
struct __cppobj JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_bed4d6375312bf30181ed42d671fb9c1>
{
};

```

### `JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_f7e610952772b7ca091b62601a8bb9d4>`
```
struct __cppobj JsonUtil::details::_makeChanceInformationSchema::__l2::<lambda_f7e610952772b7ca091b62601a8bb9d4>
{
};

```

### `jpeg_error_mgr`
```
struct jpeg_error_mgr
{
  void (__fastcall *error_exit)(jpeg_common_struct *);
  void (__fastcall *emit_message)(jpeg_common_struct *, int);
  void (__fastcall *output_message)(jpeg_common_struct *);
  void (__fastcall *format_message)(jpeg_common_struct *, char *);
  void (__fastcall *reset_error_mgr)(jpeg_common_struct *);
  int msg_code;
  jpeg_error_mgr::<unnamed_type_msg_parm> msg_parm;
  int trace_level;
  int num_warnings;
  const char *const *jpeg_message_table;
  int last_jpeg_message;
  const char *const *addon_message_table;
  int first_addon_message;
  int last_addon_message;
};

```

### `jvirt_sarray_control`
```
struct jvirt_sarray_control
{
  unsigned __int8 **mem_buffer;
  unsigned int rows_in_array;
  unsigned int samplesperrow;
  unsigned int maxaccess;
  unsigned int rows_in_mem;
  unsigned int rowsperchunk;
  unsigned int cur_start_row;
  unsigned int first_undef_row;
  unsigned __int8 pre_zero;
  unsigned __int8 dirty;
  unsigned __int8 b_s_open;
  jvirt_sarray_control *next;
  backing_store_struct b_s_info;
};

```

### `jvirt_barray_control`
```
struct jvirt_barray_control
{
  __int16 (**mem_buffer)[64];
  unsigned int rows_in_array;
  unsigned int blocksperrow;
  unsigned int maxaccess;
  unsigned int rows_in_mem;
  unsigned int rowsperchunk;
  unsigned int cur_start_row;
  unsigned int first_undef_row;
  unsigned __int8 pre_zero;
  unsigned __int8 dirty;
  unsigned __int8 b_s_open;
  jvirt_barray_control *next;
  backing_store_struct b_s_info;
};

```

### `jpeg_memory_mgr`
```
struct jpeg_memory_mgr
{
  void *(__fastcall *alloc_small)(jpeg_common_struct *, int, unsigned __int64);
  void *(__fastcall *alloc_large)(jpeg_common_struct *, int, unsigned __int64);
  unsigned __int8 **(__fastcall *alloc_sarray)(jpeg_common_struct *, int, unsigned int, unsigned int);
  __int16 (**(__fastcall *alloc_barray)(jpeg_common_struct *, int, unsigned int, unsigned int))[64];
  jvirt_sarray_control *(__fastcall *request_virt_sarray)(jpeg_common_struct *, int, unsigned __int8, unsigned int, unsigned int, unsigned int);
  jvirt_barray_control *(__fastcall *request_virt_barray)(jpeg_common_struct *, int, unsigned __int8, unsigned int, unsigned int, unsigned int);
  void (__fastcall *realize_virt_arrays)(jpeg_common_struct *);
  unsigned __int8 **(__fastcall *access_virt_sarray)(jpeg_common_struct *, jvirt_sarray_control *, unsigned int, unsigned int, unsigned __int8);
  __int16 (**(__fastcall *access_virt_barray)(jpeg_common_struct *, jvirt_barray_control *, unsigned int, unsigned int, unsigned __int8))[64];
  void (__fastcall *free_pool)(jpeg_common_struct *, int);
  void (__fastcall *self_destruct)(jpeg_common_struct *);
  int max_memory_to_use;
  int max_alloc_chunk;
};

```

### `jpeg_progress_mgr`
```
struct jpeg_progress_mgr
{
  void (__fastcall *progress_monitor)(jpeg_common_struct *);
  int pass_counter;
  int pass_limit;
  int completed_passes;
  int total_passes;
};

```

### `jpeg_compress_struct`
```
struct __declspec(align(8)) jpeg_compress_struct
{
  jpeg_error_mgr *err;
  jpeg_memory_mgr *mem;
  jpeg_progress_mgr *progress;
  void *client_data;
  unsigned __int8 is_decompressor;
  int global_state;
  jpeg_destination_mgr *dest;
  unsigned int image_width;
  unsigned int image_height;
  int input_components;
  J_COLOR_SPACE in_color_space;
  long double input_gamma;
  unsigned int scale_num;
  unsigned int scale_denom;
  unsigned int jpeg_width;
  unsigned int jpeg_height;
  int data_precision;
  int num_components;
  J_COLOR_SPACE jpeg_color_space;
  jpeg_component_info *comp_info;
  JQUANT_TBL *quant_tbl_ptrs[4];
  int q_scale_factor[4];
  JHUFF_TBL *dc_huff_tbl_ptrs[4];
  JHUFF_TBL *ac_huff_tbl_ptrs[4];
  unsigned __int8 arith_dc_L[16];
  unsigned __int8 arith_dc_U[16];
  unsigned __int8 arith_ac_K[16];
  int num_scans;
  const jpeg_scan_info *scan_info;
  unsigned __int8 raw_data_in;
  unsigned __int8 arith_code;
  unsigned __int8 optimize_coding;
  unsigned __int8 CCIR601_sampling;
  unsigned __int8 do_fancy_downsampling;
  int smoothing_factor;
  J_DCT_METHOD dct_method;
  unsigned int restart_interval;
  int restart_in_rows;
  unsigned __int8 write_JFIF_header;
  unsigned __int8 JFIF_major_version;
  unsigned __int8 JFIF_minor_version;
  unsigned __int8 density_unit;
  unsigned __int16 X_density;
  unsigned __int16 Y_density;
  unsigned __int8 write_Adobe_marker;
  J_COLOR_TRANSFORM color_transform;
  unsigned int next_scanline;
  unsigned __int8 progressive_mode;
  int max_h_samp_factor;
  int max_v_samp_factor;
  int min_DCT_h_scaled_size;
  int min_DCT_v_scaled_size;
  unsigned int total_iMCU_rows;
  int comps_in_scan;
  jpeg_component_info *cur_comp_info[4];
  unsigned int MCUs_per_row;
  unsigned int MCU_rows_in_scan;
  int blocks_in_MCU;
  int MCU_membership[10];
  int Ss;
  int Se;
  int Ah;
  int Al;
  int block_size;
  const int *natural_order;
  int lim_Se;
  jpeg_comp_master *master;
  jpeg_c_main_controller *main;
  jpeg_c_prep_controller *prep;
  jpeg_c_coef_controller *coef;
  jpeg_marker_writer *marker;
  jpeg_color_converter *cconvert;
  jpeg_downsampler *downsample;
  jpeg_forward_dct *fdct;
  jpeg_entropy_encoder *entropy;
  jpeg_scan_info *script_space;
  int script_space_size;
};

```

### `jpeg_destination_mgr`
```
struct jpeg_destination_mgr
{
  unsigned __int8 *next_output_byte;
  unsigned __int64 free_in_buffer;
  void (__fastcall *init_destination)(jpeg_compress_struct *);
  unsigned __int8 (__fastcall *empty_output_buffer)(jpeg_compress_struct *);
  void (__fastcall *term_destination)(jpeg_compress_struct *);
};

```

### `JQUANT_TBL`
```
struct __declspec(align(2)) JQUANT_TBL
{
  unsigned __int16 quantval[64];
  unsigned __int8 sent_table;
};

```

### `jpeg_component_info`
```
struct jpeg_component_info
{
  int component_id;
  int component_index;
  int h_samp_factor;
  int v_samp_factor;
  int quant_tbl_no;
  int dc_tbl_no;
  int ac_tbl_no;
  unsigned int width_in_blocks;
  unsigned int height_in_blocks;
  int DCT_h_scaled_size;
  int DCT_v_scaled_size;
  unsigned int downsampled_width;
  unsigned int downsampled_height;
  unsigned __int8 component_needed;
  int MCU_width;
  int MCU_height;
  int MCU_blocks;
  int MCU_sample_width;
  int last_col_width;
  int last_row_height;
  JQUANT_TBL *quant_table;
  void *dct_table;
};

```

### `JHUFF_TBL`
```
struct JHUFF_TBL
{
  unsigned __int8 bits[17];
  unsigned __int8 huffval[256];
  unsigned __int8 sent_table;
};

```

### `jpeg_scan_info`
```
const struct jpeg_scan_info
{
  int comps_in_scan;
  int component_index[4];
  int Ss;
  int Se;
  int Ah;
  int Al;
};

```

### `jpeg_comp_master`
```
struct __declspec(align(8)) jpeg_comp_master
{
  void (__fastcall *prepare_for_pass)(jpeg_compress_struct *);
  void (__fastcall *pass_startup)(jpeg_compress_struct *);
  void (__fastcall *finish_pass)(jpeg_compress_struct *);
  unsigned __int8 call_pass_startup;
  unsigned __int8 is_last_pass;
};

```

### `jpeg_c_main_controller`
```
struct jpeg_c_main_controller
{
  void (__fastcall *start_pass)(jpeg_compress_struct *, J_BUF_MODE);
  void (__fastcall *process_data)(jpeg_compress_struct *, unsigned __int8 **, unsigned int *, unsigned int);
};

```

### `jpeg_c_prep_controller`
```
struct jpeg_c_prep_controller
{
  void (__fastcall *start_pass)(jpeg_compress_struct *, J_BUF_MODE);
  void (__fastcall *pre_process_data)(jpeg_compress_struct *, unsigned __int8 **, unsigned int *, unsigned int, unsigned __int8 ***, unsigned int *, unsigned int);
};

```

### `jpeg_c_coef_controller`
```
struct jpeg_c_coef_controller
{
  void (__fastcall *start_pass)(jpeg_compress_struct *, J_BUF_MODE);
  unsigned __int8 (__fastcall *compress_data)(jpeg_compress_struct *, unsigned __int8 ***);
};

```

### `jpeg_marker_writer`
```
struct jpeg_marker_writer
{
  void (__fastcall *write_file_header)(jpeg_compress_struct *);
  void (__fastcall *write_frame_header)(jpeg_compress_struct *);
  void (__fastcall *write_scan_header)(jpeg_compress_struct *);
  void (__fastcall *write_file_trailer)(jpeg_compress_struct *);
  void (__fastcall *write_tables_only)(jpeg_compress_struct *);
  void (__fastcall *write_marker_header)(jpeg_compress_struct *, int, unsigned int);
  void (__fastcall *write_marker_byte)(jpeg_compress_struct *, int);
};

```

### `jpeg_color_converter`
```
struct jpeg_color_converter
{
  void (__fastcall *start_pass)(jpeg_compress_struct *);
  void (__fastcall *color_convert)(jpeg_compress_struct *, unsigned __int8 **, unsigned __int8 ***, unsigned int, int);
};

```

### `jpeg_downsampler`
```
struct __declspec(align(8)) jpeg_downsampler
{
  void (__fastcall *start_pass)(jpeg_compress_struct *);
  void (__fastcall *downsample)(jpeg_compress_struct *, unsigned __int8 ***, unsigned int, unsigned __int8 ***, unsigned int);
  unsigned __int8 need_context_rows;
};

```

### `jpeg_forward_dct`
```
struct jpeg_forward_dct
{
  void (__fastcall *start_pass)(jpeg_compress_struct *);
  void (__fastcall *forward_DCT[10])(jpeg_compress_struct *, jpeg_component_info *, unsigned __int8 **, __int16 (*)[64], unsigned int, unsigned int, unsigned int);
};

```

### `jpeg_entropy_encoder`
```
struct jpeg_entropy_encoder
{
  void (__fastcall *start_pass)(jpeg_compress_struct *, unsigned __int8);
  unsigned __int8 (__fastcall *encode_mcu)(jpeg_compress_struct *, __int16 (**)[64]);
  void (__fastcall *finish_pass)(jpeg_compress_struct *);
};

```

### `JpgSafeBuffer`
```
struct __cppobj __declspec(align(8)) JpgSafeBuffer
{
  unsigned __int8 *mpBuffer;
  unsigned int mSize;
};

```

### `JpegData`
```
struct __cppobj JpegData
{
};

```

### `Json::MinecraftJsonStyledWriter`
```
struct __cppobj __declspec(align(8)) Json::MinecraftJsonStyledWriter : Json::Writer
{
  std::vector<std::string> mChildValues;
  std::string mDocument;
  std::string mIndentString;
  int mRightMargin;
  int mIndentSize;
  bool mAddChildValues;
};

```

### `Json::MinecraftJsonStyledWriter_vtbl`
```
struct /*VFT*/ Json::MinecraftJsonStyledWriter_vtbl
{
  void (__fastcall *~Writer)(Json::Writer *this);
  std::string *(__fastcall *write)(Json::Writer *this, std::string *result, const Json::Value *);
};

```

### `JsonUtil::addMember::__l2::<lambda_fb61c2066df71d21c56c264764dd0948>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_fb61c2066df71d21c56c264764dd0948>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_6757771e57240a3d2676f53f514fc2b0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6757771e57240a3d2676f53f514fc2b0>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_bbcebe299cbf241a27448c2e6541d098>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_bbcebe299cbf241a27448c2e6541d098>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_693ff99b4975c7fbfecd3c30b469483d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_693ff99b4975c7fbfecd3c30b469483d>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8f9d6b5e8523a76ffdccc7e055516a72>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8f9d6b5e8523a76ffdccc7e055516a72>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_47376a8d9727f71a5319d4303c89b14f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_47376a8d9727f71a5319d4303c89b14f>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_6a031ddf32df174bc24f0c0a509d32db>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6a031ddf32df174bc24f0c0a509d32db>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_5812b418b19fd84111e8c48af4251123>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_5812b418b19fd84111e8c48af4251123>
{
  void (__fastcall *memberSetter)(ItemControlDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_05d5a1ecf7ace61791cceaa54795816f>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_05d5a1ecf7ace61791cceaa54795816f>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e8a7efd5e08c826083117af9256efcfa>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e8a7efd5e08c826083117af9256efcfa>
{
  void (__fastcall *memberSetter)(ItemControlDefinition *this, const std::string *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e43b6082efc1575a3664de63f628895b>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e43b6082efc1575a3664de63f628895b>
{
  void (__fastcall *memberSetter)(FamilyTypeDefinition *this, const std::string *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_b4b41cee0178fcdfffe2aab628b3bd72>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_b4b41cee0178fcdfffe2aab628b3bd72>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_91ad38c9a75964ae5bbab00b2e66c140>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_91ad38c9a75964ae5bbab00b2e66c140>
{
  void (__fastcall *memberSetter)(FamilyTypeDefinition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_2d800a2f159dcd079cd811d9a6319798>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2d800a2f159dcd079cd811d9a6319798>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e8a121bf18a2b4a247e7919aadca6858>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e8a121bf18a2b4a247e7919aadca6858>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_d0f8730be191966dc4d412771bfc5ee3>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_d0f8730be191966dc4d412771bfc5ee3>
{
  void (__fastcall *memberSetter)(SlotDropChance *this, const std::string *);
  const std::string defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_1d72e84766224249876c3c8652d8f940>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_1d72e84766224249876c3c8652d8f940>
{
  void (__fastcall *memberSetter)(SlotDropChance *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_ade74c35d12a574f174d6c460665db10>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ade74c35d12a574f174d6c460665db10>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_024a5fbbbe758ee7292827173c06ba77>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_024a5fbbbe758ee7292827173c06ba77>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_c331900e651dc6e0ed180f5fa186d08d>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_c331900e651dc6e0ed180f5fa186d08d>
{
  void (__fastcall *memberSetter)(ColorDefinition *this, const int *);
  const int defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_e4237523bbe9b9ac0851837d265f1025>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_e4237523bbe9b9ac0851837d265f1025>
{
  void (__fastcall *memberSetter)(ColorDefinition *this, const int *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_14b35562d93aa0cef8536f8d98dc4e85>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_14b35562d93aa0cef8536f8d98dc4e85>
{
  void (__fastcall *memberSetter)(ColorDefinition *this, const int *);
  const int defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_77c7eba9320f685d255b6f754882b931>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_77c7eba9320f685d255b6f754882b931>
{
  void (__fastcall *memberSetter)(ColorDefinition *this, const int *);
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_61dd6a63d7e7fdae0af26241d630281b>`
```
struct __cppobj __declspec(align(8)) JsonUtil::addMemberSetter::__l2::<lambda_61dd6a63d7e7fdae0af26241d630281b>
{
  void (__fastcall *memberSetter)(CollisionBoxDefinition *this, const float *);
  const float defaultValue;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_8e9936a3005129cce70ef3f65dcf138e>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_8e9936a3005129cce70ef3f65dcf138e>
{
  void (__fastcall *memberSetter)(CollisionBoxDefinition *this, const float *);
};

```

### `JsonUtil::addMember::__l2::<lambda_b92ffdb93b2de998ef65866579cc344a>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_b92ffdb93b2de998ef65866579cc344a>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8a63de50f3c8fe4e8614b44748ed4e27>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8a63de50f3c8fe4e8614b44748ed4e27>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_5e046fc4ae195be64008fcb12bcffda4>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5e046fc4ae195be64008fcb12bcffda4>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8370ec220554c46c8031d79f1d883d46>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8370ec220554c46c8031d79f1d883d46>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_05f824850b77c440529c551811e5e758>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_05f824850b77c440529c551811e5e758>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_353e017e24fbb508fd31bbf04f7abc32>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_353e017e24fbb508fd31bbf04f7abc32>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_897beebbbbddf005836663abf690dbd5>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_897beebbbbddf005836663abf690dbd5>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1871a407eaa2949205d6f6ff3ee4fc05>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1871a407eaa2949205d6f6ff3ee4fc05>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_79cdc1590f6e836436a457b5908b5494>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_79cdc1590f6e836436a457b5908b5494>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_937e4d1c2f596811cc0bebf665206667>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_937e4d1c2f596811cc0bebf665206667>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_477c350b9d4d023a5d62f412de6e5c74>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_477c350b9d4d023a5d62f412de6e5c74>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_1a8e1bb72804d334a9c9b50c3a9a79c9>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_1a8e1bb72804d334a9c9b50c3a9a79c9>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_c115a16ab57c0327afc2afccbc0ddaf7>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c115a16ab57c0327afc2afccbc0ddaf7>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_0c593e26ad24a70661d3877b96f2a275>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0c593e26ad24a70661d3877b96f2a275>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8427f7eba3ff1964d7cd533fa2c180d3>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8427f7eba3ff1964d7cd533fa2c180d3>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_24a6c59fe2f6bc58dbcca5a92fdfbc3c>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_24a6c59fe2f6bc58dbcca5a92fdfbc3c>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_77f55ee9b1c5b9259a4cf1f17b13b908>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_77f55ee9b1c5b9259a4cf1f17b13b908>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_e53c5425ae2602d6d22f4bb21528f511>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e53c5425ae2602d6d22f4bb21528f511>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_92c3254c97ebb0f8c19ba42acc175901>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_92c3254c97ebb0f8c19ba42acc175901>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_69985e6c7e8300ab404abaac250ad7d0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_69985e6c7e8300ab404abaac250ad7d0>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_8cbf446e28899feb592fe8c41d14d93b>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_8cbf446e28899feb592fe8c41d14d93b>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_16262c525621c3dce682471103e6f449>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_16262c525621c3dce682471103e6f449>
{
  ActorFilterGroup *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_06449b8a20cec6dec4cd4591430759fa>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_06449b8a20cec6dec4cd4591430759fa>
{
  std::string *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d182de206d6e042c8d4680328d67858d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d182de206d6e042c8d4680328d67858d>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_5867edcd5befb6c6e4ea16a254b05533>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5867edcd5befb6c6e4ea16a254b05533>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_5decd86075ce9a63cad2a1131b90f8dc>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_5decd86075ce9a63cad2a1131b90f8dc>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_62aefb32a3d31fa48cd1b7efbab99b8f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_62aefb32a3d31fa48cd1b7efbab99b8f>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_d8d287f5f9f64fd404dde83e718799c8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d8d287f5f9f64fd404dde83e718799c8>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_058316267abedac740c879314f229f53>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_058316267abedac740c879314f229f53>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_979a668deb3024be3b61df54be58fea8>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_979a668deb3024be3b61df54be58fea8>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_575f266788c55a86872e92cd2eaaa5fd>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_575f266788c55a86872e92cd2eaaa5fd>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_cb0b0061ad5bdb4a0865ed3e6b45125f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_cb0b0061ad5bdb4a0865ed3e6b45125f>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_e7d19d963caebf9e4123b06809e6814d>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e7d19d963caebf9e4123b06809e6814d>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_489d5df4f148f7a7aed21808112b0422>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_489d5df4f148f7a7aed21808112b0422>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_4367bf68bd63957d5ab17130afd4ec8e>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_4367bf68bd63957d5ab17130afd4ec8e>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_2fd7466550fcf39acf1c15dbe0fbee3f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_2fd7466550fcf39acf1c15dbe0fbee3f>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_69f5d2c8d57c24d7e40a33e9872d0022>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_69f5d2c8d57c24d7e40a33e9872d0022>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_e28fb5bd4515d06da910f1ef422f0b61>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_e28fb5bd4515d06da910f1ef422f0b61>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_d68bc644c53ea584a13a6f1ba4e8cc58>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_d68bc644c53ea584a13a6f1ba4e8cc58>
{
  float *__ptr32 member;
};

```

### `JukeboxBlock`
```
struct __cppobj JukeboxBlock : ActorBlock
{
};

```

### `JukeboxBlock_vtbl`
```
struct /*VFT*/ JukeboxBlock_vtbl
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

### `jsonValConversion<char [27]>`
```
struct __cppobj jsonValConversion<char [27]>
{
};

```

### `jsonValConversion<char [24]>`
```
struct __cppobj jsonValConversion<char [24]>
{
};

```

### `JsonUtil::addMember::__l2::<lambda_6589ef3d5d522e1389bd1554af21e9bb>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_6589ef3d5d522e1389bd1554af21e9bb>
{
  FloatRange *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_ff629279d9527948b7d6db8593ae1ce6>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_ff629279d9527948b7d6db8593ae1ce6>
{
  std::vector<ItemDescriptor> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_491c9a9b5a8b74162763ee108ff79d3d>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_491c9a9b5a8b74162763ee108ff79d3d>
{
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_c641a5874a7f2c9fe44e5fc5d5e95ff5>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_c641a5874a7f2c9fe44e5fc5d5e95ff5>
{
  std::vector<DefinitionTrigger> *__ptr32 member;
};

```

### `JsonUtil::addArrayMember::__l2::<lambda_692c4cf3e94538b2208859588e8d5e10>`
```
struct __cppobj JsonUtil::addArrayMember::__l2::<lambda_692c4cf3e94538b2208859588e8d5e10>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_f686b858abb9c3cfee7c879e92132c93>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_f686b858abb9c3cfee7c879e92132c93>
{
  void (__fastcall *memberSetter)(AvoidBlockGoal::Definition *this, const std::string *);
};

```

### `JsonUtil::addMember::__l2::<lambda_beae8ec086576fb3d3f8522bc30c7dc0>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_beae8ec086576fb3d3f8522bc30c7dc0>
{
  int *__ptr32 member;
  const int defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_c065bc11d9ccb7213b8beab15f33ed39>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_c065bc11d9ccb7213b8beab15f33ed39>
{
  int *__ptr32 member;
};

```

### `JsonUtil::addMember::__l2::<lambda_ec6bbc90cde3b6dec5c064f335422942>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_ec6bbc90cde3b6dec5c064f335422942>
{
  float *__ptr32 member;
  const float defaultValue;
};

```

### `JsonUtil::addMember::__l2::<lambda_0206a56403c2e83901885ac91cc5f08f>`
```
struct __cppobj JsonUtil::addMember::__l2::<lambda_0206a56403c2e83901885ac91cc5f08f>
{
  float *__ptr32 member;
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_db2749128519157166cb1ca1148650ed>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_db2749128519157166cb1ca1148650ed>
{
  void (__fastcall *memberSetter)(EatBlockDefinition *this, const ExpressionNode *);
};

```

### `JsonUtil::addArrayMemberSetter::__l2::<lambda_683a0897a234633fa689e4d181dd49b0>`
```
struct __cppobj JsonUtil::addArrayMemberSetter::__l2::<lambda_683a0897a234633fa689e4d181dd49b0>
{
};

```

### `JsonUtil::addMemberSetter::__l2::<lambda_86a9e749e6c43fb471f83716c875c9bb>`
```
struct __cppobj JsonUtil::addMemberSetter::__l2::<lambda_86a9e749e6c43fb471f83716c875c9bb>
{
  void (__fastcall *memberSetter)(EatBlockDefinition *this, const ExpressionNode *);
};

```

### `JunglePyramidPiece`
```
struct __cppobj __declspec(align(8)) JunglePyramidPiece : ScatteredFeaturePiece
{
  bool mHasPlacedMainChest;
  bool mHasPlacedHiddenChest;
  bool mHasPlacedTrap[2];
};

```

### `JunglePyramidPiece_vtbl`
```
struct /*VFT*/ JunglePyramidPiece_vtbl
{
  void (__fastcall *~StructurePiece)(StructurePiece *this);
  void (__fastcall *moveBoundingBox)(StructurePiece *this, int, int, int);
  PoolElementStructurePiece *(__fastcall *asPoolElement)(StructurePiece *this);
  StructurePieceType (__fastcall *getType)(StructurePiece *this);
  void (__fastcall *addChildren)(StructurePiece *this, StructurePiece *, std::vector<std::unique_ptr<StructurePiece>> *, Random *);
  bool (__fastcall *postProcess)(StructurePiece *this, BlockSource *, Random *, const BoundingBox *);
  void (__fastcall *postProcessMobsAt)(StructurePiece *this, BlockSource *, Random *, const BoundingBox *);
  int (__fastcall *getWorldX)(StructurePiece *this, int, int);
  int (__fastcall *getWorldZ)(StructurePiece *this, int, int);
  void (__fastcall *placeBlock)(StructurePiece *this, BlockSource *, const Block *, int, int, int, const BoundingBox *);
  void (__fastcall *generateBox)(StructurePiece *this, BlockSource *, const BoundingBox *, int, int, int, int, int, int, const Block *, const Block *, bool);
  void (__fastcall *addHardcodedSpawnAreas)(StructurePiece *this, LevelChunk *);
};

```

### `jpeg_decompress_struct`
```
struct jpeg_decompress_struct
{
  jpeg_error_mgr *err;
  jpeg_memory_mgr *mem;
  jpeg_progress_mgr *progress;
  void *client_data;
  unsigned __int8 is_decompressor;
  int global_state;
  jpeg_source_mgr *src;
  unsigned int image_width;
  unsigned int image_height;
  int num_components;
  J_COLOR_SPACE jpeg_color_space;
  J_COLOR_SPACE out_color_space;
  unsigned int scale_num;
  unsigned int scale_denom;
  long double output_gamma;
  unsigned __int8 buffered_image;
  unsigned __int8 raw_data_out;
  J_DCT_METHOD dct_method;
  unsigned __int8 do_fancy_upsampling;
  unsigned __int8 do_block_smoothing;
  unsigned __int8 quantize_colors;
  J_DITHER_MODE dither_mode;
  unsigned __int8 two_pass_quantize;
  int desired_number_of_colors;
  unsigned __int8 enable_1pass_quant;
  unsigned __int8 enable_external_quant;
  unsigned __int8 enable_2pass_quant;
  unsigned int output_width;
  unsigned int output_height;
  int out_color_components;
  int output_components;
  int rec_outbuf_height;
  int actual_number_of_colors;
  unsigned __int8 **colormap;
  unsigned int output_scanline;
  int input_scan_number;
  unsigned int input_iMCU_row;
  int output_scan_number;
  unsigned int output_iMCU_row;
  int (*coef_bits)[64];
  JQUANT_TBL *quant_tbl_ptrs[4];
  JHUFF_TBL *dc_huff_tbl_ptrs[4];
  JHUFF_TBL *ac_huff_tbl_ptrs[4];
  int data_precision;
  jpeg_component_info *comp_info;
  unsigned __int8 is_baseline;
  unsigned __int8 progressive_mode;
  unsigned __int8 arith_code;
  unsigned __int8 arith_dc_L[16];
  unsigned __int8 arith_dc_U[16];
  unsigned __int8 arith_ac_K[16];
  unsigned int restart_interval;
  unsigned __int8 saw_JFIF_marker;
  unsigned __int8 JFIF_major_version;
  unsigned __int8 JFIF_minor_version;
  unsigned __int8 density_unit;
  unsigned __int16 X_density;
  unsigned __int16 Y_density;
  unsigned __int8 saw_Adobe_marker;
  unsigned __int8 Adobe_transform;
  J_COLOR_TRANSFORM color_transform;
  unsigned __int8 CCIR601_sampling;
  jpeg_marker_struct *marker_list;
  int max_h_samp_factor;
  int max_v_samp_factor;
  int min_DCT_h_scaled_size;
  int min_DCT_v_scaled_size;
  unsigned int total_iMCU_rows;
  unsigned __int8 *sample_range_limit;
  int comps_in_scan;
  jpeg_component_info *cur_comp_info[4];
  unsigned int MCUs_per_row;
  unsigned int MCU_rows_in_scan;
  int blocks_in_MCU;
  int MCU_membership[10];
  int Ss;
  int Se;
  int Ah;
  int Al;
  int block_size;
  const int *natural_order;
  int lim_Se;
  int unread_marker;
  jpeg_decomp_master *master;
  jpeg_d_main_controller *main;
  jpeg_d_coef_controller *coef;
  jpeg_d_post_controller *post;
  jpeg_input_controller *inputctl;
  jpeg_marker_reader *marker;
  jpeg_entropy_decoder *entropy;
  jpeg_inverse_dct *idct;
  jpeg_upsampler *upsample;
  jpeg_color_deconverter *cconvert;
  jpeg_color_quantizer *cquantize;
};

```

### `jpeg_source_mgr`
```
struct jpeg_source_mgr
{
  const unsigned __int8 *next_input_byte;
  unsigned __int64 bytes_in_buffer;
  void (__fastcall *init_source)(jpeg_decompress_struct *);
  unsigned __int8 (__fastcall *fill_input_buffer)(jpeg_decompress_struct *);
  void (__fastcall *skip_input_data)(jpeg_decompress_struct *, int);
  unsigned __int8 (__fastcall *resync_to_restart)(jpeg_decompress_struct *, int);
  void (__fastcall *term_source)(jpeg_decompress_struct *);
};

```

### `jpeg_marker_struct`
```
struct jpeg_marker_struct
{
  jpeg_marker_struct *next;
  unsigned __int8 marker;
  unsigned int original_length;
  unsigned int data_length;
  unsigned __int8 *data;
};

```

### `jpeg_decomp_master`
```
struct __declspec(align(8)) jpeg_decomp_master
{
  void (__fastcall *prepare_for_output_pass)(jpeg_decompress_struct *);
  void (__fastcall *finish_output_pass)(jpeg_decompress_struct *);
  unsigned __int8 is_dummy_pass;
};

```

### `jpeg_d_main_controller`
```
struct jpeg_d_main_controller
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *, J_BUF_MODE);
  void (__fastcall *process_data)(jpeg_decompress_struct *, unsigned __int8 **, unsigned int *, unsigned int);
};

```

### `jpeg_d_coef_controller`
```
struct jpeg_d_coef_controller
{
  void (__fastcall *start_input_pass)(jpeg_decompress_struct *);
  int (__fastcall *consume_data)(jpeg_decompress_struct *);
  void (__fastcall *start_output_pass)(jpeg_decompress_struct *);
  int (__fastcall *decompress_data)(jpeg_decompress_struct *, unsigned __int8 ***);
  jvirt_barray_control **coef_arrays;
};

```

### `jpeg_d_post_controller`
```
struct jpeg_d_post_controller
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *, J_BUF_MODE);
  void (__fastcall *post_process_data)(jpeg_decompress_struct *, unsigned __int8 ***, unsigned int *, unsigned int, unsigned __int8 **, unsigned int *, unsigned int);
};

```

### `jpeg_input_controller`
```
struct __declspec(align(8)) jpeg_input_controller
{
  int (__fastcall *consume_input)(jpeg_decompress_struct *);
  void (__fastcall *reset_input_controller)(jpeg_decompress_struct *);
  void (__fastcall *start_input_pass)(jpeg_decompress_struct *);
  void (__fastcall *finish_input_pass)(jpeg_decompress_struct *);
  unsigned __int8 has_multiple_scans;
  unsigned __int8 eoi_reached;
};

```

### `jpeg_marker_reader`
```
struct __declspec(align(8)) jpeg_marker_reader
{
  void (__fastcall *reset_marker_reader)(jpeg_decompress_struct *);
  int (__fastcall *read_markers)(jpeg_decompress_struct *);
  unsigned __int8 (__fastcall *read_restart_marker)(jpeg_decompress_struct *);
  unsigned __int8 saw_SOI;
  unsigned __int8 saw_SOF;
  int next_restart_num;
  unsigned int discarded_bytes;
};

```

### `jpeg_entropy_decoder`
```
struct jpeg_entropy_decoder
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *);
  unsigned __int8 (__fastcall *decode_mcu)(jpeg_decompress_struct *, __int16 (**)[64]);
  void (__fastcall *finish_pass)(jpeg_decompress_struct *);
};

```

### `jpeg_inverse_dct`
```
struct jpeg_inverse_dct
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *);
  void (__fastcall *inverse_DCT[10])(jpeg_decompress_struct *, jpeg_component_info *, __int16 *, unsigned __int8 **, unsigned int);
};

```

### `jpeg_upsampler`
```
struct __declspec(align(8)) jpeg_upsampler
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *);
  void (__fastcall *upsample)(jpeg_decompress_struct *, unsigned __int8 ***, unsigned int *, unsigned int, unsigned __int8 **, unsigned int *, unsigned int);
  unsigned __int8 need_context_rows;
};

```

### `jpeg_color_deconverter`
```
struct jpeg_color_deconverter
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *);
  void (__fastcall *color_convert)(jpeg_decompress_struct *, unsigned __int8 ***, unsigned int, unsigned __int8 **, int);
};

```

### `jpeg_color_quantizer`
```
struct jpeg_color_quantizer
{
  void (__fastcall *start_pass)(jpeg_decompress_struct *, unsigned __int8);
  void (__fastcall *color_quantize)(jpeg_decompress_struct *, unsigned __int8 **, unsigned __int8 **, int);
  void (__fastcall *finish_pass)(jpeg_decompress_struct *);
  void (__fastcall *new_color_map)(jpeg_decompress_struct *);
};

```

### `JsonSaver`
```
struct __cppobj JsonSaver : Serializer
{
  JsonInternalData *mData;
};

```

### `JsonSaver_vtbl`
```
struct /*VFT*/ JsonSaver_vtbl
{
  void (__fastcall *~Serializer)(Serializer *this);
  bool (__fastcall *isBool)(Serializer *this);
  bool (__fastcall *isInt)(Serializer *this);
  bool (__fastcall *isString)(Serializer *this);
  bool (__fastcall *isObject)(Serializer *this);
  bool (__fastcall *isArray)(Serializer *this);
  bool (__fastcall *serializeBool)(Serializer *this, bool *);
  bool (__fastcall *serializeS8)(Serializer *this, char *);
  bool (__fastcall *serializeU8)(Serializer *this, unsigned __int8 *);
  bool (__fastcall *serializeS16)(Serializer *this, __int16 *);
  bool (__fastcall *serializeU16)(Serializer *this, unsigned __int16 *);
  bool (__fastcall *serializeS32)(Serializer *this, int *);
  bool (__fastcall *serializeU32)(Serializer *this, unsigned int *);
  bool (__fastcall *serializeFloat)(Serializer *this, float *);
  bool (__fastcall *serializeString)(Serializer *this, std::string *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned int *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int16 *, const SerializerTraits *);
  bool (__fastcall *serializeEnum)(Serializer *this, unsigned __int8 *, const SerializerTraits *);
  bool (__fastcall *beginMember)(Serializer *this, unsigned __int64, std::string *);
  bool (__fastcall *beginMember)(Serializer *this, const char *, bool);
  bool (__fastcall *endMember)(Serializer *this);
  bool (__fastcall *beginArray)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginArrayItem)(Serializer *this, unsigned __int64);
  bool (__fastcall *endArrayItem)(Serializer *this);
  bool (__fastcall *endArray)(Serializer *this);
  bool (__fastcall *beginObject)(Serializer *this, unsigned __int64 *);
  bool (__fastcall *beginObject)(Serializer *this);
  bool (__fastcall *endObject)(Serializer *this);
};

```

### `JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_b51db3996d738bb20aa0b6b01ffde9d9>::()::__l2::<lambda_40157ed9ca5b0556e200460240932afa>`
```
struct __cppobj JoincodeEntryScreenController::_registerEntryScreenBindings::__l2::<lambda_b51db3996d738bb20aa0b6b01ffde9d9>::()::__l2::<lambda_40157ed9ca5b0556e200460240932afa>
{
};

```

### `JsonDefinitionUpgrader::createCompositeUpgrader::__l2::Upgrader::tryUpgrade::__l3::<lambda_1e93af9a8da93918e0be923ae291e8e2>`
```
struct __cppobj JsonDefinitionUpgrader::createCompositeUpgrader::__l2::Upgrader::tryUpgrade::__l3::<lambda_1e93af9a8da93918e0be923ae291e8e2>
{
  SemVersion *currentVersion;
  Json::Value *toUpgrade;
};

```

### `JigsawEditorData::setJointTypeFromName::__l2::<lambda_3dd6328b9609c1adac729d644f9fbba2>`
```
struct __cppobj JigsawEditorData::setJointTypeFromName::__l2::<lambda_3dd6328b9609c1adac729d644f9fbba2>
{
  const std::string name;
};

```

### `JsonValidator::validate::__l2::<lambda_8961075f02cb9ca4a702a0ecb09c4fd7>`
```
struct __cppobj JsonValidator::validate::__l2::<lambda_8961075f02cb9ca4a702a0ecb09c4fd7>
{
};

```

### `JukeboxBlockActor::_spawnMusicParticles::__l5::<lambda_73f30846ea65f36104626f7c15f88e1f>::()::__l2::Literal`
```
struct __cppobj JukeboxBlockActor::_spawnMusicParticles::__l5::<lambda_73f30846ea65f36104626f7c15f88e1f>::()::__l2::Literal
{
};

```

### `JukeboxBlockActor::_spawnMusicParticles::__l5::<lambda_73f30846ea65f36104626f7c15f88e1f>`
```
struct __cppobj JukeboxBlockActor::_spawnMusicParticles::__l5::<lambda_73f30846ea65f36104626f7c15f88e1f>
{
};

```

### `JukeboxBlockActor_vtbl`
```
struct /*VFT*/ JukeboxBlockActor_vtbl
{
  void (__fastcall *~BlockActor)(BlockActor *this);
  void (__fastcall *load)(BlockActor *this, Level *, const CompoundTag *, DataLoadHelper *);
  bool (__fastcall *save)(BlockActor *this, CompoundTag *);
  bool (__fastcall *saveItemInstanceData)(BlockActor *this, CompoundTag *);
  void (__fastcall *saveBlockData)(BlockActor *this, CompoundTag *, BlockSource *);
  void (__fastcall *loadBlockData)(BlockActor *this, const CompoundTag *, BlockSource *, DataLoadHelper *);
  void (__fastcall *onCustomTagLoadDone)(BlockActor *this, BlockSource *);
  void (__fastcall *tick)(BlockActor *this, BlockSource *);
  bool (__fastcall *isFinished)(BlockActor *this);
  void (__fastcall *onChanged)(BlockActor *this, BlockSource *);
  bool (__fastcall *isMovable)(BlockActor *this, BlockSource *);
  bool (__fastcall *isCustomNameSaved)(BlockActor *this);
  bool (__fastcall *onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *, const Player *);
  void (__fastcall *onPlace)(BlockActor *this, BlockSource *);
  void (__fastcall *onMove)(BlockActor *this);
  void (__fastcall *onRemoved)(BlockActor *this, BlockSource *);
  void (__fastcall *triggerEvent)(BlockActor *this, int, int);
  void (__fastcall *clearCache)(BlockActor *this);
  void (__fastcall *onNeighborChanged)(BlockActor *this, BlockSource *, const BlockPos *);
  float (__fastcall *getShadowRadius)(BlockActor *this, BlockSource *);
  bool (__fastcall *hasAlphaLayer)(BlockActor *this);
  BlockActor *(__fastcall *getCrackEntity)(BlockActor *this, BlockSource *, const BlockPos *);
  void (__fastcall *getDebugText)(BlockActor *this, std::vector<std::string> *, const BlockPos *);
  const std::string *(__fastcall *getCustomName)(BlockActor *this);
  const std::string *(__fastcall *getFilteredCustomName)(BlockActor *this, const UIProfanityContext *);
  std::string *(__fastcall *getName)(BlockActor *this, std::string *result);
  void (__fastcall *setCustomName)(BlockActor *this, const std::string *);
  std::string *(__fastcall *getImmersiveReaderText)(BlockActor *this, std::string *result, BlockSource *);
  int (__fastcall *getRepairCost)(BlockActor *this);
  PistonBlockActor *(__fastcall *getOwningPiston)(BlockActor *this, BlockSource *);
  const Container *(__fastcall *getContainer)(BlockActor *this);
  Container *(__fastcall *getContainer)(BlockActor *this);
  float (__fastcall *getDeletionDelayTimeSeconds)(BlockActor *this);
  void (__fastcall *checkWordsOnChunkLoad)(BlockActor *this, LevelChunk *);
  void (__fastcall *checkWordsOnUpdate)(BlockActor *this, Player *);
  void (__fastcall *onChunkLoaded)(BlockActor *this, LevelChunk *);
  void (__fastcall *onChunkUnloaded)(BlockActor *this, LevelChunk *);
  std::unique_ptr<BlockActorDataPacket> *(__fastcall *_getUpdatePacket)(BlockActor *this, std::unique_ptr<BlockActorDataPacket> *result, BlockSource *);
  void (__fastcall *_onUpdatePacket)(BlockActor *this, const CompoundTag *, BlockSource *);
  bool (__fastcall *_playerCanUpdate)(BlockActor *this, const Player *);
};

```

