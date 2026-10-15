# SupaConductor

Run several Claude accounts at once on your Mac, each in its own window, with each account's 5-hour and weekly usage in the menu bar.

SupaConductor was called Claude Profiles before version 0.4.0. If you already have Claude Profiles, it updates itself: do not install it again.

## Requirements

- macOS 14 or later
- The Claude desktop app
- Apple Silicon or Intel (both are supported in 1 download)

## Install

Paste these 2 lines into Terminal:

```
curl -fsSL -o /tmp/cp.zip https://github.com/akaCT/claude-profiles-releases/releases/latest/download/SupaConductor.zip
ditto -xk /tmp/cp.zip ~/Applications && open ~/Applications/"SupaConductor.app"
```

SupaConductor lives in the menu bar, as a small "SC" at the top right of the screen. It has no Dock icon. Click SC and choose "Add Profile..." to add your first account.

## Installing from a browser instead

Downloading the zip in a browser works too, with 2 extra steps:

1. Drag SupaConductor.app into your Applications folder before you open it.
2. macOS will refuse to open it the first time, because the app is not signed with an Apple Developer ID. Open System Settings, go to Privacy & Security, scroll down to the message about SupaConductor, and click "Open Anyway". You only do this once.

The Terminal install above skips both.

## Updates

Updates install themselves. SupaConductor checks for a new version when it starts and every 6 hours, and every update is verified against a signature before it installs. Your Claude windows stay open and signed in through an update.

## Older links

SupaConductor.zip and Claude-Profiles.zip are the same app. Claude-Profiles.zip is still here so install links sent earlier keep working.
