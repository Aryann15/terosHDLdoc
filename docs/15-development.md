---
description: Development
id: development
---

# Development: backend

Colibri is a TypeScript library to work with HDL (VHDL, Verilog and SV). It's the back-end of TerosHDL, but also it can be used as part of other programs. Features:

- State machine parser.
- Schematic images.
- Documenter: it extracts the comments in the code and generates the documentation in HTML or MarkDown.
- Error linter: GHDL, Icarus, Verilator, Verible...
- Style checking: Verible.
- Code formatting.
- Code templates.
- Hierarchy images.
- Dependencies images.
- Project manager: simulations, compilations...


## Local Development Setup

 To set up the project for local development, follow these steps:
1. Clone the repository to your local machine.
2. Set up the frontend and colibri backend:
   ```
   cd packages/teroshdl/
   npm install
   cd ../colibri
   npm install
   npm run-script build
   ```
3. Open the project in Visual Studio Code
4. Debug the extension:
Press F5 and start the development environment for the extension in VS Code.


 ## Architecture

<p align="center">

![Colibri architecture](/img/colibri.png) 
</p>

 ## Documentation

[Check the API documentation](https://terostechnology.github.io/colibri/api-doc/index.html)
