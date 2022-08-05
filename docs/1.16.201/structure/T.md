# T
### `tm`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | tm_sec
4 | (4) `int` | tm_min
8 | (4) `int` | tm_hour
12 | (4) `int` | tm_mday
16 | (4) `int` | tm_mon
20 | (4) `int` | tm_year
24 | (4) `int` | tm_wday
28 | (4) `int` | tm_yday
32 | (4) `int` | tm_isdst


### `Tick`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | tickID


### `TerrainMaterialVariationManager`
Offset | Type | Name
-|-|-|-
0 | (4) `mce::RenderingProfile` | mRenderingProfile
8 | (8) `mce::RenderMaterialGroup *` | mRenderMaterialGroup
16 | (32) `std::string` | mVariationName
48 | (32) `std::string` | mFullVariationName
80 | (32) `std::string` | mFullParentVariationName
112 | (16) `std::map<enum TerrainVariation,TerrainMaterialVariationManager>` | mSubVariations
128 | (16) `std::map<TerrainLayer const *,mce::MaterialPtr>` | terrainLayerMaterialMap


### `typeid_t<IScreenCapabilities>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mID


### `TextureAtlasItem`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `int` | mParsedNodeIndex
40 | (24) `std::vector<std::vector<TextureUVCoordinateSet>>` | mTextureUVs


### `TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper_vtbl *` | __vftable


### `TextureAtlas::recreateAtlas::__l2::<lambda_b4cd09a31552d66f59ead337c2c8f72a>`
Offset | Type | Name
-|-|-|-


### `TreatmentPackDownloadMonitor::buildTreatmentStackPack::__l5::<lambda_3b2a49ec1524b669fbce386f9d135c28>`
Offset | Type | Name
-|-|-|-


### `TouchContactPoints`
Offset | Type | Name
-|-|-|-
0 | (48) `std::array<int,12>` | mTouchIDLookup


### `tagPOINT`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y


### `typeid_t<CommandRegistry>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mID


### `TextureSetHelpers::NamePair`
Offset | Type | Name
-|-|-|-
0 | (4) `cg::TextureSetLayerType` | layerType
8 | (32) `const std::string` | jsonLayerPropertyNames


### `typeid_t<EntityGoalFactory>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mID


### `TagMemoryChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mElements
8 | (8) `unsigned __int64` | mSize
16 | (8) `std::unique_ptr<unsigned char [0]>` | mBuffer


### `typeid_t<IAppConfigData>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mID


### `ThreadConfiguration`
Offset | Type | Name
-|-|-|-
0 | (4) `Bedrock::Threading::OSThreadPriority` | Priority
8 | (16) `std::optional<unsigned __int64>` | CoreAffinityMask
24 | (4) `int` | IdealCore


### `Tag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag_vtbl *` | __vftable


### `tDownloadInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | cdnFileUrl
32 | (32) `std::string` | outFilePath
64 | (1) `bool` | resumeFromBreak
72 | (8) `__int64` | resumeFromOffset
80 | (4) `int` | currentFileSize
84 | (4) `int` | downloadFileSize
88 | (4) `std::atomic<int>` | status
96 | (16) `std::shared_ptr<DownloadCallback>` | callback


### `TransferHandler`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mNeedTransferServer
8 | (16) `std::shared_ptr<NetworkHandler>` | mNetworkHandler
24 | (8) `TransferPacketHandler *` | mTransferPacketHandler
32 | (4) `unsigned int` | mHostUserId
36 | (4) `unsigned int` | mRoomId
40 | (184) `TransferHandler::<unnamed_type_mHostMode>` | mHostMode
224 | (1) `bool` | mIsSetHostMode
232 | (80) `SPSCQueue<unsigned int,512>` | mKickOutIds
312 | (1) `bool` | mIsQuit


### `TransferHandler::<unnamed_type_mHostMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | localConnector
4 | (4) `unsigned int` | userId
8 | (32) `std::string` | userToken
40 | (1) `unsigned __int8` | maxClientCount
44 | (4) `TransferRoomPrivacy` | privacy
48 | (4) `TransferRoomPlatform` | allowPe
56 | (32) `std::string` | roomName
88 | (32) `std::string` | levelId
120 | (4) `GameType` | gameType
124 | (2) `unsigned __int16` | ipv4Port
126 | (2) `unsigned __int16` | ipv6Port
128 | (24) `std::vector<unsigned char>` | tagIds
152 | (32) `std::string` | createRoomExtraBits


### `traceback_t`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | hash
4 | (4) `int` | nframe
8 | (16) `frame_t[1]` | frames


### `TradeInterestGoal::canUse::__l2::<lambda_0d1ef5e65fe9e0f12991fabfa234365c>`
Offset | Type | Name
-|-|-|-
0 | (8) `TradeInterestGoal *const` | __this


### `T1_FieldRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | ident
8 | (4) `T1_FieldLocation_` | location
12 | (4) `T1_FieldType_` | type
16 | (8) `void (__fastcall *)(FT_FaceRec_ *, void *)` | reader
24 | (4) `unsigned int` | offset
28 | (1) `unsigned __int8` | size
32 | (4) `unsigned int` | array_max
36 | (4) `unsigned int` | count_offset
40 | (4) `unsigned int` | dict


### `tt_sfnt_id_rec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | CheckSum
4 | (4) `unsigned int` | Length


### `TerrainLayer`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int64` | id
8 | (4) `_BYTE[4]` | transparency
16 | (32) `const std::string` | name
48 | (8) `unsigned __int64` | triangleCount


### `TintMapColor`
Offset | Type | Name
-|-|-|-
0 | (64) `std::array<mce::Color,4>` | colors


### `TaskResult`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsDone
8 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | mRunAtTime
16 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >` | mWaitOperation
32 | (1) `bool` | mLinkWaitOperation


### `TT_GraphicsState_`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | rp0
2 | (2) `unsigned __int16` | rp1
4 | (2) `unsigned __int16` | rp2
6 | (4) `FT_UnitVector_` | dualVector
10 | (4) `FT_UnitVector_` | projVector
14 | (4) `FT_UnitVector_` | freeVector
20 | (4) `int` | loop
24 | (4) `int` | minimum_distance
28 | (4) `int` | round_state
32 | (1) `unsigned __int8` | auto_flip
36 | (4) `int` | control_value_cutin
40 | (4) `int` | single_width_cutin
44 | (4) `int` | single_width_value
48 | (2) `unsigned __int16` | delta_base
50 | (2) `unsigned __int16` | delta_shift
52 | (1) `unsigned __int8` | instruct_control
53 | (1) `unsigned __int8` | scan_control
56 | (4) `int` | scan_type
60 | (2) `unsigned __int16` | gep0
62 | (2) `unsigned __int16` | gep1
64 | (2) `unsigned __int16` | gep2


### `ThirdPartyInfo`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_set<std::string>` | mAllowListUrls
64 | (32) `std::string` | mCreatorId
96 | (32) `std::string` | mCreatorName
128 | (1) `bool` | mRequireXBL


### `TT_CMap_ClassRec_`
Offset | Type | Name
-|-|-|-
0 | (80) `FT_CMap_ClassRec_` | clazz
80 | (4) `unsigned int` | format
88 | (8) `int (__fastcall *)(unsigned __int8 *, volatile FT_ValidatorRec_ *)` | validate
96 | (8) `int (__fastcall *)(FT_CharMapRec_ *, TT_CMapInfo_ *)` | get_cmap_info


### `T1_Builder_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(T1_BuilderRec_ *, FT_FaceRec_ *, FT_SizeRec_ *, FT_GlyphSlotRec_ *, unsigned __int8)` | init
8 | (8) `void (__fastcall *)(T1_BuilderRec_ *)` | done
16 | (8) `int (__fastcall *)(T1_BuilderRec_ *, int)` | check_points
24 | (8) `void (__fastcall *)(T1_BuilderRec_ *, int, int, unsigned __int8)` | add_point
32 | (8) `int (__fastcall *)(T1_BuilderRec_ *, int, int)` | add_point1
40 | (8) `int (__fastcall *)(T1_BuilderRec_ *)` | add_contour
48 | (8) `int (__fastcall *)(T1_BuilderRec_ *, int, int)` | start_point
56 | (8) `void (__fastcall *)(T1_BuilderRec_ *)` | close_contour


### `TextureUVCoordinateSet`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | weight
4 | (4) `float` | _u0
8 | (4) `float` | _v0
12 | (4) `float` | _u1
16 | (4) `float` | _v1
20 | (2) `unsigned __int16` | _texSizeW
22 | (2) `unsigned __int16` | _texSizeH
24 | (56) `ResourceLocation` | sourceFileLocation
80 | (8) `IsotropicFaceData` | mIsotropicFaceData
88 | (2) `__int16` | textureSetTranslationIndex
90 | (2) `unsigned __int16` | mPBRTextureDataHandle


### `TypedServerNetId<ItemStackNetIdTag,int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRawId


### `TypedClientNetId<ItemStackRequestIdTag,int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRawId


### `TypedClientNetId<ItemStackLegacyRequestIdTag,int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRawId


### `TextureTint`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPath
32 | (32) `std::string` | mTintMap
64 | (64) `TintMapColor` | mTintBaseColor
128 | (64) `TintMapColor` | mTintColor
192 | (1) `bool` | mUseTint
193 | (1) `bool` | mAnimated
196 | (4) `int` | mAnimationFrames
200 | (8) `Pack *` | mSourcePack


### `TextureAtlasItemTextureSetTranslation`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::variant<TextureAtlasItemTextureSetTranslation::Translation,TextureAtlasItemTextureSetTranslation::ColorUniform,TextureAtlasItemTextureSetTranslation::NormalTranslation,TextureAtlasItemTextureSetTranslation::MERTranslation,TextureAtlasItemTextureSetTranslation::MERUniform,TextureAtlasItemTextureSetTranslation::Uniform,TextureAtlasItemTextureSetTranslation::SingleChannelTranslation>>` | layers


### `T1_CMap_ClassesRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `const FT_CMap_ClassRec_ *` | standard
8 | (8) `const FT_CMap_ClassRec_ *` | expert
16 | (8) `const FT_CMap_ClassRec_ *` | custom
24 | (8) `const FT_CMap_ClassRec_ *` | unicode


### `TypeMapping`
Offset | Type | Name
-|-|-|-
0 | (1) `char` | inputType
8 | (8) `const char *` | type


### `T1_Decoder_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(T1_DecoderRec_ *, FT_FaceRec_ *, FT_SizeRec_ *, FT_GlyphSlotRec_ *, unsigned __int8 **, PS_BlendRec_ *, unsigned __int8, FT_Render_Mode_, int (__fastcall *)(T1_DecoderRec_ *, unsigned int))` | init
8 | (8) `void (__fastcall *)(T1_DecoderRec_ *)` | done
16 | (8) `int (__fastcall *)(T1_DecoderRec_ *, unsigned __int8 *, unsigned int)` | parse_metrics
24 | (8) `int (__fastcall *)(PS_Decoder_ *, unsigned __int8 *, unsigned int)` | parse_charstrings


### `TryBlockMapEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `` | tryLow
4 | (4) `` | tryHigh
8 | (4) `` | catchHigh
12 | (4) `` | nCatches
16 | (4) `` | pHandlerArray


### `TypeDescriptor`
Offset | Type | Name
-|-|-|-
0 | (8) `` | pVFTable
8 | (8) `` | spare
16 | (0) `` | name


### `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkPipeline,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkPipeline> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkPipeline> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkPipeline> **` | first
8 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkPipeline> **` | last
16 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkPipeline> **` | capacity


### `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkDescriptorSetLayout,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkDescriptorSetLayout> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkDescriptorSetLayout> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkDescriptorSetLayout> **` | first
8 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkDescriptorSetLayout> **` | last
16 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkDescriptorSetLayout> **` | capacity


### `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkRenderPass,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkRenderPass> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkRenderPass> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkRenderPass> **` | first
8 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkRenderPass> **` | last
16 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkRenderPass> **` | capacity


### `tinystl::unordered_map<unsigned __int64,bgfx::vk::VkSampler,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> **` | first
8 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> **` | last
16 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> **` | capacity


### `TropicalFishInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mColor
4 | (4) `int` | mColor2
8 | (4) `int` | mVariant
12 | (4) `int` | mMarkVariant
16 | (32) `std::string` | mName


### `TaskStartInfoEx<void>`
Offset | Type | Name
-|-|-|-
0 | (40) `TaskStartInfoBase` | baseclass_0
40 | (16) `std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >` | predecessor


### `TaskStartInfoBase`
Offset | Type | Name
-|-|-|-
0 | (16) `gsl::basic_string_span<char const ,-1>` | name
16 | (4) `std::thread::id` | affinity
20 | (4) `unsigned int` | priority
24 | (4) `int` | priorityBackDown
28 | (4) `TaskOptions` | options
32 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | startAtTime


### `TextObjectRoot`
Offset | Type | Name
-|-|-|-
0 | (8) `ITextObject` | baseclass_0
8 | (24) `std::vector<std::unique_ptr<ITextObject>>` | mChildren


### `typeid_t<ContentLog>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mID


### `TouchPoint`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | id
4 | (4) `TouchState` | state
8 | (4) `float` | x
12 | (4) `float` | y
16 | (1) `bool` | mCaptured
17 | (1) `bool` | mStartedInactive


### `TextEditScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `int` | index
8 | (1) `bool` | finished
16 | (8) `UIPropertyBag *` | properties
24 | (4) `_BYTE[4]` | result
28 | (1) `bool` | hasSelectedTextBox


### `ToggleChangeEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `int` | index
8 | (1) `bool` | state
9 | (1) `bool` | toggledByButtonClick
16 | (8) `UIPropertyBag *` | properties
24 | (8) `unsigned __int64` | itemStringHash


### `TextEditSelectedStateChangeEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `int` | index
8 | (1) `bool` | selected


### `TrueTypeFont::PageOfGlyphs`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<int>` | codepoints
24 | (64) `std::unordered_map<int,int>` | codepointMap
88 | (24) `std::vector<stbtt_packedchar>` | packedCharacters
112 | (4) `int` | atlasPageSize
116 | (1) `bool` | pageLocked
120 | (56) `ResourceLocation` | resourceLocationToUpload
176 | (16) `std::shared_ptr<cg::ImageBuffer>` | imageBufferToUpload


### `tAppPkgInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | pkgChn
32 | (32) `std::string` | pkgVer
64 | (32) `std::string` | pkgUrl


### `TextObjectParser::ErrorLocalization`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mErrorLocalizationString
32 | (24) `std::vector<std::string>` | mLocalizationParameters


### `TitleMessage`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mTitle
32 | (32) `std::string` | mSubtitle
64 | (4) `int` | mFadeInTime
68 | (4) `int` | mStayTime
72 | (4) `int` | mFadeOutTime
80 | (32) `std::string` | mActionBarMessage


### `TypedScreenCapabilities<SettingsScreenCapabilities>`
Offset | Type | Name
-|-|-|-
0 | (8) `IScreenCapabilities` | baseclass_0


### `Trade2ScreenController::TradeItemCollections`
Offset | Type | Name
-|-|-|-
0 | (16) `const Json::Value` | mCollections
16 | (2) `std::optional<bool>` | mHasTradeItem1Collection
18 | (2) `std::optional<bool>` | mHasTradeItem2Collection
20 | (2) `std::optional<bool>` | mHasSellItemCollection
22 | (2) `std::optional<bool>` | mHasValidTradeItemCollections
24 | (2) `std::optional<bool>` | mHasValidTradeToggleCollections
28 | (8) `std::optional<int>` | mTierIndex
36 | (8) `std::optional<int>` | mTradeIndex
48 | (16) `std::optional<MerchantRecipe *>` | mTrade


### `TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>::_searchItemsByTreatment::__l2::<lambda_e985b95cf47085b084b2f896a314c77e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> >` | weakThis
16 | (24) `const std::vector<std::string>` | treatments
40 | (4) `const unsigned int` | queryId


### `TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>::_searchItemsByTreatment::__l2::<lambda_f0d0b224456a960fbce51bd76243ee88>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> >` | weakThis
16 | (24) `const std::vector<std::string>` | treatments
40 | (4) `const unsigned int` | queryId


### `TextPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `TextPacketType` | mType
48 | (32) `std::string` | mAuthor
80 | (32) `std::string` | mMessage
112 | (24) `std::vector<std::string>` | params
136 | (1) `bool` | mLocalize
144 | (32) `std::string` | mXuid
176 | (32) `std::string` | mPlatformId


### `TextureState`
Offset | Type | Name
-|-|-|-
0 | (72) `mce::TexturePtr` | mTexturePtr
72 | (1) `bool` | mActive


### `TextCharEventData`
Offset | Type | Name
-|-|-|-
0 | (5) `std::array<char,5>` | utf8text
5 | (1) `bool` | keepImePosition


### `TextureTessellator`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mCloudLighting


### `TextureOffset`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y


### `TrustedSkinHelper`
Offset | Type | Name
-|-|-|-
0 | (152) `NetworkIdentifier` | mNetworkIdentifier
152 | (16) `std::weak_ptr<Options const >` | mPrimaryOptions
168 | (8) `gsl::not_null<Social::MultiplayerServiceManager *>` | mMultiplayerServiceManager
176 | (16) `std::weak_ptr<Social::User>` | mUser
192 | (16) `std::map<mce::UUID,bool>` | mIsTrustedClientMapCache


### `Tessellator`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsFormatFixed
8 | (240) `mce::MeshData` | mMeshData
248 | (20) `std::optional<glm::tvec4<float,0> >` | mNextNormal
268 | (36) `std::optional<glm::tvec2<float,0> >[3]` | mNextUV
304 | (8) `std::optional<unsigned int>` | mNextColor
312 | (4) `std::optional<unsigned short>` | mNextBoneId
316 | (4) `std::optional<unsigned short>` | mNextPBRTextureIdx
320 | (1) `bool` | mIndexPhase
324 | (12) `Vec3` | mPostTransformOffset
336 | (12) `Vec3` | mPostTransformScale
348 | (1) `unsigned __int8` | mQuadFacing
349 | (1) `bool` | mQuadTwoSided
352 | (24) `std::vector<TessellatorQuadInfo>` | mQuadInfoList
376 | (12) `Vec3` | mFaceCenterAccumulator
388 | (4) `int` | mCurQuadVertex
392 | (1) `bool` | mApplyTransform
396 | (64) `glm::tmat4x4<float,0>` | mTransformMatrix
460 | (1) `bool` | mNoColor
461 | (1) `bool` | mVoidBeginEnd
462 | (1) `bool` | mForceTessellateIntercept
464 | (64) `std::function<void __cdecl(Tessellator const &,mce::MaterialPtr const &,mce::TexturePtr const &)>` | mInterceptTessellator
528 | (4) `unsigned int` | mCount
532 | (1) `bool` | mTessellating
533 | (1) `bool` | mBuildFaceData
536 | (8) `std::unique_ptr<mce::Mesh>` | mPreGeneratedMesh
544 | (16) `std::weak_ptr<mce::BufferResourceService>` | mBufferResourceService


### `TerrainCommands`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<CommandListFuture>` | chunksOpaqueSeasons
24 | (24) `std::vector<CommandListFuture>` | chunksOpaque
48 | (24) `std::vector<CommandListFuture>` | chunksEndPortal
72 | (24) `std::vector<CommandListFuture>` | chunksBarrierBlock
96 | (24) `std::vector<CommandListFuture>` | chunksStructureVoidBlock
120 | (24) `std::vector<CommandListFuture>` | chunksDoubleSide
144 | (24) `std::vector<CommandListFuture>` | chunksFarSeasons
168 | (24) `std::vector<CommandListFuture>` | chunksFarSeasonsAlpha
192 | (24) `std::vector<CommandListFuture>` | chunksFar
216 | (24) `std::vector<CommandListFuture>` | chunksAlpha
240 | (24) `std::vector<CommandListFuture>` | chunksAlphaSingleSide
264 | (24) `std::vector<CommandListFuture>` | chunksAlphaSeasons
288 | (24) `std::vector<CommandListFuture>` | chunksBlendFarOther
312 | (24) `std::vector<CommandListFuture>` | chunksBlendOther
336 | (24) `std::vector<CommandListFuture>` | chunksBlendFarSame
360 | (24) `std::vector<CommandListFuture>` | chunksBlendSame
384 | (24) `std::vector<CommandListFuture>` | chunksRayTracedWater
408 | (24) `std::vector<CommandListFuture>` | chunksBlendWaterNearSame
432 | (24) `std::vector<CommandListFuture>` | chunksBlendWaterFarSame
456 | (24) `std::vector<CommandListFuture>` | chunksBlendAlphaMicroBlock


### `TextureAtlasTile`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<TextureData>` | textureDataCollection
24 | (24) `std::vector<TextureUVCoordinateSet *>` | uvs
48 | (16) `mce::Color` | overlay
64 | (1) `bool` | quad
68 | (4) `float` | mipFadeRate
72 | (16) `mce::Color` | mipFadeColor
88 | (1) `bool` | isAdditive
89 | (1) `bool` | loadedTextures
92 | (4) `cg::TextureSetLayerType` | mTextureSetLayerType
96 | (4) `unsigned int` | tileWidth
100 | (4) `unsigned int` | tileHeight


### `TextureData`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | location
56 | (72) `std::optional<cg::ImageDescription>` | imageDescription
128 | (56) `ResourceLocation` | tintMapLocation
184 | (72) `std::optional<cg::ImageDescription>` | tintMapImageDescription
256 | (16) `mce::Color` | tintColor
272 | (64) `TintMapColor` | multiChannelTintBaseColor
336 | (64) `TintMapColor` | multiChannelTintColor
400 | (1) `bool` | multiChannelTint
404 | (4) `cg::TextureSetLayerType` | mTextureSetLayerType


### `TextureHotReloader::registerTexture::__l2::<lambda_d19440a49b67ab4c701b7d6018d1d57a>`
Offset | Type | Name
-|-|-|-
0 | (56) `const ResourceLocation` | resLoc
56 | (56) `const ResourceLocation` | fullResourceLocation
112 | (64) `std::function<void __cdecl(ResourceLocation const &)>` | textureReloadCallback
176 | (8) `TextureHotReloader *const` | __this
184 | (8) `mce::TextureGroup *` | textureGroup


### `TextureHotReloader::registerAtlas::__l17::<lambda_e6a985aa285298526d00c4debf11172a>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(enum TextureAtlasStatus const &)>` | textureAtlasStatusCallback
64 | (64) `std::function<void __cdecl(ResourceLocation const &)>` | textureAtlasReloadCallback
128 | (1) `const MipMapSupport` | mipMapSupport
136 | (8) `std::function<void __cdecl(TextureAtlasResourceCallbacks)> *` | textureAtlasTaskEnqueueCallback
144 | (8) `TextureAtlas *` | textureAtlas
152 | (8) `mce::TextureGroup *` | textureGroup
160 | (8) `MinecraftGameplayGraphicsResources *` | minecraftGameplayGraphicsResources


### `TextureHotReloader::registerAtlas::__l17::<lambda_e6a985aa285298526d00c4debf11172a>::()::__l2::<lambda_3afaa43a3801353c84e3cfcd831e61a4>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(ResourceLocation const &)>` | textureAtlasReloadCallback
64 | (56) `const ResourceLocation` | fullResourceLocation


### `TreatmentPackMetadata`
Offset | Type | Name
-|-|-|-
0 | (64) `DateRange` | mDateRange
64 | (32) `std::string` | mRequiredTreatmentTag
96 | (32) `std::string` | mMinClientVersion
128 | (32) `std::string` | mMaxClientVersion
160 | (4) `int` | mPriority


### `ToastManager::pushNotificationReceived::__l8::<lambda_ea7bf187b5e06244cc520f7a0ac3d28d>`
Offset | Type | Name
-|-|-|-
0 | (8) `ToastManager *const` | __this
8 | (88) `const PushNotificationMessage` | msg


### `ToastFetcher::_processQueryResults::__l25::<lambda_5f20b6d3bbb0086d9f0765cdb6a274b0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ToastFetcher>` | weakThis
16 | (792) `const PromotionToastDocument` | toastDoc


### `TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>::_searchItemsByTreatment::__l2::<lambda_f774b8bad2c471843a0d320293710300>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> >` | weakThis
16 | (24) `const std::vector<std::string>` | treatments
40 | (4) `const unsigned int` | queryId


### `TreatmentQuery<SalesSearchResults,SalesDocument>::_searchItemsByTreatment::__l2::<lambda_aea4d7b104890074629d18fc30a151d4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<TreatmentQuery<SalesSearchResults,SalesDocument> >` | weakThis
16 | (24) `const std::vector<std::string>` | treatments
40 | (4) `const unsigned int` | queryId


### `TextToSpeechClient_flite::speakText::__l13::<lambda_68f502a62989c797c7648cd555e3232c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<TextToSpeechClient_flite>` | weakThis
16 | (32) `const std::string` | text


### `tagRAWINPUTDEVICE`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | usUsagePage
2 | (2) `unsigned __int16` | usUsage
4 | (4) `unsigned int` | dwFlags
8 | (8) `HWND__ *` | hwndTarget


### `tagMSG`
Offset | Type | Name
-|-|-|-
0 | (8) `HWND__ *` | hwnd
8 | (4) `unsigned int` | message
16 | (8) `unsigned __int64` | wParam
24 | (8) `__int64` | lParam
32 | (4) `unsigned int` | time
36 | (8) `tagPOINT` | pt


### `tagRECT`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | left
4 | (4) `int` | top
8 | (4) `int` | right
12 | (4) `int` | bottom


### `tagTOUCHINPUT`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y
8 | (8) `void *` | hSource
16 | (4) `unsigned int` | dwID
20 | (4) `unsigned int` | dwFlags
24 | (4) `unsigned int` | dwMask
28 | (4) `unsigned int` | dwTime
32 | (8) `unsigned __int64` | dwExtraInfo
40 | (4) `unsigned int` | cxContact
44 | (4) `unsigned int` | cyContact


### `tagMONITORINFO`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | cbSize
4 | (16) `tagRECT` | rcMonitor
20 | (16) `tagRECT` | rcWork
36 | (4) `unsigned int` | dwFlags


### `type_safe::strong_typedef<dragon::materials::ParameterId,unsigned short>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | value_


### `TextureSetHelpers::TextureSetDefinitionLoader::_loadImageLayers::__l17::layerConstraints`
Offset | Type | Name
-|-|-|-
0 | (4) `cg::TextureSetLayerType` | layerType
4 | (1) `bool` | mandatory
8 | (24) `std::vector<int>` | supportedImageChannelCounts


### `Trade`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMaxUses
4 | (1) `bool` | mRewardExperience
8 | (4) `int` | mWeight
12 | (4) `unsigned int` | mTraderExperience
16 | (4) `int` | mPrimaryOfferCount
24 | (24) `std::vector<std::vector<TradeItem>>` | mOffer
48 | (24) `std::vector<std::vector<TradeItem>>` | mReceive


### `TimerComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTime
8 | (8) `unsigned __int64` | mTimeStamp
16 | (1) `bool` | mHasExecuted
17 | (1) `bool` | mLooping
20 | (4) `int` | mStartTime
24 | (1) `bool` | mRandomInterval
28 | (4) `int` | mMinTime
32 | (4) `int` | mMaxTime
40 | (320) `DefinitionTrigger` | mOnTimeDown
360 | (24) `WeightedChoices<float>` | mTimeChoices


### `TypedServerNetId<RecipeNetIdTag,unsigned int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `TypedServerNetId<CreativeItemNetIdTag,unsigned int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `TextObjectParser::ServerData`
Offset | Type | Name
-|-|-|-
0 | (8) `const gsl::not_null<CommandRegistry::Parser *>` | mParser
8 | (8) `const gsl::not_null<CommandOrigin const *>` | mCommandOrigin
16 | (8) `const gsl::not_null<Scoreboard const *>` | mScoreboard


### `TickWorldComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mChunkRadius
4 | (4) `float` | mMaxDistToPlayers
8 | (1) `bool` | mAlwaysActive
9 | (1) `bool` | mChanged
16 | (16) `std::weak_ptr<ITickingArea>` | mTickingArea


### `Token`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mText
32 | (4) `$43394D8BCE5B19B713CE0E76E20E677C` | ___u1
36 | (4) `Token::Type` | mType
40 | (1) `bool` | mIsDefault


### `TrustingComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mChance
8 | (16) `std::set<Item const *>` | mTrustItems


### `TemporalAttributeBuff`
Offset | Type | Name
-|-|-|-
0 | (88) `AttributeBuff` | baseclass_0
88 | (4) `int` | mDuration
92 | (4) `int` | mLifeTimer
96 | (4) `float` | mBaseAmount
100 | (1) `bool` | mIsSerializable


### `TypedRuntimeId<ContainerRuntimeIdTag,unsigned int,0>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mRawId


### `Trade2ContainerManagerController`
Offset | Type | Name
-|-|-|-
0 | (136) `ContainerManagerController` | baseclass_0
136 | (16) `std::weak_ptr<Trade2ContainerManagerModel>` | mTradeContainerManagerModel
152 | (1) `bool` | mSelectBestTradeOnItemPlace
160 | (40) `const SlotData` | mCreatedItemOutputSlot
200 | (240) `ItemInstance` | mResultPreviewItem


### `TradeItem`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | itemId
4 | (4) `int` | itemAux
8 | (4) `int` | count_min
12 | (4) `int` | count_max
16 | (4) `float` | price_multiplier
24 | (24) `std::vector<std::unique_ptr<LootItemFunction>>` | functions


### `TradeGroup`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mNumToSelect
8 | (24) `std::vector<Trade>` | mTrades


### `TradeTier`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mExpToUnlock
8 | (24) `std::vector<TradeGroup>` | mGroups


### `TickNextTickData`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | pos
16 | (8) `const Block *` | mBlock
24 | (8) `Tick` | tick
32 | (4) `int` | priorityOffset


### `TickDelayBlock`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTickDelay
8 | (8) `const Block *` | mBlock


### `TreeHelper::AttachableDecoration::DirectionMask`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mWest
1 | (1) `bool` | mEast
2 | (1) `bool` | mNorth
3 | (1) `bool` | mSouth


### `tagOFNA`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | lStructSize
8 | (8) `HWND__ *` | hwndOwner
16 | (8) `HINSTANCE__ *` | hInstance
24 | (8) `const char *` | lpstrFilter
32 | (8) `char *` | lpstrCustomFilter
40 | (4) `unsigned int` | nMaxCustFilter
44 | (4) `unsigned int` | nFilterIndex
48 | (8) `char *` | lpstrFile
56 | (4) `unsigned int` | nMaxFile
64 | (8) `char *` | lpstrFileTitle
72 | (4) `unsigned int` | nMaxFileTitle
80 | (8) `const char *` | lpstrInitialDir
88 | (8) `const char *` | lpstrTitle
96 | (4) `unsigned int` | Flags
100 | (2) `unsigned __int16` | nFileOffset
102 | (2) `unsigned __int16` | nFileExtension
104 | (8) `const char *` | lpstrDefExt
112 | (8) `__int64` | lCustData
120 | (8) `unsigned __int64 (__fastcall *)(HWND__ *, unsigned int, unsigned __int64, __int64)` | lpfnHook
128 | (8) `const char *` | lpTemplateName
136 | (8) `void *` | pvReserved
144 | (4) `unsigned int` | dwReserved
148 | (4) `unsigned int` | FlagsEx


### `timeval`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | tv_sec
4 | (4) `int` | tv_usec


### `TransformConditions`
Offset | Type | Name
-|-|-|-
0 | (8) `TransformConditionBrightness` | mBrightness
8 | (40) `TransformConditionSurrounding` | mSurrounding
48 | (4) `TransformConditionInt` | mTickCount


### `TransformConditionBrightness`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | max
4 | (4) `int` | min


### `TransformConditionSurrounding`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | value
32 | (4) `int` | radius


### `TransformConditionInt`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | value


### `TransformComponent`
Offset | Type | Name
-|-|-|-
0 | (56) `TransformConditions` | mConditions
56 | (32) `std::string` | mResult


### `TouchInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<TouchTextButtonBinding>` | textButtonBindings
24 | (24) `std::vector<TouchGlyphButtonBinding>` | glyphButtonBindings
48 | (24) `std::vector<TouchGlyphButtonBindingEX>` | glyphButtonBindingEXs
72 | (24) `std::vector<TouchGlyphRadioButtonBinding>` | glyphRadioButtonBinding
96 | (24) `std::vector<TouchJoystickBinding>` | joystickBindings
120 | (24) `std::vector<TouchCameraJoystickBinding>` | cameraJoyskickBindings
144 | (24) `std::vector<std::string>` | multiPointerButtonNames
168 | (168) `TouchTurnInteractBinding` | turnInteractBinding
336 | (24) `std::vector<std::string>` | pointerButtonNames
360 | (1) `bool` | invertYAxis


### `TouchTurnInteractBinding`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | turnInteractButtonName
32 | (32) `std::string` | tapButtonName
64 | (32) `std::string` | holdButtonName
96 | (32) `std::string` | areaBindingName
128 | (32) `std::string` | conditionBindingName
160 | (4) `float` | sensitivity


### `TestAutoInputMapping`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<TestAutoInputBinding>` | inputBindings


### `TrailSystem::tick::__l2::<lambda_c642df8e8f8dc06e627b82e74a46ee8c>`
Offset | Type | Name
-|-|-|-
0 | (8) `TrailSystem *const` | __this


### `TrailSystem::BlockPositions`
Offset | Type | Name
-|-|-|-
0 | (48) `BlockPos[4]` | mBlockPos


### `TrunkVariantBuilder::buildTrunkVariant::__l2::<lambda_3c96b118ffe9170a2291ea38c928ddb8>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ITreeTrunkWrapper & __cdecl(FeatureLoading::ConcreteFeatureHolder<VanillaTreeFeature> *)>` | trunkAccessor


### `TreeHelper::TreeParams::buildSchema::__l2::<lambda_bf429b9943da523f3643fae7320cff06>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::TreeParams & __cdecl(FeatureLoading::ConcreteFeatureHolder<VanillaTreeFeature> *)>` | paramAccessor


### `TreeHelper::TreeParams::buildSchema::__l2::<lambda_b7dd1207d09816c0c9db1e6ece51e520>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::TreeParams & __cdecl(FeatureLoading::ConcreteFeatureHolder<VanillaTreeFeature> *)>` | paramAccessor


### `TreeHelper::TreeParams::buildSchema::__l3::<lambda_ba2ff42a04179a7d4894163efb6b8b51>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::TreeParams & __cdecl(FeatureLoading::ConcreteFeatureHolder<VanillaTreeFeature> *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_5e4bd2a6e306b937e24b2085f6536010>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_35823045a604d8e3db9f83bb8371b7d5>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_cedc28b75fb8749133e75d18d3512355>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(AcaciaTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_aec198287f74f059d029ccf4ef1c577c>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(AcaciaTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_baa72491bdadbebb01f35d1038cd8d6b>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(FallenTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_2c168f71e54c6faf572d0551eeebe8f0>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(FallenTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_b01630c12ad9025c6f4b9b3378d3dd7f>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(MegaTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_dcf9ab12608cfd54a4f7a832e8a9d7a2>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(MegaTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_4204fc98330b04bfb097d1dcec9854fb>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_1f6aaabf01f47958cadbe8c0b8c4c53f>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeTrunk *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_4f6efd324af87ba1b45da67ba0332cdc>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_d038d92cd2883b2ee65fa0a1d16c2d87>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_22ca3585577933bb2c95ef437ae03bde>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_ea8eeac4ffd972d2f79b338c9d52793b>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TreeHelper::AttachableDecoration::buildSchema::__l2::<lambda_48eb51015eaf0361e05f044e832cf162>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<TreeHelper::AttachableDecoration & __cdecl(SimpleTreeCanopy *)>` | paramAccessor


### `TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> >`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<HashedString,unsigned __int64>` | mTagIndexMap
64 | (24) `std::vector<std::string>` | mTags
88 | (24) `std::vector<IndexSet>` | mSets
112 | (24) `std::vector<std::string>` | mTagsScratchpad
136 | (24) `std::vector<IDType<BiomeTagIDType>>` | mTagIDScratchpad
160 | (48) `IndexSet` | mIndexSetScratchpad
208 | (16) `IDType<BiomeTagSetIDType>` | mEmptyTagSet


### `type_info`
Offset | Type | Name
-|-|-|-
0 | (8) `type_info_vtbl *` | __vftable
8 | (16) `__std_type_info_data` | _Data


### `TextInput`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | text
32 | (1) `bool` | keepImePosition
36 | (4) `int` | controllerId


### `TurnEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | _dx
4 | (4) `float` | dy


### `tm_unz_s`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | tm_sec
4 | (4) `unsigned int` | tm_min
8 | (4) `unsigned int` | tm_hour
12 | (4) `unsigned int` | tm_mday
16 | (4) `unsigned int` | tm_mon
20 | (4) `unsigned int` | tm_year


### `tm_zip_s`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | tm_sec
4 | (4) `unsigned int` | tm_min
8 | (4) `unsigned int` | tm_hour
12 | (4) `unsigned int` | tm_mday
16 | (4) `unsigned int` | tm_mon
20 | (4) `unsigned int` | tm_year


### `T1_DecoderRec_`
Offset | Type | Name
-|-|-|-
0 | (176) `T1_BuilderRec_` | builder
176 | (1024) `int[256]` | stack
1200 | (8) `int *` | top
1208 | (408) `T1_Decoder_ZoneRec_[17]` | zones
1616 | (8) `T1_Decoder_ZoneRec_ *` | zone
1624 | (8) `const FT_Service_PsCMapsRec_ *` | psnames
1632 | (4) `unsigned int` | num_glyphs
1640 | (8) `unsigned __int8 **` | glyph_names
1648 | (4) `int` | lenIV
1652 | (4) `int` | num_subrs
1656 | (8) `unsigned __int8 **` | subrs
1664 | (8) `unsigned int *` | subrs_len
1672 | (8) `FT_HashRec_ *` | subrs_hash
1680 | (16) `FT_Matrix_` | font_matrix
1696 | (8) `FT_Vector_` | font_offset
1704 | (4) `int` | flex_state
1708 | (4) `int` | num_flex_vectors
1712 | (56) `FT_Vector_[7]` | flex_vectors
1768 | (8) `PS_BlendRec_ *` | blend
1776 | (4) `FT_Render_Mode_` | hint_mode
1784 | (8) `int (__fastcall *)(T1_DecoderRec_ *, unsigned int)` | parse_callback
1792 | (32) `T1_Decoder_FuncsRec_` | funcs
1824 | (8) `int *` | buildchar
1832 | (4) `unsigned int` | len_buildchar
1836 | (1) `unsigned __int8` | seac
1840 | (16) `FT_Generic_` | cf2_instance


