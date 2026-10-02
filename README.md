# Developmental by Design — CHI 2027 Workshop website

The workshop site lives in `index.html`. It is hosted with GitHub Pages from the `main` branch,
root folder.

Repository: https://github.com/Developmental-by-Design/chi2027
Live site: https://developmental-by-design.github.io/chi2027/

## Turn on Pages (one time)

Repository → *Settings* → *Pages*. Under *Build and deployment*, choose *Deploy from a branch*,
branch `main`, folder `/ (root)`, and click *Save*. After a minute or two the Pages settings
screen shows the live URL. That URL goes into the proposal's "Workshop website" field.

## Updating the site later

Open `index.html` in the repository, click the pencil icon, edit, and *Commit changes*.
The live site updates within a couple of minutes. Or ask Claude to edit the file and push it.

## When submissions open

1. Create the submission form (Google Form with file upload, or EasyChair).
2. In `index.html`, find `var SUBMIT_URL = "";` near the bottom and paste the form link between the quotes.
   The grey button becomes a live "Submit your paper" button.
3. Replace "To be announced" in the Key dates table with the real dates.
4. Change the status line near the top from "Proposed workshop…" to "Accepted workshop at CHI 2027."

## Optional: custom domain

Buy a domain (e.g. developmentalbydesign.org), then in *Settings → Pages → Custom domain* enter it,
and follow GitHub's instructions to add the DNS records at your domain registrar.
