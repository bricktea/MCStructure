# Z
### `z_stream`
Offset | Type | Name
-|-|-|-
0 | (8) `Bytef *` | next_in
8 | (4) `uInt` | avail_in
16 | (8) `uLong` | total_in
24 | (8) `Bytef *` | next_out
32 | (4) `uInt` | avail_out
40 | (8) `uLong` | total_out
48 | (8) `char *` | msg
56 | (8) `internal_state *` | state
64 | (8) `alloc_func` | zalloc
72 | (8) `free_func` | zfree
80 | (8) `voidpf` | opaque
88 | (4) `int` | data_type
96 | (8) `uLong` | adler
104 | (8) `uLong` | reserved


### `ZlibFileAccessWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<zlib_filefunc64_32_def_s>` | mZipAPI
8 | (8) `IFileAccess *` | mFileAccess


### `zip_fileinfo`
Offset | Type | Name
-|-|-|-
0 | (24) `tm_zip` | tmz_date
24 | (8) `uLong` | dosDate
32 | (8) `uLong` | internal_fa
40 | (8) `uLong` | external_fa


### `zlib_filefunc64_32_def`
Offset | Type | Name
-|-|-|-
0 | (64) `zlib_filefunc64_def` | zfile_func64
64 | (8) `open_file_func` | zopen32_file
72 | (8) `tell_file_func` | ztell32_file
80 | (8) `seek_file_func` | zseek32_file


### `zlib_filefunc64_def`
Offset | Type | Name
-|-|-|-
0 | (8) `open64_file_func` | zopen64_file
8 | (8) `read_file_func` | zread_file
16 | (8) `write_file_func` | zwrite_file
24 | (8) `tell64_file_func` | ztell64_file
32 | (8) `seek64_file_func` | zseek64_file
40 | (8) `close_file_func` | zclose_file
48 | (8) `testerror_file_func` | zerror_file
56 | (8) `voidpf` | opaque


### `zip64_internal`
Offset | Type | Name
-|-|-|-
0 | (88) `zlib_filefunc64_32_def` | z_filefunc
88 | (8) `voidpf` | filestream
96 | (16) `linkedlist_data` | central_dir
112 | (4) `int` | in_opened_file_inzip
120 | (65760) `curfile64_info` | ci
65880 | (8) `ZPOS64_T` | begin_pos
65888 | (8) `ZPOS64_T` | add_position_when_writting_offset
65896 | (8) `ZPOS64_T` | number_entry
65904 | (8) `char *` | globalcomment


### `z_stream_s`
Offset | Type | Name
-|-|-|-
0 | (8) `Bytef *` | next_in
8 | (4) `uInt` | avail_in
16 | (8) `uLong` | total_in
24 | (8) `Bytef *` | next_out
32 | (4) `uInt` | avail_out
40 | (8) `uLong` | total_out
48 | (8) `char *` | msg
56 | (8) `internal_state *` | state
64 | (8) `alloc_func` | zalloc
72 | (8) `free_func` | zfree
80 | (8) `voidpf` | opaque
88 | (4) `int` | data_type
96 | (8) `uLong` | adler
104 | (8) `uLong` | reserved


### `ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2xFuzzy> : UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>:328
{
  LayerZooms::Zoom2xFuzzy mZoom;
};

```

### `ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2x>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2x> : UnaryLayer<LayerValues::Terrain,LayerValues::Terrain>:328
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x> : UnaryLayer<LayerValues::PreBiome,LayerValues::PreBiome>:328
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<int,LayerZooms::Zoom2x>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<int,LayerZooms::Zoom2x> : UnaryLayer<int,int>:328
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<Biome *,LayerZooms::Zoom2x> : UnaryLayer<Biome *,Biome *>:328
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<BiomeTemperatureCategory,LayerZooms::Zoom2x>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<BiomeTemperatureCategory,LayerZooms::Zoom2x> : UnaryLayer<BiomeTemperatureCategory,BiomeTemperatureCategory>:328
{
  LayerZooms::Zoom2x mZoom;
};

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>`
```
struct __cppobj __attribute__((aligned(8))) ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi> : UnaryLayer<Biome *,Biome *>:328
{
  LayerZooms::Zoom4xVoronoi mZoom;
};

