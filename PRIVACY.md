# AlgoAlpha Chat for TradingView: Privacy Policy

Last updated: 6 November 2026

AlgoAlpha Chat is a browser extension that adds an AI Pine Script assistant to TradingView. This policy explains what data the extension handles and where it goes.

## What the extension stores

- **Your settings:** which AI provider and model routing you chose.
- **Your API key** for Anthropic or OpenAI.
- **A copy of a script you replaced**, so you can restore it.
- **The chat panel's height** in the Pine Editor.

All of this is kept in your browser's local extension storage on your own device. We do not receive it.

## What is sent, and to whom

When you send a message, the extension sends a request to the AI provider you chose: Anthropic (api.anthropic.com) or OpenAI (api.openai.com). The request includes:

- your message, plus any images or .pine files you attached;
- the Pine Script in your editor or attached file, and any code you selected;
- details of your chart that help answer you: symbol, timeframe, the indicators on it, the live quote, and chart data when you ask about it;
- recent messages from the same chat, so the assistant has context;
- your API key, which authorises the request with the provider.

These requests go directly from your browser to the provider. They are not sent to us or to any other party, and we cannot see them. The provider's own privacy policy and data terms apply:
- Anthropic: https://www.anthropic.com/legal/privacy
- OpenAI: https://openai.com/policies/privacy-policy

The extension also reads data on tradingview.com pages to work with your chart, such as the Pine Editor contents, indicators and quotes. It looks up 24-hour volume figures from TradingView's own symbol data service. That data is only used to answer your requests.

## What we do not do

- No accounts or sign-in with us.
- No analytics, tracking, advertising or telemetry.
- We do not sell or share data, and do not use it for anything other than the assistant's features.

## Your control

- Remove your API key at any time with "Clear keys" in the extension's settings.
- Clear a conversation with the trash icon.
- Uninstalling the extension deletes everything it stored.

## Contact

Questions about this policy: <add AlgoAlpha's support email or page>.
