# Maton Slack

Slack API integration with managed OAuth authentication.

Send messages, manage channels, list users, and automate Slack workflows with a single API key.

## Quick Start

```bash
# Post a message to a channel
curl -s -X POST 'https://gateway.maton.ai/slack/api/chat.postMessage' \
  -H 'Content-Type: application/json' \
  -H 'Authorization: Bearer YOUR_API_KEY' \
  -d '{"channel": "C0123456789", "text": "Hello from Maton!"}'
```

## Getting Your API Key

1. Sign in or create an account at [maton.ai](https://maton.ai)
2. Go to [maton.ai/settings](https://maton.ai/settings)
3. Click the copy button to copy your API key

```bash
export MATON_API_KEY="YOUR_API_KEY"
```