```

### `ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain> ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2xFuzzy>::LayerData;

```

### `ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2x>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::Terrain,LayerValues::Terrain> ZoomLayerCommon<LayerValues::Terrain,LayerZooms::Zoom2x>::LayerData;

```

### `ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>::LayerData`
```
typedef LayerDetails::WorkingData<LayerValues::PreBiome,LayerValues::PreBiome> ZoomLayerCommon<LayerValues::PreBiome,LayerZooms::Zoom2x>::LayerData;

```

### `ZoomLayerCommon<int,LayerZooms::Zoom2x>::LayerData`
```
typedef LayerDetails::WorkingData<int,int> ZoomLayerCommon<int,LayerZooms::Zoom2x>::LayerData;

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> ZoomLayerCommon<Biome *,LayerZooms::Zoom2x>::LayerData;

```

### `ZoomLayerCommon<BiomeTemperatureCategory,LayerZooms::Zoom2x>::LayerData`
```
typedef LayerDetails::WorkingData<BiomeTemperatureCategory,BiomeTemperatureCategory> ZoomLayerCommon<BiomeTemperatureCategory,LayerZooms::Zoom2x>::LayerData;

```

### `ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>::LayerData`
```
typedef LayerDetails::WorkingData<Biome *,Biome *> ZoomLayerCommon<Biome *,LayerZooms::Zoom4xVoronoi>::LayerData;

```

### `Zombie`
```
struct __cppobj Zombie : HumanoidMonster
{
};

```

### `ZombieVillager`
```
struct __cppobj __attribute__((aligned(4))) ZombieVillager : Zombie
{
  int villagerConversionTime;
  bool mSpawnedFromVillage;
};

```

### `ZipPackAccessStrategyOwningFileAcccess`
```
struct __cppobj ZipPackAccessStrategyOwningFileAcccess : ZipPackAccessStrategy
{
  std::shared_ptr<IFileAccess> mFileAccessShared;
};

```

### `ZipPackAccessStrategy`
```
struct __cppobj ZipPackAccessStrategy : PackAccessStrategy
{
  std::string mPackName;
  ResourceLocation mArchiveLocation;
  Core::HeapPathBuffer mSubPath;
  IFileAccess *mFileAccess;
  bool mIsTrusted;
  bool mIsWritable;
  std::vector<std::pair<Core::PathBuffer<std::string >,std::string >> mQueueWriteContent;
  std::vector<Core::PathBuffer<std::string >> mQueueDeleteContent;
};

```

### `zlib_filefunc64_32_def_s`
```
struct zlib_filefunc64_32_def_s
{
  zlib_filefunc64_def zfile_func64;
  open_file_func zopen32_file;
  tell_file_func ztell32_file;
  seek_file_func zseek32_file;
};

```

### `zlib_filefunc64_def_s`
```
struct zlib_filefunc64_def_s
{
  open64_file_func zopen64_file;
  read_file_func zread_file;
  write_file_func zwrite_file;
  tell64_file_func ztell64_file;
  seek64_file_func zseek64_file;
  close_file_func zclose_file;
  testerror_file_func zerror_file;
  voidpf opaque;
};

```

### `zlib_filefunc_def`
```
typedef zlib_filefunc_def_s zlib_filefunc_def;

```

### `zlib_filefunc_def_s`
```
struct zlib_filefunc_def_s
{
  open_file_func zopen_file;
  read_file_func zread_file;
  write_file_func zwrite_file;
  tell_file_func ztell_file;
  seek_file_func zseek_file;
  close_file_func zclose_file;
  testerror_file_func zerror_file;
  voidpf opaque;
};

```

