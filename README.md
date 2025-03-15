# Quicksilver Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to the **Quicksilver Project**! Quicksilver aims to provide a **native framework** for running **HTML, CSS, and TypeScript/JavaScript** applications on **Windows, macOS, and Linux**

> **Important**: Quicksilver is **not** a browser and don't use WebView.

## Overview
The **Quicksilver Project** will offer an extensive set of libraries designed to provide a **browser-like environment** for compatibility with existing **Web on Desktop (WoD)** environments. However, it is **not a browser**, and will not behave as one. The framework will enable dynamic compilation and offer Just-In-Time (JIT)-like features to ensure compatibility with modern desktop environments.

The system will have **dynamic compilation** and **Just-In-Time (JIT) compilation** for ensuring compatibility with modern applications.

### Key Features:
- **Direct compilation**: Compiles HTML, CSS, and TypeScript/JavaScript to binary bytecode.
- **Real-time compilation**: Automatically makes changes for an efficient development cycle.
- **Seamless integration**: Generates machine code that is compatible with existing ABIs.
- **Cross-platform support**: Can run on **macOS**, **Windows**, and **Linux**.

### Planned Features:
- **Direct Compilation**: Compiling HTML, CSS, and TypeScript directly into machine code, improving performance and reducing latency.
- **On-the-Fly Compilation**: Changes will be reflected in real-time, allowing for a more seamless development process.
- **ABI Compliance**: Will allow seamless integration with other C-based systems and applications.
- **Cross-Platform**: Will support **macOS**, **Windows**, and **Linux**, making Quicksilver a versatile solution for developers.

## Core Technologies

The **Quicksilver runtime** will be primarily written in **Rust** for safety and performance, with components also leveraging **TypeScript**/**JavaScript** for frontend integration and dynamic code compilation. A **C API** will be exposed for seamless integration with other systems.

- **Core Technology**: **Rust** will be used for safe, high-performance execution, while **C++** will power performance-critical operations.
- **API Support**: A **C API** will allow Quicksilver to interact with external systems and applications, providing easy integration.
- **WebAssembly (WASM)**: The combination of **Rust** and **TypeScript** will ensure a modern, high-performance development environment.

## Graphics Acceleration

Rendering will be a part of Quicksilver, taking advantage of **hardware acceleration** via **OpenGL**. This ensures smooth operation and makes implementation easier, with future support for **WebGL**.

### Planned Features:
- **TypeScript/JavaScript library compatibility**: Utilize a lot of the same code developed previously.
- **OpenGL integration**: Will allow integration with OpenGL for optimal rendering performance.
- **WebGL support**: Will enable graphical applications to take advantage of WebGL for complex rendering tasks.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

Thank you for being part of the **Quicksilver Project**!
