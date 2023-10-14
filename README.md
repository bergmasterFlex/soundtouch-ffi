# soundtouch-ffi

[![Crates.io](https://img.shields.io/crates/v/soundtouch-ffi.svg)](https://crates.io/crates/soundtouch-ffi)
[![Documentation](https://docs.rs/soundtouch-ffi/badge.svg)](https://docs.rs/soundtouch-ffi/)

Rust bindings to the [SoundTouch](https://codeberg.org/soundtouch/soundtouch) C++ audio library.

There is already a [soundtouch-sys](https://crates.io/crates/soundtouch-sys) crate, but it hasn't been updated in 5 years and doesn't use static linking so I made this one.
This crate also includes other structs in the library such as `BPMDetect` and `FIFOSampleBuffer`, which the sys crate is missing. 

This is static only build with bundled version 2.3.2 (latest as of October 2023).

