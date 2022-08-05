# G
### `GameRules`
Offset | Type | Name
-|-|-|-
0 | (24) `GameRules::GameRuleMap` | mGameRules


### `GameRules::GameRuleMap`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Vector_base<GameRule>` | baseclass_0


### `GameVersion`
Offset | Type | Name
-|-|-|-
0 | (20) `uint32_t[5]` | mDigit
24 | (32) `std::string` | mString


### `google::protobuf::internal::InternalMetadataWithArena`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::internal::InternalMetadataWithArenaBase<google::protobuf::UnknownFieldSet,google::protobuf::internal::InternalMetadataWithArena>` | baseclass_0


### `google::protobuf::internal::InternalMetadataWithArenaBase<google::protobuf::UnknownFieldSet,google::protobuf::internal::InternalMetadataWithArena>`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ptr_


### `google::protobuf::internal::CachedSize`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<int>` | size_


### `google::protobuf::internal::ArenaStringPtr`
Offset | Type | Name
-|-|-|-
0 | (8) `std::string *` | ptr_


### `grpc_byte_buffer_reader_0`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_byte_buffer *` | buffer_in
8 | (8) `grpc_byte_buffer *` | buffer_out
16 | (4) `grpc_byte_buffer_reader::grpc_byte_buffer_reader_current` | current


### `grpc_byte_buffer_reader::grpc_byte_buffer_reader_current`
Offset | Type | Name
-|-|-|-
0 | (4) `unsigned int` | index


### `grpc_slice_0`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_slice_refcount *` | refcount
8 | (24) `grpc_slice::grpc_slice_data` | data


### `grpc_slice::grpc_slice_data`
Offset | Type | Name
-|-|-|-
0 | (16) `grpc_slice::grpc_slice_data::grpc_slice_refcounted` | refcounted
1 | (24) `grpc_slice::grpc_slice_data::grpc_slice_inlined` | inlined


### `grpc_slice::grpc_slice_data::grpc_slice_refcounted`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | length
8 | (8) `uint8_t *` | bytes


### `grpc_slice::grpc_slice_data::grpc_slice_inlined`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | length
1 | (23) `uint8_t[23]` | bytes


### `grpc_op_0`
Offset | Type | Name
-|-|-|-
0 | (4) `grpc_op_type` | op
4 | (4) `uint32_t` | flags
8 | (8) `void *` | reserved
16 | (64) `grpc_op::grpc_op_data` | data


### `grpc_op::grpc_op_data`
Offset | Type | Name
-|-|-|-
0 | (64) `grpc_op::grpc_op_data::$34088C6F4DED15655F247FDBE876D1D9` | reserved
1 | (24) `grpc_op::grpc_op_data::grpc_op_send_initial_metadata` | send_initial_metadata
2 | (8) `grpc_op::grpc_op_data::grpc_op_send_message` | send_message
3 | (32) `grpc_op::grpc_op_data::grpc_op_send_status_from_server` | send_status_from_server
4 | (8) `grpc_op::grpc_op_data::grpc_op_recv_initial_metadata` | recv_initial_metadata
5 | (8) `grpc_op::grpc_op_data::grpc_op_recv_message` | recv_message
6 | (32) `grpc_op::grpc_op_data::grpc_op_recv_status_on_client` | recv_status_on_client
7 | (8) `grpc_op::grpc_op_data::grpc_op_recv_close_on_server` | recv_close_on_server


### `grpc_op::grpc_op_data::$34088C6F4DED15655F247FDBE876D1D9`
Offset | Type | Name
-|-|-|-
0 | (64) `void *[8]` | reserved


### `grpc_op::grpc_op_data::grpc_op_send_initial_metadata`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | count
8 | (8) `grpc_metadata_0 *` | metadata
16 | (8) `grpc_op::grpc_op_data::grpc_op_send_initial_metadata::grpc_op_send_initial_metadata_maybe_compression_level` | maybe_compression_level


### `grpc_op::grpc_op_data::grpc_op_send_initial_metadata::grpc_op_send_initial_metadata_maybe_compression_level`
Offset | Type | Name
-|-|-|-
0 | (1) `uint8_t` | is_set
4 | (4) `grpc_compression_level` | level


### `grpc_op::grpc_op_data::grpc_op_send_message`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_byte_buffer *` | send_message


### `grpc_op::grpc_op_data::grpc_op_send_status_from_server`
Offset | Type | Name
-|-|-|-
0 | (8) `size_t` | trailing_metadata_count
8 | (8) `grpc_metadata_0 *` | trailing_metadata
16 | (4) `grpc_status_code` | status
24 | (8) `grpc_slice_0 *` | status_details


### `grpc_op::grpc_op_data::grpc_op_recv_initial_metadata`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_metadata_array *` | recv_initial_metadata


### `grpc_op::grpc_op_data::grpc_op_recv_message`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_byte_buffer **` | recv_message


### `grpc_op::grpc_op_data::grpc_op_recv_status_on_client`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_metadata_array *` | trailing_metadata
8 | (8) `grpc_status_code *` | status
16 | (8) `grpc_slice_0 *` | status_details
24 | (8) `const char **` | error_string


### `grpc_op::grpc_op_data::grpc_op_recv_close_on_server`
Offset | Type | Name
-|-|-|-
0 | (8) `int *` | cancelled


### `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::PlayerInfo>`
Offset | Type | Name
-|-|-|-
0 | (24) `google::protobuf::internal::RepeatedPtrFieldBase` | baseclass_0


### `google::protobuf::internal::RepeatedPtrFieldBase`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::Arena *` | arena_
8 | (4) `int` | current_size_
12 | (4) `int` | total_size_
16 | (8) `google::protobuf::internal::RepeatedPtrFieldBase::Rep *` | rep_


### `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::LevelFileAndSize>`
Offset | Type | Name
-|-|-|-
0 | (24) `google::protobuf::internal::RepeatedPtrFieldBase` | baseclass_0


### `GlowStoneFeature`
Offset | Type | Name
-|-|-|-
0 | (24) `Feature` | baseclass_0


### `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$223F7A100DDAA8A38606B413750A9D11` | _anon_0
1 | (8) `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$625273C7149C08D0FA41CF9F848758A0` | _anon_1
2 | (8) `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$63CAF16A424834597E8390533F817872` | _anon_2


### `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$223F7A100DDAA8A38606B413750A9D11`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y


### `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$625273C7149C08D0FA41CF9F848758A0`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r
4 | (4) `float` | g


### `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13::$63CAF16A424834597E8390533F817872`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | s
4 | (4) `float` | t


### `glm::vec2`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13` | _anon_0


### `glm::tvec2<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (8) `glm::tvec2<float,glm::packed_highp>::$653A5DA555E3CFAB9106C77AB2FC5A13` | _anon_0


### `GridPos`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | x
4 | (4) `int` | z


### `GoalSelectorComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<PrioritizedGoal>` | mTargetGoals
24 | (24) `std::vector<PrioritizedGoal>` | mNormalGoals


### `GrowsCropComponent`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mCharges
4 | (12) `BlockPos` | mTargetCrop
16 | (12) `BlockPos` | mLastGrownCrop


### `GameRulesChangedPacketData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GameRule>` | mRules


### `GameRule`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mShouldSave
1 | (1) `GameRule::Type` | mType
4 | (4) `GameRule::Value` | mValue
8 | (32) `std::string` | mName
40 | (1) `bool` | mAllowUseInCommand
41 | (1) `bool` | mIsDefaultSet
42 | (1) `bool` | mRequiresCheats
48 | (32) `GameRule::TagDataNotFoundCallback` | mTagNotFoundCallback
80 | (32) `GameRule::ValidateValueCallback` | mValidateValueCallback


### `GameRule::Value`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | boolVal
1 | (4) `int` | intVal
2 | (4) `float` | floatVal


### `GameRule::TagDataNotFoundCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (GameRule &)>::_Invoker_type` | _M_invoker


### `GameRule::ValidateValueCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<bool (const GameRule::Value &,GameRule::ValidationError *)>::_Invoker_type` | _M_invoker


### `glm::tvec3<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714` | _anon_0


### `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$814015060876AC9E96F7D0FEB9E123E1` | _anon_0
1 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$F8F36499DBCD326E4E26F9313F6D1F57` | _anon_1
2 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$8ACCFA9E7C10CD4A0EE49FAAFA620AD6` | _anon_2


### `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$814015060876AC9E96F7D0FEB9E123E1`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | z


### `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$F8F36499DBCD326E4E26F9313F6D1F57`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r
4 | (4) `float` | g
8 | (4) `float` | b


### `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714::$8ACCFA9E7C10CD4A0EE49FAAFA620AD6`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | s
4 | (4) `float` | t
8 | (4) `float` | p


### `glm::vec3`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714` | _anon_0


### `GuiDataPickItemPacket`
Offset | Type | Name
-|-|-|-
0 | (40) `Packet` | baseclass_0
40 | (32) `std::string` | mItemName
72 | (32) `std::string` | mItemEffectName
104 | (4) `int` | mSlot


### `glm::mat3x3`
Offset | Type | Name
-|-|-|-
0 | (36) `glm::tmat3x3<float,glm::packed_highp>::col_type[3]` | value


### `glm::tmat3x3<float,glm::packed_highp>::col_type`
Offset | Type | Name
-|-|-|-
0 | (12) `glm::tvec3<float,glm::packed_highp>::$F38982D14A5409100D5FF2A83EAF7714` | _anon_0


### `glm::tmat4x4<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,glm::packed_highp>::col_type[4]` | value


### `glm::tmat4x4<float,glm::packed_highp>::col_type`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59` | _anon_0


### `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$805BBB767C835B4C3289FA801EA67DFE` | _anon_0
1 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$ACDA779F9D0E9BFAF3A3754F77F6D102` | _anon_1
2 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$3BEAE2AF5D9A925A3EBB2A45E96DF0DC` | _anon_2
3 | (16) `glm::detail::storage<float,16,false>::type_0` | data


### `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$805BBB767C835B4C3289FA801EA67DFE`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | z
12 | (4) `float` | w


### `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$ACDA779F9D0E9BFAF3A3754F77F6D102`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | r
4 | (4) `float` | g
8 | (4) `float` | b
12 | (4) `float` | a


### `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59::$3BEAE2AF5D9A925A3EBB2A45E96DF0DC`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | s
4 | (4) `float` | t
8 | (4) `float` | p
12 | (4) `float` | q


### `glm::detail::storage<float,16,false>::type_0`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::detail::uint8[16]` | data


### `glm::mat4x4`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,glm::packed_highp>::col_type[4]` | value


