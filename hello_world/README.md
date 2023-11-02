# rust_practice

## hello_worldプロジェクトの生成から実行
- 生成
```shell
# cargoのインストール
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
rustup update
# hello_worldプロジェクトの生成
cargo new hello_world
```

- 実行
```shell
# 実行1
cargo build
./target/debug/hello_world
# 実行2
cargo run
```
 
## 参考
公式: https://doc.rust-lang.org/cargo/getting-started/index.html
公式: https://www.rust-lang.org/ja/learn
公式翻訳(非公式): https://doc.rust-jp.rs/book-ja/