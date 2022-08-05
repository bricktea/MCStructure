# W
### `WorldInfo::Status`
Name | Value
-|-
Online | `0`
Offline | `1`
Unavailable | `2`


### `WeatherRenderObject::PrecipitationType`
Name | Value
-|-
PRECIPITATION_RAIN | `0`
PRECIPITATION_SNOW | `1`
PRECIPITATION_PLANKTON | `2`
PRECIPITATION_RED_SPORES | `3`
PRECIPITATION_BLUE_SPORES | `4`
PRECIPITATION_ASH | `5`
PRECIPITATION_WHITE_ASH | `6`
PRECIPITATION_COUNT | `7`


### `WeatherCommand::WeatherType`
Name | Value
-|-
Clear | `0`
Rain | `1`
Thunder | `2`


### `WallConnectionType`
Name | Value
-|-


### `WoodType`
Name | Value
-|-


### `WallBlockType`
Name | Value
-|-


### `wrapEncodedKERNEL32Functions`
```
enum wrapEncodedKERNEL32Functions : __int32
{
  eFlsAlloc = 0x0,
  eFlsFree = 0x1,
  eFlsGetValue = 0x2,
  eFlsSetValue = 0x3,
  eInitializeCriticalSectionEx = 0x4,
  eInitOnceExecuteOnce = 0x5,
  eCreateEventExW = 0x6,
  eCreateSemaphoreW = 0x7,
  eCreateSemaphoreExW = 0x8,
  eCreateThreadpoolTimer = 0x9,
  eSetThreadpoolTimer = 0xA,
  eWaitForThreadpoolTimerCallbacks = 0xB,
  eCloseThreadpoolTimer = 0xC,
  eCreateThreadpoolWait = 0xD,
  eSetThreadpoolWait = 0xE,
  eCloseThreadpoolWait = 0xF,
  eFlushProcessWriteBuffers = 0x10,
  eFreeLibraryWhenCallbackReturns = 0x11,
  eGetCurrentProcessorNumber = 0x12,
  eCreateSymbolicLinkW = 0x13,
  eGetCurrentPackageId = 0x14,
  eGetTickCount64 = 0x15,
  eGetFileInformationByHandleEx = 0x16,
  eSetFileInformationByHandle = 0x17,
  eGetSystemTimePreciseAsFileTime = 0x18,
  eInitializeConditionVariable = 0x19,
  eWakeConditionVariable = 0x1A,
  eWakeAllConditionVariable = 0x1B,
  eSleepConditionVariableCS = 0x1C,
  eInitializeSRWLock = 0x1D,
  eAcquireSRWLockExclusive = 0x1E,
  eTryAcquireSRWLockExclusive = 0x1F,
  eReleaseSRWLockExclusive = 0x20,
  eSleepConditionVariableSRW = 0x21,
  eCreateThreadpoolWork = 0x22,
  eSubmitThreadpoolWork = 0x23,
  eCloseThreadpoolWork = 0x24,
  eCompareStringEx = 0x25,
  eGetLocaleInfoEx = 0x26,
  eLCMapStringEx = 0x27,
  eMaxKernel32Function = 0x28,
};

```

### `WeakStorageEntity::EmptyInit`
```
enum WeakStorageEntity::EmptyInit : __int32
{
  NoValue = 0x0,
};

```

### `WeakStorageEntity::VariadicInit`
```
enum WeakStorageEntity::VariadicInit : __int32
{
  NonAmbiguous = 0x0,
};

```

### `WeakStorageSharePtr<EntityRegistry>::EmptyInit`
```
typedef WeakStorageEntity::EmptyInit WeakStorageSharePtr<EntityRegistry>::EmptyInit;

```

### `WeakStorageSharePtr<EntityRegistry>::VariadicInit`
```
typedef WeakStorageEntity::VariadicInit WeakStorageSharePtr<EntityRegistry>::VariadicInit;

```

