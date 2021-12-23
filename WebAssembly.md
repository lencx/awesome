# WebAssembly

## Guide

- [MDN WebAssembly](https://developer.mozilla.org/zh-CN/docs/WebAssembly)
- [[Mozilla Hacks] WebAssembly Articles](https://hacks.mozilla.org/category/webassembly/) - Articles posted in WebAssembly
- [webassembly.org](https://webassembly.org) - WebAssembly (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine. Wasm is designed as a portable compilation target for programming languages, enabling deployment on the web for client and server applications.
- [Bytecode Alliance](https://bytecodealliance.org/articles/) - The Bytecode Alliance is a nonprofit organization dedicated to creating secure new software foundations, building on standards such as WebAssembly and WebAssembly System Interface (WASI).
- [WebAssembly Weekly](https://wasmweekly.news) - A weekly newsletter for keeping on top of what's new in the world of WebAssembly, with tutorials, examples, articles, and more.
- [Awesome Wasm](https://github.com/mbasso/awesome-wasm) - Curated list of awesome things regarding WebAssembly (wasm) ecosystem.
- [Wasm By Example](https://wasmbyexample.dev/home.en-us.html) - A hands-on introduction into WebAssembly ( Wasm ). Containing simple wasm examples and wasm tutorials on how to implement concepts and various tasks using WebAssembly.

## Languages

- [Awesome WebAssembly Languages](https://github.com/appcypher/awesome-wasm-langs) - A curated list of languages that compile directly to or have their VMs in WebAssembly
- [AssemblyScript](https://www.assemblyscript.org/) - A TypeScript-like language for WebAssembly.
- [Rust 🦀 and WebAssembly 🕸](https://rustwasm.github.io/docs/book) - This small book describes how to use Rust and WebAssembly together.

## WASI & VM & VDOM

- [wasmtime](https://github.com/bytecodealliance/wasmtime) - Standalone JIT-style runtime for WebAssembly, using Cranelift
- [Wasm3](https://github.com/wasm3/wasm3) - The fastest WebAssembly interpreter, and the most universal runtime
- [Wasmer](https://github.com/wasmerio/wasmer) - The leading WebAssembly Runtime supporting WASI and Emscripten.
- [Lucet](https://github.com/bytecodealliance/lucet) - Lucet, the Sandboxing WebAssembly Compiler.
- [WasmEdge](https://github.com/WasmEdge/WasmEdge) - WasmEdge Runtime is a high-performance, extensible, and hardware optimized WebAssembly Virtual Machine for automotive, cloud, AI, and blockchain applications.
- [asm-dom](https://github.com/mbasso/asm-dom) - A minimal WebAssembly virtual DOM to build C++ SPA (Single page applications)

## Emulates

- [v86](https://github.com/copy/v86) - x86 virtualization in your browser, recompiling x86 to wasm on the fly


## Tools

- [wapm](https://wapm.io) - `WAPM` is the WebAssembly Package Manager.
- [trunk](https://github.com/thedodd/trunk) - Build, bundle & ship your Rust WASM application to the web.
- [wasm-tools](https://github.com/bytecodealliance/wasm-tools) - Rust tooling for low-level manipulation of WebAssembly modules.
- [wasm-pack](https://github.com/rustwasm/wasm-pack) - your favorite rust -> wasm workflow tool!

## Optimizing

- [Shrinking `.wasm` Code Size](https://rustwasm.github.io/book/reference/code-size.html)
  - [Binaryen](https://github.com/WebAssembly/binaryen) - Binaryen is a compiler and toolchain infrastructure library for WebAssembly, written in C++. It aims to make compiling to WebAssembly easy, fast, and effective.
  - [Twiggy](https://github.com/rustwasm/twiggy) - Twiggy is a code size profiler
- [Optimizing Code (`cpp`)](https://emscripten.org/docs/optimizing/Optimizing-Code.html)
- [Superoptimization of WebAssembly Bytecode](https://arxiv.org/pdf/2002.10213.pdf)

## Open Source

- [vite-plugin-rsw](https://github.com/lencx/vite-plugin-rsw) - wasm-pack plugin for Vite
- [rsw-node](https://github.com/lencx/rsw-node) - `wasm-pack build` executed in remote deployment
- [wasi-fs-access](https://github.com/GoogleChromeLabs/wasi-fs-access) - This is a demo shell powered by WebAssembly, WASI, Asyncify and File System Access API.
- [FFMPEG.WASM](https://ffmpegwasm.github.io) - ffmpeg.wasm is a pure WebAssembly / JavaScript port of FFmpeg. It enables video & audio record, convert and stream right inside browsers.
- [wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) - A WebAssembly CHIP-8 emulator written with Rust
- [NoteCalc](https://bbodi.github.io/notecalc3) -  is a handy notepad with a smart builtin calculator.
- [Graphite](https://github.com/GraphiteEditor/Graphite) - Powerful 2D vector and raster editing: procedural and nondestructive. (Photoshop + Illustrator + Houdini = Graphite)
- [Kalker/kalk](https://github.com/PaddiM8/kalker) - is a calculator with math syntax that supports user-defined variables and functions, complex numbers, and estimation of derivatives and integrals
- [wasmboy](https://github.com/torch2424/wasmboy) - Game Boy / Game Boy Color Emulator Library, written for WebAssembly using AssemblyScript. Demos built with Preact and Svelte.
- [Plotters](https://github.com/38/plotters) - A rust drawing library for high quality data plotting for both WASM and native, statically and realtimely
- [redshirt](https://github.com/tomaka/redshirt) - The redshirt operating system is an experiment to build some kind of operating-system-like environment where executables are all in Wasm and are loaded from an IPFS-like decentralized network.
- [Photon](https://github.com/silvia-odwyer/photon) - Rust/WebAssembly image processing library
- [markdown-wasm](https://github.com/rsms/markdown-wasm) - Markdown parser and HTML generator implemented in WebAssembly, based on md4c.
- [hash-wasm](https://github.com/Daninet/hash-wasm) - Hash-WASM is a lightning fast hash function library for browsers and Node.js. It is using hand-tuned WebAssembly binaries to calculate the hash faster than other libraries.
- [serde-wasm-bindgen](https://github.com/cloudflare/serde-wasm-bindgen) - Native integration of [Serde](https://serde.rs) with [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen)
- [sycamore](https://github.com/sycamore-rs/sycamore) - A reactive DOM library for Rust in WASM.
- [gumnut](https://github.com/samthor/gumnut) - JS parser in Web Assembly / C.
- [box2d-wasm](https://github.com/Birch-san/box2d-wasm) - Box2D physics engine compiled to WebAssembly. Supports TypeScript and ES modules.
- [TensorFlow.js](https://github.com/tensorflow/tfjs) - A WebGL accelerated JavaScript library for training and deploying ML models.

## Article

- [Photoshop's journey to the web](https://web.dev/ps-on-the-web/)
- [A vision for future Web Technologies — WASM & PWAs](https://medium.com/@alshdavid/a-vision-for-future-web-technologies-wasm-pwas-9f8c6e1fe6b0)
- [The Three Pillars of WebAssembly](https://thenewstack.io/the-three-pillars-of-webassembly/)
- [Why WebAssembly Frameworks Are the Future of the Web](https://www.cloudsavvyit.com/13696/why-webassembly-frameworks-are-the-future-of-the-web/)
- [WebAssembly入门](https://lencx.github.io/book/wasm/rust_wasm_frontend.html)
- [十年磨一剑，WebAssembly是如何诞生的？](https://www.yuque.com/kiwenlau/blog/zg3349)
- [The State of WebAssembly 2021](https://blog.scottlogic.com/2021/06/21/state-of-wasm.html)
- [Using WebAssembly threads from C, C++ and Rust](https://web.dev/webassembly-threads/)
- [Faster (and smaller) uploads in Discourse with Rust, WebAssembly and MozJPEG](https://blog.discourse.org/2021/07/faster-user-uploads-on-discourse-with-rust-webassembly-and-mozjpeg/)
- [WasmBook](https://wasmbook.com/) - Rick Battagline's WebAssembly Playground
- [Is WebAssembly magic performance pixie dust?](https://surma.dev/things/js-to-asc/)
- [WebAssembly Actors: From Cloud to Edge](https://www.edx.org/course/webassembly-actors-from-cloud-to-edge) - Embrace the actor model to build portable, secure, lightweight WebAssembly modules that thrive in the cloud, at the edge, and anywhere in between.
- [Learning WebAssembly Series](https://blog.ttulka.com/learning-webassembly-series) - A series of learning texts covering the first steps with WebAssembly for complete beginners.
- [In-browser transcoding of video files with FFmpeg and WebAssembly](https://blog.scottlogic.com/2020/11/23/ffmpeg-webassembly.html)
- [Standardizing WASI: A system interface to run WebAssembly outside the web](https://hacks.mozilla.org/2019/03/standardizing-wasi-a-webassembly-system-interface)
- [The WebAssembly App Gap](https://paulbutler.org/2020/the-webassembly-app-gap)
- [Why using WebAssembly and Rust together improves Node.js performance](https://developer.ibm.com/articles/why-webassembly-and-rust-together-improve-nodejs-performance)
- [[V8] WebAssembly compilation pipeline](https://v8.dev/docs/wasm-compilation-pipeline)
- [Optimizing WebAssembly Startup Time](https://pspdfkit.com/blog/2018/optimize-webassembly-startup-performance/)
- [Bringing You Up to Speed on How Compiling WebAssembly is Faster](https://www.cs.cornell.edu/courses/cs6120/2019fa/blog/wasm/)
- [Maybe you don't need Rust and WASM to speed up your JS](https://mrale.ph/blog/2018/02/03/maybe-you-dont-need-rust-to-speed-up-your-js.html#getting-the-code)
- [Using WebAssembly Written in Rust on the Server-Side](https://thenewstack.io/using-web-assembly-written-in-rust-on-the-server-side/)
- [The Pain of Debugging WebAssembly](https://thenewstack.io/the-pain-of-debugging-webassembly/)
- [KubeCon EU: WebAssembly Is More Than a JavaScript Replacement](https://thenewstack.io/kubecon-eu-why-webassembly-is-more-than-a-javascript-replacement/)
- [Why WebAssembly Modules Could Be the New de Facto Unit of Compute](https://thenewstack.io/why-webassembly-modules-could-be-the-new-de-facto-unit-of-compute/)
- [Aggregate streaming data in real-time with WebAssembly](https://www.infinyon.com/blog/2021/08/smartstream-aggregates/)
- [Full-stack Rust: A complete tutorial with examples](https://blog.logrocket.com/full-stack-rust-a-complete-tutorial-with-examples/)
