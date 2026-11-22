# deco

iOS app (`.ipa`) for deobfuscating Lua/Luau. Runs fully offline inside a WebView.

Supported: Prometheus, Clyde, LuaObfuscator. Detection only: Luraph, MoonSec V3, 77fuscator, IronBrew.

## Build

Actions → Build IPA → Run workflow. Enter an app name and bundle ID (leave the site URL empty).
The finished `app.ipa` appears in Releases. Open it in LiveContainer.
