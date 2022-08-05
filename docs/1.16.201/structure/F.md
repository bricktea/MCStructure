# F
### `FeatureToggles::_setupDependencies::__l2::<lambda_1633bc3e3e0c6c838cb408cbbb547288>`
Offset | Type | Name
-|-|-|-


### `FindTargetNode::_findTarget::__l2::<lambda_97f0b4bbc84cd3d862b3eb5dbefdcf18>`
Offset | Type | Name
-|-|-|-


### `frame_t`
Offset | Type | Name
-|-|-|-
0 | (8) `_object *` | filename
8 | (4) `int` | lineno


### `FloatRange`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | rangeMin
4 | (4) `float` | rangeMax


### `fsm_struct`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | vocab_size
2 | (2) `__int16` | num_transitions
8 | (8) `const unsigned __int16 *` | transitions


### `FT_Service_PropertiesRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_ModuleRec_ *, const char *, const void *, unsigned __int8)` | set_property
8 | (8) `int (__fastcall *)(FT_ModuleRec_ *, const char *, void *)` | get_property


### `FT_ServiceDescRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | serv_id
8 | (8) `const void *` | serv_data


### `ft_raccess_guess_rec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_LibraryRec_ *, FT_StreamRec_ *, char *, char **, int *)` | func
8 | (4) `FT_RFork_Rule_` | type


### `FT_Palette_Data_`
Offset | Type | Name
-|-|-|-
0 | (2) `unsigned __int16` | num_palettes
8 | (8) `const unsigned __int16 *` | palette_name_ids
16 | (8) `const unsigned __int16 *` | palette_flags
24 | (2) `unsigned __int16` | num_palette_entries
32 | (8) `const unsigned __int16 *` | palette_entry_name_ids


### `FT_Outline_`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | n_contours
2 | (2) `__int16` | n_points
8 | (8) `FT_Vector_ *` | points
16 | (8) `char *` | tags
24 | (8) `__int16 *` | contours
32 | (4) `int` | flags


### `FT_Outline_Funcs_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(const FT_Vector_ *, void *)` | move_to
8 | (8) `int (__fastcall *)(const FT_Vector_ *, void *)` | line_to
16 | (8) `int (__fastcall *)(const FT_Vector_ *, const FT_Vector_ *, void *)` | conic_to
24 | (8) `int (__fastcall *)(const FT_Vector_ *, const FT_Vector_ *, const FT_Vector_ *, void *)` | cubic_to
32 | (4) `int` | shift
36 | (4) `int` | delta


### `FT_Bitmap_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | rows
4 | (4) `unsigned int` | width
8 | (4) `int` | pitch
16 | (8) `unsigned __int8 *` | buffer
24 | (2) `unsigned __int16` | num_grays
26 | (1) `unsigned __int8` | pixel_mode
27 | (1) `unsigned __int8` | palette_mode
32 | (8) `void *` | palette


### `FT_Color_`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | blue
1 | (1) `unsigned __int8` | green
2 | (1) `unsigned __int8` | red
3 | (1) `unsigned __int8` | alpha


### `FT_Service_BDFRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, const char **, const char **)` | get_charset_id
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, const char *, BDF_PropertyRec_ *)` | get_property


### `FT_CMap_ClassRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | size
8 | (8) `int (__fastcall *)(FT_CMapRec_ *, void *)` | init
16 | (8) `void (__fastcall *)(FT_CMapRec_ *)` | done
24 | (8) `unsigned int (__fastcall *)(FT_CMapRec_ *, unsigned int)` | char_index
32 | (8) `unsigned int (__fastcall *)(FT_CMapRec_ *, unsigned int *)` | char_next
40 | (8) `unsigned int (__fastcall *)(FT_CMapRec_ *, FT_CMapRec_ *, unsigned int, unsigned int)` | char_var_index
48 | (8) `int (__fastcall *)(FT_CMapRec_ *, unsigned int, unsigned int)` | char_var_default
56 | (8) `unsigned int *(__fastcall *)(FT_CMapRec_ *, FT_MemoryRec_ *)` | variant_list
64 | (8) `unsigned int *(__fastcall *)(FT_CMapRec_ *, FT_MemoryRec_ *, unsigned int)` | charvariant_list
72 | (8) `unsigned int *(__fastcall *)(FT_CMapRec_ *, FT_MemoryRec_ *, unsigned int)` | variantchar_list


### `FTC_MruListClassRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int64` | node_size
8 | (8) `unsigned __int8 (__fastcall *)(FTC_MruNodeRec_ *, void *)` | node_compare
16 | (8) `int (__fastcall *)(FTC_MruNodeRec_ *, void *, void *)` | node_init
24 | (8) `int (__fastcall *)(FTC_MruNodeRec_ *, void *, void *)` | node_reset
32 | (8) `void (__fastcall *)(FTC_MruNodeRec_ *, void *)` | node_done


### `FTC_SFamilyClassRec_`
Offset | Type | Name
-|-|-|-
0 | (40) `FTC_MruListClassRec_` | clazz
40 | (8) `unsigned int (__fastcall *)(FTC_FamilyRec_ *, FTC_ManagerRec_ *)` | family_get_count
48 | (8) `int (__fastcall *)(FTC_FamilyRec_ *, unsigned int, FTC_ManagerRec_ *, FT_FaceRec_ **)` | family_load_glyph


### `FTC_GCacheClassRec_`
Offset | Type | Name
-|-|-|-
0 | (64) `FTC_CacheClassRec_` | clazz
64 | (8) `const FTC_MruListClassRec_ *` | family_class


### `FTC_CacheClassRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FTC_NodeRec_ **, void *, FTC_CacheRec_ *)` | node_new
8 | (8) `unsigned __int64 (__fastcall *)(FTC_NodeRec_ *, FTC_CacheRec_ *)` | node_weight
16 | (8) `unsigned __int8 (__fastcall *)(FTC_NodeRec_ *, void *, FTC_CacheRec_ *, unsigned __int8 *)` | node_compare
24 | (8) `unsigned __int8 (__fastcall *)(FTC_NodeRec_ *, void *, FTC_CacheRec_ *, unsigned __int8 *)` | node_remove_faceid
32 | (8) `void (__fastcall *)(FTC_NodeRec_ *, FTC_CacheRec_ *)` | node_free
40 | (8) `unsigned __int64` | cache_size
48 | (8) `int (__fastcall *)(FTC_CacheRec_ *)` | cache_init
56 | (8) `void (__fastcall *)(FTC_CacheRec_ *)` | cache_done


### `FTC_IFamilyClassRec_`
Offset | Type | Name
-|-|-|-
0 | (40) `FTC_MruListClassRec_` | clazz
40 | (8) `int (__fastcall *)(FTC_FamilyRec_ *, unsigned int, FTC_CacheRec_ *, FT_GlyphRec_ **)` | family_load_glyph


### `FT_Service_GlyphDictRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, void *, unsigned int)` | get_name
8 | (8) `unsigned int (__fastcall *)(FT_FaceRec_ *, const char *)` | name_index


### `FT_Service_CIDRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, const char **, const char **, int *)` | get_ros
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned __int8 *)` | get_is_cid
16 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int *)` | get_cid_from_glyph_index


### `FT_Service_PsFontNameRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *(__fastcall *)(FT_FaceRec_ *)` | get_ps_font_name


### `FT_Service_CFFLoadRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int16 (__fastcall *)(unsigned int)` | get_standard_encoding
8 | (8) `int (__fastcall *)(CFF_FontRec_ *, CFF_SubFontRec_ *, unsigned int, int *)` | load_private_dict
16 | (8) `unsigned __int8 (__fastcall *)(CFF_FDSelectRec_ *, unsigned int)` | fd_select_get
24 | (8) `unsigned __int8 (__fastcall *)(CFF_BlendRec_ *, unsigned int, unsigned int, int *)` | blend_check_vector
32 | (8) `int (__fastcall *)(CFF_BlendRec_ *, unsigned int, unsigned int, int *)` | blend_build_vector


### `FT_Service_TTCMapsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_CharMapRec_ *, TT_CMapInfo_ *)` | get_cmap_info


### `FT_Service_MetricsVariationsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | hadvance_adjust
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | lsb_adjust
16 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | rsb_adjust
24 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | vadvance_adjust
32 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | tsb_adjust
40 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | bsb_adjust
48 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | vorg_adjust
56 | (8) `void (__fastcall *)(FT_FaceRec_ *)` | metrics_adjust


### `FT_Service_MultiMastersRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, FT_Multi_Master_ *)` | get_mm
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | set_mm_design
16 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | set_mm_blend
24 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | get_mm_blend
32 | (8) `int (__fastcall *)(FT_FaceRec_ *, FT_MM_Var_ **)` | get_mm_var
40 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | set_var_design
48 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | get_var_design
56 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int)` | set_instance
64 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | set_mm_weightvector
72 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int *, int *)` | get_mm_weightvector
80 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int *, int **, int **, FT_MM_Var_ **)` | get_var_blend
88 | (8) `void (__fastcall *)(FT_FaceRec_ *)` | done_blend


### `FT_Service_PsInfoRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, PS_FontInfoRec_ *)` | ps_get_font_info
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, PS_FontExtraRec_ *)` | ps_get_font_extra
16 | (8) `int (__fastcall *)(FT_FaceRec_ *)` | ps_has_glyph_names
24 | (8) `int (__fastcall *)(FT_FaceRec_ *, PS_PrivateRec_ *)` | ps_get_font_private
32 | (8) `int (__fastcall *)(FT_FaceRec_ *, PS_Dict_Keys_, unsigned int, void *, int)` | ps_get_font_value


### `FT_Frame_Field_`
Offset | Type | Name
-|-|-|-
0 | (1) `unsigned __int8` | value
1 | (1) `unsigned __int8` | size
2 | (2) `unsigned __int16` | offset


### `FT_Service_PfrMetricsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int *, unsigned int *, int *, int *)` | get_metrics
8 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int, FT_Vector_ *)` | get_kerning
16 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int *)` | get_advance


### `FT_Service_PsCMapsRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int (__fastcall *)(const char *)` | unicode_value
8 | (8) `int (__fastcall *)(FT_MemoryRec_ *, PS_UnicodesRec_ *, unsigned int, const char *(__fastcall *)(void *, unsigned int), void (__fastcall *)(void *, const char *), void *)` | unicodes_init
16 | (8) `unsigned int (__fastcall *)(PS_UnicodesRec_ *, unsigned int)` | unicodes_char_index
24 | (8) `unsigned int (__fastcall *)(PS_UnicodesRec_ *, unsigned int *)` | unicodes_char_next
32 | (8) `const char *(__fastcall *)(unsigned int)` | macintosh_name
40 | (8) `const char *(__fastcall *)(unsigned int)` | adobe_std_strings
48 | (8) `const unsigned __int16 *` | adobe_std_encoding
56 | (8) `const unsigned __int16 *` | adobe_expert_encoding


### `FT_Service_SFNT_TableRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, int, unsigned __int8 *, unsigned int *)` | load_table
8 | (8) `void *(__fastcall *)(FT_FaceRec_ *, FT_Sfnt_Tag_)` | get_table
16 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int *, unsigned int *, unsigned int *)` | table_info


### `FT_Service_TTGlyfRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int *)` | get_location


### `FT_Service_TrueTypeEngineRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `FT_TrueTypeEngineType_` | engine_type


### `FT_Service_KerningRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, int, int, int *)` | get_track


### `FT_Service_WinFntRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `int (__fastcall *)(FT_FaceRec_ *, FT_WinFNT_HeaderRec_ *)` | get_header


### `filedescr`
Offset | Type | Name
-|-|-|-
0 | (8) `char *` | suffix
8 | (8) `char *` | mode
16 | (4) `filetype` | type


### `FogDefinition`
Offset | Type | Name
-|-|-|-
0 | (48) `HashedString` | mIdentifier
48 | (32) `std::optional<FogDistanceSetting>` | mDistanceAirSetting
80 | (32) `std::optional<FogDistanceSetting>` | mDistanceWeatherSetting
112 | (32) `std::optional<FogDistanceSetting>` | mDistanceWaterSetting
144 | (32) `std::optional<FogDistanceSetting>` | mDistanceLavaSetting
176 | (32) `std::optional<FogDistanceSetting>` | mDistanceLavaResistanceSetting
208 | (20) `std::optional<FogVolumetricDensitySetting>` | mVolumeDensityAirSetting
228 | (20) `std::optional<FogVolumetricDensitySetting>` | mVolumeDensityWeatherSetting
248 | (20) `std::optional<FogVolumetricDensitySetting>` | mVolumeDensityWaterSetting
268 | (20) `std::optional<FogVolumetricDensitySetting>` | mVolumeDensityLavaSetting
288 | (20) `std::optional<FogVolumetricDensitySetting>` | mVolumeDensityLavaResistanceSetting
308 | (36) `std::optional<FogVolumetricCoefficientSetting>` | mVolumeCoefficientAirSetting
344 | (36) `std::optional<FogVolumetricCoefficientSetting>` | mVolumeCoefficientWaterSetting
380 | (36) `std::optional<FogVolumetricCoefficientSetting>` | mVolumeCoefficientCloudSetting


### `FogDistanceSetting`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | mColor
16 | (4) `float` | mStart
20 | (4) `float` | mEnd
24 | (4) `_BYTE[4]` | mType


### `FogVolumetricDensitySetting`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mMaxDensity
4 | (4) `float` | mMaxDensityHeight
8 | (4) `float` | mZeroDensityHeight
12 | (1) `bool` | mUniform


### `FogVolumetricCoefficientSetting`
Offset | Type | Name
-|-|-|-
0 | (16) `mce::Color` | mScattering
16 | (16) `mce::Color` | mAbsorption


### `FilterParamDefinition`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterParamType` | mType
4 | (4) `FilterParamRequirement` | mRequirement
8 | (32) `std::string` | mDescription
40 | (48) `FilterInput` | mDefault
88 | (64) `FilterStringMap` | mStringMap
152 | (1) `FilterParamOption` | mParamOption


### `FilterInput`
Offset | Type | Name
-|-|-|-
0 | (4) `FilterParamType` | mType
8 | (32) `std::string` | mString
40 | (4) `int` | mIValue
44 | (4) `float` | mFValue


### `FilterStringMap`
Offset | Type | Name
-|-|-|-
0 | (64) `std::unordered_map<std::string,FilterInputDefinition>` | baseclass_0


### `FT_UnitVector_`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | x
2 | (2) `__int16` | y


### `FT_Driver_ClassRec_`
Offset | Type | Name
-|-|-|-
0 | (56) `FT_Module_Class_` | root
56 | (4) `int` | face_object_size
60 | (4) `int` | size_object_size
64 | (4) `int` | slot_object_size
72 | (8) `int (__fastcall *)(FT_StreamRec_ *, FT_FaceRec_ *, int, int, FT_Parameter_ *)` | init_face
80 | (8) `void (__fastcall *)(FT_FaceRec_ *)` | done_face
88 | (8) `int (__fastcall *)(FT_SizeRec_ *)` | init_size
96 | (8) `void (__fastcall *)(FT_SizeRec_ *)` | done_size
104 | (8) `int (__fastcall *)(FT_GlyphSlotRec_ *)` | init_slot
112 | (8) `void (__fastcall *)(FT_GlyphSlotRec_ *)` | done_slot
120 | (8) `int (__fastcall *)(FT_GlyphSlotRec_ *, FT_SizeRec_ *, unsigned int, int)` | load_glyph
128 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int, FT_Vector_ *)` | get_kerning
136 | (8) `int (__fastcall *)(FT_FaceRec_ *, FT_StreamRec_ *)` | attach_file
144 | (8) `int (__fastcall *)(FT_FaceRec_ *, unsigned int, unsigned int, int, int *)` | get_advances
152 | (8) `int (__fastcall *)(FT_SizeRec_ *, FT_Size_RequestRec_ *)` | request_size
160 | (8) `int (__fastcall *)(FT_SizeRec_ *, unsigned int)` | select_size


### `FT_Module_Class_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | module_flags
4 | (4) `int` | module_size
8 | (8) `const char *` | module_name
16 | (4) `int` | module_version
20 | (4) `int` | module_requires
24 | (8) `const void *` | module_interface
32 | (8) `int (__fastcall *)(FT_ModuleRec_ *)` | module_init
40 | (8) `void (__fastcall *)(FT_ModuleRec_ *)` | module_done
48 | (8) `void *(__fastcall *)(FT_ModuleRec_ *, const char *)` | get_interface


### `FlameOdds`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mChance


### `FontHandle`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<FontRepository>` | mFontRepository
16 | (16) `std::shared_ptr<Font>` | mDefaultFont
32 | (8) `unsigned __int64` | mFontId
40 | (1) `bool` | mIsDummyHandle


### `FT_Renderer_Class_`
Offset | Type | Name
-|-|-|-
0 | (56) `FT_Module_Class_` | root
56 | (4) `FT_Glyph_Format_` | glyph_format
64 | (8) `int (__fastcall *)(FT_RendererRec_ *, FT_GlyphSlotRec_ *, FT_Render_Mode_, const FT_Vector_ *)` | render_glyph
72 | (8) `int (__fastcall *)(FT_RendererRec_ *, FT_GlyphSlotRec_ *, const FT_Matrix_ *, const FT_Vector_ *)` | transform_glyph
80 | (8) `void (__fastcall *)(FT_RendererRec_ *, FT_GlyphSlotRec_ *, FT_BBox_ *)` | get_glyph_cbox
88 | (8) `int (__fastcall *)(FT_RendererRec_ *, unsigned int, void *)` | set_mode
96 | (8) `FT_Raster_Funcs_ *` | raster_class


### `FileAccessTransforms`
Offset | Type | Name
-|-|-|-
0 | (8) `FileAccessTransforms_vtbl *` | __vftable


### `Frustum`
Offset | Type | Name
-|-|-|-
0 | (96) `glm::tvec4<float,0>[6]` | mFrustumPlanes
96 | (48) `FrustumEdges` | mNearClippingPlaneEdges
144 | (48) `FrustumEdges` | mFarClippingPlaneEdges


### `FrustumEdges`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,0>` | topLeft
12 | (12) `glm::tvec3<float,0>` | topRight
24 | (12) `glm::tvec3<float,0>` | bottomLeft
36 | (12) `glm::tvec3<float,0>` | bottomRight


### `FT_Raster_Funcs_`
Offset | Type | Name
-|-|-|-
0 | (4) `FT_Glyph_Format_` | glyph_format
8 | (8) `int (__fastcall *)(void *, struct FT_RasterRec_ **)` | raster_new
16 | (8) `void (__fastcall *)(struct FT_RasterRec_ *, unsigned __int8 *, unsigned int)` | raster_reset
24 | (8) `int (__fastcall *)(struct FT_RasterRec_ *, unsigned int, void *)` | raster_set_mode
32 | (8) `int (__fastcall *)(struct FT_RasterRec_ *, const FT_Raster_Params_ *)` | raster_render
40 | (8) `void (__fastcall *)(struct FT_RasterRec_ *)` | raster_done


### `FT_Glyph_Class_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | glyph_size
4 | (4) `FT_Glyph_Format_` | glyph_format
8 | (8) `int (__fastcall *)(FT_GlyphRec_ *, FT_GlyphSlotRec_ *)` | glyph_init
16 | (8) `void (__fastcall *)(FT_GlyphRec_ *)` | glyph_done
24 | (8) `int (__fastcall *)(FT_GlyphRec_ *, FT_GlyphRec_ *)` | glyph_copy
32 | (8) `void (__fastcall *)(FT_GlyphRec_ *, const FT_Matrix_ *, const FT_Vector_ *)` | glyph_transform
40 | (8) `void (__fastcall *)(FT_GlyphRec_ *, FT_BBox_ *)` | glyph_bbox
48 | (8) `int (__fastcall *)(FT_GlyphRec_ *, FT_GlyphSlotRec_ *)` | glyph_prepare


### `FT_AutoHinter_InterfaceRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `void (__fastcall *)(FT_AutoHinterRec_ *, FT_FaceRec_ *)` | reset_face
8 | (8) `void (__fastcall *)(FT_AutoHinterRec_ *, FT_FaceRec_ *, void **, int *)` | get_global_hints
16 | (8) `void (__fastcall *)(FT_AutoHinterRec_ *, void *)` | done_global_hints
24 | (8) `int (__fastcall *)(FT_AutoHinterRec_ *, FT_GlyphSlotRec_ *, FT_SizeRec_ *, unsigned int, int)` | load_glyph


### `FuncInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `` | magicNumber
4 | (4) `` | maxState
8 | (4) `` | pUnwindMap
12 | (4) `` | nTryBlocks
16 | (4) `` | pTryBlockMap
20 | (4) `` | nIPMapEntries
24 | (4) `` | pIPtoStateMap
28 | (4) `` | dispUnwindHelp
32 | (4) `` | pESTypeList
36 | (4) `` | EHFlags


### `FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>::()::__l8::<lambda_b7919b453013e6c018d3eb2079af3ac9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileDownloadManager>` | weak_this
16 | (64) `std::function<void __cdecl(Core::Path const &,enum DownloaderResult)>` | onCompleteCallback


### `FrameUpdateContext`
Offset | Type | Name
-|-|-|-
0 | (8) `mce::RenderContext *` | renderContext
8 | (8) `MinecraftGameplayGraphicsResources *` | minecraftGameplayGraphicsResources
16 | (8) `mce::TextureGroup *` | textureGroup
24 | (8) `Tessellator *` | tessellator


### `FocusMoveScreenEventData`
Offset | Type | Name
-|-|-|-
0 | (8) `float[2]` | position


### `Font::SheetId`
Offset | Type | Name
-|-|-|-
0 | (8) `const void *` | rawFontPtr
8 | (4) `int` | index


### `Font::TextObject`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<Font::TextObject::Page>` | mPages
24 | (16) `mce::Color` | mColor
40 | (1) `bool` | mContainsUnicode
41 | (1) `bool` | mShadow
44 | (16) `mce::Color` | mShadowColor
60 | (8) `glm::tvec2<float,0>` | mShadowOffset


### `FontAlias::ReferenceData`
Offset | Type | Name
-|-|-|-
0 | (48) `FontHandle` | mFontHandle
48 | (32) `std::string` | mLanguageCode
80 | (24) `std::vector<std::pair<int,int>>` | mIncludedUnicodeRanges


### `FontRepository::loadDefaultFonts::__l2::<lambda_4f422798d8e19b20911552d15f97b207>::()::__l2::<lambda_9f7ee64e5f52351a246105fa89b76599>`
Offset | Type | Name
-|-|-|-
0 | (8) `FontRepository *const` | __this
8 | (32) `const std::string` | alias
40 | (16) `std::shared_ptr<std::shared_ptr<BitmapFont> >` | loadedFont


