# H
### `HashedString`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mStrHash
8 | (32) `std::string` | mStr
40 | (8) `const HashedString *` | mLastMatch


### `HandlerType`
Offset | Type | Name
-|-|-|-
0 | (4) `` | adjectives
4 | (4) `` | pType
8 | (4) `` | dispCatchObj
12 | (4) `` | addressOfHandler
16 | (4) `` | dispFrame


### `HistoricalFrameTimes`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | mFrameIndex
8 | (120) `float[30]` | mHistoricalMinimumFrameTimes
128 | (120) `float[30]` | mHistoricalMaximumFrameTimes
248 | (120) `float[30]` | mHistoricalAverageFrameTimes
368 | (120) `float[30]` | mLastFrameTime


### `HitResult`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mStartPos
12 | (12) `Vec3` | mRayDir
24 | (4) `HitResultType` | mType
28 | (1) `unsigned __int8` | mFacing
32 | (12) `BlockPos` | mBlock
44 | (12) `Vec3` | mPos
56 | (24) `WeakRefT<EntityRefTraits>` | mEntity
80 | (1) `bool` | mIsHitLiquid
81 | (1) `unsigned __int8` | mLiquidFacing
84 | (12) `BlockPos` | mLiquid
96 | (12) `Vec3` | mLiquidPos
108 | (1) `bool` | mIndirectHit


### `HolographicPlatform::HoloFrameOfReferenceSetupData`
Offset | Type | Name
-|-|-|-
0 | (12) `Vec3` | mMinecraftPlayerPos
12 | (4) `float` | mUIWidth
16 | (4) `float` | mUIHeight
20 | (4) `float` | mUIGuiScale
24 | (4) `float` | mVerticalFovRadians
28 | (4) `float` | mAspectRatio
32 | (4) `float` | mHoloUIWidth
36 | (4) `float` | mHoloUIHeight
40 | (4) `float` | mHoloHUDWidth
44 | (4) `float` | mHoloHUDHeight
48 | (64) `Matrix` | mMinecraftSteveRelativeSpaceToRealitySpaceTransform
112 | (4) `float` | mRealityFrameModeWorldScale
116 | (64) `Matrix` | mScreenAnchorAugmentationMatrix
180 | (64) `Matrix` | mMinecraftView
244 | (64) `Matrix` | mMinecraftProj
308 | (1) `bool` | mDrawUIHeadLocked
309 | (1) `bool` | mTrueMonoscopicModeEnabled
310 | (1) `bool` | mDrawFloatingHud
311 | (1) `bool` | mFixHud
312 | (64) `Matrix` | mHUDMatrixPatch
376 | (64) `Matrix` | mHUDToLeftHandPatch
440 | (4) `HoloUIToPoseSource` | mUIPoseSource
444 | (64) `Matrix` | mVRTransitionMatrixPatch


### `hbui::RouterLocation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<AbstractScene>` | mScene
16 | (32) `std::string` | mUrl
48 | (32) `std::string` | mPath
80 | (40) `std::optional<std::string >` | mQuery
120 | (40) `std::optional<std::string >` | mFragment
160 | (4) `_BYTE[4]` | mMode
164 | (4) `hbui::RouteType` | mRouteType
168 | (32) `std::string` | mState


### `HoverScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `UIPropertyBag *` | properties
8 | (1) `bool` | hover


### `HoloInputModeChangeScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | mode


### `hbui::FacetRegistry::FacetEntry`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (64) `std::function<std::unique_ptr<hbui::IFacet> __cdecl(void)>` | constructor
96 | (8) `std::unique_ptr<hbui::IFacet>` | facet


### `hbui::Feature::registerIsEnabledChangedCallback::__l5::<lambda_1ab57bcd99c576631ba41c810ebdfff7>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<void __cdecl(bool)>` | callback


### `hbui::RouterHistory::FullHistory`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | entries
24 | (4) `int` | current


### `hbui::SceneProvider::createScene::__l2::<lambda_9198b0a63744d6caef4e6bf93514f963>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_03742a56a76ff97dd1e21e945eb64304>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_3ee6f9688302b02ab45782d3ee16d8ce>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_b4883a86f58b08e1adf25075f2619414>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_198843c04982cc508dc4bb1d040ed8de>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<std::string>` | featureFlags


### `hbui::SceneProvider::createScene::__l2::<lambda_304967065c66569af40ba27c5a2bf6f5>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_29ee3a92f3d498426295e1b7ffbcb6ea>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_df7288e7b03dfb70aec84d96b0a91b02>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_420fe536fd38216466f4e15beb7f8f35>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_4e8329eee189f5c87c78bda6854976e8>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l2::<lambda_b8cda2d613720fd8ef484f58bcce6777>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `hbui::SceneProvider::createScene::__l8::<lambda_41cdb76c9bee798add5b424eb551b203>`
Offset | Type | Name
-|-|-|-
0 | (8) `hbui::SceneProvider *const` | __this


### `HummingbirdUI::CallbackEntry`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | token
8 | (64) `std::function<void __cdecl(void)>` | callback


### `hbui::HybridResourceLocation`
Offset | Type | Name
-|-|-|-
0 | (4) `hbui::HybridResourceFileSystem` | mFileSystem
8 | (32) `Core::PathBuffer<std::string >` | mPath
40 | (8) `const PackInstance *` | mPack


### `hbui::RouteMatcher::Entry`
Offset | Type | Name
-|-|-|-
0 | (32) `const std::string` | baseScreenId
32 | (40) `const std::basic_regex<char,std::regex_traits<char> >` | pattern
72 | (4) `hbui::RouteType` | type
76 | (4) `_BYTE[4]` | mode
80 | (64) `std::function<void __cdecl(std::string const &)>` | callback


### `hbui::RouterLocationEventing::ScreenChangedProperties`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mShouldFireEvent
8 | (64) `std::unordered_map<std::string,std::string>` | mEventProperties


### `HostOptionSubCommand`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mButtonText
32 | (32) `std::string` | mTexture
64 | (32) `std::string` | mSubCommand


### `HudScreenController`
Offset | Type | Name
-|-|-|-
0 | (2672) `ClientInstanceScreenController` | baseclass_0
2672 | (8) `BossEventListener` | baseclass_a70
2680 | (1) `bool` | mEDUDiscoveryObserved
2684 | (4) `int` | mInputDelayTimer
2688 | (32) `std::string` | mPopupItemText
2720 | (32) `std::string` | mPopupJukeboxText
2752 | (32) `std::string` | mTipText
2784 | (12) `BlockPos` | mPlayerPos
2796 | (12) `BlockPos` | mAgentPos
2808 | (4) `_BYTE[4]` | mRecordedDirtyState
2816 | (16) `std::shared_ptr<HudContainerManagerController>` | mHudScreenManagerController
2832 | (16) `std::shared_ptr<ScoreboardScreenController>` | mScoreboardScreenController
2848 | (16) `std::shared_ptr<GamePlayTipScreenController>` | mGamePlayTipScreenController
2864 | (1) `bool` | mIsPlayerRiding
2865 | (1) `bool` | mVRRiding
2866 | (1) `bool` | mIsCreative
2867 | (1) `bool` | mVR
2868 | (1) `bool` | mHasPresentedInitialChat
2869 | (1) `bool` | mIsAutoSaving
2870 | (1) `bool` | mIsAutoSaveTimerDone
2872 | (48) `Stopwatch` | mAutoSaveTimer
2920 | (48) `Stopwatch` | mHUDOpacityTimer
2968 | (4) `float` | mHUDOpacityOverride
2972 | (1) `bool` | mOverrideHUDOpacity
2973 | (1) `bool` | mVoiceTipsVisible
2976 | (32) `std::string` | mVoiceName
3008 | (1) `bool` | mIsTitleOnDisplay
3016 | (112) `TitleMessage` | mTitleQueuedData
3128 | (112) `TitleMessage` | mTitleOnDisplayData
3240 | (24) `std::vector<HudScreenController::Tooltip>` | mLeftTooltips
3264 | (24) `std::vector<HudScreenController::Tooltip>` | mRightTooltips


### `HudScreenController::Tooltip`
Offset | Type | Name
-|-|-|-
0 | (4) `Remapping::ActionEnum` | action
4 | (1) `HudScreenController::Tooltip::Type` | type
8 | (64) `std::function<std::string __cdecl(void)>` | getDescription
72 | (32) `std::string` | keyPostfix


### `HydrateParams`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mProductId
32 | (32) `std::string` | mLastModifiedDate
64 | (1) `bool` | mDisableCachedResponseOnFailure
65 | (1) `bool` | mUsePersonaBackend


### `HomeSystem::tick::__l2::<lambda_13bc406ef66a336e9c00382282ba4146>`
Offset | Type | Name
-|-|-|-
0 | (8) `HomeSystem *const` | __this


### `HomeComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mRestrictionRadius
4 | (4) `int` | mRestrictionRadiusSqr
8 | (4) `int` | mCooldownTicksMax
12 | (4) `int` | mCooldownTicks
16 | (24) `std::vector<WeakPtr<BlockLegacy>>` | mHomeBlocks
40 | (12) `BlockPos` | mHomePos
52 | (4) `AutomaticID<Dimension,int>` | mDimensionId


### `HealableDefinition`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<FeedItem>` | mHealItems
24 | (1) `bool` | mForceUse
32 | (64) `ActorFilterGroup` | mFilter


### `HitboxComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Hitbox>` | mHitboxes


### `HistoricPredictionData`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | slot
8 | (248) `ItemStack` | item


### `HugeMushroomFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (4) `int` | mForcedType


### `HugeFungusFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mStemBlock
32 | (8) `const Block *` | mHatBlock
40 | (8) `const Block *` | mDecorBlock
48 | (1) `const bool` | mAllowedToPlaceVines


### `HTTPRequest`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mURL
32 | (32) `std::string` | mRequestBody
64 | (32) `std::string` | mContentType
96 | (4) `HTTPRequest::Method` | mRequestMethod
104 | (104) `HTTPResponse` | mResponse
208 | (16) `std::shared_ptr<HTTPRequestInternal>` | mRequest
224 | (16) `std::map<std::string,std::string>` | mCookies
240 | (16) `std::map<std::string,std::string>` | mHeaders


### `HTTPResponse`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | body
32 | (64) `std::unordered_map<std::string,std::string>` | headers
96 | (4) `int` | responseCode
100 | (4) `HTTPResponse::Status` | status


### `HellSpringFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock
32 | (1) `bool` | mInsideRock


### `HellFireFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `HINSTANCE__`
```
struct HINSTANCE__
{
  int unused;
};

```

### `HungerAttrPacket`
```
const struct __cppobj __declspec(align(8)) HungerAttrPacket : Packet
{
  float mMaxExhaustion;
};

```

### `HungerAttrPacket_vtbl`
```
struct /*VFT*/ HungerAttrPacket_vtbl
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

### `HurtArmorPacket`
```
const struct __cppobj HurtArmorPacket : Packet
{
  _BYTE mCause[4];
  int mDmg;
};

```

### `HurtArmorPacket_vtbl`
```
struct /*VFT*/ HurtArmorPacket_vtbl
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

### `HWND__`
```
struct HWND__
{
  int unused;
};

```

### `HttpHeaders`
```
struct __cppobj HttpHeaders
{
  std::map<std::string,std::string> mHeaders;
  std::string mStatusLine;
  HttpHeaders::ParseState mParseState;
  std::string mParsedName;
  std::string mParsedValue;
  unsigned __int64 mCount;
};

```

### `HeaderTimerComponent`
```
struct __cppobj HeaderTimerComponent : StoreUIComponent
{
  std::string mTimerExpiredText;
  std::string mTimerExpireOverride;
  __int64 mTimerExpireTime;
  bool mHideTimerOnExpiration;
  TimerType mTimerType;
  std::map<int,std::string> mTimerWarnings;
};

```

### `HeaderTimerComponent_vtbl`
```
struct /*VFT*/ HeaderTimerComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `HeaderBannerComponent`
```
struct __cppobj __declspec(align(8)) HeaderBannerComponent : StoreUIComponent
{
  BannerType mBannerType;
};

```

### `HeaderBannerComponent_vtbl`
```
struct /*VFT*/ HeaderBannerComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `HeaderComponent`
```
struct __cppobj HeaderComponent : StoreUIComponent
{
  std::string mHeader;
  std::string mNextSaleBeginsName;
  std::unique_ptr<HeaderTimerComponent> mTimerComponent;
  std::unique_ptr<HeaderBannerComponent> mBannerComponent;
};

```

