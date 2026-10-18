# VEIN Pool — mining configs

Ready-to-use stratum settings for every coin on **[VEIN Pool](https://veinpool.fr/?lang=en)** (EU, France).
Your wallet address is your login — no account, no KYC. Add `.rigname` after the address to name each machine.

🇬🇧 [veinpool.fr/?lang=en](https://veinpool.fr/?lang=en) · 🇫🇷 [veinpool.fr](https://veinpool.fr)

## Ports

| Coin | Algo | HW | Pool (PPLNS) | SOLO | Page |
|---|---|---|---|---|---|
| Quantus (QTC) | QPoW | GPU | `3040` | `3042` | [qtc](https://veinpool.fr/coin/qtc?lang=en) |
| Firo (FIRO) | FiroPoW | GPU | `3060` | `3062` | [firo](https://veinpool.fr/coin/firo?lang=en) |
| Ravencoin (RVN) | KawPow | GPU | `3080` | `3082` | [rvn](https://veinpool.fr/coin/rvn?lang=en) |
| Neurai (XNA) | KawPow | GPU | `3130` | `3132` | [xna](https://veinpool.fr/coin/xna?lang=en) |
| Satoxcoin (SATOX) | KawPow | GPU | `3140` | `3142` | [satox](https://veinpool.fr/coin/satox?lang=en) |
| Neoxa (NEOX) | KawPow | GPU | `3160` | `3162` | [neox](https://veinpool.fr/coin/neox?lang=en) |
| Gaelium (GAEL) | KawPow | GPU | `3240` | `3242` | [gael](https://veinpool.fr/coin/gael?lang=en) |
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
| Beam (BEAM) | BeamHash III | GPU | `3360` | `3362` | [beam](https://veinpool.fr/coin/beam?lang=en) |
| Grin (GRIN) | Cuckatoo32 | GPU | `3380` | `3382` | [grin](https://veinpool.fr/coin/grin?lang=en) |
| Warthog (WART) | Janushash | GPU + CPU | — | `3340` (direct, 0 % fee) | [wart](https://veinpool.fr/coin/wart?lang=en) |
| Dero (DERO) | AstroBWTv3 | CPU | — | `3350` (direct, 0 % fee, wss getwork) | [dero](https://veinpool.fr/coin/dero?lang=en) |
| LuckyPepe (LPEPE) | YescryptR32 | CPU | `3400` | `3402` | [lpepe](https://veinpool.fr/coin/lpepe?lang=en) |
| Kylacoin (KCN) | Flex | CPU | `3410` | `3412` | [kcn](https://veinpool.fr/coin/kcn?lang=en) |
| Cascoin (CAS) | MinotaurX | CPU | `3430` | `3432` | [cas](https://veinpool.fr/coin/cas?lang=en) |
| Tidecoin (TDC) | YespowerTIDE | CPU | `3440` | `3442` | [tdc](https://veinpool.fr/coin/tdc?lang=en) |
| Nexa (NEXA) | NexaPow | GPU | `3460` | `3462` | [nexa](https://veinpool.fr/coin/nexa?lang=en) |
| **CapStash (CAP)** 🆕 | WhirlpoolX2 (Whirlpool-512) | GPU (NVIDIA) | `3510` · `3511` (farms) | `3512` | [cap](https://veinpool.fr/coin/cap?lang=en) |
| **Zephyr (ZEPH)** 🆕 | RandomX | CPU | `3450` | `3452` | [zeph](https://veinpool.fr/coin/zeph?lang=en) |
| **Salvium (SAL)** 🆕 | RandomX | CPU | `3100` | `3102` | [sal](https://veinpool.fr/coin/sal?lang=en) |
| **Yerbas (YERB)** 🆕 | Ghostrider | CPU | `3390` · `3391` (servers) | `3392` | [yerb](https://veinpool.fr/coin/yerb?lang=en) |

### Opening next

| Coin | Algo | HW | Pool (PPLNS) | SOLO | Status |
|---|---|---|---|---|---|
| Keryx (KRX) | KeryxHash / Proof-of-Model | GPU | `3480` | `3482` | node synced, PoM stratum bridge in progress |
| Riecoin (RIC) | Stella (prime constellations) | CPU | `3530` | `3532` | node synced, StellaPool integration in progress |
| Satoshi Cash (SCASH) | RandomX (SCASH) | CPU | `3520` | `3522` | node syncing |

Full catalog of every CPU / GPU mineable coin (prices, volume, new launches), refreshed every 10 minutes: **https://veinpool.fr/pools?lang=en#catalog**

Host for every port: `veinpool.fr` · Fee: 1 % (SOLO direct: 0 % — Zycord, Warthog, Dero: the chain pays the block straight to your address) · Each coin page has copy-paste commands for Windows, Linux, HiveOS and MMPOS.

## Examples

```bash
# KawPow (Ravencoin shown — swap the port for Neurai, Satoxcoin, Neoxa, Gaelium)
t-rex -a kawpow -o stratum+tcp://veinpool.fr:3080 -u YOUR_ADDRESS.rig1 -p x

# Firo
t-rex -a firopow -o stratum+tcp://veinpool.fr:3060 -u YOUR_ADDRESS.rig1 -p x

# Zycord (SOLO direct, blocks paid straight to your address)
xmrig -a rx/2 -o veinpool.fr:3300 -u YOUR_ZCD_ADDRESS -p rig1

# WAM Coin (official miner)
wam-miner -o stratum+tcp://veinpool.fr:3310 -u YOUR_WAM_ADDRESS.rig1

# Warthog SOLO direct — Janushash needs the GPU AND the CPU
bzminer -a warthog -w YOUR_WART_ADDRESS.rig1 -p stratum+tcp://veinpool.fr:3340 --nvidia --amd --cpu

# Dero SOLO direct (CPU) — the wallet must be registered (Engram / dero-wallet-cli do it on creation)
dero-miner --wallet-address YOUR_DERO_ADDRESS --daemon-rpc-address veinpool.fr:3350 --mining-threads 8

# Grin (Cuckatoo32) — login = your grin1… slatepack address
miner --algo grin32 --server veinpool.fr:3380 --user YOUR_GRIN1_ADDRESS.rig1   # GMiner
lolMiner --algo C32 --pool veinpool.fr:3380 --user YOUR_GRIN1_ADDRESS.rig1

# CapStash (WhirlpoolX2, NVIDIA) — Omletz Miner / ccminer: https://github.com/Omletz/omletz-miner/releases
ccminer -a whirlpoolx -o stratum+tcp://veinpool.fr:3510 -u YOUR_CAP_ADDRESS.rig1 -p x --no-longpoll      # PPLNS
ccminer -a whirlpoolx -o stratum+tcp://veinpool.fr:3512 -u YOUR_CAP_ADDRESS.rig1 -p x --no-longpoll      # SOLO

# Zephyr / Salvium (RandomX, XMRig) — Salvium needs a Carrot address (SC1…, Salvium wallet 1.0+)
xmrig -a rx/0 -o veinpool.fr:3450 -u YOUR_ZEPH_ADDRESS.rig1 -p x -k      # Zephyr PPLNS (3452 = SOLO)
xmrig -a rx/0 -o veinpool.fr:3100 -u YOUR_SC1_ADDRESS.rig1 -p x -k       # Salvium PPLNS (3102 = SOLO)

# Yerbas (Ghostrider)
SRBMiner-MULTI --algorithm ghostrider --disable-gpu --pool veinpool.fr:3390 --wallet YOUR_YERB_ADDRESS.rig1

# Kerrigan (Equihash 192,7, personalization "kerrigan")
miniZ --par=192,7 --pers=kerrigan --url YOUR_KRGN_ADDRESS.rig1@veinpool.fr:3280

# CPU coins (SRBMiner-MULTI) — LuckyPepe / Kylacoin / Cascoin / Tidecoin
SRBMiner-MULTI --algorithm yescryptr32 --disable-gpu --pool veinpool.fr:3400 --wallet YOUR_LPEPE_ADDRESS.rig1
SRBMiner-MULTI --algorithm flex        --disable-gpu --pool veinpool.fr:3410 --wallet YOUR_KCN_ADDRESS.rig1
SRBMiner-MULTI --algorithm minotaurx   --disable-gpu --pool veinpool.fr:3430 --wallet YOUR_CAS_ADDRESS.rig1
SRBMiner-MULTI --algorithm yespowertide --disable-gpu --pool veinpool.fr:3440 --wallet YOUR_TDC_ADDRESS.rig1

# Nexa (NexaPow)
lolMiner --algo NEXA --pool veinpool.fr:3460 --user YOUR_NEXA_ADDRESS.rig1

# Beam (BeamHash III)
lolMiner --algo BEAM-III --pool veinpool.fr:3360 --user YOUR_BEAM_ADDRESS.rig1
miner --algo beamhashIII --server veinpool.fr:3360 --user YOUR_BEAM_ADDRESS.rig1   # GMiner
```

## HiveOS
VEIN Pool templates (PPLNS + SOLO) are proposed upstream in [minershive/hive-pooltemplates#1865](https://github.com/minershive/hive-pooltemplates/pull/1865). Until merged, use a *Custom* pool with `veinpool.fr:<port>`.

## PPLNS or SOLO?
- **PPLNS**: every block found by any VEIN miner is shared by work done — steady income.
- **SOLO**: you keep the whole block (minus 1 %) if your rig finds it — on small networks this is realistic.

Live stats, realtime rig alerts and a pool/solo profit calculator: **https://veinpool.fr/?lang=en**

Contact: contact@veinpool.fr