### `FontRepository::loadDefaultFonts::__l2::<lambda_7fe000d9f42c358f49b7b7b1aeed026a>::()::__l2::<lambda_fb53307a4bf33dc8a2da341738d6f3d3>`
Offset | Type | Name
-|-|-|-
0 | (8) `FontRepository *const` | __this
8 | (32) `const std::string` | alias
40 | (16) `std::shared_ptr<std::shared_ptr<MSDFFont> >` | loadedFont


### `Font::GlyphQuad`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | width
12 | (4) `float` | height
16 | (4) `float` | ix
20 | (4) `float` | iy
24 | (4) `float` | ixb
28 | (4) `float` | iyb
32 | (4) `int` | shear
36 | (16) `mce::Color` | color


### `FileChunkInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | chunkID
8 | (8) `unsigned __int64` | startByte
16 | (8) `unsigned __int64` | endByte


### `FogCommandSettings`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mFogIdentifier
32 | (32) `std::string` | mUserProvidedId


### `framebuilderInsertTerrainCommandsForChunks::__l2::<lambda_c1fa93ce778fd992669707126a079fcb>`
Offset | Type | Name
-|-|-|-
0 | (8) `CommandListQueue *` | commandListQueue
8 | (2) `const dragon::frameobject::components::ViewSetId` | viewSetId
16 | (8) `const ViewRenderData *` | viewData
24 | (8) `const ChunkRenderObjectCollection *` | chunkState
32 | (24) `std::vector<unsigned char,mce::AlignmentHelper::AlignmentAllocator<unsigned char,16> >` | perFrameConstantsMemory
56 | (1) `const bool` | shouldRenderBarrierBlocks
57 | (1) `const bool` | shouldRenderStructureVoidBlocks


### `FogManager::Layer`
Offset | Type | Name
-|-|-|-
0 | (4) `FogManager::LayerType` | mType
8 | (24) `std::vector<WeakRefT<SharePtrRefTraits<FogDefinition const > >>` | mDefinitions


### `FlipbookTextureDescription`
Offset | Type | Name
-|-|-|-
0 | (56) `ResourceLocation` | resourceLocation
56 | (24) `std::vector<int>` | frames
80 | (4) `int` | replicate
84 | (4) `int` | ticksPerFrame
88 | (1) `bool` | blend
92 | (4) `int` | blockVariant
96 | (32) `std::string` | tileName
128 | (1) `bool` | tickOnlyOnce
132 | (8) `std::optional<int>` | textureVariant


### `FlightingService::_fetch::__l2::<lambda_03023acb2b69c9a5fef635df5c64a11f>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FlightingService>` | weakThis


### `FilePickerSettings::FileDescription`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | Extension
32 | (32) `std::string` | Name


### `FilterFormattedStringContructor`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mFormattedStr
32 | (4) `const unsigned int` | mTotalSelected
36 | (4) `unsigned int` | mFiltersAddedCount
40 | (4) `unsigned int` | mFilterStringsAdded


### `FileArchiver::Result`
Offset | Type | Name
-|-|-|-
0 | (4) `FileArchiver::Outcome` | outcome
8 | (32) `Core::PathBuffer<std::string >` | fileName


### `FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::ScopedAllocation`
Offset | Type | Name
-|-|-|-
0 | (16) `std::shared_ptr<Core::CpuRingBufferAllocation_Buffer::Buffer>` | mBuffer
16 | (8) `const unsigned __int64` | mOffset
24 | (8) `const unsigned __int64` | mSize
32 | (8) `const unsigned __int64` | mAlignmentPrefixSize
40 | (8) `const unsigned __int64` | mFenceValue


### `FilterGroup`
Offset | Type | Name
-|-|-|-
0 | (8) `FilterGroup_vtbl *` | __vftable
8 | (4) `FilterGroup::CollectionType` | mCollectionType
16 | (24) `std::vector<std::shared_ptr<FilterGroup>>` | mChildren
40 | (24) `std::vector<std::shared_ptr<FilterTest>>` | mMembers


### `FlockingComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ActorUniqueID>` | mNeighborhood
24 | (12) `Vec3` | mCenterOfMass
36 | (12) `Vec3` | mGroupVelocity
48 | (12) `Vec3` | mGoalHeading
60 | (12) `Vec3` | mCurrentHeading
72 | (1) `bool` | mInWater
73 | (1) `bool` | mMatchVariant
74 | (1) `bool` | mUseCenterOfMass
75 | (1) `bool` | mIsLeader
76 | (1) `bool` | mInFlock
77 | (1) `bool` | mIsEnabled
78 | (1) `bool` | mHasTargetGoal
79 | (1) `bool` | mUsingDirection
80 | (4) `int` | mFlockLimit
84 | (4) `float` | mLonerChance
88 | (4) `float` | mGoalWeight
92 | (4) `float` | mInfluenceRadius
96 | (4) `float` | mBreachInfluence
100 | (4) `float` | mSeparationWeight
104 | (4) `float` | mSeparationThreshold
108 | (4) `float` | mCohesionWeight
112 | (4) `float` | mCohesionThreshold
116 | (4) `float` | mInnerCohesionThreshold
120 | (4) `float` | mMinHeight
124 | (4) `float` | mMaxHeight
128 | (4) `float` | mBlockDist
132 | (4) `float` | mBlockWeight
136 | (1) `bool` | mOverspeedRequired


### `FloatTag`
Offset | Type | Name
-|-|-|-
0 | (8) `Tag` | baseclass_0
8 | (4) `float` | data


### `FeatureToggles::FeatureToggle`
Offset | Type | Name
-|-|-|-
0 | (4) `_BYTE[4]` | featureID
4 | (4) `_BYTE[4]` | dependencyFeatureID
8 | (8) `std::unique_ptr<Option>` | option
16 | (64) `std::function<void __cdecl(Option &)>` | setup
80 | (64) `std::function<void __cdecl(bool &)>` | lock


### `FunctionManager::OriginMapping`
Offset | Type | Name
-|-|-|-
0 | (8) `std::unique_ptr<CommandOrigin>` | mOrigin
8 | (4) `unsigned int` | mRefCount


### `FullPlayerInventoryWrapper`
Offset | Type | Name
-|-|-|-
0 | (8) `PlayerInventory *` | mPlayerInventory
8 | (8) `SimpleContainer *` | mArmorInventory
16 | (8) `SimpleContainer *` | mHandInventory
24 | (8) `InventoryTransactionManager *` | mTransactionManager
32 | (8) `Player *` | mPlayer


### `FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileDownloadManager>` | weak_this
16 | (64) `std::function<void __cdecl(Core::Path const &,enum DownloaderResult)>` | onCompleteCallback


### `FileDownloadManager::_writeData::__l2::<lambda_6f81f195f94e9beac581973bed159d3c>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileDownloadManager>` | weak_this
16 | (8) `unsigned __int64` | progress
24 | (64) `std::function<void __cdecl(unsigned __int64,bool)>` | writeComplete


### `FileDownloadManager::_writeData::__l2::<lambda_e1119d03447226ec2640e6a1b57aad89>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileDownloadManager>` | weak_this
16 | (24) `std::vector<unsigned char>` | data
40 | (8) `unsigned __int64` | writeBytes
48 | (8) `unsigned __int64` | offset


### `FileUploadManager::uploadFile::__l13::<lambda_74760951e5721fb9dafc828e7e1ca7c9>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this
16 | (32) `const std::string` | uploadId
48 | (1) `bool` | autoStartUpload
56 | (16) `const Json::Value` | uploadOptions


### `FileUploadManager::_uploadChunk::__l13::<lambda_beec154458228c4f1efa54daecb2bd49>::()::__l5::<lambda_b942687c99a128d38d4a3acdf5208e9b>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this
16 | (24) `const FileChunkInfo` | chunk
40 | (24) `std::vector<unsigned char>` | buffer


### `FileUploadManager::_uploadStream::__l2::<lambda_704199bdd8ef4b5e4b61022e06e9c849>::()::__l5::<lambda_159c837b6a142bd3dc90b4a04b18c5b4>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this
16 | (16) `FileUploadManager::_uploadStream::__l2::<lambda_7c32c70c440907d77e4081b7aef620a1>` | fetchStreamDataCallback
32 | (16) `FileUploadManager::_uploadStream::__l2::<lambda_ab8d111204de64d325c648c9d712e8ea>` | onStreamFinishedCallback
48 | (32) `std::string` | boundary


### `FileUploadManager::_uploadStream::__l2::<lambda_7c32c70c440907d77e4081b7aef620a1>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this


### `FileUploadManager::_uploadStream::__l2::<lambda_ab8d111204de64d325c648c9d712e8ea>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileUploadManager>` | weak_this


### `FileChunk`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned char>` | data
24 | (24) `FileChunkInfo` | info


### `FileInfo`
Offset | Type | Name
-|-|-|-
0 | (32) `Core::PathBuffer<std::string >` | filePath
32 | (8) `unsigned __int64` | fileSize
40 | (32) `std::string` | fileHash


### `FilterContext`
Offset | Type | Name
-|-|-|-
0 | (8) `const Actor *` | mHost
8 | (8) `const Actor *` | mSubject
16 | (8) `const VariantParameterList *` | mParams
24 | (8) `const BlockSource *` | mRegion
32 | (8) `const Dimension *` | mDimension
40 | (8) `const Level *` | mLevel
48 | (8) `const Biome *` | mBiome
56 | (12) `BlockPos` | mPos
72 | (8) `const Block *` | mBlock
80 | (8) `const TagRegistry<IDType<BiomeTagIDType>,IDType<BiomeTagSetIDType> > *` | mTagRegistry


### `FilterInputDefinition`
Offset | Type | Name
-|-|-|-
0 | (48) `FilterInput` | mInput
48 | (32) `std::string` | mDescription


### `FilterTestDaytime`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `FilterTest`
Offset | Type | Name
-|-|-|-
0 | (8) `FilterTest_vtbl *` | __vftable
8 | (2) `_BYTE[2]` | mSubject
10 | (2) `FilterOperator` | mOperator


### `FilterInputs`
Offset | Type | Name
-|-|-|-
0 | (2) `_BYTE[2]` | mSubject
8 | (48) `FilterInput` | mDomain
56 | (2) `FilterOperator` | mOperator
64 | (48) `FilterInput` | mValue


### `FilterTestDifficulty`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `FilterTestGameRule`
Offset | Type | Name
-|-|-|-
0 | (16) `FilterTest` | baseclass_0
16 | (32) `std::string` | mGameRule
48 | (1) `bool` | mValue


### `FilterTestHourlyClock`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0
24 | (4) `int` | mValue


### `FilterTestBiome`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `FilterTestBiomeHasTag`
Offset | Type | Name
-|-|-|-
0 | (80) `SimpleTagIDFilterTest` | baseclass_0


### `FilterTestBiomeSnowCovered`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `FilterTestBiomeHumid`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `FilterTestTemperatureType`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `FilterTestTemperatureValue`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestBrightness`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleFloatFilterTest` | baseclass_0


### `FilterTestAltitude`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleIntFilterTest` | baseclass_0


### `FilterTestHasTradeSupply`
Offset | Type | Name
-|-|-|-
0 | (24) `SimpleBoolFilterTest` | baseclass_0


### `FilteredTransformationAttributes<PostShoreEdgeTransformation>`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PosibleTransformation>` | mTransformations


### `Feature`
Offset | Type | Name
-|-|-|-
0 | (8) `IFeature` | baseclass_0
8 | (8) `Actor *` | mPlacer
16 | (8) `WorldChangeTransaction *` | mTransaction


### `FileArchiver::archivePack::__l2::<lambda_e4861c6342045bae76278851b5db2c79>`
Offset | Type | Name
-|-|-|-
0 | (8) `FileArchiver *const` | __this
8 | (64) `std::function<void __cdecl(FileArchiver::Result &)>` | exportCallback
72 | (32) `const Core::Path` | path
104 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | outputName


### `FileArchiver::archiveLevel::__l2::<lambda_ef06c283a4b2b877a6778581d3ec778e>`
Offset | Type | Name
-|-|-|-
0 | (8) `FileArchiver *const` | __this
8 | (64) `std::function<void __cdecl(FileArchiver::Result &)>` | exportCallback
72 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | outputName
1112 | (32) `const std::string` | worldId
1144 | (1) `bool` | isBundle
1152 | (8) `unsigned __int64` | numFiles


### `FileArchiver::archiveLevel::__l2::<lambda_ac943e513845c7fd6e6317395fc32783>`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | level
8 | (8) `FileArchiver *const` | __this
16 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | outputName
1056 | (1) `bool` | isBundle
1064 | (64) `std::function<void __cdecl(FileArchiver::Result &)>` | exportCallback
1128 | (16) `std::shared_ptr<FileArchiver::Result>` | exportResult


### `FileArchiver::archiveLevel::__l2::<lambda_ac943e513845c7fd6e6317395fc32783>::()::__l2::<lambda_f3dbac58284b04dc57297a0858a258fd>`
Offset | Type | Name
-|-|-|-
0 | (8) `FileArchiver *const` | __this
8 | (8) `Level *` | level
16 | (64) `std::function<void __cdecl(FileArchiver::Result &)>` | exportCallback
80 | (16) `std::shared_ptr<FileArchiver::Result>` | exportResult


### `FileArchiver::archiveLevel::__l2::<lambda_ac943e513845c7fd6e6317395fc32783>::()::__l2::<lambda_70145daf2eda0b02012b6d6f8f2ca40e>`
Offset | Type | Name
-|-|-|-
0 | (8) `Level *` | level
8 | (8) `unsigned __int64` | numFiles
16 | (8) `FileArchiver *const` | __this
24 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | outputName
1064 | (1) `bool` | isBundle
1072 | (16) `std::shared_ptr<FileArchiver::Result>` | exportResult


### `FileArchiver::_importVanillaLevel::__l2::<lambda_982a8571ec925d774f47b3ea87936fc0>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileArchiver>` | weak_this
16 | (16) `std::shared_ptr<FileArchiver::Result>` | currentResult
32 | (64) `std::function<void __cdecl(FileArchiver::Result &)>` | importCallback
96 | (16) `std::shared_ptr<std::promise<FileArchiver::Result> >` | currentPromise


### `FileArchiver::_importVanillaLevel::__l2::<lambda_17892f377568356bdd0cc70fc9fbd172>`
Offset | Type | Name
-|-|-|-
0 | (16) `std::weak_ptr<FileArchiver>` | weak_this
16 | (16) `std::shared_ptr<FileArchiver::Result>` | currentResult
32 | (1040) `Core::PathBuffer<Core::StackString<char,1024> >` | archivedWorldFile


### `FancyTreeTrunk::FoliageCoords`
Offset | Type | Name
-|-|-|-
0 | (12) `BlockPos` | baseclass_0
12 | (4) `int` | mBranchBase


### `FlatWorldGeneratorOptions`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mEncodingVersion
8 | (24) `std::vector<BlockLayer>` | mBlockLayers
32 | (4) `int` | mBiomeId
40 | (16) `Json::Value` | mStructureOptions
56 | (4) `int` | mTotalLayers


### `FixedBiomeSource`
Offset | Type | Name
-|-|-|-
0 | (8) `BiomeSource` | baseclass_0
8 | (8) `const Biome *` | mFixedBiome


### `FoldMeuScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_d700cb1b2a11b77f5ca7cb09e25db2b8>`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<bool __cdecl(void)>` | getValue


### `fd_set`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | fd_count
8 | (512) `unsigned __int64[64]` | fd_array


### `FurnaceScreenControllerProxyCallbacks`
Offset | Type | Name
-|-|-|-
0 | (64) `std::function<ContainerController * __cdecl(std::string const &)>` | mGetContainerController
64 | (64) `std::function<int __cdecl(void)>` | mGetBurnProgress
128 | (64) `std::function<int __cdecl(void)>` | mGetLitProgress
192 | (64) `std::function<bool __cdecl(std::string &,int &,int &)>` | mIsFinished


### `FlowerFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0
24 | (8) `const Block *` | mBlock


### `FMOD::Sound`
Offset | Type | Name
-|-|-|-


### `FT_Matrix_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | xx
4 | (4) `int` | xy
8 | (4) `int` | yx
12 | (4) `int` | yy


### `FT_Vector_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | y


### `FT_BBox_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | xMin
4 | (4) `int` | yMin
8 | (4) `int` | xMax
12 | (4) `int` | yMax


### `FT_Open_Args_`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | flags
8 | (8) `const unsigned __int8 *` | memory_base
16 | (4) `int` | memory_size
24 | (8) `char *` | pathname
32 | (8) `FT_StreamRec_ *` | stream
40 | (8) `FT_ModuleRec_ *` | driver
48 | (4) `int` | num_params
56 | (8) `FT_Parameter_ *` | params


### `FT_Size_RequestRec_`
Offset | Type | Name
-|-|-|-
0 | (4) `FT_Size_Request_Type_` | type
4 | (4) `int` | width
8 | (4) `int` | height
12 | (4) `unsigned int` | horiResolution
16 | (4) `unsigned int` | vertResolution


### `FT_Raster_Params_`
Offset | Type | Name
-|-|-|-
0 | (8) `const FT_Bitmap_ *` | target
8 | (8) `const void *` | source
16 | (4) `int` | flags
24 | (8) `void (__fastcall *)(int, int, const FT_Span_ *, void *)` | gray_spans
32 | (8) `void (__fastcall *)(int, int, const FT_Span_ *, void *)` | black_spans
40 | (8) `int (__fastcall *)(int, int, void *)` | bit_test
48 | (8) `void (__fastcall *)(int, int, void *)` | bit_set
56 | (8) `void *` | user
64 | (16) `FT_BBox_` | clip_box


### `FT_GlyphSlotRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_LibraryRec_ *` | library
8 | (8) `FT_FaceRec_ *` | face
16 | (8) `FT_GlyphSlotRec_ *` | next
24 | (4) `unsigned int` | glyph_index
32 | (16) `FT_Generic_` | generic
48 | (32) `FT_Glyph_Metrics_` | metrics
80 | (4) `int` | linearHoriAdvance
84 | (4) `int` | linearVertAdvance
88 | (8) `FT_Vector_` | advance
96 | (4) `FT_Glyph_Format_` | format
104 | (40) `FT_Bitmap_` | bitmap
144 | (4) `int` | bitmap_left
148 | (4) `int` | bitmap_top
152 | (40) `FT_Outline_` | outline
192 | (4) `unsigned int` | num_subglyphs
200 | (8) `FT_SubGlyphRec_ *` | subglyphs
208 | (8) `void *` | control_data
216 | (4) `int` | control_len
220 | (4) `int` | lsb_delta
224 | (4) `int` | rsb_delta
232 | (8) `void *` | other
240 | (8) `FT_Slot_InternalRec_ *` | internal


### `FT_Generic_`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | data
8 | (8) `void (__fastcall *)(void *)` | finalizer


### `FT_Glyph_Metrics_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | width
4 | (4) `int` | height
8 | (4) `int` | horiBearingX
12 | (4) `int` | horiBearingY
16 | (4) `int` | horiAdvance
20 | (4) `int` | vertBearingX
24 | (4) `int` | vertBearingY
28 | (4) `int` | vertAdvance


### `FT_Hashkey_`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | num
1 | (8) `const char *` | str


### `FT_CharMapRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_FaceRec_ *` | face
8 | (4) `FT_Encoding_` | encoding
12 | (2) `unsigned __int16` | platform_id
14 | (2) `unsigned __int16` | encoding_id


### `FT_Span_`
Offset | Type | Name
-|-|-|-
0 | (2) `__int16` | x
2 | (2) `unsigned __int16` | len
4 | (1) `unsigned __int8` | coverage


### `FT_ListRec_`
Offset | Type | Name
-|-|-|-
0 | (8) `FT_ListNodeRec_ *` | head
8 | (8) `FT_ListNodeRec_ *` | tail


### `FT_Data_`
Offset | Type | Name
-|-|-|-
0 | (8) `const unsigned __int8 *` | pointer
8 | (4) `int` | length


### `FieldNameIterator`
Offset | Type | Name
-|-|-|-
0 | (16) `SubString` | str
16 | (8) `wchar_t *` | ptr


### `FloatTag_vtbl`
```
struct /*VFT*/ FloatTag_vtbl
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

### `FilterTextPacket`
```
const struct __cppobj __declspec(align(8)) FilterTextPacket : Packet
{
  std::string mText;
  bool mFromServer;
};

```

### `FilterTextPacket_vtbl`
```
struct /*VFT*/ FilterTextPacket_vtbl
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

### `FileChunkManager`
```
struct __cppobj FileChunkManager
{
  unsigned __int64 mTotalSize;
  unsigned int mChunkSize;
  unsigned __int64 mTotalNbChunks;
  unsigned __int64 mRequestedChunks;
  unsigned __int64 mReceivedChunks;
  unsigned __int64 mWrittenChunks;
  std::vector<FileChunkInfo> mChunkInfo;
  MovePriorityQueue<FileChunk,std::less<FileChunk> > mChunkQueue;
};

```

### `FileUploadManager`
```
struct __cppobj FileUploadManager : std::enable_shared_from_this<FileUploadManager>
{
  FileUploadManager_vtbl *__vftable /*VFT*/;
  FileInfo mFile;
  FileUploadManager::MultiPartStreamHelper mMultiPartHelper;
  UploadState mState;
  _BYTE mUploadError[4];
  std::shared_ptr<IFilePicker> mFilePicker;
  std::shared_ptr<IFileChunkUploader> mFileUploader;
  TaskGroup *mIOTaskGroup;
  std::weak_ptr<FileArchiver> mFileArchiver;
  bool mUploadAllAtOnce;
  bool mContinueOnReception;
  bool mUseStream;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
};

```

### `FileUploadManager_vtbl`
```
struct /*VFT*/ FileUploadManager_vtbl
{
  void (__fastcall *~FileUploadManager)(FileUploadManager *this);
  float (__fastcall *getUploadProgress)(FileUploadManager *this);
  void (__fastcall *uploadFileToRealmStorage)(FileUploadManager *this, const std::string *, const Core::Path *, const std::string *);
};

```

### `FileUploadManager::MultiPartStreamHelper`
```
struct __cppobj FileUploadManager::MultiPartStreamHelper
{
  bool needHeader;
  bool needTrailer;
  std::string header;
  std::string trailer;
  unsigned __int64 currentFileByte;
  unsigned __int64 totalFileByte;
  unsigned __int64 totalStreamSize;
};

```

