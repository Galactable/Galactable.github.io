# ley

An index of the tools I build, at **[galactable.github.io](https://galactable.github.io/)**.

One HTML file. No framework, no build step, no dependencies, and nothing loaded
from a CDN — the whole page is what you see in `index.html`.

## What's linked

| | | |
|---|---|---|
| [./fam](https://galactable.github.io/fam/) | Financial Allocation Monitor | Budget tracker built on a rolling pay cycle instead of a calendar month, for people paid weekly rather than monthly. Encrypted client-side, syncs across devices. |
| [./rol](https://galactable.github.io/rol/) | Rolling Obligations Log | A rolling 2–4 week calendar with today at the top. Every day listed, repeating events, per-occurrence ticks. |
| [./arc](https://arcrepo.pages.dev/) | Arcane Repo Courier | Carries HTML to your git repos on the fly using fine-grained personal access tokens. |
| [./phx](https://galactable.github.io/pokehex/) | PokéHex | Card-collecting game with a simulated market economy — prices move with supply, rarity and player trades. |

## The page itself

The four cards above are hardcoded. You can add your own with MANIFEST and drag
any card to reorder the grid — that saves to your browser's localStorage and
goes nowhere else. There's no account and no server. Nothing you add is visible
to me or to anyone else, and clearing your browser data clears it.

Anything typed into the manifest form is escaped before it reaches the DOM, and
links have to be absolute `http://` or `https://`.

Other things in there: a command palette on Ctrl+K, a handful of terminal
commands (`dicebag`, `sysinfo`, `manifest`, `help`), fourteen themes, and a
sacred-geometry sigil that generates a new figure on every load. Run `sysinfo`
if you want the page to describe itself.

## Running it

Clone it and open `index.html`. That's the whole thing.
