# V
### `Vec3`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | z


### `Vec2`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum CoralDirection>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum CoralDirection,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum CoralDirection>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum LeverDirection>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum LeverDirection,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum LeverDirection>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Facing::Name>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum Facing::Name,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum Facing::Name>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PillarAxis>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum PillarAxis,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum PillarAxis>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PortalAxis>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum PortalAxis,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum PortalAxis>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum RailDirection>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum RailDirection,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum RailDirection>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum TorchFacing>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum TorchFacing,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum TorchFacing>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Direction::Type>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum Direction::Type,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum Direction::Type>>` | mToLeft


### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum WeirdoDirection>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::pair<enum WeirdoDirection,enum CommonDirection>>` | mToRight
24 | (24) `std::vector<std::pair<enum CommonDirection,enum WeirdoDirection>>` | mToLeft


### `Vec4`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | z
12 | (4) `float` | w


### `VkPhysicalDeviceProperties`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | apiVersion
4 | (4) `unsigned int` | driverVersion
8 | (4) `unsigned int` | vendorID
12 | (4) `unsigned int` | deviceID
16 | (4) `VkPhysicalDeviceType` | deviceType
20 | (256) `char[256]` | deviceName
276 | (16) `unsigned __int8[16]` | pipelineCacheUUID
296 | (504) `VkPhysicalDeviceLimits` | limits
800 | (20) `VkPhysicalDeviceSparseProperties` | sparseProperties


### `VkPhysicalDeviceLimits`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | maxImageDimension1D
4 | (4) `unsigned int` | maxImageDimension2D
8 | (4) `unsigned int` | maxImageDimension3D
12 | (4) `unsigned int` | maxImageDimensionCube
16 | (4) `unsigned int` | maxImageArrayLayers
20 | (4) `unsigned int` | maxTexelBufferElements
24 | (4) `unsigned int` | maxUniformBufferRange
28 | (4) `unsigned int` | maxStorageBufferRange
32 | (4) `unsigned int` | maxPushConstantsSize
36 | (4) `unsigned int` | maxMemoryAllocationCount
40 | (4) `unsigned int` | maxSamplerAllocationCount
48 | (8) `unsigned __int64` | bufferImageGranularity
56 | (8) `unsigned __int64` | sparseAddressSpaceSize
64 | (4) `unsigned int` | maxBoundDescriptorSets
68 | (4) `unsigned int` | maxPerStageDescriptorSamplers
72 | (4) `unsigned int` | maxPerStageDescriptorUniformBuffers
76 | (4) `unsigned int` | maxPerStageDescriptorStorageBuffers
80 | (4) `unsigned int` | maxPerStageDescriptorSampledImages
84 | (4) `unsigned int` | maxPerStageDescriptorStorageImages
88 | (4) `unsigned int` | maxPerStageDescriptorInputAttachments
92 | (4) `unsigned int` | maxPerStageResources
96 | (4) `unsigned int` | maxDescriptorSetSamplers
100 | (4) `unsigned int` | maxDescriptorSetUniformBuffers
104 | (4) `unsigned int` | maxDescriptorSetUniformBuffersDynamic
108 | (4) `unsigned int` | maxDescriptorSetStorageBuffers
112 | (4) `unsigned int` | maxDescriptorSetStorageBuffersDynamic
116 | (4) `unsigned int` | maxDescriptorSetSampledImages
120 | (4) `unsigned int` | maxDescriptorSetStorageImages
124 | (4) `unsigned int` | maxDescriptorSetInputAttachments
128 | (4) `unsigned int` | maxVertexInputAttributes
132 | (4) `unsigned int` | maxVertexInputBindings
136 | (4) `unsigned int` | maxVertexInputAttributeOffset
140 | (4) `unsigned int` | maxVertexInputBindingStride
144 | (4) `unsigned int` | maxVertexOutputComponents
148 | (4) `unsigned int` | maxTessellationGenerationLevel
152 | (4) `unsigned int` | maxTessellationPatchSize
156 | (4) `unsigned int` | maxTessellationControlPerVertexInputComponents
160 | (4) `unsigned int` | maxTessellationControlPerVertexOutputComponents
164 | (4) `unsigned int` | maxTessellationControlPerPatchOutputComponents
168 | (4) `unsigned int` | maxTessellationControlTotalOutputComponents
172 | (4) `unsigned int` | maxTessellationEvaluationInputComponents
176 | (4) `unsigned int` | maxTessellationEvaluationOutputComponents
180 | (4) `unsigned int` | maxGeometryShaderInvocations
184 | (4) `unsigned int` | maxGeometryInputComponents
188 | (4) `unsigned int` | maxGeometryOutputComponents
192 | (4) `unsigned int` | maxGeometryOutputVertices
196 | (4) `unsigned int` | maxGeometryTotalOutputComponents
200 | (4) `unsigned int` | maxFragmentInputComponents
204 | (4) `unsigned int` | maxFragmentOutputAttachments
208 | (4) `unsigned int` | maxFragmentDualSrcAttachments
212 | (4) `unsigned int` | maxFragmentCombinedOutputResources
216 | (4) `unsigned int` | maxComputeSharedMemorySize
220 | (12) `unsigned int[3]` | maxComputeWorkGroupCount
232 | (4) `unsigned int` | maxComputeWorkGroupInvocations
236 | (12) `unsigned int[3]` | maxComputeWorkGroupSize
248 | (4) `unsigned int` | subPixelPrecisionBits
252 | (4) `unsigned int` | subTexelPrecisionBits
256 | (4) `unsigned int` | mipmapPrecisionBits
260 | (4) `unsigned int` | maxDrawIndexedIndexValue
264 | (4) `unsigned int` | maxDrawIndirectCount
268 | (4) `float` | maxSamplerLodBias
272 | (4) `float` | maxSamplerAnisotropy
276 | (4) `unsigned int` | maxViewports
280 | (8) `unsigned int[2]` | maxViewportDimensions
288 | (8) `float[2]` | viewportBoundsRange
296 | (4) `unsigned int` | viewportSubPixelBits
304 | (8) `unsigned __int64` | minMemoryMapAlignment
312 | (8) `unsigned __int64` | minTexelBufferOffsetAlignment
320 | (8) `unsigned __int64` | minUniformBufferOffsetAlignment
328 | (8) `unsigned __int64` | minStorageBufferOffsetAlignment
336 | (4) `int` | minTexelOffset
340 | (4) `unsigned int` | maxTexelOffset
344 | (4) `int` | minTexelGatherOffset
348 | (4) `unsigned int` | maxTexelGatherOffset
352 | (4) `float` | minInterpolationOffset
356 | (4) `float` | maxInterpolationOffset
360 | (4) `unsigned int` | subPixelInterpolationOffsetBits
364 | (4) `unsigned int` | maxFramebufferWidth
368 | (4) `unsigned int` | maxFramebufferHeight
372 | (4) `unsigned int` | maxFramebufferLayers
376 | (4) `unsigned int` | framebufferColorSampleCounts
380 | (4) `unsigned int` | framebufferDepthSampleCounts
384 | (4) `unsigned int` | framebufferStencilSampleCounts
388 | (4) `unsigned int` | framebufferNoAttachmentsSampleCounts
392 | (4) `unsigned int` | maxColorAttachments
396 | (4) `unsigned int` | sampledImageColorSampleCounts
400 | (4) `unsigned int` | sampledImageIntegerSampleCounts
404 | (4) `unsigned int` | sampledImageDepthSampleCounts
408 | (4) `unsigned int` | sampledImageStencilSampleCounts
412 | (4) `unsigned int` | storageImageSampleCounts
416 | (4) `unsigned int` | maxSampleMaskWords
420 | (4) `unsigned int` | timestampComputeAndGraphics
424 | (4) `float` | timestampPeriod
428 | (4) `unsigned int` | maxClipDistances
432 | (4) `unsigned int` | maxCullDistances
436 | (4) `unsigned int` | maxCombinedClipAndCullDistances
440 | (4) `unsigned int` | discreteQueuePriorities
444 | (8) `float[2]` | pointSizeRange
452 | (8) `float[2]` | lineWidthRange
460 | (4) `float` | pointSizeGranularity
464 | (4) `float` | lineWidthGranularity
468 | (4) `unsigned int` | strictLines
472 | (4) `unsigned int` | standardSampleLocations
480 | (8) `unsigned __int64` | optimalBufferCopyOffsetAlignment
488 | (8) `unsigned __int64` | optimalBufferCopyRowPitchAlignment
496 | (8) `unsigned __int64` | nonCoherentAtomSize


### `VkPhysicalDeviceSparseProperties`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | residencyStandard2DBlockShape
4 | (4) `unsigned int` | residencyStandard2DMultisampleBlockShape
8 | (4) `unsigned int` | residencyStandard3DBlockShape
12 | (4) `unsigned int` | residencyAlignedMipSize
16 | (4) `unsigned int` | residencyNonResidentStrict


### `VkPhysicalDeviceMemoryProperties`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | memoryTypeCount
4 | (256) `VkMemoryType[32]` | memoryTypes
260 | (4) `unsigned int` | memoryHeapCount
264 | (256) `VkMemoryHeap[16]` | memoryHeaps


### `VkMemoryType`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | propertyFlags
4 | (4) `unsigned int` | heapIndex


### `VkMemoryHeap`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | size
8 | (4) `unsigned int` | flags


### `VkPhysicalDeviceFeatures`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | robustBufferAccess
4 | (4) `unsigned int` | fullDrawIndexUint32
8 | (4) `unsigned int` | imageCubeArray
12 | (4) `unsigned int` | independentBlend
16 | (4) `unsigned int` | geometryShader
20 | (4) `unsigned int` | tessellationShader
24 | (4) `unsigned int` | sampleRateShading
28 | (4) `unsigned int` | dualSrcBlend
32 | (4) `unsigned int` | logicOp
36 | (4) `unsigned int` | multiDrawIndirect
40 | (4) `unsigned int` | drawIndirectFirstInstance
44 | (4) `unsigned int` | depthClamp
48 | (4) `unsigned int` | depthBiasClamp
52 | (4) `unsigned int` | fillModeNonSolid
56 | (4) `unsigned int` | depthBounds
60 | (4) `unsigned int` | wideLines
64 | (4) `unsigned int` | largePoints
68 | (4) `unsigned int` | alphaToOne
72 | (4) `unsigned int` | multiViewport
76 | (4) `unsigned int` | samplerAnisotropy
80 | (4) `unsigned int` | textureCompressionETC2
84 | (4) `unsigned int` | textureCompressionASTC_LDR
88 | (4) `unsigned int` | textureCompressionBC
92 | (4) `unsigned int` | occlusionQueryPrecise
96 | (4) `unsigned int` | pipelineStatisticsQuery
100 | (4) `unsigned int` | vertexPipelineStoresAndAtomics
104 | (4) `unsigned int` | fragmentStoresAndAtomics
108 | (4) `unsigned int` | shaderTessellationAndGeometryPointSize
112 | (4) `unsigned int` | shaderImageGatherExtended
116 | (4) `unsigned int` | shaderStorageImageExtendedFormats
120 | (4) `unsigned int` | shaderStorageImageMultisample
124 | (4) `unsigned int` | shaderStorageImageReadWithoutFormat
128 | (4) `unsigned int` | shaderStorageImageWriteWithoutFormat
132 | (4) `unsigned int` | shaderUniformBufferArrayDynamicIndexing
136 | (4) `unsigned int` | shaderSampledImageArrayDynamicIndexing
140 | (4) `unsigned int` | shaderStorageBufferArrayDynamicIndexing
144 | (4) `unsigned int` | shaderStorageImageArrayDynamicIndexing
148 | (4) `unsigned int` | shaderClipDistance
152 | (4) `unsigned int` | shaderCullDistance
156 | (4) `unsigned int` | shaderFloat64
160 | (4) `unsigned int` | shaderInt64
164 | (4) `unsigned int` | shaderInt16
168 | (4) `unsigned int` | shaderResourceResidency
172 | (4) `unsigned int` | shaderResourceMinLod
176 | (4) `unsigned int` | sparseBinding
180 | (4) `unsigned int` | sparseResidencyBuffer
184 | (4) `unsigned int` | sparseResidencyImage2D
188 | (4) `unsigned int` | sparseResidencyImage3D
192 | (4) `unsigned int` | sparseResidency2Samples
196 | (4) `unsigned int` | sparseResidency4Samples
200 | (4) `unsigned int` | sparseResidency8Samples
204 | (4) `unsigned int` | sparseResidency16Samples
208 | (4) `unsigned int` | sparseResidencyAliased
212 | (4) `unsigned int` | variableMultisampleRate
216 | (4) `unsigned int` | inheritedQueries


### `VkSwapchainCreateInfoKHR`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `VkSurfaceKHR_T *` | surface
32 | (4) `unsigned int` | minImageCount
36 | (4) `VkFormat` | imageFormat
40 | (4) `VkColorSpaceKHR` | imageColorSpace
44 | (8) `VkExtent2D` | imageExtent
52 | (4) `unsigned int` | imageArrayLayers
56 | (4) `unsigned int` | imageUsage
60 | (4) `VkSharingMode` | imageSharingMode
64 | (4) `unsigned int` | queueFamilyIndexCount
72 | (8) `const unsigned int *` | pQueueFamilyIndices
80 | (4) `VkSurfaceTransformFlagBitsKHR` | preTransform
84 | (4) `VkCompositeAlphaFlagBitsKHR` | compositeAlpha
88 | (4) `VkPresentModeKHR` | presentMode
92 | (4) `unsigned int` | clipped
96 | (8) `VkSwapchainKHR_T *` | oldSwapchain


### `VkExtent2D`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | width
4 | (4) `unsigned int` | height


### `VkDescriptorSetLayoutBinding`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | binding
4 | (4) `VkDescriptorType` | descriptorType
8 | (4) `unsigned int` | descriptorCount
12 | (4) `unsigned int` | stageFlags
16 | (8) `VkSampler_T *const *` | pImmutableSamplers


### `VanillaBlockTessellation::Config`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mGenerateNormals
1 | (1) `bool` | mFaceDimming
2 | (1) `bool` | mSmoothLighting
3 | (1) `bool` | mFlatLighting
4 | (1) `bool` | mShouldEmitColors
8 | (24) `ClientBlockPipeline::DimensionDimmingScalars` | mDimensionDimmingScalars
32 | (16) `std::shared_ptr<ClientBlockPipeline::MaterialRepository>` | mMaterialRepository


### `VariableRef`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | mUnsafePointer
8 | (16) `std::weak_ptr<UIControl>` | mControl
24 | (8) `LayoutComponent *` | mLayoutComponent
32 | (1) `LayoutVariableType` | mType


### `VisualTree::getControlsWith::__l2::<lambda_da9a91086bedb4a14722c91a3300ac8e>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::function<bool __cdecl(SliderComponent const &)> *` | predicate


### `VisualTree::getControlsWith::__l2::<lambda_d30ec14a27792ea22ada7beefee6cabf>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::function<bool __cdecl(ToggleComponent const &)> *` | predicate


### `VisualTree`
Offset | Type | Name
-|-|-|-
0 | (8) `ControlScreenAction` | baseclass_0
8 | (16) `std::shared_ptr<UIControl>` | mRootControl
24 | (16) `std::weak_ptr<UIControl>` | mInitialSelectedControl
40 | (32) `std::string` | mRootControlName
72 | (4) `_BYTE[4]` | mDirty
76 | (1) `bool` | mClearPersistantMeshes
80 | (8) `UIMeasureStrategy *` | mMeasureStrategy
88 | (24) `std::vector<std::pair<void *,std::weak_ptr<UIControl> >>` | mNeedsToRemoveDeadDependencies
112 | (24) `std::vector<std::shared_ptr<UIControl>>` | mControlsToUpdate
136 | (24) `std::vector<std::shared_ptr<UIControl>>` | mControlsToUpdateBacklog
160 | (24) `std::vector<std::shared_ptr<UIControl>>` | mControlsToRemoveFromCollections
184 | (24) `std::vector<std::shared_ptr<UIControl>>` | mControlsToBind
208 | (1) `bool` | mUpdateCollectionsFromRoot
209 | (1) `bool` | mUpdateBindsFromRoot
210 | (1) `bool` | mTextEditFocusChanged
211 | (1) `bool` | mTextEditAlwaysListeningChanged
216 | (16) `Json::Value` | mInitGlobalVars
232 | (8) `std::unique_ptr<VisualTreeProxy>` | mProxy


### `VanillaBiomeTypeAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `VanillaBiomeTypes` | mBiomeType


### `ViewRenderData`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mCameraPos
12 | (12) `glm::tvec3<float,0>` | mCameraTargetPos
24 | (16) `mce::Color` | mFogColor
40 | (16) `mce::Color` | mSkyColor
56 | (16) `mce::Color` | mSunriseColor
72 | (1) `bool` | mIsEndDimension
76 | (4) `float` | mFakeHDR
80 | (4) `float` | mMinParticleDistance
84 | (4) `float` | mRenderDistance
88 | (4) `float` | mSkyBrightnessScalar
92 | (1) `bool` | mCameraAboveClouds
93 | (1) `bool` | mCameraUnderLiquid
94 | (1) `bool` | mDrawClouds
95 | (1) `bool` | mDrawEntityEffects
96 | (1) `bool` | mDrawInsideCubes
97 | (1) `bool` | mDrawNameTags
98 | (1) `bool` | mDrawParticles
99 | (1) `bool` | mIsFancyRendering
100 | (1) `bool` | mDrawSky
101 | (1) `bool` | mDrawVRCursorInWorld
102 | (1) `bool` | mDrawVRHitFlash
103 | (1) `bool` | mDrawWeather
104 | (1) `bool` | mIsShadowPass
105 | (1) `bool` | mShowChunkMap


### `VisibilityNode`
Offset | Type | Name
-|-|-|-
0 | (6) `ByteMask[6]` | mVisibility


### `ViewRenderObject`
Offset | Type | Name
-|-|-|-
0 | (108) `ViewRenderData` | mViewData
108 | (1) `ClientRenderData` | mClientData
112 | (56) `CloudRenderObject` | mCloudState
168 | (1352) `ChunkRenderObjectCollection` | mChunksState
1520 | (112) `ActorShadowRenderObjectCollection` | mEntityShadowsState
1632 | (144) `ParticleRenderObjectCollection` | mParticleState
1776 | (576) `SkyRenderObject` | mSkyState
2352 | (10552) `WeatherRenderObject` | mWeatherState
12904 | (112) `CrackRenderObjectCollection` | mCrackState
13016 | (40) `NameTagRenderObjectCollection` | mNameTagState


### `VertIndices`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | vrt_i
4 | (4) `int` | tex_i
8 | (4) `int` | nrm_i


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent> *` | mView


### `VariantParameterList`
Offset | Type | Name
-|-|-|-
0 | (160) `VariantParameterList::Parameter[10]` | parameters


### `VariantParameterList::Parameter`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | type
8 | (8) `void *` | data


### `ViewedEntityContextT<EntityContext,PlayerTickComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent> *` | mView


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent> *` | mView


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent> *` | mView


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent> *` | mView


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::ViewedComponentWrapper<ProjectileComponent>`
Offset | Type | Name
-|-|-|-
0 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent> *` | mView
8 | (4) `const EntityId` | mEntity


### `VanillaActorData`
Offset | Type | Name
-|-|-|-
0 | (4) `ActorType` | mActorType
4 | (1) `bool` | mAllowSummon
8 | (8) `std::unique_ptr<Actor> *(__fastcall *)(std::unique_ptr<Actor> *result, ActorDefinitionGroup *, const ActorDefinitionIdentifier *)` | mFactory
16 | (8) `std::optional<int>` | experimentIndex


### `Village::DwellerData`
Offset | Type | Name
-|-|-|-
0 | (8) `Tick` | mTimeSinceTicked
8 | (12) `BlockPos` | mLastSavedPosition