### `Font`
```
struct __cppobj Font
{
  Font_vtbl *__vftable /*VFT*/;
  int mFontTexture;
  bool mAutoResetFormat;
  bool mUseCache;
  bool mRenderUnicodeSmooth;
  bool mAlwaysUnicode;
  mce::Color mCurrentColor;
  mce::Color mCaretColor;
  bool mItalic;
  bool mBold;
  bool mStrikethrough;
  bool mUnderlined;
  bool mObfuscated;
  mce::MaterialPtr mFontMat;
  mce::Color mColors[32];
  mce::TextureGroup *mTextures;
  std::map<std::tuple<std::string,mce::Color,float>,std::vector<Font::TextObject>,std::less<std::tuple<std::string,mce::Color,float> >,std::allocator<std::pair<std::tuple<std::string,mce::Color,float> const ,std::vector<Font::TextObject> > > > mStringCache;
  int mObfuscatedIndex;
  float mObfuscatedTextTime;
  Vec2 mCaretRenderPosition;
  Vec2 mCaretRenderSize;
};

```

### `Font_vtbl`
```
struct /*VFT*/ Font_vtbl
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
};

```

### `Font::TextObject::Page`
```
struct __cppobj Font::TextObject::Page
{
  mce::Mesh mMesh;
  mce::TexturePtr mTexture;
  bool mRenderSmooth;
  Font::SheetId mSheet;
};

```

### `FontRepository`
```
struct __cppobj FontRepository : AppPlatformListener, std::enable_shared_from_this<FontRepository>
{
  bool mIsInitialized;
  std::vector<std::shared_ptr<Font>> mLoadedFonts;
  std::unordered_map<std::string,unsigned __int64> mFontNameToIdentifier;
  unsigned __int64 mDefaultFontId;
  unsigned __int64 mRuneFontId;
  unsigned __int64 mUnicodeFontId;
  unsigned __int64 mSmoothFontLatinFontId;
  unsigned __int64 mUIFontId;
  unsigned __int64 mSmoothSmallFontID;
  std::unordered_map<unsigned __int64,std::shared_ptr<Font>> mOriginalMinecraftFonts;
  std::unordered_map<unsigned __int64,std::shared_ptr<Font>> mOverriddenFonts;
  std::vector<std::shared_ptr<Bedrock::Threading::IAsyncResult<void> >> mFontLoadingTaskTrackers;
  std::string mLanguageCode;
  std::vector<std::shared_ptr<Font>> mDelayedFontDelete;
};

```

### `FontRepository_vtbl`
```
struct /*VFT*/ FontRepository_vtbl
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

### `FileWatcherUpdate`
```
struct __cppobj FileWatcherUpdate
{
  std::optional<std::weak_ptr<mce::Image> > newSkin;
};

```

### `FlipbookTexture`
```
struct __cppobj __declspec(align(4)) FlipbookTexture
{
  std::vector<int> mFrames;
  TextureUVCoordinateSet mTexUVCoordSet;
  int mReplicate;
  mce::TexturePtr mTexturePtr;
  mce::MaterialPtr m2DBlitMaterial;
  std::unique_ptr<Tessellator> mTessellator;
  mce::Mesh mMesh;
  const ResourceLocation mResourceLocation;
  float mCurrFrame;
  int mNumFrames;
  int mFrameSequenceLength;
  int mTicksPerFrame;
  int mWidth;
  int mHeight;
  int mPadSize;
  bool mBlendFrames;
  bool mTickOnlyOnce;
};

```

### `FrameUpdateContextBase`
```
struct __cppobj FrameUpdateContextBase
{
};

```

### `FrameRenderObject`
```
const struct __cppobj FrameRenderObject
{
  std::vector<ViewRenderObject,LinearAllocator<ViewRenderObject> > mViews;
};

```

### `FocusManagerProxyCallbacks`
```
const struct __cppobj FocusManagerProxyCallbacks
{
  std::function<bool __cdecl(std::string const &)> mSetFocusControl;
};

```

### `FocusManagerProxy`
```
struct __cppobj FocusManagerProxy
{
  const FocusManagerProxyCallbacks mCallbacks;
};

```

### `FlyingItemCommand`
```
struct __cppobj __declspec(align(8)) FlyingItemCommand
{
  std::string mFromContainer;
  int mFromIndex;
  std::string mToContainer;
  int mToIndex;
  int mFlyingItemIdAux;
  int mColor;
  std::string mBannerPatterns;
  std::string mBannerColors;
  int mModId;
  std::string mModExtendValue;
  int mBannerType;
};

```

### `FocusManager`
```
struct __cppobj FocusManager
{
  glm::tvec2<float,0> mSize;
  std::vector<std::shared_ptr<UIControl>> mFocusControls;
  __int8 mFocusActive : 1;
  __int8 mFocusResetFlag : 1;
  __int8 mFindClosestControl : 1;
  __int8 mFocusPositionCaptured : 1;
  __int8 mNeedsDefaultFocusUpdate : 1;
  __int8 mIncludeMagnetControls : 1;
  int mFocusedControlIndex;
  std::weak_ptr<UIControl> mFocusedControl;
  std::weak_ptr<UIControl> mLostFocusControl;
  std::weak_ptr<UIControl> mCurrentModalRoot;
  std::weak_ptr<UIControl> mCurrentFocusContainer;
  RecentFocusVector mRecentFocusList;
  std::unique_ptr<FocusManagerProxy> mProxy;
  std::string mPendingFocusControlID;
  int mPendingFocusControlIndex;
  bool mHasPendingFocusControl;
  std::string mPendingFocusCollectionIndexName;
};

```

### `FlightingService`
```
struct __cppobj __declspec(align(2)) FlightingService : ServiceClient, std::enable_shared_from_this<FlightingService>
{
  std::shared_ptr<FlightingToggles> mFlightingToggles;
  IMinecraftEventing *mEventing;
  const Core::PathBuffer<std::string > mCacheLocation;
  const std::string mHostUrl;
  const std::string mClientId;
  std::string mCurrentLanguage;
  std::atomic<enum FlightingService::FetchState> mFetchState;
  std::vector<std::string> mCurrentTreatments;
  std::vector<std::string> mCurrentProgressions;
  std::vector<std::string> mOverrideTreatments;
  std::vector<std::string> mOverrideProgressions;
  std::mutex mQueuedCallbacksMutex;
  std::vector<std::function<void __cdecl(std::vector<std::string> const &)>> mQueuedCallbacks;
  std::mutex mTreatmentsMonitorCallbacksMutex;
  std::vector<FlightingService::TreatmentsMonitor> mTreatmentsMonitorCallbacks;
  std::atomic<unsigned int> mNextTreatmentsMonitorHandle;
  std::mutex mProgressionsMonitorCallbacksMutex;
  std::vector<FlightingService::ProgressionsMonitor> mProgressionsMonitorCallbacks;
  std::atomic<unsigned int> mNextProgressionsMonitorHandle;
  bool mTreatmentsOverriden;
  bool mProgressionsOverriden;
  bool mIsNetworkAllowed;
};

```

### `FlightingToggles::FlightingToggle`
```
struct __cppobj FlightingToggles::FlightingToggle
{
  FlightingToggleId toggleId;
  std::unique_ptr<Option> option;
  std::string progressionId;
};

```

### `FlightingToggles`
```
struct __cppobj FlightingToggles : IFlightingToggles
{
  std::vector<FlightingToggles::FlightingToggle> mToggles;
  FlightingService *mFlightingService;
  bool mFlightServiceIsAvailable;
  unsigned int mMonitorHandle;
  const Core::PathBuffer<std::string > mStorageLocation;
};

```

### `FlightingToggles_vtbl`
```
struct /*VFT*/ FlightingToggles_vtbl
{
  void (__fastcall *~IFlightingToggles)(IFlightingToggles *this);
  bool (__fastcall *isEnabled)(IFlightingToggles *this, FlightingToggleId);
  void (__fastcall *registerOptionObserverCallback)(IFlightingToggles *this, Bedrock::PubSub::ScopedSubscription *, FlightingToggleId, std::function<void __cdecl(Option const &)>);
};

```

### `FlightingService::TreatmentsMonitor`
```
struct __cppobj FlightingService::TreatmentsMonitor
{
  unsigned int handle;
  std::function<void __cdecl(std::vector<std::string> const &)> callback;
};

```

### `FlightingService::ProgressionsMonitor`
```
struct __cppobj FlightingService::ProgressionsMonitor
{
  unsigned int handle;
  std::function<void __cdecl(std::vector<std::string> const &)> callback;
};

```

### `FlightingService_vtbl`
```
struct /*VFT*/ FlightingService_vtbl
{
  void (__fastcall *~ServiceClient)(ServiceClient *this);
  void (__fastcall *update)(ServiceClient *this);
  void (__fastcall *_submitRequest)(ServiceClient *this, std::shared_ptr<RequestHandler>);
};

```

### `FileDownloadManager`
```
struct __cppobj __declspec(align(8)) FileDownloadManager : std::enable_shared_from_this<FileDownloadManager>
{
  FileDownloadManager_vtbl *__vftable /*VFT*/;
  FileInfo mFile;
  DownloadState mState;
  _BYTE mDownloadError[4];
  std::shared_ptr<IFilePicker> mFilePicker;
  std::shared_ptr<IFileChunkDownloader> mFileDownloader;
  std::shared_ptr<TaskGroup> mIOTaskGroup;
  bool mOwnsTaskGroup;
  MPMCQueue<std::function<void __cdecl(void)> > mCallbackQueue;
  std::vector<unsigned char> mDataBuffer;
  unsigned __int64 mCurrentBufferSize;
  unsigned __int64 mCurrentBufferOffset;
  bool mHasWriteError;
};

```

### `FileDownloadManager_vtbl`
```
struct /*VFT*/ FileDownloadManager_vtbl
{
  void (__fastcall *~FileDownloadManager)(FileDownloadManager *this);
  void (__fastcall *update)(FileDownloadManager *this);
  void (__fastcall *cancelDownload)(FileDownloadManager *this);
  float (__fastcall *getDownloadProgress)(FileDownloadManager *this);
};

```

### `FrustumCuller`
```
struct __cppobj FrustumCuller
{
  Frustum mFrustumData;
  Vec3 mOff;
};

```

### `FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearRange`
```
struct __cppobj FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearRange
{
  unsigned __int64 mOffset;
  unsigned __int64 mSize;
  std::atomic<unsigned __int64> mCurrentOffset;
};

```

### `FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>`
```
struct __cppobj FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>
{
  std::shared_ptr<Core::CpuRingBufferAllocation_Buffer::Buffer> mBuffer;
  const unsigned __int64 mSize;
  std::queue<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::ScopedAllocation,std::deque<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::ScopedAllocation,std::allocator<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::ScopedAllocation> > > mAllocations;
  std::atomic<unsigned __int64> mCurrentAllocationScopeSize;
  FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearRange mHeadRange;
  FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearRange mTailRange;
  std::atomic<unsigned __int64> mUsedSize;
  std::atomic<unsigned short> mCurrentAllocationId;
  unsigned __int64 mCurrentFence;
  std::optional<unsigned __int64> mLastFenceWithAllocation;
};

```

### `FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>`
```
struct __cppobj FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>
{
  std::atomic<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0> *> mLastPageAllocatedFrom;
  std::atomic<unsigned __int64> mAllocationScopeCheck;
  const unsigned __int64 mInitialSize;
  std::atomic<unsigned __int64> mUsedSize;
  std::atomic<unsigned __int64> mAllocationSize;
  boost::container::flat_map<unsigned __int64,std::shared_ptr<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0> >,std::less<unsigned __int64>,boost::container::new_allocator<std::pair<unsigned __int64,std::shared_ptr<FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0> > > > > mRings;
  unsigned __int16 mRingLifetimeWithNoAllocation;
  unsigned __int64 mCurrentFence;
  std::optional<unsigned __int64> mLastCompletedFenceValue;
  std::shared_ptr<Core::CpuRingBufferAllocation_Buffer> mBufferImpl;
  std::shared_mutex mAccessLock;
};

```

### `FMOD::ChannelControl`
```
struct __cppobj FMOD::ChannelControl
{
};

```

### `FMOD::ChannelGroup`
```
struct __cppobj FMOD::ChannelGroup : FMOD::ChannelControl
{
};

```

### `FMOD::Channel`
```
struct __cppobj FMOD::Channel : FMOD::ChannelControl
{
};

```

### `FMOD::System`
```
struct __cppobj FMOD::System
{
};

```

### `FileSystemFMOD`
```
struct __cppobj FileSystemFMOD
{
};

```

### `FillingContainer`
```
struct __cppobj FillingContainer : Container
{
  std::vector<ItemStack> mItems;
  Player *mPlayer;
};

```

### `FillingContainer_vtbl`
```
struct /*VFT*/ FillingContainer_vtbl
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
  bool (__fastcall *add)(FillingContainer *this, ItemStack *);
  bool (__fastcall *canAdd)(FillingContainer *this, const ItemStack *);
  void (__fastcall *clearSlot)(FillingContainer *this, int);
  int (__fastcall *clearInventory)(FillingContainer *this, int);
  void (__fastcall *load)(FillingContainer *this, const ListTag *, const SemVersion *, Level *);
  int (__fastcall *getEmptySlotsCount)(FillingContainer *this);
};

```

### `FogDefinitionRegistry`
```
struct __cppobj FogDefinitionRegistry : Bedrock::EnableNonOwnerReferences
{
  WeakRefT<SharePtrRefTraits<FogDefinition const > > mDefaultFogDefinition;
  std::unordered_map<HashedString,OwnerPtrT<SharePtrRefTraits<FogDefinition const > >> mFogDefinitionMap;
  std::unordered_map<HashedString,OwnerPtrT<SharePtrRefTraits<FogDefinition const > >> mBackCompatFogDefinitionMap;
};

```

### `FogManager`
```
struct __cppobj FogManager : Bedrock::EnableNonOwnerReferences
{
  std::vector<FogManager::Layer> mFogLayers;
};

```

### `FlushableEnv`
```
struct __cppobj FlushableEnv : leveldb::EnvWrapper
{
};

```

### `FlushableEnv_vtbl`
```
struct /*VFT*/ FlushableEnv_vtbl
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
  void (__fastcall *flushToPermanentStorage)(FlushableEnv *this);
};

```

### `FunctionManager`
```
struct __cppobj FunctionManager
{
  FunctionManager_vtbl *__vftable /*VFT*/;
  const GameRule *mGameRule;
  bool mIsProcessingStack;
  std::vector<FunctionManager::QueuedCommand> mCommandList;
  std::unordered_map<CommandOrigin const *,FunctionManager::OriginMapping> mOriginMap;
  std::unique_ptr<ICommandDispatcher> mCommandDispatcher;
  std::unique_ptr<CommandOrigin> mTickOrigin;
  std::unordered_map<std::string,std::unique_ptr<FunctionEntry>> mFunctions;
  std::vector<gsl::not_null<FunctionEntry *>> mTickFunctions;
};

```

### `FunctionManager_vtbl`
```
struct /*VFT*/ FunctionManager_vtbl
{
  void (__fastcall *~FunctionManager)(FunctionManager *this);
};

```

### `FunctionManager::QueuedCommand`
```
struct FunctionManager::QueuedCommand
{
  IFunctionEntry *mFunction;
  const CommandOrigin *mOrigin;
};

```

### `FunctionEntry`
```
struct __cppobj __declspec(align(8)) FunctionEntry : IFunctionEntry
{
  std::vector<std::unique_ptr<IFunctionEntry>> mCommandList;
  _BYTE mState[1];
};

```

### `FunctionEntry_vtbl`
```
struct /*VFT*/ FunctionEntry_vtbl
{
  void (__fastcall *~IFunctionEntry)(IFunctionEntry *this);
  void (__fastcall *execute)(IFunctionEntry *this, FunctionManager *, const CommandOrigin *);
};

```

### `FileArchiver`
```
struct __cppobj FileArchiver : Bedrock::EnableNonOwnerReferences, std::enable_shared_from_this<FileArchiver>
{
  Core::ZipUtils::ZipProgress mProgress;
  std::promise<FileArchiver::Result> mLastResult;
  FileArchiver::State mCurrentState;
  Core::FilePathManager *mFilePathManager;
  std::function<void __cdecl(std::string const &)> mDisplayMessageCallback;
  ResourcePackRepository *mResourcePackRepository;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
};

```

### `FileDataResponse`
```
struct __cppobj FileDataResponse
{
  Core::PathBuffer<std::string > mFullPath;
};

```

### `FileDataRequest`
```
struct __cppobj FileDataRequest : RequestHandler
{
  const std::string mContentUrl;
  std::function<void __cdecl(Core::Path const &)> mCallback;
  Core::PathBuffer<std::string > mFileCacheLocation;
  std::vector<std::basic_regex<char,std::regex_traits<char> >> mRequiredContentTypes;
  std::shared_ptr<FileDataResponse> mFileDataResponse;
};

```

### `FileDataRequest_vtbl`
```
struct /*VFT*/ FileDataRequest_vtbl
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

### `FeatureRegistry`
```
struct __cppobj FeatureRegistry
{
  std::vector<std::unique_ptr<IFeature>> mFeatureRegistry;
  std::vector<OwnerPtrT<FeatureRefTraits>> mFeatureSlots;
  std::unordered_map<HashedString,unsigned __int64> mFeatureLookupMap;
};

```

### `FeatureLoading::AbstractFeatureHolder`
```
struct __cppobj FeatureLoading::AbstractFeatureHolder
{
  FeatureLoading::AbstractFeatureHolder_vtbl *__vftable /*VFT*/;
};

```

### `FeatureLoading::AbstractFeatureHolder_vtbl`
```
struct /*VFT*/ FeatureLoading::AbstractFeatureHolder_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::FeatureRootParseContext`
```
struct __cppobj FeatureLoading::FeatureRootParseContext
{
  std::reference_wrapper<std::string > mFeatureName;
  std::reference_wrapper<IWorldRegistriesProvider> mRegistryProvider;
  std::reference_wrapper<ResourcePackManager const > mPackManager;
  std::unique_ptr<FeatureLoading::AbstractFeatureHolder> mFeatureHolder;
};

```

### `FeatureTypeFactory`
```
struct __cppobj FeatureTypeFactory
{
  std::unordered_map<std::string,std::function<IFeature * __cdecl(FeatureRegistry &,std::string const &)>> mFeatureGenerators;
  std::shared_ptr<JsonUtil::JsonSchemaObjectNode<JsonUtil::EmptyClass,FeatureLoading::FeatureRootParseContext> > mSchema;
  std::vector<std::function<void __cdecl(Documentation::Node &)>> mDocumentationGenerators;
  std::unique_ptr<JsonDefinitionUpgrader::IJsonDefinitionUpgrader> mFeatureDefinitionUpgrader;
};

```

### `Factory<Dimension,Level &,Scheduler &,AutomaticID<Dimension,int> &>`
```
struct __cppobj Factory<Dimension,Level &,Scheduler &,AutomaticID<Dimension,int> &>
{
  std::unordered_map<std::string,std::function<std::unique_ptr<Dimension> __cdecl(Level &,Scheduler &,AutomaticID<Dimension,int> &)>> mFactoryMap;
};

```

### `Feature_vtbl`
```
struct /*VFT*/ Feature_vtbl
{
  void (__fastcall *~IFeature)(IFeature *this);
  std::optional<BlockPos> *(__fastcall *place)(IFeature *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *);
  std::string *(__fastcall *getStructureName)(IFeature *this, std::string *result);
  bool (__fastcall *parse)(IFeature *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
  bool (__fastcall *place)(Feature *this, BlockSource *, const BlockPos *, Random *);
};

```

### `FilterTest::Definition`
```
const struct __cppobj FilterTest::Definition
{
  std::string mName;
  std::string mDescription;
  const FilterParamDefinition *mSubjectDefinition;
  const FilterParamDefinition *mDomainDefinition;
  const FilterParamDefinition *mOperatorDefinition;
  const FilterParamDefinition *mValueDefinition;
  std::function<std::shared_ptr<FilterTest> __cdecl(void)> mFactory;
};

```

### `FilterTest_vtbl`
```
struct /*VFT*/ FilterTest_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `Factory<EventResponse>`
```
const struct __cppobj Factory<EventResponse>
{
  std::unordered_map<std::string,std::function<std::unique_ptr<EventResponse> __cdecl(void)>> mFactoryMap;
};

```

### `FuelItemComponent`
```
const struct __cppobj __declspec(align(8)) FuelItemComponent : ItemComponent
{
  float mFuelDuration;
};

```

### `FuelItemComponent_vtbl`
```
struct /*VFT*/ FuelItemComponent_vtbl
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

### `FoodItemComponentLegacy::Effect`
```
struct FoodItemComponentLegacy::Effect
{
  const char *descriptionId;
  int id;
  int duration;
  int amplifier;
  float chance;
};

```

### `FoodItemComponentLegacy`
```
struct __cppobj FoodItemComponentLegacy : IFoodItemComponent
{
  const Item *mOwner;
  int mNutrition;
  float mSaturationModifier;
  std::string mUsingConvertsTo;
  _BYTE mOnUseAction[4];
  Vec3 mOnUseRange;
  std::string mCoolDownType;
  int mCooldownTime;
  bool mCanAlwaysEat;
  std::vector<FoodItemComponentLegacy::Effect> mEffects;
  std::vector<unsigned int> mRemoveEffects;
};

```

### `FoodItemComponentLegacy_vtbl`
```
struct /*VFT*/ FoodItemComponentLegacy_vtbl
{
  void (__fastcall *~IFoodItemComponent)(IFoodItemComponent *this);
  int (__fastcall *getNutrition)(IFoodItemComponent *this);
  float (__fastcall *getSaturationModifier)(IFoodItemComponent *this);
  const Item *(__fastcall *eatItem)(IFoodItemComponent *this, ItemStack *, Actor *, Level *);
  bool (__fastcall *use)(IFoodItemComponent *this, ItemStack *, Player *);
  const Item *(__fastcall *useTimeDepleted)(IFoodItemComponent *this, ItemStack *, Player *, Level *);
};

```

### `Factory<BaseLightTextureImageBuilder,Level &,Scheduler &>`
```
struct __cppobj Factory<BaseLightTextureImageBuilder,Level &,Scheduler &>
{
  std::unordered_map<std::string,std::function<std::unique_ptr<BaseLightTextureImageBuilder> __cdecl(Level &,Scheduler &)>> mFactoryMap;
};

```

### `Factory<BlockComponentDescription>`
```
struct __cppobj Factory<BlockComponentDescription>
{
  std::unordered_map<std::string,std::function<std::unique_ptr<BlockComponentDescription> __cdecl(void)>> mFactoryMap;
};

```

### `FishingHook`
```
struct __cppobj FishingHook : Actor
{
  const float SHOOT_SPEED;
  const float SHOOT_POWER;
  const int NUM_PERCENTAGE_STEPS;
  bool mInGround;
  BlockPos mBlockPos;
  float mFishAngle;
  int mLife;
  int mFlightTime;
  int mTimeUntilHooked;
  int mTimeUntilLured;
  int mTimeUntilNibble;
  int mFishingSpeed;
  int mLerpSteps;
  Vec3 mLerpPos;
  float mLerpRotX;
  float mLerpRotY;
  float mBobTimer;
  Vec3 mTargetPos;
};

```

