# C
### `Core::HeapPathBuffer`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mContainer


### `Core::FilePathManager`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsDedicatedServer
8 | (32) `Core::HeapPathBuffer` | mRoot
40 | (32) `Core::HeapPathBuffer` | mPackagePath
72 | (32) `Core::HeapPathBuffer` | mDataUrl
104 | (32) `Core::HeapPathBuffer` | mExternalFilePath
136 | (32) `Core::HeapPathBuffer` | mTemporaryFilePath
168 | (32) `Core::HeapPathBuffer` | mCacheFilePath
200 | (32) `Core::HeapPathBuffer` | mSettingsPath


### `ContentTierManager`
Offset | Type | Name
-|-|-|-
0 | (4) `MemoryTier` | mMemoryTier


### `ContentKeyMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ContentIdentity,std::string>::_Hashtable` | _M_h


### `ContentIdentity`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::UUID` | mUUID
16 | (1) `bool` | mValid


### `CompoundTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (48) `TagMap` | mTags


### `Core::Result`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::Result::MessageResolver` | mMessageResolver
32 | (1) `__int8` | _bf_20


### `Core::Result::MessageResolver`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<const char *(std::string *)>::_Invoker_type` | _M_invoker


### `ConnectionDefinition`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | ipv4Port
2 | (2) `uint16_t` | ipv6Port
4 | (4) `ConnectionDefinition::PortBusyFallbackPolicy` | fallback
8 | (4) `int` | maxNumPlayers
12 | (4) `int` | maxNumConnections


### `Core::StackPathBuffer`
Offset | Type | Name
-|-|-|-
0 | (1040) `Core::StackString<char,1024>` | mContainer


### `Core::StackString<char,1024>`
Offset | Type | Name
-|-|-|-
0 | (8) `const size_t` | MAX_LENGTH
8 | (1024) `std::array<char,1024>` | mBuf
1032 | (8) `size_t` | mLength


### `Core::File`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Core::FileImpl>` | muptFile
8 | (8) `std::unique_ptr<Core::FileSystemImpl>` | muptTransaction


### `Core::InputFileStream`
Offset | Type | Name
-|-|-|-
0 | (416) `Core::FileStream` | baseclass_0


### `Core::FileStream`
Offset | Type | Name
-|-|-|-
0 | (24) `std::iostream:192` | baseclass_0
24 | (120) `Core::FileStdStreamBuf` | mStreamBuffer
144 | (1) `bool` | mLoggingEnabled
145 | (271) `_BYTE[271]` | gap91


### `Core::FileStdStreamBuf`
Offset | Type | Name
-|-|-|-
0 | (64) `__int8[64]` | baseclass_0
64 | (16) `Core::File` | mFile
80 | (1) `Core::FileOpenMode` | mFileOpenMode
88 | (24) `std::vector<char>` | mBuffer
112 | (8) `Core::FileSize` | mBufferSize


### `Core::FileOpenMode`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `CommandRegistry::DefaultIdConverter<ChangeSettingCommand::Setting>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandVersion`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFrom
4 | (4) `int` | mTo


### `CommandRegistry::DefaultIdConverter<SaveCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<WhitelistCommand::Action>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Core::PathBuffer<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mContainer


### `com::mojang::clacks::protocol::Empty`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::LevelFileAndSize`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (8) `google::protobuf::internal::ArenaStringPtr` | value_
24 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::PlayerInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (8) `com::mojang::clacks::protocol::Xuid *` | xuid_
24 | (8) `com::mojang::clacks::protocol::PlayerName *` | name_
32 | (4) `int` | playertype_
36 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::PlayerName`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (8) `google::protobuf::internal::ArenaStringPtr` | value_
24 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::Xuid`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (8) `google::protobuf::internal::ArenaStringPtr` | value_
24 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::PlayerList`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (24) `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::PlayerInfo>` | player_
40 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::SaveQueryResult`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (24) `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::LevelFileAndSize>` | files_
40 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `com::mojang::clacks::protocol::SaveStateResult`
Offset | Type | Name
-|-|-|-
0 | (8) `__int8[8]` | baseclass_0
8 | (8) `google::protobuf::internal::InternalMetadataWithArena` | _internal_metadata_
16 | (4) `int` | savestate_
20 | (4) `google::protobuf::internal::CachedSize` | _cached_size_


### `Core::SplitPath`
Offset | Type | Name
-|-|-|-
0 | (2048) `std::array<Core::Path,64>` | mParts
2048 | (8) `size_t` | mNumParts


### `Core::PathPart`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUtf8StdString


### `Core::StringSpan`
Offset | Type | Name
-|-|-|-
0 | (16) `string_span` | mStringSpan


### `Core::SplitPathT<1024,64>::SplitPathT::$1CC25A583192B38B92CA1589E23791C2`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::SplitPathT<1024,64> *` | this
8 | (8) `__gnu_cxx::__normal_iterator<const char *,std::string > *` | splitEnd
16 | (8) `__gnu_cxx::__normal_iterator<const char *,std::string > *` | splitStart
24 | (8) `const std::string *` | fullPath


### `Core::Random`
Offset | Type | Name
-|-|-|-
0 | (4) `RandomSeed` | mSeed
4 | (2496) `uint32_t[624]` | _mt
2500 | (4) `int` | _mti
2504 | (1) `bool` | mHaveNextNextGaussian
2508 | (4) `float` | mNextNextGaussian
2512 | (4) `int` | mInitedIdx


### `Core::Profile::CPUProfileToken`
Offset | Type | Name
-|-|-|-
0 | (8) `MicroProfileToken` | mMicroProfileToken
8 | (4) `uint32_t` | mColor


### `Core::Profile::ProfileSectionCPU`
Offset | Type | Name
-|-|-|-
0 | (8) `const Core::Profile::CPUProfileToken *` | mToken


### `CommandSelectorResults<Player>`
Offset | Type | Name
-|-|-|-
0 | (16) `CommandResultVector` | mTargets


### `CommandResultVector`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<std::vector<Actor *>,__gnu_cxx::_S_atomic>` | baseclass_0


### `ChunkPos`
Offset | Type | Name
-|-|-|-
0 | (8) `ChunkPos::$9F8988CC0F9198BEB3D9C07F7FC1F2E7` | _anon_0


### `ChunkPos::$9F8988CC0F9198BEB3D9C07F7FC1F2E7`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | packed
1 | (8) `ChunkPos::$9F8988CC0F9198BEB3D9C07F7FC1F2E7::$71D3E18752AF5CECAE552A00ECF6483C` | _anon_0


### `ChunkPos::$9F8988CC0F9198BEB3D9C07F7FC1F2E7::$71D3E18752AF5CECAE552A00ECF6483C`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | z


### `ChunkBlockPos`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | x
1 | (1) `uint8_t` | z
2 | (2) `Height` | y


### `CachedBiomeSource<VanillaOverworldBiomeSource>`
Offset | Type | Name
-|-|-|-
0 | (40) `VanillaOverworldBiomeSource` | baseclass_0
40 | (16) `std::shared_ptr<BiomeSourceGetBiomeCache>` | mCache


### `ConstLayerPtr<Biome *>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::__shared_ptr<const Layer<Biome *>,__gnu_cxx::_S_atomic>` | baseclass_0


### `CommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$CommandOrigin
8 | (16) `mce::UUID` | mUUID


### `CommandOutput`
Offset | Type | Name
-|-|-|-
0 | (4) `CommandOutputType` | mType
8 | (8) `std::unique_ptr<CommandPropertyBag>` | mBag
16 | (24) `std::vector<CommandOutputMessage>` | mMessages
40 | (4) `int` | mSuccessCount


### `CommandRegistry::Parser`
Offset | Type | Name
-|-|-|-
0 | (8) `const CommandRegistry *` | mRegistry
8 | (8) `const CommandRegistry::ParseTable *` | mParseTable
16 | (80) `std::deque<std::pair<CommandRegistry::Symbol,CommandRegistry::ParseToken *>>` | mStack
96 | (32) `CommandRegistry::LexicalToken` | mNext
128 | (32) `std::string` | mInput
160 | (8) `std::unique_ptr<CommandRegistry::ParseToken>` | mRoot
168 | (32) `std::string` | mError
200 | (24) `std::vector<std::string>` | mErrorParams
224 | (4) `int` | mVersion
228 | (1) `bool` | mGenerateParams
229 | (1) `bool` | mBreakAtEnd


### `CommandRegistry::LexicalToken`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | mText
8 | (4) `uint32_t` | mLength
12 | (4) `CommandRegistry::Terminal` | mType
16 | (4) `CommandRegistry::Terminal` | mIdentifierInfo
24 | (8) `const CommandRegistry *` | mRegistry


### `CommandRegistry::Terminal`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mValue


### `CommandBlockComponent`
Offset | Type | Name
-|-|-|-
0 | (152) `BaseCommandBlock` | mBaseCommandBlock
152 | (4) `int` | mCurrentTickCount
156 | (1) `bool` | mTicking


### `Core::PathFileNamePart`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUtf8StdString


### `Core::PathExtensionWithDotPart`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mUtf8StdString


### `Core::PathBuffer<Core::StackString<char,1024> >`
Offset | Type | Name
-|-|-|-
0 | (1040) `Core::StackString<char,1024>` | mContainer


### `CraftingDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<CraftingDataEntry>` | mCraftingEntries
64 | (24) `std::vector<PotionMixDataEntry>` | mPotionMixEntries
88 | (24) `std::vector<ContainerMixDataEntry>` | mContainerMixEntries
112 | (1) `bool` | mClearRecipes


### `CraftingDataEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<Recipe>` | mRecipe
8 | (4) `int` | mItemData
12 | (4) `int` | mItemAux
16 | (40) `Util::HashString` | mTag
56 | (136) `ItemInstance` | mItemResult
192 | (4) `CraftingDataEntryType` | mEntryType


### `ContainerMixDataEntry`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | fromItemId
4 | (4) `int` | reagentItemId
8 | (4) `int` | toItemId


### `Color`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r
4 | (4) `float` | g
8 | (4) `float` | b
12 | (4) `float` | a


### `ClientboundMapItemDataPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (24) `std::vector<ActorUniqueID>` | mMapIds
64 | (1) `int8_t` | mScale
72 | (24) `std::vector<std::shared_ptr<MapDecoration>>` | mDecorations
96 | (24) `std::vector<MapItemTrackedActor::UniqueId>` | mUniqueIds
120 | (4) `int` | mStartX
124 | (4) `int` | mStartY
128 | (1) `uint8_t` | mDimension
132 | (4) `int` | mWidth
136 | (4) `int` | mHeight
140 | (4) `ClientboundMapItemDataPacket::Type` | mType
144 | (24) `std::vector<unsigned int>` | mMapPixels
168 | (1) `bool` | mLocked


### `CommandOriginData`
Offset | Type | Name
-|-|-|-
0 | (1) `CommandOriginType` | mType
8 | (16) `mce::UUID` | mUUID
24 | (32) `std::string` | mRequestId
56 | (8) `int64_t` | mPlayerId


### `Core::Path`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathPart` | mPathPart


### `ContentTierInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `MemoryTier` | mMemoryTier


### `Core::OutputFileStream`
Offset | Type | Name
-|-|-|-
0 | (416) `Core::FileStream` | baseclass_0


### `Core::ZipUtils::ZipProgress`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic_uint` | mFilesDone
4 | (4) `std::atomic_uint` | mFilesSkipped
8 | (4) `std::atomic_uint` | mTotalFiles


### `Core::ZipUtils::UnzipSettings`
Offset | Type | Name
-|-|-|-
0 | (144) `Core::ZipUtils::ZipFileRestrictions` | mRestrictions
144 | (1) `bool` | mDeleteZipOnSuccess
145 | (1) `bool` | mPreventOverwrites
152 | (8) `IFileAccess *` | mFileAccess
160 | (32) `std::string` | mPassword
192 | (24) `std::vector<std::string>` | mSelectedPaths


### `Core::ZipUtils::ZipFileRestrictions`
Offset | Type | Name
-|-|-|-
0 | (48) `std::set<std::string>` | mForbiddenExtensions
48 | (48) `std::set<std::string>` | mRestrictedExtensions
96 | (48) `std::set<std::string>` | mForbiddenFilenames


### `Core::ZipUtils::ZipSettings`
Offset | Type | Name
-|-|-|-
0 | (144) `Core::ZipUtils::ZipFileRestrictions` | mRestrictions
144 | (1) `bool` | mZipDirectoryContents
145 | (1) `bool` | mSkipInaccessibleFiles
148 | (4) `int` | mCompressionLevel
152 | (8) `IFileAccess *` | mFileAccess
160 | (32) `std::string` | mPassword
192 | (4) `int` | mZip64


