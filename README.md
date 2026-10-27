# autopost-legal

Public policy pages for the Autopost app (privacy policy and terms of service), served via GitHub Pages.

`oauth.html` — OAuth return page for platforms that require an https redirect URI: it forwards only `code`, `state` and `error` to the Autopost app running on the owner's computer (`http://127.0.0.1:3000/oauth/<platform>/callback`). No third-party scripts, no storage, no tracking.
