# Rust xtensa freedesktop sdk extension

## Overview

This includes an experimental port of rust for xtensa architecture ([rust-xtensa](https://github.com/MabezDev/rust-xtensa)) and esp32 toolchain.

## Build

    flatpak-builder --user --install build-dir org.freedesktop.Sdk.Extension.rust-xtensa.yml

## Use with VS Code

    FLATPAK_ENABLE_SDK_EXT=rust-xtensa flatpak run com.visualstudio.code
