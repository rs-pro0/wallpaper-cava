Wallpaper CAVA
==============

Display [cava](https://github.com/karlstav/cava) on top of your wallpaper.
Built by [rs-pro0](https://github.com/rs-pro0) with big(uncomfortably big for me, ngl) help from ChatGPT.
Built using [wayland-rs](https://github.com/Smithay/wayland-rs), [smithay-client-toolkit](https://github.com/Smithay/client-toolkit), [khronos-egl(for Rust)](https://github.com/timothee-haudebourg/khronos-egl), and [gl-rs](https://github.com/brendanzab/gl-rs).

Building
------------

1. Clone this repo.
2. Clone [wayland-rs](https://github.com/Smithay/wayland-rs) into "wayland-rs" directory inside of this repo directory.
3. Build using Cargo: `cargo build --release`.
4. Ensure you have [cava](https://github.com/karlstav/cava) installed.
5. You can run `target/release/wallpaper-cava`.
