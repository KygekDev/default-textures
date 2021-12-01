# Minecraft Bedrock Default Vanilla Textures Library

**NOTICE: This repo contains Minecraft Bedrock default vanilla textures library as of version 1.18.0.**

This repository is intended to help you navigate the Minecraft Bedrock default vanilla textures library.

## Usage

**NOTICE:** GitHub limits file shown inside a directory to 1000 files, while some directories in this repository contains more than 1000 files. To work around this restriction, you need to clone this repository with the following command (without the `$` symbol):
```sh
$ git clone --depth 1 --branch master https://github.com/KygekDev/default-textures
```
If you don't have Git installed, you may try downloading and installing Git [here](https://git-scm.com/downloads).

---

If you want to use the vanilla Minecraft Bedrock textures for plugins (PocketMine-MP),

1. the directory separator should be a forward slash (/),
2. don't include `https://github.com/KygekDev/default-textures/blob/master` and
3. don't include the `.png` file type.

**NOTE:** Textures should work even if the Minecraft server does not register or support some vanilla Minecraft items or blocks, because textures are rendered client-side, as long the textures remain unmodified by custom textures.

### Example:

If you want to use `https://github.com/KygekDev/default-textures/blob/master/textures/items/arrow.png`, you should use `textures/items/arrow` in your plugin config/script.

## Additional Notes

- The resource pack is always downloaded from the [official download link](https://aka.ms/resourcepacktemplate) from Microsoft.
- If you have any questions or suggestions, please join the [KygekDev Community Discord server](https://discord.gg/TstDS9jZf7).
- We are not affiliated with Mojang and Minecraft in any way. Their Products, Brands and Assets are trademarks and copyrights of their respective publisher and its licensors.
