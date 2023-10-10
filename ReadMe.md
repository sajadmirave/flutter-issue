# Issues

[!] Proxy Configuration
    ! NO_PROXY does not contain ::1

use this:

```bash
setx NO_PROXY "existing-value,localhost,127.0.0.1,::1"
```

---

[!] Android toolchain - develop for Android devices (Android SDK version 33.0.2)
    X Android license status unknown.
      Run `flutter doctor --android-licenses` to accept the SDK licenses.
      See https://flutter.dev/docs/get-started/install/windows#android-setup for more details.

```bash
flutter doctor --android-licenses
```

---
if you see this error when you use:

flutter doctor --android-licenses

Error: The proxy server URL extracted from HTTP_PROXY or HTTPS_PROXY environment variable could not be parsed. Either specify the correct URL or unset the environment variable.

solution: Inactive your vpn and use shecan:

https://shecan.ir/

---