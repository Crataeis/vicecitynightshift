# Privacy Policy

**Effective date:** 13 November 2026

Vice City Night Shift ("the app") is a personal, single-user tool that uploads short gameplay clips to
its own YouTube channel through the YouTube Data API.

## What the app accesses

- Through Google OAuth, the app requests permission to **upload videos** and **read video status** on
  the operator's own YouTube channel. No other Google account data is accessed.
- The app reads **public** Twitch clip metadata (title, streamer name, view count) through the Twitch API.

## What the app stores

- The operator's own Google OAuth token, stored on the operator's private server.
- A local list of clips that were processed, with their public titles and streamer names.

The app has no users other than its operator. It does not collect, store, sell or share any personal
data from viewers, streamers or anyone else. It does not use cookies or analytics.

## Google API Services

The app's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Removal requests

Streamers who want their clips removed from the channel can open an issue in this repository. Clips are
taken down and the channel is added to a permanent blocklist.

## Contact

Open an issue at https://github.com/Crataeis/vicecitynightshift/issues
