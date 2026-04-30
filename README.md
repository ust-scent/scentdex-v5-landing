# SCENTDEX V5 — Landing page

Coming-soon landing page for [dex.scenttoken.com](https://dex.scenttoken.com/).

Operated by **Universal Scent Technology** (Singapore).

## Status

This is a temporary single-page placeholder while the full SCENTDEX V5 frontend is under construction. The contract source lives at [`ust-scent/scentdex-v5`](https://github.com/ust-scent/scentdex-v5).

## Deployment

- **Host**: Vercel (Hobby plan)
- **Domain**: `dex.scenttoken.com` (DNS managed at お名前.com, CNAME → Vercel)
- **Pipeline**: every push to `main` auto-deploys via GitHub ↔ Vercel integration.

## Local preview

```bash
# Any static server works; for example:
npx serve .
# Then open http://localhost:3000
```

No build step. `index.html` is the entry point.

## Roadmap (visible to public on launch)

| Phase | Item |
|---|---|
| ✅ Done | V5 contract r6 — internal audit, 4 rounds /ultrareview clean, 5-tools clean |
| 🔜 Next | Sepolia testnet burn-in (2 weeks) |
| 🔜 Next | Public DEX UI replaces this landing |
| ⏳ Pending | External formal audit (budget-gated) |
| ⏳ Pending | Mainnet launch + bug bounty program |

## Contact

Security disclosures and general inquiries: **cs@scenttoken.com**

## License

[MIT](./LICENSE)
