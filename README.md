<div align="center">

<img src="https://ammanaya-coord.github.io/ammanaya.png" width="140" alt="Ammanaya" />

# 🔥 Ammanaya

**The fire that sets you free ⚡🔥**

P2P Bitcoin Lightning coordinator in the [RoboSats](https://github.com/RoboSats/robosats) federation

[Website](https://ammanaya-coord.github.io/) · [Guides](https://ammanaya-coord.github.io/guides.html) · [FAQ](https://ammanaya-coord.github.io/#faq) · [Contact](#-contact)

</div>

---

### 🧡 Who we are

Ammanaya is the ancestral goddess of fire, born to set you free. We run a privacy-first coordinator for **RoboSats**, the open-source peer-to-peer exchange where you buy and sell bitcoin over Lightning without KYC. We have been part of the federation since August 2026.

### ⚡ What is RoboSats?

RoboSats lets two people trade bitcoin for fiat directly with each other. Nobody asks who you are: you get a random **robot** identity, and its token is the only key to it.

- **No KYC:** no accounts, no ID, no personal data.
- **Non-custodial:** the seller's sats are locked in a Lightning **hold invoice** and only move when the trade completes. The coordinator never holds them.
- **Bonds keep it honest:** both sides lock a small bond (3% by default) that is returned when the trade finishes fairly.
- **A federation, not a company:** independent coordinators each run their own order book. The app shows them all in one place and you choose who coordinates your trade.
- **Tor by default:** the app and the coordinators are reached over Tor.
- **Get the app:** the [RoboSats Android app](https://github.com/RoboSats/robosats/releases) has Tor built in, or open our onion in [Tor Browser](https://www.torproject.org/download/): `ammannjgzybw4qm2odmci7xgolh5grzijidacjxose5tthm375dcopad.onion`

### 🔥 Ammanaya at a glance

| | |
|---|---|
| 🧅 Onion | `ammannjgzybw4qm2odmci7xgolh5grzijidacjxose5tthm375dcopad.onion` |
| 💸 Fees | 0.02% maker · 0.17% taker (0.19% total) |
| 📦 Order size | 1,000 – 2,000,000 sats |
| 🔒 Bond | 3% (adjustable by the maker) |
| 🛠️ DevFund | 50% of our fees are donated to RoboSats: ⅓ to the community fund, ⅔ to development |
| 📡 Orders | Also published over Nostr for decentralized discovery |
| ⚡ Lightning node | [02cd5662…7fe3 on Amboss](https://amboss.space/node/02cd566293ad8c8fd55bf5c5be38df5fc0af2b445333b10cbbd8b8a7d4c7ed7fe3) |

**How to trade:** open the [RoboSats Android app](https://github.com/RoboSats/robosats/releases) or our onion in [Tor Browser](https://www.torproject.org/download/), create your robot, **back up its token**, then make or take an order and pick Ammanaya as coordinator. Step-by-step [buy and sell guides](https://ammanaya-coord.github.io/guides.html) are on our website.

### ⚖️ Disputes and privacy

If a trade goes wrong, open a dispute in the app. We review the evidence from both sides and decide fairly. Please hide any personal details that aren't needed. Evidence is kept only while the dispute is open and deleted afterwards.

### 📬 Contact

- ✉️ Email: [pucot458KK@proton.me](mailto:pucot458KK@proton.me)
- 💬 SimpleX: [chat with us](https://smp1.simplexonflux.com/a#UmzW2iVe6cafc0G24FO-loxValRqfgBVCvXFSn6cypw)
- 🟣 Nostr: `npub1jxpqkr78u5588ft5yzx8kn5m3t5y3m39uhqrhtr9t3zaqcye24yql86vq2`
- ✈️ Telegram: [@ammanaya_support](https://t.me/ammanaya_support) · notifications via [@ammanaya_bot](https://t.me/ammanaya_bot)
- 🔑 PGP: `2B48 3017 4198 9AB0 2332 78EF 157C 0F85 7A99 8CC0`

For disputes, always mention your order number.

### 🤝 Fellow coordinators

The RoboSats federation is only as strong as its coordinators. These are the others you can trade with today:

| Coordinator | Motto | Website | GitHub | Nostr |
|---|---|---|---|---|
| 🏛 **Temple of Sats** | Privacy and Integrity | [templeofsats.org](https://templeofsats.org) | [@TempleOfSats](https://github.com/TempleOfSats) | [npub1wsqpv…k4xtl](https://njump.me/npub1wsqpvgpfwq6a4fs5whqxn7gtd9gqsll2p5qnfdu4ltr43s6wwxgsgk4xtl) |
| 🌊 **TheBigLake** | The Lake of Economic Freedom | [thebiglake.org](https://thebiglake.org/) | [@gabbygator184](https://github.com/gabbygator184) | [npub17t2g2…8wj6f](https://njump.me/npub17t2g2h0nnf7mvxtxvm5ydxs85ycumhqgmj48gj35gdplln655yxq68wj6f) |
| 🛍 **LibreBazaar** | Freedom and Integrity | [mail@librebazaar.com](mailto:mail@librebazaar.com) | [@jerryfletcher21](https://github.com/jerryfletcher21) | [npub1j4fp5…j5e5g](https://njump.me/npub1j4fp5va6xn6ey3ry7sj7sxufdvd2jp5hj6nhsd5w6pf7xcfv2zdspj5e5g) |
| ⚓ **FreePort** | Free trade, free ports, free people | [freeport.bz](https://freeport.bz) | [@fp-coordinator](https://github.com/fp-coordinator) | [npub1ujyum…gqfnw](https://njump.me/npub1ujyumv9jf7jpdfym2frztc8d4v8hyd0n5qnp50xlcexyalwpft7s7gqfnw) |

### 🛠️ On GitHub

Fixes we have sent to RoboSats while running our coordinator:

- ✅ [#2864](https://github.com/RoboSats/robosats/pull/2864) Payout safety: check reward sources and buyer payouts against LND *(merged)*
- ✅ [#2879](https://github.com/RoboSats/robosats/pull/2879) Android: embedded Tor 0.4.9, as Tor 0.4.8 can no longer bootstrap *(merged)*
- 🔄 [#2888](https://github.com/RoboSats/robosats/pull/2888) Convert v0.8.7 HTML order logs to the v0.8.8 JSON format
- 🔄 [#2889](https://github.com/RoboSats/robosats/pull/2889) Run migrations under a PostgreSQL advisory lock on container start
- 🔄 [#2890](https://github.com/RoboSats/robosats/pull/2890) Refresh the trade box after an action changes the order status

---

<div align="center">

**The fire that sets you free ⚡🔥**

— Ammanaya

</div>
