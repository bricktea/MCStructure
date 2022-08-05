# N
### `NetworkAddress`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | host
32 | (2) `uint16_t` | port


### `NetworkPeer::NetworkStatus`
Offset | Type | Name
-|-|-|-
0 | (4) `NetworkPeer::NetworkLoad` | mLoad
4 | (4) `int` | mCurrentPing
8 | (4) `int` | mAveragePing
12 | (4) `int` | mApproximateMaxBps
16 | (4) `float` | mCurrentPacketLoss
20 | (4) `float` | mAveragePacketLoss
24 | (8) `uint64_t` | mTotalBytesReceived
32 | (8) `uint64_t` | mTotalBytesSent


### `NewType<unsigned char>`
Offset | Type | Name
-|-|-|-
0 | (1) `NewType<unsigned char>::Raw` | value


### `NewType<long>`
Offset | Type | Name
-|-|-|-
0 | (8) `NewType<long>::Raw` | value


### `NpcComponent::TextFilter`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<std::string (const std::string &)>::_Invoker_type` | _M_invoker


### `NpcRequestPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `ActorRuntimeID` | mId
48 | (1) `NpcRequestPacket::RequestType` | mType
56 | (32) `std::string` | mActions
88 | (1) `uint8_t` | mActionIndex


### `NpcActions`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<std::unique_ptr<NpcAction>>` | baseclass_0


### `NpcCommandAction::CommandVector`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<NpcCommandAction::SavedCommand>` | baseclass_0


### `NavigationComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAvoidDamageBlocks
1 | (1) `bool` | mAvoidPortals
2 | (1) `bool` | mAvoidSun
3 | (1) `bool` | mAvoidWater
4 | (1) `bool` | mCanBreach
5 | (1) `bool` | mCanFloat
6 | (1) `bool` | mCanJump
7 | (1) `bool` | mCanOpenDoors
8 | (1) `bool` | mCanPassDoors
9 | (1) `bool` | mCanSink
10 | (1) `bool` | mIsAmphibious
11 | (1) `bool` | mIsFollowingRivers
12 | (1) `bool` | mHasEndPathRadius
13 | (1) `bool` | mHasDestination
16 | (4) `int` | mTick
20 | (4) `int` | mTickTimeout
24 | (4) `int` | mLastStuckCheck
28 | (4) `float` | mEndPathRadiusSqr
32 | (4) `float` | mSpeed
36 | (4) `float` | mTerminationThreshold
40 | (12) `Vec3` | mLastStuckCheckPosition
52 | (12) `Vec3` | mTargetOffset
64 | (8) `Unique<PathNavigation>` | mNavigation
72 | (8) `Unique<Path>` | mPath


### `NetworkIdentifier`
Offset | Type | Name
-|-|-|-
0 | (16) `RakNet::RakNetGUID` | mGuid
16 | (128) `sockaddr_storage` | mSock
144 | (4) `NetworkIdentifier::Type` | mType


### `NetworkStatistics::PacketStats`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | id
4 | (4) `unsigned int` | sentNum
8 | (4) `unsigned int` | sentBytes
12 | (4) `unsigned int` | receivedNum
16 | (4) `unsigned int` | receivedBytes


### `NetworkStatistics::OverviewStats`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | sentBytesUnpacked
4 | (4) `unsigned int` | sentBytesPacked
8 | (4) `unsigned int` | receivedBytesUnpacked
12 | (4) `unsigned int` | receivedBytesPacked


### `NetworkSettingOptions`
Offset | Type | Name
-|-|-|-
0 | (2) `uint16_t` | mCompressionThreshold


### `NetworkSettingsPacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (2) `uint16_t` | mCompressionThreshold


### `NetworkBlockPosition`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | baseclass_0


### `NetworkStackLatencyPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (8) `std::chrono::_V2::steady_clock::time_point` | createTime
48 | (1) `bool` | fromServer


### `NameableDescription`
Offset | Type | Name
-|-|-|-
0 | (8) `ComponentDescription` | baseclass_0
8 | (24) `std::vector<NameAction>` | mNameActions
32 | (128) `DefinitionTrigger` | mDefaultActionTrigger
160 | (1) `bool` | mAlwaysShow
161 | (1) `bool` | mAllowNameTagRenaming


### `NameableComponent`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mAllowNameTagRenaming
1 | (1) `bool` | mAlwaysShow


