# rays-bot-hunts

The command reference for **RaysChatBot** — the chat bot on the shiny-hunting
Twitch stream. It's a single static web page that lists the commands viewers can
type in chat (`!count`, `!odds`, `!guess`, and more) so anyone watching can play
along.

**Live site:** https://raymondjp33.github.io/rays-bot-hunts/
The bot's `!help` command links here.

## What's in here

- **`index.html`** — the entire site, self-contained (all CSS and JavaScript
  inline, no external requests) so it renders anywhere and stays fast.
- **`.nojekyll`** — serve the page exactly as written, skipping the Jekyll build.

The command list is maintained by hand to match what the bot supports.