### `ConstPackCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (const Pack &)>::_Invoker_type` | _M_invoker


### `const_iterator`
Offset | Type | Name
-|-|-|-
0 | (16) `std::_Bit_iterator_base` | baseclass_0


### `CriticalSyncSaveCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void ()>::_Invoker_type` | _M_invoker


### `Core::LevelStorageResult`
Offset | Type | Name
-|-|-|-
0 | (4) `Core::LevelStorageState` | state
8 | (32) `std::string` | telemetryMsg


### `Core::Profile::ProfileThread`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ContainerOpenPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mContainerId
37 | (1) `ContainerType` | mType
40 | (12) `NetworkBlockPosition` | mPos
56 | (8) `ActorUniqueID` | mEntityUniqueID


### `ContainerClosePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (1) `ContainerID` | mContainerId


### `ChunkRadiusUpdatedPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mChunkRadius


### `ContainerSetDataPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `int` | mId
40 | (4) `int` | mValue
44 | (1) `ContainerID` | mContainerId


### `CommandFlag`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | flag


### `CommandSelectorResults<Actor>`
Offset | Type | Name
-|-|-|-
0 | (16) `CommandResultVector` | mTargets


### `CommandAreaFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `Dimension *` | mDimension


### `CommandOutputParameter::CommandOutputParameter::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandPosition`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mOffset
12 | (1) `bool` | mRelativeX
13 | (1) `bool` | mRelativeY
14 | (1) `bool` | mRelativeZ
15 | (1) `bool` | mLocal


### `CommandRegistry::Symbol`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mValue


### `CommandIntegerRange`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMinValue
4 | (4) `int` | mMaxValue
8 | (1) `bool` | mInvert


### `CommandRegistry::ProcessFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<CommandRegistry::ParseToken *(CommandRegistry::ParseToken &,CommandRegistry::Symbol)>::_Invoker_type` | _M_invoker


### `CommandRegistry::SemanticInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsValid
8 | (24) `std::vector<CommandRegistry::Symbol>` | mConstrainedParams
32 | (32) `std::string` | mSoftEnumText
64 | (32) `std::string` | mSoftEnumEscapeCharExceptions
96 | (48) `std::set<CommandRegistry::Symbol>` | mAlreadyCompletedSymbols


### `CommandRegistry::ParseTreeVisitor<(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3364:3),(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3365:3),(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3366:3)>`
Offset | Type | Name
-|-|-|-
0 | (56) `std::remove_reference<(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3366:3) &>::type` | baseclass_0


### `CommandSyntaxInformation`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isValid
8 | (32) `std::string` | description
40 | (24) `std::vector<OverloadSyntaxInformation>` | possibilities


### `CommandRegistry::ParseTreeVisitor<(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3909:4),(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3910:4),(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3920:4)>`
Offset | Type | Name
-|-|-|-
0 | (8) `std::remove_reference<(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3910:4) &>::type` | baseclass_0
8 | (16) `std::remove_reference<(lambda at _Minecraftpe_handheld_src_common_server_commands_CommandRegistry_cpp:3920:4) &>::type` | baseclass_8


### `CommandRegistry::DefaultIdConverter<GameType>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<bool>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<int>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::NonTerminal`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mValue


### `CommandRegistry::CommandOverrideFunctor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (CommandFlag &,const std::string &)>::_Invoker_type` | _M_invoker


### `CommandRegistry::SymbolVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<CommandRegistry::Symbol>` | baseclass_0


### `CommandLexer`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | mInput
8 | (16) `CommandLexer::Token` | mToken


### `CommandLexer::Token`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | text
8 | (4) `uint32_t` | length
12 | (4) `CommandLexer::TokenType` | type


### `CommandRegistry::DefaultIdConverter<const Block *>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::RegistryState`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | signatureCount
4 | (4) `uint32_t` | enumValueCount
8 | (4) `uint32_t` | postfixCount
12 | (4) `uint32_t` | enumCount
16 | (4) `uint32_t` | factorizationCount
20 | (4) `uint32_t` | optionalCount
24 | (4) `uint32_t` | ruleCount
28 | (4) `uint32_t` | softEnumCount
32 | (4) `uint32_t` | constraintCount
40 | (24) `std::vector<unsigned int>` | constrainedValueCount
64 | (24) `std::vector<unsigned int>` | softEnumValuesCount


### `CommandRegistry::ConstrainedValueLookupKey`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | first
8 | (4) `unsigned int` | second


### `CommandRegistry::ScoreboardScoreAccessor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<int (bool &,const std::string &,const Actor &)>::_Invoker_type` | _M_invoker


### `CommandRegistry::CommandVisitCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (const CommandRegistry::ParseToken *,const CommandOrigin &)>::_Invoker_type` | _M_invoker


### `CommandSelectorBase::FilterFunc`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (const CommandOrigin &,const Actor &)>::_Invoker_type` | _M_invoker


### `CommandRegistry::DefaultIdConverter<const ActorDefinitionIdentifier *>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<CommandItem>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<StructureFeatureType>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<Enchant::Type>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRequestPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mCommand
72 | (64) `CommandOriginData` | mOrigin
136 | (1) `bool` | mInternalSource


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


### `ComponentDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `Description` | baseclass_0


### `CommandItem`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mVersion
4 | (4) `int` | mId


### `Core::ZipUtils::ZipProgressList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::shared_ptr<Core::ZipUtils::ZipProgress>>` | mZipProgress
24 | (40) `Bedrock::Threading::Mutex` | mProgressLock


### `ContainerComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `ContainerContentChangeListener` | baseclass_0
8 | (8) `Unique<Container>` | mContainer
16 | (8) `Mob *` | mListenerShim
24 | (1) `bool` | mCanBeSiphonedFrom
25 | (1) `bool` | mPrivate
26 | (1) `bool` | mRestrictToOwner
32 | (32) `std::string` | mLootTable
64 | (4) `int` | mLootTableSeed


### `ContainerContentChangeListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ContainerContentChangeListener


### `CameraPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorUniqueID` | mCameraId
48 | (8) `ActorUniqueID` | mTargetPlayerId


### `CompletedUsingItemPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (2) `__int16` | mItemId
40 | (4) `int` | mItemUseMethod


### `ContainerItemStack`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemStack` | itemStackInstance
136 | (136) `ItemInstance` | itemInstance


### `ClockSpriteCalculator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFrame
4 | (4) `float` | mRot
8 | (4) `float` | mRotA


### `CompassSpriteCalculator`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFrame
4 | (4) `float` | mRot
8 | (4) `float` | mRotA


### `Core::UnzipFile`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<ZlibFileAccessWrapper>` | mZipFileSystemWrapper
8 | (8) `std::unique_ptr<Core::UnzipInternals>` | mZipFile


### `ChangeDimensionPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (4) `DimensionType` | mDimensionId
40 | (12) `Vec3` | mPos
52 | (1) `bool` | mRespawn


### `ClimateAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mTemperature
4 | (4) `float` | mDownfall
8 | (4) `float` | mSnowAccumulationMin
12 | (4) `float` | mSnowAccumulationMax


### `CustomDebugMapColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDebugMapColor


### `CustomDebugMapColorOddAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mDebugMapOddColor


### `CustomHumidityAttributes`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsHumid


### `ColorPaletteAttributes`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPaletteName


### `CustomMapFoliageColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMapFoliageColor


### `CustomFoliageColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mFoliageColor


### `CustomGrassColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mGrassColor


### `CustomMapGrassColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mMapGrassColor


### `CustomSkyColorAttributes`
Offset | Type | Name
-|-|-|-
0 | (16) `Color` | mSkyColor


### `ChemistryTableBlock::isUIValidForPlayer::$253794F7C40A71086C2A1304B68E249E`
Offset | Type | Name
-|-|-|-
0 | (8) `const BlockPos *` | pos
8 | (8) `Player *` | player
16 | (4) `ChemistryTableType` | expectedType


### `ChalkboardBlockActor::CachedMessageData`
Offset | Type | Name
-|-|-|-
0 | (640) `std::array<ChalkboardBlockActor::CachedLineData,16>` | lineData
640 | (4) `unsigned int` | numLines
648 | (32) `std::string` | filteredMessage
680 | (8) `const void *` | cachedFontCompare
688 | (1) `bool` | dirty


### `ChunkHeightmapCache`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ChunkPos,std::unique_ptr<std::vector<short>>>::_Hashtable` | _M_h


### `CircuitComponentList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<CircuitComponentList::Item>` | mComponents


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
20 | (1) `FacingID` | mDirection
24 | (8) `uint64_t` | mTypeID


### `CircuitComponentList::Item`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseCircuitComponent *` | mComponent
8 | (4) `int` | mDampening
12 | (12) `BlockPos` | mPos
24 | (1) `FacingID` | mDirection
25 | (1) `bool` | mDirectlyPowered
28 | (4) `int` | mData


### `ContextAccessor`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mTypeId
8 | (8) `std::unique_ptr<ContextAccessor::TypeBase>` | mContext


### `Core::SplitPathT<1024,64>`
Offset | Type | Name
-|-|-|-
0 | (2048) `std::array<Core::Path,64>` | mParts
2048 | (8) `size_t` | mNumParts


### `Crypto::encryptedFileHeader`
Offset | Type | Name
-|-|-|-
0 | (256) `char[256]` | _data
1 | (256) `Crypto::encryptedFileHeader::$5002CB87BB9EDBB12D0797D08A1D72BD` | _efheader


### `Crypto::encryptedFileHeader::$5002CB87BB9EDBB12D0797D08A1D72BD`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | _version
4 | (4) `Crypto::signatureValue` | _efsignature
8 | (4) `unsigned int` | _data1
12 | (4) `unsigned int` | _data2
16 | (1) `unsigned __int8` | _IdSize
17 | (239) `char[239]` | _IdName


### `Crypto::signatureValue`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | _value
1 | (4) `unsigned __int8[4]` | _signatureBytes


### `ClientBlobCache::Server::TransferBuilder`
Offset | Type | Name
-|-|-|-
0 | (216) `ClientBlobCache::Server::ActiveTransfer` | mTransfer


### `ClientBlobCache::Server::ActiveTransfer`
Offset | Type | Name
-|-|-|-
0 | (8) `ClientBlobCache::Server::ActiveTransfersManager *` | mCache
8 | (152) `NetworkIdentifier` | mOwner
160 | (56) `std::unordered_map<unsigned long,std::shared_ptr<ClientBlobCache::Server::Blob>>` | mIdsWaitingForACK


### `CommandRegistry::DefaultIdConverter<CloneCommand::MaskMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<CloneCommand::CloneMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<Difficulty>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<EffectCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<const MobEffect *>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ExecuteCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<FillCommand::FillMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ListDCommand::DetailMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<PermissionCommand::Action>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<PermissionCommand::AvailableCommandPermissionPresets>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<BlockSlot>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<EquipmentSlot>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ReplaceItemCommand::TargetType>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ScoreboardCommand::Category>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ScoreboardCommand::Action>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<ObjectiveSortOrder>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<SetBlockCommand::SetBlockMode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TagCommand::Action>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TeleportCommand::FacingResult>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TestForBlocksCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TickingAreaCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TickingAreaCommand::AddAreaType>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TickingAreaCommand::TargetDimensions>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TimeCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TimeCommand::Query>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TimeCommand::TimeSpec>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TitleCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<TitleRawCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<VideoStreamConnectPacket::Action>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<WeatherCommand::WeatherType>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<WeatherCommand::WeatherRequest>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CompoundTagEditHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag *` | mTag
8 | (24) `std::vector<Tag *>` | mParentTag
32 | (24) `std::vector<std::string>` | mTagName


### `ContextMessageLogger`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ContextMessageLogger
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


### `ContainerEnumNameMap`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<ContainerEnumName,std::string,ContainerEnumNameHasher,std::equal_to<ContainerEnumName>,std::allocator<std::pair<const ContainerEnumName,std::string > > >::_Hashtable` | _M_h


### `ChunkSource`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ChunkSource
8 | (4) `int` | mChunkSide
16 | (8) `Level *` | mLevel
24 | (8) `Dimension *` | mDimension
32 | (8) `ChunkSource *` | mParent
40 | (8) `Unique<ChunkSource>` | mOwnedParent
48 | (8) `LevelChunkBuilderData *` | mLevelChunkBuilderData


