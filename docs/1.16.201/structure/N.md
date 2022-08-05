# N
### `NotifyManagerClient`
Offset | Type | Name
-|-|-|-
0 | (232) `NotifyManager` | baseclass_0


### `NotifyManager`
Offset | Type | Name
-|-|-|-
0 | (8) `NotifyManager_vtbl *` | __vftable
8 | (1) `bool` | _nextDtZero
16 | (64) `std::unordered_map<std::string,std::list<std::shared_ptr<NotifyHandler>>>` | mTempAddMap
80 | (64) `std::unordered_map<std::string,std::list<std::shared_ptr<NotifyHandler>>>` | mTempDelMap
144 | (64) `std::unordered_map<std::string,std::list<std::shared_ptr<NotifyHandler>>>` | mActiveMap
208 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | lastPushTickTm
216 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | timePassed
224 | (8) `std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > >` | lastEngineTickTm


### `NotifyManagerServer`
Offset | Type | Name
-|-|-|-
0 | (232) `NotifyManager` | baseclass_0
232 | (8) `std::chrono::duration<__int64,std::ratio<1,1000000000> >` | mLastFrameTime


### `NetworkWorldInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `WorldInfo` | baseclass_0
8 | (32) `std::string` | mPlayerCount
40 | (32) `std::string` | mOwnerName
72 | (32) `std::string` | mOwnerXuid
104 | (32) `std::string` | mWorldName
136 | (32) `std::string` | mGameType
168 | (32) `std::string` | mVersion
200 | (208) `ExternalServer` | mExternalServer
408 | (304) `PingedCompatibleServer` | mRemoteServer
712 | (472) `Social::MultiplayerGameInfo` | mFriendGame
1184 | (16) `std::shared_ptr<ThirdPartyServer>` | mThirdPartyServer


### `NewType<unsigned char>`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | value


### `NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>::()::__l2::<lambda_86aa690d2a07e32c745202fcad9767d8>`
Offset | Type | Name
-|-|-|-


### `NetworkChunkPublisher::sendQueuedChunks::__l2::<lambda_94ae8e063655f414397d243cf2bdb40c>`
Offset | Type | Name
-|-|-|-


### `NullSoundPlayer`
Offset | Type | Name
-|-|-|-
0 | (24) `SoundPlayerInterface` | baseclass_0


### `NewType<int>`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | value


### `NetherLightTextureImageBuilder::AmbientLevels`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | height
4 | (4) `float` | ambient


### `NetworkIdentifier`
Offset | Type | Name
-|-|-|-
0 | (16) `RakNet::RakNetGUID` | mGuid
16 | (128) `sockaddr_storage` | mSock
144 | (4) `NetworkIdentifier::Type` | mType


### `NullLogger`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Logger` | baseclass_0


### `NamedPipeObject`
Offset | Type | Name
-|-|-|-
0 | (8) `NamedPipeObject_vtbl *` | __vftable
8 | (32) `std::string` | recvBuffer
40 | (8) `void *` | hPipe
48 | (24) `std::vector<std::string>` | packages


### `NewType<__int64>`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | value


### `NetworkBlockPosition`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | baseclass_0


### `NavigationComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAvoidDamageBlocks
1 | (1) `bool` | mAvoidPortals
2 | (1) `bool` | mAvoidSun
3 | (1) `bool` | mAvoidWater
4 | (1) `bool` | mCanBreach
5 | (1) `bool` | mCanFloat
6 | (1) `bool` | mCanPathOverLava
7 | (1) `bool` | mCanWalkInLava
8 | (1) `bool` | mCanJump
9 | (1) `bool` | mCanOpenDoors
10 | (1) `bool` | mCanOpenIronDoors
11 | (1) `bool` | mCanPassDoors
12 | (1) `bool` | mCanSink
16 | (4) `int` | mMaxIteration
20 | (1) `bool` | mNavByScript
21 | (1) `bool` | mConfirmDest
22 | (1) `bool` | mIsAmphibious
23 | (1) `bool` | mIsFollowingRivers
24 | (1) `bool` | mHasEndPathRadius
25 | (1) `bool` | mHasDestination
28 | (4) `int` | mTick
32 | (4) `int` | mTickTimeout
36 | (4) `int` | mLastStuckCheck
40 | (4) `float` | mEndPathRadiusSqr
44 | (4) `float` | mSpeed
48 | (4) `float` | mTerminationThreshold
52 | (12) `Vec3` | mLastStuckCheckPosition
64 | (12) `Vec3` | mTargetOffset
80 | (8) `std::unique_ptr<PathNavigation>` | mNavigation
88 | (8) `std::unique_ptr<Path>` | mPath


### `NinePatchFactory`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::TextureGroup *` | textures
8 | (56) `ResourceLocation` | mResourceLocation
64 | (4) `int` | width
68 | (4) `int` | height


### `NinesliceInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `ImageInfo` | mTopLeft
32 | (32) `ImageInfo` | mTopRight
64 | (32) `ImageInfo` | mBottomLeft
96 | (32) `ImageInfo` | mBottomRight
128 | (8) `glm::tvec2<float,0>` | mUVScale
136 | (24) `std::vector<ImageInfo>` | mLeft
160 | (24) `std::vector<ImageInfo>` | mTop
184 | (24) `std::vector<ImageInfo>` | mRight
208 | (24) `std::vector<ImageInfo>` | mBottom
232 | (24) `std::vector<ImageInfo>` | mMiddle


### `NestedButtonScreenController::setUpCallbacksForNestedButtonInCollection::__l2::<lambda_f718c084a1f26651d2ecf46c8f151872>`
Offset | Type | Name
-|-|-|-
0 | (8) `NestedButtonScreenController *const` | __this
8 | (64) `std::function<int __cdecl(UIPropertyBag &)>` | indexFunc


### `NpcComponent`
Offset | Type | Name
-|-|-|-
0 | (8) `NpcComponent_vtbl *` | __vftable
8 | (4) `int` | mCurrentSkin
12 | (36) `NpcGUIOffset` | mPortraitOffsets
48 | (36) `NpcGUIOffset` | mPickerOffsets
88 | (24) `std::vector<SkinData>` | mNPCSkins
112 | (16) `Json::Value` | mNPCData
128 | (24) `std::vector<std::unique_ptr<NpcAction>>` | mActions
152 | (40) `std::optional<std::string >` | mInteractText
192 | (64) `std::function<std::string __cdecl(std::string const &)>` | mInteractTextFilter
256 | (8) `std::unique_ptr<NpcI18nObserver>` | mNpcI18nObserver


### `NpcGUIOffset`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mTranslation
12 | (12) `Vec3` | mRotation
24 | (12) `Vec3` | mScale


### `NewType<std::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | value


### `NameTagInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mPrefix
32 | (32) `std::string` | mPrefixColor
64 | (32) `std::string` | mNameColor
96 | (32) `std::string` | mSuffixColor
128 | (32) `std::string` | mSuffix
160 | (1) `bool` | mEnable
161 | (1) `bool` | mRenderNameColor


### `NetworkChunkInserter::PendingChunk`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | sequenceID
8 | (8) `std::unique_ptr<LevelChunk>` | chunk


### `NameTagRenderObject`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mNameTag
32 | (16) `std::shared_ptr<mce::Mesh>` | mMesh
48 | (8) `mce::MaterialPtr *` | mTagMat
56 | (8) `mce::MaterialPtr *` | mTextMatOverride
64 | (16) `mce::Color` | mTagColor
80 | (16) `mce::Color` | mTextColor
96 | (12) `glm::tvec3<float,0>` | mPos


### `NameTagRenderObjectCollection`
Offset | Type | Name
-|-|-|-
0 | (40) `std::vector<NameTagRenderObject,LinearAllocator<NameTagRenderObject> >` | mNameTags


### `NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>::()::__l2::KillListData`
Offset | Type | Name
-|-|-|-
0 | (152) `NetworkIdentifier` | id
152 | (8) `unsigned __int64` | index


### `NetworkComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `EntityNetId` | mEntityNetId


### `NameableDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<NameAction>` | mNameActions
24 | (320) `DefinitionTrigger` | mDefaultActionTrigger
344 | (1) `bool` | mAlwaysShow
345 | (1) `bool` | mAllowNameTagRenaming


### `NamedMolangScript`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mName
48 | (216) `ExpressionNode` | mScript


### `NewBlockID`
Offset | Type | Name
-|-|-|-
0 | (2) `NewType<unsigned short>` | baseclass_0


### `NewType<unsigned short>`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | value


### `NetworkHookAdapter::handleBreakVConnRequest::__l13::<lambda_5e83fe1dfa301b636a4c9a66ea9c3390>`
Offset | Type | Name
-|-|-|-
0 | (8) `NetworkHookAdapter *const` | __this
8 | (152) `const NetworkIdentifier` | source
160 | (64) `const VConnectionPacket` | packet


### `NetherFortressPiece`
Offset | Type | Name
-|-|-|-
0 | (40) `StructurePiece` | baseclass_0


### `NumberFieldWidths`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | n_lpadding
8 | (8) `__int64` | n_prefix
16 | (8) `__int64` | n_spadding
24 | (8) `__int64` | n_rpadding
32 | (1) `char` | sign
40 | (8) `__int64` | n_sign
48 | (8) `__int64` | n_grouped_digits
56 | (8) `__int64` | n_decimal
64 | (8) `__int64` | n_remainder
72 | (8) `__int64` | n_digits
80 | (8) `__int64` | n_min_width


### `NVSDK_NGX_D3D12_DLSS_Eval_Params`
Offset | Type | Name
-|-|-|-
0 | (24) `NVSDK_NGX_D3D12_Feature_Eval_Params` | Feature
24 | (8) `ID3D12Resource *` | pInDepth
32 | (8) `ID3D12Resource *` | pInMotionVectors
40 | (4) `float` | InJitterOffsetX
44 | (4) `float` | InJitterOffsetY
48 | (8) `NVSDK_NGX_Dimensions` | InRenderSubrectDimensions
56 | (4) `int` | InReset
60 | (4) `float` | InMVScaleX
64 | (4) `float` | InMVScaleY
72 | (8) `ID3D12Resource *` | pInTransparencyMask
80 | (8) `ID3D12Resource *` | pInExposureTexture
88 | (8) `ID3D12Resource *` | pInReduceGhostMask
96 | (8) `NVSDK_NGX_Coordinates` | InColorSubrectBase
104 | (8) `NVSDK_NGX_Coordinates` | InDepthSubrectBase
112 | (8) `NVSDK_NGX_Coordinates` | InMVSubrectBase
120 | (8) `NVSDK_NGX_Coordinates` | InTranslucencySubrectBase
128 | (8) `NVSDK_NGX_Coordinates` | InReduceGhostSubrectBase
136 | (8) `NVSDK_NGX_Coordinates` | InOutputSubrectBase
144 | (4) `float` | InPreExposure
148 | (4) `int` | InIndicatorInvertXAxis
152 | (4) `int` | InIndicatorInvertYAxis
160 | (128) `NVSDK_NGX_D3D12_GBuffer` | GBufferSurface
288 | (4) `NVSDK_NGX_ToneMapperType` | InToneMapperType
296 | (8) `ID3D12Resource *` | pInMotionVectors3D
304 | (8) `ID3D12Resource *` | pInIsParticleMask
312 | (8) `ID3D12Resource *` | pInAnimatedTextureMask
320 | (8) `ID3D12Resource *` | pInDepthHighRes
328 | (8) `ID3D12Resource *` | pInPositionViewSpace
336 | (4) `float` | InFrameTimeDeltaInMsec
344 | (8) `ID3D12Resource *` | pInRayTracingHitDistance
352 | (8) `ID3D12Resource *` | pInMotionVectorsReflections


### `NVSDK_NGX_D3D12_Feature_Eval_Params`
Offset | Type | Name
-|-|-|-
0 | (8) `ID3D12Resource *` | pInColor
8 | (8) `ID3D12Resource *` | pInOutput
16 | (4) `float` | InSharpness


### `NVSDK_NGX_Dimensions`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | Width
4 | (4) `unsigned int` | Height


### `NVSDK_NGX_Coordinates`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | X
4 | (4) `unsigned int` | Y


