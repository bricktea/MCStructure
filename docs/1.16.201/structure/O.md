# O
### `OptionConstants::<lambda_494f639503c40febe0dbb14372a57cbf>`
Offset | Type | Name
-|-|-|-


### `OptionConstants::<lambda_631366cfcd28947db7d3be15dfb1611c>`
Offset | Type | Name
-|-|-|-


### `OptionConstants::<lambda_f6873ee4037cf69a5750303b33811eac>`
Offset | Type | Name
-|-|-|-


### `OptionConstants::<lambda_ac8f171e94addf05b263c93e72bdf2a9>`
Offset | Type | Name
-|-|-|-


### `Option`
Offset | Type | Name
-|-|-|-
0 | (8) `Option_vtbl *` | __vftable
8 | (120) `Bedrock::PubSub::Publisher<void __cdecl(Option const &),Bedrock::PubSub::ThreadModel::MultiThreaded,void>` | mValueChangedPublisher
128 | (120) `Bedrock::PubSub::Publisher<void __cdecl(Option const &,enum InputMode),Bedrock::PubSub::ThreadModel::MultiThreaded,void>` | mInputModeChangedPublisher
248 | (8) `std::unique_ptr<Bedrock::PubSub::Publisher<void __cdecl(bool &),Bedrock::PubSub::ThreadModel::MultiThreaded,void>>` | mLock
256 | (32) `std::string` | mSaveTag
288 | (32) `std::string` | mTelemetryProperty
320 | (4) `const OptionID` | mID
324 | (4) `const OptionOwnerType` | mOwnerType
328 | (4) `OptionType` | mOptionType
336 | (32) `const std::string` | mCaptionId
368 | (4) `_BYTE[4]` | mOptionResetFlags
376 | (8) `Option *` | mOverrideSource
384 | (16) `Bedrock::PubSub::ScopedSubscription` | mOverrideSourceValueChangedSubscription
400 | (16) `Bedrock::PubSub::ScopedSubscription` | mOverrideSourceInputModeChangedSubscription
416 | (64) `std::function<void __cdecl(bool)>` | mRequestSaveCallback
480 | (1) `bool` | mCanChange


### `optional_ref<TerrainMaterialVariationManager const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const TerrainMaterialVariationManager *` | ptr


### `optional_ref<rendergraph::FrameBufferBuilder>`
Offset | Type | Name
-|-|-|-
0 | (8) `rendergraph::FrameBufferBuilder *` | ptr


### `OptionConstants::<lambda_0e1acb4e778a483f08cd62409c6f59ee>`
Offset | Type | Name
-|-|-|-


### `OwnerPtrT<EntityRegistryRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (16) `OwnerStorageSharePtr<EntityRegistryOwned>` | baseclass_0


### `OwnerStorageSharePtr<EntityRegistryOwned>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<EntityRegistryOwned>` | mValue


### `OwnerPtrT<EntityRefTraits>`
Offset | Type | Name
-|-|-|-
0 | (24) `OwnerStorageEntity` | baseclass_0


### `OwnerStorageEntity`
Offset | Type | Name
-|-|-|-
0 | (24) `std::optional<OwnerStorageEntity::EntityContextOwned>` | mContext


### `OwnerStorageEntity::EntityContextOwned`
Offset | Type | Name
-|-|-|-
0 | (16) `EntityContext` | baseclass_0


### `optional_ref<Localization const >`
Offset | Type | Name
-|-|-|-
0 | (8) `const Localization *` | ptr


### `OptionSaveDeferral`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<Options>` | mOptions


### `ObjModel`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | name
32 | (24) `std::vector<float>` | positions
56 | (24) `std::vector<float>` | normals
80 | (24) `std::vector<float>` | texcoords
104 | (24) `std::vector<unsigned int>` | colors
128 | (24) `std::vector<unsigned int>` | indices


### `optional_ref<rendergraph::Pass>`
Offset | Type | Name
-|-|-|-
0 | (8) `rendergraph::Pass *` | ptr


### `OwnedDurablesPagingCache::{ctor}::__l2::<lambda_28a90fe2ce902a855825d33515958818>`
Offset | Type | Name
-|-|-|-
0 | (8) `OwnedDurablesPagingCache *const` | __this


### `OwnedDurablesPagingCache::search::__l2::<lambda_c62e108c2369350517fae1efb94c51cb>`
Offset | Type | Name
-|-|-|-
0 | (8) `OwnedDurablesPagingCache *const` | __this
8 | (576) `const SearchQuery` | query
584 | (64) `std::function<void __cdecl(DurableSearchResults const &)>` | callback


### `OwnerPtrT<SharePtrRefTraits<FogDefinition const > >`
Offset | Type | Name
-|-|-|-
0 | (16) `OwnerStorageSharePtr<FogDefinition const >` | baseclass_0


### `OwnerStorageSharePtr<FogDefinition const >`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<FogDefinition const >` | mValue


### `OwnedItemStackRequestScope`
Offset | Type | Name
-|-|-|-
0 | (8) `ItemStackNetManagerClient *` | mItemStackNetManagerClient
8 | (1) `bool` | mBeganRequest
16 | (16) `std::shared_ptr<ItemStackRequestData>` | mResult


### `OptionalString`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | valid
8 | (32) `std::string` | string


### `OSInformation`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | MajorOSVersion
4 | (4) `unsigned int` | MinorOSVersion
8 | (32) `std::string` | OSVersionName


### `OverworldGenerator::OverridableBiomeSourceHelper`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<CachedBiomeSource<VanillaOverworldBiomeSource>>` | mNormalBiomeSource
8 | (8) `std::unique_ptr<FixedBiomeSource>` | mOverriddenBiomeSource
16 | (8) `BiomeSource *` | mBiomeSource


### `OceanRuinConfiguration`
Offset | Type | Name
-|-|-|-
0 | (4) `OceanTempCategory` | type
4 | (4) `float` | largeProbability
8 | (4) `float` | clusterProbability


### `OwnerPtrT<SharePtrRefTraits<PerlinSimplexNoise> >`
Offset | Type | Name
-|-|-|-
0 | (16) `OwnerStorageSharePtr<PerlinSimplexNoise>` | baseclass_0


### `OwnerStorageSharePtr<PerlinSimplexNoise>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<PerlinSimplexNoise>` | mValue


### `OutputString`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | ptr
8 | (8) `char *` | end
16 | (8) `_object *` | obj
24 | (8) `__int64` | size_increment


### `OnScreenTextureAnimationPacket`
```
const struct __cppobj __declspec(align(8)) OnScreenTextureAnimationPacket : Packet
{
  unsigned int mEffectID;
};

```

### `OnScreenTextureAnimationPacket_vtbl`
```
struct /*VFT*/ OnScreenTextureAnimationPacket_vtbl
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

### `Option_vtbl`
```
struct /*VFT*/ Option_vtbl
{
  void (__fastcall *~Option)(Option *this);
  void (__fastcall *save)(Option *this, std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *load)(Option *this, const Json::Value *);
  void (__fastcall *load)(Option *this, std::map<std::string,std::string> *);
  void (__fastcall *load)(Option *this, const std::string *);
};

```

### `Options`
```
struct __cppobj Options : std::enable_shared_from_this<Options>
{
  std::array<std::unique_ptr<Option>,541> mOptions;
  std::unique_ptr<ChatOptions> mChatOptions;
  Options *mPerMachineOptionsSource;
  std::string mOverrideUsername;
  Core::PathBuffer<std::string > mFilePath;
  bool mLoadInProgress;
  bool mUseVROptions;
  bool mPrimaryUserStatus;
  bool mAllowedToSave;
  _BYTE mSaveRequestMode[4];
  std::atomic<int> mSaveDeferralCount;
  std::chrono::time_point<std::chrono::steady_clock,std::chrono::duration<__int64,std::ratio<1,1000000000> > > mNextSaveTime;
  std::unique_ptr<OptionValueInterface> mOptionValues;
  int mDefaultViewDistanceChunks;
  int mDefaultRayTracingViewDistanceChunks;
  int mDefaultVRViewDistanceChunks;
  std::vector<int> mRenderDistanceLevels;
  std::vector<int> mVRRenderDistanceLevels;
  std::vector<int> mRayTracingRenderDistanceLevels;
  float mPpmDpadSizeOld;
  std::vector<std::string> mRecentSkinIds;
  std::unique_ptr<GamePadRemappingLayout> mGamePadRemappings[4];
  std::unique_ptr<GamePadRemappingLayout> mMotionControllerRemapping;
  std::vector<std::shared_ptr<KeyboardRemappingLayout>> mKeyboardRemappings;
  Core::Subject<OptionsObserver,Core::SingleThreadedLock> mEventSubject;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  bool mIsSaveInProgress;
  std::vector<Bedrock::PubSub::ScopedSubscription> mObserverSubscriptions;
  std::vector<Bedrock::PubSub::ScopedSubscription> mLockSubscriptions;
  int mLockPlayerViewMode;
  int mLockViewBobbing;
};