### `T1_BuilderRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_MemoryRec_ *` | memory
8 | (8) `FT_FaceRec_ *` | face
16 | (8) `FT_GlyphSlotRec_ *` | glyph
24 | (8) `FT_GlyphLoaderRec_ *` | loader
32 | (8) `FT_Outline_ *` | base
40 | (8) `FT_Outline_ *` | current
48 | (4) `int` | pos_x
52 | (4) `int` | pos_y
56 | (8) `FT_Vector_` | left_bearing
64 | (8) `FT_Vector_` | advance
72 | (16) `FT_BBox_` | bbox
88 | (4) `T1_ParseState_` | parse_state
92 | (1) `unsigned __int8` | load_points
93 | (1) `unsigned __int8` | no_recurse
94 | (1) `unsigned __int8` | metrics_only
96 | (8) `void *` | hints_funcs
104 | (8) `void *` | hints_globals
112 | (64) `T1_Builder_FuncsRec_` | funcs


### `T1_Decoder_ZoneRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | cursor
8 | (8) `unsigned __int8 *` | base
16 | (8) `unsigned __int8 *` | limit


### `T1_TokenRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | start
8 | (8) `unsigned __int8 *` | limit
16 | (4) `T1_TokenType_` | type


### `TPoint_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y


### `TT_SBitDecoderRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `TT_FaceRec_ *` | face
8 | (8) `FT_StreamRec_ *` | stream
16 | (8) `FT_Bitmap_ *` | bitmap
24 | (8) `TT_SBit_MetricsRec_ *` | metrics
32 | (1) `unsigned __int8` | metrics_loaded
33 | (1) `unsigned __int8` | bitmap_allocated
34 | (1) `unsigned __int8` | bit_depth
36 | (4) `unsigned int` | ebdt_start
40 | (4) `unsigned int` | ebdt_size
44 | (4) `unsigned int` | strike_index_array
48 | (4) `unsigned int` | strike_index_count
56 | (8) `unsigned __int8 *` | eblc_base
64 | (8) `unsigned __int8 *` | eblc_limit


### `TPixmap_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | origin
8 | (4) `int` | pitch


### `TT_LoaderRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `TT_FaceRec_ *` | face
8 | (8) `TT_SizeRec_ *` | size
16 | (8) `FT_GlyphSlotRec_ *` | glyph
24 | (8) `FT_GlyphLoaderRec_ *` | gloader
32 | (4) `unsigned int` | load_flags
36 | (4) `unsigned int` | glyph_index
40 | (8) `FT_StreamRec_ *` | stream
48 | (4) `int` | byte_len
52 | (2) `__int16` | n_contours
56 | (16) `FT_BBox_` | bbox
72 | (4) `int` | left_bearing
76 | (4) `int` | advance
80 | (4) `int` | linear
84 | (1) `unsigned __int8` | linear_def
88 | (8) `FT_Vector_` | pp1
96 | (8) `FT_Vector_` | pp2
104 | (64) `TT_GlyphZoneRec_` | base
168 | (64) `TT_GlyphZoneRec_` | zone
232 | (8) `TT_ExecContextRec_ *` | exec
240 | (8) `unsigned __int8 *` | instructions
248 | (4) `unsigned int` | ins_pos
256 | (8) `void *` | other
264 | (4) `int` | top_bearing
268 | (4) `int` | vadvance
272 | (8) `FT_Vector_` | pp3
280 | (8) `FT_Vector_` | pp4
288 | (8) `unsigned __int8 *` | cursor
296 | (8) `unsigned __int8 *` | limit
304 | (16) `FT_ListRec_` | composites


### `TT_GlyphZoneRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_MemoryRec_ *` | memory
8 | (2) `unsigned __int16` | max_points
10 | (2) `__int16` | max_contours
12 | (2) `unsigned __int16` | n_points
14 | (2) `__int16` | n_contours
16 | (8) `FT_Vector_ *` | org
24 | (8) `FT_Vector_ *` | cur
32 | (8) `FT_Vector_ *` | orus
40 | (8) `unsigned __int8 *` | tags
48 | (8) `wchar_t *` | contours
56 | (2) `unsigned __int16` | first_point


### `T1_ParserRec_`
Offset | Type | Name
-|-|-|-
0 | (144) `PS_ParserRec_` | root
144 | (8) `FT_StreamRec_ *` | stream
152 | (8) `unsigned __int8 *` | base_dict
160 | (4) `unsigned int` | base_len
168 | (8) `unsigned __int8 *` | private_dict
176 | (4) `unsigned int` | private_len
180 | (1) `unsigned __int8` | in_pfb
181 | (1) `unsigned __int8` | in_memory
182 | (1) `unsigned __int8` | single_block


### `T42_ParserRec_`
Offset | Type | Name
-|-|-|-
0 | (144) `PS_ParserRec_` | root
144 | (8) `FT_StreamRec_ *` | stream
152 | (8) `unsigned __int8 *` | base_dict
160 | (4) `int` | base_len
164 | (1) `unsigned __int8` | in_memory


### `textio`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | ob_refcnt
8 | (8) `_typeobject *` | ob_type
16 | (4) `int` | ok
20 | (4) `int` | detached
24 | (8) `__int64` | chunk_size
32 | (8) `_object *` | buffer
40 | (8) `_object *` | encoding
48 | (8) `_object *` | encoder
56 | (8) `_object *` | decoder
64 | (8) `_object *` | readnl
72 | (8) `_object *` | errors
80 | (8) `const char *` | writenl
88 | (1) `char` | line_buffering
89 | (1) `char` | readuniversal
90 | (1) `char` | readtranslate
91 | (1) `char` | writetranslate
92 | (1) `char` | seekable
93 | (1) `char` | telling
96 | (8) `_object *(__fastcall *)(_object *, _object *)` | encodefunc
104 | (1) `char` | encoding_start_of_stream
112 | (8) `_object *` | decoded_chars
120 | (8) `__int64` | decoded_chars_used
128 | (8) `_object *` | pending_bytes
136 | (8) `__int64` | pending_bytes_count
144 | (8) `_object *` | snapshot
152 | (8) `_object *` | raw
160 | (8) `_object *` | weakreflist
168 | (8) `_object *` | dict


### `tinystl::pair<tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned int> >,bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned int> >` | first
8 | (1) `bool` | second


### `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned int> >`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,unsigned int> *` | node


### `tinystl::pair<unsigned __int64,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | first
8 | (4) `unsigned int` | second


### `tinystl::list<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::vector<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>` | baseclass_0


### `tinystl::vector<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::buffer<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>` | m_buffer


### `tinystl::buffer<bgfx::NonLocalAllocator::Free,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::NonLocalAllocator::Free *` | first
8 | (8) `bgfx::NonLocalAllocator::Free *` | last
16 | (8) `bgfx::NonLocalAllocator::Free *` | capacity


### `tinystl::unordered_map<unsigned __int64,unsigned int,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,unsigned int> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::buffer<tinystl::unordered_hash_node<unsigned __int64,unsigned int> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,unsigned int> **` | first
8 | (8) `tinystl::unordered_hash_node<unsigned __int64,unsigned int> **` | last
16 | (8) `tinystl::unordered_hash_node<unsigned __int64,unsigned int> **` | capacity


### `tagPIXELFORMATDESCRIPTOR`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | nSize
2 | (2) `unsigned __int16` | nVersion
4 | (4) `unsigned int` | dwFlags
8 | (1) `unsigned __int8` | iPixelType
9 | (1) `unsigned __int8` | cColorBits
10 | (1) `unsigned __int8` | cRedBits
11 | (1) `unsigned __int8` | cRedShift
12 | (1) `unsigned __int8` | cGreenBits
13 | (1) `unsigned __int8` | cGreenShift
14 | (1) `unsigned __int8` | cBlueBits
15 | (1) `unsigned __int8` | cBlueShift
16 | (1) `unsigned __int8` | cAlphaBits
17 | (1) `unsigned __int8` | cAlphaShift
18 | (1) `unsigned __int8` | cAccumBits
19 | (1) `unsigned __int8` | cAccumRedBits
20 | (1) `unsigned __int8` | cAccumGreenBits
21 | (1) `unsigned __int8` | cAccumBlueBits
22 | (1) `unsigned __int8` | cAccumAlphaBits
23 | (1) `unsigned __int8` | cDepthBits
24 | (1) `unsigned __int8` | cStencilBits
25 | (1) `unsigned __int8` | cAuxBuffers
26 | (1) `unsigned __int8` | iLayerType
27 | (1) `unsigned __int8` | bReserved
28 | (4) `unsigned int` | dwLayerMask
32 | (4) `unsigned int` | dwVisibleMask
36 | (4) `unsigned int` | dwDamageMask


### `tinystl::vector<unsigned char,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::buffer<unsigned char,bgfx::TinyStlAllocator>` | m_buffer


### `tinystl::buffer<unsigned char,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | first
8 | (8) `unsigned __int8 *` | last
16 | (8) `unsigned __int8 *` | capacity


### `tinystl::pair<tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned short> >,bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned short> >` | first
8 | (1) `bool` | second


### `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,unsigned short> >`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,unsigned short> *` | node


### `tinystl::pair<tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> >,bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> >` | first
8 | (1) `bool` | second


### `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> >`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned __int64,bgfx::vk::VkSampler> *` | node


### `tinystl::pair<unsigned __int64,bgfx::vk::VkSampler>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | first
8 | (8) `bgfx::vk::VkSampler` | second


### `tinystl::vector<bgfx::DxbcSignature::Element,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::buffer<bgfx::DxbcSignature::Element,bgfx::TinyStlAllocator>` | m_buffer


### `tinystl::buffer<bgfx::DxbcSignature::Element,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `bgfx::DxbcSignature::Element *` | first
8 | (8) `bgfx::DxbcSignature::Element *` | last
16 | (8) `bgfx::DxbcSignature::Element *` | capacity


### `tinystl::buffer<tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> *,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> **` | first
8 | (8) `tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> **` | last
16 | (8) `tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> **` | capacity


### `tinystl::pair<tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned int,unsigned int> >,bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned int,unsigned int> >` | first
8 | (1) `bool` | second


### `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<unsigned int,unsigned int> >`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<unsigned int,unsigned int> *` | node


### `tinystl::pair<unsigned int,unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | first
4 | (4) `unsigned int` | second


### `tinystl::stringT<bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | m_first
8 | (8) `char *` | m_last
16 | (8) `char *` | m_capacity
24 | (12) `char[12]` | m_buffer


### `tinystl::unordered_map<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | m_size
8 | (24) `tinystl::buffer<tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> *,bgfx::TinyStlAllocator>` | m_buckets


### `tinystl::pair<tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> >,bool>`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> >` | first
8 | (1) `bool` | second


### `tinystl::unordered_hash_iterator<tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> >`
Offset | Type | Name
-|-|-|-
0 | (8) `tinystl::unordered_hash_node<tinystl::stringT<bgfx::TinyStlAllocator>,unsigned int> *` | node


### `tinystl::vector<unsigned int,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (24) `tinystl::buffer<unsigned int,bgfx::TinyStlAllocator>` | m_buffer


### `tinystl::buffer<unsigned int,bgfx::TinyStlAllocator>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int *` | first
8 | (8) `unsigned int *` | last
16 | (8) `unsigned int *` | capacity


### `type_info_vtbl`
```
struct /*VFT*/ type_info_vtbl
{
  void (__fastcall *~type_info)(type_info *this);
};

```

### `TlsDtorNode`
```
struct TlsDtorNode
{
  int count;
  TlsDtorNode *next;
  void (__fastcall *funcs[30])();
};

```

### `TemporalAttributeBuff_vtbl`
```
struct /*VFT*/ TemporalAttributeBuff_vtbl
{
  void (__fastcall *~AttributeBuff)(AttributeBuff *this);
  bool (__fastcall *isInstantaneous)(AttributeBuff *this);
  bool (__fastcall *isSerializable)(AttributeBuff *this);
  void (__fastcall *setDurationAmplifier)(AttributeBuff *this, std::shared_ptr<Amplifier>);
  bool (__fastcall *shouldBuff)(TemporalAttributeBuff *this);
  bool (__fastcall *isComplete)(TemporalAttributeBuff *this);
};

```

### `Tag_vtbl`
```
struct /*VFT*/ Tag_vtbl
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

### `TaskGroup`
```
struct __cppobj TaskGroup : ITaskGroup
{
  Bedrock::NonOwnerPointer<Scheduler> mScheduler;
  Bedrock::NonOwnerPointer<WorkerPool> mWorkers;
  std::string mName;
  bool mCheckOwnerThread;
  std::mutex mLock;
  std::atomic<enum TaskGroupState> mState;
  std::shared_ptr<BackgroundTaskBase> mTasks;
  unsigned __int64 mTaskCount;
  std::shared_ptr<BackgroundTaskBase> mEnumCurr;
  std::shared_ptr<BackgroundTaskBase> mEnumNext;
};

```

### `TaskGroup_vtbl`
```
struct /*VFT*/ TaskGroup_vtbl
{
  void (__fastcall *~ITaskGroup)(ITaskGroup *this);
  void (__fastcall *taskRegister)(ITaskGroup *this, std::shared_ptr<BackgroundTaskBase>);
  void (__fastcall *requeueTask)(ITaskGroup *this, std::shared_ptr<BackgroundTaskBase>, bool);
  TaskGroupState (__fastcall *getState)(ITaskGroup *this);
  void (__fastcall *processCoroutines)(ITaskGroup *this);
  void (__fastcall *taskComplete)(ITaskGroup *this, gsl::not_null<BackgroundTaskBase *>);
};

```

### `TransportNoCompressPacket`
```
const struct __cppobj TransportNoCompressPacket : Packet
{
  unsigned int mUserId;
  std::string mTransData;
};

```

### `TransportNoCompressPacket_vtbl`
```
struct /*VFT*/ TransportNoCompressPacket_vtbl
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

### `TransportPacket`
```
const struct __cppobj TransportPacket : Packet
{
  unsigned int mUserId;
  bool mIsCompress;
  std::string mTransData;
};

```

### `TransportPacket_vtbl`
```
struct /*VFT*/ TransportPacket_vtbl
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

### `TickSyncPacket`
```
const struct __cppobj TickSyncPacket : Packet
{
  __int64 mClientRequestTimestamp;
  __int64 mServerReceptionResponseTimestamp;
};

```

### `TickSyncPacket_vtbl`
```
struct /*VFT*/ TickSyncPacket_vtbl
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

### `TransferPacket`
```
const struct __cppobj __declspec(align(8)) TransferPacket : Packet
{
  std::string mServerAddress;
  int mServerPort;
};

```

### `TransferPacket_vtbl`
```
struct /*VFT*/ TransferPacket_vtbl
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

### `TakeItemActorPacket`
```
const struct __cppobj TakeItemActorPacket : Packet
{
  ActorRuntimeID mItemId;
  ActorRuntimeID mPlayerId;
};

```

### `TakeItemActorPacket_vtbl`
```
struct /*VFT*/ TakeItemActorPacket_vtbl
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

### `TextPacket_vtbl`
```
struct /*VFT*/ TextPacket_vtbl
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

### `Timer`
```
struct __cppobj Timer
{
  float mTicksPerSecond;
  int mTicks;
  float mAlpha;
  float mTimeScale;
  float mPassedTime;
  float mFrameStepAlignmentRemainder;
  float mLastTimeSeconds;
  float mLastTimestep;
  __int64 mLastMs;
  __int64 mLastMsSysTime;
  float mAdjustTime;
  int mSteppingTick;
  std::function<__int64 __cdecl(void)> mGetTimeMSCallback;
};

```

### `TickingAreaDescription`
```
struct __cppobj __declspec(align(8)) TickingAreaDescription
{
  BlockPos mOrigin;
  BlockPos mMax;
  unsigned int mRadius;
  std::string mName;
  bool mIsCircle;
};

```

### `TextFilteringProcessor`
```
struct __cppobj TextFilteringProcessor : Bedrock::EnableNonOwnerReferences
{
  TextFilteringProcessor_vtbl *__vftable /*VFT*/;
};

```

### `TextFilteringProcessor_vtbl`
```
struct /*VFT*/ TextFilteringProcessor_vtbl
{
  void (__fastcall *~TextFilteringProcessor)(TextFilteringProcessor *this);
  CallbackToken *(__fastcall *processMessages)(TextFilteringProcessor *this, CallbackToken *result, const Player *, bool, const std::vector<std::string> *, std::function<void __cdecl(std::vector<std::string> const &)>);
  void (__fastcall *processJoinEvent)(TextFilteringProcessor *this, const Player *);
  void (__fastcall *processLeaveEvent)(TextFilteringProcessor *this, const Player *);
};

```

### `TcpProxy`
```
struct __cppobj TcpProxy
{
  TcpProxy_vtbl *__vftable /*VFT*/;
};

```

### `TcpProxy_vtbl`
```
struct /*VFT*/ TcpProxy_vtbl
{
  void (__fastcall *~TcpProxy)(TcpProxy *this);
  bool (__fastcall *start)(TcpProxy *this, unsigned __int16, unsigned __int16, unsigned __int16);
  RakNet::SystemAddress *(__fastcall *connect)(TcpProxy *this, RakNet::SystemAddress *result, const std::string *, unsigned __int16);
  void (__fastcall *send)(TcpProxy *this, const char *, unsigned int, RakNet::SystemAddress);
  void (__fastcall *close)(TcpProxy *this, RakNet::SystemAddress);
  bool (__fastcall *packetsAvailable)(TcpProxy *this);
  RakNet::Packet *(__fastcall *nextPacket)(TcpProxy *this);
  void (__fastcall *deallocatePacket)(TcpProxy *this, RakNet::Packet *);
  RakNet::SystemAddress *(__fastcall *nextCompletedConnectionAttempt)(TcpProxy *this, RakNet::SystemAddress *result);
  RakNet::SystemAddress *(__fastcall *nextFailedConnectionAttempt)(TcpProxy *this, RakNet::SystemAddress *result);
  RakNet::SystemAddress *(__fastcall *nextLostConnection)(TcpProxy *this, RakNet::SystemAddress *result);
};

```

### `TimerFacade`
```
struct __cppobj TimerFacade
{
  BasicTimer mTimer;
};

```

### `TextToSpeechSystem`
```
const struct __cppobj __declspec(align(8)) TextToSpeechSystem
{
  TextToSpeechSystem_vtbl *__vftable /*VFT*/;
  TTSEnabledStatus mTTSEnabledStatus;
};

```

### `TextToSpeechClient`
```
struct __cppobj TextToSpeechClient
{
  TextToSpeechClient_vtbl *__vftable /*VFT*/;
};

```

### `TextToSpeechClient_vtbl`
```
struct /*VFT*/ TextToSpeechClient_vtbl
{
  void (__fastcall *~TextToSpeechClient)(TextToSpeechClient *this);
  void (__fastcall *setTextToSpeechEnabled)(TextToSpeechClient *this, bool);
  bool (__fastcall *getTextToSpeechEnabled)(TextToSpeechClient *this);
  void (__fastcall *speakText)(TextToSpeechClient *this, const std::string *);
  void (__fastcall *stopSpeaking)(TextToSpeechClient *this);
  bool (__fastcall *isIdle)(TextToSpeechClient *this);
};

```

### `TextToSpeechSystem_vtbl`
```
struct /*VFT*/ TextToSpeechSystem_vtbl
{
  void (__fastcall *~TextToSpeechSystem)(TextToSpeechSystem *this);
  bool (__fastcall *checkPlatformTTSEnabled)(TextToSpeechSystem *this, gsl::not_null<Options *>);
  bool (__fastcall *canAutoEnableTTS)(TextToSpeechSystem *this, gsl::not_null<Options const *>);
  TTSEnabledStatus (__fastcall *getTTSEnabledStatus)(TextToSpeechSystem *this);
  void (__fastcall *setTTSEnabledStatus)(TextToSpeechSystem *this, TTSEnabledStatus);
  bool (__fastcall *supportsMultipleTTSClients)(TextToSpeechSystem *this);
  std::shared_ptr<TextToSpeechClient> *(__fastcall *_createTTSClient)(TextToSpeechSystem *this, std::shared_ptr<TextToSpeechClient> *result);
};

```

### `ThirdPartyServer::AvailableGame`
```
struct __cppobj ThirdPartyServer::AvailableGame
{
  Core::PathBuffer<std::string > imagePath;
  std::string title;
  std::string subtitle;
  std::string description;
};

```

### `ThirdPartyServer`
```
struct __cppobj __declspec(align(8)) ThirdPartyServer
{
  std::string mCreatorName;
  std::string mProductId;
  std::string mCreatorId;
  std::string mTitle;
  std::vector<Core::PathBuffer<std::string >> mScreenshotImagePaths;
  std::string mDescription;
  std::vector<ThirdPartyServer::AvailableGame> mGames;
  std::string mNews;
  std::string mNewsTitle;
  std::string mAllowListUrl;
  Core::PathBuffer<std::string > mImagePath;
  std::string mServerUrl;
  unsigned __int16 mServerPort;
  bool mRequireXBL;
  bool mIsImageFinished;
};

```

### `TreatmentPackSource`
```
struct __cppobj TreatmentPackSource : PackSource
{
  bool mDiscovered;
  Core::PathBuffer<std::string > mPath;
  _BYTE mPackType[1];
  std::vector<std::unique_ptr<Pack>> mPacks;
};

```

### `TreatmentPackSource_vtbl`
```
struct /*VFT*/ TreatmentPackSource_vtbl
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

### `TreatmentComponent`
```
struct __cppobj TreatmentComponent : StoreUIComponent
{
  std::string mRequiredTreatmentTag;
  PackIdVersion mPackId;
};

```

### `TreatmentComponent_vtbl`
```
struct /*VFT*/ TreatmentComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `ThirdPartyServerRepository`
```
struct __cppobj ThirdPartyServerRepository
{
  std::unordered_map<std::string,std::pair<ThirdPartyInfo,std::vector<std::shared_ptr<ThirdPartyServer>> >> mTestThirdPartyServers;
  std::unordered_map<std::string,std::pair<ThirdPartyInfo,std::vector<std::shared_ptr<ThirdPartyServer>> >> mThirdPartyServers;
  bool mIsFetchingServers;
  std::unique_ptr<ContentCatalogService> mContentCatalogService;
  std::vector<std::function<void __cdecl(std::unordered_map<std::string,std::pair<ThirdPartyInfo,std::vector<std::shared_ptr<ThirdPartyServer>> >> const &)>> mOnFetchCompleteCallbacks;
  std::vector<std::function<void __cdecl(std::string const &,Core::Path const &)>> mOnImageFetchedCallbacks;
};

```

### `TessellatorQuadInfo`
```
struct __cppobj TessellatorQuadInfo
{
  unsigned __int8 facing;
  unsigned __int8 twoFace;
  Vec3 centroid;
};

```

### `TickingTextures`
```
struct __cppobj TickingTextures
{
  std::vector<std::unique_ptr<FlipbookTexture>> mTickingTextures;
  std::vector<std::unique_ptr<FlipbookTexture>> mTickingTexturesItems;
};

```

### `TextureHotReloader`
```
struct __cppobj __declspec(align(8)) TextureHotReloader
{
  std::map<ResourceLocation,cg::ImageBuffer> mCachedTextures;
  std::unique_ptr<mce::IResourceWatcher<cg::ResourceLoader<std::shared_ptr<mce::Image>,ResourceLocation,StdIoStreamPolicy,StbImageLoadPolicy,std::vector<unsigned char> >,ImageResourceManager>> mImageWatcher;
  std::unique_ptr<ImageResourceManager> mImageResourceManager;
  std::unordered_map<ResourceLocation,mce::FileWatcherHandle> mFileWatcherHandles;
  const TextureHotReloaderMode mMode;
};

```

### `TextureTintCollection`
```
struct __cppobj __declspec(align(8)) TextureTintCollection
{
  std::string mKey;
  bool mIsAnimated;
  std::vector<TextureTint> mTextures;
  std::string mClothingMapPath;
  Pack *mClothingSourcePack;
  TextureUVCoordinateSet mUv;
  _BYTE mAnimationType[4];
};

```

### `TextureAtlasItemTextureSetTranslation::LayerType`
```
struct TextureAtlasItemTextureSetTranslation::LayerType
{
  __int32 layerType : 4;
};

```

### `TextureAtlasItemTextureSetTranslation::TranslationScale`
```
struct TextureAtlasItemTextureSetTranslation::TranslationScale
{
  float uvScaleX;
  float uvScaleY;
  float uvBiasX;
  float uvBiasY;
  int maxMipCount;
};

```

### `TextureAtlasItemTextureSetTranslation::Translation`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::Translation : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::TranslationScale
{
};

```

### `TextureAtlasItemTextureSetTranslation::UniformVec4`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::UniformVec4
{
  mce::Color uniformValue;
};

```

### `TextureAtlasItemTextureSetTranslation::ColorUniform`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::ColorUniform : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::UniformVec4
{
};

```

### `TextureAtlasItemTextureSetTranslation::NormalInfo`
```
struct TextureAtlasItemTextureSetTranslation::NormalInfo
{
  __int8 x : 2;
  __int8 y : 2;
  __int8 z : 2;
};

```

### `TextureAtlasItemTextureSetTranslation::NormalTranslation`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::NormalTranslation : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::NormalInfo, TextureAtlasItemTextureSetTranslation::TranslationScale
{
};

```

### `TextureAtlasItemTextureSetTranslation::MERInfo`
```
struct TextureAtlasItemTextureSetTranslation::MERInfo
{
  __int8 metal : 2;
  __int8 emissive : 2;
  __int8 roughness : 2;
  __int8 hasMetal : 1;
  __int8 hasEmissive : 1;
  __int8 hasRoughness : 1;
};

```

### `TextureAtlasItemTextureSetTranslation::MERTranslation`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::MERTranslation : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::MERInfo, TextureAtlasItemTextureSetTranslation::TranslationScale
{
};

```

### `TextureAtlasItemTextureSetTranslation::UniformVec3`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::UniformVec3
{
  mce::Color uniformValue;
};

```

### `TextureAtlasItemTextureSetTranslation::MERUniform`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::MERUniform : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::MERInfo, TextureAtlasItemTextureSetTranslation::UniformVec3
{
};

```

### `TextureAtlasItemTextureSetTranslation::UniformFloat`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::UniformFloat
{
  ColorChannel uniformValue;
};

```

### `TextureAtlasItemTextureSetTranslation::Uniform`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::Uniform : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::UniformFloat
{
};

```

### `TextureAtlasItemTextureSetTranslation::SingleChannelInfo`
```
struct TextureAtlasItemTextureSetTranslation::SingleChannelInfo
{
  __int8 channel : 3;
};

```

### `TextureAtlasItemTextureSetTranslation::SingleChannelTranslation`
```
struct __cppobj TextureAtlasItemTextureSetTranslation::SingleChannelTranslation : TextureAtlasItemTextureSetTranslation::LayerType, TextureAtlasItemTextureSetTranslation::SingleChannelInfo, TextureAtlasItemTextureSetTranslation::TranslationScale
{
};

```

### `TextureAtlas`
```
struct __cppobj TextureAtlas : Bedrock::EnableNonOwnerReferences
{
  std::shared_ptr<AtlasItemManager> mAtlasItemManager;
  ParsedAtlasData mParsedAtlasData;
  AtlasParameters mAtlasParameters;
  std::set<ResourceLocation> mResources;
  ImageResourceManager mResourceManager;
  std::vector<mce::FileWatcherHandle> mFileWatcherHandle;
};

```

### `TextMeasureData`
```
const struct __cppobj __declspec(align(2)) TextMeasureData
{
  const float fontSize;
  const float linePadding;
  const bool renderShadow;
  const bool showColorSymbol;
  const bool hideHyphen;
};

```

### `ToggleComponent`
```
const struct __cppobj ToggleComponent : UIComponent
{
  std::weak_ptr<UIControl> mCheckedStateControl;
  std::weak_ptr<UIControl> mUncheckedStateControl;
  std::weak_ptr<UIControl> mCheckedHoverStateControl;
  std::weak_ptr<UIControl> mUncheckedHoverStateControl;
  std::weak_ptr<UIControl> mCheckedLockedStateControl;
  std::weak_ptr<UIControl> mCheckedLockedHoverStateControl;
  std::weak_ptr<UIControl> mUncheckedLockedStateControl;
  std::weak_ptr<UIControl> mUncheckedLockedHoverStateControl;
  __int8 mChecked : 1;
  __int8 mHover : 1;
  __int8 mRadioToggleGroup : 1;
  __int8 mDefaultState : 1;
  __int8 mEnableDirectionalToggling : 1;
  std::string mGridCollectionName;
  unsigned int mToggleNameId;
  unsigned int mToggleOnButtonId;
  unsigned int mToggleOffButtonId;
  int mForcedIndex;
  int mDefaultGroupSelectedIndex;
  std::string mTTSValueOn;
  std::string mTTSValueOff;
};

```

### `TextComponent`
```
struct __cppobj TextComponent : RenderableComponent
{
  bool isNoRender;
  FontHandle mFontHandle;
  FontHandle mPrimaryFontHandle;
  FontHandle mBackupFontHandle;
  bool mBackupFontHandleOverridden;
  float mTextOffset;
  mce::Color mColor;
  float mLockedAlpha;
  mce::Color mLockedColor;
  ui::FontSize mFontSize;
  float mFontScaleFactor;
  float mFontScaleFactorSrc;
  float mLinePadding;
  _BYTE mAlignment[4];
  mce::Color mShadowColor;
  glm::tvec2<float,0> mShadowOffset;
  __int8 mShadow : 1;
  __int8 mShouldRenderCaret : 1;
  __int8 mLocalize : 1;
  __int8 mCaretBlinkVisible : 1;
  __int8 mHideHyphen : 1;
  __int8 mEnableProfanityFilter : 1;
  std::string mLabel;
  std::string mLabelTTS;
  bool mAutoExpand;
  bool mFillParent;
  float mCurrentTime;
  int mCaretPosition;
  unsigned __int64 mLastTextHash;
  unsigned __int64 mLastFilteredTextHash;
  std::string mFilteredText;
  std::string mMeasuredText;
  glm::tvec2<float,0> mMeasuredSize;
  bool mCachedTextDirty;
  std::string mCachedText;
  std::string mLOCCachedText;
  std::string mCachedLangCode;
  std::string mCachedFontSources;
  std::string mCachedTextTTS;
  int mLastNumChanges;
  std::vector<int> mCaretOffsets;
  float mCaretHeightOffset;
  float mLineHeight;
  std::vector<std::string> mNotifyControlsOnEllipses;
  std::function<std::pair<FontHandle,FontHandle> __cdecl(std::string const &)> mGetFontsFromFontTypeCallback;
};

```

### `TextComponent_vtbl`
```
struct /*VFT*/ TextComponent_vtbl
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
  void (__fastcall *render)(TextComponent *this, UIRenderContext *);
};

```

### `TextEditFocusedListener`
```
struct __cppobj TextEditFocusedListener
{
  bool mHasAlwaysListeningTextEditControl;
};

```

### `ToastMessage`
```
struct __cppobj __declspec(align(8)) ToastMessage
{
  _BYTE mType[4];
  std::string mTitle;
  std::string mSubtitle;
  Json::Value mPropertyBag;
  bool mHasBeenPressed;
};

```

### `ToastManager`
```
struct __cppobj __declspec(align(8)) ToastManager : Bedrock::Threading::EnableQueueForMainThread
{
  IClientInstance *mClient;
  std::vector<std::unique_ptr<ToastMessage>> mToastPopups;
  std::unique_ptr<ToastMessage> mCurrentToast;
  std::function<RectangleArea __cdecl(void)> mAreaBinding;
  std::function<bool __cdecl(void)> mActiveBinding;
  bool mToastClicked;
  bool mToastsEnabled;
  bool mRefreshPendingInvites;
};

```

### `ToastManager_vtbl`
```
struct /*VFT*/ ToastManager_vtbl
{
  void (__fastcall *~EnableQueueForMainThread)(Bedrock::Threading::EnableQueueForMainThread *this);
};

```

### `TickingTextureStage`
```
struct __cppobj __declspec(align(8)) TickingTextureStage : mce::RenderStageWithFrameBufferObject
{
  bool mHasFrameBuffer;
  IClientInstance *mClient;
  mce::TexturePtr mAtlasTexture;
  std::string mAtlasName;
  bool mIsItem;
};

```

### `TickingTextureStage_vtbl`
```
struct /*VFT*/ TickingTextureStage_vtbl
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

### `TextureItem`
```
struct __cppobj TextureItem
{
  std::string defaultName;
  std::string carriedName;
  TextureAtlasItem defaultItem;
  TextureAtlasItem carriedItem;
};

```

### `ThreadedFrameConstantsContainer`
```
struct __cppobj ThreadedFrameConstantsContainer
{
  mce::ThreadedPerFrameConstants mPerFrameConstants;
  mce::ThreadedShaderConstants mShaderConstants;
  mce::ThreadedRenderChunkConstants mRenderChunkConstantBuffer;
  mce::ThreadedWorldConstants mWorldConstantBuffer;
};

```

### `TreatmentPackDownloadMonitor`
```
struct __cppobj TreatmentPackDownloadMonitor
{
  FlightingService *mFlightingService;
  ContentCatalogService *mCatalogService;
  ContentAcquisition *mDownloadMonitor;
  ResourcePackManager *mResourcePackManager;
  ResourcePackRepository *mResourcePackRepository;
  IMinecraftEventing *mEventing;
  TreatmentPackSource *mTreatmentPackSource;
  ResourceLoadManager *mResourceLoadManager;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager> > mDateManager;
  IClientInstance *mClientInstance;
  ScheduledCallback mReloadTask;
  ScheduledCallback mQueryTask;
  std::weak_ptr<Options const > mPrimaryOptions;
  std::atomic<enum TreatmentPackDownloadMonitor::FetchState> mFetchState;
  bool mIsNetworkEnabled;
  std::shared_ptr<bool> mExistanceTracker;
  int mMonitorHandle;
  bool mDownloadSuccess;
  std::set<std::string> mInProgressDownloads;
  std::shared_ptr<ResourcePackTreatmentQuery> mTreatmentQuery;
  std::mutex mCachedTreatmentMutex;
  std::vector<std::string> mCachedTreatmentTags;
  std::mutex mCachedPackMetadataMutex;
  std::map<PackIdVersion,TreatmentPackMetadata> mCachedPackMetadata;
};

```

### `TextToIconMapper`
```
struct __cppobj TextToIconMapper
{
  std::unordered_map<int,std::string> mGamepadIconMap;
  std::unordered_map<int,std::string> mGamepadTipsIconMap;
  std::unordered_map<std::string,std::string> mTouchIconMap;
  std::string mGamepadPrefix;
  std::string mGamepadTipsPrefix;
};

```

### `TypedScreenCapabilities<StartScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<StartScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<StartScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<StartScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TypedScreenCapabilities<PauseScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<PauseScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<PauseScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<PauseScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TypedScreenCapabilities<SettingsScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<SettingsScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TypedScreenCapabilities<EDUWorldsScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<EDUWorldsScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<EDUWorldsScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<EDUWorldsScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TypedScreenCapabilities<HudScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<HudScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<HudScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<HudScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TypedScreenCapabilities<LibraryItemScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<LibraryItemScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<LibraryItemScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<LibraryItemScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TransactionRecord`
```
struct __cppobj __declspec(align(8)) TransactionRecord
{
  ProductSku mProductSku;
  std::string mPayload;
  bool mFulfilled;
};

```

### `TransactionHandler`
```
struct __cppobj TransactionHandler
{
  TransactionHandler_vtbl *__vftable /*VFT*/;
  std::unique_ptr<TransactionContext> mTransactionContext;
};

```

### `TransactionContext`
```
struct __cppobj TransactionContext
{
  std::function<void __cdecl(TransactionContext *,enum TransactionStatus)> mCallback;
  std::string mXuid;
  std::string mPayload;
  std::string mCorrelationID;
};

```

### `TransactionHandler_vtbl`
```
struct /*VFT*/ TransactionHandler_vtbl
{
  void (__fastcall *~TransactionHandler)(TransactionHandler *this);
  void (__fastcall *update)(TransactionHandler *this);
  void (__fastcall *transactPurchase)(TransactionHandler *this, Offer *, TransactionContext *, PurchasePath);
  bool (__fastcall *transactFulfillment)(TransactionHandler *this, Offer *, std::shared_ptr<Purchase>, std::unique_ptr<TransactionContext>, PurchasePath);
};

```

### `TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>`
```
struct __cppobj TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> : std::enable_shared_from_this<TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> >
{
  TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>_vtbl *__vftable /*VFT*/;
  FlightingService *mFlightingService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  std::string mDefaultTag;
  unsigned int mLatestQueryId;
  std::string mSelectedDocumentId;
};

```

### `TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>_vtbl`
```
struct /*VFT*/ TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>_vtbl
{
  void (__fastcall *~TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> *this, const StoreConfigSearchResults *, const std::vector<std::string> *);
};

```

### `Trigger`
```
struct __cppobj Trigger
{
  bool mActive;
};

```

### `TrialManager`
```
struct __cppobj TrialManager : Bedrock::EnableNonOwnerReferences
{
  gsl::not_null<Bedrock::NonOwnerPointer<OfferRepository> > mOfferRepository;
  std::weak_ptr<Options> mOptions;
  FlightingService *mFlightingService;
  std::map<enum MinecraftGameFeatures,bool> mTrialModeFeatures;
  std::map<enum MinecraftGameFeatures,bool> mFullGameFeatures;
};

```

### `TouchTextButtonBinding`
```
struct __cppobj TouchTextButtonBinding
{
  std::string buttonName;
  std::string pointBindingName;
  std::string conditionBindingName;
  std::string labelBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  bool passThrough;
  int touchStateRequirement;
};

```

### `TouchGlyphButtonBinding`
```
struct __cppobj __declspec(align(4)) TouchGlyphButtonBinding
{
  std::string buttonName;
  std::string areaBindingName;
  std::string conditionBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  bool passThrough;
  int touchStateRequirement;
  float glyphScale;
  bool promiscuous;
};

```

### `TouchGlyphButtonBindingEX`
```
struct __cppobj TouchGlyphButtonBindingEX
{
  std::string buttonName;
  std::string areaBindingName;
  std::string conditionBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  bool passThrough;
  int touchStateRequirement;
  float glyphScale;
  bool promiscuous;
  std::string buttonName2;
};

```

### `TouchGlyphRadioButtonBinding`
```
struct __cppobj __declspec(align(4)) TouchGlyphRadioButtonBinding
{
  std::string buttonName;
  std::string areaBindingName;
  std::string conditionBindingName;
  std::string passStateBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  bool passThrough;
  int touchStateRequirement;
  float glyphScale;
  bool promiscuous;
};

