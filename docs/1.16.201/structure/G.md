# G
### `glm::tvec3<float,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `$D6EC15B927D7F6093279F9000A61AE1B` | ___u0
4 | (4) `$FCA921BEFA95D44D60D784C4D8D7ED2C` | ___u1
8 | (4) `$9B996AAE057415E4B0A10C768262D912` | ___u2


### `GameStates`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,std::variant<std::string,int,bool,float,double>>` | states


### `glm::tvec2<float,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `$D6EC15B927D7F6093279F9000A61AE1B` | ___u0
4 | (4) `$FCA921BEFA95D44D60D784C4D8D7ED2C` | ___u1


### `GeneralSettingsScreenController::_initLanguageList::__l2::<lambda_33dc1399bc4810b931d2d21893cb3876>`
Offset | Type | Name
-|-|-|-


### `GameVersion`
Offset | Type | Name
-|-|-|-
0 | (20) `unsigned int[5]` | mDigit
24 | (32) `std::string` | mString


### `glm::tmat4x4<float,0>`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tvec4<float,0>[4]` | value


### `glm::tvec4<float,0>`
Offset | Type | Name
-|-|-|-
0 | (16) `$6314C8CD613830F8484DA188117CC97D` | ___u0


### `glm::detail::storage<float,16,0>::type`
Offset | Type | Name
-|-|-|-
0 | (16) `unsigned __int8[16]` | data


### `GameRenderer::_extractFrame::__l5::<lambda_66c49b5011f688feb0a3b751971e3cda>`
Offset | Type | Name
-|-|-|-
0 | (8) `ScreenContext *` | screenContext


### `GameControllerHandler_Windows`
Offset | Type | Name
-|-|-|-
0 | (280) `GameControllerHandler` | baseclass_0
280 | (64) `GameControllerHandler_Windows::InputState_Windows` | mAllPadStates
344 | (80) `SPSCQueue<GameControllerHandler_Windows::InputState_Windows,512>` | mInputQueue


### `GameControllerHandler`
Offset | Type | Name
-|-|-|-
0 | (8) `GameControllerHandler_vtbl *` | __vftable
8 | (64) `std::unordered_map<unsigned int,int>` | mButtonMap
72 | (24) `std::vector<std::unordered_map<unsigned int,enum GameControllerButtonState>>` | mButtonState
96 | (32) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >[4]` | nextCheckTime
128 | (24) `std::vector<float>` | mLeftTrigger
152 | (24) `std::vector<float>` | mRightTrigger
176 | (32) `std::vector<bool>` | mLeftStickTouched
208 | (32) `std::vector<bool>` | mRightStickTouched
240 | (16) `unsigned int[4]` | mInputProcessResult
256 | (16) `std::thread` | mPollingThread
272 | (1) `std::atomic<bool>` | mJoinThreads


### `GameControllerHandler_Windows::InputState_Windows`
Offset | Type | Name
-|-|-|-
0 | (64) `_XINPUT_STATE[4]` | mInputState


### `GameServer`
Offset | Type | Name
-|-|-|-
0 | (8) `GameServer_vtbl *` | __vftable
8 | (8) `ServerInstance *` | mServerInstance


### `GameRuleId`
Offset | Type | Name
-|-|-|-
0 | (4) `NewType<int>` | baseclass_0


### `GlobalRegistration`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(RakNet::BitStream *, RakNet::Packet *)` | registerFunctionPointer
8 | (8) `void (__fastcall *)(RakNet::BitStream *, RakNet::BitStream *, RakNet::Packet *)` | registerBlockingFunctionPointer
16 | (48) `char[48]` | functionName
64 | (1) `unsigned __int8` | messageId
68 | (4) `int` | callPriority


### `gc_generation`
Offset | Type | Name
-|-|-|-
0 | (24) `_gc_head` | head
24 | (4) `int` | threshold
28 | (4) `int` | count


### `grammar`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | g_ndfas
8 | (8) `dfa *` | g_dfa
16 | (16) `labellist` | g_ll
32 | (4) `int` | g_start
36 | (4) `int` | g_accel


### `GUID`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Data1
4 | (2) `unsigned __int16` | Data2
6 | (2) `unsigned __int16` | Data3
8 | (8) `unsigned __int8[8]` | Data4


### `GameControllerManager`
Offset | Type | Name
-|-|-|-
0 | (8) `IGameControllerManager` | baseclass_0
8 | (24) `std::vector<std::shared_ptr<GameController>>` | mGameControllers
32 | (8) `unsigned __int64` | mMaxGameControllerButtons
40 | (1) `bool` | mIsActive
48 | (24) `std::vector<void const *>` | mConsumerRegistry
72 | (4) `ControllerRefreshState` | mControllerRefreshState
76 | (1) `bool` | mAllowSplitscreen
77 | (1) `unsigned __int8` | mClientControllerCount
80 | (64) `std::function<enum GameControllerErrorType __cdecl(void)>` | mPlatformSpecificControllerErrorRetrievalFunc


### `GlobalTags`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mNotTags


### `glm::tvec3<int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `$A293B79558BF338540E1F5C0688B11E7` | ___u0
4 | (4) `$939912DDF64FF6D2D4C7648C131EFFDB` | ___u1
8 | (4) `$65B41681DBFB7735E325E5971806959E` | ___u2


### `GeometryPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<GeometryInfo>` | mGeometryInfoPtr


### `glm::tquat<float,0>`
Offset | Type | Name
-|-|-|-
0 | (16) `$49D23D25C9A4C920027AFE1D96E7D964` | ___u0


### `glTF::Texture`
Offset | Type | Name
-|-|-|-
0 | (8) `glTF::OptionalField<enum glTF::Texture::Format>` | format
8 | (8) `glTF::OptionalField<enum glTF::Texture::Format>` | internalFormat
16 | (8) `glTF::ObjectID` | sampler
24 | (8) `glTF::ObjectID` | source
32 | (8) `glTF::OptionalField<enum glTF::Texture::Target>` | target
40 | (8) `glTF::OptionalField<enum glTF::Texture::Type>` | type
48 | (32) `std::string` | name
80 | (4) `int` | id


### `glTF::OptionalField<enum glTF::Texture::Format>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (4) `glTF::Texture::Format` | mValue


### `glTF::ObjectID`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (4) `int` | mID


### `glTF::OptionalField<enum glTF::Texture::Target>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (4) `glTF::Texture::Target` | mValue


### `glTF::OptionalField<enum glTF::Texture::Type>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (4) `glTF::Texture::Type` | mValue


### `glTF::Node`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | camera
32 | (24) `std::vector<int>` | children
56 | (24) `std::vector<int>` | skeleton
80 | (32) `std::string` | skin
112 | (32) `std::string` | jointName
144 | (68) `glTF::OptionalField<glm::tmat4x4<float,0> >` | matrix
212 | (8) `glTF::ObjectID` | mesh
220 | (20) `glTF::OptionalField<glm::tvec4<float,0> >` | rotation
240 | (16) `glTF::OptionalField<glm::tvec3<float,0> >` | scale
256 | (16) `glTF::OptionalField<glm::tvec3<float,0> >` | translation
272 | (32) `std::string` | name
304 | (4) `int` | id


### `glTF::OptionalField<glm::tmat4x4<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (64) `glm::tmat4x4<float,0>` | mValue


### `glTF::OptionalField<glm::tvec4<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (16) `glm::tvec4<float,0>` | mValue


### `glTF::OptionalField<glm::tvec3<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (12) `glm::tvec3<float,0>` | mValue


### `glTF::Accessor`
Offset | Type | Name
-|-|-|-
0 | (8) `glTF::ObjectID` | bufferView
8 | (4) `int` | byteOffset
12 | (8) `glTF::OptionalField<int>` | byteStride
20 | (4) `glTF::Primitive::ComponentType` | componentType
24 | (4) `int` | count
28 | (4) `glTF::Accessor::Type` | type
32 | (24) `std::vector<float>` | min
56 | (24) `std::vector<float>` | max
80 | (32) `std::string` | name
112 | (4) `int` | id


### `glTF::OptionalField<int>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
4 | (4) `int` | mValue


### `glTF::BufferView`
Offset | Type | Name
-|-|-|-
0 | (8) `glTF::ObjectID` | buffer
8 | (4) `int` | byteOffset
12 | (4) `int` | byteLength
16 | (32) `std::string` | name
48 | (4) `int` | id


### `glTF::Material`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | technique
32 | (16) `Json::Value` | values
48 | (16) `Json::Value` | extensions
64 | (16) `Json::Value` | pbrMetallicRoughness
80 | (4) `glTF::Material::AlphaMode` | alphaMode
88 | (32) `std::string` | name
120 | (4) `int` | id


### `glTF::Mesh::Primitive`
Offset | Type | Name
-|-|-|-
0 | (16) `Json::Value` | attributes
16 | (8) `glTF::ObjectID` | indices
24 | (8) `glTF::ObjectID` | material
32 | (4) `glTF::Mesh::Primitive::Mode` | mode


### `glm::tmat3x3<float,0>`
Offset | Type | Name
-|-|-|-
0 | (36) `glm::tvec3<float,0>[3]` | value


### `GameArguments::_onUri::__l52::<lambda_f3877d629a90262d9db07e4c779ee301>`
Offset | Type | Name
-|-|-|-
0 | (8) `GameArguments *const` | __this
8 | (32) `const std::string` | creatorId


### `GameArguments::_tryImport_RequestPermission::__l2::<lambda_cae3f5a7339e66e2c27cf99b89a61ae5>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<DefaultImportContext>` | context
16 | (32) `Core::PathBuffer<std::string >` | mcContentHeapPath
48 | (1) `bool` | fromTemp
49 | (1) `bool` | loadLevel
56 | (8) `MinecraftGame *` | mMinecraft


### `GameRules`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GameRule>` | mGameRules


### `glm::tvec2<int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `$A293B79558BF338540E1F5C0688B11E7` | ___u0
4 | (4) `$939912DDF64FF6D2D4C7648C131EFFDB` | ___u1


### `GuiMessage`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mType
8 | (32) `std::string` | mMessage
40 | (32) `std::string` | mTTSMessage
72 | (32) `std::string` | mUsername
104 | (32) `std::string` | mFullString
136 | (1) `bool` | mForceVisible
140 | (4) `float` | mDuration
144 | (1) `bool` | mHasBeenSeen


### `GridArea<std::shared_ptr<LevelChunk> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<LevelChunk> >)>` | destroy
64 | (64) `std::function<void __cdecl(buffer_span<Pos>,buffer_span_mut<std::shared_ptr<LevelChunk> >)>` | generate
128 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<LevelChunk> >,buffer_span<unsigned int>)>` | add
192 | (48) `Bounds` | mBounds
240 | (24) `std::vector<std::shared_ptr<LevelChunk>>` | mChunks
264 | (24) `std::vector<std::shared_ptr<LevelChunk>>` | mNewChunks
288 | (1) `bool` | mCircle
290 | (2) `__int16` | mMinHeight
292 | (2) `__int16` | mMaxHeight


### `GeneralSettingsScreenControllerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<int __cdecl(void)>` | mGetCurrentLanguageIndex
64 | (64) `std::function<int __cdecl(void)>` | mGetNumLanguages
128 | (64) `std::function<std::vector<std::pair<std::string,std::string >> __cdecl(void)>` | mGetLanguages
192 | (64) `std::function<StorageManagementScreenControllerProxy * __cdecl(void)>` | mGetStorageManagementScreenController
256 | (64) `std::function<void __cdecl(void)>` | mPushSafeZoneScreen


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d4ab045c0ba8654b90f3c26ccc1fb19f>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a2f75c3d0c5507430a70e7c735ae59c4>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6095b08f65ca6283ff91616f26f1ee11>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5ef691e838f73d29d1236f0f374fdfcd>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | crossPlatformOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_544e4745d968c2d79bc6dd83024e9e17>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5910a7c7e964f8fce6fc83f7d0959703>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_fec65089e120d46096f56cc932709bdd>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_8b9d07fba3b37985d05747d08e02d829>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6bf365de754ac30e72427a022446f753>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_571a98d75569e7e58d586d03fc71eb82>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0fd794229b6dcf82c3c2dff8f8f547f4>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_34c1213e53373d9c0710b91d9c42355b>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5935f54f9b6a233fcfda3f3e8eea6123>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_099e32c65cd60b98bde0f0df5dfec5d3>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l14::<lambda_51f45b8d50d1d1c86665687c14b9e9ad>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | rayTracingOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l14::<lambda_f1697f3a11285a7013672781c8afe73b>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | rayTracingOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_77f19575cc2783dd88963a20a61cc55d>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_011e72837715ce60663e8d35e92fccfd>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ca70dccea1f789c97b83687ca5ffd5db>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_80c3bae7177e7222c6623c0ef820bd17>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_c2eb30cff0a3aff87843ad9c1baaa1b9>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | textureHotReloaderOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_77faca43f8f22db93dec5bfa32bd2e59>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | textureHotReloaderOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_96e8f65078131582e8e2e5741d21ba28>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_95e834eee4400f79962c22cdd3e69ff1>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | interfaceOpacityOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6e83b579f643b25832eec406367dda38>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_fba135e4c0c424d22a36368ee2045ac9>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | interfaceOpacitySplitscreenOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_38c627201a2f3fc876bf417e93421e94>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_4483cd7c217c0e4206043ddf23f1621f>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | textBackgroundOpacityOption


### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_9d97543565157045750487d23042c921>`
Offset | Type | Name
-|-|-|-


### `GeneralSettingsScreenController::_registerEventHandlers::__l6::<lambda_2823966488ed2c7c76688dfc7fb92a0b>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this
8 | (32) `const std::string` | volumeSlider


### `GeneralSettingsScreenController::_handleLanguageChoiceClick::__l8::<lambda_c337a072ff7ddec318c84ca8bddb0440>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeneralSettingsScreenController *const` | __this
8 | (32) `const std::string` | selectedLanguageCode
40 | (4) `int` | i


### `GamepadCursorData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mEnabled
1 | (1) `bool` | mTempDisabled
4 | (4) `float` | mSensitivity


### `GameControllerMapper::GamepadStickTurnData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | turnStickActive
4 | (8) `glm::tvec2<float,0>` | lastTurnStickPos
12 | (4) `int` | controllerId


### `Geometry::NodeVertex`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mPositionIndex
4 | (4) `unsigned int` | mNormalIndex
8 | (4) `unsigned int` | mUVIndex


### `GeometryGroup::addGeometries::__l5::<lambda_26224e9023beb42bfe5dc8bb122f2e89>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeometryGroup *const` | __this
8 | (16) `std::shared_ptr<GeometryInheritanceTree>` | inheritance
24 | (8) `ResourceLoadManager *` | resourceLoadManager
32 | (64) `std::function<void __cdecl(void)>` | mtcb


### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<GeometryInheritanceTree>` | inheritance
16 | (8) `ResourcePackManager *` | resourcePackManager
24 | (8) `ResourceLoadManager *` | resourceLoadManager
32 | (64) `std::function<void __cdecl(Json::Value &)>` | postLoadFixup
96 | (16) `std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> >` | allTreesLoaded


### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_85e9c86508f88dae86a2a1c25921877e>`
Offset | Type | Name
-|-|-|-
0 | (8) `GeometryGroup *const` | __this
8 | (16) `std::shared_ptr<GeometryInheritanceTree>` | inheritance
24 | (8) `ResourceLoadManager *` | resourceLoadManager
32 | (64) `std::function<void __cdecl(GeometryGroup &,std::string const &,ModelParent const &)>` | loadModelFunction


### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3>::()::__l2::<lambda_4fc4ea1a1a6a82223f42b33031651ca3>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<GeometryInheritanceTree>` | inheritance
16 | (64) `std::function<void __cdecl(Json::Value &)>` | postLoadFixup
80 | (32) `const Core::Path` | fileWithExtension
112 | (32) `std::string` | fullPath
144 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<std::string > >` | ioTask
160 | (1) `const bool` | isBaseGamePack


### `Geometry::NodePolyMesh`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Vec3>` | mPositions
24 | (24) `std::vector<Vec3>` | mNormals
48 | (24) `std::vector<Vec2>` | mUVs
72 | (24) `std::vector<std::array<Geometry::NodeVertex,3>>` | mTris
96 | (24) `std::vector<std::array<Geometry::NodeVertex,4>>` | mQuads
120 | (1) `bool` | mAreUVsNormalized


### `glm::tmat2x3<float,0>`
Offset | Type | Name
-|-|-|-
0 | (24) `glm::tvec3<float,0>[2]` | value


### `GridArea<std::shared_ptr<RenderChunkInstanced> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >)>` | destroy
64 | (64) `std::function<void __cdecl(buffer_span<Pos>,buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >)>` | generate
128 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >,buffer_span<unsigned int>)>` | add
192 | (48) `Bounds` | mBounds
240 | (24) `std::vector<std::shared_ptr<RenderChunkInstanced>>` | mChunks
264 | (24) `std::vector<std::shared_ptr<RenderChunkInstanced>>` | mNewChunks
288 | (1) `bool` | mCircle
290 | (2) `__int16` | mMinHeight
292 | (2) `__int16` | mMaxHeight


### `GridArea<std::shared_ptr<RenderChunkInstanced> >::Definition`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | chunkSide
4 | (2) `__int16` | minHeight
6 | (2) `__int16` | maxHeight
8 | (1) `bool` | circle
16 | (64) `std::function<void __cdecl(buffer_span<Pos>,buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >)>` | generate
80 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >)>` | destroy
144 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >,buffer_span<unsigned int>)>` | add


### `GameSaveSystem::isSettingsOutOfDate::__l2::<lambda_105ecdbfe54d5ac2abcd0e6224f7f9f9>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(Core::Result,bool)>` | callback
64 | (32) `const Core::PathBuffer<std::string >` | cloudSyncFile


### `GameSaveSystem::syncSettings::__l2::<lambda_087ab1ad463405e9bdd7b7c6c815050d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrSettingsContainer
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `GameSaveSystem::syncSettings::__l2::<lambda_af7b59bc0574b72beedf639a0a9c9cd6>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Core::RemoteStorageProvider>` | wptrRemoteStorage
16 | (16) `std::weak_ptr<SaveContainer>` | wptrSettingsContainer
32 | (16) `std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >` | syncContext
48 | (16) `GameSaveSystem::syncSettings::__l2::<lambda_c2a3e921cc377171e610bc4d778f3c75>` | hackSyncFixCallback
64 | (32) `const Core::PathBuffer<std::string >` | cloudSyncFile


### `GameSaveSystem::syncSettings::__l2::<lambda_c2a3e921cc377171e610bc4d778f3c75>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrSettingsContainer


### `GameSaveSystem::syncSettingsMeta::__l5::<lambda_7d226060555da2f475a95af52f639023>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrSettingsContainer
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `GameSaveSystem::syncWorldManifest::__l16::<lambda_db61e1f5b0cf47ee576841b259520437>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrWorldContainer
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `GameSaveSystem::syncWorldsMeta::__l5::<lambda_7f3fc24b0b1656b289448225bd9f02e9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrWorldsContainer
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `GameSaveSystem::syncWorld::__l5::<lambda_4ed66249c0727f6b70239698a8759237>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<SaveContainer>` | wptrWorldContainer
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `glm::tvec2<unsigned short,0>`
Offset | Type | Name
-|-|-|-
0 | (2) `$AA0D9C0E645A4C46932A70C129AAE1AB` | ___u0
2 | (2) `$2042176E05E2A5B53562E58BCDFC4679` | ___u1


### `glm::tvec2<unsigned int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `$A6A78DDC903BEAF524B7DB4CBBB586E3` | ___u0
4 | (4) `$CBCDD465F132EF09A2AEEB3FEE02687F` | ___u1


### `GiveableTrigger`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ItemDescriptor>` | mGiveableItems
24 | (320) `DefinitionTrigger` | mOnGive
344 | (4) `float` | mCoolDown


### `GiveableComponent::getInteraction::__l30::<lambda_e19672d2e3496da46afdf667e255c2e8>`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | player
8 | (8) `Actor *` | owner
16 | (248) `ItemStack` | originalItem
264 | (8) `ContainerComponent *` | inventory
272 | (352) `const GiveableTrigger` | trigger
624 | (160) `VariantParameterList` | parameters


### `GroupSizeSystem::tick::__l2::<lambda_9ba22c967da17c1c226bddf83c81b323>`
Offset | Type | Name
-|-|-|-
0 | (8) `GroupSizeSystem *const` | __this


### `GameRule`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mShouldSave
1 | (1) `_BYTE[1]` | mType
4 | (4) `GameRule::Value` | mValue
8 | (32) `std::string` | mName
40 | (1) `bool` | mAllowUseInCommand
41 | (1) `bool` | mIsDefaultSet
42 | (1) `bool` | mRequiresCheats
48 | (64) `std::function<void __cdecl(GameRule &)>` | mTagNotFoundCallback
112 | (64) `std::function<bool __cdecl(GameRule::Value const &,GameRule::ValidationError *)>` | mValidateValueCallback


### `GameRule::Value`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | boolVal
1 | (4) `int` | intVal
2 | (4) `float` | floatVal


### `GameRuleCommand::InitProxy`
Offset | Type | Name
-|-|-|-
0 | (8) `GameRules *` | mGameRules


### `GoalDefinition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `int` | mPriority
36 | (4) `int` | mRequiredControlFlags
40 | (4) `int` | mScanInterval
44 | (4) `float` | mTargetSearchHeight
48 | (4) `int` | mPersistTargetTicks
52 | (1) `bool` | mNearestSetPersistent
56 | (4) `float` | mWithinDefault
60 | (4) `float` | mMaxDist
64 | (4) `float` | mWalkSpeedModifier
68 | (4) `float` | mSprintSpeedModifier
72 | (24) `std::vector<MobDescriptor>` | mMobDescriptions
96 | (4) `float` | mSneakSpeedModifier
100 | (4) `float` | mStartDistance
104 | (4) `float` | mStopDistance
108 | (4) `int` | mRoarDuration
112 | (4) `int` | mRoarAttackTime
116 | (4) `int` | mRoarDamage
120 | (4) `int` | mRoarStrength
124 | (4) `int` | mRoarRange
128 | (64) `ActorFilterGroup` | mKnockbackFilter
192 | (64) `ActorFilterGroup` | mDamageFilter
256 | (320) `DefinitionTrigger` | mOnRoarEnd
576 | (4) `float` | mYd
580 | (1) `bool` | mLeapSetPersistent
584 | (4) `float` | mStalkSpeed
588 | (4) `float` | mMaxStalkDist
592 | (4) `float` | mLeapHeight
596 | (4) `float` | mLeapDistance
600 | (4) `float` | mPounceMaxDistance
604 | (4) `float` | mStrikeDistance
608 | (4) `float` | mStuckTime
616 | (64) `ActorFilterGroup` | mBlockFilter
680 | (1) `bool` | mStalkSetPersistent
684 | (4) `float` | mLookDistance
688 | (4) `int` | mAngleOfViewX
692 | (4) `int` | mAngleOfViewY
696 | (4) `float` | mProbability
704 | (64) `ActorFilterGroup` | mTargetFilter
768 | (4) `int` | mMinLookTime
772 | (4) `int` | mMaxLookTime
776 | (4) `int` | mMinLookAroundTime
780 | (4) `int` | mMaxLookAroundTime
784 | (4) `float` | mMinimumRadius
788 | (1) `bool` | mBroadcast
792 | (4) `float` | mBroadcastRange
800 | (320) `DefinitionTrigger` | mWithinRadiusEvent
1120 | (320) `DefinitionTrigger` | mHurtByTargetEvent
1440 | (4) `float` | mPercentChance
1444 | (4) `_BYTE[4]` | mAttackTypes
1448 | (4) `int` | mRandomStopInterval
1452 | (4) `float` | mReachMultiplier
1456 | (4) `float` | mMeleeFOV
1460 | (1) `bool` | mAttackOnce
1464 | (4) `int` | mRandomSoundInterval
1468 | (1) `bool` | mRequireCompletePath
1472 | (320) `DefinitionTrigger` | mOnAttack
1792 | (4) `float` | mAttackDuration
1796 | (4) `float` | mHitDelay
1800 | (4) `LevelSoundEvent` | mDelayedAttackSound
1808 | (320) `DefinitionTrigger` | mOnEat
2128 | (4) `int` | mDelayBeforeEating
2136 | (24) `std::vector<DefinitionTrigger>` | mOnHomeEvents
2160 | (24) `std::vector<DefinitionTrigger>` | mOnFailedTriggers
2184 | (320) `DefinitionTrigger` | mOnLayEvent
2504 | (320) `DefinitionTrigger` | mOnWorkArrivalEvent
2824 | (4) `float` | mTargetDist
2828 | (4) `float` | mSpeedModifier
2832 | (4) `MaterialType` | mMaterialType
2836 | (4) `int` | mSearchRange
2840 | (4) `int` | mSearchHeight
2844 | (4) `int` | mSearchCount
2848 | (4) `float` | mGoalRadius
2856 | (120) `GoalDefinition::<unnamed_type_mMoveToBlockGoalData>` | mMoveToBlockGoalData
2976 | (4) `float` | mWithin
2980 | (1) `bool` | mIgnoreMobDamage
2981 | (1) `bool` | mForceUse
2984 | (32) `std::string` | mPanicSound
3016 | (24) `std::vector<enum ActorDamageCause>` | mDamageSources
3040 | (4) `float` | mLookAhead
3044 | (4) `float` | mCenteredGap
3048 | (4) `float` | mMoveSpeed
3052 | (4) `int` | mEntityCount
3056 | (4) `int` | mXZDist
3060 | (4) `int` | mYDist
3064 | (4) `float` | mYOffset
3068 | (4) `int` | mInterval
3072 | (1) `bool` | mAvoidSurface
3076 | (4) `float` | mCooldown
3080 | (1) `__int8` | _bf_c08
3084 | (4) `float` | mRangedFOV
3088 | (4) `int` | mAttackIntervalMin
3092 | (4) `int` | mAttackIntervalMax
3096 | (4) `float` | mAttackRadius
3100 | (4) `float` | mAttackRadiusMin
3104 | (4) `float` | mChargeChargedTrigger
3108 | (4) `float` | mChargeShootTrigger
3112 | (4) `int` | mBurstShots
3116 | (4) `float` | mBurstInterval
3120 | (1) `bool` | mRangedSetPersistent
3121 | (1) `__int8` | _bf_c31
3122 | (1) `__int8` | _bf_c32
3123 | (1) `bool` | mHurtOwner
3124 | (4) `int` | mMustSeeForgetTicks
3128 | (24) `std::vector<ItemDescriptor>` | mItemList
3152 | (1) `bool` | mCanTemptVertically
3153 | (1) `bool` | mCanTemptWhileRidden
3160 | (32) `std::string` | mTemptSound
3192 | (4) `int` | mMaxToEat
3196 | (4) `int` | mEatDelay
3200 | (4) `int` | mFullDelay
3204 | (4) `int` | mInitialEatDelay
3208 | (24) `std::vector<BlockDescriptor>` | mBlockDescriptors
3232 | (4) `float` | mFloatHeightOffset
3236 | (1) `bool` | mRandomReselect
3240 | (8) `FloatRange` | mFloatDuration
3248 | (8) `IntRange` | mHoverHeight
3256 | (4) `float` | mDuration
3260 | (8) `FloatRange` | mRadiusRange
3268 | (4) `int` | mRadiusChangeChance
3272 | (8) `FloatRange` | mAboveTargetRange
3280 | (8) `FloatRange` | mHeightOffsetRange
3288 | (4) `int` | mHeightChangeChance
3296 | (24) `std::vector<SummonSpellData>` | mSummonSpellData
3320 | (4) `POIType` | mPOIType
3324 | (4) `int` | mGoalCooldown
3328 | (4) `int` | mActiveTime
3332 | (4) `int` | mRandomSoundIntervalMin
3336 | (4) `int` | mRandomSoundIntervalMax
3340 | (1) `bool` | mCanWorkInRain
3344 | (4) `int` | mWorkInRainTolerance
3348 | (4) `float` | mFollowDistance
3352 | (4) `float` | mBlockDistance
3360 | (24) `std::vector<SendEventData>` | mSendEventData
3384 | (4) `int` | mStartDelay
3388 | (4) `int` | mMaxFailedAttempts
3392 | (1) `bool` | mAvoidWater
3393 | (1) `bool` | mPreferWater
3394 | (1) `bool` | mTargetNeeded
3396 | (4) `float` | mMountDistance
3400 | (24) `std::vector<DrinkPotionData>` | mDrinkPotionData
3424 | (4) `float` | mDrinkSpeedModifier
3428 | (4) `float` | mDropItemChance
3432 | (32) `std::string` | mLootTable
3464 | (4) `float` | mSnackingCooldown
3468 | (4) `float` | mSnackingCooldownMin
3472 | (4) `float` | mStopSnackingChance
3476 | (4) `float` | mStopChance
3480 | (4) `float` | mStartChance
3484 | (4) `float` | mSittingTimeMin
3488 | (4) `float` | mSittingCooldown
3496 | (32) `std::string` | mSound
3528 | (32) `std::string` | mPrepareSound
3560 | (4) `float` | mPrepareTime
3568 | (32) `std::string` | mAggroSound
3600 | (320) `DefinitionTrigger` | mOnDefendEvent
3920 | (4) `float` | mSleepYOffset
3924 | (4) `float` | mSleepColliderHeight
3928 | (4) `float` | mSleepColliderWidth
3932 | (4) `float` | mCooldownMax
3936 | (4) `float` | mCooldownMin
3940 | (4) `float` | mDetectMobDistance
3944 | (4) `float` | mDetectMobHeight
3952 | (64) `ActorFilterGroup` | mCanNapFilters
4016 | (64) `ActorFilterGroup` | mWakeMobExceptionFilters
4080 | (4) `float` | mInterestTime
4084 | (4) `float` | mRemoveItemTime
4088 | (4) `float` | mCarriedItemSwitchTime
4092 | (4) `float` | mInterestCooldown
4096 | (4) `float` | mCooldownTimeoutTime
4104 | (176) `ActorDefinitionIdentifier` | mDesiredMingleType
4280 | (4) `float` | mMingleDistance
4284 | (4) `int` | mMinLookCount
4288 | (4) `int` | mMaxLookCount
4292 | (8) `FloatRange` | mSoundInterval
4300 | (8) `FloatRange` | mJumpInterval
4312 | (320) `DefinitionTrigger` | mOnCelebrationEndEvent
4632 | (32) `std::string` | mCelebrationSound
4664 | (1) `bool` | mPickupBasedOnChance
4665 | (1) `bool` | mCanPickupAnyItem
4668 | (4) `int` | mTimeoutAfterBeingAttacked
4672 | (1) `bool` | mCanPickupToHandOrEquipment
4673 | (1) `bool` | mSlimeSetPersistent
4680 | (32) `std::string` | mAdmireItemSound
4712 | (320) `DefinitionTrigger` | mOnAdmireItemStart
5032 | (320) `DefinitionTrigger` | mOnAdmireItemStop
5352 | (4) `float` | mLiquidYOffset
5356 | (4) `float` | mRiseDelta
5360 | (4) `float` | mSinkDelta
5364 | (4) `int` | mStayAvoidTime
5368 | (4) `float` | mAvoidAngle
5372 | (4) `float` | mAvoidMinDis
5376 | (4) `float` | mAvoidMaxDis
5380 | (4) `float` | mAvoidBackAngle
5384 | (4) `float` | mAvoidBackMinDis
5388 | (4) `float` | mAvoidBackMaxDis


