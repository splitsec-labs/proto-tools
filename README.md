# proto-tools

Collection of [proto](https://moonrepo.dev/proto) TOML plugins.

## Usage

Reference a plugin from your `.prototools`:

```toml
[plugins]
hl = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/hl/plugin.toml"
tauri-cli = "https://raw.githubusercontent.com/splitsec-labs/proto-tools/main/toml-plugins/tauri-cli/plugin.toml"
```

## Plugins

| Tool | Upstream |
| --- | --- |
| `hl` | <https://github.com/pamburus/hl> |
| `tauri-cli` | <https://github.com/tauri-apps/tauri> (binary: `cargo-tauri`) |
