# U
### `uicontrolid_t<UIComponent>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mID
8 | (8) `unsigned __int64` | mBitId


### `UIAnimLayout::{ctor}::__l2::<lambda_b740528f05b815a1d9f33202085666a7>`
Offset | Type | Name
-|-|-|-


### `Urho3D::Vector3`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x_
4 | (4) `float` | y_
8 | (4) `float` | z_


### `Urho3D::Vector2`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x_
4 | (4) `float` | y_


### `Urho3D::Matrix4`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | m00_
4 | (4) `float` | m01_
8 | (4) `float` | m02_
12 | (4) `float` | m03_
16 | (4) `float` | m10_
20 | (4) `float` | m11_
24 | (4) `float` | m12_
28 | (4) `float` | m13_
32 | (4) `float` | m20_
36 | (4) `float` | m21_
40 | (4) `float` | m22_
44 | (4) `float` | m23_
48 | (4) `float` | m30_
52 | (4) `float` | m31_
56 | (4) `float` | m32_
60 | (4) `float` | m33_


### `utf8proc_property_struct`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | category
2 | (2) `__int16` | combining_class
4 | (2) `__int16` | bidi_class
6 | (2) `__int16` | decomp_type
8 | (8) `const int *` | decomp_mapping
16 | (1) `__int8` | _bf_10
17 | (3) `_BYTE[3]` | _padding_11
20 | (4) `int` | uppercase_mapping
24 | (4) `int` | lowercase_mapping
28 | (4) `int` | titlecase_mapping
32 | (4) `int` | comb1st_index
36 | (4) `int` | comb2nd_index
40 | (1) `__int8` | _bf_28
41 | (7) `_BYTE[7]` | _padding_29
48 | (8) `const int *` | casefold_mapping


### `unim_index`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int16 *` | map
8 | (1) `unsigned __int8` | bottom
9 | (1) `unsigned __int8` | top


### `Urho3D::Color`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r_
4 | (4) `float` | g_
8 | (4) `float` | b_
12 | (4) `float` | a_


### `Urho3D::IntVector3`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x_
4 | (4) `int` | y_
8 | (4) `int` | z_


### `Urho3D::IntVector2`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x_
4 | (4) `int` | y_


### `Urho3D::Matrix3`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | m00_
4 | (4) `float` | m01_
8 | (4) `float` | m02_
12 | (4) `float` | m10_
16 | (4) `float` | m11_
20 | (4) `float` | m12_
24 | (4) `float` | m20_
28 | (4) `float` | m21_
32 | (4) `float` | m22_


### `Urho3D::StringHash`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | value_


### `Urho3D::Rect`
Offset | Type | Name
-|-|-|-
0 | (8) `Urho3D::Vector2` | min_
8 | (8) `Urho3D::Vector2` | max_


### `Urho3D::Matrix3x4`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | m00_
4 | (4) `float` | m01_
8 | (4) `float` | m02_
12 | (4) `float` | m03_
16 | (4) `float` | m10_
20 | (4) `float` | m11_
24 | (4) `float` | m12_
28 | (4) `float` | m13_
32 | (4) `float` | m20_
36 | (4) `float` | m21_
40 | (4) `float` | m22_
44 | (4) `float` | m23_


### `Urho3D::IntRect`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | left_
4 | (4) `int` | top_
8 | (4) `int` | right_
12 | (4) `int` | bottom_


### `Urho3D::Quaternion`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | w_
4 | (4) `float` | x_
8 | (4) `float` | y_
12 | (4) `float` | z_


### `Urho3D::Vector4`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x_
4 | (4) `float` | y_
8 | (4) `float` | z_
12 | (4) `float` | w_


### `Urho3D::AnimatedModelRenderDispatcher`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,Urho3D::AnimatedModelRender>` | mRenderMap_
64 | (64) `std::unordered_map<std::string,unsigned __int64>` | mRenderNum_


### `us_f0_lr_term_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | feature
8 | (4) `const float` | start
12 | (4) `const float` | mid
16 | (4) `const float` | end
24 | (8) `const char *` | type


### `UIResolvedDef`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIgnored
8 | (32) `const std::string` | mDefNamespace
40 | (32) `const std::string` | mDefName
72 | (8) `const Json::Value *` | mBaseVal
80 | (8) `const Json::Value *` | mOverrideVal
88 | (16) `Json::Value` | mVariables
104 | (8) `std::vector<Json::Value *> *` | mVariablesStack
112 | (16) `std::set<std::string,Util::span_less,std::allocator<std::string > >` | mUnvalidatedProperties


### `UNWIND_INFO_HDR`
Offset | Type | Name
-|-|-|-
0 | (1) `` | Ver3_Flags
1 | (1) `` | PrologSize
2 | (1) `` | CntUnwindCodes
3 | (1) `` | FrReg_FrRegOff


### `UNWIND_CODE`
Offset | Type | Name
-|-|-|-
0 | (1) `` | PrologOff
1 | (1) `` | OpCode_OpInfo


### `UnwindMapEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `` | toState
4 | (4) `` | action


### `Util::Url::Components`
Offset | Type | Name
-|-|-|-
0 | (40) `std::optional<std::string >` | scheme
40 | (40) `std::optional<std::string >` | authority
80 | (40) `std::optional<std::string >` | path
120 | (40) `std::optional<std::string >` | query
160 | (40) `std::optional<std::string >` | fragment


### `UIScreenContext`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | xm
4 | (4) `const int` | ym
8 | (4) `const float` | a


### `UiExpression`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ExprToken>` | mTokens
24 | (1) `bool` | mIsStatic


### `ui::LayoutOffset`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ui::AxisOffset>` | noAutoScaleX
24 | (24) `std::vector<ui::AxisOffset>` | noAutoScaleY
48 | (4) `ui::LayoutAxisOffsetContainerType` | noAutoScaleXType
52 | (4) `ui::LayoutAxisOffsetContainerType` | noAutoScaleYType
56 | (24) `std::vector<ui::AxisOffset>` | x
80 | (24) `std::vector<ui::AxisOffset>` | y
104 | (4) `ui::LayoutAxisOffsetContainerType` | xType
108 | (4) `ui::LayoutAxisOffsetContainerType` | yType


### `UITextureInfoPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `UITextureInfoPtr_vtbl *` | __vftable
8 | (8) `const UITextureInfo *` | mUITextureInfo
16 | (8) `UIRepository *` | mGroup
24 | (56) `ResourceLocation` | mResourceLocation


### `UIPropertyBag`
Offset | Type | Name
-|-|-|-
0 | (8) `UIPropertyBag_vtbl *` | __vftable
8 | (24) `PropertyBag` | baseclass_8
32 | (24) `std::vector<std::pair<std::string,std::vector<UIPropertyBag::PropertyChangedNotificationInfo> >>` | mPropertyChangedNotificationInfoMap


### `UIAnimationComponent::NewAnimation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<UIAnim>` | newAnim
16 | (4) `float` | lastAnimDuration
20 | (4) `float` | lastAnimTime


### `ui::AxisOffset`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | type
4 | (4) `float` | value
8 | (4) `ui::LayoutAxisOperation` | operation


### `UIPropertyBag::registerForPropertyChangedNotification::__l2::<lambda_7e52e4d85eb4d187d33f31333af04fdb>::()::__l2::<lambda_cbc2fb54f5f402da5c9469866231f08c>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<void __cdecl(std::weak_ptr<UIControl> const &,gsl::basic_string_span<char const ,-1>,Json::Value const &,UIPropertyBag::ContextObject)>` | callback
64 | (32) `const UiExpression` | sourcePropertyName
96 | (8) `UIPropertyBag *const` | __this


### `UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_8edab51aeee724a1c610a07b9b257e12>`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | dropdownName
32 | (8) `UserProfileCardScreenController *const` | __this


### `UIControl`
Offset | Type | Name
-|-|-|-
0 | (8) `UIControl_vtbl *` | __vftable
8 | (16) `std::enable_shared_from_this<UIControl>` | baseclass_8
24 | (1) `bool` | sizeFlag
25 | (1) `bool` | posFlag
32 | (40) `BindInfo` | mBindInfo
72 | (1) `bool` | changeAutoScale2Zero
76 | (4) `_BYTE[4]` | defType
80 | (16) `std::weak_ptr<UIControl>` | mFinalLayoutCtrl
96 | (32) `std::string` | mName
128 | (8) `glm::tvec2<float,0>` | mParentRelativePosition
136 | (8) `glm::tvec2<float,0>` | mSize
144 | (8) `glm::tvec2<float,0>` | mMinSize
152 | (8) `glm::tvec2<float,0>` | mMaxSize
160 | (4) `float` | mAlpha
164 | (4) `int` | mZOrder
168 | (4) `int` | mLayer
172 | (8) `Vec2` | mClipOffset
180 | (1) `__int8` | _bf_b4
181 | (1) `__int8` | _padding_b5
182 | (2) `__int16` | _padding_b6
184 | (1) `__int8` | _bf_b8
185 | (1) `__int8` | _padding_b9
186 | (2) `__int16` | _padding_ba
188 | (2) `__int16` | _bf_bc
190 | (2) `__int16` | _padding_be
192 | (8) `glm::tvec2<float,0>` | mCachedPosition
200 | (4) `unsigned int` | mClipChangeEventId
208 | (8) `std::unique_ptr<UIPropertyBag>` | mPropertyBag
216 | (16) `std::weak_ptr<UIControl>` | mParent
232 | (24) `std::vector<std::shared_ptr<UIControl>>` | mChildren
256 | (8) `unsigned __int64` | mComponentsInUse
264 | (24) `std::vector<std::unique_ptr<UIComponent>>` | mComponents
288 | (24) `std::vector<RenderableComponent *>` | mRenderableComponentLookup
312 | (24) `std::vector<UIControl::ControlResolutionInfo>` | mControlResolvers
336 | (24) `std::vector<std::function<void __cdecl(UIControl &)>>` | mPostCreateVector
360 | (8) `ControlScreenAction *` | mControlScreenAction
368 | (4) `int` | mControlCollectionFlag
376 | (16) `std::weak_ptr<UIControl>` | mModalAncestor


### `UIRenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `UIRenderContext_vtbl *` | __vftable


### `UIMeasureStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `UIMeasureStrategy_vtbl *` | __vftable


### `UIDefRepository::loadDefsList::__l2::<lambda_1ecc128b6a504e1674127a91f414fc08>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::vector<UIDefRepository::DefEntry> >` | allDefEntriesPtr
16 | (16) `std::shared_ptr<std::unordered_map<std::string,UIDefNamespace> >` | defNamespaces
32 | (8) `UIDefRepository *const` | __this
40 | (16) `std::shared_ptr<std::vector<PackReport> >` | packReportsPtr
56 | (8) `const ResourcePackStack *` | packStack
64 | (64) `std::function<void __cdecl(std::vector<PackReport> &)>` | onReportsReady


### `UIDefRepository::_queueFinishLoad::__l5::<lambda_8c79f890e388074120223c816a5a3204>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::vector<PackReport> >` | packReportsPtr
16 | (64) `std::function<void __cdecl(std::vector<PackReport> &)>` | onReportsReady


### `UIDefRepository::validateDefEntries::__l13::<lambda_507eaf82f275a1afc1e36b521629d2d9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::vector<PackReport> >` | packReportsPtr
16 | (16) `std::shared_ptr<ResourcePackStack const >` | packStack
32 | (64) `std::function<void __cdecl(std::vector<PackReport> &)>` | onReportsReady


### `UIDefRepository::_collectAllDefEntries::__l33::<lambda_e42ddb60c01723a5881424d6dd583a07>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::vector<UIDefRepository::DefEntry> >` | allDefEntries
16 | (16) `std::shared_ptr<std::vector<PackReport> >` | packReports
32 | (16) `std::shared_ptr<std::vector<PackReport> >` | fileReports
48 | (16) `std::shared_ptr<std::vector<UIDefRepository::DefEntry> >` | fileDefEntries
64 | (1) `const bool` | loadingUI


### `UIDefRepository::DefEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | collectionIndex
8 | (32) `std::string` | ns
40 | (32) `std::string` | name
72 | (32) `std::string` | refNs
104 | (32) `std::string` | refName
136 | (16) `Json::Value` | jsonVal


### `ui::AxisOffsetContainer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ui::AxisOffset>` | axisOffsets
24 | (4) `ui::LayoutAxisOffsetContainerType` | containerType


### `UIIndexInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | index
8 | (8) `const Json::Value *` | value
16 | (1) `bool` | removed


### `UIPackError`
Offset | Type | Name
-|-|-|-
0 | (40) `PackError` | baseclass_0


### `UserAuthentication::getGlobalCertificate::__l2::<lambda_75f04232756511bb1d450f368ea2c7cb>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<UserAuthentication>` | weakThis
16 | (64) `std::function<void __cdecl(std::unique_ptr<Certificate>)>` | callback


### `UserAuthentication::getGlobalCertificate::__l2::<lambda_75f04232756511bb1d450f368ea2c7cb>::()::__l5::<lambda_fce1549d43fd9f2db1bffbfa91d8f005>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<UserAuthentication>` | weakThis
16 | (1) `bool` | success
24 | (64) `std::function<void __cdecl(std::unique_ptr<Certificate>)>` | callback
88 | (32) `std::string` | rawCertificate


### `UnverifiedCertificate`
Offset | Type | Name
-|-|-|-
0 | (128) `const WebToken` | mRawToken
128 | (8) `std::unique_ptr<UnverifiedCertificate>` | mParentUnverifiedCertificate


### `UpdateAttributesPacket::AttributeData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mCurrentValue
4 | (4) `float` | mMinValue
8 | (4) `float` | mMaxValue
12 | (4) `float` | mDefaultValue
16 | (48) `HashedString` | mName


### `UpdateAttributesPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (24) `std::vector<UpdateAttributesPacket::AttributeData>` | mAttributeData
72 | (8) `unsigned __int64` | mTick


### `UpdateTradePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `ContainerID` | mContainerId
41 | (1) `ContainerType` | mType
48 | (32) `std::string` | mDisplayName
80 | (4) `int` | mSize
84 | (4) `int` | mTraderTier
88 | (8) `ActorUniqueID` | mEntityUniqueID
96 | (8) `ActorUniqueID` | mLastTradingPlayer
104 | (24) `CompoundTag` | mData
128 | (1) `bool` | mUseNewTradeScreen
129 | (1) `bool` | mUsingEconomyTrade


### `Urho3D::ColorFrame`
Offset | Type | Name
-|-|-|-
0 | (32) `InterpolableFrame<Urho3D::Color>` | baseclass_0


### `Urho3D::EmitterPathFrame`
Offset | Type | Name
-|-|-|-
0 | (24) `InterpolableFrame<Urho3D::Vector3>` | baseclass_0


### `Urho3D::BoundingBox`
Offset | Type | Name
-|-|-|-
0 | (12) `Urho3D::Vector3` | min_
12 | (4) `float` | dummyMin_
16 | (12) `Urho3D::Vector3` | max_
28 | (4) `float` | dummyMax_


### `Urho3D::AnimatedModelRender`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Urho3D::Geometry *>` | mGeometryVector_
24 | (600) `Urho3D::GeometryGroup` | mGeometryGroup_


### `Urho3D::GeometryGroup`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<int>` | geometryIds
24 | (24) `std::vector<Urho3D::Geometry *>` | geometrys
48 | (64) `std::unordered_map<int,Urho3D::ModelPart>` | modelParts_
112 | (488) `Urho3D::ModelPartGroup` | modelPartGroup_


### `Urho3D::ModelPartGroup`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Urho3D::ModelPart const *>` | modelParts
24 | (1) `bool` | useFieldBoneId
28 | (4) `int` | vertexCount
32 | (4) `int` | indexCount
36 | (4) `int` | uvCount
40 | (432) `mce::Mesh` | mesh_
472 | (16) `std::optional<unsigned __int64>` | mMetadataId


