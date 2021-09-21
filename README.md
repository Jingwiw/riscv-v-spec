# riscv-v-spec
Working draft of the proposed RISC-V V vector extension.

[Version 1.0](https://github.com/riscv/riscv-v-spec/releases/tag/v1.0) has been frozen
and as of this writing is undergoing public review.

For the current stable release is
is a release candidate for the v1.0 frozen spec for public review - it is not
the v1.0 frozen spec.

The _previous_ stable releases are
[v1.0-rc](https://github.com/riscv/riscv-v-spec/releases/tag/v1.0-rc1),
[v0.10](https://github.com/riscv/riscv-v-spec/releases/tag/v0.10),
[v0.9](https://github.com/riscv/riscv-v-spec/releases/tag/0.9), and
[v0.8](https://github.com/riscv/riscv-v-spec/releases/tag/0.8).
Note, these previous releases are for development purposes only; changes have
been made prior to freezing.

The top level file is [v-spec.adoc](./v-spec.adoc)

Simply clicking on the file in the github repo viewer will render a usable
version as markdown.

For a better rendering, use "asciidoctor v-spec.adoc".

This work is licensed under a Creative Commons Attribution 4.0
International License. See the LICENSE file for details.

### Additional Resources

- The [Binutils port for v0.8](https://github.com/riscv/riscv-binutils-gdb/tree/rvv-0.8.x)
- The [GNU toolchain port for v0.8](https://github.com/riscv/riscv-gnu-toolchain/tree/rvv-0.8.x)
- The [Spike simulator](https://github.com/riscv/riscv-isa-sim) supports v0.10
- The [RISC-V Proxy Kernel](https://github.com/riscv/riscv-pk)
  (to be used with e.g. Spike) supports enabling v0.8 CPU support
  when compiled with a v0.8 capable GNU toolchain
- [riscvOVPsim](https://github.com/riscv/riscv-ovpsim) is a free
  RISC-V reference simulator that has support for v0.9, v0.8 and
  v0.7.1 (simulator is under a proprietary license, models are
  open source)

### Documentation generator

Requirements

`node v6+`

**Linux**: install using [nvm](https://github.com/creationix/nvm)

**macOS Homebrew**: `brew install node`

**macOS Macports**: `sudo port install npm6`

**Windows**: [nodejs.org](https://nodejs.org/en/download/)

Install documentation generator

`npm i`

Build HTML/PDF documents

`npm run build`

Resulted files

`public/*`
