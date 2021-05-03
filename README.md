# rust_hello_word
Rustでハローワールドするだけ

## rustインストールコマンド(for linux)
rustをインストール

```
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
```

> [Rustインストール]( https://doc.rust-jp.rs/book-ja/ch01-01-installation.html)

## cargoへPathを通す(fishシェルの場合)
シェルをfishに変更しているので、以下のコマンドを実行して
cargoのPathを通します

```
set -U fish_user_paths $fish_user_paths $HOME/.cargo/bin
```

> [Rustをインストール - macOS & fish-shellの場合](https://qiita.com/ledsun/items/9af5cb594b4f9b6c5523)

## hello word!
```
//プロジェクトの作成
cargo new hello_cargo --bin
//作成いたプロジェクトへ移動
cd hello_cargo
//プログラムの実行
cargo run
```