# yt-auto

A personal command-line toolkit that helps a single YouTube creator manage their own channel:
metadata drafting, thumbnail generation, Shorts clipping, uploads, analytics reports and comment
triage.

It is not a service and is not offered to the public. It runs locally on the author's own machine,
authorizes through Google OAuth with the author's own Google account, and talks only to the YouTube
Data API and YouTube Analytics API.

## What it does

- Drafts titles, descriptions and tags from existing channel keywords
- Renders branded thumbnails to YouTube's 1280x720 guidance
- Cuts vertical Shorts from long recordings using speech-activity detection
- Uploads videos with resumable transfer, thumbnails and captions
- Pulls channel and per-video analytics, and mines keyword performance
- Groups comments and drafts replies

## Data handling

No data leaves the machine. Tokens and cached responses are stored locally under the user's home
directory. See [PRIVACY.md](PRIVACY.md).

## Contact

mewttukuttu@gmail.com