### `CommandBlock::_executeChain::$8760BA774438E6A855C8C1CB8DE2843F`
Offset | Type | Name
-|-|-|-
0 | (8) `const CommandBlock *` | this


### `CompactionCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (CompactionStatus)>::_Invoker_type` | _M_invoker


### `CommandRegistry::DefaultIdConverter<AgentCommands::Direction>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<AgentCommand::Mode>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CommandRegistry::DefaultIdConverter<AgentCommands::CollectCommand::CollectionSpecification>`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ConsoleChunkBlender`
Offset | Type | Name
-|-|-|-
0 | (32) `SpinLock` | mSpinLock
32 | (16) `float[2][2]` | mInterpCorners
48 | (1024) `float[16][16]` | mInterpTable


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


### `Core::DiskAccessTracker::WriteOperation`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FileSize` | writeAmount
8 | (8) `std::chrono::_V2::steady_clock::time_point` | timePoint


### `Core::FileStorageArea::_beginTransaction::$A402370104E9C52EF545D733D86F5169`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FileStorageArea *` | this


### `Core::DirectoryIterationFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<Core::Result (const Core::DirectoryIterationItem &)>::_Invoker_type` | _M_invoker


### `Core::TransactionFrame`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Core::FileSystemImpl>` | msptTransaction
16 | (1040) `Core::StackPathBuffer` | mCleanPath
1056 | (40) `Core::Result` | mResult


### `Core::TransactionFrameSourceTarget`
Offset | Type | Name
-|-|-|-
0 | (1040) `Core::StackPathBuffer` | mSource
1040 | (1040) `Core::StackPathBuffer` | mTarget
2080 | (1) `bool` | mSameStorageArea
2088 | (16) `std::shared_ptr<Core::FileSystemImpl>` | msptSourceTransaction
2104 | (16) `std::shared_ptr<Core::FileSystemImpl>` | msptTargetTransaction
2120 | (40) `Core::Result` | mResult


### `Core::FileSystem::FileTransferProgress`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FileSize` | mStartPosition
8 | (8) `Core::FileSize` | mBytesWritten
16 | (8) `Core::FileSize` | mBytesRemaining


### `Core::BufferedFileOperations::_copyFileSection<8192>::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Core::FlatFileOperations::createFlatFile::$A33D1747C0AB08CA482DA30473C7FFB8`
Offset | Type | Name
-|-|-|-
0 | (8) `bool *` | deleteTargetDirectory
8 | (8) `Core::FileSystemImpl **` | targetTransaction
16 | (8) `const Core::Path *` | targetDirectoryPath


### `Core::FlatFileOperations::createFlatFile::$B53007EAE32060CC4F6B30C0745D046E`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<Core::FileImpl> *` | flatFile
8 | (8) `std::vector<char> *` | writeBuffer
16 | (8) `Core::FileSize *` | writeBufferSize


### `Core::FlatFileManifestInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mPath
32 | (8) `Core::FileSize` | mSeekPos
40 | (8) `Core::FileSize` | mFileSize
48 | (1) `uint8_t` | mFlags


### `Core::FlatFileSearchResult`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<const Core::FlatFileManifest>` | mManifest
16 | (8) `const Core::FlatFileManifestInfo *` | mManifestInfoEntry


### `Core::DirectoryIterationItem`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mFullPathName
32 | (32) `Core::PathPart` | mName
64 | (8) `Core::FileSize` | mFileSize
72 | (8) `Core::FileSize` | mFileSizeAllocationOnDisk
80 | (4) `Core::FileType` | mType
88 | (8) `Core::FileTime` | mCreateTime
96 | (8) `Core::FileTime` | mModifyTime


### `Core::`anonymous namespace'::TreeChildCompare`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Core::ZipUtils::unzipToFlatFile::$50374A4BB464550A3A71B057536681BD`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::File *` | flatFileData
8 | (8) `const Core::StackPathBuffer *` | flatFilePath


### `Core::ZipUtils::unzipToFlatFile::$FAF4479A2BA4AFA3BD422DA1BA9A6B87`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::File *` | flatFileData
8 | (8) `Core::ZipUtils::unzipToFlatFile::$50374A4BB464550A3A71B057536681BD *` | cleanupFlatFile
16 | (8) `const Core::StackPathBuffer *` | flatFilePath


### `Core::ZipUtils::unzipToFlatFile::$08149540B08F7C481DA597604321840B`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::File *` | flatFileData
8 | (8) `std::vector<char> *` | flatFileWriteBuffer
16 | (8) `Core::FileSize *` | flatFileWriteBufferSize
24 | (8) `Core::ZipUtils::unzipToFlatFile::$50374A4BB464550A3A71B057536681BD *` | cleanupFlatFile
32 | (8) `Core::ZipUtils::unzipToFlatFile::$FAF4479A2BA4AFA3BD422DA1BA9A6B87 *` | commitFunction


### `CompareScheduledCallback`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `curfile64_info`
Offset | Type | Name
-|-|-|-
0 | (112) `z_stream` | stream
112 | (4) `int` | stream_initialised
116 | (4) `uInt` | pos_in_buffered_data
120 | (8) `ZPOS64_T` | pos_local_header
128 | (8) `char *` | central_header
136 | (8) `uLong` | size_centralExtra
144 | (8) `uLong` | size_centralheader
152 | (8) `uLong` | size_centralExtraFree
160 | (8) `uLong` | flag
168 | (4) `int` | method
172 | (4) `int` | raw
176 | (65536) `Byte[65536]` | buffered_data
65712 | (8) `uLong` | dosDate
65720 | (8) `uLong` | crc32
65728 | (4) `int` | encrypt
65732 | (4) `int` | zip64
65736 | (8) `ZPOS64_T` | pos_zip64extrainfo
65744 | (8) `ZPOS64_T` | totalCompressedData
65752 | (8) `ZPOS64_T` | totalUncompressedData


### `Core::Profile::CounterToken`
Offset | Type | Name
-|-|-|-
0 | (8) `MicroProfileToken` | mMicroProfileToken


### `com::mojang::clacks::protocol::Settings::SettingsUnion`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | difficultysetting_
1 | (4) `int` | cheatssetting_


### `com::mojang::clacks::protocol::MetricReport::MetricUnion`
Offset | Type | Name
-|-|-|-
0 | (8) `com::mojang::clacks::protocol::MetricReport_BandwithMetric *` | bandwith_
1 | (8) `com::mojang::clacks::protocol::MetricReport_LatencyMetric *` | latency_
2 | (8) `google::protobuf::int64` | ticktime_


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


### `Core::FileStats`
Offset | Type | Name
-|-|-|-
0 | (8) `std::atomic<unsigned long>` | mNumSuccessfulWriteOperations
8 | (8) `std::atomic<unsigned long>` | mNumBytesWritten
16 | (8) `std::atomic<unsigned long>` | mNumFailedWriteOperations
24 | (8) `std::atomic<unsigned long>` | mNumSuccessfulReadOperations
32 | (8) `std::atomic<unsigned long>` | mNumBytesRead
40 | (8) `std::atomic<unsigned long>` | mNumFailedReadOperations
48 | (8) `std::atomic<unsigned long>` | mFileSystemSize
56 | (8) `std::atomic<unsigned long>` | mFileSystemAllocatedSize


### `Core::Observer<WebviewObserver,Core::SingleThreadedLock>`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Observer
8 | (8) `Core::Observer<WebviewObserver,Core::SingleThreadedLock>::SubjectType *` | mpSubject


### `CommandParameterData`
Offset | Type | Name
-|-|-|-
0 | (2) `typeid_t<CommandRegistry>` | mTypeIndex
8 | (8) `CommandParameterData::ParseFunction` | mParse
16 | (8) `_BYTE[8]` | gap10
24 | (32) `std::string` | mName
56 | (8) `const char *` | mEnumNameOrPostfix
64 | (4) `int` | mEnumOrPostfixSymbol
68 | (4) `CommandParameterDataType` | mParamType
72 | (4) `int` | mOffset
76 | (4) `int` | mSetOffset
80 | (1) `bool` | mIsOptional
81 | (1) `CommandParameterOption` | mOptions


### `CommandOutputParameter`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mString
32 | (4) `int` | mCount


### `CommandRegistry`
Offset | Type | Name
-|-|-|-
0 | (32) `std::function<void (const Packet &)>` | mNetworkUpdateCallback
32 | (32) `CommandRegistry::ScoreboardScoreAccessor` | mGetScoreForObjective
64 | (24) `std::vector<CommandRegistry::ParseRule>` | mRules
88 | (48) `CommandRegistry::ParseTableMap` | mParseTables
136 | (24) `std::vector<CommandRegistry::OptionalParameterChain>` | mOptionals
160 | (24) `std::vector<std::string>` | mEnumValues
184 | (24) `std::vector<CommandRegistry::Enum>` | mEnums
208 | (24) `std::vector<CommandRegistry::Factorization>` | mFactorizations
232 | (24) `std::vector<std::string>` | mPostfixes
256 | (48) `std::map<std::string,unsigned int>` | mEnumLookup
304 | (48) `std::map<std::string,unsigned long>` | mEnumValueLookup
352 | (24) `std::vector<CommandRegistry::Symbol>` | mCommandSymbols
376 | (48) `std::map<std::string,CommandRegistry::Signature>` | mSignatures
424 | (48) `std::map<typeid_t<CommandRegistry>,int>` | mTypeLookup
472 | (48) `std::map<std::string,std::string>` | mAliases
520 | (24) `std::vector<SemanticConstraint>` | mSemanticConstraints
544 | (48) `std::map<SemanticConstraint,unsigned char>` | mSemanticConstraintLookup
592 | (24) `std::vector<CommandRegistry::ConstrainedValue>` | mConstrainedValues
616 | (48) `std::map<std::pair<unsigned long,unsigned int>,unsigned int>` | mConstrainedValueLookup
664 | (24) `std::vector<CommandRegistry::SoftEnum>` | mSoftEnums
688 | (48) `std::map<std::string,unsigned int>` | mSoftEnumLookup
736 | (24) `std::vector<CommandRegistry::RegistryState>` | mStateStack
760 | (80) `CommandRegistry::ParamSymbols` | mArgs
840 | (32) `CommandRegistry::CommandOverrideFunctor` | mCommandOverrideFunctor


### `CommandRegistry::ParseTableMap`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<unsigned int,CommandRegistry::ParseTable>::_Rep_type` | _M_t


### `CommandRegistry::ParamSymbols`
Offset | Type | Name
-|-|-|-
0 | (4) `CommandRegistry::Terminal` | x
4 | (4) `CommandRegistry::Terminal` | y
8 | (4) `CommandRegistry::Terminal` | z
12 | (4) `CommandRegistry::Terminal` | _dx
16 | (4) `CommandRegistry::Terminal` | dy
20 | (4) `CommandRegistry::Terminal` | dz
24 | (4) `CommandRegistry::Terminal` | r
28 | (4) `CommandRegistry::Terminal` | rm
32 | (4) `CommandRegistry::Terminal` | rx
36 | (4) `CommandRegistry::Terminal` | rxm
40 | (4) `CommandRegistry::Terminal` | ry
44 | (4) `CommandRegistry::Terminal` | rym
48 | (4) `CommandRegistry::Terminal` | l
52 | (4) `CommandRegistry::Terminal` | lm
56 | (4) `CommandRegistry::Terminal` | c
60 | (4) `CommandRegistry::Terminal` | m
64 | (4) `CommandRegistry::Terminal` | name
68 | (4) `CommandRegistry::Terminal` | type
72 | (4) `CommandRegistry::Terminal` | score
76 | (4) `CommandRegistry::Terminal` | tag


### `Certificate`
Offset | Type | Name
-|-|-|-
0 | (136) `UnverifiedCertificate` | mUnverifiedCertificate
136 | (8) `Unique<Certificate>` | mParentCertificate
144 | (1) `bool` | mIsValid


### `CompoundTagVariant`
Offset | Type | Name
-|-|-|-
0 | (64) `CompoundTagVariant::Variant` | mTagStorage


### `CompoundTagVariant::Variant`
Offset | Type | Name
-|-|-|-
0 | (64) `std::__detail::__variant::_Variant_base<EndTag,ByteTag,ShortTag,IntTag,Int64Tag,FloatTag,DoubleTag,ByteArrayTag,StringTag,ListTag,CompoundTag,IntArrayTag>` | baseclass_0


### `Connector`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Connector