### `HeaderComponent_vtbl`
```
struct /*VFT*/ HeaderComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `hbui::ILibrary`
```
struct __cppobj hbui::ILibrary : Bedrock::EnableNonOwnerReferences
{
  hbui::ILibrary_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IViewRenderer`
```
struct __cppobj hbui::IViewRenderer
{
  hbui::IViewRenderer_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IViewRenderer_vtbl`
```
struct /*VFT*/ hbui::IViewRenderer_vtbl
{
  void (__fastcall *~IViewRenderer)(hbui::IViewRenderer *this);
  void (__fastcall *render)(hbui::IViewRenderer *this, ScreenContext *);
  void (__fastcall *pushFrame)(hbui::IViewRenderer *this, unsigned int);
  void (__fastcall *freeRenderingResources)(hbui::IViewRenderer *this);
  void (__fastcall *recreateRenderingResources)(hbui::IViewRenderer *this);
  void (__fastcall *resize)(hbui::IViewRenderer *this, unsigned int, unsigned int);
  void (__fastcall *resolve)(hbui::IViewRenderer *this, ScreenContext *, std::optional<RectangleArea>, std::optional<RectangleArea>);
};

```

### `hbui::IView`
```
struct __cppobj hbui::IView
{
  hbui::IView_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IViewListener`
```
struct __cppobj hbui::IViewListener
{
  hbui::IViewListener_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IViewListener_vtbl`
```
struct /*VFT*/ hbui::IViewListener_vtbl
{
  void (__fastcall *~IViewListener)(hbui::IViewListener *this);
  void (__fastcall *onLoadSucceeded)(hbui::IViewListener *this, const char *);
  void (__fastcall *onLoadFailed)(hbui::IViewListener *this, const char *, const char *);
  bool (__fastcall *isActive)(hbui::IViewListener *this);
};

```

### `hbui::CacheSnapshot`
```
struct hbui::CacheSnapshot
{
  unsigned int filledBytes;
  unsigned int capacityBytes;
  unsigned int filledCount;
  unsigned int capacityCount;
};

```

### `hbui::ViewCacheSnapshot`
```
struct hbui::ViewCacheSnapshot
{
  unsigned int viewId;
  hbui::CacheSnapshot shadows;
  hbui::CacheSnapshot paths;
  hbui::CacheSnapshot textures;
  hbui::CacheSnapshot scratchLayerTextures;
};

```

### `hbui::SystemCacheSnapshot`
```
struct hbui::SystemCacheSnapshot
{
  unsigned int aliveImagesCount;
  unsigned int aliveTotalBytesUsed;
  unsigned int orphanedImagesCount;
  unsigned int orphanedBytesUsed;
};

```

### `hbui::BufferSnapshot`
```
struct hbui::BufferSnapshot
{
  unsigned int id;
  unsigned int usedSize;
  unsigned int size;
};

```

### `hbui::DebugData`
```
struct __cppobj hbui::DebugData
{
  const struct hbui::MemorySnapshot *mMemorySnapshot;
  std::vector<hbui::ViewCacheSnapshot> mViewCacheSnapshots;
  hbui::SystemCacheSnapshot mSystemCacheSnapshot;
  std::vector<hbui::BufferSnapshot> mVertexBufferSnapshots;
  std::vector<hbui::BufferSnapshot> mIndexBufferSnapshots;
};

```

### `hbui::IView_vtbl`
```
struct /*VFT*/ hbui::IView_vtbl
{
  void (__fastcall *~IView)(hbui::IView *this);
  void (__fastcall *setViewListener)(hbui::IView *this, hbui::IViewListener *);
  void (__fastcall *resetViewListener)(hbui::IView *this);
  unsigned int (__fastcall *getId)(hbui::IView *this);
  void (__fastcall *update)(hbui::IView *this, long double);
  unsigned int (__fastcall *getWidth)(hbui::IView *this);
  unsigned int (__fastcall *getHeight)(hbui::IView *this);
  void (__fastcall *resize)(hbui::IView *this, unsigned int, unsigned int);
  void (__fastcall *reload)(hbui::IView *this);
  bool (__fastcall *isActive)(hbui::IView *this);
  void (__fastcall *deactivateTextInputAndFacets)(hbui::IView *this);
  void (__fastcall *updateInput)(hbui::IView *this);
  void (__fastcall *handleInput)(hbui::IView *this, const MouseAction *);
  void (__fastcall *setTextboxText)(hbui::IView *this, const std::string *);
  void (__fastcall *updateFacets)(hbui::IView *this);
  void (__fastcall *triggerEvent)(hbui::IView *this, const std::string *, const std::string *);
  void (__fastcall *setDebugFeature)(hbui::IView *this, UIDebugCommandFeature, bool);
  void (__fastcall *fillDebugData)(hbui::IView *this, hbui::DebugData *);
  void (__fastcall *handleMenuCancelButton)(hbui::IView *this);
  void (__fastcall *keyboardClosed)(hbui::IView *this);
  std::optional<RectangleArea> *(__fastcall *getTextInputControlArea)(hbui::IView *this, std::optional<RectangleArea> *result);
  std::optional<RectangleArea> *(__fastcall *getTextInputCaretOffsetArea)(hbui::IView *this, std::optional<RectangleArea> *result);
  void (__fastcall *routeChanged)(hbui::IView *this, const std::optional<hbui::RouterLocation> *, const hbui::RouterLocation *);
};

```

### `hbui::IFacetRegistry`
```
struct __cppobj hbui::IFacetRegistry
{
  hbui::IFacetRegistry_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IFacet`
```
struct __cppobj hbui::IFacet
{
  hbui::IFacet_vtbl *__vftable /*VFT*/;
};

```

### `hbui::FacetBinder`
```
struct __cppobj hbui::FacetBinder
{
};

```

### `hbui::IFacet_vtbl`
```
struct /*VFT*/ hbui::IFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::IFacetRegistry_vtbl`
```
struct /*VFT*/ hbui::IFacetRegistry_vtbl
{
  void (__fastcall *~IFacetRegistry)(hbui::IFacetRegistry *this);
  void (__fastcall *registerFacet)(hbui::IFacetRegistry *this, const std::string *, const std::function<std::unique_ptr<hbui::IFacet> __cdecl(void)> *);
  std::optional<enum hbui::IFacetRegistry::Error> *(__fastcall *activateFacet)(hbui::IFacetRegistry *this, std::optional<enum hbui::IFacetRegistry::Error> *result, hbui::FacetBinder *, const std::string *);
  std::optional<enum hbui::IFacetRegistry::Error> *(__fastcall *deactivateFacet)(hbui::IFacetRegistry *this, std::optional<enum hbui::IFacetRegistry::Error> *result, hbui::FacetBinder *, const std::string *);
  void (__fastcall *deactivateAllFacets)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
  void (__fastcall *bind)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
  void (__fastcall *update)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
};

```

### `hbui::ILibrary_vtbl`
```
struct /*VFT*/ hbui::ILibrary_vtbl
{
  void (__fastcall *~ILibrary)(hbui::ILibrary *this);
  void (__fastcall *update)(hbui::ILibrary *this, long double);
  void (__fastcall *onAppPreSuspended)(hbui::ILibrary *this, mce::RenderContext *);
  void (__fastcall *onAppResumed)(hbui::ILibrary *this, const Bedrock::NonOwnerPointer<mce::ShaderGroup>, const ResourcePackManager *);
  void (__fastcall *onActiveResourcePacksChanged)(hbui::ILibrary *this);
  std::tuple<std::unique_ptr<hbui::IView>,std::unique_ptr<hbui::IViewRenderer> > *(__fastcall *createViewAndRenderer)(hbui::ILibrary *this, std::tuple<std::unique_ptr<hbui::IView>,std::unique_ptr<hbui::IViewRenderer> > *result, const std::string *, unsigned int, unsigned int, std::unique_ptr<hbui::IFacetRegistry>, IClientInstance *, KeyboardManager *, bool);
  void (__fastcall *reloadAllViews)(hbui::ILibrary *this);
  void (__fastcall *setCompleteUninitialization)(hbui::ILibrary *this);
  void (__fastcall *fillDebugData)(hbui::ILibrary *this, hbui::DebugData *);
  void (__fastcall *initializeRendering)(hbui::ILibrary *this, const GuiData *, Bedrock::NonOwnerPointer<mce::ShaderGroup>, mce::RenderContext *);
  void (__fastcall *initializeBitmapFonts)(hbui::ILibrary *this, const ResourcePackManager *);
};

```

### `hbui::SceneProvider`
```
struct __cppobj hbui::SceneProvider
{
  IClientInstance *mClientInstance;
  hbui::ILibrary *mUILibrary;
};

```

### `HolographicPlatform`
```
struct __cppobj __declspec(align(2)) HolographicPlatform
{
  HolographicPlatform_vtbl *__vftable /*VFT*/;
  HolographicPlatform::HoloFrameOfReferenceSetupData mFrameData;
  Vec3 mCurrentHMDPosSpring;
  Vec3 mHoloRealityModeGazeDirMCSpace;
  std::recursive_mutex mMutex;
  std::unordered_map<unsigned int,Matrix> mTransformMap;
  std::vector<HolographicPlatform::HoloCursorWorldParams> mWorldCursorParamsVec;
  bool mBasicTransformsSet;
  bool mStereoEnabled;
  bool mVRLayeringActive;
  bool mAllowMirrorPresent;
  Matrix mHeadlockedUITransform;
  float mDynamicMonoscopicEyeConvergenceDistance;
  float mStereoPerformanceBlockPercentage;
  float mUILayerAlpha;
  int mRecenterHoloUITimeout;
  HolographicPlatform::AimFromSpace mAimFromSpace;
  bool mLeftHandAvailable;
  bool mRightHandAvailable;
  std::string mLivingRoomHintText;
  unsigned int mHolographicFeatures;
  Vec3 mHoloviewerGazePointMCSpace;
  float mRealityFrameScale;
  bool mStuckCursorTriggered;
  float mHoloviewerRotY;
  float mHoloscreenSize;
  float mHoloviewerSize;
  float mLastGazeXCoordNorm;
  float mLastGazeYCoordNorm;
  float mLastGazeXMouseCoordNorm;
  float mLastGazeYMouseCoordNorm;
  bool mGazeOnScreen;
  bool mGestureStatePrimaryHandIsHeld;
  bool mRecenterGazeActivationOriginPoint;
};

```

### `HolographicPlatform::LUID`
```
struct HolographicPlatform::LUID
{
  unsigned int LowPart;
  int HighPart;
};

```

### `HolographicPlatform_vtbl`
```
struct /*VFT*/ HolographicPlatform_vtbl
{
  void (__fastcall *~HolographicPlatform)(HolographicPlatform *this);
  void (__fastcall *init)(HolographicPlatform *this, std::shared_ptr<Options>);
  void (__fastcall *preInitUpdate)(HolographicPlatform *this);
  void (__fastcall *update)(HolographicPlatform *this, IClientInstance *);
  void (__fastcall *postRenderUpdate)(HolographicPlatform *this, IClientInstance *);
  void (__fastcall *getSoundSystemOutputDevice)(HolographicPlatform *this, SoundSystemGUID *);
  void (__fastcall *onAppFocusLost)(HolographicPlatform *this);
  void (__fastcall *onAppFocusGained)(HolographicPlatform *this);
  void (__fastcall *onAppSuspended)(HolographicPlatform *this);
  void (__fastcall *onAppResumed)(HolographicPlatform *this);
  void (__fastcall *onHMDFocusGained)(HolographicPlatform *this);
  void (__fastcall *onHMDFocusLost)(HolographicPlatform *this);
  void (__fastcall *onInitialResourcesLoaded)(HolographicPlatform *this);
  std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *(__fastcall *waitForOutputMode)(HolographicPlatform *this, std::shared_ptr<Bedrock::Threading::IAsyncResult<void> > *result, VROutputMode);
  bool (__fastcall *holographicMode)(HolographicPlatform *this);
  int (__fastcall *getWorkerFramerate)(HolographicPlatform *this);
  bool (__fastcall *allowVRFrameExperience)(HolographicPlatform *this);
  bool (__fastcall *allowSplitScreen)(HolographicPlatform *this);
  bool (__fastcall *supportsLoadingScreen)(HolographicPlatform *this);
  bool (__fastcall *pauseIsDesired)(HolographicPlatform *this);
  bool (__fastcall *allowThirdPersonView)(HolographicPlatform *this);
  bool (__fastcall *useSinglePassStereo)(HolographicPlatform *this);
  bool (__fastcall *drawCubemapInMono)(HolographicPlatform *this);
  bool (__fastcall *isVRMode)(HolographicPlatform *this);
  bool (__fastcall *isARMode)(HolographicPlatform *this);
  bool (__fastcall *isRenderingIn2D)(HolographicPlatform *this);
  bool (__fastcall *isSessionVisible)(HolographicPlatform *this);
  bool (__fastcall *needsPostRenderUpdate)(HolographicPlatform *this);
  bool (__fastcall *deviceHasPositionalTracking)(HolographicPlatform *this);
  bool (__fastcall *deviceNeedsToBeRemovedForXblSignin)(HolographicPlatform *this);
  bool (__fastcall *deviceNeedsToBeRemovedForSkinPicker)(HolographicPlatform *this);
  bool (__fastcall *deviceNeedsToBeRemovedForFilePicker)(HolographicPlatform *this);
  VRHUDPosition (__fastcall *getDefaultVRHUDPosition)(HolographicPlatform *this);
  void (__fastcall *setUndockHandler)(HolographicPlatform *this, std::function<void __cdecl(void)>);
  int (__fastcall *numRequiredControllers)(HolographicPlatform *this);
  std::string *(__fastcall *getPlatformRecalibrationMessage)(HolographicPlatform *this, std::string *result);
  std::string *(__fastcall *getPlatformRecalibrationMessageTTS)(HolographicPlatform *this, std::string *result, const GamePadRemappingLayout *);
  std::string *(__fastcall *getPlatformAlignmentPrompt)(HolographicPlatform *this, std::string *result);
  std::string *(__fastcall *getPlatformAlignmentPromptTTS)(HolographicPlatform *this, std::string *result, const GamePadRemappingLayout *);
  bool (__fastcall *forceControllerUsage)(HolographicPlatform *this);
  bool (__fastcall *separateEyePasses)(HolographicPlatform *this);
  void (__fastcall *createRenderGraph)(HolographicPlatform *this, mce::RenderGraph *, IClientInstance *);
  bool (__fastcall *isGazeDevicePresent)(HolographicPlatform *this);
  bool (__fastcall *isGestureDevicePresent)(HolographicPlatform *this);
  bool (__fastcall *useAlternateTouchInput)(HolographicPlatform *this);
  void (__fastcall *resetBaseFrameOfReference)(HolographicPlatform *this, float, bool);
  HolographicPlatform::LUID (__fastcall *getHoloDeviceAdapterLUID)(HolographicPlatform *this);
  void (__fastcall *captureRenderDevice)(HolographicPlatform *this);
  bool (__fastcall *isLocated)(HolographicPlatform *this);
  bool (__fastcall *isPrimaryHandHeld)(HolographicPlatform *this);
  bool (__fastcall *isSecondaryHandHeld)(HolographicPlatform *this);
  void (__fastcall *setScreenLocation)(HolographicPlatform *this, const Matrix *);
  void (__fastcall *setScreenLocation)(HolographicPlatform *this, const Vec3 *, const Vec3 *, float);
  void (__fastcall *setHeadlockedUITransform)(HolographicPlatform *this, const Matrix *, const float);
  void (__fastcall *setScreenLocationOffset)(HolographicPlatform *this, const Vec3 *);
  void (__fastcall *resetScreenLocationOffset)(HolographicPlatform *this);
  void (__fastcall *setHoloviewerLocation)(HolographicPlatform *this, const Matrix *);
  void (__fastcall *setHoloviewerLocation)(HolographicPlatform *this, const Vec3 *, const Vec3 *, float, bool);
  void (__fastcall *setRealityAnchorLocation)(HolographicPlatform *this, const Matrix *);
  float (__fastcall *getViewableScreenSize)(HolographicPlatform *this, float);
  void (__fastcall *defaultLSRPlane)(HolographicPlatform *this, HolographicPlatform::MCLocation);
  void (__fastcall *updateLSRPlane)(HolographicPlatform *this, HolographicPlatform::MCLocation, const Vec3 *);
  void (__fastcall *getLastLSRPlanePosAndNormPS)(HolographicPlatform *this, Vec3 *, Vec3 *);
  float (__fastcall *getSRCastDistance)(HolographicPlatform *this);
  bool (__fastcall *startEnvironmentScanning)(HolographicPlatform *this);
  void (__fastcall *stopEnvironmentScanning)(HolographicPlatform *this);
  void (__fastcall *resetEnvironmentScan)(HolographicPlatform *this);
  void (__fastcall *renderSRData)(HolographicPlatform *this, float, float);
  bool (__fastcall *hideCursorOnFocusLost)(HolographicPlatform *this, IClientInstance *);
  bool (__fastcall *getGazeCastResultPS)(HolographicPlatform *this, Vec3 *, Vec3 *, Vec3 *);
  bool (__fastcall *getStereoEnabled)(HolographicPlatform *this);
  void (__fastcall *setStereoEnabled)(HolographicPlatform *this, bool);
  void (__fastcall *delayForNextFingerPress)(HolographicPlatform *this, int);
  float (__fastcall *getPreferredUIAspectRatio)(HolographicPlatform *this);
  float (__fastcall *getPreferredLivingRoomLevelAspectRation)(HolographicPlatform *this);
  float (__fastcall *getVRFOV)(HolographicPlatform *this);
  float (__fastcall *getDefaultIngameUIDistance)(HolographicPlatform *this);
  bool (__fastcall *shouldCompressHUDWidth)(HolographicPlatform *this);
  void (__fastcall *getUIScreenWidthHeightScale)(HolographicPlatform *this, unsigned int *, unsigned int *, float *);
  void (__fastcall *getLivingRoomLevelTextureWidthHeight)(HolographicPlatform *this, unsigned int *, unsigned int *, float *);
  void (__fastcall *getItemInHandOffset)(HolographicPlatform *this, Vec3 *);
  const std::string *(__fastcall *getLivingRoomHintTextTTS)(HolographicPlatform *this, const std::string *result, const GamePadRemappingLayout *);
  UIRenderMode (__fastcall *getUIRenderMode)(HolographicPlatform *this);
  UIRenderMode (__fastcall *getVRHUDRenderMode)(HolographicPlatform *this);
  float (__fastcall *getHudAlphaBlendFactor)(HolographicPlatform *this);
  bool (__fastcall *getVRLowFrequencyHUD)(HolographicPlatform *this);
  const char *(__fastcall *getHandMaterial)(HolographicPlatform *this);
  bool (__fastcall *wantsToStealMouse)(HolographicPlatform *this);
  bool (__fastcall *drawHolographicBordersForUI)(HolographicPlatform *this);
  float (__fastcall *getDefaultHalfHoloScreenWidth)(HolographicPlatform *this);
  float (__fastcall *getDefaultHalfHoloHUDWidth)(HolographicPlatform *this);
  float (__fastcall *getAmbientBoost)(HolographicPlatform *this, float);
  bool (__fastcall *clampToMinimumLight)(HolographicPlatform *this);
  void (__fastcall *setUIClipRect)(HolographicPlatform *this, const RectangleArea *);
  float (__fastcall *getUIClipGrowPixels)(HolographicPlatform *this);
  bool (__fastcall *isFeatureEnabled)(HolographicPlatform *this, unsigned int);
  std::optional<mce::framebuilder::gamecomponents::VrConfiguration> *(__fastcall *getVrConfiguration)(HolographicPlatform *this, std::optional<mce::framebuilder::gamecomponents::VrConfiguration> *result);
  void (__fastcall *frameUpdate)(HolographicPlatform *this, FrameUpdateContext *);
  unsigned __int16 (__fastcall *getLivingRoomViewSetId)(HolographicPlatform *this);
  const mce::framebuilder::LivingRoomDescription *(__fastcall *getLivingRoomDescription)(HolographicPlatform *this);
  float (__fastcall *getMinimumLivingRoomFrameDistance)(HolographicPlatform *this);
  bool (__fastcall *neverStealMouse)(HolographicPlatform *this);
  bool (__fastcall *present)(HolographicPlatform *this, ScreenContext *);
  bool (__fastcall *isWaitingForPresent)(HolographicPlatform *this);
  bool (__fastcall *getAllowMirrorPresent)(HolographicPlatform *this);
  bool (__fastcall *permitRendering)(HolographicPlatform *this);
  bool (__fastcall *permitAudio)(HolographicPlatform *this);
  void (__fastcall *_prepPlatformSpecificTransforms)(HolographicPlatform *this);
  bool (__fastcall *_shouldRenderIn2D)(HolographicPlatform *this);
};

```

### `HolographicPlatform::HoloCursorWorldParams`
```
struct __cppobj __declspec(align(2)) HolographicPlatform::HoloCursorWorldParams
{
  HitResult hit;
  float pickRange;
  Vec3 pickDirectionMC;
  Vec3 lastGazePntMC;
  Vec3 lastGazeDirMC;
  Vec3 linearizedJumpAdj;
  float brightness;
  float overallScale;
  bool renderTextureMode;
  bool renderAsACube;
  bool forceFullyVisibleCrosshair;
};

```

### `HolosceneRenderer`
```
struct __cppobj HolosceneRenderer
{
  mce::Mesh mGazeIconMesh;
  mce::Mesh mHoloScreenFrame;
  mce::Mesh mHoloScreenLivingRoom;
  mce::Mesh mHoloScreenLivingRoomTable;
  mce::Mesh mUICursorMesh;
  mce::Mesh mHandFrameMesh;
  mce::Mesh mHandPointerMesh;
  mce::Mesh mCoordFrameMesh;
  mce::Mesh mGameCursorMesh;
  mce::Mesh mGameCursorShadowMesh;
  mce::Mesh mGameCursorCubeMesh;
  mce::Mesh mHandMeshLeft;
  mce::Mesh mHandMeshRight;
  mce::TexturePtr mWhiteIconTexture;
  mce::TexturePtr mHolographicWallTexture;
  mce::TexturePtr mCrosshairTexture;
  mce::TexturePtr mLivingRoomTexture;
  mce::TexturePtr mHandTexture;
  mce::MaterialPtr mHoloCursorPseudoShadowMaterial;
  mce::MaterialPtr mHoloCursorMainPartMaterial;
  mce::MaterialPtr mLivingRoomMaterial;
  mce::MaterialPtr mTextMaterial;
  mce::MaterialPtr mCoordFrameMaterial;
  mce::MaterialPtr mHandPointerMaterial;
  mce::MaterialPtr mHandMaterial;
  IClientInstance *mClient;
  mce::Color mVanishingColor;
  std::string mHintTextLocId;
  int mHintCycles;
  float mUIDist;
  float mHalfHoloScreenWidth;
  float mHalfHoloHUDWidth;
};

```

### `hbui::ResourceRegistry::PathCount`
```
struct __cppobj hbui::ResourceRegistry::PathCount
{
  unsigned int mRefcount;
  Core::PathBuffer<std::string > mPath;
};

```

### `hbui::ResourceRegistry`
```
struct __cppobj hbui::ResourceRegistry
{
  std::unordered_map<std::string,hbui::ResourceRegistry::PathCount> mPaths;
  unsigned __int64 mNextAutomaticallyIncrementedId;
};

```

### `hbui::RouterHistory`
```
struct __cppobj hbui::RouterHistory
{
  std::vector<hbui::RouterLocation> mEntries;
  int mCurrentIndex;
  hbui::RouterAction mLastAction;
  std::function<void __cdecl(std::optional<hbui::RouterLocation> const &,hbui::RouterLocation const &)> mOnChangeCallback;
  std::string mGetActionHelper;
};

```

### `hbui::Router`
```
struct __cppobj hbui::Router
{
  hbui::RouterHistory mRouterHistory;
  hbui::RouterHistoryAdapter mRouterHistoryAdapter;
  std::unique_ptr<hbui::IRouteMatcher> mRouteMatcher;
  std::queue<hbui::Router::QueuedRoute> mQueuedRoutes;
  ISceneStack *mSceneStack;
  Core::Subject<hbui::RouterObserver,Core::SingleThreadedLock> mSubject;
  std::unique_ptr<hbui::IRoutePrerequisiteHandler> mPrerequisiteHandler;
  IScreenChangedEventing *mScreenChangedEventing;
  IClientInstance *mClientInstance;
  Social::IGameConnectionInfoProvider *mGameConnectionInfoProvider;
};

```

### `hbui::RouterHistoryAdapter`
```
struct __cppobj hbui::RouterHistoryAdapter
{
  hbui::Router *mRouter;
  hbui::RouterHistory *mRouterHistory;
  hbui::RouterLocation mFallbackLocation;
};

```

### `hbui::IRouteMatcher`
```
struct __cppobj hbui::IRouteMatcher
{
  hbui::IRouteMatcher_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IRouteMatcher_vtbl`
```
struct /*VFT*/ hbui::IRouteMatcher_vtbl
{
  void (__fastcall *~IRouteMatcher)(hbui::IRouteMatcher *this);
  void (__fastcall *add)(hbui::IRouteMatcher *this, const std::string *, const std::basic_regex<char,std::regex_traits<char> > *, hbui::RouteType, hbui::RouteMode, std::function<void __cdecl(std::string const &)>);
  void (__fastcall *addDefault)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  void (__fastcall *resolve)(hbui::IRouteMatcher *this, const std::string *);
  bool (__fastcall *isSupported)(hbui::IRouteMatcher *this, const std::string *);
  bool (__fastcall *areCompatible)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  bool (__fastcall *isRouteInDirectory)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  std::optional<std::string > *(__fastcall *getDefaultRouteForFile)(hbui::IRouteMatcher *this, std::optional<std::string > *result, const std::string *);
  std::optional<std::string > *(__fastcall *getDefaultRouteForDirectory)(hbui::IRouteMatcher *this, std::optional<std::string > *result, const std::string *);
  std::optional<enum hbui::RouteType> *(__fastcall *getRouteType)(hbui::IRouteMatcher *this, std::optional<enum hbui::RouteType> *result, const std::string *);
  std::optional<enum hbui::RouteMode> *(__fastcall *getRouteMode)(hbui::IRouteMatcher *this, std::optional<enum hbui::RouteMode> *result, const std::string *);
};

```

### `hbui::Router::QueuedRoute`
```
struct __cppobj __declspec(align(8)) hbui::Router::QueuedRoute
{
  std::string route;
  std::string state;
  hbui::Router::QueuedRouteAction action;
};

```

### `hbui::RouterObserver`
```
struct __cppobj hbui::RouterObserver : Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock>
{
};

```

### `hbui::RouterObserver_vtbl`
```
struct /*VFT*/ hbui::RouterObserver_vtbl
{
  void (__fastcall *~Observer<hbui::RouterObserver,Core::SingleThreadedLock>)(Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<hbui::RouterObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onRouteChanged)(hbui::RouterObserver *this, const std::optional<hbui::RouterLocation> *, const hbui::RouterLocation *, hbui::RouterAction);
};

```

### `hbui::IRoutePrerequisiteHandler`
```
struct __cppobj hbui::IRoutePrerequisiteHandler
{
  hbui::IRoutePrerequisiteHandler_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IRoutePrerequisiteHandler_vtbl`
```
struct /*VFT*/ hbui::IRoutePrerequisiteHandler_vtbl
{
  void (__fastcall *~IRoutePrerequisiteHandler)(hbui::IRoutePrerequisiteHandler *this);
  hbui::RoutePrerequisiteState (__fastcall *handleRoutePrerequisites)(hbui::IRoutePrerequisiteHandler *this, const std::string *, const std::string *);
};

```

### `hbui::IFeature`
```
struct __cppobj hbui::IFeature
{
  hbui::IFeature_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IFeature_vtbl`
```
struct /*VFT*/ hbui::IFeature_vtbl
{
  void (__fastcall *~IFeature)(hbui::IFeature *this);
  bool (__fastcall *isEnabled)(hbui::IFeature *this);
  void (__fastcall *registerIsEnabledChangedCallback)(hbui::IFeature *this, Bedrock::PubSub::ScopedSubscription *, std::function<void __cdecl(bool)>);
};

```

### `hbui::Feature`
```
struct __cppobj hbui::Feature : hbui::IFeature
{
  Option *mMainToggle;
};

```

### `hbui::Feature_vtbl`
```
struct /*VFT*/ hbui::Feature_vtbl
{
  void (__fastcall *~IFeature)(hbui::IFeature *this);
  bool (__fastcall *isEnabled)(hbui::IFeature *this);
  void (__fastcall *registerIsEnabledChangedCallback)(hbui::IFeature *this, Bedrock::PubSub::ScopedSubscription *, std::function<void __cdecl(bool)>);
};

```

### `hbui::RouterConfiguration`
```
struct __cppobj hbui::RouterConfiguration
{
  hbui::RouterConfiguration_vtbl *__vftable /*VFT*/;
  const ResourcePackManager *mPackManager;
  IFileAccess *mFileAccess;
  Core::PathBuffer<std::string > mDataPath;
  std::vector<hbui::Route> mDefaultRoutes;
  std::vector<hbui::Route> mInGameRoutes;
  std::vector<hbui::Route> mOutOfGameRoutes;
};

```

### `hbui::RouterConfiguration_vtbl`
```
struct /*VFT*/ hbui::RouterConfiguration_vtbl
{
  void (__fastcall *~RouterConfiguration)(hbui::RouterConfiguration *this);
};

```

### `hbui::Route`
```
struct __cppobj __declspec(align(8)) hbui::Route
{
  std::string fileName;
  std::string route;
  _BYTE mode[4];
};

```

### `HummingbirdUI`
```
struct __cppobj HummingbirdUI : IHummingbirdUI
{
  hbui::DebugData mDebugData;
  hbui::Feature mFeatureToggle;
  hbui::Feature mUIRefreshToggle;
  hbui::Feature mUITextToSpeechToggle;
  ARVRPlatform mArVrPlatform;
  std::weak_ptr<IFlightingToggles> mFlightingToggles;
  std::function<void __cdecl(void)> mResetToMainMenu;
  Core::IFileSystem *mFileSystem;
  IFileAccess *mAppPackageFileAccess;
  const Core::PathBuffer<std::string > mPackagePath;
  IFileAccess *mRawFileAccess;
  const ResourcePackManager *mPackManager;
  hbui::RouterConfiguration mRouterConfigurationLoader;
  std::unique_ptr<hbui::ILibrary> mLibrary;
  hbui::ResourceRegistry mResourceRegistry;
  bool mAppWillRestart;
  std::vector<HummingbirdUI::CallbackEntry> mRouteConfigurationChangeCallbacks;
  Bedrock::PubSub::ScopedSubscription mUIRefreshSubscription;
  Bedrock::PubSub::ScopedSubscription mUITextToSpeechSubscription;
  Bedrock::PubSub::ScopedSubscription mFlightingTogglesSubscription;
};

```

### `HummingbirdUI_vtbl`
```
struct /*VFT*/ HummingbirdUI_vtbl
{
  void (__fastcall *~IHummingbirdUI)(IHummingbirdUI *this);
  bool (__fastcall *isUIRefreshEnabled)(IHummingbirdUI *this);
};

```

### `HudScreenCapabilities`
```
struct __cppobj __declspec(align(8)) HudScreenCapabilities : TypedScreenCapabilities<HudScreenCapabilities>
{
  bool mDisplayChatInputMsg;
};

```

### `HudScreenCapabilities_vtbl`
```
struct /*VFT*/ HudScreenCapabilities_vtbl
{
  void (__fastcall *~IScreenCapabilities)(IScreenCapabilities *this);
  bool (__fastcall *isOfType)(IScreenCapabilities *this, typeid_t<IScreenCapabilities>);
};

```

### `HitDetectSystem`
```
struct __cppobj HitDetectSystem
{
  HitDetectSystem_vtbl *__vftable /*VFT*/;
  float mPickRange;
  float mInteractRange;
  bool mEvaluated;
  __declspec(align(8)) HitResult mViewHitResult;
  HitResult mViewLastHitResult;
  HitResult mViewLiquidHitResult;
  HitResult mViewLastLiquidHitResult;
  HitResult mPickHitResult;
  HitResult mPickLastHitResult;
  HitResult mPickLiquidHitResult;
  HitResult mPickLastLiquidHitResult;
  ClientHitDetectCoordinator *mEventCoordinator;
};

```

### `HitDetectSystem_vtbl`
```
struct /*VFT*/ HitDetectSystem_vtbl
{
  void (__fastcall *~HitDetectSystem)(HitDetectSystem *this);
  void (__fastcall *reset)(HitDetectSystem *this);
  void (__fastcall *tick)(HitDetectSystem *this);
  void (__fastcall *evaluate)(HitDetectSystem *this, IClientInstance *, float);
  void (__fastcall *_evaluateType)(HitDetectSystem *this, IClientInstance *, float, Actor *, LocalPlayer *, bool, HitResult *, HitResult *);
};

```

### `HoloHudDriftDynamics`
```
struct __cppobj HoloHudDriftDynamics
{
  Matrix mMatrixPatch;
  Vec3 mHudDirPoseSpace;
  Vec3 mHudDirAVelPoseSpace;
  Vec3 mLastHudTargetDir;
  Vec3 mLastGazeToPoseDelta;
  long double mLastHudDirUpdateTime;
  bool mResetLastTargetDir;
  IClientInstance *mClient;
};

```

### `hbui::ITelemetry`
```
struct __cppobj hbui::ITelemetry
{
  hbui::ITelemetry_vtbl *__vftable /*VFT*/;
};

```

### `hbui::ITelemetry_vtbl`
```
struct /*VFT*/ hbui::ITelemetry_vtbl
{
  void (__fastcall *~ITelemetry)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdScreenLoadFailed)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdRouteUnsupported)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdJsException)(hbui::ITelemetry *this);
  void (__fastcall *fireEventScreenLoaded)(hbui::ITelemetry *this, const std::string *, long double, long double, long double);
};

```

### `hbui::Telemetry`
```
struct __cppobj hbui::Telemetry : hbui::ITelemetry
{
  IClientInstance *mClientInstance;
  IMinecraftEventing *mEventing;
};

```

### `hbui::Telemetry_vtbl`
```
struct /*VFT*/ hbui::Telemetry_vtbl
{
  void (__fastcall *~ITelemetry)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdScreenLoadFailed)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdRouteUnsupported)(hbui::ITelemetry *this);
  void (__fastcall *fireEventHummingbirdJsException)(hbui::ITelemetry *this);
  void (__fastcall *fireEventScreenLoaded)(hbui::ITelemetry *this, const std::string *, long double, long double, long double);
};

```

### `HardcodedSpawnAreaRegistry`
```
struct __cppobj HardcodedSpawnAreaRegistry
{
  std::unordered_map<enum HardcodedSpawnAreaType,std::vector<MobSpawnerData>> mMap;
};

```

### `HookNetworkPeer`
```
struct __cppobj HookNetworkPeer : NetworkPeer
{
  unsigned int mUserId;
  NetworkHandler *mLobbyHandler;
  std::unique_ptr<MPMCQueue<std::string >> mIncomingData;
};

```

### `HookNetworkPeer_vtbl`
```
struct /*VFT*/ HookNetworkPeer_vtbl
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

### `HudContainerManagerModel`
```
struct __cppobj HudContainerManagerModel : ContainerManagerModel
{
  std::vector<ItemStack> mLastSlots;
};

```

### `HudContainerManagerModel_vtbl`
```
struct /*VFT*/ HudContainerManagerModel_vtbl
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

### `HideDescription`
```
struct __cppobj HideDescription : ComponentDescription
{
};

```

### `HideDescription_vtbl`
```
struct /*VFT*/ HideDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `hbui::FacetBase<hbui::AnimationFacet>`
```
struct __cppobj hbui::FacetBase<hbui::AnimationFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::AnimationFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::AnimationFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::OptionWrapper<bool>`
```
struct __cppobj hbui::OptionWrapper<bool>
{
  Option *mOption;
  Bedrock::PubSub::ScopedSubscription mOptionSubscription;
};

```

### `hbui::AnimationFacet`
```
struct __cppobj hbui::AnimationFacet : hbui::FacetBase<hbui::AnimationFacet>
{
  bool mIsDirty;
  bool mScreenAnimations;
  hbui::OptionWrapper<bool> mScreenAnimationsOption;
};

```

### `hbui::AnimationFacet_vtbl`
```
struct /*VFT*/ hbui::AnimationFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::OptionWrapper<bool>::{ctor}::__l5::<lambda_0dd2ebf6df7ed0553bba2bc4c3b54465>`
```
struct __cppobj hbui::OptionWrapper<bool>::{ctor}::__l5::<lambda_0dd2ebf6df7ed0553bba2bc4c3b54465>
{
  hbui::OptionWrapper<bool> *const __this;
  bool *value;
  bool *isDirty;
};

```

### `hbui::RoutePrerequisiteHandlerMC`
```
struct __cppobj hbui::RoutePrerequisiteHandlerMC : hbui::IRoutePrerequisiteHandler
{
  IMinecraftGame *mMinecraftGame;
  IClientInstance *mClient;
};

```

### `hbui::RoutePrerequisiteHandlerMC_vtbl`
```
struct /*VFT*/ hbui::RoutePrerequisiteHandlerMC_vtbl
{
  void (__fastcall *~IRoutePrerequisiteHandler)(hbui::IRoutePrerequisiteHandler *this);
  hbui::RoutePrerequisiteState (__fastcall *handleRoutePrerequisites)(hbui::IRoutePrerequisiteHandler *this, const std::string *, const std::string *);
};

```

### `HomeSection`
```
struct __cppobj HomeSection : PDPSection
{
  const StoreCatalogItem *mItem;
};

```

### `HomeSection_vtbl`
```
struct /*VFT*/ HomeSection_vtbl
{
  void (__fastcall *~PDPSection)(PDPSection *this);
  std::unique_ptr<ScreenController> *(__fastcall *makeScreenController)(PDPSection *this, std::unique_ptr<ScreenController> *result, std::shared_ptr<MainMenuScreenModel>);
};

```

### `HydrateResponseCallbackHandler`
```
struct __cppobj HydrateResponseCallbackHandler
{
  HydrateResponseCallbackHandler_vtbl *__vftable /*VFT*/;
  std::string mAcceptLanguage;
};

```

### `HydrateResponseCallbackHandler_vtbl`
```
struct /*VFT*/ HydrateResponseCallbackHandler_vtbl
{
  void (__fastcall *~HydrateResponseCallbackHandler)(HydrateResponseCallbackHandler *this);
  void (__fastcall *parseResponse)(HydrateResponseCallbackHandler *this, const struct web::json::value *, const CatalogBackend *);
  void (__fastcall *handleResponseCallback)(HydrateResponseCallbackHandler *this);
};

```

### `hbui::FacetBase<hbui::RouterFacet>`
```
struct __cppobj hbui::FacetBase<hbui::RouterFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::RouterFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::RouterFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::RouterFacet`
```
struct __cppobj hbui::RouterFacet : hbui::FacetBase<hbui::RouterFacet>, hbui::RouterObserver
{
  bool mIsDirty;
  hbui::Router *mRouter;
};

```

### `hbui::RouterFacet_vtbl`
```
struct /*VFT*/ hbui::RouterFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::RoutePrerequisiteHandlerMC::_handleAchievementPrerequisites::__l15::<lambda_0cc03f2b69703d47831966b90071f608>`
```
struct __cppobj hbui::RoutePrerequisiteHandlerMC::_handleAchievementPrerequisites::__l15::<lambda_0cc03f2b69703d47831966b90071f608>
{
  hbui::RoutePrerequisiteHandlerMC *const __this;
  const std::string achievementDeepLinkId;
};

```

### `hbui::RoutePrerequisiteHandlerMC::_handleAchievementPrerequisites::__l13::<lambda_eeeb9f2af150426eb424d350f84fc216>`
```
struct __cppobj hbui::RoutePrerequisiteHandlerMC::_handleAchievementPrerequisites::__l13::<lambda_eeeb9f2af150426eb424d350f84fc216>
{
};

```

### `HudContainerManagerController`
```
struct __cppobj HudContainerManagerController : ContainerManagerController
{
  std::weak_ptr<HudContainerManagerModel> mHudContainerManagerModel;
};

```

### `HudContainerManagerController_vtbl`
```
struct /*VFT*/ HudContainerManagerController_vtbl
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

### `History::TickMobReplay`
```
struct __cppobj History::TickMobReplay : IReplayableActorInput
{
};

```

### `History::TickMobReplay_vtbl`
```
struct /*VFT*/ History::TickMobReplay_vtbl
{
  void (__fastcall *~IReplayableActorInput)(IReplayableActorInput *this);
  void (__fastcall *advanceFrame)(IReplayableActorInput *this, IActorMovementProxy *);
  AdvanceFrameResult (__fastcall *advanceLiveFrame)(IReplayableActorInput *this, Actor *);
};

```

### `History::SynchedActorDataReplay`
```
struct __cppobj History::SynchedActorDataReplay : IReplayableActorInput
{
  std::vector<std::unique_ptr<DataItem>> mData;
};

```

### `History::SynchedActorDataReplay_vtbl`
```
struct /*VFT*/ History::SynchedActorDataReplay_vtbl
{
  void (__fastcall *~IReplayableActorInput)(IReplayableActorInput *this);
  void (__fastcall *advanceFrame)(IReplayableActorInput *this, IActorMovementProxy *);
  AdvanceFrameResult (__fastcall *advanceLiveFrame)(IReplayableActorInput *this, Actor *);
};

```

### `History::AttributeReplay`
```
struct __cppobj History::AttributeReplay : IReplayableActorInput
{
  const UpdateAttributesPacket mPacket;
};

```

### `History::AttributeReplay_vtbl`
```
struct /*VFT*/ History::AttributeReplay_vtbl
{
  void (__fastcall *~IReplayableActorInput)(IReplayableActorInput *this);
  void (__fastcall *advanceFrame)(IReplayableActorInput *this, IActorMovementProxy *);
  AdvanceFrameResult (__fastcall *advanceLiveFrame)(IReplayableActorInput *this, Actor *);
};

```

### `History::createReplayableActorStateSource::__l2::FunctionStateSource`
```
struct __cppobj History::createReplayableActorStateSource::__l2::FunctionStateSource : IReplayableActorStateSource
{
  std::function<std::unique_ptr<IReplayableActorState> __cdecl(IActorMovementProxy &)> mCreator;
};

```

### `History::createReplayableActorStateSource::__l2::FunctionStateSource_vtbl`
```
struct /*VFT*/ History::createReplayableActorStateSource::__l2::FunctionStateSource_vtbl
{
  void (__fastcall *~IReplayableActorStateSource)(IReplayableActorStateSource *this);
  std::unique_ptr<IReplayableActorState> *(__fastcall *extract)(IReplayableActorStateSource *this, std::unique_ptr<IReplayableActorState> *result, IActorMovementProxy *);
};

```

### `History::createPlayerSnapshotReplaySource::__l2::PlayerSnapshotReplay`
```
struct __cppobj History::createPlayerSnapshotReplaySource::__l2::PlayerSnapshotReplay : IReplayableActorState
{
  PlayerSnapshot mSnapshot;
};

```

### `History::createPlayerSnapshotReplaySource::__l2::PlayerSnapshotReplay_vtbl`
```
struct /*VFT*/ History::createPlayerSnapshotReplaySource::__l2::PlayerSnapshotReplay_vtbl
{
  void (__fastcall *~IReplayableActorState)(IReplayableActorState *this);
  void (__fastcall *apply)(IReplayableActorState *this, IActorMovementProxy *);
};

```

### `History::createPlayerSnapshotReplaySource::__l2::<lambda_1f894fb1c8414cded9e799b2cb78ac08>`
```
struct __cppobj History::createPlayerSnapshotReplaySource::__l2::<lambda_1f894fb1c8414cded9e799b2cb78ac08>
{
};

```

### `History::SynchedActorDataReplay::advanceLiveFrame::__l5::<lambda_061e6f19e2a2840cfeb37a624df18704>`
```
struct __cppobj History::SynchedActorDataReplay::advanceLiveFrame::__l5::<lambda_061e6f19e2a2840cfeb37a624df18704>
{
  ActorUniqueID actorID;
};

```

### `HMENU__`
```
struct HMENU__
{
  int unused;
};

```

### `HBITMAP__`
```
struct HBITMAP__
{
  int unused;
};

```

### `HKEY__`
```
struct HKEY__
{
  int unused;
};

```

### `HICON__`
```
struct HICON__
{
  int unused;
};

```

### `HBRUSH__`
```
struct HBRUSH__
{
  int unused;
};

```

### `HPALETTE__`
```
struct HPALETTE__
{
  int unused;
};

```

### `HDC__`
```
struct HDC__
{
  int unused;
};

```

### `HENHMETAFILE__`
```
struct HENHMETAFILE__
{
  int unused;
};

```

### `HSTRING__`
```
struct HSTRING__
{
  int unused;
};

```

### `HWINSTA__`
```
struct HWINSTA__
{
  int unused;
};

```

### `hostent`
```
struct hostent
{
  char *h_name;
  char **h_aliases;
  __int16 h_addrtype;
  __int16 h_length;
  char **h_addr_list;
};

```

### `HSTRING_HEADER`
```
struct HSTRING_HEADER
{
  HSTRING_HEADER::<unnamed_type_Reserved> Reserved;
};

```

### `HMETAFILE__`
```
struct HMETAFILE__
{
  int unused;
};

```

### `HRSRC__`
```
struct HRSRC__
{
  int unused;
};

```

### `HRAWINPUT__`
```
struct HRAWINPUT__
{
  int unused;
};

```

### `HTOUCHINPUT__`
```
struct HTOUCHINPUT__
{
  int unused;
};

```

### `HashedString::StringHasher<char const *>`
```
struct __cppobj HashedString::StringHasher<char const *>
{
};

```

### `HashedString::Hash64<0>`
```
struct __cppobj HashedString::Hash64<0>
{
};

```

### `HashedString::Hash64_noNullTerminator<0>`
```
struct __cppobj HashedString::Hash64_noNullTerminator<0>
{
};

```

### `HTASK__`
```
struct HTASK__
{
  int unused;
};

```

### `HPEN__`
```
struct HPEN__
{
  int unused;
};

```

### `HRGN__`
```
struct HRGN__
{
  int unused;
};

```

### `HACCEL__`
```
struct HACCEL__
{
  int unused;
};

```

### `HDESK__`
```
struct HDESK__
{
  int unused;
};

```

### `HUMPD__`
```
struct HUMPD__
{
  int unused;
};

```

### `HIMC__`
```
struct HIMC__
{
  int unused;
};

```

### `HHOOK__`
```
struct HHOOK__
{
  int unused;
};

```

### `HWINEVENTHOOK__`
```
struct HWINEVENTHOOK__
{
  int unused;
};

```

### `HGLRC__`
```
struct HGLRC__
{
  int unused;
};

```

### `HashType64_hash`
```
struct __cppobj HashType64_hash
{
};

```

### `HIMCC__`
```
struct HIMCC__
{
  int unused;
};

```

### `HCOLORSPACE__`
```
struct HCOLORSPACE__
{
  int unused;
};

```

### `HMONITOR__`
```
struct HMONITOR__
{
  int unused;
};

```

### `HGESTUREINFO__`
```
struct HGESTUREINFO__
{
  int unused;
};

```

### `HLSURF__`
```
struct HLSURF__
{
  int unused;
};

```

### `HFONT__`
```
struct HFONT__
{
  int unused;
};

```

### `HSTRING_BUFFER__`
```
struct HSTRING_BUFFER__
{
  int unused;
};

```

### `HKL__`
```
struct HKL__
{
  int unused;
};

```

### `HSTR__`
```
struct HSTR__
{
  int unused;
};

```

### `HDROP__`
```
struct HDROP__
{
  int unused;
};

```

### `HSPRITE__`
```
struct HSPRITE__
{
  int unused;
};

```

### `HelpCommand`
```
struct __cppobj __declspec(align(8)) HelpCommand : Command
{
  std::string mCommand;
  int mPage;
};

```

### `HelpCommand_vtbl`
```
struct /*VFT*/ HelpCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `hbui::Scene`
```
struct __cppobj hbui::Scene : AbstractScene, hbui::IViewListener, hbui::RouterObserver
{
  unsigned int mWidth;
  unsigned int mHeight;
  std::unique_ptr<hbui::IView> mView;
  std::unique_ptr<hbui::IViewRenderer> mViewRenderer;
  std::unique_ptr<IScreenSettings> mScreenSettings;
  const std::string mInitialURL;
  std::string mCurrentRoute;
  _BYTE mMode[4];
  _BYTE mState[4];
  RectangleArea mRenderingAABB;
  glm::tvec2<float,0> mGamepadCursorPosition;
  __int16 mCurrentPointerPositionX;
  __int16 mCurrentPointerPositionY;
  InputMode mCurrentInputMode;
  _BYTE mCurrentVRInputMode[4];
  std::unique_ptr<AbstractScreenSetupCleanupStrategy> mScreenSetupCleanup;
  std::shared_ptr<AbstractSceneProxy> mProxy;
  std::function<void __cdecl(void)> mOnLoadFailedCallback;
  hbui::ITelemetry *mTelemetry;
};

```

### `hbui::Scene_vtbl`
```
struct /*VFT*/ hbui::Scene_vtbl
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
};

```

### `hbui::RouteMatcher::DefaultEntry`
```
struct __cppobj hbui::RouteMatcher::DefaultEntry
{
  const std::string baseScreenId;
  const std::string route;
};

```

### `hbui::RouteMatcher`
```
struct __cppobj hbui::RouteMatcher : hbui::IRouteMatcher
{
  std::vector<hbui::RouteMatcher::Entry> mEntries;
  std::vector<hbui::RouteMatcher::DefaultEntry> mDefaultRoutes;
};

```

### `hbui::RouteMatcher_vtbl`
```
struct /*VFT*/ hbui::RouteMatcher_vtbl
{
  void (__fastcall *~IRouteMatcher)(hbui::IRouteMatcher *this);
  void (__fastcall *add)(hbui::IRouteMatcher *this, const std::string *, const std::basic_regex<char,std::regex_traits<char> > *, hbui::RouteType, hbui::RouteMode, std::function<void __cdecl(std::string const &)>);
  void (__fastcall *addDefault)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  void (__fastcall *resolve)(hbui::IRouteMatcher *this, const std::string *);
  bool (__fastcall *isSupported)(hbui::IRouteMatcher *this, const std::string *);
  bool (__fastcall *areCompatible)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  bool (__fastcall *isRouteInDirectory)(hbui::IRouteMatcher *this, const std::string *, const std::string *);
  std::optional<std::string > *(__fastcall *getDefaultRouteForFile)(hbui::IRouteMatcher *this, std::optional<std::string > *result, const std::string *);
  std::optional<std::string > *(__fastcall *getDefaultRouteForDirectory)(hbui::IRouteMatcher *this, std::optional<std::string > *result, const std::string *);
  std::optional<enum hbui::RouteType> *(__fastcall *getRouteType)(hbui::IRouteMatcher *this, std::optional<enum hbui::RouteType> *result, const std::string *);
  std::optional<enum hbui::RouteMode> *(__fastcall *getRouteMode)(hbui::IRouteMatcher *this, std::optional<enum hbui::RouteMode> *result, const std::string *);
};

```

### `HitResultComponent`
```
struct __cppobj HitResultComponent : IEntityComponent
{
  std::unique_ptr<IHitResultContainer> mHitResults;
};

```

### `HTTPRequestInternal`
```
struct __cppobj HTTPRequestInternal : std::enable_shared_from_this<HTTPRequestInternal>
{
  HTTPRequestInternal_vtbl *__vftable /*VFT*/;
};

```

### `HTTPRequestInternal_vtbl`
```
struct /*VFT*/ HTTPRequestInternal_vtbl
{
  void (__fastcall *~HTTPRequestInternal)(HTTPRequestInternal *this);
};

```

### `HTTPRequestCancelSource`
```
struct __cppobj HTTPRequestCancelSource
{
  HTTPRequestCancelSource_vtbl *__vftable /*VFT*/;
};

```

### `HTTPRequestCancelSource_vtbl`
```
struct /*VFT*/ HTTPRequestCancelSource_vtbl
{
  void (__fastcall *~HTTPRequestCancelSource)(HTTPRequestCancelSource *this);
  void (__fastcall *cancel)(HTTPRequestCancelSource *this);
};

```

### `hbui::TapGestureParameters`
```
struct __declspec(align(8)) hbui::TapGestureParameters
{
  unsigned int maxTouches;
  long double timeToleranceMs;
  float distanceToleranceCm;
};

```

### `hbui::FlingGestureParameters`
```
struct __declspec(align(8)) hbui::FlingGestureParameters
{
  unsigned int minTouches;
  unsigned int maxTouches;
  long double maxIntervalBetweenMovesMs;
  float minDistanceCm;
};

```

### `hbui::PanGestureParameters`
```
struct hbui::PanGestureParameters
{
  unsigned int minTouches;
  unsigned int maxTouches;
  float minDistanceCm;
};

```

### `hbui::GestureParameters`
```
struct __declspec(align(8)) hbui::GestureParameters
{
  hbui::TapGestureParameters tapParameters;
  hbui::FlingGestureParameters flingParameters;
  hbui::PanGestureParameters panParameters;
};

```

### `HitResultSystem`
```
struct __cppobj HitResultSystem : ITickingSystem
{
};

```

### `HitResultSystem_vtbl`
```
struct /*VFT*/ HitResultSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `HolographicPostRenderer`
```
struct __cppobj HolographicPostRenderer : MinecraftUICustomRenderer
{
  mce::MaterialPtr mUIQuadMaterial;
  mce::MaterialPtr mUIHudMaterial;
  mce::MaterialPtr mLevelQuadMaterial;
  mce::MaterialPtr mUIFillColorMaterial;
  float mUIWidth;
  float mUIHeight;
  float mLevelMeshWidth;
  float mLevelMeshHeight;
  mce::Mesh mUIQuadMesh;
  mce::Mesh mLevelMesh;
};

```

### `HolographicPostRenderer_vtbl`
```
struct /*VFT*/ HolographicPostRenderer_vtbl
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

### `HotBarWipeRenderer`
```
struct __cppobj HotBarWipeRenderer : MinecraftUICustomRenderer
{
};

```

### `HotBarWipeRenderer_vtbl`
```
struct /*VFT*/ HotBarWipeRenderer_vtbl
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
  void (__fastcall *drawRectangle)(HotBarWipeRenderer *this, ScreenContext *, UIControl *, float, const mce::Color *, RectangleArea *);
  int (__fastcall *getHotBarIndex)(HotBarWipeRenderer *this, UIControl *);
};

```

### `HotBarCooldownRenderer`
```
struct __cppobj HotBarCooldownRenderer : HotBarWipeRenderer
{
};

```

### `HotBarCooldownRenderer_vtbl`
```
struct /*VFT*/ HotBarCooldownRenderer_vtbl
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
  void (__fastcall *drawRectangle)(HotBarWipeRenderer *this, ScreenContext *, UIControl *, float, const mce::Color *, RectangleArea *);
  int (__fastcall *getHotBarIndex)(HotBarWipeRenderer *this, UIControl *);
};

```

### `HotBarDropRenderer`
```
struct __cppobj HotBarDropRenderer : HotBarWipeRenderer
{
};

```

### `HotBarDropRenderer_vtbl`
```
struct /*VFT*/ HotBarDropRenderer_vtbl
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
  void (__fastcall *drawRectangle)(HotBarWipeRenderer *this, ScreenContext *, UIControl *, float, const mce::Color *, RectangleArea *);
  int (__fastcall *getHotBarIndex)(HotBarWipeRenderer *this, UIControl *);
};

```

### `HoverTextRenderer`
```
struct __cppobj HoverTextRenderer : MinecraftUICustomRenderer
{
  std::string mContent;
  std::string mFilteredContent;
  glm::tvec2<float,0> mCursorPosition;
  glm::tvec2<float,0> mOffset;
  glm::tvec2<float,0> mBoxDimensions;
  mce::MaterialPtr mBlitMat;
  std::unique_ptr<NinePatchLayer> mLayer;
};

```

### `HoverTextRenderer_vtbl`
```
struct /*VFT*/ HoverTextRenderer_vtbl
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

### `HudArmorRenderer`
```
struct __cppobj HudArmorRenderer : MinecraftUICustomRenderer
{
  bool mHasLoadedTextures;
  mce::TexturePtr mEmptyArmorTexture;
  mce::TexturePtr mHalfArmorTexture;
  mce::TexturePtr mFullArmorTexture;
};

```

### `HudArmorRenderer_vtbl`
```
struct /*VFT*/ HudArmorRenderer_vtbl
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

### `HudBubblesRenderer`
```
struct __cppobj HudBubblesRenderer : MinecraftUICustomRenderer
{
  bool mHasLoadedTextures;
  mce::TexturePtr mBubbleFullTexture;
  mce::TexturePtr mBubblePopTexture;
};

```

### `HudBubblesRenderer_vtbl`
```
struct /*VFT*/ HudBubblesRenderer_vtbl
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

### `HudCameraRenderer`
```
struct __cppobj __declspec(align(8)) HudCameraRenderer : MinecraftUICustomRenderer, CameraCallbacks
{
  _BYTE mState[4];
  float mShowTime;
  mce::TexturePtr mPhotoTexture;
  mce::MaterialPtr mColorMaterial;
  mce::MaterialPtr mTexMaterial;
  bool mImmediatePicture;
};

```

### `HudCameraRenderer_vtbl`
```
struct /*VFT*/ HudCameraRenderer_vtbl
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

### `HudCursorRenderer`
```
struct __cppobj HudCursorRenderer : MinecraftUICustomRenderer
{
  mce::MaterialPtr mCrosshairMat;
  mce::TexturePtr mCrosshair;
};

```

### `HudCursorRenderer_vtbl`
```
struct /*VFT*/ HudCursorRenderer_vtbl
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

### `HudDebugOverlayRenderer::WorkerStatsSnapshot`
```
struct __cppobj HudDebugOverlayRenderer::WorkerStatsSnapshot
{
  unsigned __int64 queued;
  unsigned __int64 reQueued;
  unsigned __int64 processed;
  unsigned __int64 noops;
  unsigned __int64 maxQueued;
  unsigned __int64 sorts;
  unsigned __int64 waits;
};

```

### `HudDebugOverlayRenderer::WorkerStats`
```
struct __cppobj HudDebugOverlayRenderer::WorkerStats
{
  HudDebugOverlayRenderer::WorkerStatsSnapshot last;
  HudDebugOverlayRenderer::WorkerStatsSnapshot curr;
};

```

### `HudDebugOverlayRenderer::TaskStatsSnapshot`
```
struct __cppobj HudDebugOverlayRenderer::TaskStatsSnapshot
{
  unsigned __int64 count;
  unsigned __int64 maxCount;
};

```

### `HudDebugOverlayRenderer::TaskStats`
```
struct __cppobj HudDebugOverlayRenderer::TaskStats
{
  HudDebugOverlayRenderer::TaskStatsSnapshot last;
  HudDebugOverlayRenderer::TaskStatsSnapshot curr;
};

```

### `HudDebugOverlayRenderer::SpinLockMetrics`
```
struct HudDebugOverlayRenderer::SpinLockMetrics
{
  unsigned __int64 contention;
  unsigned __int64 contentionBlocked;
  unsigned __int64 blockedTicks;
  unsigned __int64 blockedTicksMax;
  unsigned __int64 yields;
  unsigned __int64 lockCount;
  unsigned __int64 lockTicks;
  unsigned __int64 lockTicksMax;
};

```

### `HudDebugOverlayRenderer::SpinLockStats`
```
struct HudDebugOverlayRenderer::SpinLockStats
{
  HudDebugOverlayRenderer::SpinLockMetrics last;
  HudDebugOverlayRenderer::SpinLockMetrics curr;
};

```

### `HudDebugOverlayRenderer`
```
struct __cppobj HudDebugOverlayRenderer
{
  mce::MaterialPtr mDebugDepthArrayTextureMaterial;
  std::unordered_map<BackgroundWorker *,HudDebugOverlayRenderer::WorkerStats> mWorkerStats;
  std::unordered_map<BackgroundWorker *,HudDebugOverlayRenderer::WorkerStats> mCurrentWorkerStats;
  HudDebugOverlayRenderer::TaskStats mTaskStats;
  HudDebugOverlayRenderer::SpinLockStats mSpinLockStats;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastUpdateTime;
};

```

### `HudHeartRenderer`
```
struct __cppobj HudHeartRenderer : MinecraftUICustomRenderer
{
  bool mHasLoadedTextures;
  mce::TexturePtr mHeartBackgroundTexture;
  mce::TexturePtr mHeartBlinkTexture;
  mce::TexturePtr mHeartFullTexture;
  mce::TexturePtr mHeartHalfTexture;
  mce::TexturePtr mHeartPoisonFullTexture;
  mce::TexturePtr mHeartPoisonHalfTexture;
  mce::TexturePtr mHeartWitherFullTexture;
  mce::TexturePtr mHeartWitherHalfTexture;
  mce::TexturePtr mHeartAbsorptionFullTexture;
  mce::TexturePtr mHeartAbsorptionHalfTexture;
  mce::TexturePtr mHeartFlashFullTexture;
  mce::TexturePtr mHeartFlashHalfTexture;
  mce::TexturePtr mHeartPoisonFlashFullTexture;
  mce::TexturePtr mHeartPoisonFlashHalfTexture;
  mce::TexturePtr mHeartWitherFlashFullTexture;
  mce::TexturePtr mHeartWitherFlashHalfTexture;
};

```

### `HudHeartRenderer_vtbl`
```
struct /*VFT*/ HudHeartRenderer_vtbl
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

### `HudHorseHeartRenderer`
```
struct __cppobj HudHorseHeartRenderer : MinecraftUICustomRenderer
{
  bool mHasLoadedTextures;
  mce::TexturePtr mHeartHorseBackgroundTexture;
  mce::TexturePtr mHeartHorseBlinkTexture;
  mce::TexturePtr mHeartHorseFullTexture;
  mce::TexturePtr mHeartHorseHalfTexture;
  mce::TexturePtr mHeartHorseFlashFullTexture;
  mce::TexturePtr mHeartHorseFlashHalfTexture;
};

```

### `HudHorseHeartRenderer_vtbl`
```
struct /*VFT*/ HudHorseHeartRenderer_vtbl
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

### `HudHorseJumpRenderer`
```
struct __cppobj __declspec(align(8)) HudHorseJumpRenderer : MinecraftUICustomRenderer
{
  mce::TexturePtr mHorseJumpEmpty;
  mce::TexturePtr mHorseJumpFull;
  bool mHasLoadedTextures;
};

```

### `HudHorseJumpRenderer_vtbl`
```
struct /*VFT*/ HudHorseJumpRenderer_vtbl
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

### `HudHungerRenderer`
```
struct __cppobj HudHungerRenderer : MinecraftUICustomRenderer
{
  int mTickCount;
  bool mHasLoadedTextures;
  mce::TexturePtr gHungerBackgroundTexture;
  mce::TexturePtr gHungerBlinkTexture;
  mce::TexturePtr gHungerEffectBackgroundTexture;
  mce::TexturePtr gHungerFullTexture;
  mce::TexturePtr gHungerHalfTexture;
  mce::TexturePtr gHungerFlashFullTexture;
  mce::TexturePtr gHungerFlashHalfTexture;
  mce::TexturePtr gHungerEffectFullTexture;
  mce::TexturePtr gHungerEffectHalfTexture;
  mce::TexturePtr gHungerEffectFlashFullTexture;
  mce::TexturePtr gHungerEffectFlashHalfTexture;
};

```

### `HudHungerRenderer_vtbl`
```
struct /*VFT*/ HudHungerRenderer_vtbl
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

### `HudMobEffectsRenderer`
```
struct __cppobj HudMobEffectsRenderer : MinecraftUICustomRenderer
{
};

```

### `HudMobEffectsRenderer_vtbl`
```
struct /*VFT*/ HudMobEffectsRenderer_vtbl
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

### `HudPlayerRenderer`
```
struct __cppobj HudPlayerRenderer : MinecraftUICustomRenderer
{
  float mRenderTime;
  float mLastTimeStamp;
  std::vector<int> mPlayerArmorState;
};

```

### `HudPlayerRenderer_vtbl`
```
struct /*VFT*/ HudPlayerRenderer_vtbl
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

### `HudProgressRenderer`
```
struct __cppobj __declspec(align(8)) HudProgressRenderer : MinecraftUICustomRenderer
{
  float mProgressAlpha;
};

```

### `HudProgressRenderer_vtbl`
```
struct /*VFT*/ HudProgressRenderer_vtbl
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

### `HudVignetteRenderer`
```
struct __cppobj HudVignetteRenderer : MinecraftUICustomRenderer
{
  float mLastVignetteOpacity;
  float mLastAB;
  mce::Mesh mVignette;
};

```

### `HudVignetteRenderer_vtbl`
```
struct /*VFT*/ HudVignetteRenderer_vtbl
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

### `hbui::FacetBase<hbui::AchievementsFacet>`
```
struct __cppobj hbui::FacetBase<hbui::AchievementsFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::AchievementsFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::AchievementsFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::AchievementsFacet::FacetAchievementData`
```
struct __cppobj __declspec(align(8)) hbui::AchievementsFacet::FacetAchievementData
{
  std::string mId;
  std::string mAchievementName;
  std::string mDescription;
  int mGamerScore;
  __int64 mDateUnlocked;
  std::string mAchievementImageURL;
  bool mIsLocked;
  bool mIsSecret;
  float mProgressCompleted;
  float mProgressTarget;
  std::string mPersonaRewardId;
  bool mHasPersonaReward;
  bool mIsPersonaRewardOwned;
  std::string mPersonaRewardName;
  std::string mPersonaRewardImageURL;
  persona::Rarity mPersonaRewardRarity;
};

```

### `hbui::AchievementsFacet::FacetPlayerAchievementData`
```
struct __cppobj hbui::AchievementsFacet::FacetPlayerAchievementData
{
  int mAchievementsUnlocked;
  int mMaxAchievements;
  int mTimePlayed;
  int mCurrGamerScore;
  int mMaxGamerScore;
  std::vector<hbui::AchievementsFacet::FacetAchievementData> mAchievementData;
};

```

### `hbui::AchievementsFacet`
```
struct __cppobj hbui::AchievementsFacet : hbui::FacetBase<hbui::AchievementsFacet>
{
  IClientInstance *mClient;
  hbui::ResourceRegistry *mResourceRegistry;
  std::unordered_map<Core::PathBuffer<std::string >,std::string,std::hash<Core::PathBuffer<std::string > >,std::equal_to<Core::PathBuffer<std::string > >,std::allocator<std::pair<Core::PathBuffer<std::string > const ,std::string > > > mRegisteredResources;
  hbui::AchievementsFacet::AchievementFacetStatus mStatus;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mLastRefresh;
  hbui::AchievementsFacet::FacetPlayerAchievementData mFacetPlayerAchievementData;
  persona::PersonaPieceCollectionModel *mPersonaPieceCollectionModel;
};

```

### `hbui::AchievementsFacet_vtbl`
```
struct /*VFT*/ hbui::AchievementsFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::DeviceInformationFacet>`
```
struct __cppobj hbui::FacetBase<hbui::DeviceInformationFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::DeviceInformationFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::DeviceInformationFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::DeviceInformationFacet`
```
struct __cppobj __declspec(align(8)) hbui::DeviceInformationFacet : hbui::FacetBase<hbui::DeviceInformationFacet>, AppPlatformListener
{
  bool mIsDirty;
  const IClientInstance *mClientInstance;
  _BYTE mPlatform[1];
  std::vector<enum hbui::InputMethod> mInputMethods;
  bool mIsLowMemoryDevice;
  float mPixelsPerMillimeter;
  int mGuiScale;
  int mGuiScaleModifier;
  int mGuiScaleBase;
};

```

### `hbui::DeviceInformationFacet_vtbl`
```
struct /*VFT*/ hbui::DeviceInformationFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::FeatureFlagsFacet>`
```
struct __cppobj hbui::FacetBase<hbui::FeatureFlagsFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::FeatureFlagsFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::FeatureFlagsFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FeatureFlagsFacet`
```
struct __cppobj hbui::FeatureFlagsFacet : hbui::FacetBase<hbui::FeatureFlagsFacet>
{
  std::vector<std::string> mFeatureFlags;
};

```

### `hbui::FeatureFlagsFacet_vtbl`
```
struct /*VFT*/ hbui::FeatureFlagsFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::InputFacet>`
```
struct __cppobj hbui::FacetBase<hbui::InputFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::InputFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::InputFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::InputFacet`
```
struct __cppobj hbui::InputFacet : hbui::FacetBase<hbui::InputFacet>
{
  IClientInstance *mClientInstance;
  bool mIsDirty;
  Bedrock::PubSub::ScopedSubscription mSwapABOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mSwapXYOptionSubscription;
  bool mAcceptInputFromAllControllers;
  int mGameControllerId;
  std::string mGameControllerIdString;
  bool mSwapABButtons;
  bool mSwapXYButtons;
  _BYTE mCurrentInputType[1];
  InputMode mCachedInputMode;
};

```

### `hbui::InputFacet_vtbl`
```
struct /*VFT*/ hbui::InputFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::LegacyScreenFacet>`
```
struct __cppobj hbui::FacetBase<hbui::LegacyScreenFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::LegacyScreenFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::LegacyScreenFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::LegacyScreenFacet`
```
struct __cppobj hbui::LegacyScreenFacet : hbui::FacetBase<hbui::LegacyScreenFacet>
{
  IScreenController *mScreenController;
};

```

### `hbui::LegacyScreenFacet_vtbl`
```
struct /*VFT*/ hbui::LegacyScreenFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::LocaleFacet>`
```
struct __cppobj hbui::FacetBase<hbui::LocaleFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::LocaleFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::LocaleFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::LocaleFacet`
```
struct __cppobj hbui::LocaleFacet : hbui::FacetBase<hbui::LocaleFacet>, AppPlatformListener
{
  bool mIsDirty;
  Option *mLanguageOption;
  Bedrock::PubSub::ScopedSubscription mLanguageOptionSubscription;
  std::string mLocale;
};

```

### `hbui::LocaleFacet_vtbl`
```
struct /*VFT*/ hbui::LocaleFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::LocalWorldsFacet>`
```
struct __cppobj hbui::FacetBase<hbui::LocalWorldsFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::LocalWorldsFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::LocalWorldsFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::LocalWorld`
```
struct __cppobj hbui::LocalWorld
{
  std::string id;
  std::string title;
  std::string imageURL;
};

```

### `hbui::LocalWorldsFacet`
```
struct __cppobj hbui::LocalWorldsFacet : hbui::FacetBase<hbui::LocalWorldsFacet>
{
  std::vector<hbui::LocalWorld> mLocalWorlds;
  ILocalWorldsProvider *mLocalWorldsProvider;
};

```

### `hbui::LocalWorldsFacet_vtbl`
```
struct /*VFT*/ hbui::LocalWorldsFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::SafeZoneFacet>`
```
struct __cppobj hbui::FacetBase<hbui::SafeZoneFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::SafeZoneFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::SafeZoneFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::OptionWrapper<float>`
```
struct __cppobj hbui::OptionWrapper<float>
{
  Option *mOption;
  Bedrock::PubSub::ScopedSubscription mOptionSubscription;
};

```

### `hbui::SafeZoneFacet`
```
struct __cppobj hbui::SafeZoneFacet : hbui::FacetBase<hbui::SafeZoneFacet>
{
  bool mIsDirty;
  float mSafeZoneX;
  float mSafeZoneY;
  float mScreenPositionX;
  float mScreenPositionY;
  hbui::OptionWrapper<float> mSafeZoneXOption;
  hbui::OptionWrapper<float> mSafeZoneYOption;
  hbui::OptionWrapper<float> mScreenPositionXOption;
  hbui::OptionWrapper<float> mScreenPositionYOption;
};

```

### `hbui::SafeZoneFacet_vtbl`
```
struct /*VFT*/ hbui::SafeZoneFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::ScreenReaderFacet>`
```
struct __cppobj hbui::FacetBase<hbui::ScreenReaderFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::ScreenReaderFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::ScreenReaderFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::ScreenReaderFacet`
```
struct __cppobj hbui::ScreenReaderFacet : hbui::FacetBase<hbui::ScreenReaderFacet>
{
  IClientInstance *mClientInstance;
  bool mIsDirty;
  bool mIsChatTextToSpeechEnabled;
  bool mIsUITextToSpeechEnabled;
  Bedrock::PubSub::ScopedSubscription mChatOptionSubscription;
  Bedrock::PubSub::ScopedSubscription mUIOptionSubscription;
};

```

### `hbui::ScreenReaderFacet_vtbl`
```
struct /*VFT*/ hbui::ScreenReaderFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::SoundFacet>`
```
struct __cppobj hbui::FacetBase<hbui::SoundFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::SoundFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::SoundFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::SoundFacet`
```
struct __cppobj hbui::SoundFacet : hbui::FacetBase<hbui::SoundFacet>
{
  Bedrock::NonOwnerPointer<SoundPlayerInterface> mSoundPlayer;
};

```

### `hbui::SoundFacet_vtbl`
```
struct /*VFT*/ hbui::SoundFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::SplitScreenFacet>`
```
struct __cppobj hbui::FacetBase<hbui::SplitScreenFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::SplitScreenFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::SplitScreenFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::SplitScreenFacet`
```
struct __cppobj __declspec(align(8)) hbui::SplitScreenFacet : hbui::FacetBase<hbui::SplitScreenFacet>
{
  bool mIsDirty;
  IMinecraftGame *mMinecraftGame;
  int mSplitScreenPosition;
  int mActivePlayers;
  SplitScreenDirection mSplitScreenDirection;
};

```

### `hbui::SplitScreenFacet_vtbl`
```
struct /*VFT*/ hbui::SplitScreenFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::ToastFacet>`
```
struct __cppobj hbui::FacetBase<hbui::ToastFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::ToastFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::ToastFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::ToastFacet`
```
struct __cppobj hbui::ToastFacet : hbui::FacetBase<hbui::ToastFacet>
{
  ToastManager *mToastManager;
};

```

### `hbui::ToastFacet_vtbl`
```
struct /*VFT*/ hbui::ToastFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetBase<hbui::UserFacet>`
```
struct __cppobj hbui::FacetBase<hbui::UserFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::UserFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::UserFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::UserFacet`
```
struct __cppobj hbui::UserFacet : hbui::FacetBase<hbui::UserFacet>
{
  std::string mName;
  std::string mProfilePicturePath;
  IClientInstance *mClientInstance;
  std::string mOriginalProfilePicturePath;
};

```

### `hbui::UserFacet_vtbl`
```
struct /*VFT*/ hbui::UserFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::FacetRegistry`
```
struct __cppobj hbui::FacetRegistry : hbui::IFacetRegistry
{
  std::vector<hbui::FacetRegistry::FacetEntry> mFacets;
};

```

### `hbui::FacetRegistry_vtbl`
```
struct /*VFT*/ hbui::FacetRegistry_vtbl
{
  void (__fastcall *~IFacetRegistry)(hbui::IFacetRegistry *this);
  void (__fastcall *registerFacet)(hbui::IFacetRegistry *this, const std::string *, const std::function<std::unique_ptr<hbui::IFacet> __cdecl(void)> *);
  std::optional<enum hbui::IFacetRegistry::Error> *(__fastcall *activateFacet)(hbui::IFacetRegistry *this, std::optional<enum hbui::IFacetRegistry::Error> *result, hbui::FacetBinder *, const std::string *);
  std::optional<enum hbui::IFacetRegistry::Error> *(__fastcall *deactivateFacet)(hbui::IFacetRegistry *this, std::optional<enum hbui::IFacetRegistry::Error> *result, hbui::FacetBinder *, const std::string *);
  void (__fastcall *deactivateAllFacets)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
  void (__fastcall *bind)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
  void (__fastcall *update)(hbui::IFacetRegistry *this, hbui::FacetBinder *);
};

```

### `hbui::TestFacet::ComplexType`
```
struct hbui::TestFacet::ComplexType
{
  int nestedNumber;
};

```

### `hbui::FacetBase<hbui::TestFacet>`
```
struct __cppobj hbui::FacetBase<hbui::TestFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<hbui::TestFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<hbui::TestFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::TestFacet`
```
struct __cppobj __declspec(align(8)) hbui::TestFacet : hbui::FacetBase<hbui::TestFacet>
{
  unsigned int mIncrementingNumber;
  int mShallowNumber;
  std::string mShallowString;
  hbui::TestFacet::ComplexType mShallowComplexType;
  std::vector<hbui::TestFacet::ComplexType> mNestedTypeArray;
  bool mIsDirty;
  bool mShouldAutoIncrement;
};

```

### `hbui::TestFacet_vtbl`
```
struct /*VFT*/ hbui::TestFacet_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::OptionWrapper<float>::{ctor}::__l5::<lambda_5e7c5eb415c6d84f19e6135729d9635d>`
```
struct __cppobj hbui::OptionWrapper<float>::{ctor}::__l5::<lambda_5e7c5eb415c6d84f19e6135729d9635d>
{
  hbui::OptionWrapper<float> *const __this;
  float *value;
  bool *isDirty;
};

```

### `hbui::FacetRegistry::bind::__l2::<lambda_6cf8e22b1f259530c328b3a73be09bd3>`
```
struct __cppobj hbui::FacetRegistry::bind::__l2::<lambda_6cf8e22b1f259530c328b3a73be09bd3>
{
  hbui::FacetRegistry *const __this;
  hbui::FacetBinder *binder;
};

```

### `hbui::FacetRegistry::bind::__l2::<lambda_6066c263a20a7513df33bbb78d085ae3>`
```
struct __cppobj hbui::FacetRegistry::bind::__l2::<lambda_6066c263a20a7513df33bbb78d085ae3>
{
  hbui::FacetRegistry *const __this;
  hbui::FacetBinder *binder;
};

```

### `hbui::SplitScreenFacet::{ctor}::__l2::<lambda_a3896d9a4b97bcf25b659c18160e311f>`
```
struct __cppobj hbui::SplitScreenFacet::{ctor}::__l2::<lambda_a3896d9a4b97bcf25b659c18160e311f>
{
  hbui::SplitScreenFacet *const __this;
  const IClientInstance *clientInstance;
};

```

### `hbui::ScreenReaderFacet::_registerObservers::__l8::<lambda_5ae2404388e2ae8d14c2c1abb873009d>`
```
struct __cppobj hbui::ScreenReaderFacet::_registerObservers::__l8::<lambda_5ae2404388e2ae8d14c2c1abb873009d>
{
  hbui::ScreenReaderFacet *const __this;
};

```

### `hbui::ScreenReaderFacet::_registerObservers::__l5::<lambda_ff6107dbe840263fd2607a3531d764fb>`
```
struct __cppobj hbui::ScreenReaderFacet::_registerObservers::__l5::<lambda_ff6107dbe840263fd2607a3531d764fb>
{
  hbui::ScreenReaderFacet *const __this;
};

```

### `hbui::LocaleFacet::_registerObservers::__l5::<lambda_34070cf23042ac96cc4b06279f26c9e2>`
```
struct __cppobj hbui::LocaleFacet::_registerObservers::__l5::<lambda_34070cf23042ac96cc4b06279f26c9e2>
{
  hbui::LocaleFacet *const __this;
};

```

### `hbui::InputFacet::_registerObservers::__l10::<lambda_3b26e34c65f70ca7014fa632ac7bfb5b>`
```
struct __cppobj hbui::InputFacet::_registerObservers::__l10::<lambda_3b26e34c65f70ca7014fa632ac7bfb5b>
{
  hbui::InputFacet *const __this;
};

```

### `hbui::InputFacet::_registerObservers::__l6::<lambda_ad7d2f101c9885bd05e57617f5a1d792>`
```
struct __cppobj hbui::InputFacet::_registerObservers::__l6::<lambda_ad7d2f101c9885bd05e57617f5a1d792>
{
  hbui::InputFacet *const __this;
};

```

### `hbui::FacetBase<ScriptApi::ScriptEngineFacet>`
```
struct __cppobj hbui::FacetBase<ScriptApi::ScriptEngineFacet> : hbui::IFacet
{
};

```

### `hbui::FacetBase<ScriptApi::ScriptEngineFacet>_vtbl`
```
struct /*VFT*/ hbui::FacetBase<ScriptApi::ScriptEngineFacet>_vtbl
{
  void (__fastcall *~IFacet)(hbui::IFacet *this);
  void (__fastcall *bindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *unbindFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  void (__fastcall *updateFacet)(hbui::IFacet *this, hbui::FacetBinder *);
  bool (__fastcall *update)(hbui::IFacet *this);
};

```

### `hbui::TouchEventData`
```
struct __cppobj hbui::TouchEventData
{
  Vec2 pos;
  unsigned int id;
  hbui::TouchEventData::EventType type;
};

```

### `hbui::GestureEventData::<unnamed_type_panDetails>`
```
struct __cppobj hbui::GestureEventData::<unnamed_type_panDetails>
{
  Vec2 delta;
};

```

### `hbui::GestureEventData::<unnamed_type_flingDetails>`
```
struct hbui::GestureEventData::<unnamed_type_flingDetails>
{
  float duration;
};

```

### `hbui::GestureEventData`
```
struct __cppobj hbui::GestureEventData
{
  hbui::GestureEventData::<unnamed_type_panDetails> panDetails;
  hbui::GestureEventData::<unnamed_type_flingDetails> flingDetails;
  Vec2 currentLocation;
  Vec2 startLocation;
  _BYTE type[4];
};

```

### `hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos`
```
struct __cppobj hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos
{
  hbui::TouchEventData touchEventData;
  Vec2 currentPos;
};

```

### `hbui::GestureRecognizerBase`
```
struct __cppobj __declspec(align(8)) hbui::GestureRecognizerBase
{
  hbui::GestureRecognizerBase_vtbl *__vftable /*VFT*/;
  hbui::IGestureListener *mGestureListener;
  std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> mTrackingTouches;
  std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> mTrackedTouchesWithinTouchesToRecognize;
  float mPixelsPerCm;
  std::function<double __cdecl(void)> mGetTimeS;
  hbui::GestureRecognizerBase::GestureRecognizerState mState;
  bool mEnabled;
  bool mSentTouchesBegan;
  bool mSentTouchesMoved;
  bool mSentTouchesEnded;
  int mPriority;
};

```

### `hbui::GestureRecognizerBase_vtbl`
```
struct /*VFT*/ hbui::GestureRecognizerBase_vtbl
{
  void (__fastcall *~GestureRecognizerBase)(hbui::GestureRecognizerBase *this);
  void (__fastcall *onTouchesBegan)(hbui::GestureRecognizerBase *this, const std::vector<hbui::TouchEventData> *);
  void (__fastcall *onTouchesMoved)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onTouchesEnded)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onGestureRecognized)(hbui::GestureRecognizerBase *this);
};

```

### `hbui::IGestureListener`
```
struct __cppobj hbui::IGestureListener
{
  hbui::IGestureListener_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IGestureListener_vtbl`
```
struct /*VFT*/ hbui::IGestureListener_vtbl
{
  void (__fastcall *~IGestureListener)(hbui::IGestureListener *this);
  void (__fastcall *onPanRecognized)(hbui::IGestureListener *this, const Vec2 *, const Vec2 *, const Vec2 *);
  void (__fastcall *onPanCompleted)(hbui::IGestureListener *this, const Vec2 *);
  void (__fastcall *onFlingCompleted)(hbui::IGestureListener *this, const Vec2 *, const Vec2 *, float);
  void (__fastcall *onTapRecognized)(hbui::IGestureListener *this, const Vec2 *);
};

```

### `hbui::FlingRecognizer`
```
struct __cppobj hbui::FlingRecognizer : hbui::GestureRecognizerBase
{
  const unsigned __int64 mMinimumNumberOfTouches;
  const unsigned __int64 mMaximumNumberOfTouches;
  const long double mMaxFlingIntervalBetweenMovesS;
  const float mMinDistanceToFlingCm;
  Vec2 mPreviousLocation;
  long double mPreviousTouchTimeForGesture;
  long double mFlingStartTime;
  Vec2 mFlingStart;
};

```

### `hbui::FlingRecognizer_vtbl`
```
struct /*VFT*/ hbui::FlingRecognizer_vtbl
{
  void (__fastcall *~GestureRecognizerBase)(hbui::GestureRecognizerBase *this);
  void (__fastcall *onTouchesBegan)(hbui::GestureRecognizerBase *this, const std::vector<hbui::TouchEventData> *);
  void (__fastcall *onTouchesMoved)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onTouchesEnded)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onGestureRecognized)(hbui::GestureRecognizerBase *this);
};

```

### `hbui::ITouchSystem`
```
struct __cppobj hbui::ITouchSystem
{
  hbui::ITouchSystem_vtbl *__vftable /*VFT*/;
};

```

### `hbui::ITouchSystem_vtbl`
```
struct /*VFT*/ hbui::ITouchSystem_vtbl
{
  void (__fastcall *~ITouchSystem)(hbui::ITouchSystem *this);
  void (__fastcall *sendTouchEvents)(hbui::ITouchSystem *this, const std::vector<hbui::TouchEventData> *);
  void (__fastcall *sendGestureEvent)(hbui::ITouchSystem *this, const hbui::GestureEventData *);
};

```

### `hbui::GestureManager`
```
struct __cppobj hbui::GestureManager
{
  std::vector<std::unique_ptr<hbui::GestureRecognizerBase>> mRecognizers;
};

```

### `hbui::GesturePolicy`
```
struct __cppobj hbui::GesturePolicy : hbui::IGestureListener
{
  hbui::ITouchSystem *mTouchSystem;
  hbui::GestureManager mGestureManager;
};

```

### `hbui::GesturePolicy_vtbl`
```
struct /*VFT*/ hbui::GesturePolicy_vtbl
{
  void (__fastcall *~IGestureListener)(hbui::IGestureListener *this);
  void (__fastcall *onPanRecognized)(hbui::IGestureListener *this, const Vec2 *, const Vec2 *, const Vec2 *);
  void (__fastcall *onPanCompleted)(hbui::IGestureListener *this, const Vec2 *);
  void (__fastcall *onFlingCompleted)(hbui::IGestureListener *this, const Vec2 *, const Vec2 *, float);
  void (__fastcall *onTapRecognized)(hbui::IGestureListener *this, const Vec2 *);
};

```

### `hbui::TapRecognizer`
```
struct __cppobj hbui::TapRecognizer : hbui::GestureRecognizerBase
{
  const unsigned int mMaximumNumberOfTouches;
  const long double mTimeToleranceS;
  const float mTapDistanceToleranceCm;
  Vec2 mStartPoint;
  long double mLastTouchTimestamp;
};

```

### `hbui::TapRecognizer_vtbl`
```
struct /*VFT*/ hbui::TapRecognizer_vtbl
{
  void (__fastcall *~GestureRecognizerBase)(hbui::GestureRecognizerBase *this);
  void (__fastcall *onTouchesBegan)(hbui::GestureRecognizerBase *this, const std::vector<hbui::TouchEventData> *);
  void (__fastcall *onTouchesMoved)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onTouchesEnded)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onGestureRecognized)(hbui::GestureRecognizerBase *this);
};

