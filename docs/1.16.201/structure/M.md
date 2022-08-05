# M
### `MovementInterpolator`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mPos
12 | (8) `Vec2` | mRot
20 | (4) `float` | mHeadYaw
24 | (4) `int` | mPositionSteps
28 | (4) `int` | mRotationSteps
32 | (4) `int` | mHeadYawSteps
36 | (1) `bool` | mInterpolationActive


### `mce::Color`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r
4 | (4) `float` | g
8 | (4) `float` | b
12 | (4) `float` | a


### `mce::MaterialPtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::RenderMaterialInfo>` | mRenderMaterialInfoPtr


### `mce::TexturePtr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<BedrockTextureData const >` | mClientTexture
16 | (56) `ResourceLocation` | mResourceLocation


### `mce::UUID`
Offset | Type | Name
-|-|-|-
0 | (16) `unsigned __int64[2]` | Data


### `MinecoinCatalogModel::fetchAndHydrate::__l2::<lambda_572de4bfa096cecd80e1e589d96c29d2>::()::__l5::<lambda_c052bc080a478cc323090c914d1fc70a>`
Offset | Type | Name
-|-|-|-


### `MinecoinCatalogModel::fetchAllCoinOffers::__l2::<lambda_635fb040fea347febb7d715b1cd27254>::()::__l5::<lambda_c2eb9aad96d78d40471c9b3ee69a3747>`
Offset | Type | Name
-|-|-|-


### `MinecoinCatalogModel::fetchAndHydrate::__l2::<lambda_572de4bfa096cecd80e1e589d96c29d2>::()::__l5::<lambda_fcc88562243a0d1882490080a4a4353a>`
Offset | Type | Name
-|-|-|-


### `MaterialVariants`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::MaterialPtr` | mSkinningMaterialPtr
16 | (16) `mce::MaterialPtr` | mSkinningColorMaterialPtr


### `MultiplayerLessonDiscovery::refreshLessonWorlds::__l2::<lambda_810ace89c32ee12eaa122e29901082c2>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | lessonTitle


### `MolangScriptArg`
Offset | Type | Name
-|-|-|-
0 | (4) `MolangScriptArgType` | mType
8 | (8) `MolangScriptArgPOD` | mPOD
16 | (72) `std::variant<MolangMatrix,MaterialVariants,MolangActorArrayPtr,MolangActorIdArrayPtr,MolangArrayVariable,MolangClientTexture,MolangContextVariable,MolangDataDrivenGeometry,MolangEntityVariable,MolangGeometryVariable,MolangMaterialVariable,MolangMemberAccessor,MolangMemberArray,MolangQueryFunctionPtr,MolangTempVariable,MolangTextureVariable>` | mData


### `MolangScriptArgPOD`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mFloat
1 | (8) `unsigned __int64` | mHashType64
2 | (8) `Actor *` | mActorPtr
3 | (8) `__int64` | mActorId
4 | (8) `ItemStackBase *` | mItemStackBasePtr
5 | (8) `unsigned __int64` | _mData


### `MolangLoopBreak`
Offset | Type | Name
-|-|-|-


### `MolangLoopContinue`
Offset | Type | Name
-|-|-|-


### `MolangMatrix`
Offset | Type | Name
-|-|-|-
0 | (64) `float[4][4]` | mMatrix


### `MolangActorArrayPtr`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Actor *>` | mActors


### `MolangActorIdArrayPtr`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ActorUniqueID>` | mActorIds


### `MolangArrayVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0


### `MolangClientTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::pair<HashedString,mce::TexturePtr> >` | mData


### `MolangContextVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0
48 | (2) `_BYTE[2]` | mMolangVariableIndex


### `MolangDataDrivenGeometry`
Offset | Type | Name
-|-|-|-
0 | (8) `DataDrivenGeometry *` | mGeometry
8 | (48) `HashedString` | mName


### `MolangEntityVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0
48 | (2) `_BYTE[2]` | mMolangVariableIndex


### `MolangGeometryVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0


### `MolangMaterialVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0


### `MolangMemberAccessor`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0


### `MolangMemberArray`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<std::vector<MolangMemberVariable>>` | mMembers


### `MolangQueryFunctionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `_BYTE[8]` | mReturnType
8 | (8) `const std::function<MolangScriptArg const & __cdecl(RenderParams &,std::vector<ExpressionNode> const &)> *` | mQueryFunctionPtr
16 | (48) `HashedString` | mName


### `MolangTempVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0
48 | (2) `_BYTE[2]` | mMolangVariableIndex


### `MolangTextureVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | baseclass_0


### `mce::FileWatcherHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::detail::FileWatcherHandleInternal>` | mFileWatcherHandleInternal


### `mce::Image`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | imageFormat
4 | (4) `unsigned int` | mWidth
8 | (4) `unsigned int` | mHeight
12 | (1) `mce::ImageUsage` | mUsage
16 | (24) `mce::Blob` | mImageBytes
40 | (40) `KTX::KTXInfo` | mKTXInfo


### `mce::Blob`
Offset | Type | Name
-|-|-|-
0 | (16) `std::unique_ptr<unsigned char [0],mce::Blob::Deleter>` | mBlob
16 | (8) `unsigned __int64` | mSize


### `mce::Blob::Deleter`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(unsigned __int8 *)` | m_func


### `MainWindow`
Offset | Type | Name
-|-|-|-
0 | (8) `HWND__ *` | mHWnd
8 | (32) `std::string` | mWindowTitle
40 | (8) `std::unique_ptr<MinecraftGame>` | mMinecraftGame
48 | (1) `bool` | mSuspended
56 | (32) `std::vector<bool>` | mKeyDown
88 | (1) `bool` | mLeftButtonPressed
96 | (8) `?` | mAppPlatform
104 | (8) `ServiceRegistrationToken<AppPlatform>` | mAppPlatformRegistrationToken
112 | (16) `std::shared_ptr<HIDControllerWin32>` | mHIDController
128 | (8) `tagPOINT` | mLastCursorPos
136 | (8) `tagPOINT` | mLastDesiredSize
144 | (1) `MainWindow::ResizeMode` | mResizeMode
152 | (72) `InitOnce` | mGameInit
224 | (8) `std::unique_ptr<WindowState>` | mWindowState
232 | (64) `std::unordered_map<std::string,std::string>` | mArguments
296 | (8) `std::unique_ptr<ActivationUri>` | mActivationUri
304 | (424) `GameControllerHandler_Windows` | mGameControllerHandler


### `MoveControlDolphinDescription`
Offset | Type | Name
-|-|-|-
0 | (16) `MoveControlDescription` | baseclass_0


### `MoveControlDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (4) `float` | mMaxTurn


### `Matrix`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,0>` | _m


### `MobEffectInstance`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mModId
4 | (1) `bool` | mIsRefreshed
8 | (4) `unsigned int` | mId
12 | (4) `int` | mDuration
16 | (4) `int` | mDurationEasy
20 | (4) `int` | mDurationNormal
24 | (4) `int` | mDurationHard
28 | (4) `int` | mAmplifier
32 | (1) `bool` | mDisplayOnScreenTextureAnimation
33 | (1) `bool` | mAmbient
34 | (1) `bool` | mNoCounter
35 | (1) `bool` | mEffectVisible


### `MobSpawnHerdInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mMinCount
4 | (4) `unsigned int` | mMaxCount
8 | (4) `unsigned int` | mHerdEventSkipCount
12 | (4) `unsigned int` | mInitialEventCount
16 | (32) `std::string` | mInitialEvent
48 | (32) `std::string` | mHerdEvent


### `mce::MeshData`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::PrimitiveMode` | mMode
1 | (1) `bool` | mMeshNotFree
8 | (24) `std::vector<glm::tvec3<float,0>>` | mPositions
32 | (24) `std::vector<glm::tvec4<float,0>>` | mNormals
56 | (24) `std::vector<unsigned int>` | mIndices
80 | (24) `std::vector<unsigned int>` | mColors
104 | (24) `std::vector<unsigned short>` | mBoneId0s
128 | (72) `std::vector<glm::tvec2<float,0>>[3]` | mTextureUVs
200 | (24) `std::vector<unsigned short>` | mPBRTextureIndices
224 | (12) `std::array<bool,12>` | mFieldEnabled


### `ModBlockPatternManager`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::unique_ptr<ModBlockPattern>>` | mBlockPatterns
24 | (64) `std::unordered_map<unsigned __int64,ModBlockPattern const *>` | mBlockPatternHash
88 | (64) `std::unordered_map<Block const *,std::vector<ModBlockPattern const *>>` | mBlockPatternMapping


### `ModeEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `const wchar_t *` | mCModeWide
8 | (8) `const char *` | mCMode1
16 | (8) `const char *` | mCMode2
24 | (1) `Core::FileOpenMode` | mFileOpenMode
28 | (4) `int` | mIos1
32 | (4) `int` | mIos2


### `MultibyteCodec`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | encoding
8 | (8) `const void *` | config
16 | (8) `int (__fastcall *)(const void *)` | codecinit
24 | (8) `__int64 (__fastcall *)(MultibyteCodec_State *, const void *, const wchar_t **, __int64, unsigned __int8 **, __int64, int)` | encode
32 | (8) `int (__fastcall *)(MultibyteCodec_State *, const void *)` | encinit
40 | (8) `__int64 (__fastcall *)(MultibyteCodec_State *, const void *, unsigned __int8 **, __int64)` | encreset
48 | (8) `__int64 (__fastcall *)(MultibyteCodec_State *, const void *, const unsigned __int8 **, __int64, wchar_t **, __int64)` | decode
56 | (8) `int (__fastcall *)(MultibyteCodec_State *, const void *)` | decinit
64 | (8) `__int64 (__fastcall *)(MultibyteCodec_State *, const void *)` | decreset


### `method_cache_entry`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | version
8 | (8) `_object *` | name
16 | (8) `_object *` | value


### `Motive`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | mName
32 | (4) `const int` | mWidth
36 | (4) `const int` | mHeight
40 | (4) `const int` | mUo
44 | (4) `const int` | mVo
48 | (1) `const bool` | mIsPublic


### `mce::RenderMaterialGroup`
Offset | Type | Name
-|-|-|-
0 | (16) `AppPlatformListener` | baseclass_0
16 | (8) `mce::RenderMaterialGroupBase` | baseclass_10
24 | (64) `std::unordered_map<HashedString,std::shared_ptr<mce::RenderMaterialInfo>>` | mMaterials
88 | (16) `std::map<std::string,std::vector<PackIdVersion>>` | mLoadedMaterialFiles
104 | (56) `ResourceLocation` | mBoundList
160 | (80) `std::mutex` | mAsyncLoadLock
240 | (1) `std::atomic<bool>` | mRestartAsyncLoad
248 | (64) `mce::SamplerGroupCache` | mSamplerGroupCache
312 | (8) `ResourcePackManager *` | mResourcePackManager
320 | (8) `ResourceLoadManager *` | mResourceLoadManager
328 | (16) `Bedrock::NonOwnerPointer<mce::ShaderGroup>` | mShaderGroup


### `mce::RenderMaterialGroupBase`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::RenderMaterialGroupBase_vtbl *` | __vftable


### `mce::SamplerGroupCache`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<unsigned __int64,std::shared_ptr<mce::SamplerStateHeapEntry>>` | mCache


### `MCRESULT`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSuccess
1 | (1) `MCCATEGORY` | mCategory
2 | (2) `unsigned __int16` | mCode


### `MPMCQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> > >`
Offset | Type | Name
-|-|-|-
0 | (616) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>` | mQueue


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *>` | producerListTail
8 | (4) `std::atomic<unsigned int>` | producerCount
16 | (8) `std::atomic<unsigned __int64>` | initialBlockPoolIndex
24 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *` | initialBlockPool
32 | (8) `unsigned __int64` | initialBlockPoolSize
40 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>` | freeList
48 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *>` | implicitProducerHash
56 | (8) `std::atomic<unsigned __int64>` | implicitProducerHashCount
64 | (24) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash` | initialImplicitProducerHash
88 | (512) `std::array<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32>` | initialImplicitProducerHashEntries
600 | (4) `std::atomic_flag` | implicitProducerHashResizeInProgress
604 | (4) `std::atomic<unsigned int>` | nextExplicitConsumerId
608 | (4) `std::atomic<unsigned int>` | globalExplicitConsumerOffset


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *>` | freeListHead


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | capacity
8 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *` | entries
16 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *` | prev


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<unsigned int>` | key
8 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *` | value


### `mce::ChipsetInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | chipsetName
8 | (1) `bool` | brokenCentroidSampler


### `mce::VertexFormat`
Offset | Type | Name
-|-|-|-
0 | (2) `WideByteMask` | fieldMask
2 | (24) `unsigned __int16[12]` | _fieldOffset
26 | (2) `unsigned __int16` | vertexSize
28 | (1) `bool` | allowHalfFloats


### `MPMCQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> > >`
Offset | Type | Name
-|-|-|-
0 | (616) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>` | mQueue


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *>` | producerListTail
8 | (4) `std::atomic<unsigned int>` | producerCount
16 | (8) `std::atomic<unsigned __int64>` | initialBlockPoolIndex
24 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *` | initialBlockPool
32 | (8) `unsigned __int64` | initialBlockPoolSize
40 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>` | freeList
48 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *>` | implicitProducerHash
56 | (8) `std::atomic<unsigned __int64>` | implicitProducerHashCount
64 | (24) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash` | initialImplicitProducerHash
88 | (512) `std::array<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32>` | initialImplicitProducerHashEntries
600 | (4) `std::atomic_flag` | implicitProducerHashResizeInProgress
604 | (4) `std::atomic<unsigned int>` | nextExplicitConsumerId
608 | (4) `std::atomic<unsigned int>` | globalExplicitConsumerOffset


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *>` | freeListHead


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | capacity
8 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *` | entries
16 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *` | prev


### `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<unsigned int>` | key
8 | (8) `moodycamel::ConcurrentQueue<std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *` | value


### `MouseDevice`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | clickX
2 | (2) `__int16` | clickY
4 | (4) `int` | _index
8 | (2) `__int16` | _x
10 | (2) `__int16` | _y
12 | (2) `__int16` | _dx
14 | (2) `__int16` | _dy
16 | (2) `__int16` | _xOld
18 | (2) `__int16` | _yOld
20 | (5) `char[5]` | _buttonStates
32 | (24) `std::vector<MouseAction>` | _inputs
56 | (4) `int` | _firstMovementType


### `mce::Mesh`
Offset | Type | Name
-|-|-|-
0 | (32) `mce::IndexBufferContainer` | baseclass_0
32 | (24) `std::variant<std::monostate,unsigned __int64,glm::tvec3<int,0> >` | mCacheKey
56 | (1) `bool` | mTemporary
57 | (1) `mce::PrimitiveMode` | mPrimitiveMode
64 | (32) `std::string` | mDebugName
96 | (16) `std::weak_ptr<mce::BufferResourceService>` | mBufferResourceService
112 | (240) `mce::MeshData` | mMeshData
352 | (16) `mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> >` | mVertexBuffer
368 | (8) `std::optional<unsigned int>` | mVertexCount
376 | (30) `mce::VertexFormat` | mVertexFormat
408 | (24) `std::vector<unsigned char>` | mRawData


### `mce::IndexBufferContainer`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> >` | mIndexBuffer
16 | (4) `unsigned int` | mIndexCount
20 | (4) `unsigned int` | mIndexSize
24 | (4) `int` | mIteration


### `mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >` | mResourcePointerBlock


### `mce::Camera`
Offset | Type | Name
-|-|-|-
0 | (48) `MatrixStack` | viewMatrixStack
48 | (48) `MatrixStack` | worldMatrixStack
96 | (48) `MatrixStack` | projectionMatrixStack
144 | (64) `glm::tmat4x4<float,0>` | mInverseViewMatrix
208 | (12) `glm::tvec3<float,0>` | mRight
220 | (12) `glm::tvec3<float,0>` | mUp
232 | (12) `glm::tvec3<float,0>` | mForward
244 | (12) `glm::tvec3<float,0>` | mPosition
256 | (4) `float` | mAspectRatio
260 | (4) `float` | mFov
264 | (4) `float` | mZNear
268 | (4) `float` | mZFar
272 | (192) `Frustum` | mFrustum
464 | (64) `Matrix` | mViewMatrix
528 | (64) `Matrix` | mProjectionMatrix
592 | (12) `glm::tvec3<float,0>` | mWorldPosition
604 | (12) `glm::tvec3<float,0>` | mWorldTargetPosition
616 | (12) `glm::tvec3<float,0>` | mCameraTargetPos
628 | (64) `Matrix` | mLViewMat
692 | (12) `glm::tvec3<float,0>` | mLWorldPos
704 | (12) `glm::tvec3<float,0>` | mLWorldTargetPos
716 | (12) `glm::tvec3<float,0>` | mOffset
728 | (12) `glm::tvec3<float,0>` | mCameraAnchor
740 | (8) `glm::tvec2<float,0>` | mRot
748 | (8) `glm::tvec2<float,0>` | mRotPre
756 | (8) `glm::tvec2<float,0>` | mPitchLimit
764 | (4) `mce::CameraMode` | mMode


### `MatrixStack`
Offset | Type | Name
-|-|-|-
0 | (40) `std::stack<Matrix>` | stack
40 | (1) `bool` | _isDirty


### `msdfgen::SignedDistance`
Offset | Type | Name
-|-|-|-
0 | (8) `long double` | distance
8 | (8) `long double` | dot


### `mce::ClientTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr> >` | baseclass_0


### `mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >` | mResourcePointerBlock


### `mce::TextureDescription`
Offset | Type | Name
-|-|-|-
0 | (72) `cg::TextureDescription` | baseclass_0
72 | (8) `mce::SampleDescription` | mSampleDescription
80 | (16) `mce::Color` | mClearColor
96 | (4) `float` | mOptimizedClearDepth
100 | (1) `unsigned __int8` | mOptimizedClearStencil
104 | (4) `mce::BindFlagsBit` | mBindFlags
108 | (1) `bool` | mIsStaging


### `mce::SampleDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | count
4 | (4) `int` | quality


### `MagicSniffer::MagicSnifferHandler`
Offset | Type | Name
-|-|-|-
0 | (72) `NamedPipeObject` | pipe
72 | (8) `unsigned __int64` | frameCount
80 | (32) `std::string` | savePath
112 | (1) `bool` | scriptProfile
113 | (1) `bool` | scriptMemTrace
116 | (4) `int` | scriptMemTraceMaxFrame
120 | (8) `long double` | frozenInterval
128 | (1) `bool` | started
136 | (24) `std::vector<MagicSniffer::FrozenEvent>` | frozens
160 | (8) `unsigned __int64` | lastFrameID
168 | (8) `long double` | lastFrameTimestamp
176 | (1) `bool` | mergeScriptProfile


### `MemoryMappedFileAccess::StreamHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `MemoryMappedFileAccess::StreamDetails *` | mStream
8 | (8) `unsigned __int64` | mPosition


### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<unsigned int>` | key
8 | (8) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *` | value


### `mce::TextureWrappingDescription`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::TextureWrapping` | uAddress
1 | (1) `mce::TextureWrapping` | vAddress
2 | (1) `mce::TextureWrapping` | wAddress


### `ModalScreenData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | contentTitleId
32 | (24) `std::vector<std::string>` | contentTitleParams
56 | (32) `std::string` | contentLabelId
88 | (24) `std::vector<std::string>` | contentLabelParams
112 | (32) `std::string` | ttsContentTitleId
144 | (24) `std::vector<std::string>` | ttsContentTitleParams
168 | (32) `std::string` | ttsContentLabelId
200 | (24) `std::vector<std::string>` | ttsContentLabelParams
224 | (32) `std::string` | eventScreenNameOverride
256 | (32) `std::string` | leftButtonLabelId
288 | (32) `std::string` | middleButtonLabelId
320 | (32) `std::string` | rightCancelButtonLabelId
352 | (4) `ModalScreenButtonMode` | buttonMode
356 | (1) `bool` | contentContainsPII
357 | (1) `bool` | closeButton
358 | (1) `bool` | enableEmoticonify
360 | (4) `ModalScreenButtonId` | initialFocusButton


### `MovePlayerPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mPlayerID
48 | (12) `Vec3` | mPos
60 | (8) `Vec2` | mRot
68 | (4) `float` | mYHeadRot
72 | (1) `_BYTE[1]` | mResetPosition
73 | (1) `bool` | mOnGround
80 | (8) `ActorRuntimeID` | mRidingID
88 | (4) `int` | mCause
92 | (4) `int` | mSourceEntityType
96 | (8) `unsigned __int64` | mTick


### `mce::MeshContext`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::RenderContext *` | renderContext
8 | (8) `mce::Camera *` | camera
16 | (8) `mce::GlobalConstantBuffers *` | constantBuffers
24 | (8) `mce::GlobalConstantBufferManager *` | constantBufferManager
32 | (8) `ShaderColor *` | currentShaderColor
40 | (8) `ShaderColor *` | currentShaderDarkColor
48 | (8) `mce::BufferResourceService *` | bufferResourceService
56 | (8) `mce::QuadIndexBuffer *` | currentQuadIndexBuffer
64 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | immediateBuffer
80 | (20) `std::optional<glm::tvec4<float,0> >` | normalizedClipRegion
100 | (1) `unsigned __int8` | subClientId
101 | (1) `bool` | isDrawingUI
102 | (1) `bool` | isDrawingFirstPersonObjects
103 | (1) `bool` | isDrawingInLevelCubeMap
104 | (1) `bool` | isDrawingEnvironmentalText
105 | (1) `bool` | isUsingVRPatch


### `mce::ServerResourcePointer<mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >` | mResourcePointerBlock


### `MinecraftglTFExporter::_loadAsycModel::__l2::<lambda_a622c71abb5c40f0cf307f75912da47d>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftglTFExporter *const` | __this
8 | (64) `std::function<void __cdecl(Core::Path const &)>` | callback


### `MinecraftglTFExporter::ImageBakeData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mImageID
4 | (1) `bool` | mAlpha
5 | (1) `bool` | mBlend


### `MinecraftglTFExporter::AsyncModelMaterial`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mMaterialName
32 | (24) `std::vector<std::string>` | mTextureKeys
56 | (16) `mce::Color` | mChangeColor
72 | (16) `mce::Color` | mOverlayColor
88 | (1) `bool` | mUseOverlayColor
89 | (1) `bool` | mUseColorMask
90 | (1) `bool` | mUseEmissive
91 | (1) `bool` | mUseAlphaTest
92 | (1) `bool` | mUseTintedAlphaTest
93 | (1) `bool` | mUseAlphaToCoverage
94 | (1) `bool` | mUseMultiTexture
95 | (1) `bool` | mUseMaskedMultiTexture
96 | (1) `bool` | mUseColorSecondTexture
97 | (1) `bool` | mStateBlending


### `MinecraftglTFExporter::BakeData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAlpha
1 | (1) `bool` | mBlend


### `MinecraftglTFExporter::_bakeMultiTextureImage::__l2::MultiTextureData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | alphaChannel
4 | (4) `int` | bpp
8 | (4) `int` | colorChannels
12 | (4) `float` | heightRatio
16 | (4) `float` | widthRatio


### `mce::TextureContainer`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<cg::ImageBuffer>` | mStorage
24 | (112) `mce::TextureDescription` | mDescription


### `MolangVariableMap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<short>` | mMapFromVariableIndexToVariableArrayOffset
24 | (24) `std::vector<std::unique_ptr<MolangVariable>>` | mVariables
48 | (1) `bool` | mHasPublicVariables
49 | (1) `bool` | mHasVariablesThatShouldSync
50 | (1) `bool` | mHasVariablesThatShouldSave


### `mce::CreateTextureFromOwnedImageTransaction`
Offset | Type | Name
-|-|-|-
0 | (80) `mce::Image` | mImage
80 | (32) `std::string` | mDebugName


### `mce::framebuilder::gamecomponents::PlayerVision`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mNightVisionEnabled
4 | (4) `float` | mNightVisionScale
8 | (4) `float` | mBlindnessLevel


### `MinecraftGame::_initPostE::__l2::<lambda_82af75bef2ab9188506527c9f91b166c>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_1fa9dcbfa9b3eaf2961dc9aea7c94d59>`
Offset | Type | Name
-|-|-|-
0 | (80) `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>` | completedCallback


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (8) `SceneStack *` | sceneStack
16 | (64) `std::function<void __cdecl(void)>` | syncCompleteCallback


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_a2e2b143ebf49ce93012938fa0df5cda>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (80) `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>` | completedCallback


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_a2e2b143ebf49ce93012938fa0df5cda>::()::__l2::<lambda_4969cffd23c0de619ebdcf38260c48fe>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (64) `std::function<void __cdecl(Core::Result)>` | syncCallback
72 | (80) `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>` | completedCallback


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_a2e2b143ebf49ce93012938fa0df5cda>::()::__l2::<lambda_d0933490929011ed15bac26ef215c31f>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (64) `std::function<void __cdecl(Core::Result)>` | onSettingsSyncComplete
72 | (64) `std::function<void __cdecl(Core::Result)>` | syncCallback
136 | (80) `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>` | completedCallback


### `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_a2e2b143ebf49ce93012938fa0df5cda>::()::__l2::<lambda_4969cffd23c0de619ebdcf38260c48fe>::()::__l2::<lambda_d5a8ab8a5f399a78caad968a8a644159>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(Core::Result)>` | syncCallback
64 | (80) `MinecraftGame::_onInitRemoteSystem::__l5::<lambda_7c105b800501859cc3eef7b7b7109f87>` | completedCallback


### `mce::framebuilder::FrameConfiguration::View`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mPlayerId
4 | (16) `cg::math::Rect<float>` | mViewport
20 | (4) `float` | mGuiScale
24 | (1) `bool` | mSkipUI
28 | (4) `mce::framebuilder::FrameConfiguration::ViewSubmersionState` | mWaterSubmersionState
32 | (4) `mce::framebuilder::FrameConfiguration::ViewSubmersionState` | mLavaSubmersionState
36 | (64) `glm::tmat4x4<float,0>` | mView
100 | (64) `glm::tmat4x4<float,0>` | mProj
164 | (64) `glm::tmat4x4<float,0>` | mItemInHandView
228 | (64) `glm::tmat4x4<float,0>` | mItemInHandProj
292 | (12) `glm::tvec3<float,0>` | mWorldOrigin
304 | (16) `mce::Color` | mFillColor


### `MinecraftGame::createAndUploadWorldToRealm::__l2::<lambda_2475416b9ef62271aa1fb47640725728>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (32) `const std::string` | levelId
40 | (32) `const std::string` | levelName
72 | (24) `const ContentIdentity` | premiumTemplateContentIdentity
96 | (3360) `LevelSettings` | settingsCopy
3456 | (248) `Realms::World` | world
3704 | (64) `std::function<void __cdecl(void)>` | callback


### `MinecraftGame::createAndUploadWorldToRealm::__l2::<lambda_2475416b9ef62271aa1fb47640725728>::()::__l2::<lambda_4ecb63bb7d1b9d1e5d76fcd4c4903f08>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (248) `Realms::World` | world
256 | (32) `const std::string` | levelId
288 | (64) `std::function<void __cdecl(void)>` | callback


### `MinecraftGame::joinRealmFromInvite::__l2::<lambda_b1d4de3648210e849651a316d0e3749c>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (248) `const Realms::World` | world


### `MinecraftGame::joinRealm::__l2::<lambda_399b556339883ee7d2a7d7e7a44b3d71>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (248) `const Realms::World` | world


### `MinecraftGame::joinRealm::__l2::<lambda_4ac3fc4eb40a62b081946ca2676863c4>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (248) `const Realms::World` | world


### `MinecraftGame::joinRealm::__l2::<lambda_8f0bdb9c8e0d8b4db4a7d4e91c3ef521>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (248) `const Realms::World` | world


### `MinecraftGame::joinMultiplayerGame::__l2::<lambda_1c75b99c6d2554e4f187ed6dc95de8f6>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (32) `const std::string` | gameToJoinHandleId
40 | (4) `const Social::MultiplayerServiceIdentifier` | gameServiceProvider
48 | (16) `std::weak_ptr<bool>` | weakRequestAborted


### `MinecraftGame::joinMultiplayerGame::__l2::<lambda_1c75b99c6d2554e4f187ed6dc95de8f6>::()::__l2::<lambda_bc24c93b5b833504820f406a6cbbd34b>::()::__l13::<lambda_0d9dbdbb0e544b81181d77306298c412>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (256) `Social::GameConnectionInfo` | bestConnection
264 | (256) `Social::GameConnectionInfo` | backupConnection
520 | (4) `const Social::MultiplayerServiceIdentifier` | gameServiceProvider


### `MinecraftGame::joinMultiplayer::__l2::<lambda_38398a33528211dd362e8aca3d955194>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (256) `Social::GameConnectionInfo` | gameConnection
264 | (1) `bool` | isNetworkGame


### `MinecraftGame::_initPerMachineOptionObservers::__l2::<lambda_b0964a1cd276ffac57e7a2f2eea6e19e>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame *const` | __this
8 | (16) `gsl::not_null<Bedrock::NonOwnerPointer<TrialManager> >` | trialManager


### `MinecraftGame::_finishReloadingResources::__l8::<lambda_e6c52f3752df22cf185d07fb7f98287f>::()::__l2::<lambda_41cc44f2cd0343f3b1dad873c4878dd4>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<FlipbookTextureDescription>` | flipbookTextureDescriptions
24 | (24) `std::vector<FlipbookTextureDescription>` | flipbookItemTextureDescriptions
48 | (8) `MinecraftGame *const` | __this


### `MinecraftGame::forceReloadResourcePack::__l8::<lambda_f74b718687c42612b201e499363815e5>::()::__l2::<lambda_96c534976d4764786d2638ddea2aa302>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<FlipbookTextureDescription>` | flipbookTextureDescriptions
24 | (24) `std::vector<FlipbookTextureDescription>` | flipbookItemTextureDescriptions
48 | (8) `MinecraftGame *const` | __this


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_2065e32731376600173fb4ea1bcbb9b4>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int16 *` | colorMipCount


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_bc8cc4a5e9bcd28e4962e401584e810c>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<unsigned short> *` | normalOrHeightMipCount
8 | (8) `std::optional<glm::tvec2<float,0> > *` | normalOrHeightUVScale
16 | (8) `std::optional<glm::tvec2<float,0> > *` | normalOrHeightUVBias
24 | (8) `mce::framebuilder::PBRTextureDataDescription::NormalMode *` | normalMode


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_d00193f480816348f3992a08441a80fb>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<unsigned short> *` | normalOrHeightMipCount
8 | (8) `std::optional<glm::tvec2<float,0> > *` | normalOrHeightUVScale
16 | (8) `std::optional<glm::tvec2<float,0> > *` | normalOrHeightUVBias
24 | (8) `mce::framebuilder::PBRTextureDataDescription::NormalMode *` | normalMode


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_19a39ca30a9c1cb36d3b066a66e079bf>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<unsigned short> *` | merMipCount
8 | (8) `std::optional<glm::tvec2<float,0> > *` | merUVScale
16 | (8) `std::optional<glm::tvec2<float,0> > *` | merUVBias


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_b383a9617f3dde04ca8205eadd764394>`
Offset | Type | Name
-|-|-|-
0 | (8) `float *` | uniformMetalness
8 | (8) `float *` | uniformEmissive
16 | (8) `float *` | uniformRoughness


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_7354503bf8e6830a096570bb83fb0ea9>`
Offset | Type | Name
-|-|-|-


### `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_de38cdb3b974332c0bb3c504ceb15d8d>`
Offset | Type | Name
-|-|-|-


### `mce::ServerTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | baseclass_0


### `mce::ServerResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>,std::shared_ptr>` | baseclass_0


### `mce::TransactionContainer<mce::CreateTextureFromOwnedImageTransaction,mce::TextureResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateTextureFromOwnedImageTransaction &)>` | mDeferredPayload
88 | (112) `mce::CreateTextureFromOwnedImageTransaction` | mPayload
200 | (8) `gsl::not_null<mce::TextureResourceServiceContext *>` | mResourceServiceContext


### `mce::ITransactionContainer`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer_vtbl *` | __vftable


### `mce::ImmediateExecutionPolicy`
Offset | Type | Name
-|-|-|-


### `mce::ResourceServiceTextureDescription`
Offset | Type | Name
-|-|-|-
0 | (112) `mce::TextureDescription` | baseclass_0
112 | (32) `std::string` | mDebugName


### `mce::CreateTextureFromOwnedImageTransaction::apply::__l2::<lambda_75f76d1e026dc098f5e48ab88226c4f6>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::CreateTextureFromOwnedImageTransaction *const` | __this
8 | (8) `mce::TextureResourceServiceContext *` | textureResourceServiceContext


### `mce::CommandList`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::RenderContext *` | mContext
8 | (56) `mce::CommandListState` | mCommandListState


### `mce::CommandListState`
Offset | Type | Name
-|-|-|-
0 | (52) `mce::RenderTargetState` | baseclass_0
52 | (1) `mce::PrimitiveMode` | mLastPrimitiveMode


### `mce::RenderTargetState`
Offset | Type | Name
-|-|-|-
0 | (2) `mce::RenderTargetState::StencilOverride` | highStencilBitsOverride
4 | (32) `std::array<enum mce::TextureFormat,8>` | renderTargetFormat
36 | (4) `mce::TextureFormat` | depthTextureFormat
40 | (4) `unsigned int` | currentRenderTargetsBound
44 | (4) `unsigned int` | currentRenderTargetMSAACount
48 | (1) `mce::PrimitiveMode` | lastPrimitiveMode
49 | (1) `unsigned __int8` | lastStencilRef
50 | (1) `unsigned __int8` | stencilRef


### `mce::RenderTargetState::StencilOverride`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0
1 | (1) `bool` | enabled


### `mce::RingBuffer`
Offset | Type | Name
-|-|-|-


### `mce::RingBufferBase`
Offset | Type | Name
-|-|-|-


### `mce::TimeStep`
Offset | Type | Name
-|-|-|-
0 | (4) `const float` | mDeltaTime
4 | (4) `const float` | mDeltaTimeSquared
8 | (4) `float` | mAlpha
12 | (4) `float` | mInterpolatedTime
16 | (1) `bool` | mFastForward
24 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mTime


### `mce::ServerResourcePointer<mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >` | mResourcePointerBlock


### `MinecraftScreenModel`
Offset | Type | Name
-|-|-|-
0 | (8) `IDlcBatcher` | baseclass_0
8 | (16) `std::enable_shared_from_this<MinecraftScreenModel>` | baseclass_8
24 | (8) `IMinecraftGame *` | mMinecraft
32 | (8) `IClientInstance *` | mClient
40 | (8) `SceneStack *` | mSceneStack
48 | (8) `SceneFactory *` | mSceneFactory
56 | (1) `bool` | mIsDirty
64 | (24) `std::vector<DlcBatchModel>` | mDlcBatchList
88 | (8) `std::unique_ptr<IDlcValidation>` | mDlcValidation
96 | (8) `std::unique_ptr<ClientInstanceModel>` | mClientModel
104 | (4) `_BYTE[4]` | mResourcePackConfirmationLoadingState
112 | (8) `std::unique_ptr<SkinPackCollectionModel>` | mSkinPackCollectionModel
120 | (8) `std::unique_ptr<SkinPackCollectionModel>` | mPurchasableSkinPackCollectionModel
128 | (8) `std::unique_ptr<SkinPackCollectionModel>` | mOwnedSkinPackCollectionModel
136 | (8) `std::unique_ptr<SkinPackCollectionModel>` | mRealmsPlusSkinPackCollectionModel
144 | (8) `std::unique_ptr<TaskGroup>` | mFileManagerTaskGroup
152 | (8) `std::unique_ptr<TaskGroup>` | mAsyncTaskGroup
160 | (16) `std::shared_ptr<PlatformUpsellDialog>` | mPlatformUpsellDialog
176 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >` | mStartServerResult
192 | (8) `std::unique_ptr<IScreenCapabilities>` | mCapabilities
200 | (16) `PlatformStoreIconModel` | mPlatformStoreIconModel


### `MinecraftScreenController`
Offset | Type | Name
-|-|-|-
0 | (2328) `ScreenController` | baseclass_0
2328 | (16) `std::enable_shared_from_this<MinecraftScreenController>` | baseclass_918
2344 | (16) `std::shared_ptr<MinecraftScreenModel>` | mMinecraftScreenModel
2360 | (4) `ScreenExitBehavior` | mExitBehavior
2364 | (4) `InputMode` | mInputMode
2368 | (4) `_BYTE[4]` | mHoloUIInputMode
2372 | (4) `InputMode` | mPreviousInputMode
2376 | (4) `_BYTE[4]` | mPreviousHoloUIInputMode
2380 | (1) `bool` | mPlayerDied
2384 | (64) `std::function<void __cdecl(enum ModalScreenButtonId)>` | mModalDialogResultCallback
2448 | (32) `std::string` | mTTSTitle
2480 | (32) `std::string` | mTTSDialogMessage
2512 | (1) `bool` | mLeaveScreen
2513 | (1) `bool` | mRayTracingActive
2520 | (64) `std::unordered_map<std::string,std::vector<bool>>` | mDropDownActive
2584 | (64) `std::unordered_map<std::string,int>` | mStepSliderValues


### `MainMenuScreenController::attemptUserSignIn::__l12::<lambda_d4e7ee1c5adff1550b5041560b452410>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | adHocCallback


