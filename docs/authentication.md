# Authentication

Acme uses API keys to authenticate all requests. Your API key carries full access to your account.

"This line tests commit message visibility."

## Obtaining your API key

1. Log in to your Acme dashboard
2. Navigate to Settings → API Keys
3. Click "Generate new key"
4. Copy and store the key securely — it will not be shown again

## Using your API key

Include your API key in every request using the Authorization header:

Authorization: Bearer YOUR_API_KEY

## Token expiry

API tokens expire after 30 minutes of inactivity. Refresh them using the refresh endpoint.

## Security best practices

Never expose your API key in client-side code

## Multi-factor authentication

Acme supports MFA via TOTP authenticator apps.
Enable MFA in Settings → Security → Two-factor auth.