### `GoalDefinition::<unnamed_type_mMoveToBlockGoalData>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | speedModifier
4 | (4) `int` | searchRange
8 | (4) `int` | searchHeight
12 | (4) `float` | goalRadius
16 | (4) `int` | tickInterval
20 | (4) `float` | stayDuration
24 | (24) `std::vector<DefinitionTrigger>` | onReachTriggers
48 | (24) `std::vector<DefinitionTrigger>` | onStayCompletedTriggers
72 | (24) `std::vector<ItemDescriptor>` | targetDescriptors
96 | (12) `Vec3` | targetPositionOffset
108 | (4) `float` | chanceToStart
112 | (1) `TargetSelectionMethod` | targetSelectionMethod


### `GroupSizeComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCount
8 | (8) `Tick` | mNextTick


### `GridArea<std::shared_ptr<LevelChunk> >::Definition`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | chunkSide
4 | (2) `__int16` | minHeight
6 | (2) `__int16` | maxHeight
8 | (1) `bool` | circle
16 | (64) `std::function<void __cdecl(buffer_span<Pos>,buffer_span_mut<std::shared_ptr<LevelChunk> >)>` | generate
80 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<LevelChunk> >)>` | destroy
144 | (64) `std::function<void __cdecl(buffer_span_mut<std::shared_ptr<LevelChunk> >,buffer_span<unsigned int>)>` | add


### `GameRulesChangedPacketData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GameRule>` | mRules


### `GameControllerInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GameControllerButtonBinding>` | buttonBindings
24 | (24) `std::vector<GameControllerStickBinding>` | stickBindings
48 | (24) `std::vector<GameControllerTriggerBinding>` | triggerBindings
72 | (24) `std::vector<GameControllerStickToButtonBinding>` | stickToButtonBindings
96 | (4) `int` | turnStickId


### `GGVInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GGVectorBinding>` | gazeBindings
24 | (24) `std::vector<GGVectorBinding>` | handBindings
48 | (24) `std::vector<GGVEventBinding>` | eventBindings
72 | (24) `std::vector<DeviceButtonMapping>` | voiceBindings


### `GlowStoneFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `GameController::EventQueue`
Offset | Type | Name
-|-|-|-
0 | (8) `const void *` | mToken
8 | (40) `std::queue<GameControllerEvent>` | mEvents


### `GameControllerMapper::ButtonAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | nameId
4 | (4) `float` | repeatInterval


### `GameControllerButtonEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | id
4 | (4) `GameControllerButtonState` | state
8 | (1) `bool` | allowRemapping


### `GameControllerMapper::GameControllerMappingData`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_multimap<int,GameControllerMapper::ButtonAttributes>` | mGamePadButtonToButtonIdMap
64 | (64) `std::unordered_multimap<int,GameControllerMapper::TriggerState>` | mTriggerToButtonIdMap
128 | (64) `std::unordered_multimap<int,GameControllerMapper::DirectionAttributes>` | mStickToDirectionIdMap
192 | (64) `std::unordered_multimap<int,unsigned int>` | mStickToButtonIdMap
256 | (16) `std::set<unsigned int>` | mExclusiveButtonIdSet


### `g72x_state`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | yl
4 | (2) `__int16` | yu
6 | (2) `__int16` | dms
8 | (2) `__int16` | dml
10 | (2) `__int16` | ap
12 | (4) `__int16[2]` | a
16 | (12) `__int16[6]` | b
28 | (4) `__int16[2]` | pk
32 | (12) `__int16[6]` | dq
44 | (4) `__int16[2]` | sr
48 | (1) `char` | td


### `gray_TWorker_`
Offset | Type | Name
-|-|-|-
0 | (256) `_SETJMP_FLOAT128[16]` | jump_buffer
256 | (4) `int` | ex
260 | (4) `int` | ey
264 | (4) `int` | min_ex
268 | (4) `int` | max_ex
272 | (4) `int` | min_ey
276 | (4) `int` | max_ey
280 | (4) `int` | area
284 | (4) `int` | cover
288 | (4) `int` | invalid
296 | (8) `TCell_ **` | ycells
304 | (8) `TCell_ *` | cells
312 | (8) `__int64` | max_cells
320 | (8) `__int64` | num_cells
328 | (4) `int` | x
332 | (4) `int` | y
336 | (40) `FT_Outline_` | outline
376 | (16) `TPixmap_` | target
392 | (8) `void (__fastcall *)(int, int, const FT_Span_ *, void *)` | render_span
400 | (8) `void *` | render_span_data
408 | (60) `FT_Span_[10]` | spans
468 | (4) `int` | num_spans


### `glm::detail::storage<int,16,0>::type`
```
struct glm::detail::storage<int,16,0>::type
{
  unsigned __int8 data[16];
};

```

### `glm::tvec4<int,0>`
```
struct __cppobj glm::tvec4<int,0>
{
  $5C9DD8C7A55B613E9335A3B59CB499EC ___u0;
};

```

### `Geometry::Box`
```
struct __cppobj __declspec(align(4)) Geometry::Box
{
  bool mMirror;
  Vec3 mFrom;
  Vec3 mSize;
  Vec3 mRotation;
  Vec3 mPivot;
  TextureOffset mTex;
  std::array<Cube::FaceUVData,6> mFaceUVs;
  float mInflate;
  bool mUsesFaceUVs;
};

```

### `Geometry::NodeTextureMesh`
```
struct __cppobj Geometry::NodeTextureMesh
{
  std::string mTextureName;
  Vec3 mPosition;
  Vec3 mLocalPivot;
  Vec3 mRotation;
  Vec3 mScale;
};

```

### `Geometry::Node`
```
struct __cppobj Geometry::Node
{
  std::set<std::string> mMixedCaseNames;
  bool mMirror;
  bool mNeverRender;
  Vec3 mPivot;
  Vec3 mRot;
  Vec3 mScale;
  Vec3 mBindPoseRotation;
  float mInflate;
  bool mPivotSubtractsParentPivot;
  std::vector<Geometry::Box> mBoxes;
  std::string mParentName;
  std::vector<ModelPartLocator> mLocators;
  Geometry::NodePolyMesh mMesh;
  std::vector<Geometry::NodeTextureMesh> mTextureMeshes;
  bool mDebug;
  unsigned int mSkinnedMeshGroupIdentifier;
  SemVersion mSourcePackVersion;
};

```

### `Geometry`
```
struct __cppobj Geometry
{
  SkinAdjustments mSkinAdjustments;
  Vec2 mRenderDim;
  Vec3 mRenderDimOffset;
  Vec3 mLeashOffset;
  Vec3 mScale;
  bool mUseModelData;
  bool mModified;
  Vec2 mTextureDimensions;
  std::string mSourceFilePathWithExtension;
  std::string mSerializableName;
  std::map<std::string,Geometry::Node> mNodes;
  bool mIsFromBaseGamePack;
  std::vector<std::string> mMaterialInstanceList;
};

```

### `GeometryInfo`
```
struct __cppobj GeometryInfo
{
  HashedString mName;
  std::unique_ptr<Geometry> mPtr;
};

```

### `GameSpecificNetEventCallback`
```
struct __cppobj GameSpecificNetEventCallback
{
  GameSpecificNetEventCallback_vtbl *__vftable /*VFT*/;
};

```

### `GameSpecificNetEventCallback_vtbl`
```
struct /*VFT*/ GameSpecificNetEventCallback_vtbl
{
  void (__fastcall *~GameSpecificNetEventCallback)(GameSpecificNetEventCallback *this);
  void (__fastcall *handle)(GameSpecificNetEventCallback *this, const NetworkIdentifier *, const ResourcePackClientResponsePacket *);
};

```

### `GameRule::ValidationError`
```
struct __cppobj GameRule::ValidationError
{
  bool mSuccess;
  std::string mErrorDescription;
  std::vector<std::string> mErrorParameters;
};

```

### `GameRulesChangedPacket`
```
const struct __cppobj GameRulesChangedPacket : Packet
{
  GameRulesChangedPacketData mRuleData;
};

```

### `GameRulesChangedPacket_vtbl`
```
struct /*VFT*/ GameRulesChangedPacket_vtbl
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

### `GuiDataPickItemPacket`
```
const struct __cppobj __declspec(align(8)) GuiDataPickItemPacket : Packet
{
  std::string mItemName;
  std::string mItemEffectName;
  int mSlot;
};

```

### `GuiDataPickItemPacket_vtbl`
```
struct /*VFT*/ GuiDataPickItemPacket_vtbl
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

### `GamePadRemappingLayout`
```
struct __cppobj __declspec(align(8)) GamePadRemappingLayout : RemappingLayout
{
  VRControllerType mVRControllerType;
  gsl::basic_string_span<char const ,-1> mControllerIconPath;
  bool mGamepadButtonsXYAreSwapped;
  bool mGamepadButtonsABAreSwapped;
};

```

### `GamePadRemappingLayout_vtbl`
```
struct /*VFT*/ GamePadRemappingLayout_vtbl
{
  void (__fastcall *~RemappingLayout)(RemappingLayout *this);
  void (__fastcall *setMappingWithRawInput)(RemappingLayout *this, const std::string *, int, RawInputType);
  int (__fastcall *getAdjustedKey)(RemappingLayout *this, int);
  std::string *(__fastcall *getSaveString)(RemappingLayout *this, std::string *result, const std::string *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int, bool);
  std::string *(__fastcall *getMappedKeyName)(RemappingLayout *this, std::string *result, int);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, const Keymapping *);
  std::string *(__fastcall *getKeySpriteLocation)(RemappingLayout *this, std::string *result, int);
  int (__fastcall *_rawKeyToKey)(RemappingLayout *this, int, RawInputType);
};

```

### `glm::tmat3x4<float,0>`
```
struct __cppobj glm::tmat3x4<float,0>
{
  glm::tvec4<float,0> value[3];
};

```

### `GameCallbacks`
```
struct __cppobj GameCallbacks
{
  GameCallbacks_vtbl *__vftable /*VFT*/;
};

```

### `GameCallbacks_vtbl`
```
struct /*VFT*/ GameCallbacks_vtbl
{
  void (__fastcall *~GameCallbacks)(GameCallbacks *this);
  void (__fastcall *onLevelCorrupt)(GameCallbacks *this);
  void (__fastcall *onGameModeChanged)(GameCallbacks *this);
  void (__fastcall *onBeforeSimTick)(GameCallbacks *this);
  void (__fastcall *onTick)(GameCallbacks *this, int, int);
  void (__fastcall *onInternetUpdate)(GameCallbacks *this);
  void (__fastcall *onGameSessionReset)(GameCallbacks *this);
  void (__fastcall *onLevelExit)(GameCallbacks *this);
  void (__fastcall *updateScreens)(GameCallbacks *this);
};

```

### `GameModuleServer`
```
struct __cppobj GameModuleServer
{
  GameModuleServer_vtbl *__vftable /*VFT*/;
};

```

### `GameModuleServer_vtbl`
```
struct /*VFT*/ GameModuleServer_vtbl
{
  void (__fastcall *~GameModuleServer)(GameModuleServer *this);
  void (__fastcall *init)(GameModuleServer *this, ServerInstance *, Level *);
  void (__fastcall *initializeBehaviorStack)(GameModuleServer *this, const Experiments *, ResourcePackRepository *, ResourcePackStack *, const BaseGameVersion *);
  void (__fastcall *configureLevel)(GameModuleServer *this, Level *, const Experiments *, ResourcePackManager *, const BaseGameVersion *);
  void (__fastcall *configureNewPlayer)(GameModuleServer *this, Player *);
  void (__fastcall *configureDocumentation)(GameModuleServer *this, struct IGameModuleDocumentation *);
  void (__fastcall *tick)(GameModuleServer *this);
  void (__fastcall *setupCommands)(GameModuleServer *this, CommandRegistry *);
  void (__fastcall *configureServerNetworkHandler)(GameModuleServer *this, ServerInstance *, ServerNetworkHandler *);
};

```

### `GameSession`
```
struct __cppobj __declspec(align(8)) GameSession
{
  NetworkHandler *mNetworkHandler;
  std::unique_ptr<Level> mLevel;
  std::unique_ptr<ServerNetworkHandler> mServerNetworkHandler;
  std::unique_ptr<NetEventCallback> mLegacyClientNetworkHandler;
  std::unique_ptr<NetEventCallback> mClientNetworkHandler;
  LoopbackPacketSender *mLoopbackPacketSender;
  unsigned __int8 mClientSubId;
};

```

### `GenericEntitlementChangeListener`
```
struct __cppobj GenericEntitlementChangeListener : EntitlementChangeListener
{
  std::function<void __cdecl(void)> mEntitlementChangedCallback;
};

```

### `GenericEntitlementChangeListener_vtbl`
```
struct /*VFT*/ GenericEntitlementChangeListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `GeometryGroup`
```
struct __cppobj GeometryGroup
{
  std::unordered_map<HashedString,std::shared_ptr<GeometryInfo>> mGeometries;
  std::mutex mGeometryLock;
};

```

### `GameSaveSystem`
```
struct __cppobj __declspec(align(8)) GameSaveSystem
{
  std::vector<std::shared_ptr<SaveContainer>> mSaveContainers;
  std::shared_ptr<Core::RemoteStorageProvider> mRemoteStorage;
  std::shared_mutex mContainerLock;
  std::atomic<bool> mInitializedSettingsMonitor;
  std::atomic<bool> mInitializedWorldsMonitor;
};

```

### `GuiData`
```
const struct __cppobj GuiData : IConfigListener, AppPlatformListener
{
  ScreenSizeData mScreenSizeData;
  bool mScreenSizeDataValid;
  float mGuiScale;
  float mInvGuiScale;
  bool mIsCurrentlyActive;
  std::set<int> mPostedErrors;
  MenuPointer mMenuPointer;
  __int16 mPointerX;
  __int16 mPointerY;
  bool mHasShowPreexistingMessages;
  bool mToolbarWasRendered;
  int mPrevSelectedSlot;
  ContainerID mPrevSelectedInventoryContainer;
  int mNumSlots;
  int mFlashSlotId;
  long double mFlashSlotStartTime;
  IClientInstance *mClient;
  RectangleArea mToolbarArea;
  RectangleArea mToolbarAreaContainer;
  std::string mLastPopupText;
  std::string mLastPopupSubtitleText;
  std::string mLastJukeboxPopupText;
  std::string mLastJukeboxPopupSubtitleText;
  int mTickCount;
  float mItemNameOverlayTime;
  float mJukeboxNameOverlayTime;
  bool mPopupNoticeDirty;
  bool mJukeboxPopupNoticeDirty;
  std::vector<GuiMessage> mGuiMessages;
  std::vector<std::string> mDevConsoleMessages;
  int mMaxDevConsoleMessages;
  std::vector<std::string> mContentLogMessages;
  std::vector<std::string> mPerfTurtleMessages;
  TitleMessage mTitleMessage;
  unsigned int mServerSettingsId;
  std::string mServerSettings;
  bool mMuteChat;
  float mCurrentDropTicks;
  PlayerInventory::SlotData mCurrentDropSlot;
  PlayerInventory::SlotData mLastSelectedSlot;
  bool mShowProgress;
  std::string mTipMessage;
  float mTipMessageLength;
  mce::Mesh mRcFeedbackOuter;
  mce::Mesh mRcFeedbackInner;
  mce::Mesh mVignette;
  mce::MaterialPtr mInvFillMat;
  mce::MaterialPtr mCursorMat;
  DevConsoleLogger *mDevConsoleLogger;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastTickTime;
  std::map<std::string,std::vector<GuiMessage>> mDelayedMessages;
  std::vector<std::string> mQueuedDevConsoleMessages;
  std::mutex mQueuedDevMessagesMutex;
  int mHotbarRenderAloneBit;
  std::string mFilteredText;
};

```

### `GameRenderer_vtbl`
```
struct /*VFT*/ GameRenderer_vtbl
{
  void (__fastcall *~GameRenderer)(GameRenderer *this);
};

```

### `GuiContentLogEndPoint`
```
struct __cppobj GuiContentLogEndPoint : ContentLogEndPoint
{
  bool mEnabled;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits> mMessages;
};

```

### `GuiContentLogEndPoint_vtbl`
```
struct /*VFT*/ GuiContentLogEndPoint_vtbl
{
  void (__fastcall *~LogEndPoint)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(Bedrock::LogEndPoint *this, const char *);
  void (__fastcall *flush)(Bedrock::LogEndPoint *this);
  void (__fastcall *setEnabled)(Bedrock::LogEndPoint *this, bool);
  bool (__fastcall *isEnabled)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(ContentLogEndPoint *this, const LogArea, const LogLevel, const char *);
};

```

### `GameStore`
```
struct __cppobj GameStore : StoreListenerMultistore, Bedrock::EnableNonOwnerReferences
{
  gsl::not_null<StoreListener *> mStoreListener;
  std::vector<std::shared_ptr<Store>> mStores;
  std::unique_ptr<StoreSynchronizer> mStoreSynchronizer;
  std::unordered_map<std::string,QueryPurchaseResult> mQueryPurchaseResults;
  bool mAvailable;
  GameStore::State mState;
  std::function<void __cdecl(enum QueryResult)> mActiveQueryCallback;
  std::function<void __cdecl(enum PurchaseResult)> mAppPurchaseCallback;
  ServiceRegistrationToken<GameStore> mServiceRegistrationToken;
};

```

### `GameStore_vtbl`
```
struct /*VFT*/ GameStore_vtbl
{
  void (__fastcall *~StoreListener)(StoreListener *this);
  void (__fastcall *onStoreInitialized)(StoreListener *this, bool);
  void (__fastcall *setStoreAvailable)(StoreListener *this, bool);
  void (__fastcall *onQueryProductsSuccess)(StoreListener *this, const std::vector<ProductInfo> *);
  void (__fastcall *onQueryProductsFail)(StoreListener *this);
  void (__fastcall *onPurchaseSuccessful)(StoreListener *this, const PurchaseInfo *);
  void (__fastcall *onPurchaseCanceled)(StoreListener *this, const ProductSku *);
  void (__fastcall *onPurchaseFailed)(StoreListener *this, const ProductSku *);
  void (__fastcall *onQueryPurchasesSuccess)(StoreListener *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFail)(StoreListener *this);
  void (__fastcall *onAppPurchaseSuccess)(StoreListener *this);
  void (__fastcall *onAppPurchaseFailed)(StoreListener *this);
  void (__fastcall *onAppPurchaseCanceled)(StoreListener *this);
  void (__fastcall *onQueryPurchasesSuccessMultistore)(StoreListenerMultistore *this, const std::string *, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFailMultistore)(StoreListenerMultistore *this, const std::string *);
};

```

### `GameControllerButtonBinding`
```
struct __cppobj __declspec(align(8)) GameControllerButtonBinding
{
  std::string buttonName;
  int buttonNum;
  float repeatInterval;
  bool exclusive;
};

```

### `GameControllerStickBinding`
```
struct __cppobj __declspec(align(4)) GameControllerStickBinding
{
  DirectionId directionId;
  int stickId;
  bool invertX;
  bool invertY;
};

```

### `GameControllerTriggerBinding`
```
struct __cppobj GameControllerTriggerBinding
{
  std::string buttonName;
  int triggerId;
  float triggerThreshold;
};

```

### `GameControllerStickToButtonBinding`
```
struct __cppobj __declspec(align(8)) GameControllerStickToButtonBinding
{
  DirectionId directionId;
  int stickId;
  std::string buttonName;
  bool exclusive;
};

```

### `GGVectorBinding`
```
struct __cppobj __declspec(align(8)) GGVectorBinding
{
  std::string mName;
  __int16 mId;
};

```

### `GGVEventBinding`
```
struct __cppobj __declspec(align(8)) GGVEventBinding
{
  std::string mName;
  __int16 mId;
};

```

### `GuidedFlow`
```
struct __cppobj GuidedFlow
{
  GuidedFlow_vtbl *__vftable /*VFT*/;
};

```

### `GuidedFlow_vtbl`
```
struct /*VFT*/ GuidedFlow_vtbl
{
  void (__fastcall *~GuidedFlow)(GuidedFlow *this);
  void (__fastcall *initialize)(GuidedFlow *this, const IGuidedFlowClient *);
  void (__fastcall *finish)(GuidedFlow *this, const IGuidedFlowClient *, const bool);
};

```

### `GuidedFlowManager`
```
struct __cppobj GuidedFlowManager
{
  std::unique_ptr<IGuidedFlowClient> mGuidedFlowClient;
  std::unique_ptr<GuidedFlow> mActiveFlow;
};

```

### `GameModuleClient`
```
struct __cppobj GameModuleClient
{
  GameModuleClient_vtbl *__vftable /*VFT*/;
};

```

### `GameModuleClient_vtbl`
```
struct /*VFT*/ GameModuleClient_vtbl
{
  void (__fastcall *~GameModuleClient)(GameModuleClient *this);
  void (__fastcall *init)(GameModuleClient *this, IClientInstance *, Level *);
  void (__fastcall *configureLevel)(GameModuleClient *this, IClientInstance *, Level *, const Experiments *, const BaseGameVersion *);
  void (__fastcall *initializeResourceStack)(GameModuleClient *this, const Experiments *, ResourcePackRepository *, ResourcePackStack *, const BaseGameVersion *, GameModuleClient::ResourceLoadingPhase);
  void (__fastcall *configureDocumentation)(GameModuleClient *this, struct GameModuleDocumentation *);
  void (__fastcall *tick)(GameModuleClient *this);
  void (__fastcall *setupStandardCommands)(GameModuleClient *this, CommandRegistry *);
  void (__fastcall *setupStartMenuScreenCommands)(GameModuleClient *this, CommandRegistry *);
  void (__fastcall *registerActorRenderers)(GameModuleClient *this, IClientInstance *);
  std::unique_ptr<ClientInputMappingFactory> *(__fastcall *createInputMappingFactory)(GameModuleClient *this, std::unique_ptr<ClientInputMappingFactory> *result, IClientInstance *);
};

