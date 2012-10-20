# Mac OS(10.6 ~) 自分用設定

## インストールしておくもの:
* mi.app(ミミカキエディット)
* BetterTouchTool
* KeyRemap4MacBook
* PCKeyboardHack

## 操作手順

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
/Library/Service に(~/Library/Service ではない！ルートのほう)、添付のWordService.serviceを移動して、ログアウトしてログイン。その後、添付した画像のように、システム環境設定→キーボード→キーボードショートカット→サービスでLong DateとTimeを割り当てる。
