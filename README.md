# Mac OS(10.6 ~) 自分用設定

## インストールしておくもの:
* Firefox
* Google Japanese Input
* mi.app(ミミカキエディット)
* iTerm2
* DrasticInputSourceStatus 改造版
* BetterTouchTool
* KeyRemap4MacBook
* PCKeyboardHack

## 操作手順

### TrackPad(Apple標準）
「システム環境設定」→「トラックパッド」の設定を、このレポジトリのTrackPadSettingsと一致させる。

### Firefox
Sync機能を使って、addonなど一括同期。その後の設定は面倒だけどやらざるを得ない。  
また、アドレスバーに「about:config」と打鍵し、browser.search.openintab をtrueに。

### DrasticInputSourceStatus 改造版
自分が作ったものをインストール。Google Japanese Inputをインストールしてから設定しないと若干面倒。
- Start At Login, Hide icon in Dock にチェック

### iTerm2
Preferences->Keys->Global Shortcut Keysで、Command+[ -> Previous Tab, Command+] -> Next Tab に割り当てる。

### BetterTouchTool
- アプリを開いて、このディレクトリに保存されている、better_touch_tool.bkをimport
- BetterTouchTool の Preference -> Basic Settings で Launch BetterTouchTool on start up にチェック
- ↑同様に、Enable automatic update checking を切る

### KeyRemap4MacBook
アプリを開いて、Misc & Uninstall の Open private.xml をクリックするとFinderが開く。そこにあるprivate.xmlを、KR4MB-settingディレクトリに入っている、private.xmlで上書きして、アプリに戻ってChange Keyの項目で、KR4MB-settingディレクトリの画像にあるように設定。  
さらに、KeyRemap4MacBOokのKeyRepeatの[Key Repeat] Initial Wait を 250, Wait を 40に設定。

### PCKeyBoardHack
アプリを開いて、画像のように設定。

### システム環境設定
添付した画像のように、システム環境設定→キーボード→修飾キー→CapsLockをアクション無しに設定。

### WordService
/Library/Service に(~/Library/Service ではない！ルートのほう)、添付のWordService.serviceを移動して(/Library/ServiceのServiceディレクトリが無ければ作る)、ログアウトしてログイン。その後、添付した画像のように、システム環境設定→キーボード→キーボードショートカット→サービスでLong DateとTimeを割り当てる。

### PHP
php.iniを該当箇所に置く。パーミションは777でいいでしょう。。。ローカルだし。

### Netbeans
このディレクトリにある、kawa_netbeans_settings_*.zipを、Netbeansアプリを開いて、「環境設定」->下の方の「インポート」を選択して、この.zipを選択。
