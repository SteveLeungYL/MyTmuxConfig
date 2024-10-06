# MyTmuxConfig

My tmux configuration.

Using the on-my-tmux configuration. 

Download this repo, export the tmux local config to the user folder: 

```bash
cd
git clone git@github.com:SteveLeungYL/MyTmuxConfig.git .tmux_myconfig
ln -s -f .tmux_myconfig/.tmux.conf.local
ln -s -f .tmux_myconfig/.tmux.conf
```

If using Kitty as terminal emulator, add the following line to `kitty.conf`:
```
# mac navigation
map alt+left send_text all \x1b\x62
map alt+right send_text all \x1b\x66
```
