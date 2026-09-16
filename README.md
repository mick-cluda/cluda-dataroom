# cluda-dataroom

The public copy of the Cluda data room, served by GitHub Pages so `cluda.ai/dataroom` can embed it as a URL rather than pasted HTML.

- **The page is generated.** Do not edit `index.html` here. The master lives in Mick's operating system at `fundraising/found-capital/data-room/cluda-data-room.html`.
- **To republish after a change to the master:** `python3 team/dataroom-host/build.py --apply --push` from the operating system. GitHub Pages redeploys in about a minute. The Framer page needs no change, because it embeds the URL.
- **What the build removes:** the review and notes tooling, so nobody can open edit mode on a public URL. It adds a `noindex, nofollow` tag, so search engines skip the page.
- **This URL is public to anyone who has it.** The page carries no cash, runway or cap table figures. It does state the seed round, the pre-seed history and the April allocation.
