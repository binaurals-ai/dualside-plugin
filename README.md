# Dualside

Dualside is AI built specifically for B2B negotiation. This plugin brings Dualside into Claude: a negotiation
strategy for your deal, Dualside's read on emails, messages and documents, and practice against the other side,
each in Dualside's own card in your chat.

## What you need
- A paid Dualside plan at https://dualside.ai, with a work email. Dualside uses credits from your account.
- The Claude apps. Not Claude Code: Dualside's sign-in returns only to claude.ai.
- In Claude, Settings → Capabilities → "Create and edit files" turned on, so Claude can use this plugin's skill.

## Set it up
1. Add the plugin: Customize → Plugins.
2. Open Dualside, select its Connectors tab, and click Connect. Adding the plugin doesn't connect Dualside by itself.
3. Sign in to Dualside with your work email and click Allow. The Connectors tab then shows Connected.

## How it works
Tell Claude about a deal you're working on. Claude offers Dualside and starts it only when you say yes or ask
for Dualside by name. Dualside asks about the deal in its card, then shows your strategy there; ask follow-up
questions in the chat. You can also ask for Dualside's read on emails, Slack messages, documents or call
transcripts, practice your emails against the other side after a strategy, or practice replying to a real email
thread. Practice emails are never sent to anyone.

## What the plugin runs, sends and fetches
- It runs no code, scripts or hooks. It holds instructions for Claude (one skill) and the address of Dualside's
  connector, https://dualside.ai/mcp.
- When you use Dualside, Claude sends Dualside, through that connector only:
  - your own messages about the deal
  - emails, Slack messages, documents and call transcripts you ask Dualside to read, exactly as their source
    shows them; Claude fetches them with connectors you have already added in Claude, such as Gmail, Slack or
    Google Drive
  - for practice: the email thread you ask to practice, and the emails you write in the practice
  - files you add in Dualside's card
- Nothing is sent anywhere else.

## Credits (in Claude)
4 for each message you send and 4 for each reply from Dualside; a strategy, each follow-up on it, or a full read
costs 10 more. Opening a practice is free; each practice email costs 4 + 4 and the debrief at the end costs 8.
Company research costs 10. Credits come back when a step fails.

## Your data
A strategy you start in Claude is saved, encrypted, as a conversation in your Dualside account, so you can continue
it on dualside.ai or in the same Claude chat; delete it there any time. Emails, messages, documents and transcripts
Claude shares for a read, and an email thread you practice, are kept 24 hours only and never saved. Practices from a
strategy are saved to your account. Privacy policy: https://dualside.ai/privacy-policy

## Support
Help: https://dualside.ai/claude · support@dualside.ai

## License
MIT
