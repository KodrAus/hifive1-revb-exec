# Running Rust on a HiFive1 Rev B

This is a little toy repo for running some [Rust](https://rust-lang.org) code on a [RISC-V](https://riscv.org/)-based [HiFive1 Rev B](https://www.sifive.com/boards/hifive1-rev-b) board, originally adapted from [here](https://github.com/riscv-rust/riscv-rust-quickstart).

We can cross-compile for the board using one of the [pre-built toolchains from SiFive](https://www.sifive.com/software). The `riscv64-unknown-elf-gcc` binary just needs to be somewhere in your `PATH` and the `riscv32imac-unknown-none-elf` target installed.

I've been running my code using [SEGGER Embedded Studio](https://www.segger.com/products/development-tools/embedded-studio/). It's not exactly easy on the eyes but works on Windows :)