### `GoalDefinition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (4) `int` | mPriority
36 | (4) `int` | mRequiredControlFlags
40 | (4) `int` | mScanInterval
44 | (4) `float` | mTargetSearchHeight
48 | (4) `int` | mPersistTargetTicks
52 | (4) `float` | mWithinDefault
56 | (4) `float` | mMaxDist
60 | (4) `float` | mMaxFlee
64 | (4) `float` | mWalkSpeedModifier
68 | (4) `float` | mSprintSpeedModifier
72 | (4) `float` | mProbabilityPerStrength
76 | (4) `float` | mSneakSpeedModifier
80 | (4) `ActorType` | mEntityType
88 | (24) `std::vector<MobDescriptor>` | mMobDescriptions
112 | (1) `bool` | mIgnoreVisibility
116 | (4) `float` | mStartDistance
120 | (4) `float` | mStopDistance
124 | (4) `int` | mRoarDuration
128 | (4) `int` | mRoarAttackTime
132 | (4) `int` | mRoarDamage
136 | (4) `int` | mRoarStrength
140 | (4) `int` | mRoarRange
144 | (64) `ActorFilterGroup` | mKnockbackFilter
208 | (64) `ActorFilterGroup` | mDamageFilter
272 | (128) `DefinitionTrigger` | mOnRoarEnd
400 | (4) `float` | mYd
404 | (4) `float` | mStalkSpeed
408 | (4) `float` | mMaxStalkDist
412 | (4) `float` | mLeapHeight
416 | (4) `float` | mLeapDistance
420 | (4) `float` | mPounceMaxDistance
424 | (4) `float` | mStrikeDistance
428 | (4) `float` | mStuckTime
432 | (64) `ActorFilterGroup` | mBlockFilter
496 | (4) `float` | mLookDistance
500 | (4) `int` | mAngleOfViewX
504 | (4) `int` | mAngleOfViewY
508 | (4) `float` | mProbability
512 | (64) `ActorFilterGroup` | mTargetFilter
576 | (4) `int` | mMinLookTime
580 | (4) `int` | mMaxLookTime
584 | (4) `int` | mMinLookAroundTime
588 | (4) `int` | mMaxLookAroundTime
592 | (4) `float` | mMinimumRadius
596 | (1) `bool` | mBroadcast
600 | (4) `float` | mBroadcastRange
608 | (128) `DefinitionTrigger` | mWithinRadiusEvent
736 | (128) `DefinitionTrigger` | mHurtByTargetEvent
864 | (4) `float` | mPercentChance
868 | (4) `ActorCategory` | mAttackTypes
872 | (4) `int` | mRandomStopInterval
876 | (4) `float` | mReachMultiplier
880 | (4) `float` | mMeleeFOV
884 | (1) `bool` | mAttackOnce
888 | (4) `int` | mRandomSoundInterval
892 | (1) `bool` | mRequireCompletePath
896 | (128) `DefinitionTrigger` | mOnAttack
1024 | (4) `float` | mAttackDuration
1028 | (4) `float` | mHitDelay
1032 | (4) `LevelSoundEvent` | mDelayedAttackSound
1040 | (128) `DefinitionTrigger` | mOnEat
1168 | (4) `int` | mDelayBeforeEating
1172 | (4) `int` | mWaitTime
1176 | (4) `float` | mExploreDist
1184 | (24) `std::vector<DefinitionTrigger>` | mOnHomeTriggers
1208 | (24) `std::vector<DefinitionTrigger>` | mOnFailedTriggers
1232 | (128) `DefinitionTrigger` | mOnLayEvent
1360 | (128) `DefinitionTrigger` | mOnWorkArrivalEvent
1488 | (4) `float` | mTargetDist
1492 | (4) `float` | mSpeedModifier
1496 | (4) `int` | mSearchRange
1500 | (4) `int` | mSearchHeight
1504 | (4) `int` | mSearchCount
1508 | (4) `float` | mGoalRadius
1512 | (120) `GoalDefinition::$A96817768A54EC800FE0CCD12036E025` | mMoveToBlockGoalData
1632 | (4) `float` | mWithin
1636 | (1) `bool` | mIgnoreMobDamage
1637 | (1) `bool` | mForceUse
1640 | (4) `float` | mLookAhead
1644 | (4) `float` | mCenteredGap
1648 | (4) `float` | mMoveSpeed
1652 | (4) `int` | mEntityCount
1656 | (4) `int` | mXZDist
1660 | (4) `int` | mYDist
1664 | (4) `float` | mYOffset
1668 | (4) `int` | mInterval
1672 | (4) `float` | mCooldown
1676 | (1) `__int8` | _bf_68c
1680 | (4) `float` | mRangedFOV
1684 | (4) `int` | mAttackIntervalMin
1688 | (4) `int` | mAttackIntervalMax
1692 | (4) `float` | mAttackRadius
1696 | (4) `float` | mChargeChargedTrigger
1700 | (4) `float` | mChargeShootTrigger
1704 | (4) `int` | mBurstShots
1708 | (4) `float` | mBurstInterval
1712 | (2) `__int16` | _bf_6b0
1714 | (1) `bool` | mHurtOwner
1716 | (4) `int` | mMustSeeForgetTicks
1720 | (24) `std::vector<ItemDescriptor>` | mItemList
1744 | (1) `bool` | mCanTemptVertically
1748 | (4) `int` | mMaxToEat
1752 | (4) `int` | mEatDelay
1756 | (4) `int` | mFullDelay
1760 | (4) `int` | mInitialEatDelay
1768 | (48) `std::set<const Block *>` | mBlockList
1816 | (4) `float` | mFloatHeightOffset
1820 | (1) `bool` | mRandomReselect
1824 | (8) `FloatRange` | mFloatDuration
1832 | (8) `IntRange` | mHoverHeight
1840 | (4) `float` | mDuration
1844 | (8) `FloatRange` | mRadiusRange
1852 | (4) `int` | mRadiusChangeChance
1856 | (8) `FloatRange` | mAboveTargetRange
1864 | (8) `FloatRange` | mHeightOffsetRange
1872 | (4) `int` | mHeightChangeChance
1876 | (8) `FloatRange` | mDelayRange
1888 | (24) `std::vector<SummonSpellData>` | mSummonSpellData
1912 | (4) `POIType` | mPOIType
1916 | (4) `int` | mGoalCooldown
1920 | (4) `int` | mActiveTime
1924 | (4) `int` | mRandomSoundIntervalMin
1928 | (4) `int` | mRandomSoundIntervalMax
1932 | (1) `bool` | mCanWorkInRain
1936 | (4) `int` | mWorkInRainTolerance
1940 | (4) `float` | mFollowDistance
1944 | (4) `float` | mBlockDistance
1952 | (24) `std::vector<SendEventData>` | mSendEventData
1976 | (4) `int` | mStartDelay
1980 | (4) `int` | mMaxFailedAttempts
1984 | (1) `bool` | mAvoidWater
1985 | (1) `bool` | mPreferWater
1986 | (1) `bool` | mTargetNeeded
1988 | (4) `float` | mMountDistance
1992 | (24) `std::vector<DrinkPotionData>` | mDrinkPotionData
2016 | (4) `float` | mDrinkSpeedModifier
2020 | (4) `float` | mDropItemChance
2024 | (128) `DefinitionTrigger` | mOnDropAttemptEvent
2152 | (4) `float` | mOfferingDistance
2160 | (32) `std::string` | mLootTable
2192 | (8) `FloatRange` | mTimeOfDayRange
2200 | (4) `float` | mSnackingCooldown
2204 | (4) `float` | mSnackingCooldownMin
2208 | (4) `float` | mStopSnackingChance
2212 | (4) `float` | mStopChance
2216 | (4) `float` | mStartChance
2220 | (4) `float` | mSittingTimeMin
2224 | (4) `float` | mSittingCooldown
2232 | (32) `std::string` | mSound
2264 | (32) `std::string` | mPrepareSound
2296 | (4) `float` | mPrepareTime
2304 | (32) `std::string` | mAggroSound
2336 | (128) `DefinitionTrigger` | mOnDefendEvent
2464 | (4) `float` | mSleepYOffset
2468 | (4) `float` | mSleepColliderHeight
2472 | (4) `float` | mSleepColliderWidth
2476 | (4) `float` | mCooldownMax
2480 | (4) `float` | mCooldownMin
2484 | (4) `float` | mDetectMobDistance
2488 | (4) `float` | mDetectMobHeight
2496 | (64) `ActorFilterGroup` | mCanNapFilters
2560 | (64) `ActorFilterGroup` | mWakeMobExceptionFilters
2624 | (4) `float` | mInterestTime
2628 | (4) `float` | mRemoveItemTime
2632 | (4) `float` | mCarriedItemSwitchTime
2636 | (4) `float` | mInterestCooldown
2640 | (4) `float` | mCooldownTimeoutTime
2648 | (168) `ActorDefinitionIdentifier` | mDesiredMingleType
2816 | (4) `float` | mMingleDistance
2820 | (4) `int` | mMinLookCount
2824 | (4) `int` | mMaxLookCount
2828 | (8) `FloatRange` | mSoundInterval
2836 | (8) `FloatRange` | mJumpInterval
2848 | (128) `DefinitionTrigger` | mOnCelebrationEndEvent
2976 | (32) `std::string` | mCelebrationSound


### `GoalDefinition::$A96817768A54EC800FE0CCD12036E025`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | speedModifier
4 | (4) `int` | searchRange
8 | (4) `int` | searchHeight
12 | (4) `float` | goalRadius
16 | (4) `int` | tickInterval
20 | (4) `float` | stayDuration
24 | (24) `std::vector<DefinitionTrigger>` | onReachTriggers
48 | (24) `std::vector<DefinitionTrigger>` | onStayCompletedTriggers
72 | (24) `std::vector<ItemDescriptor>` | targetDescriptors
96 | (12) `Vec3` | targetPositionOffset
108 | (4) `float` | chanceToStart
112 | (1) `TargetSelectionMethod` | targetSelectionMethod


### `GoalDefinition_0::parse::$77030C46F7368D1C8A31176E7D1C3EB3`
Offset | Type | Name
-|-|-|-
0 | (8) `GoalDefinition_0 *` | this


### `glm::vec4`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59` | _anon_0


### `glm::mat4`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,glm::packed_highp>::col_type[4]` | value


### `GameMasterEntityServerCommandOrigin`
Offset | Type | Name
-|-|-|-
0 | (40) `ActorServerCommandOrigin` | baseclass_0


### `GetBlockFunction`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<const Block &(const BlockPos &)>::_Invoker_type` | _M_invoker


### `GridArea<std::shared_ptr<LevelChunk> >::AddCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (buffer_span_mut<std::shared_ptr<LevelChunk> >,buffer_span<unsigned int>)>::_Invoker_type` | _M_invoker


### `GridArea<std::shared_ptr<LevelChunk> >::Definition`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | chunkSide
4 | (2) `Height` | minHeight
6 | (2) `Height` | maxHeight
8 | (1) `bool` | circle
16 | (32) `GridArea<std::shared_ptr<LevelChunk> >::GenerateCallback` | generate
48 | (32) `GridArea<std::shared_ptr<LevelChunk> >::DestroyCallback` | destroy
80 | (32) `GridArea<std::shared_ptr<LevelChunk> >::AddCallback` | add


### `GridArea<std::shared_ptr<LevelChunk> >::GenerateCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (buffer_span<Pos>,buffer_span_mut<std::shared_ptr<LevelChunk> >)>::_Invoker_type` | _M_invoker


### `GridArea<std::shared_ptr<LevelChunk> >::DestroyCallback`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<void (buffer_span_mut<std::shared_ptr<LevelChunk> >)>::_Invoker_type` | _M_invoker


### `GameRules::_registerRules::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `GameRuleId`
Offset | Type | Name
-|-|-|-
0 | (4) `NewType<int>` | baseclass_0


### `google_breakpad::MinidumpDescriptor`
Offset | Type | Name
-|-|-|-
0 | (4) `google_breakpad::MinidumpDescriptor::DumpMode` | mode_
4 | (4) `int` | fd_
8 | (32) `std::string` | directory_
40 | (32) `std::string` | path_
72 | (8) `const char *` | c_path_
80 | (8) `off_t` | size_limit_
88 | (24) `google_breakpad::MicrodumpExtraInfo` | microdump_extra_info_


### `google_breakpad::MicrodumpExtraInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `const char *` | build_fingerprint
8 | (8) `const char *` | product_info
16 | (8) `const char *` | gpu_fingerprint


### `GeneticVariant`
Offset | Type | Name
-|-|-|-
0 | (8) `IntRange` | mainAllele
8 | (8) `IntRange` | hiddenAllele
16 | (8) `IntRange` | eitherAllele
24 | (8) `IntRange` | bothAllele
32 | (128) `DefinitionTrigger` | onBorn


### `GeneticsComponent::Gene`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | mainAllele
4 | (4) `int` | hiddenAllele


### `GeneDefinition`
Offset | Type | Name
-|-|-|-
0 | (32) `std::string` | mName
32 | (8) `IntRange` | mAlleleRange
40 | (24) `std::vector<GeneticVariant>` | mGeneticVariants


### `GiveableTrigger`
Offset | Type | Name
-|-|-|-
0 | (48) `std::set<const Item *>` | mGiveableItems
48 | (128) `DefinitionTrigger` | mOnGive
176 | (4) `float` | mCoolDown


### `GameRule::ValidationError`
Offset | Type | Name
-|-|-|-
0 | (1) `bool` | mSuccess
8 | (32) `std::string` | mErrorDescription
40 | (24) `std::vector<std::string>` | mErrorParameters


### `GenericQueryFunctionAccessor`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_Function_base` | baseclass_0
24 | (8) `std::function<MolangScriptArg (RenderParams &,const std::vector<MolangScriptArg> &)>::_Invoker_type` | _M_invoker


### `GeneticsComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<GeneticsComponent::Gene>` | mGenes
24 | (8) `const GeneticsDefinition *` | mGeneticsDescription
32 | (8) `Random *` | mRandom


### `GiveableComponent`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<unsigned long>` | mCoolDownTimeStamps


### `glm::tmat3x3<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (36) `glm::tmat3x3<float,glm::packed_highp>::col_type[3]` | value


### `google_breakpad::PageAllocator`
Offset | Type | Name
-|-|-|-
0 | (8) `const size_t` | page_size_
8 | (8) `google_breakpad::PageAllocator::PageHeader *` | last_
16 | (8) `uint8_t *` | current_page_
24 | (8) `size_t` | page_offset_
32 | (8) `unsigned __int64` | pages_allocated_


### `google_breakpad::ThreadArgument`
Offset | Type | Name
-|-|-|-
0 | (4) `pid_t` | pid
8 | (8) `const google_breakpad::MinidumpDescriptor *` | minidump_descriptor
16 | (8) `google_breakpad::ExceptionHandler *` | handler
24 | (8) `const void *` | context
32 | (8) `size_t` | context_size


### `google_breakpad::ExceptionHandler`
Offset | Type | Name
-|-|-|-
0 | (8) `const google_breakpad::ExceptionHandler::FilterCallback` | filter_
8 | (8) `const google_breakpad::ExceptionHandler::MinidumpCallback` | callback_
16 | (8) `void *const` | callback_context_
24 | (8) `google_breakpad::scoped_ptr<google_breakpad::CrashGenerationClient>` | crash_generation_client_
32 | (112) `google_breakpad::MinidumpDescriptor` | minidump_descriptor_
144 | (8) `volatile google_breakpad::ExceptionHandler::HandlerCallback` | crash_handler_
152 | (8) `int[2]` | fdes
160 | (24) `google_breakpad::MappingList` | mapping_list_
184 | (24) `google_breakpad::AppMemoryList` | app_memory_list_


### `google_breakpad::scoped_ptr<google_breakpad::CrashGenerationClient>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::CrashGenerationClient *` | ptr_


### `google_breakpad::MappingList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_List_base<google_breakpad::MappingEntry>` | baseclass_0


