# Onlure for Claude

Performance-based marketing with creators, from a conversation with Claude: search 2000+ creators, draft campaigns for store visits or online sales on the Onlure Marketplace, and read each campaign's results by creator and channel. Every verified walk-in, online sale and app install is credited to the creator or ad that drove it.

## Install

In Claude Code:

```
/plugin install onlure --marketplace onlure/claude-plugin
```

In Claude on the web or desktop, add `https://mcp.onlure.ca/mcp/claude` as a custom connector and choose **Sign in when needed**, so creator search works right away and your business account connects the first time you ask about your campaigns.

## What's inside

- **The Onlure connector**: Onlure's hosted server at `https://mcp.onlure.ca/mcp/claude`. Add it from the plugin's Connectors tab.
- **Two skills**: `onlure`, which tells Claude how to search creators and run a business's campaigns, and `get-started`, which shows someone new what Onlure does with real results.

The plugin runs no code on your computer.

## Use it

- **Without an account:** ask Claude for creators for your business, like "Find food creators in Kensington Market for my bakery". You'll get public profile facts, never prices or contact details.
- **With your Onlure business account:** ask about your campaigns, walk-ins or applicants. Claude shows a Connect card, you sign in on onlure.ca, and Claude carries on. It can draft and edit campaigns, show who applied, keep a shortlist of creators, manage your store links and read verified walk-ins by creator and channel. Changes that are hard to undo, such as declining an applicant or closing a listing, are shown to you first and need your confirmation.
- **Payments:** when payments are on for Claude, it can launch a campaign, book or pay a creator and top up your balance. Each payment is shown to you first and charged to the card saved on your Onlure account only after you confirm it. Otherwise these happen on onlure.ca.

Setup guide: https://onlure.ca/docs/ai-assistants

## Data

When Claude uses an Onlure tool, it sends Onlure the request it is making and the details it filled in, such as the search terms of a creator search or the fields of a campaign draft. Onlure doesn't receive the rest of your conversation. Connecting your business account uses Onlure's sign-in (OAuth): Claude receives a short-lived access key, never your password, card number or payout details. Disconnect any time from AI assistants on your Onlure Integrations page.

- Privacy policy: https://onlure.ca/privacy#ai-assistants
- Terms: https://onlure.ca/terms
- Support: support@onlure.ca or https://onlure.ca/support
