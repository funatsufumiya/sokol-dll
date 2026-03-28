# sokol-dll

```bash
# win
$ clang -shared -o lib/libsokol.dll src/sokol_dll.c -Iinclude

# linux
$ clang -shared -o lib/libapp.so src/app.cpp -Iinclude -fPIC -lXi -lX11 -lGL -lXcursor

# mac
$ clang -shared -o lib/libapp.dylib src/app.mm -Iinclude -lobjc -framework CoreFoundation -framework Metal -framework IOKit -framework Cocoa
```