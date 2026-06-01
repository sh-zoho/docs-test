# Quickstart Guide

Get your first integration working in under 5 minutes.

## Step 1 — Install the SDK

```bash
npm install acme-sdk
```

## Step 2 — Configure your environment

Create a `.env` file in your project root:

ACME_API_KEY=your_api_key_here
ACME_ENVIRONMENT=production

## Step 3 — Make your first request

```javascript
const result = await client.users.list({ limit: 10 });
console.log(result.users);
```

## Next steps

- Read the full API Reference
- Set up webhooks for real-time events
- Join the Acme developer community

TC-26 large PR test