### `Connector::NatPunchInfo`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | isValid
1 | (1) `bool` | addressIsDirty
2 | (1) `bool` | succeeded
8 | (136) `RakNet::SystemAddress` | externalAddress
144 | (4) `RakNet::TimeMS` | startPingSentTime
148 | (4) `RakNet::TimeMS` | pingSentTime
152 | (4) `RakNet::TimeMS` | startPongReceivedTime
156 | (4) `RakNet::TimeMS` | pongReceivedTime


### `ConnectionRequest`
Offset | Type | Name
-|-|-|-
0 | (8) `Unique<UnverifiedCertificate>` | mCertificateData
8 | (8) `Unique<Certificate>` | mCertificate
16 | (8) `Unique<WebToken>` | mRawToken
24 | (1) `SubClientId` | mClientSubId


### `ClientBlobCache::Server::ActiveTransfersManager`
Offset | Type | Name
-|-|-|-
0 | (56) `std::unordered_map<NetworkIdentifier,std::unique_ptr<ClientBlobCache::Server::ActiveTransfersManager::TransferTracker>>` | mTransferTrackerMap
56 | (48) `ClientBlobCache::Server::ActiveTransfersManager::CacheMap` | mSentBlobs
104 | (8) `size_t` | mCacheSizeBytes


### `ClientBlobCache::Server::ActiveTransfersManager::CacheMap`
Offset | Type | Name
-|-|-|-
0 | (48) `std::map<unsigned long,std::weak_ptr<ClientBlobCache::Server::Blob>>::_Rep_type` | _M_t


### `CommandOutputMessage`
Offset | Type | Name
-|-|-|-
0 | (4) `CommandOutputMessageType` | mType
8 | (32) `std::string` | mMessageId
40 | (24) `std::vector<std::string>` | mParams


### `CatalogPackManifest`
Offset | Type | Name
-|-|-|-
0 | (992) `PackManifest` | baseclass_0
992 | (32) `std::string` | mProductId
1024 | (4) `DlcPerformanceTier` | mPerfTier


### `Core::ExcludedPath`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mPath
32 | (1) `bool` | mCopyLooseFile


### `CommandSoftEnumRegistry`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandRegistry *` | mRegistry


### `CommandRegistry::Signature`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (32) `std::string` | description
64 | (24) `std::vector<CommandRegistry::Overload>` | overloads
88 | (1) `CommandPermissionLevel` | permissionLevel
92 | (4) `CommandRegistry::Symbol` | commandSymbol
96 | (4) `CommandRegistry::Symbol` | commandAliasEnum
100 | (1) `CommandFlag` | flags
104 | (4) `int` | firstRule
108 | (4) `int` | firstFactorization
112 | (4) `int` | firstOptional
116 | (1) `bool` | runnable


### `CommandRegistry::Enum`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (2) `typeid_t<CommandRegistry>` | type
40 | (8) `CommandRegistry::ParseFunction` | parse
48 | (8) `_BYTE[8]` | gap30
56 | (24) `std::vector<std::pair<unsigned long,unsigned long>>` | values


### `CommandRegistry::Factorization`
Offset | Type | Name
-|-|-|-
0 | (4) `CommandRegistry::Terminal` | commandSymbol


### `CommandRegistry::ParseToken`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<CommandRegistry::ParseToken>` | child
8 | (8) `std::unique_ptr<CommandRegistry::ParseToken>` | next
16 | (8) `CommandRegistry::ParseToken *` | parent
24 | (8) `const char *` | text
32 | (4) `uint32_t` | length
36 | (4) `CommandRegistry::Symbol` | type


### `CommandSelectorBase`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mVersion
4 | (4) `CommandSelectionType` | mType
8 | (4) `CommandSelectionOrder` | mOrder
16 | (24) `std::vector<InvertableFilter<std::string >>` | mNameFilters
40 | (24) `std::vector<InvertableFilter<ActorDefinitionIdentifier>>` | mTypeFilters
64 | (24) `std::vector<InvertableFilter<std::string >>` | mTagFilters
88 | (24) `std::vector<std::function<bool (const CommandOrigin &,const Actor &)>>` | mFilterChain
112 | (16) `CommandPosition` | mPosition
128 | (12) `BlockPos` | mBoxDeltas
140 | (4) `float` | mRadiusMin
144 | (4) `float` | mRadiusMax
152 | (8) `size_t` | mCount
160 | (1) `bool` | mIncludeDeadPlayers
161 | (1) `bool` | mIsPositionBound
162 | (1) `bool` | mDistanceFiltered
163 | (1) `bool` | mHaveDeltas
164 | (1) `bool` | mForcePlayer
165 | (1) `bool` | mIsExplicitIdSelector


### `CommandOutputPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (64) `CommandOriginData` | mOriginData
104 | (48) `CommandOutput` | mOutput


### `Cat::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Chicken::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `ContainerSizeChangeListener`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ContainerSizeChangeListener


### `CauldronBlock::spawnPotionParticles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CauldronBlock::spawnSplashParticles::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CompoundTagUpdaterBuilder`
Offset | Type | Name
-|-|-|-
0 | (8) `CompoundTagUpdater *` | mUpdater


### `ConduitBlockActor::_animateTick::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `CoralCrustFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `CircuitSceneGraph::PendingEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `BaseCircuitComponent *` | mRawComponentPtr
8 | (8) `std::unique_ptr<BaseCircuitComponent>` | mComponent
16 | (12) `BlockPos` | mPos


### `CommandPositionFloat`
Offset | Type | Name
-|-|-|-
0 | (16) `CommandPosition` | baseclass_0


### `commands::SoftEnum`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | name


### `CommandWildcardInt`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mIsWildcard
4 | (4) `int` | mValue


### `CommandSelector<Actor>`
Offset | Type | Name
-|-|-|-
0 | (168) `CommandSelectorBase` | baseclass_0


### `commands::Postfix`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | postfix


### `ChemistryIngredient`
Offset | Type | Name
-|-|-|-
0 | (136) `ItemInstance` | mItem


### `Core::FileStorageArea`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$FileStorageArea
8 | (16) `std::enable_shared_from_this<Core::FileStorageArea>` | baseclass_8
24 | (40) `Bedrock::Threading::RecursiveMutex` | mLock
64 | (24) `std::vector<Core::FileSystemImpl *>` | mAllTransactions
88 | (1) `bool` | mCanAttemptExtendSave
89 | (1) `bool` | mCachedFileUsageSize
96 | (64) `Core::FileStats` | mTransactionStats
160 | (64) `Core::FileStats` | mTotalStats
224 | (4) `Core::FileAccessType` | mAccessType
232 | (32) `Core::HeapPathBuffer` | mRootPath
264 | (24) `std::vector<Core::FileSystemImpl *>` | mWriteTransactions
288 | (32) `Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>::SubjectType` | mSubject
320 | (16) `std::shared_ptr<Core::FileStorageArea>` | mParent
336 | (104) `Core::StorageAreaState` | mState
440 | (1) `std::atomic_bool` | mFileIOSuspended
448 | (64) `Bedrock::Threading::ConditionVariableAny` | mResumeSignal
512 | (1) `bool` | mLoggingEnabled
520 | (16) `std::shared_ptr<Core::FlatFileManifestTracker>` | mManifestTracker
536 | (1) `bool` | mIsAccessedDirectly


### `Core::Observer<Core::FileStorageAreaObserver,Core::SingleThreadedLock>::SubjectType`
Offset | Type | Name
-|-|-|-
0 | (1) `Core::SingleThreadedLock` | mLock
8 | (24) `std::vector<Core::FileStorageAreaObserver *>` | mObservers


### `Core::SingleThreadedLock`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `Core::StorageAreaState`
Offset | Type | Name
-|-|-|-
0 | (40) `Bedrock::Threading::Mutex` | mMutex
40 | (32) `Core::HeapPathBuffer` | mStorageAreaRootPath
72 | (1) `std::atomic<bool>` | mIsExtendDiskSpaceEvent
73 | (1) `std::atomic<bool>` | mIsLowDiskSpaceWarning
74 | (1) `std::atomic<bool>` | mIsOutOfDiskSpaceError
75 | (1) `std::atomic<bool>` | mIsCriticalDiskError
80 | (24) `std::vector<Core::StorageAreaStateListener *>` | mListeners


### `Core::FileSystem::BasicFileData`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::HeapPathBuffer` | mPath
32 | (8) `Core::FileSize` | mSize


### `Core::FlatFileSystemImpl`
Offset | Type | Name
-|-|-|-
0 | (8) `Core::FileSystemImpl *` | mFileSystemImpl
8 | (16) `std::shared_ptr<Core::FlatFileManifestTracker>` | mFlatFileManifestTracker


### `Core::StorageAreasTree::TreeChild`
Offset | Type | Name
-|-|-|-
0 | (40) `HashedString` | mKey
40 | (8) `std::unique_ptr<Core::StorageAreasTree::TreeNode>` | mNode


### `ConsoleInputReader`
```
struct ConsoleInputReader
{
  SPSCQueue<std::string,512> mConsoleInput;
  std::atomic<bool> mReadConsole;
  Bedrock::Threading::Thread mConsoleThread;
};

```

### `ContentLogEndPoint`
```
struct __cppobj ContentLogEndPoint : Bedrock::LogEndPoint
{
};

```

### `CommandRegistry::ParseRule`
```
struct CommandRegistry::ParseRule
{
  CommandRegistry::NonTerminal nonTerminal;
  CommandRegistry::ProcessFunction process;
  CommandRegistry::SymbolVector derivation;
  CommandVersion versions;
};

```

### `CommandRegistry::ParseTable`
```
struct CommandRegistry::ParseTable
{
  CommandRegistry::ParseSet first;
  CommandRegistry::ParseSet follow;
  CommandRegistry::PredictTable predict;
};

```

### `CommandRegistry::OptionalParameterChain`
```
struct CommandRegistry::OptionalParameterChain
{
  int parameterCount;
  CommandRegistry::RuleIndex followingRuleIndex;
  CommandRegistry::Symbol paramSymbol;
};

```

### `CommandRegistry::Overload`
```
struct __attribute__((aligned(8))) CommandRegistry::Overload
{
  CommandVersion version;
  CommandRegistry::Overload::AllocFunction alloc;
  std::vector<CommandParameterData> params;
  int versionOffset;
};

```

### `Command`
```
struct __attribute__((aligned(4))) Command
{
  int (**_vptr$Command)(void);
  int mVersion;
  const CommandRegistry *mRegistry;
  int mCommandSymbol;
  CommandPermissionLevel mPermissionLevel;
  CommandFlag mFlags;
};

```

### `CommandRegistry::ConstrainedValue`
```
struct CommandRegistry::ConstrainedValue
{
  CommandRegistry::Symbol mValue;
  CommandRegistry::Symbol mEnum;
  std::vector<unsigned char> mConstraints;
};

```

### `CommandRegistry::SoftEnum`
```
struct CommandRegistry::SoftEnum
{
  std::string mName;
  std::vector<std::string> mValues;
};

```

### `Core::PathBuffer<std::string >`
```
struct Core::PathBuffer<std::string >
{
  std::string mContainer;
};

```

### `ContentLog`
```
struct ContentLog
{
  bool mEnabled;
  std::vector<ContentLogEndPoint *> mEndPoints;
  ThreadLocal<ThreadSpecificData> mThreadSpecificData;
  Bedrock::Threading::Mutex mEndpointMutex;
};

```

### `ContentLogFileEndPoint`
```
struct __cppobj __attribute__((aligned(4))) ContentLogFileEndPoint : ContentLogEndPoint
{
  std::unique_ptr<Core::OutputFileStream> mFileStream;
  Core::HeapPathBuffer mDebugLogDirectory;
  Core::HeapPathBuffer mFilePath;
  uint32_t mNumTimesOpened;
  bool mIsEnabled;
};

```

### `ClassroomModeListener`
```
struct __cppobj ClassroomModeListener : LevelListener
{
};

```

### `CommandContext`
```
struct __attribute__((aligned(8))) CommandContext
{
  std::string mCommand;
  Unique<CommandOrigin> mOrigin;
  int mVersion;
};

```

### `CompositePackSource`
```
struct __cppobj CompositePackSource : PackSource
{
  std::vector<PackSource *> mPackSources;
};

```

### `CommandOutputSender`
```
struct CommandOutputSender
{
  int (**_vptr$CommandOutputSender)(void);
  Automation::AutomationClient *mAutomationClient;
  std::function<void (AutomationCmdOutput &)> mEmplaceTestCommandOutputCallback;
};

```

### `Core::FileImpl`
```
struct __attribute__((aligned(8))) Core::FileImpl
{
  int (**_vptr$FileImpl)(void);
  Core::FileOpenMode mOpenMode;
  Core::FileSystemImpl *mpTransaction;
  bool mLoggingEnabled;
};

```