```

### `TouchJoystickBinding`
```
struct __cppobj __declspec(align(4)) TouchJoystickBinding
{
  std::string buttonUpName;
  std::string buttonDownName;
  std::string buttonLeftName;
  std::string buttonRightName;
  std::string areaBindingName;
  std::string conditionBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  int imageU1;
  int imageV1;
  int uvWidth1;
  int uvHeight1;
  bool passThrough;
  int touchStateRequirement;
  float glyphScale;
  bool promiscuous;
};

```

### `TouchCameraJoystickBinding`
```
struct __cppobj __declspec(align(4)) TouchCameraJoystickBinding
{
  std::string mButtonName;
  std::string mJumButtonName;
  std::string areaBindingName;
  std::string conditionBindingName;
  ButtonColors buttonColors;
  int imageU;
  int imageV;
  int uvWidth;
  int uvHeight;
  int imageU1;
  int imageV1;
  int uvWidth1;
  int uvHeight1;
  bool passThrough;
  int touchStateRequirement;
  float glyphScale;
  bool promiscuous;
};

```

### `TestAutoInputBinding`
```
struct __cppobj __declspec(align(8)) TestAutoInputBinding
{
  std::string buttonName;
  int actionValue;
};

```

### `TTSEventOptions`
```
struct TTSEventOptions
{
  unsigned __int32 mInterruptable : 1;
  unsigned __int32 mDisregardAppFocus : 1;
  unsigned __int32 mRequired : 1;
};

```

### `TTSEvent`
```
struct __cppobj TTSEvent
{
  std::string mText;
  TTSEventOptions mOptions;
  _BYTE mProfanityFilterContext[4];
};

```

### `TTSEventManager`
```
struct __cppobj TTSEventManager : ITTSEventManager
{
  std::function<enum AppFocusState __cdecl(void)> _getAppFocusState;
  std::vector<std::shared_ptr<TTSEvent>> mQueue;
  std::shared_ptr<TTSEvent> mActiveEvent;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastMessageTimePoint;
  const UIProfanityContext *mUIProfanityContext;
  std::weak_ptr<TextToSpeechClient> mTTSClient;
  std::shared_ptr<Options> mOptions;
};

```

### `TTSEventManager_vtbl`
```
struct /*VFT*/ TTSEventManager_vtbl
{
  void (__fastcall *~ITTSEventManager)(ITTSEventManager *this);
  void (__fastcall *enqueueTTSEvent)(ITTSEventManager *this, const std::string *, ProfanityFilterContext, bool, bool, bool, bool);
  bool (__fastcall *isChatTextToSpeechEnabled)(ITTSEventManager *this);
  bool (__fastcall *isUITextToSpeechEnabled)(ITTSEventManager *this);
  void (__fastcall *clearAllTTSEvents)(ITTSEventManager *this);
  bool (__fastcall *ttsEventQueued)(ITTSEventManager *this);
};

```

### `TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>`
```
struct __cppobj TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> : std::enable_shared_from_this<TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> >
{
  TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>_vtbl *__vftable /*VFT*/;
  FlightingService *mFlightingService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  std::string mDefaultTag;
  unsigned int mLatestQueryId;
  std::string mSelectedDocumentId;
};

```

### `TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>_vtbl`
```
struct /*VFT*/ TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>_vtbl
{
  void (__fastcall *~TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>)(TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> *this, const DressingRoomManifestSearchResults *, const std::vector<std::string> *);
};

```

### `TickingAreaListBase`
```
struct __cppobj TickingAreaListBase
{
  std::vector<std::shared_ptr<ITickingArea>> mTickingAreas;
};

```

### `TickingAreaList`
```
struct __cppobj TickingAreaList : TickingAreaListBase
{
};

```

### `TradeTable`
```
struct __cppobj TradeTable
{
  Core::PathBuffer<std::string > mPath;
  std::vector<TradeTier> mTiers;
};

```

### `TradeTables`
```
struct __cppobj TradeTables
{
  std::unordered_map<std::string,std::unique_ptr<TradeTable>> mTradeTables;
};

```

### `TextObjectRoot_vtbl`
```
struct /*VFT*/ TextObjectRoot_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TagRegistry<IDType<LevelTagIDType>,IDType<LevelTagSetIDType> >`
```
struct __cppobj TagRegistry<IDType<LevelTagIDType>,IDType<LevelTagSetIDType> >
{
  std::unordered_map<HashedString,unsigned __int64> mTagIndexMap;
  std::vector<std::string> mTags;
  std::vector<IndexSet> mSets;
  std::vector<std::string> mTagsScratchpad;
  std::vector<IDType<LevelTagIDType>> mTagIDScratchpad;
  IndexSet mIndexSetScratchpad;
  IDType<LevelTagSetIDType> mEmptyTagSet;
};

```

### `TrailDescription`
```
struct __cppobj __declspec(align(8)) TrailDescription : ComponentDescription
{
  ActorFilterGroup mSpawnCondition;
  std::string mBlockType;
  Vec3 mSpawnOffset;
};

```

### `TrailDescription_vtbl`
```
struct /*VFT*/ TrailDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TargetNearbyDescription`
```
struct __cppobj TargetNearbyDescription : ComponentDescription
{
  float mInsideRange;
  float mOutsideRange;
  bool mMustSee;
  DefinitionTrigger mInsideRangeTrigger;
  DefinitionTrigger mOutsideRangeTrigger;
  DefinitionTrigger mLostVisionTrigger;
};

```

### `TargetNearbyDescription_vtbl`
```
struct /*VFT*/ TargetNearbyDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TeleportDescription`
```
struct __cppobj TeleportDescription : ComponentDescription
{
  bool mRandomTeleports;
  float mMinTeleportTime;
  float mMaxTeleportTime;
  Vec3 mRandomTeleportCube;
  float mTargetDistance;
  float mTargetTeleportChance;
  float mLightTeleportChance;
  float mDarkTeleportChance;
};

```

### `TeleportDescription_vtbl`
```
struct /*VFT*/ TeleportDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TickWorldDescription`
```
struct __cppobj __declspec(align(8)) TickWorldDescription : ComponentDescription
{
  unsigned int mChunkRadius;
  float mMaxDistToPlayers;
  bool mAlwaysActive;
};

```

### `TickWorldDescription_vtbl`
```
struct /*VFT*/ TickWorldDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TradeResupplyDescription`
```
struct __cppobj TradeResupplyDescription : ComponentDescription
{
};

```

### `TradeResupplyDescription_vtbl`
```
struct /*VFT*/ TradeResupplyDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TrustDescription`
```
struct __cppobj TrustDescription : ComponentDescription
{
};

```

### `TrustDescription_vtbl`
```
struct /*VFT*/ TrustDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TransformationDescription`
```
struct __cppobj __declspec(align(8)) TransformationDescription : ComponentDescription
{
  ActorDefinitionIdentifier mEntityName;
  int mDelayTicks;
  bool mDropEquipment;
  bool mDropInventory;
  bool mPreserveEquipment;
  std::vector<enum LevelSoundEvent> mBeginTransformSound;
  std::vector<enum LevelSoundEvent> mTransformSound;
  float mBlockAssistChance;
  int mBlockRadius;
  int mBlockMax;
  float mBlockChance;
  std::vector<std::string> mBlockTypes;
  std::vector<std::string> mAddComponentGroups;
  bool mMaintainOwner;
  bool mMaintainTradeLevel;
};

```

### `TransformationDescription_vtbl`
```
struct /*VFT*/ TransformationDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TripodCameraDescription`
```
struct __cppobj TripodCameraDescription : ComponentDescription
{
};

```

### `TripodCameraDescription_vtbl`
```
struct /*VFT*/ TripodCameraDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `TickingAreasManager`
```
struct __cppobj TickingAreasManager
{
  const std::unordered_map<AutomaticID<Dimension,int>,std::unique_ptr<Dimension>,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::unique_ptr<Dimension> > > > *mDimensions;
  std::unordered_map<AutomaticID<Dimension,int>,std::vector<PendingArea>,std::hash<AutomaticID<Dimension,int> >,std::equal_to<AutomaticID<Dimension,int> >,std::allocator<std::pair<AutomaticID<Dimension,int> const ,std::vector<PendingArea> > > > mPendingAreas;
};

```

### `TaskStatus`
```
struct __cppobj TaskStatus
{
  TaskStatus::Value mValue;
};

```

### `TrackerStat`
```
struct __cppobj TrackerStat
{
  unsigned int sentCount;
  unsigned int sentBytes;
  unsigned int receivedCount;
  unsigned int receivedBytes;
  unsigned int sampleNum;
};

```

### `TelemetryInfo`
```
struct __cppobj __declspec(align(4)) TelemetryInfo
{
  PropertyBag mOldInfo;
  PropertyBag mNewPendingInfo;
  Core::PathBuffer<std::string > mFilePath;
  int mPropertyChangeVersion;
  bool mTampered;
  bool mFirstSession;
};

```

### `TypedScreenCapabilities<DefaultScreenCapabilities>`
```
struct __cppobj TypedScreenCapabilities<DefaultScreenCapabilities> : IScreenCapabilities
{
};

```

### `TypedScreenCapabilities<DefaultScreenCapabilities>_vtbl`
```
struct /*VFT*/ TypedScreenCapabilities<DefaultScreenCapabilities>_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `TutorialCollectionConfig`
```
struct __cppobj TutorialCollectionConfig
{
  const WorldTemplateManager *mWorldTemplateManager;
  const ResourcePackRepository *mResourcePackRepository;
  std::string mCollectionName;
};

```

### `TutorialItem`
```
struct __cppobj TutorialItem : LessonItem
{
  EducationMetadata::ContentType mContentType;
  int mEstimatedTime;
  std::string mGoals;
  std::string mLinkToMore;
  std::vector<std::string> mTasks;
  std::vector<std::string> mInstructions;
  int mOrder;
  int mWorldTemplateIndex;
  ResourceFileSystem mFileSystem;
  bool mEnabled;
  bool mIsMultiplayer;
  CompletionState::Value mCompletionState;
  std::function<void __cdecl(TutorialItem const &)> mDestructorCallback;
};

```

### `TutorialItem_vtbl`
```
struct /*VFT*/ TutorialItem_vtbl
{
  void (__fastcall *~LessonItem)(LessonItem *this);
  bool (__fastcall *isValid)(LessonItem *this);
  void (__fastcall *_createImageInfo)(LessonItem *this);
  const ResourceLocation *(__fastcall *_getImageResourceLocation)(LessonItem *this);
};

```

### `TutorialCollection`
```
struct __cppobj TutorialCollection : InstructionalContentCollection, std::enable_shared_from_this<TutorialCollection>
{
  std::shared_ptr<TutorialCollectionConfig> mConfig;
  std::shared_ptr<TutorialItem> mInvalidItem;
  std::shared_ptr<PackManifest> mInvalidPack;
  std::weak_ptr<InstructionalContentCollection> mParentCollection;
};

```

### `TutorialCollection_vtbl`
```
struct /*VFT*/ TutorialCollection_vtbl
{
  void (__fastcall *~InstructionalContentCollection)(InstructionalContentCollection *this);
  void (__fastcall *addItem)(InstructionalContentCollection *this, std::shared_ptr<LessonItem>);
  void (__fastcall *refresh)(InstructionalContentCollection *this);
  void (__fastcall *fetchItems)(InstructionalContentCollection *this);
  void (__fastcall *onItemImported)(InstructionalContentCollection *this, const LessonItem *);
};

```

### `ToastFetcher`
```
struct __cppobj ToastFetcher : std::enable_shared_from_this<ToastFetcher>
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  CatalogInfo mCatalogInfo;
  std::function<void __cdecl(enum ToastMessageType,std::string const &,std::string const &,Json::Value const &,std::string const &)> mPushToastCallback;
  int mToastQueryDocumentCount;
  std::shared_ptr<bool> mExistanceTracker;
};

```

### `TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>`
```
struct __cppobj TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> : std::enable_shared_from_this<TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> >
{
  TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>_vtbl *__vftable /*VFT*/;
  FlightingService *mFlightingService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  std::string mDefaultTag;
  unsigned int mLatestQueryId;
  std::string mSelectedDocumentId;
};

```

### `TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>_vtbl`
```
struct /*VFT*/ TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>_vtbl
{
  void (__fastcall *~TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument>)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<GiftPromotionSearchResults,GiftPromotionDocument> *this, const GiftPromotionSearchResults *, const std::vector<std::string> *);
};

```

### `TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>`
```
struct __cppobj TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> : std::enable_shared_from_this<TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> >
{
  TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>_vtbl *__vftable /*VFT*/;
  FlightingService *mFlightingService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  std::string mDefaultTag;
  unsigned int mLatestQueryId;
  std::string mSelectedDocumentId;
};

```

### `TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>_vtbl`
```
struct /*VFT*/ TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>_vtbl
{
  void (__fastcall *~TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> *this, const QueryManifestSearchResults *, const std::vector<std::string> *);
};

```

### `TreatmentQuery<SalesSearchResults,SalesDocument>`
```
struct __cppobj TreatmentQuery<SalesSearchResults,SalesDocument> : std::enable_shared_from_this<TreatmentQuery<SalesSearchResults,SalesDocument> >
{
  TreatmentQuery<SalesSearchResults,SalesDocument>_vtbl *__vftable /*VFT*/;
  FlightingService *mFlightingService;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  std::string mDefaultTag;
  unsigned int mLatestQueryId;
  std::string mSelectedDocumentId;
};

```

### `TreatmentQuery<SalesSearchResults,SalesDocument>_vtbl`
```
struct /*VFT*/ TreatmentQuery<SalesSearchResults,SalesDocument>_vtbl
{
  void (__fastcall *~TreatmentQuery<SalesSearchResults,SalesDocument>)(TreatmentQuery<SalesSearchResults,SalesDocument> *this);
  const std::string *(__fastcall *getDocumentId)(TreatmentQuery<SalesSearchResults,SalesDocument> *this);
  void (__fastcall *_processQueryResults)(TreatmentQuery<SalesSearchResults,SalesDocument> *this, const SalesSearchResults *, const std::vector<std::string> *);
};

```

### `ThirdPartyServerGame`
```
struct __cppobj ThirdPartyServerGame
{
  std::string imageTag;
  std::string title;
  std::string subtitle;
  std::string description;
};

```

### `ThirdPartyServerCustom`
```
struct __cppobj ThirdPartyServerCustom
{
  bool mRequireXBL;
  unsigned __int16 mPort;
  std::string mCreatorName;
  std::string mUrl;
  std::string mAllowListUrl;
  std::string mNews;
  std::string mNewsTitle;
  std::vector<ThirdPartyServerGame> mAvailableGames;
};

```

### `ThirdPartyServerDocument`
```
struct __cppobj ThirdPartyServerDocument
{
  CommonDocument mCommon;
  ThirdPartyServerCustom mCustom;
};

```

### `ThirdPartyServerSearchResults`
```
const struct __cppobj ThirdPartyServerSearchResults : CommonSearchResults
{
  std::vector<ThirdPartyServerDocument> mDocuments;
};

```

### `TextEditComponent`
```
struct __cppobj __declspec(align(8)) TextEditComponent : UIComponent
{
  unsigned int mMaxLength;
  bool mConstrainToRect;
  bool mEnabledNewline;
  TextType mTextType;
  FontHandle mFontHandle;
  std::weak_ptr<UIControl> mVirtualKeyboardBufferControl;
  std::weak_ptr<UIControl> mLabelControl;
  std::weak_ptr<UIControl> mPlaceHolderControl;
  std::shared_ptr<bool> mDoingTextboxUpdate;
  std::string mGridCollectionName;
  unsigned int mTextEditComponentId;
  bool mCanBeDeselected;
  bool mSelected;
  bool mBindTextToParam;
  bool mFocused;
  bool mAlwaysListening;
};

```

### `TextEditComponent_vtbl`
```
struct /*VFT*/ TextEditComponent_vtbl
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

### `TrackerStats`
```
struct __cppobj TrackerStats
{
  int downloadsPending;
  int downloading;
  int importsWaiting;
  int importsPending;
  int importing;
  int activeExclusiveDownloads;
};

```

### `TurnInput`
```
struct __cppobj TurnInput : IReplayableActorInput
{
  const Vec2 mTurnOffset;
};

```

### `TempEPtr<Actor>`
```
struct __cppobj __declspec(align(8)) TempEPtr<Actor> : _TickPtr
{
  Actor *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<Actor>_vtbl`
```
struct /*VFT*/ TempEPtr<Actor>_vtbl
{
  void (__fastcall *invalidate)(_TickPtr *this);
  void (__fastcall *~_TickPtr)(_TickPtr *this);
};

```

### `tagMENUITEMINFOA`
```
struct tagMENUITEMINFOA
{
  unsigned int cbSize;
  unsigned int fMask;
  unsigned int fType;
  unsigned int fState;
  unsigned int wID;
  HMENU__ *hSubMenu;
  HBITMAP__ *hbmpChecked;
  HBITMAP__ *hbmpUnchecked;
  unsigned __int64 dwItemData;
  char *dwTypeData;
  unsigned int cch;
  HBITMAP__ *hbmpItem;
};

```

### `tagALTTABINFO`
```
struct tagALTTABINFO
{
  unsigned int cbSize;
  int cItems;
  int cColumns;
  int cRows;
  int iColFocus;
  int iRowFocus;
  int cxItem;
  int cyItem;
  tagPOINT ptStart;
};

```

### `tagPSDW`
```
struct tagPSDW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  unsigned int Flags;
  tagPOINT ptPaperSize;
  tagRECT rtMinMargin;
  tagRECT rtMargin;
  HINSTANCE__ *hInstance;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnPageSetupHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  unsigned __int64 (__fastcall *lpfnPagePaintHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpPageSetupTemplateName;
  void *hPageSetupTemplate;
};

```

### `tagMOUSEHOOKSTRUCT`
```
struct tagMOUSEHOOKSTRUCT
{
  tagPOINT pt;
  HWND__ *hwnd;
  unsigned int wHitTestCode;
  unsigned __int64 dwExtraInfo;
};

```

### `tagCHOOSECOLORA`
```
struct tagCHOOSECOLORA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HWND__ *hInstance;
  unsigned int rgbResult;
  unsigned int *lpCustColors;
  unsigned int Flags;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpTemplateName;
};

```

### `tagLOGFONTA`
```
struct tagLOGFONTA
{
  int lfHeight;
  int lfWidth;
  int lfEscapement;
  int lfOrientation;
  int lfWeight;
  unsigned __int8 lfItalic;
  unsigned __int8 lfUnderline;
  unsigned __int8 lfStrikeOut;
  unsigned __int8 lfCharSet;
  unsigned __int8 lfOutPrecision;
  unsigned __int8 lfClipPrecision;
  unsigned __int8 lfQuality;
  unsigned __int8 lfPitchAndFamily;
  char lfFaceName[32];
};

```

### `tagENUMLOGFONTA`
```
struct tagENUMLOGFONTA
{
  tagLOGFONTA elfLogFont;
  unsigned __int8 elfFullName[64];
  unsigned __int8 elfStyle[32];
};

```

### `tagWCRANGE`
```
struct tagWCRANGE
{
  wchar_t wcLow;
  unsigned __int16 cGlyphs;
};

```

### `tagMOUSEMOVEPOINT`
```
struct tagMOUSEMOVEPOINT
{
  int x;
  int y;
  unsigned int time;
  unsigned __int64 dwExtraInfo;
};

```

### `tagWNDCLASSEXA`
```
struct tagWNDCLASSEXA
{
  unsigned int cbSize;
  unsigned int style;
  __int64 (__fastcall *lpfnWndProc)(HWND__ *, unsigned int, unsigned __int64, __int64);
  int cbClsExtra;
  int cbWndExtra;
  HINSTANCE__ *hInstance;
  HICON__ *hIcon;
  HICON__ *hCursor;
  HBRUSH__ *hbrBackground;
  const char *lpszMenuName;
  const char *lpszClassName;
  HICON__ *hIconSm;
};

```

### `tagDESIGNVECTOR`
```
struct tagDESIGNVECTOR
{
  unsigned int dvReserved;
  unsigned int dvNumAxes;
  int dvValues[16];
};

```

### `tagMETAHEADER`
```
struct __unaligned __declspec(align(2)) tagMETAHEADER
{
  unsigned __int16 mtType;
  unsigned __int16 mtHeaderSize;
  unsigned __int16 mtVersion;
  unsigned int mtSize;
  unsigned __int16 mtNoObjects;
  unsigned int mtMaxRecord;
  unsigned __int16 mtNoParameters;
};

```

### `tagTEXTMETRICW`
```
struct __declspec(align(4)) tagTEXTMETRICW
{
  int tmHeight;
  int tmAscent;
  int tmDescent;
  int tmInternalLeading;
  int tmExternalLeading;
  int tmAveCharWidth;
  int tmMaxCharWidth;
  int tmWeight;
  int tmOverhang;
  int tmDigitizedAspectX;
  int tmDigitizedAspectY;
  wchar_t tmFirstChar;
  wchar_t tmLastChar;
  wchar_t tmDefaultChar;
  wchar_t tmBreakChar;
  unsigned __int8 tmItalic;
  unsigned __int8 tmUnderlined;
  unsigned __int8 tmStruckOut;
  unsigned __int8 tmPitchAndFamily;
  unsigned __int8 tmCharSet;
};

```

### `tagMENUBARINFO`
```
struct __declspec(align(8)) tagMENUBARINFO
{
  unsigned int cbSize;
  tagRECT rcBar;
  HMENU__ *hMenu;
  HWND__ *hwndMenu;
  __int32 fBarFocused : 1;
  __int32 fFocused : 1;
  __int32 fUnused : 30;
};

```

### `tagEMR`
```
struct tagEMR
{
  unsigned int iType;
  unsigned int nSize;
};

```

### `tagEMRSELECTCLIPPATH`
```
struct tagEMRSELECTCLIPPATH
{
  tagEMR emr;
  unsigned int iMode;
};

```

### `tagEMRCREATEDIBPATTERNBRUSHPT`
```
struct tagEMRCREATEDIBPATTERNBRUSHPT
{
  tagEMR emr;
  unsigned int ihBrush;
  unsigned int iUsage;
  unsigned int offBmi;
  unsigned int cbBmi;
  unsigned int offBits;
  unsigned int cbBits;
};

```

### `tagRID_DEVICE_INFO_HID`
```
struct tagRID_DEVICE_INFO_HID
{
  unsigned int dwVendorId;
  unsigned int dwProductId;
  unsigned int dwVersionNumber;
  unsigned __int16 usUsagePage;
  unsigned __int16 usUsage;
};

```

### `tagCAUL`
```
struct tagCAUL
{
  unsigned int cElems;
  unsigned int *pElems;
};

```

### `tagTLIBATTR`
```
struct __declspec(align(4)) tagTLIBATTR
{
  _GUID guid;
  unsigned int lcid;
  tagSYSKIND syskind;
  unsigned __int16 wMajorVerNum;
  unsigned __int16 wMinorVerNum;
  unsigned __int16 wLibFlags;
};

```

### `tagEMRFILLPATH`
```
struct tagEMRFILLPATH
{
  tagEMR emr;
  _RECTL rclBounds;
};

```

### `tagLOGBRUSH`
```
struct tagLOGBRUSH
{
  unsigned int lbStyle;
  unsigned int lbColor;
  unsigned __int64 lbHatch;
};

```

### `tagEMRPOLYLINE`
```
struct tagEMRPOLYLINE
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cptl;
  _POINTL aptl[1];
};

```

### `tagLOGFONTW`
```
struct tagLOGFONTW
{
  int lfHeight;
  int lfWidth;
  int lfEscapement;
  int lfOrientation;
  int lfWeight;
  unsigned __int8 lfItalic;
  unsigned __int8 lfUnderline;
  unsigned __int8 lfStrikeOut;
  unsigned __int8 lfCharSet;
  unsigned __int8 lfOutPrecision;
  unsigned __int8 lfClipPrecision;
  unsigned __int8 lfQuality;
  unsigned __int8 lfPitchAndFamily;
  wchar_t lfFaceName[32];
};

```

### `tagICONMETRICSW`
```
struct tagICONMETRICSW
{
  unsigned int cbSize;
  int iHorzSpacing;
  int iVertSpacing;
  int iTitleWrap;
  tagLOGFONTW lfFont;
};

```

### `tagDVTARGETDEVICE`
```
struct __declspec(align(4)) tagDVTARGETDEVICE
{
  unsigned int tdSize;
  unsigned __int16 tdDriverNameOffset;
  unsigned __int16 tdDeviceNameOffset;
  unsigned __int16 tdPortNameOffset;
  unsigned __int16 tdExtDevmodeOffset;
  unsigned __int8 tdData[1];
};

```

### `tagPALETTEENTRY`
```
struct tagPALETTEENTRY
{
  unsigned __int8 peRed;
  unsigned __int8 peGreen;
  unsigned __int8 peBlue;
  unsigned __int8 peFlags;
};

```

### `tagLOGPALETTE`
```
struct tagLOGPALETTE
{
  unsigned __int16 palVersion;
  unsigned __int16 palNumEntries;
  tagPALETTEENTRY palPalEntry[1];
};

```

### `tagFORMATETC`
```
struct __declspec(align(8)) tagFORMATETC
{
  unsigned __int16 cfFormat;
  tagDVTARGETDEVICE *ptd;
  unsigned int dwAspect;
  int lindex;
  unsigned int tymed;
};

```

### `tagSTATSTG`
```
struct tagSTATSTG
{
  wchar_t *pwcsName;
  unsigned int type;
  _ULARGE_INTEGER cbSize;
  _FILETIME mtime;
  _FILETIME ctime;
  _FILETIME atime;
  unsigned int grfMode;
  unsigned int grfLocksSupported;
  _GUID clsid;
  unsigned int grfStateBits;
  unsigned int reserved;
};

```

### `tagSTGMEDIUM`
```
struct tagSTGMEDIUM
{
  unsigned int tymed;
  $2F48F757A6C6703135D8C2BD08B3E51C ___u1;
  IUnknown *pUnkForRelease;
};

```

### `tagBIND_OPTS`
```
struct tagBIND_OPTS
{
  unsigned int cbStruct;
  unsigned int grfFlags;
  unsigned int grfMode;
  unsigned int dwTickCountDeadline;
};

```

### `tagTEXTMETRICA`
```
struct __declspec(align(4)) tagTEXTMETRICA
{
  int tmHeight;
  int tmAscent;
  int tmDescent;
  int tmInternalLeading;
  int tmExternalLeading;
  int tmAveCharWidth;
  int tmMaxCharWidth;
  int tmWeight;
  int tmOverhang;
  int tmDigitizedAspectX;
  int tmDigitizedAspectY;
  unsigned __int8 tmFirstChar;
  unsigned __int8 tmLastChar;
  unsigned __int8 tmDefaultChar;
  unsigned __int8 tmBreakChar;
  unsigned __int8 tmItalic;
  unsigned __int8 tmUnderlined;
  unsigned __int8 tmStruckOut;
  unsigned __int8 tmPitchAndFamily;
  unsigned __int8 tmCharSet;
};

```

### `tagPANOSE`
```
struct tagPANOSE
{
  unsigned __int8 bFamilyType;
  unsigned __int8 bSerifStyle;
  unsigned __int8 bWeight;
  unsigned __int8 bProportion;
  unsigned __int8 bContrast;
  unsigned __int8 bStrokeVariation;
  unsigned __int8 bArmStyle;
  unsigned __int8 bLetterform;
  unsigned __int8 bMidline;
  unsigned __int8 bXHeight;
};

```

### `tagEXTLOGFONTA`
```
struct __declspec(align(4)) tagEXTLOGFONTA
{
  tagLOGFONTA elfLogFont;
  unsigned __int8 elfFullName[64];
  unsigned __int8 elfStyle[32];
  unsigned int elfVersion;
  unsigned int elfStyleSize;
  unsigned int elfMatch;
  unsigned int elfReserved;
  unsigned __int8 elfVendorId[4];
  unsigned int elfCulture;
  tagPANOSE elfPanose;
};

```

### `tagICONMETRICSA`
```
struct tagICONMETRICSA
{
  unsigned int cbSize;
  int iHorzSpacing;
  int iVertSpacing;
  int iTitleWrap;
  tagLOGFONTA lfFont;
};

```

### `tagSTYLEBUFA`
```
struct tagSTYLEBUFA
{
  unsigned int dwStyle;
  char szDescription[32];
};

```

### `tagTITLEBARINFO`
```
struct tagTITLEBARINFO
{
  unsigned int cbSize;
  tagRECT rcTitleBar;
  unsigned int rgstate[6];
};

```

### `tagSTYLEBUFW`
```
struct tagSTYLEBUFW
{
  unsigned int dwStyle;
  wchar_t szDescription[32];
};

```

### `tagTYPEDESC`
```
struct __declspec(align(8)) tagTYPEDESC
{
  $26C3E3FDE34FBA8023196F66395E3E44 ___u0;
  unsigned __int16 vt;
};

```

### `tagSAFEARRAYBOUND`
```
struct tagSAFEARRAYBOUND
{
  unsigned int cElements;
  int lLbound;
};

```

### `tagARRAYDESC`
```
struct __declspec(align(8)) tagARRAYDESC
{
  tagTYPEDESC tdescElem;
  unsigned __int16 cDims;
  tagSAFEARRAYBOUND rgbounds[1];
};

```

### `tagIDLDESC`
```
struct __declspec(align(8)) tagIDLDESC
{
  unsigned __int64 dwReserved;
  unsigned __int16 wIDLFlags;
};

```

### `tagTYPEATTR`
```
struct tagTYPEATTR
{
  _GUID guid;
  unsigned int lcid;
  unsigned int dwReserved;
  int memidConstructor;
  int memidDestructor;
  wchar_t *lpstrSchema;
  unsigned int cbSizeInstance;
  tagTYPEKIND typekind;
  unsigned __int16 cFuncs;
  unsigned __int16 cVars;
  unsigned __int16 cImplTypes;
  unsigned __int16 cbSizeVft;
  unsigned __int16 cbAlignment;
  unsigned __int16 wTypeFlags;
  unsigned __int16 wMajorVerNum;
  unsigned __int16 wMinorVerNum;
  tagTYPEDESC tdescAlias;
  tagIDLDESC idldescType;
};

```

### `tagVARIANT`
```
struct tagVARIANT
{
  $F712177AAEDF07BC4572319951B1DB6B ___u0;
  IRecordInfo *pRecInfo;
};

```

### `tagDISPPARAMS`
```
struct tagDISPPARAMS
{
  tagVARIANT *rgvarg;
  int *rgdispidNamedArgs;
  unsigned int cArgs;
  unsigned int cNamedArgs;
};

```

### `tagEXCEPINFO`
```
struct __declspec(align(8)) tagEXCEPINFO
{
  unsigned __int16 wCode;
  unsigned __int16 wReserved;
  wchar_t *bstrSource;
  wchar_t *bstrDescription;
  wchar_t *bstrHelpFile;
  unsigned int dwHelpContext;
  void *pvReserved;
  HRESULT (__fastcall *pfnDeferredFillIn)(tagEXCEPINFO *);
  int scode;
};

```

### `tagSAFEARRAY`
```
struct tagSAFEARRAY
{
  unsigned __int16 cDims;
  unsigned __int16 fFeatures;
  unsigned int cbElements;
  unsigned int cLocks;
  void *pvData;
  tagSAFEARRAYBOUND rgsabound[1];
};

```

### `tagDEC`
```
struct tagDEC
{
  unsigned __int16 wReserved;
  $1439E3F76D5605BAE82769B245DD0ED2 ___u1;
  unsigned int Hi32;
  $29CA4D2367829C48774B375DF41C04C7 ___u3;
};

```

### `tagPARAMDESCEX`
```
struct tagPARAMDESCEX
{
  unsigned int cBytes;
  tagVARIANT varDefaultValue;
};

```

### `tagPARAMDESC`
```
struct __declspec(align(8)) tagPARAMDESC
{
  tagPARAMDESCEX *pparamdescex;
  unsigned __int16 wParamFlags;
};

```

### `tagELEMDESC`
```
struct tagELEMDESC
{
  tagTYPEDESC tdesc;
  $B9590E00DCA0EECDEA0B2C4295AB4795 ___u1;
};

```

### `tagFUNCDESC`
```
struct __declspec(align(8)) tagFUNCDESC
{
  int memid;
  int *lprgscode;
  tagELEMDESC *lprgelemdescParam;
  tagFUNCKIND funckind;
  tagINVOKEKIND invkind;
  tagCALLCONV callconv;
  __int16 cParams;
  __int16 cParamsOpt;
  __int16 oVft;
  __int16 cScodes;
  tagELEMDESC elemdescFunc;
  unsigned __int16 wFuncFlags;
};

```

### `tagVARDESC`
```
struct tagVARDESC
{
  int memid;
  wchar_t *lpstrSchema;
  $0C3CB3BC63BAE9681351DEFBC9416CED ___u2;
  tagELEMDESC elemdescVar;
  unsigned __int16 wVarFlags;
  tagVARKIND varkind;
};

```

### `tagHW_PROFILE_INFOA`
```
struct __declspec(align(2)) tagHW_PROFILE_INFOA
{
  unsigned int dwDockInfo;
  char szHwProfileGuid[39];
  char szHwProfileName[80];
};

```

### `tagPOINTS`
```
struct tagPOINTS
{
  __int16 x;
  __int16 y;
};

```

### `tagEMRPOLYLINE16`
```
struct tagEMRPOLYLINE16
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cpts;
  tagPOINTS apts[1];
};

```

### `tagEXTLOGFONTW`
```
struct __declspec(align(4)) tagEXTLOGFONTW
{
  tagLOGFONTW elfLogFont;
  wchar_t elfFullName[64];
  wchar_t elfStyle[32];
  unsigned int elfVersion;
  unsigned int elfStyleSize;
  unsigned int elfMatch;
  unsigned int elfReserved;
  unsigned __int8 elfVendorId[4];
  unsigned int elfCulture;
  tagPANOSE elfPanose;
};

```

### `tagEMREXTCREATEFONTINDIRECTW`
```
struct tagEMREXTCREATEFONTINDIRECTW
{
  tagEMR emr;
  unsigned int ihFont;
  tagEXTLOGFONTW elfw;
};

```

### `tagACTCTXA`
```
struct tagACTCTXA
{
  unsigned int cbSize;
  unsigned int dwFlags;
  const char *lpSource;
  unsigned __int16 wProcessorArchitecture;
  unsigned __int16 wLangId;
  const char *lpAssemblyDirectory;
  const char *lpResourceName;
  const char *lpApplicationName;
  HINSTANCE__ *hModule;
};

```

### `tagPOLYTEXTA`
```
struct tagPOLYTEXTA
{
  int x;
  int y;
  unsigned int n;
  const char *lpstr;
  unsigned int uiFlags;
  tagRECT rcl;
  int *pdx;
};

```

### `tagPRINTPAGERANGE`
```
struct tagPRINTPAGERANGE
{
  unsigned int nFromPage;
  unsigned int nToPage;
};

```

### `tagPDEXA`
```
struct tagPDEXA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  HDC__ *hDC;
  unsigned int Flags;
  unsigned int Flags2;
  unsigned int ExclusionFlags;
  unsigned int nPageRanges;
  unsigned int nMaxPageRanges;
  tagPRINTPAGERANGE *lpPageRanges;
  unsigned int nMinPage;
  unsigned int nMaxPage;
  unsigned int nCopies;
  HINSTANCE__ *hInstance;
  const char *lpPrintTemplateName;
  IUnknown *lpCallback;
  unsigned int nPropertyPages;
  struct _PSP **lphPropertyPages;
  unsigned int nStartPage;
  unsigned int dwResultAction;
};

```

### `tagWINDOWPOS`
```
struct __declspec(align(8)) tagWINDOWPOS
{
  HWND__ *hwnd;
  HWND__ *hwndInsertAfter;
  int x;
  int y;
  int cx;
  int cy;
  unsigned int flags;
};

```

### `tagBITMAPFILEHEADER`
```
struct __unaligned __declspec(align(2)) tagBITMAPFILEHEADER
{
  unsigned __int16 bfType;
  unsigned int bfSize;
  unsigned __int16 bfReserved1;
  unsigned __int16 bfReserved2;
  unsigned int bfOffBits;
};

```

### `tagACTCTX_SECTION_KEYED_DATA_ASSEMBLY_METADATA`
```
struct __declspec(align(8)) tagACTCTX_SECTION_KEYED_DATA_ASSEMBLY_METADATA
{
  void *lpInformation;
  void *lpSectionBase;
  unsigned int ulSectionLength;
  void *lpSectionGlobalDataBase;
  unsigned int ulSectionGlobalDataLength;
};

```

### `tagACTCTX_SECTION_KEYED_DATA`
```
struct tagACTCTX_SECTION_KEYED_DATA
{
  unsigned int cbSize;
  unsigned int ulDataFormatVersion;
  void *lpData;
  unsigned int ulLength;
  void *lpSectionGlobalData;
  unsigned int ulSectionGlobalDataLength;
  void *lpSectionBase;
  unsigned int ulSectionTotalLength;
  void *hActCtx;
  unsigned int ulAssemblyRosterIndex;
  unsigned int ulFlags;
  tagACTCTX_SECTION_KEYED_DATA_ASSEMBLY_METADATA AssemblyMetadata;
};

```

### `tagMDINEXTMENU`
```
struct tagMDINEXTMENU
{
  HMENU__ *hmenuIn;
  HMENU__ *hmenuNext;
  HWND__ *hwndNext;
};

```

### `tagACTCTXW`
```
struct tagACTCTXW
{
  unsigned int cbSize;
  unsigned int dwFlags;
  const wchar_t *lpSource;
  unsigned __int16 wProcessorArchitecture;
  unsigned __int16 wLangId;
  const wchar_t *lpAssemblyDirectory;
  const wchar_t *lpResourceName;
  const wchar_t *lpApplicationName;
  HINSTANCE__ *hModule;
};

```

### `tagHELPWININFOW`
```
struct tagHELPWININFOW
{
  int wStructSize;
  int x;
  int y;
  int dx;
  int dy;
  int wMax;
  wchar_t rgchMember[2];
};

```

### `tagXFORM`
```
struct tagXFORM
{
  float eM11;
  float eM12;
  float eM21;
  float eM22;
  float eDx;
  float eDy;
};

```

### `tagEMRTRANSPARENTBLT`
```
struct tagEMRTRANSPARENTBLT
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int cxDest;
  int cyDest;
  unsigned int dwRop;
  int xSrc;
  int ySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  int cxSrc;
  int cySrc;
};

```

### `tagHARDWAREINPUT`
```
struct tagHARDWAREINPUT
{
  unsigned int uMsg;
  unsigned __int16 wParamL;
  unsigned __int16 wParamH;
};

```

### `tagMEASUREITEMSTRUCT`
```
struct tagMEASUREITEMSTRUCT
{
  unsigned int CtlType;
  unsigned int CtlID;
  unsigned int itemID;
  unsigned int itemWidth;
  unsigned int itemHeight;
  unsigned __int64 itemData;
};

```

