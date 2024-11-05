# WASM Game of Life

Conway's Game of Life implemented using WebAssembly and Rust.



https://github.com/user-attachments/assets/8c1ccf04-4966-48e4-807e-3663ae322005



## Getting Started
#### Prerequisites
- Latest Rust compiler
- Node v20
- [wasm-pack](https://github.com/rustwasm/wasm-pack)

#### Steps
1. Clone the repo
2. Run this command to build the WASM binary:
   ```bash
   wasm-pack build
   ```
3. `cd` to `www`, install dependencies, and run the dev server:
   ```bash
   cd www
   npm i
   npm run start
   ```
4. Access the app in http://localhost:8080

> [!note]
> If you encounter the following error:
> 
> <img width="483" alt="image" src="https://github.com/user-attachments/assets/f947af8f-4f17-4798-a7a7-eb7ccfac6e09">
>
> Run `export NODE_OPTIONS=--openssl-legacy-provider` and then run `npm run start` again.