### `Core::FileSystemImpl`
```
struct Core::FileSystemImpl
{
  int (**_vptr$FileSystemImpl)(void);
  std::shared_ptr<Core::FileStorageArea> mpStorageArea;
  bool mLoggingEnabled;
  bool mTransactionEnded;
  Core::FileAccessType mAccessType;
  Core::FileStats mStats;
  Bedrock::Threading::Mutex mFileLock;
  std::vector<Core::FileImpl *> mFiles;
  Core::FlatFileSystemImpl mFlatFileSystem;
};

```

### `Core::PathContainerConversions<Core::StackString<char,1024> >`
```
struct Core::PathContainerConversions<Core::StackString<char,1024> >
{
  __int8 gap0[1];
};

```

### `CommandPropertyBag`
```
struct __cppobj CommandPropertyBag : PropertyBag
{
  int (**_vptr$CommandPropertyBag)(void);
};

```

### `ChangeSettingCommand`
```
struct __cppobj __attribute__((aligned(4))) ChangeSettingCommand : ServerCommand
{
  ChangeSettingCommand::Setting mSetting;
  Difficulty mDifficulty;
  int mIntValue;
  bool mBoolValue;
};

```

### `CommandMessage::MessageComponent`
```
struct CommandMessage::MessageComponent
{
  std::string string;
  std::unique_ptr<CommandSelector<Actor>> selection;
};

```

### `CommandMessage`
```
struct CommandMessage
{
  std::vector<CommandMessage::MessageComponent> mData;
};

```

### `Core::Observer<NetworkChangeObserver,std::mutex>::SubjectType`
```
typedef Core::Subject<NetworkChangeObserver,std::mutex> Core::Observer<NetworkChangeObserver,std::mutex>::SubjectType;

```

### `Core::Subject<NetworkChangeObserver,std::mutex>`
```
struct Core::Subject<NetworkChangeObserver,std::mutex>
{
  std::mutex mLock;
  std::vector<NetworkChangeObserver *> mObservers;
};

```

### `consumer_token_t`
```
typedef moodycamel::ConsumerToken consumer_token_t;

```

### `ClacksServer`
```
struct __cppobj __attribute__((aligned(8))) ClacksServer : com::mojang::clacks::protocol::Commands::Service
{
  NetworkAddress mAddress;
  Bedrock::Threading::Thread mClacksThread;
  std::unique_ptr<grpc::Server> mGrpcServer;
  ServerInstance *mServerInstance;
  PermissionsFile *mPermissionsFile;
  WhitelistFile *mWhitelistFile;
  DedicatedServer *mDeadicatedServer;
  std::chrono::seconds mWaitTimeout;
  std::atomic<com::mojang::clacks::protocol::SaveState> mSaveCommandState;
  std::vector<SnapshotFilenameAndLength> mSaveAllFileList;
  ServerMetricsImpl *mServerMetricsImpl;
  std::atomic<bool> mIsRunning;
};

```

### `com::mojang::clacks::protocol::Commands::Service`
```
struct __cppobj com::mojang::clacks::protocol::Commands::Service : grpc::Service
{
};

```

### `ClacksServer::ExecutionAndResult`
```
struct ClacksServer::ExecutionAndResult
{
  ResetEventObj execution;
  grpc::Status error;
};

```

### `com::mojang::clacks::protocol::Settings`
```
struct __attribute__((aligned(8))) com::mojang::clacks::protocol::Settings
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  com::mojang::clacks::protocol::Settings::SettingsUnion settings_;
  google::protobuf::internal::CachedSize _cached_size_;
  google::protobuf::uint32 _oneof_case_[1];
};

```

### `com::mojang::clacks::protocol::MetricReport`
```
struct com::mojang::clacks::protocol::MetricReport
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  com::mojang::clacks::protocol::MetricReport::MetricUnion metric_;
  google::protobuf::internal::CachedSize _cached_size_;
  google::protobuf::uint32 _oneof_case_[1];
};

```

### `com::mojang::clacks::protocol::Message`
```
struct __attribute__((aligned(8))) com::mojang::clacks::protocol::Message
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  google::protobuf::internal::ArenaStringPtr value_;
  google::protobuf::internal::CachedSize _cached_size_;
};

```

### `com::mojang::clacks::protocol::Commands`
```
struct com::mojang::clacks::protocol::Commands
{
  __int8 gap0[1];
};

```

### `com::mojang::clacks::protocol::PlayerAndMessage`
```
struct __attribute__((aligned(8))) com::mojang::clacks::protocol::PlayerAndMessage
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  com::mojang::clacks::protocol::Xuid *xuid_;
  com::mojang::clacks::protocol::Message *message_;
  google::protobuf::internal::CachedSize _cached_size_;
};

```

### `com::mojang::clacks::protocol::MetricReport_BandwithMetric`
```
struct __attribute__((aligned(8))) com::mojang::clacks::protocol::MetricReport_BandwithMetric
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  com::mojang::clacks::protocol::Xuid *xuid_;
  google::protobuf::int64 playerdeltabytessent_;
  google::protobuf::int64 playerdeltabytesreceived_;
  google::protobuf::int64 connectiontotalbytesreceived_;
  google::protobuf::int64 connectiontotalbytessent_;
  google::protobuf::internal::CachedSize _cached_size_;
};

```

### `com::mojang::clacks::protocol::MetricReport_LatencyMetric`
```
struct __attribute__((aligned(8))) com::mojang::clacks::protocol::MetricReport_LatencyMetric
{
  __int8 baseclass_0[8];
  google::protobuf::internal::InternalMetadataWithArena _internal_metadata_;
  com::mojang::clacks::protocol::Xuid *xuid_;
  google::protobuf::int64 latencyinns_;
  google::protobuf::int64 pinginns_;
  google::protobuf::internal::CachedSize _cached_size_;
};

```

### `com::mojang::clacks::protocol::Commands::Stub`
```
struct __cppobj com::mojang::clacks::protocol::Commands::Stub : com::mojang::clacks::protocol::Commands::StubInterface
{
  std::shared_ptr<grpc::ChannelInterface> channel_;
  com::mojang::clacks::protocol::Commands::Stub::experimental_async async_stub_;
  const grpc::internal::RpcMethod rpcmethod_listPlayer_;
  const grpc::internal::RpcMethod rpcmethod_kick_;
  const grpc::internal::RpcMethod rpcmethod_say_;
  const grpc::internal::RpcMethod rpcmethod_changeSettings_;
  const grpc::internal::RpcMethod rpcmethod_reloadOps_;
  const grpc::internal::RpcMethod rpcmethod_reloadPermissions_;
  const grpc::internal::RpcMethod rpcmethod_reloadWhitelist_;
  const grpc::internal::RpcMethod rpcmethod_saveHold_;
  const grpc::internal::RpcMethod rpcmethod_saveQuery_;
  const grpc::internal::RpcMethod rpcmethod_saveResume_;
  const grpc::internal::RpcMethod rpcmethod_saveState_;
  const grpc::internal::RpcMethod rpcmethod_stop_;
  const grpc::internal::RpcMethod rpcmethod_serverStarted_;
  const grpc::internal::RpcMethod rpcmethod_subscribeToMetrics_;
};

```

### `com::mojang::clacks::protocol::Commands::StubInterface`
```
struct com::mojang::clacks::protocol::Commands::StubInterface
{
  int (**_vptr$StubInterface)(void);
};

```

### `com::mojang::clacks::protocol::Commands::Stub::experimental_async`
```
struct __cppobj com::mojang::clacks::protocol::Commands::Stub::experimental_async : com::mojang::clacks::protocol::Commands::StubInterface::experimental_async_interface
{
  com::mojang::clacks::protocol::Commands::Stub *stub_;
};

```

### `com::mojang::clacks::protocol::Commands::StubInterface::experimental_async_interface`
```
struct com::mojang::clacks::protocol::Commands::StubInterface::experimental_async_interface
{
  int (**_vptr$experimental_async_interface)(void);
};

```

### `CommandBlockSystem`
```
struct __cppobj CommandBlockSystem : ITickingSystem
{
};

```

### `CompoundTagUpdater`
```
struct CompoundTagUpdater
{
  uint32_t mVersion;
  std::vector<std::function<bool (CompoundTagEditHelper &)>> mFilters;
  std::vector<std::function<void (CompoundTagEditHelper &)>> mUpdates;
};

```

### `CompoundTagUpdaterContext`
```
struct __attribute__((aligned(8))) CompoundTagUpdaterContext
{
  uint8_t mUpdaterVersion;
  std::vector<std::unique_ptr<CompoundTagUpdater>> mUpdaters;
  bool mIsSorted;
};

```

### `ClayFeature`
```
struct __cppobj __attribute__((aligned(8))) ClayFeature : Feature
{
  const int mRadius;
};

```

### `CactusFeature`
```
struct __cppobj CactusFeature : Feature
{
};

```

### `CentralSpikedFeature`
```
struct __cppobj CentralSpikedFeature : Feature
{
  const Block *mBlock;
};

```

### `CoralFeature`
```
struct __cppobj CoralFeature : Feature
{
};

```

### `CoralHangFeature`
```
struct __cppobj CoralHangFeature : Feature
{
};

```

### `CommandSelector<Player>`
```
struct __cppobj CommandSelector<Player> : CommandSelectorBase
{
};

```

### `ColumnCachedData`
```
struct ColumnCachedData
{
  int grassColor;
  int waterColor;
};

```

### `CircuitSystem`
```
struct __attribute__((aligned(8))) CircuitSystem
{
  bool mLockGraph;
  CircuitSceneGraph mSceneGraph;
  std::vector<CircuitSystem::LevelChunkTracking> mAddedLevelChunk;
  bool mHasBeenEvaluated;
};

```

### `CircuitSceneGraph`
```
struct CircuitSceneGraph
{
  CircuitSceneGraph::ComponentMap mAllComponents;
  CircuitComponentList mActiveComponents;
  CircuitSceneGraph::ComponentsPerPosMap mActiveComponentsPerChunk;
  CircuitSceneGraph::ComponentsPerPosMap mPowerAssociationMap;
  std::unordered_map<BlockPos,CircuitSceneGraph::PendingEntry> mPendingAdds;
  std::unordered_map<BlockPos,CircuitSceneGraph::PendingEntry> mPendingUpdates;
  std::unordered_map<BlockPos,std::vector<BlockPos>> mComponentsToReEvaluate;
  std::vector<CircuitSceneGraph::PendingEntry> mPendingRemoves;
};

```

### `CircuitSceneGraph::ComponentMap`
```
typedef std::unordered_map<BlockPos,std::unique_ptr<BaseCircuitComponent>> CircuitSceneGraph::ComponentMap;

```

### `CircuitSceneGraph::ComponentsPerPosMap`
```
typedef std::unordered_map<BlockPos,CircuitComponentList> CircuitSceneGraph::ComponentsPerPosMap;

```

### `CircuitSystem::LevelChunkTracking`
```
struct CircuitSystem::LevelChunkTracking
{
  BlockPos mChunkPos;
};

```

### `ChunkBuildOrderPolicyBase`
```
struct ChunkBuildOrderPolicyBase
{
  int (**_vptr$ChunkBuildOrderPolicyBase)(void);
};

```

### `ChunkViewSource`
```
struct __cppobj ChunkViewSource : ChunkSource
{
  ChunkSource::LoadMode mParentLoadMode;
  ChunkSourceView mArea;
  ChunkSource *mMainSource;
};

```

### `CanyonFeature`
```
struct __attribute__((aligned(8))) CanyonFeature
{
  int (**_vptr$CanyonFeature)(void);
  bool mAllowMegaRavines;
};

```

### `ClassID`
```
struct ClassID
{
  __int8 gap0[1];
};

```

### `ChestBlockActor`
```
struct __cppobj __attribute__((aligned(8))) ChestBlockActor : RandomizableBlockActorFillingContainer
{
  float mSpeed;
  bool mIsGlobalChest;
  bool mUsesLegacyBlockDetection;
  float mObstructionHeight;
  float mOpenness;
  float mOldOpenness;
  bool mIsOpen;
  int mTickInterval;
  __int8 mPairLead : 1;
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

### `Core::Observer<WebviewObserver,Core::SingleThreadedLock>::SubjectType`
```
typedef Core::Subject<WebviewObserver,Core::SingleThreadedLock> Core::Observer<WebviewObserver,Core::SingleThreadedLock>::SubjectType;

