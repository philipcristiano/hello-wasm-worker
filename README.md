# Hello WASM Worker

Testing out [WASM Workers](https://workers.wasmlabs.dev) with a Nix Flake install of rust utils


```
# TODO: Install wws from not curl-bash
curl -fsSL https://workers.wasmlabs.dev/install | bash

cargo build --release --target wasm32-wasi
wws target/wasm32-wasi/release/
```
