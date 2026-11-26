# Pabs

Pabs is your product and design lead. It helps you choose what is worth building, keeps your product direction clear, applies design guidance to the work, and records what you learn against the right Pabs product.

This plugin connects your AI tool, such as Claude or ChatGPT, to your Pabs account. You choose which Pabs product each conversation works with, on the Pabs website, never by guesswork from a folder or chat name.

## What is included

- **pabs-init**: connects the conversation to an existing Pabs product, or sets up a new one with its Brief and strategy.
- **pabs**: Pabs as product owner. Use it when you propose or reconsider a feature, audience or direction, ask what to focus on next, make a product decision or report results.
- **pabs-design**: Pabs as design lead. Use it before building or changing a screen, page, flow or component, and to review interfaces, UX copy and design systems.
- **The Pabs connector**: a remote MCP server at `https://www.pabs.co.nz/api/plugins/mcp`. Nothing runs on your computer.

## Install

In Claude Code, type:

```
/plugin install pabs --marketplace getpabs/pabs-plugin
```

In ChatGPT, find Pabs in Plugins, or open [Pabs in ChatGPT](https://chatgpt.com/plugins/plugin_asdk_app_6af4256d528881919477148dc469051d).

## Getting started

1. Install the plugin and connect Pabs. You sign in to Pabs in your browser; your AI tool never sees your password.
2. Ask: "Set up Pabs for this product."
3. It shows a Pabs link and a confirmation code. Open the link, choose your product (or start a new one) and connect only if the page shows the same code.

You need a Pabs account. Sign up at [pabs.co.nz](https://www.pabs.co.nz).

## What the plugin sends and where

- The plugin talks only to Pabs at `www.pabs.co.nz`, using the sign-in you approve. You can revoke that sign-in from Pabs at any time.
- When you ask it to, your AI tool sends Pabs project summaries, decisions, learnings and evidence for the product you chose. Pabs stores them with that product.
- Pabs reads back that product’s saved Brief, strategy, Pulse, decisions and guidance so your AI tool can work with them.
- Some requests ask Pabs for an analysis, such as checking a feature idea. Pabs runs those with its AI model providers, which process the content and do not train on it. Pabs credits are used as shown in your account.
- The skills read Pabs's current guidance through the connector, so they stay in step with your Pabs account. They do not install or run code on your computer.

Full details are in the [privacy policy](https://www.pabs.co.nz/privacy).

## Links

- Website: [www.pabs.co.nz](https://www.pabs.co.nz)
- Install guide: [www.pabs.co.nz/docs/install-pabs](https://www.pabs.co.nz/docs/install-pabs)
- Support: [www.pabs.co.nz/contact](https://www.pabs.co.nz/contact)
- Privacy policy: [www.pabs.co.nz/privacy](https://www.pabs.co.nz/privacy)
- Terms of service: [www.pabs.co.nz/terms](https://www.pabs.co.nz/terms)

## License

Proprietary. See [LICENSE](LICENSE).
