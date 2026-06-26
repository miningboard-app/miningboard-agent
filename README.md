# mb-agent (binaries)

Public, **non-Cloudflare** mirror of the MiningBoard on-box executor agent binary, so rented boxes
in Cloudflare-stalling regions (e.g. Moscow/MSK, where `cdn.miningboard.com` wedges mid-transfer)
can fetch it over GitHub's CDN. `cdn.miningboard.com` is the fallback.

Binaries are attached to **Releases**. Each is **SHA-256 pinned** and verified on the box by
`onstart.sh` before execution (supply-chain rule) — public hosting is access convenience, not the
integrity boundary. Source is private.

Latest: see [Releases](../../releases).
