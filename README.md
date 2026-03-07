# DeployWise — Angular Template

A production-ready Angular starter, pre-configured for one-click deployment to your VPS with [DeployWise](https://deploywise.dev).

## What's Included

- Angular 21 with TypeScript
- Angular CLI configured
- Optimized for Nginx static hosting or PM2 SSR

## Quick Start

```bash
npm install
npm start
```

Open [http://localhost:4200](http://localhost:4200).

## Deploy with DeployWise

1. Push this repo to GitHub
2. Open [deploywise.dev/dashboard](https://deploywise.dev/dashboard)
3. Add your VPS → Create a project → Select this repo
4. Click **Deploy**

DeployWise automatically runs `ng build`, serves the `dist/` output via Nginx, and issues a free SSL certificate.

## Project Structure

```
├── src/
│   ├── app/          # Components and modules
│   ├── index.html    # Entry HTML
│   └── main.ts       # Bootstrap
├── angular.json      # Angular CLI config
└── package.json
```

## Learn More

- [DeployWise Docs](https://deploywise.dev/docs)
- [Angular Documentation](https://angular.dev)

---

Deployed with [DeployWise](https://deploywise.dev) — free, open source.