### `WorldConversionError`
```
typedef Rotation WorldConversionError;

```

### `WeakStorageSharePtr<FogDefinition const >::EmptyInit`
```
typedef WeakStorageEntity::EmptyInit WeakStorageSharePtr<FogDefinition const >::EmptyInit;

```

### `WeakStorageSharePtr<FogDefinition const >::VariadicInit`
```
typedef WeakStorageEntity::VariadicInit WeakStorageSharePtr<FogDefinition const >::VariadicInit;

```

### `WeirdoDirection`
```
typedef DimensionId WeirdoDirection;

```

### `WorldPacksHistoryFile::ParseResult`
```
typedef IMinecraftEventing::AuthenticationOutcome WorldPacksHistoryFile::ParseResult;

```

### `WeatherRenderObject::<unnamed_enum_PASS_COUNT>`
```
enum WeatherRenderObject::<unnamed_enum_PASS_COUNT> : __int32
{
  PASS_COUNT = 0xA,
};

```

### `WELL_KNOWN_SID_TYPE`
```
enum WELL_KNOWN_SID_TYPE : __int32
{
  WinNullSid = 0x0,
  WinWorldSid = 0x1,
  WinLocalSid = 0x2,
  WinCreatorOwnerSid = 0x3,
  WinCreatorGroupSid = 0x4,
  WinCreatorOwnerServerSid = 0x5,
  WinCreatorGroupServerSid = 0x6,
  WinNtAuthoritySid = 0x7,
  WinDialupSid = 0x8,
  WinNetworkSid = 0x9,
  WinBatchSid = 0xA,
  WinInteractiveSid = 0xB,
  WinServiceSid = 0xC,
  WinAnonymousSid = 0xD,
  WinProxySid = 0xE,
  WinEnterpriseControllersSid = 0xF,
  WinSelfSid = 0x10,
  WinAuthenticatedUserSid = 0x11,
  WinRestrictedCodeSid = 0x12,
  WinTerminalServerSid = 0x13,
  WinRemoteLogonIdSid = 0x14,
  WinLogonIdsSid = 0x15,
  WinLocalSystemSid = 0x16,
  WinLocalServiceSid = 0x17,
  WinNetworkServiceSid = 0x18,
  WinBuiltinDomainSid = 0x19,
  WinBuiltinAdministratorsSid = 0x1A,
  WinBuiltinUsersSid = 0x1B,
  WinBuiltinGuestsSid = 0x1C,
  WinBuiltinPowerUsersSid = 0x1D,
  WinBuiltinAccountOperatorsSid = 0x1E,
  WinBuiltinSystemOperatorsSid = 0x1F,
  WinBuiltinPrintOperatorsSid = 0x20,
  WinBuiltinBackupOperatorsSid = 0x21,
  WinBuiltinReplicatorSid = 0x22,
  WinBuiltinPreWindows2000CompatibleAccessSid = 0x23,
  WinBuiltinRemoteDesktopUsersSid = 0x24,
  WinBuiltinNetworkConfigurationOperatorsSid = 0x25,
  WinAccountAdministratorSid = 0x26,
  WinAccountGuestSid = 0x27,
  WinAccountKrbtgtSid = 0x28,
  WinAccountDomainAdminsSid = 0x29,
  WinAccountDomainUsersSid = 0x2A,
  WinAccountDomainGuestsSid = 0x2B,
  WinAccountComputersSid = 0x2C,
  WinAccountControllersSid = 0x2D,
  WinAccountCertAdminsSid = 0x2E,
  WinAccountSchemaAdminsSid = 0x2F,
  WinAccountEnterpriseAdminsSid = 0x30,
  WinAccountPolicyAdminsSid = 0x31,
  WinAccountRasAndIasServersSid = 0x32,
  WinNTLMAuthenticationSid = 0x33,
  WinDigestAuthenticationSid = 0x34,
  WinSChannelAuthenticationSid = 0x35,
  WinThisOrganizationSid = 0x36,
  WinOtherOrganizationSid = 0x37,
  WinBuiltinIncomingForestTrustBuildersSid = 0x38,
  WinBuiltinPerfMonitoringUsersSid = 0x39,
  WinBuiltinPerfLoggingUsersSid = 0x3A,
  WinBuiltinAuthorizationAccessSid = 0x3B,
  WinBuiltinTerminalServerLicenseServersSid = 0x3C,
  WinBuiltinDCOMUsersSid = 0x3D,
  WinBuiltinIUsersSid = 0x3E,
  WinIUserSid = 0x3F,
  WinBuiltinCryptoOperatorsSid = 0x40,
  WinUntrustedLabelSid = 0x41,
  WinLowLabelSid = 0x42,
  WinMediumLabelSid = 0x43,
  WinHighLabelSid = 0x44,
  WinSystemLabelSid = 0x45,
  WinWriteRestrictedCodeSid = 0x46,
  WinCreatorOwnerRightsSid = 0x47,
  WinCacheablePrincipalsGroupSid = 0x48,
  WinNonCacheablePrincipalsGroupSid = 0x49,
  WinEnterpriseReadonlyControllersSid = 0x4A,
  WinAccountReadonlyControllersSid = 0x4B,
  WinBuiltinEventLogReadersGroup = 0x4C,
  WinNewEnterpriseReadonlyControllersSid = 0x4D,
  WinBuiltinCertSvcDComAccessGroup = 0x4E,
  WinMediumPlusLabelSid = 0x4F,
  WinLocalLogonSid = 0x50,
  WinConsoleLogonSid = 0x51,
  WinThisOrganizationCertificateSid = 0x52,
  WinApplicationPackageAuthoritySid = 0x53,
  WinBuiltinAnyPackageSid = 0x54,
  WinCapabilityInternetClientSid = 0x55,
  WinCapabilityInternetClientServerSid = 0x56,
  WinCapabilityPrivateNetworkClientServerSid = 0x57,
  WinCapabilityPicturesLibrarySid = 0x58,
  WinCapabilityVideosLibrarySid = 0x59,
  WinCapabilityMusicLibrarySid = 0x5A,
  WinCapabilityDocumentsLibrarySid = 0x5B,
  WinCapabilitySharedUserCertificatesSid = 0x5C,
  WinCapabilityEnterpriseAuthenticationSid = 0x5D,
  WinCapabilityRemovableStorageSid = 0x5E,
  WinBuiltinRDSRemoteAccessServersSid = 0x5F,
  WinBuiltinRDSEndpointServersSid = 0x60,
  WinBuiltinRDSManagementServersSid = 0x61,
  WinUserModeDriversSid = 0x62,
  WinBuiltinHyperVAdminsSid = 0x63,
  WinAccountCloneableControllersSid = 0x64,
  WinBuiltinAccessControlAssistanceOperatorsSid = 0x65,
  WinBuiltinRemoteManagementUsersSid = 0x66,
  WinAuthenticationAuthorityAssertedSid = 0x67,
  WinAuthenticationServiceAssertedSid = 0x68,
  WinLocalAccountSid = 0x69,
  WinLocalAccountAndAdministratorSid = 0x6A,
  WinAccountProtectedUsersSid = 0x6B,
  WinCapabilityAppointmentsSid = 0x6C,
  WinCapabilityContactsSid = 0x6D,
  WinAccountDefaultSystemManagedSid = 0x6E,
  WinBuiltinDefaultSystemManagedGroupSid = 0x6F,
  WinBuiltinStorageReplicaAdminsSid = 0x70,
  WinAccountKeyAdminsSid = 0x71,
  WinAccountEnterpriseKeyAdminsSid = 0x72,
  WinAuthenticationKeyTrustSid = 0x73,
  WinAuthenticationKeyPropertyMFASid = 0x74,
  WinAuthenticationKeyPropertyAttestationSid = 0x75,
  WinAuthenticationFreshKeyAuthSid = 0x76,
  WinBuiltinDeviceOwnersSid = 0x77,
};

```