```

### `OptionValueInterface`
```
struct __cppobj OptionValueInterface
{
  OptionValueInterface_vtbl *__vftable /*VFT*/;
};

```

### `OptionValueInterface_vtbl`
```
struct /*VFT*/ OptionValueInterface_vtbl
{
  void (__fastcall *~OptionValueInterface)(OptionValueInterface *this);
  const std::vector<int> *(__fastcall *getRenderDistanceLevels)(OptionValueInterface *this, const std::vector<int> *result);
  const std::vector<int> *(__fastcall *getVRRenderDistanceLevels)(OptionValueInterface *this, const std::vector<int> *result);
  const std::vector<int> *(__fastcall *getRayTracingRenderDistanceLevels)(OptionValueInterface *this, const std::vector<int> *result);
  int (__fastcall *getDefaultRenderDistanceLevel)(OptionValueInterface *this);
  int (__fastcall *getDefaultVRRenderDistanceLevel)(OptionValueInterface *this);
  int (__fastcall *getDefaultRayTracingRenderDistanceLevel)(OptionValueInterface *this);
  bool (__fastcall *getDefaultTexelAA)(OptionValueInterface *this);
  bool (__fastcall *getDefaultVRTexelAA)(OptionValueInterface *this);
  int (__fastcall *getDefaultMSAA)(OptionValueInterface *this);
  int (__fastcall *getDefaultVRMSAA)(OptionValueInterface *this);
  VRHUDPosition (__fastcall *getDefaultVRHUDPosition)(OptionValueInterface *this);
  const std::vector<int> *(__fastcall *getSupportedMSAAValues)(OptionValueInterface *this, const std::vector<int> *result, bool);
  void (__fastcall *setMSAAValue)(OptionValueInterface *this, int);
  void (__fastcall *setTexelAA)(OptionValueInterface *this, const bool);
};

```

### `OptionsObserver`
```
struct __cppobj OptionsObserver : Core::Observer<OptionsObserver,Core::SingleThreadedLock>
{
};

```

### `OptionsObserver_vtbl`
```
struct /*VFT*/ OptionsObserver_vtbl
{
  void (__fastcall *~Observer<OptionsObserver,Core::SingleThreadedLock>)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *_onSubjectDestroyed)(Core::Observer<OptionsObserver,Core::SingleThreadedLock> *this);
  void (__fastcall *onForceCloudSave)(OptionsObserver *this);
  void (__fastcall *onOptionsLoadBegin)(OptionsObserver *this);
  void (__fastcall *onOptionsLoadComplete)(OptionsObserver *this);
};

```

### `Offer`
```
struct __cppobj Offer
{
  ProductSku mProductSku;
  ProductType mProductType;
  OfferCategory mCategory;
  std::unique_ptr<ProductInfo> mActiveProductInfo;
  std::vector<std::shared_ptr<Purchase>> mActivePurchases;
};

```

### `ObjectiveCriteria`
```
const struct __cppobj __declspec(align(8)) ObjectiveCriteria
{
  const std::string mName;
  const bool mReadOnly;
  const ObjectiveRenderType mRenderType;
};

```

### `Objective`
```
const struct __cppobj Objective
{
  std::unordered_map<ScoreboardId,int> mScores;
  const std::string mName;
  std::string mDisplayName;
  const ObjectiveCriteria *mCriteria;
};

```

### `OfferCollectionComponent`
```
struct __cppobj __declspec(align(8)) OfferCollectionComponent : StoreUIComponent
{
  std::shared_ptr<CatalogCollection> mCollection;
  bool mIsValid;
};

```

### `OfferCollectionComponent_vtbl`
```
struct /*VFT*/ OfferCollectionComponent_vtbl
{
  void (__fastcall *~StoreUIComponent)(StoreUIComponent *this);
  void (__fastcall *tick)(StoreUIComponent *this, ui::DirtyFlag *);
  bool (__fastcall *canRemove)(StoreUIComponent *this);
  int (__fastcall *getReadyCount)(StoreUIComponent *this);
  void (__fastcall *parseData)(StoreUIComponent *this, const struct web::json::value *);
};

```

### `OwnedDurablesPagingCache`
```
struct __cppobj OwnedDurablesPagingCache
{
  const int SEARCH_BATCH_SIZE;
  std::shared_ptr<GenericEntitlementChangeListener> mEntitlementChangeListener;
  std::function<void __cdecl(SearchQuery const &,std::function<void __cdecl(DurableSearchResults const &)>)> mSearchHandler;
  std::unordered_map<std::string,DocumentMeta> mDocumentCache;
  std::unordered_map<unsigned int,std::unique_ptr<std::unordered_set<std::string>>> mCachedQueryResultsMap;
  std::function<std::vector<mce::UUID> __cdecl(void)> mRetrieveOwnedPackIds;
  std::function<std::unordered_set<PackIdVersion,PackIdentityUUIDHash,PackIdentityUUIDEquality,std::allocator<PackIdVersion> > __cdecl(void)> mRetrieveInstalledPackIds;
};

```

### `optional_ref<rendergraph::ResourceViewInterface const >`
```
struct __cppobj optional_ref<rendergraph::ResourceViewInterface const >
{
  const rendergraph::ResourceViewInterface *ptr;
};

```

### `optional_ref<rendergraph::ResourceTargetInterface const >`
```
struct __cppobj optional_ref<rendergraph::ResourceTargetInterface const >
{
  const rendergraph::ResourceTargetInterface *ptr;
};

```

### `OverlayTextureMap`
```
struct __cppobj OverlayTextureMap
{
  mce::TextureGroupBase *mTextureGroup;
  _BYTE mCachedOverlayTextureId[4];
  mce::TexturePtr mCachedOverlayTexture;
  std::array<std::string,2> mTextureNames;
};

```

### `optional_ref<PlayerRenderView>`
```
struct __cppobj optional_ref<PlayerRenderView>
{
  PlayerRenderView *ptr;
};

```

### `optional_ref<PlayerRenderView::LegacyPlayerRenderPass>`
```
struct __cppobj optional_ref<PlayerRenderView::LegacyPlayerRenderPass>
{
  PlayerRenderView::LegacyPlayerRenderPass *ptr;
};

```

### `optional_ref<mce::RenderStage>`
```
struct __cppobj optional_ref<mce::RenderStage>
{
  mce::RenderStage *ptr;
};

```

### `optional_ref<CommandListQueue>`
```
struct __cppobj optional_ref<CommandListQueue>
{
  CommandListQueue *ptr;
};

```

### `OVRPlatformMessageHandler`
```
struct __cppobj OVRPlatformMessageHandler
{
  OVRPlatformMessageHandler_vtbl *__vftable /*VFT*/;
};

```

### `OVRPlatformMessageHandler_vtbl`
```
struct /*VFT*/ OVRPlatformMessageHandler_vtbl
{
  void (__fastcall *~OVRPlatformMessageHandler)(OVRPlatformMessageHandler *this);
  bool (__fastcall *handleMessage)(OVRPlatformMessageHandler *this, struct ovrMessage *);
};

```

### `OculusPlatformMessagePump`
```
struct __cppobj __declspec(align(8)) OculusPlatformMessagePump
{
  std::vector<OVRPlatformMessageHandler *> mOVRPlatformMessageHandlers;
  bool mEnabled;
};

```

### `OfferRepository::ProductQueryAttemptResult`
```
struct __cppobj OfferRepository::ProductQueryAttemptResult
{
  bool mComplete;
  bool mSuccess;
};

```

### `OfferRepository::RealmsOfferTypeContainer`
```
struct __cppobj OfferRepository::RealmsOfferTypeContainer
{
  std::map<enum RealmsOfferPeriod,std::map<enum RealmsOfferTier,std::vector<Offer *>>> Elements;
};

```

### `OculusSyncService`
```
struct __cppobj OculusSyncService : ServiceClient
{
};

```

### `OculusSyncService_vtbl`
```
struct /*VFT*/ OculusSyncService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `OfferRepository`
```
struct __cppobj OfferRepository : StoreListener, Bedrock::EnableNonOwnerReferences, std::enable_shared_from_this<OfferRepository>
{
  IMinecraftEventing *mEventing;
  Bedrock::NonOwnerPointer<Social::IUserManager> mUserManager;
  IEntitlementManager *mEntitlementManager;
  IClientInstance *mPrimaryClient;
  std::vector<std::unique_ptr<Offer>> mAllOffers;
  std::vector<Offer *> mRealmsOffersPendingFulfillment;
  std::vector<Offer *> mMinecoinOffersPendingFulfillment;
  std::vector<Offer *> mEduOffersPendingFulfillment;
  std::function<std::shared_ptr<OfferRepository::ProductQueryAttemptResult> __cdecl(void)> mProductQueryAttemptCallback;
  std::map<enum RealmsOfferType,OfferRepository::RealmsOfferTypeContainer> mRealmsOfferMatrix;
  std::unique_ptr<GameStore> mGameStore;
  std::unique_ptr<DurableTransactionHandler> mDurableTransactionHandler;
  std::unique_ptr<RealmsTransactionHandler> mRealmsTransactionHandler;
  std::unique_ptr<MinecoinTransactionHandler> mMinecoinTransactionHandler;
  std::unique_ptr<EduTransactionHandler> mEduTransactionHandler;
  std::unique_ptr<PurchaseCache> mPurchaseCache;
  std::unique_ptr<TransactionContext> mUserTransactionContext;
  std::function<void __cdecl(bool)> mQueryPurchasesCallback;
  bool mQueryPurchasesAllowSignIn;
  __declspec(align(4)) RetryDelay mProductsRefresh;
  RetryDelay mPurchasesRefresh;
  RetryDelay mFulfillmentRefresh;
  bool mInitialized;
  ServiceRegistrationToken<OfferRepository> mServiceRegistrationToken;
};

```