```

### `Core::Subject<WebviewObserver,Core::SingleThreadedLock>`
```
struct Core::Subject<WebviewObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<WebviewObserver *> mObservers;
};

```

### `Core::PathContainerConversions<std::string >`
```
struct Core::PathContainerConversions<std::string >
{
  __int8 gap0[1];
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
  ChalkboardSize mSize;
  bool mIsOnGround;
  bool mIsLocked;
  ActorUniqueID mOwner;
};

```

### `const_reverse_iterator`
```
typedef std::reverse_iterator<std::_Bit_const_iterator> const_reverse_iterator;

```

### `Container`
```
struct __attribute__((aligned(8))) Container
{
  int (**_vptr$Container)(void);
  ContainerType mContainerType;
  std::unordered_set<ContainerContentChangeListener *> mContentChangeListeners;
  std::unordered_set<ContainerSizeChangeListener *> mSizeChangeListeners;
  std::deque<std::function<void (Container &,int,const ItemStack &,const ItemStack &)>> mTransactionContextStack;
  std::string mName;
  bool mCustomName;
};

```

### `CompressedNetworkPeer`
```
struct __cppobj CompressedNetworkPeer : NetworkPeer
{
  std::string mSendBuffer;
  std::string mReceiveBuffer;
};

```

### `ClientToServerHandshakePacket`
```
struct __cppobj ClientToServerHandshakePacket : Packet
{
};

```

### `ClientCacheStatusPacket`
```
struct __cppobj __attribute__((aligned(4))) ClientCacheStatusPacket : Packet:288
{
  bool mEnabled;
};

```

### `ClientCacheBlobStatusPacket`
```
struct __cppobj ClientCacheBlobStatusPacket : Packet
{
  std::vector<unsigned long> mMissingIds;
  std::vector<unsigned long> mFoundIds;
};

```

### `ClientCacheMissResponsePacket`
```
struct __cppobj ClientCacheMissResponsePacket : Packet
{
  std::vector<std::shared_ptr<ClientBlobCache::Server::Blob>> mWriteMissingContent;
  std::unordered_map<unsigned long,std::string> mReceivedMissingContent;
};

```

### `CraftingEventPacket`
```
struct __cppobj CraftingEventPacket : Packet:288
{
  ContainerID mContainerId;
  int mContainerType;
  mce::UUID mRecipeId;
  std::vector<ItemStack> mInputItems;
  std::vector<ItemStack> mOutputItems;
};

```

### `CommandBlockUpdatePacket`
```
struct __cppobj __attribute__((aligned(2))) CommandBlockUpdatePacket : Packet:288
{
  NetworkBlockPosition mBlockPos;
  CommandBlockMode mMode;
  bool mRedstoneMode;
  bool mIsConditional;
  ActorRuntimeID mEntityId;
  std::string mCommand;
  std::string mLastOutput;
  std::string mName;
  int mTickDelay;
  bool mTrackOutput;
  bool mExecuteOnFirstTick;
  bool mIsBlock;
};

```

### `ClientBlobCache::Server::Blob`
```
struct ClientBlobCache::Server::Blob
{
  const ClientBlobCache::BlobId id;
  const std::string data;
};

```

### `ClientBlobCache::Server::ActiveTransfersManager::TransferTracker`
```
struct __attribute__((aligned(8))) ClientBlobCache::Server::ActiveTransfersManager::TransferTracker
{
  ClientBlobCache::Server::ActiveTransfersManager *mCache;
  const NetworkIdentifier mOwner;
  std::vector<ClientBlobCache::Server::ActiveTransfer> mTransfers;
  uint32_t mMaxConcurrentTransfers;
};

```

### `Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>`
```
struct Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
  int (**_vptr$Observer)(void);
  Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>::SubjectType *mpSubject;
};

```

### `Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>::SubjectType`
```
typedef Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock> Core::Observer<Social::XboxLiveUserObserver,Core::SingleThreadedLock>::SubjectType;

```

### `Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock>`
```
struct Core::Subject<Social::XboxLiveUserObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<Social::XboxLiveUserObserver *> mObservers;
};

```

### `ClassroomModeNetworkHandler`
```
struct __cppobj __attribute__((aligned(8))) ClassroomModeNetworkHandler : NetEventCallback
{
  Automation::AutomationClient *mAutomationClient;
  std::unique_ptr<RoleChecker> mRoleChecker;
  std::string mTenantId;
  std::string mLastRequestAddress;
  bool mIsDedicatedServer;
};

```

### `ComplexInventoryTransaction`
```
struct ComplexInventoryTransaction
{
  int (**_vptr$ComplexInventoryTransaction)(void);
  ComplexInventoryTransaction::Type mType;
  InventoryTransaction mTransaction;
};

```

### `Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>`
```
struct Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
  int (**_vptr$Observer)(void);
  Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>::SubjectType *mpSubject;
};

```

### `Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>::SubjectType`
```
typedef Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock> Core::Observer<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>::SubjectType;

```

### `Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>`
```
struct Core::Subject<Social::MultiplayerServiceObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<Social::MultiplayerServiceObserver *> mObservers;
};

```

### `CommandBlockActor`
```
struct __cppobj CommandBlockActor : BlockActor
{
  BaseCommandBlock mBaseCB;
  bool mPowered;
  bool mConditionMet;
  bool mRedstoneMode;
  bool mLastPerformedConditionalMode;
  bool mLastPerformedRedstoneMode;
  bool mExecuteFirstTickOnPlace;
  CommandBlockMode mLastPerformedCBMode;
};

```

### `ChemistryTableBlockActor`
```
struct __cppobj ChemistryTableBlockActor : BlockActor, Container
{
  std::unique_ptr<ActorUniqueID> mOpenedPlayer;
  std::unique_ptr<LabTableReaction> mCurReaction;
  std::unique_ptr<CraftableCompounds> mCraftableCompounds;
  ItemStack mItems[9];
  ItemStack mPendingReactionOutput;
  bool mShouldCombine;
  bool mIsTableTypeCached;
  ChemistryTableType mCachedTableType;
};

