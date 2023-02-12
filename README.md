# Triangle Rust WASM

In this project I used the
[tutorial](https://rust-tutorials.github.io/triangle-from-scratch/web_stuff/web_gl_with_bare_wasm.html)
to display a triangle from scratch in WebAssembly.

## Quickstart

First you will need to add WASM as a target.

```console
rustup target add wasm32-unknown-unknown
```

Build the wasm module and start a http server locally.

```console
cargo build --release --target wasm32-unknown-unknown
python3 -m http.server
```

Then you can access the index.html page at `localhost:8000`