### `FishingHook_vtbl`
```
struct /*VFT*/ FishingHook_vtbl
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
};

```

### `FilePickerSettings`
```
struct __cppobj FilePickerSettings
{
  std::function<void __cdecl(std::shared_ptr<FilePickerSettings>)> onCancel;
  std::function<void __cdecl(bool)> onOperationComplete;
  std::function<void __cdecl(std::shared_ptr<FilePickerSettings>,Core::Path const &)> onPick;
  std::vector<FilePickerSettings::FileDescription> mFileDescriptions;
  unsigned __int64 mDefaultFileExtensionIndex;
  FilePickerSettings::PickerType mPickerType;
  std::string mDefaultFileName;
  std::string mDefaultAlbumName;
  std::string mFilePickerTitle;
};

```

### `FeatureToggles`
```
struct __cppobj FeatureToggles : Bedrock::EnableNonOwnerReferences
{
  std::vector<FeatureToggles::FeatureToggle> mFeatures;
  std::vector<Bedrock::PubSub::ScopedSubscription> mOptionLockSubscriptions;
  Core::PathBuffer<std::string > mFilePath;
};

```

### `Facing`
```
struct __cppobj Facing
{
};

```

### `Facing::Plane`
```
struct __cppobj Facing::Plane
{
};

```

### `FMOD_ASYNCREADINFO`
```
struct FMOD_ASYNCREADINFO
{
  void *handle;
  unsigned int offset;
  unsigned int sizebytes;
  int priority;
  void *userdata;
  void *buffer;
  unsigned int bytesread;
  void (__fastcall *done)(FMOD_ASYNCREADINFO *, FMOD_RESULT);
};

```

### `FMOD_GUID`
```
struct FMOD_GUID
{
  unsigned int Data1;
  unsigned __int16 Data2;
  unsigned __int16 Data3;
  unsigned __int8 Data4[8];
};

```

### `FMOD_CREATESOUNDEXINFO`
```
struct FMOD_CREATESOUNDEXINFO
{
  int cbsize;
  unsigned int length;
  unsigned int fileoffset;
  int numchannels;
  int defaultfrequency;
  FMOD_SOUND_FORMAT format;
  unsigned int decodebuffersize;
  int initialsubsound;
  int numsubsounds;
  int *inclusionlist;
  int inclusionlistnum;
  FMOD_RESULT (__fastcall *pcmreadcallback)(struct FMOD_SOUND *, void *, unsigned int);
  FMOD_RESULT (__fastcall *pcmsetposcallback)(struct FMOD_SOUND *, int, unsigned int, unsigned int);
  FMOD_RESULT (__fastcall *nonblockcallback)(struct FMOD_SOUND *, FMOD_RESULT);
  const char *dlsname;
  const char *encryptionkey;
  int maxpolyphony;
  void *userdata;
  FMOD_SOUND_TYPE suggestedsoundtype;
  FMOD_RESULT (__fastcall *fileuseropen)(const char *, unsigned int *, void **, void *);
  FMOD_RESULT (__fastcall *fileuserclose)(void *, void *);
  FMOD_RESULT (__fastcall *fileuserread)(void *, void *, unsigned int, unsigned int *, void *);
  FMOD_RESULT (__fastcall *fileuserseek)(void *, unsigned int, void *);
  FMOD_RESULT (__fastcall *fileuserasyncread)(FMOD_ASYNCREADINFO *, void *);
  FMOD_RESULT (__fastcall *fileuserasynccancel)(FMOD_ASYNCREADINFO *, void *);
  void *fileuserdata;
  int filebuffersize;
  FMOD_CHANNELORDER channelorder;
  unsigned int channelmask;
  struct FMOD_SOUNDGROUP *initialsoundgroup;
  unsigned int initialseekposition;
  unsigned int initialseekpostype;
  int ignoresetfilesystem;
  unsigned int audioqueuepolicy;
  unsigned int minmidigranularity;
  int nonblockthreadid;
  FMOD_GUID *fsbguid;
};

```

### `FMODFileDescriptor`
```
struct __cppobj FMODFileDescriptor
{
  unsigned __int64 mFileSize;
  std::string mFileName;
  std::mutex mFileMutex;
};

```

### `FMODFileTracker`
```
struct __cppobj FMODFileTracker
{
  std::unordered_map<void *,std::shared_ptr<FMODFileDescriptor>> mFileDescriptorsMap;
  std::mutex mMutex;
};

```

### `FetchImageParams`
```
struct __cppobj FetchImageParams
{
  std::string mContentUrl;
};

```

### `FocusComponent`
```
struct __cppobj __declspec(align(8)) FocusComponent : UIComponent
{
  FocusManager *mFocusManager;
  int mDefaultFocusPrecedence;
  glm::tvec2<float,0> mCapturedFocusPoint;
  std::string mFocusIdentifier;
  std::unordered_map<enum ui::CardinalDirection,std::string> mDirectionalFocusOverrides;
  std::unordered_map<std::string,std::unordered_map<enum ui::CardinalDirection,std::string>> mNamedMappingLookupData;
  __int8 mFocusEnabled : 1;
  __int8 mFocusWrapEnabled : 1;
  __int8 mFocusPointCaptured : 1;
  __int8 mFocusMagnetEnabled : 1;
  __int8 mResetOnFocusLost : 1;
};

```

### `FocusComponent_vtbl`
```
struct /*VFT*/ FocusComponent_vtbl
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

### `FormattedAchievementData`
```
struct __cppobj FormattedAchievementData
{
  std::string mAchievementId;
  std::string mDisplayNames;
  std::string mDisplayDescription;
  Core::PathBuffer<std::string > mTexturePath;
  std::string mTextureLocationType;
  bool mVisibleWorldIcon;
  bool mIsLocked;
  std::string mAchievementGamerScore;
  std::string mAchievementWorldScore;
  float mProgressBar;
  const StoreCatalogItem *mPersonaReward;
  mce::UUID mPersonaRewardId;
};

```

### `FormattedPlayerStats`
```
struct __cppobj FormattedPlayerStats
{
  std::string mGamerscoreValue;
  std::string mAchievementValue;
  std::string mTimePlayedValue;
  std::string mAchievementPercentage;
};

```

### `FILE_ID_DESCRIPTOR`
```
struct FILE_ID_DESCRIPTOR
{
  unsigned int dwSize;
  _FILE_ID_TYPE Type;
  $DDC60D76A4217E10985A7D269A0E4857 ___u2;
};

```

### `FLASHWINFO`
```
struct __declspec(align(8)) FLASHWINFO
{
  unsigned int cbSize;
  HWND__ *hwnd;
  unsigned int dwFlags;
  unsigned int uCount;
  unsigned int dwTimeout;
};

```

### `FirstPersonLookBehavior`
```
struct __cppobj __declspec(align(8)) FirstPersonLookBehavior : CameraBehavior<FirstPersonLookBehavior>
{
  float mYaw;
  float mPitch;
  float mYawDelta;
  float mPitchMin;
  float mPitchMax;
};

```

### `FirstPersonLookBehavior_vtbl`
```
struct /*VFT*/ FirstPersonLookBehavior_vtbl
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

### `FlyBehavior`
```
struct __cppobj FlyBehavior : CameraBehavior<FlyBehavior>
{
  float mSpeed;
  float mSpeedAlt;
};

```

### `FlyBehavior_vtbl`
```
struct /*VFT*/ FlyBehavior_vtbl
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

### `FirstPersonLookBehaviorLoader`
```
struct __cppobj FirstPersonLookBehaviorLoader : CameraBehaviorLoader
{
};

```

### `FirstPersonLookBehaviorLoader_vtbl`
```
struct /*VFT*/ FirstPersonLookBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `FlyBehaviorLoader`
```
struct __cppobj FlyBehaviorLoader : CameraBehaviorLoader
{
};

```

### `FlyBehaviorLoader_vtbl`
```
struct /*VFT*/ FlyBehaviorLoader_vtbl
{
  void (__fastcall *~CameraBehaviorLoader)(CameraBehaviorLoader *this);
  std::unique_ptr<ICameraBehavior> *(__fastcall *create)(CameraBehaviorLoader *this, std::unique_ptr<ICameraBehavior> *result);
  void (__fastcall *parse)(CameraBehaviorLoader *this, Json::Value *, ICameraBehavior *);
};

```

### `FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearAllocation`
```
struct __cppobj FencedRingBuffer<Core::CpuRingBufferAllocation_Buffer,0>::LinearAllocation
{
  unsigned __int64 mOffsetPrefix;
  unsigned __int64 mDataOffset;
};

```

### `FireBlock`
```
struct __cppobj __declspec(align(8)) FireBlock : BlockLegacy
{
  std::unordered_map<BlockPos,std::string> mFireSourceMap;
  AABB mAabb;
};

```

### `FireBlock_vtbl`
```
struct /*VFT*/ FireBlock_vtbl
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

### `FoliageColor`
```
struct __cppobj FoliageColor
{
};

```

### `FileEntry`
```
struct FileEntry
{
  int file_id;
  unsigned int offset;
  unsigned int length;
  unsigned int origin_len;
};

```

### `FrontloadedResources`
```
struct __cppobj FrontloadedResources
{
};

```

### `FactoryComponent`
```
struct __cppobj __declspec(align(8)) FactoryComponent : UIComponent
{
  std::weak_ptr<UIControlFactory> mControlFactory;
  std::string mFactoryName;
  std::unordered_map<std::string,std::string> mControlIdToTemplateLookup;
  std::vector<std::pair<std::string const ,Json::Value const >> mVariables;
  std::shared_ptr<UIControl> mControlTemplate;
  std::vector<std::weak_ptr<UIControl>> mProgeny;
  bool mFactoryIsChild;
  int mMaxSize;
  _BYTE mInsertPosition[4];
};

```

### `FactoryComponent_vtbl`
```
struct /*VFT*/ FactoryComponent_vtbl
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

### `FocusContainerCustomData`
```
struct __cppobj FocusContainerCustomData
{
  std::string otherFocusContainerName;
  std::string focusIdInside;
};

```

### `FocusContainerComponent`
```
struct __cppobj __declspec(align(8)) FocusContainerComponent : UIComponent
{
  RecentFocusVector mRecentFocusList;
  std::weak_ptr<UIControl> mLastFocusedControl;
  std::unordered_map<enum ui::CardinalDirection,enum FocusNavigationMode> mDirectionalFocusOverrides;
  std::unordered_map<enum ui::CardinalDirection,std::vector<FocusContainerCustomData>> mFocusContainerCustomOverrides;
  bool mUseLastFocus;
  bool mWrappingAllowed;
};

```

### `FocusContainerComponent_vtbl`
```
struct /*VFT*/ FocusContainerComponent_vtbl
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

### `FocusComponent::_captureFocusPoint::__l2::<lambda_0e51f1eba29be0dc80ad7fe30da0fb50>`
```
struct __cppobj FocusComponent::_captureFocusPoint::__l2::<lambda_0e51f1eba29be0dc80ad7fe30da0fb50>
{
  const UIControl *owner;
};

```

### `FactoryComponent::create::__l52::<lambda_98dfe690793ad1dd20aceb51ef2d7967>`
```
struct __cppobj FactoryComponent::create::__l52::<lambda_98dfe690793ad1dd20aceb51ef2d7967>
{
  const UIPropertyBag *properties;
};

```

### `FlyingItemRenderer`
```
struct __cppobj FlyingItemRenderer : MinecraftUICustomRenderer
{
  std::vector<ui::FlyingItem> mFlyingItems;
};

```

### `FlyingItemRenderer_vtbl`
```
struct /*VFT*/ FlyingItemRenderer_vtbl
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

### `FileDeleteProgressHandler`
```
struct __cppobj __declspec(align(8)) FileDeleteProgressHandler : ProgressHandler
{
  ContentManager *mContentManager;
  std::vector<ContentItem const *> mToDelete;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  bool mDeleteComplete;
};

```

### `FileDeleteProgressHandler_vtbl`
```
struct /*VFT*/ FileDeleteProgressHandler_vtbl
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

### `FontAlias`
```
struct __cppobj __declspec(align(8)) FontAlias : Font
{
  std::vector<FontAlias::ReferenceData> mFontReferences;
  std::string mCurrentLanguageCode;
  bool mAllReferencesMaterialsCanBeOverridden;
  bool mAllReferencesScreenPixelAligned;
  bool mAllReferencesSupportShadowInSingleDraw;
  float mMaxWrapHeight;
  float mMaxScalar;
};

```

### `FontAlias_vtbl`
```
struct /*VFT*/ FontAlias_vtbl
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
};

```

### `FT_MemoryRec_`
```
struct FT_MemoryRec_
{
  void *user;
  void *(__fastcall *alloc)(FT_MemoryRec_ *, int);
  void (__fastcall *free)(FT_MemoryRec_ *, void *);
  void *(__fastcall *realloc)(FT_MemoryRec_ *, int, int, void *);
};

```

### `FT_StreamRec_`
```
struct FT_StreamRec_
{
  unsigned __int8 *base;
  unsigned int size;
  unsigned int pos;
  FT_StreamDesc_ descriptor;
  FT_StreamDesc_ pathname;
  unsigned int (__fastcall *read)(FT_StreamRec_ *, unsigned int, unsigned __int8 *, unsigned int);
  void (__fastcall *close)(FT_StreamRec_ *);
  FT_MemoryRec_ *memory;
  unsigned __int8 *cursor;
  unsigned __int8 *limit;
};

```

### `FT_ListNodeRec_`
```
struct FT_ListNodeRec_
{
  FT_ListNodeRec_ *prev;
  FT_ListNodeRec_ *next;
  void *data;
};

```

### `FT_Bitmap_Size_`
```
struct FT_Bitmap_Size_
{
  __int16 height;
  __int16 width;
  int size;
  int x_ppem;
  int y_ppem;
};

```

### `FT_ModuleRec_`
```
struct FT_ModuleRec_
{
  FT_Module_Class_ *clazz;
  FT_LibraryRec_ *library;
  FT_MemoryRec_ *memory;
};

```

### `FT_LibraryRec_`
```
struct __declspec(align(8)) FT_LibraryRec_
{
  FT_MemoryRec_ *memory;
  int version_major;
  int version_minor;
  int version_patch;
  unsigned int num_modules;
  FT_ModuleRec_ *modules[32];
  FT_ListRec_ renderers;
  FT_RendererRec_ *cur_renderer;
  FT_ModuleRec_ *auto_hinter;
  int (__fastcall *debug_hooks[4])(void *);
  FT_Vector_ lcd_geometry[3];
  int refcount;
};

```

### `FT_RendererRec_`
```
struct FT_RendererRec_
{
  FT_ModuleRec_ root;
  FT_Renderer_Class_ *clazz;
  FT_Glyph_Format_ glyph_format;
  FT_Glyph_Class_ glyph_class;
  struct FT_RasterRec_ *raster;
  int (__fastcall *raster_render)(struct FT_RasterRec_ *, const FT_Raster_Params_ *);
  int (__fastcall *render)(FT_RendererRec_ *, FT_GlyphSlotRec_ *, FT_Render_Mode_, const FT_Vector_ *);
};

```

### `FT_FaceRec_`
```
struct FT_FaceRec_
{
  int num_faces;
  int face_index;
  int face_flags;
  int style_flags;
  int num_glyphs;
  char *family_name;
  char *style_name;
  int num_fixed_sizes;
  FT_Bitmap_Size_ *available_sizes;
  int num_charmaps;
  FT_CharMapRec_ **charmaps;
  FT_Generic_ generic;
  FT_BBox_ bbox;
  unsigned __int16 units_per_EM;
  __int16 ascender;
  __int16 descender;
  __int16 height;
  __int16 max_advance_width;
  __int16 max_advance_height;
  __int16 underline_position;
  __int16 underline_thickness;
  FT_GlyphSlotRec_ *glyph;
  FT_SizeRec_ *size;
  FT_CharMapRec_ *charmap;
  FT_DriverRec_ *driver;
  FT_MemoryRec_ *memory;
  FT_StreamRec_ *stream;
  FT_ListRec_ sizes_list;
  FT_Generic_ autohint;
  void *extensions;
  FT_Face_InternalRec_ *internal;
};

```

### `FT_Size_Metrics_`
```
struct FT_Size_Metrics_
{
  unsigned __int16 x_ppem;
  unsigned __int16 y_ppem;
  int x_scale;
  int y_scale;
  int ascender;
  int descender;
  int height;
  int max_advance;
};

```

### `FT_Size_InternalRec_`
```
struct FT_Size_InternalRec_
{
  void *module_data;
  FT_Render_Mode_ autohint_mode;
  FT_Size_Metrics_ autohint_metrics;
};

```

### `FT_SizeRec_`
```
struct FT_SizeRec_
{
  FT_FaceRec_ *face;
  FT_Generic_ generic;
  FT_Size_Metrics_ metrics;
  FT_Size_InternalRec_ *internal;
};

```

### `FT_Parameter_`
```
struct FT_Parameter_
{
  unsigned int tag;
  void *data;
};

```

### `FT_SubGlyphRec_`
```
struct FT_SubGlyphRec_
{
  int index;
  unsigned __int16 flags;
  int arg1;
  int arg2;
  FT_Matrix_ transform;
};

```

### `FT_GlyphLoadRec_`
```
struct FT_GlyphLoadRec_
{
  FT_Outline_ outline;
  FT_Vector_ *extra_points;
  FT_Vector_ *extra_points2;
  unsigned int num_subglyphs;
  FT_SubGlyphRec_ *subglyphs;
};

```

### `FT_GlyphLoaderRec_`
```
struct FT_GlyphLoaderRec_
{
  FT_MemoryRec_ *memory;
  unsigned int max_points;
  unsigned int max_contours;
  unsigned int max_subglyphs;
  unsigned __int8 use_extra;
  FT_GlyphLoadRec_ base;
  FT_GlyphLoadRec_ current;
  void *other;
};

```

### `FT_DriverRec_`
```
struct FT_DriverRec_
{
  FT_ModuleRec_ root;
  FT_Driver_ClassRec_ *clazz;
  FT_ListRec_ faces_list;
  FT_GlyphLoaderRec_ *glyph_loader;
};

```

### `FT_ServiceCacheRec_`
```
struct FT_ServiceCacheRec_
{
  void *service_POSTSCRIPT_FONT_NAME;
  void *service_MULTI_MASTERS;
  void *service_METRICS_VARIATIONS;
  void *service_GLYPH_DICT;
  void *service_PFR_METRICS;
  void *service_WINFNT;
};

```

### `FT_Incremental_MetricsRec_`
```
struct FT_Incremental_MetricsRec_
{
  int bearing_x;
  int bearing_y;
  int advance;
  int advance_v;
};

```

### `FT_Incremental_FuncsRec_`
```
const struct FT_Incremental_FuncsRec_
{
  int (__fastcall *get_glyph_data)(struct FT_IncrementalRec_ *, unsigned int, FT_Data_ *);
  void (__fastcall *free_glyph_data)(struct FT_IncrementalRec_ *, FT_Data_ *);
  int (__fastcall *get_glyph_metrics)(struct FT_IncrementalRec_ *, unsigned int, unsigned __int8, FT_Incremental_MetricsRec_ *);
};

```

### `FT_Incremental_InterfaceRec_`
```
struct FT_Incremental_InterfaceRec_
{
  const FT_Incremental_FuncsRec_ *funcs;
  struct FT_IncrementalRec_ *object;
};

```

### `FT_Face_InternalRec_`
```
struct __declspec(align(8)) FT_Face_InternalRec_
{
  FT_Matrix_ transform_matrix;
  FT_Vector_ transform_delta;
  int transform_flags;
  FT_ServiceCacheRec_ services;
  FT_Incremental_InterfaceRec_ *incremental_interface;
  char no_stem_darkening;
  int random_seed;
  int refcount;
};

```

### `FT_Slot_InternalRec_`
```
struct __declspec(align(8)) FT_Slot_InternalRec_
{
  FT_GlyphLoaderRec_ *loader;
  unsigned int flags;
  unsigned __int8 glyph_transformed;
  FT_Matrix_ glyph_matrix;
  FT_Vector_ glyph_delta;
  void *glyph_hints;
  int load_flags;
};

```

### `FT_GlyphRec_`
```
struct __declspec(align(8)) FT_GlyphRec_
{
  FT_LibraryRec_ *library;
  const FT_Glyph_Class_ *clazz;
  FT_Glyph_Format_ format;
  FT_Vector_ advance;
};

```

### `FontRepository::parseAndLoadMetadataFonts::__l2::<lambda_88925860aafd3405404c7e1df5755f91>`
```
struct __cppobj FontRepository::parseAndLoadMetadataFonts::__l2::<lambda_88925860aafd3405404c7e1df5755f91>
{
  FontRepository *const __this;
  std::shared_ptr<std::vector<std::shared_ptr<Font>> > fontsLoaded;
};

```

### `FontRepository::parseAndLoadMetadataFonts::__l2::<lambda_31bdad871b22ac7caa6a500c31451947>`
```
struct __cppobj FontRepository::parseAndLoadMetadataFonts::__l2::<lambda_31bdad871b22ac7caa6a500c31451947>
{
  FontRepository *const __this;
  mce::TextureGroup *textureGroup;
  std::shared_ptr<std::vector<std::shared_ptr<Font>> > fontsLoaded;
};

```

### `FontRepository::loadDefaultFonts::__l2::<lambda_7fe000d9f42c358f49b7b7b1aeed026a>::()::__l2::<lambda_ac0252748f91156e691c7d207fae26a9>`
```
struct __cppobj FontRepository::loadDefaultFonts::__l2::<lambda_7fe000d9f42c358f49b7b7b1aeed026a>::()::__l2::<lambda_ac0252748f91156e691c7d207fae26a9>
{
  const std::string alias;
  const Core::Path fontPagePrefix;
  std::shared_ptr<std::shared_ptr<MSDFFont> > loadedFont;
  mce::TextureGroup *textureGroup;
};

```

### `FontRepository::loadDefaultFonts::__l2::<lambda_4f422798d8e19b20911552d15f97b207>::()::__l2::<lambda_97de77aa165493b1e2383fa55c9aadef>`
```
struct __cppobj FontRepository::loadDefaultFonts::__l2::<lambda_4f422798d8e19b20911552d15f97b207>::()::__l2::<lambda_97de77aa165493b1e2383fa55c9aadef>
{
  const std::string alias;
  const Core::Path asciiName;
  const Core::Path unicodeName;
  std::shared_ptr<std::shared_ptr<BitmapFont> > loadedFont;
  mce::TextureGroup *textureGroup;
};

