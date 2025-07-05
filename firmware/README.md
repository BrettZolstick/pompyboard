# PompyBoard Firmware

## Must read

- https://probe.rs
- https://github.com/stm32-rs/stm32f4xx-hal
- https://github.com/rust-embedded/cortex-m
- https://defmt.ferrous-systems.com
- https://docs.rust-embedded.org/book

## Setting up

1. [Setup devenv](https://devenv.sh/getting-started)
   - we use this to manage tooling (i.e. no [rustup](https://rustup.rs/))

## Commands

### Flash and run

See https://probe.rs/docs/tools/probe-rs/ for more information.

```bash
cargo run --release
```

### List USB devices

```bash
lsusb
```

### Dump USB device HID report descriptor

```bash
usbhid-dump -m 1209:02d7 # (vid:pid)
```