### `NVSDK_NGX_D3D12_GBuffer`
Offset | Type | Name
-|-|-|-
0 | (128) `ID3D12Resource *[16]` | pInAttrib


### `NVSDK_NGX_DLSS_Create_Params`
Offset | Type | Name
-|-|-|-
0 | (20) `NVSDK_NGX_Feature_Create_Params` | Feature
20 | (4) `int` | InFeatureCreateFlags
24 | (1) `bool` | InEnableOutputSubrects


### `NVSDK_NGX_Feature_Create_Params`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | InWidth
4 | (4) `unsigned int` | InHeight
8 | (4) `unsigned int` | InTargetWidth
12 | (4) `unsigned int` | InTargetHeight
16 | (4) `NVSDK_NGX_PerfQuality_Value` | InPerfQualityValue


### `NetworkPeer`
```
struct __cppobj NetworkPeer
{
  NetworkPeer_vtbl *__vftable /*VFT*/;
  std::shared_ptr<NetworkPeer> mPeer;
};

```

### `NetworkPeer::NetworkStatus`
```
struct NetworkPeer::NetworkStatus
{
  NetworkPeer::NetworkLoad mLoad;
  int mCurrentPing;
  int mAveragePing;
  int mApproximateMaxBps;
  float mCurrentPacketLoss;
  float mAveragePacketLoss;
  unsigned __int64 mTotalBytesReceived;
  unsigned __int64 mTotalBytesSent;
};

```

### `NetworkPeer_vtbl`
```
struct /*VFT*/ NetworkPeer_vtbl
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

### `NetworkSuspendResumeListener`
```
struct __cppobj __declspec(align(8)) NetworkSuspendResumeListener
{
  NetworkSuspendResumeListener_vtbl *__vftable /*VFT*/;
  NetworkSuspendResumeListener::State mState;
};

```

### `NetworkSuspendResumeListener_vtbl`
```
struct /*VFT*/ NetworkSuspendResumeListener_vtbl
{
  void (__fastcall *~NetworkSuspendResumeListener)(NetworkSuspendResumeListener *this);
  void (__fastcall *onSuspend)(NetworkSuspendResumeListener *this);
  void (__fastcall *onResume)(NetworkSuspendResumeListener *this);
};

```

### `NetworkPacketRecorder`
```
struct __cppobj NetworkPacketRecorder : NetworkPeer
{
  bool mRecording;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPacketTime;
  Core::File mFile;
};

```

### `NetworkPacketRecorder_vtbl`
```
struct /*VFT*/ NetworkPacketRecorder_vtbl
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

### `NetworkHandler::Connection`
```
struct __cppobj NetworkHandler::Connection
{
  NetworkIdentifier mId;
  NetworkHandler::Connection::Type mType;
  std::weak_ptr<NetworkPacketRecorder> mNetworkPacketRecorder;
  std::weak_ptr<EncryptedNetworkPeer> mEncryptedPeer;
  std::weak_ptr<BatchedNetworkPeer> mBatchedPeer;
  std::shared_ptr<NetworkPeer> mPeer;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastPacketTime;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mClosedTime;
  bool mShouldCloseConnection;
  bool mDisconnected;
  std::bitset<2> mPausedChannels;
  std::queue<std::string> mResumedPackets;
  std::array<std::vector<std::string>,2> mPausedPackets;
};

```

### `NetEventCallback`
```
struct __cppobj NetEventCallback
{
  NetEventCallback_vtbl *__vftable /*VFT*/;
};

```

### `NetworkStackLatencyPacket`
```
const struct __cppobj __declspec(align(8)) NetworkStackLatencyPacket : Packet
{
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > createTime;
  bool fromServer;
};

```

### `NetworkStackLatencyPacket_vtbl`
```
struct /*VFT*/ NetworkStackLatencyPacket_vtbl
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

### `NetworkSettingsPacket`
```
const struct __cppobj __declspec(align(8)) NetworkSettingsPacket : Packet
{
  unsigned __int16 mCompressionThreshold;
};

```

### `NetworkSettingsPacket_vtbl`
```
struct /*VFT*/ NetworkSettingsPacket_vtbl
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

### `NpcRequestPacket`
```
const struct __cppobj __declspec(align(8)) NpcRequestPacket : Packet
{
  ActorRuntimeID mId;
  NpcRequestPacket::RequestType mType;
  std::string mActions;
  unsigned __int8 mActionIndex;
};

```

### `NpcRequestPacket_vtbl`
```
struct /*VFT*/ NpcRequestPacket_vtbl
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

### `NetworkChunkPublisherUpdatePacket`
```
const struct __cppobj NetworkChunkPublisherUpdatePacket : Packet
{
  BlockPos mPosition;
  unsigned int mRadius;
};

```

### `NetworkChunkPublisherUpdatePacket_vtbl`
```
struct /*VFT*/ NetworkChunkPublisherUpdatePacket_vtbl
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

### `NetworkIdentifierWithSubId`
```
struct __cppobj __declspec(align(8)) NetworkIdentifierWithSubId
{
  NetworkIdentifier id;
  unsigned __int8 subClientId;
};

```

### `NewType<std::string >`
```
struct __cppobj NewType<std::string >
{
  std::string value;
};

```

### `NetworkHandler`
```
struct __cppobj __declspec(align(8)) NetworkHandler : Social::IGameConnectionInfoProvider, RakNetInstance::ConnectionCallbacks, RakPeerHelper::IPSupportInterface, LocalConnector::ConnectionCallbacks, NetworkSuspendResumeListener
{
  std::unique_ptr<RakNetInstance> mRakNetInstance;
  std::unique_ptr<LocalConnector> mLocalConnector;
  std::unique_ptr<RakNetServerLocator> mRakNetServerLocator;
  std::unique_ptr<UPNPInterface> mUPnPInterface;
  bool mConnectionDelayErase;
  std::recursive_mutex mConnectionsMutex;
  std::vector<std::unique_ptr<NetworkHandler::Connection>> mConnections;
  std::shared_mutex mSendStreamMutex;
  std::unordered_map<NetworkIdentifier,NetworkHandler::Connection *> mConnectionMap;
  unsigned __int64 mCurrentConnection;
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > mReceiveTask;
  std::unique_ptr<TaskGroup> mReceiveTaskGroup;
  PacketObserver *mPacketObserver;
  Scheduler *mMainThread;
  std::string mReceiveBuffer;
  NetworkIdentifier mHostingPlayerId;
  unsigned __int8 mHostingPlayerSubId;
  std::string mSendBuffer;
  BinaryStream mSendStream;
  std::unique_ptr<ResourcePackTransmissionManager> mResourcePackTransmissionManager;
  std::unique_ptr<NetworkHandler::IncomingPacketQueue> mIncomingPackets[4];
  bool mUseIPv6Only;
  unsigned __int16 mDefaultGamePort;
  unsigned __int16 mDefaultGamePortv6;
  bool mUseLocalConnector;
  bool mIsNetSafeAndFast;
  std::shared_ptr<NetworkHookAdapter> mHookAdapter;
  std::shared_ptr<NetworkHookAdapter> mBackupHookAdapter;
  bool mIsNetWorkGame;
  bool mIsScriptHandler;
  std::unique_ptr<NetworkPacketEventCoordinator> mPacketEventCoordinator;
  std::unique_ptr<NetworkStatistics> mNetworkStatistics;
  std::unique_ptr<PacketViolationHandler> mPacketViolationHandler;
  unsigned __int16 mCompressionThreshold;
};

```

### `NetworkPacketEventListener`
```
struct __cppobj NetworkPacketEventListener
{
  NetworkPacketEventListener_vtbl *__vftable /*VFT*/;
};

```

### `NetworkPacketEventListener_vtbl`
```
struct /*VFT*/ NetworkPacketEventListener_vtbl
{
  void (__fastcall *~NetworkPacketEventListener)(NetworkPacketEventListener *this);
  EventResult (__fastcall *onPacketReceivedFrom)(NetworkPacketEventListener *this, const PacketHeader *, const Packet *);
};

```

### `NavButtonComponent`
```
struct __cppobj __declspec(align(4)) NavButtonComponent : StoreUIComponent
{
  std::string mNavButtonName;
  std::string mImageId;
  std::string mGroupName;
  StoreCatalogCategory mCategory;
  std::string mButtonId;
  NavButtonLinksTo mNavButtonLinksTo;
  bool mButtonSizeIsFill;
};

```

### `NavButtonComponent_vtbl`
```
struct /*VFT*/ NavButtonComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `NavButtonSectionComponent`
```
struct __cppobj __declspec(align(8)) NavButtonSectionComponent : StoreUIComponent
{
  std::vector<std::shared_ptr<StoreVisualStyle>> mNavButtonVisualStyles;
  std::string mGroupName;
  bool mButtonSizeIsFill;
};

```

### `NavButtonSectionComponent_vtbl`
```
struct /*VFT*/ NavButtonSectionComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `NetworkChunkSubscriber`
```
struct __cppobj NetworkChunkSubscriber
{
  BlockPos mLastChunkUpdatePosition;
  unsigned int mHandleForChunkBuildOrderUpdates;
  unsigned int mBlockRadiusLimit;
  std::unique_ptr<ChunkViewSource> mSource;
};

```

### `NavigationDescription`
```
struct __cppobj __declspec(align(8)) NavigationDescription : ComponentDescription
{
  std::string mNavigationType;
  bool mIsAmphibious;
  bool mAvoidSun;
  bool mCanPassDoors;
  bool mCanOpenDoors;
  bool mCanOpenIronDoors;
  bool mCanBreakDoors;
  bool mAvoidWater;
  bool mAvoidDamageBlocks;
  bool mCanFloat;
  bool mCanSink;
  bool mCanPathOverLava;
  bool mCanWalkInLava;
  bool mAvoidPortals;
  bool mCanWalk;
  bool mCanSwim;
  bool mCanBreach;
  bool mCanJump;
  bool mUsingDoorAnnotations;
  bool mCanPathFromAir;
};

```

### `NavigationDescription_vtbl`
```
struct /*VFT*/ NavigationDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NetworkHandler::IncomingPacketQueue`
```
struct __cppobj NetworkHandler::IncomingPacketQueue
{
  NetEventCallback *mCallbacksObj;
  std::mutex mMutex;
};

```

### `NetworkHookAdapter`
```
struct __cppobj NetworkHookAdapter : std::enable_shared_from_this<NetworkHookAdapter>
{
  NetworkHookAdapter_vtbl *__vftable /*VFT*/;
  bool mIsConnectedOrHost;
  bool mIsGameServerHook;
  unsigned int mHostPlayerUid;
  NetworkHandler *mGameHandler;
  NetworkHandler *mLobbyHandler;
  std::map<NetworkIdentifier,unsigned int> mNetID2UID;
  std::map<unsigned int,std::shared_ptr<HookNetworkPeer>> mHookPeerMap;
};

```

### `NetworkHookAdapter_vtbl`
```
struct /*VFT*/ NetworkHookAdapter_vtbl
{
  void (__fastcall *~NetworkHookAdapter)(NetworkHookAdapter *this);
};

```

### `NetworkPacketEventCoordinator`
```
struct __cppobj NetworkPacketEventCoordinator : EventCoordinator<NetworkPacketEventListener>
{
};

```

### `NetworkStatistics::OverviewStats`
```
struct NetworkStatistics::OverviewStats
{
  unsigned int sentBytesUnpacked;
  unsigned int sentBytesPacked;
  unsigned int receivedBytesUnpacked;
  unsigned int receivedBytesPacked;
};

```

### `NetworkStatistics::PacketStats`
```
struct __cppobj NetworkStatistics::PacketStats
{
  unsigned int id;
  unsigned int sentNum;
  unsigned int sentBytes;
  unsigned int receivedNum;
  unsigned int receivedBytes;
  unsigned int handledPackets;
};

```