```

### `GuiData_vtbl`
```
struct /*VFT*/ GuiData_vtbl
{
  void (__fastcall *~IConfigListener)(IConfigListener *this);
  void (__fastcall *onConfigChanged)(IConfigListener *this, const Config *);
};

```

### `glTFExportData`
```
const struct __cppobj glTFExportData
{
  std::string mModelName;
  Core::PathBuffer<std::string > mFilePath;
  std::string mModelId;
  int mBlockCount;
  int mEntityCount;
  int mPlayerCount;
  AutomaticID<Dimension,int> mDimension;
  int mGameTime;
  unsigned __int64 mFileSize;
  unsigned __int64 mStartTime;
  unsigned __int64 mEndTime;
};

```

### `GameplayHandler`
```
struct __cppobj GameplayHandler
{
  GameplayHandler_vtbl *__vftable /*VFT*/;
};

```

### `GameplayHandler_vtbl`
```
struct /*VFT*/ GameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
};

```

### `GameplayHandlerResult<enum CoordinatorResult>`
```
struct __cppobj GameplayHandlerResult<enum CoordinatorResult>
{
  HandlerResult mHandlerResult;
  _BYTE mReturnValue[4];
};

```

### `GameMode`
```
struct __cppobj __declspec(align(8)) GameMode
{
  GameMode_vtbl *__vftable /*VFT*/;
  Player *mPlayer;
  BlockPos mDestroyBlockPos;
  unsigned __int8 mDestroyBlockFace;
  float mOldDestroyProgress;
  float mDestroyProgress;
  long double mLastDestroyTime;
  float mDistanceTravelled;
  Vec3 mPlayerLastPosition;
  BlockPos mLastBuiltBlockPosition;
  bool mLastBuildBlockWasInteractive;
  bool mLastBuildBlockWasSnappable;
  float mMinPlayerSpeed;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastBuildTime;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNoDestroyUntil;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNoDestroySoundUntil;
  std::chrono::duration<__int64,std::ratio<1,1000> > creativeDestructionTickDelay;
  std::chrono::duration<__int64,std::ratio<1,1000> > buildingTickDelay;
  std::chrono::duration<__int64,std::ratio<1,1000> > destroySoundDelay;
  bool mHasBuildDirection;
  bool mHasLastBuiltPosition;
  unsigned __int8 mContinueFacing;
  BlockPos mBuildDirection;
  BlockPos mNextBuildPos;
  std::unique_ptr<IGameModeTimer> mTimer;
  std::unique_ptr<IGameModeMessenger> mMessenger;
  bool mForbidBreakBlock;
  bool mIsValid;
};

```

### `GameMode_vtbl`
```
struct /*VFT*/ GameMode_vtbl
{
  void (__fastcall *~GameMode)(GameMode *this);
  bool (__fastcall *startDestroyBlock)(GameMode *this, const BlockPos *, unsigned __int8, bool *);
  bool (__fastcall *destroyBlock)(GameMode *this, const BlockPos *, unsigned __int8, bool);
  bool (__fastcall *continueDestroyBlock)(GameMode *this, const BlockPos *, unsigned __int8, const Vec3 *, bool *);
  void (__fastcall *stopDestroyBlock)(GameMode *this, const BlockPos *);
  void (__fastcall *startBuildBlock)(GameMode *this, const BlockPos *, unsigned __int8);
  bool (__fastcall *buildBlock)(GameMode *this, const BlockPos *, unsigned __int8);
  void (__fastcall *continueBuildBlock)(GameMode *this, const BlockPos *, unsigned __int8);
  void (__fastcall *stopBuildBlock)(GameMode *this);
  void (__fastcall *tick)(GameMode *this);
  float (__fastcall *getPickRange)(GameMode *this, const InputMode *, bool);
  bool (__fastcall *useItem)(GameMode *this, ItemStack *);
  bool (__fastcall *useItemOn)(GameMode *this, ItemStack *, const BlockPos *, unsigned __int8, const Vec3 *, const Block *);
  bool (__fastcall *interact)(GameMode *this, Actor *, const Vec3 *);
  bool (__fastcall *attack)(GameMode *this, Actor *);
  void (__fastcall *releaseUsingItem)(GameMode *this);
  void (__fastcall *setTrialMode)(GameMode *this, bool);
  bool (__fastcall *isInTrialMode)(GameMode *this);
  void (__fastcall *registerUpsellScreenCallback)(GameMode *this, std::function<void __cdecl(bool)>);
};

```

### `GenericMoveControlDescription`
```
struct __cppobj GenericMoveControlDescription : MoveControlDescription
{
};

```

### `GenericMoveControlDescription_vtbl`
```
struct /*VFT*/ GenericMoveControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `GlideMoveControlDescription`
```
struct __cppobj GlideMoveControlDescription : MoveControlDescription
{
  float mStartSpeed;
  float mSpeedWhenTurning;
};

```

### `GlideMoveControlDescription_vtbl`
```
struct /*VFT*/ GlideMoveControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `glm::tmat4x3<float,0>`
```
struct __cppobj glm::tmat4x3<float,0>
{
  glm::tvec3<float,0> value[4];
};

```

### `glm::tmat4x2<float,0>`
```
struct __cppobj glm::tmat4x2<float,0>
{
  glm::tvec2<float,0> value[4];
};

```

### `glm::tmat2x4<float,0>`
```
struct __cppobj glm::tmat2x4<float,0>
{
  glm::tvec4<float,0> value[2];
};

```

### `glm::tmat3x2<float,0>`
```
struct __cppobj glm::tmat3x2<float,0>
{
  glm::tvec2<float,0> value[3];
};

```

### `glm::tmat2x2<float,0>`
```
struct __cppobj glm::tmat2x2<float,0>
{
  glm::tvec2<float,0> value[2];
};

```

### `Goal`
```
struct __cppobj __declspec(align(8)) Goal
{
  Goal_vtbl *__vftable /*VFT*/;
  int mRequiredControlFlags;
  std::string mName;
  unsigned __int16 mTypeId;
};

```

### `Goal_vtbl`
```
struct /*VFT*/ Goal_vtbl
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

### `GameMode::BuildDelay`
```
struct __cppobj GameMode::BuildDelay
{
  bool mHasDelayElapsed;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNewLastBuildTimeIfBlockIsBuilt;
};

```

### `glm::detail::compute_transpose<glm::tmat3x3,float,0,0>`
```
struct __cppobj glm::detail::compute_transpose<glm::tmat3x3,float,0,0>
{
};

```

### `glm::detail::compute_transpose<glm::tmat4x4,float,0,0>`
```
struct __cppobj glm::detail::compute_transpose<glm::tmat4x4,float,0,0>
{
};

```

### `glm::detail::compute_inverse<glm::tmat4x4,float,0,0>`
```
struct __cppobj glm::detail::compute_inverse<glm::tmat4x4,float,0,0>
{
};

```

### `glm::detail::compute_normalize<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_normalize<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::compute_vec4_add<float,0,0>`
```
struct __cppobj glm::detail::compute_vec4_add<float,0,0>
{
};

```

### `glm::detail::compute_dot<glm::tvec3,float,0,0>`
```
struct __cppobj glm::detail::compute_dot<glm::tvec3,float,0,0>
{
};

```

### `glm::detail::compute_vec4_sub<float,0,0>`
```
struct __cppobj glm::detail::compute_vec4_sub<float,0,0>
{
};

```

### `GiftContent`
```
struct __cppobj __declspec(align(8)) GiftContent
{
  const std::string mDate;
  std::string mProductId;
  bool mIsWorld;
};

```

### `GiftPromotionCustom`
```
struct __cppobj GiftPromotionCustom
{
  std::string mTitleLocId;
  std::string mDescriptionLocId;
  std::string mClaimedTagLocId;
  std::string mUnclaimedTagLocId;
  std::vector<GiftContent> mPromotionItems;
};

```

### `GiftPromotionDocument`
```
struct __cppobj GiftPromotionDocument
{
  CommonDocument mCommon;
  GiftPromotionCustom mCustom;
};

```

### `GiftPromotionSearchResults`
```
const struct __cppobj GiftPromotionSearchResults : CommonSearchResults
{
  std::vector<GiftPromotionDocument> mDocuments;
};

```

### `GiftPromotionQuery`
```
struct __cppobj GiftPromotionQuery : TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>
{
  std::function<void __cdecl(GiftPromotionCustom const &)> mOnQueryFinishedCallbeck;
};

```

### `GiftPromotionQuery_vtbl`
```
struct /*VFT*/ GiftPromotionQuery_vtbl
{
  void (__fastcall *~TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this, const GiftPromotionSearchResults *, const std::vector<std::string> *);
};

```

### `GfxDriverOutdatedScreenController`
```
struct __cppobj GfxDriverOutdatedScreenController : MainMenuScreenController
{
};

```

### `GfxDriverOutdatedScreenController_vtbl`
```
struct /*VFT*/ GfxDriverOutdatedScreenController_vtbl
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

### `GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_7459143b64c93dea16b8bc843e7d6a8c>`
```
struct __cppobj GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_7459143b64c93dea16b8bc843e7d6a8c>
{
  GfxDriverOutdatedScreenController *const __this;
};

```

### `GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_97acee73db78e80356f16dbdfb8474db>`
```
struct __cppobj GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_97acee73db78e80356f16dbdfb8474db>
{
  GfxDriverOutdatedScreenController *const __this;
};

```

### `GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_39a5f6a9600c074559a9b9e4ebc02071>`
```
struct __cppobj GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_39a5f6a9600c074559a9b9e4ebc02071>
{
  GfxDriverOutdatedScreenController *const __this;
};

```

### `GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_85cb2de37bd3efb7746f9136bd08ef83>`
```
struct __cppobj GfxDriverOutdatedScreenController::_registerEventHandlers::__l2::<lambda_85cb2de37bd3efb7746f9136bd08ef83>
{
};

```

### `glTF::Image`
```
struct __cppobj __declspec(align(8)) glTF::Image
{
  std::string uri;
  glTF::ObjectID bufferView;
  glTF::Image::ImageMimeType mimeType;
  std::string name;
  int id;
};

```

### `glTFExporter`
```
struct __cppobj glTFExporter
{
  glTFExporter_vtbl *__vftable /*VFT*/;
  const Core::PathBuffer<std::string > mFolderPath;
  const std::string mModelName;
  Core::PathBuffer<std::string > mBinaryPath;
  std::string mBinaryFileName;
  Core::PathBuffer<std::string > mglTFPath;
  const bool mUseBinary;
  std::vector<glTF::Accessor> mAccessors;
  std::vector<glTF::Animation> mAnimations;
  glTF::Asset mAsset;
  std::vector<glTF::Buffer> mBuffers;
  std::vector<glTF::BufferView> mBufferViewers;
  std::vector<glTF::Image> mImages;
  std::vector<glTF::Material> mMaterials;
  std::vector<glTF::Mesh> mMeshes;
  std::vector<glTF::Node> mNodes;
  std::vector<glTF::Sampler> mSamplers;
  std::vector<glTF::Scene> mScenes;
  std::vector<glTF::Shader> mShaders;
  std::vector<glTF::Texture> mTextures;
  std::vector<std::string> mExtensions;
  int mDefaultSceneName;
  std::vector<unsigned char> mBinaryBuffer;
  std::mutex mMutex;
};

```

### `glTFExporter_vtbl`
```
struct /*VFT*/ glTFExporter_vtbl
{
  void (__fastcall *~glTFExporter)(glTFExporter *this);
};

```

### `glTF::Animation`
```
struct __cppobj glTF::Animation
{
};

```

### `glTF::Asset::Profile`
```
struct __cppobj glTF::Asset::Profile
{
  std::string api;
  std::string version;
};

```

### `glTF::Asset`
```
struct __cppobj glTF::Asset
{
  std::string copyright;
  std::string generator;
  glTF::Asset::Profile profile;
  std::string version;
};

```

### `glTF::Buffer`
```
struct __cppobj __declspec(align(8)) glTF::Buffer
{
  std::string uri;
  int byteLength;
  std::string name;
  int id;
};

```

### `glTF::Mesh`
```
struct __cppobj glTF::Mesh
{
  std::vector<glTF::Mesh::Primitive> primitives;
  std::string name;
  int id;
  Json::Value extras;
};

```

### `glTF::OptionalField<enum glTF::Sampler::MagFilter>`
```
struct __cppobj glTF::OptionalField<enum glTF::Sampler::MagFilter>
{
  bool mValid;
  glTF::Sampler::MagFilter mValue;
};

```

### `glTF::OptionalField<enum glTF::Sampler::MinFilter>`
```
struct __cppobj glTF::OptionalField<enum glTF::Sampler::MinFilter>
{
  bool mValid;
  glTF::Sampler::MinFilter mValue;
};

```

### `glTF::OptionalField<enum glTF::Sampler::WrapS>`
```
struct __cppobj glTF::OptionalField<enum glTF::Sampler::WrapS>
{
  bool mValid;
  glTF::Sampler::WrapS mValue;
};

```

### `glTF::OptionalField<enum glTF::Sampler::WrapT>`
```
struct __cppobj glTF::OptionalField<enum glTF::Sampler::WrapT>
{
  bool mValid;
  glTF::Sampler::WrapT mValue;
};

```

### `glTF::Sampler`
```
struct __cppobj __declspec(align(8)) glTF::Sampler
{
  glTF::OptionalField<enum glTF::Sampler::MagFilter> magFilter;
  glTF::OptionalField<enum glTF::Sampler::MinFilter> minFilter;
  glTF::OptionalField<enum glTF::Sampler::WrapS> wrapS;
  glTF::OptionalField<enum glTF::Sampler::WrapT> wrapT;
  std::string name;
  int id;
};

```

### `glTF::Scene`
```
struct __cppobj __declspec(align(8)) glTF::Scene
{
  std::vector<int> nodes;
  std::string name;
  int id;
};

```

### `glTF::Shader`
```
struct __cppobj __declspec(align(8)) glTF::Shader
{
  std::string uri;
  glTF::Shader::Type type;
  std::string name;
  int id;
};

```

### `glm::detail::compute_length2<glm::tvec2,float,0,0>`
```
struct __cppobj glm::detail::compute_length2<glm::tvec2,float,0,0>
{
};

```

### `glm::detail::compute_dot<glm::tvec2,float,0,0>`
```
struct __cppobj glm::detail::compute_dot<glm::tvec2,float,0,0>
{
};

```

### `GeometryInheritanceTree::GeometryInheritanceTreeNode`
```
struct __cppobj __declspec(align(8)) GeometryInheritanceTree::GeometryInheritanceTreeNode
{
  std::string mName;
  std::string mFileName;
  ModelParent mModelParent;
  std::vector<GeometryInheritanceTree::GeometryInheritanceTreeNode *> mChildren;
  bool mIsVisited;
};

```

### `GeometryInheritanceTree`
```
struct __cppobj GeometryInheritanceTree
{
  std::vector<std::unique_ptr<Json::Value>> mLoadedJsonFiles;
  std::unordered_map<std::string,GeometryInheritanceTree::GeometryInheritanceTreeNode> mNodes;
  std::mutex mNodeLock;
};

```

### `group_req`
```
struct group_req
{
  unsigned int gr_interface;
  sockaddr_storage gr_group;
};

```

### `group_filter`
```
struct group_filter
{
  unsigned int gf_interface;
  sockaddr_storage gf_group;
  MULTICAST_MODE_TYPE gf_fmode;
  unsigned int gf_numsrc;
  sockaddr_storage gf_slist[1];
};

```

### `group_source_req`
```
struct group_source_req
{
  unsigned int gsr_interface;
  sockaddr_storage gsr_group;
  sockaddr_storage gsr_source;
};

```

### `glm::tvec4<float,4>`
```
struct __cppobj glm::tvec4<float,4>
{
  $9B4DEC3AF9AA78A5D0E586067CDFEB5A ___u0;
};

```

### `glm::tvec2<short,0>`
```
struct __cppobj glm::tvec2<short,0>
{
  $91C137FE90E3E5D2019C7CF6A11827B7 ___u0;
  $871014CD32273E432CA9C2A1A600BD33 ___u1;
};

```

### `glm::tvec3<float,3>`
```
struct __cppobj glm::tvec3<float,3>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
  $9B996AAE057415E4B0A10C768262D912 ___u2;
};

```

### `glm::tvec4<float,3>`
```
struct __cppobj glm::tvec4<float,3>
{
  $9B4DEC3AF9AA78A5D0E586067CDFEB5A ___u0;
};

```

### `glm::tmat4x3<float,3>`
```
struct __cppobj glm::tmat4x3<float,3>
{
  glm::tvec3<float,3> value[4];
};

```

### `glm::tmat3x4<float,3>`
```
struct __cppobj glm::tmat3x4<float,3>
{
  glm::tvec4<float,3> value[3];
};

```

### `glm::tvec2<float,3>`
```
struct __cppobj glm::tvec2<float,3>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
};

```

### `glm::tmat4x2<float,3>`
```
struct __cppobj glm::tmat4x2<float,3>
{
  glm::tvec2<float,3> value[4];
};

```

### `glm::tmat2x4<float,3>`
```
struct __cppobj glm::tmat2x4<float,3>
{
  glm::tvec4<float,3> value[2];
};

```

### `glm::tmat3x2<float,3>`
```
struct __cppobj glm::tmat3x2<float,3>
{
  glm::tvec2<float,3> value[3];
};

```

### `glm::tmat2x3<float,3>`
```
struct __cppobj glm::tmat2x3<float,3>
{
  glm::tvec3<float,3> value[2];
};

```

### `glm::tmat4x4<float,3>`
```
struct __cppobj glm::tmat4x4<float,3>
{
  glm::tvec4<float,3> value[4];
};

```

### `glm::tmat3x3<float,3>`
```
struct __cppobj glm::tmat3x3<float,3>
{
  glm::tvec3<float,3> value[3];
};

```

### `glm::tmat2x2<float,3>`
```
struct __cppobj glm::tmat2x2<float,3>
{
  glm::tvec2<float,3> value[2];
};

```

### `glm::tvec1<float,0>`
```
struct __cppobj glm::tvec1<float,0>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
};

```

### `glm::tvec1<bool,0>`
```
struct __cppobj glm::tvec1<bool,0>
{
  $9FD72FC5497EA808217EA08221ECF2CA ___u0;
};

```

### `glm::detail::storage<unsigned int,16,0>::type`
```
struct glm::detail::storage<unsigned int,16,0>::type
{
  unsigned __int8 data[16];
};

```

### `glm::tvec4<unsigned int,0>`
```
struct __cppobj glm::tvec4<unsigned int,0>
{
  $099087880415C29A502EDEB2867EFA28 ___u0;
};

```

### `glm::tvec3<float,5>`
```
struct __cppobj glm::tvec3<float,5>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
  $9B996AAE057415E4B0A10C768262D912 ___u2;
};

```

### `glm::tvec2<signed char,0>`
```
struct __cppobj glm::tvec2<signed char,0>
{
  $08E0FA21F97AC5F5C1A884CF1AF3FA58 ___u0;
  $90E4983844D83F6959ADF0268FDB62DC ___u1;
};

```

### `glm::tvec3<unsigned int,0>`
```
struct __cppobj glm::tvec3<unsigned int,0>
{
  $A6A78DDC903BEAF524B7DB4CBBB586E3 ___u0;
  $CBCDD465F132EF09A2AEEB3FEE02687F ___u1;
  $1E2D8DAC2884DD21736CADE6D06F6255 ___u2;
};

```

### `glm::tvec2<float,4>`
```
struct __cppobj glm::tvec2<float,4>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
};

```

### `glm::tmat2x4<float,4>`
```
struct __cppobj glm::tmat2x4<float,4>
{
  glm::tvec4<float,4> value[2];
};

```

### `glm::tmat4x2<float,4>`
```
struct __cppobj glm::tmat4x2<float,4>
{
  glm::tvec2<float,4> value[4];
};

```

### `glm::tvec3<float,4>`
```
struct __cppobj glm::tvec3<float,4>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
  $9B996AAE057415E4B0A10C768262D912 ___u2;
};

```

### `glm::tmat4x3<float,4>`
```
struct __cppobj glm::tmat4x3<float,4>
{
  glm::tvec3<float,4> value[4];
};

```

### `glm::tmat3x4<float,4>`
```
struct __cppobj glm::tmat3x4<float,4>
{
  glm::tvec4<float,4> value[3];
};

```

### `glm::tmat3x2<float,4>`
```
struct __cppobj glm::tmat3x2<float,4>
{
  glm::tvec2<float,4> value[3];
};

```

### `glm::tmat2x3<float,4>`
```
struct __cppobj glm::tmat2x3<float,4>
{
  glm::tvec3<float,4> value[2];
};

```

### `glm::tmat4x4<float,4>`
```
struct __cppobj glm::tmat4x4<float,4>
{
  glm::tvec4<float,4> value[4];
};

```

### `glm::tmat3x3<float,4>`
```
struct __cppobj glm::tmat3x3<float,4>
{
  glm::tvec3<float,4> value[3];
};

```

### `glm::tmat2x2<float,4>`
```
struct __cppobj glm::tmat2x2<float,4>
{
  glm::tvec2<float,4> value[2];
};

```

### `glm::tvec3<unsigned short,0>`
```
struct __cppobj glm::tvec3<unsigned short,0>
{
  $AA0D9C0E645A4C46932A70C129AAE1AB ___u0;
  $2042176E05E2A5B53562E58BCDFC4679 ___u1;
  $3B07C86FEE358F4F2293089AECEB34AB ___u2;
};

```

### `glm::detail::storage<double,32,0>::type`
```
struct glm::detail::storage<double,32,0>::type
{
  unsigned __int8 data[32];
};

```

### `glm::tquat<double,0>`
```
struct __cppobj glm::tquat<double,0>
{
  $75DC5B15D19BD64461E8D520BD808E2A ___u0;
};

```

### `glm::tvec1<unsigned char,0>`
```
struct __cppobj glm::tvec1<unsigned char,0>
{
  $21A5844E448AC676884A35851BC8122F ___u0;
};

```

### `glm::detail::storage<signed char,4,0>::type`
```
struct glm::detail::storage<signed char,4,0>::type
{
  unsigned __int8 data[4];
};

```

### `glm::tvec4<signed char,0>`
```
struct __cppobj glm::tvec4<signed char,0>
{
  $46240A595F19ECB2AC189384A1090A05 ___u0;
};

```

### `glm::detail::storage<short,8,0>::type`
```
struct glm::detail::storage<short,8,0>::type
{
  unsigned __int8 data[8];
};

```

### `glm::tvec4<short,0>`
```
struct __cppobj glm::tvec4<short,0>
{
  $88B40697B5D1C5A987E0B5D14B4EBA6D ___u0;
};

```

### `glm::tvec2<float,5>`
```
struct __cppobj glm::tvec2<float,5>
{
  $D6EC15B927D7F6093279F9000A61AE1B ___u0;
  $FCA921BEFA95D44D60D784C4D8D7ED2C ___u1;
};

```

### `glm::tvec4<float,5>`
```
struct __cppobj glm::tvec4<float,5>
{
  $9B4DEC3AF9AA78A5D0E586067CDFEB5A ___u0;
};

```

### `glm::detail::storage<unsigned short,8,0>::type`
```
struct glm::detail::storage<unsigned short,8,0>::type
{
  unsigned __int8 data[8];
};

```

### `glm::tvec4<unsigned short,0>`
```
struct __cppobj glm::tvec4<unsigned short,0>
{
  $FD01C1611073296247BAA62CF14FDD49 ___u0;
};

```

### `glm::tvec4<double,0>`
```
struct __cppobj glm::tvec4<double,0>
{
  $4E9901F10420A74D8A51DC7B675D6A60 ___u0;
};

```

### `glm::tmat2x3<float,5>`
```
struct __cppobj glm::tmat2x3<float,5>
{
  glm::tvec3<float,5> value[2];
};

```

### `glm::tmat3x2<float,5>`
```
struct __cppobj glm::tmat3x2<float,5>
{
  glm::tvec2<float,5> value[3];
};

```

### `glm::tmat4x3<float,5>`
```
struct __cppobj glm::tmat4x3<float,5>
{
  glm::tvec3<float,5> value[4];
};

```

### `glm::tmat4x2<float,5>`
```
struct __cppobj glm::tmat4x2<float,5>
{
  glm::tvec2<float,5> value[4];
};

```

### `glm::tmat3x4<float,5>`
```
struct __cppobj glm::tmat3x4<float,5>
{
  glm::tvec4<float,5> value[3];
};

```

### `glm::tmat2x4<float,5>`
```
struct __cppobj glm::tmat2x4<float,5>
{
  glm::tvec4<float,5> value[2];
};

```

### `glm::tmat4x4<float,5>`
```
struct __cppobj glm::tmat4x4<float,5>
{
  glm::tvec4<float,5> value[4];
};

```

### `glm::tmat3x3<float,5>`
```
struct __cppobj glm::tmat3x3<float,5>
{
  glm::tvec3<float,5> value[3];
};

```

### `glm::tmat2x2<float,5>`
```
struct __cppobj glm::tmat2x2<float,5>
{
  glm::tvec2<float,5> value[2];
};

```

### `glm::tvec1<int,0>`
```
struct __cppobj glm::tvec1<int,0>
{
  $A293B79558BF338540E1F5C0688B11E7 ___u0;
};

```

### `glm::detail::storage<unsigned char,4,0>::type`
```
struct glm::detail::storage<unsigned char,4,0>::type
{
  unsigned __int8 data[4];
};

```

### `glm::tvec4<unsigned char,0>`
```
struct __cppobj glm::tvec4<unsigned char,0>
{
  $CD17CFFAC81082D99E9B5DFB43697074 ___u0;
};

```

### `glm::tvec3<unsigned char,0>`
```
struct __cppobj glm::tvec3<unsigned char,0>
{
  $21A5844E448AC676884A35851BC8122F ___u0;
  $993B9A649076EF0C0DD665A22E342DAF ___u1;
  $0516BA637A8A3D862008DF913B970BCB ___u2;
};

