# J
### `Json::Value`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value::ValueHolder` | value_
8 | (1) `__int8` | type_
9 | (1) `__int8` | _bf_9


### `Json::Value::ValueHolder`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Value::LargestInt` | int_
1 | (8) `Json::Value::LargestUInt` | uint_
2 | (8) `double` | real_
3 | (1) `bool` | bool_
4 | (8) `char *` | string_
5 | (8) `Json::Value::ObjectValues *` | map_


### `Json::ValueConstIterator`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::ValueIteratorBase` | baseclass_0


### `Json::ValueIteratorBase`
Offset | Type | Name
-|-|-|-
0 | (8) `std::map<Json::Value::CZString,Json::Value>::iterator` | current_
8 | (1) `bool` | isNull_


### `Json::ValueIterator`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::ValueIteratorBase` | baseclass_0


### `Json::Reader`
Offset | Type | Name
-|-|-|-
0 | (80) `Json::Reader::Nodes` | nodes_
80 | (80) `Json::Reader::Errors` | errors_
160 | (32) `std::string` | document_
192 | (8) `Json::Reader::Location` | begin_
200 | (8) `Json::Reader::Location` | end_
208 | (8) `Json::Reader::Location` | current_
216 | (8) `Json::Reader::Location` | lastValueEnd_
224 | (8) `Json::Value *` | lastValue_
232 | (32) `std::string` | commentsBefore_
264 | (2) `Json::Features` | features_
266 | (1) `bool` | collectComments_


### `Json::Reader::Nodes`
Offset | Type | Name
-|-|-|-
0 | (80) `std::deque<Json::Value *>` | c


### `Json::Reader::Errors`
Offset | Type | Name
-|-|-|-
0 | (80) `std::_Deque_base<Json::Reader::ErrorInfo>` | baseclass_0


### `Json::Features`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | allowComments_
1 | (1) `bool` | strictRoot_


### `Json::FastWriter`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Writer` | baseclass_0
8 | (32) `std::string` | document_
40 | (1) `bool` | yamlCompatiblityEnabled_


### `Json::Writer`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Writer


### `JumpControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mJumping
1 | (1) `bool` | mSwimming
4 | (4) `float` | mJumpPower
8 | (4) `JumpType` | mJumpType
12 | (64) `JumpInfo[4]` | mJumpInfo
80 | (8) `Unique<JumpControl>` | mJumpControl


### `JumpInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mAnimDuration
4 | (4) `int` | mJumpDelay
8 | (4) `float` | mDistanceScale
12 | (4) `float` | mHeight


### `JsonValidator::Property`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Json::ValueType>` | mTypes
24 | (1) `bool` | mIsRequired
25 | (1) `bool` | mRequiresConditionalProperty
32 | (32) `std::string` | mDescription
64 | (16) `JsonValidator::Property::PropertyPtr` | mChildProperty
80 | (24) `std::vector<std::pair<Json::Value,std::shared_ptr<JsonValidator::Property> >>` | mConditionalPropertiesByValue
104 | (24) `std::vector<std::pair<Json::ValueType,std::shared_ptr<JsonValidator::Property> >>` | mConditionalPropertiesByType
128 | (56) `std::unordered_map<std::string,std::shared_ptr<JsonValidator::Property>>` | mPropertyMap


### `JsonValidator::Property::PropertyPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<JsonValidator::Property,__gnu_cxx::_S_atomic>` | baseclass_0


### `Json::StyledWriter`
Offset | Type | Name
-|-|-|-
0 | (8) `Json::Writer` | baseclass_0
8 | (24) `Json::StyledWriter::ChildValues` | childValues_
32 | (32) `std::string` | document_
64 | (32) `std::string` | indentString_
96 | (4) `int` | rightMargin_
100 | (4) `int` | indentSize_
104 | (1) `bool` | addChildValues_


### `Json::StyledWriter::ChildValues`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::string>` | baseclass_0