### `Urho3D::Animation`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isGlobal
8 | (32) `std::string` | animationName_
40 | (4) `Urho3D::StringHash` | animationNameHash_
44 | (4) `float` | length_
48 | (16) `std::map<Urho3D::StringHash,Urho3D::AnimationTrack>` | tracks_
64 | (24) `std::vector<Urho3D::AnimationTriggerPoint>` | triggers_
88 | (8) `unsigned __int64` | memory_


### `Urho3D::AnimationStateTrack`
Offset | Type | Name
-|-|-|-
0 | (8) `const Urho3D::AnimationTrack *` | track_
8 | (8) `Urho3D::Bone *` | bone_
16 | (4) `float` | weight_
20 | (4) `unsigned int` | keyFrame_
24 | (12) `Urho3D::Vector3` | newPosition_
36 | (16) `Urho3D::Quaternion` | newRotation_
52 | (12) `Urho3D::Vector3` | newScale_
64 | (1) `bool` | shouldPlayAni
65 | (1) `bool` | shouldApplyTrack


### `Urho3D::Node`
Offset | Type | Name
-|-|-|-
0 | (12) `Urho3D::Vector3` | position_
12 | (16) `Urho3D::Quaternion` | rotation_
28 | (12) `Urho3D::Vector3` | scale_
40 | (8) `Urho3D::Node *` | parent_
48 | (24) `std::vector<Urho3D::Node *>` | children_
72 | (1) `bool` | dirty_
76 | (48) `Urho3D::Matrix3x4` | worldTransform_
124 | (16) `Urho3D::Quaternion` | worldRotation_
140 | (1) `bool` | valid_


### `Urho3D::EmitterScaleFrame`
Offset | Type | Name
-|-|-|-
0 | (16) `InterpolableFrame<float>` | baseclass_0


### `Urho3D::ParticleEmitter::RenderData`
Offset | Type | Name
-|-|-|-
0 | (16) `Urho3D::Color` | color
16 | (48) `Vec3[4]` | meshPos
64 | (4) `float` | u0
68 | (4) `float` | v0
72 | (4) `float` | u1
76 | (4) `float` | v1
80 | (4) `int` | worldPosIndex


### `unz_file_info64_s`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | version
4 | (4) `unsigned int` | version_needed
8 | (4) `unsigned int` | flag
12 | (4) `unsigned int` | compression_method
16 | (4) `unsigned int` | dosDate
20 | (4) `unsigned int` | crc
24 | (8) `unsigned __int64` | compressed_size
32 | (8) `unsigned __int64` | uncompressed_size
40 | (4) `unsigned int` | size_filename
44 | (4) `unsigned int` | size_file_extra
48 | (4) `unsigned int` | size_file_comment
52 | (4) `unsigned int` | disk_num_start
56 | (4) `unsigned int` | internal_fa
60 | (4) `unsigned int` | external_fa
64 | (24) `tm_unz_s` | tmu_date


### `U`
Offset | Type | Name
-|-|-|-
0 | (8) `long double` | d
1 | (8) `unsigned int[2]` | L


### `UPNPInterface::ConnectionStateListener`
```
struct __cppobj UPNPInterface::ConnectionStateListener
{
  UPNPInterface::ConnectionStateListener_vtbl *__vftable /*VFT*/;
};

```

### `UPNPInterface::ConnectionStateListener_vtbl`
```
struct /*VFT*/ UPNPInterface::ConnectionStateListener_vtbl
{
  void (__fastcall *~ConnectionStateListener)(UPNPInterface::ConnectionStateListener *this);
  void (__fastcall *onConnectionStateChanged)(UPNPInterface::ConnectionStateListener *this, const std::string *, const std::string *, unsigned int, unsigned int, unsigned int, const std::string *);
};

```

### `UPNPPortMappingResult`
```
struct UPNPPortMappingResult
{
  bool bUPNPSupported;
  char hostIPAddress[256];
  unsigned __int16 externalPort;
  unsigned __int16 internalPort;
};

```

### `UPnPResultState<UPNPPortMappingResult>`
```
struct __cppobj UPnPResultState<UPNPPortMappingResult>
{
  UPNPPortMappingResult result;
  UpnpState state;
  bool isValid;
  AsyncTracker tracker;
};

```

### `UPNPExternalIPResult`
```
struct UPNPExternalIPResult
{
  bool bUPNPSupported;
  char hostIPAddress[256];
};

```

### `UPnPResultState<UPNPExternalIPResult>`
```
struct __cppobj UPnPResultState<UPNPExternalIPResult>
{
  UPNPExternalIPResult result;
  UpnpState state;
  bool isValid;
  AsyncTracker tracker;
};

```

### `UPNPInterface`
```
struct __cppobj UPNPInterface : NetworkSuspendResumeListener
{
  std::vector<UPNPInterface::ConnectionStateListener *> mConnectionStateListeners;
  UPnPResultState<UPNPPortMappingResult> mUPnPPortMappingv4;
  UPnPResultState<UPNPPortMappingResult> mUPnPPortMappingv6;
  UPnPResultState<UPNPExternalIPResult> mUPnPExternalIP;
  MPMCQueue<std::function<void __cdecl(void)> > mCompletedQueue;
};

```

### `UPNPInterface_vtbl`
```
struct /*VFT*/ UPNPInterface_vtbl
{
  void (__fastcall *~NetworkSuspendResumeListener)(NetworkSuspendResumeListener *this);
  void (__fastcall *onSuspend)(NetworkSuspendResumeListener *this);
  void (__fastcall *onResume)(NetworkSuspendResumeListener *this);
};

```

### `UpdateSoftEnumPacket`
```
const struct __cppobj __declspec(align(8)) UpdateSoftEnumPacket : Packet
{
  std::string mEnumName;
  std::vector<std::string> mValues;
  _BYTE mType[1];
};

```

### `UpdateSoftEnumPacket_vtbl`
```
struct /*VFT*/ UpdateSoftEnumPacket_vtbl
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

### `UpdateEquipPacket`
```
const struct __cppobj UpdateEquipPacket : Packet
{
  ContainerID mContainerId;
  ContainerType mType;
  int mSize;
  ActorUniqueID mEntityUniqueID;
  CompoundTag mData;
};

```

### `UpdateEquipPacket_vtbl`
```
struct /*VFT*/ UpdateEquipPacket_vtbl
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

### `UpdateTradePacket_vtbl`
```
struct /*VFT*/ UpdateTradePacket_vtbl
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

### `UpdateAttributesPacket_vtbl`
```
struct /*VFT*/ UpdateAttributesPacket_vtbl
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

### `UpdateBlockPacket`
```
struct __cppobj UpdateBlockPacket : Packet
{
  NetworkBlockPosition mPos;
  unsigned int mLayer;
  unsigned __int8 mUpdateFlags;
  unsigned int mRuntimeId;
};

```

### `UpdateBlockPacket_vtbl`
```
struct /*VFT*/ UpdateBlockPacket_vtbl
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

### `UpdateBlockSyncedPacket`
```
struct __cppobj UpdateBlockSyncedPacket : UpdateBlockPacket
{
  ActorBlockSyncMessage mEntityBlockSyncMessage;
};

```

### `UpdateBlockSyncedPacket_vtbl`
```
struct /*VFT*/ UpdateBlockSyncedPacket_vtbl
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

### `UpdatePlayerGameTypePacket`
```
const struct __cppobj UpdatePlayerGameTypePacket : Packet
{
  GameType mPlayerGameType;
  ActorUniqueID mTargetPlayer;
};

```

### `UpdatePlayerGameTypePacket_vtbl`
```
struct /*VFT*/ UpdatePlayerGameTypePacket_vtbl
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

### `UriListener`
```
struct __cppobj UriListener
{
  UriListener_vtbl *__vftable /*VFT*/;
};

```

### `UriListener_vtbl`
```
struct /*VFT*/ UriListener_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `UIDefNamespace`
```
struct __cppobj UIDefNamespace
{
  std::string mName;
  std::unordered_map<std::string,Json::Value> mDefs;
};

```

### `UIDefRepository`
```
struct __cppobj UIDefRepository
{
  ResourceLoadManager *mResourceLoadManager;
  std::unordered_map<std::string,UIDefNamespace> mDefNamespaces;
  Json::Value mGlobalVariables;
  std::shared_mutex mMutex;
};

```

### `ui::SliceSize`
```
struct __cppobj ui::SliceSize
{
  float left;
  float top;
  float right;
  float bottom;
};

```

### `UITextureInfo`
```
struct __cppobj __declspec(align(8)) UITextureInfo
{
  ui::SliceSize mNineslice;
  bool mHasNineslice;
  glm::tvec2<float,0> mBaseUVSize;
  std::vector<AsepriteFrameInformation> mAsepriteFrames;
  int mTotalDurationInMilliseconds;
};

```

### `UITextureInfoPtr_vtbl`
```
struct /*VFT*/ UITextureInfoPtr_vtbl
{
  void (__fastcall *~UITextureInfoPtr)(UITextureInfoPtr *this);
};

```

### `UIRepository`
```
struct __cppobj UIRepository
{
  std::map<ResourceLocation,UITextureInfo> mLoadedUITextureInfo;
  ResourceLoader *mResourceLoader;
  std::unordered_set<UITextureInfoPtr *> mRegisteredPtrs;
};

```

### `UIControl_vtbl`
```
struct /*VFT*/ UIControl_vtbl
{
  void (__fastcall *~UIControl)(UIControl *this);
};

```

### `UIPropertyBag_vtbl`
```
struct /*VFT*/ UIPropertyBag_vtbl
{
  void (__fastcall *~UIPropertyBag)(UIPropertyBag *this);
};

```

### `UIPropertyBag::ContextObject`
```
struct UIPropertyBag::ContextObject
{
  int count;
};

```

### `UIPropertyBag::PropertyChangedNotificationInfo`
```
struct __cppobj UIPropertyBag::PropertyChangedNotificationInfo
{
  std::string targetPropertyName;
  std::weak_ptr<UIControl> targetControl;
  std::function<void __cdecl(std::weak_ptr<UIControl> const &,gsl::basic_string_span<char const ,-1>,Json::Value const &,UIPropertyBag::ContextObject)> callback;
};

```

### `UIComponent`
```
struct __cppobj UIComponent
{
  UIComponent_vtbl *__vftable /*VFT*/;
  UIControl *mOwner;
};

```

### `UIMeasureStrategy_vtbl`
```
struct /*VFT*/ UIMeasureStrategy_vtbl
{
  void (__fastcall *~UIMeasureStrategy)(UIMeasureStrategy *this);
  MeasureResult *(__fastcall *measureText)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, int, int, const TextMeasureData *, const CaretMeasureData *);
  MeasureResult *(__fastcall *measureTextHeight)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, int, const TextMeasureData *, const CaretMeasureData *);
  MeasureResult *(__fastcall *measureTextWidth)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, const TextMeasureData *, const CaretMeasureData *);
  std::string *(__fastcall *filterProfanityFromText)(UIMeasureStrategy *this, std::string *result, const std::string *, const bool);
};

```

### `UIAnimationController::AnimationUIControlFunctionCallback`
```
struct __cppobj UIAnimationController::AnimationUIControlFunctionCallback
{
  std::weak_ptr<UIControl> control;
  std::function<enum ui::AnimationStatus __cdecl(mce::TimeStep const &)> function;
};

```

### `UIAnimationController`
```
struct __cppobj UIAnimationController
{
  std::vector<UIAnimationController::AnimationUIControlFunctionCallback> animationListFixedTimestep;
  std::vector<UIAnimationController::AnimationUIControlFunctionCallback> animationListRenderTimestep;
};

```

### `UIComponent_vtbl`
```
struct /*VFT*/ UIComponent_vtbl
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

### `UIControl::ControlResolutionInfo`
```
struct __cppobj UIControl::ControlResolutionInfo
{
  std::string targetControlName;
  ui::NameResolutionScope scope;
  std::function<void __cdecl(UIControl &,std::shared_ptr<UIControl>)> setter;
};

```

### `UISoundPlayer`
```
const struct __cppobj UISoundPlayer
{
  UISoundPlayer_vtbl *__vftable /*VFT*/;
};

```

### `UISoundPlayer_vtbl`
```
struct /*VFT*/ UISoundPlayer_vtbl
{
  void (__fastcall *~UISoundPlayer)(UISoundPlayer *this);
  void (__fastcall *play)(UISoundPlayer *this, const std::string *, float, float);
};

```

### `UIControlFactory`
```
struct __cppobj UIControlFactory : std::enable_shared_from_this<UIControlFactory>
{
  const UIDefRepository *mUIDefRepository;
  const UISoundPlayer *mSoundPlayer;
  std::string mCurrentNamespace;
  Json::Value mGlobalVars;
  std::vector<Json::Value *> mVariablesStack;
  FontHandle mFontHandle;
  FontHandle mRuneFontHandle;
  FontHandle mUnicodeFontHandle;
  FontHandle mSmoothFontHandle;
  bool mLowMemoryMode;
  std::weak_ptr<UIControl> mInitialSelectedControl;
};

```

### `UIFrameUpdateContext`
```
struct __cppobj UIFrameUpdateContext
{
};

```

### `UICustomRenderer`
```
struct __cppobj __declspec(align(8)) UICustomRenderer
{
  UICustomRenderer_vtbl *__vftable /*VFT*/;
  float mPropagatedAlpha;
};

```

### `UIRenderContext_vtbl`
```
struct /*VFT*/ UIRenderContext_vtbl
{
  void (__fastcall *~UIRenderContext)(UIRenderContext *this);
  int (__fastcall *getLineLength)(UIRenderContext *this, Font *, const std::string *, float, bool);
  float (__fastcall *getTextAlpha)(UIRenderContext *this);
  void (__fastcall *setTextAlpha)(UIRenderContext *this, float);
  void (__fastcall *drawDebugText)(UIRenderContext *this, const RectangleArea *, const std::string *, const mce::Color *, float, ui::TextAlignment, const TextMeasureData *, const CaretMeasureData *);
  void (__fastcall *drawText)(UIRenderContext *this, Font *, const RectangleArea *, const std::string *, const mce::Color *, float, const mce::Color *, const glm::tvec2<float,0> *, ui::TextAlignment, const TextMeasureData *, const CaretMeasureData *);
  void (__fastcall *flushText)(UIRenderContext *this, float);
  void (__fastcall *drawImage)(UIRenderContext *this, const mce::TexturePtr *, const glm::tvec2<float,0> *, const glm::tvec2<float,0> *, const glm::tvec2<float,0> *, const glm::tvec2<float,0> *, int);
  void (__fastcall *drawNineslice)(UIRenderContext *this, const mce::TexturePtr *, const NinesliceInfo *, int);
  void (__fastcall *flushImages)(UIRenderContext *this, const mce::Color *, float, const HashedString *);
  void (__fastcall *beginSharedMeshBatch)(UIRenderContext *this, ComponentRenderBatch *);
  void (__fastcall *endSharedMeshBatch)(UIRenderContext *this, ComponentRenderBatch *);
  void (__fastcall *drawRectangle)(UIRenderContext *this, const RectangleArea *, const mce::Color *, float, int);
  void (__fastcall *fillRectangle)(UIRenderContext *this, const RectangleArea *, const mce::Color *, float);
  void (__fastcall *increaseStencilRef)(UIRenderContext *this);
  void (__fastcall *decreaseStencilRef)(UIRenderContext *this);
  void (__fastcall *resetStencilRef)(UIRenderContext *this);
  void (__fastcall *fillRectangleStencil)(UIRenderContext *this, const RectangleArea *);
  void (__fastcall *enableScissorTest)(UIRenderContext *this, const RectangleArea *);
  void (__fastcall *disableScissorTest)(UIRenderContext *this);
  void (__fastcall *setClippingRectangle)(UIRenderContext *this, const RectangleArea *);
  void (__fastcall *setFullClippingRectangle)(UIRenderContext *this);
  void (__fastcall *saveCurrentClippingRectangle)(UIRenderContext *this);
  void (__fastcall *restoreSavedClippingRectangle)(UIRenderContext *this);
  RectangleArea *(__fastcall *getFullClippingRectangle)(UIRenderContext *this, RectangleArea *result);
  bool (__fastcall *updateCustom)(UIRenderContext *this, gsl::not_null<CustomRenderComponent *>);
  void (__fastcall *renderCustom)(UIRenderContext *this, gsl::not_null<CustomRenderComponent *>, int, RectangleArea *);
  void (__fastcall *cleanup)(UIRenderContext *this);
  void (__fastcall *removePersistentMeshes)(UIRenderContext *this);
  mce::TexturePtr *(__fastcall *getTexture)(UIRenderContext *this, mce::TexturePtr *result, const ResourceLocation *, bool);
  mce::TexturePtr *(__fastcall *getZippedTexture)(UIRenderContext *this, mce::TexturePtr *result, const Core::Path *, const ResourceLocation *, bool);
  bool (__fastcall *unloadTexture)(UIRenderContext *this, const ResourceLocation *);
  UITextureInfoPtr *(__fastcall *getUITextureInfo)(UIRenderContext *this, UITextureInfoPtr *result, const ResourceLocation *, bool);
  void (__fastcall *touchTexture)(UIRenderContext *this, const ResourceLocation *);
  UIMeasureStrategy *(__fastcall *getMeasureStrategy)(UIRenderContext *this);
  void (__fastcall *flushImagesUVZeroOneBase)(UIRenderContext *this, const mce::Color *, float, const std::string *, int);
  bool (__fastcall *hasTexture)(UIRenderContext *this, const ResourceLocation *);
  void (__fastcall *snapImageSizeToGrid)(UIRenderContext *this, glm::tvec2<float,0> *);
  void (__fastcall *snapImagePositionToGrid)(UIRenderContext *this, glm::tvec2<float,0> *);
  void (__fastcall *notifyImageEstimate)(UIRenderContext *this, unsigned __int64);
};

