# GradientElement for GPUI

> 🌞🌞 We not need this, GPUI has it own gradient implementation.
>
> https://github.com/zed-industries/zed/blob/main/crates/gpui/examples/gradient.rs

This is a simple Element to render a gradient for GPUI.

The core implementation is based drawing the gradient into a bitmap img, and then use `cx.paint_image()` to render the image to the GPUI.

## Ranbow Gradient

<img width="912" alt="image" src="https://github.com/user-attachments/assets/5261fd6c-f666-4b94-b9ac-52f2d4e788dd">

## Development

```bash
cargo run --example hello_world
```
