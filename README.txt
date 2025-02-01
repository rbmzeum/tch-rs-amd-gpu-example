### tch-rs for amd gpu

#### install

git clone git@github.com:rbmzeum/tch-rs-amd-gpu-example.git
cd tch-rs-amd-gpu-example
git rm tch-rs
git clone git@github.com:rbmzeum/tch-rs-amd-gpu.git tch-rs
cd tch-rs
git checkout tch-rs-amd-gpu
cd ..

#### run example
RUSTFLAGS='-L /path/to/tch-rs/torch-sys/libtch/build' CARGO_MANIFEST_DIR=/path/to/tch-rs/torch-sys/libtch/build cargo run --release --bin basics

#### Requirements
archlinux 6.12.10-arch1-1
rocm 6.2.4
extra/python-pytorch-opt-rocm 2.5.1-7
rustc 1.85.0-nightly (9c707a8b7 2024-12-07)

and https://github.com/rbmzeum/tch-rs-amd-gpu/tree/tch-rs-amd-gpu
