# StellaFrame

Beautiful widgets for your website, on any site with two lines of HTML.

[StellaFrame](https://stellaframe.com) makes eight embeddable widgets: Google reviews, an Instagram feed, a YouTube gallery, an audio player, an FAQ, a WhatsApp chat button, a countdown timer and a class schedule. Start free with 1 widget. Pro is $5/mo flat for up to 3 widgets.

## Let your AI agent do it

StellaFrame has a remote [MCP](https://modelcontextprotocol.io) server. Connect Claude, Claude Code, Cursor or another AI agent, sign in with your StellaFrame account, and ask for the widget you want in plain words.

    https://app.stellaframe.com/mcp

- One address for every agent
- Sign in with your normal account. There is no API key to copy
- Works on the Free plan

### Connect

**Claude** (web, desktop or mobile)

1. Open Settings, then Connectors.
2. Choose Add custom connector and paste the address.
3. Choose Connect and sign in with your StellaFrame account.

**Claude Code**

```sh
claude mcp add --transport http stellaframe https://app.stellaframe.com/mcp
```

Then run `/mcp` in Claude Code to sign in.

**Cursor and other agents**

Add a remote MCP server with the address, and sign in when it asks.

### Then just ask

- "List my StellaFrame widgets."
- "Add a Google reviews carousel for my bakery to the homepage."
- "Make an FAQ widget from the questions on my pricing page and install it there."
- "Put a WhatsApp chat button on every page of this site."
- "Change my Instagram feed to three columns."

An agent that can edit your site's code installs the widget itself. For Squarespace, Wix, WordPress, Shopify or Webflow it gives you the embed code and the steps.

### What your agent can do

| Tool | What it does |
| --- | --- |
| `get_account` | Reads your plan and how many widgets it allows |
| `list_widgets`, `get_widget` | Reads your widgets, their settings and whether a page has shown them this month |
| `get_widget_options` | Looks up what one kind of widget needs |
| `search_businesses` | Finds your business on Google, for a reviews widget |
| `find_instagram_account` | Shows you an Instagram account before a feed is made from it |
| `create_widget`, `update_widget`, `delete_widget` | The same changes you can make in the dashboard, with a preview link |
| `get_install_instructions` | Embed code and steps for your site |
| `get_upgrade_link` | A link you open yourself to upgrade |
| `get_narration_help` | Help with making and hosting audio |
| `send_feedback` | Passes a request or a problem on to us |

Your agent cannot see your password or payment details, change your plan, charge a card or delete your account.

### You stay in control

- Every connection is approved on a StellaFrame consent screen first.
- The dashboard's AI agents page lists every connected agent, each with a Disconnect button.
- Before creating a widget, your agent can show you the account or business it found. After, it gives you a preview link.

## Links

- [How to connect your AI agent](https://stellaframe.com/ai-agents)
- [All eight widgets](https://stellaframe.com/widgets)
- [Privacy](https://stellaframe.com/privacy) and [Terms](https://stellaframe.com/terms)
- Support: support@stellaframe.com

The source code for StellaFrame is not public. This profile is documentation only.