```

### `Font::getTextHeight::__l2::<lambda_1e8f76698c9e82e8bd78f1bc5facf7f6>`
```
struct __cppobj Font::getTextHeight::__l2::<lambda_1e8f76698c9e82e8bd78f1bc5facf7f6>
{
};

```

### `Font::_drawWordWrap::__l2::<lambda_109e8cc2ec8061788bcb30eaf502d4f4>`
```
struct __cppobj Font::_drawWordWrap::__l2::<lambda_109e8cc2ec8061788bcb30eaf502d4f4>
{
  std::string *text;
};

```

### `FileDeleteProgressHandler::onStart::__l2::<lambda_f66a9fb0340462681c16b2ec2802629e>`
```
struct __cppobj FileDeleteProgressHandler::onStart::__l2::<lambda_f66a9fb0340462681c16b2ec2802629e>
{
  MinecraftScreenModel *minecraftScreenModel;
  FileDeleteProgressHandler *const __this;
};

```

### `FileDeleteProgressHandler::onStart::__l2::<lambda_d001b78764dbe0c23a6aa3eb590da16a>`
```
struct __cppobj FileDeleteProgressHandler::onStart::__l2::<lambda_d001b78764dbe0c23a6aa3eb590da16a>
{
  FileDeleteProgressHandler *const __this;
};

```

### `FileCopyProgressHandler`
```
struct __cppobj FileCopyProgressHandler : ProgressHandler
{
  std::string mTitle;
  Core::PathBuffer<std::string > mDestPath;
  std::shared_ptr<bool> mExistenceTracker;
  std::function<void __cdecl(bool)> mCallback;
  std::unique_ptr<TaskGroup> mIOTaskGroup;
  ResourceLocation mSrcLocation;
  bool mSrcZip;
  bool mDestZip;
  bool mCopyComplete;
  bool mCopySuccess;
  std::vector<std::string> mExcludeDirs;
};

```

### `FileCopyProgressHandler_vtbl`
```
struct /*VFT*/ FileCopyProgressHandler_vtbl
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

### `FileCopyProgressHandler::onStart::__l2::<lambda_845c8ae8b621017e79b44eea229b9484>`
```
struct __cppobj FileCopyProgressHandler::onStart::__l2::<lambda_845c8ae8b621017e79b44eea229b9484>
{
  std::weak_ptr<bool> weak_existence;
  FileCopyProgressHandler *const __this;
};

```

### `FileAccessTransforms_vtbl`
```
struct /*VFT*/ FileAccessTransforms_vtbl
{
  void (__fastcall *~FileAccessTransforms)(FileAccessTransforms *this);
  bool (__fastcall *readTransform)(FileAccessTransforms *this, std::vector<unsigned char> *);
  bool (__fastcall *writeTransform)(FileAccessTransforms *this, std::vector<unsigned char> *);
};

```

### `FilteredContainerModel`
```
struct __cppobj FilteredContainerModel : ExpandoContainerModel
{
  bool mDoExpandoGroups;
  bool mIsFiltering;
  int mFilteredItemCount;
  std::vector<std::pair<ItemInstance,unsigned int>> mSavedItems;
  std::vector<std::pair<ItemInstance,unsigned int>> mActiveFilteredExpandableSetHeads;
  std::function<enum FilterResult __cdecl(ItemInstance const &)> mFilterRule;
};

```

### `FilteredContainerModel_vtbl`
```
struct /*VFT*/ FilteredContainerModel_vtbl
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
  void (__fastcall *setItemInstance)(ExpandoContainerModel *this, int, const ItemInstance *);
  void (__fastcall *refreshContainer)(ExpandoContainerModel *this, bool);
};

```

### `FloatOption`
```
struct __cppobj __declspec(align(8)) FloatOption : Option
{
  const float VALUE_MIN;
  const float VALUE_MAX;
  float mValue;
  float mDefaultValue;
  const float DELTA;
};

```

### `FloatOption_vtbl`
```
struct /*VFT*/ FloatOption_vtbl
{
  void (__fastcall *~Option)(Option *this);
  void (__fastcall *save)(Option *this, std::vector<std::pair<std::string,std::string >> *);
  void (__fastcall *load)(Option *this, const Json::Value *);
  void (__fastcall *load)(Option *this, std::map<std::string,std::string> *);
  void (__fastcall *load)(Option *this, const std::string *);
};

```

### `FeedbackPromptController`
```
struct __cppobj FeedbackPromptController : ClientInstanceScreenController
{
  const std::string mTitleId;
  const std::string mImage;
  const std::string mButtonName;
};

```

### `FeedbackPromptController_vtbl`
```
struct /*VFT*/ FeedbackPromptController_vtbl
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

### `FileDownloadScreenController::RealmData`
```
struct __cppobj FileDownloadScreenController::RealmData
{
  std::string realmID;
  std::string realmName;
  std::string realmVersion;
  std::string realmVersionName;
};

```

### `FileDownloadScreenController`
```
struct __cppobj __declspec(align(8)) FileDownloadScreenController : MainMenuScreenController
{
  FileDownloadScreenController::RealmData mRealmData;
  float mDownloadProgress;
  bool mContinueOnWifi;
  bool mWifiWarningDisplaying;
  bool mDownloadStarted;
  bool mIsWaitingForCancel;
  DownloadState mDownloadState;
};

```

### `FileDownloadScreenController_vtbl`
```
struct /*VFT*/ FileDownloadScreenController_vtbl
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

### `FileUploadScreenController`
```
struct __cppobj FileUploadScreenController : MainMenuScreenController
{
  std::string mRealmdID;
  std::string mFileID;
  bool mNeedArchiving;
  float mUploadProgress;
  bool mContinueOnWifi;
  bool mWifiWarningDisplaying;
  bool mUploadStarted;
  UploadState mUploadState;
  Core::FileUploadType mFileUploadType;
  std::function<void __cdecl(enum UploadState)> mCallback;
  std::shared_ptr<FileUploadManager> mFileUploadManager;
};

```

### `FileUploadScreenController_vtbl`
```
struct /*VFT*/ FileUploadScreenController_vtbl
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

### `FurnaceScreenControllerProxyCallbacks::<lambda_68069f7fbd4730b8b6a4b64cd4ec15f3>`
```
struct __cppobj FurnaceScreenControllerProxyCallbacks::<lambda_68069f7fbd4730b8b6a4b64cd4ec15f3>
{
};

```

### `FurnaceScreenControllerProxyCallbacks::<lambda_9f2f11c7cc5957bbdf8a1f458419fc5b>`
```
struct __cppobj FurnaceScreenControllerProxyCallbacks::<lambda_9f2f11c7cc5957bbdf8a1f458419fc5b>
{
};

```

### `FurnaceScreenControllerProxyCallbacks::<lambda_6e9c8476017789a33bb2e3f39ef6501b>`
```
struct __cppobj FurnaceScreenControllerProxyCallbacks::<lambda_6e9c8476017789a33bb2e3f39ef6501b>
{
};

```

### `FurnaceScreenControllerProxy`
```
struct __cppobj FurnaceScreenControllerProxy : ScreenControllerProxy
{
  const FurnaceScreenControllerProxyCallbacks mCallbacks;
};

```

### `FurnaceScreenControllerProxy_vtbl`
```
struct /*VFT*/ FurnaceScreenControllerProxy_vtbl
{
  void (__fastcall *~ScreenControllerProxy)(ScreenControllerProxy *this);
};