### `google_breakpad::AppMemoryList`
Offset | Type | Name
-|-|-|-
0 | (24) `std::_List_base<google_breakpad::AppMemory>` | baseclass_0


### `google_breakpad::ExceptionHandler::CrashContext`
Offset | Type | Name
-|-|-|-
0 | (128) `siginfo_t` | siginfo
128 | (4) `pid_t` | tid
136 | (936) `ucontext_t_0` | context
1072 | (512) `google_breakpad::fpstate_t` | float_state


### `google_breakpad::fpstate_t`
Offset | Type | Name
-|-|-|-
0 | (2) `__uint16_t` | cwd
2 | (2) `__uint16_t` | swd
4 | (2) `__uint16_t` | ftw
6 | (2) `__uint16_t` | fop
8 | (8) `__uint64_t` | _rip
16 | (8) `__uint64_t` | rdp
24 | (4) `__uint32_t` | _mxcsr
28 | (4) `__uint32_t` | mxcr_mask
32 | (128) `_libc_fpxreg[8]` | _st
160 | (256) `_libc_xmmreg[16]` | _xmm
416 | (96) `__uint32_t[24]` | __glibc_reserved1


### `google_breakpad::MappingInfo`
Offset | Type | Name
-|-|-|-
0 | (8) `uintptr_t` | start_addr
8 | (8) `size_t` | size
16 | (8) `size_t` | offset
24 | (1) `bool` | exec
25 | (255) `char[255]` | name


### `google_breakpad::MappingEntry`
Offset | Type | Name
-|-|-|-
0 | (280) `google_breakpad::MappingInfo` | first
280 | (16) `uint8_t[16]` | second


### `google_breakpad::AppMemory`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | ptr
8 | (8) `size_t` | length


### `GUID`
Offset | Type | Name
-|-|-|-
0 | (4) `uint32_t` | data1
4 | (2) `uint16_t` | data2
6 | (2) `uint16_t` | data3
8 | (8) `uint8_t[8]` | data4


### `google_breakpad::LinuxPtraceDumper`
Offset | Type | Name
-|-|-|-
0 | (224) `google_breakpad::LinuxDumper` | baseclass_0
224 | (1) `bool` | threads_suspended_


### `google_breakpad::LinuxDumper`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$LinuxDumper
8 | (4) `const pid_t` | pid_
16 | (8) `const char *const` | root_prefix_
24 | (8) `uintptr_t` | crash_address_
32 | (4) `int` | crash_signal_
36 | (4) `pid_t` | crash_thread_
40 | (40) `google_breakpad::PageAllocator` | allocator_
80 | (48) `google_breakpad::wasteful_vector<int>` | threads_
128 | (48) `google_breakpad::wasteful_vector<google_breakpad::MappingInfo *>` | mappings_
176 | (48) `google_breakpad::wasteful_vector<unsigned long>` | auxv_


### `google_breakpad::wasteful_vector<int>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<int,google_breakpad::PageStdAllocator<int> >` | baseclass_0


### `google_breakpad::wasteful_vector<google_breakpad::MappingInfo *>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<google_breakpad::MappingInfo *,google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *> >` | baseclass_0


### `google_breakpad::wasteful_vector<unsigned long>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<unsigned long,google_breakpad::PageStdAllocator<unsigned long> >` | baseclass_0


### `google_breakpad::MinidumpFileWriter`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | file_
4 | (1) `bool` | close_file_when_destroyed_
8 | (4) `MDRVA` | position_
16 | (8) `size_t` | size_


### `google_breakpad::wasteful_vector<MDMemoryDescriptor>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<MDMemoryDescriptor,google_breakpad::PageStdAllocator<MDMemoryDescriptor> >` | baseclass_0


### `google_breakpad::UntypedMDRVA`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::MinidumpFileWriter *` | writer_
8 | (4) `MDRVA` | position_
16 | (8) `size_t` | size_


### `google_breakpad::TypedMDRVA<MDRawDirectory>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (12) `MDRawDirectory` | data_
36 | (4) `google_breakpad::TypedMDRVA<MDRawDirectory>::AllocationState` | allocation_state_


### `google_breakpad::TypedMDRVA<MDRawHeader>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (32) `$505B58DFE4F8194A15938BA4CDF168E6` | data_
56 | (4) `google_breakpad::TypedMDRVA<MDRawHeader>::AllocationState` | allocation_state_


### `google_breakpad::TypedMDRVA<unsigned int>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (4) `unsigned int` | data_
28 | (4) `google_breakpad::TypedMDRVA<unsigned int>::AllocationState` | allocation_state_


### `google_breakpad::TypedMDRVA<MDRawContextAMD64>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (1232) `MDRawContextAMD64` | data_
1256 | (4) `google_breakpad::TypedMDRVA<MDRawContextAMD64>::AllocationState` | allocation_state_


### `google_breakpad::ThreadInfo`
Offset | Type | Name
-|-|-|-
0 | (4) `pid_t` | tgid
4 | (4) `pid_t` | ppid
8 | (8) `uintptr_t` | stack_pointer
16 | (216) `user_regs_struct` | regs
232 | (512) `user_fpregs_struct` | fpregs
744 | (64) `google_breakpad::debugreg_t[8]` | dregs


### `google_breakpad::TypedMDRVA<MDRawExceptionStream>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (168) `$2CCFF0E0CE8001A98FB5D6703B5EE6EF` | data_
192 | (4) `google_breakpad::TypedMDRVA<MDRawExceptionStream>::AllocationState` | allocation_state_


### `google_breakpad::TypedMDRVA<MDRawSystemInfo>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (56) `MDRawSystemInfo` | data_
80 | (4) `google_breakpad::TypedMDRVA<MDRawSystemInfo>::AllocationState` | allocation_state_


### `google_breakpad::TypedMDRVA<MDRawDebug64>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (40) `$7C6655196A4AF765C464D6B72AEFAD0C` | data_
64 | (4) `google_breakpad::TypedMDRVA<MDRawDebug64>::AllocationState` | allocation_state_


### `google_breakpad::wasteful_vector<char>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<char,google_breakpad::PageStdAllocator<char> >` | baseclass_0


### `google_breakpad::TypedMDRVA<MDRawLinkMap64>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (24) `MDRawLinkMap64` | data_
48 | (4) `google_breakpad::TypedMDRVA<MDRawLinkMap64>::AllocationState` | allocation_state_


### `google_breakpad::auto_wasteful_vector<unsigned char,20>`
Offset | Type | Name
-|-|-|-
0 | (48) `google_breakpad::wasteful_vector<unsigned char>` | baseclass_0
48 | (20) `unsigned __int8[20]` | stackdata_


### `google_breakpad::wasteful_vector<unsigned char>`
Offset | Type | Name
-|-|-|-
0 | (48) `std::vector<unsigned char,google_breakpad::PageStdAllocator<unsigned char> >` | baseclass_0


### `google_breakpad::PageStdAllocator<unsigned char>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<unsigned char>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<unsigned char>::size_type` | stackdata_size_


### `google_breakpad::MemoryMappedFile`
Offset | Type | Name
-|-|-|-
0 | (16) `google_breakpad::MemoryRange` | content_


### `google_breakpad::MemoryRange`
Offset | Type | Name
-|-|-|-
0 | (8) `const uint8_t *` | data_
8 | (8) `size_t` | length_


### `google_breakpad::elf_aux_entry`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | a_type
8 | (8) `Elf64_auxv_t::$218B18A37F77BA833A070E25C7DC6FF2` | a_un


### `google_breakpad::RawContextCPU`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | p1_home
8 | (8) `uint64_t` | p2_home
16 | (8) `uint64_t` | p3_home
24 | (8) `uint64_t` | p4_home
32 | (8) `uint64_t` | p5_home
40 | (8) `uint64_t` | p6_home
48 | (4) `uint32_t` | context_flags
52 | (4) `uint32_t` | mx_csr
56 | (2) `uint16_t` | _cs
58 | (2) `uint16_t` | _ds
60 | (2) `uint16_t` | _es
62 | (2) `uint16_t` | _fs
64 | (2) `uint16_t` | _gs
66 | (2) `uint16_t` | _ss
68 | (4) `uint32_t` | eflags
72 | (8) `uint64_t` | dr0
80 | (8) `uint64_t` | dr1
88 | (8) `uint64_t` | dr2
96 | (8) `uint64_t` | dr3
104 | (8) `uint64_t` | dr6
112 | (8) `uint64_t` | dr7
120 | (8) `uint64_t` | _rax
128 | (8) `uint64_t` | _rcx
136 | (8) `uint64_t` | _rdx
144 | (8) `uint64_t` | _rbx
152 | (8) `uint64_t` | _rsp
160 | (8) `uint64_t` | _rbp
168 | (8) `uint64_t` | _rsi
176 | (8) `uint64_t` | _rdi
184 | (8) `uint64_t` | _r8
192 | (8) `uint64_t` | _r9
200 | (8) `uint64_t` | _r10
208 | (8) `uint64_t` | _r11
216 | (8) `uint64_t` | _r12
224 | (8) `uint64_t` | _r13
232 | (8) `uint64_t` | _r14
240 | (8) `uint64_t` | _r15
248 | (8) `uint64_t` | _rip
256 | (512) `MDRawContextAMD64::$D520141881593523D1DB94D2DAC55DA9` | _anon_0
768 | (416) `uint128_struct[26]` | vector_register
1184 | (8) `uint64_t` | vector_control
1192 | (8) `uint64_t` | debug_control
1200 | (8) `uint64_t` | last_branch_to_rip
1208 | (8) `uint64_t` | last_branch_from_rip
1216 | (8) `uint64_t` | last_exception_to_rip
1224 | (8) `uint64_t` | last_exception_from_rip


### `google_breakpad::TypedMDRVA<MDString>`
Offset | Type | Name
-|-|-|-
0 | (24) `google_breakpad::UntypedMDRVA` | baseclass_0
24 | (8) `$10AD719A749B48FD0C0A3351B1A2B499` | data_
32 | (4) `google_breakpad::TypedMDRVA<MDString>::AllocationState` | allocation_state_


### `google_breakpad::scoped_array<unsigned short>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int16 *` | array_


### `google_breakpad::scoped_array<unsigned char>`
Offset | Type | Name
-|-|-|-
0 | (8) `unsigned __int8 *` | array_


### `google::protobuf::internal::once_flag`
Offset | Type | Name
-|-|-|-
0 | (4) `std::once_flag::__native_type` | _M_once


### `google::protobuf::internal::ExtensionIdentifier<google::protobuf::FileOptions,google::protobuf::internal::StringTypeTraits,'_t',false>`
Offset | Type | Name
-|-|-|-
0 | (4) `const int` | number_
8 | (8) `google::protobuf::internal::StringTypeTraits::ConstType` | default_value_


### `gpr_timespec_0`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | tv_sec
8 | (4) `int32_t` | tv_nsec
12 | (4) `gpr_clock_type` | clock_type


### `google::protobuf::internal::ExplicitlyConstructed<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >`
Offset | Type | Name
-|-|-|-
0 | (32) `google::protobuf::internal::ExplicitlyConstructed<std::string >::AlignedUnion` | union_


### `google::protobuf::internal::ExplicitlyConstructed<std::__cxx11::basic_string<char,std::char_traits<char>,std::allocator<char> > >::AlignedUnion`
Offset | Type | Name
-|-|-|-
0 | (32) `char[32]` | space
1 | (8) `google::protobuf::int64` | align_to_int64
2 | (8) `void *` | align_to_ptr


### `grpc_completion_queue_attributes_0`
Offset | Type | Name
-|-|-|-
0 | (4) `int` | version
4 | (4) `grpc_cq_completion_type` | cq_completion_type
8 | (4) `grpc_cq_polling_type` | cq_polling_type
16 | (8) `grpc_experimental_completion_queue_functor_0 *` | cq_shutdown_cb


### `glm::tvec4<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tvec4<float,glm::packed_highp>::$36BDC9567EB6C00EB115CBFBA7286E59` | _anon_0


### `Goal:96`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Goal
8 | (4) `int` | mRequiredControlFlags


### `Goal`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$Goal
8 | (4) `int` | mRequiredControlFlags


### `glm::tmat4x4<float,glm::packed_highp>::transpose_type`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::tmat4x4<float,glm::packed_highp>::col_type[4]` | value


### `glm::tquat<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tquat<float,glm::packed_highp>::$8B90D65E2B902F9818D8631C8F9DB935` | _anon_0


### `glm::tquat<float,glm::packed_highp>::$8B90D65E2B902F9818D8631C8F9DB935`
Offset | Type | Name
-|-|-|-
0 | (16) `glm::tquat<float,glm::packed_highp>::$8B90D65E2B902F9818D8631C8F9DB935::$805BBB767C835B4C3289FA801EA67DFE` | _anon_0
1 | (16) `glm::detail::storage<float,16,false>::type_0` | data


### `glm::tquat<float,glm::packed_highp>::$8B90D65E2B902F9818D8631C8F9DB935::$805BBB767C835B4C3289FA801EA67DFE`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
4 | (4) `float` | y
8 | (4) `float` | z
12 | (4) `float` | w


