# D
### `dragon::result::SuccessTag`
Offset | Type | Name
-|-|-|-


### `DurableCustom`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<AchievementOfferInfo>` | mAchievementInfo
16 | (32) `std::string` | mCreatorName
48 | (32) `std::string` | mRealmsTier
80 | (32) `std::string` | mRealmsPlusEndDate
112 | (32) `std::string` | mRealmsPlusStartDate
144 | (1) `bool` | mShowRealmsPlusEndDate
152 | (32) `std::string` | mShareUrl
184 | (32) `std::string` | mVideoUrl
216 | (32) `std::string` | mTextureVersion
248 | (4) `int` | mMinPerformanceTier
252 | (4) `int` | mPrice
256 | (4) `int` | mPacksIncludedInOfferCount
260 | (4) `int` | mTotalMSRP
264 | (4) `int` | mStorePriority
268 | (4) `int` | mNumSkins
272 | (4) `_BYTE[4]` | mPersonaPieceType
276 | (1) `persona::Rarity` | mPersonaPieceRarity
277 | (1) `bool` | mPurchasable
278 | (1) `bool` | mRedeemable
279 | (1) `bool` | mIsPromoItem
280 | (24) `std::vector<DateRange>` | mActiveOfferDates
304 | (24) `std::vector<std::string>` | mBundleProductIds
328 | (24) `std::vector<PackIdVersion>` | mPackIdentities
352 | (16) `std::shared_ptr<StoreVisualStyle>` | mRelatedItemsRow


### `dragon::materials::MaterialUniformName`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mHash


### `dragon::frameobject::BlitExtractAndSortSystem::ExtractAndSort::__l2::<lambda_bdd2dbd9a538efd9e8006221080bc33e>`
Offset | Type | Name
-|-|-|-


### `dragon::rendering::BufferClear`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mBufferClearMask
4 | (4) `unsigned int` | mColor
8 | (4) `float` | mDepth
12 | (1) `unsigned __int8` | mStencilRef


### `dragon::rendering::ViewSet`
Offset | Type | Name
-|-|-|-
0 | (24) `const std::vector<unsigned short>` | mSets


### `Description`
Offset | Type | Name
-|-|-|-
0 | (8) `Description_vtbl *` | __vftable


### `detail::SpawnManager`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ItemStack>` | mSpawnedItemInstance


### `detail::getRecipesByResult::__l7::<lambda_386849b12334321bacf7794b65d89835>`
Offset | Type | Name
-|-|-|-


### `detail::getRecipesByInput::__l7::<lambda_ef181433dc3cc8cd3389e6d145a10c82>`
Offset | Type | Name
-|-|-|-


### `DataStructures::List<RakNet::PluginInterface2 *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::PluginInterface2 **` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DataStructures::Queue<RakNet::Packet *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::Packet **` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::ThreadsafeAllocatingQueue<RakNet::Packet>`
Offset | Type | Name
-|-|-|-
0 | (40) `DataStructures::MemoryPool<RakNet::Packet>` | memoryPool
40 | (40) `RakNet::SimpleMutex` | memoryPoolMutex
80 | (24) `DataStructures::Queue<RakNet::Packet *>` | queue
104 | (40) `RakNet::SimpleMutex` | queueMutex


### `DataStructures::MemoryPool<RakNet::Packet>`
Offset | Type | Name
-|-|-|-
0 | (8) `DataStructures::MemoryPool<RakNet::Packet>::Page *` | availablePages
8 | (8) `DataStructures::MemoryPool<RakNet::Packet>::Page *` | unavailablePages
16 | (8) `DataStructures::MemoryPool<RakNet::Packet>::Page *` | lastReleasePage
24 | (4) `int` | availablePagesSize
28 | (4) `int` | unavailablePagesSize
32 | (4) `int` | memoryPoolPageSize


### `DataStructures::ThreadsafeAllocatingQueue<RakNet::SystemAddress>`
Offset | Type | Name
-|-|-|-
0 | (40) `DataStructures::MemoryPool<RakNet::SystemAddress>` | memoryPool
40 | (40) `RakNet::SimpleMutex` | memoryPoolMutex
80 | (24) `DataStructures::Queue<RakNet::SystemAddress *>` | queue
104 | (40) `RakNet::SimpleMutex` | queueMutex


### `DataStructures::MemoryPool<RakNet::SystemAddress>`
Offset | Type | Name
-|-|-|-
0 | (8) `DataStructures::MemoryPool<RakNet::SystemAddress>::Page *` | availablePages
8 | (8) `DataStructures::MemoryPool<RakNet::SystemAddress>::Page *` | unavailablePages
16 | (8) `DataStructures::MemoryPool<RakNet::SystemAddress>::Page *` | lastReleasePage
24 | (4) `int` | availablePagesSize
28 | (4) `int` | unavailablePagesSize
32 | (4) `int` | memoryPoolPageSize


### `DataStructures::Queue<RakNet::SystemAddress *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::SystemAddress **` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::ThreadsafeAllocatingQueue<RakNet::RemoteClient *>`
Offset | Type | Name
-|-|-|-
0 | (40) `DataStructures::MemoryPool<RakNet::RemoteClient *>` | memoryPool
40 | (40) `RakNet::SimpleMutex` | memoryPoolMutex
80 | (24) `DataStructures::Queue<RakNet::RemoteClient * *>` | queue
104 | (40) `RakNet::SimpleMutex` | queueMutex


### `DataStructures::MemoryPool<RakNet::RemoteClient *>`
Offset | Type | Name
-|-|-|-
0 | (8) `DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *` | availablePages
8 | (8) `DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *` | unavailablePages
16 | (8) `DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *` | lastReleasePage
24 | (4) `int` | availablePagesSize
28 | (4) `int` | unavailablePagesSize
32 | (4) `int` | memoryPoolPageSize


### `DataStructures::Queue<RakNet::RemoteClient * *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RemoteClient ***` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::Queue<RakNet::SystemAddress>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::SystemAddress *` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::List<unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64 *` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `dragon::mesh::translateFormat::__l3::<lambda_633e9c10ac4a5a2ae92c8d597c5207c3>`
Offset | Type | Name
-|-|-|-


### `dragon::rendering::BloomParameters`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | enabled
4 | (4) `float` | multiplier
8 | (4) `int` | mipLevels


### `dragon::rendering::<unnamed_type_rtBufferFormats>`
Offset | Type | Name
-|-|-|-
0 | (4) `mce::TextureFormat` | mTextureFormat
4 | (4) `dragon::rendering::RtBufferSizes` | mSize


### `dragon::rendering::ToneMappingParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | intensity
4 | (1) `bool` | colorGradingEnabled
8 | (4) `float` | colorTemperature
12 | (4) `float` | colorTint
16 | (4) `float` | shadowContrast
20 | (4) `float` | shadowContrastEnd
24 | (4) `float` | curveShift
28 | (4) `float` | dynamicRange
32 | (4) `float` | shadowMinSlope
36 | (4) `float` | maxExposureIncrease
40 | (4) `float` | filmicSaturationCorrection
44 | (1) `bool` | debugMode


### `dragon::result::FailureTag`
Offset | Type | Name
-|-|-|-


### `DropItemForGoal::start::__l2::<lambda_70c3bde66f3ae4c4e2559bc58752dbed>`
Offset | Type | Name
-|-|-|-
0 | (8) `const Vec3 *` | mobPos


### `dbcs_index`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int16 *` | map
8 | (1) `unsigned __int8` | bottom
9 | (1) `unsigned __int8` | top


### `dbcs_map`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | charset
8 | (8) `const unim_index *` | encmap
16 | (8) `const dbcs_index *` | decmap


### `dfa`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | d_type
8 | (8) `char *` | d_name
16 | (4) `int` | d_initial
20 | (4) `int` | d_nstates
24 | (8) `state *` | d_state
32 | (8) `char *` | d_first


### `D3D11_INPUT_ELEMENT_DESC`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | SemanticName
8 | (4) `unsigned int` | SemanticIndex
12 | (4) `DXGI_FORMAT` | Format
16 | (4) `unsigned int` | InputSlot
20 | (4) `unsigned int` | AlignedByteOffset
24 | (4) `D3D11_INPUT_CLASSIFICATION` | InputSlotClass
28 | (4) `unsigned int` | InstanceDataStepRate


### `DXGI_SAMPLE_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Count
4 | (4) `unsigned int` | Quality


### `D3D12_HEAP_PROPERTIES`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_HEAP_TYPE` | Type
4 | (4) `D3D12_CPU_PAGE_PROPERTY` | CPUPageProperty
8 | (4) `D3D12_MEMORY_POOL` | MemoryPoolPreference
12 | (4) `unsigned int` | CreationNodeMask
16 | (4) `unsigned int` | VisibleNodeMask


### `D3D12_INPUT_ELEMENT_DESC`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | SemanticName
8 | (4) `unsigned int` | SemanticIndex
12 | (4) `DXGI_FORMAT` | Format
16 | (4) `unsigned int` | InputSlot
20 | (4) `unsigned int` | AlignedByteOffset
24 | (4) `D3D12_INPUT_CLASSIFICATION` | InputSlotClass
28 | (4) `unsigned int` | InstanceDataStepRate


### `D3D12_RANGE`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | Begin
8 | (8) `unsigned __int64` | End


### `DelayedDeleter<SubChunkBrightnessStorage>`
Offset | Type | Name
-|-|-|-
0 | (32) `std::priority_queue<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBrightnessStorage> >,std::vector<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBrightnessStorage> >>,std::greater<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBrightnessStorage> > > >` | mEntries
32 | (80) `std::mutex` | mEntriesMutex


### `DirtyTicksCounter`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | totalTime
4 | (4) `int` | lastChange


### `DataStructures::List<RakNet::RakString::SharedString *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakString::SharedString **` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DynDnsResult`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | description
8 | (8) `const char *` | code
16 | (4) `RakNet::DynDnsResultCode` | resultCode


### `DelayedDeleter<SubChunkBlockStorage>`
Offset | Type | Name
-|-|-|-
0 | (32) `std::priority_queue<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBlockStorage> >,std::vector<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBlockStorage> >>,std::greater<std::pair<std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >,std::unique_ptr<SubChunkBlockStorage> > > >` | mEntries
32 | (80) `std::mutex` | mEntriesMutex


### `DlcUIWrapper::tick::__l16::<lambda_bfd2b51cecfab4c1e061c5edadc6ab82>`
Offset | Type | Name
-|-|-|-
0 | (8) `DlcUIWrapper *const` | __this
8 | (144) `DlcDependency` | unownedDependency


### `DlcDependency`
Offset | Type | Name
-|-|-|-
0 | (136) `PackIdVersion` | mPackIdentity
136 | (8) `const ManifestContentItem *` | mManifestContentItem


### `DlcUIWrapper::tick::__l58::<lambda_60f23828f0d7604993f7eea9ab594137>`
Offset | Type | Name
-|-|-|-
0 | (8) `DlcUIWrapper *const` | __this
8 | (16) `std::weak_ptr<bool>` | weak


### `DlcId`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mUsePersonaLookupRequest
8 | (32) `std::string` | mProductId
40 | (32) `std::string` | mBinaryType
72 | (128) `DlcHydrationInfo` | mHydrationInfo


### `DlcHydrationInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mTitle
32 | (32) `std::string` | mContentId
64 | (32) `std::string` | mContentUrl
96 | (24) `std::vector<PackIdVersion>` | mPackIdentities
120 | (1) `bool` | mTitleLocked


### `dragon::rendering::drawcommands::BufferBinding`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mStage
2 | (6) `std::variant<bgfx::IndexBufferHandle,bgfx::VertexBufferHandle,bgfx::DynamicIndexBufferHandle,bgfx::DynamicVertexBufferHandle,bgfx::IndirectBufferHandle,dragon::rendering::drawcommands::BufferBinding::ShaderBufferHandle>` | mHandle
8 | (4) `bgfx::Access::Enum` | mAccess


### `dragon::rendering::drawcommands::BufferBinding::ShaderBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::UniformHandle` | mSampler
2 | (2) `bgfx::ShaderBufferHandle` | mHandle


### `dragon::platform::helpers::VisitOverloaded<<lambda_2065e32731376600173fb4ea1bcbb9b4>,<lambda_bc8cc4a5e9bcd28e4962e401584e810c>,<lambda_d00193f480816348f3992a08441a80fb>,<lambda_19a39ca30a9c1cb36d3b066a66e079bf>,<lambda_b383a9617f3dde04ca8205eadd764394>,<lambda_7354503bf8e6830a096570bb83fb0ea9>,<lambda_de38cdb3b974332c0bb3c504ceb15d8d> >`
Offset | Type | Name
-|-|-|-
0 | (8) `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_2065e32731376600173fb4ea1bcbb9b4>` | baseclass_0
8 | (32) `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_bc8cc4a5e9bcd28e4962e401584e810c>` | baseclass_8
40 | (32) `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_d00193f480816348f3992a08441a80fb>` | baseclass_28
72 | (24) `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_19a39ca30a9c1cb36d3b066a66e079bf>` | baseclass_48
96 | (24) `MinecraftGame::_updateTextureAtlasPBRData::__l17::<lambda_b383a9617f3dde04ca8205eadd764394>` | baseclass_60
120 | (1) `_BYTE` | gap78


### `DataBindingComponent::DataBinding`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | bindingType
4 | (4) `_BYTE[4]` | bindingCondition
8 | (32) `std::string` | bindingName
40 | (32) `UiExpression` | bindingExpression
72 | (32) `std::string` | bindingNameOverride
104 | (32) `std::string` | collectionName
136 | (32) `std::string` | collectionPrefix
168 | (32) `UiExpression` | viewBindingSourcePropertyName
200 | (32) `std::string` | viewBindingTargetPropertyName
232 | (16) `std::weak_ptr<UIControl>` | viewBindingSourceControl
248 | (4) `unsigned int` | collectionNameHash
252 | (4) `unsigned int` | bindingNameHash
256 | (4) `int` | collectionIndex
260 | (1) `bool` | alreadyBoundOnce
261 | (1) `bool` | visible


### `DataBindingComponent::_addBindings::__l2::<lambda_ae694adc5431441ed2a34f3dcdf92f95>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ExprToken *` | overrideToken
8 | (8) `BindingType *` | bindingType
16 | (8) `const std::string *` | collectionName
24 | (8) `const unsigned __int64 *` | collectionNameHash
32 | (8) `UiExpression *` | bindingExpression
40 | (8) `const std::string *` | bindingNameOverride
48 | (8) `const BindingCondition *` | bindingCondition
56 | (8) `DataBindingComponent *const` | __this


### `DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::queue::__l2::<lambda_1671079fd17c377b6ba1e3322caff484>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::promise<enum DeferredTasksManager<enum MinecraftGame::DeferredTaskCategory>::Reason> >` | promise
16 | (64) `std::function<void __cdecl(void)>` | callback


### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Span`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Page *` | mPage
8 | (8) `unsigned __int64` | mBegin
16 | (8) `unsigned __int64` | mEnd
24 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >` | mHandle
40 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >` | mBuffer
56 | (4) `unsigned int` | mBucketKey
60 | (4) `unsigned int` | mBytesOffset
64 | (4) `unsigned int` | mElementCount
68 | (4) `unsigned int` | mPayLoadSize


### `dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mValue


### `dragon::platform::helpers::VisitOverloaded<<lambda_e54f98baf2987f77ea926a7cd49c8fc6>,<lambda_b5e7774ec560db157d48075e329552a9>,<lambda_8e4ab82d5bcb07b8427408b8b83b3761> >`
Offset | Type | Name
-|-|-|-
0 | (8) `_renderLayer::__l2::<lambda_d082a5f259f0ca08b9059a7e04233587>::()::__l5::<lambda_e54f98baf2987f77ea926a7cd49c8fc6>` | baseclass_0
8 | (8) `_renderLayer::__l2::<lambda_d082a5f259f0ca08b9059a7e04233587>::()::__l5::<lambda_b5e7774ec560db157d48075e329552a9>` | baseclass_8
16 | (8) `_renderLayer::__l2::<lambda_d082a5f259f0ca08b9059a7e04233587>::()::__l5::<lambda_8e4ab82d5bcb07b8427408b8b83b3761>` | baseclass_10


### `dragon::res::ServerTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | baseclass_0


### `DayOneExperienceScreenController::_registerEventHandlers::__l2::<lambda_f10099cf2a5bfbc92fa7d934f63d1af7>::()::__l2::<lambda_4ab40b1b340b633ec6109521a74361ba>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<DayOneExperienceScreenController>` | weakThis
16 | (608) `const LegacyWorldInfo` | worldInfo


### `DropdownScreenController::setUpCallbacksForCollectionDropdownOption::__l8::<lambda_c600f6519c28f876d1ec983205dafb93>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(int)>` | isEnabled


### `DayOneExperienceModel::fetchLegacySkin::__l2::<lambda_b5e83f1d4458c114d16c121ef6e05623>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<DayOneExperienceModel>` | weakThis
16 | (112) `SkinHandle` | skinHandle


### `DayOneExperienceModel::_getWorldImportCallback::__l2::<lambda_f853d7d16d9e220223621d3818c282af>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<DayOneExperienceModel>` | weakThis
16 | (32) `const std::string` | levelId
48 | (64) `std::function<void __cdecl(void)>` | failureCallback


### `DayOneExperienceModel::_onWorldConversionCompleted::__l2::<lambda_7f3628f39ee7691a06d2d3f17aea0b37>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<DayOneExperienceModel>` | weakThis
16 | (16) `std::shared_ptr<ImportResult>` | result
32 | (32) `const std::string` | levelId


### `DlcBatchModel::searchForProductIds::__l2::<lambda_2325ef26f38ec7586543d999d52bbc65>`
Offset | Type | Name
-|-|-|-
0 | (8) `DlcBatchModel *const` | __this
8 | (16) `std::weak_ptr<bool>` | weak_existence
24 | (64) `std::function<void __cdecl(bool)>` | searchCompleteCallback


### `DlcBatchModel`
Offset | Type | Name
-|-|-|-
0 | (8) `IDlcBatchModel` | baseclass_0
8 | (16) `gsl::not_null<Bedrock::NonOwnerPointer<ContentAcquisition> >` | mContentAcquisition
24 | (16) `gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> >` | mStoreCatalog
40 | (16) `std::shared_ptr<bool>` | mExistenceTracker
56 | (24) `std::vector<DlcId>` | mDlcIds
80 | (24) `std::vector<PackIdVersion>` | mPackIds
104 | (4) `_BYTE[4]` | mDlcProductIdSearch
108 | (4) `_BYTE[4]` | mInitiatorCategory


### `DBChunkStorageKey`
Offset | Type | Name
-|-|-|-
0 | (8) `const ChunkPos` | pos
8 | (4) `const AutomaticID<Dimension,int>` | id


### `DBStorageConfig`
Offset | Type | Name
-|-|-|-
0 | (8) `Scheduler *` | scheduler
8 | (32) `Core::PathBuffer<std::string >` | fullPath
40 | (32) `std::string` | levelId
72 | (32) `Core::PathBuffer<std::string >` | dbSubfolder
104 | (8) `const ContentIdentity *` | contentIdentity
112 | (8) `const IContentKeyProvider *` | keyProvider
120 | (16) `std::shared_ptr<SaveTransactionManager>` | saveTransactionManager
136 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | compactionInterval
144 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | writeFlushInterval
152 | (16) `std::shared_ptr<Core::FileStorageArea>` | storageArea
168 | (1) `bool` | enableCompactionListener
169 | (1) `bool` | enableStorage
170 | (1) `bool` | enableSnapshots


### `dragon::RenderMetadata`
Offset | Type | Name
-|-|-|-
0 | (8) `const __int64` | mID


### `dragon::platform::helpers::VisitOverloaded<<lambda_646478fcdb2a37f507ae4129658625ce>,<lambda_7625e103360d3e551555490519cd97c2>,<lambda_a9ff2fc524dc959b011c3f226a1ef25b> >`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `dragon::platform::helpers::VisitOverloaded<<lambda_d7940ffb93fe410c58f19e715232b6a2>,<lambda_5f8c4a4c624541123271290ae21b2013>,<lambda_b559a75f772e7c4c981d41b43e1aabbe> >`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `dragon::platform::helpers::VisitOverloaded<<lambda_252416c79aa1913095d3ae39c6637066>,<lambda_e40dd031a90a08d6d5d2f9c21e88995c>,<lambda_8249f339d7b54daa285aa378ab1a26f3> >`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >` | mBuffer
16 | (4) `unsigned int` | mOffset
20 | (4) `unsigned int` | mSize


### `dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mValue


### `DistanceFieldCullingStep`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawIdx
4 | (1) `char` | mX
5 | (1) `char` | mY
6 | (1) `char` | mZ
7 | (1) `unsigned __int8` | mPadding


### `dragon::frameobject::components::ViewSetId`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mValue


### `dragon::res::ClientTexture`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ClientResourcePointer<mce::ResourcePointer<dragon::res::ResolvedTextureResource,mce::ResourceBlockTemplate<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,dragon::res::TextureDescription>,std::shared_ptr> >` | baseclass_0


### `dragon::BufferDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | baseclass_0
8 | (32) `std::string` | mDebugName


### `DateRange`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mStartDate
32 | (32) `std::string` | mEndDate


### `dragon::frameobject::components::MeshFilter`
Offset | Type | Name
-|-|-|-
0 | (32) `std::variant<dragon::mesh::TypedVertexBufferHandle,mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler> >` | mVertexBuffer
32 | (4) `unsigned int` | mVertexOffset
40 | (8) `unsigned __int64` | mVertexCount
48 | (24) `std::variant<std::monostate,std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler> >` | mIndexBuffer
72 | (4) `unsigned int` | mIndexOffset
80 | (8) `unsigned __int64` | mIndexCount


### `dragon::mesh::TypedVertexBufferHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >` | mHandle
16 | (4) `std::optional<unsigned short>` | mFormat


### `dragon::guarded::GuardedAccess<std::unordered_map<mce::framebuilder::bgfxbridge::RayTraceableMeshKey,std::unique_ptr<mce::framebuilder::bgfxbridge::RayTraceableMesh,std::default_delete<mce::framebuilder::bgfxbridge::RayTraceableMesh> >,mce::framebuilder::bgfxbridge::RayTraceableMeshKeyHasher,std::equal_to<mce::framebuilder::bgfxbridge::RayTraceableMeshKey>,std::allocator<std::pair<mce::framebuilder::bgfxbridge::RayTraceableMeshKey const ,std::unique_ptr<mce::framebuilder::bgfxbridge::RayTraceableMesh,std::default_delete<mce::framebuilder::bgfxbridge::RayTraceableMesh> > > > >,std::mutex,std::unique_lock>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unordered_map<mce::framebuilder::bgfxbridge::RayTraceableMeshKey,std::unique_ptr<mce::framebuilder::bgfxbridge::RayTraceableMesh>,mce::framebuilder::bgfxbridge::RayTraceableMeshKeyHasher,std::equal_to<mce::framebuilder::bgfxbridge::RayTraceableMeshKey>,std::allocator<std::pair<mce::framebuilder::bgfxbridge::RayTraceableMeshKey const ,std::unique_ptr<mce::framebuilder::bgfxbridge::RayTraceableMesh> > > > *` | mAccess
8 | (16) `std::unique_lock<std::mutex>` | mGuard


### `dragon::materials::MaterialLocation`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | mName
32 | (16) `const std::map<std::string,std::string>` | mFlags
48 | (8) `const unsigned __int64` | mHash


### `dragon::materials::MaterialUniformMap`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > >` | mAllocator
8 | (16) `gsl::span<unsigned char,-1>` | mUniformsBlockContent
24 | (8) `std::reference_wrapper<dragon::materials::MaterialUniformHandles>` | mUniformHandles
32 | (16) `gsl::span<unsigned char,-1>` | mUniformsData
48 | (16) `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::UniformParameter>` | mUniforms
64 | (16) `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::TextureParameter>` | mTextures
80 | (16) `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::BufferParameter>` | mBuffers
96 | (128) `std::array<dragon::res::ServerTexture,8>` | mLifetimeTextures
224 | (8) `unsigned __int64` | mStateHash


### `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::UniformParameter>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | mDataPtr
8 | (2) `unsigned __int16` | mCapacity
10 | (2) `unsigned __int16` | mSize


### `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::TextureParameter>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | mDataPtr
8 | (2) `unsigned __int16` | mCapacity
10 | (2) `unsigned __int16` | mSize