```

### `UIScene`
```
struct __cppobj UIScene : BaseScreen
{
  IClientInstance *mClientInstance;
  std::unique_ptr<ScreenView> mScreenView;
  std::function<void __cdecl(void)> mOnInitializedCallback;
  std::shared_ptr<AbstractSceneProxy> mProxy;
};

```

### `UICustomRenderer_vtbl`
```
struct /*VFT*/ UICustomRenderer_vtbl
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
};

```

### `UIScene_vtbl`
```
struct /*VFT*/ UIScene_vtbl
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
  void (__fastcall *setupForRendering)(BaseScreen *this, ScreenContext *);
  void (__fastcall *cleanupForRendering)(BaseScreen *this, ScreenContext *);
  void (__fastcall *setScreenSetupCleanup)(BaseScreen *this, std::unique_ptr<AbstractScreenSetupCleanupStrategy>);
};

```

### `UserAuthentication`
```
struct __cppobj UserAuthentication : Bedrock::Threading::EnableQueueForMainThread, std::enable_shared_from_this<UserAuthentication>
{
  LocalAuthentication mLocalAuthentication;
  std::weak_ptr<IClientInstance> mClient;
  std::unique_ptr<UserAuthentication::UserListObserver> mUserListObserver;
  unsigned __int64 mClientRandomId;
  std::shared_ptr<Options> mOptions;
  Bedrock::PubSub::ScopedSubscription mUsernameOptionSubscription;
  std::shared_ptr<web::http::client::http_client> mHttpClient;
};

```

### `UserAuthentication::UserListObserver`
```
struct __cppobj UserAuthentication::UserListObserver : Social::UserListObserver
{
  UserAuthentication *mUserAuthentication;
};

```

### `UserAuthentication::UserListObserver_vtbl`
```
struct /*VFT*/ UserAuthentication::UserListObserver_vtbl
{
  void (__fastcall *~Observer<Social::UserListObserver,Core::SingleThreadedLock>)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onUserAdded)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *);
  void (__fastcall *onUserRemoved)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *);
  void (__fastcall *onUserStorageAreaChanged)(Social::UserListObserver *this, const std::shared_ptr<Social::User> *, std::shared_ptr<Core::FileStorageArea> *);
};

```

### `UserAuthentication_vtbl`
```
struct /*VFT*/ UserAuthentication_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `UIProfanityContext`
```
const struct __cppobj UIProfanityContext
{
  UIProfanityContext_vtbl *__vftable /*VFT*/;
  _BYTE mFilterMask[4];
  std::unordered_map<std::string,int> mProfanityExactMap;
  std::unordered_set<std::string> mProfanityContainsSet;
};

```

### `UIProfanityContext_vtbl`
```
struct /*VFT*/ UIProfanityContext_vtbl
{
  void (__fastcall *~UIProfanityContext)(UIProfanityContext *this);
  std::string *(__fastcall *_doMaskProfanity)(UIProfanityContext *this, std::string *result, const std::string *);
  bool (__fastcall *_doFindProfanity)(UIProfanityContext *this, const std::string *);
};

```

### `UIEventListener`
```
struct __cppobj UIEventListener
{
  UIEventListener_vtbl *__vftable /*VFT*/;
};

```

### `UIEventListener_vtbl`
```
struct /*VFT*/ UIEventListener_vtbl
{
  void (__fastcall *~UIEventListener)(UIEventListener *this);
  EventResult (__fastcall *onPushedScreen)(UIEventListener *this, AbstractScene *);
  EventResult (__fastcall *onPoppedScreen)(UIEventListener *this, AbstractScene *);
};

```

### `UIEventCoordinator`
```
struct __cppobj UIEventCoordinator : EventCoordinator<UIEventListener>
{
};

```

### `Util::EntityComponentProcessor`
```
struct __cppobj Util::EntityComponentProcessor
{
  Util::EntityComponentProcessor_vtbl *__vftable /*VFT*/;
};

```

### `Util::EntityComponentProcessor_vtbl`
```
struct /*VFT*/ Util::EntityComponentProcessor_vtbl
{
  void (__fastcall *~EntityComponentProcessor)(Util::EntityComponentProcessor *this);
  bool (__fastcall *canProcess)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
  void (__fastcall *process)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
};

```

### `Util::XXHash::XXH32_state_s`
```
struct Util::XXHash::XXH32_state_s
{
  unsigned int total_len_32;
  unsigned int large_len;
  unsigned int v1;
  unsigned int v2;
  unsigned int v3;
  unsigned int v4;
  unsigned int mem32[4];
  unsigned int memsize;
  unsigned int reserved;
};

```

### `Util::XXHash::XXH32_canonical_t`
```
struct Util::XXHash::XXH32_canonical_t
{
  unsigned __int8 digest[4];
};

```

### `Util::XXHash::XXH64_state_s`
```
struct __declspec(align(8)) Util::XXHash::XXH64_state_s
{
  unsigned __int64 total_len;
  unsigned __int64 v1;
  unsigned __int64 v2;
  unsigned __int64 v3;
  unsigned __int64 v4;
  unsigned __int64 mem64[4];
  unsigned int memsize;
  unsigned int reserved[2];
};

```

### `Util::XXHash::XXH64_canonical_t`
```
struct Util::XXHash::XXH64_canonical_t
{
  unsigned __int8 digest[8];
};

```

### `UserManagementModalScreenData`
```
struct __cppobj __declspec(align(4)) UserManagementModalScreenData : ModalScreenData
{
  ModalWindowSize windowSize;
  bool defaultFocusOnLeftButton;
};

```

### `Util::span_less`
```
struct __cppobj Util::span_less
{
};

```

### `UIResolvedDefValConversion<mce::Color>`
```
struct __cppobj UIResolvedDefValConversion<mce::Color>
{
};

```

### `UIResolvedDefValConversion<float>`
```
struct __cppobj UIResolvedDefValConversion<float>
{
};

```

### `UIResolvedDefValConversion<ui::LayoutOffset>`
```
struct __cppobj UIResolvedDefValConversion<ui::LayoutOffset>
{
};

```

### `UIResolvedDefValConversion<std::string >`
```
struct __cppobj UIResolvedDefValConversion<std::string >
{
};

```

### `UIResolvedDefValConversion<glm::tvec2<float,0> >`
```
struct __cppobj UIResolvedDefValConversion<glm::tvec2<float,0> >
{
};

```

### `UIAnim`
```
struct __cppobj UIAnim
{
  UIAnim_vtbl *__vftable /*VFT*/;
  ui::AnimationType mAnimType;
  float mTime;
  std::function<float __cdecl(float,float,float)> mEase;
  UIAnim::State mState;
  unsigned int mAnimEndEventId;
  unsigned int mPlayEventId;
  unsigned int mResetEventId;
  float mDuration;
  std::string mName;
  std::string mNext;
  std::string mDestroyControlAtEnd;
  bool mResettable;
  std::shared_ptr<UIAnim> mNextAnim;
};

```

### `UIAnimationComponent`
```
struct __cppobj UIAnimationComponent : UIComponent
{
  std::vector<std::shared_ptr<UIAnim>> mAnimList;
  std::vector<std::shared_ptr<UIAnim>> mOriginalAnimList;
  std::vector<ScreenEvent> mNewScreenEvents;
  bool mTickAttached;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mCreatedTime;
  bool mRecievedFirstTick;
  bool mDisableFastForward;
  unsigned int mResetId;
};

```

### `UIAnimationComponent_vtbl`
```
struct /*VFT*/ UIAnimationComponent_vtbl
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

### `UIAnim_vtbl`
```
struct /*VFT*/ UIAnim_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIControlFactoryContext`
```
struct __cppobj UIControlFactoryContext
{
  std::shared_lock<std::shared_mutex> mLock;
};

```

### `UpdateHistoryRecords`
```
struct __cppobj UpdateHistoryRecords
{
  Core::PathBuffer<std::string > mFilepath;
  Json::Value mRootRecordObj;
};

```

### `Util::CaseInsensitiveHash`
```
struct __cppobj Util::CaseInsensitiveHash
{
};

```

### `Util::CaseInsensitiveCompare`
```
struct __cppobj Util::CaseInsensitiveCompare
{
};

```

### `UDATE`
```
struct UDATE
{
  _SYSTEMTIME st;
  unsigned __int16 wDayOfYear;
};

```

### `Urho3D::EmitterScaleFrame_vtbl`
```
struct /*VFT*/ Urho3D::EmitterScaleFrame_vtbl
{
  void (__fastcall *~InterpolableFrame<float>)(InterpolableFrame<float> *this);
  float (__fastcall *Lerp)(InterpolableFrame<float> *this, const float *, const float *, float);
};

```

### `Urho3D::EmitterPathFrame_vtbl`
```
struct /*VFT*/ Urho3D::EmitterPathFrame_vtbl
{
  void (__fastcall *~InterpolableFrame<Urho3D::Vector3>)(InterpolableFrame<Urho3D::Vector3> *this);
  Urho3D::Vector3 *(__fastcall *Lerp)(InterpolableFrame<Urho3D::Vector3> *this, Urho3D::Vector3 *result, const Urho3D::Vector3 *, const Urho3D::Vector3 *, float);
};

```

### `Urho3D::ScaleFrame`
```
struct __cppobj Urho3D::ScaleFrame : InterpolableFrame<Urho3D::Vector2>
{
};

```

### `Urho3D::ScaleFrame_vtbl`
```
struct /*VFT*/ Urho3D::ScaleFrame_vtbl
{
  void (__fastcall *~InterpolableFrame<Urho3D::Vector2>)(InterpolableFrame<Urho3D::Vector2> *this);
  Urho3D::Vector2 *(__fastcall *Lerp)(InterpolableFrame<Urho3D::Vector2> *this, Urho3D::Vector2 *result, const Urho3D::Vector2 *, const Urho3D::Vector2 *, float);
};

```

### `Urho3D::ColorFrame_vtbl`
```
struct /*VFT*/ Urho3D::ColorFrame_vtbl
{
  void (__fastcall *~InterpolableFrame<Urho3D::Color>)(InterpolableFrame<Urho3D::Color> *this);
  Urho3D::Color *(__fastcall *Lerp)(InterpolableFrame<Urho3D::Color> *this, Urho3D::Color *result, const Urho3D::Color *, const Urho3D::Color *, float);
};

```

### `Urho3D::TextureFrame`
```
struct __cppobj Urho3D::TextureFrame
{
  Urho3D::Rect uv_;
};

```

### `Urho3D::ParticleEffect`
```
struct __cppobj Urho3D::ParticleEffect
{
  unsigned int numParticles_;
  bool updateInvisible_;
  bool relative_;
  bool scaled_;
  bool sorted_;
  bool fixedScreenSize_;
  float animationLodBias_;
  float surfaceThickness_;
  Urho3D::EmitDirType emitDir_;
  Urho3D::EmitterType emitterType_;
  Urho3D::Vector3 emitterSize_;
  Urho3D::Vector3 directionMin_;
  Urho3D::Vector3 directionMax_;
  Urho3D::Vector3 constantForce_;
  float dampingForce_;
  float activeTime_;
  float inactiveTime_;
  float emissionRateMin_;
  float emissionRateMax_;
  Urho3D::Vector2 sizeMin_;
  Urho3D::Vector2 sizeMax_;
  float timeToLiveMin_;
  float timeToLiveMax_;
  float velocityMin_;
  float velocityMax_;
  Urho3D::Vector3 rotationMin_;
  Urho3D::Vector3 rotationMax_;
  Urho3D::Vector3 rotationSpeedMin_;
  Urho3D::Vector3 rotationSpeedMax_;
  Urho3D::Vector3 disorderMin_;
  Urho3D::Vector3 disorderMax_;
  float sizeAdd_;
  float sizeMul_;
  InterpolableFrameArray<Urho3D::ScaleFrame,Urho3D::Vector2> scaleFrames_;
  InterpolableFrameArray<Urho3D::ColorFrame,Urho3D::Color> colorFrames_;
  std::vector<Urho3D::TextureFrame> textureFrames_;
  InterpolableFrameArray<Urho3D::EmitterPathFrame,Urho3D::Vector3> emitterPathFrames_;
  InterpolableFrameArray<Urho3D::EmitterScaleFrame,float> emitterScaleFrames_;
  std::string loadMaterialName_;
  Urho3D::FaceCameraMode faceCameraMode_;
  std::string name_;
  std::string materialName_;
  std::string textureName_;
  _BYTE blendMode_[4];
  bool enableColor_;
  bool enableTexture_;
  bool enableLoop_;
  int textureFrameFps_;
  float textureFrameStep_;
  float colorFrameTime_;
  bool shuffle_;
  int layer_;
  bool loadSuccess;
  float disorderInterval_;
  float disorderIncrement_;
  Urho3D::Vector3 oldDisorder_;
  float fadeDistance_;
  bool depthTest_;
  bool mIsIndependent;
  float mDelay;
};

```

### `Urho3D::ParticleEmitterNode`
```
struct __cppobj __declspec(align(4)) Urho3D::ParticleEmitterNode
{
  bool dirty_;
  Urho3D::Vector3 position_;
  Urho3D::Quaternion rotation_;
  Urho3D::Vector3 scale_;
  bool enabled_;
};

```

### `Urho3D::TimerMini`
```
struct __cppobj Urho3D::TimerMini
{
  int curTime;
  int preTime;
  int updateStep;
  int overrideStep;
  int fps;
  int msPerFrame;
  float sPerFrame;
};

```

### `Urho3D::CommonParticle`
```
struct __cppobj Urho3D::CommonParticle
{
  Urho3D::Vector3 velocity_;
  Urho3D::Vector2 size_;
  float timer_;
  float timeToLive_;
  Urho3D::Vector2 scale_;
  Urho3D::Vector3 rotationSpeed_;
  unsigned int texIndex_;
  unsigned int lastTexIndex_;
  Urho3D::Vector3 position_;
  Urho3D::Rect uv_;
  Urho3D::Color color_;
  Urho3D::Vector3 rotation_;
  Urho3D::Vector3 direction_;
  bool enabled_;
  float sortDistance_;
  float screenScaleFactor_;
  Urho3D::Vector3 disorder_;
  float disorderTime_;
  int disorderCount_;
  int renderIndex;
};

