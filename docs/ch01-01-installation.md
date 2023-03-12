# インストール

**インストール方法を中心にmac向けにアレンジしています。**

## コンパイラ

C++ のコンパイラは多くのベンダが開発しています。
代表的なものには次のようなものがあります。

| コンパイラ | Linux              | macOS              | Windows            |
|------------|:------------------:|:------------------:|:------------------:|
| GCC        | :white_check_mark: | :white_check_mark: | ️:white_check_mark: |
| Clang      | :white_check_mark: | :white_check_mark: | :warning:          |
| Visual C++ |                    |                    | :white_check_mark: |

GCC は Linux をメインに使用されるコンパイラですが、
Linux 以外の主要なプラットフォームでも使用することができ、
一番実績のあるコンパイラです。
Clang は近年注目されているコンパイラで、
今後は GCC に取って代わる可能性があるコンパイラです。

本書では Windows 版の GCC をインストールします。
GCC のインストールには msys2 というツールを使用します。
msys2 は Linux で使用できるコマンドの一部を Windows に移植したツールセットです。

~~### msys2 のインストール~~
### ターミナルの起動

macの方はターミナルがあるので、msys2のインストールは不要です。ターミナルの場所はspotlight(画面右上の虫眼鏡マーク)から検索してください。

### GCC のインストール

まずはhomebrewを入れましょう。入れ方は[こちら](https://brew.sh/index_ja)

入っているかが不明な場合は

```
brew doctor
```
で確認できます。

gccは**mac** のターミナルを起動して下記コマンドを打ってインストールします。

```bash
brew install gcc
```
インストールの確認は

```
brew list | grep gcc
```

詳しくは[こちら](https://qiita.com/DaikiSuyama/items/09f5aa399aad37783146)

## IDE

C++ 用の IDE としては Visual Studio Code が人気です。
Visual Studio Code 自体はエディタなのですが、拡張機能を入れることで
C++ 向けに使用することもできます。

下記サイトより Visual Studio Code をインストールしてください。

```
https://code.visualstudio.com/
```

Visual Studio Code の拡張機能である [C/C++] もインストールします。
Visual Studio Code を起動した後、`command+Shift+X` を押すと
拡張機能のインストール画面に切り替わるので、
[C/C++] を検索してインストールしてください。

[C/C++]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools
