# Blinky for BBC microbit v2 (nRF52833)

This contains a minimal rust application that lets the first LED of the LED matrix blink.

## Install requirement
```
rustup target add thumbv7em-none-eabihf
cargo binstall probe-rs-tools
```

## Flashing the microcontroller
```
cargo embed
```
