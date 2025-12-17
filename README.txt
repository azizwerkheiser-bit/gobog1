# GOBOG Website (Static)

Isi folder ini ke GitHub Pages / Netlify / Vercel / Cloudflare Pages.

## 1) Edit config
Buka `config.js` dan isi:
- TOKEN_ADDRESS
- PRESALE_ADDRESS
- USDT_ADDRESS (testnet: MockUSDT, mainnet: Binance-Peg USDT)
- CHAIN_ID (97 testnet / 56 mainnet)
- EXPLORER_BASE

## 2) Upload
### GitHub Pages
- Buat repo baru
- Upload semua file
- Settings -> Pages -> Deploy from branch (main / root)

## 3) Presale UI
Open `presale.html` lalu:
- Connect wallet
- Approve USDT
- Buy
- Setelah finalize: Claim

Catatan:
- User perlu sedikit BNB untuk gas.