### `Ghast::updateEntitySpecificMolangVariables::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `GameMode`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$GameMode
8 | (8) `Player *` | mPlayer
16 | (12) `BlockPos` | mDestroyBlockPos
28 | (4) `float` | mOldDestroyProgress
32 | (4) `float` | mDestroyProgress
40 | (8) `double` | mLastDestroyTime
48 | (4) `float` | mDistanceTravelled
52 | (12) `Vec3` | mPlayerLastPosition
64 | (12) `BlockPos` | mLastBuiltBlockPosition
76 | (1) `bool` | mLastBuildBlockWasInteractive
77 | (1) `bool` | mLastBuildBlockWasSnappable
80 | (4) `float` | mMinPlayerSpeed
88 | (8) `std::chrono::_V2::steady_clock::time_point` | mLastBuildTime
96 | (8) `std::chrono::_V2::steady_clock::time_point` | mNoDestroyUntil
104 | (8) `std::chrono::_V2::steady_clock::time_point` | mNoDestroySoundUntil
112 | (8) `std::chrono::milliseconds` | creativeDestructionTickDelay
120 | (8) `std::chrono::milliseconds` | buildingTickDelay
128 | (8) `std::chrono::milliseconds` | destroySoundDelay
136 | (1) `bool` | mHasBuildDirection
137 | (1) `bool` | mHasLastBuiltPosition
138 | (1) `FacingID` | mContinueFacing
140 | (12) `BlockPos` | mBuildDirection
152 | (12) `BlockPos` | mNextBuildPos


### `glm::tvec1<float,glm::packed_highp>`
Offset | Type | Name
-|-|-|-
0 | (4) `glm::tvec1<float,glm::packed_highp>::$1F160FB999C380CA18558A34A1C7792D` | _anon_0


### `glm::tvec1<float,glm::packed_highp>::$1F160FB999C380CA18558A34A1C7792D`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | x
1 | (4) `float` | r
2 | (4) `float` | s


### `GameRuleCommand::InitProxy`
Offset | Type | Name
-|-|-|-
0 | (8) `GameRules *` | mGameRules


### `GoHomeGoal`
Offset | Type | Name
-|-|-|-
0 | (16) `Goal` | baseclass_0
16 | (8) `Mob *` | mMob
24 | (4) `float` | mSpeedMod
28 | (4) `int` | mInterval
32 | (4) `float` | mGoalRadius
40 | (24) `const std::vector<DefinitionTrigger>` | mOnHomeTriggers
64 | (24) `const std::vector<DefinitionTrigger>` | mOnFailedTriggers
88 | (12) `BlockPos` | mLastEndPos


### `google_breakpad::PageStdAllocator<MDMemoryDescriptor>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<MDMemoryDescriptor>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<MDMemoryDescriptor>::size_type` | stackdata_size_


### `google_breakpad::PageStdAllocator<char>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<char>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<char>::size_type` | stackdata_size_


### `google_breakpad::PageStdAllocator<int>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<int>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<int>::size_type` | stackdata_size_


### `google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::size_type` | stackdata_size_


### `google_breakpad::PageStdAllocator<unsigned long>`
Offset | Type | Name
-|-|-|-
0 | (8) `google_breakpad::PageAllocator *` | allocator_
8 | (8) `google_breakpad::PageStdAllocator<unsigned long>::pointer` | stackdata_
16 | (8) `google_breakpad::PageStdAllocator<unsigned long>::size_type` | stackdata_size_


### `google::protobuf::internal::SCCInfoBase`
Offset | Type | Name
-|-|-|-
0 | (4) `std::atomic<int>` | visit_status
4 | (4) `int` | num_deps
8 | (8) `void (*)(void)` | init_func


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerInfo>`
Offset | Type | Name
-|-|-|-
0 | (40) `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerInfo>::AlignedUnion` | union_


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerInfo>::AlignedUnion`
Offset | Type | Name
-|-|-|-
0 | (40) `char[40]` | space
1 | (8) `google::protobuf::int64` | align_to_int64
2 | (8) `void *` | align_to_ptr


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerAndMessage>`
Offset | Type | Name
-|-|-|-
0 | (40) `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerAndMessage>::AlignedUnion` | union_


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerAndMessage>::AlignedUnion`
Offset | Type | Name
-|-|-|-
0 | (40) `char[40]` | space
1 | (8) `google::protobuf::int64` | align_to_int64
2 | (8) `void *` | align_to_ptr


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_BandwithMetric>`
Offset | Type | Name
-|-|-|-
0 | (64) `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_BandwithMetric>::AlignedUnion` | union_


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_BandwithMetric>::AlignedUnion`
Offset | Type | Name
-|-|-|-
0 | (64) `char[64]` | space
1 | (8) `google::protobuf::int64` | align_to_int64
2 | (8) `void *` | align_to_ptr


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_LatencyMetric>`
Offset | Type | Name
-|-|-|-
0 | (48) `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_LatencyMetric>::AlignedUnion` | union_


### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport_LatencyMetric>::AlignedUnion`
Offset | Type | Name
-|-|-|-
0 | (48) `char[48]` | space
1 | (8) `google::protobuf::int64` | align_to_int64
2 | (8) `void *` | align_to_ptr


### `google::protobuf::io::CodedInputStream`
Offset | Type | Name
-|-|-|-
0 | (8) `const google::protobuf::uint8 *` | buffer_
8 | (8) `const google::protobuf::uint8 *` | buffer_end_
16 | (8) `google::protobuf::io::ZeroCopyInputStream *` | input_
24 | (4) `int` | total_bytes_read_
28 | (4) `int` | overflow_bytes_
32 | (4) `google::protobuf::uint32` | last_tag_
36 | (1) `bool` | legitimate_message_end_
37 | (1) `bool` | aliasing_enabled_
40 | (4) `google::protobuf::io::CodedInputStream::Limit` | current_limit_
44 | (4) `int` | buffer_size_after_limit_
48 | (4) `int` | total_bytes_limit_
52 | (4) `int` | recursion_budget_
56 | (4) `int` | recursion_limit_
64 | (8) `const google::protobuf::DescriptorPool *` | extension_pool_
72 | (8) `google::protobuf::MessageFactory *` | extension_factory_


### `google::protobuf::UnknownFieldSet`
Offset | Type | Name
-|-|-|-
0 | (8) `std::vector<google::protobuf::UnknownField> *` | fields_


### `google::protobuf::io::ZeroCopyInputStream`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$ZeroCopyInputStream


### `gpr_timespec`
Offset | Type | Name
-|-|-|-
0 | (8) `int64_t` | tv_sec
8 | (4) `int32_t` | tv_nsec
12 | (4) `gpr_clock_type` | clock_type


### `grpc_slice`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_slice_refcount *` | refcount
8 | (24) `grpc_slice::grpc_slice_data` | data


### `google::protobuf::io::CodedOutputStream`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::io::ZeroCopyOutputStream *` | output_
8 | (8) `google::protobuf::uint8 *` | buffer_
16 | (4) `int` | buffer_size_
20 | (4) `int` | total_bytes_
24 | (1) `bool` | had_error_
25 | (1) `bool` | aliasing_enabled_
26 | (1) `bool` | is_serialization_deterministic_


### `google::protobuf::internal::WrappedMutex`
Offset | Type | Name
-|-|-|-
0 | (40) `std::mutex` | mu_


### `google::protobuf::internal::MutexLock`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::internal::Mutex *const` | mu_


### `google::protobuf::internal::MutexLockMaybe`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::internal::Mutex *const` | mu_


### `google::protobuf::internal::MigrationSchema`
Offset | Type | Name
-|-|-|-
0 | (4) `google::protobuf::int32` | offsets_index
4 | (4) `google::protobuf::int32` | has_bit_indices_index
8 | (4) `int` | object_size


### `google::protobuf::FieldDescriptor`
Offset | Type | Name
-|-|-|-
0 | (8) `const std::string *` | name_
8 | (8) `const std::string *` | full_name_
16 | (8) `const std::string *` | lowercase_name_
24 | (8) `const std::string *` | camelcase_name_
32 | (8) `const std::string *` | json_name_
40 | (8) `const google::protobuf::FileDescriptor *` | file_
48 | (8) `google::protobuf::GoogleOnceDynamic *` | type_once_
56 | (4) `google::protobuf::FieldDescriptor::Type` | type_
60 | (4) `google::protobuf::FieldDescriptor::Label` | label_
64 | (1) `bool` | has_default_value_
65 | (1) `bool` | has_json_name_
66 | (1) `bool` | is_extension_
68 | (4) `int` | number_
72 | (4) `int` | index_in_oneof_
80 | (8) `const google::protobuf::Descriptor *` | containing_type_
88 | (8) `const google::protobuf::OneofDescriptor *` | containing_oneof_
96 | (8) `const google::protobuf::Descriptor *` | extension_scope_
104 | (8) `const google::protobuf::Descriptor *` | message_type_
112 | (8) `const google::protobuf::EnumDescriptor *` | enum_type_
120 | (8) `const google::protobuf::FieldOptions *` | options_
128 | (8) `const std::string *` | type_name_
136 | (8) `const std::string *` | default_value_enum_name_
144 | (8) `google::protobuf::FieldDescriptor::$8BD136CD6D5A82A6D3B7D3BD04E134E0` | _anon_0


### `google::protobuf::FieldDescriptor::$8BD136CD6D5A82A6D3B7D3BD04E134E0`
Offset | Type | Name
-|-|-|-
0 | (4) `google::protobuf::int32` | default_value_int32_
1 | (8) `google::protobuf::int64` | default_value_int64_
2 | (4) `google::protobuf::uint32` | default_value_uint32_
3 | (8) `google::protobuf::uint64` | default_value_uint64_
4 | (4) `float` | default_value_float_
5 | (8) `double` | default_value_double_
6 | (1) `bool` | default_value_bool_
7 | (8) `const google::protobuf::EnumValueDescriptor *` | default_value_enum_
8 | (8) `const std::string *` | default_value_string_


### `google::protobuf::UnknownField`
Offset | Type | Name
-|-|-|-
0 | (4) `google::protobuf::uint32` | number_
4 | (4) `google::protobuf::uint32` | type_
8 | (8) `google::protobuf::UnknownField::$C8C49B7DCE1DF5248C6FC4AAAED29219` | data_


### `google::protobuf::UnknownField::$C8C49B7DCE1DF5248C6FC4AAAED29219`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::uint64` | varint_
1 | (4) `google::protobuf::uint32` | fixed32_
2 | (8) `google::protobuf::uint64` | fixed64_
3 | (8) `google::protobuf::UnknownField::LengthDelimited` | length_delimited_
4 | (8) `google::protobuf::UnknownFieldSet *` | group_


### `google::protobuf::UnknownField::LengthDelimited`
Offset | Type | Name
-|-|-|-
0 | (8) `std::string *` | string_value_


### `grpc_slice_buffer`
Offset | Type | Name
-|-|-|-
0 | (8) `grpc_slice_0 *` | base_slices
8 | (8) `grpc_slice_0 *` | slices
16 | (8) `size_t` | count
24 | (8) `size_t` | capacity
32 | (8) `size_t` | length
40 | (256) `grpc_slice_0[8]` | inlined


### `google::protobuf::internal::WireFormatLite`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `google::protobuf::internal::ExtensionSet`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::Arena *` | arena_
8 | (2) `google::protobuf::uint16` | flat_capacity_
10 | (2) `google::protobuf::uint16` | flat_size_
16 | (8) `google::protobuf::internal::ExtensionSet::AllocatedData` | map_


### `google::protobuf::internal::ExtensionSet::AllocatedData`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::internal::ExtensionSet::KeyValue *` | flat
1 | (8) `google::protobuf::internal::ExtensionSet::LargeMap *` | large


### `google::protobuf::DescriptorPool`
Offset | Type | Name
-|-|-|-
0 | (8) `google::protobuf::internal::Mutex *` | mutex_
8 | (8) `google::protobuf::DescriptorDatabase *` | fallback_database_
16 | (8) `google::protobuf::DescriptorPool::ErrorCollector *` | default_error_collector_
24 | (8) `const google::protobuf::DescriptorPool *` | underlay_
32 | (8) `std::unique_ptr<google::protobuf::DescriptorPool::Tables>` | tables_
40 | (1) `bool` | enforce_dependencies_
41 | (1) `bool` | lazily_build_dependencies_
42 | (1) `bool` | allow_unknown_
43 | (1) `bool` | enforce_weak_
44 | (1) `bool` | disallow_enforce_utf8_
48 | (48) `std::set<std::string>` | unused_import_track_files_


### `GameRulesChangedPacket`
```
struct __cppobj GameRulesChangedPacket : Packet
{
  GameRulesChangedPacketData mRuleData;
};

```

### `glm::highp_vec3`
```
typedef glm::tvec3<float,glm::packed_highp> glm::highp_vec3;

```

### `glm::highp_vec2`
```
typedef glm::tvec2<float,glm::packed_highp> glm::highp_vec2;

```

### `glm::ivec3`
```
typedef glm::highp_ivec3 glm::ivec3;

```

### `glm::highp_ivec3`
```
typedef glm::tvec3<int,glm::packed_highp> glm::highp_ivec3;

```

### `glm::tvec3<int,glm::packed_highp>`
```
struct glm::tvec3<int,glm::packed_highp>
{
  glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB _anon_0;
};

```

### `glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$658387DF36738DCF5BFC2937BA4E0BEF`
```
struct glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$658387DF36738DCF5BFC2937BA4E0BEF
{
  int x;
  int y;
  int z;
};

```

