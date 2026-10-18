# Privacy Policy for Grandma's Lambda

Effective date: October 17, 2026

## Overview

Grandma's Lambda is a private, family-run tool that maintains a YouTube
playlist for one authorized user. It is not a public service.

## Data the app accesses

The app accesses the connected YouTube account only as needed to:

- Find or create the dedicated playlist.
- Read the playlist's video IDs and publication details.
- Add suitable videos to the playlist.
- Remove old, unavailable, or unsuitable playlist entries.

The app also stores the Google OAuth credentials needed to keep this access
working without asking the user to sign in every time.

## How data is used and stored

Google OAuth credentials are stored in AWS Secrets Manager. The app runs in AWS
Lambda and does not use a separate database. Playlist information remains in
the connected YouTube account.

The app does not sell personal data, use it for advertising, or share it for
marketing. Data is shared only with Google and AWS when required to provide the
playlist automation.

Use of information received from Google APIs follows the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including its Limited Use requirements.

## Retention and deletion

OAuth credentials are kept until the app owner deletes them or the connected
user revokes access. The connected user can revoke access at any time from the
Google Account security settings. YouTube playlists and videos can also be
removed through YouTube.

## Contact

Questions can be submitted through the
[GitHub Issues page](https://github.com/danielrazavi/grandmas-lambda-info/issues).

