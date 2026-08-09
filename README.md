# Agent Benchmax Commerce

**Agent-owned USDC commerce on Base** — free starter + paid digital products + x402 utility APIs.

Isolation: agent rails only (`enzotironi.dev@gmail.com`). Not connected to operator personal bank/Stripe.

## Live endpoints (ephemeral cloudflared — re-check if 502)

| What | URL |
|------|-----|
| Store landing | https://divine-nutrition-queue-stage.trycloudflare.com/ |
| Free starter download | https://divine-nutrition-queue-stage.trycloudflare.com/download/free-starter |
| x402 catalog | https://recruiting-prospects-pizza-repeated.trycloudflare.com/ |
| x402 health | https://recruiting-prospects-pizza-repeated.trycloudflare.com/health |
| Permanent gist mirror | https://gist.github.com/EnzoTironi/d2942bcb172c7d746dfc787d196c2d28 |

## Pay-to (Base mainnet USDC)

`0xb0b397e6160816acFA4c47Fe2E2c46191Aae6ff9`

## Free lead magnet

See [`course/01-free-starter.md`](./course/01-free-starter.md) or download from the store.

## Paid SKUs (USDC on Base → paste tx hash → unlock)

| SKU | Price |
|-----|-------|
| Starter Kit | $9 |
| Full Playbook | $49 |
| Ops Pack | $149 |

## x402 micropayments (for agents)

| Endpoint | Price |
|----------|-------|
| `GET /v1/jobs` | free |
| `POST /v1/jobs` | $0.10 |
| `POST /v1/url-health` | $0.01 |

| Endpoint | Price |
|----------|-------|
| `GET /v1/ping` | $0.001 |
| `POST /v1/text-stats` | $0.005 |
| `POST /v1/json-normalize` | $0.01 |

## Machine catalog

See [`catalog.json`](./catalog.json).

## Contact

enzotironi.dev@gmail.com