### `dragon::materials::UniformDataVector<dragon::materials::MaterialUniform::BufferParameter>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | mDataPtr
8 | (2) `unsigned __int16` | mCapacity
10 | (2) `unsigned __int16` | mSize


### `dragon::frameobject::components::MaterialFilter`
Offset | Type | Name
-|-|-|-
0 | (8) `std::reference_wrapper<dragon::materials::Material const >` | mMaterial
8 | (232) `dragon::materials::MaterialUniformMap` | mUniforms


### `dragon::materials::ParameterId`
Offset | Type | Name
-|-|-|-
0 | (2) `type_safe::strong_typedef<dragon::materials::ParameterId,unsigned short>` | baseclass_0


### `dragon::frameobject::components::SortIndex`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mIndex


### `dragon::frameobject::components::SceneObject`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::RaytraceObject`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedAccelerationStructureResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedAccelerationStructureResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mBLASHandle
16 | (1) `_BYTE[1]` | mObjectType
24 | (8) `__int64` | mUniqueId
32 | (2) `_BYTE[2]` | mMaterialFlags
40 | (48) `dragon::res::ServerTexture[3]` | mTextures
88 | (8) `unsigned int[2]` | mTintColours


### `dragon::frameobject::components::UIElement`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAlphaTest


### `dragon::frameobject::components::defaultpasses::AlphaTest`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::defaultpasses::UI`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::defaultpasses::Transparent`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::defaultpasses::Opaque`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::SortOrigin`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mPosition


### `dragon::frameobject::components::PassState`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mBlendMode
4 | (1) `dragon::rendering::ColorWriteMask` | mColorWriteMask
8 | (4) `_BYTE[4]` | mCullMode
12 | (8) `dragon::rendering::DepthState` | mDepthState
20 | (4) `dragon::rendering::PrimitiveType` | mPrimitiveType
24 | (20) `dragon::rendering::ScissorTestState` | mScissorTestState
44 | (16) `dragon::rendering::StencilFaceDescription` | mFrontFaceStencil
60 | (16) `dragon::rendering::StencilFaceDescription` | mBackFaceStencil
76 | (1) `bool` | mUseStencils
77 | (1) `unsigned __int8` | mStencilRef
78 | (1) `unsigned __int8` | mStencilMask


### `dragon::rendering::ColorWriteMask`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mWriteMask


### `dragon::rendering::DepthState`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mEnabled
1 | (1) `bool` | mWriteDepth
4 | (4) `_BYTE[4]` | mComparisonFunction


### `dragon::rendering::ScissorTestState`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mEnabled
4 | (16) `glm::tvec4<float,0>` | mScissorRect


### `dragon::rendering::StencilFaceDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mComparisonFunc
4 | (4) `dragon::rendering::StencilOp` | mDepthFailOp
8 | (4) `dragon::rendering::StencilOp` | mPassOp
12 | (4) `dragon::rendering::StencilOp` | mFailOp


### `dragon::frameobject::components::Transform`
Offset | Type | Name
-|-|-|-
0 | (72) `std::variant<glm::tmat4x4<float,0>,std::vector<glm::tmat4x4<float,0>>,unsigned __int64>` | mWorldMatrix


### `dragon::frameobject::DynamicEntityTransactionBuilder<dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::Transform,dragon::frameobject::components::PassState,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::defaultpasses::AlphaTest,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::PlayerUI,dragon::frameobject::components::UIElement,dragon::frameobject::components::RaytraceObject,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SortIndex>`
Offset | Type | Name
-|-|-|-
0 | (712) `std::tuple<std::optional<dragon::frameobject::components::MeshFilter>,std::optional<dragon::frameobject::components::MaterialFilter>,std::optional<dragon::frameobject::components::Transform>,std::optional<dragon::frameobject::components::PassState>,std::optional<dragon::frameobject::components::SortOrigin>,std::optional<dragon::frameobject::components::ViewSetId>,std::optional<dragon::frameobject::components::defaultpasses::Opaque>,std::optional<dragon::frameobject::components::defaultpasses::Transparent>,std::optional<dragon::frameobject::components::defaultpasses::UI>,std::optional<dragon::frameobject::components::defaultpasses::AlphaTest>,std::optional<mce::framebuilder::gamecomponents::TransparentItemInWorldObject>,std::optional<mce::framebuilder::gamecomponents::ItemInHandObject>,std::optional<mce::framebuilder::gamecomponents::PlayerUI>,std::optional<dragon::frameobject::components::UIElement>,std::optional<dragon::frameobject::components::RaytraceObject>,std::optional<dragon::frameobject::components::SceneObject>,std::optional<dragon::frameobject::components::SortIndex> >` | mComponents


### `dragon::mesh::Mesh`
Offset | Type | Name
-|-|-|-
0 | (20) `dragon::mesh::MeshDescription` | mMeshDescription
24 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mVertexBuffer
40 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedIndexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mIndexBuffer


### `dragon::mesh::MeshDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | mVertexBufferDescription
8 | (12) `std::optional<cg::BufferDescription>` | mIndexBufferDescription


### `dragon::frameobject::components::ShadowOverlay`
Offset | Type | Name
-|-|-|-


### `dragon::mesh::VertexFormat`
Offset | Type | Name
-|-|-|-
0 | (168) `boost::container::static_vector<dragon::mesh::VertexFormat::FieldEntry,13>` | mFields
168 | (2) `unsigned __int16` | mStride


### `dragon::mesh::VertexFormat::FieldEntry`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mField
4 | (4) `_BYTE[4]` | mType
8 | (2) `unsigned __int16` | mOffset
10 | (1) `unsigned __int8` | mCount


### `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | mImpl


### `dragon::platform::helpers::VisitOverloaded<<lambda_8c81b13bcd5d75ab3d73ea62009230c1>,<lambda_bb8beb4409003096d51127f9ebf87e1e>,<lambda_99d0f8f794ca1b18902a8edf76995a3b> >`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::createExternalTexture::__l7::<lambda_8c81b13bcd5d75ab3d73ea62009230c1>` | baseclass_0
16 | (16) `mce::framebuilder::bgfxbridge::BgfxFrameExtractor::createExternalTexture::__l7::<lambda_bb8beb4409003096d51127f9ebf87e1e>` | baseclass_10


### `dragon::platform::helpers::VisitOverloaded<<lambda_7a2549314d4b2469dd85f519b18b2713>,<lambda_43d630b5188acfc25f19f26a18357d3c>,<lambda_6cf1c25155f42c1baaf07050dffdd3ae> >`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `dragon::frameobject::components::RenderTarget`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | mColorTargetTextureHandle
16 | (16) `dragon::res::ServerTexture` | mDepthTargetTextureHandle
32 | (16) `glm::tvec4<float,0>` | mViewport
48 | (16) `glm::tvec4<float,0>` | mScissor


### `dragon::frameobject::components::ForceRasterizationWithMultiply`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::ShadowCaster`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::DynamicEntityTransactionBuilder<dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::PassState,dragon::frameobject::components::RaytraceObject,dragon::frameobject::components::SceneObject,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::UI,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::SceneObjectActors>`
Offset | Type | Name
-|-|-|-
0 | (680) `std::tuple<std::optional<dragon::frameobject::components::MaterialFilter>,std::optional<dragon::frameobject::components::MeshFilter>,std::optional<dragon::frameobject::components::PassState>,std::optional<dragon::frameobject::components::RaytraceObject>,std::optional<dragon::frameobject::components::SceneObject>,std::optional<dragon::frameobject::components::ShadowCaster>,std::optional<dragon::frameobject::components::SortIndex>,std::optional<dragon::frameobject::components::SortOrigin>,std::optional<dragon::frameobject::components::Transform>,std::optional<dragon::frameobject::components::UIElement>,std::optional<dragon::frameobject::components::ViewSetId>,std::optional<dragon::frameobject::components::ForceRasterizationWithMultiply>,std::optional<dragon::frameobject::components::defaultpasses::AlphaTest>,std::optional<dragon::frameobject::components::defaultpasses::Opaque>,std::optional<dragon::frameobject::components::defaultpasses::Transparent>,std::optional<dragon::frameobject::components::defaultpasses::UI>,std::optional<mce::framebuilder::gamecomponents::ItemInHandObject>,std::optional<mce::framebuilder::gamecomponents::PlayerUI>,std::optional<mce::framebuilder::gamecomponents::SceneObjectActors> >` | mComponents


### `dragon::frameobject::DynamicEntityTransactionBuilder<dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::Transform,dragon::frameobject::components::PassState,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::SceneObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::InLevelCubeMapObject,dragon::frameobject::components::UIElement,dragon::frameobject::components::SortIndex,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::UI,mce::framebuilder::gamecomponents::PlayerUI,dragon::frameobject::components::SceneOverlayObject,mce::framebuilder::gamecomponents::WaterHoleObject,dragon::frameobject::components::RaytraceObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,mce::framebuilder::gamecomponents::VrPresenceObject>`
Offset | Type | Name
-|-|-|-
0 | (744) `std::tuple<std::optional<dragon::frameobject::components::MeshFilter>,std::optional<dragon::frameobject::components::MaterialFilter>,std::optional<dragon::frameobject::components::Transform>,std::optional<dragon::frameobject::components::PassState>,std::optional<dragon::frameobject::components::SortOrigin>,std::optional<dragon::frameobject::components::SceneObject>,std::optional<mce::framebuilder::gamecomponents::EnvironmentalText>,std::optional<mce::framebuilder::gamecomponents::ItemInHandObject>,std::optional<mce::framebuilder::gamecomponents::InLevelCubeMapObject>,std::optional<dragon::frameobject::components::UIElement>,std::optional<dragon::frameobject::components::SortIndex>,std::optional<dragon::frameobject::components::ViewSetId>,std::optional<dragon::frameobject::components::defaultpasses::Opaque>,std::optional<dragon::frameobject::components::defaultpasses::Transparent>,std::optional<dragon::frameobject::components::defaultpasses::UI>,std::optional<mce::framebuilder::gamecomponents::PlayerUI>,std::optional<dragon::frameobject::components::SceneOverlayObject>,std::optional<mce::framebuilder::gamecomponents::WaterHoleObject>,std::optional<dragon::frameobject::components::RaytraceObject>,std::optional<dragon::frameobject::components::SelectionOverlayObject>,std::optional<dragon::frameobject::components::ForceRasterization>,std::optional<dragon::frameobject::components::ForceRasterizationWithMultiply>,std::optional<mce::framebuilder::gamecomponents::VrPresenceObject> >` | mComponents


### `dragon::frameobject::components::ForceRasterization`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::SelectionOverlayObject`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::SceneOverlayObject`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::ShadowVolume`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::defaultpasses::StencilWrite`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::SceneSkyObject`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::ParticleObject`
Offset | Type | Name
-|-|-|-


### `dragon::frameobject::components::LightParameters`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mColor
12 | (4) `float` | mIntensity
16 | (1) `bool` | mIsLarge


### `dragon::platform::helpers::VisitOverloaded<<lambda_9bf98d6e7c0ab933ef7fbe91a62554f0>,<lambda_5912e87a3c190284b51ff76d03e89a1a> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>::tryGet::__l2::<lambda_9bf98d6e7c0ab933ef7fbe91a62554f0>` | baseclass_0
8 | (16) `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>::tryGet::__l2::<lambda_5912e87a3c190284b51ff76d03e89a1a>` | baseclass_8


### `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>::tryGet::__l2::<lambda_9bf98d6e7c0ab933ef7fbe91a62554f0>`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | hasValue


### `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>::tryGet::__l2::<lambda_5912e87a3c190284b51ff76d03e89a1a>`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | hasValue
8 | (8) `std::variant<dragon::rendering::SharedTextureHandle> *` | result


### `dragon::CreateVertexOnlyAccelerationStructureTransaction`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mVertexBuffer
16 | (4) `unsigned int` | mVertexCount
20 | (4) `unsigned int` | mVertexOffset
24 | (2) `_BYTE[2]` | mBuildFlags


### `dragon::materials::MaterialUniformOverrides`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *const` | mAllocator
8 | (32) `std::vector<dragon::materials::MaterialUniformOverrides::UniformPair,Core::CpuRingBufferAllocator<dragon::materials::MaterialUniformOverrides::UniformPair,2,0,Core::CheckedRingBuffer<2,0> > >` | mUniforms
40 | (24) `std::vector<dragon::res::ServerTexture>` | mTextureLifetime


### `dragon::rendering::modules::BlitTaskContext`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::math::Rect<unsigned short>` | mViewportRect
8 | (120) `dragon::frameobject::StateFlagPreparedDraws` | mStateFlagPreparedDraws


### `dragon::frameobject::StateFlagPreparedDraws`
Offset | Type | Name
-|-|-|-
0 | (88) `dragon::rendering::GPUState` | mGPUState
88 | (32) `std::vector<dragon::frameobject::PreparedDraw,Core::CpuRingBufferAllocator<dragon::frameobject::PreparedDraw,2,0,Core::CheckedRingBuffer<2,0> > >` | mPreparedDraws


### `dragon::rendering::GPUState`
Offset | Type | Name
-|-|-|-
0 | (64) `dragon::rendering::RenderStateFlags` | mStateFlags
64 | (20) `dragon::rendering::ScissorTestState` | mScissorTestState


### `dragon::rendering::RenderStateFlags`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mBackStencilState
8 | (8) `unsigned __int64` | mBlendState
16 | (8) `unsigned __int64` | mCullMode
24 | (8) `unsigned __int64` | mDepthTest
32 | (4) `unsigned int` | mFrontStencilState
40 | (8) `unsigned __int64` | mMSAA
48 | (8) `unsigned __int64` | mPrimitiveType
56 | (8) `unsigned __int64` | mWriteMask


### `dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | index
8 | (8) `const dragon::framegraph::detail::AbstractResource<dragon::rendering::RenderContext> *` | resource
16 | (8) `const dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> *` | predecessor


### `dragon::frameobject::PreparedBlits`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | mRenderTargetTextureHandle
16 | (8) `cg::math::Rect<unsigned short>` | mViewportRect
24 | (120) `dragon::frameobject::StateFlagPreparedDraws` | mStateFlagPreparedDraws


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::Token`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::pair<std::bitset<59>,std::array<unsigned short,59> > *` | mIndex


### `dragon::frameobject::BlitExtractAndSortSystem::ExtractAndSort::__l2::<lambda_e5e64091840cd71f246711141e63d644>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::frameobject::BlitableEntityCollection *` | outputBlitableEntityCollection
8 | (8) `unsigned int *` | idx


### `dragon::frameobject::SortedEntity`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mEntityIndex
8 | (16) `std::variant<std::monostate,dragon::frameobject::OrderSortKey,dragon::frameobject::RenderTargetSortKey>` | mSortKey


### `dragon::frameobject::OrderSortKey`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mIndex


### `dragon::frameobject::RenderTargetSortKey`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mRenderTargetKey


### `dragon::framegraph::detail::ResourceInitialization`
Offset | Type | Name
-|-|-|-


### `dragon::framegraph::dependency::BindFramebufferDepth<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::framegraph::detail::AbstractResource<dragon::rendering::RenderContext> *` | resource
8 | (8) `const dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> *` | predecessor


### `dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialUniformName` | name
8 | (4) `unsigned int` | flags
16 | (8) `const dragon::framegraph::detail::AbstractResource<dragon::rendering::RenderContext> *` | resource
24 | (8) `const dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> *` | predecessor


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Sortable`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mValue
8 | (16) `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::Token` | mKey


### `dragon::rendering::drawutils::GenericPassSet`
Offset | Type | Name
-|-|-|-
0 | (280) `const dragon::rendering::Camera` | mCamera
280 | (148) `const dragon::rendering::ViewDescription` | mViewDesc
432 | (24) `const dragon::rendering::ViewSet` | mViewSets


### `dragon::rendering::Camera`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::CameraHandle` | mHandle
8 | (8) `cg::math::Rect<unsigned short>` | mViewport
16 | (8) `cg::math::Rect<unsigned short>` | mScissorRect
24 | (64) `glm::tmat4x4<float,0>` | mProjectionMatrix
88 | (64) `glm::tmat4x4<float,0>` | mViewMatrix
152 | (12) `glm::tvec3<float,0>` | mPosition
164 | (12) `glm::tvec3<float,0>` | mTarget
176 | (12) `glm::tvec3<float,0>` | mRight
188 | (12) `glm::tvec3<float,0>` | mUp
200 | (12) `glm::tvec3<float,0>` | mDirection
212 | (4) `float` | mDistanceToTarget
216 | (16) `dragon::rendering::BufferClear` | mBufferClear
232 | (32) `std::optional<std::vector<unsigned short> >` | mRegistryEntryHandlesFilter
264 | (12) `std::optional<dragon::rendering::RenderTargetTexture>` | mRenderTargetTexture


### `dragon::rendering::CameraHandle`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mID


### `dragon::rendering::RenderTargetTexture`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mWidth
2 | (2) `unsigned __int16` | mHeight
4 | (4) `mce::TextureFormat` | mFormat


### `dragon::rendering::ViewDescription`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,0>` | mViewMatrix
64 | (64) `glm::tmat4x4<float,0>` | mProjectionMatrix
128 | (8) `cg::math::Rect<unsigned short>` | mViewportRect
136 | (8) `cg::math::Rect<unsigned short>` | mScissorRect
144 | (4) `bgfx::ViewMode::Enum` | mViewMode


### `dragon::rendering::details::RenderPass`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<dragon::rendering::details::DepthBind>` | mDepthOutput
24 | (24) `std::vector<dragon::rendering::details::ColorBind>` | mColorOutputs
48 | (24) `std::vector<std::shared_ptr<dragon::rendering::ProcessingPassReference>>` | mDependencies
72 | (24) `std::vector<std::variant<dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind,dragon::rendering::details::MaterialBind>>` | mReferencedResources
96 | (64) `std::function<void __cdecl(dragon::framegraph::Declarator<dragon::rendering::RenderContext> &)>` | mTask


### `dragon::rendering::details::DepthBind`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::details::ResourceReference` | baseclass_0


### `dragon::rendering::details::ResourceReference`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<dragon::rendering::details::ResourceToken>` | mResourceInst


### `dragon::rendering::drawutils::GenericPassContext<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | mAllocator
8 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | mFrame
16 | (64) `dragon::materials::MaterialUniformOverrides` | mGlobalOverrides
80 | (24) `const std::vector<dragon::rendering::drawutils::GenericPassSet>` | mViews
104 | (116) `std::optional<dragon::rendering::PassStateOverride>` | mPassStateOverride


### `dragon::rendering::PassStateOverride`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<enum dragon::materials::definition::BlendMode>` | mBlendMode
8 | (2) `std::optional<dragon::rendering::ColorWriteMask>` | mColorWriteMask
12 | (8) `std::optional<enum dragon::rendering::CullMode>` | mCullMode
20 | (12) `std::optional<dragon::rendering::DepthState>` | mDepthState
32 | (8) `std::optional<enum dragon::rendering::PrimitiveType>` | mPrimitiveType
40 | (24) `std::optional<dragon::rendering::ScissorTestState>` | mScissorTestState
64 | (20) `std::optional<dragon::rendering::StencilFaceDescription>` | mFrontFaceStencil
84 | (20) `std::optional<dragon::rendering::StencilFaceDescription>` | mBackFaceStencil
104 | (2) `std::optional<bool>` | mUseStencils
106 | (2) `std::optional<unsigned char>` | mStencilRef
108 | (2) `std::optional<unsigned char>` | mStencilMask


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (24) `std::tuple<dragon::rendering::details::ColorBind>` | mDeps


### `dragon::rendering::details::ColorBind`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::details::ResourceReference` | baseclass_0
16 | (8) `unsigned __int64` | mSlot


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind &,dragon::rendering::details::DepthBind &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (40) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind>` | mDeps


### `dragon::rendering::GraphicsFrame::renderPass::__l2::<lambda_774850311c9251349888708a89857a6c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::details::RenderPassImpl<1,1> >` | pass
16 | (148) `const dragon::rendering::ViewDescription` | viewDesc
168 | (24) `const std::array<dragon::rendering::details::ColorBind,1>` | outputs
192 | (16) `const dragon::rendering::details::DepthBind` | depth


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_d5c41a8665205acfcaae1feb187f614b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::rendering::drawutils::PassName`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mValue


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (248) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const >` | mDeps


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_57f8907306e362d2926c0098e4fc3248>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | mAllocator
8 | (32) `_BYTE[32]` | gap8


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_6a61ff7dc493e5b9dc6c4cead7477bea>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_4378bb29cdae57b5f79ab4f9c606ef3c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_3ee972886b322cfb9b657e57b39ba271>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_8e01741070d5550cd75b0da09894126f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_7e3f19a70eed3a8a21dee45342b01d14>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_49cd90139af99ff87757a2e1d9f2530a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_0e91431e7a0459a6236f4d1793144489>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_1aa2a88118f1b6e02e04f1ec9ef27fcc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_80e32c786a40dd173344dd99abcc359f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_a7be69a6662f1436a41ece6b25a332b1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_231c444cb28859b305af13c3ed8efa5b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_fac1e80b0d6a095d31f9926323df99b2>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_a8a839dc4793ee0a3287aee38d3e03b1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_874a8a2401ae3dd6440a18238da46cf9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_22b9fee9e63c68574e8d4b3283d182a2>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_a287a9caf8b162bca7585bb9c73c21eb>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_327a1d77757de78d470f28085b7bd13f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_9ee343709d9e515e8545c9066709aab0>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_20eca4c96e635601f467716e71ef5127>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_7b0b6bec730901ae2afb1ad9ba5d4d78>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_707ba98f6dfda2ed955e06ac0e9fb55f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_20eda95cfd45f20a0b6b2a63f14e8d19>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_d963d4e6b975d8215015eccaae5b1bf7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_a61563ef68d1d93eca88e6393b7009c1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_2cb94bed089de23fd989079c446bdeee>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_93958a1ebf928a9e4035eea1d73fcdac>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_97573ea1743928fabdfda971892bd787>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_c1de86e95f1e58f5a2437c27562c4fdd>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_f34cdd088887992dffcd882e784f8569>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_c470b6ef3e79acdf827bd7b63ada3f58>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_918f7320bce6d842e006a47770111f4a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_8c5082cbab699e2fea31f376d9cf3812>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_3db7f1931d62aa34bcd2045eb0f56181>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_73e6bff6dbdf44be6b941d624d4be031>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_aed12f97a05a0bcf6530be07038a8ebb>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_2f6ba284cb1952903a01d2c0e8843eef>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_eaa741b720f45bdcc838c3218b6b5348>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_da74fc131fea52219f7af4ef5d7af06a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_fbb9b66ce6f2adf048198b4db2604b4a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_38de0fddfbd2da6bc9cf12ebb1103d46>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_f07aac6e7efd54d6fdaee78fe63255bc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_ef2797c51fd1472c7ac52dbf1181bf67>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_e629e4fc7bd6712848d0285f51ee29b3>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_b3badc8a58b63a6ab663ec0a3af4b11b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_07031e4f9b246ab755ad2867f5429860>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_025c56c9be2240f35889d9b6dfba0a9a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_88e3055ab1a9b267bcc357cda1466710>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_bf0912574a72f7d280cbf39c0d848652>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_01ecc136dfdc25e4da2dc10cb0375bb5>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_1a726a2206f64b5a52f175b3e4359d0a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_fdc32c5a8592aad1a1ae44931b4e07f0>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_07d9da799e54b96be4508f475a3a02fe>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_e441338911c91e3490b8a661425f5b96>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_fabee5939e60f6450a04cb02e3b36058>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_30a12209703857064de4bf1b1f5fd481>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_bece8a639e85e82835654b838f8948dc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_274a984eed637eb9ce0db378abdf932c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_55e4999d5025d4777ff3503938b85431>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame>::createProcessingPass::__l2::<lambda_333df8ea756db66afc9742c532603181>`
Offset | Type | Name
-|-|-|-
8 | (64) `std::function<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> __cdecl(void)>` | callback
72 | (32) `const std::string` | name


