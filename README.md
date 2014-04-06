MacBook Setup For Delevopers
========
## Over View
新しいMacBookを購入した際、イチからセットアップするのってすごい大変。  
そこで、簡単に開発に必要なツール類を``` brew bundle```コマンドのみで実行することが出来ます。

Brewfile作成のため、こちらのサイトを参考にさせて頂きました。  
[Mac OSX をクリーンインストールしてからの環境構築メモ](http://www.1x1.jp/blog/2014/04/how-to-setup-application-on-osx.html?utm_content=buffera66ab&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer "Mac OSX をクリーンインストールしてからの環境構築メモ")

cloneしてご自身の用途に応じて書き換えて行って下さい！

## Getting Start
1. Install Homebrew  
  ```
  $ ruby -e &quot;$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)&quot;
  ```

2. Install Xcode  
AppStoreからDL  

3. Install Command Line Tool  
ここを参考に。[MavericksでCommand Line Tools for Xcodeをインストールする](http://qiita.com/3yatsu/items/47470091277d46f3fde2)

4. brew bundle  
以下のコマンドをTerminalで実行
  ```
  git clone git@github.com:Twinuma/brewfile.git
  cd brewfile
  brew bundle
  ```  