```

### `Urho3D::ParticleEmitter::RenderContextPrepareData`
```
struct __cppobj __declspec(align(8)) Urho3D::ParticleEmitter::RenderContextPrepareData
{
  bool canRender;
  bool isDrawingUI;
  Vec3 camWorldPos;
  std::vector<Vec3> worldPosList;
  Vec3 ebEntityPos;
  Vec2 ebEntityRot;
  Matrix viewMatrix;
  Urho3D::Matrix3x4 sbMatrix;
  Urho3D::Matrix3x4 nodeTransform;
};

```

### `UserAuthCheckStage`
```
struct __cppobj __declspec(align(8)) UserAuthCheckStage : BaseStage
{
  int nErrCode;
  std::string strMsg;
  std::string strDetail;
  bool isLoginWebServer;
};

```

### `UserAuthCheckStage_vtbl`
```
struct /*VFT*/ UserAuthCheckStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `Urho3D::Vertex`
```
struct __cppobj Urho3D::Vertex
{
  Urho3D::Vector3 position;
  Urho3D::Vector3 normal;
  Urho3D::Vector4 texcoord;
  float weight[3];
  int boneindex[3];
  int count;
};

```

### `Urho3D::Bone`
```
struct __cppobj Urho3D::Bone
{
  std::string name_;
  Urho3D::StringHash nameHash_;
  unsigned int parentIndex_;
  Urho3D::Vector3 initialPosition_;
  Urho3D::Quaternion initialRotation_;
  Urho3D::Vector3 initialScale_;
  Urho3D::Matrix3x4 offsetMatrix_;
  bool animated_;
  unsigned __int8 collisionMask_;
  Urho3D::BoundingBox boundingBox_;
  int occupiedRef_;
  bool isBlended_;
  std::vector<unsigned int> children_;
  Urho3D::Node mNode;
};

```

### `Urho3D::AnimatedModel`
```
struct __cppobj __declspec(align(8)) Urho3D::AnimatedModel
{
  Urho3D::AnimatedModel_vtbl *__vftable /*VFT*/;
  bool renderable_;
  bool isMaster_;
  Urho3D::Skeleton skeleton_;
  Urho3D::BoundingBox boneBoundingBox_;
  bool animationDirty_;
  bool animationOrderDirty_;
  std::vector<Urho3D::AnimationState *> animationStates_;
  std::unordered_map<std::string,ResourceLocation> animationMap_;
  std::vector<std::string> finishAni_;
  int mLastUpdateMs;
  Urho3D::AnimationController animationControl_;
  std::map<int,Urho3D::TagPoint *> tagPointMap_;
  std::unordered_set<int> tagPointObjIds_;
  Urho3D::Node mNode;
  float scale_;
  glm::tmat4x4<float,0> worldMat_;
  glm::tmat4x4<float,0> projMat_;
  glm::tmat4x4<float,0> viewMat_;
  glm::tvec3<float,0> curCameraWorldTargetPos_;
  std::string fpModelName_;
  std::unique_ptr<Urho3D::AnimatedModel> fpModel_;
  std::array<mce::TexturePtr,3> textures_;
  mce::TexturePtr glintTexture;
  mce::Color glintColor;
  bool usePlayerSkin_;
  mce::ClientTexture playerSkinTexture_;
  std::string modelName_;
  std::vector<std::vector<mce::MaterialPtr>> staticMats_;
  mce::MaterialPtr mSpecialAlphaMat;
  float opacity_;
  float brightness_;
  bool bloom_;
  bool glint_;
  bool modelFrameAni_;
  std::unique_ptr<Urho3D::ModelFrameAniInfo> frameAniInfo;
  bool hasFpModel_;
  Urho3D::ModelRenderType renderType_;
  Vec3 mWeaponFpsTran;
  Vec3 mWeaponFpsRot;
  Vec3 mWeaponTpsTran;
  Vec3 mWeaponTpsRot;
  unsigned __int64 useGpuSkin_;
  mce::MaterialPtr freeMat_[2];
  std::string animationDefault_;
  float animationFadeTime_;
  bool useLegacyBindRot_;
  bool mRenderImmediately;
  unsigned int renderLayer_;
  mce::Color mHideColor;
  std::vector<glm::tmat3x4<float,0>> skinMat3x4_;
  std::mutex mQueueTagPointLock;
  std::mutex mSkiningUpdateLock;
  std::vector<glm::tmat3x4<float,0>> mCalSkinMat4;
  std::vector<glm::tmat3x4<float,0>> mMiddleQueueSkinMat4;
  std::mutex mAnimationUpdateLock;
  std::mutex mAnimationStateUpdateLock;
  bool mMiddleQueueUpdate;
  std::vector<glm::tvec4<float,0>> mExtraUniforms;
  int selfID_;
};

```

### `Urho3D::AnimatedModel_vtbl`
```
struct /*VFT*/ Urho3D::AnimatedModel_vtbl
{
  void (__fastcall *~AnimatedModel)(Urho3D::AnimatedModel *this);
  void (__fastcall *Update)(Urho3D::AnimatedModel *this, float);
};

```

### `Urho3D::Skeleton`
```
struct __cppobj __declspec(align(8)) Urho3D::Skeleton
{
  std::vector<Urho3D::Bone> bones_;
  unsigned int rootBoneIndex_;
};

```

### `Urho3D::AnimationKeyFrame`
```
struct __cppobj Urho3D::AnimationKeyFrame
{
  float time_;
  Urho3D::Vector3 position_;
  Urho3D::Quaternion rotation_;
  Urho3D::Vector3 scale_;
};

```

### `Urho3D::AnimationTrack`
```
const struct __cppobj Urho3D::AnimationTrack
{
  std::string name_;
  Urho3D::StringHash nameHash_;
  unsigned __int8 channelMask_;
  std::vector<Urho3D::AnimationKeyFrame> keyFrames_;
  unsigned __int64 memory_;
  std::unordered_map<int,bool> modelIdBoneTrackMap_;
};

```

### `Urho3D::AnimationState`
```
struct __cppobj Urho3D::AnimationState
{
  Urho3D::AnimatedModel *model_;
  ResourceLocation animationLoc_;
  HashedString animationNameHash_;
  Urho3D::Bone *startBone_;
  std::unordered_map<HashedString,Urho3D::AnimationStateTrack> stateTracks_;
  bool looped_;
  float weight_;
  float time_;
  unsigned __int8 layer_;
  bool finished_;
  bool shouldBlend_;
  std::vector<HashedString> blendParameterNameHashVec_;
  std::mutex mStateUpdateMutex;
};

```

### `Urho3D::AnimationController`
```
struct __cppobj Urho3D::AnimationController
{
  Urho3D::AnimationController_vtbl *__vftable /*VFT*/;
  std::vector<Urho3D::AnimationControl> animations_;
  std::vector<Urho3D::AnimationState *> nodeAnimationStates_;
  Urho3D::AnimatedModel *animatedModel_;
  std::unordered_map<HashedString,std::shared_ptr<Urho3D::Animation1DControlParameter>> oneDimensionControlParamMap_;
  std::mutex mThreadUpdateMutex;
  std::mutex mThreadStateMutex;
};

```

### `Urho3D::AnimationController_vtbl`
```
struct /*VFT*/ Urho3D::AnimationController_vtbl
{
  void (__fastcall *~AnimationController)(Urho3D::AnimationController *this);
  void (__fastcall *Update)(Urho3D::AnimationController *this, float);
};

```

### `Urho3D::AnimationControl`
```
struct __cppobj __declspec(align(4)) Urho3D::AnimationControl
{
  std::string name_;
  Urho3D::StringHash hash_;
  HashedString keyNameHash_;
  float speed_;
  float targetWeight_;
  float fadeTime_;
  bool start_;
};

```

### `Urho3D::Animation1DControlParameter`
```
struct __cppobj __declspec(align(8)) Urho3D::Animation1DControlParameter
{
  float value_;
  HashedString lAnimNameHash_;
  HashedString rAnimNameHash_;
  bool hasApplied_;
};

```

### `Urho3D::TagPoint`
```
struct __cppobj Urho3D::TagPoint
{
  Urho3D::Bone *bindBone;
  Urho3D::AnimatedModel *bindModel;
  int tagIdx;
  float mOpacity;
  float mBrightness;
  Vec3 mOffset;
  Vec3 mRotation;
  int mClientObjId;
};

```

### `Urho3D::ModelFrameAniInfo`
```
struct __cppobj Urho3D::ModelFrameAniInfo
{
  mce::Color param;
  int gridCol;
  float curTime;
  float stepTime;
  int curFrame;
  int totalFrame;
};

```

### `Urho3D::Geometry`
```
struct __cppobj __declspec(align(8)) Urho3D::Geometry
{
  std::vector<Urho3D::Vertex> vertexBuffer_;
  std::vector<unsigned int> indexBuffer_;
  std::vector<unsigned char> shadowData_;
  std::string mTexturePath;
  int mUsedUV;
};

```

### `Urho3D::ModelPart`
```
struct __cppobj Urho3D::ModelPart
{
  int boneId;
  int usedUV;
  std::vector<Urho3D::Vertex> vertexs;
  std::vector<int> indexs;
};

```

### `Urho3D::AnimationTriggerPoint`
```
struct __cppobj Urho3D::AnimationTriggerPoint
{
  float time_;
};

```

### `Urho3D::ModelInfo`
```
struct __cppobj Urho3D::ModelInfo
{
  Urho3D::Skeleton skeleton;
  Urho3D::BoundingBox boundingBox;
  std::unordered_map<std::string,ResourceLocation> aniMap;
  bool dyLoad;
  bool isLoaded;
  std::string geoFilePath;
  std::string skeletonFilePath;
  std::vector<Urho3D::Geometry> geometryVector;
  std::string fpModelName;
  bool hasFpModel;
  bool isGlobal;
  int materialVertexUVCount;
  std::vector<std::string> textures;
  std::string materialPath;
  std::string materialCpuPath;
  Urho3D::ModelFrameAniInfo frameAniInfo;
  std::string renderLayer;
};

```

### `Urho3D::AnimationStateContext`
```
struct __cppobj Urho3D::AnimationStateContext
{
  unsigned __int8 previousLayer_;
};

```

### `ui::FlyingItem`
```
struct __cppobj __declspec(align(8)) ui::FlyingItem
{
  ItemStack item;
  long double startTime;
  float sourcex;
  float sourcey;
  float destx;
  float desty;
  float sourceScale;
  float destScale;
  bool forceFoil;
};

```

### `UIHoloCursorRenderer`
```
struct __cppobj UIHoloCursorRenderer : MinecraftUICustomRenderer
{
};

```

### `UIHoloCursorRenderer_vtbl`
```
struct /*VFT*/ UIHoloCursorRenderer_vtbl
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

### `UIAnimAlpha`
```
struct __cppobj __declspec(align(8)) UIAnimAlpha : UIAnim
{
  float mFromAlpha;
  float mToAlpha;
  float mAlphaValueToScale;
};

```

### `UIAnimAlpha_vtbl`
```
struct /*VFT*/ UIAnimAlpha_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAnimClip`
```
struct __cppobj UIAnimClip : UIAnim
{
  float mFromClipRatio;
  float mToClipRatio;
};

```

### `UIAnimClip_vtbl`
```
struct /*VFT*/ UIAnimClip_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAnimColor`
```
struct __cppobj UIAnimColor : UIAnim
{
  mce::Color mFromColor;
  mce::Color mToColor;
};

```

### `UIAnimColor_vtbl`
```
struct /*VFT*/ UIAnimColor_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAnimFlipbook`
```
struct __cppobj __declspec(align(2)) UIAnimFlipbook : UIAnim
{
  float mAnimationTime;
  float mCurrentFrame;
  float mFPS;
  int mFrameCount;
  float mFrameStep;
  bool mReverse;
  bool mReversible;
  bool mMoreRow;
};

```

### `UIAnimFlipbook_vtbl`
```
struct /*VFT*/ UIAnimFlipbook_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAsepriteFlipbook`
```
struct __cppobj __declspec(align(8)) UIAsepriteFlipbook : UIAnim
{
  float mTimeSoFar;
};

```

### `UIAsepriteFlipbook_vtbl`
```
struct /*VFT*/ UIAsepriteFlipbook_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAnimLayout`
```
struct __cppobj UIAnimLayout : UIAnim
{
  UIAnimLayout::ApplyTo mApplyTo;
  ui::LayoutOffset mInterpolatedOffset;
  ui::LayoutOffset mFromOffset;
  ui::LayoutOffset mToOffset;
};

```

### `UIAnimLayout_vtbl`
```
struct /*VFT*/ UIAnimLayout_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UIAnimUV`
```
struct __cppobj UIAnimUV : UIAnim
{
  glm::tvec2<float,0> mFromUV;
  glm::tvec2<float,0> mToUV;
};

```

### `UIAnimUV_vtbl`
```
struct /*VFT*/ UIAnimUV_vtbl
{
  void (__fastcall *~UIAnim)(UIAnim *this);
  std::shared_ptr<UIAnim> *(__fastcall *clone)(UIAnim *this, std::shared_ptr<UIAnim> *result);
  const char *(__fastcall *getInitialValueKey)(UIAnim *this);
  bool (__fastcall *tick)(UIAnim *this, UIControl *, const float);
  void (__fastcall *updateProperties)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *onResourcesLoaded)(UIAnim *this, UIAnimationComponent *);
  void (__fastcall *_reset)(UIAnim *this, UIControl *);
  void (__fastcall *_play)(UIAnim *this);
};

```

### `UILaytouComponent`
```
struct __cppobj UILaytouComponent : UIComponent
{
};

```

### `UILaytouComponent_vtbl`
```
struct /*VFT*/ UILaytouComponent_vtbl
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

### `UIPropertyBag::registerForPropertyChangedNotification::__l2::<lambda_7e52e4d85eb4d187d33f31333af04fdb>`
```
struct __cppobj UIPropertyBag::registerForPropertyChangedNotification::__l2::<lambda_7e52e4d85eb4d187d33f31333af04fdb>
{
  UIPropertyBag *const __this;
  const std::string *targetPropertyName;
  std::weak_ptr<UIControl> *targetControl;
  const std::function<void __cdecl(std::weak_ptr<UIControl> const &,gsl::basic_string_span<char const ,-1>,Json::Value const &,UIPropertyBag::ContextObject)> *callback;
  const UiExpression *sourcePropertyName;
};

```

### `UIControlFactory::_populateJoystickComponent::__l2::<lambda_997e2d2d96815838e087c785eb9784ed>`
```
struct __cppobj UIControlFactory::_populateJoystickComponent::__l2::<lambda_997e2d2d96815838e087c785eb9784ed>
{
};

```

### `UIControlFactory::_populateSelectionWheelComponent::__l6::<lambda_051809ab354ad22b30b42a785a5b613a>`
```
struct __cppobj UIControlFactory::_populateSelectionWheelComponent::__l6::<lambda_051809ab354ad22b30b42a785a5b613a>
{
};

```

### `UIControlFactory::_populateSliderGroupManagerComponent::__l2::<lambda_3a2608c10ba3910712abae6e3a24e32f>`
```
struct __cppobj UIControlFactory::_populateSliderGroupManagerComponent::__l2::<lambda_3a2608c10ba3910712abae6e3a24e32f>
{
  std::vector<std::string> stringVector;
};

```

