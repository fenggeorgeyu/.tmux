`.tmux` configuration
=====================

## Installation

```shell
cd
git clone https://github.com/fenggeorgeyu/.tmux.git
ln -s -f .tmux/.tmux.conf
ln -s -f .tmux/.tmux.conf.local .
```

## copy to system clip board (Mac OSX)

install `reattach-to-user-namespace` first

	brew install reattach-to-user-namespace

in `tmux` use `Ctrl+[` to enter copy mode, you may use `SPACE` to enable selection after move to the zone or you may use mouse to select and the content will be copied to system clipboard


