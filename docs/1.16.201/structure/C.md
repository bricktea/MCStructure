# C
### `Core::Profile::GroupToken`
Offset | Type | Name
-|-|-|-
0 | (8) `const Core::Profile::ProfileGroup *` | mGroup
8 | (80) `std::mutex` | mTokenCreationMutex
88 | (16) `Core::Profile::CPUProfileTokenMicroProfile` | mToken
104 | (8) `const char *` | mLabel
112 | (4) `unsigned int` | mCustomColor


### `Core::Profile::CPUProfileTokenMicroProfile`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mColor
8 | (8) `std::atomic<unsigned __int64>` | mMicroProfileToken


### `ClientBlockPipeline::SmoothLightBakingStep::_computeLightBrightness::__l2::<lambda_44f4050c3c928648c37d299e6a06abad>`
Offset | Type | Name
-|-|-|-


### `Core::PathBuffer<std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mContainer


### `Core::Path`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathPart` | mPathPart


### `Core::PathPart`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUtf8StdString


### `ContentIdentity`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mUUID
16 | (1) `bool` | mValid


### `ClientBlobCache::Cache::_trimIfNeeded::__l5::<lambda_cfc6481d33223e5533d33a80b1ed8b6a>`
Offset | Type | Name
-|-|-|-


### `ChunkPos`
Offset | Type | Name
-|-|-|-
0 | (8) `$9E42F9C9F7B1A17B3F4FC42C25BE33AF` | ___u0


### `Core::PathBuffer<Core::StackString<char,1024> >`
Offset | Type | Name
-|-|-|-
0 | (1040) `Core::StackString<char,1024>` | mContainer


### `Core::StackString<char,1024>`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int64` | MAX_LENGTH
8 | (1024) `std::array<char,1024>` | mBuf
1032 | (8) `unsigned __int64` | mLength


### `ContentAcquisition::_sortContentTrackersByPriority::__l2::<lambda_9747ad26564c82a94e7199d71afa4537>`
Offset | Type | Name
-|-|-|-


### `CommonDocument`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mProductId
32 | (32) `std::string` | mContentType
64 | (32) `std::string` | mCreatorId
96 | (32) `std::string` | mStartDate
128 | (32) `std::string` | mCreationDate
160 | (32) `std::string` | mLastModifiedDate
192 | (64) `CommonLocTextPair` | mTitle
256 | (64) `CommonLocTextPair` | mDescription
320 | (64) `std::unordered_map<std::string,std::string>` | mTitleDictionary
384 | (64) `std::unordered_map<std::string,std::string>` | mDescriptionDictionary
448 | (28) `RatingData` | mRatingData
476 | (1) `bool` | mIsSemVersionValid
477 | (1) `bool` | mIsTitleLocked
480 | (32) `std::string` | mThumbnailUrl
512 | (24) `std::vector<std::string>` | mTags
536 | (24) `std::vector<CommonContent>` | mContents
560 | (24) `std::vector<CommonImage>` | mImages


### `CommonLocTextPair`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | langCode
32 | (32) `std::string` | locText


### `ContentTierManager::ValidatorRegistry::ValidatorRegisterer`
Offset | Type | Name
-|-|-|-


### `ContentTierManager::ValidatorRegistry`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_0
16 | (64) `std::unordered_map<std::string,ContentTierManager::ValidatorRegistry::ValidatorRegistryValidators>` | mValidatorList


### `CommandFlag`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | flag


### `CommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandOrigin_vtbl *` | __vftable
8 | (16) `mce::UUID` | mUUID


### `Core::Random`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mSeed
4 | (2496) `unsigned int[624]` | _mt
2500 | (4) `int` | _mti
2504 | (1) `bool` | mHaveNextNextGaussian
2508 | (4) `float` | mNextNextGaussian
2512 | (4) `int` | mInitedIdx


### `ComponentDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `Description` | baseclass_0


### `CompoundTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (16) `std::map<std::string,CompoundTagVariant>` | mTags


### `CraftableCompounds::_getCompoundId::__l2::<lambda_cb3f8bb483eddc0a11d03ac37babd3ba>`
Offset | Type | Name
-|-|-|-


### `ContainerPopulationData`
Offset | Type | Name
-|-|-|-
0 | (1) `ContainerEnumName` | containerName
4 | (4) `CreativeItemCategory` | itemCategory


### `ContainerScreenContext`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | mPlayer
8 | (1) `ContainerType` | mScreenContainerType
16 | (24) `std::variant<std::monostate,ActorUniqueID,BlockPos>` | mOwner


### `ChemicalHeatBlock::_getRelativeOffsets::__l5::<lambda_b0dd78f1bda910ef2822257e4eb6eb5b>`
Offset | Type | Name
-|-|-|-


### `ChunkLocalHeight`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | mVal


### `ChunkSource::_spawnChunkGenerationTasks::__l3::<lambda_7e0f765fe899e3b8d51a4ee6497a8231>`
Offset | Type | Name
-|-|-|-


### `cst_diphone_entry_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (2) `unsigned __int16` | start_pm
10 | (1) `unsigned __int8` | pb_pm
11 | (1) `unsigned __int8` | end_pm


### `cst_dur_stats_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | phone
8 | (4) `float` | mean
12 | (4) `float` | stddev


### `cst_val_struct`
Offset | Type | Name
-|-|-|-
0 | (16) `union {cst_val_cons_struct cc;cst_val_atom_struct a;}` | c


### `cst_val_cons_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `cst_val_struct *` | car
8 | (8) `cst_val_struct *` | cdr


### `cst_val_atom_struct`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | type
4 | (4) `int` | ref_count
8 | (8) `cst_val_atom_struct::<unnamed_type_v>` | v


### `cst_val_atom_struct::<unnamed_type_v>`
Offset | Type | Name
-|-|-|-
0 | (8) `long double` | fval
1 | (8) `__int64` | ival
2 | (8) `void *` | vval


### `cst_cart_node_struct`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | feat
1 | (1) `unsigned __int8` | op
2 | (2) `unsigned __int16` | no_node
8 | (8) `const cst_val_struct *` | val


### `cst_regex_struct`
Offset | Type | Name
-|-|-|-
0 | (1) `char` | regstart
1 | (1) `char` | reganch
8 | (8) `char *` | regmust
16 | (4) `int` | regmlen
20 | (4) `int` | regsize
24 | (8) `char *` | program


### `cst_synth_module_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | hookname
8 | (8) `cst_utterance_struct *(__fastcall *)(cst_utterance_struct *)` | defhook


### `config_s`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | good_length
2 | (2) `unsigned __int16` | max_lazy
4 | (2) `unsigned __int16` | nice_length
6 | (2) `unsigned __int16` | max_chain
8 | (8) `block_state (__fastcall *)(internal_state *, int)` | func


### `code`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | op
1 | (1) `unsigned __int8` | bits
2 | (2) `unsigned __int16` | val


### `ct_data_s`
Offset | Type | Name
-|-|-|-
0 | (2) `union {unsigned __int16 freq;unsigned __int16 code;}` | fc
2 | (2) `union {unsigned __int16 dad;unsigned __int16 len;}` | _dl


### `Core::FileOpenMode`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `CompareScheduledCallback`
Offset | Type | Name
-|-|-|-


### `CFF_Field_Handler_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | kind
4 | (4) `int` | code
8 | (4) `unsigned int` | offset
12 | (1) `unsigned __int8` | size
16 | (8) `int (__fastcall *)(CFF_ParserRec_ *)` | reader
24 | (4) `unsigned int` | array_max
28 | (4) `unsigned int` | count_offset


### `Core::Profile::ProfileGroupManager`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Core::Profile::ProfileGroupManager::Impl>` | mImpl


### `Core::Profile::CounterTokenMicroProfile`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mMicroProfileToken


### `ColorChannel`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mValue


### `CatalogPropertyBag`
Offset | Type | Name
-|-|-|-
0 | (24) `PropertyBag` | baseclass_0


### `CompassSpriteCalculator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFrame
4 | (4) `float` | mRot
8 | (4) `float` | mRotA


### `cst_lang_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | lang
8 | (8) `void (__fastcall *)(cst_voice_struct *)` | lang_init
16 | (8) `lexicon_struct *(*)(...)` | lex_init


### `CrashDumpFormatEntryImpl`
Offset | Type | Name
-|-|-|-
0 | (32) `CrashDumpLogFieldFormat` | baseclass_0


### `CrashDumpLogFieldFormat`
Offset | Type | Name
-|-|-|-
0 | (24) `char[24]` | mMemberName
24 | (4) `unsigned int` | mMemberSize
28 | (4) `_BYTE[4]` | mMemberFormatCode


### `cst_cart_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const cst_cart_node_struct *` | rule_table
8 | (8) `const char *const *` | feat_table


### `Core::Subject<I18nObserver,Core::SingleThreadedLock>`
Offset | Type | Name
-|-|-|-
8 | (24) `std::vector<gsl::not_null<I18nObserver *>>` | mObservers


### `Core::SingleThreadedLock`
Offset | Type | Name
-|-|-|-


### `Core::StorageAreasTree`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::StorageAreasTree::TreeNode` | mRoot
32 | (24) `std::vector<Core::FileStorageArea *>` | mStorageAreas


### `Core::StorageAreasTree::TreeNode`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Core::StorageAreasTree::TreeChild>` | mChildren
24 | (8) `Core::FileStorageArea *` | mStorageArea


### `cst_lts_rules_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | name
8 | (8) `const unsigned __int16 *` | letter_index
16 | (8) `const unsigned __int8 *` | models
24 | (8) `const char *const *` | phone_table
32 | (4) `int` | context_window_size
36 | (4) `int` | context_extra_feats
40 | (8) `const char *const *` | letter_table


### `Core::OutputFileStream`
Offset | Type | Name
-|-|-|-
0 | (296) `Core::FileStream` | baseclass_0


### `Core::FileStream`
Offset | Type | Name
-|-|-|-
0 | (128) `std::iostream` | baseclass_0
128 | (56) `_BYTE[56]` | mStreamBuffer
184 | (1) `bool` | mLoggingEnabled
185 | (111) `_BYTE[111]` | gapB9


### `CommandRegistry::Symbol`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mValue


### `CFF_Decoder_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(CFF_Decoder_ *, TT_FaceRec_ *, CFF_SizeRec_ *, CFF_GlyphSlotRec_ *, unsigned __int8, FT_Render_Mode_, int (__fastcall *)(TT_FaceRec_ *, unsigned int, unsigned __int8 **, unsigned int *), void (__fastcall *)(TT_FaceRec_ *, unsigned __int8 **, unsigned int))` | init
8 | (8) `int (__fastcall *)(CFF_Decoder_ *, CFF_SizeRec_ *, unsigned int)` | prepare
16 | (8) `int (__fastcall *)(PS_Decoder_ *, unsigned __int8 *, unsigned int)` | parse_charstrings


### `Core::FileStats`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<unsigned __int64>` | mNumSuccessfulWriteOperations
8 | (8) `std::atomic<unsigned __int64>` | mNumBytesWritten
16 | (8) `std::atomic<unsigned __int64>` | mNumFailedWriteOperations
24 | (8) `std::atomic<unsigned __int64>` | mNumSuccessfulReadOperations
32 | (8) `std::atomic<unsigned __int64>` | mNumBytesRead
40 | (8) `std::atomic<unsigned __int64>` | mNumFailedReadOperations
48 | (8) `std::atomic<unsigned __int64>` | mFileSystemSize
56 | (8) `std::atomic<unsigned __int64>` | mFileSystemAllocatedSize


### `cst_sts_list_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const cst_sts_struct *` | sts
8 | (8) `const cst_sts_paged_struct *` | sts_paged
16 | (8) `const unsigned __int16 *` | frames
24 | (8) `const unsigned __int8 *` | residuals
32 | (8) `const unsigned int *` | resoffs
40 | (8) `const unsigned __int8 *` | ressizes
48 | (4) `int` | num_sts
52 | (4) `int` | num_channels
56 | (4) `int` | sample_rate
60 | (4) `float` | coeff_min
64 | (4) `float` | coeff_range
72 | (8) `const char *` | codec


### `cst_phoneset_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (8) `const char *const *` | featnames
16 | (8) `const cst_val_struct *const *` | featvals
24 | (8) `const char *const *` | phonenames
32 | (8) `const char *` | silence
40 | (4) `const int` | num_phones
48 | (8) `const int *const *` | fvtable
56 | (4) `int` | freeable


### `CFF_Builder_FuncsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(CFF_Builder_ *, TT_FaceRec_ *, CFF_SizeRec_ *, CFF_GlyphSlotRec_ *, unsigned __int8)` | init
8 | (8) `void (__fastcall *)(CFF_Builder_ *)` | done
16 | (8) `int (__fastcall *)(CFF_Builder_ *, int)` | check_points
24 | (8) `void (__fastcall *)(CFF_Builder_ *, int, int, unsigned __int8)` | add_point
32 | (8) `int (__fastcall *)(CFF_Builder_ *, int, int)` | add_point1
40 | (8) `int (__fastcall *)(CFF_Builder_ *)` | add_contour
48 | (8) `int (__fastcall *)(CFF_Builder_ *, int, int)` | start_point
56 | (8) `void (__fastcall *)(CFF_Builder_ *)` | close_contour


### `cst_val_def_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (8) `void (__fastcall *)(void *)` | delete_function


### `cg::TextureDescription`
Offset | Type | Name
-|-|-|-
0 | (64) `cg::ImageDescription` | baseclass_0
64 | (4) `unsigned int` | mMipCount


### `cg::ImageDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mWidth
4 | (4) `unsigned int` | mHeight
8 | (4) `mce::TextureFormat` | mTextureFormat
12 | (1) `cg::ColorSpace` | mColorSpace
13 | (1) `bool` | mIsCubemap
16 | (40) `KTX::KTXInfo` | mKTXInfo
56 | (4) `unsigned int` | mArraySize


### `cg::TextureSetImageDescription`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<cg::TextureSetImageDescription::LayerInfoVar>` | mLayerInfo


### `cst_diphone_db_struct`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name
8 | (4) `int` | num_entries
16 | (8) `const cst_diphone_entry_struct *` | diphones
24 | (8) `const cst_sts_list_struct *` | sts


### `ContentTierIncompatibleReason`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mError


### `C_SCOPE_TABLE`
Offset | Type | Name
-|-|-|-
0 | (4) `` | Begin
4 | (4) `` | End
8 | (4) `` | Handler
12 | (4) `` | Target


### `Core::FileStdStreamBuf`
Offset | Type | Name
-|-|-|-
0 | (104) `std::streambuf` | baseclass_0
104 | (16) `Core::File` | mFile
120 | (1) `Core::FileOpenMode` | mFileOpenMode
128 | (24) `std::vector<char>` | mBuffer
152 | (8) `unsigned __int64` | mBufferSize


### `Core::File`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Core::FileImpl>` | muptFile
8 | (8) `std::unique_ptr<Core::FileSystemImpl>` | muptTransaction


### `cg::TypeFlagPair`
Offset | Type | Name
-|-|-|-
0 | (4) `cg::TextureSetLayerType` | type
8 | (8) `const char *` | desc


### `CameraShakeComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<CameraShakeEvent>` | mShakeEvents
24 | (8) `std::unique_ptr<SimplexNoise>` | xAxisNoise
32 | (8) `std::unique_ptr<SimplexNoise>` | yAxisNoise
40 | (8) `std::unique_ptr<SimplexNoise>` | zAxisNoise
48 | (8) `long double` | mLastUpdatedTime
56 | (4) `float` | mNoiseTime
60 | (4) `float` | mShakeIntensity
64 | (4) `float` | mDecayRate
68 | (1) `CameraShakeType` | mShakeType
69 | (1) `bool` | mWasShaking


### `ComplexInventoryTransaction`
Offset | Type | Name
-|-|-|-
0 | (8) `ComplexInventoryTransaction_vtbl *` | __vftable
8 | (4) `ComplexInventoryTransaction::Type` | mType
16 | (88) `InventoryTransaction` | mTransaction


### `ClientBlockPipeline::Inputs`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::any>` | mInputs


### `Core::Profile::ProfileSectionGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::Profile::GroupToken *` | mToken
8 | (1) `bool` | mEntered


### `Core::Profile::ProfileGroup`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `unsigned int` | mColor
36 | (4) `int` | mGroupIndex
40 | (1) `bool` | mEnabled


### `ClientBlockPipeline::VolumeViewOf<BrightnessPair const >`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (16) `buffer_span_mut<BrightnessPair const >` | mView


### `ClientBlockPipeline::UvTransform`
Offset | Type | Name
-|-|-|-
0 | (8) `Vec2` | mStart
8 | (8) `Vec2` | mSize


### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockSchematicCell const >`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (16) `buffer_span_mut<ClientBlockPipeline::BlockSchematicCell const >` | mView


### `ClientBlockPipeline::BoxSchematicInstance`
Offset | Type | Name
-|-|-|-
0 | (4) `std::bitset<6>` | mFaceMask
4 | (64) `Matrix` | mLocalToGridTransform


### `ClientBlockPipeline::SchematicsJoiningStep::StaticStepData`
Offset | Type | Name
-|-|-|-
0 | (8) `gsl::not_null<ClientBlockPipeline::OwnedBlockVolume const *>` | mBlockVolume
8 | (8) `gsl::not_null<ClientBlockPipeline::BlockSchematicVolume const *>` | mInputSchematicVolume
16 | (8) `gsl::not_null<ClientBlockPipeline::BoxSchematicAttributes const *>` | mInputBoxes
24 | (8) `gsl::not_null<ClientBlockPipeline::FaceSchematicAttributes const *>` | mInputFaces
32 | (8) `gsl::not_null<ClientBlockPipeline::SolidOpaqueBlockVolume const *>` | mSolidOpaqueBlockVolume
40 | (8) `gsl::not_null<ClientBlockPipeline::BlockSchematicVolume *>` | mOutputSchematicVolume
48 | (8) `gsl::not_null<ClientBlockPipeline::BoxSchematicAttributes *>` | mOutputBoxes
56 | (8) `gsl::not_null<ClientBlockPipeline::FaceSchematicAttributes *>` | mOutputFaces


### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell const >`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (16) `buffer_span_mut<ClientBlockPipeline::BlockCell const >` | mView


### `ClientBlockPipeline::SchematicsJoiningStep::BlockCellStepData`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mBlockPos
16 | (8) `unsigned __int64` | mBlockIndex
24 | (8) `unsigned __int64` | mLayer
32 | (8) `gsl::not_null<Block const *>` | mInputBlock
40 | (8) `gsl::not_null<ClientBlockPipeline::BlockSchematicInstance const *>` | mInputSchematic
48 | (8) `gsl::not_null<ClientBlockPipeline::BlockSchematicInstance *>` | mOutputSchematic


### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockOpacityData const >`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (16) `buffer_span_mut<ClientBlockPipeline::BlockOpacityData const >` | mView


### `ClientBlockPipeline::BoxFaceSchematic`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mExists
4 | (16) `ClientBlockPipeline::UvTransform` | mUvTransform
20 | (4) `int` | mMaterialInstanceId


### `ClientBlockPipeline::BoxSchematic`
Offset | Type | Name
-|-|-|-
0 | (64) `Matrix` | mLocalToModelTransform
64 | (144) `std::array<ClientBlockPipeline::BoxFaceSchematic,6>` | mFaces


### `ClientBlockPipeline::SmoothLightBakingStep::SampledLightValues`
Offset | Type | Name
-|-|-|-
0 | (8) `Vec2` | mLightUvs
8 | (4) `float` | mAoValue


### `ClientBlockPipeline::VolumeViewOf<float const >`
Offset | Type | Name
-|-|-|-
0 | (12) `Pos` | mMin
12 | (12) `Pos` | mMax
24 | (16) `buffer_span_mut<float const >` | mView


### `ClientBlockPipeline::BakedMaterialMap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<ClientBlockPipeline::Material const >>` | mResolvedMaterials
24 | (1) `bool` | mIsOpaqueForOccluding


### `ClientBlockPipeline::DimensionDimmingScalars`
Offset | Type | Name
-|-|-|-
0 | (24) `std::array<float,6>` | mScalars


### `ClientBlockPipeline::Description::BakedStep`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mStepId
8 | (24) `std::vector<unsigned __int64>` | mDependencies
32 | (24) `std::vector<unsigned __int64>` | mDependants


### `ClientBlockPipeline::BlockCell`
Offset | Type | Name
-|-|-|-
0 | (16) `std::array<Block const *,2>` | mBlocks


### `ContentSource`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentSource_vtbl *` | __vftable
8 | (24) `std::vector<ContentItem *>` | mLoadedItems
32 | (4) `_BYTE[4]` | mType
40 | (8) `ContentManager *` | mContentManager


### `Core::Result`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<char const * __cdecl(std::string *)>` | mMessageResolver
64 | (1) `__int8` | _bf_40


### `cg::ImageBuffer`
Offset | Type | Name
-|-|-|-
0 | (24) `mce::Blob` | mStorage
24 | (64) `cg::ImageDescription` | mImageDescription


### `Core::SplitPathT<1024,64>`
Offset | Type | Name
-|-|-|-
0 | (2048) `std::array<Core::Path,64>` | mParts
2048 | (8) `unsigned __int64` | mNumParts


### `CameraBlendSettings`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<float __cdecl(float,float,float)>` | mEaseFunction
64 | (4) `float` | mBlendTime
68 | (1) `bool` | mCameraFromAcceptsInput
69 | (1) `bool` | mCameraToAcceptsInput


### `CameraDirector`
Offset | Type | Name
-|-|-|-
0 | (312) `Camera` | mCamera
312 | (24) `std::vector<std::unique_ptr<ICameraBehavior>>` | mBehaviors
336 | (8) `std::unique_ptr<ActivationRule>` | mActivationRule


### `Camera`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mId
48 | (4) `int` | mPriority
56 | (72) `CameraBlendSettings` | mBlendInDefault
128 | (1) `bool` | mRenderPlayerModel
129 | (1) `bool` | mShouldRenderFirstPersonObjects
136 | (8) `ActorUniqueID` | mLookTarget
144 | (8) `ActorUniqueID` | mFollowTarget
152 | (4) `float` | mAspectRatio
156 | (4) `float` | mFieldOfView
160 | (4) `float` | mNearPlane
164 | (4) `float` | mFarPlane
168 | (16) `glm::tquat<float,0>` | mOrientation
184 | (12) `glm::tvec3<float,0>` | mPosition
196 | (12) `glm::tvec3<float,0>` | mScale
208 | (64) `Matrix` | mPostViewTransform
272 | (1) `bool` | mFacesPlayerFront
273 | (1) `bool` | mPlayerRotateWithCamera
276 | (8) `glm::tvec2<float,0>` | mPlayerRotationOffset
284 | (12) `glm::tvec3<float,0>` | mLiquidOffset
296 | (4) `float` | mRideRotationOffset
300 | (4) `float` | mPlayerSneakOffset
304 | (4) `float` | mPlayerGlideOffset


### `CommandVersion`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFrom
4 | (4) `int` | mTo


### `ContextMessageLogger`
Offset | Type | Name
-|-|-|-
0 | (8) `ContextMessageLogger_vtbl *` | __vftable
8 | (24) `std::vector<ContextMessage>` | mMessageBufferArray
32 | (5) `bool[5]` | mReceivedMessages
37 | (14) `ContextMessageLoggerOptions` | mOptions


### `ContextMessageLoggerOptions`
Offset | Type | Name
-|-|-|-
0 | (4) `bool[4]` | mStoreMessages
4 | (4) `bool[4]` | mAssertIfMessageTypeWasReceived
8 | (4) `bool[4]` | mAssertInDestructorIfMessageTypeWasReceived
12 | (1) `bool` | mAllowMessagesToPostToParentMessageLoggers
13 | (1) `bool` | mOutputAllMessagesOnDestruction


### `Config`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mWidth
4 | (4) `int` | mHeight
8 | (4) `float` | mGuiScale
12 | (4) `float` | mInvGuiScale
16 | (4) `int` | mGuiWidth
20 | (4) `int` | mGuiHeight
24 | (8) `PixelCalc` | mDpadScale
32 | (8) `IMinecraftGame *` | mMinecraft
40 | (16) `std::shared_ptr<Options>` | mOptions
56 | (4) `InputMode` | mCurrentInputMode


### `CrashDumpGameplayData`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mFunc
2 | (2) `_BYTE[2]` | mTag
4 | (4) `int` | mClientId
8 | (4) `int` | mBuildActionIntention


### `ClientInstance::_leaveGameOnUnrecoverableError::__l11::<lambda_9e193ddaee367b7b7b07833f6136df6c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstance>` | weakThis
16 | (32) `const std::string` | titleMessage
48 | (32) `const std::string` | displayMessage


### `ClientFrameUpdateContext`
Offset | Type | Name
-|-|-|-
0 | (32) `FrameUpdateContext` | baseclass_0
32 | (4) `float` | a
36 | (1) `bool` | stereoRendering


### `ClientInstance::update::__l42::<lambda_2eadb951cae52f74e068bad3dd7fa7f4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstance>` | weakPtr


### `ClientInstance::setupClientGame::__l8::<lambda_f8252ab8124c045f24524d1760b419d8>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstance>` | weakThis
16 | (64) `std::function<void __cdecl(enum ClientGameSetupResult)>` | callback
80 | (1) `bool` | joiningLocalServer


### `ClientInstance::_startExternalNetworkWorld::__l2::<lambda_2f4e89c11809877f171d784f43a2bb0a>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientInstance *const` | __this
8 | (256) `Social::GameConnectionInfo` | connection
264 | (32) `const std::string` | serverName


### `ClientInstance::_startExternalNetworkWorld::__l2::<lambda_2f4e89c11809877f171d784f43a2bb0a>::()::__l25::<lambda_89f9ae71cef463ef90f3d3d6d3c5a294>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientInstance *const` | __this
8 | (256) `Social::GameConnectionInfo` | connectionInfo


### `ConstCompositeSceneStackView`
Offset | Type | Name
-|-|-|-
0 | (8) `const SceneStack *` | mMainStack
8 | (8) `const SceneStack *` | mClientInstanceStack


### `ClientInstance::_isShowingScreen::__l2::<lambda_851bb6c3689e76182cb941d3bd1036a4>`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | showingScreen
8 | (32) `const std::string` | screenName


### `ClientInstance::navigateToCoinPurchaseScreen::__l2::<lambda_e1cf1260acbd6347c10ba2122d74ca7a>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstance>` | weakPtr
16 | (16) `std::shared_ptr<OfferRepository::ProductQueryAttemptResult>` | queryAttemptFinished
32 | (16) `std::shared_ptr<AsyncTracker>` | tracker
48 | (4) `int` | neededCoins
56 | (64) `std::function<void __cdecl(bool)>` | callback


### `ClientInstance::navigateToStoreSeeAllByCreatorScreen::__l2::<lambda_15d8531333f726aeede88a06a28b4fd0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstance>` | weakThis
16 | (32) `const std::string` | creatorId
48 | (1) `const bool` | calledFromHyperlink


### `ClientInstance::ClientDestroyBlockState`
Offset | Type | Name
-|-|-|-
0 | (8) `Player *` | mPlayer
8 | (8) `GameMode *` | mGameMode
16 | (1) `bool` | mDestroyButtonDown
24 | (8) `const HitResult *` | mHit
32 | (64) `std::function<void __cdecl(void)>` | mClearInProgressBAI
96 | (64) `std::function<void __cdecl(void)>` | mStopDestroying
160 | (64) `std::function<void __cdecl(void)>` | mVibrate


### `ClientSkin`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mInitialized
1 | (1) `bool` | mIsLoadingGeometry
4 | (4) `int` | mReferenceCount
8 | (24) `OwnerPtrT<EntityRefTraits>` | mEntity
32 | (776) `ClientSkinInfoData` | mSkinInfoData
808 | (8) `std::unique_ptr<GeometryGroup>` | mClientSkinGeometryGroup


### `ClientSkinInfoData`
Offset | Type | Name
-|-|-|-
0 | (688) `SkinInfoData` | baseclass_0
688 | (1) `unsigned __int8` | mSubClientId
696 | (16) `BedrockTexture` | mBloomTexture
712 | (16) `BedrockTexture` | mSkinTexture
728 | (24) `std::vector<BedrockTexture>` | mSkinAnimatedTextures
752 | (16) `BedrockTexture` | mCapeTexture
768 | (1) `bool` | mValid


### `ClientParticleTrackingComponent`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<HashedString,std::vector<unsigned int>>` | mParticleEmitterLists


### `CatalogInfo`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<DateManager>` | mDateManager
16 | (20) `RetryDelay` | mSaveDelay
36 | (4) `int` | mPropertyChangeVersion


### `CallbackToken`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<CallbackTokenCancelState>` | mCancelState


### `cg::math::Rect<float>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mX
4 | (4) `float` | mY
8 | (4) `float` | mWidth
12 | (4) `float` | mHeight


### `CrashDumpKeyValueData`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mTag0
2 | (2) `_BYTE[2]` | mTag1
4 | (4) `int` | mValue0
8 | (8) `unsigned __int64` | mValue1


### `ContentLog::ContentLogEndPointData`
Offset | Type | Name
-|-|-|-
0 | (8) `gsl::not_null<ContentLogEndPoint *>` | mContentLogEndPoint


### `ControllerDirectionEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `DirectionId` | directionId
4 | (8) `float[2]` | deltaPosition


### `ClippedCollectionEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | collectionNameHash
4 | (4) `int` | startIndex
8 | (4) `int` | endIndex
16 | (8) `UIPropertyBag *` | propertyBag


### `ClipStateChangeEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
8 | (8) `UIPropertyBag *` | propertyBag
16 | (1) `bool` | isClipped


### `CustomRendererEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id


### `CollisionGrid<15>`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mWidth
4 | (4) `float` | mHeight
8 | (32) `std::bitset<225>` | mGrid


### `ClientBlockPipeline::TessellatorContext`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<ClientBlockPipeline::SchematicsRepository>` | mSchematicsRepo


### `CommandListTaskContext`
Offset | Type | Name
-|-|-|-
0 | (64) `mce::CommandList` | mCommandList
64 | (8) `mce::RingBuffer *` | mCbUploadRingBuffer
72 | (8) `mce::PerFrameConstants *` | mThreadedPerFrameConstants
80 | (8) `mce::ShaderConstants *` | mThreadedShaderConstants
88 | (8) `mce::RenderChunkConstants *` | mRenderChunkConstantBuffer
96 | (8) `mce::WorldConstants *` | mThreadedWorldConstantBuffer
104 | (8) `` | gap68


### `ChunkLayerRenderObject`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mChunkIdx
8 | (8) `const mce::MaterialPtr *` | mMaterial
16 | (4) `unsigned int` | mIndicesStart
20 | (4) `unsigned int` | mIndicesCount
24 | (4) `unsigned int` | mUnsortedIndicesStart
28 | (4) `unsigned int` | mUnsortedIndicesCount
32 | (1) `bool` | mShouldFallBackToUnsorted


### `ContentLog::ContentLogScope`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mPopScope
8 | (16) `std::weak_ptr<ContentLog::ScopeHandler>` | mScopeHandler


### `ClientInstanceScreenModel`
Offset | Type | Name
-|-|-|-
0 | (216) `MinecraftScreenModel` | baseclass_0
216 | (64) `std::unordered_map<ActorUniqueID,BossInfo>` | mBossInfo


### `ContainerScreenController::_registerStateMachine::__l2::<lambda_22ba86bea9db98d4be3d24a41addfd59>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerScreenController *const` | __this


### `ControlsSettingsScreenController::_registerControllerCallbacks::__l2::<lambda_7847dc19740a716fdd766d12d5c86f1d>::()::__l2::<lambda_e1ed6117cdc1faf979ad9c55cf15bfe3>`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | option
8 | (64) `std::function<void __cdecl(void)>` | onToggle


### `ControlsSettingsScreenController::KeyboardLayoutInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `const KeyboardType` | mType
8 | (8) `KeyboardRemappingLayout *` | mLayout
16 | (24) `std::vector<ControlsSettingsScreenController::BindingInfo>` | mBindings
40 | (32) `const std::string` | mGridDimensionName
72 | (32) `const std::string` | mCollectionName


### `CourseScreenController::_setLeaveGameOverride::__l2::<lambda_b1807e78fd2d1443f9792a801376796c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<TutorialCollection>` | tutorialCollection
16 | (16) `std::shared_ptr<LibraryCollection>` | libraryCollection
32 | (32) `std::string` | courseTitle
64 | (32) `std::string` | courseId
96 | (4) `int` | activeItemIndex


### `CraftingScreenControllerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ContainerController * __cdecl(std::string const &)>` | mGetContainerController
64 | (64) `std::function<void __cdecl(std::string const &,int,enum ItemCraftType)>` | mRecipeAutoCraft
128 | (64) `std::function<void __cdecl(std::string const &,int)>` | mHandleRecipeSelect
192 | (64) `std::function<void __cdecl(Recipe const *)>` | mHandleRecipePlaceInputs
256 | (64) `std::function<void __cdecl(std::string const &,int)>` | mHandleAutoPlace
320 | (64) `std::function<void __cdecl(void)>` | mLeaveScreen


### `CraftableCountingData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTotalResultItems
4 | (4) `int` | mAmountOfTimesRecipeIsCrafted


### `CraftingScreenController::_registerStateMachine::__l2::<lambda_be0bf6bd90e4b29638d1008293b3501b>`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | clearHotbarButtonOrDropId


### `CraftingScreenController::_recipeAutoCraft::__l2::<lambda_6aa2f103e2c2f5d7d0fafc45ee252653>`
Offset | Type | Name
-|-|-|-
0 | (8) `CraftingScreenController *const` | __this
8 | (32) `const std::string` | collectionName
40 | (4) `int` | collectionIndex


### `CraftingTableComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mGridSize
8 | (32) `std::string` | mCustomDescription
40 | (24) `std::vector<std::string>` | mCraftingTags


### `CustomTemplatesScreenController::_registerEvents::__l2::<lambda_faa911ab3abefbbffed8c9d57cca4fc8>::()::__l8::<lambda_855dc3b3dd5168adfa3023a3c097783b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<CustomTemplatesScreenController>` | weakThis
16 | (264) `const WorldTemplateInfo` | level


### `CustomTemplatesScreenController::_handleWorldTemplateClicked::__l2::<lambda_0fd1354ad3496433dfc1a1fe4fe2b8a7>`
Offset | Type | Name
-|-|-|-
0 | (8) `CustomTemplatesScreenController *const` | __this
8 | (136) `PackIdVersion` | packId


### `CustomTemplatesScreenController::_createWorldTemplate::__l5::<lambda_bc20e33a775adc61e26b6412226bb3d7>`
Offset | Type | Name
-|-|-|-
0 | (8) `CustomTemplatesScreenController *const` | __this
8 | (8) `const WorldTemplateInfo *` | level
16 | (64) `std::function<void __cdecl(void)>` | failureCallback


### `CustomTemplatesScreenController::_createWorldTemplate::__l5::<lambda_bc20e33a775adc61e26b6412226bb3d7>::()::__l5::<lambda_1e628f6eed268bb442e37bdf2a00b8a2>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(void)>` | failureCallback


### `ClientInstanceScreenController`
Offset | Type | Name
-|-|-|-
0 | (2648) `MinecraftScreenController` | baseclass_0
2648 | (16) `std::shared_ptr<ClientInstanceScreenModel>` | mClientInstanceScreenModel
2664 | (8) `std::unique_ptr<PlatformMultiplayerRestrictions>` | mPlatformMultiplayerRestrictions


### `ContentTierInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMemoryTier
4 | (1) `bool` | mIsRayTracingCapable


### `Clubs::ClubModel`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mClubID
32 | (32) `std::string` | mClubDescription
64 | (32) `std::string` | mClubIcon
96 | (32) `std::string` | mClubName


### `ControlScreenAction`
Offset | Type | Name
-|-|-|-
0 | (8) `ControlScreenAction_vtbl *` | __vftable


### `CommandSyntaxInformation`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isValid
8 | (32) `std::string` | description
40 | (24) `std::vector<OverloadSyntaxInformation>` | possibilities


### `Core::ZipUtils::ZipFileRestrictions`
Offset | Type | Name
-|-|-|-
0 | (16) `std::set<std::string>` | mForbiddenExtensions
16 | (16) `std::set<std::string>` | mRestrictedExtensions
32 | (16) `std::set<std::string>` | mForbiddenFilenames


### `Core::ZipUtils::ZipProgress`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<unsigned int>` | mFilesDone
4 | (4) `std::atomic<unsigned int>` | mFilesSkipped
8 | (4) `std::atomic<unsigned int>` | mTotalFiles


### `CommandBlockComponent`
Offset | Type | Name
-|-|-|-
0 | (152) `BaseCommandBlock` | mBaseCommandBlock
152 | (4) `int` | mCurrentTickCount
156 | (1) `bool` | mTicking


### `CommonSearchResults`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mTotalCount
4 | (4) `int` | mFilteredCount
8 | (4) `int` | mUnfilteredDocumentCount


### `ClientInstanceScreenModel::navigateToLeaveLevelScreen::__l5::<lambda_ef00954ff1e757a0ee5bf3eac0e1e9ef>::()::__l5::<lambda_f55e9c9a0c9d5b1a28a0ec013240d974>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<ClientInstanceScreenModel>` | weakThis
16 | (1) `bool` | switchScreen
24 | (384) `LevelSummary` | summary


### `ClientInstanceScreenModel::initiateGLBFileSave::__l5::<lambda_18e2ef64fe5ed0094ca318e07172f502>`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | originPath
32 | (64) `std::function<void __cdecl(bool)>` | onComplete


### `Crypto::Hash::Hash`
Offset | Type | Name
-|-|-|-
0 | (8) `Crypto::Hash::IHash` | baseclass_0
8 | (8) `std::unique_ptr<Crypto::Hash::IHash>` | mHash
16 | (4) `int` | mUuidVersion


### `Crypto::Hash::IHash`
Offset | Type | Name
-|-|-|-
0 | (8) `Crypto::Hash::IHash_vtbl *` | __vftable


### `ClipAreas`
Offset | Type | Name
-|-|-|-
0 | (16) `std::set<RectangleArea>` | mAreas


### `ClippedControlMetadata`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<RenderControlMetadata>` | controlsToUpdate
24 | (24) `std::vector<std::shared_ptr<UIControl>>` | clippedGrids
48 | (24) `std::vector<ScreenEvent>` | clipStateChangeEvents


### `ClientBindingFactory::getAreaBinding::__l5::<lambda_f4ef36c9c2241edd05e2049a4cc37d3c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l9::<lambda_86bc8e749623499401e3fdbcc7ae7f39>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l13::<lambda_dcb08eb3e54defb9e64370fd721b66b7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l17::<lambda_6b703eda3e6b7618b784bcc537ad3c62>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l21::<lambda_363f1cc72b078a154ed0ead09b4d024d>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l25::<lambda_fa86098d63427aae10170ef55fc211e6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l29::<lambda_4ad4abaf36d194589aeacc2087f8e5d8>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l33::<lambda_c124153a23bc74bb259e700314fabfe5>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l37::<lambda_ad03e7fd0cd44601e962483c0c526b9c>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l41::<lambda_15d4d27fc3fab10c113ccc141c937ae8>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l45::<lambda_8ff1de1eef774dd1106ac7f5857e2d9b>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l49::<lambda_b41f787d80d65477826583f3d77947ad>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l53::<lambda_02e65bc75bc403a0d5915dac1a58e8c2>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l57::<lambda_662ee5d55e561d65a044d078186e83d9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l65::<lambda_11cb320c71eb9c2c133ff6d68d8de661>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l69::<lambda_9003cc46be8ff06e6019466117b648cb>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l73::<lambda_63d65d763c745e34cfd24e2ed9e972e9>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l81::<lambda_91076f5a9a3c55292508097fc4d6fac7>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l85::<lambda_feb1532674b9f50b160f3ecdb14b5bbc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l89::<lambda_3045ae51b964740e158387af04a53e99>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l93::<lambda_98c915c68a450916aaedca71464fb20d>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l97::<lambda_30a6bbd5c8267ea08db9dc591f356dc6>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l101::<lambda_9dbc146f72c67fa5eb0eb81ee8beb838>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l105::<lambda_8236814038f22a3770d7eb365f42c1bb>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory::getAreaBinding::__l109::<lambda_5be19c9e68037c701d60f79feeb8b6fc>`
Offset | Type | Name
-|-|-|-
0 | (8) `const ClientBindingFactory *const` | __this
8 | (64) `std::unordered_map<std::string,bool>` | map


### `ClientBindingFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `BindingFactory` | baseclass_0
8 | (8) `const ClientInputHandler *` | mClientInputHandler
16 | (8) `IClientInstance *` | mClient
24 | (16) `RectangleArea` | mEmpty
40 | (16) `RectangleArea` | mTurnInteract
56 | (16) `RectangleArea` | mDPadNoTurnInteractArea
72 | (16) `RectangleArea` | mDisableJumpArea
88 | (16) `RectangleArea` | mDisableSneakArea
104 | (16) `RectangleArea` | mGuiPassthrough
120 | (16) `RectangleArea` | mChangingFlightHeight
136 | (16) `RectangleArea` | mLeft
152 | (16) `RectangleArea` | mRight
168 | (16) `RectangleArea` | mUpInvisible
184 | (16) `RectangleArea` | mUp
200 | (16) `RectangleArea` | mDown
216 | (16) `RectangleArea` | mAscend
232 | (16) `RectangleArea` | mMiddleRight
248 | (16) `RectangleArea` | mDescend
264 | (16) `RectangleArea` | mPause
280 | (16) `RectangleArea` | mEmote
296 | (16) `RectangleArea` | mChat
312 | (16) `RectangleArea` | mJump
328 | (16) `RectangleArea` | mUpLeft
344 | (16) `RectangleArea` | mUpRight
360 | (16) `RectangleArea` | mPlayerEffects
376 | (16) `RectangleArea` | mPaddleRight
392 | (16) `RectangleArea` | mPaddleLeft
408 | (16) `RectangleArea` | mSneak
424 | (16) `RectangleArea` | mMobEffects
440 | (16) `RectangleArea` | mToastArea
456 | (16) `RectangleArea` | mCodeBuilder
472 | (16) `RectangleArea` | mImmersiveReader
488 | (16) `RectangleArea` | mKeyJobArea
504 | (16) `RectangleArea` | mSneakOnJK
520 | (16) `RectangleArea` | mStoreArea
536 | (16) `RectangleArea` | mWalkStateArea
552 | (16) `RectangleArea` | mVState0
568 | (16) `RectangleArea` | mMicrophone
584 | (16) `RectangleArea` | mScreenshot
600 | (16) `RectangleArea` | mVoiceTrans
616 | (16) `RectangleArea` | mFoldMenuArea
632 | (16) `RectangleArea` | mReportCheat
648 | (4) `float` | mStoreAreaX
652 | (4) `float` | mStoreAreaY
656 | (8) `glm::tvec2<float,0>` | mInteractCreative
664 | (8) `glm::tvec2<float,0>` | mInteractSurvival


### `ChannelListQuery`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mSkip
4 | (4) `int` | mCount
8 | (32) `std::string` | mChannelName
40 | (1) `ChannelListQueryType` | mType


### `Cube`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mOrigin
12 | (12) `Vec3` | mSize
24 | (12) `Vec3` | mRotation
36 | (12) `Vec3` | mCubePivot
48 | (24) `std::vector<PolygonQuad>` | mPolygons
72 | (16) `mce::Color` | mColor
88 | (1) `bool` | mMirrored
92 | (144) `std::array<Cube::FaceUVData,6>` | mFaceData


### `Cube::FaceUVData`
Offset | Type | Name
-|-|-|-
0 | (8) `Vec2` | mUV
8 | (8) `Vec2` | mUVSize
16 | (4) `int` | mMaterialInstanceListIndex
20 | (1) `bool` | mFaceValid


### `ClientNetworkHandler::handle::__l2::<lambda_3a932b1c4cad8a420efad8f5991d860f>`
Offset | Type | Name
-|-|-|-
0 | (8) `ResourcePackFileDownloaderManager *` | downloadManager
8 | (32) `std::string` | resourceName
40 | (8) `ClientNetworkHandler *const` | __this
48 | (16) `std::weak_ptr<bool>` | weakValid


### `ClientNetworkHandler::handle::__l2::<lambda_57a8c0175a82e2b1f2fddb694a815e8f>`
Offset | Type | Name
-|-|-|-
0 | (152) `const NetworkIdentifier` | source
152 | (32) `std::string` | resourceName
184 | (8) `ClientNetworkHandler *const` | __this
192 | (1) `_BYTE[1]` | packType
200 | (16) `std::weak_ptr<bool>` | weakValid


### `ClientNetworkHandler::handle::__l2::<lambda_f7c9cc170d1b2d687b5ef307e2dd2a5f>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientNetworkHandler *const` | __this
8 | (8) `ResourcePackFileDownloaderManager *` | downloadManager
16 | (8) `const NetworkIdentifier *` | source
24 | (128) `const ResourcePackDataInfoPacket` | packet
152 | (32) `std::string` | resourceName


### `ClientNetworkHandler::handle::__l2::<lambda_f7c9cc170d1b2d687b5ef307e2dd2a5f>::()::__l5::<lambda_c1b3156103bb292e2178303c3a153411>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientNetworkHandler *const` | __this
8 | (8) `ResourcePackFileDownloaderManager *` | downloadManager
16 | (128) `const ResourcePackDataInfoPacket` | packet
144 | (32) `std::string` | resourceName


### `ClientNetworkHandler::handle::__l2::<lambda_d12db79ea14521c577faa9163e217abc>`
Offset | Type | Name
-|-|-|-
0 | (64) `const LabTablePacket` | packet


### `ConnectionRequest`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<UnverifiedCertificate>` | mCertificateData
8 | (8) `std::unique_ptr<Certificate>` | mCertificate
16 | (8) `std::unique_ptr<WebToken>` | mRawToken
24 | (1) `unsigned __int8` | mClientSubId


### `ContainerOpenPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (1) `ContainerID` | mContainerId
41 | (1) `ContainerType` | mType
44 | (12) `NetworkBlockPosition` | mPos
56 | (8) `ActorUniqueID` | mEntityUniqueID


### `ContainerComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerContentChangeListener` | baseclass_0
8 | (8) `std::unique_ptr<Container>` | mContainer
16 | (8) `Mob *` | mListenerShim
24 | (1) `bool` | mCanBeSiphonedFrom
25 | (1) `bool` | mPrivate
26 | (1) `bool` | mRestrictToOwner
32 | (32) `std::string` | mLootTable
64 | (4) `int` | mLootTableSeed


### `ContainerContentChangeListener`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerContentChangeListener_vtbl *` | __vftable


### `ChatOptions::ChatOption`
Offset | Type | Name
-|-|-|-
0 | (8) `Option *` | option
8 | (1) `const ChatCategory` | category
16 | (32) `const std::string` | telemetryName


### `ConstDeserializeDataParams`
Offset | Type | Name
-|-|-|-
0 | (8) `const Json::Value *` | mValue
8 | (112) `const SemVersion` | mPackVersion


### `Core::InputFileStream`
Offset | Type | Name
-|-|-|-
0 | (296) `Core::FileStream` | baseclass_0


### `CommonResourceDefinitionMap`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<HashedString,ActorSkeletalAnimationPtr>` | mActorAnimationMap
64 | (64) `std::unordered_map<HashedString,ActorAnimationControllerPtr>` | mActorAnimationControllerMap
128 | (24) `std::vector<NamedMolangScript>` | mActorAnimateScriptArray
152 | (24) `std::vector<MolangVariableSettings>` | mVariableSettings
176 | (24) `std::vector<HashedString>` | mQueryableGeometryBoneNames


### `ClientBlockPipeline::Transforms`
Offset | Type | Name
-|-|-|-
0 | (64) `Matrix` | mPostTransform


### `ChalkboardBlockActor::CachedMessageData`
Offset | Type | Name
-|-|-|-
0 | (640) `std::array<ChalkboardBlockActor::CachedLineData,16>` | lineData
640 | (4) `unsigned int` | numLines
648 | (32) `std::string` | filteredMessage
680 | (8) `const void *` | cachedFontCompare
688 | (1) `bool` | dirty


### `ChalkboardBlockActor::CachedLineData`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | text
32 | (4) `int` | lineLength


### `ChunkBlockPos`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | x
1 | (1) `unsigned __int8` | z
2 | (2) `ChunkLocalHeight` | y


### `ChunkSource`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkSource_vtbl *` | __vftable
8 | (4) `int` | mChunkSide
16 | (8) `Level *` | mLevel
24 | (8) `Dimension *` | mDimension
32 | (8) `ChunkSource *` | mParent
40 | (8) `std::unique_ptr<ChunkSource>` | mOwnedParent
48 | (8) `LevelChunkBuilderData *` | mLevelChunkBuilderData


### `CubeMap::renderCubeMap::__l17::<lambda_260eef0ecc0f3850dffbb1b638223cba>`
Offset | Type | Name
-|-|-|-
0 | (64) `const Matrix` | cubemapWorldMatrix


### `ClientRenderData`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | mClientSubId


### `CloudRenderObject`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::Mesh>` | mCloudsMesh
16 | (8) `const mce::MaterialPtr *` | mCloudMaterial
24 | (16) `mce::Color` | mCloudColor
40 | (12) `glm::tvec3<float,0>` | mCloudDiff
52 | (4) `float` | mYTranslation


### `ChunkRenderObjectCollection`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<mce::ServerTexture>` | mTextures
24 | (24) `std::vector<ChunkRenderData>` | mChunkQueue
48 | (1296) `std::vector<ChunkLayerRenderObject>[3][18]` | mTerrainLayerChunkQueue
1344 | (4) `unsigned int` | mMaximumChunkVertexCount


### `CrackRenderObjectCollection`
Offset | Type | Name
-|-|-|-
0 | (40) `std::vector<CrackRenderObject,LinearAllocator<CrackRenderObject> >` | mCracks
40 | (72) `mce::TexturePtr` | mAtlasTexture


### `CrackRenderObject`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<mce::Mesh>` | mMesh
16 | (8) `const mce::MaterialPtr *` | mCrackMat
24 | (1) `bool` | mAlphaTest


### `cg::BufferSpan`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::BufferDescription` | mDescription
8 | (8) `const unsigned __int8 *` | mData


### `cg::BufferDescription`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mStride
4 | (4) `unsigned int` | mCount


### `cg::RenderMaterialGroupLoader<std::unordered_map<HashedString,std::shared_ptr<mce::RenderMaterialInfo>,std::hash<HashedString>,std::equal_to<HashedString>,std::allocator<std::pair<HashedString const ,std::shared_ptr<mce::RenderMaterialInfo> > > >,mce::RenderMaterial,mce::RenderMaterialInfo,ResourcePackManager>`
Offset | Type | Name
-|-|-|-


### `cg::RenderFeaturesConfiguration`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | MSAAEnabled
1 | (1) `bool` | TexelAAEnabled
2 | (1) `bool` | HolographicMode
3 | (1) `bool` | AlphaToCoverageSupported
4 | (1) `bool` | VertexFormatRGBA8Supported
5 | (1) `bool` | VertexShaderInstancingSupported
6 | (1) `bool` | LargeVertexShaderUniforms


### `cg::RenderMaterialBase`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::RenderMaterialBase_vtbl *` | __vftable
8 | (16) `std::map<std::string,std::shared_ptr<cg::RenderMaterialBase>>` | mMaterialVariations
24 | (32) `cg::VariationMap` | mVariationMap
56 | (32) `std::string` | mFullMaterialName
88 | (32) `std::string` | mVariantName
120 | (32) `std::string` | mMaterialIdentifier
152 | (16) `std::set<std::string>` | mDefines
168 | (2) `_BYTE[2]` | mStateMask
176 | (32) `std::string` | mShaderHeader
208 | (32) `Core::PathBuffer<std::string >` | mVertexShader
240 | (32) `Core::PathBuffer<std::string >` | mFragmentShader
272 | (32) `Core::PathBuffer<std::string >` | mGeometryShader
304 | (32) `Core::PathBuffer<std::string >` | mVRGeometryShader
336 | (112) `SemVersion` | mVersion


### `cg::VariationMap`
Offset | Type | Name
-|-|-|-
0 | (16) `std::map<std::string,cg::VariationMap>` | mMaterialJsonVariationMap
16 | (16) `Json::Value` | mVariantJson


### `cg::ResourceManager<std::shared_ptr<cg::ImageBuffer>,ResourceLocation,SharedImageBufferTracker,std::shared_ptr<cg::ImageBuffer>,std::map>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::map<ResourceLocation,std::shared_ptr<cg::ImageBuffer>>` | mContainer


### `ContentCatalogPackSource::_collectAllCatalogItems::__l2::<lambda_baa95d9a96c4efb4ae292f92f510cc21>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentCatalogPackSource *const` | __this
8 | (576) `SearchQuery` | query
584 | (16) `std::shared_ptr<unsigned __int64>` | documentsReceived
600 | (16) `std::shared_ptr<unsigned __int64>` | documentsRemoved
616 | (64) `std::function<void __cdecl(void)>` | callback
680 | (16) `std::weak_ptr<bool>` | weakTracker


### `ContentCatalogPackSource::_addCatalogItemsFromSearch::__l9::<lambda_6c2cc72359c8774f2a3e9185f6c63471>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentCatalogPackSource *const` | __this
8 | (576) `SearchQuery` | nextQuery
584 | (16) `std::shared_ptr<unsigned __int64>` | documentsReceived
600 | (16) `std::shared_ptr<unsigned __int64>` | documentsRemoved
616 | (64) `std::function<void __cdecl(void)>` | callback
680 | (16) `std::weak_ptr<bool>` | weakTracker


### `Core::ZipUtils::UnzipSettings`
Offset | Type | Name
-|-|-|-
0 | (48) `Core::ZipUtils::ZipFileRestrictions` | mRestrictions
48 | (1) `bool` | mDeleteZipOnSuccess
49 | (1) `bool` | mPreventOverwrites
56 | (8) `IFileAccess *` | mFileAccess
64 | (32) `std::string` | mPassword
96 | (24) `std::vector<std::string>` | mSelectedPaths


### `ContentAcquisition::searchForDlcIdsByPackIds::__l11::<lambda_b5e7ac097f87844b528ff4a5d3cae47b>`
Offset | Type | Name
-|-|-|-
0 | (136) `const PackIdVersion` | packId
136 | (160) `ContentAcquisition::searchForDlcIdsByPackIds::__l6::<lambda_1d55797dc2ac18165f6bbd44e10719d3>` | onSearchComplete


### `ContentAcquisition::searchForDlcIdsByPackIds::__l6::<lambda_1d55797dc2ac18165f6bbd44e10719d3>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentAcquisition *const` | __this
8 | (16) `std::shared_ptr<`ContentAcquisition::searchForDlcIdsByPackIds'::`2'::SearchTracker>` | tracker
24 | (136) `const PackIdVersion` | packId


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentAcquisition *const` | __this
8 | (16) `std::shared_ptr<`ContentAcquisition::checkStorageRequirements'::`2'::Totals>` | sharedTotals
24 | (24) `const std::vector<DlcId>` | dlcIds
48 | (64) `std::function<void __cdecl(bool,unsigned __int64)>` | callback


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l2::<lambda_23d0a1b8fd39adaa4c0cd04cd9e72a88>::()::__l5::<lambda_fb76be13b8fe047662fa721a3a77c9bb>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | dlcSize
8 | (64) `std::function<void __cdecl(bool,unsigned __int64)>` | callback


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l6::<lambda_5be28da840c3ba3420f6b07d0ad08a78>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentAcquisition *const` | __this
8 | (200) `const DlcId` | dlcId
208 | (88) `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l2::<lambda_23d0a1b8fd39adaa4c0cd04cd9e72a88>` | onFileSizeFound
296 | (8) `std::_List_iterator<std::_List_val<std::_List_simple_types<std::pair<DlcId const ,ContentAcquisition::DownloadHistory> > > >` | pairIt


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l2::<lambda_23d0a1b8fd39adaa4c0cd04cd9e72a88>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<`ContentAcquisition::checkStorageRequirements'::`2'::Totals>` | sharedTotals
16 | (4) `const int` | numRequested
24 | (64) `std::function<void __cdecl(bool,unsigned __int64)>` | callback


### `ContentTracker::fetchFileSize::__l7::<lambda_aa9599aea01d6dd62378f60e02738f2f>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentTracker *const` | __this
8 | (64) `std::function<void __cdecl(unsigned __int64)>` | callback


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l2::<lambda_23d0a1b8fd39adaa4c0cd04cd9e72a88>::()::__l5::<lambda_fb76be13b8fe047662fa721a3a77c9bb>::()::__l5::<lambda_5dde433396ba1836ea97aad5da28a35d>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | dlcSize
8 | (64) `std::function<void __cdecl(bool,unsigned __int64)>` | callback


### `ContentAcquisition::checkStorageRequirements::__l2::<lambda_9e238074f4708f40d39951c6bbb8c3d5>::()::__l2::<lambda_23d0a1b8fd39adaa4c0cd04cd9e72a88>::()::__l5::<lambda_fb76be13b8fe047662fa721a3a77c9bb>::()::__l5::<lambda_06fba6772e5a40319ba863ad66ed81c5>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | dlcSize
8 | (64) `std::function<void __cdecl(bool,unsigned __int64)>` | callback


### `ContentAcquisition::getTitles::__l6::<lambda_6b2ec6fd37d40446a41ee22bbc465839>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentAcquisition *const` | __this
8 | (200) `const DlcId` | dlcId
208 | (88) `ContentAcquisition::getTitles::__l2::<lambda_c6179e0117411f607c7c2f5e595ff517>` | onFileFound
296 | (8) `std::_List_iterator<std::_List_val<std::_List_simple_types<std::pair<DlcId const ,ContentAcquisition::DownloadHistory> > > >` | pairIt


### `ContentAcquisition::getTitles::__l2::<lambda_c6179e0117411f607c7c2f5e595ff517>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | numRequested
8 | (64) `std::function<void __cdecl(std::vector<std::string> const &)>` | callback
72 | (16) `std::shared_ptr<std::vector<std::string> >` | sharedTitles


### `ContentTracker::fetchTitle::__l7::<lambda_580c010aa240fa46c9d3dfd81e8f23e3>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentTracker *const` | __this
8 | (64) `std::function<void __cdecl(std::string const &)>` | callback


### `ContentAcquisition::DownloadCallback`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mShouldCheckExistence
8 | (16) `std::weak_ptr<bool>` | mExistenceTracker
24 | (64) `std::function<void __cdecl(DownloadStateObject &)>` | mCallback


### `ContentAcquisition::_getAvailableDiskFreeSpaceAsync::__l2::<lambda_450f8a999d305d9c737ff19408a1e820>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(unsigned __int64)>` | callback
64 | (16) `std::shared_ptr<unsigned __int64>` | shared_size


### `ContentTracker::fetchFileSize::__l7::<lambda_aa9599aea01d6dd62378f60e02738f2f>::()::__l5::<lambda_b649e17da3516653addd3c4881defd02>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(unsigned __int64)>` | callback
64 | (16) `std::weak_ptr<bool>` | weakExistence


### `ContentTracker::_fetchContentDetails::__l2::<lambda_852b98f00350dbcb07efe1ff2bc71eec>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentTracker *const` | __this
8 | (64) `std::function<void __cdecl(bool)>` | callback
72 | (16) `std::weak_ptr<bool>` | weakExistence


### `ContentTracker::_importLegacyMusicPack::__l2::<lambda_e71312bd262726470a6492efa540d394>`
Offset | Type | Name
-|-|-|-
0 | (8) `ContentTracker *const` | __this
8 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | musicTargetPath
1048 | (16) `std::shared_ptr<enum Core::ZipUtils::UnzipResult>` | sharedErrorCode


### `ContentTracker::_importLegacyMusicPack::__l2::<lambda_4ae52eb2e663e20b64225feacde9ef21>`
Offset | Type | Name
-|-|-|-
0 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | fileToImport
1040 | (1040) `const Core::PathBuffer<Core::StackString<char,1024> >` | musicTargetPath
2080 | (16) `std::shared_ptr<enum Core::ZipUtils::UnzipResult>` | sharedErrorCode


### `ContentAcquisition::DownloadHistory`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mDownloadSize
8 | (1) `bool` | mHasDownloadSize
12 | (4) `_BYTE[4]` | mStatus
16 | (32) `std::string` | mTitle
48 | (1) `bool` | mHasTitle


### `Core::CallbackListeners<int,enum Social::SignInResult>::Listener`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<bool>` | mExistenceTracker
16 | (64) `std::function<void __cdecl(int,enum Social::SignInResult)>` | mCallback
80 | (1) `bool` | mShouldCheckExistence


### `CSHA1`
Offset | Type | Name
-|-|-|-
0 | (20) `unsigned int[5]` | m_state
20 | (8) `unsigned int[2]` | m_count
28 | (4) `unsigned int[1]` | m_reserved0
32 | (64) `unsigned __int8[64]` | m_buffer
96 | (20) `unsigned __int8[20]` | m_digest
116 | (12) `unsigned int[3]` | m_reserved1
128 | (64) `unsigned __int8[64]` | m_workspace
192 | (8) `SHA1_WORKSPACE_BLOCK *` | m_block


### `CloudSaveSystemWrapper::isSettingsOutOfDate::__l13::<lambda_c97df555e43ec3a5e05f628f8af02513>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(Core::Result,bool)>` | callback


### `CloudSaveSystemWrapper::acquireSettingsAsync::__l13::<lambda_7bb126be8a3e79d11e6699d2a94b7bda>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Social::User>` | weakUser
16 | (64) `std::function<void __cdecl(Core::Result)>` | callback


### `CDScopedEvent`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mTag
2 | (2) `_BYTE[2]` | mTagEnd


### `Concurrency::details::_MakeVoidToUnitFunc::__l2::<lambda_052e919cc0e5399df76dff3972c0cac1>`
Offset | Type | Name
-|-|-|-
0 | (64) `const std::function<void __cdecl(void)>` | _Func


### `Concurrency::details::_DefaultPPLTaskScheduler`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::scheduler_interface` | baseclass_0


### `Concurrency::scheduler_interface`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::scheduler_interface_vtbl *` | __vftable


### `Concurrency::details::_Task_impl_base::_ScheduleContinuationTask::__l5::<lambda_713ee8bbd6b08550d59c52695cab5ce3>::()::__l8::<lambda_f25c37099038263181b5186a3fa41b37>`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::details::_ContinuationTaskHandleBase *` | _PTaskHandle
8 | (16) `std::shared_ptr<Concurrency::details::_Task_impl_base>` | _TaskImplPtr


### `Concurrency::invalid_operation`
Offset | Type | Name
-|-|-|-
0 | (24) `std::exception` | baseclass_0


### `cg::details::WorkToken::asLifetime::__l2::<lambda_89b2dae39f23600ad3e66c7a2b82fa2b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<cg::details::WorkToken>` | ptrHandle
16 | (64) `std::function<void __cdecl(void)>` | finalizeCallback


### `CommandListQueue::generateAsync::__l5::<lambda_7ffb9bb526d84acb0ee651a3ebd1913c>`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandListQueue *const` | __this
8 | (64) `std::function<void __cdecl(CommandListTaskContext &)>` | func


### `cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>::execute::__l2::<lambda_2cf6a093770e7d9b1aecca19f5efb284>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<gsl::final_action<std::function<void __cdecl(void)> > >` | token
16 | (64) `const std::function<void __cdecl(dragon::rendering::RenderContext &)>` | callback


### `cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>::{ctor}::__l2::<lambda_6874d52efc76d8cff42ccf8c811d2193>`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1> *const` | __this


### `Core::CpuRingBufferAllocator<dragon::frameobject::PreparedDraw,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<dragon::materials::MaterialUniformOverrides::UniformPair,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `cg::taskorder::TaskBuilderWithActionAndDependencies<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,dragon::rendering::modules::BlitTaskContext,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (224) `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,dragon::rendering::modules::BlitTaskContext>` | baseclass_0
224 | (24) `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,dragon::rendering::modules::BlitTaskContext>`
Offset | Type | Name
-|-|-|-
0 | (32) `cg::taskorder::TaskBuilder<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> >` | baseclass_0
32 | (128) `dragon::rendering::modules::BlitTaskContext` | mContext
160 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &,dragon::rendering::modules::BlitTaskContext const &)>` | mAction


### `cg::taskorder::TaskBuilder<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName


### `cg::math::Rect<unsigned short>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mX
2 | (2) `unsigned __int16` | mY
4 | (2) `unsigned __int16` | mWidth
6 | (2) `unsigned __int16` | mHeight


### `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (24) `std::tuple<dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `cg::taskorder::TaskBuilderWithActionAndDependencies<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void,dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (96) `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void>` | baseclass_0
96 | (56) `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void>`
Offset | Type | Name
-|-|-|-
0 | (32) `cg::taskorder::TaskBuilder<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> >` | baseclass_0
32 | (64) `std::function<void __cdecl(dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext> const &)>` | mAction


### `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (56) `std::tuple<dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `Core::CpuRingBufferAllocator<std::pair<dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> const *,dragon::framegraph::detail::LinkingContext<dragon::rendering::RenderContext> *>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<glm::tvec4<float,0>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<glm::tmat3x3<float,0>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<glm::tmat4x4<float,0>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `cg::taskorder::TaskBuilderWithActionAndDependencies<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void,dragon::framegraph::dependency::BindFramebufferDepth<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (96) `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void>` | baseclass_0
96 | (72) `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindFramebufferDepth<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindFramebufferDepth<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (72) `std::tuple<dragon::framegraph::dependency::BindFramebufferDepth<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindMaterialTexture<dragon::rendering::RenderContext>,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `cg::taskorder::TaskBuilderWithActionAndDependencies<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void,dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >`
Offset | Type | Name
-|-|-|-
0 | (96) `cg::taskorder::TaskBuilderWithAction<dragon::framegraph::ExecutionContext<dragon::rendering::RenderContext>,void>` | baseclass_0
96 | (24) `cg::taskorder::DependencyBuilder<dragon::framegraph::dependency::BindFramebufferColor<dragon::rendering::RenderContext> >` | mDependencies


### `Core::CpuRingBufferAllocator<dragon::frameobject::SceneLightingInformation::PointLight,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `cg::TextureMetaData`
Offset | Type | Name
-|-|-|-
0 | (4) `cg::TextureMetaData::FilterMode` | mFilterMin
4 | (4) `cg::TextureMetaData::FilterMode` | mFilterMag
8 | (4) `cg::TextureMetaData::FilterMode` | mFilterMip
12 | (4) `cg::TextureMetaData::ColorSpace` | mColorSpace
16 | (4) `cg::TextureMetaData::Dimension` | mDimension
20 | (4) `cg::TextureMetaData::WrapMode` | mWrapU
24 | (4) `cg::TextureMetaData::WrapMode` | mWrapV
28 | (4) `int` | mNumSlices


### `ChunkRenderObjectCollection::addToChunkQueue::__l2::<lambda_4669a033a94b2cbc882de43740c3bcf3>`
Offset | Type | Name
-|-|-|-


### `ChunkRenderData`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<int,0>` | mPosition
16 | (8) `long double` | mReadyTimeDiff
24 | (24) `const std::variant<std::monostate,std::shared_ptr<mce::IndexBufferContainer>,std::shared_ptr<RenderChunkDirectIndexData> >` | mChunkIndices
48 | (24) `const std::variant<std::monostate,std::shared_ptr<mce::Mesh>,std::shared_ptr<RenderChunkDirectVertexData> >` | mChunkMesh
72 | (16) `gsl::span<mce::PointLight const ,-1>` | mPointLights


### `CameraShakeEvent`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mIntensity
4 | (4) `float` | mDuration


### `CameraShakeSystem::tick::__l2::<lambda_ff1179873d2d698a099b81d15231fa79>`
Offset | Type | Name
-|-|-|-
0 | (8) `CameraShakeSystem *const` | __this


### `CommandParameterData`
Offset | Type | Name
-|-|-|-
0 | (2) `typeid_t<CommandRegistry>` | mTypeIndex
8 | (8) `bool (__fastcall *)(CommandRegistry *this, void *, const CommandRegistry::ParseToken *, const CommandOrigin *, int, std::string *, std::vector<std::string> *)` | mParse
16 | (32) `std::string` | mName
48 | (8) `const char *` | mEnumNameOrPostfix
56 | (4) `int` | mEnumOrPostfixSymbol
60 | (4) `CommandParameterDataType` | mParamType
64 | (4) `int` | mOffset
68 | (4) `int` | mSetOffset
72 | (1) `bool` | mIsOptional
73 | (1) `CommandParameterOption` | mOptions


### `CommandSelectorResults<Player>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<std::vector<Actor *> >` | mTargets


### `CommandOutputParameter`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mString
32 | (4) `int` | mCount


### `ChunkLoadedRequest`
Offset | Type | Name
-|-|-|-
0 | (1) `AreaType` | mAreaType
4 | (48) `Bounds` | mBounds
56 | (32) `std::string` | mTickingAreaName
88 | (32) `std::string` | mSerializationId
120 | (8) `std::unique_ptr<IChunkLoadedAction>` | mChunkLoadedAction


### `CommandAreaFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `Dimension *` | mDimension


### `cg::TextureSetLayerDefinition`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_0
16 | (208) `std::variant<ResourceLocationPair,ColorChannel,mce::Color>` | mData
224 | (4) `cg::TextureSetLayerType` | mLayerType


### `ComponentItem::_validateServerSchemaAndInitItem::__l2::<lambda_8fbf7210d948bc9a2c7c196ed13498ff>`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentItem *const` | __this
8 | (112) `SemVersion` | version


### `ComponentItem::_validateClientSchemaAndInitItem::__l2::<lambda_e04caa0b9c3fce21a3adffae430565da>`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentItem *const` | __this
8 | (112) `SemVersion` | version


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_4b0d6bde792ed619e67322018f9b43c7>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_646300c760a21a5dee87bd50ffc76f84>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_bde458400d5e0c936f319b6fbc51f7ea>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_08a8fb2c819f7557ca2eb39a18b10555>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_7ac0608cb5cbb757eac814257996d998>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_27740b06e312776918dffed8bff42b16>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_6bba8aa0feff95e899fc6a8a254ef7bc>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_700e819f7949a3cf2c4a087a7587af4f>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_cb4ad2fefaa769f49c3ee0dd42da1168>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_5d561c02c26be577f9c5dd22c1d3cc29>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_d887d12a5e8c683324eafb3aff797194>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_2ae06341078d5910279305cbe94f0403>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_d430a32fa966086497fdee2689d5f072>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_2e61ce2ecee42b8c801d2a0fce372345>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_f11da43554209a966dd612f49a500c13>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_d138d2cc7881ec912693e17053aa36d3>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_08c154647375c28c098b616470505c81>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_8d2b9f4c977ef7bcf18b00933e8d133c>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_720d686375472b328e72c11b0a4529c9>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_f00f608ba659db531edffcb30f33581b>`
Offset | Type | Name
-|-|-|-


### `CerealItemComponentFactory::registerComponent::__l2::<lambda_4f2170e72cbb54e6a6a019874716cd58>`
Offset | Type | Name
-|-|-|-


### `CappedSurfaceAttributes`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<CappedSurfaceAttributes::MaterialLayer>` | mFloorMaterials
24 | (24) `std::vector<CappedSurfaceAttributes::MaterialLayer>` | mCeilingMaterials
48 | (8) `const Block *` | mSeaMaterial
56 | (8) `const Block *` | mFoundationMaterial
64 | (8) `const Block *` | mBeachMaterial
72 | (1) `bool` | mIsInitialized


### `CommandRegistry::Parser`
Offset | Type | Name
-|-|-|-
0 | (8) `const CommandRegistry *` | mRegistry
8 | (8) `const CommandRegistry::ParseTable *` | mParseTable
16 | (40) `std::deque<std::pair<CommandRegistry::Symbol,CommandRegistry::ParseToken *>>` | mStack
56 | (32) `CommandRegistry::LexicalToken` | mNext
88 | (32) `std::string` | mInput
120 | (8) `std::unique_ptr<CommandRegistry::ParseToken>` | mRoot
128 | (32) `std::string` | mError
160 | (24) `std::vector<std::string>` | mErrorParams
184 | (4) `int` | mVersion
188 | (1) `bool` | mGenerateParams
189 | (1) `bool` | mBreakAtEnd


### `CommandRegistry::LexicalToken`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mText
8 | (4) `unsigned int` | mLength
12 | (4) `CommandRegistry::Symbol` | mType
16 | (4) `CommandRegistry::Symbol` | mIdentifierInfo
24 | (8) `const CommandRegistry *` | mRegistry


### `ContextAccessor`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | mTypeId
8 | (8) `std::unique_ptr<ContextAccessor::TypeBase>` | mContext


### `CompoundTagVariant`
Offset | Type | Name
-|-|-|-
0 | (48) `std::variant<EndTag,ByteTag,ShortTag,IntTag,Int64Tag,FloatTag,DoubleTag,ByteArrayTag,StringTag,ListTag,CompoundTag,IntArrayTag>` | mTagStorage


### `CompoundTagVariant::copy::__l2::<lambda_847acbaa2673dfafb4b947487bdf32fd>`
Offset | Type | Name
-|-|-|-


### `ClassroomModeNetworkHandler::onWebsocketRequest::__l13::<lambda_f8f06f33a691ac69d078ed77b77cf8f8>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClassroomModeNetworkHandler *const` | __this
8 | (32) `const std::string` | serverAddress
40 | (64) `std::function<void __cdecl(void)>` | errorCallback


### `ClassroomModeNetworkHandler::_connect::__l2::<lambda_4c552053559105a51c96d1cc72ebc426>`
Offset | Type | Name
-|-|-|-
0 | (8) `ClassroomModeNetworkHandler *const` | __this
8 | (32) `const std::string` | address


### `CommandOriginData`
Offset | Type | Name
-|-|-|-
0 | (1) `CommandOriginType` | mType
8 | (16) `mce::UUID` | mUUID
24 | (32) `std::string` | mRequestId
56 | (8) `__int64` | mPlayerId


### `CommandOutputMessage`
Offset | Type | Name
-|-|-|-
0 | (4) `CommandOutputMessageType` | mType
8 | (32) `std::string` | mMessageId
40 | (24) `std::vector<std::string>` | mParams


### `CraftingDataEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Recipe>` | mRecipe
8 | (4) `int` | mItemData
12 | (4) `int` | mItemAux
16 | (48) `HashedString` | mTag
64 | (240) `ItemInstance` | mItemResult
304 | (4) `CraftingDataEntryType` | mEntryType


### `CreativeItemEntry`
Offset | Type | Name
-|-|-|-
0 | (16) `Bedrock::EnableNonOwnerReferences` | baseclass_0
16 | (8) `CreativeItemRegistry *` | mRegistry
24 | (4) `unsigned int` | mGroupIndex
28 | (4) `TypedServerNetId<CreativeItemNetIdTag,unsigned int,0>` | mCreativeNetId
32 | (240) `ItemInstance` | mItemInstance
272 | (4) `unsigned int` | mIndex


### `ConnectionDefinition`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | ipv4Port
2 | (2) `unsigned __int16` | ipv6Port
4 | (4) `ConnectionDefinition::PortBusyFallbackPolicy` | fallback
8 | (4) `int` | maxNumPlayers
12 | (4) `int` | maxNumConnections


### `Connector::NatPunchInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isValid
1 | (1) `bool` | addressIsDirty
2 | (1) `bool` | succeeded
8 | (136) `RakNet::SystemAddress` | externalAddress
144 | (4) `unsigned int` | startPingSentTime
148 | (4) `unsigned int` | pingSentTime
152 | (4) `unsigned int` | startPongReceivedTime
156 | (4) `unsigned int` | pongReceivedTime


### `CommandBlockUpdatePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (12) `NetworkBlockPosition` | mBlockPos
52 | (2) `_BYTE[2]` | mMode
54 | (1) `bool` | mRedstoneMode
55 | (1) `bool` | mIsConditional
56 | (8) `ActorRuntimeID` | mEntityId
64 | (32) `std::string` | mCommand
96 | (32) `std::string` | mLastOutput
128 | (32) `std::string` | mName
160 | (4) `int` | mTickDelay
164 | (1) `bool` | mTrackOutput
165 | (1) `bool` | mExecuteOnFirstTick
166 | (1) `bool` | mIsBlock


### `ClientboundMapItemDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<ActorUniqueID>` | mMapIds
64 | (1) `char` | mScale
72 | (24) `std::vector<std::shared_ptr<MapDecoration>>` | mDecorations
96 | (24) `std::vector<MapItemTrackedActor::UniqueId>` | mUniqueIds
120 | (4) `int` | mStartX
124 | (4) `int` | mStartY
128 | (1) `unsigned __int8` | mDimension
132 | (4) `int` | mWidth
136 | (4) `int` | mHeight
140 | (4) `ClientboundMapItemDataPacket::Type` | mType
144 | (24) `std::vector<unsigned int>` | mMapPixels
168 | (1) `bool` | mLocked


### `ConditionalBandwidthOptimization`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mMaxOptimizedDistance
8 | (8) `unsigned __int64` | mMaxDroppedTicks
16 | (1) `bool` | mUseMotionPredictionHints
24 | (64) `ActorFilterGroup` | mConditions


### `ConditionalBandwidthOptimizationComponent`
Offset | Type | Name
-|-|-|-
0 | (88) `ConditionalBandwidthOptimization` | mDefaultValues
88 | (24) `std::vector<ConditionalBandwidthOptimization>` | mConditionalValues
112 | (8) `Tick` | mLastRequestedValuesTick
120 | (88) `ConditionalBandwidthOptimization` | mCachedOptimizationValues


### `ContentTierManager::ValidatorRegistry::ValidatorRegistryValidators`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ContentTierIncompatibleReason __cdecl(PackInstance const &,ContentTierInfo const &)>` | mFuncPackValidator
64 | (64) `std::function<ContentTierIncompatibleReason __cdecl(SubpackInfo const &,ContentTierInfo const &)>` | mFuncSubpackValidator


### `Crypto::Symmetric::Symmetric`
Offset | Type | Name
-|-|-|-
0 | (8) `Crypto::Symmetric::ISystemInterface` | baseclass_0
8 | (8) `std::unique_ptr<Crypto::Symmetric::ISystemInterface>` | mInterface


### `Crypto::Symmetric::ISystemInterface`
Offset | Type | Name
-|-|-|-
0 | (8) `Crypto::Symmetric::ISystemInterface_vtbl *` | __vftable


### `Core::ExcludedPath`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | mPath
32 | (1) `bool` | mCopyLooseFile


### `Core::ZipUtils::ZipSettings`
Offset | Type | Name
-|-|-|-
0 | (48) `Core::ZipUtils::ZipFileRestrictions` | mRestrictions
48 | (1) `bool` | mZipDirectoryContents
49 | (1) `bool` | mSkipInaccessibleFiles
52 | (4) `int` | mCompressionLevel
56 | (8) `IFileAccess *` | mFileAccess
64 | (32) `std::string` | mPassword
96 | (4) `int` | mZip64


### `Core::FileSystem::copyFile::__l2::<lambda_98acb2cebb3139e7dcaf8bae69363f0a>`
Offset | Type | Name
-|-|-|-


### `Core::UnzipFile`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ZlibFileAccessWrapper>` | mZipFileSystemWrapper
8 | (8) `std::unique_ptr<Core::UnzipInternals>` | mZipFile


### `ClientBlobCache::Server::Blob`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int64` | id
8 | (32) `const std::string` | data


### `CommandIntegerRange`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMinValue
4 | (4) `int` | mMaxValue
8 | (1) `bool` | mInvert


### `CommandRegistry::parseSelector::__l243::<lambda_c6bfa6ab44c8dc5137236fba12271e1d>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::pair<float,float>` | xRotation


### `CommandRegistry::Signature`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | description
64 | (24) `std::vector<CommandRegistry::Overload>` | overloads
88 | (1) `_BYTE[1]` | permissionLevel
92 | (4) `CommandRegistry::Symbol` | commandSymbol
96 | (4) `CommandRegistry::Symbol` | commandAliasEnum
100 | (1) `CommandFlag` | flags
104 | (4) `int` | firstRule
108 | (4) `int` | firstFactorization
112 | (4) `int` | firstOptional
116 | (1) `bool` | runnable


### `CommandLexer`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | mInput
8 | (16) `CommandLexer::Token` | mToken


### `CommandLexer::Token`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | text
8 | (4) `unsigned int` | length
12 | (4) `CommandLexer::TokenType` | type


### `CommandRegistry::RegistryState`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | signatureCount
4 | (4) `unsigned int` | enumValueCount
8 | (4) `unsigned int` | postfixCount
12 | (4) `unsigned int` | enumCount
16 | (4) `unsigned int` | factorizationCount
20 | (4) `unsigned int` | optionalCount
24 | (4) `unsigned int` | ruleCount
28 | (4) `unsigned int` | softEnumCount
32 | (4) `unsigned int` | constraintCount
40 | (24) `std::vector<unsigned int>` | constrainedValueCount
64 | (24) `std::vector<unsigned int>` | softEnumValuesCount


### `CommandItem`
Offset | Type | Name
-|-|-|-
0 | (8) `$F8070BC88C1447D17F82F88E7F729FB1` | ___u0


### `CloneCommand::execute::__l2::CloneBlockInfo`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | mPos
16 | (8) `const Block *` | mState
24 | (8) `std::unique_ptr<CompoundTag>` | mTag


### `ClientBlobCache::Server::TransferBuilder`
Offset | Type | Name
-|-|-|-
0 | (224) `ClientBlobCache::Server::ActiveTransfer` | mTransfer


### `ClientBlobCache::Server::ActiveTransfer`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientBlobCache::Server::ActiveTransfersManager *` | mCache
8 | (152) `NetworkIdentifier` | mOwner
160 | (64) `std::unordered_map<unsigned __int64,std::shared_ptr<ClientBlobCache::Server::Blob>>` | mIdsWaitingForACK


### `ChunkPositionAndDimension`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos` | mPos
8 | (4) `AutomaticID<Dimension,int>` | mType


### `ContainerDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (4) `int` | mSize
12 | (1) `bool` | mCanBesiphonedFrom
13 | (1) `bool` | mPrivate
14 | (1) `bool` | mRestrictToOwner
16 | (4) `int` | mSlotsPerStrength
20 | (1) `ContainerType` | mContainerType


### `CrashDumpEventData`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mTag0
2 | (2) `_BYTE[2]` | mTag1
4 | (4) `int` | mEventThreadId


### `CompoundTagUpdaterBuilder::match::__l2::<lambda_d6e645fd0760b5869a1c1fbc97f375e0>`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | tagName
32 | (32) `std::string` | pattern


### `CompoundTagUpdaterBuilder::tryEdit::__l2::<lambda_331080c9253f49c0e39d20a115988e3c>`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | tagName
32 | (64) `std::function<void __cdecl(CompoundTagEditHelper &)>` | update


### `CompoundTagUpdaterBuilder::rename::__l2::<lambda_4bed7a15ca03b6882a582c4103e2a48e>`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | tagName
32 | (32) `const std::string` | newTagName


### `Core::ZipUtils::ZipProgressList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<Core::ZipUtils::ZipProgress>>` | mZipProgress
24 | (80) `std::mutex` | mProgressLock


### `ClientParticleInitializationComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ParticleInitializationData>` | mParticleInitializationData


### `ContainerValidation::assignValidationDelegates::__l12::<lambda_f3de1f01db6586c03466a09e7bf05768>`
Offset | Type | Name
-|-|-|-
0 | (40) `const ContainerScreenContext` | screenContext


### `CraftableCompounds`
Offset | Type | Name
-|-|-|-
0 | (8) `CraftableCompounds_vtbl *` | __vftable
8 | (64) `std::unordered_map<std::string,ItemStack>` | mComponentsToCompound
72 | (64) `std::unordered_map<int,std::vector<ItemStack>>` | mCompoundToComponents
136 | (64) `std::unordered_map<std::string,enum LabTableReactionType>` | mComponentsToReaction
200 | (64) `std::unordered_map<std::string,enum CompoundContainerType>` | mComponentsToContainerOverride


### `ChemistryIngredient`
Offset | Type | Name
-|-|-|-
0 | (240) `ItemInstance` | mItem


### `CreateContainerItemScope`
Offset | Type | Name
-|-|-|-
0 | (8) `const SlotData *const` | mSrcSlot
8 | (16) `std::shared_ptr<ContainerController>` | mCreatedItemContainerController
24 | (16) `ItemStackRequestScope` | mItemStackRequestScope


### `Container`
Offset | Type | Name
-|-|-|-
0 | (8) `Container_vtbl *` | __vftable
8 | (1) `ContainerType` | mContainerType
9 | (1) `ContainerType` | mGameplayContainerType
16 | (64) `std::unordered_set<ContainerContentChangeListener *>` | mContentChangeListeners
80 | (64) `std::unordered_set<ContainerSizeChangeListener *>` | mSizeChangeListeners
144 | (40) `std::deque<std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>>` | mTransactionContextStack
184 | (32) `std::string` | mName
216 | (1) `bool` | mCustomName
220 | (4) `TypedRuntimeId<ContainerRuntimeIdTag,unsigned int,0>` | mContainerRuntimeId


### `ContainerManagerController`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerManagerController_vtbl *` | __vftable
8 | (16) `std::enable_shared_from_this<ContainerManagerController>` | baseclass_8
24 | (16) `std::weak_ptr<ContainerManagerModel>` | mContainerManagerModel
40 | (64) `std::unordered_map<std::string,std::shared_ptr<ContainerController>>` | mContainers
104 | (24) `std::vector<ContainerSplitControl>` | mContainerSplitItemStackItems
128 | (4) `int` | mSplitItemRemainder
132 | (1) `bool` | mContainerDirty
133 | (1) `bool` | mContainersClosed


### `ChestBlockTryPairEvent`
Offset | Type | Name
-|-|-|-
0 | (16) `const std::shared_ptr<BlockSourceHandle>` | mBlockSourceHandle
16 | (12) `const Vec3` | mBlockPos
28 | (12) `const Vec3` | mOtherBlockPos


### `CraftingContainer`
Offset | Type | Name
-|-|-|-
0 | (224) `Container` | baseclass_0
224 | (24) `std::vector<ItemStack>` | mItems
248 | (4) `int` | mWidth


### `ContainerWeakRef`
Offset | Type | Name
-|-|-|-
0 | (8) `ActorUniqueID` | mContainerActor
8 | (4) `ActorContainerType` | mActorContainerType
12 | (12) `BlockPos` | mBlockPosition
24 | (4) `TypedRuntimeId<ContainerRuntimeIdTag,unsigned int,0>` | mContainerRuntimeId


### `ContainerWeakRefData`
Offset | Type | Name
-|-|-|-
0 | (8) `Container *` | mContainer
8 | (8) `Actor *` | mActor
16 | (8) `BlockActor *` | mBlockActor


### `ContainerScreenContextComponent`
Offset | Type | Name
-|-|-|-
0 | (40) `ContainerScreenContext` | mContext


### `ConnectionComponent`
Offset | Type | Name
-|-|-|-
0 | (16) `std::set<HashedString>` | mConnection


### `CompoundTagUpdaterBuilder`
Offset | Type | Name
-|-|-|-
0 | (8) `CompoundTagUpdater *` | mUpdater


### `CommandSoftEnumRegistry`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandRegistry *` | mRegistry


### `CachedComponentData`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mFriction
4 | (4) `float` | mDestroySpeed
8 | (4) `int` | mBurnOdds
12 | (4) `int` | mFlameOdds
16 | (1) `Brightness` | mLight
17 | (1) `Brightness` | mLightEmission
18 | (1) `bool` | mIsSolid


### `ChunkViewSource`
Offset | Type | Name
-|-|-|-
0 | (56) `ChunkSource` | baseclass_0
56 | (4) `_BYTE[4]` | mParentLoadMode
64 | (296) `GridArea<std::shared_ptr<LevelChunk> >` | mArea
360 | (8) `ChunkSource *` | mMainSource


### `ColumnCachedData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | grassColor
4 | (4) `int` | waterColor


### `ConsoleChunkBlender`
Offset | Type | Name
-|-|-|-
0 | (32) `SpinLock` | mSpinLock
32 | (16) `float[2][2]` | mInterpCorners
48 | (1024) `float[16][16]` | mInterpTable


### `CircuitComponentList::Item`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseCircuitComponent *` | mComponent
8 | (4) `int` | mDampening
12 | (12) `BlockPos` | mPos
24 | (1) `unsigned __int8` | mDirection
25 | (1) `bool` | mDirectlyPowered
28 | (4) `int` | mData


### `CircuitSceneGraph::PendingEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseCircuitComponent *` | mRawComponentPtr
8 | (8) `std::unique_ptr<BaseCircuitComponent>` | mComponent
16 | (12) `BlockPos` | mPos


### `CircuitTrackingInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `CircuitTrackingInfo::Entry` | mCurrent
32 | (32) `CircuitTrackingInfo::Entry` | mPower
64 | (32) `CircuitTrackingInfo::Entry` | mNearest
96 | (32) `CircuitTrackingInfo::Entry` | m2ndNearest
128 | (4) `int` | mDampening
132 | (1) `bool` | mDirectlyPowered
136 | (4) `int` | mData


### `CircuitTrackingInfo::Entry`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseCircuitComponent *` | mComponent
8 | (12) `BlockPos` | mPos
20 | (1) `unsigned __int8` | mDirection
24 | (8) `unsigned __int64` | mTypeID


### `CircuitComponentList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<CircuitComponentList::Item>` | mComponents


### `Concurrency::task_options`
Offset | Type | Name
-|-|-|-
0 | (24) `Concurrency::scheduler_ptr` | _M_Scheduler
24 | (8) `Concurrency::cancellation_token` | _M_CancellationToken
32 | (16) `Concurrency::task_continuation_context` | _M_ContinuationContext
48 | (40) `Concurrency::details::_Internal_task_options` | _M_InternalTaskOptions
88 | (1) `bool` | _M_HasCancellationToken
89 | (1) `bool` | _M_HasScheduler


### `Concurrency::scheduler_ptr`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Concurrency::scheduler_interface>` | _M_sharedScheduler
16 | (8) `Concurrency::scheduler_interface *` | _M_scheduler


### `Concurrency::cancellation_token`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::details::_CancellationTokenState *` | _M_Impl


### `Concurrency::task_continuation_context`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::details::_ContextCallback` | baseclass_0
8 | (1) `bool` | _M_RunInline


### `Concurrency::details::_ContextCallback`
Offset | Type | Name
-|-|-|-
0 | (8) `Concurrency::details::_ContextCallback::<unnamed_type__M_context>` | _M_context


### `Concurrency::details::_ContextCallback::<unnamed_type__M_context>`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | _M_pContextCallback
1 | (8) `unsigned __int64` | _M_captureMethod


### `Concurrency::details::_Internal_task_options`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | _M_hasPresetCreationCallstack
8 | (32) `Concurrency::details::_TaskCreationCallstack` | _M_presetCreationCallstack


### `Concurrency::details::_TaskCreationCallstack`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | _M_SingleFrame
8 | (24) `std::vector<void *>` | _M_frames


### `ChangeModelPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mEntityId
48 | (32) `std::string` | mModelName


### `ChangeModelTexturePacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mEntityId
48 | (32) `std::string` | mModelTexture
80 | (8) `ActorUniqueID` | mSkinOwnerId
88 | (1) `modelTextureType` | mType


### `CustomPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mContent


### `Crypto::Hash::md5`
Offset | Type | Name
-|-|-|-
0 | (8) `Crypto::Hash::IHash` | baseclass_0
8 | (4) `unsigned int` | _lo
12 | (4) `unsigned int` | _hi
16 | (4) `unsigned int` | _a
20 | (4) `unsigned int` | _b
24 | (4) `unsigned int` | _c
28 | (4) `unsigned int` | _d
32 | (64) `unsigned __int8[64]` | _buffer
96 | (64) `unsigned int[16]` | _block


### `ConfirmSkinPacket::ConfirmSkinEntry`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mValid
8 | (16) `mce::UUID` | mUUID
24 | (32) `std::string` | mSkinImageData


### `Core::FilePathManager`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsDedicatedServer
8 | (32) `Core::PathBuffer<std::string >` | mLibraryRoot
40 | (32) `Core::PathBuffer<std::string >` | mDocumentRoot
72 | (32) `Core::PathBuffer<std::string >` | mRoot
104 | (32) `Core::PathBuffer<std::string >` | mPackagePath
136 | (32) `Core::PathBuffer<std::string >` | mDataUrl
168 | (32) `Core::PathBuffer<std::string >` | mExternalFilePath
200 | (32) `Core::PathBuffer<std::string >` | mTemporaryFilePath
232 | (32) `Core::PathBuffer<std::string >` | mCacheFilePath
264 | (32) `Core::PathBuffer<std::string >` | mSettingsPath


### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource> >::CacheDefaultFactory<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource> >`
Offset | Type | Name
-|-|-|-


### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource> >::CacheDefaultFactory<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource> >`
Offset | Type | Name
-|-|-|-


### `Core::CpuRingBufferAllocator<std::_Tree_node<std::pair<dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> const * const,std::unique_ptr<dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext>,std::default_delete<dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> > > >,void *>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<std::_Tree_node<int,void *>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<dragon::framegraph::detail::AbstractPass<dragon::rendering::RenderContext> const *,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `Core::CpuRingBufferAllocator<std::_Tree_node<std::pair<dragon::framegraph::detail::AbstractResource<dragon::rendering::RenderContext> const * const,dragon::res::ServerTexture>,void *>,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::basic_string<char,std::char_traits<char>,std::allocator<char> > const &,std::vector<cg::GroupPoolDescription,std::allocator<cg::GroupPoolDescription> > const &> > >::TaskDispatcherExecution,0>`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > > *` | mDispatcher


### `cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>::{ctor}::__l2::<lambda_38b95ff2bedc8501d3bbf586eabb0e1e>`
Offset | Type | Name
-|-|-|-
0 | (8) `cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1> *const` | __this


### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource> >::CacheDefaultFactory<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource> >`
Offset | Type | Name
-|-|-|-


### `ClimateAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mTemperature
4 | (4) `float` | mDownfall
8 | (4) `float` | mRedSporeDensity
12 | (4) `float` | mBlueSporeDensity
16 | (4) `float` | mAshDensity
20 | (4) `float` | mWhiteAshDensity
24 | (4) `float` | mSnowAccumulationMin
28 | (4) `float` | mSnowAccumulationMax


### `CanopyVariantBuilder::buildCanopyVariant::__l2::<lambda_d70ff2a45c19225400bf0b1fd63f432d>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ITreeCanopyWrapper & __cdecl(FeatureLoading::ConcreteFeatureHolder<VanillaTreeFeature> *)>` | canopyAccessor


### `CachedBiomeSource<VanillaOverworldBiomeSource>`
Offset | Type | Name
-|-|-|-
0 | (40) `VanillaOverworldBiomeSource` | baseclass_0
40 | (16) `std::shared_ptr<BiomeSourceGetBiomeCache>` | mCache


### `CameraItemComponentLegacy`
Offset | Type | Name
-|-|-|-
0 | (8) `ICameraItemComponent` | baseclass_0
8 | (4) `float` | mBlackBarsDuration
12 | (4) `float` | mBlackBarsScreenRatio
16 | (4) `float` | mShutterScreenRatio
20 | (4) `float` | mShutterDuration
24 | (4) `float` | mPictureDuration
28 | (4) `float` | mSlideAwayDuration
32 | (1) `bool` | mPlacingTripod
40 | (8) `unsigned __int64` | mPlacingTripodClientTick
48 | (8) `unsigned __int64` | mPlacingTripodServerTick
56 | (8) `CameraCallbacks *` | mCallbacks


### `CustomBlob`
Offset | Type | Name
-|-|-|-
0 | (8) `IDxcBlob` | baseclass_0
8 | (8) `void *` | data
16 | (8) `unsigned __int64` | size


### `CaretLocationData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | location


### `ConnectionStateData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isConnected


### `ChangeUserData`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | restrictToControllerIdChange


### `compression_state`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int8 *` | input
8 | (8) `unsigned __int64` | input_len
16 | (4) `unsigned int` | output_len
20 | (1024) `unsigned __int8[1024]` | output


### `Core::FileStorageArea::_beginTransaction::__l5::<lambda_299c7b1db8373c80435acd53fe6c3bdb>`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FileStorageArea *const` | __this


### `Core::TransactionFrame`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Core::FileSystemImpl>` | msptTransaction
16 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | mCleanPath
1056 | (72) `Core::Result` | mResult


### `Core::FileSystemImpl::renameFileOrDirectory::__l15::<lambda_455282c5f2c9971e330b5e9517f1b8d0>`
Offset | Type | Name
-|-|-|-
0 | (32) `const Core::Path` | sourceEntryPath
32 | (32) `const Core::Path` | targetEntryPath


### `Core::FileSystemImpl::renameFileOrDirectory::__l18::<lambda_a88ce22f21287b4119b5de040b24fbd2>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Core::PathPart>` | sourceDirectoryRelativeFiles
24 | (32) `const Core::Path` | sourceEntryPath
56 | (32) `const Core::Path` | targetEntryPath


### `Core::FlatFileSearchResult`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Core::FlatFileManifest const >` | mManifest
16 | (8) `const Core::FlatFileManifestInfo *` | mManifestInfoEntry


### `Core::Result::either::__l2::<lambda_febe3dbf8fbc4fa631ce502a657ef1ea>`
Offset | Type | Name
-|-|-|-
0 | (72) `Core::Result` | r1
72 | (72) `Core::Result` | r2


### `CrashDump_AllData`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | mStartSentinel
8 | (4) `int` | mFormatSize
12 | (4) `int` | mDataBlobCount
16 | (1372) `char[1372]` | mFormat
1388 | (520) `CrashDumpGlobalData` | mGlobalData
1908 | (32784) `CrashDumpEventDataArray` | mEventDataArray
34692 | (8208) `CrashDumpKeyValueDataArray` | mKeyValueDataArray
42900 | (272) `CrashDumpFrameDataArray` | mFrameDataArray
43172 | (1552) `CrashDumpGameplayDataArray` | mGameplayDataArray
44724 | (1040) `CrashDumpRenderDataArray` | mRenderDataArray
45764 | (272) `CrashDumpPlayerDataArray` | mPlayerDataArray
46036 | (400) `CrashDumpFirstAssertsDataArray` | mFirstAssertsDataArray
46436 | (400) `CrashDumpLastAssertsDataArray` | mLastAssertsDataArray
46836 | (8) `__int64` | mEndSentinel


### `CrashDumpGlobalData`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (32) `char[32]` | mPlatform
48 | (32) `char[32]` | mGameVersion
80 | (4) `int` | mResourcePack
84 | (4) `int` | mWorldSeed
88 | (4) `int` | mRegion
92 | (4) `int` | __pad
96 | (8) `unsigned __int64` | mTotalMemory
104 | (16) `_GUID` | mDeviceSessionId
120 | (16) `_GUID` | mDeviceId
136 | (256) `char[256]` | mResourcePackIds
392 | (128) `char[128]` | mMainSceneStack


### `CrashDumpLogBlobHeader`
Offset | Type | Name
-|-|-|-
0 | (4) `CrashDumpLogSectionType` | mType
4 | (4) `unsigned int` | mSize
8 | (4) `unsigned int` | mIndex
12 | (4) `unsigned int` | mFieldCount


### `CrashDumpEventDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (32768) `CrashDumpEventData[4096]` | mEventData


### `CrashDumpKeyValueDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (8192) `CrashDumpKeyValueData[512]` | mKeyValueData


### `CrashDumpFrameDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (256) `CrashDumpFrameData[8]` | mFrameData


### `CrashDumpFrameData`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | mNumControllers
4 | (4) `unsigned int` | mPrimaryControllerId
8 | (8) `unsigned __int64` | mFreeMemory
16 | (4) `float` | mX
20 | (4) `float` | mY
24 | (4) `float` | mZ
28 | (4) `float` | mDirection


### `CrashDumpGameplayDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (1536) `CrashDumpGameplayData[128]` | mGameplayData


### `CrashDumpRenderDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (1024) `CrashDumpRenderData[128]` | mRenderData


### `CrashDumpRenderData`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mTag
2 | (2) `__int16` | mPad
4 | (4) `int` | mObjectId


### `CrashDumpPlayerDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (256) `CrashDumpPlayerData[4]` | mPlayerData


### `CrashDumpPlayerData`
Offset | Type | Name
-|-|-|-
0 | (64) `char[64]` | mSceneStack


### `CrashDumpFirstAssertsDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (384) `CrashDumpAssertData[3]` | mAssertData


### `CrashDumpAssertData`
Offset | Type | Name
-|-|-|-
0 | (128) `char[128]` | mAssertMessage


### `CrashDumpLastAssertsDataArray`
Offset | Type | Name
-|-|-|-
0 | (16) `CrashDumpLogBlobHeader` | baseclass_0
16 | (384) `CrashDumpAssertData[3]` | mAssertData


### `CFF_ParserRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_LibraryRec_ *` | library
8 | (8) `unsigned __int8 *` | start
16 | (8) `unsigned __int8 *` | limit
24 | (8) `unsigned __int8 *` | cursor
32 | (8) `unsigned __int8 **` | stack
40 | (8) `unsigned __int8 **` | top
48 | (4) `unsigned int` | stackSize
52 | (4) `unsigned int` | object_code
56 | (8) `void *` | object
64 | (2) `unsigned __int16` | num_designs
66 | (2) `unsigned __int16` | num_axes


### `CFF_IndexRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_StreamRec_ *` | stream
8 | (4) `unsigned int` | start
12 | (4) `unsigned int` | hdr_size
16 | (4) `unsigned int` | count
20 | (1) `unsigned __int8` | off_size
24 | (4) `unsigned int` | data_offset
28 | (4) `unsigned int` | data_size
32 | (8) `unsigned int *` | offsets
40 | (8) `unsigned __int8 *` | bytes


### `CID_Parser_`
Offset | Type | Name
-|-|-|-
0 | (144) `PS_ParserRec_` | root
144 | (8) `FT_StreamRec_ *` | stream
152 | (8) `unsigned __int8 *` | postscript
160 | (4) `unsigned int` | postscript_len
164 | (4) `unsigned int` | data_offset
168 | (4) `unsigned int` | binary_length
176 | (8) `CID_FaceInfoRec_ *` | cid
184 | (4) `int` | num_dict


### `CF2_Matrix_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | a
4 | (4) `int` | b
8 | (4) `int` | c
12 | (4) `int` | d
16 | (4) `int` | tx
20 | (4) `int` | ty


### `CF2_BufferRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int *` | error
8 | (8) `const unsigned __int8 *` | start
16 | (8) `const unsigned __int8 *` | end
24 | (8) `const unsigned __int8 *` | ptr


### `CF2_HintMaskRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int *` | error
8 | (1) `unsigned __int8` | isValid
9 | (1) `unsigned __int8` | isNew
16 | (8) `unsigned __int64` | bitCount
24 | (8) `unsigned __int64` | byteCount
32 | (12) `unsigned __int8[12]` | mask


### `CF2_HintRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | flags
8 | (8) `unsigned __int64` | index
16 | (4) `int` | csCoord
20 | (4) `int` | dsCoord
24 | (4) `int` | scale


### `CF2_GlyphPathRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `CF2_FontRec_ *` | font
8 | (8) `CF2_OutlineCallbacksRec_ *` | callbacks
16 | (6184) `CF2_HintMapRec_` | hintMap
6200 | (6184) `CF2_HintMapRec_` | firstHintMap
12384 | (6184) `CF2_HintMapRec_` | initialHintMap
18568 | (64) `CF2_ArrStackRec_` | hintMoves
18632 | (4) `int` | scaleX
18636 | (4) `int` | scaleC
18640 | (4) `int` | scaleY
18644 | (8) `FT_Vector_` | fractionalTranslation
18652 | (1) `unsigned __int8` | pathIsOpen
18653 | (1) `unsigned __int8` | pathIsClosing
18654 | (1) `unsigned __int8` | darken
18655 | (1) `unsigned __int8` | moveIsPending
18656 | (8) `CF2_ArrStackRec_ *` | hStemHintArray
18664 | (8) `CF2_ArrStackRec_ *` | vStemHintArray
18672 | (8) `CF2_HintMaskRec_ *` | hintMask
18680 | (4) `int` | hintOriginY
18688 | (8) `const CF2_BluesRec_ *` | blues
18696 | (4) `int` | xOffset
18700 | (4) `int` | yOffset
18704 | (4) `int` | miterLimit
18708 | (4) `int` | snapThreshold
18712 | (8) `FT_Vector_` | offsetStart0
18720 | (8) `FT_Vector_` | offsetStart1
18728 | (8) `FT_Vector_` | currentCS
18736 | (8) `FT_Vector_` | currentDS
18744 | (8) `FT_Vector_` | start
18752 | (1) `unsigned __int8` | elemIsQueued
18756 | (4) `int` | prevElemOp
18760 | (8) `FT_Vector_` | prevElemP0
18768 | (8) `FT_Vector_` | prevElemP1
18776 | (8) `FT_Vector_` | prevElemP2
18784 | (8) `FT_Vector_` | prevElemP3


### `CF2_HintMapRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `CF2_FontRec_ *` | font
8 | (8) `CF2_HintMapRec_ *` | initialHintMap
16 | (8) `CF2_ArrStackRec_ *` | hintMoves
24 | (1) `unsigned __int8` | isValid
25 | (1) `unsigned __int8` | hinted
28 | (4) `int` | scale
32 | (4) `unsigned int` | count
36 | (4) `unsigned int` | lastIndex
40 | (6144) `CF2_HintRec_[192]` | edge


### `CF2_ArrStackRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_MemoryRec_ *` | memory
8 | (8) `int *` | error
16 | (8) `unsigned __int64` | sizeItem
24 | (8) `unsigned __int64` | allocated
32 | (8) `unsigned __int64` | chunk
40 | (8) `unsigned __int64` | count
48 | (8) `unsigned __int64` | totalSize
56 | (8) `void *` | ptr


### `cookie_type`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | start_pos
8 | (4) `int` | dec_flags
12 | (4) `int` | bytes_to_feed
16 | (4) `int` | chars_to_skip
20 | (1) `char` | need_eof


### `compiling`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | c_encoding
8 | (4) `int` | c_future_unicode
16 | (8) `_arena *` | c_arena
24 | (8) `const char *` | c_filename


### `compiler`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | c_filename
8 | (8) `symtable *` | c_st
16 | (8) `?` | c_future
24 | (8) `?` | c_flags
32 | (4) `int` | c_interactive
36 | (4) `int` | c_nestlevel
40 | (8) `compiler_unit *` | u
48 | (8) `_object *` | c_stack
56 | (8) `_arena *` | c_arena


### `Core::CpuRingBufferAllocator<dragon::platform::registry::BasicRenderRegistry<dragon::frameobject::components::ComputeDispatch,dragon::frameobject::components::ViewSetId,dragon::frameobject::components::defaultpasses::AlphaTest,dragon::frameobject::components::defaultpasses::Blit,dragon::frameobject::components::defaultpasses::Opaque,dragon::frameobject::components::defaultpasses::StencilWrite,dragon::frameobject::components::defaultpasses::Transparent,dragon::frameobject::components::defaultpasses::PostFX,dragon::frameobject::components::defaultpasses::UI,dragon::frameobject::components::LightParameters,dragon::frameobject::components::DirectionalLight,dragon::frameobject::components::AmbientLight,dragon::frameobject::components::PointLight,dragon::frameobject::components::MeshFilter,dragon::frameobject::components::MaterialFilter,dragon::frameobject::components::ParticleObject,dragon::frameobject::components::PassState,dragon::frameobject::components::PostEffect,dragon::frameobject::components::RenderTarget,dragon::frameobject::components::SceneObject,dragon::frameobject::components::SceneOverlayObject,dragon::frameobject::components::SceneSky,dragon::frameobject::components::SceneSkyObject,dragon::frameobject::components::SelectionOverlayObject,dragon::frameobject::components::Cubemap,dragon::frameobject::components::ShadowSource,dragon::frameobject::components::ShadowCaster,dragon::frameobject::components::ShadowOverlay,dragon::frameobject::components::ShadowVolume,dragon::frameobject::components::SortIndex,dragon::frameobject::components::SortOrigin,dragon::frameobject::components::Transform,dragon::frameobject::components::UIElement,dragon::frameobject::components::ForceRasterization,dragon::frameobject::components::ForceRasterizationWithMultiply,dragon::frameobject::components::RaytraceObject,mce::framebuilder::gamecomponents::AlphaTestCracks,mce::framebuilder::gamecomponents::Atmosphere,mce::framebuilder::gamecomponents::BlendedCracksObject,mce::framebuilder::gamecomponents::EnvironmentalText,mce::framebuilder::gamecomponents::Gameface,mce::framebuilder::gamecomponents::InLevelCubeMapObject,mce::framebuilder::gamecomponents::ItemInHandObject,mce::framebuilder::gamecomponents::SceneObjectActors,mce::framebuilder::gamecomponents::TransparentItemInWorldObject,mce::framebuilder::gamecomponents::WaterHoleObject,mce::framebuilder::gamecomponents::PlayerUI,mce::framebuilder::gamecomponents::PlayerVision,mce::framebuilder::gamecomponents::OverlayUI,mce::framebuilder::gamecomponents::VrConfiguration,mce::framebuilder::gamecomponents::VrPresenceObject,mce::framebuilder::gamecomponents::LivingRoomViewFilter,mce::framebuilder::gamecomponents::LivingRoomTransitionFilter,mce::framebuilder::gamecomponents::LivingRoomSceneObject,mce::framebuilder::gamecomponents::VrFloatingUiQuad,mce::framebuilder::gamecomponents::FadeToBlackEffect,mce::framebuilder::bgfxbridge::RTXMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::VanillaMinecraftFrameRendererResources,mce::framebuilder::bgfxbridge::HolographicMinecraftFrameRendererResources>::SortedView::Sortable,2,0,Core::CheckedRingBuffer<2,0> >`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::CheckedRingBuffer<2,0> *` | mBufferInstance


### `CsFrame`
```
struct CsFrame
{
  unsigned __int64 SavedR10;
  unsigned __int64 SavedR11;
};

```

### `CompoundTag_vtbl`
```
struct /*VFT*/ CompoundTag_vtbl
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

### `ClockSpriteCalculator`
```
struct __cppobj ClockSpriteCalculator
{
  int mFrame;
  float mRot;
  float mRotA;
};

```

### `Core::PathBuffer<std::string >`
```
struct __cppobj Core::PathBuffer<std::string >
{
  std::string mContainer;
};

```

### `cg::RenderMaterialBase_vtbl`
```
struct /*VFT*/ cg::RenderMaterialBase_vtbl
{
  void (__fastcall *~RenderMaterialBase)(cg::RenderMaterialBase *this);
  void (__fastcall *parseRuntimeStates)(cg::RenderMaterialBase *this, const Json::Value *);
  void (__fastcall *appendShaderPathForGfxAPI)(cg::RenderMaterialBase *this);
  std::string *(__fastcall *buildHeader)(cg::RenderMaterialBase *this, std::string *result, const std::set<std::string> *);
  void (__fastcall *parseShader)(cg::RenderMaterialBase *this, const Json::Value *);
};

```

### `cg::TextureSetImageDescription::LayerInfoVar`
```
struct __cppobj cg::TextureSetImageDescription::LayerInfoVar
{
  cg::TextureSetLayerType mLayerType;
  std::variant<cg::ImageDescription,ColorChannel,mce::Color> mData;
};

```

### `Connector`
```
struct __cppobj Connector
{
  Connector_vtbl *__vftable /*VFT*/;
};

```

### `Connector::ConnectionStateListener`
```
struct __cppobj Connector::ConnectionStateListener
{
  Connector::ConnectionStateListener_vtbl *__vftable /*VFT*/;
};

```

### `Connector::ConnectionStateListener_vtbl`
```
struct /*VFT*/ Connector::ConnectionStateListener_vtbl
{
  void (__fastcall *~ConnectionStateListener)(Connector::ConnectionStateListener *this);
  void (__fastcall *onConnectionStateChanged)(Connector::ConnectionStateListener *this, const std::string *, const std::string *, unsigned int, unsigned int, unsigned int, const std::string *);
};

```

### `Connector_vtbl`
```
struct /*VFT*/ Connector_vtbl
{
  void (__fastcall *~Connector)(Connector *this);
  std::vector<std::string> *(__fastcall *getLocalIps)(Connector *this, std::vector<std::string> *result);
  std::string *(__fastcall *getLocalIp)(Connector *this, std::string *result);
  unsigned __int16 (__fastcall *getPort)(Connector *this);
  std::vector<RakNet::SystemAddress> *(__fastcall *getRefinedLocalIps)(Connector *this, std::vector<RakNet::SystemAddress> *result);
  const Social::GameConnectionInfo *(__fastcall *getConnectedGameInfo)(Connector *this);
  void (__fastcall *setupNatPunch)(Connector *this, bool);
  Connector::NatPunchInfo *(__fastcall *getNatPunchInfo)(Connector *this, Connector::NatPunchInfo *result);
  void (__fastcall *startNatPunchingClient)(Connector *this, Social::GameConnectionInfo);
  void (__fastcall *addConnectionStateListener)(Connector *this, Connector::ConnectionStateListener *);
  void (__fastcall *removeConnectionStateListener)(Connector *this, Connector::ConnectionStateListener *);
  bool (__fastcall *isIPv4Supported)(Connector *this);
  bool (__fastcall *isIPv6Supported)(Connector *this);
  unsigned __int16 (__fastcall *getIPv4Port)(Connector *this);
  unsigned __int16 (__fastcall *getIPv6Port)(Connector *this);
  RakNet::RakNetGUID *(__fastcall *getGUID)(Connector *this, RakNet::RakNetGUID *result);
};

```

### `Core::FileImpl`
```
struct __cppobj __declspec(align(8)) Core::FileImpl
{
  Core::FileImpl_vtbl *__vftable /*VFT*/;
  Core::FileOpenMode mOpenMode;
  Core::FileSystemImpl *mpTransaction;
  bool mLoggingEnabled;
};

```

### `Core::FileImpl_vtbl`
```
struct /*VFT*/ Core::FileImpl_vtbl
{
  void (__fastcall *~FileImpl)(Core::FileImpl *this);
  Core::PathBuffer<std::string > *(__fastcall *_getPath)(Core::FileImpl *this, Core::PathBuffer<std::string > *result);
  unsigned __int64 (__fastcall *_getBlockSize)(Core::FileImpl *this);
  bool (__fastcall *_isOpen)(Core::FileImpl *this);
  Core::Result *(__fastcall *_close)(Core::FileImpl *this, Core::Result *result);
  Core::Result *(__fastcall *_read)(Core::FileImpl *this, Core::Result *result, void *, unsigned __int64, unsigned __int64 *);
  Core::Result *(__fastcall *_readExactly)(Core::FileImpl *this, Core::Result *result, void *, unsigned __int64);
  Core::Result *(__fastcall *_skip)(Core::FileImpl *this, Core::Result *result, unsigned __int64);
  Core::Result *(__fastcall *_readAtPosition)(Core::FileImpl *this, Core::Result *result, unsigned __int64, void *, unsigned __int64, unsigned __int64 *);
  Core::Result *(__fastcall *_getPosition)(Core::FileImpl *this, Core::Result *result, unsigned __int64 *);
  Core::Result *(__fastcall *_setPosition)(Core::FileImpl *this, Core::Result *result, unsigned __int64);
  Core::Result *(__fastcall *_write)(Core::FileImpl *this, Core::Result *result, const void *, unsigned __int64);
  Core::Result *(__fastcall *_flush)(Core::FileImpl *this, Core::Result *result);
  Core::Result *(__fastcall *_getSize)(Core::FileImpl *this, Core::Result *result, unsigned __int64 *);
  Core::Result *(__fastcall *_getRemainingSize)(Core::FileImpl *this, Core::Result *result, unsigned __int64 *);
};

```

### `Core::FileSystemImpl`
```
struct __cppobj Core::FileSystemImpl
{
  Core::FileSystemImpl_vtbl *__vftable /*VFT*/;
  std::shared_ptr<Core::FileStorageArea> mpStorageArea;
  bool mLoggingEnabled;
  bool mTransactionEnded;
  __declspec(align(4)) _BYTE mTransactionFlags[4];
  Core::FileAccessType mAccessType;
  Core::FileStats mStats;
  std::mutex mFileLock;
  std::vector<Core::FileImpl *> mFiles;
  Core::FlatFileSystemImpl mFlatFileSystem;
};

```

### `Core::DirectoryIterationItem`
```
const struct __cppobj Core::DirectoryIterationItem
{
  Core::PathBuffer<std::string > mFullPathName;
  Core::PathPart mName;
  unsigned __int64 mFileSize;
  unsigned __int64 mFileSizeAllocationOnDisk;
  _BYTE mType[4];
  __int64 mCreateTime;
  __int64 mModifyTime;
};

```

### `Core::FileStorageArea`
```
struct __cppobj __declspec(align(8)) Core::FileStorageArea : std::enable_shared_from_this<Core::FileStorageArea>
{
  Core::FileStorageArea_vtbl *__vftable /*VFT*/;
  std::recursive_mutex mLock;
  std::vector<Core::FileSystemImpl *> mAllTransactions;
  bool mCanAttemptExtendSave;
  bool mCachedFileUsageSize;
  Core::FileStats mTransactionStats;
  Core::FileStats mTotalStats;
  Core::FileAccessType mAccessType;
  Core::PathBuffer<std::string > mRootPath;
  std::vector<Core::FileSystemImpl *> mWriteTransactions;
  Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock> mSubject;
  std::shared_ptr<Core::FileStorageArea> mParent;
  Core::StorageAreaState mState;
  std::atomic<bool> mFileIOSuspended;
  std::condition_variable_any mResumeSignal;
  bool mLoggingEnabled;
  std::shared_ptr<Core::FlatFileManifestTracker> mManifestTracker;
  bool mIsAccessedDirectly;
};

```

### `Core::FileStorageArea_vtbl`
```
struct /*VFT*/ Core::FileStorageArea_vtbl
{
  void (__fastcall *~FileStorageArea)(Core::FileStorageArea *this);
  std::unique_ptr<Core::FileSystemImpl> *(__fastcall *createTransaction)(Core::FileStorageArea *this, std::unique_ptr<Core::FileSystemImpl> *result, Core::FileAccessType, Core::TransactionFlags);
  std::unique_ptr<Core::FileSystemImpl> *(__fastcall *createTransaction)(Core::FileStorageArea *this, std::unique_ptr<Core::FileSystemImpl> *result, Core::FileAccessType);
  bool (__fastcall *supportsSizeQuery)(Core::FileStorageArea *this);
  unsigned __int64 (__fastcall *getTotalSize)(Core::FileStorageArea *this);
  Core::Result *(__fastcall *getUsedSize)(Core::FileStorageArea *this, Core::Result *result, unsigned __int64 *);
  void (__fastcall *notifyChangeInFileSize)(Core::FileStorageArea *this, __int64, __int64);
  bool (__fastcall *handlesPendingWrites)(Core::FileStorageArea *this);
  void (__fastcall *informPendingWriteSize)(Core::FileStorageArea *this, const unsigned __int64 *, const bool);
  void (__fastcall *informStorageAreaCopy)(Core::FileStorageArea *this, const unsigned __int64 *);
  bool (__fastcall *supportsExtendSize)(Core::FileStorageArea *this);
  bool (__fastcall *canExtendSize)(Core::FileStorageArea *this);
  void (__fastcall *resetCanAttemptExtendSize)(Core::FileStorageArea *this);
  Core::Result *(__fastcall *getExtendSizeThreshold)(Core::FileStorageArea *this, Core::Result *result, unsigned __int64 *);
  void (__fastcall *attemptExtendSize)(Core::FileStorageArea *this, const __int64 *, std::function<void __cdecl(void)>);
  void (__fastcall *preemptiveExtendSize)(Core::FileStorageArea *this, const unsigned __int64, std::function<void __cdecl(void)>, std::function<void __cdecl(void)>);
  void (__fastcall *unloadFlatFileManifests)(Core::FileStorageArea *this, bool);
  bool (__fastcall *canFlushToDisk)(Core::FileStorageArea *this);
  bool (__fastcall *needsTick)(Core::FileStorageArea *this);
  void (__fastcall *tick)(Core::FileStorageArea *this);
  void (__fastcall *flushImmediately)(Core::FileStorageArea *this);
  void (__fastcall *enableFlushToDisk)(Core::FileStorageArea *this, bool);
  bool (__fastcall *checkCorrupt)(Core::FileStorageArea *this, bool);
  Core::FileStorageArea::FlushableLevelDbEnvType (__fastcall *getFlushableLevelDbEnvType)(Core::FileStorageArea *this);
  unsigned __int64 (__fastcall *getTransactionWriteSizeLimit)(Core::FileStorageArea *this);
  Core::Result *(__fastcall *setSaveDataIcon)(Core::FileStorageArea *this, Core::Result *result, const Core::Path *);
  bool (__fastcall *shouldAllowCommit)(Core::FileStorageArea *this);
  void (__fastcall *trackFileWriteSize)(Core::FileStorageArea *this, const unsigned __int64);
  Core::Result *(__fastcall *_commit)(Core::FileStorageArea *this, Core::Result *result);
  Core::Result *(__fastcall *_onTransactionsEmpty)(Core::FileStorageArea *this, Core::Result *result, bool);
  void (__fastcall *_onTeardown)(Core::FileStorageArea *this);
};

```

### `Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>
{
  Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<Core::FileStorageAreaObserver *>> mObservers;
};

```

### `Core::FileStorageAreaObserver`
```
struct __cppobj Core::FileStorageAreaObserver : Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>
{
};

```

### `Core::FileStorageAreaObserver_vtbl`
```
struct /*VFT*/ Core::FileStorageAreaObserver_vtbl
{
  void (__fastcall *~Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onBeginWrites)(Core::FileStorageAreaObserver *this);
  void (__fastcall *_onEndWrites)(Core::FileStorageAreaObserver *this);
  void (__fastcall *_onWriteFile)(Core::FileStorageAreaObserver *this, Core::Path);
  void (__fastcall *_onDeleteFile)(Core::FileStorageAreaObserver *this, Core::Path);
};

```

### `Core::StorageAreaStateListener`
```
struct __cppobj Core::StorageAreaStateListener
{
  Core::StorageAreaStateListener_vtbl *__vftable /*VFT*/;
  std::shared_ptr<Core::FileStorageArea> mFileStorageArea;
  std::mutex mMutex;
};

```

### `Core::StorageAreaStateListener_vtbl`
```
struct /*VFT*/ Core::StorageAreaStateListener_vtbl
{
  void (__fastcall *~StorageAreaStateListener)(Core::StorageAreaStateListener *this);
  void (__fastcall *onExtendDiskSpace)(Core::StorageAreaStateListener *this, const bool, std::weak_ptr<Core::FileStorageArea> *, const unsigned __int64 *, std::function<void __cdecl(void)>);
  void (__fastcall *onLowDiskSpace)(Core::StorageAreaStateListener *this, const bool);
  void (__fastcall *onOutOfDiskSpace)(Core::StorageAreaStateListener *this, const bool);
  void (__fastcall *onCriticalDiskError)(Core::StorageAreaStateListener *this, const bool, const Core::LevelStorageState *);
};

```

### `Core::StorageAreaState`
```
struct __cppobj Core::StorageAreaState
{
  std::mutex mMutex;
  Core::PathBuffer<std::string > mStorageAreaRootPath;
  std::atomic<bool> mIsExtendDiskSpaceEvent;
  std::atomic<bool> mIsLowDiskSpaceWarning;
  std::atomic<bool> mIsOutOfDiskSpaceError;
  std::atomic<bool> mIsCriticalDiskError;
  std::vector<Core::StorageAreaStateListener *> mListeners;
};

```

### `Core::FlatFileManifestInfo`
```
struct __cppobj __declspec(align(8)) Core::FlatFileManifestInfo
{
  Core::PathBuffer<std::string > mPath;
  unsigned __int64 mSeekPos;
  unsigned __int64 mFileSize;
  unsigned __int8 mFlags;
};

```

### `Core::FlatFileManifest`
```
struct __cppobj Core::FlatFileManifest
{
  std::unordered_map<std::string,unsigned __int64> mManifestEntriesMap;
  std::vector<Core::FlatFileManifestInfo> mManifestInfoVector;
  unsigned __int64 mEntriesCount;
  unsigned __int64 mVersion;
  Core::PathBuffer<std::string > mManifestPath;
};

```

### `Core::FlatFileManifestTracker`
```
struct __cppobj Core::FlatFileManifestTracker
{
  std::mutex mManifestsLock;
  std::unordered_map<std::string,std::shared_ptr<Core::FlatFileManifest>> mManifestMap;
  std::set<std::string> mManifestNames;
};

```

### `Core::FlatFileSystemImpl`
```
struct __cppobj Core::FlatFileSystemImpl
{
  Core::FileSystemImpl *mFileSystemImpl;
  std::shared_ptr<Core::FlatFileManifestTracker> mFlatFileManifestTracker;
};

```

### `Crypto::Symmetric::ISystemInterface_vtbl`
```
struct /*VFT*/ Crypto::Symmetric::ISystemInterface_vtbl
{
  void (__fastcall *~ISystemInterface)(Crypto::Symmetric::ISystemInterface *this);
  void (__fastcall *init)(Crypto::Symmetric::ISystemInterface *this, const std::string *, const std::string *);
  void (__fastcall *encrypt)(Crypto::Symmetric::ISystemInterface *this, const std::string *, std::string *);
  void (__fastcall *decrypt)(Crypto::Symmetric::ISystemInterface *this, const std::string *, std::string *);
  unsigned __int64 (__fastcall *getKeySize)(Crypto::Symmetric::ISystemInterface *this);
  unsigned __int64 (__fastcall *getBlockSize)(Crypto::Symmetric::ISystemInterface *this);
  unsigned __int64 (__fastcall *getEncryptionBufferSize)(Crypto::Symmetric::ISystemInterface *this, const unsigned __int64);
  bool (__fastcall *encryptToBuffer)(Crypto::Symmetric::ISystemInterface *this, const char *, const unsigned __int64, char *, const unsigned __int64, unsigned __int64 *);
};

```

### `Crypto::Symmetric::Symmetric_vtbl`
```
struct /*VFT*/ Crypto::Symmetric::Symmetric_vtbl
{
  void (__fastcall *~ISystemInterface)(Crypto::Symmetric::ISystemInterface *this);
  void (__fastcall *init)(Crypto::Symmetric::ISystemInterface *this, const std::string *, const std::string *);
  void (__fastcall *encrypt)(Crypto::Symmetric::ISystemInterface *this, const std::string *, std::string *);
  void (__fastcall *decrypt)(Crypto::Symmetric::ISystemInterface *this, const std::string *, std::string *);
  unsigned __int64 (__fastcall *getKeySize)(Crypto::Symmetric::ISystemInterface *this);
  unsigned __int64 (__fastcall *getBlockSize)(Crypto::Symmetric::ISystemInterface *this);
  unsigned __int64 (__fastcall *getEncryptionBufferSize)(Crypto::Symmetric::ISystemInterface *this, const unsigned __int64);
  bool (__fastcall *encryptToBuffer)(Crypto::Symmetric::ISystemInterface *this, const char *, const unsigned __int64, char *, const unsigned __int64, unsigned __int64 *);
};

```

### `Crypto::Hash::IHash_vtbl`
```
struct /*VFT*/ Crypto::Hash::IHash_vtbl
{
  void (__fastcall *~IHash)(Crypto::Hash::IHash *this);
  void (__fastcall *reset)(Crypto::Hash::IHash *this);
  void (__fastcall *update)(Crypto::Hash::IHash *this, const void *, unsigned int);
  void (__fastcall *final)(Crypto::Hash::IHash *this, unsigned __int8 *);
  unsigned __int64 (__fastcall *resultSize)(Crypto::Hash::IHash *this);
};

```

### `Crypto::Hash::HMAC`
```
struct __cppobj __declspec(align(8)) Crypto::Hash::HMAC
{
  std::unique_ptr<Crypto::Hash::IHash> mHash;
  std::string mKey;
  int mResultSize;
};

```

### `CorrectPlayerMovePredictionPacket`
```
const struct __cppobj __declspec(align(8)) CorrectPlayerMovePredictionPacket : Packet
{
  Vec3 mPos;
  Vec3 mPosDelta;
  unsigned __int64 mTick;
  bool mOnGround;
};

```

### `CorrectPlayerMovePredictionPacket_vtbl`
```
struct /*VFT*/ CorrectPlayerMovePredictionPacket_vtbl
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

### `CodeBuilderPacket`
```
const struct __cppobj __declspec(align(8)) CodeBuilderPacket : Packet
{
  std::string mURL;
  bool mShouldOpenCodeBuilder;
};

```

### `CodeBuilderPacket_vtbl`
```
struct /*VFT*/ CodeBuilderPacket_vtbl
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

### `CreativeItemRegistry`
```
struct __cppobj CreativeItemRegistry : Bedrock::EnableNonOwnerReferences
{
  std::vector<CreativeItemEntry> mCreativeItems;
  std::vector<CreativeGroupInfo> mCreativeGroups;
  std::unordered_map<enum CreativeItemCategory,CreativeItemGroupCategory> mCreativeGroupCategories;
  std::unordered_map<TypedServerNetId<CreativeItemNetIdTag,unsigned int,0>,unsigned __int64,std::hash<TypedServerNetId<CreativeItemNetIdTag,unsigned int,0> >,std::equal_to<TypedServerNetId<CreativeItemNetIdTag,unsigned int,0> >,std::allocator<std::pair<TypedServerNetId<CreativeItemNetIdTag,unsigned int,0> const ,unsigned __int64> > > mCreativeNetIdIndex;
};

```

### `CreativeGroupInfo`
```
struct __cppobj CreativeGroupInfo : Bedrock::EnableNonOwnerReferences
{
  CreativeItemCategory mCategory;
  CreativeItemRegistry *mRegistry;
  HashedString mName;
  ItemInstance mIcon;
  unsigned int mIndex;
  std::vector<unsigned int> mItemIndexes;
};

```

### `CreativeItemGroupCategory`
```
struct __cppobj CreativeItemGroupCategory : Bedrock::EnableNonOwnerReferences
{
  std::string mName;
  CreativeItemCategory mCategory;
  CreativeItemRegistry *mRegistry;
  std::unordered_map<HashedString,unsigned int> mNamedGroupIndex;
  std::vector<unsigned int> mGroupIndexes;
};

```

### `CreativeContentPacket`
```
const struct __cppobj CreativeContentPacket : Packet
{
  const std::vector<CreativeItemEntry> *mWriteEntries;
  std::vector<CreativeItemEntry> mReadEntries;
};

```

### `CreativeContentPacket_vtbl`
```
struct /*VFT*/ CreativeContentPacket_vtbl
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

### `ConfirmSkinPacket`
```
const struct __cppobj ConfirmSkinPacket : Packet
{
  std::vector<ConfirmSkinPacket::ConfirmSkinEntry> mEntries;
};

```

### `ConfirmSkinPacket_vtbl`
```
struct /*VFT*/ ConfirmSkinPacket_vtbl
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

### `ChangeModelTexturePacket_vtbl`
```
struct /*VFT*/ ChangeModelTexturePacket_vtbl
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

### `ChangeModelOffsetPacket`
```
const struct __cppobj __declspec(align(8)) ChangeModelOffsetPacket : Packet
{
  ActorUniqueID mEntityId;
  Vec3 mModelOffset;
};

```

### `ChangeModelOffsetPacket_vtbl`
```
struct /*VFT*/ ChangeModelOffsetPacket_vtbl
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

### `ChangeModelBindPacket`
```
const struct __cppobj ChangeModelBindPacket : Packet
{
  ActorUniqueID mEntityId;
  ActorUniqueID mBindEntityId;
};

```

### `ChangeModelBindPacket_vtbl`
```
struct /*VFT*/ ChangeModelBindPacket_vtbl
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

### `ChangeModelPacket_vtbl`
```
struct /*VFT*/ ChangeModelPacket_vtbl
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

### `CombinePacket`
```
const struct __cppobj CombinePacket : Packet
{
  unsigned __int8 mCount;
  std::string mContent;
};

```

### `CombinePacket_vtbl`
```
struct /*VFT*/ CombinePacket_vtbl
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

### `CustomPacket_vtbl`
```
struct /*VFT*/ CustomPacket_vtbl
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

### `ComplexInventoryTransaction_vtbl`
```
struct /*VFT*/ ComplexInventoryTransaction_vtbl
{
  void (__fastcall *~ComplexInventoryTransaction)(ComplexInventoryTransaction *this);
  void (__fastcall *read)(ComplexInventoryTransaction *this, ReadOnlyBinaryStream *);
  void (__fastcall *write)(ComplexInventoryTransaction *this, BinaryStream *);
  InventoryTransactionError (__fastcall *handle)(ComplexInventoryTransaction *this, Player *, bool);
  void (__fastcall *onTransactionError)(ComplexInventoryTransaction *this, Player *, InventoryTransactionError);
};

```

### `CameraShakePacket`
```
const struct __cppobj __declspec(align(8)) CameraShakePacket : Packet
{
  float mIntensity;
  float mSeconds;
  CameraShakeType mShakeType;
};

```

### `CameraShakePacket_vtbl`
```
struct /*VFT*/ CameraShakePacket_vtbl
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

### `CameraPacket`
```
const struct __cppobj CameraPacket : Packet
{
  ActorUniqueID mCameraId;
  ActorUniqueID mTargetPlayerId;
};

```

### `CameraPacket_vtbl`
```
struct /*VFT*/ CameraPacket_vtbl
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

### `CompletedUsingItemPacket`
```
const struct __cppobj CompletedUsingItemPacket : Packet
{
  __int16 mItemId;
  int mItemUseMethod;
  std::optional<ItemStack> mItemStack;
};

```

### `CompletedUsingItemPacket_vtbl`
```
struct /*VFT*/ CompletedUsingItemPacket_vtbl
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

### `CommandBlockUpdatePacket_vtbl`
```
struct /*VFT*/ CommandBlockUpdatePacket_vtbl
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

### `CommandPropertyBag`
```
struct __cppobj CommandPropertyBag : PropertyBag
{
  CommandPropertyBag_vtbl *__vftable /*VFT*/;
};

```

### `CommandPropertyBag_vtbl`
```
struct /*VFT*/ CommandPropertyBag_vtbl
{
  void (__fastcall *~CommandPropertyBag)(CommandPropertyBag *this);
};

```

### `CommandOutput`
```
struct __cppobj __declspec(align(8)) CommandOutput
{
  _BYTE mType[4];
  std::unique_ptr<CommandPropertyBag> mBag;
  std::vector<CommandOutputMessage> mMessages;
  int mSuccessCount;
};

```

### `CommandOutputPacket`
```
const struct __cppobj CommandOutputPacket : Packet
{
  CommandOriginData mOriginData;
  CommandOutput mOutput;
};

```

### `CommandOutputPacket_vtbl`
```
struct /*VFT*/ CommandOutputPacket_vtbl
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

### `CommandRequestPacket`
```
const struct __cppobj __declspec(align(8)) CommandRequestPacket : Packet
{
  std::string mCommand;
  CommandOriginData mOrigin;
  bool mInternalSource;
  bool mUnLimit;
};

```

### `CommandRequestPacket_vtbl`
```
struct /*VFT*/ CommandRequestPacket_vtbl
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

### `ChunkRadiusUpdatedPacket`
```
const struct __cppobj __declspec(align(8)) ChunkRadiusUpdatedPacket : Packet
{
  int mChunkRadius;
};

```

### `ChunkRadiusUpdatedPacket_vtbl`
```
struct /*VFT*/ ChunkRadiusUpdatedPacket_vtbl
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

### `ClientCacheStatusPacket`
```
const struct __cppobj __declspec(align(8)) ClientCacheStatusPacket : Packet
{
  bool mEnabled;
};

```

### `ClientCacheStatusPacket_vtbl`
```
struct /*VFT*/ ClientCacheStatusPacket_vtbl
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

### `ClientboundMapItemDataPacket_vtbl`
```
struct /*VFT*/ ClientboundMapItemDataPacket_vtbl
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

### `ChangeDimensionPacket`
```
const struct __cppobj __declspec(align(8)) ChangeDimensionPacket : Packet
{
  AutomaticID<Dimension,int> mDimensionId;
  Vec3 mPos;
  bool mRespawn;
};

```

### `ChangeDimensionPacket_vtbl`
```
struct /*VFT*/ ChangeDimensionPacket_vtbl
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

### `ClientCacheMissResponsePacket`
```
struct __cppobj ClientCacheMissResponsePacket : Packet
{
  std::vector<std::shared_ptr<ClientBlobCache::Server::Blob>> mWriteMissingContent;
  std::unordered_map<unsigned __int64,std::string> mReceivedMissingContent;
};

```

### `ClientCacheMissResponsePacket_vtbl`
```
struct /*VFT*/ ClientCacheMissResponsePacket_vtbl
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

### `ClientCacheBlobStatusPacket`
```
const struct __cppobj ClientCacheBlobStatusPacket : Packet
{
  std::vector<unsigned __int64> mMissingIds;
  std::vector<unsigned __int64> mFoundIds;
};

```

### `ClientCacheBlobStatusPacket_vtbl`
```
struct /*VFT*/ ClientCacheBlobStatusPacket_vtbl
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

### `CraftingEventPacket`
```
const struct __cppobj CraftingEventPacket : Packet
{
  ContainerID mContainerId;
  int mContainerType;
  mce::UUID mRecipeId;
  std::vector<ItemStack> mInputItems;
  std::vector<ItemStack> mOutputItems;
};

```

### `CraftingEventPacket_vtbl`
```
struct /*VFT*/ CraftingEventPacket_vtbl
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

### `ContainerContentChangeListener_vtbl`
```
struct /*VFT*/ ContainerContentChangeListener_vtbl
{
  void (__fastcall *containerContentChanged)(ContainerContentChangeListener *this, int);
  void (__fastcall *~ContainerContentChangeListener)(ContainerContentChangeListener *this);
  void (__fastcall *containerAddCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *containerRemoveCallback)(ContainerContentChangeListener *this, Container *);
};

```

### `Container_vtbl`
```
struct /*VFT*/ Container_vtbl
{
  void (__fastcall *~Container)(Container *this);
  void (__fastcall *init)(Container *this);
  void (__fastcall *serverInitItemStackIds)(Container *this, int, int, std::function<void __cdecl(int,ItemStack const &)>);
  void (__fastcall *addContentChangeListener)(Container *this, ContainerContentChangeListener *);
  void (__fastcall *removeContentChangeListener)(Container *this, ContainerContentChangeListener *);
  const ItemStack *(__fastcall *getItem)(Container *this, int);
  bool (__fastcall *hasRoomForItem)(Container *this, const ItemStack *);
  void (__fastcall *addItem)(Container *this, ItemStack *);
  bool (__fastcall *addItemToFirstEmptySlot)(Container *this, ItemStack *);
  void (__fastcall *setItem)(Container *this, int, const ItemStack *);
  void (__fastcall *setItemWithForceBalance)(Container *this, int, const ItemStack *, bool);
  void (__fastcall *removeItem)(Container *this, int, int);
  void (__fastcall *removeAllItems)(Container *this);
  void (__fastcall *dropContents)(Container *this, BlockSource *, const Vec3 *, bool);
  int (__fastcall *getContainerSize)(Container *this);
  int (__fastcall *getMaxStackSize)(Container *this);
  void (__fastcall *startOpen)(Container *this, Player *);
  void (__fastcall *stopOpen)(Container *this, Player *);
  std::vector<ItemStack> *(__fastcall *getSlotCopies)(Container *this, std::vector<ItemStack> *result);
  const std::vector<ItemStack const *> *(__fastcall *getSlots)(Container *this, const std::vector<ItemStack const *> *result);
  int (__fastcall *getItemCount)(Container *this, const ItemStack *);
  int (__fastcall *findFirstSlotForItem)(Container *this, const ItemStack *);
  bool (__fastcall *canPushInItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  bool (__fastcall *canPullOutItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  void (__fastcall *setContainerChanged)(Container *this, int);
  void (__fastcall *setContainerMoved)(Container *this);
  void (__fastcall *setCustomName)(Container *this, const std::string *);
  bool (__fastcall *hasCustomName)(Container *this);
  void (__fastcall *readAdditionalSaveData)(Container *this, const CompoundTag *);
  void (__fastcall *addAdditionalSaveData)(Container *this, CompoundTag *);
  void (__fastcall *createTransactionContext)(Container *this, std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>, std::function<void __cdecl(void)>);
  void (__fastcall *initializeContainerContents)(Container *this, BlockSource *);
  bool (__fastcall *reviewItems)(Container *this, Level *);
};

```

### `ContainerSizeChangeListener`
```
struct __cppobj ContainerSizeChangeListener
{
  ContainerSizeChangeListener_vtbl *__vftable /*VFT*/;
};

```

### `ContainerSizeChangeListener_vtbl`
```
struct /*VFT*/ ContainerSizeChangeListener_vtbl
{
  void (__fastcall *containerSizeChanged)(ContainerSizeChangeListener *this, int);
  void (__fastcall *~ContainerSizeChangeListener)(ContainerSizeChangeListener *this);
};

```

### `CraftingContainer_vtbl`
```
struct /*VFT*/ CraftingContainer_vtbl
{
  void (__fastcall *~Container)(Container *this);
  void (__fastcall *init)(Container *this);
  void (__fastcall *serverInitItemStackIds)(Container *this, int, int, std::function<void __cdecl(int,ItemStack const &)>);
  void (__fastcall *addContentChangeListener)(Container *this, ContainerContentChangeListener *);
  void (__fastcall *removeContentChangeListener)(Container *this, ContainerContentChangeListener *);
  const ItemStack *(__fastcall *getItem)(Container *this, int);
  bool (__fastcall *hasRoomForItem)(Container *this, const ItemStack *);
  void (__fastcall *addItem)(Container *this, ItemStack *);
  bool (__fastcall *addItemToFirstEmptySlot)(Container *this, ItemStack *);
  void (__fastcall *setItem)(Container *this, int, const ItemStack *);
  void (__fastcall *setItemWithForceBalance)(Container *this, int, const ItemStack *, bool);
  void (__fastcall *removeItem)(Container *this, int, int);
  void (__fastcall *removeAllItems)(Container *this);
  void (__fastcall *dropContents)(Container *this, BlockSource *, const Vec3 *, bool);
  int (__fastcall *getContainerSize)(Container *this);
  int (__fastcall *getMaxStackSize)(Container *this);
  void (__fastcall *startOpen)(Container *this, Player *);
  void (__fastcall *stopOpen)(Container *this, Player *);
  std::vector<ItemStack> *(__fastcall *getSlotCopies)(Container *this, std::vector<ItemStack> *result);
  const std::vector<ItemStack const *> *(__fastcall *getSlots)(Container *this, const std::vector<ItemStack const *> *result);
  int (__fastcall *getItemCount)(Container *this, const ItemStack *);
  int (__fastcall *findFirstSlotForItem)(Container *this, const ItemStack *);
  bool (__fastcall *canPushInItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  bool (__fastcall *canPullOutItem)(Container *this, BlockSource *, int, int, const ItemInstance *);
  void (__fastcall *setContainerChanged)(Container *this, int);
  void (__fastcall *setContainerMoved)(Container *this);
  void (__fastcall *setCustomName)(Container *this, const std::string *);
  bool (__fastcall *hasCustomName)(Container *this);
  void (__fastcall *readAdditionalSaveData)(Container *this, const CompoundTag *);
  void (__fastcall *addAdditionalSaveData)(Container *this, CompoundTag *);
  void (__fastcall *createTransactionContext)(Container *this, std::function<void __cdecl(Container &,int,ItemStack const &,ItemStack const &)>, std::function<void __cdecl(void)>);
  void (__fastcall *initializeContainerContents)(Container *this, BlockSource *);
  bool (__fastcall *reviewItems)(Container *this, Level *);
};

```

### `ContainerMixDataEntry`
```
struct ContainerMixDataEntry
{
  int fromItemId;
  int reagentItemId;
  int toItemId;
};

```

### `CraftingDataPacket`
```
const struct __cppobj __declspec(align(8)) CraftingDataPacket : Packet
{
  std::vector<CraftingDataEntry> mCraftingEntries;
  std::vector<PotionMixDataEntry> mPotionMixEntries;
  std::vector<ContainerMixDataEntry> mContainerMixEntries;
  std::vector<DurabilityDataEntry> mDurabilityDataEntries;
  bool mClearRecipes;
};

```

### `CraftingDataPacket_vtbl`
```
struct /*VFT*/ CraftingDataPacket_vtbl
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

### `ContainerSetDataPacket`
```
const struct __cppobj __declspec(align(8)) ContainerSetDataPacket : Packet
{
  int mId;
  int mValue;
  ContainerID mContainerId;
};

```

### `ContainerSetDataPacket_vtbl`
```
struct /*VFT*/ ContainerSetDataPacket_vtbl
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

### `ContainerClosePacket`
```
const struct __cppobj __declspec(align(8)) ContainerClosePacket : Packet
{
  ContainerID mContainerId;
  bool mServerInitiatedClose;
};

```

### `ContainerClosePacket_vtbl`
```
struct /*VFT*/ ContainerClosePacket_vtbl
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

### `ContainerOpenPacket_vtbl`
```
struct /*VFT*/ ContainerOpenPacket_vtbl
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

### `ClientToServerHandshakePacket`
```
const struct __cppobj ClientToServerHandshakePacket : Packet
{
};

```

### `ClientToServerHandshakePacket_vtbl`
```
struct /*VFT*/ ClientToServerHandshakePacket_vtbl
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

### `Certificate`
```
struct __cppobj __declspec(align(8)) Certificate
{
  UnverifiedCertificate mUnverifiedCertificate;
  std::unique_ptr<Certificate> mParentCertificate;
  bool mIsValid;
};

```

### `CompositePackSource`
```
struct __cppobj CompositePackSource : PackSource
{
  std::vector<PackSource *> mPackSources;
};

```

### `CompositePackSource_vtbl`
```
struct /*VFT*/ CompositePackSource_vtbl
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

### `Core::Observer<WebviewObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<WebviewObserver,Core::SingleThreadedLock>
{
  Core::Observer<WebviewObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<WebviewObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<WebviewObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<WebviewObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<WebviewObserver,Core::SingleThreadedLock>)(Core::Observer<WebviewObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<WebviewObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<WebviewObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<WebviewObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<WebviewObserver *>> mObservers;
};

```

### `ChatOptions`
```
struct __cppobj ChatOptions
{
  std::map<enum OptionID,ChatOptions::ChatOption> mChatOptions;
};

```

### `Core::Observer<OptionsObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<OptionsObserver,Core::SingleThreadedLock>
{
  Core::Observer<OptionsObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<OptionsObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<OptionsObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<OptionsObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<OptionsObserver,Core::SingleThreadedLock>)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<OptionsObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<OptionsObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<OptionsObserver *>> mObservers;
};

```

### `Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
  Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>)(Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<Social::XboxLiveUserObserver *>> mObservers;
};

```

### `ContentTierManager`
```
const struct __cppobj ContentTierManager
{
  int mMemoryTier;
};

```

### `CommandRegistry::ParseToken`
```
struct __cppobj CommandRegistry::ParseToken
{
  std::unique_ptr<CommandRegistry::ParseToken> child;
  std::unique_ptr<CommandRegistry::ParseToken> next;
  CommandRegistry::ParseToken *parent;
  const char *text;
  unsigned int length;
  CommandRegistry::Symbol type;
};

```

### `CommandRegistry::ParseRule`
```
struct __cppobj CommandRegistry::ParseRule
{
  CommandRegistry::Symbol nonTerminal;
  std::function<CommandRegistry::ParseToken * __cdecl(CommandRegistry::ParseToken &,CommandRegistry::Symbol)> process;
  std::vector<CommandRegistry::Symbol> derivation;
  CommandVersion versions;
};

```

### `CommandRegistry::ParseTable`
```
struct __cppobj CommandRegistry::ParseTable
{
  std::map<CommandRegistry::Symbol,std::vector<CommandRegistry::Symbol>> first;
  std::map<CommandRegistry::Symbol,std::vector<CommandRegistry::Symbol>> follow;
  std::map<std::pair<CommandRegistry::Symbol,CommandRegistry::Symbol>,int,std::less<std::pair<CommandRegistry::Symbol,CommandRegistry::Symbol> >,std::allocator<std::pair<std::pair<CommandRegistry::Symbol,CommandRegistry::Symbol> const ,int> > > predict;
};

```

### `CommandRegistry::OptionalParameterChain`
```
struct __cppobj CommandRegistry::OptionalParameterChain
{
  int parameterCount;
  int followingRuleIndex;
  CommandRegistry::Symbol paramSymbol;
};

```

### `CustomParticle`
```
struct __cppobj CustomParticle
{
  CustomParticle_vtbl *__vftable /*VFT*/;
};

```

### `CustomParticle_vtbl`
```
struct /*VFT*/ CustomParticle_vtbl
{
  void (__fastcall *~CustomParticle)(CustomParticle *this);
  void (__fastcall *normalTick)(CustomParticle *this);
  void (__fastcall *render)(CustomParticle *this, BaseActorRenderContext *, const Vec3 *, float);
  bool (__fastcall *isRemoved)(CustomParticle *this);
};

```

### `ChunkSource_vtbl`
```
struct /*VFT*/ ChunkSource_vtbl
{
  void (__fastcall *~ChunkSource)(ChunkSource *this);
  void (__fastcall *shutdown)(ChunkSource *this);
  bool (__fastcall *isShutdownDone)(ChunkSource *this);
  std::shared_ptr<LevelChunk> *(__fastcall *getExistingChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *);
  std::shared_ptr<LevelChunk> *(__fastcall *getRandomChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, Random *);
  std::shared_ptr<LevelChunk> *(__fastcall *createNewChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  std::shared_ptr<LevelChunk> *(__fastcall *getOrLoadChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  bool (__fastcall *postProcess)(ChunkSource *this, ChunkViewSource *);
  void (__fastcall *checkAndReplaceChunk)(ChunkSource *this, ChunkViewSource *, LevelChunk *);
  void (__fastcall *loadChunk)(ChunkSource *this, LevelChunk *, bool);
  void (__fastcall *postProcessMobsAt)(ChunkSource *this, BlockSource *, int, int, Random *);
  bool (__fastcall *saveLiveChunk)(ChunkSource *this, LevelChunk *);
  void (__fastcall *hintDiscardBatchBegin)(ChunkSource *this);
  void (__fastcall *hintDiscardBatchEnd)(ChunkSource *this);
  void (__fastcall *acquireDiscarded)(ChunkSource *this, std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>);
  void (__fastcall *compact)(ChunkSource *this);
  void (__fastcall *flushPendingWrites)(ChunkSource *this);
  bool (__fastcall *isWithinWorldLimit)(ChunkSource *this, const ChunkPos *);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getChunkMap)(ChunkSource *this);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getStorage)(ChunkSource *this);
  void (__fastcall *clearDeletedEntities)(ChunkSource *this);
  void (__fastcall *removeDimensionData)(ChunkSource *this, const std::unordered_set<AutomaticID<Dimension,int>> *);
  bool (__fastcall *hasChunk)(ChunkSource *this, const ChunkPos *, AutomaticID<Dimension,int>);
  bool (__fastcall *canCreateViews)(ChunkSource *this);
};

```

### `ChunkViewSource_vtbl`
```
struct /*VFT*/ ChunkViewSource_vtbl
{
  void (__fastcall *~ChunkSource)(ChunkSource *this);
  void (__fastcall *shutdown)(ChunkSource *this);
  bool (__fastcall *isShutdownDone)(ChunkSource *this);
  std::shared_ptr<LevelChunk> *(__fastcall *getExistingChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *);
  std::shared_ptr<LevelChunk> *(__fastcall *getRandomChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, Random *);
  std::shared_ptr<LevelChunk> *(__fastcall *createNewChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  std::shared_ptr<LevelChunk> *(__fastcall *getOrLoadChunk)(ChunkSource *this, std::shared_ptr<LevelChunk> *result, const ChunkPos *, ChunkSource::LoadMode);
  bool (__fastcall *postProcess)(ChunkSource *this, ChunkViewSource *);
  void (__fastcall *checkAndReplaceChunk)(ChunkSource *this, ChunkViewSource *, LevelChunk *);
  void (__fastcall *loadChunk)(ChunkSource *this, LevelChunk *, bool);
  void (__fastcall *postProcessMobsAt)(ChunkSource *this, BlockSource *, int, int, Random *);
  bool (__fastcall *saveLiveChunk)(ChunkSource *this, LevelChunk *);
  void (__fastcall *hintDiscardBatchBegin)(ChunkSource *this);
  void (__fastcall *hintDiscardBatchEnd)(ChunkSource *this);
  void (__fastcall *acquireDiscarded)(ChunkSource *this, std::unique_ptr<LevelChunk,LevelChunkFinalDeleter>);
  void (__fastcall *compact)(ChunkSource *this);
  void (__fastcall *flushPendingWrites)(ChunkSource *this);
  bool (__fastcall *isWithinWorldLimit)(ChunkSource *this, const ChunkPos *);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getChunkMap)(ChunkSource *this);
  const std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> *(__fastcall *getStorage)(ChunkSource *this);
  void (__fastcall *clearDeletedEntities)(ChunkSource *this);
  void (__fastcall *removeDimensionData)(ChunkSource *this, const std::unordered_set<AutomaticID<Dimension,int>> *);
  bool (__fastcall *hasChunk)(ChunkSource *this, const ChunkPos *, AutomaticID<Dimension,int>);
  bool (__fastcall *canCreateViews)(ChunkSource *this);
};

```

### `CommandArea`
```
struct __cppobj CommandArea
{
  std::unique_ptr<ChunkViewSource> mChunkSource;
  BlockSource mBlockSource;
};

```

### `Core::LevelStorageResult`
```
struct __cppobj Core::LevelStorageResult
{
  _BYTE state[4];
  std::string telemetryMsg;
};

```

### `CallbackTokenCancelState`
```
struct __cppobj CallbackTokenCancelState
{
  std::atomic<bool> mCanceled;
};

```

### `ContentLogEndPoint`
```
struct __cppobj ContentLogEndPoint : Bedrock::LogEndPoint, Bedrock::EnableNonOwnerReferences
{
};

```

### `ContentLogEndPoint_vtbl`
```
struct /*VFT*/ ContentLogEndPoint_vtbl
{
  void (__fastcall *~LogEndPoint)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(Bedrock::LogEndPoint *this, const char *);
  void (__fastcall *flush)(Bedrock::LogEndPoint *this);
  void (__fastcall *setEnabled)(Bedrock::LogEndPoint *this, bool);
  bool (__fastcall *isEnabled)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(ContentLogEndPoint *this, const LogArea, const LogLevel, const char *);
};

```

### `CommandRegistry`
```
struct __cppobj CommandRegistry
{
  std::function<void __cdecl(Packet const &)> mNetworkUpdateCallback;
  std::function<int __cdecl(bool &,std::string const &,Actor const &)> mGetScoreForObjective;
  std::vector<CommandRegistry::ParseRule> mRules;
  std::map<unsigned int,CommandRegistry::ParseTable> mParseTables;
  std::vector<CommandRegistry::OptionalParameterChain> mOptionals;
  std::vector<std::string> mEnumValues;
  std::vector<CommandRegistry::Enum> mEnums;
  std::vector<CommandRegistry::Factorization> mFactorizations;
  std::vector<std::string> mPostfixes;
  std::map<std::string,unsigned int> mEnumLookup;
  std::map<std::string,unsigned __int64> mEnumValueLookup;
  std::vector<CommandRegistry::Symbol> mCommandSymbols;
  std::map<std::string,CommandRegistry::Signature> mSignatures;
  std::map<typeid_t<CommandRegistry>,int,std::less<typeid_t<CommandRegistry> >,std::allocator<std::pair<typeid_t<CommandRegistry> const ,int> > > mTypeLookup;
  std::map<std::string,std::string> mAliases;
  std::vector<enum SemanticConstraint> mSemanticConstraints;
  std::map<enum SemanticConstraint,unsigned char> mSemanticConstraintLookup;
  std::vector<CommandRegistry::ConstrainedValue> mConstrainedValues;
  std::map<std::pair<unsigned __int64,unsigned int>,unsigned int,std::less<std::pair<unsigned __int64,unsigned int> >,std::allocator<std::pair<std::pair<unsigned __int64,unsigned int> const ,unsigned int> > > mConstrainedValueLookup;
  std::vector<CommandRegistry::SoftEnum> mSoftEnums;
  std::map<std::string,unsigned int> mSoftEnumLookup;
  std::vector<CommandRegistry::RegistryState> mStateStack;
  CommandRegistry::ParamSymbols mArgs;
  std::function<void __cdecl(CommandFlag &,std::string const &)> mCommandOverrideFunctor;
};

```

### `Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
  Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>)(Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<Social::MultiplayerServiceObserver *>> mObservers;
};

```

### `Crypto::Asymmetric::ISystemInterface`
```
struct __cppobj Crypto::Asymmetric::ISystemInterface
{
  Crypto::Asymmetric::ISystemInterface_vtbl *__vftable /*VFT*/;
};

```

### `Crypto::Asymmetric::ISystemInterface_vtbl`
```
struct /*VFT*/ Crypto::Asymmetric::ISystemInterface_vtbl
{
  void (__fastcall *~ISystemInterface)(Crypto::Asymmetric::ISystemInterface *this);
  bool (__fastcall *generateKeyPair)(Crypto::Asymmetric::ISystemInterface *this, std::string *, std::string *);
  std::string *(__fastcall *encryptData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Asymmetric::Padding, Crypto::Asymmetric::PubKeyFormat);
  std::string *(__fastcall *decryptData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Asymmetric::Padding);
  std::string *(__fastcall *signData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Hash::HashType);
  bool (__fastcall *verifyData)(Crypto::Asymmetric::ISystemInterface *this, const std::string *, const std::string *, const std::string *, Crypto::Hash::HashType);
  std::string *(__fastcall *computeSharedSecret)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *);
  bool (__fastcall *ECCompressedKeyToPoint)(Crypto::Asymmetric::ISystemInterface *this, const std::string *, std::vector<unsigned char> *, std::vector<unsigned char> *);
  std::string *(__fastcall *getSystemAsString)(Crypto::Asymmetric::ISystemInterface *this, std::string *result);
};

```

### `Crypto::Asymmetric::Asymmetric`
```
struct __cppobj Crypto::Asymmetric::Asymmetric : Crypto::Asymmetric::ISystemInterface
{
  Crypto::Asymmetric::System mSystem;
  std::unique_ptr<Crypto::Asymmetric::ISystemInterface> mInterface;
};

```

### `Crypto::Asymmetric::Asymmetric_vtbl`
```
struct /*VFT*/ Crypto::Asymmetric::Asymmetric_vtbl
{
  void (__fastcall *~ISystemInterface)(Crypto::Asymmetric::ISystemInterface *this);
  bool (__fastcall *generateKeyPair)(Crypto::Asymmetric::ISystemInterface *this, std::string *, std::string *);
  std::string *(__fastcall *encryptData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Asymmetric::Padding, Crypto::Asymmetric::PubKeyFormat);
  std::string *(__fastcall *decryptData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Asymmetric::Padding);
  std::string *(__fastcall *signData)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *, Crypto::Hash::HashType);
  bool (__fastcall *verifyData)(Crypto::Asymmetric::ISystemInterface *this, const std::string *, const std::string *, const std::string *, Crypto::Hash::HashType);
  std::string *(__fastcall *computeSharedSecret)(Crypto::Asymmetric::ISystemInterface *this, std::string *result, const std::string *, const std::string *);
  bool (__fastcall *ECCompressedKeyToPoint)(Crypto::Asymmetric::ISystemInterface *this, const std::string *, std::vector<unsigned char> *, std::vector<unsigned char> *);
  std::string *(__fastcall *getSystemAsString)(Crypto::Asymmetric::ISystemInterface *this, std::string *result);
};

```

### `CommandOutputSender`
```
struct __cppobj CommandOutputSender
{
  CommandOutputSender_vtbl *__vftable /*VFT*/;
  Automation::AutomationClient *mAutomationClient;
  std::function<void __cdecl(AutomationCmdOutput &)> mEmplaceTestCommandOutputCallback;
};

```

### `CommandOutputSender_vtbl`
```
struct /*VFT*/ CommandOutputSender_vtbl
{
  void (__fastcall *~CommandOutputSender)(CommandOutputSender *this);
  void (__fastcall *send)(CommandOutputSender *this, const CommandOrigin *, const CommandOutput *);
  void (__fastcall *registerOutputCallback)(CommandOutputSender *this, const std::function<void __cdecl(AutomationCmdOutput &)> *);
};

```

### `Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>
{
  Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<Automation::AutomationObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<Automation::AutomationObserver,Core::SingleThreadedLock>)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Automation::AutomationObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<Automation::AutomationObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<Automation::AutomationObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<Automation::AutomationObserver *>> mObservers;
};

```

### `Command`
```
struct __cppobj __declspec(align(4)) Command
{
  Command_vtbl *__vftable /*VFT*/;
  int mVersion;
  const CommandRegistry *mRegistry;
  int mCommandSymbol;
  _BYTE mPermissionLevel[1];
  CommandFlag mFlags;
};

```

### `Command_vtbl`
```
struct /*VFT*/ Command_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ClientBlobCache::Server::ActiveTransfersManager`
```
struct __cppobj ClientBlobCache::Server::ActiveTransfersManager
{
  std::unordered_map<NetworkIdentifier,std::unique_ptr<ClientBlobCache::Server::ActiveTransfersManager::TransferTracker>> mTransferTrackerMap;
  std::map<unsigned __int64,std::weak_ptr<ClientBlobCache::Server::Blob>> mSentBlobs;
  unsigned __int64 mCacheSizeBytes;
};

```

### `ClientBlobCache::Server::ActiveTransfersManager::TransferTracker`
```
struct __cppobj __declspec(align(8)) ClientBlobCache::Server::ActiveTransfersManager::TransferTracker
{
  ClientBlobCache::Server::ActiveTransfersManager *mCache;
  const NetworkIdentifier mOwner;
  std::vector<ClientBlobCache::Server::ActiveTransfer> mTransfers;
  unsigned int mMaxConcurrentTransfers;
};

```

### `ClassroomModeNetworkHandler`
```
struct __cppobj __declspec(align(8)) ClassroomModeNetworkHandler : NetEventCallback, Bedrock::Threading::EnableQueueForMainThread
{
  Automation::AutomationClient *mAutomationClient;
  std::unique_ptr<RoleChecker> mRoleChecker;
  std::string mTenantId;
  std::string mLastRequestAddress;
  bool mIsDedicatedServer;
};

```

### `Core::FileStdStreamBuf_vtbl`
```
struct /*VFT*/ Core::FileStdStreamBuf_vtbl
{
  void (__fastcall *~basic_streambuf<char,std::char_traits<char> >)(std::streambuf *this);
  void (__fastcall *_Lock)(std::streambuf *this);
  void (__fastcall *_Unlock)(std::streambuf *this);
  int (__fastcall *overflow)(std::streambuf *this, int);
  int (__fastcall *pbackfail)(std::streambuf *this, int);
  __int64 (__fastcall *showmanyc)(std::streambuf *this);
  int (__fastcall *underflow)(std::streambuf *this);
  int (__fastcall *uflow)(std::streambuf *this);
  __int64 (__fastcall *xsgetn)(std::streambuf *this, char *, __int64);
  __int64 (__fastcall *xsputn)(std::streambuf *this, const char *, __int64);
  std::fpos<_Mbstatet> *(__fastcall *seekoff)(std::streambuf *this, std::fpos<_Mbstatet> *result, __int64, int, int);
  std::fpos<_Mbstatet> *(__fastcall *seekpos)(std::streambuf *this, std::fpos<_Mbstatet> *result, std::fpos<_Mbstatet>, int);
  std::streambuf *(__fastcall *setbuf)(std::streambuf *this, char *, __int64);
  int (__fastcall *sync)(std::streambuf *this);
  void (__fastcall *imbue)(std::streambuf *this, const std::locale *);
};

```

### `Core::FileStream_vtbl`
```
struct /*VFT*/ Core::FileStream_vtbl
{
  void *(__fastcall *__vecDelDtor)(Core::FileStream *this, unsigned int);
};

```

### `Core::OutputFileStream_vtbl`
```
struct /*VFT*/ Core::OutputFileStream_vtbl
{
  void *(__fastcall *__vecDelDtor)(Core::OutputFileStream *this, unsigned int);
};

```

### `CatalogBackend`
```
struct __cppobj __declspec(align(8)) CatalogBackend
{
  CatalogBackend_vtbl *__vftable /*VFT*/;
  CatalogProviderId mProviderId;
};

```

### `CatalogBackend_vtbl`
```
struct /*VFT*/ CatalogBackend_vtbl
{
  void (__fastcall *~CatalogBackend)(CatalogBackend *this);
  const std::string *(__fastcall *getCachedFilePrefix)(CatalogBackend *this);
  bool (__fastcall *usePascalCase)(CatalogBackend *this);
};

```

### `CustomDocumentModifier`
```
struct __cppobj CustomDocumentModifier
{
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
};

```

### `CommonContent`
```
struct __cppobj CommonContent
{
  std::string id;
  std::string url;
  std::string type;
  std::string maxClientVersion;
  std::string minClientVersion;
  std::vector<std::string> tags;
};

```

### `CommonImage`
```
struct __cppobj CommonImage
{
  std::string id;
  std::string tag;
  std::string type;
  std::string url;
};

```

### `ContentCatalogPackSource`
```
struct __cppobj __declspec(align(8)) ContentCatalogPackSource : PackSource
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  IEntitlementManager *mEntitlementManager;
  bool mEnabled;
  std::shared_ptr<bool> mExistenceTracker;
  int mIconFetchesRemaining;
  ContentCatalogPackSource::FetchingState mFetchingCatalogEntries;
  std::vector<std::unique_ptr<Pack>> mPacks;
  std::vector<DurableDocument> mDocuments;
  std::function<void __cdecl(bool)> mOnAsyncLoadComplete;
  bool mHighPriorityIconRequests;
};

```

### `ContentCatalogPackSource_vtbl`
```
struct /*VFT*/ ContentCatalogPackSource_vtbl
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

### `CatalogCollection`
```
struct __cppobj CatalogCollection
{
  StoreCatalogRepository *mStoreCatalog;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  IEntitlementManager *mEntitlementManager;
  StoreCatalogItem *mInvalidItem;
  std::shared_ptr<bool> mExistenceTracker;
  std::shared_ptr<CatalogCollection::CatalogCollectionListener> mEntitlementChangeListener;
  __int64 mSaleExpirationTime;
  std::vector<gsl::not_null<StoreCatalogItem *>> mContents;
  std::unordered_set<std::string> mContentProductIds;
  std::function<bool __cdecl(StoreCatalogItem const &)> mFilterOutIfTrue;
  int mItemLimit;
  std::vector<std::shared_ptr<SearchQuery>> mQueries;
  std::vector<CatalogCollection::QueryContentInfo> mContentCountPerQuery;
  bool mFetchingItems;
  bool mHasUpcomingSale;
  bool mFilterOwnedToBack;
  bool mFilterOutInvalidOffers;
  bool mClientSortEnabled;
  bool mTotalNumberOffersSent;
  bool mSent;
  bool mIsPromoRow;
  bool mDirty;
  bool mReady;
  int mQueryIndex;
  int mContentFetchLimit;
  int mVisibleItemsPerPage;
  int mFirstVisibleItemIndex;
  std::mutex mContentCheck;
};

```

### `CatalogCollection::CatalogCollectionListener`
```
struct __cppobj CatalogCollection::CatalogCollectionListener : EntitlementChangeListener
{
  CatalogCollection *mCollection;
};

```

### `CatalogCollection::CatalogCollectionListener_vtbl`
```
struct /*VFT*/ CatalogCollection::CatalogCollectionListener_vtbl
{
  void (__fastcall *~EntitlementChangeListener)(EntitlementChangeListener *this);
  void (__fastcall *_onEntitlementChanged)(EntitlementChangeListener *this);
};

```

### `CatalogCollection::QueryContentInfo`
```
struct __cppobj __declspec(align(4)) CatalogCollection::QueryContentInfo
{
  int mTotalContentCount;
  int mFilteredContent;
  int mSkipAmount;
  int mPossibleContent;
  bool mHasCheckedContentCount;
  bool mHasExhaustedQuery;
};

```

### `CarouselComponent`
```
struct __cppobj CarouselComponent : StoreUIComponent
{
  bool mShouldCarouselCycle;
  std::vector<std::shared_ptr<StoreVisualStyle>> mCarouselStyles;
  int mCurrentCarouselPage;
  float mCarouselTimer;
  int mCarouselTimerDuration;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mTimeLastChecked;
};

```

### `CarouselComponent_vtbl`
```
struct /*VFT*/ CarouselComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `ContentCatalogService`
```
struct __cppobj ContentCatalogService : ServiceClient, Bedrock::EnableNonOwnerReferences
{
  std::shared_ptr<CatalogBackend> mCatalogBackendPlayFab;
  std::shared_ptr<CatalogBackend> mCatalogBackendXforge;
  std::shared_ptr<CatalogBackend> mCatalogBackendPersonaService;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  CustomDocumentModifier mCustomModifier;
  std::unique_ptr<OwnedDurablesPagingCache> mOwnedDurablesPagingInterface;
  std::string mAcceptLanguage;
  const Core::PathBuffer<std::string > mDefaultCacheLocation;
  std::unordered_map<enum CatalogRequestType,Core::PathBuffer<std::string >> mCacheLocationPerType;
  std::string mPlatformOverride;
  std::shared_ptr<bool> mExistenceTracker;
  unsigned int mCacheDurationSeconds;
  int mCacheExpirationOffsetSec;
};

```

### `ContentCatalogService_vtbl`
```
struct /*VFT*/ ContentCatalogService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `ControllerIDtoClientMap`
```
struct __cppobj __declspec(align(8)) ControllerIDtoClientMap
{
  std::map<int,std::weak_ptr<IClientInstance>> controllerIDtoClientMap;
  bool useGameControllerId;
  bool onScreenAcceptingAllControllerInput;
  bool acceptInputFromAllControllers;
  bool inGame;
  int primaryUserControllerId;
  int lastInputUserControllerId;
};

```

### `Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>
{
  Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<LevelLocationObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<LevelLocationObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<LevelLocationObserver,Core::SingleThreadedLock>)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<LevelLocationObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<LevelLocationObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<LevelLocationObserver *>> mObservers;
};

```

### `ClientBlockPipeline::BlockSchematicPart`
```
struct __cppobj ClientBlockPipeline::BlockSchematicPart
{
  std::vector<ClientBlockPipeline::BoxSchematic> mBoxes;
  std::string mName;
};

```

### `ClientBlockPipeline::BlockSchematic`
```
struct __cppobj ClientBlockPipeline::BlockSchematic
{
  Matrix mModelToGridTransform;
  std::vector<ClientBlockPipeline::BlockSchematicPart> mParts;
  std::vector<std::string> mMaterialNames;
};

```

### `ClientBlockPipeline::Material`
```
const struct __cppobj __declspec(align(8)) ClientBlockPipeline::Material : Bedrock::EnableNonOwnerReferences
{
  const TerrainLayer *mTerrainLayer;
  TextureUVCoordinateSet mUvSet;
  bool mAmbientOcclusion;
  bool mFaceDimming;
};

```

### `ClientBlockPipeline::MaterialRepository`
```
struct __cppobj ClientBlockPipeline::MaterialRepository
{
  std::vector<std::shared_ptr<ClientBlockPipeline::Material const >> mMaterials;
};

```

### `ClientBlockPipeline::SchematicsRepository`
```
struct __cppobj ClientBlockPipeline::SchematicsRepository
{
  std::unordered_map<HashedString,std::shared_ptr<ClientBlockPipeline::BlockSchematic>> mSchematicNameMap;
  std::shared_ptr<ClientBlockPipeline::MaterialRepository> mMaterialRepository;
};

```

### `CallbackTokenContext<std::function<void __cdecl(enum Social::UserPlatformConnectionResult)> >`
```
struct __cppobj CallbackTokenContext<std::function<void __cdecl(enum Social::UserPlatformConnectionResult)> >
{
  std::vector<std::function<void __cdecl(enum Social::UserPlatformConnectionResult)>> mCallbacks;
  std::shared_ptr<CallbackTokenCancelState> mCancelState;
};

```

### `CallbackTokenContext<std::function<void __cdecl(Core::Result)> >`
```
struct __cppobj CallbackTokenContext<std::function<void __cdecl(Core::Result)> >
{
  std::vector<std::function<void __cdecl(Core::Result)>> mCallbacks;
  std::shared_ptr<CallbackTokenCancelState> mCancelState;
};

```

### `Core::RemoteStorageProvider`
```
struct __cppobj Core::RemoteStorageProvider
{
  Core::RemoteStorageProvider_vtbl *__vftable /*VFT*/;
  std::map<std::string,std::string> mContainerRoots;
};

```

### `Core::RemoteStorageManifest::BlobSequence`
```
struct __cppobj __declspec(align(8)) Core::RemoteStorageManifest::BlobSequence
{
  std::string mName;
  int mNumber;
};

```

### `Core::RemoteStorageManifest::BlobRecord`
```
struct __cppobj Core::RemoteStorageManifest::BlobRecord
{
  std::vector<Core::RemoteStorageManifest::BlobSequence> mBlobSequences;
  std::string mDecodedName;
  unsigned __int64 mChunkSize;
};

```

### `Core::RemoteStorageManifest`
```
struct __cppobj Core::RemoteStorageManifest
{
  std::map<std::string,Core::RemoteStorageManifest::BlobRecord> mCorrelationTable;
  Core::RemoteStorageManifest::State mState;
  std::string mContainerName;
};

```

### `Core::RemoteStorageProvider_vtbl`
```
struct /*VFT*/ Core::RemoteStorageProvider_vtbl
{
  void (__fastcall *~RemoteStorageProvider)(Core::RemoteStorageProvider *this);
  void (__fastcall *shutdown)(Core::RemoteStorageProvider *this);
  const std::string *(__fastcall *getWorldsPrefix)(Core::RemoteStorageProvider *this);
  std::string *(__fastcall *encodeWorldName)(Core::RemoteStorageProvider *this, std::string *result, const std::string *);
  std::string *(__fastcall *encodeFileName)(Core::RemoteStorageProvider *this, std::string *result, const std::string *);
  void (__fastcall *tick)(Core::RemoteStorageProvider *this);
  void (__fastcall *onAppSuspend)(Core::RemoteStorageProvider *this);
  void (__fastcall *onAppResume)(Core::RemoteStorageProvider *this);
  void (__fastcall *onSignOut)(Core::RemoteStorageProvider *this);
  CallbackToken *(__fastcall *onSignIn)(Core::RemoteStorageProvider *this, CallbackToken *result, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >);
  CallbackToken *(__fastcall *deleteContainer)(Core::RemoteStorageProvider *this, CallbackToken *result, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >, const std::string *);
  CallbackToken *(__fastcall *commit)(Core::RemoteStorageProvider *this, CallbackToken *result, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >, const std::string *, const std::set<std::string> *, std::set<std::string> *, std::set<std::string> *);
  CallbackToken *(__fastcall *sync)(Core::RemoteStorageProvider *this, CallbackToken *result, const std::string *, const std::string *, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >, std::function<void __cdecl(std::string const &,bool)>);
  CallbackToken *(__fastcall *syncMeta)(Core::RemoteStorageProvider *this, CallbackToken *result, const std::string *, const std::string *, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >);
  CallbackToken *(__fastcall *syncContainerManifest)(Core::RemoteStorageProvider *this, CallbackToken *result, const std::string *, const std::string *, std::shared_ptr<CallbackTokenContext<std::function<void __cdecl(Core::Result)> > >);
  Core::RemoteStorageManifest *(__fastcall *getManifest)(Core::RemoteStorageProvider *this, Core::RemoteStorageManifest *result, const std::string *);
};

```

### `CloudSaveSystemWrapper`
```
struct __cppobj CloudSaveSystemWrapper : OptionsObserver
{
  std::unique_ptr<GameSaveSystem> mGameSaveSystem;
  std::weak_ptr<Social::User> mOwningUser;
  std::function<void __cdecl(std::function<void __cdecl(void)>)> mInitRemoteSystemCallback;
};

```

### `CloudSaveSystemWrapper_vtbl`
```
struct /*VFT*/ CloudSaveSystemWrapper_vtbl
{
  void (__fastcall *~Observer<OptionsObserver,Core::SingleThreadedLock>)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onForceCloudSave)(OptionsObserver *this);
  void (__fastcall *onOptionsLoadBegin)(OptionsObserver *this);
  void (__fastcall *onOptionsLoadComplete)(OptionsObserver *this);
};

```

### `cg::ResourceManager<std::shared_ptr<mce::Image>,ResourceLocation,ImageTrackerTemplate<ImageResourceManager>,std::shared_ptr<mce::Image>,std::unordered_map>`
```
struct __cppobj cg::ResourceManager<std::shared_ptr<mce::Image>,ResourceLocation,ImageTrackerTemplate<ImageResourceManager>,std::shared_ptr<mce::Image>,std::unordered_map>
{
  std::unordered_map<ResourceLocation,std::shared_ptr<mce::Image>> mContainer;
};

```

### `cg::ResourceManager<std::shared_ptr<mce::Image>,enum mce::DynamicTexture,ImageTrackerTemplate<DynamicImageResourceManager>,std::shared_ptr<mce::Image>,std::map>`
```
struct __cppobj cg::ResourceManager<std::shared_ptr<mce::Image>,enum mce::DynamicTexture,ImageTrackerTemplate<DynamicImageResourceManager>,std::shared_ptr<mce::Image>,std::map>
{
  std::map<enum mce::DynamicTexture,std::shared_ptr<mce::Image>> mContainer;
};

```

### `cg::ResourceManager<std::shared_ptr<mce::ClientTexture>,enum mce::DynamicTexture,void,std::shared_ptr<mce::ClientTexture>,std::map>`
```
struct __cppobj cg::ResourceManager<std::shared_ptr<mce::ClientTexture>,enum mce::DynamicTexture,void,std::shared_ptr<mce::ClientTexture>,std::map>
{
  std::map<enum mce::DynamicTexture,std::shared_ptr<mce::ClientTexture>> mContainer;
};

```

### `ChannelService`
```
struct __cppobj ChannelService : ServiceClient
{
  const WorldTemplateManager *mWorldTemplateManager;
  gsl::not_null<Bedrock::NonOwnerPointer<DateManager const > > mDateManager;
  std::string mAcceptLanguage;
  const Core::PathBuffer<std::string > mDefaultCacheLocation;
  const std::string mHostUrl;
  unsigned int mCacheDurationHours;
  std::string mUserToken;
  std::shared_ptr<LessonItemCache> mItemCache;
};

```

### `ChannelService_vtbl`
```
struct /*VFT*/ ChannelService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `ControlScreenAction_vtbl`
```
struct /*VFT*/ ControlScreenAction_vtbl
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

### `CaretMeasureData`
```
const struct __cppobj __declspec(align(4)) CaretMeasureData
{
  const int position;
  const bool shouldRender;
};

```

### `CachedScene`
```
struct __cppobj CachedScene
{
  std::unique_ptr<VisualTree> mVisualTree;
  std::shared_ptr<UIControlFactory> mControlFactory;
  std::unique_ptr<LayoutManager> mLayoutManager;
};

```

### `CachedScenes`
```
struct __cppobj CachedScenes
{
  bool mLowMemoryDevice;
  std::unique_ptr<TaskGroup> mDestroyScreenTaskGroup;
  std::map<Json::Value,std::unique_ptr<CachedScene>> mCachedScene;
};

```

### `CustomRenderComponent`
```
struct __cppobj CustomRenderComponent : RenderableComponent
{
  std::shared_ptr<UICustomRenderer> mRenderer;
};

```

### `ComponentRenderBatch`
```
struct __cppobj ComponentRenderBatch
{
  BatchKey mBatchKey;
  bool mIsDirty;
  bool mRequiresPreRenderSetup;
  int mRenderPass;
  std::vector<CustomRenderComponent *> mCustomRenderInstances;
  std::vector<SpriteComponent *> mSpriteInstances;
  std::vector<TextComponent *> mTextInstances;
};

```

### `CustomRenderComponent_vtbl`
```
struct /*VFT*/ CustomRenderComponent_vtbl
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
  UIBatchType (__fastcall *getBatchType)(CustomRenderComponent *this);
  int (__fastcall *getCustomId)(CustomRenderComponent *this);
  int (__fastcall *getNumRenderPasses)(CustomRenderComponent *this);
  UIMaterialType (__fastcall *getUIMaterialType)(CustomRenderComponent *this, int);
  ResourceLocation *(__fastcall *getResourceLocation)(CustomRenderComponent *this, ResourceLocation *result, int, int);
  bool (__fastcall *getRequiresPreRenderSetup)(CustomRenderComponent *this, int);
  void (__fastcall *collectScreenEvents)(CustomRenderComponent *this, std::queue<ScreenEvent> *);
};

```

### `ContentItem`
```
struct __cppobj ContentItem
{
  ContentItem_vtbl *__vftable /*VFT*/;
  unsigned __int64 mId;
  std::string mName;
  std::string mDescription;
  unsigned __int64 mSize;
  bool mIsDescriptionExpanded;
  __declspec(align(8)) _BYTE mType[8];
  _BYTE mItemType[8];
  _BYTE mFlags[8];
  ContentSource *mSource;
};

```

### `ContentItem_vtbl`
```
struct /*VFT*/ ContentItem_vtbl
{
  void (__fastcall *~ContentItem)(ContentItem *this);
};

```

### `ContentSource_vtbl`
```
struct /*VFT*/ ContentSource_vtbl
{
  void (__fastcall *~ContentSource)(ContentSource *this);
  void (__fastcall *load)(ContentSource *this);
  void (__fastcall *generateItems)(ContentSource *this, std::vector<std::unique_ptr<ContentItem>> *);
  void (__fastcall *save)(ContentSource *this);
  void (__fastcall *deleteContentFiles)(ContentSource *this, std::vector<ContentItem const *>);
  void (__fastcall *postDeleteContent)(ContentSource *this, std::vector<ContentItem const *>);
};

```

### `ContentManager`
```
struct __cppobj ContentManager : LevelLocationObserver, std::enable_shared_from_this<ContentManager>
{
  Core::FilePathManager *mFilePathManager;
  LevelListCache *mLevelListCache;
  WorldTemplateManager *mWorldTemplateManager;
  ResourcePackRepository *mResourcePackRepository;
  ResourcePackManager *mResourcePackManager;
  PackManifestFactory *mPackManifestFactory;
  IEntitlementManager *mEntitlementManager;
  const ContentTierManager *mContentTierManager;
  gsl::not_null<Bedrock::NonOwnerPointer<StoreCatalogRepository> > mStoreCatalog;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mContentCatalogService;
  PackSourceFactory *mPackSourceFactory;
  std::vector<std::unique_ptr<ContentItem>> mContent;
  std::vector<std::unique_ptr<ContentSource>> mContentSources;
  std::vector<ContentManagerContext *> mContexts;
  unsigned __int64 mContentId;
  ContentCatalogPackSource *mCatalogResourcePackSource;
  std::unique_ptr<ContentManagerProxy> mProxy;
  bool mInitialized;
  const std::string WORLD_RESOURCE_PACK_FILENAME;
  const std::string WORLD_BEHAVIOR_PACK_FILENAME;
};

```

### `ContentView::ItemCollection`
```
struct __cppobj ContentView::ItemCollection
{
  std::unique_ptr<ContentItem> mItemProxy;
  std::vector<ContentItem *> mItems;
  std::function<bool __cdecl(ContentItem const *)> mPredicate;
};

```

### `ContentView`
```
struct __cppobj ContentView
{
  ContentManager *mContentManager;
  std::vector<ContentItem *> mItems;
  std::function<bool __cdecl(ContentItem const *)> mPredicate;
  std::function<bool __cdecl(ContentItem *,ContentItem *)> mSortFunction;
  std::function<void __cdecl(void)> mOnReload;
  std::vector<std::unique_ptr<ContentView::ItemCollection>> mItemCollections;
  std::vector<ContentView const *> mContentViewSources;
};

```

### `ContentManagerContext`
```
struct __cppobj ContentManagerContext
{
  std::function<bool __cdecl(ContentItem const *)> mContextPredicate;
  std::vector<std::unique_ptr<ContentView>> mContentViews;
  ContentManager *mManager;
};

```

### `ContentManagerProxyCallbacks`
```
struct __cppobj ContentManagerProxyCallbacks
{
  std::function<ContentItem * __cdecl(PackManifest &)> mGetContentItemByManifest;
};

```

### `ContentManagerProxy`
```
struct __cppobj ContentManagerProxy
{
  ContentManagerProxyCallbacks mCallbacks;
};

```

### `ContentManager_vtbl`
```
struct /*VFT*/ ContentManager_vtbl
{
  void (__fastcall *~Observer<LevelLocationObserver,Core::SingleThreadedLock>)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<LevelLocationObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onLevelAdded)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelUpdated)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onLevelDeleted)(LevelLocationObserver *this, const std::string *);
  void (__fastcall *onStorageChanged)(LevelLocationObserver *this);
};

```

### `ClientModel`
```
struct __cppobj ClientModel
{
  ClientModel_vtbl *__vftable /*VFT*/;
};

```

### `ClientModel_vtbl`
```
struct /*VFT*/ ClientModel_vtbl
{
  void (__fastcall *~ClientModel)(ClientModel *this);
  bool (__fastcall *hasCommandsEnabled)(ClientModel *this);
  std::string *(__fastcall *getFormattedHoverText)(ClientModel *this, std::string *result, const ItemStackBase *, const bool);
  bool (__fastcall *achievementsWillBeDisabledOnLoad)(ClientModel *this);
  bool (__fastcall *hasAchievementsDisabled)(ClientModel *this);
  std::string *(__fastcall *getLevelName)(ClientModel *this, std::string *result);
  int (__fastcall *getGameDifficulty)(ClientModel *this);
  int (__fastcall *getGameType)(ClientModel *this);
  void (__fastcall *setGameType)(ClientModel *this, GameType);
  int (__fastcall *getGenerator)(ClientModel *this);
  bool (__fastcall *getStartWithMap)(ClientModel *this);
  bool (__fastcall *isAlwaysDay)(ClientModel *this);
  bool (__fastcall *isGameRule)(ClientModel *this, GameRuleId);
  bool (__fastcall *isImmutableWorld)(ClientModel *this);
  std::unique_ptr<PlayerCommandOrigin> *(__fastcall *makePlayerCommandOrigin)(ClientModel *this, std::unique_ptr<PlayerCommandOrigin> *result);
  void (__fastcall *setCommandsEnabled)(ClientModel *this, bool);
  void (__fastcall *disableAchievements)(ClientModel *this);
  float (__fastcall *getGuiScale)(ClientModel *this);
  const Option *(__fastcall *getGuiScaleOption)(ClientModel *this);
  void (__fastcall *setGuiScaleOffset)(ClientModel *this, int);
  void (__fastcall *notifyForLeaveGame)(ClientModel *this);
};

```

### `ClientInstanceModel`
```
struct __cppobj ClientInstanceModel : ClientModel
{
  IClientInstance *mClient;
};

```

### `ClientInstanceModel_vtbl`
```
struct /*VFT*/ ClientInstanceModel_vtbl
{
  void (__fastcall *~ClientModel)(ClientModel *this);
  bool (__fastcall *hasCommandsEnabled)(ClientModel *this);
  std::string *(__fastcall *getFormattedHoverText)(ClientModel *this, std::string *result, const ItemStackBase *, const bool);
  bool (__fastcall *achievementsWillBeDisabledOnLoad)(ClientModel *this);
  bool (__fastcall *hasAchievementsDisabled)(ClientModel *this);
  std::string *(__fastcall *getLevelName)(ClientModel *this, std::string *result);
  int (__fastcall *getGameDifficulty)(ClientModel *this);
  int (__fastcall *getGameType)(ClientModel *this);
  void (__fastcall *setGameType)(ClientModel *this, GameType);
  int (__fastcall *getGenerator)(ClientModel *this);
  bool (__fastcall *getStartWithMap)(ClientModel *this);
  bool (__fastcall *isAlwaysDay)(ClientModel *this);
  bool (__fastcall *isGameRule)(ClientModel *this, GameRuleId);
  bool (__fastcall *isImmutableWorld)(ClientModel *this);
  std::unique_ptr<PlayerCommandOrigin> *(__fastcall *makePlayerCommandOrigin)(ClientModel *this, std::unique_ptr<PlayerCommandOrigin> *result);
  void (__fastcall *setCommandsEnabled)(ClientModel *this, bool);
  void (__fastcall *disableAchievements)(ClientModel *this);
  float (__fastcall *getGuiScale)(ClientModel *this);
  const Option *(__fastcall *getGuiScaleOption)(ClientModel *this);
  void (__fastcall *setGuiScaleOffset)(ClientModel *this, int);
  void (__fastcall *notifyForLeaveGame)(ClientModel *this);
};

```

### `Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>
{
  Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<Social::UserListObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<Social::UserListObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<Social::UserListObserver,Core::SingleThreadedLock>)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<Social::UserListObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<Social::UserListObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<Social::UserListObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<Social::UserListObserver *>> mObservers;
};

```

### `ChannelTransform`
```
struct __cppobj ChannelTransform
{
  ExpressionNode mXYZ[3];
  Vec3 mAxis;
  ChannelTransformAxisType mTransformDataType;
};

```

### `ChannelTransform_Float`
```
struct __cppobj ChannelTransform_Float
{
  float mXYZ[3];
};

```

### `ChunkVisibilityCacheElement`
```
struct __cppobj ChunkVisibilityCacheElement
{
  unsigned __int8 mVisibility[6];
  unsigned __int16 mLatticeLookup;
  float mDistance;
  unsigned __int8 mCanSeeChunkBitfield;
  unsigned __int8 mChunkIsEmpty : 1;
  unsigned __int8 mChunkVisible : 1;
  unsigned __int8 mChunkAccessBitX : 1;
  unsigned __int8 mChunkAccessBitY : 1;
  unsigned __int8 mChunkAccessBitZ : 1;
  unsigned __int8 mIsSkyLit : 1;
  unsigned __int8 mAllSidesCanSeeAllSides : 1;
  unsigned __int8 mForceRequery : 1;
  unsigned __int8 mUpdateCounter;
  unsigned __int8 mInitted;
};

```

### `ChunkVisibilityCache`
```
struct __cppobj __declspec(align(4)) ChunkVisibilityCache
{
  std::vector<ChunkVisibilityCacheElement> mCache;
  int mCacheSideMask;
  unsigned __int8 mCacheSideShift;
  unsigned __int8 mCacheDoubleSideShift;
};

```

### `ClientBlockPipeline::SimpleMesh`
```
struct __cppobj ClientBlockPipeline::SimpleMesh
{
  mce::MeshData mMeshData;
  std::vector<TessellatorQuadInfo> mQuadInfoList;
};

```

### `ClientBlockPipeline::NamedMeshStreams`
```
struct __cppobj ClientBlockPipeline::NamedMeshStreams
{
  std::unordered_map<TerrainLayer const *,ClientBlockPipeline::SimpleMesh> mStreams;
};

```

### `ClientBlockPipeline::BlockTessellatorPipeline`
```
struct __cppobj ClientBlockPipeline::BlockTessellatorPipeline
{
  ClientBlockPipeline::NamedMeshStreams mMeshStreams;
};

```

### `ClientBlockPipeline::Step`
```
const struct __cppobj ClientBlockPipeline::Step
{
  ClientBlockPipeline::Step_vtbl *__vftable /*VFT*/;
  unsigned __int64 mStepId;
};

```

### `ClientBlockPipeline::PipelineError`
```
struct __cppobj ClientBlockPipeline::PipelineError
{
  std::string mError;
};

```

### `ClientBlockPipeline::StepResult`
```
struct __cppobj ClientBlockPipeline::StepResult
{
  std::variant<ClientBlockPipeline::PipelineError,std::vector<std::any> > mResults;
};

```

### `ClientBlockPipeline::Step_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::Step_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::Description`
```
struct __cppobj ClientBlockPipeline::Description
{
  std::vector<std::shared_ptr<ClientBlockPipeline::Step const >> mSteps;
  std::vector<std::shared_ptr<ClientBlockPipeline::Step const >> mOutputs;
  std::vector<ClientBlockPipeline::Description::BakedStep> mBakedSteps;
};

```

### `CommandListBase`
```
struct __cppobj CommandListBase
{
};

```

### `cg::details::LambdaExecutorContextContainer<std::nullptr_t,0>`
```
struct __declspec(align(8)) cg::details::LambdaExecutorContextContainer<std::nullptr_t,0>
{
  __int16 mContext;
};

```

### `cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>`
```
struct __cppobj cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>
{
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(std::nullptr_t &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>> mWorkQueue;
  __int16 *mContext;
};

```

### `cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>`
```
struct __cppobj cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>
{
  cg::details::LambdaExecutorContextContainer<std::nullptr_t,0> mContextContainer;
  __int16 *mContext;
  cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1> mExecutionPolicy;
};

```

### `cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> >`
```
struct __cppobj __declspec(align(8)) cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> >
{
  std::unique_ptr<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>> mExecutionContext;
  std::atomic<int> mPendingWorkCount;
};

```

### `cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >`
```
struct __cppobj cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >
{
  cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > mScheduler;
};

```

### `cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>`
```
struct __cppobj cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>
{
};

```

### `cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0>`
```
struct __cppobj cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0> : cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>
{
  cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > > *mDispatcher;
};

```

### `cg::details::SpecializedScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,void>`
```
struct __cppobj cg::details::SpecializedScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,void> : cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0>
{
};

```

### `CommandListQueue`
```
struct __cppobj CommandListQueue
{
  CommandListTaskContext mGlobalContext;
  bool mIsAsync;
  mce::RenderContext *mGlobalRenderContext;
  cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > > mDragonDispatcher;
  std::unique_ptr<cg::details::SpecializedScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,void>> mDragonDispatcherScope;
  Bedrock::Threading::InstancedThreadLocal<ThreadedFrameConstantsContainer,std::allocator<ThreadedFrameConstantsContainer> > mPerThreadContextConstants;
};

```

### `Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>
{
  Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<hbui::RouterObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<hbui::RouterObserver,Core::SingleThreadedLock>)(Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<hbui::RouterObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<hbui::RouterObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<hbui::RouterObserver *>> mObservers;
};

```

### `ContentDiscovery`
```
struct __cppobj ContentDiscovery
{
  IContentDiscoveryListener *mContentDiscoveryListener;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  PackSourceFactory *mPackSourceFactory;
  const int SEARCH_BATCH_SIZE;
  const int SEARCH_PAGE_SIZE;
  std::shared_ptr<bool> mExistenceTracker;
};

```

### `ContentTracker`
```
struct __cppobj ContentTracker
{
  bool mUsePersonaService;
  IContentEventListener *mEventListener;
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  ExternalContentManager *mExternalContentManager;
  Bedrock::NonOwnerPointer<SoundEngine> mSoundEngine;
  std::function<std::shared_ptr<DlcImportContext> __cdecl(bool,Core::Path const &,std::function<void __cdecl(bool)>,std::function<void __cdecl(bool,PackManifest const *)>)> mDlcImportContextFactory;
  PropertyBag mProperties;
  int mPropertyChangeVersion;
  std::string mContentUrl;
  std::string mTitle;
  unsigned __int64 mFileSize;
  bool mTitleLocked;
  bool mHasHydrated;
  std::shared_ptr<TaskGroup> mIOTaskGroup;
  std::shared_ptr<FileDownloadManager> mFileDownloadManager;
  std::shared_ptr<DlcImportContext> mImportContext;
  std::shared_ptr<bool> mExistenceTracker;
  bool mReleaseDownloader;
  int mDownloadRetryAttempts;
  std::chrono::duration<__int64,std::ratio<1,1> > mDownloadRetryDelay;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mDownloadFailureTime;
};

```

### `ContentAcquisition::PackImportCallbackInfo`
```
struct __cppobj ContentAcquisition::PackImportCallbackInfo
{
  bool mShouldCheckExistence;
  std::weak_ptr<bool> mExistenceTracker;
  std::function<void __cdecl(PackImportStateObject &)> mCallback;
};

```

### `ContentAcquisition`
```
struct __cppobj ContentAcquisition : IContentEventListener, IContentDiscoveryListener, IContentAcquisition, Bedrock::EnableNonOwnerReferences
{
  gsl::not_null<Bedrock::NonOwnerPointer<ContentCatalogService> > mCatalogService;
  ExternalContentManager *mExternalContentManager;
  ResourcePackRepository *mResourcePackRepository;
  ResourcePackManager *mResourcePackManager;
  WorldTemplateManager *mTemplateManager;
  IMinecraftEventing *mEventing;
  ToastManager *mToastManager;
  Bedrock::NonOwnerPointer<SoundEngine> mSoundEngine;
  bool mStarted;
  __declspec(align(4)) RetryDelay mAutoSaveRetry;
  RetryDelay mContentDiscoveryRetry;
  Json::Value mSerializedState;
  AutoUpdateMode mAutoUpdateMode;
  std::unique_ptr<ContentDiscovery> mContentDiscovery;
  std::vector<std::shared_ptr<ContentTracker>> mContentTrackers;
  std::vector<ContentAcquisition::DownloadCallback> mDownloadCallbacks;
  std::function<void __cdecl(std::string const &,DurableDocument const &)> mUpdateFoundCallback;
  std::vector<ContentAcquisition::PackImportCallbackInfo> mPackImportCallbacks;
  std::unordered_map<DlcId,ContentAcquisition::DownloadHistory> mDownloadHistory;
  std::unordered_map<std::string,DlcId> mCachedProductIdLookup;
  std::shared_ptr<TaskGroup> mIOTaskGroup;
};

```

### `ContentAcquisition_vtbl`
```
struct /*VFT*/ ContentAcquisition_vtbl
{
  void (__fastcall *~IContentEventListener)(IContentEventListener *this);
  void (__fastcall *onDownloadEvent)(IContentEventListener *this, ContentEventType, InitiatorCategory, const DlcId *, const std::string *, const std::vector<PackIdVersion> *, unsigned __int64, long double, bool);
  void (__fastcall *onImportEvent)(IContentEventListener *this, ContentEventType, InitiatorCategory, const DlcId *, const std::string *, const std::vector<PackIdVersion> *, bool, bool);
  void (__fastcall *onPackImportEvent)(IContentEventListener *this, const std::string *, const PackManifest *, bool);
};

```

### `ComponentDescription_vtbl`
```
struct /*VFT*/ ComponentDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>
{
  Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<ActiveDirectoryIdentityObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<ActiveDirectoryIdentityObserver *>> mObservers;
};

```

### `Core::Observer<I18nObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<I18nObserver,Core::SingleThreadedLock>
{
  Core::Observer<I18nObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<I18nObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<I18nObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<I18nObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<I18nObserver,Core::SingleThreadedLock>)(Core::Observer<I18nObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<I18nObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::DeferredTask`
```
struct __cppobj __declspec(align(8)) Core::DeferredTask
{
  std::atomic<enum Core::DeferredTask::State> mState;
  std::condition_variable mCondition;
  std::mutex mExecutionMutex;
  std::function<void __cdecl(void)> mCallback;
  const bool mCanSkipExecution;
};

```

### `cg::details::LambdaExecutorContextContainer<dragon::rendering::RenderContext,0>`
```
struct __cppobj cg::details::LambdaExecutorContextContainer<dragon::rendering::RenderContext,0>
{
  dragon::rendering::RenderContext mContext;
};

```

### `cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>`
```
struct __cppobj cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>
{
  std::unique_ptr<Bedrock::Threading::Burst::WorkQueue<std::function<void __cdecl(dragon::rendering::RenderContext &)>,Bedrock::Threading::Burst::Strategy::Console,Bedrock::Threading::Burst::Strategy::Execution::GreedyExecution>> mWorkQueue;
  dragon::rendering::RenderContext *mContext;
};

```

### `cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>`
```
struct __cppobj cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>
{
  cg::details::LambdaExecutorContextContainer<dragon::rendering::RenderContext,0> mContextContainer;
  dragon::rendering::RenderContext *mContext;
  cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1> mExecutionPolicy;
};

```

### `cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> >`
```
struct __cppobj __declspec(align(8)) cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> >
{
  std::unique_ptr<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>> mExecutionContext;
  std::atomic<int> mPendingWorkCount;
};

```

### `cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >`
```
struct __cppobj cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >
{
  cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > mScheduler;
};

```

### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource> >`
```
struct __cppobj Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource> >
{
  std::shared_mutex mAccess;
  std::unordered_map<unsigned __int64,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::VertexBufferType>::BufferResource>> mContent;
};

```

### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource> >`
```
struct __cppobj Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource> >
{
  std::shared_mutex mAccess;
  std::unordered_map<unsigned __int64,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::mesh::IndexBufferType>::BufferResource>> mContent;
};

```

### `Core::CpuRingBufferAllocation_Buffer::Buffer`
```
struct __cppobj Core::CpuRingBufferAllocation_Buffer::Buffer
{
  std::vector<unsigned char> mBuffer;
};

```

### `Core::CpuRingBufferAllocation_Buffer`
```
struct __cppobj Core::CpuRingBufferAllocation_Buffer
{
};

```

### `Core::CheckedRingBuffer<2,0>`
```
struct __cppobj Core::CheckedRingBuffer<2,0>
{
  FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0> *mBuffer;
  unsigned __int64 mFence;
};

```

### `Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >`
```
struct __cppobj Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >
{
  Core::CheckedRingBuffer<2,0> *mBufferInstance;
};

```

### `Core::SharedMemoryTracker`
```
struct __cppobj Core::SharedMemoryTracker
{
  MPMCQueue<std::shared_ptr<Core::SharedMemoryTracker::SharedMemoryTrackerBase> > mTrackedMemory;
};

```

### `Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope`
```
struct __cppobj Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >::AllocationScope
{
  std::function<void __cdecl(void)> mFinalizer;
  Core::CpuRingBufferAllocator<unsigned char,2,0,Core::CheckedRingBuffer<2,0> > mAllocator;
  FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0> *mRing;
  Core::CheckedRingBuffer<2,0> mCheckedRing;
  const unsigned __int64 mFence;
};

```

### `Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >`
```
struct __cppobj Core::RingAllocatorContainer<unsigned char,2,0,Core::CheckedRingBuffer<2,0> >
{
  unsigned __int64 mCurrentFence;
  std::atomic<unsigned __int64> mLastCompletedFence;
  std::atomic<bool> mHasLastCompletedFence;
  std::shared_ptr<Core::CpuRingBufferAllocation_Buffer> mBuffer;
  FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0> mRing;
};

```

### `cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>`
```
struct __cppobj cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>
{
};

```

### `cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0>`
```
struct __cppobj cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0> : cg::details::ScopedFrameBase<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution>
{
  cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > > *mDispatcher;
};

```

### `cg::details::SpecializedScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,void>`
```
struct __cppobj cg::details::SpecializedScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,void> : cg::details::ScopedFrame<cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution,0>
{
};

```

### `cg::ResourceManager<std::unique_ptr<dragon::materials::CompiledMaterialDefinition>,std::string,void,std::unique_ptr<dragon::materials::CompiledMaterialDefinition> *,std::unordered_map>`
```
struct __cppobj cg::ResourceManager<std::unique_ptr<dragon::materials::CompiledMaterialDefinition>,std::string,void,std::unique_ptr<dragon::materials::CompiledMaterialDefinition> *,std::unordered_map>
{
  std::unordered_map<std::string,std::unique_ptr<dragon::materials::CompiledMaterialDefinition>> mContainer;
};

```

### `cg::ResourceManager<std::unique_ptr<dragon::materials::Material>,dragon::materials::MaterialLocation,void,std::unique_ptr<dragon::materials::Material> *,std::unordered_map>`
```
struct __cppobj cg::ResourceManager<std::unique_ptr<dragon::materials::Material>,dragon::materials::MaterialLocation,void,std::unique_ptr<dragon::materials::Material> *,std::unordered_map>
{
  std::unordered_map<dragon::materials::MaterialLocation,std::unique_ptr<dragon::materials::Material>> mContainer;
};

```

### `Core::IFileSystem`
```
struct __cppobj Core::IFileSystem
{
  Core::IFileSystem_vtbl *__vftable /*VFT*/;
};

```

### `Core::IFile`
```
struct __cppobj Core::IFile
{
  Core::IFile_vtbl *__vftable /*VFT*/;
};

```

### `Core::IFile_vtbl`
```
struct /*VFT*/ Core::IFile_vtbl
{
  void (__fastcall *~IFile)(Core::IFile *this);
  Core::Result *(__fastcall *readExactly)(Core::IFile *this, Core::Result *result, void *, unsigned __int64);
  Core::Result *(__fastcall *readAtPosition)(Core::IFile *this, Core::Result *result, unsigned __int64, void *, unsigned __int64, unsigned __int64 *);
  Core::Result *(__fastcall *getSize)(Core::IFile *this, Core::Result *result, unsigned __int64 *);
};

```

### `Core::IFileSystem_vtbl`
```
struct /*VFT*/ Core::IFileSystem_vtbl
{
  void (__fastcall *~IFileSystem)(Core::IFileSystem *this);
  std::unique_ptr<Core::IFile> *(__fastcall *openFile)(Core::IFileSystem *this, std::unique_ptr<Core::IFile> *result, Core::Path, Core::FileOpenMode, Core::FileBufferingMode);
  bool (__fastcall *fileExists)(Core::IFileSystem *this, Core::Path);
  Core::Result *(__fastcall *iterateOverDirectory)(Core::IFileSystem *this, Core::Result *result, Core::Path, Core::DirectoryIterationFlags, std::function<Core::Result __cdecl(Core::DirectoryIterationItem const &)>);
  Core::Result *(__fastcall *getDirectoryFiles)(Core::IFileSystem *this, Core::Result *result, std::vector<Core::PathBuffer<std::string >> *, Core::Path);
};

```

### `ContentLog::ThreadSpecificData::ScopeData`
```
struct __cppobj ContentLog::ThreadSpecificData::ScopeData
{
  std::string mMessage;
  gsl::not_null<ContentLog::ContentLogScope const *> mContentLogScope;
};

```

### `ContextMessageLogger_vtbl`
```
struct /*VFT*/ ContextMessageLogger_vtbl
{
  void (__fastcall *~ContextMessageLogger)(ContextMessageLogger *this);
};

```

### `ContextMessage`
```
struct __cppobj ContextMessage
{
  LogArea mArea;
  LogLevel mLevel;
  std::string mMessage;
};

```

### `ContentLog::ThreadSpecificData`
```
struct __cppobj ContentLog::ThreadSpecificData
{
  std::vector<ContentLog::ThreadSpecificData::ScopeData> mScope;
  std::vector<ContextMessageLogger *> mMessageLoggers;
};

```

### `ContentLog::ScopeHandler`
```
struct __cppobj ContentLog::ScopeHandler : std::enable_shared_from_this<ContentLog::ScopeHandler>
{
  Bedrock::Threading::InstancedThreadLocal<ContentLog::ThreadSpecificData,std::allocator<ContentLog::ThreadSpecificData> > mThreadSpecificData;
};

```

### `ContentLog`
```
struct __cppobj ContentLog : Bedrock::EnableNonOwnerReferences, DisableServiceLocatorOverride
{
  bool mEnabled;
  std::map<typeid_t<ContentLog>,ContentLog::ContentLogEndPointData,std::less<typeid_t<ContentLog> >,std::allocator<std::pair<typeid_t<ContentLog> const ,ContentLog::ContentLogEndPointData> > > mEndPoints;
  std::mutex mEndpointMutex;
  std::shared_ptr<ContentLog::ScopeHandler> mScopeHandler;
};

```

### `ContentLogFileEndPoint`
```
struct __cppobj __declspec(align(4)) ContentLogFileEndPoint : ContentLogEndPoint
{
  std::unique_ptr<Core::OutputFileStream> mFileStream;
  Core::PathBuffer<std::string > mDebugLogDirectory;
  Core::PathBuffer<std::string > mFilePath;
  unsigned int mNumTimesOpened;
  bool mIsEnabled;
};

```

### `ContentLogFileEndPoint_vtbl`
```
struct /*VFT*/ ContentLogFileEndPoint_vtbl
{
  void (__fastcall *~LogEndPoint)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(Bedrock::LogEndPoint *this, const char *);
  void (__fastcall *flush)(Bedrock::LogEndPoint *this);
  void (__fastcall *setEnabled)(Bedrock::LogEndPoint *this, bool);
  bool (__fastcall *isEnabled)(Bedrock::LogEndPoint *this);
  void (__fastcall *log)(ContentLogEndPoint *this, const LogArea, const LogLevel, const char *);
};

```

### `Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem`
```
struct __cppobj Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem
{
  Core::PathBuffer<std::string > mKey;
  std::shared_ptr<FMOD::Sound> mValue;
  unsigned __int64 mSizeInBytes;
};

```

### `Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >`
```
struct __cppobj Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >
{
  std::shared_mutex mAccess;
  std::atomic<unsigned __int64> mCurrentSizeInBytes;
  const unsigned __int64 mCapacityInBytes;
  std::list<Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem,std::allocator<Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem> > mCacheList;
  std::unordered_map<Core::PathBuffer<std::string >,std::_List_iterator<std::_List_val<std::_List_simple_types<Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem> > >,std::hash<Core::PathBuffer<std::string > >,std::equal_to<Core::PathBuffer<std::string > >,std::allocator<std::pair<Core::PathBuffer<std::string > const ,std::_List_iterator<std::_List_val<std::_List_simple_types<Core::LRUCache<Core::PathBuffer<std::string >,FMOD::Sound,std::shared_ptr<FMOD::Sound> >::CacheItem> > > > > > mCacheMap;
};

```

### `CustomMusic::QueuedMusicItem`
```
struct __cppobj __declspec(align(8)) CustomMusic::QueuedMusicItem
{
  std::string mEventName;
  float mVolume;
  float mFadeoutSeconds;
  _BYTE mPlayMode[1];
};

```

### `CustomMusic`
```
struct __cppobj __declspec(align(8)) CustomMusic : Music
{
  _BYTE mCurrentPlayMode[1];
  std::queue<CustomMusic::QueuedMusicItem> mMusicQueue;
  bool _mIsActive;
};

```

### `CustomMusic_vtbl`
```
struct /*VFT*/ CustomMusic_vtbl
{
  void (__fastcall *~Music)(Music *this);
  bool (__fastcall *hasTracks)(Music *this);
  void (__fastcall *nextTrack)(Music *this);
  void (__fastcall *setActive)(Music *this, bool);
};

```

### `ClientAssetCacheController::UnloadCallback`
```
struct __cppobj __declspec(align(8)) ClientAssetCacheController::UnloadCallback
{
  std::function<void __cdecl(void)> mCallback;
  bool mResourceCached;
};

```

### `ClientAssetCacheController`
```
struct __cppobj ClientAssetCacheController
{
  bool mIsInGame;
  bool mCacheInvalid;
  std::vector<std::string> mPackIds;
  std::map<enum AssetCacheCategory,ClientAssetCacheController::UnloadCallback> mUnloadCallbacks;
};

```

### `ClubsService`
```
struct __cppobj ClubsService : ServiceClient
{
  IMinecraftEventing *mMinecraftEventing;
};

```

### `ClubsService_vtbl`
```
struct /*VFT*/ ClubsService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `CubemapBackgroundResources`
```
struct __cppobj CubemapBackgroundResources
{
  std::array<mce::TexturePtr,6> mPanoramaImages;
  std::array<ResourceLocation,6> mPanormaResourceLocations;
  mce::ClientTexture mCubemapTexture;
  ResourceLocation mOverlayLocation;
  mce::TexturePtr mOverlayTexture;
  int mTextureRefCount;
  bool mPrimaryClientUnloaded;
  bool mPendingRecreateCubemap;
  mce::Color mFadeInColor;
};

```

### `ClientInstanceEventListener`
```
struct __cppobj ClientInstanceEventListener
{
  ClientInstanceEventListener_vtbl *__vftable /*VFT*/;
};

```

### `ClientInstance`
```
struct __cppobj ClientInstance : IClientInstance, Core::StorageAreaStateListener, GameCallbacks, PlayerListener, std::enable_shared_from_this<ClientInstance>
{
  ClientInstanceState mClientState;
  IMinecraftApp *mApp;
  LevelListener *mLevelListener;
  IMinecraftGame *mMinecraftGame;
  std::unique_ptr<Minecraft> mMinecraft;
  bool mIsFullVanillaPackOnStack;
  std::unique_ptr<LevelRenderer> mLevelRenderer;
  std::unique_ptr<LightTexture> mLightTexture;
  std::unique_ptr<LoopbackPacketSender> mPacketSender;
  std::unique_ptr<HolographicPlatform> mHoloInput;
  std::unique_ptr<VoiceSystem> mVoiceSystem;
  std::unique_ptr<MoveInputHandler> mClientMoveInputHandler;
  std::unique_ptr<ClientInputHandler> mClientInputHandler;
  std::unique_ptr<MinecraftKeyboardManager> mKeyboardManager;
  std::unique_ptr<HitDetectSystem> mHitDetectSystem;
  std::shared_ptr<UserAuthentication> mUserAuthentication;
  std::unique_ptr<SceneFactory> mSceneFactory;
  std::unique_ptr<CachedScenes> mCachesScenes;
  std::unique_ptr<CameraManager> mCameraManager;
  Actor *mCameraEntity;
  Actor *mCameraTargetEntity;
  LocalPlayer *mPlayer;
  ActorUniqueID mCameraTargetEntityId;
  std::unique_ptr<BuildActionIntention> mInProgressBai;
  int mLastBuildActionTick;
  float mHoloviewerScale;
  float mRealityModeFrameFactor;
  bool mRealityModeToggleTriggered;
  ClientPlayMode mPlayMode;
  bool mTickedLastFrame;
  std::atomic<bool> mOpenControllerDisconnectScreen;
  std::atomic<bool> mHandlingControllerDisconnect;
  std::atomic<bool> mConnectGamepadScreenActive;
  PlayScreenDefaultTab mDefaultPlayscreenTab;
  bool mIsInUpdate;
  bool mLivingRoomCredits;
  std::function<void __cdecl(void)> mCreditsCallback;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNoBlockBreakUntil;
  bool mNewDictationString;
  std::string mDictation;
  mce::ViewportInfo mViewportInfo;
  ClientInstance::ClientRenderResources mClientRenderResources;
  mce::Texture *mLevelTexture;
  mce::Camera mCamera;
  ShaderColor mShaderColor;
  ShaderColor mDarkShaderColor;
  Vec3 mLastPointerLocation;
  std::unique_ptr<SceneStack> mSceneStack;
  std::unique_ptr<hbui::Router> mUIRouter;
  std::unique_ptr<ContentCatalogService> mServerService;
  std::unique_ptr<UIProfanityContext> mUIProfanityContext;
  std::shared_ptr<TextToSpeechClient> mTextToSpeechClient;
  std::shared_ptr<TTSEventManager> mTTSEventManager;
  std::unique_ptr<TaskGroup> mTaskGroup;
  std::unique_ptr<BlockTessellator> mBlockTessellator;
  std::unique_ptr<BlockActorRenderDispatcher> mBlockEntityRenderDispatcher;
  std::unique_ptr<ActorRenderDispatcher> mEntityRenderDispatcher;
  std::unique_ptr<ActorBlockRenderer> mEntityBlockRenderer;
  std::unique_ptr<ItemInHandRenderer> mItemInHandRenderer;
  std::unique_ptr<ItemRenderer> mItemRenderer;
  std::unique_ptr<GuiData> mGuiData;
  std::unique_ptr<GuidedFlowManager> mGuidedFlowManager;
  std::unique_ptr<MobEffectsLayout> mMobEffectsLayout;
  std::unique_ptr<ToastManager> mToastManager;
  const unsigned __int8 mClientSubId;
  std::unique_ptr<SkinRepositoryClientInterface> mSkinRepositoryClientInterface;
  std::shared_ptr<persona::PersonaPieceCollectionModel> mPersonaPieceCollectionModel;
  ClientHMDState mHMDState;
  bool mIsSceneStackChanging;
  std::unique_ptr<FogDefinitionRegistry> mFogDefinitionRegistry;
  std::unique_ptr<FogManager> mFogManager;
  bool mHasSwitchedScreen;
  bool mShouldLeaveGame;
  bool mPreparingToLeaveGame;
  bool mIsLeavingGame;
  bool mSyncLeaveGame;
  bool mDestroyingGame;
  bool mShuttingDown;
  bool mUsingTripodNow;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mServerConnectionTime;
  unsigned int mServerPingTime;
  std::deque<std::string> mSentMessageHistory;
  std::deque<std::string> mDevConsoleMessageHistory;
  std::function<void __cdecl(std::string const &,enum BehaviorStatus)> mBehaviorCommandStatusCallback;
  std::unique_ptr<UIEventCoordinator> mUIEventCoordinator;
  std::unique_ptr<ClientHitDetectCoordinator> mHitEventCoordinator;
  std::unordered_map<std::string,int> mProfanityExactMap;
  std::unordered_set<std::string> mProfanityContainsSet;
  std::unique_ptr<EducationOptions> mEducationOptions;
  glm::tvec2<float,0> mPrevCursorPos;
  glm::tvec2<float,0> mCurrentCursorPos;
  float mCursorPosAlpha;
  LatencyGraphDisplay *mLatencyGraphDisplay;
  std::unique_ptr<GameModuleClient> mGameModule;
  gsl::not_null<Bedrock::NonOwnerPointer<ClientInstanceEventCoordinator> > mEventCoordinator;
  std::unique_ptr<MinecraftClientScriptEngine> mScriptEngine;
  int mGameControllerId;
  bool mHideSnakeGUI;
  bool mHookMouse;
  bool mResponse;
  Actor *mHovered;
  std::vector<std::string> mAddOnList;
  int mSendCreateUiFinished;
  bool mLoadFinished;
  bool mHudScreenFinish;
  std::unique_ptr<hbui::SceneProvider> mSceneProvider;
  hbui::Telemetry mHBUITelemetry;
  std::shared_ptr<ClientRequirementVerifier> mClientRequirementVerifier;
};

```

### `ClientInputHandler`
```
struct __cppobj ClientInputHandler
{
  IClientInstance *mClient;
  InputHandler *mInputHandler;
  std::unique_ptr<ClientBindingFactory> mBindingFactory;
  std::unique_ptr<ClientInputMappingFactory> mMappingFactory;
  std::string mLastGameMode;
  std::string mLastHoloUIMode;
  bool mIsFlying;
  bool mIsSneaking;
  bool mIsSwimming;
  bool mIsInWater;
  bool mIsInScaffolding;
  bool mIsOnScaffolding;
  bool mIsCreativeMode;
  bool mInteractActive;
  bool mHasMobEffects;
  bool mShowJumpButton;
  bool mShowSneakButton;
  std::unique_ptr<ClientInputHandlerProxy> mProxy;
};

```

### `ClientBindingFactory_vtbl`
```
struct /*VFT*/ ClientBindingFactory_vtbl
{
  void (__fastcall *~BindingFactory)(BindingFactory *this);
  std::function<bool __cdecl(void)> *(__fastcall *getBooleanBinding)(BindingFactory *this, std::function<bool __cdecl(void)> *result, const std::string *);
  std::function<std::string __cdecl(void)> *(__fastcall *getStringBinding)(BindingFactory *this, std::function<std::string __cdecl(void)> *result, const std::string *);
  std::function<glm::tvec2<float,0> __cdecl(void)> *(__fastcall *getPointBinding)(BindingFactory *this, std::function<glm::tvec2<float,0> __cdecl(void)> *result, const std::string *);
  std::function<RectangleArea __cdecl(void)> *(__fastcall *getAreaBinding)(BindingFactory *this, std::function<RectangleArea __cdecl(void)> *result, const std::string *);
};

```

### `ChordButtonMapping`
```
struct __cppobj ChordButtonMapping
{
  std::string generatedButtonName;
  std::vector<std::string> sourceButtonNames;
};

```

### `ClientInputMappingFactory`
```
struct __cppobj ClientInputMappingFactory : InputMappingFactory
{
  std::unordered_map<std::string,InputMapping> mActiveInputMappings;
  std::unordered_map<std::string,InputMapping> mInputMappingTemplates;
  bool mInvertYAxis;
  bool mSwapGamepadButtonsXY;
  bool mSwapGamepadButtonsAB;
  float mSensitivity;
  GamePadRemappingLayout mGameControllerRemappingLayout;
  GamePadRemappingLayout mMotionControllerRemappingLayout;
  std::weak_ptr<KeyboardRemappingLayout> mKeyboardRemappingLayout;
};

```

### `ClientInputMappingFactory_vtbl`
```
struct /*VFT*/ ClientInputMappingFactory_vtbl
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

### `ClientInputHandlerProxyCallbacks`
```
const struct __cppobj ClientInputHandlerProxyCallbacks
{
  std::function<unsigned int __cdecl(std::string const &)> mGetNameId;
};

```

### `ClientInputHandlerProxy`
```
struct __cppobj ClientInputHandlerProxy
{
  const ClientInputHandlerProxyCallbacks mCallbacks;
};

```

### `ClientHitDetectListener`
```
struct __cppobj ClientHitDetectListener
{
  ClientHitDetectListener_vtbl *__vftable /*VFT*/;
};

```

### `ClientHitDetectListener_vtbl`
```
struct /*VFT*/ ClientHitDetectListener_vtbl
{
  void (__fastcall *~ClientHitDetectListener)(ClientHitDetectListener *this);
  EventResult (__fastcall *onChangedHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onContinuousHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onChangedPickHitResult)(ClientHitDetectListener *this, HitResult *);
  EventResult (__fastcall *onContinuousPickHitResult)(ClientHitDetectListener *this, HitResult *);
};

```

### `ClientHitDetectCoordinator`
```
struct __cppobj ClientHitDetectCoordinator : EventCoordinator<ClientHitDetectListener>
{
};

```

### `CameraLoader`
```
struct __cppobj CameraLoader
{
  CameraLoader_vtbl *__vftable /*VFT*/;
  std::vector<std::unique_ptr<CameraBehaviorLoader>> mRegisteredBehaviorLoaders;
  std::unordered_map<HashedString,std::unique_ptr<ActivationRule>> mRegisteredActivationRules;
};

```

### `CameraLoader_vtbl`
```
struct /*VFT*/ CameraLoader_vtbl
{
  void (__fastcall *~CameraLoader)(CameraLoader *this);
  void (__fastcall *setupFallbackCamera)(CameraLoader *this, CameraDirector *);
};

```

### `CameraBehaviorLoader`
```
struct __cppobj CameraBehaviorLoader
{
  CameraBehaviorLoader_vtbl *__vftable /*VFT*/;
  HashedString mId;
  std::string mName;
};

```

### `CameraBehaviorLoader_vtbl`
```
struct /*VFT*/ CameraBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `CameraPairHasher`
```
struct __cppobj CameraPairHasher
{
};

```

### `CameraBlend`
```
struct __cppobj __declspec(align(8)) CameraBlend
{
  HashedString mCameraFromId;
  HashedString mCameraToId;
  float mPercentage;
  float mFieldOfViewOffset;
  Vec3 mPositionOffset;
  glm::tquat<float,0> mRotationOffset;
};

```

### `CameraManager`
```
struct __cppobj __declspec(align(4)) CameraManager
{
  bool mIsDebugCameraActive;
  bool mIsDebugCameraControlActive;
  float mPreviousUpdateTime;
  std::unique_ptr<CameraLoader> mCameraLoader;
  std::unordered_map<HashedString,CameraDirector> mAvailableCameras;
  std::unordered_map<std::pair<HashedString,HashedString>,CameraBlendSettings,CameraPairHasher,std::equal_to<std::pair<HashedString,HashedString> >,std::allocator<std::pair<std::pair<HashedString,HashedString> const ,CameraBlendSettings> > > mCameraBlends;
  CameraDirector mFallbackCamera;
  HashedString mOverrideCamera;
  HashedString mForceActivateCamera;
  CameraBlend mCameraBlend;
  Camera mCamera;
  bool mDebugRenderFlagActiveCamera;
  bool mDebugRenderFlagAvoidance;
  bool mDebugRenderFlagFraming;
  bool mDebugRenderFlagSpline;
  bool mDebugRenderFlagAll;
  bool mIsBindingEntity;
};

```

### `ClientInstance::ClientRenderResources`
```
struct __cppobj ClientInstance::ClientRenderResources
{
  mce::Texture *mUITexture;
  mce::TexturePtr mUICursorTexture;
};

```

### `ChestBlockActor`
```
struct __cppobj __declspec(align(8)) ChestBlockActor : RandomizableBlockActorFillingContainer
{
  float mSpeed;
  bool mIsGlobalChest;
  bool mUsesLegacyBlockDetection;
  float mObstructionHeight;
  __int8 mPairLead : 1;
  float mOpenness;
  float mOldOpenness;
  bool mIsOpen;
  int mTickInterval;
  __int8 mPairingChanged : 1;
  __int8 mAlongX : 1;
  __int8 mDeferredPairLoad : 1;
  __int8 mConverted : 1;
  int mDeferredPairX;
  int mDeferredPairZ;
  ChestBlockActor *mLargeChestPaired;
  BlockPos mLargeChestPairedPosition;
  bool mIsTrappedChest;
  bool mIsFindable;
  std::unordered_set<ActorUniqueID> mOpenedByIds;
  bool mNotifyPlayersOnChange;
};

```

### `ConduitBlockActor`
```
struct __cppobj ConduitBlockActor : BlockActor
{
  bool mIsActive;
  bool mIsHunting;
  int mBlockRefreshCounter;
  unsigned __int64 mNextAmbientSound;
  float mAnimationValue;
  float mRotation;
  int mRotationTickCount;
  int mWindLevel;
  int mEffectRange;
  ActorUniqueID mTarget;
  std::vector<BlockPos> mBlockPositions;
};

```

### `ClientHMDState::VRRotationResetState`
```
struct __cppobj ClientHMDState::VRRotationResetState
{
  bool mPendingReset;
  bool mForceNextReset;
};

```

### `ClientHMDState`
```
struct __cppobj __declspec(align(8)) ClientHMDState
{
  ClientInstance *mClientInstance;
  HoloHudDriftDynamics mHoloHudDriftDynamics;
  mce::RenderStage *mUIStage;
  mce::RenderStage *mLevelStage;
  mce::Texture *mLevelTexture;
  mce::Texture *mUITexture;
  std::shared_ptr<mce::Texture> mUILayersTexture;
  float mHoloScreenCursorXCoordNorm;
  float mHoloScreenCursorYCoordNorm;
  Matrix mLastLevelViewMatrix;
  Matrix mLastLevelViewMatrixAbsolute;
  Matrix mLastLevelProjMatrix;
  Matrix mLastLevelWorldMatrix;
  Matrix mHUDMatrixPatch;
  Matrix mVRTransitionMatrixPatch;
  float mLastLevelViewMatrixVerticalShift;
  float mLastVRPitchAngle;
  float mVRRotationAdjustment;
  float mVRRotAdjYawTweak;
  float mGazeCursorPitchBoostAngle;
  float mFadeScreenAlpha;
  float mDesiredFadeScreenAlpha;
  float mRealityFrameModeWorldScale;
  float mHeadSetDirForSleeping;
  __int16 mPointerX;
  __int16 mPointerY;
  bool mHoloCursorOn;
  bool mAppJustResumed;
  ClientHMDState::VRRotationResetState mVRRotationResetState;
  bool mHoloTransformsHaveBeenUpdated;
  HoloUIToPoseSource mLastHoloUIToPoseSource;
};

```

### `ClientRequirementVerifier`
```
struct __cppobj __declspec(align(8)) ClientRequirementVerifier : std::enable_shared_from_this<ClientRequirementVerifier>
{
  std::weak_ptr<FlightingService> mFlightingServiceExistenceTracker;
  bool mTreatmentsReady;
  std::vector<std::string> mTreatments;
  unsigned int mFlightingMonitorHandle;
};

```

### `ClientInstanceEventListener_vtbl`
```
struct /*VFT*/ ClientInstanceEventListener_vtbl
{
  void (__fastcall *~ClientInstanceEventListener)(ClientInstanceEventListener *this);
  EventResult (__fastcall *onClientInitializeStart)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onClientInitializeEnd)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onClientMinecraftInitialized)(ClientInstanceEventListener *this, ClientInstance *, Minecraft *);
  EventResult (__fastcall *onClientCreatedLevel)(ClientInstanceEventListener *this, ClientInstance *, Level *);
  EventResult (__fastcall *onClientUpdateStart)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onClientUpdateEnd)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onClientSuspend)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onClientEnteredWorld)(ClientInstanceEventListener *this, ClientInstance *);
  EventResult (__fastcall *onStartLeaveGame)(ClientInstanceEventListener *this, ClientInstance *);
};

```

### `ClientInstanceEventCoordinator`
```
struct __cppobj ClientInstanceEventCoordinator : EventCoordinator<ClientInstanceEventListener>
{
};

```

### `CompactionListenerEnv`
```
struct __cppobj CompactionListenerEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  std::mutex mLock;
  bool mCompactionRunning;
  std::function<void __cdecl(enum CompactionStatus)> mCompactionCallback;
};

```

### `CompactionListenerEnv_vtbl`
```
struct /*VFT*/ CompactionListenerEnv_vtbl
{
  void (__fastcall *~Env)(leveldb::Env *this);
  leveldb::Status *(__fastcall *NewSequentialFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::SequentialFile **);
  leveldb::Status *(__fastcall *NewRandomAccessFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::RandomAccessFile **);
  leveldb::Status *(__fastcall *NewWritableFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::WritableFile **);
  leveldb::Status *(__fastcall *NewAppendableFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::WritableFile **);
  bool (__fastcall *FileExists)(leveldb::Env *this, const std::string *);
  leveldb::Status *(__fastcall *GetChildren)(leveldb::Env *this, leveldb::Status *result, const std::string *, std::vector<std::string> *);
  leveldb::Status *(__fastcall *DeleteFileA)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *CreateDir)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *DeleteDir)(leveldb::Env *this, leveldb::Status *result, const std::string *);
  leveldb::Status *(__fastcall *GetFileSize)(leveldb::Env *this, leveldb::Status *result, const std::string *, unsigned __int64 *);
  leveldb::Status *(__fastcall *RenameFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, const std::string *);
  leveldb::Status *(__fastcall *LockFile)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::FileLock **);
  leveldb::Status *(__fastcall *UnlockFile)(leveldb::Env *this, leveldb::Status *result, leveldb::FileLock *);
  void (__fastcall *Schedule)(leveldb::Env *this, void (__fastcall *)(void *), void *);
  void (__fastcall *StartThread)(leveldb::Env *this, void (__fastcall *)(void *), void *);
  leveldb::Status *(__fastcall *GetTestDirectory)(leveldb::Env *this, leveldb::Status *result, std::string *);
  leveldb::Status *(__fastcall *NewLogger)(leveldb::Env *this, leveldb::Status *result, const std::string *, leveldb::Logger **);
  unsigned __int64 (__fastcall *NowMicros)(leveldb::Env *this);
  void (__fastcall *SleepForMicroseconds)(leveldb::Env *this, int);
};

```

### `ClientBlobCache::Cache`
```
struct __cppobj ClientBlobCache::Cache : AppPlatformListener
{
  std::shared_ptr<DBStorage> mDB;
  TaskGroup mTaskGroup;
  std::mutex mTimestampMutex;
  std::unordered_map<unsigned __int64,unsigned __int64> mTimestamps;
  unsigned __int64 mBaseTimestamp;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mCacheLoadingTime;
};

```

### `ClientBlobCache::Cache_vtbl`
```
struct /*VFT*/ ClientBlobCache::Cache_vtbl
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

### `Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>
{
  Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>_vtbl *__vftable /*VFT*/;
  Core::Subject<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> *mpSubject;
};

```

### `Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>_vtbl`
```
struct /*VFT*/ Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>_vtbl
{
  void (__fastcall *~Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>)(Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock> *this);
};

```

### `Core::Subject<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>`
```
struct __cppobj Core::Subject<EDUDiscovery::DiscoveryObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<gsl::not_null<EDUDiscovery::DiscoveryObserver *>> mObservers;
};

```

### `ChunkPerformanceData::AtomicTimeAccumulator`
```
struct __cppobj ChunkPerformanceData::AtomicTimeAccumulator
{
  unsigned __int64 mCount;
  std::chrono::duration<__int64,std::ratio<1,1000000000> > mTimeSum;
  std::mutex mTimeSumMutex;
};

```

### `ChunkPerformanceData::AtomicMemoryAccumulator`
```
struct __cppobj ChunkPerformanceData::AtomicMemoryAccumulator
{
  std::atomic<unsigned __int64> mCount;
  std::atomic<unsigned __int64> mMemorySum;
};

```

### `ChunkPerformanceData`
```
struct __cppobj ChunkPerformanceData : Bedrock::EnableNonOwnerReferences
{
  ChunkPerformanceData::AtomicTimeAccumulator mRenderChunkBuildPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mRenderChunkVisibilityPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mClientLevelChunkInitialLightingPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mServerLevelChunkLoadChunkPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mServerLevelChunkPostProcessingPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mServerLevelChunkCheckForReplacementDataPerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mServerLevelChunkInitialLightingPerformanceData;
  ChunkPerformanceData::AtomicMemoryAccumulator mRenderChunkMemorySizePerformanceData;
  ChunkPerformanceData::AtomicTimeAccumulator mBiomeDecorationSystemDecorateTimeData;
  ChunkPerformanceData::AtomicTimeAccumulator mScatterFeaturePlaceTimeData;
  std::atomic<unsigned __int64> mBiomeFeaturePlaceCallsCount;
};

```

### `ChunkBuildOrderPolicyBase`
```
struct __cppobj ChunkBuildOrderPolicyBase
{
  ChunkBuildOrderPolicyBase_vtbl *__vftable /*VFT*/;
};

```

### `ChunkBuildOrderPolicyBase_vtbl`
```
struct /*VFT*/ ChunkBuildOrderPolicyBase_vtbl
{
  void (__fastcall *~ChunkBuildOrderPolicyBase)(ChunkBuildOrderPolicyBase *this);
  int (__fastcall *getChunkRebuildPriority)(ChunkBuildOrderPolicyBase *this, const ChunkPos *);
  unsigned int (__fastcall *registerForUpdates)(ChunkBuildOrderPolicyBase *this);
  void (__fastcall *unregisterForUpdates)(ChunkBuildOrderPolicyBase *this, unsigned int);
  void (__fastcall *setBuildOrderInfluence)(ChunkBuildOrderPolicyBase *this, unsigned int, const ChunkPos *, const Vec3 *);
  void (__fastcall *updateInfluences)(ChunkBuildOrderPolicyBase *this);
};

```

### `CircuitSceneGraph`
```
struct __cppobj CircuitSceneGraph
{
  std::unordered_map<BlockPos,std::unique_ptr<BaseCircuitComponent>> mAllComponents;
  CircuitComponentList mActiveComponents;
  std::unordered_map<BlockPos,CircuitComponentList> mActiveComponentsPerChunk;
  std::unordered_map<BlockPos,CircuitComponentList> mPowerAssociationMap;
  std::unordered_map<BlockPos,CircuitSceneGraph::PendingEntry> mPendingAdds;
  std::unordered_map<BlockPos,CircuitSceneGraph::PendingEntry> mPendingUpdates;
  std::unordered_map<BlockPos,std::vector<BlockPos>> mComponentsToReEvaluate;
  std::vector<CircuitSceneGraph::PendingEntry> mPendingRemoves;
};

```

### `CircuitSystem`
```
struct __cppobj __declspec(align(8)) CircuitSystem
{
  bool mLockGraph;
  CircuitSceneGraph mSceneGraph;
  std::vector<CircuitSystem::LevelChunkTracking> mAddedLevelChunk;
  bool mHasBeenEvaluated;
};

```

### `CircuitSystem::LevelChunkTracking`
```
struct __cppobj CircuitSystem::LevelChunkTracking
{
  BlockPos mChunkPos;
};

```

### `ChunkLoadActionList`
```
struct __cppobj __declspec(align(8)) ChunkLoadActionList
{
  std::vector<ChunkLoadedRequest> mChunkLoadedRequests;
  std::vector<ChunkLoadedRequest> mChunkLoadedRequestsWaitForTicking;
  unsigned int mRequestSaveCounter;
};

```

### `CommandOrigin_vtbl`
```
struct /*VFT*/ CommandOrigin_vtbl
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

### `CommandRegistry::Enum`
```
struct __cppobj CommandRegistry::Enum
{
  std::string name;
  typeid_t<CommandRegistry> type;
  bool (__fastcall *parse)(CommandRegistry *this, void *, const CommandRegistry::ParseToken *, const CommandOrigin *, int, std::string *, std::vector<std::string> *);
  std::vector<std::pair<unsigned __int64,unsigned __int64>> values;
};

```

### `CommandRegistry::Factorization`
```
struct __cppobj CommandRegistry::Factorization
{
  CommandRegistry::Symbol commandSymbol;
};

```

### `CommandRegistry::Overload`
```
struct __cppobj __declspec(align(8)) CommandRegistry::Overload
{
  CommandVersion version;
  std::unique_ptr<Command> *(__fastcall *alloc)(std::unique_ptr<Command> *result);
  std::vector<CommandParameterData> params;
  int versionOffset;
};

```

### `CommandRegistry::ConstrainedValue`
```
struct __cppobj CommandRegistry::ConstrainedValue
{
  CommandRegistry::Symbol mValue;
  CommandRegistry::Symbol mEnum;
  std::vector<unsigned char> mConstraints;
};

```

### `CommandRegistry::SoftEnum`
```
struct __cppobj CommandRegistry::SoftEnum
{
  std::string mName;
  std::vector<std::string> mValues;
};

```

### `CommandRegistry::ParamSymbols`
```
struct __cppobj CommandRegistry::ParamSymbols
{
  CommandRegistry::Symbol x;
  CommandRegistry::Symbol y;
  CommandRegistry::Symbol z;
  CommandRegistry::Symbol dx;
  CommandRegistry::Symbol dy;
  CommandRegistry::Symbol dz;
  CommandRegistry::Symbol r;
  CommandRegistry::Symbol rm;
  CommandRegistry::Symbol rx;
  CommandRegistry::Symbol rxm;
  CommandRegistry::Symbol ry;
  CommandRegistry::Symbol rym;
  CommandRegistry::Symbol l;
  CommandRegistry::Symbol lm;
  CommandRegistry::Symbol c;
  CommandRegistry::Symbol m;
  CommandRegistry::Symbol name;
  CommandRegistry::Symbol type;
  CommandRegistry::Symbol family;
  CommandRegistry::Symbol score;
  CommandRegistry::Symbol tag;
};

```

### `ChalkboardBlockActor`
```
struct __cppobj ChalkboardBlockActor : BlockActor
{
  std::string mText;
  std::string mTextObjectString;
  TextObjectRoot mTextObjectMessage;
  ChalkboardBlockActor::CachedMessageData mCachedMessage;
  BlockPos mBasePos;
  _BYTE mSize[1];
  bool mIsOnGround;
  bool mIsLocked;
  ActorUniqueID mOwner;
};

```

### `CameraCallbacks`
```
struct __cppobj CameraCallbacks
{
  CameraCallbacks_vtbl *__vftable /*VFT*/;
};

```

### `CameraCallbacks_vtbl`
```
struct /*VFT*/ CameraCallbacks_vtbl
{
  void (__fastcall *onTakePictureNow)(CameraCallbacks *this, Player *, Actor *, Actor *);
  void (__fastcall *onStartTakingPicture)(CameraCallbacks *this, Player *);
  void (__fastcall *onEndTakingPicture)(CameraCallbacks *this, Player *, Actor *, Actor *);
  void (__fastcall *~CameraCallbacks)(CameraCallbacks *this);
};

```

### `ComponentItem`
```
struct __cppobj ComponentItem : Item
{
  std::unique_ptr<std::unordered_map<std::string,DefinitionEvent>> mEventHandlers;
  __int8 mExcludeUserDataDiffCheck : 1;
  __int8 mCanDestroyInCreative : 1;
  __int8 mRequiresInteract : 1;
  __int8 mIsLiquidClipped : 1;
  int mLevel;
  int mUses;
  float mSpeed;
  int mDamage;
  _BYTE mEnchantSlot[4];
  int mEnchantValue;
  std::vector<std::string> mAlias;
  Json::Value mOffsetList;
  std::map<HashedString,std::shared_ptr<ItemComponent>> mItemComponents;
  std::map<std::string,std::shared_ptr<ItemComponent>> mRegisteredCerealComponents;
};

```

### `CameraItemComponentLegacy_vtbl`
```
struct /*VFT*/ CameraItemComponentLegacy_vtbl
{
  void (__fastcall *~ICameraItemComponent)(ICameraItemComponent *this);
  float (__fastcall *blackBarsDuration)(ICameraItemComponent *this);
  float (__fastcall *blackBarsScreenRatio)(ICameraItemComponent *this);
  float (__fastcall *shutterScreenRatio)(ICameraItemComponent *this);
  float (__fastcall *shutterDuration)(ICameraItemComponent *this);
  float (__fastcall *pictureDuration)(ICameraItemComponent *this);
  float (__fastcall *slideAwayDuration)(ICameraItemComponent *this);
  bool (__fastcall *canPlace)(ICameraItemComponent *this, const ItemStack *, Actor *, const BlockPos *, unsigned __int8);
  void (__fastcall *takePictureNow)(ICameraItemComponent *this, Player *, Actor *, Actor *);
  void (__fastcall *registerCallbacks)(ICameraItemComponent *this, CameraCallbacks *);
  void (__fastcall *use)(ICameraItemComponent *this, ItemStack *, Player *);
  void (__fastcall *releaseUsing)(ICameraItemComponent *this, ItemStack *, Player *, int);
  bool (__fastcall *useOn)(ICameraItemComponent *this, ItemStack *, Actor *, const BlockPos *, unsigned __int8, const Vec3 *);
};

```

### `Control`
```
struct __cppobj Control
{
  Control_vtbl *__vftable /*VFT*/;
};

```

### `Control_vtbl`
```
struct /*VFT*/ Control_vtbl
{
  void (__fastcall *~Control)(Control *this);
};

```

### `ContainerManagerModel`
```
struct __cppobj ContainerManagerModel : IContainerManager
{
  Player *mPlayer;
  std::vector<ItemStack> mLastSlots;
  ContainerID mContainerId;
  ContainerType mContainerType;
  std::function<void __cdecl(ContainerManagerModel &)> mInformControllerOfDestructionCallback;
  std::unordered_map<std::string,std::shared_ptr<ContainerModel>> mContainers;
};

```

### `ContainerModel`
```
struct __cppobj ContainerModel : ContainerContentChangeListener
{
  const bool mIsClientSide;
  std::string mContainerStringName;
  const ContainerEnumName mContainerEnumName;
  std::vector<std::function<void __cdecl(int,ItemStack const &,ItemStack const &)>> mOnContainerChangedCallbacks;
  std::function<void __cdecl(int,ItemStack const &,ItemStack const &)> mPlayerNotificationCallbacks;
  ContainerCategory mContainerCategory;
  std::vector<SlotData> mItemSource;
  SparseContainer *mClientUIContainer;
  std::vector<ItemStack> mItems;
};

```

### `ContainerEnumNameHasher`
```
struct __cppobj ContainerEnumNameHasher
{
};

```

### `ContainerModel_vtbl`
```
struct /*VFT*/ ContainerModel_vtbl
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

### `ContainerManagerModel_vtbl`
```
struct /*VFT*/ ContainerManagerModel_vtbl
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

### `Core::Cache<unsigned short,Block const *,Block const *>`
```
struct __cppobj Core::Cache<unsigned short,Block const *,Block const *>
{
  std::shared_mutex mAccess;
  std::unordered_map<unsigned short,Block const *> mContent;
};

```

### `ContextAccessor::TypeBase`
```
struct __cppobj ContextAccessor::TypeBase
{
  ContextAccessor::TypeBase_vtbl *__vftable /*VFT*/;
};

```

### `ContextAccessor::TypeBase_vtbl`
```
struct /*VFT*/ ContextAccessor::TypeBase_vtbl
{
  void (__fastcall *~TypeBase)(ContextAccessor::TypeBase *this);
};

```

### `CustomEntityTypeDescription`
```
struct __cppobj CustomEntityTypeDescription : ComponentDescription
{
  std::string mCustomEntityType;
};

```

### `CustomEntityTypeDescription_vtbl`
```
struct /*VFT*/ CustomEntityTypeDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `CommandBlockDescription`
```
struct __cppobj __declspec(align(8)) CommandBlockDescription : ComponentDescription
{
  int mCurrentTickCount;
  int mTicksPerCommand;
  bool mTicking;
};

```

### `CommandBlockDescription_vtbl`
```
struct /*VFT*/ CommandBlockDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ContainerDescription_vtbl`
```
struct /*VFT*/ ContainerDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `ChangeDimensionRequest`
```
struct __cppobj ChangeDimensionRequest
{
  ChangeDimensionRequest::State mState;
  AutomaticID<Dimension,int> mFromDimensionId;
  AutomaticID<Dimension,int> mToDimensionId;
  Vec3 mPosition;
  bool mUsePortal;
  bool mRespawn;
  std::unique_ptr<CompoundTag> mAgentTag;
};

```

### `ClientPlayerEventCoordinator`
```
struct __cppobj ClientPlayerEventCoordinator : PlayerEventCoordinator
{
};

```

### `ClientLevelEventCoordinator`
```
struct __cppobj ClientLevelEventCoordinator : LevelEventCoordinator
{
};

```

### `ChunkSourceViewMgr`
```
struct __cppobj ChunkSourceViewMgr : LevelListener
{
  std::unordered_map<std::string,std::pair<__int64,std::unique_ptr<GridArea<std::shared_ptr<LevelChunk> >> >> mViewPtrs;
  std::unordered_map<std::string,std::unique_ptr<GridArea<std::shared_ptr<LevelChunk> >>> mPermanentViewPtrs;
};

```

### `Core::String`
```
struct __cppobj Core::String
{
};

```

### `Core::StringSpan`
```
struct __cppobj Core::StringSpan
{
  gsl::basic_string_span<char const ,-1> mStringSpan;
};

```

### `Core::Path::path_less`
```
struct __cppobj Core::Path::path_less
{
};

```

### `Core::PathContainerConversions<std::string >`
```
struct __cppobj Core::PathContainerConversions<std::string >
{
};

```

### `Core::StorageAreasTree::TreeChild`
```
struct __cppobj Core::StorageAreasTree::TreeChild
{
  HashedString mKey;
  std::unique_ptr<Core::StorageAreasTree::TreeNode> mNode;
};

```

### `Core::Observer<NetworkChangeObserver,std::mutex>`
```
struct __cppobj Core::Observer<NetworkChangeObserver,std::mutex>
{
  Core::Observer<NetworkChangeObserver,std::mutex>_vtbl *__vftable /*VFT*/;
  Core::Subject<NetworkChangeObserver,std::mutex> *mpSubject;
};

```

### `Core::Observer<NetworkChangeObserver,std::mutex>_vtbl`
```
struct /*VFT*/ Core::Observer<NetworkChangeObserver,std::mutex>_vtbl
{
  void (__fastcall *~Observer<NetworkChangeObserver,std::mutex>)(Core::Observer<NetworkChangeObserver,std::mutex> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<NetworkChangeObserver,std::mutex> *this);
};

```

### `Core::Subject<NetworkChangeObserver,std::mutex>`
```
struct __cppobj Core::Subject<NetworkChangeObserver,std::mutex>
{
  std::mutex mLock;
  std::vector<gsl::not_null<NetworkChangeObserver *>> mObservers;
};

```

### `Core::InputFileStream_vtbl`
```
struct /*VFT*/ Core::InputFileStream_vtbl
{
  void *(__fastcall *__vecDelDtor)(Core::InputFileStream *this, unsigned int);
};

```

### `cg::IGraphicsDevicePlatformProvider`
```
struct __cppobj cg::IGraphicsDevicePlatformProvider : Bedrock::EnableNonOwnerReferences
{
  cg::IGraphicsDevicePlatformProvider_vtbl *__vftable /*VFT*/;
};

```

### `cg::IGraphicsDevicePlatformProvider_vtbl`
```
struct /*VFT*/ cg::IGraphicsDevicePlatformProvider_vtbl
{
  void (__fastcall *~IGraphicsDevicePlatformProvider)(cg::IGraphicsDevicePlatformProvider *this);
  std::string *(__fastcall *getDriverVersion)(cg::IGraphicsDevicePlatformProvider *this, std::string *result);
  Json::Value *(__fastcall *getDeviceInfoJson)(cg::IGraphicsDevicePlatformProvider *this, Json::Value *result);
};

```

### `Core::LoadTimeData`
```
struct __cppobj Core::LoadTimeData
{
  const std::string mName;
  int mScope;
  long double mTotalTime;
};

```

### `Core::ScopedLoadTimeSection`
```
struct __cppobj Core::ScopedLoadTimeSection
{
  long double mStartTime;
  Core::LoadTimeData mProfileData;
};

```

### `Core::LoadTimeProfiler`
```
struct __cppobj __declspec(align(8)) Core::LoadTimeProfiler : Bedrock::EnableNonOwnerReferences
{
  std::vector<Core::ScopedLoadTimeSection *> mSections;
  unsigned int mCurrentFrame;
  std::vector<Core::LoadTimeData> mFinishedSections;
  Core::OutputFileStream mLogFile;
  bool mEnabled;
  bool mCloseLogOnUpdate;
};

```

### `ClientNetworkHandler`
```
struct __cppobj ClientNetworkHandler : NetEventCallback
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastBossRemoved;
  std::shared_ptr<ClientBlobCache::Cache> mBlobCache;
  IClientInstance *mClient;
  NetworkHandler *mNetworkHandler;
  PacketSender *mPacketSender;
  PrivateKeyManager *mClientKeys;
  MinecraftCommands *mMinecraftCommands;
  Level *mLevel;
  bool mHasMessage;
  bool mIsLoggedIn;
  std::shared_ptr<bool> mExistenceTracker;
  std::unordered_map<std::pair<Dimension const *,ChunkPos>,unsigned __int64,mce::Math::PairHash,std::equal_to<std::pair<Dimension const *,ChunkPos> >,std::allocator<std::pair<std::pair<Dimension const *,ChunkPos> const ,unsigned __int64> > > mPendingChunks;
  std::unordered_map<std::tuple<NetworkIdentifier,Dimension const *,ChunkPos>,std::function<void __cdecl(BlockSource &)>,mce::Math::Tuple3Hash,std::equal_to<std::tuple<NetworkIdentifier,Dimension const *,ChunkPos> >,std::allocator<std::pair<std::tuple<NetworkIdentifier,Dimension const *,ChunkPos> const ,std::function<void __cdecl(BlockSource &)> > > > mConnectionPausedCallbacks;
};

```

### `ClientInstance::<lambda_f6e4b0d87d4d949bdaea4c283d4c6cc0>`
```
struct __cppobj ClientInstance::<lambda_f6e4b0d87d4d949bdaea4c283d4c6cc0>
{
};

```

### `ClientInstance::<lambda_57e1ebedf9bd0f5ca98bc6185e1f58e3>`
```
struct __cppobj ClientInstance::<lambda_57e1ebedf9bd0f5ca98bc6185e1f58e3>
{
};

```

### `CommandSelectorResults<Actor>`
```
struct __cppobj CommandSelectorResults<Actor>
{
  std::shared_ptr<std::vector<Actor *> > mTargets;
};

```

### `CommandPosition`
```
struct __cppobj CommandPosition
{
  Vec3 mOffset;
  bool mRelativeX;
  bool mRelativeY;
  bool mRelativeZ;
  bool mLocal;
};

```

### `CommandSelectorBase`
```
struct __cppobj __declspec(align(4)) CommandSelectorBase
{
  int mVersion;
  CommandSelectionType mType;
  _BYTE mOrder[4];
  std::vector<InvertableFilter<std::string >> mNameFilters;
  std::vector<InvertableFilter<ActorDefinitionIdentifier>> mTypeFilters;
  std::vector<InvertableFilter<std::string >> mFamilyFilters;
  std::vector<InvertableFilter<std::string >> mTagFilters;
  std::vector<std::function<bool __cdecl(CommandOrigin const &,Actor const &)>> mFilterChain;
  CommandPosition mPosition;
  BlockPos mBoxDeltas;
  float mRadiusMin;
  float mRadiusMax;
  unsigned __int64 mCount;
  bool mIncludeDeadPlayers;
  bool mIsPositionBound;
  bool mDistanceFiltered;
  bool mHaveDeltas;
  bool mForcePlayer;
  bool mIsExplicitIdSelector;
};

```

### `CustomTabStorage`
```
struct __cppobj CustomTabStorage
{
  int index;
  std::string name;
  std::string path;
};

```

### `CameraBehavior<ComfortMoveBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<ComfortMoveBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<ComfortMoveBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<ComfortMoveBehavior>_vtbl
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

### `ComfortMoveBehavior`
```
struct __cppobj __declspec(align(8)) ComfortMoveBehavior : CameraBehavior<ComfortMoveBehavior>
{
  float mLinearYRemap;
  float mMaxLinearYRemap;
  float mStartYPos;
  float mAccumulatedDT;
  bool mYMotionUp;
};

```

### `ComfortMoveBehavior_vtbl`
```
struct /*VFT*/ ComfortMoveBehavior_vtbl
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

### `CameraBehavior<ShakeBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<ShakeBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<ShakeBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<ShakeBehavior>_vtbl
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

### `ComfortMoveBehaviorLoader`
```
struct __cppobj ComfortMoveBehaviorLoader : CameraBehaviorLoader
{
};

```

### `ComfortMoveBehaviorLoader_vtbl`
```
struct /*VFT*/ ComfortMoveBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `Clubs::FeedItem`
```
struct __cppobj __declspec(align(8)) Clubs::FeedItem
{
  _BYTE mFeedItemType[4];
  std::string mFeedItemRoot;
  std::string mFeedItemId;
  std::string mContent;
  std::string mAuthorXuid;
  std::string mDatePosted;
  std::string mCaption;
  int mNumComments;
  int mNumLikes;
  bool mHasLiked;
  bool mHasScreenshotLoaded;
};

```

### `Clubs::ActivityFeed`
```
struct __cppobj Clubs::ActivityFeed
{
  Clubs::ActivityFeed::Type mType;
  std::vector<Clubs::FeedItem> mFeedItems;
};

```

### `Clubs::ReportedItem`
```
struct __cppobj Clubs::ReportedItem
{
  Clubs::ReportedItem::Type mType;
  std::string mPathToItem;
  std::string mLastReported;
  int mReportCount;
  std::string mReportId;
  std::vector<std::pair<std::string,std::string >> mReports;
  Clubs::FeedItem mFeedItem;
};

```

### `Clubs::NewFeedItem`
```
struct __cppobj Clubs::NewFeedItem
{
  Clubs::NewFeedItem::Type mType;
  std::string mContent;
  std::string mScreenshotCaption;
};

```

### `ClientInputCallbacks`
```
struct __cppobj ClientInputCallbacks
{
};

```

### `ClientContentKeyProvider`
```
struct __cppobj ClientContentKeyProvider : IContentAccessibilityProvider
{
  IEntitlementManager *mEntitlementManager;
  std::unordered_map<ContentIdentity,std::string> mTempContentKeys;
};

```

### `ClientContentKeyProvider_vtbl`
```
struct /*VFT*/ ClientContentKeyProvider_vtbl
{
  void (__fastcall *~IContentKeyProvider)(IContentKeyProvider *this);
  std::string *(__fastcall *getContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  std::string *(__fastcall *getAlternateContentKey)(IContentKeyProvider *this, std::string *result, const ContentIdentity *);
  bool (__fastcall *requireEncryptedReads)(IContentKeyProvider *this);
  void (__fastcall *setTempContentKeys)(IContentKeyProvider *this, const std::unordered_map<ContentIdentity,std::string> *);
  void (__fastcall *clearTempContentKeys)(IContentKeyProvider *this);
  bool (__fastcall *canAccess)(IContentAccessibilityProvider *this, const ContentIdentity *);
};

```

### `CreateReviewParams`
```
struct __cppobj CreateReviewParams
{
  std::string mProductId;
  std::string mTitle;
  std::string mReviewText;
  int mRating;
  bool mIsInstalled;
  std::string mItemVersion;
};

```

### `Core::CallbackListeners<int,enum Social::SignInResult>`
```
struct __cppobj Core::CallbackListeners<int,enum Social::SignInResult>
{
  std::mutex mLock;
  std::vector<Core::CallbackListeners<int,enum Social::SignInResult>::Listener,std::allocator<Core::CallbackListeners<int,enum Social::SignInResult>::Listener> > mListeners;
};

```

### `CompileTime::Hash<38>`
```
struct __cppobj CompileTime::Hash<38>
{
};

```

### `CompileTime::Hash<37>`
```
struct __cppobj CompileTime::Hash<37>
{
};

```

### `CompileTime::Hash<36>`
```
struct __cppobj CompileTime::Hash<36>
{
};

```

### `CompileTime::Hash<35>`
```
struct __cppobj CompileTime::Hash<35>
{
};

```

### `CompileTime::Hash<34>`
```
struct __cppobj CompileTime::Hash<34>
{
};

```

### `CompileTime::Hash<33>`
```
struct __cppobj CompileTime::Hash<33>
{
};

```

### `CompileTime::Hash<32>`
```
struct __cppobj CompileTime::Hash<32>
{
};

```

### `CompileTime::Hash<31>`
```
struct __cppobj CompileTime::Hash<31>
{
};

```

### `CompileTime::Hash<30>`
```
struct __cppobj CompileTime::Hash<30>
{
};

```

### `CompileTime::Hash<29>`
```
struct __cppobj CompileTime::Hash<29>
{
};

```

### `CompileTime::Hash<28>`
```
struct __cppobj CompileTime::Hash<28>
{
};

```

### `CompileTime::Hash<27>`
```
struct __cppobj CompileTime::Hash<27>
{
};

```

### `CompileTime::Hash<26>`
```
struct __cppobj CompileTime::Hash<26>
{
};

```

### `CompileTime::Hash<25>`
```
struct __cppobj CompileTime::Hash<25>
{
};

```

### `CompileTime::Hash<24>`
```
struct __cppobj CompileTime::Hash<24>
{
};

```

### `CompileTime::Hash<23>`
```
struct __cppobj CompileTime::Hash<23>
{
};

```

### `CompileTime::Hash<22>`
```
struct __cppobj CompileTime::Hash<22>
{
};

```

### `CompileTime::Hash<21>`
```
struct __cppobj CompileTime::Hash<21>
{
};

```

### `CompileTime::Hash<20>`
```
struct __cppobj CompileTime::Hash<20>
{
};

```

### `CompileTime::Hash<19>`
```
struct __cppobj CompileTime::Hash<19>
{
};

```

### `CompileTime::Hash<18>`
```
struct __cppobj CompileTime::Hash<18>
{
};

```

### `CompileTime::Hash<17>`
```
struct __cppobj CompileTime::Hash<17>
{
};

```

### `CompileTime::Hash<16>`
```
struct __cppobj CompileTime::Hash<16>
{
};

```

### `CompileTime::Hash<15>`
```
struct __cppobj CompileTime::Hash<15>
{
};

```

### `CompileTime::Hash<14>`
```
struct __cppobj CompileTime::Hash<14>
{
};

```

### `CompileTime::Hash<13>`
```
struct __cppobj CompileTime::Hash<13>
{
};

```

### `CompileTime::Hash<12>`
```
struct __cppobj CompileTime::Hash<12>
{
};

```

### `CompileTime::Hash<11>`
```
struct __cppobj CompileTime::Hash<11>
{
};

```

### `CompileTime::Hash<10>`
```
struct __cppobj CompileTime::Hash<10>
{
};

```

### `CompileTime::Hash<9>`
```
struct __cppobj CompileTime::Hash<9>
{
};

```

### `CompileTime::Hash<8>`
```
struct __cppobj CompileTime::Hash<8>
{
};

```

### `CompileTime::Hash<7>`
```
struct __cppobj CompileTime::Hash<7>
{
};

```

### `CompileTime::Hash<6>`
```
struct __cppobj CompileTime::Hash<6>
{
};

```

### `CompileTime::Hash<5>`
```
struct __cppobj CompileTime::Hash<5>
{
};

```

### `CompileTime::Hash<4>`
```
struct __cppobj CompileTime::Hash<4>
{
};

```

### `CompileTime::Hash<3>`
```
struct __cppobj CompileTime::Hash<3>
{
};

```

### `CompileTime::Hash<2>`
```
struct __cppobj CompileTime::Hash<2>
{
};

```

### `CompileTime::Hash<1>`
```
struct __cppobj CompileTime::Hash<1>
{
};

```

### `ClientInstanceScreenModel_vtbl`
```
struct /*VFT*/ ClientInstanceScreenModel_vtbl
{
  void (__fastcall *~IDlcBatcher)(IDlcBatcher *this);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<PackIdVersion> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<std::string> *);
  IDlcBatchModel *(__fastcall *getDlcBatchModel)(IDlcBatcher *this, const std::vector<DlcId> *);
};

```

### `ClientInstanceScreenController_vtbl`
```
struct /*VFT*/ ClientInstanceScreenController_vtbl
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

### `ContainerSplitControl`
```
struct __cppobj __declspec(align(8)) ContainerSplitControl
{
  SlotData slot;
  int addedCount;
};

```

### `ContainerManagerController_vtbl`
```
struct /*VFT*/ ContainerManagerController_vtbl
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

### `ContainerController`
```
struct __cppobj __declspec(align(8)) ContainerController
{
  ContainerController_vtbl *__vftable /*VFT*/;
  std::weak_ptr<ContainerModel> mContainerModel;
  bool mDrop;
};

```

### `ContainerController_vtbl`
```
struct /*VFT*/ ContainerController_vtbl
{
  void (__fastcall *~ContainerController)(ContainerController *this);
  bool (__fastcall *canRemove)(ContainerController *this, int, int);
  bool (__fastcall *isItemAllowed)(ContainerController *this, const ItemStackBase *);
  bool (__fastcall *isItemFiltered)(ContainerController *this, const Recipes *, const ItemStackBase *);
  int (__fastcall *getBackgroundStyle)(ContainerController *this, int, bool);
  ItemSetType (__fastcall *_canSet)(ContainerController *this, int, const ItemStackBase *, ItemTransferAmount);
  int (__fastcall *_getAvailableSetCount)(ContainerController *this, int, const ItemStackBase *);
  bool (__fastcall *_canRemove)(ContainerController *this, int, int);
  void (__fastcall *_onItemChanged)(ContainerController *this, int);
};

```

### `CompileTime::Hash<50>`
```
struct __cppobj CompileTime::Hash<50>
{
};

```

### `CompileTime::Hash<39>`
```
struct __cppobj CompileTime::Hash<39>
{
};

```

### `CompileTime::Hash<49>`
```
struct __cppobj CompileTime::Hash<49>
{
};

```

### `CompileTime::Hash<48>`
```
struct __cppobj CompileTime::Hash<48>
{
};

```

### `CompileTime::Hash<47>`
```
struct __cppobj CompileTime::Hash<47>
{
};

```

### `CompileTime::Hash<46>`
```
struct __cppobj CompileTime::Hash<46>
{
};

```

### `CompileTime::Hash<45>`
```
struct __cppobj CompileTime::Hash<45>
{
};

```

### `CompileTime::Hash<44>`
```
struct __cppobj CompileTime::Hash<44>
{
};

```

### `CompileTime::Hash<43>`
```
struct __cppobj CompileTime::Hash<43>
{
};

```

### `CompileTime::Hash<42>`
```
struct __cppobj CompileTime::Hash<42>
{
};

```

### `CompileTime::Hash<41>`
```
struct __cppobj CompileTime::Hash<41>
{
};

```

### `CompileTime::Hash<40>`
```
struct __cppobj CompileTime::Hash<40>
{
};

```

### `CorrectPlayerPredictionInput`
```
struct __cppobj CorrectPlayerPredictionInput : IReplayableActorInput
{
  CorrectPlayerMovePredictionPacket mPacket;
};

```

### `ClientPlayerRewindListener`
```
struct __cppobj ClientPlayerRewindListener : PlayerEventListener
{
  std::vector<std::unique_ptr<IReplayableActorStateSource>> mActorStateSources;
};

```

### `ClientPlayerRewindListener_vtbl`
```
struct /*VFT*/ ClientPlayerRewindListener_vtbl
{
  void (__fastcall *~PlayerEventListener)(PlayerEventListener *this);
  EventResult (__fastcall *onPlayerAwardAchievement)(PlayerEventListener *this, Player *, MinecraftEventing::AchievementIds);
  EventResult (__fastcall *onPlayerPortalBuilt)(PlayerEventListener *this, Player *, AutomaticID<Dimension,int>);
  EventResult (__fastcall *onPlayerPortalUsed)(PlayerEventListener *this, Player *, AutomaticID<Dimension,int>, AutomaticID<Dimension,int>);
  EventResult (__fastcall *onPlayerCaravanChanged)(PlayerEventListener *this, const Actor *, int);
  EventResult (__fastcall *onPlayerSaved)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerInput)(PlayerEventListener *this, IPlayerMovementProxy *, MoveInputHandler *);
  EventResult (__fastcall *onPlayerAuthInputReceived)(PlayerEventListener *this, Player *, const PlayerAuthInputPacket *);
  EventResult (__fastcall *onPlayerAuthInputApplied)(PlayerEventListener *this, Player *, const PlayerAuthInputPacket *);
  EventResult (__fastcall *onPlayerTurn)(PlayerEventListener *this, Player *, Vec2 *);
  EventResult (__fastcall *onCameraSetPlayerRot)(PlayerEventListener *this, Player *, const Camera *);
  EventResult (__fastcall *onStartDestroyBlock)(PlayerEventListener *this, Player *, const BlockPos *, unsigned __int8 *);
  EventResult (__fastcall *onPlayerAction)(PlayerEventListener *this, Player *, PlayerActionType, const BlockPos *, int);
  EventResult (__fastcall *onPlayerHurt)(PlayerEventListener *this, const PlayerDamageEvent *);
  EventResult (__fastcall *onLocalPlayerDeath)(PlayerEventListener *this, IClientInstance *, LocalPlayer *);
  EventResult (__fastcall *onLocalPlayerRespawn)(PlayerEventListener *this, IClientInstance *, LocalPlayer *);
  EventResult (__fastcall *onPlayerMove)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerSlide)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerTargetBlockHit)(PlayerEventListener *this, Player *, const int);
  EventResult (__fastcall *onPlayerAIStepBegin)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerTick)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerStartRiding)(PlayerEventListener *this, Player *, Actor *);
  EventResult (__fastcall *onPlayerStopRiding)(PlayerEventListener *this, Player *, bool, bool, bool);
  EventResult (__fastcall *onPlayerCreated)(PlayerEventListener *this, LocalPlayer *, const std::string *, const std::string *, bool);
  EventResult (__fastcall *onPlayerTeleported)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerAttackedActor)(PlayerEventListener *this, Player *, Actor *);
  EventResult (__fastcall *onPlayerMovementCorrected)(PlayerEventListener *this, Player *, const Vec3 *, const float, const float);
  EventResult (__fastcall *onPlayerMovementAnomaly)(PlayerEventListener *this, Player *, const Vec3 *, const float, const float);
  EventResult (__fastcall *onPlayerDestroyedBlock)(PlayerEventListener *this, Player *, const BlockLegacy *);
  EventResult (__fastcall *onPlayerDestroyedBlock)(PlayerEventListener *this, Player *, int, int, int);
  EventResult (__fastcall *onPlayerOnGround)(PlayerEventListener *this, Player *);
  EventResult (__fastcall *onPlayerEquippedArmor)(PlayerEventListener *this, Player *, const ItemDescriptor *);
  EventResult (__fastcall *onPlayerEnchantedItem)(PlayerEventListener *this, Player *, const ItemStack *, const ItemEnchants *);
  EventResult (__fastcall *onPlayerNamedItem)(PlayerEventListener *this, Player *, const ItemDescriptor *);
  EventResult (__fastcall *onPlayerItemUseInteraction)(PlayerEventListener *this, Player *, const ItemInstance *);
  EventResult (__fastcall *onPlayerItemPlaceInteraction)(PlayerEventListener *this, Player *, const ItemInstance *);
  EventResult (__fastcall *onPlayerStartUsingItem)(PlayerEventListener *this, const Player *, const ItemStack *);
  EventResult (__fastcall *onPlayerStopUsingItem)(PlayerEventListener *this, const Player *, const ItemStack *);
  EventResult (__fastcall *onPlayerCraftedItem)(PlayerEventListener *this, Player *, const ItemInstance *, bool, bool, bool, int, int, int, bool, bool, const std::vector<short> *);
  EventResult (__fastcall *onPlayerItemEquipped)(PlayerEventListener *this, Player *, const ItemInstance *, int);
  EventResult (__fastcall *onPlayerJumped)(PlayerEventListener *this, const Player *);
  EventResult (__fastcall *onPlayerOpenContainer)(PlayerEventListener *this, Player *, ContainerType, const BlockPos *, ActorUniqueID);
  EventResult (__fastcall *onPlayerPiglinBarter)(PlayerEventListener *this, Player *, const std::string *, bool);
  EventResult (__fastcall *onPlayerAddExp)(PlayerEventListener *this, const PlayerAddExpEvent *);
  EventResult (__fastcall *onPlayerAddLevel)(PlayerEventListener *this, const PlayerAddLevelEvent *);
  EventResult (__fastcall *onPlayerArmorExchange)(PlayerEventListener *this, const PlayerArmorExchangeEvent *);
  EventResult (__fastcall *onPlayerDestroyBlock)(PlayerEventListener *this, const PlayerDestroyBlockEvent *);
  EventResult (__fastcall *onPlayerDie)(PlayerEventListener *this, const PlayerDamageEvent *);
  EventResult (__fastcall *onPlayerGetExperienceOrb)(PlayerEventListener *this, const PlayerGetExperienceOrbEvent *);
  EventResult (__fastcall *onPlayerSayCommand)(PlayerEventListener *this, const PlayerSayCommandEvent *);
  EventResult (__fastcall *onPlayerShootArrow)(PlayerEventListener *this, const PlayerShootArrowEvent *);
  EventResult (__fastcall *onPlayerStopLoading)(PlayerEventListener *this, const PlayerEvent *);
  EventResult (__fastcall *onPlayerUseNameTag)(PlayerEventListener *this, const PlayerUseNameTagEvent *);
};

```

### `cg::TextureSetLayerTypeHash`
```
struct __cppobj cg::TextureSetLayerTypeHash
{
};

```

### `ClientPlayerMovementProxy`
```
struct __cppobj ClientPlayerMovementProxy : DirectPlayerMovementProxy
{
  std::unique_ptr<IClientInstanceProxy> mClient;
};

```

### `ClientBlockPipeline::FaceSchematicInstance`
```
struct __cppobj ClientBlockPipeline::FaceSchematicInstance
{
  bool mExists;
  const ClientBlockPipeline::Material *mMaterial;
  ClientBlockPipeline::UvTransform mUvTransform;
};

```

### `ClientBlockPipeline::NullPtrErrorChecker`
```
struct __cppobj ClientBlockPipeline::NullPtrErrorChecker
{
};

```

### `ClientBlockPipeline::BlockOpacityData`
```
struct __cppobj ClientBlockPipeline::BlockOpacityData
{
  bool mSolid;
  bool mOpaque;
};

```

### `ClientBlockPipeline::Instance::StepCache`
```
struct __cppobj ClientBlockPipeline::Instance::StepCache
{
  unsigned __int64 mDependenciesCount;
  unsigned __int64 mDependentsCount;
  ClientBlockPipeline::StepResult mResult;
};

```

### `ClientBlockPipeline::Instance`
```
struct __cppobj ClientBlockPipeline::Instance
{
  const ClientBlockPipeline::Description *mDescription;
  std::vector<ClientBlockPipeline::Instance::StepCache> mStepCache;
  std::queue<unsigned __int64> mStepsToProcess;
  std::vector<std::function<void __cdecl(ClientBlockPipeline::Inputs const &)>> mCallbackFunctions;
};

```

### `ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockCell>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockCell>
{
  Pos mMin;
  Pos mMax;
  std::vector<ClientBlockPipeline::BlockCell> mData;
};

```

### `ClientBlockPipeline::OwnedBlockVolume`
```
struct __cppobj ClientBlockPipeline::OwnedBlockVolume : ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockCell>
{
};

```

### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell>`
```
struct __cppobj ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell>
{
  Pos mMin;
  Pos mMax;
  buffer_span_mut<ClientBlockPipeline::BlockCell> mView;
};

```

### `ClientBlockPipeline::BlockTessellatorPipeline::_run::__l2::<lambda_95e3b116649ef0529b93b2b805ca35e0>`
```
struct __cppobj ClientBlockPipeline::BlockTessellatorPipeline::_run::__l2::<lambda_95e3b116649ef0529b93b2b805ca35e0>
{
  ClientBlockPipeline::BlockTessellatorPipeline *const __this;
};

```

### `ClientBlockPipeline::QuadIndices`
```
struct __cppobj ClientBlockPipeline::QuadIndices
{
  std::array<unsigned __int64,4> mIndices;
};

```

### `ClientBlockPipeline::FaceDimmingStep`
```
struct __cppobj ClientBlockPipeline::FaceDimmingStep : ClientBlockPipeline::Step
{
  ClientBlockPipeline::DimensionDimmingScalars mDimmingScalars;
};

```

### `ClientBlockPipeline::FaceDimmingStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::FaceDimmingStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::FaceAttribute<Vec3>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<Vec3> : std::vector<Vec3>
{
};

```

### `ClientBlockPipeline::FaceNormalAttributes`
```
struct __cppobj ClientBlockPipeline::FaceNormalAttributes : ClientBlockPipeline::FaceAttribute<Vec3>
{
};

```

### `ClientBlockPipeline::FaceAttribute<float>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<float> : std::vector<float>
{
};

```

### `ClientBlockPipeline::FaceDimmingAttributes`
```
struct __cppobj ClientBlockPipeline::FaceDimmingAttributes : ClientBlockPipeline::FaceAttribute<float>
{
};

```

### `ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::Material const *>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::Material const *> : std::vector<ClientBlockPipeline::Material const *>
{
};

```

### `ClientBlockPipeline::MaterialFaceAttributes`
```
struct __cppobj ClientBlockPipeline::MaterialFaceAttributes : ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::Material const *>
{
};

```

### `ClientBlockPipeline::FaceMergingStep`
```
struct __cppobj ClientBlockPipeline::FaceMergingStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::FaceMergingStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::FaceMergingStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::LocalClipArea`
```
struct __cppobj ClientBlockPipeline::LocalClipArea : AABB
{
};

```

### `ClientBlockPipeline::VertexAttribute<Vec3>`
```
struct __cppobj ClientBlockPipeline::VertexAttribute<Vec3> : std::vector<Vec3>
{
};

```

### `ClientBlockPipeline::PositionVertexAttributes`
```
struct __cppobj ClientBlockPipeline::PositionVertexAttributes : ClientBlockPipeline::VertexAttribute<Vec3>
{
};

```

### `ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadIndices>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadIndices> : std::vector<ClientBlockPipeline::QuadIndices>
{
};

```

### `ClientBlockPipeline::QuadIndicesFaceAttributes`
```
struct __cppobj ClientBlockPipeline::QuadIndicesFaceAttributes : ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadIndices>
{
};

```

### `ClientBlockPipeline::FaceAttribute<bool>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<bool> : std::vector<bool>
{
};

```

### `ClientBlockPipeline::CulledFaceAttribute`
```
struct __cppobj ClientBlockPipeline::CulledFaceAttribute : ClientBlockPipeline::FaceAttribute<bool>
{
};

```

### `ClientBlockPipeline::FlatLightBakingStep`
```
struct __cppobj ClientBlockPipeline::FlatLightBakingStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::FlatLightBakingStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::FlatLightBakingStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::VolumeOf<BrightnessPair>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<BrightnessPair>
{
  Pos mMin;
  Pos mMax;
  std::vector<BrightnessPair> mData;
};

```

### `ClientBlockPipeline::LightVolume`
```
struct __cppobj ClientBlockPipeline::LightVolume : ClientBlockPipeline::VolumeOf<BrightnessPair>
{
};

```

### `ClientBlockPipeline::FaceAttribute<Vec2>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<Vec2> : std::vector<Vec2>
{
};

```

### `ClientBlockPipeline::LightUvFaceAttributes`
```
struct __cppobj ClientBlockPipeline::LightUvFaceAttributes : ClientBlockPipeline::FaceAttribute<Vec2>
{
};

```

### `ClientBlockPipeline::GpuBufferGenStep`
```
struct __cppobj __declspec(align(8)) ClientBlockPipeline::GpuBufferGenStep : ClientBlockPipeline::Step
{
  bool mEmitColors;
};

```

### `ClientBlockPipeline::GpuBufferGenStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::GpuBufferGenStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::UvTransform>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::UvTransform> : std::vector<ClientBlockPipeline::UvTransform>
{
};

```

### `ClientBlockPipeline::ImageUvFaceAttributes`
```
struct __cppobj ClientBlockPipeline::ImageUvFaceAttributes : ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::UvTransform>
{
};

```

### `ClientBlockPipeline::FaceAttribute<unsigned char>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<unsigned char> : std::vector<unsigned char>
{
};

```

### `ClientBlockPipeline::FaceDirectionFaceAttributes`
```
struct __cppobj ClientBlockPipeline::FaceDirectionFaceAttributes : ClientBlockPipeline::FaceAttribute<unsigned char>
{
};

```

### `ClientBlockPipeline::QuadVertexBrightnessUvs`
```
struct __cppobj ClientBlockPipeline::QuadVertexBrightnessUvs
{
  std::array<Vec2,4> mUvs;
};

```

### `ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadVertexBrightnessUvs>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadVertexBrightnessUvs> : std::vector<ClientBlockPipeline::QuadVertexBrightnessUvs>
{
};

```

### `ClientBlockPipeline::SmoothLightingUvAttributes`
```
struct __cppobj ClientBlockPipeline::SmoothLightingUvAttributes : ClientBlockPipeline::FaceAttribute<ClientBlockPipeline::QuadVertexBrightnessUvs>
{
};

```

### `ClientBlockPipeline::FaceAttribute<Vec4>`
```
struct __cppobj ClientBlockPipeline::FaceAttribute<Vec4> : std::vector<Vec4>
{
};

```

### `ClientBlockPipeline::VertexAOAttributes`
```
struct __cppobj ClientBlockPipeline::VertexAOAttributes : ClientBlockPipeline::FaceAttribute<Vec4>
{
};

```

### `ClientBlockPipeline::MaterialOverrideStep`
```
struct __cppobj __declspec(align(8)) ClientBlockPipeline::MaterialOverrideStep : ClientBlockPipeline::Step
{
  Bedrock::NonOwnerPointer<ClientBlockPipeline::Material const > mMaterialOverride;
  _BYTE mUvGenerationType[4];
};

```

### `ClientBlockPipeline::MaterialOverrideStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::MaterialOverrideStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::NormalGenerationStep`
```
struct __cppobj ClientBlockPipeline::NormalGenerationStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::NormalGenerationStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::NormalGenerationStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::PrimitiveGenerationStep`
```
struct __cppobj ClientBlockPipeline::PrimitiveGenerationStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::PrimitiveGenerationStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::PrimitiveGenerationStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::BlockSchematicInstance`
```
struct __cppobj ClientBlockPipeline::BlockSchematicInstance
{
  const ClientBlockPipeline::BlockSchematic *mSchematic;
  unsigned __int64 mBoxIndexStart;
  unsigned __int64 mBoxCount;
};

```

### `ClientBlockPipeline::BlockSchematicCell`
```
struct __cppobj ClientBlockPipeline::BlockSchematicCell
{
  std::array<ClientBlockPipeline::BlockSchematicInstance,2> mSchematics;
};

```

### `ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockSchematicCell>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockSchematicCell>
{
  Pos mMin;
  Pos mMax;
  std::vector<ClientBlockPipeline::BlockSchematicCell> mData;
};

```

### `ClientBlockPipeline::BlockSchematicVolume`
```
struct __cppobj ClientBlockPipeline::BlockSchematicVolume : ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockSchematicCell>
{
};

```

### `ClientBlockPipeline::BoxAttribute<ClientBlockPipeline::BoxSchematicInstance>`
```
struct __cppobj ClientBlockPipeline::BoxAttribute<ClientBlockPipeline::BoxSchematicInstance> : std::vector<ClientBlockPipeline::BoxSchematicInstance>
{
};

```

### `ClientBlockPipeline::BoxSchematicAttributes`
```
struct __cppobj ClientBlockPipeline::BoxSchematicAttributes : ClientBlockPipeline::BoxAttribute<ClientBlockPipeline::BoxSchematicInstance>
{
};

```

### `ClientBlockPipeline::FaceSchematicAttributes`
```
struct __cppobj ClientBlockPipeline::FaceSchematicAttributes : std::vector<ClientBlockPipeline::FaceSchematicInstance>
{
};

```

### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockSchematicCell>`
```
struct __cppobj ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockSchematicCell>
{
  Pos mMin;
  Pos mMax;
  buffer_span_mut<ClientBlockPipeline::BlockSchematicCell> mView;
};

```

### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockSchematicCell const >::VolumeViewOfIterator`
```
struct __cppobj ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockSchematicCell const >::VolumeViewOfIterator
{
  Pos mMin;
  Pos mMax;
  Pos mPosition;
  buffer_span_mut<ClientBlockPipeline::BlockSchematicCell const >::iterator mIterator;
};

```

### `ClientBlockPipeline::SchematicsJoiningStep`
```
struct __cppobj ClientBlockPipeline::SchematicsJoiningStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::SchematicsJoiningStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::SchematicsJoiningStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockOpacityData>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockOpacityData>
{
  Pos mMin;
  Pos mMax;
  std::vector<ClientBlockPipeline::BlockOpacityData> mData;
};

```

### `ClientBlockPipeline::SolidOpaqueBlockVolume`
```
const struct __cppobj ClientBlockPipeline::SolidOpaqueBlockVolume : ClientBlockPipeline::VolumeOf<ClientBlockPipeline::BlockOpacityData>
{
};

```

### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell const >::VolumeViewOfIterator`
```
struct __cppobj ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell const >::VolumeViewOfIterator
{
  Pos mMin;
  Pos mMax;
  Pos mPosition;
  buffer_span_mut<ClientBlockPipeline::BlockCell const >::iterator mIterator;
};

```

### `ClientBlockPipeline::SchematicsMappingStep`
```
struct __cppobj ClientBlockPipeline::SchematicsMappingStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::SchematicsMappingStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::SchematicsMappingStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::BakedBox`
```
struct __cppobj ClientBlockPipeline::BakedBox
{
  Vec3 mCenter;
  Vec3 mScale;
  Vec3 mRotation;
  Vec3 mPivot;
};

```

### `ClientBlockPipeline::BakedNode`
```
struct __cppobj ClientBlockPipeline::BakedNode
{
  Vec3 mPivot;
  Vec3 mRotation;
  Vec3 mScale;
  Vec3 mBindPoseRotation;
  float mInflate;
};

```

### `ClientBlockPipeline::SmoothLightBakingStep`
```
struct __cppobj ClientBlockPipeline::SmoothLightBakingStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::SmoothLightBakingStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::SmoothLightBakingStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::VolumeOf<float>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<float>
{
  Pos mMin;
  Pos mMax;
  std::vector<float> mData;
};

```

### `ClientBlockPipeline::AOBrightnessVolume`
```
struct __cppobj ClientBlockPipeline::AOBrightnessVolume : ClientBlockPipeline::VolumeOf<float>
{
};

```

### `ClientBlockPipeline::SmoothLightBakingStep::VisibleCellData`
```
struct __cppobj ClientBlockPipeline::SmoothLightBakingStep::VisibleCellData
{
  unsigned __int64 mIndex;
  float mDistanceSq;
  Pos mSampleCellPos;
};

```

### `ClientBlockPipeline::SurfaceExtractionStep`
```
struct __cppobj ClientBlockPipeline::SurfaceExtractionStep : ClientBlockPipeline::Step
{
};

```

### `ClientBlockPipeline::SurfaceExtractionStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::SurfaceExtractionStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::SurfaceExtractionStep::_run::__l2::QuadData`
```
struct __declspec(align(4)) ClientBlockPipeline::SurfaceExtractionStep::_run::__l2::QuadData
{
  std::array<int,4> vertices;
  unsigned __int8 facing;
};

```

### `Core::SharedMemoryTracker::SharedMemoryTrackerBase`
```
struct __cppobj Core::SharedMemoryTracker::SharedMemoryTrackerBase
{
  Core::SharedMemoryTracker::SharedMemoryTrackerBase_vtbl *__vftable /*VFT*/;
};

```

### `Core::SharedMemoryTracker::SharedMemoryTrackerBase_vtbl`
```
struct /*VFT*/ Core::SharedMemoryTracker::SharedMemoryTrackerBase_vtbl
{
  void (__fastcall *~SharedMemoryTrackerBase)(Core::SharedMemoryTracker::SharedMemoryTrackerBase *this);
};

```

### `cg::details::WorkToken`
```
struct __cppobj cg::details::WorkToken
{
  std::atomic<bool> mIsDone;
};

```

### `cg::GroupPoolDescription`
```
struct __declspec(align(8)) cg::GroupPoolDescription
{
  WorkerPool *mPool;
  Scheduler *mScheduler;
  bool mIsHelper;
};

```

### `cg::TaskDispatcherSchedulerTraits<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >`
```
struct __cppobj cg::TaskDispatcherSchedulerTraits<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >
{
};

```

### `cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution`
```
struct __cppobj cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution
{
};

```

### `cg::SchedulerExecutionTraits<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>,cg::details::WorkToken>`
```
struct __cppobj cg::SchedulerExecutionTraits<cg::LambdaExecutor<dragon::rendering::RenderContext,cg::TaskPoolGroupExecutionPolicy<dragon::rendering::RenderContext,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>,cg::details::WorkToken>
{
};

```

### `cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > >`
```
struct __cppobj cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > >
{
  std::shared_ptr<cg::details::WorkToken const > mToken;
  std::optional<std::shared_ptr<std::function<void __cdecl(dragon::rendering::RenderContext &)> > > mResult;
};

```

### `Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource> >`
```
struct __cppobj Core::Cache<unsigned __int64,dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource> >
{
  std::shared_mutex mAccess;
  std::unordered_map<unsigned __int64,std::shared_ptr<dragon::rendering::BufferResourceManager<dragon::rendering::TextureResourceType>::BufferResource>> mContent;
};

```

### `ClientBlockPipeline::WorldExtractorStep`
```
const struct __cppobj ClientBlockPipeline::WorldExtractorStep : ClientBlockPipeline::Step
{
  std::function<bool __cdecl(Block const &)> mBlockUsagePredicate;
};

```

### `ClientBlockPipeline::WorldExtractorStep_vtbl`
```
struct /*VFT*/ ClientBlockPipeline::WorldExtractorStep_vtbl
{
  void (__fastcall *~Step)(ClientBlockPipeline::Step *this);
  ClientBlockPipeline::StepResult *(__fastcall *run)(ClientBlockPipeline::Step *this, ClientBlockPipeline::StepResult *result, const ClientBlockPipeline::Inputs *);
};

```

### `ClientBlockPipeline::VolumeOf<int>`
```
struct __cppobj ClientBlockPipeline::VolumeOf<int>
{
  Pos mMin;
  Pos mMax;
  std::vector<int> mData;
};

```

### `ClientBlockPipeline::GrassTintVolume`
```
struct __cppobj ClientBlockPipeline::GrassTintVolume : ClientBlockPipeline::VolumeOf<int>
{
};

```

### `ClientBlockPipeline::WaterTintVolume`
```
struct __cppobj ClientBlockPipeline::WaterTintVolume : ClientBlockPipeline::VolumeOf<int>
{
};

```

### `ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell>::VolumeViewOfIterator`
```
struct __cppobj ClientBlockPipeline::VolumeViewOf<ClientBlockPipeline::BlockCell>::VolumeViewOfIterator
{
  Pos mMin;
  Pos mMax;
  Pos mPosition;
  buffer_span_mut<ClientBlockPipeline::BlockCell>::iterator mIterator;
};

```

### `ClientBlockPipeline::WorldClipArea`
```
struct __cppobj ClientBlockPipeline::WorldClipArea : AABB
{
};

```

### `CrimsonForestMoodSoundPlayer`
```
struct __cppobj CrimsonForestMoodSoundPlayer
{
};

```

### `CommerceAuthToken`
```
struct __cppobj CommerceAuthToken
{
  std::string mToken;
  std::string mExpiration;
};

```

### `CommerceIdentity`
```
struct __cppobj CommerceIdentity : std::enable_shared_from_this<CommerceIdentity>
{
  IMinecraftEventing *mEventing;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  std::unique_ptr<SecureStorage> mSecureStore;
  std::unique_ptr<Crypto::Asymmetric::Asymmetric> mSSLInterface;
  bool mHasQueriedForDeviceId;
  bool mDeviceAccountUsed;
  std::string mUserId;
  CommerceAuthToken mDeviceAuthToken;
};

```

### `Crypto::Pkcs7::ISystemInterface`
```
struct __cppobj Crypto::Pkcs7::ISystemInterface
{
  Crypto::Pkcs7::ISystemInterface_vtbl *__vftable /*VFT*/;
};

```

### `Crypto::Pkcs7::ISystemInterface_vtbl`
```
struct /*VFT*/ Crypto::Pkcs7::ISystemInterface_vtbl
{
  void (__fastcall *~ISystemInterface)(Crypto::Pkcs7::ISystemInterface *this);
  std::vector<unsigned char> *(__fastcall *verifyAndReadPKCS7Data)(Crypto::Pkcs7::ISystemInterface *this, std::vector<unsigned char> *result, const std::string *);
};

```

### `cmsghdr`
```
struct cmsghdr
{
  unsigned __int64 cmsg_len;
  int cmsg_level;
  int cmsg_type;
};

```

### `Concurrency::Context`
```
struct __cppobj Concurrency::Context
{
  Concurrency::Context_vtbl *__vftable /*VFT*/;
};

```

### `Concurrency::Context_vtbl`
```
struct /*VFT*/ Concurrency::Context_vtbl
{
  unsigned int (__fastcall *GetId)(Concurrency::Context *this);
  unsigned int (__fastcall *GetVirtualProcessorId)(Concurrency::Context *this);
  unsigned int (__fastcall *GetScheduleGroupId)(Concurrency::Context *this);
  void (__fastcall *Unblock)(Concurrency::Context *this);
  bool (__fastcall *IsSynchronouslyBlocked)(Concurrency::Context *this);
  void (__fastcall *~Context)(Concurrency::Context *this);
};

```

### `Concurrency::message_not_found`
```
struct __cppobj Concurrency::message_not_found : std::exception
{
};

```

### `Concurrency::message_not_found_vtbl`
```
struct /*VFT*/ Concurrency::message_not_found_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::critical_section`
```
struct __cppobj Concurrency::critical_section
{
  void *_M_activeNode[5];
  void *volatile _M_pHead;
  void *volatile _M_pTail;
};

```

### `Concurrency::critical_section::scoped_lock`
```
struct __cppobj Concurrency::critical_section::scoped_lock
{
  Concurrency::critical_section *_M_critical_section;
  void *_M_node[5];
};

```

### `Concurrency::Scheduler`
```
struct __cppobj Concurrency::Scheduler
{
  Concurrency::Scheduler_vtbl *__vftable /*VFT*/;
};

```

### `Concurrency::SchedulerPolicy::_PolicyBag::<unnamed_type__M_values>::<unnamed_type__M_specificValues>`
```
struct Concurrency::SchedulerPolicy::_PolicyBag::<unnamed_type__M_values>::<unnamed_type__M_specificValues>
{
  Concurrency::SchedulerType _M_schedulerKind;
  unsigned int _M_maxConcurrency;
  unsigned int _M_minConcurrency;
  unsigned int _M_targetOversubscriptionFactor;
  unsigned int _M_localContextCacheSize;
  unsigned int _M_contextStackSize;
  unsigned int _M_contextPriority;
  Concurrency::SchedulingProtocolType _M_schedulingProtocol;
  Concurrency::DynamicProgressFeedbackType _M_dynamicProgressFeedback;
  Concurrency::WinRTInitializationType _M_WinRTInitialization;
};

```

### `Concurrency::SchedulerPolicy::_PolicyBag`
```
struct Concurrency::SchedulerPolicy::_PolicyBag
{
  Concurrency::SchedulerPolicy::_PolicyBag::<unnamed_type__M_values> _M_values;
};

```

### `Concurrency::SchedulerPolicy`
```
struct __cppobj Concurrency::SchedulerPolicy
{
  Concurrency::SchedulerPolicy::_PolicyBag *_M_pPolicyBag;
};

```

### `Concurrency::ScheduleGroup`
```
struct __cppobj Concurrency::ScheduleGroup
{
  Concurrency::ScheduleGroup_vtbl *__vftable /*VFT*/;
};

```

### `Concurrency::ScheduleGroup_vtbl`
```
struct /*VFT*/ Concurrency::ScheduleGroup_vtbl
{
  void (__fastcall *ScheduleTask)(Concurrency::ScheduleGroup *this, void (__fastcall *)(void *), void *);
  unsigned int (__fastcall *Id)(Concurrency::ScheduleGroup *this);
  unsigned int (__fastcall *Reference)(Concurrency::ScheduleGroup *this);
  unsigned int (__fastcall *Release)(Concurrency::ScheduleGroup *this);
  void (__fastcall *~ScheduleGroup)(Concurrency::ScheduleGroup *this);
};

```

### `Concurrency::location`
```
struct __cppobj Concurrency::location
{
  unsigned __int32 _M_type : 28;
  unsigned __int32 _M_reserved : 4;
  unsigned int _M_bindingId;
  $441E66D683A4B86F862CB9A174F60F9E ___u3;
  void *_M_pBinding;
};

```

### `Concurrency::Scheduler_vtbl`
```
struct /*VFT*/ Concurrency::Scheduler_vtbl
{
  void (__fastcall *~Scheduler)(Concurrency::Scheduler *this);
  unsigned int (__fastcall *Id)(Concurrency::Scheduler *this);
  unsigned int (__fastcall *GetNumberOfVirtualProcessors)(Concurrency::Scheduler *this);
  Concurrency::SchedulerPolicy *(__fastcall *GetPolicy)(Concurrency::Scheduler *this, Concurrency::SchedulerPolicy *result);
  unsigned int (__fastcall *Reference)(Concurrency::Scheduler *this);
  unsigned int (__fastcall *Release)(Concurrency::Scheduler *this);
  void (__fastcall *RegisterShutdownEvent)(Concurrency::Scheduler *this, void *);
  void (__fastcall *Attach)(Concurrency::Scheduler *this);
  Concurrency::ScheduleGroup *(__fastcall *CreateScheduleGroup)(Concurrency::Scheduler *this, Concurrency::location *);
  Concurrency::ScheduleGroup *(__fastcall *CreateScheduleGroup)(Concurrency::Scheduler *this);
  void (__fastcall *ScheduleTask)(Concurrency::Scheduler *this, void (__fastcall *)(void *), void *, Concurrency::location *);
  void (__fastcall *ScheduleTask)(Concurrency::Scheduler *this, void (__fastcall *)(void *), void *);
  bool (__fastcall *IsAvailableLocation)(Concurrency::Scheduler *this, const Concurrency::location *);
};

```

### `Concurrency::scheduler_resource_allocation_error`
```
struct __cppobj __declspec(align(8)) Concurrency::scheduler_resource_allocation_error : std::exception
{
  HRESULT _Hresult;
};

```

### `Concurrency::scheduler_resource_allocation_error_vtbl`
```
struct /*VFT*/ Concurrency::scheduler_resource_allocation_error_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::scheduler_worker_creation_error`
```
struct __cppobj Concurrency::scheduler_worker_creation_error : Concurrency::scheduler_resource_allocation_error
{
};

```

### `Concurrency::scheduler_worker_creation_error_vtbl`
```
struct /*VFT*/ Concurrency::scheduler_worker_creation_error_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::details::_RefCounterBase`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_RefCounterBase
{
  Concurrency::details::_RefCounterBase_vtbl *__vftable /*VFT*/;
  volatile int _M_refCount;
};

```

### `Concurrency::details::_RefCounterBase_vtbl`
```
struct /*VFT*/ Concurrency::details::_RefCounterBase_vtbl
{
  void (__fastcall *~_RefCounterBase)(Concurrency::details::_RefCounterBase *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounterBase *this);
};

```

### `Concurrency::details::_TaskCollectionBase`
```
struct __cppobj Concurrency::details::_TaskCollectionBase
{
  Concurrency::details::_TaskCollectionBase *_M_pParent;
  __int32 _M_inliningDepth : 28;
  __int32 _M_inlineFlags : 4;
  Concurrency::details::_CancellationTokenState *_M_pTokenState;
  void *_M_pOwningContext;
  int _M_unpoppedChores;
  volatile int _M_completedStolenChores;
  std::exception_ptr *_M_pException;
};

```

### `Concurrency::details::_RefCounter`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_RefCounter
{
  Concurrency::details::_RefCounter_vtbl *__vftable /*VFT*/;
  volatile int _M_refCount;
};

```

### `Concurrency::details::_RefCounter_vtbl`
```
struct /*VFT*/ Concurrency::details::_RefCounter_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
};

```

### `Concurrency::details::_CancellationTokenRegistration`
```
struct __cppobj Concurrency::details::_CancellationTokenRegistration : Concurrency::details::_RefCounter
{
  std::atomic<long> _M_state;
  std::condition_variable _M_CondVar;
  std::mutex _M_Mutex;
  bool _M_signaled;
  Concurrency::details::_CancellationTokenState *_M_pTokenState;
};

```

### `Concurrency::details::_CancellationTokenState`
```
struct __cppobj Concurrency::details::_CancellationTokenState : Concurrency::details::_RefCounter
{
  std::atomic<long> _M_stateFlag;
  std::mutex _M_listLock;
  Concurrency::details::_CancellationTokenState::TokenRegistrationContainer _M_registrations;
};

```

### `Concurrency::details::_CancellationTokenRegistration_vtbl`
```
struct /*VFT*/ Concurrency::details::_CancellationTokenRegistration_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Exec)(Concurrency::details::_CancellationTokenRegistration *this);
};

```

### `Concurrency::details::_CancellationTokenState::TokenRegistrationContainer::_Node`
```
struct __cppobj Concurrency::details::_CancellationTokenState::TokenRegistrationContainer::_Node
{
  Concurrency::details::_CancellationTokenRegistration *_M_token;
  Concurrency::details::_CancellationTokenState::TokenRegistrationContainer::_Node *_M_next;
};

```

### `Concurrency::details::_CancellationTokenState::TokenRegistrationContainer`
```
struct __cppobj Concurrency::details::_CancellationTokenState::TokenRegistrationContainer
{
  Concurrency::details::_CancellationTokenState::TokenRegistrationContainer::_Node *_M_begin;
  Concurrency::details::_CancellationTokenState::TokenRegistrationContainer::_Node *_M_last;
};

```

### `Concurrency::details::_CancellationTokenState_vtbl`
```
struct /*VFT*/ Concurrency::details::_CancellationTokenState_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
};

```

### `Concurrency::event`
```
struct __cppobj Concurrency::event
{
  void *volatile _M_pWaitChain;
  void *_M_pResetChain;
  Concurrency::critical_section _M_lock;
};

```

### `Concurrency::details::_TaskCollection`
```
struct __cppobj Concurrency::details::_TaskCollection : Concurrency::details::_TaskCollectionBase
{
  void *_M_stealTracker[4];
  int _M_activeStealersForCancellation;
  volatile int _M_exitCode;
  volatile int _M_executionStatus;
  Concurrency::event _M_event;
  Concurrency::details::_TaskCollection *_M_pOriginalCollection;
  Concurrency::details::_TaskCollection *_M_pNextAlias;
  void *_M_pTaskExtension;
  int _M_taskCookies[2];
  volatile int _M_flags;
  volatile int _M_chaining;
  unsigned int _M_boundQueueId;
  int _M_stackPos;
  void (__fastcall *_M_completionHandler)(void *);
  void *_M_pCompletionContext;
};

```

### `Concurrency::details::_AsyncTaskCollection`
```
struct __cppobj Concurrency::details::_AsyncTaskCollection : Concurrency::details::_RefCounterBase
{
  Concurrency::details::_TaskCollection _M_taskCollection;
};

```

### `Concurrency::details::_AsyncTaskCollection_vtbl`
```
struct /*VFT*/ Concurrency::details::_AsyncTaskCollection_vtbl
{
  void (__fastcall *~_RefCounterBase)(Concurrency::details::_RefCounterBase *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounterBase *this);
};

```

### `Concurrency::details::_Chore`
```
struct __cppobj Concurrency::details::_Chore
{
  Concurrency::details::_Chore_vtbl *__vftable /*VFT*/;
  void (__fastcall *m_pFunction)(void *);
};

```

### `Concurrency::details::_Chore_vtbl`
```
struct /*VFT*/ Concurrency::details::_Chore_vtbl
{
  void (__fastcall *~_Chore)(Concurrency::details::_Chore *this);
};

```

### `Concurrency::details::_AllocBase`
```
struct __cppobj Concurrency::details::_AllocBase
{
};

```

### `Concurrency::details::_UnrealizedChore`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_UnrealizedChore : Concurrency::details::_Chore, Concurrency::details::_AllocBase
{
  Concurrency::details::_TaskCollectionBase *_M_pTaskCollection;
  void (__fastcall *_M_pChoreFunction)(Concurrency::details::_UnrealizedChore *);
  bool _M_fRuntimeOwnsLifetime;
  bool _M_fDetached;
};

```

### `Concurrency::details::_UnrealizedChore_vtbl`
```
struct /*VFT*/ Concurrency::details::_UnrealizedChore_vtbl
{
  void (__fastcall *~_Chore)(Concurrency::details::_Chore *this);
};

```

### `Concurrency::details::_Task_generator_oversubscriber`
```
struct __cppobj Concurrency::details::_Task_generator_oversubscriber
{
};

```

### `Concurrency::details::_Beacon_reference`
```
struct __cppobj Concurrency::details::_Beacon_reference
{
  volatile int _M_signals;
};

```

### `Concurrency::details::_Cancellation_beacon`
```
struct __cppobj Concurrency::details::_Cancellation_beacon
{
  Concurrency::details::_Beacon_reference *_M_pRef;
};

```

### `Concurrency::details::_NonReentrantBlockingLock`
```
struct __cppobj Concurrency::details::_NonReentrantBlockingLock
{
  void *_M_criticalSection[5];
};

```

### `Concurrency::details::_NonReentrantBlockingLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_NonReentrantBlockingLock::_Scoped_lock
{
  Concurrency::details::_NonReentrantBlockingLock *_M_lock;
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_a40cf361f6b489cdc7950415e60bfc49> >`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_CancellationTokenCallback<<lambda_a40cf361f6b489cdc7950415e60bfc49> > : Concurrency::details::_CancellationTokenRegistration
{
  struct Concurrency::details::_JoinAllTokens_Add::__l5::<lambda_a40cf361f6b489cdc7950415e60bfc49> _M_function;
  _BYTE gapC0[8];
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_a40cf361f6b489cdc7950415e60bfc49> >_vtbl`
```
struct /*VFT*/ Concurrency::details::_CancellationTokenCallback<<lambda_a40cf361f6b489cdc7950415e60bfc49> >_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Exec)(Concurrency::details::_CancellationTokenRegistration *this);
};

```

### `Concurrency::details::_Task_impl_base`
```
struct __cppobj Concurrency::details::_Task_impl_base
{
  Concurrency::details::_Task_impl_base_vtbl *__vftable /*VFT*/;
  volatile Concurrency::details::_Task_impl_base::_TaskInternalState _M_TaskState;
  bool _M_fFromAsync;
  bool _M_fUnwrappedTask;
  std::shared_ptr<Concurrency::details::_ExceptionHolder> _M_exceptionHolder;
  std::mutex _M_ContinuationsCritSec;
  Concurrency::details::_ContinuationTaskHandleBase *_M_Continuations;
  Concurrency::details::_CancellationTokenState *_M_pTokenState;
  Concurrency::details::_CancellationTokenRegistration *_M_pRegistration;
  Concurrency::details::_TaskCollectionBaseImpl _M_TaskCollection;
  Concurrency::details::_TaskCreationCallstack _M_pTaskCreationCallstack;
  Concurrency::details::_TaskEventLogger _M_taskEventLogger;
};

```

### `Concurrency::details::_ExceptionHolder`
```
struct __cppobj Concurrency::details::_ExceptionHolder
{
  std::atomic<long> _M_exceptionObserved;
  std::exception_ptr _M_stdException;
  Concurrency::details::_TaskCreationCallstack _M_stackTrace;
};

```

### `Concurrency::details::_Task_impl_base_vtbl`
```
struct /*VFT*/ Concurrency::details::_Task_impl_base_vtbl
{
  void (__fastcall *~_Task_impl_base)(Concurrency::details::_Task_impl_base *this);
  bool (__fastcall *_CancelAndRunContinuations)(Concurrency::details::_Task_impl_base *this, bool, bool, bool, const std::shared_ptr<Concurrency::details::_ExceptionHolder> *);
};

```

### `Concurrency::details::_TaskProcHandle`
```
struct __cppobj Concurrency::details::_TaskProcHandle
{
  Concurrency::details::_TaskProcHandle_vtbl *__vftable /*VFT*/;
};

```

### `Concurrency::details::_TaskProcHandle_vtbl`
```
struct /*VFT*/ Concurrency::details::_TaskProcHandle_vtbl
{
  void (__fastcall *~_TaskProcHandle)(Concurrency::details::_TaskProcHandle *this);
  void (__fastcall *invoke)(Concurrency::details::_TaskProcHandle *this);
};

```

### `Concurrency::details::_ContinuationTaskHandleBase`
```
struct __cppobj Concurrency::details::_ContinuationTaskHandleBase : Concurrency::details::_TaskProcHandle
{
  Concurrency::details::_ContinuationTaskHandleBase *_M_next;
  Concurrency::task_continuation_context _M_continuationContext;
  bool _M_isTaskBasedContinuation;
  Concurrency::details::_TaskInliningMode _M_inliningMode;
};

```

### `Concurrency::details::_ContinuationTaskHandleBase_vtbl`
```
struct /*VFT*/ Concurrency::details::_ContinuationTaskHandleBase_vtbl
{
  void (__fastcall *~_TaskProcHandle)(Concurrency::details::_TaskProcHandle *this);
  void (__fastcall *invoke)(Concurrency::details::_TaskProcHandle *this);
  std::shared_ptr<Concurrency::details::_Task_impl_base> *(__fastcall *_GetTaskImplBase)(Concurrency::details::_ContinuationTaskHandleBase *this, std::shared_ptr<Concurrency::details::_Task_impl_base> *result);
};

```

### `Concurrency::scheduler_interface_vtbl`
```
struct /*VFT*/ Concurrency::scheduler_interface_vtbl
{
  void (__fastcall *schedule)(Concurrency::scheduler_interface *this, void (__fastcall *)(void *), void *);
};

```

### `Concurrency::details::_TaskCollectionBaseImpl`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_TaskCollectionBaseImpl
{
  std::condition_variable _M_StateChanged;
  std::mutex _M_Cs;
  Concurrency::scheduler_ptr _M_pScheduler;
  Concurrency::details::_TaskCollectionBaseImpl::_TaskCollectionState _M_State;
};

```

### `Concurrency::details::_TaskEventLogger`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_TaskEventLogger
{
  Concurrency::details::_Task_impl_base *_M_task;
  bool _M_scheduled;
  bool _M_taskPostEventStarted;
};

```

### `Concurrency::details::_Task_impl_base::_RegisterCancellation::__l2::<lambda_be3e5d9dce35d2c8dbfa8485373731d5>`
```
struct __cppobj Concurrency::details::_Task_impl_base::_RegisterCancellation::__l2::<lambda_be3e5d9dce35d2c8dbfa8485373731d5>
{
  std::weak_ptr<Concurrency::details::_Task_impl_base> _WeakPtr;
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_be3e5d9dce35d2c8dbfa8485373731d5> >`
```
struct __cppobj Concurrency::details::_CancellationTokenCallback<<lambda_be3e5d9dce35d2c8dbfa8485373731d5> > : Concurrency::details::_CancellationTokenRegistration
{
  Concurrency::details::_Task_impl_base::_RegisterCancellation::__l2::<lambda_be3e5d9dce35d2c8dbfa8485373731d5> _M_function;
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_be3e5d9dce35d2c8dbfa8485373731d5> >_vtbl`
```
struct /*VFT*/ Concurrency::details::_CancellationTokenCallback<<lambda_be3e5d9dce35d2c8dbfa8485373731d5> >_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Exec)(Concurrency::details::_CancellationTokenRegistration *this);
};

```

### `Concurrency::details::_TypeSelectorAsyncAction`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncAction
{
};

```

### `Concurrency::details::_Interruption_exception`
```
struct __cppobj Concurrency::details::_Interruption_exception : std::exception
{
};

```

### `Concurrency::details::_Interruption_exception_vtbl`
```
struct /*VFT*/ Concurrency::details::_Interruption_exception_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::details::_ResultHolder<unsigned char>`
```
struct Concurrency::details::_ResultHolder<unsigned char>
{
  unsigned __int8 _Result;
};

```

### `Concurrency::details::_Task_impl<unsigned char>`
```
struct __cppobj Concurrency::details::_Task_impl<unsigned char> : Concurrency::details::_Task_impl_base
{
  Concurrency::details::_ResultHolder<unsigned char> _M_Result;
  std::function<void __cdecl(void)> _M_InternalCancellation;
};

```

### `Concurrency::details::_Task_impl<unsigned char>_vtbl`
```
struct /*VFT*/ Concurrency::details::_Task_impl<unsigned char>_vtbl
{
  void (__fastcall *~_Task_impl_base)(Concurrency::details::_Task_impl_base *this);
  bool (__fastcall *_CancelAndRunContinuations)(Concurrency::details::_Task_impl_base *this, bool, bool, bool, const std::shared_ptr<Concurrency::details::_ExceptionHolder> *);
};

```

### `Concurrency::details::_Task_completion_event_impl<unsigned char>`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_Task_completion_event_impl<unsigned char>
{
  std::vector<std::shared_ptr<Concurrency::details::_Task_impl<unsigned char> >> _M_tasks;
  std::mutex _M_taskListCritSec;
  Concurrency::details::_ResultHolder<unsigned char> _M_value;
  std::shared_ptr<Concurrency::details::_ExceptionHolder> _M_exceptionHolder;
  bool _M_fHasValue;
  bool _M_fIsCanceled;
};

```

### `Concurrency::details::_TaskProcThunk`
```
struct __cppobj Concurrency::details::_TaskProcThunk
{
  std::function<void __cdecl(void)> _M_func;
};

```

### `Concurrency::details::_TaskProcThunk::_Holder`
```
struct __cppobj Concurrency::details::_TaskProcThunk::_Holder
{
  Concurrency::details::_TaskProcThunk *_M_pThunk;
};

```

### `Concurrency::details::CancellationTokenRegistration_TaskProc`
```
struct __cppobj Concurrency::details::CancellationTokenRegistration_TaskProc : Concurrency::details::_CancellationTokenRegistration
{
  void (__fastcall *_M_proc)(void *);
  void *_M_pData;
};

```

### `Concurrency::details::CancellationTokenRegistration_TaskProc_vtbl`
```
struct /*VFT*/ Concurrency::details::CancellationTokenRegistration_TaskProc_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Exec)(Concurrency::details::_CancellationTokenRegistration *this);
};

```

### `Concurrency::details::_TaskWorkItemRAIILogger`
```
struct __cppobj Concurrency::details::_TaskWorkItemRAIILogger
{
  Concurrency::details::_TaskEventLogger *_M_logger;
};

```

### `Concurrency::details::_Scheduler`
```
struct __cppobj Concurrency::details::_Scheduler
{
  Concurrency::Scheduler *_M_pScheduler;
};

```

### `Concurrency::details::_ThenImplOptions`
```
struct __cppobj Concurrency::details::_ThenImplOptions
{
  Concurrency::details::_CancellationTokenState *_PTokenState;
  Concurrency::scheduler_ptr _Scheduler;
  Concurrency::details::_TaskCreationCallstack _CreationStack;
  Concurrency::details::_TaskInliningMode _InliningMode;
  Concurrency::task_continuation_context *_PContinuationContext;
};

```

### `Concurrency::details::_ReentrantPPLLock`
```
struct __cppobj Concurrency::details::_ReentrantPPLLock
{
  Concurrency::critical_section _M_criticalSection;
  int _M_recursionCount;
  volatile int _M_owner;
};

```

### `Concurrency::details::_ReentrantPPLLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_ReentrantPPLLock::_Scoped_lock
{
  Concurrency::details::_ReentrantPPLLock *_M_lock;
  void *_M_lockNode[5];
};

```

### `Concurrency::details::_TaskTypeFromParam<Concurrency::task_completion_event<void> >`
```
struct __cppobj Concurrency::details::_TaskTypeFromParam<Concurrency::task_completion_event<void> >
{
};

```

### `Concurrency::details::_IsUnwrappedAsyncSelector<Concurrency::details::_TypeSelectorNoAsync>`
```
struct __cppobj Concurrency::details::_IsUnwrappedAsyncSelector<Concurrency::details::_TypeSelectorNoAsync>
{
};

```

### `Concurrency::details::_Context`
```
struct __cppobj Concurrency::details::_Context
{
  Concurrency::Context *_M_pContext;
};

```

### `Concurrency::details::_BadArgType`
```
struct __cppobj Concurrency::details::_BadArgType
{
};

```

### `Concurrency::details::_SpinCount`
```
struct __cppobj Concurrency::details::_SpinCount
{
};

```

### `Concurrency::task_completion_event<unsigned char>`
```
struct __cppobj Concurrency::task_completion_event<unsigned char>
{
  std::shared_ptr<Concurrency::details::_Task_completion_event_impl<unsigned char> > _M_Impl;
};

```

### `Concurrency::details::_RunAllParam<unsigned char>`
```
struct __cppobj Concurrency::details::_RunAllParam<unsigned char>
{
  Concurrency::task_completion_event<unsigned char> _M_completed;
  std::atomic<unsigned __int64> _M_completeCount;
  unsigned __int64 _M_numTasks;
};

```

### `Concurrency::details::_Threadpool_chore`
```
struct __cppobj Concurrency::details::_Threadpool_chore
{
  void *_M_work;
  void (__fastcall *_M_callback)(void *);
  void *_M_data;
};

```

### `Concurrency::details::_DefaultPPLTaskScheduler::_PPLTaskChore`
```
struct __cppobj Concurrency::details::_DefaultPPLTaskScheduler::_PPLTaskChore
{
  Concurrency::details::_Threadpool_chore _M_Chore;
  void (__fastcall *_M_proc)(void *);
  void *_M_param;
};

```

### `Concurrency::details::_DefaultPPLTaskScheduler_vtbl`
```
struct /*VFT*/ Concurrency::details::_DefaultPPLTaskScheduler_vtbl
{
  void (__fastcall *schedule)(Concurrency::scheduler_interface *this, void (__fastcall *)(void *), void *);
};

```

### `Concurrency::details::_Threadpool_task`
```
struct __cppobj Concurrency::details::_Threadpool_task
{
  Concurrency::details::_Threadpool_task_vtbl *__vftable /*VFT*/;
  Concurrency::details::_Threadpool_chore _M_chore;
};

```

### `Concurrency::details::_Threadpool_task_vtbl`
```
struct /*VFT*/ Concurrency::details::_Threadpool_task_vtbl
{
  void (__fastcall *_Invoke)(Concurrency::details::_Threadpool_task *this);
  void (__fastcall *~_Threadpool_task)(Concurrency::details::_Threadpool_task *this);
};

```

### `Concurrency::details::_TypeSelectorAsyncOperationOrTask`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncOperationOrTask
{
};

```

### `Concurrency::details::_TypeSelectorAsyncTask`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncTask : Concurrency::details::_TypeSelectorAsyncOperationOrTask
{
};

```

### `Concurrency::details::_CurrentScheduler`
```
struct __cppobj Concurrency::details::_CurrentScheduler
{
};

```

### `Concurrency::details::_Task_ptr<unsigned __int64>`
```
struct __cppobj Concurrency::details::_Task_ptr<unsigned __int64>
{
};

```

### `Concurrency::details::_Task_ptr<unsigned char>`
```
struct __cppobj Concurrency::details::_Task_ptr<unsigned char>
{
};

```

### `Concurrency::details::_ResultHolder<std::vector<bool> >`
```
struct __cppobj Concurrency::details::_ResultHolder<std::vector<bool> >
{
  std::vector<char> _Result;
};

```

### `Concurrency::details::_ReentrantLock`
```
struct __cppobj Concurrency::details::_ReentrantLock
{
  int _M_recursionCount;
  volatile int _M_owner;
};

```

### `Concurrency::details::_ReentrantLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_ReentrantLock::_Scoped_lock
{
  Concurrency::details::_ReentrantLock *_M_lock;
};

```

### `Concurrency::details::_SpinLock`
```
struct __cppobj Concurrency::details::_SpinLock
{
  volatile int *_M_flag;
};

```

### `Concurrency::details::_NormalizeVoidToUnitType<void>`
```
struct __cppobj Concurrency::details::_NormalizeVoidToUnitType<void>
{
};

```

### `Concurrency::details::_TypeSelectorNoAsync`
```
struct __cppobj Concurrency::details::_TypeSelectorNoAsync
{
};

```

### `Concurrency::details::_CONCRT_TRACE_INFO`
```
struct __cppobj __declspec(align(4)) Concurrency::details::_CONCRT_TRACE_INFO
{
  volatile unsigned int EnableFlags;
  volatile unsigned __int8 EnableLevel;
};

```

### `Concurrency::details::_Timer`
```
struct __cppobj __declspec(align(4)) Concurrency::details::_Timer
{
  Concurrency::details::_Timer_vtbl *__vftable /*VFT*/;
  void *_M_hTimer;
  unsigned int _M_ms;
  bool _M_fRepeating;
};

```

### `Concurrency::details::_Timer_vtbl`
```
struct /*VFT*/ Concurrency::details::_Timer_vtbl
{
  void (__fastcall *~_Timer)(Concurrency::details::_Timer *this);
  void (__fastcall *_Fire)(Concurrency::details::_Timer *this);
};

```

### `Concurrency::details::_TaskTypeTraits<void,0>`
```
struct __cppobj Concurrency::details::_TaskTypeTraits<void,0>
{
};

```

### `Concurrency::details::_StructuredTaskCollection`
```
struct __cppobj Concurrency::details::_StructuredTaskCollection : Concurrency::details::_TaskCollectionBase
{
  void *_M_event[1];
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_cef198b90b48c5c98bd59f7c1dcac0b2> >`
```
struct __cppobj __declspec(align(8)) Concurrency::details::_CancellationTokenCallback<<lambda_cef198b90b48c5c98bd59f7c1dcac0b2> > : Concurrency::details::_CancellationTokenRegistration
{
  struct Concurrency::cancellation_token_source::create_linked_source::__l2::<lambda_cef198b90b48c5c98bd59f7c1dcac0b2> _M_function;
  _BYTE gapC0[8];
};

```

### `Concurrency::details::_CancellationTokenCallback<<lambda_cef198b90b48c5c98bd59f7c1dcac0b2> >_vtbl`
```
struct /*VFT*/ Concurrency::details::_CancellationTokenCallback<<lambda_cef198b90b48c5c98bd59f7c1dcac0b2> >_vtbl
{
  void (__fastcall *~_RefCounter)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Destroy)(Concurrency::details::_RefCounter *this);
  void (__fastcall *_Exec)(Concurrency::details::_CancellationTokenRegistration *this);
};

```

### `Concurrency::details::_ReaderWriterLock`
```
struct __cppobj Concurrency::details::_ReaderWriterLock
{
  volatile int _M_state;
  volatile int _M_numberOfWriters;
};

```

### `Concurrency::details::_ReaderWriterLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_ReaderWriterLock::_Scoped_lock
{
  Concurrency::details::_ReaderWriterLock *_M_lock;
};

```

### `Concurrency::details::_ReaderWriterLock::_Scoped_lock_read`
```
struct __cppobj Concurrency::details::_ReaderWriterLock::_Scoped_lock_read
{
  Concurrency::details::_ReaderWriterLock *_M_lock;
};

```

### `Concurrency::details::_BadContinuationParamType`
```
struct __cppobj Concurrency::details::_BadContinuationParamType
{
};

```

### `Concurrency::details::_DefaultTaskHelper`
```
struct __cppobj Concurrency::details::_DefaultTaskHelper
{
};

```

### `Concurrency::details::_NonReentrantPPLLock`
```
struct __cppobj Concurrency::details::_NonReentrantPPLLock
{
  Concurrency::critical_section _M_criticalSection;
};

```

### `Concurrency::details::_NonReentrantPPLLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_NonReentrantPPLLock::_Scoped_lock
{
  Concurrency::details::_NonReentrantPPLLock *_M_lock;
  void *_M_lockNode[5];
};

```

### `Concurrency::details::_StackGuard`
```
struct __cppobj Concurrency::details::_StackGuard
{
  unsigned __int64 *_Depth;
};

```

### `Concurrency::details::_Subatomic_impl<4>`
```
struct __cppobj Concurrency::details::_Subatomic_impl<4>
{
};

```

### `Concurrency::details::_ReentrantBlockingLock`
```
struct __cppobj Concurrency::details::_ReentrantBlockingLock
{
  void *_M_criticalSection[5];
};

```

### `Concurrency::details::_ReentrantBlockingLock::_Scoped_lock`
```
struct __cppobj Concurrency::details::_ReentrantBlockingLock::_Scoped_lock
{
  Concurrency::details::_ReentrantBlockingLock *_M_lock;
};

```

### `Concurrency::details::_Subatomic_impl<8>`
```
struct __cppobj Concurrency::details::_Subatomic_impl<8>
{
};

```

### `Concurrency::details::_TypeSelectorAsyncOperationWithProgress`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncOperationWithProgress
{
};

```

### `Concurrency::details::_ProgressReporterCtorArgType`
```
struct __cppobj Concurrency::details::_ProgressReporterCtorArgType
{
};

```

### `Concurrency::details::_TypeSelectorAsyncOperation`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncOperation : Concurrency::details::_TypeSelectorAsyncOperationOrTask
{
};

```

### `Concurrency::details::_TypeSelectorAsyncActionWithProgress`
```
struct __cppobj Concurrency::details::_TypeSelectorAsyncActionWithProgress
{
};

```

### `Concurrency::improper_scheduler_reference`
```
struct __cppobj Concurrency::improper_scheduler_reference : std::exception
{
};

```

### `Concurrency::improper_scheduler_reference_vtbl`
```
struct /*VFT*/ Concurrency::improper_scheduler_reference_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::auto_partitioner`
```
struct __cppobj Concurrency::auto_partitioner
{
};

```

### `Concurrency::simple_partitioner`
```
struct __cppobj Concurrency::simple_partitioner
{
  unsigned __int64 _M_chunk_size;
};

```

### `Concurrency::task_group`
```
struct __cppobj Concurrency::task_group
{
  Concurrency::details::_TaskCollection _M_task_collection;
};

```

### `Concurrency::CurrentScheduler`
```
struct __cppobj Concurrency::CurrentScheduler
{
};

```

### `Concurrency::_Binary_transform_impl_helper<std::random_access_iterator_tag,std::random_access_iterator_tag,std::random_access_iterator_tag>`
```
struct __cppobj Concurrency::_Binary_transform_impl_helper<std::random_access_iterator_tag,std::random_access_iterator_tag,std::random_access_iterator_tag>
{
};

```

### `Concurrency::_Init_func_transformer<void>`
```
struct __cppobj Concurrency::_Init_func_transformer<void>
{
};

```

### `Concurrency::_Continuation_func_transformer<void,void>`
```
struct __cppobj Concurrency::_Continuation_func_transformer<void,void>
{
};

```

### `Concurrency::bad_target`
```
struct __cppobj Concurrency::bad_target : std::exception
{
};

```

### `Concurrency::bad_target_vtbl`
```
struct /*VFT*/ Concurrency::bad_target_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::invalid_oversubscribe_operation`
```
struct __cppobj Concurrency::invalid_oversubscribe_operation : std::exception
{
};

```

### `Concurrency::invalid_oversubscribe_operation_vtbl`
```
struct /*VFT*/ Concurrency::invalid_oversubscribe_operation_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::task<unsigned __int64>`
```
struct __cppobj Concurrency::task<unsigned __int64>
{
  std::shared_ptr<Concurrency::details::_Task_impl<unsigned __int64> > _M_Impl;
};

```

### `Concurrency::unsupported_os`
```
struct __cppobj Concurrency::unsupported_os : std::exception
{
};

```

### `Concurrency::unsupported_os_vtbl`
```
struct /*VFT*/ Concurrency::unsupported_os_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::scheduler_not_attached`
```
struct __cppobj Concurrency::scheduler_not_attached : std::exception
{
};

```

### `Concurrency::scheduler_not_attached_vtbl`
```
struct /*VFT*/ Concurrency::scheduler_not_attached_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::invalid_link_target`
```
struct __cppobj Concurrency::invalid_link_target : std::exception
{
};

```

### `Concurrency::invalid_link_target_vtbl`
```
struct /*VFT*/ Concurrency::invalid_link_target_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::cancellation_token_registration`
```
struct __cppobj Concurrency::cancellation_token_registration
{
  Concurrency::details::_CancellationTokenRegistration *_M_pRegistration;
};

```

### `Concurrency::invalid_scheduler_policy_thread_specification`
```
struct __cppobj Concurrency::invalid_scheduler_policy_thread_specification : std::exception
{
};

```

### `Concurrency::invalid_scheduler_policy_thread_specification_vtbl`
```
struct /*VFT*/ Concurrency::invalid_scheduler_policy_thread_specification_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::cancellation_token_source`
```
struct __cppobj Concurrency::cancellation_token_source
{
  Concurrency::details::_CancellationTokenState *_M_Impl;
};

```

### `Concurrency::structured_task_group`
```
struct __cppobj Concurrency::structured_task_group
{
  Concurrency::details::_StructuredTaskCollection _M_task_collection;
};

```

### `Concurrency::invalid_multiple_scheduling`
```
struct __cppobj Concurrency::invalid_multiple_scheduling : std::exception
{
};

```

### `Concurrency::invalid_multiple_scheduling_vtbl`
```
struct /*VFT*/ Concurrency::invalid_multiple_scheduling_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::static_partitioner`
```
struct __cppobj Concurrency::static_partitioner
{
};

```

### `Concurrency::task<unsigned char>`
```
struct __cppobj Concurrency::task<unsigned char>
{
  std::shared_ptr<Concurrency::details::_Task_impl<unsigned char> > _M_Impl;
};

```

### `Concurrency::task<void>`
```
struct __cppobj Concurrency::task<void>
{
  Concurrency::task<unsigned char> _M_unitTask;
};

```

### `Concurrency::task_completion_event<void>`
```
struct __cppobj Concurrency::task_completion_event<void>
{
  Concurrency::task_completion_event<unsigned char> _M_unitEvent;
};

```

### `Concurrency::operation_timed_out`
```
struct __cppobj Concurrency::operation_timed_out : std::exception
{
};

```

### `Concurrency::operation_timed_out_vtbl`
```
struct /*VFT*/ Concurrency::operation_timed_out_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::invalid_scheduler_policy_value`
```
struct __cppobj Concurrency::invalid_scheduler_policy_value : std::exception
{
};

```

### `Concurrency::invalid_scheduler_policy_value_vtbl`
```
struct /*VFT*/ Concurrency::invalid_scheduler_policy_value_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::task_canceled`
```
struct __cppobj Concurrency::task_canceled : std::exception
{
};

```

### `Concurrency::task_canceled_vtbl`
```
struct /*VFT*/ Concurrency::task_canceled_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::context_self_unblock`
```
struct __cppobj Concurrency::context_self_unblock : std::exception
{
};

```

### `Concurrency::context_self_unblock_vtbl`
```
struct /*VFT*/ Concurrency::context_self_unblock_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::nested_scheduler_missing_detach`
```
struct __cppobj Concurrency::nested_scheduler_missing_detach : std::exception
{
};

```

### `Concurrency::nested_scheduler_missing_detach_vtbl`
```
struct /*VFT*/ Concurrency::nested_scheduler_missing_detach_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::missing_wait`
```
struct __cppobj Concurrency::missing_wait : std::exception
{
};

```

### `Concurrency::missing_wait_vtbl`
```
struct /*VFT*/ Concurrency::missing_wait_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::task_continuation_context::_Tag`
```
struct __cppobj Concurrency::task_continuation_context::_Tag
{
};

```

### `Concurrency::invalid_scheduler_policy_key`
```
struct __cppobj Concurrency::invalid_scheduler_policy_key : std::exception
{
};

```

### `Concurrency::invalid_scheduler_policy_key_vtbl`
```
struct /*VFT*/ Concurrency::invalid_scheduler_policy_key_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::_Unary_transform_impl_helper<std::random_access_iterator_tag,std::random_access_iterator_tag>`
```
struct __cppobj Concurrency::_Unary_transform_impl_helper<std::random_access_iterator_tag,std::random_access_iterator_tag>
{
};

```

### `Concurrency::improper_lock`
```
struct __cppobj Concurrency::improper_lock : std::exception
{
};

```

### `Concurrency::improper_lock_vtbl`
```
struct /*VFT*/ Concurrency::improper_lock_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::default_scheduler_exists`
```
struct __cppobj Concurrency::default_scheduler_exists : std::exception
{
};

```

### `Concurrency::default_scheduler_exists_vtbl`
```
struct /*VFT*/ Concurrency::default_scheduler_exists_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::improper_scheduler_attach`
```
struct __cppobj Concurrency::improper_scheduler_attach : std::exception
{
};

```

### `Concurrency::improper_scheduler_attach_vtbl`
```
struct /*VFT*/ Concurrency::improper_scheduler_attach_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::context_unblock_unbalanced`
```
struct __cppobj Concurrency::context_unblock_unbalanced : std::exception
{
};

```

### `Concurrency::context_unblock_unbalanced_vtbl`
```
struct /*VFT*/ Concurrency::context_unblock_unbalanced_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::improper_scheduler_detach`
```
struct __cppobj Concurrency::improper_scheduler_detach : std::exception
{
};

```

### `Concurrency::improper_scheduler_detach_vtbl`
```
struct /*VFT*/ Concurrency::improper_scheduler_detach_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::reader_writer_lock`
```
struct __cppobj __declspec(align(8)) Concurrency::reader_writer_lock
{
  void *_M_activeWriter[5];
  void *_M_pReaderHead;
  void *_M_pWriterHead;
  void *_M_pWriterTail;
  volatile int _M_lockState;
};

```

### `Concurrency::reader_writer_lock::scoped_lock`
```
struct __cppobj Concurrency::reader_writer_lock::scoped_lock
{
  Concurrency::reader_writer_lock *_M_reader_writer_lock;
  void *_M_writerNode[5];
};

```

### `Concurrency::reader_writer_lock::scoped_lock_read`
```
struct __cppobj Concurrency::reader_writer_lock::scoped_lock_read
{
  Concurrency::reader_writer_lock *_M_reader_writer_lock;
};

```

### `Concurrency::invalid_operation_vtbl`
```
struct /*VFT*/ Concurrency::invalid_operation_vtbl
{
  void (__fastcall *~exception)(std::exception *this);
  const char *(__fastcall *what)(std::exception *this);
};

```

### `Concurrency::affinity_partitioner`
```
struct __cppobj Concurrency::affinity_partitioner
{
  unsigned int _M_num_chunks;
  Concurrency::location *_M_pChunk_locations;
};

```

### `Concurrency::details::_Task_impl<unsigned char>::_CancelAndRunContinuations::__l34::<lambda_763529b0c7473cbc215a52d189ac9b18>`
```
struct __cppobj Concurrency::details::_Task_impl<unsigned char>::_CancelAndRunContinuations::__l34::<lambda_763529b0c7473cbc215a52d189ac9b18>
{
  Concurrency::details::_Task_impl<unsigned char> *const __this;
};

```

### `Concurrency::details::_Task_impl_base::_ScheduleContinuationTask::__l5::<lambda_713ee8bbd6b08550d59c52695cab5ce3>`
```
struct __cppobj Concurrency::details::_Task_impl_base::_ScheduleContinuationTask::__l5::<lambda_713ee8bbd6b08550d59c52695cab5ce3>
{
  Concurrency::details::_ContinuationTaskHandleBase *_PTaskHandle;
};

```

### `Concurrency::details::_GetStaticAmbientSchedulerRef::__l2::<lambda_0e64988457575224279dcb6d61e61bdd>`
```
struct __cppobj Concurrency::details::_GetStaticAmbientSchedulerRef::__l2::<lambda_0e64988457575224279dcb6d61e61bdd>
{
};

```

### `CM_Power_Data_s`
```
struct CM_Power_Data_s
{
  unsigned int PD_Size;
  _DEVICE_POWER_STATE PD_MostRecentPowerState;
  unsigned int PD_Capabilities;
  unsigned int PD_D1Latency;
  unsigned int PD_D2Latency;
  unsigned int PD_D3Latency;
  _DEVICE_POWER_STATE PD_PowerStateMapping[7];
  _SYSTEM_POWER_STATE PD_DeepestSystemWake;
};

```

### `CompileTime::Hash64<0>`
```
struct __cppobj CompileTime::Hash64<0>
{
};

```

### `CompileTime::Hash<0>`
```
struct __cppobj CompileTime::Hash<0>
{
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_ChunkStarted>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_ChunkStarted>
{
  unsigned int dwStreamNumber;
  unsigned int dwReserved;
  void *hSourceFile;
  void *hDestinationFile;
  _ULARGE_INTEGER uliChunkNumber;
  _ULARGE_INTEGER uliChunkSize;
  _ULARGE_INTEGER uliStreamSize;
  _ULARGE_INTEGER uliTotalFileSize;
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_ChunkFinished>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_ChunkFinished>
{
  unsigned int dwStreamNumber;
  unsigned int dwFlags;
  void *hSourceFile;
  void *hDestinationFile;
  _ULARGE_INTEGER uliChunkNumber;
  _ULARGE_INTEGER uliChunkSize;
  _ULARGE_INTEGER uliStreamSize;
  _ULARGE_INTEGER uliStreamBytesTransferred;
  _ULARGE_INTEGER uliTotalFileSize;
  _ULARGE_INTEGER uliTotalBytesTransferred;
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_StreamStarted>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_StreamStarted>
{
  unsigned int dwStreamNumber;
  unsigned int dwReserved;
  void *hSourceFile;
  void *hDestinationFile;
  _ULARGE_INTEGER uliStreamSize;
  _ULARGE_INTEGER uliTotalFileSize;
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_StreamFinished>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_StreamFinished>
{
  unsigned int dwStreamNumber;
  unsigned int dwReserved;
  void *hSourceFile;
  void *hDestinationFile;
  _ULARGE_INTEGER uliStreamSize;
  _ULARGE_INTEGER uliStreamBytesTransferred;
  _ULARGE_INTEGER uliTotalFileSize;
  _ULARGE_INTEGER uliTotalBytesTransferred;
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_PollContinue>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_PollContinue>
{
  unsigned int dwReserved;
};

```

### `COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_Error>`
```
struct COPYFILE2_MESSAGE::<unnamed_type_Info>::<unnamed_type_Error>
{
  _COPYFILE2_COPY_PHASE CopyPhase;
  unsigned int dwStreamNumber;
  HRESULT hrFailure;
  unsigned int dwReserved;
  _ULARGE_INTEGER uliChunkNumber;
  _ULARGE_INTEGER uliStreamSize;
  _ULARGE_INTEGER uliStreamBytesTransferred;
  _ULARGE_INTEGER uliTotalFileSize;
  _ULARGE_INTEGER uliTotalBytesTransferred;
};

```

### `COPYFILE2_MESSAGE`
```
struct COPYFILE2_MESSAGE
{
  _COPYFILE2_MESSAGE_TYPE Type;
  unsigned int dwPadding;
  COPYFILE2_MESSAGE::<unnamed_type_Info> Info;
};

```

### `COPYFILE2_EXTENDED_PARAMETERS`
```
struct COPYFILE2_EXTENDED_PARAMETERS
{
  unsigned int dwSize;
  unsigned int dwCopyFlags;
  int *pfCancel;
  _COPYFILE2_MESSAGE_ACTION (__fastcall *pProgressRoutine)(const COPYFILE2_MESSAGE *, void *);
  void *pvCallbackContext;
};

```

### `CONFIRMSAFETY`
```
struct __declspec(align(8)) CONFIRMSAFETY
{
  _GUID clsid;
  IUnknown *pUnk;
  unsigned int dwFlags;
};

```

### `cg::TextureSetLayerImageMipList`
```
struct __cppobj cg::TextureSetLayerImageMipList
{
  cg::TextureSetLayerType mLayerType;
  std::vector<cg::ImageBuffer> mImageList;
};

```

### `cg::TextureSetImageContainer`
```
struct __cppobj cg::TextureSetImageContainer : Bedrock::EnableNonOwnerReferences
{
  std::vector<cg::TextureSetLayerImageMipList> mLayerImageList;
};

```

### `cg::TextureSetDefinition`
```
struct __cppobj cg::TextureSetDefinition
{
  std::vector<cg::TextureSetLayerDefinition> mLayerInfoList;
  bool mIsMissingTexture;
  std::shared_ptr<cg::TextureSetImageContainer> mTextureSetImageData;
  ResourceLocationPair mResourceLocationPair;
};

```

### `cg::CacheLocation`
```
struct __cppobj __declspec(align(8)) cg::CacheLocation
{
  Core::PathBuffer<std::string > mPath;
  _BYTE mOrigin[1];
};

```

### `Core::FileSystem`
```
struct __cppobj Core::FileSystem
{
};

```

### `Core::FileSystem::BasicFileData`
```
struct __cppobj Core::FileSystem::BasicFileData
{
  Core::PathBuffer<std::string > mPath;
  unsigned __int64 mSize;
};

```

### `Core::FileSystem::FileTransferProgress`
```
struct __cppobj Core::FileSystem::FileTransferProgress
{
  unsigned __int64 mStartPosition;
  unsigned __int64 mBytesWritten;
  unsigned __int64 mBytesRemaining;
};

```

### `CameraBehavior<AttachBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<AttachBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<AttachBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<AttachBehavior>_vtbl
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

### `CameraBehavior<AvoidanceBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<AvoidanceBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<AvoidanceBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<AvoidanceBehavior>_vtbl
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

### `CriticallyDampedSpring<float>`
```
struct __cppobj CriticallyDampedSpring<float>
{
  float mSpring;
};

```

### `CameraBehavior<OrbitBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<OrbitBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<OrbitBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<OrbitBehavior>_vtbl
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

### `CameraBehavior<BobBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<BobBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<BobBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<BobBehavior>_vtbl
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

### `CameraBehavior<FirstPersonLookBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<FirstPersonLookBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<FirstPersonLookBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<FirstPersonLookBehavior>_vtbl
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

### `CameraBehavior<RideRotationBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<RideRotationBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<RideRotationBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<RideRotationBehavior>_vtbl
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

### `CameraBehavior<FlyBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<FlyBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<FlyBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<FlyBehavior>_vtbl
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

### `CameraBehavior<LiquidOffsetBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<LiquidOffsetBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<LiquidOffsetBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<LiquidOffsetBehavior>_vtbl
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

### `CameraBehavior<LookAtBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<LookAtBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<LookAtBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<LookAtBehavior>_vtbl
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

### `CameraBehavior<PortalBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<PortalBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<PortalBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<PortalBehavior>_vtbl
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

### `CameraBehavior<SleepBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<SleepBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<SleepBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<SleepBehavior>_vtbl
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

### `CameraBehavior<SneakBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<SneakBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<SneakBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<SneakBehavior>_vtbl
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

### `Core::PathContainerConversions<Core::StackString<char,1024> >`
```
struct __cppobj Core::PathContainerConversions<Core::StackString<char,1024> >
{
};

```

### `CameraBehavior<SplineBehavior>`
```
struct __cppobj __declspec(align(8)) CameraBehavior<SplineBehavior> : ICameraBehavior
{
  ICameraBehavior::UpdateOrder mUpdateOrder;
};

```

### `CameraBehavior<SplineBehavior>_vtbl`
```
struct /*VFT*/ CameraBehavior<SplineBehavior>_vtbl
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

### `CriticallyDampedSpring<Vec3>`
```
struct __cppobj CriticallyDampedSpring<Vec3>
{
  float mSpring;
};

```

### `CatmullRomSpline`
```
struct __cppobj __declspec(align(8)) CatmullRomSpline
{
  std::vector<Vec3> mControlPoints;
  std::vector<float> mAccumulatedSegmentLengths;
  bool mLooped;
};

```

### `CameraLoader::parseCameras::__l2::<lambda_39f3f306e576c66b261bbdd8909b2247>`
```
struct __cppobj CameraLoader::parseCameras::__l2::<lambda_39f3f306e576c66b261bbdd8909b2247>
{
  CameraLoader *const __this;
  std::unordered_map<HashedString,CameraDirector> *loadedCameras;
  std::unordered_map<HashedString,CameraDirector> *newCameraMap;
};

```

### `CameraLoader::parseBlends::__l2::<lambda_c6a4c0e67c1895cce63e1cdd7ae7d3c3>`
```
struct __cppobj CameraLoader::parseBlends::__l2::<lambda_c6a4c0e67c1895cce63e1cdd7ae7d3c3>
{
  CameraLoader *const __this;
  std::unordered_map<HashedString,CameraDirector> *loadedCameras;
  std::unordered_map<std::pair<HashedString,HashedString>,CameraBlendSettings,CameraPairHasher,std::equal_to<std::pair<HashedString,HashedString> >,std::allocator<std::pair<std::pair<HashedString,HashedString> const ,CameraBlendSettings> > > *customBlendMap;
};

```

### `CommandContext`
```
struct __cppobj __declspec(align(8)) CommandContext
{
  std::string mCommand;
  std::unique_ptr<CommandOrigin> mOrigin;
  int mVersion;
};

```

### `ClientCommand`
```
struct __cppobj ClientCommand : Command
{
};

```

### `ClientCommand_vtbl`
```
struct /*VFT*/ ClientCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ClientCommandOutputSender`
```
struct __cppobj ClientCommandOutputSender : CommandOutputSender
{
  GuiData *mMachineGuiData;
};

```

### `ClientCommandOutputSender_vtbl`
```
struct /*VFT*/ ClientCommandOutputSender_vtbl
{
  void (__fastcall *~CommandOutputSender)(CommandOutputSender *this);
  void (__fastcall *send)(CommandOutputSender *this, const CommandOrigin *, const CommandOutput *);
  void (__fastcall *registerOutputCallback)(CommandOutputSender *this, const std::function<void __cdecl(AutomationCmdOutput &)> *);
};

```

### `CommandSelector<Actor>`
```
struct __cppobj CommandSelector<Actor> : CommandSelectorBase
{
};

```

### `CommandRegistry::SemanticInfo`
```
struct __cppobj CommandRegistry::SemanticInfo
{
  bool mIsValid;
  std::vector<CommandRegistry::Symbol> mConstrainedParams;
  std::string mSoftEnumText;
  std::string mSoftEnumEscapeCharExceptions;
  std::set<CommandRegistry::Symbol> mAlreadyCompletedSymbols;
};

```

### `commands::Postfix`
```
struct __cppobj commands::Postfix
{
  const char *postfix;
};

```

### `commands::SoftEnum`
```
struct __cppobj commands::SoftEnum
{
  const char *name;
};

```

### `CloseWebSocketCommand`
```
struct __cppobj CloseWebSocketCommand : Command
{
};

```

### `CloseWebSocketCommand_vtbl`
```
struct /*VFT*/ CloseWebSocketCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `CloseChatCommand`
```
struct __cppobj CloseChatCommand : Command
{
};

```

### `CloseChatCommand_vtbl`
```
struct /*VFT*/ CloseChatCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `ClientCommandOutputSender::send::__l20::<lambda_0b751b1533f17cdbef71e6a6deb7f9bd>`
```
struct __cppobj ClientCommandOutputSender::send::__l20::<lambda_0b751b1533f17cdbef71e6a6deb7f9bd>
{
  const CommandOutputMessage *message;
};

```

### `ClientSkinInfoData_vtbl`
```
struct /*VFT*/ ClientSkinInfoData_vtbl
{
  void (__fastcall *~SkinInfoData)(SkinInfoData *this);
  void (__fastcall *updateSkin)(SkinInfoData *this, const SerializedSkin *, const mce::Image *, const mce::Image *);
  void (__fastcall *updateSkinNe)(SkinInfoData *this, const SerializedSkin *, const mce::Image *, const mce::Image *, const mce::Image *);
  bool (__fastcall *hasValidTexture)(SkinInfoData *this);
  bool (__fastcall *validateAndResizeSkinData)(SkinInfoData *this, mce::Image *, bool);
};

```

### `ClientSkinSystem`
```
struct __cppobj ClientSkinSystem
{
};

```

### `ClientParticleTerminationComponent`
```
struct __cppobj ClientParticleTerminationComponent : IEntityComponent
{
  HashedString mAnimationControllerName;
};

```

### `CallbackTokenContext<std::function<void __cdecl(void)> >`
```
struct __cppobj CallbackTokenContext<std::function<void __cdecl(void)> >
{
  std::vector<std::function<void __cdecl(void)>> mCallbacks;
  std::shared_ptr<CallbackTokenCancelState> mCancelState;
};

```

### `ContainerComponent_vtbl`
```
struct /*VFT*/ ContainerComponent_vtbl
{
  void (__fastcall *containerContentChanged)(ContainerContentChangeListener *this, int);
  void (__fastcall *~ContainerContentChangeListener)(ContainerContentChangeListener *this);
  void (__fastcall *containerAddCallback)(ContainerContentChangeListener *this, Container *);
  void (__fastcall *containerRemoveCallback)(ContainerContentChangeListener *this, Container *);
};

```

### `CDScopedGameplay`
```
struct __cppobj CDScopedGameplay
{
  _BYTE mFunc[2];
  _BYTE mTagEnd[2];
  int mClientId;
  int mBuildActionIntention;
};

```

### `CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> >`
```
struct __cppobj CallbackTokenContext<std::function<void __cdecl(enum Legacy::RetrieveStatus)> >
{
  std::vector<std::function<void __cdecl(enum Legacy::RetrieveStatus)>> mCallbacks;
  std::shared_ptr<CallbackTokenCancelState> mCancelState;
};

```

### `CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> >`
```
struct __cppobj CallbackTokenContext<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)> >
{
  std::vector<std::function<void __cdecl(enum Legacy::ImportStatus,float,std::shared_ptr<ImportResult>)>> mCallbacks;
  std::shared_ptr<CallbackTokenCancelState> mCancelState;
};

```

### `ChaCha`
```
struct __cppobj ChaCha
{
  unsigned int m_state[16];
  unsigned int m_mask[16];
  unsigned int m_off;
  unsigned int m_rnd;
};

```

### `CrashDumpLogUtils`
```
struct __cppobj CrashDumpLogUtils
{
};

```

### `CrashDumpLog`
```
struct __cppobj CrashDumpLog
{
};

```

### `CompositeSceneStackView`
```
struct __cppobj CompositeSceneStackView
{
  SceneStack *mMainStack;
  SceneStack *mClientInstanceStack;
  ConstCompositeSceneStackView mConstView;
};

```

### `ClientInstance::_onScreenSizeVariablesChanged::__l2::<lambda_90393c59d32660745f34e36629dc4206>`
```
struct __cppobj ClientInstance::_onScreenSizeVariablesChanged::__l2::<lambda_90393c59d32660745f34e36629dc4206>
{
  const ScreenSizeData *screenSizeData;
};

```

### `ClientInstance::updateControllerHandling::__l11::<lambda_15b5620979f052f9384ec29576b39029>`
```
struct __cppobj ClientInstance::updateControllerHandling::__l11::<lambda_15b5620979f052f9384ec29576b39029>
{
  std::weak_ptr<ClientInstance> weakPtr;
};

```

### `ClientInstance::tickDestroyBlock::__l11::<lambda_df7287ab01c6507a213cfdfd14b9340d>`
```
struct __cppobj ClientInstance::tickDestroyBlock::__l11::<lambda_df7287ab01c6507a213cfdfd14b9340d>
{
  const BlockPos *hitPos;
  const unsigned __int8 hitFace;
  ClientInstance::ClientDestroyBlockState *state;
};

```

### `ClientInstance::navigateToStoreSeeAllByCreatorScreen::__l2::<lambda_15d8531333f726aeede88a06a28b4fd0>::()::__l22::<lambda_3f6c191c869f81aace7d27ad31821f7d>`
```
struct __cppobj ClientInstance::navigateToStoreSeeAllByCreatorScreen::__l2::<lambda_15d8531333f726aeede88a06a28b4fd0>::()::__l22::<lambda_3f6c191c869f81aace7d27ad31821f7d>
{
  std::shared_ptr<ClientInstance> sharedThis;
};

```

### `ClientInstance::_initSceneStack::__l2::<lambda_97650e0fd8d8e2d4ab764eb737bc7498>`
```
struct __cppobj ClientInstance::_initSceneStack::__l2::<lambda_97650e0fd8d8e2d4ab764eb737bc7498>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::_initSceneStack::__l2::<lambda_582f79c63c5d93588b6a0221f4853e8c>`
```
struct __cppobj ClientInstance::_initSceneStack::__l2::<lambda_582f79c63c5d93588b6a0221f4853e8c>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::_initSceneStack::__l2::<lambda_878ba9a1bc34c18f3fb6c7370a888ee2>`
```
struct __cppobj ClientInstance::_initSceneStack::__l2::<lambda_878ba9a1bc34c18f3fb6c7370a888ee2>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::_initSceneStack::__l2::<lambda_878ba9a1bc34c18f3fb6c7370a888ee2>::()::__l2::<lambda_193b3faf9447328a85dac550e43be45e>`
```
struct __cppobj ClientInstance::_initSceneStack::__l2::<lambda_878ba9a1bc34c18f3fb6c7370a888ee2>::()::__l2::<lambda_193b3faf9447328a85dac550e43be45e>
{
  std::string *currentNamespace;
  AbstractScene *screen;
};

```

### `ClientInstance::_initSceneStack::__l2::<lambda_299ba7fd9fe4ee5b945befbd386be495>`
```
struct __cppobj ClientInstance::_initSceneStack::__l2::<lambda_299ba7fd9fe4ee5b945befbd386be495>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::_createSkinRepositoryClientInterface::__l5::<lambda_1214f5056699946a17be2ec6b86b5a63>`
```
struct __cppobj ClientInstance::_createSkinRepositoryClientInterface::__l5::<lambda_1214f5056699946a17be2ec6b86b5a63>
{
  std::weak_ptr<ClientInstance> weakThis;
};

```

### `ClientInstance::isShowingMenu::__l2::<lambda_cfd341f57ab31a2ca42b1aefca30254a>`
```
struct __cppobj ClientInstance::isShowingMenu::__l2::<lambda_cfd341f57ab31a2ca42b1aefca30254a>
{
  bool *showingMenu;
};

```

### `ClientInstance::initCommands::__l2::<lambda_bb361151b842928025ac08534ab16337>`
```
struct __cppobj ClientInstance::initCommands::__l2::<lambda_bb361151b842928025ac08534ab16337>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::onTick::__l38::<lambda_71b0399f4662fd076d571faae3370350>`
```
struct __cppobj ClientInstance::onTick::__l38::<lambda_71b0399f4662fd076d571faae3370350>
{
  int *nTick;
  int *maxTick;
};

```

### `ClientInstance::_joinWorldInProgress::__l2::<lambda_02e2605fd0c5e1a6375f3072765e8e5a>`
```
struct __cppobj __declspec(align(8)) ClientInstance::_joinWorldInProgress::__l2::<lambda_02e2605fd0c5e1a6375f3072765e8e5a>
{
  std::weak_ptr<ClientInstance> weakThis;
  bool isNetworkGame;
};

```

### `ClientInstance::_joinWorldInProgress::__l11::<lambda_abecbc1c0e8dcdce57775fbf971d4035>`
```
struct __cppobj ClientInstance::_joinWorldInProgress::__l11::<lambda_abecbc1c0e8dcdce57775fbf971d4035>
{
};

```

### `ClientInstance::startSubClientLateJoin::__l13::<lambda_b51ae057fc840348fcf61fa2148e38c6>`
```
struct __cppobj __declspec(align(8)) ClientInstance::startSubClientLateJoin::__l13::<lambda_b51ae057fc840348fcf61fa2148e38c6>
{
  ClientInstance *const __this;
  bool isNetworkGame;
};

```

### `ClientInstance::update::__l42::<lambda_2eadb951cae52f74e068bad3dd7fa7f4>::()::__l14::<lambda_702502096d39b6c5ea025d728e798aee>`
```
struct __cppobj ClientInstance::update::__l42::<lambda_2eadb951cae52f74e068bad3dd7fa7f4>::()::__l14::<lambda_702502096d39b6c5ea025d728e798aee>
{
  std::weak_ptr<ClientInstance> weakPtr;
};

```

### `ClientInstance::_startLeaveGame::__l2::<lambda_2b74ebf9d9d48a05c165bbb31d30842e>`
```
struct __cppobj ClientInstance::_startLeaveGame::__l2::<lambda_2b74ebf9d9d48a05c165bbb31d30842e>
{
};

```

### `ClientInstance::requestLeaveGame::__l2::<lambda_4bc0650f4f0405926a0a487036642fde>`
```
struct __cppobj __declspec(align(8)) ClientInstance::requestLeaveGame::__l2::<lambda_4bc0650f4f0405926a0a487036642fde>
{
  std::weak_ptr<ClientInstance> weakThis;
  bool switchScreen;
  bool sync;
};

```

### `ClientInstance::init::__l2::<lambda_a36354b83242328e7f1f5c5935e0ecaa>`
```
struct __cppobj ClientInstance::init::__l2::<lambda_a36354b83242328e7f1f5c5935e0ecaa>
{
  std::weak_ptr<ClientInstance> weakThis;
};

```

### `ClientInstance::init::__l2::<lambda_7d463a3c887b82eef60c5bc398d58571>`
```
struct __cppobj ClientInstance::init::__l2::<lambda_7d463a3c887b82eef60c5bc398d58571>
{
  std::weak_ptr<ClientInstance> weakThis;
};

```

### `ClientInstance::init::__l2::<lambda_2dbee955e45009a41bd19a4f5d977b90>`
```
struct __cppobj ClientInstance::init::__l2::<lambda_2dbee955e45009a41bd19a4f5d977b90>
{
  ClientInstance *const __this;
};

```

### `ClientInputCallbacks::vibrate::__l13::<lambda_abfe2ccf6929051526d977f1e506ac3d>`
```
struct __cppobj ClientInputCallbacks::vibrate::__l13::<lambda_abfe2ccf6929051526d977f1e506ac3d>
{
  int milliSeconds;
};

```

### `ClientInputCallbacks::handleCommandEvent::__l2::<lambda_3ca896b064936e0c3219171a0fd62bea>`
```
struct __cppobj ClientInputCallbacks::handleCommandEvent::__l2::<lambda_3ca896b064936e0c3219171a0fd62bea>
{
  const VoiceCommand *command;
};

```

### `ClientInputCallbacks::handleDictationEvent::__l8::<lambda_e6fd729911e6f890df89f1279cd76373>`
```
struct __cppobj ClientInputCallbacks::handleDictationEvent::__l8::<lambda_e6fd729911e6f890df89f1279cd76373>
{
  const std::string *newDictationStr;
};

```

### `ClientInputCallbacks::handleVectorInput::__l4::<lambda_0f0def3c3c1a653163fbf9c1bccfcf88>`
```
struct __cppobj ClientInputCallbacks::handleVectorInput::__l4::<lambda_0f0def3c3c1a653163fbf9c1bccfcf88>
{
  __int16 *id;
  float *x;
  float *y;
  float *z;
  FocusImpact *focusImpact;
};

```

### `ClientInputCallbacks::handleHoloInputModeChanged::__l2::<lambda_e79dccabe9c15a9b64dbdfbab7317d1d>`
```
struct __cppobj ClientInputCallbacks::handleHoloInputModeChanged::__l2::<lambda_e79dccabe9c15a9b64dbdfbab7317d1d>
{
  HoloUIInputMode *inputMode;
};

```

### `ClientInputCallbacks::handleInputModeChanged::__l2::<lambda_86c8143899b89eccea3596158e019ff1>`
```
struct __cppobj ClientInputCallbacks::handleInputModeChanged::__l2::<lambda_86c8143899b89eccea3596158e019ff1>
{
  InputMode *inputMode;
};

```

### `ClientInputCallbacks::handleDirection::__l2::<lambda_1ca73074d044029f1123f1b8e204c386>`
```
struct __cppobj ClientInputCallbacks::handleDirection::__l2::<lambda_1ca73074d044029f1123f1b8e204c386>
{
  DirectionId *stickId;
  float *x;
  float *y;
  FocusImpact *focusImpact;
};

```

### `ClientInputCallbacks::handlePointerLocation::__l5::<lambda_585dae7b1422f8853e1863f4bcfab0ab>`
```
struct __cppobj ClientInputCallbacks::handlePointerLocation::__l5::<lambda_585dae7b1422f8853e1863f4bcfab0ab>
{
  const PointerLocationEventData *pointerLocationData;
  FocusImpact *focusImpact;
};

```

### `ClientInputCallbacks::handleMenuButtonRelease::__l2::<lambda_d0e4742031c76c6b90374d00cc4059a8>`
```
struct __cppobj ClientInputCallbacks::handleMenuButtonRelease::__l2::<lambda_d0e4742031c76c6b90374d00cc4059a8>
{
  unsigned int *buttonId;
  FocusImpact *focusImpact;
};

```

### `ClientInputCallbacks::handlePointerPressedButtonRelease::__l2::<lambda_39242d26cf3982dde303d99c138d7fea>`
```
struct __cppobj ClientInputCallbacks::handlePointerPressedButtonRelease::__l2::<lambda_39242d26cf3982dde303d99c138d7fea>
{
};

```

### `ClientInputCallbacks::handleMenuButtonPress::__l2::<lambda_21d7273568769b2a2e8a145779122fe2>`
```
struct __cppobj ClientInputCallbacks::handleMenuButtonPress::__l2::<lambda_21d7273568769b2a2e8a145779122fe2>
{
  unsigned int *buttonId;
  FocusImpact *focusImpact;
};

```

### `ClientInputCallbacks::handleBuildOrAttackButtonPress::__l2::<lambda_da56761cda2d44f41691415c5db47201>`
```
struct __cppobj ClientInputCallbacks::handleBuildOrAttackButtonPress::__l2::<lambda_da56761cda2d44f41691415c5db47201>
{
};

```

### `ClientInputCallbacks::handleDestroyOrInteractButtonPress::__l2::<lambda_30eab25553a0289c6a2e647a94663f5c>`
```
struct __cppobj ClientInputCallbacks::handleDestroyOrInteractButtonPress::__l2::<lambda_30eab25553a0289c6a2e647a94663f5c>
{
};

```

### `ClientInputCallbacks::handleBuildOrInteractButtonPress::__l2::<lambda_549184ca211057ee986f55f9691f0b5d>`
```
struct __cppobj ClientInputCallbacks::handleBuildOrInteractButtonPress::__l2::<lambda_549184ca211057ee986f55f9691f0b5d>
{
};

```

### `ClientInputCallbacks::handleBuildOrInteractButtonPress::__l5::<lambda_99d95ad1f219b828a438795fbbae0add>`
```
struct __cppobj ClientInputCallbacks::handleBuildOrInteractButtonPress::__l5::<lambda_99d95ad1f219b828a438795fbbae0add>
{
};

```

### `ClientInputCallbacks::handleDestoryOrAttackButtonPress::__l2::<lambda_a250f32d2aec155df20b3e6b1bd71989>`
```
struct __cppobj ClientInputCallbacks::handleDestoryOrAttackButtonPress::__l2::<lambda_a250f32d2aec155df20b3e6b1bd71989>
{
};

```

### `ClientInputCallbacks::handleDestoryOrAttackButtonPress::__l5::<lambda_1768354503fc5fcd1469a64b30f27d5c>`
```
struct __cppobj ClientInputCallbacks::handleDestoryOrAttackButtonPress::__l5::<lambda_1768354503fc5fcd1469a64b30f27d5c>
{
};

```

### `ClientInputCallbacks::handleScreenshotPress::__l8::<lambda_e70b5943a0b1cecdb66c029e8c0cbe0e>`
```
struct __cppobj ClientInputCallbacks::handleScreenshotPress::__l8::<lambda_e70b5943a0b1cecdb66c029e8c0cbe0e>
{
  std::string filePath;
  IClientInstance *client;
};

```

### `ClientInputCallbacks::handleGoToReportCheatButtonPress::__l8::<lambda_82f858da70d941e940912bb30990deca>`
```
struct __cppobj ClientInputCallbacks::handleGoToReportCheatButtonPress::__l8::<lambda_82f858da70d941e940912bb30990deca>
{
  std::string filePath;
  IClientInstance *client;
};

```

### `ClientInputCallbacks::handlePointerPressedButtonPress::__l2::<lambda_ed584832a847dcbeef5b61997314db23>`
```
struct __cppobj ClientInputCallbacks::handlePointerPressedButtonPress::__l2::<lambda_ed584832a847dcbeef5b61997314db23>
{
};

```

### `ClientSkinSystem::_updateClientSkin::__l2::<lambda_3edaec2b809ed40c0096426422f09c9f>`
```
struct __cppobj ClientSkinSystem::_updateClientSkin::__l2::<lambda_3edaec2b809ed40c0096426422f09c9f>
{
  std::weak_ptr<IClientInstance> weakClient;
  const std::string skinName;
  std::function<void __cdecl(void)> cb;
};

```

### `ClientInstance::_startExternalNetworkWorld::__l2::<lambda_2f4e89c11809877f171d784f43a2bb0a>::()::__l25::<lambda_c3b381cfcfb0e0326cf8436579754cbd>`
```
struct __cppobj ClientInstance::_startExternalNetworkWorld::__l2::<lambda_2f4e89c11809877f171d784f43a2bb0a>::()::__l25::<lambda_c3b381cfcfb0e0326cf8436579754cbd>
{
  Social::GameConnectionInfo connectionInfo;
};

```

### `ClientInstance::linkToAllOffers::__l8::<lambda_8c1c471bd4836df2d4db0c759413a7fe>`
```
struct __cppobj ClientInstance::linkToAllOffers::__l8::<lambda_8c1c471bd4836df2d4db0c759413a7fe>
{
  ClientInstance *const __this;
};

```

### `ClientInstance::initTTSClient::__l5::<lambda_385529706c5cafdb75cef3e23b3c0d1a>`
```
struct __cppobj ClientInstance::initTTSClient::__l5::<lambda_385529706c5cafdb75cef3e23b3c0d1a>
{
};

```

### `CooldownItemComponent`
```
struct __cppobj __declspec(align(8)) CooldownItemComponent : ItemComponent
{
  std::string mCoolDownType;
  float mCooldownTime;
};

```

### `CooldownItemComponent_vtbl`
```
struct /*VFT*/ CooldownItemComponent_vtbl
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

### `ChannelImageParams`
```
struct __cppobj ChannelImageParams
{
  std::string mContentUrl;
};

```

### `cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(std::nullptr_t &)> > >`
```
const struct __cppobj cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(std::nullptr_t &)> > >
{
  std::shared_ptr<cg::details::WorkToken const > mToken;
  std::optional<std::shared_ptr<std::function<void __cdecl(std::nullptr_t &)> > > mResult;
};

```

### `CommandListFuture`
```
struct __cppobj CommandListFuture
{
  std::variant<std::function<void __cdecl(CommandListTaskContext &)>,std::shared_ptr<cg::details::DispatchToken<std::shared_ptr<cg::details::WorkToken const >,std::shared_ptr<std::function<void __cdecl(std::nullptr_t &)> > > const > > mWork;
};

```

### `CompletionState`
```
struct __cppobj CompletionState
{
};

```

### `cg::TaskDispatcherSchedulerTraits<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >`
```
struct __cppobj cg::TaskDispatcherSchedulerTraits<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >
{
};

```

### `cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution`
```
struct __cppobj cg::TaskDispatcher<cg::TaskScheduler<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &> > >::TaskDispatcherExecution
{
};

```

### `ChangeUserStage`
```
struct __cppobj ChangeUserStage : BaseStage
{
};

```

### `ChangeUserStage_vtbl`
```
struct /*VFT*/ ChangeUserStage_vtbl
{
  void (__fastcall *~BaseStage)(BaseStage *this);
  void (__fastcall *onAwake)(BaseStage *this);
  void (__fastcall *onUpdate)(BaseStage *this);
  bool (__fastcall *ayncTask)(BaseStage *this);
};

```

### `Crypto::Random::Random`
```
struct __cppobj Crypto::Random::Random
{
  std::random_device rd;
};

```

### `Core::FileSystemInterfaceImpl`
```
struct __cppobj Core::FileSystemInterfaceImpl : Core::IFileSystem
{
};

```

### `Core::FileSystemInterfaceImpl_vtbl`
```
struct /*VFT*/ Core::FileSystemInterfaceImpl_vtbl
{
  void (__fastcall *~IFileSystem)(Core::IFileSystem *this);
  std::unique_ptr<Core::IFile> *(__fastcall *openFile)(Core::IFileSystem *this, std::unique_ptr<Core::IFile> *result, Core::Path, Core::FileOpenMode, Core::FileBufferingMode);
  bool (__fastcall *fileExists)(Core::IFileSystem *this, Core::Path);
  Core::Result *(__fastcall *iterateOverDirectory)(Core::IFileSystem *this, Core::Result *result, Core::Path, Core::DirectoryIterationFlags, std::function<Core::Result __cdecl(Core::DirectoryIterationItem const &)>);
  Core::Result *(__fastcall *getDirectoryFiles)(Core::IFileSystem *this, Core::Result *result, std::vector<Core::PathBuffer<std::string >> *, Core::Path);
};

```

### `Core::Profile::ProfileSectionCPU`
```
struct __cppobj Core::Profile::ProfileSectionCPU
{
  const Core::Profile::CPUProfileTokenMicroProfile *mToken;
};

```

### `cg::IGraphicsDeviceVendorProvider`
```
struct __cppobj cg::IGraphicsDeviceVendorProvider : Bedrock::EnableNonOwnerReferences
{
  cg::IGraphicsDeviceVendorProvider_vtbl *__vftable /*VFT*/;
};

```

### `cg::IGraphicsDeviceVendorProvider_vtbl`
```
struct /*VFT*/ cg::IGraphicsDeviceVendorProvider_vtbl
{
  void (__fastcall *~IGraphicsDeviceVendorProvider)(cg::IGraphicsDeviceVendorProvider *this);
  unsigned int (__fastcall *getVendorID)(cg::IGraphicsDeviceVendorProvider *this);
};

```

### `Core::Profile::FileCounters`
```
struct __cppobj Core::Profile::FileCounters
{
  unsigned __int64 requests;
  unsigned __int64 retries;
  unsigned __int64 retrySuccess;
  unsigned __int64 failures;
};

```

### `CollectionComponent`
```
struct __cppobj CollectionComponent : UIComponent
{
  int mCurrentLength;
  std::string mCollectionName;
  std::vector<std::string> mControlBindings;
};

```

### `CollectionComponent_vtbl`
```
struct /*VFT*/ CollectionComponent_vtbl
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

### `CollectionItemComponent`
```
struct __cppobj __declspec(align(8)) CollectionItemComponent : UIComponent
{
  int mCollectionIndex;
};

```

### `CollectionItemComponent_vtbl`
```
struct /*VFT*/ CollectionItemComponent_vtbl
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

### `ClipArea`
```
struct __cppobj ClipArea
{
  glm::tvec2<float,0> mTopLeftClip;
  glm::tvec2<float,0> mBottomRightClip;
};

```

### `cg::SchedulerExecutionTraits<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>,cg::details::WorkToken>`
```
struct __cppobj cg::SchedulerExecutionTraits<cg::LambdaExecutor<std::nullptr_t,cg::TaskPoolGroupExecutionPolicy<std::nullptr_t,1>,std::string const &,std::vector<cg::GroupPoolDescription> const &>,cg::details::WorkToken>
{
};

```

### `CreditsRenderer::CreditsContent`
```
struct __cppobj CreditsRenderer::CreditsContent
{
  CreditsRenderer::CreditsContent::Type mType;
  int mHeight;
  int mPaddingAfter;
  std::string mText;
  bool mCentered;
  mce::TexturePtr mTexturePtr;
};

```

### `CreditsRenderer`
```
struct __cppobj CreditsRenderer : MinecraftUICustomRenderer
{
  bool mInitialized;
  glm::tvec2<float,0> mOwnerSize;
  std::vector<CreditsRenderer::CreditsContent> mContent;
  unsigned int mIndex;
  float mCurrentOffset;
  std::string mPlayerName;
  float mScrollSpeed;
  bool mFinished;
  std::vector<ScreenEvent> mScreenEvents;
  unsigned int mCreditsEndEventId;
  long double mTimeNowSeconds;
  long double mTimeLastSeconds;
  long double mDeltaTimeSeconds;
};

```

### `CreditsRenderer_vtbl`
```
struct /*VFT*/ CreditsRenderer_vtbl
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

### `CallbackProgressHandler`
```
struct __cppobj __declspec(align(8)) CallbackProgressHandler : EmptyProgressHandler
{
  std::function<enum LoadingState __cdecl(void)> mOnStart;
  _BYTE mLoadingState[4];
};

```

### `CallbackProgressHandler_vtbl`
```
struct /*VFT*/ CallbackProgressHandler_vtbl
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

### `ContentLogFileDeleteProgressHandler`
```
struct __cppobj ContentLogFileDeleteProgressHandler : ProgressHandler
{
  std::unique_ptr<TaskGroup> mIOTaskGroup;
};

```

### `ContentLogFileDeleteProgressHandler_vtbl`
```
struct /*VFT*/ ContentLogFileDeleteProgressHandler_vtbl
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

### `ContentLogFileDeleteProgressHandler::onStart::__l2::<lambda_4c44ad55a9de036e094d9593064c39b6>`
```
struct __cppobj ContentLogFileDeleteProgressHandler::onStart::__l2::<lambda_4c44ad55a9de036e094d9593064c39b6>
{
  std::weak_ptr<MinecraftScreenModel> weakModel;
};

```

### `ContentLogFileDeleteProgressHandler::onStart::__l2::<lambda_df8545a0f7b237ada6fdb7790c17e3e2>`
```
struct __cppobj ContentLogFileDeleteProgressHandler::onStart::__l2::<lambda_df8545a0f7b237ada6fdb7790c17e3e2>
{
  std::weak_ptr<MinecraftScreenModel> weakModel;
};

```

### `CheckDoneProgressHandler`
```
struct __cppobj CheckDoneProgressHandler : EmptyProgressHandler
{
};

```

### `CheckDoneProgressHandler_vtbl`
```
struct /*VFT*/ CheckDoneProgressHandler_vtbl
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

### `ContainerInteractionStateMachine`
```
struct __cppobj __declspec(align(8)) ContainerInteractionStateMachine
{
  Node mCurrentNode;
  _BYTE mCurrentNodeId[4];
  _BYTE mDefaultNodeId[4];
  std::unordered_map<int,Node> mNodes;
  std::unordered_map<int,std::vector<ButtonEdge>> mButtonEdges;
  std::unordered_map<int,std::vector<PointerHeldEdge>> mPointerHeldEdges;
  _BYTE mNodeChangeRequest[4];
};

```

### `CannotUseNetworkFeaturesScreenController`
```
struct __cppobj CannotUseNetworkFeaturesScreenController : MinecraftScreenController
{
  std::function<void __cdecl(bool)> mCallback;
};

```

### `CannotUseNetworkFeaturesScreenController_vtbl`
```
struct /*VFT*/ CannotUseNetworkFeaturesScreenController_vtbl
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

### `CellularDataWarningScreenController`
```
struct __cppobj CellularDataWarningScreenController : MinecraftScreenController
{
  std::function<void __cdecl(bool)> mCallback;
};

```

### `CellularDataWarningScreenController_vtbl`
```
struct /*VFT*/ CellularDataWarningScreenController_vtbl
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

### `ChalkboardScreenController`
```
struct __cppobj __declspec(align(4)) ChalkboardScreenController : ClientInstanceScreenController
{
  std::unique_ptr<DeferredTextObject> mDeferredTextObject;
  BlockPos mBlockPosition;
  bool mLockVisible;
};

```

### `ChalkboardScreenController_vtbl`
```
struct /*VFT*/ ChalkboardScreenController_vtbl
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

### `ChalkboardScreenController::_registerBindings::__l2::<lambda_c19ad1e94829ad65b348c00d4b053945>`
```
struct __cppobj ChalkboardScreenController::_registerBindings::__l2::<lambda_c19ad1e94829ad65b348c00d4b053945>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::_registerBindings::__l2::<lambda_e6cf651c2b9c075e876ca69014ef3811>`
```
struct __cppobj ChalkboardScreenController::_registerBindings::__l2::<lambda_e6cf651c2b9c075e876ca69014ef3811>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::_registerBindings::__l2::<lambda_af391edb9ee7620a22893f79e25173cc>`
```
struct __cppobj ChalkboardScreenController::_registerBindings::__l2::<lambda_af391edb9ee7620a22893f79e25173cc>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::_registerBindings::__l2::<lambda_8c03d1cb961bf5361ba907cd86efe50f>`
```
struct __cppobj ChalkboardScreenController::_registerBindings::__l2::<lambda_8c03d1cb961bf5361ba907cd86efe50f>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::_registerEventHandlers::__l2::<lambda_fa542fb72eb60c5ac5c4fac0c505fbf8>`
```
struct __cppobj ChalkboardScreenController::_registerEventHandlers::__l2::<lambda_fa542fb72eb60c5ac5c4fac0c505fbf8>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::_registerEventHandlers::__l2::<lambda_b42cf05c41a2e21b640eb802e5774fa5>`
```
struct __cppobj ChalkboardScreenController::_registerEventHandlers::__l2::<lambda_b42cf05c41a2e21b640eb802e5774fa5>
{
  ChalkboardScreenController *const __this;
};

```

### `ChalkboardScreenController::{ctor}::__l2::<lambda_fff40c3734e5a3c973fe8967245ac69b>`
```
struct __cppobj ChalkboardScreenController::{ctor}::__l2::<lambda_fff40c3734e5a3c973fe8967245ac69b>
{
  ChalkboardScreenController *const __this;
};

```

### `CellularDataWarningScreenController::onOpen::__l2::<lambda_6d10d2c4851a646b8d330e59b5f34f14>`
```
struct __cppobj CellularDataWarningScreenController::onOpen::__l2::<lambda_6d10d2c4851a646b8d330e59b5f34f14>
{
  std::weak_ptr<CellularDataWarningScreenController> weakThis;
};

```

### `CannotUseNetworkFeaturesScreenController::onOpen::__l2::<lambda_b48d9a7038debf97dda08a06e326b111>`
```
struct __cppobj CannotUseNetworkFeaturesScreenController::onOpen::__l2::<lambda_b48d9a7038debf97dda08a06e326b111>
{
  std::weak_ptr<CannotUseNetworkFeaturesScreenController> weakThis;
};

```

### `ChatSettingsScreenController::ChatSettings`
```
struct ChatSettingsScreenController::ChatSettings
{
  bool mIsChatMute;
  bool mIsTTSOn;
  Typeface mTypeface;
  int mFontSize;
  float mLineSpacing;
  int mChatColorCode;
  int mMentionsColorCode;
};

```

### `ChatSettingsScreenController`
```
struct __cppobj ChatSettingsScreenController : ClientInstanceScreenController
{
  ChatSettingsScreenController::ChatSettings mInitialSettings;
  ChatSettingsScreenController::ChatSettings mSettings;
  const bool mLanguageCanBeSmooth;
  std::function<void __cdecl(void)> mRefreshChatCallback;
};

```

### `ChatSettingsScreenController_vtbl`
```
struct /*VFT*/ ChatSettingsScreenController_vtbl
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

### `ChatScreenController`
```
struct __cppobj ChatScreenController : ClientInstanceScreenController
{
  std::string mCurrentMessage;
  bool mRefreshChatMessages;
  int mCurrentSentMessageIndex;
  bool mNeedsLayoutUpdate;
  bool mLastKeyboardActive;
  bool mIsDevConsole;
  bool mSendMessage;
  bool mUpdateIntellisense;
  IntellisenseHandler mIntellisense;
  _BYTE mCurrentHostOption[4];
  std::vector<std::string> mHostCommands;
  unsigned int mExpectedCommandDepth;
  std::string mTeleportWhoName;
  std::string mTeleportWhereName;
  std::string mDeferedCollectionFocusName;
  int mDeferedCollectionFocusIndex;
  bool mWaitOneTick;
  std::vector<std::pair<enum HostOptionStates,std::string >> mMainHostButtons;
};

```

### `ChatScreenController_vtbl`
```
struct /*VFT*/ ChatScreenController_vtbl
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

### `ChooseRealmScreenController::RealmsWorld`
```
struct __cppobj __declspec(align(8)) ChooseRealmScreenController::RealmsWorld
{
  RealmsWorldInfo world;
  bool doneLoading;
};

```

### `ChooseRealmScreenController`
```
struct __cppobj __declspec(align(8)) ChooseRealmScreenController : MainMenuScreenController
{
  bool mDirty;
  std::vector<Realms::World> mRealms;
  std::vector<ChooseRealmScreenController::RealmsWorld> mRealmWorldList;
  std::function<void __cdecl(Realms::World)> mCallback;
  ChooseRealmScreenController::RealmsSubscriptionsLoadingState mRealmsSubscriptionsLoadingState;
};

```

### `ChooseRealmScreenController_vtbl`
```
struct /*VFT*/ ChooseRealmScreenController_vtbl
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

### `CodeScreenControllerProxy`
```
struct __cppobj CodeScreenControllerProxy : ScreenControllerProxy
{
};

```

### `CodeScreenControllerProxy_vtbl`
```
struct /*VFT*/ CodeScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
  void (__fastcall *selectCodeButton)(CodeScreenControllerProxy *this, int);
};

```

### `CodeScreenEditorButton`
```
struct __cppobj CodeScreenEditorButton
{
  std::string name;
  std::string description;
  std::string url;
  std::string defaultImage;
};

```

### `CodeScreenController`
```
struct __cppobj CodeScreenController : ClientInstanceScreenController, CodeScreenControllerProxy, WebviewObserver
{
  std::vector<CodeScreenEditorButton> mEditorButtons;
  std::string mChosenUrl;
  CodeScreenController::View mView;
  _BYTE mModalView[4];
  bool mNeedsRefresh;
  bool mWebviewLoading;
  bool mHasDefaultUri;
  bool mHasOverrideUri;
  WebviewInterfaceOptions mCodebuilderDef;
};

```

### `CodeScreenController_vtbl`
```
struct /*VFT*/ CodeScreenController_vtbl
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

### `CodeScreenController::_registerBindings::__l2::<lambda_16de65ca34e12ac497d252dfd6d10cf9>`
```
struct __cppobj CodeScreenController::_registerBindings::__l2::<lambda_16de65ca34e12ac497d252dfd6d10cf9>
{
  CodeScreenController *const __this;
};

```

### `CommonDialogInfoScreenController`
```
struct __cppobj CommonDialogInfoScreenController : MinecraftScreenController
{
  const std::string mDialogTitle;
  const std::string mDialogBody;
};

```

### `CommonDialogInfoScreenController_vtbl`
```
struct /*VFT*/ CommonDialogInfoScreenController_vtbl
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

### `ConnectGamepadScreenController`
```
struct __cppobj ConnectGamepadScreenController : MinecraftScreenController
{
  std::function<void __cdecl(void)> mOnCompleteCallback;
};

```

### `ConnectGamepadScreenController_vtbl`
```
struct /*VFT*/ ConnectGamepadScreenController_vtbl
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

### `ContainerScreenController`
```
struct __cppobj __declspec(align(8)) ContainerScreenController : ClientInstanceScreenController
{
  BlockPos mBlockPos;
  ActorUniqueID mEntityUniqueID;
  _BYTE mTypeInContainer[4];
  bool mShowItemCategory;
  ContainerInteractionStateMachine mContainerStateMachine;
  SlotData mLastStateSlot;
  int mLastPlacedAmount;
  bool mSingleSplit;
  SlotData mTouchSplitData;
  ItemGroup mSelectedSplitTarget;
  ProgressiveTakeButtonData mProgressiveTakeButton;
  unsigned int mTouchProgressiveSelectButton;
  std::vector<ItemStateData> mPreviousState;
  SlotData mSelectedSlotData;
  SlotData mLastSelectedSlotData;
  SlotData mHoveredSlotData;
  std::unordered_map<std::string,std::vector<std::string>> mCoalesceOrderMap;
  std::unordered_map<std::string,std::vector<AutoPlaceItem>> mAutoPlaceOrderMap;
  InteractionModel mInteractionModel;
  std::shared_ptr<ContainerManagerController> mContainerManagerController;
  bool mNeedsUpdatedBinds;
};

```

### `ContainerScreenController_vtbl`
```
struct /*VFT*/ ContainerScreenController_vtbl
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

### `ContainerFactory`
```
struct __cppobj ContainerFactory
{
};

```

### `ContainerScreenControllerProxyCallbacks`
```
struct __cppobj ContainerScreenControllerProxyCallbacks
{
  std::function<ItemStack const & __cdecl(std::string const &,int)> mGetItemInstance;
  std::function<void __cdecl(int,std::string const &,int)> mAutoPlace;
  std::function<unsigned int __cdecl(std::string const &)> mGetNameId;
  std::function<enum NodeId __cdecl(unsigned int,enum ButtonEventType,std::string const &,int)> mReceiveEvent;
};

```

### `ContainerScreenControllerProxy`
```
struct __cppobj ContainerScreenControllerProxy : ScreenControllerProxy
{
  const ContainerScreenControllerProxyCallbacks mCallbacks;
};

```

### `ContainerScreenControllerProxy_vtbl`
```
struct /*VFT*/ ContainerScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `ContentLogScreenController`
```
struct __cppobj ContentLogScreenController : MinecraftScreenController
{
};

```

### `ContentLogScreenController_vtbl`
```
struct /*VFT*/ ContentLogScreenController_vtbl
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

### `ContentLogHistoryScreenController`
```
struct __cppobj ContentLogHistoryScreenController : MinecraftScreenController
{
};

```

### `ContentLogHistoryScreenController_vtbl`
```
struct /*VFT*/ ContentLogHistoryScreenController_vtbl
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

### `ControlsSettingsScreenController`
```
struct __cppobj ControlsSettingsScreenController : SettingsScreenControllerBase
{
  GamePadRemappingLayout *mGamepadLayout;
  std::vector<ControlsSettingsScreenController::BindingInfo> mGamepadBindings;
  KeyboardType mCurrentKeyboardType;
  std::vector<ControlsSettingsScreenController::KeyboardLayoutInfo> mKeyboardLayoutInformation;
  int mSelectedIndex;
  InputBindingMode mActiveBindingMode;
  const std::vector<std::string> *mDisabledInputMappings;
};

```

### `ControlsSettingsScreenController::BindingInfo`
```
struct __cppobj __declspec(align(8)) ControlsSettingsScreenController::BindingInfo
{
  std::string mAction;
  std::string mIcon;
  std::vector<int> mKeys;
  bool mActive;
};

```

### `ControlsSettingsScreenController_vtbl`
```
struct /*VFT*/ ControlsSettingsScreenController_vtbl
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
  void (__fastcall *_registerControllerCallbacks)(ControlsSettingsScreenController *this);
};

```

### `ConvertPurchasesToXBLScreenController`
```
struct __cppobj __declspec(align(8)) ConvertPurchasesToXBLScreenController : MinecraftScreenController
{
  std::function<void __cdecl(bool)> mExitScreenCallback;
  bool mTryConversionAgain;
};

```

### `ConvertPurchasesToXBLScreenController_vtbl`
```
struct /*VFT*/ ConvertPurchasesToXBLScreenController_vtbl
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

### `CourseScreenController`
```
struct __cppobj CourseScreenController : MainMenuScreenController
{
  std::shared_ptr<TutorialCollection> mTutorialCollection;
  int mActiveItemIndex;
  std::string mCourseTitle;
  std::string mCourseId;
  bool mHasComputedInitialActiveIndex;
  CourseScreenController::LoadingProgress mLocalWorldLoadingProgress;
  int mHoveredItemIndex;
  std::shared_ptr<PlayScreenModel> mPlayScreenModel;
  std::shared_ptr<MultiplayerLessonScreenController> mMultiplayerLessonScreenController;
  std::shared_ptr<EducationContentManagerScreenController> mEducationContentManagerScreenController;
  std::shared_ptr<LessonProgressionService> mLessonProgressionService;
};

```

