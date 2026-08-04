# paptrack-support

Privacy policy + support page for the [PAPTrack](https://github.com/eagleadams86/paptrack-ios) iOS app, published via GitHub Pages: https://eagleadams86.github.io/paptrack-support/

Static HTML, no build step — same pattern as the other `eagleadams86` sites (`lottery`, `artifacts`). `style.css` is the shared Midnight-theme stylesheet.

`privacy.html` promises that emailing the contact address gets a user's synced data deleted. The runbook for actually doing that — mapping the email address to the right Firestore document, and what to tell them about the copies that can't be reached — lives in the iOS repo at [`DATA_DELETION.md`](https://github.com/eagleadams86/paptrack-ios/blob/main/DATA_DELETION.md). If the wording of the promise in `privacy.html` changes, check that runbook still matches it.