### `MainMenuScreenController::showPickCustomSkinDialog::__l5::<lambda_a4e2bdb233233a02453894c9a17595b4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(enum PickCustomSkinResult)>` | callback


### `MainMenuScreenController::confirmationNoCrossPlatformMultiplayerSkinDialog::__l2::<lambda_661d23eabc432e83ee91010b2c308115>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | callback


### `MainMenuScreenController::_startLocalWorldSubRoutine::__l5::<lambda_94583f83035eb769c7fe01832ec0681a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (568) `const LocalWorldInfo` | world
584 | (88) `MainMenuScreenController::_startLocalWorldSubRoutine::__l2::<lambda_aed306b9ae45d40861000344cc5f6fdf>` | startWorldCallback


### `MainMenuScreenController::_startLocalWorldSubRoutine::__l2::<lambda_aed306b9ae45d40861000344cc5f6fdf>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (8) `DlcUIWrapper *` | dlcUIWrapper
24 | (64) `std::function<void __cdecl(LocalWorldInfo const &)>` | startLocalWorldCallback


### `MainMenuScreenController::_startLocalWorldSubRoutine::__l2::<lambda_aed306b9ae45d40861000344cc5f6fdf>::()::__l5::<lambda_49a08e8269771801e54a0cc23500ee1e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (568) `const LocalWorldInfo` | world
584 | (64) `std::function<void __cdecl(LocalWorldInfo const &)>` | startLocalWorldCallback


### `MainMenuScreenController::_displayReportWorldModalDialog::__l2::<lambda_4cf5b46cca09918886a9bd92fd4cfbbc>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (608) `const LegacyWorldInfo` | worldInfo
624 | (1) `bool` | conversionFailed
625 | (1) `const bool` | supportsLegacyWorldUpload


### `MainMenuScreenController::startRealm::__l27::<lambda_bab6cb3dcfe66620a1773603f0d0c82d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (248) `Realms::World` | world
264 | (16) `std::shared_ptr<bool>` | joinComplete
280 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow
288 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback


### `MainMenuScreenController::startRealm::__l27::<lambda_8a1dd54eeb6e3b69a1429d063ff02918>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (248) `Realms::World` | world
264 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow
272 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback


### `MainMenuScreenController::startRealm::__l27::<lambda_14455c4014649d238c7e6a0cced5b49a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (248) `Realms::World` | world
264 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow
272 | (16) `std::shared_ptr<bool>` | joinComplete
288 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback
352 | (352) `MainMenuScreenController::startRealm::__l27::<lambda_bab6cb3dcfe66620a1773603f0d0c82d>` | successCallback
704 | (104) `MainMenuScreenController::startRealm::__l27::<lambda_d05dfcd461241f102785287ff09185fa>` | failureCallback
808 | (24) `MainMenuScreenController::startRealm::__l27::<lambda_bab1efb03fdb6b4d13239fdb2a028e22>` | retryCallback


### `MainMenuScreenController::startRealm::__l27::<lambda_d05dfcd461241f102785287ff09185fa>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (16) `std::shared_ptr<bool>` | joinComplete
32 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow
40 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback


### `MainMenuScreenController::startRealm::__l27::<lambda_bab1efb03fdb6b4d13239fdb2a028e22>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow


### `MainMenuScreenController::startRealm::__l27::<lambda_69253f24756a895374ae9fbbc561a7ca>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenController>` | weakThis
16 | (248) `Realms::World` | world
264 | (4) `IMinecraftEventing::RealmConnectionFlow` | fromFlow
272 | (352) `MainMenuScreenController::startRealm::__l27::<lambda_bab6cb3dcfe66620a1773603f0d0c82d>` | successCallback
624 | (104) `MainMenuScreenController::startRealm::__l27::<lambda_d05dfcd461241f102785287ff09185fa>` | failureCallback
728 | (24) `MainMenuScreenController::startRealm::__l27::<lambda_bab1efb03fdb6b4d13239fdb2a028e22>` | retryCallback


### `MainMenuScreenController::startRealm::__l27::<lambda_d05dfcd461241f102785287ff09185fa>::()::__l5::<lambda_f2297fd6cdff54fc728f1b9b6ff42190>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback
64 | (4) `IMinecraftEventing::RealmConnectionResult` | result


### `MainMenuScreenController::startRealm::__l27::<lambda_14455c4014649d238c7e6a0cced5b49a>::()::__l8::<lambda_e0fa9b20346e881a4c77a1c989abe7e5>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum IMinecraftEventing::RealmConnectionResult)>` | callback


### `MinecoinPurchaseDetails`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | foundPayload
8 | (32) `std::string` | productSku
40 | (32) `std::string` | originalXuid
72 | (16) `std::weak_ptr<Purchase>` | purchase


### `MinecraftScreenController::_displayStandardModalPopup::__l2::<lambda_9df9b5978eca9995e58eed112de41c4a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback


### `MinecraftScreenController::setUpCallbacksForStackPanelGrid::__l2::<lambda_06d43f22d6c9f224142b6f47060d20ba>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<int __cdecl(void)>` | heightCallback


### `MinecraftScreenController::setUpCallbacksForFloatOption::__l5::<lambda_1432e15f7f202e95ad119dc38ce704bb>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(void)>` | isEnabled


### `MinecraftScreenController::setUpCallbacksForFloatOption::__l2::<lambda_a48d5a543a5e933dc9b2ff12cdf16317>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<float __cdecl(void)>` | getValue
64 | (64) `std::function<void __cdecl(float)>` | setValue
128 | (64) `std::function<float __cdecl(void)>` | getMin
192 | (64) `std::function<float __cdecl(void)>` | getMax
256 | (64) `std::function<bool __cdecl(void)>` | isEnabled


### `MinecraftScreenController::setUpCallbacksForStepOption::__l5::<lambda_5e84b88f7dd95cdbcc340efebd78c9f6>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(void)>` | isEnabled


### `MinecraftScreenController::setUpCallbacksForStepOption::__l2::<lambda_d5331ec696dfdb985a5c5d1bf63ac924>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::vector<int> __cdecl(void)>` | getValues
64 | (64) `std::function<int __cdecl(void)>` | getValue
128 | (32) `const std::string` | valueBindingName
160 | (1) `bool` | continuousUpdate
168 | (8) `MinecraftScreenController *const` | __this


### `MinecraftScreenController::gateOnPlatformSignInForStoreAccess::__l8::<lambda_7931a47f7f18e525bc6af9c6166f89bb>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(void)>` | callback


### `MinecraftScreenController::promptConnect::__l11::<lambda_721b7bf62beaa7d2b5bb96f84d98bbd1>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>` | signInCallback


### `MinecraftScreenController::_attemptSignIn::__l10::<lambda_d4b4d05ce3108da8c444f53df4362090>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(enum Social::SignInResult)>` | onResultCallback
80 | (64) `std::function<void __cdecl(enum Social::SignInResult)>` | onPostFailCallback


### `MinecraftScreenController::_attemptConnect::__l2::<lambda_7a2dc6183b6fd73d19ad9fa528c3fe95>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis
16 | (64) `std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>` | callback


### `MinecraftScreenController::showPlayerProfile::__l5::<lambda_39aeb780af1cb1ba7606733638b96c5a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis
16 | (32) `const std::string` | xuid
48 | (16) `mce::UUID` | uuid
64 | (32) `const std::string` | platformId


### `MinecraftScreenController::exportPDF::__l13::<lambda_998f8d95f0c81e284ea8a93c630abe92>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | onComplete
64 | (16) `std::weak_ptr<MinecraftScreenController>` | weakThis


### `MainMenuScreenController`
Offset | Type | Name
-|-|-|-
0 | (2648) `MinecraftScreenController` | baseclass_0
2648 | (16) `std::shared_ptr<MainMenuScreenModel>` | mMainMenuScreenModel
2664 | (8) `std::unique_ptr<AsyncTracker>` | mAsyncTracker


### `MainMenuScreenModel::getToastFetcher::__l5::<lambda_8bc558fac96bf55cc3cb9ceb59f46c82>`
Offset | Type | Name
-|-|-|-
0 | (8) `MainMenuScreenModel *const` | __this


### `MainMenuScreenModel::fetchNewStoreOfferContent::__l2::<lambda_c82750803de2756be39f425956566c06>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenModel>` | weakModel
16 | (64) `std::function<void __cdecl(bool)>` | callback


### `MouseAction`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | x
2 | (2) `__int16` | y
4 | (2) `__int16` | _dx
6 | (2) `__int16` | dy
8 | (1) `char` | action
9 | (1) `char` | data
12 | (4) `int` | pointerId
16 | (1) `bool` | forceMotionlessPointer


### `MainMenuScreenModel::instantiateTemplate::__l2::<lambda_f64d5ea1600bb3d2b2eef0a6c9730723>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenModel>` | weakThis
16 | (32) `const Core::PathBuffer<std::string >` | newWorldDir
48 | (32) `const std::string` | levelName
80 | (24) `const ContentIdentity` | templateContentIdentity
104 | (136) `const PackIdVersion` | packIdentity
240 | (112) `const BaseGameVersion` | baseGameVersion
352 | (1) `const bool` | isPremiumWorldTemplate
353 | (1) `const bool` | isPlatformLocked
354 | (1) `_BYTE[1]` | manifestTemplateLockState
360 | (64) `std::function<void __cdecl(LevelSummary *,enum InstantiationResult)>` | method
424 | (16) `std::shared_ptr<enum InstantiationResult>` | successTracker


### `MainMenuScreenModel::instantiateTemplate::__l5::<lambda_2ec67d84188917943a8c48c18686d72c>`
Offset | Type | Name
-|-|-|-
0 | (8) `MainMenuScreenModel *const` | __this
8 | (32) `const Core::PathBuffer<std::string >` | newWorldDir
40 | (24) `const ContentIdentity` | templateContentIdentity
64 | (16) `std::shared_ptr<enum InstantiationResult>` | successTracker


### `MainMenuScreenModel::instantiateTemplate::__l2::<lambda_a1c74e951defb296eb47726f29c7afc8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenModel>` | weakThis
16 | (32) `const Core::PathBuffer<std::string >` | newWorldDir
48 | (16) `std::shared_ptr<enum InstantiationResult>` | successTracker


### `MainMenuScreenModel::instantiateTemplate::__l2::<lambda_f19f7e8990b7db427d93a9295b1cf01f>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<enum InstantiationResult>` | successTracker
16 | (440) `MainMenuScreenModel::instantiateTemplate::__l2::<lambda_f64d5ea1600bb3d2b2eef0a6c9730723>` | finalizeLevel


### `MainMenuScreenModel::navigateToFeaturedWorld::__l8::<lambda_377a05a3b8b6c737b072b8d7001def04>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenModel>` | weakThis
16 | (16) `std::shared_ptr<std::shared_ptr<LibraryItem> >` | itemTracker
32 | (32) `std::string` | worldId


### `MainMenuScreenModel::getStoreSalesTreatmentQuery::__l2::<lambda_bbaddeb19d2191f22b88b3b436951d98>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MainMenuScreenModel>` | weakModel


### `MinecoinModel`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecoinModel_vtbl *` | __vftable
8 | (8) `Offer *` | mMinecoinOffer
16 | (32) `std::string` | mProductId
48 | (4) `unsigned int` | mCoinCount
52 | (4) `unsigned int` | mBonusCoinCount
56 | (56) `ResourceLocation` | mKeyArtLocation


### `MinecoinCatalogModel::fetchAndHydrate::__l2::<lambda_572de4bfa096cecd80e1e589d96c29d2>::()::__l15::<lambda_d395113aa232aadd9b41637a270f3051>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecoinCatalogModel *const` | __this
8 | (72) `HydrateParams` | params
80 | (16) `std::weak_ptr<bool>` | weakTracker
96 | (32) `const std::string` | productId
128 | (16) `std::shared_ptr<int>` | imageFetchTracker
144 | (32) `std::string` | thumbnailUrl


### `MinecoinCatalogModel::fetchAndHydrate::__l2::<lambda_572de4bfa096cecd80e1e589d96c29d2>::()::__l15::<lambda_d395113aa232aadd9b41637a270f3051>::()::__l2::<lambda_e2fb793f22a037e39d281ac27856873a>::()::__l5::<lambda_7136880f20aafaa0e36e2b033512eec6>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecoinCatalogModel *const` | __this
8 | (16) `std::weak_ptr<bool>` | weakTracker
24 | (32) `const std::string` | productId
56 | (16) `std::shared_ptr<int>` | imageFetchTracker


### `MinecoinCatalogModel::fetchAndHydrate::__l2::<lambda_572de4bfa096cecd80e1e589d96c29d2>::()::__l15::<lambda_d395113aa232aadd9b41637a270f3051>::()::__l2::<lambda_e2fb793f22a037e39d281ac27856873a>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecoinCatalogModel *const` | __this
8 | (16) `std::weak_ptr<bool>` | weakTracker
24 | (32) `const std::string` | productId
56 | (16) `std::shared_ptr<int>` | imageFetchTracker
72 | (32) `std::string` | thumbnailUrl
104 | (24) `const std::vector<std::string>` | treatments


### `MinecraftScreenModel::navigateToOptionsScreen::__l2::<lambda_b90aae995a782c216c4c5f83ec086536>::()::__l5::<lambda_d0f5a644821eaf4d71be4f865ab0164d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakThis
16 | (384) `LevelSummary` | levelSummary
400 | (4) `SettingsTabIndex` | startingTabIndex
404 | (1) `bool` | navToMenuOnExit
405 | (1) `const bool` | maintainOldFocus


### `MinecraftScreenModel::_startLocalServerAsync::__l2::<lambda_6f9cde69521b7bb16bbc43429e7f65bf>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | hasRun
8 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakThis
24 | (32) `std::string` | levelId
56 | (32) `std::string` | levelName
88 | (24) `ContentIdentity` | contentIdentity
112 | (3360) `LevelSettings` | settings


### `MinecraftScreenModel::generateFilePickerSettingsForExport::__l2::<lambda_f0261e3cb677b2caffbab08177b976be>::()::__l5::<lambda_a11fb195ffbab16b56df4de83a818d04>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (1096) `MinecraftScreenModel::generateFilePickerSettingsForExport::__l2::<lambda_f0261e3cb677b2caffbab08177b976be>::()::__l2::<lambda_c8dac7c0f833e525c0b191b85ab07bca>` | exportWorldFnc
1104 | (16) `std::shared_ptr<FilePickerSettings>` | settings


### `MinecraftScreenModel::generateFilePickerSettingsForExport::__l2::<lambda_f0261e3cb677b2caffbab08177b976be>::()::__l2::<lambda_c8dac7c0f833e525c0b191b85ab07bca>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (32) `const std::string` | levelId
40 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | fileStackPath
1080 | (16) `std::shared_ptr<FilePickerSettings>` | settings


### `MinecraftScreenModel::generateFilePickerSettingsForExport::__l2::<lambda_f0261e3cb677b2caffbab08177b976be>::()::__l2::<lambda_c8dac7c0f833e525c0b191b85ab07bca>::()::__l2::<lambda_e6f65051d3acc2c4ce6d89d9942f7127>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (16) `std::shared_ptr<FilePickerSettings>` | settings
24 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | completeFilePath


### `MinecraftScreenModel::_processWorldTemplate::__l13::<lambda_1524be1dfdf8a4ddc334d761b12f8da5>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback
64 | (16) `std::shared_ptr<LevelStorage>` | levelStorage


### `MinecraftScreenModel::_processWorldTemplate::__l2::<lambda_2a72f72cc8199a6a7f602d41ca233968>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (64) `std::function<void __cdecl(bool)>` | callback
72 | (16) `std::shared_ptr<LevelStorage>` | levelStorage


### `MinecraftScreenModel::_processWorldTemplate::__l2::<lambda_2a72f72cc8199a6a7f602d41ca233968>::()::__l2::<lambda_ce75ffb60a5a14b2e3a42d89692a19b5>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback
64 | (16) `std::shared_ptr<LevelStorage>` | levelStorage


### `MinecraftScreenModel::connectToPlatformNetwork::__l2::<lambda_ae8223ad44e307d3b7f2b9a57f7e85d9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakThis
16 | (8) `IMinecraftGame *` | minecraftGame
24 | (64) `std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>` | callback
88 | (1) `bool` | isPrimaryUser
89 | (1) `bool` | isUserInitiated


### `MinecraftScreenModel::pickCustomSkin::__l2::<lambda_d332418f10b6aacb37321b48d4d75356>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum PickCustomSkinResult)>` | callback
64 | (8) `IClientInstance *` | client


### `MinecraftScreenModel::getThirdPartyDisplayPicture::__l2::<lambda_75b7f6c4734f15d209ecc133d2254e94>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakThis
16 | (32) `const std::string` | playerId
48 | (1) `bool` | isLocal
56 | (16) `const std::weak_ptr<Social::User>` | weakUser
72 | (64) `std::function<void __cdecl(Core::Path const &)>` | callback


### `MinecraftScreenModel::getThirdPartyDisplayPicture::__l2::<lambda_75b7f6c4734f15d209ecc133d2254e94>::()::__l2::<lambda_0114feb4e94d7cd6ef629f8df0572acc>`
Offset | Type | Name
-|-|-|-
0 | (56) `const ResourceLocation` | path
56 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakThis
72 | (64) `std::function<void __cdecl(Core::Path const &)>` | callback


### `MinecraftScreenModel::_savePDF::__l2::<lambda_8d03e2209190b5e8be1a5f874ceb7bb1>`
Offset | Type | Name
-|-|-|-
0 | (88) `PDFOptions` | options
88 | (16) `std::shared_ptr<PDFWriter>` | pdfWriter
104 | (16) `std::weak_ptr<MinecraftScreenModel>` | weakModel
120 | (16) `std::shared_ptr<FilePickerSettings>` | settings


### `MinecraftScreenModel::generateFilePickerSettingsForExport::__l2::<lambda_f0261e3cb677b2caffbab08177b976be>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (32) `const std::string` | levelId
40 | (32) `const std::string` | levelName
72 | (1) `bool` | isTemplate


### `MinecraftScreenModel::generateFilePickerSettingsForPDF::__l2::<lambda_c897a00c9a03376a9c9b4864affeee51>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftScreenModel *const` | __this
8 | (88) `PDFOptions` | options


### `MinecraftUIRenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `UIRenderContext` | baseclass_0
8 | (8) `IClientInstance *` | mClient
16 | (8) `ScreenContext *` | mScreenContext
24 | (16) `MinecraftUIMeasureStrategy` | mMeasureStrategy
40 | (4) `float` | mTextAlpha
48 | (8) `UIRepository *` | mUIRepository
56 | (8) `mce::TextureGroup *` | mTextures
64 | (8) `mce::TextureGroup *` | mStoreCacheTextures
72 | (24) `std::vector<MinecraftUIRenderContext::TextItem>` | mTextToDraw
96 | (24) `std::vector<MinecraftUIRenderContext::ImageItem>` | mImagesToDraw
120 | (24) `std::vector<std::unique_ptr<MinecraftUIRenderContext::PersistentMeshItem>>` | mPersistentMeshes
144 | (1) `unsigned __int8` | mStencilRef
148 | (4) `int` | mCurrentPersistentMeshItemIdx
152 | (48) `FontHandle` | mDebugTextFontHandle
200 | (36) `glm::tmat3x3<float,0>` | mCurrentTransformMatrix
240 | (8) `const UIScene *` | mCurrentScene
248 | (20) `std::optional<glm::tvec4<float,0> >` | mSavedOriginalClippingRectangle


### `MinecraftUIMeasureStrategy`
Offset | Type | Name
-|-|-|-
0 | (8) `UIMeasureStrategy` | baseclass_0
8 | (8) `const UIProfanityContext *` | mUIProfanityContext


### `MinecraftInputRenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `InputRenderContext` | baseclass_0
8 | (16) `mce::Color` | mCurrentColor
24 | (48) `FontHandle` | mFontHandle
72 | (24) `std::vector<MinecraftInputRenderContext::TextItem>` | mTextToDraw
96 | (8) `ScreenContext *` | mScreenContext
104 | (8) `Tessellator *` | mTessellator
112 | (72) `mce::TexturePtr` | mTexture


### `MinecraftInputHandler::init::__l14::<lambda_ac238c1b3b5ae4fbed6d6c179fe617ef>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftInputHandler *const` | __this


### `ModelPart`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mName
48 | (12) `Vec3` | mPos
60 | (12) `Vec3` | mOffset
72 | (12) `Vec3` | mRot
84 | (12) `Vec3` | mScale
96 | (12) `Vec3` | mWorldPos
108 | (28) `AABB` | mAABB
136 | (4) `int` | mGroupIndex
140 | (4) `int` | mPartIndex
144 | (4) `int` | mMeshIndex
148 | (4) `int` | mBoneOrientationIndex
152 | (24) `std::vector<ModelPartLocator>` | mLocators
176 | (4) `_BYTE[4]` | mRotationRelativeMode
180 | (1) `bool` | mDebug
184 | (4) `const int` | IndexNotSet
188 | (1) `bool` | mMirror
189 | (1) `bool` | mVisible
192 | (4) `int` | mSkinnedMeshGroupIdentifier
200 | (24) `std::vector<Cube>` | mCubes
224 | (24) `std::vector<ModelPart::TextureMesh>` | mTextureMeshes
248 | (128) `Geometry::NodePolyMesh` | mPolyMesh
376 | (8) `ModelPart *` | mParent
384 | (24) `std::vector<ModelPart *>` | mChildren
408 | (8) `Vec2` | mTexSize
416 | (8) `TextureOffset` | mTexOffs
424 | (1) `bool` | mNeverRender
428 | (12) `Vec3` | mOriginPos
440 | (1) `bool` | mHasColor
448 | (64) `std::unordered_map<RenderController const *,ExpressionNode>` | mIsVisibleMap
512 | (64) `std::unordered_map<RenderController const *,ExpressionNode>` | mMaterialExpressionMap
576 | (28) `AABB` | ?


### `MusicCommand::CommandData`
Offset | Type | Name
-|-|-|-
0 | (1) `MusicCommand::Action` | mAction
8 | (32) `std::string` | mTrackName
40 | (4) `float` | mVolume
44 | (4) `float` | mFadeSeconds
48 | (1) `_BYTE[1]` | mRepeatMode


### `MoveActorAbsoluteData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorRuntimeID` | mRuntimeId
8 | (1) `MoveActorAbsoluteData::Header` | mHeader
12 | (12) `Vec3` | mPos
24 | (1) `char` | mRotX
25 | (1) `char` | mRotY
26 | (1) `char` | mRotYHead


### `MoveActorAbsoluteData::Header`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mRaw
1 | (1) `$47A40755A56C6625356F14B823F76499` | __s1


### `mce::GraphicsDeviceInformation`
Offset | Type | Name
-|-|-|-
0 | (80) `mce::GraphicsAdapterDescription` | mAdapterDescription
80 | (32) `std::string` | mChipsetVendorName
112 | (32) `std::string` | mGraphicsVersion
144 | (32) `std::string` | mGraphicsExtensions
176 | (1) `bool` | mTearingSupport
177 | (1) `bool` | mVertexShaderInstancingSupport
180 | (4) `int` | mScreenWidth
184 | (4) `int` | mScreenHeight


### `mce::GraphicsAdapterDescription`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mDescription
32 | (4) `unsigned int` | mVendorId
36 | (4) `unsigned int` | mDeviceId
40 | (4) `unsigned int` | mSubSysId
44 | (4) `unsigned int` | mRevision
48 | (8) `unsigned __int64` | mDedicatedVideoMemory
56 | (8) `unsigned __int64` | mDedicatedSystemMemory
64 | (8) `unsigned __int64` | mSharedSystemMemory
72 | (8) `unsigned __int64` | mReservedVideoMemory


### `MatrixStack::MatrixStackRef`
Offset | Type | Name
-|-|-|-
0 | (8) `MatrixStack *` | stack
8 | (8) `Matrix *` | mat


### `MobRenderer::getClientTextureFromActorTextureVariant::__l2::ActorVariantVisitor`
Offset | Type | Name
-|-|-|-


### `MovePriorityQueue<std::shared_ptr<BackgroundTaskBase>,BackgroundTaskBase::PendingComparer>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<BackgroundTaskBase>>` | mC


### `mcr::MigrationTextureBinding`
Offset | Type | Name
-|-|-|-


### `mce::FrameBufferAttachmentDescription`
Offset | Type | Name
-|-|-|-
0 | (112) `mce::TextureDescription` | baseclass_0
112 | (4) `mce::FrameBufferAttachmentType` | mFrameBufferAttachmentType
116 | (1) `bool` | mAutomaticLatentResolve


### `mce::framebuilder::RenderItemInHandDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *` | mMesh
8 | (16) `const dragon::res::ServerTexture` | mTexture
24 | (16) `const dragon::res::ServerTexture` | mGlintTexture
40 | (16) `mce::MaterialPtr` | mMaterial
56 | (64) `glm::tmat4x4<float,0>` | mWorldMatrix
120 | (1) `ItemContextFlags` | mItemContextFlags
121 | (1) `bool` | mIsInUIPass
122 | (1) `bool` | mNeedsBlending
123 | (1) `bool` | mNeedsAlphaTest
124 | (16) `glm::tvec4<float,0>` | mGlintColor
140 | (16) `glm::tvec4<float,0>` | mOverlayColor
156 | (16) `glm::tvec4<float,0>` | mChangeColor
172 | (16) `glm::tvec4<float,0>` | mMultiplicativeTintColor
188 | (16) `glm::tvec4<float,0>` | mTileLightColor
204 | (28) `mce::framebuilder::FogDescription` | mFog
232 | (8) `glm::tvec2<float,0>` | mUVOffset
240 | (8) `glm::tvec2<float,0>` | mUVRotation
248 | (8) `glm::tvec2<float,0>` | mUVScale
256 | (2) `const unsigned __int16` | mViewId
264 | (8) `const dragon::RenderMetadata` | mRenderMetadata


### `mce::framebuilder::FogDescription`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,0>` | mColor
16 | (8) `glm::tvec2<float,0>` | mControl
24 | (4) `float` | mRenderDistance


### `mce::ViewportInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,0>` | size
8 | (8) `glm::tvec2<float,0>` | offset
16 | (4) `float` | minDepth
20 | (4) `float` | maxDepth


### `MutableGraphicsFrame`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<MutableGraphicsFrame::Lifetime>` | mLifetime
16 | (32) `ServiceReference<mce::framebuilder::FrameBuilder>` | mFrameBuilder
48 | (40) `mce::framebuilder::FrameConfiguration` | mCurrentConfiguration


### `mce::framebuilder::FrameConfiguration`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<mce::framebuilder::FrameConfiguration::View>` | mViews
24 | (1) `bool` | mIsRayTracingEnabled
32 | (8) `cg::ImageBuffer *` | mTargetImage


### `mce::framebuilder::RenderAtmosphereDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mDimensionIdx
4 | (4) `float` | mFogMaxDensity
8 | (4) `float` | mFogMaxDensityHeight
12 | (4) `float` | mFogZeroDensityHeight
16 | (16) `mce::Color` | mFogAbsorbtion
32 | (16) `mce::Color` | mFogScattering
48 | (16) `mce::Color` | mWaterAbsorbtion
64 | (16) `mce::Color` | mWaterScattering
80 | (16) `mce::Color` | mCloudAbsorbtion
96 | (16) `mce::Color` | mCloudScattering
112 | (4) `float` | mFogStart
116 | (4) `float` | mFogEnd
120 | (4) `float` | mRenderDistance
124 | (4) `float` | mWeatherFogLevel
128 | (4) `float` | mRainLevel
132 | (16) `mce::Color` | mSkyColor
152 | (16) `const dragon::res::ServerTexture` | mSkyTexture
168 | (8) `glm::tvec2<float,0>` | mSkyUVScale


### `mce::framebuilder::BlitFlipbookSingleTextureDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *` | mMesh
8 | (16) `const dragon::res::ServerTexture` | mBlitTexture
24 | (4) `float` | mVBlendFrom
28 | (4) `float` | mVBlendTo
32 | (4) `float` | mVBlendAmount
36 | (24) `mce::ViewportInfo` | mViewportInfo
60 | (1) `dragon::rendering::ClipSpaceOrigin` | mClipSpaceOrigin


### `mce::framebuilder::RenderWeatherDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *` | mMesh
8 | (4) `unsigned int` | mIndexOffset
12 | (4) `unsigned int` | mIndexCount
16 | (64) `glm::tmat4x4<float,0>` | mWorldMatrix
80 | (16) `const dragon::res::ServerTexture` | mWeatherTexture
96 | (16) `const dragon::res::ServerTexture` | mOcclusionTexture
112 | (16) `const dragon::res::ServerTexture` | mLightingTexture
128 | (4) `WeatherRenderObject::PrecipitationType` | mType
132 | (28) `mce::framebuilder::FogDescription` | mFog
160 | (4) `float` | mFarChunkDistance
164 | (16) `glm::tvec4<float,0>` | mPositionBaseOffset
180 | (16) `glm::tvec4<float,0>` | mPositionForwardOffset
196 | (16) `glm::tvec4<float,0>` | mViewPosition
212 | (16) `glm::tvec4<float,0>` | mUVOffsetAndScale
228 | (16) `glm::tvec4<float,0>` | mVelocity
244 | (16) `glm::tvec4<float,0>` | mDimensions
260 | (2) `const unsigned __int16` | mViewId


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::FlushedTransactions`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mCount
8 | (24) `std::vector<std::unique_ptr<mce::IDeferredDebugUpdate>>` | mDeferredDebugUpdates


### `mce::Buffer`
Offset | Type | Name
-|-|-|-
0 | (32) `mce::BufferNull` | baseclass_0


### `mce::BufferNull`
Offset | Type | Name
-|-|-|-
0 | (20) `mce::BufferBase` | baseclass_0
24 | (8) `unsigned __int64` | mDataSize


### `mce::BufferBase`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::BufferType` | mBufferType
4 | (4) `unsigned int` | mStride
8 | (4) `unsigned int` | mCount
12 | (4) `unsigned int` | mInternalSize
16 | (4) `unsigned int` | mBufferOffset


### `mce::ResourceBase<mce::BufferNull>`
Offset | Type | Name
-|-|-|-


### `mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >` | mResourcePointerBlock


### `mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >` | mResourcePointerBlock


### `mce::Texture`
Offset | Type | Name
-|-|-|-
0 | (120) `mce::TextureNull` | baseclass_0
120 | (16) `std::shared_ptr<mce::DragonLifetime>` | mDragonTextureLifetime
136 | (16) `std::optional<unsigned __int64>` | mRenderDragonTexture


### `mce::TextureNull`
Offset | Type | Name
-|-|-|-
0 | (120) `mce::TextureBase` | baseclass_0


### `mce::TextureBase`
Offset | Type | Name
-|-|-|-
0 | (112) `mce::TextureDescription` | textureDescription
112 | (1) `bool` | created
113 | (1) `bool` | mOwnsResource


### `mce::ResourceBase<mce::TextureNull>`
Offset | Type | Name
-|-|-|-


### `mce::ClientResourcePointer<mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr>` | baseclass_0


### `mce::TransactionContainer<mce::CreateTextureTransaction,mce::TextureResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateTextureTransaction &)>` | mDeferredPayload
88 | (128) `mce::CreateTextureTransaction` | mPayload
216 | (8) `gsl::not_null<mce::TextureResourceServiceContext *>` | mResourceServiceContext


### `mce::CreateTextureTransaction`
Offset | Type | Name
-|-|-|-
0 | (112) `mce::TextureDescription` | mTextureDescription
112 | (16) `gsl::basic_string_span<char const ,-1>` | mDebugName


### `mce::TransactionContainer<mce::CreateImmediateBufferTransaction,mce::ImmediateBufferResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateImmediateBufferTransaction &)>` | mDeferredPayload
88 | (40) `mce::CreateImmediateBufferTransaction` | mPayload
128 | (8) `gsl::not_null<mce::BufferResourceServiceContext *>` | mResourceServiceContext


### `mce::CreateImmediateBufferTransaction`
Offset | Type | Name
-|-|-|-
0 | (16) `cg::BufferSpan` | mBufferSpan
16 | (1) `mce::BufferType` | mBufferType
24 | (16) `gsl::basic_string_span<char const ,-1>` | mDebugName


### `mce::RenderMaterial`
Offset | Type | Name
-|-|-|-
0 | (448) `cg::RenderMaterialBase` | baseclass_0
448 | (16) `std::optional<unsigned __int64>` | mCacheKey
464 | (8) `mce::SamplerGroupCache *` | mSamplerGroupCache
472 | (1) `mce::StencilRefObject` | mStencilRefObject
480 | (8) `mce::Shader *` | mShader
488 | (1) `bool` | mExpectedNullShader
492 | (228) `mce::SamplerStateGroup` | mSamplerStateGroup
720 | (30) `mce::VertexFormat` | mVertexFormat
750 | (1) `mce::StencilRefObject` | stencilRefObject
752 | (4) `mce::MSAASupport` | mMsaaSupport
760 | (24) `std::vector<mce::RenderMaterial::PipelineStateObjectVariantPair>` | mPipelineStateObjectVariants
784 | (1) `bool` | mDirtyPipelineState
788 | (4) `float` | mDepthBias
792 | (4) `float` | mSlopeScaledDepthBias
796 | (7) `mce::BlendStateDescription` | blendStateDescription
804 | (24) `mce::DepthStencilStateDescription` | depthStencilStateDescription
828 | (12) `mce::RasterizerStateDescription` | rasterizerStateDescription
840 | (96) `std::array<mce::SamplerStateDescription,8>` | samplerStateDescriptions
936 | (16) `std::set<enum mce::VertexField>` | mVertexFields
952 | (1) `mce::PrimitiveMode` | mPrimitiveMode
960 | (24) `std::vector<enum mce::TextureFormat>` | mDefaultRenderTargetFormats
984 | (24) `std::vector<std::vector<enum mce::TextureFormat>>` | mRenderTargetFormats
1008 | (8) `mce::Shader *` | mTmpCompliedShader


### `mce::StencilRefObject`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `mce::ResourceBase<mce::StencilRefObjectNull>`
Offset | Type | Name
-|-|-|-


### `mce::SamplerStateGroup`
Offset | Type | Name
-|-|-|-
0 | (228) `mce::SamplerStateGroupNull` | baseclass_0


### `mce::SamplerStateGroupNull`
Offset | Type | Name
-|-|-|-
0 | (228) `mce::SamplerStateGroupBase` | baseclass_0


### `mce::SamplerStateGroupBase`
Offset | Type | Name
-|-|-|-
0 | (128) `mce::SamplerState[8]` | mSamplerStates
128 | (96) `mce::SamplerStateDescription[8]` | mSamplerStateDescriptions
224 | (2) `unsigned __int16` | mSamplerCount


### `mce::SamplerState`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::SamplerStateNull` | baseclass_0


### `mce::SamplerStateNull`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::SamplerStateBase` | baseclass_0


### `mce::SamplerStateBase`
Offset | Type | Name
-|-|-|-
0 | (12) `mce::SamplerStateDescription` | mSamplerStateDescription
12 | (2) `unsigned __int16` | mSamplerIndex


### `mce::SamplerStateDescription`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::TextureFiltering` | textureFilter
1 | (3) `mce::TextureWrappingDescription` | textureWrappingDescription
4 | (4) `unsigned int` | shaderStagesBits
8 | (2) `__int16` | samplerIndex
10 | (1) `_BYTE[1]` | comparisonFunc


### `mce::ResourceBase<mce::SamplerStateNull>`
Offset | Type | Name
-|-|-|-


### `mce::ResourceBase<mce::SamplerStateGroupNull>`
Offset | Type | Name
-|-|-|-


