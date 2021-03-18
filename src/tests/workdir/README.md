This directory contains libraries to be used for linking by CMake.

`libsteam_api.dylib` has been patched to fix a linking issue.

```bash
install_name_tool -id "@rpath/libsteam_api.dylib" libsteam_api.dylib
```
