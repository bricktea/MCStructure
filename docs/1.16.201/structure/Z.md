# Z
### `z_stream_s`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | next_in
8 | (4) `unsigned int` | avail_in
12 | (4) `unsigned int` | total_in
16 | (8) `unsigned __int8 *` | next_out
24 | (4) `unsigned int` | avail_out
28 | (4) `unsigned int` | total_out
32 | (8) `char *` | msg
40 | (8) `internal_state *` | state
48 | (8) `void *(__fastcall *)(void *, unsigned int, unsigned int)` | zalloc
56 | (8) `void (__fastcall *)(void *, void *)` | zfree
64 | (8) `void *` | opaque
72 | (4) `int` | data_type
76 | (4) `unsigned int` | adler
80 | (4) `unsigned int` | reserved


### `zlib_filefunc64_32_def_s`
Offset | Type | Name
-|-|-|-
0 | (64) `zlib_filefunc64_def_s` | zfile_func64
64 | (8) `void *(__fastcall *)(void *, const char *, int)` | zopen32_file
72 | (8) `int (__fastcall *)(void *, void *)` | ztell32_file
80 | (8) `int (__fastcall *)(void *, void *, unsigned int, int)` | zseek32_file


### `zlib_filefunc64_def_s`
Offset | Type | Name
-|-|-|-
0 | (8) `void *(__fastcall *)(void *, const void *, int)` | zopen64_file
8 | (8) `unsigned int (__fastcall *)(void *, void *, void *, unsigned int)` | zread_file
16 | (8) `unsigned int (__fastcall *)(void *, void *, const void *, unsigned int)` | zwrite_file
24 | (8) `unsigned __int64 (__fastcall *)(void *, void *)` | ztell64_file
32 | (8) `int (__fastcall *)(void *, void *, unsigned __int64, int)` | zseek64_file
40 | (8) `int (__fastcall *)(void *, void *)` | zclose_file
48 | (8) `int (__fastcall *)(void *, void *)` | zerror_file
56 | (8) `void *` | opaque


### `ZlibFileAccessWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<zlib_filefunc64_32_def_s>` | mZipAPI
8 | (8) `IFileAccess *` | mFileAccess


### `zip_fileinfo`
Offset | Type | Name
-|-|-|-
0 | (24) `tm_zip_s` | tmz_date
24 | (4) `unsigned int` | dosDate
28 | (4) `unsigned int` | internal_fa
32 | (4) `unsigned int` | external_fa


### `ZombieModel`
```
struct __cppobj ZombieModel : HumanoidModel
{
  mce::MaterialPtr mDefaultMaterial;
};

```

### `ZombieModel_vtbl`
```
struct /*VFT*/ ZombieModel_vtbl
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

### `ZipPackAccessStrategy`
```
struct __cppobj ZipPackAccessStrategy : PackAccessStrategy
{
  std::string mPackName;
  ResourceLocation mArchiveLocation;
  Core::PathBuffer<std::string > mSubPath;
  IFileAccess *mFileAccess;
  bool mIsTrusted;
  bool mIsWritable;
  std::vector<std::pair<Core::PathBuffer<std::string >,std::string >> mQueueWriteContent;
  std::vector<Core::PathBuffer<std::string >> mQueueDeleteContent;
  __int64 mLastModified;
  const IContentKeyProvider *mKeyProvider;
};

```

### `ZipPackAccessStrategy_vtbl`
```
struct /*VFT*/ ZipPackAccessStrategy_vtbl
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

### `ZipPackAccessStrategyOwningFileAcccess`
```
struct __cppobj ZipPackAccessStrategyOwningFileAcccess : ZipPackAccessStrategy
{
  std::shared_ptr<IFileAccess> mFileAccessShared;
};

```

### `ZipPackAccessStrategyOwningFileAcccess_vtbl`
```
struct /*VFT*/ ZipPackAccessStrategyOwningFileAcccess_vtbl
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

### `Zombie`
```
struct __cppobj Zombie : HumanoidMonster
{
};

