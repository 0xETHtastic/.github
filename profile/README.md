# ETHastic

> Resilient payments for when the internet goes dark.

ETHastic is an asynchronous financial protocol that keeps economic activity alive when centralized infrastructure fails. By combining **LoRa Mesh Networking**, **WaaS**, and **Stripe**, we ensure a total blackout doesn't mean a total freeze of value exchange — payments travel peer-to-peer through the community, settle on-chain, and confirm back to the sender, even miles away from the nearest cell tower.

---

## 📡 EVVM Deployment — Arc Testnet

| Field | Value |
|-------|-------|
| **Chain ID** | `5042002` |
| **Network** | Arc Testnet |
| **EVVM ID** | `1160` |
| **Core Address** | `0x085FEa487ca750479fB82b690C563312FBc2d1a8` |

### Deployed Contracts

| Contract | Address |
|----------|---------|
| Core | `0x085FEa487ca750479fB82b690C563312FBc2d1a8` |
| Staking | `0x8D10eD1d0F396d970a7e9CF9587fA79b0B9905aa` |
| Estimator | `0x9F10189C58568F540CbF84aB9f6fE9fF1c833732` |
| NameService | `0xffE9489Ce9A783E8286Db1D7Fe9977002c7c2781` |
| Treasury | `0x1fa4Ae804E27896C45771B7D41330feBC868A7Bc` |
| P2PSwap | `0x5A389465baD0AEaBf8601F60F905a5cc79140490` |
| CctpService | `0x166b4207da35740e38e55B09819fdFAdF27401cD` |

> 📅 Timestamp: `2026-04-03T22:39:10.656Z`

---

## 🌉 CCTP Bridge — Arc Testnet → Arbitrum Sepolia

**Status:** ✅ `done`

### Arc Testnet (origin)

| Step | Tx Hash |
|------|---------|
| Tx Service | [`0x1f6ca73e3e648de5d1b720c071a6708d5123839d1d9142697dd4cf5f9e846695`](https://testnet.arcscan.app/tx/0x1f6ca73e3e648de5d1b720c071a6708d5123839d1d9142697dd4cf5f9e846695) |
| Withdraw EVVM | [`0x7c8b187fd0591b4088b20bda515b77bf4cc64003413e6ad928d9b647c39f9e27`](https://testnet.arcscan.app/tx/0x7c8b187fd0591b4088b20bda515b77bf4cc64003413e6ad928d9b647c39f9e27) |
| Approve | [`0x2cfeb7c40296554601411962a53502c1e8cbbc2d70f2d8d2be49111595c74d5a`](https://testnet.arcscan.app/tx/0x2cfeb7c40296554601411962a53502c1e8cbbc2d70f2d8d2be49111595c74d5a) |
| Burn | [`0xebc0798e0cd0e1ffd752561b6c7a3eb0d9d03322103d97a64cfdc48d7d612e2a`](https://testnet.arcscan.app/tx/0xebc0798e0cd0e1ffd752561b6c7a3eb0d9d03322103d97a64cfdc48d7d612e2a) |

### Arbitrum Sepolia (destination)

| Step | Tx Hash |
|------|---------|
| Mint | [`0x40959a6a384010205dfde771f353d8a1153d1091ddb5ef6ed0a3317c4c8a41c9`](https://sepolia.arbiscan.io/tx/0x40959a6a384010205dfde771f353d8a1153d1091ddb5ef6ed0a3317c4c8a41c9) |