### `UIControlFactory::_populateToggleGroupManagerComponent::__l2::<lambda_d7c0454e94b6d1cf44041bbbc98cb12c>`
```
struct __cppobj UIControlFactory::_populateToggleGroupManagerComponent::__l2::<lambda_d7c0454e94b6d1cf44041bbbc98cb12c>
{
  std::vector<std::string> stringVector;
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_59def4c6bc1fa6dd05a998f427c9d07a>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_59def4c6bc1fa6dd05a998f427c9d07a>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_af27a6657ea4aba74d4aca451e1dd836>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_af27a6657ea4aba74d4aca451e1dd836>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_1972730c69dd8958ef3f64b72fc91bdb>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_1972730c69dd8958ef3f64b72fc91bdb>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_242ed0cc31adacd3d2aa40ac5bb2fb04>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_242ed0cc31adacd3d2aa40ac5bb2fb04>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_f011228343baa9667f9c7d117c6aac91>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_f011228343baa9667f9c7d117c6aac91>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_bb8103905c71b4f4ffe894b8fec68f72>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_bb8103905c71b4f4ffe894b8fec68f72>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_e9a435563fcb3bcfceacc3f0ea0595ca>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_e9a435563fcb3bcfceacc3f0ea0595ca>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_7acf4bfc74cea0b9050826b88d648dad>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_7acf4bfc74cea0b9050826b88d648dad>
{
};

```

### `UIControlFactory::_populateToggleComponent::__l2::<lambda_35f51619cbbebabf5a338f6dcaa468ac>`
```
struct __cppobj UIControlFactory::_populateToggleComponent::__l2::<lambda_35f51619cbbebabf5a338f6dcaa468ac>
{
};

```

### `UIControlFactory::_populateTextEditComponent::__l2::<lambda_f2b8ecbb8d3e355465dea6476bc29c31>`
```
struct __cppobj UIControlFactory::_populateTextEditComponent::__l2::<lambda_f2b8ecbb8d3e355465dea6476bc29c31>
{
};

```

### `UIControlFactory::_populateTextEditComponent::__l2::<lambda_dd866a7f7845aa880d7eaed0c214ca5c>`
```
struct __cppobj UIControlFactory::_populateTextEditComponent::__l2::<lambda_dd866a7f7845aa880d7eaed0c214ca5c>
{
};

```

### `UIControlFactory::_populateTextEditComponent::__l2::<lambda_12231a513eea755555a31a2e01ee5281>`
```
struct __cppobj UIControlFactory::_populateTextEditComponent::__l2::<lambda_12231a513eea755555a31a2e01ee5281>
{
};

```

### `UIControlFactory::_populateTextComponent::__l2::<lambda_e126f1ea521e57383f9726deb5c0a692>`
```
struct __cppobj UIControlFactory::_populateTextComponent::__l2::<lambda_e126f1ea521e57383f9726deb5c0a692>
{
  UIControlFactory *const __this;
};

```

### `UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_d4ef19f748f9cbb0f88e82c90a7df604>`
```
struct __cppobj UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_d4ef19f748f9cbb0f88e82c90a7df604>
{
};

```

### `UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_0af924af3a93db7ef10ec3c5067f54db>`
```
struct __cppobj UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_0af924af3a93db7ef10ec3c5067f54db>
{
};

```

### `UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_ccaff2dca858ee38d4afece73a8bc4f8>`
```
struct __cppobj UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_ccaff2dca858ee38d4afece73a8bc4f8>
{
};

```

### `UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_5b19ca696826fc514be1dd6bde7aef70>`
```
struct __cppobj UIControlFactory::_populateSliderBoxComponent::__l2::<lambda_5b19ca696826fc514be1dd6bde7aef70>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_3f2fa77fbba10729b6ca895d1e8a0006>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_3f2fa77fbba10729b6ca895d1e8a0006>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_938ec40245b4c1cd8d75f3e605adc546>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_938ec40245b4c1cd8d75f3e605adc546>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_7452b4eda204b93db909c1b778a091c6>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_7452b4eda204b93db909c1b778a091c6>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_7679c0c31cf7a7053891ae029cc8d553>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_7679c0c31cf7a7053891ae029cc8d553>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_3b501e0451271b43ffcae4b1f6376b78>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_3b501e0451271b43ffcae4b1f6376b78>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_a90f5915e35ed86fbde2a82f96c158b5>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_a90f5915e35ed86fbde2a82f96c158b5>
{
};

```

### `UIControlFactory::_populateSliderComponent::__l2::<lambda_042d8562b6901b28f3883343b591aab9>`
```
struct __cppobj UIControlFactory::_populateSliderComponent::__l2::<lambda_042d8562b6901b28f3883343b591aab9>
{
};

```

### `UIControlFactory::_populateScrollViewComponent::__l2::<lambda_c0d56f9717e044e19eb12f646aa84a5b>`
```
struct __cppobj UIControlFactory::_populateScrollViewComponent::__l2::<lambda_c0d56f9717e044e19eb12f646aa84a5b>
{
};

```

### `UIControlFactory::_populateScrollViewComponent::__l2::<lambda_3a32d314d83ca3a1f04d8017b3f330e9>`
```
struct __cppobj UIControlFactory::_populateScrollViewComponent::__l2::<lambda_3a32d314d83ca3a1f04d8017b3f330e9>
{
};

```

### `UIControlFactory::_populateScrollViewComponent::__l2::<lambda_b45de6332e15271f859ce5b6a9c62fee>`
```
struct __cppobj UIControlFactory::_populateScrollViewComponent::__l2::<lambda_b45de6332e15271f859ce5b6a9c62fee>
{
};

```

### `UIControlFactory::_populateScrollViewComponent::__l2::<lambda_a52b9414e64307039a47247b42a3e54d>`
```
struct __cppobj UIControlFactory::_populateScrollViewComponent::__l2::<lambda_a52b9414e64307039a47247b42a3e54d>
{
};

```

### `UIControlFactory::_populateScrollViewComponent::__l2::<lambda_447456a120d184d622dadd7f2ca7f23a>`
```
struct __cppobj UIControlFactory::_populateScrollViewComponent::__l2::<lambda_447456a120d184d622dadd7f2ca7f23a>
{
};

```

### `UIControlFactory::_populateDropdownComponent::__l2::<lambda_52f39ca51285917ea64c3f76654444dc>`
```
struct __cppobj UIControlFactory::_populateDropdownComponent::__l2::<lambda_52f39ca51285917ea64c3f76654444dc>
{
};

```

### `UIControlFactory::_populateDropdownComponent::__l2::<lambda_127b8072b01cb4c0f7759b5c29d3e243>`
```
struct __cppobj UIControlFactory::_populateDropdownComponent::__l2::<lambda_127b8072b01cb4c0f7759b5c29d3e243>
{
};

```

### `UIControlFactory::_populateDataBindingComponent::__l40::<lambda_b43182dc60d84642d64856899313c1fc>`
```
struct __cppobj UIControlFactory::_populateDataBindingComponent::__l40::<lambda_b43182dc60d84642d64856899313c1fc>
{
  UiExpression sourcePropertyNameString;
  const std::string targetPropertyNameString;
};

```

### `UIControlFactory::_populateButtonComponent::__l2::<lambda_b21d914f1a53ebdc728bc1fbf54b3be0>`
```
struct __cppobj UIControlFactory::_populateButtonComponent::__l2::<lambda_b21d914f1a53ebdc728bc1fbf54b3be0>
{
};

```

### `UIControlFactory::_populateButtonComponent::__l2::<lambda_7056164914efd8ddf7b9676511020e8e>`
```
struct __cppobj UIControlFactory::_populateButtonComponent::__l2::<lambda_7056164914efd8ddf7b9676511020e8e>
{
};

```

### `UIControlFactory::_populateButtonComponent::__l2::<lambda_769ec34c6985bb0f18f7441b6977ae68>`
```
struct __cppobj UIControlFactory::_populateButtonComponent::__l2::<lambda_769ec34c6985bb0f18f7441b6977ae68>
{
};

```

### `UIControlFactory::_populateButtonComponent::__l2::<lambda_8a6a01a68dfdb3b755d14de2e9cad4dc>`
```
struct __cppobj UIControlFactory::_populateButtonComponent::__l2::<lambda_8a6a01a68dfdb3b755d14de2e9cad4dc>
{
};

```

### `UserDataScreenController`
```
struct __cppobj UserDataScreenController : ClientInstanceScreenController
{
  std::atomic<bool> mDirty;
  bool mCanInvite;
  std::vector<PlayerListInfo> mPlayerList;
  std::vector<mce::UUID> mPlayerLobbyList;
  std::vector<std::string> mXuidList;
};

```

### `UserDataScreenController_vtbl`
```
struct /*VFT*/ UserDataScreenController_vtbl
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

### `UnlinkMsaScreenController`
```
struct __cppobj __declspec(align(4)) UnlinkMsaScreenController : MinecraftScreenController
{
  bool mIsRealmsEnabled;
  bool mConfirm0;
  bool mConfirm1;
  bool mConfirm2;
  bool mConfirm3;
};

