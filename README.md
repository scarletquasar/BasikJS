# BasikJS

BasikJS is a ***TypeScript*** runtime written in modern .NET, focused on fault tolerance, DevOps, server management and automation. It aims to provide a full set of features to ease pipeline tasks profiting from high parallelism and optimal usage of the device resources while keeping the simplicity and usability of JavaScript/TypeScript. Basik counts with its own spec and set of carefully selected functionalities to provide an optimal experience.

> *In development*

## Architecture Sketches

### External tool usage

- [Vite] -> [Pre-compiling?]
- [Jint] -> [JavaScript interpreter]
- [CliWrap] -> [Cli operations]
- [Spectre] -> [Cli beautify/utility]

### Worker manual garbage collection

- [Front worker] -> [Default JS Garbage collection]
- [IO worker] -> [Manual Garbage collection through free api?]
- [Interop worker] -> [Manual Garbage collection through free api?]
