# SRB2 Legacy Android Port

Based off [bitten2up/Kart-Public/android](https://github.com/bitten2up/Kart-Public/tree/android). This port is currently in an experimental state.

## Status

- [x] Compiles
- [x] Runs
- [x] Software renderer
- [ ] OpenGL renderer
     - gl4es is not compatible with SRB2 in its current state.
- [x] Gamepad controls
     - Works, but remapping might be required. This is the recommended way to play this port.
- [x] Keyboard controls
- [ ] Touch controls
     - Not planned. It wouldn't play very well anyway.
     - Note that you can use touch to move the camera like you would with a mouse.
- [x] On-screen keyboard for text input
     - Somewhat buggy, it sometimes appears when it shouldn't
- [x] Netplay
- [x] Logs
     - latest-log.txt works, dated logs are not yet working
- [x] Addon support
- [x] Native Resolutions
- [x] Full digital music support (libopenmpt, libgme)
- [x] Correct app icon
- [x] Non-hardcoded CMake
     - Possible to build with CMake on non-Android, still needs more cleanup
- [x] SAF support
- [ ] Prepackaged assets
- [x] Distributable build
- [ ] Merge into next

Note: this is an ideal list. Don't expect everything listed to actually be done.
