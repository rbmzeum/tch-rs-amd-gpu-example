### tch-rs for amd gpu

#### run example
RUSTFLAGS='-L /path/to/tch-rs/torch-sys/libtch/build' CARGO_MANIFEST_DIR=/path/to/tch-rs/torch-sys/libtch/build cargo run --release --bin basics

#### Requirements
archlinux 6.12.10-arch1-1
rocm 6.2.4
extra/python-pytorch-opt-rocm 2.5.1-7
rustc 1.85.0-nightly (9c707a8b7 2024-12-07)

