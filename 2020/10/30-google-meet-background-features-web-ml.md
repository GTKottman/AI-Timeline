# Google Meet background blur and replacement run in the browser with web ML

- **Date:** 2020-10-30
- **Who:** Google Research (Tingbo Hou, Tyler Mullen)
- **Type:** product

Google Research described how Meet's background blur and replacement run entirely in the browser, with no extra software, using MediaPipe segmentation models compiled to WebAssembly and rendered with WebGL2. The team credited Chrome 84's WebAssembly SIMD support with more than a 2x speed-up. It showed that real-time person segmentation could run on ordinary laptop CPUs in a mainstream video product.

## Sources
- https://research.google/blog/background-features-in-google-meet-powered-by-web-ml/