```

### `hbui::PanRecognizer`
```
struct __cppobj hbui::PanRecognizer : hbui::GestureRecognizerBase
{
  const unsigned __int64 mMinimumNumberOfTouches;
  const unsigned __int64 mMaximumNumberOfTouches;
  const float mMinDistanceToPanCm;
  float mTotalDeltaMovementInCm;
  Vec2 mPreviousLocation;
  Vec2 mStartPoint;
  Vec2 mEndPoint;
  Vec2 mDeltaTranslation;
};

```

### `hbui::PanRecognizer_vtbl`
```
struct /*VFT*/ hbui::PanRecognizer_vtbl
{
  void (__fastcall *~GestureRecognizerBase)(hbui::GestureRecognizerBase *this);
  void (__fastcall *onTouchesBegan)(hbui::GestureRecognizerBase *this, const std::vector<hbui::TouchEventData> *);
  void (__fastcall *onTouchesMoved)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onTouchesEnded)(hbui::GestureRecognizerBase *this, const std::vector<hbui::GestureRecognizerBase::TouchEventDataWithCurrentPos> *);
  void (__fastcall *onGestureRecognized)(hbui::GestureRecognizerBase *this);
};

```

### `HummingbirdUI::_registerToggleObservers::__l8::<lambda_65fa83552ca5e7be58a344e69c942bb3>`
```
struct __cppobj HummingbirdUI::_registerToggleObservers::__l8::<lambda_65fa83552ca5e7be58a344e69c942bb3>
{
  HummingbirdUI *const __this;
};

