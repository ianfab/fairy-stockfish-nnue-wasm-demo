# fairy-stockfish-nnue.wasm demo

Demo frontend for [fairy-stockfish-nnue.wasm](https://github.com/ianfab/fairy-stockfish.wasm)

## Development

```
npm install

# Or use a local version of stockfish-nnue.wasm by e.g.
npm install fairy-stockfish-nnue.wasm@../fairy-stockfish-nnue-wasm-v2/src/emscripten/public

# Link node_modules/fairy-stockfish-nnue.wasm to public/lib
npm run link-lib

npm run serve
```

## Deployment

```
# Copy node_modules/fairy-stockfish-nnue.wasm to public/lib
npm run copy-lib

# Run vercel cli
npm run deploy
```