### `mce::BlendStateDescription`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | blendSource
1 | (1) `_BYTE[1]` | blendDestination
2 | (1) `_BYTE[1]` | alphaSource
3 | (1) `_BYTE[1]` | alphaDestination
4 | (1) `unsigned __int8` | colorWriteMask
5 | (1) `bool` | enableBlend
6 | (1) `bool` | enableAlphaToCoverage


### `mce::DepthStencilStateDescription`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | depthTestEnabled
1 | (1) `bool` | stencilTestEnabled
2 | (1) `_BYTE[1]` | depthFunc
3 | (4) `mce::StencilFaceDescription` | frontFace
7 | (4) `mce::StencilFaceDescription` | backFace
11 | (1) `mce::DepthWriteMask` | depthWriteMask
12 | (4) `unsigned int` | stencilReadMask
16 | (4) `unsigned int` | stencilWriteMask
20 | (1) `unsigned __int8` | stencilRef
21 | (1) `unsigned __int8` | originalStencilRef
22 | (1) `bool` | overwroteStencilRef


### `mce::StencilFaceDescription`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | stencilFunc
1 | (1) `mce::StencilOp` | stencilDepthFailOp
2 | (1) `mce::StencilOp` | stencilPassOp
3 | (1) `mce::StencilOp` | stencilFailOp


### `mce::RasterizerStateDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | depthBias
4 | (4) `float` | slopeScaledDepthBias
8 | (1) `mce::CullMode` | cullMode
9 | (1) `mce::FillMode` | fillMode


### `mce::TextureGroup::loadTextureSetAsync::__l2::<lambda_a38e5105e4d5277da6834ce3f755e58e>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::TextureGroup *const` | __this
8 | (16) `std::shared_ptr<`mce::TextureGroup::loadTextureSetAsync'::`2'::TextureSetDefinitionHolder>` | asyncTextureSetHolder
24 | (64) `const std::pair<ResourceLocation,enum TextureLoadMode>` | textureQueueKey
88 | (8) `Bedrock::Threading::CountReference` | PendingCount
96 | (16) `mce::PendingTexture` | pendingBit


### `mce::PendingTexture`
Offset | Type | Name
-|-|-|-
0 | (8) `gsl::not_null<enum TextureLoadState *>` | mTextureLoadState
8 | (4) `TextureLoadMode` | mTextureLoadMode


### `mce::TextureGroup::loadTextureSetAsync::__l2::<lambda_1b0dc13e9546238bebba0e3929a83843>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::TextureGroup *const` | __this
8 | (16) `std::shared_ptr<`mce::TextureGroup::loadTextureSetAsync'::`2'::TextureSetDefinitionHolder>` | asyncTextureSetHolder
24 | (64) `const std::pair<ResourceLocation,enum TextureLoadMode>` | textureQueueKey
88 | (4) `const TextureLoadMode` | textureLoadMode
96 | (8) `Bedrock::Threading::CountReference` | PendingCount


### `MinecoinTransactionHandler::transactFulfillment::__l2::<lambda_0c66dafc28dfff5f9d4507cf911e69c4>`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecoinTransactionHandler *const` | __this
8 | (8) `Offer *` | offer
16 | (16) `std::shared_ptr<Purchase>` | purchase
32 | (4) `_BYTE[4]` | path
40 | (32) `std::string` | correlationID


### `mce::ShaderConstantBase`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ShaderConstantBase_vtbl *` | __vftable
8 | (32) `std::string` | name
40 | (4) `unsigned int` | numberOfElements
44 | (4) `unsigned int` | byteOffset
48 | (1) `mce::ShaderPrimitiveTypes` | shaderPrimitiveType
49 | (1) `bool` | dirty


### `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::framebuilder::bgfxbridge::RayTraceableMeshKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const __int64` | mMeshGroupId
8 | (2) `const unsigned __int16` | mSubSpanId
16 | (8) `const mce::Mesh *const` | mMeshPtr


### `mce::framebuilder::bgfxbridge::rtxutils::tryGetRayTraceableMesh::__l2::<lambda_4b615ff85ae31d212785fad20d849080>`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *` | staticMesh
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext
16 | (8) `dragon::rendering::BgfxPrimitiveIndexBuffer *` | quadIndexBuffer


### `mce::framebuilder::bgfxbridge::RayTraceableMeshMetadata`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mAccelerationStructureHandle


### `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >` | mResourcePointerBlock


### `mce::framebuilder::bgfxbridge::rtxutils::tryGetRayTraceableMesh::__l2::<lambda_896978dc0f97ed275fa58bf51ecb582e>`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::framebuilder::RenderSkinnedMeshDescription *` | skinnedMeshDescription


### `mce::framebuilder::bgfxbridge::DefineFlags`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mFlags


### `mce::framebuilder::gamecomponents::PlayerUI`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::ItemInHandObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::TransparentItemInWorldObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_createStaticMeshes::__l2::<lambda_4247d7e55abdc363c5b66aae36ab0825>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | vertexStride


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_createStaticMeshes::__l2::<lambda_7b50bd49a243c4d56d9bfb5f0e1c28cb>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | indexStride
4 | (72) `const std::array<unsigned short,36>` | cubeIndices
76 | (4) `const unsigned int` | numCubeIndices


### `MixerLayer<Biome *,Biome *,bool>`
Offset | Type | Name
-|-|-|-
0 | (24) `Layer<Biome *>` | baseclass_0
24 | (16) `std::shared_ptr<Layer<Biome *> >` | mFirstParent
40 | (16) `std::tuple<std::shared_ptr<Layer<bool> > >` | mMoreParents


### `mce::framebuilder::bgfxbridge::RenderMaterialHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mKey


### `mce::framebuilder::bgfxbridge::MaterialKey`
Offset | Type | Name
-|-|-|-
0 | (1) `mce::framebuilder::bgfxbridge::ShaderType` | mType
4 | (4) `mce::framebuilder::bgfxbridge::DefineFlags` | mDefines


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::createExternalTexture::__l7::<lambda_8c81b13bcd5d75ab3d73ea62009230c1>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *` | textureManager
8 | (8) `cg::TextureDescription *` | defaultDesc


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::createExternalTexture::__l7::<lambda_bb8beb4409003096d51127f9ebf87e1e>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *` | textureManager
8 | (8) `cg::TextureDescription *` | defaultDesc


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::createExternalTexture::__l7::<lambda_99d0f8f794ca1b18902a8edf76995a3b>`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::updateExternalTexture::__l8::<lambda_090298dbd3dcf9d6e3aefc43d02d6da7>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *` | textureManager
8 | (16) `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>` | texture
24 | (64) `std::function<void __cdecl(dragon::rendering::SharedTextureHandle)>` | rendererCallbackUpdateDelegate


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::generateRenderChunkVertexData::__l2::<lambda_1e31737a4636a062c61b82c2159bc65d>`
Offset | Type | Name
-|-|-|-
0 | (176) `const dragon::mesh::VertexFormat` | dragonFormat
176 | (8) `const unsigned __int64` | vertexCount
184 | (24) `std::vector<unsigned char>` | data


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::generateRenderChunkIndexData::__l2::<lambda_686396822c9997e5f56f739d624345a4>`
Offset | Type | Name
-|-|-|-
0 | (4) `const unsigned int` | indexSizeInBytes
4 | (4) `const unsigned int` | indexCount
8 | (24) `std::vector<unsigned char>` | data


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l2::<lambda_43d630b5188acfc25f19f26a18357d3c>`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l2::<lambda_6cf1c25155f42c1baaf07050dffdd3ae>`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::Gameface`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l2::<lambda_29fa73eaeaaf8daefd40d7a5950a900a>`
Offset | Type | Name
-|-|-|-
0 | (176) `dragon::mesh::VertexFormat` | dragonFormat
176 | (4) `unsigned int` | vertexCount
184 | (24) `std::vector<unsigned char>` | data


### `mce::framebuilder::gamecomponents::SceneObjectActors`
Offset | Type | Name
-|-|-|-


### `mce::ServerResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::framebuilder::gamecomponents::VrPresenceObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::WaterHoleObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::InLevelCubeMapObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::EnvironmentalText`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l134::<lambda_dcd123cbf890429ae58c1f10ebaf9f6c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l2::<lambda_64f122915bcebd7da889f016004036d3> *` | layerChunkTransaction


### `mce::framebuilder::gamecomponents::BlendedCracksObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::gamecomponents::LivingRoomSceneObject`
Offset | Type | Name
-|-|-|-


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::_insert::__l2::<lambda_42c898a68a2556d8029159b58af0e944>`
Offset | Type | Name
-|-|-|-
0 | (176) `const dragon::mesh::VertexFormat` | dragonFormat
176 | (4) `const int` | vertexCount
184 | (24) `std::vector<unsigned char>` | data


### `mce::framebuilder::gamecomponents::Atmosphere`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | mSkyColor
16 | (16) `dragon::res::ServerTexture` | mSkyTexture
32 | (8) `glm::tvec2<float,0>` | mSkyUVScale
40 | (4) `unsigned int` | mDimensionIdx
44 | (4) `float` | mFogDensityMultiplier
48 | (4) `float` | mHeightFogStart
52 | (4) `float` | mHeightFogFalloffHeight
56 | (16) `mce::Color` | mFogAbsorbtion
72 | (16) `mce::Color` | mFogScattering
88 | (16) `mce::Color` | mWaterAbsorbtion
104 | (16) `mce::Color` | mWaterScattering
120 | (16) `mce::Color` | mCloudAbsorbtion
136 | (16) `mce::Color` | mCloudScattering
152 | (4) `float` | mFogStart
156 | (4) `float` | mFogEnd
160 | (4) `float` | mRenderDistance
164 | (4) `float` | mWeatherFogLevel
168 | (4) `float` | mRainLevel


### `mce::framebuilder::RenderBannerDescription`
Offset | Type | Name
-|-|-|-
0 | (120) `boost::container::static_vector<glm::tvec4<float,0>,7>` | mBannerColors
120 | (120) `boost::container::static_vector<glm::tvec4<float,0>,7>` | mBannerUVOffsetsAndScales


### `mce::framebuilder::RenderCracksOverlayBlockEntityDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::framebuilder::RenderSkinnedMeshDescription *` | mSkinnedMeshDescription
8 | (8) `glm::tvec2<float,0>` | mUVScale


### `mce::framebuilder::RenderBlockSelectionOverlayBlockEntityDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::framebuilder::RenderSkinnedMeshDescription *` | mSkinnedMeshDescription


### `mce::Font::RenderingParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mGlyphSmoothRadius
4 | (4) `float` | mGlyphCutoff
8 | (4) `float` | mOutlineCutoff
12 | (16) `glm::tvec4<float,0>` | mOutlineColor
28 | (4) `float` | mShadowSmoothRadius
32 | (16) `glm::tvec4<float,0>` | mShadowColor
48 | (8) `glm::tvec2<float,0>` | mShadowOffset
56 | (1) `bool` | mGrayScale
60 | (4) `mce::Font::Type` | mFontType


### `mce::framebuilder::gamecomponents::LivingRoomViewFilter`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mViewWidth
2 | (2) `unsigned __int16` | mViewHeight


### `mce::framebuilder::bgfxbridge::makeMeshFilter::__l8::<lambda_1e5621da2dd3d5f393a9a062234977a9>`
Offset | Type | Name
-|-|-|-
0 | (176) `const dragon::mesh::VertexFormat` | dragonFormat
176 | (4) `const int` | vertexCount
184 | (24) `std::vector<unsigned char>` | data


### `mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>` | baseclass_0


### `mce::framebuilder::modules::declareTerrainAtlasBlitTask::__l5::<lambda_39f8040220cedd22130c1d3ce5ea5193>`
Offset | Type | Name
-|-|-|-
0 | (64) `dragon::materials::MaterialUniformOverrides` | overrides


### `mce::framebuilder::bgfxbridge::GraphicsFrameContext`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGfx
8 | (8) `dragon::framegraph::Declarator<dragon::rendering::RenderContext> *` | mDecl
16 | (8) `dragon::materials::MaterialUniformOverrides *` | mGlobalUniformOverrides
24 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | mAllocator
32 | (32) `dragon::rendering::details::MaterialBind` | mChunkTex
64 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | mFrame
72 | (8) `const mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources *` | mFrameRendererResources
80 | (96) `std::optional<dragon::frameobject::FrameExplicitTarget>` | mTarget


### `mce::framebuilder::bgfxbridge::PassCamera`
Offset | Type | Name
-|-|-|-
0 | (280) `const dragon::rendering::Camera` | mCamera
280 | (24) `const dragon::rendering::ViewSet` | mViewSet


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >>` | mPendingTransactionHandles


### `mpmc::Sender<std::function<void __cdecl(void)> >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<MPMCQueue<std::function<void __cdecl(void)> > >` | mQueue


### `mce::framebuilder::bgfxbridge::PlayerView`
Offset | Type | Name
-|-|-|-
0 | (280) `const dragon::rendering::Camera` | mSceneCamera
280 | (280) `const dragon::rendering::Camera` | mPlayerItemInHandCamera
560 | (288) `const std::optional<dragon::rendering::Camera>` | mUICamera
848 | (24) `const std::vector<unsigned short>` | mViewSets


### `mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources`
Offset | Type | Name
-|-|-|-
0 | (192) `mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources` | baseclass_0


### `mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources`
Offset | Type | Name
-|-|-|-
0 | (64) `dragon::frameobject::FrameRendererResources` | baseclass_0
64 | (8) `const cg::math::Rect<unsigned short>` | mScreenViewport
72 | (24) `const std::vector<mce::framebuilder::bgfxbridge::PlayerView>` | mPlayerViews
96 | (24) `const std::vector<dragon::rendering::Camera>` | mDebugCameras
120 | (16) `const dragon::res::ServerTexture` | mTerrainAtlasTextureHandle
136 | (40) `const std::optional<mce::framebuilder::bgfxbridge::UITarget>` | mPersistentUITarget
176 | (8) `const cg::math::Rect<unsigned short>` | mPersistentUIRect
184 | (8) `const mce::framebuilder::bgfxbridge::FrameExtractorMaterials *` | mMaterials


### `mce::framebuilder::bgfxbridge::UITarget`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | mColor
16 | (16) `dragon::res::ServerTexture` | mDepth


### `mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources`
Offset | Type | Name
-|-|-|-
0 | (192) `mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources` | baseclass_0
192 | (8) `const dragon::rendering::RayTracingResources *` | mRayTracingResources


### `mce::framebuilder::BgfxFrameBuilder::endFrame::__l2::<lambda_cbdc984cb883648ce5a643aae63d5422>`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | allocator
8 | (16) `std::shared_ptr<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >` | frame
24 | (8) `std::unique_ptr<dragon::platform::BgfxContext> *` | context
32 | (16) `std::shared_ptr<dragon::frameobject::FrameRenderer<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >` | renderer
48 | (96) `std::optional<dragon::frameobject::FrameExplicitTarget>` | targetImageWrapper


### `mce::framebuilder::BgfxFrameBuilder::setTerrainAtlasTexture::__l2::<lambda_f66434dd3ba885a057ef1298c806b300>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::BgfxFrameBuilder *const` | __this
8 | (16) `const mce::ClientTexture` | texture


### `mce::framebuilder::bgfxbridge::EntityCreationContext`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | mAllocator
8 | (1) `dragon::rendering::ClipSpaceOrigin` | clipSaceOrigin
16 | (8) `dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | mFrame
24 | (8) `dragon::rendering::GraphicsTasks *` | mGraphicsTasks
32 | (8) `dragon::rendering::AsyncTasksScope *` | mAsyncTasks
40 | (8) `dragon::VertexBufferResourceService *` | mVbResourceService
48 | (8) `dragon::IndexBufferResourceService *` | mIbResourceService
56 | (8) `dragon::AccelerationStructureResourceService *` | mAsResourceService
64 | (8) `dragon::mesh::VertexDeclManager *` | mVertexDeclManager
72 | (8) `dragon::rendering::BgfxPrimitiveIndexBuffer *` | mQuadIndexBuffer
80 | (8) `dragon::rendering::BgfxPrimitiveIndexBuffer *` | mSequenceIndexBuffer
88 | (8) `dragon::materials::MaterialResourceManager *` | mMaterialsManager


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::insert::__l2::<lambda_865bec86ccfdea79ed88812b7f77021f>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor *` | frameExtractor
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::insert::__l2::<lambda_c8d72bf576c9c8a362542257df972acd>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor *` | frameExtractor
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::insert::__l2::<lambda_ad4f63a451bb7c5eccdca3106916db60>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor *` | frameExtractor
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::insert::__l2::<lambda_6baa1b05e36fe68fda960d68fee6c12e>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor *` | frameExtractor
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext


### `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::insert::__l2::<lambda_a1ac28a76ec46cf23bda31dc03cba3f0>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor *` | frameExtractor
8 | (8) `const mce::framebuilder::bgfxbridge::EntityCreationContext *` | entityContext


### `mce::CreateTextureFromUnownedContainerTransaction`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<mce::TextureContainer const >` | mContainer
8 | (16) `gsl::basic_string_span<char const ,-1>` | mDebugName


### `mce::TransactionContainer<mce::CreateTextureFromOwnedContainerTransaction,mce::TextureResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateTextureFromOwnedContainerTransaction &)>` | mDeferredPayload
88 | (168) `mce::CreateTextureFromOwnedContainerTransaction` | mPayload
256 | (8) `gsl::not_null<mce::TextureResourceServiceContext *>` | mResourceServiceContext


### `mce::CreateTextureFromOwnedContainerTransaction`
Offset | Type | Name
-|-|-|-
0 | (136) `mce::TextureContainer` | mContainer
136 | (32) `std::string` | mDebugName


### `mce::TransactionContainer<mce::CreateTextureFromUnownedContainerTransaction,mce::TextureResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateTextureFromUnownedContainerTransaction &)>` | mDeferredPayload
88 | (24) `mce::CreateTextureFromUnownedContainerTransaction` | mPayload
112 | (8) `gsl::not_null<mce::TextureResourceServiceContext *>` | mResourceServiceContext


### `mce::Mesh::_loadRawData::__l2::<lambda_c509ec6bac3b65e68e4de08430a60571>`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *const` | __this
8 | (8) `const unsigned int *` | vertexCount
16 | (8) `unsigned __int8 *const *` | rawData
24 | (8) `const gsl::basic_string_span<char const ,-1> *` | debugName


### `mce::framebuilder::RenderMeshFallbackDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `const mce::Mesh *` | mMesh
8 | (136) `boost::container::static_vector<dragon::res::ServerTexture,8>` | mTextures
144 | (64) `glm::tmat4x4<float,0>` | mWorldMatrix
208 | (12) `glm::tvec3<float,0>` | mSortOrigin
220 | (1) `bool` | mIsUI
221 | (1) `bool` | mIsDrawingFirstPersonObjects
222 | (1) `bool` | mIsDrawingInLevelCubeMap
223 | (1) `bool` | mEnvironmentalText
224 | (16) `mce::Color` | mCurrentColorUniform
240 | (16) `mce::Color` | mDarkenUniform
256 | (16) `mce::MaterialPtr` | mOldMat
272 | (8) `const mce::GlobalConstantBuffers *` | mConstants
280 | (16) `glm::tvec4<float,0>` | mUVAnim
296 | (4) `float` | mHudOpacity
300 | (28) `mce::framebuilder::FogDescription` | mFog
328 | (20) `std::optional<glm::tvec4<float,0> >` | mClipRegion
348 | (2) `const unsigned __int16` | mViewId
352 | (8) `const dragon::RenderMetadata` | mRenderMetadata


### `mce::TransactionContainer<mce::CreateBufferTransaction,mce::BufferResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(mce::CreateBufferTransaction &)>` | mDeferredPayload
88 | (104) `mce::CreateBufferTransaction` | mPayload
192 | (8) `gsl::not_null<mce::BufferResourceServiceContext *>` | mResourceServiceContext


### `mce::CreateBufferTransaction`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | mBufferDescription
8 | (24) `std::vector<unsigned char>` | mBufferData
32 | (1) `mce::BufferType` | mBufferType
40 | (32) `std::string` | mDebugName
72 | (30) `mce::VertexFormat` | mVertexFormat


### `mce::UpdateBufferTransaction`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | mBufferDescription
8 | (24) `std::vector<unsigned char>` | mBufferData
32 | (32) `std::string` | mDebugName


### `mce::RenderMaterial::PipelineStateObjectVariantPair`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::PipelineStateObjectVariantKey` | key
16 | (16) `std::shared_ptr<mce::PipelineStateObject>` | pso


### `mce::PipelineStateObjectVariantKey`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::PipelineStateObjectVariantKeyNull` | baseclass_0


### `mce::PipelineStateObjectVariantKeyNull`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::PipelineStateObjectVariantKeyBase` | baseclass_0


### `mce::PipelineStateObjectVariantKeyBase`
Offset | Type | Name
-|-|-|-
0 | (8) `$AA70263B83BB5476A8C7C7860796DC53` | ___u0
8 | (2) `__int16` | sampleDescriptionCount


### `mce::ResourceBase<mce::PipelineStateObjectVariantKeyNull>`
Offset | Type | Name
-|-|-|-


### `mce::CreateBufferTransaction::apply::__l15::<lambda_89ff1010936644b0319320dbb7511a4e>`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | bufferDescription
8 | (24) `std::vector<unsigned char>` | bufferData
32 | (32) `std::string` | debugName


### `mce::CreateBufferTransaction::apply::__l14::<lambda_f49f49f8ced5468e7e17ea028dc2ea86>`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | bufferDescription
8 | (30) `mce::VertexFormat` | vertexFormat
40 | (24) `std::vector<unsigned char>` | bufferData
64 | (32) `std::string` | debugName


### `mce::IndexBufferContainer::loadIndexBuffer::__l29::<lambda_6311c026061ac77b741722eff3b8f476>`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned int *` | stride
8 | (8) `const unsigned int *` | count
16 | (8) `const unsigned __int8 *const *` | data
24 | (8) `const gsl::basic_string_span<char const ,-1> *` | debugName


### `MolangQueryFunction`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<MolangScriptArg const & __cdecl(RenderParams &,std::vector<ExpressionNode> const &)>` | mAccessor
64 | (32) `std::string` | mDocumentation
96 | (8) `unsigned __int64` | mMinArgumentCount
104 | (8) `unsigned __int64` | mMaxArgumentCount
112 | (1) `bool` | mIsExperimentalFunction
120 | (8) `_BYTE[8]` | mFunctionReturnType


### `MobEffectComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mEffectRange
4 | (4) `int` | mEffectId
8 | (4) `int` | mEffectTime
16 | (64) `ActorFilterGroup` | mEntityFilter


### `MobEffectSystem::tick::__l2::<lambda_b598a11a07d52c4b9e84cd2d7c890e69>`
Offset | Type | Name
-|-|-|-
0 | (8) `MobEffectSystem *const` | __this


### `MoveControlComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mHasWanted
4 | (12) `Vec3` | mWantedPosition
16 | (1) `bool` | mShouldBreach
20 | (4) `float` | mMaxTurn
24 | (4) `float` | mSpeedModifier
32 | (16) `std::shared_ptr<MoveControl>` | mMoveControl


### `MapItemTrackedActor::UniqueId`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | type
8 | (8) `ActorUniqueID` | keyEntityId
16 | (12) `BlockPos` | keyBlockPos


### `MoveActorDeltaData`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorRuntimeID` | mRuntimeId
8 | (2) `MoveActorDeltaData::Header` | mHeader
12 | (4) `float` | mNewPositionX
16 | (4) `float` | mNewPositionY
20 | (4) `float` | mNewPositionZ
24 | (1) `char` | mRotX
25 | (1) `char` | mRotY
26 | (1) `char` | mRotYHead
32 | (32) `MoveActorAbsoluteData` | mPreviousData


### `MoveActorDeltaData::Header`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mRaw
1 | (2) `$F6B22BA5FFEFB0263AA7B63FD39E3332` | __s1


### `MobEquipmentPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (248) `ItemStack` | mItem
296 | (4) `int` | mSlot
300 | (4) `int` | mSelectedSlot
304 | (1) `bool` | mIsServerSide
305 | (1) `ContainerID` | mContainerId
306 | (1) `unsigned __int8` | mSlotByte
307 | (1) `unsigned __int8` | mSelectedSlotByte
308 | (1) `unsigned __int8` | mContainerIdByte


### `ModEffectPacket::ModEffectEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mModId
4 | (4) `float` | mColorR
8 | (4) `float` | mColorG
12 | (4) `float` | mColorB
16 | (32) `std::string` | mResourceName
48 | (32) `std::string` | mIconName


### `MapSample`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | mColor
16 | (8) `const Block *` | mBlock
24 | (2) `__int16` | mHeight


### `MobArmorEquipmentPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mRuntimeId
48 | (248) `ItemStack` | mHead
296 | (248) `ItemStack` | mTorso
544 | (248) `ItemStack` | mLegs
792 | (248) `ItemStack` | mFeet


### `MolangProgramBuildState`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mUsedRegCount
8 | (1) `bool` | mStoreStackState
16 | (24) `std::vector<std::function<void __cdecl(MolangEvalParams &)>>` | mDestProgram


### `MolangVariable`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mName
48 | (88) `MolangScriptArg` | mValue
136 | (88) `MolangScriptArg` | mPublicValue
224 | (16) `MolangVariableSettings` | mSettings


### `MolangVariableSettings`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mIndex
4 | (4) `MolangVariableSetting_AccessSpecifier` | mAccessSpecifier
8 | (4) `_BYTE[4]` | mShouldSync
12 | (4) `_BYTE[4]` | mShouldSave


### `MolangUpdateSystem::tick::__l5::<lambda_acb985f9c150c7ab03f991a539dcac19>`
Offset | Type | Name
-|-|-|-


### `MobSpawnRules`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMinBrightness
4 | (4) `int` | mMaxBrightness
8 | (4) `float` | mMinMoonBrightness
12 | (4) `float` | mMaxMoonBrightness
16 | (1) `bool` | mAdjustForWeather
20 | (4) `int` | mMinHeight
24 | (4) `int` | mMaxHeight
28 | (4) `int` | mRarity
32 | (4) `int` | mSurfaceCap
36 | (4) `int` | mUndergroundCap
40 | (4) `Difficulty` | mMinDifficulty
44 | (4) `Difficulty` | mMaxDifficulty
48 | (4) `int` | mMinSpawnDistance
52 | (4) `int` | mMaxSpawnDistance
56 | (4) `int` | mSpawnDistanceCap
60 | (1) `bool` | mSurfaceSpawner
61 | (1) `bool` | mUndergroundSpawner
62 | (1) `bool` | mWaterSpawner
63 | (1) `bool` | mLavaSpawner
64 | (4) `unsigned int` | mPlayerInVillageDistance
68 | (4) `unsigned int` | mPlayerInVillageBorderTolerance
72 | (1) `bool` | mExperimentalSpawner
80 | (8) `unsigned __int64` | mMinWorldAge
88 | (8) `unsigned __int64` | mMaxWorldAge
96 | (4) `int` | mMinDelay
100 | (4) `int` | mMaxDelay
104 | (24) `std::vector<MobSpawnHerdInfo>` | mHerdList
128 | (24) `std::vector<MobSpawnerPermutation>` | mPermutationList
152 | (32) `std::string` | mMobEventName
184 | (64) `std::unordered_set<BlockLegacy const *>` | mSpawnOnBlockList
248 | (64) `std::unordered_set<BlockLegacy const *>` | mSpawnOnBlockPreventedList
312 | (24) `std::vector<MobSpawnerPermutation>` | mGuaranteedList
336 | (32) `std::string` | mMobToDelayId
368 | (4) `int` | mDelaySpawnChance
372 | (1) `bool` | mPersistence


### `MobSpawnerData`
Offset | Type | Name
-|-|-|-
0 | (4) `WeighedRandom::WeighedRandomItem` | baseclass_0
8 | (176) `ActorDefinitionIdentifier` | mIdentifier
184 | (376) `MobSpawnRules` | mSpawnRules
560 | (64) `std::function<void __cdecl(std::vector<Mob *> &,Random &)>` | mOnSpawnHerd
624 | (64) `std::function<ActorDefinitionIdentifier __cdecl(Random &)>` | mOnSelectEntity


### `Mob::JumpPreventionResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mJumpIsPrevented
4 | (12) `BlockPos` | mPreventingBlockBlockPos


### `MaterialReducerInputValidationState::getAllowedInSlotCallback::__l2::<lambda_712f226a04b1f0d9adf965ed2f0fa152>`
Offset | Type | Name
-|-|-|-
0 | (336) `MaterialReducerInputValidationState` | state


### `MaterialReducerInputValidationState`
Offset | Type | Name
-|-|-|-
0 | (72) `BlockReducer` | mBlockReducer
72 | (264) `CraftableCompounds` | mCraftableCompounds


### `MountTamingEvent`
Offset | Type | Name
-|-|-|-
0 | (24) `WeakRefT<EntityRefTraits>` | mRider
24 | (24) `WeakRefT<EntityRefTraits>` | mMount


### `MapItem::_scheduleMapChunkRendering::__l2::<lambda_14c9cbcd8873e01715361a180f9da00a>`
Offset | Type | Name
-|-|-|-
0 | (8) `Dimension *` | dimension
8 | (16) `std::shared_ptr<std::vector<unsigned int> >` | pixels
24 | (8) `ActorUniqueID` | uuid
32 | (16) `MapItemSavedData::ChunkBounds` | bb
48 | (16) `std::shared_ptr<bool>` | chunksRefCount


### `MapItemSavedData::ChunkBounds`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | x0
4 | (4) `unsigned int` | z0
8 | (4) `unsigned int` | x1
12 | (4) `unsigned int` | z1


### `MapItem::_scheduleMapChunkRendering::__l2::<lambda_acc1ef23d8ccb53aae72c55e69d8c265>`
Offset | Type | Name
-|-|-|-
0 | (8) `Dimension *` | dimension
8 | (16) `std::shared_ptr<std::vector<unsigned int> >` | pixels
24 | (12) `BlockPos` | origin
36 | (4) `int` | scale
40 | (16) `MapItemSavedData::ChunkBounds` | bb


### `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BlockTickingQueue::BlockTick>` | mC


### `MobileAuthenticateScreenController::setupCallbacksForStringOption::__l2::<lambda_31836c078e3d35786732ec89b9d0f39e>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::string __cdecl(void)>` | getValue


### `MobileAuthenticateScreenController::setupCallbacksForStringOption::__l2::<lambda_8245dd556b6f5c0926ed70600b52b3a7>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(std::string const &)>` | setValue
64 | (64) `std::function<bool __cdecl(std::string const &)>` | changedValidator
128 | (64) `std::function<bool __cdecl(void)>` | isEnabled


### `mce::TransactionContainer<dragon::res::CreatePoolTextureTransaction,dragon::TextureResourceService,mce::ImmediateExecutionPolicy>`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::ITransactionContainer` | baseclass_0
8 | (16) `std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >` | mResourceTransactionPointer
24 | (64) `std::function<void __cdecl(dragon::res::CreatePoolTextureTransaction &)>` | mDeferredPayload
88 | (112) `dragon::res::CreatePoolTextureTransaction` | mPayload
200 | (8) `gsl::not_null<dragon::TaskQueueContext *>` | mResourceServiceContext


### `MouseInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<MouseButtonBinding>` | buttonBindings
24 | (24) `std::vector<std::string>` | wheelUpButtonNames
48 | (24) `std::vector<std::string>` | wheelDownButtonNames
72 | (1) `bool` | invertYAxis


### `MesaSurfaceAttributes`
Offset | Type | Name
-|-|-|-
0 | (112) `BlockDescriptor` | mClayMaterial
112 | (112) `BlockDescriptor` | mHardClayMaterial
224 | (1) `bool` | mBrycePillars
225 | (1) `bool` | mHasForest


### `MegaTreeTrunk::_buildSchema::__l4::<lambda_8234dfabad7939141cb7e102ba0eb4d5>`
Offset | Type | Name
-|-|-|-


### `MegaTreeTrunk::_buildSchema::__l7::<lambda_f5fcd0fac45f65f4ed833f4a16e89794>`
Offset | Type | Name
-|-|-|-


### `MemoryMappedFileAccess::StreamDetails`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | mStream
24 | (1) `bool` | mReadAllowed
25 | (1) `bool` | mWriteAllowed
26 | (1) `bool` | mAlwaysWriteAtEnd
27 | (1) `bool` | mDirty


### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *>` | producerListTail
8 | (4) `std::atomic<unsigned int>` | producerCount
16 | (8) `std::atomic<unsigned __int64>` | initialBlockPoolIndex
24 | (8) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *` | initialBlockPool
32 | (8) `unsigned __int64` | initialBlockPoolSize
40 | (8) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block>` | freeList
48 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *>` | implicitProducerHash
56 | (8) `std::atomic<unsigned __int64>` | implicitProducerHashCount
64 | (24) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash` | initialImplicitProducerHash
88 | (512) `std::array<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32>` | initialImplicitProducerHashEntries
600 | (4) `std::atomic_flag` | implicitProducerHashResizeInProgress
604 | (4) `std::atomic<unsigned int>` | nextExplicitConsumerId
608 | (4) `std::atomic<unsigned int>` | globalExplicitConsumerOffset


### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *>` | freeListHead


### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | capacity
8 | (8) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *` | entries
16 | (8) `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *` | prev


### `MultibyteEncodeBuffer`
Offset | Type | Name
-|-|-|-
0 | (8) `const wchar_t *` | inbuf
8 | (8) `const wchar_t *` | inbuf_top
16 | (8) `const wchar_t *` | inbuf_end
24 | (8) `unsigned __int8 *` | outbuf
32 | (8) `unsigned __int8 *` | outbuf_end
40 | (8) `_object *` | excobj
48 | (8) `_object *` | outobj


### `MultibyteCodec_State`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | p
1 | (4) `int` | i
2 | (8) `unsigned __int8[8]` | c
3 | (8) `unsigned __int16[4]` | u2
4 | (8) `unsigned int[2]` | u4


### `MultibyteDecodeBuffer`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int8 *` | inbuf
8 | (8) `const unsigned __int8 *` | inbuf_top
16 | (8) `const unsigned __int8 *` | inbuf_end
24 | (8) `wchar_t *` | outbuf
32 | (8) `wchar_t *` | outbuf_end
40 | (8) `_object *` | excobj
48 | (8) `_object *` | outobj


### `md5_state_s`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int[2]` | count
8 | (16) `unsigned int[4]` | abcd
24 | (64) `unsigned __int8[64]` | buf


### `MobEffect`
```
const struct __cppobj MobEffect
{
  MobEffect_vtbl *__vftable /*VFT*/;
  const unsigned int mId;
  bool mIsHarmful;
  mce::Color mColor;
  std::string mDescriptionId;
  int mIcon;
  float mDurationModifier;
  bool mIsDisabled;
  std::string mResourceName;
  std::string mIconName;
  bool mEffectVisible;
  int mModEffectNum;
  std::unordered_map<int,ModMobEffect> mModEffectsById;
  std::unordered_map<std::string,int> mModIdByName;
  HashedString mComponentName;
  std::shared_ptr<Amplifier> mValueAmplifier;
  std::shared_ptr<Amplifier> mDurationAmplifier;
  std::vector<std::pair<Attribute const *,std::shared_ptr<AttributeBuff> >> mAttributeBuffs;
  std::vector<std::pair<Attribute const *,std::shared_ptr<AttributeModifier> >> mAttributeModifiers;
};

```

### `MobEffect_vtbl`
```
struct /*VFT*/ MobEffect_vtbl
{
  void (__fastcall *~MobEffect)(MobEffect *this);
  void (__fastcall *applyEffects)(MobEffect *this, Actor *, int, int);
  void (__fastcall *removeEffects)(MobEffect *this, Actor *);
  void (__fastcall *applyInstantaneousEffect)(MobEffect *this, Actor *, Actor *, Actor *, int, float, const MobEffectInstance *, bool);
  bool (__fastcall *isInstantaneous)(MobEffect *this);
  float (__fastcall *getAttributeModifierValue)(MobEffect *this, int, const AttributeModifier *);
};

```

### `ModMobEffect`
```
struct __cppobj ModMobEffect
{
  mce::Color mColor;
  std::string mResourceName;
  std::string mIconName;
};

```

### `mce::SamplerStateHeapEntryBase`
```
struct __cppobj mce::SamplerStateHeapEntryBase
{
  unsigned __int16 mHeapIndex;
};

```

### `mce::SamplerStateHeapEntryNull`
```
struct __cppobj mce::SamplerStateHeapEntryNull : mce::SamplerStateHeapEntryBase
{
};

```

### `mce::ResourceBase<mce::SamplerStateHeapEntryNull>`
```
struct __cppobj mce::ResourceBase<mce::SamplerStateHeapEntryNull>
{
};

```