### `WorldType`
```
typedef RealmsEnvironment WorldType;

```

### `WorldPingStatus`
```
typedef NetworkPeer::NetworkLoad WorldPingStatus;

```

### `WorldInfoType`
```
typedef Rotation WorldInfoType;

```

### `WSConnectionResult`
```
typedef IMinecraftEventing::AuthenticationOutcome WSConnectionResult;

```

### `WebviewInterfaceType`
```
typedef NetworkIdentifier::Type WebviewInterfaceType;

```

### `WindowsStoreMode`
```
typedef DimensionId WindowsStoreMode;

```

### `WebSocketCommunicator::SocketType`
```
typedef ActorEvent WebSocketCommunicator::SocketType;

```

### `WorldProcessProgressHandler::Type`
```
typedef IMinecraftEventing::FileTransmissionDirection WorldProcessProgressHandler::Type;

```

### `WorldVerificationResult`
```
typedef StreamReadResult WorldVerificationResult;

```

### `WebviewError::Type`
```
typedef cg::ColorSpace WebviewError::Type;

```

### `WeakStorageSharePtr<FogDefinition>::EmptyInit`
```
typedef WeakStorageEntity::EmptyInit WeakStorageSharePtr<FogDefinition>::EmptyInit;

```

### `WeakStorageSharePtr<FogDefinition>::VariadicInit`
```
typedef WeakStorageEntity::VariadicInit WeakStorageSharePtr<FogDefinition>::VariadicInit;

```

