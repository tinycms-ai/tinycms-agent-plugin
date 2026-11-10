# tinycms.ai

Run your website and social media from a conversation. tinycms is where the website lives: it hosts the site, manages everything on it, and is built for AI agents to work in. Your agent is the designer and the writer. It can give the site the look and layout that suits you, from colors, type, header and footer to the structure of each page and custom styling on top, and tinycms serves the result to your visitors. There is no separate host to set up and nothing to deploy.

With this plugin, your agent can also draft pages, articles and forms on your tinycms site, run the checks, show you a preview on the real site, and publish or schedule once you approve. On the Pro plan it can write and schedule social posts and plan campaigns.

tinycms is also the gate between your agent and the public internet. Whatever it writes or designs waits there as a draft, and nothing goes live until you approve it. Every publish is recorded with who approved it, when, and the exact version they saw. Earlier versions are kept, so you can look back at how a page, an article or the site's design changed over time and see who changed it.

## What you need

- A tinycms account. If you don't have one, connecting makes a free one: enter your email and the 6-digit code tinycms sends. More at https://www.tinycms.ai.

## Install

1. Add the **tinycms** plugin from the marketplace.
2. Connect **tinycms** when asked. A window opens: enter your email and the code tinycms sends, then pick the site this connection works on. A new account starts with one site for your agent to set up.
3. Ask for something. For example: "Write a page about our opening hours and show me a preview."

Each connection is bound to one site. To work on another site, add another connection and pick that site when you sign in.

## What the plugin does

The plugin bundles the tinycms connector (the MCP server at `https://mcp.tinycms.ai/mcp`) with four skills that teach your agent how to use it well:

- **working-with-tinycms**: draft articles, pages and forms; fix the blocking checks; copy-edit the final text; show the preview link; ask for your approval of the exact version before publishing or scheduling.
- **social-posts**: write and schedule social posts on your connected channels, link them to the right article, and run campaigns.
- **site-and-pages**: design the site, from a template or from nothing: its look, layout, header, footer, navigation and home page, with custom CSS for whatever the settings do not cover; add media.
- **troubleshooting**: what your agent does when a call answers "Ask first" or "Not allowed", when a publish is refused, when a social channel has expired, or when you want to send feedback to the tinycms team.

## Configuration

There is nothing to configure and no key to enter. Sign-in happens in the tinycms window when you connect.

## How much your agent may do on its own

Every connected agent starts on **Ask first**: it drafts and proposes, and you approve in tinycms before anything changes. You can change that per agent in the tinycms app under **Account › AI Agents**. Publishing always needs your approval of the exact version you saw.

## Data

The plugin sends the content you ask your agent to write or change (page text, article text, form fields, social post text, media links and site settings) to your tinycms account through `https://mcp.tinycms.ai`. It reads your site's content, settings, media library, social channels and approval history from the same place. It sends nothing anywhere else, runs no code on your computer, and stores nothing itself. Feedback to the tinycms team is sent only after you have seen the exact text and agreed.

## Privacy Policy

tinycms handles your account and site data as described in its privacy policy at https://www.tinycms.ai/privacy. Terms of service: https://www.tinycms.ai/terms.

## Support

Help center: https://tinycms-help.tinycms.ai. Problems with the plugin itself: open an issue in this repository.

## License

MIT. See LICENSE.
