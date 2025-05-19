# Installation

First, clone the RPL repository `git clone https://github.com/RPL-Toolchain/RPL.git && cd RPL`.

Then, use `cargo install --path .` in current directory to install RPL as a cargo subcommand.

Then, use `cargo +nightly-2025-02-14 rpl` to run RPL in your own repository to detect errors, where `+nightly-2025-02-14` is the current toolchain RPL is using. You may upate this argument if RPL is switched into a new toolchain.

> Every three months (or so), the toolchain will be updated to the latest nightly version. You can check the current toolchain by running `rustc -V` in the RPL repository.