```

### `glm::tvec2<unsigned char,0>`
```
struct __cppobj glm::tvec2<unsigned char,0>
{
  $21A5844E448AC676884A35851BC8122F ___u0;
  $993B9A649076EF0C0DD665A22E342DAF ___u1;
};

```

### `glm::tvec4<int,5>`
```
struct __cppobj glm::tvec4<int,5>
{
  $61ED7D8B19C6F681DF213B698FD2A90B ___u0;
};

```

### `glm::tvec4<int,4>`
```
struct __cppobj glm::tvec4<int,4>
{
  $61ED7D8B19C6F681DF213B698FD2A90B ___u0;
};

```

### `glm::detail::storage<unsigned char,4,0>`
```
struct __cppobj glm::detail::storage<unsigned char,4,0>
{
};

```

### `glm::detail::functor1<float,float,0,glm::tvec4>`
```
struct __cppobj glm::detail::functor1<float,float,0,glm::tvec4>
{
};

```

### `glm::detail::storage<int,16,1>`
```
struct __cppobj glm::detail::storage<int,16,1>
{
};

```

### `glm::detail::storage<int,16,0>`
```
struct __cppobj glm::detail::storage<int,16,0>
{
};

```

### `glm::detail::compute_round<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_round<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::compute_abs<float,1>`
```
struct __cppobj glm::detail::compute_abs<float,1>
{
};

```

### `glm::detail::compute_sqrt<glm::tvec4,float,5,1>`
```
struct __cppobj glm::detail::compute_sqrt<glm::tvec4,float,5,1>
{
};

```

### `glm::detail::compute_max_vector<float,0,glm::tvec4,0>`
```
struct __cppobj glm::detail::compute_max_vector<float,0,glm::tvec4,0>
{
};

```

### `glm::detail::compute_vec4_div<float,5,1>`
```
struct __cppobj glm::detail::compute_vec4_div<float,5,1>
{
};

```

### `glm::detail::compute_floor<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_floor<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::is_int<unsigned __int64>`
```
struct __cppobj glm::detail::is_int<unsigned __int64>
{
};

```

### `glm::detail::functor1<float,float,0,glm::tvec3>`
```
struct __cppobj glm::detail::functor1<float,float,0,glm::tvec3>
{
};

```

### `glm::detail::u4u4u4u4::<unnamed_type_data>`
```
struct glm::detail::u4u4u4u4::<unnamed_type_data>
{
  unsigned __int32 x : 4;
  unsigned __int32 y : 4;
  unsigned __int32 z : 4;
  unsigned __int32 w : 4;
};

```

### `glm::detail::compute_min_vector<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_min_vector<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::compute_round<float,0,glm::tvec4,0>`
```
struct __cppobj glm::detail::compute_round<float,0,glm::tvec4,0>
{
};

```

### `glm::detail::storage<short,8,0>`
```
struct __cppobj glm::detail::storage<short,8,0>
{
};

```

### `glm::detail::compute_ceilMultiple<0,1>`
```
struct __cppobj glm::detail::compute_ceilMultiple<0,1>
{
};

```

### `glm::detail::functor1<float,float,0,glm::tvec1>`
```
struct __cppobj glm::detail::functor1<float,float,0,glm::tvec1>
{
};

```

### `glm::detail::compute_floorMultiple<0,1>`
```
struct __cppobj glm::detail::compute_floorMultiple<0,1>
{
};

```

### `glm::detail::is_int<int>`
```
struct __cppobj glm::detail::is_int<int>
{
};

```

### `glm::detail::is_int<__int64>`
```
struct __cppobj glm::detail::is_int<__int64>
{
};

```

### `glm::detail::is_aligned<4>`
```
struct __cppobj glm::detail::is_aligned<4>
{
};

```

### `glm::detail::storage<unsigned int,16,0>`
```
struct __cppobj glm::detail::storage<unsigned int,16,0>
{
};

```

### `glm::detail::u3u3u2::<unnamed_type_data>`
```
struct glm::detail::u3u3u2::<unnamed_type_data>
{
  unsigned __int32 x : 3;
  unsigned __int32 y : 3;
  unsigned __int32 z : 2;
};

```

### `glm::detail::compute_roundMultiple<1,1>`
```
struct __cppobj glm::detail::compute_roundMultiple<1,1>
{
};

```

### `glm::detail::is_int<unsigned int>`
```
struct __cppobj glm::detail::is_int<unsigned int>
{
};

```

### `glm::detail::functor2<float,0,glm::tvec3>`
```
struct __cppobj glm::detail::functor2<float,0,glm::tvec3>
{
};

```

### `glm::detail::outerProduct_trait<float,4,glm::tvec4,glm::tvec4>`
```
struct __cppobj glm::detail::outerProduct_trait<float,4,glm::tvec4,glm::tvec4>
{
};

```

### `glm::detail::u5u6u5::<unnamed_type_data>`
```
struct glm::detail::u5u6u5::<unnamed_type_data>
{
  unsigned __int32 x : 5;
  unsigned __int32 y : 6;
  unsigned __int32 z : 5;
};

```

### `glm::detail::compute_log2<float,0,glm::tvec1,1,0>`
```
struct __cppobj glm::detail::compute_log2<float,0,glm::tvec1,1,0>
{
};

```

### `glm::detail::functor2<float,0,glm::tvec2>`
```
struct __cppobj glm::detail::functor2<float,0,glm::tvec2>
{
};

```

### `glm::detail::compute_round<float,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_round<float,0,glm::tvec2,0>
{
};

```

### `glm::detail::storage<float,16,0>`
```
struct __cppobj glm::detail::storage<float,16,0>
{
};

```

### `glm::detail::compute_roundMultiple<0,0>`
```
struct __cppobj glm::detail::compute_roundMultiple<0,0>
{
};

```

### `glm::detail::compute_max_vector<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_max_vector<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::functor1<float,float,0,glm::tvec2>`
```
struct __cppobj glm::detail::functor1<float,float,0,glm::tvec2>
{
};

```

### `glm::detail::functor2<float,0,glm::tvec4>`
```
struct __cppobj glm::detail::functor2<float,0,glm::tvec4>
{
};

```

### `glm::detail::storage<unsigned int,16,1>`
```
struct __cppobj glm::detail::storage<unsigned int,16,1>
{
};

```

### `glm::detail::storage<float,16,1>`
```
struct __cppobj glm::detail::storage<float,16,1>
{
};

```

### `glm::detail::is_aligned<5>`
```
struct __cppobj glm::detail::is_aligned<5>
{
};

```

### `glm::detail::outerProduct_trait<float,5,glm::tvec4,glm::tvec4>`
```
struct __cppobj glm::detail::outerProduct_trait<float,5,glm::tvec4,glm::tvec4>
{
};

```

### `glm::detail::compute_clamp_vector<float,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_clamp_vector<float,0,glm::tvec2,0>
{
};

```

### `glm::detail::compute_floorMultiple<0,0>`
```
struct __cppobj glm::detail::compute_floorMultiple<0,0>
{
};

```

### `glm::detail::compute_vec4_mul<float,0,0>`
```
struct __cppobj glm::detail::compute_vec4_mul<float,0,0>
{
};

```

### `glm::detail::i10i10i10i2::<unnamed_type_data>`
```
struct glm::detail::i10i10i10i2::<unnamed_type_data>
{
  __int32 x : 10;
  __int32 y : 10;
  __int32 z : 10;
  __int32 w : 2;
};

```

### `glm::detail::compute_min_vector<float,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_min_vector<float,0,glm::tvec2,0>
{
};

```

### `glm::detail::compute_roundMultiple<0,1>`
```
struct __cppobj glm::detail::compute_roundMultiple<0,1>
{
};

```

### `glm::detail::compute_clamp_vector<float,0,glm::tvec4,0>`
```
struct __cppobj glm::detail::compute_clamp_vector<float,0,glm::tvec4,0>
{
};

```

### `glm::detail::outerProduct_trait<float,3,glm::tvec4,glm::tvec4>`
```
struct __cppobj glm::detail::outerProduct_trait<float,3,glm::tvec4,glm::tvec4>
{
};

```

### `glm::detail::storage<signed char,4,0>`
```
struct __cppobj glm::detail::storage<signed char,4,0>
{
};

```

### `glm::detail::compute_ceilMultiple<0,0>`
```
struct __cppobj glm::detail::compute_ceilMultiple<0,0>
{
};

```

### `glm::detail::u5u5u5u1::<unnamed_type_data>`
```
struct glm::detail::u5u5u5u1::<unnamed_type_data>
{
  unsigned __int32 x : 5;
  unsigned __int32 y : 5;
  unsigned __int32 z : 5;
  unsigned __int32 w : 1;
};

```

### `glm::detail::storage<unsigned short,8,0>`
```
struct __cppobj glm::detail::storage<unsigned short,8,0>
{
};

```

### `glm::detail::is_aligned<3>`
```
struct __cppobj glm::detail::is_aligned<3>
{
};

```

### `glm::detail::compute_floorMultiple<1,1>`
```
struct __cppobj glm::detail::compute_floorMultiple<1,1>
{
};

```

### `glm::detail::compute_clamp_vector<float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_clamp_vector<float,0,glm::tvec3,0>
{
};

```

### `glm::detail::u10u10u10u2::<unnamed_type_data>`
```
struct glm::detail::u10u10u10u2::<unnamed_type_data>
{
  unsigned __int32 x : 10;
  unsigned __int32 y : 10;
  unsigned __int32 z : 10;
  unsigned __int32 w : 2;
};

```

### `glm::detail::is_aligned<0>`
```
struct __cppobj glm::detail::is_aligned<0>
{
};

```

### `glm::detail::compute_ceilMultiple<1,1>`
```
struct __cppobj glm::detail::compute_ceilMultiple<1,1>
{
};

```

### `glm::detail::compute_min_vector<float,0,glm::tvec4,0>`
```
struct __cppobj glm::detail::compute_min_vector<float,0,glm::tvec4,0>
{
};

```

### `glm::detail::compute_abs<double,1>`
```
struct __cppobj glm::detail::compute_abs<double,1>
{
};

```

### `glm::detail::compute_max_vector<float,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_max_vector<float,0,glm::tvec2,0>
{
};

```

### `glm::detail::u9u9u9e5::<unnamed_type_data>`
```
struct glm::detail::u9u9u9e5::<unnamed_type_data>
{
  unsigned __int32 x : 9;
  unsigned __int32 y : 9;
  unsigned __int32 z : 9;
  unsigned __int32 w : 5;
};

```

### `glm::detail::u4u4::<unnamed_type_data>`
```
struct glm::detail::u4u4::<unnamed_type_data>
{
  unsigned __int32 x : 4;
  unsigned __int32 y : 4;
};

```

### `glm::tvec4<int,3>`
```
struct __cppobj glm::tvec4<int,3>
{
  $61ED7D8B19C6F681DF213B698FD2A90B ___u0;
};

```

### `glTF::Primitive`
```
struct __cppobj glTF::Primitive
{
};

```

### `glm::detail::compute_cross<float,0,0>`
```
struct __cppobj glm::detail::compute_cross<float,0,0>
{
};

```

### `glm::detail::compute_dot<glm::tquat,float,0,0>`
```
struct __cppobj glm::detail::compute_dot<glm::tquat,float,0,0>
{
};

```

### `glm::detail::compute_length2<glm::tvec3,float,0,0>`
```
struct __cppobj glm::detail::compute_length2<glm::tvec3,float,0,0>
{
};

```

### `glm::detail::compute_vec4_div<float,0,0>`
```
struct __cppobj glm::detail::compute_vec4_div<float,0,0>
{
};

```

### `glm::detail::compute_mix<float,float>`
```
struct __cppobj glm::detail::compute_mix<float,float>
{
};

```

### `glm::detail::compute_quat_add<float,0,0>`
```
struct __cppobj glm::detail::compute_quat_add<float,0,0>
{
};

```

### `GetEduClientInfoCommand`
```
struct __cppobj GetEduClientInfoCommand : ClientCommand
{
};

```

### `GetEduClientInfoCommand_vtbl`
```
struct /*VFT*/ GetEduClientInfoCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GetLocalPlayerNameCommand`
```
struct __cppobj GetLocalPlayerNameCommand : ClientCommand
{
};

```

### `GetLocalPlayerNameCommand_vtbl`
```
struct /*VFT*/ GetLocalPlayerNameCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GGInput`
```
struct __cppobj GGInput
{
};

```

### `GuidedFlowClient`
```
struct __cppobj GuidedFlowClient : IGuidedFlowClient
{
  IClientInstance *mClientInstance;
};

```

### `GuidedFlowClient_vtbl`
```
struct /*VFT*/ GuidedFlowClient_vtbl
{
  void (__fastcall *~IGuidedFlowClient)(IGuidedFlowClient *this);
  std::shared_ptr<Social::User> *(__fastcall *getPrimaryUser)(IGuidedFlowClient *this, std::shared_ptr<Social::User> *result);
  SceneFactory *(__fastcall *getSceneFactory)(IGuidedFlowClient *this);
  Options *(__fastcall *getOptions)(IGuidedFlowClient *this);
};

```

### `GameControllerStickEvent`
```
struct GameControllerStickEvent
{
  int id;
  GameControllerStickState state;
  float x;
  float y;
};

```

### `GameControllerTriggerEvent`
```
struct GameControllerTriggerEvent
{
  int id;
  float magnitude;
};

```

### `GameControllerConnectionStateEvent`
```
struct GameControllerConnectionStateEvent
{
  bool controllerIsConnected;
};

```

### `GameControllerJoinEvent`
```
struct GameControllerJoinEvent
{
  bool isConfirmation;
};

```

### `GameControllerChangeUserEvent`
```
struct GameControllerChangeUserEvent
{
  bool restrictToControllerIdChange;
};

```

### `GameControllerEvent`
```
struct GameControllerEvent
{
  GameControllerEventType type;
  GameControllerEventData data;
  int controllerId;
};

```

### `GameController`
```
struct __cppobj __declspec(align(8)) GameController : IGameController
{
  std::vector<GameController::EventQueue> mEventQueues;
  bool mIsConnected;
  int mControllerId;
  bool mIsAdequateController;
  bool mIsPairedToClient;
};

```

### `GameController_vtbl`
```
struct /*VFT*/ GameController_vtbl
{
  void (__fastcall *~IGameController)(IGameController *this);
  bool (__fastcall *hasEvents)(IGameController *this, const void *);
  GameControllerEvent *(__fastcall *getNextEvent)(IGameController *this, GameControllerEvent *result, const void *);
  int (__fastcall *getId)(IGameController *this);
  bool (__fastcall *isConnected)(IGameController *this);
  bool (__fastcall *isAdequateController)(IGameController *this);
  void (__fastcall *setControllerPairedToClient)(IGameController *this, const bool);
  bool (__fastcall *isControllerPairedToClient)(IGameController *this);
};

```

### `GameControllerManager_vtbl`
```
struct /*VFT*/ GameControllerManager_vtbl
{
  void (__fastcall *~IGameControllerManager)(IGameControllerManager *this);
  std::weak_ptr<IGameController> *(__fastcall *getGameController)(IGameControllerManager *this, std::weak_ptr<IGameController> *result, int);
  std::vector<std::weak_ptr<IGameController>> *(__fastcall *getConnectedGameControllers)(IGameControllerManager *this, std::vector<std::weak_ptr<IGameController>> *result);
  std::vector<std::weak_ptr<IGameController>> *(__fastcall *getGameControllersInUse)(IGameControllerManager *this, std::vector<std::weak_ptr<IGameController>> *result);
  bool (__fastcall *hasAdequateConnectedGameController)(IGameControllerManager *this);
  bool (__fastcall *hasAdequateConnectedGameControllers)(IGameControllerManager *this, const unsigned __int64);
  unsigned __int64 (__fastcall *getMaxGameControllerButtons)(IGameControllerManager *this);
  void (__fastcall *registerConsumer)(IGameControllerManager *this, const void *);
  void (__fastcall *unregisterConsumer)(IGameControllerManager *this, const void *);
  void (__fastcall *setControllerRefreshState)(IGameControllerManager *this, ControllerRefreshState);
  ControllerRefreshState (__fastcall *getControllerRefreshState)(IGameControllerManager *this);
  GameControllerErrorType (__fastcall *getPlatformSpecificControllerError)(IGameControllerManager *this);
  void (__fastcall *setPlatformSpecificControllerErrorRetrievalFunc)(IGameControllerManager *this, std::function<enum GameControllerErrorType __cdecl(void)> *);
  void (__fastcall *resetClientControllerCount)(IGameControllerManager *this);
  void (__fastcall *addClientHasAdequateConnectedController)(IGameControllerManager *this, int, const bool);
  bool (__fastcall *isSplitscreenJoinAllowed)(IGameControllerManager *this);
  void (__fastcall *setSplitScreenJoinAllowed)(IGameControllerManager *this, bool);
};

```

### `GameServerConnectProgressHandler`
```
struct __cppobj GameServerConnectProgressHandler : ProgressHandler
{
  bool mFailed;
  bool mConnected;
  bool mHandoverProgress;
  bool mInitialized;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mInitTime;
  std::chrono::duration<__int64,std::ratio<1,1> > mTimeoutTime;
  GameConnectionType mConnectionType;
  std::function<void __cdecl(void)> mOnStart;
  std::function<void __cdecl(void)> mAbortCallback;
  std::function<void __cdecl(std::unordered_map<std::string,std::string> &)> mEventCallback;
};

```

### `GameServerConnectProgressHandler_vtbl`
```
struct /*VFT*/ GameServerConnectProgressHandler_vtbl
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

### `GridComponent`
```
struct __cppobj __declspec(align(8)) GridComponent : UIComponent
{
  glm::tvec2<int,0> mInitDimensions;
  bool IsFirstResize;
  ui::LayoutOffset mBaseSize;
  bool mAutoExpand;
  int mId;
  std::string mInitGridItemPrefix;
  glm::tvec2<int,0> mDimensions;
  std::shared_ptr<UIControl> mGridItemTemplate;
  std::shared_ptr<UIControlFactory> mControlFactory;
  std::string mGridDimensionBinding;
  std::string mCollectionName;
  ui::OrientationType mGridRescalingType;
  ui::OrientationType mGridFillDirection;
  int mMaximumGridItems;
  std::vector<std::shared_ptr<UIControl>> mCachedControls;
  bool mLowMemoryMode;
  int mPartialCreationStartIndex;
  int mPartialCreationEndIndex;
};

```

### `GridComponent_vtbl`
```
struct /*VFT*/ GridComponent_vtbl
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

### `GameArguments`
```
struct __cppobj GameArguments : UriListener, Bedrock::Threading::EnableQueueForMainThread
{
  MinecraftGame *mMinecraft;
  std::vector<ActivationUri> mQueuedUris;
};

```

### `GameArguments_vtbl`
```
struct /*VFT*/ GameArguments_vtbl
{
  void (__fastcall *~UriListener)(UriListener *this);
  void (__fastcall *onUri)(UriListener *this, const ActivationUri *);
  void (__fastcall *tick)(UriListener *this);
};

```

### `GameArgumentCommandOrigin`
```
struct __cppobj GameArgumentCommandOrigin : CommandOrigin
{
  std::string mRequestId;
};

```

### `GameArgumentCommandOrigin_vtbl`
```
struct /*VFT*/ GameArgumentCommandOrigin_vtbl
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

### `GrassBlock`
```
struct __cppobj GrassBlock : BlockLegacy
{
  std::vector<mce::Color> mSideColors;
};

```

### `GrassBlock_vtbl`
```
struct /*VFT*/ GrassBlock_vtbl
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

### `GlobalResourcesCrashRecovery`
```
struct __cppobj GlobalResourcesCrashRecovery
{
};

```

### `GenericProgressHandler`
```
struct __cppobj GenericProgressHandler : ProgressHandler
{
  std::function<void __cdecl(void)> mOnStart;
  std::function<void __cdecl(void)> mOnTick;
  std::function<void __cdecl(void)> mOnCancel;
  bool mIsCancellable;
  std::string mTitleText;
  std::string mMessageText;
};

```

### `GenericProgressHandler_vtbl`
```
struct /*VFT*/ GenericProgressHandler_vtbl
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

### `glm::detail::compute_max_vector<unsigned int,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_max_vector<unsigned int,0,glm::tvec2,0>
{
};

```

### `glm::detail::functor2<unsigned int,0,glm::tvec2>`
```
struct __cppobj glm::detail::functor2<unsigned int,0,glm::tvec2>
{
};

```

### `GameArguments::_tryImport_RequestPermission::__l13::<lambda_7aa0f6aa8ef754a7ea7ed095e894e828>`
```
struct __cppobj GameArguments::_tryImport_RequestPermission::__l13::<lambda_7aa0f6aa8ef754a7ea7ed095e894e828>
{
  std::function<void __cdecl(void)> importFn;
};

```

### `GameArguments::_onUri::__l87::<lambda_2f8cb6b489aa65077a00636dae7ed414>`
```
struct __cppobj GameArguments::_onUri::__l87::<lambda_2f8cb6b489aa65077a00636dae7ed414>
{
  std::function<void __cdecl(void)> loadLevelFn;
};

```

### `GameArguments::_onUri::__l79::<lambda_86dee1a2809def93d60a889bcf0ed582>`
```
struct __cppobj GameArguments::_onUri::__l79::<lambda_86dee1a2809def93d60a889bcf0ed582>
{
  std::_List_const_iterator<std::_List_val<std::_List_simple_types<std::pair<std::string const ,std::string > > > > foundHandle;
  MinecraftGame *mMinecraft;
};

```

### `GameArguments::_onUri::__l55::<lambda_7c893ae7eb244863ee5e402dfe4d16c2>`
```
struct __cppobj GameArguments::_onUri::__l55::<lambda_7c893ae7eb244863ee5e402dfe4d16c2>
{
  GameArguments *const __this;
};

```

### `GameArguments::_onUri::__l46::<lambda_e4058ffa41abf9060aec702ef6d2f7d8>`
```
struct __cppobj GameArguments::_onUri::__l46::<lambda_e4058ffa41abf9060aec702ef6d2f7d8>
{
  GameArguments *const __this;
};

```

### `GameArguments::_onUri::__l43::<lambda_385dacd708e8590483eed567b1dd6fb3>`
```
struct __cppobj GameArguments::_onUri::__l43::<lambda_385dacd708e8590483eed567b1dd6fb3>
{
  GameArguments *const __this;
};

```

### `GameArguments::_onUri::__l40::<lambda_0416f0a054f881cb8b1335285c506372>`
```
struct __cppobj GameArguments::_onUri::__l40::<lambda_0416f0a054f881cb8b1335285c506372>
{
  GameArguments *const __this;
  std::string offerId;
};

```

### `GameArguments::_onUri::__l37::<lambda_c575e68b2bfc376af4d80426985e501f>`
```
struct __cppobj GameArguments::_onUri::__l37::<lambda_c575e68b2bfc376af4d80426985e501f>
{
  GameArguments *const __this;
  std::string offerId;
};

```

### `GameArguments::_onUri::__l5::<lambda_cf42ed79f51f3efd4682a9e1195aa580>`
```
struct __cppobj GameArguments::_onUri::__l5::<lambda_cf42ed79f51f3efd4682a9e1195aa580>
{
  GameArguments *const __this;
  std::string startTopic;
};

```

### `GestureComponent`
```
struct __cppobj __declspec(align(8)) GestureComponent : UIComponent
{
  bool mButtonDown;
  unsigned int mTrackpadButtonId;
  bool mIsHandleButtonMove;
  float mLastPosX;
  float mLastPosY;
};

```

### `GestureComponent_vtbl`
```
struct /*VFT*/ GestureComponent_vtbl
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

### `GridItemComponent`
```
struct __cppobj __declspec(align(8)) GridItemComponent : UIComponent
{
  int mCollectionIndex;
  glm::tvec2<int,0> mGridPosition;
};

```

### `GridItemComponent_vtbl`
```
struct /*VFT*/ GridItemComponent_vtbl
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

### `glm::detail::compute_distance<glm::tvec2,float,0,0>`
```
struct __cppobj glm::detail::compute_distance<glm::tvec2,float,0,0>
{
};

```

### `glm::detail::compute_length<glm::tvec2,float,0,0>`
```
struct __cppobj glm::detail::compute_length<glm::tvec2,float,0,0>
{
};

```

### `GridComponent::_reconstructGridItem::__l13::<lambda_1fa13fbeea773e79889fc47324b29dbd>`
```
struct __cppobj GridComponent::_reconstructGridItem::__l13::<lambda_1fa13fbeea773e79889fc47324b29dbd>
{
};

```

### `GradientRenderer`
```
struct __cppobj __declspec(align(8)) GradientRenderer : MinecraftUICustomRenderer
{
  GradientRenderer::GradientDirection mDirection;
  mce::Color mColor1;
  mce::Color mColor2;
};

```

### `GradientRenderer_vtbl`
```
struct /*VFT*/ GradientRenderer_vtbl
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

### `GlowStickRenderer`
```
struct __cppobj GlowStickRenderer
{
};

```

### `GuiData::_addMessage::__l2::<lambda_ccd9b0b394466a02979b559beb6705c1>`
```
struct __cppobj GuiData::_addMessage::__l2::<lambda_ccd9b0b394466a02979b559beb6705c1>
{
  const std::string *msg;
};

```

### `GamepadDisconnectScreenController`
```
struct __cppobj GamepadDisconnectScreenController : MinecraftScreenController
{
};

```

### `GamepadDisconnectScreenController_vtbl`
```
struct /*VFT*/ GamepadDisconnectScreenController_vtbl
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

### `GamePlayTipScreenController`
```
struct __cppobj GamePlayTipScreenController : ClientInstanceScreenController, PlayerEventListener, ContainerContentChangeListener, ItemEventListener, ActorEventListener
{
  std::shared_ptr<HudContainerManagerController> mHudContainerManagerController;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mGameTipStartTime;
  std::chrono::duration<__int64,std::ratio<1,1> > mTipDisplayDuration;
  std::chrono::duration<__int64,std::ratio<1,1> > mTipDisplayTimeElapsed;
  std::map<enum GamePlayTipId,enum GamePlayTipStatus> mGamePlayTipStatus;
  int mCurrentGamePlayTipIndex;
  bool mIsFirstTick;
  int mCameraMovementDuration;
  int mCharacterWalkDuration;
};

```

### `GamePlayTipScreenController_vtbl`
```
struct /*VFT*/ GamePlayTipScreenController_vtbl
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

