# Angular 21 ERP/CRM Inventory Remote

Author: Amit Mahida

Inventory remote micro-frontend for the Angular 21 ERP/CRM demo.

This repository is an independently deployable Angular 21 Native Federation remote. It exposes:

```text
./Routes -> projects/inventory-app/src/app/remote-entry.routes.ts
```

The shell mounts this remote at `/inventory`.

## Local Development

```bash
npm ci
npm run start
```

Standalone URL: `http://localhost:4202`

## Build And Test

```bash
npm run build
npm run test:ci
```

## GitHub Pages

```bash
npm run build:gh-pages
```

Remote entry: https://amitmahida92.github.io/angular21-erp-crm-inventory-app/remoteEntry.json

Repository: https://github.com/amitmahida92/angular21-erp-crm-inventory-app
