# Troubleshooting

## Authentication errors

**Error: 401 Unauthorized**
Your API key is missing or invalid. Check that the Authorization header is correctly formatted.

**Error: 403 Forbidden**
Your API key does not have permission for this action. Check your key's permission scope in the dashboard.

## Rate limiting

**Error: 429 Too Many Requests**
You have exceeded the rate limit of 100 requests per minute. Implement exponential backoff in your client.

## Common integration issues

**SDK not initialising**
Ensure your API key is set in the environment variable ACME_API_KEY before importing the SDK.

**Webhook not firing**
Check that your endpoint URL is publicly accessible. Localhost URLs will not receive webhooks.
