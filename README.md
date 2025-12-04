# Scoop Bucket for duobolt

Fast duplicate file finder using BLAKE3 hashing (Rust CLI).

## Installation

```powershell
scoop bucket add duobolt https://github.com/rnine/scoop-duobolt
scoop install duobolt
```

## Usage

```powershell
duobolt-cli <directory...> [options]
duobolt-cli C:\Users\you\Documents --ignore-system-files --output=json
duobolt-cli --help
```

## Documentation

https://duobolt.app/cli-usage/
