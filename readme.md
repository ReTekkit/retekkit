# ReTekkit

A modern modpack aiming to recreate and update Tekkit.

**Important Note:** ReTekkit is *not* affiliated with Tekkit nor Technic!

ReTekkit is still in heavy development. There are many mods that need to be
recreated and reimagined.

For the fun development information, see [ReTekkit/doc](https://github.com/ReTekkit/doc).

## Developers

To download the pack for development purposes, I first recommend these programs:

- Git (if you are a developer then you probably already have this installed :p)
- [Packwiz](https://packwiz.infra.link/) (add, update, or remove mods)
- [Prism Launcher](https://prismlauncher.org/) (for testing and playing the pack)
- VSCode, VSCodium, or any other IDE (to edit configs, tweak recipes, etc)

To set up a development environment:

1. `git clone` this repo somewhere.
2. Open Prism Launcher and create a new instance (name does not matter but I
just use `ReTekkit-dev`).
	- This instance should be Minecraft version 1.21.1 and NeoForge on
	whatever version ReTekkit is using. This can be found in `pack.toml`.
3. Download the latest `packwiz-installer-bootstrap.jar` from
[here](https://github.com/packwiz/packwiz-installer-bootstrap/releases) and put
it in the instance's folder.
	- This is used to automatically update the pack when you make a change
4. Then, in your instance's settings, set the pre-launch command to this:
`"$INST_JAVA" -jar packwiz-installer-bootstrap.jar http://localhost:8080/pack.toml`

> See [this](https://packwiz.infra.link/tutorials/installing/packwiz-installer/)
for more information about `packwiz-installer`.
