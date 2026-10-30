# VEIN Pool — mining configs

Ready-to-use stratum settings for all **42 coins** on **[VEIN Pool](https://veinpool.fr/en)** (EU, France): 21 GPU · 17 CPU · 4 ASIC (+ Kiirocoin in a few days).
Your wallet address is your login — no account, no KYC. Add `.rigname` after the address to name each machine.

🇬🇧 [veinpool.fr/en](https://veinpool.fr/en) · 🇫🇷 [veinpool.fr](https://veinpool.fr)

## Ports

| Coin | Algo | HW | Pool (PPLNS) | SOLO | Page |
|---|---|---|---|---|---|
| Quantus (QTC) | QPoW | GPU | `3040` | `3042` | [qtc](https://veinpool.fr/en/coin/qtc) |
| Firo (FIRO) | FiroPoW | GPU | `3060` | `3062` | [firo](https://veinpool.fr/en/coin/firo) |
| Ravencoin (RVN) | KawPow | GPU | `3080` | `3082` | [rvn](https://veinpool.fr/en/coin/rvn) |
| Neurai (XNA) | KawPow | GPU | `3130` | `3132` | [xna](https://veinpool.fr/en/coin/xna) |
| Satoxcoin (SATOX) | KawPow | GPU | `3140` | `3142` | [satox](https://veinpool.fr/en/coin/satox) |
| Neoxa (NEOX) | KawPow | GPU | `3160` | `3162` | [neox](https://veinpool.fr/en/coin/neox) |
| Gaelium (GAEL) | KawPow | GPU | `3240` | `3242` | [gael](https://veinpool.fr/en/coin/gael) |
| Kerrigan (KRGN) | Equihash 192,7 | GPU | `3280` | `3282` | [krgneq](https://veinpool.fr/en/coin/krgneq) |
| Zano (ZANO) | ProgPowZ | GPU | `3170` | `3172` | [zano](https://veinpool.fr/en/coin/zano) |
| **Epic Cash (EPIC)** 🆕 CPU too | ProgPow + RandomX | GPU + CPU | `3150` (GPU `progpow_epic`, CPU `randomepic`) | `3152` | [epic](https://veinpool.fr/en/coin/epic) |
| Qubitcoin (QTC) | Qhash | GPU | `3210` | `3212` | [qubit](https://veinpool.fr/en/coin/qubit) |
| Ycash (YEC) | Equihash 192,7 | GPU | `3230` | `3232` | [yec](https://veinpool.fr/en/coin/yec) |
| Tari (XTM) | RandomXT | CPU | `3070` | `3072` | [xtm](https://veinpool.fr/en/coin/xtm) |
| Xelis (XEL) | XelisHash v3 | CPU | `3120` | `3122` | [xel](https://veinpool.fr/en/coin/xel) |
| Feelcoin (FEEL) | RandomX | CPU | `3290` | `3292` | [feel](https://veinpool.fr/en/coin/feel) |
| WAM Coin (WAM) | RandomX | CPU | `3310` (CPU) · `3311` (servers) | — | [wam](https://veinpool.fr/en/coin/wam) |
| Zycord (ZCD) | RandomX v2 | CPU | — | `3300` (direct, 0 % fee) | [zcd](https://veinpool.fr/en/coin/zcd) |
| Lajkto Coin (LKCT) | RandomX | CPU | — | `3702` (direct, 0 % fee) | [lkct](https://veinpool.fr/en/coin/lkct) |
| Beam (BEAM) | BeamHash III | GPU | `3360` | `3362` | [beam](https://veinpool.fr/en/coin/beam) |
| Grin (GRIN) | Cuckatoo32 | GPU | `3380` | `3382` | [grin](https://veinpool.fr/en/coin/grin) |
| Warthog (WART) | Janushash | GPU + CPU | — | `3340` (direct, 0 % fee) | [wart](https://veinpool.fr/en/coin/wart) |
| Dero (DERO) | AstroBWTv3 | CPU | — | `3350` (direct, 0 % fee, wss getwork) | [dero](https://veinpool.fr/en/coin/dero) |
| LuckyPepe (LPEPE) | YescryptR32 | CPU | `3400` | `3402` | [lpepe](https://veinpool.fr/en/coin/lpepe) |
| Kylacoin (KCN) | Flex | CPU | `3410` | `3412` | [kcn](https://veinpool.fr/en/coin/kcn) |
| Cascoin (CAS) | MinotaurX | CPU | `3430` | `3432` | [cas](https://veinpool.fr/en/coin/cas) |
| Tidecoin (TDC) | YespowerTIDE | CPU | `3440` | `3442` | [tdc](https://veinpool.fr/en/coin/tdc) |
| Nexa (NEXA) | NexaPow | GPU | `3460` | `3462` | [nexa](https://veinpool.fr/en/coin/nexa) |
| **CapStash (CAP)** 🆕 | WhirlpoolX2 (Whirlpool-512) | GPU (NVIDIA) | `3510` · `3511` (farms) | `3512` | [cap](https://veinpool.fr/en/coin/cap) |
| **Zephyr (ZEPH)** 🆕 | RandomX | CPU | `3450` | `3452` | [zeph](https://veinpool.fr/en/coin/zeph) |
| **Salvium (SAL)** 🆕 | RandomX | CPU | `3100` | `3102` | [sal](https://veinpool.fr/en/coin/sal) |
| **Yerbas (YERB)** 🆕 | Ghostrider | CPU | `3390` · `3391` (servers) | `3392` | [yerb](https://veinpool.fr/en/coin/yerb) |
| **Satoshi Cash (SCASH)** 🆕 | RandomX (SCASH) | CPU | `3520` · `3521` (servers) | `3522` | [scash](https://veinpool.fr/en/coin/scash) |
| **Karlsen (KLS)** 🆕 | KarlsenHashV2 (FishHash) | GPU | `3470` | `3472` | [kls](https://veinpool.fr/en/coin/kls) |
| **Conceal (CCX)** 🆕 | CryptoNight-GPU | GPU + CPU | `3560` | `3562` | [ccx](https://veinpool.fr/en/coin/ccx) |
| **Riecoin (RIC)** 🆕 | Stella (prime constellations) | CPU | `3530` (login = ric1 address) | — | [ric](https://veinpool.fr/en/coin/ric) |
| **Phicoin (PHI)** 🆕 | PhiHash | GPU | `3570` | `3572` | [phi](https://veinpool.fr/en/coin/phi) |
| **Bitcoin (BTC)** 🆕 | SHA-256 | **ASIC · Bitaxe · NerdMiner** | — | `3600` NerdMiner · `3601` Bitaxe · `3602` ASIC (SOLO lottery, 1 %) | [btc](https://veinpool.fr/en/coin/btc) |
| **Bitcoin Cash (BCH)** 🆕 | SHA-256 | **ASIC · Bitaxe · NerdMiner** | — | `3610` NerdMiner · `3611` Bitaxe · `3612` ASIC (SOLO, 1 %, TLS 13610–13612) | [bch](https://veinpool.fr/en/coin/bch) |
| **Litecoin (LTC)** 🆕 | Scrypt | **Scrypt ASIC** | — | `3620` mini Scrypt · `3622` ASIC (SOLO, 1 %, LTC only, TLS 13620 / 13622) | [ltc](https://veinpool.fr/en/coin/ltc) |
| **Dogecoin (DOGE)** 🆕 | Scrypt | **Scrypt ASIC** | — | `3630` mini Scrypt · `3632` ASIC (SOLO, 1 %, DOGE only) | [doge](https://veinpool.fr/en/coin/doge) |
| **Kiirocoin (KIIRO)** ⏳ opens in a few days | FiroPoW | GPU | `3650` · `3651` (farms) | `3652` | [kiiro](https://veinpool.fr/en/coin/kiiro) |
| **FortuneBlock (FBX)** 🆕 | Mike | CPU | `3660` · `3661` (servers) | `3662` | [fbx](https://veinpool.fr/en/coin/fbx) |
| **RIGOR (ORU)** 🆕 | OpuHash (SHA3-256) | GPU + CPU | — | `3642` (direct, 0 % fee, getblocktemplate over `http://`, no stratum) | [oru](https://veinpool.fr/en/coin/oru) |
| **GSP Coin (GSPC)** 🆕 | GhostRider | CPU | `3730` · `3731` (servers) | `3732` | [gspc](https://veinpool.fr/en/coin/gspc) |
| **GoByte (GBX)** 🆕 | NeoScrypt | GPU | `3890` · `3891` (farms) | `3892` | [gbx](https://veinpool.fr/en/coin/gbx) |
| **Vertcoin (VTC)** 🆕 | Verthash | GPU | `3710` · `3711` (farms) | — | [vtc](https://veinpool.fr/en/coin/vtc) |
| **Zero (ZER)** 🆕 | Equihash 192,7 | GPU | `3690` · `3691` (farms) | `3692` | [zer](https://veinpool.fr/en/coin/zer) |
| **Feathercoin (FTC)** 🆕 | NeoScrypt | GPU | `3810` · `3811` (farms) | `3812` | [ftc](https://veinpool.fr/en/coin/ftc) |
| **Phoenixcoin (PXC)** 🆕 | NeoScrypt | GPU | `3680` · `3681` (farms) | `3682` | [pxc](https://veinpool.fr/en/coin/pxc) |
| **Groestlcoin (GRS)** 🆕 | Groestl | GPU | `3800` · `3801` (farms) | `3802` | [grs](https://veinpool.fr/en/coin/grs) |

Full catalog of every CPU / GPU / ASIC mineable coin (prices, volume, new launches), refreshed every 10 minutes: **https://veinpool.fr/en/pools#catalog**

Host for every port: `veinpool.fr` · Fee: 1 % (SOLO direct: 0 % — Zycord, Lajkto Coin, RIGOR, Warthog, Dero: the chain pays the block straight to your address) · Each coin page has copy-paste commands for Windows, Linux, HiveOS and MMPOS.

## Examples

```bash
# Bitcoin SOLO lottery — NerdMiner / Bitaxe / ASIC: type these in the device's web page (no software)
#   NerdMiner (ESP32):      pool veinpool.fr  port 3600  BTC address = YOUR_BTC_ADDRESS
#   Bitaxe / NerdAxe (AxeOS): Stratum URL veinpool.fr  Port 3601  User YOUR_BTC_ADDRESS.rig1  Password x
#   ASIC (Antminer...):     stratum+tcp://veinpool.fr:3602  Worker YOUR_BTC_ADDRESS.rig1  Password x
cgminer -o stratum+tcp://veinpool.fr:3602 -u YOUR_BTC_ADDRESS.rig1 -p x

# Bitcoin Cash SOLO — same SHA-256 hardware, network ~325x smaller than Bitcoin's (S21 200 TH/s: ~1 block / 109 days on average)
#   NerdMiner 3610 · Bitaxe 3611 · ASIC 3612   User YOUR_BCH_ADDRESS.rig1  Password x
cgminer -o stratum+tcp://veinpool.fr:3612 -u YOUR_BCH_ADDRESS.rig1 -p x

# Litecoin SOLO — Scrypt ASIC (Antminer L7 / L9, Elphapex DG1, Goldshell); LTC only, no merged DOGE
#   mini Scrypt 3620 · ASIC 3622   Worker YOUR_LTC_ADDRESS.rig1  Password x   (L9 16 GH/s: ~70 % chance of a block per year)
cgminer --scrypt -o stratum+tcp://veinpool.fr:3622 -u YOUR_LTC_ADDRESS.rig1 -p x

# Dogecoin SOLO — Scrypt ASIC; DOGE only, no merged LTC; 10,000 DOGE per block, 1 block a minute
#   mini Scrypt 3630 · ASIC 3632   Worker YOUR_DOGE_ADDRESS.rig1  Password x   (L9 16 GH/s: ~1 block every 4 months on average)
cgminer --scrypt -o stratum+tcp://veinpool.fr:3632 -u YOUR_DOGE_ADDRESS.rig1 -p x

# Epic Cash — GPU (ProgPow) AND CPU (RandomX) on the same pool, same address: run both, two worker names
SRBMiner-MULTI --algorithm progpow_epic --disable-cpu --pool veinpool.fr:3150 --wallet YOUR_EPICBOX_ADDRESS.gpu1
SRBMiner-MULTI --algorithm randomepic --disable-gpu --pool veinpool.fr:3150 --wallet YOUR_EPICBOX_ADDRESS.cpu1

# KawPow (Ravencoin shown — swap the port for Neurai, Satoxcoin, Neoxa, Gaelium)
t-rex -a kawpow -o stratum+tcp://veinpool.fr:3080 -u YOUR_ADDRESS.rig1 -p x

# Firo
t-rex -a firopow -o stratum+tcp://veinpool.fr:3060 -u YOUR_ADDRESS.rig1 -p x

# Zycord (SOLO direct, blocks paid straight to your address)
xmrig -a rx/2 -o veinpool.fr:3300 -u YOUR_ZCD_ADDRESS -p rig1

# Lajkto Coin (SOLO direct, 0 % fee; young coin: 15 % founder premine, not listed yet)
xmrig -a rx/0 -o veinpool.fr:3702 -u YOUR_LKCT_ADDRESS.rig1 -p x -k

# Kiirocoin (same FiroPoW settings as Firo; opens in a few days)
t-rex -a firopow -o stratum+tcp://veinpool.fr:3650 -u YOUR_KIIRO_ADDRESS.rig1 -p x

# FortuneBlock (CPU, Mike; not listed on an exchange yet)
SRBMiner-MULTI --algorithm mike --disable-gpu --pool veinpool.fr:3660 --wallet YOUR_FBX_ADDRESS.cpu1

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

# Satoshi Cash (RandomX SCASH variant — XMRig has no SCASH mode, use SRBMiner 3.7+)
SRBMiner-MULTI --algorithm randomscash --disable-gpu --pool veinpool.fr:3520 --wallet YOUR_SCASH_ADDRESS.rig1   # PPLNS (3522 = SOLO)

# Yerbas (Ghostrider)
SRBMiner-MULTI --algorithm ghostrider --disable-gpu --pool veinpool.fr:3390 --wallet YOUR_YERB_ADDRESS.rig1

# Kerrigan (Equihash 192,7, personalization "kerrigan")
miniZ --par=192,7 --pers=kerrigan --url YOUR_KRGN_ADDRESS.rig1@veinpool.fr:3280

# CPU coins (SRBMiner-MULTI) — LuckyPepe / Kylacoin / Cascoin / Tidecoin
SRBMiner-MULTI --algorithm yescryptr32 --disable-gpu --pool veinpool.fr:3400 --wallet YOUR_LPEPE_ADDRESS.rig1
SRBMiner-MULTI --algorithm flex        --disable-gpu --pool veinpool.fr:3410 --wallet YOUR_KCN_ADDRESS.rig1
SRBMiner-MULTI --algorithm minotaurx   --disable-gpu --pool veinpool.fr:3430 --wallet YOUR_CAS_ADDRESS.rig1
SRBMiner-MULTI --algorithm yespowertide --disable-gpu --pool veinpool.fr:3440 --wallet YOUR_TDC_ADDRESS.rig1

# Riecoin (official rieMiner, https://riecoin.xyz/rieMiner/)
rieMiner rieMiner.conf Mode=Pool Host=veinpool.fr Port=3530 Username=YOUR_RIC1_ADDRESS Password=x

# Karlsen (KarlsenHashV2) — lolMiner or Rigel
lolMiner --algo KARLSENV2 --pool veinpool.fr:3470 --user YOUR_KLS_ADDRESS.rig1
rigel -a karlsenhashv2 -o stratum+tcp://veinpool.fr:3470 -u YOUR_KLS_ADDRESS -w rig1

# Nexa (NexaPow)
lolMiner --algo NEXA --pool veinpool.fr:3460 --user YOUR_NEXA_ADDRESS.rig1

# Beam (BeamHash III)
lolMiner --algo BEAM-III --pool veinpool.fr:3360 --user YOUR_BEAM_ADDRESS.rig1
miner --algo beamhashIII --server veinpool.fr:3360 --user YOUR_BEAM_ADDRESS.rig1   # GMiner
```

## HiveOS
VEIN Pool templates (PPLNS + SOLO) are proposed upstream in [minershive/hive-pooltemplates#1865](https://github.com/minershive/hive-pooltemplates/pull/1865). Until merged, use a *Custom* pool with `veinpool.fr:<port>`.

## Squads (beta) — mine solo as a team

A third mode between PPLNS and SOLO: a closed group mines solo together and shares **only the blocks the group finds**, by merit
(PPLNS window = the squad's last 2 network difficulties of work). 1 % fee, small-miner bonus up to +5 % inside the squad too, a public
split statement with its SHA-256 for every block. Create or join a squad: https://veinpool.fr/en/escouades

| Coin | Squad port | TLS | Worker name |
|---|---|---|---|
| Satoxcoin (KawPow) | `3143` | `13143` | `CODE-rig`, e.g. `YOUR_ADDRESS.7KQ2-rig1` |
| Feelcoin (RandomX) | `3293` | `13293` | `CODE-rig` |
| Phicoin (PhiHash) | `3573` | `13573` | `CODE-rig` |

```
# Satoxcoin, squad VEIN-7KQ2
t-rex -a kawpow -o stratum+tcp://veinpool.fr:3143 -u YOUR_SATOX_ADDRESS.7KQ2-rig1 -p x
# Feelcoin
xmrig -a rx/0 -o veinpool.fr:3293 -u YOUR_FEEL_ADDRESS.7KQ2-rig1 -p x -k
```
Without a valid code the rig simply mines SOLO (it never loses a block).

## PPLNS or SOLO?
- **PPLNS**: every block found by any VEIN miner is shared by work done — steady income.
- **SOLO**: you keep the whole block (minus 1 %) if your rig finds it — on small networks this is realistic.

Live stats, realtime rig alerts and a pool/solo profit calculator: **https://veinpool.fr/en**

Live market for every coin (price, 24 h change, volume, candlestick chart from its main exchange, refreshed every 10 s): **https://veinpool.fr/en#marches** · each coin page also links its official site, explorer, GitHub and exchange.

Contact: contact@veinpool.fr