### `Json::StyledStreamWriter`
Offset | Type | Name
-|-|-|-
0 | (24) `Json::StyledStreamWriter::ChildValues` | childValues_
24 | (8) `std::ostream *` | document_
32 | (32) `std::string` | indentString_
64 | (4) `int` | rightMargin_
72 | (32) `std::string` | indentation_
104 | (1) `bool` | addChildValues_


### `Json::StyledStreamWriter::ChildValues`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::string>` | baseclass_0


### `Json::Value::Members`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::string>` | baseclass_0


### `JsonUtil::SchemaConverterCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<JsonUtil::SchemaConverterNode>` | mCollection


### `JsonUtil::details::BlockReference`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mBlockType
32 | (56) `CompoundTag` | mStates


### `JsonMergeStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackMergeStrategy` | baseclass_0
8 | (32) `std::string` | mFileName
40 | (8) `Json::Value *` | mRoot
48 | (32) `JsonMergeStrategy::PreMergeCallback` | mPreMergeCallback


### `JsonMergeStrategy::PreMergeCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (Json::Value &,const Json::Value &)>::_Invoker_type` | _M_invoker


### `JigsawBlockInfo`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mPos
16 | (8) `const Block *` | mBlock
24 | (8) `const Block *` | mFinalBlock
32 | (32) `std::string` | mAttachmentType
64 | (32) `std::string` | mTargetPool


### `JigsawJunction`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mSourceBlockPos
12 | (4) `int` | mDeltaSourceY
16 | (4) `int` | mDeltaTargetY
20 | (4) `Projection` | mSourceProjection
24 | (4) `Projection` | mTargetProjection


### `JournaledFile`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mFilePath
32 | (16) `Core::File` | mFile
48 | (32) `JournaledFile::ValidationCallback` | mValidationCallback
80 | (4) `JournaledFile::Progression` | mFileProgression


### `JournaledFile::ValidationCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<Core::Result (Core::Path)>::_Invoker_type` | _M_invoker


### `JsonValidator::validate::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `JsonValidator::validate::ValidationState`
Offset | Type | Name
-|-|-|-
0 | (8) `const JsonValidator::Property *` | prop
8 | (8) `const Json::Value *` | data
16 | (8) `const Json::Value *` | parent
24 | (1) `bool` | checkType
32 | (32) `std::string` | name


### `JsonValidator::generateDocs::DocumentationState`
Offset | Type | Name
-|-|-|-
0 | (8) `const JsonValidator::Property *` | prop
8 | (8) `Json::Value *` | data


### `Json::Reader::Token`
Offset | Type | Name
-|-|-|-
0 | (4) `Json::Reader::TokenType` | type_
8 | (8) `Json::Reader::Location` | start_
16 | (8) `Json::Reader::Location` | end_


### `Json::Reader::ErrorInfo`
Offset | Type | Name
-|-|-|-
0 | (24) `Json::Reader::Token` | token_
24 | (32) `std::string` | message_
56 | (8) `Json::Reader::Location` | extra_


### `Json::Value::CZString`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | cstr_
8 | (4) `Json::Value::ArrayIndex` | index_


### `Json::Path::InArgs`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<const Json::PathArgument *>` | baseclass_0


### `jsonValConversion<int>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `jsonValConversion<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `jsonValConversion<Json::Value>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `JukeboxBlockActor::tick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Json::StaticString`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | str_


### `Json::PathArgument`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | key_
32 | (4) `Json::ArrayIndex` | index_
36 | (4) `Json::PathArgument::Kind` | kind_


### `Json::Value::ObjectValues`
```
typedef std::map<Json::Value::CZString,Json::Value> Json::Value::ObjectValues;

```

### `Json::Value::const_iterator`
```
typedef Json::ValueConstIterator Json::Value::const_iterator;

```

### `Json::Value::iterator`
```
typedef Json::ValueIterator Json::Value::iterator;

```

### `Json::ValueConstIterator::SelfType`
```
typedef Json::ValueConstIterator Json::ValueConstIterator::SelfType;

```

