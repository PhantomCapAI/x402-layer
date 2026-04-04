# x402 Layer

USDC micropayment layer for Phantom Capital. Implements the x402 HTTP payment protocol — $0.01 USDC per query on Base.

## Tech Stack
- TypeScript, Express
- Solana Web3.js + SPL Token
- Docker + Zeabur
- tsx runtime

## Env Vars
See `.env.example`. Requires:
- Solana/Base wallet credentials
- USDC contract addresses
- Pricing configuration

## Development
```bash
npm install
npm run dev    # Watch mode
npm run start  # Production
npm run build  # Compile TypeScript
```

## Deployment
Deployed on Zeabur via `zbpack.json` + Dockerfile.

