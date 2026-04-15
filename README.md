# mkt-anvil

Standalone Anvil + local contract deploy service extracted from `mkt`.

## Local

```bash
npm ci
npm run local:chain:fresh
```

## Railway

- Build command: `npm ci`
- Start command: `npm run railway:local:chain:fresh`

This service starts Anvil on `0.0.0.0:$PORT`, deploys contracts, and keeps the chain running.
Use this service URL as `RPC_URL` for the separate FE/BE service.
