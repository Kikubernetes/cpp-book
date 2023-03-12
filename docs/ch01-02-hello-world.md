# Hello, World!

mac user向けにアレンジしています。たった今cを始めたど初心者なので間違いがあればご指摘ください。

Visual Studio Code 上で `main.cc` というファイルを作成して
下記のようなソースコードを作成します。

!!! example "main.cc"
    ```cpp linenums="1"
    #include <iostream>

    int main() {
        std::cout << "Hello, World!" << std::endl;

        return 0;
    }
    ```

*mac* のターミナルを起動して下記コマンドを打ってコンパイルします。

```bash
$ g++ -std=c++11 main.cc
```

*成功すると `a.out` というファイルができていると思います。*

これが実行ファイルになるので、実行すると `Hello, World!` という
メッセージが表示されます。

```bash
$ ./a.out
Hello, World!
```
