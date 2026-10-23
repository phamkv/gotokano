# English Patch: The Quintessential Quintuplets: Five Promises With Her

A fan-made English translation using LLMs for the Nintendo Switch release of *The Quintessential Quintuplets: Five Promises With Her*.

The patch is a **LayeredFS mod**. It doesn't change your game files. Your custom firmware or emulator loads the translated files from the `romfs` folder in place of the originals while the game runs. To uninstall it, remove or disable the mod.

## What's included

```
English Patch/
└── romfs/
    ├── config_*      # menus and settings
    ├── font_*        # fonts that support English text
    ├── motion_*      # translated UI and image text
    ├── scenario_*    # story script
    └── script_*      # game scripts
```

**Why does some of the menu text look small or squished?**
Most of the menu text isn't real text. It's drawn straight into the game's images, and each one has a fixed size. Japanese packs a whole word into two or three characters, but English needs a lot more room. Wherever the English didn't fit, I had to reduce the font size. That was the trade-off for keeping the whole text inside the original box and keeping the original colours, outlines and shadows.

**Is this AI slop translation?**
No, I don't intend that. The two earlier Quintuplets games got official English releases, and I forced the LLM to use the dialogues of them as style guide references. The aim is for this game to read like a continuation of the earlier games.

## Setup

Download latest release: https://github.com/phamkv/gotokano/releases

You need your own copy of the game, either on a Switch running custom firmware or dumped for an emulator. By downloading the patch, you agree in good faith that you are using it with a legally owned copy.

How you install a LayeredFS mod depends on what you play on, so follow the mod guide for your setup:

- **Switch with custom firmware (for example, Atmosphère):** look up how your CFW loads LayeredFS mods. For Atmosphère, the `phamkvEnglishPatch` folder goes in `atmosphere/contents/<Title ID>/`.
- **Emulators:** follow your emulator's mod guide. For Eden, see the [Eden Mods guide](https://git.eden-emu.dev/eden-emu/eden/src/branch/master/docs/user/Mods.md).

In every case, you put the `phamkvEnglishPatch` folder into your `<Title ID>/` folder.

## Support & feedback

If you need help, find a bug or typo, or want to send feedback (greatly appreciated), join the Discord server: **https://discord.gg/TkmvJ2jfvX**

## Copyright Notice

This is a fan translation offered free of charge and without any form of monetization. This patch only includes assets necessary to translate the base game to English, and is useless without the base game to patch over. I am in no way affiliated or related to MAGES., Spike Chunsoft, or any parties involved in the development of this game. By downloading my patch, you agree that you have obtained your copy of the game legitimately and legally. Nintendo Switch and Nintendo eShop are trademarks of Nintendo Co. ltd.