### `tagSOLE_AUTHENTICATION_SERVICE`
```
struct __declspec(align(8)) tagSOLE_AUTHENTICATION_SERVICE
{
  unsigned int dwAuthnSvc;
  unsigned int dwAuthzSvc;
  wchar_t *pPrincipalName;
  HRESULT hr;
};

```

### `tagBinaryParam`
```
struct __declspec(align(8)) tagBinaryParam
{
  void *Buffer;
  __int16 Size;
};

```

### `tagRPC_EE_INFO_PARAM`
```
struct tagRPC_EE_INFO_PARAM
{
  tagExtendedErrorParamTypes ParameterType;
  tagRPC_EE_INFO_PARAM::<unnamed_type_u> u;
};

```

### `tagPAINTSTRUCT`
```
struct __declspec(align(8)) tagPAINTSTRUCT
{
  HDC__ *hdc;
  int fErase;
  tagRECT rcPaint;
  int fRestore;
  int fIncUpdate;
  unsigned __int8 rgbReserved[32];
};

```

### `tagCSPLATFORM`
```
struct tagCSPLATFORM
{
  unsigned int dwPlatformId;
  unsigned int dwVersionHi;
  unsigned int dwVersionLo;
  unsigned int dwProcessorArch;
};

```

### `tagENUMLOGFONTW`
```
struct tagENUMLOGFONTW
{
  tagLOGFONTW elfLogFont;
  wchar_t elfFullName[64];
  wchar_t elfStyle[32];
};

```

### `tagLOCALESIGNATURE`
```
struct tagLOCALESIGNATURE
{
  unsigned int lsUsb[4];
  unsigned int lsCsbDefault[2];
  unsigned int lsCsbSupported[2];
};

```

### `tagMINMAXINFO`
```
struct tagMINMAXINFO
{
  tagPOINT ptReserved;
  tagPOINT ptMaxSize;
  tagPOINT ptMaxPosition;
  tagPOINT ptMinTrackSize;
  tagPOINT ptMaxTrackSize;
};

```

### `tagIMEMENUITEMINFOA`
```
struct tagIMEMENUITEMINFOA
{
  unsigned int cbSize;
  unsigned int fType;
  unsigned int fState;
  unsigned int wID;
  HBITMAP__ *hbmpChecked;
  HBITMAP__ *hbmpUnchecked;
  unsigned int dwItemData;
  char szString[80];
  HBITMAP__ *hbmpItem;
};

```

### `tagEMRFILLRGN`
```
struct __declspec(align(4)) tagEMRFILLRGN
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cbRgnData;
  unsigned int ihBrush;
  unsigned __int8 RgnData[1];
};

```

### `tagRemFORMATETC`
```
struct tagRemFORMATETC
{
  unsigned int cfFormat;
  unsigned int ptd;
  unsigned int dwAspect;
  int lindex;
  unsigned int tymed;
};

```

### `tagBITMAPCOREHEADER`
```
struct tagBITMAPCOREHEADER
{
  unsigned int bcSize;
  unsigned __int16 bcWidth;
  unsigned __int16 bcHeight;
  unsigned __int16 bcPlanes;
  unsigned __int16 bcBitCount;
};

```

### `tagSIZE`
```
struct tagSIZE
{
  int cx;
  int cy;
};

```

### `tagENHMETAHEADER`
```
struct tagENHMETAHEADER
{
  unsigned int iType;
  unsigned int nSize;
  _RECTL rclBounds;
  _RECTL rclFrame;
  unsigned int dSignature;
  unsigned int nVersion;
  unsigned int nBytes;
  unsigned int nRecords;
  unsigned __int16 nHandles;
  unsigned __int16 sReserved;
  unsigned int nDescription;
  unsigned int offDescription;
  unsigned int nPalEntries;
  tagSIZE szlDevice;
  tagSIZE szlMillimeters;
  unsigned int cbPixelFormat;
  unsigned int offPixelFormat;
  unsigned int bOpenGL;
  tagSIZE szlMicrometers;
};

```

### `tagACTCTX_SECTION_KEYED_DATA_2600`
```
struct __declspec(align(8)) tagACTCTX_SECTION_KEYED_DATA_2600
{
  unsigned int cbSize;
  unsigned int ulDataFormatVersion;
  void *lpData;
  unsigned int ulLength;
  void *lpSectionGlobalData;
  unsigned int ulSectionGlobalDataLength;
  void *lpSectionBase;
  unsigned int ulSectionTotalLength;
  void *hActCtx;
  unsigned int ulAssemblyRosterIndex;
};

```

### `tagBITMAP`
```
struct tagBITMAP
{
  int bmType;
  int bmWidth;
  int bmHeight;
  int bmWidthBytes;
  unsigned __int16 bmPlanes;
  unsigned __int16 bmBitsPixel;
  void *bmBits;
};

```

### `tagBITMAPINFOHEADER`
```
struct tagBITMAPINFOHEADER
{
  unsigned int biSize;
  int biWidth;
  int biHeight;
  unsigned __int16 biPlanes;
  unsigned __int16 biBitCount;
  unsigned int biCompression;
  unsigned int biSizeImage;
  int biXPelsPerMeter;
  int biYPelsPerMeter;
  unsigned int biClrUsed;
  unsigned int biClrImportant;
};

```

### `tagDIBSECTION`
```
struct __declspec(align(8)) tagDIBSECTION
{
  tagBITMAP dsBm;
  tagBITMAPINFOHEADER dsBmih;
  unsigned int dsBitfields[3];
  void *dshSection;
  unsigned int dsOffset;
};

```

### `tagEMRALPHABLEND`
```
struct tagEMRALPHABLEND
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int cxDest;
  int cyDest;
  unsigned int dwRop;
  int xSrc;
  int ySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  int cxSrc;
  int cySrc;
};

```

### `tagMONITORINFOEXW`
```
struct __cppobj tagMONITORINFOEXW : tagMONITORINFO
{
  wchar_t szDevice[32];
};

```

### `tagAXISINFOA`
```
struct tagAXISINFOA
{
  int axMinValue;
  int axMaxValue;
  unsigned __int8 axAxisName[16];
};

```

### `tagAXESLISTA`
```
struct tagAXESLISTA
{
  unsigned int axlReserved;
  unsigned int axlNumAxes;
  tagAXISINFOA axlAxisInfo[16];
};

```

### `tagTRACKMOUSEEVENT`
```
struct __declspec(align(8)) tagTRACKMOUSEEVENT
{
  unsigned int cbSize;
  unsigned int dwFlags;
  HWND__ *hwndTrack;
  unsigned int dwHoverTime;
};

```

### `tagNMHDR`
```
struct __declspec(align(8)) tagNMHDR
{
  HWND__ *hwndFrom;
  unsigned __int64 idFrom;
  unsigned int code;
};

```

### `tagABORTPATH`
```
struct tagABORTPATH
{
  tagEMR emr;
};

```

### `tagHW_PROFILE_INFOW`
```
struct __declspec(align(4)) tagHW_PROFILE_INFOW
{
  unsigned int dwDockInfo;
  wchar_t szHwProfileGuid[39];
  wchar_t szHwProfileName[80];
};

```

### `tagEMRPOLYDRAW16`
```
struct __declspec(align(4)) tagEMRPOLYDRAW16
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cpts;
  tagPOINTS apts[1];
  unsigned __int8 abTypes[1];
};

```

### `tagPDA`
```
struct tagPDA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  HDC__ *hDC;
  unsigned int Flags;
  unsigned __int16 nFromPage;
  unsigned __int16 nToPage;
  unsigned __int16 nMinPage;
  unsigned __int16 nMaxPage;
  unsigned __int16 nCopies;
  HINSTANCE__ *hInstance;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnPrintHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  unsigned __int64 (__fastcall *lpfnSetupHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpPrintTemplateName;
  const char *lpSetupTemplateName;
  void *hPrintTemplate;
  void *hSetupTemplate;
};

```

### `tagHELPINFO`
```
struct tagHELPINFO
{
  unsigned int cbSize;
  int iContextType;
  int iCtrlId;
  void *hItemHandle;
  unsigned __int64 dwContextId;
  tagPOINT MousePos;
};

```

### `tagMSGBOXPARAMSW`
```
struct __declspec(align(8)) tagMSGBOXPARAMSW
{
  unsigned int cbSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  const wchar_t *lpszText;
  const wchar_t *lpszCaption;
  unsigned int dwStyle;
  const wchar_t *lpszIcon;
  unsigned __int64 dwContextHelpId;
  void (__fastcall *lpfnMsgBoxCallback)(tagHELPINFO *);
  unsigned int dwLanguageId;
};

```

### `tagCLIENTCREATESTRUCT`
```
struct __declspec(align(8)) tagCLIENTCREATESTRUCT
{
  void *hWindowMenu;
  unsigned int idFirstChild;
};

```

### `tagGESTUREINFO`
```
struct __declspec(align(8)) tagGESTUREINFO
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int dwID;
  HWND__ *hwndTarget;
  tagPOINTS ptsLocation;
  unsigned int dwInstanceID;
  unsigned int dwSequenceID;
  unsigned __int64 ullArguments;
  unsigned int cbExtraArgs;
};

```

### `tagEXTLOGPEN32`
```
struct tagEXTLOGPEN32
{
  unsigned int elpPenStyle;
  unsigned int elpWidth;
  unsigned int elpBrushStyle;
  unsigned int elpColor;
  unsigned int elpHatch;
  unsigned int elpNumEntries;
  unsigned int elpStyleEntry[1];
};

```

### `tagENUMLOGFONTEXW`
```
struct tagENUMLOGFONTEXW
{
  tagLOGFONTW elfLogFont;
  wchar_t elfFullName[64];
  wchar_t elfStyle[32];
  wchar_t elfScript[32];
};

```

### `tagENUMLOGFONTEXDVW`
```
struct tagENUMLOGFONTEXDVW
{
  tagENUMLOGFONTEXW elfEnumLogfontEx;
  tagDESIGNVECTOR elfDesignVector;
};

```

### `tagEMRELLIPSE`
```
struct tagEMRELLIPSE
{
  tagEMR emr;
  _RECTL rclBox;
};

```

### `tagNEWTEXTMETRICW`
```
struct tagNEWTEXTMETRICW
{
  int tmHeight;
  int tmAscent;
  int tmDescent;
  int tmInternalLeading;
  int tmExternalLeading;
  int tmAveCharWidth;
  int tmMaxCharWidth;
  int tmWeight;
  int tmOverhang;
  int tmDigitizedAspectX;
  int tmDigitizedAspectY;
  wchar_t tmFirstChar;
  wchar_t tmLastChar;
  wchar_t tmDefaultChar;
  wchar_t tmBreakChar;
  unsigned __int8 tmItalic;
  unsigned __int8 tmUnderlined;
  unsigned __int8 tmStruckOut;
  unsigned __int8 tmPitchAndFamily;
  unsigned __int8 tmCharSet;
  unsigned int ntmFlags;
  unsigned int ntmSizeEM;
  unsigned int ntmCellHeight;
  unsigned int ntmAvgWidth;
};

```

### `tagFONTSIGNATURE`
```
struct tagFONTSIGNATURE
{
  unsigned int fsUsb[4];
  unsigned int fsCsb[2];
};

```

### `tagNEWTEXTMETRICEXW`
```
struct tagNEWTEXTMETRICEXW
{
  tagNEWTEXTMETRICW ntmTm;
  tagFONTSIGNATURE ntmFontSig;
};

```

### `tagAXISINFOW`
```
struct tagAXISINFOW
{
  int axMinValue;
  int axMaxValue;
  wchar_t axAxisName[16];
};

```

### `tagAXESLISTW`
```
struct tagAXESLISTW
{
  unsigned int axlReserved;
  unsigned int axlNumAxes;
  tagAXISINFOW axlAxisInfo[16];
};

```

### `tagENUMTEXTMETRICW`
```
struct tagENUMTEXTMETRICW
{
  tagNEWTEXTMETRICEXW etmNewTextMetricEx;
  tagAXESLISTW etmAxesList;
};

```

### `tagEMREXCLUDECLIPRECT`
```
struct tagEMREXCLUDECLIPRECT
{
  tagEMR emr;
  _RECTL rclClip;
};

```

### `tagGESTURENOTIFYSTRUCT`
```
struct tagGESTURENOTIFYSTRUCT
{
  unsigned int cbSize;
  unsigned int dwFlags;
  HWND__ *hwndTarget;
  tagPOINTS ptsLocation;
  unsigned int dwInstanceID;
};

```

### `tagRAWMOUSE`
```
struct tagRAWMOUSE
{
  unsigned __int16 usFlags;
  $7A001CDBB2BC712910161E3151FD4BDB ___u1;
  unsigned int ulRawButtons;
  int lLastX;
  int lLastY;
  unsigned int ulExtraInformation;
};

```

### `tagNCCALCSIZE_PARAMS`
```
struct tagNCCALCSIZE_PARAMS
{
  tagRECT rgrc[3];
  tagWINDOWPOS *lppos;
};

```

### `tagPOINTFX`
```
struct tagPOINTFX
{
  _FIXED x;
  _FIXED y;
};

```

### `tagTTPOLYCURVE`
```
struct tagTTPOLYCURVE
{
  unsigned __int16 wType;
  unsigned __int16 cpfx;
  tagPOINTFX apfx[1];
};

```

### `tagRPCOLEMESSAGE`
```
struct __declspec(align(8)) tagRPCOLEMESSAGE
{
  void *reserved1;
  unsigned int dataRepresentation;
  void *Buffer;
  unsigned int cbBuffer;
  unsigned int iMethod;
  void *reserved2[5];
  unsigned int rpcFlags;
};

```

### `tagINPUT_MESSAGE_SOURCE`
```
struct tagINPUT_MESSAGE_SOURCE
{
  tagINPUT_MESSAGE_DEVICE_TYPE deviceType;
  tagINPUT_MESSAGE_ORIGIN_ID originId;
};

```

### `tagMULTI_QI`
```
struct __declspec(align(8)) tagMULTI_QI
{
  const _GUID *pIID;
  IUnknown *pItf;
  HRESULT hr;
};

```

### `tagEMRSETWORLDTRANSFORM`
```
struct tagEMRSETWORLDTRANSFORM
{
  tagEMR emr;
  tagXFORM xform;
};

```

### `tagCABSTR`
```
struct tagCABSTR
{
  unsigned int cElems;
  wchar_t **pElems;
};

```

### `tagDRAWITEMSTRUCT`
```
struct tagDRAWITEMSTRUCT
{
  unsigned int CtlType;
  unsigned int CtlID;
  unsigned int itemID;
  unsigned int itemAction;
  unsigned int itemState;
  HWND__ *hwndItem;
  HDC__ *hDC;
  tagRECT rcItem;
  unsigned __int64 itemData;
};

```

### `tagIMEMENUITEMINFOW`
```
struct tagIMEMENUITEMINFOW
{
  unsigned int cbSize;
  unsigned int fType;
  unsigned int fState;
  unsigned int wID;
  HBITMAP__ *hbmpChecked;
  HBITMAP__ *hbmpUnchecked;
  unsigned int dwItemData;
  wchar_t szString[80];
  HBITMAP__ *hbmpItem;
};

```

### `tagOBJECTDESCRIPTOR`
```
struct tagOBJECTDESCRIPTOR
{
  unsigned int cbSize;
  _GUID clsid;
  unsigned int dwDrawAspect;
  tagSIZE sizel;
  _POINTL pointl;
  unsigned int dwStatus;
  unsigned int dwFullUserTypeName;
  unsigned int dwSrcOfCopy;
};

```

### `tagNONCLIENTMETRICSA`
```
struct tagNONCLIENTMETRICSA
{
  unsigned int cbSize;
  int iBorderWidth;
  int iScrollWidth;
  int iScrollHeight;
  int iCaptionWidth;
  int iCaptionHeight;
  tagLOGFONTA lfCaptionFont;
  int iSmCaptionWidth;
  int iSmCaptionHeight;
  tagLOGFONTA lfSmCaptionFont;
  int iMenuWidth;
  int iMenuHeight;
  tagLOGFONTA lfMenuFont;
  tagLOGFONTA lfStatusFont;
  tagLOGFONTA lfMessageFont;
  int iPaddedBorderWidth;
};

```

### `tagWNDCLASSA`
```
struct tagWNDCLASSA
{
  unsigned int style;
  __int64 (__fastcall *lpfnWndProc)(HWND__ *, unsigned int, unsigned __int64, __int64);
  int cbClsExtra;
  int cbWndExtra;
  HINSTANCE__ *hInstance;
  HICON__ *hIcon;
  HICON__ *hCursor;
  HBRUSH__ *hbrBackground;
  const char *lpszMenuName;
  const char *lpszClassName;
};

```

### `tagEMRRESIZEPALETTE`
```
struct tagEMRRESIZEPALETTE
{
  tagEMR emr;
  unsigned int ihPal;
  unsigned int cEntries;
};

```

### `tagCREATESTRUCTA`
```
struct __declspec(align(8)) tagCREATESTRUCTA
{
  void *lpCreateParams;
  HINSTANCE__ *hInstance;
  HMENU__ *hMenu;
  HWND__ *hwndParent;
  int cy;
  int cx;
  int y;
  int x;
  int style;
  const char *lpszName;
  const char *lpszClass;
  unsigned int dwExStyle;
};

```

### `tagCBT_CREATEWNDA`
```
struct tagCBT_CREATEWNDA
{
  tagCREATESTRUCTA *lpcs;
  HWND__ *hwndInsertAfter;
};

```

### `tagENUMLOGFONTEXA`
```
struct tagENUMLOGFONTEXA
{
  tagLOGFONTA elfLogFont;
  unsigned __int8 elfFullName[64];
  unsigned __int8 elfStyle[32];
  unsigned __int8 elfScript[32];
};

```

### `tagENUMLOGFONTEXDVA`
```
struct tagENUMLOGFONTEXDVA
{
  tagENUMLOGFONTEXA elfEnumLogfontEx;
  tagDESIGNVECTOR elfDesignVector;
};

```

### `tagEMREXTCREATEPEN`
```
struct tagEMREXTCREATEPEN
{
  tagEMR emr;
  unsigned int ihPen;
  unsigned int offBmi;
  unsigned int cbBmi;
  unsigned int offBits;
  unsigned int cbBits;
  tagEXTLOGPEN32 elp;
};

```

### `tagEMREXTSELECTCLIPRGN`
```
struct __declspec(align(4)) tagEMREXTSELECTCLIPRGN
{
  tagEMR emr;
  unsigned int cbRgnData;
  unsigned int iMode;
  unsigned __int8 RgnData[1];
};

```

### `tagRPC_CALL_ATTRIBUTES_V1_W`
```
struct __declspec(align(8)) tagRPC_CALL_ATTRIBUTES_V1_W
{
  unsigned int Version;
  unsigned int Flags;
  unsigned int ServerPrincipalNameBufferLength;
  unsigned __int16 *ServerPrincipalName;
  unsigned int ClientPrincipalNameBufferLength;
  unsigned __int16 *ClientPrincipalName;
  unsigned int AuthenticationLevel;
  unsigned int AuthenticationService;
  int NullSession;
};

```

### `tagCIEXYZ`
```
struct tagCIEXYZ
{
  int ciexyzX;
  int ciexyzY;
  int ciexyzZ;
};

```

### `tagPOLYTEXTW`
```
struct tagPOLYTEXTW
{
  int x;
  int y;
  unsigned int n;
  const wchar_t *lpstr;
  unsigned int uiFlags;
  tagRECT rcl;
  int *pdx;
};

```

### `tagCREATESTRUCTW`
```
struct __declspec(align(8)) tagCREATESTRUCTW
{
  void *lpCreateParams;
  HINSTANCE__ *hInstance;
  HMENU__ *hMenu;
  HWND__ *hwndParent;
  int cy;
  int cx;
  int y;
  int x;
  int style;
  const wchar_t *lpszName;
  const wchar_t *lpszClass;
  unsigned int dwExStyle;
};

```

### `tagCBT_CREATEWNDW`
```
struct tagCBT_CREATEWNDW
{
  tagCREATESTRUCTW *lpcs;
  HWND__ *hwndInsertAfter;
};

```

### `tagLOGBRUSH32`
```
struct tagLOGBRUSH32
{
  unsigned int lbStyle;
  unsigned int lbColor;
  unsigned int lbHatch;
};

```

### `tagI_RpcProxyCallbackInterface`
```
struct tagI_RpcProxyCallbackInterface
{
  int (__fastcall *IsValidMachineFn)(unsigned __int16 *, unsigned __int16 *, unsigned int);
  int (__fastcall *GetClientAddressFn)(void *, char *, unsigned int *);
  int (__fastcall *GetConnectionTimeoutFn)(unsigned int *);
  int (__fastcall *PerformCalloutFn)(void *, _RDR_CALLOUT_STATE *, _RPC_HTTP_REDIRECTOR_STAGE);
  void (__fastcall *FreeCalloutStateFn)(_RDR_CALLOUT_STATE *);
  int (__fastcall *GetClientSessionAndResourceUUIDFn)(void *, int *, _GUID *, int *, _GUID *);
  int (__fastcall *ProxyFilterIfFn)(void *, _GUID *, unsigned __int16, int *);
  void (__fastcall *RpcProxyUpdatePerfCounterFn)(RpcProxyPerfCounters, int, unsigned int);
  void (__fastcall *RpcProxyUpdatePerfCounterBackendServerFn)(unsigned __int16 *, int);
};

```

### `tagSTATPROPSTG`
```
struct __declspec(align(4)) tagSTATPROPSTG
{
  wchar_t *lpwstrName;
  unsigned int propid;
  unsigned __int16 vt;
};

```

### `tagCOMPOSITIONFORM`
```
struct tagCOMPOSITIONFORM
{
  unsigned int dwStyle;
  tagPOINT ptCurrentPos;
  tagRECT rcArea;
};

```

### `tagOLEVERB`
```
struct tagOLEVERB
{
  int lVerb;
  wchar_t *lpszVerbName;
  unsigned int fuFlags;
  unsigned int grfAttribs;
};

```

### `tagLOGPEN`
```
struct tagLOGPEN
{
  unsigned int lopnStyle;
  tagPOINT lopnWidth;
  unsigned int lopnColor;
};

```

### `tagEMREXTESCAPE`
```
struct __declspec(align(4)) tagEMREXTESCAPE
{
  tagEMR emr;
  int iEscape;
  int cbEscData;
  unsigned __int8 EscData[1];
};

```

### `tagSTATDATA`
```
struct __declspec(align(8)) tagSTATDATA
{
  tagFORMATETC formatetc;
  unsigned int advf;
  IAdviseSink *pAdvSink;
  unsigned int dwConnection;
};

```

### `tagENUMUILANG`
```
struct tagENUMUILANG
{
  unsigned int NumOfEnumUILang;
  unsigned int SizeOfEnumUIBuffer;
  unsigned __int16 *pEnumUIBuffer;
};

```

### `tagDEBUGHOOKINFO`
```
struct __declspec(align(8)) tagDEBUGHOOKINFO
{
  unsigned int idThread;
  unsigned int idThreadInstaller;
  __int64 lParam;
  unsigned __int64 wParam;
  int code;
};

```

### `tagKBDLLHOOKSTRUCT`
```
struct tagKBDLLHOOKSTRUCT
{
  unsigned int vkCode;
  unsigned int scanCode;
  unsigned int flags;
  unsigned int time;
  unsigned __int64 dwExtraInfo;
};

```

### `tagBSTRBLOB`
```
struct tagBSTRBLOB
{
  unsigned int cbSize;
  unsigned __int8 *pData;
};

```

### `tagMULTIKEYHELPA`
```
struct __declspec(align(4)) tagMULTIKEYHELPA
{
  unsigned int mkSize;
  char mkKeylist;
  char szKeyphrase[1];
};

```

### `tagMULTIKEYHELPW`
```
struct tagMULTIKEYHELPW
{
  unsigned int mkSize;
  wchar_t mkKeylist;
  wchar_t szKeyphrase[1];
};

```

### `tagEMRMODIFYWORLDTRANSFORM`
```
struct tagEMRMODIFYWORLDTRANSFORM
{
  tagEMR emr;
  tagXFORM xform;
  unsigned int iMode;
};

```

### `tagOFN_NT4W`
```
struct tagOFN_NT4W
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  const wchar_t *lpstrFilter;
  wchar_t *lpstrCustomFilter;
  unsigned int nMaxCustFilter;
  unsigned int nFilterIndex;
  wchar_t *lpstrFile;
  unsigned int nMaxFile;
  wchar_t *lpstrFileTitle;
  unsigned int nMaxFileTitle;
  const wchar_t *lpstrInitialDir;
  const wchar_t *lpstrTitle;
  unsigned int Flags;
  unsigned __int16 nFileOffset;
  unsigned __int16 nFileExtension;
  const wchar_t *lpstrDefExt;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpTemplateName;
};

```

### `tagEMRGLSBOUNDEDRECORD`
```
struct __declspec(align(4)) tagEMRGLSBOUNDEDRECORD
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagLAYERPLANEDESCRIPTOR`
```
struct tagLAYERPLANEDESCRIPTOR
{
  unsigned __int16 nSize;
  unsigned __int16 nVersion;
  unsigned int dwFlags;
  unsigned __int8 iPixelType;
  unsigned __int8 cColorBits;
  unsigned __int8 cRedBits;
  unsigned __int8 cRedShift;
  unsigned __int8 cGreenBits;
  unsigned __int8 cGreenShift;
  unsigned __int8 cBlueBits;
  unsigned __int8 cBlueShift;
  unsigned __int8 cAlphaBits;
  unsigned __int8 cAlphaShift;
  unsigned __int8 cAccumBits;
  unsigned __int8 cAccumRedBits;
  unsigned __int8 cAccumGreenBits;
  unsigned __int8 cAccumBlueBits;
  unsigned __int8 cAccumAlphaBits;
  unsigned __int8 cDepthBits;
  unsigned __int8 cStencilBits;
  unsigned __int8 cAuxBuffers;
  unsigned __int8 iLayerPlane;
  unsigned __int8 bReserved;
  unsigned int crTransparent;
};

```

### `tagFILTERKEYS`
```
struct tagFILTERKEYS
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int iWaitMSec;
  unsigned int iDelayMSec;
  unsigned int iRepeatMSec;
  unsigned int iBounceMSec;
};

```

### `tagPELARRAY`
```
struct __declspec(align(4)) tagPELARRAY
{
  int paXCount;
  int paYCount;
  int paXExt;
  int paYExt;
  unsigned __int8 paRGBs;
};

```

### `tagWNDCLASSW`
```
struct tagWNDCLASSW
{
  unsigned int style;
  __int64 (__fastcall *lpfnWndProc)(HWND__ *, unsigned int, unsigned __int64, __int64);
  int cbClsExtra;
  int cbWndExtra;
  HINSTANCE__ *hInstance;
  HICON__ *hIcon;
  HICON__ *hCursor;
  HBRUSH__ *hbrBackground;
  const wchar_t *lpszMenuName;
  const wchar_t *lpszClassName;
};

```

### `tagCBTACTIVATESTRUCT`
```
struct tagCBTACTIVATESTRUCT
{
  int fMouse;
  HWND__ *hWndActive;
};

```

### `tagDRAWTEXTPARAMS`
```
struct tagDRAWTEXTPARAMS
{
  unsigned int cbSize;
  int iTabLength;
  int iLeftMargin;
  int iRightMargin;
  unsigned int uiLengthDrawn;
};

```

### `tagRPC_CALL_ATTRIBUTES_V2_W`
```
struct __declspec(align(8)) tagRPC_CALL_ATTRIBUTES_V2_W
{
  unsigned int Version;
  unsigned int Flags;
  unsigned int ServerPrincipalNameBufferLength;
  unsigned __int16 *ServerPrincipalName;
  unsigned int ClientPrincipalNameBufferLength;
  unsigned __int16 *ClientPrincipalName;
  unsigned int AuthenticationLevel;
  unsigned int AuthenticationService;
  int NullSession;
  int KernelModeCaller;
  unsigned int ProtocolSequence;
  tagRpcCallClientLocality IsClientLocal;
  void *ClientPID;
  unsigned int CallStatus;
  tagRpcCallType CallType;
  _RPC_CALL_LOCAL_ADDRESS_V1 *CallLocalAddress;
  unsigned __int16 OpNum;
  _GUID InterfaceUuid;
};

```

### `tagUPDATELAYEREDWINDOWINFO`
```
struct tagUPDATELAYEREDWINDOWINFO
{
  unsigned int cbSize;
  HDC__ *hdcDst;
  const tagPOINT *pptDst;
  const tagSIZE *psize;
  HDC__ *hdcSrc;
  const tagPOINT *pptSrc;
  unsigned int crKey;
  const _BLENDFUNCTION *pblend;
  unsigned int dwFlags;
  const tagRECT *prcDirty;
};

```

### `tagAUDIODESCRIPTION`
```
struct tagAUDIODESCRIPTION
{
  unsigned int cbSize;
  int Enabled;
  unsigned int Locale;
};

```

### `tagEVENTMSG`
```
struct tagEVENTMSG
{
  unsigned int message;
  unsigned int paramL;
  unsigned int paramH;
  unsigned int time;
  HWND__ *hwnd;
};

```

### `tagHARDWAREHOOKSTRUCT`
```
struct tagHARDWAREHOOKSTRUCT
{
  HWND__ *hwnd;
  unsigned int message;
  unsigned __int64 wParam;
  __int64 lParam;
};

```

### `tagEMRTEXT`
```
struct tagEMRTEXT
{
  _POINTL ptlReference;
  unsigned int nChars;
  unsigned int offString;
  unsigned int fOptions;
  _RECTL rcl;
  unsigned int offDx;
};

```

### `tagEMREXTTEXTOUTA`
```
struct tagEMREXTTEXTOUTA
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int iGraphicsMode;
  float exScale;
  float eyScale;
  tagEMRTEXT emrtext;
};

```

### `tagRAWHID`
```
struct __declspec(align(4)) tagRAWHID
{
  unsigned int dwSizeHid;
  unsigned int dwCount;
  unsigned __int8 bRawData[1];
};

```

### `tagCUSTDATAITEM`
```
struct tagCUSTDATAITEM
{
  _GUID guid;
  tagVARIANT varValue;
};

```

### `tagCUSTDATA`
```
struct tagCUSTDATA
{
  unsigned int cCustData;
  tagCUSTDATAITEM *prgCustData;
};

```

### `tagIMECHARPOSITION`
```
struct tagIMECHARPOSITION
{
  unsigned int dwSize;
  unsigned int dwCharPos;
  tagPOINT pt;
  unsigned int cLineHeight;
  tagRECT rcDocument;
};

```

### `tagCADBL`
```
struct tagCADBL
{
  unsigned int cElems;
  long double *pElems;
};

```

### `tagRemHMETAFILEPICT`
```
struct __declspec(align(4)) tagRemHMETAFILEPICT
{
  int mm;
  int xExt;
  int yExt;
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagCOLORADJUSTMENT`
```
struct tagCOLORADJUSTMENT
{
  unsigned __int16 caSize;
  unsigned __int16 caFlags;
  unsigned __int16 caIlluminantIndex;
  unsigned __int16 caRedGamma;
  unsigned __int16 caGreenGamma;
  unsigned __int16 caBlueGamma;
  unsigned __int16 caReferenceBlack;
  unsigned __int16 caReferenceWhite;
  __int16 caContrast;
  __int16 caBrightness;
  __int16 caColorfulness;
  __int16 caRedGreenTint;
};

```

### `tagMENUGETOBJECTINFO`
```
struct tagMENUGETOBJECTINFO
{
  unsigned int dwFlags;
  unsigned int uPos;
  HMENU__ *hmenu;
  void *riid;
  void *pvObj;
};

```

### `tagEMRPOLYPOLYLINE`
```
struct tagEMRPOLYPOLYLINE
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int nPolys;
  unsigned int cptl;
  unsigned int aPolyCounts[1];
  _POINTL aptl[1];
};

```

### `tagSOUNDSENTRYA`
```
struct __declspec(align(8)) tagSOUNDSENTRYA
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int iFSTextEffect;
  unsigned int iFSTextEffectMSec;
  unsigned int iFSTextEffectColorBits;
  unsigned int iFSGrafEffect;
  unsigned int iFSGrafEffectMSec;
  unsigned int iFSGrafEffectColor;
  unsigned int iWindowsEffect;
  unsigned int iWindowsEffectMSec;
  char *lpszWindowsEffectDLL;
  unsigned int iWindowsEffectOrdinal;
};

```

### `tagICEXYZTRIPLE`
```
struct tagICEXYZTRIPLE
{
  tagCIEXYZ ciexyzRed;
  tagCIEXYZ ciexyzGreen;
  tagCIEXYZ ciexyzBlue;
};

```

### `tagRemBRUSH`
```
struct __declspec(align(4)) tagRemBRUSH
{
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagRAWKEYBOARD`
```
struct tagRAWKEYBOARD
{
  unsigned __int16 MakeCode;
  unsigned __int16 Flags;
  unsigned __int16 Reserved;
  unsigned __int16 VKey;
  unsigned int Message;
  unsigned int ExtraInformation;
};

```

### `tagRAWINPUTHEADER`
```
struct tagRAWINPUTHEADER
{
  unsigned int dwType;
  unsigned int dwSize;
  void *hDevice;
  unsigned __int64 wParam;
};

```

### `tagNEWTEXTMETRICA`
```
struct tagNEWTEXTMETRICA
{
  int tmHeight;
  int tmAscent;
  int tmDescent;
  int tmInternalLeading;
  int tmExternalLeading;
  int tmAveCharWidth;
  int tmMaxCharWidth;
  int tmWeight;
  int tmOverhang;
  int tmDigitizedAspectX;
  int tmDigitizedAspectY;
  unsigned __int8 tmFirstChar;
  unsigned __int8 tmLastChar;
  unsigned __int8 tmDefaultChar;
  unsigned __int8 tmBreakChar;
  unsigned __int8 tmItalic;
  unsigned __int8 tmUnderlined;
  unsigned __int8 tmStruckOut;
  unsigned __int8 tmPitchAndFamily;
  unsigned __int8 tmCharSet;
  unsigned int ntmFlags;
  unsigned int ntmSizeEM;
  unsigned int ntmCellHeight;
  unsigned int ntmAvgWidth;
};

```

### `tagEMRSETPALETTEENTRIES`
```
struct tagEMRSETPALETTEENTRIES
{
  tagEMR emr;
  unsigned int ihPal;
  unsigned int iStart;
  unsigned int cEntries;
  tagPALETTEENTRY aPalEntries[1];
};

```

### `tagFINDREPLACEA`
```
struct tagFINDREPLACEA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  unsigned int Flags;
  char *lpstrFindWhat;
  char *lpstrReplaceWith;
  unsigned __int16 wFindWhatLen;
  unsigned __int16 wReplaceWithLen;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpTemplateName;
};

```

### `tagCOMPAREITEMSTRUCT`
```
struct __declspec(align(8)) tagCOMPAREITEMSTRUCT
{
  unsigned int CtlType;
  unsigned int CtlID;
  HWND__ *hwndItem;
  unsigned int itemID1;
  unsigned __int64 itemData1;
  unsigned int itemID2;
  unsigned __int64 itemData2;
  unsigned int dwLocaleId;
};

```

### `tagRemSTGMEDIUM`
```
struct __declspec(align(4)) tagRemSTGMEDIUM
{
  unsigned int tymed;
  unsigned int dwHandleType;
  unsigned int pData;
  unsigned int pUnkForRelease;
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagMETAFILEPICT`
```
struct tagMETAFILEPICT
{
  int mm;
  int xExt;
  int yExt;
  HMETAFILE__ *hMF;
};

```

### `tagEMRSELECTPALETTE`
```
struct tagEMRSELECTPALETTE
{
  tagEMR emr;
  unsigned int ihPal;
};

```

### `tagPDW`
```
struct tagPDW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  HDC__ *hDC;
  unsigned int Flags;
  unsigned __int16 nFromPage;
  unsigned __int16 nToPage;
  unsigned __int16 nMinPage;
  unsigned __int16 nMaxPage;
  unsigned __int16 nCopies;
  HINSTANCE__ *hInstance;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnPrintHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  unsigned __int64 (__fastcall *lpfnSetupHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpPrintTemplateName;
  const wchar_t *lpSetupTemplateName;
  void *hPrintTemplate;
  void *hSetupTemplate;
};

```

### `tagDROPSTRUCT`
```
struct __declspec(align(8)) tagDROPSTRUCT
{
  HWND__ *hwndSource;
  HWND__ *hwndSink;
  unsigned int wFmt;
  unsigned __int64 dwData;
  tagPOINT ptDrop;
  unsigned int dwControlData;
};

```

### `tagNEWTEXTMETRICEXA`
```
struct tagNEWTEXTMETRICEXA
{
  tagNEWTEXTMETRICA ntmTm;
  tagFONTSIGNATURE ntmFontSig;
};

```

### `tagENUMTEXTMETRICA`
```
struct tagENUMTEXTMETRICA
{
  tagNEWTEXTMETRICEXA etmNewTextMetricEx;
  tagAXESLISTA etmAxesList;
};

```

### `tagEXTLOGPEN`
```
struct tagEXTLOGPEN
{
  unsigned int elpPenStyle;
  unsigned int elpWidth;
  unsigned int elpBrushStyle;
  unsigned int elpColor;
  unsigned __int64 elpHatch;
  unsigned int elpNumEntries;
  unsigned int elpStyleEntry[1];
};

```

### `tagRECONVERTSTRING`
```
struct tagRECONVERTSTRING
{
  unsigned int dwSize;
  unsigned int dwVersion;
  unsigned int dwStrLen;
  unsigned int dwStrOffset;
  unsigned int dwCompStrLen;
  unsigned int dwCompStrOffset;
  unsigned int dwTargetStrLen;
  unsigned int dwTargetStrOffset;
};

```

### `tagEMRPOLYTEXTOUTA`
```
struct tagEMRPOLYTEXTOUTA
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int iGraphicsMode;
  float exScale;
  float eyScale;
  int cStrings;
  tagEMRTEXT aemrtext[1];
};

```

### `tagCALPSTR`
```
struct tagCALPSTR
{
  unsigned int cElems;
  char **pElems;
};

```

### `tagHIGHCONTRASTW`
```
struct tagHIGHCONTRASTW
{
  unsigned int cbSize;
  unsigned int dwFlags;
  wchar_t *lpszDefaultScheme;
};

```

### `tagEMRPLGBLT`
```
struct tagEMRPLGBLT
{
  tagEMR emr;
  _RECTL rclBounds;
  _POINTL aptlDest[3];
  int xSrc;
  int ySrc;
  int cxSrc;
  int cySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  int xMask;
  int yMask;
  unsigned int iUsageMask;
  unsigned int offBmiMask;
  unsigned int cbBmiMask;
  unsigned int offBitsMask;
  unsigned int cbBitsMask;
};

```