### `NetworkStatistics`
```
struct __cppobj NetworkStatistics : PacketObserver
{
  const TrackerType mType;
  NetworkHandler *mNetworkHandler;
  int mTicks;
  NetworkStatistics::OverviewStats mTotalOverview;
  std::unordered_map<int,NetworkStatistics::PacketStats> mTotalPacketStats;
  std::vector<NetworkStatistics::PacketStats> mTotalCSVPacketStats;
  std::unordered_map<int,NetworkStatistics::PacketStats> mCurrentPacketStats;
  std::unordered_map<unsigned __int64,std::string> mCurrentSourceNetworkIdentifierStrings;
  std::unordered_map<unsigned __int64,std::string> mCurrentTargetNetworkIdentifierStrings;
  std::array<std::string,255> mPacketNames;
  NetworkStatistics::OverviewStats mCurrentOverview;
  std::vector<NetworkStatistics::OverviewStats> mLastSeconds;
  long double mStartSeconds;
  std::mutex mRakNetStatsReadingLock;
  RakNet::RakNetStatistics mRakNetStatsReading;
  std::function<bool __cdecl(RakNet::RakNetStatistics &)> mGetRakNetStatsReading;
  std::unique_ptr<Core::OutputFileStream> mCSVFile;
  Core::Profile::CounterTokenMicroProfile mUserBytesPerSecSentCounterToken;
  Core::Profile::CounterTokenMicroProfile mActualBytesPerSecSentCounterToken;
  Core::Profile::CounterTokenMicroProfile mActualBytesPerSecReceivedCounterToken;
  Core::Profile::CounterTokenMicroProfile mUserBytesTotalSentCounterToken;
  Core::Profile::CounterTokenMicroProfile mActualBytesTotalSentCounterToken;
  Core::Profile::CounterTokenMicroProfile mActualBytesTotalReceivedCounterToken;
  Core::Profile::CounterTokenMicroProfile mPacketLossPercentagePerSecCounterToken;
  Core::Profile::CounterTokenMicroProfile mPacketLossPercentageTotalCounterToken;
};

```

### `NetworkStatistics_vtbl`
```
struct /*VFT*/ NetworkStatistics_vtbl
{
  void (__fastcall *~PacketObserver)(PacketObserver *this);
  void (__fastcall *packetSentTo)(PacketObserver *this, const NetworkIdentifier *, const Packet *, unsigned int);
  void (__fastcall *packetReceivedFrom)(PacketObserver *this, const NetworkIdentifier *, const Packet *, unsigned int);
  void (__fastcall *dataSentTo)(PacketObserver *this, const NetworkIdentifier *, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *dataReceivedFrom)(PacketObserver *this, const NetworkIdentifier *, const std::string *);
};

```

### `NetworkHandler_vtbl`
```
struct /*VFT*/ NetworkHandler_vtbl
{
  void (__fastcall *~IGameConnectionInfoProvider)(Social::IGameConnectionInfoProvider *this);
  const Social::GameConnectionInfo *(__fastcall *getConnectionInfo)(Social::IGameConnectionInfoProvider *this);
};

```

### `NavigationClimbDescription`
```
struct __cppobj NavigationClimbDescription : NavigationDescription
{
};

```

### `NavigationClimbDescription_vtbl`
```
struct /*VFT*/ NavigationClimbDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationFloatDescription`
```
struct __cppobj NavigationFloatDescription : NavigationDescription
{
};

```

### `NavigationFloatDescription_vtbl`
```
struct /*VFT*/ NavigationFloatDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationFlyDescription`
```
struct __cppobj NavigationFlyDescription : NavigationDescription
{
};

```

### `NavigationFlyDescription_vtbl`
```
struct /*VFT*/ NavigationFlyDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationHoverDescription`
```
struct __cppobj NavigationHoverDescription : NavigationDescription
{
};

```

### `NavigationHoverDescription_vtbl`
```
struct /*VFT*/ NavigationHoverDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationGenericDescription`
```
struct __cppobj NavigationGenericDescription : NavigationDescription
{
};

```

### `NavigationGenericDescription_vtbl`
```
struct /*VFT*/ NavigationGenericDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationSwimDescription`
```
struct __cppobj __declspec(align(8)) NavigationSwimDescription : NavigationDescription
{
  bool mUsingWander;
  bool mAllowRiverFollow;
  float mSteeringDamping;
  float mMinDepth;
  float mMaxDepth;
  float mTerrainAvoidDist;
  float mLookAheadDist;
  float mCenteredThres;
};

```

### `NavigationSwimDescription_vtbl`
```
struct /*VFT*/ NavigationSwimDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NavigationWalkDescription`
```
struct __cppobj NavigationWalkDescription : NavigationDescription
{
};

```

### `NavigationWalkDescription_vtbl`
```
struct /*VFT*/ NavigationWalkDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `NetheriteArmorEquippedListener`
```
struct __cppobj NetheriteArmorEquippedListener : ActorEventListener
{
};

```

### `NetheriteArmorEquippedListener_vtbl`
```
struct /*VFT*/ NetheriteArmorEquippedListener_vtbl
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

### `NetworkChangeObserver`
```
struct __cppobj NetworkChangeObserver : Core::Observer<NetworkChangeObserver,std::mutex>
{
};

```

### `NetworkChangeObserver_vtbl`
```
struct /*VFT*/ NetworkChangeObserver_vtbl
{
  void (__fastcall *~Observer<NetworkChangeObserver,std::mutex>)(Core::Observer<NetworkChangeObserver,std::mutex> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<NetworkChangeObserver,std::mutex> *this);
  void (__fastcall *onNetworkConfigurationChanged)(NetworkChangeObserver *this);
};

```

### `NetworkDebugManager::Tracker`
```
struct __cppobj __declspec(align(8)) NetworkDebugManager::Tracker
{
  std::mutex mCurrentStatLock;
  TrackerStat mCurrentStat;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastUpdate;
  std::vector<TrackerStat> mStats;
  unsigned int mLastSampleNum;
};

```

### `NetworkDebugManager`
```
struct __cppobj NetworkDebugManager : Bedrock::EnableNonOwnerReferences
{
  std::array<NetworkDebugManager::Tracker,4> mTrackers;
  TrackerType mRenderGraphMode;
  std::set<NetworkStatistics *> mStatistics;
};

```

### `NetworkChunkInserter`
```
struct __cppobj NetworkChunkInserter
{
  ClientNetworkHandler *mHandler;
  unsigned __int64 mChunkSequenceIDCounter;
  unsigned __int64 mNextChunkSequenceID;
  MovePriorityQueue<NetworkChunkInserter::PendingChunk,std::greater<NetworkChunkInserter::PendingChunk> > mChunksPendingInsertion;
};

```

### `NibblePair`
```
const struct NibblePair
{
  unsigned __int8 first : 4;
  unsigned __int8 second : 4;
};

```

### `NavigateToGameScreenProgressHandler`
```
struct __cppobj __declspec(align(8)) NavigateToGameScreenProgressHandler : ProgressHandler
{
  _BYTE state[4];
};

```

### `NavigateToGameScreenProgressHandler_vtbl`
```
struct /*VFT*/ NavigateToGameScreenProgressHandler_vtbl
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

### `NewOffersQuery`
```
struct __cppobj NewOffersQuery : SearchQuery
{
};

```

### `NbtIo`
```
struct __cppobj NbtIo
{
};

```

### `NetworkChunkSource`
```
struct __cppobj NetworkChunkSource : ChunkSource
{
  std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> mChunkMap;
  std::vector<SyncChunkPosPacket> mNewComingChunkPosPackets;
};

```

### `NetworkChunkSource_vtbl`
```
struct /*VFT*/ NetworkChunkSource_vtbl
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

### `NetherWastesMoodSoundPlayer`
```
struct __cppobj NetherWastesMoodSoundPlayer
{
};

```

### `NullSecureStorage`
```
struct __cppobj NullSecureStorage : SecureStorage
{
};

```

### `NullSecureStorage_vtbl`
```
struct /*VFT*/ NullSecureStorage_vtbl
{
  void (__fastcall *~SecureStorage)(SecureStorage *this);
  bool (__fastcall *add)(SecureStorage *this, const std::string *, const std::string *);
  bool (__fastcall *addOrUpdate)(SecureStorage *this, const std::string *, const std::string *);
  bool (__fastcall *remove)(SecureStorage *this, const std::string *);
  bool (__fastcall *get)(SecureStorage *this, const std::string *, std::string *);
};

```

### `NUMPARSE`
```
struct NUMPARSE
{
  int cDig;
  unsigned int dwInFlags;
  unsigned int dwOutFlags;
  int cchUsed;
  int nBaseShift;
  int nPwr10;
};

```

### `NOTIFY_USER_POWER_SETTING`
```
struct NOTIFY_USER_POWER_SETTING
{
  _GUID Guid;
};

```

### `netent`
```
struct netent
{
  char *n_name;
  char **n_aliases;
  __int16 n_addrtype;
  unsigned int n_net;
};

```

### `NotifyHandler`
```
struct __cppobj __declspec(align(8)) NotifyHandler
{
  NotifyHandler_vtbl *__vftable /*VFT*/;
  int m_handleId;
  std::string m_funcName;
  bool mIsEnable;
};

```

### `NotifyManager_vtbl`
```
struct /*VFT*/ NotifyManager_vtbl
{
  void (__fastcall *~NotifyManager)(NotifyManager *this);
  bool (__fastcall *checkThread)(NotifyManager *this);
  void (__fastcall *pushTick)(NotifyManager *this, __int64);
  void (__fastcall *pushTickUpdate)(NotifyManager *this);
  void (__fastcall *_dispatchTick)(NotifyManager *this);
};

```

### `NotifyManagerClient_vtbl`
```
struct /*VFT*/ NotifyManagerClient_vtbl
{
  void (__fastcall *~NotifyManager)(NotifyManager *this);
  bool (__fastcall *checkThread)(NotifyManager *this);
  void (__fastcall *pushTick)(NotifyManager *this, __int64);
  void (__fastcall *pushTickUpdate)(NotifyManager *this);
  void (__fastcall *_dispatchTick)(NotifyManager *this);
};

```

### `NetworkChunkPublisher`
```
struct __cppobj NetworkChunkPublisher
{
  NetworkChunkPublisher_vtbl *__vftable /*VFT*/;
  Level *mLevel;
  NetworkHandler *mNetworkHandler;
  NetworkIdentifier mOwner;
  ClientBlobCache::Server::ActiveTransfersManager *mClientCache;
  unsigned __int8 mSubClientId;
  BlockPos mLastChunkUpdatePosition;
  unsigned int mLastChunkUpdateRadius;
  unsigned int mHandleForChunkBuildOrderUpdates;
  int mChunksSentSinceStart;
  std::unique_ptr<ChunkViewSource> mSource;
  std::function<void __cdecl(buffer_span_mut<std::shared_ptr<LevelChunk> >,buffer_span<unsigned int>)> mAddCallback;
  std::string mCacheSerializeBuffer;
  std::unordered_map<ChunkPositionAndDimension,std::weak_ptr<LevelChunk>> mQueuedChunks;
};

```

### `NetworkChunkPublisher_vtbl`
```
struct /*VFT*/ NetworkChunkPublisher_vtbl
{
  void (__fastcall *~NetworkChunkPublisher)(NetworkChunkPublisher *this);
};

```

### `NetworkStatMetrics`
```
struct __cppobj NetworkStatMetrics
{
  unsigned int sentPackets;
  unsigned int sentBytes;
  unsigned int receivedPackets;
  unsigned int receivedBytes;
};

```

### `NotifyManagerServer_vtbl`
```
struct /*VFT*/ NotifyManagerServer_vtbl
{
  void (__fastcall *~NotifyManager)(NotifyManager *this);
  bool (__fastcall *checkThread)(NotifyManager *this);
  void (__fastcall *pushTick)(NotifyManager *this, __int64);
  void (__fastcall *pushTickUpdate)(NotifyManager *this);
  void (__fastcall *_dispatchTick)(NotifyManager *this);
};

```

### `NinePatchLayer::CachedQuad`
```
struct NinePatchLayer::CachedQuad
{
  float x0;
  float x1;
  float y0;
  float y1;
  float z;
  float u0;
  float u1;
  float v0;
  float v1;
};

```

### `NinePatchLayer`
```
struct __cppobj NinePatchLayer : ScreenRenderer
{
  NinePatchLayer_vtbl *__vftable /*VFT*/;
  float w;
  float h;
  NinePatchDescription desc;
  mce::TexturePtr texture;
  int excluded;
  NinePatchLayer::CachedQuad quads[9];
};

```

