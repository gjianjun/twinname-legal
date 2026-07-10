# TwinName Legal

Static legal pages for Google Play:

- Privacy Policy
- Data Safety
- Delete Account

Public site after GitHub Pages is enabled:

- https://gjianjun.github.io/twinname-legal/
- https://gjianjun.github.io/twinname-legal/privacy/
- https://gjianjun.github.io/twinname-legal/data-safety/
- https://gjianjun.github.io/twinname-legal/delete-account/

## Before you publish

1. Support email is `gjianjun666@gmail.com` (display name: TwinName Support)
2. Confirm pages disclose Google sign-in / link / merge / controlled switch
3. Confirm Unlock Restore (Play) is distinguished from Credits restore (Google-linked TwinName account)
4. Confirm deletion wording: no automatic refund; Play/legal refunds handled separately
5. Commit and push to the `main` branch of `https://github.com/gjianjun/twinname-legal`
6. Remember: the delete-account page only collects requests by email; you must delete user data in Firebase / backend using the Account ID within 30 days for verified requests

## Enable GitHub Pages

1. Open the repository on GitHub
2. Go to **Settings → Pages**
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
4. Save
5. Wait 1–2 minutes, then open the links above

## Upload these files

Upload everything in this folder to the repository root:

```text
index.html
styles.css
README.md
privacy/index.html
data-safety/index.html
delete-account/index.html
```
