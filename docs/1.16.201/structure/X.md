# X
### `xtime`
Offset | Type | Name
-|-|-|-
0 | (8) `__int64` | sec
8 | (4) `int` | nsec


### `XforgeGameVersion`
Offset | Type | Name
-|-|-|-
0 | (20) `unsigned int[5]` | mDigit
24 | (32) `std::string` | mString


### `XMLDOMDocumentEvents_vtbl`
```
struct /*VFT*/ XMLDOMDocumentEvents_vtbl
{
  HRESULT (__fastcall *QueryInterface)(IUnknown *this, const _GUID *, void **);
  unsigned int (__fastcall *AddRef)(IUnknown *this);
  unsigned int (__fastcall *Release)(IUnknown *this);
  HRESULT (__fastcall *GetTypeInfoCount)(IDispatch *this, unsigned int *);
  HRESULT (__fastcall *GetTypeInfo)(IDispatch *this, unsigned int, unsigned int, ITypeInfo **);
  HRESULT (__fastcall *GetIDsOfNames)(IDispatch *this, const _GUID *, wchar_t **, unsigned int, unsigned int, int *);
  HRESULT (__fastcall *Invoke)(IDispatch *this, int, const _GUID *, unsigned int, unsigned __int16, tagDISPPARAMS *, tagVARIANT *, tagEXCEPINFO *, unsigned int *);
};

```

### `XMLDOMDocumentEvents`
```
struct __cppobj XMLDOMDocumentEvents : IDispatch
{
};

```

### `XblConsoleSignInScreenController`
```
struct __cppobj __declspec(align(8)) XblConsoleSignInScreenController : MinecraftScreenController
{
  const std::string mCode;
  const std::string mUrl;
  bool mDirty;
  const bool mLanguageCanBeSmooth;
};

```

### `XblConsoleSignInScreenController_vtbl`
```
struct /*VFT*/ XblConsoleSignInScreenController_vtbl
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

### `XblConsoleSignInSucceededScreenController`
```
struct __cppobj XblConsoleSignInSucceededScreenController : MinecraftScreenController
{
  Social::UserPicturePath mGamerPicPath;
  bool mDirty;
  bool mIsNewAccount;
  bool mDisplayedPicture;
  __declspec(align(2)) _BYTE mSignInResult[4];
  std::function<void __cdecl(enum Social::SignInResult)> mOnLetsPlayCallback;
};

```

### `XblConsoleSignInSucceededScreenController_vtbl`
```
struct /*VFT*/ XblConsoleSignInSucceededScreenController_vtbl
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

### `XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_2f4a09ef9243b7a441b7ffa6a4522b13>`
```
struct __cppobj XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_2f4a09ef9243b7a441b7ffa6a4522b13>
{
  XblConsoleSignInScreenController *const __this;
};

```

### `XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_a4660731f1f893bdfcafb3c37f3c74c1>`
```
struct __cppobj XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_a4660731f1f893bdfcafb3c37f3c74c1>
{
  XblConsoleSignInScreenController *const __this;
};

```

### `XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_faa4ecdd94945fc14413b33f4d36fe2a>`
```
struct __cppobj XblConsoleSignInScreenController::_registerBindings::__l2::<lambda_faa4ecdd94945fc14413b33f4d36fe2a>
{
  XblConsoleSignInScreenController *const __this;
};

```

### `XblConsoleSignInScreenController::_registerEventHandlers::__l2::<lambda_4bd8b8df77ee6e64cdcd96600abfc7a1>`
```
struct __cppobj XblConsoleSignInScreenController::_registerEventHandlers::__l2::<lambda_4bd8b8df77ee6e64cdcd96600abfc7a1>
{
};

```

### `XblFriendFinderScreenController`
```
struct __cppobj __declspec(align(8)) XblFriendFinderScreenController : MinecraftScreenController
{
  std::string mGamertag;
  bool mSearchingForGamertag;
  bool mGamertagNotFound;
  bool mShowPlatformAccounts;
  bool mDirty;
};

```

### `XblFriendFinderScreenController_vtbl`
```
struct /*VFT*/ XblFriendFinderScreenController_vtbl
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

### `XblReportUserScreenController`
```
struct __cppobj __declspec(align(4)) XblReportUserScreenController : MinecraftScreenController
{
  const std::string mGamertag;
  const std::string mXuid;
  std::string mReportAdditionalText;
  _BYTE mReportReason[4];
  bool mReportReasonDropDownActive;
  bool mReasonSelected;
};

```

### `XblReportUserScreenController_vtbl`
```
struct /*VFT*/ XblReportUserScreenController_vtbl
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

