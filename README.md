# shadowsocks-windows-gui-rust
Shadowsocks Windows GUI in Rust, with Stream Cipher support.

## Important
1. Edit russ.json and fill your shadowsocks server IP, pass, method...etc.
2. put `shadowsocks-gui-rust.exe` and `russ.json` in the same place.
3. Stream Ciphers Enabled (by default)
- `plain` or `none` (No encryption, only used for debugging or with plugins that ensure transport security)

- `table`
- `aes-128-cfb`, `aes-128-cfb1`, `aes-128-cfb8`, `aes-128-cfb128`
- `aes-192-cfb`, `aes-192-cfb1`, `aes-192-cfb8`, `aes-192-cfb128`
- `aes-256-cfb`, `aes-256-cfb1`, `aes-256-cfb8`, `aes-256-cfb128`
- `aes-128-ctr`
- `aes-192-ctr`
- `aes-256-ctr`
- `camellia-128-cfb`, `camellia-128-cfb1`, `camellia-128-cfb8`, `camellia-128-cfb128`
- `camellia-192-cfb`, `camellia-192-cfb1`, `camellia-192-cfb8`, `camellia-192-cfb128`
- `camellia-256-cfb`, `camellia-256-cfb1`, `camellia-256-cfb8`, `camellia-256-cfb128`
- `rc4-md5`
- `chacha20-ietf`

### Thanks
1. shadowsocks-rust https://github.com/shadowsocks/shadowsocks-rust
2. native-windows-gui https://github.com/gabdube/native-windows-gui



