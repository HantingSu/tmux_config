# my tmux config

## 第一次使用
第一次使用時，需要先建立一個.tmux的檔案,你可以使用以下指令將tmux下載至你的電腦並配置
1.  首先先將我的專案clone下來
```
git clone git@github.com:HantingSu/tmux_config.git
``` bash
2. 然後創立.tmux的目錄，並執行以下指令
``` bash
mkdir ~/.tmux
cd ~/.tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
cp ~/tmux_config/.tmux.conf
tmux source ~/.tmux.conf
```

## 第N次使用
當你已經將這個tmux config設定過，你之後只需要使用以下指令，就可以再將你的新設定relode進去
```
C-b + r
````

然後如果要儲存就打
```
prefix+ctrl+s #儲存
prefix+ctrl+l #載入
```