### `OfferRepository_vtbl`
```
struct /*VFT*/ OfferRepository_vtbl
{
  void (__fastcall *~StoreListener)(StoreListener *this);
  void (__fastcall *onStoreInitialized)(StoreListener *this, bool);
  void (__fastcall *setStoreAvailable)(StoreListener *this, bool);
  void (__fastcall *onQueryProductsSuccess)(StoreListener *this, const std::vector<ProductInfo> *);
  void (__fastcall *onQueryProductsFail)(StoreListener *this);
  void (__fastcall *onPurchaseSuccessful)(StoreListener *this, const PurchaseInfo *);
  void (__fastcall *onPurchaseCanceled)(StoreListener *this, const ProductSku *);
  void (__fastcall *onPurchaseFailed)(StoreListener *this, const ProductSku *);
  void (__fastcall *onQueryPurchasesSuccess)(StoreListener *this, const std::vector<PurchaseInfo> *);
  void (__fastcall *onQueryPurchasesFail)(StoreListener *this);
  void (__fastcall *onAppPurchaseSuccess)(StoreListener *this);
  void (__fastcall *onAppPurchaseFailed)(StoreListener *this);
  void (__fastcall *onAppPurchaseCanceled)(StoreListener *this);
};

```

### `OwnerStorageFeature`
```
struct __cppobj OwnerStorageFeature
{
  std::optional<std::reference_wrapper<FeatureRegistry> > mRegistry;
  unsigned __int64 mIndex;
};

```

### `OwnerPtrT<FeatureRefTraits>`
```
struct __cppobj OwnerPtrT<FeatureRefTraits> : OwnerStorageFeature
{
};

```

### `OnHitSubcomponent`
```
struct __cppobj OnHitSubcomponent
{
  OnHitSubcomponent_vtbl *__vftable /*VFT*/;
};

```

### `OnHitSubcomponent_vtbl`
```
struct /*VFT*/ OnHitSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `OpenDoorAnnotationDescription`
```
struct __cppobj OpenDoorAnnotationDescription : ComponentDescription
{
};

```

### `OpenDoorAnnotationDescription_vtbl`
```
struct /*VFT*/ OpenDoorAnnotationDescription_vtbl
{
  const char *(__fastcall *getJsonName)(Description *this);
  void (__fastcall *~Description)(Description *this);
  void (__fastcall *deserializeData)(Description *this, DeserializeDataParams);
  void (__fastcall *serializeData)(Description *this, Json::Value *);
};

```

### `OwnerStorageSharePtr<EntityRegistry>`
```
struct __cppobj OwnerStorageSharePtr<EntityRegistry>
{
  std::shared_ptr<EntityRegistry> mValue;
};

```

### `OnlineSafetyProgressHandler`
```
struct __cppobj __declspec(align(8)) OnlineSafetyProgressHandler : ProgressHandler
{
  OnlineSafetyProgressHandler::State mState;
};

```

### `OnlineSafetyProgressHandler_vtbl`
```
struct /*VFT*/ OnlineSafetyProgressHandler_vtbl
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

### `OfferCollectionCustom`
```
struct __cppobj __declspec(align(8)) OfferCollectionCustom
{
  QueryDocument mQueryDoc;
  int mSalesRecentDocumentValue;
};

```

### `OfferCollectionDocument`
```
struct __cppobj OfferCollectionDocument
{
  CommonDocument mCommon;
  OfferCollectionCustom mCustom;
};

```

### `OfferCollectionSearchResults`
```
const struct __cppobj OfferCollectionSearchResults : CommonSearchResults
{
  std::vector<OfferCollectionDocument> mDocuments;
};

```

### `OnlineSafetyDialogScreenController`
```
struct __cppobj OnlineSafetyDialogScreenController : MinecraftScreenController
{
  OnlineSafetyProgressHandler *mOnlineSafetyProgressHandler;
};

```

### `OnlineSafetyDialogScreenController_vtbl`
```
struct /*VFT*/ OnlineSafetyDialogScreenController_vtbl
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

### `OnlineSafetyDialogScreenController::_registerProgressBindings::__l2::<lambda_7cab83aadfffc6c6f3533f3188941405>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerProgressBindings::__l2::<lambda_7cab83aadfffc6c6f3533f3188941405>
{
};

```

### `OnlineSafetyDialogScreenController::_registerProgressBindings::__l2::<lambda_9a561524d40350cc3faeda38517440ce>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerProgressBindings::__l2::<lambda_9a561524d40350cc3faeda38517440ce>
{
  OnlineSafetyDialogScreenController *const __this;
};

```

### `OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_aa0696b494dc24d731ca3415eb7512e1>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_aa0696b494dc24d731ca3415eb7512e1>
{
  OnlineSafetyDialogScreenController *const __this;
};

```

### `OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_ff8c03f366e9ea90c239e7accb05879d>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_ff8c03f366e9ea90c239e7accb05879d>
{
  OnlineSafetyDialogScreenController *const __this;
};

```

### `OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_1ca3a046a3907aedfae4f13653e071cc>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_1ca3a046a3907aedfae4f13653e071cc>
{
  OnlineSafetyDialogScreenController *const __this;
};

```

### `OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_a93e6c06c61804e1fbd2a20a8c69c969>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_a93e6c06c61804e1fbd2a20a8c69c969>
{
  OnlineSafetyDialogScreenController *const __this;
};

```

### `OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_98bb0289cd1621c1ca883be4cca3467d>`
```
struct __cppobj OnlineSafetyDialogScreenController::_registerEventHandlers::__l2::<lambda_98bb0289cd1621c1ca883be4cca3467d>
{
};

```

### `OfferCategoryEnumHasher`
```
struct __cppobj OfferCategoryEnumHasher
{
};

```

### `optional_ref<int>`
```
struct __cppobj optional_ref<int>
{
  int *ptr;
};

```

### `optional_ref<mce::Texture>`
```
struct __cppobj optional_ref<mce::Texture>
{
  mce::Texture *ptr;
};

```

### `OptionActivationRule`
```
struct __cppobj __declspec(align(8)) OptionActivationRule : ActivationRule
{
  PlayerViewMode mType;
};

```

### `OptionActivationRule_vtbl`
```
struct /*VFT*/ OptionActivationRule_vtbl
{
  void (__fastcall *~ActivationRule)(ActivationRule *this);
  std::unique_ptr<ActivationRule> *(__fastcall *create)(ActivationRule *this, std::unique_ptr<ActivationRule> *result, Json::Value *);
  bool (__fastcall *evaluate)(ActivationRule *this, const IClientInstance *, float, const Camera *);
};

```

### `OrbitBehavior`
```
struct __cppobj __declspec(align(8)) OrbitBehavior : CameraBehavior<OrbitBehavior>
{
  CriticallyDampedSpring<float> mAzimuthSmoothingSpring;
  CriticallyDampedSpring<float> mPolarAngleSmoothingSpring;
  CriticallyDampedSpring<float> mDistanceSmoothingSpring;
  Spherical mCurrentSpherical;
  Spherical mIdealSpherical;
  float mPolarAngleMin;
  float mPolarAngleMax;
  float mAzimuthVelocity;
  float mPolarAngleVelocity;
  float mDistanceVelocity;
  float mDistanceConstraint;
};

```

### `OrbitBehavior_vtbl`
```
struct /*VFT*/ OrbitBehavior_vtbl
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

### `OrbitBehaviorLoader`
```
struct __cppobj OrbitBehaviorLoader : CameraBehaviorLoader
{
};

```

### `OrbitBehaviorLoader_vtbl`
```
struct /*VFT*/ OrbitBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `OverloadSyntaxInformation`
```
struct __cppobj OverloadSyntaxInformation
{
  std::string text;
  unsigned int start;
  unsigned int length;
};

```

### `OnUseItemComponent`
```
struct __cppobj OnUseItemComponent : ItemComponent
{
  DefinitionTrigger mOnUse;
};

```

### `OnUseItemComponent_vtbl`
```
struct /*VFT*/ OnUseItemComponent_vtbl
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

