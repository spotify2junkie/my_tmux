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
git clone https://github.com/spotify2junkie/my_tmux_conf && cd my_tmux_conf
# sed 命令可直接跳过;如果你想替换左下角天气城市 , city_name 写拼音或者airport_code
sed -i '' 's/hangzhou/city_name/g' .tmux.conf.local 
mv .tmux.conf* ~/.tmux
```

