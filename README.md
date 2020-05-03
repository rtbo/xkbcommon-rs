# xkbcommon-rs

xkbcommon-rs is a set of bindings and safe wrappers for [libxkbcommon](http://xkbcommon.org/).

For use with wayland:
```toml
[dependencies]
xkbcommon = { version = "0.5", features = ["wayland"] }
```
For use with X11:
```toml
[dependencies]
xkbcommon = { version = "0.5", features = ["x11"] }
```

# documentation

https://rtbo.github.io/xkbcommon-rs/xkbcommon


# example

Living example for X11 here:
https://github.com/rtbo/toy_xcb/blob/master/src/keyboard.rs
