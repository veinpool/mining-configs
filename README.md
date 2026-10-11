# VEIN Pool — mining configs

Ready-to-use stratum settings for every coin on **[VEIN Pool](https://veinpool.fr/?lang=en)** (EU, France).
Your wallet address is your login — no account, no KYC. Add `.rigname` after the address to name each machine.

🇬🇧 [veinpool.fr/?lang=en](https://veinpool.fr/?lang=en) · 🇫🇷 [veinpool.fr](https://veinpool.fr)

## Ports

| Coin | Algo | HW | Pool (PPLNS) | SOLO | Page |
|---|---|---|---|---|---|
| Ergo (ERG) | Autolykos2 | GPU | `3032` (1–4 GPU) · `3034` (5+ GPU) | — | [erg](https://veinpool.fr/coin/erg?lang=en) |
| Quantus (QTC) | QPoW | GPU | `3040` | `3042` | [qtc](https://veinpool.fr/coin/qtc?lang=en) |
| Firo (FIRO) | FiroPoW | GPU | `3060` | `3062` | [firo](https://veinpool.fr/coin/firo?lang=en) |
| Ravencoin (RVN) | KawPow | GPU | `3080` | `3082` | [rvn](https://veinpool.fr/coin/rvn?lang=en) |
| Neurai (XNA) | KawPow | GPU | `3130` | `3132` | [xna](https://veinpool.fr/coin/xna?lang=en) |
| Satoxcoin (SATOX) | KawPow | GPU | `3140` | `3142` | [satox](https://veinpool.fr/coin/satox?lang=en) |
| Neoxa (NEOX) | KawPow | GPU | `3160` | `3162` | [neox](https://veinpool.fr/coin/neox?lang=en) |
| Gaelium (GAEL) | KawPow | GPU | `3240` | `3242` | [gael](https://veinpool.fr/coin/gael?lang=en) |
| Kerrigan (KRGN) | KawPow | GPU | `3270` | `3272` | [krgn](https://veinpool.fr/coin/krgn?lang=en) |
| Kerrigan (KRGN) | Equihash 192,7 | GPU | `3280` | `3282` | [krgneq](https://veinpool.fr/coin/krgneq?lang=en) |
| Zano (ZANO) | ProgPowZ | GPU | `3170` | `3172` | [zano](https://veinpool.fr/coin/zano?lang=en) |
| Epic Cash (EPIC) | ProgPow | GPU | `3150` | `3152` | [epic](https://veinpool.fr/coin/epic?lang=en) |
| Qubitcoin (QTC) | Qhash | GPU | `3210` | `3212` | [qubit](https://veinpool.fr/coin/qubit?lang=en) |
| Ycash (YEC) | Equihash 192,7 | GPU | `3230` | `3232` | [yec](https://veinpool.fr/coin/yec?lang=en) |
| Tari (XTM) | RandomXT | CPU | `3070` | `3072` | [xtm](https://veinpool.fr/coin/xtm?lang=en) |
| Xelis (XEL) | XelisHash v3 | CPU | `3120` | `3122` | [xel](https://veinpool.fr/coin/xel?lang=en) |
| Feelcoin (FEEL) | RandomX | CPU | `3290` | `3292` | [feel](https://veinpool.fr/coin/feel?lang=en) |
| WAM Coin (WAM) | RandomX | CPU | `3310` (CPU) · `3311` (servers) | — | [wam](https://veinpool.fr/coin/wam?lang=en) |
| Zycord (ZCD) | RandomX v2 | CPU | — | `3300` (direct, 0 % fee) | [zcd](https://veinpool.fr/coin/zcd?lang=en) |

Host for every port: `veinpool.fr` · Fee: 1 % (Zycord 0 %) · Each coin page has copy-paste commands for Windows, Linux, HiveOS and MMPOS.

## Examples

```bash
# KawPow (Ravencoin shown — swap the port for Neurai, Satoxcoin, Neoxa, Gaelium, Kerrigan)
t-rex -a kawpow -o stratum+tcp://veinpool.fr:3080 -u YOUR_ADDRESS.rig1 -p x

# Ergo
lolMiner --algo AUTOLYKOS2 --pool veinpool.fr:3032 --user YOUR_ADDRESS.rig1

# Firo
t-rex -a firopow -o stratum+tcp://veinpool.fr:3060 -u YOUR_ADDRESS.rig1 -p x

# Zycord (SOLO direct, blocks paid straight to your address)
xmrig -a rx/2 -o veinpool.fr:3300 -u YOUR_ZCD_ADDRESS -p rig1

# WAM Coin (official miner)
wam-miner -o stratum+tcp://veinpool.fr:3310 -u YOUR_WAM_ADDRESS.rig1
```

## PPLNS or SOLO?
- **PPLNS**: every block found by any VEIN miner is shared by work done — steady income.
- **SOLO**: you keep the whole block (minus 1 %) if your rig finds it — on small networks this is realistic.

Live stats, realtime rig alerts and a pool/solo profit calculator: **https://veinpool.fr/?lang=en**

Contact: contact@veinpool.fr