### `NinePatchLayer_vtbl`
```
struct /*VFT*/ NinePatchLayer_vtbl
{
  void (__fastcall *~NinePatchLayer)(NinePatchLayer *this);
};

```

### `NinePatchDescription`
```
struct __cppobj NinePatchDescription
{
  float u0;
  float u1;
  float u2;
  float u3;
  float v0;
  float v1;
  float v2;
  float v3;
  float w;
  float e;
  float n;
  float s;
  int imgW;
  int imgH;
};

```

### `NameTagRenderer`
```
struct __cppobj NameTagRenderer : MinecraftUICustomRenderer
{
  std::string mNameTagText;
  std::string mFilteredText;
  mce::Color mTextColor;
  mce::Color mBackgroundColor;
};

```

### `NameTagRenderer_vtbl`
```
struct /*VFT*/ NameTagRenderer_vtbl
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

### `Node`
```
struct __cppobj Node
{
  std::function<enum ui::ViewRequest __cdecl(unsigned int,std::string const &,int)> mOnEnter;
  std::function<enum ui::ViewRequest __cdecl(unsigned int,std::string const &,int)> mOnExit;
};

```

### `NestedButtonScreenController`
```
struct __cppobj NestedButtonScreenController : ScreenController
{
  std::string mFirstControlName;
  bool mFocusFirst;
  bool mNestedContentVisible;
  int mSelectedIndex;
  unsigned int mBaseButtonId;
  std::vector<unsigned int> mIgnoredControls;
};

```

### `NestedButtonScreenController_vtbl`
```
struct /*VFT*/ NestedButtonScreenController_vtbl
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
};

```

### `NoInvitesOrJoiningScreenController`
```
struct __cppobj NoInvitesOrJoiningScreenController : MinecraftScreenController
{
};

```

### `NoInvitesOrJoiningScreenController_vtbl`
```
struct /*VFT*/ NoInvitesOrJoiningScreenController_vtbl
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

### `NoLicenseScreenController`
```
struct __cppobj NoLicenseScreenController : MinecraftScreenController
{
};

```

### `NoLicenseScreenController_vtbl`
```
struct /*VFT*/ NoLicenseScreenController_vtbl
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

### `NoWifiWarningScreenController`
```
struct __cppobj NoWifiWarningScreenController : MinecraftScreenController
{
};

```

### `NoWifiWarningScreenController_vtbl`
```
struct /*VFT*/ NoWifiWarningScreenController_vtbl
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

### `NpcAction`
```
struct __cppobj NpcAction
{
  NpcAction_vtbl *__vftable /*VFT*/;
  const NpcActionType mType;
  NpcActionMode mMode;
  std::string mButtonName;
  std::string mEvaluatedButtonName;
  std::string mText;
  std::optional<std::string > mEvaluatedText;
};

```

### `NpcAction_vtbl`
```
struct /*VFT*/ NpcAction_vtbl
{
  void (__fastcall *~NpcAction)(NpcAction *this);
  Json::Value *(__fastcall *toJson)(NpcAction *this, Json::Value *result);
  bool (__fastcall *fromJson)(NpcAction *this, const Json::Value *);
};

```

### `NpcInteractScreenController`
```
struct __cppobj NpcInteractScreenController : ClientInstanceScreenController
{
  Player *mPlayer;
  ActorUniqueID mActorId;
  NpcInteractScreenController::Section mVisibleSection;
  int mMaxSkinsPerRow;
  int mStartSkinIndex;
  int mMaxSkinButtonIndex;
  int mMaxSkinIndex;
  int mSelectedSkinIndex;
  int mHoverSkin;
  int mMaximizedEditIndex;
  std::unique_ptr<DeferredTextObject> mDeferredNameText;
  std::unique_ptr<DeferredTextObject> mDeferredInteractText;
  std::vector<std::pair<DeferredTextObject,DeferredTextObject>> mDeferredActionTexts;
};

```

### `NpcInteractScreenController_vtbl`
```
struct /*VFT*/ NpcInteractScreenController_vtbl
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

### `NpcComponent_vtbl`
```
struct /*VFT*/ NpcComponent_vtbl
{
  void (__fastcall *~NpcComponent)(NpcComponent *this);
};

```

### `NpcI18nObserver`
```
struct __cppobj NpcI18nObserver : I18nObserver
{
  NpcComponent *mOwner;
  Actor *mActor;
};

```

### `NpcI18nObserver_vtbl`
```
struct /*VFT*/ NpcI18nObserver_vtbl
{
  void (__fastcall *~Observer<I18nObserver,Core::SingleThreadedLock>)(Core::Observer<I18nObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<I18nObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onLanguageChanged)(I18nObserver *this, const std::string *, bool);
  void (__fastcall *onLanguageKeywordsLoadedFromPack)(I18nObserver *this, const PackManifest *);
  void (__fastcall *onLanguagesLoaded)(I18nObserver *this);
};

```

### `NpcUrlAction`
```
struct __cppobj NpcUrlAction : NpcAction
{
};

```

### `NpcUrlAction_vtbl`
```
struct /*VFT*/ NpcUrlAction_vtbl
{
  void (__fastcall *~NpcAction)(NpcAction *this);
  Json::Value *(__fastcall *toJson)(NpcAction *this, Json::Value *result);
  bool (__fastcall *fromJson)(NpcAction *this, const Json::Value *);
};

```

### `NpcCommandAction::SavedCommand`
```
struct __cppobj __declspec(align(8)) NpcCommandAction::SavedCommand
{
  std::string mCommandLine;
  std::unique_ptr<Command> mCommand;
  int mVersion;
};

```

### `NpcCommandAction`
```
struct __cppobj NpcCommandAction : NpcAction
{
  std::vector<NpcCommandAction::SavedCommand> mCommands;
};

```

### `NpcCommandAction_vtbl`
```
struct /*VFT*/ NpcCommandAction_vtbl
{
  void (__fastcall *~NpcAction)(NpcAction *this);
  Json::Value *(__fastcall *toJson)(NpcAction *this, Json::Value *result);
  bool (__fastcall *fromJson)(NpcAction *this, const Json::Value *);
};

```

### `NpcInteractScreenController::_addNewDeferredButtonTexts::__l27::<lambda_525972a55d1f265793f219cebda19565>`
```
struct __cppobj NpcInteractScreenController::_addNewDeferredButtonTexts::__l27::<lambda_525972a55d1f265793f219cebda19565>
{
  NpcInteractScreenController *const __this;
  unsigned __int64 actionIndex;
};

```

### `NpcInteractScreenController::_addNewDeferredButtonTexts::__l27::<lambda_5979e78b14d99a72e640ac7a1490967a>`
```
struct __cppobj NpcInteractScreenController::_addNewDeferredButtonTexts::__l27::<lambda_5979e78b14d99a72e640ac7a1490967a>
{
  NpcInteractScreenController *const __this;
  unsigned __int64 actionIndex;
};