### `XblReportUserScreenController::_registerReportReasonDropdown::__l6::<lambda_88bcef1d7c9e57c41a90343c9670718a>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l6::<lambda_88bcef1d7c9e57c41a90343c9670718a>
{
  std::pair<std::string const ,enum Social::ReportReason> blockTypePair;
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l6::<lambda_e4888b90ce259c243405cc142b6a0274>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l6::<lambda_e4888b90ce259c243405cc142b6a0274>
{
  std::pair<std::string const ,enum Social::ReportReason> blockTypePair;
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_b4b1334bb14fefc5f38cc3b84ad43f4a>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_b4b1334bb14fefc5f38cc3b84ad43f4a>
{
  std::vector<std::string> reportReasonLabels;
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_e8c7814febe457a2b6aaf115b255ed1b>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_e8c7814febe457a2b6aaf115b255ed1b>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_f70f0bf90b49a54b217fa4fbac44b339>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_f70f0bf90b49a54b217fa4fbac44b339>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_fd371238e2ca7481dafd38b7db268828>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_fd371238e2ca7481dafd38b7db268828>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_10dbbaa422c82c7b0aaa698b196c8860>`
```
struct __cppobj XblReportUserScreenController::_registerReportReasonDropdown::__l2::<lambda_10dbbaa422c82c7b0aaa698b196c8860>
{
  const std::string dropdownName;
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerBindings::__l2::<lambda_a0334f7b4aebbfa53ba98b2353bc46a0>`
```
struct __cppobj XblReportUserScreenController::_registerBindings::__l2::<lambda_a0334f7b4aebbfa53ba98b2353bc46a0>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerBindings::__l2::<lambda_fd0f9d83b563f9139c951c7bab4be1ad>`
```
struct __cppobj XblReportUserScreenController::_registerBindings::__l2::<lambda_fd0f9d83b563f9139c951c7bab4be1ad>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_ae05fab552e586cbc7d5fdc3c1c86c91>`
```
struct __cppobj XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_ae05fab552e586cbc7d5fdc3c1c86c91>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_d06a57ef78bf8fcf5bf1ef99580152bb>`
```
struct __cppobj XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_d06a57ef78bf8fcf5bf1ef99580152bb>
{
  XblReportUserScreenController *const __this;
};

```

### `XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_d06a57ef78bf8fcf5bf1ef99580152bb>::()::__l2::<lambda_ca803275f04f4837cd092ef34211a85d>`
```
struct __cppobj XblReportUserScreenController::_registerEventHandlers::__l2::<lambda_d06a57ef78bf8fcf5bf1ef99580152bb>::()::__l2::<lambda_ca803275f04f4837cd092ef34211a85d>
{
  std::shared_ptr<MinecraftScreenModel> sharedMinecraftScreenModel;
  std::string gamertag;
};

```

### `XblFriendFinderScreenController::_checkLinkedProfiles::__l2::<lambda_b9ae3cfd4bb0a767f638b0615f147218>`
```
struct __cppobj XblFriendFinderScreenController::_checkLinkedProfiles::__l2::<lambda_b9ae3cfd4bb0a767f638b0615f147218>
{
  std::weak_ptr<XblFriendFinderScreenController> weakThis;
  const Social::XboxLiveUserProfileData xboxProfile;
};

```

### `XblFriendFinderScreenController::_checkLinkedProfiles::__l2::<lambda_b9ae3cfd4bb0a767f638b0615f147218>::()::__l8::<lambda_bb5c55fccfae49aaefc2ba322ac9d152>`
```
struct __cppobj XblFriendFinderScreenController::_checkLinkedProfiles::__l2::<lambda_b9ae3cfd4bb0a767f638b0615f147218>::()::__l8::<lambda_bb5c55fccfae49aaefc2ba322ac9d152>
{
  std::weak_ptr<XblFriendFinderScreenController> weakThis;
  std::string xuid;
  std::string uuid;
};

```

### `XblFriendFinderScreenController::_registerEventHandlers::__l2::<lambda_de17937c2e542e02b685f02b95117836>::()::__l5::<lambda_c0feb565d82aad36c0ce654825cdf3b0>`
```
struct __cppobj XblFriendFinderScreenController::_registerEventHandlers::__l2::<lambda_de17937c2e542e02b685f02b95117836>::()::__l5::<lambda_c0feb565d82aad36c0ce654825cdf3b0>
{
  std::weak_ptr<XblFriendFinderScreenController> weakThis;
};

```

### `XPCommand`
```
struct __cppobj XPCommand : Command
{
  CommandSelector<Player> mTargets;
  int mXP;
  int mLevels;
};

```

### `XPCommand_vtbl`
```
struct /*VFT*/ XPCommand_vtbl
{
  void (__fastcall *~Command)(Command *this);
  void (__fastcall *execute)(Command *this, const CommandOrigin *, CommandOutput *);
};

```

### `X509_algor_st`
```
struct X509_algor_st
{
  asn1_object_st *algorithm;
  asn1_type_st *parameter;
};

```

### `X509_info_st`
```
struct X509_info_st
{
  struct x509_st *x509;
  struct X509_crl_st *crl;
  private_key_st *x_pkey;
  evp_cipher_info_st enc_cipher;
  int enc_len;
  char *enc_data;
};

```

### `x509_trust_st`
```
struct x509_trust_st
{
  int trust;
  int flags;
  int (__fastcall *check_trust)(x509_trust_st *, struct x509_st *, int);
  char *name;
  int arg1;
  void *arg2;
};

```