### `tagNONCLIENTMETRICSW`
```
struct tagNONCLIENTMETRICSW
{
  unsigned int cbSize;
  int iBorderWidth;
  int iScrollWidth;
  int iScrollHeight;
  int iCaptionWidth;
  int iCaptionHeight;
  tagLOGFONTW lfCaptionFont;
  int iSmCaptionWidth;
  int iSmCaptionHeight;
  tagLOGFONTW lfSmCaptionFont;
  int iMenuWidth;
  int iMenuHeight;
  tagLOGFONTW lfMenuFont;
  tagLOGFONTW lfStatusFont;
  tagLOGFONTW lfMessageFont;
  int iPaddedBorderWidth;
};

```

### `tagEMRPOLYPOLYLINE16`
```
struct tagEMRPOLYPOLYLINE16
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int nPolys;
  unsigned int cpts;
  unsigned int aPolyCounts[1];
  tagPOINTS apts[1];
};

```

### `tagEMROFFSETCLIPRGN`
```
struct tagEMROFFSETCLIPRGN
{
  tagEMR emr;
  _POINTL ptlOffset;
};

```

### `tagEMREOF`
```
struct tagEMREOF
{
  tagEMR emr;
  unsigned int nPalEntries;
  unsigned int offPalEntries;
  unsigned int nSizeLast;
};

```

### `tagRGBTRIPLE`
```
struct tagRGBTRIPLE
{
  unsigned __int8 rgbtBlue;
  unsigned __int8 rgbtGreen;
  unsigned __int8 rgbtRed;
};

```

### `tagBITMAPCOREINFO`
```
struct __declspec(align(2)) tagBITMAPCOREINFO
{
  tagBITMAPCOREHEADER bmciHeader;
  tagRGBTRIPLE bmciColors[1];
};

```

### `tagCLIPDATA`
```
struct tagCLIPDATA
{
  unsigned int cbSize;
  int ulClipFmt;
  unsigned __int8 *pClipData;
};

```

### `tagCACLIPDATA`
```
struct tagCACLIPDATA
{
  unsigned int cElems;
  tagCLIPDATA *pElems;
};

```

### `tagOFN_NT4A`
```
struct tagOFN_NT4A
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  const char *lpstrFilter;
  char *lpstrCustomFilter;
  unsigned int nMaxCustFilter;
  unsigned int nFilterIndex;
  char *lpstrFile;
  unsigned int nMaxFile;
  char *lpstrFileTitle;
  unsigned int nMaxFileTitle;
  const char *lpstrInitialDir;
  const char *lpstrTitle;
  unsigned int Flags;
  unsigned __int16 nFileOffset;
  unsigned __int16 nFileExtension;
  const char *lpstrDefExt;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpTemplateName;
};

```

### `tagCOMBOBOXINFO`
```
struct tagCOMBOBOXINFO
{
  unsigned int cbSize;
  tagRECT rcItem;
  tagRECT rcButton;
  unsigned int stateButton;
  HWND__ *hwndCombo;
  HWND__ *hwndItem;
  HWND__ *hwndList;
};

```

### `tagWINDOWPLACEMENT`
```
struct tagWINDOWPLACEMENT
{
  unsigned int length;
  unsigned int flags;
  unsigned int showCmd;
  tagPOINT ptMinPosition;
  tagPOINT ptMaxPosition;
  tagRECT rcNormalPosition;
};

```

### `tagPDEXW`
```
struct tagPDEXW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  HDC__ *hDC;
  unsigned int Flags;
  unsigned int Flags2;
  unsigned int ExclusionFlags;
  unsigned int nPageRanges;
  unsigned int nMaxPageRanges;
  tagPRINTPAGERANGE *lpPageRanges;
  unsigned int nMinPage;
  unsigned int nMaxPage;
  unsigned int nCopies;
  HINSTANCE__ *hInstance;
  const wchar_t *lpPrintTemplateName;
  IUnknown *lpCallback;
  unsigned int nPropertyPages;
  struct _PSP **lphPropertyPages;
  unsigned int nStartPage;
  unsigned int dwResultAction;
};

```

### `type_safe::strong_typedef<mce::Radian,float>`
```
struct __cppobj type_safe::strong_typedef<mce::Radian,float>
{
  float value_;
};

```

### `type_safe::strong_typedef_op::equality_comparison<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::equality_comparison<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::relational_comparison<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::relational_comparison<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::unary_plus<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::unary_minus<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::unary_minus<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::addition<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::addition<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::subtraction<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::subtraction<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::multiplication<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::multiplication<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::division<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::division<mce::Radian>
{
};

```

### `type_safe::strong_typedef_op::floating_point_arithmetic<mce::Radian>`
```
struct __cppobj type_safe::strong_typedef_op::floating_point_arithmetic<mce::Radian> : type_safe::strong_typedef_op::unary_plus<mce::Radian>, type_safe::strong_typedef_op::unary_minus<mce::Radian>, type_safe::strong_typedef_op::addition<mce::Radian>, type_safe::strong_typedef_op::subtraction<mce::Radian>, type_safe::strong_typedef_op::multiplication<mce::Radian>, type_safe::strong_typedef_op::division<mce::Radian>
{
  _BYTE gap0;
  _BYTE gap1;
  _BYTE gap2;
  _BYTE gap3;
  _BYTE gap4;
};

```

### `type_safe::strong_typedef_op::input_operator<mce::Radian_`
```
struct __cppobj type_safe::strong_typedef_op::input_operator<mce::Radian_
{
};

```

### `type_safe::strong_typedef_op::output_operator<mce::Radian_`
```
struct __cppobj type_safe::strong_typedef_op::output_operator<mce::Radian_
{
};

```

### `type_safe::strong_typedef<mce::Degree,float>`
```
struct __cppobj type_safe::strong_typedef<mce::Degree,float>
{
  float value_;
};

```

### `type_safe::strong_typedef_op::equality_comparison<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::equality_comparison<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::relational_comparison<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::relational_comparison<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::unary_plus<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::unary_minus<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::unary_minus<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::addition<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::addition<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::subtraction<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::subtraction<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::multiplication<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::multiplication<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::division<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::division<mce::Degree>
{
};

```

### `type_safe::strong_typedef_op::floating_point_arithmetic<mce::Degree>`
```
struct __cppobj type_safe::strong_typedef_op::floating_point_arithmetic<mce::Degree> : type_safe::strong_typedef_op::unary_plus<mce::Degree>, type_safe::strong_typedef_op::unary_minus<mce::Degree>, type_safe::strong_typedef_op::addition<mce::Degree>, type_safe::strong_typedef_op::subtraction<mce::Degree>, type_safe::strong_typedef_op::multiplication<mce::Degree>, type_safe::strong_typedef_op::division<mce::Degree>
{
  _BYTE gap0;
  _BYTE gap1;
  _BYTE gap2;
  _BYTE gap3;
  _BYTE gap4;
};

```

### `type_safe::strong_typedef_op::input_operator<mce::Degree_`
```
struct __cppobj type_safe::strong_typedef_op::input_operator<mce::Degree_
{
};

```

### `type_safe::strong_typedef_op::output_operator<mce::Degree_`
```
struct __cppobj type_safe::strong_typedef_op::output_operator<mce::Degree_
{
};

```

### `tagTTPOLYGONHEADER`
```
struct tagTTPOLYGONHEADER
{
  unsigned int cb;
  unsigned int dwType;
  tagPOINTFX pfxStart;
};

```

### `tagCHOOSEFONTA`
```
struct __declspec(align(8)) tagCHOOSEFONTA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HDC__ *hDC;
  tagLOGFONTA *lpLogFont;
  int iPointSize;
  unsigned int Flags;
  unsigned int rgbColors;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpTemplateName;
  HINSTANCE__ *hInstance;
  char *lpszStyle;
  unsigned __int16 nFontType;
  unsigned __int16 ___MISSING_ALIGNMENT__;
  int nSizeMin;
  int nSizeMax;
};

```

### `tagSCROLLINFO`
```
struct tagSCROLLINFO
{
  unsigned int cbSize;
  unsigned int fMask;
  int nMin;
  int nMax;
  unsigned int nPage;
  int nPos;
  int nTrackPos;
};

```

### `tagEMREXTFLOODFILL`
```
struct tagEMREXTFLOODFILL
{
  tagEMR emr;
  _POINTL ptlStart;
  unsigned int crColor;
  unsigned int iMode;
};

```

### `tagOFNW`
```
struct tagOFNW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  const wchar_t *lpstrFilter;
  wchar_t *lpstrCustomFilter;
  unsigned int nMaxCustFilter;
  unsigned int nFilterIndex;
  wchar_t *lpstrFile;
  unsigned int nMaxFile;
  wchar_t *lpstrFileTitle;
  unsigned int nMaxFileTitle;
  const wchar_t *lpstrInitialDir;
  const wchar_t *lpstrTitle;
  unsigned int Flags;
  unsigned __int16 nFileOffset;
  unsigned __int16 nFileExtension;
  const wchar_t *lpstrDefExt;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpTemplateName;
  void *pvReserved;
  unsigned int dwReserved;
  unsigned int FlagsEx;
};

```

### `tagRGBQUAD`
```
struct tagRGBQUAD
{
  unsigned __int8 rgbBlue;
  unsigned __int8 rgbGreen;
  unsigned __int8 rgbRed;
  unsigned __int8 rgbReserved;
};

```

### `tagPSDA`
```
struct tagPSDA
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  void *hDevMode;
  void *hDevNames;
  unsigned int Flags;
  tagPOINT ptPaperSize;
  tagRECT rtMinMargin;
  tagRECT rtMargin;
  HINSTANCE__ *hInstance;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnPageSetupHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  unsigned __int64 (__fastcall *lpfnPagePaintHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const char *lpPageSetupTemplateName;
  void *hPageSetupTemplate;
};

```

### `tagCHOOSECOLORW`
```
struct tagCHOOSECOLORW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HWND__ *hInstance;
  unsigned int rgbResult;
  unsigned int *lpCustColors;
  unsigned int Flags;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpTemplateName;
};

```

### `tagEMRSETVIEWPORTORGEX`
```
struct tagEMRSETVIEWPORTORGEX
{
  tagEMR emr;
  _POINTL ptlOrigin;
};

```

### `tagEMRFRAMERGN`
```
struct __declspec(align(4)) tagEMRFRAMERGN
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cbRgnData;
  unsigned int ihBrush;
  tagSIZE szlStroke;
  unsigned __int8 RgnData[1];
};

```

### `tagREGISTERWORDA`
```
struct tagREGISTERWORDA
{
  char *lpReading;
  char *lpWord;
};

```

### `tagRPC_ERROR_ENUM_HANDLE`
```
struct tagRPC_ERROR_ENUM_HANDLE
{
  unsigned int Signature;
  void *CurrentPos;
  void *Head;
};

```

### `tagEMRRESTOREDC`
```
struct tagEMRRESTOREDC
{
  tagEMR emr;
  int iRelative;
};

```

### `tagBITMAPINFO`
```
struct tagBITMAPINFO
{
  tagBITMAPINFOHEADER bmiHeader;
  tagRGBQUAD bmiColors[1];
};

```

### `tagRemSNB`
```
struct __declspec(align(4)) tagRemSNB
{
  unsigned int ulCntStr;
  unsigned int ulCntChar;
  wchar_t rgString[1];
};

```

### `tagMDICREATESTRUCTA`
```
struct tagMDICREATESTRUCTA
{
  const char *szClass;
  const char *szTitle;
  void *hOwner;
  int x;
  int y;
  int cx;
  int cy;
  unsigned int style;
  __int64 lParam;
};

```

### `tagEMRMASKBLT`
```
struct tagEMRMASKBLT
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int cxDest;
  int cyDest;
  unsigned int dwRop;
  int xSrc;
  int ySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  int xMask;
  int yMask;
  unsigned int iUsageMask;
  unsigned int offBmiMask;
  unsigned int cbBmiMask;
  unsigned int offBitsMask;
  unsigned int cbBitsMask;
};

```

### `tagOleMenuGroupWidths`
```
struct tagOleMenuGroupWidths
{
  int width[6];
};

```

### `tagRID_DEVICE_INFO_MOUSE`
```
struct tagRID_DEVICE_INFO_MOUSE
{
  unsigned int dwId;
  unsigned int dwNumberOfButtons;
  unsigned int dwSampleRate;
  int fHasHorizontalWheel;
};

```

### `tagRID_DEVICE_INFO_KEYBOARD`
```
struct tagRID_DEVICE_INFO_KEYBOARD
{
  unsigned int dwType;
  unsigned int dwSubType;
  unsigned int dwKeyboardMode;
  unsigned int dwNumberOfFunctionKeys;
  unsigned int dwNumberOfIndicators;
  unsigned int dwNumberOfKeysTotal;
};

```

### `tagRID_DEVICE_INFO`
```
struct tagRID_DEVICE_INFO
{
  unsigned int cbSize;
  unsigned int dwType;
  $1A8176FE7C0930105C769309D1675A1F ___u2;
};

```

### `tagCOLORCORRECTPALETTE`
```
struct tagCOLORCORRECTPALETTE
{
  tagEMR emr;
  unsigned int ihPalette;
  unsigned int nFirstEntry;
  unsigned int nPalEntries;
  unsigned int nReserved;
};

```

### `tagRPC_CALL_ATTRIBUTES_V2_A`
```
struct __declspec(align(8)) tagRPC_CALL_ATTRIBUTES_V2_A
{
  unsigned int Version;
  unsigned int Flags;
  unsigned int ServerPrincipalNameBufferLength;
  unsigned __int8 *ServerPrincipalName;
  unsigned int ClientPrincipalNameBufferLength;
  unsigned __int8 *ClientPrincipalName;
  unsigned int AuthenticationLevel;
  unsigned int AuthenticationService;
  int NullSession;
  int KernelModeCaller;
  unsigned int ProtocolSequence;
  unsigned int IsClientLocal;
  void *ClientPID;
  unsigned int CallStatus;
  tagRpcCallType CallType;
  _RPC_CALL_LOCAL_ADDRESS_V1 *CallLocalAddress;
  unsigned __int16 OpNum;
  _GUID InterfaceUuid;
};

```

### `tagSCROLLBARINFO`
```
struct tagSCROLLBARINFO
{
  unsigned int cbSize;
  tagRECT rcScrollBar;
  int dxyLineButton;
  int xyThumbTop;
  int xyThumbBottom;
  int reserved;
  unsigned int rgstate[6];
};

```

### `tagCAFILETIME`
```
struct tagCAFILETIME
{
  unsigned int cElems;
  _FILETIME *pElems;
};

```

### `tagCHANGEFILTERSTRUCT`
```
struct tagCHANGEFILTERSTRUCT
{
  unsigned int cbSize;
  unsigned int ExtStatus;
};

```

### `tagCALPWSTR`
```
struct tagCALPWSTR
{
  unsigned int cElems;
  wchar_t **pElems;
};

```

### `tagCAL`
```
struct tagCAL
{
  unsigned int cElems;
  int *pElems;
};

```

### `tagCABSTRBLOB`
```
struct tagCABSTRBLOB
{
  unsigned int cElems;
  tagBSTRBLOB *pElems;
};

```

### `tagMENUITEMINFOW`
```
struct tagMENUITEMINFOW
{
  unsigned int cbSize;
  unsigned int fMask;
  unsigned int fType;
  unsigned int fState;
  unsigned int wID;
  HMENU__ *hSubMenu;
  HBITMAP__ *hbmpChecked;
  HBITMAP__ *hbmpUnchecked;
  unsigned __int64 dwItemData;
  wchar_t *dwTypeData;
  unsigned int cch;
  HBITMAP__ *hbmpItem;
};

```

### `tagEMRANGLEARC`
```
struct tagEMRANGLEARC
{
  tagEMR emr;
  _POINTL ptlCenter;
  unsigned int nRadius;
  float eStartAngle;
  float eSweepAngle;
};

```

### `tagCHOOSEFONTW`
```
struct __declspec(align(8)) tagCHOOSEFONTW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HDC__ *hDC;
  tagLOGFONTW *lpLogFont;
  int iPointSize;
  unsigned int Flags;
  unsigned int rgbColors;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpTemplateName;
  HINSTANCE__ *hInstance;
  wchar_t *lpszStyle;
  unsigned __int16 nFontType;
  unsigned __int16 ___MISSING_ALIGNMENT__;
  int nSizeMin;
  int nSizeMax;
};

```

### `tagWINDOWINFO`
```
struct tagWINDOWINFO
{
  unsigned int cbSize;
  tagRECT rcWindow;
  tagRECT rcClient;
  unsigned int dwStyle;
  unsigned int dwExStyle;
  unsigned int dwWindowStatus;
  unsigned int cxWindowBorders;
  unsigned int cyWindowBorders;
  unsigned __int16 atomWindowType;
  unsigned __int16 wCreatorVersion;
};

```

### `tagCAFLT`
```
struct tagCAFLT
{
  unsigned int cElems;
  float *pElems;
};

```

### `tagEMRLINETO`
```
struct tagEMRLINETO
{
  tagEMR emr;
  _POINTL ptl;
};

```

### `tagCANDIDATELIST`
```
struct tagCANDIDATELIST
{
  unsigned int dwSize;
  unsigned int dwStyle;
  unsigned int dwCount;
  unsigned int dwSelection;
  unsigned int dwPageStart;
  unsigned int dwPageSize;
  unsigned int dwOffset[1];
};

```

### `tagSERIALIZEDPROPERTYVALUE`
```
struct __declspec(align(4)) tagSERIALIZEDPROPERTYVALUE
{
  unsigned int dwType;
  unsigned __int8 rgb[1];
};

```

### `tagCAH`
```
struct tagCAH
{
  unsigned int cElems;
  _LARGE_INTEGER *pElems;
};

```

### `tagCAUI`
```
struct tagCAUI
{
  unsigned int cElems;
  unsigned __int16 *pElems;
};

```

### `tagLOGCOLORSPACEA`
```
struct tagLOGCOLORSPACEA
{
  unsigned int lcsSignature;
  unsigned int lcsVersion;
  unsigned int lcsSize;
  int lcsCSType;
  int lcsIntent;
  tagICEXYZTRIPLE lcsEndpoints;
  unsigned int lcsGammaRed;
  unsigned int lcsGammaGreen;
  unsigned int lcsGammaBlue;
  char lcsFilename[260];
};

```

### `tagINTERFACEINFO`
```
struct __declspec(align(8)) tagINTERFACEINFO
{
  IUnknown *pUnk;
  _GUID iid;
  unsigned __int16 wMethod;
};

```

### `tagGCP_RESULTSA`
```
struct tagGCP_RESULTSA
{
  unsigned int lStructSize;
  char *lpOutString;
  unsigned int *lpOrder;
  int *lpDx;
  int *lpCaretPos;
  char *lpClass;
  wchar_t *lpGlyphs;
  unsigned int nGlyphs;
  int nMaxFit;
};

```

### `tagRemHBITMAP`
```
struct __declspec(align(4)) tagRemHBITMAP
{
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagEMRARC`
```
struct tagEMRARC
{
  tagEMR emr;
  _RECTL rclBox;
  _POINTL ptlStart;
  _POINTL ptlEnd;
};

```

### `tagEMRCREATEPALETTE`
```
struct tagEMRCREATEPALETTE
{
  tagEMR emr;
  unsigned int ihPal;
  tagLOGPALETTE lgpl;
};

```

### `tagEMRSETCOLORADJUSTMENT`
```
struct tagEMRSETCOLORADJUSTMENT
{
  tagEMR emr;
  tagCOLORADJUSTMENT ColorAdjustment;
};

```

### `tagUSEROBJECTFLAGS`
```
struct tagUSEROBJECTFLAGS
{
  int fInherit;
  int fReserved;
  unsigned int dwFlags;
};

```

### `tagEMRSETCOLORSPACE`
```
struct tagEMRSETCOLORSPACE
{
  tagEMR emr;
  unsigned int ihCS;
};

```

### `tagHELPWININFOA`
```
struct __declspec(align(4)) tagHELPWININFOA
{
  int wStructSize;
  int x;
  int y;
  int dx;
  int dy;
  int wMax;
  char rgchMember[2];
};

```

### `tagMOUSEINPUT`
```
struct tagMOUSEINPUT
{
  int dx;
  int dy;
  unsigned int mouseData;
  unsigned int dwFlags;
  unsigned int time;
  unsigned __int64 dwExtraInfo;
};

```

### `tagKEYBDINPUT`
```
struct tagKEYBDINPUT
{
  unsigned __int16 wVk;
  unsigned __int16 wScan;
  unsigned int dwFlags;
  unsigned int time;
  unsigned __int64 dwExtraInfo;
};

```

### `tagINPUT`
```
struct tagINPUT
{
  unsigned int type;
  $E55F5E364084B5948AD3D1F5CC4EB887 ___u1;
};

```

### `tagCAUH`
```
struct tagCAUH
{
  unsigned int cElems;
  _ULARGE_INTEGER *pElems;
};

```

### `tagCADATE`
```
struct tagCADATE
{
  unsigned int cElems;
  long double *pElems;
};

```

### `tagRPC_CALL_ATTRIBUTES_V1_A`
```
struct __declspec(align(8)) tagRPC_CALL_ATTRIBUTES_V1_A
{
  unsigned int Version;
  unsigned int Flags;
  unsigned int ServerPrincipalNameBufferLength;
  unsigned __int8 *ServerPrincipalName;
  unsigned int ClientPrincipalNameBufferLength;
  unsigned __int8 *ClientPrincipalName;
  unsigned int AuthenticationLevel;
  unsigned int AuthenticationService;
  int NullSession;
};

```

### `tagVersionedStream`
```
struct tagVersionedStream
{
  _GUID guidVersion;
  IStream *pStream;
};

```

### `tagCAC`
```
struct tagCAC
{
  unsigned int cElems;
  char *pElems;
};

```

### `tagCAUB`
```
struct tagCAUB
{
  unsigned int cElems;
  unsigned __int8 *pElems;
};

```

### `tagCAI`
```
struct tagCAI
{
  unsigned int cElems;
  __int16 *pElems;
};

```

### `tagCABOOL`
```
struct tagCABOOL
{
  unsigned int cElems;
  __int16 *pElems;
};

```

### `tagCASCODE`
```
struct tagCASCODE
{
  unsigned int cElems;
  int *pElems;
};

```

### `tagCACY`
```
struct tagCACY
{
  unsigned int cElems;
  tagCY *pElems;
};

```

### `tagCACLSID`
```
struct tagCACLSID
{
  unsigned int cElems;
  _GUID *pElems;
};

```

### `tagPROPVARIANT`
```
struct tagPROPVARIANT
{
  $F1B8DA29A14370238910C8DF4C5980E2 ___u0;
};

```

### `tagCAPROPVARIANT`
```
struct tagCAPROPVARIANT
{
  unsigned int cElems;
  tagPROPVARIANT *pElems;
};

```

### `tagSTYLESTRUCT`
```
struct tagSTYLESTRUCT
{
  unsigned int styleOld;
  unsigned int styleNew;
};

```

### `tagSERIALKEYSA`
```
struct __declspec(align(8)) tagSERIALKEYSA
{
  unsigned int cbSize;
  unsigned int dwFlags;
  char *lpszActivePort;
  char *lpszPort;
  unsigned int iBaudRate;
  unsigned int iPortState;
  unsigned int iActive;
};

```

### `tagEMRROUNDRECT`
```
struct tagEMRROUNDRECT
{
  tagEMR emr;
  _RECTL rclBox;
  tagSIZE szlCorner;
};

```

### `tagEMRGLSRECORD`
```
struct __declspec(align(4)) tagEMRGLSRECORD
{
  tagEMR emr;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagCHARSETINFO`
```
struct tagCHARSETINFO
{
  unsigned int ciCharset;
  unsigned int ciACP;
  tagFONTSIGNATURE fs;
};

```

### `tagLOGCOLORSPACEW`
```
struct tagLOGCOLORSPACEW
{
  unsigned int lcsSignature;
  unsigned int lcsVersion;
  unsigned int lcsSize;
  int lcsCSType;
  int lcsIntent;
  tagICEXYZTRIPLE lcsEndpoints;
  unsigned int lcsGammaRed;
  unsigned int lcsGammaGreen;
  unsigned int lcsGammaBlue;
  wchar_t lcsFilename[260];
};

```

### `tagEMRCREATECOLORSPACEW`
```
struct __declspec(align(4)) tagEMRCREATECOLORSPACEW
{
  tagEMR emr;
  unsigned int ihCS;
  tagLOGCOLORSPACEW lcs;
  unsigned int dwFlags;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagACCESSTIMEOUT`
```
struct tagACCESSTIMEOUT
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int iTimeOutMSec;
};

```

### `tagGCP_RESULTSW`
```
struct tagGCP_RESULTSW
{
  unsigned int lStructSize;
  wchar_t *lpOutString;
  unsigned int *lpOrder;
  int *lpDx;
  int *lpCaretPos;
  char *lpClass;
  wchar_t *lpGlyphs;
  unsigned int nGlyphs;
  int nMaxFit;
};

```

### `tagEMRSETTEXTCOLOR`
```
struct tagEMRSETTEXTCOLOR
{
  tagEMR emr;
  unsigned int crColor;
};

```

### `tagEMRSETDIBITSTODEVICE`
```
struct tagEMRSETDIBITSTODEVICE
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int xSrc;
  int ySrc;
  int cxSrc;
  int cySrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  unsigned int iUsageSrc;
  unsigned int iStartScan;
  unsigned int cScans;
};

```

### `tagEMRNAMEDESCAPE`
```
struct __declspec(align(4)) tagEMRNAMEDESCAPE
{
  tagEMR emr;
  int iEscape;
  int cbDriver;
  int cbEscData;
  unsigned __int8 EscData[1];
};

```

### `tagOIFI`
```
struct __declspec(align(8)) tagOIFI
{
  unsigned int cb;
  int fMDIApp;
  HWND__ *hwndFrame;
  HACCEL__ *haccel;
  unsigned int cAccelEntries;
};

```

### `tagENHMETARECORD`
```
struct tagENHMETARECORD
{
  unsigned int iType;
  unsigned int nSize;
  unsigned int dParm[1];
};

```

### `tagGESTURECONFIG`
```
struct tagGESTURECONFIG
{
  unsigned int dwID;
  unsigned int dwWant;
  unsigned int dwBlock;
};

```

### `type_safe::nullvar_t`
```
struct __cppobj type_safe::nullvar_t
{
};

```

### `type_safe::reference_optional_storage<type_safe::nullvar_t const ,0>`
```
struct __cppobj type_safe::reference_optional_storage<type_safe::nullvar_t const ,0>
{
  const type_safe::nullvar_t *pointer_;
};

```

### `type_safe::detail::signed_integer_tag`
```
struct __cppobj type_safe::detail::signed_integer_tag
{
};

```

### `type_safe::detail::optional_storage<type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> >`
```
struct __cppobj type_safe::detail::optional_storage<type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> >
{
  type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> storage;
};

```

### `type_safe::detail::copy_control<1>`
```
struct __cppobj type_safe::detail::copy_control<1>
{
};

```

### `type_safe::detail::move_control<1>`
```
struct __cppobj type_safe::detail::move_control<1>
{
};

```

### `type_safe::basic_optional<type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> >`
```
struct __cppobj __declspec(align(8)) type_safe::basic_optional<type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> > : type_safe::detail::optional_storage<type_safe::reference_optional_storage<type_safe::nullvar_t const ,0> >, type_safe::detail::copy_control<1>, type_safe::detail::move_control<1>
{
  _BYTE gap8;
};

```

### `type_safe::direct_optional_storage<int>`
```
struct __cppobj __declspec(align(4)) type_safe::direct_optional_storage<int>
{
  std::_Align_type<int,4> storage_;
  bool empty_;
};

```

### `type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic>`
```
struct __cppobj type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic>
{
  unsigned __int64 value_;
};

```

### `type_safe::strong_typedef<type_safe::index_t,type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::strong_typedef<type_safe::index_t,type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >
{
  type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> value_;
};

```

### `type_safe::strong_typedef_op::equality_comparison<type_safe::index_t>`
```
struct __cppobj type_safe::strong_typedef_op::equality_comparison<type_safe::index_t>
{
};

```

### `type_safe::strong_typedef_op::relational_comparison<type_safe::index_t>`
```
struct __cppobj type_safe::strong_typedef_op::relational_comparison<type_safe::index_t>
{
};

```

### `type_safe::strong_typedef_op::increment<type_safe::index_t>`
```
struct __cppobj type_safe::strong_typedef_op::increment<type_safe::index_t>
{
};

```

### `type_safe::strong_typedef_op::decrement<type_safe::index_t>`
```
struct __cppobj type_safe::strong_typedef_op::decrement<type_safe::index_t>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<type_safe::index_t>`
```
struct __cppobj type_safe::strong_typedef_op::unary_plus<type_safe::index_t>
{
};

```

### `type_safe::index_t`
```
struct __cppobj __declspec(align(8)) type_safe::index_t : type_safe::strong_typedef<type_safe::index_t,type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >, type_safe::strong_typedef_op::equality_comparison<type_safe::index_t>, type_safe::strong_typedef_op::relational_comparison<type_safe::index_t>, type_safe::strong_typedef_op::increment<type_safe::index_t>, type_safe::strong_typedef_op::decrement<type_safe::index_t>, type_safe::strong_typedef_op::unary_plus<type_safe::index_t>
{
  _BYTE gap8;
  _BYTE gapA;
};

```

### `type_safe::boolean`
```
struct __cppobj type_safe::boolean
{
  bool value_;
};

```

### `type_safe::detail::optional_storage<type_safe::direct_optional_storage<int> >`
```
struct __cppobj type_safe::detail::optional_storage<type_safe::direct_optional_storage<int> >
{
  type_safe::direct_optional_storage<int> storage;
};

```

### `type_safe::basic_optional<type_safe::direct_optional_storage<int> >`
```
struct __cppobj __declspec(align(4)) type_safe::basic_optional<type_safe::direct_optional_storage<int> > : type_safe::detail::optional_storage<type_safe::direct_optional_storage<int> >, type_safe::detail::copy_control<1>, type_safe::detail::move_control<1>
{
  _BYTE gap8;
};

```

### `type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>`
```
struct __cppobj type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>
{
  __int64 value_;
};

```

### `type_safe::object_ref<type_safe::nullvar_t const ,0>`
```
struct type_safe::object_ref<type_safe::nullvar_t const ,0>
{
  const type_safe::nullvar_t *ptr_;
};

```

### `tagSOLE_AUTHENTICATION_INFO`
```
struct tagSOLE_AUTHENTICATION_INFO
{
  unsigned int dwAuthnSvc;
  unsigned int dwAuthzSvc;
  void *pAuthInfo;
};

```

### `tagSOLE_AUTHENTICATION_LIST`
```
struct tagSOLE_AUTHENTICATION_LIST
{
  unsigned int cAuthInfo;
  tagSOLE_AUTHENTICATION_INFO *aAuthInfo;
};

```

### `tagHANDLETABLE`
```
struct tagHANDLETABLE
{
  void *objectHandle[1];
};

```

### `tagRemHENHMETAFILE`
```
struct __declspec(align(4)) tagRemHENHMETAFILE
{
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagMONITORINFOEXA`
```
struct __cppobj tagMONITORINFOEXA : tagMONITORINFO
{
  char szDevice[32];
};

```

### `tagSOUNDSENTRYW`
```
struct __declspec(align(8)) tagSOUNDSENTRYW
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int iFSTextEffect;
  unsigned int iFSTextEffectMSec;
  unsigned int iFSTextEffectColorBits;
  unsigned int iFSGrafEffect;
  unsigned int iFSGrafEffectMSec;
  unsigned int iFSGrafEffectColor;
  unsigned int iWindowsEffect;
  unsigned int iWindowsEffectMSec;
  wchar_t *lpszWindowsEffectDLL;
  unsigned int iWindowsEffectOrdinal;
};

```

### `tagStorageLayout`
```
struct tagStorageLayout
{
  unsigned int LayoutType;
  wchar_t *pwcsElementName;
  _LARGE_INTEGER cOffset;
  _LARGE_INTEGER cBytes;
};

```

### `tagHIGHCONTRASTA`
```
struct tagHIGHCONTRASTA
{
  unsigned int cbSize;
  unsigned int dwFlags;
  char *lpszDefaultScheme;
};

```

### `tagEMRPOLYDRAW`
```
struct __declspec(align(4)) tagEMRPOLYDRAW
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cptl;
  _POINTL aptl[1];
  unsigned __int8 abTypes[1];
};

```

### `tagCWPSTRUCT`
```
struct tagCWPSTRUCT
{
  __int64 lParam;
  unsigned __int64 wParam;
  unsigned int message;
  HWND__ *hwnd;
};

```

### `tagCURSORINFO`
```
struct tagCURSORINFO
{
  unsigned int cbSize;
  unsigned int flags;
  HICON__ *hCursor;
  tagPOINT ptScreenPos;
};

```

### `tagMDICREATESTRUCTW`
```
struct tagMDICREATESTRUCTW
{
  const wchar_t *szClass;
  const wchar_t *szTitle;
  void *hOwner;
  int x;
  int y;
  int cx;
  int cy;
  unsigned int style;
  __int64 lParam;
};

```

### `tagGLYPHSET`
```
struct tagGLYPHSET
{
  unsigned int cbThis;
  unsigned int flAccel;
  unsigned int cGlyphsSupported;
  unsigned int cRanges;
  tagWCRANGE ranges[1];
};

```

### `tagWTSSESSION_NOTIFICATION`
```
struct tagWTSSESSION_NOTIFICATION
{
  unsigned int cbSize;
  unsigned int dwSessionId;
};

```

### `tagMSGBOXPARAMSA`
```
struct __declspec(align(8)) tagMSGBOXPARAMSA
{
  unsigned int cbSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  const char *lpszText;
  const char *lpszCaption;
  unsigned int dwStyle;
  const char *lpszIcon;
  unsigned __int64 dwContextHelpId;
  void (__fastcall *lpfnMsgBoxCallback)(tagHELPINFO *);
  unsigned int dwLanguageId;
};

```

### `tagPROPSPEC`
```
struct tagPROPSPEC
{
  unsigned int ulKind;
  $BCD5257052F2DAAF91A32A374615C63E ___u1;
};

```

### `tagEMRFORMAT`
```
struct tagEMRFORMAT
{
  unsigned int dSignature;
  unsigned int nVersion;
  unsigned int cbData;
  unsigned int offData;
};

```

### `tagBIND_OPTS2`
```
struct __cppobj tagBIND_OPTS2 : tagBIND_OPTS
{
  unsigned int dwTrackFlags;
  unsigned int dwClassContext;
  unsigned int locale;
  _COSERVERINFO *pServerInfo;
};

```

### `tagEMRCREATEBRUSHINDIRECT`
```
struct tagEMRCREATEBRUSHINDIRECT
{
  tagEMR emr;
  unsigned int ihBrush;
  tagLOGBRUSH32 lb;
};

```

### `tagCWPRETSTRUCT`
```
struct tagCWPRETSTRUCT
{
  __int64 lResult;
  __int64 lParam;
  unsigned __int64 wParam;
  unsigned int message;
  HWND__ *hwnd;
};

```

### `tagEMRCREATEPEN`
```
struct tagEMRCREATEPEN
{
  tagEMR emr;
  unsigned int ihPen;
  tagLOGPEN lopn;
};

```

### `tagNC_ADDRESS`
```
struct __declspec(align(8)) tagNC_ADDRESS
{
  NET_ADDRESS_INFO_ *pAddrInfo;
  unsigned __int16 PortNumber;
  unsigned __int8 PrefixLength;
};

```

### `timespec`
```
struct __declspec(align(8)) timespec
{
  __int64 tv_sec;
  int tv_nsec;
};

```

### `tagMOUSEHOOKSTRUCTEX`
```
struct __cppobj __declspec(align(8)) tagMOUSEHOOKSTRUCTEX : tagMOUSEHOOKSTRUCT
{
  unsigned int mouseData;
};

```

### `tagKERNINGPAIR`
```
struct tagKERNINGPAIR
{
  unsigned __int16 wFirst;
  unsigned __int16 wSecond;
  int iKernAmount;
};

```

### `tagEMRSTRETCHBLT`
```
struct tagEMRSTRETCHBLT
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int cxDest;
  int cyDest;
  unsigned int dwRop;
  int xSrc;
  int ySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  int cxSrc;
  int cySrc;
};

```

### `tagDELETEITEMSTRUCT`
```
struct tagDELETEITEMSTRUCT
{
  unsigned int CtlType;
  unsigned int CtlID;
  unsigned int itemID;
  HWND__ *hwndItem;
  unsigned __int64 itemData;
};

```

### `tagSTICKYKEYS`
```
struct tagSTICKYKEYS
{
  unsigned int cbSize;
  unsigned int dwFlags;
};

```

### `tagGUITHREADINFO`
```
struct tagGUITHREADINFO
{
  unsigned int cbSize;
  unsigned int flags;
  HWND__ *hwndActive;
  HWND__ *hwndFocus;
  HWND__ *hwndCapture;
  HWND__ *hwndMenuOwner;
  HWND__ *hwndMoveSize;
  HWND__ *hwndCaret;
  tagRECT rcCaret;
};

```

### `tagSTATPROPSETSTG`
```
struct tagSTATPROPSETSTG
{
  _GUID fmtid;
  _GUID clsid;
  unsigned int grfFlags;
  _FILETIME mtime;
  _FILETIME ctime;
  _FILETIME atime;
  unsigned int dwOSVersion;
};

```

### `tagREGISTERWORDW`
```
struct tagREGISTERWORDW
{
  wchar_t *lpReading;
  wchar_t *lpWord;
};

```

### `tagEMRCREATECOLORSPACE`
```
struct tagEMRCREATECOLORSPACE
{
  tagEMR emr;
  unsigned int ihCS;
  tagLOGCOLORSPACEA lcs;
};

```

### `tagMENUINFO`
```
struct tagMENUINFO
{
  unsigned int cbSize;
  unsigned int fMask;
  unsigned int dwStyle;
  unsigned int cyMax;
  HBRUSH__ *hbrBack;
  unsigned int dwContextHelpID;
  unsigned __int64 dwMenuData;
};

```

### `tagRAWINPUT`
```
struct tagRAWINPUT
{
  tagRAWINPUTHEADER header;
  tagRAWINPUT::<unnamed_type_data> data;
};

```

### `tagLASTINPUTINFO`
```
struct tagLASTINPUTINFO
{
  unsigned int cbSize;
  unsigned int dwTime;
};

```

### `tagEMRGRADIENTFILL`
```
struct tagEMRGRADIENTFILL
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int nVer;
  unsigned int nTri;
  unsigned int ulMode;
  _TRIVERTEX Ver[1];
};

