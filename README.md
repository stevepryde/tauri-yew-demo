# Tauri + Yew Demo

This is a small demo to accompany the Tauri + Yew tutorial

https://dev.to/stevepryde/create-a-desktop-app-in-rust-using-tauri-and-yew-2bhe

## Installation

```shell
rustup target add wasm32-unknown-unknown
cargo install trunk
cargo install wasm-bindgen-cli
cargo install tauri-cli
```

## Dev Server 

After installing the above, you should be able to run it with

```shell
cargo tauri dev
```

## Building the app

You can do a release build with

```shell
cargo tauri build
```

This should create an installer in src-tauri/target/release/bundle/

## Further reading

Tauri: https://tauri.studio/en/docs/get-started/intro

Yew: https://yew.rs/docs/getting-started/introduction
