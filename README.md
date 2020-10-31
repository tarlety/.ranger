.ranger
===

This is Ranger config files located at `~/.config/ranger`.

## What does .ranger provide

- sensible defaults: vcs aware
- preflight dependencies (for Ubuntu distro)
- colorscheme: default
- preview image as asciiart
- plugins: autojump, devicons

## Screenshots

- How image preview looks like

    <img src="https://i.imgur.com/wWp8vp6.png" alt="drawing" width="480"/>

## How to install

1. Do git clone to your ranger configure folder.

```
$ git clone https://github.com/t16ing/.ranger ~/.config/ranger
```

2. Execute the preflight.sh to install ranger and dependencies.

```
$ cd ~/.config/rander
$ ./preflight.sh
```

3. Run ranger.

```
$ ranger
```

## Licence

MIT