### `Json::ValueIteratorBase::SelfType`
```
typedef Json::ValueIteratorBase Json::ValueIteratorBase::SelfType;

```

### `Json::ValueIterator::SelfType`
```
typedef Json::ValueIterator Json::ValueIterator::SelfType;

```

### `JumpControlSystem`
```
struct __cppobj JumpControlSystem : ITickingSystem
{
};

```

### `JsonUtil::JsonNamedNodePtr`
```
struct JsonUtil::JsonNamedNodePtr
{
  const std::string mNodeName;
  const Json::Value *mValuePtr;
};

```

### `JsonUtil::EmptyClass`
```
struct JsonUtil::EmptyClass
{
  __int8 gap0[1];
};

```

### `JungleTreeFeature`
```
struct __cppobj __attribute__((aligned(8))) JungleTreeFeature : TreeFeature
{
};

```

### `JsonUtil::EmptyClass::_TLocalType`
```
typedef JsonUtil::EmptyClass JsonUtil::EmptyClass::_TLocalType;

```

### `JigsawStructureRegistry`
```
struct JigsawStructureRegistry
{
  JigsawStructureRegistry::JigsawPoolLookupMap mJigsawPoolLookupMap;
  JigsawStructureBlockRulesRegistry mJigsawBlockRulesRegistry;
  JigsawStructureBlockTagRulesRegistry mJigsawBlockTagRulesRegistry;
  JigsawStructureActorRulesRegistry mJigsawActorRulesRegistry;
  JigsawStructureElementRegistry mJigsawElementRegistry;
};

```

### `JigsawStructureRegistry::JigsawPoolLookupMap`
```
typedef std::unordered_map<std::string,std::unique_ptr<StructureTemplatePool>> JigsawStructureRegistry::JigsawPoolLookupMap;

```

### `JigsawStructureBlockRulesRegistry`
```
struct JigsawStructureBlockRulesRegistry
{
  JigsawStructureBlockRulesRegistry::BlockRulesRegistryMap mBlockRulesRegistry;
  JigsawStructureBlockRulesRegistry::BlockRulesLookupMap mBlockRuleLookupMap;
};

```

### `JigsawStructureBlockRulesRegistry::BlockRulesRegistryMap`
```
typedef std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockRule>>>> JigsawStructureBlockRulesRegistry::BlockRulesRegistryMap;

```

### `JigsawStructureBlockRulesRegistry::BlockRulesLookupMap`
```
typedef std::unordered_map<std::string,const std::vector<std::unique_ptr<StructurePoolBlockRule>> *,std::hash<std::string>,std::equal_to<std::string >,std::allocator<std::pair<const std::string,const std::vector<std::unique_ptr<StructurePoolBlockRule>> *> > > JigsawStructureBlockRulesRegistry::BlockRulesLookupMap;

```

### `JigsawStructureBlockTagRulesRegistry`
```
struct JigsawStructureBlockTagRulesRegistry
{
  JigsawStructureBlockTagRulesRegistry::BlockTagRulesRegistryMap mBlockTagRulesRegistry;
  JigsawStructureBlockTagRulesRegistry::BlockTagRulesLookupMap mBlockTagRuleLookupMap;
};

```

### `JigsawStructureBlockTagRulesRegistry::BlockTagRulesRegistryMap`
```
typedef std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolBlockTagRule>>>> JigsawStructureBlockTagRulesRegistry::BlockTagRulesRegistryMap;

```

### `JigsawStructureBlockTagRulesRegistry::BlockTagRulesLookupMap`
```
typedef std::unordered_map<std::string,const std::vector<std::unique_ptr<StructurePoolBlockTagRule>> *,std::hash<std::string>,std::equal_to<std::string >,std::allocator<std::pair<const std::string,const std::vector<std::unique_ptr<StructurePoolBlockTagRule>> *> > > JigsawStructureBlockTagRulesRegistry::BlockTagRulesLookupMap;

```