### `dragon::rendering::details::MaterialBind`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::details::ResourceReference` | baseclass_0
16 | (8) `dragon::materials::MaterialUniformName` | mUniform
24 | (4) `unsigned int` | mFlags


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Group<dragon::frameobject::components::MaterialFilter>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mBegin
8 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mEnd
16 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mCurrent


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator`
Offset | Type | Name
-|-|-|-
0 | (8) `std::_Vector_const_iterator<std::_Vector_val<std::_Simple_types<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Sortable> > >` | mCurrent


### `dragon::rendering::GraphicsFrame::renderPass::__l2::<lambda_860e4b3feb269bc8e3c082c371074162>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::details::RenderPassImpl<0,0> >` | pass
16 | (148) `const dragon::rendering::ViewDescription` | viewDesc
168 | (24) `const std::array<dragon::rendering::details::ColorBind,0>` | outputs


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Group<dragon::frameobject::components::PassState>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mBegin
8 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mEnd
16 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mCurrent


### `dragon::platform::helpers::VisitOverloaded<<lambda_ed090bd1921bb1d9170bd9fa51a52d69> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::details::_connectDependenciesToPass::__l13::<lambda_ed090bd1921bb1d9170bd9fa51a52d69>` | baseclass_0


### `dragon::rendering::details::_connectDependenciesToPass::__l13::<lambda_ed090bd1921bb1d9170bd9fa51a52d69>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> **` | passReference


### `dragon::rendering::modules::ClearTaskContext`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::BufferClear` | mBufferClear
16 | (8) `cg::math::Rect<unsigned short>` | mViewportRect


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (56) `std::tuple<dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind>` | mDeps


### `dragon::rendering::GraphicsFrame::renderPass::__l2::<lambda_a6197f26f9fbb4dffaf59bd23bfcb4ae>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::details::RenderPassImpl<0,1> >` | pass
16 | (148) `const dragon::rendering::ViewDescription` | viewDesc
168 | (24) `const std::array<dragon::rendering::details::ColorBind,1>` | outputs


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_e090e788ff39d0cb03338f7d1447f726>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_6abd7101fb12ee977453f0547e9fadee>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_0f55557cbf18bb237929d6a860e3342a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_142794945fd02768b329ae477dd6ca9a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_21f85a6bcd1f30dd8d7c0ecd23cea834>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_02b07e64bc1b39da3b21816880b0e98e>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_64545c9df9d748ffa7c0c6e6921fd39b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_81fb1b6c59f7f26022733d4d5183e57a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_6fe3aa7498cb285ca5383612e5a53cf6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>,dragon::rendering::details::MaterialBind>::prepareExtract::__l2::<lambda_bef390f7cec0d359cc344b38c517a8c4>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (280) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_3cd69d9696ef88d9ba82b2dfe9673a33>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_7c25c214db68c49a1a84f4da17add59f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_0ee01fee31465e9b0f85295dac1145ff>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_76e5fc0e1683e75c9aeba3c12d60d9aa>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_c6c0b3f65b09febd3303f8c6630d32aa>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_b746b595a780f3b8ebf2d068eb1d4b05>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_5293118f4da994fb02871a857920b2d0>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_9dd64f71e4da4cae2390d9b03f105717>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>::_createSingleRenderPass::__l2::<lambda_1db688038bede345b19c350d24068019>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> const &,dragon::rendering::drawutils::PassName const &,dragon::materials::MaterialUniformOverrides const &,std::optional<dragon::rendering::PassStateOverride> const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (280) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>` | deps
496 | (32) `const std::string` | name


### `dragon::platform::helpers::VisitOverloaded<<lambda_694ed436aaa9c1a984d64d605e4ab72d>,<lambda_a4a5676b6794bf38764f4054b12eeaad>,<lambda_20e169b5e77590d3cbcc72e3a54fc129>,<lambda_e8027b237ad2bd129b3b44053ff973a4> >`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_a4a5676b6794bf38764f4054b12eeaad>` | baseclass_0
16 | (16) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_20e169b5e77590d3cbcc72e3a54fc129>` | baseclass_10
32 | (16) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_e8027b237ad2bd129b3b44053ff973a4>` | baseclass_20


### `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_a4a5676b6794bf38764f4054b12eeaad>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_20e169b5e77590d3cbcc72e3a54fc129>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext>::link::__l2::<lambda_e8027b237ad2bd129b3b44053ff973a4>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Group<dragon::frameobject::components::UIElement>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mBegin
8 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mEnd
16 | (8) `const dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Iterator` | mCurrent


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::_drawCallbackUI::__l7::<lambda_b0515506eb47ba7c6e6b8418f0c4fdf6>::()::__l2::<lambda_114b514df049e95dbc75a7677aec9ed0>`
Offset | Type | Name
-|-|-|-


### `dragon::rendering::drawcommands::DrawCommandContext`
Offset | Type | Name
-|-|-|-
0 | (440) `dragon::rendering::drawcommands::GraphicsCommandContext` | baseclass_0


### `dragon::rendering::drawcommands::GraphicsCommandContext`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::CommandContext *` | mCommands
8 | (384) `std::array<std::optional<dragon::rendering::drawcommands::TextureBinding>,16>` | mTextures
392 | (24) `std::vector<dragon::rendering::drawcommands::UniformBindings>` | mUniforms
416 | (24) `std::vector<dragon::rendering::drawcommands::BufferBinding>` | mBuffers


### `dragon::rendering::drawcommands::TextureBinding`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::TextureHandle` | mHandle
4 | (16) `std::variant<std::monostate,dragon::rendering::drawcommands::TextureBinding::Image,dragon::rendering::drawcommands::TextureBinding::Texture>` | mData


### `dragon::rendering::drawcommands::TextureBinding::Image`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mMip
4 | (4) `bgfx::Access::Enum` | mAccess
8 | (4) `_BYTE[4]` | mFormat


### `dragon::rendering::drawcommands::TextureBinding::Texture`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::UniformHandle` | mSampler
4 | (4) `unsigned int` | mFlags


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>,dragon::rendering::details::MaterialBind>::_drawCallbackUI::__l7::<lambda_ed02c1a32632b0d32b372548ed0653d2>::()::__l2::<lambda_7081e7f9b8d9ff2f9190bad919ce2937>`
Offset | Type | Name
-|-|-|-


### `dragon::framegraph::detail::TextureSlice<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | handle
16 | (1) `unsigned __int8` | mipLevel
17 | (1) `unsigned __int8` | arrayIndex


### `dragon::framegraph::detail::LinkingMaterialTexture<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialUniformName` | name
8 | (4) `unsigned int` | flags
16 | (32) `std::variant<std::monostate,dragon::res::ServerTexture,dragon::framegraph::detail::TextureSlice<dragon::rendering::RenderContext>,unsigned __int64>` | slot


### `dragon::rendering::drawutils::DirectDrawContext`
Offset | Type | Name
-|-|-|-
0 | (148) `dragon::rendering::ViewDescription` | mViewDesc
148 | (80) `dragon::frameobject::components::PassState` | mPassState


### `dragon::rendering::drawutils::BlitDescription`
Offset | Type | Name
-|-|-|-
0 | (40) `dragon::rendering::drawutils::BlitDescriptionTarget` | mSource
40 | (40) `dragon::rendering::drawutils::BlitDescriptionTarget` | mTarget
80 | (6) `std::optional<glm::tvec2<unsigned short,0> >` | mArea


### `dragon::rendering::drawutils::BlitDescriptionTarget`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::MaterialBind` | mTexture
32 | (1) `unsigned __int8` | mMip
34 | (4) `glm::tvec2<unsigned short,0>` | mPosition
38 | (1) `unsigned __int8` | mDepth


### `dragon::rendering::BgfxTexture2DPool::Description`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mWidth
2 | (2) `unsigned __int16` | mHeight
4 | (4) `mce::TextureFormat` | mFormat
8 | (4) `unsigned int` | mFlags
12 | (4) `dragon::rendering::TextureUsage` | mTextureUsage


### `dragon::rendering::GraphicsFrame`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame>` | baseclass_0
16 | (24) `std::vector<dragon::rendering::details::RenderPass>` | mRenderPasses
40 | (24) `std::vector<std::shared_ptr<dragon::rendering::details::ResourceToken>>` | mResources


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (8) `` | gap8


### `dragon::frameobject::FrameExplicitTarget`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | mTexture
16 | (72) `cg::TextureDescription` | mDesc


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind,dragon::rendering::details::MaterialBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (104) `std::tuple<dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::materials::MaterialUniformOverrides::UniformPair`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialUniformName` | mName
8 | (40) `std::variant<dragon::materials::MaterialUniformOverrides::UniformData<glm::tvec4<float,0> >,dragon::materials::MaterialUniformOverrides::UniformData<glm::tmat3x3<float,0> >,dragon::materials::MaterialUniformOverrides::UniformData<glm::tmat4x4<float,0> >,dragon::materials::MaterialUniformOverrides::TextureData,dragon::materials::MaterialUniformOverrides::BufferData>` | mData
48 | (8) `unsigned __int64` | mHash


### `dragon::materials::MaterialUniformOverrides::UniformData<glm::tvec4<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::vector<glm::tvec4<float,0>,Core::CpuRingBufferAllocator<glm::tvec4<float,0>,2,0,Core::CheckedRingBuffer<2,0> > >` | mData


### `dragon::materials::MaterialUniformOverrides::UniformData<glm::tmat3x3<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::vector<glm::tmat3x3<float,0>,Core::CpuRingBufferAllocator<glm::tmat3x3<float,0>,2,0,Core::CheckedRingBuffer<2,0> > >` | mData


### `dragon::materials::MaterialUniformOverrides::UniformData<glm::tmat4x4<float,0> >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::vector<glm::tmat4x4<float,0>,Core::CpuRingBufferAllocator<glm::tmat4x4<float,0>,2,0,Core::CheckedRingBuffer<2,0> > >` | mData


### `dragon::materials::MaterialUniformOverrides::TextureData`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::res::ResolvedTextureResource *` | mTexture
8 | (4) `unsigned int` | mSamplerFlags


### `dragon::materials::MaterialUniformOverrides::BufferData`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::ShaderBufferHandle` | mBuffer
2 | (1) `dragon::materials::definition::SamplerAccess` | mAccess


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_6da2fcad5326d75448d09008d2a8caa7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_c29bac36982d4929623808f769102d6e>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_f11cc7119741706b237aa275105d78db>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>,dragon::rendering::details::MaterialBind>::prepareExtract::__l2::<lambda_61ec7016f0a8c27c89d56f6740a03592>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareNonTransparent::__l2::<lambda_e3fe457de1d35696122a1141b1547cfb>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::frameobject::ScenePrepareSystem::PrepareOrderDependent::__l2::<lambda_6e83e9cad7d4026944f0b0586adbc5ce>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_1c8cbc54cb41f4ea202d52f886b3dd00>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_f8d12a7594d948618e7312716b3b0061>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_beeff1f147a05e4e35f24354d7752f56>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_6b9ecbd48a2c43900c9c240bb9dcd750>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_e516ad5f7e7a8a8b64a4ab2520389a4d>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_ac9e1aa81de2d4bae9128ecedc8519a1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_498abab3ad9e65552316e64f6cde7ca9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_66a62da18f901bac963b00546ae14b86>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_96caa2fedf9e0f041556a0aba209dfef>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::SceneLightingSystem::ExtractSceneLighting::__l2::<lambda_437c9904458fa964045824bc39d1cb62>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::frameobject::SceneLightingInformation *` | result
8 | (8) `const gsl::span<unsigned short const ,-1> *` | viewSets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::drawutils::BlitDescription const &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (152) `std::tuple<dragon::rendering::details::MaterialBind const ,dragon::rendering::details::MaterialBind const ,dragon::rendering::drawutils::BlitDescription const >` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::materials::MaterialUniformOverrides const &,__int64 &,__int64 &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView &,dragon::rendering::details::MaterialBind &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (152) `std::tuple<dragon::materials::MaterialUniformOverrides const ,__int64,__int64,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::materials::MaterialUniformOverrides const &,__int64 &,__int64 &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (120) `std::tuple<dragon::materials::MaterialUniformOverrides const ,__int64,__int64,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView>` | mDeps


### `dragon::frameobject::SceneLightingInformation::PointLight`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mWorldSpacePosition
12 | (12) `glm::tvec3<float,0>` | mColor
24 | (4) `float` | mIntensity
28 | (1) `bool` | mIsLarge


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>::_createSingleRenderPass::__l2::<lambda_845fcf2d8c9f2f827178634d4b12804b>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> const &,dragon::rendering::drawutils::PassName const &,dragon::materials::MaterialUniformOverrides const &,std::optional<dragon::rendering::PassStateOverride> const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (280) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const ,dragon::rendering::details::MaterialBind>` | deps
496 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind,dragon::rendering::details::MaterialBind>::_createSingleRenderPass::__l2::<lambda_9441f694ee284219bb13727953f67957>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::ColorBind const &,dragon::rendering::details::DepthBind const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (104) `std::tuple<dragon::rendering::details::MaterialBind,dragon::rendering::details::ColorBind,dragon::rendering::details::DepthBind,dragon::rendering::details::MaterialBind>` | deps
320 | (32) `const std::string` | name


### `dragon::platform::helpers::VisitOverloaded<<lambda_9da078c993713ac3a570e756b022fa55>,<lambda_b850d1b6627b9c5794b2644fe395a119>,<lambda_6aece11b6c48fde0326bec86d2a798bf>,<lambda_00956a5308b13d1034a46d3085aaf610> >`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_b850d1b6627b9c5794b2644fe395a119>` | baseclass_0
16 | (16) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_6aece11b6c48fde0326bec86d2a798bf>` | baseclass_10
32 | (16) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_00956a5308b13d1034a46d3085aaf610>` | baseclass_20


### `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_b850d1b6627b9c5794b2644fe395a119>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_6aece11b6c48fde0326bec86d2a798bf>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext>::link::__l2::<lambda_00956a5308b13d1034a46d3085aaf610>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::TransientImage<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::platform::helpers::VisitOverloaded<<lambda_aef58e1045f7a7a772045d87ea67b71d>,<lambda_46bbfff86b0e6684a07cb91695ad583d>,<lambda_2f2ff72c2fc0bdc31d49b69401ae8c73>,<lambda_43ccdd2872e2f97050bf30cf0ba7d0dc> >`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_46bbfff86b0e6684a07cb91695ad583d>` | baseclass_0
16 | (16) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_2f2ff72c2fc0bdc31d49b69401ae8c73>` | baseclass_10
32 | (16) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_43ccdd2872e2f97050bf30cf0ba7d0dc>` | baseclass_20


### `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_46bbfff86b0e6684a07cb91695ad583d>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_2f2ff72c2fc0bdc31d49b69401ae8c73>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext>::link::__l2::<lambda_43ccdd2872e2f97050bf30cf0ba7d0dc>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::framegraph::resource::ExternalTextureSlice<dragon::rendering::RenderContext> *const` | __this
8 | (8) `dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *` | context


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::drawutils::BlitDescription const &>::_createSingleRenderPass::__l2::<lambda_77bd270865ad9859855c2dc765424b58>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::drawutils::BlitDescription const &)>` | callback
216 | (152) `std::tuple<dragon::rendering::details::MaterialBind const ,dragon::rendering::details::MaterialBind const ,dragon::rendering::drawutils::BlitDescription const >` | deps
368 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::materials::MaterialUniformOverrides const &,__int64 &,__int64 &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView &>::_createSingleRenderPass::__l2::<lambda_95a4a2f41b597f9111b8177b680064d9>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::materials::MaterialUniformOverrides const &,__int64 const &,__int64 const &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView const &)>` | callback
216 | (120) `std::tuple<dragon::materials::MaterialUniformOverrides const ,__int64,__int64,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView>` | deps
336 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::materials::MaterialUniformOverrides const &,__int64 &,__int64 &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView &,dragon::rendering::details::MaterialBind &>::_createSingleRenderPass::__l2::<lambda_65ffed367918506be5ee55b8e6fd39c1>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::materials::MaterialUniformOverrides const &,__int64 const &,__int64 const &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (152) `std::tuple<dragon::materials::MaterialUniformOverrides const ,__int64,__int64,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView,dragon::rendering::details::MaterialBind>` | deps
368 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::materials::MaterialUniformOverrides const &,__int64 &,__int64 &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView &,dragon::rendering::details::MaterialBind &>::_createSingleRenderPass::__l2::<lambda_adbddacd40dc71f22505d4704e8182a2>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::materials::MaterialUniformOverrides const &,__int64 const &,__int64 const &,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (152) `std::tuple<dragon::materials::MaterialUniformOverrides const ,__int64,__int64,dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView,dragon::rendering::details::MaterialBind>` | deps
368 | (32) `const std::string` | name


### `dragon::UpdateVertexOnlyAccelerationStructureTransaction`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::ServerResourcePointer<mce::ResourcePointer<dragon::mesh::ResolvedVertexBufferResource,mce::ResourceBlockTemplate<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>` | mVertexBuffer
16 | (4) `unsigned int` | mVertexCount
20 | (2) `_BYTE[2]` | mBuildFlags


### `dragon::rendering::details::ProcessingPassCreator<`dragon::rendering::modules::rayTrace'::`2'::TransientData,dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > > >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> >` | baseclass_0
16 | (24) `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > >` | baseclass_10


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (16) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > >` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,`dragon::rendering::modules::rayTrace'::`2'::TransientData &,dragon::frameobject::SceneLightingInformation const &>::createProcessingPass::__l2::<lambda_d75a707727f1fc9f38b25c8d1f5cd128>`
Offset | Type | Name
-|-|-|-
0 | (120) `std::tuple<`dragon::rendering::modules::rayTrace'::`2'::TransientData,dragon::frameobject::SceneLightingInformation const >` | deps
120 | (64) `std::function<`dragon::rendering::modules::rayTrace'::`2'::TransientData __cdecl(`dragon::rendering::modules::rayTrace'::`2'::TransientData const &,dragon::frameobject::SceneLightingInformation const &)>` | callback
184 | (32) `const std::string` | name


### `dragon::frameobject::SceneLightingInformation`
Offset | Type | Name
-|-|-|-
0 | (36) `dragon::frameobject::SceneLightingInformation::DirectionalLight` | mPrimaryDirectionalLight
36 | (16) `dragon::frameobject::SceneLightingInformation::AmbientLight` | mPrimaryAmbientLight
56 | (32) `std::vector<dragon::frameobject::SceneLightingInformation::PointLight,Core::CpuRingBufferAllocator<dragon::frameobject::SceneLightingInformation::PointLight,2,0,Core::CheckedRingBuffer<2,0> > >` | mPointLights


### `dragon::frameobject::SceneLightingInformation::DirectionalLight`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mWorldSpaceDirection
12 | (12) `glm::tvec3<float,0>` | mColor
24 | (4) `float` | mIntensity
28 | (8) `std::optional<enum dragon::frameobject::ShadowQuality>` | mCastsShadows


### `dragon::frameobject::SceneLightingInformation::AmbientLight`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | mColor
12 | (4) `float` | mIntensity


### `dragon::rendering::modules::rayTrace::__l2::TransientData`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int *` | mHistogramBins
8 | (8) `bgfx::RtLightInfo *` | mLights
16 | (8) `unsigned __int64` | mPointLightsCount
24 | (8) `const dragon::rendering::RayTracingResources *` | mRtResources


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtractTopLevelAccelerationStructure::__l2::<lambda_cdec317e83d6ef50f264defd607a49a9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (32) `std::tuple<dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_f1a4fd1f20796f0b2412f5d039c39cb9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_dbc70ffa1730cdb8c99415f70a402f0b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_1a3eb5a7e770a6aeb67c2a9daf33bdc0>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_9db981ba13cc9b175e91521cf5cfa3fc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_bb86887b570920c2cd21c74d77e978b3>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_dd11e0d8d1dfc894b45259957c6b6ec6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_00cc64556b892db5ead197d5a9d88f95>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_8b8fc639e7e190fdb145fe21aae0e644>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_748aec194ac8c90d1227dcba610747d9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_505fe6f25c921254c23959754ce782a5>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_b62e04ec1ca2873a6d5e9d931a732e37>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_2321dcc5b4beff61984487f001ae2760>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_247e42dfeb361c4959cc0be093ef4d7c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_9acc9f3884b7e67dfe1436ccc221f2f0>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_b6d3d575ff4e9a6a713390b714ee8eb3>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_1fe8933a47404a5b3911f079a02fc11a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_8e27cb59fdff0528a480339a2979b089>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_a7279288c9b57476b6b681108343d396>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_6872470c3f076519393072e6759fef4f>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_cfb621c5b75a40601b415180be10edcd>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_c630e977d9f6b82521a071066c0146f1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::drawutils::Generic<dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> >::prepareExtract::__l2::<lambda_a1e21d46526d2e0301905daeb11e3e9d>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> *` | frame
8 | (280) `const dragon::rendering::Camera` | camera
288 | (4) `const dragon::rendering::drawutils::SortMode` | sortMode
296 | (24) `dragon::rendering::ViewSet` | viewSets


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_e810db29fd69a54c0243a1ab41516837>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::Camera *` | camera


### `dragon::frameobject::ScenePrepareSystem::PrepareTransparent::__l2::<lambda_ee480d4359bf3cd22a745f5ffe7da5b6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::frameobject::components::Transform::getFirstTransform::__l2::Visitor`
Offset | Type | Name
-|-|-|-


### `dragon::rendering::GraphicsFrame::renderPass::__l2::<lambda_9f1ed3b98162420885d690d6d90c190c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::details::RenderPassImpl<1,0> >` | pass
16 | (148) `const dragon::rendering::ViewDescription` | viewDesc
168 | (24) `const std::array<dragon::rendering::details::ColorBind,0>` | outputs
192 | (16) `const dragon::rendering::details::DepthBind` | depth


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const >::_createSingleRenderPass::__l2::<lambda_fe397353d52a2e6255b4098c73fba212>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> const &,dragon::rendering::drawutils::PassName const &,dragon::materials::MaterialUniformOverrides const &,std::optional<dragon::rendering::PassStateOverride> const &)>` | callback
216 | (248) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<std::optional<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView> > >,dragon::rendering::drawutils::PassName,dragon::materials::MaterialUniformOverrides const ,std::optional<dragon::rendering::PassStateOverride> const >` | deps
464 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > >::_createSingleRenderPass::__l2::<lambda_d9a3e4dea4288f749cc92d5390fbc3bf>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,`dragon::rendering::modules::rayTrace'::`2'::TransientData const &)>` | callback
216 | (16) `std::tuple<std::shared_ptr<dragon::rendering::details::ProcessingPassImpl<`dragon::rendering::modules::rayTrace'::`2'::TransientData> > >` | deps
232 | (32) `const std::string` | name


### `dragon::frameobject::ScenePrepareSystem::PrepareTLAS::__l2::<lambda_3fdf73b5f3db9928ddc8019ad221cda8>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::ViewSet *` | sets


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::MaterialBind &>::_createSingleRenderPass::__l2::<lambda_cd0d70a94b38823da07ba7c1ff79a0eb>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (32) `std::tuple<dragon::rendering::details::MaterialBind>` | deps
248 | (32) `const std::string` | name


### `dragon::platform::_transformSurfaceParameters::__l2::SurfaceParameterTransform`
Offset | Type | Name
-|-|-|-
0 | (4) `bgfx::RendererType::Enum` | mRendererType


### `dragon::res::CreateTextureTransaction`
Offset | Type | Name
-|-|-|-
0 | (112) `dragon::res::TextureDescription` | mTextureDescription
112 | (24) `std::vector<cg::ImageBuffer>` | mImageBuffers


### `dragon::res::TextureDescription`
Offset | Type | Name
-|-|-|-
0 | (72) `cg::TextureDescription` | baseclass_0
72 | (32) `std::string` | mIdentifier
104 | (4) `dragon::TextureUsage` | mUsage


### `dragon::TextureUsage`
Offset | Type | Name
-|-|-|-
0 | (4) `std::bitset<4>` | baseclass_0


### `dragon::frameobject::FrameRendererResources`
Offset | Type | Name
-|-|-|-
0 | (1) `dragon::rendering::ClipSpaceDepthMode` | mClipSpaceMode
8 | (56) `dragon::mesh::Mesh` | mScreenQuad


### `dragon::result::Result<dragon::res::TextureRead,enum dragon::res::TextureError>`
Offset | Type | Name
-|-|-|-
0 | (104) `std::variant<dragon::res::TextureRead,enum dragon::res::TextureError>` | mValue


### `dragon::res::TextureRead`
Offset | Type | Name
-|-|-|-
0 | (88) `cg::ImageBuffer` | mImage
88 | (8) `unsigned __int64` | mReadyFrame


### `dragon::res::WrapApiTextureTransaction`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE[1]` | mRendererType
8 | (112) `dragon::res::TextureDescription` | mDescription
120 | (8) `void *` | mExternalTexture