```

### `tagRAWINPUTDEVICELIST`
```
struct __declspec(align(8)) tagRAWINPUTDEVICELIST
{
  void *hDevice;
  unsigned int dwType;
};

```

### `tagEMRSETMAPPERFLAGS`
```
struct tagEMRSETMAPPERFLAGS
{
  tagEMR emr;
  unsigned int dwFlags;
};

```

### `tagRemHPALETTE`
```
struct __declspec(align(4)) tagRemHPALETTE
{
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagPARAMDATA`
```
struct __declspec(align(8)) tagPARAMDATA
{
  wchar_t *szName;
  unsigned __int16 vt;
};

```

### `tagMETHODDATA`
```
struct __declspec(align(8)) tagMETHODDATA
{
  wchar_t *szName;
  tagPARAMDATA *ppdata;
  int dispid;
  unsigned int iMeth;
  tagCALLCONV cc;
  unsigned int cArgs;
  unsigned __int16 wFlags;
  unsigned __int16 vtReturn;
};

```

### `tagINTERFACEDATA`
```
struct __declspec(align(8)) tagINTERFACEDATA
{
  tagMETHODDATA *pmethdata;
  unsigned int cMembers;
};

```

### `tagQUERYCONTEXT`
```
struct tagQUERYCONTEXT
{
  unsigned int dwContext;
  tagCSPLATFORM Platform;
  unsigned int Locale;
  unsigned int dwVersionHi;
  unsigned int dwVersionLo;
};

```

### `tagEMRSETVIEWPORTEXTEX`
```
struct tagEMRSETVIEWPORTEXTEX
{
  tagEMR emr;
  tagSIZE szlExtent;
};

```

### `tagEMRSELECTOBJECT`
```
struct tagEMRSELECTOBJECT
{
  tagEMR emr;
  unsigned int ihObject;
};

```

### `tagSTGOPTIONS`
```
struct tagSTGOPTIONS
{
  unsigned __int16 usVersion;
  unsigned __int16 reserved;
  unsigned int ulSectorSize;
  const wchar_t *pwcsTemplateFile;
};

```

### `tagCANDIDATEFORM`
```
struct tagCANDIDATEFORM
{
  unsigned int dwIndex;
  unsigned int dwStyle;
  tagPOINT ptCurrentPos;
  tagRECT rcArea;
};

```

### `tagFINDREPLACEW`
```
struct tagFINDREPLACEW
{
  unsigned int lStructSize;
  HWND__ *hwndOwner;
  HINSTANCE__ *hInstance;
  unsigned int Flags;
  wchar_t *lpstrFindWhat;
  wchar_t *lpstrReplaceWith;
  unsigned __int16 wFindWhatLen;
  unsigned __int16 wReplaceWithLen;
  __int64 lCustData;
  unsigned __int64 (__fastcall *lpfnHook)(HWND__ *, unsigned int, unsigned __int64, __int64);
  const wchar_t *lpTemplateName;
};

```

### `tagCOLORMATCHTOTARGET`
```
struct __declspec(align(4)) tagCOLORMATCHTOTARGET
{
  tagEMR emr;
  unsigned int dwAction;
  unsigned int dwFlags;
  unsigned int cbName;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagWNDCLASSEXW`
```
struct tagWNDCLASSEXW
{
  unsigned int cbSize;
  unsigned int style;
  __int64 (__fastcall *lpfnWndProc)(HWND__ *, unsigned int, unsigned __int64, __int64);
  int cbClsExtra;
  int cbWndExtra;
  HINSTANCE__ *hInstance;
  HICON__ *hIcon;
  HICON__ *hCursor;
  HBRUSH__ *hbrBackground;
  const wchar_t *lpszMenuName;
  const wchar_t *lpszClassName;
  HICON__ *hIconSm;
};

```

### `tagVS_FIXEDFILEINFO`
```
struct tagVS_FIXEDFILEINFO
{
  unsigned int dwSignature;
  unsigned int dwStrucVersion;
  unsigned int dwFileVersionMS;
  unsigned int dwFileVersionLS;
  unsigned int dwProductVersionMS;
  unsigned int dwProductVersionLS;
  unsigned int dwFileFlagsMask;
  unsigned int dwFileFlags;
  unsigned int dwFileOS;
  unsigned int dwFileType;
  unsigned int dwFileSubtype;
  unsigned int dwFileDateMS;
  unsigned int dwFileDateLS;
};

```

### `tagBIND_OPTS3`
```
struct __cppobj tagBIND_OPTS3 : tagBIND_OPTS2
{
  HWND__ *hwnd;
};

```

### `type_safe::floating_point<float>`
```
struct __cppobj type_safe::floating_point<float>
{
  float value_;
};

```

### `type_safe::floating_point<double>`
```
struct __cppobj type_safe::floating_point<double>
{
  long double value_;
};

```

### `type_safe::greater_equal`
```
struct __cppobj type_safe::greater_equal
{
};

```

### `type_safe::nullopt_t`
```
struct __cppobj type_safe::nullopt_t
{
};

```

### `type_safe::strong_typedef<type_safe::difference_t,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::strong_typedef<type_safe::difference_t,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >
{
  type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> value_;
};

```

### `type_safe::strong_typedef_op::equality_comparison<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::equality_comparison<type_safe::difference_t>
{
};

```

### `type_safe::strong_typedef_op::relational_comparison<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::relational_comparison<type_safe::difference_t>
{
};

```

### `type_safe::strong_typedef_op::unary_plus<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::unary_plus<type_safe::difference_t>
{
};

```

### `type_safe::strong_typedef_op::unary_minus<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::unary_minus<type_safe::difference_t>
{
};

```

### `type_safe::strong_typedef_op::addition<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::addition<type_safe::difference_t>
{
};

```

### `type_safe::strong_typedef_op::subtraction<type_safe::difference_t>`
```
struct __cppobj type_safe::strong_typedef_op::subtraction<type_safe::difference_t>
{
};

```

### `type_safe::difference_t`
```
struct __cppobj __declspec(align(4)) type_safe::difference_t : type_safe::strong_typedef<type_safe::difference_t,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >, type_safe::strong_typedef_op::equality_comparison<type_safe::difference_t>, type_safe::strong_typedef_op::relational_comparison<type_safe::difference_t>, type_safe::strong_typedef_op::unary_plus<type_safe::difference_t>, type_safe::strong_typedef_op::unary_minus<type_safe::difference_t>, type_safe::strong_typedef_op::addition<type_safe::difference_t>, type_safe::strong_typedef_op::subtraction<type_safe::difference_t>
{
  _BYTE gap8;
  _BYTE gapA;
  _BYTE gapC;
};

```

### `type_safe::strong_typedef<type_safe::detail::union_type_id,unsigned __int64>`
```
struct __cppobj type_safe::strong_typedef<type_safe::detail::union_type_id,unsigned __int64>
{
  unsigned __int64 value_;
};

```

### `type_safe::optional_variant_policy`
```
struct __cppobj type_safe::optional_variant_policy
{
};

```

### `type_safe::undefined_behavior_arithmetic`
```
struct __cppobj type_safe::undefined_behavior_arithmetic
{
};

```

### `type_safe::greater`
```
struct __cppobj type_safe::greater
{
};

```

### `type_safe::less_equal`
```
struct __cppobj type_safe::less_equal
{
};

```

### `type_safe::detail::move_control<0>`
```
struct __cppobj type_safe::detail::move_control<0>
{
};

```

### `type_safe::detail::no_digit`
```
struct __cppobj type_safe::detail::no_digit
{
};

```

### `type_safe::detail::storage_access`
```
struct __cppobj type_safe::detail::storage_access
{
};

```

### `type_safe::detail::is_safe_integer_conversion<unsigned int,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<unsigned int,unsigned __int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::parse_loop<>`
```
struct __cppobj type_safe::detail::parse_loop<>
{
};

```

### `type_safe::detail::is_safe_integer_operation<__int64,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::is_safe_integer_operation<__int64,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> > : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::lower_hexadecimal_digit`
```
struct __cppobj type_safe::detail::lower_hexadecimal_digit
{
};

```

### `type_safe::detail::decimal_digit`
```
struct __cppobj type_safe::detail::decimal_digit
{
};

```

### `type_safe::detail::is_safe_integer_conversion<unsigned __int64,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<unsigned __int64,unsigned __int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::make_unsigned<__int64>`
```
struct __cppobj type_safe::detail::make_unsigned<__int64>
{
};

```

### `type_safe::detail::is_safe_integer_conversion<__int64,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<__int64,__int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::is_safe_floating_point_conversion<double,double>`
```
struct __cppobj type_safe::detail::is_safe_floating_point_conversion<double,double> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::is_safe_integer_operation<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_operation<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::unsigned_integer_tag`
```
struct __cppobj type_safe::detail::unsigned_integer_tag
{
};

```

### `type_safe::detail::is_safe_integer_conversion<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic>,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic>,unsigned __int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::strong_typedef_op::equality_comparison<type_safe::detail::union_type_id>`
```
struct __cppobj type_safe::strong_typedef_op::equality_comparison<type_safe::detail::union_type_id>
{
};

```

### `type_safe::strong_typedef_op::relational_comparison<type_safe::detail::union_type_id>`
```
struct __cppobj type_safe::strong_typedef_op::relational_comparison<type_safe::detail::union_type_id>
{
};

```

### `type_safe::detail::union_type_id`
```
struct __cppobj __declspec(align(8)) type_safe::detail::union_type_id : type_safe::strong_typedef<type_safe::detail::union_type_id,unsigned __int64>, type_safe::strong_typedef_op::equality_comparison<type_safe::detail::union_type_id>, type_safe::strong_typedef_op::relational_comparison<type_safe::detail::union_type_id>
{
  _BYTE gap8;
};

```

### `type_safe::detail::is_integer<int>`
```
struct __cppobj type_safe::detail::is_integer<int> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::no_size`
```
struct __cppobj type_safe::detail::no_size
{
};

```

### `type_safe::detail::integer_result_type<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64>`
```
struct __cppobj type_safe::detail::integer_result_type<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64> : std::enable_if<0,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >
{
};

```

### `type_safe::detail::is_safe_integer_conversion<type_safe::difference_t,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<type_safe::difference_t,unsigned __int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_boolean<type_safe::boolean>`
```
struct __cppobj type_safe::detail::is_boolean<type_safe::boolean> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::make_signed<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::make_signed<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >
{
};

```

### `type_safe::detail::copy_control<0>`
```
struct __cppobj type_safe::detail::copy_control<0>
{
};

```

### `type_safe::detail::is_integer<type_safe::difference_t>`
```
struct __cppobj type_safe::detail::is_integer<type_safe::difference_t> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::non_member_size`
```
struct __cppobj type_safe::detail::non_member_size : type_safe::detail::no_size
{
};

```

### `type_safe::detail::member_size`
```
struct __cppobj type_safe::detail::member_size : type_safe::detail::non_member_size
{
};

```

### `type_safe::detail::upper_hexadecimal_digit`
```
struct __cppobj type_safe::detail::upper_hexadecimal_digit
{
};

```

### `type_safe::detail::is_safe_floating_point_conversion<float,float>`
```
struct __cppobj type_safe::detail::is_safe_floating_point_conversion<float,float> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::common_type<void,void>`
```
struct __cppobj type_safe::detail::common_type<void,void>
{
};

```

### `type_safe::detail::matching_function_pointer_tag`
```
struct __cppobj type_safe::detail::matching_function_pointer_tag
{
};

```

### `type_safe::detail::assert_handler`
```
struct __cppobj type_safe::detail::assert_handler : debug_assert::set_level<0>, debug_assert::default_handler
{
  _BYTE gap0;
};

```

### `type_safe::detail::is_safe_integer_conversion<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,unsigned __int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_integer<__int64>`
```
struct __cppobj type_safe::detail::is_integer<__int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::is_integer<unsigned __int64>`
```
struct __cppobj type_safe::detail::is_integer<unsigned __int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::integer_result_type<__int64,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::integer_result_type<__int64,type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> > : std::enable_if<0,__int64>
{
};

```

### `type_safe::detail::make_signed<unsigned __int64>`
```
struct __cppobj type_safe::detail::make_signed<unsigned __int64>
{
};

```

### `type_safe::detail::is_safe_integer_operation<__int64,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_operation<__int64,__int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::is_integer<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::is_integer<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> > : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_safe_integer_conversion<int,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<int,__int64> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::matching_functor_tag`
```
struct __cppobj type_safe::detail::matching_functor_tag
{
};

```

### `type_safe::detail::is_integer<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::is_integer<type_safe::integer<unsigned __int64,type_safe::undefined_behavior_arithmetic> > : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_safe_integer_conversion<type_safe::index_t,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<type_safe::index_t,__int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_boolean<bool>`
```
struct __cppobj type_safe::detail::is_boolean<bool> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::make_unsigned<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >`
```
struct __cppobj type_safe::detail::make_unsigned<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic> >
{
};

```

### `type_safe::detail::invalid_functor_tag`
```
struct __cppobj type_safe::detail::invalid_functor_tag
{
};

```

### `type_safe::detail::is_safe_integer_conversion<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<type_safe::integer<__int64,type_safe::undefined_behavior_arithmetic>,__int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::integer_result_type<__int64,__int64>`
```
struct __cppobj type_safe::detail::integer_result_type<__int64,__int64> : std::enable_if<1,__int64>
{
};

```

### `type_safe::detail::is_safe_integer_conversion<__int64,unsigned __int64>`
```
struct __cppobj type_safe::detail::is_safe_integer_conversion<__int64,unsigned __int64> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_integer<type_safe::index_t>`
```
struct __cppobj type_safe::detail::is_integer<type_safe::index_t> : std::integral_constant<bool,0>
{
};

```

### `type_safe::detail::is_integer<unsigned int>`
```
struct __cppobj type_safe::detail::is_integer<unsigned int> : std::integral_constant<bool,1>
{
};

```

### `type_safe::detail::precondition_error_handler`
```
struct __cppobj type_safe::detail::precondition_error_handler : debug_assert::set_level<1>, debug_assert::default_handler
{
  _BYTE gap0;
};

```

### `type_safe::strong_typedef_op::detail::make_void<>`
```
struct __cppobj type_safe::strong_typedef_op::detail::make_void<>
{
};

```

### `type_safe::less`
```
struct __cppobj type_safe::less
{
};

```

### `type_safe::default_arithmetic`
```
struct __cppobj type_safe::default_arithmetic
{
};

```

### `type_safe::not_equal_to`
```
struct __cppobj type_safe::not_equal_to
{
};

```

### `type_safe::equal_to`
```
struct __cppobj type_safe::equal_to
{
};

```

### `type_safe::checked_arithmetic::error`
```
struct __cppobj type_safe::checked_arithmetic::error : std::range_error
{
};

```

### `type_safe::checked_arithmetic::error_vtbl`
```
struct /*VFT*/ type_safe::checked_arithmetic::error_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `type_safe::checked_arithmetic`
```
struct __cppobj type_safe::checked_arithmetic
{
};

```

### `tagEMRSETMITERLIMIT`
```
struct tagEMRSETMITERLIMIT
{
  tagEMR emr;
  float eMiterLimit;
};

```

### `tagDEVNAMES`
```
struct tagDEVNAMES
{
  unsigned __int16 wDriverOffset;
  unsigned __int16 wDeviceOffset;
  unsigned __int16 wOutputOffset;
  unsigned __int16 wDefault;
};

```

### `tagTITLEBARINFOEX`
```
struct tagTITLEBARINFOEX
{
  unsigned int cbSize;
  tagRECT rcTitleBar;
  unsigned int rgstate[6];
  tagRECT rgrect[6];
};

```

### `tagMETARECORD`
```
struct tagMETARECORD
{
  unsigned int rdSize;
  unsigned __int16 rdFunction;
  unsigned __int16 rdParm[1];
};

```

### `tagSERIALKEYSW`
```
struct __declspec(align(8)) tagSERIALKEYSW
{
  unsigned int cbSize;
  unsigned int dwFlags;
  wchar_t *lpszActivePort;
  wchar_t *lpszPort;
  unsigned int iBaudRate;
  unsigned int iPortState;
  unsigned int iActive;
};

```

### `tagACCEL`
```
struct tagACCEL
{
  unsigned __int8 fVirt;
  unsigned __int16 key;
  unsigned __int16 cmd;
};

```

### `tagEMRSETPIXELV`
```
struct tagEMRSETPIXELV
{
  tagEMR emr;
  _POINTL ptlPixel;
  unsigned int crColor;
};

```

### `tagEMRPIXELFORMAT`
```
struct tagEMRPIXELFORMAT
{
  tagEMR emr;
  tagPIXELFORMATDESCRIPTOR pfd;
};

```

### `tagMSLLHOOKSTRUCT`
```
struct tagMSLLHOOKSTRUCT
{
  tagPOINT pt;
  unsigned int mouseData;
  unsigned int flags;
  unsigned int time;
  unsigned __int64 dwExtraInfo;
};

```

### `tagEMRSETICMPROFILE`
```
struct __declspec(align(4)) tagEMRSETICMPROFILE
{
  tagEMR emr;
  unsigned int dwFlags;
  unsigned int cbName;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagTOGGLEKEYS`
```
struct tagTOGGLEKEYS
{
  unsigned int cbSize;
  unsigned int dwFlags;
};

```

### `tagTPMPARAMS`
```
struct tagTPMPARAMS
{
  unsigned int cbSize;
  tagRECT rcExclude;
};

```

### `tagEMRBITBLT`
```
struct tagEMRBITBLT
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int cxDest;
  int cyDest;
  unsigned int dwRop;
  int xSrc;
  int ySrc;
  tagXFORM xformSrc;
  unsigned int crBkColorSrc;
  unsigned int iUsageSrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
};

```

### `tagCOPYDATASTRUCT`
```
struct tagCOPYDATASTRUCT
{
  unsigned __int64 dwData;
  unsigned int cbData;
  void *lpData;
};

```

### `tagMOUSEKEYS`
```
struct tagMOUSEKEYS
{
  unsigned int cbSize;
  unsigned int dwFlags;
  unsigned int iMaxSpeed;
  unsigned int iTimeToMaxSpeed;
  unsigned int iCtrlSpeed;
  unsigned int dwReserved1;
  unsigned int dwReserved2;
};

```

### `tagRemHGLOBAL`
```
struct __declspec(align(4)) tagRemHGLOBAL
{
  int fNullHGlobal;
  unsigned int cbData;
  unsigned __int8 data[1];
};

```

### `tagEMRSTRETCHDIBITS`
```
struct tagEMRSTRETCHDIBITS
{
  tagEMR emr;
  _RECTL rclBounds;
  int xDest;
  int yDest;
  int xSrc;
  int ySrc;
  int cxSrc;
  int cySrc;
  unsigned int offBmiSrc;
  unsigned int cbBmiSrc;
  unsigned int offBitsSrc;
  unsigned int cbBitsSrc;
  unsigned int iUsageSrc;
  unsigned int dwRop;
  int cxDest;
  int cyDest;
};

```

### `tagEMRINVERTRGN`
```
struct __declspec(align(4)) tagEMRINVERTRGN
{
  tagEMR emr;
  _RECTL rclBounds;
  unsigned int cbRgnData;
  unsigned __int8 RgnData[1];
};

```

### `tagCLEANLOCALSTORAGE`
```
struct __declspec(align(8)) tagCLEANLOCALSTORAGE
{
  IUnknown *pInterface;
  void *pStorage;
  unsigned int flags;
};

```

### `tagEMRSETARCDIRECTION`
```
struct tagEMRSETARCDIRECTION
{
  tagEMR emr;
  unsigned int iArcDirection;
};

```

### `tagANIMATIONINFO`
```
struct tagANIMATIONINFO
{
  unsigned int cbSize;
  int iMinAnimate;
};

```

### `tagEMRCREATEMONOBRUSH`
```
struct tagEMRCREATEMONOBRUSH
{
  tagEMR emr;
  unsigned int ihBrush;
  unsigned int iUsage;
  unsigned int offBmi;
  unsigned int cbBmi;
  unsigned int offBits;
  unsigned int cbBits;
};

```

### `tagCURSORSHAPE`
```
struct __declspec(align(4)) tagCURSORSHAPE
{
  int xHotSpot;
  int yHotSpot;
  int cx;
  int cy;
  int cbWidth;
  unsigned __int8 Planes;
  unsigned __int8 BitsPixel;
};

```

### `tagRPC_EXTENDED_ERROR_INFO`
```
struct tagRPC_EXTENDED_ERROR_INFO
{
  unsigned int Version;
  wchar_t *ComputerName;
  unsigned int ProcessID;
  tagRPC_EXTENDED_ERROR_INFO::<unnamed_type_u> u;
  unsigned int GeneratingComponent;
  unsigned int Status;
  unsigned __int16 DetectionLocation;
  unsigned __int16 Flags;
  int NumberOfParameters;
  tagRPC_EE_INFO_PARAM Parameters[4];
};

```

### `tagMINIMIZEDMETRICS`
```
struct tagMINIMIZEDMETRICS
{
  unsigned int cbSize;
  int iWidth;
  int iHorzGap;
  int iVertGap;
  int iArrange;
};

```

### `tagEMRGDICOMMENT`
```
struct __declspec(align(4)) tagEMRGDICOMMENT
{
  tagEMR emr;
  unsigned int cbData;
  unsigned __int8 Data[1];
};

```

### `tagEMRSCALEVIEWPORTEXTEX`
```
struct tagEMRSCALEVIEWPORTEXTEX
{
  tagEMR emr;
  int xNum;
  int xDenom;
  int yNum;
  int yDenom;
};

```

### `TerrainTextures`
```
struct __cppobj TerrainTextures
{
  std::array<std::shared_ptr<mce::ClientTexture>,4> mBrightnessTextures;
  mce::TexturePtr mEndPortalColorTexture;
  mce::TexturePtr mEndPortalTexture;
  std::shared_ptr<mce::ClientTexture> mFoliageTexture;
  std::vector<mce::TexturePtr> mAtlasLayers;
};

```

### `TripodActivationRule`
```
struct __cppobj TripodActivationRule : ActivationRule
{
};

```

### `TripodActivationRule_vtbl`
```
struct /*VFT*/ TripodActivationRule_vtbl
{
  void (__fastcall *~ActivationRule)(ActivationRule *this);
  std::unique_ptr<ActivationRule> *(__fastcall *create)(ActivationRule *this, std::unique_ptr<ActivationRule> *result, Json::Value *);
  bool (__fastcall *evaluate)(ActivationRule *this, const IClientInstance *, float, const Camera *);
};

```

### `TextureAtlasResourceCallbacks`
```
struct __cppobj TextureAtlasResourceCallbacks
{
  std::function<TaskResult __cdecl(void)> mThreadedCallback;
  std::function<void __cdecl(void)> mMainThreadCallback;
};

```

### `TestClientCommands`
```
struct __cppobj TestClientCommands
{
};

```

### `TextObjectText`
```
struct __cppobj TextObjectText : ITextObject
{
  std::string mText;
};

```

### `TextObjectText_vtbl`
```
struct /*VFT*/ TextObjectText_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TextObjectLocalizedTextWithParams`
```
struct __cppobj TextObjectLocalizedTextWithParams : ITextObject
{
  std::string mText;
  std::unique_ptr<TextObjectRoot> mParams;
};

```

### `TextObjectLocalizedTextWithParams_vtbl`
```
struct /*VFT*/ TextObjectLocalizedTextWithParams_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TransferPacketHandler::<unnamed_type_mHostModel>`
```
struct __cppobj TransferPacketHandler::<unnamed_type_mHostModel>
{
  unsigned __int8 mMaxClientCount;
  TransferRoomPrivacy mPrivacy;
  TransferRoomPlatform mAllowPe;
  std::string mRoomName;
  std::string mLevelId;
  GameType mGameType;
  unsigned int mRoomId;
  unsigned __int16 mIpv4Port;
  unsigned __int16 mIpv6Port;
  std::vector<unsigned char> tagIds;
  std::string createRoomExtraBits;
};

```

### `TransferPacketHandler::<unnamed_type_mClientModel>`
```
struct __cppobj TransferPacketHandler::<unnamed_type_mClientModel>
{
  unsigned int mOwnerUserId;
  unsigned int mRoomId;
  std::vector<unsigned int> mPlayerUids;
  std::string mServerHost;
};

```

### `TransferPacketHandler`
```
struct __cppobj __declspec(align(8)) TransferPacketHandler : NetEventCallback
{
  std::shared_ptr<NetworkHandler> mNetworkHandler;
  std::unique_ptr<ChaCha> mEncryptChaCha;
  std::unique_ptr<ChaCha> mDecryptChaCha;
  std::string mEncryptKey;
  std::string mDecryptKey;
  unsigned int mUserId;
  std::string mUserToken;
  RakNet::RakNetGUID mRakNetGUID;
  std::string mRandSeed;
  std::string mAesRandSeed;
  std::function<void __cdecl(void)> mPrepareCallback;
  bool mIsHost;
  bool mIsGameStarted;
  TransferPacketHandler::<unnamed_type_mHostModel> mHostModel;
  TransferPacketHandler::<unnamed_type_mClientModel> mClientModel;
  std::set<unsigned int> mIncomingUsers;
  bool mLoggedIn;
  bool mCreatedOrJoinedRoom;
};

```

### `typeid_t<ScriptBinderComponent>`
```
struct __cppobj typeid_t<ScriptBinderComponent>
{
  unsigned __int16 mID;
};

```

### `ThrowableItemComponent`
```
struct __cppobj __declspec(align(4)) ThrowableItemComponent : ItemComponent
{
  bool mDoSwing;
  float mMinDrawDuration;
  float mDrawDuration;
  float mLaunchPowerScale;
  float mMaxLaunchPower;
  bool mScalePowerByDrawDuration;
};

```

### `ThrowableItemComponent_vtbl`
```
struct /*VFT*/ ThrowableItemComponent_vtbl
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

### `TrialManager::setTrialABTest::__l2::<lambda_c30bbd6b5b06c9cde920159e96e64d3e>`
```
struct __cppobj TrialManager::setTrialABTest::__l2::<lambda_c30bbd6b5b06c9cde920159e96e64d3e>
{
  TrialManager *const __this;
  PropertyBag *abTests;
};

```

### `TrialTimerTextRenderer`
```
struct __cppobj TrialTimerTextRenderer : MinecraftUICustomRenderer
{
};

```

### `TrialTimerTextRenderer_vtbl`
```
struct /*VFT*/ TrialTimerTextRenderer_vtbl
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

### `TextToSpeechComponent`
```
struct __cppobj __declspec(align(8)) TextToSpeechComponent : UIComponent
{
  int mTTSComponentNamePriority;
  int mTTSComponentValuePriority;
  int mTTSIndexValuePriority;
  std::string mOverrideComponentValue;
  std::string mComponentHeader;
  std::string mSectionHeaderOverride;
  std::string mTTSControlType;
  bool mInheritTTSSiblings;
  bool mMessageInterruptible;
  int mTTSIndexOrder;
  bool mIgnoreSubsections;
  bool mIgnoreForTTSIndexCount;
  bool mSkipNarration;
};

```

### `TextToSpeechComponent_vtbl`
```
struct /*VFT*/ TextToSpeechComponent_vtbl
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

### `TextToSpeechContainerComponent`
```
struct __cppobj TextToSpeechContainerComponent : UIComponent
{
  std::string mSectionHeader;
};

```

### `TextToSpeechContainerComponent_vtbl`
```
struct /*VFT*/ TextToSpeechContainerComponent_vtbl
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

### `ToggleManagerComponent`
```
struct __cppobj ToggleManagerComponent : UIComponent
{
  ToggleManagerBehavior mBehavior;
  std::vector<unsigned int> mToggleGroupNames;
};

```

### `ToggleManagerComponent_vtbl`
```
struct /*VFT*/ ToggleManagerComponent_vtbl
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

### `ToggleManagerComponent::_defaultToggleGroupState::__l9::<lambda_12f26c8dc2ca39311adb402504fcedde>`
```
struct __cppobj ToggleManagerComponent::_defaultToggleGroupState::__l9::<lambda_12f26c8dc2ca39311adb402504fcedde>
{
  unsigned int groupName;
};

```

### `ToggleManagerComponent::_gatherToggleGroupState::__l9::<lambda_ca15693672eabce4abc5322de9dd77d8>`
```
struct __cppobj ToggleManagerComponent::_gatherToggleGroupState::__l9::<lambda_ca15693672eabce4abc5322de9dd77d8>
{
  unsigned int groupeName;
};

```

### `ToggleManagerComponent::_updateToggleGroupState::__l9::<lambda_2cadc300ef6806b33ff78c7f6178869c>`
```
struct __cppobj ToggleManagerComponent::_updateToggleGroupState::__l9::<lambda_2cadc300ef6806b33ff78c7f6178869c>
{
  unsigned int groupName;
};

```

### `ToggleComponent::_updateToggleGroupState::__l2::<lambda_17a4efe3fb46caa404d1b253c6c028aa>`
```
struct __cppobj __declspec(align(8)) ToggleComponent::_updateToggleGroupState::__l2::<lambda_17a4efe3fb46caa404d1b253c6c028aa>
{
  ToggleComponent *const __this;
  const unsigned int groupName;
};

```

### `TextToSpeechComponent::_getControlIndexAndSectionCount::__l2::<lambda_d030f3c5102e18e1f48320b267600bb9>`
```
struct __cppobj TextToSpeechComponent::_getControlIndexAndSectionCount::__l2::<lambda_d030f3c5102e18e1f48320b267600bb9>
{
  int *count;
  int *numBefore;
  int *numSubIndicesBefore;
  bool *foundParent;
  TextToSpeechComponent *const __this;
};

```

### `TextToSpeechComponent::_addComponentStringToTTS::__l2::<lambda_c27c32a302c4e74a5d899a589fb9fc6c>`
```
struct __cppobj TextToSpeechComponent::_addComponentStringToTTS::__l2::<lambda_c27c32a302c4e74a5d899a589fb9fc6c>
{
  std::string *message;
  const TextToSpeechComponent *const __this;
  const std::function<std::string __cdecl(std::string const &,std::optional<std::vector<std::string> >)> *localizationCallback;
};

```

### `TextToSpeechComponent::_addComponentStringToTTS::__l2::<lambda_86cbabb9349b322ab8ada6118b46dc41>`
```
struct __cppobj TextToSpeechComponent::_addComponentStringToTTS::__l2::<lambda_86cbabb9349b322ab8ada6118b46dc41>
{
  std::multimap<int,std::string> *messageQueue;
  const TextToSpeechComponent *const __this;
  const std::function<std::string __cdecl(std::string const &,std::optional<std::vector<std::string> >)> *localizationCallback;
};

```

### `TextEditComponent::registerTextParam::__l5::<lambda_745368237de7bd6abcfa7a0fd1a5b5e5>`
```
struct __cppobj TextEditComponent::registerTextParam::__l5::<lambda_745368237de7bd6abcfa7a0fd1a5b5e5>
{
  TextEditComponent *const __this;
};

```

### `TextEditComponent::registerPropertyChangedNotifications::__l5::<lambda_d0aaf1a92f88685d006ea6fdfb160693>`
```
struct __cppobj TextEditComponent::registerPropertyChangedNotifications::__l5::<lambda_d0aaf1a92f88685d006ea6fdfb160693>
{
  TextEditComponent *const __this;
};

```

### `TextEditComponent::handleTextCharEvent::__l20::<lambda_b14aeca121a64518d1a3ae7a89d7d6ea>`
```
struct __cppobj TextEditComponent::handleTextCharEvent::__l20::<lambda_b14aeca121a64518d1a3ae7a89d7d6ea>
{
  TextEditComponent *const __this;
  std::weak_ptr<bool> weakBool;
};

```

### `TrueTypeFont`
```
struct __cppobj TrueTypeFont : Font
{
  Core::PathBuffer<std::string > mFontFile;
  int mCollectionIndex;
  unsigned int mVersion;
  unsigned __int8 mDefaultRenderSize;
  unsigned __int16 mAtlasPageSize;
  float mRenderSizeToGameSizeScalar;
  bool mFirstSheetIsShared;
  bool mIsReloading;
  TrueTypeFont::LoadedFontInformation mLoadedFontInformation;
  std::unordered_map<int,TrueTypeFont::PageOfGlyphs> mGlyphSheets;
  std::vector<std::pair<ResourceLocation,std::shared_ptr<cg::ImageBuffer> >> mTexturesToUpload;
  std::mutex mIsReloadingMutex;
  std::recursive_mutex mLoadedFontInformationGlyphSheetsMutex;
  std::mutex mTexturesToUploadMutex;
};

```

### `TrueTypeFont::LoadedFontInformation`
```
struct __cppobj TrueTypeFont::LoadedFontInformation
{
  stbtt_fontinfo info;
  float scale;
  float ascent;
  float descent;
  float lineGap;
  std::shared_ptr<std::string > resourceData;
};

```

### `TrueTypeFont_vtbl`
```
struct /*VFT*/ TrueTypeFont_vtbl
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
  Core::PathBuffer<std::string > *(__fastcall *getUnicodeFontNameWithPage)(TrueTypeFont *this, Core::PathBuffer<std::string > *result, const Core::Path *, const unsigned __int8);
};

```

### `TrueTypeMsdfFont`
```
struct __cppobj TrueTypeMsdfFont : Font
{
  std::unordered_map<int,float> mGlyphWidths;
  std::unordered_set<int> mGlyphSheets;
  Core::PathBuffer<std::string > mFontFile;
  std::string mFontResourceData;
  unsigned int mVersion;
  std::vector<std::pair<ResourceLocation,std::shared_ptr<cg::ImageBuffer> >> mTexturesToUpload;
  bool mIsReloading;
  FT_LibraryRec_ *mFreeTypeLibrary;
  FT_FaceRec_ *mFontFace;
};

```

### `TrueTypeMsdfFont_vtbl`
```
struct /*VFT*/ TrueTypeMsdfFont_vtbl
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
  Core::PathBuffer<std::string > *(__fastcall *getUnicodeFontNameWithPage)(TrueTypeMsdfFont *this, Core::PathBuffer<std::string > *result, const Core::Path *, const unsigned __int8);
};

```

### `ThirdPartyServerItemProgressHandler`
```
struct __cppobj ThirdPartyServerItemProgressHandler : StoreProgressHandler
{
  std::string mServerName;
};

```

### `ThirdPartyServerItemProgressHandler_vtbl`
```
struct /*VFT*/ ThirdPartyServerItemProgressHandler_vtbl
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

### `TrueTypeMsdfFont::reloadFontTextures::__l11::<lambda_cf3df30235cd8ea222e022252afc0421>`
```
struct __cppobj TrueTypeMsdfFont::reloadFontTextures::__l11::<lambda_cf3df30235cd8ea222e022252afc0421>
{
  TrueTypeMsdfFont *const __this;
};

```

### `TrueTypeMsdfFont::reloadFontTextures::__l11::<lambda_7619341e5294fd85cbcc7a01d6bdd2b8>`
```
struct __cppobj TrueTypeMsdfFont::reloadFontTextures::__l11::<lambda_7619341e5294fd85cbcc7a01d6bdd2b8>
{
  TrueTypeMsdfFont *const __this;
};

```

### `TrueTypeFont::_queueAtlasForUpload::__l2::<lambda_72bda49c80fd5e57dd3ddf026138fb59>`
```
struct __cppobj __declspec(align(8)) TrueTypeFont::_queueAtlasForUpload::__l2::<lambda_72bda49c80fd5e57dd3ddf026138fb59>
{
  TrueTypeFont *const __this;
  const int sheetIndex;
};

```

### `TrueTypeFont::reloadFontTextures::__l14::<lambda_e1e95685307b913616f04cba0e107a81>`
```
struct __cppobj TrueTypeFont::reloadFontTextures::__l14::<lambda_e1e95685307b913616f04cba0e107a81>
{
  TrueTypeFont *const __this;
};

```

### `TrueTypeFont::reloadFontTextures::__l14::<lambda_426b994154f9107e0b15c5313f9e4cc8>`
```
struct __cppobj TrueTypeFont::reloadFontTextures::__l14::<lambda_426b994154f9107e0b15c5313f9e4cc8>
{
  TrueTypeFont *const __this;
};

```

### `TrueTypeFont::_loadSheet::__l33::<lambda_8b0436422f0b9144af5aaeec973271d9>`
```
struct __cppobj TrueTypeFont::_loadSheet::__l33::<lambda_8b0436422f0b9144af5aaeec973271d9>
{
  TrueTypeFont *const __this;
};

```

### `TextObjectParser`
```
struct __cppobj TextObjectParser
{
};

```

### `TemporaryItemCounter`
```
struct __cppobj __declspec(align(8)) TemporaryItemCounter
{
  ItemInstance mItemInst;
  int mTotalCount;
};

```

### `TabbedUpsellScreenController`
```
struct __cppobj __declspec(align(8)) TabbedUpsellScreenController : MinecraftScreenController
{
  TabbedUpsellScreenDefaultTab mActiveTabIndex;
};

```

### `TabbedUpsellScreenController_vtbl`
```
struct /*VFT*/ TabbedUpsellScreenController_vtbl
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

### `TemplateExportScreenController`
```
struct __cppobj TemplateExportScreenController : MainMenuScreenController
{
  std::weak_ptr<IWorldSettingsStorage> mWorldSettingsStorageInterface;
  std::string mMinTemplateVersionString;
  GameVersion mMinTemplateVersion;
};

```

### `TemplateExportScreenController_vtbl`
```
struct /*VFT*/ TemplateExportScreenController_vtbl
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

### `TemplateExportScreenController::_validateTemplateVersion::__l2::<lambda_77558d3841ad27bd312186249b41887b>`
```
struct __cppobj TemplateExportScreenController::_validateTemplateVersion::__l2::<lambda_77558d3841ad27bd312186249b41887b>
{
  TemplateExportScreenController *const __this;
};

```

### `TestScreenController`
```
struct __cppobj __declspec(align(8)) TestScreenController : MinecraftScreenController
{
  unsigned int mGoButton1Id;
  unsigned int mGoButton2Id;
  bool mAnimActive;
};

```

### `TestScreenController_vtbl`
```
struct /*VFT*/ TestScreenController_vtbl
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

### `ThirdPartyStoreScreenController`
```
struct __cppobj ThirdPartyStoreScreenController : StoreBaseScreenController
{
};

```

### `ThirdPartyStoreScreenController_vtbl`
```
struct /*VFT*/ ThirdPartyStoreScreenController_vtbl
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

### `ToastScreenController`
```
struct __cppobj ToastScreenController : MinecraftScreenController
{
  bool mAnimationActive;
  bool mSplitscreenJoinPopupActive;
  std::weak_ptr<PerfTurtleScreenController> mPerfTurtleScreenController;
  PersonaRepository *mPersonaRepository;
};

```