### `GeneralSettingsScreenControllerProxy`
```
struct __cppobj GeneralSettingsScreenControllerProxy
{
  const GeneralSettingsScreenControllerProxyCallbacks mCallbacks;
};

```

### `GeneralSettingsScreenController`
```
struct __cppobj __declspec(align(8)) GeneralSettingsScreenController : SettingsScreenControllerBase
{
  bool mIsGlobalSettings;
  bool mReloadTexturePacksOnExit;
  bool mGlobalResourcePacksVisible;
  std::vector<std::pair<std::string,std::string >> mLanguages;
  unsigned __int64 mCurrentlySelectedIndex;
  MultiplayerLockState mMultiplayerState;
  ContentManager *mContentManager;
  PackManagerContentSource *mResourceContentSource;
  tm mLastRefreshTime;
  Bedrock::PubSub::ScopedSubscription mScreenAnimationsOptionSubscription;
  std::string mOverrideMajorVersion;
  std::string mOverrideMinorVersion;
  std::string mOverridePatchVersion;
  std::string mOverrideBetaVersion;
  std::unique_ptr<ContentManagerContext> mContentManagerContext;
  std::unique_ptr<GeneralSettingsScreenControllerProxy> mProxy;
  Social::UserPicturePath mUserGamerPic;
  std::string mUserDisplayName;
  bool mDirty;
  std::shared_ptr<StorageManagementScreenController> mStorageManagementScreenController;
  std::shared_ptr<SubscriptionsScreenController> mSubscriptionsScreenController;
  SoundOptions mSoundOptions;
  bool mRayTracingHoverWarningRenderDistance;
  bool mRayTracingHoverWarningRayTracingDisabled;
  bool mRayTracingHoverWarningUpscalingDisabled;
};

```

### `GeneralSettingsScreenController_vtbl`
```
struct /*VFT*/ GeneralSettingsScreenController_vtbl
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

### `GlobalPauseScreenController`
```
struct __cppobj GlobalPauseScreenController : ClientInstanceScreenController
{
};

```

### `GlobalPauseScreenController_vtbl`
```
struct /*VFT*/ GlobalPauseScreenController_vtbl
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

### `GlobalPauseScreenController::{ctor}::__l2::<lambda_fe774cd51a1995231b4540756fdd05ae>`
```
struct __cppobj GlobalPauseScreenController::{ctor}::__l2::<lambda_fe774cd51a1995231b4540756fdd05ae>
{
  GlobalPauseScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_setFancyBubbles::__l5::<lambda_57f3ab47f411f0a954714065d33b1c77>`
```
struct __cppobj __declspec(align(8)) GeneralSettingsScreenController::_setFancyBubbles::__l5::<lambda_57f3ab47f411f0a954714065d33b1c77>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
  bool value;
};

```

### `GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>`
```
struct __cppobj GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l18::<lambda_8c961efbb9af88f3544748c670760a78>`
```
struct __cppobj GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l18::<lambda_8c961efbb9af88f3544748c670760a78>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l16::<lambda_446324031d016bf4cee7991754960dcd>`
```
struct __cppobj GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l16::<lambda_446324031d016bf4cee7991754960dcd>
{
};

```

### `GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l14::<lambda_5be02b0f0deddff212d928523b97f8c1>`
```
struct __cppobj GeneralSettingsScreenController::_navigateToXblSigninRequiredScreen::__l2::<lambda_a285e8d449efb586750cb4a22290e943>::()::__l14::<lambda_5be02b0f0deddff212d928523b97f8c1>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_updateGamerpicContentAsync::__l5::<lambda_4e3d2391c2ac233aef095450bc0872d5>`
```
struct __cppobj GeneralSettingsScreenController::_updateGamerpicContentAsync::__l5::<lambda_4e3d2391c2ac233aef095450bc0872d5>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_toggleCrossPlatformPlayState::__l2::<lambda_e0a90f514352508e64c4e3ef8ea8215b>`
```
struct __cppobj GeneralSettingsScreenController::_toggleCrossPlatformPlayState::__l2::<lambda_e0a90f514352508e64c4e3ef8ea8215b>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_processPendingImports::__l5::<lambda_77b1685b9689add818af68cbb3fba0e6>`
```
struct __cppobj GeneralSettingsScreenController::_processPendingImports::__l5::<lambda_77b1685b9689add818af68cbb3fba0e6>
{
  GeneralSettingsScreenController *const __this;
  std::vector<PackInstanceId> modelManagerIdentities;
};

```

### `GeneralSettingsScreenController::_setGlobalStack::__l5::<lambda_486d2a4c42f76f99cb73ce04fc304aea>`
```
struct __cppobj __declspec(align(8)) GeneralSettingsScreenController::_setGlobalStack::__l5::<lambda_486d2a4c42f76f99cb73ce04fc304aea>
{
  const std::vector<PackInstanceId> modelManagerIdentities;
  bool anyVersion;
  bool saveStack;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_7dbe0ebc5b38b8562e98f21caca472a4>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_7dbe0ebc5b38b8562e98f21caca472a4>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_f56e393cac229c09a7f9b7fb1ea2a5e4>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_f56e393cac229c09a7f9b7fb1ea2a5e4>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_23bde0fc4d6e2aab824af573f72c4766>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_23bde0fc4d6e2aab824af573f72c4766>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_26f18ea40620a8682d1515156b65e9db>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_26f18ea40620a8682d1515156b65e9db>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_4a217940a79b4db557455c724ea3aeaa>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_4a217940a79b4db557455c724ea3aeaa>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_68afee1cf3821dad92dd03b031ab59d9>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_68afee1cf3821dad92dd03b031ab59d9>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_2b55e5c688479054e9ceab62c2b796d9>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_2b55e5c688479054e9ceab62c2b796d9>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_2b55e5c688479054e9ceab62c2b796d9>::()::__l2::<lambda_4538fb2e55c37fe28a9ca64f9eb3e073>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_2b55e5c688479054e9ceab62c2b796d9>::()::__l2::<lambda_4538fb2e55c37fe28a9ca64f9eb3e073>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_451047ea0615367c522ed11049a42f63>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_451047ea0615367c522ed11049a42f63>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_8bb74f70f38d19cb3d8b6e8ab67b0794>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_8bb74f70f38d19cb3d8b6e8ab67b0794>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_15d029b7158ead18d18c5de556b5f813>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_15d029b7158ead18d18c5de556b5f813>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_ccb05b24b895259988cdebbb99978176>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_ccb05b24b895259988cdebbb99978176>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_e436223cb51fd56e52d064141b269f29>`
```
struct __cppobj GeneralSettingsScreenController::_registerEventHandlers::__l2::<lambda_e436223cb51fd56e52d064141b269f29>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_26dea17c1907d0566d5d9801314f308c>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_26dea17c1907d0566d5d9801314f308c>
{
  Option *nameOption;
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_18903d47233c3b06b541ff4fee88168f>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_18903d47233c3b06b541ff4fee88168f>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_e66dcb1efd362742cd34e1916f1e6ad5>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_e66dcb1efd362742cd34e1916f1e6ad5>
{
  Option *nameOption;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_d1c2fc4cbb1893bae523d499d5d9e225>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_d1c2fc4cbb1893bae523d499d5d9e225>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_fc09532b3b170686a4e6212257f03554>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksLegacy::__l2::<lambda_fc09532b3b170686a4e6212257f03554>
{
  Option *nameOption;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_8acd04d2e1fbea05d68848754b5d474d>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_8acd04d2e1fbea05d68848754b5d474d>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_9488670c798ae44bd0f0e9c54772f6f5>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_9488670c798ae44bd0f0e9c54772f6f5>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_81edc17e43cd964e15fccf24e226595c>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_81edc17e43cd964e15fccf24e226595c>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_4de5652b561123caed60c62dd7003e6e>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_4de5652b561123caed60c62dd7003e6e>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_c1bff72d410cc1c61ca0e0baf776ce00>`
```
struct __cppobj GeneralSettingsScreenController::_registerEditBoxCallbacksPlayFab::__l2::<lambda_c1bff72d410cc1c61ca0e0baf776ce00>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_85e3c213d877e8de2ed457628a956f90>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_85e3c213d877e8de2ed457628a956f90>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6b068617df3c8fd198aee4b941df8162>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6b068617df3c8fd198aee4b941df8162>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6a37024b0eb6d403aad788e368a0bc0d>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6a37024b0eb6d403aad788e368a0bc0d>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_05155037d9fc3c7c262815cc38b0e055>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_05155037d9fc3c7c262815cc38b0e055>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a72bc9c288786b46ada9dfc88fdfd1e4>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a72bc9c288786b46ada9dfc88fdfd1e4>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5447946ab5e1f22a66142355d584aa83>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5447946ab5e1f22a66142355d584aa83>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_67cf9393ffa970a19496f8cceb36ba20>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_67cf9393ffa970a19496f8cceb36ba20>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_39401df7bc880d46575d17ae8037b1d7>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_39401df7bc880d46575d17ae8037b1d7>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d64371d4cf569d9505a87fef4c55a535>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d64371d4cf569d9505a87fef4c55a535>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_76dcc320970c1b91b4a14bd0e448ef9a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_76dcc320970c1b91b4a14bd0e448ef9a>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f7451c3507bf743c11c54fd47d1b34a3>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f7451c3507bf743c11c54fd47d1b34a3>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_aca96a98e38eb59a4b8a6d1455deb2e1>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_aca96a98e38eb59a4b8a6d1455deb2e1>
{
  Option *textBackgroundOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f713f465a8d20885acad8f4197733658>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f713f465a8d20885acad8f4197733658>
{
  Option *textBackgroundOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_9b785234f3a049d091a1744f553a3733>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_9b785234f3a049d091a1744f553a3733>
{
  Option *textBackgroundOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_17d5812b5cd1371b36884d49994fa507>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_17d5812b5cd1371b36884d49994fa507>
{
  Option *textBackgroundOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2c483c397dab7701342434a333c14b43>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2c483c397dab7701342434a333c14b43>
{
  Option *textBackgroundOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_da8668d25b743892e4049b28db222a8c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_da8668d25b743892e4049b28db222a8c>
{
  Option *interfaceOpacitySplitscreenOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b38648f98506a229d02f8c75a5874ce2>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b38648f98506a229d02f8c75a5874ce2>
{
  Option *interfaceOpacitySplitscreenOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2367b2f12f47a7cf0b476cd6bb86427a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2367b2f12f47a7cf0b476cd6bb86427a>
{
  Option *interfaceOpacitySplitscreenOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_760e23450c2389bc04d53d22c3645085>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_760e23450c2389bc04d53d22c3645085>
{
  Option *interfaceOpacitySplitscreenOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3f6d9767cede3da3fc744ffe1d0ff519>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3f6d9767cede3da3fc744ffe1d0ff519>
{
  Option *interfaceOpacitySplitscreenOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3bba6bfb7949e15868914264af82e4da>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3bba6bfb7949e15868914264af82e4da>
{
  Option *interfaceOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_db458ce0d1605d0384770e5c1b58420c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_db458ce0d1605d0384770e5c1b58420c>
{
  Option *interfaceOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1175bb704a7842dd09f22582710ad925>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1175bb704a7842dd09f22582710ad925>
{
  Option *interfaceOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6c288a4cb2b1f58331466cd68d580a3f>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6c288a4cb2b1f58331466cd68d580a3f>
{
  Option *interfaceOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3b6a18900af1b41b6ee4817e9cb447c2>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3b6a18900af1b41b6ee4817e9cb447c2>
{
  Option *interfaceOpacityOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_9718b42e1adc7e7331515a60caba2992>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_9718b42e1adc7e7331515a60caba2992>
{
  Option *smoothLightingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3b7d770f3c21a567e403602c76771e10>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3b7d770f3c21a567e403602c76771e10>
{
  Option *smoothLightingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_79c3e444a991ba1af5a47d8df553ea57>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_79c3e444a991ba1af5a47d8df553ea57>
{
  Option *smoothLightingOption;
  Option *rayTracingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6fa6b3e9c008442325ccb490b210ce17>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6fa6b3e9c008442325ccb490b210ce17>
{
  Option *upscalingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d10210c080f98126228b3fcb6027c629>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d10210c080f98126228b3fcb6027c629>
{
  Option *upscalingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5feb92b4cefc212108b5b0a3bf22f977>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5feb92b4cefc212108b5b0a3bf22f977>
{
  Option *upscalingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ff4977fae0e0d362d30e15abaa96394d>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ff4977fae0e0d362d30e15abaa96394d>
{
  GeneralSettingsScreenController *const __this;
  Option *rayTracingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d971eab6082d70a7a6a5d641c1db6343>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d971eab6082d70a7a6a5d641c1db6343>
{
  Option *rayTracingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_bd978e96379ec6e15ecf1c30ae2095e6>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_bd978e96379ec6e15ecf1c30ae2095e6>
{
  Option *rayTracingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3de35fea6549d14308cea0624a5cb149>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3de35fea6549d14308cea0624a5cb149>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ba0e8f359ca323ac28363dd8daf8a477>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ba0e8f359ca323ac28363dd8daf8a477>
{
  Option *fancyBubbles;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2d3001db54b02cde80cd0e575c0c3d65>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2d3001db54b02cde80cd0e575c0c3d65>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f10951684c60cfd300e6c1a5151d97a8>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f10951684c60cfd300e6c1a5151d97a8>
{
  Option *cloudOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_512a053ada70417ce96db121d697e4d6>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_512a053ada70417ce96db121d697e4d6>
{
  Option *cloudOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7e33798e7b9e6a7fccdddd29c82ffc61>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7e33798e7b9e6a7fccdddd29c82ffc61>
{
  Option *cloudOption;
  Option *fancySkiesOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b8de5d2ce75d202a961854d990e6aa5b>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b8de5d2ce75d202a961854d990e6aa5b>
{
  GeneralSettingsScreenController *const __this;
  Option *textureHotReloaderOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3d820602528804405f3873882173becb>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3d820602528804405f3873882173becb>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_509fbf47531da9b0b317092343850c91>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_509fbf47531da9b0b317092343850c91>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_68c219ae05286fbba032106d2bb3707f>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_68c219ae05286fbba032106d2bb3707f>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_290f616e5ee8e5c2ef040d38a7f32bf5>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_290f616e5ee8e5c2ef040d38a7f32bf5>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a765e72e1f23d69c48b03c2a93576b53>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a765e72e1f23d69c48b03c2a93576b53>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_59659ea40bb189947348eafac32b2efb>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_59659ea40bb189947348eafac32b2efb>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0a67311a8b48b6abdcf5d24cf8a14f7a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0a67311a8b48b6abdcf5d24cf8a14f7a>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2a70dab88ae07abaf012b91ce0e9fb4e>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2a70dab88ae07abaf012b91ce0e9fb4e>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_be34d433288df7528ed8da051d249ab6>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_be34d433288df7528ed8da051d249ab6>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_bbfb5a19f45e0cce45027c638cb0bf48>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_bbfb5a19f45e0cce45027c638cb0bf48>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ffed3988c47ba09ecea43c20b517e03a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ffed3988c47ba09ecea43c20b517e03a>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2f7fb69f2c8f0fb0baee690c64680b3e>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2f7fb69f2c8f0fb0baee690c64680b3e>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ba5f43ea9e8519080825bd76ad2a151c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ba5f43ea9e8519080825bd76ad2a151c>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l14::<lambda_4f16f8dc066b7ca448143de25a0d4fbd>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l14::<lambda_4f16f8dc066b7ca448143de25a0d4fbd>
{
  Option *rayTracingOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0ea63192afd189ca0c6cf13d5f585841>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0ea63192afd189ca0c6cf13d5f585841>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_fc2d72e0447140b9de1f067cec21c9cb>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_fc2d72e0447140b9de1f067cec21c9cb>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3e7a3d27d14520bb67c9ef85c88f7434>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_3e7a3d27d14520bb67c9ef85c88f7434>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_710ee40c904f146247a20186bb0aca60>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_710ee40c904f146247a20186bb0aca60>
{
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_e9e472dfdb709c650b689606659e253b>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_e9e472dfdb709c650b689606659e253b>
{
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b777949437eff6702b8dc1e306de3ccb>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_b777949437eff6702b8dc1e306de3ccb>
{
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_418dbaef90656bf0c3255241d72dee7b>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_418dbaef90656bf0c3255241d72dee7b>
{
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2c75ecbcaf6953569afd8b3faf2e830a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2c75ecbcaf6953569afd8b3faf2e830a>
{
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a0ff7abeac688138056df821ded28447>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a0ff7abeac688138056df821ded28447>
{
  GeneralSettingsScreenController *const __this;
  Option *primeFovOption;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_79edb145081bde14e6cada42167889ac>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_79edb145081bde14e6cada42167889ac>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_acb943e0bd8c4ea4c166051b5e9d017c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_acb943e0bd8c4ea4c166051b5e9d017c>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f3213293b3d02f6e3380e27b82320763>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_f3213293b3d02f6e3380e27b82320763>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1ec5cc74ebf99a976fe769113e2d86d4>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1ec5cc74ebf99a976fe769113e2d86d4>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_44879c87172bcfa2dd6940d06f10c37a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_44879c87172bcfa2dd6940d06f10c37a>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1a09b66746ab0a3fc42f5bc52da23c9b>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1a09b66746ab0a3fc42f5bc52da23c9b>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1aee00d0d578831c97e043d291fe32f3>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1aee00d0d578831c97e043d291fe32f3>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_90e1a2a2aed07bc9594cff42d57e19ee>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_90e1a2a2aed07bc9594cff42d57e19ee>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d75d0f11eaefb6874c09e00f8d04364d>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_d75d0f11eaefb6874c09e00f8d04364d>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_e6568cf6d4a5008daaad2a3ff4df68ff>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_e6568cf6d4a5008daaad2a3ff4df68ff>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_4292a584eda9e1b274da5d69267c4d19>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_4292a584eda9e1b274da5d69267c4d19>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_4292a584eda9e1b274da5d69267c4d19>::()::__l2::<lambda_1fdbc1cdd9fafe0db41f605b98940373>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_4292a584eda9e1b274da5d69267c4d19>::()::__l2::<lambda_1fdbc1cdd9fafe0db41f605b98940373>
{
  std::string resetGroupTag;
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_99559b7545ac6f26ae99cd186fafd46e>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_99559b7545ac6f26ae99cd186fafd46e>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1c0b22f6bf0ed1f57c5a368e80fdd9ee>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1c0b22f6bf0ed1f57c5a368e80fdd9ee>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1c0b22f6bf0ed1f57c5a368e80fdd9ee>::()::__l2::<lambda_868d0c102ea85af4b4a8ef6c5324d739>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1c0b22f6bf0ed1f57c5a368e80fdd9ee>::()::__l2::<lambda_868d0c102ea85af4b4a8ef6c5324d739>
{
  std::weak_ptr<GeneralSettingsScreenController> weakThis;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_36eab77f1e93bb925db0220bf5c1b64c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_36eab77f1e93bb925db0220bf5c1b64c>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7b16c97a9d20775d1a496fa9720e7d9d>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7b16c97a9d20775d1a496fa9720e7d9d>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_945d4b29053537859b4c0a640fabddad>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_945d4b29053537859b4c0a640fabddad>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l10::<lambda_ccf731862b40569e5b4aeb4b07e8e2e1>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l10::<lambda_ccf731862b40569e5b4aeb4b07e8e2e1>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l10::<lambda_adc70ac2950b21a3b04958c1789c0279>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l10::<lambda_adc70ac2950b21a3b04958c1789c0279>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7eaf61fe58d7404413bd99d2aa0362b1>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7eaf61fe58d7404413bd99d2aa0362b1>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7dd8ebc768c13a53c85c43b7b78a8682>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7dd8ebc768c13a53c85c43b7b78a8682>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1e5944f6022985e1f352de0156dfe7f3>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_1e5944f6022985e1f352de0156dfe7f3>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7e16fa7604de848f0965289fce1a95a8>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7e16fa7604de848f0965289fce1a95a8>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6c21f98004cb1eb4d97bf04e15a4e93f>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_6c21f98004cb1eb4d97bf04e15a4e93f>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2917c565c74ceb2227b1fad3f7b99905>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2917c565c74ceb2227b1fad3f7b99905>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5c46500abe436a25bb021248b23de133>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_5c46500abe436a25bb021248b23de133>
{
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2ee64da9d502734069ae9ad14dae324b>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_2ee64da9d502734069ae9ad14dae324b>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ef5feac0ac4ef09e8e494c29136d735f>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_ef5feac0ac4ef09e8e494c29136d735f>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_8cff55b6bc6327f2322ef8a2fcf1c69a>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_8cff55b6bc6327f2322ef8a2fcf1c69a>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_53603fc23b36fd94e03e60dca2aa2fb6>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_53603fc23b36fd94e03e60dca2aa2fb6>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0c319efb96758e44ba532300eccda346>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0c319efb96758e44ba532300eccda346>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_eb20d9ee1af586f42cbbfed67f2f15ba>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_eb20d9ee1af586f42cbbfed67f2f15ba>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_8540bbcc5b7f0a35831384ec434d7e65>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_8540bbcc5b7f0a35831384ec434d7e65>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a54d885870a4936102f0ecb32a948bb6>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_a54d885870a4936102f0ecb32a948bb6>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0277457ba4bdaed49d8dab41624f6b42>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_0277457ba4bdaed49d8dab41624f6b42>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_763f2f4605a7877840a13d1081c8cd7c>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_763f2f4605a7877840a13d1081c8cd7c>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_29c05672899dfe73c9fbf1d93ce60891>`
```
struct __cppobj GeneralSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_29c05672899dfe73c9fbf1d93ce60891>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_d21f3266c96cf6363dbd96c80f2d866e>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_d21f3266c96cf6363dbd96c80f2d866e>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_02c84020cea5e130393faf4a07a66dad>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_02c84020cea5e130393faf4a07a66dad>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_2f1384c895585897340a8656ca7c6f0f>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_2f1384c895585897340a8656ca7c6f0f>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_d996b4866699dc38cc51b64f96988544>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_d996b4866699dc38cc51b64f96988544>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_abaa6967f791710918e5cc28b7a6f3a0>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_abaa6967f791710918e5cc28b7a6f3a0>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l30::<lambda_1cfb91ff6485e39317d6d3b8323c9250>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l30::<lambda_1cfb91ff6485e39317d6d3b8323c9250>
{
  GeneralSettingsScreenController *const __this;
};

```

### `GeneralSettingsScreenController::{ctor}::__l2::<lambda_aa7d27e589872d3cebdd6d8090e3c1d5>`
```
struct __cppobj GeneralSettingsScreenController::{ctor}::__l2::<lambda_aa7d27e589872d3cebdd6d8090e3c1d5>
{
};

```

### `GamepadDisconnectScreenController::{ctor}::__l2::<lambda_4b6cdc10162a796b28bbec52abcc9c45>`
```
struct __cppobj GamepadDisconnectScreenController::{ctor}::__l2::<lambda_4b6cdc10162a796b28bbec52abcc9c45>
{
  GamepadDisconnectScreenController *const __this;
};

```

### `GiftPromoLocIDs`
```
struct __cppobj GiftPromoLocIDs
{
  std::string title;
  std::string description;
  std::string claimed;
  std::string unclaimed;
};

```

### `GenericPlatformMultiplayerRestrictions`
```
struct __cppobj GenericPlatformMultiplayerRestrictions : PlatformMultiplayerRestrictions
{
};

```

### `GenericPlatformMultiplayerRestrictions_vtbl`
```
struct /*VFT*/ GenericPlatformMultiplayerRestrictions_vtbl
{
  void (__fastcall *~PlatformMultiplayerRestrictions)(PlatformMultiplayerRestrictions *this);
  bool (__fastcall *platformRestrictsMultiplayer)(PlatformMultiplayerRestrictions *this);
  void (__fastcall *displayPlatformRestrictsMultiplayerModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)>);
  void (__fastcall *displayPlatformRestrictsUserGeneratedContentModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)> *);
  void (__fastcall *displayPlatformRestrictsChatModal)(PlatformMultiplayerRestrictions *this, std::function<void __cdecl(void)> *);
};

```

### `GenericPlatformUpsellDialog`
```
struct __cppobj GenericPlatformUpsellDialog : PlatformUpsellDialog
{
};

```

### `GenericPlatformUpsellDialog_vtbl`
```
struct /*VFT*/ GenericPlatformUpsellDialog_vtbl
{
  void (__fastcall *~PlatformUpsellDialog)(PlatformUpsellDialog *this);
  void (__fastcall *show)(PlatformUpsellDialog *this, const std::shared_ptr<Social::User>, std::function<void __cdecl(bool)>);
};

```

### `glm::detail::compute_normalize<float,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_normalize<float,0,glm::tvec2,0>
{
};

```

### `glm::detail::compute_determinant<glm::tmat4x4,float,0,0>`
```
struct __cppobj glm::detail::compute_determinant<glm::tmat4x4,float,0,0>
{
};

```

### `GameServer_vtbl`
```
struct /*VFT*/ GameServer_vtbl
{
  void (__fastcall *~GameServer)(GameServer *this);
};

```

### `GameControllerMapper::TriggerState`
```
struct GameControllerMapper::TriggerState
{
  unsigned int id;
  ButtonState currentState;
  float triggerThreshold;
};

```

### `GameControllerMapper::DirectionAttributes`
```
struct __declspec(align(4)) GameControllerMapper::DirectionAttributes
{
  DirectionId id;
  int xAxis;
  int yAxis;
  bool raiseTurnEvents;
};

```

### `GameControllerMapper`
```
struct __cppobj GameControllerMapper : InputDeviceMapper
{
  long double mLastTime;
  std::vector<GameControllerMapper::GamepadStickTurnData> mStickTurnData;
  std::unordered_map<int,GameControllerMapper::GameControllerMappingData> mPerIdMappings;
};