```

### `NpcInteractScreenController::_performAction::__l16::<lambda_770c8bde188452f9dd915d451b120383>`
```
struct __cppobj __declspec(align(8)) NpcInteractScreenController::_performAction::__l16::<lambda_770c8bde188452f9dd915d451b120383>
{
  NpcInteractScreenController *const __this;
  int index;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_685132e4215fce5d6b0e5251f3fff374>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_685132e4215fce5d6b0e5251f3fff374>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_bd50889f0f8efbf1910ec3665fab9da6>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_bd50889f0f8efbf1910ec3665fab9da6>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_f9dc8265b0e290a3b9979321e6f98210>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_f9dc8265b0e290a3b9979321e6f98210>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_918f49358adec11c427318acb5d69f83>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_918f49358adec11c427318acb5d69f83>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_c2e417e5496db5e00549a0c1c7657df9>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_c2e417e5496db5e00549a0c1c7657df9>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_9cc7365efe2ecd15773c5e96154585c0>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_9cc7365efe2ecd15773c5e96154585c0>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_1b11e5bdefb9cfebd326408a82e32cc9>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_1b11e5bdefb9cfebd326408a82e32cc9>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_961bd95fcd582e4bbf5c0414148176ab>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_961bd95fcd582e4bbf5c0414148176ab>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_d50efe909a7c46e7687e0b3a232473ba>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_d50efe909a7c46e7687e0b3a232473ba>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_38ce483024813d3823a3ac425c8f3b4f>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_38ce483024813d3823a3ac425c8f3b4f>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_28f724f63f22111fcc66aa3c85134d52>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_28f724f63f22111fcc66aa3c85134d52>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_27b60f1c49a81525a15a80133af6e6c5>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_27b60f1c49a81525a15a80133af6e6c5>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_6b93d3f1b7924a3692e51f0a818a2aa3>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_6b93d3f1b7924a3692e51f0a818a2aa3>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_9ffaf4d7b653b6efe16a30a56024a344>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_9ffaf4d7b653b6efe16a30a56024a344>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_98dd1895ad58be4fd0643ba408f3dc9b>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_98dd1895ad58be4fd0643ba408f3dc9b>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_bf814a0438fe0cf5a9d127c9d3fbc2e7>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_bf814a0438fe0cf5a9d127c9d3fbc2e7>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_5f7a42ab3172a17486bd8c065939826a>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_5f7a42ab3172a17486bd8c065939826a>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_27126e782ce13cc59b9148c91d336520>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_27126e782ce13cc59b9148c91d336520>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_3d87a45349c82392988892f1aa6201d4>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_3d87a45349c82392988892f1aa6201d4>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_bbd7a451a770d6ad1104aee1de332f62>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_bbd7a451a770d6ad1104aee1de332f62>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_c4f01a600a557aae90fd29dc866bc693>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_c4f01a600a557aae90fd29dc866bc693>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_551f4af8bd75ecee9d5b1320adf1cbac>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_551f4af8bd75ecee9d5b1320adf1cbac>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_ce4df114df64c7ea79640edf13f8035e>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_ce4df114df64c7ea79640edf13f8035e>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_2f9ed62f6fbe1445c08b4da73602ec87>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_2f9ed62f6fbe1445c08b4da73602ec87>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_b7f1b4cbf605dd4eb95d8a9c52ca36fb>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_b7f1b4cbf605dd4eb95d8a9c52ca36fb>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_6b2f551d84bdc8e3c9679231c50a02e3>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_6b2f551d84bdc8e3c9679231c50a02e3>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_ce31bf8ec73dc59d148c0b13005b77ea>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_ce31bf8ec73dc59d148c0b13005b77ea>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_76e75e1f87ca49bb70bfd42ceed335d9>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_76e75e1f87ca49bb70bfd42ceed335d9>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_dc7c55d4bb3f780ccc8c0b5828296abc>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_dc7c55d4bb3f780ccc8c0b5828296abc>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_b64b97281b0f0f98fea045f927cb3214>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_b64b97281b0f0f98fea045f927cb3214>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_8b0c4a6b6ced70ce383d81cc6b2ca2d2>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_8b0c4a6b6ced70ce383d81cc6b2ca2d2>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerBindings::__l2::<lambda_af06e22ddd1258f13e12a0178e52eb82>`
```
struct __cppobj NpcInteractScreenController::_registerBindings::__l2::<lambda_af06e22ddd1258f13e12a0178e52eb82>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0f87fed6fb4312dda2670798b50f151e>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0f87fed6fb4312dda2670798b50f151e>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0b39ecdd70a9cbba8ff6d63033e7656f>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0b39ecdd70a9cbba8ff6d63033e7656f>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_9afc29b3dd5cc1aae8670def45ffc7be>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_9afc29b3dd5cc1aae8670def45ffc7be>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_27417888587095cb2e72a69771817beb>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_27417888587095cb2e72a69771817beb>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_46fb4c0b60385f1a6cf29c5c493a988f>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_46fb4c0b60385f1a6cf29c5c493a988f>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_8d65bfe355354836db1ec1e005ccee61>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_8d65bfe355354836db1ec1e005ccee61>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_92f886b587409e6e1e5d18b741ec11eb>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_92f886b587409e6e1e5d18b741ec11eb>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_b119d233e4e8b72d38293e7cf0841ebd>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_b119d233e4e8b72d38293e7cf0841ebd>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_5b8259b00dee110f428b87fabc7b6ef1>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_5b8259b00dee110f428b87fabc7b6ef1>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_e569107e2da18809e468761ce1180ac9>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_e569107e2da18809e468761ce1180ac9>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_529c12038656d1e68dae8adde58aae76>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_529c12038656d1e68dae8adde58aae76>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_3f9ebd4054d1f015433789d31640f170>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_3f9ebd4054d1f015433789d31640f170>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d8dc877c9602e19aace2f6ea1e3ac663>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d8dc877c9602e19aace2f6ea1e3ac663>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_65cd00d13b9b49e1a03643d6c3a37994>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_65cd00d13b9b49e1a03643d6c3a37994>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_b1e8cdc2fe15eeaad5abf69089b81ac1>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_b1e8cdc2fe15eeaad5abf69089b81ac1>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0b7a2867178d7c118d371ed4ffefe5ec>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_0b7a2867178d7c118d371ed4ffefe5ec>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_59277c57f9ed34755d3501796c6d5e19>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_59277c57f9ed34755d3501796c6d5e19>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_835aae1b6d1de636a10bfb62595ec300>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_835aae1b6d1de636a10bfb62595ec300>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_527810ea16a23cdbccc7359bea9aa091>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_527810ea16a23cdbccc7359bea9aa091>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_10f7de869da8691f08d1419b8765e838>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_10f7de869da8691f08d1419b8765e838>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_9c561b746454dc637849d9e0de291451>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_9c561b746454dc637849d9e0de291451>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d6543b3c323d884ac56460bbbd12fffc>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d6543b3c323d884ac56460bbbd12fffc>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d2e6de15aefe0f4465d6f2b0455c106b>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_d2e6de15aefe0f4465d6f2b0455c106b>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_42cc15f8d8a565c4d87fa63846cefc74>`
```
struct __cppobj NpcInteractScreenController::_registerEventHandlers::__l2::<lambda_42cc15f8d8a565c4d87fa63846cefc74>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::{ctor}::__l5::<lambda_545b5b064f68a330907a1d62901c26fd>`
```
struct __cppobj NpcInteractScreenController::{ctor}::__l5::<lambda_545b5b064f68a330907a1d62901c26fd>
{
  std::weak_ptr<ClientInstanceScreenModel> clientInstanceScreenModel;
};

```

### `NpcInteractScreenController::{ctor}::__l2::<lambda_12cdb0e9312e4c06909367b29defc283>`
```
struct __cppobj NpcInteractScreenController::{ctor}::__l2::<lambda_12cdb0e9312e4c06909367b29defc283>
{
  NpcInteractScreenController *const __this;
};

```

### `NpcInteractScreenController::{ctor}::__l2::<lambda_96fcc5098b0104a2c148880f42282cd3>`
```
struct __cppobj NpcInteractScreenController::{ctor}::__l2::<lambda_96fcc5098b0104a2c148880f42282cd3>
{
  NpcInteractScreenController *const __this;
};

```

### `NoWifiWarningScreenController::onOpen::__l2::<lambda_678e104bd177bafcbbaf50e5b4a17646>`
```
struct __cppobj NoWifiWarningScreenController::onOpen::__l2::<lambda_678e104bd177bafcbbaf50e5b4a17646>
{
  std::weak_ptr<NoWifiWarningScreenController> weakThis;
};

```

### `NoLicenseScreenController::_registerEventHandlers::__l2::<lambda_0dde9eacc6bf0e0b0c150fb009adb02b>`
```
struct __cppobj NoLicenseScreenController::_registerEventHandlers::__l2::<lambda_0dde9eacc6bf0e0b0c150fb009adb02b>
{
  MinecraftScreenModel *minecraftScreenModel;
};

```

### `NoLicenseScreenController::onOpen::__l2::<lambda_2735138fa77094ec25279457d23a4977>`
```
struct __cppobj NoLicenseScreenController::onOpen::__l2::<lambda_2735138fa77094ec25279457d23a4977>
{
  std::weak_ptr<NoLicenseScreenController> weakThis;
  MinecraftScreenModel *minecraftScreenModel;
};

```

### `NoInvitesOrJoiningScreenController::onOpen::__l2::<lambda_3c9e8f66ed803a3660dcf022e414dc0b>`
```
struct __cppobj NoInvitesOrJoiningScreenController::onOpen::__l2::<lambda_3c9e8f66ed803a3660dcf022e414dc0b>
{
  std::weak_ptr<NoInvitesOrJoiningScreenController> weakThis;
};

```

### `NestedButtonScreenController::setUpCallbacksForNestedButtonInCollection::__l2::<lambda_2440ef04aad8628a954849b7a600a2b1>`
```
struct __cppobj NestedButtonScreenController::setUpCallbacksForNestedButtonInCollection::__l2::<lambda_2440ef04aad8628a954849b7a600a2b1>
{
  NestedButtonScreenController *const __this;
  std::function<bool __cdecl(UIPropertyBag &,int)> visibilityFunc;
};

```

### `NestedButtonScreenController::setUpCallbacksForNestedButton::__l2::<lambda_83d1f6d270356c6c9764f02a4331fd7c>`
```
struct __cppobj NestedButtonScreenController::setUpCallbacksForNestedButton::__l2::<lambda_83d1f6d270356c6c9764f02a4331fd7c>
{
  NestedButtonScreenController *const __this;
};

```

### `NestedButtonScreenController::setUpCallbacksForNestedButton::__l2::<lambda_0061e4a29d8aa831f112fae32c83e5fb>`
```
struct __cppobj NestedButtonScreenController::setUpCallbacksForNestedButton::__l2::<lambda_0061e4a29d8aa831f112fae32c83e5fb>
{
  NestedButtonScreenController *const __this;
};

```

### `NetworkSettingOptions`
```
struct NetworkSettingOptions
{
  unsigned __int16 mCompressionThreshold;
};

```

### `NetworkChunkRelighter`
```
struct __cppobj NetworkChunkRelighter
{
};

```

### `NetworkChunkRelighter::_spawnLightingTask::__l2::<lambda_c80b1902f85c8610f74a44f0a2e8f79a>`
```
struct __cppobj __declspec(align(8)) NetworkChunkRelighter::_spawnLightingTask::__l2::<lambda_c80b1902f85c8610f74a44f0a2e8f79a>
{
  LevelChunk *lcActual;
  std::shared_ptr<ChunkViewSource> chunks;
  int basePriority;
};

```

### `NetworkChunkRelighter::_spawnLightingTask::__l2::<lambda_116be2b2e5e0868b15dbe531e6fc72e7>`
```
struct __cppobj NetworkChunkRelighter::_spawnLightingTask::__l2::<lambda_116be2b2e5e0868b15dbe531e6fc72e7>
{
  LevelChunk *lcActual;
  std::shared_ptr<ChunkViewSource> chunks;
};

```

### `NoteParticle`
```
struct __cppobj __declspec(align(8)) NoteParticle : Particle
{
  float oSize;
};

```

### `NoteParticle_vtbl`
```
struct /*VFT*/ NoteParticle_vtbl
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

### `NoteBlock`
```
struct __cppobj NoteBlock : ActorBlock
{
};

```

### `NoteBlock_vtbl`
```
struct /*VFT*/ NoteBlock_vtbl
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

### `NavSectionStoreVisualStyle`
```
struct __cppobj NavSectionStoreVisualStyle : StoreVisualStyle
{
};

```

### `NullTextToSpeechClient`
```
struct __cppobj NullTextToSpeechClient : TextToSpeechClient
{
};

```

### `NullTextToSpeechClient_vtbl`
```
struct /*VFT*/ NullTextToSpeechClient_vtbl
{
  void (__fastcall *~TextToSpeechClient)(TextToSpeechClient *this);
  void (__fastcall *setTextToSpeechEnabled)(TextToSpeechClient *this, bool);
  bool (__fastcall *getTextToSpeechEnabled)(TextToSpeechClient *this);
  void (__fastcall *speakText)(TextToSpeechClient *this, const std::string *);
  void (__fastcall *stopSpeaking)(TextToSpeechClient *this);
  bool (__fastcall *isIdle)(TextToSpeechClient *this);
};

```

### `NullTextToSpeechSystem`
```
struct __cppobj NullTextToSpeechSystem : TextToSpeechSystem
{
};

```

### `NullTextToSpeechSystem_vtbl`
```
struct /*VFT*/ NullTextToSpeechSystem_vtbl
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

### `NtAssociatedFile`
```
struct __cppobj NtAssociatedFile
{
  char *m_srcFilePathUtf8;
  char *m_srcContentUtf8;
  char *m_destFileNameUtf8;
};

```

### `NameableComponent`
```
struct __cppobj NameableComponent : IEntityComponent
{
  bool mAllowNameTagRenaming;
  bool mAlwaysShow;
};

```

### `NameAction`
```
struct __cppobj NameAction
{
  std::vector<std::string> mNameFilters;
  DefinitionTrigger mOnNamed;
};

```

### `NormalNoiseLayer`
```
struct __cppobj __declspec(align(8)) NormalNoiseLayer : RootLayer<float>
{
  unsigned int mSeedOffset;
  int mLevels;
  std::unique_ptr<PerlinNoise> mFirst;
  std::unique_ptr<PerlinNoise> mSecond;
  float mValueFactor;
};

```

### `NormalNoiseLayer_vtbl`
```
struct /*VFT*/ NormalNoiseLayer_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<float> *(__fastcall *_allocateAndFill)(Layer<float> *this, LayerDetails::TransferData<float> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(RootLayer<float> *this, LayerDetails::WorkingData<float,char> *, int, int, int, int);
};

```

### `NpcDefinition`
```
struct __cppobj NpcDefinition
{
  Json::Value mNPCData;
};

```

### `Npc`
```
struct __cppobj Npc : Mob
{
};

```

### `NpcComponent::getInteraction::__l5::<lambda_af092033498043834f29b3d77957f2af>`
```
struct __cppobj NpcComponent::getInteraction::__l5::<lambda_af092033498043834f29b3d77957f2af>
{
  Actor *owner;
  Player *pPlayer;
};

```

### `NavigationComponent::checkSendMoveToResult::__l5::<lambda_c9b21251bc9efcfb8c3fa81a3ebf905e>`
```
struct __cppobj NavigationComponent::checkSendMoveToResult::__l5::<lambda_c9b21251bc9efcfb8c3fa81a3ebf905e>
{
  __int64 *rawID;
  int *result;
};

```

### `NameableComponent::getInteraction::__l27::<lambda_19d4c46f68253fdf8e80814d97b1ae7b>`
```
struct __cppobj NameableComponent::getInteraction::__l27::<lambda_19d4c46f68253fdf8e80814d97b1ae7b>
{
  Player *player;
  NameableComponent *const __this;
  Actor *owner;
};

```

### `NavigationSystem`
```
struct __cppobj NavigationSystem : ITickingSystem
{
};

```

### `NavigationSystem_vtbl`
```
struct /*VFT*/ NavigationSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `NetworkHandler::_sortAndPacketizeEvents::__l26::<lambda_c18f95e2a881ec6c4bfa5557333b70c8>`
```
struct __cppobj NetworkHandler::_sortAndPacketizeEvents::__l26::<lambda_c18f95e2a881ec6c4bfa5557333b70c8>
{
  NetworkHandler *const __this;
  ReadOnlyBinaryStream *stream;
  unsigned __int64 *oldReadPointer;
  NetworkHandler::Connection *connection;
  std::shared_ptr<Packet> *packet;
};

```

### `NetworkReplayer`
```
struct __cppobj NetworkReplayer : AppPlatformListener
{
  std::chrono::duration<__int64,std::ratio<1,1000> > mPingIntervals;
  std::unique_ptr<Scheduler> mScheduler;
  std::unique_ptr<NetworkHandler> mNetworkHandler;
  std::unique_ptr<PacketReplayNetworkHandler> mPacketReplayNetworkHandler;
  std::vector<__int64> mLatencyTimePointsMS;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastLatencyPacketSentAt;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastReplayPacketSentAt;
};

```

### `NetworkReplayer_vtbl`
```
struct /*VFT*/ NetworkReplayer_vtbl
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

### `NetworkReplayReader`
```
struct __cppobj NetworkReplayReader
{
  Core::PathBuffer<std::string > mReplayFolderPath;
  std::string mReplayName;
  const unsigned int mVersion;
  std::vector<std::string> mPacketData;
};

```

### `NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>`
```
struct __cppobj __declspec(align(8)) NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>
{
  NetworkHandler *const __this;
  bool networkIsCritical;
};

```

### `NetworkChunkPublisher::_sendQueuedChunk::__l14::<lambda_27221b25a8833b16088c094287e84112>`
```
struct __cppobj NetworkChunkPublisher::_sendQueuedChunk::__l14::<lambda_27221b25a8833b16088c094287e84112>
{
  std::shared_ptr<LevelChunk> levelChunk;
};

```

### `NetworkChunkPublisher::_sendQueuedChunk::__l18::<lambda_3d90a21a191e0fc25d4d3524ff4242ca>`
```
struct __cppobj NetworkChunkPublisher::_sendQueuedChunk::__l18::<lambda_3d90a21a191e0fc25d4d3524ff4242ca>
{
  SubChunk *sc;
};

```

### `NetworkChunkPublisher::prepareRegion::__l2::<lambda_230d3b8c30a9a01eadc378cb610b2e9d>`
```
struct __cppobj NetworkChunkPublisher::prepareRegion::__l2::<lambda_230d3b8c30a9a01eadc378cb610b2e9d>
{
  NetworkChunkPublisher *const __this;
};

```

### `NetworkAddress`
```
struct __cppobj __declspec(align(8)) NetworkAddress
{
  std::string host;
  unsigned __int16 port;
};

```

### `NearestAttackableTargetDefinition`
```
struct __cppobj __declspec(align(8)) NearestAttackableTargetDefinition : TargetGoalDefinition
{
  bool mReselectTargets;
  int mAttackInterval;
  int mScanInterval;
  float mTargetSearchHeight;
  float mTargetInvisibleMultiplier;
  float mTargetSneakVisibilityMultiplier;
  bool mSetPersistent;
};

```

### `NearestAttackableTargetDefinition_vtbl`
```
struct /*VFT*/ NearestAttackableTargetDefinition_vtbl
{
  void (__fastcall *~BaseGoalDefinition)(BaseGoalDefinition *this);
  bool (__fastcall *validateMobType)(BaseGoalDefinition *this, Mob *);
  bool (__fastcall *validate)(BaseGoalDefinition *this, Mob *);
};

```

### `NearestAttackableTargetGoal`
```
struct __cppobj __declspec(align(8)) NearestAttackableTargetGoal : TargetGoal
{
  ActorUniqueID mTargetID;
  const MobDescriptor *mTargetDescriptor;
  bool mReselectTargets;
  int mAttackInterval;
  int mScanInterval;
  bool mSetPersistent;
  float mTargetSearchHeight;
  float mTargetInvisibleMultiplier;
  float mTargetSneakVisibilityMultiplier;
};

```

### `NearestAttackableTargetGoal_vtbl`
```
struct /*VFT*/ NearestAttackableTargetGoal_vtbl
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
  ActorUniqueID *(__fastcall *_findTarget)(NearestAttackableTargetGoal *this, ActorUniqueID *result, const MobDescriptor **);
};

```

### `NearestPrioritizedAttackableTargetGoal`
```
struct __cppobj NearestPrioritizedAttackableTargetGoal : NearestAttackableTargetGoal
{
};

```

### `NearestPrioritizedAttackableTargetGoal_vtbl`
```
struct /*VFT*/ NearestPrioritizedAttackableTargetGoal_vtbl
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
  ActorUniqueID *(__fastcall *_findTarget)(NearestAttackableTargetGoal *this, ActorUniqueID *result, const MobDescriptor **);
};

```

### `NetworkPacketEventCoordinator::sendPacketReceivedFrom::__l2::<lambda_b5b734c663c77d1d84ead46a045879f1>`
```
struct __cppobj NetworkPacketEventCoordinator::sendPacketReceivedFrom::__l2::<lambda_b5b734c663c77d1d84ead46a045879f1>
{
  const PacketHeader *header;
  const Packet *packet;
};

```

### `NoiseBasedTemperatureAttributes`
```
struct NoiseBasedTemperatureAttributes
{
  TemperatureCategory mTemperatureCategory;
};

```

### `NetherReactorBlockActor`
```
struct __cppobj __declspec(align(8)) NetherReactorBlockActor : BlockActor
{
  bool mIsInitialized;
  bool mHasFinished;
  __int16 mProgress;
};

```

### `NetherReactorBlockActor_vtbl`
```
struct /*VFT*/ NetherReactorBlockActor_vtbl
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

### `NetherFungusBlock`
```
struct __cppobj NetherFungusBlock : BlockLegacy
{
};

```

### `NetherFungusBlock_vtbl`
```
struct /*VFT*/ NetherFungusBlock_vtbl
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

### `NetherrackBlock`
```
struct __cppobj NetherrackBlock : BlockLegacy
{
};

```

### `NetherrackBlock_vtbl`
```
struct /*VFT*/ NetherrackBlock_vtbl
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

### `NyliumBlock`
```
struct __cppobj NyliumBlock : BlockLegacy
{
};

```

### `NyliumBlock_vtbl`
```
struct /*VFT*/ NyliumBlock_vtbl
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

### `NetherReactorBlock`
```
struct __cppobj NetherReactorBlock : ActorBlock
{
};

```

### `NetherReactorBlock_vtbl`
```
struct /*VFT*/ NetherReactorBlock_vtbl
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

### `NetherReactorPattern`
```
struct __cppobj NetherReactorPattern
{
  const BlockLegacy *pattern[3][3][3];
};

```

### `NetherSprouts`
```
struct __cppobj NetherSprouts : BlockLegacy
{
};

```

### `NetherSprouts_vtbl`
```
struct /*VFT*/ NetherSprouts_vtbl
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

### `NetherWartBlock`
```
struct __cppobj NetherWartBlock : BushBlock
{
};

```

### `NetherWartBlock_vtbl`
```
struct /*VFT*/ NetherWartBlock_vtbl
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

### `NewLeafBlock`
```
struct __cppobj NewLeafBlock : LeafBlock
{
};

```

### `NewLeafBlock_vtbl`
```
struct /*VFT*/ NewLeafBlock_vtbl
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
  ItemInstance *(__fastcall *getExtraResourceItem)(LeafBlock *this, ItemInstance *result, const Block *);
};