### `ToastScreenController_vtbl`
```
struct /*VFT*/ ToastScreenController_vtbl
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

### `TokenFAQScreenController`
```
struct __cppobj TokenFAQScreenController : MainMenuScreenController
{
};

```

### `TokenFAQScreenController_vtbl`
```
struct /*VFT*/ TokenFAQScreenController_vtbl
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

### `Trade2ContainerManagerModel`
```
struct __cppobj __declspec(align(8)) Trade2ContainerManagerModel : LevelContainerManagerModel
{
  int mSelectedTrade;
};

```

### `Trade2ContainerManagerModel_vtbl`
```
struct /*VFT*/ Trade2ContainerManagerModel_vtbl
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

### `Trade2ContainerManagerController_vtbl`
```
struct /*VFT*/ Trade2ContainerManagerController_vtbl
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

### `Trade2ScreenController`
```
struct __cppobj Trade2ScreenController : ContainerScreenController
{
  std::shared_ptr<Trade2ContainerManagerController> mTradeContainerManagerController;
  std::vector<int> mNumberOfTradesByTier;
  int mSelectedLeftTab;
  int mLastExp;
  int mNewExp;
  int mExpAnimationTimer;
  bool mShowVisualOffer;
  MerchantRecipe mVisualOffer;
  ItemInstance mVisualBuyAItem;
  ItemInstance mVisualBuyBItem;
  ItemInstance mVisualSellItem;
};

```

### `Trade2ScreenController_vtbl`
```
struct /*VFT*/ Trade2ScreenController_vtbl
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

### `TradeContainerManagerModel`
```
struct __cppobj __declspec(align(8)) TradeContainerManagerModel : LevelContainerManagerModel
{
  int mCurrentIndex;
};

```

### `TradeContainerManagerModel_vtbl`
```
struct /*VFT*/ TradeContainerManagerModel_vtbl
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

### `TradeContainerManagerController`
```
struct __cppobj TradeContainerManagerController : ContainerManagerController
{
  std::weak_ptr<TradeContainerManagerModel> mTradeContainerMangerModel;
  int mCurrentRecipeIndex;
  const SlotData mCreatedItemOutputSlot;
  ItemInstance mResultPreviewItem;
  MerchantRecipe *mResultPreviewRecipe;
};

```

### `TradeContainerManagerController_vtbl`
```
struct /*VFT*/ TradeContainerManagerController_vtbl
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

### `TradeScreenController`
```
struct __cppobj TradeScreenController : ContainerScreenController
{
  int mCurrentIndex;
  std::shared_ptr<TradeContainerManagerController> mTradeContainerManagerController;
};

```

### `TradeScreenController_vtbl`
```
struct /*VFT*/ TradeScreenController_vtbl
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

### `TrialUpsellScreenController`
```
struct __cppobj __declspec(align(8)) TrialUpsellScreenController : MinecraftScreenController
{
  bool mIsNewWorld;
  bool mTimeExpired;
};

```

### `TrialUpsellScreenController_vtbl`
```
struct /*VFT*/ TrialUpsellScreenController_vtbl
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

### `TTSEnabledWarningScreenController`
```
struct __cppobj TTSEnabledWarningScreenController : MinecraftScreenController
{
  bool mFirstTick;
  const TTSEnabledStatus mEnabledStatus;
};

```

### `TTSEnabledWarningScreenController_vtbl`
```
struct /*VFT*/ TTSEnabledWarningScreenController_vtbl
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

### `TutorialScreenController`
```
struct __cppobj TutorialScreenController : MainMenuScreenController
{
  std::shared_ptr<EducationContentManagerScreenController> mEducationContentManagerScreenController;
  std::shared_ptr<TutorialCollection> mTutorialCollection;
  std::shared_ptr<TutorialItem> mActiveTutorialItem;
  int mActiveItemIndex;
  int mHoveredItemIndex;
};

```