### `glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$38D542917534AA75D6CF6098F232A747`
```
struct glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$38D542917534AA75D6CF6098F232A747
{
  int r;
  int g;
  int b;
};

```

### `glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$DF61BFD7E18A16B498B9242D9858231B`
```
struct glm::tvec3<int,glm::packed_highp>::$D5E519F64C4DF986CFB1269BA1E778FB::$DF61BFD7E18A16B498B9242D9858231B
{
  int s;
  int t;
  int p;
};

```

### `GameModuleServer`
```
struct GameModuleServer
{
  int (**_vptr$GameModuleServer)(void);
};

```

### `GetEduServerInfoCommand`
```
struct __cppobj GetEduServerInfoCommand : Command
{
};

```

### `google::protobuf::internal::ArenaImpl::SerialArena`
```
struct google::protobuf::internal::ArenaImpl::SerialArena
{
  google::protobuf::internal::ArenaImpl *arena_;
  void *owner_;
  google::protobuf::internal::ArenaImpl::Block *head_;
  google::protobuf::internal::ArenaImpl::CleanupChunk *cleanup_;
  google::protobuf::internal::ArenaImpl::SerialArena *next_;
  char *ptr_;
  char *limit_;
  google::protobuf::internal::ArenaImpl::CleanupNode *cleanup_ptr_;
  google::protobuf::internal::ArenaImpl::CleanupNode *cleanup_limit_;
};

```

### `google::protobuf::internal::ArenaImpl`
```
struct google::protobuf::internal::ArenaImpl
{
  std::atomic<google::protobuf::internal::ArenaImpl::SerialArena *> threads_;
  std::atomic<google::protobuf::internal::ArenaImpl::SerialArena *> hint_;
  std::atomic<unsigned long> space_allocated_;
  google::protobuf::internal::ArenaImpl::Block *initial_block_;
  google::protobuf::int64 lifecycle_id_;
  google::protobuf::internal::ArenaImpl::Options options_;
};

```

### `google::protobuf::internal::ArenaImpl::Block`
```
struct google::protobuf::internal::ArenaImpl::Block
{
  google::protobuf::internal::ArenaImpl::Block *next_;
  size_t pos_;
  size_t size_;
};

```

### `google::protobuf::internal::ArenaImpl::Options`
```
struct google::protobuf::internal::ArenaImpl::Options
{
  size_t start_block_size;
  size_t max_block_size;
  char *initial_block;
  size_t initial_block_size;
  void *(*block_alloc)(size_t);
  void (*block_dealloc)(void *, size_t);
};

```

### `google::protobuf::internal::ArenaImpl::CleanupChunk`
```
struct google::protobuf::internal::ArenaImpl::CleanupChunk
{
  size_t size;
  google::protobuf::internal::ArenaImpl::CleanupChunk *next;
  google::protobuf::internal::ArenaImpl::CleanupNode nodes[1];
};

```

### `google::protobuf::internal::ArenaImpl::CleanupNode`
```
struct google::protobuf::internal::ArenaImpl::CleanupNode
{
  void *elem;
  void (*cleanup)(void *);
};

```

### `grpc_experimental_completion_queue_functor_0`
```
typedef grpc_experimental_completion_queue_functor grpc_experimental_completion_queue_functor_0;

```

### `grpc_experimental_completion_queue_functor`
```
struct grpc_experimental_completion_queue_functor
{
  void (*functor_run)(grpc_experimental_completion_queue_functor *, int);
  int internal_success;
  grpc_experimental_completion_queue_functor *internal_next;
};

```

### `grpc_metadata_array`
```
struct grpc_metadata_array
{
  size_t count;
  size_t capacity;
  grpc_metadata_0 *metadata;
};

```

### `grpc_metadata_0`
```
typedef grpc_metadata grpc_metadata_0;

```

### `grpc_metadata`
```
struct grpc_metadata
{
  grpc_slice_0 key;
  grpc_slice_0 value;
  uint32_t flags;
  grpc_metadata::$DBD30B538C125DB2441881D85AF48C64 internal_data;
};

```

### `grpc_metadata::$DBD30B538C125DB2441881D85AF48C64`
```
struct grpc_metadata::$DBD30B538C125DB2441881D85AF48C64
{
  void *obfuscated[4];
};

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>`
```
struct google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>
{
  __int8 gap0[1];
};

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>::Type`
```
typedef com::mojang::clacks::protocol::LevelFileAndSize google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>::Type;

```

### `google::protobuf::internal::ArenaImpl::ThreadCache`
```
struct google::protobuf::internal::ArenaImpl::ThreadCache
{
  google::protobuf::int64 last_lifecycle_id_seen;
  google::protobuf::internal::ArenaImpl::SerialArena *last_serial_arena;
};

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>`
```
struct google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>
{
  __int8 gap0[1];
};

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>::Type`
```
typedef com::mojang::clacks::protocol::PlayerInfo google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>::Type;

```

### `google::protobuf::internal::Mutex`
```
typedef google::protobuf::internal::WrappedMutex google::protobuf::internal::Mutex;

```

### `google::protobuf::internal::ReaderMutexLock`
```
typedef google::protobuf::internal::MutexLock google::protobuf::internal::ReaderMutexLock;

```

### `google::protobuf::internal::WriterMutexLock`
```
typedef google::protobuf::internal::MutexLock google::protobuf::internal::WriterMutexLock;

```

### `google::protobuf::internal::TaggedPtr<std::string >`
```
struct google::protobuf::internal::TaggedPtr<std::string >
{
  uintptr_t ptr_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<std::string >`
```
struct google::protobuf::internal::ExplicitlyConstructed<std::string >
{
  google::protobuf::internal::ExplicitlyConstructed<std::string >::AlignedUnion union_;
};

```

### `google::protobuf::Arena`
```
struct google::protobuf::Arena
{
  google::protobuf::internal::ArenaImpl impl_;
  void (*on_arena_allocation_)(const std::type_info *, google::protobuf::uint64, void *);
  void (*on_arena_reset_)(google::protobuf::Arena *, void *, google::protobuf::uint64);
  void (*on_arena_destruction_)(google::protobuf::Arena *, void *, google::protobuf::uint64);
  void *hooks_cookie_;
};

```

### `google::protobuf::internal::RepeatedPtrFieldBase::Rep`
```
struct google::protobuf::internal::RepeatedPtrFieldBase::Rep
{
  int allocated_size;
  void *elements[1];
};

```

### `google::protobuf::ArenaOptions`
```
struct google::protobuf::ArenaOptions
{
  size_t start_block_size;
  size_t max_block_size;
  char *initial_block;
  size_t initial_block_size;
  void *(*block_alloc)(size_t);
  void (*block_dealloc)(void *, size_t);
  void *(*on_arena_init)(google::protobuf::Arena *);
  void (*on_arena_reset)(google::protobuf::Arena *, void *, google::protobuf::uint64);
  void (*on_arena_destruction)(google::protobuf::Arena *, void *, google::protobuf::uint64);
  void (*on_arena_allocation)(const std::type_info *, google::protobuf::uint64, void *);
};

```

### `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::LevelFileAndSize>::TypeHandler`
```
struct __cppobj google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::LevelFileAndSize>::TypeHandler : google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>
{
};

```

### `google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::PlayerInfo>::TypeHandler`
```
struct __cppobj google::protobuf::RepeatedPtrField<com::mojang::clacks::protocol::PlayerInfo>::TypeHandler : google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>
{
};

```

### `grpc_byte_buffer_0`
```
typedef grpc_byte_buffer grpc_byte_buffer_0;

```

### `grpc_byte_buffer`
```
struct grpc_byte_buffer
{
  void *reserved;
  grpc_byte_buffer_type type;
  grpc_byte_buffer::grpc_byte_buffer_data data;
};

```

### `grpc_byte_buffer::grpc_byte_buffer_data::$34088C6F4DED15655F247FDBE876D1D9`
```
struct grpc_byte_buffer::grpc_byte_buffer_data::$34088C6F4DED15655F247FDBE876D1D9
{
  void *reserved[8];
};

```

### `grpc_byte_buffer::grpc_byte_buffer_data::grpc_compressed_buffer`
```
struct grpc_byte_buffer::grpc_byte_buffer_data::grpc_compressed_buffer
{
  grpc_compression_algorithm compression;
  grpc_slice_buffer_0 slice_buffer;
};

```

### `grpc_slice_buffer_0`
```
typedef grpc_slice_buffer grpc_slice_buffer_0;

```

### `grpc_byte_buffer_reader`
```
struct __attribute__((aligned(8))) grpc_byte_buffer_reader
{
  grpc_byte_buffer *buffer_in;
  grpc_byte_buffer *buffer_out;
  grpc_byte_buffer_reader::grpc_byte_buffer_reader_current current;
};

```

### `grpc_completion_queue_attributes`
```
struct grpc_completion_queue_attributes
{
  int version;
  grpc_cq_completion_type cq_completion_type;
  grpc_cq_polling_type cq_polling_type;
  grpc_experimental_completion_queue_functor_0 *cq_shutdown_cb;
};

```

### `grpc_op`
```
struct grpc_op
{
  grpc_op_type op;
  uint32_t flags;
  void *reserved;
  grpc_op::grpc_op_data data;
};

```

### `grpc_event`
```
struct grpc_event
{
  grpc_completion_type_0 type;
  int success;
  void *tag;
};

```

### `GoalSelectorSystem`
```
struct __cppobj GoalSelectorSystem : ITickingSystem
{
};

```

### `GrowCropSystem`
```
struct __cppobj GrowCropSystem : ITickingSystem
{
};

```

### `GroundBushFeature`
```
struct __cppobj __attribute__((aligned(8))) GroundBushFeature : TreeFeature
{
};

```

### `GridArea<std::shared_ptr<LevelChunk> >`
```
struct __attribute__((aligned(4))) GridArea<std::shared_ptr<LevelChunk> >
{
  GridArea<std::shared_ptr<LevelChunk> >::DestroyCallback destroy;
  GridArea<std::shared_ptr<LevelChunk> >::GenerateCallback generate;
  GridArea<std::shared_ptr<LevelChunk> >::AddCallback add;
  Bounds mBounds;
  GridArea<std::shared_ptr<LevelChunk> >::ChunkList mChunks;
  GridArea<std::shared_ptr<LevelChunk> >::ChunkList mNewChunks;
  bool mCircle;
  Height mMinHeight;
  Height mMaxHeight;
};

```

### `GridArea<std::shared_ptr<LevelChunk> >::ChunkList`
```
typedef std::vector<std::shared_ptr<LevelChunk>> GridArea<std::shared_ptr<LevelChunk> >::ChunkList;

```

### `GridArea<std::shared_ptr<LevelChunk> >::Iterator`
```
typedef std::vector<std::shared_ptr<LevelChunk>>::iterator GridArea<std::shared_ptr<LevelChunk> >::Iterator;

```

### `GridArea<std::shared_ptr<LevelChunk> >::ConstIterator`
```
typedef std::vector<std::shared_ptr<LevelChunk>>::const_iterator GridArea<std::shared_ptr<LevelChunk> >::ConstIterator;

```

### `glm::detail::compute_length2<tvec2,float,glm::packed_highp,false>`
```
struct glm::detail::compute_length2<tvec2,float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_dot<tvec2,float,glm::packed_highp,false>`
```
struct glm::detail::compute_dot<tvec2,float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `GrowsCropDefinition`
```
struct GrowsCropDefinition
{
  int mCharges;
  float mChance;
};

```

### `GameCallbacks`
```
struct GameCallbacks
{
  int (**_vptr$GameCallbacks)(void);
};

```

### `GlobalActorList`
```
typedef SmallSet<Actor *> GlobalActorList;

```

### `GroundOffsetDescription`
```
struct __cppobj __attribute__((aligned(8))) GroundOffsetDescription : PropertyDescription
{
  float mValue;
};

```

### `GenericMoveControlDescription`
```
struct __cppobj __attribute__((aligned(8))) GenericMoveControlDescription : MoveControlDescription
{
};

```

### `GlideMoveControlDescription`
```
struct __cppobj __attribute__((aligned(8))) GlideMoveControlDescription : MoveControlDescription:96
{
  float mStartSpeed;
  float mSpeedWhenTurning;
};

```

### `GrindstoneContainerManagerModel`
```
struct __cppobj __attribute__((aligned(8))) GrindstoneContainerManagerModel : ContainerManagerModel
{
  BlockPos mBlockPos;
};

```

### `glm::detail::storage<float,16,false>::type`
```
struct glm::detail::storage<float,16,false>::type
{
  glm::detail::uint8 data[16];
};

```

### `glm::detail::storage<float,16,false>`
```
struct glm::detail::storage<float,16,false>
{
  __int8 gap0[1];
};

```

### `glm::highp_mat3x3`
```
typedef glm::tmat3x3<float,glm::packed_highp> glm::highp_mat3x3;

```

### `GameArgumentCommandOrigin`
```
struct __cppobj GameArgumentCommandOrigin : CommandOrigin
{
  std::string mRequestId;
};

```

### `glm::highp_vec4`
```
typedef glm::tvec4<float,glm::packed_highp> glm::highp_vec4;