```

### `GameControllerMapper_vtbl`
```
struct /*VFT*/ GameControllerMapper_vtbl
{
  void (__fastcall *~InputDeviceMapper)(InputDeviceMapper *this);
  void (__fastcall *setMapping)(InputDeviceMapper *this, InputEventQueue *, const BindingFactory *, const InputMapping *, int);
  void (__fastcall *clearMapping)(InputDeviceMapper *this, int);
  void (__fastcall *clearInputDeviceQueue)(InputDeviceMapper *this);
  void (__fastcall *clearInputDeviceQueueForFrame)(InputDeviceMapper *this);
  void (__fastcall *hardResetInputDeviceQueue)(InputDeviceMapper *this);
  bool (__fastcall *tick)(InputDeviceMapper *this, InputEventQueue *, ControllerIDtoClientMap *);
  InputMode (__fastcall *getInputMode)(InputDeviceMapper *this);
  void (__fastcall *getCursorPos)(InputDeviceMapper *this, float *, float *);
  void (__fastcall *render)(InputDeviceMapper *this, InputRenderContext *);
  void (__fastcall *setWindowSize)(InputDeviceMapper *this, int, int);
  void (__fastcall *setBindingMode)(InputDeviceMapper *this, InputBindingMode, int);
  InputBindingMode (__fastcall *getBindingMode)(InputDeviceMapper *this, int);
  void (__fastcall *changeControllerId)(InputDeviceMapper *this, int, int);
  std::vector<std::weak_ptr<IGameController>> *(__fastcall *_getGameControllers)(GameControllerMapper *this, std::vector<std::weak_ptr<IGameController>> *result);
  const GameControllerInputMapping *(__fastcall *getGameControllerMapping)(GameControllerMapper *this, const InputMapping *);
};

```

### `GazeGestureVoiceMapper`
```
struct __cppobj GazeGestureVoiceMapper : InputDeviceMapper
{
  unsigned int mPointerPressedButtonId;
  unsigned int mMenuSelectButtonId;
  unsigned int mDictationEventButtonId;
  int mPrimaryGameControllerId;
};

```

### `GazeGestureVoiceMapper_vtbl`
```
struct /*VFT*/ GazeGestureVoiceMapper_vtbl
{
  void (__fastcall *~InputDeviceMapper)(InputDeviceMapper *this);
  void (__fastcall *setMapping)(InputDeviceMapper *this, InputEventQueue *, const BindingFactory *, const InputMapping *, int);
  void (__fastcall *clearMapping)(InputDeviceMapper *this, int);
  void (__fastcall *clearInputDeviceQueue)(InputDeviceMapper *this);
  void (__fastcall *clearInputDeviceQueueForFrame)(InputDeviceMapper *this);
  void (__fastcall *hardResetInputDeviceQueue)(InputDeviceMapper *this);
  bool (__fastcall *tick)(InputDeviceMapper *this, InputEventQueue *, ControllerIDtoClientMap *);
  InputMode (__fastcall *getInputMode)(InputDeviceMapper *this);
  void (__fastcall *getCursorPos)(InputDeviceMapper *this, float *, float *);
  void (__fastcall *render)(InputDeviceMapper *this, InputRenderContext *);
  void (__fastcall *setWindowSize)(InputDeviceMapper *this, int, int);
  void (__fastcall *setBindingMode)(InputDeviceMapper *this, InputBindingMode, int);
  InputBindingMode (__fastcall *getBindingMode)(InputDeviceMapper *this, int);
  void (__fastcall *changeControllerId)(InputDeviceMapper *this, int, int);
};

```

### `GamePadMapper`
```
struct __cppobj GamePadMapper : GameControllerMapper
{
};

```

### `GamePadMapper_vtbl`
```
struct /*VFT*/ GamePadMapper_vtbl
{
  void (__fastcall *~InputDeviceMapper)(InputDeviceMapper *this);
  void (__fastcall *setMapping)(InputDeviceMapper *this, InputEventQueue *, const BindingFactory *, const InputMapping *, int);
  void (__fastcall *clearMapping)(InputDeviceMapper *this, int);
  void (__fastcall *clearInputDeviceQueue)(InputDeviceMapper *this);
  void (__fastcall *clearInputDeviceQueueForFrame)(InputDeviceMapper *this);
  void (__fastcall *hardResetInputDeviceQueue)(InputDeviceMapper *this);
  bool (__fastcall *tick)(InputDeviceMapper *this, InputEventQueue *, ControllerIDtoClientMap *);
  InputMode (__fastcall *getInputMode)(InputDeviceMapper *this);
  void (__fastcall *getCursorPos)(InputDeviceMapper *this, float *, float *);
  void (__fastcall *render)(InputDeviceMapper *this, InputRenderContext *);
  void (__fastcall *setWindowSize)(InputDeviceMapper *this, int, int);
  void (__fastcall *setBindingMode)(InputDeviceMapper *this, InputBindingMode, int);
  InputBindingMode (__fastcall *getBindingMode)(InputDeviceMapper *this, int);
  void (__fastcall *changeControllerId)(InputDeviceMapper *this, int, int);
  std::vector<std::weak_ptr<IGameController>> *(__fastcall *_getGameControllers)(GameControllerMapper *this, std::vector<std::weak_ptr<IGameController>> *result);
  const GameControllerInputMapping *(__fastcall *getGameControllerMapping)(GameControllerMapper *this, const InputMapping *);
};

```

### `GeometryGroup::_loadModelsAsync::__l2::<lambda_ad86789f0e858ab44c5ce87d7d4b8f93>`
```
struct __cppobj GeometryGroup::_loadModelsAsync::__l2::<lambda_ad86789f0e858ab44c5ce87d7d4b8f93>
{
  GeometryGroup *const __this;
  std::shared_ptr<GeometryInheritanceTree> inheritance;
  std::function<void __cdecl(GeometryGroup &,std::string const &,ModelParent const &)> loadModelFunction;
};

```

### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l7::<lambda_a96d96bc6b381f557279f6ff3a82af7c>`
```
struct __cppobj GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l7::<lambda_a96d96bc6b381f557279f6ff3a82af7c>
{
  std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> > allTreesLoaded;
};

```

### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3>`
```
struct __cppobj GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3>
{
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *rit;
  const std::shared_ptr<GeometryInheritanceTree> *inheritance;
  const std::function<void __cdecl(Json::Value &)> *postLoadFixup;
  ResourceLoadManager *resourceLoadManager;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *lastTask;
};

```

### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_bddabd69558e514a4bfb627a747ff667>`
```
struct __cppobj GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_bddabd69558e514a4bfb627a747ff667>
{
  GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3> *buildInheritanceTree;
};

```

### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_cc7a6660ea8906e5852e5cceccee4e66>`
```
struct __cppobj GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_cc7a6660ea8906e5852e5cceccee4e66>
{
  GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3> *buildInheritanceTree;
};

```

### `GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3>::()::__l2::<lambda_47439bac35702fdd0781327729bea8c5>`
```
struct __cppobj GeometryGroup::loadGeometriesAsync::__l2::<lambda_dc702485f766a53d6093827c408e76c0>::()::__l4::<lambda_df1fb1247c02491ca14ca3838db4c6b3>::()::__l2::<lambda_47439bac35702fdd0781327729bea8c5>
{
};

```

### `GeometryGroup::addGeometries::__l5::<lambda_d1e781d8425c4095739e674442407f17>`
```
struct __cppobj GeometryGroup::addGeometries::__l5::<lambda_d1e781d8425c4095739e674442407f17>
{
  std::shared_ptr<GeometryInheritanceTree> inheritance;
  std::string gs;
};

```

### `GeometryGroup::_buildGeometryFileSchema_v1_8::__l2::<lambda_b1c74fc64238af4a05a0d12e6c0d1e34>`
```
struct __cppobj GeometryGroup::_buildGeometryFileSchema_v1_8::__l2::<lambda_b1c74fc64238af4a05a0d12e6c0d1e34>
{
};

```

### `GeometryGroup::_buildGeometryFileSchema_pre_v1_8::__l2::<lambda_5f5d9379159cf865e9f7ed5dd46adc9e>`
```
struct __cppobj GeometryGroup::_buildGeometryFileSchema_pre_v1_8::__l2::<lambda_5f5d9379159cf865e9f7ed5dd46adc9e>
{
};

```

### `GeometryGroup::_buildGeometryFileSchema_v1_16::__l2::<lambda_e911008a3fbab95447a5e990fc4d13a6>`
```
struct __cppobj GeometryGroup::_buildGeometryFileSchema_v1_16::__l2::<lambda_e911008a3fbab95447a5e990fc4d13a6>
{
};

```

### `GeometryGroup::_buildGeometryFileSchema_v1_14::__l2::<lambda_4fa752bf8dec3d38971e5833db55df11>`
```
struct __cppobj GeometryGroup::_buildGeometryFileSchema_v1_14::__l2::<lambda_4fa752bf8dec3d38971e5833db55df11>
{
};

```

### `GeometryGroup::_buildGeometryFileSchema_v1_12::__l2::<lambda_3611d3b7f6da78ef9c66988a45d5c291>`
```
struct __cppobj GeometryGroup::_buildGeometryFileSchema_v1_12::__l2::<lambda_3611d3b7f6da78ef9c66988a45d5c291>
{
};

```

### `GeometryGroup::_loadModelsAsync::__l5::<lambda_c45606d7c3a8134a8270bb7a89e953eb>`
```
struct __cppobj GeometryGroup::_loadModelsAsync::__l5::<lambda_c45606d7c3a8134a8270bb7a89e953eb>
{
  std::function<void __cdecl(void)> mainThreadCallback;
};

```

### `Guardian`
```
struct __cppobj Guardian : Monster
{
  std::string ATTACK_SOUND;
  float ELDER_SIZE_SCALE;
  RandomStrollGoal *randomStrollGoal;
  int FLAG_MOVING;
  int FLAG_ELDER;
  Vec3 startPos;
  float clientSideTailAnimation;
  float clientSideTailAnimationO;
  float clientSideTailAnimationSpeed;
  float clientSideSpikesAnimation;
  float clientSideSpikesAnimationO;
  Mob *clientSideCachedAttackTarget;
  int clientSideAttackTime;
  bool clientSideTouchedGround;
  ActorUniqueID mAttackTargetId;
  bool mElderGhost;
  unsigned __int64 mLaserLoop;
  ActorUniqueID mEyeTarget;
};

```

### `GuardianModel`
```
struct __cppobj GuardianModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mHead;
  ModelPart mEye;
  ModelPart mTailPart0;
  ModelPart mTailPart1;
  ModelPart mTailPart2;
  ModelPart mSpikeParts[12];
  Vec3 mSpikePositions[12];
};

```

### `GuardianModel_vtbl`
```
struct /*VFT*/ GuardianModel_vtbl
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
  void (__fastcall *setupAnim)(GuardianModel *this, Actor *, float, float, float, float, float, float);
};

```

### `GameRelightingTestData`
```
struct __cppobj __declspec(align(8)) GameRelightingTestData : Bedrock::EnableNonOwnerReferences
{
  std::atomic<unsigned __int64> mNumberOfInFlightChunkOriginalRelights;
  unsigned __int64 mNumberOfPendingServerRuntimeChunksToRelight;
  unsigned __int64 mNumberOfPendingClientRuntimeChunksToRelight;
  bool mPauseRuntimeRelighting;
};

```

### `glm::detail::compute_findMSB_vec<int,0,glm::tvec1,32>`
```
struct __cppobj glm::detail::compute_findMSB_vec<int,0,glm::tvec1,32>
{
};

```

### `glm::detail::functor1<int,int,0,glm::tvec1>`
```
struct __cppobj glm::detail::functor1<int,int,0,glm::tvec1>
{
};

```

### `GeometryPiece`
```
struct __cppobj GeometryPiece
{
  Json::Value mValue;
  SemVersion mFileVersion;
  TextureUVCoordinateSet mPieceUV;
  _BYTE mAnimationType[4];
  bool mIsSkeleton;
  std::string mDebugName;
};

```

### `GuardianRenderer`
```
struct __cppobj GuardianRenderer : MobRenderer
{
  mce::TexturePtr mElderSkin;
  mce::TexturePtr mBeamSkin;
  mce::MaterialPtr mBeamMaterial;
  std::unique_ptr<GuardianModel> mGhostModel;
};

```

### `GuardianRenderer_vtbl`
```
struct /*VFT*/ GuardianRenderer_vtbl
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
};

```

### `GrantXPSubcomponent`
```
struct __cppobj GrantXPSubcomponent : OnHitSubcomponent
{
  int mMinXPGranted;
  int mMaxXPGranted;
};

```

### `GrantXPSubcomponent_vtbl`
```
struct /*VFT*/ GrantXPSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `glm::detail::compute_length<glm::tvec3,float,0,0>`
```
struct __cppobj glm::detail::compute_length<glm::tvec3,float,0,0>
{
};

```

### `glm::detail::compute_mix_scalar<float,float,0,glm::tvec3,0>`
```
struct __cppobj glm::detail::compute_mix_scalar<float,float,0,glm::tvec3,0>
{
};

```

### `glm::detail::compute_sign<int,0,glm::tvec1,0,0>`
```
struct __cppobj glm::detail::compute_sign<int,0,glm::tvec1,0,0>
{
};

```

### `GameRenderer::_extractFrame::__l2::<lambda_7b800e73f11ba95173c33127ae4d80bc>`
```
struct __cppobj GameRenderer::_extractFrame::__l2::<lambda_7b800e73f11ba95173c33127ae4d80bc>
{
};

```

### `GameRenderer::renderCurrentFrame::__l11::<lambda_316ec61db70aec121777e41ebae9f41c>`
```
struct __cppobj GameRenderer::renderCurrentFrame::__l11::<lambda_316ec61db70aec121777e41ebae9f41c>
{
  bool *renderGraphContainsPlayScreen;
  GameRenderer *const __this;
};

```

### `GameRenderer::renderCurrentFrame::__l11::<lambda_316ec61db70aec121777e41ebae9f41c>::()::__l5::<lambda_beb2d88144d2ab7d071a920b89695f97>`
```
struct __cppobj GameRenderer::renderCurrentFrame::__l11::<lambda_316ec61db70aec121777e41ebae9f41c>::()::__l5::<lambda_beb2d88144d2ab7d071a920b89695f97>
{
  IClientInstance *client;
  bool *renderGraphContainsPlayScreen;
  GameRenderer *const __this;
};

```

### `glm::detail::compute_clamp_vector<int,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_clamp_vector<int,0,glm::tvec2,0>
{
};

```

### `glm::detail::compute_mix_scalar<float,float,0,glm::tvec4,0>`
```
struct __cppobj glm::detail::compute_mix_scalar<float,float,0,glm::tvec4,0>
{
};

```

### `glm::detail::compute_max_vector<int,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_max_vector<int,0,glm::tvec2,0>
{
};

```

### `glm::detail::compute_min_vector<int,0,glm::tvec2,0>`
```
struct __cppobj glm::detail::compute_min_vector<int,0,glm::tvec2,0>
{
};

```

### `glm::detail::functor2<int,0,glm::tvec2>`
```
struct __cppobj glm::detail::functor2<int,0,glm::tvec2>
{
};

```

### `GetRealmsPaymentServiceStatus`
```
struct __cppobj GetRealmsPaymentServiceStatus : RequestHandler
{
  const std::string mHost;
  const std::string mRelyingParty;
  std::function<void __cdecl(bool)> mCallback;
  std::shared_ptr<bool> mIsStatusOk;
};

```

### `GetRealmsPaymentServiceStatus_vtbl`
```
struct /*VFT*/ GetRealmsPaymentServiceStatus_vtbl
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

### `GameSaveSystem::syncWorld::__l5::<lambda_ba37237390008dfc3af06f2d10e416a5>`
```
struct __cppobj GameSaveSystem::syncWorld::__l5::<lambda_ba37237390008dfc3af06f2d10e416a5>
{
  std::weak_ptr<SaveContainer> wptrWorldContainer;
};

```

### `GameSaveSystem::monitorWorld::__l5::<lambda_f7aaf3dc6d271f4cdfe6f939ad56de57>`
```
struct __cppobj GameSaveSystem::monitorWorld::__l5::<lambda_f7aaf3dc6d271f4cdfe6f939ad56de57>
{
  GameSaveSystem *const __this;
  std::string *levelId;
  bool *isMonitoringWorld;
};

```

### `GameControllerHandler_vtbl`
```
struct /*VFT*/ GameControllerHandler_vtbl
{
  void (__fastcall *~GameControllerHandler)(GameControllerHandler *this);
  void (__fastcall *refresh)(GameControllerHandler *this, bool, bool);
  void (__fastcall *refresh)(GameControllerHandler *this);
  void (__fastcall *shutdown)(GameControllerHandler *this);
  GameControllerErrorType (__fastcall *checkPlatformSpecificControllerError)(GameControllerHandler *this);
  float (__fastcall *normalizeAxis)(GameControllerHandler *this, float, float);
  void (__fastcall *normalizeAxes)(GameControllerHandler *this, float *, float *, float);
};

```

### `GameControllerHandler_Windows_vtbl`
```
struct /*VFT*/ GameControllerHandler_Windows_vtbl
{
  void (__fastcall *~GameControllerHandler)(GameControllerHandler *this);
  void (__fastcall *refresh)(GameControllerHandler *this, bool, bool);
  void (__fastcall *refresh)(GameControllerHandler *this);
  void (__fastcall *shutdown)(GameControllerHandler *this);
  GameControllerErrorType (__fastcall *checkPlatformSpecificControllerError)(GameControllerHandler *this);
  float (__fastcall *normalizeAxis)(GameControllerHandler *this, float, float);
  void (__fastcall *normalizeAxes)(GameControllerHandler *this, float *, float *, float);
};

```

### `glm::detail::compute_vec4_nequal<int,0,-1,32,0>`
```
struct __cppobj glm::detail::compute_vec4_nequal<int,0,-1,32,0>
{
};

```

### `glm::detail::is_int<float>`
```
struct __cppobj glm::detail::is_int<float>
{
};

```

### `glm::detail::compute_vec4_nequal<float,0,0,32,0>`
```
struct __cppobj glm::detail::compute_vec4_nequal<float,0,0,32,0>
{
};

```

### `glm::detail::compute_vec4_equal<float,0,0,32,0>`
```
struct __cppobj glm::detail::compute_vec4_equal<float,0,0,32,0>
{
};

```

### `GildedBlackstone`
```
struct __cppobj GildedBlackstone : BlockLegacy
{
};

```

### `GildedBlackstone_vtbl`
```
struct /*VFT*/ GildedBlackstone_vtbl
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

### `GameLightingChecker::CheckAreaForLightingResults`
```
struct __cppobj __declspec(align(8)) GameLightingChecker::CheckAreaForLightingResults
{
  std::vector<BlockPos> mErrorList;
  unsigned __int64 mNumBlocksChecked;
  bool mSuccess;
};

```

### `GameMasterEntityServerCommandOrigin`
```
struct __cppobj GameMasterEntityServerCommandOrigin : ActorServerCommandOrigin
{
};

```

### `GameMasterEntityServerCommandOrigin_vtbl`
```
struct /*VFT*/ GameMasterEntityServerCommandOrigin_vtbl
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

### `getAlgorithm::__l2::<lambda_df051ec572d0ca9607931632dcae6c76>`
```
struct __cppobj getAlgorithm::__l2::<lambda_df051ec572d0ca9607931632dcae6c76>
{
  const std::string *algorithm;
};

```

### `getAlgorithm::__l2::<lambda_54f6018f10717073cad896b0fbeb9f59>`
```
struct __cppobj getAlgorithm::__l2::<lambda_54f6018f10717073cad896b0fbeb9f59>
{
  Crypto::Asymmetric::System keyType;
};

```

### `GeneticsComponent::Gene`
```
struct __cppobj GeneticsComponent::Gene
{
  int mainAllele;
  int hiddenAllele;
};

```

### `GeneticVariant`
```
struct __cppobj GeneticVariant
{
  IntRange mainAllele;
  IntRange hiddenAllele;
  IntRange eitherAllele;
  IntRange bothAllele;
  DefinitionTrigger onBorn;
};

```

### `GeneDefinition`
```
struct __cppobj GeneDefinition
{
  std::string mName;
  IntRange mAlleleRange;
  std::vector<GeneticVariant> mGeneticVariants;
};

```

### `GeneticsDefinition`
```
const struct __cppobj GeneticsDefinition
{
  float mMutationRate;
  std::vector<GeneDefinition> mGeneDefinitions;
};

```

### `GeneticsComponent`
```
struct __cppobj GeneticsComponent : IEntityComponent
{
  std::vector<GeneticsComponent::Gene> mGenes;
  const GeneticsDefinition *mGeneticsDescription;
  Random *mRandom;
};

```

### `GiveableDefinition`
```
struct __cppobj GiveableDefinition
{
  std::vector<GiveableTrigger> mTriggers;
};

```

### `GiveableComponent`
```
struct __cppobj GiveableComponent : IEntityComponent
{
  std::vector<unsigned __int64> mCoolDownTimeStamps;
};

```

### `GoalSelectorComponent`
```
struct __cppobj GoalSelectorComponent : IEntityComponent
{
  std::vector<std::pair<unsigned short,PrioritizedGoal>> mGoalMap;
};

```

### `GroupSizeDefinition`
```
struct __cppobj GroupSizeDefinition
{
  float mRadius;
  ActorFilterGroup mFilter;
};

```

### `GrowsCropDefinition`
```
struct __cppobj GrowsCropDefinition
{
  int mCharges;
  float mChance;
};

```

### `GrowsCropComponent`
```
struct __cppobj GrowsCropComponent : IEntityComponent
{
  int mCharges;
  BlockPos mTargetCrop;
  BlockPos mLastGrownCrop;
};

```

### `GenericMoveControl`
```
struct __cppobj GenericMoveControl : MoveControl
{
};

```

### `GenericMoveControl_vtbl`
```
struct /*VFT*/ GenericMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `GlideMoveControl`
```
struct __cppobj __declspec(align(8)) GlideMoveControl : MoveControl
{
  float mSpeed;
  float mStartSpeed;
  float mSpeedWhenTurning;
};

```

### `GlideMoveControl_vtbl`
```
struct /*VFT*/ GlideMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `GenericPathNavigation`
```
struct __cppobj GenericPathNavigation : PathNavigation
{
};

```

### `GenericPathNavigation_vtbl`
```
struct /*VFT*/ GenericPathNavigation_vtbl
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

### `GoalSelectorSystem`
```
struct __cppobj GoalSelectorSystem : ITickingSystem
{
};

```

### `GoalSelectorSystem_vtbl`
```
struct /*VFT*/ GoalSelectorSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `GroupSizeSystem`
```
struct __cppobj GroupSizeSystem : ITickingSystem
{
};

```

### `GroupSizeSystem_vtbl`
```
struct /*VFT*/ GroupSizeSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `GrowCropSystem`
```
struct __cppobj GrowCropSystem : ITickingSystem
{
};

```

### `GrowCropSystem_vtbl`
```
struct /*VFT*/ GrowCropSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `getDeviceIDPlatformMap::__l2::<lambda_9d9ceb45bedb17ac6e5739c9be0df8c7>`
```
struct __cppobj getDeviceIDPlatformMap::__l2::<lambda_9d9ceb45bedb17ac6e5739c9be0df8c7>
{
  std::map<std::string,int> *currentDeviceIds;
};

```

### `GameControllerHandler_Windows::{ctor}::__l2::<lambda_b8cec19ea8b9b774b34d04142bcb279b>`
```
struct __cppobj GameControllerHandler_Windows::{ctor}::__l2::<lambda_b8cec19ea8b9b774b34d04142bcb279b>
{
  GameControllerHandler_Windows *const __this;
};

```

### `GameSpecificPacketHandlerDispatcherInstance<ResourcePackClientResponsePacket,0>`
```
struct __cppobj GameSpecificPacketHandlerDispatcherInstance<ResourcePackClientResponsePacket,0> : IPacketHandlerDispatcher
{
};

```

### `GameSpecificPacketHandlerDispatcherInstance<ResourcePackClientResponsePacket,0>_vtbl`
```
struct /*VFT*/ GameSpecificPacketHandlerDispatcherInstance<ResourcePackClientResponsePacket,0>_vtbl
{
  void (__fastcall *~IPacketHandlerDispatcher)(IPacketHandlerDispatcher *this);
  void (__fastcall *handle)(IPacketHandlerDispatcher *this, const NetworkIdentifier *, NetEventCallback *, std::shared_ptr<Packet> *);
};

```

### `GetChunkDataCommand`
```
struct __cppobj GetChunkDataCommand : Command
{
  AutomaticID<Dimension,int> mDimension;
  int mChunkX;
  int mChunkZ;
  int mHeight;
};

```

### `GetChunkDataCommand_vtbl`
```
struct /*VFT*/ GetChunkDataCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GetChunksCommand`
```
struct __cppobj __declspec(align(8)) GetChunksCommand : Command
{
  AutomaticID<Dimension,int> mDimension;
};

```

### `GetChunksCommand_vtbl`
```
struct /*VFT*/ GetChunksCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GetSpawnPointCommand`
```
struct __cppobj GetSpawnPointCommand : Command
{
  CommandSelector<Player> mTargets;
};

```

### `GetSpawnPointCommand_vtbl`
```
struct /*VFT*/ GetSpawnPointCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GlobalPauseCommand`
```
struct __cppobj __declspec(align(8)) GlobalPauseCommand : ServerCommand
{
  bool mPause;
  bool mPauseSet;
};

```

### `GlobalPauseCommand_vtbl`
```
struct /*VFT*/ GlobalPauseCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GameModeCommand`
```
struct __cppobj GameModeCommand : Command
{
  CommandSelector<Player> mPlayers;
  GameType mGameMode;
  int mGameModeNumber;
};

```

### `GameModeCommand_vtbl`
```
struct /*VFT*/ GameModeCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GameRuleCommand`
```
struct __cppobj __declspec(align(8)) GameRuleCommand : Command
{
  std::string mGameRule;
  float mFloatValue;
  int mIntValue;
  bool mBoolValue;
  bool mBoolValueSet;
  bool mIntValueSet;
  bool mFloatValueSet;
};

```

### `GameRuleCommand_vtbl`
```
struct /*VFT*/ GameRuleCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GetTopSolidBlockCommand`
```
struct __cppobj GetTopSolidBlockCommand : Command
{
  CommandPosition mPosition;
};

```

### `GetTopSolidBlockCommand_vtbl`
```
struct /*VFT*/ GetTopSolidBlockCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GiveCommand`
```
struct __cppobj __declspec(align(8)) GiveCommand : Command
{
  CommandSelector<Player> mTargets;
  CommandItem mItem;
  int mCount;
  int mData;
  Json::Value mComponents;
  bool mHaveComponents;
};

```

### `GiveCommand_vtbl`
```
struct /*VFT*/ GiveCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GameRuleCommand::setGameRule::__l60::<lambda_e29830c2fb8e8c9d7d4a6df2a148f9fe>`
```
struct __cppobj GameRuleCommand::setGameRule::__l60::<lambda_e29830c2fb8e8c9d7d4a6df2a148f9fe>
{
  std::string *message;
  std::vector<std::string> *params;
};

```