### `OwnedDurablesPagingCache::AggregateResults`
```
struct __cppobj OwnedDurablesPagingCache::AggregateResults
{
  int mRemainingBatches;
  std::unique_ptr<std::unordered_set<std::string>> mProductIdSet;
  std::function<void __cdecl(std::unique_ptr<std::unordered_set<std::string>>)> mCallback;
};

```

### `OptionSaveDeferral::release::__l16::<lambda_b309dec70b808e8609e224c1506fb95a>`
```
struct __cppobj OptionSaveDeferral::release::__l16::<lambda_b309dec70b808e8609e224c1506fb95a>
{
  std::weak_ptr<Options> options;
};

```

### `Options::setPlayerViewPerspective::__l2::<lambda_2933f73a92da25ab7eb8888027fc5027>`
```
struct __cppobj Options::setPlayerViewPerspective::__l2::<lambda_2933f73a92da25ab7eb8888027fc5027>
{
  Options *const __this;
  int *playerViewPerspective;
};

```

### `Options::_endLoadingSession::__l5::<lambda_c02e99fb4834412c0d487a342dd02b2a>`
```
struct __cppobj Options::_endLoadingSession::__l5::<lambda_c02e99fb4834412c0d487a342dd02b2a>
{
};

```

### `Options::_beginLoadingSession::__l5::<lambda_efe1aacdc65c1acb51ca6cd303b70c1d>`
```
struct __cppobj Options::_beginLoadingSession::__l5::<lambda_efe1aacdc65c1acb51ca6cd303b70c1d>
{
};

```

### `Options::_loadOptions::__l2::<lambda_f2dc6bf19bfc274071900699a3267aab>`
```
struct __cppobj Options::_loadOptions::__l2::<lambda_f2dc6bf19bfc274071900699a3267aab>
{
  Options *const __this;
};

```

### `Options::_loadOptions::__l2::<lambda_a60f418fafc87ff5dc33874f9996e92d>`
```
struct __cppobj Options::_loadOptions::__l2::<lambda_a60f418fafc87ff5dc33874f9996e92d>
{
  Options *const __this;
};

```

### `Options::_loadOptions::__l2::<lambda_75c87264413dc083e0ecaa10c5192172>`
```
struct __cppobj Options::_loadOptions::__l2::<lambda_75c87264413dc083e0ecaa10c5192172>
{
  Options *const __this;
};

```

### `Options::_save::__l18::<lambda_6f9032d848d392ddf02a80ada4c68215>`
```
struct __cppobj Options::_save::__l18::<lambda_6f9032d848d392ddf02a80ada4c68215>
{
};

```

### `Options::_saveAsync::__l2::<lambda_79138d76ef9458f6e4612f819f3ab2ea>`
```
struct __cppobj __declspec(align(8)) Options::_saveAsync::__l2::<lambda_79138d76ef9458f6e4612f819f3ab2ea>
{
  Options *const __this;
  std::shared_ptr<bool> hasFailedToSave;
  _BYTE cachedSaveRequest[4];
};

```

### `Options::_saveAsync::__l2::<lambda_fbed4f7a7e8aeeddc0b8e4a80d747935>`
```
struct __cppobj Options::_saveAsync::__l2::<lambda_fbed4f7a7e8aeeddc0b8e4a80d747935>
{
  Options *const __this;
  std::vector<std::pair<std::string,std::string >> settingsVec;
  std::shared_ptr<bool> hasFailedToSave;
};

```

### `Options::_saveAsync::__l2::<lambda_79138d76ef9458f6e4612f819f3ab2ea>::()::__l8::<lambda_0dfff5764f0623e212f81d2e2f8bfba1>`
```
struct __cppobj Options::_saveAsync::__l2::<lambda_79138d76ef9458f6e4612f819f3ab2ea>::()::__l8::<lambda_0dfff5764f0623e212f81d2e2f8bfba1>
{
};

```

### `Options::_registerSelfLocks::__l2::<lambda_50fe63b9e25ac6375291495c25d838f4>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_50fe63b9e25ac6375291495c25d838f4>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_b5d6adc02c288532a55896180d04bcb6>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_b5d6adc02c288532a55896180d04bcb6>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_a38362f13b6055cf66128de76723f3d8>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_a38362f13b6055cf66128de76723f3d8>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_ac581a5d50fb80d69368380a8811d8a1>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_ac581a5d50fb80d69368380a8811d8a1>
{
};