```

### `HummingbirdUI::_registerToggleObservers::__l5::<lambda_ede23b58d9466ab0eecaabf665c4ae6f>`
```
struct __cppobj HummingbirdUI::_registerToggleObservers::__l5::<lambda_ede23b58d9466ab0eecaabf665c4ae6f>
{
  HummingbirdUI *const __this;
};

```

### `HummingbirdUI::_registerToggleObservers::__l2::<lambda_04aa32db8b81ea2ad470eb40b776b578>`
```
struct __cppobj HummingbirdUI::_registerToggleObservers::__l2::<lambda_04aa32db8b81ea2ad470eb40b776b578>
{
  HummingbirdUI *const __this;
};

```

### `hbui::Scene::init::__l2::<lambda_a0f580796429890ad766443cc20dda62>`
```
struct __cppobj hbui::Scene::init::__l2::<lambda_a0f580796429890ad766443cc20dda62>
{
};

```

### `hbui::Scene::init::__l2::<lambda_b0e36d1425fd16211c03af30c4297f0b>`
```
struct __cppobj hbui::Scene::init::__l2::<lambda_b0e36d1425fd16211c03af30c4297f0b>
{
};

```

### `hbui::Scene::init::__l2::<lambda_c102446960817e9a9b5b64dd6cc74790>`
```
struct __cppobj hbui::Scene::init::__l2::<lambda_c102446960817e9a9b5b64dd6cc74790>
{
  hbui::Scene *const __this;
};