### `GLBHeader`
```
struct __cppobj GLBHeader
{
  unsigned int magic;
  unsigned int version;
  unsigned int length;
};

```

### `GLBChunkInfo`
```
struct __cppobj GLBChunkInfo
{
  unsigned int length;
  unsigned int type;
};

```

### `gz_header_s`
```
struct __declspec(align(8)) gz_header_s
{
  int text;
  unsigned int time;
  int xflags;
  int os;
  unsigned __int8 *extra;
  unsigned int extra_len;
  unsigned int extra_max;
  unsigned __int8 *name;
  unsigned int name_max;
  unsigned __int8 *comment;
  unsigned int comm_max;
  int hcrc;
  int done;
};

```

### `GroundOffsetDefinition`
```
struct __cppobj GroundOffsetDefinition
{
  float mValue;
};

```

### `GetInteractionPositionForBlockNode`
```
struct __cppobj GetInteractionPositionForBlockNode : BehaviorNode
{
  BlockPos mTargetBlockPos;
  BlockPos mAnchorBlockPos;
  Facing::Name mFacing;
  int mMaxSearchDistance;
};

```

### `GetInteractionPositionForBlockNode_vtbl`
```
struct /*VFT*/ GetInteractionPositionForBlockNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `GetInteractionPositionForBlockDefinition`
```
struct __cppobj GetInteractionPositionForBlockDefinition : BehaviorDefinition
{
  BlockPos mTargetBlockPos;
  std::string mTargetBlockPosId;
  BlockPos mAnchorBlockPos;
  std::string mAnchorBlockPosId;
  std::string mFacingString;
  std::string mFacingStringId;
  int mMaxSearchDistance;
  std::string mMaxSearchDistanceId;
};

```

### `GetInteractionPositionForBlockDefinition_vtbl`
```
struct /*VFT*/ GetInteractionPositionForBlockDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `GoalDebugInfo`
```
struct __cppobj GoalDebugInfo
{
  int mPriority;
  std::string mName;
  bool mUsed;
  int mControlFlag;
};

```

### `Ghast`
```
struct __cppobj Ghast : Monster
{
};

```

### `Guardian::aiStep::__l8::<lambda_c04beb0effafeac5fa454435c97fc819>`
```
struct __cppobj Guardian::aiStep::__l8::<lambda_c04beb0effafeac5fa454435c97fc819>
{
  Guardian *const __this;
  MobEffect **effect;
  float *effectDuration;
  float *effectAmplifier;
  float *displayEffectLimit;
};

```

### `Guardian::registerLoopingSounds::__l2::<lambda_83e3d6fea4135d64957b9de8952f48cc>`
```
struct __cppobj Guardian::registerLoopingSounds::__l2::<lambda_83e3d6fea4135d64957b9de8952f48cc>
{
  Guardian *const __this;
};

```

### `GameMode::releaseUsingItem::__l2::<lambda_944ec8a292c093bb087e137349816e8e>`
```
struct __cppobj GameMode::releaseUsingItem::__l2::<lambda_944ec8a292c093bb087e137349816e8e>
{
  GameMode *const __this;
  ItemStack *item;
  std::unique_ptr<ItemReleaseInventoryTransaction> *transaction;
};

```

### `GameMode::releaseUsingItem::__l2::<lambda_bbf2b0cb09f1a93163e00e1c2d679c4a>`
```
struct __cppobj GameMode::releaseUsingItem::__l2::<lambda_bbf2b0cb09f1a93163e00e1c2d679c4a>
{
  GameMode *const __this;
  std::unique_ptr<ItemReleaseInventoryTransaction> *transaction;
};

```

### `GameMode::baseUseItem::__l2::<lambda_a792a9e763d98111862b866f2e963cd2>`
```
struct __cppobj GameMode::baseUseItem::__l2::<lambda_a792a9e763d98111862b866f2e963cd2>
{
  GameMode *const __this;
  ItemStack *item;
  std::unique_ptr<ItemUseInventoryTransaction> *transaction;
  bool *success;
};

```

### `GameMode::baseUseItem::__l2::<lambda_de3982cfce540930dc77b3b571b31280>`
```
struct __cppobj GameMode::baseUseItem::__l2::<lambda_de3982cfce540930dc77b3b571b31280>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseInventoryTransaction> *transaction;
};

```

### `GameMode::buildBlock::__l2::<lambda_61fa6c72fdeab3a1a4cb49807d59e8f4>`
```
struct __cppobj __declspec(align(8)) GameMode::buildBlock::__l2::<lambda_61fa6c72fdeab3a1a4cb49807d59e8f4>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseInventoryTransaction> *transaction;
  bool *success;
  const BlockPos *pos;
  unsigned __int8 face;
};

```

### `GameMode::buildBlock::__l2::<lambda_ed7fd04181d96367dab230a6e17f8331>`
```
struct __cppobj GameMode::buildBlock::__l2::<lambda_ed7fd04181d96367dab230a6e17f8331>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseInventoryTransaction> *transaction;
};

```

### `GameMode::continueDestroyBlock::__l70::<lambda_e9c69802ff74493b49da49ac6ffbbe07>`
```
struct __cppobj GameMode::continueDestroyBlock::__l70::<lambda_e9c69802ff74493b49da49ac6ffbbe07>
{
  const BlockPos *pos;
  const Block *block;
  GameMode *const __this;
};

```

### `GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>`
```
struct __cppobj __declspec(align(8)) GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>
{
  GameMode *const __this;
  const BlockPos *pos;
  unsigned __int8 face;
  bool particle;
};

```

### `GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>::()::__l19::<lambda_1b1a5dec59d48e30d83907ee88bf0345>`
```
struct __cppobj GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>::()::__l19::<lambda_1b1a5dec59d48e30d83907ee88bf0345>
{
  const BlockPos *pos;
  const unsigned __int8 *face;
  const Block *block;
  const CompoundTag *dataID;
  GameMode *const __this;
  bool *cancel;
};

```

### `GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>::()::__l11::<lambda_ee35285b100f016e7c1238f16bf9654b>`
```
struct __cppobj GameMode::destroyBlock::__l2::<lambda_2efbd0477cf3d3d4cafe4f6650dc7dd0>::()::__l11::<lambda_ee35285b100f016e7c1238f16bf9654b>
{
  const BlockPos *pos;
  const unsigned __int8 *face;
  const Block *block;
  const CompoundTag *dataID;
  GameMode *const __this;
  bool *cancel;
  bool *spawnResources;
};

```

### `GameMode::startDestroyBlock::__l16::<lambda_1226b86775516d17692f5a9e58eac3f9>`
```
struct __cppobj GameMode::startDestroyBlock::__l16::<lambda_1226b86775516d17692f5a9e58eac3f9>
{
  const BlockPos *pos;
  const Block *block;
  GameMode *const __this;
};

```

### `GameMode::attack::__l2::<lambda_b0cd2bf1dd2aaa6c8cc5f2dad8034e2c>`
```
struct __cppobj GameMode::attack::__l2::<lambda_b0cd2bf1dd2aaa6c8cc5f2dad8034e2c>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseOnActorInventoryTransaction> *transaction;
  Actor *entity;
  bool *success;
};

```

### `GameMode::attack::__l2::<lambda_60cb0d4d5046b736b1111d35e6841024>`
```
struct __cppobj GameMode::attack::__l2::<lambda_60cb0d4d5046b736b1111d35e6841024>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseOnActorInventoryTransaction> *transaction;
};

```

### `GameMode::interact::__l2::<lambda_c20dbf30e3c2e03c7de1ea39feb139d8>`
```
struct __cppobj GameMode::interact::__l2::<lambda_c20dbf30e3c2e03c7de1ea39feb139d8>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseOnActorInventoryTransaction> *transaction;
  bool *success;
  Actor *entity;
  const Vec3 *location;
};

```

### `GameMode::interact::__l2::<lambda_83582d04c2cd5ad2b67fa4c9b264dfc0>`
```
struct __cppobj GameMode::interact::__l2::<lambda_83582d04c2cd5ad2b67fa4c9b264dfc0>
{
  GameMode *const __this;
  std::unique_ptr<ItemUseOnActorInventoryTransaction> *transaction;
};

```

### `GlowStickItem`
```
struct __cppobj GlowStickItem : ChemistryStickItem
{
  std::unique_ptr<BlockItem> mBlockItem;
};

```

### `glm::detail::compute_vec4_add<int,0,0>`
```
struct __cppobj glm::detail::compute_vec4_add<int,0,0>
{
};

```

### `glm::detail::compute_vec4_sub<int,0,0>`
```
struct __cppobj glm::detail::compute_vec4_sub<int,0,0>
{
};

```

### `glm::detail::compute_vec4_div<int,0,0>`
```
struct __cppobj glm::detail::compute_vec4_div<int,0,0>
{
};

```

### `GlassBlock`
```
struct __cppobj __declspec(align(8)) GlassBlock : BlockLegacy
{
  bool mDoesDrops;
  bool mCanBeUsedInCommands;
};

```

### `GlassBlock_vtbl`
```
struct /*VFT*/ GlassBlock_vtbl
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

### `GlazedTerracottaBlock`
```
struct __cppobj GlazedTerracottaBlock : FaceDirectionalBlock
{
};

```

### `GlazedTerracottaBlock_vtbl`
```
struct /*VFT*/ GlazedTerracottaBlock_vtbl
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

### `GrassPathBlock`
```
struct __cppobj GrassPathBlock : BlockLegacy
{
};

```

### `GrassPathBlock_vtbl`
```
struct /*VFT*/ GrassPathBlock_vtbl
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

### `GravelBlock`
```
struct __cppobj GravelBlock : HeavyBlock
{
};

```

### `GravelBlock_vtbl`
```
struct /*VFT*/ GravelBlock_vtbl
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

### `GrindstoneBlock`
```
struct __cppobj GrindstoneBlock : BlockLegacy
{
};

```

### `GrindstoneBlock_vtbl`
```
struct /*VFT*/ GrindstoneBlock_vtbl
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

### `glm::detail::compute_inverse<glm::tmat3x3,float,0,0>`
```
struct __cppobj glm::detail::compute_inverse<glm::tmat3x3,float,0,0>
{
};

```

### `GroundedConstraint`
```
struct __cppobj GroundedConstraint : IStructureConstraint
{
  std::vector<BlockPos> mFoundationOffsets;
};

```

### `GroundedConstraint_vtbl`
```
struct /*VFT*/ GroundedConstraint_vtbl
{
  void (__fastcall *~IStructureConstraint)(IStructureConstraint *this);
  bool (__fastcall *isSatisfied)(IStructureConstraint *this, const IBlockWorldGenAPI *, const BlockPos *, const Rotation *);
};

```

### `GameRules::_registerRules::__l2::<lambda_46c110ed8eb7cf6c694ceaf63c3ecf8f>`
```
struct __cppobj GameRules::_registerRules::__l2::<lambda_46c110ed8eb7cf6c694ceaf63c3ecf8f>
{
};

```

### `GameRules::_registerRules::__l2::<lambda_1746da2b58e39dd7ab36c4827f73812d>`
```
struct __cppobj GameRules::_registerRules::__l2::<lambda_1746da2b58e39dd7ab36c4827f73812d>
{
  GameRules::_registerRules::__l2::<lambda_46c110ed8eb7cf6c694ceaf63c3ecf8f> validateRange;
};

```

### `GameRules::_registerRules::__l2::<lambda_39f66fc7a080e290ce7239101ccb1236>`
```
struct __cppobj GameRules::_registerRules::__l2::<lambda_39f66fc7a080e290ce7239101ccb1236>
{
  GameRules::_registerRules::__l2::<lambda_46c110ed8eb7cf6c694ceaf63c3ecf8f> validateRange;
};

```

### `GameRules::_registerRules::__l2::<lambda_0dd1d4277bac2e2ee5e982c075a30d01>`
```
struct __cppobj GameRules::_registerRules::__l2::<lambda_0dd1d4277bac2e2ee5e982c075a30d01>
{
  GameRules::_registerRules::__l2::<lambda_46c110ed8eb7cf6c694ceaf63c3ecf8f> validateRange;
};

```

### `GameRules::_registerRules::__l2::<lambda_7b996cf19c32ca65eb7b73792d338595>`
```
struct __cppobj GameRules::_registerRules::__l2::<lambda_7b996cf19c32ca65eb7b73792d338595>
{
};

```

### `getServerTag::__l2::<lambda_6ebc7fae7302c64d5a346c415ff588cf>`
```
struct __cppobj getServerTag::__l2::<lambda_6ebc7fae7302c64d5a346c415ff588cf>
{
  LevelStorage *storage;
  std::string *loadedFromTagName;
  std::unique_ptr<CompoundTag> *serverTag;
};

```

### `glm::detail::compute_dot<glm::tquat,double,0,0>`
```
struct __cppobj glm::detail::compute_dot<glm::tquat,double,0,0>
{
};

```

### `glm::detail::storage<double,32,0>`
```
struct __cppobj glm::detail::storage<double,32,0>
{
};

```

### `glm::detail::compute_transpose<glm::tmat3x4,float,0,0>`
```
struct __cppobj glm::detail::compute_transpose<glm::tmat3x4,float,0,0>
{
};

```

### `gladGLversionStruct`
```
struct gladGLversionStruct
{
  int major;
  int minor;
};

```

### `GetDurabilityCommand`
```
struct __cppobj GetDurabilityCommand : ClientCommand
{
};

```

### `GetDurabilityCommand_vtbl`
```
struct /*VFT*/ GetDurabilityCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `GrindstoneContainerManagerModel`
```
struct __cppobj __declspec(align(8)) GrindstoneContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `GrindstoneContainerManagerModel_vtbl`
```
struct /*VFT*/ GrindstoneContainerManagerModel_vtbl
{
  void (__fastcall *~IContainerManager)(IContainerManager *this);
  ContainerID (__fastcall *getContainerId)(IContainerManager *this);
  void (__fastcall *setContainerId)(IContainerManager *this, ContainerID);
  ContainerType (__fastcall *getContainerType)(IContainerManager *this);
  void (__fastcall *setContainerType)(IContainerManager *this, ContainerType);
  void (__fastcall *serverInitItemStackIds)(IContainerManager *this);
  std::vector<ItemStack> *(__fastcall *getItemCopies)(IContainerManager *this, std::vector<ItemStack> *result);
  void (__fastcall *setSlot)(IContainerManager *this, int, const ItemStack *, bool);
  const ItemStack *(__fastcall *getSlot)(IContainerManager *this, int);
  void (__fastcall *setData)(IContainerManager *this, int, int);
  void (__fastcall *broadcastChanges)(IContainerManager *this);
  bool (__fastcall *validateContainer)(IContainerManager *this);
  bool (__fastcall *isValid)(ContainerManagerModel *this, float);
  ContainerScreenContext *(__fastcall *_postInit)(ContainerManagerModel *this, ContainerScreenContext *result);
};

```

### `GrindstoneContainerManagerController`
```
struct __cppobj GrindstoneContainerManagerController : ContainerManagerController
{
  std::weak_ptr<GrindstoneContainerManagerModel> mGrindstoneContainerManagerModel;
  const SlotData mCreatedItemOutputSlot;
  ItemInstance mResultItemPreview;
};

```

### `GrindstoneContainerManagerController_vtbl`
```
struct /*VFT*/ GrindstoneContainerManagerController_vtbl
{
  void (__fastcall *~ContainerManagerController)(ContainerManagerController *this);
  void (__fastcall *registerContainerCallbacks)(ContainerManagerController *this);
  const ItemStackBase *(__fastcall *getTakeableItemStackBase)(ContainerManagerController *this, const SlotData *);
  void (__fastcall *handleTakeAmount)(ContainerManagerController *this, const SlotData *, int, const SlotData *);
  void (__fastcall *handleTakeAll)(ContainerManagerController *this, const SlotData *, const SlotData *);
  void (__fastcall *handlePlaceAll)(ContainerManagerController *this, const SelectedSlotInfo *, const SlotData *);
  void (__fastcall *handleTakeHalf)(ContainerManagerController *this, const SlotData *, const SlotData *);
  void (__fastcall *handlePlaceOne)(ContainerManagerController *this, const SlotData *, const SlotData *);
  void (__fastcall *handlePlaceAmount)(ContainerManagerController *this, const SlotData *, int, const SlotData *);
  int (__fastcall *handleAutoPlace)(ContainerManagerController *this, const SlotData *, int, const std::vector<AutoPlaceItem> *, std::vector<AutoPlaceResult> *);
  int (__fastcall *handleAutoPlaceStack)(ContainerManagerController *this, const SlotData *, ItemTakeType, const std::vector<AutoPlaceItem> *, std::vector<AutoPlaceResult> *);
  void (__fastcall *handleSplitSingle)(ContainerManagerController *this, const SlotData *, const SlotData *);
  void (__fastcall *handleSplitMultiple)(ContainerManagerController *this, const SelectedSlotInfo *, const ItemInstance *, const SlotData *);
  void (__fastcall *handleCoalesce)(ContainerManagerController *this, const SlotData *, const std::vector<std::string> *);
  bool (__fastcall *handleSwap)(ContainerManagerController *this, const SlotData *, const SlotData *);
  bool (__fastcall *handleDrop)(ContainerManagerController *this, const SlotData *, const ItemTransferAmount);
  bool (__fastcall *handleDestroy)(ContainerManagerController *this, const SlotData *, const ItemTransferAmount);
  bool (__fastcall *handleDestroy)(ContainerManagerController *this, const SelectedSlotInfo *, const ItemTransferAmount);
  bool (__fastcall *handleConsume)(ContainerManagerController *this, const SlotData *, const ItemTransferAmount);
  void (__fastcall *handleAddToStack)(ContainerManagerController *this, const SlotData *, const SlotData *, ItemTakeType);
  void (__fastcall *closeContainers)(ContainerManagerController *this);
  const std::vector<ContainerSplitControl> *(__fastcall *getSplitItems)(ContainerManagerController *this);
  bool (__fastcall *isOutputSlot)(ContainerManagerController *this, const std::string *);
  void (__fastcall *_onItemTransferredFrom)(ContainerManagerController *this, const ItemInstance *, const SlotData *);
  void (__fastcall *_onItemTransferredTo)(ContainerManagerController *this, const ItemInstance *, const SlotData *);
  void (__fastcall *_onItemAcquired)(ContainerManagerController *this, const ItemInstance *, const SlotData *);
  void (__fastcall *_onItemPlaced)(ContainerManagerController *this, const ItemInstance *, const SlotData *);
};

```

### `GrindstoneScreenController`
```
struct __cppobj __declspec(align(8)) GrindstoneScreenController : ContainerScreenController
{
  std::shared_ptr<GrindstoneContainerManagerController> mGrindstoneContainerManagerController;
  GrindstoneScreenController::SlotIndex mHoveredSlot;
};

```

### `GrindstoneScreenController_vtbl`
```
struct /*VFT*/ GrindstoneScreenController_vtbl
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
  void (__fastcall *_handlePlaceAll)(ContainerScreenController *this, const std::string *, int);
  void (__fastcall *_handlePlaceOne)(ContainerScreenController *this, const std::string *, int);
  void (__fastcall *_handleSelectSlot)(ContainerScreenController *this, const std::string *, int);
  const SelectedSlotInfo *(__fastcall *_getSelectedSlotInfo)(ContainerScreenController *this, const SelectedSlotInfo *result);
  const ItemStack *(__fastcall *_getItemStack)(ContainerScreenController *this, const std::string *, int);
  const ItemStackBase *(__fastcall *_getVisualItemStack)(ContainerScreenController *this, const std::string *, int);
  const ItemStackBase *(__fastcall *_getTakeableItemStackBase)(ContainerScreenController *this, const std::string *, int);
  ui::ViewRequest (__fastcall *_onContainerSlotHovered)(ContainerScreenController *this, const std::string *, int);
  ui::ViewRequest (__fastcall *_onContainerSlotSelected)(ContainerScreenController *this, const std::string *, int);
  ui::ViewRequest (__fastcall *_onContainerSlotPressed)(ContainerScreenController *this, const std::string *, int);
  bool (__fastcall *_shouldSwap)(ContainerScreenController *this, const std::string *, int, const std::string *, int);
  std::string *(__fastcall *_getCollectionName)(ContainerScreenController *this, std::string *result, UIPropertyBag *);
  bool (__fastcall *_canSplit)(ContainerScreenController *this, const std::string *, int);
  void (__fastcall *_sendFlyingItem)(ContainerScreenController *this, const ItemStackBase *, const std::string *, int, const std::string *, int);
  void (__fastcall *_registerCoalesceOrder)(ContainerScreenController *this);
  void (__fastcall *_registerAutoPlaceOrder)(ContainerScreenController *this);
};

```

### `GrindstoneScreenController::_registerStateMachine::__l2::<lambda_193a5639ee08738a51616e204f1017d6>`
```
struct __cppobj GrindstoneScreenController::_registerStateMachine::__l2::<lambda_193a5639ee08738a51616e204f1017d6>
{
  unsigned int grindstoneTakeAllPlaceAllButtonId;
  unsigned int grindstoneCoalesceButtonId;
};

```

### `GrindstoneScreenController::_registerStateMachine::__l2::<lambda_7b701450e267196c795ddb3586a80b21>`
```
struct __cppobj GrindstoneScreenController::_registerStateMachine::__l2::<lambda_7b701450e267196c795ddb3586a80b21>
{
  unsigned int grindstoneTakeAllPlaceAllButtonId;
  unsigned int grindstoneCoalesceButtonId;
};

```

### `GrindstoneScreenController::_registerStateMachine::__l2::<lambda_e253d3b02173cb9cd49fdc17146864df>`
```
struct __cppobj GrindstoneScreenController::_registerStateMachine::__l2::<lambda_e253d3b02173cb9cd49fdc17146864df>
{
  GrindstoneScreenController *const __this;
  unsigned int grindstoneTakeAllPlaceAllButtonId;
  unsigned int grindstoneCoalesceButtonId;
};

```

### `GrindstoneScreenController::_registerStateMachine::__l2::<lambda_8a175739216272854736b178dbc11c80>`
```
struct __cppobj GrindstoneScreenController::_registerStateMachine::__l2::<lambda_8a175739216272854736b178dbc11c80>
{
  GrindstoneScreenController *const __this;
  unsigned int grindstoneTakeAllPlaceAllButtonId;
  unsigned int grindstoneCoalesceButtonId;
};

```

### `GrindstoneScreenController::_registerBindings::__l2::<lambda_c6330d907d4cfff9afb7cee6292a6dcb>`
```
struct __cppobj GrindstoneScreenController::_registerBindings::__l2::<lambda_c6330d907d4cfff9afb7cee6292a6dcb>
{
  GrindstoneScreenController *const __this;
};

```

### `GoHomeGoal`
```
struct __cppobj __declspec(align(8)) GoHomeGoal : Goal
{
  Mob *mMob;
  float mSpeedMod;
  int mInterval;
  float mGoalRadius;
  const std::vector<DefinitionTrigger> mOnHomeTriggers;
  const std::vector<DefinitionTrigger> mOnFailedTriggers;
  BlockPos mLastEndPos;
};

```

### `GoHomeGoal_vtbl`
```
struct /*VFT*/ GoHomeGoal_vtbl
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

### `GuardianAttackDefinition`
```
struct __cppobj __declspec(align(8)) GuardianAttackDefinition : BaseGoalDefinition
{
  int mMagicDamage;
  int mHardModeExtraMagicDamage;
  int mElderExtraMagicDamage;
  float mMaxRotationX;
  float mMaxHeadRotationY;
  float mMinDistance;
  float mSoundDelayTime;
};

```

### `GuardianAttackDefinition_vtbl`
```
struct /*VFT*/ GuardianAttackDefinition_vtbl
{
  void (__fastcall *~BaseGoalDefinition)(BaseGoalDefinition *this);
  bool (__fastcall *validateMobType)(BaseGoalDefinition *this, Mob *);
  bool (__fastcall *validate)(BaseGoalDefinition *this, Mob *);
};

```

### `GuardianAttackGoal`
```
struct __cppobj GuardianAttackGoal : Goal
{
  Guardian *mGuardian;
  int mAttackTicks;
  int mSoundDelayTicks;
  int mMagicDamage;
  int mHardModeExtraMagicDamage;
  int mElderExtraMagicDamage;
  float mMaxRotationX;
  float mMaxHeadRotationY;
  float mMinDistance;
};

```

### `GuardianAttackGoal_vtbl`
```
struct /*VFT*/ GuardianAttackGoal_vtbl
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

### `GrindstoneContainerManagerController::_setupCallbacks::__l2::<lambda_082e2a09e34ad40063a67288885e972e>`
```
struct __cppobj GrindstoneContainerManagerController::_setupCallbacks::__l2::<lambda_082e2a09e34ad40063a67288885e972e>
{
  GrindstoneContainerManagerController *const __this;
};

```

### `GrindstoneContainerManagerController::_setupCallbacks::__l2::<lambda_dc10b45092a06085eed47e2fde8f46f6>`
```
struct __cppobj GrindstoneContainerManagerController::_setupCallbacks::__l2::<lambda_dc10b45092a06085eed47e2fde8f46f6>
{
  GrindstoneContainerManagerController *const __this;
};

```

### `GridPos`
```
struct GridPos
{
  int x;
  int z;
};

```

### `GlowStoneFeature_vtbl`
```
struct /*VFT*/ GlowStoneFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `GGDevice`
```
struct __cppobj GGDevice
{
  std::queue<PlatformGestureEvent> mGestureEventVector;
};

```

### `GGVDeviceManager`
```
struct __cppobj GGVDeviceManager
{
};

```

### `GridSectorizer`
```
struct __cppobj GridSectorizer
{
  float cellOriginX;
  float cellOriginY;
  float cellWidth;
  float cellHeight;
  float invCellWidth;
  float invCellHeight;
  float gridWidth;
  float gridHeight;
  int gridCellWidthCount;
  int gridCellHeightCount;
  DataStructures::List<void *> *grid;
};

```

### `gzFile_s`
```
struct gzFile_s
{
  unsigned int have;
  unsigned __int8 *next;
  __int64 pos;
};

```

### `gz_state`
```
struct gz_state
{
  gzFile_s x;
  int mode;
  int fd;
  char *path;
  unsigned int size;
  unsigned int want;
  unsigned __int8 *in;
  unsigned __int8 *out;
  int direct;
  int how;
  __int64 start;
  int eof;
  int past;
  int level;
  int strategy;
  __int64 skip;
  int seek;
  int err;
  char *msg;
  z_stream_s strm;
};

```

