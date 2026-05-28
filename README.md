# omarchy-dot
omarchyのためのdotfiles管理プロジェクト
極力いじらず退屈なテーマに収束させていくのが目標
## ツール
- stow
## 対象
- alacritty
- systemd
- tmux
- bash
- vim
- uwsm
- hypr
- waybar
## 使い方
~~~bash
$ cd ~/omarchy-dot
$ stow alacritty
$ stow systemd
$ stow tmux
$ stow bash
$ stow vim
$ stow uwsm
$ stow hypr
$ stow waybar

# All
$ stow --simulate */ #dry_run
$ stow */
~~~
# 注意
- systemdはenableせよ。user側で動かすように
- 初回では既存ファイルが被りwarningが出るので事前にバックアップを取得する形で対応せよ
