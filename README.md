# RetroArch Minimal Windows Builds

## The Minimal build disables:
- qt (desktop interface)
- ffmpeg (audio and video file playback) 
- sdl2 (controller input, but xinput and dinput are still available)

## The Super Minimal build disables:
- qt (desktop interface)
- ffmpeg (audio and video file playback) 
- sdl2 (controller input, but xinput and dinput are still available)
- overlays
- networking (core and asset updaters, acheivements, online play)
- video filters
- glsl shaders
- bsv movie file support
- dsp audio filters
- cheats
- rewind
- accessibility features
- translation
- cdrom drive reading
- image file viewer
- blissbox support
- xmb, materialui and rgui interfaces (only ozone)
- d3d9, d3d10 and d3d12 video drivers
- wasapi and dsound audio drivers
- libretro database support
- audio mixer
- freetype font support
- extra languages
- cc and nearest audio resamplers
- crt switchres support
- 7z/zip archived content frontend support (cores like fbneo that have 7z/zip support internally can still load them)
- softpatching