```

### `hbui::SceneProvider::createScene::__l2::<lambda_b8946bc37d35e6137b2e4d7a3bcc47ca>`
```
struct __cppobj hbui::SceneProvider::createScene::__l2::<lambda_b8946bc37d35e6137b2e4d7a3bcc47ca>
{
  ISceneStack *sceneStack;
};

```

### `hbui::GamepadState`
```
struct __cppobj hbui::GamepadState
{
  int gamepadId;
  std::array<enum hbui::GamepadButtonState,33> buttonStates;
  std::array<float,33> buttonValues;
  std::array<float,4> axisStates;
};

```

### `hbui::GameControllerInputHandler`
```
struct __cppobj __declspec(align(8)) hbui::GameControllerInputHandler
{
  IGameControllerManager *mGameControllerManager;
  std::vector<hbui::GamepadState> mGamepadStates;
  bool mWasActiveLastTime;
};

```

### `hbui::IGamepadSystem`
```
struct __cppobj hbui::IGamepadSystem
{
  hbui::IGamepadSystem_vtbl *__vftable /*VFT*/;
};

```

### `hbui::IGamepadSystem_vtbl`
```
struct /*VFT*/ hbui::IGamepadSystem_vtbl
{
  void (__fastcall *~IGamepadSystem)(hbui::IGamepadSystem *this);
  void (__fastcall *registerGamepad)(hbui::IGamepadSystem *this, int, const std::string *);
  void (__fastcall *unregisterGamepad)(hbui::IGamepadSystem *this, int);
  void (__fastcall *updateGamepadState)(hbui::IGamepadSystem *this, hbui::GamepadState *, float);
  void (__fastcall *updateGamepadStateExtended)(hbui::IGamepadSystem *this, const hbui::GamepadState *, float);
};

