# shadowsocks-windows-gui-rust
Shadowsocks Windows GUI in Rust language, with Stream Cipher support.

## Important
1. Edit russ.json and fill your shadowsocks server IP, pass, method...etc.
2. put `shadowsocks-gui-rust.exe` and `russ.json` in the same place.
3. Stream Ciphers Enabled (by default)
- `plain` or `none` (No encryption, only used for debugging or with plugins that ensure transport security)

  About:
  -----
The primary encryption used is AEAD-cipher and AEAD-cipher-2022, but stream cipher is also supported. However, caution is advised when using it, as it is relatively less secure.

Note: The security-replay-attack-detect patch, which enables detection against replay attacks, has been activated by default to protect "stream cipher".
.

Stream Cipher Supported:
------------------------

- `table`, `aes-cfb`, `aes-cfb1`, `aes-cfb8`, `aes-cfb128`, `aes-ctr`, `camellia-cfb`, `camellia-cfb1`, `camellia-cfb8`, `camellia-cfb128`, `rc4-md5`, `chacha20-ietf`.

AED

### Thanks
1. shadowsocks-rust https://github.com/shadowsocks/shadowsocks-rust
2. native-windows-gui https://github.com/gabdube/native-windows-gui