### `dragon::res::ResolvedTextureResource`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::TextureHandle` | mTextureHandle
8 | (112) `dragon::res::TextureDescription` | mTextureDescription
120 | (36) `std::optional<cg::TextureMetaData>` | mTextureMetaData
160 | (16) `mpmc::Sender<std::function<void __cdecl(void)> >` | mDestructionQueue


### `dragon::platform::helpers::VisitOverloaded<<lambda_fbe26c8e4f7c9bae2f810aaf7646b609>,<lambda_4669a033a94b2cbc882de43740c3bcf3> >`
Offset | Type | Name
-|-|-|-
0 | (1) `_BYTE` | gap0


### `dragon::res::CreateCubemapTransaction`
Offset | Type | Name
-|-|-|-
0 | (96) `std::array<dragon::res::ServerTexture,6>` | mTextures


### `DefinitionTrigger`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mType
32 | (2) `_BYTE[2]` | mTarget
40 | (64) `ActorFilterGroup` | mFilter
104 | (216) `ExpressionNode` | mCondition


### `DefinitionEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mProbability
8 | (64) `ActorFilterGroup` | mFilter
72 | (216) `ExpressionNode` | mCondition
288 | (32) `std::string` | mName
320 | (4) `_BYTE[4]` | mType
328 | (24) `std::vector<std::string>` | mGroups
352 | (24) `std::vector<std::string>` | mRemoveGroups
376 | (320) `DefinitionTrigger` | mTrigger
696 | (24) `std::vector<DefinitionEvent>` | mChildren
720 | (24) `EventResponseCollection` | mResponses


### `DiggerItemComponent::buildNetworkTag::__l2::<lambda_f361346fda0e42e8ad899f6341ebf194>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ListTag> *` | blockInfoTag


### `DeserializedChunkLoadedRequest`
Offset | Type | Name
-|-|-|-
0 | (128) `ChunkLoadedRequest` | mChunkLoadedRequest
128 | (1) `ChunkRequestListType` | mChunkRequestListType


### `DistanceConstraint`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mConstraintMass
4 | (12) `Vec3` | mConstraintAxis
16 | (4) `float` | mBias
20 | (1) `bool` | mShouldEnforce
24 | (4) `float` | mMassA
28 | (4) `float` | mMassB
32 | (4) `float` | mDesiredDistance


### `DespawnSystem::tick::__l2::<lambda_bb839350a950a62221858e3a5609afb5>`
Offset | Type | Name
-|-|-|-
0 | (8) `DespawnSystem *const` | __this


### `DebugInfoComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorEventListener` | baseclass_0
8 | (24) `std::vector<DebugInfoComponent::Listener>` | mListeners
32 | (64) `std::unordered_map<HashedString,unsigned __int64>` | mPacketHashes
96 | (40) `std::deque<std::string>` | mSentEvents
136 | (1) `bool` | mEventListenerRegistered
144 | (8) `ActorUniqueID` | mMobUniqueId


### `DoubleTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (8) `long double` | data


### `DebugUdpProxy::Verdict`
Offset | Type | Name
-|-|-|-
0 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mDelayedUntil
8 | (1) `bool` | mIsDropped


### `DurabilityDataEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | minDurability
4 | (4) `int` | maxDurability
8 | (32) `std::string` | recipeId


### `DenyList::Entry`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mUuid
16 | (32) `std::string` | mXuid
48 | (32) `std::string` | mBlockedMessage
80 | (4) `DenyList::Duration` | mDuration


### `DirectoryPackSource::load::__l5::<lambda_28c626212524a01ef0d292d1f3c91ecf>`
Offset | Type | Name
-|-|-|-
0 | (8) `DirectoryPackSource *const` | __this
8 | (8) `PackManifestFactory *` | manifestFactory
16 | (8) `const IContentKeyProvider *` | keyProvider
24 | (8) `PackSourceReport *` | result
32 | (8) `bool *` | isRediscovering
40 | (8) `std::vector<bool> *` | touchedPacks
48 | (8) `int *` | addedPacks


### `DamageSensorDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<DamageSensorTrigger>` | mTriggers


### `DamageSensorComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDamageAmount
4 | (1) `bool` | mDamageIsFatal
8 | (4) `int` | mDamageCause
16 | (24) `std::vector<DamageSensorTrigger>` | mTriggers
40 | (4) `float` | mDamageMultipler
44 | (4) `float` | mDamageModifier


### `DefintionDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `DefintionDescription_vtbl *` | __vftable


### `DefinitionInstanceGroup`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<IDefinitionInstance>>` | mDefinitionList
24 | (64) `std::unordered_map<std::string,std::shared_ptr<IDefinitionInstance>>` | mDefinitionMap
88 | (64) `std::unordered_map<unsigned short,std::string>` | mTypeIdToDefinitionName


### `DwellerComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mCanFindPOI
1 | (1) `bool` | mCanMigrate
2 | (1) `bool` | mHasJoinedDwelling
3 | (1) `bool` | mFixUpRole
4 | (1) `bool` | mRewardPlayersOnFirstFounding
8 | (48) `HashedString` | mPreferredProfession
56 | (4) `int` | mFirstFoundingReward
60 | (4) `int` | mUpdateIntervalVariant
64 | (8) `unsigned __int64` | mDwellingUpdateInterval
72 | (8) `unsigned __int64` | mUpdateIntervalBase
80 | (4) `float` | mDwellingBoundsTolerance
84 | (4) `DwellerComponent::DwellingType` | mType
88 | (4) `DwellerRole` | mRole
96 | (16) `mce::UUID` | mDwellingUniqueID


### `DataLoadHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `DataLoadHelper_vtbl *` | __vftable


### `DefinitionModifier`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mAddGroups
24 | (24) `std::vector<std::string>` | mRemoveGroups
48 | (24) `std::vector<DefinitionTrigger>` | mTriggers
72 | (24) `std::vector<EventResponse const *>` | mResponses


### `DimensionHeightRange`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mMin
2 | (2) `__int16` | mMax


### `DBStorage::_queueSaveCallback::__l13::<lambda_4b7d8b81183841cc2eb6a4dbcb326c74>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(void)>` | saveCallback


### `DBStorage::PendingWriteResult`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::string const >` | mLatestValue
16 | (1) `bool` | mIsDeleted


### `DBStorage::_suspendAndPerformSaveAction::__l2::<lambda_b50680963ccf0981bcc7927f3779c9ad>`
Offset | Type | Name
-|-|-|-
0 | (8) `DBStorage *const` | __this
8 | (64) `std::function<TaskResult __cdecl(void)>` | action
72 | (8) `DBStorage::DBStorageToken` | token


### `DBStorage::DBStorageToken`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<int> *` | mRefCounter


### `DisplayObjective`
Offset | Type | Name
-|-|-|-
0 | (8) `const Objective *` | mObjective
8 | (1) `_BYTE[1]` | mSortOrder


### `Downloader::ProgressData`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Downloader>` | downloader
16 | (32) `std::string` | customId
48 | (32) `std::string` | url
80 | (32) `std::string` | path
112 | (32) `std::string` | name
144 | (8) `long double` | downloaded
152 | (8) `long double` | totalToDownload


### `Downloader::notifyError::__l2::<lambda_87a318d39a70699bf12a1da8feeba66d>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Downloader>` | ptr
16 | (4) `Downloader::ErrorCode` | code
20 | (4) `int` | curle_code
24 | (4) `int` | curlm_code
32 | (32) `const std::string` | msg
64 | (32) `const std::string` | customId


### `Downloader::FileDescriptor`
Offset | Type | Name
-|-|-|-
0 | (8) `_iobuf *` | fp
8 | (8) `void *` | curl


### `Downloader::download::__l13::<lambda_4747c02da55263ea937882d69ff931b4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Downloader>` | ptr
16 | (160) `const Downloader::ProgressData` | data


### `Downloader::curlmDownload::__l2::<lambda_850048095cec98720335af25b66fc2c6>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Downloader>` | ptr
16 | (1) `bool` | allSuccess
24 | (24) `std::vector<std::string>` | customIds
48 | (4) `int` | errorCode


### `dragon::rendering::drawcommands::VertexBufferBind`
Offset | Type | Name
-|-|-|-
0 | (2) `const bgfx::VertexDeclHandle` | mVertexDeclHandle
8 | (8) `const bgfx::VertexDecl *` | mDecl
16 | (8) `const dragon::mesh::ResolvedVertexBuffer *` | mVertexBuffer
24 | (112) `std::optional<dragon::mesh::ResolvedVertexBuffer>` | mHandle


### `dragon::mesh::ResolvedVertexBuffer`
Offset | Type | Name
-|-|-|-
0 | (4) `std::variant<bgfx::VertexBufferHandle,bgfx::DynamicVertexBufferHandle>` | mResource
4 | (4) `unsigned int` | mOffset
8 | (4) `unsigned int` | mCount
12 | (2) `bgfx::VertexDeclHandle` | mVertexDeclHandle
16 | (80) `bgfx::VertexDecl` | mVertexDecl
96 | (8) `std::unique_ptr<dragon::mesh::VertexBufferView>` | mStorageView


### `dragon::materials::definition::SamplerDefinition`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mSlot
1 | (1) `dragon::materials::definition::SamplerAccess` | mAccess
2 | (1) `_BYTE[1]` | mPrecision
3 | (1) `bool` | mAllowUnorderedAccess
4 | (1) `dragon::materials::definition::SamplerType` | mType
8 | (32) `std::string` | mFormat
40 | (40) `std::optional<std::string >` | mDefaultTexture
80 | (48) `std::optional<dragon::materials::definition::SamplerDefinition::CustomTypeInfo>` | mCustomType


### `dragon::materials::definition::SamplerDefinition::CustomTypeInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | customType
32 | (4) `unsigned int` | customTypeStride


### `dragon::materials::CompiledMaterialDefinition::Pass`
Offset | Type | Name
-|-|-|-
0 | (1) `dragon::materials::definition::GraphicsProfile` | mGraphicsProfile
8 | (32) `std::string` | mFallback
40 | (24) `std::vector<dragon::materials::CompiledMaterialDefinition::Variant>` | mVariants
64 | (64) `std::unordered_map<std::string,std::string>` | mFlagDefaultValues
128 | (8) `std::optional<enum dragon::materials::definition::BlendMode>` | mDefaultBlendMode


### `dragon::materials::PlatformShaderStage`
Offset | Type | Name
-|-|-|-
0 | (1) `dragon::materials::ShaderCodePlatform` | mPlatform
1 | (1) `dragon::materials::definition::ShaderStage` | mStage


### `dragon::materials::CompiledMaterialDefinition::Variant`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsSupported
8 | (64) `std::unordered_map<std::string,std::string>` | mFlags
72 | (64) `std::unordered_map<dragon::materials::PlatformShaderStage,dragon::materials::CompiledMaterialDefinition::ShaderCode>` | mShaders


### `dragon::materials::CompiledMaterialDefinition::VariantSet`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::materials::CompiledMaterialDefinition *` | mDefinition
8 | (8) `const dragon::materials::CompiledMaterialDefinition::Pass *` | mPass
16 | (24) `std::vector<dragon::materials::CompiledMaterialDefinition::Variant const *>` | mVariants
40 | (64) `const std::unordered_map<std::string,std::string>` | mDefaultFlagValues
104 | (64) `const std::unordered_map<std::string,std::string>` | mSetFlags
168 | (8) `const dragon::materials::CompiledMaterialDefinition::Variant *` | mDefaultVariant


### `dragon::platform::GraphicsPlatform`
Offset | Type | Name
-|-|-|-
0 | (1) `dragon::materials::definition::GraphicsProfile` | mGraphicsProfile
1 | (1) `dragon::materials::ShaderCodePlatform` | mShaderPlatform
8 | (32) `std::string` | mChipsetName
40 | (32) `std::string` | mChipsetVendorName
72 | (32) `std::string` | mGraphicsVersion
104 | (8) `glm::tvec2<unsigned int,0>` | mScreenDimensions
112 | (4) `unsigned int` | mVendorId
116 | (4) `unsigned int` | mDeviceId
120 | (4) `unsigned int` | mSubSysId
124 | (4) `unsigned int` | mRevision
128 | (8) `unsigned __int64` | mDedicatedVideoMemory
136 | (8) `unsigned __int64` | mDedicatedSystemMemory
144 | (8) `unsigned __int64` | mSharedSystemMemory
152 | (8) `unsigned __int64` | mReservedVideoMemory


### `dragon::materials::Material::_loadMaterial::__l2::PassFallbackState`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | mFallbackName
8 | (16) `std::shared_ptr<dragon::materials::Pass>` | mConstructedPass


### `dragon::materials::MaterialRepositoryIndex`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,dragon::materials::MaterialRepositoryIndex::Entry>` | mEntries


### `dragon::materials::MaterialResourceManager::_tryCreateMaterialAsync::__l19::<lambda_fd5d73d1c5bdaee312c98709dbed648d>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialResourceManager *const` | __this
8 | (56) `const dragon::materials::MaterialLocation` | location
64 | (16) `std::shared_ptr<dragon::materials::MaterialResourceManager::MaterialLoadResult>` | workResult


### `dragon::materials::MaterialResourceManager::MaterialLoadResult`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mResolvedMaterialPath
32 | (8) `std::unique_ptr<dragon::materials::CompiledMaterialDefinition>` | mCompiledMaterial


### `dragon::materials::MaterialUniform::UniformParameter`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::materials::MaterialUniform *` | mParameter
8 | (2) `unsigned __int16` | mValueOffset
10 | (2) `unsigned __int16` | mValueSize


### `dragon::platform::helpers::VisitOverloaded<<lambda_d3c53adb5163b2dc6cb38e1389232b1d>,<lambda_a0db3f8e29018abb09c3341a0b51529b>,<lambda_d8356658306be6d9f3e48f29ec2d9e03> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_a0db3f8e29018abb09c3341a0b51529b>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_d8356658306be6d9f3e48f29ec2d9e03>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_a0db3f8e29018abb09c3341a0b51529b>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexBufferType::create::__l8::<lambda_e47c005c7d6b9976d725fa3856b3c219> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_d8356658306be6d9f3e48f29ec2d9e03>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexBufferType::create::__l8::<lambda_e47c005c7d6b9976d725fa3856b3c219> *` | callback


### `dragon::platform::helpers::VisitOverloaded<<lambda_fbf8f11091c1cfcec0d531bce112a61e>,<lambda_b39af3e4f2db86d7c3a3a9d7b03c4313>,<lambda_3dba1a0e50b0932b071a896977e9343c> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_b39af3e4f2db86d7c3a3a9d7b03c4313>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_3dba1a0e50b0932b071a896977e9343c>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_b39af3e4f2db86d7c3a3a9d7b03c4313>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexBufferType::create::__l12::<lambda_b7dfe6184cc14514f6c43d7b49641c2d> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_3dba1a0e50b0932b071a896977e9343c>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexBufferType::create::__l12::<lambda_b7dfe6184cc14514f6c43d7b49641c2d> *` | callback


### `dragon::rendering::details::BufferHandleTypeWrapper<dragon::rendering::details::TextureHandleTypeKey,unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mValue


### `dragon::platform::helpers::VisitOverloaded<<lambda_626d90e41a069a68169eeda6a9f217ad> >`
Offset | Type | Name
-|-|-|-


### `dragon::CreateVertexOnlyAccelerationStructureTransaction::apply::__l8::<lambda_626d90e41a069a68169eeda6a9f217ad>`
Offset | Type | Name
-|-|-|-


### `dragon::mesh::IndexBufferType::ResourceCreationParameters`
Offset | Type | Name
-|-|-|-
0 | (1) `dragon::mesh::IndexSize` | mIndexSize
1 | (1) `bool` | mIsDynamic
8 | (8) `unsigned __int64` | mSizeInBytes
16 | (56) `std::optional<dragon::memory::BufferSource>` | mInitialData
72 | (2) `unsigned __int16` | mFlags


### `dragon::memory::BufferSource`
Offset | Type | Name
-|-|-|-
0 | (40) `std::variant<std::monostate,std::shared_ptr<std::vector<unsigned char> const >,std::pair<gsl::span<unsigned char const ,-1>,std::weak_ptr<dragon::memory::BufferSource::LifetimeToken> > >` | mData
40 | (8) `unsigned __int64` | mSize


### `dragon::platform::helpers::VisitOverloaded<<lambda_08cf54ea2da37cd267dd894e7acde7af>,<lambda_e9898cbdfbfe337f07f9a022cd2533b8> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexBufferType::update::__l2::<lambda_08cf54ea2da37cd267dd894e7acde7af>` | baseclass_0


### `dragon::mesh::IndexBufferType::update::__l2::<lambda_08cf54ea2da37cd267dd894e7acde7af>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::IndexBufferType::ResourceUpdateParameters *` | updateParameters


### `dragon::mesh::IndexBufferType::update::__l2::<lambda_e9898cbdfbfe337f07f9a022cd2533b8>`
Offset | Type | Name
-|-|-|-


### `dragon::mesh::IndexBufferType::destroy::__l2::<lambda_b41843360f86d6463d5290166c37ba81>`
Offset | Type | Name
-|-|-|-


### `dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >` | mBuffer
16 | (4) `unsigned int` | mOffset
20 | (4) `unsigned int` | mSize


### `dragon::platform::helpers::VisitOverloaded<<lambda_838ec8792ec8f28cdf0b6e20dc2dccfb>,<lambda_80a8cb8142b6085bcd924e87e95f1e07>,<lambda_2d5e904666ae2f1560ea914ee31e16ce> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_80a8cb8142b6085bcd924e87e95f1e07>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_2d5e904666ae2f1560ea914ee31e16ce>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_80a8cb8142b6085bcd924e87e95f1e07>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::create::__l8::<lambda_98fb0b014d7bc1522a65b9d9e52e128c> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_2d5e904666ae2f1560ea914ee31e16ce>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::create::__l8::<lambda_98fb0b014d7bc1522a65b9d9e52e128c> *` | callback


### `dragon::platform::helpers::VisitOverloaded<<lambda_97d926c5e853868c401c51db34c77980>,<lambda_19704ddaed9e069227898e5ca9d1d801>,<lambda_e38ecc87e5dddf41ee46693aebabe505> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_19704ddaed9e069227898e5ca9d1d801>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_e38ecc87e5dddf41ee46693aebabe505>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_19704ddaed9e069227898e5ca9d1d801>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::create::__l12::<lambda_fc397e945a4de1d8f2f7561c51f6c5f5> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_e38ecc87e5dddf41ee46693aebabe505>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::create::__l12::<lambda_fc397e945a4de1d8f2f7561c51f6c5f5> *` | callback


### `dragon::mesh::VertexBufferDescription`
Offset | Type | Name
-|-|-|-
0 | (176) `dragon::mesh::VertexFormat` | mFormat
176 | (8) `unsigned __int64` | mStride
184 | (4) `std::optional<unsigned short>` | mFormatHandle
192 | (8) `unsigned __int64` | mDataSize
200 | (8) `unsigned __int64` | mVertexCount
208 | (2) `unsigned __int16` | mFlags


### `dragon::mesh::VertexBufferType::ResourceCreationParameters`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsDynamic
8 | (176) `dragon::mesh::VertexFormat` | mFormat
184 | (4) `std::optional<unsigned short>` | mFormatHandle
188 | (2) `bgfx::VertexDeclHandle` | mVertexDeclHandle
192 | (80) `bgfx::VertexDecl` | mVertexDecl
272 | (8) `unsigned __int64` | mSizeInBytes
280 | (56) `std::optional<dragon::memory::BufferSource>` | mInitialData
336 | (2) `unsigned __int16` | mFlags


### `dragon::platform::helpers::VisitOverloaded<<lambda_40fff7d480dea1c0478fd3f43504e31a>,<lambda_365c258b847d71589ba2a1cd689d60a8> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>` | baseclass_0


### `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::variant<dragon::mesh::VertexBufferType::ItemResourceUpdateParameters,dragon::mesh::A0xd4a888ee::VertexBufferType::OffsetResourceUpdateParameters> *` | updateParameters


### `dragon::mesh::VertexBufferType::update::__l2::<lambda_365c258b847d71589ba2a1cd689d60a8>`
Offset | Type | Name
-|-|-|-


### `dragon::mesh::VertexBufferType::ItemResourceUpdateParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mStartIndex
8 | (48) `dragon::memory::BufferSource` | mUpdateData


### `dragon::mesh::VertexBufferType::OffsetResourceUpdateParameters`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mOffset
4 | (2) `unsigned __int16` | mStride
8 | (48) `dragon::memory::BufferSource` | mUpdateData


### `dragon::platform::helpers::VisitOverloaded<<lambda_959750e4c9ef93d18ac58f647170ba0c>,<lambda_056c755a608f3fa91ffb88d1fe572769> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>::()::__l2::<lambda_959750e4c9ef93d18ac58f647170ba0c>` | baseclass_0
8 | (8) `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>::()::__l2::<lambda_056c755a608f3fa91ffb88d1fe572769>` | baseclass_8


### `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>::()::__l2::<lambda_959750e4c9ef93d18ac58f647170ba0c>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::DynamicVertexBufferHandle *` | buffer


### `dragon::mesh::VertexBufferType::update::__l2::<lambda_40fff7d480dea1c0478fd3f43504e31a>::()::__l2::<lambda_056c755a608f3fa91ffb88d1fe572769>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::DynamicVertexBufferHandle *` | buffer


### `dragon::mesh::VertexBufferType::destroy::__l2::<lambda_f6d3c002ba1e181a707d7a9a4c8d4dfd>`
Offset | Type | Name
-|-|-|-


### `dragon::guarded::GuardedAccess<std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout,std::hash<unsigned int>,std::equal_to<unsigned int>,std::allocator<std::pair<unsigned int const ,dragon::mesh::VertexDeclManager::Impl::DeclLayout> > >,std::shared_mutex,std::shared_lock>`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout> *` | mAccess
8 | (16) `std::shared_lock<std::shared_mutex>` | mGuard


### `dragon::mesh::VertexDeclManager::Impl::DeclLayout`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::VertexDeclHandle` | mHandle
4 | (80) `bgfx::VertexDecl` | mDecl


### `dragon::mesh::VertexDeclManager::Impl::ValidationKey`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mMaterial
8 | (8) `unsigned __int64` | mPass
16 | (4) `unsigned int` | mVertexDecl


### `dragon::platform::_createQuad::__l2::<lambda_2d628195d5c4ea3479f62462e71f1498>`
Offset | Type | Name
-|-|-|-
0 | (20) `dragon::mesh::MeshDescription` | meshDescription
20 | (112) `const std::array<`dragon::platform::_createQuad'::`2'::QuadVertex,4>` | quadVerts
136 | (176) `dragon::mesh::VertexFormat` | format


### `dragon::platform::_createQuad::__l2::QuadVertex`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,0>` | mPos
16 | (12) `glm::tvec3<float,0>` | mUv


### `dragon::platform::ResourcesManagerConfiguration`
Offset | Type | Name
-|-|-|-
0 | (8) `std::optional<unsigned int>` | mVertexBufferCombinedAllocationPageSize
8 | (8) `std::optional<unsigned int>` | mIndexBufferCombinedAllocationPageSize


### `dragon::framegraph::Linker<dragon::rendering::RenderContext,dragon::framegraph::NoLinkerTrace>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::BgfxTexture2DPool *` | mTexturePool
8 | (8) `dragon::rendering::BgfxFrameBufferCache *` | mFramebufferCache
16 | (8) `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > *` | mAllocator


### `dragon::framegraph::detail::ResolveContext<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (16) `gsl::basic_string_span<char const ,-1>` | passName
16 | (4) `std::optional<bgfx::FrameBufferHandle>` | framebufferToBind
24 | (24) `std::vector<dragon::framegraph::detail::ResolvingMaterialTexture<dragon::rendering::RenderContext>>` | materialTexturesToBind


### `dragon::rendering::BgfxFrameBufferCache::Description`
Offset | Type | Name
-|-|-|-
0 | (96) `std::array<bgfx::Attachment,16>` | mColorAttachments
96 | (6) `bgfx::Attachment` | mDepthAttachment


### `dragon::framegraph::detail::ResolvingMaterialTexture<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialUniformName` | name
8 | (16) `dragon::res::ServerTexture` | texture
24 | (4) `unsigned int` | flags


