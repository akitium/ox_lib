# ox_lib - Security Enhanced Fork

A security-enhanced fork of the ox_lib FiveM library with critical exploit fixes.

## Security Improvements

This fork addresses a critical security vulnerability in the progress system where malicious actors could exploit prop spawning to crash other players. The fix includes:

- Prop spawn rate limiting per player
- Blacklist for problematic prop models
- Enhanced validation and logging for exploit detection
- Automatic prop cleanup to prevent accumulation

## Original Project

This is a fork of [overextended/ox_lib](https://github.com/overextended/ox_lib) (archived).

The original project provided a comprehensive FiveM library implementing reusable modules, methods, and UI elements.

## Download

https://github.com/akitium/ox_lib/releases

## Documentation

Original documentation: https://overextended.dev/ox_lib

## Lua Language Server

- Install [Lua Language Server](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) to ease development with annotations, type checking, diagnostics, and more.
- Install [cfxlua-vscode](https://marketplace.visualstudio.com/items?itemName=overextended.cfxlua-vscode) to add natives and cfxlua runtime declarations to LLS.
- You can load ox_lib into your global development environment by modifying workspace/user settings "Lua.workspace.library" with the resource path.

## Changes from Original

- Fixed prop spam exploit in progress system
- Added security controls for prop spawning
- Enhanced logging for security monitoring

## License

This project maintains the original LGPL-3.0 license. See [LICENSE](./LICENSE) for details.

Original work Copyright (C) 2025 Linden and contributors
Security enhancements by akitium
