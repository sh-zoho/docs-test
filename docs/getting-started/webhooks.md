# Webhooks

Webhooks allow Acme to notify your application when events occur in real time.

## Setting up a webhook

1. Go to Settings → Webhooks in your dashboard
2. Click "Add endpoint"
3. Enter your endpoint URL
4. Select the events you want to receive

## Event types

- `user.created` — Fired when a new user is created
- `user.deleted` — Fired when a user is deleted
- `payment.completed` — Fired when a payment completes successfully

## Payload structure

Every webhook payload includes:

```json
{
  "event": "user.created",
  "timestamp": "2026-05-20T10:00:00Z",
  "data": {}
}
```

## Verifying webhook signatures

Always verify the `X-Acme-Signature` header to ensure the payload is genuine.

TC-26 large PR test
