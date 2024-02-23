# DiscWars

DiscWars is a game that is inspired by the movie Tron. The game is a 2D game where the player controls a disc and tries to hit the other player with it. The game is made in Unity and is a school project.

## Git LFS

Ensure you have git lfs installed on your system. You can download it from [here](https://git-lfs.github.com/)

Run the following command to install git lfs

```bash
git lfs install
```

Test that git lfs is installed by running the following command

```bash
git lfs version
```

## Git hooks

Ensure the local project uses the .githooks folder

```bash
git config --local core.hooksPath .githooks/
```

If on MacOS or Linux, make sure the hooks are executable

```bash
chmod +x .githooks/*
```
