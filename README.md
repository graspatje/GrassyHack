# GrassyHack

A mod menu for Geometry Dash 2.2081 (Geode), in the style of Mega Hack. Press **Tab** in game to open it.

Every hack is a switch: click it to turn it on or off, right-click it for its options and its keybind. All keybinds can also be changed in the Keybinds window.

## What's in it

- **Global:** speedhack (0.1x to 10x), safe mode, FPS bypass, TPS bypass, vertical sync, fast chest opening
- **Player:** noclip, instant respawn, custom respawn time, jump hack, auto clicker, Click Between Frames switch (needs the [Click Between Frames](https://geode-sdk.org/mods/syzzi.click_between_frames) mod), GD's click between steps and click on steps
- **Level:** start position switcher, smart start positions, frame stepper, death tracker, confirm exit, confirm practice, 0% practice complete, auto kill, auto deafen (Discord), jumpscare, instant complete, force platformer, auto music sync, restart from 0%, and buttons to uncomplete or reset a level's progress
- **Visual:** hitboxes, hitboxes on death, hitbox trail, trajectory, layout mode, show triggers
- **Cosmetic:** hide player, icon randomizer, players on top, trail options, wave trail and pulse options, no death effect, no respawn flash, no particles, no glow, no pulse, no shaders, no shake, no camera zoom, no mirror, accurate percentage, total attempts, pitch shifter and more
- **Bypass:** practice music, unlock main levels, unlock everything (icons, colors, shops, vaults, only while it's on), no slider limit, no text length limit
- **Labels:** custom text, clock, FPS, CPS, frame, session time, attempts, percentage, noclip accuracy and deaths, and a cheat indicator with rulesets (GD, Pointercrate, or your own)
- **Bot:** an auto bot that finds its own way through a level, macro recording and playback, and a macro converter for GDR (Mega Hack, xdBot, zBot, Prism Menu), GDR2 (Eclipse), ReplayEngine 3/4 (GDH), Silicate, TCBot, yBot 2 and older formats

Safe mode is on by default: a run where a cheat was on doesn't save your progress or send your score.

## Building

You need Windows, Visual Studio 2022 with the C++ tools, CMake, Ninja, the [Geode SDK](https://docs.geode-sdk.org/getting-started/geode-cli) (with the `GEODE_SDK` environment variable set) and the Geode CLI.

```
powershell -ExecutionPolicy Bypass -File build.ps1
```

The mod ends up in `out/graspatje.grassyhack.geode`. Put it in Geometry Dash's `geode/mods` folder, or build with `-Install` to do that for you.

## Credits

- [Dear ImGui](https://github.com/ocornut/imgui) by Omar Cornut (MIT license), in `libs/imgui`
- [gd-imgui-cocos](https://github.com/matcool/gd-imgui-cocos) by mat (MIT license), in `libs/imgui-cocos`
- Macro file layouts based on [zcb3](https://github.com/zeozeozeo/zcb3), [slc_oxide](https://github.com/silicate-bot/slc_oxide), [tcm-rs](https://github.com/tcbot-gd/tcm-rs) and [xdBot](https://github.com/Zilko/xdBot)
- Built with [Geode](https://geode-sdk.org)

## License

MIT, see [LICENSE](LICENSE). The libraries in `libs/` keep their own licenses.
