# Travel Booking Shared Library

This repository contains shared components, utilities, and types used across the Travel Booking microfrontend architecture.

## Installation

```bash
npm install
```

## Build

```bash
npm run build
```

## Testing

```bash
npm test
```

## Usage

Import the shared components and utilities in your microfrontend:

```typescript
import { formatCurrency, ApiService, Tour } from '@travel-booking/shared-lib';
```

## CI/CD

This repository uses GitHub Actions for CI/CD pipeline, which will:
- Build and test the code on every PR and push to main
- Collect build metrics
- Deploy to GitHub Packages on push to main