```

### `NewLogBlock`
```
struct __cppobj NewLogBlock : LogBlock
{
};

```

### `NewLogBlock_vtbl`
```
struct /*VFT*/ NewLogBlock_vtbl
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

### `NetherrackBlock::onFertilized::__l2::<lambda_6d65dcf93f58a78a396e94a2bb3d8336>`
```
struct __cppobj NetherrackBlock::onFertilized::__l2::<lambda_6d65dcf93f58a78a396e94a2bb3d8336>
{
};

```

### `NetherLayer`
```
struct __cppobj NetherLayer : RootLayer<enum LayerValues::Terrain>
{
};

```

### `NetherLayer_vtbl`
```
struct /*VFT*/ NetherLayer_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<enum LayerValues::Terrain> *(__fastcall *_allocateAndFill)(Layer<enum LayerValues::Terrain> *this, LayerDetails::TransferData<enum LayerValues::Terrain> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(RootLayer<enum LayerValues::Terrain> *this, LayerDetails::WorkingData<enum LayerValues::Terrain,char> *, int, int, int, int);
};

```

### `NullLogger_vtbl`
```
struct /*VFT*/ NullLogger_vtbl
{
  void (__fastcall *~Logger)(leveldb::Logger *this);
  void (__fastcall *Logv)(leveldb::Logger *this, const char *, char *);
};

```

### `NetworkHookAdapter::hostConnectionLost::__l9::<lambda_f0ec1d78c18f06441748962b30921005>`
```
struct __cppobj NetworkHookAdapter::hostConnectionLost::__l9::<lambda_f0ec1d78c18f06441748962b30921005>
{
  NetworkHookAdapter *const __this;
  RakNet::RakNetGUID rakGuid;
};

```

### `NetworkHookAdapter::disconnect::__l9::<lambda_f87092517f3f9678454df5a1b6684d7f>`
```
struct __cppobj NetworkHookAdapter::disconnect::__l9::<lambda_f87092517f3f9678454df5a1b6684d7f>
{
  NetworkHookAdapter *const __this;
};

```

### `NetworkHookAdapter::disconnect::__l9::<lambda_f87092517f3f9678454df5a1b6684d7f>::()::__l2::<lambda_dd670411e34a0c080be72d02f3a94087>`
```
struct __cppobj NetworkHookAdapter::disconnect::__l9::<lambda_f87092517f3f9678454df5a1b6684d7f>::()::__l2::<lambda_dd670411e34a0c080be72d02f3a94087>
{
};

```

### `NamedPipeObject_vtbl`
```
struct /*VFT*/ NamedPipeObject_vtbl
{
  void (__fastcall *~NamedPipeObject)(NamedPipeObject *this);
};

```

### `NativeSubEntry`
```
struct __cppobj NativeSubEntry
{
  _object *code;
  unsigned int callcount;
  unsigned int recursivecallcount;
  long double totaltime;
  long double inlinetime;
};

```

### `NativeEntry`
```
struct __cppobj NativeEntry
{
  _object *code;
  unsigned int callcount;
  unsigned int recursivecallcount;
  long double totaltime;
  long double inlinetime;
  std::unordered_map<_object *,NativeSubEntry> calls;
};

```

### `native_statscollector_t`
```
struct __cppobj native_statscollector_t
{
  std::unordered_map<_object *,NativeEntry> entries;
  std::unordered_map<_object *,NativeSubEntry> subEntries;
  long double factor;
};

```

### `NetherLightTextureImageBuilder`
```
struct __cppobj NetherLightTextureImageBuilder : BaseLightTextureImageBuilder
{
  Brightness mBrightnessColorBoost[128];
};

```

### `NetherLightTextureImageBuilder_vtbl`
```
struct /*VFT*/ NetherLightTextureImageBuilder_vtbl
{
  void (__fastcall *~BaseLightTextureImageBuilder)(BaseLightTextureImageBuilder *this);
  void (__fastcall *init)(BaseLightTextureImageBuilder *this, Dimension *);
  bool (__fastcall *buildImage)(BaseLightTextureImageBuilder *this, const BaseLightData *, mce::Image *, unsigned int, float, float, bool);
  void (__fastcall *getModifiedBlockBrightnessColor)(BaseLightTextureImageBuilder *this, const BlockPos *, const Block *, const Brightness *, BrightnessPair *);
  std::unique_ptr<BaseLightData> *(__fastcall *createBaseLightTextureData)(BaseLightTextureImageBuilder *this, std::unique_ptr<BaseLightData> *result, IClientInstance *, const BaseLightData *);
};

```

### `NapGoal`
```
struct __cppobj NapGoal : Goal
{
  Mob *mMob;
  Tick mCooldown;
  Tick mDetectMobsTimer;
  bool mInvalidCooldown;
  const int mNapCooldownMin;
  const int mNapCooldownMax;
  const Vec3 mDetectRange;
  ActorFilterGroup mCanNapFilters;
  ActorFilterGroup mWakeMobExceptions;
};

```

### `NapGoal_vtbl`
```
struct /*VFT*/ NapGoal_vtbl
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

### `NetherBrightnessRamp`
```
struct __cppobj NetherBrightnessRamp : DimensionBrightnessRamp
{
};

```

### `NetherBrightnessRamp_vtbl`
```
struct /*VFT*/ NetherBrightnessRamp_vtbl
{
  void (__fastcall *~DimensionBrightnessRamp)(DimensionBrightnessRamp *this);
  void (__fastcall *buildBrightnessRamp)(DimensionBrightnessRamp *this);
  float (__fastcall *getBaseAmbientValue)(DimensionBrightnessRamp *this);
};

```

### `NetherFortressStart`
```
struct __cppobj NetherFortressStart : StructureStart
{
};

```

### `NetherFortressStart_vtbl`
```
struct /*VFT*/ NetherFortressStart_vtbl
{
  void (__fastcall *~StructureStart)(StructureStart *this);
  bool (__fastcall *postProcess)(StructureStart *this, BlockSource *, Random *, const BoundingBox *);
  bool (__fastcall *isValid)(StructureStart *this);
  StructureFeatureType (__fastcall *getType)(StructureStart *this);
};

