# CK Track Ring

A small **WoW Forever** addon: a movable icon showing what you're tracking. Click it, and every tracking type you have opens in a ring around it; click one to switch.

**Status: an early test version.** Please report problems; a BugSack error text helps most.

## Install

**With WowUp:** Get Addons → *Install from URL* → paste `https://github.com/Nuclearjke/CKTrackRing-releases`. WowUp will then keep it up to date from this page's releases.

**By hand:** download `CKTrackRing-<version>-forever.zip` from [Releases](../../releases) and extract it into
`World of Warcraft\_forever_\Interface\AddOns\`, so that you get `AddOns\CKTrackRing\CKTrackRing.toc`. Then restart the game.

## What it does
- **The icon:** a round icon with your current track. It shows on any character with two or more tracking types (hunters, gatherers).
- **The ring:** left-click the icon and your tracks spring out around it, hunter tracks first, then Find Herbs / Minerals / Fish. The active one glows green; hovering one shows its name under the icon.
- **Switching:** click a track to cast it, just like from an action bar. The ring folds back in.
- **Closing:** Esc, a click anywhere else, or the icon again.
- **Movable:** drag the icon anywhere; right-click locks it.

## Limits
- WoW doesn't let addons show their spell buttons in combat, so the ring opens out of combat only.

## Commands
`/trackring lock` · `/trackring unlock` · `/trackring reset`

Licensed under MIT (see LICENSE). World of Warcraft is a trademark of Blizzard Entertainment.