### `NpcComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCurrentSkin
4 | (36) `NpcGUIOffset` | mPortraitOffsets
40 | (36) `NpcGUIOffset` | mPickerOffsets
80 | (24) `std::vector<SkinData>` | mNPCSkins
104 | (16) `Json::Value` | mNPCData
120 | (24) `NpcActions` | mActions
144 | (40) `std::optional<std::string >` | mInteractText
184 | (32) `NpcComponent::TextFilter` | mInteractTextFilter


### `NpcGUIOffset`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mTranslation
12 | (12) `Vec3` | mRotation
24 | (12) `Vec3` | mScale


### `NewBlockID`
Offset | Type | Name
-|-|-|-
0 | (2) `NewType<unsigned short>` | baseclass_0


### `NewType<unsigned short>`
Offset | Type | Name
-|-|-|-
0 | (2) `NewType<unsigned short>::Raw` | value


### `NibblePair`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8` | _bf_0


### `NetworkComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `EntityNetId` | mEntityNetId


### `NoiseBasedTemperatureAttributes`
Offset | Type | Name
-|-|-|-
0 | (4) `TemperatureCategory` | mTemperatureCategory


### `NewType<int>`
Offset | Type | Name
-|-|-|-
0 | (4) `NewType<int>::Raw` | value


### `NameAction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | mNameFilters
24 | (128) `DefinitionTrigger` | mOnNamed


### `NetworkChunkPublisherUpdatePacket`
Offset | Type | Name
-|-|-|-
0 | (36) `Packet:288` | baseclass_0
36 | (12) `BlockPos` | mPosition
48 | (4) `uint32_t` | mRadius


### `NullLogger`
Offset | Type | Name
-|-|-|-
0 | (8) `leveldb::Logger` | baseclass_0


### `NetEventCallback`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$NetEventCallback


### `NetworkHandler`
Offset | Type | Name
-|-|-|-
0 | (8) `RakNetInstance::ConnectionCallbacks` | baseclass_0
8 | (8) `RakPeerHelper::IPSupportInterface` | baseclass_8
16 | (8) `LocalConnector::ConnectionCallbacks` | baseclass_10
24 | (8) `Unique<RakNetInstance>` | mRakNetInstance
32 | (8) `Unique<LocalConnector>` | mLocalConnector
40 | (8) `Unique<RakNetServerLocator>` | mRakNetServerLocator
48 | (8) `Unique<UPNPInterface>` | mUPnPInterface
56 | (40) `Bedrock::Threading::RecursiveMutex` | mConnectionsMutex
96 | (24) `std::vector<std::unique_ptr<NetworkHandler::Connection>>` | mConnections
120 | (56) `std::unordered_map<NetworkIdentifier,NetworkHandler::Connection *>` | mConnectionMap
176 | (8) `size_t` | mCurrentConnection
184 | (16) `Bedrock::Threading::IAsyncResult<void>::Handle` | mReceiveTask
200 | (8) `std::unique_ptr<TaskGroup>` | mReceiveTaskGroup
208 | (8) `PacketObserver *` | mPacketObserver
216 | (8) `Scheduler *` | mMainThread
224 | (32) `std::string` | mReceiveBuffer
256 | (152) `NetworkIdentifier` | mHostingPlayerId
408 | (1) `SubClientId` | mHostingPlayerSubId
416 | (32) `std::string` | mSendBuffer
448 | (96) `BinaryStream` | mSendStream
544 | (8) `std::unique_ptr<ResourcePackTransmissionManager>` | mResourcePackTransmissionManager
552 | (32) `Unique<NetworkHandler::IncomingPacketQueue>[4]` | mIncomingPackets
584 | (1) `bool` | mUseIPv6Only
586 | (2) `uint16_t` | mDefaultGamePort
588 | (2) `uint16_t` | mDefaultGamePortv6
592 | (8) `std::unique_ptr<NetworkPacketEventCoordinator>` | mPacketEventCoordinator
600 | (8) `std::unique_ptr<NetworkStatistics>` | mNetworkStatistics
608 | (2) `uint16_t` | mCompressionThreshold