### `GX_AVarCorrespondenceRec_`
```
struct GX_AVarCorrespondenceRec_
{
  int fromCoord;
  int toCoord;
};

```

### `GX_AVarSegmentRec_`
```
struct GX_AVarSegmentRec_
{
  unsigned __int16 pairCount;
  GX_AVarCorrespondenceRec_ *correspondence;
};

```

### `GX_ItemVarDataRec_`
```
struct GX_ItemVarDataRec_
{
  unsigned int itemCount;
  unsigned int regionIdxCount;
  unsigned int *regionIndices;
  __int16 *deltaSet;
};

```

### `GX_AxisCoordsRec_`
```
struct GX_AxisCoordsRec_
{
  int startCoord;
  int peakCoord;
  int endCoord;
};

```

### `GX_VarRegionRec_`
```
struct GX_VarRegionRec_
{
  GX_AxisCoordsRec_ *axisList;
};

```

### `GX_ItemVarStoreRec_`
```
struct GX_ItemVarStoreRec_
{
  unsigned int dataCount;
  GX_ItemVarDataRec_ *varData;
  unsigned __int16 axisCount;
  unsigned int regionCount;
  GX_VarRegionRec_ *varRegionList;
};

```

### `GX_DeltaSetIdxMapRec_`
```
struct GX_DeltaSetIdxMapRec_
{
  unsigned int mapCount;
  unsigned int *outerIndex;
  unsigned int *innerIndex;
};

```

### `GX_HVVarTableRec_`
```
struct GX_HVVarTableRec_
{
  GX_ItemVarStoreRec_ itemStore;
  GX_DeltaSetIdxMapRec_ widthMap;
};

```

### `GX_ValueRec_`
```
struct __declspec(align(4)) GX_ValueRec_
{
  unsigned int tag;
  unsigned __int16 outerIndex;
  unsigned __int16 innerIndex;
  __int16 unmodified;
};

```

### `GX_MVarTableRec_`
```
struct GX_MVarTableRec_
{
  unsigned __int16 valueCount;
  GX_ItemVarStoreRec_ itemStore;
  GX_ValueRec_ *values;
};

```

### `GX_BlendRec_`
```
struct __declspec(align(8)) GX_BlendRec_
{
  unsigned int num_axis;
  int *coords;
  int *normalizedcoords;
  FT_MM_Var_ *mmvar;
  unsigned __int64 mmvar_len;
  int *normalized_stylecoords;
  unsigned __int8 avar_loaded;
  GX_AVarSegmentRec_ *avar_segment;
  unsigned __int8 hvar_loaded;
  unsigned __int8 hvar_checked;
  int hvar_error;
  GX_HVVarTableRec_ *hvar_table;
  unsigned __int8 vvar_loaded;
  unsigned __int8 vvar_checked;
  int vvar_error;
  GX_HVVarTableRec_ *vvar_table;
  GX_MVarTableRec_ *mvar_table;
  unsigned int tuplecount;
  int *tuplecoords;
  unsigned int gv_glyphcnt;
  unsigned int *glyphoffsets;
  unsigned int gvar_size;
};

```

### `gray_TRaster_`
```
struct gray_TRaster_
{
  void *memory;
};

```

### `GX_GVar_Head_`
```
struct GX_GVar_Head_
{
  int version;
  unsigned __int16 axisCount;
  unsigned __int16 globalCoordCount;
  unsigned int offsetToCoord;
  unsigned __int16 glyphCount;
  unsigned __int16 flags;
  unsigned int offsetToData;
};

```

### `GX_FVar_Head_`
```
struct __declspec(align(4)) GX_FVar_Head_
{
  int version;
  unsigned __int16 offsetToData;
  unsigned __int16 axisCount;
  unsigned __int16 axisSize;
  unsigned __int16 instanceCount;
  unsigned __int16 instanceSize;
};

```

### `groupbyobject`
```
struct groupbyobject
{
  __int64 ob_refcnt;
  _typeobject *ob_type;
  _object *it;
  _object *keyfunc;
  _object *tgtkey;
  _object *currkey;
  _object *currvalue;
};

```

### `GroupGenerator`
```
struct GroupGenerator
{
  const char *grouping;
  char previous;
  __int64 i;
};

```

### `GameArguments::_onUri::__l2::<lambda_ce112b18e67df44d9cdddd0f3e0798c5>`
```
struct __cppobj GameArguments::_onUri::__l2::<lambda_ce112b18e67df44d9cdddd0f3e0798c5>
{
  ResourcePackRepository *resourcePackRepository;
  ResourcePackManager *resourcePackManager;
  WorldTemplateManager *worldTemplateManager;
  IMinecraftEventing *eventing;
  ToastManager *toastManager;
  Core::PathBuffer<Core::StackString<char,1024> > *originalPath;
};

```

### `GuiData::clearPlayerMessages::__l2::<lambda_5077aa398c0ccdf80b4fc4d4eb96ad8d>`
```
struct __cppobj GuiData::clearPlayerMessages::__l2::<lambda_5077aa398c0ccdf80b4fc4d4eb96ad8d>
{
};

```

### `GeneralSettingsScreenController::_initLanguageList::__l2::<lambda_a8cd0aa405ba0ad7240ec7063a91f5bd>`
```
struct __cppobj GeneralSettingsScreenController::_initLanguageList::__l2::<lambda_a8cd0aa405ba0ad7240ec7063a91f5bd>
{
  const std::string *currentLanguageCode;
};

```

### `GeneralSettingsScreenController::addStaticScreenVars::__l2::<lambda_029cc549430946d6ebc8c9998ff381c3>`
```
struct __cppobj GeneralSettingsScreenController::addStaticScreenVars::__l2::<lambda_029cc549430946d6ebc8c9998ff381c3>
{
  BuildPlatform buildPlatform;
};

```

### `GeneralSettingsScreenController::addStaticScreenVars::__l2::<lambda_e6f6b03b054ec5b7cbd2eb66ebf60c8d>`
```
struct __cppobj GeneralSettingsScreenController::addStaticScreenVars::__l2::<lambda_e6f6b03b054ec5b7cbd2eb66ebf60c8d>
{
  BuildPlatform buildPlatform;
};

```

### `GamePadRemappingLayout::_swapGamepadKeyBindings::__l6::<lambda_b203e72b3aeff8c311f4cf5281e7dc64>`
```
struct __cppobj GamePadRemappingLayout::_swapGamepadKeyBindings::__l6::<lambda_b203e72b3aeff8c311f4cf5281e7dc64>
{
  int *key1;
  int *key2;
};

```

### `GameRenderer::removePlayerRenderView::__l2::<lambda_a2a54e7863b758c7adccfbcc608ca29d>`
```
struct __cppobj GameRenderer::removePlayerRenderView::__l2::<lambda_a2a54e7863b758c7adccfbcc608ca29d>
{
  PlayerRenderView *view;
};

```

### `GameRenderer::renderDebugScreen::__l24::<lambda_742f6ade1db35b018e2704242aef1a58>`
```
struct __cppobj GameRenderer::renderDebugScreen::__l24::<lambda_742f6ade1db35b018e2704242aef1a58>
{
  std::optional<dragon::platform::Statistics> *stats;
};

```

### `GoalSelectorComponent::clearTargetGoals::__l2::<lambda_78cc794fe5ea5bbb863cf9f65329d7ca>`
```
struct __cppobj GoalSelectorComponent::clearTargetGoals::__l2::<lambda_78cc794fe5ea5bbb863cf9f65329d7ca>
{
};

```

### `GoalSelectorComponent::clearNonTargetedGoals::__l2::<lambda_ca9b2df2e278cab2e6dbfd3a51079d17>`
```
struct __cppobj GoalSelectorComponent::clearNonTargetedGoals::__l2::<lambda_ca9b2df2e278cab2e6dbfd3a51079d17>
{
};

```

### `GoalSelectorComponent::_findGoalByKey::__l2::<lambda_226903ec9aef958acba5544cc6274638>`
```
struct __cppobj GoalSelectorComponent::_findGoalByKey::__l2::<lambda_226903ec9aef958acba5544cc6274638>
{
  unsigned __int16 key;
};

```

### `glTFExporter::_hasBuffer::__l2::<lambda_0b37021b49a90b609a183ab0035a7c39>`
```
struct __cppobj glTFExporter::_hasBuffer::__l2::<lambda_0b37021b49a90b609a183ab0035a7c39>
{
  int bufferID;
};

```

### `glTFExporter::updateBufferSize::__l2::<lambda_aa64259bded46ba9708890e6ee944f41>`
```
struct __cppobj glTFExporter::updateBufferSize::__l2::<lambda_aa64259bded46ba9708890e6ee944f41>
{
  int bufferID;
};

```

### `glTFExporter::getMaterialID::__l2::<lambda_7f311a0b6097e84757dac133aefc48a2>`
```
struct __cppobj glTFExporter::getMaterialID::__l2::<lambda_7f311a0b6097e84757dac133aefc48a2>
{
  const std::string materialName;
};

```

### `glTFExporter::_hasMaterial::__l2::<lambda_a4868ac304213b2c3cc40f860130b94e>`
```
struct __cppobj glTFExporter::_hasMaterial::__l2::<lambda_a4868ac304213b2c3cc40f860130b94e>
{
  const std::string materialName;
};

```

### `glTFExporter::addMaterial::__l10::<lambda_ba520a9d2810af9b9a66c789bbbf4168>`
```
struct __cppobj glTFExporter::addMaterial::__l10::<lambda_ba520a9d2810af9b9a66c789bbbf4168>
{
  const std::string materialName;
};

```

### `GoalDefinition::parse::__l2::<lambda_bb642b32e16a67ad66da9eb5422435cf>`
```
struct __cppobj GoalDefinition::parse::__l2::<lambda_bb642b32e16a67ad66da9eb5422435cf>
{
  GoalDefinition *const __this;
};

```

### `Ghast::updateEntitySpecificMolangVariables::__l2::<lambda_365546796e3c168742f42b3f07199f01>::()::__l2::Literal`
```
struct __cppobj Ghast::updateEntitySpecificMolangVariables::__l2::<lambda_365546796e3c168742f42b3f07199f01>::()::__l2::Literal
{
};

```

### `Ghast::updateEntitySpecificMolangVariables::__l2::<lambda_365546796e3c168742f42b3f07199f01>`
```
struct __cppobj Ghast::updateEntitySpecificMolangVariables::__l2::<lambda_365546796e3c168742f42b3f07199f01>
{
};

```

### `GameMode::continueDestroyBlock::__l16::<lambda_4f5c247bff61cae35be62f6a11cf86f2>`
```
struct __cppobj __declspec(align(8)) GameMode::continueDestroyBlock::__l16::<lambda_4f5c247bff61cae35be62f6a11cf86f2>
{
  GameMode *const __this;
  const BlockPos *pos;
  const bool isDestroyingAir;
  unsigned __int8 face;
};

```

### `GrindstoneContainerManagerController::_grantExperience::__l2::<lambda_fbb771b40e0f7c8be6dd6df0d96a53a5>`
```
struct __cppobj GrindstoneContainerManagerController::_grantExperience::__l2::<lambda_fbb771b40e0f7c8be6dd6df0d96a53a5>
{
};

```

### `GameController::_unregisterConsumer::__l5::<lambda_1228ff1e26e1cfb014a5da5fe5862d94>`
```
struct __cppobj GameController::_unregisterConsumer::__l5::<lambda_1228ff1e26e1cfb014a5da5fe5862d94>
{
  const void *token;
};

```

### `GameControllerMapper::handleConnectionStateChangedEvent::__l5::<lambda_fccbab4361d3b0eaebce6ee5ac6bdbcd>`
```
struct __cppobj GameControllerMapper::handleConnectionStateChangedEvent::__l5::<lambda_fccbab4361d3b0eaebce6ee5ac6bdbcd>
{
  int *controllerId;
};

```

### `GameController::_registerConsumer::__l2::<lambda_dbfb983aff22c77ae2a10346be44dde6>`
```
struct __cppobj GameController::_registerConsumer::__l2::<lambda_dbfb983aff22c77ae2a10346be44dde6>
{
  const void *token;
};

```

### `Ghast_vtbl`
```
struct /*VFT*/ Ghast_vtbl
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
  void (__fastcall *knockback)(Mob *this, Actor *, int, float, float, float, float, float);
  void (__fastcall *resolveDeathLoot)(Mob *this, int, const ActorDamageSource *);
  void (__fastcall *spawnAnim)(Mob *this);
  void (__fastcall *setSleeping)(Mob *this, bool);
  void (__fastcall *setSprinting)(Mob *this, bool);
  void (__fastcall *playAmbientSound)(Mob *this);
  LevelSoundEvent (__fastcall *getAmbientSound)(Mob *this);
  int (__fastcall *getAmbientSoundPostponeTicks)(Mob *this);
  int (__fastcall *getAmbientSoundPostponeTicksRange)(Mob *this);
  const TextureUVCoordinateSet *(__fastcall *getItemInHandIcon)(Mob *this, const ItemStack *, int);
  float (__fastcall *getSpeed)(Mob *this);
  void (__fastcall *setSpeed)(Mob *this, float);
  float (__fastcall *getJumpPower)(Mob *this);
  bool (__fastcall *hurtEffects)(Mob *this, const ActorDamageSource *, int, bool, bool);
  int (__fastcall *getMeleeWeaponDamageBonus)(Mob *this, Mob *);
  int (__fastcall *getMeleeKnockbackBonus)(Mob *this);
  void (__fastcall *travel)(Mob *this, IMobMovementProxy *, float, float, float);
  void (__fastcall *travel)(Mob *this, float, float, float);
  void (__fastcall *applyFinalFriction)(Mob *this, float, bool);
  void (__fastcall *updateWalkAnim)(Mob *this);
  void (__fastcall *aiStep)(Mob *this, IMobMovementProxy *);
  void (__fastcall *aiStep)(Mob *this);
  void (__fastcall *pushActors)(Mob *this);
  void (__fastcall *lookAt)(Mob *this, Actor *, float, float);
  bool (__fastcall *isLookingAtAnEntity)(Mob *this);
  bool (__fastcall *checkSpawnRules)(Mob *this, bool);
  bool (__fastcall *checkSpawnObstruction)(Mob *this);
  float (__fastcall *getAttackAnim)(Mob *this, float);
  int (__fastcall *getItemUseDuration)(Mob *this);
  float (__fastcall *getItemUseStartupProgress)(Mob *this);
  float (__fastcall *getItemUseIntervalProgress)(Mob *this);
  int (__fastcall *getItemuseIntervalAxis)(Mob *this);
  int (__fastcall *getTimeAlongSwing)(Mob *this);
  void (__fastcall *ate)(Mob *this);
  float (__fastcall *getMaxHeadXRot)(Mob *this);
  Mob *(__fastcall *getLastHurtByMob)(Mob *this);
  void (__fastcall *setLastHurtByMob)(Mob *this, Mob *);
  Player *(__fastcall *getLastHurtByPlayer)(Mob *this);
  void (__fastcall *setLastHurtByPlayer)(Mob *this, Player *);
  Mob *(__fastcall *getLastHurtMob)(Mob *this);
  void (__fastcall *setLastHurtMob)(Mob *this, Actor *);
  bool (__fastcall *isAlliedTo)(Mob *this, Mob *);
  bool (__fastcall *doHurtTarget)(Mob *this, Actor *);
  bool (__fastcall *canBeControlledByRider)(Mob *this);
  void (__fastcall *leaveCaravan)(Mob *this);
  void (__fastcall *joinCaravan)(Mob *this, Mob *);
  bool (__fastcall *hasCaravanTail)(Mob *this);
  ActorUniqueID *(__fastcall *getCaravanHead)(Mob *this, ActorUniqueID *result);
  int (__fastcall *getArmorValue)(Mob *this);
  float (__fastcall *getArmorCoverPercentage)(Mob *this);
  void (__fastcall *hurtArmor)(Mob *this, const ActorDamageSource *, int, const std::bitset<4> *);
  void (__fastcall *hurtArmor)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *hurtArmorSlot)(Mob *this, const ActorDamageSource *, int, ArmorSlot);
  void (__fastcall *setDamagedArmor)(Mob *this, ArmorSlot, const ItemStack *);
  void (__fastcall *sendArmorDamage)(Mob *this, const std::bitset<4> *);
  void (__fastcall *sendArmor)(Mob *this, const std::bitset<4> *);
  void (__fastcall *containerChanged)(Mob *this, int);
  void (__fastcall *updateEquipment)(Mob *this);
  int (__fastcall *clearEquipment)(Mob *this);
  std::vector<ItemStack const *> *(__fastcall *getAllArmor)(Mob *this, std::vector<ItemStack const *> *result);
  std::vector<int> *(__fastcall *getAllArmorID)(Mob *this, std::vector<int> *result);
  std::vector<ItemStack const *> *(__fastcall *getAllHand)(Mob *this, std::vector<ItemStack const *> *result);
  std::vector<ItemStack const *> *(__fastcall *getAllEquipment)(Mob *this, std::vector<ItemStack const *> *result);
  int (__fastcall *getArmorTypeHash)(Mob *this);
  void (__fastcall *dropEquipmentOnDeath)(Mob *this);
  void (__fastcall *dropEquipmentOnDeath)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *clearVanishEnchantedItemsOnDeath)(Mob *this);
  void (__fastcall *sendInventory)(Mob *this, bool);
  int (__fastcall *getDamageAfterMagicAbsorb)(Mob *this, const ActorDamageSource *, int);
  bool (__fastcall *createAIGoals)(Mob *this);
  void (__fastcall *onBorn)(Mob *this, Actor *, Actor *);
  bool (__fastcall *setItemSlot)(Mob *this, EquipmentSlot, const ItemStack *);
  void (__fastcall *setTransitioningSitting)(Mob *this, bool);
  void (__fastcall *attackAnimation)(Mob *this, Actor *, float);
  int (__fastcall *getAttackTime)(Mob *this);
  float (__fastcall *_getWalkTargetValue)(Mob *this, const BlockPos *);
  bool (__fastcall *canExistWhenDisallowMob)(Mob *this);
  bool (__fastcall *useNewAi)(Mob *this);
  void (__fastcall *ascendLadder)(Mob *this);
  void (__fastcall *ascendScaffolding)(Mob *this);
  void (__fastcall *descendScaffolding)(Mob *this);
  void (__fastcall *dropContainer)(Mob *this);
  std::unique_ptr<BodyControl> *(__fastcall *initBodyControl)(Mob *this, std::unique_ptr<BodyControl> *result);
  void (__fastcall *jumpFromGround)(Mob *this, IMobMovementProxy *);
  void (__fastcall *jumpFromGround)(Mob *this);
  void (__fastcall *updateAi)(Mob *this);
  void (__fastcall *newServerAiStep)(Mob *this);
  void (__fastcall *_serverAiMobStep)(Mob *this);
  int (__fastcall *getDamageAfterEnchantReduction)(Mob *this, const ActorDamageSource *, int);
  int (__fastcall *getDamageAfterArmorAbsorb)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *dropBags)(Mob *this);
  void (__fastcall *tickDeath)(Mob *this);
  void (__fastcall *updateGliding)(Mob *this);
  bool (__fastcall *_allowAscendingScaffolding)(Mob *this);
  bool (__fastcall *isDarkEnoughToSpawn)(Monster *this);
};

```

### `Guardian_vtbl`
```
struct /*VFT*/ Guardian_vtbl
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
  void (__fastcall *knockback)(Mob *this, Actor *, int, float, float, float, float, float);
  void (__fastcall *resolveDeathLoot)(Mob *this, int, const ActorDamageSource *);
  void (__fastcall *spawnAnim)(Mob *this);
  void (__fastcall *setSleeping)(Mob *this, bool);
  void (__fastcall *setSprinting)(Mob *this, bool);
  void (__fastcall *playAmbientSound)(Mob *this);
  LevelSoundEvent (__fastcall *getAmbientSound)(Mob *this);
  int (__fastcall *getAmbientSoundPostponeTicks)(Mob *this);
  int (__fastcall *getAmbientSoundPostponeTicksRange)(Mob *this);
  const TextureUVCoordinateSet *(__fastcall *getItemInHandIcon)(Mob *this, const ItemStack *, int);
  float (__fastcall *getSpeed)(Mob *this);
  void (__fastcall *setSpeed)(Mob *this, float);
  float (__fastcall *getJumpPower)(Mob *this);
  bool (__fastcall *hurtEffects)(Mob *this, const ActorDamageSource *, int, bool, bool);
  int (__fastcall *getMeleeWeaponDamageBonus)(Mob *this, Mob *);
  int (__fastcall *getMeleeKnockbackBonus)(Mob *this);
  void (__fastcall *travel)(Mob *this, IMobMovementProxy *, float, float, float);
  void (__fastcall *travel)(Mob *this, float, float, float);
  void (__fastcall *applyFinalFriction)(Mob *this, float, bool);
  void (__fastcall *updateWalkAnim)(Mob *this);
  void (__fastcall *aiStep)(Mob *this, IMobMovementProxy *);
  void (__fastcall *aiStep)(Mob *this);
  void (__fastcall *pushActors)(Mob *this);
  void (__fastcall *lookAt)(Mob *this, Actor *, float, float);
  bool (__fastcall *isLookingAtAnEntity)(Mob *this);
  bool (__fastcall *checkSpawnRules)(Mob *this, bool);
  bool (__fastcall *checkSpawnObstruction)(Mob *this);
  float (__fastcall *getAttackAnim)(Mob *this, float);
  int (__fastcall *getItemUseDuration)(Mob *this);
  float (__fastcall *getItemUseStartupProgress)(Mob *this);
  float (__fastcall *getItemUseIntervalProgress)(Mob *this);
  int (__fastcall *getItemuseIntervalAxis)(Mob *this);
  int (__fastcall *getTimeAlongSwing)(Mob *this);
  void (__fastcall *ate)(Mob *this);
  float (__fastcall *getMaxHeadXRot)(Mob *this);
  Mob *(__fastcall *getLastHurtByMob)(Mob *this);
  void (__fastcall *setLastHurtByMob)(Mob *this, Mob *);
  Player *(__fastcall *getLastHurtByPlayer)(Mob *this);
  void (__fastcall *setLastHurtByPlayer)(Mob *this, Player *);
  Mob *(__fastcall *getLastHurtMob)(Mob *this);
  void (__fastcall *setLastHurtMob)(Mob *this, Actor *);
  bool (__fastcall *isAlliedTo)(Mob *this, Mob *);
  bool (__fastcall *doHurtTarget)(Mob *this, Actor *);
  bool (__fastcall *canBeControlledByRider)(Mob *this);
  void (__fastcall *leaveCaravan)(Mob *this);
  void (__fastcall *joinCaravan)(Mob *this, Mob *);
  bool (__fastcall *hasCaravanTail)(Mob *this);
  ActorUniqueID *(__fastcall *getCaravanHead)(Mob *this, ActorUniqueID *result);
  int (__fastcall *getArmorValue)(Mob *this);
  float (__fastcall *getArmorCoverPercentage)(Mob *this);
  void (__fastcall *hurtArmor)(Mob *this, const ActorDamageSource *, int, const std::bitset<4> *);
  void (__fastcall *hurtArmor)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *hurtArmorSlot)(Mob *this, const ActorDamageSource *, int, ArmorSlot);
  void (__fastcall *setDamagedArmor)(Mob *this, ArmorSlot, const ItemStack *);
  void (__fastcall *sendArmorDamage)(Mob *this, const std::bitset<4> *);
  void (__fastcall *sendArmor)(Mob *this, const std::bitset<4> *);
  void (__fastcall *containerChanged)(Mob *this, int);
  void (__fastcall *updateEquipment)(Mob *this);
  int (__fastcall *clearEquipment)(Mob *this);
  std::vector<ItemStack const *> *(__fastcall *getAllArmor)(Mob *this, std::vector<ItemStack const *> *result);
  std::vector<int> *(__fastcall *getAllArmorID)(Mob *this, std::vector<int> *result);
  std::vector<ItemStack const *> *(__fastcall *getAllHand)(Mob *this, std::vector<ItemStack const *> *result);
  std::vector<ItemStack const *> *(__fastcall *getAllEquipment)(Mob *this, std::vector<ItemStack const *> *result);
  int (__fastcall *getArmorTypeHash)(Mob *this);
  void (__fastcall *dropEquipmentOnDeath)(Mob *this);
  void (__fastcall *dropEquipmentOnDeath)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *clearVanishEnchantedItemsOnDeath)(Mob *this);
  void (__fastcall *sendInventory)(Mob *this, bool);
  int (__fastcall *getDamageAfterMagicAbsorb)(Mob *this, const ActorDamageSource *, int);
  bool (__fastcall *createAIGoals)(Mob *this);
  void (__fastcall *onBorn)(Mob *this, Actor *, Actor *);
  bool (__fastcall *setItemSlot)(Mob *this, EquipmentSlot, const ItemStack *);
  void (__fastcall *setTransitioningSitting)(Mob *this, bool);
  void (__fastcall *attackAnimation)(Mob *this, Actor *, float);
  int (__fastcall *getAttackTime)(Mob *this);
  float (__fastcall *_getWalkTargetValue)(Mob *this, const BlockPos *);
  bool (__fastcall *canExistWhenDisallowMob)(Mob *this);
  bool (__fastcall *useNewAi)(Mob *this);
  void (__fastcall *ascendLadder)(Mob *this);
  void (__fastcall *ascendScaffolding)(Mob *this);
  void (__fastcall *descendScaffolding)(Mob *this);
  void (__fastcall *dropContainer)(Mob *this);
  std::unique_ptr<BodyControl> *(__fastcall *initBodyControl)(Mob *this, std::unique_ptr<BodyControl> *result);
  void (__fastcall *jumpFromGround)(Mob *this, IMobMovementProxy *);
  void (__fastcall *jumpFromGround)(Mob *this);
  void (__fastcall *updateAi)(Mob *this);
  void (__fastcall *newServerAiStep)(Mob *this);
  void (__fastcall *_serverAiMobStep)(Mob *this);
  int (__fastcall *getDamageAfterEnchantReduction)(Mob *this, const ActorDamageSource *, int);
  int (__fastcall *getDamageAfterArmorAbsorb)(Mob *this, const ActorDamageSource *, int);
  void (__fastcall *dropBags)(Mob *this);
  void (__fastcall *tickDeath)(Mob *this);
  void (__fastcall *updateGliding)(Mob *this);
  bool (__fastcall *_allowAscendingScaffolding)(Mob *this);
  bool (__fastcall *isDarkEnoughToSpawn)(Monster *this);
};

```

