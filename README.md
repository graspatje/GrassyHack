# GrassyHack

A mod menu for Geometry Dash 2.2081 (Geode), in the style of Mega Hack. Press **Tab** in game to open it.

Every hack is a switch: click it to turn it on or off, right-click it for its options and its keybind. All keybinds can also be changed in the Keybinds window.

Found a bug or have an idea? Click **Bugs & Suggestions** in the GrassyHack window, or join the [Discord server](https://discord.gg/GpSQcTrKAs).

## How to install

1. Install [Geode](https://geode-sdk.org) if you don't have it yet.
2. Download [graspatje.grassyhack.geode](graspatje.grassyhack.geode) (click it, then the download button).
3. Put it in Geometry Dash's `geode/mods` folder. On Steam: right-click Geometry Dash, click **Manage**, then **Browse local files**, and open `geode`, then `mods`.
4. Start Geometry Dash and press **Tab**.

## What's in it

- **Global:** speedhack (0.1x to 10x), safe mode, FPS bypass, TPS bypass, vertical sync, fast chest opening, see more levels (zooms out the level lists in search, saved and created levels)
- **Player:** noclip, instant respawn, custom respawn time, jump hack, auto clicker, Click Between Frames switch (needs the [Click Between Frames](https://geode-sdk.org/mods/syzzi.click_between_frames) mod), GD's click between steps and click on steps
- **Level:** start position switcher, smart start positions, frame stepper, death tracker, confirm exit, confirm practice, 0% practice complete, auto kill, auto deafen (Discord), jumpscare, instant complete, force platformer, auto music sync, restart from 0%, and buttons to uncomplete or reset a level's progress
- **Visual:** hitboxes, hitboxes on death, hitbox trail, trajectory, layout mode, show triggers
- **Cosmetic:** hide player, icon randomizer, players on top, trail options, wave trail and pulse options, no death effect, no respawn flash, no particles, no glow, no pulse, no shaders, no shake, no camera zoom, no mirror, accurate percentage, total attempts, custom font, pitch shifter and more
- **Bypass:** practice music, unlock main levels, unlock everything (icons, colors, shops, vaults, only while it's on), no slider limit, no text length limit
- **Labels:** custom text, clock, FPS, CPS, frame, session time, attempts, percentage, noclip accuracy and deaths, and a cheat indicator with rulesets (GD, Pointercrate, or your own)
- **AI Chat:** talk to an AI that knows the menu and can turn hacks on and off or change the game speed for you (see below)
- **Bot:** an auto bot that finds its own way through a level, macro recording and playback, and a macro converter for GDR (Mega Hack, xdBot, zBot, Prism Menu), GDR2 (Eclipse), ReplayEngine 3/4 (GDH), Silicate, TCBot, yBot 2 and older formats

Safe mode is on by default: a run where a cheat was on doesn't save your progress or send your score.

## AI Chat

The AI Chat button in the GrassyHack window opens a chat with a free AI. It runs on [Groq](https://groq.com), which has free AI models with a daily message limit. Each player uses their own free key:

1. Go to [console.groq.com/keys](https://console.groq.com/keys) and make a Groq account. Groq is meant for people 18 and older.
2. Click **Create API Key** and copy the key.
3. Paste it into the AI Chat window and click **Save**.

The key is only saved on your own PC, in GrassyHack's saved options. What you type in the chat goes to Groq and nowhere else. In the chat's settings you can pick another model, stop the AI from changing hacks, change or remove the key, and set a key to open the chat.

Your picture in the chat is the cube you have picked in GD. The AI's picture can be any GD icon (any type, number and colors, with or without glow) or a picture from your PC, also in the chat's settings.

## Custom Font

Custom Font (in the Cosmetic window) puts a font from your PC on all of GD's text. Pick one of your installed fonts in its options, or a .ttf or .otf file you downloaded. GrassyHack draws it in GD's style, with the black outline, shadow and gold colors, and saves it in its save folder. Text that level creators placed in their levels keeps its own font.

## Credits

- [Dear ImGui](https://github.com/ocornut/imgui) by Omar Cornut (MIT license), in `libs/imgui`
- [gd-imgui-cocos](https://github.com/matcool/gd-imgui-cocos) by mat (MIT license), in `libs/imgui-cocos`
- Macro file layouts based on [zcb3](https://github.com/zeozeozeo/zcb3), [slc_oxide](https://github.com/silicate-bot/slc_oxide), [tcm-rs](https://github.com/tcbot-gd/tcm-rs) and [xdBot](https://github.com/Zilko/xdBot)
- [stb_truetype](https://github.com/nothings/stb) by Sean Barrett (public domain), the copy that comes with Dear ImGui, for Custom Font
- Built with [Geode](https://geode-sdk.org)

## License

MIT, see `LICENSE` in GrassyHack-source.zip. The libraries in `libs/` keep their own licenses.