### `Win32MockStore::InternalPurchase::Status`
```
typedef Player::DimensionState Win32MockStore::InternalPurchase::Status;

```

### `WeakStorageFeature::EmptyInit`
```
typedef WeakStorageEntity::EmptyInit WeakStorageFeature::EmptyInit;

```

### `WeakStorageFeature::VariadicInit`
```
typedef WeakStorageEntity::VariadicInit WeakStorageFeature::VariadicInit;

```

### `WeatherCommand::WeatherRequest`
```
typedef PermissionCommand::Action WeatherCommand::WeatherRequest;

```

### `WebSocketMessageType`
```
typedef CreditsRenderer::CreditsContent::Type WebSocketMessageType;

```

### `WeakStorageSharePtr<PerlinSimplexNoise>::EmptyInit`
```
typedef WeakStorageEntity::EmptyInit WeakStorageSharePtr<PerlinSimplexNoise>::EmptyInit;

```

### `WeakStorageSharePtr<PerlinSimplexNoise>::VariadicInit`
```
typedef WeakStorageEntity::VariadicInit WeakStorageSharePtr<PerlinSimplexNoise>::VariadicInit;

```

### `Windows::Foundation::Diagnostics::RoErrorReportingFlags`
```
typedef Rotation Windows::Foundation::Diagnostics::RoErrorReportingFlags;

```

### `WildcardString::Case`
```
enum WildcardString::Case : __int32
{
  Sensitive = 0x0,
  Insensitive = 0x1,
};

```

### `why_code`
```
enum why_code : __int32
{
  WHY_NOT = 0x1,
  WHY_EXCEPTION = 0x2,
  WHY_RERAISE = 0x4,
  WHY_RETURN = 0x8,
  WHY_BREAK = 0x10,
  WHY_CONTINUE = 0x20,
  WHY_YIELD = 0x40,
};

```

### `WoodlandMansionPieces::WoodlandMansionPiece::_addChest::__l2::SensibleDirections`
```
typedef Direction::Type WoodlandMansionPieces::WoodlandMansionPiece::_addChest::__l2::SensibleDirections;

```

