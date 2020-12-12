# SX Token

> SX token contract based on `eosio.token`

## SHA256 Checksum

**Local**
```bash
$ eosio-cpp token.sx.cpp
$ shasum -a 256 token.sx.wasm
74fb8f96e5cbdd9f3524c14425dd8478a9ca86c51aefc9ecdf9a4968e43fe1ed  token.sx.wasm
```

**EOS Mainnet**
```bash
$ cleos -u https://api.eosn.io get code token.sx
code hash: 74fb8f96e5cbdd9f3524c14425dd8478a9ca86c51aefc9ecdf9a4968e43fe1ed
```