```

### `UnlinkMsaScreenController_vtbl`
```
struct /*VFT*/ UnlinkMsaScreenController_vtbl
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

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_54303167825b991cb35552e3dcd410de>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_54303167825b991cb35552e3dcd410de>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>::()::__l5::<lambda_3bf5cabb33c6ba8cfb994e8438736e47>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>::()::__l5::<lambda_3bf5cabb33c6ba8cfb994e8438736e47>
{
  std::weak_ptr<UnlinkMsaScreenController> weakThis;
  std::weak_ptr<AbstractScene> weakProgressScreen;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>::()::__l5::<lambda_3bf5cabb33c6ba8cfb994e8438736e47>::()::__l5::<lambda_e1909ad8803259bfa4249e426e41671a>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_9759b1ce1a0d0667af6297e7eeb64320>::()::__l5::<lambda_3bf5cabb33c6ba8cfb994e8438736e47>::()::__l5::<lambda_e1909ad8803259bfa4249e426e41671a>
{
  std::weak_ptr<UnlinkMsaScreenController> weakThis;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_f568cb11b762bee865a35187d57b3eba>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_f568cb11b762bee865a35187d57b3eba>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_980351544fe1f61846c8562b7b490269>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_980351544fe1f61846c8562b7b490269>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_12023552a4b84c8396aa322db2e38fad>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_12023552a4b84c8396aa322db2e38fad>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_7b207dd06a72d3860133a478770becc9>`
```
struct __cppobj UnlinkMsaScreenController::_registerEventHandlers::__l2::<lambda_7b207dd06a72d3860133a478770becc9>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_3d07442a45132e0ebbb54714d455e162>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_3d07442a45132e0ebbb54714d455e162>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_22196263bcd2b28faa60cac684f191fa>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_22196263bcd2b28faa60cac684f191fa>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_8da39eabd902b9ce683d251e58d0f01a>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_8da39eabd902b9ce683d251e58d0f01a>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_4abb7228fab97675aae32a491ead0e05>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_4abb7228fab97675aae32a491ead0e05>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_878a9544527ce65b693e15ecd59aabe4>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_878a9544527ce65b693e15ecd59aabe4>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UnlinkMsaScreenController::_registerBindings::__l2::<lambda_5da5d171d5772bedd141bc3ca65c0047>`
```
struct __cppobj UnlinkMsaScreenController::_registerBindings::__l2::<lambda_5da5d171d5772bedd141bc3ca65c0047>
{
  UnlinkMsaScreenController *const __this;
};

```

### `UpdateVersionScreenController`
```
struct __cppobj UpdateVersionScreenController : MainMenuScreenController
{
  std::string mPatchNotes;
  std::string mVersionString;
  std::string mBodyText;
  std::string mTitleText;
};

```

### `UpdateVersionScreenController_vtbl`
```
struct /*VFT*/ UpdateVersionScreenController_vtbl
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

### `UserManagementScreenController`
```
struct __cppobj __declspec(align(8)) UserManagementScreenController : MinecraftScreenController
{
  UserManagementModalScreenData mScreenData;
  std::function<void __cdecl(bool)> mCallback;
  bool mCallbackResult;
};

```

### `UserManagementScreenController_vtbl`
```
struct /*VFT*/ UserManagementScreenController_vtbl
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

### `UserProfileCardScreenController`
```
struct __cppobj UserProfileCardScreenController : MinecraftScreenController
{
  const std::string mXuid;
  std::string mGamertag;
  std::string mGamerscore;
  Social::UserPicturePath mGamerPicPath;
  std::string mTitleName;
  _BYTE mFriendStatus[4];
  _BYTE mPresenceStatus[4];
  bool mIsFriend;
  bool mMutePlayer;
  bool mBlockPlayer;
  bool mAddFriendDropDownActive;
  bool mAddRemoveFriendInProgress;
  bool mDirty;
  mce::UUID mUUID;
  std::string mPlatformId;
  ResourceLocation mPlatformGamerPicLocation;
  std::string mThirdPartyPlayerName;
};

```

### `UserProfileCardScreenController_vtbl`
```
struct /*VFT*/ UserProfileCardScreenController_vtbl
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

### `UserProfileCardScreenController::_requestPlatformProfilePic::__l2::<lambda_628dc8dc5d8bb6b61e554128ffc0b982>`
```
struct __cppobj UserProfileCardScreenController::_requestPlatformProfilePic::__l2::<lambda_628dc8dc5d8bb6b61e554128ffc0b982>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>
{
  std::pair<std::string const ,enum FriendStatus> blockTypePair;
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l16::<lambda_9b36e3c260d2acef78e4016410901c81>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l16::<lambda_9b36e3c260d2acef78e4016410901c81>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l12::<lambda_e89ec697c66ea2fad34062eee5ce7056>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l12::<lambda_e89ec697c66ea2fad34062eee5ce7056>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l8::<lambda_e8ae233d234aa536312f5c2894198cd7>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_2d67284d2dec7acdf8bac2348e4273c4>::()::__l8::<lambda_e8ae233d234aa536312f5c2894198cd7>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_49790983055ab7cb0365524a9526e588>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l6::<lambda_49790983055ab7cb0365524a9526e588>
{
  std::pair<std::string const ,enum FriendStatus> blockTypePair;
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_b65d9753dad2e5b06ae5dd93a32efd7b>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_b65d9753dad2e5b06ae5dd93a32efd7b>
{
  std::vector<std::string> friendStatusLabels;
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_4d2195c5505a0adffcf6efde8c71069b>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_4d2195c5505a0adffcf6efde8c71069b>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_93f3e17a5fe2f4db5fbe62ada0f04711>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_93f3e17a5fe2f4db5fbe62ada0f04711>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_c0f9e2af2642c204d99604e0ccb87dba>`
```
struct __cppobj UserProfileCardScreenController::_registerFriendsDropdown::__l2::<lambda_c0f9e2af2642c204d99604e0ccb87dba>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_e86360916a8dce991f37401ec3f4fa15>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_e86360916a8dce991f37401ec3f4fa15>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_b08aa0aaa917eaaf8c26966313ea898c>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_b08aa0aaa917eaaf8c26966313ea898c>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_8b53e2c218f2846eb1756ffceb6e6ad8>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_8b53e2c218f2846eb1756ffceb6e6ad8>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_eefc67550e326b3f9b70dc74a9ddcb3f>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_eefc67550e326b3f9b70dc74a9ddcb3f>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_ccf70a122115c2885d268dcf1fea8e3b>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_ccf70a122115c2885d268dcf1fea8e3b>
{
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_18faaeed74b7bdad92defd2852fc58c8>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_18faaeed74b7bdad92defd2852fc58c8>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_d46ab09f1f4a85965078f78acbae8602>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_d46ab09f1f4a85965078f78acbae8602>
{
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_cf212e09803aa1a569cbece92abdc7f6>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_cf212e09803aa1a569cbece92abdc7f6>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_1cb2639903fa236dc5e3e16aa81b3ef5>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_1cb2639903fa236dc5e3e16aa81b3ef5>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_fbb131b4c5fc0ca31bc7cccf28cb37f7>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_fbb131b4c5fc0ca31bc7cccf28cb37f7>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_02f022668260fbfe8575c85ec30893c5>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_02f022668260fbfe8575c85ec30893c5>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_1983305dd5e771db74cab95d86ef43c2>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_1983305dd5e771db74cab95d86ef43c2>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_79f015ab2a07433487fa7dee550aa5c2>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_79f015ab2a07433487fa7dee550aa5c2>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_6544421f78824afb37d7a08d7580dd5e>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_6544421f78824afb37d7a08d7580dd5e>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_f94bc11eee0ba4a7254297523e635374>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_f94bc11eee0ba4a7254297523e635374>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_2afdf8626700ff77123efada76f6a647>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_2afdf8626700ff77123efada76f6a647>
{
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_ace99107df48e2da2b02d1207a962929>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_ace99107df48e2da2b02d1207a962929>
{
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_ec1a33bb0e92c819248f700d3545bf40>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_ec1a33bb0e92c819248f700d3545bf40>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_97f6490ec09a3f28d970543d53b369ee>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_97f6490ec09a3f28d970543d53b369ee>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_2691e8a03af203a01d365b8ba4611ee4>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_2691e8a03af203a01d365b8ba4611ee4>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_bedb5d9688ebd19dc8ab0c0de50cbd8d>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_bedb5d9688ebd19dc8ab0c0de50cbd8d>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_2ff44a667b1d0891bb8d6ce14d753bc4>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_2ff44a667b1d0891bb8d6ce14d753bc4>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_cabf7fcdf347870ef1234114679ccc6f>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_cabf7fcdf347870ef1234114679ccc6f>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerBindings::__l2::<lambda_c15915bea12e6a55998dbc338493dade>`
```
struct __cppobj UserProfileCardScreenController::_registerBindings::__l2::<lambda_c15915bea12e6a55998dbc338493dade>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>::()::__l7::<lambda_2b4e7092758b5a03c97d2216618b2603>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>::()::__l7::<lambda_2b4e7092758b5a03c97d2216618b2603>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>::()::__l5::<lambda_dc3120543102b03843e9faba0523f918>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_321345a8e15caa78a9025b2f7c444d2c>::()::__l5::<lambda_dc3120543102b03843e9faba0523f918>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>::()::__l7::<lambda_f8cd7febc7152c82f61b09d6531e702d>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>::()::__l7::<lambda_f8cd7febc7152c82f61b09d6531e702d>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>::()::__l5::<lambda_4366c9d43350977d9e24f943a14cd9d1>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_28fd4be39568c65af52022866af1427b>::()::__l5::<lambda_4366c9d43350977d9e24f943a14cd9d1>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_82ba6062f2dda32b678900bb97e0720c>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_82ba6062f2dda32b678900bb97e0720c>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_82ba6062f2dda32b678900bb97e0720c>::()::__l2::<lambda_6920f00baa5d5b71e864096e54321814>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_82ba6062f2dda32b678900bb97e0720c>::()::__l2::<lambda_6920f00baa5d5b71e864096e54321814>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_29d3be49d0ca9c0b8a1c1f815af66dfa>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_29d3be49d0ca9c0b8a1c1f815af66dfa>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_29d3be49d0ca9c0b8a1c1f815af66dfa>::()::__l2::<lambda_313bdb65b315d6b5909ee0c576fbbe77>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_29d3be49d0ca9c0b8a1c1f815af66dfa>::()::__l2::<lambda_313bdb65b315d6b5909ee0c576fbbe77>
{
  std::weak_ptr<UserProfileCardScreenController> weakThis;
};

```

### `UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_7cd91a33f145a8ab561c4807dd25e8ec>`
```
struct __cppobj UserProfileCardScreenController::_registerEventHandlers::__l2::<lambda_7cd91a33f145a8ab561c4807dd25e8ec>
{
  UserProfileCardScreenController *const __this;
};

```

### `UserManagementScreenController::_registerBindings::__l2::<lambda_b9e9ae3eb9288982ec11bd97d42e51ed>`
```
struct __cppobj UserManagementScreenController::_registerBindings::__l2::<lambda_b9e9ae3eb9288982ec11bd97d42e51ed>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerBindings::__l2::<lambda_89e8710f676f280269f3e7d2863478b6>`
```
struct __cppobj UserManagementScreenController::_registerBindings::__l2::<lambda_89e8710f676f280269f3e7d2863478b6>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerBindings::__l2::<lambda_dedb7c4b3a353d0432b971f6f9b5b59d>`
```
struct __cppobj UserManagementScreenController::_registerBindings::__l2::<lambda_dedb7c4b3a353d0432b971f6f9b5b59d>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerBindings::__l2::<lambda_c532f37aa2afd9f21599f13937d7b8a2>`
```
struct __cppobj UserManagementScreenController::_registerBindings::__l2::<lambda_c532f37aa2afd9f21599f13937d7b8a2>
{
  std::string content;
};

```

### `UserManagementScreenController::_registerBindings::__l2::<lambda_6cc2955e5cda5494e6fe4ba0c8b339b2>`
```
struct __cppobj UserManagementScreenController::_registerBindings::__l2::<lambda_6cc2955e5cda5494e6fe4ba0c8b339b2>
{
  std::string title;
};

```

### `UserManagementScreenController::_registerEventHandlers::__l2::<lambda_5e84b0cbba6b481d1ff8b2a18c3c3735>`
```
struct __cppobj UserManagementScreenController::_registerEventHandlers::__l2::<lambda_5e84b0cbba6b481d1ff8b2a18c3c3735>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerEventHandlers::__l2::<lambda_5d4dae614a9edd73ea30e7f2247a78e7>`
```
struct __cppobj UserManagementScreenController::_registerEventHandlers::__l2::<lambda_5d4dae614a9edd73ea30e7f2247a78e7>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerEventHandlers::__l2::<lambda_97121ef6e891bb97cb1fe1eae398c6e6>`
```
struct __cppobj UserManagementScreenController::_registerEventHandlers::__l2::<lambda_97121ef6e891bb97cb1fe1eae398c6e6>
{
  UserManagementScreenController *const __this;
};

```

### `UserManagementScreenController::_registerEventHandlers::__l2::<lambda_77f02e951fe8eeac9fa9c5e21466de57>`
```
struct __cppobj UserManagementScreenController::_registerEventHandlers::__l2::<lambda_77f02e951fe8eeac9fa9c5e21466de57>
{
  UserManagementScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_a3dc2b903414c7a54185fe43be9c80ab>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_a3dc2b903414c7a54185fe43be9c80ab>
{
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_99317237bdb4928c9b60bc24372052d9>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_99317237bdb4928c9b60bc24372052d9>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_2b95d0869135de0dc5177f4f57350d14>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_2b95d0869135de0dc5177f4f57350d14>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_8bd4dfe1c2fb510458393efe609e4079>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_8bd4dfe1c2fb510458393efe609e4079>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_00e544b9b8c19223d62d892d31a2cc08>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_00e544b9b8c19223d62d892d31a2cc08>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_2e18ade293b9df1ee6c3a80bfbc728fd>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_2e18ade293b9df1ee6c3a80bfbc728fd>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_bfbecf79a42585faa6d95814ed17bca7>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_bfbecf79a42585faa6d95814ed17bca7>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_a489df75ace22d576283f0c580684176>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_a489df75ace22d576283f0c580684176>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_5c507e26f88cde16e818161eed308d58>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_5c507e26f88cde16e818161eed308d58>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_1ae255e86bc1579d61ed9251c29bbadb>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_1ae255e86bc1579d61ed9251c29bbadb>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_b71457bed353e2d18e459983c3bcd258>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_b71457bed353e2d18e459983c3bcd258>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_5141d5f416599418f62c64503a900d4a>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_5141d5f416599418f62c64503a900d4a>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_c878625850a415624094374a8c7c0950>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_c878625850a415624094374a8c7c0950>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerBindings::__l2::<lambda_39ff518ac2d9175066cd44420940b0df>`
```
struct __cppobj UserDataScreenController::_registerBindings::__l2::<lambda_39ff518ac2d9175066cd44420940b0df>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_registerEventHandlers::__l2::<lambda_fa0a8bd6e82218480ee0615986866c7f>`
```
struct __cppobj UserDataScreenController::_registerEventHandlers::__l2::<lambda_fa0a8bd6e82218480ee0615986866c7f>
{
  UserDataScreenController *const __this;
};

```

### `UserDataScreenController::_requestThirdPartyPics::__l2::<lambda_6f30ed4af1084cd590da280d6f212311>`
```
struct __cppobj UserDataScreenController::_requestThirdPartyPics::__l2::<lambda_6f30ed4af1084cd590da280d6f212311>
{
  std::weak_ptr<UserDataScreenController> weakThis;
};

```

### `UserDataScreenController::_requestPlayerProfiles::__l5::<lambda_1490c5e2375cbfb0c0f7c887786c437b>`
```
struct __cppobj UserDataScreenController::_requestPlayerProfiles::__l5::<lambda_1490c5e2375cbfb0c0f7c887786c437b>
{
  std::weak_ptr<UserDataScreenController> weakThis;
};

```

### `UpdateVersionScreenController::_registerEventHandlers::__l2::<lambda_b72a5e45c81d0ac5f95d466cb7f852ec>`
```
struct __cppobj UpdateVersionScreenController::_registerEventHandlers::__l2::<lambda_b72a5e45c81d0ac5f95d466cb7f852ec>
{
  UpdateVersionScreenController *const __this;
};

```

### `UpdateVersionScreenController::_registerBindings::__l2::<lambda_b8926fd83cc2056b28f9ee0b77e80c64>`
```
struct __cppobj UpdateVersionScreenController::_registerBindings::__l2::<lambda_b8926fd83cc2056b28f9ee0b77e80c64>
{
  UpdateVersionScreenController *const __this;
};

```

### `UpdateVersionScreenController::_registerBindings::__l2::<lambda_c5ce0f06069d95b733c81a395c5e9bca>`
```
struct __cppobj UpdateVersionScreenController::_registerBindings::__l2::<lambda_c5ce0f06069d95b733c81a395c5e9bca>
{
  UpdateVersionScreenController *const __this;
};

```

### `UpdateVersionScreenController::_registerBindings::__l2::<lambda_528c0d272bf41d76f71a9affa82a515b>`
```
struct __cppobj UpdateVersionScreenController::_registerBindings::__l2::<lambda_528c0d272bf41d76f71a9affa82a515b>
{
  UpdateVersionScreenController *const __this;
};

```

### `UpsellPackCollector`
```
struct __cppobj __declspec(align(4)) UpsellPackCollector : SkinPackCollector
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalog;
  MainMenuScreenModel *mMainMenu;
  std::shared_ptr<SkinPickerUpsellTreatmentQuery> mSkinPickerUpsellTreatmentQuery;
  std::unique_ptr<std::vector<SkinPackMeta>> mSkinPackMeta;
  int mNumUpsellPacks;
  bool mSearchActive;
};

```

### `UpsellPackCollector_vtbl`
```
struct /*VFT*/ UpsellPackCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `UnownedCatalogCollector`
```
struct __cppobj __declspec(align(8)) UnownedCatalogCollector : CatalogPackCollector
{
  _BYTE mPerfTier[4];
};

```

### `UnownedCatalogCollector_vtbl`
```
struct /*VFT*/ UnownedCatalogCollector_vtbl
{
  void (__fastcall *~SkinPackCollector)(SkinPackCollector *this);
  void (__fastcall *start)(SkinPackCollector *this, bool);
  bool (__fastcall *exhausted)(SkinPackCollector *this);
  HandleRangeResult (__fastcall *handleRange)(SkinPackCollector *this, int, int);
  void (__fastcall *collect)(SkinPackCollector *this, IEntitlementManager *, SkinRepositoryClientInterface *, std::vector<std::shared_ptr<SkinPackModel>> *, std::unordered_set<mce::UUID> *);
};

```

### `UpsellPackCollector::_search::__l2::<lambda_366e05248461b03b8939a06c71424fbc>`
```
struct __cppobj UpsellPackCollector::_search::__l2::<lambda_366e05248461b03b8939a06c71424fbc>
{
  UpsellPackCollector *const __this;
  std::weak_ptr<bool> weakTracker;
};

```

### `UpsellPackCollector::_search::__l2::<lambda_366e05248461b03b8939a06c71424fbc>::()::__l10::<lambda_321b6aa5ebf06b15c3f96749c3a30b2f>`
```
struct __cppobj UpsellPackCollector::_search::__l2::<lambda_366e05248461b03b8939a06c71424fbc>::()::__l10::<lambda_321b6aa5ebf06b15c3f96749c3a30b2f>
{
  UpsellPackCollector *const __this;
  std::weak_ptr<bool> weakTracker;
};

```

### `UIResourcePackMergeStrategy`
```
struct __cppobj UIResourcePackMergeStrategy : ResourcePackMergeStrategy
{
  const std::string mFileName;
  Json::Value *mRoot;
  std::vector<PackReport> *mPackReports;
};

```

### `UIResourcePackMergeStrategy_vtbl`
```
struct /*VFT*/ UIResourcePackMergeStrategy_vtbl
{
  void (__fastcall *~ResourcePackMergeStrategy)(ResourcePackMergeStrategy *this);
  void (__fastcall *mergeFiles)(ResourcePackMergeStrategy *this, const std::vector<LoadedResourceData> *);
};

```

### `UIEval`
```
struct __cppobj UIEval
{
};

```

### `UIModification`
```
struct __cppobj __declspec(align(8)) UIModification
{
  Json::Value *mValue;
  std::vector<UIIndexInfo> mIndices;
  bool mIsControlsArray;
};

```

### `UICondition`
```
struct __cppobj UICondition
{
  std::string controlName;
  const Json::Value *condition;
};

```

### `UIPackError_vtbl`
```
struct /*VFT*/ UIPackError_vtbl
{
  void (__fastcall *~PackError)(PackError *this);
  std::string *(__fastcall *getLocErrorMessage)(PackError *this, std::string *result);
  const std::unordered_map<int,std::string> *(__fastcall *getLocErrorMessageMap)(PackError *this);
  const std::unordered_map<int,std::string> *(__fastcall *getEventErrorMessageMap)(PackError *this);
};

```

### `UIResolvedDef::_pushVariables::__l2::<lambda_110a7f35c13d05a1f7de58bdd4366bf9>`
```
struct __cppobj UIResolvedDef::_pushVariables::__l2::<lambda_110a7f35c13d05a1f7de58bdd4366bf9>
{
  UIResolvedDef *const __this;
};

```

### `UIResolvedDef::getAsTextureString::__l7::<lambda_de94cf2c7057817bd3ad2aa00878193f>`
```
struct __cppobj UIResolvedDef::getAsTextureString::__l7::<lambda_de94cf2c7057817bd3ad2aa00878193f>
{
  const UIResolvedDef *const __this;
  const gsl::basic_string_span<char const ,-1> *textureColon;
};

```

### `UIResolvedDef::getAsTextureString::__l5::<lambda_2eab3b17d68031da6cc5d6a56b5b5e15>`
```
struct __cppobj UIResolvedDef::getAsTextureString::__l5::<lambda_2eab3b17d68031da6cc5d6a56b5b5e15>
{
  const UIResolvedDef *const __this;
  int *bestIndex;
  gsl::basic_string_span<char const ,-1> *bestName;
  const gsl::basic_string_span<char const ,-1> *textureColon;
};

```

### `UIDefRepository::_collectAllDefEntries::__l33::<lambda_26d39e94e87968f45d9682aec458e784>`
```
struct __cppobj UIDefRepository::_collectAllDefEntries::__l33::<lambda_26d39e94e87968f45d9682aec458e784>
{
  std::string fileName;
  std::shared_ptr<std::vector<UIDefRepository::DefEntry> > fileDefEntries;
  std::shared_ptr<std::vector<PackReport> > fileReports;
  const bool loadingUI;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<bool> > loadFilesTask;
  std::shared_ptr<Json::Value> defRoot;
};

```

### `UIDefRepository::_collectAllDefEntries::__l33::<lambda_2cb4b770d1292cb375a6542944d453e9>`
```
struct __cppobj UIDefRepository::_collectAllDefEntries::__l33::<lambda_2cb4b770d1292cb375a6542944d453e9>
{
  std::shared_ptr<Json::Value> defRoot;
  std::shared_ptr<std::vector<PackReport> > fileReports;
};

```

### `UIDefRepository::translateLegacyItemIdsInRepository::__l11::<lambda_8e6e247a093523ef96588b8b0ed05693>`
```
struct __cppobj UIDefRepository::translateLegacyItemIdsInRepository::__l11::<lambda_8e6e247a093523ef96588b8b0ed05693>
{
};

```

### `UIDefRepository::_queueFinishLoad::__l2::<lambda_2cecd1c08ac8b65ce9c8ffd4a0de30c7>`
```
struct __cppobj UIDefRepository::_queueFinishLoad::__l2::<lambda_2cecd1c08ac8b65ce9c8ffd4a0de30c7>
{
  UIDefRepository *const __this;
  std::shared_ptr<std::unordered_map<std::string,UIDefNamespace> > defNamespaces;
  const ResourcePackStack *packStack;
};

```

### `UIScene::init::__l2::<lambda_d2bae8e022891f5c1d950d39174e1124>`
```
struct __cppobj UIScene::init::__l2::<lambda_d2bae8e022891f5c1d950d39174e1124>
{
  UIScene *const __this;
};

```

### `UIScene::init::__l2::<lambda_8e0d2a2a7c64a82a8ec6b2175ba94bed>`
```
struct __cppobj UIScene::init::__l2::<lambda_8e0d2a2a7c64a82a8ec6b2175ba94bed>
{
  UIScene *const __this;
};

```

### `UIScene::init::__l2::<lambda_fda08a902e96a41a8144946d3abafb8b>`
```
struct __cppobj UIScene::init::__l2::<lambda_fda08a902e96a41a8144946d3abafb8b>
{
  UIScene *const __this;
};

```

### `UserAuthentication::init::__l5::<lambda_d797eca5cc9f47277a1329940b1f9c36>`
```
struct __cppobj UserAuthentication::init::__l5::<lambda_d797eca5cc9f47277a1329940b1f9c36>
{
  UserAuthentication *const __this;
};

```

### `UIFrameBufferObjectData`
```
struct __cppobj __declspec(align(8)) UIFrameBufferObjectData
{
  mce::FrameBufferObject mFrameBufferObject;
  mce::Texture mColorBufferTexture;
  mce::Texture mDepthBufferTexture;
  unsigned __int8 mAssociatedClient;
};

```

### `UIRenderStageWithFrameBufferObjects`
```
struct __cppobj UIRenderStageWithFrameBufferObjects : mce::RenderStage
{
  std::vector<UIFrameBufferObjectData> mFrameBufferObjectData;
  IClientInstance *mClient;
};

```

### `UIRenderStageWithFrameBufferObjects_vtbl`
```
struct /*VFT*/ UIRenderStageWithFrameBufferObjects_vtbl
{
  void (__fastcall *~RenderStage)(mce::RenderStage *this);
  void (__fastcall *preRenderUpdate)(mce::RenderStage *this, ScreenContext *);
  void (__fastcall *postRenderUpdate)(mce::RenderStage *this, ScreenContext *);
  void (__fastcall *preRender)(mce::RenderStage *this, ScreenContext *);
  void (__fastcall *prepareFrame)(mce::RenderStage *this, ScreenContext *);
  void (__fastcall *render)(mce::RenderStage *this, ScreenContext *, const FrameRenderObject *);
  void (__fastcall *postRender)(mce::RenderStage *this, ScreenContext *);
  bool (__fastcall *shouldSkip)(mce::RenderStage *this);
  bool (__fastcall *shouldRender)(mce::RenderStage *this);
  void (__fastcall *preparePostProcess)(mce::RenderStage *this, mce::RenderContext *, const mce::TextureDescription *);
};

```

### `Util::EntityComponentProcessor_Impl<BlockCollisionComponent>::ProcessContext`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockCollisionComponent>::ProcessContext
{
  bool mAllOnFirst;
  std::tuple<BlockCollisionComponent *> mComponents;
};

```

### `Util::EntityComponentProcessor_Impl<BlockCollisionComponent>`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockCollisionComponent> : Util::EntityComponentProcessor
{
  std::vector<std::function<void __cdecl(Util::EntityComponentProcessor_Impl<BlockCollisionComponent>::ProcessContext &,EntityContext &,EntityContext &)>> mProcessFunctions;
};

```

### `Util::EntityComponentProcessor_Impl<BlockCollisionComponent>_vtbl`
```
struct /*VFT*/ Util::EntityComponentProcessor_Impl<BlockCollisionComponent>_vtbl
{
  void (__fastcall *~EntityComponentProcessor)(Util::EntityComponentProcessor *this);
  bool (__fastcall *canProcess)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
  void (__fastcall *process)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
};

```

### `Util::EntityComponentProcessor_Impl<BlockCollisionComponent>::_componentCheck<BlockCollisionComponent>`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockCollisionComponent>::_componentCheck<BlockCollisionComponent>
{
};

```

### `Util::EntityComponentProcessor_Impl<BlockRaycastComponent>::ProcessContext`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockRaycastComponent>::ProcessContext
{
  bool mAllOnFirst;
  std::tuple<BlockRaycastComponent *> mComponents;
};

```

### `Util::EntityComponentProcessor_Impl<BlockRaycastComponent>`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockRaycastComponent> : Util::EntityComponentProcessor
{
  std::vector<std::function<void __cdecl(Util::EntityComponentProcessor_Impl<BlockRaycastComponent>::ProcessContext &,EntityContext &,EntityContext &)>> mProcessFunctions;
};

```

### `Util::EntityComponentProcessor_Impl<BlockRaycastComponent>_vtbl`
```
struct /*VFT*/ Util::EntityComponentProcessor_Impl<BlockRaycastComponent>_vtbl
{
  void (__fastcall *~EntityComponentProcessor)(Util::EntityComponentProcessor *this);
  bool (__fastcall *canProcess)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
  void (__fastcall *process)(Util::EntityComponentProcessor *this, EntityContext *, EntityContext *);
};

```

### `Util::EntityComponentProcessor_Impl<BlockRaycastComponent>::_componentCheck<BlockRaycastComponent>`
```
struct __cppobj Util::EntityComponentProcessor_Impl<BlockRaycastComponent>::_componentCheck<BlockRaycastComponent>
{
};

```

### `UnknownBlockTypeRegistry`
```
struct __cppobj UnknownBlockTypeRegistry : IUnknownBlockTypeRegistry
{
  std::mutex mMutex;
  std::map<unsigned __int64,SharedPtr<BlockLegacy>> mUnknownBlockLookupMap;
};

```

### `UnknownBlockTypeRegistry_vtbl`
```
struct /*VFT*/ UnknownBlockTypeRegistry_vtbl
{
  void (__fastcall *~IUnknownBlockTypeRegistry)(IUnknownBlockTypeRegistry *this);
  const Block *(__fastcall *getUnknownBlock)(IUnknownBlockTypeRegistry *this, const CompoundTag *);
};

```

### `UnknownBlock`
```
struct __cppobj UnknownBlock : BlockLegacy
{
};

```

### `UnknownBlock_vtbl`
```
struct /*VFT*/ UnknownBlock_vtbl
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

### `Util::LootTableUtils`
```
struct __cppobj Util::LootTableUtils
{
};

```

### `UpdateAttributesPacket::AttributeData::<lambda_9997ff9d83022fcbb3e6903837cca530>::()::__l2::Literal`
```
struct __cppobj UpdateAttributesPacket::AttributeData::<lambda_9997ff9d83022fcbb3e6903837cca530>::()::__l2::Literal
{
};

```

### `UpdateAttributesPacket::AttributeData::<lambda_9997ff9d83022fcbb3e6903837cca530>`
```
struct __cppobj UpdateAttributesPacket::AttributeData::<lambda_9997ff9d83022fcbb3e6903837cca530>
{
};

```

### `UpdateSoftEnumPacket::read::__l2::<lambda_04dc0c99053ac25af7f1bc12e2c95f86>`
```
struct __cppobj UpdateSoftEnumPacket::read::__l2::<lambda_04dc0c99053ac25af7f1bc12e2c95f86>
{
};

```

### `UpdateSoftEnumPacket::write::__l2::<lambda_690ed97c4ad4303601a2f6ab1e8abf73>`
```
struct __cppobj UpdateSoftEnumPacket::write::__l2::<lambda_690ed97c4ad4303601a2f6ab1e8abf73>
{
};

```

### `UpdateAttributesPacket::read::__l2::<lambda_42ec43c904a315ef4d6b3be44db1eb4e>`
```
struct __cppobj UpdateAttributesPacket::read::__l2::<lambda_42ec43c904a315ef4d6b3be44db1eb4e>
{
};

```

### `UpdateAttributesPacket::write::__l2::<lambda_124985996d73ddd8cc6a1341e9329d4e>`
```
struct __cppobj UpdateAttributesPacket::write::__l2::<lambda_124985996d73ddd8cc6a1341e9329d4e>
{
};

```

### `UPNPInterface::createIPv4PortMapping::__l2::<lambda_91da9e08afacc8fa333bcdd99c5a1342>`
```
struct __cppobj UPNPInterface::createIPv4PortMapping::__l2::<lambda_91da9e08afacc8fa333bcdd99c5a1342>
{
  UPNPInterface *const __this;
};

```

### `utimbuf`
```
struct utimbuf
{
  __int64 actime;
  __int64 modtime;
};

```

### `UseActorNode`
```
struct __cppobj __declspec(align(4)) UseActorNode : BehaviorNode
{
  int mDelayCounter;
  bool mRightMouseDown;
  bool mPreActionDone;
};

```

### `UseActorNode_vtbl`
```
struct /*VFT*/ UseActorNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `UseActorDefinition`
```
struct __cppobj UseActorDefinition : BehaviorDefinition
{
};

```

### `UseActorDefinition_vtbl`
```
struct /*VFT*/ UseActorDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `UIEventCoordinator::sendPoppedScreen::__l2::<lambda_435f8bf32000b6ad0827ba647844e3a8>`
```
struct __cppobj UIEventCoordinator::sendPoppedScreen::__l2::<lambda_435f8bf32000b6ad0827ba647844e3a8>
{
  AbstractScene *screen;
};

```

### `UIEventCoordinator::sendPushedScreen::__l2::<lambda_d9ca35c2789d97c2aee6b49c49105509>`
```
struct __cppobj UIEventCoordinator::sendPushedScreen::__l2::<lambda_d9ca35c2789d97c2aee6b49c49105509>
{
  AbstractScene *screen;
};

```

### `UnderwaterTorchBlock`
```
struct __cppobj UnderwaterTorchBlock : TorchBlock
{
};

```

### `UnderwaterTorchBlock_vtbl`
```
struct /*VFT*/ UnderwaterTorchBlock_vtbl
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

### `UndyedShulkerBoxBlock`
```
struct __cppobj UndyedShulkerBoxBlock : ShulkerBoxBlock
{
};

```

### `UndyedShulkerBoxBlock_vtbl`
```
struct /*VFT*/ UndyedShulkerBoxBlock_vtbl
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

### `UnburiedConstraint`
```
struct __cppobj UnburiedConstraint : IStructureConstraint
{
  std::vector<BlockPos> mCeilingOffsets;
};

```

### `UnburiedConstraint_vtbl`
```
struct /*VFT*/ UnburiedConstraint_vtbl
{
  void (__fastcall *~IStructureConstraint)(IStructureConstraint *this);
  bool (__fastcall *isSatisfied)(IStructureConstraint *this, const IBlockWorldGenAPI *, const BlockPos *, const Rotation *);
};

```

### `UnderwaterCanyonFeature`
```
struct __cppobj UnderwaterCanyonFeature : CanyonFeature
{
};

```

### `UnderwaterCanyonFeature_vtbl`
```
struct /*VFT*/ UnderwaterCanyonFeature_vtbl
{
  void (__fastcall *~CanyonFeature)(CanyonFeature *this);
  bool (__fastcall *carve)(CanyonFeature *this, BlockVolume *, BiomeSource *, Random *, const ChunkPos *, const Vec3 *, const Vec3 *, int, int, int, int, int, int, float, float, gsl::span<float const ,-1>);
  void (__fastcall *addFeature)(CanyonFeature *this, BlockVolume *, BiomeSource *, const ChunkPos *, Random *, int, int);
};

```

### `UnderwaterLargeCaveFeature`
```
struct __cppobj UnderwaterLargeCaveFeature : LargeCaveFeature
{
};

```

### `UnderwaterLargeCaveFeature_vtbl`
```
struct /*VFT*/ UnderwaterLargeCaveFeature_vtbl
{
  void (__fastcall *~LargeCaveFeature)(LargeCaveFeature *this);
  bool (__fastcall *carve)(LargeCaveFeature *this, BlockVolume *, BiomeSource *, Random *, const ChunkPos *, const Vec3 *, const Vec3 *, int, int, int, int, int, int, float, float);
};

```

### `useCommandFuncs::__l15::<lambda_b50d8574caf9d3cea7a38ac3a02cbfac>`
```
struct __cppobj useCommandFuncs::__l15::<lambda_b50d8574caf9d3cea7a38ac3a02cbfac>
{
  std::string *cmd;
};

```

### `UserAuthCheckStage::onAwake::__l2::<lambda_5e18b78c0bf03a4b0ce5df1efcfee300>`
```
struct __cppobj UserAuthCheckStage::onAwake::__l2::<lambda_5e18b78c0bf03a4b0ce5df1efcfee300>
{
  std::shared_ptr<BaseStage> this_ptr;
};

```

### `UserAuthCheckStage::onAwake::__l2::<lambda_af70cfd87d55eb0860a153ea72f4a511>`
```
struct __cppobj UserAuthCheckStage::onAwake::__l2::<lambda_af70cfd87d55eb0860a153ea72f4a511>
{
};

```

### `Urho3D::AnimatedModel::LoadConfigAllAsync::__l2::<lambda_d3ef0a69bb7dd4e2c816af45caa4932c>`
```
struct __cppobj Urho3D::AnimatedModel::LoadConfigAllAsync::__l2::<lambda_d3ef0a69bb7dd4e2c816af45caa4932c>
{
  std::shared_ptr<std::map<std::string,Json::Value> > vecContent;
  ResourcePackManager *resourceMgr;
};

```

### `Urho3D::LoadOneModelAsync::__l16::<lambda_17b8a0a1ed84a9bb0a0ecb1b0a4eb378>`
```
struct __cppobj Urho3D::LoadOneModelAsync::__l16::<lambda_17b8a0a1ed84a9bb0a0ecb1b0a4eb378>
{
  const std::string modelName;
  std::shared_ptr<Urho3D::ModelInfo> modelInfo;
};

```

### `Urho3D::LoadOneModelAsync::__l8::<lambda_26f8fbf8eb5c59959e2e7a3adf351f33>`
```
struct __cppobj Urho3D::LoadOneModelAsync::__l8::<lambda_26f8fbf8eb5c59959e2e7a3adf351f33>
{
  std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > > ioTask;
  std::shared_ptr<Urho3D::ModelInfo> modelInfo;
};

```

### `Urho3D::LoadOneModelAsync::__l11::<lambda_13bb81b237e48b8ac027b909c1ffd7d8>`
```
struct __cppobj Urho3D::LoadOneModelAsync::__l11::<lambda_13bb81b237e48b8ac027b909c1ffd7d8>
{
  std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > > ioTask;
  std::shared_ptr<Urho3D::ModelInfo> modelInfo;
};

```

### `Urho3D::AnimatedModel::LoadConfigAllAsync::__l2::<lambda_7dfe8951df89437ad58de6d8453346a2>`
```
struct __cppobj Urho3D::AnimatedModel::LoadConfigAllAsync::__l2::<lambda_7dfe8951df89437ad58de6d8453346a2>
{
  std::shared_ptr<std::map<std::string,Json::Value> > vecContent;
  ResourceLoadManager *resourceLoadManager;
};

```

### `unz_file_info_s`
```
struct unz_file_info_s
{
  unsigned int version;
  unsigned int version_needed;
  unsigned int flag;
  unsigned int compression_method;
  unsigned int dosDate;
  unsigned int crc;
  unsigned int compressed_size;
  unsigned int uncompressed_size;
  unsigned int size_filename;
  unsigned int size_file_extra;
  unsigned int size_file_comment;
  unsigned int disk_num_start;
  unsigned int internal_fa;
  unsigned int external_fa;
  tm_unz_s tmu_date;
};

```

### `unz64_file_pos_s`
```
struct unz64_file_pos_s
{
  unsigned __int64 pos_in_zip_directory;
  unsigned __int64 num_of_file;
};

```

### `unz_global_info64_s`
```
struct __declspec(align(8)) unz_global_info64_s
{
  unsigned __int64 number_entry;
  unsigned int size_comment;
};

```

### `unz_file_pos_s`
```
struct unz_file_pos_s
{
  unsigned int pos_in_zip_directory;
  unsigned int num_of_file;
};

```

### `unz_global_info_s`
```
struct unz_global_info_s
{
  unsigned int number_entry;
  unsigned int size_comment;
};

```

### `unz_file_info64_internal_s`
```
struct unz_file_info64_internal_s
{
  unsigned __int64 offset_curfile;
};

```

### `unz64_s`
```
struct unz64_s
{
  zlib_filefunc64_32_def_s z_filefunc;
  int is64bitOpenFunction;
  void *filestream;
  unz_global_info64_s gi;
  unsigned __int64 byte_before_the_zipfile;
  unsigned __int64 num_file;
  unsigned __int64 pos_in_central_dir;
  unsigned __int64 current_file_ok;
  unsigned __int64 central_pos;
  unsigned __int64 size_central_dir;
  unsigned __int64 offset_central_dir;
  unz_file_info64_s cur_file_info;
  unz_file_info64_internal_s cur_file_info_internal;
  file_in_zip64_read_info_s *pfile_in_zip_read;
  int encrypted;
  int isZip64;
};

```

### `Unpicklerobject`
```
struct Unpicklerobject
{
  __int64 ob_refcnt;
  _typeobject *ob_type;
  _iobuf *fp;
  _object *file;
  _object *readline;
  _object *read;
  _object *memo;
  _object *arg;
  Pdata *stack;
  _object *mark;
  _object *pers_func;
  _object *last_string;
  __int64 *marks;
  __int64 num_marks;
  __int64 marks_size;
  __int64 (__fastcall *read_func)(Unpicklerobject *, char **, __int64);
  __int64 (__fastcall *readline_func)(Unpicklerobject *, char **);
  __int64 buf_size;
  char *buf;
  _object *find_class;
};

```

### `UIAnimationController::_removeComponentAnimationCallback::__l3::<lambda_b26e14d6c1b9c9eef104a38936982491>`
```
struct __cppobj UIAnimationController::_removeComponentAnimationCallback::__l3::<lambda_b26e14d6c1b9c9eef104a38936982491>
{
  const UIControl **owner;
};

```

### `UIAnimationController::addComponentAnimationCallback::__l2::<lambda_7210179e1006d8249075f3b0d2d68ad9>`
```
struct __cppobj UIAnimationController::addComponentAnimationCallback::__l2::<lambda_7210179e1006d8249075f3b0d2d68ad9>
{
  UIControl *owner;
};

```

### `UIAnimationController::addComponentAnimationCallback::__l2::<lambda_7b6f49925859840d8fd11428fb7a2549>`
```
struct __cppobj UIAnimationController::addComponentAnimationCallback::__l2::<lambda_7b6f49925859840d8fd11428fb7a2549>
{
  UIControl *owner;
};

```

### `UIAnimLayout::{ctor}::__l2::<lambda_7ad873189bfc3a2858aea8085a0304a6>::()::__l4::<lambda_7fbe764f457bffbc58849281ef26e51b>`
```
struct __cppobj UIAnimLayout::{ctor}::__l2::<lambda_7ad873189bfc3a2858aea8085a0304a6>::()::__l4::<lambda_7fbe764f457bffbc58849281ef26e51b>
{
  std::_Vector_const_iterator<std::_Vector_val<std::_Simple_types<ui::AxisOffset> > > *it;
};

```

### `UIAnimationComponent::_animationTick::__l30::<lambda_0d490c9d8979e319a498116b849b59ac>`
```
struct __cppobj UIAnimationComponent::_animationTick::__l30::<lambda_0d490c9d8979e319a498116b849b59ac>
{
  UIAnim *anim;
};

```

### `UIAnimLayout::{ctor}::__l2::<lambda_ab9eb31eb3ff274d7b009430ab196642>`
```
struct __cppobj UIAnimLayout::{ctor}::__l2::<lambda_ab9eb31eb3ff274d7b009430ab196642>
{
  UIAnimLayout::{ctor}::__l2::<lambda_b740528f05b815a1d9f33202085666a7> *axisOffsetComp;
};

```

### `UIAnimLayout::{ctor}::__l2::<lambda_7ad873189bfc3a2858aea8085a0304a6>`
```
struct __cppobj UIAnimLayout::{ctor}::__l2::<lambda_7ad873189bfc3a2858aea8085a0304a6>
{
};

```

### `UIControlFactory::_populateFactoryComponent::__l2::<lambda_b596f85625c438a04391c64a7f86f22b>`
```
struct __cppobj UIControlFactory::_populateFactoryComponent::__l2::<lambda_b596f85625c438a04391c64a7f86f22b>
{
  UIControl *ownerControl;
  UIControlFactory *const __this;
  const UIControlFactoryContext *context;
};

```

### `UIControlFactory::_populateFocusContainerComponent::__l2::<lambda_ff28a1c32232589a53cb90f64db45918>`
```
struct __cppobj UIControlFactory::_populateFocusContainerComponent::__l2::<lambda_ff28a1c32232589a53cb90f64db45918>
{
  const UIResolvedDef *def;
  UIControlFactory *const __this;
  FocusContainerComponent **focusContainerComponent;
};

```

### `UserDataScreenController::_requestPlayerProfiles::__l5::<lambda_1490c5e2375cbfb0c0f7c887786c437b>::()::__l9::<lambda_f6c6de009e692f4423d3c18cd245ef29>`
```
struct __cppobj UserDataScreenController::_requestPlayerProfiles::__l5::<lambda_1490c5e2375cbfb0c0f7c887786c437b>::()::__l9::<lambda_f6c6de009e692f4423d3c18cd245ef29>
{
  const Social::XboxLiveUserProfileData **user;
};

```

### `UserDataScreenController::_requestThirdPartyPics::__l2::<lambda_6f30ed4af1084cd590da280d6f212311>::()::__l5::<lambda_9074e219380beb24676dd2b0938317b6>`
```
struct __cppobj UserDataScreenController::_requestThirdPartyPics::__l2::<lambda_6f30ed4af1084cd590da280d6f212311>::()::__l5::<lambda_9074e219380beb24676dd2b0938317b6>
{
  const std::string playerId;
};

```

### `UserDataScreenController::_updatePlayerList::__l2::<lambda_4c41d63c081626750f375c082936753a>`
```
struct __cppobj UserDataScreenController::_updatePlayerList::__l2::<lambda_4c41d63c081626750f375c082936753a>
{
};

```

### `unregisterCallback::__l2::<lambda_da769d13dd4e02f7266b06dad4d7460a>`
```
struct __cppobj unregisterCallback::__l2::<lambda_da769d13dd4e02f7266b06dad4d7460a>
{
  void *token;
};

```

### `unregisterCallback::__l2::<lambda_e34fd8fbb8d1d32152349b260cbc8bad>`
```
struct __cppobj unregisterCallback::__l2::<lambda_e34fd8fbb8d1d32152349b260cbc8bad>
{
  void *token;
};

```

### `unregisterCallback::__l2::<lambda_d1e303b899cfa439d2a5599afb887f22>`
```
struct __cppobj unregisterCallback::__l2::<lambda_d1e303b899cfa439d2a5599afb887f22>
{
  void *token;
};

```

### `UIModification::move::__l5::<lambda_b02b0be281c25aabff263565d3832d9d>::()::__l2::<lambda_eda5d03da7233b364efc281fe6eda383>`
```
struct __cppobj UIModification::move::__l5::<lambda_b02b0be281c25aabff263565d3832d9d>::()::__l2::<lambda_eda5d03da7233b364efc281fe6eda383>
{
  int index;
};

```

### `UIDefRepository::_applyGlobalColorFormat::__l2::<lambda_04db596b1c24f43eb8080983ab401f6e>`
```
struct __cppobj UIDefRepository::_applyGlobalColorFormat::__l2::<lambda_04db596b1c24f43eb8080983ab401f6e>
{
  UIDefRepository *const __this;
};

```

### `UIEval::evalExpression::__l2::<lambda_8e42635ba22252d090b3780ff82d9f4c>`
```
struct __cppobj UIEval::evalExpression::__l2::<lambda_8e42635ba22252d090b3780ff82d9f4c>
{
};

```

### `UIEval::evalExpression::__l2::<lambda_04e23dceb1515200fa3df65ebdb5e6c0>`
```
struct __cppobj UIEval::evalExpression::__l2::<lambda_04e23dceb1515200fa3df65ebdb5e6c0>
{
  UIEval::evalExpression::__l2::<lambda_8e42635ba22252d090b3780ff82d9f4c> isOperator;
};

```

### `UIEval::evalExpression::__l2::<lambda_2f7b847e83e10d031ca89cbb5435f003>`
```
struct __cppobj UIEval::evalExpression::__l2::<lambda_2f7b847e83e10d031ca89cbb5435f003>
{
  std::vector<Json::Value *> *variablesStack;
  const Json::Value *localStack;
};

```

### `UiExpression::evaluate::__l2::<lambda_80da289f6a5af3b2a0a6c774543cf53e>`
```
struct __cppobj UiExpression::evaluate::__l2::<lambda_80da289f6a5af3b2a0a6c774543cf53e>
{
};

```

### `UiExpression::evaluate::__l2::<lambda_8ca8b6b89774593dcf8d749618ffc4cd>`
```
struct __cppobj UiExpression::evaluate::__l2::<lambda_8ca8b6b89774593dcf8d749618ffc4cd>
{
  UiExpression::evaluate::__l2::<lambda_80da289f6a5af3b2a0a6c774543cf53e> operatorPrecedence;
};

```

### `UIResolvedDef::_pushVariables::__l5::<lambda_9c40e1472112e6e7b82658cd1f5df9ca>`
```
struct __cppobj UIResolvedDef::_pushVariables::__l5::<lambda_9c40e1472112e6e7b82658cd1f5df9ca>
{
  UIResolvedDef *const __this;
};

```

### `UIModification::move::__l5::<lambda_b02b0be281c25aabff263565d3832d9d>`
```
struct __cppobj UIModification::move::__l5::<lambda_b02b0be281c25aabff263565d3832d9d>
{
  UIModification *const __this;
};

```

### `UiExpression::evaluate::__l2::<lambda_7b621d55ae36d121a2dc626262fe6ca2>`
```
struct __cppobj UiExpression::evaluate::__l2::<lambda_7b621d55ae36d121a2dc626262fe6ca2>
{
};

```

### `UiExpression::evaluate::__l2::<lambda_c71438f2516743994815b18824b9ee90>`
```
struct __cppobj UiExpression::evaluate::__l2::<lambda_c71438f2516743994815b18824b9ee90>
{
};

```

### `UIResolvedDef::_replaceVarsInRefString::__l2::<lambda_f030c3e2857621ed62e7233f70b5d432>`
```
struct __cppobj UIResolvedDef::_replaceVarsInRefString::__l2::<lambda_f030c3e2857621ed62e7233f70b5d432>
{
};

```

### `UnderwaterTorchBlock::animateTick::__l7::<lambda_e54b68f30e068896e9e6b14638f51d48>::()::__l2::Literal`
```
struct __cppobj UnderwaterTorchBlock::animateTick::__l7::<lambda_e54b68f30e068896e9e6b14638f51d48>::()::__l2::Literal
{
};

```

### `UnderwaterTorchBlock::animateTick::__l7::<lambda_e54b68f30e068896e9e6b14638f51d48>`
```
struct __cppobj UnderwaterTorchBlock::animateTick::__l7::<lambda_e54b68f30e068896e9e6b14638f51d48>
{
};

```

### `Urho3D::AnimatedModel::SetUsePlayerSkinTexture::__l2::<lambda_5727e2c6da58f6c34e317380571c50ed>`
```
struct __cppobj Urho3D::AnimatedModel::SetUsePlayerSkinTexture::__l2::<lambda_5727e2c6da58f6c34e317380571c50ed>
{
  Urho3D::AnimatedModel *const __this;
  Player *player;
};

```

### `Urho3D::ModelPartGroup::Render::__l25::<lambda_fc3ea086288d9a4679822873927759c1>`
```
struct __cppobj Urho3D::ModelPartGroup::Render::__l25::<lambda_fc3ea086288d9a4679822873927759c1>
{
};

```

### `Util::compareNoCase::__l5::<lambda_66ffc931f665b533e37bf255483dbe9b>`
```
struct __cppobj Util::compareNoCase::__l5::<lambda_66ffc931f665b533e37bf255483dbe9b>
{
};

```

### `Util::simpleJoin::__l2::<lambda_43e0745da616a7052673d3c8c0f22b19>`
```
struct __cppobj Util::simpleJoin::__l2::<lambda_43e0745da616a7052673d3c8c0f22b19>
{
};

```

### `Util::toUpper::__l2::<lambda_28b25c038d0802432cc5bbd48e2a8713>`
```
struct __cppobj Util::toUpper::__l2::<lambda_28b25c038d0802432cc5bbd48e2a8713>
{
};

```

### `Util::toLower::__l2::<lambda_4927a132a8d64a0f7b7af34c6e1174b4>`
```
struct __cppobj Util::toLower::__l2::<lambda_4927a132a8d64a0f7b7af34c6e1174b4>
{
};

```

### `Util::toLowerInPlace::__l2::<lambda_4e5f751b7e4667056c00a96eb42d1c60>`
```
struct __cppobj Util::toLowerInPlace::__l2::<lambda_4e5f751b7e4667056c00a96eb42d1c60>
{
};

```

### `Util::toUpper::__l2::<lambda_5e09b8c67383841454b48757d7174023>`
```
struct __cppobj Util::toUpper::__l2::<lambda_5e09b8c67383841454b48757d7174023>
{
};

```

### `Util::toLower::__l2::<lambda_b8e1907913916984e1f93d32888049a9>`
```
struct __cppobj Util::toLower::__l2::<lambda_b8e1907913916984e1f93d32888049a9>
{
};

```

### `Util::toLower::__l2::<lambda_d8b5fe84894cc768bbfd002181788abf>`
```
struct __cppobj Util::toLower::__l2::<lambda_d8b5fe84894cc768bbfd002181788abf>
{
};

```

### `Util::Url::isValidIP::__l5::<lambda_186ee2cc104ead6bb02f694a6f8f6d99>`
```
struct __cppobj Util::Url::isValidIP::__l5::<lambda_186ee2cc104ead6bb02f694a6f8f6d99>
{
};

```

### `Util::Url::isValidIP::__l10::<lambda_6c9c971572d162af7bb515ae8aaef667>`
```
struct __cppobj Util::Url::isValidIP::__l10::<lambda_6c9c971572d162af7bb515ae8aaef667>
{
};

```