### `JigsawStructureActorRulesRegistry`
```
struct JigsawStructureActorRulesRegistry
{
  JigsawStructureActorRulesRegistry::ActorRulesRegistryMap mActorRulesRegistry;
  JigsawStructureActorRulesRegistry::ActorRulesLookupMap mActorRuleLookupMap;
};

```

### `JigsawStructureActorRulesRegistry::ActorRulesRegistryMap`
```
typedef std::vector<std::unique_ptr<std::vector<std::unique_ptr<StructurePoolActorRule>>>> JigsawStructureActorRulesRegistry::ActorRulesRegistryMap;

```

### `JigsawStructureActorRulesRegistry::ActorRulesLookupMap`
```
typedef std::unordered_map<std::string,const std::vector<std::unique_ptr<StructurePoolActorRule>> *,std::hash<std::string>,std::equal_to<std::string >,std::allocator<std::pair<const std::string,const std::vector<std::unique_ptr<StructurePoolActorRule>> *> > > JigsawStructureActorRulesRegistry::ActorRulesLookupMap;

```

### `JigsawStructureElementRegistry`
```
struct JigsawStructureElementRegistry
{
  JigsawStructureElementRegistry::StructureElementRegistry mElementRegistry;
  JigsawStructureElementRegistry::StructureElementLookupMap mElementLookupMap;
};

```

### `JigsawStructureElementRegistry::StructureElementRegistry`
```
typedef std::vector<std::unique_ptr<StructurePoolElement>> JigsawStructureElementRegistry::StructureElementRegistry;

```

### `JigsawStructureElementRegistry::StructureElementLookupMap`
```
typedef std::unordered_map<std::string,const StructurePoolElement *> JigsawStructureElementRegistry::StructureElementLookupMap;

```

### `JumpControl`
```
struct __cppobj JumpControl : Control
{
};

```

### `JumpControlDescription`
```
struct __cppobj __attribute__((aligned(8))) JumpControlDescription : ComponentDescription
{
  float mJumpPower;
};

```

### `JsonValidator`
```
struct JsonValidator
{
  __int8 gap0[1];
};

```

### `JsonUtil::SchemaConverterNode`
```
struct JsonUtil::SchemaConverterNode
{
  std::vector<JsonUtil::SchemaConverterNodeEntry> mStack;
};

```

### `JsonUtil::SchemaConverterNodeEntry`
```
struct JsonUtil::SchemaConverterNodeEntry
{
  std::string mName;
  Json::Value *mNode;
  size_t mIndex;
};

```

### `JukeboxBlockActor`
```
struct __cppobj __attribute__((aligned(8))) JukeboxBlockActor : RandomizableBlockActorContainer
{
  ItemStack mRecord;
  int mCount;
  bool mRecordingFinished;
  int mTicksPlaying;
};

```

### `JigsawBlockActor`
```
struct __cppobj JigsawBlockActor : BlockActor
{
};

```

### `JsonComponentSchema`
```
typedef JsonUtil::JsonSchemaObjectNode<JsonUtil::JsonParseState<JsonUtil::EmptyClass,BlockDefinition>,BlockDefinition> JsonComponentSchema;

```

### `JukeboxBlock`
```
struct __cppobj JukeboxBlock : ActorBlock
{
};

```

### `JigsawBlock`
```
struct __cppobj JigsawBlock : FaceDirectionalActorBlock
{
};

```

### `JunglePyramidPiece`
```
struct __cppobj __attribute__((aligned(8))) JunglePyramidPiece : ScatteredFeaturePiece
{
  bool mHasPlacedMainChest;
  bool mHasPlacedHiddenChest;
  bool mHasPlacedTrap[2];
};

```

### `Json::Path`
```
struct Json::Path
{
  Json::Path::Args args_;
};

```

### `Json::Path::Args`
```
typedef std::vector<Json::PathArgument> Json::Path::Args;

```

### `jsonValConversion<std::string >`
```
struct jsonValConversion<std::string >
{
  __int8 gap0[1];
};

```

