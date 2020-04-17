emcc -O3 -s WASM=1 -s EXTRA_EXPORTED_RUNTIME_METHODS='["cwrap"]'  -s ALLOW_MEMORY_GROWTH=1   -I libwebp     webp.c  -s ASSERTIONS=1   libwebp/src/{dec,dsp,demux,enc,mux,utils}/*.c
