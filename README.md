# MufiZ Standard Library

Standard library for the [MufiZ](https://github.com/mustafif/MufiZ) programming language.

## Modules

- **math** - Mathematical functions (sqrt, abs, sin, cos, etc.)
- **types** - Type inspection and type utilities
- **io** - Input/output operations
- **collections** - Array, map, and collection operations
- **matrix** - Linear algebra and matrix operations
- **json** - JSON parsing and serialization
- **serde** - Serialization framework
  - **serde_json** - JSON serialization
  - **serde_toml** - TOML serialization
  - **serde_yaml** - YAML serialization
- **network** - Network operations and sockets
- **fs** - File system operations
- **time** - Time and date functions
- **utils** - Utility functions

## Version

**0.1.0** - Initial release with all core stdlib modules

## Usage

This library is a dependency of the MufiZ compiler. To use stdlib functions in MufiZ code:

```mufi
// All functions are automatically available
var result = sqrt(16.0)      // 4.0
var abs_val = abs(-5)        // 5
```

## Development

This repository contains the standard library source code for MufiZ. To modify or extend the stdlib:

1. Clone this repository
2. Edit the desired `.zig` file in `src/`
3. Test changes by building the MufiZ compiler with the local stdlib path in `build.zig.zon`

## Building

```bash
zig build
```

## License

See LICENSE file in the MufiZ repository.

## Contributing

Contributions to the stdlib are welcome! Please submit pull requests or issues to the [MufiZ repository](https://github.com/mustafif/MufiZ).
