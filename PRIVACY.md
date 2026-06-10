# Privacy Policy — ecoverse-scribe

_Last updated: 2026-06-10_

This policy explains what data the ecoverse-scribe app ("the app") does and does not
handle.

## Summary

The app collects **no personal data**. It does not read, store, or transmit any user
posts, comments, messages, profiles, or identifiers.

## What the app accesses

- **Outbound fetch (read-only):** the app makes unauthenticated HTTP `GET` requests
  to `raw.githubusercontent.com` to read one public, static JSON file describing the
  next chronicle entry to post (title, body, and ready/kill flags). No data is sent
  in these requests.
- **Reddit API (write-only, posting):** the app submits text posts authored by the
  Knights of the Ecoverse project to the subreddit where it is installed. It does
  not read user-generated content.

## What the app stores

- **Redis:** the app stores only the set of entry ids it has already posted, to
  avoid duplicate posts. These ids are project content identifiers, not user data.

## What the app does NOT do

- It does not collect, profile, or track users.
- It does not read posts, comments, votes, or private messages.
- It does not use analytics or advertising.
- It does not share data with third parties (it sends no data to anyone).

## Data retention

The only stored data is the list of already-posted content ids, retained to prevent
duplicates. No user data is retained because none is collected.

## Contact

Questions or requests: lovanroyen@gmail.com