```

### `GameSession`
```
struct __attribute__((aligned(8))) GameSession
{
  NetworkHandler *mNetworkHandler;
  std::unique_ptr<Level> mLevel;
  std::unique_ptr<ServerNetworkHandler> mServerNetworkHandler;
  std::unique_ptr<NetEventCallback> mLegacyClientNetworkHandler;
  std::unique_ptr<NetEventCallback> mClientNetworkHandler;
  LoopbackPacketSender *mLoopbackPacketSender;
  SubClientId mClientSubId;
};

```

### `GeneticsDefinition`
```
struct GeneticsDefinition
{
  float mMutationRate;
  std::vector<GeneDefinition> mGeneDefinitions;
};

```

### `glm::highp_mat4x4`
```
typedef glm::tmat4x4<float,glm::packed_highp> glm::highp_mat4x4;

```

### `glm::detail::compute_vec4_add<float,glm::packed_highp,false>`
```
struct glm::detail::compute_vec4_add<float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_vec4_mul<float,glm::packed_highp,false>`
```
struct glm::detail::compute_vec4_mul<float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_normalize<float,glm::packed_highp,tvec3,false>`
```
struct glm::detail::compute_normalize<float,glm::packed_highp,tvec3,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_dot<tvec3,float,glm::packed_highp,false>`
```
struct glm::detail::compute_dot<tvec3,float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::quat`
```
typedef glm::highp_quat glm::quat;

```

### `glm::highp_quat`
```
typedef glm::tquat<float,glm::packed_highp> glm::highp_quat;

```

### `Ghast`
```
struct __cppobj Ghast : Mob
{
};

```

### `Guardian`
```
struct __cppobj Guardian : Monster
{
  std::string ATTACK_SOUND;
  float ELDER_SIZE_SCALE;
  RandomStrollGoal *randomStrollGoal;
  int FLAG_MOVING;
  int FLAG_ELDER;
  Vec3 startPos;
  float clientSideTailAnimation;
  float clientSideTailAnimationO;
  float clientSideTailAnimationSpeed;
  float clientSideSpikesAnimation;
  float clientSideSpikesAnimationO;
  Mob *clientSideCachedAttackTarget;
  int clientSideAttackTime;
  bool clientSideTouchedGround;
  ActorUniqueID mAttackTargetId;
  bool mElderGhost;
  LoopingSoundHandle mLaserLoop;
  ActorUniqueID mEyeTarget;
};

```

### `GenericMoveControl`
```
struct __cppobj GenericMoveControl : MoveControl
{
};

```

### `GlideMoveControl`
```
struct __cppobj __attribute__((aligned(8))) GlideMoveControl : MoveControl
{
  float mSpeed;
  float mStartSpeed;
  float mSpeedWhenTurning;
};

```

### `GenericPathNavigation`
```
struct __cppobj GenericPathNavigation : PathNavigation
{
};

```

### `glm::detail::compute_abs<float,true>`
```
struct glm::detail::compute_abs<float,true>
{
  __int8 gap0[1];
};

```

### `GoalDefinition_0`
```
struct GoalDefinition_0
{
  std::string mName;
  int mPriority;
  int mRequiredControlFlags;
  int mScanInterval;
  float mTargetSearchHeight;
  int mPersistTargetTicks;
  float mWithinDefault;
  float mMaxDist;
  float mMaxFlee;
  float mWalkSpeedModifier;
  float mSprintSpeedModifier;
  float mProbabilityPerStrength;
  float mSneakSpeedModifier;
  ActorType mEntityType;
  std::vector<MobDescriptor> mMobDescriptions;
  bool mIgnoreVisibility;
  float mStartDistance;
  float mStopDistance;
  int mRoarDuration;
  int mRoarAttackTime;
  int mRoarDamage;
  int mRoarStrength;
  int mRoarRange;
  ActorFilterGroup mKnockbackFilter;
  ActorFilterGroup mDamageFilter;
  DefinitionTrigger mOnRoarEnd;
  float mYd;
  float mStalkSpeed;
  float mMaxStalkDist;
  float mLeapHeight;
  float mLeapDistance;
  float mPounceMaxDistance;
  float mStrikeDistance;
  float mStuckTime;
  ActorFilterGroup mBlockFilter;
  float mLookDistance;
  int mAngleOfViewX;
  int mAngleOfViewY;
  float mProbability;
  ActorFilterGroup mTargetFilter;
  int mMinLookTime;
  int mMaxLookTime;
  int mMinLookAroundTime;
  int mMaxLookAroundTime;
  float mMinimumRadius;
  bool mBroadcast;
  float mBroadcastRange;
  DefinitionTrigger mWithinRadiusEvent;
  DefinitionTrigger mHurtByTargetEvent;
  float mPercentChance;
  ActorCategory mAttackTypes;
  int mRandomStopInterval;
  float mReachMultiplier;
  float mMeleeFOV;
  bool mAttackOnce;
  int mRandomSoundInterval;
  bool mRequireCompletePath;
  DefinitionTrigger mOnAttack;
  float mAttackDuration;
  float mHitDelay;
  LevelSoundEvent mDelayedAttackSound;
  DefinitionTrigger mOnEat;
  int mDelayBeforeEating;
  int mWaitTime;
  float mExploreDist;
  std::vector<DefinitionTrigger> mOnHomeTriggers;
  std::vector<DefinitionTrigger> mOnFailedTriggers;
  DefinitionTrigger mOnLayEvent;
  DefinitionTrigger mOnWorkArrivalEvent;
  float mTargetDist;
  float mSpeedModifier;
  int mSearchRange;
  int mSearchHeight;
  int mSearchCount;
  float mGoalRadius;
  GoalDefinition::$957942B4FBBCA72D92900834D61C4C9E mMoveToBlockGoalData;
  float mWithin;
  bool mIgnoreMobDamage;
  bool mForceUse;
  float mLookAhead;
  float mCenteredGap;
  float mMoveSpeed;
  int mEntityCount;
  int mXZDist;
  int mYDist;
  float mYOffset;
  int mInterval;
  float mCooldown;
  __int8 mCanLandOnTrees : 1;
  float mRangedFOV;
  int mAttackIntervalMin;
  int mAttackIntervalMax;
  float mAttackRadius;
  float mChargeChargedTrigger;
  float mChargeShootTrigger;
  int mBurstShots;
  float mBurstInterval;
  __int8 mMustSee : 1;
  __int8 mMustReach : 1;
  __int8 mCloseDoorAfter : 1;
  __int8 mCanGetScared : 1;
  __int8 mOnlyAtNight : 1;
  __int8 mMustBeOnGround : 1;
  __int8 mTrackTarget : 1;
  __int8 mAlertSameType : 1;
  __int8 mReselectTargets : 1;
  bool mHurtOwner;
  int mMustSeeForgetTicks;
  std::vector<ItemDescriptor> mItemList;
  bool mCanTemptVertically;
  int mMaxToEat;
  int mEatDelay;
  int mFullDelay;
  int mInitialEatDelay;
  std::set<const Block *> mBlockList;
  float mFloatHeightOffset;
  bool mRandomReselect;
  FloatRange mFloatDuration;
  IntRange mHoverHeight;
  float mDuration;
  FloatRange mRadiusRange;
  int mRadiusChangeChance;
  FloatRange mAboveTargetRange;
  FloatRange mHeightOffsetRange;
  int mHeightChangeChance;
  FloatRange mDelayRange;
  std::vector<SummonSpellData> mSummonSpellData;
  POIType mPOIType;
  int mGoalCooldown;
  int mActiveTime;
  int mRandomSoundIntervalMin;
  int mRandomSoundIntervalMax;
  bool mCanWorkInRain;
  int mWorkInRainTolerance;
  float mFollowDistance;
  float mBlockDistance;
  std::vector<SendEventData> mSendEventData;
  int mStartDelay;
  int mMaxFailedAttempts;
  bool mAvoidWater;
  bool mPreferWater;
  bool mTargetNeeded;
  float mMountDistance;
  std::vector<DrinkPotionData> mDrinkPotionData;
  float mDrinkSpeedModifier;
  float mDropItemChance;
  DefinitionTrigger mOnDropAttemptEvent;
  float mOfferingDistance;
  std::string mLootTable;
  FloatRange mTimeOfDayRange;
  float mSnackingCooldown;
  float mSnackingCooldownMin;
  float mStopSnackingChance;
  float mStopChance;
  float mStartChance;
  float mSittingTimeMin;
  float mSittingCooldown;
  std::string mSound;
  std::string mPrepareSound;
  float mPrepareTime;
  std::string mAggroSound;
  DefinitionTrigger mOnDefendEvent;
  float mSleepYOffset;
  float mSleepColliderHeight;
  float mSleepColliderWidth;
  float mCooldownMax;
  float mCooldownMin;
  float mDetectMobDistance;
  float mDetectMobHeight;
  ActorFilterGroup mCanNapFilters;
  ActorFilterGroup mWakeMobExceptionFilters;
  float mInterestTime;
  float mRemoveItemTime;
  float mCarriedItemSwitchTime;
  float mInterestCooldown;
  float mCooldownTimeoutTime;
  ActorDefinitionIdentifier mDesiredMingleType;
  float mMingleDistance;
  int mMinLookCount;
  int mMaxLookCount;
  FloatRange mSoundInterval;
  FloatRange mJumpInterval;
  DefinitionTrigger mOnCelebrationEndEvent;
  std::string mCelebrationSound;
};

```

### `GoalDefinition::$957942B4FBBCA72D92900834D61C4C9E`
```
struct __attribute__((aligned(8))) GoalDefinition::$957942B4FBBCA72D92900834D61C4C9E
{
  float speedModifier;
  int searchRange;
  int searchHeight;
  float goalRadius;
  int tickInterval;
  float stayDuration;
  std::vector<DefinitionTrigger> onReachTriggers;
  std::vector<DefinitionTrigger> onStayCompletedTriggers;
  std::vector<ItemDescriptor> targetDescriptors;
  Vec3 targetPositionOffset;
  float chanceToStart;
  TargetSelectionMethod_0 targetSelectionMethod;
};

```

### `GuardianAttackGoal`
```
struct __cppobj __attribute__((aligned(8))) GuardianAttackGoal : Goal
{
  Guardian *mGuardian;
  int attackTime;
};

```

### `glm::tmat4x4<float,glm::packed_highp>::row_type`
```
typedef glm::tvec4<float,glm::packed_highp> glm::tmat4x4<float,glm::packed_highp>::row_type;

```

### `glm::detail::compute_transpose<tmat4x4,float,glm::packed_highp,false>`
```
struct glm::detail::compute_transpose<tmat4x4,float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_vec4_sub<float,glm::packed_highp,false>`
```
struct glm::detail::compute_vec4_sub<float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::functor1<float,float,glm::packed_highp,tvec3>`
```
struct glm::detail::functor1<float,float,glm::packed_highp,tvec3>
{
  __int8 gap0[1];
};

```

### `GrantXPSubcomponent`
```
struct __cppobj GrantXPSubcomponent : OnHitSubcomponent
{
  int mMinXPGranted;
  int mMaxXPGranted;
};

```

### `GameMode:1312`
```
struct __attribute__((packed)) __attribute__((aligned(4))) GameMode:1312
{
  int (**_vptr$GameMode)(void);
  Player *mPlayer;
  BlockPos mDestroyBlockPos;
  float mOldDestroyProgress;
  float mDestroyProgress;
  _BYTE gap24[4];
  double mLastDestroyTime;
  float mDistanceTravelled;
  Vec3 mPlayerLastPosition;
  BlockPos mLastBuiltBlockPosition;
  bool mLastBuildBlockWasInteractive;
  bool mLastBuildBlockWasSnappable;
  __attribute__((aligned(4))) float mMinPlayerSpeed;
  _BYTE gap54[4];
  std::chrono::_V2::steady_clock::time_point mLastBuildTime;
  std::chrono::_V2::steady_clock::time_point mNoDestroyUntil;
  std::chrono::_V2::steady_clock::time_point mNoDestroySoundUntil;
  std::chrono::milliseconds creativeDestructionTickDelay;
  std::chrono::milliseconds buildingTickDelay;
  std::chrono::milliseconds destroySoundDelay;
  bool mHasBuildDirection;
  bool mHasLastBuiltPosition;
  FacingID mContinueFacing;
  __attribute__((aligned(2))) BlockPos mBuildDirection;
  BlockPos mNextBuildPos;
};

```

### `GlowStickItem`
```
struct __cppobj GlowStickItem : ChemistryStickItem
{
  std::unique_ptr<BlockItem> mBlockItem;
};

```

### `glm::detail::compute_log2<float,glm::packed_highp,tvec1,true,false>`
```
struct glm::detail::compute_log2<float,glm::packed_highp,tvec1,true,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::functor1<float,float,glm::packed_highp,tvec1>`
```
struct glm::detail::functor1<float,float,glm::packed_highp,tvec1>
{
  __int8 gap0[1];
};

```

### `GrassBlock`
```
struct __cppobj GrassBlock : BlockLegacy
{
  std::vector<Color> mSideColors;
};

```

### `GravelBlock`
```
struct __cppobj GravelBlock : HeavyBlock
{
};

```

### `GlassBlock`
```
struct __cppobj __attribute__((aligned(8))) GlassBlock : BlockLegacy
{
  bool mDoesDrops;
  bool mCanBeUsedInCommands;
};

