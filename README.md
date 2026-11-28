# drift

Encrypted copies of a private daily briefing. Each page is a self-contained AES-256-GCM ciphertext; the key travels only in the link's `#fragment`, which browsers never send to the server. Without the full link, the pages are unreadable.

The `pages` branch is force-pushed as a single commit on each publish (only recent editions are kept).
