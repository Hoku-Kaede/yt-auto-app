# Privacy Policy — yt-auto

Last updated: 22 October 2026

`yt-auto` is a personal, single-user command-line tool that runs on the operator's own computer. It
is not a hosted service, it has no users other than its operator, and it does not collect data about
anyone.

## What the tool accesses

When the operator authorizes it, Google grants access to the operator's own YouTube channel through
these OAuth scopes:

- `https://www.googleapis.com/auth/youtube.upload` — to upload the operator's videos
- `https://www.googleapis.com/auth/youtube.force-ssl` — to manage the operator's own comments
- `https://www.googleapis.com/auth/youtube.readonly` — to read the operator's own channel data
- `https://www.googleapis.com/auth/yt-analytics.readonly` — to read the operator's own analytics

This covers the operator's own channel metadata, video statistics, analytics reports and public
comments on their videos. No other Google account or service is touched.

## How data is stored

All data stays on the operator's local machine:

- OAuth refresh and access tokens: `%USERPROFILE%\.yt-auto\tokens\`
- Configuration and cached API responses: `%USERPROFILE%\.yt-auto\`

API responses are cached locally so the tool does not repeatedly spend the daily YouTube API quota.

## Sharing and retention

- Nothing is transmitted to any third party.
- Nothing is sold, rented or shared.
- There is no analytics, telemetry, tracking or advertising of any kind.
- There is no server or database; no data is stored off the operator's machine.

Local files are kept until the operator deletes them.

## Revoking access

Access can be revoked at any time at
[myaccount.google.com/permissions](https://myaccount.google.com/permissions). Deleting
`%USERPROFILE%\.yt-auto\tokens\` removes the stored credentials from the machine.

## YouTube Terms of Service

Use of this tool is also subject to the
[YouTube Terms of Service](https://www.youtube.com/t/terms) and the
[Google Privacy Policy](https://policies.google.com/privacy).

## Contact

Questions about this policy: mewttukuttu@gmail.com
