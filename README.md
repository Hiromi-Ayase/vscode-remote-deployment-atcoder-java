# Visual Studio Code の AtCoder (Java)用 Remote Development コンテナ サンプル

これは AtCoder の問題を Java で書く時に Visual Studio Code の新機能 **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** を使ってコーディングするためのものです。

> **Note** 現在 Remote Deployment extensions の機能は **[ Visual Studio Code Insiders](http://code.visualstudio.com/insiders)** のみ対応です。

## 何がうれしいのか

Java の開発環境がコンテナの中で勝手に構築されます。他の言語も Microsoft のサンプルを似たような感じで修正すれば 競技プログラミング用に作成できるはずです。

```
git clone https://github.com/Microsoft/vscode-remote-try-node
git clone https://github.com/Microsoft/vscode-remote-try-python
git clone https://github.com/Microsoft/vscode-remote-try-go
git clone https://github.com/Microsoft/vscode-remote-try-java
git clone https://github.com/Microsoft/vscode-remote-try-dotnetcore
git clone https://github.com/Microsoft/vscode-remote-try-php
git clone https://github.com/Microsoft/vscode-remote-try-rust
git clone https://github.com/Microsoft/vscode-remote-try-cpp
```

#＃ インストール方法

> **Note** Windows の場合はDocker for Desktopを動かすために **[Hyper-V の有効化](https://docs.microsoft.com/ja-jp/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)** を事前に設定しておく必要があります。

1. Docker(Linux) または Docker Desktop for Windows/Mac をインストールします。
2. Docker Desktop for Windows/Mac の場合は **[Getting Started](https://code.visualstudio.com/docs/remote/containers#_getting-started)** のようにタスクトレイからCドライブの共有ドライブの設定をする必要があります。
3. Visual Studio Code の拡張機能から **[Remote Deployment](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)** をインストールします。
4. clone したコードをフォルダごと Visual Studio Code で開きます。
5. 拡張機能がインストールできると、Visual Studio Code の左下に左色のボタンが現れますので、それをクリックするとコンテナで開くモードになります。この状態になると、Java の実行環境がある状態になっています。
6. Main.java にコードを書き、F5 でローカル実行等をします。
7. AC して Red Coder になります。


## License

Licensed under the MIT License. See LICENSE in the project root for license information.
