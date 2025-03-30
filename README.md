# TinyPNG-WASM

This is a PNG image compressor that works directly in the browser, built using WebAssembly (WASM). It leverages powerful image processing libraries to provide efficient compression while maintaining image quality.

---

## Features  
- **Browser-based** PNG compression using WebAssembly  
- **Fast and efficient** compression powered by `libimagequant`  
- **Built with modern libraries** such as `libpng`, `zlib`, and `libimagequant`  
- **Optimized for performance** using C++ and WebAssembly  

---

## Libraries Used  
The following libraries are integrated into the project for efficient image compression:  
- [`libimagequant`](https://pngquant.org/lib/) - High-quality palette-based image quantization  
- [`libpng`](http://www.libpng.org/pub/png/libpng.html) - PNG file format handling  
- [`zlib`](https://zlib.net/) - Compression library for lossless data  

---

## Building the Project  

### Prerequisites  
Before building the project, ensure you have the following dependencies installed:  
- **Git**  (for cloning the repository)  
- **Emscripten** (for compiling C++ to WebAssembly)  
- **WebAssembly Toolchain** (for linking and optimization)  
- **CMake** (for project configuration and building)  

###  Clone the Repository  
```sh
git clone --recursive <repo-url>
cd TinyPNG-WASM
