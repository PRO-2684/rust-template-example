# rust-template-example

[![GitHub License](https://img.shields.io/github/license/runner/rust-template-example?logo=opensourceinitiative)](https://github.com/runner/rust-template-example/blob/main/LICENSE)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/runner/rust-template-example/release.yml?logo=githubactions)](https://github.com/runner/rust-template-example/blob/main/.github/workflows/release.yml)
[![GitHub Release](https://img.shields.io/github/v/release/runner/rust-template-example?logo=githubactions)](https://github.com/runner/rust-template-example/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/runner/rust-template-example/total?logo=github)](https://github.com/runner/rust-template-example/releases)
[![Crates.io Version](https://img.shields.io/crates/v/rust-template-example?logo=rust)](https://crates.io/crates/rust-template-example)
[![Crates.io Total Downloads](https://img.shields.io/crates/d/rust-template-example?logo=rust)](https://crates.io/crates/rust-template-example)
[![docs.rs](https://img.shields.io/docsrs/rust-template-example?logo=rust)](https://docs.rs/rust-template-example)

An example showcasing the usage of https://github.com/PRO-2684/rust-template.

## ⚙️ Automatic Releases Setup

1. [Create a new GitHub repository](https://github.com/new) with the name `rust-template-example` and push this generated project to it.
2. Enable Actions for the repository, and grant "Read and write permissions" to the workflow [here](https://github.com/runner/rust-template-example/settings/actions).
3. [Generate an API token on crates.io](https://crates.io/settings/tokens/new), with the following setup:

    - `Name`: `rust-template-example`
    - `Expiration`: `No expiration`
    - `Scopes`: `publish-new`, `publish-update`
    - `Crates`: `rust-template-example`

4. [Add a repository secret](https://github.com/runner/rust-template-example/settings/secrets/actions) named `CARGO_TOKEN` with the generated token as its value.
5. Consider removing this section and updating this README with your own project information.

## 📥 Installation

### Using [`binstall`](https://github.com/cargo-bins/cargo-binstall)

```shell
cargo binstall rust-template-example
```

### Downloading from Releases

Navigate to the [Releases page](https://github.com/runner/rust-template-example/releases) and download respective binary for your platform. Make sure to give it execute permissions.

### Compiling from Source

```shell
cargo install rust-template-example
```

## 💡 Examples

TODO

## 📖 Usage

TODO

## 🎉 Credits

TODO