### `VanillaItems::registerItems::__l2::<lambda_4b88ce55f1a38b6079b1ba725a247c08>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::registerItems::__l2::<lambda_1b2b284bc54314f149d601649aa8e0ff>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::registerItems::__l2::<lambda_90559bbe7914be5dfc7a8af4a5c45b24>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::registerItems::__l2::<lambda_5938727f1e17a4e879a8035bbdf207af>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::registerItems::__l2::<lambda_729a425f61fbcace02e2572ce428d37d>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::registerItems::__l2::<lambda_451496a4b1ff6a1f836e00dcfea4e6ee>`
Offset | Type | Name
-|-|-|-


### `VanillaItems::serverInitCreativeItemsCallback::__l13::<lambda_1005507c92b4817a6c1c75fa5110c130>`
Offset | Type | Name
-|-|-|-
0 | (8) `BlockDefinitionGroup *` | blockDefinitionGroup
8 | (8) `std::vector<Item *> (*)[9]` | ?


### `VanillaItems::serverInitCreativeItemsCallback::__l10::<lambda_94b7dd7becc4c0111f54db02f1989d76>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::vector<Item *> (*)[9]` | ?


### `VanillaItems::serverInitCreativeItemsCallback::__l88::<lambda_d3cb99921afe1d27e5c2a37346fc8ddd>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_85a5e292953b459ff467f05dbb43fb8f>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_e76d4e139a4c12dfe2c683002d04ac4a>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_159ed9db1e6e04fa24571a6bf01ce997>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_d6e89f84f17c6e5e0fc6aac99310013a>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_ea2d55cb57a08505c53e7d4068b908c1>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_2a78babea562bd96e7e7530b178e95e4>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_cab8ced90b4aac3e488cf4beb555b00b>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_95e2ab41ec42d49ff06910f7a0fc546b>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_cc53562d5e2589732fa072e8fa5762e6>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_80a0e944d92891bf7315ccf189b1f176>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_e4caf359e392ba1f8d4eb04dba1823c1>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_9468b49344527a2abbb205e1510f5b53>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_02e58e6f5516c205d02adf8fe1f3e3df>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_ac242902225f6a77e2e2224318853024>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_ed22c1cd52f95a9ba0dd1a8bdba60bcd>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_b8111d24a693bb149ae55c666516eea9>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_5ea5d76a9ead2e294b8b630cb0de7f93>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_3d9502ed95115c72d83bf2561a140435>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_dd636c355907df6ce357692719cde7a7>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_52de2e93c5b82e00f5a76791cf4fbd9e>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_221f570a648cfe7e7642e232b2f6fd30>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_0086d5b34401320a1fb2a444f822e051>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_b3d3b2b7492ac7d28f1adaf2654c830b>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_f025e7b657409b0df2fa094407858914>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_f822381505ee32fc6277bc0577a26c3b>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_6fb3d2ac11c17c3145092ff9d2ba8297>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_2bff6345ccfb1ca571d86cf4bc15a17e>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_fd645048ae3a850382f64f182a3e0363>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_5a273132f08e7a148f968fe1a95c9b9b>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_1de1c8e051bc1e75d774da84c556aba4>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_7c2f9fe258c150723abc11a7ca06d18f>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_eaeb7c0ac14a3f2ea45ecf190db5d70e>`
Offset | Type | Name
-|-|-|-


### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_d8cddec96da93d1fcb89e6872195e657>`
Offset | Type | Name
-|-|-|-


### `VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_3e5719820ab0f90dfc7613d37a124f51>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(void)>` | getValue


### `VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_a399d8dd5fd94eab242f091b2d1d0cce>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | setValue
64 | (64) `std::function<bool __cdecl(void)>` | isEnabled
128 | (32) `const std::string` | toggleName


### `VConnectionPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (4) `unsigned int` | mPacketUid
48 | (16) `std::shared_ptr<VConnBaseCtrlCMD>` | mVConnCmd


### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0
16 | (8) `entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent> *` | mView


### `VanillaOverworldBiomeSource`
Offset | Type | Name
-|-|-|-
0 | (24) `LayerBiomeSource` | baseclass_0
24 | (16) `std::shared_ptr<Layer<Biome *> const >` | m4x4ResolutionLayer


### `VectorEventData`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | id
4 | (4) `float` | x
8 | (4) `float` | y
12 | (4) `float` | z


### `VkExtensionProperties`
Offset | Type | Name
-|-|-|-
0 | (256) `char[256]` | extensionName
256 | (4) `unsigned int` | specVersion


### `VkLayerProperties`
Offset | Type | Name
-|-|-|-
0 | (256) `char[256]` | layerName
256 | (4) `unsigned int` | specVersion
260 | (4) `unsigned int` | implementationVersion
264 | (256) `char[256]` | description


### `VkImageMemoryBarrier`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | srcAccessMask
20 | (4) `unsigned int` | dstAccessMask
24 | (4) `VkImageLayout` | oldLayout
28 | (4) `VkImageLayout` | newLayout
32 | (4) `unsigned int` | srcQueueFamilyIndex
36 | (4) `unsigned int` | dstQueueFamilyIndex
40 | (8) `VkImage_T *` | image
48 | (20) `VkImageSubresourceRange` | subresourceRange


### `VkImageSubresourceRange`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | aspectMask
4 | (4) `unsigned int` | baseMipLevel
8 | (4) `unsigned int` | levelCount
12 | (4) `unsigned int` | baseArrayLayer
16 | (4) `unsigned int` | layerCount


### `VkImageCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `VkImageType` | imageType
24 | (4) `VkFormat` | format
28 | (12) `VkExtent3D` | extent
40 | (4) `unsigned int` | mipLevels
44 | (4) `unsigned int` | arrayLayers
48 | (4) `VkSampleCountFlagBits` | samples
52 | (4) `VkImageTiling` | tiling
56 | (4) `unsigned int` | usage
60 | (4) `VkSharingMode` | sharingMode
64 | (4) `unsigned int` | queueFamilyIndexCount
72 | (8) `const unsigned int *` | pQueueFamilyIndices
80 | (4) `VkImageLayout` | initialLayout


### `VkExtent3D`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | width
4 | (4) `unsigned int` | height
8 | (4) `unsigned int` | depth


### `VkMemoryRequirements`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | size
8 | (8) `unsigned __int64` | alignment
16 | (4) `unsigned int` | memoryTypeBits


### `VkMemoryAllocateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `unsigned __int64` | allocationSize
24 | (4) `unsigned int` | memoryTypeIndex


### `VkImageViewCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `VkImage_T *` | image
32 | (4) `VkImageViewType` | viewType
36 | (4) `VkFormat` | format
40 | (16) `VkComponentMapping` | components
56 | (20) `VkImageSubresourceRange` | subresourceRange


### `VkComponentMapping`
Offset | Type | Name
-|-|-|-
0 | (4) `VkComponentSwizzle` | r
4 | (4) `VkComponentSwizzle` | g
8 | (4) `VkComponentSwizzle` | b
12 | (4) `VkComponentSwizzle` | a


### `VkFramebufferCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `VkRenderPass_T *` | renderPass
32 | (4) `unsigned int` | attachmentCount
40 | (8) `VkImageView_T *const *` | pAttachments
48 | (4) `unsigned int` | width
52 | (4) `unsigned int` | height
56 | (4) `unsigned int` | layers


### `VkInstanceCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `const VkApplicationInfo *` | pApplicationInfo
32 | (4) `unsigned int` | enabledLayerCount
40 | (8) `const char *const *` | ppEnabledLayerNames
48 | (4) `unsigned int` | enabledExtensionCount
56 | (8) `const char *const *` | ppEnabledExtensionNames


### `VkDebugReportCallbackCreateInfoEXT`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `unsigned int (__fastcall *)(unsigned int, VkDebugReportObjectTypeEXT, unsigned __int64, unsigned __int64, int, const char *, const char *, void *)` | pfnCallback
32 | (8) `void *` | pUserData


### `VkImageFormatProperties`
Offset | Type | Name
-|-|-|-
0 | (12) `VkExtent3D` | maxExtent
12 | (4) `unsigned int` | maxMipLevels
16 | (4) `unsigned int` | maxArrayLayers
20 | (4) `unsigned int` | sampleCounts
24 | (8) `unsigned __int64` | maxResourceSize


### `VkDeviceCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | queueCreateInfoCount
24 | (8) `const VkDeviceQueueCreateInfo *` | pQueueCreateInfos
32 | (4) `unsigned int` | enabledLayerCount
40 | (8) `const char *const *` | ppEnabledLayerNames
48 | (4) `unsigned int` | enabledExtensionCount
56 | (8) `const char *const *` | ppEnabledExtensionNames
64 | (8) `const VkPhysicalDeviceFeatures *` | pEnabledFeatures


### `VkWin32SurfaceCreateInfoKHR`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `HINSTANCE__ *` | hinstance
32 | (8) `HWND__ *` | hwnd


### `VkSurfaceCapabilitiesKHR`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | minImageCount
4 | (4) `unsigned int` | maxImageCount
8 | (8) `VkExtent2D` | currentExtent
16 | (8) `VkExtent2D` | minImageExtent
24 | (8) `VkExtent2D` | maxImageExtent
32 | (4) `unsigned int` | maxImageArrayLayers
36 | (4) `unsigned int` | supportedTransforms
40 | (4) `VkSurfaceTransformFlagBitsKHR` | currentTransform
44 | (4) `unsigned int` | supportedCompositeAlpha
48 | (4) `unsigned int` | supportedUsageFlags


### `VkSurfaceFormatKHR`
Offset | Type | Name
-|-|-|-
0 | (4) `VkFormat` | format
4 | (4) `VkColorSpaceKHR` | colorSpace


### `VkSemaphoreCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags


### `VkRenderPassCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | attachmentCount
24 | (8) `const VkAttachmentDescription *` | pAttachments
32 | (4) `unsigned int` | subpassCount
40 | (8) `const VkSubpassDescription *` | pSubpasses
48 | (4) `unsigned int` | dependencyCount
56 | (8) `const VkSubpassDependency *` | pDependencies


### `VkFenceCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags


### `VkCommandPoolCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | queueFamilyIndex


### `VkPipelineCacheCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `unsigned __int64` | initialDataSize
32 | (8) `const void *` | pInitialData


### `VkPresentInfoKHR`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | waitSemaphoreCount
24 | (8) `VkSemaphore_T *const *` | pWaitSemaphores
32 | (4) `unsigned int` | swapchainCount
40 | (8) `VkSwapchainKHR_T *const *` | pSwapchains
48 | (8) `const unsigned int *` | pImageIndices
56 | (8) `VkResult *` | pResults


### `VkViewport`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | width
12 | (4) `float` | height
16 | (4) `float` | minDepth
20 | (4) `float` | maxDepth


### `VkRect2D`
Offset | Type | Name
-|-|-|-
0 | (8) `VkOffset2D` | offset
8 | (8) `VkExtent2D` | extent


### `VkOffset2D`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y


### `VkDescriptorSetAllocateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `VkDescriptorPool_T *` | descriptorPool
24 | (4) `unsigned int` | descriptorSetCount
32 | (8) `VkDescriptorSetLayout_T *const *` | pSetLayouts


### `VkWriteDescriptorSet`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `VkDescriptorSet_T *` | dstSet
24 | (4) `unsigned int` | dstBinding
28 | (4) `unsigned int` | dstArrayElement
32 | (4) `unsigned int` | descriptorCount
36 | (4) `VkDescriptorType` | descriptorType
40 | (8) `const VkDescriptorImageInfo *` | pImageInfo
48 | (8) `const VkDescriptorBufferInfo *` | pBufferInfo
56 | (8) `struct VkBufferView_T *const *` | pTexelBufferView


### `VkSamplerCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `VkFilter` | magFilter
24 | (4) `VkFilter` | minFilter
28 | (4) `VkSamplerMipmapMode` | mipmapMode
32 | (4) `VkSamplerAddressMode` | addressModeU
36 | (4) `VkSamplerAddressMode` | addressModeV
40 | (4) `VkSamplerAddressMode` | addressModeW
44 | (4) `float` | mipLodBias
48 | (4) `unsigned int` | anisotropyEnable
52 | (4) `float` | maxAnisotropy
56 | (4) `unsigned int` | compareEnable
60 | (4) `VkCompareOp` | compareOp
64 | (4) `float` | minLod
68 | (4) `float` | maxLod
72 | (4) `VkBorderColor` | borderColor
76 | (4) `unsigned int` | unnormalizedCoordinates


### `VkComputePipelineCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (48) `VkPipelineShaderStageCreateInfo` | stage
72 | (8) `VkPipelineLayout_T *` | layout
80 | (8) `struct VkPipeline_T *` | basePipelineHandle
88 | (4) `int` | basePipelineIndex


### `VkPipelineShaderStageCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `VkShaderStageFlagBits` | stage
24 | (8) `VkShaderModule_T *` | module
32 | (8) `const char *` | pName
40 | (8) `const VkSpecializationInfo *` | pSpecializationInfo


### `VkPipelineColorBlendStateCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | logicOpEnable
24 | (4) `VkLogicOp` | logicOp
28 | (4) `unsigned int` | attachmentCount
32 | (8) `const VkPipelineColorBlendAttachmentState *` | pAttachments
40 | (16) `float[4]` | blendConstants


### `VkPipelineVertexInputStateCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | vertexBindingDescriptionCount
24 | (8) `const VkVertexInputBindingDescription *` | pVertexBindingDescriptions
32 | (4) `unsigned int` | vertexAttributeDescriptionCount
40 | (8) `const VkVertexInputAttributeDescription *` | pVertexAttributeDescriptions


### `VkGraphicsPipelineCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | stageCount
24 | (8) `const VkPipelineShaderStageCreateInfo *` | pStages
32 | (8) `const VkPipelineVertexInputStateCreateInfo *` | pVertexInputState
40 | (8) `const VkPipelineInputAssemblyStateCreateInfo *` | pInputAssemblyState
48 | (8) `const VkPipelineTessellationStateCreateInfo *` | pTessellationState
56 | (8) `const VkPipelineViewportStateCreateInfo *` | pViewportState
64 | (8) `const VkPipelineRasterizationStateCreateInfo *` | pRasterizationState
72 | (8) `const VkPipelineMultisampleStateCreateInfo *` | pMultisampleState
80 | (8) `const VkPipelineDepthStencilStateCreateInfo *` | pDepthStencilState
88 | (8) `const VkPipelineColorBlendStateCreateInfo *` | pColorBlendState
96 | (8) `const VkPipelineDynamicStateCreateInfo *` | pDynamicState
104 | (8) `VkPipelineLayout_T *` | layout
112 | (8) `VkRenderPass_T *` | renderPass
120 | (4) `unsigned int` | subpass
128 | (8) `struct VkPipeline_T *` | basePipelineHandle
136 | (4) `int` | basePipelineIndex


### `VkClearAttachment`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | aspectMask
4 | (4) `unsigned int` | colorAttachment
8 | (16) `VkClearValue` | clearValue


### `VkClearValue`
Offset | Type | Name
-|-|-|-
0 | (16) `VkClearColorValue` | color
1 | (8) `VkClearDepthStencilValue` | depthStencil


### `VkClearColorValue`
Offset | Type | Name
-|-|-|-
0 | (16) `float[4]` | float32
1 | (16) `int[4]` | int32
2 | (16) `unsigned int[4]` | uint32


### `VkClearDepthStencilValue`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | depth
4 | (4) `unsigned int` | stencil


### `VkClearRect`
Offset | Type | Name
-|-|-|-
0 | (16) `VkRect2D` | rect
16 | (4) `unsigned int` | baseArrayLayer
20 | (4) `unsigned int` | layerCount


### `VkCommandBufferAllocateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `VkCommandPool_T *` | commandPool
24 | (4) `VkCommandBufferLevel` | level
28 | (4) `unsigned int` | commandBufferCount


### `VkCommandBufferBeginInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `const VkCommandBufferInheritanceInfo *` | pInheritanceInfo


### `VkSubmitInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | waitSemaphoreCount
24 | (8) `VkSemaphore_T *const *` | pWaitSemaphores
32 | (8) `const unsigned int *` | pWaitDstStageMask
40 | (4) `unsigned int` | commandBufferCount
48 | (8) `VkCommandBuffer_T *const *` | pCommandBuffers
56 | (4) `unsigned int` | signalSemaphoreCount
64 | (8) `VkSemaphore_T *const *` | pSignalSemaphores


### `VkBufferCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `unsigned __int64` | size
32 | (4) `unsigned int` | usage
36 | (4) `VkSharingMode` | sharingMode
40 | (4) `unsigned int` | queueFamilyIndexCount
48 | (8) `const unsigned int *` | pQueueFamilyIndices


### `VkBufferCopy`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | srcOffset
8 | (8) `unsigned __int64` | dstOffset
16 | (8) `unsigned __int64` | size


### `VkShaderModuleCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
24 | (8) `unsigned __int64` | codeSize
32 | (8) `const unsigned int *` | pCode


### `VkDescriptorSetLayoutCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | bindingCount
24 | (8) `const VkDescriptorSetLayoutBinding *` | pBindings


### `VkPipelineLayoutCreateInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (4) `unsigned int` | flags
20 | (4) `unsigned int` | setLayoutCount
24 | (8) `VkDescriptorSetLayout_T *const *` | pSetLayouts
32 | (4) `unsigned int` | pushConstantRangeCount
40 | (8) `const VkPushConstantRange *` | pPushConstantRanges


### `VkBufferImageCopy`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | bufferOffset
8 | (4) `unsigned int` | bufferRowLength
12 | (4) `unsigned int` | bufferImageHeight
16 | (16) `VkImageSubresourceLayers` | imageSubresource
32 | (12) `VkOffset3D` | imageOffset
44 | (12) `VkExtent3D` | imageExtent


### `VkImageSubresourceLayers`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | aspectMask
4 | (4) `unsigned int` | mipLevel
8 | (4) `unsigned int` | baseArrayLayer
12 | (4) `unsigned int` | layerCount


### `VkOffset3D`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (4) `int` | z


### `VkImageBlit`
Offset | Type | Name
-|-|-|-
0 | (16) `VkImageSubresourceLayers` | srcSubresource
16 | (24) `VkOffset3D[2]` | srcOffsets
40 | (16) `VkImageSubresourceLayers` | dstSubresource
56 | (24) `VkOffset3D[2]` | dstOffsets


### `VkRenderPassBeginInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `VkRenderPass_T *` | renderPass
24 | (8) `VkFramebuffer_T *` | framebuffer
32 | (16) `VkRect2D` | renderArea
48 | (4) `unsigned int` | clearValueCount
56 | (8) `const VkClearValue *` | pClearValues


### `VkMappedMemoryRange`
Offset | Type | Name
-|-|-|-
0 | (4) `VkStructureType` | sType
8 | (8) `const void *` | pNext
16 | (8) `VkDeviceMemory_T *` | memory
24 | (8) `unsigned __int64` | offset
32 | (8) `unsigned __int64` | size


### `VertexPT`
```
struct __cppobj VertexPT
{
  Vec3 pos;
  float u;
  float v;
};

```

### `VConnBaseCtrlCMD`
```
struct __cppobj __declspec(align(8)) VConnBaseCtrlCMD
{
  VConnBaseCtrlCMD_vtbl *__vftable /*VFT*/;
  unsigned __int16 mCtrlCmdId;
};

```

### `VConnBaseCtrlCMD_vtbl`
```
struct /*VFT*/ VConnBaseCtrlCMD_vtbl
{
  void (__fastcall *~VConnBaseCtrlCMD)(VConnBaseCtrlCMD *this);
  void (__fastcall *write)(VConnBaseCtrlCMD *this, BinaryStream *);
  void (__fastcall *read)(VConnBaseCtrlCMD *this, ReadOnlyBinaryStream *);
};

```