```

### `FileUploadScreenController::_displayUploadErrorPopup::__l2::<lambda_56479a187dcfd6ee8d9902a0e71991b4>`
```
struct __cppobj FileUploadScreenController::_displayUploadErrorPopup::__l2::<lambda_56479a187dcfd6ee8d9902a0e71991b4>
{
  std::weak_ptr<FileUploadScreenController> weakThis;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_8ee8e9c67e75344676445575aa03028f>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_8ee8e9c67e75344676445575aa03028f>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_a41320f59fb4cdb7cf30ce6c99707a59>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_a41320f59fb4cdb7cf30ce6c99707a59>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_5d144608546dbfd12362935a26df5fe2>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_5d144608546dbfd12362935a26df5fe2>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_e9304b7a424ecfbe227e796bc2e63013>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_e9304b7a424ecfbe227e796bc2e63013>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_33c32188ae4ce4f1a02432932a76c7c1>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_33c32188ae4ce4f1a02432932a76c7c1>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_53068d20d0cb864e1047432b0d9cdc33>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_53068d20d0cb864e1047432b0d9cdc33>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_cdf8cce4febf7d2f4dae8b6771bbb5b0>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_cdf8cce4febf7d2f4dae8b6771bbb5b0>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_6218337b9af756811c5a0c44f91959a1>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_6218337b9af756811c5a0c44f91959a1>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_590fca01935110f4321c59eab36a6688>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_590fca01935110f4321c59eab36a6688>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_63c99c602725913d46f15e1db4705954>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_63c99c602725913d46f15e1db4705954>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_44e7db5e29f5d557c5a0fc50a4e0360e>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_44e7db5e29f5d557c5a0fc50a4e0360e>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_bec49fcaff1cdd081d60664ec8b895ec>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_bec49fcaff1cdd081d60664ec8b895ec>
{
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_b5162ffa6e174b6687e4fce666835e1e>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_b5162ffa6e174b6687e4fce666835e1e>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_82b9e20ea4e5e480bc08d809da2c4815>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_82b9e20ea4e5e480bc08d809da2c4815>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_b00c115ac684d8c7428ecfbed066a03c>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_b00c115ac684d8c7428ecfbed066a03c>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerBindings::__l2::<lambda_9a195338068e0741805c9ba0c4634bf4>`
```
struct __cppobj FileUploadScreenController::_registerBindings::__l2::<lambda_9a195338068e0741805c9ba0c4634bf4>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerEventHandlers::__l2::<lambda_10f62041708a9870311deb91f897c1bf>`
```
struct __cppobj FileUploadScreenController::_registerEventHandlers::__l2::<lambda_10f62041708a9870311deb91f897c1bf>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerEventHandlers::__l2::<lambda_a0267568ae2a9f2a627ec27bf4e9481e>`
```
struct __cppobj FileUploadScreenController::_registerEventHandlers::__l2::<lambda_a0267568ae2a9f2a627ec27bf4e9481e>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_registerEventHandlers::__l2::<lambda_c32e1d45ca7729f5575d04896f9c582d>`
```
struct __cppobj FileUploadScreenController::_registerEventHandlers::__l2::<lambda_c32e1d45ca7729f5575d04896f9c582d>
{
  FileUploadScreenController *const __this;
};

```

### `FileUploadScreenController::_startUpload::__l13::<lambda_2d9bac4d3ebd66077c58a3e88c390363>`
```
struct __cppobj FileUploadScreenController::_startUpload::__l13::<lambda_2d9bac4d3ebd66077c58a3e88c390363>
{
  std::weak_ptr<FileUploadScreenController> weakThis;
};

```

### `FileDownloadScreenController::_displayDownloadErrorPopup::__l2::<lambda_016f9441dc96df5e1212767102cffed0>`
```
struct __cppobj FileDownloadScreenController::_displayDownloadErrorPopup::__l2::<lambda_016f9441dc96df5e1212767102cffed0>
{
  std::weak_ptr<FileDownloadScreenController> weakThis;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_7da7beb6a65d54a1547704035d2c60dd>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_7da7beb6a65d54a1547704035d2c60dd>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_6392fad553f144397ab5bcc2a1d34410>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_6392fad553f144397ab5bcc2a1d34410>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_d634eb97b82394f3e97dcded9545e06c>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_d634eb97b82394f3e97dcded9545e06c>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_bf7ee73a20735c45f364febe848a40dc>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_bf7ee73a20735c45f364febe848a40dc>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_da21480f755e865b17249a84b077e41e>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_da21480f755e865b17249a84b077e41e>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_9d75819f3dfd579957095ef2ceb945c5>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_9d75819f3dfd579957095ef2ceb945c5>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_f99f8a6b71a89bd7283c91f2e01d22cc>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_f99f8a6b71a89bd7283c91f2e01d22cc>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_d9aab4afec3fedb3c12b0897b272bc41>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_d9aab4afec3fedb3c12b0897b272bc41>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_b60d51e9e7c65f65d9f81d6be7ae464e>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_b60d51e9e7c65f65d9f81d6be7ae464e>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_996752e5deef7428293288b78e380631>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_996752e5deef7428293288b78e380631>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_b1ff2e52ed7aa2dee4b9f89ce6c1d862>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_b1ff2e52ed7aa2dee4b9f89ce6c1d862>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_05336d8bcda55d6e0b4f646905c793e0>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_05336d8bcda55d6e0b4f646905c793e0>
{
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_316a697dff604b8b60e9d793ceae3786>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_316a697dff604b8b60e9d793ceae3786>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_498a0262eabc38b6226b47f518d4c077>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_498a0262eabc38b6226b47f518d4c077>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_07f3a1b857c8b974fed3caa7b4f0db34>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_07f3a1b857c8b974fed3caa7b4f0db34>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerBindings::__l2::<lambda_271488a91b26a46f85ad51579d06d1a4>`
```
struct __cppobj FileDownloadScreenController::_registerBindings::__l2::<lambda_271488a91b26a46f85ad51579d06d1a4>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_44f09b874ee9fcdf631c347a92c94060>`
```
struct __cppobj FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_44f09b874ee9fcdf631c347a92c94060>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_cd96aaa67025ff6782d0910f7df6f119>`
```
struct __cppobj FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_cd96aaa67025ff6782d0910f7df6f119>
{
  FileDownloadScreenController *const __this;
};

```

### `FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_74500b1f1908729aafc9a10e57877dd5>`
```
struct __cppobj FileDownloadScreenController::_registerEventHandlers::__l2::<lambda_74500b1f1908729aafc9a10e57877dd5>
{
  FileDownloadScreenController *const __this;
};

```

### `FeedbackPromptController::_registerBindings::__l2::<lambda_bbece4f512b264b74faf5ba26b7d54aa>`
```
struct __cppobj FeedbackPromptController::_registerBindings::__l2::<lambda_bbece4f512b264b74faf5ba26b7d54aa>
{
  FeedbackPromptController *const __this;
};

```

### `FeedbackPromptController::_registerBindings::__l2::<lambda_5e849c6e2f41680228c07a77ce688bfb>`
```
struct __cppobj FeedbackPromptController::_registerBindings::__l2::<lambda_5e849c6e2f41680228c07a77ce688bfb>
{
  FeedbackPromptController *const __this;
};

```

### `FeedbackPromptController::_registerBindings::__l2::<lambda_b03504ae3a90eba43bc483a487f7bf8e>`
```
struct __cppobj FeedbackPromptController::_registerBindings::__l2::<lambda_b03504ae3a90eba43bc483a487f7bf8e>
{
  FeedbackPromptController *const __this;
};

```

### `FeedbackPromptController::_registerEventHandlers::__l2::<lambda_64f43d278793f4163eaa5b14f6e2ef4e>`
```
struct __cppobj FeedbackPromptController::_registerEventHandlers::__l2::<lambda_64f43d278793f4163eaa5b14f6e2ef4e>
{
  FeedbackPromptController *const __this;
};

```

### `FeedbackPromptController::_registerEventHandlers::__l2::<lambda_e5d09be02c5d2616caaafaec652597f8>`
```
struct __cppobj FeedbackPromptController::_registerEventHandlers::__l2::<lambda_e5d09be02c5d2616caaafaec652597f8>
{
  FeedbackPromptController *const __this;
};

```

### `FaceDirectionalActorBlock`
```
struct __cppobj FaceDirectionalActorBlock : ActorBlock
{
  bool mHorizontalOnly;
  float mYRotOffset;
};

```

### `FaceDirectionalActorBlock_vtbl`
```
struct /*VFT*/ FaceDirectionalActorBlock_vtbl
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

### `FormJsonValidator`
```
struct __cppobj FormJsonValidator
{
};

```

### `FilterCollection`
```
struct __cppobj __declspec(align(8)) FilterCollection
{
  std::string mPrefix;
  StoreFilter::MenuScreenType mScreenType;
  std::vector<StoreFilter::Toggle> mCollection;
  unsigned int mSelectedCount;
  unsigned int mDirty;
  bool mOneFilterSelection;
};

```

### `FocusManager::updatePendingFocusControl::__l2::<lambda_2e50f233adf9bc85cb1c5a5ad8433623>`
```
struct __cppobj FocusManager::updatePendingFocusControl::__l2::<lambda_2e50f233adf9bc85cb1c5a5ad8433623>
{
};

```

### `FocusManager::_sweepToNextFocusObject::__l26::<lambda_fd9f72a95693dd52737e0c11d36d84ac>`
```
struct __cppobj FocusManager::_sweepToNextFocusObject::__l26::<lambda_fd9f72a95693dd52737e0c11d36d84ac>
{
};

```

### `FocusManager::{ctor}::__l2::<lambda_db482c4c922ab9a00f2e95c83a532c5b>`
```
struct __cppobj FocusManager::{ctor}::__l2::<lambda_db482c4c922ab9a00f2e95c83a532c5b>
{
  FocusManager *const __this;
};

```

### `FullScreenEffectRenderer`
```
struct __cppobj FullScreenEffectRenderer : AppPlatformListener
{
  std::unordered_map<unsigned int,mce::Mesh> mMeshes;
  mce::Mesh mHeadlockedOverlayMesh;
  mce::Mesh mHeadlockedOverlayMeshFill;
  mce::TexturePtr mAtlasTexture;
  mce::TexturePtr mPumpkinTex;
  mce::MaterialPtr mFullscreenCubeOpaqueMaterial;
  mce::MaterialPtr mFullscreenCubeBlendMaterial;
};

```

### `FullScreenEffectRenderer_vtbl`
```
struct /*VFT*/ FullScreenEffectRenderer_vtbl
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

### `FirstChargeInfo`
```
struct __cppobj FirstChargeInfo
{
  bool mIsBuy;
  std::string mTextureUrl;
  std::string mTextureMD5;
  std::unique_ptr<ResourceLocation> mResourceLocation;
};

```

### `FoldMeuScreenController`
```
struct __cppobj FoldMeuScreenController : MinecraftScreenController
{
  bool isInit;
  const std::string mScreenName;
};

```

### `FoldMeuScreenController_vtbl`
```
struct /*VFT*/ FoldMeuScreenController_vtbl
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

### `FlameParticle`
```
struct __cppobj __declspec(align(8)) FlameParticle : Particle
{
  float oSize;
};

```

### `FlameParticle_vtbl`
```
struct /*VFT*/ FlameParticle_vtbl
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

### `FireworksStarter`
```
struct __cppobj FireworksStarter : Particle
{
  ParticleEngine *mEngine;
  std::unique_ptr<CompoundTag> mTag;
  const ListTag *mExplosions;
  bool mTwinkleDelay;
  Level *mLevel;
};

```

### `FireworksStarter_vtbl`
```
struct /*VFT*/ FireworksStarter_vtbl
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

### `FireworkChargeItem`
```
struct __cppobj FireworkChargeItem : Item
{
};

```

### `FireworksItem`
```
struct __cppobj FireworksItem : Item
{
};

```

### `FireworksSparkParticle`
```
struct __cppobj FireworksSparkParticle : Particle
{
  bool mTrail;
  bool mFlicker;
  bool mHasFade;
  int mBaseTex;
  int mSpriteCount;
  Level *mLevel;
  mce::Color mFade;
};

```

### `FireworksSparkParticle_vtbl`
```
struct /*VFT*/ FireworksSparkParticle_vtbl
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

### `FireworksOverlayParticle`
```
struct __cppobj FireworksOverlayParticle : Particle
{
};

```

### `FireworksOverlayParticle_vtbl`
```
struct /*VFT*/ FireworksOverlayParticle_vtbl
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

### `FallingDustParticle`
```
struct __cppobj __declspec(align(4)) FallingDustParticle : Particle
{
  float oSize;
  const int maxLifetime;
  float rotSpeed;
  bool insideBlock;
};

```

### `FallingDustParticle_vtbl`
```
struct /*VFT*/ FallingDustParticle_vtbl
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

### `FoodItemComponent::SaturationModifier`
```
struct __cppobj FoodItemComponent::SaturationModifier
{
  float mSaturationValue;
};

```

### `FoodItemComponent`
```
struct __cppobj FoodItemComponent : ItemComponent, IFoodItemComponent
{
  int mNutrition;
  FoodItemComponent::SaturationModifier mSaturationModifier;
  ItemDescriptor mUsingConvertsTo;
  bool mCanAlwaysEat;
  DefinitionTrigger mOnConsume;
};

```

### `FoodItemComponent_vtbl`
```
struct /*VFT*/ FoodItemComponent_vtbl
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

### `FallingBlockRenderer`
```
struct __cppobj FallingBlockRenderer : ActorRenderer
{
  BlockTessellator *mBlockTessellator;
  mce::MaterialPtr mHeavyBlockMaterial;
  mce::MaterialPtr mHeavyBlockMaterialWithColor;
};

```

### `FallingBlockRenderer_vtbl`
```
struct /*VFT*/ FallingBlockRenderer_vtbl
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

### `FallingBlock`
```
struct __cppobj __declspec(align(8)) FallingBlock : PredictableProjectile
{
  bool mCreative;
  FallingBlock::State mState;
  int mWaitTicks;
  int mTime;
  bool mCancelDrop;
  bool mHurtEntities;
  int mFallDamageMax;
  float mFallDamageAmount;
  std::unique_ptr<CompoundTag> mFallingBlockSerId;
  NewBlockID mFallingBlockId;
  unsigned __int16 mFallingBlockData;
};

```

### `FallingBlock_vtbl`
```
struct /*VFT*/ FallingBlock_vtbl
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
};

```

### `FreezeOnHitSubcomponent`
```
struct __cppobj __declspec(align(8)) FreezeOnHitSubcomponent : OnHitSubcomponent
{
  FreezeOnHitSubcomponent::Shape mShape;
  float mSize;
  bool mSnapToBlock;
};

```

### `FreezeOnHitSubcomponent_vtbl`
```
struct /*VFT*/ FreezeOnHitSubcomponent_vtbl
{
  void (__fastcall *~OnHitSubcomponent)(OnHitSubcomponent *this);
  void (__fastcall *readfromJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *writetoJSON)(OnHitSubcomponent *this, Json::Value *);
  void (__fastcall *doOnHitEffect)(OnHitSubcomponent *this, Actor *, ProjectileComponent *);
  const char *(__fastcall *getName)(OnHitSubcomponent *this);
};

```

### `FenceBlock`
```
struct __cppobj FenceBlock : BlockLegacy
{
};

```

### `FenceBlock_vtbl`
```
struct /*VFT*/ FenceBlock_vtbl
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

### `FlowerPotBlock`
```
struct __cppobj FlowerPotBlock : ActorBlock
{
};

```

### `FlowerPotBlock_vtbl`
```
struct /*VFT*/ FlowerPotBlock_vtbl
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

### `FlowerPotBlockActor`
```
struct __cppobj FlowerPotBlockActor : BlockActor
{
  const Block *mPlant;
};

```

### `FlowerPotBlockActor_vtbl`
```
struct /*VFT*/ FlowerPotBlockActor_vtbl
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

### `FaceDirectionalComponentDescription`
```
struct __cppobj __declspec(align(8)) FaceDirectionalComponentDescription : BlockComponentDescription
{
  bool mHorizontalOnly;
};

```

### `FaceDirectionalComponentDescription_vtbl`
```
struct /*VFT*/ FaceDirectionalComponentDescription_vtbl
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

### `FaceDirectionalComponent`
```
struct __cppobj FaceDirectionalComponent
{
  BlockLegacy *mBlockLegacy;
  bool mHorizontalOnly;
  float mYRotOffset;
};

```

### `FileSizeRequest`
```
struct __cppobj FileSizeRequest : RequestHandler
{
  const std::string mContentUrl;
  std::function<void __cdecl(unsigned __int64)> mCallback;
  std::shared_ptr<unsigned __int64> mContentLength;
};

```

### `FileSizeRequest_vtbl`
```
struct /*VFT*/ FileSizeRequest_vtbl
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

### `FileImageRequest`
```
struct __cppobj FileImageRequest : FileDataRequest
{
};

```

### `FileImageRequest_vtbl`
```
struct /*VFT*/ FileImageRequest_vtbl
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

### `FlightingResponse`
```
const struct __cppobj FlightingResponse
{
  std::vector<std::string> mTreatments;
  std::vector<std::string> mProgressions;
};

```

### `FlightingRequest::CacheMetadata`
```
struct __cppobj FlightingRequest::CacheMetadata
{
  std::string mEntityTag;
};

```

### `FlightingRequest`
```
struct __cppobj FlightingRequest : CachedRequest
{
  const std::string mClientId;
  const std::string mCurrentLanguage;
  const std::string mHostUrl;
  std::function<void __cdecl(FlightingResponse const &)> mCallback;
  FlightingResponse mFlightingResponse;
  FlightingRequest::CacheMetadata mCacheMetadata;
};

```

### `FlightingRequest_vtbl`
```
struct /*VFT*/ FlightingRequest_vtbl
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

### `FlightingToggles::{ctor}::__l2::<lambda_38d0b82f17466d32b7c7c17849ffae66>`
```
struct __cppobj FlightingToggles::{ctor}::__l2::<lambda_38d0b82f17466d32b7c7c17849ffae66>
{
  FlightingToggles *const __this;
};

```

### `FileTTSOutput`
```
struct __cppobj FileTTSOutput : TTSOutputInterface
{
  std::function<Core::PathBuffer<std::string > __cdecl(void)> mOutputPathCallback;
};

```

### `FileTTSOutput_vtbl`
```
struct /*VFT*/ FileTTSOutput_vtbl
{
  void (__fastcall *~TTSOutputInterface)(TTSOutputInterface *this);
  void (__fastcall *synthesizeAndOutput)(TTSOutputInterface *this, const std::string *, cst_voice_struct *);
  void (__fastcall *stop)(TTSOutputInterface *this);
  bool (__fastcall *isIdle)(TTSOutputInterface *this);
};

```

### `FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>::is_shared_ptr<std::shared_ptr<Core::CpuRingBufferAllocation_Buffer> >`
```
struct __cppobj FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>::is_shared_ptr<std::shared_ptr<Core::CpuRingBufferAllocation_Buffer> > : std::integral_constant<bool,1>
{
};

```

### `FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>::setLastCompletedFenceValue::__l2::<lambda_be601a93d3a973414038685af37130e7>`
```
struct __cppobj FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0>::setLastCompletedFenceValue::__l2::<lambda_be601a93d3a973414038685af37130e7>
{
  const unsigned __int64 *completedFenceValue;
  FencedDynamicRingBuffer<Core::CpuRingBufferAllocation_Buffer,2,0> *const __this;
};

```

### `FogCommandComponent`
```
struct __cppobj FogCommandComponent : IEntityComponent
{
  std::vector<FogCommandSettings> mFogStack;
};

```

### `FlagComponent<ActorTickedFlag>`
```
struct __cppobj FlagComponent<ActorTickedFlag> : IEntityComponent
{
};

```

### `FogCommand`
```
struct __cppobj FogCommand : Command
{
  CommandSelector<Player> mTargets;
  FogCommand::Mode mMode;
  std::string mFogId;
  std::string mUserProvidedId;
};

```

### `FogCommand_vtbl`
```
struct /*VFT*/ FogCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `FunctionAction`
```
struct __cppobj FunctionAction : IChunkLoadedAction
{
  std::string mFilePath;
};

```

### `FunctionAction_vtbl`
```
struct /*VFT*/ FunctionAction_vtbl
{
  void (__fastcall *~IChunkLoadedAction)(IChunkLoadedAction *this);
  void (__fastcall *execute)(IChunkLoadedAction *this, ServerLevel *, Dimension *);
  void (__fastcall *serialize)(IChunkLoadedAction *this, CompoundTag *);
};

```

### `FireworksRocketActor`
```
struct __cppobj __declspec(align(8)) FireworksRocketActor : PredictableProjectile
{
  int mLife;
  int mLifeTime;
  bool mDispensed;
};

```

### `FireworksRocketActor_vtbl`
```
struct /*VFT*/ FireworksRocketActor_vtbl
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
};

```

### `FurnaceBlockActor`
```
struct __cppobj __declspec(align(8)) FurnaceBlockActor : BlockActor, Container
{
  int mLitTime;
  int mLitDuration;
  int mCookingProgress;
  unsigned int mStoredXP;
  ItemStack mItems[3];
  bool mDirty[3];
  std::unordered_set<ActorUniqueID> mPlayers;
  const HashedString mRecipeTag;
  const int mBurnInterval;
  LevelSoundEvent mSmeltSoundEvent;
  int mSoundTick;
  int mSoundTickTarget;
  Random mRandom;
  const Block *mUnlitFurnace;
  const Block *mLitFurnace;
  ItemInstance mLastFuelItem;
  bool mCanBeFinished;
  bool mFinished;
  bool mNoDrop;
};

```

### `FurnaceBlockActor_vtbl`
```
struct /*VFT*/ FurnaceBlockActor_vtbl
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

### `FunctionAction::_printOutput::__l2::<lambda_29a6859966874ed56bdad0b621ece517>`
```
struct __cppobj __declspec(align(8)) FunctionAction::_printOutput::__l2::<lambda_29a6859966874ed56bdad0b621ece517>
{
  TextObjectRoot *textObjectRoot;
  _BYTE opPermLevel[1];
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_c388d79e814dd4ff849cbad3604bc61d>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_c388d79e814dd4ff849cbad3604bc61d>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_0a8ee2cd4bd4a4731c71a57d4abd4de2>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_0a8ee2cd4bd4a4731c71a57d4abd4de2>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_b6ab99318bc34040c23c84728383dea2>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l8::<lambda_b6ab99318bc34040c23c84728383dea2>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_aa019d3dd92124d59bef87041ba622b0>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_aa019d3dd92124d59bef87041ba622b0>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_00880b92af31f968791c4eed7e6c61a8>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_00880b92af31f968791c4eed7e6c61a8>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_f97cbdba0d2385587c63cedbaed4cbc4>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_f97cbdba0d2385587c63cedbaed4cbc4>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_2d9619e7737f7b9ef352678014760872>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l7::<lambda_2d9619e7737f7b9ef352678014760872>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_dec754abcac794b6da96a720eded68bf>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_dec754abcac794b6da96a720eded68bf>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_caeb69210887eb326d6a99ae06ff7020>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_caeb69210887eb326d6a99ae06ff7020>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_2c1b06c9f0a2c5248839b21168fc798c>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_2c1b06c9f0a2c5248839b21168fc798c>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_9c00dedd5332c3e2cd5037afcff10e0e>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_9c00dedd5332c3e2cd5037afcff10e0e>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_a595d4db4302e152869dfff914040933>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l5::<lambda_a595d4db4302e152869dfff914040933>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l4::<lambda_455a293d6b2c8ad2f10c131dbc53c5d4>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l4::<lambda_455a293d6b2c8ad2f10c131dbc53c5d4>
{
};

```

### `FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l4::<lambda_2cf1aefae47b2796c9704e85ed50ae79>`
```
struct __cppobj FogDefinition::buildFogDefinitionSchema_v1_16_100::__l2::<lambda_7dad882e37f33ff82791872eb65e74f2>::()::__l4::<lambda_2cf1aefae47b2796c9704e85ed50ae79>
{
};

```

### `FogManager::calculateCurrentCoefficientSetting::__l2::<lambda_12ef8424d68d1b5554d461cc50e22571>`
```
struct __cppobj FogManager::calculateCurrentCoefficientSetting::__l2::<lambda_12ef8424d68d1b5554d461cc50e22571>
{
  FogDefinition::CoefficientSettingType settingType;
};

```

### `FogManager::calculateCurrentDensitySetting::__l2::<lambda_6ba298e373dadcb52a3d9720e76557ba>`
```
struct __cppobj FogManager::calculateCurrentDensitySetting::__l2::<lambda_6ba298e373dadcb52a3d9720e76557ba>
{
  FogDefinition::DensitySettingType settingType;
};

```

### `FogManager::calculateCurrentDistanceSetting::__l2::<lambda_fd7ebdbd98023fd0d9a821e51c7a6b3e>`
```
struct __cppobj FogManager::calculateCurrentDistanceSetting::__l2::<lambda_fd7ebdbd98023fd0d9a821e51c7a6b3e>
{
  FogDefinition::DistanceSettingType settingType;
};

```

### `FamilyTypeDefinition`
```
struct __cppobj FamilyTypeDefinition
{
  std::set<HashedString,std::hash<HashedString>,std::allocator<HashedString> > mFamilySet;
};

```

### `FlockingDefinition`
```
struct __cppobj FlockingDefinition
{
  bool mInWater;
  bool mMatchVariant;
  bool mUseCenterOfMass;
  int mLowFlockLimit;
  int mHighFlockLimit;
  float mGoalWeight;
  float mLonerChance;
  float mInfluenceRadius;
  float mBreachInfluence;
  float mSeparationWeight;
  float mSeparationThreshold;
  float mCohesionWeight;
  float mCohesionThreshold;
  float mInnerCohesionThres;
  float mMinHeight;
  float mMaxHeight;
  float mBlockDistance;
  float mBlockWeight;
};

```

### `FeedItem::Effect`
```
struct __cppobj FeedItem::Effect
{
  std::string descriptionId;
  int id;
  int duration;
  int amplifier;
  float chance;
};

```

### `FeedItem`
```
struct __cppobj FeedItem
{
  ItemDescriptor mItemDescriptor;
  int mValue;
  std::vector<FeedItem::Effect> mEffects;
};

```

### `FlyMoveControl`
```
struct __cppobj FlyMoveControl : MoveControl
{
};

```

### `FlyMoveControl_vtbl`
```
struct /*VFT*/ FlyMoveControl_vtbl
{
  void (__fastcall *~Control)(Control *this);
  void (__fastcall *initializeInternal)(MoveControl *this, Mob *, MoveControlDescription *);
  void (__fastcall *tick)(MoveControl *this, MoveControlComponent *, Mob *);
  void (__fastcall *setWantedPosition)(MoveControl *this, MoveControlComponent *, Mob *, const Vec3 *, float);
};

```

### `FloatNavigation`
```
struct __cppobj FloatNavigation : PathNavigation
{
};

```

### `FloatNavigation_vtbl`
```
struct /*VFT*/ FloatNavigation_vtbl
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

### `FlyingPathNavigation`
```
struct __cppobj FlyingPathNavigation : PathNavigation
{
  bool mHadGravity;
  bool mCanPathFromAir;
  const float mMinWaypointRadius;
};

```

### `FlyingPathNavigation_vtbl`
```
struct /*VFT*/ FlyingPathNavigation_vtbl
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

### `FlockingSystem`
```
struct __cppobj FlockingSystem : ITickingSystem
{
};

```

### `FlockingSystem_vtbl`
```
struct /*VFT*/ FlockingSystem_vtbl
{
  void (__fastcall *~ITickingSystem)(ITickingSystem *this);
  void (__fastcall *tick)(ITickingSystem *this, EntityRegistry *);
};

```

### `FriendlySize`
```
struct __cppobj FriendlySize
{
  unsigned __int64 bytes;
};

```

### `FireworksRecipe`
```
struct __cppobj FireworksRecipe : MultiRecipe
{
  std::vector<ItemInstance> mResult;
};

```

### `FireworksRecipe_vtbl`
```
struct /*VFT*/ FireworksRecipe_vtbl
{
  void (__fastcall *~Recipe)(Recipe *this);
  const std::vector<ItemInstance> *(__fastcall *assemble)(Recipe *this, CraftingContainer *);
  int (__fastcall *getCraftingSize)(Recipe *this);
  const RecipeIngredient *(__fastcall *getIngredient)(Recipe *this, int, int);
  const std::vector<ItemInstance> *(__fastcall *getResultItem)(Recipe *this);
  bool (__fastcall *isShapeless)(Recipe *this);
  bool (__fastcall *matches)(Recipe *this, CraftingContainer *, Level *);
  int (__fastcall *size)(Recipe *this);
  const mce::UUID *(__fastcall *getId)(Recipe *this);
  const ItemPack *(__fastcall *getItemPack)(Recipe *this);
  bool (__fastcall *isMultiRecipe)(Recipe *this);
  std::string *(__fastcall *getTypeString)(Recipe *this, std::string *result);
  bool (__fastcall *itemValidForRecipe)(Recipe *this, const ItemDescriptor *, const ItemStack *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, int, int, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *, const CompoundTag *);
  bool (__fastcall *itemsMatch)(Recipe *this, const ItemDescriptor *, const ItemDescriptor *);
};

```

### `FeatureToggles::_getDisabledLockedCallback::__l2::<lambda_5dbb485860e64799dd5864728b4946ff>`
```
struct __cppobj __declspec(align(8)) FeatureToggles::_getDisabledLockedCallback::__l2::<lambda_5dbb485860e64799dd5864728b4946ff>
{
  FeatureToggles *const __this;
  _BYTE optionIdToCheck[4];
};

```

### `FeatureToggles::_getDisabledSetupCallback::__l2::<lambda_7d67b21fbe351c2d84afc65451e90be2>`
```
struct __cppobj __declspec(align(8)) FeatureToggles::_getDisabledSetupCallback::__l2::<lambda_7d67b21fbe351c2d84afc65451e90be2>
{
  FeatureToggles *const __this;
  _BYTE optionIdToCheck[4];
};

```

### `FeatureToggles::_getEnabledLockedCallback::__l2::<lambda_e21ea8f733186111a070e29c202e5203>`
```
struct __cppobj __declspec(align(8)) FeatureToggles::_getEnabledLockedCallback::__l2::<lambda_e21ea8f733186111a070e29c202e5203>
{
  FeatureToggles *const __this;
  _BYTE optionIdToCheck[4];
};

```

### `FeatureToggles::_getEnabledSetupCallback::__l2::<lambda_5db25955c5ba18bb6f909f1c95a0c4c3>`
```
struct __cppobj __declspec(align(8)) FeatureToggles::_getEnabledSetupCallback::__l2::<lambda_5db25955c5ba18bb6f909f1c95a0c4c3>
{
  FeatureToggles *const __this;
  _BYTE optionIdToCheck[4];
};

```

### `FeatureToggles::_initialize::__l2::<lambda_56780e8a1121adf4efc9847217156039>`
```
struct __cppobj FeatureToggles::_initialize::__l2::<lambda_56780e8a1121adf4efc9847217156039>
{
  FeatureToggles *const __this;
};

```

### `FileSystemFileAccess::FileSystemFileReadAccess`
```
struct __cppobj FileSystemFileAccess::FileSystemFileReadAccess : IFileReadAccess
{
};

```

### `FileSystemFileAccess::FileSystemFileReadAccess_vtbl`
```
struct /*VFT*/ FileSystemFileAccess::FileSystemFileReadAccess_vtbl
{
  void (__fastcall *~IFileReadAccess)(IFileReadAccess *this);
  unsigned __int64 (__fastcall *fread)(IFileReadAccess *this, void *, unsigned __int64, unsigned __int64, void *);
};

```

### `FileSystemFileAccess::FileSystemFileWriteAccess`
```
struct __cppobj FileSystemFileAccess::FileSystemFileWriteAccess : IFileWriteAccess
{
};

```

### `FileSystemFileAccess::FileSystemFileWriteAccess_vtbl`
```
struct /*VFT*/ FileSystemFileAccess::FileSystemFileWriteAccess_vtbl
{
  void (__fastcall *~IFileWriteAccess)(IFileWriteAccess *this);
  unsigned __int64 (__fastcall *fwrite)(IFileWriteAccess *this, const void *, unsigned __int64, unsigned __int64, void *);
};

```

### `FileSystemFileAccess`
```
struct __cppobj FileSystemFileAccess : IFileAccess
{
  FileSystemMode mMode;
  FileSystemFileAccess::FileSystemFileReadAccess mReadInterface;
  FileSystemFileAccess::FileSystemFileWriteAccess mWriteInterface;
};

```

### `FileSystemFileAccess_vtbl`
```
struct /*VFT*/ FileSystemFileAccess_vtbl
{
  void (__fastcall *~IFileAccess)(IFileAccess *this);
  void *(__fastcall *fopen)(IFileAccess *this, const Core::Path *, const std::string *);
  int (__fastcall *fclose)(IFileAccess *this, void *);
  int (__fastcall *fseek)(IFileAccess *this, void *, __int64, int);
  __int64 (__fastcall *ftell)(IFileAccess *this, void *);
  const IFileReadAccess *(__fastcall *getReadInterface)(IFileAccess *this);
  IFileWriteAccess *(__fastcall *getWriteInterface)(IFileAccess *this);
  void (__fastcall *unload)(IFileAccess *this);
};

```

### `FeatureRefTraits`
```
struct __cppobj FeatureRefTraits
{
};

```

### `FeatureConstRefTraits`
```
struct __cppobj FeatureConstRefTraits
{
};

```

### `FunctionManager::load::__l7::<lambda_83470faaeb21466e721bad93b29e86d1>`
```
struct __cppobj FunctionManager::load::__l7::<lambda_83470faaeb21466e721bad93b29e86d1>
{
  FunctionManager *const __this;
  const SemVersion *minEngineVersion;
  ResourcePackManager *serverPackManager;
  const CurrentCmdVersion *packCommandVersion;
  CommandRegistry *registry;
  std::vector<std::string> *functionSoftEnumNames;
};

```

### `FillCommand`
```
struct __cppobj __declspec(align(8)) FillCommand : Command
{
  CommandPosition mFrom;
  CommandPosition mTo;
  const Block *mBlock;
  const Block *mReplaceBlock;
  FillCommand::FillMode mMode;
  int mBlockData;
  int mReplaceBlockData;
};

```

### `FillCommand_vtbl`
```
struct /*VFT*/ FillCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `FunctionCommand`
```
struct __cppobj FunctionCommand : Command
{
  CommandFilePath mFilePath;
};

```

### `FunctionCommand_vtbl`
```
struct /*VFT*/ FunctionCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `FileDataOutput`
```
struct __cppobj FileDataOutput : BytesDataOutput
{
  bool mIsOk;
  Core::File mFile;
};

```

### `FileDataOutput_vtbl`
```
struct /*VFT*/ FileDataOutput_vtbl
{
  void (__fastcall *~IDataOutput)(IDataOutput *this);
  void (__fastcall *writeString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeLongString)(IDataOutput *this, gsl::basic_string_span<char const ,-1>);
  void (__fastcall *writeFloat)(IDataOutput *this, float);
  void (__fastcall *writeDouble)(IDataOutput *this, long double);
  void (__fastcall *writeByte)(IDataOutput *this, char);
  void (__fastcall *writeShort)(IDataOutput *this, __int16);
  void (__fastcall *writeInt)(IDataOutput *this, int);
  void (__fastcall *writeLongLong)(IDataOutput *this, __int64);
  void (__fastcall *writeBytes)(IDataOutput *this, const void *, unsigned __int64);
  bool (__fastcall *isOk)(IDataOutput *this);
};

```

### `FileDataInput`
```
struct __cppobj FileDataInput : BytesDataInput
{
  bool mIsOk;
  Core::File mFile;
};

```

### `FileDataInput_vtbl`
```
struct /*VFT*/ FileDataInput_vtbl
{
  void (__fastcall *~IDataInput)(IDataInput *this);
  std::string *(__fastcall *readString)(IDataInput *this, std::string *result);
  std::string *(__fastcall *readLongString)(IDataInput *this, std::string *result);
  float (__fastcall *readFloat)(IDataInput *this);
  long double (__fastcall *readDouble)(IDataInput *this);
  char (__fastcall *readByte)(IDataInput *this);
  __int16 (__fastcall *readShort)(IDataInput *this);
  int (__fastcall *readInt)(IDataInput *this);
  __int64 (__fastcall *readLongLong)(IDataInput *this);
  bool (__fastcall *readBytes)(IDataInput *this, void *, unsigned __int64);
  unsigned __int64 (__fastcall *numBytesLeft)(IDataInput *this);
  bool (__fastcall *isOk)(IDataInput *this);
  bool (__fastcall *seek)(IDataInput *this, unsigned __int64);
};

```

### `FilePickerSettings::<lambda_129896ef764bb08519885b7ab5ca9016>`
```
struct __cppobj FilePickerSettings::<lambda_129896ef764bb08519885b7ab5ca9016>
{
};

```

### `FilePickerSettings::<lambda_1c69aa04d55bac9dab0ac921a14d8c2b>`
```
struct __cppobj FilePickerSettings::<lambda_1c69aa04d55bac9dab0ac921a14d8c2b>
{
};

```

### `FilePickerSettings::<lambda_3b83f32960a2e8aa93e0654bf1d2fbe5>`
```
struct __cppobj FilePickerSettings::<lambda_3b83f32960a2e8aa93e0654bf1d2fbe5>
{
};

```

### `FileUploadManager::_uploadStream::__l2::<lambda_704199bdd8ef4b5e4b61022e06e9c849>`
```
struct __cppobj FileUploadManager::_uploadStream::__l2::<lambda_704199bdd8ef4b5e4b61022e06e9c849>
{
  std::weak_ptr<FileUploadManager> weak_this;
  FileUploadManager::_uploadStream::__l2::<lambda_7c32c70c440907d77e4081b7aef620a1> fetchStreamDataCallback;
  FileUploadManager::_uploadStream::__l2::<lambda_ab8d111204de64d325c648c9d712e8ea> onStreamFinishedCallback;
  std::string boundary;
};

```

### `FileUploadManager::_uploadChunk::__l13::<lambda_beec154458228c4f1efa54daecb2bd49>`
```
struct __cppobj FileUploadManager::_uploadChunk::__l13::<lambda_beec154458228c4f1efa54daecb2bd49>
{
  std::weak_ptr<FileUploadManager> weak_this;
  const FileChunkInfo chunk;
};

```

### `FileUploadManager::_uploadChunk::__l13::<lambda_beec154458228c4f1efa54daecb2bd49>::()::__l5::<lambda_b942687c99a128d38d4a3acdf5208e9b>::()::__l5::<lambda_0e10341a96d156a6650052c442f8bc7b>`
```
struct __cppobj FileUploadManager::_uploadChunk::__l13::<lambda_beec154458228c4f1efa54daecb2bd49>::()::__l5::<lambda_b942687c99a128d38d4a3acdf5208e9b>::()::__l5::<lambda_0e10341a96d156a6650052c442f8bc7b>
{
  std::weak_ptr<FileUploadManager> weak_this;
};

```

### `FileUploadManager::_resumeUpload::__l2::<lambda_edbb1383cf59043f3a41a84683bc4a8c>`
```
struct __cppobj FileUploadManager::_resumeUpload::__l2::<lambda_edbb1383cf59043f3a41a84683bc4a8c>
{
  std::weak_ptr<FileUploadManager> weak_this;
};

```

### `FileUploadManager::uploadFile::__l13::<lambda_74760951e5721fb9dafc828e7e1ca7c9>::()::__l11::<lambda_aa179f462ff3a856f50c63ee1659ca3f>`
```
struct __cppobj __declspec(align(8)) FileUploadManager::uploadFile::__l13::<lambda_74760951e5721fb9dafc828e7e1ca7c9>::()::__l11::<lambda_aa179f462ff3a856f50c63ee1659ca3f>
{
  std::weak_ptr<FileUploadManager> weak_this;
  bool autoStartUpload;
};

```

### `FileDownloadManager::pauseDownload::__l5::<lambda_411b52f0bd9ccf2ab6e8671e1b98316a>`
```
struct __cppobj FileDownloadManager::pauseDownload::__l5::<lambda_411b52f0bd9ccf2ab6e8671e1b98316a>
{
};

```

### `FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>::()::__l8::<lambda_d89c88a6ec3abc173214fdc98b971c20>`
```
struct __cppobj FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>::()::__l8::<lambda_d89c88a6ec3abc173214fdc98b971c20>
{
  std::weak_ptr<FileDownloadManager> weak_this;
};

```

### `FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>::()::__l8::<lambda_2443bc6f7ea8a704e54426e60ed6d6fd>`
```
struct __cppobj FileDownloadManager::downloadFile::__l13::<lambda_0e52f60533a747952835c01f8836253e>::()::__l8::<lambda_2443bc6f7ea8a704e54426e60ed6d6fd>
{
  std::weak_ptr<FileDownloadManager> weak_this;
};

```

### `Fish`
```
struct __cppobj Fish : WaterAnimal
{
  float mAnimationAmount;
  float mAnimationAmountPrev;
};

```

### `FilterTestDaytime_vtbl`
```
struct /*VFT*/ FilterTestDaytime_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestClock`
```
struct __cppobj FilterTestClock : SimpleFloatFilterTest
{
};

```

### `FilterTestClock_vtbl`
```
struct /*VFT*/ FilterTestClock_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestMoonIntensity`
```
struct __cppobj FilterTestMoonIntensity : SimpleFloatFilterTest
{
};

```

### `FilterTestMoonIntensity_vtbl`
```
struct /*VFT*/ FilterTestMoonIntensity_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestMoonPhase`
```
struct __cppobj FilterTestMoonPhase : SimpleFloatFilterTest
{
};

```

### `FilterTestMoonPhase_vtbl`
```
struct /*VFT*/ FilterTestMoonPhase_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestDistanceToNearestPlayer`
```
struct __cppobj FilterTestDistanceToNearestPlayer : SimpleFloatFilterTest
{
};

```

### `FilterTestDistanceToNearestPlayer_vtbl`
```
struct /*VFT*/ FilterTestDistanceToNearestPlayer_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestDimensionWeather`
```
struct __cppobj __declspec(align(8)) FilterTestDimensionWeather : FilterTest
{
  FilterTestDimensionWeather::WeatherType mWeather;
};

```

### `FilterTestDimensionWeather_vtbl`
```
struct /*VFT*/ FilterTestDimensionWeather_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestDifficulty_vtbl`
```
struct /*VFT*/ FilterTestDifficulty_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestHourlyClock_vtbl`
```
struct /*VFT*/ FilterTestHourlyClock_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestGameRule_vtbl`
```
struct /*VFT*/ FilterTestGameRule_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestBiome_vtbl`
```
struct /*VFT*/ FilterTestBiome_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestBiomeSnowCovered_vtbl`
```
struct /*VFT*/ FilterTestBiomeSnowCovered_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestBiomeHumid_vtbl`
```
struct /*VFT*/ FilterTestBiomeHumid_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestTemperatureType_vtbl`
```
struct /*VFT*/ FilterTestTemperatureType_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestTemperatureValue_vtbl`
```
struct /*VFT*/ FilterTestTemperatureValue_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestBrightness_vtbl`
```
struct /*VFT*/ FilterTestBrightness_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestAltitude_vtbl`
```
struct /*VFT*/ FilterTestAltitude_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestBiomeHasTag_vtbl`
```
struct /*VFT*/ FilterTestBiomeHasTag_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestHasTradeSupply_vtbl`
```
struct /*VFT*/ FilterTestHasTradeSupply_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FilterTestLightLevel`
```
struct __cppobj FilterTestLightLevel : SimpleIntFilterTest
{
};

```

### `FilterTestLightLevel_vtbl`
```
struct /*VFT*/ FilterTestLightLevel_vtbl
{
  void (__fastcall *~FilterTest)(FilterTest *this);
  bool (__fastcall *setup)(FilterTest *this, const FilterTest::Definition *, const FilterInputs *);
  bool (__fastcall *evaluate)(FilterTest *this, const FilterContext *);
  void (__fastcall *finalizeParsedValue)(FilterTest *this, IWorldRegistriesProvider *);
  gsl::basic_string_span<char const ,-1> *(__fastcall *getName)(FilterTest *this, gsl::basic_string_span<char const ,-1> *result);
  Json::Value *(__fastcall *_serializeDomain)(FilterTest *this, Json::Value *result);
  Json::Value *(__fastcall *_serializeValue)(FilterTest *this, Json::Value *result);
};

```

### `FireImmuneDefinition`
```
struct __cppobj FireImmuneDefinition
{
};

```

### `FloatsInLiquidDefinition`
```
struct __cppobj FloatsInLiquidDefinition
{
};

```

### `FlyingSpeedDefinition`
```
struct __cppobj FlyingSpeedDefinition
{
  float mValue;
};

```

### `FrictionModifierDefinition`
```
struct __cppobj FrictionModifierDefinition
{
  float mValue;
};

```

### `FindCoverGoal`
```
struct __cppobj __declspec(align(8)) FindCoverGoal : Goal
{
  Mob *mMob;
  float mSpeed;
  int mCooldownTicks;
  Tick mCooldownTimer;
  Vec3 mWantedPosition;
};

```

### `FindCoverGoal_vtbl`
```
struct /*VFT*/ FindCoverGoal_vtbl
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

### `FleeSunGoal`
```
struct __cppobj FleeSunGoal : FindCoverGoal
{
};

```

### `FleeSunGoal_vtbl`
```
struct /*VFT*/ FleeSunGoal_vtbl
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

### `FollowFlockGoal`
```
struct __cppobj __declspec(align(8)) FollowFlockGoal : Goal
{
  Mob *mMob;
  int mCooldownTicks;
  int mNotInFlockTicks;
  float mSpeed;
};

```

### `FollowFlockGoal_vtbl`
```
struct /*VFT*/ FollowFlockGoal_vtbl
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

### `FindBlockNode`
```
struct __cppobj __declspec(align(4)) FindBlockNode : BehaviorNode
{
  const Block *mBlock;
  int mSearchRadius;
  bool mJumping;
};

```

### `FindBlockNode_vtbl`
```
struct /*VFT*/ FindBlockNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `FindBlockDefinition`
```
struct __cppobj FindBlockDefinition : BehaviorDefinition
{
  std::string mBlockName;
  std::string mBlockNameId;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `FindBlockDefinition_vtbl`
```
struct /*VFT*/ FindBlockDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FindActorNode`
```
struct __cppobj FindActorNode : BehaviorNode
{
  ActorType mActorType;
  int mSearchRadius;
};

```

### `FindActorNode_vtbl`
```
struct /*VFT*/ FindActorNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `FindActorDefinition`
```
struct __cppobj FindActorDefinition : BehaviorDefinition
{
  std::string mEntityName;
  std::string mEntityType;
  int mSearchRadius;
  std::string mSearchRadiusId;
};

```

### `FindActorDefinition_vtbl`
```
struct /*VFT*/ FindActorDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FlyNode`
```
struct __cppobj __declspec(align(4)) FlyNode : BehaviorNode
{
  bool mHaveCheckedFlightStatus;
  bool mJumpedLastTick;
  bool mJumpedOnce;
  bool mShouldBeFlying;
  bool mShouldThrowEventIfNoStateChangeNecessary;
};

```

### `FlyNode_vtbl`
```
struct /*VFT*/ FlyNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `FlyDefinition`
```
struct __cppobj FlyDefinition : BehaviorDefinition
{
  bool mShouldBeFlying;
  std::string mShouldBeFlyingId;
  bool mShouldThrowEventIfNoStateChangeNecessary;
  std::string mShouldThrowEventIfNoStateChangeNecessaryId;
};

```

### `FlyDefinition_vtbl`
```
struct /*VFT*/ FlyDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FindTargetNode`
```
struct __cppobj __declspec(align(8)) FindTargetNode : BehaviorNode
{
  bool mReselectTargets;
};

```

### `FindTargetNode_vtbl`
```
struct /*VFT*/ FindTargetNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `FindTargetDefinition`
```
struct __cppobj FindTargetDefinition : BehaviorDefinition
{
  std::string mOperation;
  std::string mOperationId;
  float mDist;
  std::string mDistId;
  Vec3 mTargetPos;
  std::string mTargetPosId;
};

```

### `FindTargetDefinition_vtbl`
```
struct /*VFT*/ FindTargetDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FindHarvestDefinition`
```
struct __cppobj FindHarvestDefinition : BehaviorDefinition
{
  std::string mItemName;
  std::string mItemNameId;
};

```

### `FindHarvestDefinition_vtbl`
```
struct /*VFT*/ FindHarvestDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FindRecipeDefinition`
```
struct __cppobj FindRecipeDefinition : BehaviorDefinition
{
  std::string mItemName;
  std::string mItemNameId;
};

```

### `FindRecipeDefinition_vtbl`
```
struct /*VFT*/ FindRecipeDefinition_vtbl
{
  void (__fastcall *~BehaviorDefinition)(BehaviorDefinition *this);
  void (__fastcall *load)(BehaviorDefinition *this, Json::Value, const BehaviorFactory *);
  std::unique_ptr<BehaviorNode> *(__fastcall *createNode)(BehaviorDefinition *this, std::unique_ptr<BehaviorNode> *result, Actor *, const BehaviorFactory *, BehaviorNode *, BehaviorData *);
};

```

### `FindRecipeNode`
```
struct __cppobj FindRecipeNode : BehaviorNode
{
  std::string mTargetItemName;
};

```

### `FindRecipeNode_vtbl`
```
struct /*VFT*/ FindRecipeNode_vtbl
{
  void (__fastcall *~BehaviorNode)(BehaviorNode *this);
  BehaviorStatus (__fastcall *tick)(BehaviorNode *this, Actor *);
  void (__fastcall *initializeFromDefinition)(BehaviorNode *this, Actor *);
};

```

### `FireworksRocketActor::checkAchievement::__l21::<lambda_c73dc455ce730d1f42b1b56fbc1f5399>`
```
struct __cppobj FireworksRocketActor::checkAchievement::__l21::<lambda_c73dc455ce730d1f42b1b56fbc1f5399>
{
  AABB *areaofeffect;
};

```

### `Fireball`
```
struct __cppobj __declspec(align(8)) Fireball : PredictableProjectile
{
  ActorUniqueID ownerId;
  bool mInGround;
  MovementInterpolator mInterpolation;
};

```

### `Fireball_vtbl`
```
struct /*VFT*/ Fireball_vtbl
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
  float (__fastcall *getInertia)(Fireball *this);
  void (__fastcall *onHit)(Fireball *this, const HitResult *);
  ParticleType (__fastcall *getTrailParticle)(Fireball *this);
  bool (__fastcall *shouldBurn)(Fireball *this);
};

```

### `FurnaceInputContainerController`
```
struct __cppobj FurnaceInputContainerController : ContainerController
{
  HashedString mRecipeTag;
};

```

### `FurnaceInputContainerController_vtbl`
```
struct /*VFT*/ FurnaceInputContainerController_vtbl
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

### `FilterList::initialize::__l2::<lambda_53e6ff47ca84784fadfa6f6ea435d0db>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_53e6ff47ca84784fadfa6f6ea435d0db>
{
};

```

### `FilterList::initialize::__l2::<lambda_0b20278bf0b6617c64212f827fc3f6c6>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_0b20278bf0b6617c64212f827fc3f6c6>
{
};

```

### `FilterList::initialize::__l2::<lambda_70127f048990374f535f74a1b0a14315>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_70127f048990374f535f74a1b0a14315>
{
};

```

### `FilterList::initialize::__l2::<lambda_c08235eaf234640396c8d9d4980e4d68>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_c08235eaf234640396c8d9d4980e4d68>
{
};

```

### `FilterList::initialize::__l2::<lambda_2277542b59c4fb23b9fa70a8ed97c541>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_2277542b59c4fb23b9fa70a8ed97c541>
{
};

```

### `FilterList::initialize::__l2::<lambda_93c18a3b380a6e7a33442d3c0483fbe3>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_93c18a3b380a6e7a33442d3c0483fbe3>
{
};

```

### `FilterList::initialize::__l2::<lambda_2d06b743fa8020ab3d8bf3c094340db8>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_2d06b743fa8020ab3d8bf3c094340db8>
{
};

```

### `FilterList::initialize::__l2::<lambda_c3f8d4e5adf6bce18ffcdda2e15ecf8a>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_c3f8d4e5adf6bce18ffcdda2e15ecf8a>
{
};

```

### `FilterList::initialize::__l2::<lambda_695aad19b31fab8d5eb858d6aa1aa324>`
```
struct __cppobj FilterList::initialize::__l2::<lambda_695aad19b31fab8d5eb858d6aa1aa324>
{
};

```

### `FilterTestDistanceToNearestPlayer::evaluate::__l2::<lambda_ac2cf845ac1aa3efb9503cdba1ff5946>`
```
struct __cppobj FilterTestDistanceToNearestPlayer::evaluate::__l2::<lambda_ac2cf845ac1aa3efb9503cdba1ff5946>
{
  const Vec3 pos;
  float *best;
};

```

### `FertilizerItem`
```
struct __cppobj __declspec(align(8)) FertilizerItem : Item
{
  FertilizerType mType;
};

```

### `FishingEnchant`
```
struct __cppobj FishingEnchant : Enchant
{
};

```

### `FishingEnchant_vtbl`
```
struct /*VFT*/ FishingEnchant_vtbl
{
  void (__fastcall *~Enchant)(Enchant *this);
  bool (__fastcall *isCompatibleWith)(Enchant *this, Enchant::Type);
  int (__fastcall *getMinCost)(Enchant *this, int);
  int (__fastcall *getMaxCost)(Enchant *this, int);
  int (__fastcall *getMinLevel)(Enchant *this);
  int (__fastcall *getMaxLevel)(Enchant *this);
  int (__fastcall *getDamageProtection)(Enchant *this, int, const ActorDamageSource *);
  float (__fastcall *getDamageBonus)(Enchant *this, int, const Actor *);
  void (__fastcall *doPostAttack)(Enchant *this, Actor *, Actor *, int);
  void (__fastcall *doPostHurt)(Enchant *this, ItemInstance *, Actor *, Actor *, int);
  bool (__fastcall *isMeleeDamageEnchant)(Enchant *this);
  bool (__fastcall *isProtectionEnchant)(Enchant *this);
  bool (__fastcall *isTreasureOnly)(Enchant *this);
  bool (__fastcall *isDiscoverable)(Enchant *this);
};

```

### `FrostWalkerEnchant`
```
struct __cppobj FrostWalkerEnchant : Enchant
{
};

```

### `FrostWalkerEnchant_vtbl`
```
struct /*VFT*/ FrostWalkerEnchant_vtbl
{
  void (__fastcall *~Enchant)(Enchant *this);
  bool (__fastcall *isCompatibleWith)(Enchant *this, Enchant::Type);
  int (__fastcall *getMinCost)(Enchant *this, int);
  int (__fastcall *getMaxCost)(Enchant *this, int);
  int (__fastcall *getMinLevel)(Enchant *this);
  int (__fastcall *getMaxLevel)(Enchant *this);
  int (__fastcall *getDamageProtection)(Enchant *this, int, const ActorDamageSource *);
  float (__fastcall *getDamageBonus)(Enchant *this, int, const Actor *);
  void (__fastcall *doPostAttack)(Enchant *this, Actor *, Actor *, int);
  void (__fastcall *doPostHurt)(Enchant *this, ItemInstance *, Actor *, Actor *, int);
  bool (__fastcall *isMeleeDamageEnchant)(Enchant *this);
  bool (__fastcall *isProtectionEnchant)(Enchant *this);
  bool (__fastcall *isTreasureOnly)(Enchant *this);
  bool (__fastcall *isDiscoverable)(Enchant *this);
};

```

### `FireChargeItem`
```
struct __cppobj FireChargeItem : Item
{
};

```

### `FishingRodItem`
```
struct __cppobj FishingRodItem : Item
{
  TextureUVCoordinateSet mFrame[2];
};

```

### `FlintAndSteelItem`
```
struct __cppobj FlintAndSteelItem : Item
{
};

```

### `FlagComponent<NoiseBasedColorPalette>`
```
struct __cppobj FlagComponent<NoiseBasedColorPalette> : IEntityComponent
{
};

```

### `FilteredTransformationAttributes<PreHillsEdgeTransformation>`
```
struct __cppobj FilteredTransformationAttributes<PreHillsEdgeTransformation>
{
  std::vector<PosibleTransformation> mTransformations;
};

```

### `FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation>`
```
struct __cppobj FilteredTransformationAttributes<LegacyPreHillsEdgeTransformation>
{
  std::vector<PosibleTransformation> mTransformations;
};

```

### `FixedBiomeSource_vtbl`
```
struct /*VFT*/ FixedBiomeSource_vtbl
{
  void (__fastcall *~BiomeSource)(BiomeSource *this);
  void (__fastcall *fillBiomes)(BiomeSource *this, LevelChunk *);
  BiomeArea *(__fastcall *getBiomeArea)(BiomeSource *this, BiomeArea *result, const BoundingBox *, unsigned int);
  bool (__fastcall *containsOnly)(BiomeSource *this, int, int, int, gsl::span<int const ,-1>);
  const Biome *(__fastcall *getBiome)(BiomeSource *this, int, int);
};

```

### `FaceDirectionalBlock`
```
struct __cppobj FaceDirectionalBlock : BlockLegacy
{
  bool mHorizontalOnly;
  float mYRotOffset;
};

```

### `FaceDirectionalBlock_vtbl`
```
struct /*VFT*/ FaceDirectionalBlock_vtbl
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

### `FurnaceBlock`
```
struct __cppobj __declspec(align(8)) FurnaceBlock : ActorBlock
{
  const bool mLit;
};

```

### `FurnaceBlock_vtbl`
```
struct /*VFT*/ FurnaceBlock_vtbl
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

### `FrostedIceBlock`
```
struct __cppobj FrostedIceBlock : BlockLegacy
{
};

```

### `FrostedIceBlock_vtbl`
```
struct /*VFT*/ FrostedIceBlock_vtbl
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

### `FireResistantComponentDescription`
```
struct __cppobj __declspec(align(8)) FireResistantComponentDescription : BlockComponentDescription
{
  bool fireResistant;
};

```

### `FireResistantComponentDescription_vtbl`
```
struct /*VFT*/ FireResistantComponentDescription_vtbl
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

### `FarmBlock`
```
struct __cppobj FarmBlock : BlockLegacy
{
};

```

### `FarmBlock_vtbl`
```
struct /*VFT*/ FarmBlock_vtbl
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

### `FenceGateBlock`
```
struct __cppobj FenceGateBlock : BlockLegacy
{
};

```

### `FenceGateBlock_vtbl`
```
struct /*VFT*/ FenceGateBlock_vtbl
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

### `FlowerBlock`
```
struct __cppobj __declspec(align(8)) FlowerBlock : BushBlock
{
  _BYTE mType[4];
};

```

### `FlowerBlock_vtbl`
```
struct /*VFT*/ FlowerBlock_vtbl
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

### `FarmBlock::transformOnFall::__l16::<lambda_6f1c6586e35323b556ccaad789196afc>`
```
struct __cppobj FarmBlock::transformOnFall::__l16::<lambda_6f1c6586e35323b556ccaad789196afc>
{
  Actor **entity;
  const FarmBlock *const __this;
  const BlockPos *pos;
  BlockSource *region;
};

```

### `FungusStem`
```
struct __cppobj FungusStem : RotatedPillarBlock
{
};

```

### `FungusStem_vtbl`
```
struct /*VFT*/ FungusStem_vtbl
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

### `FileArchiver::_importLegacyWorld::__l16::<lambda_538357a0a1f30c0e58914473ed9ae7db>`
```
struct __cppobj FileArchiver::_importLegacyWorld::__l16::<lambda_538357a0a1f30c0e58914473ed9ae7db>
{
  Core::File *fOut;
};

```

### `FileArchiver::_importLegacyWorld::__l2::<lambda_30db252728e558b809611799e47d6aba>`
```
struct __cppobj FileArchiver::_importLegacyWorld::__l2::<lambda_30db252728e558b809611799e47d6aba>
{
};

```

### `FileArchiver::_importWorld::__l2::<lambda_80dd2c13733dd620134364ce61fd290a>`
```
struct __cppobj FileArchiver::_importWorld::__l2::<lambda_80dd2c13733dd620134364ce61fd290a>
{
};

```

### `FileArchiver::archiveLevel::__l2::<lambda_e96768593f2d4ea24e6f0259355ea06f>`
```
struct __cppobj FileArchiver::archiveLevel::__l2::<lambda_e96768593f2d4ea24e6f0259355ea06f>
{
  unsigned __int64 *numFiles;
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<0> >`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<AggregateFeature<0> > : FeatureLoading::AbstractFeatureHolder
{
  AggregateFeature<0> *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<0> >_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<AggregateFeature<0> >_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<1> >`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<AggregateFeature<1> > : FeatureLoading::AbstractFeatureHolder
{
  AggregateFeature<1> *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<AggregateFeature<1> >_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<AggregateFeature<1> >_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FlagComponent<IgnoreAutomaticFeatureRules>`
```
struct __cppobj FlagComponent<IgnoreAutomaticFeatureRules> : IEntityComponent
{
};

```

### `FallenTreeTrunk`
```
struct __cppobj FallenTreeTrunk : ITreeTrunk
{
  IntRange mLogLength;
  IntRange mHeightModifier;
  IntRange mStumpHeight;
  BlockDescriptor mTrunkBlockDescriptor;
  WeakRefT<FeatureRefTraits> mLogDecorationFeature;
  TreeHelper::AttachableDecoration mDecoration;
};

```

### `FallenTreeTrunk_vtbl`
```
struct /*VFT*/ FallenTreeTrunk_vtbl
{
  void (__fastcall *~ITreeTrunk)(ITreeTrunk *this);
  std::optional<BlockPos> *(__fastcall *placeTrunk)(ITreeTrunk *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *, const TreeHelper::TreeParams *, const ITreeCanopy *);
  bool (__fastcall *parse)(ITreeTrunk *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `FancyTreeCanopy`
```
struct __cppobj FancyTreeCanopy : ITreeCanopy
{
  int mHeight;
  int mRadius;
  BlockDescriptor mLeafBlockDescriptor;
};

```

### `FancyTreeCanopy_vtbl`
```
struct /*VFT*/ FancyTreeCanopy_vtbl
{
  void (__fastcall *~ITreeCanopy)(ITreeCanopy *this);
  std::optional<BlockPos> *(__fastcall *placeCanopy)(ITreeCanopy *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *, const TreeHelper::TreeParams *);
  bool (__fastcall *parseTreeCanopy)(ITreeCanopy *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `FancyTreeTrunk`
```
struct __cppobj __declspec(align(8)) FancyTreeTrunk : ITreeTrunk
{
  int mBaseHeight;
  int mHeightVariance;
  int mTrunkWidth;
  float mHeightScale;
  float mBranchSlope;
  float mBranchDensity;
  float mBranchAltitudeFactor;
  float mFoliageAltitudeFactor;
  BlockDescriptor mTrunkBlockDescriptor;
  float mWidthScale;
};

```

### `FancyTreeTrunk_vtbl`
```
struct /*VFT*/ FancyTreeTrunk_vtbl
{
  void (__fastcall *~ITreeTrunk)(ITreeTrunk *this);
  std::optional<BlockPos> *(__fastcall *placeTrunk)(ITreeTrunk *this, std::optional<BlockPos> *result, IBlockWorldGenAPI *, const BlockPos *, Random *, RenderParams *, const TreeHelper::TreeParams *, const ITreeCanopy *);
  bool (__fastcall *parse)(ITreeTrunk *this, const rapidjson::GenericValue<rapidjson::UTF8<char>,rapidjson::MemoryPoolAllocator<rapidjson::CrtAllocator> > *, IWorldRegistriesProvider *);
};

```

### `FeatureLoading::ConcreteFeatureHolder<OreFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<OreFeature> : FeatureLoading::AbstractFeatureHolder
{
  OreFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<OreFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<OreFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<ScatterFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<ScatterFeature> : FeatureLoading::AbstractFeatureHolder
{
  ScatterFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<ScatterFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<ScatterFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<SearchFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<SearchFeature> : FeatureLoading::AbstractFeatureHolder
{
  SearchFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<SearchFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<SearchFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature> : FeatureLoading::AbstractFeatureHolder
{
  SingleBlockFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<SingleBlockFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature> : FeatureLoading::AbstractFeatureHolder
{
  StructureTemplateFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<StructureTemplateFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature>`
```
struct __cppobj FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature> : FeatureLoading::AbstractFeatureHolder
{
  WeightedRandomFeature *mFeaturePtr;
};

```

### `FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature>_vtbl`
```
struct /*VFT*/ FeatureLoading::ConcreteFeatureHolder<WeightedRandomFeature>_vtbl
{
  void (__fastcall *~AbstractFeatureHolder)(FeatureLoading::AbstractFeatureHolder *this);
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_070746fd668a8863cbe2a3fa42ef5d69>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_070746fd668a8863cbe2a3fa42ef5d69>
{
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_d26feffea4ae0d0b0b8b4d6cae78c5cf>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_d26feffea4ae0d0b0b8b4d6cae78c5cf>
{
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_af5d1f29c06df3f1db5b8f80f70364da>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_af5d1f29c06df3f1db5b8f80f70364da>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_269493b156b355f6873e78f5de861254>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_269493b156b355f6873e78f5de861254>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_534deace486ba3fe58b054318be7d5d3>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_534deace486ba3fe58b054318be7d5d3>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_ab790779e99eb67e9d8c5c8fd9cc4c45>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_ab790779e99eb67e9d8c5c8fd9cc4c45>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_4037a9070031ea00ecf26a17b8deac9a>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_4037a9070031ea00ecf26a17b8deac9a>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_58c2dcc1193277e90b7e9d1eb1c15558>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_58c2dcc1193277e90b7e9d1eb1c15558>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_4299ec9b57c324e4ed6c59adea430d1b>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_4299ec9b57c324e4ed6c59adea430d1b>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_39ac3505671351be2f07089f45af80d4>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_39ac3505671351be2f07089f45af80d4>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_62a233d718e72e6d45d8be1832f214d7>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_62a233d718e72e6d45d8be1832f214d7>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_765a9a9c0c55c35967e3b8f28c6a4eb6>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_765a9a9c0c55c35967e3b8f28c6a4eb6>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_897e6fcd2a422a00b9d9c4a201bfd773>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_897e6fcd2a422a00b9d9c4a201bfd773>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_42561c5376106a2d36a76d95d16bfeed>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_42561c5376106a2d36a76d95d16bfeed>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_3353d277619da3d5cd138ecb16b20a40>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_3353d277619da3d5cd138ecb16b20a40>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_2555eade625bb966e8a1cb8c17c7d650>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_2555eade625bb966e8a1cb8c17c7d650>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_a0eedeb0869af7a0f96ac76dc92d0031>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_a0eedeb0869af7a0f96ac76dc92d0031>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_4bf39c4a9b08fca0df43481eceb092dc>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_4bf39c4a9b08fca0df43481eceb092dc>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_5ae05df8699a59f68386294438b05b14>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_5ae05df8699a59f68386294438b05b14>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_72c5c6cc5f5dd19ec9b756a6f4aa1c7e>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_72c5c6cc5f5dd19ec9b756a6f4aa1c7e>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_45506032ba1c7b9bbd1df26c52850076>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_45506032ba1c7b9bbd1df26c52850076>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_bca5b7ec8dc84ccd012b20d3dd8504ec>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_bca5b7ec8dc84ccd012b20d3dd8504ec>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_13ccba55549a4f3cd8e4c2c51a107ddd>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_13ccba55549a4f3cd8e4c2c51a107ddd>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_3aa76ff1487ac6670529bd834c913005>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_3aa76ff1487ac6670529bd834c913005>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_5cb6d1b77b80274727750302cf95eef8>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_5cb6d1b77b80274727750302cf95eef8>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_2db0a06029a62470922787888580f857>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_2db0a06029a62470922787888580f857>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_e3ab05455b51e5b1eb353e38d6a02e5a>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_e3ab05455b51e5b1eb353e38d6a02e5a>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_a341f3a50e60c6ed529981a28c90aaac>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_a341f3a50e60c6ed529981a28c90aaac>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_8d80157009857924b75728f5593a8ff8>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_8d80157009857924b75728f5593a8ff8>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_b79033f7b1569ed146e124133fdbcc0c>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_b79033f7b1569ed146e124133fdbcc0c>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_ff651ceb1e4b05630dbf709c5689b4b1>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_ff651ceb1e4b05630dbf709c5689b4b1>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_5c3870871285efa3a3aa788bcc59a6a5>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_5c3870871285efa3a3aa788bcc59a6a5>
{
};

```

### `FeatureLoading::_buildSchema::__l3::<lambda_30a0658175a01da0b1d017c3a844bd3e>`
```
struct __cppobj FeatureLoading::_buildSchema::__l3::<lambda_30a0658175a01da0b1d017c3a844bd3e>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_8863387e98ecef072021858bd81ad446>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_8863387e98ecef072021858bd81ad446>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_5345261c4062f4e77220602c18289610>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_5345261c4062f4e77220602c18289610>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_8fb55b46049a0200c7143f7ba4895532>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_8fb55b46049a0200c7143f7ba4895532>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_64df30a075a0c8c674bb3f6f828c52ca>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_64df30a075a0c8c674bb3f6f828c52ca>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_0d7cacde3fd40c099b69258499db96d6>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_0d7cacde3fd40c099b69258499db96d6>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_e34e6baeca6179063c960b15821263e0>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_e34e6baeca6179063c960b15821263e0>
{
};

```

### `FeatureLoading::_buildSchema::__l5::<lambda_bd812f17ea40517b41fdb6a37c75611f>`
```
struct __cppobj FeatureLoading::_buildSchema::__l5::<lambda_bd812f17ea40517b41fdb6a37c75611f>
{
};

```

### `FeatureLoading::_buildSchema::__l5::<lambda_0bab2de68df3204c165f75450ef8e72a>`
```
struct __cppobj FeatureLoading::_buildSchema::__l5::<lambda_0bab2de68df3204c165f75450ef8e72a>
{
};

```

### `FeatureLoading::_buildSchema::__l5::<lambda_332a15757cb5a2ca55e4629941ee6bfe>`
```
struct __cppobj FeatureLoading::_buildSchema::__l5::<lambda_332a15757cb5a2ca55e4629941ee6bfe>
{
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_03b0ae550376e085f07188b9454238fd>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_03b0ae550376e085f07188b9454238fd>
{
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_6b158c2e512a8d1fbc8831cf780ee4dc>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_6b158c2e512a8d1fbc8831cf780ee4dc>
{
};

```

### `FeatureLoading::_buildSchema::__l4::<lambda_83079f870ce1353e2d06423894cf973e>`
```
struct __cppobj FeatureLoading::_buildSchema::__l4::<lambda_83079f870ce1353e2d06423894cf973e>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_97556ef3bb7e60132ee693ff92d4f682>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_97556ef3bb7e60132ee693ff92d4f682>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_ed2b13013692bdd7f19a91b5afd86826>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_ed2b13013692bdd7f19a91b5afd86826>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_d222b44934b5477be8e0cf5e6eaab932>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_d222b44934b5477be8e0cf5e6eaab932>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_c8bd75ad40874126e6105b6c5b3170a4>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_c8bd75ad40874126e6105b6c5b3170a4>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_6820c32e3003b153c2b3cea1bdc8d1b3>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_6820c32e3003b153c2b3cea1bdc8d1b3>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_374f89a74208a5ae69066c135eeec787>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_374f89a74208a5ae69066c135eeec787>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_90c035c83f69abd1911d31525619f974>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_90c035c83f69abd1911d31525619f974>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_8d4f36e87c6e3e131780a3a2f22c6d9d>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_8d4f36e87c6e3e131780a3a2f22c6d9d>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_6de0fdb9a2c3ef41e1fef4cdd647078c>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_6de0fdb9a2c3ef41e1fef4cdd647078c>
{
};

```

### `FlatWorldGenerator::ThreadData`
```
struct __cppobj FlatWorldGenerator::ThreadData
{
  Random random;
};

```

### `FlatWorldGenerator`
```
struct __cppobj FlatWorldGenerator : ChunkSource, WorldGenerator
{
  std::vector<Block const *> mPrototypeBlocks;
  BlockVolume mPrototype;
  const Biome *mBiome;
  Bedrock::Threading::InstancedThreadLocal<FlatWorldGenerator::ThreadData,std::allocator<FlatWorldGenerator::ThreadData> > generatorHelpersPool;
};

```

### `FlatWorldGenerator_vtbl`
```
struct /*VFT*/ FlatWorldGenerator_vtbl
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

### `FeaturePoolElement`
```
struct __cppobj FeaturePoolElement : StructurePoolElement
{
  WeakRefT<FeatureRefTraits> mFeature;
};

```

### `FeaturePoolElement_vtbl`
```
struct /*VFT*/ FeaturePoolElement_vtbl
{
  BlockPos *(__fastcall *getSize)(StructurePoolElement *this, BlockPos *result, Rotation);
  std::vector<JigsawBlockInfo> *(__fastcall *getJigsawMarkers)(StructurePoolElement *this, std::vector<JigsawBlockInfo> *result, BlockPos, LegacyStructureSettings *, BlockSource *);
  std::vector<JigsawBlockInfo> *(__fastcall *getJigsawMarkers)(StructurePoolElement *this, std::vector<JigsawBlockInfo> *result, BlockPos, Rotation);
  BoundingBox *(__fastcall *getBoundingBox)(StructurePoolElement *this, BoundingBox *result, BlockPos, Rotation);
  void (__fastcall *setProjection)(StructurePoolElement *this, Projection);
  Projection (__fastcall *getProjection)(StructurePoolElement *this);
  PostProcessSettings (__fastcall *getPostProcessSettings)(StructurePoolElement *this);
  bool (__fastcall *place)(StructurePoolElement *this, BlockSource *, BlockPos, Rotation, BoundingBox, Random *, std::unordered_map<BlockPos,std::optional<ActorDefinitionIdentifier>> *, BlockPos);
  void (__fastcall *placeActors)(StructurePoolElement *this, BlockSource *, BlockPos, Rotation, Random *);
  void (__fastcall *handleJigsawBlock)(StructurePoolElement *this, BlockSource *, JigsawBlockInfo *, LegacyStructureSettings *);
  void (__fastcall *handleDataMarker)(StructurePoolElement *this, BlockSource *, BlockPos, std::string, std::unordered_map<BlockPos,std::optional<ActorDefinitionIdentifier>> *);
  bool (__fastcall *isValid)(StructurePoolElement *this);
  void (__fastcall *~StructurePoolElement)(StructurePoolElement *this);
};

```

### `FlushableStorageAreaEnv`
```
struct __cppobj FlushableStorageAreaEnv : FlushableEnv
{
  std::shared_ptr<Core::FileStorageArea> mStorageArea;
};

```

### `FlushableStorageAreaEnv_vtbl`
```
struct /*VFT*/ FlushableStorageAreaEnv_vtbl
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
  void (__fastcall *flushToPermanentStorage)(FlushableEnv *this);
};

```

### `FillContainerFunction`
```
struct __cppobj FillContainerFunction : LootItemFunction
{
  std::string mLootTable;
};

```

### `FillContainerFunction_vtbl`
```
struct /*VFT*/ FillContainerFunction_vtbl
{
  void (__fastcall *~LootItemFunction)(LootItemFunction *this);
  int (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemInstance *, Random *, LootTableContext *);
  int (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, const Trade *, LootTableContext *);
  void (__fastcall *apply)(LootItemFunction *this, ItemStack *, Random *, LootTableContext *);
};

```

### `FileEntryComparer`
```
struct __cppobj FileEntryComparer
{
};

```

### `FindTargetNode::_findTarget::__l2::SortedEntity`
```
struct FindTargetNode::_findTarget::__l2::SortedEntity
{
  float distSq;
  Actor *ptr;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6a6025a330bc32a52676484b89f42bc>::()::__l5::<lambda_8feab0bb6d6076ddaea0f0c6fdd2a476>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6a6025a330bc32a52676484b89f42bc>::()::__l5::<lambda_8feab0bb6d6076ddaea0f0c6fdd2a476>
{
  LocalPlayer **player;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_b501aa9096a8ed529fb12076180c73f1>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_b501aa9096a8ed529fb12076180c73f1>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_c083550131e71a55511296daac40f470>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_c083550131e71a55511296daac40f470>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_0f88f144beee21e5774357a5f78da137>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_0f88f144beee21e5774357a5f78da137>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_2483871e72b0a3a4918ebadc3d6ad9a5>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_2483871e72b0a3a4918ebadc3d6ad9a5>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_ef2987bf3d9f28b29fff7aa0a64c5416>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_ef2987bf3d9f28b29fff7aa0a64c5416>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_64b49edc8ba5aeeb2f3476bd9b9c093a>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_64b49edc8ba5aeeb2f3476bd9b9c093a>
{
};

```

### `FoldMeuScreenController::setUpCallbacksForBooleanOption::__l5::<lambda_88a7b0e5f2761b34ffb9d0a84e730c1c>`
```
struct __cppobj FoldMeuScreenController::setUpCallbacksForBooleanOption::__l5::<lambda_88a7b0e5f2761b34ffb9d0a84e730c1c>
{
  std::function<bool __cdecl(void)> isEnabled;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_918e92bc02a750928ba6a2b7978a22e3>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_918e92bc02a750928ba6a2b7978a22e3>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6fc73c80d8a9683560641429bd0ed96>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6fc73c80d8a9683560641429bd0ed96>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_e823ae91e9641fd1835e13f3c4ee3ca3>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_e823ae91e9641fd1835e13f3c4ee3ca3>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_6ec23c973f7b6a4da05b0939ba1a1eb0>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_6ec23c973f7b6a4da05b0939ba1a1eb0>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_5ade11331fe1558f519255d4b1202822>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_5ade11331fe1558f519255d4b1202822>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_fa9d43b382490adf14339cf539e74ad6>`
```
struct __cppobj FoldMeuScreenController::setUpCallbacksForBooleanOption::__l2::<lambda_fa9d43b382490adf14339cf539e74ad6>
{
  std::function<void __cdecl(bool)> setValue;
  std::function<bool __cdecl(void)> isEnabled;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_a5e9eed93727d5c4ebb5be06e9c90f04>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_a5e9eed93727d5c4ebb5be06e9c90f04>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_cb3d7b3d49701cb402d19becafe55657>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_cb3d7b3d49701cb402d19becafe55657>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_22fb87d39d0a867e7d00db491a10a129>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_22fb87d39d0a867e7d00db491a10a129>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_2f57f4b9490b0343616042fd9a3c990a>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_2f57f4b9490b0343616042fd9a3c990a>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_08424e551f27aafc65791bc8288cbde3>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_08424e551f27aafc65791bc8288cbde3>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_d157d9d5d6fdbca615e3caa8e0bf4222>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_d157d9d5d6fdbca615e3caa8e0bf4222>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_3ed8c7b17036d6d51f6c5b76009abbb0>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_3ed8c7b17036d6d51f6c5b76009abbb0>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_b5146d2372a6b1483802334539c53cff>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_b5146d2372a6b1483802334539c53cff>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_9ad56d1a09ac749d3b8f4649d9b1d636>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_9ad56d1a09ac749d3b8f4649d9b1d636>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_444e43ea276a91140d204a9cd9f398dc>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_444e43ea276a91140d204a9cd9f398dc>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_0f9b4d753427a8d4bf03f7ba64413b92>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_0f9b4d753427a8d4bf03f7ba64413b92>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6a6025a330bc32a52676484b89f42bc>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_a6a6025a330bc32a52676484b89f42bc>
{
};

```

### `FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_d0a328a4c1f934c10ffb505d9b5e76c9>`
```
struct __cppobj FoldMeuScreenController::_registerEventHandlers::__l2::<lambda_d0a328a4c1f934c10ffb505d9b5e76c9>
{
  FoldMeuScreenController *const __this;
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_b17e57dcd81ae199a0d252bf7005e06e>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_b17e57dcd81ae199a0d252bf7005e06e>
{
};

```

### `FoldMeuScreenController::_registerBindings::__l2::<lambda_3d3e37d1c4de3bdd812b3e051f0c85a9>`
```
struct __cppobj FoldMeuScreenController::_registerBindings::__l2::<lambda_3d3e37d1c4de3bdd812b3e051f0c85a9>
{
};

```

### `FileUpdateCallback`
```
struct __cppobj FileUpdateCallback : DownloadCallback
{
  std::function<void __cdecl(tDownloadInfo &)> succCallback;
  std::function<void __cdecl(tDownloadInfo &)> failCallback;
  std::function<void __cdecl(tDownloadInfo &)> progCallback;
};

```

### `FileUpdateCallback_vtbl`
```
struct /*VFT*/ FileUpdateCallback_vtbl
{
  void (__fastcall *onSuccCallback)(DownloadCallback *this, tDownloadInfo *);
  void (__fastcall *onFailCallback)(DownloadCallback *this, tDownloadInfo *);
  void (__fastcall *onProgCallback)(DownloadCallback *this, tDownloadInfo *);
  void (__fastcall *~DownloadCallback)(DownloadCallback *this);
};

```

### `FaceDirectionalComponentDescription::buildSchema::__l2::<lambda_e384047c49a815c3752804224621532b>`
```
struct __cppobj FaceDirectionalComponentDescription::buildSchema::__l2::<lambda_e384047c49a815c3752804224621532b>
{
};

```

### `FaceDirectionalComponentDescription::buildSchema::__l2::<lambda_66c7ce4eb31239d7104331f3bfa7521d>`
```
struct __cppobj FaceDirectionalComponentDescription::buildSchema::__l2::<lambda_66c7ce4eb31239d7104331f3bfa7521d>
{
  const BlockComponentFactory *factory;
};

```

### `FireResistantComponentDescription::buildSchema::__l2::<lambda_8759fb23e5c0a21392825d06d0b04050>`
```
struct __cppobj FireResistantComponentDescription::buildSchema::__l2::<lambda_8759fb23e5c0a21392825d06d0b04050>
{
  const BlockComponentFactory *factory;
};

```

### `FireResistantComponentDescription::buildSchema::__l2::<lambda_329954e13c2e3af67509eaea49dde588>`
```
struct __cppobj FireResistantComponentDescription::buildSchema::__l2::<lambda_329954e13c2e3af67509eaea49dde588>
{
};

```

### `FeatureLoading::_buildSchema::__l2::<lambda_b9b2bed89d2ad2db6dad7f2f0e544444>`
```
struct __cppobj FeatureLoading::_buildSchema::__l2::<lambda_b9b2bed89d2ad2db6dad7f2f0e544444>
{
};

```

### `FurnaceContainerManagerModel`
```
struct __cppobj FurnaceContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
  int mLastTickCount;
  int mLastLitTime;
  int mLastLitDuration;
  int mLastStoredXP;
  int mLastInputId;
  int mLastInputAux;
  std::string mLastOutputName;
  int mLastResultDisplayId;
  const BlockActorType mBlockActorType;
  const ContainerEnumName mIngredientContainerName;
  const HashedString mRecipeTag;
};

```

