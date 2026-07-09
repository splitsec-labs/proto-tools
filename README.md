# proto-tools

Collection of [proto](https://moonrepo.dev/proto) TOML plugins.

## Usage

Reference a plugin from your `.prototools`:

```toml
[plugins]
cargo-nextest = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/cargo-nextest/plugin.toml"
hl = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/hl/plugin.toml"
sccache = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/sccache/plugin.toml"
tauri-cli = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/tauri-cli/plugin.toml"
```

## Plugins

| Tool | Upstream |
| --- | --- |
| `cargo-nextest` | <https://github.com/nextest-rs/nextest> |
| `hl` | <https://github.com/pamburus/hl> |
| `sccache` | <https://github.com/mozilla/sccache> |
| `tauri-cli` | <https://github.com/tauri-apps/tauri> (binary: `cargo-tauri`) |
