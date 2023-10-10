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