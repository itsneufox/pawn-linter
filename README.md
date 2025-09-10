# PAWN Linter Addon

A PAWN code linter and formatter addon for pawnctl.

## Features

- **Linting**: Check PAWN code for common issues and style violations
- **Formatting**: Automatically format PAWN code for consistency
- **Build Integration**: Automatically lint code before and after builds
- **Custom Commands**: Use `pawnctl addons run lint` and `pawnctl addons run format`

## Installation

```bash
pawnctl addons install @community/pawn-linter
```

Or install from GitHub:

```bash
pawnctl addons install https://github.com/itsneufox/pawn-linter-addon
```

## Usage

### Lint PAWN files

```bash
pawnctl addons run lint file1.pwn file2.pwn
```

### Format PAWN files

```bash
pawnctl addons run format file1.pwn file2.pwn
```

### Build Integration

The addon automatically runs during the build process:

- **Pre-build**: Lints code before compilation
- **Post-build**: Validates build output

## Commands

- `lint` - Lint PAWN code files
- `format` - Format PAWN code files

## License

MIT