### `dragon::res::ResolvedShaderBufferResource`
Offset | Type | Name
-|-|-|-
0 | (12) `dragon::res::ResolvedShaderBuffer` | baseclass_0


### `dragon::res::ResolvedShaderBuffer`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::ShaderBufferHandle` | mResource
4 | (4) `unsigned int` | mCount
8 | (4) `unsigned int` | mStride


### `dragon::rendering::CommandContext::MaterialTextureBinding`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::materials::MaterialUniformName` | nameHash
8 | (16) `dragon::res::ServerTexture` | textureHandle
24 | (4) `unsigned int` | textureFlags


### `dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::rendering::RenderContext *` | global
8 | (16) `std::shared_ptr<dragon::rendering::CommandContext>` | local


### `dragon::rendering::BgfxPrimitiveIndexBuffer::ensureSize::__l5::<lambda_39df09be4154b1f3855ec67d59c013af>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | mIndices
24 | (8) `dragon::rendering::BgfxPrimitiveIndexBuffer *const` | __this


### `dragon::res::CreatePoolTextureTransaction`
Offset | Type | Name
-|-|-|-
0 | (112) `dragon::res::TextureDescription` | mTextureDescription


### `dragon::rendering::BgfxTexture2DPool::LeasedTextureHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::res::ServerTexture` | mHandle
16 | (1) `bool` | mLeased


### `dragon::platform::helpers::VisitOverloaded<<lambda_6b7fab46896fa255efc95c2fbafc2ae2>,<lambda_d57860972a2cb7418df119bfd8dfb2cd> >`
Offset | Type | Name
-|-|-|-
0 | (48) `dragon::rendering::_applyUniformsAndTextures::__l43::<lambda_d57860972a2cb7418df119bfd8dfb2cd>` | baseclass_0


### `dragon::rendering::_applyUniformsAndTextures::__l43::<lambda_d57860972a2cb7418df119bfd8dfb2cd>`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | valueMustComeFromOverride
8 | (8) `dragon::materials::MaterialUniformName *` | parameterName
16 | (8) `const dragon::materials::definition::ShaderPipeline *` | pipeline
24 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | target
32 | (8) `const dragon::materials::MaterialUniform::TextureParameter *` | textureParameter
40 | (8) `bool *` | isValidState


### `dragon::platform::helpers::VisitOverloaded<<lambda_d515b1e007d244831d97e49ed01d76b8>,<lambda_427379a9307ad90b0c557dae7cdf0cc6>,<lambda_2be803adef4c3b09f09b09eea560ece7> >`
Offset | Type | Name
-|-|-|-
0 | (24) `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_d515b1e007d244831d97e49ed01d76b8>` | baseclass_0
24 | (40) `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_427379a9307ad90b0c557dae7cdf0cc6>` | baseclass_18
64 | (40) `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_2be803adef4c3b09f09b09eea560ece7>` | baseclass_40


### `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_d515b1e007d244831d97e49ed01d76b8>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | target
8 | (8) `const unsigned __int8 *` | slot
16 | (8) `const dragon::materials::MaterialUniform *const *` | parameter


### `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_427379a9307ad90b0c557dae7cdf0cc6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::materials::definition::ShaderPipeline *` | pipeline
8 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | target
16 | (8) `dragon::mesh::VertexBufferResourceManager *` | vbManager
24 | (8) `const unsigned __int8 *` | slot
32 | (8) `const dragon::materials::definition::SamplerAccess *` | access


### `dragon::rendering::_applyUniformsAndTextures::__l47::<lambda_2be803adef4c3b09f09b09eea560ece7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::materials::definition::ShaderPipeline *` | pipeline
8 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | target
16 | (8) `dragon::mesh::IndexBufferResourceManager *` | ibManager
24 | (8) `const unsigned __int8 *` | slot
32 | (8) `const dragon::materials::definition::SamplerAccess *` | access


### `dragon::rendering::_applyBuffer::__l2::<lambda_effa8405b0f2d54c7f90f046d9a71d36>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | encoder
8 | (8) `const int *` | slot
16 | (8) `const std::optional<enum bgfx::Access::Enum> *` | bgfxAccess


### `dragon::rendering::_applyBuffer::__l2::<lambda_3fc2e34c02af7c8fca4936f5107c5b1e>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::GraphicsCommandContext *` | encoder
8 | (8) `const int *` | slot
16 | (8) `const std::optional<enum bgfx::Access::Enum> *` | bgfxAccess


### `dragon::platform::helpers::VisitOverloaded<<lambda_12b1a0ae33466fe2a2564a97983e407c>,<lambda_1b0ee8d220c5c035145e5b27cdda25a3>,<lambda_d58a83712c32c5ec362b86baf793f792> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::_resolveVertexBuffer::__l2::<lambda_1b0ee8d220c5c035145e5b27cdda25a3>` | baseclass_0


### `dragon::rendering::drawcommands::_resolveVertexBuffer::__l2::<lambda_1b0ee8d220c5c035145e5b27cdda25a3>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::platform::ResourcesManager *` | resourcesManager


### `dragon::rendering::drawcommands::_resolveVertexBuffer::__l2::<lambda_d58a83712c32c5ec362b86baf793f792>`
Offset | Type | Name
-|-|-|-


### `dragon::platform::helpers::VisitOverloaded<<lambda_34d5234f01c4d7358ee01b5198c85700>,<lambda_8738462f3d76fb4ba563f00bec0d3e6c> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::drawcommands::bindMeshVertexBuffer::__l2::<lambda_34d5234f01c4d7358ee01b5198c85700>` | baseclass_0
32 | (24) `dragon::rendering::drawcommands::bindMeshVertexBuffer::__l2::<lambda_8738462f3d76fb4ba563f00bec0d3e6c>` | baseclass_20


### `dragon::rendering::drawcommands::bindMeshVertexBuffer::__l2::<lambda_34d5234f01c4d7358ee01b5198c85700>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::Encoder *` | encoder
8 | (8) `const dragon::frameobject::components::MeshFilter *` | meshFilter
16 | (8) `const dragon::mesh::ResolvedVertexBuffer *` | buffer
24 | (8) `std::optional<dragon::rendering::drawcommands::VertexBufferBind> *` | vbBind


### `dragon::rendering::drawcommands::bindMeshVertexBuffer::__l2::<lambda_8738462f3d76fb4ba563f00bec0d3e6c>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::Encoder *` | encoder
8 | (8) `const dragon::frameobject::components::MeshFilter *` | meshFilter
16 | (8) `const dragon::mesh::ResolvedVertexBuffer *` | buffer


### `dragon::rendering::drawcommands::IndexBufferBind`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::ResolvedIndexBuffer *` | mIndexBuffer
8 | (32) `std::optional<dragon::mesh::ResolvedIndexBuffer>` | mHandle


### `dragon::mesh::ResolvedIndexBuffer`
Offset | Type | Name
-|-|-|-
0 | (4) `std::variant<bgfx::IndexBufferHandle,bgfx::DynamicIndexBufferHandle>` | mResource
4 | (4) `unsigned int` | mOffset
8 | (4) `unsigned int` | mCount
12 | (1) `dragon::mesh::IndexSize` | mIndexSize
16 | (8) `std::unique_ptr<dragon::mesh::IndexBufferView>` | mStorageView


### `dragon::platform::helpers::VisitOverloaded<<lambda_040c469f11856dccdc394d032338fec6>,<lambda_0ba5a7d4b31cfc68acfa4d697cbae264>,<lambda_e9436f7b22c21ee4b8e756d8be3b14bf> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::_resolveIndexBuffer::__l2::<lambda_0ba5a7d4b31cfc68acfa4d697cbae264>` | baseclass_0


### `dragon::rendering::drawcommands::_resolveIndexBuffer::__l2::<lambda_0ba5a7d4b31cfc68acfa4d697cbae264>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::platform::ResourcesManager *` | resourcesManager


### `dragon::rendering::drawcommands::_resolveIndexBuffer::__l2::<lambda_e9436f7b22c21ee4b8e756d8be3b14bf>`
Offset | Type | Name
-|-|-|-


### `dragon::rendering::drawcommands::bindMeshIndexBuffer::__l2::<lambda_263a02d53d306df5e0a7eca2d142f9f6>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::Encoder *` | encoder
8 | (8) `const dragon::frameobject::components::MeshFilter *` | meshFilter
16 | (8) `const unsigned int *` | indexNumOffset


### `dragon::platform::helpers::VisitOverloaded<<lambda_27a9c16cbd5d7146e496bcd9e758037e>,<lambda_675661a5acec4240821ebf9cc8dc9ea1> >`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::drawcommands::bindUniforms::__l17::<lambda_27a9c16cbd5d7146e496bcd9e758037e>` | baseclass_0
16 | (16) `dragon::rendering::drawcommands::bindUniforms::__l17::<lambda_675661a5acec4240821ebf9cc8dc9ea1>` | baseclass_10


### `dragon::rendering::drawcommands::bindUniforms::__l17::<lambda_27a9c16cbd5d7146e496bcd9e758037e>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::Encoder *` | encoder
8 | (8) `const dragon::rendering::drawcommands::BufferBinding *` | buffer


### `dragon::rendering::drawcommands::bindUniforms::__l17::<lambda_675661a5acec4240821ebf9cc8dc9ea1>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::Encoder *` | encoder
8 | (8) `const dragon::rendering::drawcommands::BufferBinding *` | buffer


### `dragon::platform::helpers::VisitOverloaded<<lambda_d9b5a7aeeabfa2df5ce92c0b0204d27c>,<lambda_db154fc97a1aa016fc5c011997c2c269>,<lambda_00994345140f36eea9f6a4188c638770> >`
Offset | Type | Name
-|-|-|-
0 | (40) `dragon::rendering::drawcommands::submit::__l2::<lambda_d9b5a7aeeabfa2df5ce92c0b0204d27c>` | baseclass_0
40 | (40) `dragon::rendering::drawcommands::submit::__l2::<lambda_db154fc97a1aa016fc5c011997c2c269>` | baseclass_28
80 | (40) `dragon::rendering::drawcommands::submit::__l2::<lambda_00994345140f36eea9f6a4188c638770>` | baseclass_50


### `dragon::rendering::drawcommands::submit::__l2::<lambda_d9b5a7aeeabfa2df5ce92c0b0204d27c>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::DrawCommandContext *` | commands
8 | (8) `bool *` | preserveState
16 | (8) `const unsigned __int16 *` | id
24 | (8) `const dragon::materials::Pass *` | pass
32 | (8) `const int *` | depth


### `dragon::rendering::drawcommands::submit::__l2::<lambda_db154fc97a1aa016fc5c011997c2c269>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::DrawCommandContext *` | commands
8 | (8) `bool *` | preserveState
16 | (8) `const unsigned __int16 *` | id
24 | (8) `const dragon::materials::Pass *` | pass
32 | (8) `const int *` | depth


### `dragon::rendering::drawcommands::submit::__l2::<lambda_00994345140f36eea9f6a4188c638770>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::drawcommands::DrawCommandContext *` | commands
8 | (8) `bool *` | preserveState
16 | (8) `const unsigned __int16 *` | id
24 | (8) `const dragon::materials::Pass *` | pass
32 | (8) `const int *` | depth


### `dragon::materials::PassProgramHandle`
Offset | Type | Name
-|-|-|-
0 | (4) `std::optional<unsigned short>` | mHandle
8 | (8) `const dragon::materials::definition::StageInputMap *` | mInputDeclaration


### `dragon::rendering::GraphicsTasks::frame::__l2::<lambda_ce01dea6a319546938933c0ba3ab32c3>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *const` | __this
8 | (64) `const std::function<void __cdecl(void)>` | frameContentCallback


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (24) `std::tuple<dragon::rendering::details::ColorBind>` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (88) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind>::_createSingleRenderPass::__l2::<lambda_5a780548ce7c2e6f378aed9be3986d64>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::ColorBind const &)>` | callback
216 | (24) `std::tuple<dragon::rendering::details::ColorBind>` | deps
240 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (56) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind>::_createSingleRenderPass::__l2::<lambda_ac83b85472f0390318ae584c01eb3d04>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::ColorBind const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (56) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind>` | deps
272 | (32) `const std::string` | name


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsFrame *` | mGraph
8 | (120) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>` | mDeps


### `dragon::rendering::details::TaskCreator<dragon::rendering::GraphicsFrame,dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>::_createSingleRenderPass::__l2::<lambda_135e935318537d70f077fdc7dfad0424>`
Offset | Type | Name
-|-|-|-
0 | (148) `const dragon::rendering::ViewDescription` | viewDesc
152 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::ViewDescription const &,dragon::rendering::details::ColorBind const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::MaterialBind const &,dragon::rendering::details::MaterialBind const &)>` | callback
216 | (120) `std::tuple<dragon::rendering::details::ColorBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind,dragon::rendering::details::MaterialBind>` | deps
336 | (32) `const std::string` | name


### `dragon::platform::helpers::VisitOverloaded<<lambda_15e28bd6d8adc8970663389fbec0ea91>,<lambda_079e70e84ce19ba31462476cc36e31ac>,<lambda_88478167f9d20b8528ae1901b96098f2> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_079e70e84ce19ba31462476cc36e31ac>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_88478167f9d20b8528ae1901b96098f2>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_079e70e84ce19ba31462476cc36e31ac>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceType::create::__l32::<lambda_1a1126684490dea2688199c650391340> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_88478167f9d20b8528ae1901b96098f2>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceType::create::__l32::<lambda_1a1126684490dea2688199c650391340> *` | callback


### `dragon::rendering::BgfxTextureDesc`
Offset | Type | Name
-|-|-|-
0 | (72) `cg::TextureDescription` | mDesc
72 | (4) `_BYTE[4]` | mFormat
76 | (4) `unsigned int` | mFlags


### `dragon::rendering::TextureResourceManager::Impl::getInternalAsync::__l2::<lambda_c2f36c41a6f8b939cf03ff8a0cc2efce>`
Offset | Type | Name
-|-|-|-
0 | (16) `const std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::rendering::details::TextureHandleTypeKey,unsigned __int64> >` | srcHandle
16 | (16) `std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource>` | resourcePtr


### `dragon::rendering::TextureResourceManager::Impl::overrideInternalAsync::__l2::<lambda_f6804d13e6c1f399c569beed1d3a6cb8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource>` | resourcePtr


### `dragon::rendering::DeferredResult<bool>::then::__l2::<lambda_c3545776d4a1357cc987df9697644608>`
Offset | Type | Name
-|-|-|-
0 | (32) `const dragon::rendering::TextureResourceManager::createFromExternal::__l21::<lambda_45f4f6ab2b7d63b66d1d9b2346a37dfb>` | coroutineCallback
32 | (16) `dragon::rendering::DeferredResult<bool>` | dependency


### `dragon::rendering::TextureResourceManager::createFromExternal::__l21::<lambda_45f4f6ab2b7d63b66d1d9b2346a37dfb>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *const` | __this
8 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::rendering::details::TextureHandleTypeKey,unsigned __int64> >` | baseTexture
24 | (8) `unsigned __int64` | nativePlatformPtr


### `dragon::rendering::DeferredResult<bool>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | mImpl


### `dragon::rendering::coroutine::when::__l2::<lambda_43bb4ffe9e3a22cb4498ae83c4961d8c>`
Offset | Type | Name
-|-|-|-
0 | (16) `dragon::rendering::DeferredResult<dragon::rendering::SharedTextureHandle>` | dependency
16 | (16) `const dragon::rendering::TextureResourceManager::updateFromExternal::__l2::<lambda_ffbad76e72915ec6432f861e3a3851e5>` | coroutine


### `dragon::rendering::TextureResourceManager::updateFromExternal::__l2::<lambda_ffbad76e72915ec6432f861e3a3851e5>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *const` | __this
8 | (8) `unsigned __int64` | nativePlatformPtr


### `dragon::rendering::TextureResourceManager::createAsExternal::__l12::<lambda_b09ac5df02a6a00a8bfe64931c430cce>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *const` | __this
8 | (72) `const cg::TextureDescription` | textureDescription
80 | (4) `const unsigned int` | bgfxFlags


### `dragon::rendering::DeferredResult<unsigned __int64>::then::__l2::<lambda_e7b38f5f36d64d4501f5714de64d6730>`
Offset | Type | Name
-|-|-|-
0 | (24) `const dragon::rendering::TextureResourceManager::createAsExternal::__l19::<lambda_c295bf717af6e2394176e734e3e9c5ba>` | coroutineCallback
24 | (16) `dragon::rendering::DeferredResult<unsigned __int64>` | dependency


### `dragon::rendering::TextureResourceManager::createAsExternal::__l19::<lambda_c295bf717af6e2394176e734e3e9c5ba>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceManager *const` | __this
8 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::rendering::details::TextureHandleTypeKey,unsigned __int64> >` | baseTexture


### `dragon::rendering::DeferredResult<unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | mImpl


### `dragon::rendering::ResolvedTextureHandle`
Offset | Type | Name
-|-|-|-
0 | (2) `bgfx::TextureHandle` | mHandle
8 | (80) `dragon::rendering::TextureResourceDesc` | mDesc
88 | (1) `bool` | mIsMissingTexture


### `dragon::rendering::TextureResourceDesc`
Offset | Type | Name
-|-|-|-
0 | (72) `cg::TextureDescription` | mDesc
72 | (4) `unsigned int` | mFlags
76 | (1) `bool` | mIsExternal


### `dragon::platform::helpers::VisitOverloaded<<lambda_5e2cafae2a141aba0edbd603236f9af1>,<lambda_92c73a15d9274b0d1a248d9abf51511c>,<lambda_b50f500f91a20b4751ce5c2e073e265f> >`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_92c73a15d9274b0d1a248d9abf51511c>` | baseclass_0
8 | (8) `dragon::memory::BufferSource::resolve::__l2::<lambda_b50f500f91a20b4751ce5c2e073e265f>` | baseclass_8


### `dragon::memory::BufferSource::resolve::__l2::<lambda_92c73a15d9274b0d1a248d9abf51511c>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceType::update::__l2::<lambda_aeb698e76d03013a75a21854b6e155b4> *` | callback


### `dragon::memory::BufferSource::resolve::__l2::<lambda_b50f500f91a20b4751ce5c2e073e265f>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::TextureResourceType::update::__l2::<lambda_aeb698e76d03013a75a21854b6e155b4> *` | callback


### `dragon::rendering::coroutine::dispatch::__l5::<lambda_c201a2385fe8a0ce0eedc2939cd7c6b7>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | stateHolder
24 | (32) `const dragon::rendering::TextureResourceManager::Impl::getInternalAsync::__l2::<lambda_c2f36c41a6f8b939cf03ff8a0cc2efce>` | coroutineCallback


### `dragon::rendering::coroutine::dispatch::__l5::<lambda_d903639098f09a582d86f54cd0aff478>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (88) `const dragon::rendering::TextureResourceManager::createAsExternal::__l12::<lambda_b09ac5df02a6a00a8bfe64931c430cce>` | coroutineCallback


### `dragon::rendering::coroutine::TryAgain`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDummy


### `dragon::rendering::coroutine::Run<unsigned __int64>`
Offset | Type | Name
-|-|-|-
0 | (4) `const dragon::rendering::coroutine::DispatchTarget` | mTarget
8 | (16) `const std::shared_ptr<std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<unsigned __int64>,unsigned __int64> __cdecl(void)> >` | mFunc


### `dragon::platform::helpers::VisitOverloaded<<lambda_578aaec7db733e7f1f2cb901ace77b80>,<lambda_56a057a413dadfdd162cdce03e706fb2>,<lambda_a65032f92358d667ca432c5cf9eea2cc> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_578aaec7db733e7f1f2cb901ace77b80>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_56a057a413dadfdd162cdce03e706fb2>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_a65032f92358d667ca432c5cf9eea2cc>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_578aaec7db733e7f1f2cb901ace77b80>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder
24 | (8) `const dragon::rendering::TextureResourceManager::Impl::getInternalAsync::__l2::<lambda_c2f36c41a6f8b939cf03ff8a0cc2efce> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_56a057a413dadfdd162cdce03e706fb2>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_a65032f92358d667ca432c5cf9eea2cc>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_578aaec7db733e7f1f2cb901ace77b80>::()::__l5::<lambda_809a9b93147a0c13238c2f246c495576>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | stateHolder
24 | (32) `const dragon::rendering::TextureResourceManager::Impl::getInternalAsync::__l2::<lambda_c2f36c41a6f8b939cf03ff8a0cc2efce>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_578aaec7db733e7f1f2cb901ace77b80>::()::__l6::<lambda_46809a2bcf160cf0081fdc62e4f2765b>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | stateHolder
24 | (32) `const dragon::rendering::TextureResourceManager::Impl::getInternalAsync::__l2::<lambda_c2f36c41a6f8b939cf03ff8a0cc2efce>` | coroutineCallback


### `dragon::rendering::coroutine::Run<bool>`
Offset | Type | Name
-|-|-|-
0 | (4) `const dragon::rendering::coroutine::DispatchTarget` | mTarget
8 | (16) `const std::shared_ptr<std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<bool>,bool> __cdecl(void)> >` | mFunc


### `dragon::platform::helpers::VisitOverloaded<<lambda_a569cced27cf5a1cf209a41b43f8456a>,<lambda_c39af1b785cfd9fef232bb63f8916fde>,<lambda_ba29daccb7e572063fdb7a37378f4199> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_a569cced27cf5a1cf209a41b43f8456a>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_c39af1b785cfd9fef232bb63f8916fde>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_ba29daccb7e572063fdb7a37378f4199>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_a569cced27cf5a1cf209a41b43f8456a>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder
24 | (8) `const dragon::rendering::TextureResourceManager::Impl::overrideInternalAsync::__l2::<lambda_f6804d13e6c1f399c569beed1d3a6cb8> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_c39af1b785cfd9fef232bb63f8916fde>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_ba29daccb7e572063fdb7a37378f4199>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder


### `dragon::rendering::coroutine::dispatch::__l6::<lambda_6850fb333f12c27cd59a9034a301f95b>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (48) `const dragon::rendering::DeferredResult<bool>::then::__l2::<lambda_c3545776d4a1357cc987df9697644608>` | coroutineCallback


### `dragon::rendering::coroutine::dispatch::__l6::<lambda_39686f9ee391368a5f5799abea2a52b2>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | stateHolder
24 | (32) `const dragon::rendering::coroutine::when::__l2::<lambda_43bb4ffe9e3a22cb4498ae83c4961d8c>` | coroutineCallback


### `dragon::platform::helpers::VisitOverloaded<<lambda_85541cfa69e92eff3e45ee81a3f9b30c>,<lambda_0d771b36c68787c1e72511b5fa13c6d0>,<lambda_ce47d89f9332f141d9aa4a6e46498bd9> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_85541cfa69e92eff3e45ee81a3f9b30c>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_0d771b36c68787c1e72511b5fa13c6d0>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_ce47d89f9332f141d9aa4a6e46498bd9>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_85541cfa69e92eff3e45ee81a3f9b30c>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder
24 | (8) `const dragon::rendering::TextureResourceManager::createAsExternal::__l12::<lambda_b09ac5df02a6a00a8bfe64931c430cce> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_0d771b36c68787c1e72511b5fa13c6d0>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_ce47d89f9332f141d9aa4a6e46498bd9>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder


### `dragon::rendering::coroutine::Run<dragon::rendering::SharedTextureHandle>`
Offset | Type | Name
-|-|-|-
0 | (4) `const dragon::rendering::coroutine::DispatchTarget` | mTarget
8 | (16) `const std::shared_ptr<std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<dragon::rendering::SharedTextureHandle>,dragon::rendering::SharedTextureHandle> __cdecl(void)> >` | mFunc


### `dragon::rendering::SharedTextureHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::rendering::details::TextureHandleTypeKey,unsigned __int64> >` | mHandle
16 | (8) `unsigned __int64` | mNativeHandle


### `dragon::rendering::details::runStep::__l2::<lambda_85541cfa69e92eff3e45ee81a3f9b30c>::()::__l5::<lambda_fc5eedfadc0191b386fca01044fdd460>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (88) `const dragon::rendering::TextureResourceManager::createAsExternal::__l12::<lambda_b09ac5df02a6a00a8bfe64931c430cce>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_85541cfa69e92eff3e45ee81a3f9b30c>::()::__l6::<lambda_d284f61578d5079e372603c0661babc1>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (88) `const dragon::rendering::TextureResourceManager::createAsExternal::__l12::<lambda_b09ac5df02a6a00a8bfe64931c430cce>` | coroutineCallback


### `dragon::rendering::coroutine::dispatch::__l6::<lambda_101f7c6729f18b301b9de5099ca81596>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (40) `const dragon::rendering::DeferredResult<unsigned __int64>::then::__l2::<lambda_e7b38f5f36d64d4501f5714de64d6730>` | coroutineCallback


