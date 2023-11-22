# Works

`cross build --locked --release --all-features --target=x86_64-unknown-linux-gnu --target-dir target`

## Patch Breaks:

```
libudev-sys = { git = "https://github.com/Emilgardis/libudev-sys", branch = "fix-cross-compilation" }
```

## Patch Fixes:

```
libudev-sys = { git = "https://github.com/tuna-f1sh/libudev-sys/", rev = "7a94a7bbfd6eca85ab1be6cd53d25f337fbe15db" }
```

# Fails

`cross build --locked --release --all-features --target=aarch64-unknown-linux-gnu --target-dir target`

## Patch Fixes:

```
libudev-sys = { git = "https://github.com/Emilgardis/libudev-sys", branch = "fix-cross-compilation" }
```