```

### `NetherDimension`
```
struct __cppobj NetherDimension : Dimension
{
};

```

### `NetherGenerator::ThreadData`
```
struct __cppobj NetherGenerator::ThreadData
{
  Random random;
  std::array<Block const *,32768> blockBuffer;
};

```

### `NetherFortressFeature`
```
struct __cppobj NetherFortressFeature : StructureFeature
{
  std::vector<int> mAllowedBiomes;
};

```

### `NetherFortressFeature_vtbl`
```
struct /*VFT*/ NetherFortressFeature_vtbl
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

### `NetherGenerator`
```
struct __cppobj NetherGenerator : ChunkSource, WorldGenerator
{
  std::unique_ptr<PerlinNoise> lperlinNoise1;
  std::unique_ptr<PerlinNoise> lperlinNoise2;
  std::unique_ptr<PerlinNoise> perlinNoise1;
  std::unique_ptr<PerlinNoise> perlinNoise2;
  std::unique_ptr<PerlinNoise> scaleNoise;
  std::unique_ptr<PerlinNoise> depthNoise;
  std::unique_ptr<PerlinSimplexNoise> surfaceNoise;
  std::unique_ptr<PerlinSimplexNoise> mMaterialAdjNoise;
  Bedrock::Threading::InstancedThreadLocal<NetherGenerator::ThreadData,std::allocator<NetherGenerator::ThreadData> > generatorHelpersPool;
  NetherFortressFeature netherFortressFeature;
  RuinedPortalFeature ruinedPortalFeature;
  BastionFeature bastionFeature;
  LargeHellCaveFeature hellCaveFeature;
  std::shared_ptr<Layer<Biome *> const > mBlockResolutionLayer;
  std::shared_ptr<Layer<Biome *> const > m4x4ResolutionLayer;
  std::shared_mutex mTryGetHeightMutex;
  std::unordered_map<BlockPos,int> mHeightCache;
};

```

### `NetherGenerator_vtbl`
```
struct /*VFT*/ NetherGenerator_vtbl
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

### `NetherFossilFeature`
```
struct __cppobj __declspec(align(8)) NetherFossilFeature : Feature
{
  std::vector<Block const *> mValidGroundBlocks;
  bool mMayPlaceInLava;
};

```

### `NetherFossilFeature_vtbl`
```
struct /*VFT*/ NetherFossilFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `NoSurfaceOreFeature`
```
struct __cppobj NoSurfaceOreFeature : IFeature
{
  IntRange mCount;
  BlockDescriptor mPlaceBlock;
  BlockDescriptor mReplaceBlock;
  BlockDescriptor mAvoidsBlock;
};

```

### `NoSurfaceOreFeature_vtbl`
```
struct /*VFT*/ NoSurfaceOreFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `NetherFortressPiece_vtbl`
```
struct /*VFT*/ NetherFortressPiece_vtbl
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
};

```

### `NBBridgeCrossing`
```
struct __cppobj NBBridgeCrossing : NetherFortressPiece
{
};

```

### `NBBridgeCrossing_vtbl`
```
struct /*VFT*/ NBBridgeCrossing_vtbl
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
};

```

### `NBStartPiece`
```
struct __cppobj NBStartPiece : NBBridgeCrossing
{
  std::string previousPiece;
  std::vector<PieceWeight> availableBridgePieces;
  std::vector<PieceWeight> availableCastlePieces;
  std::vector<StructurePiece *> pendingChildren;
};

```

### `NBStartPiece_vtbl`
```
struct /*VFT*/ NBStartPiece_vtbl
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
};

```

### `NBBridgeStraight`
```
struct __cppobj NBBridgeStraight : NetherFortressPiece
{
};

```

### `NBBridgeStraight_vtbl`
```
struct /*VFT*/ NBBridgeStraight_vtbl
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
};

```

### `NBBridgeEndFiller`
```
struct __cppobj __declspec(align(8)) NBBridgeEndFiller : NetherFortressPiece
{
  int selfSeed;
};

```

### `NBBridgeEndFiller_vtbl`
```
struct /*VFT*/ NBBridgeEndFiller_vtbl
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
};

```

### `NBRoomCrossing`
```
struct __cppobj NBRoomCrossing : NetherFortressPiece
{
};

```

### `NBRoomCrossing_vtbl`
```
struct /*VFT*/ NBRoomCrossing_vtbl
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
};

```

### `NBStairsRoom`
```
struct __cppobj NBStairsRoom : NetherFortressPiece
{
};

```

### `NBStairsRoom_vtbl`
```
struct /*VFT*/ NBStairsRoom_vtbl
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
};

```

### `NBMonsterThrone`
```
struct __cppobj __declspec(align(8)) NBMonsterThrone : NetherFortressPiece
{
  bool hasPlacedMobSpawner;
};

```

### `NBMonsterThrone_vtbl`
```
struct /*VFT*/ NBMonsterThrone_vtbl
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
};

```

### `NBCastleEntrance`
```
struct __cppobj NBCastleEntrance : NetherFortressPiece
{
};

```

### `NBCastleEntrance_vtbl`
```
struct /*VFT*/ NBCastleEntrance_vtbl
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
};

```

### `NBCastleStalkRoom`
```
struct __cppobj NBCastleStalkRoom : NetherFortressPiece
{
};

```

### `NBCastleStalkRoom_vtbl`
```
struct /*VFT*/ NBCastleStalkRoom_vtbl
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
};

```

### `NBCastleSmallCorridorPiece`
```
struct __cppobj NBCastleSmallCorridorPiece : NetherFortressPiece
{
};

```

### `NBCastleSmallCorridorPiece_vtbl`
```
struct /*VFT*/ NBCastleSmallCorridorPiece_vtbl
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
};

```

### `NBCastleSmallCorridorCrossingPiece`
```
struct __cppobj NBCastleSmallCorridorCrossingPiece : NetherFortressPiece
{
};

```

### `NBCastleSmallCorridorCrossingPiece_vtbl`
```
struct /*VFT*/ NBCastleSmallCorridorCrossingPiece_vtbl
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
};

```

### `NBCastleSmallCorridorRightTurnPiece`
```
struct __cppobj __declspec(align(8)) NBCastleSmallCorridorRightTurnPiece : NetherFortressPiece
{
  bool isNeedingChest;
};

```

### `NBCastleSmallCorridorRightTurnPiece_vtbl`
```
struct /*VFT*/ NBCastleSmallCorridorRightTurnPiece_vtbl
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
};

```

### `NBCastleSmallCorridorLeftTurnPiece`
```
struct __cppobj __declspec(align(8)) NBCastleSmallCorridorLeftTurnPiece : NetherFortressPiece
{
  bool isNeedingChest;
};

```

### `NBCastleSmallCorridorLeftTurnPiece_vtbl`
```
struct /*VFT*/ NBCastleSmallCorridorLeftTurnPiece_vtbl
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
};

```

### `NBCastleCorridorStairsPiece`
```
struct __cppobj NBCastleCorridorStairsPiece : NetherFortressPiece
{
};

```

### `NBCastleCorridorStairsPiece_vtbl`
```
struct /*VFT*/ NBCastleCorridorStairsPiece_vtbl
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
};

```

### `NBCastleCorridorTBalconyPiece`
```
struct __cppobj NBCastleCorridorTBalconyPiece : NetherFortressPiece
{
};

```

### `NBCastleCorridorTBalconyPiece_vtbl`
```
struct /*VFT*/ NBCastleCorridorTBalconyPiece_vtbl
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
};

```

### `nldecoder_object`
```
struct __declspec(align(8)) nldecoder_object
{
  __int64 ob_refcnt;
  _typeobject *ob_type;
  _object *decoder;
  _object *errors;
  __int32 pendingcr : 1;
  __int32 translate : 1;
  unsigned __int32 seennl : 3;
};

```

### `NullImporter`
```
struct NullImporter
{
  __int64 ob_refcnt;
  _typeobject *ob_type;
};

```

### `NRMUTEX`
```
struct NRMUTEX
{
  int owned;
  unsigned int thread_id;
  void *hevent;
};

```

### `NVSDK_NGX_PathListInfo`
```
struct __declspec(align(8)) NVSDK_NGX_PathListInfo
{
  wchar_t **Path;
  unsigned int Length;
};

```

### `NVSDK_NGX_FeatureCommonInfo`
```
struct NVSDK_NGX_FeatureCommonInfo
{
  NVSDK_NGX_PathListInfo PathListInfo;
  NVSDK_NGX_FeatureCommonInfo_Internal *InternalData;
};

```

### `NVSDK_NGX_Parameter`
```
struct __cppobj NVSDK_NGX_Parameter
{
  NVSDK_NGX_Parameter_vtbl *__vftable /*VFT*/;
};

```

### `NVSDK_NGX_Parameter_vtbl`
```
struct /*VFT*/ NVSDK_NGX_Parameter_vtbl
{
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, void *);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, ID3D12Resource *);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, ID3D11Resource *);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, int);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, unsigned int);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, long double);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, float);
  void (__fastcall *Set)(NVSDK_NGX_Parameter *this, const char *, unsigned __int64);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, void **);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, ID3D12Resource **);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, ID3D11Resource **);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, int *);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, unsigned int *);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, long double *);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, float *);
  NVSDK_NGX_Result (__fastcall *Get)(NVSDK_NGX_Parameter *this, const char *, unsigned __int64 *);
  void (__fastcall *Reset)(NVSDK_NGX_Parameter *this);
};

```

### `NVSDK_NGX_Handle`
```
struct NVSDK_NGX_Handle
{
  unsigned int Id;
};

```

### `NgxLoader`
```
struct __cppobj NgxLoader
{
  void *m_dllHandle;
  std::tuple<std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *>,std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *>,std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *>,std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *>,std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *>,std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> > m_functions;
};

```

### `NVSDK_NGX_D3D11_Feature_Eval_Params`
```
struct __declspec(align(8)) NVSDK_NGX_D3D11_Feature_Eval_Params
{
  ID3D11Resource *pInColor;
  ID3D11Resource *pInOutput;
  float InSharpness;
};

```

### `NVSDK_NGX_D3D11_DLISP_Eval_Params`
```
struct __declspec(align(8)) NVSDK_NGX_D3D11_DLISP_Eval_Params
{
  NVSDK_NGX_D3D11_Feature_Eval_Params Feature;
  unsigned int InRectX;
  unsigned int InRectY;
  unsigned int InRectW;
  unsigned int InRectH;
  float InDenoise;
};

```

### `NVSDK_NGX_D3D11_GBuffer`
```
struct NVSDK_NGX_D3D11_GBuffer
{
  ID3D11Resource *pInAttrib[16];
};

```

### `NVSDK_NGX_D3D11_DLSS_Eval_Params`
```
struct NVSDK_NGX_D3D11_DLSS_Eval_Params
{
  NVSDK_NGX_D3D11_Feature_Eval_Params Feature;
  ID3D11Resource *pInDepth;
  ID3D11Resource *pInMotionVectors;
  float InJitterOffsetX;
  float InJitterOffsetY;
  NVSDK_NGX_Dimensions InRenderSubrectDimensions;
  int InReset;
  float InMVScaleX;
  float InMVScaleY;
  ID3D11Resource *pInTransparencyMask;
  ID3D11Resource *pInExposureTexture;
  ID3D11Resource *pInReduceGhostMask;
  NVSDK_NGX_Coordinates InColorSubrectBase;
  NVSDK_NGX_Coordinates InDepthSubrectBase;
  NVSDK_NGX_Coordinates InMVSubrectBase;
  NVSDK_NGX_Coordinates InTranslucencySubrectBase;
  NVSDK_NGX_Coordinates InReduceGhostSubrectBase;
  NVSDK_NGX_Coordinates InOutputSubrectBase;
  float InPreExposure;
  int InIndicatorInvertXAxis;
  int InIndicatorInvertYAxis;
  NVSDK_NGX_D3D11_GBuffer GBufferSurface;
  NVSDK_NGX_ToneMapperType InToneMapperType;
  ID3D11Resource *pInMotionVectors3D;
  ID3D11Resource *pInIsParticleMask;
  ID3D11Resource *pInAnimatedTextureMask;
  ID3D11Resource *pInDepthHighRes;
  ID3D11Resource *pInPositionViewSpace;
  float InFrameTimeDeltaInMsec;
  ID3D11Resource *pInRayTracingHitDistance;
  ID3D11Resource *pInMotionVectorsReflections;
};