```

### `CommandDispatcher`
```
struct __cppobj CommandDispatcher : ICommandDispatcher
{
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

### `CanClimbDescription`
```
struct __cppobj CanClimbDescription : PropertyDescription
{
};

```

### `CanFlyDescription`
```
struct __cppobj CanFlyDescription : PropertyDescription
{
};

```

### `CanPowerJumpDescription`
```
struct __cppobj CanPowerJumpDescription : PropertyDescription
{
};

```

### `CollisionBoxDescription`
```
struct __cppobj CollisionBoxDescription : PropertyDescription
{
  Vec2 mBBDim;
};

```

### `Color2Description`
```
struct __cppobj __attribute__((aligned(8))) Color2Description : ColorDescription
{
};

```

### `ColorDescription`
```
struct __cppobj __attribute__((aligned(8))) ColorDescription : PropertyDescription
{
  PaletteColor mColorChoice;
};

```

### `CommandBlockDescription`
```
struct __cppobj __attribute__((aligned(8))) CommandBlockDescription : ComponentDescription
{
  int mCurrentTickCount;
  int mTicksPerCommand;
  bool mTicking;
};

```

### `ChestContainerManagerModel`
```
struct __cppobj ChestContainerManagerModel : LevelContainerManagerModel:1312
{
  BlockActorType mBlockActorType;
};

```

### `CompoundCreatorContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) CompoundCreatorContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `ChangeDimensionRequest`
```
struct ChangeDimensionRequest
{
  ChangeDimensionRequest::State mState;
  DimensionType mFromDimensionId;
  DimensionType mToDimensionId;
  Vec3 mPosition;
  bool mUsePortal;
  bool mRespawn;
  Unique<CompoundTag> mAgentTag;
};

```

### `CommandRawText`
```
struct CommandRawText
{
  std::string mText;
};

```

### `CommandFilePath`
```
struct CommandFilePath
{
  std::string mText;
};

```

### `CommandArea`
```
struct CommandArea
{
  std::unique_ptr<ChunkViewSource> mChunkSource;
  BlockSource mBlockSource;
};

```

### `ClientAutomationCommandOrigin`
```
struct __cppobj ClientAutomationCommandOrigin : CommandOrigin
{
  std::string mRequestId;
};

```

### `CommandRegistry::ParseSet`
```
typedef std::map<CommandRegistry::Symbol,std::vector<CommandRegistry::Symbol>> CommandRegistry::ParseSet;

```

### `CommandRegistry::PredictTable`
```
typedef std::map<std::pair<CommandRegistry::Symbol,CommandRegistry::Symbol>,int> CommandRegistry::PredictTable;

```

### `CommandRegistry::ParamVisitCallback`
```
typedef std::function<bool (const CommandParameterData &,const CommandOrigin &,const CommandRegistry::ParseToken *)> CommandRegistry::ParamVisitCallback;

```

### `CommandVersion::getVersionMapping::VersionPair`
```
typedef std::pair<SemVersion,CurrentCmdVersion> CommandVersion::getVersionMapping::VersionPair;

```

### `CommandFunctionEntry`
```
struct __cppobj CommandFunctionEntry : IFunctionEntry
{
  std::unique_ptr<Command> mCommand;
};

```

### `CustomScriptEventData`
```
struct __cppobj CustomScriptEventData : ScriptEventData
{
  Json::Value mData;
};

```

### `CauldronBlockActor`
```
struct __cppobj CauldronBlockActor : BlockActor, Container:1952
{
  int mPotionId;
  int mPotionType;
  bool mHasCustomColor;
  int mCustomColor;
  ItemStack mItems[10];
};

```

### `CauldronBlock`
```
struct __cppobj CauldronBlock : ActorBlock
{
};

```

### `Cat`
```
struct __cppobj Cat : Animal
{
  float mLieDownAmount;
  float mLieDownAmountLast;
  float mLieDownAmountTail;
  float mLieDownAmountTailLast;
};

```

### `Chicken`
```
struct __cppobj __attribute__((aligned(8))) Chicken : Animal
{
  float mFlap;
  float mOFlap;
  float mFlapSpeed;
  float mOFlapSpeed;
  float mFlapping;
};

```

### `Creeper`
```
struct __cppobj __attribute__((aligned(8))) Creeper : Monster
{
  int mSwell;
  int mOldSwell;
  int mSwellDir;
};

```

### `CaveSpider`
```
struct __cppobj CaveSpider : Spider
{
};

```

### `Control`
```
struct Control
{
  int (**_vptr$Control)(void);
};

```

### `CircleAroundAnchorGoal`
```
struct __cppobj CircleAroundAnchorGoal : Goal
{
  Mob *mMob;
  float mSpeedMod;
  FloatRange mRadiusRange;
  int mRadiusChangeChance;
  FloatRange mAboveTargetRange;
  FloatRange mHeightOffsetRange;
  int mHeightChangeChance;
  float mGoalRadiusSq;
  CircleAroundAnchorGoal::OptionalVec3 mAnchorPoint;
  float mCurRadius;
  float mCurHeight;
  float mClockwise;
  float mCurAngle;
};

```

### `ControlledByPlayerGoal`
```
struct __cppobj __attribute__((aligned(8))) ControlledByPlayerGoal : Goal
{
  Mob *mMob;
  float mSpeed;
};

```

### `ChargeAttackGoal`
```
struct __cppobj ChargeAttackGoal : Goal
{
  Mob *mMob;
};

```

### `ChargeHeldItemGoal`
```
struct __cppobj ChargeHeldItemGoal : Goal:96
{
  int mUsingTime;
  Mob *mMob;
  std::vector<ItemDescriptor> mItems;
};

```

### `ChannelTransform`
```
struct ChannelTransform
{
  ExpressionNode mXYZ[3];
  Vec3 mAxis;
  ChannelTransformAxisType mTransformDataType;
};

```

### `ComplexItem`
```
struct __cppobj ComplexItem : Item
{
};

```

### `CatchFireSubcomponent`
```
struct __cppobj __attribute__((aligned(4))) CatchFireSubcomponent : OnHitSubcomponent
{
  float mOnFireTime;
  bool mFireAffectedByGriefing;
};

```

### `ContainerModel`
```
struct __cppobj ContainerModel : ContainerContentChangeListener
{
  std::string mContainerStringName;
  const ContainerEnumName mContainerEnumName;
  std::vector<ContainerItemStack> mItems;
  std::vector<ItemInstance> mItemInstances;
  std::vector<std::function<void (int,const ItemStack &,const ItemStack &)>> mOnContainerChangedCallbacks;
  std::function<void (int,const ItemStack &,const ItemStack &)> mPlayerNotificationCallbacks;
  ContainerCategory mContainerCategory;
  std::vector<SlotData> mItemSource;
};

```

### `ContainerController`
```
struct __attribute__((aligned(8))) ContainerController
{
  int (**_vptr$ContainerController)(void);
  std::weak_ptr<ContainerModel> mContainerModel;
  bool mDrop;
};

```

### `ContainerEnumNameHasher`
```
struct ContainerEnumNameHasher
{
  __int8 gap0[1];
};

```

### `ContainerManagerModel`
```
struct __cppobj ContainerManagerModel : IContainerManager
{
  Player *mPlayer;
  std::vector<ContainerItemStack> mLastSlots;
  ContainerID mContainerId;
  ContainerType mContainerType;
  std::function<void (ContainerManagerModel &)> mInformControllerOfDestructionCallback;
  std::unordered_map<std::string,std::shared_ptr<ContainerModel>> mContainers;
};

```

### `ContainerFactory`
```
struct ContainerFactory
{
  __int8 gap0[1];
};

```

### `CreativeGroupInfo`
```
struct CreativeGroupInfo
{
  std::string mName;
  __int16 mIconId;
  __int16 mIconAux;
  Unique<CompoundTag> mIconUserData;
};

```

### `CameraItemComponent`
```
struct CameraItemComponent
{
  int (**_vptr$CameraItemComponent)(void);
  float mBlackBarsDuration;
  float mBlackBarsScreenRatio;
  float mShutterScreenRatio;
  float mShutterDuration;
  float mPictureDuration;
  float mSlideAwayDuration;
  bool mPlacingTripod;
  uint64_t mPlacingTripodClientTick;
  uint64_t mPlacingTripodServerTick;
  CameraCallbacks *mCallbacks;
};

```

### `ClockItem`
```
struct __cppobj ClockItem : Item
{
  int mAtlasWidth;
  int mAtlasHeight;
  TextureUVCoordinateSet mFrames[64];
};

```

### `CompassItem`
```
struct __cppobj CompassItem : Item
{
  int mAtlasWidth;
  int mAtlasHeight;
  TextureUVCoordinateSet mFrames[32];
};

```

### `CompoundItem`
```
struct __cppobj CompoundItem : ChemistryItem
{
};

```

### `ChemistryItem`
```
struct __cppobj ChemistryItem : Item
{
};

```

### `CreativeItemCategoryEnumHasher`
```
struct CreativeItemCategoryEnumHasher
{
  __int8 gap0[1];
};

```

### `CoalItem`
```
struct __cppobj CoalItem : Item
{
  TextureUVCoordinateSet m_charoalUV;
};

```

### `CarrotOnAStickItem`
```
struct __cppobj __attribute__((aligned(8))) CarrotOnAStickItem : Item
{
  bool mirrored;
};

```

### `CrossbowItem`
```
struct __cppobj CrossbowItem : RangedWeaponItem
{
  TextureUVCoordinateSet mFrame[5];
  const int mMaxDurability;
  const int mMaxMultiShots;
  const float mMultishotAngleDelta;
  const float mDefaultArrowPower;
};

```

### `CameraItem`
```
struct __cppobj CameraItem : Item
{
};

```

### `ClothBlockItem`
```
struct __cppobj ClothBlockItem : BlockItem
{
};

```

### `CoralFanBlockItem`
```
struct __cppobj CoralFanBlockItem : BlockItem
{
};

```

### `ChemistryAuxDataBlockItem`
```
struct __cppobj ChemistryAuxDataBlockItem : AuxDataBlockItem
{
};

```

### `CraftingContainer`
```
struct __cppobj __attribute__((aligned(8))) CraftingContainer : Container
{
  std::vector<ItemStack> mItems;
  int mWidth;
};

```

### `CrossbowEnchant`
```
struct __cppobj CrossbowEnchant : Enchant
{
};

```

### `Core::UnzipInternals`
```
struct Core::UnzipInternals
{
  unzFile mZipFile;
};

```

### `CustomTemperatureCategoryAttributes`
```
struct CustomTemperatureCategoryAttributes
{
  Biome::BiomeTempCategory mTemperatureCategory;
};

```

### `ConsumerComponent`
```
struct __cppobj ConsumerComponent : BaseCircuitComponent:480
{
  bool mSecondaryPowered;
  bool mPropagatePower;
  bool mPromotedToProducer;
  bool mAcceptHalfPulse;
};

```

### `ChemistryTableBlock`
```
struct __cppobj ChemistryTableBlock : ActorBlock
{
};

```

### `ComposterBlock`
```
struct __cppobj ComposterBlock : BlockLegacy
{
};

```

### `CakeBlock`
```
struct __cppobj CakeBlock : BlockLegacy
{
};

```

### `CompoundTagUpdaterBuilder::TagType<ByteTag>`
```
struct CompoundTagUpdaterBuilder::TagType<ByteTag>
{
  __int8 gap0[1];
};

```

### `CompoundTagUpdaterBuilder::TagType<IntTag>`
```
struct CompoundTagUpdaterBuilder::TagType<IntTag>
{
  __int8 gap0[1];
};

```

### `ComparatorBlockActor`
```
struct __cppobj ComparatorBlockActor : BlockActor:1632
{
  int mOutput;
};

```

### `ConduitBlockActor`
```
struct __cppobj ConduitBlockActor : BlockActor:1608
{
  bool mIsActive;
  bool mIsHunting;
  int mBlockRefreshCounter;
  uint64_t mNextAmbientSound;
  float mAnimationValue;
  float mRotation;
  int mRotationTickCount;
  int mWindLevel;
  int mEffectRange;
  ActorUniqueID mTarget;
  std::vector<BlockPos> mBlockPositions;
};

```

### `CampfireBlockActor`
```
struct __cppobj CampfireBlockActor : BlockActor
{
  ItemInstance mCookingItem[4];
  int mCookingTime[4];
  bool mWasLit;
  int mNextSmokeParticleTick;
};

```

### `Container:1952`
```
struct __attribute__((packed)) __attribute__((aligned(4))) Container:1952
{
  int (**_vptr$Container)(void);
  ContainerType mContainerType;
  _BYTE gap9[7];
  std::unordered_set<ContainerContentChangeListener *> mContentChangeListeners;
  std::unordered_set<ContainerSizeChangeListener *> mSizeChangeListeners;
  std::deque<std::function<void (Container &,int,const ItemStack &,const ItemStack &)>> mTransactionContextStack;
  std::string mName;
  bool mCustomName;
};

```

### `ChalkboardBlockActor::CachedLineData`
```
struct __attribute__((aligned(8))) ChalkboardBlockActor::CachedLineData
{
  std::string text;
  int lineLength;
};

```

### `CraftableCompounds`
```
struct CraftableCompounds
{
  int (**_vptr$CraftableCompounds)(void);
  std::unordered_map<std::string,ItemStack> mComponentsToCompound;
  std::unordered_map<int,std::vector<ItemStack>> mCompoundToComponents;
  std::unordered_map<std::string,LabTableReactionType> mComponentsToReaction;
  std::unordered_map<std::string,CompoundContainerType> mComponentsToContainerOverride;
};

```

### `ChestBlock`
```
struct __cppobj __attribute__((aligned(8))) ChestBlock : ActorBlock
{
  ChestBlock::ChestType mType;
};

```

### `CommandBlock`
```
struct __cppobj __attribute__((aligned(8))) CommandBlock : ActorBlock
{
  CommandBlockMode mCBMode;
};

```

### `ComparatorCapacitor`
```
struct ComparatorCapacitor
{
  __int8 baseclass_0[68];
  int mRearAnalogStrength;
  int mSideAnalogStrengthRight;
  int mSideAnalogStrengthLeft;
  int mOldStrength;
  ComparatorCapacitor::Mode mMode;
  int mRearStrength;
  int mSideStrengths;
  bool mHasAnalogBeenSet;
  CircuitComponentList mSideComponents;
};

```

### `ChestBlockActor:5192`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(1))) ChestBlockActor:5192 : RandomizableBlockActorFillingContainer
{
  float mSpeed;
  bool mIsGlobalChest;
  bool mUsesLegacyBlockDetection;
  _BYTE gap216[2];
  float mObstructionHeight;
  float mOpenness;
  float mOldOpenness;
  bool mIsOpen;
  _BYTE gap225[3];
  int mTickInterval;
  __int8 mPairLead : 1;
  __int8 mPairingChanged : 1;
  __int8 mAlongX : 1;
  __int8 mDeferredPairLoad : 1;
  __int8 mConverted : 1;
  _BYTE gap22D[3];
  int mDeferredPairX;
  int mDeferredPairZ;
  ChestBlockActor *mLargeChestPaired;
  BlockPos mLargeChestPairedPosition;
  bool mIsTrappedChest;
  bool mIsFindable;
  _BYTE gap24E[2];
  std::unordered_set<ActorUniqueID> mOpenedByIds;
  bool mNotifyPlayersOnChange;
};

```

### `ClothBlock`
```
struct __cppobj ClothBlock : BlockLegacy
{
};

```

### `CropBlock`
```
struct __cppobj CropBlock : BushBlock
{
};

```

### `CactusBlock`
```
struct __cppobj CactusBlock : BlockLegacy
{
};

```

### `ClayBlock`
```
struct __cppobj ClayBlock : BlockLegacy
{
};

```

### `CocoaBlock`
```
struct __cppobj CocoaBlock : BlockLegacy
{
};

```

### `CarrotBlock`
```
struct __cppobj CarrotBlock : CropBlock
{
};

```

### `ComparatorBlock`
```
struct __cppobj __attribute__((aligned(8))) ComparatorBlock : ActorBlock
{
  bool mOn;
};

```

### `ColoredBlock`
```
struct __cppobj ColoredBlock : BlockLegacy
{
};

```

### `ChorusFlowerBlock`
```
struct __cppobj ChorusFlowerBlock : BlockLegacy
{
};

```

### `ConcreteBlock`
```
struct __cppobj ConcreteBlock : BlockLegacy
{
};

```

### `ConcretePowderBlock`
```
struct __cppobj ConcretePowderBlock : HeavyBlock
{
};

```

### `ChorusPlantBlock`
```
struct __cppobj ChorusPlantBlock : BlockLegacy
{
};

```

### `CameraBlock`
```
struct __cppobj CameraBlock : BlockLegacy
{
};

```

### `ChemicalHeatBlock`
```
struct __cppobj ChemicalHeatBlock : BlockLegacy
{
};

```

### `ColoredTorchBlock`
```
struct __cppobj __attribute__((aligned(8))) ColoredTorchBlock : TorchBlock
{
  ColoredTorchColor mBaseColor;
};

```

### `Coral`
```
struct __cppobj Coral : BlockLegacy
{
};

```

### `CoralBlock`
```
struct __cppobj CoralBlock : BlockLegacy
{
};

```

### `CoralFan`
```
struct __cppobj CoralFan : BushBlock
{
};

```

### `CoralFanHang`
```
struct __cppobj CoralFanHang : CoralFan
{
};

```

### `ConduitBlock`
```
struct __cppobj ConduitBlock : ActorBlock
{
};

```

### `CartographyTableBlock`
```
struct __cppobj CartographyTableBlock : BlockLegacy
{
};

```

### `CampfireBlock`
```
struct __cppobj CampfireBlock : ActorBlock
{
};

```

### `ChunkSourceLookupMap`
```
typedef std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> ChunkSourceLookupMap;

```

### `ChunkSourceView`
```
typedef GridArea<std::shared_ptr<LevelChunk> > ChunkSourceView;

```

### `ChunkBuildOrderPolicy`
```
struct __cppobj __attribute__((aligned(8))) ChunkBuildOrderPolicy : ChunkBuildOrderPolicyBase
{
  std::unordered_map<unsigned int,ChunkPos> mPositionMap;
  SpinLock mChunkPosAsyncSpinLock;
  std::vector<ChunkPos> mChunkPosAsync;
  uint32_t mLastHandle;
};

```

### `CapacitorComponent`
```
struct __cppobj __attribute__((aligned(8))) CapacitorComponent : ProducerComponent
{
};

```

### `CrashHandler`
```
struct CrashHandler
{
  __int8 gap0[1];
};

```

### `CrashHelper`
```
struct CrashHelper
{
  __int8 gap0[1];
};

```

### `ContextAccessor::TypeBase`
```
struct ContextAccessor::TypeBase
{
  __int8 gap0[1];
};

```

### `ContextAccessor::TypeDerived<EntityContext>`
```
struct ContextAccessor::TypeDerived<EntityContext>
{
  EntityContext mData;
};

```

### `Crypto::Hash::HMAC`
```
struct __attribute__((aligned(8))) Crypto::Hash::HMAC
{
  std::unique_ptr<Crypto::Hash::IHash> mHash;
  std::string mKey;
  int mResultSize;
};

```

### `Command:240`
```
struct __attribute__((packed)) __attribute__((aligned(2))) Command:240
{
  int (**_vptr$Command)(void);
  int mVersion;
  _BYTE gapC[4];
  const CommandRegistry *mRegistry;
  int mCommandSymbol;
  CommandPermissionLevel mPermissionLevel;
  CommandFlag mFlags;
};

```

### `ClearCommand`
```
struct __cppobj ClearCommand : Command
{
  PlayerSelector mTargets;
  CommandItem mItem;
  int mData;
  int mMaxCount;
};

```

### `CloneCommand`
```
struct __cppobj __attribute__((aligned(8))) CloneCommand : Command
{
  CommandPosition mBegin;
  CommandPosition mEnd;
  CommandPosition mDestination;
  CloneCommand::MaskMode mMaskMode;
  CloneCommand::CloneMode mCloneMode;
  const Block *mBlock;
  int mData;
};

```

### `CloneCommand::execute::CloneBlockInfo`
```
struct CloneCommand::execute::CloneBlockInfo
{
  BlockPos mPos;
  const Block *mState;
  std::unique_ptr<CompoundTag> mTag;
};

```

### `CircleAroundAnchorGoal::OptionalVec3`
```
typedef std::optional<Vec3> CircleAroundAnchorGoal::OptionalVec3;

```

### `ConsumeItemDefinition`
```
struct __cppobj ConsumeItemDefinition : BehaviorDefinition
{
};

```

### `ConsumeItemNode`
```
struct __cppobj ConsumeItemNode : BehaviorNode:480
{
  bool mRightMouseDown;
  int mDelayTicks;
  int mDelayCounter;
};

```

### `CompositeDefinition`
```
struct __cppobj CompositeDefinition : BehaviorDefinition
{
  std::vector<std::unique_ptr<BehaviorDefinition>> mChildren;
};

```

### `CraftingInputContainerController`
```
struct __cppobj CraftingInputContainerController : CraftingContainerController
{
  std::vector<ContainerItemStack> mRecipeItems;
};

```

### `CraftingOutputContainerController`
```
struct __cppobj CraftingOutputContainerController : CraftingContainerController
{
  ContainerItemStack mRecipeItem;
};

```

### `CreativeContainerController`
```
struct __cppobj CreativeContainerController : ContainerController
{
};

```

### `CompoundCreatorInputContainerController`
```
struct __cppobj CompoundCreatorInputContainerController : ContainerController
{
};

```

### `ContainerController:200`
```
struct __attribute__((packed)) __attribute__((aligned(1))) ContainerController:200
{
  int (**_vptr$ContainerController)(void);
  std::weak_ptr<ContainerModel> mContainerModel;
  bool mDrop;
};

```

### `CartographyInputContainerController`
```
struct __cppobj CartographyInputContainerController : ContainerController
{
};

```

### `CraftingContainerController`
```
struct __cppobj CraftingContainerController : ContainerController
{
  const Recipe *mCurrentRecipe;
  bool mIs3x3Grid;
  bool mDisplayGhostItems;
  std::vector<ContainerItemStack> mGhostItems;
};

```

### `ChemistryBlockItem`
```
struct __cppobj ChemistryBlockItem : BlockItem
{
};

```

### `cg::ImageDescription`
```
struct cg::ImageDescription
{
  uint32_t mWidth;
  uint32_t mHeight;
  mce::TextureFormat mTextureFormat;
  cg::ColorSpace mColorSpace;
  bool mIsCubemap;
  uint32_t mArraySize;
};

```

### `ChemistryStickItem`
```
struct __cppobj __attribute__((aligned(8))) ChemistryStickItem : ChemistryItem
{
  int mMaxActiveTime;
};

```

### `ChemistryRecipes`
```
struct ChemistryRecipes
{
  __int8 gap0[1];
};

```

### `CompactionListenerEnv`
```
struct __cppobj CompactionListenerEnv : leveldb::EnvWrapper
{
  leveldb::Env *mTarget;
  Bedrock::Threading::Mutex mLock;
  bool mCompactionRunning;
  CompactionCallback mCompactionCallback;
};

```

### `CapacitorComponent:528`
```
struct __cppobj CapacitorComponent:528 : ProducerComponent:528
{
};

```

### `CapacitorComponent:544`
```
struct __cppobj __attribute__((aligned(4))) CapacitorComponent:544 : ProducerComponent:544
{
};

```

### `Core::ScopedLoadTimeSection`
```
struct Core::ScopedLoadTimeSection
{
  double mStartTime;
  Core::LoadTimeData mProfileData;
};

```

### `Core::LoadTimeData`
```
struct Core::LoadTimeData
{
  const std::string mName;
  int mScope;
  double mTotalTime;
};

```

### `Core::FileSystem_generic`
```
struct __cppobj Core::FileSystem_generic : Core::FileSystemImpl
{
};

```

### `Core::BasicDirectoryStorageArea<Core::FileSystem_generic>`
```
struct __cppobj __attribute__((aligned(8))) Core::BasicDirectoryStorageArea<Core::FileSystem_generic> : Core::FileStorageArea
{
};

```

### `Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock>`
```
struct Core::Subject<Core::FileStorageAreaObserver,Core::SingleThreadedLock>
{
  Core::SingleThreadedLock mLock;
  std::vector<Core::FileStorageAreaObserver *> mObservers;
};

```

### `Core::FlatFileManifestTracker`
```
struct Core::FlatFileManifestTracker
{
  Bedrock::Threading::Mutex mManifestsLock;
  std::unordered_map<std::string,std::shared_ptr<Core::FlatFileManifest>> mManifestMap;
  std::set<std::string> mManifestNames;
};

```

### `Core::LoadTimeProfiler`
```
struct __attribute__((aligned(8))) Core::LoadTimeProfiler
{
  std::vector<Core::ScopedLoadTimeSection *> mSections;
  unsigned int mCurrentFrame;
  std::vector<Core::LoadTimeData> mFinishedSections;
  __attribute__((packed)) __attribute__((aligned(1))) Core::OutputFileStream mLogFile;
  bool mEnabled;
  bool mCloseLogOnUpdate;
};

```

### `ContextMessage`
```
struct ContextMessage
{
  LogArea mArea;
  LogLevel mLevel;
  std::string mMessage;
};

```

### `Core::DiskAccessDiagnostics`
```
struct Core::DiskAccessDiagnostics
{
  std::chrono::_V2::steady_clock::duration mLogInterval;
  std::chrono::_V2::steady_clock::time_point mLastLogTime;
  double mWriteMBPerMinuteHWM;
  double mWriteCountPerMinuteHWM;
};

```

### `Core::DiskAccessTracker`
```
struct Core::DiskAccessTracker
{
  std::chrono::_V2::steady_clock::duration mBytesWrittenInterval;
  std::chrono::_V2::steady_clock::duration mNumWritesInterval;
  std::vector<Core::DiskAccessTracker::WriteOperation> mWriteOperations;
  std::set<Core::PathBuffer<std::string >> mIgnoredPaths;
  std::unique_ptr<Core::DiskAccessDiagnostics> mDiskAccessDiagnostics;
  Bedrock::Threading::Mutex mMutex;
};

```

### `Core::FlatFileManifest`
```
struct Core::FlatFileManifest
{
  std::unordered_map<std::string,unsigned long> mManifestEntriesMap;
  std::vector<Core::FlatFileManifestInfo> mManifestInfoVector;
  size_t mEntriesCount;
  uint64_t mVersion;
  Core::HeapPathBuffer mManifestPath;
};

```

### `Core::FileSystem::copyDirectoryAndContentsRecursivelyWithLimit::$F457DC01F16FBA362CDB9DA581FCE3BD`
```
struct Core::FileSystem::copyDirectoryAndContentsRecursivelyWithLimit::$F457DC01F16FBA362CDB9DA581FCE3BD
{
  bool *directoriesCreated;
  std::vector<Core::PathBuffer<std::string >> *directories;
  std::vector<Core::FileSystem::BasicFileData> *files;
  Core::FileSize *currentFileBytesWritten;
};

```

### `Core::FileSystem::copyFlatFile::$F457DC01F16FBA362CDB9DA581FCE3BD`
```
struct Core::FileSystem::copyFlatFile::$F457DC01F16FBA362CDB9DA581FCE3BD
{
  bool *directoriesCreated;
  std::vector<Core::PathBuffer<std::string >> *directories;
  std::vector<Core::FileSystem::BasicFileData> *files;
  Core::FileSize *currentFileBytesWritten;
};

```

### `Core::FileSystem`
```
struct Core::FileSystem
{
  __int8 gap0[1];
};

```

### `Core::BufferedFileOperations`
```
struct Core::BufferedFileOperations
{
  __int8 gap0[1];
};

```

### `Core::FlatFileOperations`
```
struct Core::FlatFileOperations
{
  __int8 gap0[1];
};

```

### `Core::FlatFile`
```
struct __cppobj Core::FlatFile : Core::FileImpl
{
  std::unique_ptr<Core::FileImpl> mFlatFile;
  Core::HeapPathBuffer mRequestedPath;
  Core::FileSize mFileSize;
  Core::FileSize mSeekPos;
};

```

### `Core::FullCopyFileOperations`
```
struct Core::FullCopyFileOperations
{
  __int8 gap0[1];
};

```

### `Core::File_c`
```
struct __cppobj Core::File_c : Core::FileImpl
{
  FILE *mpFile;
  Core::HeapPathBuffer mPath;
};

```

### `Core::String`
```
struct Core::String
{
  __int8 gap0[1];
};

```

### `Core::Profile::ProfileMultiSectionCPU`
```
struct Core::Profile::ProfileMultiSectionCPU
{
  __int8 gap0[1];
};

```

### `Core::Profile::ProfileMultiSectionCPU::ProfileSectionSuspend`
```
struct Core::Profile::ProfileMultiSectionCPU::ProfileSectionSuspend
{
  __int8 gap0[1];
};

```

### `Core::Profile::FileCounters`
```
struct Core::Profile::FileCounters
{
  uint64_t requests;
  uint64_t retries;
  uint64_t retrySuccess;
  uint64_t failures;
};

```

### `cmsghdr`
```
struct cmsghdr
{
  size_t cmsg_len;
  int cmsg_level;
  int cmsg_type;
  unsigned __int8 __cmsg_data[];
};

```

### `com::mojang::clacks::protocol::EmptyDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::EmptyDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Empty> _instance;
};