### `VConnectionPacket_vtbl`
```
struct /*VFT*/ VConnectionPacket_vtbl
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

### `VisualTreeProxyCallbacks`
```
const struct __cppobj VisualTreeProxyCallbacks
{
  std::function<std::vector<std::shared_ptr<UIControl>> __cdecl(std::function<bool __cdecl(ToggleComponent const &)>)> mGetVisibleControlsWith;
  std::function<bool __cdecl(std::string const &)> mVisibleControlExistsWithName;
  std::function<std::shared_ptr<UIControl> __cdecl(std::function<bool __cdecl(UIControl const &)> const &)> mGetFirstVisibleControl;
};

```

### `VisualTreeProxy`
```
struct __cppobj VisualTreeProxy
{
  const VisualTreeProxyCallbacks mCallbacks;
};

```

### `VisualTree_vtbl`
```
struct /*VFT*/ VisualTree_vtbl
{
  void (__fastcall *~ControlScreenAction)(ControlScreenAction *this);
  bool (__fastcall *getDirty)(ControlScreenAction *this, ui::DirtyFlag);
  bool (__fastcall *getDirty)(ControlScreenAction *this);
  ui::DirtyFlag (__fastcall *getDirtyValue)(ControlScreenAction *this);
  void (__fastcall *addDirtyFlag)(ControlScreenAction *this, ui::DirtyFlag);
  void (__fastcall *measureControls)(ControlScreenAction *this, UIControl *);
  void (__fastcall *markToRemoveDeadDependencies)(ControlScreenAction *this, std::shared_ptr<UIControl>);
  void (__fastcall *updateControlCollection)(ControlScreenAction *this, std::shared_ptr<UIControl>);
  void (__fastcall *updateControlCollectionFromRoot)(ControlScreenAction *this);
  void (__fastcall *removeFromControlCollection)(ControlScreenAction *this, std::shared_ptr<UIControl>);
  void (__fastcall *updateControlBinds)(ControlScreenAction *this, std::shared_ptr<UIControl>);
  void (__fastcall *updateBindsFromRoot)(ControlScreenAction *this);
  void (__fastcall *markTextEditFocusChanged)(ControlScreenAction *this);
  void (__fastcall *markTextEditAlwaysListeningChanged)(ControlScreenAction *this);
  std::shared_ptr<UIControl> *(__fastcall *getControlWithName)(ControlScreenAction *this, std::shared_ptr<UIControl> *result, const std::string *);
};

```

### `VoiceSystem`
```
struct __cppobj VoiceSystem
{
  VoiceSystem_vtbl *__vftable /*VFT*/;
  std::unique_ptr<VoiceDevice> mVoiceDevice;
};

```

### `VoiceSystem_vtbl`
```
struct /*VFT*/ VoiceSystem_vtbl
{
  void (__fastcall *~VoiceSystem)(VoiceSystem *this);
  bool (__fastcall *isActive)(VoiceSystem *this);
  void (__fastcall *init)(VoiceSystem *this, const std::string *);
  void (__fastcall *update)(VoiceSystem *this);
  void (__fastcall *reset)(VoiceSystem *this);
  void (__fastcall *addCommand)(VoiceSystem *this, MCGrammar, __int16, const std::string *, float);
  void (__fastcall *finalizeCommands)(VoiceSystem *this);
  void (__fastcall *switchToGrammar)(VoiceSystem *this, MCGrammar);
  MCGrammar (__fastcall *getCurrentGrammar)(VoiceSystem *this);
  void (__fastcall *setTranslationLanguage)(VoiceSystem *this, const std::string *);
};

```

### `VoiceDevice`
```
struct __cppobj VoiceDevice
{
  VoiceDevice_vtbl *__vftable /*VFT*/;
  std::queue<unsigned int> mVoiceEventVector;
  std::string mDictation;
};

```

### `VoiceDevice_vtbl`
```
struct /*VFT*/ VoiceDevice_vtbl
{
  void (__fastcall *~VoiceDevice)(VoiceDevice *this);
  bool (__fastcall *voiceEventPresent)(VoiceDevice *this);
  const unsigned int *(__fastcall *getNextVoiceEvent)(VoiceDevice *this);
  void (__fastcall *setDictation)(VoiceDevice *this, const std::string *);
  std::string *(__fastcall *getDictationStr)(VoiceDevice *this, std::string *result);
  void (__fastcall *addVoiceEvent)(VoiceDevice *this, unsigned int);
  void (__fastcall *clearEvents)(VoiceDevice *this);
};

```

### `Village`
```
struct __cppobj Village
{
  mce::UUID mUniqueID;
  Dimension *mDimension;
  std::array<std::vector<std::weak_ptr<POIInstance>>,3> mUnclaimedPOIStacks;
  std::unordered_map<ActorUniqueID,std::vector<std::weak_ptr<POIInstance>>> mClaimedPOIs;
  std::array<std::unordered_map<ActorUniqueID,Village::DwellerData>,4> mDwellers;
  AABB mBounds;
  AABB mStaticRaidBounds;
  unsigned __int8 mVillageVersion;
  Tick mGameTick;
  Tick mSaveTick;
  Tick mRingTick;
  Tick mNoBreedTimer;
  Tick mBadStandingDecayTimer;
  Tick mGoodStandingDecayTimer;
  Tick mPassiveDwellerSpawnTimer;
  __int64 mVillageHeroTimer;
  int mInitializationTimer;
  std::unordered_map<ActorUniqueID,int> mPlayerStanding;
  std::unordered_map<ActorUniqueID,Village::DwellerData> mAggressors;
  std::vector<std::pair<ActorUniqueID,Tick>> mVillagerWorkTimestamps;
  bool mVillageInitialized;
  const HashedString mNitwitFamily;
  const HashedString mVillagePrefix;
  std::unique_ptr<Raid> mRaid;
  std::unordered_set<ActorUniqueID> mSoundTheAlarmPlayerList;
};

```

### `VillageManager`
```
struct __cppobj VillageManager
{
  Dimension *mDimension;
  std::deque<ActorUniqueID> mFindPOIQueries;
  std::vector<std::shared_ptr<POIInstance>> mUnclusteredPOIs;
  std::unordered_map<mce::UUID,std::shared_ptr<Village>> mVillages;
  std::array<std::unordered_map<BlockPos,std::shared_ptr<POIInstance>>,3> mClusteredPOIs;
  std::unordered_map<BlockLegacy const *,std::unique_ptr<POIBlueprint>> mPOIBlueprints;
  Tick mTickCount;
  WanderingTraderScheduler mWanderingTraderScheduler;
  bool mFinishedQueryScan;
  int mCurrentXScan;
  int mCurrentYScan;
  int mCurrentZScan;
};

```

### `VanillaStates::CachedItemStateMapPtr`
```
struct __cppobj __declspec(align(8)) VanillaStates::CachedItemStateMapPtr
{
  const ItemState *ptr;
  int mapVersion;
};

```

### `VanillaBlockUseEventWhiteList`
```
struct __cppobj VanillaBlockUseEventWhiteList
{
  std::unordered_set<std::string> mWhiteList;
};

```

### `VarIntDataInput`
```
struct __cppobj VarIntDataInput : BytesDataInput
{
  ReadOnlyBinaryStream *mStream;
};

```

### `VarIntDataInput_vtbl`
```
struct /*VFT*/ VarIntDataInput_vtbl
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

### `VarIntDataOutput`
```
struct __cppobj VarIntDataOutput : BytesDataOutput
{
  BinaryStream *mStream;
};

```

### `VarIntDataOutput_vtbl`
```
struct /*VFT*/ VarIntDataOutput_vtbl
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

### `VanillaDimensions::DimensionInfoAttributes`
```
struct VanillaDimensions::DimensionInfoAttributes
{
  GeneratorType mDimensionType;
  GeneratorType mGenatorType;
};

```

### `VanillaDimensions`
```
struct __cppobj VanillaDimensions
{
};

```

### `VoiceCommandData`
```
struct __cppobj VoiceCommandData
{
  std::string mButtonName;
  std::string mLocalizedCommandString;
  MCGrammar mGrammar;
  float mConfidence;
};

```

### `VanillaBlockTessellation::_createMaterialOverridePipelineDescription::__l2::<lambda_22ea20fed205a47f74b0b808342f7e62>`
```
struct __cppobj VanillaBlockTessellation::_createMaterialOverridePipelineDescription::__l2::<lambda_22ea20fed205a47f74b0b808342f7e62>
{
};

```

### `VanillaBlockTessellation::_createWorldPipelineDescription::__l2::<lambda_3ab0c3a900f34c539801d109b2a6da25>`
```
struct __cppobj VanillaBlockTessellation::_createWorldPipelineDescription::__l2::<lambda_3ab0c3a900f34c539801d109b2a6da25>
{
};

```

### `value_entW`
```
struct __declspec(align(8)) value_entW
{
  wchar_t *ve_valuename;
  unsigned int ve_valuelen;
  unsigned __int64 ve_valueptr;
  unsigned int ve_type;
};

```

### `value_entA`
```
struct __declspec(align(8)) value_entA
{
  char *ve_valuename;
  unsigned int ve_valuelen;
  unsigned __int64 ve_valueptr;
  unsigned int ve_type;
};

```

### `val_context`
```
struct val_context
{
  int valuelen;
  void *value_context;
  void *val_buff_ptr;
};

```

### `VanillaCameraLoader`
```
struct __cppobj VanillaCameraLoader : CameraLoader
{
};

```

### `VanillaCameraLoader_vtbl`
```
struct /*VFT*/ VanillaCameraLoader_vtbl
{
  void (__fastcall *~CameraLoader)(CameraLoader *this);
  void (__fastcall *setupFallbackCamera)(CameraLoader *this, CameraDirector *);
};

```

### `VerifyLocalStage`
```
struct __cppobj VerifyLocalStage : BaseStage
{
};

```

### `VerifyLocalStage_vtbl`
```
struct /*VFT*/ VerifyLocalStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `VanillaItems`
```
struct __cppobj VanillaItems
{
};

```

### `VanillaItemTags`
```
struct __cppobj VanillaItemTags
{
};

```

### `VisualTree::_destroyAsync::__l2::<lambda_be72705aae2c4d37669c448562add4cc>`
```
struct __cppobj VisualTree::_destroyAsync::__l2::<lambda_be72705aae2c4d37669c448562add4cc>
{
  std::shared_ptr<UIControl> control;
  TaskGroup *taskGroup;
};

```

### `VisualTree::measureControls::__l5::<lambda_9363673c9b1d3c1a7cf0c537fc55a0e7>`
```
struct __cppobj VisualTree::measureControls::__l5::<lambda_9363673c9b1d3c1a7cf0c537fc55a0e7>
{
  VisualTree *const __this;
};

```

### `VisualTree::measureControls::__l5::<lambda_9363673c9b1d3c1a7cf0c537fc55a0e7>::()::__l9::<lambda_0c9d7624c3c5e1f38350bf6650218543>`
```
struct __cppobj VisualTree::measureControls::__l5::<lambda_9363673c9b1d3c1a7cf0c537fc55a0e7>::()::__l9::<lambda_0c9d7624c3c5e1f38350bf6650218543>
{
  VisualTree *const __this;
};

```

### `VisualTree::getControlByName::__l2::<lambda_5bf6996d8987e3acbf4f7b6723548f6b>`
```
struct __cppobj VisualTree::getControlByName::__l2::<lambda_5bf6996d8987e3acbf4f7b6723548f6b>
{
  std::string *name;
};

```

### `VisualTree::getVisibleControls::__l2::<lambda_711e457fa010a57a92c5843911831914>`
```
struct __cppobj VisualTree::getVisibleControls::__l2::<lambda_711e457fa010a57a92c5843911831914>
{
  std::function<bool __cdecl(UIControl const &)> *predicate;
  std::vector<std::shared_ptr<UIControl>> *result;
};

```

### `VisualTree::{ctor}::__l2::<lambda_c66183de8ff8a09846ac930a68175c77>`
```
struct __cppobj VisualTree::{ctor}::__l2::<lambda_c66183de8ff8a09846ac930a68175c77>
{
  VisualTree *const __this;
};

```

### `VisualTree::{ctor}::__l2::<lambda_08a5c65ce1312bf57c1a85e93d9dc656>`
```
struct __cppobj VisualTree::{ctor}::__l2::<lambda_08a5c65ce1312bf57c1a85e93d9dc656>
{
  VisualTree *const __this;
};

```

### `VisualTree::{ctor}::__l2::<lambda_d0ab3a76da77c4df1982cdc359e625be>`
```
struct __cppobj VisualTree::{ctor}::__l2::<lambda_d0ab3a76da77c4df1982cdc359e625be>
{
  VisualTree *const __this;
};

```

### `VisualTree::{ctor}::__l2::<lambda_08a5c65ce1312bf57c1a85e93d9dc656>::()::__l2::<lambda_e4762d06132e645ae086ef9e5c625a63>`
```
struct __cppobj VisualTree::{ctor}::__l2::<lambda_08a5c65ce1312bf57c1a85e93d9dc656>::()::__l2::<lambda_e4762d06132e645ae086ef9e5c625a63>
{
  const std::string *controlName;
};

```

### `VisualTree::getVisibleControlsWith::__l2::<lambda_df7f0efd3e68f966bd729ae33da654c2>`
```
struct __cppobj VisualTree::getVisibleControlsWith::__l2::<lambda_df7f0efd3e68f966bd729ae33da654c2>
{
  std::function<bool __cdecl(ToggleComponent const &)> *predicate;
};

```

### `VRAlignScreenController`
```
struct __cppobj __declspec(align(8)) VRAlignScreenController : MinecraftScreenController
{
  bool mIsFirstTick;
};

```

### `VRAlignScreenController_vtbl`
```
struct /*VFT*/ VRAlignScreenController_vtbl
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

### `VRAlignScreenController::_registerBindings::__l18::<lambda_632a5e9b1f56b12538cb4a23fa81ef9c>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l18::<lambda_632a5e9b1f56b12538cb4a23fa81ef9c>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l18::<lambda_bb0cf38d9f038a76a04c7d9c6af3ad8a>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l18::<lambda_bb0cf38d9f038a76a04c7d9c6af3ad8a>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l18::<lambda_d6881a36f4f55cd8ba3682060823197a>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l18::<lambda_d6881a36f4f55cd8ba3682060823197a>
{
};

```

### `VRAlignScreenController::_registerBindings::__l18::<lambda_b9330bc67a83f90302ba49a4806f7c77>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l18::<lambda_b9330bc67a83f90302ba49a4806f7c77>
{
};

```

### `VRAlignScreenController::_registerBindings::__l16::<lambda_f51437435c8fb1ab5907efe8d8caef2e>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l16::<lambda_f51437435c8fb1ab5907efe8d8caef2e>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l16::<lambda_c81148aa01e63485457a4d82cfa56e33>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l16::<lambda_c81148aa01e63485457a4d82cfa56e33>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l16::<lambda_c97e26755cc0040f1d06846de06c6f24>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l16::<lambda_c97e26755cc0040f1d06846de06c6f24>
{
  VRAlignScreenController *const __this;
};

```

### `VRAlignScreenController::_registerBindings::__l16::<lambda_43011c09e982c3c600710d92dbfa38b3>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l16::<lambda_43011c09e982c3c600710d92dbfa38b3>
{
};

```

### `VRAlignScreenController::_registerBindings::__l12::<lambda_21864fb17f676ca1bee8084aebc48f05>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l12::<lambda_21864fb17f676ca1bee8084aebc48f05>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l12::<lambda_bf99d61f2198a2c2ce6f8e8abaac9727>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l12::<lambda_bf99d61f2198a2c2ce6f8e8abaac9727>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l12::<lambda_9df8e2bdd937937437937613228d257d>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l12::<lambda_9df8e2bdd937937437937613228d257d>
{
  VRAlignScreenController *const __this;
};

```

### `VRAlignScreenController::_registerBindings::__l12::<lambda_da3a758bcff44763bdf169ce670a75f8>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l12::<lambda_da3a758bcff44763bdf169ce670a75f8>
{
};

