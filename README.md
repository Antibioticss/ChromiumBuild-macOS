# ChromiumBuild-macOS

Chromium for macOS, built from official unmodified source code

- [x] All codecs

Go to Release to download

## Build environment

macOS 13.5, ARM

Xcode Version 14.3.1

## Used gn args

```args
target_cpu="x64" # only for x64 build

is_debug = false
is_component_build = false
dcheck_always_on = false
is_official_build=true

symbol_level = 0
blink_symbol_level=0
v8_symbol_level=0
chrome_pgo_phase=0

enable_nacl = false

proprietary_codecs = true
ffmpeg_branding = "Chrome"
```

If you have better ideas, please create issues.

I don't have much experience, any advice would be greatly appreciated.
