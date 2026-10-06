# Routing API - Postman Collection

Ready-to-import Postman collection for testing and integrating with the Routing API.

## Quick Start

### Import into Postman

1. Download `routing-api.postman_collection.json`
2. Open Postman
3. Click **Import** → **Upload Files** → Select the JSON file
4. Import the environment `routing-api-environment.json`

### Setup

1. Get your API key from https://dashboard.routingapi.com
2. In Postman, go to **Environments** → **Routing API**
3. Set `api_key` to your key
4. Set `base_url` to:
   - Production: `https://api.routingapi.com`
   - Sandbox: `https://sandbox.routingapi.com`

### First Request

1. Open the collection → **Payment Routing** → **Route Payment**
2. Click **Send**
3. See the response

## Collection Contents

### Authentication
- API Key setup guide

### Payment Routing
- Route payment (POST)
- Get routing info (GET)
- Update routing rules (PUT)

### Compliance
- Check sanctions (POST)
- Get compliance status (GET)
- KYC verification (POST)

### Transactions
- Create transaction (POST)
- Get transaction (GET)
- List transactions (GET)
- Refund transaction (POST)

### Webhooks
- Get webhook (GET)
- Send test webhook (POST)
- List webhook deliveries (GET)

### Admin
- Create API key (POST)
- Rotate API key (POST)
- Delete API key (DELETE)

## Pre-request Scripts

Tests are included for:
- Request signing
- Response validation
- Error handling

## Environment Variables

```json
{
  "base_url": "https://api.routingapi.com",
  "api_key": "your-api-key",
  "merchant_id": "your-merchant-id",
  "sandbox_enabled": false
}
```

## Documentation

Full API reference: https://docs.routingapi.com

## Support

Email: support@webundle.org