```

### `com::mojang::clacks::protocol::MessageDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::MessageDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Message> _instance;
};

```

### `com::mojang::clacks::protocol::XuidDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::XuidDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Xuid> _instance;
};

```

### `com::mojang::clacks::protocol::PlayerNameDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::PlayerNameDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerName> _instance;
};

```

### `com::mojang::clacks::protocol::PlayerInfoDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::PlayerInfoDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerInfo> _instance;
};

```

### `com::mojang::clacks::protocol::PlayerListDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::PlayerListDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerList> _instance;
};

```

### `com::mojang::clacks::protocol::PlayerAndMessageDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::PlayerAndMessageDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerAndMessage> _instance;
};

```

### `com::mojang::clacks::protocol::SettingsDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::SettingsDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Settings> _instance;
  int difficultysetting_;
  int cheatssetting_;
};

```

### `com::mojang::clacks::protocol::LevelFileAndSizeDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::LevelFileAndSizeDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::LevelFileAndSize> _instance;
};

```

### `com::mojang::clacks::protocol::SaveQueryResultDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::SaveQueryResultDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveQueryResult> _instance;
};

```

### `com::mojang::clacks::protocol::SaveStateResultDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::SaveStateResultDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveStateResult> _instance;
};

```

### `com::mojang::clacks::protocol::MetricReport_BandwithMetricDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::MetricReport_BandwithMetricDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_BandwithMetric> _instance;
};

```

### `com::mojang::clacks::protocol::MetricReport_LatencyMetricDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::MetricReport_LatencyMetricDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_LatencyMetric> _instance;
};

```

### `com::mojang::clacks::protocol::MetricReportDefaultTypeInternal`
```
struct com::mojang::clacks::protocol::MetricReportDefaultTypeInternal
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport> _instance;
  const com::mojang::clacks::protocol::MetricReport_BandwithMetric *bandwith_;
  const com::mojang::clacks::protocol::MetricReport_LatencyMetric *latency_;
  google::protobuf::int64 ticktime_;
};

```