```

### `hbui::ITouchInput`
```
struct __cppobj hbui::ITouchInput
{
  hbui::ITouchInput_vtbl *__vftable /*VFT*/;
};

```

### `hbui::ITouchInput_vtbl`
```
struct /*VFT*/ hbui::ITouchInput_vtbl
{
  void (__fastcall *~ITouchInput)(hbui::ITouchInput *this);
  const std::vector<int> *(__fastcall *getActivePointerIdsThisUpdate)(hbui::ITouchInput *this, const std::vector<int> *result);
  __int16 (__fastcall *getX)(hbui::ITouchInput *this, int);
  __int16 (__fastcall *getY)(hbui::ITouchInput *this, int);
  bool (__fastcall *isPressed)(hbui::ITouchInput *this, int);
  bool (__fastcall *isEdgeTouch)(hbui::ITouchInput *this, int);
  bool (__fastcall *isPointerDown)(hbui::ITouchInput *this, int);
};

```

### `hbui::ActiveTouch`
```
struct __cppobj __declspec(align(4)) hbui::ActiveTouch
{
  int id;
  Vec2 origin;
  Vec2 currentLocation;
  bool hasMoved;
};

```

### `hbui::TouchInputHandler`
```
struct __cppobj hbui::TouchInputHandler
{
  std::unique_ptr<hbui::ITouchInput> mTouchInput;
  std::unique_ptr<hbui::ITouchSystem> mTouchSystem;
  std::unique_ptr<hbui::GesturePolicy> mGesturePolicy;
  std::vector<hbui::ActiveTouch> mActiveTouches;
};

```

### `hbui::RouterConfiguration::_addAchievementsRouteToMatcher::__l5::<lambda_81c8189686239e53df73b08a181027a5>`
```
struct __cppobj hbui::RouterConfiguration::_addAchievementsRouteToMatcher::__l5::<lambda_81c8189686239e53df73b08a181027a5>
{
  SceneFactory *sceneFactory;
  ISceneStack *sceneStack;
};

```

### `hbui::RouterConfiguration::_addPersonaRouteToMatcher::__l9::<lambda_4e587607a05bd4df095d17592af911f5>`
```
struct __cppobj hbui::RouterConfiguration::_addPersonaRouteToMatcher::__l9::<lambda_4e587607a05bd4df095d17592af911f5>
{
  SceneFactory *sceneFactory;
  ISceneStack *sceneStack;
};

```

### `hbui::RouterConfiguration::createOutOfGameRouteMatcher::__l9::<lambda_e7171c66b973a5665fbb403dbb2c2862>`
```
struct __cppobj hbui::RouterConfiguration::createOutOfGameRouteMatcher::__l9::<lambda_e7171c66b973a5665fbb403dbb2c2862>
{
  SceneFactory *sceneFactory;
  ISceneStack *sceneStack;
  const hbui::Route *routeEntry;
};

```

### `hbui::RouterConfiguration::createInGameRouteMatcher::__l9::<lambda_b1e01b8ba6fa85f066e412929aa6b2d5>`
```
struct __cppobj hbui::RouterConfiguration::createInGameRouteMatcher::__l9::<lambda_b1e01b8ba6fa85f066e412929aa6b2d5>
{
  SceneFactory *sceneFactory;
  ISceneStack *sceneStack;
  const hbui::Route *routeEntry;
};

```

### `hbui::Router::_onChange::__l2::<lambda_ca382762252883c93e5f24dc2b0c8635>`
```
struct __cppobj __declspec(align(8)) hbui::Router::_onChange::__l2::<lambda_ca382762252883c93e5f24dc2b0c8635>
{
  const std::optional<hbui::RouterLocation> previousLocation;
  const hbui::RouterLocation currentLocation;
  const hbui::RouterAction action;
};

```

### `hbui::loadJsonFromHybridResources::__l6::<lambda_44461f9abae851eab9a9c18a435bebbd>`
```
struct __cppobj hbui::loadJsonFromHybridResources::__l6::<lambda_44461f9abae851eab9a9c18a435bebbd>
{
  std::string *resourceStream;
};

```

### `HdrCalibrationScreenController`
```
struct __cppobj __declspec(align(8)) HdrCalibrationScreenController : MinecraftScreenController
{
  float mCalibrationSliderPercent;
};

```

### `HdrCalibrationScreenController_vtbl`
```
struct /*VFT*/ HdrCalibrationScreenController_vtbl
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

### `HowToPlayScreenController`
```
struct __cppobj __declspec(align(8)) HowToPlayScreenController : MainMenuScreenController
{
  std::string mCurrentTabTitle;
  HowToPlayTopicIndex mCurrentTab;
  HowToPlayTopicIndex mInitialTab;
  bool mInitialTabSelected;
};

```

### `HowToPlayScreenController_vtbl`
```
struct /*VFT*/ HowToPlayScreenController_vtbl
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

### `HowToPlayScreenControllerProxyCallbacks`
```
struct __cppobj HowToPlayScreenControllerProxyCallbacks
{
  std::function<void __cdecl(int)> mChangeTab;
};

```

### `HowToPlayScreenControllerProxy`
```
struct __cppobj HowToPlayScreenControllerProxy : ScreenControllerProxy
{
  const HowToPlayScreenControllerProxyCallbacks mCallbacks;
};

```

### `HowToPlayScreenControllerProxy_vtbl`
```
struct /*VFT*/ HowToPlayScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `HowToPlayScreenController::_registerEventHandlers::__l2::<lambda_df79304cc9649fb67bf9353cd28ebf6e>`
```
struct __cppobj HowToPlayScreenController::_registerEventHandlers::__l2::<lambda_df79304cc9649fb67bf9353cd28ebf6e>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerEventHandlers::__l2::<lambda_8ed3ed5e7ff5517b92878b3114b94405>`
```
struct __cppobj HowToPlayScreenController::_registerEventHandlers::__l2::<lambda_8ed3ed5e7ff5517b92878b3114b94405>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerControllerCallbacks::__l2::<lambda_3df758b5b4c13cd9b28dec94ab6a2f24>`
```
struct __cppobj HowToPlayScreenController::_registerControllerCallbacks::__l2::<lambda_3df758b5b4c13cd9b28dec94ab6a2f24>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerControllerCallbacks::__l2::<lambda_3df758b5b4c13cd9b28dec94ab6a2f24>::()::__l2::<lambda_696e9f1d37641dc281f8ace2b56e28eb>`
```
struct __cppobj HowToPlayScreenController::_registerControllerCallbacks::__l2::<lambda_3df758b5b4c13cd9b28dec94ab6a2f24>::()::__l2::<lambda_696e9f1d37641dc281f8ace2b56e28eb>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_98980cad79d6be51a970ed8b8a173214>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_98980cad79d6be51a970ed8b8a173214>
{
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_3e638c576b835e1ca482eeb052965021>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_3e638c576b835e1ca482eeb052965021>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_7df109e05f81532ad44d42e1d67f6a9e>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_7df109e05f81532ad44d42e1d67f6a9e>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_09d820a0cb2cc4cac0a8a8313d479d20>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_09d820a0cb2cc4cac0a8a8313d479d20>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_e03c3214a50b8f20f4a5670fcc3b81ff>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_e03c3214a50b8f20f4a5670fcc3b81ff>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_9ce3b3187c64fdea79f2e075c2b0e68c>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_9ce3b3187c64fdea79f2e075c2b0e68c>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_a893d1a64f2d99f078fe2b0ca5f81962>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_a893d1a64f2d99f078fe2b0ca5f81962>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_013a21fcd39d0c31c90d5c67a77acc75>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_013a21fcd39d0c31c90d5c67a77acc75>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_dd5bc4d1a3b691c61f18e7e5ff239919>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_dd5bc4d1a3b691c61f18e7e5ff239919>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_cc9c32b4c0f9d03fa404b76987170fd6>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_cc9c32b4c0f9d03fa404b76987170fd6>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_2082268c4a2becb732c3d6439028974e>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_2082268c4a2becb732c3d6439028974e>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_291b19c5d96adffbb9e7233717fc17be>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_291b19c5d96adffbb9e7233717fc17be>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_15a24123e7032ce14c4f6a0cddfb6aec>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_15a24123e7032ce14c4f6a0cddfb6aec>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::_registerBindings::__l2::<lambda_ebc5cd8dba9baf966beeb4271f47b30c>`
```
struct __cppobj HowToPlayScreenController::_registerBindings::__l2::<lambda_ebc5cd8dba9baf966beeb4271f47b30c>
{
  HowToPlayScreenController *const __this;
};

```

### `HowToPlayScreenController::{ctor}::__l2::<lambda_1a1204ee0fbb79e5ac63c518e03feff6>`
```
struct __cppobj HowToPlayScreenController::{ctor}::__l2::<lambda_1a1204ee0fbb79e5ac63c518e03feff6>
{
  HowToPlayScreenController *const __this;
};

```

### `HdrCalibrationScreenController::_registerBindings::__l2::<lambda_0090d31c2cd362a2b64f1c680f920a17>`
```
struct __cppobj HdrCalibrationScreenController::_registerBindings::__l2::<lambda_0090d31c2cd362a2b64f1c680f920a17>
{
  HdrCalibrationScreenController *const __this;
};

```

### `HdrCalibrationScreenController::_registerBindings::__l2::<lambda_af0e07900b26df6861fa15ee3c18d3c2>`
```
struct __cppobj HdrCalibrationScreenController::_registerBindings::__l2::<lambda_af0e07900b26df6861fa15ee3c18d3c2>
{
  HdrCalibrationScreenController *const __this;
};

```

### `HdrCalibrationScreenController::_registerEventHandlers::__l2::<lambda_e31c3805daa310b61ad09c3ee7e5a55a>`
```
struct __cppobj HdrCalibrationScreenController::_registerEventHandlers::__l2::<lambda_e31c3805daa310b61ad09c3ee7e5a55a>
{
  HdrCalibrationScreenController *const __this;
};

```

### `HdrCalibrationScreenController::_registerEventHandlers::__l2::<lambda_d5a504e56c9f0309e2a9176fd48019d0>`
```
struct __cppobj HdrCalibrationScreenController::_registerEventHandlers::__l2::<lambda_d5a504e56c9f0309e2a9176fd48019d0>
{
  HdrCalibrationScreenController *const __this;
};

```

### `HudScreenController_vtbl`
```
struct /*VFT*/ HudScreenController_vtbl
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

### `HudScreenController::_registerTooltips::__l5::<lambda_612dea3e7018646313e2faa32f42c26e>`
```
struct __cppobj HudScreenController::_registerTooltips::__l5::<lambda_612dea3e7018646313e2faa32f42c26e>
{
};

```

### `HudScreenController::_registerTooltips::__l5::<lambda_2915616f499390bbcede6846322347ad>`
```
struct __cppobj HudScreenController::_registerTooltips::__l5::<lambda_2915616f499390bbcede6846322347ad>
{
};

```

### `HudScreenController::_registerTooltips::__l5::<lambda_7f648107bc38bb342441c4168205c24d>`
```
struct __cppobj HudScreenController::_registerTooltips::__l5::<lambda_7f648107bc38bb342441c4168205c24d>
{
};

```

### `HudScreenController::_registerTooltips::__l5::<lambda_c8ef105c332367b5272a0c12f091592c>`
```
struct __cppobj HudScreenController::_registerTooltips::__l5::<lambda_c8ef105c332367b5272a0c12f091592c>
{
};

```

### `HudScreenController::_registerTooltips::__l2::<lambda_aa7f61a620b28af03619de18f5f993b4>`
```
struct __cppobj HudScreenController::_registerTooltips::__l2::<lambda_aa7f61a620b28af03619de18f5f993b4>
{
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_fcb18562d72831645bebf861fdbf02a3>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_fcb18562d72831645bebf861fdbf02a3>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_33ace497c08bbdbd85bf4001f20e22e6>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_33ace497c08bbdbd85bf4001f20e22e6>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_9f199990a0b5ca789dab498388215a16>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_9f199990a0b5ca789dab498388215a16>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_dac0e6bb1a7406d99e29528a46bd7e58>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_dac0e6bb1a7406d99e29528a46bd7e58>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_4fd4c19a1f90e062769f9cb8be417707>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_4fd4c19a1f90e062769f9cb8be417707>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l4::<lambda_da91a43e8ee85cc522816548750ccfb3>`
```
struct __cppobj __declspec(align(8)) HudScreenController::_registerEventHandlers::__l4::<lambda_da91a43e8ee85cc522816548750ccfb3>
{
  HudScreenController *const __this;
  int i;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_a93ebc1a35c9b83cd387ef55c5566cff>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_a93ebc1a35c9b83cd387ef55c5566cff>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_4819de47fe36d9e12608ee0f8134edf8>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_4819de47fe36d9e12608ee0f8134edf8>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_df72e0e5dae7626d909fab6738c73a52>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_df72e0e5dae7626d909fab6738c73a52>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_9cf50b366d8387dd95be8c064fd6b39b>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_9cf50b366d8387dd95be8c064fd6b39b>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_registerEventHandlers::__l2::<lambda_e639e2da445daa176c2ec1175dd978eb>`
```
struct __cppobj HudScreenController::_registerEventHandlers::__l2::<lambda_e639e2da445daa176c2ec1175dd978eb>
{
  HudScreenController *const __this;
};

```

### `HudScreenController::_selectSlot::__l2::<lambda_1c7e7760850e81b8138b17aa3d0e7ea6>`
```
struct __cppobj HudScreenController::_selectSlot::__l2::<lambda_1c7e7760850e81b8138b17aa3d0e7ea6>
{
  int *slot;
};

```

### `HudScreenController::{ctor}::__l2::<lambda_524a1af1e618de3686b438edfbe6d5e4>`
```
struct __cppobj HudScreenController::{ctor}::__l2::<lambda_524a1af1e618de3686b438edfbe6d5e4>
{
  HudScreenController *const __this;
};

```

### `HoloUIScreenSetupCleanupStrategy`
```
struct __cppobj HoloUIScreenSetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  IClientInstance *mClient;
  Matrix mLastMatrixPatch;
};

```

### `HoloUIScreenSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloUIScreenSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
  Matrix *(__fastcall *_generateMatrixPatch)(HoloUIScreenSetupCleanupStrategy *this, Matrix *result);
};

```

### `HoloHUDScreenSetupCleanupStrategy`
```
struct __cppobj HoloHUDScreenSetupCleanupStrategy : HoloUIScreenSetupCleanupStrategy
{
};

```

### `HoloHUDScreenSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloHUDScreenSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
  Matrix *(__fastcall *_generateMatrixPatch)(HoloUIScreenSetupCleanupStrategy *this, Matrix *result);
};

```

### `HoloIngameUIScreenSetupCleanupStrategy`
```
struct __cppobj HoloIngameUIScreenSetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  IClientInstance *mClient;
  Matrix mLastMatrixPatch;
};

```

### `HoloIngameUIScreenSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloIngameUIScreenSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
  Matrix *(__fastcall *_generateMatrixPatch)(HoloIngameUIScreenSetupCleanupStrategy *this, Matrix *result);
};

```

### `HoloPlayspaceSetupCleanupStrategy`
```
struct __cppobj HoloPlayspaceSetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  IClientInstance *mClient;
  Matrix mLastMatrixPatch;
};

```

### `HoloPlayspaceSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloPlayspaceSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
};

```

### `HoloRealitySetupCleanupStrategy`
```
struct __cppobj HoloRealitySetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  IClientInstance *mClient;
  Matrix mLastMatrixPatch;
};

```

### `HoloRealitySetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloRealitySetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
};

```

### `HoloScreenSetupCleanupStrategy`
```
struct __cppobj HoloScreenSetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  Matrix mLastMatrixPatch;
};

```

### `HoloScreenSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloScreenSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
};

```

### `HoloViewerSetupCleanupStrategy`
```
struct __cppobj HoloViewerSetupCleanupStrategy : AbstractScreenSetupCleanupStrategy
{
  IClientInstance *mClient;
  Matrix mLastMatrixPatch;
};

```

### `HoloViewerSetupCleanupStrategy_vtbl`
```
struct /*VFT*/ HoloViewerSetupCleanupStrategy_vtbl
{
  void (__fastcall *~AbstractScreenSetupCleanupStrategy)(AbstractScreenSetupCleanupStrategy *this);
  void (__fastcall *setupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  void (__fastcall *cleanupScreen)(AbstractScreenSetupCleanupStrategy *this, ScreenContext *);
  EyeRenderingModeBit (__fastcall *getEyeRenderingMode)(AbstractScreenSetupCleanupStrategy *this);
};

```

### `Hitbox`
```
struct __cppobj Hitbox
{
  Vec3 mPivot;
  AABB mAabb;
};

```

### `HangingActor`
```
struct __cppobj HangingActor : Actor
{
  int mDir;
  int mCheckInterval;
};

```

### `HangingActor_vtbl`
```
struct /*VFT*/ HangingActor_vtbl
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
  void (__fastcall *setDir)(HangingActor *this, int);
  int (__fastcall *getWidth)(HangingActor *this);
  int (__fastcall *getHeight)(HangingActor *this);
  void (__fastcall *dropItem)(HangingActor *this);
  bool (__fastcall *placeHangingEntity)(HangingActor *this, BlockSource *, int);
  bool (__fastcall *wouldSurvive)(HangingActor *this, BlockSource *);
};

```

### `HumanoidModel`
```
struct __cppobj __declspec(align(8)) HumanoidModel : Model
{
  mce::MaterialPtr mArmor;
  mce::MaterialPtr mArmorLeather;
  mce::MaterialPtr mArmorEnchanted;
  mce::MaterialPtr mArmorLeatherEnchanted;
  ModelPart mHead;
  ModelPart mHat;
  ModelPart mBody;
  ModelPart mRightArm;
  ModelPart mLeftArm;
  ModelPart mRightLeg;
  ModelPart mLeftLeg;
  ModelPart mRightItem;
  ModelPart mLeftItem;
  ModelPart mWaist;
  ModelPart mBottom;
  ModelPart mBodyArmorOffset;
  ModelPart mHelmetArmorOffset;
  ModelPart mRightArmArmorOffset;
  ModelPart mLeftArmArmorOffset;
  ModelPart mRightBootArmorOffset;
  ModelPart mLeftBootArmorOffset;
  ModelPart mWaistArmorOffset;
  ModelPart mRightLegArmorOffset;
  ModelPart mLeftLegArmorOffset;
  bool mDamageNearbyMobs;
  bool mSneaking;
  float mSwimAmount;
  float mChargeAmount;
  bool mBowAndArrow;
  bool mCrossbow;
  bool mMainHandShield;
  bool mOffHandShield;
  bool mSpear;
  bool mCharging;
  bool mIsGliding;
  float mGlidingSpeedValue;
  float mUseItemStartupProgress;
  float mUseItemIntervalProgress;
  int mUseItemInvervalAxis;
  float mShieldBlockProgress;
  SkinAdjustments mSkinAdjustments;
  std::array<ModelPart *,13> mBindParts;
  SkinAdjustments mBaseSkinAdjustments;
  float mHoldingHand[2];
};