### `dragon::platform::helpers::VisitOverloaded<<lambda_d3a5c939dbee499625fd0911c0353b30>,<lambda_b05b51eb72137a21c2cf1048902f2e5e>,<lambda_1fb6a727bdc84b41650abb7cbf04f9be> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_d3a5c939dbee499625fd0911c0353b30>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_b05b51eb72137a21c2cf1048902f2e5e>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_1fb6a727bdc84b41650abb7cbf04f9be>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_d3a5c939dbee499625fd0911c0353b30>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder
24 | (8) `const dragon::rendering::coroutine::when::__l2::<lambda_43bb4ffe9e3a22cb4498ae83c4961d8c> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_b05b51eb72137a21c2cf1048902f2e5e>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_1fb6a727bdc84b41650abb7cbf04f9be>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_a4713c0cfe5a3b6c52ea9ddde732e47d>::()::__l5::<lambda_992ba4f46045f8240ec29b509f0791ec>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<bool>,bool> __cdecl(void)>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_a4713c0cfe5a3b6c52ea9ddde732e47d>::()::__l6::<lambda_a0654c1ee856b1e582dd2b404878fe3a>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<bool>,bool> __cdecl(void)>` | coroutineCallback


### `dragon::platform::helpers::VisitOverloaded<<lambda_e569e4abc2ad97a8ab2101ce0bebf711>,<lambda_011674cc6bf6055202422059f93cb0b6>,<lambda_20323028200954a01770466e23981c43> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_e569e4abc2ad97a8ab2101ce0bebf711>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_011674cc6bf6055202422059f93cb0b6>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_20323028200954a01770466e23981c43>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_e569e4abc2ad97a8ab2101ce0bebf711>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder
24 | (8) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<unsigned __int64>,unsigned __int64> __cdecl(void)> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_011674cc6bf6055202422059f93cb0b6>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_20323028200954a01770466e23981c43>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_e569e4abc2ad97a8ab2101ce0bebf711>::()::__l5::<lambda_1dce09a17b89e1369d672a4ee4e4e4ab>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<unsigned __int64>,unsigned __int64> __cdecl(void)>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_e569e4abc2ad97a8ab2101ce0bebf711>::()::__l6::<lambda_77a3d5c3ee2698181e0e34fef807fe8d>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,unsigned __int64> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<unsigned __int64>,unsigned __int64> __cdecl(void)>` | coroutineCallback


### `dragon::platform::helpers::VisitOverloaded<<lambda_d00de6bbc43d43a05bdb24eeb5c3e496>,<lambda_432cf39907ff9873ee4e999290412742>,<lambda_231ca9ffa745735704c28be27c81c6e9> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::rendering::details::runStep::__l2::<lambda_d00de6bbc43d43a05bdb24eeb5c3e496>` | baseclass_0
32 | (16) `dragon::rendering::details::runStep::__l2::<lambda_432cf39907ff9873ee4e999290412742>` | baseclass_20
48 | (8) `dragon::rendering::details::runStep::__l2::<lambda_231ca9ffa745735704c28be27c81c6e9>` | baseclass_30


### `dragon::rendering::details::runStep::__l2::<lambda_d00de6bbc43d43a05bdb24eeb5c3e496>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::coroutine::DispatchTarget *` | currentTarget
8 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
16 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder
24 | (8) `const dragon::rendering::DeferredResult<unsigned __int64>::then::__l2::<lambda_e7b38f5f36d64d4501f5714de64d6730> *` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_432cf39907ff9873ee4e999290412742>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_231ca9ffa745735704c28be27c81c6e9>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> > *` | stateHolder


### `dragon::rendering::details::runStep::__l2::<lambda_bc347f2c11c4f4acbd4f8abb87b036b1>::()::__l5::<lambda_395e8f46ee6ae2ec12349456d40ac076>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (48) `const dragon::rendering::DeferredResult<bool>::then::__l2::<lambda_c3545776d4a1357cc987df9697644608>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_bc347f2c11c4f4acbd4f8abb87b036b1>::()::__l6::<lambda_992d042135f52c877b45a2d1c458e6d1>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (48) `const dragon::rendering::DeferredResult<bool>::then::__l2::<lambda_c3545776d4a1357cc987df9697644608>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_d3a5c939dbee499625fd0911c0353b30>::()::__l5::<lambda_9abf3e3463ba57409b159420a0ef7b0a>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | stateHolder
24 | (32) `const dragon::rendering::coroutine::when::__l2::<lambda_43bb4ffe9e3a22cb4498ae83c4961d8c>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_d3a5c939dbee499625fd0911c0353b30>::()::__l6::<lambda_f10e050de8f728512a3c86538d818533>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,bool> >` | stateHolder
24 | (32) `const dragon::rendering::coroutine::when::__l2::<lambda_43bb4ffe9e3a22cb4498ae83c4961d8c>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_56131c259497b6ec942552da7c21d76f>::()::__l5::<lambda_0afc1d9e7de895844012834ce83d4eda>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<dragon::rendering::SharedTextureHandle>,dragon::rendering::SharedTextureHandle> __cdecl(void)>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_56131c259497b6ec942552da7c21d76f>::()::__l6::<lambda_467f0f8e00d8a7ce73b4595317e8ea80>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (64) `const std::function<std::variant<dragon::rendering::coroutine::TryAgain,dragon::rendering::coroutine::Run<dragon::rendering::SharedTextureHandle>,dragon::rendering::SharedTextureHandle> __cdecl(void)>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_d00de6bbc43d43a05bdb24eeb5c3e496>::()::__l5::<lambda_fad601f0254978b683237a88d12f8dae>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (40) `const dragon::rendering::DeferredResult<unsigned __int64>::then::__l2::<lambda_e7b38f5f36d64d4501f5714de64d6730>` | coroutineCallback


### `dragon::rendering::details::runStep::__l2::<lambda_d00de6bbc43d43a05bdb24eeb5c3e496>::()::__l6::<lambda_9076b7210075e75f20163fdf414fd3da>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::rendering::GraphicsTasks *` | gfxTasks
8 | (16) `std::shared_ptr<std::variant<dragon::rendering::details::Empty,dragon::rendering::SharedTextureHandle> >` | stateHolder
24 | (40) `const dragon::rendering::DeferredResult<unsigned __int64>::then::__l2::<lambda_e7b38f5f36d64d4501f5714de64d6730>` | coroutineCallback


### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::ReservedSpan<unsigned short,std::optional<unsigned short> const &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::VertexSpanContext *` | mContext
8 | (80) `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Span` | mSpan


### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Span`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Page *` | mPage
8 | (8) `unsigned __int64` | mBegin
16 | (8) `unsigned __int64` | mEnd
24 | (24) `dragon::mesh::TypedVertexBufferHandle` | mHandle
48 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >` | mBuffer
64 | (2) `unsigned __int16` | mBucketKey
68 | (4) `unsigned int` | mBytesOffset
72 | (4) `unsigned int` | mElementCount
76 | (4) `unsigned int` | mPayLoadSize


### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::ReservedSpan<enum dragon::mesh::IndexSize &>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::IndexSpanContext *` | mContext
8 | (72) `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Span` | mSpan


### `dragon::platform::helpers::VisitOverloaded<<lambda_4d53cd172c99e670bc86aa06728656e9>,<lambda_27e08a9bf906c54eca422e7cd0773bd1> >`
Offset | Type | Name
-|-|-|-
0 | (24) `dragon::CreateVertexOnlyAccelerationStructureTransaction::apply::__l8::<lambda_4d53cd172c99e670bc86aa06728656e9>` | baseclass_0
24 | (24) `dragon::CreateVertexOnlyAccelerationStructureTransaction::apply::__l8::<lambda_27e08a9bf906c54eca422e7cd0773bd1>` | baseclass_18


### `dragon::CreateVertexOnlyAccelerationStructureTransaction::apply::__l8::<lambda_4d53cd172c99e670bc86aa06728656e9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::ResolvedVertexBuffer *const *` | resolvedVertexBuffer
8 | (8) `dragon::CreateVertexOnlyAccelerationStructureTransaction *const` | __this
16 | (8) `const bgfx::AccelerationStructureBuildFlags::Enum *` | buildFlags


### `dragon::CreateVertexOnlyAccelerationStructureTransaction::apply::__l8::<lambda_27e08a9bf906c54eca422e7cd0773bd1>`
Offset | Type | Name
-|-|-|-
0 | (8) `const dragon::mesh::ResolvedVertexBuffer *const *` | resolvedVertexBuffer
8 | (8) `dragon::CreateVertexOnlyAccelerationStructureTransaction *const` | __this
16 | (8) `const bgfx::AccelerationStructureBuildFlags::Enum *` | buildFlags


### `dragon::platform::helpers::VisitOverloaded<<lambda_a76ece19decab96ffd79a77f3d0a0453>,<lambda_6579ed1640339e40f22cffd17f1e6024> >`
Offset | Type | Name
-|-|-|-
0 | (32) `dragon::UpdateVertexOnlyAccelerationStructureTransaction::apply::__l11::<lambda_a76ece19decab96ffd79a77f3d0a0453>` | baseclass_0
32 | (32) `dragon::UpdateVertexOnlyAccelerationStructureTransaction::apply::__l11::<lambda_6579ed1640339e40f22cffd17f1e6024>` | baseclass_20


### `dragon::UpdateVertexOnlyAccelerationStructureTransaction::apply::__l11::<lambda_a76ece19decab96ffd79a77f3d0a0453>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::ResolvedAccelerationStructure *const *` | resolvedAccelerationStructure
8 | (8) `const dragon::mesh::ResolvedVertexBuffer *const *` | resolvedVertexBuffer
16 | (8) `dragon::UpdateVertexOnlyAccelerationStructureTransaction *const` | __this
24 | (8) `const bgfx::AccelerationStructureBuildFlags::Enum *` | buildFlags


### `dragon::UpdateVertexOnlyAccelerationStructureTransaction::apply::__l11::<lambda_6579ed1640339e40f22cffd17f1e6024>`
Offset | Type | Name
-|-|-|-
0 | (8) `dragon::mesh::ResolvedAccelerationStructure *const *` | resolvedAccelerationStructure
8 | (8) `const dragon::mesh::ResolvedVertexBuffer *const *` | resolvedVertexBuffer
16 | (8) `dragon::UpdateVertexOnlyAccelerationStructureTransaction *const` | __this
24 | (8) `const bgfx::AccelerationStructureBuildFlags::Enum *` | buildFlags


### `dragon::mesh::RegistryTraits<dragon::mesh::VertexSpanType>::TBufferCreation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >` | mHandle
16 | (4) `unsigned int` | mBaseOffset
24 | (24) `dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>` | mBlock
48 | (4) `dragon::mesh::RegistryTraits<dragon::mesh::VertexSpanType>::AllocationType` | mAllocationType


### `dragon::result::Result<dragon::res::ResolvedTextureResource &,enum dragon::res::TextureError>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::variant<std::reference_wrapper<dragon::res::ResolvedTextureResource>,enum dragon::res::TextureError>` | mValue


### `DimensionConversionData`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mOverworldSpawnPoint
12 | (4) `int` | mNetherScale


### `DirectionEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `DirectionId` | id
4 | (4) `float` | x
8 | (4) `float` | y


### `DataStructures::Queue<RakNet::InternalPacket *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::InternalPacket **` | array
8 | (4) `unsigned int` | head
12 | (4) `unsigned int` | tail
16 | (4) `unsigned int` | allocation_size


### `DataStructures::LinkedList<HuffmanEncodingTreeNode *>`
Offset | Type | Name
-|-|-|-
0 | (24) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>` | baseclass_0


### `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | list_size
8 | (8) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *` | root
16 | (8) `DataStructures::CircularLinkedList<HuffmanEncodingTreeNode *>::node *` | position


### `DataStructures::List<RakNet::RakNetSocket2 *>`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNet::RakNetSocket2 **` | listArray
8 | (4) `unsigned int` | list_size
12 | (4) `unsigned int` | allocation_size


### `DatagramHeaderFormat`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::uint24_t` | datagramNumber
4 | (4) `float` | AS
8 | (1) `bool` | isACK
9 | (1) `bool` | isNAK
10 | (1) `bool` | isPacketPair
11 | (1) `bool` | hasBAndAS
12 | (1) `bool` | isContinuousSend
13 | (1) `bool` | needsBAndAs
14 | (1) `bool` | isValid


### `DataStructures::Heap<unsigned __int64,RakNet::InternalPacket *,0>::HeapNode`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | weight
8 | (8) `RakNet::InternalPacket *` | data


### `DataStructures::RangeNode<RakNet::uint24_t>`
Offset | Type | Name
-|-|-|-
0 | (4) `RakNet::uint24_t` | minIndex
4 | (4) `RakNet::uint24_t` | maxIndex


### `DataStructures::Map<int,RakNet::HuffmanEncodingTree *,&DataStructures::defaultMapKeyComparison<int> >::MapNode`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mapNodeKey
8 | (8) `RakNet::HuffmanEncodingTree *` | mapNodeData


### `DebugAssertException`
Offset | Type | Name
-|-|-|-
0 | (24) `std::exception` | baseclass_0
24 | (8) `std::unique_ptr<char [0]>` | mDescription
32 | (8) `std::unique_ptr<char [0]>` | mArgument
40 | (8) `std::unique_ptr<char [0]>` | mInfo
48 | (4) `int` | mLine
56 | (8) `std::unique_ptr<char [0]>` | mFile
64 | (8) `std::unique_ptr<char [0]>` | mFunction


### `D3D11_TEXTURE2D_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Width
4 | (4) `unsigned int` | Height
8 | (4) `unsigned int` | MipLevels
12 | (4) `unsigned int` | ArraySize
16 | (4) `DXGI_FORMAT` | Format
20 | (8) `DXGI_SAMPLE_DESC` | SampleDesc
28 | (4) `D3D11_USAGE` | Usage
32 | (4) `unsigned int` | BindFlags
36 | (4) `unsigned int` | CPUAccessFlags
40 | (4) `unsigned int` | MiscFlags


### `D3D12_RESOURCE_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_DIMENSION` | Dimension
8 | (8) `unsigned __int64` | Alignment
16 | (8) `unsigned __int64` | Width
24 | (4) `unsigned int` | Height
28 | (2) `unsigned __int16` | DepthOrArraySize
30 | (2) `unsigned __int16` | MipLevels
32 | (4) `DXGI_FORMAT` | Format
36 | (8) `DXGI_SAMPLE_DESC` | SampleDesc
44 | (4) `D3D12_TEXTURE_LAYOUT` | Layout
48 | (4) `D3D12_RESOURCE_FLAGS` | Flags


### `D3D12_CLEAR_VALUE`
Offset | Type | Name
-|-|-|-
0 | (4) `DXGI_FORMAT` | Format
4 | (16) `$B1C54AF1B8597FB0EAEF618BEB1816BB` | ___u1


### `D3D12_DEPTH_STENCIL_VALUE`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | Depth
4 | (1) `unsigned __int8` | Stencil


### `D3D12_VERTEX_BUFFER_VIEW`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | BufferLocation
8 | (4) `unsigned int` | SizeInBytes
12 | (4) `unsigned int` | StrideInBytes


### `D3D12_SUBRESOURCE_DATA`
Offset | Type | Name
-|-|-|-
0 | (8) `const void *` | pData
8 | (8) `__int64` | RowPitch
16 | (8) `__int64` | SlicePitch


### `D3D12_ROOT_SIGNATURE_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | NumParameters
8 | (8) `const D3D12_ROOT_PARAMETER *` | pParameters
16 | (4) `unsigned int` | NumStaticSamplers
24 | (8) `const D3D12_STATIC_SAMPLER_DESC *` | pStaticSamplers
32 | (4) `D3D12_ROOT_SIGNATURE_FLAGS` | Flags


### `D3D12_BLEND_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | AlphaToCoverageEnable
4 | (4) `int` | IndependentBlendEnable
8 | (320) `D3D12_RENDER_TARGET_BLEND_DESC[8]` | RenderTarget


### `D3D12_RENDER_TARGET_BLEND_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | BlendEnable
4 | (4) `int` | LogicOpEnable
8 | (4) `D3D12_BLEND` | SrcBlend
12 | (4) `D3D12_BLEND` | DestBlend
16 | (4) `D3D12_BLEND_OP` | BlendOp
20 | (4) `D3D12_BLEND` | SrcBlendAlpha
24 | (4) `D3D12_BLEND` | DestBlendAlpha
28 | (4) `D3D12_BLEND_OP` | BlendOpAlpha
32 | (4) `D3D12_LOGIC_OP` | LogicOp
36 | (1) `unsigned __int8` | RenderTargetWriteMask


### `D3D12_SAMPLER_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_FILTER` | Filter
4 | (4) `D3D12_TEXTURE_ADDRESS_MODE` | AddressU
8 | (4) `D3D12_TEXTURE_ADDRESS_MODE` | AddressV
12 | (4) `D3D12_TEXTURE_ADDRESS_MODE` | AddressW
16 | (4) `float` | MipLODBias
20 | (4) `unsigned int` | MaxAnisotropy
24 | (4) `D3D12_COMPARISON_FUNC` | ComparisonFunc
28 | (16) `float[4]` | BorderColor
44 | (4) `float` | MinLOD
48 | (4) `float` | MaxLOD


### `D3D12_GPU_DESCRIPTOR_HANDLE`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | ptr


### `D3D12_RESOURCE_BARRIER`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RESOURCE_BARRIER_TYPE` | Type
4 | (4) `D3D12_RESOURCE_BARRIER_FLAGS` | Flags
8 | (24) `$C2D3390844E6E77DD7A5EF954ED7B240` | ___u2


### `D3D12_RESOURCE_TRANSITION_BARRIER`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | pResource
8 | (4) `unsigned int` | Subresource
12 | (4) `D3D12_RESOURCE_STATES` | StateBefore
16 | (4) `D3D12_RESOURCE_STATES` | StateAfter


### `D3D12_RESOURCE_ALIASING_BARRIER`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | pResourceBefore
8 | (8) `ID3D12Resource *` | pResourceAfter


### `D3D12_RESOURCE_UAV_BARRIER`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | pResource


### `D3D12_DXIL_LIBRARY_DESC`
Offset | Type | Name
-|-|-|-
0 | (16) `D3D12_SHADER_BYTECODE` | DXILLibrary
16 | (4) `unsigned int` | NumExports
24 | (8) `D3D12_EXPORT_DESC *` | pExports


### `D3D12_SHADER_BYTECODE`
Offset | Type | Name
-|-|-|-
0 | (8) `const void *` | pShaderBytecode
8 | (8) `unsigned __int64` | BytecodeLength


### `D3D12_EXPORT_DESC`
Offset | Type | Name
-|-|-|-
0 | (8) `const wchar_t *` | Name
8 | (8) `const wchar_t *` | ExportToRename
16 | (4) `D3D12_EXPORT_FLAGS` | Flags


### `D3D12_STATE_SUBOBJECT`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_STATE_SUBOBJECT_TYPE` | Type
8 | (8) `const void *` | pDesc


### `DxcDefine`
Offset | Type | Name
-|-|-|-
0 | (8) `const wchar_t *` | Name
8 | (8) `const wchar_t *` | Value


### `D3D12_RAYTRACING_GEOMETRY_DESC`
Offset | Type | Name
-|-|-|-
0 | (4) `D3D12_RAYTRACING_GEOMETRY_TYPE` | Type
4 | (4) `D3D12_RAYTRACING_GEOMETRY_FLAGS` | Flags
8 | (48) `$F394181ACC9B4E24ADAEE34C04C61964` | ___u2


### `D3D12_RAYTRACING_GEOMETRY_TRIANGLES_DESC`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | Transform3x4
8 | (4) `DXGI_FORMAT` | IndexFormat
12 | (4) `DXGI_FORMAT` | VertexFormat
16 | (4) `unsigned int` | IndexCount
20 | (4) `unsigned int` | VertexCount
24 | (8) `unsigned __int64` | IndexBuffer
32 | (16) `D3D12_GPU_VIRTUAL_ADDRESS_AND_STRIDE` | VertexBuffer


### `D3D12_GPU_VIRTUAL_ADDRESS_AND_STRIDE`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | StartAddress
8 | (8) `unsigned __int64` | StrideInBytes


### `D3D12_RAYTRACING_GEOMETRY_AABBS_DESC`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | AABBCount
8 | (16) `D3D12_GPU_VIRTUAL_ADDRESS_AND_STRIDE` | AABBs


### `D3D12_DISPATCH_RAYS_DESC`
Offset | Type | Name
-|-|-|-
0 | (16) `D3D12_GPU_VIRTUAL_ADDRESS_RANGE` | RayGenerationShaderRecord
16 | (24) `D3D12_GPU_VIRTUAL_ADDRESS_RANGE_AND_STRIDE` | MissShaderTable
40 | (24) `D3D12_GPU_VIRTUAL_ADDRESS_RANGE_AND_STRIDE` | HitGroupTable
64 | (24) `D3D12_GPU_VIRTUAL_ADDRESS_RANGE_AND_STRIDE` | CallableShaderTable
88 | (4) `unsigned int` | Width
92 | (4) `unsigned int` | Height
96 | (4) `unsigned int` | Depth


### `D3D12_GPU_VIRTUAL_ADDRESS_RANGE`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | StartAddress
8 | (8) `unsigned __int64` | SizeInBytes


### `D3D12_GPU_VIRTUAL_ADDRESS_RANGE_AND_STRIDE`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | StartAddress
8 | (8) `unsigned __int64` | SizeInBytes
16 | (8) `unsigned __int64` | StrideInBytes


### `dragon::materials::definition::FlagMode`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (32) `std::string` | mValue


### `DataItem`
```
struct __cppobj __declspec(align(4)) DataItem
{
  DataItem_vtbl *__vftable /*VFT*/;
  _BYTE mType[1];
  const unsigned __int16 mId;
  bool mDirty;
};

```

### `DataItem_vtbl`
```
struct /*VFT*/ DataItem_vtbl
{
  void (__fastcall *~DataItem)(DataItem *this);
  bool (__fastcall *isDataEqual)(DataItem *this, const DataItem *);
  std::unique_ptr<DataItem> *(__fastcall *clone)(DataItem *this, std::unique_ptr<DataItem> *result);
};

```

### `DoubleTag_vtbl`
```
struct /*VFT*/ DoubleTag_vtbl
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

### `DataLoadHelper_vtbl`
```
struct /*VFT*/ DataLoadHelper_vtbl
{
  void (__fastcall *~DataLoadHelper)(DataLoadHelper *this);
  Vec3 *(__fastcall *loadPosition)(DataLoadHelper *this, Vec3 *result, const Vec3 *);
  BlockPos *(__fastcall *loadBlockPosition)(DataLoadHelper *this, BlockPos *result, const BlockPos *);
  BlockPos *(__fastcall *loadBlockPositionOffset)(DataLoadHelper *this, BlockPos *result, const BlockPos *);
  float (__fastcall *loadRotationDegreesX)(DataLoadHelper *this, float);
  float (__fastcall *loadRotationDegreesY)(DataLoadHelper *this, float);
  float (__fastcall *loadRotationRadiansX)(DataLoadHelper *this, float);
  float (__fastcall *loadRotationRadiansY)(DataLoadHelper *this, float);
  unsigned __int8 (__fastcall *loadFacingID)(DataLoadHelper *this, unsigned __int8);
  Direction::Type (__fastcall *loadDirection)(DataLoadHelper *this, Direction::Type);
  Vec3 *(__fastcall *loadDirection)(DataLoadHelper *this, Vec3 *result, const Vec3 *);
  Rotation (__fastcall *loadRotation)(DataLoadHelper *this, Rotation);
  Mirror (__fastcall *loadMirror)(DataLoadHelper *this, Mirror);
  ActorUniqueID *(__fastcall *loadActorUniqueID)(DataLoadHelper *this, ActorUniqueID *result, ActorUniqueID);
  ActorUniqueID *(__fastcall *loadOwnerID)(DataLoadHelper *this, ActorUniqueID *result, ActorUniqueID);
  DataLoadHelperType (__fastcall *getType)(DataLoadHelper *this);
  bool (__fastcall *shouldResetTime)(DataLoadHelper *this);
};

