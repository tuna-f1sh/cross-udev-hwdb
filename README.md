# Works

`cross build --locked --release --all-features --target=x86_64-unknown-linux-gnu --target-dir target`

## Patch Fixes:

```
libudev-sys = { git = "https://github.com/Emilgardis/libudev-sys", branch = "fix-cross-compilation" }
```

# Fails

`cross build --locked --release --all-features --target=aarch64-unknown-linux-gnu --target-dir target`

## Patch Fixes:

```
libudev-sys = { git = "https://github.com/Emilgardis/libudev-sys", branch = "fix-cross-compilation" }
```
