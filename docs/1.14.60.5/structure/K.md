# K
### `KeyManager`
Offset | Type | Name
-|-|-|-
0 | (8) `int (**)(void)` | _vptr$KeyManager
8 | (32) `std::string` | mPublicKey
40 | (8) `Unique<Crypto::Asymmetric::Asymmetric>` | mInstance


### `KeyFrameTransformData`
Offset | Type | Name
-|-|-|-
0 | (24) `std::vector<ChannelTransform>` | mChannelTransforms


### `KeyFrameLerpMode`
Offset | Type | Name
-|-|-|-
0 | (64) `glm::mat4` | mPrecomputedCubicCoeffs
64 | (4) `KeyFrameLerpStyle` | mLerpStyle


### `KeyFrameTransform`
Offset | Type | Name
-|-|-|-
0 | (4) `float` | mTime
8 | (24) `KeyFrameTransformData` | mPre
32 | (24) `KeyFrameTransformData` | mPost
56 | (68) `KeyFrameLerpMode` | mLerpMode


### `KeyFrameTransform::computeCubicPolynomial::$7EF7C94BEAB75C6CEF4ADFB99B570420`
Offset | Type | Name
-|-|-|-
0 | (1) `__int8[1]` | gap0


### `kernel_iovec`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | iov_base
8 | (8) `unsigned __int64` | iov_len


### `kernel_msghdr`
Offset | Type | Name
-|-|-|-
0 | (8) `void *` | msg_name
8 | (4) `int` | msg_namelen
16 | (8) `kernel_iovec *` | msg_iov
24 | (8) `unsigned __int64` | msg_iovlen
32 | (8) `void *` | msg_control
40 | (8) `unsigned __int64` | msg_controllen
48 | (4) `unsigned int` | msg_flags


### `kernel_stat`
Offset | Type | Name
-|-|-|-
0 | (8) `uint64_t` | st_dev
8 | (8) `uint64_t` | st_ino
16 | (8) `uint64_t` | st_nlink
24 | (4) `unsigned int` | st_mode
28 | (4) `unsigned int` | st_uid
32 | (4) `unsigned int` | st_gid
36 | (4) `unsigned int` | __pad0
40 | (8) `uint64_t` | st_rdev
48 | (8) `int64_t` | st_size
56 | (8) `int64_t` | st_blksize
64 | (8) `int64_t` | st_blocks
72 | (8) `uint64_t` | st_atime_
80 | (8) `uint64_t` | st_atime_nsec_
88 | (8) `uint64_t` | st_mtime_
96 | (8) `uint64_t` | st_mtime_nsec_
104 | (8) `uint64_t` | st_ctime_
112 | (8) `uint64_t` | st_ctime_nsec_
120 | (24) `int64_t[3]` | __unused4


### `KelpFeature`
```
struct __cppobj KelpFeature : Feature
{
};

```

### `KnockbackRoarGoal`
```
struct __cppobj __attribute__((aligned(8))) KnockbackRoarGoal : Goal:96
{
  const int mDuration;
  const int mAttackTime;
  const int mKnockbackDamage;
  const int mKnockbackStrength;
  const int mKnockbackRange;
  ActorFilterGroup mKnockbackFilter;
  ActorFilterGroup mDamageFilter;
  const DefinitionTrigger mOnRoarEnd;
  const int mCooldownTime;
  int mCurrentCooldown;
  Mob *mMob;
  int mRoarTime;
};

```

### `KelpBlock`
```
struct __cppobj KelpBlock : BlockLegacy
{
};

```

### `KickCommand`
```
struct __cppobj KickCommand : ServerCommand
{
  std::string mNameOrXuid;
  CommandMessage mMessage;
};

```

### `KillCommand`
```
struct __cppobj KillCommand : Command
{
  ActorSelector mTargets;
};

```

### `kernel_dirent`
```
struct __attribute__((aligned(8))) kernel_dirent
{
  __int64 d_ino;
  __int64 d_off;
  unsigned __int16 d_reclen;
  char d_name[256];
};

```