```

### `NVSDK_NGX_D3D12_DLISP_Eval_Params`
```
struct __declspec(align(8)) NVSDK_NGX_D3D12_DLISP_Eval_Params
{
  NVSDK_NGX_D3D12_Feature_Eval_Params Feature;
  unsigned int InRectX;
  unsigned int InRectY;
  unsigned int InRectW;
  unsigned int InRectH;
  float InDenoise;
};

```

### `NpcInteractScreenController::_performAction::__l8::<lambda_91d1e6691d6d39f56b307163e6dbf920>`
```
struct __cppobj NpcInteractScreenController::_performAction::__l8::<lambda_91d1e6691d6d39f56b307163e6dbf920>
{
  NpcAction *action;
};

```

### `NpcComponent::getButtonCounts::__l12::<lambda_e2d1cdb6cb681ef1beb194f64005002a>`
```
struct __cppobj NpcComponent::getButtonCounts::__l12::<lambda_e2d1cdb6cb681ef1beb194f64005002a>
{
};

```

### `NpcComponent::getUrlCount::__l2::<lambda_3eb1d5c3281d617e75c2642d583a26a7>`
```
struct __cppobj NpcComponent::getUrlCount::__l2::<lambda_3eb1d5c3281d617e75c2642d583a26a7>
{
};

```

### `NetworkHandler::onConnectionClosed::__l2::<lambda_9480810ae157ee4bfb675726738eebc8>`
```
struct __cppobj NetworkHandler::onConnectionClosed::__l2::<lambda_9480810ae157ee4bfb675726738eebc8>
{
  const NetworkIdentifier *id;
};

```

### `NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>::()::__l20::<lambda_adf0c3bb7090e3c81bf11e92a1890232>`
```
struct __cppobj NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>::()::__l20::<lambda_adf0c3bb7090e3c81bf11e92a1890232>
{
  const NetworkHandler::runEvents::__l2::<lambda_548e329923228af3a9c05419563beac9>::()::__l2::KillListData id;
};

```

### `NoteBlock::triggerEvent::__l2::<lambda_0100b5e5d44339fc9040c38336001c41>::()::__l2::Literal`
```
struct __cppobj NoteBlock::triggerEvent::__l2::<lambda_0100b5e5d44339fc9040c38336001c41>::()::__l2::Literal
{
};

```

### `NoteBlock::triggerEvent::__l2::<lambda_0100b5e5d44339fc9040c38336001c41>`
```
struct __cppobj NoteBlock::triggerEvent::__l2::<lambda_0100b5e5d44339fc9040c38336001c41>
{
};

```

### `NotifyManager::tickUpdate::__l10::<lambda_ea8507050d0b423e358e089c69f28097>`
```
struct __cppobj NotifyManager::tickUpdate::__l10::<lambda_ea8507050d0b423e358e089c69f28097>
{
  std::_List_iterator<std::_List_val<std::_List_simple_types<std::shared_ptr<NotifyHandler> > > > remove;
};

```

### `NetherDimension::createGenerator::__l2::<lambda_817f6734b6547373310e517d46e852ba>`
```
struct __cppobj NetherDimension::createGenerator::__l2::<lambda_817f6734b6547373310e517d46e852ba>
{
};

```

### `NetherFossilFeature::place::__l4::<lambda_43d78cc1a17d10de4f962512a76c319f>`
```
struct __cppobj NetherFossilFeature::place::__l4::<lambda_43d78cc1a17d10de4f962512a76c319f>
{
  BlockSource *region;
  const NetherFossilFeature *const __this;
};

```

### `NetherFossilFeature::place::__l7::<lambda_aba1b6b3f46ea98c9b5b4643fde7d896>`
```
struct __cppobj NetherFossilFeature::place::__l7::<lambda_aba1b6b3f46ea98c9b5b4643fde7d896>
{
  BlockSource *region;
};

```

### `NetherFossilFeature::place::__l4::<lambda_e02907b64d2b8692df4ffa8e49654add>`
```
struct __cppobj NetherFossilFeature::place::__l4::<lambda_e02907b64d2b8692df4ffa8e49654add>
{
  int testY;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>
{
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_cae84393e093c2b9dfe8d29a926b8480>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_cae84393e093c2b9dfe8d29a926b8480>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_1ea729a85be84ceda97c81a80935f84b>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_1ea729a85be84ceda97c81a80935f84b>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_a4cb10909c7a811092c5e99775a11fc5>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_a4cb10909c7a811092c5e99775a11fc5>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_ee70469736aa2a6cf0e46653f4c99ecb>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_ee70469736aa2a6cf0e46653f4c99ecb>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_b6a3e25a28cc8b2ccd554b218ad28d32>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_b6a3e25a28cc8b2ccd554b218ad28d32>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_47d447b34610e4b746cb6093934dffae>`
```
struct __cppobj NgxLoader::{ctor}::__l5::<lambda_b6b08d8b75b7d65c3da867be38e76baf>::()::__l2::<lambda_47d447b34610e4b746cb6093934dffae>
{
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(unsigned __int64,wchar_t const *,ID3D12Device *,NVSDK_NGX_FeatureCommonInfo const *,enum NVSDK_NGX_Version),char const *> *<func_0>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(void),char const *> *<func_1>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Parameter * *),char const *> *<func_2>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,enum NVSDK_NGX_Feature,NVSDK_NGX_Parameter const *,NVSDK_NGX_Handle * *),char const *> *<func_3>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(ID3D12GraphicsCommandList *,NVSDK_NGX_Handle const *,NVSDK_NGX_Parameter const *,void (__cdecl*)(float,bool &)),char const *> *<func_4>;
  std::pair<enum NVSDK_NGX_Result (__cdecl*)(NVSDK_NGX_Handle *),char const *> *<func_5>;
  NgxLoader *const __this;
};

```

### `Npc_vtbl`
```
struct /*VFT*/ Npc_vtbl
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

### `NetherDimension_vtbl`
```
struct /*VFT*/ NetherDimension_vtbl
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
  void (__fastcall *allChanged)(LevelListener *this);
  Particle *(__fastcall *addParticle)(LevelListener *this, ParticleType, const Vec3 *, const Vec3 *, int, const CompoundTag *, bool);
  void (__fastcall *sendServerLegacyParticle)(LevelListener *this, ParticleType, const Vec3 *, const Vec3 *, int);
  void (__fastcall *addParticleEffect)(LevelListener *this, const HashedString *, const Actor *, const HashedString *, const Vec3 *, const MolangVariableMap *);
  void (__fastcall *addParticleEffect)(LevelListener *this, const HashedString *, const Vec3 *, const MolangVariableMap *);
  void (__fastcall *addTerrainParticleEffect)(LevelListener *this, const BlockPos *, const Block *, const Vec3 *, float, float, float);
  void (__fastcall *addTerrainSlideEffect)(LevelListener *this, const BlockPos *, const Block *, const Vec3 *, float, float, float);
  void (__fastcall *addBreakingItemParticleEffect)(LevelListener *this, const Vec3 *, ParticleType, const TextureUVCoordinateSet *, bool);
  void (__fastcall *playMusic)(LevelListener *this, const std::string *, const Vec3 *, float, float);
  void (__fastcall *playStreamingMusic)(LevelListener *this, const std::string *, int, int, int);
  void (__fastcall *onEntityAdded)(LevelListener *this, Actor *);
  void (__fastcall *onEntityRemoved)(LevelListener *this, Actor *);
  void (__fastcall *onChunkLoaded)(LevelListener *this, ChunkSource *, LevelChunk *);
  void (__fastcall *onChunkUnloaded)(LevelListener *this, LevelChunk *);
  void (__fastcall *onLevelDestruction)(LevelListener *this, const std::string *);
  void (__fastcall *levelEvent)(LevelListener *this, LevelEvent, const CompoundTag *);
  void (__fastcall *levelEvent)(LevelListener *this, LevelEvent, const Vec3 *, int);
  void (__fastcall *levelSoundEvent)(LevelListener *this, const std::string *, const Vec3 *, float, float);
  void (__fastcall *levelSoundEvent)(LevelListener *this, LevelSoundEvent, const Vec3 *, int, const ActorDefinitionIdentifier *, bool, bool);
  void (__fastcall *stopSoundEvent)(LevelListener *this, const std::string *);
  void (__fastcall *stopAllSounds)(LevelListener *this);
  void (__fastcall *takePicture)(LevelListener *this, cg::ImageBuffer *, Actor *, Actor *, ScreenshotOptions *);
  void (__fastcall *playerListChanged)(LevelListener *this);
  void (__fastcall *init)(Dimension *this);
  void (__fastcall *tick)(Dimension *this);
  void (__fastcall *tickRedstone)(Dimension *this);
  std::tuple<std::unique_ptr<ChunkSource>,WorldGenerator *> *(__fastcall *createGenerator)(Dimension *this, std::tuple<std::unique_ptr<ChunkSource>,WorldGenerator *> *result);
  void (__fastcall *upgradeLevelChunk)(Dimension *this, ChunkSource *, LevelChunk *);
  void (__fastcall *fixWallChunk)(Dimension *this, ChunkSource *, LevelChunk *);
  bool (__fastcall *isNaturalDimension)(Dimension *this);
  bool (__fastcall *isValidSpawn)(Dimension *this, int, int);
  mce::Color *(__fastcall *getBrightnessDependentFogColor)(Dimension *this, mce::Color *result, const mce::Color *, float);
  float (__fastcall *getMaxFogEnd)(Dimension *this);
  float (__fastcall *getMaxFogStart)(Dimension *this);
  bool (__fastcall *isFoggyAt)(Dimension *this, int, int);
  __int16 (__fastcall *getCloudHeight)(Dimension *this);
  int (__fastcall *getDefaultBiome)(Dimension *this);
  bool (__fastcall *mayRespawnViaBed)(Dimension *this);
  bool (__fastcall *hasGround)(Dimension *this);
  BlockPos *(__fastcall *getSpawnPos)(Dimension *this, BlockPos *result);
  int (__fastcall *getSpawnYPosition)(Dimension *this);
  bool (__fastcall *hasBedrockFog)(Dimension *this);
  float (__fastcall *getClearColorScale)(Dimension *this);
  bool (__fastcall *showSky)(Dimension *this);
  bool (__fastcall *isDay)(Dimension *this);
  float (__fastcall *getTimeOfDay)(Dimension *this, int, float);
  float (__fastcall *getSunIntensity)(Dimension *this, float, const Vec3 *, float);
  bool (__fastcall *forceCheckAllNeighChunkSavedStat)(Dimension *this);
  Vec3 *(__fastcall *translatePosAcrossDimension)(Dimension *this, Vec3 *result, const Vec3 *, AutomaticID<Dimension,int>);
  void (__fastcall *sendBroadcast)(Dimension *this, const Packet *, Player *);
  bool (__fastcall *is2DPositionRelevantForPlayer)(Dimension *this, const BlockPos *, Player *);
  bool (__fastcall *isEntityRelevantForPlayer)(Dimension *this, Player *, const Actor *);
  BaseLightTextureImageBuilder *(__fastcall *getLightTextureImageBuilder)(Dimension *this);
  const DimensionBrightnessRamp *(__fastcall *getBrightnessRamp)(Dimension *this);
  void (__fastcall *startLeaveGame)(Dimension *this);
  std::unique_ptr<ChunkBuildOrderPolicyBase> *(__fastcall *_createChunkBuildOrderPolicy)(Dimension *this, std::unique_ptr<ChunkBuildOrderPolicyBase> *result);
  void (__fastcall *_upgradeOldLimboEntity)(Dimension *this, CompoundTag *, LimboEntitiesVersion);
  std::unique_ptr<ChunkSource> *(__fastcall *_wrapStorageForVersionCompatibility)(Dimension *this, std::unique_ptr<ChunkSource> *result, std::unique_ptr<ChunkSource>, StorageVersion);
};

```

