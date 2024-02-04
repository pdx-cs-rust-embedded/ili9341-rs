# `ili9341`

> A platform agnostic driver to interface with the ILI9341 (and ILI9340C) TFT
> LCD display

## This fork

This is my (Bart Massey) fork of Yuri Iozzelli's ILI9341
display chip driver. I made some changes to make this work
with the `microbit-v2` crate and some generalizations for
the display I had. Thanks to Yuri for making this.

The rest of this README is Yuri's.

## What works

- Putting pixels on the screen
- Change the screen orientation
- Hardware scrolling
- Compatible with [embedded-graphics](https://docs.rs/embedded-graphics)

## TODO

- [ ] Expose more configuration options
- [ ] Read video memory
- [ ] DMA API
- ???

## Examples

SOON

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the
work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any
additional terms or conditions.