### `mce::SamplerStateHeapEntry`
```
struct __cppobj mce::SamplerStateHeapEntry : mce::SamplerStateHeapEntryNull, mce::ResourceBase<mce::SamplerStateHeapEntryNull>
{
};

```

### `mce::StencilRefObjectNull`
```
struct __cppobj mce::StencilRefObjectNull
{
};

```

### `mce::ShaderProgramBase`
```
struct __cppobj __declspec(align(8)) mce::ShaderProgramBase
{
  const std::string mHeader;
  const std::string mShaderSignature;
  const Core::PathBuffer<std::string > mShaderPath;
  const mce::ShaderType mShaderType;
  bool mValid;
};

```

### `mce::ShaderProgramNull`
```
struct __cppobj mce::ShaderProgramNull : mce::ShaderProgramBase
{
};

```

### `mce::ResourceBase<mce::ShaderProgramNull>`
```
struct __cppobj mce::ResourceBase<mce::ShaderProgramNull>
{
};

```

### `mce::ShaderProgram`
```
struct __cppobj mce::ShaderProgram : mce::ShaderProgramNull, mce::ResourceBase<mce::ShaderProgramNull>
{
};

```

### `mce::ShaderBase`
```
struct __cppobj __declspec(align(8)) mce::ShaderBase
{
  unsigned int attributeListIndex;
  mce::ShaderProgram *vertexShader;
  mce::ShaderProgram *fragmentShader;
  mce::ShaderProgram *geometryShader;
  bool mReflected;
};

```

### `mce::ShaderNull`
```
struct __cppobj mce::ShaderNull : mce::ShaderBase
{
};

```

### `mce::ResourceBase<mce::ShaderNull>`
```
struct __cppobj mce::ResourceBase<mce::ShaderNull>
{
};

```

### `mce::Shader`
```
struct __cppobj mce::Shader : mce::ShaderNull, mce::ResourceBase<mce::ShaderNull>
{
};

```

### `mce::PipelineStateObjectBase`
```
struct __cppobj mce::PipelineStateObjectBase
{
};

```

### `mce::BlendStateBase`
```
struct __cppobj mce::BlendStateBase
{
  mce::BlendStateDescription blendStateDescription;
};

```

### `mce::BlendStateNull`
```
struct __cppobj mce::BlendStateNull : mce::BlendStateBase
{
  bool enableBlend;
};

```

### `mce::DepthStencilStateBase`
```
struct __cppobj mce::DepthStencilStateBase
{
  mce::DepthStencilStateDescription depthStencilStateDescription;
};

```

### `mce::DepthStencilStateNull`
```
struct __cppobj mce::DepthStencilStateNull : mce::DepthStencilStateBase
{
};

```

### `mce::RasterizerStateBase`
```
struct __cppobj mce::RasterizerStateBase
{
  mce::RasterizerStateDescription rasterizerStateDescription;
};

```

### `mce::RasterizerStateNull`
```
struct __cppobj mce::RasterizerStateNull : mce::RasterizerStateBase
{
};

```

### `mce::PipelineStateObjectNull`
```
struct __cppobj mce::PipelineStateObjectNull : mce::PipelineStateObjectBase
{
  mce::BlendStateNull mBlendState;
  mce::DepthStencilStateNull mDepthStencilState;
  mce::RasterizerStateNull mRasterizerState;
};

```

### `mce::ResourceBase<mce::PipelineStateObjectNull>`
```
struct __cppobj mce::ResourceBase<mce::PipelineStateObjectNull>
{
};

```

### `mce::PipelineStateObject`
```
struct __cppobj mce::PipelineStateObject : mce::PipelineStateObjectNull, mce::ResourceBase<mce::PipelineStateObjectNull>
{
};

```

### `mce::RenderMaterial_vtbl`
```
struct /*VFT*/ mce::RenderMaterial_vtbl
{
  void (__fastcall *~RenderMaterialBase)(cg::RenderMaterialBase *this);
  void (__fastcall *parseRuntimeStates)(cg::RenderMaterialBase *this, const Json::Value *);
  void (__fastcall *appendShaderPathForGfxAPI)(cg::RenderMaterialBase *this);
  std::string *(__fastcall *buildHeader)(cg::RenderMaterialBase *this, std::string *result, const std::set<std::string> *);
  void (__fastcall *parseShader)(cg::RenderMaterialBase *this, const Json::Value *);
};

```

### `mce::RenderMaterialInfo`
```
struct __cppobj mce::RenderMaterialInfo : std::enable_shared_from_this<mce::RenderMaterialInfo>
{
  HashedString mHashedName;
  std::unique_ptr<mce::RenderMaterial> mPtr;
};

```

### `mce::PerFrameHandleTracker`
```
struct __cppobj __declspec(align(2)) mce::PerFrameHandleTracker
{
  std::atomic<unsigned short> mCheckCount;
  std::atomic<bool> mIsValid;
};

```

### `mce::DragonLifetime`
```
struct __cppobj mce::DragonLifetime
{
  mce::DragonLifetime_vtbl *__vftable /*VFT*/;
};

```

### `mce::DragonLifetime_vtbl`
```
struct /*VFT*/ mce::DragonLifetime_vtbl
{
  void (__fastcall *~DragonLifetime)(mce::DragonLifetime *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $C121F4620A648719078F94D5C15923F7 ___u0;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::details::ConcurrentQueueProducerTypelessBase`
```
struct __cppobj moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::details::ConcurrentQueueProducerTypelessBase *next;
  std::atomic<bool> inactive;
  moodycamel::ProducerToken *token;
};

```

### `moodycamel::ProducerToken`
```
struct __cppobj moodycamel::ProducerToken
{
  moodycamel::details::ConcurrentQueueProducerTypelessBase *producer;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::function<void __cdecl(void)> >`
```
struct __cppobj MPMCQueue<std::function<void __cdecl(void)> >
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>
{
  std::shared_ptr<dragon::res::TextureDescription> mDebugInfoBlock;
  mce::PerFrameHandleTracker mTrackingBlock;
  std::unique_ptr<dragon::res::ResolvedTextureResource> mResource;
};

```

### `mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription>
{
  std::shared_ptr<mce::ResourceServiceTextureDescription> mDebugInfoBlock;
  mce::PerFrameHandleTracker mTrackingBlock;
  std::unique_ptr<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>> mResource;
};

```

### `ModelPartLocator`
```
struct __cppobj ModelPartLocator
{
  _BYTE mSkeletalHierarchyIndex[4];
  int mBoneMapping;
  HashedString mBoneName;
  HashedString mName;
  Vec3 mOffset;
  Vec3 mPosition;
  Vec3 mRotation;
  bool mIgnoreInheritedScale;
  Matrix mWorldAbsoluteTransform;
};

```

### `ModelPart::TextureMesh`
```
struct __cppobj ModelPart::TextureMesh
{
  std::string mFriendlyName;
  ResourceLocation mResourceLocation;
  Vec3 mPosition;
  Vec3 mLocalPivot;
  Vec3 mRotation;
  Vec3 mScale;
};

```

### `mce::UncheckedHandleTracker`
```
struct __cppobj mce::UncheckedHandleTracker
{
  bool mIsValid;
};

```

### `mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::UncheckedHandleTracker mTrackingBlock;
  std::unique_ptr<dragon::mesh::ResolvedVertexBufferResource> mResource;
};

```

### `mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::UncheckedHandleTracker mTrackingBlock;
  std::unique_ptr<dragon::mesh::ResolvedIndexBufferResource> mResource;
};

```

### `mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::PerFrameHandleTracker mTrackingBlock;
  std::unique_ptr<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >> mResource;
};

```

### `mce::IDeferredDebugUpdate`
```
struct __cppobj mce::IDeferredDebugUpdate
{
  mce::IDeferredDebugUpdate_vtbl *__vftable /*VFT*/;
};

```

### `mce::IDeferredDebugUpdate_vtbl`
```
struct /*VFT*/ mce::IDeferredDebugUpdate_vtbl
{
  void (__fastcall *~IDeferredDebugUpdate)(mce::IDeferredDebugUpdate *this);
  void (__fastcall *apply)(mce::IDeferredDebugUpdate *this);
};

```

### `mce::ITransactionContainer_vtbl`
```
struct /*VFT*/ mce::ITransactionContainer_vtbl
{
  void (__fastcall *~ITransactionContainer)(mce::ITransactionContainer *this);
  std::unique_ptr<mce::IDeferredDebugUpdate> *(__fastcall *apply)(mce::ITransactionContainer *this, std::unique_ptr<mce::IDeferredDebugUpdate> *result);
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedI
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `mce::RenderContextStateBase`
```
struct __cppobj mce::RenderContextStateBase
{
  mce::BlendStateDescription blendStateDescription;
  mce::DepthStencilStateDescription depthStencilStateDescription;
  mce::RasterizerStateDescription rasterizerStateDescription;
  mce::SamplerStateDescription samplerStateDescription[8];
  bool textureUnitActive[8];
  glm::tvec4<int,0> currentScissor;
  mce::ViewportInfo currentViewport;
  bool initializedSamplerState[8];
  std::array<mce::TextureBase const *,8> lastBoundTexture;
  mce::RenderTargetState *renderTargetState;
};

```

### `mce::VertexFormatCacheKey`
```
struct __cppobj mce::VertexFormatCacheKey
{
  mce::VertexFormat vertexFormat;
  unsigned int attributeListIndex;
};

```

### `mce::FrameBufferDescription`
```
struct __cppobj mce::FrameBufferDescription
{
  mce::SampleDescription mSampleDescription;
  unsigned int mWidth;
  unsigned int mHeight;
};

```

### `mce::FrameBufferObject`
```
struct __cppobj mce::FrameBufferObject : mce::FrameBufferObjectNull, mce::ResourceBase<mce::FrameBufferObjectNull>
{
};

```

### `mce::FrameBufferAttachmentBase`
```
struct __cppobj __declspec(align(8)) mce::FrameBufferAttachmentBase
{
  const mce::Texture *mTexturePtr;
  unsigned __int8 mTextureLevel;
  unsigned __int16 mTextureLayer;
  mce::FrameBufferObject *mParentFrameBufferObject;
  mce::FrameBufferAttachmentDescription mFrameBufferAttachmentDescription;
  std::string mResourceName;
  bool mStorageAllocated;
};

```

### `mce::FrameBufferAttachmentNull`
```
struct __cppobj mce::FrameBufferAttachmentNull : mce::FrameBufferAttachmentBase
{
};

```

### `mce::ResourceBase<mce::FrameBufferAttachmentNull>`
```
struct __cppobj mce::ResourceBase<mce::FrameBufferAttachmentNull>
{
};

```

### `mce::FrameBufferAttachment`
```
struct __cppobj mce::FrameBufferAttachment : mce::FrameBufferAttachmentNull, mce::ResourceBase<mce::FrameBufferAttachmentNull>
{
};

```

### `mce::FrameBufferObjectBase`
```
struct __cppobj __declspec(align(4)) mce::FrameBufferObjectBase
{
  mce::FrameBufferDescription mFrameBufferDescription;
  std::vector<std::unique_ptr<mce::FrameBufferAttachment>> mFrameBufferAttachments;
  mce::FrameBufferAttachment *mColorFrameBufferAttachment;
  mce::FrameBufferAttachment *mDepthFrameBufferAttachment;
  std::string mFrameBufferObjectName;
  unsigned int mNumberOfColorFrameBufferAttachments;
  bool mFinalizedFrameBuffer;
  bool mCreatedFrameBuffer;
};

```

### `mce::FrameBufferObjectNull`
```
struct __cppobj mce::FrameBufferObjectNull : mce::FrameBufferObjectBase
{
};

```

### `mce::ResourceBase<mce::FrameBufferObjectNull>`
```
struct __cppobj mce::ResourceBase<mce::FrameBufferObjectNull>
{
};

```

### `mce::SwapChainDescription`
```
struct __cppobj __declspec(align(4)) mce::SwapChainDescription
{
  unsigned int width;
  unsigned int height;
  mce::TextureFormat textureFormat;
  mce::SampleDescription sampleDescription;
  unsigned int bufferCount;
  mce::SwapEffect swapEffect;
  bool stereo;
};

```

### `mce::SwapChainBase`
```
struct __cppobj mce::SwapChainBase
{
  mce::SwapChainDescription mSwapChainDescription;
};

```

### `mce::SwapChainNull`
```
struct __cppobj mce::SwapChainNull : mce::SwapChainBase
{
};

```

### `mce::ResourceBase<mce::SwapChainNull>`
```
struct __cppobj mce::ResourceBase<mce::SwapChainNull>
{
};

```

### `mce::SwapChain`
```
struct __cppobj mce::SwapChain : mce::SwapChainNull, mce::ResourceBase<mce::SwapChainNull>
{
};

```

### `mce::AdapterDescription`
```
struct __cppobj mce::AdapterDescription
{
  std::string mDescription;
  unsigned int mVendorId;
  unsigned int mDeviceId;
  unsigned int mSubSysId;
  unsigned int mRevision;
  unsigned __int64 mDedicatedVideoMemory;
  unsigned __int64 mDedicatedSystemMemory;
  unsigned __int64 mSharedSystemMemory;
  unsigned __int64 mReservedVideoMemory;
};

```

### `mce::DeviceInformationBase`
```
struct __cppobj __declspec(align(8)) mce::DeviceInformationBase
{
  mce::ChipsetInfo *mChipsetInfo;
  mce::AdapterDescription mAdapterDescription;
  std::string mChipsetVendorName;
  std::string mGraphicsVersion;
  std::string mGraphicsExtensions;
  bool mTearingSupport;
  bool mVertexShaderInstancingSupport;
  int mScreenWidth;
  int mScreenHeight;
};

```

### `mce::DeviceInformationNull`
```
struct __cppobj __declspec(align(8)) mce::DeviceInformationNull : mce::DeviceInformationBase
{
  bool mDeviceInitialized;
};

```

### `mce::ResourceBase<mce::DeviceInformationNull>`
```
struct __cppobj mce::ResourceBase<mce::DeviceInformationNull>
{
};

```

### `mce::DeviceInformation`
```
struct __cppobj mce::DeviceInformation : mce::DeviceInformationNull, mce::ResourceBase<mce::DeviceInformationNull>
{
};

```

### `mce::Attribute`
```
struct __cppobj mce::Attribute
{
  _BYTE builtInAttribute[2];
  unsigned int location;
  unsigned int count;
};

```

### `mce::RenderDeviceBase::AttributeList`
```
struct __cppobj mce::RenderDeviceBase::AttributeList
{
  std::vector<mce::Attribute> attributeList;
};

```

### `mce::RenderContext`
```
struct __cppobj __declspec(align(8)) mce::RenderContext : mce::RenderContextNull, mce::ResourceBase<mce::RenderContextNull>
{
  bool mWithinFrame;
};

```

### `mce::RenderDeviceBase`
```
struct __cppobj __declspec(align(8)) mce::RenderDeviceBase
{
  mce::DeviceInformation mDeviceInformation;
  std::vector<mce::RenderDeviceBase::AttributeList> registeredAttributeLists;
  std::unique_ptr<mce::RenderContext> immediateContext;
  bool mDeviceLost;
};

```

### `mce::FeatureSupportNull`
```
struct __cppobj mce::FeatureSupportNull
{
  std::array<bool,20> mRenderFeatures;
};

```

### `mce::RenderDeviceNull`
```
struct __cppobj __declspec(align(8)) mce::RenderDeviceNull : mce::RenderDeviceBase
{
  mce::FeatureSupportNull mFeatureSupportNull;
};

```

### `mce::ResourceBase<mce::RenderDeviceNull>`
```
struct __cppobj mce::ResourceBase<mce::RenderDeviceNull>
{
};

```

### `mce::Singleton<mce::RenderDevice>`
```
struct __cppobj mce::Singleton<mce::RenderDevice>
{
};

```

### `mce::RenderDevice`
```
struct __cppobj __declspec(align(8)) mce::RenderDevice : mce::RenderDeviceNull, mce::ResourceBase<mce::RenderDeviceNull>, mce::Singleton<mce::RenderDevice>
{
  _BYTE gap110;
};

```

### `mce::RenderContextBase`
```
struct __cppobj __declspec(align(8)) mce::RenderContextBase
{
  mce::RenderContextStateBase currentState;
  mce::VertexFormatCacheKey lastVertexFormat;
  std::array<mce::ShaderProgram *,3> lastShaderPrograms;
  mce::FrameBufferObject *mFrameBufferObject;
  mce::SwapChain mSwapChain;
  mce::RenderDevice *mRenderDevice;
  mce::RenderTargetState mRenderTargetState;
};

```

### `mce::RenderContextNull`
```
struct __cppobj mce::RenderContextNull : mce::RenderContextBase
{
};

```

### `mce::ResourceBase<mce::RenderContextNull>`
```
struct __cppobj mce::ResourceBase<mce::RenderContextNull>
{
};

```

### `mce::ResourceServiceRenderContext`
```
struct __cppobj mce::ResourceServiceRenderContext
{
  gsl::not_null<mce::RenderContext *> mRenderContext;
};

```

### `mce::BufferResourceServiceContext`
```
struct __cppobj __declspec(align(8)) mce::BufferResourceServiceContext : mce::ResourceServiceRenderContext
{
  bool mFrameBuilderEnabled;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  mce::BufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::BufferResourceService`
```
struct __cppobj mce::BufferResourceService : mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >
{
};

```

### `MolangMemberVariable`
```
struct __cppobj MolangMemberVariable
{
  HashedString mName;
  MolangScriptArg mData;
};

```

### `MolangEvalStackState`
```
struct __cppobj MolangEvalStackState
{
  unsigned __int64 mContinueIndexStackSize;
  unsigned __int64 mBreakIndexStackSize;
  unsigned __int64 mDataStackSize;
  unsigned __int64 mDataStackPCSize;
  unsigned __int64 mMissingVariableOrActorIndexStackSize;
  unsigned __int64 mPublicAccessModeStackSize;
  unsigned __int64 mRenderParamsPtrsStackSize;
  unsigned __int64 mRenderParamsInstancesStackSize;
};

```

### `MolangEvalParams`
```
struct __cppobj MolangEvalParams
{
  unsigned __int64 mPC;
  const MolangScriptArg *mRet;
  MolangVariableMap mTempVariables;
  MolangVariableMap mContextVariables;
  std::vector<unsigned __int64> mContinueIndexStack;
  std::vector<unsigned __int64> mBreakIndexStack;
  std::vector<MolangScriptArg> mDataStack;
  std::vector<unsigned __int64> mDataStackPC;
  std::vector<unsigned __int64> mMissingVariableOrActorIndexStack;
  unsigned __int64 mPublicAccessModeStack;
  std::vector<RenderParams *> mRenderParamsPtrsStack;
  std::vector<RenderParams> mRenderParamsInstancesStack;
  std::vector<MolangEvalStackState> mStackState;
};

```

### `MeshInstanceConstants`
```
struct __cppobj MeshInstanceConstants
{
  glm::tvec4<float,0> OVERLAY_COLOR;
  glm::tvec4<float,0> TILE_LIGHT_COLOR;
  glm::tvec4<float,0> CHANGE_COLOR;
  glm::tvec4<float,0> GLINT_COLOR;
  glm::tvec4<float,0> UV_ANIM;
  glm::tvec4<float,0> MULTIPLICATIVE_TINT_CHANGE_COLOR;
  glm::tvec2<float,0> UV_OFFSET;
  glm::tvec2<float,0> UV_ROTATION;
  glm::tvec2<float,0> UV_SCALE;
  mce::Camera mCamera;
};

```

### `MeshRenderData`
```
struct __cppobj MeshRenderData
{
  SkinnedMesh *mSkinnedMesh;
  bool mIsQuads;
  unsigned __int64 mNumVerts;
  ShaderColor mCurrentShaderColor;
  ShaderColor mCurrentShaderDarkColor;
  MeshInstanceConstants mMeshInstanceConstants;
  std::vector<glm::tmat4x4<float,0>> mBoneMatrices;
};

```

### `MultiplayerSettingsPacket`
```
const struct __cppobj __declspec(align(8)) MultiplayerSettingsPacket : Packet
{
  MultiplayerSettingsPacketType mPacketType;
};

```

### `MultiplayerSettingsPacket_vtbl`
```
struct /*VFT*/ MultiplayerSettingsPacket_vtbl
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

### `ModEffectPacket`
```
const struct __cppobj ModEffectPacket : Packet
{
  std::vector<ModEffectPacket::ModEffectEntry> mEntries;
};

```

### `ModEffectPacket_vtbl`
```
struct /*VFT*/ ModEffectPacket_vtbl
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

### `ModalFormResponsePacket`
```
const struct __cppobj ModalFormResponsePacket : Packet
{
  unsigned int mFormId;
  std::string mJSONResponse;
};

```

### `ModalFormResponsePacket_vtbl`
```
struct /*VFT*/ ModalFormResponsePacket_vtbl
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

### `ModalFormRequestPacket`
```
const struct __cppobj ModalFormRequestPacket : Packet
{
  unsigned int mFormId;
  std::string mFormJSON;
};

```

### `ModalFormRequestPacket_vtbl`
```
struct /*VFT*/ ModalFormRequestPacket_vtbl
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

### `MapInfoRequestPacket`
```
const struct __cppobj MapInfoRequestPacket : Packet
{
  ActorUniqueID mMapId;
};

```

### `MapInfoRequestPacket_vtbl`
```
struct /*VFT*/ MapInfoRequestPacket_vtbl
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

### `MapCreateLockedCopyPacket`
```
const struct __cppobj MapCreateLockedCopyPacket : Packet
{
  ActorUniqueID mOriginalMapId;
  ActorUniqueID mNewMapId;
};

```

### `MapCreateLockedCopyPacket_vtbl`
```
struct /*VFT*/ MapCreateLockedCopyPacket_vtbl
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

### `MapDecoration`
```
struct __cppobj __declspec(align(8)) MapDecoration
{
  std::string mLabel;
  _BYTE mImage[1];
  char mX;
  char mY;
  char mRotation;
  mce::Color mColor;
};

```

### `MotionPredictionHintsPacket`
```
const struct __cppobj __declspec(align(4)) MotionPredictionHintsPacket : Packet
{
  ActorRuntimeID mRuntimeId;
  Vec3 mMotion;
  bool mOnGround;
};

```

### `MotionPredictionHintsPacket_vtbl`
```
struct /*VFT*/ MotionPredictionHintsPacket_vtbl
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

### `MobArmorEquipmentPacket_vtbl`
```
struct /*VFT*/ MobArmorEquipmentPacket_vtbl
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

### `MobEquipmentPacket_vtbl`
```
struct /*VFT*/ MobEquipmentPacket_vtbl
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

### `MobEffectPacket`
```
const struct __cppobj __declspec(align(8)) MobEffectPacket : Packet
{
  ActorRuntimeID mRuntimeId;
  int mEffectDurationTicks;
  _BYTE mEventId[1];
  int mEffectId;
  int mEffectAmplifier;
  bool mShowParticles;
};

```

### `MobEffectPacket_vtbl`
```
struct /*VFT*/ MobEffectPacket_vtbl
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

### `MovePlayerPacket_vtbl`
```
struct /*VFT*/ MovePlayerPacket_vtbl
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

### `MoveActorDeltaPacket`
```
const struct __cppobj MoveActorDeltaPacket : Packet
{
  MoveActorDeltaData mMoveData;
};

```

### `MoveActorDeltaPacket_vtbl`
```
struct /*VFT*/ MoveActorDeltaPacket_vtbl
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

### `MoveActorAbsolutePacket`
```
const struct __cppobj MoveActorAbsolutePacket : Packet
{
  MoveActorAbsoluteData mMoveData;
};

```

### `MoveActorAbsolutePacket_vtbl`
```
struct /*VFT*/ MoveActorAbsolutePacket_vtbl
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

### `MovePriorityQueue<std::shared_ptr<BackgroundTaskBase>,BackgroundTaskBase::PriorityComparer>`
```
struct __cppobj MovePriorityQueue<std::shared_ptr<BackgroundTaskBase>,BackgroundTaskBase::PriorityComparer>
{
  std::vector<std::shared_ptr<BackgroundTaskBase>> mC;
};

```

### `MovePriorityQueue<FileChunk,std::less<FileChunk> >`
```
struct __cppobj MovePriorityQueue<FileChunk,std::less<FileChunk> >
{
  std::vector<FileChunk> mC;
};

```

### `mce::Singleton<mce::GlobalConstantBuffers>`
```
struct __cppobj mce::Singleton<mce::GlobalConstantBuffers>
{
};

```

### `mce::ConstantBufferConstantsBase`
```
struct __cppobj mce::ConstantBufferConstantsBase
{
  mce::ConstantBufferConstantsBase_vtbl *__vftable /*VFT*/;
  mce::ConstantBufferContainer *constantBuffer;
};

```

### `mce::ConstantBufferConstantsBase_vtbl`
```
struct /*VFT*/ mce::ConstantBufferConstantsBase_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::ShaderConstantBase_vtbl`
```
struct /*VFT*/ mce::ShaderConstantBase_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantNull`
```
struct __cppobj mce::ShaderConstantNull : mce::ShaderConstantBase
{
};

```

### `mce::ShaderConstantNull_vtbl`
```
struct /*VFT*/ mce::ShaderConstantNull_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ResourceBase<mce::ShaderConstantNull>`
```
struct __cppobj mce::ResourceBase<mce::ShaderConstantNull>
{
};

```

### `mce::ShaderConstant`
```
struct __cppobj mce::ShaderConstant : mce::ShaderConstantNull, mce::ResourceBase<mce::ShaderConstantNull>
{
};

```

### `mce::ShaderConstant_vtbl`
```
struct /*VFT*/ mce::ShaderConstant_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::AlignmentHelper::AlignmentAllocator<unsigned char,16>`
```
struct __cppobj mce::AlignmentHelper::AlignmentAllocator<unsigned char,16>
{
};

```

### `mce::ConstantBufferContainerBase`
```
struct __cppobj __declspec(align(8)) mce::ConstantBufferContainerBase
{
  std::vector<mce::ShaderConstantBase> mReflectedShaderConstants;
  std::vector<std::unique_ptr<mce::ShaderConstant>> mShaderConstants;
  std::vector<unsigned char,mce::AlignmentHelper::AlignmentAllocator<unsigned char,16> > constantBufferBytes;
  std::string mConstantBufferName;
  bool mCurrentlyMapped;
};

```

### `mce::ConstantBufferContainerNull`
```
struct __cppobj mce::ConstantBufferContainerNull : mce::ConstantBufferContainerBase
{
};

```

### `mce::ResourceBase<mce::ConstantBufferContainerNull>`
```
struct __cppobj mce::ResourceBase<mce::ConstantBufferContainerNull>
{
};

```

### `mce::ConstantBufferContainer`
```
struct __cppobj mce::ConstantBufferContainer : mce::ConstantBufferContainerNull, mce::ResourceBase<mce::ConstantBufferContainerNull>
{
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,4,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,4,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,4>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,4>
{
};

```

### `mce::ShaderConstantWithDataBase<4>`
```
struct __cppobj mce::ShaderConstantWithDataBase<4> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,4,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,4>
{
  _BYTE gap38;
  glm::tvec4<float,0> *data;
};

```

### `mce::ShaderConstantWithDataBase<4>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<4>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<4>`
```
struct __cppobj mce::ShaderConstantWithDataNull<4> : mce::ShaderConstantWithDataBase<4>
{
};

```

### `mce::ShaderConstantWithDataNull<4>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<4>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantFloat4`
```
struct __cppobj mce::ShaderConstantFloat4 : mce::ShaderConstantWithDataNull<4>
{
};

```

### `mce::ShaderConstantFloat4_vtbl`
```
struct /*VFT*/ mce::ShaderConstantFloat4_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,1,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,1,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,1>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,1>
{
};

```

### `mce::ShaderConstantWithDataBase<1>`
```
struct __cppobj mce::ShaderConstantWithDataBase<1> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,1,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,1>
{
  _BYTE gap38;
  float *data;
};

```

### `mce::ShaderConstantWithDataBase<1>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<1>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<1>`
```
struct __cppobj mce::ShaderConstantWithDataNull<1> : mce::ShaderConstantWithDataBase<1>
{
};

```

### `mce::ShaderConstantWithDataNull<1>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<1>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantFloat1`
```
struct __cppobj mce::ShaderConstantFloat1 : mce::ShaderConstantWithDataNull<1>
{
};

```

### `mce::ShaderConstantFloat1_vtbl`
```
struct /*VFT*/ mce::ShaderConstantFloat1_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::RenderChunkConstants`
```
struct __cppobj mce::RenderChunkConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *CHUNK_ORIGIN_AND_SCALE;
  mce::ShaderConstantFloat4 *CHUNK_WORLD_POS_MOD_VALUE;
  mce::ShaderConstantFloat1 *RENDER_CHUNK_FOG_ALPHA;
};

```

### `mce::RenderChunkConstants_vtbl`
```
struct /*VFT*/ mce::RenderChunkConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,13,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,13,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,13>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,13>
{
};

```

### `mce::ShaderConstantWithDataBase<13>`
```
struct __cppobj mce::ShaderConstantWithDataBase<13> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,13,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,13>
{
  _BYTE gap38;
  glm::tmat4x4<float,0> *data;
};

```

### `mce::ShaderConstantWithDataBase<13>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<13>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<13>`
```
struct __cppobj mce::ShaderConstantWithDataNull<13> : mce::ShaderConstantWithDataBase<13>
{
};

```

### `mce::ShaderConstantWithDataNull<13>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<13>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantMatrix4x4`
```
struct __cppobj mce::ShaderConstantMatrix4x4 : mce::ShaderConstantWithDataNull<13>
{
};

```

### `mce::ShaderConstantMatrix4x4_vtbl`
```
struct /*VFT*/ mce::ShaderConstantMatrix4x4_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::WorldConstants`
```
struct __cppobj mce::WorldConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantMatrix4x4 *WORLDVIEWPROJ;
  mce::ShaderConstantMatrix4x4 *WORLD;
  mce::ShaderConstantMatrix4x4 *WORLDVIEW;
  mce::ShaderConstantMatrix4x4 *PROJ;
};

```

### `mce::WorldConstants_vtbl`
```
struct /*VFT*/ mce::WorldConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::WorldConstantsHolographic`
```
struct __cppobj __declspec(align(4)) mce::WorldConstantsHolographic : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantMatrix4x4 *WORLDVIEWPROJ;
  mce::ShaderConstantMatrix4x4 *WORLD;
  mce::ShaderConstantMatrix4x4 *WORLDVIEW;
  mce::ShaderConstantMatrix4x4 *PROJ;
  bool mSinglePassStereo;
  bool mOverrideViewProjMatrix;
  Matrix mLeftViewMatOverride;
  Matrix mRightViewMatOverride;
  Matrix mLeftProjMatOverride;
  Matrix mRightProjMatOverride;
  Matrix mLeftViewShiftMatStereo;
  Matrix mRightViewShiftMatStereo;
  Matrix mMatrixPatch;
  bool mRenderTextureStereo;
  bool mMatrixPatchDirty;
};

```

### `mce::WorldConstantsHolographic_vtbl`
```
struct /*VFT*/ mce::WorldConstantsHolographic_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::WorldConstantsHolographic *this, const bool);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,3,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,3,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,3>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,3>
{
};

```

### `mce::ShaderConstantWithDataBase<3>`
```
struct __cppobj mce::ShaderConstantWithDataBase<3> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,3,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,3>
{
  _BYTE gap38;
  glm::tvec3<float,0> *data;
};

```

### `mce::ShaderConstantWithDataBase<3>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<3>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<3>`
```
struct __cppobj mce::ShaderConstantWithDataNull<3> : mce::ShaderConstantWithDataBase<3>
{
};

```

### `mce::ShaderConstantWithDataNull<3>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<3>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantFloat3`
```
struct __cppobj mce::ShaderConstantFloat3 : mce::ShaderConstantWithDataNull<3>
{
};

```

### `mce::ShaderConstantFloat3_vtbl`
```
struct /*VFT*/ mce::ShaderConstantFloat3_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,2,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,2,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,2>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,2>
{
};

```

### `mce::ShaderConstantWithDataBase<2>`
```
struct __cppobj mce::ShaderConstantWithDataBase<2> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,2,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,2>
{
  _BYTE gap38;
  glm::tvec2<float,0> *data;
};

```

### `mce::ShaderConstantWithDataBase<2>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<2>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<2>`
```
struct __cppobj mce::ShaderConstantWithDataNull<2> : mce::ShaderConstantWithDataBase<2>
{
};

```

### `mce::ShaderConstantWithDataNull<2>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<2>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantFloat2`
```
struct __cppobj mce::ShaderConstantFloat2 : mce::ShaderConstantWithDataNull<2>
{
};

```

### `mce::ShaderConstantFloat2_vtbl`
```
struct /*VFT*/ mce::ShaderConstantFloat2_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::PerFrameConstants`
```
struct __cppobj mce::PerFrameConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *TIME;
  mce::ShaderConstantFloat3 *VIEW_POS;
  mce::ShaderConstantFloat4 *BLEND_COLOR;
  mce::ShaderConstantFloat4 *USER_FOR_COLOR_NEAR;
  mce::ShaderConstantFloat4 *USER_FOR_COLOR_FAR;
  mce::ShaderConstantFloat4 *FOG_COLOR;
  mce::ShaderConstantFloat2 *FOG_CONTROL;
  mce::ShaderConstantFloat1 *RENDER_DISTANCE;
  mce::ShaderConstantFloat1 *FAR_CHUNKS_DISTANCE;
};

```

### `mce::PerFrameConstants_vtbl`
```
struct /*VFT*/ mce::PerFrameConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,11,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,11,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,11>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,11>
{
};

```

### `mce::ShaderConstantWithDataBase<11>`
```
struct __cppobj mce::ShaderConstantWithDataBase<11> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,11,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,11>
{
  _BYTE gap38;
  glm::tmat3x4<float,0> *data;
};

```

### `mce::ShaderConstantWithDataBase<11>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<11>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<11>`
```
struct __cppobj mce::ShaderConstantWithDataNull<11> : mce::ShaderConstantWithDataBase<11>
{
};

```

### `mce::ShaderConstantWithDataNull<11>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<11>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantMatrix3x4`
```
struct __cppobj mce::ShaderConstantMatrix3x4 : mce::ShaderConstantWithDataNull<11>
{
};

```

### `mce::ShaderConstantMatrix3x4_vtbl`
```
struct /*VFT*/ mce::ShaderConstantMatrix3x4_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::AnimationConstants`
```
struct __cppobj mce::AnimationConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantMatrix4x4 *BONES;
  mce::ShaderConstantMatrix4x4 *BONE;
  mce::ShaderConstantMatrix3x4 *BONES_70;
  mce::ConstantBufferContainer *legacyConstantBuffer;
};

```

### `mce::AnimationConstants_vtbl`
```
struct /*VFT*/ mce::AnimationConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::ActorConstants`
```
struct __cppobj mce::ActorConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *OVERLAY_COLOR;
  mce::ShaderConstantFloat4 *TILE_LIGHT_COLOR;
  mce::ShaderConstantFloat4 *CHANGE_COLOR;
  mce::ShaderConstantFloat4 *GLINT_COLOR;
  mce::ShaderConstantFloat4 *UV_ANIM;
  mce::ShaderConstantFloat4 *MULTIPLICATIVE_TINT_CHANGE_COLOR;
  mce::ShaderConstantFloat2 *UV_OFFSET;
  mce::ShaderConstantFloat2 *UV_ROTATION;
  mce::ShaderConstantFloat2 *UV_SCALE;
  mce::ShaderConstantMatrix4x4 *BONE_MAT;
  mce::ShaderConstantFloat4 *HIDE_COLOR;
  mce::ShaderConstantFloat4 *UV_FRAME_ANIM_PARAM;
};

```

### `mce::ActorConstants_vtbl`
```
struct /*VFT*/ mce::ActorConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::IsA<enum mce::ShaderPrimitiveTypes,5,unsigned char>`
```
struct __cppobj mce::IsA<enum mce::ShaderPrimitiveTypes,5,unsigned char>
{
};

```

### `mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,5>`
```
struct __cppobj mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,5>
{
};

```

### `mce::ShaderConstantWithDataBase<5>`
```
struct __cppobj mce::ShaderConstantWithDataBase<5> : mce::ShaderConstant, mce::IsA<enum mce::ShaderPrimitiveTypes,5,unsigned char>, mce::PrimitiveTypeFromEnumType<enum mce::ShaderPrimitiveTypes,5>
{
  _BYTE gap38;
  int *data;
};