```

### `GrassPathBlock`
```
struct __cppobj GrassPathBlock : BlockLegacy
{
};

```

### `GlazedTerracottaBlock`
```
struct __cppobj GlazedTerracottaBlock : FaceDirectionalBlock
{
};

```

### `GrindstoneBlock`
```
struct __cppobj GrindstoneBlock : BlockLegacy
{
};

```

### `GroundedConstraint`
```
struct __cppobj GroundedConstraint : IStructureConstraint
{
  std::vector<BlockPos> mFoundationOffsets;
};

```

### `google_breakpad::CrashGenerationClient`
```
struct google_breakpad::CrashGenerationClient
{
  int (**_vptr$CrashGenerationClient)(void);
};

```

### `google_breakpad::MinidumpDescriptor::MicrodumpOnConsole`
```
struct google_breakpad::MinidumpDescriptor::MicrodumpOnConsole
{
  __int8 gap0[1];
};

```

### `GiveableDefinition`
```
struct GiveableDefinition
{
  std::vector<GiveableTrigger> mTriggers;
};

```

### `GetChunkDataCommand`
```
struct __cppobj GetChunkDataCommand : Command
{
  DimensionType mDimension;
  int mChunkX;
  int mChunkZ;
  int mHeight;
};

```

### `GetChunksCommand`
```
struct __cppobj __attribute__((aligned(8))) GetChunksCommand : Command
{
  DimensionType mDimension;
};

```

### `GetSpawnPointCommand`
```
struct __cppobj GetSpawnPointCommand : Command
{
  PlayerSelector mTargets;
};

```

### `GlobalPauseCommand`
```
struct __cppobj GlobalPauseCommand : ServerCommand:240
{
  bool mPause;
  bool mPauseSet;
};

```

### `GameModeCommand`
```
struct __cppobj GameModeCommand : Command
{
  PlayerSelector mPlayers;
  GameType mGameMode;
  int mGameModeNumber;
};

```

### `GameRuleCommand`
```
struct __cppobj __attribute__((aligned(8))) GameRuleCommand : Command
{
  std::string mGameRule;
  float mFloatValue;
  int mIntValue;
  bool mBoolValue;
  bool mBoolValueSet;
  bool mIntValueSet;
  bool mFloatValueSet;
};

```

### `GetTopSolidBlockCommand`
```
struct __cppobj GetTopSolidBlockCommand : Command
{
  CommandPosition mPosition;
};

```

### `GiveCommand`
```
struct __cppobj __attribute__((aligned(8))) GiveCommand : Command
{
  PlayerSelector mTargets;
  CommandItem mItem;
  int mCount;
  int mData;
  Json::Value mComponents;
  bool mHaveComponents;
};

```

### `GetInteractionPositionForBlockDefinition`
```
struct __cppobj GetInteractionPositionForBlockDefinition : BehaviorDefinition
{
  BlockPos mTargetBlockPos;
  std::string mTargetBlockPosId;
  BlockPos mAnchorBlockPos;
  std::string mAnchorBlockPosId;
  std::string mFacingString;
  std::string mFacingStringId;
  int mMaxSearchDistance;
  std::string mMaxSearchDistanceId;
};

```

### `GetInteractionPositionForBlockNode`
```
struct __cppobj __attribute__((aligned(8))) GetInteractionPositionForBlockNode : BehaviorNode:480
{
  BlockPos mTargetBlockPos;
  BlockPos mAnchorBlockPos;
  Facing::Name mFacing;
  int mMaxSearchDistance;
};

```

### `GrindstoneContainerController`
```
struct __cppobj GrindstoneContainerController : ContainerController
{
};

```

### `glm::detail::compute_cross<float,glm::packed_highp,false>`
```
struct glm::detail::compute_cross<float,glm::packed_highp,false>
{
  __int8 gap0[1];
};

```

### `glm::detail::compute_mix_scalar<float,float,glm::packed_highp,tvec3,false>`
```
struct glm::detail::compute_mix_scalar<float,float,glm::packed_highp,tvec3,false>
{
  __int8 gap0[1];
};

```

### `google_breakpad::HTTPUpload`
```
struct google_breakpad::HTTPUpload
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageAllocator::PageHeader`
```
struct google_breakpad::PageAllocator::PageHeader
{
  google_breakpad::PageAllocator::PageHeader *next;
  size_t num_pages;
};

```

### `google_breakpad::`anonymous namespace'::CrashGenerationClientImpl`
```
struct __cppobj __attribute__((aligned(8))) google_breakpad::`anonymous namespace'::CrashGenerationClientImpl : google_breakpad::CrashGenerationClient
{
  int server_fd_;
};

```

### `google_breakpad::PageStdAllocator<MDMemoryDescriptor>::rebind<MDMemoryDescriptor>::other`
```
typedef google_breakpad::PageStdAllocator<MDMemoryDescriptor> google_breakpad::PageStdAllocator<MDMemoryDescriptor>::rebind<MDMemoryDescriptor>::other;

```

### `google_breakpad::MDTypeHelper<8>::MDRawLinkMap`
```
typedef MDRawLinkMap64 google_breakpad::MDTypeHelper<8>::MDRawLinkMap;

```

### `google_breakpad::PageStdAllocator<MDMemoryDescriptor>::rebind<MDMemoryDescriptor>`
```
struct google_breakpad::PageStdAllocator<MDMemoryDescriptor>::rebind<MDMemoryDescriptor>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<unsigned char>::rebind<unsigned char>`
```
struct google_breakpad::PageStdAllocator<unsigned char>::rebind<unsigned char>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<unsigned char>::rebind<unsigned char>::other`
```
typedef google_breakpad::PageStdAllocator<unsigned char> google_breakpad::PageStdAllocator<unsigned char>::rebind<unsigned char>::other;

```

### `google_breakpad::PageStdAllocator<char>::rebind<char>`
```
struct google_breakpad::PageStdAllocator<char>::rebind<char>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<char>::rebind<char>::other`
```
typedef google_breakpad::PageStdAllocator<char> google_breakpad::PageStdAllocator<char>::rebind<char>::other;

```

### `google_breakpad::CpuSet`
```
struct google_breakpad::CpuSet
{
  google_breakpad::CpuSet::MaskWordType mask_[32];
};

```

### `google_breakpad::LineReader`
```
struct google_breakpad::LineReader
{
  const int fd_;
  bool hit_eof_;
  unsigned int buf_used_;
  char buf_[512];
};

```

### `google_breakpad::ProcCpuInfoReader`
```
struct google_breakpad::ProcCpuInfoReader
{
  google_breakpad::LineReader line_reader_;
  int pop_count_;
  const char *value_;
  size_t value_len_;
};

```

### `google_breakpad::UContextReader`
```
struct google_breakpad::UContextReader
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawHeader>`
```
struct google_breakpad::minidump_size<MDRawHeader>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawDirectory>`
```
struct google_breakpad::minidump_size<MDRawDirectory>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<int>::rebind<int>::other`
```
typedef google_breakpad::PageStdAllocator<int> google_breakpad::PageStdAllocator<int>::rebind<int>::other;

```

### `google_breakpad::PageStdAllocator<int>::rebind<int>`
```
struct google_breakpad::PageStdAllocator<int>::rebind<int>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::rebind<google_breakpad::MappingInfo *>::other`
```
typedef google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *> google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::rebind<google_breakpad::MappingInfo *>::other;

```

### `google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::rebind<google_breakpad::MappingInfo *>`
```
struct google_breakpad::PageStdAllocator<google_breakpad::MappingInfo *>::rebind<google_breakpad::MappingInfo *>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<unsigned int>`
```
struct google_breakpad::minidump_size<unsigned int>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawContextAMD64>`
```
struct google_breakpad::minidump_size<MDRawContextAMD64>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawExceptionStream>`
```
struct google_breakpad::minidump_size<MDRawExceptionStream>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawSystemInfo>`
```
struct google_breakpad::minidump_size<MDRawSystemInfo>
{
  __int8 gap0[1];
};

```

### `google_breakpad::PageStdAllocator<unsigned long>::rebind<unsigned long>::other`
```
typedef google_breakpad::PageStdAllocator<unsigned long> google_breakpad::PageStdAllocator<unsigned long>::rebind<unsigned long>::other;

```

### `google_breakpad::PageStdAllocator<unsigned long>::rebind<unsigned long>`
```
struct google_breakpad::PageStdAllocator<unsigned long>::rebind<unsigned long>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawLinkMap64>`
```
struct google_breakpad::minidump_size<MDRawLinkMap64>
{
  __int8 gap0[1];
};

```

### `google_breakpad::minidump_size<MDRawDebug64>`
```
struct google_breakpad::minidump_size<MDRawDebug64>
{
  __int8 gap0[1];
};

```

### `google_breakpad::MDTypeHelper<8>`
```
struct google_breakpad::MDTypeHelper<8>
{
  __int8 gap0[1];
};

```

### `google_breakpad::DirectoryReader`
```
struct google_breakpad::DirectoryReader
{
  const int fd_;
  bool hit_eof_;
  unsigned int buf_used_;
  uint8_t buf_[536];
};

```

### `google_breakpad::minidump_size<MDString>`
```
struct google_breakpad::minidump_size<MDString>
{
  __int8 gap0[1];
};

```

### `GUIDGenerator`
```
struct GUIDGenerator
{
  __int8 gap0[1];
};

```

### `google_breakpad::ElfClassBuildIDNoteIdentifier<google_breakpad::ElfClass32>::Nhdr`
```
typedef google_breakpad::ElfClass32::Nhdr google_breakpad::ElfClassBuildIDNoteIdentifier<google_breakpad::ElfClass32>::Nhdr;

```

### `google_breakpad::ElfClass32::Nhdr`
```
typedef Elf32_Nhdr google_breakpad::ElfClass32::Nhdr;

```

### `google_breakpad::ElfClass32`
```
struct google_breakpad::ElfClass32
{
  __int8 gap0[1];
};

```

### `google_breakpad::ElfClassBuildIDNoteIdentifier<google_breakpad::ElfClass64>::Nhdr`
```
typedef google_breakpad::ElfClass64::Nhdr google_breakpad::ElfClassBuildIDNoteIdentifier<google_breakpad::ElfClass64>::Nhdr;

```

### `google_breakpad::ElfClass64::Nhdr`
```
typedef Elf64_Nhdr google_breakpad::ElfClass64::Nhdr;

```

### `google_breakpad::ElfClass64`
```
struct google_breakpad::ElfClass64
{
  __int8 gap0[1];
};

```

### `google_breakpad::FileID`
```
struct google_breakpad::FileID
{
  std::string path_;
};

```

### `google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass32>::Ehdr`
```
typedef google_breakpad::ElfClass32::Ehdr google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass32>::Ehdr;

```

### `google_breakpad::ElfClass32::Ehdr`
```
typedef Elf32_Ehdr google_breakpad::ElfClass32::Ehdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass32>::Shdr`
```
typedef google_breakpad::ElfClass32::Shdr google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass32>::Shdr;

```

### `google_breakpad::ElfClass32::Shdr`
```
typedef Elf32_Shdr google_breakpad::ElfClass32::Shdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass64>::Ehdr`
```
typedef google_breakpad::ElfClass64::Ehdr google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass64>::Ehdr;

```

### `google_breakpad::ElfClass64::Ehdr`
```
typedef Elf64_Ehdr google_breakpad::ElfClass64::Ehdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass64>::Shdr`
```
typedef google_breakpad::ElfClass64::Shdr google_breakpad::`anonymous namespace'::FindElfClassSection<google_breakpad::ElfClass64>::Shdr;

```

### `google_breakpad::ElfClass64::Shdr`
```
typedef Elf64_Shdr google_breakpad::ElfClass64::Shdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass32>::Ehdr`
```
typedef google_breakpad::ElfClass32::Ehdr google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass32>::Ehdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass32>::Phdr`
```
typedef google_breakpad::ElfClass32::Phdr google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass32>::Phdr;

```

### `google_breakpad::ElfClass32::Phdr`
```
typedef Elf32_Phdr google_breakpad::ElfClass32::Phdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass64>::Ehdr`
```
typedef google_breakpad::ElfClass64::Ehdr google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass64>::Ehdr;

```

### `google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass64>::Phdr`
```
typedef google_breakpad::ElfClass64::Phdr google_breakpad::`anonymous namespace'::FindElfClassSegment<google_breakpad::ElfClass64>::Phdr;

```

### `google_breakpad::ElfClass64::Phdr`
```
typedef Elf64_Phdr google_breakpad::ElfClass64::Phdr;

```

### `google::protobuf::internal::ExtensionSet::Extension`
```
struct google::protobuf::internal::ExtensionSet::Extension
{
  google::protobuf::internal::ExtensionSet::Extension::$CBE77C1C9F53FBD33D6BF126D08E2EBF _anon_0;
  google::protobuf::internal::FieldType type;
  bool is_repeated;
  __int8 is_cleared : 4;
  __int8 is_lazy : 4;
  bool is_packed;
  int cached_size;
  const google::protobuf::FieldDescriptor *descriptor;
};

```

### `google::protobuf::RepeatedField<int>`
```
struct google::protobuf::RepeatedField<int>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<int>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<int>::Rep`
```
struct __attribute__((aligned(8))) google::protobuf::RepeatedField<int>::Rep
{
  google::protobuf::Arena *arena;
  int elements[1];
};