### `NoteBlock::triggerEvent::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


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
  std::array<std::string,145> mPacketNames;
  NetworkStatistics::OverviewStats mCurrentOverview;
  std::vector<NetworkStatistics::OverviewStats> mLastSeconds;
  double mStartSeconds;
  Bedrock::Threading::Mutex mRakNetStatsReadingLock;
  RakNet::RakNetStatistics mRakNetStatsReading;
  std::function<bool (RakNet::RakNetStatistics &)> mGetRakNetStatsReading;
  std::unique_ptr<Core::OutputFileStream> mCSVFile;
  Core::Profile::CounterToken mUserBytesPerSecSentCounterToken;
  Core::Profile::CounterToken mActualBytesPerSecSentCounterToken;
  Core::Profile::CounterToken mActualBytesPerSecReceivedCounterToken;
  Core::Profile::CounterToken mUserBytesTotalSentCounterToken;
  Core::Profile::CounterToken mActualBytesTotalSentCounterToken;
  Core::Profile::CounterToken mActualBytesTotalReceivedCounterToken;
  Core::Profile::CounterToken mPacketLossPercentagePerSecCounterToken;
  Core::Profile::CounterToken mPacketLossPercentageTotalCounterToken;
};

```

### `NetworkPeer`
```
struct NetworkPeer
{
  int (**_vptr$NetworkPeer)(void);
  std::shared_ptr<NetworkPeer> mPeer;
};

```

### `NetworkHandler::Connection`
```
struct NetworkHandler::Connection
{
  NetworkIdentifier mId;
  NetworkHandler::Connection::Type mType;
  std::weak_ptr<NetworkPacketRecorder> mNetworkPacketRecorder;
  std::weak_ptr<EncryptedNetworkPeer> mEncryptedPeer;
  std::weak_ptr<BatchedNetworkPeer> mBatchedPeer;
  std::shared_ptr<NetworkPeer> mPeer;
  std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > > mLastPacketTime;
  std::chrono::time_point<std::chrono::_V2::steady_clock,std::chrono::duration<long,std::ratio<1,1000000000> > > mClosedTime;
  bool mShouldCloseConnection;
  bool mDisconnected;
  std::bitset<2> mPausedChannels;
  std::queue<std::string> mResumedPackets;
  std::array<std::vector<std::string>,2> mPausedPackets;
};

```

### `NavigationSystem`
```
struct __cppobj NavigationSystem : ITickingSystem
{
};

```

### `NetherDimension`
```
struct __cppobj NetherDimension : Dimension
{
};

```

### `NetherGenerator`
```
struct __cppobj __attribute__((aligned(8))) NetherGenerator : ChunkSource, WorldGenerator
{
  PerlinNoisePtr lperlinNoise1;
  PerlinNoisePtr lperlinNoise2;
  PerlinNoisePtr perlinNoise1;
  PerlinNoisePtr perlinNoise2;
  PerlinNoisePtr perlinNoise3;
  PerlinNoisePtr scaleNoise;
  PerlinNoisePtr depthNoise;
  ThreadLocal<NetherGenerator::ThreadData> generatorHelpersPool;
  NetherFortressFeature netherFortressFeature;
  LargeHellCaveFeature hellCaveFeature;
};

```

### `NetworkIdentifierWithSubId`
```
struct __attribute__((aligned(8))) NetworkIdentifierWithSubId
{
  NetworkIdentifier id;
  SubClientId subClientId;
};

```

### `NetherGenerator::ThreadData`
```
struct NetherGenerator::ThreadData
{
  Random random;
  std::array<long,32768> blockBuffer;
};

```

### `NetherFortressFeature`
```
struct __cppobj NetherFortressFeature : StructureFeature
{
  NetherFortressFeature::MobList bridgeEnemies;
};

```

### `NetherFortressFeature::MobList`
```
typedef std::vector<MobSpawnerData> NetherFortressFeature::MobList;

```

### `NetherFortressStart`
```
struct __cppobj NetherFortressStart : StructureStart
{
};

```

### `NBStartPiece`
```
struct __cppobj NBStartPiece : NBBridgeCrossing
{
  std::string previousPiece;
  PieceWeightList availableBridgePieces;
  PieceWeightList availableCastlePieces;
  ReferencedPieceList pendingChildren;
};

```

### `NetherFortressPiece`
```
struct __cppobj NetherFortressPiece : StructurePiece
{
};

```

### `NBBridgeCrossing`
```
struct __cppobj NBBridgeCrossing : NetherFortressPiece
{
};

```

### `NBBridgeStraight`
```
struct __cppobj NBBridgeStraight : NetherFortressPiece
{
};

```

### `NBBridgeEndFiller`
```
struct __cppobj __attribute__((aligned(8))) NBBridgeEndFiller : NetherFortressPiece
{
  int selfSeed;
};

```

### `NBRoomCrossing`
```
struct __cppobj NBRoomCrossing : NetherFortressPiece
{
};

