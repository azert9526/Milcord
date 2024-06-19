# Milcord
## Building from Source

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/azert9526/Milcord
cd Vesktop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```
