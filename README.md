# Text Editor Configuration

> Sublime Text 3 text editor configuration

## Sublime from the Command Line

Sublime Text includes a command line tool, `subl`, to work with files from the command line.

### Initial Setup

To launch Sublime from command line make a symlink to `subl`. Assuming Sublime Text is in the Applications folder, and that a ~/bin directory is in your PATH, you can run:

```sh
ln -sv "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```

NOTE: To add a personal bin directory (~/bin):

```sh
mkdir -p ~/bin
```
