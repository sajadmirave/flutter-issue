# Issues

[!] Proxy Configuration
    ! NO_PROXY does not contain ::1

use this:

```bash
setx NO_PROXY "existing-value,localhost,127.0.0.1,::1"
```