```

### `google::protobuf::RepeatedField<long>`
```
struct google::protobuf::RepeatedField<long>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<long>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<long>::Rep`
```
struct google::protobuf::RepeatedField<long>::Rep
{
  google::protobuf::Arena *arena;
  __int64 elements[1];
};

```

### `google::protobuf::RepeatedField<unsigned int>`
```
struct google::protobuf::RepeatedField<unsigned int>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<unsigned int>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<unsigned int>::Rep`
```
struct __attribute__((aligned(8))) google::protobuf::RepeatedField<unsigned int>::Rep
{
  google::protobuf::Arena *arena;
  unsigned int elements[1];
};

```

### `google::protobuf::RepeatedField<unsigned long>`
```
struct google::protobuf::RepeatedField<unsigned long>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<unsigned long>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<unsigned long>::Rep`
```
struct google::protobuf::RepeatedField<unsigned long>::Rep
{
  google::protobuf::Arena *arena;
  unsigned __int64 elements[1];
};

```

### `google::protobuf::RepeatedField<float>`
```
struct google::protobuf::RepeatedField<float>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<float>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<float>::Rep`
```
struct __attribute__((aligned(8))) google::protobuf::RepeatedField<float>::Rep
{
  google::protobuf::Arena *arena;
  float elements[1];
};

```

### `google::protobuf::RepeatedField<double>`
```
struct google::protobuf::RepeatedField<double>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<double>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<double>::Rep`
```
struct google::protobuf::RepeatedField<double>::Rep
{
  google::protobuf::Arena *arena;
  double elements[1];
};

```

### `google::protobuf::RepeatedField<bool>`
```
struct google::protobuf::RepeatedField<bool>
{
  int current_size_;
  int total_size_;
  google::protobuf::RepeatedField<bool>::Pointer ptr_;
};

```

### `google::protobuf::RepeatedField<bool>::Rep`
```
struct __attribute__((aligned(8))) google::protobuf::RepeatedField<bool>::Rep
{
  google::protobuf::Arena *arena;
  bool elements[1];
};

```

### `google::protobuf::RepeatedPtrField<std::string >`
```
struct __cppobj google::protobuf::RepeatedPtrField<std::string > : google::protobuf::internal::RepeatedPtrFieldBase
{
};

```

### `google::protobuf::FileDescriptor`
```
struct google::protobuf::FileDescriptor
{
  const std::string *name_;
  const std::string *package_;
  const google::protobuf::DescriptorPool *pool_;
  google::protobuf::GoogleOnceDynamic *dependencies_once_;
  int dependency_count_;
  int public_dependency_count_;
  int weak_dependency_count_;
  int message_type_count_;
  int enum_type_count_;
  int service_count_;
  int extension_count_;
  google::protobuf::FileDescriptor::Syntax syntax_;
  bool is_placeholder_;
  bool finished_building_;
  const google::protobuf::FileDescriptor **dependencies_;
  const std::string **dependencies_names_;
  int *public_dependencies_;
  int *weak_dependencies_;
  google::protobuf::Descriptor *message_types_;
  google::protobuf::EnumDescriptor *enum_types_;
  google::protobuf::ServiceDescriptor *services_;
  google::protobuf::FieldDescriptor *extensions_;
  const google::protobuf::FileOptions *options_;
  const google::protobuf::FileDescriptorTables *tables_;
  const google::protobuf::SourceCodeInfo *source_code_info_;
};

```

### `google::protobuf::GoogleOnceDynamic`
```
struct google::protobuf::GoogleOnceDynamic
{
  google::protobuf::ProtobufOnceType state_;
};

```

### `google::protobuf::ProtobufOnceType`
```
typedef google::protobuf::internal::once_flag google::protobuf::ProtobufOnceType;

```

### `google::protobuf::Descriptor`
```
struct __attribute__((aligned(8))) google::protobuf::Descriptor
{
  const std::string *name_;
  const std::string *full_name_;
  const google::protobuf::FileDescriptor *file_;
  const google::protobuf::Descriptor *containing_type_;
  const google::protobuf::MessageOptions *options_;
  google::protobuf::FieldDescriptor *fields_;
  google::protobuf::OneofDescriptor *oneof_decls_;
  google::protobuf::Descriptor *nested_types_;
  google::protobuf::EnumDescriptor *enum_types_;
  google::protobuf::Descriptor::ExtensionRange *extension_ranges_;
  google::protobuf::FieldDescriptor *extensions_;
  google::protobuf::Descriptor::ReservedRange *reserved_ranges_;
  const std::string **reserved_names_;
  int field_count_;
  int oneof_decl_count_;
  int nested_type_count_;
  int enum_type_count_;
  int extension_range_count_;
  int extension_count_;
  int reserved_range_count_;
  int reserved_name_count_;
  bool is_placeholder_;
  bool is_unqualified_placeholder_;
};

```

### `google::protobuf::OneofDescriptor`
```
struct google::protobuf::OneofDescriptor
{
  const std::string *name_;
  const std::string *full_name_;
  const google::protobuf::Descriptor *containing_type_;
  bool is_extendable_;
  int field_count_;
  const google::protobuf::FieldDescriptor **fields_;
  const google::protobuf::OneofOptions *options_;
};

```

### `google::protobuf::EnumDescriptor`
```
struct google::protobuf::EnumDescriptor
{
  const std::string *name_;
  const std::string *full_name_;
  const google::protobuf::FileDescriptor *file_;
  const google::protobuf::Descriptor *containing_type_;
  const google::protobuf::EnumOptions *options_;
  bool is_placeholder_;
  bool is_unqualified_placeholder_;
  int value_count_;
  google::protobuf::EnumValueDescriptor *values_;
  int reserved_range_count_;
  int reserved_name_count_;
  google::protobuf::EnumDescriptor::ReservedRange *reserved_ranges_;
  const std::string **reserved_names_;
};

```

### `google::protobuf::EnumValueDescriptor`
```
struct google::protobuf::EnumValueDescriptor
{
  const std::string *name_;
  const std::string *full_name_;
  int number_;
  const google::protobuf::EnumDescriptor *type_;
  const google::protobuf::EnumValueOptions *options_;
};

```

### `google::protobuf::EnumDescriptor::ReservedRange`
```
struct google::protobuf::EnumDescriptor::ReservedRange
{
  int start;
  int end;
};

```

### `google::protobuf::Descriptor::ExtensionRange`
```
struct google::protobuf::Descriptor::ExtensionRange
{
  int start;
  int end;
  const google::protobuf::ExtensionRangeOptions *options_;
};

```

### `google::protobuf::Descriptor::ReservedRange`
```
struct google::protobuf::Descriptor::ReservedRange
{
  int start;
  int end;
};

```

### `google::protobuf::ServiceDescriptor`
```
struct __attribute__((aligned(8))) google::protobuf::ServiceDescriptor
{
  const std::string *name_;
  const std::string *full_name_;
  const google::protobuf::FileDescriptor *file_;
  const google::protobuf::ServiceOptions *options_;
  google::protobuf::MethodDescriptor *methods_;
  int method_count_;
};

```

### `google::protobuf::MethodDescriptor`
```
struct __attribute__((aligned(8))) google::protobuf::MethodDescriptor
{
  const std::string *name_;
  const std::string *full_name_;
  const google::protobuf::ServiceDescriptor *service_;
  google::protobuf::internal::LazyDescriptor input_type_;
  google::protobuf::internal::LazyDescriptor output_type_;
  const google::protobuf::MethodOptions *options_;
  bool client_streaming_;
  bool server_streaming_;
};

```

### `google::protobuf::internal::LazyDescriptor`
```
struct google::protobuf::internal::LazyDescriptor
{
  const google::protobuf::Descriptor *descriptor_;
  const std::string *name_;
  google::protobuf::GoogleOnceDynamic *once_;
  const google::protobuf::FileDescriptor *file_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Empty>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Empty>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Empty>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Message>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Message>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Message>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Xuid>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Xuid>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Xuid>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerName>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerName>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerName>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerList>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerList>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::PlayerList>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Settings>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Settings>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::Settings>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::LevelFileAndSize>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::LevelFileAndSize>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::LevelFileAndSize>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveQueryResult>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveQueryResult>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveQueryResult>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveStateResult>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveStateResult>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::SaveStateResult>::AlignedUnion union_;
};

```

### `google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport>`
```
struct google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport>
{
  google::protobuf::internal::ExplicitlyConstructed<com::mojang::clacks::protocol::MetricReport>::AlignedUnion union_;
};

```

### `google::protobuf::internal::InternalMetadataWithArenaBase<google::protobuf::UnknownFieldSet,google::protobuf::internal::InternalMetadataWithArena>::Container`
```
struct google::protobuf::internal::InternalMetadataWithArenaBase<google::protobuf::UnknownFieldSet,google::protobuf::internal::InternalMetadataWithArena>::Container
{
  google::protobuf::UnknownFieldSet unknown_fields;
  google::protobuf::Arena *arena;
};

```

### `google::protobuf::internal::SCCInfo<0>`
```
struct google::protobuf::internal::SCCInfo<0>
{
  google::protobuf::internal::SCCInfoBase base;
  google::protobuf::internal::SCCInfoBase *deps[1];
};

```

### `google::protobuf::internal::SCCInfo<2>`
```
struct google::protobuf::internal::SCCInfo<2>
{
  google::protobuf::internal::SCCInfoBase base;
  google::protobuf::internal::SCCInfoBase *deps[2];
};

```

### `google::protobuf::internal::SCCInfo<1>`
```
struct google::protobuf::internal::SCCInfo<1>
{
  google::protobuf::internal::SCCInfoBase base;
  google::protobuf::internal::SCCInfoBase *deps[1];
};

```

### `google::protobuf::internal::ParseTableField`
```
struct google::protobuf::internal::ParseTableField
{
  google::protobuf::uint32 offset;
  google::protobuf::uint32 presence_index;
  unsigned __int8 normal_wiretype;
  unsigned __int8 packed_wiretype;
  unsigned __int8 processing_type;
  unsigned __int8 tag_size;
};

```

### `google::protobuf::internal::AuxillaryParseTableField::enum_aux`
```
struct google::protobuf::internal::AuxillaryParseTableField::enum_aux
{
  google::protobuf::internal::AuxillaryParseTableField::EnumValidator validator;
};

```

### `google::protobuf::internal::AuxillaryParseTableField::message_aux`
```
struct google::protobuf::internal::AuxillaryParseTableField::message_aux
{
  const void *default_message_void;
};

```

### `google::protobuf::internal::AuxillaryParseTableField::string_aux`
```
struct google::protobuf::internal::AuxillaryParseTableField::string_aux
{
  const void *default_ptr;
  const char *field_name;
};

```

### `google::protobuf::internal::AuxillaryParseTableField::map_aux`
```
struct google::protobuf::internal::AuxillaryParseTableField::map_aux
{
  bool (*parse_map)(google::protobuf::io::CodedInputStream *, void *);
};

```

### `google::protobuf::internal::ParseTable`
```
struct __attribute__((aligned(8))) google::protobuf::internal::ParseTable
{
  const google::protobuf::internal::ParseTableField *fields;
  const google::protobuf::internal::AuxillaryParseTableField *aux;
  int max_field_number;
  google::protobuf::int64 has_bits_offset;
  google::protobuf::int64 oneof_case_offset;
  google::protobuf::int64 extension_offset;
  google::protobuf::int64 arena_offset;
  const void *default_instance_void;
  bool unknown_field_set;
};

```

### `google::protobuf::internal::FieldMetadata`
```
struct google::protobuf::internal::FieldMetadata
{
  google::protobuf::uint32 offset;
  google::protobuf::uint32 tag;
  google::protobuf::uint32 has_offset;
  google::protobuf::uint32 type;
  const void *ptr;
};

```

### `google::protobuf::internal::SerializationTable`
```
struct google::protobuf::internal::SerializationTable
{
  int num_fields;
  const google::protobuf::internal::FieldMetadata *field_table;
};

```

### `google::protobuf::internal::StringTypeTraits`
```
struct google::protobuf::internal::StringTypeTraits
{
  __int8 gap0[1];
};

```

### `google::protobuf::internal::ExtensionSet::KeyValue`
```
struct google::protobuf::internal::ExtensionSet::KeyValue
{
  int first;
  google::protobuf::internal::ExtensionSet::Extension second;
};

```

### `google::protobuf::internal::ExtensionSet::LargeMap`
```
typedef std::map<int,google::protobuf::internal::ExtensionSet::Extension> google::protobuf::internal::ExtensionSet::LargeMap;

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>::WeakType`
```
typedef com::mojang::clacks::protocol::PlayerInfo google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::PlayerInfo>::WeakType;

```

### `google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>::WeakType`
```
typedef com::mojang::clacks::protocol::LevelFileAndSize google::protobuf::internal::GenericTypeHandler<com::mojang::clacks::protocol::LevelFileAndSize>::WeakType;

```

### `google::protobuf::Metadata`
```
struct google::protobuf::Metadata
{
  const google::protobuf::Descriptor *descriptor;
  const google::protobuf::Reflection *reflection;
};

```

### `google::protobuf::Bits`
```
struct google::protobuf::Bits
{
  __int8 gap0[1];
};

```