```

### `HumanoidModel_vtbl`
```
struct /*VFT*/ HumanoidModel_vtbl
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
  void (__fastcall *renderAniModel)(HumanoidModel *this, ScreenContext *, int, float, float);
};

```

### `HorseModel`
```
struct __cppobj HorseModel : Model
{
  mce::MaterialPtr mDefaultMaterial;
  mce::MaterialPtr mLeatherArmorMaterial;
  mce::MaterialPtr mSaddleMaterial;
  mce::MaterialPtr mHairMaterial;
  ModelPart Head;
  ModelPart UMouth;
  ModelPart LMouth;
  ModelPart Ear1;
  ModelPart Ear2;
  ModelPart MuleEarL;
  ModelPart MuleEarR;
  ModelPart Neck;
  ModelPart HeadSaddle;
  ModelPart Mane;
  ModelPart Body;
  ModelPart TailA;
  ModelPart TailB;
  ModelPart TailC;
  ModelPart Leg1A;
  ModelPart Leg1B;
  ModelPart Leg1C;
  ModelPart Leg2A;
  ModelPart Leg2B;
  ModelPart Leg2C;
  ModelPart Leg3A;
  ModelPart Leg3B;
  ModelPart Leg3C;
  ModelPart Leg4A;
  ModelPart Leg4B;
  ModelPart Leg4C;
  ModelPart Bag1;
  ModelPart Bag2;
  ModelPart Saddle;
  ModelPart SaddleB;
  ModelPart SaddleC;
  ModelPart SaddleL;
  ModelPart SaddleL2;
  ModelPart SaddleR;
  ModelPart SaddleR2;
  ModelPart SaddleMouthL;
  ModelPart SaddleMouthR;
  ModelPart SaddleMouthLine;
  ModelPart SaddleMouthLineR;
};

```

### `HorseModel_vtbl`
```
struct /*VFT*/ HorseModel_vtbl
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

### `Horse`
```
struct __cppobj __declspec(align(8)) Horse : Animal
{
  std::string layerTextureHashName;
  std::string layerTextureLayers[3];
  bool mHasReproduced;
  bool mLandedOnGround;
  float mEatAnim;
  float mEatAnimO;
  float mStandAnim;
  float mStandAnimO;
  float mMouthAnim;
  float mMouthAnimO;
  int mCountEating;
  int mMouthCounter;
  int mStandCounter;
  int mSprintCounter;
  int mGallopSoundCounter;
  int mTailCounter;
};

```

### `HorseModelV2`
```
struct __cppobj __declspec(align(8)) HorseModelV2 : Model
{
  mce::MaterialPtr mDefaultMaterial;
  mce::MaterialPtr mLeatherArmorMaterial;
  mce::MaterialPtr mSaddleMaterial;
  mce::MaterialPtr mHairMaterial;
  Vec3 mRestFrontLegPos;
  Vec3 mRestBagPos;
  ModelPart mHead;
  ModelPart mUMouth;
  ModelPart mEar1;
  ModelPart mEar2;
  ModelPart mMuleEarL;
  ModelPart mMuleEarR;
  ModelPart mNeck;
  ModelPart mHeadSaddle;
  ModelPart mMane;
  ModelPart mBody;
  ModelPart mTailA;
  ModelPart mLeg1A;
  ModelPart mLeg2A;
  ModelPart mLeg3A;
  ModelPart mLeg4A;
  ModelPart mBag1;
  ModelPart mBag2;
  ModelPart mSaddle;
  ModelPart mSaddleB;
  ModelPart mSaddleC;
  ModelPart mSaddleL;
  ModelPart mSaddleL2;
  ModelPart mSaddleR;
  ModelPart mSaddleR2;
  ModelPart mSaddleMouthL;
  ModelPart mSaddleMouthR;
  ModelPart mSaddleMouthLine;
  ModelPart mSaddleMouthLineR;
  float mBabyLegInitialUpscale;
};

```

### `HorseModelV2_vtbl`
```
struct /*VFT*/ HorseModelV2_vtbl
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

### `HeartParticle`
```
struct __cppobj __declspec(align(8)) HeartParticle : Particle
{
  float oSize;
};

```

### `HeartParticle_vtbl`
```
struct /*VFT*/ HeartParticle_vtbl
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

### `HugeExplosionParticle`
```
struct __cppobj __declspec(align(8)) HugeExplosionParticle : Particle
{
  int baseTex;
};

```

### `HugeExplosionParticle_vtbl`
```
struct /*VFT*/ HugeExplosionParticle_vtbl
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

### `HugeExplosionSeedParticle`
```
struct __cppobj HugeExplosionSeedParticle : Particle
{
};

```

### `HugeExplosionSeedParticle_vtbl`
```
struct /*VFT*/ HugeExplosionSeedParticle_vtbl
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

### `HappyVillagerParticle`
```
struct __cppobj HappyVillagerParticle : SuspendedTownParticle
{
};

```

### `HappyVillagerParticle_vtbl`
```
struct /*VFT*/ HappyVillagerParticle_vtbl
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

### `HuskModel`
```
struct __cppobj HuskModel : ZombieModel
{
  mce::MaterialPtr mHuskMaterial;
  mce::MaterialPtr mClothesMaterial;
  ModelPart mHat;
  ModelPart mLeftSleeve;
  ModelPart mRightSleeve;
};

```

### `HuskModel_vtbl`
```
struct /*VFT*/ HuskModel_vtbl
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
  void (__fastcall *renderAniModel)(HumanoidModel *this, ScreenContext *, int, float, float);
};

```

### `HumanoidMonster`
```
struct __cppobj __declspec(align(8)) HumanoidMonster : Monster
{
  AttackState mState;
};

```

### `HorseArmorItem`
```
struct __cppobj __declspec(align(8)) HorseArmorItem : Item
{
  const int mDefense;
  const int mModelIndex;
  _BYTE mTier[4];
};

```

### `HorseRenderer`
```
struct __cppobj HorseRenderer : MobRenderer
{
  mce::TexturePtr mHorseTypeTextures[5];
  mce::TexturePtr mHorseVariantTextures[7];
  mce::TexturePtr mHorseMarkingTextures[5];
  mce::TexturePtr mHorseArmorTextures[5];
};

```

### `HorseRenderer_vtbl`
```
struct /*VFT*/ HorseRenderer_vtbl
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

### `HorseRendererV2`
```
struct __cppobj HorseRendererV2 : MobRenderer
{
  mce::TexturePtr mHorseTypeTextures[5];
  mce::TexturePtr mHorseVariantTextures[7];
  mce::TexturePtr mHorseMarkingTextures[5];
  mce::TexturePtr mHorseArmorTextures[5];
};

```

### `HorseRendererV2_vtbl`
```
struct /*VFT*/ HorseRendererV2_vtbl
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

### `HumanoidMobRenderer`
```
struct __cppobj __declspec(align(8)) HumanoidMobRenderer : MobRenderer
{
  std::unique_ptr<HumanoidModel> mBabyModel;
  std::unique_ptr<HumanoidModel> mArmorParts1;
  std::unique_ptr<HumanoidModel> mArmorParts2;
  std::unique_ptr<SpinAttackModel> mSpinAttackModel;
  std::vector<mce::TexturePtr> mArmorTextures;
  mce::TexturePtr mSpinAttackTex;
  std::unique_ptr<HumanoidModel> mOriginalArmorModel;
  bool lastCustomArmorHead;
  bool lastCustomArmorBody;
  bool lastCustomArmorLeg;
  bool lastCustomArmorFeet;
};

```

### `HumanoidMobRenderer_vtbl`
```
struct /*VFT*/ HumanoidMobRenderer_vtbl
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
  void (__fastcall *prepareCarriedOffhandItem)(HumanoidMobRenderer *this, Model *, Mob *, const ItemStack *);
  void (__fastcall *_bindModelRender)(HumanoidMobRenderer *this, BaseActorRenderContext *, HumanoidModel *, Mob *, float, float);
};

```

### `HeavyBlock`
```
struct __cppobj HeavyBlock : BlockLegacy
{
};

```

### `HeavyBlock_vtbl`
```
struct /*VFT*/ HeavyBlock_vtbl
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

### `HurtOwnerSubcomponent`
```
struct __cppobj __declspec(align(4)) HurtOwnerSubcomponent : OnHitSubcomponent
{
  float mOwnerDamage;
  bool mKnockback;
  bool mIgnite;
};

```

### `HurtOwnerSubcomponent_vtbl`
```
struct /*VFT*/ HurtOwnerSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `HydrateItemRequest::CacheMetadata`
```
struct __cppobj HydrateItemRequest::CacheMetadata
{
  std::string mLastModifiedDate;
  std::string mCacheWriteDate;
  std::string mEntityTag;
};

```

### `HydrateItemRequest`
```
struct __cppobj HydrateItemRequest : CachedRequest
{
  std::shared_ptr<CatalogBackend> mBackend;
  const std::string mAcceptLanguage;
  HydrateParams mParams;
  std::unique_ptr<HydrateResponseCallbackHandler> mHydrateResponse;
  HydrateItemRequest::CacheMetadata mCacheMetadata;
};

```

### `HydrateItemRequest_vtbl`
```
struct /*VFT*/ HydrateItemRequest_vtbl
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

### `HIDController`
```
struct __cppobj __declspec(align(8)) HIDController : Bedrock::Input::KeyboardEventProcessor
{
  std::unique_ptr<Bedrock::SignalReceiver> mSignalRcvr;
  TextEditContext mEditContext;
  bool mTextboxIsFocused;
  bool mTextboxIsSelected;
  bool mIsMultiline;
};

```

### `HIDController_vtbl`
```
struct /*VFT*/ HIDController_vtbl
{
  void (__fastcall *~KeyboardEventProcessor)(Bedrock::Input::KeyboardEventProcessor *this);
  void (__fastcall *onKeyDown)(Bedrock::Input::KeyboardEventProcessor *this, int);
  void (__fastcall *onKeyUp)(Bedrock::Input::KeyboardEventProcessor *this, int);
  void (__fastcall *setIMEEnabled)(HIDController *this, bool);
};

```

### `HIDControllerWin32`
```
struct __cppobj HIDControllerWin32 : HIDController
{
  HWND__ *mHWnd;
};

```

### `HIDControllerWin32_vtbl`
```
struct /*VFT*/ HIDControllerWin32_vtbl
{
  void (__fastcall *~KeyboardEventProcessor)(Bedrock::Input::KeyboardEventProcessor *this);
  void (__fastcall *onKeyDown)(Bedrock::Input::KeyboardEventProcessor *this, int);
  void (__fastcall *onKeyUp)(Bedrock::Input::KeyboardEventProcessor *this, int);
  void (__fastcall *setIMEEnabled)(HIDController *this, bool);
};

```

### `HitResultContainer::LocalPlayerContainer`
```
struct __cppobj HitResultContainer::LocalPlayerContainer : IHitResultContainer
{
  std::vector<std::pair<HitResult,HitResult>> mHits;
};

```

### `HitResultContainer::LocalPlayerContainer_vtbl`
```
struct /*VFT*/ HitResultContainer::LocalPlayerContainer_vtbl
{
  void (__fastcall *~IHitResultContainer)(IHitResultContainer *this);
  void (__fastcall *addHitResult)(IHitResultContainer *this, HitResult, HitResult);
  void (__fastcall *clear)(IHitResultContainer *this);
  gsl::span<std::pair<HitResult,HitResult> const ,-1> *(__fastcall *getHits)(IHitResultContainer *this, gsl::span<std::pair<HitResult,HitResult> const ,-1> *result);
};

```

### `HomeSystem`
```
struct __cppobj HomeSystem : ITickingSystem
{
};

```

### `HomeSystem_vtbl`
```
struct /*VFT*/ HomeSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `HTTPRequestCancelSourceAbort`
```
struct __cppobj HTTPRequestCancelSourceAbort : HTTPRequestCancelSource
{
  std::mutex mRequestsMutex;
  std::vector<gsl::not_null<HTTPRequest *>> mRequests;
};

```

### `HTTPRequestCancelSourceAbort_vtbl`
```
struct /*VFT*/ HTTPRequestCancelSourceAbort_vtbl
{
  void (__fastcall *~HTTPRequestCancelSource)(HTTPRequestCancelSource *this);
  void (__fastcall *cancel)(HTTPRequestCancelSource *this);
};

```

### `HealableComponent`
```
struct __cppobj HealableComponent : IEntityComponent
{
};

```

### `HideComponent`
```
struct __cppobj HideComponent
{
  bool mIsInRaid;
  bool mReactToBell;
};

```

### `HitboxDefinition`
```
struct __cppobj HitboxDefinition
{
  std::vector<Hitbox> mHitboxes;
};

```

### `HitboxJson`
```
struct __cppobj HitboxJson
{
  Vec3 mPivot;
  float mWidth;
  float mHeight;
};

```

### `HomeDefinition`
```
struct __cppobj HomeDefinition
{
  int mRestrictionRadius;
  std::vector<std::string> mHomeBlockNames;
};

```

### `HopperDefinition`
```
struct __cppobj HopperDefinition
{
};

```

### `Hopper`
```
struct __cppobj Hopper
{
  int mCooldownTime;
  bool mTransferedFromChestMinecart;
  bool mIsEntity;
  bool mCanHopperIn;
  bool mCanHopperOut;
  bool mCanTriggerPullInEvent;
  bool mCanTriggerPullOutEvent;
  int mMoveItemSpeed;
};

```

### `HopperComponent`
```
struct __cppobj HopperComponent : Hopper
{
  BlockPos mLastPosition;
};

```

### `HurtOnConditionDefinition`
```
struct __cppobj HurtOnConditionDefinition
{
  std::vector<DamageCondition> mDamageConditions;
};

```

### `HomeDefinition::buildSchema::__l2::<lambda_2ca5030ea1b6b39672c73b4b66f2fe15>`
```
struct __cppobj HomeDefinition::buildSchema::__l2::<lambda_2ca5030ea1b6b39672c73b4b66f2fe15>
{
};

```

### `HealableComponent::getInteraction::__l20::<lambda_2e4b6d19d8e2cc25bfd90a4348859777>`
```
struct __cppobj HealableComponent::getInteraction::__l20::<lambda_2e4b6d19d8e2cc25bfd90a4348859777>
{
  Player *player;
  Actor *owner;
  std::_Vector_const_iterator<std::_Vector_val<std::_Simple_types<FeedItem> > > healableItemIter;
  HealableComponent *const __this;
};

```

### `HopMoveControl`
```
struct __cppobj __declspec(align(8)) HopMoveControl : MoveControl
{
  int mJumpDelayTicks;
};

```

### `HopMoveControl_vtbl`
```
struct /*VFT*/ HopMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `HoverMoveControl`
```
struct __cppobj HoverMoveControl : MoveControl
{
};

```

### `HoverMoveControl_vtbl`
```
struct /*VFT*/ HoverMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `HoverPathNavigation`
```
struct __cppobj __declspec(align(8)) HoverPathNavigation : PathNavigation
{
  bool mCanPathFromAir;
};

```

### `HoverPathNavigation_vtbl`
```
struct /*VFT*/ HoverPathNavigation_vtbl
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

### `HurtOnConditionComponent`
```
struct __cppobj HurtOnConditionComponent : IEntityComponent
{
};

```

### `HurtOnConditionSystem`
```
struct __cppobj HurtOnConditionSystem : ITickingSystem
{
};

```

### `HurtOnConditionSystem_vtbl`
```
struct /*VFT*/ HurtOnConditionSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `HurtByTargetGoal`
```
struct __cppobj HurtByTargetGoal : TargetGoal
{
};

```

### `HurtByTargetGoal_vtbl`
```
struct /*VFT*/ HurtByTargetGoal_vtbl
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
  void (__fastcall *alertOther)(HurtByTargetGoal *this, Mob *, Mob *);
};

```

### `HaveItemDefinition`
```
struct __cppobj HaveItemDefinition : BehaviorDefinition
{
  std::string mItemName;
  int mItemCount;
  std::string mItemNameId;
  std::string mItemCountId;
};

```

### `HaveItemDefinition_vtbl`
```
struct /*VFT*/ HaveItemDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `HaveItemNode`
```
struct __cppobj __declspec(align(8)) HaveItemNode : BehaviorNode
{
  std::string mItemName;
  int mItemCount;
};

```

### `HaveItemNode_vtbl`
```
struct /*VFT*/ HaveItemNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `HopperBlockActor`
```
struct __cppobj HopperBlockActor : BlockActor, Container, Hopper
{
  ItemStack mItems[5];
  Tick mLastTick;
};

```

### `HopperBlockActor_vtbl`
```
struct /*VFT*/ HopperBlockActor_vtbl
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

### `Hopper::_pushOutItems::__l11::<lambda_8021f23895e628ed9b3c2f2406f50b3b>`
```
struct __cppobj Hopper::_pushOutItems::__l11::<lambda_8021f23895e628ed9b3c2f2406f50b3b>
{
  const Vec3 *position;
  BlockActor **attachedBlockEntity;
  bool *canHopperOut;
  BlockSource *region;
};

```

### `Hopper::_tryPullInItemsFromAboveContainer::__l14::<lambda_cfa17afae7045b99dd77cd1780d5e42b>`
```
struct __cppobj Hopper::_tryPullInItemsFromAboveContainer::__l14::<lambda_cfa17afae7045b99dd77cd1780d5e42b>
{
  const Vec3 *pos;
  BlockActor **aboveBlockEntity;
  bool *canHopperIn;
  BlockSource *region;
};

```

### `HealthAttributeDelegate`
```
struct __cppobj HealthAttributeDelegate : AttributeInstanceDelegate
{
  int mTickCounter;
  Mob *mMob;
};

```

### `HealthAttributeDelegate_vtbl`
```
struct /*VFT*/ HealthAttributeDelegate_vtbl
{
  void (__fastcall *~AttributeInstanceDelegate)(AttributeInstanceDelegate *this);
  void (__fastcall *tick)(AttributeInstanceDelegate *this);
  void (__fastcall *notify)(AttributeInstanceDelegate *this, __int64);
  bool (__fastcall *change)(AttributeInstanceDelegate *this, float, float, AttributeBuffInfo);
  float (__fastcall *getBuffValue)(AttributeInstanceDelegate *this, const AttributeBuff *);
};

```

### `HungerAttributeDelegate`
```
struct __cppobj HungerAttributeDelegate : AttributeInstanceDelegate
{
  int mActionTickTimer;
  int mTickCounter;
  float mLastFoodLevel;
  Player *mPlayer;
};

```

### `HungerAttributeDelegate_vtbl`
```
struct /*VFT*/ HungerAttributeDelegate_vtbl
{
  void (__fastcall *~AttributeInstanceDelegate)(AttributeInstanceDelegate *this);
  void (__fastcall *tick)(AttributeInstanceDelegate *this);
  void (__fastcall *notify)(AttributeInstanceDelegate *this, __int64);
  bool (__fastcall *change)(AttributeInstanceDelegate *this, float, float, AttributeBuffInfo);
  float (__fastcall *getBuffValue)(AttributeInstanceDelegate *this, const AttributeBuff *);
};

```

### `HorseEquipValidationState`
```
struct __cppobj HorseEquipValidationState
{
  std::vector<ItemDescriptor> armorAllowedItems;
  std::vector<ItemDescriptor> saddleAllowedItems;
};

```

### `HudContainerModel`
```
struct __cppobj HudContainerModel : ContainerModel
{
  Player *mPlayer;
};

```

### `HudContainerModel_vtbl`
```
struct /*VFT*/ HudContainerModel_vtbl
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

### `HangingActorItem`
```
struct __cppobj __declspec(align(8)) HangingActorItem : Item
{
  ActorType mEntityType;
};

```

### `HatchetItem`
```
struct __cppobj HatchetItem : DiggerItem
{
};