```

### `dragon::mesh::VertexBufferView`
```
struct __cppobj dragon::mesh::VertexBufferView
{
  dragon::mesh::VertexBufferView_vtbl *__vftable /*VFT*/;
};

```

### `dragon::mesh::VertexBufferView_vtbl`
```
struct /*VFT*/ dragon::mesh::VertexBufferView_vtbl
{
  void (__fastcall *~VertexBufferView)(dragon::mesh::VertexBufferView *this);
};

```

### `dragon::mesh::ResolvedVertexBufferResource`
```
struct __cppobj dragon::mesh::ResolvedVertexBufferResource : dragon::mesh::ResolvedVertexBuffer
{
};

```

### `dragon::mesh::IndexBufferView`
```
struct __cppobj dragon::mesh::IndexBufferView
{
  dragon::mesh::IndexBufferView_vtbl *__vftable /*VFT*/;
};

```

### `dragon::mesh::IndexBufferView_vtbl`
```
struct /*VFT*/ dragon::mesh::IndexBufferView_vtbl
{
  void (__fastcall *~IndexBufferView)(dragon::mesh::IndexBufferView *this);
};

```

### `dragon::mesh::ResolvedIndexBufferResource`
```
struct __cppobj dragon::mesh::ResolvedIndexBufferResource : dragon::mesh::ResolvedIndexBuffer
{
};

```

### `DataDrivenGeometry`
```
struct __cppobj __declspec(align(8)) DataDrivenGeometry
{
  HashedString mGeoName;
  std::vector<ModelPart> mModelParts;
  std::vector<unsigned __int64> mRootModelParts;
  mce::MaterialPtr mDefaultMaterial;
  Vec3 mLeashOffset;
  std::vector<SkinnedMeshGroup> mSkinnedMeshGroups;
  std::vector<BoneOrientation> mDefaultBoneOrientations;
  std::vector<ModelPartLocator> mLocators;
  GeometryPtr mSourceGeometry;
  _BYTE mSkeletalHierarchyIndex[4];
};

```

### `DrawsByTexture`
```
struct __cppobj DrawsByTexture
{
  const mce::ClientTexture *mTexture;
  std::vector<MeshRenderData> mMeshes;
  std::vector<DrawsByTexture> mDrawsByTexture;
};

```

### `DrawsByMesh`
```
struct __cppobj DrawsByMesh
{
  mce::Mesh *mMesh;
  std::vector<DrawsByTexture> mDrawsByTexture;
};

```

### `DrawsByMaterial`
```
struct __cppobj DrawsByMaterial
{
  mce::MaterialPtr mMaterial;
  std::vector<DrawsByMesh> mDrawsByMesh;
};

```

### `DrawsByRenderController`
```
struct __cppobj DrawsByRenderController
{
  const RenderController *mRenderController;
  std::vector<DrawsByMaterial> mDrawsByMaterial;
};