```

### `NBStairsRoom`
```
struct __cppobj NBStairsRoom : NetherFortressPiece
{
};

```

### `NBMonsterThrone`
```
struct __cppobj __attribute__((aligned(8))) NBMonsterThrone : NetherFortressPiece
{
  bool hasPlacedMobSpawner;
};

```

### `NBCastleEntrance`
```
struct __cppobj NBCastleEntrance : NetherFortressPiece
{
};

```

### `NBCastleStalkRoom`
```
struct __cppobj NBCastleStalkRoom : NetherFortressPiece
{
};

```

### `NBCastleSmallCorridorPiece`
```
struct __cppobj NBCastleSmallCorridorPiece : NetherFortressPiece
{
};

```

### `NBCastleSmallCorridorCrossingPiece`
```
struct __cppobj NBCastleSmallCorridorCrossingPiece : NetherFortressPiece
{
};

```

### `NBCastleSmallCorridorRightTurnPiece`
```
struct __cppobj __attribute__((aligned(8))) NBCastleSmallCorridorRightTurnPiece : NetherFortressPiece
{
  bool isNeedingChest;
};

```

### `NBCastleSmallCorridorLeftTurnPiece`
```
struct __cppobj __attribute__((aligned(8))) NBCastleSmallCorridorLeftTurnPiece : NetherFortressPiece
{
  bool isNeedingChest;
};

```

### `NBCastleCorridorStairsPiece`
```
struct __cppobj NBCastleCorridorStairsPiece : NetherFortressPiece
{
};

```

### `NBCastleCorridorTBalconyPiece`
```
struct __cppobj NBCastleCorridorTBalconyPiece : NetherFortressPiece
{
};

```

### `NewType<std::string >`
```
struct NewType<std::string >
{
  NewType<std::string >::Raw value;
};

```

### `NewType<std::string >::Raw`
```
typedef std::string NewType<std::string >::Raw;

```

### `NpcAction`
```
struct NpcAction
{
  int (**_vptr$NpcAction)(void);
  const NpcActionType mType;
  NpcActionMode mMode;
  std::string mButtonName;
  std::string mEvaluatedButtonName;
  std::string mText;
  std::optional<std::string > mEvaluatedText;
};

```

### `NpcUrlAction`
```
struct __cppobj NpcUrlAction : NpcAction
{
};

```

### `NpcCommandAction::SavedCommand`
```
struct __attribute__((aligned(8))) NpcCommandAction::SavedCommand
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
  NpcCommandAction::CommandVector mCommands;
};

```

### `NpcDescription`
```
struct __cppobj NpcDescription : ComponentDescription
{
  Json::Value mNPCData;
};

```

### `NavigationDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationDescription : ComponentDescription
{
  std::string mNavigationType;
  bool mIsAmphibious;
  bool mAvoidSun;
  bool mCanPassDoors;
  bool mCanOpenDoors;
  bool mCanBreakDoors;
  bool mAvoidWater;
  bool mAvoidDamageBlocks;
  bool mCanFloat;
  bool mCanSink;
  bool mAvoidPortals;
  bool mCanFly;
  bool mCanWalk;
  bool mCanSwim;
  bool mCanClimb;
  bool mCanBreach;
  bool mCanJump;
  bool mUsingDoorAnnotations;
  bool mCanPathFromAir;
};

```

### `NbtIo`
```
struct NbtIo
{
  __int8 gap0[1];
};

```

### `NetworkHandler::IncomingPacketQueue`
```
struct NetworkHandler::IncomingPacketQueue
{
  NetEventCallback *mCallbacksObj;
  Bedrock::Threading::Mutex mMutex;
};

```

### `NetworkPacketEventCoordinator`
```
struct __cppobj NetworkPacketEventCoordinator : EventCoordinator<NetworkPacketEventListener>
{
};

```

### `NetworkPacketEventListener`
```
struct NetworkPacketEventListener
{
  int (**_vptr$NetworkPacketEventListener)(void);
};

```

### `NetworkDebugManager::Tracker`
```
struct __attribute__((aligned(8))) NetworkDebugManager::Tracker
{
  Bedrock::Threading::Mutex mCurrentStatLock;
  TrackerStat mCurrentStat;
  std::chrono::_V2::steady_clock::time_point mLastUpdate;
  std::vector<TrackerStat> mStats;
  uint32_t mLastSampleNum;
};