```

### `HoeItem`
```
struct __cppobj HoeItem : DiggerItem
{
};

```

### `HopperBlock`
```
struct __cppobj HopperBlock : ActorBlock
{
};

```

### `HopperBlock_vtbl`
```
struct /*VFT*/ HopperBlock_vtbl
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

### `HayBlockBlock`
```
struct __cppobj HayBlockBlock : RotatedPillarBlock
{
};

```

### `HayBlockBlock_vtbl`
```
struct /*VFT*/ HayBlockBlock_vtbl
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

### `HoneyBlock`
```
struct __cppobj HoneyBlock : BlockLegacy
{
};

```

### `HoneyBlock_vtbl`
```
struct /*VFT*/ HoneyBlock_vtbl
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

### `HoneycombBlock`
```
struct __cppobj HoneycombBlock : BlockLegacy
{
};

```

### `HoneycombBlock_vtbl`
```
struct /*VFT*/ HoneycombBlock_vtbl
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

### `HugeMushroomBlock`
```
struct __cppobj __declspec(align(8)) HugeMushroomBlock : BlockLegacy
{
  _BYTE mType[4];
};

```

### `HugeMushroomBlock_vtbl`
```
struct /*VFT*/ HugeMushroomBlock_vtbl
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

### `HugeMushroomFeature_vtbl`
```
struct /*VFT*/ HugeMushroomFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `HugeFungusFeature_vtbl`
```
struct /*VFT*/ HugeFungusFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `HTTPRequestInternalWinInet`
```
struct __cppobj __declspec(align(8)) HTTPRequestInternalWinInet : HTTPRequestInternal
{
  HTTPRequest *mParentRequest;
  std::wstring_convert<std::codecvt_utf8_utf16<wchar_t,1114111,0>,wchar_t,std::allocator<wchar_t>,std::allocator<char> > ws_converter;
  Microsoft::WRL::ComPtr<IXMLHTTPRequest2> spXHR;
  Microsoft::WRL::ComPtr<CXMLHttpRequest2Callback> spXhrCallback;
  Microsoft::WRL::ComPtr<CXMLHttpRequestPostStream> spXhrPostStream;
  HTTPRequestCancelSourceAbort *mCancelSource;
  bool mAborted;
};

```

### `HTTPRequestInternalWinInet_vtbl`
```
struct /*VFT*/ HTTPRequestInternalWinInet_vtbl
{
  void (__fastcall *~HTTPRequestInternal)(HTTPRequestInternal *this);
};

```

### `HVIDEOINPUTDEVICENV__`
```
struct HVIDEOINPUTDEVICENV__
{
  int unused;
};

```

### `HGPUNV__`
```
struct HGPUNV__
{
  int unused;
};

```

### `HPBUFFEREXT__`
```
struct HPBUFFEREXT__
{
  int unused;
};

```

### `HPBUFFERARB__`
```
struct HPBUFFERARB__
{
  int unused;
};

```

### `HVIDEOOUTPUTDEVICENV__`
```
struct HVIDEOOUTPUTDEVICENV__
{
  int unused;
};

```

### `HPVIDEODEV__`
```
struct HPVIDEODEV__
{
  int unused;
};

```

### `HorseScreenController`
```
struct __cppobj __declspec(align(8)) HorseScreenController : BlockContainerScreenController
{
  bool mChestTabOpen;
};

```

### `HorseScreenController_vtbl`
```
struct /*VFT*/ HorseScreenController_vtbl
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

### `HorseContainerManagerModel`
```
struct __cppobj HorseContainerManagerModel : LevelContainerManagerModel
{
  std::weak_ptr<ContainerModel> mEquipContainerModel;
};

```

### `HorseContainerManagerModel_vtbl`
```
struct /*VFT*/ HorseContainerManagerModel_vtbl
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

### `HorseContainerManagerController`
```
struct __cppobj __declspec(align(8)) HorseContainerManagerController : ContainerManagerController
{
  std::weak_ptr<HorseContainerManagerModel> mHorseContainerManagerModel;
  bool mIsEquipTabOpen;
};

```

### `HorseContainerManagerController_vtbl`
```
struct /*VFT*/ HorseContainerManagerController_vtbl
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

### `HorseScreenController::{ctor}::__l2::<lambda_af5fa2530f826d5d08def04c7eb5cee0>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_af5fa2530f826d5d08def04c7eb5cee0>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_80c6e5409393cca0fc5a377974added3>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_80c6e5409393cca0fc5a377974added3>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_025986612949938973253e99816d0a0c>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_025986612949938973253e99816d0a0c>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_d80db6b9e9a3d13343bb578caa017e7a>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_d80db6b9e9a3d13343bb578caa017e7a>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_32008c64cf8e1a2b5f1a9adf16734b12>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_32008c64cf8e1a2b5f1a9adf16734b12>
{
  const ActorUniqueID uniqueId;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_f366e4756a3ad1e14c2b165ae3e1cce7>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_f366e4756a3ad1e14c2b165ae3e1cce7>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_70e96ef0b510e7e22cd1bec90fd98052>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_70e96ef0b510e7e22cd1bec90fd98052>
{
  bool carpet;
  bool saddle;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_aae33fb3c021b427366010e85d724955>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_aae33fb3c021b427366010e85d724955>
{
  bool carpet;
  bool saddle;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_c826454155f9e06315851f1096cfd6e3>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_c826454155f9e06315851f1096cfd6e3>
{
  bool carpet;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_29032eead47001b61f3051162f12b0a4>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_29032eead47001b61f3051162f12b0a4>
{
  bool armor;
  bool carpet;
  bool saddle;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_fb3a37bc67e2165084c025dfaaa0634c>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_fb3a37bc67e2165084c025dfaaa0634c>
{
  bool armor;
  bool carpet;
  bool saddle;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_fb9ac15c96cbbb5498e516bbd1f5ec92>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_fb9ac15c96cbbb5498e516bbd1f5ec92>
{
  bool armor;
  bool carpet;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_8428b03acd8d82eba9ca1912315ce62f>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_8428b03acd8d82eba9ca1912315ce62f>
{
  bool saddle;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_af0dac77beec41d4c248848aad34ecc4>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_af0dac77beec41d4c248848aad34ecc4>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_b4fd066aa479ddd11366c1ab3ac22cad>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_b4fd066aa479ddd11366c1ab3ac22cad>
{
  HorseScreenController *const __this;
};

```

### `HorseScreenController::{ctor}::__l2::<lambda_64713f98632f01bc3921ea3e304729ed>`
```
struct __cppobj HorseScreenController::{ctor}::__l2::<lambda_64713f98632f01bc3921ea3e304729ed>
{
  HorseScreenController *const __this;
};

```

### `HopperContainerManagerModel`
```
struct __cppobj HopperContainerManagerModel : LevelContainerManagerModel
{
};

```

### `HopperContainerManagerModel_vtbl`
```
struct /*VFT*/ HopperContainerManagerModel_vtbl
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

### `HopperSystem`
```
struct __cppobj HopperSystem : ITickingSystem
{
};

```

### `HopperSystem_vtbl`
```
struct /*VFT*/ HopperSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `HarvestFarmBlockDefinition`
```
struct __cppobj HarvestFarmBlockDefinition : BaseGoalDefinition
{
  float mMaximumSecondsUntilSearch;
  float mSearchCooldownMaximumSeconds;
  float mTaskCooldownSeconds;
  int mSearchCount;
  int mSearchHeight;
  int mSearchRange;
  float mGoalRadius;
  float mSpeedModifier;
};

```

### `HarvestFarmBlockDefinition_vtbl`
```
struct /*VFT*/ HarvestFarmBlockDefinition_vtbl
{
  void (__fastcall *~BaseGoalDefinition)(BaseGoalDefinition *this);
  bool (__fastcall *validateMobType)(BaseGoalDefinition *this, Mob *);
  bool (__fastcall *validate)(BaseGoalDefinition *this, Mob *);
};

```

### `HarvestFarmBlockGoal`
```
struct __cppobj __declspec(align(8)) HarvestFarmBlockGoal : BaseMoveToBlockGoal
{
  int mMaximumTicksUntilSearch;
  int mSearchCooldownMaximumTicks;
  int mTaskCooldownTicks;
  int mInventorySeedsIndex;
  _BYTE mCurrentTask[4];
};

```

### `HarvestFarmBlockGoal_vtbl`
```
struct /*VFT*/ HarvestFarmBlockGoal_vtbl
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
  bool (__fastcall *hasReachedTarget)(BaseMoveToGoal *this);
  bool (__fastcall *isValidTarget)(BaseMoveToGoal *this, BlockSource *, const BlockPos *);
  int (__fastcall *_nextStartTick)(BaseMoveToGoal *this);
  bool (__fastcall *_canReach)(BaseMoveToGoal *this, const BlockPos *);
  void (__fastcall *_moveToBlock)(BaseMoveToGoal *this);
  Vec3 *(__fastcall *_getTargetPosition)(BaseMoveToGoal *this, Vec3 *result);
  unsigned __int64 (__fastcall *_getRepathTime)(BaseMoveToGoal *this);
  bool (__fastcall *findTargetBlock)(BaseMoveToBlockGoal *this);
};

```

### `HideGoal`
```
struct __cppobj __declspec(align(8)) HideGoal : MoveToPOIGoal
{
  __int16 mHideAttempts;
};

```

### `HideGoal_vtbl`
```
struct /*VFT*/ HideGoal_vtbl
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
  bool (__fastcall *hasReachedTarget)(BaseMoveToGoal *this);
  bool (__fastcall *isValidTarget)(BaseMoveToGoal *this, BlockSource *, const BlockPos *);
  int (__fastcall *_nextStartTick)(BaseMoveToGoal *this);
  bool (__fastcall *_canReach)(BaseMoveToGoal *this, const BlockPos *);
  void (__fastcall *_moveToBlock)(BaseMoveToGoal *this);
  Vec3 *(__fastcall *_getTargetPosition)(BaseMoveToGoal *this, Vec3 *result);
  unsigned __int64 (__fastcall *_getRepathTime)(BaseMoveToGoal *this);
  bool (__fastcall *getPOI)(MoveToPOIGoal *this, POIType);
  std::weak_ptr<POIInstance> *(__fastcall *_getOwnedPOI)(MoveToPOIGoal *this, std::weak_ptr<POIInstance> *result, POIType);
};

```

### `HoldGroundGoal`
```
struct __cppobj HoldGroundGoal : Goal
{
  Mob *mMob;
  TempEPtr<Actor> mLookAt;
  float mHostileRadiusSqr;
  bool mBroadcast;
  float mBroadcastRange;
  const DefinitionTrigger mWithinRangeEvent;
};

```

### `HoldGroundGoal_vtbl`
```
struct /*VFT*/ HoldGroundGoal_vtbl
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

### `HoverGoal`
```
struct __cppobj HoverGoal : Goal
{
  Mob *mMob;
  float mSpeedMultiplier;
  Vec3 mStartPos;
};

```

### `HoverGoal_vtbl`
```
struct /*VFT*/ HoverGoal_vtbl
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

### `HorseContainerManagerModel::_postInit::__l5::<lambda_1ff89581375038258850ba975b22babe>`
```
struct __cppobj HorseContainerManagerModel::_postInit::__l5::<lambda_1ff89581375038258850ba975b22babe>
{
  HorseContainerManagerModel *const __this;
};

```

### `HorseContainerManagerModel::_postInit::__l5::<lambda_89ec054521d8a3163489de1362af6a58>`
```
struct __cppobj HorseContainerManagerModel::_postInit::__l5::<lambda_89ec054521d8a3163489de1362af6a58>
{
  HorseContainerManagerModel *const __this;
};

```

### `HellFireFeature_vtbl`
```
struct /*VFT*/ HellFireFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `HellSpringFeature_vtbl`
```
struct /*VFT*/ HellSpringFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `huff_entropy_encoder`
```
struct huff_entropy_encoder
{
  jpeg_entropy_encoder pub;
  _BYTE saved[20];
  __declspec(align(8)) unsigned int restarts_to_go;
  int next_restart_num;
  c_derived_tbl *dc_derived_tbls[4];
  c_derived_tbl *ac_derived_tbls[4];
  int *dc_count_ptrs[4];
  int *ac_count_ptrs[4];
  unsigned __int8 gather_statistics;
  unsigned __int8 *next_output_byte;
  unsigned __int64 free_in_buffer;
  jpeg_compress_struct *cinfo;
  int ac_tbl_no;
  unsigned int EOBRUN;
  unsigned int BE;
  char *bit_buffer;
};

```

### `huff_entropy_decoder`
```
struct huff_entropy_decoder
{
  jpeg_entropy_decoder pub;
  bitread_perm_state bitstate;
  _BYTE saved[20];
  unsigned __int8 insufficient_data;
  unsigned int restarts_to_go;
  d_derived_tbl *derived_tbls[4];
  d_derived_tbl *ac_derived_tbl;
  d_derived_tbl *dc_derived_tbls[4];
  d_derived_tbl *ac_derived_tbls[4];
  d_derived_tbl *dc_cur_tbls[10];
  d_derived_tbl *ac_cur_tbls[10];
  int coef_limit[10];
};

```

### `HuffmanEncodingTreeNode`
```
struct HuffmanEncodingTreeNode
{
  unsigned __int8 value;
  unsigned int weight;
  HuffmanEncodingTreeNode *left;
  HuffmanEncodingTreeNode *right;
  HuffmanEncodingTreeNode *parent;
};

```

### `HudHorseJumpRenderer::render::__l2::<lambda_f26f6b421c5d8a48941cbbe5d0c0ad83>`
```
struct __cppobj HudHorseJumpRenderer::render::__l2::<lambda_f26f6b421c5d8a48941cbbe5d0c0ad83>
{
  float *uSize;
  float *vSize;
  int *u;
  int *v;
};

```

### `HudPlayerRenderer::render::__l11::<lambda_3c8a26f25fde2aa3aadba65938c29373>::()::__l2::Literal`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_3c8a26f25fde2aa3aadba65938c29373>::()::__l2::Literal
{
};

```

### `HudPlayerRenderer::render::__l11::<lambda_ee7b0def6be5201d2193da1373b2d92c>::()::__l2::Literal`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_ee7b0def6be5201d2193da1373b2d92c>::()::__l2::Literal
{
};

```

### `HudPlayerRenderer::render::__l11::<lambda_7c138ce959f7ff186fa0298c49f4fbf1>::()::__l2::Literal`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_7c138ce959f7ff186fa0298c49f4fbf1>::()::__l2::Literal
{
};

```

### `HudMobEffectsRenderer::render::__l24::<lambda_8b8e8c379e3d3ef9f9c7f588b3d37ae9>`
```
struct __cppobj HudMobEffectsRenderer::render::__l24::<lambda_8b8e8c379e3d3ef9f9c7f588b3d37ae9>
{
  int *ux;
  int *vy;
  float *uvWidth;
  float *uvHeight;
  float *us;
  float *vs;
};

```

### `HudPlayerRenderer::render::__l11::<lambda_3c8a26f25fde2aa3aadba65938c29373>`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_3c8a26f25fde2aa3aadba65938c29373>
{
};

```

### `HudPlayerRenderer::render::__l11::<lambda_7c138ce959f7ff186fa0298c49f4fbf1>`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_7c138ce959f7ff186fa0298c49f4fbf1>
{
};

```

### `HudPlayerRenderer::render::__l11::<lambda_ee7b0def6be5201d2193da1373b2d92c>`
```
struct __cppobj HudPlayerRenderer::render::__l11::<lambda_ee7b0def6be5201d2193da1373b2d92c>
{
};

```

### `hbui::FacetRegistry::registerFacet::__l2::<lambda_bd9bb8f2cadf3b0f10a80c7e81deb91c>`
```
struct __cppobj hbui::FacetRegistry::registerFacet::__l2::<lambda_bd9bb8f2cadf3b0f10a80c7e81deb91c>
{
  const std::string *name;
};

```

### `hbui::FacetRegistry::activateFacet::__l2::<lambda_9a9590cfcd6a92ccbb29c3aa72aee23c>`
```
struct __cppobj hbui::FacetRegistry::activateFacet::__l2::<lambda_9a9590cfcd6a92ccbb29c3aa72aee23c>
{
  const std::string *name;
};

```

### `hbui::FacetRegistry::deactivateFacet::__l2::<lambda_f70eba82a047d5efe865983ea2888497>`
```
struct __cppobj hbui::FacetRegistry::deactivateFacet::__l2::<lambda_f70eba82a047d5efe865983ea2888497>
{
  const std::string *name;
};

```

### `HummingbirdUI::unregisterRouteConfigurationChangeCallback::__l2::<lambda_3e88f95f6d5af2b53e78952b635e1bb8>`
```
struct __cppobj HummingbirdUI::unregisterRouteConfigurationChangeCallback::__l2::<lambda_3e88f95f6d5af2b53e78952b635e1bb8>
{
  void *token;
};

```

### `hbui::RouteMatcher::_match::__l2::<lambda_fa4836dab5b272682811c18a65ff5f30>`
```
struct __cppobj hbui::RouteMatcher::_match::__l2::<lambda_fa4836dab5b272682811c18a65ff5f30>
{
  const std::string route;
};

```

### `hbui::RouterConfiguration::_addRoute::__l2::<lambda_9d53e344a0271a1458e6afaa48e7f0d5>`
```
struct __cppobj hbui::RouterConfiguration::_addRoute::__l2::<lambda_9d53e344a0271a1458e6afaa48e7f0d5>
{
  const std::string *route;
};

```

### `HudScreenController::_updateTitleText::__l14::<lambda_348b4ca9d695a98721f80bb664a775dd>`
```
struct __cppobj HudScreenController::_updateTitleText::__l14::<lambda_348b4ca9d695a98721f80bb664a775dd>
{
};

```

### `HitResultSystem::tick::__l2::<lambda_ad1d02461820c9e892f4d2da456e3aa6>`
```
struct __cppobj HitResultSystem::tick::__l2::<lambda_ad1d02461820c9e892f4d2da456e3aa6>
{
};

```

### `HealableComponent::getInteraction::__l2::<lambda_90c5c6f55d8f131a1d67e74a13742cae>`
```
struct __cppobj HealableComponent::getInteraction::__l2::<lambda_90c5c6f55d8f131a1d67e74a13742cae>
{
  const ItemStack *item;
};

```

### `HomeComponent::tick::__l2::<lambda_ea3f16251f6d40785ec8bf72849f1501>`
```
struct __cppobj HomeComponent::tick::__l2::<lambda_ea3f16251f6d40785ec8bf72849f1501>
{
  const BlockLegacy *blockAtHomePos;
};

```

### `HeavyBlock::animateTick::__l11::<lambda_34dbdd8a4780ed8cc471ac95c73990c9>::()::__l2::Literal`
```
struct __cppobj HeavyBlock::animateTick::__l11::<lambda_34dbdd8a4780ed8cc471ac95c73990c9>::()::__l2::Literal
{
};

```

### `HeavyBlock::animateTick::__l11::<lambda_34dbdd8a4780ed8cc471ac95c73990c9>`
```
struct __cppobj HeavyBlock::animateTick::__l11::<lambda_34dbdd8a4780ed8cc471ac95c73990c9>
{
};

```

### `Horse_vtbl`
```
struct /*VFT*/ Horse_vtbl
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
  void (__fastcall *setType)(Horse *this, int);
  int (__fastcall *getType)(Horse *this);
  void (__fastcall *setHorseEating)(Horse *this, bool);
  float (__fastcall *getEatAnim)(Horse *this, float);
  float (__fastcall *getStandAnim)(Horse *this, float);
  float (__fastcall *getMouthAnim)(Horse *this, float);
  bool (__fastcall *canWearArmor)(Horse *this);
  bool (__fastcall *getHasReproduced)(Horse *this);
  void (__fastcall *setBred)(Horse *this, bool);
  void (__fastcall *setReproduced)(Horse *this, bool);
  bool (__fastcall *isAmuletHorse)(Horse *this);
  bool (__fastcall *isUndead)(Horse *this);
  bool (__fastcall *isSterile)(Horse *this);
  bool (__fastcall *isAdult)(Horse *this);
  bool (__fastcall *isHorseEating)(Horse *this);
  bool (__fastcall *isBred)(Horse *this);
  void (__fastcall *makeMad)(Horse *this);
  int (__fastcall *nameYOffset)(Horse *this);
  bool (__fastcall *tameToPlayer)(Horse *this, Player *, bool);
  std::string *(__fastcall *getMadSound)(Horse *this, std::string *result);
};

```

### `HumanoidMonster_vtbl`
```
struct /*VFT*/ HumanoidMonster_vtbl
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

