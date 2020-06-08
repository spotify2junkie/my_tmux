## Installation

Requirements:

- tmux 
- Oh-my-tmux
- tmux-resurrect 

To Install all dependencies:

```bash
brew install tmux # 安装tmux 
cd
git clone https://github.com/gpakosz/.tmux.git
mkdir .tmux_resurrect
git clone https://github.com/tmux-plugins/tmux-resurrect ~/.tmux_resurrect
git clone https://github.com/spotify2junkie/my_tmux && cd my_tmux
cp .tmux.conf* ~/
```