```

### `NetworkDebugManager`
```
struct NetworkDebugManager
{
  std::array<NetworkDebugManager::Tracker,4> mTrackers;
  TrackerType mRenderGraphMode;
  std::set<NetworkStatistics *> mStatistics;
};

```

### `NullSoundPlayer`
```
struct NullSoundPlayer
{
  __int8 baseclass_0[8];
};

```

### `NetworkChunkPublisher`
```
struct NetworkChunkPublisher
{
  int (**_vptr$NetworkChunkPublisher)(void);
  Level *mLevel;
  NetworkHandler *mNetworkHandler;
  NetworkIdentifier mOwner;
  ClientBlobCache::Server::ActiveTransfersManager *mClientCache;
  SubClientId mSubClientId;
  BlockPos mLastChunkUpdatePosition;
  uint32_t mLastChunkUpdateRadius;
  uint32_t mHandleForChunkBuildOrderUpdates;
  int mChunksSentSinceStart;
  std::unique_ptr<ChunkViewSource> mSource;
  GridArea<std::shared_ptr<LevelChunk> >::AddCallback mAddCallback;
  std::string mCacheSerializeBuffer;
  std::unordered_map<ChunkPos,std::weak_ptr<LevelChunk>> mQueuedChunks;
};

```

### `NavigationClimbDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationClimbDescription : NavigationDescription
{
};

```

### `NavigationFloatDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationFloatDescription : NavigationDescription
{
};

```

### `NavigationFlyDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationFlyDescription : NavigationDescription
{
};

```

### `NavigationHoverDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationHoverDescription : NavigationDescription
{
};

```

### `NavigationGenericDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationGenericDescription : NavigationDescription
{
};

```

### `NavigationSwimDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationSwimDescription : NavigationDescription:464
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

### `NavigationWalkDescription`
```
struct __cppobj __attribute__((aligned(8))) NavigationWalkDescription : NavigationDescription
{
};

```

### `NavigationDescription:464`
```
struct __cppobj __attribute__((packed)) __attribute__((aligned(2))) NavigationDescription:464 : ComponentDescription
{
  std::string mNavigationType;
  bool mIsAmphibious;
  bool mAvoidSun;
  bool mCanPassDoors;
  bool mCanOpenDoors;
  bool mCanBreakDoors;
  bool mAvoidWater;
  bool mAvoidDamageBlocks;
  bool mCanFloat;
  bool mCanSink;
  bool mAvoidPortals;
  bool mCanFly;
  bool mCanWalk;
  bool mCanSwim;
  bool mCanClimb;
  bool mCanBreach;
  bool mCanJump;
  bool mUsingDoorAnnotations;
  bool mCanPathFromAir;
};

```

### `NearestAttackableTargetGoal`
```
struct __cppobj NearestAttackableTargetGoal : TargetGoal
{
  ActorUniqueID mTargetID;
  const MobDescriptor *mTargetDescriptor;
  int mRandomInterval;
  bool mIgnoreTargetType;
  bool mReselectTargets;
  int mScanInterval;
  float mTargetSearchHeight;
};

```

### `NearestPrioritizedAttackableTargetGoal`
```
struct __cppobj NearestPrioritizedAttackableTargetGoal : NearestAttackableTargetGoal
{
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

### `Npc`
```
struct __cppobj Npc : Mob
{
};

```

### `NetherReactorBlockActor`
```
struct __cppobj __attribute__((aligned(4))) NetherReactorBlockActor : BlockActor:1608
{
  bool mIsInitialized;
  bool mHasFinished;
  __int16 mProgress;
};

```

### `NoteBlock`
```
struct __cppobj NoteBlock : ActorBlock
{
};

```

### `NetherWartBlock`
```
struct __cppobj NetherWartBlock : BushBlock
{
};

```

### `NewLeafBlock`
```
struct __cppobj NewLeafBlock : LeafBlock
{
};

```

### `NewLogBlock`
```
struct __cppobj NewLogBlock : LogBlock
{
};

```

### `NetherReactorBlock`
```
struct __cppobj NetherReactorBlock : ActorBlock
{
};

```

### `NetworkChunkSource`
```
struct __cppobj NetworkChunkSource : ChunkSource
{
  ChunkSourceLookupMap mChunkMap;
};

```

### `NetworkChunkPublisher::sendQueuedChunks::SortedChunk`
```
typedef std::pair<float,ChunkPos> NetworkChunkPublisher::sendQueuedChunks::SortedChunk;

```

### `NullSecureStorage`
```
struct __cppobj NullSecureStorage : SecureStorage
{
};

```

