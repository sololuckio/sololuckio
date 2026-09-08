# SoloLuck

**[sololuck.io](https://sololuck.io) — a 0% fee Bitcoin solo mining pool.**

True solo mining: you mine against the whole Bitcoin network on your own, and a block
you solve pays **the entire reward straight to your own address**. The pool never holds
your coins, takes no cut, and there is no account and no KYC — your Bitcoin address *is*
your login.

### Connect

Point a miner at the tier that fits your hardware:

| tier | port | for |
|---|---|---|
| Nano | `3335` | CPUs and NerdMiners |
| Lite | `3333` | Bitaxe and small ASICs |
| Pro | `4334` | large ASICs and rentals |
| TLS | `3334` | encrypted, any hardware |

```
stratum+tcp://stratum.sololuck.io:3333   # Jakarta
stratum+tcp://us.stratum.sololuck.io:3333   # Phoenix
stratum+tcp://sg.stratum.sololuck.io:3333   # Singapore door
```

The minimum share difficulty is 1, so CPU- and NerdMiner-class hardware is actually
served rather than rejected. Full setup guides and a live latency test are at
[sololuck.io/connect](https://sololuck.io/connect).

### Verify it rather than trust it

- Live pool stats: [sololuck.io/status](https://sololuck.io/status) · [`/api/public`](https://sololuck.io/api/public)
- Every block template we build is inspectable: [sololuck.io/proof](https://sololuck.io/proof)
- Independent listing: [miningpoolstats.stream](https://miningpoolstats.stream/bitcoin)

**Stated plainly: SoloLuck has not found a Bitcoin block yet.** It is a small pool and
says so on its own front page.

### Here

Mostly the miner software and the integrations that let other people's firmware and apps
reach the pool — plus forks of projects we have contributed pool listings back to.

- [`SoloLuckMiner`](https://github.com/sololuckio/SoloLuckMiner) — open-source Windows CPU miner
- [`stratum-speed-test`](https://github.com/sololuckio/stratum-speed-test) — measure latency and stratum handshake speed against any pool

### Elsewhere

[Website](https://sololuck.io) · [Telegram](https://t.me/SoloLuckPool) · [Status](https://sololuck.io/status)
