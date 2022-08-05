# Q
### `QueryRegistrationResult`
```
typedef IMinecraftEventing::AuthenticationOutcome QueryRegistrationResult;

```

### `QUERY_USER_NOTIFICATION_STATE`
```
enum QUERY_USER_NOTIFICATION_STATE : __int32
{
  QUNS_NOT_PRESENT = 0x1,
  QUNS_BUSY = 0x2,
  QUNS_RUNNING_D3D_FULL_SCREEN = 0x3,
  QUNS_PRESENTATION_MODE = 0x4,
  QUNS_ACCEPTS_NOTIFICATIONS = 0x5,
  QUNS_QUIET_TIME = 0x6,
};

```

### `QueryResult`
```
typedef IMinecraftEventing::AuthenticationOutcome QueryResult;

```

### `QueueRequestResult`
```
enum QueueRequestResult : __int8
{
  CanExecuteNow = 0x0,
  Queued = 0x1,
};

```

