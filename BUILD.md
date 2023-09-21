# Building modpack from source
Dependencies (install these):
- Java JDK (almost certainly already installed if you have Minecraft installed, required to zip shaderpacks)
- [nodejs](https://nodejs.org/) (required for zx)
- [zx](https://github.com/google/zx) (used for build scripts)
- [packwiz](https://github.com/packwiz/packwiz) (used to manage modpack/generate Modrinth/Curseforge-compatible modpacks, place executable in this folder)
- [packsquash](https://github.com/ComunidadAylas/PackSquash) (used to build resourcepack and protect included assets)

Once all dependcies are installed, you can build the modpack with `zx scripts/build.mjs`. The built modpacks will be in the `dist` folder.