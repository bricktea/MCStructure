# B
### `BoolOption`
Offset | Type | Name
-|-|-|-
0 | (488) `Option` | baseclass_0
488 | (1) `bool` | mValue
489 | (1) `bool` | mDefaultValue
496 | (64) `std::function<bool __cdecl(bool)>` | mCoerceValueCallback


### `Bedrock::PubSub::Publisher<void __cdecl(Option const &),Bedrock::PubSub::ThreadModel::MultiThreaded,void>`
Offset | Type | Name
-|-|-|-
0 | (120) `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>` | baseclass_0


### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::list<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody>>` | mSubscriptions
16 | (80) `std::mutex` | mMutex
96 | (16) `std::weak_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody>` | mSingleSubscriber
112 | (8) `std::atomic<unsigned __int64>` | mSubscriberCount


### `Bedrock::PubSub::Publisher<void __cdecl(Option const &,enum InputMode),Bedrock::PubSub::ThreadModel::MultiThreaded,void>`
Offset | Type | Name
-|-|-|-
0 | (120) `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>` | baseclass_0


### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::list<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody>>` | mSubscriptions
16 | (80) `std::mutex` | mMutex
96 | (16) `std::weak_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody>` | mSingleSubscriber
112 | (8) `std::atomic<unsigned __int64>` | mSubscriberCount


### `Bedrock::PubSub::ScopedSubscription`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::PubSub::Subscription` | baseclass_0


### `Bedrock::PubSub::Subscription`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface>` | mBody


### `Brightness`
Offset | Type | Name
-|-|-|-
0 | (1) `NewType<unsigned char>` | baseclass_0


### `BlockPos`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (4) `int` | z


### `BaseGameVersion`
Offset | Type | Name
-|-|-|-
0 | (112) `SemVersion` | mSemVersion


### `Bedrock::Threading::OSThreadPriority`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mPriority


### `Bedrock::EnableNonOwnerReferences`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::Application::ThreadOwner<Core::Random>`
Offset | Type | Name
-|-|-|-
0 | (2516) `Core::Random` | mObject


### `BidirectionalUnorderedMap<std::basic_string<char,std::char_traits<char>,std::allocator<char> >,enum ActorDamageCause>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,enum ActorDamageCause>` | mRight
64 | (64) `std::unordered_map<enum ActorDamageCause,std::string>` | mLeft


### `BucketableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0


### `BoneAnimationChannel::sortKeyFrames::__l2::KeyFrameCompare`
Offset | Type | Name
-|-|-|-


### `BoneOrientation`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mUseMatrixFromOwningActor
4 | (4) `int` | mParentBoneIndex
8 | (4) `_BYTE[4]` | mParentSkeletalHierarchyIndex
16 | (48) `HashedString` | mName
64 | (48) `HashedString` | mParentName
112 | (64) `Matrix` | mLocalPreTransformMatrix
176 | (64) `Matrix` | mMatrix
240 | (4) `_BYTE[4]` | mRotationRelativeMode
244 | (36) `BoneOrientationTransform` | mTransform
280 | (36) `BoneOrientationTransform` | mDefaultTransform
316 | (12) `Vec3` | mPivot
328 | (1) `bool` | mOverrideStackMatrix
329 | (1) `bool` | mApplyLocalPreTransformMatrix


### `BoneOrientationTransform`
Offset | Type | Name
-|-|-|-
0 | (36) `Vec3[3]` | mData


### `BlockSerializationUtils::NbtToBlockCache`
Offset | Type | Name
-|-|-|-
0 | (16) `std::map<unsigned __int64,Block const *>` | mCache
16 | (80) `std::mutex` | mMutex


### `BlockSource::fetchBlocksInCylinderSorted::__l2::<lambda_162be0394a410a4558b7b369e9c9236e>`
Offset | Type | Name
-|-|-|-


### `Bedrock::Detail::DataStoreInfo`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<Core::PathBuffer<std::string > __cdecl(gsl::not_null<AppPlatform *>)>` | mFilePathFn


### `bgfx::TopLevelInstanceDesc`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::AccelerationStructureHandle` | bottomLevelAS
4 | (4) `bgfx::RtObjectCategory` | objectCategory
8 | (4) `bgfx::RtMediaType` | mediaType
12 | (4) `unsigned int` | hitGroupIdx
16 | (4) `unsigned int` | mask
20 | (6) `bgfx::TextureHandle[3]` | hTextures
28 | (8) `unsigned int[2]` | tintColours
36 | (2) `unsigned __int16` | materialFlags
38 | (1) `bool` | useIrradianceCache
40 | (48) `float[3][4]` | transform
88 | (8) `__int64` | uniqueId


### `bgfx::AccelerationStructureHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::TextureHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::RayTracingConfiguration`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mRtxOn
4 | (16) `bgfx::DLSSOptions` | mDLSSOptions
20 | (4) `float` | mEmissiveBrightnessMultiplier
24 | (4) `float` | mEmissiveDesaturation
28 | (4) `float` | mIndirectEmissiveBoostMultiplier
32 | (4) `float` | mSurfaceWetness
36 | (4) `unsigned int` | mIrradianceCacheMaxHistoryLength
40 | (4) `float` | mRayCountMultiplier
44 | (4) `unsigned int` | mDoubleBufferWriteIdx
48 | (8) `float[2]` | mSubPixelJitterOffset
56 | (8) `float[2]` | mPreviousSubPixelJitterOffset
64 | (1) `bool` | mCameraIsUnderWater
65 | (1) `bool` | mCameraIsUnderLava
68 | (4) `unsigned int` | mDimensionIdx
72 | (12) `float[3]` | mFogAbsorbtion
84 | (12) `float[3]` | mFogScattering
96 | (12) `float[3]` | mWaterAbsorbtion
108 | (12) `float[3]` | mWaterScattering
120 | (12) `float[3]` | mCloudAbsorbtion
132 | (12) `float[3]` | mCloudScattering
144 | (12) `float[3]` | mDirectionToSun
156 | (4) `float` | mTweakableSunAzimuthRotation
160 | (4) `float` | mHeightMapPixelEdgeWidth
164 | (4) `float` | mHeightMapDepth
168 | (4) `float` | mHeightFogFalloffHeight
172 | (4) `float` | mHeightFogStart
176 | (4) `float` | mFogHenyeyGreensteinG
180 | (4) `float` | mWaterHenyeyGreensteinG
184 | (4) `float` | mFogDensityMultiplier
188 | (1) `bool` | mInjectGlobalIlluminationIntoFog
192 | (4) `float` | mFogStart
196 | (4) `float` | mFogEnd
200 | (4) `float` | mRenderDistance
204 | (4) `float` | mWeatherFogLevel
208 | (4) `float` | mRainLevel
212 | (2) `bgfx::TextureHandle` | mSkyTexture
216 | (16) `float[4]` | mSkyColor
232 | (8) `float[2]` | mSkyUVScale
240 | (12) `float[3]` | mFinalCombineSkyColourOverride
252 | (4) `float` | mFinalCombineSkyColourOverrideStrength
256 | (12) `float[3]` | mPreviousFrameWorldOrigin
268 | (12) `float[3]` | mWorldOrigin
280 | (1) `bool` | mNightVisionEnabled
284 | (4) `float` | mNightVisionScale
288 | (4) `float` | mExposureModifierEv
292 | (4) `float` | mAutoExposureTemporalFitlerAlpha
296 | (4) `float` | mAutoExposureMinEV
300 | (4) `float` | mAutoExposureMaxEV
304 | (4) `float` | mAutoExposureLobeDifferenceThreshold
308 | (4) `float` | mAutoExposureLobeMixingMin
312 | (4) `float` | mAutoExposureLobeMixingMax
316 | (4) `float` | mSkyBrightnessAdjustment
320 | (4) `float` | mMoonMeshIntensity
324 | (4) `float` | mSunMeshIntensity
328 | (4) `_BYTE[4]` | mDebugMode
332 | (4) `bgfx::RtRenderMethod` | mRenderMethod
336 | (4) `float` | mSmoothertron
340 | (1) `bool` | mEnableDenoising
341 | (1) `bool` | mEnableGlassOpacityHack
342 | (1) `bool` | mRequestRecompileShaders
343 | (1) `bool` | mEnableProfiling
344 | (1) `bool` | mEnableIrradianceCache
345 | (1) `bool` | mProbabilityBasedRaycasts
346 | (1) `bool` | mEnableTraceRayInline
347 | (1) `bool` | mEnableCausticsStabilizationInRefMode
348 | (1) `bool` | mEnableRayReordering
349 | (1) `bool` | mEnableSHDiffuse
350 | (1) `bool` | mEnableWFTest
351 | (1) `bool` | mVisualizeLights
352 | (1) `bool` | mEnableExplicitLightSampling
356 | (4) `float` | mExplicitLightsIntensityBias
360 | (4) `unsigned int` | mMaxLightCount
364 | (4) `_BYTE[4]` | mLevelCuller
368 | (4) `_BYTE[4]` | mFrustumCuller
372 | (4) `float` | mFocalDistance
376 | (4) `float` | mApertureSize
380 | (4) `float` | mApertureType
384 | (4) `float` | mDiffuseDespeckleFilterRelativeDifferenceEpsilon
388 | (4) `float` | mSpecularDespeckleFilterRelativeDifferenceEpsilon
392 | (4) `float` | mSVGFDiffuseAlpha
396 | (4) `float` | mSVGFDiffuseAlphaMoments
400 | (4) `float` | mSVGFDiffusePhiLuminance
404 | (4) `float` | mSVGFSpecularAlpha
408 | (4) `float` | mSVGFSpecularAlphaMoments
412 | (4) `float` | mSVGFSpecularPhiLuminance
416 | (4) `float` | mSVGFDiffusePhiNormal
420 | (4) `float` | mSVGFSpecularPhiNormal
424 | (4) `float` | mSVGFPhiDepth
428 | (4) `int` | mSVGFAtrousIterationCountDiffuse
432 | (4) `int` | mSVGFAtrousIterationCountSpecular
436 | (4) `int` | mSVGFDiffuseTemporalFeedbackIterationIdx
440 | (4) `int` | mSVGFSpecularTemporalFeedbackIterationIdx
444 | (1) `bool` | mSVGFEnableFireflyFilterDiffuse
445 | (1) `bool` | mSVGFEnableFireflyFilterSpecular
446 | (1) `bool` | mEnableAdaptiveDenoiser
448 | (8) `const bgfx::RtLightInfo *` | mPointLights
456 | (8) `unsigned __int64` | mPointLightsCount
464 | (8) `unsigned int *` | mLightDistanceHistogram
472 | (16) `std::shared_ptr<std::vector<bgfx::PBRTextureData> >` | mPBRTextureData
488 | (4) `float` | mToneMappingShadowContrast
492 | (4) `float` | mToneMappingShadowContrastEnd
496 | (4) `float` | mToneMappingCurveShift
500 | (4) `float` | mToneMappingDynamicRange
504 | (4) `float` | mToneMappingShadowMinSlope
508 | (4) `float` | mToneMappingMaxExposureIncrease
512 | (4) `float` | mToneMappingFilmicSaturationCorrection
516 | (1) `bool` | mPrioritizeVisibleChunksForIrradianceCache
520 | (16) `float[4]` | mGenericDebugSliders


### `bgfx::DLSSOptions`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::DLSSOptions::Mode` | mMode
4 | (4) `bgfx::DLSSOptions::Scaling` | mQuality
8 | (4) `float` | mSharpness
12 | (4) `float` | mMipmapBias


### `ButtonColors`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | pressed
16 | (16) `mce::Color` | released


### `BedrockLog::CategoryLogs`
Offset | Type | Name
-|-|-|-
0 | (504) `std::array<BedrockLog::CategoryLogFile,7>` | baseclass_0


### `BedrockLog::CategoryLogFile`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum BedrockLog::LogChannel,std::unique_ptr<BedrockLog::LogDetails>,std::enum_hash<enum BedrockLog::LogChannel>,std::equal_to<enum BedrockLog::LogChannel>,std::allocator<std::pair<enum BedrockLog::LogChannel const ,std::unique_ptr<BedrockLog::LogDetails> > > >` | mChannel
64 | (4) `std::bitset<3>` | mCombinedChannelMask
68 | (4) `int` | mMessageCount


### `Bedrock::Memory::InternalHeapAllocator`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Memory::IMemoryAllocator` | baseclass_0


### `Bedrock::Memory::IMemoryAllocator`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Memory::IMemoryAllocator_vtbl *` | __vftable


### `BackgroundTaskBase::PriorityComparer`
Offset | Type | Name
-|-|-|-


### `Bedrock::Threading::CustomTLS::TLSManager`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mNativeKey
8 | (16384) `Bedrock::Threading::CustomTLS::TLSManager::KeyInfo[1024]` | mKeyInfo
16392 | (8208) `Bedrock::Threading::LFFixedRingBuffer<unsigned __int64,1024>` | mFreeList
24600 | (4) `std::atomic<int>` | mFreeListSize
24604 | (1) `bool` | mInitialized


### `Bedrock::Threading::CustomTLS::TLSManager::KeyInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(void *)` | mDestructor
8 | (4) `unsigned int` | mVersionId


### `Bedrock::Threading::LFFixedRingBuffer<unsigned __int64,1024>`
Offset | Type | Name
-|-|-|-
0 | (8192) `unsigned __int64[1024]` | mItems
8192 | (8) `std::atomic<unsigned __int64>` | mReadPos
8200 | (8) `std::atomic<unsigned __int64>` | mWritePos


### `BackgroundTaskBase::PendingComparer`
Offset | Type | Name
-|-|-|-


### `Bedrock::JSONObject::NodeFunctionTable`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(bool *, const Bedrock::JSONObject::Node *)` | mBoolean
8 | (8) `void (__fastcall *)(unsigned int *, const Bedrock::JSONObject::Node *)` | mUInt32
16 | (8) `void (__fastcall *)(int *, const Bedrock::JSONObject::Node *)` | mSInt32
24 | (8) `void (__fastcall *)(unsigned __int64 *, const Bedrock::JSONObject::Node *)` | mUInt64
32 | (8) `void (__fastcall *)(__int64 *, const Bedrock::JSONObject::Node *)` | mSInt64
40 | (8) `void (__fastcall *)(float *, const Bedrock::JSONObject::Node *)` | mFloat
48 | (8) `void (__fastcall *)(long double *, const Bedrock::JSONObject::Node *)` | mDouble
56 | (8) `void (__fastcall *)(std::ostream *, const Bedrock::JSONObject::Node *)` | mStream
64 | (8) `void (__fastcall *)(std::ostream *, const Bedrock::JSONObject::Node *)` | mJSONStream
72 | (8) `void (__fastcall *)(const Bedrock::JSONObject::ArrayNode **, const Bedrock::JSONObject::Node *)` | mArray
80 | (8) `void (__fastcall *)(const Bedrock::JSONObject::ObjectNode **, const Bedrock::JSONObject::Node *)` | mObject
88 | (8) `bool (__fastcall *)(Bedrock::JSONObject::Node *, const Bedrock::JSONObject::ValueWrapper *)` | mAssignment
96 | (8) `bool (__fastcall *)(const Bedrock::JSONObject::Node *, const Bedrock::JSONObject::Node *)` | mCompareEqual


### `bdf_options_t_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | correct_metrics
4 | (4) `int` | keep_unencoded
8 | (4) `int` | keep_comments
12 | (4) `int` | font_spacing


### `bdf_property_t_`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (4) `int` | format
12 | (4) `int` | builtin
16 | (8) `union {char *atom;int l;unsigned int ul;}` | value


### `bx::ErrorResult`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | code


### `bgfx::EmbeddedShader`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (264) `bgfx::EmbeddedShader::Data[11]` | data


### `bgfx::EmbeddedShader::Data`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::RendererType::Enum` | type
8 | (8) `const unsigned __int8 *` | data
16 | (4) `unsigned int` | size


### `bgfx::RendererCreator`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::RendererContextI *(__fastcall *)(const bgfx::Init *)` | createFn
8 | (8) `void (__fastcall *)()` | destroyFn
16 | (8) `const char *` | name
24 | (1) `bool` | supported


### `bgfx::CapsFlags`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_flag
8 | (8) `const char *` | m_str


### `bgfx::IndexBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::d3d11::UavFormat`
Offset | Type | Name
-|-|-|-
0 | (12) `DXGI_FORMAT[3]` | format
12 | (4) `unsigned int` | stride


### `bgfx::d3d11::PrimInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D_PRIMITIVE_TOPOLOGY` | m_type
4 | (4) `unsigned int` | m_min
8 | (4) `unsigned int` | m_div
12 | (4) `unsigned int` | m_sub


### `bgfx::d3d11::TextureFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `DXGI_FORMAT` | m_fmt
4 | (4) `DXGI_FORMAT` | m_fmtSrv
8 | (4) `DXGI_FORMAT` | m_fmtDsv
12 | (4) `DXGI_FORMAT` | m_fmtSrgb


### `bgfx::d3d11::IntelExtension`
Offset | Type | Name
-|-|-|-
0 | (16) `char[16]` | key
16 | (4) `unsigned int` | version
20 | (4) `unsigned int` | type
24 | (64) `unsigned int[16]` | data


### `bgfx::d3d11::Zero`
Offset | Type | Name
-|-|-|-
0 | (256) `ID3D11Buffer *[32]` | m_buffer
1 | (64) `ID3D11UnorderedAccessView *[8]` | m_uav
2 | (1024) `ID3D11ShaderResourceView *[128]` | m_srv
3 | (128) `ID3D11SamplerState *[16]` | m_sampler
4 | (1024) `ID3D11RenderTargetView *[128]` | m_rtv
5 | (128) `unsigned int[32]` | m_zero
6 | (128) `float[32]` | m_zerof


### `bgfx::ViewState`
Offset | Type | Name
-|-|-|-
0 | (32768) `bgfx::Matrix4[2][256]` | m_viewTmp
32768 | (32768) `bgfx::Matrix4[2][256]` | m_viewProj
65536 | (16) `bgfx::Matrix4 *[2]` | m_view
65552 | (8) `bgfx::Rect` | m_rect
65568 | (64) `bgfx::Matrix4` | m_invView
65632 | (64) `bgfx::Matrix4` | m_invProj
65696 | (64) `bgfx::Matrix4` | m_invViewProj
65760 | (4) `float` | m_alphaRef
65764 | (2) `unsigned __int16` | m_invViewCached
65766 | (2) `unsigned __int16` | m_invProjCached
65768 | (2) `unsigned __int16` | m_invViewProjCached


### `bgfx::Matrix4`
Offset | Type | Name
-|-|-|-
0 | (64) `bgfx::Matrix4::<unnamed_type_un>` | un


### `bgfx::Matrix4::<unnamed_type_un>`
Offset | Type | Name
-|-|-|-
0 | (64) `float[16]` | val
1 | (64) `bx::float4x4_t` | f4x4


### `bx::float4x4_t`
Offset | Type | Name
-|-|-|-
0 | (64) `__m128[4]` | col


### `bgfx::Rect`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | m_x
2 | (2) `unsigned __int16` | m_y
4 | (2) `unsigned __int16` | m_width
6 | (2) `unsigned __int16` | m_height


### `bgfx::d3d12::HeapProperty`
Offset | Type | Name
-|-|-|-
0 | (20) `D3D12_HEAP_PROPERTIES` | m_properties
20 | (4) `D3D12_RESOURCE_STATES` | m_state


### `bgfx::d3d12::UavFormat`
Offset | Type | Name
-|-|-|-
0 | (12) `DXGI_FORMAT[3]` | format
12 | (4) `unsigned int` | stride


### `bgfx::d3d12::PrimInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D_PRIMITIVE_TOPOLOGY` | m_topology
4 | (4) `D3D12_PRIMITIVE_TOPOLOGY_TYPE` | m_topologyType
8 | (4) `unsigned int` | m_min
12 | (4) `unsigned int` | m_div
16 | (4) `unsigned int` | m_sub


### `bgfx::d3d12::TextureFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `DXGI_FORMAT` | m_fmt
4 | (4) `DXGI_FORMAT` | m_fmtSrv
8 | (4) `DXGI_FORMAT` | m_fmtDsv
12 | (4) `DXGI_FORMAT` | m_fmtSrgb


### `bgfx::FrameBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::d3d12rtx::RendererContextD3D12RTX::runRayTracingShader::__l2::RayTracingShaderInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::d3d12rtx::RTRayGenShader` | mRayGenShader
4 | (4) `bgfx::d3d12rtx::RTComputeShader` | mComputeShader
8 | (4) `bgfx::d3d12rtx::RTDispatchSize` | mDispatchSize


### `bgfx::d3d9::Blend`
Offset | Type | Name
-|-|-|-
0 | (4) `_D3DBLEND` | m_src
4 | (4) `_D3DBLEND` | m_dst
8 | (1) `bool` | m_factor


### `bgfx::d3d9::Msaa`
Offset | Type | Name
-|-|-|-
0 | (4) `_D3DMULTISAMPLE_TYPE` | m_type
4 | (4) `unsigned int` | m_quality


### `bgfx::d3d9::ExtendedFormat`
Offset | Type | Name
-|-|-|-
0 | (4) `_D3DFORMAT` | m_fmt
4 | (4) `unsigned int` | m_usage
8 | (4) `_D3DRESOURCETYPE` | m_type
12 | (1) `bool` | m_supported


### `bgfx::d3d9::PrimInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `_D3DPRIMITIVETYPE` | m_type
4 | (4) `unsigned int` | m_min
8 | (4) `unsigned int` | m_div
12 | (4) `unsigned int` | m_sub


### `bgfx::d3d9::TextureFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `_D3DFORMAT` | m_fmt


### `bgfx::gl::Blend`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_src
4 | (4) `unsigned int` | m_dst
8 | (1) `bool` | m_factor


### `bgfx::gl::Extension`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | m_name
8 | (1) `bool` | m_supported
9 | (1) `bool` | m_initialize


### `bgfx::gl::PrimInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_type
4 | (4) `unsigned int` | m_min
8 | (4) `unsigned int` | m_div
12 | (4) `unsigned int` | m_sub


### `bgfx::gl::VendorId`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (2) `unsigned __int16` | id


### `bgfx::gl::TextureFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_internalFmt
4 | (4) `unsigned int` | m_internalFmtSrgb
8 | (4) `unsigned int` | m_fmt
12 | (4) `unsigned int` | m_type
16 | (1) `bool` | m_supported


### `bgfx::vk::Extension`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | m_name
8 | (4) `unsigned int` | m_minVersion
12 | (1) `bool` | m_instanceExt
13 | (1) `bool` | m_supported
14 | (1) `bool` | m_initialize


### `bgfx::vk::PrimInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkPrimitiveTopology` | m_topology
4 | (4) `unsigned int` | m_min
8 | (4) `unsigned int` | m_div
12 | (4) `unsigned int` | m_sub


### `bgfx::vk::TextureFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkFormat` | m_fmt
4 | (4) `VkFormat` | m_fmtSrv
8 | (4) `VkFormat` | m_fmtDsv
12 | (4) `VkFormat` | m_fmtSrgb


### `bgfx::Dx9bcOpcodeInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | numOperands
1 | (1) `unsigned __int8` | numValues


### `bgfx::DxbcOpcodeInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | numOperands
1 | (1) `unsigned __int8` | numValues


### `bgfx::SpvOpcodeInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | hasType
1 | (1) `bool` | hasResult
4 | (32) `bgfx::SpvOperand::Enum[8]` | operands


### `bgfx::SpvDecorationInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::SpvOperand::Enum[2]` | operands


### `bgfx::AttribToId`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::Attrib::Enum` | attr
4 | (2) `unsigned __int16` | id


### `bimg::TranslatePvr3Format`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_format
8 | (4) `unsigned int` | m_channelTypeMask
12 | (4) `_BYTE[4]` | m_textureFormat


### `bimg::TranslateDdsFormat`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_format
4 | (4) `_BYTE[4]` | m_textureFormat
8 | (1) `bool` | m_srgb


### `bimg::ImageBlockInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | bitsPerPixel
1 | (1) `unsigned __int8` | blockWidth
2 | (1) `unsigned __int8` | blockHeight
3 | (1) `unsigned __int8` | blockSize
4 | (1) `unsigned __int8` | minBlockX
5 | (1) `unsigned __int8` | minBlockY
6 | (1) `unsigned __int8` | depthBits
7 | (1) `unsigned __int8` | stencilBits
8 | (1) `unsigned __int8` | rBits
9 | (1) `unsigned __int8` | gBits
10 | (1) `unsigned __int8` | bBits
11 | (1) `unsigned __int8` | aBits
12 | (1) `unsigned __int8` | encoding


### `bimg::Bc7ModeInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | numSubsets
1 | (1) `unsigned __int8` | partitionBits
2 | (1) `unsigned __int8` | rotationBits
3 | (1) `unsigned __int8` | indexSelectionBits
4 | (1) `unsigned __int8` | colorBits
5 | (1) `unsigned __int8` | alphaBits
6 | (1) `unsigned __int8` | endpointPBits
7 | (1) `unsigned __int8` | sharedPBits
8 | (2) `unsigned __int8[2]` | indexBits


### `bimg::Bc6hModeInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | transformed
1 | (1) `unsigned __int8` | partitionBits
2 | (1) `unsigned __int8` | endpointBits
3 | (3) `unsigned __int8[3]` | deltaBits


### `bimg::KtxFormatInfo2`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_internalFmt
4 | (4) `_BYTE[4]` | m_format


### `bimg::KtxFormatInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_internalFmt
4 | (4) `unsigned int` | m_internalFmtSrgb
8 | (4) `unsigned int` | m_fmt
12 | (4) `unsigned int` | m_type


### `bimg::TranslateDdsPixelFormat`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_bitCount
4 | (4) `unsigned int` | m_flags
8 | (16) `unsigned int[4]` | m_bitmask
24 | (4) `_BYTE[4]` | m_textureFormat


### `bimg::PackUnpack`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(void *, const float *)` | pack
8 | (8) `void (__fastcall *)(float *, const void *)` | unpack


### `bimg::CubeMapFace::Neighbour`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | m_faceIdx
1 | (1) `unsigned __int8` | m_faceEdge


### `bimg::CubeMapFace`
Offset | Type | Name
-|-|-|-
0 | (36) `float[3][3]` | uv


### `Bedrock::NonOwnerPointer<mce::ShaderGroup>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BurnOdds`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mChance


### `Bedrock::NonOwnerPointer<AppConfigs>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Bedrock::IApplicationDataStores>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<int,AutomaticID<Dimension,int> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<int,AutomaticID<Dimension,int>>` | mRight
64 | (64) `std::unordered_map<AutomaticID<Dimension,int>,int,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,int> > >` | mLeft


### `Bedrock::NonOwnerPointer<cg::IGraphicsDeviceVendorProvider>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ProfilingManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum ComplexInventoryTransaction::Type,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ComplexInventoryTransaction::Type,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ComplexInventoryTransaction::Type>` | mLeft


### `BackwardsCompatTextureInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mUse
4 | (8) `glm::tvec2<float,0>` | mUVSize
12 | (8) `glm::tvec2<float,0>` | mUV
20 | (8) `glm::tvec2<float,0>` | mBaseSize
32 | (32) `Core::PathBuffer<std::string >` | mBackCompatTexture


### `Bedrock::NonOwnerPointer<cg::IGraphicsDevicePlatformProvider>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BehaviorTreeDefinitionPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `BehaviorTreeGroup *` | mGroup
8 | (8) `BehaviorTreeDefinition *` | mPtr


### `Bedrock::NonOwnerPointer<ServiceClientScheduler>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Social::MultiplayerServiceManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BeardKernel`
Offset | Type | Name
-|-|-|-
0 | (55296) `const std::array<float,13824>` | mKernel


### `Bedrock::NonOwnerPointer<IEntitlementManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum ItemUseInventoryTransaction::ActionType,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ItemUseInventoryTransaction::ActionType,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ItemUseInventoryTransaction::ActionType>` | mLeft


### `Bedrock::NonOwnerPointer<DateManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<std::basic_string<char,std::char_traits<char>,std::allocator<char> >,AutomaticID<Dimension,int> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,AutomaticID<Dimension,int>>` | mRight
64 | (64) `std::unordered_map<AutomaticID<Dimension,int>,std::string,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::string > > >` | mLeft


### `BidirectionalUnorderedMap<enum ItemAcquisitionMethod,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ItemAcquisitionMethod,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ItemAcquisitionMethod>` | mLeft


### `Bedrock::NonOwnerPointer<OfferRepository>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `bgfx::Caps`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::RendererType::Enum` | rendererType
4 | (32) `char[32]` | rendererVersion
40 | (8) `unsigned __int64` | rendererFeatureVersion
48 | (8) `unsigned __int64` | supported
56 | (2) `unsigned __int16` | vendorId
58 | (2) `unsigned __int16` | deviceId
60 | (4) `unsigned int` | subSysId
64 | (4) `unsigned int` | revision
72 | (8) `unsigned __int64` | dedicatedVideoMemory
80 | (8) `unsigned __int64` | dedicatedSystemMemory
88 | (8) `unsigned __int64` | sharedSystemMemory
96 | (8) `unsigned __int64` | reservedVideoMemory
104 | (512) `char[512]` | chipsetName
616 | (1) `bool` | homogeneousDepth
617 | (1) `bool` | originBottomLeft
618 | (1) `unsigned __int8` | numGPUs
620 | (4) `unsigned int` | displayWidth
624 | (4) `unsigned int` | displayHeight
632 | (2240) `bgfx::Caps::GPU[4]` | gpu
2872 | (96) `bgfx::Caps::Limits` | limits
2968 | (170) `unsigned __int16[85]` | formats


### `bgfx::Caps::GPU`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | vendorId
2 | (2) `unsigned __int16` | deviceId
4 | (4) `unsigned int` | subSysId
8 | (4) `unsigned int` | revision
16 | (8) `unsigned __int64` | dedicatedVideoMemory
24 | (8) `unsigned __int64` | dedicatedSystemMemory
32 | (8) `unsigned __int64` | sharedSystemMemory
40 | (8) `unsigned __int64` | reservedVideoMemory
48 | (512) `char[512]` | chipsetName


### `bgfx::Caps::Limits`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | maxDrawCalls
4 | (4) `unsigned int` | maxBlits
8 | (4) `unsigned int` | maxTextureSize
12 | (4) `unsigned int` | maxTextureLayers
16 | (4) `unsigned int` | maxViews
20 | (4) `unsigned int` | maxFrameBuffers
24 | (4) `unsigned int` | maxFBAttachments
28 | (4) `unsigned int` | maxPrograms
32 | (4) `unsigned int` | maxShaders
36 | (4) `unsigned int` | maxTextures
40 | (4) `unsigned int` | maxTextureSamplers
44 | (4) `unsigned int` | maxVertexDecls
48 | (4) `unsigned int` | maxVertexStreams
52 | (4) `unsigned int` | maxIndexBuffers
56 | (4) `unsigned int` | maxVertexBuffers
60 | (4) `unsigned int` | maxDynamicIndexBuffers
64 | (4) `unsigned int` | maxDynamicVertexBuffers
68 | (4) `unsigned int` | maxUniforms
72 | (4) `unsigned int` | maxOcclusionQueries
76 | (4) `unsigned int` | maxEncoders
80 | (4) `unsigned int` | transientVbSize
84 | (4) `unsigned int` | transientIbSize
88 | (4) `unsigned int` | maxAccelerationStructures
92 | (4) `unsigned int` | avgAccelerationStructureSize


### `Bedrock::NonOwnerPointer<Social::UserManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<mce::FileWatcherNull>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum ParticleType,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ParticleType,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ParticleType>` | mLeft


### `Bedrock::NonOwnerPointer<IMinecraftEventing>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ServerInstance>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<IApp>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<BasicTestProfileStats>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<GameRelightingTestData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Core::LoadTimeProfiler>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<NetworkDebugManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<IRayTracingOptions>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<std::basic_string<char,std::char_traits<char>,std::allocator<char> >,enum LevelSoundEvent>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,enum LevelSoundEvent>` | mRight
64 | (64) `std::unordered_map<enum LevelSoundEvent,std::string>` | mLeft


### `Bedrock::NonOwnerPointer<AppPlatform>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<std::basic_string<char,std::char_traits<char>,std::allocator<char> >,enum FilterSubject>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,enum FilterSubject>` | mRight
64 | (64) `std::unordered_map<enum FilterSubject,std::string>` | mLeft


### `bgfx::DREDData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | m_enableDRED
8 | (24) `std::vector<std::string>` | m_breadCrumbStrings
32 | (24) `std::vector<std::string>` | m_pageFaultFreedDataStrings
56 | (24) `std::vector<std::string>` | m_pageFaultExistingDataStrings


### `BidirectionalUnorderedMap<enum ItemUseMethod,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ItemUseMethod,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ItemUseMethod>` | mLeft


### `Bedrock::NonOwnerPointer<ChunkPerformanceData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ContentTierManager::ValidatorRegistry>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<mce::framebuilder::FrameBuilder>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum ItemStackNetResult,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ItemStackNetResult,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ItemStackNetResult>` | mLeft


### `Bedrock::NonOwnerPointer<GameStore>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<DataUtils::MiscData>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::Threading::InstancedThreadLocal<bool (__cdecl**)(AssertHandlerContext const &),std::allocator<bool (__cdecl**)(AssertHandlerContext const &)> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool (__cdecl** *)(AssertHandlerContext const &))>` | mConstructor
64 | (16) `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bool (__cdecl**)(AssertHandlerContext const &),std::allocator<bool (__cdecl**)(AssertHandlerContext const &)> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >` | mItems
80 | (80) `std::mutex` | mMutex
160 | (4) `unsigned int` | mKey
164 | (1) `bool` | mInitialized


### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bool (__cdecl**)(AssertHandlerContext const &),std::allocator<bool (__cdecl**)(AssertHandlerContext const &)> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::Intrusive::list_base_hook<void>` | mSentinel


### `Bedrock::Intrusive::list_base_hook<void>`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Intrusive::list_base_hook<void> *` | mNext
8 | (8) `Bedrock::Intrusive::list_base_hook<void> *` | mPrev


### `BedrockTextureData`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ClientTexture` | mClientTexture
16 | (112) `mce::TextureDescription` | mTextureDescription
128 | (1) `IsMissingTexture` | mIsMissingTexture
129 | (1) `TextureLoadState` | mTextureLoadState
136 | (24) `cg::TextureSetImageDescription` | mTextureSetDescription


### `bgfx::PlatformData`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ndt
8 | (8) `void *` | nwh
16 | (8) `void *` | context
24 | (8) `void *` | backBuffer
32 | (8) `void *` | backBufferDS
40 | (8) `void *` | session


### `BidirectionalUnorderedMap<enum InventoryTransactionError,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum InventoryTransactionError,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum InventoryTransactionError>` | mLeft


### `BidirectionalUnorderedMap<enum ItemStackRequestActionType,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ItemStackRequestActionType,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ItemStackRequestActionType>` | mLeft


### `Bedrock::NonOwnerPointer<FeatureToggles>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Bedrock::Threading::PendingConditionals>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BackwardsCompatTextureGroup`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<ResourceLocation,BackwardsCompatTextureInfo>` | mBackCompatMap


### `Bedrock::NonOwnerPointer<EducationOptions>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ResourceLoadManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum SparseContainer::PushSlotPredictionResult,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum SparseContainer::PushSlotPredictionResult,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum SparseContainer::PushSlotPredictionResult>` | mLeft


### `Bedrock::NonOwnerPointer<PackManifest::CapabilityRegistry>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ContentLog>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BidirectionalUnorderedMap<enum ContainerType,std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<enum ContainerType,std::string>` | mRight
64 | (64) `std::unordered_map<std::string,enum ContainerType>` | mLeft


### `bgfx::InternalData`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::Caps *` | caps
8 | (8) `void *` | context


### `Bedrock::Threading::Burst::Details::WorkerTaskStats<std::atomic<unsigned __int64> >`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<unsigned __int64>` | mTasksQueued
8 | (8) `std::atomic<unsigned __int64>` | mTasksCompleted


### `bgfx::vk::RendererContextVK`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::RendererContextI` | baseclass_0
8 | (8) `VkAllocationCallbacks *` | m_allocatorCb
16 | (8) `struct VkDebugReportCallbackEXT_T *` | m_debugReportCallback
24 | (8) `VkInstance_T *` | m_instance
32 | (8) `VkPhysicalDevice_T *` | m_physicalDevice
40 | (824) `VkPhysicalDeviceProperties` | m_deviceProperties
864 | (520) `VkPhysicalDeviceMemoryProperties` | m_memoryProperties
1384 | (220) `VkPhysicalDeviceFeatures` | m_deviceFeatures
1608 | (104) `VkSwapchainCreateInfoKHR` | m_sci
1712 | (8) `VkSurfaceKHR_T *` | m_surface
1720 | (8) `bgfx::vk::VkSwapchainKHR` | m_swapchain
1728 | (4) `unsigned int` | m_numSwapchainImages
1732 | (16) `VkImageLayout[4]` | m_backBufferColorImageLayout
1752 | (32) `bgfx::vk::VkImage[4]` | m_backBufferColorImage
1784 | (32) `bgfx::vk::VkImageView[4]` | m_backBufferColorImageView
1816 | (32) `bgfx::vk::VkFramebuffer[4]` | m_backBufferColor
1848 | (32) `VkCommandBuffer_T *[4]` | m_commandBuffers
1880 | (8) `VkCommandBuffer_T *` | m_commandBuffer
1888 | (1) `bool` | m_needToRefreshSwapchain
1892 | (4) `VkFormat` | m_backBufferDepthStencilFormat
1896 | (8) `VkDeviceMemory_T *` | m_backBufferDepthStencilMemory
1904 | (8) `bgfx::vk::VkImage` | m_backBufferDepthStencilImage
1912 | (8) `bgfx::vk::VkImageView` | m_backBufferDepthStencilImageView
1920 | (192) `bgfx::vk::ScratchBufferVK[4]` | m_scratchBuffer
2112 | (32) `bgfx::vk::VkSemaphore[4]` | m_presentDone
2144 | (4) `unsigned int` | m_qfiGraphics
2148 | (4) `unsigned int` | m_qfiCompute
2152 | (8) `VkDevice_T *` | m_device
2160 | (8) `VkQueue_T *` | m_queueGraphics
2168 | (8) `VkQueue_T *` | m_queueCompute
2176 | (8) `bgfx::vk::VkFence` | m_fence
2184 | (8) `bgfx::vk::VkRenderPass` | m_renderPass
2192 | (8) `bgfx::vk::VkDescriptorPool` | m_descriptorPool
2200 | (8) `bgfx::vk::VkPipelineCache` | m_pipelineCache
2208 | (8) `bgfx::vk::VkCommandPool` | m_commandPool
2216 | (8) `void *` | m_renderDocDll
2224 | (8) `void *` | m_vulkan1Dll
2232 | (98304) `bgfx::vk::BufferVK[4096]` | m_indexBuffers
100536 | (131072) `bgfx::vk::VertexBufferVK[4096]` | m_vertexBuffers
231608 | (8159232) `bgfx::vk::ShaderVK[4096]` | m_shaders
8390840 | (458752) `bgfx::vk::ProgramVK[2048]` | m_program
8849592 | (425984) `bgfx::vk::TextureVK[4096]` | m_textures
9275576 | (5120) `bgfx::VertexDecl[64]` | m_vertexDecls
9280696 | (13312) `bgfx::vk::FrameBufferVK[128]` | m_frameBuffers
9294008 | (4096) `void *[512]` | m_uniforms
9298104 | (7176) `bgfx::UniformRegistry` | m_uniformReg
9305280 | (32) `bgfx::vk::StateCacheT<bgfx::vk::VkPipeline>` | m_pipelineStateCache
9305312 | (32) `bgfx::vk::StateCacheT<bgfx::vk::VkDescriptorSetLayout>` | m_descriptorSetLayoutCache
9305344 | (32) `bgfx::vk::StateCacheT<bgfx::vk::VkRenderPass>` | m_renderPassCache
9305376 | (32) `bgfx::vk::StateCacheT<bgfx::vk::VkSampler>` | m_samplerCache
9305408 | (12) `bgfx::Resolution` | m_resolution
9305420 | (4) `unsigned int` | m_maxAnisotropy
9305424 | (1) `bool` | m_depthClamp
9305425 | (1) `bool` | m_wireframe
9305432 | (24) `bgfx::TextVideoMem` | m_textVideoMem
9305456 | (65536) `unsigned __int8[65536]` | m_fsScratch
9370992 | (65536) `unsigned __int8[65536]` | m_vsScratch
9436528 | (4) `unsigned int` | m_fsChanges
9436532 | (4) `unsigned int` | m_vsChanges
9436536 | (4) `unsigned int` | m_backBufferColorIdx
9436540 | (2) `bgfx::FrameBufferHandle` | m_fbh


### `bgfx::RendererContextI`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::RendererContextI_vtbl *` | __vftable


### `bgfx::vk::VkSwapchainKHR`
Offset | Type | Name
-|-|-|-
0 | (8) `VkSwapchainKHR_T *` | vk


### `bgfx::vk::VkImage`
Offset | Type | Name
-|-|-|-
0 | (8) `VkImage_T *` | vk


### `bgfx::vk::VkImageView`
Offset | Type | Name
-|-|-|-
0 | (8) `VkImageView_T *` | vk


### `bgfx::vk::VkFramebuffer`
Offset | Type | Name
-|-|-|-
0 | (8) `VkFramebuffer_T *` | vk


### `bgfx::vk::ScratchBufferVK`
Offset | Type | Name
-|-|-|-
0 | (8) `VkDescriptorSet_T **` | m_descriptorSet
8 | (8) `bgfx::vk::VkBuffer` | m_buffer
16 | (8) `VkDeviceMemory_T *` | m_deviceMem
24 | (8) `unsigned __int8 *` | m_data
32 | (4) `unsigned int` | m_size
36 | (4) `unsigned int` | m_pos
40 | (4) `unsigned int` | m_currentDs
44 | (4) `unsigned int` | m_maxDescriptors


### `bgfx::vk::VkBuffer`
Offset | Type | Name
-|-|-|-
0 | (8) `VkBuffer_T *` | vk


### `bgfx::vk::VkSemaphore`
Offset | Type | Name
-|-|-|-
0 | (8) `VkSemaphore_T *` | vk


### `bgfx::vk::VkFence`
Offset | Type | Name
-|-|-|-
0 | (8) `VkFence_T *` | vk


### `bgfx::vk::VkRenderPass`
Offset | Type | Name
-|-|-|-
0 | (8) `VkRenderPass_T *` | vk


### `bgfx::vk::VkDescriptorPool`
Offset | Type | Name
-|-|-|-
0 | (8) `VkDescriptorPool_T *` | vk


### `bgfx::vk::VkPipelineCache`
Offset | Type | Name
-|-|-|-
0 | (8) `VkPipelineCache_T *` | vk


### `bgfx::vk::VkCommandPool`
Offset | Type | Name
-|-|-|-
0 | (8) `VkCommandPool_T *` | vk


### `bgfx::vk::BufferVK`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::vk::VkBuffer` | m_buffer
8 | (8) `VkDeviceMemory_T *` | m_deviceMem
16 | (4) `unsigned int` | m_size
20 | (2) `unsigned __int16` | m_flags
22 | (1) `bool` | m_dynamic


### `bgfx::vk::VertexBufferVK`
Offset | Type | Name
-|-|-|-
0 | (24) `bgfx::vk::BufferVK` | baseclass_0
24 | (2) `bgfx::VertexDeclHandle` | m_decl


### `bgfx::VertexDeclHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::vk::ShaderVK`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::Memory *` | m_code
8 | (8) `bgfx::vk::VkShaderModule` | m_module
16 | (8) `bgfx::UniformBuffer *` | m_constantBuffer
24 | (96) `bgfx::PredefinedUniform[12]` | m_predefined
120 | (36) `unsigned __int16[18]` | m_attrMask
156 | (18) `unsigned __int8[18]` | m_attrRemap
176 | (4) `unsigned int` | m_hash
180 | (2) `unsigned __int16` | m_numUniforms
182 | (2) `unsigned __int16` | m_size
184 | (1) `unsigned __int8` | m_numPredefined
185 | (1) `unsigned __int8` | m_numAttrs
188 | (1024) `bgfx::vk::ShaderVK::BindInfo[64]` | m_bindInfo
1212 | (4) `unsigned int` | m_uniformBinding
1216 | (2) `unsigned __int16` | m_numBindings
1224 | (768) `VkDescriptorSetLayoutBinding[32]` | m_bindings


### `bgfx::vk::VkShaderModule`
Offset | Type | Name
-|-|-|-
0 | (8) `VkShaderModule_T *` | vk


### `bgfx::PredefinedUniform`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_loc
4 | (2) `unsigned __int16` | m_count
6 | (1) `unsigned __int8` | m_type


### `bgfx::vk::ShaderVK::BindInfo`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::UniformHandle` | uniformHandle
4 | (4) `_BYTE[4]` | type
8 | (4) `unsigned int` | binding
12 | (4) `unsigned int` | samplerBinding


### `bgfx::UniformHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::vk::ProgramVK`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::vk::ShaderVK *` | m_vsh
8 | (8) `const bgfx::vk::ShaderVK *` | m_fsh
16 | (192) `bgfx::PredefinedUniform[24]` | m_predefined
208 | (1) `unsigned __int8` | m_numPredefined
212 | (4) `unsigned int` | m_descriptorSetLayoutHash
216 | (8) `bgfx::vk::VkPipelineLayout` | m_pipelineLayout


### `bgfx::vk::VkPipelineLayout`
Offset | Type | Name
-|-|-|-
0 | (8) `VkPipelineLayout_T *` | vk


### `bgfx::vk::TextureVK`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | m_directAccessPtr
8 | (8) `unsigned __int64` | m_flags
16 | (4) `unsigned int` | m_width
20 | (4) `unsigned int` | m_height
24 | (4) `unsigned int` | m_depth
28 | (4) `unsigned int` | m_numLayers
32 | (4) `unsigned int` | m_numSides
36 | (4) `VkImageViewType` | m_type
40 | (1) `unsigned __int8` | m_requestedFormat
41 | (1) `unsigned __int8` | m_textureFormat
42 | (1) `unsigned __int8` | m_numMips
44 | (4) `VkFormat` | m_vkTextureFormat
48 | (4) `unsigned int` | m_vkTextureAspect
56 | (8) `bgfx::vk::VkImage` | m_textureImage
64 | (8) `VkDeviceMemory_T *` | m_textureDeviceMem
72 | (8) `bgfx::vk::VkImageView` | m_textureImageView
80 | (8) `bgfx::vk::VkImageView` | m_textureImageDepthView
88 | (8) `bgfx::vk::VkImageView` | m_textureImageStorageView
96 | (4) `VkImageLayout` | m_currentImageLayout


### `bgfx::VertexDecl`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_hash
4 | (2) `unsigned __int16` | m_stride
6 | (36) `unsigned __int16[18]` | m_offset
42 | (36) `unsigned __int16[18]` | m_attributes


### `bgfx::vk::FrameBufferVK`
Offset | Type | Name
-|-|-|-
0 | (16) `bgfx::TextureHandle[8]` | m_texture
16 | (2) `bgfx::TextureHandle` | m_depth
20 | (4) `unsigned int` | m_width
24 | (4) `unsigned int` | m_height
28 | (2) `unsigned __int16` | m_denseIdx
30 | (1) `unsigned __int8` | m_num
31 | (1) `unsigned __int8` | m_numTh
32 | (1) `unsigned __int8` | m_numAttachment
34 | (48) `bgfx::Attachment[8]` | m_attachment
88 | (8) `bgfx::vk::VkFramebuffer` | m_framebuffer
96 | (8) `bgfx::vk::VkRenderPass` | m_renderPass


### `bgfx::Attachment`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::TextureHandle` | handle
2 | (2) `unsigned __int16` | mip
4 | (2) `unsigned __int16` | layer


### `bgfx::UniformRegistry`
Offset | Type | Name
-|-|-|-
0 | (6152) `bx::HandleHashMapT<1024,unsigned int>` | m_uniforms
6152 | (1024) `bgfx::UniformRegInfo[512]` | m_info


### `bx::HandleHashMapT<1024,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_maxCapacity
4 | (4) `unsigned int` | m_numElements
8 | (4096) `unsigned int[1024]` | m_key
4104 | (2048) `unsigned __int16[1024]` | m_handle


### `bgfx::UniformRegInfo`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::UniformHandle` | m_handle


### `bgfx::vk::StateCacheT<bgfx::vk::VkPipeline>`
Offset | Type | Name
-|-|-|-
0 | (32) `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkPipeline,bgfx::TinyStlAllocator>` | m_hashMap


### `bgfx::vk::StateCacheT<bgfx::vk::VkDescriptorSetLayout>`
Offset | Type | Name
-|-|-|-
0 | (32) `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkDescriptorSetLayout,bgfx::TinyStlAllocator>` | m_hashMap


### `bgfx::vk::StateCacheT<bgfx::vk::VkRenderPass>`
Offset | Type | Name
-|-|-|-
0 | (32) `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkRenderPass,bgfx::TinyStlAllocator>` | m_hashMap


### `bgfx::vk::StateCacheT<bgfx::vk::VkSampler>`
Offset | Type | Name
-|-|-|-
0 | (32) `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkSampler,bgfx::TinyStlAllocator>` | m_hashMap


### `bgfx::Resolution`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | width
4 | (4) `unsigned int` | height
8 | (4) `unsigned int` | reset


### `bgfx::TextVideoMem`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::TextVideoMem::MemSlot *` | m_mem
8 | (4) `unsigned int` | m_size
12 | (2) `unsigned __int16` | m_width
14 | (2) `unsigned __int16` | m_height
16 | (1) `bool` | m_small


### `BlockSerializationUtils::<lambda_c386b27b51dd5988e6b0ca8a8aac9607>`
Offset | Type | Name
-|-|-|-


### `bgfx::d3d12::ProgramD3D12`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::d3d12::ShaderD3D12 *` | m_vsh
8 | (8) `const bgfx::d3d12::ShaderD3D12 *` | m_fsh
16 | (192) `bgfx::PredefinedUniform[24]` | m_predefined
208 | (1) `unsigned __int8` | m_numPredefined


### `Bedrock::NonOwnerPointer<WorkerPool>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Social::IUserManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `buffer_span<std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | mBegin
8 | (8) `const std::string *` | mEnd


### `BaseAttributeMap`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<unsigned int,AttributeInstance>` | mInstanceMap
64 | (24) `std::vector<AttributeInstanceHandle>` | mDirtyAttributes


### `BlockMaterialInstancesComponent`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,BlockMaterialInstance>` | mMaterials


### `buffer_span_mut<BrightnessPair const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const BrightnessPair *` | mBegin
8 | (8) `const BrightnessPair *` | mEnd


### `bgfx::gl::ShaderGL`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_id
4 | (4) `unsigned int` | m_type
8 | (4) `unsigned int` | m_hash


### `bgfx::d3d12::IndexedResourceStatesManager<128,bgfx::FrameBufferHandle,bgfx::d3d12::FrameBufferD3D12,bgfx::d3d12::FrameBufferD3D12 [128]>::ResourceStateEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_STATES` | m_initialState
4 | (4) `D3D12_RESOURCE_STATES` | m_currentState


### `bgfx::VertexBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::DynamicIndexBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::DynamicVertexBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::IndirectBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::ShaderBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `buffer_span_mut<ClientBlockPipeline::BlockSchematicCell const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBlockPipeline::BlockSchematicCell *` | mBegin
8 | (8) `const ClientBlockPipeline::BlockSchematicCell *` | mEnd


### `buffer_span_mut<ClientBlockPipeline::BlockCell const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBlockPipeline::BlockCell *` | mBegin
8 | (8) `const ClientBlockPipeline::BlockCell *` | mEnd


### `buffer_span_mut<ClientBlockPipeline::BlockOpacityData const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBlockPipeline::BlockOpacityData *` | mBegin
8 | (8) `const ClientBlockPipeline::BlockOpacityData *` | mEnd


### `buffer_span_mut<float const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const float *` | mBegin
8 | (8) `const float *` | mEnd


### `BlockBakedMaterialDataComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `ClientBlockPipeline::BakedMaterialMap` | mBakedMaterials
32 | (1) `bool` | mIsSolidOpaque


### `BlockSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource_vtbl *` | __vftable
8 | (4) `const std::thread::id` | mOwnerThreadID
12 | (1) `const bool` | mAllowUnpopulatedChunks
13 | (1) `const bool` | mPublicSource
16 | (8) `Level *` | mLevel
24 | (8) `ChunkSource *` | mChunkSource
32 | (8) `Dimension *` | mDimension
40 | (2) `const __int16` | mMaxHeight
42 | (2) `const __int16` | mMinHeight
48 | (24) `std::vector<BlockFetchResult>` | mTempBlockFetchResult
72 | (12) `BlockPos` | mPlaceChunkPos
88 | (24) `std::vector<BlockSourceListener *>` | mListeners
112 | (8) `ChunkPos` | mLastChunkPos
120 | (1) `bool` | mForbidSetBlock
128 | (16) `std::weak_ptr<LevelChunk>` | mLastChunkWeakPtr
144 | (8) `LevelChunk *` | mLastChunkDirectPtr
152 | (8) `BlockTickingQueue *` | mRandomTickQueue
160 | (8) `BlockTickingQueue *` | mTickQueue
168 | (2) `const BrightnessPair` | mDefaultBrightness
176 | (24) `std::vector<Actor *>` | mTempEntityList
200 | (24) `std::vector<BlockActor *>` | mTempBlockEntityList
224 | (24) `std::vector<AABB>` | mTempCubeList


### `BrightnessPair`
Offset | Type | Name
-|-|-|-
0 | (1) `Brightness` | sky
1 | (1) `Brightness` | block


### `BaseActorRenderContext`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseActorRenderContext_vtbl *` | __vftable
8 | (4) `float` | mNumEntitiesRenderedThisFrame
12 | (4) `float` | mLastFrameTime
16 | (4) `const float` | mFrameAlpha
24 | (8) `SortedMeshDrawList *` | mSortedMeshDrawList
32 | (8) `IClientInstance *` | mClientInstance
40 | (8) `IMinecraftGame *` | mMinecraftGame
48 | (8) `ScreenContext *` | mScreenContext
56 | (8) `BlockActorRenderDispatcher *` | mBlockEntityRenderDispatcher
64 | (8) `ActorRenderDispatcher *` | mEntityRenderDispatcher
72 | (8) `ActorBlockRenderer *` | mEntityBlockRenderer
80 | (8) `ItemInHandRenderer *` | mItemInHandRenderer
88 | (8) `ItemRenderer *` | mItemRenderer
96 | (8) `ParticleSystemEngine *` | mParticleSystemEngine
104 | (16) `std::optional<__int64>` | mRenderUniqueIdOverride
120 | (12) `Vec3` | mCameraTargetPosition
132 | (12) `Vec3` | mCameraPosition
144 | (28) `AABB` | mWorldClipRegion
172 | (1) `bool` | mIsOnScreen
173 | (1) `bool` | mUpdateBonesAndEffects
174 | (1) `bool` | mUpdateEffects
175 | (1) `bool` | mIgnoresLightning
176 | (488) `HistoricalFrameTimes` | mHistoricalFrameTimes


### `Bounds`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (12) `Pos` | mDim
36 | (4) `int` | mArea
40 | (4) `int` | mVolume
44 | (4) `int` | mSide


### `Bedrock::NonOwnerPointer<SoundEngine>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<SoundPlayerInterface>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<TextureAtlas const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BedrockTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<BedrockTextureData>` | mBedrockTextureData


### `Bedrock::NonOwnerPointer<LevelLoader>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<DateManager const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<Music>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<ContentAcquisition>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<WebSocketCommManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<TrialManager>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `ButtonUpRightOfFirstRefusalRequest`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | buttonId
8 | (16) `std::weak_ptr<UIControl>` | control


### `ButtonScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `unsigned int` | fromButtonId
8 | (1) `ButtonState` | previousState
9 | (1) `ButtonState` | state
10 | (1) `bool` | handleDeselection
11 | (1) `bool` | handleSelection
16 | (8) `UIPropertyBag *` | properties
24 | (8) `float[2]` | cursorPosition
32 | (1) `bool` | isInteracted
36 | (4) `InputMode` | inputMode
40 | (1) `bool` | outOfClip
48 | (8) `std::string *` | path


### `bgfx::FencedRingBuffer<bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<0> >::RingBufferResourceAllocator,0>::ScopedAllocation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<0> >::RingBufferResourceAllocator::Buffer>` | m_buffer
16 | (8) `const unsigned __int64` | m_offset
24 | (8) `const unsigned __int64` | m_size
32 | (8) `const unsigned __int64` | m_alignmentPrefixSize
40 | (8) `const unsigned __int64` | m_fenceValue


### `buffer_span<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `const int *` | mBegin
8 | (8) `const int *` | mEnd


### `buffer_span_mut<std::shared_ptr<LevelChunk> >`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<LevelChunk> *` | mBegin
8 | (8) `std::shared_ptr<LevelChunk> *` | mEnd


### `BasicTimer`
Offset | Type | Name
-|-|-|-
0 | (8) `long double` | mTimeDelay
8 | (8) `long double` | mStartTime
16 | (64) `std::function<double __cdecl(void)>` | mGetCurrentTimeCallback


### `BossInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `float` | mHealth


### `BossEventListener`
Offset | Type | Name
-|-|-|-
0 | (8) `BossEventListener_vtbl *` | __vftable


### `bgfx::d3d12::ResourceStatesMananger`
Offset | Type | Name
-|-|-|-
0 | (41488) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::IndexBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>` | m_indexBuffers
41488 | (41488) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::VertexBufferHandle,bgfx::d3d12::VertexBufferD3D12,bgfx::d3d12::VertexBufferD3D12 [4096]>` | m_vertexBuffers
82976 | (41488) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::TextureHandle,bgfx::d3d12::TextureD3D12,bgfx::d3d12::TextureD3D12 [4096]>` | m_textures
124464 | (41488) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::ShaderBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>` | m_shaderBuffers
165952 | (1312) `bgfx::d3d12::IndexedResourceStatesManager<128,bgfx::FrameBufferHandle,bgfx::d3d12::FrameBufferD3D12,bgfx::d3d12::FrameBufferD3D12 [128]>` | m_frameBuffers


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::IndexBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::BufferD3D12 (*)[4096]` | m_resources
8 | (2) `unsigned __int16` | m_count
16 | (512) `std::bitset<4096>` | m_sets
528 | (32768) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::IndexBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>::ResourceStateEntry[4096]` | m_states
33296 | (8192) `unsigned __int16[4096]` | m_setIndices


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::IndexBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>::ResourceStateEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_STATES` | m_initialState
4 | (4) `D3D12_RESOURCE_STATES` | m_currentState


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::VertexBufferHandle,bgfx::d3d12::VertexBufferD3D12,bgfx::d3d12::VertexBufferD3D12 [4096]>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::VertexBufferD3D12 (*)[4096]` | m_resources
8 | (2) `unsigned __int16` | m_count
16 | (512) `std::bitset<4096>` | m_sets
528 | (32768) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::VertexBufferHandle,bgfx::d3d12::VertexBufferD3D12,bgfx::d3d12::VertexBufferD3D12 [4096]>::ResourceStateEntry[4096]` | m_states
33296 | (8192) `unsigned __int16[4096]` | m_setIndices


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::VertexBufferHandle,bgfx::d3d12::VertexBufferD3D12,bgfx::d3d12::VertexBufferD3D12 [4096]>::ResourceStateEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_STATES` | m_initialState
4 | (4) `D3D12_RESOURCE_STATES` | m_currentState


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::TextureHandle,bgfx::d3d12::TextureD3D12,bgfx::d3d12::TextureD3D12 [4096]>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::TextureD3D12 (*)[4096]` | m_resources
8 | (2) `unsigned __int16` | m_count
16 | (512) `std::bitset<4096>` | m_sets
528 | (32768) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::TextureHandle,bgfx::d3d12::TextureD3D12,bgfx::d3d12::TextureD3D12 [4096]>::ResourceStateEntry[4096]` | m_states
33296 | (8192) `unsigned __int16[4096]` | m_setIndices


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::TextureHandle,bgfx::d3d12::TextureD3D12,bgfx::d3d12::TextureD3D12 [4096]>::ResourceStateEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_STATES` | m_initialState
4 | (4) `D3D12_RESOURCE_STATES` | m_currentState


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::ShaderBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::BufferD3D12 (*)[4096]` | m_resources
8 | (2) `unsigned __int16` | m_count
16 | (512) `std::bitset<4096>` | m_sets
528 | (32768) `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::ShaderBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>::ResourceStateEntry[4096]` | m_states
33296 | (8192) `unsigned __int16[4096]` | m_setIndices


### `bgfx::d3d12::IndexedResourceStatesManager<4096,bgfx::ShaderBufferHandle,bgfx::d3d12::BufferD3D12,bgfx::d3d12::BufferD3D12 [4096]>::ResourceStateEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_STATES` | m_initialState
4 | (4) `D3D12_RESOURCE_STATES` | m_currentState


### `bgfx::d3d12::IndexedResourceStatesManager<128,bgfx::FrameBufferHandle,bgfx::d3d12::FrameBufferD3D12,bgfx::d3d12::FrameBufferD3D12 [128]>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::FrameBufferD3D12 (*)[128]` | m_resources
8 | (2) `unsigned __int16` | m_count
16 | (16) `std::bitset<128>` | m_sets
32 | (1024) `bgfx::d3d12::IndexedResourceStatesManager<128,bgfx::FrameBufferHandle,bgfx::d3d12::FrameBufferD3D12,bgfx::d3d12::FrameBufferD3D12 [128]>::ResourceStateEntry[128]` | m_states
1056 | (256) `unsigned __int16[128]` | m_setIndices


### `Bedrock::NonOwnerPointer<ContentCatalogService>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<StoreCatalogRepository>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BaseCommandBlock`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mLastOutputId
32 | (24) `std::vector<std::string>` | mLastOutputParams
56 | (32) `std::string` | mCommand
88 | (32) `std::string` | mName
120 | (8) `std::unique_ptr<Command>` | mCompiledCommand
128 | (8) `unsigned __int64` | mLastExecution
136 | (4) `int` | mVersion
140 | (4) `int` | mSuccessCount
144 | (4) `int` | mTickDelay
148 | (1) `bool` | mExecuteOnFirstTick
149 | (1) `bool` | mTrackOutput


### `BatchClippingState`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,0>` | mTopLeftClip
8 | (8) `glm::tvec2<float,0>` | mBottomRightClip
16 | (1) `bool` | mClipsChildren
17 | (1) `bool` | mEnableScissorTest
24 | (16) `ClipAreas` | mClipArea


### `BatchVisualState`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mAlpha
4 | (4) `float` | mPropagatedAlpha


### `BatchKey`
Offset | Type | Name
-|-|-|-
0 | (4) `UIBatchType` | mBatchType
4 | (4) `int` | mCustomId
8 | (4) `int` | mDepth
12 | (4) `float` | mAlpha
16 | (16) `mce::Color` | mColor
32 | (4) `_BYTE[4]` | mUIMaterialType
40 | (40) `BatchClippingState` | mClippingState
80 | (112) `std::array<ResourceLocation,2>` | mResourceLocations


### `BindInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `BindType` | bindType
4 | (1) `bool` | autoScale
8 | (12) `Vec3` | pos
24 | (8) `ActorUniqueID` | bindEntityId
32 | (4) `float` | scaleRate


### `BindingFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `BindingFactory_vtbl *` | __vftable


### `BuildActionIntention`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mAction


### `bgfx::d3d9::VertexBufferD3D9`
Offset | Type | Name
-|-|-|-
0 | (8) `IDirect3DVertexBuffer9 *` | m_ptr
8 | (8) `unsigned __int8 *` | m_dynamic
16 | (4) `unsigned int` | m_size
20 | (2) `bgfx::VertexDeclHandle` | m_decl


### `BossEventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `const int` | FLAG_DARKEN
44 | (4) `const int` | FLAG_FOG
48 | (8) `ActorUniqueID` | mBossID
56 | (8) `ActorUniqueID` | mPlayerID
64 | (4) `BossEventUpdateType` | mEventType
72 | (32) `std::string` | mName
104 | (4) `float` | mHealthPercent
108 | (4) `BossBarColor` | mColor
112 | (4) `BossBarOverlay` | mOverlay
116 | (1) `unsigned __int8` | mDarkenScreen
117 | (1) `unsigned __int8` | mCreateWorldFog


### `Bedrock::NonOwnerPointer<FogDefinitionRegistry const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BlockEventPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (12) `NetworkBlockPosition` | mPos
52 | (4) `int` | mB0
56 | (4) `int` | mB1


### `buffer_span_mut<ExpressionNode>`
Offset | Type | Name
-|-|-|-
0 | (8) `ExpressionNode *` | mBegin
8 | (8) `ExpressionNode *` | mEnd


### `BlockGeometry::ElementBox`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mOrigin
12 | (12) `glm::tvec3<float,0>` | mSize
24 | (384) `std::array<BlockGeometry::Face,6>` | mFaces


### `BlockGeometry::Face`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | u0
4 | (4) `float` | v0
8 | (4) `float` | u1
12 | (4) `float` | v1
16 | (4) `int` | rotation
24 | (32) `std::string` | texture
56 | (4) `int` | textureIndex
60 | (1) `bool` | enabled


### `BlockGraphics`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockGraphics_vtbl *` | __vftable
8 | (8) `IsotropicFaceData` | mIsotropicFaceData
16 | (8) `const Block *` | mBlock
24 | (4) `BlockRenderLayer` | mRenderLayer
28 | (4) `BlockShape` | mBlockShape
32 | (1) `bool` | mAnimatedTexture
36 | (4) `float` | mBrightnessGamma
40 | (1) `bool` | mFancy
41 | (1) `bool` | mAllowSame
44 | (4) `BlockSoundType` | mSoundType
48 | (28) `AABB` | mVisualShape
80 | (24) `std::vector<TextureItem>` | mTextureItems
104 | (8) `unsigned __int64` | mIconTextureIndex
112 | (24) `std::vector<std::vector<BlockGeometry::Model const *>>` | mBlockModelVariants
136 | (24) `std::vector<std::vector<BlockGraphics::ModelItem>>` | mTessellatedModelParts
160 | (16) `?` | mUsingModTessellatedModel


### `BlockGraphics::initBlocks::__l2::<lambda_ae40432cfeaa2b9f26426c68835add40>`
Offset | Type | Name
-|-|-|-


### `BlockOccluder`
Offset | Type | Name
-|-|-|-
0 | (4) `std::bitset<6>` | mFacingOccluded
8 | (8) `BlockTessellatorCache *` | mBlockCache


### `BlockTessellatorBlockInWorld`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block *` | block
8 | (4) `BlockRenderLayer` | layer
12 | (12) `BlockPos` | pos
24 | (8) `const void *` | owner


### `BlockTessellatorCustomExtraData::CauldronData`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | mColor
16 | (4) `int` | mTextureIndex
20 | (4) `int` | mRenderLayer


### `BannerBlockActor`
Offset | Type | Name
-|-|-|-
0 | (288) `BlockActor` | baseclass_0
288 | (1) `bool` | mDirtyBounds
289 | (1) `unsigned __int8` | mBaseColor
296 | (24) `std::vector<unsigned char>` | mPatterns
320 | (24) `std::vector<unsigned char>` | mColors
344 | (4) `BannerBlockType` | mBannerType


### `BlockActor`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockActor_vtbl *` | __vftable
8 | (4) `int` | mTickCount
12 | (16) `mce::Color` | mFront
28 | (16) `mce::Color` | mBack
48 | (8) `long double` | mPercent
56 | (1) `bool` | mShowProcessBar
57 | (1) `bool` | mCanRenderNameTag
64 | (8) `const Block *` | mBlock
72 | (4) `float` | mDestroyTimer
76 | (12) `Vec3` | mDestroyDirection
88 | (4) `float` | mDestroyProgress
92 | (12) `BlockPos` | mPosition
104 | (28) `AABB` | mBB
132 | (4) `const BlockActorType` | mType
136 | (4) `BlockActorRendererId` | mRendererId
144 | (32) `std::string` | mCustomName
176 | (32) `std::string` | mFilteredCustomName
208 | (4) `int` | mRepairCost
212 | (1) `bool` | mClientSideOnly
213 | (1) `bool` | mIsMovable
214 | (1) `bool` | mSaveCustomName
215 | (1) `bool` | mCanRenderCustomName
216 | (4) `const float` | signShadowRadius
224 | (32) `std::string` | mUserCustomData
256 | (24) `ActorTerrainInterlockData` | mTerrainInterlockData
280 | (1) `bool` | mChanged


### `BannerRenderer::_setupTextureAtlas::__l2::<lambda_d1aa061d604d54f0e610811945668f01>`
Offset | Type | Name
-|-|-|-
0 | (8) `BannerRenderer *const` | __this
8 | (8) `mce::TextureGroup *` | textures
16 | (24) `std::vector<std::string>` | patternTextures
40 | (16) `std::map<std::string,BackwardsCompatTextureInfo>` | backCompatTextures


### `buffer_span_mut<SubChunk>`
Offset | Type | Name
-|-|-|-
0 | (8) `SubChunk *` | mBegin
8 | (8) `SubChunk *` | mEnd


### `ByteMask`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mask


### `BlockTessellatorCustomExtraData::Map`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<BlockPos,BlockTessellatorCustomExtraData::CauldronData>` | mExtraCauldronData
64 | (64) `std::unordered_map<BlockPos,BlockTessellatorCustomExtraData::FlowerPotData>` | mExtraFlowerPotData


### `buffer_span_mut<RangeIndices>`
Offset | Type | Name
-|-|-|-
0 | (8) `RangeIndices *` | mBegin
8 | (8) `RangeIndices *` | mEnd


### `BlockActorBlockSyncMessage`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mBlockEntityPos
12 | (4) `_BYTE[4]` | mMessage


### `buffer_span_mut<CommandListFuture>`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandListFuture *` | mBegin
8 | (8) `CommandListFuture *` | mEnd


### `BlockDestructInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | destructRate
4 | (4) `float` | destructProgress


### `buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<RenderChunkInstanced> *` | mBegin
8 | (8) `std::shared_ptr<RenderChunkInstanced> *` | mEnd


### `Bedrock::Threading::CountReference`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::Threading::CountTracker *` | mCountSource


### `bgfx::d3d12::FenceSyncContext::addBuffer::__l2::<lambda_ac6b7a419de5ff0a554a1beba548a9d9>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<0> > *` | buffer


### `Bedrock::Threading::Burst::Details::WorkTargetItem`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mWorkerCount
8 | (8) `unsigned __int64` | mKickCount


### `BlockDescriptor`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mBlockName
48 | (16) `std::shared_ptr<ExpressionNode>` | mTags
64 | (24) `std::vector<BlockDescriptor::BlockState>` | mStates
88 | (4) `_BYTE[4]` | mCompareType
96 | (8) `const Block *` | mBlock
104 | (1) `bool` | mValid
105 | (1) `bool` | mIsDeferred


### `BuoyancyComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mBaseBuoyancy
4 | (4) `float` | mDragDownOnRemoval
8 | (4) `float` | mBigWaveProbability
12 | (4) `float` | mBigWaveSpeedMultiplier
16 | (1) `bool` | mSimulateWaves
17 | (1) `bool` | mApplyGravity
24 | (8) `long double` | mTimer
32 | (24) `std::vector<BlockDescriptor>` | mLiquidBlocks


### `Bedrock::NonOwnerPointer<PackStorage::PackStorageImpl>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `Bedrock::NonOwnerPointer<cg::TextureSetLayerDefinition const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_28e21e68b5d2bdce02834018dcd63395>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<CappedSurfaceAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_d6ab075ac52cb670009075d6b429800e>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<CappedSurfaceAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BlockRaycastComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mEnabled
1 | (1) `bool` | mWorldInfoBaked
4 | (28) `AABB` | mOriginalAABB
32 | (28) `AABB` | mTransformedAABB


### `BlockFrictionComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mFriction


### `BlockDisplayNameComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mDisplayName


### `BlockGeometryComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mGeometryName
32 | (16) `std::shared_ptr<ClientBlockPipeline::BlockSchematic>` | mBlockSchematic


### `BlockLightEmissionComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `Brightness` | mLightEmission


### `BlockPlacementCondition`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | directionalFilter
8 | (24) `std::vector<BlockDescriptor>` | blockFilter


### `BlockPlacementFilterComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BlockPlacementCondition>` | conditions


### `BlockQueuedTickingComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | mDelayRange
8 | (1) `bool` | mLooping
16 | (320) `DefinitionTrigger` | mOnTimeDown


### `BlockUnitCubeComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ClientBlockPipeline::BlockSchematic>` | mBlockSchematic


### `BidirectionalUnorderedMap<int,unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<int,unsigned __int64>` | mRight
64 | (64) `std::unordered_map<unsigned __int64,int>` | mLeft


### `BlockVolume`
Offset | Type | Name
-|-|-|-
0 | (16) `buffer_span_mut<Block const *>` | mBlocks
16 | (4) `unsigned int` | mWidth
20 | (4) `unsigned int` | mHeight
24 | (4) `unsigned int` | mDepth


### `buffer_span_mut<Block const *>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | mBegin
8 | (8) `const Block **` | mEnd


### `BoundingBox`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | min
12 | (12) `BlockPos` | max


### `BeardAndShaverDescription`
Offset | Type | Name
-|-|-|-
0 | (24) `BoundingBox` | mCachedPieceBounds
24 | (4) `int` | mCachedPieceBaseY
28 | (4) `int` | mCachedXCenter
32 | (4) `int` | mCachedZCenter
36 | (4) `float` | mCachedMaxRadius
40 | (4) `int` | mDeltaTargetY
44 | (24) `BoundingBox` | mBoundingBox
68 | (4) `float` | mMinBeardWidth
72 | (4) `float` | mMaxBeardWidth


### `BreedableType`
Offset | Type | Name
-|-|-|-
0 | (176) `ActorDefinitionIdentifier` | mMateType
176 | (176) `ActorDefinitionIdentifier` | mBabyType
352 | (320) `DefinitionTrigger` | mOnBred


### `BlockBreakSensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mSensorRadius
4 | (12) `Vec3` | mSensorPos
16 | (16) `BlockEventDispatcherToken` | mListener
32 | (24) `std::vector<BlockListEventMap>` | mBlockSets


### `BlockEventDispatcherToken`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mHandle
8 | (8) `BlockEventDispatcher *` | mDispatcher


### `BinaryHeap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PathfinderNode *>` | heap
24 | (4) `int` | sizeVar


### `BlockSet`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | cost
8 | (24) `std::vector<BlockDescriptor>` | blockDescriptors


### `BossComponent`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (1) `bool` | mHealthBarVisible
36 | (4) `float` | mHealthPercent
40 | (1) `bool` | mShouldDarkenSky
41 | (1) `bool` | mCreateWorldFog
44 | (4) `BossBarColor` | mColor
48 | (4) `BossBarOverlay` | mOverlay
52 | (4) `int` | mPlayersRegistered
56 | (4) `int` | mLastHealth
60 | (4) `int` | mHudRangeSquared
64 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mLastPlayerUpdate
72 | (64) `std::unordered_map<mce::UUID,int>` | mPlayerParty


### `BehaviorComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `BehaviorTreeDefinitionPtr` | mTreeDefinition
16 | (8) `std::unique_ptr<BehaviorNode>` | mRoot
24 | (88) `BehaviorData` | mBehaviorData
112 | (32) `std::string` | mBehaviorTreeId


### `BehaviorData`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,std::unique_ptr<BehaviorData::DataProxy>>` | mData
64 | (24) `std::vector<std::unique_ptr<BehaviorData::DataProxy>>` | mDataStack


### `BreakBlocksSystem::tick::__l2::<lambda_6fc3bb95378df2694061b49575fc6c14>`
Offset | Type | Name
-|-|-|-
0 | (8) `BreakBlocksSystem *const` | __this


### `BreathableComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSuffocateTime
4 | (4) `float` | mInhaleTime
8 | (4) `int` | mAirRegenPerTick
12 | (1) `bool` | mBreathesAir
13 | (1) `bool` | mBreathesWater
14 | (1) `bool` | mBreathesLava
15 | (1) `bool` | mBreathesSolids
16 | (1) `bool` | mGeneratesBubbles
18 | (2) `__int16` | mAirSupply
20 | (2) `__int16` | mAirSupplyMax
24 | (24) `std::vector<BlockDescriptor>` | mBreathableBlocks
48 | (24) `std::vector<BlockDescriptor>` | mNonBreathableBlocks
72 | (4) `BreathableComponent::BreathableState` | mBreathableState
76 | (1) `bool` | mIsConsumingAirSupply


### `ByteTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (1) `unsigned __int8` | data


### `ByteArrayTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (24) `TagMemoryChunk` | data


### `BatchedNetworkPeer::DataCallback`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | data
32 | (4) `Compressibility` | compressible
40 | (64) `std::function<void __cdecl(void)>` | callback


### `BookEditPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `BookEditAction` | mAction
44 | (4) `int` | mBookSlot
48 | (4) `int` | mPageIndex1
52 | (4) `int` | mPageIndex2
56 | (32) `std::string` | mText1
88 | (32) `std::string` | mText2
120 | (32) `std::string` | mText3


### `BlockVolume::BlockVolumeIter`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | pos
12 | (12) `Pos` | dims
24 | (8) `buffer_span_mut<Block const *>::iterator` | blockIter


### `buffer_span_mut<Block const *>::iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `const Block **` | mPtr


### `BinaryStream`
Offset | Type | Name
-|-|-|-
0 | (64) `ReadOnlyBinaryStream` | baseclass_0
64 | (32) `std::string` | mOwnedBuffer
96 | (8) `std::string *` | mBuffer


### `Bedrock::NonOwnerPointer<ServerInstanceEventCoordinator>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BlockChange`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mUpdateFlags
8 | (8) `const Block *` | mOldBlock
16 | (8) `const Block *` | mNewBlock


### `Bedrock::Threading::completeThen::__l2::<lambda_0b7e0b68a12c863263a53ce71992289b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<std::pair<Json::Value,Core::PathBuffer<std::string > > > >` | wrapperTask
16 | (40) `ActorDefinitionGroup::_getResources::__l8::<lambda_d64fe27ef6da0a56cad972a0ec1d52ab>` | callback


### `Bedrock::NonOwnerPointer<Level>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock>` | mControlBlock


### `BarterComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mItemOriginationActorUniqueID
8 | (2) `__int16` | mBarterItemId
10 | (1) `bool` | mExecuteTrade


### `BlockReducer`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockReducer_vtbl *` | __vftable
8 | (64) `std::unordered_map<int,std::vector<ItemStack>>` | mBlockToElements


### `BlockLegacy::tryGetStateFromLegacyData::__l2::<lambda_aa356eec0c94171593ee29f169b1c8dd>`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockLegacy *const` | __this
8 | (2) `unsigned __int16` | data


### `BuildMatch`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mMatched
1 | (1) `unsigned __int8` | mForward
2 | (1) `unsigned __int8` | mUp
4 | (4) `int` | mNumPatterns
8 | (4) `int` | mPatternSize
12 | (4) `int` | mSubPatternIndex
16 | (4) `int` | mRowIndex
20 | (12) `BlockPos` | mPattern
32 | (12) `Vec3` | mObjectPos


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_588cbba04482f56d12cfb2e5c6cae432>::()::__l2::<lambda_45198a55f8a28523ff9cd66bab017799>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<BiomeDecorationAttributes<ListedFeatures> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_2b22735977b37e611b382921ec440033>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ClimateAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_45252a856d8739e9c6bb0100836f32b3>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<SurfaceMaterialAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_e1885f2df24d7b159c293c55fe6bfd77>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<OverworldHeightAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_9cd4a940da8b9d3c7f88c55d5cb46739>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<OverworldHeightAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeDecorationAttributes<ListedFeatures>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BiomeDecorationFeature *>` | mFeatures
24 | (64) `std::unordered_set<HashedString>` | mFeatureRuleNameSet


### `BlockActorFactory::createBlockEntity::__l4::<lambda_0a8b0200222e817880ba31bb39105399>`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockActorType *` | type


### `BaseRailBlock::Rail`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *` | mRegion
8 | (12) `BlockPos` | mPos
20 | (1) `bool` | mUsesDataBit
24 | (24) `std::vector<BlockPos>` | mConnections


### `BlockDefinition`
Offset | Type | Name
-|-|-|-
0 | (112) `SemVersion` | mFormatVersion
112 | (192) `BlockDescription` | mDescription
304 | (48) `BlockComponentGroupDescription` | mBaseComponents
352 | (24) `std::vector<BlockPermutationDescription>` | mPermutationDescriptions
376 | (64) `std::unordered_map<std::string,DefinitionEvent>` | mEventHandlers


### `BlockDescription`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mIdentifier
32 | (24) `std::vector<BlockStateDefinition>` | mStates
56 | (32) `std::string` | mMaterial
88 | (32) `std::string` | mBaseBlock
120 | (32) `std::string` | mCategory
152 | (32) `std::string` | mMicroSize
184 | (1) `bool` | mRegisterToCreativeMenu


### `BlockComponentGroupDescription`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<BlockComponentDescription>>` | mDescriptions
24 | (24) `std::vector<HashedString>` | mTags


### `BlockStateDefinition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (1) `_BYTE[1]` | mType
40 | (8) `std::unique_ptr<ListTag>` | mEnumValues
48 | (8) `const ItemState *` | mEngineState


### `BlockDefinitionGroup::loadResourcesMod::__l2::BlockResource`
Offset | Type | Name
-|-|-|-
0 | (112) `SemVersion` | mVersion
112 | (192) `BlockDescription` | mDescription
304 | (16) `Json::Value` | mRoot


### `BlockSource::fetchBlocksInCylinder::__l2::<lambda_0d9328dc3cbb3a479fb4635880f92988>`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *const` | __this
8 | (8) `const BlockPos *` | centerPos
16 | (4) `unsigned int` | radius
20 | (4) `unsigned int` | height
24 | (8) `std::function<bool __cdecl(Block const &)> *` | predicate


### `BlockSource::fetchBlocksInBox::__l2::<lambda_f079637cc512a127f579039b711c8a60>`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSource *const` | __this
8 | (8) `const BoundingBox *` | box
16 | (8) `std::function<bool __cdecl(Block const &)> *` | predicate


### `BlockTickingQueue::BlockTick`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsRemoved
8 | (40) `TickNextTickData` | mData


### `BlockFetchResult`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<Block const >` | mBlock
8 | (12) `BlockPos` | mBlockPos
20 | (4) `unsigned int` | mDistanceSquared


### `BiomeDecorationFeature`
Offset | Type | Name
-|-|-|-
0 | (1816) `ScatterParams` | mScatter
1816 | (24) `WeakRefT<FeatureRefTraits>` | mFeature
1840 | (48) `HashedString` | mIdentifier


### `BiomeFilterGroup`
Offset | Type | Name
-|-|-|-
0 | (64) `FilterGroup` | baseclass_0


### `Block`
Offset | Type | Name
-|-|-|-
0 | (8) `Block_vtbl *` | __vftable
8 | (2) `const unsigned __int16` | mData
16 | (8) `gsl::not_null<BlockLegacy *>` | mLegacyBlock
24 | (24) `CompoundTag` | mSerializationId
48 | (4) `unsigned int` | mRuntimeId
52 | (1) `bool` | mHasRuntimeId
56 | (20) `CachedComponentData` | mCachedComponentData
80 | (24) `OwnerPtrT<EntityRefTraits>` | mEntity
104 | (24) `std::vector<HashedString>` | mTags
128 | (1) `bool` | mSetByPlayer


### `BiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeSource_vtbl *` | __vftable


### `BonusChestFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `BigEndianStringByteInput`
Offset | Type | Name
-|-|-|-
0 | (32) `StringByteInput` | baseclass_0


### `BytesDataInput`
Offset | Type | Name
-|-|-|-
0 | (8) `IDataInput` | baseclass_0


### `BlockTickingQueue::TickDataSet`
Offset | Type | Name
-|-|-|-
0 | (24) `MovePriorityQueue<BlockTickingQueue::BlockTick,std::greater<BlockTickingQueue::BlockTick> >` | baseclass_0


### `BiomeChunkData`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | biome


### `bgfx::Memory`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | data
8 | (4) `unsigned int` | size


### `bgfx::ShaderHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::Init`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::RendererType::Enum` | type
4 | (2) `unsigned __int16` | vendorId
6 | (2) `unsigned __int16` | deviceId
8 | (1) `bool` | debug
9 | (1) `bool` | profile
12 | (12) `bgfx::Resolution` | resolution
24 | (16) `bgfx::Init::Limits` | limits
40 | (8) `bgfx::CallbackI *` | callback
48 | (8) `bx::AllocatorI *` | allocator


### `bgfx::Init::Limits`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | maxEncoders
4 | (4) `unsigned int` | transientVbSize
8 | (4) `unsigned int` | transientIbSize
12 | (1) `unsigned __int8` | maxRendererWorkers


### `bgfx::InstanceDataBuffer`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | data
8 | (4) `unsigned int` | size
12 | (4) `unsigned int` | offset
16 | (4) `unsigned int` | num
20 | (2) `unsigned __int16` | stride
22 | (2) `bgfx::VertexBufferHandle` | handle


### `BaseGamePackSlices`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<BaseGamePackSlices::BaseGameVersionPack>` | mBaseGameVersionPacks
24 | (24) `std::vector<BaseGamePackSlices::BaseGameVersionPack>` | mBaseGameVersionTestPacks


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_304b29c86db3d6bdd6f6537782e989e0>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<MesaSurfaceAttributes & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_7bf6a58d63e3c81bd35ab4e9d081ecbf>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<WeightedBiomeAttributes<HillsTransformation> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_86a0f9e6e32f92158f68bfa3784704c3>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<WeightedBiomeAttributes<MutateBiomeTransformation> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_2892db5edaa4d8160c8761f115eea62c>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<WeightedBiomeAttributes<RiverTransformation> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_9d9461e1e6ffd446a377f5480aefaf21>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<WeightedBiomeAttributes<ShoreTransformation> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | componentAccessor


### `BiomeComponentLoading::_buildSchema::__l2::<lambda_f24f1fe26483478c4c9f59e59c913b83>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<std::vector<std::pair<Biome *,unsigned int>> & __cdecl(std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > *)>` | biomeVectorAccessor


### `BlockSelector`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockSelector_vtbl *` | __vftable


### `BlockTickingQueue`
Offset | Type | Name
-|-|-|-
0 | (8) `LevelChunk *` | mOwningChunk
8 | (8) `Tick` | mCurrentTick
16 | (24) `BlockTickingQueue::TickDataSet` | mNextTickQueue
40 | (24) `BlockTickingQueue::TickDataSet` | mActiveTickQueue
64 | (1) `TickingQueueType` | mQueueType
65 | (1) `bool` | mInstaTick


### `BiomeArea`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mStride
8 | (24) `std::vector<Biome const *>` | mBiomes


### `Biome`
Offset | Type | Name
-|-|-|-
0 | (8) `Biome_vtbl *` | __vftable
8 | (32) `std::string` | mName
40 | (4) `int` | mDebugMapColor
44 | (4) `int` | mDebugMapOddColor
48 | (4) `float` | mTemperature
52 | (4) `float` | mDownfall
56 | (4) `float` | mRedSporeDensity
60 | (4) `float` | mBlueSporeDensity
64 | (4) `float` | mAshDensity
68 | (4) `float` | mWhiteAshDensity
72 | (4) `float` | mSnowAccumulation
76 | (4) `float` | mFoliageSnow
80 | (4) `float` | mMinSnowLevel
84 | (4) `float` | mMaxSnowLevel
88 | (4) `float` | mDepth
92 | (4) `float` | mScale
96 | (16) `mce::Color` | mWaterColor
112 | (4) `float` | mWaterTransparency
116 | (1) `bool` | mRain
120 | (4) `int` | mId
128 | (16) `WeakRefT<SharePtrRefTraits<FogDefinition const > >` | mFogDefinition
144 | (12) `OceanRuinConfiguration` | mOceanRuinConfig
160 | (24) `std::vector<MobSpawnerData>` | mMobs
184 | (8) `std::unique_ptr<PerlinSimplexNoise>` | mTemperatureNoise
192 | (8) `std::unique_ptr<PerlinSimplexNoise>` | mFrozenTemperatureNoise
200 | (24) `OwnerPtrT<EntityRefTraits>` | mEntity
224 | (16) `OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> >` | mBiomeInfoNoise
240 | (4) `AutomaticID<Dimension,int>` | mDimensionType
248 | (32) `std::string` | mVanillaName


### `BlockActorFactory::registerCustomBlockEntityCreationCallback::__l2::<lambda_fff5251917a5d96d413be26580a41046>`
Offset | Type | Name
-|-|-|-


### `ButtonChordTracker::ChordButtonDetails`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | buttonMaskForThisChord
4 | (4) `int` | completeChordMask
8 | (4) `unsigned int` | resultantButtonId
12 | (4) `int` | currentStateIndex
16 | (4) `int` | originalChordButtonSequenceIndex


### `ButtonEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (1) `ButtonState` | state
5 | (1) `bool` | exclusive
8 | (4) `float` | repeatInterval


### `ButtonChordTracker::TrackerMappingAndState`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_multimap<unsigned int,ButtonChordTracker::ChordButtonDetails>` | mChordMap
64 | (24) `std::vector<int>` | mChordState
88 | (24) `std::vector<std::vector<unsigned int>>` | mButtonSequences


### `Bedrock::JSONObject::ValueWrapper`
Offset | Type | Name
-|-|-|-
0 | (4) `Bedrock::JSONObject::JSONType` | mType
8 | (64) `$26CCF555AF14FCAE7148684434635FE2` | ___u1


### `Bedrock::JSONObject::ValueWrapper::NumberInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `$3EB15921B14454EE0C46C34FC3F1335B` | ___u0
8 | (1) `bool` | mIsFloatingPoint


### `Bedrock::JSONObject::ValueWrapper::StringInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mString
8 | (4) `unsigned int` | mLength
12 | (4) `unsigned int` | mCopy


### `bgfx::d3d12rtx::IrradianceCacheClearContext`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_blasIdx


### `Bedrock::JSONObject::ParseHandler`
Offset | Type | Name
-|-|-|-
0 | (8) `gsl::not_null<Bedrock::JSONObject::Document *>` | mDocument
8 | (8) `Bedrock::JSONObject::ParseHandler::StackEntry *` | mStack


### `Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>::iterator_base<0>`
Offset | Type | Name
-|-|-|-
0 | (8) `Bedrock::JSONObject::NodeBase *` | mHook


### `black_TWorker_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | precision_bits
4 | (4) `int` | precision
8 | (4) `int` | precision_half
12 | (4) `int` | precision_scale
16 | (4) `int` | precision_step
20 | (4) `int` | precision_jitter
24 | (8) `int *` | buff
32 | (8) `int *` | sizeBuff
40 | (8) `int *` | maxBuff
48 | (8) `int *` | top
56 | (4) `int` | error
60 | (4) `int` | numTurns
64 | (8) `TPoint_ *` | arc
72 | (2) `unsigned __int16` | bWidth
80 | (8) `unsigned __int8 *` | bOrigin
88 | (4) `int` | lastX
92 | (4) `int` | lastY
96 | (4) `int` | minY
100 | (4) `int` | maxY
104 | (2) `unsigned __int16` | num_Profs
106 | (1) `char` | fresh
107 | (1) `char` | joint
112 | (8) `TProfile_ *` | cProfile
120 | (8) `TProfile_ *` | fProfile
128 | (8) `TProfile_ *` | gProfile
136 | (4) `TStates_` | state
144 | (40) `FT_Bitmap_` | target
184 | (40) `FT_Outline_` | outline
224 | (4) `int` | traceOfs
228 | (2) `__int16` | traceIncr
232 | (8) `void (__fastcall *)(black_TWorker_ *, __int16 *, __int16 *)` | Proc_Sweep_Init
240 | (8) `void (__fastcall *)(black_TWorker_ *, __int16, int, int, TProfile_ *, TProfile_ *)` | Proc_Sweep_Span
248 | (8) `void (__fastcall *)(black_TWorker_ *, __int16, int, int, TProfile_ *, TProfile_ *)` | Proc_Sweep_Drop
256 | (8) `void (__fastcall *)(black_TWorker_ *)` | Proc_Sweep_Step
264 | (1) `unsigned __int8` | dropOutControl
265 | (1) `char` | second_pass
268 | (776) `TPoint_[97]` | arcs
1044 | (64) `black_TBand_[16]` | band_stack
1108 | (4) `int` | band_top


### `black_TBand_`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | y_min
2 | (2) `__int16` | y_max


### `BDF_PropertyRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `BDF_PropertyType_` | type
8 | (8) `union {const char *atom;int integer;unsigned int cardinal;}` | u


### `bufferinfo`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | buf
8 | (8) `_object *` | obj
16 | (8) `__int64` | len
24 | (8) `__int64` | itemsize
32 | (4) `int` | readonly
36 | (4) `int` | ndim
40 | (8) `char *` | format
48 | (8) `__int64 *` | shape
56 | (8) `__int64 *` | strides
64 | (8) `__int64 *` | suboffsets
72 | (16) `__int64[2]` | smalltable
88 | (8) `void *` | internal


### `buffered`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | ob_refcnt
8 | (8) `_typeobject *` | ob_type
16 | (8) `_object *` | raw
24 | (4) `int` | ok
28 | (4) `int` | detached
32 | (4) `int` | readable
36 | (4) `int` | writable
40 | (4) `int` | fast_closed_checks
48 | (8) `__int64` | abs_pos
56 | (8) `char *` | buffer
64 | (8) `__int64` | pos
72 | (8) `__int64` | raw_pos
80 | (8) `__int64` | read_end
88 | (8) `__int64` | write_pos
96 | (8) `__int64` | write_end
104 | (8) `void *` | lock
112 | (4) `volatile int` | owner
120 | (8) `__int64` | buffer_size
128 | (8) `__int64` | buffer_mask
136 | (8) `_object *` | dict
144 | (8) `_object *` | weakreflist


### `BCinfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | e0
4 | (4) `int` | nd
8 | (4) `int` | nd0
12 | (4) `int` | scale


### `bgfx::NonLocalAllocator::Allocation`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_ptr
8 | (4) `unsigned int` | m_offset


### `bgfx::Context::DynamicVertexAllocation`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_ptr
8 | (4) `unsigned int` | m_offset
16 | (8) `unsigned __int64` | m_totalSize


### `bx::MemoryReader`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::ReaderSeekerI` | baseclass_0
16 | (8) `const unsigned __int8 *` | m_data
24 | (8) `__int64` | m_pos
32 | (8) `__int64` | m_top


### `bx::ReaderSeekerI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::ReaderI` | baseclass_0
8 | (8) `bx::SeekerI` | baseclass_8


### `bx::ReaderI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::ReaderI_vtbl *` | __vftable


### `bx::SeekerI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::SeekerI_vtbl *` | __vftable


### `bx::Error`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::StringView` | m_msg
16 | (4) `unsigned int` | m_code


### `bx::StringView`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | m_ptr
8 | (4) `int` | m_len


### `bimg::ImageContainer`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::AllocatorI *` | m_allocator
8 | (8) `void *` | m_data
16 | (4) `_BYTE[4]` | m_format
20 | (4) `bimg::Orientation::Enum` | m_orientation
24 | (4) `unsigned int` | m_size
28 | (4) `unsigned int` | m_offset
32 | (4) `unsigned int` | m_width
36 | (4) `unsigned int` | m_height
40 | (4) `unsigned int` | m_depth
44 | (2) `unsigned __int16` | m_numLayers
46 | (1) `unsigned __int8` | m_numMips
47 | (1) `bool` | m_hasAlpha
48 | (1) `bool` | m_cubeMap
49 | (1) `bool` | m_ktx
50 | (1) `bool` | m_ktxLE
51 | (1) `bool` | m_srgb


### `bx::WriterI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::WriterI_vtbl *` | __vftable


### `bx::DefaultAllocator`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::AllocatorI` | baseclass_0


### `bx::AllocatorI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::AllocatorI_vtbl *` | __vftable


### `bgfx::Context`
Offset | Type | Name
-|-|-|-
0 | (128) `bx::Semaphore` | m_renderSem
128 | (128) `bx::Semaphore` | m_apiSem
256 | (128) `bx::Semaphore` | m_encoderEndSem
384 | (64) `bx::Mutex` | m_encoderApiLock
448 | (64) `bx::Mutex` | m_resourceApiLock
512 | (464) `bx::Thread` | m_thread
976 | (8) `bgfx::EncoderStats *` | m_encoderStats
984 | (8) `bgfx::Encoder *` | m_encoder0
992 | (8) `bgfx::EncoderImpl *` | m_encoder
1000 | (4) `unsigned int` | m_numEncoders
1008 | (8) `bx::HandleAlloc *` | m_encoderHandle
1024 | (96326016) `bgfx::Frame[2]` | m_frame
96327040 | (8) `bgfx::Frame *` | m_render
96327048 | (8) `bgfx::Frame *` | m_submit
96327056 | (524280) `unsigned __int64[65535]` | m_tempKeys
96851336 | (131070) `unsigned __int16[65535]` | m_tempValues
96982408 | (16384) `bgfx::IndexBuffer[4096]` | m_indexBuffers
96998792 | (32768) `bgfx::VertexBuffer[4096]` | m_vertexBuffers
97031560 | (81920) `bgfx::DynamicIndexBuffer[4096]` | m_dynamicIndexBuffers
97113480 | (114688) `bgfx::DynamicVertexBuffer[4096]` | m_dynamicVertexBuffers
97228168 | (2) `unsigned __int16` | m_numFreeDynamicIndexBufferHandles
97228170 | (2) `unsigned __int16` | m_numFreeDynamicVertexBufferHandles
97228172 | (2) `unsigned __int16` | m_numFreeOcclusionQueryHandles
97228174 | (8192) `bgfx::DynamicIndexBufferHandle[4096]` | m_freeDynamicIndexBufferHandle
97236366 | (8192) `bgfx::DynamicVertexBufferHandle[4096]` | m_freeDynamicVertexBufferHandle
97244558 | (512) `bgfx::OcclusionQueryHandle[256]` | m_freeOcclusionQueryHandle
97245072 | (56) `bgfx::NonLocalAllocator` | m_dynIndexBufferAllocator
97245128 | (16388) `bx::HandleAllocT<4096>` | m_dynamicIndexBufferHandle
97261520 | (56) `bgfx::NonLocalAllocator` | m_dynVertexBufferAllocator
97261576 | (16388) `bx::HandleAllocT<4096>` | m_dynamicVertexBufferHandle
97277964 | (16388) `bx::HandleAllocT<4096>` | m_indexBufferHandle
97294352 | (260) `bx::HandleAllocT<64>` | m_vertexDeclHandle
97294612 | (16388) `bx::HandleAllocT<4096>` | m_vertexBufferHandle
97311000 | (16388) `bx::HandleAllocT<4096>` | m_shaderHandle
97327388 | (8196) `bx::HandleAllocT<2048>` | m_programHandle
97335584 | (16388) `bx::HandleAllocT<4096>` | m_textureHandle
97351972 | (16388) `bx::HandleAllocT<4096>` | m_shaderBufferHandle
97368360 | (516) `bx::HandleAllocT<128>` | m_frameBufferHandle
97368876 | (2052) `bx::HandleAllocT<512>` | m_uniformHandle
97370928 | (1028) `bx::HandleAllocT<256>` | m_occlusionQueryHandle
97371956 | (131076) `bx::HandleAllocT<32768>` | m_accelerationStructureBufferHandle
97503032 | (6152) `bx::HandleHashMapT<1024,unsigned int>` | m_uniformHashMap
97509184 | (12288) `bgfx::Context::UniformRef[512]` | m_uniformRef
97521472 | (49160) `bx::HandleHashMapT<8192,unsigned int>` | m_shaderHashMap
97570632 | (131072) `bgfx::Context::ShaderRef[4096]` | m_shaderRef
97701704 | (24584) `bx::HandleHashMapT<4096,unsigned int>` | m_programHashMap
97726288 | (12288) `bgfx::Context::ProgramRef[2048]` | m_programRef
97738576 | (163840) `bgfx::Context::TextureRef[4096]` | m_textureRef
97902416 | (163840) `bgfx::Context::ShaderBufferRef[4096]` | m_shaderBufferRef
98066256 | (3072) `bgfx::Context::FrameBufferRef[128]` | m_frameBufferRef
98069328 | (17288) `bgfx::VertexDeclRef` | m_declRef
98086616 | (512) `unsigned __int16[256]` | m_viewRemap
98087128 | (1024) `unsigned int[256]` | m_seq
98088192 | (65536) `bgfx::View[256]` | m_view
98153728 | (256) `float[16][4]` | m_clearColor
98153984 | (1) `unsigned __int8` | m_colorPaletteDirty
98153992 | (56) `bgfx::Init` | m_init
98154048 | (8) `__int64` | m_frameTimeLast
98154056 | (4) `unsigned int` | m_frames
98154060 | (4) `unsigned int` | m_debug
98154064 | (8) `__int64` | m_rtMemoryUsed
98154072 | (8) `__int64` | m_textureMemoryUsed
98154080 | (8) `__int64` | m_shaderBufferMemoryUsed
98154088 | (112) `bgfx::TextVideoMemBlitter` | m_textVideoMemBlitter
98154200 | (104) `bgfx::ClearQuad` | m_clearQuad
98154304 | (8) `bgfx::RendererContextI *` | m_renderCtx
98154312 | (8) `bgfx::RendererContextI *` | m_renderMain
98154320 | (8) `bgfx::RendererContextI *` | m_renderNoop
98154328 | (1) `bool` | m_rendererInitialized
98154329 | (1) `bool` | m_exit
98154330 | (1) `bool` | m_flipAfterRender
98154331 | (1) `bool` | m_singleThreaded
98154332 | (1) `bool` | m_flipped
98154368 | (2052) `bgfx::UpdateBatchT<256>` | m_textureUpdateBatch


### `bx::Semaphore`
Offset | Type | Name
-|-|-|-
0 | (128) `unsigned __int8[128]` | m_internal


### `bx::Mutex`
Offset | Type | Name
-|-|-|-
0 | (64) `unsigned __int8[64]` | m_internal


### `bx::Thread`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::Thread_vtbl *` | __vftable
16 | (64) `unsigned __int8[64]` | m_internal
80 | (8) `int (__fastcall *)(bx::Thread *, void *)` | m_fn
88 | (8) `void *` | m_userData
96 | (224) `bx::MpScUnboundedBlockingQueue<void>` | m_queue
320 | (128) `bx::Semaphore` | m_sem
448 | (4) `unsigned int` | m_stackSize
452 | (4) `int` | m_exitCode
456 | (1) `bool` | m_running


### `bx::MpScUnboundedBlockingQueue<void>`
Offset | Type | Name
-|-|-|-
0 | (96) `bx::MpScUnboundedQueueT<void>` | m_queue
96 | (128) `bx::Semaphore` | m_sem


### `bx::MpScUnboundedQueueT<void>`
Offset | Type | Name
-|-|-|-
0 | (64) `bx::Mutex` | m_write
64 | (32) `bx::SpScUnboundedQueueT<void>` | m_queue


### `bx::SpScUnboundedQueueT<void>`
Offset | Type | Name
-|-|-|-
0 | (32) `bx::SpScUnboundedQueue` | m_queue


### `bx::SpScUnboundedQueue`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::AllocatorI *` | m_allocator
8 | (8) `bx::SpScUnboundedQueue::Node *` | m_first
16 | (8) `bx::SpScUnboundedQueue::Node *` | m_divider
24 | (8) `bx::SpScUnboundedQueue::Node *` | m_last


### `bgfx::Frame`
Offset | Type | Name
-|-|-|-
0 | (512) `unsigned __int16[256]` | m_viewRemap
512 | (256) `float[16][4]` | m_colorPalette
768 | (65536) `bgfx::View[256]` | m_view
66304 | (1024) `int[256]` | m_occlusion
67328 | (524288) `unsigned __int64[65536]` | m_sortKeys
591616 | (131072) `unsigned __int16[65536]` | m_sortValues
722688 | (8388608) `bgfx::RenderItem[65536]` | m_renderItem
9111296 | (33554432) `bgfx::RenderBind[65536]` | m_renderItemBind
42665728 | (4100) `unsigned int[1025]` | m_blitKeys
42669888 | (65600) `bgfx::BlitItem[1025]` | m_blitItem
42735488 | (4718624) `bgfx::FrameCache` | m_frameCache
47454112 | (8) `bgfx::UniformBuffer **` | m_uniformBuffer
47454120 | (4) `unsigned int` | m_numRenderItems
47454124 | (2) `unsigned __int16` | m_numBlitItems
47454128 | (4) `unsigned int` | m_iboffset
47454132 | (4) `unsigned int` | m_vboffset
47454136 | (8) `bgfx::TransientIndexBuffer *` | m_transientIb
47454144 | (8) `bgfx::TransientVertexBuffer *` | m_transientVb
47454152 | (12) `bgfx::Resolution` | m_resolution
47454164 | (4) `unsigned int` | m_debug
47454168 | (262152) `bgfx::CommandBuffer` | m_cmdPre
47716320 | (262152) `bgfx::CommandBuffer` | m_cmdPost
47978472 | (8194) `bgfx::Frame::FreeHandle<bgfx::IndexBufferHandle,4096>` | m_freeIndexBuffer
47986666 | (130) `bgfx::Frame::FreeHandle<bgfx::VertexDeclHandle,64>` | m_freeVertexDecl
47986796 | (8194) `bgfx::Frame::FreeHandle<bgfx::VertexBufferHandle,4096>` | m_freeVertexBuffer
47994990 | (8194) `bgfx::Frame::FreeHandle<bgfx::ShaderHandle,4096>` | m_freeShader
48003184 | (4098) `bgfx::Frame::FreeHandle<bgfx::ProgramHandle,2048>` | m_freeProgram
48007282 | (8194) `bgfx::Frame::FreeHandle<bgfx::TextureHandle,4096>` | m_freeTexture
48015476 | (8194) `bgfx::Frame::FreeHandle<bgfx::ShaderBufferHandle,4096>` | m_freeShaderBuffer
48023670 | (258) `bgfx::Frame::FreeHandle<bgfx::FrameBufferHandle,128>` | m_freeFrameBuffer
48023928 | (1026) `bgfx::Frame::FreeHandle<bgfx::UniformHandle,512>` | m_freeUniform
48024954 | (65538) `bgfx::Frame::FreeHandle<bgfx::AccelerationStructureHandle,32768>` | m_freeAccelerationStructure
48090496 | (8) `bgfx::TextVideoMem *` | m_textVideoMem
48090504 | (216) `bgfx::Stats` | m_perfStats
48090720 | (71680) `bgfx::ViewStats[256]` | m_viewStats
48162400 | (8) `__int64` | m_waitSubmit
48162408 | (8) `__int64` | m_waitRender
48162416 | (536) `bgfx::RayTracingConfiguration` | m_rtConfig
48162952 | (1) `bool` | m_capture
48162953 | (1) `bool` | m_skipFlip


### `bgfx::View`
Offset | Type | Name
-|-|-|-
0 | (16) `bgfx::Clear` | m_clear
16 | (8) `bgfx::Rect` | m_rect
24 | (8) `bgfx::Rect` | m_scissor
32 | (64) `bgfx::Matrix4` | m_view
96 | (128) `bgfx::Matrix4[2]` | m_proj
224 | (2) `bgfx::FrameBufferHandle` | m_fbh
226 | (1) `unsigned __int8` | m_mode
227 | (1) `unsigned __int8` | m_flags


### `bgfx::Clear`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8[8]` | m_index
8 | (4) `float` | m_depth
12 | (1) `unsigned __int8` | m_stencil
14 | (2) `unsigned __int16` | m_flags


### `bgfx::RenderItem`
Offset | Type | Name
-|-|-|-
0 | (128) `bgfx::RenderDraw` | draw
1 | (64) `bgfx::RenderCompute` | compute


### `bgfx::RenderDraw`
Offset | Type | Name
-|-|-|-
0 | (32) `bgfx::Stream[4]` | m_stream
32 | (8) `unsigned __int64` | m_stateFlags
40 | (8) `unsigned __int64` | m_stencil
48 | (4) `unsigned int` | m_rgba
52 | (4) `unsigned int` | m_uniformBegin
56 | (4) `unsigned int` | m_uniformEnd
60 | (4) `unsigned int` | m_startMatrix
64 | (4) `unsigned int` | m_startIndex
68 | (4) `unsigned int` | m_numIndices
72 | (4) `unsigned int` | m_numVertices
76 | (4) `unsigned int` | m_instanceDataOffset
80 | (4) `unsigned int` | m_numInstances
84 | (2) `unsigned __int16` | m_instanceDataStride
86 | (2) `unsigned __int16` | m_startIndirect
88 | (2) `unsigned __int16` | m_numIndirect
90 | (2) `unsigned __int16` | m_numMatrices
92 | (2) `unsigned __int16` | m_scissor
94 | (1) `unsigned __int8` | m_submitFlags
95 | (1) `unsigned __int8` | m_streamMask
96 | (1) `unsigned __int8` | m_uniformIdx
100 | (4) `int` | m_biasConst
104 | (4) `float` | m_biasSlope
108 | (4) `float` | m_biasClamp
112 | (2) `bgfx::IndexBufferHandle` | m_indexBuffer
114 | (2) `bgfx::VertexBufferHandle` | m_instanceDataBuffer
116 | (2) `bgfx::IndirectBufferHandle` | m_indirectBuffer
118 | (2) `bgfx::OcclusionQueryHandle` | m_occlusionQuery


### `bgfx::Stream`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_startVertex
4 | (2) `bgfx::VertexBufferHandle` | m_handle
6 | (2) `bgfx::VertexDeclHandle` | m_decl


### `bgfx::OcclusionQueryHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::RenderCompute`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_uniformBegin
4 | (4) `unsigned int` | m_uniformEnd
8 | (4) `unsigned int` | m_startMatrix
12 | (2) `bgfx::IndirectBufferHandle` | m_indirectBuffer
16 | (4) `unsigned int` | m_numX
20 | (4) `unsigned int` | m_numY
24 | (4) `unsigned int` | m_numZ
28 | (2) `unsigned __int16` | m_startIndirect
30 | (2) `unsigned __int16` | m_numIndirect
32 | (2) `unsigned __int16` | m_numMatrices
34 | (1) `unsigned __int8` | m_submitFlags
35 | (1) `unsigned __int8` | m_uniformIdx
36 | (1) `bool` | m_isRayTracing


### `bgfx::RenderBind`
Offset | Type | Name
-|-|-|-
0 | (512) `bgfx::Binding[64]` | m_bind


### `bgfx::Binding`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | m_idx
2 | (1) `unsigned __int8` | m_type
4 | (4) `bgfx::Binding::<unnamed_type_m_un>` | m_un


### `bgfx::Binding::<unnamed_type_m_un>`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::Binding::<unnamed_type_m_un>::<unnamed_type_m_draw>` | m_draw
1 | (3) `bgfx::Binding::<unnamed_type_m_un>::<unnamed_type_m_compute>` | m_compute


### `bgfx::Binding::<unnamed_type_m_un>::<unnamed_type_m_draw>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_textureFlags


### `bgfx::Binding::<unnamed_type_m_un>::<unnamed_type_m_compute>`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | m_format
1 | (1) `unsigned __int8` | m_access
2 | (1) `unsigned __int8` | m_mip


### `bgfx::BlitItem`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | m_srcX
2 | (2) `unsigned __int16` | m_srcY
4 | (2) `unsigned __int16` | m_srcZ
6 | (2) `unsigned __int16` | m_dstX
8 | (2) `unsigned __int16` | m_dstY
10 | (2) `unsigned __int16` | m_dstZ
12 | (2) `unsigned __int16` | m_width
14 | (2) `unsigned __int16` | m_height
16 | (2) `unsigned __int16` | m_depth
18 | (1) `unsigned __int8` | m_srcMip
19 | (1) `unsigned __int8` | m_dstMip
20 | (2) `bgfx::TextureHandle` | m_src
22 | (2) `bgfx::TextureHandle` | m_dst


### `bgfx::FrameCache`
Offset | Type | Name
-|-|-|-
0 | (4194320) `bgfx::MatrixCache` | m_matrixCache
4194320 | (524292) `bgfx::RectCache` | m_rectCache


### `bgfx::MatrixCache`
Offset | Type | Name
-|-|-|-
0 | (4194304) `bgfx::Matrix4[65536]` | m_cache
4194304 | (4) `unsigned int` | m_num


### `bgfx::RectCache`
Offset | Type | Name
-|-|-|-
0 | (524288) `bgfx::Rect[65536]` | m_cache
524288 | (4) `unsigned int` | m_num


### `bgfx::CommandBuffer`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_pos
4 | (4) `unsigned int` | m_size
8 | (262144) `unsigned __int8[262144]` | m_buffer


### `bgfx::Frame::FreeHandle<bgfx::IndexBufferHandle,4096>`
Offset | Type | Name
-|-|-|-
0 | (8192) `bgfx::IndexBufferHandle[4096]` | m_queue
8192 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::VertexDeclHandle,64>`
Offset | Type | Name
-|-|-|-
0 | (128) `bgfx::VertexDeclHandle[64]` | m_queue
128 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::VertexBufferHandle,4096>`
Offset | Type | Name
-|-|-|-
0 | (8192) `bgfx::VertexBufferHandle[4096]` | m_queue
8192 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::ShaderHandle,4096>`
Offset | Type | Name
-|-|-|-
0 | (8192) `bgfx::ShaderHandle[4096]` | m_queue
8192 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::ProgramHandle,2048>`
Offset | Type | Name
-|-|-|-
0 | (4096) `bgfx::ProgramHandle[2048]` | m_queue
4096 | (2) `unsigned __int16` | m_num


### `bgfx::ProgramHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | idx


### `bgfx::Frame::FreeHandle<bgfx::TextureHandle,4096>`
Offset | Type | Name
-|-|-|-
0 | (8192) `bgfx::TextureHandle[4096]` | m_queue
8192 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::ShaderBufferHandle,4096>`
Offset | Type | Name
-|-|-|-
0 | (8192) `bgfx::ShaderBufferHandle[4096]` | m_queue
8192 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::FrameBufferHandle,128>`
Offset | Type | Name
-|-|-|-
0 | (256) `bgfx::FrameBufferHandle[128]` | m_queue
256 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::UniformHandle,512>`
Offset | Type | Name
-|-|-|-
0 | (1024) `bgfx::UniformHandle[512]` | m_queue
1024 | (2) `unsigned __int16` | m_num


### `bgfx::Frame::FreeHandle<bgfx::AccelerationStructureHandle,32768>`
Offset | Type | Name
-|-|-|-
0 | (65536) `bgfx::AccelerationStructureHandle[32768]` | m_queue
65536 | (2) `unsigned __int16` | m_num


### `bgfx::Stats`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | cpuTimeFrame
8 | (8) `__int64` | cpuTimeBegin
16 | (8) `__int64` | cpuTimeEnd
24 | (8) `__int64` | cpuTimerFreq
32 | (8) `__int64` | gpuTimeBegin
40 | (8) `__int64` | gpuTimeEnd
48 | (8) `__int64` | gpuTimerFreq
56 | (8) `__int64` | waitRender
64 | (8) `__int64` | waitSubmit
72 | (4) `unsigned int` | numDraw
76 | (4) `unsigned int` | numCompute
80 | (4) `unsigned int` | maxGpuLatency
84 | (2) `unsigned __int16` | numDynamicIndexBuffers
86 | (2) `unsigned __int16` | numDynamicVertexBuffers
88 | (2) `unsigned __int16` | numFrameBuffers
90 | (2) `unsigned __int16` | numIndexBuffers
92 | (2) `unsigned __int16` | numOcclusionQueries
94 | (2) `unsigned __int16` | numPrograms
96 | (2) `unsigned __int16` | numShaders
98 | (2) `unsigned __int16` | numTextures
100 | (2) `unsigned __int16` | numUniforms
102 | (2) `unsigned __int16` | numVertexBuffers
104 | (2) `unsigned __int16` | numVertexDecls
112 | (8) `__int64` | textureMemoryUsed
120 | (8) `__int64` | rtMemoryUsed
128 | (4) `int` | transientVbUsed
132 | (4) `int` | transientIbUsed
136 | (20) `unsigned int[5]` | numPrims
160 | (8) `unsigned __int64` | gpuMemoryMax
168 | (8) `unsigned __int64` | gpuMemoryUsed
176 | (2) `unsigned __int16` | width
178 | (2) `unsigned __int16` | height
180 | (2) `unsigned __int16` | textWidth
182 | (2) `unsigned __int16` | textHeight
184 | (2) `unsigned __int16` | numViews
192 | (8) `bgfx::ViewStats *` | viewStats
200 | (1) `unsigned __int8` | numEncoders
208 | (8) `bgfx::EncoderStats *` | encoderStats


### `bgfx::ViewStats`
Offset | Type | Name
-|-|-|-
0 | (256) `char[256]` | name
256 | (2) `unsigned __int16` | view
264 | (8) `__int64` | cpuTimeElapsed
272 | (8) `__int64` | gpuTimeElapsed


### `bgfx::IndexBuffer`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_size


### `bgfx::VertexBuffer`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_size
4 | (2) `unsigned __int16` | m_stride


### `bgfx::DynamicIndexBuffer`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::IndexBufferHandle` | m_handle
4 | (4) `unsigned int` | m_offset
8 | (4) `unsigned int` | m_size
12 | (4) `unsigned int` | m_startIndex
16 | (2) `unsigned __int16` | m_flags


### `bgfx::DynamicVertexBuffer`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::VertexBufferHandle` | m_handle
4 | (4) `unsigned int` | m_offset
8 | (4) `unsigned int` | m_size
12 | (4) `unsigned int` | m_startVertex
16 | (4) `unsigned int` | m_numVertices
20 | (2) `unsigned __int16` | m_stride
22 | (2) `bgfx::VertexDeclHandle` | m_decl
24 | (2) `unsigned __int16` | m_flags


### `bgfx::NonLocalAllocator`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::list<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>` | m_free
24 | (32) `tinystl::unordered_map<unsigned __int64,unsigned int,bgfx::TinyStlAllocator>` | m_used


### `bx::HandleAllocT<4096>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (16384) `unsigned __int16[8192]` | m_padding


### `bx::HandleAlloc`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | m_numHandles
2 | (2) `unsigned __int16` | m_maxHandles


### `bx::HandleAllocT<64>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (256) `unsigned __int16[128]` | m_padding


### `bx::HandleAllocT<2048>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (8192) `unsigned __int16[4096]` | m_padding


### `bx::HandleAllocT<128>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (512) `unsigned __int16[256]` | m_padding


### `bx::HandleAllocT<512>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (2048) `unsigned __int16[1024]` | m_padding


### `bx::HandleAllocT<256>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (1024) `unsigned __int16[512]` | m_padding


### `bx::HandleAllocT<32768>`
Offset | Type | Name
-|-|-|-
0 | (4) `bx::HandleAlloc` | baseclass_0
4 | (131072) `unsigned __int16[65536]` | m_padding


### `bgfx::Context::UniformRef`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::StringT<&bgfx::g_allocator>` | m_name
16 | (4) `_BYTE[4]` | m_type
20 | (2) `unsigned __int16` | m_num
22 | (2) `__int16` | m_refCount


### `bx::StringT<&bgfx::g_allocator>`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::StringView` | baseclass_0


### `bx::HandleHashMapT<8192,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_maxCapacity
4 | (4) `unsigned int` | m_numElements
8 | (32768) `unsigned int[8192]` | m_key
32776 | (16384) `unsigned __int16[8192]` | m_handle


### `bgfx::Context::ShaderRef`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::UniformHandle *` | m_uniforms
8 | (16) `bx::StringT<&bgfx::g_allocator>` | m_name
24 | (4) `unsigned int` | m_hash
28 | (2) `__int16` | m_refCount
30 | (2) `unsigned __int16` | m_num


### `bx::HandleHashMapT<4096,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_maxCapacity
4 | (4) `unsigned int` | m_numElements
8 | (16384) `unsigned int[4096]` | m_key
16392 | (8192) `unsigned __int16[4096]` | m_handle


### `bgfx::Context::ProgramRef`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::ShaderHandle` | m_vsh
2 | (2) `bgfx::ShaderHandle` | m_fsh
4 | (2) `__int16` | m_refCount


### `bgfx::Context::TextureRef`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::StringT<&bgfx::g_allocator>` | m_name
16 | (8) `void *` | m_ptr
24 | (4) `unsigned int` | m_storageSize
28 | (2) `__int16` | m_refCount
30 | (1) `unsigned __int8` | m_bbRatio
31 | (1) `unsigned __int8` | m_format
32 | (1) `unsigned __int8` | m_numMips
34 | (2) `unsigned __int16` | m_numLayers
36 | (1) `bool` | m_owned
37 | (1) `bool` | m_immutable
38 | (1) `bool` | m_rt


### `bgfx::Context::ShaderBufferRef`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::StringT<&bgfx::g_allocator>` | m_name
16 | (8) `void *` | m_ptr
24 | (4) `unsigned int` | m_stride
28 | (4) `unsigned int` | m_count
32 | (2) `__int16` | m_refCount


### `bgfx::Context::FrameBufferRef`
Offset | Type | Name
-|-|-|-
0 | (16) `bgfx::Context::FrameBufferRef::un` | un
16 | (1) `bool` | m_window


### `bgfx::Context::FrameBufferRef::un`
Offset | Type | Name
-|-|-|-
0 | (16) `bgfx::TextureHandle[8]` | m_th
1 | (8) `void *` | m_nwh


### `bgfx::VertexDeclRef`
Offset | Type | Name
-|-|-|-
0 | (776) `bx::HandleHashMapT<128,unsigned int>` | m_vertexDeclMap
776 | (128) `unsigned __int16[64]` | m_vertexDeclRef
904 | (8192) `bgfx::VertexDeclHandle[4096]` | m_vertexBufferRef
9096 | (8192) `bgfx::VertexDeclHandle[4096]` | m_dynamicVertexBufferRef


### `bx::HandleHashMapT<128,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_maxCapacity
4 | (4) `unsigned int` | m_numElements
8 | (512) `unsigned int[128]` | m_key
520 | (256) `unsigned __int16[128]` | m_handle


### `bgfx::TextVideoMemBlitter`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::TextureHandle` | m_texture
8 | (8) `bgfx::TransientVertexBuffer *` | m_vb
16 | (8) `bgfx::TransientIndexBuffer *` | m_ib
24 | (80) `bgfx::VertexDecl` | m_decl
104 | (2) `bgfx::ProgramHandle` | m_program


### `bgfx::ClearQuad`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::TransientVertexBuffer *` | m_vb
8 | (80) `bgfx::VertexDecl` | m_decl
88 | (16) `bgfx::ProgramHandle[8]` | m_program


### `bgfx::UpdateBatchT<256>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_num
4 | (1024) `unsigned int[256]` | m_keys
1028 | (1024) `unsigned int[256]` | m_values


### `bx::MemoryWriter`
Offset | Type | Name
-|-|-|-
0 | (16) `bx::WriterSeekerI` | baseclass_0
16 | (8) `bx::MemoryBlockI *` | m_memBlock
24 | (8) `unsigned __int8 *` | m_data
32 | (8) `__int64` | m_pos
40 | (8) `__int64` | m_top
48 | (8) `__int64` | m_size


### `bx::WriterSeekerI`
Offset | Type | Name
-|-|-|-
0 | (8) `bx::WriterI` | baseclass_0
8 | (8) `bx::SeekerI` | baseclass_8


### `bx::HashMurmur2A`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_hash
4 | (4) `unsigned int` | m_tail
8 | (4) `unsigned int` | m_count
12 | (4) `unsigned int` | m_size


### `bgfx::NvMemoryInfoV2`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | version
4 | (4) `unsigned int` | dedicatedVideoMemory
8 | (4) `unsigned int` | availableDedicatedVideoMemory
12 | (4) `unsigned int` | systemVideoMemory
16 | (4) `unsigned int` | sharedSystemMemory
20 | (4) `unsigned int` | curAvailableDedicatedVideoMemory


### `bgfx::d3d11::AGSDriverVersionInfo`
Offset | Type | Name
-|-|-|-
0 | (256) `char[256]` | strDriverVersion
256 | (256) `char[256]` | strCatalystVersion
512 | (256) `char[256]` | strCatalystWebLink


### `bgfx::DxbcShader`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | version
8 | (24) `tinystl::vector<unsigned char,bgfx::TinyStlAllocator>` | byteCode
32 | (1) `bool` | shex
33 | (1) `bool` | aon9


### `bimg::ImageMip`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | m_format
4 | (4) `unsigned int` | m_width
8 | (4) `unsigned int` | m_height
12 | (4) `unsigned int` | m_depth
16 | (4) `unsigned int` | m_blockSize
20 | (4) `unsigned int` | m_size
24 | (1) `unsigned __int8` | m_bpp
25 | (1) `bool` | m_hasAlpha
32 | (8) `const unsigned __int8 *` | m_data


### `bgfx::SwapChainDesc`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | width
4 | (4) `unsigned int` | height
8 | (4) `DXGI_FORMAT` | format
12 | (1) `bool` | stereo
16 | (8) `DXGI_SAMPLE_DESC` | sampleDesc
24 | (4) `unsigned int` | bufferUsage
28 | (4) `unsigned int` | bufferCount
32 | (4) `DXGI_SCALING` | scaling
36 | (4) `DXGI_SWAP_EFFECT` | swapEffect
40 | (4) `DXGI_ALPHA_MODE` | alphaMode
44 | (4) `unsigned int` | flags
48 | (8) `void *` | nwh
56 | (8) `void *` | ndt
64 | (1) `bool` | windowed


### `bgfx::BlitState`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::Frame *` | m_frame
8 | (4) `bgfx::BlitKey` | m_key
12 | (2) `unsigned __int16` | m_item


### `bgfx::BlitKey`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | m_item
2 | (2) `unsigned __int16` | m_view


### `bgfx::Profiler<bgfx::d3d11::TimerQueryD3D11>`
Offset | Type | Name
-|-|-|-
0 | (8) `const char (*)[256]` | m_viewName
8 | (8) `bgfx::Frame *` | m_frame
16 | (8) `bgfx::d3d11::TimerQueryD3D11 *` | m_gpuTimer
24 | (4) `unsigned int` | m_queryIdx
28 | (2) `unsigned __int16` | m_numViews
30 | (1) `bool` | m_enabled


### `bgfx::vk::VkSampler`
Offset | Type | Name
-|-|-|-
0 | (8) `struct VkSampler_T *` | vk


### `bgfx::d3d12::ResourceCreate`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | m_ptr
8 | (4) `D3D12_RESOURCE_STATES` | m_initialState
16 | (8) `unsigned __int64` | m_gpuVA


### `bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> >::Location`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_offset
4 | (4) `unsigned int` | m_size
8 | (32) `bgfx::d3d12::StagingBufferD3D12` | m_buffer
40 | (8) `unsigned __int64` | m_gpuAddr
48 | (8) `void *` | m_cpuAddr


### `bgfx::d3d12::StagingBufferD3D12`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | m_upload
8 | (8) `unsigned __int64` | m_gpuVA
16 | (8) `unsigned __int8 *` | m_data
24 | (4) `unsigned int` | m_size
28 | (4) `bgfx::d3d12::HeapProperty::Enum` | m_properties


### `bgfx::DxbcContext`
Offset | Type | Name
-|-|-|-
0 | (32) `bgfx::DxbcContext::Header` | header
32 | (32) `bgfx::DxbcSignature` | inputSignature
64 | (32) `bgfx::DxbcSignature` | outputSignature
96 | (40) `bgfx::DxbcShader` | shader
136 | (24) `tinystl::vector<unsigned char,bgfx::TinyStlAllocator>` | debugInfo
160 | (4) `unsigned int` | debugInfoFormat


### `bgfx::DxbcContext::Header`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | magic
4 | (16) `unsigned __int8[16]` | hash
20 | (4) `unsigned int` | version
24 | (4) `unsigned int` | size
28 | (4) `unsigned int` | numChunks


### `bgfx::DxbcSignature`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | key
8 | (24) `tinystl::vector<bgfx::DxbcSignature::Element,bgfx::TinyStlAllocator>` | elements


### `bgfx::d3d12::Bind`
Offset | Type | Name
-|-|-|-
0 | (8) `D3D12_GPU_DESCRIPTOR_HANDLE` | m_srvHandle
8 | (2) `unsigned __int16` | m_samplerStateIdx


### `bgfx::d3d12::UniformBufferInstance`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<bgfx::UniformBufferView>` | m_vsCb
24 | (24) `std::optional<bgfx::UniformBufferView>` | m_fsCb


### `bgfx::UniformBufferView`
Offset | Type | Name
-|-|-|-
0 | (8) `const bgfx::UniformBuffer *` | m_uniforms
8 | (4) `unsigned int` | m_size
12 | (4) `unsigned int` | m_pos


### `bgfx::d3d12::ConstantBufferDataContainer`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::d3d12::ConstantBufferScratch *` | m_scratch
8 | (8) `unsigned __int64` | m_currentOffset
16 | (4) `unsigned int` | m_cbSize
24 | (8) `bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> > *` | m_uploadBuffer
32 | (56) `bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> >::Location` | m_cbData
88 | (8) `unsigned __int64` | m_vsDataSize
96 | (8) `unsigned __int64` | m_fsDataSize


### `bgfx::FencedRingBuffer<bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> >::RingBufferResourceAllocator,0>::ScopedAllocation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> >::RingBufferResourceAllocator::Buffer>` | m_buffer
16 | (8) `const unsigned __int64` | m_offset
24 | (8) `const unsigned __int64` | m_size
32 | (8) `const unsigned __int64` | m_alignmentPrefixSize
40 | (8) `const unsigned __int64` | m_fenceValue


### `bgfx::FencedRingBuffer<bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<2> >::RingBufferResourceAllocator,0>::LinearAllocation`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_offsetPrefix
8 | (8) `unsigned __int64` | m_dataOffset


### `bgfx::d3d12rtx::D3D12RTProgram`
Offset | Type | Name
-|-|-|-
0 | (24) `bgfx::d3d12rtx::D3D12RTShaderInfo` | info
24 | (8) `IDxcBlob *` | blob
32 | (32) `D3D12_DXIL_LIBRARY_DESC` | dxilLibDesc
64 | (24) `D3D12_EXPORT_DESC` | exportDesc
88 | (16) `D3D12_STATE_SUBOBJECT` | subobject
104 | (32) `std::wstring` | exportName


### `bgfx::d3d12rtx::D3D12RTShaderInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const wchar_t *` | filename
8 | (8) `const wchar_t *` | entryPoint
16 | (8) `const wchar_t *` | targetProfile


### `bgfx::d3d12rtx::AdaptiveDenoiserLightSortKey`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | idx
4 | (4) `float` | distanceSquared


### `bgfx::d3d12rtx::RendererContextD3D12RTX::BlasCompactionContext`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::d3d12rtx::RTBlasCompactionState` | state
4 | (2) `bgfx::AccelerationStructureHandle` | hBuffer
8 | (4) `unsigned int` | beforeSize
12 | (4) `unsigned int` | afterSize
16 | (4) `unsigned int` | frameCountOfLastUpdate
20 | (4) `int` | sizeRequestIndex


### `bgfx::d3d12rtx::RendererContextD3D12RTX::BlasBuildContext`
Offset | Type | Name
-|-|-|-
0 | (56) `D3D12_RAYTRACING_GEOMETRY_DESC` | desc
56 | (2) `bgfx::AccelerationStructureHandle` | hBuffer
60 | (4) `D3D12_RAYTRACING_ACCELERATION_STRUCTURE_BUILD_FLAGS` | flags
64 | (4) `unsigned int` | scratchSize


### `bgfx::RingBuffer<bgfx::d3d12::StagingBufferD3D12,unsigned __int64,void *,bgfx::d3d12::RingBufferAllocator<0> >::Location`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | m_offset
4 | (4) `unsigned int` | m_size
8 | (32) `bgfx::d3d12::StagingBufferD3D12` | m_buffer
40 | (8) `unsigned __int64` | m_gpuAddr
48 | (8) `void *` | m_cpuAddr


### `bgfx::d3d12rtx::RendererContextD3D12RTX::GlobalDescriptorTableTextureTransition`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::d3d12rtx::RTGlobalDescriptorTable` | m_whichEntry
4 | (4) `D3D12_RESOURCE_STATES` | m_assumedPreviousState


### `bgfx::d3d12rtx::RendererContextD3D12RTX::float3x4`
Offset | Type | Name
-|-|-|-
0 | (48) `float[3][4]` | data


### `bgfx::gl::FrameBufferGL`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::gl::SwapChainGL *` | m_swapChain
8 | (8) `unsigned int[2]` | m_fbo
16 | (4) `unsigned int` | m_width
20 | (4) `unsigned int` | m_height
24 | (2) `unsigned __int16` | m_denseIdx
26 | (1) `unsigned __int8` | m_num
27 | (1) `unsigned __int8` | m_numTh
28 | (1) `bool` | m_needPresent
30 | (48) `bgfx::Attachment[8]` | m_attachment


### `bgfx::vk::VkPipeline`
Offset | Type | Name
-|-|-|-
0 | (8) `struct VkPipeline_T *` | vk


### `bgfx::DxbcSubOperand`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::DxbcOperandType::Enum` | type
4 | (1) `unsigned __int8` | mode
5 | (1) `unsigned __int8` | modeBits
6 | (1) `unsigned __int8` | num
7 | (1) `unsigned __int8` | numAddrModes
8 | (1) `unsigned __int8` | addrMode
12 | (4) `unsigned int` | regIndex


### `bgfx::DxbcOperand`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::DxbcOperandType::Enum` | type
4 | (4) `bgfx::DxbcOperandMode::Enum` | mode
8 | (1) `unsigned __int8` | modeBits
9 | (1) `unsigned __int8` | num
12 | (4) `_BYTE[4]` | modifier
16 | (1) `unsigned __int8` | numAddrModes
17 | (3) `unsigned __int8[3]` | addrMode
20 | (12) `unsigned int[3]` | regIndex
32 | (48) `bgfx::DxbcSubOperand[3]` | subOperand
80 | (32) `bgfx::DxbcOperand::<unnamed_type_un>` | un


### `bgfx::DxbcOperand::<unnamed_type_un>`
Offset | Type | Name
-|-|-|-
0 | (16) `unsigned int[4]` | imm32
1 | (32) `unsigned __int64[4]` | imm64


### `bgfx::DxbcInstruction`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::DxbcOpcode::Enum` | opcode
4 | (12) `unsigned int[3]` | value
16 | (4) `unsigned int` | length
20 | (1) `unsigned __int8` | numOperands
24 | (12) `bgfx::DxbcInstruction::ExtendedType::Enum[3]` | extended
36 | (4) `_BYTE[4]` | srv
40 | (1) `unsigned __int8` | samples
44 | (4) `_BYTE[4]` | interpolation
48 | (1) `bool` | shadow
49 | (1) `bool` | mono
50 | (1) `bool` | allowRefactoring
51 | (1) `bool` | fp64
52 | (1) `bool` | earlyDepth
53 | (1) `bool` | enableBuffers
54 | (1) `bool` | skipOptimization
55 | (1) `bool` | enableMinPrecision
56 | (1) `bool` | enableDoubleExtensions
57 | (1) `bool` | enableShaderExtensions
58 | (1) `bool` | threadsInGroup
59 | (1) `bool` | sharedMemory
60 | (1) `bool` | uavGroup
61 | (1) `bool` | uavGlobal
64 | (4) `bgfx::DxbcResourceReturnType::Enum` | retType
68 | (1) `bool` | saturate
69 | (1) `unsigned __int8` | testNZ
70 | (3) `unsigned __int8[3]` | sampleOffsets
73 | (1) `unsigned __int8` | resourceTarget
74 | (1) `unsigned __int8` | resourceStride
76 | (16) `bgfx::DxbcResourceReturnType::Enum[4]` | resourceReturnTypes
96 | (672) `bgfx::DxbcOperand[6]` | operand
768 | (4) `bgfx::DxbcCustomDataClass::Enum` | customDataClass
776 | (24) `tinystl::vector<unsigned int,bgfx::TinyStlAllocator>` | customData


### `bimg::BitReader`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int8 *` | m_data
8 | (2) `unsigned __int16` | m_bitPos


### `bgfx::d3d12::ConstantBufferScratch`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | m_data


### `BlockActorDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (12) `NetworkBlockPosition` | mPos
56 | (24) `CompoundTag` | mData


### `bgfx::Profiler<bgfx::gl::TimerQueryGL>`
Offset | Type | Name
-|-|-|-
0 | (8) `const char (*)[256]` | m_viewName
8 | (8) `bgfx::Frame *` | m_frame
16 | (8) `bgfx::gl::TimerQueryGL *` | m_gpuTimer
24 | (4) `unsigned int` | m_queryIdx
28 | (2) `unsigned __int16` | m_numViews
30 | (1) `bool` | m_enabled


### `Bedrock::JSONObject::Document`
Offset | Type | Name
-|-|-|-
0 | (32) `Bedrock::JSONObject::DocumentOptions` | mOptions
32 | (16) `Bedrock::JSONObject::ParseResult` | mParseResult
48 | (8) `Bedrock::Memory::IMemoryAllocator *` | mAllocator
56 | (8) `Bedrock::JSONObject::MemoryPage *` | mPageHead
64 | (8) `Bedrock::JSONObject::Node *` | mRootNode
72 | (8) `Bedrock::JSONObject::Document::AllocatedResources *` | mAllocatedResources
80 | (4) `unsigned int` | mPageCount


### `Bedrock::JSONObject::DocumentOptions`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | mFixedBlock
8 | (8) `Bedrock::Memory::IMemoryAllocator *` | mAllocator
16 | (8) `char *` | mInSituBuffer
24 | (4) `unsigned int` | mFixedBlockLength
28 | (1) `bool` | mAllowDynamicAllocation


### `Bedrock::JSONObject::ParseResult`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mErrorDescription
8 | (4) `unsigned int` | mOffset
12 | (4) `int` | mErrorCode


### `Bedrock::Threading::PrioritizeDefault`
```
struct __cppobj Bedrock::Threading::PrioritizeDefault
{
  std::mutex mLock;
  std::hash<std::thread::id> mThreadHasher;
  const unsigned __int64 mNoThreadId;
  unsigned __int64 mOwnerThread;
  unsigned __int64 mReadCount;
  std::condition_variable mWriteQueue;
  std::condition_variable mReadQueue;
};

```

### `Bedrock::Threading::PrioritizeUniqueOwnership`
```
struct __cppobj Bedrock::Threading::PrioritizeUniqueOwnership
{
  std::mutex mLock;
  std::hash<std::thread::id> mThreadHasher;
  const unsigned __int64 mNoThreadId;
  unsigned __int64 mOwnerThread;
  unsigned __int64 mWriteCount;
  unsigned __int64 mReadCount;
  std::condition_variable mPriorityWriteQueue;
  std::condition_variable mWriteQueue;
  std::condition_variable mReadQueue;
};

```

### `BlockSource_vtbl`
```
struct /*VFT*/ BlockSource_vtbl
{
  void (__fastcall *~BlockSource)(BlockSource *this);
};

```

### `BlockSourceListener`
```
struct __cppobj BlockSourceListener
{
  BlockSourceListener_vtbl *__vftable /*VFT*/;
};

```

### `Block_vtbl`
```
struct /*VFT*/ Block_vtbl
{
  void (__fastcall *~Block)(Block *this);
  BlockRenderLayer (__fastcall *getRenderLayer)(Block *this);
};

```

### `BlockLegacy`
```
struct __cppobj BlockLegacy
{
  BlockLegacy_vtbl *__vftable /*VFT*/;
  std::string mDescriptionId;
  HashedString mRawNameId;
  std::string mNamespace;
  HashedString mFullName;
  bool mFancy;
  BlockRenderLayer mRenderLayer;
  bool mRenderLayerCanRenderAsOpaque;
  __declspec(align(8)) _BYTE mProperties[8];
  BlockActorType mBlockEntityType;
  bool mAnimatedTexture;
  float mBrightnessGamma;
  float mThickness;
  bool mCanSlide;
  bool mCanInstatick;
  bool mIsInteraction;
  float mGravity;
  const Material *mMaterial;
  bool mHeavy;
  float mParticleQuantityScalar;
  CreativeItemCategory mCreativeCategory;
  std::string mCreativeGroup;
  bool mAllowsRunes;
  bool mCanBeBrokenFromFalling;
  bool mSolid;
  bool mPushesOutItems;
  bool mIgnoreBlockForInsideCubeRenderer;
  bool mIsTrapdoor;
  bool mIsDoor;
  float mTranslucency;
  bool mShouldRandomTick;
  bool mShouldRandomTickExtraLayer;
  bool mIsMobPiece;
  bool mCanBeExtraBlock;
  bool mCanPropagateBrightness;
  Brightness mLightBlock;
  Brightness mLightEmission;
  int mFlameOdds;
  int mBurnOdds;
  float mDestroySpeed;
  float mExplosionResistance;
  mce::Color mMapColor;
  float mFriction;
  NewBlockID mID;
  BaseGameVersion mMinRequiredBaseGameVersion;
  bool mIsVanilla;
  std::vector<HashedString> mTags;
  bool mTickToScript;
  bool mSendNeighborChangedToScript;
  bool mFireResistant;
  std::unordered_map<std::string,DefinitionEvent> mEventHandlers;
  AABB mVisualShape;
  unsigned int mBitsUsed;
  unsigned int mTotalBitsUsed;
  std::map<unsigned __int64,ItemStateInstance> mStates;
  std::unordered_map<HashedString,unsigned __int64> mStateNameMap;
  unsigned __int64 mCreativeEnumState;
  std::vector<std::unique_ptr<Block>> mBlockPermutations;
  const Block *mDefaultState;
  Core::Cache<unsigned short,Block const *,Block const *> mLegacyDataLookupTable;
  OwnerPtrT<EntityRefTraits> mEntity;
  std::unique_ptr<BlockStateGroup> mBlockStateGroup;
  HashedString mHashedFullName;
};

```

### `ByteTag_vtbl`
```
struct /*VFT*/ ByteTag_vtbl
{
  void (__fastcall *~Tag)(Tag *this);
  void (__fastcall *deleteChildren)(Tag *this);
  void (__fastcall *write)(Tag *this, IDataOutput *);
  void (__fastcall *load)(Tag *this, IDataInput *);
  void (__fastcall *writeScriptData)(Tag *this, IDataOutput *);
  void (__fastcall *loadScriptData)(Tag *this, IDataInput *);
  std::string *(__fastcall *toString)(Tag *this, std::string *result);
  Tag::Type (__fastcall *getId)(Tag *this);
  bool (__fastcall *equals)(Tag *this, const Tag *);
  void (__fastcall *print)(Tag *this, const std::string *, PrintStream *);
  void (__fastcall *print)(Tag *this, PrintStream *);
  std::unique_ptr<Tag> *(__fastcall *copy)(Tag *this, std::unique_ptr<Tag> *result);
  unsigned __int64 (__fastcall *hash)(Tag *this);
};

```

### `ByteArrayTag_vtbl`
```
struct /*VFT*/ ByteArrayTag_vtbl
{
  void (__fastcall *~Tag)(Tag *this);
  void (__fastcall *deleteChildren)(Tag *this);
  void (__fastcall *write)(Tag *this, IDataOutput *);
  void (__fastcall *load)(Tag *this, IDataInput *);
  void (__fastcall *writeScriptData)(Tag *this, IDataOutput *);
  void (__fastcall *loadScriptData)(Tag *this, IDataInput *);
  std::string *(__fastcall *toString)(Tag *this, std::string *result);
  Tag::Type (__fastcall *getId)(Tag *this);
  bool (__fastcall *equals)(Tag *this, const Tag *);
  void (__fastcall *print)(Tag *this, const std::string *, PrintStream *);
  void (__fastcall *print)(Tag *this, PrintStream *);
  std::unique_ptr<Tag> *(__fastcall *copy)(Tag *this, std::unique_ptr<Tag> *result);
  unsigned __int64 (__fastcall *hash)(Tag *this);
};

```

### `BaseActorRenderContext_vtbl`
```
struct /*VFT*/ BaseActorRenderContext_vtbl
{
  void (__fastcall *~BaseActorRenderContext)(BaseActorRenderContext *this);
};

```

### `BinaryStream_vtbl`
```
struct /*VFT*/ BinaryStream_vtbl
{
  void (__fastcall *~ReadOnlyBinaryStream)(ReadOnlyBinaryStream *this);
  bool (__fastcall *read)(ReadOnlyBinaryStream *this, void *, unsigned __int64);
};

```

### `BackgroundTaskBase`
```
struct __cppobj BackgroundTaskBase
{
  BackgroundTaskBase_vtbl *__vftable /*VFT*/;
  const bool mIsAsync;
  ITaskGroup *mGroup;
  BackgroundTaskBase *mPrevTask;
  std::shared_ptr<BackgroundTaskBase> mNextTask;
  int mPriority;
  std::thread::id mAffinity;
  const int mBackDownPriorityAmount;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mStartAfterTime;
};

```

### `BackgroundTaskBase_vtbl`
```
struct /*VFT*/ BackgroundTaskBase_vtbl
{
  void (__fastcall *~BackgroundTaskBase)(BackgroundTaskBase *this);
  void (__fastcall *cancel)(BackgroundTaskBase *this);
  bool (__fastcall *isReady)(BackgroundTaskBase *this);
  TaskRunResult (__fastcall *run)(BackgroundTaskBase *this, const ITaskExecutionContext *);
};

```

### `Bedrock::EnableNonOwnerReferences::ControlBlock`
```
struct __cppobj Bedrock::EnableNonOwnerReferences::ControlBlock
{
  Bedrock::EnableNonOwnerReferences *mPtr;
};

```

### `Bedrock::NonOwnerPointer<Scheduler>`
```
struct __cppobj Bedrock::NonOwnerPointer<Scheduler>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `BatchedNetworkPeer`
```
struct __cppobj __declspec(align(8)) BatchedNetworkPeer : NetworkPeer
{
  BinaryStream mOutgoingData;
  unsigned __int64 mCompressibleBytes;
  std::string mIncomingDataBuffer;
  std::unique_ptr<ReadOnlyBinaryStream> mIncomingData;
  std::unique_ptr<TaskGroup> mTaskGroup;
  SPSCQueue<BatchedNetworkPeer::DataCallback,512> mSendQueue;
  std::atomic<bool> mTaskRunning;
  std::atomic<unsigned __int64> mQueuedPackets;
  unsigned __int64 mSentPackets;
  unsigned __int16 mCompressionThreshold;
  bool mAsyncEnabled;
};

```

### `BatchedNetworkPeer_vtbl`
```
struct /*VFT*/ BatchedNetworkPeer_vtbl
{
  void (__fastcall *~NetworkPeer)(NetworkPeer *this);
  void (__fastcall *sendPacket)(NetworkPeer *this, const std::string *, NetworkPeer::Reliability, int, unsigned __int16, Compressibility);
  NetworkPeer::DataStatus (__fastcall *receivePacket)(NetworkPeer *this, std::string *);
  NetworkPeer::NetworkStatus *(__fastcall *getNetworkStatus)(NetworkPeer *this, NetworkPeer::NetworkStatus *result);
  void (__fastcall *addIncomingData)(NetworkPeer *this, std::string);
  void (__fastcall *update)(NetworkPeer *this);
  void (__fastcall *flush)(NetworkPeer *this, std::function<void __cdecl(void)> *);
};

```

### `Bedrock::Threading::AsyncBase`
```
struct __cppobj Bedrock::Threading::AsyncBase : std::enable_shared_from_this<Bedrock::Threading::AsyncBase>
{
};

```

### `Bedrock::Threading::IAsyncResult<void>`
```
struct __cppobj Bedrock::Threading::IAsyncResult<void> : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<void>_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `BiomeDefinitionListPacket`
```
const struct __cppobj BiomeDefinitionListPacket : Packet
{
  CompoundTag mBiomeData;
};

```

### `BiomeDefinitionListPacket_vtbl`
```
struct /*VFT*/ BiomeDefinitionListPacket_vtbl
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

### `BookEditPacket_vtbl`
```
struct /*VFT*/ BookEditPacket_vtbl
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

### `BossEventPacket_vtbl`
```
struct /*VFT*/ BossEventPacket_vtbl
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

### `BlockActorDataPacket_vtbl`
```
struct /*VFT*/ BlockActorDataPacket_vtbl
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

### `BlockPickRequestPacket`
```
const struct __cppobj __declspec(align(4)) BlockPickRequestPacket : Packet
{
  BlockPos mPos;
  bool mWithData;
  unsigned __int8 mMaxSlots;
};

```

### `BlockPickRequestPacket_vtbl`
```
struct /*VFT*/ BlockPickRequestPacket_vtbl
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

### `BlockEventPacket_vtbl`
```
struct /*VFT*/ BlockEventPacket_vtbl
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

### `BlockPalette`
```
const struct __cppobj BlockPalette
{
  std::mutex mLegacyBlockStatesConversionWarningMutex;
  std::set<std::pair<int,int>> mLegacyBlockStatesConversionWarningSet;
  std::map<std::string,BlockLegacy const *> mNameLookup;
  std::vector<Block const *> mBlockFromRuntimeId;
  Level *mLevel;
};

```

### `BackgroundTaskQueue`
```
struct __cppobj __declspec(align(8)) BackgroundTaskQueue
{
  std::mutex mIngressLock;
  std::mutex mEgressLock;
  SPSCQueue<std::shared_ptr<BackgroundTaskBase>,512> mTasks;
  std::atomic<unsigned __int64> mQueuedTasksCount;
  std::atomic<bool> mResortQueue;
  std::mutex mQueueLock;
  MovePriorityQueue<std::shared_ptr<BackgroundTaskBase>,BackgroundTaskBase::PriorityComparer> mLocalPriorityQueue;
  std::atomic<int> mNextItemPriority;
};

```

### `BackgroundWorker`
```
struct __cppobj BackgroundWorker : ITaskExecutionContext
{
  const bool mAsync;
  Bedrock::Threading::OSThreadPriority mPriority;
  std::optional<unsigned __int64> mCoreAffinity;
  std::string mName;
  std::thread mThread;
  std::thread::id mWorkerThreadID;
  std::atomic<enum BackgroundWorker::State> mState;
  ResetEventObj mResetEvent;
  std::atomic<bool> mIdle;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mIdleSinceTime;
  std::shared_ptr<BackgroundTaskBase> mCurrentTask;
  WorkerPool *mWorkerPool;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mMaxSpinlockDuration;
  BackgroundTaskQueue mTaskQueue;
};

```

### `BackgroundWorker_vtbl`
```
struct /*VFT*/ BackgroundWorker_vtbl
{
  void (__fastcall *~ITaskExecutionContext)(ITaskExecutionContext *this);
  bool (__fastcall *isAsync)(ITaskExecutionContext *this);
  bool (__fastcall *canTaskRunAgain)(ITaskExecutionContext *this);
};

```

### `BackgroundWorkerPerfInfo`
```
struct __cppobj BackgroundWorkerPerfInfo
{
  const BackgroundWorker *mUpdaterWorker;
  std::atomic<unsigned __int64> mTotalRunTasks;
  std::atomic<unsigned __int64> mTotalRunTasksTicks;
  std::atomic<unsigned int> mTotalWakeUps;
  std::atomic<double> mAverageTaskDuration;
  std::atomic<unsigned int> mWakeUpsPerSecond;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPerfInfoUpdate;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNextPerfInfoUpdate;
};

```

### `Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>,void,void,Option const &>`
```
struct __cppobj Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>,void,void,Option const &>
{
};

```

### `Bedrock::PubSub::Detail::SubscriptionBodyInterface`
```
struct __cppobj Bedrock::PubSub::Detail::SubscriptionBodyInterface
{
  Bedrock::PubSub::Detail::SubscriptionBodyInterface_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::PubSub::SubscriptionContext`
```
const struct __cppobj Bedrock::PubSub::SubscriptionContext
{
  Bedrock::PubSub::SubscriptionContext_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::PubSub::SubscriptionContext_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::SubscriptionContext_vtbl
{
  void (__fastcall *~SubscriptionContext)(Bedrock::PubSub::SubscriptionContext *this);
  void (__fastcall *to_string)(Bedrock::PubSub::SubscriptionContext *this, std::string *);
};

```

### `Bedrock::PubSub::Detail::SubscriptionBodyInterface_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::Detail::SubscriptionBodyInterface_vtbl
{
  void (__fastcall *~SubscriptionBodyInterface)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  const Bedrock::PubSub::SubscriptionContext *(__fastcall *_getContext)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  void (__fastcall *_disconnect)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this, std::shared_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface> *);
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody`
```
struct __cppobj __declspec(align(8)) Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody : Bedrock::PubSub::Detail::SubscriptionBodyInterface
{
  Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)> *mOwner;
  std::_List_iterator<std::_List_val<std::_List_simple_types<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody> > > > mIterator;
  std::function<void __cdecl(Option const &)> mFunction;
  std::unique_ptr<Bedrock::PubSub::SubscriptionContext> mContext;
  int mGroup;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &)>::SubscriptionBody_vtbl
{
  void (__fastcall *~SubscriptionBodyInterface)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  const Bedrock::PubSub::SubscriptionContext *(__fastcall *_getContext)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  void (__fastcall *_disconnect)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this, std::shared_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface> *);
};

```

### `Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>,void,void,Option const &,enum InputMode>`
```
struct __cppobj Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>,void,void,Option const &,enum InputMode>
{
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody`
```
struct __cppobj __declspec(align(8)) Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody : Bedrock::PubSub::Detail::SubscriptionBodyInterface
{
  Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)> *mOwner;
  std::_List_iterator<std::_List_val<std::_List_simple_types<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody> > > > mIterator;
  std::function<void __cdecl(Option const &,enum InputMode)> mFunction;
  std::unique_ptr<Bedrock::PubSub::SubscriptionContext> mContext;
  int mGroup;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Option const &,enum InputMode)>::SubscriptionBody_vtbl
{
  void (__fastcall *~SubscriptionBodyInterface)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  const Bedrock::PubSub::SubscriptionContext *(__fastcall *_getContext)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  void (__fastcall *_disconnect)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this, std::shared_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface> *);
};

```

### `Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>,void,void,bool &>`
```
struct __cppobj Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>,void,void,bool &>
{
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>`
```
struct __cppobj Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)> : Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>,void,void,bool &>
{
  std::list<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody>> mSubscriptions;
  std::mutex mMutex;
  std::weak_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody> mSingleSubscriber;
  std::atomic<unsigned __int64> mSubscriberCount;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody`
```
struct __cppobj __declspec(align(8)) Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody : Bedrock::PubSub::Detail::SubscriptionBodyInterface
{
  Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)> *mOwner;
  std::_List_iterator<std::_List_val<std::_List_simple_types<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody> > > > mIterator;
  std::function<void __cdecl(bool &)> mFunction;
  std::unique_ptr<Bedrock::PubSub::SubscriptionContext> mContext;
  int mGroup;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>::SubscriptionBody_vtbl
{
  void (__fastcall *~SubscriptionBodyInterface)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  const Bedrock::PubSub::SubscriptionContext *(__fastcall *_getContext)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  void (__fastcall *_disconnect)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this, std::shared_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface> *);
};

```

### `Bedrock::PubSub::Publisher<void __cdecl(bool &),Bedrock::PubSub::ThreadModel::MultiThreaded,void>`
```
struct __cppobj Bedrock::PubSub::Publisher<void __cdecl(bool &),Bedrock::PubSub::ThreadModel::MultiThreaded,void> : Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(bool &)>
{
};

```

### `Bedrock::Threading::IAsyncResult<std::string >`
```
struct __cppobj Bedrock::Threading::IAsyncResult<std::string > : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<std::string >_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<std::string >_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<std::string >_vtbl
{
  void (__fastcall *~IAsyncResult<std::string >)(Bedrock::Threading::IAsyncResult<std::string > *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<std::string > *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<std::string > *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<std::string > *this, std::exception_ptr *result);
  std::string *(__fastcall *getResult)(Bedrock::Threading::IAsyncResult<std::string > *this, std::string *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<std::string > *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<std::string > *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::string > const &)>);
};

```

### `Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> >`
```
struct __cppobj Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> >_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> >_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> >_vtbl
{
  void (__fastcall *~IAsyncResult<std::vector<ResourcePath> >)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this, std::exception_ptr *result);
  std::vector<ResourcePath> *(__fastcall *getResult)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this, std::vector<ResourcePath> *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::vector<ResourcePath> > const &)>);
};

```

### `Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> >`
```
struct __cppobj Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> >_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> >_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> >_vtbl
{
  void (__fastcall *~IAsyncResult<std::shared_ptr<mce::Image> >)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this, std::exception_ptr *result);
  std::shared_ptr<mce::Image> *(__fastcall *getResult)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this, std::shared_ptr<mce::Image> *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::shared_ptr<mce::Image> > const &)>);
};

```

### `Bedrock::Threading::IAsyncResult<bool>`
```
struct __cppobj Bedrock::Threading::IAsyncResult<bool> : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<bool>_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<bool>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<bool>_vtbl
{
  void (__fastcall *~IAsyncResult<bool>)(Bedrock::Threading::IAsyncResult<bool> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<bool> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<bool> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<bool> *this, std::exception_ptr *result);
  bool (__fastcall *getResult)(Bedrock::Threading::IAsyncResult<bool> *this);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<bool> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<bool> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<bool> const &)>);
};

```

### `BaseLightData`
```
struct __cppobj BaseLightData
{
  BaseLightData_vtbl *__vftable /*VFT*/;
  mce::Color mSunriseColor;
  float mGamma;
  float mSkyDarken;
  AutomaticID<Dimension,int> mDimensionType;
  float mDarkenWorldAmount;
  float mPreviousDarkenWorldAmount;
  bool mNightvisionActive;
  float mNightvisionScale;
  bool mUnderwaterVision;
  float mUnderwaterScale;
  int mSkyFlashTime;
};

```

### `BaseLightData_vtbl`
```
struct /*VFT*/ BaseLightData_vtbl
{
  bool (__fastcall *operator==)(BaseLightData *this, const BaseLightData *);
  void (__fastcall *~BaseLightData)(BaseLightData *this);
};

```

### `BiomeChunkState`
```
struct __cppobj BiomeChunkState
{
  unsigned __int8 snowLevel;
};

```

### `buffer_span<Pos>`
```
struct __cppobj buffer_span<Pos>
{
  const Pos *mBegin;
  const Pos *mEnd;
};

```

### `buffer_span<unsigned int>`
```
struct __cppobj buffer_span<unsigned int>
{
  const unsigned int *mBegin;
  const unsigned int *mEnd;
};

```

### `BlockEventListener`
```
struct __cppobj BlockEventListener
{
  BlockEventListener_vtbl *__vftable /*VFT*/;
};

```

### `BlockSourceHandle`
```
struct __cppobj BlockSourceHandle : BlockSourceListener
{
  BlockSource *mSource;
};

```

### `BlockEventListener_vtbl`
```
struct /*VFT*/ BlockEventListener_vtbl
{
  void (__fastcall *~BlockEventListener)(BlockEventListener *this);
  EventResult (__fastcall *onBlockPlacedByPlayer)(BlockEventListener *this, Player *, const Block *, const BlockPos *, bool);
  EventResult (__fastcall *onBlockDestroyedByPlayer)(BlockEventListener *this, Player *, const std::string, const BlockPos *);
  EventResult (__fastcall *onBlockMovedByPiston)(BlockEventListener *this, const BlockPos *, const BlockPos *, const PistonBlockActor::PistonState);
  EventResult (__fastcall *onBlockDestructionStopped)(BlockEventListener *this, Player *, const BlockPos *, int);
  EventResult (__fastcall *onBlockDestructionStarted)(BlockEventListener *this, Player *, const BlockPos *);
  EventResult (__fastcall *onBlockInteractedWith)(BlockEventListener *this, Player *, const BlockPos *);
  EventResult (__fastcall *onBlockExploded)(BlockEventListener *this, const BlockPos *, const Block *, Actor *);
  EventResult (__fastcall *onBlockModified)(BlockEventListener *this, const BlockPos *, const Block *, const Block *);
  EventResult (__fastcall *onChestBlockTryPaired)(BlockEventListener *this, const ChestBlockTryPairEvent *);
  EventResult (__fastcall *onUnknownBlockReceived)(BlockEventListener *this, Level *, const NewBlockID *, unsigned __int16);
};

```

### `BiomeRegistry`
```
struct __cppobj BiomeRegistry : IEntityRegistryOwner
{
  WellKnownBiomeTags mWellKnownBiomeTags;
  std::unordered_map<AutomaticID<Dimension,int>,unsigned int,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,unsigned int> > > mDimensionNextId;
  std::unordered_map<AutomaticID<Dimension,int>,std::vector<std::unique_ptr<Biome>>,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::vector<std::unique_ptr<Biome>> > > > mDimensionBiomes;
  std::vector<std::unique_ptr<Biome>> mBiomes;
  OwnerPtrT<EntityRegistryRefTraits> mEntities;
  unsigned int mNextId;
  std::atomic<bool> mClosedForRegistration;
  bool mLoadFromPacks;
  TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > mTagRegistry;
  Biome *mEmptyBiome;
  std::unique_ptr<JsonDefinitionUpgrader::IJsonDefinitionUpgrader> mBiomeDefinitionUpgrader;
};

```

### `Biome_vtbl`
```
struct /*VFT*/ Biome_vtbl
{
  void (__fastcall *~Biome)(Biome *this);
};

```

### `BiomeRegistry_vtbl`
```
struct /*VFT*/ BiomeRegistry_vtbl
{
  OwnerPtrT<EntityRegistryRefTraits> *(__fastcall *getEntityRegistry)(IEntityRegistryOwner *this);
  void (__fastcall *~BiomeRegistry)(BiomeRegistry *this);
};

```

### `Bedrock::LogEndPoint`
```
struct __cppobj Bedrock::LogEndPoint
{
  Bedrock::LogEndPoint_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::LogEndPoint_vtbl`
```
struct /*VFT*/ Bedrock::LogEndPoint_vtbl
{
  void (__fastcall *~LogEndPoint)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(Bedrock::LogEndPoint *this, const char *);
  void (__fastcall *flush)(Bedrock::LogEndPoint *this);
  void (__fastcall *setEnabled)(Bedrock::LogEndPoint *this, bool);
  bool (__fastcall *isEnabled)(Bedrock::LogEndPoint *this);
};

```

### `Bedrock::NonOwnerPointer<TextFilteringProcessor>`
```
struct __cppobj Bedrock::NonOwnerPointer<TextFilteringProcessor>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::Threading::EnableQueueForMainThread`
```
struct __cppobj Bedrock::Threading::EnableQueueForMainThread
{
  Bedrock::Threading::EnableQueueForMainThread_vtbl *__vftable /*VFT*/;
  std::unique_ptr<TaskGroup> mQueueForMainThreadTaskGroup;
};

```

### `Bedrock::Threading::EnableQueueForMainThread_vtbl`
```
struct /*VFT*/ Bedrock::Threading::EnableQueueForMainThread_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `Bedrock::Threading::CountTracker`
```
struct __cppobj Bedrock::Threading::CountTracker
{
  std::atomic<unsigned int> mCount;
};

```

### `Bedrock::NonOwnerPointer<TextureAtlas>`
```
struct __cppobj Bedrock::NonOwnerPointer<TextureAtlas>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `BaseContainerMenu`
```
struct __cppobj __declspec(align(8)) BaseContainerMenu : ContainerContentChangeListener, IContainerManager
{
  Player *mPlayer;
  std::vector<ItemStack> mLastSlots;
  ContainerID mContainerId;
  ContainerType mContainerType;
};

```

### `BaseContainerMenu_vtbl`
```
struct /*VFT*/ BaseContainerMenu_vtbl
{
  void (__fastcall *containerContentChanged)(ContainerContentChangeListener *this, int);
  void (__fastcall *~ContainerContentChangeListener)(ContainerContentChangeListener *this);
  void (__fastcall *containerAddCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *containerRemoveCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *removeSlot)(BaseContainerMenu *this, int, int);
  bool (__fastcall *isSlotDirty)(BaseContainerMenu *this, int);
  bool (__fastcall *isResultSlot)(BaseContainerMenu *this, int);
  Container *(__fastcall *_getContainer)(BaseContainerMenu *this);
};

```

### `Bedrock::NonOwnerPointer<StoreCatalogConfig>`
```
struct __cppobj Bedrock::NonOwnerPointer<StoreCatalogConfig>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<UIEventCoordinator>`
```
struct __cppobj Bedrock::NonOwnerPointer<UIEventCoordinator>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `BaseScreen`
```
struct __cppobj BaseScreen : AbstractScene
{
  int mWidth;
  int mHeight;
  bool mShouldSendEvents;
  bool mWantsTextOnly;
  bool mIsPopped;
  bool mShowingModUI;
  std::unique_ptr<AbstractScreenSetupCleanupStrategy> mScreenSetupCleanup;
};

```

### `BaseScreen_vtbl`
```
struct /*VFT*/ BaseScreen_vtbl
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

### `Bedrock::NonOwnerPointer<PersonaService>`
```
struct __cppobj Bedrock::NonOwnerPointer<PersonaService>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<FileArchiver>`
```
struct __cppobj Bedrock::NonOwnerPointer<FileArchiver>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::Threading::AsyncDeferredResultT<void>`
```
struct __cppobj Bedrock::Threading::AsyncDeferredResultT<void> : Bedrock::Threading::IAsyncResult<void>
{
  std::mutex mLock;
  Bedrock::Threading::AsyncDeferredResultT<void>::DelayStatus mStatus;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>> mComplete;
};

```

### `Bedrock::Threading::AsyncDeferredResultT<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::AsyncDeferredResultT<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `BaseActorRenderer`
```
struct __cppobj BaseActorRenderer : ActorShaderManager
{
  mce::MaterialPtr mNameTagMat;
  mce::MaterialPtr mDepthTestedNameTagMat;
  mce::MaterialPtr mDepthTestedNameTextMat;
  mce::MaterialPtr mDepthTestedHealthMat;
};

```

### `BaseActorRenderer_vtbl`
```
struct /*VFT*/ BaseActorRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
};

```

### `BlockActorRenderData`
```
struct __cppobj BlockActorRenderData
{
  BlockSource *renderSource;
  BlockActor *entity;
  const Block *block;
  const Vec3 *position;
  const mce::MaterialPtr *forcedMat;
  const mce::ClientTexture forcedTex;
  int breakingAmount;
  const dragon::RenderMetadata actorRenderMetadata;
};

```

### `BlockActorRenderer`
```
struct __cppobj BlockActorRenderer : BaseActorRenderer
{
};

```

### `BlockActorRenderer_vtbl`
```
struct /*VFT*/ BlockActorRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `BoneAnimationChannel`
```
struct __cppobj BoneAnimationChannel
{
  BoneTransformType mBoneTransformType;
  std::vector<KeyFrameTransform> mKeyFrames;
};

```

### `BoneAnimation`
```
struct __cppobj __declspec(align(8)) BoneAnimation
{
  HashedString mBoneName;
  std::vector<BoneAnimationChannel> mAnimationChannels;
  _BYTE mRotationRelativeMode[4];
};

```

### `buffer_span<std::string >`
```
struct __cppobj buffer_span<std::string >
{
  const std::string *mBegin;
  const std::string *mEnd;
};

```

### `BlockActorRenderDispatcher`
```
struct __cppobj BlockActorRenderDispatcher
{
  std::map<enum BlockActorRendererId,std::unique_ptr<BlockActorRenderer>> mRenderers;
  std::vector<std::function<void __cdecl(ActorResourceDefinitionGroup const &,mce::TextureGroup *)>> mGameSpecificRegistrationCallbacks;
};

```

### `BlockTessellator::UVOverride`
```
struct __cppobj BlockTessellator::UVOverride
{
  unsigned __int16 pbrTextureDataHandle;
  float u0;
  float u1;
  float v0;
  float v1;
};

```

### `BlockGraphics_vtbl`
```
struct /*VFT*/ BlockGraphics_vtbl
{
  void (__fastcall *~BlockGraphics)(BlockGraphics *this);
  int (__fastcall *getIconYOffset)(BlockGraphics *this);
  BlockRenderLayer (__fastcall *getRenderLayer)(BlockGraphics *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColor)(BlockGraphics *this, BlockSource *, const BlockPos *);
  int (__fastcall *getColor)(BlockGraphics *this, int);
  int (__fastcall *getColorForParticle)(BlockGraphics *this, BlockSource *, const BlockPos *, int);
  bool (__fastcall *isSeasonTinted)(BlockGraphics *this, BlockSource *, const BlockPos *);
  void (__fastcall *onGraphicsModeChanged)(BlockGraphics *this, bool, bool);
  int (__fastcall *getExtraRenderLayers)(BlockGraphics *this);
  const AABB *(__fastcall *getVisualShape)(BlockGraphics *this, unsigned __int16, AABB *, bool);
  const AABB *(__fastcall *getVisualShape)(BlockGraphics *this, const Block *, AABB *, bool);
  const TextureUVCoordinateSet *(__fastcall *getCarriedTexture)(BlockGraphics *this, unsigned __int64, int);
  void (__fastcall *animateTick)(BlockGraphics *this, BlockSource *, const BlockPos *, Random *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockGraphics *this, Vec3 *result, const BlockPos *);
  Vec3 *(__fastcall *randomlyModifyPosition)(BlockGraphics *this, Vec3 *result, const BlockPos *, int *);
  void (__fastcall *setVisualShape)(BlockGraphics *this, const Vec3 *, const Vec3 *);
  void (__fastcall *setVisualShape)(BlockGraphics *this, const AABB *);
};

```

### `BlockGeometry::Element`
```
struct __cppobj BlockGeometry::Element
{
  std::string mName;
  std::string mParent;
  glm::tvec3<float,0> mPivot;
  glm::tvec3<float,0> mRotation;
  std::vector<BlockGeometry::ElementBox> mBoxes;
};

```

### `BlockGeometry::Model`
```
const struct __cppobj BlockGeometry::Model
{
  GameVersion mVersion;
  std::string mName;
  std::string mParent;
  std::vector<BlockGeometry::Element> mElements;
  std::unordered_map<std::string,std::string> mTextureMap;
  std::vector<std::string> mTextureList;
  std::vector<std::string> mTextureStack;
};

```

### `BlockGeometry::AlignedFace`
```
struct __cppobj BlockGeometry::AlignedFace
{
  std::array<Vec3,4> verts;
  std::array<Vec2,4> uvs;
  unsigned __int64 textureIndex;
};

```

### `BlockGeometry::OrientedFace`
```
struct __cppobj BlockGeometry::OrientedFace
{
  std::array<Vec3,4> verts;
  std::array<Vec2,4> uvs;
  Vec3 norm;
  unsigned __int64 textureIndex;
};

```

### `BlockGeometry::TessellatedModel::Occlusion`
```
struct BlockGeometry::TessellatedModel::Occlusion
{
  std::array<unsigned char,8> blocking;
  std::array<unsigned char,8> visible;
};

```

### `BlockGeometry::TessellatedModel`
```
const struct __cppobj BlockGeometry::TessellatedModel
{
  std::array<AABB,4> mAABoxes;
  std::array<std::vector<BlockGeometry::AlignedFace>,6> mEdgeSet;
  std::array<std::vector<BlockGeometry::AlignedFace>,6> mAlignedSet;
  std::vector<BlockGeometry::OrientedFace> mOrientedSet;
  std::array<BlockGeometry::TessellatedModel::Occlusion,6> mOcclusion;
  std::array<BlockGeometry::TessellatedModel::Occlusion,3> mTopOcclusionRot;
  std::array<BlockGeometry::TessellatedModel::Occlusion,3> mBotOcclusionRot;
  std::vector<std::string> mTextureNames;
};

```

### `BlockGraphics::ModelItem`
```
struct __cppobj BlockGraphics::ModelItem
{
  std::string name;
  const BlockGeometry::TessellatedModel *model;
  std::vector<unsigned __int64> textureIndices;
};

```

### `BlockTessellatorCache`
```
struct __cppobj BlockTessellatorCache
{
  BlockPos mPos;
  BlockSource *mRegion;
  std::array<BrightnessPair,8000> mLightColors;
  std::array<Block const *,8000> mBlocks;
  std::array<Block const *,8000> mExtraBlocks;
  std::array<BlockGraphics const *,8000> mBlockGraphics[2];
};

```

### `BlockTessellator::AocBlockFaceData`
```
struct __cppobj BlockTessellator::AocBlockFaceData
{
  std::array<mce::Color,4> aocCL;
  std::array<mce::Color,4> aocCH;
  std::array<Vec2,4> aocUVL;
  std::array<Vec2,4> aocUVH;
};

```

### `BlockTessellatorCustomExtraData::FlowerPotData`
```
struct __cppobj BlockTessellatorCustomExtraData::FlowerPotData
{
  const Block *mPlant;
};

```

### `BlockTessellator`
```
struct __cppobj BlockTessellator
{
  bool mRenderingExtra;
  bool mUseNormals;
  BlockSource *mRegion;
  TextureUVCoordinateSet mFixedTexture;
  bool mUseFixedTexture;
  bool mUseOccluder;
  bool _tmpUseRegion;
  bool mXFlipTexture;
  int mRenderingLayer;
  bool mRenderingGUI;
  bool mUsePBRFormats;
  bool mShouldEmitPointLights;
  bool mUseFixedColor;
  std::array<mce::Color,6> mFixedColors;
  bool mApplyAmbientOcclusion;
  __declspec(align(4)) _BYTE mBakedLighting[4];
  bool mForExport;
  mce::Color mAoColors[8];
  BrightnessPair mTc[4];
  std::array<enum Flip,6> mFlipFace;
  std::array<BlockTessellator::UVOverride,6> mTextureOverride;
  const Block *mAmbientOcclusionCacheBlocks[125];
  mce::MaterialPtr mItemMat;
  AABB mCurrentShapeBB;
  bool mCurrentShapeSet;
  const Block *mCurrentShapeBlock;
  BlockPos mCurrentShapeBlockPos;
  float mCurrentScale;
  std::unordered_map<unsigned int,mce::Mesh> mBlockMeshes;
  std::unordered_map<BlockTessellatorBlockInWorld,mce::Mesh> mInWorldBlockMeshes;
  BlockTessellatorCache mBlockCache;
  std::function<Block const & __cdecl(BlockPos const &)> mCachedGetBlock;
  bool mForceOpaque;
  std::vector<mce::PointLight> mPointLights;
  std::array<BlockTessellator::AocBlockFaceData,6> mAocBlockData;
  BlockTessellatorCustomExtraData::Map mBlockExtraDataMap;
};

```

### `BlockQueueEntry`
```
struct __cppobj BlockQueueEntry
{
  BlockPos pos;
  const Block *blockInfo;
};

```

### `BlockActorDelayedDeletionInfo`
```
struct __cppobj BlockActorDelayedDeletionInfo
{
  std::shared_ptr<BlockActor> mBlockEntity;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mExpirationTime;
  const Block *mBlock;
};

```

### `Bedrock::Threading::Burst::Strategy::Console`
```
struct __cppobj Bedrock::Threading::Burst::Strategy::Console
{
  unsigned __int64 mPrimaryWorkerCount;
  unsigned __int64 mSecondaryWorkerCount;
};

```

### `Bedrock::Threading::Burst::Details::Lifetime`
```
struct __cppobj Bedrock::Threading::Burst::Details::Lifetime
{
  std::atomic<unsigned __int64> mLifetime;
};

```

### `Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution`
```
struct __cppobj Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution
{
};

```

### `Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>`
```
struct __cppobj __declspec(align(8)) Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>
{
  const std::string mName;
  const unsigned int mPriority;
  const std::thread::id mAffinity;
  std::shared_ptr<Bedrock::Threading::Burst::Details::Lifetime> mCurrentLifetime;
  TaskGroup *mTaskGroup;
  const std::function<TaskResult __cdecl(void)> mCallback;
  Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution mExecutionStrategy;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks
{
  TaskGroup mTaskGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>>> mTasks;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution> : Bedrock::Threading::Burst::Strategy::Console
{
  std::vector<TaskGroup *> mTaskGroups;
  const std::string mName;
  const unsigned int mPriority;
  std::function<void __cdecl(std::function<void __cdecl(std::nullptr_t &)> &&)> mPredicate;
  std::atomic<unsigned __int64> mTotalItems;
  MPMCQueue<std::function<void __cdecl(std::nullptr_t &)> > mQueue;
  std::mutex mWaitMutex;
  std::condition_variable mWait;
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> > mPrimaryGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> >> mSecondaryGroups;
  std::vector<std::thread::id> mAffinities;
};

```

### `Bedrock::Threading::InstancedThreadLocalBase`
```
struct __cppobj Bedrock::Threading::InstancedThreadLocalBase
{
};

```

### `Bedrock::Intrusive::list_standard_operations<Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
```
struct __cppobj Bedrock::Intrusive::list_standard_operations<Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >
{
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >
{
  Bedrock::Intrusive::list_base_hook<void> mSentinel;
};

```

### `Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >`
```
struct __cppobj __declspec(align(4)) Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> > : Bedrock::Threading::InstancedThreadLocalBase
{
  std::function<void __cdecl(ThreadedFrameConstantsContainer *)> mConstructor;
  Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> > mItems;
  std::mutex mMutex;
  unsigned int mKey;
  bool mInitialized;
};

```

### `Bedrock::IIslandCore`
```
struct __cppobj Bedrock::IIslandCore
{
  Bedrock::IIslandCore_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::ActivationArguments`
```
const struct __cppobj __declspec(align(4)) Bedrock::ActivationArguments
{
  std::unordered_map<std::string,std::string> mArguments;
  std::string mProcessRegistrationKey;
  std::string mUrl;
  _BYTE mType[4];
  unsigned int mNumArgs;
  ARVRPlatform mARVRPlatform;
  bool mGenerateDocumentation;
  bool mDisablePauseMenuOnFocusLost;
};

```

### `Bedrock::IIslandCore_vtbl`
```
struct /*VFT*/ Bedrock::IIslandCore_vtbl
{
  void (__fastcall *~IIslandCore)(Bedrock::IIslandCore *this);
  unsigned __int16 (__fastcall *getId)(Bedrock::IIslandCore *this);
  bool (__fastcall *start)(Bedrock::IIslandCore *this);
  bool (__fastcall *suspend)(Bedrock::IIslandCore *this);
  bool (__fastcall *resume)(Bedrock::IIslandCore *this);
  bool (__fastcall *stop)(Bedrock::IIslandCore *this);
  void (__fastcall *mainUpdate)(Bedrock::IIslandCore *this);
  void (__fastcall *processActivationArguments)(Bedrock::IIslandCore *this, const Bedrock::ActivationArguments *);
};

```

### `Bedrock::SignalReceiver`
```
struct __cppobj __declspec(align(8)) Bedrock::SignalReceiver
{
  Bedrock::SignalReceiver_vtbl *__vftable /*VFT*/;
  std::vector<moodycamel::ConcurrentQueue<std::shared_ptr<Bedrock::SignalBase>,moodycamel::ConcurrentQueueDefaultTraits>> mSignalQueues;
  std::vector<std::weak_ptr<Bedrock::ISignalHandlerMap>> mHandlerMapVector;
  std::vector<std::weak_ptr<Bedrock::SignalRouteBase>> mRouteVector;
  unsigned __int16 mReceiverId;
};

```

### `Bedrock::SignalReceiver_vtbl`
```
struct /*VFT*/ Bedrock::SignalReceiver_vtbl
{
  void (__fastcall *~SignalReceiver)(Bedrock::SignalReceiver *this);
};

```

### `Bedrock::ISignalHandlerMap`
```
struct __cppobj Bedrock::ISignalHandlerMap
{
  Bedrock::ISignalHandlerMap_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::ISignalHandlerMap_vtbl`
```
struct /*VFT*/ Bedrock::ISignalHandlerMap_vtbl
{
  void (__fastcall *~ISignalHandlerMap)(Bedrock::ISignalHandlerMap *this);
  bool (__fastcall *remove)(Bedrock::ISignalHandlerMap *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalBase`
```
struct __cppobj __declspec(align(8)) Bedrock::SignalBase : std::enable_shared_from_this<Bedrock::SignalBase>
{
  Bedrock::SignalBase_vtbl *__vftable /*VFT*/;
  std::shared_ptr<Bedrock::SignalRouteNode> mNode;
  unsigned __int64 mCurrentPriority;
  bool mConsume;
};

```

### `Bedrock::SignalBase_vtbl`
```
struct /*VFT*/ Bedrock::SignalBase_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalRouteNode`
```
struct __cppobj Bedrock::SignalRouteNode
{
  std::function<void __cdecl(std::shared_ptr<Bedrock::SignalBase>)> mHandler;
  Bedrock::SignalReceiver *mRcvr;
  unsigned __int64 mQueueIdx;
};

```

### `Bedrock::SignalRouteBase`
```
struct __cppobj Bedrock::SignalRouteBase
{
  std::vector<std::shared_ptr<Bedrock::SignalRouteNode>> mNodes;
};

```

### `Bedrock::AppIsland`
```
struct __cppobj Bedrock::AppIsland : Bedrock::IIslandCore
{
  std::unique_ptr<Bedrock::SignalReceiver> mSignalRcvr;
};

```

### `Bedrock::AppIsland_vtbl`
```
struct /*VFT*/ Bedrock::AppIsland_vtbl
{
  void (__fastcall *~IIslandCore)(Bedrock::IIslandCore *this);
  unsigned __int16 (__fastcall *getId)(Bedrock::IIslandCore *this);
  bool (__fastcall *start)(Bedrock::IIslandCore *this);
  bool (__fastcall *suspend)(Bedrock::IIslandCore *this);
  bool (__fastcall *resume)(Bedrock::IIslandCore *this);
  bool (__fastcall *stop)(Bedrock::IIslandCore *this);
  void (__fastcall *mainUpdate)(Bedrock::IIslandCore *this);
  void (__fastcall *processActivationArguments)(Bedrock::IIslandCore *this, const Bedrock::ActivationArguments *);
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >
{
  Bedrock::Intrusive::list_base_hook<void> mSentinel;
};

```

### `Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > >`
```
struct __cppobj __declspec(align(4)) Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > > : Bedrock::Threading::InstancedThreadLocalBase
{
  std::function<void __cdecl(boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > *)> mConstructor;
  Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> > mItems;
  std::mutex mMutex;
  unsigned int mKey;
  bool mInitialized;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks
{
  TaskGroup mTaskGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>>> mTasks;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution> : Bedrock::Threading::Burst::Strategy::Console
{
  std::vector<TaskGroup *> mTaskGroups;
  const std::string mName;
  const unsigned int mPriority;
  std::function<void __cdecl(std::function<void __cdecl(dragon::rendering::RenderContext &)> &&)> mPredicate;
  std::atomic<unsigned __int64> mTotalItems;
  MPMCQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)> > mQueue;
  std::mutex mWaitMutex;
  std::condition_variable mWait;
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> > mPrimaryGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> >> mSecondaryGroups;
  std::vector<std::thread::id> mAffinities;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks
{
  TaskGroup mTaskGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>>> mTasks;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution> : Bedrock::Threading::Burst::Strategy::Console
{
  std::vector<TaskGroup *> mTaskGroups;
  const std::string mName;
  const unsigned int mPriority;
  std::function<void __cdecl(std::function<void __cdecl(void)> &&)> mPredicate;
  std::atomic<unsigned __int64> mTotalItems;
  MPMCQueue<std::function<void __cdecl(void)> > mQueue;
  std::mutex mWaitMutex;
  std::condition_variable mWait;
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> > mPrimaryGroup;
  std::vector<std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks,std::default_delete<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::TaskGroupTasks> >> mSecondaryGroups;
  std::vector<std::thread::id> mAffinities;
};

```

### `bgfx::RtLightInfo`
```
const struct bgfx::RtLightInfo
{
  unsigned __int16 mWorldSpacePosition[3];
  unsigned int packedData;
};

```

### `bgfx::PBRTextureData`
```
struct __cppobj bgfx::PBRTextureData
{
  float colourToMaterialUvScale[2];
  float colourToMaterialUvBias[2];
  float colourToNormalUvScale[2];
  float colourToNormalUvBias[2];
  int flags;
  float uniformRoughness;
  float uniformEmissive;
  float uniformMetalness;
  float maxMipColour;
  float maxMipMer;
  float maxMipNormalOrHeight;
  float pad;
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >
{
  Bedrock::Intrusive::list_base_hook<void> mSentinel;
};

```

### `Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >`
```
struct __cppobj __declspec(align(4)) Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> > : Bedrock::Threading::InstancedThreadLocalBase
{
  std::function<void __cdecl(ContentLog::ThreadSpecificData *)> mConstructor;
  Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> > mItems;
  std::mutex mMutex;
  unsigned int mKey;
  bool mInitialized;
};

```

### `Bedrock::NonOwnerPointer<ResourcePackManager>`
```
struct __cppobj Bedrock::NonOwnerPointer<ResourcePackManager>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<hbui::ILibrary>`
```
struct __cppobj Bedrock::NonOwnerPointer<hbui::ILibrary>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::Threading::Details::PendingConditional`
```
struct __cppobj Bedrock::Threading::Details::PendingConditional : Bedrock::Threading::IAsyncResult<void>
{
  std::function<bool __cdecl(void)> mCondition;
  std::mutex mLock;
  Bedrock::Threading::Details::ConditionalState mState;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>> mCallbacks;
};

```

### `Bedrock::Threading::Details::PendingConditional_vtbl`
```
struct /*VFT*/ Bedrock::Threading::Details::PendingConditional_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `Bedrock::Threading::PendingConditionals`
```
struct __cppobj Bedrock::Threading::PendingConditionals : Bedrock::EnableNonOwnerReferences
{
  std::mutex mLock;
  std::vector<std::shared_ptr<Bedrock::Threading::Details::PendingConditional>> mConditionals;
};

```

### `BindingFactory_vtbl`
```
struct /*VFT*/ BindingFactory_vtbl
{
  void (__fastcall *~BindingFactory)(BindingFactory *this);
  std::function<bool __cdecl(void)> *(__fastcall *getBooleanBinding)(BindingFactory *this, std::function<bool __cdecl(void)> *result, const std::string *);
  std::function<std::string __cdecl(void)> *(__fastcall *getStringBinding)(BindingFactory *this, std::function<std::string __cdecl(void)> *result, const std::string *);
  std::function<glm::tvec2<float,0> __cdecl(void)> *(__fastcall *getPointBinding)(BindingFactory *this, std::function<glm::tvec2<float,0> __cdecl(void)> *result, const std::string *);
  std::function<RectangleArea __cdecl(void)> *(__fastcall *getAreaBinding)(BindingFactory *this, std::function<RectangleArea __cdecl(void)> *result, const std::string *);
};

```

### `Bedrock::NonOwnerPointer<ClientInstanceEventCoordinator>`
```
struct __cppobj Bedrock::NonOwnerPointer<ClientInstanceEventCoordinator>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::DynamicPackage::DynamicPackageSourceListener`
```
struct __cppobj Bedrock::DynamicPackage::DynamicPackageSourceListener : Bedrock::EnableNonOwnerReferences
{
  Bedrock::DynamicPackage::DynamicPackageSourceListener_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::DynamicPackage::DynamicPackageSourceListener_vtbl`
```
struct /*VFT*/ Bedrock::DynamicPackage::DynamicPackageSourceListener_vtbl
{
  void (__fastcall *~DynamicPackageSourceListener)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this);
  void (__fastcall *onDownloadStarted)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this);
  void (__fastcall *onDownloadStateChanged)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, bool, bool, bool, bool, bool, Bedrock::DynamicPackage::DownloadPausedReason, Bedrock::DynamicPackage::DownloadFailedReason);
  void (__fastcall *onDownloadProgress)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, unsigned __int64, unsigned __int64, float, unsigned __int64);
  void (__fastcall *onMountStateChanged)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, std::string, Bedrock::DynamicPackage::MountState);
};

```

### `Bedrock::DynamicPackage::DynamicPackageSource`
```
struct __cppobj Bedrock::DynamicPackage::DynamicPackageSource
{
  Bedrock::DynamicPackage::DynamicPackageSource_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageSourceListener>`
```
struct __cppobj Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageSourceListener>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::DynamicPackage::CheckFilesResult`
```
struct Bedrock::DynamicPackage::CheckFilesResult
{
  Bedrock::DynamicPackage::CheckFilesResult::Value value;
  unsigned __int64 fileSize;
};

```

### `Bedrock::DynamicPackage::DynamicPackageSource_vtbl`
```
struct /*VFT*/ Bedrock::DynamicPackage::DynamicPackageSource_vtbl
{
  void (__fastcall *~DynamicPackageSource)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *setListener)(Bedrock::DynamicPackage::DynamicPackageSource *this, Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageSourceListener>);
  void (__fastcall *setConfig)(Bedrock::DynamicPackage::DynamicPackageSource *this, const rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator> *);
  bool (__fastcall *requireProcess)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *checkFiles)(Bedrock::DynamicPackage::DynamicPackageSource *this, Bedrock::NonOwnerPointer<AppPlatform>, std::weak_ptr<bool>, std::function<void __cdecl(Bedrock::DynamicPackage::CheckFilesResult)> *);
  void (__fastcall *mountFiles)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *downloadFiles)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *pauseDownload)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *resumeDownload)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *resumeDownloadOnCell)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *abortDownload)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  const Core::PathBuffer<std::string > *(__fastcall *getMountPath)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  const Core::PathBuffer<std::string > *(__fastcall *getDownloadDirectoryPath)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  const Core::PathBuffer<std::string > *(__fastcall *getDownloadFilePath)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  unsigned __int64 (__fastcall *getDownloadSize)(Bedrock::DynamicPackage::DynamicPackageSource *this);
  void (__fastcall *onLanguageChanged)(Bedrock::DynamicPackage::DynamicPackageSource *this);
};

```

### `Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageManagerListener>`
```
struct __cppobj Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageManagerListener>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::DynamicPackage::DownloadState`
```
struct __cppobj __declspec(align(8)) Bedrock::DynamicPackage::DownloadState
{
  bool mIsStarted;
  bool mIsPaused;
  bool mIsCompleted;
  bool mIsFailed;
  bool mNeedCelularPermission;
  bool mProgressIndeterminate;
  unsigned __int64 mProgress;
  unsigned __int64 mTotal;
  float mKbpsSpeed;
  unsigned __int64 mTimeRemainingMilliseconds;
  Bedrock::DynamicPackage::DownloadPausedReason mPausedReason;
  Bedrock::DynamicPackage::DownloadFailedReason mFailedReason;
};

```

### `Bedrock::DynamicPackage::DynamicPackageManagerImpl`
```
struct __cppobj Bedrock::DynamicPackage::DynamicPackageManagerImpl : Bedrock::DynamicPackage::DynamicPackageSourceListener
{
  Bedrock::NonOwnerPointer<AppPlatform> mAppPlatform;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::unique_ptr<Bedrock::DynamicPackage::DynamicPackageSource> mDynamicPackageSource;
  std::vector<Bedrock::NonOwnerPointer<Bedrock::DynamicPackage::DynamicPackageManagerListener>> mListeners;
  std::shared_ptr<bool> mExistenceTracker;
  rapidjson::GenericDocument<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator>,rapidjson::CrtAllocator> mDocument;
  _BYTE mCurrentStep[1];
  Bedrock::DynamicPackage::MountState mMountState;
  Bedrock::DynamicPackage::DownloadState mDownloadState;
  Bedrock::DynamicPackage::CheckFilesResult mLatestCheckFilesResult;
  bool mSelfCheckFiles;
  bool mSelfDownload;
  bool mSelfMount;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mCheckFilesHandle;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mMountHandle;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mStartDownloadHandle;
};

```

### `Bedrock::DynamicPackage::DynamicPackageManagerImpl_vtbl`
```
struct /*VFT*/ Bedrock::DynamicPackage::DynamicPackageManagerImpl_vtbl
{
  void (__fastcall *~DynamicPackageSourceListener)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this);
  void (__fastcall *onDownloadStarted)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this);
  void (__fastcall *onDownloadStateChanged)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, bool, bool, bool, bool, bool, Bedrock::DynamicPackage::DownloadPausedReason, Bedrock::DynamicPackage::DownloadFailedReason);
  void (__fastcall *onDownloadProgress)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, unsigned __int64, unsigned __int64, float, unsigned __int64);
  void (__fastcall *onMountStateChanged)(Bedrock::DynamicPackage::DynamicPackageSourceListener *this, std::string, Bedrock::DynamicPackage::MountState);
};

```

### `Bedrock::DynamicPackage::DynamicPackageManager`
```
struct __cppobj Bedrock::DynamicPackage::DynamicPackageManager
{
  std::unique_ptr<Bedrock::DynamicPackage::DynamicPackageManagerImpl> mImpl;
};

```

### `Bedrock::DynamicPackage::DynamicPackageManagerListener`
```
struct __cppobj Bedrock::DynamicPackage::DynamicPackageManagerListener : Bedrock::EnableNonOwnerReferences
{
  Bedrock::DynamicPackage::DynamicPackageManagerListener_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::DynamicPackage::DynamicPackageManagerListener_vtbl`
```
struct /*VFT*/ Bedrock::DynamicPackage::DynamicPackageManagerListener_vtbl
{
  void (__fastcall *~DynamicPackageManagerListener)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this);
  void (__fastcall *onInitializeComplete)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this);
  void (__fastcall *onCheckFileResult)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this, const Bedrock::DynamicPackage::CheckFilesResult *);
  void (__fastcall *onMountStateChanged)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this, const Bedrock::DynamicPackage::MountState *);
  void (__fastcall *onDownloadStarted)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this, const Bedrock::DynamicPackage::DownloadState *);
  void (__fastcall *onDownloadStateChanged)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this, const Bedrock::DynamicPackage::DownloadState *);
  void (__fastcall *onDownloadCompleted)(Bedrock::DynamicPackage::DynamicPackageManagerListener *this, const Bedrock::DynamicPackage::DownloadState *);
};

```

### `ButtonChordTracker`
```
struct __cppobj ButtonChordTracker
{
  InputEventQueue *mQueue;
  std::vector<ButtonChordTracker::ChordButtonDetails *> mChordsDown;
  std::unordered_map<int,ButtonChordTracker::TrackerMappingAndState> mPerIdTrackerData;
};

```

### `ButtonRepeater::ButtonTimeTracker`
```
struct __cppobj __declspec(align(8)) ButtonRepeater::ButtonTimeTracker
{
  BasicTimer mRepeatTimer;
  ButtonState mCurrentState;
  InputEvent mEventToSend;
};

```

### `ButtonRepeater`
```
struct __cppobj ButtonRepeater
{
  std::unordered_map<int,std::unordered_map<unsigned int,ButtonRepeater::ButtonTimeTracker>> mPerIdTrackerData;
};

```

### `BindingFactoryMap`
```
struct __cppobj BindingFactoryMap
{
  BindingFactoryMap_vtbl *__vftable /*VFT*/;
};

```

### `BindingFactoryMap_vtbl`
```
struct /*VFT*/ BindingFactoryMap_vtbl
{
  void (__fastcall *~BindingFactoryMap)(BindingFactoryMap *this);
  const BindingFactory *(__fastcall *getBindingFactory)(BindingFactoryMap *this, int);
};

```

### `Bedrock::NonOwnerPointer<ContentLogFileEndPoint>`
```
const struct __cppobj Bedrock::NonOwnerPointer<ContentLogFileEndPoint>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `buffer_span<ChunkPos>`
```
struct __cppobj buffer_span<ChunkPos>
{
  const ChunkPos *mBegin;
  const ChunkPos *mEnd;
};

```

### `BaseLightTextureImageBuilder`
```
struct __cppobj BaseLightTextureImageBuilder
{
  BaseLightTextureImageBuilder_vtbl *__vftable /*VFT*/;
  const Dimension *mDimension;
};

```

### `BaseLightTextureImageBuilder_vtbl`
```
struct /*VFT*/ BaseLightTextureImageBuilder_vtbl
{
  void (__fastcall *~BaseLightTextureImageBuilder)(BaseLightTextureImageBuilder *this);
  void (__fastcall *init)(BaseLightTextureImageBuilder *this, Dimension *);
  bool (__fastcall *buildImage)(BaseLightTextureImageBuilder *this, const BaseLightData *, mce::Image *, unsigned int, float, float, bool);
  void (__fastcall *getModifiedBlockBrightnessColor)(BaseLightTextureImageBuilder *this, const BlockPos *, const Block *, const Brightness *, BrightnessPair *);
  std::unique_ptr<BaseLightData> *(__fastcall *createBaseLightTextureData)(BaseLightTextureImageBuilder *this, std::unique_ptr<BaseLightData> *result, IClientInstance *, const BaseLightData *);
};

```

### `BlockEventDispatcher`
```
struct __cppobj __declspec(align(8)) BlockEventDispatcher
{
  std::unordered_map<int,std::unique_ptr<ListenerInfo>> mRegisteredListeners;
  int mHandleCounter;
};

```

### `BaseCircuitComponent`
```
struct __cppobj __declspec(align(8)) BaseCircuitComponent
{
  BaseCircuitComponent_vtbl *__vftable /*VFT*/;
  CircuitComponentList mSources;
  bool mIgnoreFirstUpdate;
  bool mIsFirstTime;
  bool mNeedsUpdate;
  BlockPos mChunkPosition;
  bool mShouldEvaluate;
  int mStrength;
  unsigned __int8 mDirection;
  bool mAllowPowerUp;
  bool mAllowPowerDown;
  bool mRemoved;
};

```

### `BaseCircuitComponent_vtbl`
```
struct /*VFT*/ BaseCircuitComponent_vtbl
{
  void (__fastcall *~BaseCircuitComponent)(BaseCircuitComponent *this);
  int (__fastcall *getStrength)(BaseCircuitComponent *this);
  int (__fastcall *getDirection)(BaseCircuitComponent *this);
  void (__fastcall *setStrength)(BaseCircuitComponent *this, int);
  void (__fastcall *setDirection)(BaseCircuitComponent *this, unsigned __int8);
  bool (__fastcall *consumePowerAnyDirection)(BaseCircuitComponent *this);
  bool (__fastcall *canConsumerPower)(BaseCircuitComponent *this);
  bool (__fastcall *canStopPower)(BaseCircuitComponent *this);
  void (__fastcall *setStopPower)(BaseCircuitComponent *this, bool);
  unsigned __int64 (__fastcall *getBaseType)(BaseCircuitComponent *this);
  unsigned __int64 (__fastcall *getInstanceType)(BaseCircuitComponent *this);
  bool (__fastcall *removeSource)(BaseCircuitComponent *this, const BlockPos *, const BaseCircuitComponent *);
  bool (__fastcall *addSource)(BaseCircuitComponent *this, CircuitSceneGraph *, const CircuitTrackingInfo *, int *, bool *);
  bool (__fastcall *allowConnection)(BaseCircuitComponent *this, CircuitSceneGraph *, const CircuitTrackingInfo *, bool *);
  void (__fastcall *checkLock)(BaseCircuitComponent *this, CircuitSystem *, const BlockPos *);
  bool (__fastcall *evaluate)(BaseCircuitComponent *this, CircuitSystem *, const BlockPos *);
  void (__fastcall *cacheValues)(BaseCircuitComponent *this, CircuitSystem *, const BlockPos *);
  void (__fastcall *updateDependencies)(BaseCircuitComponent *this, CircuitSceneGraph *, const BlockPos *);
  bool (__fastcall *allowIndirect)(BaseCircuitComponent *this);
  bool (__fastcall *isHalfPulse)(BaseCircuitComponent *this);
  bool (__fastcall *hasSource)(BaseCircuitComponent *this, BaseCircuitComponent *);
  bool (__fastcall *hasChildrenSource)(BaseCircuitComponent *this);
  bool (__fastcall *isSecondaryPowered)(BaseCircuitComponent *this);
};

```

### `BeardAndShaverStorage`
```
struct __cppobj BeardAndShaverStorage
{
  std::unordered_map<ChunkPos,std::vector<BeardAndShaverDescription>> mBeardsAndShaversToProcess;
  std::shared_mutex mMutex;
};

```

### `BossbarInfo`
```
struct __cppobj BossbarInfo
{
  BossBarColor mColor;
  int mMax;
  int mValue;
  bool mVisible;
  Json::Value mName;
  std::vector<ActorUniqueID> mPlayers;
};

```

### `BossbarManager`
```
struct __cppobj BossbarManager
{
  std::unordered_map<std::string,BossbarInfo> mBossbars;
};

```

### `buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >`
```
struct __cppobj buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >
{
  const std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > *mBegin;
  const std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > *mEnd;
};

```

### `Bedrock::NonOwnerPointer<FogDefinitionRegistry>`
```
struct __cppobj Bedrock::NonOwnerPointer<FogDefinitionRegistry>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<FogManager>`
```
struct __cppobj Bedrock::NonOwnerPointer<FogManager>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<FogManager const >`
```
struct __cppobj Bedrock::NonOwnerPointer<FogManager const >
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `BiomeComponentFactory`
```
struct __cppobj __declspec(align(4)) BiomeComponentFactory
{
  std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,std::pair<std::reference_wrapper<Biome>,std::reference_wrapper<IWorldRegistriesProvider> > > > mSchema;
  std::vector<std::function<void __cdecl(CompoundTag &,EntityContext &,IWorldRegistriesProvider &)>> mExtraSerialization;
  BiomeComponentFactory::FactoryScope mScope;
  bool mClosedForRegistration;
};

```

### `BlockDescriptor::BlockState`
```
struct __cppobj BlockDescriptor::BlockState
{
  HashedString mName;
  int mValue;
  VanillaStates::CachedItemStateMapPtr mCachedPtr;
};

```

### `BodyControl`
```
struct __cppobj BodyControl : Control
{
  int mTimeStill;
  float mLastHeadY;
};

```

### `BodyControl_vtbl`
```
struct /*VFT*/ BodyControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *clientTick)(BodyControl *this, Mob *);
};

```

### `BedHelper`
```
struct __cppobj BedHelper
{
  float mNorthDir;
  float mSouthDir;
  float mWestDir;
  float mEastDir;
  float mBedOffsetX;
  float mBedOffsetZ;
  float mMobOffsetWestX;
  float mMobOffsetEastX;
  float mMobOffsetSouthZ;
  float mMobOffsetNorthZ;
};

```

### `BlockActor_vtbl`
```
struct /*VFT*/ BlockActor_vtbl
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

### `BlockGraphicsModeChangeContext`
```
const struct __cppobj BlockGraphicsModeChangeContext
{
  bool mFancyRendering;
  bool mTransparentLeaves;
  bool mFancyBubbles;
  bool mRayTracing;
};

```

### `BlockLegacy_vtbl`
```
struct /*VFT*/ BlockLegacy_vtbl
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

### `BlockStateVariant`
```
struct __cppobj BlockStateVariant : ItemState
{
  std::unique_ptr<ListTag> mEnumValues;
  BidirectionalUnorderedMap<int,unsigned __int64> mHashIndexMap;
};

```

### `BlockStateVariant_vtbl`
```
struct /*VFT*/ BlockStateVariant_vtbl
{
  void (__fastcall *~ItemState)(ItemState *this);
  void (__fastcall *toNBT)(ItemState *this, CompoundTag *, int);
  bool (__fastcall *fromNBT)(ItemState *this, const CompoundTag *, int *);
};

```

### `BidirectionalUnorderedMap<unsigned __int64,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<unsigned __int64,std::string >
{
  std::unordered_map<unsigned __int64,std::string> mRight;
  std::unordered_map<std::string,unsigned __int64> mLeft;
};

```

### `BlockStateMeta`
```
struct __cppobj BlockStateMeta
{
  _BYTE mType[1];
  std::unique_ptr<ListTag> mEnumValues;
  BidirectionalUnorderedMap<int,unsigned __int64> mHashIndexMap;
  const ItemState *mItemState;
  std::string mName;
};

```

### `BlockStateGroup`
```
struct __cppobj BlockStateGroup
{
  std::vector<std::unique_ptr<BlockStateVariant>> mRegisteredBlockStates;
  BidirectionalUnorderedMap<unsigned __int64,std::string > mHashNames;
  BidirectionalUnorderedMap<int,unsigned __int64> mIdNames;
  std::unordered_map<int,std::unique_ptr<BlockStateMeta>> mBlockStates;
  unsigned __int64 lastStateID;
};

```

### `BlockSourceListener_vtbl`
```
struct /*VFT*/ BlockSourceListener_vtbl
{
  void (__fastcall *~BlockSourceListener)(BlockSourceListener *this);
  void (__fastcall *onSourceCreated)(BlockSourceListener *this, BlockSource *);
  void (__fastcall *onSourceDestroyed)(BlockSourceListener *this, BlockSource *);
  void (__fastcall *onAreaChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *, const BlockPos *);
  void (__fastcall *onBlockChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *, unsigned int, const Block *, const Block *, int, const ActorBlockSyncMessage *);
  void (__fastcall *onBrightnessChanged)(BlockSourceListener *this, BlockSource *, const BlockPos *);
  void (__fastcall *onBlockEntityChanged)(BlockSourceListener *this, BlockSource *, BlockActor *);
  void (__fastcall *onBlockEntityAboutToBeRemoved)(BlockSourceListener *this, BlockSource *, std::shared_ptr<BlockActor>);
  void (__fastcall *onEntityChanged)(BlockSourceListener *this, BlockSource *, Actor *);
  void (__fastcall *onBlockEvent)(BlockSourceListener *this, BlockSource *, int, int, int, int, int);
};

```

### `BehaviorTreeDescription`
```
struct __cppobj BehaviorTreeDescription : ComponentDescription
{
  std::string mBehaviorTreeId;
};

```

### `BehaviorTreeDescription_vtbl`
```
struct /*VFT*/ BehaviorTreeDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
  void (__fastcall *parseData)(BehaviorTreeDescription *this, Json::Value *);
};

```

### `BreakBlocksDescription`
```
struct __cppobj BreakBlocksDescription : ComponentDescription
{
  std::unordered_set<BlockLegacy const *> mBreakableBlocks;
};

```

### `BreakBlocksDescription_vtbl`
```
struct /*VFT*/ BreakBlocksDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `BreakDoorAnnotationDescription`
```
struct __cppobj BreakDoorAnnotationDescription : ComponentDescription
{
  int mBreakTicks;
  Difficulty mMinDifficulty;
};

```

### `BreakDoorAnnotationDescription_vtbl`
```
struct /*VFT*/ BreakDoorAnnotationDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `BucketableDescription_vtbl`
```
struct /*VFT*/ BucketableDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `BlockComponentDescription`
```
struct __cppobj BlockComponentDescription
{
  BlockComponentDescription_vtbl *__vftable /*VFT*/;
};

```

### `BlockComponentFactory`
```
struct __cppobj BlockComponentFactory : Factory<BlockComponentDescription>
{
};

```

### `BlockComponentDescription_vtbl`
```
struct /*VFT*/ BlockComponentDescription_vtbl
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

### `BlockPermutationDescription`
```
struct __cppobj BlockPermutationDescription
{
  ExpressionNode mCondition;
  BlockComponentGroupDescription mComponents;
};

```

### `BlockEventResponseFactory`
```
struct __cppobj BlockEventResponseFactory : EventResponseFactory
{
};

```

### `BlockEventResponseFactory_vtbl`
```
struct /*VFT*/ BlockEventResponseFactory_vtbl
{
  void (__fastcall *~EventResponseFactory)(EventResponseFactory *this);
  void (__fastcall *initializeFactory)(EventResponseFactory *this, const Experiments *);
};

```

### `BlockDefinitionGroup`
```
struct __cppobj BlockDefinitionGroup
{
  std::unordered_map<std::string,DefinitionEvent> mEventHandlers;
  std::unordered_map<std::string,std::unique_ptr<BlockDefinition>> mBlockDefinitions;
  std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,BlockDescription> > mDescriptionSchema;
  std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,BlockComponentGroupDescription> > mBlockComponentsSchema;
  BlockEventResponseFactory mResponseFactory;
  std::unique_ptr<JsonDefinitionUpgrader::IJsonDefinitionUpgrader> mBlockDefinitionUpgrader;
  int mLastBlockId;
  std::vector<std::unique_ptr<Util::EntityComponentProcessor>> mComponentPostProcessors;
};

```

### `BehaviorDefinition`
```
struct __cppobj BehaviorDefinition
{
  BehaviorDefinition_vtbl *__vftable /*VFT*/;
  std::string mName;
  BehaviorTreeDefinitionPtr mTreeDefinition;
};

```

### `BehaviorFactory`
```
struct __cppobj BehaviorFactory
{
  std::unordered_map<std::string,std::pair<std::function<std::unique_ptr<BehaviorDefinition> __cdecl(void)>,std::function<std::unique_ptr<BehaviorNode> __cdecl(void)> >> mFactoryPairs;
};

```

### `BehaviorNode`
```
struct __cppobj __declspec(align(8)) BehaviorNode
{
  BehaviorNode_vtbl *__vftable /*VFT*/;
  const BehaviorDefinition *mNodeDefinition;
  BehaviorTreeDefinitionPtr mTreeDefinition;
  BehaviorNode *mParent;
  BehaviorComponent *mComponent;
  BehaviorData *mTreeData;
  BehaviorStatus mStatus;
};

```

### `BehaviorNode_vtbl`
```
struct /*VFT*/ BehaviorNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `BehaviorTreeDefinition`
```
struct __cppobj BehaviorTreeDefinition
{
  std::string mTreeName;
  std::string mStringInput;
  std::unique_ptr<BehaviorDefinition> mRoot;
};

```

### `BehaviorTreeGroup`
```
struct __cppobj BehaviorTreeGroup
{
  ResourcePackManager *mResourcePackManager;
  BehaviorFactory *mFactory;
  std::unordered_map<std::string,std::unique_ptr<BehaviorTreeDefinition>> mDefinitions;
  std::unordered_set<BehaviorTreeDefinitionPtr *> mRegisteredPtrs;
};

```

### `BehaviorData::DataProxy`
```
struct __cppobj __declspec(align(8)) BehaviorData::DataProxy
{
  BehaviorData::DataProxy_vtbl *__vftable /*VFT*/;
  std::string mId;
  _BYTE mType[1];
};

```

### `BehaviorData::DataProxy_vtbl`
```
struct /*VFT*/ BehaviorData::DataProxy_vtbl
{
  void (__fastcall *~DataProxy)(BehaviorData::DataProxy *this);
  std::unique_ptr<BehaviorData::DataProxy> *(__fastcall *copy)(BehaviorData::DataProxy *this, std::unique_ptr<BehaviorData::DataProxy> *result);
};

```

### `BehaviorDefinition_vtbl`
```
struct /*VFT*/ BehaviorDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `BossEventListener_vtbl`
```
struct /*VFT*/ BossEventListener_vtbl
{
  void (__fastcall *~BossEventListener)(BossEventListener *this);
  void (__fastcall *onBossEvent)(BossEventListener *this, BossEventUpdateType);
  void (__fastcall *onBossEvent)(BossEventListener *this, BossEventUpdateType, const ActorUniqueID *, const BossEventPacket *);
};

```

### `BlockGameplayHandler`
```
struct __cppobj BlockGameplayHandler : GameplayHandler
{
};

```

### `BlockGameplayHandler_vtbl`
```
struct /*VFT*/ BlockGameplayHandler_vtbl
{
  void (__fastcall *~GameplayHandler)(GameplayHandler *this);
  GameplayHandlerResult<enum CoordinatorResult> *(__fastcall *handleChestBlockTryPaired)(BlockGameplayHandler *this, GameplayHandlerResult<enum CoordinatorResult> *result, const ChestBlockTryPairEvent *);
};

```

### `BlockEventCoordinator`
```
struct __cppobj BlockEventCoordinator : EventCoordinator<BlockEventListener>
{
  std::unique_ptr<BlockGameplayHandler> mBlockGameplayHandler;
};

```

### `Bedrock::NonOwnerPointer<ActorDefinitionGroup>`
```
struct __cppobj Bedrock::NonOwnerPointer<ActorDefinitionGroup>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `BlockActorLevelListener`
```
struct __cppobj BlockActorLevelListener : LevelListener
{
};

```

### `BlockID`
```
struct __cppobj BlockID : NewType<unsigned char>
{
};

```

### `Bedrock::Threading::AsyncResult::CompleteResult<void>`
```
struct __cppobj Bedrock::Threading::AsyncResult::CompleteResult<void> : Bedrock::Threading::IAsyncResult<void>
{
};

```

### `Bedrock::Threading::AsyncResult::CompleteResult<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::AsyncResult::CompleteResult<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > >`
```
struct __cppobj Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > : Bedrock::Threading::AsyncBase
{
  Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > >_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > >_vtbl`
```
struct /*VFT*/ Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > >_vtbl
{
  void (__fastcall *~IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > >)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this, std::exception_ptr *result);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *getResult)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > const &)>);
};

```

### `Bedrock::Threading::AsyncResult::UnwrapResultBase<void>`
```
struct __cppobj Bedrock::Threading::AsyncResult::UnwrapResultBase<void> : Bedrock::Threading::IAsyncResult<void>
{
  std::mutex mLock;
  bool mCanceled;
  bool mDone;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > > > mWrapperResult;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mInnerResult;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>> mCallbacks;
};

```

### `Bedrock::Threading::AsyncResult::UnwrapResultBase<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::AsyncResult::UnwrapResultBase<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `Bedrock::Threading::AsyncResult::UnwrapResult<void>`
```
struct __cppobj Bedrock::Threading::AsyncResult::UnwrapResult<void> : Bedrock::Threading::AsyncResult::UnwrapResultBase<void>
{
};

```

### `Bedrock::Threading::AsyncResult::UnwrapResult<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::AsyncResult::UnwrapResult<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `Bedrock::Threading::WhenAll<void>`
```
struct __cppobj Bedrock::Threading::WhenAll<void> : Bedrock::Threading::IAsyncResult<void>
{
  std::mutex mLock;
  Bedrock::Threading::AsyncStatus mStatus;
  Bedrock::Threading::AsyncStatus mAggregateResult;
  unsigned __int64 mPending;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>> mCallbacks;
  std::vector<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >> mActions;
};

```

### `Bedrock::Threading::WhenAll<void>_vtbl`
```
struct /*VFT*/ Bedrock::Threading::WhenAll<void>_vtbl
{
  void (__fastcall *~IAsyncResult<void>)(Bedrock::Threading::IAsyncResult<void> *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<void> *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<void> *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<void> *this, std::exception_ptr *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<void> *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<void> *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<void> const &)>);
};

```

### `BedrockLog::LogAreaFilter`
```
struct __cppobj BedrockLog::LogAreaFilter : std::bitset<38>
{
};

```

### `buffer_span<WorkerPool *>`
```
struct __cppobj buffer_span<WorkerPool *>
{
  WorkerPool *const *mBegin;
  WorkerPool *const *mEnd;
};

```

### `BackgroundTaskBase::CurrentTaskAutoScope`
```
struct __cppobj BackgroundTaskBase::CurrentTaskAutoScope
{
  BackgroundTaskBase *mPrev;
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPaste>`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardPaste> : Bedrock::SignalBase
{
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPaste>_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardPaste>_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPaste>::SignalHandlerMap`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardPaste>::SignalHandlerMap : Bedrock::ISignalHandlerMap
{
  std::map<unsigned short,std::function<void __cdecl(std::shared_ptr<ApplicationSignal::ClipboardPaste>)>> mMap;
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPaste>::SignalHandlerMap_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardPaste>::SignalHandlerMap_vtbl
{
  void (__fastcall *~ISignalHandlerMap)(Bedrock::ISignalHandlerMap *this);
  bool (__fastcall *remove)(Bedrock::ISignalHandlerMap *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalRoute<ApplicationSignal::ClipboardPaste>`
```
struct __cppobj Bedrock::SignalRoute<ApplicationSignal::ClipboardPaste> : Bedrock::SignalRouteBase
{
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardCopy>`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardCopy> : Bedrock::SignalBase
{
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardCopy>_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardCopy>_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardCopy>::SignalHandlerMap`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardCopy>::SignalHandlerMap : Bedrock::ISignalHandlerMap
{
  std::map<unsigned short,std::function<void __cdecl(std::shared_ptr<ApplicationSignal::ClipboardCopy>)>> mMap;
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardCopy>::SignalHandlerMap_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardCopy>::SignalHandlerMap_vtbl
{
  void (__fastcall *~ISignalHandlerMap)(Bedrock::ISignalHandlerMap *this);
  bool (__fastcall *remove)(Bedrock::ISignalHandlerMap *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalRoute<ApplicationSignal::ClipboardCopy>`
```
struct __cppobj Bedrock::SignalRoute<ApplicationSignal::ClipboardCopy> : Bedrock::SignalRouteBase
{
};

```

### `buffer_span<bool>`
```
struct __cppobj buffer_span<bool>
{
  const bool *mBegin;
  const bool *mEnd;
};

```

### `buffer_span<unsigned char>`
```
const struct __cppobj buffer_span<unsigned char>
{
  const unsigned __int8 *mBegin;
  const unsigned __int8 *mEnd;
};

```

### `Bedrock::CommonPlatform`
```
struct __cppobj __declspec(align(8)) Bedrock::CommonPlatform
{
  Bedrock::CommonPlatform_vtbl *__vftable /*VFT*/;
  std::unique_ptr<Bedrock::PlatformRuntimeInfo> mPlatformRuntimeInfo;
  std::unique_ptr<Bedrock::PlatformBuildInfo> mPlatformBuildInfo;
  std::unique_ptr<Bedrock::IIslandManager> mIslandMgr;
  std::shared_ptr<Bedrock::AppIsland> mApp;
  std::atomic<bool> mbQueueRenderParameterSignal;
  std::atomic<bool> mHasInitialized;
};

```

### `Bedrock::CommonPlatform_vtbl`
```
struct /*VFT*/ Bedrock::CommonPlatform_vtbl
{
  void (__fastcall *~CommonPlatform)(Bedrock::CommonPlatform *this);
  bool (__fastcall *updatePlatformInfo)(Bedrock::CommonPlatform *this);
  bool (__fastcall *updatePlatformGraphicsInfo)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueShutdown)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueSuspend)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueResume)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueBack)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueLowMemory)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueFocusLost)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueFocusGained)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueInputPaneVisible)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueInputPaneHidden)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueSuspendWarning)(Bedrock::CommonPlatform *this);
  void (__fastcall *issueVisibilityChange)(Bedrock::CommonPlatform *this, bool);
  void (__fastcall *issueWindowSizeChange)(Bedrock::CommonPlatform *this, float, float);
  void (__fastcall *issueDPIChange)(Bedrock::CommonPlatform *this, float);
  void (__fastcall *issueOrientationChange)(Bedrock::CommonPlatform *this, const DisplayOrientation *);
  void (__fastcall *feedButtonPress)(Bedrock::CommonPlatform *this, const int *);
  void (__fastcall *feedKeyPress)(Bedrock::CommonPlatform *this, const char);
  void (__fastcall *setTextboxText)(Bedrock::CommonPlatform *this, const std::string *);
  void (__fastcall *setStorageDirectory)(Bedrock::CommonPlatform *this, FileStorageDirectory, bool, const PropertyBag *);
  FileStorageDirectory (__fastcall *setInitialStorageDirectory)(Bedrock::CommonPlatform *this, FileStorageDirectory);
  FileStorageDirectory (__fastcall *getStorageDirectory)(Bedrock::CommonPlatform *this);
  bool (__fastcall *_preAppCreation)(Bedrock::CommonPlatform *this, const Bedrock::ActivationArguments *);
  bool (__fastcall *_postAppCreation)(Bedrock::CommonPlatform *this, const Bedrock::ActivationArguments *);
  void (__fastcall *_processActivationArguments)(Bedrock::CommonPlatform *this, const Bedrock::ActivationArguments *);
  bool (__fastcall *_update)(Bedrock::CommonPlatform *this, bool);
  bool (__fastcall *_isShuttingDown)(Bedrock::CommonPlatform *this);
  bool (__fastcall *_isShutdown)(Bedrock::CommonPlatform *this);
  void (__fastcall *pushNotificationReceived_Shim)(Bedrock::CommonPlatform *this, const PushNotificationMessage *);
  void (__fastcall *notifyUriListeners_Shim)(Bedrock::CommonPlatform *this, const ActivationUri *);
  std::string *(__fastcall *getDeviceId_Shim)(Bedrock::CommonPlatform *this, std::string *result);
};

```

### `Bedrock::PlatformRuntimeInfo`
```
struct __cppobj Bedrock::PlatformRuntimeInfo
{
  Bedrock::PlatformRuntimeInfo_vtbl *__vftable /*VFT*/;
  std::string mDeviceModelName;
  std::string mOSVersion;
  std::string mCPUType;
  std::string mCPUName;
  std::string mCPUFeatures;
  std::string mGPUDriverVersion;
  std::string mSecureId;
  std::string mSerial;
  std::string mBoard;
  std::string mInstallerPackageName;
  std::string mRegion;
  PlatformType mPlatformType;
  unsigned __int64 mCachedFreeStorageSpace_Internal;
  unsigned __int64 mCachedFreeStorageSpace_External;
  unsigned __int64 mCachedFreeStorageSpace_Cloud;
  unsigned __int64 mTotalPhysicalMemory;
  unsigned __int64 mTotalVirtualMemory;
  unsigned __int64 mUsedMemory;
  unsigned __int64 mPhysicalMemorySize;
  unsigned int mOptimalLDBSize;
  float mWidth;
  float mHeight;
  float mDPI;
  _BYTE mOrientation[4];
  int mSignaturesHash;
  bool mGraphicsTearingSupport;
  bool mAllowSplitScreen;
  bool mSupportsMSAA;
  bool mHasFastAlphaTest;
  bool mSupportsVibration;
  bool mSupportsTextToSpeech;
  bool mSupportsClipboard;
  bool mSupportsFilePicking;
  bool mAllowContentLogWrite;
  bool mIsRooted;
  bool mCanSelfTerminate;
  bool mCanLaunchUri;
  unsigned __int8 mCoreCount;
  unsigned __int8 mThreadCount;
  unsigned __int8 mHighPerfThreadCount;
  unsigned __int8 mProcessorGrade;
  unsigned __int8 mGraphicsGrade;
  unsigned __int8 mMemoryGrade;
  unsigned __int8 mStorageGrade;
  unsigned __int8 mPowerSupplyGrade;
  unsigned int mCPUBits;
  Core::PathBuffer<std::string > mAssetStoragePath;
  Core::PathBuffer<std::string > mCurrentStoragePath;
  Core::PathBuffer<std::string > mExternalStoragePath;
  Core::PathBuffer<std::string > mInternalStoragePath;
  Core::PathBuffer<std::string > mLoggingPath;
  Core::PathBuffer<std::string > mPackagePath;
  Core::PathBuffer<std::string > mUserDataPath;
  Core::PathBuffer<std::string > mCacheStoragePath;
};

```

### `Bedrock::PlatformRuntimeInfo_vtbl`
```
struct /*VFT*/ Bedrock::PlatformRuntimeInfo_vtbl
{
  void (__fastcall *~PlatformRuntimeInfo)(Bedrock::PlatformRuntimeInfo *this);
};

```

### `Bedrock::PlatformBuildInfo`
```
struct __cppobj __declspec(align(8)) Bedrock::PlatformBuildInfo
{
  std::string mInstallerPackageName;
  Core::PathBuffer<std::string > mPlatformTempPath;
  Core::PathBuffer<std::string > mOnDiskScratchPath;
  Core::PathBuffer<std::string > mDataUrl;
  Core::PathBuffer<std::string > mAltDataUrl;
  std::string mFeedbackURL;
  __int64 mAppLastModified;
  bool mHasBuyButtonWhenLicenseInvalid;
};

```

### `Bedrock::IIslandManager`
```
struct __cppobj Bedrock::IIslandManager
{
  Bedrock::IIslandManager_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::IslandRegistrationInfo`
```
struct __cppobj Bedrock::IslandRegistrationInfo
{
  unsigned __int16 mId;
  std::string mName;
  std::vector<unsigned short> mRequires;
  std::shared_ptr<Bedrock::IIslandCore> *(__fastcall *mFactory)(std::shared_ptr<Bedrock::IIslandCore> *result);
};

```

### `Bedrock::IIslandManager_vtbl`
```
struct /*VFT*/ Bedrock::IIslandManager_vtbl
{
  void (__fastcall *~IIslandManager)(Bedrock::IIslandManager *this);
  bool (__fastcall *registerIsland)(Bedrock::IIslandManager *this, Bedrock::IslandRegistrationInfo *);
  std::shared_ptr<Bedrock::IIslandCore> *(__fastcall *getIsland)(Bedrock::IIslandManager *this, std::shared_ptr<Bedrock::IIslandCore> *result, unsigned __int16);
  void (__fastcall *start)(Bedrock::IIslandManager *this);
  void (__fastcall *suspend)(Bedrock::IIslandManager *this);
  void (__fastcall *resume)(Bedrock::IIslandManager *this);
  void (__fastcall *stop)(Bedrock::IIslandManager *this);
  bool (__fastcall *isTransitionComplete)(Bedrock::IIslandManager *this);
  void (__fastcall *update)(Bedrock::IIslandManager *this);
};

```

### `Bedrock::IApplicationDataStores`
```
struct __cppobj Bedrock::IApplicationDataStores : Bedrock::EnableNonOwnerReferences
{
  Bedrock::IApplicationDataStores_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::NonOwnerPointer<Bedrock::DataStore const >`
```
struct __cppobj Bedrock::NonOwnerPointer<Bedrock::DataStore const >
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<Bedrock::DataStore>`
```
struct __cppobj Bedrock::NonOwnerPointer<Bedrock::DataStore>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::IApplicationDataStores_vtbl`
```
struct /*VFT*/ Bedrock::IApplicationDataStores_vtbl
{
  void (__fastcall *~IApplicationDataStores)(Bedrock::IApplicationDataStores *this);
  Bedrock::NonOwnerPointer<Bedrock::DataStore const > *(__fastcall *getDataStore)(Bedrock::IApplicationDataStores *this, Bedrock::NonOwnerPointer<Bedrock::DataStore const > *result, Bedrock::IApplicationDataStores::DataStores);
  Bedrock::NonOwnerPointer<Bedrock::DataStore> *(__fastcall *getDataStore)(Bedrock::IApplicationDataStores *this, Bedrock::NonOwnerPointer<Bedrock::DataStore> *result, Bedrock::IApplicationDataStores::DataStores);
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest> : Bedrock::SignalBase
{
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `buffer_span<BlockID>`
```
struct __cppobj buffer_span<BlockID>
{
  const BlockID *mBegin;
  const BlockID *mEnd;
};

```

### `buffer_span<NibblePair>`
```
struct __cppobj buffer_span<NibblePair>
{
  const NibblePair *mBegin;
  const NibblePair *mEnd;
};

```

### `buffer_span<SubChunk>`
```
struct __cppobj buffer_span<SubChunk>
{
  const SubChunk *mBegin;
  const SubChunk *mEnd;
};

```

### `BytesDataOutput`
```
struct __cppobj BytesDataOutput : IDataOutput
{
};

```

### `BytesDataOutput_vtbl`
```
struct /*VFT*/ BytesDataOutput_vtbl
{
  void (__fastcall *~IDataOutput)(IDataOutput *this);
  void (__fastcall *writeString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeLongString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeFloat)(IDataOutput *this, float);
  void (__fastcall *writeDouble)(IDataOutput *this, long double);
  void (__fastcall *writeByte)(IDataOutput *this, char);
  void (__fastcall *writeShort)(IDataOutput *this, __int16);
  void (__fastcall *writeInt)(IDataOutput *this, int);
  void (__fastcall *writeLongLong)(IDataOutput *this, __int64);
  void (__fastcall *writeBytes)(IDataOutput *this, const void *, unsigned __int64);
  bool (__fastcall *isOk)(IDataOutput *this);
};

```

### `BytesDataInput_vtbl`
```
struct /*VFT*/ BytesDataInput_vtbl
{
  void (__fastcall *~IDataInput)(IDataInput *this);
  std::string *(__fastcall *readString)(IDataInput *this, std::string *result);
  std::string *(__fastcall *readLongString)(IDataInput *this, std::string *result);
  float (__fastcall *readFloat)(IDataInput *this);
  long double (__fastcall *readDouble)(IDataInput *this);
  char (__fastcall *readByte)(IDataInput *this);
  __int16 (__fastcall *readShort)(IDataInput *this);
  int (__fastcall *readInt)(IDataInput *this);
  __int64 (__fastcall *readLongLong)(IDataInput *this);
  bool (__fastcall *readBytes)(IDataInput *this, void *, unsigned __int64);
  unsigned __int64 (__fastcall *numBytesLeft)(IDataInput *this);
  bool (__fastcall *isOk)(IDataInput *this);
  bool (__fastcall *seek)(IDataInput *this, unsigned __int64);
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<Core::Random,std::allocator<Core::Random> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<Core::Random,std::allocator<Core::Random> >
{
  Core::Random *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<Core::Random,std::allocator<Core::Random> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<Core::Random,std::allocator<Core::Random> > : Bedrock::Threading::ThreadLocalObjectImplementation<Core::Random,std::allocator<Core::Random> >
{
  std::function<void __cdecl(Core::Random *)> mConstructor;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<Random,std::allocator<Random> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<Random,std::allocator<Random> >
{
  Random *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<Random,std::allocator<Random> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<Random,std::allocator<Random> > : Bedrock::Threading::ThreadLocalObjectImplementation<Random,std::allocator<Random> >
{
  std::function<void __cdecl(Random *)> mConstructor;
};

```

### `BiomeHeight`
```
struct __cppobj BiomeHeight
{
  float depth;
  float scale;
};

```

### `BiomeRegistry::BiomeParent`
```
struct __cppobj BiomeRegistry::BiomeParent
{
  std::string parentName;
  Json::Value json;
};

```

### `Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item`
```
struct __cppobj Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item : Bedrock::Intrusive::list_base_hook<void>
{
  std::_Align_type<double,48> mData;
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>
{
  Bedrock::Intrusive::list_base_hook<void> *mHook;
};

```

### `BoneAnimationChannelPlayer`
```
struct __cppobj __declspec(align(8)) BoneAnimationChannelPlayer
{
  unsigned __int64 mEndFrameIndex;
  float mTime;
};

```

### `BoneAnimationPlayer`
```
struct __cppobj BoneAnimationPlayer
{
  std::vector<BoneAnimationChannelPlayer> mBoneAnimationChannelPlayers;
};

```

### `buffer_span<std::unique_ptr<Block> >`
```
struct __cppobj buffer_span<std::unique_ptr<Block> >
{
  const std::unique_ptr<Block> *mBegin;
  const std::unique_ptr<Block> *mEnd;
};

```

### `BaseGameVersion::any_version_constructor`
```
struct __cppobj BaseGameVersion::any_version_constructor
{
};

```

### `BidirectionalUnorderedMap<enum ContainerType,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum ContainerType,std::string >
{
  std::unordered_map<enum ContainerType,std::string> mRight;
  std::unordered_map<std::string,enum ContainerType> mLeft;
};

```

### `BidirectionalUnorderedMap<std::string,enum FilterSubject>`
```
struct __cppobj BidirectionalUnorderedMap<std::string,enum FilterSubject>
{
  std::unordered_map<std::string,enum FilterSubject> mRight;
  std::unordered_map<enum FilterSubject,std::string> mLeft;
};

```

### `buffer_span_mut<std::unique_ptr<Block> >`
```
struct __cppobj buffer_span_mut<std::unique_ptr<Block> >
{
  std::unique_ptr<Block> *mBegin;
  std::unique_ptr<Block> *mEnd;
};

```

### `Bounds::Iterator`
```
struct __cppobj __declspec(align(8)) Bounds::Iterator
{
  Pos mPos;
  const Bounds *mBounds;
  int mIdx;
};

```

### `BlockTypeRegistry`
```
struct __cppobj BlockTypeRegistry
{
};

```

### `BlockPalette::ConstructorToken`
```
struct __cppobj BlockPalette::ConstructorToken
{
};

```

### `buffer_span_mut<NibblePair>`
```
struct __cppobj buffer_span_mut<NibblePair>
{
  NibblePair *mBegin;
  NibblePair *mEnd;
};

```

### `buffer_span_mut<SubChunk>::iterator`
```
struct __cppobj buffer_span_mut<SubChunk>::iterator
{
  SubChunk *mPtr;
};

```

### `BidirectionalUnorderedMap<std::string,AutomaticID<Dimension,int> >`
```
struct __cppobj BidirectionalUnorderedMap<std::string,AutomaticID<Dimension,int> >
{
  std::unordered_map<std::string,AutomaticID<Dimension,int>> mRight;
  std::unordered_map<AutomaticID<Dimension,int>,std::string,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::string > > > mLeft;
};

```

### `BehaviorPackContents`
```
struct __cppobj BehaviorPackContents
{
  unsigned int mEntities;
  unsigned int mLoots;
  unsigned int mTrades;
  unsigned int mPlugins;
};

```

### `Bedrock::PubSub::ThreadModel::SingleThreaded::NullMutex`
```
struct __cppobj Bedrock::PubSub::ThreadModel::SingleThreaded::NullMutex
{
};

```

### `Bedrock::PubSub::ThreadModel::SingleThreaded`
```
struct __cppobj Bedrock::PubSub::ThreadModel::SingleThreaded
{
};

```

### `BidirectionalUnorderedMap<enum InventoryTransactionError,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum InventoryTransactionError,std::string >
{
  std::unordered_map<enum InventoryTransactionError,std::string> mRight;
  std::unordered_map<std::string,enum InventoryTransactionError> mLeft;
};

```

### `BidirectionalUnorderedMap<enum ComplexInventoryTransaction::Type,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum ComplexInventoryTransaction::Type,std::string >
{
  std::unordered_map<enum ComplexInventoryTransaction::Type,std::string> mRight;
  std::unordered_map<std::string,enum ComplexInventoryTransaction::Type> mLeft;
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>::SignalHandlerMap`
```
struct __cppobj Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>::SignalHandlerMap : Bedrock::ISignalHandlerMap
{
  std::map<unsigned short,std::function<void __cdecl(std::shared_ptr<ApplicationSignal::ClipboardPasteRequest>)>> mMap;
};

```

### `Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>::SignalHandlerMap_vtbl`
```
struct /*VFT*/ Bedrock::Signal<ApplicationSignal::ClipboardPasteRequest>::SignalHandlerMap_vtbl
{
  void (__fastcall *~ISignalHandlerMap)(Bedrock::ISignalHandlerMap *this);
  bool (__fastcall *remove)(Bedrock::ISignalHandlerMap *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalRoute<ApplicationSignal::ClipboardPasteRequest>`
```
struct __cppobj Bedrock::SignalRoute<ApplicationSignal::ClipboardPasteRequest> : Bedrock::SignalRouteBase
{
};

```

### `Bedrock::Threading::WhenAll<void>::initialize::__l6::<lambda_3496a18835e5c18c61a44274245c5836>`
```
struct __cppobj Bedrock::Threading::WhenAll<void>::initialize::__l6::<lambda_3496a18835e5c18c61a44274245c5836>
{
  std::shared_ptr<Bedrock::Threading::WhenAll<void> > sharedThis;
};

```

### `BundleSection`
```
struct __cppobj BundleSection : PDPSection
{
};

```

### `BundleSection_vtbl`
```
struct /*VFT*/ BundleSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `BundleUpsellSection`
```
struct __cppobj BundleUpsellSection : PDPSection
{
};

```

### `BundleUpsellSection_vtbl`
```
struct /*VFT*/ BundleUpsellSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `BoolOption_vtbl`
```
struct /*VFT*/ BoolOption_vtbl
{
  void (__fastcall *~Option)(Option *this);
  void (__fastcall *save)(Option *this, std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *load)(Option *this, const Json::Value *);
  void (__fastcall *load)(Option *this, std::map<std::string,std::string> *);
  void (__fastcall *load)(Option *this, const std::string *);
};

```

### `BlockScreenController`
```
struct __cppobj BlockScreenController : ClientInstanceScreenController
{
  BlockActorType mBlockEntityType;
  BlockPos mBlockPos;
  ActorUniqueID mEntityUniqueID;
};

```

### `BlockScreenController_vtbl`
```
struct /*VFT*/ BlockScreenController_vtbl
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

### `BookScreenManager`
```
struct __cppobj __declspec(align(8)) BookScreenManager
{
  Player *mPlayer;
  LecternBlockActor *mLectern;
  int mBookSlot;
  PacketSender *mPacketSender;
  std::unique_ptr<SyncedPhotoView> mPhotoView;
  std::vector<Core::PathBuffer<std::string >> mPickPictures;
  std::vector<Core::PathBuffer<std::string >> mExportFiles;
  unsigned __int64 mCurExportPage;
  bool mEdited;
  bool mIsEdu;
};

```

### `BannerPattern`
```
const struct __cppobj __declspec(align(8)) BannerPattern
{
  unsigned __int8 mID;
  std::vector<std::string> mPattern;
  ItemStack mIngredientItem;
  std::string mName;
  std::string mNameID;
  __int16 mPatternItemType;
  bool mIgnoreAux;
};

```

### `buffer_span<std::string >::iterator`
```
struct __cppobj buffer_span<std::string >::iterator
{
  const std::string *mPtr;
};

```

### `buffer_span_mut<std::string >`
```
struct __cppobj buffer_span_mut<std::string >
{
  std::string *mBegin;
  std::string *mEnd;
};

```

### `buffer_span_mut<int>`
```
struct __cppobj buffer_span_mut<int>
{
  int *mBegin;
  int *mEnd;
};

```

### `buffer_span_mut<bool>`
```
struct __cppobj buffer_span_mut<bool>
{
  bool *mBegin;
  bool *mEnd;
};

```

### `BidirectionalUnorderedMap<enum ItemUseInventoryTransaction::ActionType,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum ItemUseInventoryTransaction::ActionType,std::string >
{
  std::unordered_map<enum ItemUseInventoryTransaction::ActionType,std::string> mRight;
  std::unordered_map<std::string,enum ItemUseInventoryTransaction::ActionType> mLeft;
};

```

### `BlockFilterGroup`
```
struct __cppobj BlockFilterGroup : FilterGroup
{
};

```

### `Boat::Paddle`
```
struct __cppobj Boat::Paddle
{
  int mOldPressTime;
  int mPressTime;
  float mOldRowingTime;
  float mRowingTime;
  float mForce;
};

```

### `Boat`
```
struct __cppobj __declspec(align(8)) Boat : Actor
{
  MovementInterpolator mInterpolation;
  Boat::Paddle mPaddles[2];
  int mOutOfControlTicks;
  float mYRotD;
  float mInvFriction;
  bool mAboveBubbleColumn;
  bool mBubbleColumnDown;
  float mBubbleMultiplier;
  float mBubbleAngle;
  float mBubbleAngleOld;
};

```

### `Boat_vtbl`
```
struct /*VFT*/ Boat_vtbl
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

### `boost_container_new_t`
```
struct __cppobj boost_container_new_t
{
};

```

### `boost_move_new_t`
```
struct __cppobj boost_move_new_t
{
};

```

### `buffer_span<TerrainLayer *>`
```
struct __cppobj buffer_span<TerrainLayer *>
{
  TerrainLayer *const *mBegin;
  TerrainLayer *const *mEnd;
};

```

### `buffer_span<TerrainLayer *>::iterator`
```
struct __cppobj buffer_span<TerrainLayer *>::iterator
{
  TerrainLayer *const *mPtr;
};

```

### `buffer_span_mut<TerrainLayer *>`
```
struct __cppobj buffer_span_mut<TerrainLayer *>
{
  TerrainLayer **mBegin;
  TerrainLayer **mEnd;
};

```

### `BlockUnitCubeDescription`
```
struct __cppobj BlockUnitCubeDescription : BlockComponentDescription
{
};

```

### `BlockUnitCubeDescription_vtbl`
```
struct /*VFT*/ BlockUnitCubeDescription_vtbl
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

### `BlockGeometryDescription`
```
struct __cppobj BlockGeometryDescription : BlockComponentDescription
{
  std::string mGeometryName;
};

```

### `BlockGeometryDescription_vtbl`
```
struct /*VFT*/ BlockGeometryDescription_vtbl
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

### `BlockMaterialInstance`
```
struct __cppobj BlockMaterialInstance
{
  std::string mTextureName;
  std::string mRenderMethod;
  bool mAmbientOcclusion;
  bool mFaceDimming;
  BlockRenderLayer mRenderLayer;
  std::shared_ptr<ClientBlockPipeline::Material const > mMaterial;
};

```

### `BlockMaterialInstancesDescription`
```
struct __cppobj BlockMaterialInstancesDescription : BlockComponentDescription
{
  std::unordered_map<std::string,BlockMaterialInstance> mMaterials;
  std::unordered_map<std::string,std::string> mMaterialMappings;
};

```

### `BlockMaterialInstancesDescription_vtbl`
```
struct /*VFT*/ BlockMaterialInstancesDescription_vtbl
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

### `buffer_span_mut<ClientBlockPipeline::BlockCell>`
```
struct __cppobj buffer_span_mut<ClientBlockPipeline::BlockCell>
{
  ClientBlockPipeline::BlockCell *mBegin;
  ClientBlockPipeline::BlockCell *mEnd;
};

```

### `BlockGraphics::ConstructorToken`
```
struct __cppobj BlockGraphics::ConstructorToken
{
};

```

### `Bedrock::NonOwnerPointer<ClientBlockPipeline::Material const >`
```
struct __cppobj Bedrock::NonOwnerPointer<ClientBlockPipeline::Material const >
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `buffer_span_mut<ClientBlockPipeline::BlockSchematicCell>`
```
struct __cppobj buffer_span_mut<ClientBlockPipeline::BlockSchematicCell>
{
  ClientBlockPipeline::BlockSchematicCell *mBegin;
  ClientBlockPipeline::BlockSchematicCell *mEnd;
};

```

### `buffer_span_mut<ClientBlockPipeline::BlockSchematicCell const >::iterator`
```
struct __cppobj buffer_span_mut<ClientBlockPipeline::BlockSchematicCell const >::iterator
{
  const ClientBlockPipeline::BlockSchematicCell *mPtr;
};

```

### `BlockRotationDescription`
```
struct __cppobj __declspec(align(8)) BlockRotationDescription : BlockComponentDescription
{
  Vec3 mRotation;
};

```

### `BlockRotationDescription_vtbl`
```
struct /*VFT*/ BlockRotationDescription_vtbl
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

### `buffer_span_mut<ClientBlockPipeline::BlockCell const >::iterator`
```
struct __cppobj buffer_span_mut<ClientBlockPipeline::BlockCell const >::iterator
{
  const ClientBlockPipeline::BlockCell *mPtr;
};

```

### `BlockRotationComponent`
```
struct __cppobj BlockRotationComponent
{
  Vec3 mRotation;
};

```

### `Bedrock::Threading::Burst::Details::WorkTarget`
```
struct __cppobj Bedrock::Threading::Burst::Details::WorkTarget
{
  Bedrock::Threading::Burst::Details::WorkTargetItem mPrimary;
  gsl::span<Bedrock::Threading::Burst::Details::WorkTargetItem,-1> mSecondaries;
  std::vector<Bedrock::Threading::Burst::Details::WorkTargetItem> mSecondariesStorage;
};

```

### `Bedrock::Threading::Burst::QueueConfig`
```
struct __cppobj Bedrock::Threading::Burst::QueueConfig
{
  std::string mName;
  unsigned int mPriority;
  Scheduler *mScheduler;
  WorkerPool *mPrimaryWorkerPool;
  std::vector<std::reference_wrapper<WorkerPool>> mSecondaryWorkerPools;
  std::vector<std::thread::id> mAffinities;
};

```

### `Bedrock::Threading::Burst::Strategy::Execution::DefaultExecution`
```
struct __cppobj Bedrock::Threading::Burst::Strategy::Execution::DefaultExecution
{
};

```

### `buffer_span_mut<unsigned char>`
```
struct __cppobj buffer_span_mut<unsigned char>
{
  unsigned __int8 *mBegin;
  unsigned __int8 *mEnd;
};

```

### `bgfx::CallbackI`
```
struct __cppobj bgfx::CallbackI
{
  bgfx::CallbackI_vtbl *__vftable /*VFT*/;
};

```

### `bgfx::CallbackI_vtbl`
```
struct /*VFT*/ bgfx::CallbackI_vtbl
{
  void (__fastcall *~CallbackI)(bgfx::CallbackI *this);
  void (__fastcall *fatal)(bgfx::CallbackI *this, bgfx::Fatal::Enum, const char *);
  void (__fastcall *traceVargs)(bgfx::CallbackI *this, const char *, unsigned __int16, const char *, char *);
  void (__fastcall *profilerBegin)(bgfx::CallbackI *this, const char *, unsigned int, const char *, unsigned __int16);
  void (__fastcall *profilerBeginLiteral)(bgfx::CallbackI *this, const char *, unsigned int, const char *, unsigned __int16);
  void (__fastcall *profilerEnd)(bgfx::CallbackI *this);
  unsigned int (__fastcall *cacheReadSize)(bgfx::CallbackI *this, unsigned __int64);
  bool (__fastcall *cacheRead)(bgfx::CallbackI *this, unsigned __int64, void *, unsigned int);
  void (__fastcall *cacheWrite)(bgfx::CallbackI *this, unsigned __int64, const void *, unsigned int);
  void (__fastcall *screenShot)(bgfx::CallbackI *this, const char *, unsigned int, unsigned int, unsigned int, const void *, unsigned int, bool);
  void (__fastcall *captureBegin)(bgfx::CallbackI *this, unsigned int, unsigned int, unsigned int, bgfx::TextureFormat::Enum, bool);
  void (__fastcall *captureEnd)(bgfx::CallbackI *this);
  void (__fastcall *captureFrame)(bgfx::CallbackI *this, const void *, unsigned int);
  void (__fastcall *parallelForeach)(bgfx::CallbackI *this, void *, const unsigned int, void (__fastcall *)(void *, const unsigned int));
  void (__fastcall *postRenderCommandBuffer)(bgfx::CallbackI *this, void *);
};

```

### `bx::AllocatorI_vtbl`
```
struct /*VFT*/ bx::AllocatorI_vtbl
{
  void (__fastcall *~AllocatorI)(bx::AllocatorI *this);
  void *(__fastcall *realloc)(bx::AllocatorI *this, void *, unsigned __int64, unsigned __int64, const char *, unsigned int);
};

```

### `bgfx::Encoder`
```
struct __cppobj bgfx::Encoder
{
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >
{
  Bedrock::Intrusive::list_base_hook<void> mSentinel;
};

```

### `Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >`
```
struct __cppobj __declspec(align(4)) Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> > : Bedrock::Threading::InstancedThreadLocalBase
{
  std::function<void __cdecl(bgfx::Encoder * *)> mConstructor;
  Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> > mItems;
  std::mutex mMutex;
  unsigned int mKey;
  bool mInitialized;
};

```

### `buffer_span_mut<ClientBlockPipeline::BlockCell>::iterator`
```
struct __cppobj buffer_span_mut<ClientBlockPipeline::BlockCell>::iterator
{
  ClientBlockPipeline::BlockCell *mPtr;
};

```

### `BasaltDeltasMoodSoundPlayer`
```
struct __cppobj BasaltDeltasMoodSoundPlayer
{
};

```

### `BiomeMoodSoundPlayerRegistry`
```
struct __cppobj BiomeMoodSoundPlayerRegistry
{
};

```

### `BITMAPV4HEADER`
```
struct BITMAPV4HEADER
{
  unsigned int bV4Size;
  int bV4Width;
  int bV4Height;
  unsigned __int16 bV4Planes;
  unsigned __int16 bV4BitCount;
  unsigned int bV4V4Compression;
  unsigned int bV4SizeImage;
  int bV4XPelsPerMeter;
  int bV4YPelsPerMeter;
  unsigned int bV4ClrUsed;
  unsigned int bV4ClrImportant;
  unsigned int bV4RedMask;
  unsigned int bV4GreenMask;
  unsigned int bV4BlueMask;
  unsigned int bV4AlphaMask;
  unsigned int bV4CSType;
  tagICEXYZTRIPLE bV4Endpoints;
  unsigned int bV4GammaRed;
  unsigned int bV4GammaGreen;
  unsigned int bV4GammaBlue;
};

```

### `BATTERY_REPORTING_SCALE`
```
struct BATTERY_REPORTING_SCALE
{
  unsigned int Granularity;
  unsigned int Capacity;
};

```

### `Bedrock::Threading::MainProcScope`
```
struct __cppobj Bedrock::Threading::MainProcScope
{
};

```

### `BITMAPV5HEADER`
```
struct BITMAPV5HEADER
{
  unsigned int bV5Size;
  int bV5Width;
  int bV5Height;
  unsigned __int16 bV5Planes;
  unsigned __int16 bV5BitCount;
  unsigned int bV5Compression;
  unsigned int bV5SizeImage;
  int bV5XPelsPerMeter;
  int bV5YPelsPerMeter;
  unsigned int bV5ClrUsed;
  unsigned int bV5ClrImportant;
  unsigned int bV5RedMask;
  unsigned int bV5GreenMask;
  unsigned int bV5BlueMask;
  unsigned int bV5AlphaMask;
  unsigned int bV5CSType;
  tagICEXYZTRIPLE bV5Endpoints;
  unsigned int bV5GammaRed;
  unsigned int bV5GammaGreen;
  unsigned int bV5GammaBlue;
  unsigned int bV5Intent;
  unsigned int bV5ProfileData;
  unsigned int bV5ProfileSize;
  unsigned int bV5Reserved;
};

```

### `BSMINFO`
```
struct BSMINFO
{
  unsigned int cbSize;
  HDESK__ *hdesk;
  HWND__ *hwnd;
  _LUID luid;
};

```

### `buffer_span<RangeIndices>`
```
struct __cppobj buffer_span<RangeIndices>
{
  const RangeIndices *mBegin;
  const RangeIndices *mEnd;
};

```

### `buffer_span<std::vector<RenderChunkQuadInfo> >`
```
struct __cppobj buffer_span<std::vector<RenderChunkQuadInfo> >
{
  const std::vector<RenderChunkQuadInfo> *mBegin;
  const std::vector<RenderChunkQuadInfo> *mEnd;
};

```

### `buffer_span<ActorBlockSyncMessage>`
```
struct __cppobj buffer_span<ActorBlockSyncMessage>
{
  const ActorBlockSyncMessage *mBegin;
  const ActorBlockSyncMessage *mEnd;
};

```

### `buffer_span<BlockActorBlockSyncMessage>`
```
struct __cppobj buffer_span<BlockActorBlockSyncMessage>
{
  const BlockActorBlockSyncMessage *mBegin;
  const BlockActorBlockSyncMessage *mEnd;
};

```

### `Bedrock::IIslandManagerLogger`
```
struct __cppobj Bedrock::IIslandManagerLogger
{
  Bedrock::IIslandManagerLogger_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::IIslandManagerLogger_vtbl`
```
struct /*VFT*/ Bedrock::IIslandManagerLogger_vtbl
{
  void (__fastcall *~IIslandManagerLogger)(Bedrock::IIslandManagerLogger *this);
  void (__fastcall *transitionSignaled)(Bedrock::IIslandManagerLogger *this, Bedrock::IslandTransition);
  void (__fastcall *transitionCompleted)(Bedrock::IIslandManagerLogger *this);
  void (__fastcall *islandUpdate)(Bedrock::IIslandManagerLogger *this, unsigned __int16, std::chrono::duration<__int64,std::ratio<1,1000000000> >);
  void (__fastcall *islandTransition)(Bedrock::IIslandManagerLogger *this, unsigned __int16, Bedrock::IslandTransition, bool, std::chrono::duration<__int64,std::ratio<1,1000000000> >);
};

```

### `Bedrock::NonOwnerPointer<LevelStorageSource>`
```
struct __cppobj Bedrock::NonOwnerPointer<LevelStorageSource>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::Signal<MinecraftGame::ServerInitCompleted>`
```
struct __cppobj Bedrock::Signal<MinecraftGame::ServerInitCompleted> : Bedrock::SignalBase
{
};

```

### `Bedrock::Signal<MinecraftGame::ServerInitCompleted>_vtbl`
```
struct /*VFT*/ Bedrock::Signal<MinecraftGame::ServerInitCompleted>_vtbl
{
  void (__fastcall *~SignalBase)(Bedrock::SignalBase *this);
  bool (__fastcall *invokeHandler)(Bedrock::SignalBase *this, const unsigned __int16 *);
};

```

### `Bedrock::Signal<MinecraftGame::ServerInitCompleted>::SignalHandlerMap`
```
struct __cppobj Bedrock::Signal<MinecraftGame::ServerInitCompleted>::SignalHandlerMap : Bedrock::ISignalHandlerMap
{
  std::map<unsigned short,std::function<void __cdecl(std::shared_ptr<MinecraftGame::ServerInitCompleted>)>> mMap;
};

```

### `Bedrock::Signal<MinecraftGame::ServerInitCompleted>::SignalHandlerMap_vtbl`
```
struct /*VFT*/ Bedrock::Signal<MinecraftGame::ServerInitCompleted>::SignalHandlerMap_vtbl
{
  void (__fastcall *~ISignalHandlerMap)(Bedrock::ISignalHandlerMap *this);
  bool (__fastcall *remove)(Bedrock::ISignalHandlerMap *this, const unsigned __int16 *);
};

```

### `Bedrock::SignalRoute<MinecraftGame::ServerInitCompleted>`
```
struct __cppobj Bedrock::SignalRoute<MinecraftGame::ServerInitCompleted> : Bedrock::SignalRouteBase
{
};

```

### `BobBehavior`
```
struct __cppobj BobBehavior : CameraBehavior<BobBehavior>
{
};

```

### `BobBehavior_vtbl`
```
struct /*VFT*/ BobBehavior_vtbl
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

### `BedBlock`
```
struct __cppobj BedBlock : BlockLegacy
{
};

```

### `BedBlock_vtbl`
```
struct /*VFT*/ BedBlock_vtbl
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

### `BobBehaviorLoader`
```
struct __cppobj BobBehaviorLoader : CameraBehaviorLoader
{
};

```

### `BobBehaviorLoader_vtbl`
```
struct /*VFT*/ BobBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `buffer_span<enum Flip>`
```
struct __cppobj buffer_span<enum Flip>
{
  const Flip *mBegin;
  const Flip *mEnd;
};

```

### `Bedrock::Threading::AsyncDeferredResultT<std::string >`
```
struct __cppobj Bedrock::Threading::AsyncDeferredResultT<std::string > : Bedrock::Threading::IAsyncResult<std::string >
{
  std::mutex mLock;
  Bedrock::Threading::AsyncDeferredResultT<std::string >::DelayStatus mStatus;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::string > const &)>> mComplete;
  std::optional<std::string > mResult;
};

```

### `Bedrock::Threading::AsyncDeferredResultT<std::string >_vtbl`
```
struct /*VFT*/ Bedrock::Threading::AsyncDeferredResultT<std::string >_vtbl
{
  void (__fastcall *~IAsyncResult<std::string >)(Bedrock::Threading::IAsyncResult<std::string > *this);
  Bedrock::Threading::AsyncStatus (__fastcall *getStatus)(Bedrock::Threading::IAsyncResult<std::string > *this);
  std::error_code *(__fastcall *getError)(Bedrock::Threading::IAsyncResult<std::string > *this, std::error_code *result);
  std::exception_ptr *(__fastcall *getException)(Bedrock::Threading::IAsyncResult<std::string > *this, std::exception_ptr *result);
  std::string *(__fastcall *getResult)(Bedrock::Threading::IAsyncResult<std::string > *this, std::string *result);
  void (__fastcall *cancel)(Bedrock::Threading::IAsyncResult<std::string > *this);
  void (__fastcall *addOnComplete)(Bedrock::Threading::IAsyncResult<std::string > *this, std::function<void __cdecl(Bedrock::Threading::IAsyncResult<std::string > const &)>);
};

```

### `buffer_span<unsigned __int64>::iterator`
```
struct __cppobj buffer_span<unsigned __int64>::iterator
{
  const unsigned __int64 *mPtr;
};

```

### `buffer_span<unsigned __int64>`
```
struct __cppobj buffer_span<unsigned __int64>
{
  const unsigned __int64 *mBegin;
  const unsigned __int64 *mEnd;
};

```

### `ByValueLevelDataOverride`
```
struct __cppobj ByValueLevelDataOverride : ILevelDataOverride
{
  std::function<void __cdecl(gsl::basic_string_span<char const ,-1>)> mOnValueChanged;
  LevelDataOverrideValues mValues;
};

```

### `ByValueLevelDataOverride_vtbl`
```
struct /*VFT*/ ByValueLevelDataOverride_vtbl
{
  void (__fastcall *~ILevelDataOverride)(ILevelDataOverride *this);
  void (__fastcall *applyTo)(ILevelDataOverride *this, LevelData *);
};

```

### `BlockGeometry::Rotation`
```
struct __cppobj BlockGeometry::Rotation
{
  glm::tvec3<float,0> origin;
  _BYTE axis[4];
  float angle;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<PerfTimer,std::allocator<PerfTimer> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<PerfTimer,std::allocator<PerfTimer> >
{
  PerfTimer *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<PerfTimer,std::allocator<PerfTimer> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<PerfTimer,std::allocator<PerfTimer> > : Bedrock::Threading::ThreadLocalObjectImplementation<PerfTimer,std::allocator<PerfTimer> >
{
  std::function<void __cdecl(PerfTimer *)> mConstructor;
};

```

### `BigEndianStringByteOutput`
```
struct __cppobj BigEndianStringByteOutput : StringByteOutput
{
};

```

### `BigEndianStringByteOutput_vtbl`
```
struct /*VFT*/ BigEndianStringByteOutput_vtbl
{
  void (__fastcall *~IDataOutput)(IDataOutput *this);
  void (__fastcall *writeString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeLongString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeFloat)(IDataOutput *this, float);
  void (__fastcall *writeDouble)(IDataOutput *this, long double);
  void (__fastcall *writeByte)(IDataOutput *this, char);
  void (__fastcall *writeShort)(IDataOutput *this, __int16);
  void (__fastcall *writeInt)(IDataOutput *this, int);
  void (__fastcall *writeLongLong)(IDataOutput *this, __int64);
  void (__fastcall *writeBytes)(IDataOutput *this, const void *, unsigned __int64);
  bool (__fastcall *isOk)(IDataOutput *this);
};

```

### `BigEndianStringByteInput_vtbl`
```
struct /*VFT*/ BigEndianStringByteInput_vtbl
{
  void (__fastcall *~IDataInput)(IDataInput *this);
  std::string *(__fastcall *readString)(IDataInput *this, std::string *result);
  std::string *(__fastcall *readLongString)(IDataInput *this, std::string *result);
  float (__fastcall *readFloat)(IDataInput *this);
  long double (__fastcall *readDouble)(IDataInput *this);
  char (__fastcall *readByte)(IDataInput *this);
  __int16 (__fastcall *readShort)(IDataInput *this);
  int (__fastcall *readInt)(IDataInput *this);
  __int64 (__fastcall *readLongLong)(IDataInput *this);
  bool (__fastcall *readBytes)(IDataInput *this, void *, unsigned __int64);
  unsigned __int64 (__fastcall *numBytesLeft)(IDataInput *this);
  bool (__fastcall *isOk)(IDataInput *this);
  bool (__fastcall *seek)(IDataInput *this, unsigned __int64);
  bool (__fastcall *readBigEndianBytes)(BigEndianStringByteInput *this, void *, unsigned __int64);
};

```

### `BlockLegacyPtr`
```
struct __cppobj BlockLegacyPtr
{
  const BlockLegacy *mBlockLegacy;
};

```

### `Bedrock::Memory::IMemoryAllocator_vtbl`
```
struct /*VFT*/ Bedrock::Memory::IMemoryAllocator_vtbl
{
  void (__fastcall *~IMemoryAllocator)(Bedrock::Memory::IMemoryAllocator *this);
  void *(__fastcall *allocate)(Bedrock::Memory::IMemoryAllocator *this, const unsigned __int64);
  void (__fastcall *release)(Bedrock::Memory::IMemoryAllocator *this, void *);
  void *(__fastcall *realloc)(Bedrock::Memory::IMemoryAllocator *this, void *, const unsigned __int64);
  void *(__fastcall *alignedAllocate)(Bedrock::Memory::IMemoryAllocator *this, const unsigned __int64, const unsigned __int64);
  void (__fastcall *alignedRelease)(Bedrock::Memory::IMemoryAllocator *this, void *);
  void (__fastcall *logCurrentState)(Bedrock::Memory::IMemoryAllocator *this);
};

```

### `Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item`
```
struct __cppobj Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item : Bedrock::Intrusive::list_base_hook<void>
{
  std::_Align_type<double,688> mData;
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>
{
  Bedrock::Intrusive::list_base_hook<void> *mHook;
};

```

### `BaseStage`
```
struct __cppobj BaseStage : std::enable_shared_from_this<BaseStage>
{
  BaseStage_vtbl *__vftable /*VFT*/;
  LoginStateMachine *mMachine;
  std::atomic<enum eLoginStage> mStageType;
  std::atomic<enum eStageStatus> mStatus;
  EasyThread mThread;
};

```

### `BaseStage_vtbl`
```
struct /*VFT*/ BaseStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `BasicTestProfileStats`
```
struct __cppobj BasicTestProfileStats : Bedrock::EnableNonOwnerReferences
{
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mMinecraftGameUpdateTime;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mMinecraftGameEndFrameTime;
};

```

### `ButtonComponent`
```
struct __cppobj __declspec(align(8)) ButtonComponent : UIComponent
{
  std::weak_ptr<UIControl> mDefaultStateControl;
  std::weak_ptr<UIControl> mHoverStateControl;
  std::weak_ptr<UIControl> mPressedStateControl;
  std::weak_ptr<UIControl> mLockedStateControl;
  bool mPressed;
  bool mHover;
  bool mConsumeEvents;
};

```

### `ButtonComponent_vtbl`
```
struct /*VFT*/ ButtonComponent_vtbl
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

### `BackgroundRenderer`
```
struct __cppobj BackgroundRenderer : MinecraftUICustomRenderer
{
};

```

### `BackgroundRenderer_vtbl`
```
struct /*VFT*/ BackgroundRenderer_vtbl
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

### `BannerPatternRenderer::BannerPatternTextureInfo`
```
struct __cppobj BannerPatternRenderer::BannerPatternTextureInfo
{
  mce::TexturePtr mTexture;
  glm::tvec2<float,0> mUV;
  glm::tvec2<float,0> mUVScale;
};

```

### `BannerPatternRenderer`
```
struct __cppobj BannerPatternRenderer : MinecraftUICustomRenderer, ActorShaderManager
{
  bool mHasLoadedTextures;
  std::vector<BannerPatternRenderer::BannerPatternTextureInfo> mTextures;
  std::vector<mce::Color> mColors;
};

```

### `BannerPatternRenderer_vtbl`
```
struct /*VFT*/ BannerPatternRenderer_vtbl
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

### `BohrModelRenderer::State`
```
struct __cppobj BohrModelRenderer::State
{
  int mElectrons;
  int mProtons;
  int mNeutrons;
  int mRings;
  float mScale;
  Vec2 mTopLeft;
  Vec2 mBottomRight;
};

```

### `BohrModelRenderer::Renderable`
```
struct __cppobj BohrModelRenderer::Renderable
{
  std::unique_ptr<mce::Mesh> mMesh;
  mce::TexturePtr mTexture;
};

```

### `BohrModelRenderer`
```
struct __cppobj BohrModelRenderer : MinecraftUICustomRenderer
{
  std::unique_ptr<Stopwatch> mStopwatch;
  BohrModelRenderer::State mCurState;
  BohrModelRenderer::State mLastState;
  float mCenterRadius;
  float mRingDistance;
  float mRingThickness;
  float mMargin;
  float mElectronSize;
  float mClumpRadius;
  unsigned int mProtonSeed;
  unsigned int mNeutronSeed;
  mce::TexturePtr mRingTexture;
  mce::TexturePtr mProtonTexture;
  mce::TexturePtr mElectronTexture;
  mce::TexturePtr mNeutronTexture;
  std::vector<BohrModelRenderer::Renderable> mRenderables;
};

```

### `BohrModelRenderer_vtbl`
```
struct /*VFT*/ BohrModelRenderer_vtbl
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

### `ButtonSoundEventConditions`
```
struct __declspec(align(4)) ButtonSoundEventConditions
{
  unsigned int id;
  __int8 matchSpecificButtonId : 1;
};

```

### `BitmapFont`
```
struct __cppobj BitmapFont : Font
{
  Core::PathBuffer<std::string > mAsciiFontName;
  Core::PathBuffer<std::string > mUnicodeFontName;
  float mCharWidths[256];
  std::shared_ptr<mce::Image> mBitmapFontImage;
  std::unordered_map<int,float> mUnicodeWidths;
  std::unordered_map<int,float> mUnicodeOffsets;
  std::unordered_map<int,float> mUnicodePageGlyphWidths;
  std::unordered_set<int> mSheetScannedForWidthsAndOffsets;
  std::recursive_mutex mMutex;
};

```

### `BitmapFont_vtbl`
```
struct /*VFT*/ BitmapFont_vtbl
{
  void (__fastcall *~Font)(Font *this);
  float (__fastcall *getCharWidth)(Font *this, int);
  void (__fastcall *switchFontsource)(Font *this, const Core::Path *, const Core::Path *);
  std::pair<Core::PathBuffer<std::string > const &,Core::PathBuffer<std::string > const &> *(__fastcall *getFontSources)(Font *this, std::pair<Core::PathBuffer<std::string > const &,Core::PathBuffer<std::string > const &> *result);
  void (__fastcall *fetchPage)(Font *this, int);
  Font::SheetId *(__fastcall *getSheet)(Font *this, Font::SheetId *result, int, int *, bool);
  bool (__fastcall *supportsChar)(Font *this, const int *);
  bool (__fastcall *_supportsShadowInSingleDraw)(Font *this);
  int (__fastcall *getLineLength)(Font *this, const std::string *, float, bool);
  float (__fastcall *getWrapHeight)(Font *this);
  float (__fastcall *getScaleFactor)(Font *this);
  Vec2 *(__fastcall *getTranslationFactor)(Font *this, Vec2 *result);
  bool (__fastcall *isScreenPixelAligned)(Font *this);
  bool (__fastcall *materialCanBeOverridden)(Font *this);
  void (__fastcall *uploadTextureToGPU)(Font *this);
  void (__fastcall *setTextConstantsInScreenContext)(Font *this, ScreenContext *, const Font::SheetId *, float, const mce::Color *, bool);
  float (__fastcall *_getCharWidth)(Font *this, int, bool);
  bool (__fastcall *_isIconPage)(Font *this, const Font::SheetId *);
  mce::Font::Type (__fastcall *getType)(Font *this, const Font::SheetId *);
  std::optional<mce::Font::RenderingParameters> *(__fastcall *tryGetRenderingParameters)(Font *this, std::optional<mce::Font::RenderingParameters> *result, const ScreenContext *, const Font::SheetId *, float, const mce::Color *, bool, const mce::Color *, const glm::tvec2<float,0> *);
  void (__fastcall *drawCached)(Font *this, ScreenContext *, const std::string *, float, float, const mce::Color *, const mce::Color *, const glm::tvec2<float,0> *, bool, bool, mce::MaterialPtr *, int, bool, float, const mce::Color *);
  void (__fastcall *onAppSuspended)(Font *this);
  void (__fastcall *onDeviceLost)(Font *this);
  void (__fastcall *reloadFontTextures)(Font *this, ResourceLoadManager *, bool);
  bool (__fastcall *isReloadingTextures)(Font *this);
  void (__fastcall *unloadTextures)(Font *this);
  void (__fastcall *_scanUnicodeCharacterSize)(Font *this, int, const Font::SheetId *, bool);
  bool (__fastcall *isSheetMatch)(Font *this, const Font::SheetId *);
  bool (__fastcall *_containsWideChar)(Font *this, const std::string *);
  float (__fastcall *_buildChar)(Font *this, std::vector<Font::GlyphQuad> *, int, const mce::Color *, bool, float, float, bool);
  ResourceLocation *(__fastcall *_getFontSheetLocation)(Font *this, ResourceLocation *result, const Font::SheetId *, bool);
  const mce::MaterialPtr *(__fastcall *getMaterial)(Font *this, const Font::SheetId *, bool);
  void (__fastcall *flushQueuedImageUploads)(Font *this);
  void (__fastcall *onLanguageChanged)(Font *this, const std::string *);
  void (__fastcall *loadFontData)(Font *this, bool);
  int (__fastcall *_getReplacementCharacter)(Font *this);
  Core::PathBuffer<std::string > *(__fastcall *getUnicodeFontNameWithPage)(BitmapFont *this, Core::PathBuffer<std::string > *result, const Core::Path *, const unsigned __int8);
};

```

### `buffer_span<unsigned int>::iterator`
```
struct __cppobj buffer_span<unsigned int>::iterator
{
  const unsigned int *mPtr;
};

```

### `buffer_span_mut<unsigned int>`
```
struct __cppobj buffer_span_mut<unsigned int>
{
  unsigned int *mBegin;
  unsigned int *mEnd;
};

```

### `ButtonEdge`
```
struct __cppobj ButtonEdge
{
  std::function<bool __cdecl(unsigned int,enum ButtonEventType,std::string const &,int)> mRequirement;
  _BYTE mTargetNode[4];
  int mPriority;
};

```

### `BookScreenController`
```
struct __cppobj BookScreenController : ClientInstanceScreenController
{
  std::unique_ptr<BookScreenManager> mBookScreenManager;
  const bool mEditable;
  bool mEditingLeft;
  bool mEditingRight;
  std::array<bool,2> mPageHasCursor;
  std::vector<PageContent> mPages;
  int mCurrentPage;
  int mCurrentPageIndex;
  std::string mTitle;
  std::string mAuthor;
  std::string mAuthorXUID;
  BookScreenController::BookView mCurrentView;
  bool mForceUIRefresh;
  int mPickPageIndex;
  std::string mPageBlockedText;
};

```

### `BookScreenController_vtbl`
```
struct /*VFT*/ BookScreenController_vtbl
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

### `buffer_span<gsl::basic_string_span<char const ,-1> >::iterator`
```
struct __cppobj buffer_span<gsl::basic_string_span<char const ,-1> >::iterator
{
  const gsl::basic_string_span<char const ,-1> *mPtr;
};

```

### `buffer_span<gsl::basic_string_span<char const ,-1> >`
```
struct __cppobj buffer_span<gsl::basic_string_span<char const ,-1> >
{
  const gsl::basic_string_span<char const ,-1> *mBegin;
  const gsl::basic_string_span<char const ,-1> *mEnd;
};

```

### `BrazeScreenController`
```
struct __cppobj __declspec(align(8)) BrazeScreenController : MinecraftScreenController
{
  bool mDirty;
};

```

### `BrazeScreenController_vtbl`
```
struct /*VFT*/ BrazeScreenController_vtbl
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

### `BrewingStandScreenControllerProxyCallbacks`
```
struct __cppobj BrewingStandScreenControllerProxyCallbacks
{
  std::function<bool __cdecl(int &,int &,int)> mIsFinished;
};

```

### `BrewingStandScreenControllerProxyCallbacks::<lambda_dca25c3eb6c965db2860fcf8aff0badd>`
```
struct __cppobj BrewingStandScreenControllerProxyCallbacks::<lambda_dca25c3eb6c965db2860fcf8aff0badd>
{
};

```

### `BrewingStandScreenControllerProxy`
```
struct __cppobj BrewingStandScreenControllerProxy : ScreenControllerProxy
{
  const BrewingStandScreenControllerProxyCallbacks mCallbacks;
};

```

### `BrewingStandScreenControllerProxy_vtbl`
```
struct /*VFT*/ BrewingStandScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `BundlePurchaseWarningScreenController`
```
struct __cppobj BundlePurchaseWarningScreenController : StoreBaseScreenController
{
  const StoreCatalogItem *mCatalogItem;
  const OfferCollectionComponent *mBundleCollection;
  std::function<void __cdecl(void)> mOnPurchaseCallback;
  std::vector<StoreCatalogItem *> mOwnedList;
  std::vector<StoreCatalogItem *> mUnownedList;
  std::shared_ptr<bool> mExistenceTracker;
};

```

### `BundlePurchaseWarningScreenController_vtbl`
```
struct /*VFT*/ BundlePurchaseWarningScreenController_vtbl
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

### `BrazeScreenController::_registerEventHandlers::__l2::<lambda_6ee0a4037e32ed239751915bc2fb9143>`
```
struct __cppobj BrazeScreenController::_registerEventHandlers::__l2::<lambda_6ee0a4037e32ed239751915bc2fb9143>
{
  const std::string button1Uri;
  BrazeScreenController *const __this;
};

```

### `BrazeScreenController::_registerEventHandlers::__l2::<lambda_d538ff3b0a3e0bc3a1dc8e0775e63e4a>`
```
struct __cppobj BrazeScreenController::_registerEventHandlers::__l2::<lambda_d538ff3b0a3e0bc3a1dc8e0775e63e4a>
{
  const std::string button0Uri;
  BrazeScreenController *const __this;
};

```

### `BrazeScreenController::_registerBindings::__l2::<lambda_5aee90bcfa1e5a70bf0ca95c9575d189>`
```
struct __cppobj BrazeScreenController::_registerBindings::__l2::<lambda_5aee90bcfa1e5a70bf0ca95c9575d189>
{
  const std::string button1Text;
};

```

### `BrazeScreenController::_registerBindings::__l2::<lambda_e13d728b79c79e1383c5f4763f2f3684>`
```
struct __cppobj BrazeScreenController::_registerBindings::__l2::<lambda_e13d728b79c79e1383c5f4763f2f3684>
{
  const std::string button0Text;
};

```

### `BrazeScreenController::_registerBindings::__l2::<lambda_5a407d611f31f08f56278e1901254b13>`
```
struct __cppobj BrazeScreenController::_registerBindings::__l2::<lambda_5a407d611f31f08f56278e1901254b13>
{
  const std::string body;
};

```

### `BrazeScreenController::_registerBindings::__l2::<lambda_933ebebca03896adf11e9108e028ce0c>`
```
struct __cppobj BrazeScreenController::_registerBindings::__l2::<lambda_933ebebca03896adf11e9108e028ce0c>
{
  const std::string title;
};

```

### `BrazeScreenController::{ctor}::__l2::<lambda_1d27d0a8647f7a806eb7e511f394dade>`
```
struct __cppobj BrazeScreenController::{ctor}::__l2::<lambda_1d27d0a8647f7a806eb7e511f394dade>
{
  BrazeScreenController *const __this;
};

```

### `BrazeScreenController::{ctor}::__l2::<lambda_1d27d0a8647f7a806eb7e511f394dade>::()::__l2::<lambda_f8252f6da819418395269bd8d455fd62>`
```
struct __cppobj BrazeScreenController::{ctor}::__l2::<lambda_1d27d0a8647f7a806eb7e511f394dade>::()::__l2::<lambda_f8252f6da819418395269bd8d455fd62>
{
  const Core::Path imagePath;
};

```

### `BookScreenController::_tickExport::__l11::<lambda_cbe2da03d3218249e5c877e06cf3bb8f>`
```
struct __cppobj BookScreenController::_tickExport::__l11::<lambda_cbe2da03d3218249e5c877e06cf3bb8f>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_tickExport::__l8::<lambda_3ef49f4f5b7ca55f4c47ba66d73c6ba7>`
```
struct __cppobj BookScreenController::_tickExport::__l8::<lambda_3ef49f4f5b7ca55f4c47ba66d73c6ba7>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_signBook::__l2::<lambda_56a585e9f725b0ae8749565ca4ee0752>`
```
struct __cppobj BookScreenController::_signBook::__l2::<lambda_56a585e9f725b0ae8749565ca4ee0752>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_setPageText::__l2::<lambda_b7d07d847fcccd5b27285171e4d6a221>`
```
struct __cppobj BookScreenController::_setPageText::__l2::<lambda_b7d07d847fcccd5b27285171e4d6a221>
{
  const std::string *text;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_2c23570ba6b46212b820e69e06fa8f40>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_2c23570ba6b46212b820e69e06fa8f40>
{
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_6668922cc3a1c4f2b6c454708a8d6e31>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_6668922cc3a1c4f2b6c454708a8d6e31>
{
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_38669daa8999fedfe92008e33cbf3bcd>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_38669daa8999fedfe92008e33cbf3bcd>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_17139683e7ad7e9fef391f4b92f4bb86>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_17139683e7ad7e9fef391f4b92f4bb86>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_d3e052e72319cb8cf248fff03a1459ee>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_d3e052e72319cb8cf248fff03a1459ee>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_da3023e0ea5e8dc27cbbb8a1316a504e>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_da3023e0ea5e8dc27cbbb8a1316a504e>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_9c7943b6d7d49a43eb525e7cb04bc37d>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_9c7943b6d7d49a43eb525e7cb04bc37d>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_0a931edafd053fc993aa5a4a107548e5>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_0a931edafd053fc993aa5a4a107548e5>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_1eb31ca0e1010a327ecea190879f37e2>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_1eb31ca0e1010a327ecea190879f37e2>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_f98214ab71487913885f6e2817a6ff8e>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_f98214ab71487913885f6e2817a6ff8e>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_2f08e915bcc85063e264a2d5a8ca9c6b>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_2f08e915bcc85063e264a2d5a8ca9c6b>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_4b51d874acfcd92297d19b75e40fd9a7>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_4b51d874acfcd92297d19b75e40fd9a7>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_449d7670077fabf8054ad28d5c9c4859>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_449d7670077fabf8054ad28d5c9c4859>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_7fdad6c089186003b5ba72d7dceb6ae4>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_7fdad6c089186003b5ba72d7dceb6ae4>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_97b35f1f3f292a323b4a65ae99954970>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_97b35f1f3f292a323b4a65ae99954970>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_b856e9944b209f0f2c4dd50065e04395>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_b856e9944b209f0f2c4dd50065e04395>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_a900bd39ae590f113754eed6b73cda90>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_a900bd39ae590f113754eed6b73cda90>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_b85a78236e3c5cf59d6b384bb7df9429>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_b85a78236e3c5cf59d6b384bb7df9429>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_32e3b98b63f8b1f26c302f98d57d4448>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_32e3b98b63f8b1f26c302f98d57d4448>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_0e1bf8ad4c409c2c8f875ebf2b09a5d4>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_0e1bf8ad4c409c2c8f875ebf2b09a5d4>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_32d9fff5156d1fde6cf6d921108708e6>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_32d9fff5156d1fde6cf6d921108708e6>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_a42146ef4881c0299d2772c8e0c6ca84>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_a42146ef4881c0299d2772c8e0c6ca84>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_6e472ed66f0c53546a0b144ad8848394>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_6e472ed66f0c53546a0b144ad8848394>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_980f57c58b056dbacc17eb339c26fd07>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_980f57c58b056dbacc17eb339c26fd07>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_40ac37c21938dd767fee8bba914bc9d6>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_40ac37c21938dd767fee8bba914bc9d6>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_8960f4c6aeaa118d8afd8f231c524958>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_8960f4c6aeaa118d8afd8f231c524958>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_919f86313deae95265162bc008fa7c8e>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_919f86313deae95265162bc008fa7c8e>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerBindings::__l2::<lambda_94fc43a149aec474366caab8ebbaa33e>`
```
struct __cppobj BookScreenController::_registerBindings::__l2::<lambda_94fc43a149aec474366caab8ebbaa33e>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_4ed091f1da30f81f28e5f550d66abd14>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_4ed091f1da30f81f28e5f550d66abd14>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_11b65ada601cf3200a60738aa12b400e>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_11b65ada601cf3200a60738aa12b400e>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_11b65ada601cf3200a60738aa12b400e>::()::__l2::<lambda_7828bb44b1fcdb96306da87dbc474e31>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_11b65ada601cf3200a60738aa12b400e>::()::__l2::<lambda_7828bb44b1fcdb96306da87dbc474e31>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_68512987264b3c9ae16ff4df9ef66b87>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_68512987264b3c9ae16ff4df9ef66b87>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_6878a4398b0ea544de0b5b508592c192>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_6878a4398b0ea544de0b5b508592c192>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_8a5705a75d9d6e43000560d6acc19a40>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_8a5705a75d9d6e43000560d6acc19a40>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_143f085f5ac4c42310864b83a7e3a178>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_143f085f5ac4c42310864b83a7e3a178>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_542194880356dec9682c663ff3c895b3>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_542194880356dec9682c663ff3c895b3>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_b18ca6ef114d4011b6898690f5836e2c>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_b18ca6ef114d4011b6898690f5836e2c>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_7e99b0c889ea7689486d9ad304660aee>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_7e99b0c889ea7689486d9ad304660aee>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_4236224130f9a47f1a840738f1fe0844>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_4236224130f9a47f1a840738f1fe0844>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_7f071518a46576f69e99147875a86af2>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_7f071518a46576f69e99147875a86af2>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_62c8e8496dd68fb615d2007634be761c>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_62c8e8496dd68fb615d2007634be761c>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_64f62a0f32ed2be12cfd4f4d5bc5f8a4>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_64f62a0f32ed2be12cfd4f4d5bc5f8a4>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_2d25936ddb4171b92ede1cddfdeb15a6>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_2d25936ddb4171b92ede1cddfdeb15a6>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_4faeb6cb49aaaee4cc496b671d03ef9f>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_4faeb6cb49aaaee4cc496b671d03ef9f>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_e2683272ca8caea2d4b75821a48502a3>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_e2683272ca8caea2d4b75821a48502a3>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_83945d1606f73308a0decdf366174f80>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_83945d1606f73308a0decdf366174f80>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_d3c3eb04e7f28b0c8c70d2906a31e60d>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_d3c3eb04e7f28b0c8c70d2906a31e60d>
{
  BookScreenController *const __this;
};

```

### `BookScreenController::_registerEventHandlers::__l2::<lambda_4844ca985ad444ebd27c9087c989b554>`
```
struct __cppobj BookScreenController::_registerEventHandlers::__l2::<lambda_4844ca985ad444ebd27c9087c989b554>
{
  BookScreenController *const __this;
};

```

### `BasicToggle`
```
struct __cppobj BasicToggle
{
  bool mIsOn;
  bool mStateChanged;
  bool mFirstStateChange;
};

```

### `buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >::iterator`
```
struct __cppobj buffer_span<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >::iterator
{
  const std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > *mPtr;
};

```

### `buffer_span_mut<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >`
```
struct __cppobj buffer_span_mut<std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > >
{
  std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > *mBegin;
  std::pair<gsl::basic_string_span<char const ,-1>,gsl::basic_string_span<char const ,-1> > *mEnd;
};

```

### `BucketItem`
```
struct __cppobj BucketItem : Item
{
  _BYTE mFillType[2];
  TextureUVCoordinateSet m_uvBucket;
};

```

### `BeehiveBlock`
```
struct __cppobj BeehiveBlock : FaceDirectionalActorBlock
{
};

```

### `BeehiveBlock_vtbl`
```
struct /*VFT*/ BeehiveBlock_vtbl
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

### `BeehiveBlockActor::Occupant`
```
struct __cppobj __declspec(align(8)) BeehiveBlockActor::Occupant
{
  ActorDefinitionIdentifier mActorIdentifier;
  CompoundTag mSaveData;
  unsigned int mTicksLeftToStay;
};

```

### `BeehiveBlockActor`
```
struct __cppobj __declspec(align(8)) BeehiveBlockActor : BlockActor
{
  std::vector<BeehiveBlockActor::Occupant> mOccupants;
  bool mShouldSpawnBees;
};

```

### `BeehiveBlockActor_vtbl`
```
struct /*VFT*/ BeehiveBlockActor_vtbl
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

### `BlockCommandOrigin`
```
struct __cppobj __declspec(align(8)) BlockCommandOrigin : CommandOrigin
{
  BlockSource *mRegion;
  BlockPos mPosition;
};

```

### `BlockCommandOrigin_vtbl`
```
struct /*VFT*/ BlockCommandOrigin_vtbl
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
  CommandBlockActor *(__fastcall *getBlockEntity)(BlockCommandOrigin *this);
  BaseCommandBlock *(__fastcall *getBaseCommandBlock)(BlockCommandOrigin *this);
};

```

### `BlockPtr`
```
struct __cppobj BlockPtr
{
  const Block *mBlock;
};

```

### `BalloonItem`
```
struct __cppobj BalloonItem : ChemistryItem
{
};

```

### `BlockPlanterItem`
```
struct __cppobj __declspec(align(8)) BlockPlanterItem : Item
{
  const Block *mBlock;
  const bool mUseBlockDescription;
};

```

### `Bedrock::Threading::asVoidTask::__l2::<lambda_d7f1027c792d450a6d889ec9715c5110>`
```
struct __cppobj Bedrock::Threading::asVoidTask::__l2::<lambda_d7f1027c792d450a6d889ec9715c5110>
{
  std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> > wrapper;
};

```

### `BehaviorActionMapper`
```
struct __cppobj BehaviorActionMapper : InputDeviceMapper
{
  std::unordered_map<int,std::unordered_multimap<int,unsigned int>> mTestAutoActionToButtonIdMappings;
};

```

### `BehaviorActionMapper_vtbl`
```
struct /*VFT*/ BehaviorActionMapper_vtbl
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

### `BalloonModel`
```
struct __cppobj BalloonModel : Model
{
  std::unique_ptr<std::vector<ModelPart>> mParts;
  std::unique_ptr<mce::MaterialPtr> mDefaultMaterial;
};

```

### `BalloonModel_vtbl`
```
struct /*VFT*/ BalloonModel_vtbl
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

### `BannerModel`
```
struct __cppobj BannerModel : Model
{
  ModelPart mFlag;
  ModelPart mPole;
  ModelPart mLongPole;
  ModelPart mBar;
  ModelPart mForcedMatFlag;
  ModelPart mForcedMatPole;
  ModelPart mForcedMatBar;
  mce::MaterialPtr mBannerMaterial;
  mce::MaterialPtr mBannerPoleMaterial;
};

```

### `BannerModel_vtbl`
```
struct /*VFT*/ BannerModel_vtbl
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

### `BedModel`
```
struct __cppobj BedModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mBody;
  ModelPart mLeg0;
  ModelPart mLeg1;
  ModelPart mLeg2;
  ModelPart mLeg3;
};

```

### `BedModel_vtbl`
```
struct /*VFT*/ BedModel_vtbl
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

### `BellModel`
```
struct __cppobj BellModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mBellBody;
  ModelPart mBellBase;
};

```

### `BellModel_vtbl`
```
struct /*VFT*/ BellModel_vtbl
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

### `BoatModel`
```
struct __cppobj BoatModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mBottom;
  ModelPart mBack;
  ModelPart mFront;
  ModelPart mLeft;
  ModelPart mRight;
  ModelPart mLeftPaddle;
  ModelPart mRightPaddle;
};

```

### `BoatModel_vtbl`
```
struct /*VFT*/ BoatModel_vtbl
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

### `Bedrock::Threading::asVoidTask::__l2::<lambda_ed7b5341cd28450411fe7d5e3644acd3>`
```
struct __cppobj Bedrock::Threading::asVoidTask::__l2::<lambda_ed7b5341cd28450411fe7d5e3644acd3>
{
  std::shared_ptr<Bedrock::Threading::AsyncDeferredResultT<void> > wrapper;
};

```

### `BlockDefinitionGroup::BlockResource`
```
struct __cppobj BlockDefinitionGroup::BlockResource
{
  SemVersion mVersion;
  BlockDescription mDescription;
  std::string mResourcePackLocation;
  std::string mResourceFileLocation;
  Json::Value mRoot;
};

```

### `BannerRecipes`
```
struct __cppobj BannerRecipes
{
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<LevelStorageWriteBatch,std::allocator<LevelStorageWriteBatch> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<LevelStorageWriteBatch,std::allocator<LevelStorageWriteBatch> >
{
  LevelStorageWriteBatch *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<LevelStorageWriteBatch,std::allocator<LevelStorageWriteBatch> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<LevelStorageWriteBatch,std::allocator<LevelStorageWriteBatch> > : Bedrock::Threading::ThreadLocalObjectImplementation<LevelStorageWriteBatch,std::allocator<LevelStorageWriteBatch> >
{
  std::function<void __cdecl(LevelStorageWriteBatch *)> mConstructor;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<std::string,std::allocator<std::string > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<std::string,std::allocator<std::string > >
{
  std::string *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<std::string,std::allocator<std::string > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<std::string,std::allocator<std::string > > : Bedrock::Threading::ThreadLocalObjectImplementation<std::string,std::allocator<std::string > >
{
  std::function<void __cdecl(std::string *)> mConstructor;
};

```

### `BidirectionalUnorderedMap<enum SparseContainer::PushSlotPredictionResult,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum SparseContainer::PushSlotPredictionResult,std::string >
{
  std::unordered_map<enum SparseContainer::PushSlotPredictionResult,std::string> mRight;
  std::unordered_map<std::string,enum SparseContainer::PushSlotPredictionResult> mLeft;
};

```

### `BalloonGasParticle`
```
struct __cppobj BalloonGasParticle : EndRodParticle
{
};

```

### `BalloonGasParticle_vtbl`
```
struct /*VFT*/ BalloonGasParticle_vtbl
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

### `BlockForceFieldParticle`
```
struct __cppobj __declspec(align(8)) BlockForceFieldParticle : Particle
{
  bool mCanFadeout;
};

```

### `BlockForceFieldParticle_vtbl`
```
struct /*VFT*/ BlockForceFieldParticle_vtbl
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

### `BubbleParticle`
```
struct __cppobj BubbleParticle : Particle
{
};

```

### `BubbleParticle_vtbl`
```
struct /*VFT*/ BubbleParticle_vtbl
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

### `BubbleColumnParticle`
```
struct __cppobj __declspec(align(8)) BubbleColumnParticle : BubbleParticle
{
  bool mNeedsWater;
};

```

### `BubbleColumnParticle_vtbl`
```
struct /*VFT*/ BubbleColumnParticle_vtbl
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

### `BubbleColumnDownParticle`
```
struct __cppobj __declspec(align(8)) BubbleColumnDownParticle : BubbleColumnParticle
{
  float mAngle;
};

```

### `BubbleColumnDownParticle_vtbl`
```
struct /*VFT*/ BubbleColumnDownParticle_vtbl
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

### `BubbleColumnUpParticle`
```
struct __cppobj BubbleColumnUpParticle : BubbleColumnParticle
{
};

```

### `BubbleColumnUpParticle_vtbl`
```
struct /*VFT*/ BubbleColumnUpParticle_vtbl
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

### `BreakingItemParticle`
```
struct __cppobj BreakingItemParticle : Particle
{
  const Item *mItem;
};

```

### `BreakingItemParticle_vtbl`
```
struct /*VFT*/ BreakingItemParticle_vtbl
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

### `BidirectionalUnorderedMap<std::string,enum LevelSoundEvent>`
```
struct __cppobj BidirectionalUnorderedMap<std::string,enum LevelSoundEvent>
{
  std::unordered_map<std::string,enum LevelSoundEvent> mRight;
  std::unordered_map<enum LevelSoundEvent,std::string> mLeft;
};

```

### `Bedrock::Intrusive::list_standard_operations<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>`
```
struct __cppobj Bedrock::Intrusive::list_standard_operations<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>
{
};

```

### `Bedrock::JSONObject::MemoryPage`
```
struct __cppobj Bedrock::JSONObject::MemoryPage
{
  gsl::not_null<Bedrock::JSONObject::Document *> mDocument;
  Bedrock::JSONObject::MemoryPage *mPrevious;
  unsigned int mLength;
  unsigned int mPageIndex;
  unsigned __int64 mFrontPtr;
  unsigned __int64 mBackPtr;
};

```

### `Bedrock::JSONObject::NodeBase::Offset`
```
struct Bedrock::JSONObject::NodeBase::Offset
{
  $7AE99247DE4E2AB7A8FBAA39B692D4AC ___u0;
};

```

### `Bedrock::JSONObject::NodeBase`
```
struct __cppobj Bedrock::JSONObject::NodeBase : Bedrock::Intrusive::list_standard_operations<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>
{
  $A502E20004E18863C23A549842F01CFA ___u1;
};

```

### `Bedrock::JSONObject::Node`
```
struct __cppobj Bedrock::JSONObject::Node : Bedrock::JSONObject::NodeBase
{
};

```

### `Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>
{
  Bedrock::JSONObject::NodeBase mSentinel;
};

```

### `Bedrock::JSONObject::Collection`
```
struct __cppobj Bedrock::JSONObject::Collection
{
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase> mList;
  unsigned int mSize;
  unsigned int mPadding;
};

```

### `Bedrock::JSONObject::ArrayNode`
```
struct __cppobj Bedrock::JSONObject::ArrayNode : Bedrock::JSONObject::Node, Bedrock::JSONObject::Collection
{
};

```

### `Bedrock::JSONObject::ObjectNode`
```
struct __cppobj Bedrock::JSONObject::ObjectNode : Bedrock::JSONObject::Node, Bedrock::JSONObject::Collection
{
};

```

### `Bedrock::JSONObject::Document::AllocatedResources`
```
struct __cppobj Bedrock::JSONObject::Document::AllocatedResources
{
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase> mFreeNullsOrBools;
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase> mFreeNumbers;
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase> mFreeCollections;
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase> mFreeStringBuffers;
  Bedrock::JSONObject::ArrayNode mNullArray;
  Bedrock::JSONObject::ObjectNode mNullObject;
};

```

### `Bedrock::JSONObject::OutputOptions`
```
struct __cppobj __declspec(align(4)) Bedrock::JSONObject::OutputOptions
{
  bool mPretty;
  unsigned int mIndentAmount;
  char mIndentChar;
};

```

### `Bedrock::JSONObject::StringNode`
```
struct __cppobj Bedrock::JSONObject::StringNode : Bedrock::JSONObject::Node
{
  $4F31B525017717FAA4DCB639C7FC65D7 ___u1;
};

```

### `Bedrock::JSONObject::NullNode`
```
struct __cppobj Bedrock::JSONObject::NullNode : Bedrock::JSONObject::Node
{
};

```

### `Bedrock::JSONObject::BooleanNode`
```
struct __cppobj Bedrock::JSONObject::BooleanNode : Bedrock::JSONObject::Node
{
};

```

### `Bedrock::JSONObject::NumberNode`
```
struct __cppobj Bedrock::JSONObject::NumberNode : Bedrock::JSONObject::Node
{
  $3EB15921B14454EE0C46C34FC3F1335B ___u1;
};

```

### `Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>::iterator_base<1>`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>::iterator_base<1>
{
  const Bedrock::JSONObject::NodeBase *mHook;
};

```

### `Bedrock::JSONObject::ArrayNode::iterator_base<0>`
```
struct __cppobj Bedrock::JSONObject::ArrayNode::iterator_base<0>
{
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>::iterator_base<0> mHandle;
};

```

### `Bedrock::JSONObject::ArrayNode::iterator_base<1>`
```
struct __cppobj Bedrock::JSONObject::ArrayNode::iterator_base<1>
{
  Bedrock::Intrusive::list<Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase,Bedrock::JSONObject::NodeBase>::iterator_base<1> mHandle;
};

```

### `Bedrock::JSONObject::ObjectNode::iterator_base<0>`
```
struct __cppobj Bedrock::JSONObject::ObjectNode::iterator_base<0>
{
  std::pair<Bedrock::JSONObject::StringNode const *,Bedrock::JSONObject::Node *> mPair;
};

```

### `Bedrock::JSONObject::ObjectNode::iterator_base<1>`
```
struct __cppobj Bedrock::JSONObject::ObjectNode::iterator_base<1>
{
  std::pair<Bedrock::JSONObject::StringNode const *,Bedrock::JSONObject::Node const *> mPair;
};

```

### `Bedrock::JSONObject::NumberNode::InternalFormat`
```
struct __cppobj __declspec(align(8)) Bedrock::JSONObject::NumberNode::InternalFormat
{
  $3EB15921B14454EE0C46C34FC3F1335B ___u0;
  bool mIsFloatingPoint;
};

```

### `Bedrock::JSONObject::Wrap<Bedrock::JSONObject::ValueWrapper,void>`
```
struct __cppobj Bedrock::JSONObject::Wrap<Bedrock::JSONObject::ValueWrapper,void>
{
};

```

### `Bedrock::JSONObject::Wrap<bool,void>`
```
struct __cppobj Bedrock::JSONObject::Wrap<bool,void>
{
};

```

### `Bedrock::JSONObject::Wrap<gsl::basic_string_span<char const ,-1>,void>`
```
struct __cppobj Bedrock::JSONObject::Wrap<gsl::basic_string_span<char const ,-1>,void>
{
};

```

### `Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>,void,void,Core::Profile::ProfileGroup &>`
```
struct __cppobj Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>,void,void,Core::Profile::ProfileGroup &>
{
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>`
```
struct __cppobj Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)> : Bedrock::PubSub::Detail::Dispatcher<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>,void,void,Core::Profile::ProfileGroup &>
{
  std::list<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody>> mSubscriptions;
  std::mutex mMutex;
  std::weak_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody> mSingleSubscriber;
  std::atomic<unsigned __int64> mSubscriberCount;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody`
```
struct __cppobj __declspec(align(8)) Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody : Bedrock::PubSub::Detail::SubscriptionBodyInterface
{
  Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)> *mOwner;
  std::_List_iterator<std::_List_val<std::_List_simple_types<std::shared_ptr<Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody> > > > mIterator;
  std::function<void __cdecl(Core::Profile::ProfileGroup &)> mFunction;
  std::unique_ptr<Bedrock::PubSub::SubscriptionContext> mContext;
  int mGroup;
};

```

### `Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody_vtbl`
```
struct /*VFT*/ Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>::SubscriptionBody_vtbl
{
  void (__fastcall *~SubscriptionBodyInterface)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  const Bedrock::PubSub::SubscriptionContext *(__fastcall *_getContext)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this);
  void (__fastcall *_disconnect)(Bedrock::PubSub::Detail::SubscriptionBodyInterface *this, std::shared_ptr<Bedrock::PubSub::Detail::SubscriptionBodyInterface> *);
};

```

### `Bedrock::PubSub::Publisher<void __cdecl(Core::Profile::ProfileGroup &),Bedrock::PubSub::ThreadModel::MultiThreaded,void>`
```
struct __cppobj Bedrock::PubSub::Publisher<void __cdecl(Core::Profile::ProfileGroup &),Bedrock::PubSub::ThreadModel::MultiThreaded,void> : Bedrock::PubSub::Detail::PublisherBase<Bedrock::PubSub::ThreadModel::MultiThreaded,void,void __cdecl(Core::Profile::ProfileGroup &)>
{
};

```

### `BootstrapConfig::LoadResult`
```
struct BootstrapConfig::LoadResult
{
  bool success;
  const char *errorMessage;
};

```

### `BootstrapConfig`
```
struct __cppobj __declspec(align(8)) BootstrapConfig
{
  char mBuffer[2048];
  char mError[512];
  Bedrock::JSONObject::Document mDocument;
  Bedrock::JSONObject::ObjectNode *mRootObject;
  bool mInitialized;
};

```

### `BoatRenderer`
```
struct __cppobj BoatRenderer : ActorRenderer, AppPlatformListener
{
  BoatModel mModel;
  mce::MaterialPtr mHoleMaterial;
  mce::TexturePtr mBoatTex[6];
  mce::Mesh mHole;
};

```

### `BoatRenderer_vtbl`
```
struct /*VFT*/ BoatRenderer_vtbl
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

### `BannerRenderer`
```
struct __cppobj BannerRenderer : BlockActorRenderer
{
  bool mAtlasLoaded;
  std::unique_ptr<TextureAtlas> mTextureAtlas;
  glm::tvec2<float,0> mMaxTileSize;
  mce::TexturePtr mTexture;
  std::unique_ptr<BannerModel> mBannerModel;
  mce::MaterialPtr mGuiMaterial;
  mce::MaterialPtr mGuiPoleMaterial;
};

```

### `BannerRenderer_vtbl`
```
struct /*VFT*/ BannerRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `BushBlock`
```
struct __cppobj BushBlock : BlockLegacy
{
};

```

### `BushBlock_vtbl`
```
struct /*VFT*/ BushBlock_vtbl
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
  void (__fastcall *checkAlive)(BushBlock *this, BlockSource *, const BlockPos *);
};

```

### `BeaconBeamSection`
```
struct __cppobj BeaconBeamSection
{
  int mHeight;
  mce::Color mColor;
};

```

### `BeaconBlockActor`
```
struct __cppobj BeaconBlockActor : BlockActor, Container
{
  std::vector<BeaconBeamSection> mBeamSections;
  float mBeamRot;
  int mNumLevels;
  int mNumLevelsSet;
  int mBlockRefreshCounter;
  int mPrimaryEffectId;
  int mSecondaryEffectId;
  int mPrimaryEffectTier;
  int mSecondaryEffectTier;
  std::vector<MobEffect *> mBeaconEffects;
  std::vector<std::vector<MobEffect *>> mTierEffects;
};

```

### `BeaconBlockActor_vtbl`
```
struct /*VFT*/ BeaconBlockActor_vtbl
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

### `BeaconRenderer`
```
struct __cppobj BeaconRenderer : BlockActorRenderer
{
  mce::TexturePtr mBeaconTexture;
  mce::MaterialPtr mBeaconMaterial;
  mce::MaterialPtr mBeaconTransparentMaterial;
};

```

### `BeaconRenderer_vtbl`
```
struct /*VFT*/ BeaconRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `BedRenderer`
```
struct __cppobj BedRenderer : BlockActorRenderer
{
  mce::TexturePtr mBookTex;
  BedModel mBed;
  mce::TexturePtr mTextures[16];
};

```

### `BedRenderer_vtbl`
```
struct /*VFT*/ BedRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `BedBlockActor`
```
struct __cppobj BedBlockActor : BlockActor
{
  int mDyeColor;
  bool mDirty;
  ActorUniqueID mPetSleepingOnBed;
};

```

### `BedBlockActor_vtbl`
```
struct /*VFT*/ BedBlockActor_vtbl
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

### `BellBlockActorRenderer`
```
struct __cppobj BellBlockActorRenderer : BlockActorRenderer
{
  mce::TexturePtr mBellTexture;
  BellModel mBell;
};

```

### `BellBlockActorRenderer_vtbl`
```
struct /*VFT*/ BellBlockActorRenderer_vtbl
{
  void (__fastcall *~ActorShaderManager)(ActorShaderManager *this);
  mce::Color *(__fastcall *_getOverlayColor)(ActorShaderManager *this, mce::Color *result, Actor *, float);
  void (__fastcall *render)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  void (__fastcall *renderAlpha)(BlockActorRenderer *this, BaseActorRenderContext *, BlockActorRenderData *);
  std::vector<NameTagRenderObject> *(__fastcall *extractText)(BlockActorRenderer *this, std::vector<NameTagRenderObject> *result, Tessellator *, BlockActor *, const std::string *, const std::vector<int> *, Vec3, bool);
};

```

### `BellBlockActor`
```
struct __cppobj BellBlockActor : BlockActor
{
  bool mRinging;
  Direction::Type mMovementDirection;
  bool mPowered;
  int mAlarmCooldown;
};

```

### `BellBlockActor_vtbl`
```
struct /*VFT*/ BellBlockActor_vtbl
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

### `BlockGraphics::registerMicroBlockGraphics::__l2::<lambda_826af4ce9791fce1685fd480ea7c7493>`
```
struct __cppobj BlockGraphics::registerMicroBlockGraphics::__l2::<lambda_826af4ce9791fce1685fd480ea7c7493>
{
  BlockGraphics **ptr;
};

```

### `BlockGraphics::registerBlockGraphics::__l2::<lambda_8c64b90d378b38d9711ce518f594d580>`
```
struct __cppobj BlockGraphics::registerBlockGraphics::__l2::<lambda_8c64b90d378b38d9711ce518f594d580>
{
  BlockGraphics **ptr;
};

```

### `BlockTessellator::{ctor}::__l2::<lambda_cbf0c27e84d3545f4e5c8fd5f8fc8d47>`
```
struct __cppobj BlockTessellator::{ctor}::__l2::<lambda_cbf0c27e84d3545f4e5c8fd5f8fc8d47>
{
  BlockTessellator *const __this;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<std::array<std::vector<BlockQueueEntry>,14>,std::allocator<std::array<std::vector<BlockQueueEntry>,14> > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<std::array<std::vector<BlockQueueEntry>,14>,std::allocator<std::array<std::vector<BlockQueueEntry>,14> > >
{
  std::array<std::vector<BlockQueueEntry>,14> *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<std::array<std::vector<BlockQueueEntry>,14>,std::allocator<std::array<std::vector<BlockQueueEntry>,14> > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<std::array<std::vector<BlockQueueEntry>,14>,std::allocator<std::array<std::vector<BlockQueueEntry>,14> > > : Bedrock::Threading::ThreadLocalObjectImplementation<std::array<std::vector<BlockQueueEntry>,14>,std::allocator<std::array<std::vector<BlockQueueEntry>,14> > >
{
  std::function<void __cdecl(std::array<std::vector<BlockQueueEntry>,14> *)> mConstructor;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<std::vector<BlockQueueEntry>,std::allocator<std::vector<BlockQueueEntry> > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<std::vector<BlockQueueEntry>,std::allocator<std::vector<BlockQueueEntry> > >
{
  std::vector<BlockQueueEntry> *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<std::vector<BlockQueueEntry>,std::allocator<std::vector<BlockQueueEntry> > >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<std::vector<BlockQueueEntry>,std::allocator<std::vector<BlockQueueEntry> > > : Bedrock::Threading::ThreadLocalObjectImplementation<std::vector<BlockQueueEntry>,std::allocator<std::vector<BlockQueueEntry> > >
{
  std::function<void __cdecl(std::vector<BlockQueueEntry> *)> mConstructor;
};

```

### `BaseMobSpawner`
```
struct __cppobj BaseMobSpawner
{
  BaseMobSpawner_vtbl *__vftable /*VFT*/;
  int mSpawnDelay;
  float mSpin;
  float mOSpin;
  ActorDefinitionIdentifier mActorId;
  std::vector<SpawnData> mSpawnPotentials;
  std::unique_ptr<SpawnData> mNextSpawnData;
  int mMinSpawnDelay;
  int mMaxSpawnDelay;
  int mSpawnCount;
  std::unique_ptr<Mob> mDisplayEntity;
  int mMaxNearbyEntities;
  int mRequiredPlayerRange;
  int mSpawnRange;
  float mDisplayEntityWidth;
  float mDisplayEntityHeight;
  float mDisplayEntityScale;
};

```

### `BaseMobSpawner_vtbl`
```
struct /*VFT*/ BaseMobSpawner_vtbl
{
  void (__fastcall *~BaseMobSpawner)(BaseMobSpawner *this);
  void (__fastcall *tick)(BaseMobSpawner *this, BlockSource *);
  void (__fastcall *load)(BaseMobSpawner *this, const CompoundTag *);
  void (__fastcall *save)(BaseMobSpawner *this, CompoundTag *);
  const BlockPos *(__fastcall *getPos)(BaseMobSpawner *this);
};

```

### `buffer_span<ActorBlockSyncMessage>::iterator`
```
struct __cppobj buffer_span<ActorBlockSyncMessage>::iterator
{
  const ActorBlockSyncMessage *mPtr;
};

```

### `buffer_span<BlockActorBlockSyncMessage>::iterator`
```
struct __cppobj buffer_span<BlockActorBlockSyncMessage>::iterator
{
  const BlockActorBlockSyncMessage *mPtr;
};

```

### `BlockPosIterator`
```
struct __cppobj __declspec(align(4)) BlockPosIterator
{
  const BlockPos mMinCorner;
  const BlockPos mMaxCorner;
  BlockPos mCurrentPos;
  bool mDone;
};

```

### `Bedrock::Threading::ThreadLocalObjectImplementation<VisibilityExtimator,std::allocator<VisibilityExtimator> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObjectImplementation<VisibilityExtimator,std::allocator<VisibilityExtimator> >
{
  VisibilityExtimator *mPtr;
};

```

### `Bedrock::Threading::ThreadLocalObject<VisibilityExtimator,std::allocator<VisibilityExtimator> >`
```
struct __cppobj Bedrock::Threading::ThreadLocalObject<VisibilityExtimator,std::allocator<VisibilityExtimator> > : Bedrock::Threading::ThreadLocalObjectImplementation<VisibilityExtimator,std::allocator<VisibilityExtimator> >
{
  std::function<void __cdecl(VisibilityExtimator *)> mConstructor;
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<std::vector<BlockQueueEntry>,void>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<std::vector<BlockQueueEntry>,void>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<std::array<std::vector<BlockQueueEntry>,14>,void>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<std::array<std::vector<BlockQueueEntry>,14>,void>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<std::vector<BlockQueueEntry>,void>::create::__l2::<lambda_ace7f0cb8a0f5c69bc0e799433d574e3>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<std::vector<BlockQueueEntry>,void>::create::__l2::<lambda_ace7f0cb8a0f5c69bc0e799433d574e3>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<std::array<std::vector<BlockQueueEntry>,14>,void>::create::__l2::<lambda_c9dbd5b763eda418ab002da6227e142f>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<std::array<std::vector<BlockQueueEntry>,14>,void>::create::__l2::<lambda_c9dbd5b763eda418ab002da6227e142f>
{
};

```

### `buffer_span<std::vector<RenderChunkQuadInfo> >::iterator`
```
struct __cppobj buffer_span<std::vector<RenderChunkQuadInfo> >::iterator
{
  const std::vector<RenderChunkQuadInfo> *mPtr;
};

```

### `buffer_span<RenderChunkSorter::FaceInfo>`
```
struct __cppobj buffer_span<RenderChunkSorter::FaceInfo>
{
  const RenderChunkSorter::FaceInfo *mBegin;
  const RenderChunkSorter::FaceInfo *mEnd;
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<VisibilityExtimator,void>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<VisibilityExtimator,void>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<VisibilityExtimator,void>::create::__l2::<lambda_36f8a46397ac3ff79641196e7dbcdcaf>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<VisibilityExtimator,void>::create::__l2::<lambda_36f8a46397ac3ff79641196e7dbcdcaf>
{
};

```

### `BuildTaskContext`
```
struct __cppobj BuildTaskContext
{
  PolygonOperatorPool<RenderChunkBuilder> *mBuilders;
  PolygonOperatorPool<RenderChunkBuilder>::PoolEntry mBuilder;
};

```

### `buffer_span_mut<CommandListFuture>::iterator`
```
struct __cppobj buffer_span_mut<CommandListFuture>::iterator
{
  CommandListFuture *mPtr;
};

```

### `buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >::iterator`
```
struct __cppobj buffer_span_mut<std::shared_ptr<RenderChunkInstanced> >::iterator
{
  std::shared_ptr<RenderChunkInstanced> *mPtr;
};

```

### `Bedrock::NonOwnerPointer<cg::TextureSetLayerDefinition>`
```
struct __cppobj Bedrock::NonOwnerPointer<cg::TextureSetLayerDefinition>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::NonOwnerPointer<CustomMusic>`
```
struct __cppobj Bedrock::NonOwnerPointer<CustomMusic>
{
  std::shared_ptr<Bedrock::EnableNonOwnerReferences::ControlBlock> mControlBlock;
};

```

### `Bedrock::Input::KeyboardEventProcessor`
```
struct __cppobj Bedrock::Input::KeyboardEventProcessor
{
  Bedrock::Input::KeyboardEventProcessor_vtbl *__vftable /*VFT*/;
};

```

### `Bedrock::Input::KeyboardEventProcessor_vtbl`
```
struct /*VFT*/ Bedrock::Input::KeyboardEventProcessor_vtbl
{
  void (__fastcall *~KeyboardEventProcessor)(Bedrock::Input::KeyboardEventProcessor *this);
  void (__fastcall *onKeyDown)(Bedrock::Input::KeyboardEventProcessor *this, int);
  void (__fastcall *onKeyUp)(Bedrock::Input::KeyboardEventProcessor *this, int);
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<ThreadedFrameConstantsContainer,void>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<ThreadedFrameConstantsContainer,void>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<ThreadedFrameConstantsContainer,void>::create::__l2::<lambda_818de085286a61d3373be624e0869fe9>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<ThreadedFrameConstantsContainer,void>::create::__l2::<lambda_818de085286a61d3373be624e0869fe9>
{
};

```

### `Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::_kickNewWorkerTask::__l5::<lambda_4b11245632ccb66fc7aa20e2bc6b2264>`
```
struct __cppobj Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::_kickNewWorkerTask::__l5::<lambda_4b11245632ccb66fc7aa20e2bc6b2264>
{
};

```

### `Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::_kickNewWorkerTask::__l5::<lambda_75cdf9faff596de1f4e63d5cc780601a>`
```
struct __cppobj Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::_kickNewWorkerTask::__l5::<lambda_75cdf9faff596de1f4e63d5cc780601a>
{
  Bedrock::Threading::Burst::Details::WorkerTask<Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution> *const __this;
  std::shared_ptr<Bedrock::Threading::Burst::Details::Lifetime> lifetime;
};

```

### `Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::{ctor}::__l2::<lambda_d3f941515fbef779c9de2f61db7c6f6d>`
```
struct __cppobj Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>::{ctor}::__l2::<lambda_d3f941515fbef779c9de2f61db7c6f6d>
{
  Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution> *const __this;
};

```

### `bgfx::TextureFormat`
```
struct __cppobj bgfx::TextureFormat
{
};

```

### `bgfx::Topology`
```
struct __cppobj bgfx::Topology
{
};

```

### `bgfx::Attrib`
```
struct __cppobj bgfx::Attrib
{
};

```

### `bgfx::RendererType`
```
struct __cppobj bgfx::RendererType
{
};

```

### `bgfx::ViewMode`
```
struct __cppobj bgfx::ViewMode
{
};

```

### `bgfx::Transform`
```
struct __declspec(align(8)) bgfx::Transform
{
  float *data;
  unsigned __int16 num;
};

```

### `bgfx::TransientIndexBuffer`
```
struct __declspec(align(8)) bgfx::TransientIndexBuffer
{
  unsigned __int8 *data;
  unsigned int size;
  unsigned int startIndex;
  bgfx::IndexBufferHandle handle;
};

```

### `bgfx::TransientVertexBuffer`
```
struct __declspec(align(4)) bgfx::TransientVertexBuffer
{
  unsigned __int8 *data;
  unsigned int size;
  unsigned int startVertex;
  unsigned __int16 stride;
  bgfx::VertexBufferHandle handle;
  bgfx::VertexDeclHandle decl;
};

```

### `Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item`
```
struct __cppobj Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item : Bedrock::Intrusive::list_base_hook<void>
{
  std::_Align_type<double,8> mData;
};

```

### `Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>`
```
struct __cppobj Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0>
{
  Bedrock::Intrusive::list_base_hook<void> *mHook;
};

```

### `Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::IteratorType`
```
struct __cppobj Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::IteratorType
{
  Bedrock::Intrusive::list<Bedrock::Threading::InstancedThreadLocal<bgfx::Encoder *,std::allocator<bgfx::Encoder *> >::Item,Bedrock::Intrusive::list_base_hook<void>,Bedrock::Intrusive::list_base_hook<void> >::iterator_base<0> mIterator;
};

```

### `bgfx::Access`
```
struct __cppobj bgfx::Access
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<bgfx::Encoder *,void>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<bgfx::Encoder *,void>
{
};

```

### `Bedrock::Threading::TLSDetail::DefaultConstructor<bgfx::Encoder *,void>::create::__l2::<lambda_a5b5eb428bb69d7ea1327cfc6389f2e4>`
```
struct __cppobj Bedrock::Threading::TLSDetail::DefaultConstructor<bgfx::Encoder *,void>::create::__l2::<lambda_a5b5eb428bb69d7ea1327cfc6389f2e4>
{
};

```

### `bgfx::AttribType`
```
struct __cppobj bgfx::AttribType
{
};

```

### `boost_intrusive_hmfcw::dont_care`
```
struct __cppobj boost_intrusive_hmfcw::dont_care
{
};

```

### `boost_intrusive_hmfcw::no_type`
```
struct boost_intrusive_hmfcw::no_type
{
  char dummy[2];
};

```

### `BarterDefinition`
```
struct __cppobj __declspec(align(8)) BarterDefinition
{
  std::string mBarterItemsTable;
  int mCooldown;
};

```

### `BlockPosTrackerComponent`
```
struct __cppobj BlockPosTrackerComponent
{
  bool mPreviousOnGround;
  BlockPos mPreviousBlockPos;
};

```

### `BuoyancyDefinition`
```
struct __cppobj BuoyancyDefinition
{
  float mBaseBuoyancy;
  float mDragDownOnRemoval;
  float mBigWaveProbability;
  float mBigWaveSpeedMultiplier;
  bool mSimulateWaves;
  bool mApplyGravity;
  std::vector<BlockDescriptor> mLiquidBlocks;
  Json::Value mFloatData;
};

```

### `BlockUtils`
```
struct __cppobj BlockUtils
{
};

```

### `BuoyancyDefinition::buildSchema::__l2::<lambda_9b31f2e060bc8aee1e94182a51f43d11>`
```
struct __cppobj BuoyancyDefinition::buildSchema::__l2::<lambda_9b31f2e060bc8aee1e94182a51f43d11>
{
};

```

### `BuoyancyDefinition::buildSchema::__l2::<lambda_8ed573b6261707ebee8ec5ff12cb5a04>`
```
struct __cppobj BuoyancyDefinition::buildSchema::__l2::<lambda_8ed573b6261707ebee8ec5ff12cb5a04>
{
};

```

### `BuoyancyDefinition::buildSchema::__l2::<lambda_6e4982b2edfd861ec7fa1334f1250fb9>`
```
struct __cppobj BuoyancyDefinition::buildSchema::__l2::<lambda_6e4982b2edfd861ec7fa1334f1250fb9>
{
};

```

### `BlockPosTrackerSystem`
```
struct __cppobj BlockPosTrackerSystem : ITickingSystem
{
};

```

### `BlockPosTrackerSystem_vtbl`
```
struct /*VFT*/ BlockPosTrackerSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `BuoyancySystem`
```
struct __cppobj BuoyancySystem : ITickingSystem
{
};

```

### `BuoyancySystem_vtbl`
```
struct /*VFT*/ BuoyancySystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `BidirectionalUnorderedMap<enum ItemStackRequestActionType,std::string >`
```
struct __cppobj BidirectionalUnorderedMap<enum ItemStackRequestActionType,std::string >
{
  std::unordered_map<enum ItemStackRequestActionType,std::string> mRight;
  std::unordered_map<std::string,enum ItemStackRequestActionType> mLeft;
};

```

### `BatchWorker<PackStorage::PendingTask>`
```
struct __cppobj BatchWorker<PackStorage::PendingTask>
{
  unsigned __int64 mActiveWorkers;
  const unsigned __int64 mDesiredWorkers;
  std::mutex mMutex;
  MPMCQueue<PackStorage::PendingTask> mTasks;
  std::function<void __cdecl(PackStorage::PendingTask &&)> mDoWork;
  std::shared_ptr<ITaskGroupProxy> mTaskGroup;
  std::string mName;
};

```

### `Bedrock::Threading::AsyncDeferredResultT<bool>`
```
struct __cppobj __declspec(align(8)) Bedrock::Threading::AsyncDeferredResultT<bool> : Bedrock::Threading::IAsyncResult<bool>
{
  std::mutex mLock;
  Bedrock::Threading::AsyncDeferredResultT<bool>::DelayStatus mStatus;
  std::vector<std::function<void __cdecl(Bedrock::Threading::IAsyncResult<bool> const &)>> mComplete;
  std::optional<bool> mResult;
};

```

