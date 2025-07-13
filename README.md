# Blinky for BBC microbit v2 (nRF52833)

This contains a minimal rust application that lets the first LED of the LED matrix blink.

## Install requirements
```
rustup target add thumbv7em-none-eabihf
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/probe-rs/probe-rs/releases/latest/download/probe-rs-tools-installer.sh | sh
```

## Flashing the microcontroller
```
cargo embed
```
