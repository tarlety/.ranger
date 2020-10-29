ranger.conf
===

## What is ranger.conf?

- default configurations: vcs aware, console image preview
- preflights for Ubuntu distro
- colorscheme: default
- preview image as asciicart
- plugins: autojump, devicons

## How to install

1. Do git clone to your ranger conf folder.

```
$ git clone --depth=1 https://github.com/tarlety/ranger.conf ~/.config/ranger
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
