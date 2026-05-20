# Automation & QA Assignment
Developed an automated crypto alert workflow using n8n, CoinGecko API, and Discord Webhooks. The workflow fetches cryptocurrency market data, filters top results, applies conditional logic on price changes, and automatically sends real-time alerts to Discord using API integration and workflow automation.


## APIs Used
- CoinGecko API
- Discord Webhook

## Workflow Logic
1. Schedule Trigger runs every minute.
2. HTTP Request fetches cryptocurrency market data.
3. Code node filters top 5 items.
4. IF node checks if price change percentage is greater than 0%.
5. Discord notification sends alert messages.

## Error Handling
Basic conditional branching and workflow validation implemented.

## Tools Used
- n8n
- Discord
- CoinGecko API