```

### `mce::ShaderConstantWithDataBase<5>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataBase<5>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantWithDataNull<5>`
```
struct __cppobj mce::ShaderConstantWithDataNull<5> : mce::ShaderConstantWithDataBase<5>
{
};

```

### `mce::ShaderConstantWithDataNull<5>_vtbl`
```
struct /*VFT*/ mce::ShaderConstantWithDataNull<5>_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstantInt1`
```
struct __cppobj mce::ShaderConstantInt1 : mce::ShaderConstantWithDataNull<5>
{
};

```

### `mce::ShaderConstantInt1_vtbl`
```
struct /*VFT*/ mce::ShaderConstantInt1_vtbl
{
  void (__fastcall *~ShaderConstantBase)(mce::ShaderConstantBase *this);
};

```

### `mce::ShaderConstants`
```
struct __cppobj mce::ShaderConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *CURRENT_COLOR;
  mce::ShaderConstantFloat4 *DARKEN;
  mce::ShaderConstantFloat3 *TEXTURE_DIMENSIONS;
  mce::ShaderConstantFloat1 *HUD_OPACITY;
  mce::ShaderConstantMatrix4x4 *UV_TRANSFORM;
  mce::ShaderConstantInt1 *MSAA_SAMPLECOUNT;
};

```

### `mce::ShaderConstants_vtbl`
```
struct /*VFT*/ mce::ShaderConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::EffectConstants`
```
struct __cppobj mce::EffectConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat2 *UV_OFFSET;
};

```

### `mce::EffectConstants_vtbl`
```
struct /*VFT*/ mce::EffectConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::WeatherConstants`
```
struct __cppobj mce::WeatherConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *POSITION_OFFSET;
  mce::ShaderConstantFloat4 *VELOCITY;
  mce::ShaderConstantFloat4 *ALPHA;
  mce::ShaderConstantFloat4 *VIEW_POSITION;
  mce::ShaderConstantFloat4 *SIZE_SCALE;
  mce::ShaderConstantFloat4 *FORWARD;
  mce::ShaderConstantFloat4 *UV_INFO;
  mce::ShaderConstantFloat4 *PARTICLE_BOX;
};

```

### `mce::WeatherConstants_vtbl`
```
struct /*VFT*/ mce::WeatherConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::FlipbookTextureConstants`
```
struct __cppobj mce::FlipbookTextureConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *V_OFFSET;
  mce::ShaderConstantFloat1 *V_BLEND_OFFSET;
};

```

### `mce::FlipbookTextureConstants_vtbl`
```
struct /*VFT*/ mce::FlipbookTextureConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::TextConstants`
```
struct __cppobj mce::TextConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *GLYPH_SMOOTH_RADIUS;
  mce::ShaderConstantFloat1 *GLYPH_CUTOFF;
  mce::ShaderConstantFloat1 *OUTLINE_CUTOFF;
  mce::ShaderConstantFloat4 *OUTLINE_COLOR;
  mce::ShaderConstantFloat1 *SHADOW_SMOOTH_RADIUS;
  mce::ShaderConstantFloat4 *SHADOW_COLOR;
  mce::ShaderConstantFloat2 *SHADOW_OFFSET;
};

```

### `mce::TextConstants_vtbl`
```
struct /*VFT*/ mce::TextConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::InterFrameConstants`
```
struct __cppobj mce::InterFrameConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *TOTAL_REAL_WORLD_TIME;
  mce::ShaderConstantMatrix4x4 *CUBE_MAP_ROTATION;
};

```

### `mce::InterFrameConstants_vtbl`
```
struct /*VFT*/ mce::InterFrameConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::DebugConstants`
```
struct __cppobj mce::DebugConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *TEXTURE_ARRAY_INDEX_0;
};

```

### `mce::DebugConstants_vtbl`
```
struct /*VFT*/ mce::DebugConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::BannerConstants`
```
struct __cppobj mce::BannerConstants
{
  mce::ShaderConstantFloat4 *BANNER_COLORS;
  mce::ShaderConstantFloat4 *BANNER_UV_OFFSETS_AND_SCALES;
  mce::ConstantBufferContainer *constantBuffer;
};

```

### `mce::PostProcessConstants`
```
struct __cppobj mce::PostProcessConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantInt1 *GaussianBlurSize;
  mce::ShaderConstantFloat1 *DepthOfFieldNearEndDepth;
  mce::ShaderConstantFloat1 *DepthOfFieldFarStartDepth;
  mce::ShaderConstantFloat1 *DepthOfFieldFarEndDepth;
};

```

### `mce::PostProcessConstants_vtbl`
```
struct /*VFT*/ mce::PostProcessConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::SfxConstants`
```
struct __cppobj mce::SfxConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *EXTRA_VECTOR1;
  mce::ShaderConstantFloat4 *EXTRA_VECTOR2;
  mce::ShaderConstantFloat4 *EXTRA_VECTOR3;
  mce::ShaderConstantFloat4 *EXTRA_VECTOR4;
  mce::ShaderConstantFloat4 *SUN_DIR;
  mce::ShaderConstantFloat4 *WATER_TEXTURE_UV_RANGE;
  mce::ShaderConstantFloat4 *SKY_NEAR_COLOR;
  mce::ShaderConstantFloat4 *SKY_FAR_COLOR;
  mce::ShaderConstantFloat4 *RAIN_NEAR_COLOR;
  mce::ShaderConstantFloat4 *RAIN_FAR_COLOR;
  mce::ShaderConstantFloat4 *COLOR_MAPPING_PARAM;
};

```

### `mce::SfxConstants_vtbl`
```
struct /*VFT*/ mce::SfxConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UITransformsConstants`
```
struct __cppobj mce::UITransformsConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantMatrix4x4 *TRANSFORM;
};

```

### `mce::UITransformsConstants_vtbl`
```
struct /*VFT*/ mce::UITransformsConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIGlobalPixelConstants`
```
struct __cppobj mce::UIGlobalPixelConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat2 *VIEWPORT_SIZE;
};

```

### `mce::UIGlobalPixelConstants_vtbl`
```
struct /*VFT*/ mce::UIGlobalPixelConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIStandardPrimitivePixelConstants`
```
struct __cppobj mce::UIStandardPrimitivePixelConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantInt1 *SHADER_TYPE;
};

```

### `mce::UIStandardPrimitivePixelConstants_vtbl`
```
struct /*VFT*/ mce::UIStandardPrimitivePixelConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIStandardPrimitiveAdditionalPixelConstants`
```
struct __cppobj mce::UIStandardPrimitiveAdditionalPixelConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *PRIM_PROPS_0;
  mce::ShaderConstantFloat4 *PRIM_PROPS_1;
};

```

### `mce::UIStandardPrimitiveAdditionalPixelConstants_vtbl`
```
struct /*VFT*/ mce::UIStandardPrimitiveAdditionalPixelConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIEffectsPixelConstants`
```
struct __cppobj mce::UIEffectsPixelConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *COEFFICIENTS;
  mce::ShaderConstantFloat4 *PIXEL_OFFSETS;
};

```

### `mce::UIEffectsPixelConstants_vtbl`
```
struct /*VFT*/ mce::UIEffectsPixelConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIRenoirShaderVSConstants`
```
struct __cppobj mce::UIRenoirShaderVSConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantMatrix4x4 *COORD_TRANSFORM;
  mce::ShaderConstantFloat4 *RENOIR_SHADER_VS_PROPS_0;
};

```

### `mce::UIRenoirShaderVSConstants_vtbl`
```
struct /*VFT*/ mce::UIRenoirShaderVSConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UIRenoirShaderPSConstants`
```
struct __cppobj mce::UIRenoirShaderPSConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat4 *RENOIR_SHADER_PS_PROPS_0;
  mce::ShaderConstantFloat4 *RENOIR_SHADER_PS_PROPS_1;
  mce::ShaderConstantFloat4 *RENOIR_SHADER_PS_PROPS_2;
  mce::ShaderConstantFloat4 *RENOIR_SHADER_PS_PROPS_3;
};

```

### `mce::UIRenoirShaderPSConstants_vtbl`
```
struct /*VFT*/ mce::UIRenoirShaderPSConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::UITextPSConstants`
```
struct __cppobj mce::UITextPSConstants : mce::ConstantBufferConstantsBase
{
  mce::ShaderConstantFloat1 *BITMAP;
};

```

### `mce::UITextPSConstants_vtbl`
```
struct /*VFT*/ mce::UITextPSConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::GlobalConstantBuffers`
```
struct __cppobj mce::GlobalConstantBuffers : mce::Singleton<mce::GlobalConstantBuffers>
{
  mce::RenderChunkConstants renderChunkConstantBuffer;
  mce::WorldConstants worldConstantBuffer;
  mce::WorldConstantsHolographic worldConstantBufferHolographic;
  mce::PerFrameConstants perFrameConstantBuffer;
  mce::AnimationConstants animationConstants;
  mce::ActorConstants entityConstantBuffer;
  mce::ShaderConstants shaderConstantBuffer;
  mce::EffectConstants effectConstantBuffer;
  mce::WeatherConstants weatherConstantBuffer;
  mce::FlipbookTextureConstants flipbookTextureConstants;
  mce::TextConstants textConstants;
  mce::InterFrameConstants interFrameConstantBuffer;
  mce::DebugConstants debugConstants;
  mce::BannerConstants bannerConstantBuffer;
  mce::PostProcessConstants postProcessConstants;
  mce::SfxConstants sfxConstants;
  mce::UITransformsConstants uiTransformsConstantBuffer;
  mce::UIGlobalPixelConstants uiGlobalPixelConstantBuffer;
  mce::UIStandardPrimitivePixelConstants uiStandardPrimitivePixelConstantBuffer;
  mce::UIStandardPrimitiveAdditionalPixelConstants uiStandardPrimitiveAdditionalPixelConstantBuffer;
  mce::UIEffectsPixelConstants uiEffectsPixelConstantBuffer;
  mce::UIRenoirShaderVSConstants uiRenoirShaderVSConstantBuffer;
  mce::UIRenoirShaderPSConstants uiRenoirShaderPSConstantBuffer;
  mce::UITextPSConstants uiTextPSConstants;
};

```

### `mce::Singleton<mce::GlobalConstantBufferManager>`
```
struct __cppobj mce::Singleton<mce::GlobalConstantBufferManager>
{
};

```

### `mce::GlobalConstantBufferManager`
```
struct __cppobj __declspec(align(8)) mce::GlobalConstantBufferManager : mce::Singleton<mce::GlobalConstantBufferManager>
{
  std::vector<mce::ConstantBufferContainer> mConstantBufferContainers;
  bool mStereoEnabled;
  bool mIsHolographic;
  bool mLeftPass;
};

```

### `mce::QuadIndexBuffer`
```
struct __cppobj mce::QuadIndexBuffer
{
  unsigned int mCapacity;
  unsigned __int8 mIndexSize;
  mce::ClientResourcePointer<mce::ResourcePointer<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> > mGlobalBuffer;
};

```

### `mce::ImmediateBufferBase`
```
struct __cppobj mce::ImmediateBufferBase
{
};

```

### `mce::ImmediateBufferNull`
```
struct __cppobj mce::ImmediateBufferNull : mce::ImmediateBufferBase, mce::BufferNull
{
};

```

### `mce::ResourceBase<mce::ImmediateBufferNull>`
```
struct __cppobj mce::ResourceBase<mce::ImmediateBufferNull>
{
};

```

### `mce::ImmediateBuffer`
```
struct __cppobj mce::ImmediateBuffer : mce::ImmediateBufferNull, mce::ResourceBase<mce::ImmediateBufferNull>
{
};

```

### `mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::PerFrameHandleTracker mTrackingBlock;
  std::unique_ptr<mce::ImmediateBuffer> mResource;
};

```

### `mce::Singleton<mce::RendererSettings>`
```
struct __cppobj mce::Singleton<mce::RendererSettings>
{
};

```

### `mce::RendererSettings`
```
struct __cppobj mce::RendererSettings : mce::Singleton<mce::RendererSettings>
{
  unsigned int mBufferCount;
  mce::TextureFormat mBackBufferTextureFormat;
  mce::SwapEffect mSwapEffect;
  mce::SampleDescription mBackBufferSampleDescription;
  glm::tvec2<float,0> mOutputSize;
  glm::tvec2<float,0> mLogicalSize;
  glm::tvec2<float,0> mCompositionScale;
  float mDPI;
  mce::VerticalSync mVSync;
  bool mTexelAA;
  HWND__ *mHWND;
  bool mRenderDragonRenderPath;
  unsigned int mInstanceCount;
};

```

### `Minecraft`
```
struct __cppobj Minecraft : IEntityRegistryOwner
{
  GameCallbacks *mGameCallbacks;
  IMinecraftEventing *mEventing;
  std::unique_ptr<ResourcePackManager> mResourceLoader;
  std::unique_ptr<StructureManager> mStructureManager;
  std::shared_ptr<GameModuleServer> mGameModuleServer;
  AllowList *mAllowList;
  PermissionsFile *mPermissionsFile;
  std::unique_ptr<PrivateKeyManager> mServerKeys;
  const std::string mSaveGamePath;
  Core::FilePathManager *mFilePathManager;
  ServerMetrics *mServerMetrics;
  bool mLevelIsCorrupted;
  long double mFrameDuration;
  long double mLastFrameStart;
  std::chrono::duration<__int64,std::ratio<1,1> > mMaxPlayerIdleTime;
  std::unique_ptr<MinecraftCommands> mCommands;
  std::unique_ptr<GameSession> mGameSession;
  Timer *mSimTimer;
  Timer *mRealTimer;
  NetworkHandler *mNetworkHandler;
  PacketSender *mPacketSender;
  IMinecraftApp *mApp;
  unsigned __int8 mClientSubId;
  OwnerPtrT<EntityRegistryRefTraits> mEntityRegistry;
};

```

### `MinecraftServerScriptEngine`
```
struct __cppobj MinecraftServerScriptEngine : ScriptEngineWithContext<ScriptServerContext>, ServerInstanceEventListener
{
  std::unique_ptr<ScriptServerActorEventListener> mEntityEventListener;
  std::unique_ptr<ScriptServerBlockEventListener> mBlockEventListener;
  std::unique_ptr<ScriptServerPacketEventListener> mPacketEventListener;
  std::unique_ptr<ScriptTelemetryEventListener> mTelemetryListener;
  std::unique_ptr<ScriptServerLevelEventListener> mLevelListener;
  std::unique_ptr<ScriptLevelWeatherEventListener> mWeatherListener;
  std::unique_ptr<entt::basic_registry<enum entt::entity>> mRegistry;
  ServerInstance *mServerInstance;
};

```

### `MobSpawnerPermutation`
```
struct __cppobj MobSpawnerPermutation : WeighedRandom::WeighedRandomItem
{
  ActorDefinitionIdentifier mId;
};