```

### `Options::_registerSelfLocks::__l2::<lambda_57c624900efc65c068fad36bbfdbaebf>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_57c624900efc65c068fad36bbfdbaebf>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_199adfe065c6dca797da5ce18416772e>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_199adfe065c6dca797da5ce18416772e>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_cd834d48ffb65032bb9f6c8cca8d0312>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_cd834d48ffb65032bb9f6c8cca8d0312>
{
  Options::_registerSelfLocks::__l2::<lambda_199adfe065c6dca797da5ce18416772e> vrSnapLock;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_86205ee13076472cb59fe87cb90a8ae9>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_86205ee13076472cb59fe87cb90a8ae9>
{
  Options::_registerSelfLocks::__l2::<lambda_199adfe065c6dca797da5ce18416772e> vrSnapLock;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_b9da9739a53f45c8f2534e78482a8f15>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_b9da9739a53f45c8f2534e78482a8f15>
{
  Options::_registerSelfLocks::__l2::<lambda_199adfe065c6dca797da5ce18416772e> vrSnapLock;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_0a437dfd734b2239b707d376daf7211a>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_0a437dfd734b2239b707d376daf7211a>
{
  Options *const __this;
};

```

### `Options::_registerSelfLocks::__l2::<lambda_de46fbdf10fbd5875880cec202917d13>`
```
struct __cppobj Options::_registerSelfLocks::__l2::<lambda_de46fbdf10fbd5875880cec202917d13>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_8728dfacd96bef3f811545e6af45195a>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_8728dfacd96bef3f811545e6af45195a>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_236561e98783743080cb37aab28a134f>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_236561e98783743080cb37aab28a134f>
{
  Options::_registerSelfObservers::__l2::<lambda_8728dfacd96bef3f811545e6af45195a> forEachGamePadRemapping;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_236561e98783743080cb37aab28a134f>::()::__l2::<lambda_7ecfef012c0561dc8df6ecd46b929d09>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_236561e98783743080cb37aab28a134f>::()::__l2::<lambda_7ecfef012c0561dc8df6ecd46b929d09>
{
  const bool newValue;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_da79e5db0113a982f326005a0df5fe67>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_da79e5db0113a982f326005a0df5fe67>
{
  Options::_registerSelfObservers::__l2::<lambda_8728dfacd96bef3f811545e6af45195a> forEachGamePadRemapping;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_da79e5db0113a982f326005a0df5fe67>::()::__l2::<lambda_83afd32887477a4a48785321fb5da7ce>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_da79e5db0113a982f326005a0df5fe67>::()::__l2::<lambda_83afd32887477a4a48785321fb5da7ce>
{
  const bool newValue;
};

```

### `Options::_registerSelfObservers::__l5::<lambda_54a4fc15e87446e96720d7403f0c0d1e>`
```
struct __cppobj Options::_registerSelfObservers::__l5::<lambda_54a4fc15e87446e96720d7403f0c0d1e>
{
};

```

### `Options::_registerSelfObservers::__l5::<lambda_557bf8d5cc55e77fe80dd091c4484c9d>`
```
struct __cppobj Options::_registerSelfObservers::__l5::<lambda_557bf8d5cc55e77fe80dd091c4484c9d>
{
};

```

### `Options::_registerSelfObservers::__l2::<lambda_83f555d90a49e0a1b25a0ec40e3fff25>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_83f555d90a49e0a1b25a0ec40e3fff25>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_e30f9b834d00dfc3dd4e96db8a3a5bea>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_e30f9b834d00dfc3dd4e96db8a3a5bea>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_64ef34ccf9fab49f51aa313471ca3845>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_64ef34ccf9fab49f51aa313471ca3845>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_c77648a2d5ed4dd75b935a12e6167dc4>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_c77648a2d5ed4dd75b935a12e6167dc4>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_153f972500716c6f966a5058a0a6e79d>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_153f972500716c6f966a5058a0a6e79d>
{
  Options *const __this;
};

```

### `Options::_registerSelfObservers::__l2::<lambda_e4f03c81be69e05a90c38d508926b073>`
```
struct __cppobj Options::_registerSelfObservers::__l2::<lambda_e4f03c81be69e05a90c38d508926b073>
{
  Options *const __this;
};

```

### `Options::_setOptionCallbacks::__l2::<lambda_2baa0dd320795f4976a4bc2b9c2a8c73>`
```
struct __cppobj Options::_setOptionCallbacks::__l2::<lambda_2baa0dd320795f4976a4bc2b9c2a8c73>
{
  Options *const __this;
};

```

### `Options::_setOptionCallbacks::__l2::<lambda_977405555789dcffc289e657addad1ed>`
```
struct __cppobj Options::_setOptionCallbacks::__l2::<lambda_977405555789dcffc289e657addad1ed>
{
};

```

### `Options::_setOptionCallbacks::__l2::<lambda_adeaa5a7f14542839dda6e3dd82859e5>`
```
struct __cppobj Options::_setOptionCallbacks::__l2::<lambda_adeaa5a7f14542839dda6e3dd82859e5>
{
};

```

### `Options::_registerOption::__l2::<lambda_66976bbdee59fb67fe1feb36db4af030>`
```
struct __cppobj Options::_registerOption::__l2::<lambda_66976bbdee59fb67fe1feb36db4af030>
{
  Options *const __this;
};

```

### `Options::{ctor}::__l14::<lambda_fa4403c1a03d594c6268b771c878a778>`
```
struct __cppobj Options::{ctor}::__l14::<lambda_fa4403c1a03d594c6268b771c878a778>
{
  Options *const __this;
};

```

### `Options::_registerChatOptions::__l2::<lambda_4b61316cf59efab0fcdfe3f771b9653b>`
```
struct __cppobj Options::_registerChatOptions::__l2::<lambda_4b61316cf59efab0fcdfe3f771b9653b>
{
  Options *const __this;
};

```

### `OwnerStorageSharePtr<FogDefinition>`
```
struct __cppobj OwnerStorageSharePtr<FogDefinition>
{
  std::shared_ptr<FogDefinition> mValue;
};

```

### `OwnedDurablesPagingCache::_performBatchedSearch::__l2::<lambda_b134f75ebce8a481f3da8d26d3d4bddf>`
```
struct __cppobj OwnedDurablesPagingCache::_performBatchedSearch::__l2::<lambda_b134f75ebce8a481f3da8d26d3d4bddf>
{
  OwnedDurablesPagingCache *const __this;
  std::shared_ptr<std::vector<mce::UUID> > packIdBatch;
  std::shared_ptr<OwnedDurablesPagingCache::AggregateResults> sharedResults;
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_709068024ba758914a8b9be0575b359c>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_709068024ba758914a8b9be0575b359c>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_f79e648a61267cc2eba8fabdbac8c75a>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_f79e648a61267cc2eba8fabdbac8c75a>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_278f90c39267690d5f8fd7879c8a262a>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_278f90c39267690d5f8fd7879c8a262a>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_b101d75ce3122f6287edbbe29bc1860e>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_b101d75ce3122f6287edbbe29bc1860e>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_2352e89429b7cbbe1e610b942d38dc7a>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_2352e89429b7cbbe1e610b942d38dc7a>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_810c9df654a8be4ff39687782286a8a0>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_810c9df654a8be4ff39687782286a8a0>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_39e81e94d3d33a0f208a7c22f80c2a20>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_39e81e94d3d33a0f208a7c22f80c2a20>
{
};

```

### `OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_fb4fd9557833de1e6e3d537364831732>`
```
struct __cppobj OwnedDurablesPagingCache::_sortDocIteratorsBy::__l2::<lambda_fb4fd9557833de1e6e3d537364831732>
{
};

```

### `OculusPostData`
```
struct __cppobj OculusPostData
{
  const std::string mOculusAppId;
  const std::string mLanguageCode;
  const std::string mRegionCode;
  const std::string mCustomerPurchaseId;
  const std::string mOculusUserAccessToken;
  const std::string mProductSku;
};

```

### `OculusGetServiceTicket`
```
struct __cppobj OculusGetServiceTicket : RequestHandler
{
  std::string mClientId;
  mce::UUID mCorrelationId;
  std::function<void __cdecl(std::string const &)> mCallback;
  std::shared_ptr<std::string > mServiceTicketResponse;
};

```

### `OculusGetServiceTicket_vtbl`
```
struct /*VFT*/ OculusGetServiceTicket_vtbl
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

### `OculusPostEntitlement`
```
struct __cppobj OculusPostEntitlement : RequestHandler
{
  OculusPostData mPostData;
  mce::UUID mCorrelationId;
  std::function<void __cdecl(bool)> mCallback;
  std::shared_ptr<bool> mSuccess;
};

```

### `OculusPostEntitlement_vtbl`
```
struct /*VFT*/ OculusPostEntitlement_vtbl
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

### `OfferRepository::update::__l25::<lambda_872c40fd9efcbf74f55c70f8d9ffb74d>`
```
struct __cppobj OfferRepository::update::__l25::<lambda_872c40fd9efcbf74f55c70f8d9ffb74d>
{
  OfferRepository *const __this;
};

```

### `OfferRepository::update::__l22::<lambda_8ae77870353b265a35b8d175223822f8>`
```
struct __cppobj OfferRepository::update::__l22::<lambda_8ae77870353b265a35b8d175223822f8>
{
  OfferRepository *const __this;
};

```

### `OfferRepository::beginAsyncInit::__l2::<lambda_fe2a701c6f03e4c80ab08db13674b5da>`
```
struct __cppobj OfferRepository::beginAsyncInit::__l2::<lambda_fe2a701c6f03e4c80ab08db13674b5da>
{
  std::weak_ptr<OfferRepository> weakThis;
};

```

### `OfferRepository::beginAsyncInit::__l2::<lambda_0690b8f7dfc1d762a7c6c615b4ac4b94>`
```
struct __cppobj OfferRepository::beginAsyncInit::__l2::<lambda_0690b8f7dfc1d762a7c6c615b4ac4b94>
{
  std::weak_ptr<OfferRepository> weakThis;
};

```

### `OfferRepository::registerProductQueryAttemptCallback::__l2::<lambda_36626fa5e6a2b1fdb27f2301632d6635>`
```
struct __cppobj OfferRepository::registerProductQueryAttemptCallback::__l2::<lambda_36626fa5e6a2b1fdb27f2301632d6635>
{
  std::shared_ptr<OfferRepository::ProductQueryAttemptResult> productQueryAttempted;
};

```

### `OutOfControlDefinition`
```
struct __cppobj OutOfControlDefinition
{
};

```

### `OutOfControlComponent`
```
struct __cppobj OutOfControlComponent : IEntityComponent
{
};

```

### `OnUseOnItemComponent`
```
struct __cppobj OnUseOnItemComponent : ItemComponent
{
  DefinitionTrigger mOnUseOn;
};

```

### `OnUseOnItemComponent_vtbl`
```
struct /*VFT*/ OnUseOnItemComponent_vtbl
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

### `OnFallOnTriggerDescription`
```
struct __cppobj __declspec(align(8)) OnFallOnTriggerDescription : BlockTriggerDescription<OnFallOnTrigger>
{
  float mMinimumFallDistance;
};

```

### `OnFallOnTriggerDescription_vtbl`
```
struct /*VFT*/ OnFallOnTriggerDescription_vtbl
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

### `OnFallOnTrigger`
```
struct __cppobj __declspec(align(8)) OnFallOnTrigger : DefinitionTrigger
{
  float mMinimumFallDistance;
};

```

### `OnFallOnTriggerDescription::buildSchema::__l2::<lambda_ff131107eb300bbd2c5caa396b00731d>`
```
struct __cppobj OnFallOnTriggerDescription::buildSchema::__l2::<lambda_ff131107eb300bbd2c5caa396b00731d>
{
};

```

### `OnFallOnTriggerDescription::buildSchema::__l2::<lambda_faf42de703e4e5a4c3f6fb1f94959021>`
```
struct __cppobj OnFallOnTriggerDescription::buildSchema::__l2::<lambda_faf42de703e4e5a4c3f6fb1f94959021>
{
};

```

### `OnFallOnTriggerDescription::buildSchema::__l2::<lambda_b614e50d91add974a8a52f7400d9d361>`
```
struct __cppobj OnFallOnTriggerDescription::buildSchema::__l2::<lambda_b614e50d91add974a8a52f7400d9d361>
{
};

```

### `OnFallOnTriggerDescription::buildSchema::__l2::<lambda_654a272ba692830cd3f5ce995706e46f>`
```
struct __cppobj OnFallOnTriggerDescription::buildSchema::__l2::<lambda_654a272ba692830cd3f5ce995706e46f>
{
};

```

### `OnFallOnTriggerDescription::buildSchema::__l2::<lambda_c92ebfb32705be8ff950d83fc5ef4c37>`
```
struct __cppobj OnFallOnTriggerDescription::buildSchema::__l2::<lambda_c92ebfb32705be8ff950d83fc5ef4c37>
{
  const BlockComponentFactory *factory;
};

```

### `OnInteractTriggerDescription`
```
struct __cppobj OnInteractTriggerDescription : BlockTriggerDescription<OnInteractTrigger>
{
};

```

### `OnInteractTriggerDescription_vtbl`
```
struct /*VFT*/ OnInteractTriggerDescription_vtbl
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

### `OnInteractTrigger`
```
struct __cppobj OnInteractTrigger : DefinitionTrigger
{
};

```

### `OnPlacedTriggerDescription`
```
struct __cppobj OnPlacedTriggerDescription : BlockTriggerDescription<OnPlacedTrigger>
{
};

```

### `OnPlacedTriggerDescription_vtbl`
```
struct /*VFT*/ OnPlacedTriggerDescription_vtbl
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

### `OnPlacedTrigger`
```
struct __cppobj OnPlacedTrigger : DefinitionTrigger
{
};

```

### `OnPlayerDestroyedTriggerDescription`
```
struct __cppobj OnPlayerDestroyedTriggerDescription : BlockTriggerDescription<OnPlayerDestroyedTrigger>
{
};

```

### `OnPlayerDestroyedTriggerDescription_vtbl`
```
struct /*VFT*/ OnPlayerDestroyedTriggerDescription_vtbl
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

### `OnPlayerDestroyedTrigger`
```
struct __cppobj OnPlayerDestroyedTrigger : DefinitionTrigger
{
};

```

### `OnPlayerPlacingTriggerDescription`
```
struct __cppobj OnPlayerPlacingTriggerDescription : BlockTriggerDescription<OnPlayerPlacingTrigger>
{
};

```

### `OnPlayerPlacingTriggerDescription_vtbl`
```
struct /*VFT*/ OnPlayerPlacingTriggerDescription_vtbl
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

### `OnPlayerPlacingTrigger`
```
struct __cppobj OnPlayerPlacingTrigger : DefinitionTrigger
{
};

```

### `OnStepOnTriggerDescription`
```
struct __cppobj OnStepOnTriggerDescription : BlockTriggerDescription<OnStepOnTrigger>
{
};

```

### `OnStepOnTriggerDescription_vtbl`
```
struct /*VFT*/ OnStepOnTriggerDescription_vtbl
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

### `OnStepOffTriggerDescription`
```
struct __cppobj OnStepOffTriggerDescription : BlockTriggerDescription<OnStepOffTrigger>
{
};

```

### `OnStepOffTriggerDescription_vtbl`
```
struct /*VFT*/ OnStepOffTriggerDescription_vtbl
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

### `OnStepOffTrigger`
```
struct __cppobj OnStepOffTrigger : DefinitionTrigger
{
};

```

### `OnStepOnTrigger`
```
struct __cppobj OnStepOnTrigger : DefinitionTrigger
{
};

```

### `OwnerPtrT<SharePtrRefTraits<FogDefinition> >`
```
struct __cppobj OwnerPtrT<SharePtrRefTraits<FogDefinition> > : OwnerStorageSharePtr<FogDefinition>
{
};

```

### `OpenDoorAnnotationComponent`
```
struct __cppobj OpenDoorAnnotationComponent : IEntityComponent
{
  std::queue<BlockPos> mPassedDoorPositions;
};

```

### `OnIgniteDefinition`
```
struct __cppobj OnIgniteDefinition : DefinitionTrigger
{
};

```

### `OnFriendlyAngerDefinition`
```
struct __cppobj OnFriendlyAngerDefinition : DefinitionTrigger
{
};

```

### `OpenDoorAnnotationSystem`
```
struct __cppobj OpenDoorAnnotationSystem : ITickingSystem
{
};

```

### `OpenDoorAnnotationSystem_vtbl`
```
struct /*VFT*/ OpenDoorAnnotationSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `ObservingNetworkPeer`
```
struct __cppobj ObservingNetworkPeer : NetworkPeer
{
  NetworkIdentifier mId;
  PacketObserver *mPacketObserver;
};

```

### `ObservingNetworkPeer_vtbl`
```
struct /*VFT*/ ObservingNetworkPeer_vtbl
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

### `Option::setOverrideSource::__l8::<lambda_b12e3f1582359f44e815cb61e571f14c>`
```
struct __cppobj Option::setOverrideSource::__l8::<lambda_b12e3f1582359f44e815cb61e571f14c>
{
  Option *const __this;
};

```

### `Option::setOverrideSource::__l8::<lambda_0267e32cdc5641c5ccc3bda66d66248e>`
```
struct __cppobj Option::setOverrideSource::__l8::<lambda_0267e32cdc5641c5ccc3bda66d66248e>
{
  Option *const __this;
};

```

### `OpCommand`
```
struct __cppobj OpCommand : ServerCommand
{
  CommandSelector<Player> mTargets;
};

```

### `OpCommand_vtbl`
```
struct /*VFT*/ OpCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `OnTargetAcquiredDefinition`
```
struct __cppobj OnTargetAcquiredDefinition : DefinitionTrigger
{
};

```

### `OnTargetEscapeDefinition`
```
struct __cppobj OnTargetEscapeDefinition : DefinitionTrigger
{
};

```

### `OnHurtDefinition`
```
struct __cppobj OnHurtDefinition : DefinitionTrigger
{
};

```

### `OnDeathDefinition`
```
struct __cppobj OnDeathDefinition : DefinitionTrigger
{
};

```

### `OnHurtByPlayerDefinition`
```
struct __cppobj OnHurtByPlayerDefinition : DefinitionTrigger
{
};

```

### `OnStartLandingDefinition`
```
struct __cppobj OnStartLandingDefinition : DefinitionTrigger
{
};

```

### `OnStartTakeoffDefinition`
```
struct __cppobj OnStartTakeoffDefinition : DefinitionTrigger
{
};

```

### `OnWakeWithOwnerDefinition`
```
struct __cppobj OnWakeWithOwnerDefinition : DefinitionTrigger
{
};

```

### `OfferFlowerGoal`
```
struct __cppobj OfferFlowerGoal : Goal
{
  TempEPtr<Mob> mOfferedToMob;
  int mGameTicks;
  IronGolem *mGolem;
};

```

### `OfferFlowerGoal_vtbl`
```
struct /*VFT*/ OfferFlowerGoal_vtbl
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

### `Ocelot`
```
struct __cppobj Ocelot : Animal
{
};

```

### `OffhandContainerModel`
```
struct __cppobj OffhandContainerModel : ContainerModel
{
  Player *mPlayer;
};

```

### `OffhandContainerModel_vtbl`
```
struct /*VFT*/ OffhandContainerModel_vtbl
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

### `OverworldHeightAttributes`
```
struct __cppobj OverworldHeightAttributes
{
  BiomeHeight mHeightParams;
};

```

### `ObserverBlock`
```
struct __cppobj ObserverBlock : FaceDirectionalBlock
{
};

```

### `ObserverBlock_vtbl`
```
struct /*VFT*/ ObserverBlock_vtbl
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

### `ObsidianBlock`
```
struct __cppobj __declspec(align(8)) ObsidianBlock : BlockLegacy
{
  bool mIsGlowing;
};

```

### `ObsidianBlock_vtbl`
```
struct /*VFT*/ ObsidianBlock_vtbl
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

### `OldLeafBlock`
```
struct __cppobj OldLeafBlock : LeafBlock
{
};

```

### `OldLeafBlock_vtbl`
```
struct /*VFT*/ OldLeafBlock_vtbl
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

### `OldLogBlock`
```
struct __cppobj OldLogBlock : LogBlock
{
};

```

### `OldLogBlock_vtbl`
```
struct /*VFT*/ OldLogBlock_vtbl
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

### `OreBlock`
```
struct __cppobj OreBlock : BlockLegacy
{
};

```

### `OreBlock_vtbl`
```
struct /*VFT*/ OreBlock_vtbl
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

### `OreFeature`
```
struct __cppobj OreFeature : IFeature
{
  int mCount;
  float mCountf;
  float mCountfInv;
  BlockDescriptor mBlock;
  std::vector<BlockDescriptor> mMayReplace;
  std::set<Block const *> mMatchBlocks;
};

```

### `OreFeature_vtbl`
```
struct /*VFT*/ OreFeature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `OceanMixerLayer`
```
struct __cppobj OceanMixerLayer : MixerLayer<Biome *,Biome *,enum BiomeTemperatureCategory>
{
  Biome *mGenericShallowOcean;
  Biome *mGenericDeepOcean;
  std::vector<std::pair<Biome *,unsigned int>> mShallowOceanBiomes[5];
  std::vector<std::pair<Biome *,unsigned int>> mDeepOceanBiomes[5];
};

```

### `OceanMixerLayer_vtbl`
```
struct /*VFT*/ OceanMixerLayer_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<Biome *> *(__fastcall *_allocateAndFill)(Layer<Biome *> *this, LayerDetails::TransferData<Biome *> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<Biome *,Biome *,enum BiomeTemperatureCategory> *this, LayerDetails::WorkingData<Biome *,Biome *> *, int, int, int, int, int, LayerResult<enum BiomeTemperatureCategory>);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<Biome *,Biome *,enum BiomeTemperatureCategory> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `OceanMixerLayer::{ctor}::__l2::<lambda_12b4dbfeadd327d72f7fe23713e095d6>`
```
struct __cppobj OceanMixerLayer::{ctor}::__l2::<lambda_12b4dbfeadd327d72f7fe23713e095d6>
{
  OceanMixerLayer *const __this;
  const TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > *tagRegistry;
  const WellKnownBiomeTags *wellKnownBiomeTags;
};

```

### `OverworldLightTextureImageBuilder`
```
struct __cppobj OverworldLightTextureImageBuilder : BaseLightTextureImageBuilder
{
};

```

### `OverworldLightTextureImageBuilder_vtbl`
```
struct /*VFT*/ OverworldLightTextureImageBuilder_vtbl
{
  void (__fastcall *~BaseLightTextureImageBuilder)(BaseLightTextureImageBuilder *this);
  void (__fastcall *init)(BaseLightTextureImageBuilder *this, Dimension *);
  bool (__fastcall *buildImage)(BaseLightTextureImageBuilder *this, const BaseLightData *, mce::Image *, unsigned int, float, float, bool);
  void (__fastcall *getModifiedBlockBrightnessColor)(BaseLightTextureImageBuilder *this, const BlockPos *, const Block *, const Brightness *, BrightnessPair *);
  std::unique_ptr<BaseLightData> *(__fastcall *createBaseLightTextureData)(BaseLightTextureImageBuilder *this, std::unique_ptr<BaseLightData> *result, IClientInstance *, const BaseLightData *);
};

```

### `OcelotAttackDefinition`
```
struct __cppobj OcelotAttackDefinition : BaseGoalDefinition
{
  float mCooldownTime;
  float mMaxRotationX;
  float mMaxHeadRotationY;
  float mMaxDistance;
  float mMaxSneakRange;
  float mMaxSprintRange;
  float mReachMultiplier;
  float mSneakSpeedModifier;
  float mSprintSpeedModifier;
  float mWalkSpeedModifier;
};

```

### `OcelotAttackDefinition_vtbl`
```
struct /*VFT*/ OcelotAttackDefinition_vtbl
{
  void (__fastcall *~BaseGoalDefinition)(BaseGoalDefinition *this);
  bool (__fastcall *validateMobType)(BaseGoalDefinition *this, Mob *);
  bool (__fastcall *validate)(BaseGoalDefinition *this, Mob *);
};

```

### `OcelotAttackGoal`
```
struct __cppobj __declspec(align(8)) OcelotAttackGoal : Goal
{
  Mob *mMob;
  int mAttackTicks;
  int mCooldownTicks;
  float mMaxRotationX;
  float mMaxHeadRotationY;
  float mMaxDistance;
  float mMaxSneakRange;
  float mMaxSprintRange;
  float mReachMultiplier;
  float mSneakSpeedModifier;
  float mSprintSpeedModifier;
  float mWalkSpeedModifier;
};

```

### `OcelotAttackGoal_vtbl`
```
struct /*VFT*/ OcelotAttackGoal_vtbl
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

### `OcelotSitOnBlockGoal`
```
struct __cppobj OcelotSitOnBlockGoal : BaseMoveToBlockGoal
{
  Mob *mMob;
};

```

### `OcelotSitOnBlockGoal_vtbl`
```
struct /*VFT*/ OcelotSitOnBlockGoal_vtbl
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

### `OpenDoorGoal`
```
struct __cppobj OpenDoorGoal : DoorInteractGoal
{
  bool mCloseDoor;
  int mForgetTime;
  Mob *mMob;
};

```

### `OpenDoorGoal_vtbl`
```
struct /*VFT*/ OpenDoorGoal_vtbl
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

### `OwnerHurtByTargetGoal`
```
struct __cppobj OwnerHurtByTargetGoal : TargetGoal
{
  TempEPtr<Mob> mOwnerHurtBy;
  Mob *mMob;
};

```

### `OwnerHurtByTargetGoal_vtbl`
```
struct /*VFT*/ OwnerHurtByTargetGoal_vtbl
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

### `OwnerHurtTargetGoal`
```
struct __cppobj __declspec(align(8)) OwnerHurtTargetGoal : TargetGoal
{
  TempEPtr<Mob> mLastOwnerHurt;
  Mob *mMob;
  int mTimestamp;
};

```

### `OwnerHurtTargetGoal_vtbl`
```
struct /*VFT*/ OwnerHurtTargetGoal_vtbl
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

### `OceanMonumentStart`
```
struct __cppobj __declspec(align(8)) OceanMonumentStart : StructureStart
{
  bool isCreated;
};

```

### `OceanMonumentStart_vtbl`
```
struct /*VFT*/ OceanMonumentStart_vtbl
{
  void (__fastcall *~StructureStart)(StructureStart *this);
  bool (__fastcall *postProcess)(StructureStart *this, BlockSource *, Random *, const BoundingBox *);
  bool (__fastcall *isValid)(StructureStart *this);
  StructureFeatureType (__fastcall *getType)(StructureStart *this);
};

```

### `OceanRuinStart`
```
struct __cppobj __declspec(align(8)) OceanRuinStart : StructureStart
{
  OceanRuinConfiguration mConfig;
};

```

### `OceanRuinStart_vtbl`
```
struct /*VFT*/ OceanRuinStart_vtbl
{
  void (__fastcall *~StructureStart)(StructureStart *this);
  bool (__fastcall *postProcess)(StructureStart *this, BlockSource *, Random *, const BoundingBox *);
  bool (__fastcall *isValid)(StructureStart *this);
  StructureFeatureType (__fastcall *getType)(StructureStart *this);
};

```

### `OverworldGenerator::ThreadData`
```
struct __cppobj __declspec(align(8)) OverworldGenerator::ThreadData
{
  std::array<float,1024> buffer;
  std::array<float,256> depthBuffer;
  std::array<float,256> dataBuffer;
  std::array<Block const *,32768> blockBuffer;
  float *fi;
  float *fis;
  Random random;
};

```

### `OceanMonumentFeature`
```
struct __cppobj OceanMonumentFeature : StructureFeature
{
  int mMonumentSpacing;
  int mMinMonumentSeparation;
  std::vector<int> allowedBiomes;
  std::vector<int> allowedSpawnBiomes;
};

```

### `OceanMonumentFeature_vtbl`
```
struct /*VFT*/ OceanMonumentFeature_vtbl
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

### `OverworldGenerator`
```
struct __cppobj OverworldGenerator : ChunkSource, WorldGenerator
{
  const bool legacyDevice;
  BeardKernel mBeardKernel;
  std::unique_ptr<PerlinNoise> minLimitPerlinNoise;
  std::unique_ptr<PerlinNoise> maxLimitPerlinNoise;
  std::unique_ptr<PerlinNoise> mainPerlinNoise;
  std::unique_ptr<PerlinSimplexNoise> surfaceNoise;
  std::unique_ptr<PerlinNoise> scaleNoise;
  std::unique_ptr<PerlinNoise> depthNoise;
  std::unique_ptr<PerlinNoise> forestNoise;
  std::unique_ptr<PerlinSimplexNoise> mMaterialAdjNoise;
  float biomeWeights[25];
  __declspec(align(8)) Bedrock::Threading::InstancedThreadLocal<OverworldGenerator::ThreadData,std::allocator<OverworldGenerator::ThreadData> > generatorHelpersPool;
  VillageFeature villageFeature;
  StrongholdFeature strongholdFeature;
  RandomScatteredLargeFeature scatteredFeature;
  MineshaftFeature mineshaftFeature;
  MonsterRoomFeature monsterRoomFeature;
  OceanMonumentFeature oceanMonumentFeature;
  OceanRuinFeature oceanRuinFeature;
  WoodlandMansionFeature woodlandMansionFeature;
  ShipwreckFeature shipwreckFeature;
  RuinedPortalFeature ruinedPortalFeature;
  BuriedTreasureFeature buriedChestFeature;
  LargeCaveFeature caveFeature;
  CanyonFeature canyonFeature;
  UnderwaterLargeCaveFeature underwaterCaveFeature;
  UnderwaterCanyonFeature underwaterCanyonFeature;
  PillagerOutpostFeature pillagerOutpostFeature;
  std::shared_ptr<Layer<Biome *> const > mBlockResolutionLayer;
  std::shared_ptr<Layer<Biome *> const > m4x4ResolutionLayer;
  std::shared_ptr<BiomeSourceGetBiomeCache> mBiomeSourceCache;
  const Biome *mBiomeOverride;
  std::shared_mutex mTryGetHeightMutex;
  std::unordered_map<BlockPos,int> mHeightCache;
};

```

### `OceanRuinFeature`
```
struct __cppobj OceanRuinFeature : StructureFeature
{
  int mRuinSpacing;
  int mMinRuinSeparation;
  std::vector<int> allowedBiomes;
  OverworldGenerator *mLevelSource;
  OceanMonumentFeature *mMonument;
};

```

### `OceanRuinFeature_vtbl`
```
struct /*VFT*/ OceanRuinFeature_vtbl
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

### `OverworldGenerator_vtbl`
```
struct /*VFT*/ OverworldGenerator_vtbl
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

### `OverworldDimension`
```
struct __cppobj OverworldDimension : Dimension
{
};

```

### `OverworldBrightnessRamp`
```
struct __cppobj OverworldBrightnessRamp : DimensionBrightnessRamp
{
};

```

### `OverworldBrightnessRamp_vtbl`
```
struct /*VFT*/ OverworldBrightnessRamp_vtbl
{
  void (__fastcall *~DimensionBrightnessRamp)(DimensionBrightnessRamp *this);
  void (__fastcall *buildBrightnessRamp)(DimensionBrightnessRamp *this);
  float (__fastcall *getBaseAmbientValue)(DimensionBrightnessRamp *this);
};

```

### `OceanMonumentPiece`
```
struct __cppobj OceanMonumentPiece : StructurePiece
{
  bool mDoFill;
  std::shared_ptr<RoomDefinition> mRoomDefinition;
};

```

### `OceanMonumentPiece_vtbl`
```
struct /*VFT*/ OceanMonumentPiece_vtbl
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

### `OceanMonumentEntryRoom`
```
struct __cppobj OceanMonumentEntryRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentEntryRoom_vtbl`
```
struct /*VFT*/ OceanMonumentEntryRoom_vtbl
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

### `OceanMonumentSimpleRoom`
```
struct __cppobj __declspec(align(8)) OceanMonumentSimpleRoom : OceanMonumentPiece
{
  int mMainDesign;
};

```

### `OceanMonumentSimpleRoom_vtbl`
```
struct /*VFT*/ OceanMonumentSimpleRoom_vtbl
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

### `OceanMonumentSimpleTopRoom`
```
struct __cppobj OceanMonumentSimpleTopRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentSimpleTopRoom_vtbl`
```
struct /*VFT*/ OceanMonumentSimpleTopRoom_vtbl
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

### `OceanMonumentDoubleYRoom`
```
struct __cppobj OceanMonumentDoubleYRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleYRoom_vtbl`
```
struct /*VFT*/ OceanMonumentDoubleYRoom_vtbl
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

### `OceanMonumentDoubleXRoom`
```
struct __cppobj OceanMonumentDoubleXRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleXRoom_vtbl`
```
struct /*VFT*/ OceanMonumentDoubleXRoom_vtbl
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

### `OceanMonumentDoubleZRoom`
```
struct __cppobj OceanMonumentDoubleZRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleZRoom_vtbl`
```
struct /*VFT*/ OceanMonumentDoubleZRoom_vtbl
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

### `OceanMonumentDoubleXYRoom`
```
struct __cppobj OceanMonumentDoubleXYRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleXYRoom_vtbl`
```
struct /*VFT*/ OceanMonumentDoubleXYRoom_vtbl
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

### `OceanMonumentDoubleYZRoom`
```
struct __cppobj OceanMonumentDoubleYZRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentDoubleYZRoom_vtbl`
```
struct /*VFT*/ OceanMonumentDoubleYZRoom_vtbl
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

### `OceanMonumentCoreRoom`
```
struct __cppobj OceanMonumentCoreRoom : OceanMonumentPiece
{
};

```

### `OceanMonumentCoreRoom_vtbl`
```
struct /*VFT*/ OceanMonumentCoreRoom_vtbl
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

### `OceanMonumentWingRoom`
```
struct __cppobj __declspec(align(4)) OceanMonumentWingRoom : OceanMonumentPiece
{
  int mMainDesign;
  bool mIsRightWing;
};

```

### `OceanMonumentWingRoom_vtbl`
```
struct /*VFT*/ OceanMonumentWingRoom_vtbl
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

### `OceanMonumentPenthouse`
```
struct __cppobj OceanMonumentPenthouse : OceanMonumentPiece
{
};

```

### `OceanMonumentPenthouse_vtbl`
```
struct /*VFT*/ OceanMonumentPenthouse_vtbl
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

### `OceanRuinPieces`
```
struct __cppobj OceanRuinPieces
{
};

```

### `OceanRuinPieces::OceanRuinPiece`
```
struct __cppobj OceanRuinPieces::OceanRuinPiece : TemplateStructurePiece
{
  StructureManager *mStructureManager;
  std::string mTemplateName;
  OceanTempCategory mBiomeType;
  float mIntegrity;
  bool mIsLarge;
  Rotation mRotation;
  BlockPos mPosition;
};

```

### `OceanRuinPieces::OceanRuinPiece_vtbl`
```
struct /*VFT*/ OceanRuinPieces::OceanRuinPiece_vtbl
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
  void (__fastcall *_handleDataMarker)(TemplateStructurePiece *this, const std::string *, const BlockPos *, BlockSource *, Random *, const BoundingBox *);
};

```

### `Oobject`
```
struct __declspec(align(8)) Oobject
{
  __int64 ob_refcnt;
  _typeobject *ob_type;
  char *buf;
  __int64 pos;
  __int64 string_size;
  __int64 buf_size;
  int softspace;
};

```

### `Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>::()::__l2::<lambda_d80c656ec8d59dbc8c64dfb75c527a17>`
```
struct __cppobj Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>::()::__l2::<lambda_d80c656ec8d59dbc8c64dfb75c527a17>
{
  std::map<std::string,std::string> *propertyMap;
  VRHUDPosition *newValue;
  bool *oldValueFound;
};

```

### `Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>`
```
struct __cppobj Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>
{
  Options *const __this;
  std::map<std::string,std::string> *propertyMap;
};

```

### `Options::_loadSpecialOptions::__l2::<lambda_5f5d8b8987f054e6094d54779a8bba1c>`
```
struct __cppobj Options::_loadSpecialOptions::__l2::<lambda_5f5d8b8987f054e6094d54779a8bba1c>
{
  Options *const __this;
  std::map<std::string,std::string> *propertyMap;
};

```

### `Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>::()::__l2::<lambda_e1c73b97ad6c18a48e39f5468b8a33d5>`
```
struct __cppobj Options::_loadSpecialOptions::__l2::<lambda_7bb255bdacde2a2b702d5f80ab936b7a>::()::__l2::<lambda_e1c73b97ad6c18a48e39f5468b8a33d5>
{
  std::map<std::string,std::string> *propertyMap;
  VRStickyMining *newValue;
  bool *oldValueFound;
};

```

### `Options::_saveInputMapping::__l2::<lambda_065485d2bbf015adaf440567a3df3aed>`
```
struct __cppobj Options::_saveInputMapping::__l2::<lambda_065485d2bbf015adaf440567a3df3aed>
{
  std::vector<std::pair<std::string,std::string >> *settingsVec;
};

```

### `Options::_registerOptions::__l2::<lambda_e2061f6fc1dbebba1e5f7aa7386008ab>`
```
struct __cppobj Options::_registerOptions::__l2::<lambda_e2061f6fc1dbebba1e5f7aa7386008ab>
{
};

```

### `OwnedDurablesPagingCache::_performBatchedSearch::__l2::<lambda_0c82040d1ea396f7bd80ce9a5fa8db51>`
```
struct __cppobj OwnedDurablesPagingCache::_performBatchedSearch::__l2::<lambda_0c82040d1ea396f7bd80ce9a5fa8db51>
{
};

```

### `OnUseOnItemComponent::useOn::__l2::<lambda_617c656cd3c75210e2a62aa9582f3625>::()::__l2::Literal`
```
struct __cppobj OnUseOnItemComponent::useOn::__l2::<lambda_617c656cd3c75210e2a62aa9582f3625>::()::__l2::Literal
{
};

```

### `OnUseOnItemComponent::useOn::__l2::<lambda_617c656cd3c75210e2a62aa9582f3625>`
```
struct __cppobj OnUseOnItemComponent::useOn::__l2::<lambda_617c656cd3c75210e2a62aa9582f3625>
{
};

```

### `Ocelot::updateEntitySpecificMolangVariables::__l2::<lambda_d37c0c731b3f334c5f417233dbc1aa03>::()::__l2::Literal`
```
struct __cppobj Ocelot::updateEntitySpecificMolangVariables::__l2::<lambda_d37c0c731b3f334c5f417233dbc1aa03>::()::__l2::Literal
{
};

```

### `Ocelot::updateEntitySpecificMolangVariables::__l2::<lambda_d37c0c731b3f334c5f417233dbc1aa03>`
```
struct __cppobj Ocelot::updateEntitySpecificMolangVariables::__l2::<lambda_d37c0c731b3f334c5f417233dbc1aa03>
{
};

```

### `OverworldGenerator::_makeLayers::__l2::<lambda_00d2029390727aff6abfa69bf88b314f>`
```
struct __cppobj OverworldGenerator::_makeLayers::__l2::<lambda_00d2029390727aff6abfa69bf88b314f>
{
  const BiomeRegistry *biomeRegistry;
  const AutomaticID<Dimension,int> *id;
};

```

### `Ocelot_vtbl`
```
struct /*VFT*/ Ocelot_vtbl
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

### `OverworldDimension_vtbl`
```
struct /*VFT*/ OverworldDimension_vtbl
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

