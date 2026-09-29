# Claude Profiles

Run several Claude accounts at once on your Mac, each in its own window, with each account's 5-hour and weekly usage in the menu bar.

## Install

Paste these 2 lines into Terminal:

```
curl -fsSL -o /tmp/cp.zip https://github.com/akaCT/claude-profiles-releases/releases/latest/download/Claude-Profiles.zip
ditto -xk /tmp/cp.zip ~/Applications && open ~/Applications/"Claude Profiles.app"
```

## Requirements

- macOS 14 or later
- The Claude desktop app
- Apple Silicon or Intel (both are supported in 1 download)

## A note on the browser download

Downloading the zip in a browser works too, but macOS will ask you to approve the app in System Settings first (this app is not signed with an Apple Developer ID, so Gatekeeper asks once). The Terminal install above skips that extra step.

## Updates

Updates install themselves. Claude Profiles checks for a new version when it starts and every 6 hours, and every update is verified against a signature before it installs. Your Claude windows stay open and signed in through an update.