```

### `MinecraftServerScriptEngine_vtbl`
```
struct /*VFT*/ MinecraftServerScriptEngine_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *onLogReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onInfoReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onWarnReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onErrorReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const ActorUniqueID *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetActor)(ScriptEngine *this, const ScriptObjectBinder *, Actor **);
  bool (__fastcall *helpGetBlockSource)(ScriptEngine *this, const ScriptObjectBinder *, BlockSource **);
  bool (__fastcall *helpGetBlock)(ScriptEngine *this, const ScriptObjectBinder *, const Block **, const BlockSource *);
  bool (__fastcall *helpGetBlockPos)(ScriptEngine *this, const ScriptObjectBinder *, BlockPos *);
  bool (__fastcall *helpDefineLevel)(ScriptEngine *this, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetLevel)(ScriptEngine *this, const ScriptObjectBinder *, Level **);
  bool (__fastcall *helpDefineItemStack)(ScriptEngine *this, const ItemInstance *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *helpPopulateEcsID)(ScriptEngine *this, Json::Value *);
  bool (__fastcall *setupInterface)(ScriptEngine *this);
  bool (__fastcall *registerEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *onEventReceivedFromScriptEngine)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *destroyEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *isValidEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, bool *);
  bool (__fastcall *registerComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *);
  bool (__fastcall *destroyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *applyComponentChanges)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerScriptOnlyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const long double, const long double, const long double, const long double, const long double, const long double, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *addFilter)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *getBlock)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const BlockPos *, const ScriptApi::ScriptObjectHandle *, const ScriptObjectBinder *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ActorUniqueID *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ITickingArea *);
  void (__fastcall *onExecuteCommandCalled)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptCommand *);
  bool (__fastcall *executeCommand)(ScriptEngine *this, const ScriptCommand *);
  bool (__fastcall *onCommandOutputCallback)(ScriptEngine *this, unsigned int, Json::Value *);
  bool (__fastcall *_registerSystemObjects)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *_hasEvent)(ScriptEngine *this, const std::string *);
  bool (__fastcall *_helpRegisterSystemCallbacks)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  void (__fastcall *_handleError)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  void (__fastcall *_handleWarning)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  EventResult (__fastcall *onLevelTick)(MinecraftServerScriptEngine *this);
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $AF41FC17702287ADCE42EFECF54176CF ___u0;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value> >`
```
struct __cppobj MPMCQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value> >
{
  moodycamel::ConcurrentQueue<std::pair<std::unique_ptr<CommandOrigin>,Json::Value>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MinecraftCommands`
```
struct __cppobj MinecraftCommands
{
  std::unique_ptr<CommandOutputSender> mOutputSender;
  std::unique_ptr<CommandRegistry> mRegistry;
  _BYTE mOpPermissionLevel[1];
  Minecraft *mMinecraft;
  std::function<bool __cdecl(void)> mChatPermissionsCallback;
  std::unordered_map<HashedString,std::unique_ptr<Command>> mCompiledCommandMap;
};

```

### `Minecraft_vtbl`
```
struct /*VFT*/ Minecraft_vtbl
{
  OwnerPtrT<EntityRegistryRefTraits> *(__fastcall *getEntityRegistry)(IEntityRegistryOwner *this);
  void (__fastcall *~Minecraft)(Minecraft *this);
};

```

### `mce::TextureGroupBase`
```
struct __cppobj mce::TextureGroupBase
{
  mce::TextureGroupBase_vtbl *__vftable /*VFT*/;
};

```

### `mce::TextureGroupBase_vtbl`
```
struct /*VFT*/ mce::TextureGroupBase_vtbl
{
  void (__fastcall *~TextureGroupBase)(mce::TextureGroupBase *this);
  mce::TexturePtr *(__fastcall *getTexture)(mce::TextureGroupBase *this, mce::TexturePtr *result, const ResourceLocation *, bool);
};

```

### `mce::LRUCache::CacheEntry`
```
struct __cppobj __declspec(align(8)) mce::LRUCache::CacheEntry
{
  ResourceLocation mResourceLocation;
  unsigned __int64 mImageSize;
  unsigned int mTouchMarker;
};

```

### `mce::LRUCache`
```
struct __cppobj mce::LRUCache
{
  unsigned __int64 mMemoryLimit;
  unsigned __int64 mMemoryUsage;
  unsigned int mTouchMarker;
  std::list<mce::LRUCache::CacheEntry> mLRUEntryList;
  std::unordered_map<ResourceLocation,std::_List_iterator<std::_List_val<std::_List_simple_types<mce::LRUCache::CacheEntry> > >> mLRULookupMap;
  std::function<void __cdecl(ResourceLocation const &)> mUnloader;
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > > mDeferredResourceTracker;
};

```

### `mce::TextureResourceServiceContext`
```
struct __cppobj mce::TextureResourceServiceContext : mce::ResourceServiceRenderContext
{
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::TextureResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::TextureResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > > mResourceTracker;
  mce::TextureResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::TextureResourceService`
```
struct __cppobj mce::TextureResourceService : mce::CheckedResourceService<mce::resource_service_traits<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::TextureResourceServiceContext> >
{
};

```

### `mce::TextureGroup`
```
struct __cppobj __declspec(align(8)) mce::TextureGroup : mce::TextureGroupBase
{
  std::map<ResourceLocation,BedrockTexture> mLoadedTextures;
  std::map<std::pair<ResourceLocation,enum TextureLoadMode>,std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >,std::less<std::pair<ResourceLocation,enum TextureLoadMode> >,std::allocator<std::pair<std::pair<ResourceLocation,enum TextureLoadMode> const ,std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > > > mLoadQueueResults;
  std::map<std::pair<ResourceLocation,enum TextureLoadMode>,std::optional<enum ResourceLoadType>,std::less<std::pair<ResourceLocation,enum TextureLoadMode> >,std::allocator<std::pair<std::pair<ResourceLocation,enum TextureLoadMode> const ,std::optional<enum ResourceLoadType> > > > mRateLimitedTextureLoadList;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mQueuLoadResultCoroutine;
  std::set<ResourceLocation> mTouchedTextures;
  ImageBufferResourceManager mImageBufferCache;
  std::unique_ptr<mce::LRUCache> mLRUCache;
  ResourceLoadManager *mResourceLoadManager;
  Bedrock::Threading::CountTracker mPendingReloadCounter;
  std::atomic<unsigned __int64> mOutstandingTaskMemory;
  std::atomic<unsigned __int64> mOutstandingTaskCount;
  mce::TextureResourceService *mResourceService;
  const cg::ImageBuffer mMissingTexture;
  unsigned int mMaxTextureQueueDepth;
  std::chrono::duration<__int64,std::ratio<1,1000> > mLoadDelayTime;
  bool mEnableAsyncFileLoads;
  bool mEnableMissingAsyncTextureLoad;
};

```

### `mce::TextureGroup_vtbl`
```
struct /*VFT*/ mce::TextureGroup_vtbl
{
  void (__fastcall *~TextureGroupBase)(mce::TextureGroupBase *this);
  mce::TexturePtr *(__fastcall *getTexture)(mce::TextureGroupBase *this, mce::TexturePtr *result, const ResourceLocation *, bool);
};

```

### `mce::ShaderCacheBase`
```
struct __cppobj mce::ShaderCacheBase
{
  Core::PathBuffer<std::string > mPackagedCacheLocation;
  Core::PathBuffer<std::string > mTempCacheLocation;
};

```

### `mce::ShaderCacheNull`
```
struct __cppobj mce::ShaderCacheNull : mce::ShaderCacheBase
{
};

```

### `mce::ResourceBase<mce::ShaderCacheNull>`
```
struct __cppobj mce::ResourceBase<mce::ShaderCacheNull>
{
};

```

### `mce::ShaderCache`
```
struct __cppobj mce::ShaderCache : mce::ShaderCacheNull, mce::ResourceBase<mce::ShaderCacheNull>
{
};

```

### `mce::ShaderGroupBase`
```
struct __cppobj mce::ShaderGroupBase
{
  std::unique_ptr<mce::ShaderCache> mShaderCache;
  std::vector<std::unique_ptr<mce::Shader>> mShaders;
  std::unordered_map<std::string,std::unique_ptr<mce::ShaderProgram>> mPrograms;
  std::unordered_map<std::string,std::unique_ptr<mce::ShaderProgram>> mTmpPrograms;
};

```

### `mce::ShaderGroup`
```
struct __cppobj mce::ShaderGroup : AppPlatformListener, Bedrock::EnableNonOwnerReferences, mce::ShaderGroupBase
{
};

```

### `mce::ShaderGroup_vtbl`
```
struct /*VFT*/ mce::ShaderGroup_vtbl
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

### `mce::ClientResourcePointer<mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> >`
```
struct __cppobj mce::ClientResourcePointer<mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> > : mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr>
{
};

```

### `mcr::DynamicTextureResourceManager`
```
struct __cppobj mcr::DynamicTextureResourceManager : cg::ResourceManager<std::shared_ptr<mce::ClientTexture>,enum mce::DynamicTexture,void,std::shared_ptr<mce::ClientTexture>,std::map>
{
};

```

### `mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::pair<std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::unique_ptr<mce::ITransactionContainer> >> mPendingTransactionHandles;
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<mce::ImmediateBuffer,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<mce::ImmediateBuffer,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  mce::BufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::ImmediateBufferResourceService`
```
struct __cppobj mce::ImmediateBufferResourceService : mce::CheckedResourceService<mce::resource_service_traits<mce::ImmediateBuffer,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,mce::BufferResourceServiceContext> >
{
};

```

### `MinecraftGameplayGraphicsResources`
```
struct __cppobj MinecraftGameplayGraphicsResources
{
  ImageResourceManager mImageResources;
  ImageTrackerTemplate<ImageResourceManager> mImageResourceTracker;
  ImageBufferResourceManager mItemAtlasResources;
  SharedImageBufferTracker mSharedImageBufferAtlasTracker;
  DynamicImageResourceManager mDynamicImageResourceManager;
  ImageTrackerTemplate<DynamicImageResourceManager> mDynamicImageTracker;
  TickingTextures mTickingTextures;
  mcr::DynamicTextureResourceManager mDynamicTextures;
  mce::TextureResourceService mTextureResourceService;
  std::shared_ptr<mce::BufferResourceService> mBufferResourceService;
  mce::ImmediateBufferResourceService mImmediateBufferResourceService;
};

```

### `MinecraftGraphics`
```
struct __cppobj MinecraftGraphics : AppPlatformListener
{
  std::unique_ptr<mce::ShaderGroup> mShaderGroup;
  std::unique_ptr<mce::QuadIndexBuffer> mQuadBuffer;
  mce::ClientResourcePointer<mce::ResourcePointer<mce::ImmediateBuffer,mce::ResourceBlockTemplate<mce::ImmediateBuffer,mce::PerFrameHandleTracker,dragon::BufferDescription>,std::shared_ptr> > mImmediateBuffer;
  MinecraftGameplayGraphicsResources mMinecraftGameplayGraphicsResources;
};

```

### `MinecraftGraphics_vtbl`
```
struct /*VFT*/ MinecraftGraphics_vtbl
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

### `mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>`
```
struct __cppobj mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>
{
  mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>_vtbl *__vftable /*VFT*/;
};

```

### `mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>_vtbl`
```
struct /*VFT*/ mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>_vtbl
{
  void (__fastcall *~IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>)(mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager> *this);
  mce::FileWatcherHandle *(__fastcall *load)(mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager> *this, mce::FileWatcherHandle *result, const ResourceLocation *, ImageResourceManager *, std::shared_ptr<mce::Image> *, const mce::WatchStatus);
  mce::FileWatcherHandle *(__fastcall *loadAndRegister)(mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager> *this, mce::FileWatcherHandle *result, const ResourceLocation *, ImageResourceManager *, std::shared_ptr<mce::Image> *, const mce::WatchStatus, std::function<void __cdecl(ResourceLocation,std::shared_ptr<mce::Image> const &)>);
  mce::FileWatcherHandle *(__fastcall *registerLoader)(mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager> *this, mce::FileWatcherHandle *result, const ResourceLocation *, ImageResourceManager *, std::shared_ptr<mce::Image> *, const mce::WatchStatus, std::function<void __cdecl(ResourceLocation,std::shared_ptr<mce::Image> const &)>);
};

```

### `MessageParam`
```
struct __cppobj MessageParam
{
  MessageParam_vtbl *__vftable /*VFT*/;
};

```

### `MessageParam_vtbl`
```
struct /*VFT*/ MessageParam_vtbl
{
  bool (__fastcall *IsString)(MessageParam *this);
  bool (__fastcall *IsInt)(MessageParam *this);
  bool (__fastcall *IsFloat)(MessageParam *this);
  std::string *(__fastcall *GetString)(MessageParam *this, std::string *result);
  int (__fastcall *GetInt)(MessageParam *this);
  float (__fastcall *GetFloat)(MessageParam *this);
  void (__fastcall *~MessageParam)(MessageParam *this);
};

```

### `MeasureResult`
```
struct __cppobj __declspec(align(8)) MeasureResult
{
  std::string mFormattedText;
  glm::tvec2<float,0> mSize;
  std::vector<int> mCaretOffsets;
  float mCaretHeightOffset;
  float mLineHeight;
  bool mUsingEllipses;
};

```

### `MinecraftUIFrameUpdateContext`
```
struct __cppobj MinecraftUIFrameUpdateContext : UIFrameUpdateContext, FrameUpdateContext
{
  _BYTE gap0[8];
  IClientInstance *mClientInstance;
};

```

### `MemBlock`
```
struct __cppobj MemBlock
{
  const unsigned __int64 mCapacity;
  unsigned __int64 mSize;
  std::unique_ptr<unsigned char [0]> mDataBlock;
};

```

### `mce::PointLight`
```
const struct __cppobj __declspec(align(4)) mce::PointLight
{
  float mIntensity;
  glm::tvec3<float,0> mColor;
  glm::tvec3<float,0> mWorldPosition;
  bool mIsLarge;
};

```

### `ManifestContentItem`
```
const struct __cppobj ManifestContentItem : ContentItem
{
  std::unique_ptr<PackManifest const > mManifest;
  Core::PathBuffer<std::string > mIconPath;
  Core::PathBuffer<std::string > mZipPath;
  std::string mFileSystem;
};

```

### `ManifestContentItem_vtbl`
```
struct /*VFT*/ ManifestContentItem_vtbl
{
  void (__fastcall *~ContentItem)(ContentItem *this);
};

```

### `MainMenuScreenModel`
```
struct __cppobj MainMenuScreenModel : MinecraftScreenModel, IMainMenuScreenModel
{
  std::unique_ptr<MinecoinCatalogModel> mMinecoinCatalogModel;
  std::unique_ptr<WorldSeedCatalogModel> mWorldSeedCatalogModel;
  std::shared_ptr<WorldFileDownloadManager> mFileDownloadManager;
  std::unique_ptr<TaskGroup> mFileUploadTaskGroup;
  WorldTemplateManager *mWorldTemplateManager;
};

```

### `MinecraftScreenModel_vtbl`
```
struct /*VFT*/ MinecraftScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `MinecoinModel_vtbl`
```
struct /*VFT*/ MinecoinModel_vtbl
{
  void (__fastcall *~MinecoinModel)(MinecoinModel *this);
};

```

### `MinecoinCatalogModel`
```
struct __cppobj MinecoinCatalogModel
{
  gsl::not_null<Bedrock::NonOwnerPointer<OfferRepository> > mOfferRepository;
  FlightingService *mFlightingService;
  std::shared_ptr<bool> mExistenceTracker;
  MinecoinCatalogStatus mCatalogStatus;
  std::vector<MinecoinModel> mMinecoinModels;
  std::vector<MinecoinModel> mActiveMinecoinModels;
  MinecoinModel mInvalidMinecoinModel;
  std::unique_ptr<ContentCatalogService> mContentCatalogService;
  std::function<void __cdecl(void)> mUpdateBindsCallback;
};

```

### `MainMenuScreenModel_vtbl`
```
struct /*VFT*/ MainMenuScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `MinecraftGraphicsPipeline`
```
struct __cppobj MinecraftGraphicsPipeline
{
  mce::Texture mMSAAColorTexture;
  mce::Texture mMSAADepthTexture;
};

```

### `mce::RenderStage_vtbl`
```
struct /*VFT*/ mce::RenderStage_vtbl
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

### `mce::RenderGraph`
```
struct __cppobj mce::RenderGraph
{
  std::vector<std::unique_ptr<mce::RenderStage>> mRenderStages;
  std::unordered_set<gsl::not_null<mce::RenderStage *>> mRenderTickStages;
};

```

### `mce::Clock`
```
struct __cppobj __declspec(align(4)) mce::Clock
{
  float mAccumulatedTime;
  float mLastDeltaTime;
  float mLastDeltaTimeSquared;
  float mCurrentTime;
  float mAccumulatedModTime;
  float mTimeScale;
  bool mPaused;
};

```

### `mce::RenderStageWithFrameBufferObject`
```
struct __cppobj mce::RenderStageWithFrameBufferObject : mce::RenderStage
{
  mce::FrameBufferObject mFrameBufferObject;
  mce::Texture mColorBufferTexture;
  mce::Texture mDepthBufferTexture;
  mce::Texture *mFrameBufferTexture;
};

```

### `mce::RenderStageWithFrameBufferObject_vtbl`
```
struct /*VFT*/ mce::RenderStageWithFrameBufferObject_vtbl
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
  void (__fastcall *setupStage)(mce::RenderStageWithFrameBufferObject *this, ScreenContext *, const bool);
};

```

### `MaterialVariationManager`
```
struct __cppobj MaterialVariationManager
{
};

```

### `mce::RenderMaterialGroupBase_vtbl`
```
struct /*VFT*/ mce::RenderMaterialGroupBase_vtbl
{
  void (__fastcall *~RenderMaterialGroupBase)(mce::RenderMaterialGroupBase *this);
  mce::RenderMaterialInfo *(__fastcall *getMaterialInfo)(mce::RenderMaterialGroupBase *this, const HashedString *);
  void (__fastcall *clearMaterial)(mce::RenderMaterialGroupBase *this, const HashedString *);
};

```

### `mce::RenderMaterialGroup_vtbl`
```
struct /*VFT*/ mce::RenderMaterialGroup_vtbl
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

### `mce::framebuilder::VrEyeConfiguration`
```
struct __cppobj __declspec(align(8)) mce::framebuilder::VrEyeConfiguration
{
  dragon::res::ServerTexture mEyeTexture;
  unsigned __int8 mArrayIndex;
  glm::tmat4x4<float,0> mView;
  glm::tmat4x4<float,0> mProj;
};

```

### `mce::framebuilder::gamecomponents::VrConfiguration`
```
struct __cppobj mce::framebuilder::gamecomponents::VrConfiguration
{
  _BYTE mMirroring[4];
  glm::tmat4x4<float,0> mWorldPatch;
  glm::tmat4x4<float,0> mUiPatch;
  cg::math::Rect<unsigned short> mViewport;
  mce::framebuilder::VrEyeConfiguration mLeftEyeConfig;
  std::optional<mce::framebuilder::VrEyeConfiguration> mRightEyeConfig;
  std::function<void __cdecl(void)> mPostRenderCallback;
};

```

### `mce::framebuilder::LivingRoomDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::LivingRoomDescription
{
  mce::ClientTexture mColorTarget;
  glm::tvec4<float,0> mViewport;
  dragon::frameobject::components::ViewSetId mViewSetId;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $D8F963D0E8DC3884413CFC01B88920F0 ___u0;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<SubChunkPos>`
```
struct __cppobj MPMCQueue<SubChunkPos>
{
  moodycamel::ConcurrentQueue<SubChunkPos,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $C121F4620A648719078F94D5C15923F7 ___u0;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::function<void __cdecl(std::nullptr_t &)> >`
```
struct __cppobj MPMCQueue<std::function<void __cdecl(std::nullptr_t &)> >
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(std::nullptr_t &)>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `mce::ThreadedPerFrameConstants`
```
struct __cppobj mce::ThreadedPerFrameConstants : mce::PerFrameConstants
{
  mce::ConstantBufferContainer mPerFrameConstants;
};

```

### `mce::ThreadedPerFrameConstants_vtbl`
```
struct /*VFT*/ mce::ThreadedPerFrameConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::ThreadedShaderConstants`
```
struct __cppobj mce::ThreadedShaderConstants : mce::ShaderConstants
{
  mce::ConstantBufferContainer mShaderConstants;
};

```

### `mce::ThreadedShaderConstants_vtbl`
```
struct /*VFT*/ mce::ThreadedShaderConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::ThreadedRenderChunkConstants`
```
struct __cppobj mce::ThreadedRenderChunkConstants : mce::RenderChunkConstants
{
  mce::ConstantBufferContainer ownedConstantBuffer;
};

```

### `mce::ThreadedRenderChunkConstants_vtbl`
```
struct /*VFT*/ mce::ThreadedRenderChunkConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `mce::ThreadedWorldConstants`
```
struct __cppobj mce::ThreadedWorldConstants : mce::WorldConstants
{
  mce::ConstantBufferContainer mWorldConstantsContainer;
};

```

### `mce::ThreadedWorldConstants_vtbl`
```
struct /*VFT*/ mce::ThreadedWorldConstants_vtbl
{
  void (__fastcall *~ConstantBufferConstantsBase)(mce::ConstantBufferConstantsBase *this);
  void (__fastcall *init)(mce::ConstantBufferConstantsBase *this);
};

```

### `MoveInput`
```
struct __cppobj __declspec(align(4)) MoveInput
{
  MoveInput_vtbl *__vftable /*VFT*/;
  Vec2 mMove;
  Vec2 mLookDelta;
  Vec3 mGazeDir;
  Vec3 mGazeDirDelta;
  Vec3 mDisplacement;
  Vec3 mDisplacementDelta;
  bool mSneaking;
  bool mSneakDown;
  bool mSprinting;
  bool mWantUp;
  bool mWantDown;
  bool mWantDownSlow;
  bool mWantUpSlow;
  bool mJumping;
  bool mAutoJumpingInWater;
  bool mAscendScaffolding;
  bool mDescendScaffolding;
  bool mSneakToggleDown;
  bool mMoveLocked;
};

```

### `MovementCorrection`
```
struct __cppobj MovementCorrection
{
  CorrectionMethod mMethod;
  Vec3 mAcceptPosition;
};

```

### `MoveInputHandler`
```
struct __cppobj __declspec(align(2)) MoveInputHandler : MoveInput
{
  bool mAscend;
  bool mDescend;
  bool mNorthJump;
  bool mJumpDown;
  bool mSprintDown;
  bool mChangeHeight;
  bool mPersistSneak;
  bool mUp;
  bool mDown;
  bool mLeft;
  bool mRight;
  bool mUpLeft;
  bool mUpRight;
  Vec2 mAnalogMoveVector;
  Vec3 mGazeDir;
  bool mLookCenter;
  unsigned __int8 mLookSlightDirField;
  unsigned __int8 mLookNormalDirField;
  unsigned __int8 mLookSmoothDirField;
  bool mPreJumpDownState;
  bool mPreMovingState;
  bool mFlyDown;
  bool mTryFly;
  bool mWalkDown;
  int mWalkState;
  int mWalkStateOld;
  bool mWantSlowdown;
  bool mSneakButtonDown;
  bool mFirstPersonDown;
  bool mThirdPersonDown;
  bool mThirdPersonFrontDown;
  bool mMayFile;
  bool mSprintMode;
};

```

### `MoveInput_vtbl`
```
struct /*VFT*/ MoveInput_vtbl
{
  void (__fastcall *~MoveInput)(MoveInput *this);
  void (__fastcall *tick)(MoveInput *this, IPlayerMovementProxy *);
  void (__fastcall *render)(MoveInput *this, float);
  void (__fastcall *setKey)(MoveInput *this, int, bool);
  void (__fastcall *clearInputState)(MoveInput *this);
  void (__fastcall *clearMovementState)(MoveInput *this);
  bool (__fastcall *allowPicking)(MoveInput *this, float, float);
  void (__fastcall *setJumping)(MoveInput *this, bool);
  void (__fastcall *setAutoJumpingInWater)(MoveInput *this, bool);
  bool (__fastcall *isChangeHeight)(MoveInput *this);
  void (__fastcall *setSneakDown)(MoveInput *this, bool);
  bool (__fastcall *isPlayerMoving)(MoveInput *this);
  const Vec3 *(__fastcall *getGazeDirection)(MoveInput *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `MinecraftGame`
```
struct __cppobj MinecraftGame : Bedrock::AppIsland, App, IMinecraftGame, LevelListener, ResourcePackListener, OptionsObserver, ActiveDirectoryIdentityObserver, IDynamicPackageConsumer, I18nObserver
{
  bool focusForbidden;
  std::unique_ptr<MinecraftGraphics> mMinecraftGraphics;
  std::unique_ptr<mce::framebuilder::FrameBuilder> mFrameBuilder;
  ServiceRegistrationToken<mce::framebuilder::FrameBuilder> mFrameBuilderServiceRegistrationToken;
  std::unique_ptr<mce::FileWatcherNull> mFileWatcher;
  ServiceRegistrationToken<mce::FileWatcherNull> mFileWatcherServiceRegistrationToken;
  std::unique_ptr<UriListener> mArguments;
  std::unique_ptr<UriListener> mDeeplinkListener;
  std::unique_ptr<GameRenderer> mGameRenderer;
  std::unique_ptr<CommandListQueue> mCommandListQueue;
  std::unique_ptr<HolosceneRenderer> mHolosceneRenderer;
  std::unique_ptr<ExternalServerFile> mExternalServer;
  std::unique_ptr<mce::TextureGroup> mTextures;
  std::unique_ptr<TextureHotReloader> mTextureHotReloader;
  std::unique_ptr<mce::TextureGroup> mStoreCacheTextures;
  std::unique_ptr<UIRepository> mUIRepository;
  FontHandle mFontHandle;
  FontHandle mRuneFontHandle;
  FontHandle mUnicodeFontHandle;
  FontHandle mSmoothFontLatinHandle;
  FontHandle mUIFontHandle;
  std::shared_ptr<FontRepository> mFontRepository;
  std::unique_ptr<EmoticonManager> mEmoticonManager;
  std::unique_ptr<TextToIconMapper> mTextToIconMapper;
  std::unique_ptr<MinecraftUIMeasureStrategy> mMeasureStrategy;
  std::unique_ptr<SeasonsRenderer> mSeasonsRenderer;
  std::shared_ptr<PersonaRepository> mPersonaRepository;
  std::shared_ptr<SkinRepository> mSkinRepository;
  std::unique_ptr<HummingbirdUI> mHummingbirdUI;
  std::unique_ptr<ContentLog> mContentLog;
  ServiceRegistrationToken<ContentLog> mContentLogServiceRegistrationToken;
  std::unique_ptr<ContentLogFileEndPoint> mContentLogFileEndPoint;
  std::unique_ptr<GuiContentLogEndPoint> mContentLogGuiEndPoint;
  std::unique_ptr<DebugEndPoint> mDebugEndPoint;
  std::unique_ptr<AppConfigs> mAppConfig;
  ServiceRegistrationToken<AppConfigs> mAppConfigServiceRegistrationToken;
  std::unique_ptr<SceneStack> mSceneStack;
  std::unique_ptr<CachedScenes> mCachedScenes;
  std::unique_ptr<hbui::Router> mUIRouter;
  bool mMouseGrabbed;
  std::unordered_map<unsigned int,std::function<void __cdecl(void)>> mButtonDownHandlerMap;
  std::unordered_map<unsigned int,std::function<void __cdecl(void)>> mButtonUpHandlerMap;
  std::set<unsigned char> mAvailableClientSubIds;
  std::unique_ptr<ServerInstance> mServerInstance;
  std::map<unsigned char,std::shared_ptr<IClientInstance>> mClientInstances;
  std::unique_ptr<HolographicPlatform> mPrimaryClientHoloInput;
  std::function<void __cdecl(enum TestCommandType,std::vector<std::string> const &,int)> mTestExecuteCommandCallback;
  std::function<void __cdecl(enum TestAssetCommandType,std::vector<std::string> const &)> mTestAssetCommandCallback;
  std::unique_ptr<Timer> mSimTimer;
  std::unique_ptr<Timer> mRealTimer;
  std::unique_ptr<DebugUdpProxyConsumer> mDebugUdpProxy;
  std::unique_ptr<MinecraftInputHandler> mInput;
  std::unique_ptr<UIDefRepository> mUIDefRepo;
  std::unique_ptr<Core::IFileSystem> mFileSystem;
  std::unique_ptr<SoundEngine> mTempSoundEngine;
  std::unique_ptr<SoundEngine> mSoundEngine;
  std::unique_ptr<MusicManager> mMusicManager;
  std::unique_ptr<ProfilingManager> mProfilingManager;
  ServiceRegistrationToken<ProfilingManager> mProfilingManagerServiceRegistrationToken;
  std::unique_ptr<Bedrock::Threading::PendingConditionals> mPendingConditionals;
  ServiceRegistrationToken<Bedrock::Threading::PendingConditionals> mPendingConditionalsServiceRegistrationToken;
  std::unique_ptr<TextToSpeechSystem> mTTSSystem;
  std::unique_ptr<OculusPlatformMessagePump> mOculusPlatformMessagePump;
  std::unique_ptr<ContentAcquisition> mContentAcquisition;
  std::shared_ptr<OfferRepository> mOfferRepository;
  std::unique_ptr<PersonaService> mPersonaService;
  std::unique_ptr<ContentCatalogService> mContentCatalogService;
  std::unique_ptr<LibraryService> mLibraryService;
  std::unique_ptr<ChannelService> mChannelService;
  std::shared_ptr<LessonProgressionService> mLessonProgressionService;
  std::shared_ptr<StoreCatalogConfig> mStoreCatalogConfig;
  std::unique_ptr<StoreCatalogRepository> mStoreCatalogRepository;
  std::unique_ptr<ServiceDrivenImageRepository> mServiceDrivenImageRepository;
  std::unique_ptr<LibraryRepository> mLibraryRepository;
  std::unique_ptr<ThirdPartyServerRepository> mThirdPartyServerRepository;
  std::unique_ptr<ResourcePackRepository> mResourcePackRepository;
  std::unique_ptr<WorldTemplateManager> mWorldTemplateManager;
  ResourcePackManager *mResourcePackManager;
  std::unique_ptr<ClientAssetCacheController> mClientAssetCacheController;
  std::unique_ptr<DevConsoleLogger> mDevConsoleLogger;
  std::shared_ptr<GeometryGroup> mGeometryGroup;
  std::shared_ptr<ClientBlockPipeline::SchematicsRepository> mSchematicRepository;
  std::unique_ptr<ParticleEffectGroup> mParticleEffectGroup;
  std::unique_ptr<ParticleSystem::ParticleEffectComponentRegistry> mParticleComponentRegistry;
  std::unique_ptr<ActorAnimationGroup> mActorAnimationGroup;
  std::unique_ptr<ActorAnimationControllerGroup> mActorAnimationControllerGroup;
  std::unique_ptr<RenderControllerGroup> mRenderControllerGroup;
  std::unique_ptr<NetworkHandler> mClientNetworkSystem;
  ServiceReference<Social::UserManager> mUserManager;
  std::string mCurrentSignInXUID;
  std::string mCurrentEntitlementsXUID;
  std::unique_ptr<Social::MultiplayerServiceManager> mMultiplayerServiceManager;
  std::unique_ptr<Social::InteractivityManager> mInteractivityManager;
  std::unique_ptr<Social::InviteUriListener> mInviteListener;
  std::unique_ptr<Social::RealmsUriListener> mRealmsListener;
  std::shared_ptr<FlightingService> mFlightingService;
  std::unique_ptr<TreatmentPackDownloadMonitor> mTreatmentPackMonitor;
  std::shared_ptr<GenericEntitlementChangeListener> mEntitlementChangeListener;
  bool mHasNewPrimaryUserForEntitlements;
  bool mHasUnhandledEntitlementsChangeEvent;
  std::unique_ptr<DateManager> mDateManager;
  ServiceRegistrationToken<DateManager> mDateManagerServiceRegistrationToken;
  std::unique_ptr<PatchNotesManager> mPatchNotesManager;
  std::shared_ptr<FileArchiver> mFileArchiver;
  std::unique_ptr<TextureAtlas> mTextureAtlas;
  std::unique_ptr<TextureAtlas> mItemTextureAtlas;
  std::shared_ptr<RealmsAPI> mRealms;
  std::unique_ptr<Realms::RealmsServices> mRealmsServices;
  std::unique_ptr<ActiveDirectoryIdentity> mActiveDirectoryIdentity;
  std::unique_ptr<Social::PresenceManager> mPresenceManager;
  std::unique_ptr<Automation::AutomationClient> mAutomationClient;
  std::unique_ptr<WebSocketCommManager> mWebSocketCommunicatorManager;
  std::unique_ptr<ServiceClientScheduler> mServiceClientScheduler;
  std::set<unsigned char> mSubclientRemovalSet;
  std::vector<std::pair<void *,std::function<void __cdecl(void)> >> mSplitScreenChangedCallbacks;
  std::atomic<enum MinecraftGame::SuspendState> mSuspended;
  bool mRunServerWhileSuspended;
  bool mConnectedToRemoteServer;
  ResetCallbackObject *mResetCallbackObj;
  std::unique_ptr<PixelCalc> mDpadScale;
  mce::UUID mUUID;
  MinecraftGame::SkinLoadStatus mCustomSkinShouldBeLoadedNow;
  std::string mProcessRegistrationKey;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mCheckLoadRendererAssetsCompleteHandle;
  std::atomic<bool> mIsFileSystemSpaceTrackingComplete;
  std::atomic<bool> mIsLevelInfoRepopulationComplete;
  const unsigned __int64 MAX_LOCAL_CLIENTS;
  ServiceReference<IMinecraftEventing> mEventing;
  bool mNewLevel;
  std::unique_ptr<LevelLoader> mLevelLoader;
  std::unique_ptr<ExternalContentManager> mContentManager;
  std::unique_ptr<PackManifestFactory> mManifestFactory;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mEndOfLastFrame;
  unsigned __int8 mUIRenderIterId;
  unsigned int mUIRenderClientMask;
  unsigned int mUIRenderIssuedMask;
  bool mTickedLastFrame;
  bool mInitialResourcesLoaded;
  bool mReadyToRender;
  bool mGenerateDocs;
  bool mLaunchedFromLegacyVersion;
  unsigned int mLeaveGameProgress;
  ResourcePacksInfoData mResourcePacksInfoData;
  unsigned __int64 mResourcePackTotalDownloadingSize;
  std::unordered_set<std::string> mResourcePackDownloadingQueue;
  std::unordered_map<std::string,unsigned __int64> mResourcePackDownloadedData;
  std::unique_ptr<TrialManager> mTrialManager;
  std::atomic<bool> mIsInGame;
  std::atomic<enum LocalServerStartupState> mLocalServerStartupState;
  std::unique_ptr<ResourceLoadManager> mResourceLoadManager;
  ServiceRegistrationToken<ResourceLoadManager> mResourceLoadManagerServiceRegistrationToken;
  std::unique_ptr<ActorResourceDefinitionGroup> mActorResourceDefinitionGroup;
  std::shared_ptr<bool> mDeferHandleInvite;
  bool mInitFinished;
  bool mHasDestroyedGame;
  bool mAppWillTerminate;
  bool mFiredInitialEvents;
  bool mForceReloadResources;
  std::unique_ptr<ContentTierManager> mContentTierManager;
  std::unique_ptr<PackSourceFactory> mPackSourceFactory;
  std::function<void __cdecl(IClientInstance &)> mLeaveCompleteCallback;
  std::function<void __cdecl(std::vector<std::string> const &)> mTestAutomationCallback;
  bool mOptionsSetForAutomation;
  bool mRunningInTestCloud;
  bool mProfilerIsOn;
  int mScreenShotCount;
  std::mutex mTextMutex;
  std::vector<std::pair<std::string,int>> mInputMessages;
  bool mRealSuspended;
  bool mIsInTransfer;
  bool mKeepResourceWhenTransfer;
  bool mIsInForceReload;
  std::unique_ptr<CubemapBackgroundResources> mCubemapBackgroundResources;
  std::unique_ptr<LevelListCache> mLevelListCache;
  std::unique_ptr<LevelStorageSource> mLevelStorageSource;
  std::shared_ptr<bool> mExistenceTracker;
  std::unique_ptr<DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>> mDeferredTasks;
  std::unique_ptr<TaskGroup> mStorageAreaTaskGroup;
  std::unique_ptr<TaskGroup> mInitializationTaskGroup;
  std::unique_ptr<TaskGroup> mServerInitTaskGroup;
  std::shared_ptr<ContentManager> mResourceContentManager;
  int mDeferedMaterialReloadRefCnt;
  bool mPrimaryRenderOptionsChanged;
  bool mNeedsBadGlobalPacksToast;
  bool mHasLicence;
  bool mNewID;
  std::unique_ptr<UIEventCoordinator> mUIEventCoordinator;
  std::unique_ptr<ClientInstanceEventCoordinator> mClientInstanceEventCoordinator;
  std::unique_ptr<ServerInstanceEventCoordinator> mServerInstanceEventCoordinator;
  LoadingScreen mLoadingScreen;
  std::array<SerialWorkList,3> mSerialWorkList;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mLastClientUpdateDuration;
  ScreenshotRecorder mScreenshotRecorder;
  std::weak_ptr<ClientBlobCache::Cache> mClientBlobCache;
  bool mDisablePauseMenuOnFocusLost;
  std::unique_ptr<EDUSystems> mEDUSystems;
  std::unique_ptr<RayTracingOptions> mRayTracingOptions;
  std::unique_ptr<IGameModuleApp> mGameModule;
  std::unique_ptr<ServerInitData> mServerInitData;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mServerStartHandle;
  std::unique_ptr<SerialWorkList> mSuspendWorkList;
  std::unique_ptr<ChunkPerformanceData> mChunkPerformanceData;
  ServiceRegistrationToken<ChunkPerformanceData> mChunkPerformanceDataRegistrationToken;
  std::optional<PendingScreenshotRequest> mPendingScreenshotRequest;
  bool mAddingUserInProgress;
  bool mSplashScreenHidden;
  bool mInitPrimaryUserComplete;
  std::unique_ptr<DynamicPackageControl> mDynamicPackage;
  std::vector<Bedrock::PubSub::ScopedSubscription> mPrimaryUserOptionLockSubscriptions;
  std::vector<Bedrock::PubSub::ScopedSubscription> mPrimaryUserOptionObserverSubscriptions;
  std::multimap<unsigned char,Bedrock::PubSub::ScopedSubscription> mClientOptionLockSubscriptions;
  std::multimap<unsigned char,Bedrock::PubSub::ScopedSubscription> mClientOptionObserverSubscriptions;
};

```

### `mce::framebuilder::FrameBuilder`
```
struct __cppobj mce::framebuilder::FrameBuilder : Bedrock::EnableNonOwnerReferences
{
  mce::framebuilder::FrameBuilder_vtbl *__vftable /*VFT*/;
};

```

### `mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::UncheckedHandleTracker mTrackingBlock;
  std::unique_ptr<dragon::res::ResolvedShaderBufferResource> mResource;
};

```

### `mcr::DeferredResourceTransactions`
```
struct __cppobj mcr::DeferredResourceTransactions
{
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > > mDeferredTextureTransactions;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Buffer,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> >,mce::ClientResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr> > >,mce::PerFrameHandleTracker,dragon::BufferDescription> > > mDeferredBufferTransactions;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredDragonVertexBufferTransactions;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredDragonIndexBufferTransactions;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredDragonShaderBufferTransactions;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > > mDeferredDragonTextureTransactions;
};

```

### `mcr::FrameContext`
```
struct __cppobj mcr::FrameContext
{
};

```

### `mce::framebuilder::FrameBuilderContext`
```
struct __cppobj mce::framebuilder::FrameBuilderContext
{
  mcr::DeferredResourceTransactions deferredResourceTransactions;
  mcr::FrameContext frameContext;
  mce::framebuilder::FrameConfiguration configuration;
};

```

### `mce::framebuilder::CameraDescriptionOrthographic`
```
const struct __cppobj mce::framebuilder::CameraDescriptionOrthographic
{
  cg::math::Rect<unsigned short> mViewport;
  cg::math::Rect<unsigned short> mScissorRect;
  glm::tvec3<float,0> mPosition;
  glm::tvec3<float,0> mTarget;
  glm::tvec3<float,0> mUp;
  cg::math::Rect<float> mProjectionBounds;
  float mNearPlane;
  float mFarPlane;
};

```

### `mce::framebuilder::BufferClearDescription`
```
const struct __cppobj __declspec(align(4)) mce::framebuilder::BufferClearDescription
{
  _BYTE mBufferClearMask[2];
  mce::Color mColor;
  float mDepth;
  unsigned __int8 mStencilRef;
};

```

### `mce::framebuilder::CameraDescriptionPerspective`
```
const struct __cppobj mce::framebuilder::CameraDescriptionPerspective
{
  cg::math::Rect<unsigned short> mViewport;
  cg::math::Rect<unsigned short> mScissorRect;
  glm::tvec3<float,0> mPosition;
  glm::tvec3<float,0> mTarget;
  glm::tvec3<float,0> mUp;
  float mFovInDegrees;
  float mNearPlane;
  float mFarPlane;
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $C121F4620A648719078F94D5C15923F7 ___u0;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)> >`
```
struct __cppobj MPMCQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)> >
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> > >`
```
struct __cppobj MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> > >
{
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> > >`
```
struct __cppobj MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> > >
{
  moodycamel::ConcurrentQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  dragon::DragonBufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  dragon::DragonBufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  dragon::DragonBufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > > mDeferredResourceTracker;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::TaskQueueContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::TaskQueueContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > > mResourceTracker;
  dragon::TaskQueueContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase> >`
```
struct __cppobj MPMCQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase> >
{
  moodycamel::ConcurrentQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<dragon::res::ServerTexture>`
```
struct __cppobj MPMCQueue<dragon::res::ServerTexture>
{
  moodycamel::ConcurrentQueue<dragon::res::ServerTexture,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `mce::framebuilder::bgfxbridge::FrameExtractorMaterials::MaterialEntry`
```
struct __cppobj mce::framebuilder::bgfxbridge::FrameExtractorMaterials::MaterialEntry
{
  dragon::materials::Material *mResource;
  std::string mName;
  std::map<std::string,std::string> mVariation;
};

```

### `mce::framebuilder::bgfxbridge::FrameExtractorMaterials`
```
const struct __cppobj mce::framebuilder::bgfxbridge::FrameExtractorMaterials
{
  std::vector<std::unique_ptr<mce::framebuilder::bgfxbridge::FrameExtractorMaterials::MaterialEntry>> mMaterials;
  dragon::materials::Material **mCoreScreenBlit;
  dragon::materials::Material **mScreenUV;
  dragon::materials::Material **mDefaultActorMaterial;
  dragon::materials::Material **mDefaultHugeBonesActorMaterial;
  dragon::materials::Material **mCracksOverlayBlockEntityMaterial;
  dragon::materials::Material **mBlockSelectionOutlineMaterial;
  dragon::materials::Material **mBlockSelectionOverlayMaterial;
  dragon::materials::Material **mBlockSelectionOverlayAlphaTestMaterial;
  dragon::materials::Material **mBlockSelectionOverlayBlockEntityMaterial;
  dragon::materials::Material **mCracksMaterial;
  dragon::materials::Material **mRenderChunkMaterial;
  dragon::materials::Material **mRenderChunkZBiasMaterial;
  dragon::materials::Material **mRenderChunkSeasonsMaterial;
  dragon::materials::Material **mRenderChunkSeasonsZBiasMaterial;
  dragon::materials::Material **mRenderChunkBarrierMaterial;
  dragon::materials::Material **mRenderChunkEndPortalMaterial;
  dragon::materials::Material **mCloudsMaterial;
  dragon::materials::Material **mEndSkyMaterial;
  dragon::materials::Material **mSkyMaterial;
  dragon::materials::Material **mStarsMaterial;
  dragon::materials::Material **mSunMoonMaterial;
  dragon::materials::Material **mCubemapMaterial;
  dragon::materials::Material **mLegacyCubemapMaterial;
  dragon::materials::Material **mUIBaseMaterial;
  dragon::materials::Material **mUIBlitMaterial;
  dragon::materials::Material **mUIFillMaterial;
  dragon::materials::Material **mUISpriteMaterial;
  dragon::materials::Material **mUISpriteMultiColorTintMaterial;
  dragon::materials::Material **mUIGlintMaterial;
  dragon::materials::Material **mUITextMaterialNoMSDF;
  dragon::materials::Material **mUITextMaterialWithMSDF;
  dragon::materials::Material **mUITextMaterialNoMSDFGrayScale;
  dragon::materials::Material **mImGuiMaterial;
  dragon::materials::Material **mBlitMaterial;
  dragon::materials::Material **mColorBlitMaterial;
  dragon::materials::Material **mShadowOverlayMaterial;
  dragon::materials::Material **mShadowVolumeMaterial;
  dragon::materials::Material **mFlipbookMaterial;
  dragon::materials::Material **mRainMaterial;
  dragon::materials::Material **mSnowMaterial;
  dragon::materials::Material **mPlanktonMaterial;
  dragon::materials::Material **mRedSporesMaterial;
  dragon::materials::Material **mBlueSporesMaterial;
  dragon::materials::Material **mAshMaterial;
  dragon::materials::Material **mWhiteAshMaterial;
  dragon::materials::Material **mFlameBillboardMaterial;
  dragon::materials::Material **mBeaconBeamMaterial;
  dragon::materials::Material **mParticleMaterial;
  dragon::materials::Material **mPostEffectBloomMaterial;
  dragon::materials::Material **mPostEffectTonemapMaterial;
  dragon::materials::Material **mPostEffectDebugMaterial;
  dragon::materials::Material **mMeshFallbackPosUVMaterialNormalColor;
  dragon::materials::Material **mGamefaceStandardMaterial;
  dragon::materials::Material **mGamefaceStandardRareMaterial;
  dragon::materials::Material **mGamefaceStencilMaterial;
  dragon::materials::Material **mGamefaceStencilRareMaterial;
  dragon::materials::Material **mGamefaceStencilPathMaterial;
  dragon::materials::Material **mGamefaceClearQuadMaterial;
  dragon::materials::Material **mGamefaceRenoirMaterial;
  dragon::materials::Material **mGamefacePathMaterial;
  dragon::materials::Material **mSequenceEffectMaterial;
};

```

### `mce::framebuilder::gamecomponents::FadeToBlackEffect`
```
struct __cppobj mce::framebuilder::gamecomponents::FadeToBlackEffect
{
};

```

### `mce::framebuilder::gamecomponents::VrFloatingUiQuad`
```
struct __cppobj mce::framebuilder::gamecomponents::VrFloatingUiQuad
{
};

```

### `mce::framebuilder::gamecomponents::LivingRoomTransitionFilter`
```
struct __cppobj mce::framebuilder::gamecomponents::LivingRoomTransitionFilter
{
  glm::tmat4x4<float,0> mLeftProj;
  glm::tmat4x4<float,0> mRightProj;
};

```

### `mce::framebuilder::gamecomponents::OverlayUI`
```
struct __cppobj mce::framebuilder::gamecomponents::OverlayUI
{
};

```

### `mce::framebuilder::gamecomponents::AlphaTestCracks`
```
struct __cppobj mce::framebuilder::gamecomponents::AlphaTestCracks
{
};

```

### `mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>`
```
struct __cppobj mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>
{
  std::shared_ptr<dragon::BufferDescription> mDebugInfoBlock;
  mce::UncheckedHandleTracker mTrackingBlock;
  std::unique_ptr<dragon::mesh::ResolvedAccelerationStructureResource> mResource;
};

```

### `mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>`
```
struct __cppobj mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>
{
  std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > mResourcePointerBlock;
};

```

### `mce::ServerResourcePointer<mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>`
```
struct __cppobj mce::ServerResourcePointer<mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler> : mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>
{
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $2ED4633196722D52F9A0320DAB3D2C69 ___u0;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const > >`
```
struct __cppobj MPMCQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const > >
{
  moodycamel::ConcurrentQueue<std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > const >,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >`
```
struct __cppobj mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > >
{
  std::vector<std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >> mResourceTrackingBlocks;
  mce::SimpleDeferredResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mDeferredResourceTracker;
};

```

### `mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >`
```
struct __cppobj __declspec(align(8)) mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
  mce::SimpleResourceTracker<std::shared_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> >,std::weak_ptr<mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription> > > mResourceTracker;
  dragon::DragonBufferResourceServiceContext mResourceServiceContext;
  _BYTE mState[1];
};

```

### `mce::framebuilder::PBRTextureDataDescription`
```
const struct __cppobj mce::framebuilder::PBRTextureDataDescription
{
  unsigned __int16 mNumMipsColor;
  float mUniformMetalness;
  float mUniformEmissive;
  float mUniformRoughness;
  std::optional<glm::tvec2<float,0> > mMERUVScale;
  std::optional<glm::tvec2<float,0> > mMERUVBias;
  std::optional<unsigned short> mNumMipsMER;
  _BYTE mNormalMode[4];
  std::optional<glm::tvec2<float,0> > mNormalOrHeightUVScale;
  std::optional<glm::tvec2<float,0> > mNormalOrHeightUVBias;
  std::optional<unsigned short> mNumMipsNormalOrHeight;
};

```

### `mce::framebuilder::RenderFlameBillboardDescription`
```
const struct __cppobj __declspec(align(4)) mce::framebuilder::RenderFlameBillboardDescription
{
  const mce::Mesh *mMesh;
  glm::tmat4x4<float,0> mWorldMatrix;
  const dragon::res::ServerTexture mTexture;
  bool mIsUIPass;
  glm::tvec2<float,0> mUVOffset;
  mce::framebuilder::FogDescription mFog;
  float mFarChunkDistance;
  const dragon::frameobject::components::ViewSetId mViewId;
};

```

### `mce::framebuilder::BlitFlipbookTextureDescription`
```
const struct __cppobj mce::framebuilder::BlitFlipbookTextureDescription
{
  const dragon::res::ServerTexture mRenderTargetTexture;
  gsl::span<mce::framebuilder::BlitFlipbookSingleTextureDescription const ,-1> mTextures;
};

```

### `mce::framebuilder::RenderParticleDescription`
```
const struct __cppobj mce::framebuilder::RenderParticleDescription
{
  const mce::Mesh *mMesh;
  const dragon::res::ServerTexture mTexture;
  mce::framebuilder::FogDescription mFog;
  float mFarChunkDistance;
  _BYTE mBlendMode[4];
  mce::CullMode mCullMode;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderPlayerVisionDescription`
```
const struct __cppobj mce::framebuilder::RenderPlayerVisionDescription
{
  bool mNightVisionEnabled;
  float mNightVisionScale;
  float mBlindnessLevel;
};

```

### `mce::framebuilder::RenderShadowDescription`
```
const struct __declspec(align(8)) mce::framebuilder::RenderShadowDescription
{
  const ActorShadowRenderObjectCollection *mActorShadowRenderObjectCollection;
  const glm::tmat4x4<float,0> *mWorldMatrix;
  const glm::tvec3<float,0> *mCameraPosition;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderSequenceEffectDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderSequenceEffectDescription
{
  glm::tmat4x4<float,0> mWorldTransform;
  const mce::Mesh *mMesh;
  const mce::ClientTexture *mTexture;
  bool mDepthTest;
  const unsigned __int16 mViewId;
  glm::tvec2<float,0> mUVOffset;
  glm::tvec2<float,0> mUVScale;
  glm::tvec2<float,0> mUVRepeat;
  glm::tvec4<float,0> mMixColor;
};

```

### `mce::framebuilder::FadeToBlackDescription`
```
const struct __declspec(align(4)) mce::framebuilder::FadeToBlackDescription
{
  const mce::Mesh *mMesh;
  float mAlpha;
  glm::tmat4x4<float,0> mWorldTransform;
  unsigned __int16 mViewId;
};

```

### `mce::framebuilder::GamefaceRenderTarget`
```
struct __cppobj __declspec(align(8)) mce::framebuilder::GamefaceRenderTarget
{
  std::variant<std::monostate,dragon::res::ClientTexture,mce::ClientTexture> mColorTargetTextureHandle;
  std::variant<std::monostate,dragon::res::ClientTexture,mce::ClientTexture> mDepthTargetTextureHandle;
  glm::tvec4<int,0> mViewport;
  glm::tvec4<int,0> mScissor;
  bool scissorEnabled;
};

```

### `mce::framebuilder::GamefacePipelineState`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::GamefacePipelineState
{
  mce::framebuilder::GamefacePipelineState::Shader shader;
  mce::framebuilder::GamefaceRenderTarget renderTarget;
  mce::RasterizerStateDescription rasterStateDesc;
  mce::BlendStateDescription blendStateDesc;
  mce::DepthStencilStateDescription depthStateDesc;
};

```

### `mce::framebuilder::GamefaceUniformCBTransforms`
```
struct __cppobj mce::framebuilder::GamefaceUniformCBTransforms
{
  float Transform[16];
};

```

### `mce::framebuilder::GamefaceUniformRenoirShaderVS`
```
struct __cppobj mce::framebuilder::GamefaceUniformRenoirShaderVS
{
  float Matrix0[16];
  float Prop0[4];
};

```

### `mce::framebuilder::GamefaceUniformGlobalPixelCB`
```
struct __cppobj mce::framebuilder::GamefaceUniformGlobalPixelCB
{
  float ViewportSize[2];
  float __padding0[2];
};

```

### `mce::framebuilder::GamefaceUniformStandardPrimitivePixel`
```
struct __cppobj mce::framebuilder::GamefaceUniformStandardPrimitivePixel
{
  int ShaderType;
  int _padding0[3];
};

```

### `mce::framebuilder::GamefaceUniformStandardPrimitiveAdditionalPixel`
```
struct __cppobj mce::framebuilder::GamefaceUniformStandardPrimitiveAdditionalPixel
{
  float PrimProps0[4];
  float PrimProps1[4];
};

```

### `mce::framebuilder::GamefaceUniformEffectsPixelCB`
```
struct __cppobj mce::framebuilder::GamefaceUniformEffectsPixelCB
{
  float Coefficients[12];
  float PixelOffsets[24];
};

```

### `mce::framebuilder::GamefaceUniformRenoirShaderPS`
```
struct __cppobj mce::framebuilder::GamefaceUniformRenoirShaderPS
{
  float Prop0[4];
  float Prop1[4];
  float Prop2[4];
  float Prop3[4];
};

```

### `mce::framebuilder::GamefaceBatchDraw::GamefaceMesh`
```
struct __cppobj __declspec(align(8)) mce::framebuilder::GamefaceBatchDraw::GamefaceMesh
{
  mce::framebuilder::GamefaceUniformCBTransforms cbTransforms;
  mce::framebuilder::GamefaceUniformRenoirShaderVS renoirShaderVS;
  mce::framebuilder::GamefaceUniformGlobalPixelCB globalPixelCB;
  mce::framebuilder::GamefaceUniformStandardPrimitivePixel standardPrimitivePixel;
  mce::framebuilder::GamefaceUniformStandardPrimitiveAdditionalPixel standardPrimitiveAdditionalPixel;
  mce::framebuilder::GamefaceUniformEffectsPixelCB effectsPixelCB;
  mce::framebuilder::GamefaceUniformRenoirShaderPS renoirShaderPS;
  std::variant<std::monostate,dragon::res::ClientTexture,mce::ClientTexture> mTextures[4];
  mce::SamplerStateDescription mSamplers[4];
  dragon::mesh::Mesh mMesh;
  unsigned int indexOffset;
  unsigned int indexCount;
  unsigned __int8 stencilRef;
  glm::tvec4<float,0> scissor;
};

```

### `mce::framebuilder::GamefaceBatchDraw`
```
const struct __cppobj mce::framebuilder::GamefaceBatchDraw
{
  std::vector<mce::framebuilder::GamefaceBatchDraw::GamefaceMesh> meshes;
};

```

### `mce::framebuilder::RenderUIGamefaceDescription`
```
const struct __cppobj mce::framebuilder::RenderUIGamefaceDescription
{
  const mce::framebuilder::GamefacePipelineState mPipelineState;
  const mce::framebuilder::GamefaceBatchDraw *mBatchDraw;
};

```

### `mce::framebuilder::GlintDescription`
```
const struct __cppobj mce::framebuilder::GlintDescription
{
  glm::tvec4<float,0> mGlintColor;
  glm::tvec2<float,0> mGlintUVScale;
  glm::tvec2<float,0> mGlintOffset;
  glm::tvec2<float,0> mGlintRotation;
};

```

### `mce::framebuilder::RenderUIMeshDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderUIMeshDescription
{
  const std::optional<glm::tvec4<float,0> > *mClippingRect;
  const mce::Mesh *mMesh;
  const glm::tmat4x4<float,0> *mWorldMatrix;
  boost::container::static_vector<dragon::res::ServerTexture,4> mTextures;
  const mce::Color *mTintColor;
  const glm::tvec4<float,0> *mChangeColor;
  float mHudOpacity;
  const mce::framebuilder::GlintDescription *mGlintDescription;
  bool mIsMultiColorTint;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderUITextDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderUITextDescription
{
  const mce::Mesh *mMesh;
  const glm::tmat4x4<float,0> *mWorldMatrix;
  const dragon::res::ServerTexture mTexture;
  const mce::Color *mColor;
  const std::optional<glm::tvec4<float,0> > *mClipRegion;
  const std::optional<mce::Font::RenderingParameters> *mParameters;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderUIImGuiDescription::DrawItem`
```
const struct __cppobj mce::framebuilder::RenderUIImGuiDescription::DrawItem
{
  const glm::tvec4<float,0> mScissor;
  const unsigned int mIndexBase;
  const unsigned int mIndexCount;
  const dragon::res::ServerTexture mTexture;
};

```

### `mce::framebuilder::RenderUIImGuiDescription`
```
const struct __cppobj mce::framebuilder::RenderUIImGuiDescription
{
  const dragon::mesh::VertexFormat *mVbFormat;
  const gsl::span<unsigned char const ,-1> mVbData;
  const gsl::span<unsigned short const ,-1> mIbData;
  const gsl::span<mce::framebuilder::RenderUIImGuiDescription::DrawItem const ,-1> mItems;
  const glm::tmat4x4<float,0> mProj;
};

```

### `mce::framebuilder::RenderUIVRDescription`
```
const struct mce::framebuilder::RenderUIVRDescription
{
  const mce::Mesh *mMesh;
};

```

### `mce::framebuilder::RenderCubemapDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderCubemapDescription
{
  dragon::res::ServerTexture mCubemap;
  glm::tmat4x4<float,0> mWorldMatrix;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderEndSkyDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderEndSkyDescription
{
  const mce::Mesh *mMesh;
  const dragon::res::ServerTexture mTexture;
  const unsigned __int16 mViewId;
  mce::Color mColor;
  glm::tmat4x4<float,0> mWorldMatrix;
  glm::tmat4x4<float,0> mUVTransformMatrix;
};

```

### `mce::framebuilder::RenderLegacyCubemapDescription`
```
const struct __cppobj __declspec(align(4)) mce::framebuilder::RenderLegacyCubemapDescription
{
  const mce::Mesh *mMesh;
  dragon::res::ServerTexture mTexture;
  const glm::tmat4x4<float,0> *mWorldMatrix;
  const glm::tmat4x4<float,0> *mCubemapRotationMatrix;
  glm::tvec3<float,0> mSortOrigin;
  unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderSkyDescription`
```
const struct __declspec(align(8)) mce::framebuilder::RenderSkyDescription
{
  const mce::Mesh *mMesh;
  mce::Color mColor;
  mce::Color mFogColor;
  glm::tmat4x4<float,0> mWorldMatrix;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderStarsDescription`
```
const struct __declspec(align(8)) mce::framebuilder::RenderStarsDescription
{
  const mce::Mesh *mMesh;
  mce::Color mColor;
  glm::tmat4x4<float,0> mWorldMatrix;
  const unsigned __int16 mViewId;
  bool mIsCameraUnderLiquid;
};

```

### `mce::framebuilder::RenderSunMoonDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderSunMoonDescription
{
  const mce::Mesh *mMesh;
  const dragon::res::ServerTexture mTexture;
  mce::Color mColor;
  glm::tmat4x4<float,0> mWorldMatrix;
  const unsigned __int16 mViewId;
  bool mIsSun;
  bool mIsCameraUnderLiquid;
};

```

### `mce::framebuilder::RenderChunkGeometryDescription::PerChunkData`
```
const struct __cppobj mce::framebuilder::RenderChunkGeometryDescription::PerChunkData
{
  const RenderChunkDirectIndexData *mDirectIndexData;
  const RenderChunkDirectVertexData *mDirectVertexData;
  bool mUnsorted;
  unsigned int mIndicesOffset;
  unsigned int mIndicesCount;
  glm::tvec4<float,0> mChunkOriginAndScale;
  float mRenderChunkFogAlpha;
  gsl::span<mce::PointLight const ,-1> mPointLights;
};

```

### `mce::framebuilder::RenderChunkGeometryDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderChunkGeometryDescription
{
  boost::container::static_vector<dragon::res::ServerTexture const ,3> mTextures;
  gsl::span<mce::framebuilder::RenderChunkGeometryDescription::PerChunkData const ,-1> mChunks;
  const TerrainLayer *mTerrainLayer;
  mce::framebuilder::FogDescription mFog;
  float mFarChunkDistance;
  float mTime;
  glm::tmat4x4<float,0> mWorldAdjustmentMatrix;
  bool mIsUI;
  const dragon::frameobject::components::ViewSetId mViewId;
  glm::tvec3<float,0> mCameraPosition;
};

```

### `mce::framebuilder::RenderCrackDescription`
```
const struct __cppobj __declspec(align(8)) mce::framebuilder::RenderCrackDescription
{
  const mce::Mesh *mMesh;
  const dragon::res::ServerTexture mTexture;
  const glm::tmat4x4<float,0> *mWorldMatrix;
  const bool mAlphaTest;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::RenderSkinnedMeshDescription`
```
const struct __cppobj __declspec(align(4)) mce::framebuilder::RenderSkinnedMeshDescription
{
  glm::tmat4x4<float,0> mWorldTransform;
  const mce::Mesh *mMesh;
  int mSkinnedIndexCount;
  gsl::span<glm::tmat4x4<float,0>,-1> mBones;
  boost::container::static_vector<dragon::res::ServerTexture,8> mTextures;
  mce::MaterialPtr mMaterial;
  bool mIsDrawingUI;
  bool mIsDrawingFirstPersonObjects;
  mce::Color mColor;
  unsigned __int16 mSubRenderLayerIndex;
  const dragon::RenderMetadata mRenderMetadata;
  std::optional<glm::tvec4<float,0> > mClipRegion;
  const unsigned __int16 mViewId;
};

```

### `mce::framebuilder::FrameBuilder_vtbl`
```
struct /*VFT*/ mce::framebuilder::FrameBuilder_vtbl
{
  void (__fastcall *~FrameBuilder)(mce::framebuilder::FrameBuilder *this);
  bool (__fastcall *enabled)(mce::framebuilder::FrameBuilder *this);
  std::optional<dragon::platform::Statistics> *(__fastcall *getStatistics)(mce::framebuilder::FrameBuilder *this, std::optional<dragon::platform::Statistics> *result);
  bool (__fastcall *supportsRenderFeature)(mce::framebuilder::FrameBuilder *this, const mce::RenderFeature);
  bool (__fastcall *isDeviceRemoved)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *init)(mce::framebuilder::FrameBuilder *this, const std::variant<HWND__ *,std::monostate> *, const unsigned int, const unsigned int);
  bool (__fastcall *initialized)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *destroy)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *loadCoreAssets)(mce::framebuilder::FrameBuilder *this, const std::string *, std::function<std::string __cdecl(std::string const &)>);
  mce::framebuilder::AsyncLoadResult (__fastcall *loadAsyncAssets)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *startFrame)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *endFrame)(mce::framebuilder::FrameBuilder *this, mce::framebuilder::FrameBuilderContext *);
  void (__fastcall *discardFrame)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *setTerrainAtlasTexture)(mce::framebuilder::FrameBuilder *this, const mce::ClientTexture *);
  void (__fastcall *updateSurfaceParameters)(mce::framebuilder::FrameBuilder *this, const std::variant<HWND__ *,std::monostate> *);
  void (__fastcall *updateWindowSize)(mce::framebuilder::FrameBuilder *this, const unsigned int, const unsigned int);
  void (__fastcall *updateClientViewSize)(mce::framebuilder::FrameBuilder *this, const glm::tvec2<float,0> *);
  bool (__fastcall *updateMsaaLevel)(mce::framebuilder::FrameBuilder *this, const unsigned __int8);
  void (__fastcall *updateVSync)(mce::framebuilder::FrameBuilder *this, dragon::platform::VerticalSync);
  void (__fastcall *createMaterial)(mce::framebuilder::FrameBuilder *this, const mce::RenderMaterial *);
  void (__fastcall *evictMaterialCache)(mce::framebuilder::FrameBuilder *this);
  dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle> *(__fastcall *createExternalTexture)(mce::framebuilder::FrameBuilder *this, dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle> *result, std::optional<std::variant<std::monostate,dragon::platform::GLTextureWrapper,dragon::platform::WindowsTextureWrapper> >);
  void (__fastcall *updateExternalTexture)(mce::framebuilder::FrameBuilder *this, dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>, std::optional<std::variant<std::monostate,dragon::platform::GLTextureWrapper,dragon::platform::WindowsTextureWrapper> >, std::function<void __cdecl(dragon::rendering::SharedTextureHandle)>);
  dragon::res::ServerTexture *(__fastcall *wrapExternalTexture)(mce::framebuilder::FrameBuilder *this, dragon::res::ServerTexture *result, dragon::platform::RenderAPI, const dragon::res::TextureDescription *, void *);
  void (__fastcall *createRenderChunk)(mce::framebuilder::FrameBuilder *this, const dragon::RenderMetadata *);
  void (__fastcall *destroyRenderChunk)(mce::framebuilder::FrameBuilder *this, const dragon::RenderMetadata *);
  void (__fastcall *generateRenderChunkVertexData)(mce::framebuilder::FrameBuilder *this, RenderChunkDirectVertexData *, const std::array<RangeIndices,18> *, const gsl::span<unsigned char const ,-1> *, const unsigned __int64 *, const mce::VertexFormat *, const int *);
  void (__fastcall *generateRenderChunkIndexData)(mce::framebuilder::FrameBuilder *this, RenderChunkDirectIndexData *, const std::array<RangeIndices,18> *, const gsl::span<unsigned char const ,-1> *, const dragon::mesh::IndexSize);
  void (__fastcall *freeRenderChunkVertexData)(mce::framebuilder::FrameBuilder *this, RenderChunkDirectVertexData *);
  void (__fastcall *freeRenderChunkIndexData)(mce::framebuilder::FrameBuilder *this, RenderChunkDirectIndexData *);
  void (__fastcall *debugPrintToScreen)(mce::framebuilder::FrameBuilder *this, std::function<void __cdecl(char const *)>);
  void (__fastcall *debugDeclareSceneCamera)(mce::framebuilder::FrameBuilder *this, const mce::framebuilder::CameraDescriptionOrthographic *, const mce::framebuilder::BufferClearDescription *);
  void (__fastcall *debugDeclareSceneCamera)(mce::framebuilder::FrameBuilder *this, const mce::framebuilder::CameraDescriptionPerspective *, const mce::framebuilder::BufferClearDescription *);
  dragon::VertexBufferResourceService *(__fastcall *getVertexBufferResourceService)(mce::framebuilder::FrameBuilder *this);
  dragon::IndexBufferResourceService *(__fastcall *getIndexBufferResourceService)(mce::framebuilder::FrameBuilder *this);
  dragon::ShaderBufferResourceService *(__fastcall *getShaderBufferResourceService)(mce::framebuilder::FrameBuilder *this);
  dragon::TextureResourceService *(__fastcall *getTextureResourceService)(mce::framebuilder::FrameBuilder *this);
  bool (__fastcall *isRayTracingCapable)(mce::framebuilder::FrameBuilder *this);
  bool (__fastcall *isRayTracingEnabled)(mce::framebuilder::FrameBuilder *this);
  bool (__fastcall *isUpscalingAvailable)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *setUpscaling)(mce::framebuilder::FrameBuilder *this, bool);
  bool (__fastcall *isUpscalingEnabled)(mce::framebuilder::FrameBuilder *this);
  float (__fastcall *getUpscalingFactor)(mce::framebuilder::FrameBuilder *this);
  const gsl::basic_string_span<char const ,-1> *(__fastcall *getUpscalingInfo)(mce::framebuilder::FrameBuilder *this, const gsl::basic_string_span<char const ,-1> *result);
  void (__fastcall *custom)(mce::framebuilder::FrameBuilder *this, const std::function<void __cdecl(mce::framebuilder::bgfxbridge::EntityCreationContext const &)> *);
  LevelCullerType (__fastcall *getLevelCullerType)(mce::framebuilder::FrameBuilder *this);
  FrustumCullerType (__fastcall *getFrustumCullerType)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *clearRenderingResourcesCache)(mce::framebuilder::FrameBuilder *this);
  unsigned __int16 (__fastcall *allocatePBRTextureDataHandle)(mce::framebuilder::FrameBuilder *this);
  void (__fastcall *freePBRTextureDataHandle)(mce::framebuilder::FrameBuilder *this, const unsigned __int16);
  void (__fastcall *updatePBRData)(mce::framebuilder::FrameBuilder *this, const unsigned __int16, const mce::framebuilder::PBRTextureDataDescription *);
  void (__fastcall *_insert)(mce::framebuilder::FrameBuilder *this, std::variant<std::reference_wrapper<mce::framebuilder::gamecomponents::VrConfiguration const >,std::reference_wrapper<mce::framebuilder::LivingRoomDescription const > >);
  void (__fastcall *_insert)(mce::framebuilder::FrameBuilder *this, std::variant<std::reference_wrapper<mce::framebuilder::RenderFlameBillboardDescription const >,std::reference_wrapper<mce::framebuilder::BlitFlipbookTextureDescription const >,std::reference_wrapper<mce::framebuilder::RenderParticleDescription const >,std::reference_wrapper<mce::framebuilder::RenderPlayerVisionDescription const >,std::reference_wrapper<mce::framebuilder::RenderShadowDescription const >,std::reference_wrapper<mce::framebuilder::RenderSequenceEffectDescription const >,std::reference_wrapper<mce::framebuilder::FadeToBlackDescription const > >);
  void (__fastcall *_insert)(mce::framebuilder::FrameBuilder *this, std::variant<std::reference_wrapper<mce::framebuilder::RenderUIGamefaceDescription const >,std::reference_wrapper<mce::framebuilder::RenderUIMeshDescription const >,std::reference_wrapper<mce::framebuilder::RenderUITextDescription const >,std::reference_wrapper<mce::framebuilder::RenderUIImGuiDescription const >,std::reference_wrapper<mce::framebuilder::RenderUIVRDescription const > >);
  void (__fastcall *_insert)(mce::framebuilder::FrameBuilder *this, std::variant<std::reference_wrapper<mce::framebuilder::RenderAtmosphereDescription const >,std::reference_wrapper<mce::framebuilder::RenderCubemapDescription const >,std::reference_wrapper<mce::framebuilder::RenderEndSkyDescription const >,std::reference_wrapper<mce::framebuilder::RenderLegacyCubemapDescription const >,std::reference_wrapper<mce::framebuilder::RenderSkyDescription const >,std::reference_wrapper<mce::framebuilder::RenderStarsDescription const >,std::reference_wrapper<mce::framebuilder::RenderSunMoonDescription const >,std::reference_wrapper<mce::framebuilder::RenderWeatherDescription const > >);
  void (__fastcall *_insert)(mce::framebuilder::FrameBuilder *this, std::variant<std::reference_wrapper<mce::framebuilder::RenderMeshFallbackDescription const >,std::reference_wrapper<mce::framebuilder::RenderChunkGeometryDescription const >,std::reference_wrapper<mce::framebuilder::RenderCrackDescription const >,std::reference_wrapper<mce::framebuilder::RenderItemInHandDescription const >,std::reference_wrapper<mce::framebuilder::RenderSkinnedMeshDescription const > >);
};

```

### `mce::FileWatcherNull`
```
struct __cppobj mce::FileWatcherNull : Bedrock::EnableNonOwnerReferences
{
};

```

### `MinecraftUIMeasureStrategy_vtbl`
```
struct /*VFT*/ MinecraftUIMeasureStrategy_vtbl
{
  void (__fastcall *~UIMeasureStrategy)(UIMeasureStrategy *this);
  MeasureResult *(__fastcall *measureText)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, int, int, const TextMeasureData *, const CaretMeasureData *);
  MeasureResult *(__fastcall *measureTextHeight)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, int, const TextMeasureData *, const CaretMeasureData *);
  MeasureResult *(__fastcall *measureTextWidth)(UIMeasureStrategy *this, MeasureResult *result, const FontHandle *, const std::string *, const TextMeasureData *, const CaretMeasureData *);
  std::string *(__fastcall *filterProfanityFromText)(UIMeasureStrategy *this, std::string *result, const std::string *, const bool);
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $C88A8F1E2E2F4697F8F59C79BA55129F ___u0;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MinecraftInputHandler`
```
struct __cppobj MinecraftInputHandler : IConfigListener
{
  std::unique_ptr<InputHandler> mInputHandler;
  IClientInstance *mClient;
  std::unique_ptr<MinecraftBindingFactoryMap> mBindingFactoryMap;
  std::unique_ptr<MinecraftInputMappingFactoryMap> mMappingFactoryMap;
  std::unique_ptr<SplitscreenJoinListener> mSplitscreenJoinListener;
  MouseMapper *mMouseMapper;
  std::unique_ptr<MinecraftInputHandlerProxy> mProxy;
};

```

### `Music`
```
struct __cppobj __declspec(align(8)) Music : Bedrock::EnableNonOwnerReferences
{
  Music_vtbl *__vftable /*VFT*/;
  Category mCategory;
  std::string mName;
  std::string mEventName;
  int mMinDelay;
  int mMaxDelay;
  float mVolume;
  float mFadeoutSeconds;
  bool mPlaylist;
  unsigned int mPlaylistIndex;
  std::vector<std::string> mOverrideInterruptibleCategories;
  bool mInitialized;
};

```

### `Music_vtbl`
```
struct /*VFT*/ Music_vtbl
{
  void (__fastcall *~Music)(Music *this);
  bool (__fastcall *hasTracks)(Music *this);
  void (__fastcall *nextTrack)(Music *this);
  void (__fastcall *setActive)(Music *this, bool);
};

```

### `MusicManager`
```
struct __cppobj __declspec(align(8)) MusicManager
{
  Music mMenu;
  Music mGame;
  Music mCreative;
  Music mNether;
  Music mEnd;
  Music mEndboss;
  Music mCredits;
  Music mWater;
  Music mSoulsandValley;
  Music mCrimsonForest;
  Music mWarpedForest;
  Music mNetherWastes;
  Music mLoop;
  CustomMusic mCustomMusic;
  int mNextSongDelay;
  Bedrock::NonOwnerPointer<SoundPlayerInterface> mSoundPlayer;
  Bedrock::NonOwnerPointer<Music> mCurrentMusic;
  Category mLastMusicCategory;
  std::string mCurrentMusicName;
  std::vector<Bedrock::NonOwnerPointer<Music>> mMusicCategories;
  bool mEnabled;
  bool mDisableOriginMusic;
  bool mContinueLoopMusic;
};

```

### `MinecoinTransactionHandler`
```
struct __cppobj MinecoinTransactionHandler : TransactionHandler
{
  GameStore *mGameStore;
  PurchaseCache *mPurchaseCache;
  IEntitlementManager *mEntitlementManager;
  IMinecraftEventing *mEventing;
};

```

### `MinecoinTransactionHandler_vtbl`
```
struct /*VFT*/ MinecoinTransactionHandler_vtbl
{
  void (__fastcall *~TransactionHandler)(TransactionHandler *this);
  void (__fastcall *update)(TransactionHandler *this);
  void (__fastcall *transactPurchase)(TransactionHandler *this, Offer *, TransactionContext *, PurchasePath);
  bool (__fastcall *transactFulfillment)(TransactionHandler *this, Offer *, std::shared_ptr<Purchase>, std::unique_ptr<TransactionContext>, PurchasePath);
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $565C40948716BD72D64BA5E044635E17 ___u0;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> > >`
```
struct __cppobj MPMCQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> > >
{
  moodycamel::ConcurrentQueue<std::pair<enum MinecraftGame::DeferredTaskCategory,std::function<void __cdecl(enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason)> >,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MouseButtonBinding`
```
struct __cppobj __declspec(align(8)) MouseButtonBinding
{
  std::string buttonName;
  int buttonNum;
};

```

### `MinecraftKeyboardManager`
```
struct __cppobj MinecraftKeyboardManager : KeyboardManager
{
  bool mDelayedInputResume;
  __int8 mIsKeyboardActive : 1;
  __int8 mIsKeyboardEnabled : 1;
  __int8 mKeyboardClosedEvent : 1;
  float mKeyboardForcedHeight;
  std::function<void __cdecl(void)> mResumeInputCallback;
  std::function<void __cdecl(int)> mDisableInputToOtherClientsCallback;
  IClientInstance *mClientInstance;
  bool mWasEnabledWithMultiline;
  int mMaxLength;
};

```

### `MinecraftKeyboardManager_vtbl`
```
struct /*VFT*/ MinecraftKeyboardManager_vtbl
{
  void (__fastcall *~KeyboardManager)(KeyboardManager *this);
  bool (__fastcall *tryEnableKeyboard)(KeyboardManager *this, const std::string *, int, bool, bool, bool, const Vec2 *, float);
  bool (__fastcall *isFullScreenKeyboard)(KeyboardManager *this);
  void (__fastcall *disableKeyboard)(KeyboardManager *this);
  void (__fastcall *setKeyboardActive)(KeyboardManager *this, bool);
  bool (__fastcall *canActivateKeyboard)(KeyboardManager *this);
  bool (__fastcall *isKeyboardEnabled)(KeyboardManager *this);
  bool (__fastcall *isKeyboardActive)(KeyboardManager *this);
  bool (__fastcall *wasEnabledWithMultiline)(KeyboardManager *this);
  int (__fastcall *getMaxLength)(KeyboardManager *this);
  float (__fastcall *getKeyboardHeight)(KeyboardManager *this);
  void (__fastcall *setForcedHeight)(KeyboardManager *this, float);
  bool (__fastcall *tryClaimKeyboardOwnership)(KeyboardManager *this);
  void (__fastcall *releaseKeyboardOwnership)(KeyboardManager *this);
  bool (__fastcall *getKeyboardClosedEvent)(KeyboardManager *this);
  void (__fastcall *clearKeyboardClosedEvent)(KeyboardManager *this);
  void (__fastcall *updateTextEditBoxPosition)(KeyboardManager *this, const RectangleArea *, const Vec2 *, const Vec2 *);
  void (__fastcall *setResumeInputCallback)(MinecraftKeyboardManager *this, std::function<void __cdecl(void)>);
  void (__fastcall *setDisableInputToOtherClientsCallback)(MinecraftKeyboardManager *this, std::function<void __cdecl(int)>);
};

```

### `Model`
```
struct __cppobj Model : AppPlatformListener
{
  Vec3 mLeashOffset;
  float mAttackTime;
  bool mYoung;
  bool mRiding;
  MaterialVariants mMaterialVariants;
  std::vector<ModelPart *> mAllParts;
  std::unordered_map<HashedString,ParticleEffectPtr> mParticleEffectsMap;
  std::unordered_map<HashedString,ModelPartLocator> mLocators;
  std::vector<std::pair<RenderController,ExpressionNode>> mRenderControllers;
  std::vector<std::unique_ptr<DataDrivenGeometry>> mGeometries;
  unsigned __int64 mQueryableGeometryIndex;
};

```

### `Model_vtbl`
```
struct /*VFT*/ Model_vtbl
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

### `MobEffectsLayout`
```
struct __cppobj MobEffectsLayout
{
  IClientInstance *mClient;
  RectangleArea mTouchArea;
  std::vector<EffectDisplayInfo> mEffectDisplays;
  int mLastEffectCount;
  int mIconStartY;
  int mIconStartX;
  int mIconSize;
  int mOffsetToStartingPositionY;
  int mOffsetToStartingPositionX;
  int mWidth;
  int mHeight;
};

```

### `MinecraftClientScriptEngine`
```
struct __cppobj MinecraftClientScriptEngine : ScriptEngineWithContext<ScriptClientContext>
{
  std::unique_ptr<ScriptClientPacketEventListener> mPacketEventListener;
  std::unique_ptr<ScriptTelemetryEventListener> mTelemetryListener;
  std::unique_ptr<ScriptClientInstanceEventListener> mClientInstanceEventListener;
  std::unique_ptr<ScriptClientLevelEventListener> mLevelListener;
  std::unique_ptr<ScriptHitDetectEventListener> mScriptHitDetectListener;
  std::unique_ptr<entt::basic_registry<enum entt::entity>> mRegistry;
  ClientInstance *mClientInstance;
};

```

### `MinecraftClientScriptEngine_vtbl`
```
struct /*VFT*/ MinecraftClientScriptEngine_vtbl
{
  void (__fastcall *~ScriptFramework)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *initialize)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *shutdown)(ScriptApi::ScriptFramework *this);
  bool (__fastcall *onLogReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onInfoReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onWarnReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *onErrorReceived)(ScriptEngine *this, const std::string *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const Actor *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpDefineActor)(ScriptEngine *this, const ActorUniqueID *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetActor)(ScriptEngine *this, const ScriptObjectBinder *, Actor **);
  bool (__fastcall *helpGetBlockSource)(ScriptEngine *this, const ScriptObjectBinder *, BlockSource **);
  bool (__fastcall *helpGetBlock)(ScriptEngine *this, const ScriptObjectBinder *, const Block **, const BlockSource *);
  bool (__fastcall *helpGetBlockPos)(ScriptEngine *this, const ScriptObjectBinder *, BlockPos *);
  bool (__fastcall *helpDefineLevel)(ScriptEngine *this, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *helpGetLevel)(ScriptEngine *this, const ScriptObjectBinder *, Level **);
  bool (__fastcall *helpDefineItemStack)(ScriptEngine *this, const ItemInstance *, ScriptApi::ScriptObjectHandle *);
  void (__fastcall *helpPopulateEcsID)(ScriptEngine *this, Json::Value *);
  bool (__fastcall *setupInterface)(ScriptEngine *this);
  bool (__fastcall *registerEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEventData)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *onEventReceivedFromScriptEngine)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *);
  bool (__fastcall *createEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *destroyEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *isValidEntity)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, bool *);
  bool (__fastcall *registerComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *createComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *hasComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *, bool *);
  bool (__fastcall *destroyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *applyComponentChanges)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerScriptOnlyComponent)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const std::string *, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const std::string *, const std::string *, const std::string *, const std::string *);
  bool (__fastcall *registerQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const long double, const long double, const long double, const long double, const long double, const long double, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *getEntitiesFromQuery)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, std::vector<ScriptApi::ScriptObjectHandle> *);
  bool (__fastcall *addFilter)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, const ScriptApi::ScriptObjectHandle *, const std::string *);
  bool (__fastcall *getBlock)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const BlockPos *, const ScriptApi::ScriptObjectHandle *, const ScriptObjectBinder *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ActorUniqueID *);
  bool (__fastcall *helpDefineTickingArea)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptApi::ScriptObjectHandle *, const ITickingArea *);
  void (__fastcall *onExecuteCommandCalled)(ScriptEngine *this, const ScriptApi::ScriptVersionInfo *, ScriptCommand *);
  bool (__fastcall *executeCommand)(ScriptEngine *this, const ScriptCommand *);
  bool (__fastcall *onCommandOutputCallback)(ScriptEngine *this, unsigned int, Json::Value *);
  bool (__fastcall *_registerSystemObjects)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  bool (__fastcall *_hasEvent)(ScriptEngine *this, const std::string *);
  bool (__fastcall *_helpRegisterSystemCallbacks)(ScriptEngine *this, const ScriptApi::ScriptObjectHandle *);
  void (__fastcall *_handleError)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
  void (__fastcall *_handleWarning)(ScriptEngine *this, const ScriptApi::ScriptReportItem *);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $C121F4620A648719078F94D5C15923F7 ___u0;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::function<void __cdecl(Social::MultiplayerEDU &)> >`
```
struct __cppobj MPMCQueue<std::function<void __cdecl(Social::MultiplayerEDU &)> >
{
  moodycamel::ConcurrentQueue<std::function<void __cdecl(Social::MultiplayerEDU &)>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MinecraftGame_vtbl`
```
struct /*VFT*/ MinecraftGame_vtbl
{
  void (__fastcall *~IIslandCore)(Bedrock::IIslandCore *this);
  unsigned __int16 (__fastcall *getId)(Bedrock::IIslandCore *this);
  bool (__fastcall *start)(Bedrock::IIslandCore *this);
  bool (__fastcall *suspend)(Bedrock::IIslandCore *this);
  bool (__fastcall *resume)(Bedrock::IIslandCore *this);
  bool (__fastcall *stop)(Bedrock::IIslandCore *this);
  void (__fastcall *mainUpdate)(Bedrock::IIslandCore *this);
  void (__fastcall *processActivationArguments)(Bedrock::IIslandCore *this, const Bedrock::ActivationArguments *);
  bool (__fastcall *handleBack)(MinecraftGame *this, bool);
};

```

### `MoveInputHandler_vtbl`
```
struct /*VFT*/ MoveInputHandler_vtbl
{
  void (__fastcall *~MoveInput)(MoveInput *this);
  void (__fastcall *tick)(MoveInput *this, IPlayerMovementProxy *);
  void (__fastcall *render)(MoveInput *this, float);
  void (__fastcall *setKey)(MoveInput *this, int, bool);
  void (__fastcall *clearInputState)(MoveInput *this);
  void (__fastcall *clearMovementState)(MoveInput *this);
  bool (__fastcall *allowPicking)(MoveInput *this, float, float);
  void (__fastcall *setJumping)(MoveInput *this, bool);
  void (__fastcall *setAutoJumpingInWater)(MoveInput *this, bool);
  bool (__fastcall *isChangeHeight)(MoveInput *this);
  void (__fastcall *setSneakDown)(MoveInput *this, bool);
  bool (__fastcall *isPlayerMoving)(MoveInput *this);
  const Vec3 *(__fastcall *getGazeDirection)(MoveInput *this);
  void (__fastcall *fillInputPacket)(MoveInputHandler *this, PlayerAuthInputPacket *);
  void (__fastcall *registerInputHandlers)(MoveInputHandler *this, InputHandler *);
  std::unique_ptr<IReplayableActorInput> *(__fastcall *createSnapshot)(MoveInputHandler *this, std::unique_ptr<IReplayableActorInput> *result);
};

```

### `MinecraftBindingFactoryMap::NullBindingFactory`
```
const struct __cppobj MinecraftBindingFactoryMap::NullBindingFactory : BindingFactory
{
};

```

### `MinecraftBindingFactoryMap::NullBindingFactory_vtbl`
```
struct /*VFT*/ MinecraftBindingFactoryMap::NullBindingFactory_vtbl
{
  void (__fastcall *~BindingFactory)(BindingFactory *this);
  std::function<bool __cdecl(void)> *(__fastcall *getBooleanBinding)(BindingFactory *this, std::function<bool __cdecl(void)> *result, const std::string *);
  std::function<std::string __cdecl(void)> *(__fastcall *getStringBinding)(BindingFactory *this, std::function<std::string __cdecl(void)> *result, const std::string *);
  std::function<glm::tvec2<float,0> __cdecl(void)> *(__fastcall *getPointBinding)(BindingFactory *this, std::function<glm::tvec2<float,0> __cdecl(void)> *result, const std::string *);
  std::function<RectangleArea __cdecl(void)> *(__fastcall *getAreaBinding)(BindingFactory *this, std::function<RectangleArea __cdecl(void)> *result, const std::string *);
};

```

### `MinecraftBindingFactoryMap`
```
struct __cppobj MinecraftBindingFactoryMap : BindingFactoryMap
{
  const ControllerIDtoClientMap *mCIDToClientMap;
  const MinecraftBindingFactoryMap::NullBindingFactory mNullBindingFactory;
};

```

### `MinecraftBindingFactoryMap_vtbl`
```
struct /*VFT*/ MinecraftBindingFactoryMap_vtbl
{
  void (__fastcall *~BindingFactoryMap)(BindingFactoryMap *this);
  const BindingFactory *(__fastcall *getBindingFactory)(BindingFactoryMap *this, int);
};

```

### `MinecraftInputMappingFactoryMap::NullInputMappingFactory`
```
struct __cppobj MinecraftInputMappingFactoryMap::NullInputMappingFactory : InputMappingFactory
{
  const InputMapping mEmptyInputMapping;
};

```

### `MinecraftInputMappingFactoryMap::NullInputMappingFactory_vtbl`
```
struct /*VFT*/ MinecraftInputMappingFactoryMap::NullInputMappingFactory_vtbl
{
  void (__fastcall *~InputMappingFactory)(InputMappingFactory *this);
  const InputMapping *(__fastcall *getMapping)(InputMappingFactory *this, const std::string *);
};

```

### `MinecraftInputMappingFactoryMap`
```
struct __cppobj MinecraftInputMappingFactoryMap : InputMappingFactoryMap
{
  const ControllerIDtoClientMap *mCIDToClientMap;
  MinecraftInputMappingFactoryMap::NullInputMappingFactory mNullInputMappingFactory;
};

```

### `MinecraftInputMappingFactoryMap_vtbl`
```
struct /*VFT*/ MinecraftInputMappingFactoryMap_vtbl
{
  void (__fastcall *~InputMappingFactoryMap)(InputMappingFactoryMap *this);
  InputMappingFactory *(__fastcall *getInputMappingFactory)(InputMappingFactoryMap *this, int);
};

```

### `MouseMapper`
```
struct __cppobj __declspec(align(8)) MouseMapper : InputDeviceMapper
{
  int mYAxisInversionFactor;
  std::unordered_multimap<int,unsigned int> mMouseButtonToButtonIdMap;
  std::vector<unsigned int> mMouseWheelUpButtonIds;
  std::vector<unsigned int> mMouseWheelDownButtonIds;
  int mPrimaryGameControllerId;
};

```

### `MouseMapper_vtbl`
```
struct /*VFT*/ MouseMapper_vtbl
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

### `MinecraftInputHandlerProxyCallbacks`
```
const struct __cppobj MinecraftInputHandlerProxyCallbacks
{
  std::function<void __cdecl(bool)> mSetInputEnabled;
};

```

### `MinecraftInputHandlerProxy`
```
struct __cppobj MinecraftInputHandlerProxy
{
  const MinecraftInputHandlerProxyCallbacks mCallbacks;
};

```

### `MenuPointer`
```
struct __cppobj MenuPointer
{
  bool mPressed;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $922113CC63D86E8A75D6DAB28258DF7A ___u0;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter> >`
```
struct __cppobj MPMCQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter> >
{
  moodycamel::ConcurrentQueue<std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MobEvents`
```
struct __cppobj __declspec(align(8)) MobEvents
{
  MobEvents_vtbl *__vftable /*VFT*/;
  std::array<MobEvent,3> mMobEvents;
  BasicTimer mSaveTimer;
  LevelStorage *mLevelStorage;
  bool mEventsEnabled;
  bool mNeedsToSave;
};

```

### `MobEvents_vtbl`
```
struct /*VFT*/ MobEvents_vtbl
{
  void (__fastcall *~MobEvents)(MobEvents *this);
};

```

### `MobEvent`
```
struct __cppobj __declspec(align(8)) MobEvent
{
  std::string mName;
  std::string mLocalizableName;
  bool mEnabled;
  bool mIsDefaultSet;
};

```

### `MPMCQueue<std::string >`
```
struct __cppobj MPMCQueue<std::string >
{
  moodycamel::ConcurrentQueue<std::string,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MultiPlayerLevel::DelayedActorDelete`
```
struct __cppobj MultiPlayerLevel::DelayedActorDelete
{
  ActorUniqueID mEntityUniqueID;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeToDelete;
};

```

### `MultiPlayerLevel`
```
const struct __cppobj MultiPlayerLevel : Level
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastSyncTime;
  __int64 mServerTickOffset;
  SmallSet<std::unique_ptr<Actor> > mEntities;
  std::vector<MultiPlayerLevel::DelayedActorDelete> mDelayedEntityDeleteList;
  std::unordered_set<std::string> mPickBlacklist;
  TrustedSkinHelper mTrustedSkinHelper;
};

```

### `Material`
```
const struct __cppobj Material
{
  MaterialType mType;
  bool mFlammable;
  bool mNeverBuildable;
  bool mAlwaysDestroyable;
  bool mReplaceable;
  bool mLiquid;
  float mTranslucency;
  bool mBlocksMotion;
  bool mBlocksPrecipitation;
  bool mSolid;
  bool mSuperHot;
};

```

### `MobDescriptor`
```
struct __cppobj MobDescriptor
{
  ActorFilterGroup mTargetFilter;
  float mMaxDistance;
  float mMaxHeight;
  float mMaxFlee;
  float mWalkSpeedModifier;
  float mSprintSpeedModifier;
  bool mOverrideMustSee;
  bool mMustSee;
  bool mCheckIfOutnumbered;
  int mMustSeeForgetTicks;
  int mPriority;
};

```

### `MobEffectChangeDescription`
```
struct __cppobj MobEffectChangeDescription : AttributeDescription
{
  std::vector<MobEffectInstance> mAddEffects;
  std::vector<std::string> mRemoveEffects;
};

```

### `MobEffectChangeDescription_vtbl`
```
struct /*VFT*/ MobEffectChangeDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlDescription_vtbl`
```
struct /*VFT*/ MoveControlDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ManagedWanderingTraderDescription`
```
struct __cppobj ManagedWanderingTraderDescription : ComponentDescription
{
};

```

### `ManagedWanderingTraderDescription_vtbl`
```
struct /*VFT*/ ManagedWanderingTraderDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlBasicDescription`
```
struct __cppobj MoveControlBasicDescription : MoveControlDescription
{
};

```

### `MoveControlBasicDescription_vtbl`
```
struct /*VFT*/ MoveControlBasicDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlDolphinDescription_vtbl`
```
struct /*VFT*/ MoveControlDolphinDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlFlyDescription`
```
struct __cppobj MoveControlFlyDescription : MoveControlDescription
{
};

```

### `MoveControlFlyDescription_vtbl`
```
struct /*VFT*/ MoveControlFlyDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlSkipDescription`
```
struct __cppobj MoveControlSkipDescription : MoveControlDescription
{
};

```

### `MoveControlSkipDescription_vtbl`
```
struct /*VFT*/ MoveControlSkipDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlHoverDescription`
```
struct __cppobj MoveControlHoverDescription : MoveControlDescription
{
};

```

### `MoveControlHoverDescription_vtbl`
```
struct /*VFT*/ MoveControlHoverDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MoveControlSwayDescription`
```
struct __cppobj MoveControlSwayDescription : MoveControlDescription
{
  float mSwayFrequency;
  float mSwayAmplitude;
};

```

### `MoveControlSwayDescription_vtbl`
```
struct /*VFT*/ MoveControlSwayDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `MapItemTrackedActor`
```
struct __cppobj MapItemTrackedActor
{
  MapItemTrackedActor::UniqueId mUniqueId;
  int mStep;
  bool mNeedsResend;
  unsigned int mMinDirtyX;
  unsigned int mMinDirtyY;
  unsigned int mMaxDirtyX;
  unsigned int mMaxDirtyY;
  int mTick;
  float mLastRotation;
  _BYTE mDecorationType[1];
  AutomaticID<Dimension,int> mDimensionId;
  std::shared_ptr<ChunkViewSource> mChunkViewSource;
};

```

### `MapItemSavedData`
```
struct __cppobj MapItemSavedData
{
  unsigned __int64 mUpdateInterval;
  ActorUniqueID mMapId;
  ActorUniqueID mParentMapId;
  bool mIsFullyExplored;
  bool mPreviewIncomplete;
  BlockPos mOrigin;
  AutomaticID<Dimension,int> mDimension;
  char mScale;
  std::vector<unsigned int> mPixels;
  std::vector<std::shared_ptr<MapItemTrackedActor>> mTrackedEntities;
  bool mUnlimitedTracking;
  bool mDirtyForSave;
  bool mDirtyPixelData;
  bool mLocked;
  std::vector<std::pair<MapItemTrackedActor::UniqueId,std::shared_ptr<MapDecoration> >> mDecorations;
};

```

### `MoveTrackComponent`
```
struct __cppobj __declspec(align(8)) MoveTrackComponent
{
  Actor *mEntity;
  std::vector<Vec3> mTrackList;
  int mFrameCount;
  int mFrameInterval;
  bool mActivated;
};

```

### `MerchantRecipeList`
```
struct __cppobj MerchantRecipeList
{
  MerchantRecipeList_vtbl *__vftable /*VFT*/;
  std::vector<MerchantRecipe> mRecipeList;
  std::vector<unsigned int> mTierExpRequirements;
};

```

### `MerchantRecipe`
```
struct __cppobj __declspec(align(8)) MerchantRecipe
{
  ItemInstance mBuyA;
  ItemInstance mBuyB;
  ItemInstance mSell;
  int mTier;
  int mUses;
  int mMaxUses;
  unsigned int mTraderExp;
  bool mRewardExp;
  int mDemand;
  int mBuyCountA;
  int mBuyCountB;
  float mPriceMultiplierA;
  float mPriceMultiplierB;
  TypedServerNetId<RecipeNetIdTag,unsigned int,0> mRecipeNetId;
};

```

### `MerchantRecipeList_vtbl`
```
struct /*VFT*/ MerchantRecipeList_vtbl
{
  void (__fastcall *~MerchantRecipeList)(MerchantRecipeList *this);
  MerchantRecipe *(__fastcall *getRecipeFor)(MerchantRecipeList *this, const ItemInstance *, const ItemInstance *, int);
  void (__fastcall *addIfNewOrBetter)(MerchantRecipeList *this, MerchantRecipe *);
  MerchantRecipe *(__fastcall *getMatchingRecipeFor)(MerchantRecipeList *this, const MerchantRecipe *);
  MerchantRecipe *(__fastcall *getMatchingRecipeFor)(MerchantRecipeList *this, const ItemInstance *, const ItemInstance *, const ItemInstance *);
  void (__fastcall *load)(MerchantRecipeList *this, const CompoundTag *);
  std::unique_ptr<CompoundTag> *(__fastcall *createTag)(MerchantRecipeList *this, std::unique_ptr<CompoundTag> *result, bool);
};

```

### `mce::ResourcePointerHelper<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > >`
```
struct __cppobj mce::ResourcePointerHelper<std::shared_ptr<mce::ResourceBlockTemplate<std::variant<std::monostate,mce::Texture,dragon::res::ClientTexture>,mce::PerFrameHandleTracker,mce::ResourceServiceTextureDescription> > >
{
};

```

### `moodycamel::ConsumerToken`
```
struct __cppobj moodycamel::ConsumerToken
{
  unsigned int initialOffset;
  unsigned int lastKnownGlobalOffset;
  unsigned int itemsConsumedFromCurrent;
  moodycamel::details::ConcurrentQueueProducerTypelessBase *currentProducer;
  moodycamel::details::ConcurrentQueueProducerTypelessBase *desiredProducer;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry`
```
struct moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry
{
  unsigned __int64 base;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::Block *block;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer : moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  std::atomic<moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexHeader *> blockIndex;
  unsigned __int64 pr_blockIndexSlotsUsed;
  unsigned __int64 pr_blockIndexSize;
  unsigned __int64 pr_blockIndexFront;
  moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer::BlockIndexEntry *pr_blockIndexEntries;
  void *pr_blockIndexRaw;
};

```

### `moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ExplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<std::function<void __cdecl(void)>,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `mce::Math::PairHash`
```
struct __cppobj mce::Math::PairHash
{
};

```

### `mce::Math::Tuple3Hash`
```
struct __cppobj mce::Math::Tuple3Hash
{
};

```

### `MovePriorityQueue<NetworkChunkInserter::PendingChunk,std::greater<NetworkChunkInserter::PendingChunk> >`
```
struct __cppobj MovePriorityQueue<NetworkChunkInserter::PendingChunk,std::greater<NetworkChunkInserter::PendingChunk> >
{
  std::vector<NetworkChunkInserter::PendingChunk> mC;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block
{
  $922113CC63D86E8A75D6DAB28258DF7A ___u0;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block *next;
  std::atomic<unsigned __int64> elementsCompletelyDequeued;
  std::atomic<bool> emptyFlags[32];
  std::atomic<unsigned int> freeListRefs;
  std::atomic<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListNext;
  std::atomic<bool> shouldBeOnFreeList;
  bool dynamicallyAllocated;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block>`
```
struct __cppobj moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block>
{
  std::atomic<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block *> freeListHead;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase`
```
struct __cppobj moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase : moodycamel::details::ConcurrentQueueProducerTypelessBase
{
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl *__vftable /*VFT*/;
  std::atomic<unsigned __int64> tailIndex;
  std::atomic<unsigned __int64> headIndex;
  std::atomic<unsigned __int64> dequeueOptimisticCount;
  std::atomic<unsigned __int64> dequeueOvercommit;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block *tailBlock;
  bool isExplicit;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits> *parent;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>`
```
struct __cppobj __declspec(align(8)) moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>
{
  std::atomic<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *> producerListTail;
  std::atomic<unsigned int> producerCount;
  std::atomic<unsigned __int64> initialBlockPoolIndex;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block *initialBlockPool;
  unsigned __int64 initialBlockPoolSize;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::FreeList<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::Block> freeList;
  std::atomic<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *> implicitProducerHash;
  std::atomic<unsigned __int64> implicitProducerHashCount;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash initialImplicitProducerHash;
  std::array<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP,32> initialImplicitProducerHashEntries;
  std::atomic_flag implicitProducerHashResizeInProgress;
  std::atomic<unsigned int> nextExplicitConsumerId;
  std::atomic<unsigned int> globalExplicitConsumerOffset;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer`
```
struct __cppobj moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer : moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase
{
  unsigned __int64 nextBlockIndexCapacity;
  std::atomic<moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer::BlockIndexHeader *> blockIndex;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl`
```
struct /*VFT*/ moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer_vtbl
{
  void (__fastcall *~ProducerBase)(moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ProducerBase *this);
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP`
```
struct __cppobj moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP
{
  std::atomic<unsigned int> key;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducer *value;
};

```

### `moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash`
```
struct moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash
{
  unsigned __int64 capacity;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerKVP *entries;
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits>::ImplicitProducerHash *prev;
};

```

### `MPMCQueue<unsigned __int64>`
```
struct __cppobj MPMCQueue<unsigned __int64>
{
  moodycamel::ConcurrentQueue<unsigned __int64,moodycamel::ConcurrentQueueDefaultTraits> mQueue;
};

```

### `MolangItemStackBasePtr`
```
struct __cppobj MolangItemStackBasePtr
{
  ItemStackBase *mItemStackBasePtr;
};

```

### `MolangActorPtr`
```
struct __cppobj MolangActorPtr
{
  Actor *mActor;
};

```

### `MolangActorIdPtr`
```
struct __cppobj MolangActorIdPtr
{
  ActorUniqueID mActorId;
};

```

### `MolangScriptArgUnsetType`
```
struct __cppobj MolangScriptArgUnsetType
{
};

```

### `MolangScriptArgReturnValue`
```
struct __cppobj MolangScriptArgReturnValue
{
  const MolangScriptArg *mReturnValue;
};

```

### `MolangScriptArgMissingVariableOrActorValue`
```
struct __cppobj MolangScriptArgMissingVariableOrActorValue
{
  _BYTE mVariableIndex[2];
};

```

### `MaterialTypeEnumHasher`
```
struct __cppobj MaterialTypeEnumHasher
{
};

```

### `MinecraftEventing`
```
struct __cppobj MinecraftEventing : IMinecraftEventing
{
  std::unique_ptr<Social::Events::EventManager> mEventManager;
  std::unique_ptr<TelemetryInfo> mTelemetryInfo;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  unsigned int mPrimaryLocalUserId;
  Core::PathBuffer<std::string > mSettingsDir;
  std::string mPlayerSessionID;
  std::string mAppSessionID;
  bool mShouldHaveAchievementsEnabled;
  bool mAchievementsAlwaysEnabled;
  Bedrock::PubSub::ScopedSubscription mAchivementsAlwaysOptionSubscription;
  bool mIsHost;
  long double mLastScreenTimestamp;
  bool mFlagPlayerGameTypeDefault;
  bool mFlagDeepLink;
  int mNumTimesDeviceLost;
  std::unordered_map<unsigned int,double> mPlayerLastDamagedTimestamp;
  ServiceRegistrationToken<IMinecraftEventing> mServiceRegistrationToken;
};

```

### `MinecraftEventing_vtbl`
```
struct /*VFT*/ MinecraftEventing_vtbl
{
  void (__fastcall *~IPackTelemetry)(IPackTelemetry *this);
  void (__fastcall *fireEventPackUpgradeAttempt)(IPackTelemetry *this, const PackManifest *, const PackReport *);
  void (__fastcall *init)(IMinecraftEventing *this, const gsl::not_null<Bedrock::NonOwnerPointer<Social::IUserManager> > *);
  void (__fastcall *shutdown)(IMinecraftEventing *this);
  const std::string *(__fastcall *getPlayerSessionId)(IMinecraftEventing *this);
  bool (__fastcall *getShouldHaveAchievementsEnabled)(IMinecraftEventing *this);
  void (__fastcall *setShouldHaveAchievementsEnabled)(IMinecraftEventing *this, bool);
  bool (__fastcall *getAchievementsAlwaysEnabled)(IMinecraftEventing *this);
  unsigned int (__fastcall *getPrimaryLocalUserId)(IMinecraftEventing *this);
  void (__fastcall *forceSendEvents)(IMinecraftEventing *this);
  Social::Events::EventManager *(__fastcall *getEventManager)(IMinecraftEventing *this);
  void (__fastcall *updatePrimaryLocalUserId)(IMinecraftEventing *this, const unsigned int *);
  void (__fastcall *updateIsLegacyPlayer)(IMinecraftEventing *this, bool);
  void (__fastcall *updateIsTrial)(IMinecraftEventing *this, bool);
  void (__fastcall *registerOptionsObserver)(IMinecraftEventing *this, std::shared_ptr<Options>);
  void (__fastcall *addListener)(IMinecraftEventing *this, std::unique_ptr<Social::Events::IEventListener>);
  void (__fastcall *fireEventOnSuccessfulClientLogin)(IMinecraftEventing *this, const Level *);
  void (__fastcall *clearListeners)(IMinecraftEventing *this);
  void (__fastcall *fireEventStartClient)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, bool);
  void (__fastcall *fireEventStartWorld)(IMinecraftEventing *this, IMinecraftEventing::NetworkType, const std::string *, const Social::MultiplayerServiceIdentifier);
  void (__fastcall *fireGlobalResourcePackCrashRecovery)(IMinecraftEventing *this, PackInstance *, mce::UUID, int);
  void (__fastcall *fireServerConnectionEvent)(IMinecraftEventing *this, IMinecraftEventing::ServerConnectionOutcome, unsigned int, long double, const std::string *);
  void (__fastcall *fireServerConnectionAttemptEvent)(IMinecraftEventing *this, const std::string *, bool, const std::string *);
  void (__fastcall *fireTextToSpeechToggled)(IMinecraftEventing *this, bool, bool);
  void (__fastcall *fireEventClientIdCreated)(IMinecraftEventing *this, int);
  void (__fastcall *fireEventFloatPropertyList)(IMinecraftEventing *this, const std::string *, const std::vector<std::pair<std::string,float>> *);
  void (__fastcall *fireEventHardwareInfo)(IMinecraftEventing *this);
  void (__fastcall *fireEventDeviceLost)(IMinecraftEventing *this);
  void (__fastcall *fireEventOptionsUpdated)(IMinecraftEventing *this, Options *, InputMode, bool);
  void (__fastcall *fireEventChatSettingsUpdated)(IMinecraftEventing *this, const Player *, const std::vector<Social::Events::Property> *);
  void (__fastcall *fireEventPerformanceMetrics)(IMinecraftEventing *this, const ProfilerLiteTelemetry *, bool);
  void (__fastcall *fireEventPerformanceContext)(IMinecraftEventing *this, const PerfContextTrackerReport *);
  void (__fastcall *fireEventPlayerTravelled)(IMinecraftEventing *this, Player *, float);
  void (__fastcall *fireEventPromotionNotificationClicked)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventVideoPlayed)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventRespondedToAcceptContent)(IMinecraftEventing *this, const ResourcePacksInfoData *, bool);
  void (__fastcall *fireEventSignInToIdentity)(IMinecraftEventing *this, IMinecraftEventing::SignInAccountType, IMinecraftEventing::SignInTrigger, bool, IMinecraftEventing::SignInStage, Social::SignInResult, const std::string *, const std::string *);
  void (__fastcall *fireEventSignOutOfIdentity)(IMinecraftEventing *this, IMinecraftEventing::SignInAccountType, IMinecraftEventing::SignInTrigger, const std::string *, const std::string *);
  void (__fastcall *fireEventSignOutOfXboxLive)(IMinecraftEventing *this, const Social::XboxLiveUser *);
  void (__fastcall *fireEventAppSuspended)(IMinecraftEventing *this, bool);
  void (__fastcall *fireEventAppPaused)(IMinecraftEventing *this);
  void (__fastcall *fireEventAppUnpaused)(IMinecraftEventing *this);
  void (__fastcall *fireEventAppResumed)(IMinecraftEventing *this);
  void (__fastcall *fireEventSplitScreenUpdated)(IMinecraftEventing *this, const IClientInstance *);
  void (__fastcall *fireEventPopupClosed)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventGameplayTipShown)(IMinecraftEventing *this, int, bool, const std::string *);
  void (__fastcall *fireEventWorldImported)(IMinecraftEventing *this, __int64, unsigned __int64);
  void (__fastcall *fireCurrentInputUpdated)(IMinecraftEventing *this, const IClientInstance *);
  void (__fastcall *fireEventTreatmentPackApplied)(IMinecraftEventing *this, const PackManifest *);
  void (__fastcall *fireEventPackPlayed)(IMinecraftEventing *this, const PackInstance *, unsigned int);
  void (__fastcall *fireEventPackHashChanged)(IMinecraftEventing *this, const PackManifest *);
  void (__fastcall *fireEventTreatmentPackDownloaded)(IMinecraftEventing *this, std::string);
  void (__fastcall *fireEventTreatmentPackRemoved)(IMinecraftEventing *this, std::string);
  void (__fastcall *fireEventContentLogsInWorldSession)(IMinecraftEventing *this, const std::string *, unsigned int, unsigned int);
  void (__fastcall *fireEventPackStorageWrite)(IMinecraftEventing *this, const PackStorageMetrics *);
  void (__fastcall *fireRealmConnectionEventStart)(IMinecraftEventing *this, IMinecraftEventing::RealmConnectionFlow);
  void (__fastcall *fireRealmConnectionEventGenericLambdaCalled)(IMinecraftEventing *this, IMinecraftEventing::RealmConnectionFlow, IMinecraftEventing::RealmConnectionLambda, IMinecraftEventing::RealmConnectionResult);
  void (__fastcall *fireEventCompoundCreatorCreated)(IMinecraftEventing *this, int, int);
  void (__fastcall *fireEventElementConstructorUsed)(IMinecraftEventing *this, int, int, IMinecraftEventing::ElementConstructorUseType);
  void (__fastcall *fireEventEntitySpawned)(IMinecraftEventing *this, Player *, int, unsigned int);
  void (__fastcall *fireEventReducerBlockEntered)(IMinecraftEventing *this, const ItemDescriptor *);
  void (__fastcall *fireEventRespawn)(IMinecraftEventing *this, Player *, int);
  void (__fastcall *fireEventServerRespawnSearchTime)(IMinecraftEventing *this, Player *, const PlayerRespawnTelemetryData *);
  void (__fastcall *firePackSettingsEvent)(IMinecraftEventing *this, const PackSettings *, const PackManifest *);
  void (__fastcall *removeTestRunIdTag)(IMinecraftEventing *this);
  void (__fastcall *removeTestTelemetryTag)(IMinecraftEventing *this);
  void (__fastcall *setTestRunIdTag)(IMinecraftEventing *this, const char *);
  void (__fastcall *setTestTelemetryTag)(IMinecraftEventing *this, const char *);
  void (__fastcall *stopDebugEventLoggingForAllListeners)(IMinecraftEventing *this);
  void (__fastcall *tick)(IMinecraftEventing *this);
  void (__fastcall *updateEditionType)(IMinecraftEventing *this);
  void (__fastcall *fireEventMultiplayerConnectionStateChanged)(IMinecraftEventing *this, bool, const std::string *, const std::string *, unsigned int, unsigned int, unsigned int, const std::string *);
  void (__fastcall *fireEventPacketViolationDetected)(IMinecraftEventing *this, const ExtendedStreamReadResult *, PacketViolationResponse, MinecraftPacketIds, const NetworkIdentifier *);
  void (__fastcall *fireEventJoinCanceled)(IMinecraftEventing *this, LoadingState);
  void (__fastcall *fireClubsEngagementEvent)(IMinecraftEventing *this, IMinecraftEventing::ClubsEngagementAction, IMinecraftEventing::ClubsEngagementTargetType, const char *, const Realms::RealmId, const std::string);
  void (__fastcall *fireClubsOpenFeedScreenEvent)(IMinecraftEventing *this, const IMinecraftEventing::ClubsFeedScreenSource, const Realms::RealmId, const std::string);
  void (__fastcall *fireEventEntitlementListInfo)(IMinecraftEventing *this, std::vector<ContentIdentity> *, bool);
  void (__fastcall *fireEventIncognitoFailure)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventStorage)(IMinecraftEventing *this, int, const std::string *);
  void (__fastcall *fireEventIAPPurchaseAttempt)(IMinecraftEventing *this, const std::string *, const std::string *, Offer *, PurchasePath);
  void (__fastcall *fireEventIAPPurchaseResolved)(IMinecraftEventing *this, const std::string *, const std::string *, Offer *, IMinecraftEventing::PurchaseResult, PurchasePath);
  void (__fastcall *fireEventIAPRedeemAttempt)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, PurchasePath);
  void (__fastcall *fireEventIAPRedeemResolved)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::PurchaseResult, PurchasePath);
  void (__fastcall *fireEventPurchaseAttempt)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::StoreType, PurchasePath);
  void (__fastcall *fireEventPurchaseResolved)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::StoreType, IMinecraftEventing::PurchaseResult, PurchasePath);
  void (__fastcall *fireEventIAPPurchaseFailure)(IMinecraftEventing *this, const std::string *, unsigned __int16, const std::string *, const PurchaseInfo *);
  void (__fastcall *fireEventPurchaseFailureDetails)(IMinecraftEventing *this, int, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventTreatmentsCleared)(IMinecraftEventing *this);
  void (__fastcall *fireEventTreatmentsSet)(IMinecraftEventing *this, const std::vector<std::string> *);
  void (__fastcall *fireEventProgressionsSet)(IMinecraftEventing *this, const std::vector<std::string> *);
  void (__fastcall *fireEventSetMultiplayerCorrelationId)(IMinecraftEventing *this, Player *, const std::string *);
  void (__fastcall *fireEventGameSessionStart)(IMinecraftEventing *this, Player *, IClientInstance *, Level *, const std::string *, int, const std::string *, const std::string *, bool);
  void (__fastcall *prepEventSearchCatalogRequest)(IMinecraftEventing *this, const SearchRequestTelemetry *);
  void (__fastcall *fireEventSearchCatalogRequest)(IMinecraftEventing *this, const SearchRequestTelemetry *);
  void (__fastcall *fireEventArmorStandItemEquipped)(IMinecraftEventing *this, const ArmorStand *, const ItemDescriptor *);
  void (__fastcall *fireEventArmorStandPosed)(IMinecraftEventing *this, const ArmorStand *);
  void (__fastcall *fireEventLockedItemGiven)(IMinecraftEventing *this);
  void (__fastcall *fireEventPlayerBounced)(IMinecraftEventing *this, Player *, const Block *, int);
  void (__fastcall *fireEventSetValidForAchievements)(IMinecraftEventing *this, Player *, bool);
  void (__fastcall *fireEventAchievementReceived)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventWorldLoaded)(IMinecraftEventing *this, Player *, Level *, ResourcePackManager *, ResourcePacksInfoData *, bool);
  void (__fastcall *fireMinecraftVersionLaunched)(IMinecraftEventing *this, bool);
  void (__fastcall *fireMinecraftVersionInviteAccepted)(IMinecraftEventing *this, bool, unsigned __int64);
  void (__fastcall *fireDayOneExperienceStateChanged)(IMinecraftEventing *this, IMinecraftEventing::DayOneExperienceState, std::optional<unsigned int>, std::optional<unsigned __int64>);
  void (__fastcall *fireWorldConversionAttemptEvent)(IMinecraftEventing *this, const Legacy::WorldConversionReport *);
  void (__fastcall *fireWorldConversionInitiatedEvent)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireLegacyWorldUploadEvent)(IMinecraftEventing *this, const Legacy::WorldConversionReport *, bool, WorldConversionError);
  void (__fastcall *fireEventAssertFailed)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventSessionCrashed)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventCrashSystemFailedToInit)(IMinecraftEventing *this);
  void (__fastcall *fireChatUsedEvent)(IMinecraftEventing *this, unsigned int, bool);
  void (__fastcall *fireEventJoinByCode)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventBlockPlacedByCommand)(IMinecraftEventing *this, const Block *, int);
  void (__fastcall *fireEventDwellerDied)(IMinecraftEventing *this, Actor *, const ActorDamageSource *, bool);
  void (__fastcall *fireEventDwellerRemoved)(IMinecraftEventing *this, Actor *, bool);
  void (__fastcall *fireEventScriptLoaded)(IMinecraftEventing *this, const std::string *, unsigned __int64);
  void (__fastcall *fireEventScriptRan)(IMinecraftEventing *this, const std::string *, unsigned __int64, bool, bool);
  void (__fastcall *fireEventDevConsoleOpen)(IMinecraftEventing *this);
  void (__fastcall *fireEventDevConsoleCommand)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventNpcPropertiesUpdated)(IMinecraftEventing *this, Actor *, bool);
  void (__fastcall *fireEventBoardTextUpdated)(IMinecraftEventing *this, ChalkboardBlockActor *);
  void (__fastcall *fireEventCameraUsed)(IMinecraftEventing *this, bool);
  void (__fastcall *fireEventPortfolioExported)(IMinecraftEventing *this, int, int);
  void (__fastcall *fireQuickPlayEvent)(IMinecraftEventing *this);
  void (__fastcall *firePermissionsSetEvent)(IMinecraftEventing *this, const PlayerPermissionLevel, const CommandPermissionLevel, const PlayerPermissionLevel, const CommandPermissionLevel);
  void (__fastcall *fireLibraryButtonPressed)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireCourseButtonPressed)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireLessonActionTaken)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, IMinecraftEventing::EducationLessonAction);
  void (__fastcall *fireInAppCodeBuilderActivated)(IMinecraftEventing *this, IMinecraftEventing::OpenCodeMethod);
  void (__fastcall *fireCodeCommandButtonPressed)(IMinecraftEventing *this);
  void (__fastcall *fireIDESelected)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventEduResources)(IMinecraftEventing *this);
  void (__fastcall *fireEventEduiOSPurchaseTransaction)(IMinecraftEventing *this, const TransactionStatus *);
  void (__fastcall *fireEventEduOptionSet)(IMinecraftEventing *this, const Option *);
  void (__fastcall *fireEventCodeBuilderClosed)(IMinecraftEventing *this);
  void (__fastcall *fireEventEduServiceStatus)(IMinecraftEventing *this, const std::string *, const std::string *, int, buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >);
  void (__fastcall *fireEventWebviewDownload)(IMinecraftEventing *this, const std::string *, const WebviewDownloadInfo *);
  void (__fastcall *fireEduServiceRequestFailed)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >);
  void (__fastcall *fireEventButtonPressed)(IMinecraftEventing *this, gsl::basic_string_span<char const ,-1>, buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >);
  void (__fastcall *fireEventLevelDataOverride)(IMinecraftEventing *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *fireEventEduContentVerificationFailed)(IMinecraftEventing *this);
  void (__fastcall *fireEventWorldExported)(IMinecraftEventing *this, __int64, unsigned __int64);
  void (__fastcall *fireEventControlRemappedByPlayer)(IMinecraftEventing *this, const std::string *, RawInputType, int);
  void (__fastcall *fireEventDifficultySet)(IMinecraftEventing *this, Difficulty, Difficulty);
  void (__fastcall *fireEventGameRulesUpdated)(IMinecraftEventing *this, float, float, const std::string *);
  void (__fastcall *fireEventGameRulesUpdated)(IMinecraftEventing *this, int, int, const std::string *);
  void (__fastcall *fireEventGameRulesUpdated)(IMinecraftEventing *this, bool, bool, const std::string *);
  void (__fastcall *fireEventDefaultGameTypeChanged)(IMinecraftEventing *this, GameType, GameType);
  void (__fastcall *fireEventConnectionFailed)(IMinecraftEventing *this, IMinecraftEventing::ConnectionFailureReason);
  void (__fastcall *fireEventOfferRated)(IMinecraftEventing *this, const std::string *, int, int, int, long double);
  void (__fastcall *fireEventNewContentCheckCompleted)(IMinecraftEventing *this, const std::string *, bool);
  void (__fastcall *fireEventHowToPlayTopicChanged)(IMinecraftEventing *this, const std::string *, InputMode);
  void (__fastcall *fireEventApiInit)(IMinecraftEventing *this, float, unsigned __int64);
  void (__fastcall *fireEventWorldFilesListed)(IMinecraftEventing *this, unsigned __int64, unsigned __int64, unsigned __int64, unsigned __int64);
  void (__fastcall *fireEventLabTableCreated)(IMinecraftEventing *this, int, int, int);
  void (__fastcall *fireEventPlayerMessageSay)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerMessageTell)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerMessageChat)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerMessageMe)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerMessageTitle)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerDamaged)(IMinecraftEventing *this, Player *, ActorDamageCause);
  void (__fastcall *fireEventPlayerKicked)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventPlayerBanned)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventRealmShared)(IMinecraftEventing *this, const std::string *, const IMinecraftEventing::ShareMode *, const Realms::RealmId *);
  void (__fastcall *fireEventRealmMemberlistCleared)(IMinecraftEventing *this, const Realms::RealmId *, const int *);
  void (__fastcall *fireEventRealmUrlGenerated)(IMinecraftEventing *this, const std::string *, const Realms::RealmId *);
  void (__fastcall *fireEventStructureExport)(IMinecraftEventing *this, const glTFExportData *, IMinecraftEventing::ExportOutcome, IMinecraftEventing::ExportStage);
  void (__fastcall *fireEventContentShared)(IMinecraftEventing *this, const std::string *, const std::string *, const IMinecraftEventing::ShareMode *);
  void (__fastcall *fireEventStorageReport)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventStackLoaded)(IMinecraftEventing *this, const StackStats *);
  void (__fastcall *fireEventUnknownBlockReceived)(IMinecraftEventing *this, const NewBlockID *, unsigned __int16);
  void (__fastcall *fireEventSignInEdu)(IMinecraftEventing *this, const std::string *, ADRole, IMinecraftEventing::EduSignInStage, const std::string *, const std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *fireEventPopupFiredEdu)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, const std::string *, const ActiveDirectoryAction);
  void (__fastcall *fireEventAppConfigurationChanged)(IMinecraftEventing *this);
  void (__fastcall *fireEventPurchaseGameAttempt)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventTrialDeviceIdCorrelation)(IMinecraftEventing *this, __int64, const std::string *, __int64, const std::string *);
  void (__fastcall *fireEventPushNotificationPermission)(IMinecraftEventing *this, bool, const std::string *);
  void (__fastcall *fireEventPushNotificationReceived)(IMinecraftEventing *this, const PushNotificationMessage *);
  void (__fastcall *fireEventPushNotificationOpened)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventUploadSkin)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *firePerfTestEvent)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, const std::vector<std::pair<std::string,float>> *);
  void (__fastcall *fireEventLicenseCheck)(IMinecraftEventing *this, bool, ExtraLicenseData *);
  void (__fastcall *fireQueryOfferResult)(IMinecraftEventing *this, const std::string *, int, bool);
  void (__fastcall *fireEventStorePromotionNotification)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventWorldGenerated)(IMinecraftEventing *this, const std::string *, const LevelSettings *, bool);
  void (__fastcall *fireEventCopyWorldEducationEnabled)(IMinecraftEventing *this);
  void (__fastcall *fireEventStoreOfferClicked)(IMinecraftEventing *this, int, int, int, int, int, int, const std::string *, const std::string *, bool, const std::string *);
  void (__fastcall *fireEventStoreSearch)(IMinecraftEventing *this, const StoreSearchTelemetryData *);
  void (__fastcall *fireEventSearchItemSelected)(IMinecraftEventing *this, const int, const int, const std::string *, const int, const int);
  void (__fastcall *fireEventUgcDownloadStarted)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventUgcDownloadCompleted)(IMinecraftEventing *this, const std::string *, bool);
  void (__fastcall *fireRealmConnectionEventRealmAPIRequest)(IMinecraftEventing *this, IMinecraftEventing::RealmConnectionFlow);
  void (__fastcall *fireRealmConnectionEventRealmAPIResponse)(IMinecraftEventing *this, IMinecraftEventing::RealmConnectionFlow, int);
  std::string *(__fastcall *getSessionId)(IMinecraftEventing *this, std::string *result);
  void (__fastcall *fireEventChunkLoaded)(IMinecraftEventing *this, LevelChunk *);
  void (__fastcall *fireEventChunkUnloaded)(IMinecraftEventing *this, LevelChunk *);
  void (__fastcall *fireEventChunkChanged)(IMinecraftEventing *this, LevelChunk *);
  void (__fastcall *fireEventMultiplayerSessionUpdate)(IMinecraftEventing *this, gsl::not_null<Level const *>, const Player *);
  void (__fastcall *fireEventLevelDestruct)(IMinecraftEventing *this);
  void (__fastcall *flagEventDeepLink)(IMinecraftEventing *this);
  void (__fastcall *flagEventPlayerGameTypeDefault)(IMinecraftEventing *this, bool);
  void (__fastcall *fileEventCloudWorldPullFailed)(IMinecraftEventing *this, const std::string *, const std::string *, bool);
  void (__fastcall *fireEventLevelDatLoadFailed)(IMinecraftEventing *this, const std::string *, const std::string *, bool);
  void (__fastcall *fireEventWorldCorruptionCausedWorldShutdown)(IMinecraftEventing *this, const std::string *, const std::string *);
  void (__fastcall *fireEventClientLeftGameDueToUnrecoverableError)(IMinecraftEventing *this, const std::string *, bool);
  void (__fastcall *fireEventServerShutdownDueToError)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventPersonaItemPreviewed)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *, unsigned int, unsigned int, IMinecraftEventing::PromotionType, bool, const std::string *, const std::string *, long double, IMinecraftEventing::StoreType);
  void (__fastcall *fireEventPersonaSkinChanged)(IMinecraftEventing *this, const std::string *, const std::string *, bool);
  void (__fastcall *fireEventPersonaAvatarUpdated)(IMinecraftEventing *this, const std::string *, const std::vector<std::string> *, const std::vector<bool> *, const std::vector<bool> *, bool, bool, const std::string *, const std::string *, const std::string *, bool, const std::vector<std::string> *, const std::vector<std::string> *);
  void (__fastcall *fireEventPersonaAvatarsListed)(IMinecraftEventing *this, const std::vector<std::string> *);
  void (__fastcall *fireEventPersonaEmotePlayed)(IMinecraftEventing *this, const std::string *, bool, int);
  void (__fastcall *fireEventPersonaInitalizationEvent)(IMinecraftEventing *this, unsigned int, const std::string *, const std::string *);
  void (__fastcall *fireEventPersonaGeneralError)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventPersonaLoadingPieces)(IMinecraftEventing *this, unsigned int, long double);
  void (__fastcall *fireEventPersonaStillLoading)(IMinecraftEventing *this, bool, bool, bool, bool, bool, bool, bool, bool);
  void (__fastcall *fireEventPersonaCreationFailed)(IMinecraftEventing *this, const std::string *, const std::string *, bool, bool, const std::string *, const std::string *);
  void (__fastcall *fireEventPersonaXForgeResponses)(IMinecraftEventing *this, const std::vector<std::string> *, int);
  void (__fastcall *fireEventPersonaCategoryInformation)(IMinecraftEventing *this, const std::string *);
  void (__fastcall *fireEventWorldHistoryPackSourceMissingDuringUpgrade)(IMinecraftEventing *this, const std::string *, const std::string *, const std::string *);
  void (__fastcall *fireEventFixedMarketplaceWorldUsingV2VillagersToUseV1)(IMinecraftEventing *this);
  void (__fastcall *fireEventAccountTransferStateChanged)(IMinecraftEventing *this, const std::string *, TransferState, const std::string *);
  void (__fastcall *fireStructureBlockAction)(IMinecraftEventing *this, IMinecraftEventing::StructureBlockActionType, const StructureEditorData *, const StructureTelemetryClientData *);
  void (__fastcall *fireStructureBlockRedstoneActivated)(IMinecraftEventing *this, IMinecraftEventing::StructureBlockActionType, const StructureEditorData *, const StructureTelemetryClientData *);
  void (__fastcall *fireEventHummingbirdError)(IMinecraftEventing *this, const unsigned int *, const std::string *);
  void (__fastcall *fireEventScreenLoaded)(IMinecraftEventing *this, const unsigned int *, const std::string *, long double, long double, long double);
  void (__fastcall *fireLevelChunkChecksumMismatchEvent)(IMinecraftEventing *this);
  void (__fastcall *fireEventVRModeChanged)(IMinecraftEventing *this, const bool);
  void (__fastcall *fireEventDeviceAccountSuccess)(IMinecraftEventing *this, bool, const std::string *);
  void (__fastcall *fireEventDeviceAccountFailure)(IMinecraftEventing *this, IMinecraftEventing::SignInStage, IMinecraftEventing::DeviceAccountFailurePhase, unsigned int, const std::string *);
  void (__fastcall *fireEventStoreConfigRetrieved)(IMinecraftEventing *this, const std::string *, int);
};

```

### `mce::ResourcePointerHelper<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > >`
```
struct __cppobj mce::ResourcePointerHelper<std::shared_ptr<mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription> > >
{
};

```

### `MinecraftScreenController_vtbl`
```
struct /*VFT*/ MinecraftScreenController_vtbl
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

