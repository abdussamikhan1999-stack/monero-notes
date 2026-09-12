# Monero (/XMR/) Notes

Notes distilled from `/XMR/` (Monero General, 4chan-style) — Monero itself,
buying/mining/storing it, and legitimate merchant directories.

See [LINKS.md](LINKS.md) for the full raw link list.

## A flag before the summary

The thread's "Buy/sell goods & services" section includes an **"Exotic
goods"** pastebin link. Given the context (a privacy-coin community
specifically prizing untraceability), that link is very likely pointing at
darknet-market-style listings rather than anything mundane. I haven't
fetched or verified its contents, and I'm not summarizing or cataloging
what it links to — it's noted in LINKS.md purely for completeness, not as
something to act on. Everything else in this thread — the coin itself, the
technology, exchanges, wallets, mining, and the merchant/gift-card
directories — is legitimate: Monero is a legal, widely-traded
cryptocurrency in most jurisdictions, and using it to pay real, legitimate
merchants privately isn't itself a legal or ethical gray area.

## What Monero actually is

A cryptocurrency built specifically around **untraceability**, not just
"crypto in general": it cryptographically hides both transaction amounts
and wallet addresses, so external chain analysis can't link payments to
identities the way it routinely can on Bitcoin/Ethereum. The three
selling points the community makes: **financial sovereignty** (no bank/
government visibility into spending), **security** (privacy as protection
against targeted theft/extortion/ad-targeting based on your finances, not
just abstract principle), and **fungibility** (every coin is worth the same
as every other — no "tainted coin" blacklisting based on transaction
history, which is a real, ongoing problem for Bitcoin). The community
explicitly frames XMR as a payments tool, not a speculative investment.

## Buying it

Two paths, per the community's own exchange map (monero.eco/exchanges):
**centralized exchanges** (easier, but require identity verification/KYC at
most reputable ones) and **decentralized/P2P exchanges** (harder, but
preserve the privacy XMR is actually for — buying it on a KYC exchange and
never moving it is a common way people undermine the privacy they bought it
for in the first place). **kycnot.me** is the actually useful cross-cutting
resource here — a maintained, rated directory of 500+ services (exchanges,
VPNs, hosting, more) that don't require identity verification, filterable
by network (clearnet/Tor/I2P) and coin supported. Crypto ATMs
(coinatmradar.com) are a third option if you want to buy with cash directly.

## Mining it

The community's stated motivation isn't primarily profit — it's
**network security** (more independent miners = more expensive to attack
the network) and, as a side effect, supporting XMR's value. Practically
accessible now via **Gupax** (simplifies P2Pool solo/pooled mining setup)
or **MoneroOcean** (mine other GPU-friendly coins, get paid out in XMR
automatically). Hardware recommendations range from high-end (Ryzen 9
7950X) to genuinely budget CPUs — this isn't presented as something that
requires expensive ASICs the way Bitcoin mining does; XMR is deliberately
CPU/GPU-mineable to keep mining decentralized.

## Wallets

- **Desktop**: the official GUI/CLI wallet, Feather Wallet (lighter-weight,
  popular community alternative), Stack Wallet.
- **Mobile**: Cake Wallet, Monero.com's own app, Stack Wallet, Unstoppable,
  Edge, and two Android-only options (Monerujo, Monfluo).

## Storing it securely

The core principle, stated bluntly by the source: **"If you lose your seed
phrase, forget it, or it gets stolen, it's over."** Options in ascending
effort/security:
- **Hardware wallets** (Ledger/Trezor) — note XMR isn't supported by the
  vendors' own native apps, you need compatible third-party wallet software
  alongside the hardware device.
- **Paper wallets** generated on an air-gapped (never-networked) machine.
- **Dice-generated seeds** — 98+ physical dice rolls converted to a hex
  private key, for people who don't trust any software RNG at all.
- **TAILS OS** (a privacy-focused live-USB Linux distro) + an encrypted
  partition + a desktop wallet, for a fully ephemeral/no-trace setup.
- **Purpose-built hardware**: Pitrezor (Raspberry-Pi-based), XmrSigner, and
  QR-code/Bluetooth "air-gapped signing" tools (Anonero, Cupcake, Sidekick)
  that let a networked device build a transaction while the actual signing
  key never touches the internet.
- **A dedicated Android device** with strong lock security and an
  emergency-wipe feature, as a lower-effort middle ground.

The unifying theme across all of these: keep the private key/seed on
something that has never been and will never be connected to the internet.

## Spending it (legitimate merchants)

- **monerica.com**, **cryptwerk.com** (filterable by "pay with XMR"),
  **xmrbazaar.com** — general merchant/marketplace directories.
- **cakepay.com**, **coincards.com**, **xmr.cards** — convert XMR into
  gift cards for major retailers, useful for spending XMR at stores that
  don't accept crypto directly.
- **monero.observer/resources** — the most comprehensive single directory
  (351 resources): exchanges, wallets, mining pools, dev tooling, merchants,
  and community/education links, including onion addresses for Tor access.

## Supporting development

Monero has no company/foundation behind it in the traditional sense — it's
funded through community mechanisms: the **CCS** (Community Crowdfunding
System, ccs.getmonero.org), the **Monero Fund**, working groups listed on
the official site, and **MAGIC Grants** (a 501(c)(3) that accepts
tax-deductible crypto donations and funnels them to Monero and other
open-source privacy projects).