```

### `DataStructures::List<RakNet::SystemAddress>`
```
struct __cppobj DataStructures::List<RakNet::SystemAddress>
{
  RakNet::SystemAddress *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::List<RakNet::RakNetGUID>`
```
struct __cppobj DataStructures::List<RakNet::RakNetGUID>
{
  RakNet::RakNetGUID *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DataStructures::ByteQueue`
```
struct __cppobj __declspec(align(8)) DataStructures::ByteQueue
{
  char *data;
  unsigned int readOffset;
  unsigned int writeOffset;
  unsigned int lengthAllocated;
};

```

### `DataStructures::MemoryPool<RakNet::Packet>::Page`
```
struct DataStructures::MemoryPool<RakNet::Packet>::Page
{
  DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::Packet>::Page *next;
  DataStructures::MemoryPool<RakNet::Packet>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage`
```
struct __cppobj DataStructures::MemoryPool<RakNet::Packet>::MemoryWithPage
{
  RakNet::Packet userMemory;
  DataStructures::MemoryPool<RakNet::Packet>::Page *parentPage;
};

```

### `DataStructures::MemoryPool<RakNet::SystemAddress>::Page`
```
struct DataStructures::MemoryPool<RakNet::SystemAddress>::Page
{
  DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *next;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage`
```
struct __cppobj DataStructures::MemoryPool<RakNet::SystemAddress>::MemoryWithPage
{
  RakNet::SystemAddress userMemory;
  DataStructures::MemoryPool<RakNet::SystemAddress>::Page *parentPage;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteClient *>::Page`
```
struct DataStructures::MemoryPool<RakNet::RemoteClient *>::Page
{
  DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage **availableStack;
  int availableStackSize;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage *block;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *next;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *prev;
};

```

### `DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage`
```
struct DataStructures::MemoryPool<RakNet::RemoteClient *>::MemoryWithPage
{
  RakNet::RemoteClient *userMemory;
  DataStructures::MemoryPool<RakNet::RemoteClient *>::Page *parentPage;
};

```

### `DataStructures::List<RakNet::RakNetStatistics>`
```
struct __cppobj DataStructures::List<RakNet::RakNetStatistics>
{
  RakNet::RakNetStatistics *listArray;
  unsigned int list_size;
  unsigned int allocation_size;
};

```

### `DebugInfoPacket`
```
const struct __cppobj DebugInfoPacket : Packet
{
  std::string mData;
  ActorUniqueID mActorId;
};

```

### `DebugInfoPacket_vtbl`
```
struct /*VFT*/ DebugInfoPacket_vtbl
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

### `DisconnectPacket`
```
const struct __cppobj DisconnectPacket : Packet
{
  bool mSkipMessage;
  std::string mMessage;
};

```

### `DisconnectPacket_vtbl`
```
struct /*VFT*/ DisconnectPacket_vtbl
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

### `Dimension`
```
struct __cppobj Dimension : LevelListener, SavedData, Bedrock::EnableNonOwnerReferences
{
  Level *mLevel;
  DimensionHeightRange mHeightRange;
  __int16 mSeaLevel;
  std::unique_ptr<BlockSource> mBlockSource;
  float mMobsPerChunkSurface[7];
  float mMobsPerChunkUnderground[7];
  BrightnessPair mDefaultBrightness;
  std::unique_ptr<BaseLightTextureImageBuilder> mLightTextureImageBuilder;
  std::unique_ptr<DimensionBrightnessRamp> mDimensionBrightnessRamp;
  std::string mName;
  AutomaticID<Dimension,int> mId;
  bool mUltraWarm;
  bool mHasCeiling;
  bool mHasWeather;
  bool mHasSkylight;
  Brightness mSkyDarken;
  std::unique_ptr<BlockEventDispatcher> mDispatcher;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::unique_ptr<PostprocessingManager> mPostProcessingManager;
  std::unique_ptr<ChunkSource> mChunkSource;
  WorldGenerator *mWorldGenerator;
  std::unique_ptr<Weather> mWeather;
  std::unique_ptr<Seasons> mSeasons;
  std::unique_ptr<CircuitSystem> mCircuitSystem;
  const int CIRCUIT_TICK_RATE;
  int mCircuitSystemTickRate;
  std::unordered_map<ActorUniqueID,gsl::not_null<Actor *>> mEntityIdLookup;
  BeardAndShaverStorage mBeardandShaverStorage;
  std::unordered_map<ChunkPos,std::vector<std::unique_ptr<CompoundTag>>> mLimboEntities;
  std::set<ActorUniqueID> mEntitiesToMoveChunks;
  std::unique_ptr<TickingAreaList> mTickingAreaList;
  LevelChunkGarbageCollector mLevelChunkGarbageCollector;
  std::set<ActorUniqueID> mWitherIDs;
  std::unique_ptr<RuntimeLightingManager> mRuntimeLightingManager;
  std::unique_ptr<LevelChunkBuilderData> mLevelChunkBuilderData;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPruneTime;
  std::unique_ptr<ChunkBuildOrderPolicyBase> mChunkBuildOrderPolicy;
  std::string mClientLevelID;
  std::unique_ptr<ChunkSource> mClientTerrainDBChunkSource;
  std::unordered_map<std::string,EntityAOIInfo> mEntityAOI;
  std::unordered_map<std::string,EntityAOIInfo> mEntityAOIToAdd;
  std::vector<std::string> mEntityAOIToErase;
  std::optional<AutomaticID<Dimension,int> > mSourceDimensionType;
  bool mUseLocalTime;
  int mLocalTime;
  bool mLocalDoDayNightCycle;
  __int64 mLastTimePacketSent;
  std::unique_ptr<VillageManager> mVillageManager;
  std::vector<NetworkIdentifierWithSubId> mTemporaryPlayerIds;
  std::unique_ptr<ChunkLoadActionList> mChunkLoadActionList;
};

```

### `DenyList`
```
struct __cppobj DenyList
{
  std::vector<DenyList::Entry> mEntries;
  std::recursive_mutex mEntriesMutex;
};

```

### `DevConsoleLogger`
```
struct __cppobj DevConsoleLogger
{
  Core::PathBuffer<std::string > mLogFolder;
  Core::OutputFileStream mLogFile;
  std::basic_stringstream<char,std::char_traits<char>,std::allocator<char> > mFileBuffer;
  std::string mTimeStamp;
  std::function<std::string __cdecl(void)> mGetTestrunIDCallback;
  std::function<bool __cdecl(void)> mIsAutomationRunCallback;
  TimerFacade mTimerFacade;
};

```

### `DirectoryPackSource`
```
struct __cppobj DirectoryPackSource : PackSource
{
  Core::PathBuffer<std::string > mPath;
  _BYTE mPackType[1];
  PackOrigin mPackOrigin;
  bool mDiscovered;
  bool mIsRediscoverable;
  bool mIsDevDirectory;
  std::vector<std::unique_ptr<Pack>> mPacks;
  PackSourceReport mReport;
};

```

### `DirectoryPackSource_vtbl`
```
struct /*VFT*/ DirectoryPackSource_vtbl
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

### `DateManager`
```
struct __cppobj DateManager : Bedrock::EnableNonOwnerReferences
{
  unsigned int mTimeScale;
  __int64 mRealTime;
  __int64 mTime;
  std::mutex mScheduledCallbacksMutex;
  std::priority_queue<ScheduledCallback,std::vector<ScheduledCallback>,CompareScheduledCallback> mScheduledCallbacks;
};

```

### `DocumentComponent`
```
struct __cppobj DocumentComponent : StoreUIComponent
{
  std::string mDocumentReference;
  std::string mDocumentId;
};

```

### `DocumentComponent_vtbl`
```
struct /*VFT*/ DocumentComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `DurableDocument`
```
struct __cppobj DurableDocument
{
  CommonDocument mCommon;
  DurableCustom mCustom;
};

```

### `DurableSearchResults`
```
const struct __cppobj DurableSearchResults : CommonSearchResults
{
  std::vector<DurableDocument> mDocuments;
};

```

### `DocumentMeta`
```
struct __cppobj __declspec(align(8)) DocumentMeta
{
  DurableDocument doc;
  bool installed;
  bool updateAvailable;
};

```

### `DynamicImageResourceManager`
```
struct __cppobj DynamicImageResourceManager : cg::ResourceManager<std::shared_ptr<mce::Image>,enum mce::DynamicTexture,ImageTrackerTemplate<DynamicImageResourceManager>,std::shared_ptr<mce::Image>,std::map>
{
};

```

### `DlcBatchModel_vtbl`
```
struct /*VFT*/ DlcBatchModel_vtbl
{
  void (__fastcall *~IDlcBatchModel)(IDlcBatchModel *this);
  void (__fastcall *searchForProductIds)(IDlcBatchModel *this, std::function<void __cdecl(bool)>);
  void (__fastcall *beginExclusiveDownload)(IDlcBatchModel *this);
  void (__fastcall *beginPackDownload)(IDlcBatchModel *this);
  void (__fastcall *beginAutoDownload)(IDlcBatchModel *this);
  void (__fastcall *cancelDownload)(IDlcBatchModel *this);
  void (__fastcall *cancelPendingDownload)(IDlcBatchModel *this);
  void (__fastcall *cancelPendingImport)(IDlcBatchModel *this);
  void (__fastcall *pauseDownload)(IDlcBatchModel *this);
  void (__fastcall *resumeDownload)(IDlcBatchModel *this);
  bool (__fastcall *isDownloadingOrImporting)(IDlcBatchModel *this);
  bool (__fastcall *isDownloading)(IDlcBatchModel *this);
  bool (__fastcall *isDownloadComplete)(IDlcBatchModel *this);
  unsigned __int64 (__fastcall *getDownloadSize)(IDlcBatchModel *this);
  unsigned __int64 (__fastcall *getDownloadedBytes)(IDlcBatchModel *this);
  float (__fastcall *getDownloadProgress)(IDlcBatchModel *this);
  bool (__fastcall *isImporting)(IDlcBatchModel *this);
  bool (__fastcall *isImportWaiting)(IDlcBatchModel *this);
  unsigned __int64 (__fastcall *getImportTotal)(IDlcBatchModel *this);
  unsigned __int64 (__fastcall *getImportedCount)(IDlcBatchModel *this);
  float (__fastcall *getImportProgress)(IDlcBatchModel *this);
  int (__fastcall *getIndexOfActiveImport)(IDlcBatchModel *this);
  const std::vector<DlcId> *(__fastcall *getDlcIds)(IDlcBatchModel *this);
  ItemInstallState (__fastcall *getDlcInstalledState)(IDlcBatchModel *this);
  bool (__fastcall *isContentSearchComplete)(IDlcBatchModel *this);
  bool (__fastcall *isFailed)(IDlcBatchModel *this);
  bool (__fastcall *isCancelled)(IDlcBatchModel *this);
  gsl::not_null<Bedrock::NonOwnerPointer<ContentAcquisition> > *(__fastcall *contentAcquisition)(IDlcBatchModel *this, gsl::not_null<Bedrock::NonOwnerPointer<ContentAcquisition> > *result);
  gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > *(__fastcall *storeCatalog)(IDlcBatchModel *this, gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > *result);
};

```

### `DlcBatchCacheModel`
```
struct __cppobj DlcBatchCacheModel
{
  std::vector<DlcBatchModel> mDlcBatchList;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentAcquisition> > mContentAcquisition;
  gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > mStoreCatalog;
};

```

### `DebugRenderer`
```
struct __cppobj DebugRenderer
{
};

```

### `DeferredSound`
```
struct __cppobj __declspec(align(8)) DeferredSound
{
  std::string mName;
  Vec3 mPos;
  float mVolume;
  float mPitch;
};

```

### `DefaultImportContext`
```
struct __cppobj DefaultImportContext : ImportContext
{
  ResourcePackManager *mPackManager;
  ResourcePackRepository *mPackRepository;
  WorldTemplateManager *mTemplateManager;
  IMinecraftEventing *mEventing;
  ToastManager *mToasting;
  Core::PathBuffer<std::string > mOriginPath;
  bool mPreferZippedPacks;
  std::function<void __cdecl(bool)> mAllSuccessCallback;
  std::function<void __cdecl(bool,PackManifest const *)> mPackImportCallback;
};

```

### `DefaultImportContext_vtbl`
```
struct /*VFT*/ DefaultImportContext_vtbl
{
  void (__fastcall *~ImportContext)(ImportContext *this);
  Core::PathBuffer<std::string > *(__fastcall *generatePackFolderName)(ImportContext *this, Core::PathBuffer<std::string > *result, const PackManifest *);
  Core::PathBuffer<std::string > *(__fastcall *getBehaviorPacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getResourcePacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getWorldTemplatePath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getSkinPacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getPersonaPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  bool (__fastcall *allowOverwrite)(ImportContext *this);
  bool (__fastcall *shouldUnzipToDestination)(ImportContext *this, const PackManifest *);
  bool (__fastcall *importAsFlatFile)(ImportContext *this, const PackManifest *);
  void (__fastcall *notifyEarlyImportStarted)(ImportContext *this, bool);
  void (__fastcall *notifyImportStarted)(ImportContext *this, const PackManifest *);
  void (__fastcall *notifyMultiImportStarted)(ImportContext *this, int);
  void (__fastcall *notifyImportSucceeded)(ImportContext *this, const ResourcePack *, ImportSuccess, const PackManifest *, const PackReport *, const Core::Path *);
  void (__fastcall *notifyImportFailed)(ImportContext *this, ImportFailure, const PackManifest *, PackReport *, const Core::Path *);
  bool (__fastcall *modifyManifest)(ImportContext *this, PackManifest *);
};

```

### `DlcImportContext`
```
struct __cppobj DlcImportContext : DefaultImportContext
{
  const Core::PathBuffer<std::string > mImportFilePath;
  int mTotalImportCount;
  int mCompletedImportCount;
};

```

### `DlcImportContext_vtbl`
```
struct /*VFT*/ DlcImportContext_vtbl
{
  void (__fastcall *~ImportContext)(ImportContext *this);
  Core::PathBuffer<std::string > *(__fastcall *generatePackFolderName)(ImportContext *this, Core::PathBuffer<std::string > *result, const PackManifest *);
  Core::PathBuffer<std::string > *(__fastcall *getBehaviorPacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getResourcePacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getWorldTemplatePath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getSkinPacksPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  Core::PathBuffer<std::string > *(__fastcall *getPersonaPath)(ImportContext *this, Core::PathBuffer<std::string > *result);
  bool (__fastcall *allowOverwrite)(ImportContext *this);
  bool (__fastcall *shouldUnzipToDestination)(ImportContext *this, const PackManifest *);
  bool (__fastcall *importAsFlatFile)(ImportContext *this, const PackManifest *);
  void (__fastcall *notifyEarlyImportStarted)(ImportContext *this, bool);
  void (__fastcall *notifyImportStarted)(ImportContext *this, const PackManifest *);
  void (__fastcall *notifyMultiImportStarted)(ImportContext *this, int);
  void (__fastcall *notifyImportSucceeded)(ImportContext *this, const ResourcePack *, ImportSuccess, const PackManifest *, const PackReport *, const Core::Path *);
  void (__fastcall *notifyImportFailed)(ImportContext *this, ImportFailure, const PackManifest *, PackReport *, const Core::Path *);
  bool (__fastcall *modifyManifest)(ImportContext *this, PackManifest *);
};

```

### `DownloadStateObject`
```
struct __cppobj __declspec(align(8)) DownloadStateObject
{
  const DlcId mDlcId;
  const std::vector<PackIdVersion> mPackIdentities;
  const bool mSuccess;
};

```

### `DeserializeDataParams`
```
struct __cppobj DeserializeDataParams
{
  Json::Value *mValue;
  const SemVersion mPackVersion;
};

```

### `Description_vtbl`
```
struct /*VFT*/ Description_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `DiscoveryConfig`
```
struct __cppobj DiscoveryConfig
{
  float heartbeatFrequencyS;
  int maxRetryCount;
  int failedHeartbeatsBeforeInvalidation;
};

```

### `DemoConfig`
```
struct __cppobj DemoConfig
{
  std::string worldId;
  std::optional<int> limitedWorldWidth;
  std::optional<int> limitedWorldDepth;
};

```

### `dragon::platform::Statistics`
```
struct __cppobj __declspec(align(8)) dragon::platform::Statistics
{
  __int64 mCpuTimeFrame;
  __int64 mCpuTimeBegin;
  __int64 mCpuTimeEnd;
  __int64 mCpuTimerFreq;
  __int64 mGpuTimeBegin;
  __int64 mGpuTimeEnd;
  __int64 mGpuTimerFreq;
  __int64 mWaitRender;
  __int64 mWaitSubmit;
  unsigned int mNumDraw;
  unsigned int mNumCompute;
  unsigned int mMaxGpuLatency;
  unsigned __int16 mNumDynamicIndexBuffers;
  unsigned __int16 mNumDynamicVertexBuffers;
  unsigned __int16 mNumFrameBuffers;
  unsigned __int16 mNumIndexBuffers;
  unsigned __int16 mNumOcclusionQueries;
  unsigned __int16 mNumPrograms;
  unsigned __int16 mNumShaders;
  unsigned __int16 mNumTextures;
  unsigned __int16 mNumUniforms;
  unsigned __int16 mNumVertexBuffers;
  unsigned __int16 mNumVertexDecls;
  __int64 mTextureMemoryUsed;
  __int64 mRtMemoryUsed;
  int mTransientVbUsed;
  int mTransientIbUsed;
  unsigned __int64 mGpuMemoryMax;
  unsigned __int64 mGpuMemoryUsed;
  boost::container::static_vector<unsigned char,16> mSupportedMSAALevels;
  _BYTE mRenderApi[1];
};

```

### `dragon::rendering::details::Empty`
```
struct __cppobj dragon::rendering::details::Empty
{
  int mDummy;
};

```

### `dragon::platform::GLTextureWrapper`
```
struct dragon::platform::GLTextureWrapper
{
  unsigned int mGLName;
};

```

### `dragon::platform::WindowsTextureWrapper`
```
struct dragon::platform::WindowsTextureWrapper
{
  void *mPtr;
};

```

### `dragon::guarded::Guarded<std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout>,std::shared_mutex>`
```
struct __cppobj dragon::guarded::Guarded<std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout>,std::shared_mutex>
{
  std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout> mValue;
  std::shared_mutex mMutex;
};

```

### `dragon::guarded::Guarded<std::unordered_map<unsigned short,dragon::mesh::VertexDeclManager::Impl::DeclLayout const *>,std::shared_mutex>`
```
struct __cppobj dragon::guarded::Guarded<std::unordered_map<unsigned short,dragon::mesh::VertexDeclManager::Impl::DeclLayout const *>,std::shared_mutex>
{
  std::unordered_map<unsigned short,dragon::mesh::VertexDeclManager::Impl::DeclLayout const *> mValue;
  std::shared_mutex mMutex;
};

```

### `dragon::mesh::VertexDeclManager::Impl`
```
struct __cppobj dragon::mesh::VertexDeclManager::Impl
{
  dragon::guarded::Guarded<std::unordered_map<unsigned int,dragon::mesh::VertexDeclManager::Impl::DeclLayout>,std::shared_mutex> mHashTable;
  dragon::guarded::Guarded<std::unordered_map<unsigned short,dragon::mesh::VertexDeclManager::Impl::DeclLayout const *>,std::shared_mutex> mHandleTable;
  Bedrock::Threading::InstancedThreadLocal<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > >,std::allocator<boost::container::flat_map<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool,std::less<dragon::mesh::VertexDeclManager::Impl::ValidationKey>,boost::container::new_allocator<std::pair<dragon::mesh::VertexDeclManager::Impl::ValidationKey,bool> > > > > mValidationCache;
};

```

### `dragon::mesh::VertexDeclManager`
```
struct __cppobj dragon::mesh::VertexDeclManager
{
  std::unique_ptr<dragon::mesh::VertexDeclManager::Impl> mImpl;
};

```

### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Page`
```
struct __cppobj dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Page
{
  dragon::mesh::RegistryTraits<dragon::mesh::VertexSpanType>::TBufferCreation mBuffer;
  unsigned __int64 mSize;
};

```

### `dragon::rendering::RenderContext`
```
struct __cppobj dragon::rendering::RenderContext
{
};

```

### `dragon::rendering::GraphicsTasks`
```
struct __cppobj dragon::rendering::GraphicsTasks
{
  std::thread::id mRendererThreadId;
  bool mInitialized;
  bool mSkipPresenting;
  dragon::rendering::GraphicsTasks::ExecutionMode mExecutionMode;
  gsl::not_null<WorkerPool *> mRendererPool;
  std::vector<std::reference_wrapper<WorkerPool>> mHelperPools;
  gsl::not_null<Scheduler *> mClientScheduler;
  std::shared_ptr<MPMCQueue<std::function<void __cdecl(void)> > > mResourceTasks;
  std::shared_ptr<MPMCQueue<std::function<void __cdecl(void)> > > mRenderingTasks;
  std::shared_ptr<MPMCQueue<std::function<void __cdecl(void)> > > mRenderingPostTasks;
  std::shared_ptr<Core::DeferredTask> mFrameContentCallback;
  std::shared_ptr<Core::DeferredTask> mRenderingFrameWorker;
  Scheduler mRenderingCommandScheduler;
  cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > > mGraphicsDispatcher;
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>> mMainFrameRenderTasksQueue;
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(void)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>> mParallelWorkTasksQueue;
  std::atomic<unsigned int> mFrameCount;
  unsigned __int64 mWorkersCount;
};

```

### `dragon::memory::BufferSource::LifetimeToken`
```
struct __cppobj dragon::memory::BufferSource::LifetimeToken
{
};

```

### `dragon::mesh::VertexBufferType::ResourceDescription`
```
struct __cppobj dragon::mesh::VertexBufferType::ResourceDescription
{
  bgfx::VertexDeclHandle mDeclHandle;
  unsigned __int64 mSize;
  unsigned __int64 mStride;
};

```

### `dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource`
```
struct __cppobj dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource
{
  std::mutex mAccessLock;
  std::vector<std::variant<dragon::mesh::VertexBufferType::ItemResourceUpdateParameters,dragon::mesh::A0xd4a888ee::VertexBufferType::OffsetResourceUpdateParameters>> mDeferredOrderedUpdateSequence;
  dragon::rendering::BufferState mState;
  bool mWasEverCreated;
  bool mWasEverUsed;
  std::variant<bgfx::VertexBufferHandle,bgfx::DynamicVertexBufferHandle> mResource;
  dragon::mesh::VertexBufferType::ResourceDescription mDescription;
  dragon::mesh::VertexBufferDescription mPublicDescription;
  std::optional<dragon::mesh::VertexBufferType::ResourceCreationParameters> mCreationParameters;
};

```

### `dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>`
```
struct __cppobj dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>
{
  dragon::rendering::GraphicsTasks *mGraphicsTasks;
  std::atomic<unsigned __int64> mHandleCounter;
  MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> > > mBuffersDeletionQueue;
  Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource> > mBuffers;
};

```

### `dragon::mesh::VertexBufferResourceManager::Impl`
```
struct __cppobj dragon::mesh::VertexBufferResourceManager::Impl : dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>
{
};

```

### `dragon::mesh::VertexBufferResourceManager`
```
struct __cppobj dragon::mesh::VertexBufferResourceManager
{
  std::unique_ptr<dragon::mesh::VertexBufferResourceManager::Impl> mImpl;
  dragon::mesh::VertexDeclManager *mVertexDeclManager;
};

```

### `dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>`
```
struct __cppobj dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>
{
  std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> > mBuffer;
  unsigned __int64 mFreeCount;
  unsigned __int64 mSlotCount;
  unsigned __int64 mFreeStart;
  std::vector<dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>> mFreeTargets;
};

```

### `dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>`
```
struct __cppobj dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>
{
  const unsigned int mSlabSize;
  const unsigned int mSlotSize;
  std::vector<std::unique_ptr<dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::VertexBufferHandleTypeKey,unsigned __int64> >,unsigned int>>> mSlabs;
};

```

### `dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>,std::mutex>`
```
struct __cppobj dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>,std::mutex>
{
  dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int> mValue;
  std::mutex mMutex;
};

```

### `dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>`
```
struct __cppobj dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>
{
  const unsigned int mSlotSize;
  const bool mIsPassThrough;
  dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int>,std::mutex> mAllocator;
};

```

### `dragon::mesh::VertexSpanContext`
```
struct __cppobj dragon::mesh::VertexSpanContext
{
  dragon::mesh::VertexBufferResourceManager *mVbResourceManager;
  dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::VertexBufferAllocator,unsigned int> mPartitionedAllocator;
  dragon::mesh::VertexFormat mBytesDecl;
};

```

### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>`
```
struct __cppobj dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>
{
  std::map<unsigned short,std::list<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Page,std::allocator<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Page> >> mActivePages;
  std::map<unsigned short,std::vector<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Span,std::allocator<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>::Span> >> mFreeBlocks;
  std::mutex mAccessLock;
  std::atomic<unsigned __int64> mBytesInUse;
  std::atomic<unsigned __int64> mTotalBytesAllocated;
  dragon::mesh::VertexSpanContext mContext;
};

```

### `dragon::mesh::VertexSpanRegistry`
```
struct __cppobj dragon::mesh::VertexSpanRegistry : dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::VertexSpanType,dragon::memory::BufferSource &&>
{
};

```

### `dragon::mesh::RegistryTraits<dragon::mesh::IndexSpanType>::TBufferCreation`
```
struct __cppobj __declspec(align(8)) dragon::mesh::RegistryTraits<dragon::mesh::IndexSpanType>::TBufferCreation
{
  std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> > mHandle;
  unsigned int mBaseOffset;
  dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int> mBlock;
  dragon::mesh::RegistryTraits<dragon::mesh::IndexSpanType>::AllocationType mAllocationType;
};

```

### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Page`
```
struct __cppobj dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Page
{
  dragon::mesh::RegistryTraits<dragon::mesh::IndexSpanType>::TBufferCreation mBuffer;
  unsigned __int64 mSize;
};

```

### `dragon::mesh::IndexBufferType::ResourceUpdateParameters`
```
struct __cppobj dragon::mesh::IndexBufferType::ResourceUpdateParameters
{
  unsigned int mStartIndex;
  dragon::memory::BufferSource mUpdateData;
};

```

### `dragon::mesh::IndexBufferType::ResourceDescription`
```
struct __cppobj dragon::mesh::IndexBufferType::ResourceDescription
{
  dragon::mesh::IndexSize mIndexSize;
  unsigned __int64 mSize;
};

```

### `dragon::mesh::IndexBufferDescription`
```
struct __cppobj __declspec(align(8)) dragon::mesh::IndexBufferDescription
{
  dragon::mesh::IndexSize mIndexSize;
  unsigned __int64 mDataSize;
  unsigned __int64 mElementCount;
  unsigned __int16 mFlags;
};

```

### `dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource`
```
struct __cppobj dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource
{
  std::mutex mAccessLock;
  std::vector<dragon::mesh::IndexBufferType::ResourceUpdateParameters> mDeferredOrderedUpdateSequence;
  dragon::rendering::BufferState mState;
  bool mWasEverCreated;
  bool mWasEverUsed;
  std::variant<bgfx::IndexBufferHandle,bgfx::DynamicIndexBufferHandle> mResource;
  dragon::mesh::IndexBufferType::ResourceDescription mDescription;
  dragon::mesh::IndexBufferDescription mPublicDescription;
  std::optional<dragon::mesh::IndexBufferType::ResourceCreationParameters> mCreationParameters;
};

```

### `dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>`
```
struct __cppobj dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>
{
  dragon::rendering::GraphicsTasks *mGraphicsTasks;
  std::atomic<unsigned __int64> mHandleCounter;
  MPMCQueue<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> > > mBuffersDeletionQueue;
  Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource> > mBuffers;
};

```

### `dragon::mesh::IndexBufferResourceManager::Impl`
```
struct __cppobj dragon::mesh::IndexBufferResourceManager::Impl : dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>
{
};

```

### `dragon::mesh::IndexBufferResourceManager`
```
struct __cppobj dragon::mesh::IndexBufferResourceManager
{
  std::unique_ptr<dragon::mesh::IndexBufferResourceManager::Impl> mImpl;
};

```

### `dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int>`
```
struct __cppobj dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int>
{
  std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> > mBuffer;
  unsigned __int64 mFreeCount;
  unsigned __int64 mSlotCount;
  unsigned __int64 mFreeStart;
  std::vector<dragon::memory::Block<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int>> mFreeTargets;
};

```

### `dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>`
```
struct __cppobj dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>
{
  const unsigned int mSlabSize;
  const unsigned int mSlotSize;
  std::vector<std::unique_ptr<dragon::memory::PartitionedFixedAllocator<std::optional<dragon::rendering::details::BufferHandleTypeWrapper<dragon::mesh::details::IndexBufferHandleTypeKey,unsigned __int64> >,unsigned int>>> mSlabs;
};

```

### `dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>,std::mutex>`
```
struct __cppobj dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>,std::mutex>
{
  dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int> mValue;
  std::mutex mMutex;
};

```

### `dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>`
```
struct __cppobj dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>
{
  const unsigned int mSlotSize;
  const bool mIsPassThrough;
  dragon::guarded::Guarded<dragon::memory::PartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int>,std::mutex> mAllocator;
};

```

### `dragon::mesh::IndexSpanContext`
```
struct __cppobj dragon::mesh::IndexSpanContext
{
  dragon::mesh::IndexBufferResourceManager *mIbResourceManager;
  dragon::mesh::IndexSize mIndexSize;
  dragon::memory::SynchronizedPartitionedAllocator<dragon::mesh::IndexBufferAllocator,unsigned int> mPartitionedAllocator;
};

```

### `dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>`
```
struct __cppobj dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>
{
  std::map<unsigned int,std::list<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Page,std::allocator<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Page> >> mActivePages;
  std::map<unsigned int,std::vector<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Span,std::allocator<dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>::Span> >> mFreeBlocks;
  std::mutex mAccessLock;
  std::atomic<unsigned __int64> mBytesInUse;
  std::atomic<unsigned __int64> mTotalBytesAllocated;
  dragon::mesh::IndexSpanContext mContext;
};

```

### `dragon::mesh::IndexSpanRegistry`
```
struct __cppobj dragon::mesh::IndexSpanRegistry : dragon::mesh::SplitMergeBasedSpanRegistry<dragon::mesh::IndexSpanType,dragon::memory::BufferSource &&>
{
};

```

### `dragon::DragonBufferResourceServiceContext`
```
struct __cppobj dragon::DragonBufferResourceServiceContext
{
  gsl::not_null<dragon::mesh::VertexDeclManager *> mVertexDeclManager;
  gsl::not_null<dragon::mesh::VertexSpanRegistry *> mVertexSpanStorage;
  gsl::not_null<dragon::mesh::IndexSpanRegistry *> mIndexSpanStorage;
};

```

### `dragon::VertexBufferResourceService`
```
struct __cppobj dragon::VertexBufferResourceService : mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedVertexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
};

```

### `dragon::IndexBufferResourceService`
```
struct __cppobj dragon::IndexBufferResourceService : mce::CheckedResourceService<mce::resource_service_traits<dragon::mesh::ResolvedIndexBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
};

```

### `dragon::ShaderBufferResourceService`
```
struct __cppobj dragon::ShaderBufferResourceService : mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::DragonBufferResourceServiceContext> >
{
};

```

### `dragon::TaskQueueContext`
```
struct __cppobj dragon::TaskQueueContext
{
  mpmc::Sender<std::function<void __cdecl(void)> > queue;
};

```

### `dragon::TextureResourceService`
```
struct __cppobj dragon::TextureResourceService : mce::CheckedResourceService<mce::resource_service_traits<dragon::res::ResolvedTextureResource,mce::PerFrameHandleTracker,mce::SimpleResourceTracker,mce::AssertResourceServiceErrorHandler,dragon::TaskQueueContext> >
{
};

```

### `dragon::res::DragonFrameResources`
```
struct __cppobj dragon::res::DragonFrameResources
{
  MPMCQueue<dragon::res::ServerTexture> mTextures;
  dragon::res::ResolvedTextureResource *mMissingTextureResource;
};

```

### `dragon::materials::MaterialUniform`
```
struct __cppobj __declspec(align(4)) dragon::materials::MaterialUniform
{
  const dragon::materials::UniformType mType;
  const std::string mName;
  const unsigned __int64 mNameHash;
  const unsigned __int16 mCount;
  const std::optional<unsigned short> mHandle;
};

```

### `dragon::materials::MaterialUniformHandles`
```
struct __cppobj dragon::materials::MaterialUniformHandles
{
  std::vector<std::unique_ptr<dragon::materials::MaterialUniform>> mUniforms;
};

```

### `dragon::materials::definition::SemanticDescription`
```
struct __cppobj dragon::materials::definition::SemanticDescription
{
  _BYTE mInput[1];
  unsigned __int8 mIndex;
};

```

### `dragon::materials::definition::StageInputMap`
```
struct __cppobj dragon::materials::definition::StageInputMap
{
  std::unordered_set<dragon::materials::definition::SemanticDescription> mInputs;
};

```

### `dragon::materials::definition::ShaderInput`
```
struct __cppobj __declspec(align(2)) dragon::materials::definition::ShaderInput
{
  dragon::materials::definition::ShaderInputType mType;
  bool mIsPerInstance;
  dragon::materials::definition::SemanticDescription mSemantic;
  std::optional<enum dragon::materials::definition::PrecisionConstraint> mPrecisionConstraint;
  std::optional<enum dragon::materials::definition::InterpolationConstraint> mInterpolationConstraint;
};

```

### `dragon::materials::CompiledMaterialDefinition::ShaderCode`
```
struct __cppobj dragon::materials::CompiledMaterialDefinition::ShaderCode
{
  unsigned __int64 mSourceHash;
  std::vector<unsigned char> mData;
  std::unordered_map<std::string,dragon::materials::definition::ShaderInput> mInputs;
};

```

### `dragon::materials::definition::PropertyField<glm::tvec4<float,0>,std::optional<glm::tvec4<float,0> > >`
```
struct __cppobj dragon::materials::definition::PropertyField<glm::tvec4<float,0>,std::optional<glm::tvec4<float,0> > >
{
  int mArrayCount;
  std::optional<glm::tvec4<float,0> > mDefaultValue;
};

```

### `dragon::materials::definition::PropertyField<glm::tmat3x3<float,0>,std::optional<glm::tmat3x3<float,0> > >`
```
struct __cppobj dragon::materials::definition::PropertyField<glm::tmat3x3<float,0>,std::optional<glm::tmat3x3<float,0> > >
{
  int mArrayCount;
  std::optional<glm::tmat3x3<float,0> > mDefaultValue;
};

```

### `dragon::materials::definition::PropertyField<glm::tmat4x4<float,0>,std::optional<glm::tmat4x4<float,0> > >`
```
struct __cppobj dragon::materials::definition::PropertyField<glm::tmat4x4<float,0>,std::optional<glm::tmat4x4<float,0> > >
{
  int mArrayCount;
  std::optional<glm::tmat4x4<float,0> > mDefaultValue;
};

```

### `dragon::materials::definition::ExternalUniformDeclaration`
```
struct __cppobj dragon::materials::definition::ExternalUniformDeclaration
{
};

```

### `dragon::materials::definition::PropertyField<dragon::materials::definition::ExternalUniformDeclaration,std::optional<dragon::materials::definition::ExternalUniformDeclaration> >`
```
struct __cppobj __declspec(align(4)) dragon::materials::definition::PropertyField<dragon::materials::definition::ExternalUniformDeclaration,std::optional<dragon::materials::definition::ExternalUniformDeclaration> >
{
  int mArrayCount;
  std::optional<dragon::materials::definition::ExternalUniformDeclaration> mDefaultValue;
};

```

### `dragon::materials::definition::CustomTypeDeclaration::MemberType`
```
struct __cppobj dragon::materials::definition::CustomTypeDeclaration::MemberType
{
  std::string name;
  dragon::materials::definition::ShaderInputType type;
  unsigned int arraySize;
};

```

### `dragon::materials::definition::CustomTypeDeclaration`
```
struct __cppobj __declspec(align(8)) dragon::materials::definition::CustomTypeDeclaration
{
  std::string mName;
  std::vector<dragon::materials::definition::CustomTypeDeclaration::MemberType> mMembers;
  unsigned int mStride;
};

```

### `dragon::materials::CompiledMaterialDefinition`
```
const struct __cppobj dragon::materials::CompiledMaterialDefinition
{
  std::unordered_map<std::string,dragon::materials::CompiledMaterialDefinition::Pass> mPasses;
  std::string mName;
  std::optional<std::string > mParentName;
  std::unordered_map<std::string,std::variant<std::monostate,dragon::materials::definition::PropertyField<glm::tvec4<float,0>,std::optional<glm::tvec4<float,0> > >,dragon::materials::definition::PropertyField<glm::tmat3x3<float,0>,std::optional<glm::tmat3x3<float,0> > >,dragon::materials::definition::PropertyField<glm::tmat4x4<float,0>,std::optional<glm::tmat4x4<float,0> > >,dragon::materials::definition::PropertyField<dragon::materials::definition::ExternalUniformDeclaration,std::optional<dragon::materials::definition::ExternalUniformDeclaration> > >> mProperties;
  std::unordered_map<std::string,dragon::materials::definition::SamplerDefinition> mIndexedSamplers;
  std::unordered_map<std::string,dragon::materials::definition::CustomTypeDeclaration> mCustomTypes;
};

```

### `dragon::materials::PassProgram`
```
struct __cppobj __declspec(align(8)) dragon::materials::PassProgram
{
  dragon::materials::PassProgramType mType;
  std::optional<unsigned short> mProgram;
  dragon::materials::definition::StageInputMap mVertexInputDesc;
  bool mHasVertexStage;
};

```

### `dragon::materials::Pass`
```
struct __cppobj dragon::materials::Pass
{
  const unsigned int mMaterialId;
  const HashedString mName;
  const dragon::materials::CompiledMaterialDefinition::VariantSet mVariantSet;
  dragon::materials::definition::StageInputMap mCombinedVertexInputDesc;
  std::optional<dragon::materials::PassProgramHandle> mDefaultProgram;
  std::unordered_map<dragon::materials::CompiledMaterialDefinition::Variant const *,dragon::materials::PassProgram> mPrograms;
};

```

### `dragon::materials::SamplerSlot`
```
struct __cppobj __declspec(align(4)) dragon::materials::SamplerSlot
{
  int mSlot;
  std::string mName;
  unsigned __int64 mNameHash;
  std::string mPropertyName;
  std::string mCustomType;
  unsigned int mCustomTypeStride;
  dragon::materials::definition::SamplerAccess mAccess;
  bool mIsUAV;
};

```

### `dragon::materials::Material`
```
struct __cppobj dragon::materials::Material
{
  const unsigned int mId;
  const dragon::platform::GraphicsPlatform mPlatform;
  std::string mName;
  std::optional<std::string > mParentName;
  std::unique_ptr<dragon::materials::MaterialUniformMap> mDefaultUniforms;
  Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > mDefaultUniformsData;
  dragon::materials::MaterialUniformHandles mUniformHandles;
  dragon::materials::definition::StageInputMap mCombinedVertexInputDesc;
  std::vector<std::string> mPassNames;
  const std::unordered_map<std::string,std::string> mGlobalFlags;
  std::shared_ptr<dragon::materials::CompiledMaterialDefinition const > mSharedMaterialDefinition;
  boost::container::flat_map<HashedString,std::shared_ptr<dragon::materials::Pass>,std::less<HashedString>,boost::container::new_allocator<std::pair<HashedString,std::shared_ptr<dragon::materials::Pass> > > > mPasses;
  std::unordered_map<std::string,std::variant<std::monostate,dragon::materials::definition::PropertyField<glm::tvec4<float,0>,std::optional<glm::tvec4<float,0> > >,dragon::materials::definition::PropertyField<glm::tmat3x3<float,0>,std::optional<glm::tmat3x3<float,0> > >,dragon::materials::definition::PropertyField<glm::tmat4x4<float,0>,std::optional<glm::tmat4x4<float,0> > >,dragon::materials::definition::PropertyField<dragon::materials::definition::ExternalUniformDeclaration,std::optional<dragon::materials::definition::ExternalUniformDeclaration> > >> mProperties;
  std::unordered_map<std::string,dragon::materials::definition::SamplerDefinition> mIndexedSamplers;
  std::unordered_map<unsigned short,dragon::materials::SamplerSlot> mSamplerSlots;
};

```

### `dragon::rendering::PostFxDebugParameters`
```
struct __cppobj dragon::rendering::PostFxDebugParameters
{
  float mDebugMode;
  dragon::rendering::RtDebugType mType;
  _BYTE mDebugBlitMode[4];
  unsigned int mResourceIdx;
};

```

### `dragon::rendering::RayTracingResources`
```
const struct __cppobj __declspec(align(8)) dragon::rendering::RayTracingResources
{
  bool mRtxOn;
  bgfx::DLSSOptions mDlssOptions;
  bool mExecutePostFXinRTXOff;
  bool mDisplayResourcesAllocated;
  unsigned int mWidth;
  unsigned int mHeight;
  float mRenderScale;
  unsigned int mDoubleBufferWriteIdx;
  bgfx::RayTracingConfiguration mBgfxRayTracingConfiguration;
  dragon::rendering::ToneMappingParameters mToneMappingParams;
  dragon::rendering::BloomParameters mBloomParams;
  dragon::rendering::PostFxDebugParameters mPostFxDebugParams;
  dragon::res::ServerTexture mhRtBuffers[60];
  float mJitterSamples[128][2];
  unsigned int mCurrentJitterIdx;
  std::shared_ptr<std::vector<bgfx::PBRTextureData> > mPBRTextureData;
  bool mPBRTextureDataIsDirty;
};

```

### `dragon::mesh::ResolvedAccelerationStructure`
```
struct __cppobj dragon::mesh::ResolvedAccelerationStructure
{
  bgfx::AccelerationStructureHandle mResource;
};

```

### `dragon::mesh::ResolvedAccelerationStructureResource`
```
struct __cppobj dragon::mesh::ResolvedAccelerationStructureResource : dragon::mesh::ResolvedAccelerationStructure
{
};

```

### `dragon::frameobject::components::ShadowSource`
```
struct __cppobj dragon::frameobject::components::ShadowSource
{
  dragon::frameobject::ShadowQuality mQuality;
};

```

### `dragon::frameobject::components::Cubemap`
```
struct __cppobj dragon::frameobject::components::Cubemap
{
};

```

### `dragon::frameobject::components::SceneSky`
```
struct __cppobj dragon::frameobject::components::SceneSky
{
};

```

### `dragon::frameobject::components::PostEffect::DescBloom`
```
struct dragon::frameobject::components::PostEffect::DescBloom
{
  float dummyNotUsed;
};

```

### `dragon::frameobject::components::PostEffect::DescTAA`
```
struct dragon::frameobject::components::PostEffect::DescTAA
{
  float dummyNotUsed;
};

```

### `dragon::frameobject::components::PostEffect::DescToneMapping`
```
struct dragon::frameobject::components::PostEffect::DescToneMapping
{
  float dummyNotUsed;
};

```

### `dragon::frameobject::components::PostEffect`
```
struct __cppobj dragon::frameobject::components::PostEffect
{
  unsigned int mEnabled;
  std::optional<dragon::frameobject::components::PostEffect::DescBloom> mDescBloom;
  std::optional<dragon::frameobject::components::PostEffect::DescTAA> mDescTAA;
  std::optional<dragon::frameobject::components::PostEffect::DescToneMapping> mDescToneMapping;
};

```

### `dragon::frameobject::components::PointLight`
```
struct __cppobj dragon::frameobject::components::PointLight
{
};

```

### `dragon::frameobject::components::AmbientLight`
```
struct __cppobj dragon::frameobject::components::AmbientLight
{
};

```

### `dragon::frameobject::components::DirectionalLight`
```
struct __cppobj dragon::frameobject::components::DirectionalLight
{
};

```

### `dragon::frameobject::components::defaultpasses::PostFX`
```
struct dragon::frameobject::components::defaultpasses::PostFX
{
  unsigned __int64 mSortKey;
};

```

### `dragon::frameobject::components::defaultpasses::Blit`
```
struct __cppobj dragon::frameobject::components::defaultpasses::Blit
{
};

```

### `dragon::frameobject::components::ComputeDispatch`
```
struct __cppobj __declspec(align(8)) dragon::frameobject::components::ComputeDispatch
{
  HashedString mPassName;
  glm::tvec3<int,0> mThreadGroupCount;
};

```

### `dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>`
```
struct __cppobj dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::compone
{
  _BYTE gap0[168];
  std::unique_ptr<Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope,std::default_delete<Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope> > *mFrameAllocator;
};

```

### `dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>`
```
struct __cppobj dragon::frameobject::Frame<mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce:
{
  Core::SharedMemoryTracker mFrameTrackedMemory;
  dragon::res::DragonFrameResources mFrameResources;
  std::unique_ptr<Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope,std::default_delete<Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope> > mFrameAllocationScope;
  dragon::mesh::VertexDeclManager mVertexDeclManager;
  dragon::DragonBufferResourceServiceContext mBufferResourceServiceContext;
  dragon::IndexBufferResourceService mIndexBufferResourceService;
  dragon::VertexBufferResourceService mVertexBufferResourceService;
  dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources> mRegistry;
  std::optional<unsigned __int64> mFrameNumber;
  std::vector<mce::ServerResourcePointer<mce::ResourcePointer<dragon::res::ResolvedShaderBufferResource,mce::ResourceBlockTemplate<dragon::res::ResolvedShaderBufferResource,mce::UncheckedHandleTracker,dragon::BufferDescription>,std::shared_ptr>,mce::AssertResourceServiceErrorHandler>> mActiveShaderBuffers;
};

```