```

### `VRAlignScreenController::_registerBindings::__l8::<lambda_b800891bc564048b29c0c02a60f0e358>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l8::<lambda_b800891bc564048b29c0c02a60f0e358>
{
  const std::string platformAlignmentPromptTTS;
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l8::<lambda_7afc3ae7593abd7c81a4414a6dfa7e77>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l8::<lambda_7afc3ae7593abd7c81a4414a6dfa7e77>
{
  const std::string advancementPrompt;
};

```

### `VRAlignScreenController::_registerBindings::__l8::<lambda_f82042af1d9be01d44a5557446d6b13a>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l8::<lambda_f82042af1d9be01d44a5557446d6b13a>
{
};

```

### `VRAlignScreenController::_registerBindings::__l8::<lambda_b90596a92fd84f3a044001ed8d003dbd>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l8::<lambda_b90596a92fd84f3a044001ed8d003dbd>
{
};

```

### `VRAlignScreenController::_registerBindings::__l2::<lambda_fba67360512fc78407417e1e7e01a0f9>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l2::<lambda_fba67360512fc78407417e1e7e01a0f9>
{
  const std::string platformRecalibrationMessage;
};

```

### `VRAlignScreenController::_registerBindings::__l5::<lambda_226d88733df204eb37f657fc3df5c061>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l5::<lambda_226d88733df204eb37f657fc3df5c061>
{
  const std::string platformRecalibrationMessageTTS;
  const std::string recalibrationMessage;
};

```

### `VRAlignScreenController::_registerBindings::__l5::<lambda_b97c60cddf9fd5bbca1311e9c1d2d8f1>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l5::<lambda_b97c60cddf9fd5bbca1311e9c1d2d8f1>
{
  VRAlignScreenController *const __this;
  const std::string recalibrationMessage;
};

```

### `VRAlignScreenController::_registerBindings::__l2::<lambda_8a77f2e1cc1f7d672ed79331fd314911>`
```
struct __cppobj VRAlignScreenController::_registerBindings::__l2::<lambda_8a77f2e1cc1f7d672ed79331fd314911>
{
};

```

### `VRAlignScreenController::_registerEventHandlers::__l2::<lambda_0d16e65bc9a014595d6fe2b7a0e08ead>`
```
struct __cppobj VRAlignScreenController::_registerEventHandlers::__l2::<lambda_0d16e65bc9a014595d6fe2b7a0e08ead>
{
  VRAlignScreenController *const __this;
};

```

### `VRAlignScreenController::_registerEventHandlers::__l2::<lambda_e79228810ffc936702222875f0c82ae7>`
```
struct __cppobj VRAlignScreenController::_registerEventHandlers::__l2::<lambda_e79228810ffc936702222875f0c82ae7>
{
  VRAlignScreenController *const __this;
};

```

### `VoiceScreenController::PlayerListInfo`
```
struct __cppobj VoiceScreenController::PlayerListInfo
{
  std::string playerName;
  mce::UUID uuid;
};

```

### `VoiceScreenController`
```
struct __cppobj VoiceScreenController : MinecraftScreenController
{
  std::unordered_map<mce::UUID,PlayerListEntry> mPlayerLobbyList;
  std::vector<VoiceScreenController::PlayerListInfo> mPlayerList;
};

```

### `VoiceScreenController_vtbl`
```
struct /*VFT*/ VoiceScreenController_vtbl
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

### `VoiceTransScreenController`
```
struct __cppobj VoiceTransScreenController : MinecraftScreenController
{
  bool mShowTrans;
  bool mShowRecord;
  int mStartTime;
  int mEndTime;
  int mLastTime;
  int deltaTime;
  const int maxDurationTime;
  bool mHasStartRecord;
  bool mRecordFinish;
  bool mTranslatedFinish;
  bool mUploadFinish;
  bool mShowDialog;
  bool mHasStopRecord;
  bool mInitProgressBarSuccess;
  bool mHasVoicePermission;
  bool mCurrentIsInputMuted;
  glm::tvec2<float,0> mProgressBarSize;
  const std::string mScreenName;
  const std::string mImageProgressBarPath;
};

```

### `VoiceTransScreenController_vtbl`
```
struct /*VFT*/ VoiceTransScreenController_vtbl
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

### `VisualTree::getFirstControlWith::__l2::<lambda_b78f6c75ba48d0562d703985e686a740>`
```
struct __cppobj VisualTree::getFirstControlWith::__l2::<lambda_b78f6c75ba48d0562d703985e686a740>
{
  const std::function<bool __cdecl(GridItemComponent const &)> *predicate;
};

```

### `VisualTree::getFirstVisibleControlWith::__l2::<lambda_573b4ccaee30e69dc91b2ec619d6e3a9>`
```
struct __cppobj VisualTree::getFirstVisibleControlWith::__l2::<lambda_573b4ccaee30e69dc91b2ec619d6e3a9>
{
  const std::function<bool __cdecl(GridComponent const &)> *predicate;
};

```

### `VisualTree::getFirstVisibleControlWith::__l2::<lambda_aa4ebcad635233c609c130f9a6cf4fc3>`
```
struct __cppobj VisualTree::getFirstVisibleControlWith::__l2::<lambda_aa4ebcad635233c609c130f9a6cf4fc3>
{
  const std::function<bool __cdecl(FocusComponent const &)> *predicate;
};

```

### `VanillaBiomesMod`
```
struct __cppobj VanillaBiomesMod
{
};

```

### `VanillaBlockUpdater`
```
struct __cppobj VanillaBlockUpdater
{
};

```

### `VineBlock`
```
struct __cppobj VineBlock : BlockLegacy
{
};

```

### `VineBlock_vtbl`
```
struct /*VFT*/ VineBlock_vtbl
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

### `VisibilityExtimator`
```
struct __cppobj VisibilityExtimator
{
  Stopwatch timer;
  BlockPos mOrigin;
  int mEmptyBlocks;
  std::array<enum VisibilityExtimator::BlockState,4096> mBlocks;
  std::deque<SubChunkBlockPos> mFloodQueue;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::ViewedComponentWrapper<BlockPosTrackerComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::ViewedComponentWrapper<BlockPosTrackerComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::IsInViewedSet<BlockPosTrackerComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockPosTrackerComponent>::IsInViewedSet<BlockPosTrackerComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,HitResultComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,HitResultComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,HitResultComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,HitResultComponent>::ViewedComponentWrapper<HitResultComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,HitResultComponent>::ViewedComponentWrapper<HitResultComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,HitResultComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,HitResultComponent>::IsInViewedSet<HitResultComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,HitResultComponent>::IsInViewedSet<HitResultComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::ViewedComponentWrapper<HomeComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::ViewedComponentWrapper<HomeComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::IsInViewedSet<HomeComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::IsInViewedSet<HomeComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HomeComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::ViewedComponentWrapper<InstantDespawnComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::ViewedComponentWrapper<InstantDespawnComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::IsInViewedSet<InstantDespawnComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::IsInViewedSet<InstantDespawnComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,InstantDespawnComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent>::ViewedComponentWrapper<PlayerTickComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,PlayerTickComponent>::ViewedComponentWrapper<PlayerTickComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent>::IsInViewedSet<PlayerTickComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,PlayerTickComponent>::IsInViewedSet<PlayerTickComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<PlayerTickComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<PlayerTickComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<ServerPlayerMovementComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<ServerPlayerMovementComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<PlayerTickComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<PlayerTickComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<ServerPlayerMovementComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<ServerPlayerMovementComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,PlayerTickComponent,ServerPlayerMovementComponent,ActorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper`
```
struct __cppobj VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper
{
  VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper_vtbl *__vftable /*VFT*/;
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper_vtbl
{
  void (__fastcall *~MaterialHelper)(VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper *this);
  bool (__fastcall *isFoundationBlock)(VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper *this, const Block *);
  bool (__fastcall *isWaterBlock)(VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper *this, const Block *);
  bool (__fastcall *isSolidBlock)(VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper *this, const Block *);
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::CappedSurfaceBuilder : ISurfaceBuilder
{
  unsigned int mLevelSeed;
  std::unique_ptr<PerlinNoise> mBeachNoise;
  std::unique_ptr<VanillaSurfaceBuilders::CappedSurfaceBuilder::MaterialHelper> mMaterialHelper;
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::CappedSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder::buildSurfaceAt::__l23::<lambda_96b3125da2805fe539de889b9d4c11ff>`
```
struct __cppobj __declspec(align(8)) VanillaSurfaceBuilders::CappedSurfaceBuilder::buildSurfaceAt::__l23::<lambda_96b3125da2805fe539de889b9d4c11ff>
{
  const bool placeBeach;
  const Block *floorMaterial;
  const Block *beachMaterial;
  __int16 seaLevel;
};

```

### `VanillaSurfaceBuilders::CappedSurfaceBuilder::buildSurfaceAt::__l21::<lambda_60e0528d552d071d0e4d3467b7583cdc>`
```
struct __cppobj VanillaSurfaceBuilders::CappedSurfaceBuilder::buildSurfaceAt::__l21::<lambda_60e0528d552d071d0e4d3467b7583cdc>
{
  const Block *ceilingMaterial;
};

```

### `VanillaBlockStateTransformUtils`
```
struct __cppobj VanillaBlockStateTransformUtils
{
};

```

### `Village::StandingModifiers`
```
struct __cppobj Village::StandingModifiers
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::ViewedComponentWrapper<AngryComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::ViewedComponentWrapper<AngryComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::IsInViewedSet<AngryComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AngryComponent>::IsInViewedSet<AngryComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::ViewedComponentWrapper<AreaAttackComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::ViewedComponentWrapper<AreaAttackComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::IsInViewedSet<AreaAttackComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AreaAttackComponent>::IsInViewedSet<AreaAttackComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::ViewedComponentWrapper<BlockBreakSensorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::ViewedComponentWrapper<BlockBreakSensorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::IsInViewedSet<BlockBreakSensorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BlockBreakSensorComponent>::IsInViewedSet<BlockBreakSensorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::ViewedComponentWrapper<BreakBlocksComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::ViewedComponentWrapper<BreakBlocksComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::IsInViewedSet<BreakBlocksComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreakBlocksComponent>::IsInViewedSet<BreakBlocksComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::ViewedComponentWrapper<BreathableComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::ViewedComponentWrapper<BreathableComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::IsInViewedSet<BreathableComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,BreathableComponent>::IsInViewedSet<BreathableComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::ViewedComponentWrapper<CommandBlockComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::ViewedComponentWrapper<CommandBlockComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::IsInViewedSet<CommandBlockComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,CommandBlockComponent>::IsInViewedSet<CommandBlockComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::ViewedComponentWrapper<DamageOverTimeComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::ViewedComponentWrapper<DamageOverTimeComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::IsInViewedSet<DamageOverTimeComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DamageOverTimeComponent>::IsInViewedSet<DamageOverTimeComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::ViewedComponentWrapper<DespawnComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::ViewedComponentWrapper<DespawnComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::IsInViewedSet<DespawnComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::IsInViewedSet<DespawnComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,DespawnComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::ViewedComponentWrapper<EntitySensorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::ViewedComponentWrapper<EntitySensorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::IsInViewedSet<EntitySensorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::IsInViewedSet<EntitySensorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,EntitySensorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ActorFlagComponent<EnvironmentSensorFlag> >`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ActorFlagComponent<EnvironmentSensorFlag> > : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ActorFlagComponent<EnvironmentSensorFlag> > *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,GoalSelectorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,HurtOnConditionComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::ViewedComponentWrapper<OpenDoorAnnotationComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::ViewedComponentWrapper<OpenDoorAnnotationComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::IsInViewedSet<OpenDoorAnnotationComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::IsInViewedSet<OpenDoorAnnotationComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,OpenDoorAnnotationComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::IsInViewedSet<ProjectileComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ProjectileComponent>::IsInViewedSet<ProjectileComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::ViewedComponentWrapper<SpawnActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::ViewedComponentWrapper<SpawnActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::IsInViewedSet<SpawnActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,SpawnActorComponent>::IsInViewedSet<SpawnActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::ViewedComponentWrapper<TimerComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::ViewedComponentWrapper<TimerComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::IsInViewedSet<TimerComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::IsInViewedSet<TimerComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TimerComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `VanillaAppConfigs`
```
struct __cppobj VanillaAppConfigs : AppConfigs
{
};

```

### `VanillaAppConfigs_vtbl`
```
struct /*VFT*/ VanillaAppConfigs_vtbl
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

### `Vec3Option`
```
struct __cppobj Vec3Option : Option
{
  glm::tvec3<float,0> mValue;
  glm::tvec3<float,0> mDefaultValue;
};

```

### `Vec3Option_vtbl`
```
struct /*VFT*/ Vec3Option_vtbl
{
  void (__fastcall *~Option)(Option *this);
  void (__fastcall *save)(Option *this, std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *load)(Option *this, const Json::Value *);
  void (__fastcall *load)(Option *this, std::map<std::string,std::string> *);
  void (__fastcall *load)(Option *this, const std::string *);
};

```

### `VirtualFile`
```
struct __cppobj VirtualFile
{
  Core::PathBuffer<std::string > mPath;
  std::string mContent;
};

```

### `VirtualCommandOrigin`
```
struct __cppobj VirtualCommandOrigin : CommandOrigin
{
  Vec3 mPos;
  std::unique_ptr<CommandOrigin> mOrigin;
  std::unique_ptr<CommandOrigin> mOutputReceiver;
};

```

### `VirtualCommandOrigin_vtbl`
```
struct /*VFT*/ VirtualCommandOrigin_vtbl
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

### `VariantDefinition`
```
struct __cppobj VariantDefinition
{
  int mVariantChoice;
};

```

### `VindicationIllager`
```
struct __cppobj VindicationIllager : HumanoidMonster
{
};

```

### `VexCopyOwnerTargetGoal`
```
struct __cppobj VexCopyOwnerTargetGoal : TargetGoal
{
};

```

### `VexCopyOwnerTargetGoal_vtbl`
```
struct /*VFT*/ VexCopyOwnerTargetGoal_vtbl
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
  bool (__fastcall *_canAttack)(TargetGoal *this, Mob *, Actor *, bool, bool, const MobDescriptor **);
};

```

### `VillageManager::loadAllVillages::__l2::<lambda_9d93ab856a34c8dd9c070fc801e8b9a6>`
```
struct __cppobj VillageManager::loadAllVillages::__l2::<lambda_9d93ab856a34c8dd9c070fc801e8b9a6>
{
  VillageManager *const __this;
};

```

### `Village::_applyHeroOfTheVillageEffect::__l2::<lambda_3b227706c80122b762e8e7e216733b48>`
```
struct __cppobj Village::_applyHeroOfTheVillageEffect::__l2::<lambda_3b227706c80122b762e8e7e216733b48>
{
  MobEffectInstance *effect;
  const AABB *effectBounds;
};

```

### `Village::fireSoundTheAlarm::__l5::<lambda_c9c3893cbc8afc8e2f41a0a69f34aa42>`
```
struct __cppobj Village::fireSoundTheAlarm::__l5::<lambda_c9c3893cbc8afc8e2f41a0a69f34aa42>
{
  Village *const __this;
};

```

### `Village::_spawnRaidGroup::__l5::<lambda_8db5e016651a44438e38d9ec4e523fd2>`
```
struct __cppobj Village::_spawnRaidGroup::__l5::<lambda_8db5e016651a44438e38d9ec4e523fd2>
{
};

```

### `Village::_findPlayerCentricSpawnPointForRaid::__l2::<lambda_7e6d7dfc5d305936c7a9aa4b37493584>`
```
struct __cppobj Village::_findPlayerCentricSpawnPointForRaid::__l2::<lambda_7e6d7dfc5d305936c7a9aa4b37493584>
{
  const Village *const __this;
  Player **raidPlayer;
  float *closestMatchDist;
  const Vec3 *center;
};

```

### `Village::_sendRaidUpdateToPlayersInVillage::__l2::<lambda_f3dbaad973d8593ff82cea5728a58fe2>`
```
struct __cppobj __declspec(align(8)) Village::_sendRaidUpdateToPlayersInVillage::__l2::<lambda_f3dbaad973d8593ff82cea5728a58fe2>
{
  const Village *const __this;
  const bool wonRaid;
};

```

### `Village::_createRaid::__l5::<lambda_e4381ca1d793f0cf12a3a3844dfc26b9>`
```
struct __cppobj Village::_createRaid::__l5::<lambda_e4381ca1d793f0cf12a3a3844dfc26b9>
{
  Village *const __this;
};

```

### `Village::_createRaid::__l5::<lambda_ac14a3605af1c452fd433fad79088702>`
```
struct __cppobj Village::_createRaid::__l5::<lambda_ac14a3605af1c452fd433fad79088702>
{
  Village *const __this;
};

```

### `Village::_createRaid::__l5::<lambda_ac14a3605af1c452fd433fad79088702>::()::__l2::<lambda_e0d315fe71dca83c09ead8129a086410>`
```
struct __cppobj Village::_createRaid::__l5::<lambda_ac14a3605af1c452fd433fad79088702>::()::__l2::<lambda_e0d315fe71dca83c09ead8129a086410>
{
  OnScreenTextureAnimationPacket *packet;
  const AABB *effectBounds;
};

```

### `Village::_createRaid::__l5::<lambda_4b1b8d671d79a17c81c90368748176c4>`
```
struct __cppobj Village::_createRaid::__l5::<lambda_4b1b8d671d79a17c81c90368748176c4>
{
  Village *const __this;
};

```

### `Village::tick::__l27::<lambda_f3841702211d4e68dc00d3982cf0b8bd>`
```
struct __cppobj Village::tick::__l27::<lambda_f3841702211d4e68dc00d3982cf0b8bd>
{
  Village *const __this;
};

```

### `Village::_createRaid::__l2::<lambda_1e609e8423200509422b57fa4e56c7bd>`
```
struct __cppobj Village::_createRaid::__l2::<lambda_1e609e8423200509422b57fa4e56c7bd>
{
  Village *const __this;
};

```

### `Village::_createRaid::__l2::<lambda_1a29185176a47f772799d7d827797394>`
```
struct __cppobj Village::_createRaid::__l2::<lambda_1a29185176a47f772799d7d827797394>
{
  Village *const __this;
};

```

### `Village::_createRaid::__l2::<lambda_567a9d9cd6f457f3efc4e18babc7c4cd>`
```
struct __cppobj Village::_createRaid::__l2::<lambda_567a9d9cd6f457f3efc4e18babc7c4cd>
{
  Village *const __this;
};

```

### `Vex`
```
struct __cppobj Vex : Monster
{
};

```

### `VillagerBase`
```
struct __cppobj __declspec(align(8)) VillagerBase : Mob
{
  bool mChasing;
  bool mWillingToBreed;
};

```

### `Villager`
```
struct __cppobj Villager : VillagerBase
{
};

```

### `VillagerV2`
```
struct __cppobj __declspec(align(8)) VillagerV2 : VillagerBase
{
  float mRaiseArmValue;
};

```

### `VillagerV2::getInteraction::__l8::<lambda_5aa6f8473917f72a47767a2cc68f8883>`
```
struct __cppobj VillagerV2::getInteraction::__l8::<lambda_5aa6f8473917f72a47767a2cc68f8883>
{
  VillagerV2 *const __this;
};

```

### `VanillaItemTiers`
```
struct __cppobj VanillaItemTiers
{
};

```

### `VanillaOverworldBiomeSource_vtbl`
```
struct /*VFT*/ VanillaOverworldBiomeSource_vtbl
{
  void (__fastcall *~BiomeSource)(BiomeSource *this);
  void (__fastcall *fillBiomes)(BiomeSource *this, LevelChunk *);
  BiomeArea *(__fastcall *getBiomeArea)(BiomeSource *this, BiomeArea *result, const BoundingBox *, unsigned int);
  bool (__fastcall *containsOnly)(BiomeSource *this, int, int, int, gsl::span<int const ,-1>);
  const Biome *(__fastcall *getBiome)(BiomeSource *this, int, int);
};

```

### `VanillaSurfaceBuilders::OverworldDefaultSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::OverworldDefaultSurfaceBuilder : ISurfaceBuilder
{
};

```

### `VanillaSurfaceBuilders::OverworldDefaultSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::OverworldDefaultSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaBlockTags`
```
struct __cppobj VanillaBlockTags
{
};

```

### `VanillaStates::<lambda_fe6e7fcd2a5a7eb1ab6a0363be1760b8>::()::__l2::Literal`
```
struct __cppobj VanillaStates::<lambda_fe6e7fcd2a5a7eb1ab6a0363be1760b8>::()::__l2::Literal
{
};

```

### `VanillaStates::<lambda_fe6e7fcd2a5a7eb1ab6a0363be1760b8>`
```
struct __cppobj VanillaStates::<lambda_fe6e7fcd2a5a7eb1ab6a0363be1760b8>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ce8f42aceb71021379fa0d4fca3870f8>::()::__l2::<lambda_1b98701fb73d1f595d6ee3834a7d508d>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ce8f42aceb71021379fa0d4fca3870f8>::()::__l2::<lambda_1b98701fb73d1f595d6ee3834a7d508d>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_abdb5c8b9571ffd03a50feb33a1491fb>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_abdb5c8b9571ffd03a50feb33a1491fb>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_e6cd64d362e025bc4b987f4fea17eff0>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_e6cd64d362e025bc4b987f4fea17eff0>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_493a35617343a7628b16c394c25e7288>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_493a35617343a7628b16c394c25e7288>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_3ddd583dd03e1047eadfbe6f93d71944>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_3ddd583dd03e1047eadfbe6f93d71944>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_275e3f2d4348f8be7957dc2aabbbb380>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_275e3f2d4348f8be7957dc2aabbbb380>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_97cdea4f4f400a7278011fa8d2d1f685>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_97cdea4f4f400a7278011fa8d2d1f685>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ab348420d44697dda4767f0b025227af>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ab348420d44697dda4767f0b025227af>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_66c06b013927116d17edc2968cdfeed4>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_66c06b013927116d17edc2968cdfeed4>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ca1dfd5068ed9e10753039de3ab03376>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ca1dfd5068ed9e10753039de3ab03376>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_61bddccac50ff55ec07604306d90a0c2>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_61bddccac50ff55ec07604306d90a0c2>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_07252a608be21f7966425081439103c9>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_07252a608be21f7966425081439103c9>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_15_0::__l2::<lambda_8d4b605da35931865a1aedfa809a9afd>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_15_0::__l2::<lambda_8d4b605da35931865a1aedfa809a9afd>
{
};

```

### `VanillaBlockUpdater::addRailUpdater_1_14_0::__l2::<lambda_163060b3314c2df7c03cca92c2bd474b>`
```
struct __cppobj VanillaBlockUpdater::addRailUpdater_1_14_0::__l2::<lambda_163060b3314c2df7c03cca92c2bd474b>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_14_0::__l2::<lambda_1e64aa7001cd8847efd10a6613bcfedb>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_14_0::__l2::<lambda_1e64aa7001cd8847efd10a6613bcfedb>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_87f59ec0d50bc1afa00d60205f2c2faa>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_87f59ec0d50bc1afa00d60205f2c2faa>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_e3936787634fa70963edd9d5da537114>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_e3936787634fa70963edd9d5da537114>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_f8da966397545692365372cb43e99c38>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_f8da966397545692365372cb43e99c38>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_1da6e27dce515c28f9a1791fca93a549>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_1da6e27dce515c28f9a1791fca93a549>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_379cdc85c11cade417af6da513f512d9>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_379cdc85c11cade417af6da513f512d9>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_d677aa722cd10017bc1213d67c6b58c9>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_d677aa722cd10017bc1213d67c6b58c9>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_5369e1e5484ccb53d80c735fe2ecd2f8>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_5369e1e5484ccb53d80c735fe2ecd2f8>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_e3e4cae704d05b25869e39210dacdbe0>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_13_0::__l2::<lambda_e3e4cae704d05b25869e39210dacdbe0>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_70018795a1b8e0cdff82f5fbab88789e>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_70018795a1b8e0cdff82f5fbab88789e>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_d10a43d92abb1a7423f0f41af87ee41c>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_d10a43d92abb1a7423f0f41af87ee41c>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_2ddc20a1024515167145ea6823386c95>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_2ddc20a1024515167145ea6823386c95>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_cd73912804e89a3ed175a053d1a1721f>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_cd73912804e89a3ed175a053d1a1721f>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_4abe217b2ad19a2e3f268465f0a63dbd>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_4abe217b2ad19a2e3f268465f0a63dbd>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_583634c7e77f3c19a67cab6dfd1148ae>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_583634c7e77f3c19a67cab6dfd1148ae>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_5baa5e04a57fd98b06825dae95542648>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_5baa5e04a57fd98b06825dae95542648>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_e20167452f1a1f532be1a09ea1d8b766>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_e20167452f1a1f532be1a09ea1d8b766>
{
};

```

### `VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_d9d80317d423489be04adf928cf6a8f9>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_10_0::__l2::<lambda_d9d80317d423489be04adf928cf6a8f9>
{
};

```

### `VanillaBlockUpdater::addBaseUpdater::__l2::<lambda_5df4d4502f7e2f8726cf08a3c546649d>`
```
struct __cppobj VanillaBlockUpdater::addBaseUpdater::__l2::<lambda_5df4d4502f7e2f8726cf08a3c546649d>
{
};

```

### `VanillaStates::registerStates::__l2::<lambda_3b45a4442336f8dec982fd25c87b7b33>`
```
struct __cppobj VanillaStates::registerStates::__l2::<lambda_3b45a4442336f8dec982fd25c87b7b33>
{
};

```

### `VanillaDimensions::_loadDimensionFile::__l4::<lambda_054e473d6d5d3b3d1d051747f92c518d>`
```
struct __cppobj VanillaDimensions::_loadDimensionFile::__l4::<lambda_054e473d6d5d3b3d1d051747f92c518d>
{
  std::reverse_iterator<std::_Vector_iterator<std::_Vector_val<std::_Simple_types<PackInstance> > > > *rit;
};

```

### `VillagePiece`
```
struct __cppobj VillagePiece : PoolElementStructurePiece
{
};

```

### `VillagePiece::addPieces::__l53::<lambda_9f8862215d3156dc9e78592d5d9c958e>`
```
struct __cppobj VillagePiece::addPieces::__l53::<lambda_9f8862215d3156dc9e78592d5d9c958e>
{
};

```

### `VanillaGameModuleServer`
```
struct __cppobj VanillaGameModuleServer : GameModuleServer
{
  std::unique_ptr<VanillaServerGameplayEventListener> mGameplayListener;
  std::unique_ptr<ServerPlayerRewindListener> mPlayerRewindListener;
  std::shared_ptr<VanillaWorldSystems::Impl> mWorldSystems;
};

```

### `VanillaServerGameplayEventListener`
```
struct __cppobj VanillaServerGameplayEventListener : ActorEventListener, BlockEventListener, PlayerEventListener, LevelEventListener
{
};

```

### `VanillaServerGameplayEventListener_vtbl`
```
struct /*VFT*/ VanillaServerGameplayEventListener_vtbl
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

### `VanillaWorldSystems::Impl`
```
struct __cppobj VanillaWorldSystems::Impl
{
  std::atomic<unsigned int> _initCount;
};

```

### `VanillaGameModuleServer_vtbl`
```
struct /*VFT*/ VanillaGameModuleServer_vtbl
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
  void (__fastcall *registerListeners)(VanillaGameModuleServer *this, Level *);
  void (__fastcall *registerGameplayHandlers)(VanillaGameModuleServer *this, Level *);
};

```

### `VanillaGameModuleApp`
```
struct __cppobj VanillaGameModuleApp : IGameModuleApp
{
};

```

### `VanillaGameModuleApp_vtbl`
```
struct /*VFT*/ VanillaGameModuleApp_vtbl
{
  void (__fastcall *~IGameModuleShared)(IGameModuleShared *this);
  std::unique_ptr<GameModuleServer> *(__fastcall *createGameModuleServer)(IGameModuleShared *this, std::unique_ptr<GameModuleServer> *result);
  std::shared_ptr<IInPackagePacks> *(__fastcall *createInPackagePacks)(IGameModuleShared *this, std::shared_ptr<IInPackagePacks> *result);
  void (__fastcall *registerMolangQueries)(IGameModuleShared *this);
  std::unique_ptr<GameModuleClient> *(__fastcall *createGameModuleClient)(IGameModuleApp *this, std::unique_ptr<GameModuleClient> *result);
  std::unique_ptr<mce::framebuilder::FrameBuilder> *(__fastcall *createFrameBuilder)(IGameModuleApp *this, std::unique_ptr<mce::framebuilder::FrameBuilder> *result, WorkerPool *, const gsl::span<std::reference_wrapper<WorkerPool>,-1>, Scheduler *);
  std::unique_ptr<MinecraftInputHandler> *(__fastcall *createInputHandler)(IGameModuleApp *this, std::unique_ptr<MinecraftInputHandler> *result, IClientInstance *);
  std::unique_ptr<SceneFactory> *(__fastcall *createSceneFactory)(IGameModuleApp *this, std::unique_ptr<SceneFactory> *result, IMinecraftGame *, IClientInstance *, hbui::SceneProvider *);
  std::unique_ptr<ClientInputMappingFactory> *(__fastcall *createInputMappingFactory)(IGameModuleApp *this, std::unique_ptr<ClientInputMappingFactory> *result, IClientInstance *);
  void (__fastcall *setupStartMenuScreenCommands)(IGameModuleApp *this, CommandRegistry *);
  std::shared_ptr<IDynamicPackagePacks> *(__fastcall *createDynamicPackagePacks)(IGameModuleApp *this, std::shared_ptr<IDynamicPackagePacks> *result);
};

```

### `VanillaGameModuleClient`
```
struct __cppobj __declspec(align(8)) VanillaGameModuleClient : GameModuleClient, LevelEventListener
{
  std::unique_ptr<IAchievementsListener> mAchievementsListener;
  std::unique_ptr<VanillaClientGameplayEventListener> mGameplayListener;
  std::unique_ptr<VanillaTelemetryEventListener> mTelemetryListener;
  std::unique_ptr<VanillaBlockInteractionsUIListener> mBlockInteractionsUI;
  std::unique_ptr<ClientPlayerRewindListener> mPlayerRewindListener;
  std::shared_ptr<VanillaWorldSystems::Impl> mWorldSystems;
  bool mIsVR;
};

```

### `VanillaClientGameplayEventListener::State`
```
struct __cppobj VanillaClientGameplayEventListener::State
{
  int mSprintTriggerTime;
  int mJumpRidingTicks;
  int mJumpTriggerTime;
  int mScaffoldingDropHeldTime;
  bool mWasChangeHeight;
  bool mWasJumping;
  bool mWasSneaking;
  bool mWasRunning;
  bool mEmoteMoveLock;
  bool mBoatingInputSwitchRequested;
  bool mMinecartInputSwitchRequested;
  Vec3 mPreviousRidingPosition;
  float mPreviousRidingDistance;
  unsigned __int64 mStartRidingTick;
};

```

### `VanillaClientGameplayEventListener`
```
struct __cppobj VanillaClientGameplayEventListener : ActorEventListener, PlayerEventListener
{
  VanillaClientGameplayEventListener::State mState;
};

```

### `VanillaClientGameplayEventListener_vtbl`
```
struct /*VFT*/ VanillaClientGameplayEventListener_vtbl
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

### `VanillaTelemetryEventListener`
```
struct __cppobj VanillaTelemetryEventListener : BlockEventListener, ItemEventListener, PlayerEventListener, ActorEventListener
{
  Vec3 mLastPosition;
  float mDistanceSinceTravelledEvent;
};

```

### `VanillaTelemetryEventListener_vtbl`
```
struct /*VFT*/ VanillaTelemetryEventListener_vtbl
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

### `VanillaBlockInteractionsUIListener`
```
struct __cppobj VanillaBlockInteractionsUIListener : BlockEventListener, PlayerEventListener
{
  std::vector<std::string> mContainerScreenNames;
};

```

### `VanillaBlockInteractionsUIListener_vtbl`
```
struct /*VFT*/ VanillaBlockInteractionsUIListener_vtbl
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

### `VanillaGameModuleClient_vtbl`
```
struct /*VFT*/ VanillaGameModuleClient_vtbl
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
  void (__fastcall *registerListeners)(VanillaGameModuleClient *this, IClientInstance *, Level *);
  void (__fastcall *registerGameplayHandlers)(VanillaGameModuleClient *this, Level *);
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_dabac9a31fa92ec09abfda905bde5537>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_dabac9a31fa92ec09abfda905bde5537>
{
  VoiceScreenController *const __this;
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_9c34f739588215aae1ccfc375b1b02b0>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_9c34f739588215aae1ccfc375b1b02b0>
{
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_a964a558faec98d9eb45325a854ac2ab>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_a964a558faec98d9eb45325a854ac2ab>
{
  VoiceScreenController *const __this;
};

```

### `VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_2b875f553ba47bddb16670cd51b89b5d>`
```
struct __cppobj VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_2b875f553ba47bddb16670cd51b89b5d>
{
  OptionID optionID;
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_715d032b443a31c6be646e52829fcfb7>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_715d032b443a31c6be646e52829fcfb7>
{
};

```

### `VoiceScreenController::_registerEventHandlers::__l2::<lambda_248d58c91c2dde6263c20c5e7792973f>`
```
struct __cppobj VoiceScreenController::_registerEventHandlers::__l2::<lambda_248d58c91c2dde6263c20c5e7792973f>
{
  VoiceScreenController *const __this;
};

```

### `VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_6e23d1a647b3e0e8d602c4faaeeb9b7f>`
```
struct __cppobj VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_6e23d1a647b3e0e8d602c4faaeeb9b7f>
{
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_b0a8f055fa465ca84d929818e87a433f>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_b0a8f055fa465ca84d929818e87a433f>
{
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_418541dc9e442acdfb284526f9950077>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_418541dc9e442acdfb284526f9950077>
{
};

```

### `VoiceScreenController::setUpCallbacksForBooleanOption::__l5::<lambda_f0ab946328211a28e908bf30028b56e1>`
```
struct __cppobj VoiceScreenController::setUpCallbacksForBooleanOption::__l5::<lambda_f0ab946328211a28e908bf30028b56e1>
{
  std::function<bool __cdecl(void)> isEnabled;
};

```

### `VoiceScreenController::_registerBindings::__l2::<lambda_91b25bc9313f384cf71cc0f3a4148b24>`
```
struct __cppobj VoiceScreenController::_registerBindings::__l2::<lambda_91b25bc9313f384cf71cc0f3a4148b24>
{
  VoiceScreenController *const __this;
};

```

### `VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_33ddd6380a94d557ed622bf762fe5b5f>`
```
struct __cppobj VoiceScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_33ddd6380a94d557ed622bf762fe5b5f>
{
  OptionID optionID;
};

```

### `VoiceTransScreenController::_ngvoice_log::__l2::<lambda_2a2877e132994be94087d924a88725db>`
```
struct __cppobj VoiceTransScreenController::_ngvoice_log::__l2::<lambda_2a2877e132994be94087d924a88725db>
{
  std::string str;
};

```

### `VerifyLocalStage::onAwake::__l2::<lambda_381e658bbe07ad263ec9e818c40bfbeb>`
```
struct __cppobj VerifyLocalStage::onAwake::__l2::<lambda_381e658bbe07ad263ec9e818c40bfbeb>
{
  std::shared_ptr<BaseStage> this_ptr;
};

```

### `VanillaInPackagePacks`
```
struct __cppobj VanillaInPackagePacks : IInPackagePacks
{
};

```

### `VanillaInPackagePacks_vtbl`
```
struct /*VFT*/ VanillaInPackagePacks_vtbl
{
  void (__fastcall *~IInPackagePacks)(IInPackagePacks *this);
  std::vector<IInPackagePacks::MetaData> *(__fastcall *getPacks)(IInPackagePacks *this, std::vector<IInPackagePacks::MetaData> *result, PackType);
};

```

### `VanillaBiomes`
```
struct __cppobj VanillaBiomes
{
};

```

### `VanillaSurfaceBuilders::TheEndSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::TheEndSurfaceBuilder : ISurfaceBuilder
{
};

```

### `VanillaSurfaceBuilders::TheEndSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::TheEndSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaSceneFactory`
```
struct __cppobj VanillaSceneFactory : SceneFactory
{
};

```

### `VanillaSceneFactory_vtbl`
```
struct /*VFT*/ VanillaSceneFactory_vtbl
{
  void (__fastcall *~SceneFactory)(SceneFactory *this);
  Json::Value *(__fastcall *createGlobalVars)(SceneFactory *this, Json::Value *result, UIDefRepository *);
};

```

### `VanillaBlockInteractionsUIListener::onPlayerOpenContainer::__l16::<lambda_63339fc5698e84c08f98dbea4941825d>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onPlayerOpenContainer::__l16::<lambda_63339fc5698e84c08f98dbea4941825d>
{
  Player *player;
  const BlockPos *blockPos;
};

```

### `VanillaClientInputMappingFactory`
```
struct __cppobj __declspec(align(8)) VanillaClientInputMappingFactory : ClientInputMappingFactory
{
  bool mIsEdu;
};

```

### `VanillaClientInputMappingFactory_vtbl`
```
struct /*VFT*/ VanillaClientInputMappingFactory_vtbl
{
  void (__fastcall *~InputMappingFactory)(InputMappingFactory *this);
  const InputMapping *(__fastcall *getMapping)(InputMappingFactory *this, const std::string *);
  void (__fastcall *createInputMappingTemplates)(ClientInputMappingFactory *this, Options *);
  TouchInputMapping *(__fastcall *_createScreenTouchMapping)(ClientInputMappingFactory *this, TouchInputMapping *result);
  std::vector<DeviceButtonMapping> *(__fastcall *_createScreenDeviceButtonMapping)(ClientInputMappingFactory *this, std::vector<DeviceButtonMapping> *result);
  void (__fastcall *_updateKeyboardAndMouseControls)(ClientInputMappingFactory *this);
  void (__fastcall *_updateGameControllerControls)(ClientInputMappingFactory *this);
};

```

### `VanillaInputHandler`
```
struct __cppobj VanillaInputHandler : MinecraftInputHandler
{
};

```

### `VanillaMoveInputHandler`
```
struct __cppobj VanillaMoveInputHandler : ClientMoveInputHandler
{
};

```

### `VanillaMoveInputHandler_vtbl`
```
struct /*VFT*/ VanillaMoveInputHandler_vtbl
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

### `VanillaMoveInputHandler::createSnapshot::__l2::Snapshot`
```
struct __cppobj VanillaMoveInputHandler::createSnapshot::__l2::Snapshot : IReplayableActorInput
{
  VanillaMoveInputHandler mInput;
};

```

### `VanillaMoveInputHandler::createSnapshot::__l2::Snapshot_vtbl`
```
struct /*VFT*/ VanillaMoveInputHandler::createSnapshot::__l2::Snapshot_vtbl
{
  void (__fastcall *~IReplayableActorInput)(IReplayableActorInput *this);
  void (__fastcall *advanceFrame)(IReplayableActorInput *this, IActorMovementProxy *);
  AdvanceFrameResult (__fastcall *advanceLiveFrame)(IReplayableActorInput *this, Actor *);
};

```

### `VanillaRenderers`
```
struct __cppobj VanillaRenderers
{
};

```

### `VanillaRenderers::registerRenderers::__l2::<lambda_7ad3494cc9f276f37a4dd572a911aeb7>`
```
struct __cppobj VanillaRenderers::registerRenderers::__l2::<lambda_7ad3494cc9f276f37a4dd572a911aeb7>
{
  BlockActorRenderDispatcher *blockActorRenderDispatcher;
};

```

### `VanillaRenderers::registerRenderers::__l2::<lambda_c4d8ff1075e7acdf85dbda135c187eda>`
```
struct __cppobj VanillaRenderers::registerRenderers::__l2::<lambda_c4d8ff1075e7acdf85dbda135c187eda>
{
  ActorRenderDispatcher *actorRenderDispatcher;
};

```

### `VanillaRenderers::registerRenderers::__l2::<lambda_8d031b0df9aad2e7ffd90d4ae699407f>`
```
struct __cppobj VanillaRenderers::registerRenderers::__l2::<lambda_8d031b0df9aad2e7ffd90d4ae699407f>
{
  ActorRenderDispatcher *actorRenderDispatcher;
};

```

### `VanillaClientGameplayEventListener::_createStateSource::__l2::Snapshot`
```
struct __cppobj VanillaClientGameplayEventListener::_createStateSource::__l2::Snapshot : IReplayableActorState
{
  gsl::not_null<VanillaClientGameplayEventListener *> mGameplay;
  VanillaClientGameplayEventListener::State mState;
};

```

### `VanillaClientGameplayEventListener::_createStateSource::__l2::Snapshot_vtbl`
```
struct /*VFT*/ VanillaClientGameplayEventListener::_createStateSource::__l2::Snapshot_vtbl
{
  void (__fastcall *~IReplayableActorState)(IReplayableActorState *this);
  void (__fastcall *apply)(IReplayableActorState *this, IActorMovementProxy *);
};

```

### `VanillaClientGameplayEventListener::_createStateSource::__l2::<lambda_54f8dc9f08ea3772f765f7741bb0fecc>`
```
struct __cppobj VanillaClientGameplayEventListener::_createStateSource::__l2::<lambda_54f8dc9f08ea3772f765f7741bb0fecc>
{
  VanillaClientGameplayEventListener *const __this;
};

```

### `VanillaDynamicPackagePacks`
```
struct __cppobj VanillaDynamicPackagePacks : IDynamicPackagePacks
{
  Core::PathBuffer<std::string > mRoot;
};

```

### `VanillaDynamicPackagePacks_vtbl`
```
struct /*VFT*/ VanillaDynamicPackagePacks_vtbl
{
  void (__fastcall *~IInPackagePacks)(IInPackagePacks *this);
  std::vector<IInPackagePacks::MetaData> *(__fastcall *getPacks)(IInPackagePacks *this, std::vector<IInPackagePacks::MetaData> *result, PackType);
  void (__fastcall *setDynamicPackageRoot)(IDynamicPackagePacks *this, Core::PathBuffer<std::string >);
};

```

### `VanillaXboxLiveAchievementsEventListener`
```
struct __cppobj __declspec(align(8)) VanillaXboxLiveAchievementsEventListener : IAchievementsListener
{
  Vec3 mStartRidingPosition;
  float mPrevRidingDistance;
  int mTimeInWater;
  int mTimeInWaterNoPotion;
  bool mSleepWithFishesSent;
  Vec3 mLastStructureCheckPos;
  bool mTreasureHunterSent;
  bool mAhoySent;
  bool mAtlantisSent;
  float mStartedFloating;
  bool mCastawaySent;
  int mCastawayTimer;
  bool mAteKelp;
  int mLastBiome;
  bool mSailSeasSent;
  bool mSuperSonicSent;
  bool mGreatViewSent;
  bool mIronBellySent;
  bool mFreeDiverSent;
  bool mOnARailSent;
  bool mOnePickleTwoPickleSeaPickleFourSent;
  bool mBrillianceSent;
  bool mStickySituationSent;
  bool mTotalBeeLocationSent;
};

```

### `VanillaXboxLiveAchievementsEventListener_vtbl`
```
struct /*VFT*/ VanillaXboxLiveAchievementsEventListener_vtbl
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
  void (__fastcall *init)(IAchievementsListener *this, std::shared_ptr<Social::User>);
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::ViewedComponentWrapper<AgeableComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::ViewedComponentWrapper<AgeableComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::IsInViewedSet<AgeableComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::IsInViewedSet<AgeableComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgeableComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::ViewedComponentWrapper<AgentCommandComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::ViewedComponentWrapper<AgentCommandComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::IsInViewedSet<AgentCommandComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AgentCommandComponent>::IsInViewedSet<AgentCommandComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,AttackCooldownComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::ViewedComponentWrapper<ExplodeComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::ViewedComponentWrapper<ExplodeComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::IsInViewedSet<ExplodeComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,ExplodeComponent>::IsInViewedSet<ExplodeComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,LeashableComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::ViewedComponentWrapper<RailActivatorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::ViewedComponentWrapper<RailActivatorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::IsInViewedSet<RailActivatorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,RailActivatorComponent>::IsInViewedSet<RailActivatorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent> : EntityContext
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent> *mView;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::ViewedComponentWrapper<ActorComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::ViewedComponentWrapper<ActorComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::ViewedComponentWrapper<TransformationComponent>`
```
struct __cppobj __declspec(align(8)) ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::ViewedComponentWrapper<TransformationComponent>
{
  entt::basic_view<EntityId,entt::exclude_t<>,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent> *mView;
  const EntityId mEntity;
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::IsInViewedSet<ActorComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::IsInViewedSet<ActorComponent>
{
};

```

### `ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::IsInViewedSet<TransformationComponent>`
```
struct __cppobj ViewedEntityContextT<EntityContext,FlagComponent<ActorTickedFlag>,ActorComponent,TransformationComponent>::IsInViewedSet<TransformationComponent>
{
};

```

### `VanillaServerNetworkHandler`
```
struct __cppobj VanillaServerNetworkHandler : GameSpecificNetEventCallback
{
  ServerNetworkHandler *mBedrockHandler;
  ServerInstance *mServer;
};

```

### `VanillaServerNetworkHandler_vtbl`
```
struct /*VFT*/ VanillaServerNetworkHandler_vtbl
{
  void (__fastcall *~GameSpecificNetEventCallback)(GameSpecificNetEventCallback *this);
  void (__fastcall *handle)(GameSpecificNetEventCallback *this, const NetworkIdentifier *, const ResourcePackClientResponsePacket *);
};

```

### `VanillaFeatures`
```
struct __cppobj VanillaFeatures
{
};

```

### `VanillaVillageJigsawStructures`
```
struct __cppobj VanillaVillageJigsawStructures
{
};

```

### `VanillaBastionJigsawStructures`
```
struct __cppobj VanillaBastionJigsawStructures
{
};

```

### `VanillaGameModuleServer::registerListeners::__l2::<lambda_0d4eeef3f10641dbc368475ad8a6c013>`
```
struct __cppobj VanillaGameModuleServer::registerListeners::__l2::<lambda_0d4eeef3f10641dbc368475ad8a6c013>
{
  Level *level;
};

```

### `VanillaGameModuleServer::init::__l2::<lambda_533b29a2f62289e5af9416485914c9f7>`
```
struct __cppobj VanillaGameModuleServer::init::__l2::<lambda_533b29a2f62289e5af9416485914c9f7>
{
};

```

### `VanillaNetworkEventListener`
```
struct __cppobj VanillaNetworkEventListener : ActorEventListener, PlayerEventListener
{
};

```

### `VanillaNetworkEventListener_vtbl`
```
struct /*VFT*/ VanillaNetworkEventListener_vtbl
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

### `VanillaServerGameplayEventListener::onPlayerOpenContainer::__l15::<lambda_1317b9c2bca47b0e5ebfcec2bc0b27ef>`
```
struct __cppobj VanillaServerGameplayEventListener::onPlayerOpenContainer::__l15::<lambda_1317b9c2bca47b0e5ebfcec2bc0b27ef>
{
  ServerPlayer *serverPlayer;
  const BlockPos *blockPos;
};

```

### `VanillaServerGameplayEventListener::onPlayerOpenContainer::__l10::<lambda_8dec8135ee231af692876c4d42ab2e94>`
```
struct __cppobj VanillaServerGameplayEventListener::onPlayerOpenContainer::__l10::<lambda_8dec8135ee231af692876c4d42ab2e94>
{
  ServerPlayer *serverPlayer;
  ActorUniqueID *uniqueId;
};

```

### `VexRandomMoveGoal`
```
struct __cppobj VexRandomMoveGoal : Goal
{
  Mob *mMob;
};

```

### `VexRandomMoveGoal_vtbl`
```
struct /*VFT*/ VexRandomMoveGoal_vtbl
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

### `VanillaGoalDefinition::init::__l2::<lambda_97949567b6adcfe21b59e68940c97784>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_97949567b6adcfe21b59e68940c97784>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_a777e666efe3bbc984273602b80933c8>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_a777e666efe3bbc984273602b80933c8>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_0926a2660f997f923c6d86fea0af9868>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_0926a2660f997f923c6d86fea0af9868>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_015c1a623ed28dfc7578a94ef77d319e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_015c1a623ed28dfc7578a94ef77d319e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_d15d357080d9cae185be51326684ce05>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_d15d357080d9cae185be51326684ce05>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_57e7e67ca0198d13a70f597470833d75>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_57e7e67ca0198d13a70f597470833d75>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_081aa1b89c7824e0862587f3ea92e586>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_081aa1b89c7824e0862587f3ea92e586>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_8f6de3ca543eb8fc3382b8d4d8a362db>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_8f6de3ca543eb8fc3382b8d4d8a362db>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_87a82a94e1a292a1b0ac4c146d55bd86>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_87a82a94e1a292a1b0ac4c146d55bd86>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_54262916da0c43cefebd365031d6df71>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_54262916da0c43cefebd365031d6df71>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_6d8d577a1173de416b989a113b7b3978>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_6d8d577a1173de416b989a113b7b3978>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_2a8aaa79734b7fdbb1d300f28b7cc5ac>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_2a8aaa79734b7fdbb1d300f28b7cc5ac>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_ce0b6fc3749b3b5d2a3466dca043544e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_ce0b6fc3749b3b5d2a3466dca043544e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_766478aa4d420322457c1da407849528>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_766478aa4d420322457c1da407849528>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_856df2439931cc2f031ea7c1953a376f>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_856df2439931cc2f031ea7c1953a376f>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e24465e550f87ebcb0f185e722ef22b6>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e24465e550f87ebcb0f185e722ef22b6>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e2e02e05a2c4cb8273f251c595d06222>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e2e02e05a2c4cb8273f251c595d06222>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_0164ad3db98b12d07cf77e0e472ebc6a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_0164ad3db98b12d07cf77e0e472ebc6a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_21a651ce81b35fc2bd64472ee71687ff>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_21a651ce81b35fc2bd64472ee71687ff>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_1401752cfc51d3716dfa66e861c21057>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_1401752cfc51d3716dfa66e861c21057>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_355b020a45cd5bd077da5763e635718d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_355b020a45cd5bd077da5763e635718d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_1e5e60f283c9e33ed86d2d5e2a2f407b>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_1e5e60f283c9e33ed86d2d5e2a2f407b>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_ba07a965325a41084fc7a416a11f5432>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_ba07a965325a41084fc7a416a11f5432>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3b1649a703a2b183ae893707dd672d2e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3b1649a703a2b183ae893707dd672d2e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_f6a1d09133f8e23b1a356e17a51cc234>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_f6a1d09133f8e23b1a356e17a51cc234>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_697efda90af8b7058f64c210036fc5c2>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_697efda90af8b7058f64c210036fc5c2>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_d5ee3e6c0fe7bf89fe5c556e2426f2ed>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_d5ee3e6c0fe7bf89fe5c556e2426f2ed>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_0cdc81f353990f6f3c2a308a58874716>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_0cdc81f353990f6f3c2a308a58874716>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e848731f4ac2780475e32c17eb8cc1f4>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e848731f4ac2780475e32c17eb8cc1f4>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_06896e47efed3af55d2b0723652ab95e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_06896e47efed3af55d2b0723652ab95e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_8cebb5a0c3f446d4415142d07ee375dd>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_8cebb5a0c3f446d4415142d07ee375dd>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_1793494276ce02036857288a1c085c05>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_1793494276ce02036857288a1c085c05>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_48f81e8a4c4788a62936c96dff0986ee>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_48f81e8a4c4788a62936c96dff0986ee>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3029f19af82769e2e5b97c95d0b5929a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3029f19af82769e2e5b97c95d0b5929a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_503c30ef7a60e4bf83b13bf9854c347a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_503c30ef7a60e4bf83b13bf9854c347a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_69c47153f7434c576f809edb8a4695cb>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_69c47153f7434c576f809edb8a4695cb>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_c9879f9787eacf3bc744a62f79544abc>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_c9879f9787eacf3bc744a62f79544abc>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_1a840819efc6e9ab37d4423f0e0d0ee8>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_1a840819efc6e9ab37d4423f0e0d0ee8>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_719ef34156d3568a3c818da00ceda0e8>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_719ef34156d3568a3c818da00ceda0e8>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4305832f9f3862689e6b53c5e4f666be>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4305832f9f3862689e6b53c5e4f666be>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_5655ed387edd726e7b5c12c57158da49>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_5655ed387edd726e7b5c12c57158da49>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_38a33520ef44217f2aad15cbb0a3abc3>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_38a33520ef44217f2aad15cbb0a3abc3>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e39df80e320ccb503822ebae8911991d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e39df80e320ccb503822ebae8911991d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_a88f0e56e49ddc8bf01e18bf48cda68d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_a88f0e56e49ddc8bf01e18bf48cda68d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_19d6d0a4239a6633d3c2fdcced2e02b3>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_19d6d0a4239a6633d3c2fdcced2e02b3>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_aa050de021af27d1eeadfdd2e75954c5>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_aa050de021af27d1eeadfdd2e75954c5>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3653d4be92858778fbb7226bd2943d34>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3653d4be92858778fbb7226bd2943d34>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b53a7a18d46874605ea2f48c88b4be76>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b53a7a18d46874605ea2f48c88b4be76>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_129e909e71b4c9080d8f2a87ac5f31e5>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_129e909e71b4c9080d8f2a87ac5f31e5>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_616299f7d7453728abb1f8be4034a555>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_616299f7d7453728abb1f8be4034a555>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_86d06c570f0fa43c397a1d2984956518>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_86d06c570f0fa43c397a1d2984956518>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b5f9dbb538cfdf326eb7e17684ac9878>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b5f9dbb538cfdf326eb7e17684ac9878>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e2b3bc511cccec4ee5a2c8d0e8289cb1>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e2b3bc511cccec4ee5a2c8d0e8289cb1>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_489444aca7c80a8002e1156fdf1d41af>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_489444aca7c80a8002e1156fdf1d41af>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_cb1a3e75fb4ec619de0721b42a593806>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_cb1a3e75fb4ec619de0721b42a593806>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_758ea2ba96d0bcef995e3fa85e9eb5ee>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_758ea2ba96d0bcef995e3fa85e9eb5ee>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_d8bb416f764b073063f0adc4a130116d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_d8bb416f764b073063f0adc4a130116d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b84b8818e1386841b1dbeecbda0e81c1>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b84b8818e1386841b1dbeecbda0e81c1>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_fed845e1f058e8651b88f8cd6021e9ab>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_fed845e1f058e8651b88f8cd6021e9ab>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_c254b0454a4333a6cc33050b555d2695>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_c254b0454a4333a6cc33050b555d2695>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_fae40915f2ba9b91feb334b8faee4cd7>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_fae40915f2ba9b91feb334b8faee4cd7>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_5ca1762b640890467a2b1aa4ca1de37c>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_5ca1762b640890467a2b1aa4ca1de37c>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_7dededb157e44c7698027a4c1a2d2f6e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_7dededb157e44c7698027a4c1a2d2f6e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_653e0c79ce971e2ae91da412eeaac6c4>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_653e0c79ce971e2ae91da412eeaac6c4>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4861b5e75bafcea9697f73849b485a3d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4861b5e75bafcea9697f73849b485a3d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_36d26ec2e7d06203869aa885b3ddc05a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_36d26ec2e7d06203869aa885b3ddc05a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_262c97d3d562cc33cbbf92723051ea61>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_262c97d3d562cc33cbbf92723051ea61>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_69547bfc3ff065a5690762d6991bb841>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_69547bfc3ff065a5690762d6991bb841>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_0dffe06c2ad5a9e65bfcfe424040ffbf>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_0dffe06c2ad5a9e65bfcfe424040ffbf>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4b8fc4f3bdd84e049b28dc494a9c5643>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4b8fc4f3bdd84e049b28dc494a9c5643>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_dbe065545b91f868dd4e8eca265f516d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_dbe065545b91f868dd4e8eca265f516d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_f08a112844a0b5915b2cecc3f59d51da>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_f08a112844a0b5915b2cecc3f59d51da>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4448af0b640749b73cb1c745cab739bc>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4448af0b640749b73cb1c745cab739bc>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_bb97716b9034170019757344b8837573>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_bb97716b9034170019757344b8837573>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4eb4b23092870360b133686dabcc243c>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4eb4b23092870360b133686dabcc243c>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_9f1c250c3dc665530f6ed2c1158c4315>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_9f1c250c3dc665530f6ed2c1158c4315>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e3bc5c918a5d8c8e1b674354fa7add96>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e3bc5c918a5d8c8e1b674354fa7add96>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b3677484d33712b06d64084319b65479>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b3677484d33712b06d64084319b65479>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_2f8c035a4dd1be5ec0c5032970241965>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_2f8c035a4dd1be5ec0c5032970241965>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_1c89ed69c95907fca187311281936215>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_1c89ed69c95907fca187311281936215>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_7b88fa93fad703d2f531419f11cd0660>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_7b88fa93fad703d2f531419f11cd0660>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_575ee1a384fc700b9a9697737ae768ba>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_575ee1a384fc700b9a9697737ae768ba>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_5b02c40c7d40ec4f22873c571fd8581a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_5b02c40c7d40ec4f22873c571fd8581a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3c124c240aacfb3823b6ba169c74164d>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3c124c240aacfb3823b6ba169c74164d>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b15f74a4cceca467b83c1e2704fe87db>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b15f74a4cceca467b83c1e2704fe87db>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_cd26fe728f9050f5ce1aff05e744b320>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_cd26fe728f9050f5ce1aff05e744b320>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_eddf79d7579fd9fd37944de91ca35829>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_eddf79d7579fd9fd37944de91ca35829>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_930f04c859fa3f4f1ec878a05f75493f>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_930f04c859fa3f4f1ec878a05f75493f>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_f463a0981e07dd7d36c3ce2f29d43b60>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_f463a0981e07dd7d36c3ce2f29d43b60>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_6cac8cf1e5b50f7baa179e74672125dd>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_6cac8cf1e5b50f7baa179e74672125dd>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b3795fdbfabaee0e13c94b808ee66723>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b3795fdbfabaee0e13c94b808ee66723>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_2b1308a661622120e995f2d57d3450a5>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_2b1308a661622120e995f2d57d3450a5>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_74536c5ec561005be9398c7ca0dbda9e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_74536c5ec561005be9398c7ca0dbda9e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_0160d626b5f346ed847165a8fe190d64>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_0160d626b5f346ed847165a8fe190d64>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_27f73aab9833d50f095c85775246606e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_27f73aab9833d50f095c85775246606e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_2484468e1faf34baa19d5067b05d3368>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_2484468e1faf34baa19d5067b05d3368>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_a34b19d8ce8bb37fb204cc80b35adc58>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_a34b19d8ce8bb37fb204cc80b35adc58>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_515ffea52886a1045cccbd80ed72d4cd>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_515ffea52886a1045cccbd80ed72d4cd>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_f59389d2f267f23bc71db169fc738068>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_f59389d2f267f23bc71db169fc738068>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4dec8e38f3a878b27ae85cc9dd075d9f>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4dec8e38f3a878b27ae85cc9dd075d9f>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_2360b305178446782be425346277906a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_2360b305178446782be425346277906a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_a31ba5ecae6b875cc4e5e7e7f1ba33a3>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_a31ba5ecae6b875cc4e5e7e7f1ba33a3>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_69f887b992523d318796768cc2235d80>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_69f887b992523d318796768cc2235d80>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_e872d24e07460899ceeeae415820c471>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_e872d24e07460899ceeeae415820c471>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_b4be5069487270a60d910fc9b9bff25c>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_b4be5069487270a60d910fc9b9bff25c>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_ab71f4699850f37502dcaaed582dc23a>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_ab71f4699850f37502dcaaed582dc23a>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_8a4b7bf4c13597a629bd750600f8891e>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_8a4b7bf4c13597a629bd750600f8891e>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_138ffd040dcb0060b1769235a67df797>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_138ffd040dcb0060b1769235a67df797>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3b84690b956d790135b74dd73e5353c7>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3b84690b956d790135b74dd73e5353c7>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4bb85008eef0d4a661b9e4ebd348c7f0>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4bb85008eef0d4a661b9e4ebd348c7f0>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_7f554aea104ebcdf4225aed7b9e627b6>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_7f554aea104ebcdf4225aed7b9e627b6>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_4b08152d7f01ad6f7d83a9ab5d471e37>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_4b08152d7f01ad6f7d83a9ab5d471e37>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_dfd1276eba3fa68be805b51f724cd66f>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_dfd1276eba3fa68be805b51f724cd66f>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_91b93a842f47eb6aaaf86c84deb043c5>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_91b93a842f47eb6aaaf86c84deb043c5>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_3e9ddcbf713787b846e286b0df7fa6b6>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_3e9ddcbf713787b846e286b0df7fa6b6>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_27facb8330d7dbc2ab7da7060769c934>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_27facb8330d7dbc2ab7da7060769c934>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_5189e062782e4a36012cc3f9f28a3a01>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_5189e062782e4a36012cc3f9f28a3a01>
{
};

```

### `VanillaGoalDefinition::init::__l2::<lambda_6786732d81f1728c0d07630d942d2ef8>`
```
struct __cppobj VanillaGoalDefinition::init::__l2::<lambda_6786732d81f1728c0d07630d942d2ef8>
{
};

```

### `VanillaSurfaceBuilders::MesaSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::MesaSurfaceBuilder : ISurfaceBuilder
{
  std::array<enum BlockColor,64> mColorBands;
  std::unique_ptr<PerlinSimplexNoise> mPillarNoise;
  std::unique_ptr<PerlinSimplexNoise> mPillarRoofNoise;
  std::unique_ptr<PerlinSimplexNoise> mBandsNoise;
};

```

### `VanillaSurfaceBuilders::MesaSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::MesaSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaSurfaceBuilders::NetherSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::NetherSurfaceBuilder : ISurfaceBuilder
{
  std::unique_ptr<PerlinNoise> mMaterialNoise;
};

```

### `VanillaSurfaceBuilders::NetherSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::NetherSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaSurfaceBuilders::OceanFrozenSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::OceanFrozenSurfaceBuilder : ISurfaceBuilder
{
  std::unique_ptr<PerlinSimplexNoise> mIcebergNoise;
  std::unique_ptr<PerlinSimplexNoise> mIcebergRoofNoise;
};

```

### `VanillaSurfaceBuilders::OceanFrozenSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::OceanFrozenSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `VanillaSurfaceBuilders::SwampSurfaceBuilder`
```
struct __cppobj VanillaSurfaceBuilders::SwampSurfaceBuilder : ISurfaceBuilder
{
  std::unique_ptr<PerlinSimplexNoise> mWaterlilyNoise;
};

```

### `VanillaSurfaceBuilders::SwampSurfaceBuilder_vtbl`
```
struct /*VFT*/ VanillaSurfaceBuilders::SwampSurfaceBuilder_vtbl
{
  void (__fastcall *~ISurfaceBuilder)(ISurfaceBuilder *this);
  void (__fastcall *init)(ISurfaceBuilder *this, EntityContext *, unsigned int);
  void (__fastcall *buildSurfaceAt)(ISurfaceBuilder *this, Biome *, Random *, BlockVolume *, const BlockPos *, float, __int16, std::unique_ptr<PerlinSimplexNoise> *);
};

```

### `V113ToV114::_upgradeDescription::__l2::<lambda_b6dd78c0c7a983262f21bba219ee8477>`
```
struct __cppobj V113ToV114::_upgradeDescription::__l2::<lambda_b6dd78c0c7a983262f21bba219ee8477>
{
};

```

### `V113ToV114::_upgradeDescription::__l2::<lambda_b6dd78c0c7a983262f21bba219ee8477>::()::__l2::<lambda_f29287cf0c7ae35d8d4ad67a8714ec30>`
```
struct __cppobj V113ToV114::_upgradeDescription::__l2::<lambda_b6dd78c0c7a983262f21bba219ee8477>::()::__l2::<lambda_f29287cf0c7ae35d8d4ad67a8714ec30>
{
};

```

### `V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>`
```
struct __cppobj V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>
{
  const bool isNether;
};

```

### `V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>::()::__l2::<lambda_818c987ce6acdc1506a780969ed0174e>`
```
struct __cppobj V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>::()::__l2::<lambda_818c987ce6acdc1506a780969ed0174e>
{
  const bool isNether;
};

```

### `V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>::()::__l2::<lambda_818c987ce6acdc1506a780969ed0174e>::()::__l6::<lambda_95347d195861f728669bb7d25168dbee>`
```
struct __cppobj V113ToV114::_upgradeSurfaceAdjustments::__l2::<lambda_644e31b139ddc0e8f669fed9a3542fcc>::()::__l2::<lambda_818c987ce6acdc1506a780969ed0174e>::()::__l6::<lambda_95347d195861f728669bb7d25168dbee>
{
};

```

### `V113ToV114::_upgradeNoiseRange::__l2::<lambda_94058b53879072868e610799ce93baa0>`
```
struct __cppobj __declspec(align(8)) V113ToV114::_upgradeNoiseRange::__l2::<lambda_94058b53879072868e610799ce93baa0>
{
  Json::Value *adjustment;
  const bool isNether;
};

```

### `V113ToV114::_upgradeWorldGenerationRules::__l2::<lambda_0587df78a23013fb19457a02ae34f43c>`
```
struct __cppobj __declspec(align(8)) V113ToV114::_upgradeWorldGenerationRules::__l2::<lambda_0587df78a23013fb19457a02ae34f43c>
{
  Json::Value *componentsRoot;
  const char *worldGenerationRules;
  const bool isNether;
};

```

### `V113ToV114::_upgradeOverworldSurface::__l2::<lambda_b559e413b9828f358f05d0a9fc76ea8a>`
```
struct __cppobj V113ToV114::_upgradeOverworldSurface::__l2::<lambda_b559e413b9828f358f05d0a9fc76ea8a>
{
  Json::Value *componentsRoot;
};

```

### `VanillaBiomes::initDefaultWorldGenComponents::__l2::<lambda_1e36a981c0af2bc873d9a007bf1e1d75>`
```
struct __cppobj VanillaBiomes::initDefaultWorldGenComponents::__l2::<lambda_1e36a981c0af2bc873d9a007bf1e1d75>
{
  AutomaticID<Dimension,int> *id;
  IWorldRegistriesProvider *registries;
  TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > *tagRegistry;
  WellKnownBiomeTags *wellKnownBiomeTags;
};

```

### `VanillaBiomes::initDefaultWorldGenComponents::__l2::<lambda_5b3ac02b59fa04f2fd58dd6c27660acf>`
```
struct __cppobj VanillaBiomes::initDefaultWorldGenComponents::__l2::<lambda_5b3ac02b59fa04f2fd58dd6c27660acf>
{
  IWorldRegistriesProvider *registries;
  TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > *tagRegistry;
  WellKnownBiomeTags *wellKnownBiomeTags;
};

```

### `V110ToV116::_convertSinglePropertyComponentToKeyValuePair::__l2::<lambda_b5545e3ca20fb3f21d04b525090a9281>`
```
struct __cppobj V110ToV116::_convertSinglePropertyComponentToKeyValuePair::__l2::<lambda_b5545e3ca20fb3f21d04b525090a9281>
{
  const char *propertyName;
};

```

### `V110ToV116::_convertSinglePropertyComponentToKeyValuePair::__l2::<lambda_b5545e3ca20fb3f21d04b525090a9281>::()::__l2::<lambda_546019875acd41689ff25be131b871bb>`
```
struct __cppobj V110ToV116::_convertSinglePropertyComponentToKeyValuePair::__l2::<lambda_b5545e3ca20fb3f21d04b525090a9281>::()::__l2::<lambda_546019875acd41689ff25be131b871bb>
{
  Json::Value *component;
};

```

### `VillageFeature`
```
struct __cppobj VillageFeature : StructureFeature
{
  std::vector<int> allowedBiomes;
  const int mTownSpacing;
  const int mMinTownSeparation;
};

```

### `VillageFeature_vtbl`
```
struct /*VFT*/ VillageFeature_vtbl
{
  void (__fastcall *~StructureFeature)(StructureFeature *this);
  bool (__fastcall *postProcess)(StructureFeature *this, BlockSource *, Random *, int, int);
  bool (__fastcall *getNearestGeneratedFeature)(StructureFeature *this, Dimension *, BiomeSource *, const BlockPos *, BlockPos *);
  bool (__fastcall *isFeatureChunk)(StructureFeature *this, const BiomeSource *, Random *, const ChunkPos *, unsigned int);
  std::unique_ptr<StructureStart> *(__fastcall *createStructureStart)(StructureFeature *this, std::unique_ptr<StructureStart> *result, Dimension *, BiomeSource *, Random *, const ChunkPos *);
  StructureStart *(__fastcall *getStructureAt)(StructureFeature *this, int, int, int);
  std::vector<BlockPos> *(__fastcall *getGuesstimatedFeaturePositions)(StructureFeature *this, std::vector<BlockPos> *result);
};

```

### `VillageStart`
```
struct __cppobj __declspec(align(8)) VillageStart : StructureStart
{
  bool mValid;
};

```

### `VillageStart_vtbl`
```
struct /*VFT*/ VillageStart_vtbl
{
  void (__fastcall *~StructureStart)(StructureStart *this);
  bool (__fastcall *postProcess)(StructureStart *this, BlockSource *, Random *, const BoundingBox *);
  bool (__fastcall *isValid)(StructureStart *this);
  StructureFeatureType (__fastcall *getType)(StructureStart *this);
};

```

### `VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_4ab15a409add9b6e469c74dfbd1f1acd>`
```
struct __cppobj VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_4ab15a409add9b6e469c74dfbd1f1acd>
{
};

```

### `VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_73cff2eac2fc020be9b0aa43af366aff>`
```
struct __cppobj VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_73cff2eac2fc020be9b0aa43af366aff>
{
};

```

### `VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_944b908856deb5ceb05f6ed73ed6092b>`
```
struct __cppobj VanillaDimensionFactory::registerDimensionTypes::__l2::<lambda_944b908856deb5ceb05f6ed73ed6092b>
{
};

```

### `VinesFeature`
```
struct __cppobj VinesFeature : Feature
{
};

```

### `VinesFeature_vtbl`
```
struct /*VFT*/ VinesFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `VanillaTreeFeature`
```
struct __cppobj VanillaTreeFeature : ITreeFeature
{
};

```

### `VanillaTreeFeature_vtbl`
```
struct /*VFT*/ VanillaTreeFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `VanillaTreeFeature::_buildSchema::__l2::<lambda_71a9c5ed1b65479ead02b39e164080cd>`
```
struct __cppobj VanillaTreeFeature::_buildSchema::__l2::<lambda_71a9c5ed1b65479ead02b39e164080cd>
{
};

```

### `VanillaTreeFeature::_buildSchema::__l2::<lambda_4e10bcf797b892747345a27e097f3a4a>`
```
struct __cppobj VanillaTreeFeature::_buildSchema::__l2::<lambda_4e10bcf797b892747345a27e097f3a4a>
{
};

```

### `VanillaBastionJigsawStructureBlockRules`
```
struct __cppobj VanillaBastionJigsawStructureBlockRules
{
};

```

### `VanillaBastionJigsawStructureElements`
```
struct __cppobj VanillaBastionJigsawStructureElements
{
};

```

### `VanillaVillageJigsawStructureActorRules`
```
struct __cppobj VanillaVillageJigsawStructureActorRules
{
};

```

### `VanillaVillageJigsawStructureBlockRules`
```
struct __cppobj VanillaVillageJigsawStructureBlockRules
{
};

```

### `VanillaVillageJigsawStructureBlockTagRules`
```
struct __cppobj VanillaVillageJigsawStructureBlockTagRules
{
};

```

### `VanillaVillageJigsawStructureElements`
```
struct __cppobj VanillaVillageJigsawStructureElements
{
};

```

### `VariadicSQLParser::IndexAndType`
```
struct VariadicSQLParser::IndexAndType
{
  unsigned int strIndex;
  unsigned int typeMappingIndex;
};

```

### `VkApplicationInfo`
```
const struct VkApplicationInfo
{
  VkStructureType sType;
  const void *pNext;
  const char *pApplicationName;
  unsigned int applicationVersion;
  const char *pEngineName;
  unsigned int engineVersion;
  unsigned int apiVersion;
};

```

### `VkAllocationCallbacks`
```
struct VkAllocationCallbacks
{
  void *pUserData;
  void *(__fastcall *pfnAllocation)(void *, unsigned __int64, unsigned __int64, VkSystemAllocationScope);
  void *(__fastcall *pfnReallocation)(void *, void *, unsigned __int64, unsigned __int64, VkSystemAllocationScope);
  void (__fastcall *pfnFree)(void *, void *);
  void (__fastcall *pfnInternalAllocation)(void *, unsigned __int64, VkInternalAllocationType, VkSystemAllocationScope);
  void (__fastcall *pfnInternalFree)(void *, unsigned __int64, VkInternalAllocationType, VkSystemAllocationScope);
};

```

### `VkImageResolve`
```
struct VkImageResolve
{
  VkImageSubresourceLayers srcSubresource;
  VkOffset3D srcOffset;
  VkImageSubresourceLayers dstSubresource;
  VkOffset3D dstOffset;
  VkExtent3D extent;
};

```

### `VkDebugUtilsObjectNameInfoEXT`
```
struct VkDebugUtilsObjectNameInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  VkObjectType objectType;
  unsigned __int64 objectHandle;
  const char *pObjectName;
};

```

### `VkDeviceQueueCreateInfo`
```
const struct VkDeviceQueueCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int queueFamilyIndex;
  unsigned int queueCount;
  const float *pQueuePriorities;
};

```

### `VkDebugUtilsLabelEXT`
```
struct VkDebugUtilsLabelEXT
{
  VkStructureType sType;
  const void *pNext;
  const char *pLabelName;
  float color[4];
};

```

### `VkFormatProperties`
```
struct VkFormatProperties
{
  unsigned int linearTilingFeatures;
  unsigned int optimalTilingFeatures;
  unsigned int bufferFeatures;
};

```

### `VkAttachmentDescription`
```
const struct VkAttachmentDescription
{
  unsigned int flags;
  VkFormat format;
  VkSampleCountFlagBits samples;
  VkAttachmentLoadOp loadOp;
  VkAttachmentStoreOp storeOp;
  VkAttachmentLoadOp stencilLoadOp;
  VkAttachmentStoreOp stencilStoreOp;
  VkImageLayout initialLayout;
  VkImageLayout finalLayout;
};

```

### `VkAttachmentReference`
```
const struct VkAttachmentReference
{
  unsigned int attachment;
  VkImageLayout layout;
};

```

### `VkSubpassDescription`
```
const struct VkSubpassDescription
{
  unsigned int flags;
  VkPipelineBindPoint pipelineBindPoint;
  unsigned int inputAttachmentCount;
  const VkAttachmentReference *pInputAttachments;
  unsigned int colorAttachmentCount;
  const VkAttachmentReference *pColorAttachments;
  const VkAttachmentReference *pResolveAttachments;
  const VkAttachmentReference *pDepthStencilAttachment;
  unsigned int preserveAttachmentCount;
  const unsigned int *pPreserveAttachments;
};

```

### `VkSubpassDependency`
```
const struct VkSubpassDependency
{
  unsigned int srcSubpass;
  unsigned int dstSubpass;
  unsigned int srcStageMask;
  unsigned int dstStageMask;
  unsigned int srcAccessMask;
  unsigned int dstAccessMask;
  unsigned int dependencyFlags;
};

```

### `VkDescriptorImageInfo`
```
const struct __declspec(align(8)) VkDescriptorImageInfo
{
  struct VkSampler_T *sampler;
  VkImageView_T *imageView;
  VkImageLayout imageLayout;
};

```

### `VkDescriptorBufferInfo`
```
const struct VkDescriptorBufferInfo
{
  VkBuffer_T *buffer;
  unsigned __int64 offset;
  unsigned __int64 range;
};

```

### `VkCopyDescriptorSet`
```
struct __declspec(align(8)) VkCopyDescriptorSet
{
  VkStructureType sType;
  const void *pNext;
  VkDescriptorSet_T *srcSet;
  unsigned int srcBinding;
  unsigned int srcArrayElement;
  VkDescriptorSet_T *dstSet;
  unsigned int dstBinding;
  unsigned int dstArrayElement;
  unsigned int descriptorCount;
};

```

### `VkQueueFamilyProperties`
```
struct VkQueueFamilyProperties
{
  unsigned int queueFlags;
  unsigned int queueCount;
  unsigned int timestampValidBits;
  VkExtent3D minImageTransferGranularity;
};

```

### `VkPushConstantRange`
```
const struct VkPushConstantRange
{
  unsigned int stageFlags;
  unsigned int offset;
  unsigned int size;
};

```

### `VkSpecializationMapEntry`
```
const struct VkSpecializationMapEntry
{
  unsigned int constantID;
  unsigned int offset;
  unsigned __int64 size;
};

```

### `VkSpecializationInfo`
```
const struct VkSpecializationInfo
{
  unsigned int mapEntryCount;
  const VkSpecializationMapEntry *pMapEntries;
  unsigned __int64 dataSize;
  const void *pData;
};

```

### `VkVertexInputBindingDescription`
```
const struct VkVertexInputBindingDescription
{
  unsigned int binding;
  unsigned int stride;
  VkVertexInputRate inputRate;
};

```

### `VkVertexInputAttributeDescription`
```
const struct VkVertexInputAttributeDescription
{
  unsigned int location;
  unsigned int binding;
  VkFormat format;
  unsigned int offset;
};

```

### `VkPipelineInputAssemblyStateCreateInfo`
```
const struct __declspec(align(8)) VkPipelineInputAssemblyStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  VkPrimitiveTopology topology;
  unsigned int primitiveRestartEnable;
};

```

### `VkPipelineTessellationStateCreateInfo`
```
const struct VkPipelineTessellationStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int patchControlPoints;
};

```

### `VkPipelineViewportStateCreateInfo`
```
const struct VkPipelineViewportStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int viewportCount;
  const VkViewport *pViewports;
  unsigned int scissorCount;
  const VkRect2D *pScissors;
};

```

### `VkPipelineRasterizationStateCreateInfo`
```
const struct __declspec(align(8)) VkPipelineRasterizationStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int depthClampEnable;
  unsigned int rasterizerDiscardEnable;
  VkPolygonMode polygonMode;
  unsigned int cullMode;
  VkFrontFace frontFace;
  unsigned int depthBiasEnable;
  float depthBiasConstantFactor;
  float depthBiasClamp;
  float depthBiasSlopeFactor;
  float lineWidth;
};

```

### `VkPipelineMultisampleStateCreateInfo`
```
const struct VkPipelineMultisampleStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  VkSampleCountFlagBits rasterizationSamples;
  unsigned int sampleShadingEnable;
  float minSampleShading;
  const unsigned int *pSampleMask;
  unsigned int alphaToCoverageEnable;
  unsigned int alphaToOneEnable;
};

```

### `VkStencilOpState`
```
struct VkStencilOpState
{
  VkStencilOp failOp;
  VkStencilOp passOp;
  VkStencilOp depthFailOp;
  VkCompareOp compareOp;
  unsigned int compareMask;
  unsigned int writeMask;
  unsigned int reference;
};

```

### `VkPipelineDepthStencilStateCreateInfo`
```
const struct VkPipelineDepthStencilStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int depthTestEnable;
  unsigned int depthWriteEnable;
  VkCompareOp depthCompareOp;
  unsigned int depthBoundsTestEnable;
  unsigned int stencilTestEnable;
  VkStencilOpState front;
  VkStencilOpState back;
  float minDepthBounds;
  float maxDepthBounds;
};

```

### `VkPipelineColorBlendAttachmentState`
```
const struct VkPipelineColorBlendAttachmentState
{
  unsigned int blendEnable;
  VkBlendFactor srcColorBlendFactor;
  VkBlendFactor dstColorBlendFactor;
  VkBlendOp colorBlendOp;
  VkBlendFactor srcAlphaBlendFactor;
  VkBlendFactor dstAlphaBlendFactor;
  VkBlendOp alphaBlendOp;
  unsigned int colorWriteMask;
};

```

### `VkPipelineDynamicStateCreateInfo`
```
const struct VkPipelineDynamicStateCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int dynamicStateCount;
  const VkDynamicState *pDynamicStates;
};

```

### `VkDescriptorPoolSize`
```
const struct VkDescriptorPoolSize
{
  VkDescriptorType type;
  unsigned int descriptorCount;
};

```

### `VkDescriptorPoolCreateInfo`
```
struct VkDescriptorPoolCreateInfo
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int maxSets;
  unsigned int poolSizeCount;
  const VkDescriptorPoolSize *pPoolSizes;
};

```

### `VkMemoryBarrier`
```
struct VkMemoryBarrier
{
  VkStructureType sType;
  const void *pNext;
  unsigned int srcAccessMask;
  unsigned int dstAccessMask;
};

```

### `VkBufferMemoryBarrier`
```
struct VkBufferMemoryBarrier
{
  VkStructureType sType;
  const void *pNext;
  unsigned int srcAccessMask;
  unsigned int dstAccessMask;
  unsigned int srcQueueFamilyIndex;
  unsigned int dstQueueFamilyIndex;
  VkBuffer_T *buffer;
  unsigned __int64 offset;
  unsigned __int64 size;
};

```

### `VkDisplayPropertiesKHR`
```
struct __declspec(align(8)) VkDisplayPropertiesKHR
{
  struct VkDisplayKHR_T *display;
  const char *displayName;
  VkExtent2D physicalDimensions;
  VkExtent2D physicalResolution;
  unsigned int supportedTransforms;
  unsigned int planeReorderPossible;
  unsigned int persistentContent;
};

```

### `VkCommandBufferInheritanceInfo`
```
const struct __declspec(align(8)) VkCommandBufferInheritanceInfo
{
  VkStructureType sType;
  const void *pNext;
  VkRenderPass_T *renderPass;
  unsigned int subpass;
  VkFramebuffer_T *framebuffer;
  unsigned int occlusionQueryEnable;
  unsigned int queryFlags;
  unsigned int pipelineStatistics;
};

```

### `VkDebugUtilsMessengerCallbackDataEXT`
```
struct VkDebugUtilsMessengerCallbackDataEXT
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  const char *pMessageIdName;
  int messageIdNumber;
  const char *pMessage;
  unsigned int queueLabelCount;
  VkDebugUtilsLabelEXT *pQueueLabels;
  unsigned int cmdBufLabelCount;
  VkDebugUtilsLabelEXT *pCmdBufLabels;
  unsigned int objectCount;
  VkDebugUtilsObjectNameInfoEXT *pObjects;
};

```

### `VkDebugUtilsObjectTagInfoEXT`
```
struct VkDebugUtilsObjectTagInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  VkObjectType objectType;
  unsigned __int64 objectHandle;
  unsigned __int64 tagName;
  unsigned __int64 tagSize;
  const void *pTag;
};

```

### `VkDebugMarkerObjectTagInfoEXT`
```
struct VkDebugMarkerObjectTagInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  VkDebugReportObjectTypeEXT objectType;
  unsigned __int64 object;
  unsigned __int64 tagName;
  unsigned __int64 tagSize;
  const void *pTag;
};

```

### `VkDebugMarkerObjectNameInfoEXT`
```
struct VkDebugMarkerObjectNameInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  VkDebugReportObjectTypeEXT objectType;
  unsigned __int64 object;
  const char *pObjectName;
};

```

### `VkDebugMarkerMarkerInfoEXT`
```
struct VkDebugMarkerMarkerInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  const char *pMarkerName;
  float color[4];
};

```

### `VkPhysicalDeviceMemoryProperties2`
```
struct VkPhysicalDeviceMemoryProperties2
{
  VkStructureType sType;
  void *pNext;
  VkPhysicalDeviceMemoryProperties memoryProperties;
};

```

### `VkDebugUtilsMessengerCreateInfoEXT`
```
struct VkDebugUtilsMessengerCreateInfoEXT
{
  VkStructureType sType;
  const void *pNext;
  unsigned int flags;
  unsigned int messageSeverity;
  unsigned int messageType;
  unsigned int (__fastcall *pfnUserCallback)(VkDebugUtilsMessageSeverityFlagBitsEXT, unsigned int, const VkDebugUtilsMessengerCallbackDataEXT *, void *);
  void *pUserData;
};

```

### `VisualTree::markToRemoveDeadDependencies::__l2::<lambda_03fa1c26f3f0531927d494e5c2eb4834>`
```
struct __cppobj VisualTree::markToRemoveDeadDependencies::__l2::<lambda_03fa1c26f3f0531927d494e5c2eb4834>
{
  std::shared_ptr<UIControl> *control;
};

```

### `VisualTree::updateControlBinds::__l2::<lambda_f63b9a97483adfd833d2ffc4eeaec7c1>`
```
struct __cppobj VisualTree::updateControlBinds::__l2::<lambda_f63b9a97483adfd833d2ffc4eeaec7c1>
{
  std::shared_ptr<UIControl> *control;
};

```

### `VisualTree::updateControlCollection::__l2::<lambda_f79db187ec04e7fc255ffa7a4e55a43b>`
```
struct __cppobj VisualTree::updateControlCollection::__l2::<lambda_f79db187ec04e7fc255ffa7a4e55a43b>
{
  std::shared_ptr<UIControl> *control;
};

```

### `VisualTree::removeFromControlCollection::__l2::<lambda_ff259bb8a9592ff121705d37d4649d95>`
```
struct __cppobj VisualTree::removeFromControlCollection::__l2::<lambda_ff259bb8a9592ff121705d37d4649d95>
{
  std::shared_ptr<UIControl> *control;
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Facing::Name>::get::__l2::<lambda_fdf3b77cda7358cf8dfa85507ddd2834>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Facing::Name>::get::__l2::<lambda_fdf3b77cda7358cf8dfa85507ddd2834>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Direction::Type>::get::__l2::<lambda_999d4e043ca9c2db24e924a08002a4f2>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Direction::Type>::get::__l2::<lambda_999d4e043ca9c2db24e924a08002a4f2>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Facing::Name>::get::__l2::<lambda_65b66f12cd623f03a4eff2d7d71c9f82>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Facing::Name>::get::__l2::<lambda_65b66f12cd623f03a4eff2d7d71c9f82>
{
  Facing::Name value;
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Direction::Type>::get::__l2::<lambda_c47ae2d37d4666830b2493b27302aa4b>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum Direction::Type>::get::__l2::<lambda_c47ae2d37d4666830b2493b27302aa4b>
{
  Direction::Type value;
};

```

### `Village::_pruneRecentlyWorkedDwellers::__l2::<lambda_746584a7bc7e4978dbe6a92758ad1cbd>`
```
struct __cppobj Village::_pruneRecentlyWorkedDwellers::__l2::<lambda_746584a7bc7e4978dbe6a92758ad1cbd>
{
  Village *const __this;
};

```

### `Village::_getNumRecentlyWorkedDwellers::__l2::<lambda_8facc359e30bd890555deddd5d9d5599>`
```
struct __cppobj Village::_getNumRecentlyWorkedDwellers::__l2::<lambda_8facc359e30bd890555deddd5d9d5599>
{
  const __int64 workTimestampCutoff;
};

```

### `VillageManager::getPOIInitEventFromName::__l2::<lambda_667ffddfe043e276035af12649652ced>`
```
struct __cppobj VillageManager::getPOIInitEventFromName::__l2::<lambda_667ffddfe043e276035af12649652ced>
{
  const HashedString *name;
};

```

### `Village::_saveVillageDwellers::__l8::<lambda_94cc6a044a321f8f2d459e65af577bed>`
```
struct __cppobj Village::_saveVillageDwellers::__l8::<lambda_94cc6a044a321f8f2d459e65af577bed>
{
  const std::pair<ActorUniqueID const ,Village::DwellerData> *actorID;
};

```

### `Village::trySetVillagerWorkTimestamp::__l5::<lambda_298756b1985793f5750058c078d2f10e>`
```
struct __cppobj Village::trySetVillagerWorkTimestamp::__l5::<lambda_298756b1985793f5750058c078d2f10e>
{
  const ActorUniqueID *id;
};

```

### `VillagerV2::updateEntitySpecificMolangVariables::__l2::<lambda_a40f3d6a280100bd20fdada013492f26>::()::__l2::Literal`
```
struct __cppobj VillagerV2::updateEntitySpecificMolangVariables::__l2::<lambda_a40f3d6a280100bd20fdada013492f26>::()::__l2::Literal
{
};

```

### `VillagerV2::updateEntitySpecificMolangVariables::__l2::<lambda_a40f3d6a280100bd20fdada013492f26>`
```
struct __cppobj VillagerV2::updateEntitySpecificMolangVariables::__l2::<lambda_a40f3d6a280100bd20fdada013492f26>
{
};

```

### `VanillaSurfaceBuilders::Utils::buildSurface::__l16::<lambda_ec5709d38353adcc7da37c895a1d8906>::()::__l2::Literal`
```
struct __cppobj VanillaSurfaceBuilders::Utils::buildSurface::__l16::<lambda_ec5709d38353adcc7da37c895a1d8906>::()::__l2::Literal
{
};

```

### `VanillaSurfaceBuilders::Utils::buildSurface::__l16::<lambda_ec5709d38353adcc7da37c895a1d8906>`
```
struct __cppobj VanillaSurfaceBuilders::Utils::buildSurface::__l16::<lambda_ec5709d38353adcc7da37c895a1d8906>
{
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum CoralDirection>::get::__l2::<lambda_b097d27233f25a7831909887f6bca39b>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum CoralDirection>::get::__l2::<lambda_b097d27233f25a7831909887f6bca39b>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum LeverDirection>::get::__l2::<lambda_12173f4d88dac392ec6238da8b86929d>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum LeverDirection>::get::__l2::<lambda_12173f4d88dac392ec6238da8b86929d>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PillarAxis>::get::__l2::<lambda_77719526202a058a2659f35b68a8afea>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PillarAxis>::get::__l2::<lambda_77719526202a058a2659f35b68a8afea>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PortalAxis>::get::__l2::<lambda_26aee33b246ba52692a0b0fc6c10f06d>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PortalAxis>::get::__l2::<lambda_26aee33b246ba52692a0b0fc6c10f06d>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum RailDirection>::get::__l2::<lambda_b887a6b4e0f79c46c40655adf6c036d6>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum RailDirection>::get::__l2::<lambda_b887a6b4e0f79c46c40655adf6c036d6>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum TorchFacing>::get::__l2::<lambda_95a0d5be0f750bc2ab1441f31d404139>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum TorchFacing>::get::__l2::<lambda_95a0d5be0f750bc2ab1441f31d404139>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum WeirdoDirection>::get::__l2::<lambda_ab17b9537440bf745fdf727699ab2f35>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum WeirdoDirection>::get::__l2::<lambda_ab17b9537440bf745fdf727699ab2f35>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum CoralDirection>::get::__l2::<lambda_e45a2138e47c0e55367e6dd408148d86>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum CoralDirection>::get::__l2::<lambda_e45a2138e47c0e55367e6dd408148d86>
{
  CoralDirection value;
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum LeverDirection>::get::__l2::<lambda_a01120809e48f4b8d7a8fa6528641bf2>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum LeverDirection>::get::__l2::<lambda_a01120809e48f4b8d7a8fa6528641bf2>
{
  LeverDirection value;
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PillarAxis>::get::__l2::<lambda_5a785b1f9212e0ff9f2b43e14bfed9b9>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PillarAxis>::get::__l2::<lambda_5a785b1f9212e0ff9f2b43e14bfed9b9>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PortalAxis>::get::__l2::<lambda_c2a6b74a205cfeb5686b6105a1975919>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum PortalAxis>::get::__l2::<lambda_c2a6b74a205cfeb5686b6105a1975919>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum RailDirection>::get::__l2::<lambda_681ecf4e62b46d0e7d71ae5fae35eb9c>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum RailDirection>::get::__l2::<lambda_681ecf4e62b46d0e7d71ae5fae35eb9c>
{
  RailDirection value;
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum TorchFacing>::get::__l2::<lambda_983a2a10673ff0b3a95de78804ef97b9>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum TorchFacing>::get::__l2::<lambda_983a2a10673ff0b3a95de78804ef97b9>
{
  _BYTE value[4];
};

```

### `VanillaBlockStateTransformUtils::CommonDirectionMapping<enum WeirdoDirection>::get::__l2::<lambda_0d390205c0db002d59378506c50958a3>`
```
struct __cppobj VanillaBlockStateTransformUtils::CommonDirectionMapping<enum WeirdoDirection>::get::__l2::<lambda_0d390205c0db002d59378506c50958a3>
{
  WeirdoDirection value;
};

```

### `VanillaBlockStateTransformUtils::transformStandingRotation::__l2::<lambda_15870c03f8b050832b4eb10d4536c270>`
```
struct __cppobj VanillaBlockStateTransformUtils::transformStandingRotation::__l2::<lambda_15870c03f8b050832b4eb10d4536c270>
{
  const int halfSteps;
  const int variationCount;
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_b247a10df3b84cb793fe5646caabcc6f>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_b247a10df3b84cb793fe5646caabcc6f>
{
  CompoundTagUpdaterContext *context;
};

```

### `VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ce8f42aceb71021379fa0d4fca3870f8>`
```
struct __cppobj VanillaBlockUpdater::addUpdaters_1_16_0::__l2::<lambda_ce8f42aceb71021379fa0d4fca3870f8>
{
  CompoundTagUpdaterContext *context;
};

```

### `VanillaBlockStateTransformUtils::transformVineDirectionBits::__l2::<lambda_a1cf2667ef7f49ed3371b68272fd84bd>`
```
struct __cppobj VanillaBlockStateTransformUtils::transformVineDirectionBits::__l2::<lambda_a1cf2667ef7f49ed3371b68272fd84bd>
{
};

```

### `VanillaBlockStateTransformUtils::transformVineDirectionBits::__l2::<lambda_bb09bc831737bb99086e65a9cde02f9c>`
```
struct __cppobj VanillaBlockStateTransformUtils::transformVineDirectionBits::__l2::<lambda_bb09bc831737bb99086e65a9cde02f9c>
{
};

```

### `VanillaBlockInteractionsUIListener::{ctor}::__l2::<lambda_f34ed4ece60259c38cc296221c0f2d15>`
```
struct __cppobj VanillaBlockInteractionsUIListener::{ctor}::__l2::<lambda_f34ed4ece60259c38cc296221c0f2d15>
{
  VanillaBlockInteractionsUIListener *const __this;
  SceneFactory *sceneFactory;
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_811f2357007283fd11066f498da84188>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_811f2357007283fd11066f498da84188>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_ec55570015b9a5e3a41cd99346cb1570>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_ec55570015b9a5e3a41cd99346cb1570>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_bded4f3fcfe6a187c35c1c1b3555a90e>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_bded4f3fcfe6a187c35c1c1b3555a90e>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_f6b17ad9746003dca1b0c3195e469182>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_f6b17ad9746003dca1b0c3195e469182>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_4819149d4c73f02b6c8625b93773f28b>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_4819149d4c73f02b6c8625b93773f28b>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_aca40fa8217e31112dbfde94b39aa1bb>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_aca40fa8217e31112dbfde94b39aa1bb>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_317c82060279a925e9b9a354271436d0>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_317c82060279a925e9b9a354271436d0>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_8840dbfeb5c14df5dc414610390e5289>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_8840dbfeb5c14df5dc414610390e5289>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_34d9126d8070755f20ab9518f7d5321c>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_34d9126d8070755f20ab9518f7d5321c>
{
};

```

### `VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_479f72b3c7b966a9a3dd3f788562fb81>`
```
struct __cppobj VanillaBlockInteractionsUIListener::onBlockInteractedWith::__l7::<lambda_479f72b3c7b966a9a3dd3f788562fb81>
{
};

```

### `VanillaGameModuleClient::initializeResourceStack::__l2::<lambda_9c10a8011ccc3b3e213a82ddf3cc763a>`
```
struct __cppobj VanillaGameModuleClient::initializeResourceStack::__l2::<lambda_9c10a8011ccc3b3e213a82ddf3cc763a>
{
  ResourcePackRepository *repo;
  ResourcePackStack *stack;
};

```

### `VanillaXboxLiveAchievementsEventListener::_checkForStructureAchievements::__l2::<lambda_bd3c82aa53bf2bda4eb6a398433732c0>`
```
struct __cppobj VanillaXboxLiveAchievementsEventListener::_checkForStructureAchievements::__l2::<lambda_bd3c82aa53bf2bda4eb6a398433732c0>
{
  const ItemStack *mainhandItem;
  const ItemStack *offhandItem;
};

```

### `VanillaGameModuleServer::initializeBehaviorStack::__l2::<lambda_a93a1f3aad9928113da7fc704165109a>`
```
struct __cppobj VanillaGameModuleServer::initializeBehaviorStack::__l2::<lambda_a93a1f3aad9928113da7fc704165109a>
{
  ResourcePackRepository *repo;
  ResourcePackStack *tempStack;
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l2::<lambda_16140ccafd120b593f1b68eed6513fec>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l2::<lambda_16140ccafd120b593f1b68eed6513fec>
{
  Player *player;
  const BlockPos *blockPos;
  const Block *interactedWithBlock;
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_cf6a0dc32d4e3e4057eee621c4fee6b7>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_cf6a0dc32d4e3e4057eee621c4fee6b7>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_271fe90456492963c9ebf77a6083157c>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_271fe90456492963c9ebf77a6083157c>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_0f54a591010dc2640c46d404a1ee49fd>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_0f54a591010dc2640c46d404a1ee49fd>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_013e7d27e9d5256dc34452adaa225e66>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_013e7d27e9d5256dc34452adaa225e66>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_53d8e39b373be73d3eed84af3b97c493>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_53d8e39b373be73d3eed84af3b97c493>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_d8bd3fae1c1bfaa3cc11087142333493>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_d8bd3fae1c1bfaa3cc11087142333493>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_635c07eee776678409f44006c415788e>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_635c07eee776678409f44006c415788e>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_bc73df71276eb4570950267ae6c91690>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_bc73df71276eb4570950267ae6c91690>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_aa3746b4ba9eaa55bc81c2961d2f2592>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_aa3746b4ba9eaa55bc81c2961d2f2592>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_f17a525e6dea941c813ed01d2ccabfab>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_f17a525e6dea941c813ed01d2ccabfab>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_b2bbe1c826ae203cb7e5d813f37cf12b>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_b2bbe1c826ae203cb7e5d813f37cf12b>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_41cb228a100148ea0e27822560a602b0>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_41cb228a100148ea0e27822560a602b0>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_faffd4b759b2c785101dc0b08815605d>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_faffd4b759b2c785101dc0b08815605d>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_4a21d74a3cb3b89f3c01a3ccfb2962c7>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_4a21d74a3cb3b89f3c01a3ccfb2962c7>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_2b58b29ecc4f9e6b2d3a0a37fe1738a1>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_2b58b29ecc4f9e6b2d3a0a37fe1738a1>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_485af8c30bdd05ea649d92b1309a8f3a>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_485af8c30bdd05ea649d92b1309a8f3a>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_cbff893f9bb2e3138bfbd8368038a386>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_cbff893f9bb2e3138bfbd8368038a386>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_c79217faffc8b3a940d81a60326dbc63>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_c79217faffc8b3a940d81a60326dbc63>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_ffa3915e7485145e81c4cf418cfde3c7>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_ffa3915e7485145e81c4cf418cfde3c7>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_77c5858bb7748a68650b58f6bf9153ae>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_77c5858bb7748a68650b58f6bf9153ae>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_def090672c6662e33836bce57add7c66>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_def090672c6662e33836bce57add7c66>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_66913731a9d849c1eb72ac4e5bce5cae>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_66913731a9d849c1eb72ac4e5bce5cae>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_6aed8c0680d959a0168738f579141ae8>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_6aed8c0680d959a0168738f579141ae8>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_a9950955390f9d16f160de706c135571>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_a9950955390f9d16f160de706c135571>
{
};

```

### `VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_903ff99c22a967a19b13db16f59b89ae>`
```
struct __cppobj VanillaServerGameplayEventListener::onBlockInteractedWith::__l6::<lambda_903ff99c22a967a19b13db16f59b89ae>
{
};

```

### `V113ToV114::_upgradeNoiseRange::__l2::<lambda_94058b53879072868e610799ce93baa0>::()::__l2::<lambda_40ad0332f3683702705a7ce78f5b667e>`
```
struct __cppobj V113ToV114::_upgradeNoiseRange::__l2::<lambda_94058b53879072868e610799ce93baa0>::()::__l2::<lambda_40ad0332f3683702705a7ce78f5b667e>
{
};

```

### `VanillaInputHandler_vtbl`
```
struct /*VFT*/ VanillaInputHandler_vtbl
{
  void (__fastcall *~IConfigListener)(IConfigListener *this);
  void (__fastcall *onConfigChanged)(IConfigListener *this, const Config *);
  std::unique_ptr<MoveInputHandler> *(__fastcall *_createMoveInputHandler)(MinecraftInputHandler *this, std::unique_ptr<MoveInputHandler> *result, std::weak_ptr<IClientInstance>);
  void (__fastcall *_registerInputHandlers)(MinecraftInputHandler *this);
  void (__fastcall *_registerDebugInputHandlers)(MinecraftInputHandler *this);
};

```

### `Vex_vtbl`
```
struct /*VFT*/ Vex_vtbl
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

### `VillagePiece_vtbl`
```
struct /*VFT*/ VillagePiece_vtbl
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
  int (__fastcall *generateHeightAtPosition)(PoolElementStructurePiece *this, const BlockPos *, Dimension *, BlockVolume *, std::unordered_map<ChunkPos,std::unique_ptr<std::vector<short>>> *);
  const Block *(__fastcall *getSupportBlock)(PoolElementStructurePiece *this, BlockSource *, const BlockPos *, const Block *);
  const Block *(__fastcall *getBeardStabilizeBlock)(PoolElementStructurePiece *this, const Block *);
  bool (__fastcall *_needsPostProcessing)(PoolElementStructurePiece *this, BlockSource *);
};

```

### `VillagerBase_vtbl`
```
struct /*VFT*/ VillagerBase_vtbl
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
};

```

### `VillagerV2_vtbl`
```
struct /*VFT*/ VillagerV2_vtbl
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
};

```

### `Villager_vtbl`
```
struct /*VFT*/ Villager_vtbl
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
};

```

### `VindicationIllager_vtbl`
```
struct /*VFT*/ VindicationIllager_vtbl
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

