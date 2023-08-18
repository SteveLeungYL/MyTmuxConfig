# MyTmuxConfig

My tmux configuration.

### Custom keymappings:

```
# Custom ones
Ctrl-<h,l>: Switch panel in the same window.
Shift-Option-<h,l>: Switch window in the same session.

# Default ones
Ctrl + b + %: Split pane vertically.
Ctrl + b + ": Split pane horizontally.
Ctrl + b + x: Close the current pane.
```

### Setup

```bash
# Install tmux
sudo apt install tmux
# Install TPM Plugin Manager.
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# Copy the current config to the user directory.
cp ./tmux.conf ~/.tmux.conf
# Reload the tmux env
# Go to one tmux env.
tmux new-session -s test
tmux source ~/.tmux.conf
<Ctrl-b> + I # Type Control-b (tmux-prefix), followed by capital I to install the Plugin.
```
