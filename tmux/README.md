# TMUX config

1. Add the tmux configuration file to your home `$XDG_CONFIG_HOME` directory.

2. This tmux config relies on plugins installed by tpm

```bash
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

3. Source file to apply changes

```bash
$ tmux source ~/.tmux.conf`
```

4. Install plugins with tpm

```bash
# start tmux
$ tmux

# install plugins
<prefix> I
```