### `TutorialScreenController_vtbl`
```
struct /*VFT*/ TutorialScreenController_vtbl
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

### `TutorialScreenController::_onDownloadError::__l2::<lambda_23b2f1528d64ac1a6cf423c817d4e981>`
```
struct __cppobj TutorialScreenController::_onDownloadError::__l2::<lambda_23b2f1528d64ac1a6cf423c817d4e981>
{
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_13dac67bd65710286b4696703b40951a>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_13dac67bd65710286b4696703b40951a>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_b03583d5d4a8d0e8be0daa83697948c2>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_b03583d5d4a8d0e8be0daa83697948c2>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_fe98fdab113b6fd68a78765ca98d0d4e>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_fe98fdab113b6fd68a78765ca98d0d4e>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_db2c33509d8c77814d6629e3e3720af6>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_db2c33509d8c77814d6629e3e3720af6>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_d96da64dc7efac910adbb14ab3feaf87>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_d96da64dc7efac910adbb14ab3feaf87>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_99334fc6ecb4e5cdbe73bfd18b0adb08>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_99334fc6ecb4e5cdbe73bfd18b0adb08>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_b7251a6107a9a61c95767a1d66fd18cc>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_b7251a6107a9a61c95767a1d66fd18cc>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_393ba30a81e652cd9eb3f5e3ea9f569f>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_393ba30a81e652cd9eb3f5e3ea9f569f>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerEventHandlers::__l2::<lambda_2073ff7892642018b0c5abf268ee8c4b>`
```
struct __cppobj TutorialScreenController::_registerEventHandlers::__l2::<lambda_2073ff7892642018b0c5abf268ee8c4b>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_c92cc20637f7091520839896358278b8>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_c92cc20637f7091520839896358278b8>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_dc5c51c3cafeef9ebeaffaa7ee0739a8>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_dc5c51c3cafeef9ebeaffaa7ee0739a8>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_e1d8e24c03bda4d955e4f054168a9f49>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_e1d8e24c03bda4d955e4f054168a9f49>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_ac9c7257821d4fef6bf5bca67c5390a1>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_ac9c7257821d4fef6bf5bca67c5390a1>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_17e83845737e7a10692083a77807dde6>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_17e83845737e7a10692083a77807dde6>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_6b54b4e5b58cea5081892d937c6687d5>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_6b54b4e5b58cea5081892d937c6687d5>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_6847dc1cffd9361e3d110f2c034edbe0>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_6847dc1cffd9361e3d110f2c034edbe0>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_a9db0baedba4e87a66b606890bde9847>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_a9db0baedba4e87a66b606890bde9847>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_edf3adb023ffc159bd8592835f17af22>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_edf3adb023ffc159bd8592835f17af22>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_ae74be6026a6d576c04d24769bee4179>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_ae74be6026a6d576c04d24769bee4179>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_4c8d1be414b97685cb8e6bac1cab2d7f>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_4c8d1be414b97685cb8e6bac1cab2d7f>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_7db746b5af55e90d585f1504cd1c60a0>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_7db746b5af55e90d585f1504cd1c60a0>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_fa8f8c2d571a37597fb0d9d6837aaa17>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_fa8f8c2d571a37597fb0d9d6837aaa17>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_d667c918a00399ec8156645be04b6747>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_d667c918a00399ec8156645be04b6747>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_24085719d9677c2daa24575fc35ed86d>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_24085719d9677c2daa24575fc35ed86d>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_60c15c3559db21674bac191ba4ee7f62>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_60c15c3559db21674bac191ba4ee7f62>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_545b8a2257c578651972e523025adcc1>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_545b8a2257c578651972e523025adcc1>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_dddae3021219bb2a9d18a20891484102>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_dddae3021219bb2a9d18a20891484102>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_95b19c2e8c73803f7740b3002e7a6a07>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_95b19c2e8c73803f7740b3002e7a6a07>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_95b02572473ede360e60805c33b71280>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_95b02572473ede360e60805c33b71280>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_6482cb3f446ba9320df8689969f7b27d>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_6482cb3f446ba9320df8689969f7b27d>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_777a3f245db278f05ac72bed95c5c9f7>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_777a3f245db278f05ac72bed95c5c9f7>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_d481500e8fdc73c639515c9f54d283f9>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_d481500e8fdc73c639515c9f54d283f9>
{
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_843592290c9bbd865539eba48d772e65>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_843592290c9bbd865539eba48d772e65>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_8214bc87c37fe7bf969f807b65ee784e>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_8214bc87c37fe7bf969f807b65ee784e>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_d2f5a688761796c57a1e0297ee301a2e>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_d2f5a688761796c57a1e0297ee301a2e>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_203b49a3262d345e7f8ff929fbf7d222>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_203b49a3262d345e7f8ff929fbf7d222>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_9acfcaa137f523e3819ffc7a6f9f89e6>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_9acfcaa137f523e3819ffc7a6f9f89e6>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_c5bda68251f2a90b3fe92c25269f3a59>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_c5bda68251f2a90b3fe92c25269f3a59>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_a2b8ecd808bc19783458cf5cfdad1af2>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_a2b8ecd808bc19783458cf5cfdad1af2>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_aec622f0886d1ef324d718fafe9b761b>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_aec622f0886d1ef324d718fafe9b761b>
{
  TutorialScreenController *const __this;
};

```

### `TutorialScreenController::_registerBindings::__l2::<lambda_a751a3d129b988a013ad89f32b3dba75>`
```
struct __cppobj TutorialScreenController::_registerBindings::__l2::<lambda_a751a3d129b988a013ad89f32b3dba75>
{
  TutorialScreenController *const __this;
};

```

### `TTSEnabledWarningScreenController::tick::__l5::<lambda_b65b4fa076e22992cdfe8f125f5618e4>`
```
struct __cppobj TTSEnabledWarningScreenController::tick::__l5::<lambda_b65b4fa076e22992cdfe8f125f5618e4>
{
  TTSEnabledWarningScreenController *const __this;
};

```

### `TrialUpsellScreenController::_registerBindings::__l2::<lambda_5a3b479643b814f29eb82acb50b9efe7>`
```
struct __cppobj TrialUpsellScreenController::_registerBindings::__l2::<lambda_5a3b479643b814f29eb82acb50b9efe7>
{
  TrialUpsellScreenController *const __this;
};

```

### `TrialUpsellScreenController::_registerBindings::__l2::<lambda_c0c46cae410e36b7d312b15a2a208797>`
```
struct __cppobj TrialUpsellScreenController::_registerBindings::__l2::<lambda_c0c46cae410e36b7d312b15a2a208797>
{
  TrialUpsellScreenController *const __this;
};

```

### `TrialUpsellScreenController::_registerBindings::__l2::<lambda_aba5d4a8df7f5247a28c4da8c07b8279>`
```
struct __cppobj TrialUpsellScreenController::_registerBindings::__l2::<lambda_aba5d4a8df7f5247a28c4da8c07b8279>
{
  TrialUpsellScreenController *const __this;
};

```

### `TrialUpsellScreenController::_registerEventHandlers::__l2::<lambda_ee15e1f1404add9f2e05ad3fd92c308e>`
```
struct __cppobj TrialUpsellScreenController::_registerEventHandlers::__l2::<lambda_ee15e1f1404add9f2e05ad3fd92c308e>
{
  TrialUpsellScreenController *const __this;
};

```

### `TrialUpsellScreenController::_registerEventHandlers::__l2::<lambda_8998b6e291a35f8b1ce98446ba2d0242>`
```
struct __cppobj TrialUpsellScreenController::_registerEventHandlers::__l2::<lambda_8998b6e291a35f8b1ce98446ba2d0242>
{
  TrialUpsellScreenController *const __this;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_14b4e95cb16ef9beba6419dee6e680fd>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_14b4e95cb16ef9beba6419dee6e680fd>
{
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_cf6bed908a9220c62b884466191a8d62>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_cf6bed908a9220c62b884466191a8d62>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_9dc289b798e739268583fdaba34bfc29>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_9dc289b798e739268583fdaba34bfc29>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_19f6604fbe7f053c434320992f3fbf4d>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_19f6604fbe7f053c434320992f3fbf4d>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_2c19b106adc13a4b38ab22997ff3a10b>`
```
struct __cppobj __declspec(align(8)) TradeScreenController::_registerStateMachine::__l2::<lambda_2c19b106adc13a4b38ab22997ff3a10b>
{
  TradeScreenController *const __this;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_af18b0bda2235a491a5c381015b8a0b0>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_af18b0bda2235a491a5c381015b8a0b0>
{
  TradeScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_8b2983440b84a7f442a20b49d1633d00>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_8b2983440b84a7f442a20b49d1633d00>
{
  TradeScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerStateMachine::__l2::<lambda_4d0c0d989646feb9c4147577f05cc344>`
```
struct __cppobj TradeScreenController::_registerStateMachine::__l2::<lambda_4d0c0d989646feb9c4147577f05cc344>
{
  TradeScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_9fb3437738a256371b18a8994914f9d6>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_9fb3437738a256371b18a8994914f9d6>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_6edcb0a685152212bec264329cd48041>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_6edcb0a685152212bec264329cd48041>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_6fbfe2265bc9b20ce962c6d8f5f3155b>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_6fbfe2265bc9b20ce962c6d8f5f3155b>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_6ea878b20decf06268ebdd877ae62f0a>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_6ea878b20decf06268ebdd877ae62f0a>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_a3ad63fecb684726fb3183dc321ec1d9>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_a3ad63fecb684726fb3183dc321ec1d9>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_b0b15455af551b2a1daa2ac5d00df448>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_b0b15455af551b2a1daa2ac5d00df448>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_f2ab1926b5b810b78a33c601eb54e5e4>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_f2ab1926b5b810b78a33c601eb54e5e4>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_ed2be208c6b9fb36bfad07f191b027fc>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_ed2be208c6b9fb36bfad07f191b027fc>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_04d7d683c89ed1eee342fada40c8f0f0>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_04d7d683c89ed1eee342fada40c8f0f0>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_4f1419e2d8401b30802d33acfe1bf4ba>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_4f1419e2d8401b30802d33acfe1bf4ba>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_dd54d5020bb45818d3c46f99d88f5eb9>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_dd54d5020bb45818d3c46f99d88f5eb9>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_a7a08e3b65ee29ccf94df15438adf68c>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_a7a08e3b65ee29ccf94df15438adf68c>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_abf7032eaa189b9f698d886d2904b846>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_abf7032eaa189b9f698d886d2904b846>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_c2a424e14c2edd53fc57c7203dbe439a>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_c2a424e14c2edd53fc57c7203dbe439a>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_fac5e5bdc579fe41c89535fa48591cf8>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_fac5e5bdc579fe41c89535fa48591cf8>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_d402ec5e3e8ae044bf151d80c0154775>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_d402ec5e3e8ae044bf151d80c0154775>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_4b66b3bf0624f37994651db0695d330d>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_4b66b3bf0624f37994651db0695d330d>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_699a4960df85c062f1de397d0f1d4d5f>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_699a4960df85c062f1de397d0f1d4d5f>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerBindings::__l2::<lambda_1ae4926139022560839bd3ed0289a6f4>`
```
struct __cppobj TradeScreenController::_registerBindings::__l2::<lambda_1ae4926139022560839bd3ed0289a6f4>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerEventHandlers::__l2::<lambda_6c8bd1e993a3e25879d9b6440d86063c>`
```
struct __cppobj TradeScreenController::_registerEventHandlers::__l2::<lambda_6c8bd1e993a3e25879d9b6440d86063c>
{
  TradeScreenController *const __this;
};

```

### `TradeScreenController::_registerEventHandlers::__l2::<lambda_71ace49e61e36dacd5f99a83ecca3396>`
```
struct __cppobj TradeScreenController::_registerEventHandlers::__l2::<lambda_71ace49e61e36dacd5f99a83ecca3396>
{
  TradeScreenController *const __this;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_3cff5947c5fccfa52c5c18e7aae2b158>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_3cff5947c5fccfa52c5c18e7aae2b158>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_0859de46715c65e095a472a49f11145d>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_0859de46715c65e095a472a49f11145d>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_0fcfca9bcfe8d7596cf4270a03217598>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_0fcfca9bcfe8d7596cf4270a03217598>
{
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_11c7b388e65e9ab0f8d7bb5e4371138f>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_11c7b388e65e9ab0f8d7bb5e4371138f>
{
  Trade2ScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_ddef2433dc2ec6668e6b0a29ef43b2ec>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_ddef2433dc2ec6668e6b0a29ef43b2ec>
{
  Trade2ScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerStateMachine::__l2::<lambda_f6edd9cdcf1ac886c3452133207b6792>`
```
struct __cppobj Trade2ScreenController::_registerStateMachine::__l2::<lambda_f6edd9cdcf1ac886c3452133207b6792>
{
  Trade2ScreenController *const __this;
  const unsigned int tradeTakeAllPlaceAllButtonId;
  const unsigned int tradeCoalesceButtonId;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_27daf06da30691f1ffb9d99a1545c039>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_27daf06da30691f1ffb9d99a1545c039>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_4d26e28b9520ea65977e598b0f1996fd>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_4d26e28b9520ea65977e598b0f1996fd>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_1af33ce7b49c9eff38941de7bed9f894>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_1af33ce7b49c9eff38941de7bed9f894>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_da75d75657d4257289b42a0c15ae54e2>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_da75d75657d4257289b42a0c15ae54e2>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_f7537fbd680c22f0e9ec9d8d4903437c>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_f7537fbd680c22f0e9ec9d8d4903437c>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_623d0568ad16b6169626fa482ffe6e2f>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_623d0568ad16b6169626fa482ffe6e2f>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_4ca8c413e00728b8ff006f1614bd46d9>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_4ca8c413e00728b8ff006f1614bd46d9>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_a5f1e3ee2cc99ffea8d4735ec1fa05cd>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_a5f1e3ee2cc99ffea8d4735ec1fa05cd>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_3bd43c6347383245985b77a9bf5f3d7c>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_3bd43c6347383245985b77a9bf5f3d7c>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_c95253e7a40bb7f2f23f009095fedbb9>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_c95253e7a40bb7f2f23f009095fedbb9>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_cc3254324fbdb2755269018c901fd9ea>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_cc3254324fbdb2755269018c901fd9ea>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_f6aa96f491f4fd952dc5b52dea944ae3>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_f6aa96f491f4fd952dc5b52dea944ae3>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_b0548137de0a09f8918daa544f8bd4a7>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_b0548137de0a09f8918daa544f8bd4a7>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_80d11c7f3622f1f109442ffe8de7001d>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_80d11c7f3622f1f109442ffe8de7001d>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_36b01c6d0b77ab28e3d515791e8c382c>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_36b01c6d0b77ab28e3d515791e8c382c>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_e8d97c641475d6dc940e0d2f6350f264>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_e8d97c641475d6dc940e0d2f6350f264>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_2bce45160e6fcdcefc780d28806e11e9>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_2bce45160e6fcdcefc780d28806e11e9>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_4a0b772b5173a9e46f7ba40bbed09f9e>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_4a0b772b5173a9e46f7ba40bbed09f9e>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_62549f0d4b7b7a53cf721617f04f86e6>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_62549f0d4b7b7a53cf721617f04f86e6>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_3becfc8367bdfcf4a492fb988f0670e4>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_3becfc8367bdfcf4a492fb988f0670e4>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_742552ae555e14ba2b273d096ffe6056>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_742552ae555e14ba2b273d096ffe6056>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_5d03bb0ff513f95a637c3f1dad67641b>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_5d03bb0ff513f95a637c3f1dad67641b>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_9efee4e9cb8415407f351488f103287c>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_9efee4e9cb8415407f351488f103287c>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_24bae11dda32b1a9672e85300fb7fe79>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_24bae11dda32b1a9672e85300fb7fe79>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_28879ddc2f0e928407f9d79486ad79f3>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_28879ddc2f0e928407f9d79486ad79f3>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_41f8dbe096bb6a7b92955b4925c77f00>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_41f8dbe096bb6a7b92955b4925c77f00>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_d80e30b960d2e834b166913b633e0e65>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_d80e30b960d2e834b166913b633e0e65>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_8631c8494c76f90c6f919c6fbf0a6520>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_8631c8494c76f90c6f919c6fbf0a6520>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_854643686d90f6822719419325daafea>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_854643686d90f6822719419325daafea>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_96b1aaa9a73bbdad452c083f874d01f2>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_96b1aaa9a73bbdad452c083f874d01f2>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_e03f396f5f5da85f7560a3db851dddee>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_e03f396f5f5da85f7560a3db851dddee>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_cf37cbc838b4cecf216aa7ff25b8ab6e>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_cf37cbc838b4cecf216aa7ff25b8ab6e>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_f16e4f6cc48e2bc598961e6ebdc0afeb>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_f16e4f6cc48e2bc598961e6ebdc0afeb>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_0d02b61409fe81e21f3fb9e40b67dbf6>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_0d02b61409fe81e21f3fb9e40b67dbf6>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_c86c3e6b07e44c3cb53c45314108b323>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_c86c3e6b07e44c3cb53c45314108b323>
{
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_4e5284f61caf94bda382c7087affea23>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_4e5284f61caf94bda382c7087affea23>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_354ea939ae3bf89830b3e57e2e7fd375>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_354ea939ae3bf89830b3e57e2e7fd375>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_daafbe468a2a13bfc1540b641da1b9a0>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_daafbe468a2a13bfc1540b641da1b9a0>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_d1bd151f848e7facf4db3312a7ebca39>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_d1bd151f848e7facf4db3312a7ebca39>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_55c8ddc36c90cf007ab25b954d4a61ac>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_55c8ddc36c90cf007ab25b954d4a61ac>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_499bc61ab1bc7050853aa4bb27b74bfa>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_499bc61ab1bc7050853aa4bb27b74bfa>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_622c953d4e1eda8813aa6a3bedb2b48c>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_622c953d4e1eda8813aa6a3bedb2b48c>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerBindings::__l2::<lambda_c6a3e4880bc1763b27bf9add744d3da2>`
```
struct __cppobj Trade2ScreenController::_registerBindings::__l2::<lambda_c6a3e4880bc1763b27bf9add744d3da2>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_b17a7f79a766645f61a68b1f5f93f20d>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_b17a7f79a766645f61a68b1f5f93f20d>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_07da5b6147732c03aa058ffd11b71bd7>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_07da5b6147732c03aa058ffd11b71bd7>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_597f8190a2bb85164dc89c327914a4e5>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_597f8190a2bb85164dc89c327914a4e5>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_a7fdc6534cac0af3aaca78f811422d49>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_a7fdc6534cac0af3aaca78f811422d49>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_9f13c2b8994bade05c9d76c0e3c4bb38>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_9f13c2b8994bade05c9d76c0e3c4bb38>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_fc9ba8b8b894340ccd23aeb5d610cbfe>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_fc9ba8b8b894340ccd23aeb5d610cbfe>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ec327119967ee3bd7f2c22082fcff333>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ec327119967ee3bd7f2c22082fcff333>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f54c9bde7e96ce7f1c65148edf337749>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f54c9bde7e96ce7f1c65148edf337749>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_9fe81177f1ba900def9370d55caa8cd7>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_9fe81177f1ba900def9370d55caa8cd7>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_29e66d3bf67e1001a1ee5e15f978a295>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_29e66d3bf67e1001a1ee5e15f978a295>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_58d940d279c71f171aac175cee7471a9>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_58d940d279c71f171aac175cee7471a9>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f5fedfb39f484ace110587b5cf396af5>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f5fedfb39f484ace110587b5cf396af5>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f5fedfb39f484ace110587b5cf396af5>::()::__l2::<lambda_17eeb1e2dadfd934f2b0012a6736be00>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_f5fedfb39f484ace110587b5cf396af5>::()::__l2::<lambda_17eeb1e2dadfd934f2b0012a6736be00>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>::()::__l10::<lambda_f58f30b027b8fbf347ca5a539fb7e06e>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>::()::__l10::<lambda_f58f30b027b8fbf347ca5a539fb7e06e>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>::()::__l5::<lambda_87d1bcc4b13d7466569aa65f582ecbde>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_ab54a4af05b5e13bd4028b2b368d49ba>::()::__l5::<lambda_87d1bcc4b13d7466569aa65f582ecbde>
{
  Trade2ScreenController *const __this;
};

```

### `Trade2ScreenController::_registerEventHandlers::__l2::<lambda_4cf1dfca89fdea9ef790a508b5e39fe0>`
```
struct __cppobj Trade2ScreenController::_registerEventHandlers::__l2::<lambda_4cf1dfca89fdea9ef790a508b5e39fe0>
{
  Trade2ScreenController *const __this;
};

```

### `TokenFAQScreenController::_registerBindings::__l2::<lambda_082199155bd4501f976e662b89b032d4>`
```
struct __cppobj TokenFAQScreenController::_registerBindings::__l2::<lambda_082199155bd4501f976e662b89b032d4>
{
  TokenFAQScreenController *const __this;
};

```

### `TokenFAQScreenController::_registerEventHandlers::__l2::<lambda_3c36029f8c1fb05802a2a422de42fe25>`
```
struct __cppobj TokenFAQScreenController::_registerEventHandlers::__l2::<lambda_3c36029f8c1fb05802a2a422de42fe25>
{
};

```

### `TokenFAQScreenController::_registerEventHandlers::__l2::<lambda_1cb97384a830859bd2b77273e2aea979>`
```
struct __cppobj TokenFAQScreenController::_registerEventHandlers::__l2::<lambda_1cb97384a830859bd2b77273e2aea979>
{
};

```

### `ToastScreenController::_registerEvents::__l2::<lambda_7fad33e1179f9bab071dd0455ff26826>`
```
struct __cppobj ToastScreenController::_registerEvents::__l2::<lambda_7fad33e1179f9bab071dd0455ff26826>
{
  ToastScreenController *const __this;
};

```

### `TemplateExportScreenController::_exportTemplate::__l5::<lambda_fcd8c83962c58ea5962f6362ee5c2a65>`
```
struct __cppobj TemplateExportScreenController::_exportTemplate::__l5::<lambda_fcd8c83962c58ea5962f6362ee5c2a65>
{
  std::shared_ptr<IWorldSettingsStorage> strongStorageInterface;
  bool *bIsLowDiskSpaceWarning;
};

```

### `TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_1a0848a57bb4642f0042cf53f74a768a>`
```
struct __cppobj TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_1a0848a57bb4642f0042cf53f74a768a>
{
  TemplateExportScreenController *const __this;
};

```

### `TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_1a2474f2f91d62a8e644e5c51cc76caa>`
```
struct __cppobj TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_1a2474f2f91d62a8e644e5c51cc76caa>
{
  TemplateExportScreenController *const __this;
};

```

### `TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_521b5d45fa0b701c0942f41085bcdef4>`
```
struct __cppobj TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_521b5d45fa0b701c0942f41085bcdef4>
{
  TemplateExportScreenController *const __this;
};

```

### `TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_ef01739a89ca42de25d18fb3573aa9f1>`
```
struct __cppobj TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_ef01739a89ca42de25d18fb3573aa9f1>
{
  TemplateExportScreenController *const __this;
};

```

### `TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_49a50320d75dfec90fe863675d39edca>`
```
struct __cppobj TemplateExportScreenController::_registerControllerCallbacks::__l2::<lambda_49a50320d75dfec90fe863675d39edca>
{
  TemplateExportScreenController *const __this;
};

```

### `TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_c450ac46cf957605fa0aafbaa46abb69>`
```
struct __cppobj TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_c450ac46cf957605fa0aafbaa46abb69>
{
  TabbedUpsellScreenController *const __this;
};

```

### `TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_c450ac46cf957605fa0aafbaa46abb69>::()::__l7::<lambda_ad29e818ddbc5f7c9c110d4f7e0f2d95>`
```
struct __cppobj TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_c450ac46cf957605fa0aafbaa46abb69>::()::__l7::<lambda_ad29e818ddbc5f7c9c110d4f7e0f2d95>
{
  TabbedUpsellScreenController *const __this;
};

```

### `TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_508c8f65e3532e6a45981118070c4728>`
```
struct __cppobj TabbedUpsellScreenController::_registerEventHandlers::__l2::<lambda_508c8f65e3532e6a45981118070c4728>
{
  TabbedUpsellScreenController *const __this;
};

```

### `TemplateExportScreenController::_pickTemplateLocalization::__l2::<lambda_1e5b6729761afe7e42ee4b26774be298>`
```
struct __cppobj TemplateExportScreenController::_pickTemplateLocalization::__l2::<lambda_1e5b6729761afe7e42ee4b26774be298>
{
  std::weak_ptr<TemplateExportScreenController> weakThis;
};

```

### `TemplateExportScreenController::_pickTemplateImage::__l2::<lambda_95e956f9c0e719a6eb64ab92ca969fed>`
```
struct __cppobj TemplateExportScreenController::_pickTemplateImage::__l2::<lambda_95e956f9c0e719a6eb64ab92ca969fed>
{
  std::weak_ptr<TemplateExportScreenController> weakThis;
};

```

### `TutorialScreenController::_registerSubControllers::__l2::<lambda_ecc634dc5b46d33cf16b73da7f3be7be>`
```
struct __cppobj TutorialScreenController::_registerSubControllers::__l2::<lambda_ecc634dc5b46d33cf16b73da7f3be7be>
{
  TutorialScreenController *const __this;
};

```

### `TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>::searchItemsByTreatment::__l2::<lambda_2053cde3a47e1f60660fcfa429ab404f>`
```
struct __cppobj TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument>::searchItemsByTreatment::__l2::<lambda_2053cde3a47e1f60660fcfa429ab404f>
{
  const SearchQuery query;
  const unsigned int queryId;
  std::weak_ptr<TreatmentQuery<DressingRoomManifestSearchResults,DressingRoomManifestDocument> > weakThis;
};

```

### `TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>::searchItemsByTreatment::__l2::<lambda_74657ca70e90569fb2a8b865f1f00164>`
```
struct __cppobj TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument>::searchItemsByTreatment::__l2::<lambda_74657ca70e90569fb2a8b865f1f00164>
{
  const SearchQuery query;
  const unsigned int queryId;
  std::weak_ptr<TreatmentQuery<QueryManifestSearchResults,QueryManifestDocument> > weakThis;
};

```

### `TouchPointResults`
```
struct __cppobj TouchPointResults
{
  std::vector<std::pair<TouchPoint,enum TouchEventResult>> _touchEventResults;
};

```

### `TouchControl`
```
struct __cppobj TouchControl
{
  TouchControl_vtbl *__vftable /*VFT*/;
  std::function<RectangleArea __cdecl(void)> mArea;
  int mScreenWidth;
  int mScreenHeight;
  std::string mCurrentLabel;
};

```

### `TouchControl_vtbl`
```
struct /*VFT*/ TouchControl_vtbl
{
  void (__fastcall *~TouchControl)(TouchControl *this);
  void (__fastcall *render)(TouchControl *this, InputRenderContext *);
  void (__fastcall *tick)(TouchControl *this, InputEventQueue *, TouchPointResults *, int);
  void (__fastcall *release)(TouchControl *this, InputEventQueue *);
};

```

### `TouchTurnInteractControl`
```
struct __cppobj TouchTurnInteractControl : TouchControl
{
  std::function<bool __cdecl(void)> mCondition;
  std::function<std::vector<RectangleArea> __cdecl(void)> mGetInactiveAreasCallback;
  const unsigned int mTurnInteractButtonId;
  const unsigned int mTapButtonId;
  const unsigned int mHoldButtonId;
  float mSensitivity;
  float mHoldSensitivity;
  bool mPersistData;
  TouchTurnState mState;
  int mActiveTurnPointerId;
  long double mStartTurnTime;
  float mTotalMoveDelta;
  bool mHoldGesture;
  float mX0;
  float mY0;
};

```

### `TouchTurnInteractControl_vtbl`
```
struct /*VFT*/ TouchTurnInteractControl_vtbl
{
  void (__fastcall *~TouchControl)(TouchControl *this);
  void (__fastcall *render)(TouchControl *this, InputRenderContext *);
  void (__fastcall *tick)(TouchControl *this, InputEventQueue *, TouchPointResults *, int);
  void (__fastcall *release)(TouchControl *this, InputEventQueue *);
};

```

### `TouchControlSet`
```
struct __cppobj TouchControlSet
{
  bool mTempState;
  TouchPointResults mTouchPointResults;
  std::vector<std::unique_ptr<TouchControl>> mControls;
  TouchTurnInteractControl *mTurnInteractControl;
  int mScreenWidth;
  int mScreenHeight;
  bool mWasHoldingGesture;
  TouchTurnState mPrevState;
};

```

### `TouchMapper`
```
struct __cppobj __declspec(align(8)) TouchMapper : InputDeviceMapper
{
  std::unique_ptr<TouchControlSet> mTouchControlSet;
  int mLastCursorX;
  int mLastCursorY;
  bool mPressed;
  int mYAxisInversionFactor;
  std::vector<std::pair<int,int>> touchIdsWithFlags;
  std::function<std::vector<RectangleArea> __cdecl(void)> mAreaFunc;
  int mPrimaryGameControllerId;
};

```

### `TouchMapper_vtbl`
```
struct /*VFT*/ TouchMapper_vtbl
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

### `TridentModel`
```
struct __cppobj TridentModel : Model
{
  mce::MaterialPtr mGlintMaterial;
  mce::MaterialPtr mDefaultMaterial;
  ModelPart mPole;
  ModelPart mRDent;
};

```

### `TridentModel_vtbl`
```
struct /*VFT*/ TridentModel_vtbl
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

### `TempEPtr<Player>`
```
struct __cppobj __declspec(align(8)) TempEPtr<Player> : _TickPtr
{
  Player *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<Player>_vtbl`
```
struct /*VFT*/ TempEPtr<Player>_vtbl
{
  void (__fastcall *invalidate)(_TickPtr *this);
  void (__fastcall *~_TickPtr)(_TickPtr *this);
};

```

### `TripodCamera`
```
struct __cppobj TripodCamera : Mob
{
  TempEPtr<Player> mPlayer;
  bool mActivated;
  int mCountdown;
};

```

### `TripodCameraModel`
```
struct __cppobj TripodCameraModel : Model
{
};

```

### `TripodCameraModel_vtbl`
```
struct /*VFT*/ TripodCameraModel_vtbl
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

### `TakeAnimationParticle`
```
struct __cppobj __declspec(align(8)) TakeAnimationParticle : CustomParticle
{
  Level *mLevel;
  std::unique_ptr<Actor> mItemActor;
  ActorUniqueID mTargetEntityId;
  Vec3 mOffset;
  int mLife;
  int mLifeTime;
};

```

### `TakeAnimationParticle_vtbl`
```
struct /*VFT*/ TakeAnimationParticle_vtbl
{
  void (__fastcall *~CustomParticle)(CustomParticle *this);
  void (__fastcall *normalTick)(CustomParticle *this);
  void (__fastcall *render)(CustomParticle *this, BaseActorRenderContext *, const Vec3 *, float);
  bool (__fastcall *isRemoved)(CustomParticle *this);
};

```

### `TerrainParticle`
```
struct __cppobj TerrainParticle : Particle
{
  const BlockGraphics *mBlock;
  TextureUVCoordinateSet _terrainTex;
};

```

### `TerrainParticle_vtbl`
```
struct /*VFT*/ TerrainParticle_vtbl
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

### `TotemParticle`
```
struct __cppobj __declspec(align(8)) TotemParticle : Particle
{
  int baseTex;
};

```

### `TotemParticle_vtbl`
```
struct /*VFT*/ TotemParticle_vtbl
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

### `TrackingEmitter`
```
struct __cppobj __declspec(align(8)) TrackingEmitter : Particle
{
  ActorUniqueID mEntityID;
  ParticleType mEmittedType;
};

```

### `TrackingEmitter_vtbl`
```
struct /*VFT*/ TrackingEmitter_vtbl
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

### `TextObjectLocalizedText`
```
struct __cppobj TextObjectLocalizedText : ITextObject
{
  std::string mText;
};

```

### `TextObjectLocalizedText_vtbl`
```
struct /*VFT*/ TextObjectLocalizedText_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TntRenderer`
```
struct __cppobj TntRenderer : ActorRenderer
{
  BlockTessellator *mBlockTessellator;
};

```

### `TntRenderer_vtbl`
```
struct /*VFT*/ TntRenderer_vtbl
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

### `ThrownTridentRenderer`
```
struct __cppobj ThrownTridentRenderer : ActorRenderer
{
  mce::TexturePtr mTridentTex;
  mce::TexturePtr mLoyaltyRopeTex;
  mce::TexturePtr mGlintTexture;
  mce::MaterialPtr mLeashMaterial;
  TridentModel mTridentModel;
};

```

### `ThrownTridentRenderer_vtbl`
```
struct /*VFT*/ ThrownTridentRenderer_vtbl
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

### `ThrownTridentRenderer::LeashStepValues`
```
struct __cppobj ThrownTridentRenderer::LeashStepValues
{
  float uVal;
  float ringScale;
  Vec3 v;
};

```

### `ThrownTrident`
```
struct __cppobj ThrownTrident : AbstractArrow
{
  bool mDealtDamage;
  int mClientSideReturnTridentTickCount;
  ItemStack mTrident;
};

```

### `ThrownTrident_vtbl`
```
struct /*VFT*/ ThrownTrident_vtbl
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

### `TridentItem`
```
struct __cppobj TridentItem : Item
{
};

```

### `ThrownPotionEffectSubcomponent`
```
struct __cppobj ThrownPotionEffectSubcomponent : SplashPotionEffectSubcomponent
{
};

```

### `ThrownPotionEffectSubcomponent_vtbl`
```
struct /*VFT*/ ThrownPotionEffectSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `TeleportToSubcomponent`
```
struct __cppobj TeleportToSubcomponent : OnHitSubcomponent
{
};

```

### `TeleportToSubcomponent_vtbl`
```
struct /*VFT*/ TeleportToSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `TripodCameraRenderer`
```
struct __cppobj TripodCameraRenderer : MobRenderer
{
  BaseActorRenderContext *mCachedRenderContext;
};

```

### `TripodCameraRenderer_vtbl`
```
struct /*VFT*/ TripodCameraRenderer_vtbl
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

### `TopSnowBlock`
```
struct __cppobj TopSnowBlock : HeavyBlock
{
};

```

### `TopSnowBlock_vtbl`
```
struct /*VFT*/ TopSnowBlock_vtbl
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

### `TripWireBlock`
```
struct __cppobj TripWireBlock : BlockLegacy
{
};

```

### `TripWireBlock_vtbl`
```
struct /*VFT*/ TripWireBlock_vtbl
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

### `Throwable`
```
struct __cppobj Throwable : PredictableProjectile
{
  bool mInGround;
  ActorUniqueID mOwnerId;
  int mShakeTime;
  int mLife;
  MovementInterpolator mInterpolation;
};

```

### `Throwable_vtbl`
```
struct /*VFT*/ Throwable_vtbl
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
  float (__fastcall *getThrowPower)(Throwable *this);
  bool (__fastcall *stopUponGroundCollision)(Throwable *this);
  float (__fastcall *getThrowUpAngleOffset)(Throwable *this);
  float (__fastcall *getGravity)(Throwable *this);
  ParticleType (__fastcall *getParticleType)(Throwable *this);
  void (__fastcall *onHit)(Throwable *this, const HitResult *);
};

```

### `ThrownPotion`
```
struct __cppobj ThrownPotion : Throwable
{
};

```

### `ThrownPotion_vtbl`
```
struct /*VFT*/ ThrownPotion_vtbl
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
  float (__fastcall *getThrowPower)(Throwable *this);
  bool (__fastcall *stopUponGroundCollision)(Throwable *this);
  float (__fastcall *getThrowUpAngleOffset)(Throwable *this);
  float (__fastcall *getGravity)(Throwable *this);
  ParticleType (__fastcall *getParticleType)(Throwable *this);
  void (__fastcall *onHit)(Throwable *this, const HitResult *);
};

```

### `TickingTextureMergeStrategy`
```
struct __cppobj TickingTextureMergeStrategy : JsonMergeStrategy
{
};

```

### `TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper_vtbl`
```
struct /*VFT*/ TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper_vtbl
{
  void (__fastcall *~TextureSetDefinitionLoaderResourceHelper)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this);
  ResourceLocation *(__fastcall *getBackCompatResourceLocation)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, ResourceLocation *result, const ResourceLocation *);
  std::optional<unsigned int> *(__fastcall *getPackStackIndexOfNoExtensionOrImage)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, std::optional<unsigned int> *result, const ResourceLocation *);
  std::optional<unsigned int> *(__fastcall *getPackStackIndexOfTextureSet)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, std::optional<unsigned int> *result, const ResourceLocation *);
  bool (__fastcall *loadResourceOfExtensions)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, const ResourceLocationPair *, std::string *, const std::vector<std::string> *);
  bool (__fastcall *loadResource)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, const ResourceLocation *, std::string *);
  bool (__fastcall *loadImageFromMemory)(TextureSetHelpers::TextureSetDefinitionLoaderResourceHelper *this, mce::Image *, const std::string *);
};

```

### `TintUtility`
```
struct __cppobj TintUtility
{
};

```

### `TextureSetHelpers::TextureSetDefinitionLoader`
```
struct __cppobj TextureSetHelpers::TextureSetDefinitionLoader
{
};

```

### `TreatmentImportContext`
```
struct __cppobj TreatmentImportContext : DlcImportContext
{
};

```

### `TreatmentImportContext_vtbl`
```
struct /*VFT*/ TreatmentImportContext_vtbl
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

### `TreatmentPackDownloadMonitor::<lambda_11b0ab540ec12b654d1e347be12eeb41>`
```
struct __cppobj TreatmentPackDownloadMonitor::<lambda_11b0ab540ec12b654d1e347be12eeb41>
{
};

```

### `TreatmentPackDownloadMonitor::<lambda_968ac4c03d74b8f72ff13ce46bb939e4>`
```
struct __cppobj TreatmentPackDownloadMonitor::<lambda_968ac4c03d74b8f72ff13ce46bb939e4>
{
};

```

### `TreatmentPackDownloadMonitor::buildTreatmentStackPack::__l5::<lambda_03176697d2469a0171370ce670549ba9>`
```
struct __cppobj TreatmentPackDownloadMonitor::buildTreatmentStackPack::__l5::<lambda_03176697d2469a0171370ce670549ba9>
{
  const TreatmentPackDownloadMonitor *const __this;
  std::vector<std::pair<int,gsl::not_null<ResourcePack *> >> *packPriorityList;
};

```

### `TreatmentPackDownloadMonitor::_reloadResourcePacks::__l8::<lambda_07f1a422e66ec4b03a68c646fe5a6eac>`
```
struct __cppobj TreatmentPackDownloadMonitor::_reloadResourcePacks::__l8::<lambda_07f1a422e66ec4b03a68c646fe5a6eac>
{
  TreatmentPackDownloadMonitor *const __this;
};

```

### `TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_dc82c2ec49616997cbf6d2ea6c2a555b>`
```
struct __cppobj TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_dc82c2ec49616997cbf6d2ea6c2a555b>
{
  TreatmentPackDownloadMonitor *const __this;
};

```

### `TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_46bff75d05826f81abd18050c2edb30e>`
```
struct __cppobj TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_46bff75d05826f81abd18050c2edb30e>
{
  TreatmentPackDownloadMonitor *const __this;
};

```

### `TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_6079e2357570a150807bd79962c485e4>`
```
struct __cppobj TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_6079e2357570a150807bd79962c485e4>
{
  TreatmentPackDownloadMonitor *const __this;
};

```

### `TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_b4fad2d91cfc8ea1ac0e43795b16d409>`
```
struct __cppobj TreatmentPackDownloadMonitor::{ctor}::__l2::<lambda_b4fad2d91cfc8ea1ac0e43795b16d409>
{
  TreatmentPackDownloadMonitor *const __this;
};

```

### `ToastManager::_handleInvite::__l5::<lambda_be8ef6bf14fe2ef69752d727485c0566>`
```
struct __cppobj __declspec(align(8)) ToastManager::_handleInvite::__l5::<lambda_be8ef6bf14fe2ef69752d727485c0566>
{
  ToastManager *const __this;
  std::string inviteHandle;
  bool parseJSON;
};

```

### `TreatmentQuery<SalesSearchResults,SalesDocument>::searchItemsByTreatment::__l2::<lambda_8757d1f732ec4068f98416135156cf8b>`
```
struct __cppobj TreatmentQuery<SalesSearchResults,SalesDocument>::searchItemsByTreatment::__l2::<lambda_8757d1f732ec4068f98416135156cf8b>
{
  const SearchQuery query;
  const unsigned int queryId;
  std::weak_ptr<TreatmentQuery<SalesSearchResults,SalesDocument> > weakThis;
};

```

### `TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>::searchItemsByTreatment::__l2::<lambda_fe2ae65f295b768da534bca0cd8722d3>`
```
struct __cppobj TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument>::searchItemsByTreatment::__l2::<lambda_fe2ae65f295b768da534bca0cd8722d3>
{
  const SearchQuery query;
  const unsigned int queryId;
  std::weak_ptr<TreatmentQuery<StoreConfigSearchResults,StoreConfigDocument> > weakThis;
};

```

### `ToastFetcher::_processQueryResults::__l9::<lambda_3565c02a5e85af80fee79c4821279aa8>`
```
struct __cppobj ToastFetcher::_processQueryResults::__l9::<lambda_3565c02a5e85af80fee79c4821279aa8>
{
  std::weak_ptr<ToastFetcher> weakThis;
};

```

### `ToastFetcher::fetchToasts::__l13::<lambda_f39813a64b5c35570ffc19ea92d119eb>`
```
struct __cppobj ToastFetcher::fetchToasts::__l13::<lambda_f39813a64b5c35570ffc19ea92d119eb>
{
  std::weak_ptr<ToastFetcher> weakThis;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l13::<lambda_274358272b052b523fb6b4484b0412ed>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l13::<lambda_274358272b052b523fb6b4484b0412ed>
{
  ThirdPartyServerRepository *const __this;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l65::<lambda_fbd43098a301c6270095fa7129b2afd1>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l65::<lambda_fbd43098a301c6270095fa7129b2afd1>
{
  std::string productId;
  ThirdPartyServerRepository::_processSearchResponse::__l13::<lambda_274358272b052b523fb6b4484b0412ed> availableGameCallback;
  std::string title;
  std::string subtitle;
  std::string description;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l51::<lambda_a4b4eabb5a9f80d9316701fd00838363>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l51::<lambda_a4b4eabb5a9f80d9316701fd00838363>
{
  ThirdPartyServerRepository *const __this;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l51::<lambda_d39ea53fd1214ce41a09711894826854>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l51::<lambda_d39ea53fd1214ce41a09711894826854>
{
  std::string productId;
  ThirdPartyServerRepository::_processSearchResponse::__l51::<lambda_a4b4eabb5a9f80d9316701fd00838363> screenshotsCallback;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l34::<lambda_f0ccdb8e0f9b5d02c003e62b10e068f0>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l34::<lambda_f0ccdb8e0f9b5d02c003e62b10e068f0>
{
  std::string productId;
  std::vector<std::function<void __cdecl(std::string const &,Core::Path const &)>> imageCallbacks;
};

```

### `ThirdPartyServerRepository::_processSearchResponse::__l34::<lambda_fb1cefaaa589df41e8c44fc3cc4d02c0>`
```
struct __cppobj ThirdPartyServerRepository::_processSearchResponse::__l34::<lambda_fb1cefaaa589df41e8c44fc3cc4d02c0>
{
  ThirdPartyServerRepository *const __this;
};

```

### `ThirdPartyServerRepository::fetch::__l2::<lambda_a181bd517d633d5f8b7e81d46df5ac6a>`
```
struct __cppobj ThirdPartyServerRepository::fetch::__l2::<lambda_a181bd517d633d5f8b7e81d46df5ac6a>
{
  ThirdPartyServerRepository *const __this;
};

```

### `TTSOutputInterface`
```
struct __cppobj TTSOutputInterface
{
  TTSOutputInterface_vtbl *__vftable /*VFT*/;
};

```

### `TTSOutputInterface_vtbl`
```
struct /*VFT*/ TTSOutputInterface_vtbl
{
  void (__fastcall *~TTSOutputInterface)(TTSOutputInterface *this);
  void (__fastcall *synthesizeAndOutput)(TTSOutputInterface *this, const std::string *, cst_voice_struct *);
  void (__fastcall *stop)(TTSOutputInterface *this);
  bool (__fastcall *isIdle)(TTSOutputInterface *this);
};

```

### `TextToSpeechClientCommon`
```
struct __cppobj __declspec(align(8)) TextToSpeechClientCommon : TextToSpeechClient
{
  bool mTextToSpeechEnabled;
};

```

### `TextToSpeechClientCommon_vtbl`
```
struct /*VFT*/ TextToSpeechClientCommon_vtbl
{
  void (__fastcall *~TextToSpeechClient)(TextToSpeechClient *this);
  void (__fastcall *setTextToSpeechEnabled)(TextToSpeechClient *this, bool);
  bool (__fastcall *getTextToSpeechEnabled)(TextToSpeechClient *this);
  void (__fastcall *speakText)(TextToSpeechClient *this, const std::string *);
  void (__fastcall *stopSpeaking)(TextToSpeechClient *this);
  bool (__fastcall *isIdle)(TextToSpeechClient *this);
  void (__fastcall *_setTextToSpeechEnabled)(TextToSpeechClientCommon *this, bool);
};

```

### `TextToSpeechClient_flite`
```
struct __cppobj TextToSpeechClient_flite : TextToSpeechClientCommon, std::enable_shared_from_this<TextToSpeechClient_flite>
{
  cst_voice_struct *mCurrentVoice;
  std::unique_ptr<TTSOutputInterface> mOutputInterface;
  std::unique_ptr<TaskGroup> mTaskGroup;
};

```

### `TextToSpeechClient_flite_vtbl`
```
struct /*VFT*/ TextToSpeechClient_flite_vtbl
{
  void (__fastcall *~TextToSpeechClient)(TextToSpeechClient *this);
  void (__fastcall *setTextToSpeechEnabled)(TextToSpeechClient *this, bool);
  bool (__fastcall *getTextToSpeechEnabled)(TextToSpeechClient *this);
  void (__fastcall *speakText)(TextToSpeechClient *this, const std::string *);
  void (__fastcall *stopSpeaking)(TextToSpeechClient *this);
  bool (__fastcall *isIdle)(TextToSpeechClient *this);
  void (__fastcall *_setTextToSpeechEnabled)(TextToSpeechClientCommon *this, bool);
};

```

### `TextToSpeechSystem_flite`
```
struct __cppobj TextToSpeechSystem_flite : TextToSpeechSystem
{
  Bedrock::NonOwnerPointer<SoundEngine> mSoundEngine;
};

```

### `TextToSpeechSystem_flite_vtbl`
```
struct /*VFT*/ TextToSpeechSystem_flite_vtbl
{
  void (__fastcall *~TextToSpeechSystem)(TextToSpeechSystem *this);
  bool (__fastcall *checkPlatformTTSEnabled)(TextToSpeechSystem *this, gsl::not_null<Options *>);
  bool (__fastcall *canAutoEnableTTS)(TextToSpeechSystem *this, gsl::not_null<Options const *>);
  TTSEnabledStatus (__fastcall *getTTSEnabledStatus)(TextToSpeechSystem *this);
  void (__fastcall *setTTSEnabledStatus)(TextToSpeechSystem *this, TTSEnabledStatus);
  bool (__fastcall *supportsMultipleTTSClients)(TextToSpeechSystem *this);
  std::shared_ptr<TextToSpeechClient> *(__fastcall *_createTTSClient)(TextToSpeechSystem *this, std::shared_ptr<TextToSpeechClient> *result);
};

```

### `TextRange`
```
struct __cppobj TextRange
{
  int mStartCaretPos;
  int mEndCaretPos;
};

```

### `TextEditContext`
```
struct __cppobj __declspec(align(8)) TextEditContext
{
  bool mIsEnabled;
  std::string mCurrentUtf8Text;
  int mCaret;
  bool mHighlightSelection;
  int mMaxLength;
  TextRange mSelection;
};

```

### `tagBLOB`
```
struct tagBLOB
{
  unsigned int cbSize;
  unsigned __int8 *pBlobData;
};

```

### `typeid_t<IDefinitionInstance>`
```
struct __cppobj typeid_t<IDefinitionInstance>
{
  unsigned __int16 mID;
};

```

### `tickInsideBlockNotifierComponent::__l2::<lambda_16a9f65802bfd7dcaf3f9bd8f1d04263>`
```
struct __cppobj tickInsideBlockNotifierComponent::__l2::<lambda_16a9f65802bfd7dcaf3f9bd8f1d04263>
{
  InsideBlockNotifierComponent *insideComp;
};

```

### `TaskGroupProxy`
```
struct __cppobj TaskGroupProxy : ITaskGroupProxy
{
  std::unique_ptr<TaskGroup> mTaskGroup;
};

```

### `TaskGroupProxy_vtbl`
```
struct /*VFT*/ TaskGroupProxy_vtbl
{
  void (__fastcall *~ITaskGroupProxy)(ITaskGroupProxy *this);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *queue)(ITaskGroupProxy *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, TaskStartInfoEx<void>, std::function<TaskResult __cdecl(void)>, std::function<void __cdecl(void)>);
  void (__fastcall *flush)(ITaskGroupProxy *this);
};

```

### `TickingAreaView`
```
struct __cppobj __declspec(align(8)) TickingAreaView : ITickingAreaView
{
  std::shared_ptr<ChunkViewSource> mTickingArea;
  bool mDoneLoading;
};

```

### `TickingAreaView_vtbl`
```
struct /*VFT*/ TickingAreaView_vtbl
{
  void (__fastcall *~ITickingAreaView)(ITickingAreaView *this);
  void (__fastcall *init)(ITickingAreaView *this, const Bounds *, bool);
  void (__fastcall *tick)(ITickingAreaView *this, const Tick *, BlockSource *, bool);
  void (__fastcall *tickSeasons)(ITickingAreaView *this, BlockSource *, Random *);
  AutomaticID<Dimension,int> *(__fastcall *getDimensionId)(ITickingAreaView *this, AutomaticID<Dimension,int> *result);
  const Bounds *(__fastcall *getBounds)(ITickingAreaView *this);
  bool (__fastcall *isCircle)(ITickingAreaView *this);
  bool (__fastcall *isDoneLoading)(ITickingAreaView *this);
  bool (__fastcall *checkInitialLoadDone)(ITickingAreaView *this);
  float (__fastcall *getInitialLoadPercentage)(ITickingAreaView *this);
  void (__fastcall *move)(ITickingAreaView *this, const Bounds *);
  std::unique_ptr<ChunkViewSource> *(__fastcall *createChildSource)(ITickingAreaView *this, std::unique_ptr<ChunkViewSource> *result);
  std::shared_ptr<LevelChunk> *(__fastcall *getAvailableChunk)(ITickingAreaView *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *);
};

```

### `TickingArea`
```
struct __cppobj TickingArea : ITickingArea
{
  mce::UUID mUID;
  std::string mName;
  ActorUniqueID mEntityId;
  float mMaxDistToPlayers;
  bool mAlwaysActive;
  bool mEntityFound;
  bool mSizeChanged;
  bool mRemoved;
  Vec3 mLastChunkUpdatePos;
  Vec3 mLastPos;
  unsigned int mLastRadius;
  ChunkViewSource mChunkSource;
  BlockSource mBlockSource;
  TickingAreaView mView;
};

```

### `TickingArea_vtbl`
```
struct /*VFT*/ TickingArea_vtbl
{
  void (__fastcall *~ITickingArea)(ITickingArea *this);
  const mce::UUID *(__fastcall *getId)(ITickingArea *this);
  const std::string *(__fastcall *getName)(ITickingArea *this);
  const ActorUniqueID *(__fastcall *getEntityId)(ITickingArea *this);
  bool (__fastcall *isEntityOwned)(ITickingArea *this);
  BlockSource *(__fastcall *getBlockSource)(ITickingArea *this);
  bool (__fastcall *isAlwaysActive)(ITickingArea *this);
  float (__fastcall *getMaxDistToPlayers)(ITickingArea *this);
  ITickingAreaView *(__fastcall *getView)(ITickingArea *this);
  const ITickingAreaView *(__fastcall *getView)(ITickingArea *this);
  TickingAreaDescription *(__fastcall *getDescription)(ITickingArea *this, TickingAreaDescription *result);
  void (__fastcall *tick)(ITickingArea *this, const Tick *, bool);
  void (__fastcall *tickSeasons)(ITickingArea *this, Random *);
  void (__fastcall *updatePosition)(ITickingArea *this, const Vec3 *);
  void (__fastcall *center)(ITickingArea *this);
  Actor *(__fastcall *findOwner)(ITickingArea *this, unsigned __int8 *);
  bool (__fastcall *entityHasBeenFound)(ITickingArea *this);
  void (__fastcall *setEntityFound)(ITickingArea *this);
  bool (__fastcall *isRemoved)(ITickingArea *this);
  void (__fastcall *remove)(ITickingArea *this);
  void (__fastcall *onComponentChanged)(ITickingArea *this, unsigned int, float, bool);
};

```

### `TextObjectScore`
```
struct __cppobj TextObjectScore : ITextObject
{
  std::string mName;
  std::string mObjective;
};

```

### `TextObjectScore_vtbl`
```
struct /*VFT*/ TextObjectScore_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TextObjectSelector`
```
struct __cppobj TextObjectSelector : ITextObject
{
  std::string mSelectorString;
};

```

### `TextObjectSelector_vtbl`
```
struct /*VFT*/ TextObjectSelector_vtbl
{
  void (__fastcall *~ITextObject)(ITextObject *this);
  std::string *(__fastcall *asString)(ITextObject *this, std::string *result);
  Json::Value *(__fastcall *asJsonValue)(ITextObject *this, Json::Value *result);
  Json::Value *(__fastcall *resolve)(ITextObject *this, Json::Value *result, const ResolveData *);
};

```

### `TextureSetHelpers::TextureSetDefinitionParser`
```
struct __cppobj TextureSetHelpers::TextureSetDefinitionParser
{
};

```

### `TextureSetHelpers::TextureSetLayerDefinitionParser`
```
struct __cppobj TextureSetHelpers::TextureSetLayerDefinitionParser
{
};

```

### `TextureSetHelpers::TextureSetDefinitionParser::buildTextureSetFileSchema_v1_16_100::__l2::<lambda_ba176efafbeb69da9abbe64bb3b94336>`
```
struct __cppobj TextureSetHelpers::TextureSetDefinitionParser::buildTextureSetFileSchema_v1_16_100::__l2::<lambda_ba176efafbeb69da9abbe64bb3b94336>
{
};

```

### `TextureSetHelpers::TextureSetLayerDefinitionParser::_schemaAddChildColor::__l2::<lambda_f21c9cffa1980c564d8709d5f7f6833b>`
```
struct __cppobj TextureSetHelpers::TextureSetLayerDefinitionParser::_schemaAddChildColor::__l2::<lambda_f21c9cffa1980c564d8709d5f7f6833b>
{
  const cg::TextureSetLayerType type;
};

```

### `TextureSetHelpers::TextureSetLayerDefinitionParser::_schemaAddChildResourceLocation::__l2::<lambda_be310702578af5dafadccf2dd4c90de5>`
```
struct __cppobj TextureSetHelpers::TextureSetLayerDefinitionParser::_schemaAddChildResourceLocation::__l2::<lambda_be310702578af5dafadccf2dd4c90de5>
{
  const cg::TextureSetLayerType type;
};

```

### `TickingQueue::Stage`
```
struct __cppobj __declspec(align(8)) TickingQueue::Stage
{
  TickingQueue::Stage_vtbl *__vftable /*VFT*/;
  bool mInitRan;
};

```

### `TickingQueue::Stage_vtbl`
```
struct /*VFT*/ TickingQueue::Stage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue::OneshotStage`
```
struct __cppobj TickingQueue::OneshotStage : TickingQueue::Stage
{
  std::function<void __cdecl(void)> mInitFn;
};

```

### `TickingQueue::OneshotStage_vtbl`
```
struct /*VFT*/ TickingQueue::OneshotStage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue::PollingStage`
```
struct __cppobj TickingQueue::PollingStage : TickingQueue::Stage
{
  std::function<void __cdecl(void)> mInitFn;
  std::function<bool __cdecl(void)> mTickFn;
};

```

### `TickingQueue::PollingStage_vtbl`
```
struct /*VFT*/ TickingQueue::PollingStage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue::WaitForCallbackStage`
```
struct __cppobj __declspec(align(8)) TickingQueue::WaitForCallbackStage : TickingQueue::Stage
{
  std::function<void __cdecl(std::function<void __cdecl(void)>)> mInitFn;
  Signal mSignal;
};

```

### `TickingQueue::WaitForCallbackStage_vtbl`
```
struct /*VFT*/ TickingQueue::WaitForCallbackStage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue::WaitForSignalStage`
```
struct __cppobj TickingQueue::WaitForSignalStage : TickingQueue::Stage
{
  Signal *mSignal;
};

```

### `TickingQueue::WaitForSignalStage_vtbl`
```
struct /*VFT*/ TickingQueue::WaitForSignalStage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue::SleepStage`
```
struct __cppobj TickingQueue::SleepStage : TickingQueue::Stage
{
  BasicTimer mBasicTimer;
};

```

### `TickingQueue::SleepStage_vtbl`
```
struct /*VFT*/ TickingQueue::SleepStage_vtbl
{
  void (__fastcall *~Stage)(TickingQueue::Stage *this);
  void (__fastcall *init)(TickingQueue::Stage *this);
  bool (__fastcall *tick)(TickingQueue::Stage *this);
};

```

### `TickingQueue`
```
struct __cppobj __declspec(align(8)) TickingQueue
{
  std::vector<std::unique_ptr<TickingQueue::Stage>> mStages;
  unsigned int mCurrentStage;
};

```

### `TeleportResponse`
```
struct __cppobj __declspec(align(4)) TeleportResponse : EventResponse
{
  _BYTE mTarget[2];
  Vec3 mMaxRange;
  Vec3 mDestination;
  bool mAvoidWater;
  bool mLandOnBlock;
};

```

### `TeleportResponse_vtbl`
```
struct /*VFT*/ TeleportResponse_vtbl
{
  void (__fastcall *~EventResponse)(EventResponse *this);
  const std::string *(__fastcall *getName)(EventResponse *this);
  void (__fastcall *executeAction)(EventResponse *this, RenderParams *);
  void (__fastcall *buildSchema)(EventResponse *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,EventResponseCollection> > *, const Factory<EventResponse> *);
};

```

### `TransformItemResponse`
```
struct __cppobj TransformItemResponse : EventResponse
{
  std::string mTransformInto;
};

```

### `TransformItemResponse_vtbl`
```
struct /*VFT*/ TransformItemResponse_vtbl
{
  void (__fastcall *~EventResponse)(EventResponse *this);
  const std::string *(__fastcall *getName)(EventResponse *this);
  void (__fastcall *executeAction)(EventResponse *this, RenderParams *);
  void (__fastcall *buildSchema)(EventResponse *this, std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,EventResponseCollection> > *, const Factory<EventResponse> *);
};

```

### `TwistingVinesBlock`
```
struct __cppobj TwistingVinesBlock : BlockLegacy
{
};

```

### `TwistingVinesBlock_vtbl`
```
struct /*VFT*/ TwistingVinesBlock_vtbl
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

### `TestAction`
```
struct __cppobj TestAction : IChunkLoadedAction
{
  std::string mName;
  std::string *mExecuteString;
};

```

### `TestAction_vtbl`
```
struct /*VFT*/ TestAction_vtbl
{
  void (__fastcall *~IChunkLoadedAction)(IChunkLoadedAction *this);
  void (__fastcall *execute)(IChunkLoadedAction *this, ServerLevel *, Dimension *);
  void (__fastcall *serialize)(IChunkLoadedAction *this, CompoundTag *);
};

```

### `TraderMaterialTypeFunction`
```
struct __cppobj TraderMaterialTypeFunction : LootItemFunction
{
};

```

### `TraderMaterialTypeFunction_vtbl`
```
struct /*VFT*/ TraderMaterialTypeFunction_vtbl
{
  void (__fastcall *~LootItemFunction)(LootItemFunction *this);
  int (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, LootTableContext *);
  int (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, LootTableContext *);
};

```

### `TeleportResponse::buildSchema::__l2::<lambda_11e4e64adc008f5c5be71b7d17a0b5dc>`
```
struct __cppobj TeleportResponse::buildSchema::__l2::<lambda_11e4e64adc008f5c5be71b7d17a0b5dc>
{
};

```

### `TeleportResponse::buildSchema::__l2::<lambda_5fdf0e72c5a54d90d50e44b92130908f>`
```
struct __cppobj TeleportResponse::buildSchema::__l2::<lambda_5fdf0e72c5a54d90d50e44b92130908f>
{
};

```

### `TeleportResponse::buildSchema::__l2::<lambda_95e3e7e9b97b99564d60799ea311ee30>`
```
struct __cppobj TeleportResponse::buildSchema::__l2::<lambda_95e3e7e9b97b99564d60799ea311ee30>
{
};

```

### `TeleportResponse::buildSchema::__l2::<lambda_61f633edee585cb33c44d5c6f5f0c21c>`
```
struct __cppobj TeleportResponse::buildSchema::__l2::<lambda_61f633edee585cb33c44d5c6f5f0c21c>
{
};

```

### `TeleportResponse::buildSchema::__l2::<lambda_b1fb5a85632ac928fb01f025559d07ad>`
```
struct __cppobj TeleportResponse::buildSchema::__l2::<lambda_b1fb5a85632ac928fb01f025559d07ad>
{
  const Factory<EventResponse> *factory;
};

```

### `TransformItemResponse::buildSchema::__l2::<lambda_b8a0a2acc8ce29258ac9752e3c786ea9>`
```
struct __cppobj TransformItemResponse::buildSchema::__l2::<lambda_b8a0a2acc8ce29258ac9752e3c786ea9>
{
};

```

### `TransformItemResponse::buildSchema::__l2::<lambda_c71eca83285b325553324d79dba7bdf2>`
```
struct __cppobj TransformItemResponse::buildSchema::__l2::<lambda_c71eca83285b325553324d79dba7bdf2>
{
  const Factory<EventResponse> *factory;
};

```

### `TrustComponent`
```
struct __cppobj TrustComponent : IEntityComponent
{
  std::unordered_set<ActorUniqueID> mTrustedPlayerIDs;
};

```

### `TeleportToSubcomponent::doOnHitEffect::__l26::<lambda_d33dbc7f75bb3091c84043f63af77e00>`
```
struct __cppobj TeleportToSubcomponent::doOnHitEffect::__l26::<lambda_d33dbc7f75bb3091c84043f63af77e00>
{
  std::vector<NetworkIdentifierWithSubId> *ids;
  Player *player;
  Vec3 *oldPlayerPos;
};

```

### `TeleportToSubcomponent::doOnHitEffect::__l14::<lambda_ad7a5dc6e6f0de392d81664e464d9cfd>`
```
struct __cppobj TeleportToSubcomponent::doOnHitEffect::__l14::<lambda_ad7a5dc6e6f0de392d81664e464d9cfd>
{
  Player *player;
  Vec3 *oldPlayerPos;
  Vec3 *teleportPos;
};

```

### `TameableDefinition`
```
struct __cppobj TameableDefinition
{
  float mTameChance;
  std::set<Item const *> mTameItems;
  DefinitionTrigger mOnTame;
};

```

### `TameableComponent`
```
struct __cppobj TameableComponent : IEntityComponent
{
  float mChance;
  std::set<Item const *> mTameItems;
};

```

### `TargetNearbyComponent`
```
struct __cppobj TargetNearbyComponent : IEntityComponent
{
  bool mWasSeenLastTick;
  bool mWasInsideRange;
  bool mWasOutsideRange;
  float mPreviousDistance;
};

```

### `TeleportComponent`
```
struct __cppobj TeleportComponent : IEntityComponent
{
  bool mRandomTeleports;
  int mMinTeleportTime;
  int mMaxTeleportTime;
  Vec3 mRandomTeleportCube;
  float mTargetDistance;
  float mTargetTeleportChance;
  float mLightTeleportChance;
  float mDarkTeleportChance;
  int mTeleportTime;
};

```

### `TeleportComponent::teleport::__l30::<lambda_9130bd251c12fa1ac70f29d981a940a3>`
```
struct __cppobj TeleportComponent::teleport::__l30::<lambda_9130bd251c12fa1ac70f29d981a940a3>
{
  std::vector<NetworkIdentifierWithSubId> *ids;
  Actor *owner;
  const Vec3 *origin;
  BlockPos *blockPos;
};

```

### `TeleportComponent::teleport::__l18::<lambda_daebc4da42af9d7f6fc3a26b463d0843>`
```
struct __cppobj TeleportComponent::teleport::__l18::<lambda_daebc4da42af9d7f6fc3a26b463d0843>
{
  Actor *owner;
  const Vec3 *origin;
  BlockPos *blockPos;
};

```

### `TameableComponent::getInteraction::__l11::<lambda_85de93a26522ada2de7ba76a38cd26e9>`
```
struct __cppobj TameableComponent::getInteraction::__l11::<lambda_85de93a26522ada2de7ba76a38cd26e9>
{
  Player *player;
  Actor *owner;
  TameableComponent *const __this;
};

```

### `TimerDefinition`
```
struct __cppobj TimerDefinition
{
  bool mLooping;
  bool mRandomInterval;
  FloatRange mTime;
  DefinitionTrigger mOnTimeDown;
  WeightedChoices<float> mTimeChoices;
};

```

### `TradeResupplyComponent`
```
struct __cppobj TradeResupplyComponent : IEntityComponent
{
  bool mHasResupplied;
};

```

### `TrailComponent`
```
struct __cppobj __declspec(align(8)) TrailComponent : IEntityComponent
{
  const BlockLegacy *mBlockType;
  Vec3 mSpawnOffset;
};

```

### `TransformationComponent`
```
struct __cppobj TransformationComponent : IEntityComponent
{
  int mDelayTicks;
};

```

### `TripodCameraComponent`
```
struct __cppobj TripodCameraComponent : IEntityComponent
{
};

```

### `TrustingDefinition`
```
struct __cppobj TrustingDefinition
{
  float mTrustProbability;
  std::set<Item const *> mTrustItems;
  DefinitionTrigger mOnTrust;
};

```

### `TrustingComponent::getInteraction::__l11::<lambda_0fc0173eaae0a742acebc23640ef2139>`
```
struct __cppobj TrustingComponent::getInteraction::__l11::<lambda_0fc0173eaae0a742acebc23640ef2139>
{
  Player *player;
  Actor *owner;
  TrustingComponent *const __this;
};

```

### `TripodCameraComponent::getInteraction::__l15::<lambda_667927d796701bc18c24f0841efba17d>`
```
struct __cppobj TripodCameraComponent::getInteraction::__l15::<lambda_667927d796701bc18c24f0841efba17d>
{
  TripodCamera *tripodCamera;
  Player *player;
};

```

### `TimerDefinition::buildSchema::__l2::<lambda_8a96bd0f32f0f92e3c95d4e009cea4e1>`
```
struct __cppobj TimerDefinition::buildSchema::__l2::<lambda_8a96bd0f32f0f92e3c95d4e009cea4e1>
{
};

```

### `typeid_t<ContextAccessor>`
```
struct __cppobj typeid_t<ContextAccessor>
{
  unsigned __int16 mID;
};

```

### `TempEPtr<Mob>`
```
struct __cppobj __declspec(align(8)) TempEPtr<Mob> : _TickPtr
{
  Mob *tmp;
  ActorUniqueID mEntityId;
  Level *mLevel;
  bool mHasLocked;
};

```

### `TempEPtr<Mob>_vtbl`
```
struct /*VFT*/ TempEPtr<Mob>_vtbl
{
  void (__fastcall *invalidate)(_TickPtr *this);
  void (__fastcall *~_TickPtr)(_TickPtr *this);
};

```

### `TargetNearbySystem`
```
struct __cppobj TargetNearbySystem : ITickingSystem
{
};

```

### `TargetNearbySystem_vtbl`
```
struct /*VFT*/ TargetNearbySystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `TeleportSystem`
```
struct __cppobj TeleportSystem : ITickingSystem
{
};

```

### `TeleportSystem_vtbl`
```
struct /*VFT*/ TeleportSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `TimerSystem`
```
struct __cppobj TimerSystem : ITickingSystem
{
};

```

### `TimerSystem_vtbl`
```
struct /*VFT*/ TimerSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `TextPacket::read::__l7::<lambda_7cd9b5212b0367df8ac0a7b2f8498984>`
```
struct __cppobj TextPacket::read::__l7::<lambda_7cd9b5212b0367df8ac0a7b2f8498984>
{
};

```

### `TextPacket::read::__l4::<lambda_a4896c695fc851fc77114ba166a2c452>`
```
struct __cppobj TextPacket::read::__l4::<lambda_a4896c695fc851fc77114ba166a2c452>
{
};

```

### `TextPacket::write::__l7::<lambda_e83aca2eab073780067fc90b2bd3d097>`
```
struct __cppobj TextPacket::write::__l7::<lambda_e83aca2eab073780067fc90b2bd3d097>
{
};

```

### `TextPacket::write::__l4::<lambda_596e51374069ff929839efe6f2bb4faf>`
```
struct __cppobj TextPacket::write::__l4::<lambda_596e51374069ff929839efe6f2bb4faf>
{
};

```

### `TestPackAccessStrategy`
```
struct __cppobj TestPackAccessStrategy : PackAccessStrategy
{
  ResourceLocation mResourceLocation;
  unsigned __int64 mPackSize;
  bool mIsWriteable;
  bool mIsTrusted;
  std::string mPackName;
  PackAccessStrategyType mAccessStrategyType;
  std::unordered_map<Core::PathBuffer<std::string >,VirtualFile,std::hash<Core::PathBuffer<std::string > >,std::equal_to<Core::PathBuffer<std::string > >,std::allocator<std::pair<Core::PathBuffer<std::string > const ,VirtualFile> > > mFileDirectory;
};

```

### `TestPackAccessStrategy_vtbl`
```
struct /*VFT*/ TestPackAccessStrategy_vtbl
{
  void (__fastcall *~PackAccessStrategy)(PackAccessStrategy *this);
  unsigned __int64 (__fastcall *getPackSize)(PackAccessStrategy *this);
  const ResourceLocation *(__fastcall *getPackLocation)(PackAccessStrategy *this);
  const std::string *(__fastcall *getPackName)(PackAccessStrategy *this);
  bool (__fastcall *isWritable)(PackAccessStrategy *this);
  void (__fastcall *setIsTrusted)(PackAccessStrategy *this, bool);
  bool (__fastcall *isTrusted)(PackAccessStrategy *this);
  bool (__fastcall *hasAsset)(PackAccessStrategy *this, const Core::Path *, bool);
  bool (__fastcall *hasFolder)(PackAccessStrategy *this, const Core::Path *);
  bool (__fastcall *getAsset)(PackAccessStrategy *this, const Core::Path *, std::string *, bool);
  bool (__fastcall *deleteAsset)(PackAccessStrategy *this, const Core::PathBuffer<std::string > *);
  bool (__fastcall *writeAsset)(PackAccessStrategy *this, const Core::Path *, const std::string *);
  void (__fastcall *forEachIn)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>, bool);
  void (__fastcall *forEachInAssetSet)(PackAccessStrategy *this, const Core::Path *, std::function<void __cdecl(Core::Path const &)>);
  PackAccessStrategyType (__fastcall *getStrategyType)(PackAccessStrategy *this);
  const Core::PathBuffer<std::string > *(__fastcall *getSubPath)(PackAccessStrategy *this);
  std::unique_ptr<PackAccessStrategy> *(__fastcall *createSubPack)(PackAccessStrategy *this, std::unique_ptr<PackAccessStrategy> *result, const Core::Path *);
  PackAccessAssetGenerationResult (__fastcall *generateAssetSet)(PackAccessStrategy *this);
  bool (__fastcall *canRecurse)(PackAccessStrategy *this);
  void (__fastcall *unload)(PackAccessStrategy *this);
  __int64 (__fastcall *getLastModifiedTime)(PackAccessStrategy *this, const Core::Path *);
  std::unique_ptr<IDataOutput> *(__fastcall *createEncryptor)(PackAccessStrategy *this, std::unique_ptr<IDataOutput> *result, std::unique_ptr<IDataOutput>);
  std::unique_ptr<IDataInput> *(__fastcall *createDecryptor)(PackAccessStrategy *this, std::unique_ptr<IDataInput> *result, std::unique_ptr<IDataInput>);
  bool (__fastcall *hasUpgradeFiles)(PackAccessStrategy *this);
  ContentIdentity *(__fastcall *readContentIdentity)(PackAccessStrategy *this, ContentIdentity *result);
  bool (__fastcall *hasFile)(PackAccessStrategy *this, const Core::Path *);
  void (__fastcall *setSubPathAsPackName)(PackAccessStrategy *this);
};

```

### `TreatmentPackSource::load::__l5::<lambda_b6e7809886387660f36c54eb091a8cb1>`
```
struct __cppobj TreatmentPackSource::load::__l5::<lambda_b6e7809886387660f36c54eb091a8cb1>
{
  TreatmentPackSource *const __this;
  PackManifestFactory *manifestFactory;
  const IContentKeyProvider *keyProvider;
  PackSourceReport *result;
};

```

### `TestCommandOrigin`
```
struct __cppobj __declspec(align(8)) TestCommandOrigin : CommandOrigin
{
  ActorUniqueID mPlayerId;
  Level *mLevel;
  NetworkIdentifier mSourceId;
  unsigned __int8 mSourceSubId;
};

```

### `TestCommandOrigin_vtbl`
```
struct /*VFT*/ TestCommandOrigin_vtbl
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

