# Shiromino - Playstation Vita port
All known features are working perfectly. Needs some aesthetic refreshes and code cleanup.

## Building
Requires a [Vita SDK](https://vitasdk.org) environment. Inside, install `SDL2`, `SDL2_image` and `SDL2_mixer`. `debugnet` is currently required for debugging, but will be made an optional dependency. Additionally requires [VitaSmith/libsqlite](https://github.com/VitaSmith/libsqlite), install it into the SDK directory overwriting existing (crippled) version of sqlite.

To build, run `cmake CMakeLists.txt` and then `make`.

## Known issues
 * Debugging permanently enabled, hardcoded IP and port
 * Stretched backgrounds
 * Bad usage of screen estate
 * PC specific dead code
 * Pointless config