```

### `ZombieVillager`
```
struct __cppobj __declspec(align(4)) ZombieVillager : Zombie
{
  int villagerConversionTime;
  bool mSpawnedFromVillage;
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi> : MixerLayer<Biome *,Biome *>
{
  LayerZooms::Zoom4xVoronoi mZoom;
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<Biome *> *(__fastcall *_allocateAndFill)(Layer<Biome *> *this, LayerDetails::TransferData<Biome *> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<Biome *,Biome *> *this, LayerDetails::WorkingData<Biome *,Biome *> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<Biome *,Biome *> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2xFuzzy> : MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain>
{
  LayerZooms::Zoom2xFuzzy mZoom;
};

```

### `ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<enum LayerValues::Terrain> *(__fastcall *_allocateAndFill)(Layer<enum LayerValues::Terrain> *this, LayerDetails::TransferData<enum LayerValues::Terrain> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain> *this, LayerDetails::WorkingData<enum LayerValues::Terrain,enum LayerValues::Terrain> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2x>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2x> : MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain>
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2x>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<enum LayerValues::Terrain,LayerZooms::Zoom2x>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<enum LayerValues::Terrain> *(__fastcall *_allocateAndFill)(Layer<enum LayerValues::Terrain> *this, LayerDetails::TransferData<enum LayerValues::Terrain> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain> *this, LayerDetails::WorkingData<enum LayerValues::Terrain,enum LayerValues::Terrain> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<enum LayerValues::Terrain,enum LayerValues::Terrain> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x> : MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome>
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<LayerValues::PreBiome> *(__fastcall *_allocateAndFill)(Layer<LayerValues::PreBiome> *this, LayerDetails::TransferData<LayerValues::PreBiome> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> *this, LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<LayerValues::PreBiome,LayerValues::PreBiome> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<Biome *,LayerZooms::Zoom2x> : MixerLayer<Biome *,Biome *>
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<Biome *> *(__fastcall *_allocateAndFill)(Layer<Biome *> *this, LayerDetails::TransferData<Biome *> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<Biome *,Biome *> *this, LayerDetails::WorkingData<Biome *,Biome *> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<Biome *,Biome *> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<int,LayerZooms::Zoom2x>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<int,LayerZooms::Zoom2x> : MixerLayer<int,int>
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<int,LayerZooms::Zoom2x>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<int,LayerZooms::Zoom2x>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<int> *(__fastcall *_allocateAndFill)(Layer<int> *this, LayerDetails::TransferData<int> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<int,int> *this, LayerDetails::WorkingData<int,int> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<int,int> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `ZoomLayerCommon<enum BiomeTemperatureCategory,LayerZooms::Zoom2x>`
```
struct __cppobj __declspec(align(8)) ZoomLayerCommon<enum BiomeTemperatureCategory,LayerZooms::Zoom2x> : MixerLayer<enum BiomeTemperatureCategory,enum BiomeTemperatureCategory>
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<enum BiomeTemperatureCategory,LayerZooms::Zoom2x>_vtbl`
```
struct /*VFT*/ ZoomLayerCommon<enum BiomeTemperatureCategory,LayerZooms::Zoom2x>_vtbl
{
  void (__fastcall *~LayerBase)(LayerDetails::LayerBase *this);
  void (__fastcall *init)(LayerDetails::LayerBase *this, __int64);
  LayerDetails::TransferData<enum BiomeTemperatureCategory> *(__fastcall *_allocateAndFill)(Layer<enum BiomeTemperatureCategory> *this, LayerDetails::TransferData<enum BiomeTemperatureCategory> *result, unsigned __int64, int, int, unsigned int, unsigned int);
  void (__fastcall *_fillArea)(MixerLayer<enum BiomeTemperatureCategory,enum BiomeTemperatureCategory> *this, LayerDetails::WorkingData<enum BiomeTemperatureCategory,enum BiomeTemperatureCategory> *, int, int, int, int, int);
  std::tuple<int,int,unsigned int,unsigned int> *(__fastcall *_getAreaRead)(MixerLayer<enum BiomeTemperatureCategory,enum BiomeTemperatureCategory> *this, std::tuple<int,int,unsigned int,unsigned int> *result, int, int, unsigned int, unsigned int);
};

```

### `zlib_filefunc_def_s`
```
struct zlib_filefunc_def_s
{
  void *(__fastcall *zopen_file)(void *, const char *, int);
  unsigned int (__fastcall *zread_file)(void *, void *, void *, unsigned int);
  unsigned int (__fastcall *zwrite_file)(void *, void *, const void *, unsigned int);
  int (__fastcall *ztell_file)(void *, void *);
  int (__fastcall *zseek_file)(void *, void *, unsigned int, int);
  int (__fastcall *zclose_file)(void *, void *);
  int (__fastcall *zerror_file)(void *, void *);
  void *opaque;
};

```

### `zip64_internal`
```
struct zip64_internal
{
  zlib_filefunc64_32_def_s z_filefunc;
  void *filestream;
  linkedlist_data_s central_dir;
  int in_opened_file_inzip;
  curfile64_info ci;
  unsigned __int64 begin_pos;
  unsigned __int64 add_position_when_writting_offset;
  unsigned __int64 number_entry;
  char *globalcomment;
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_4e6540f9300ff5f13a4b0e6d8886056d>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_4e6540f9300ff5f13a4b0e6d8886056d>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_5b91378e54ed645a4a53fb6a63063e0e>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_5b91378e54ed645a4a53fb6a63063e0e>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_7c1d8f960511cf37c16fa19eb0eb7786>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_7c1d8f960511cf37c16fa19eb0eb7786>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_820b5f8f4afd36dc7d61d48f18fa7f36>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_820b5f8f4afd36dc7d61d48f18fa7f36>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_869fc17f49cf97ef0f6604be49825694>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_869fc17f49cf97ef0f6604be49825694>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_982c3505019204722080b3746c05d493>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_982c3505019204722080b3746c05d493>
{
};

```

### `ZlibFileAccessWrapper::{ctor}::__l5::<lambda_aab1f6d42a2e2665b9648455aede595f>`
```
struct __cppobj ZlibFileAccessWrapper::{ctor}::__l5::<lambda_aab1f6d42a2e2665b9648455aede595f>
{
};

```

### `Zombie_vtbl`
```
struct /*VFT*/ Zombie_vtbl
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

### `ZombieVillager_vtbl`
```
struct /*VFT*/ ZombieVillager_vtbl
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

