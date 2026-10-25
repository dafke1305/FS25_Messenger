# Messenger — User guide

[Nederlands](HANDLEIDING.md) · [English](USER_GUIDE.md) · [Download / README](README.md)

For the **1.0.2.3** package linked in [this release](https://github.com/dafke1305/FS25_Messenger/releases/tag/v1.0.2.3). These instructions describe that ZIP, not another build sharing its version number.

## Installation

1. Download **FS25_Messenger.zip** from the release Assets. Keep that filename and do not extract it; the automatic GitHub Source code archives are not the mod.
2. Put the ZIP in FS25's configured mods folder (normally `Documents\My Games\FarmingSimulator2025\mods` on Windows) and enable it before loading the savegame. These script mods require PC/Mac.
3. On multiplayer/dedicated servers, the server and every client need the **identical ZIP**, not just the same version label. Close the game/stop the server and back up the save before updating.

## Open and send

1. Join a player farm. Messenger is a **farm-to-farm mailbox**, not a private mailbox for one individual farm member.
2. Open the Messenger page in the in-game menu or press **Alt+M**. Select another farm/conversation.
3. Enter a subject and message, then choose **Send**. Maximum subject: **80 characters**; message: **600 characters**. The displayed counters help you stay within those limits.
4. Use **Reply** or a quick reply to continue a conversation. **Enter sends directly** in the compose input, so use the Send button if you want to control exactly when it is submitted.
5. Check **Sent/Read** status and use **Newest unread** to jump to the latest unread conversation.

Offline recipient farms can receive stored messages when their members reconnect. The mailbox is stored in the server savegame and survives ordinary save/restart. Members of the same farm share that farm's correspondence; do not treat it as a confidential player-to-player DM service.

## Organize messages and alerts

Search conversations or filter by unread/pinned status. **Pin**, **Mute**, **Archive** and **Restore** manage the selected farm conversation. Archive hides it from the active list without being the same as deleting it. **Delete conversation** removes the conversation from your farm mailbox; it does not mean every other farm's copy is removed.

The alert button cycles through **all**, **quiet**, **pinned** and **off**. Quiet suppresses the notification sound; pinned restricts notifications to pinned conversations. These preferences are client-local. A muted thread can also suppress its alerts, so check both the global mode and thread state when notifications seem absent.

## Administrator actions

An in-game logged-in server administrator can send an announcement to **all eligible other player farms**. Read the recipient confirmation before sending. A normal player cannot use this broadcast action.

**Admin: clear old messages** deletes qualifying server messages at least one full **in-game month** old, keeping recent messages. It is a server-wide cleanup, not the same as archiving your own thread; read its confirmation and keep a save backup before cleanup.

## Troubleshooting

| Problem | Check |
| --- | --- |
| No recipients | Join a farm and check that another eligible player farm exists. |
| Cannot send | Fill subject/body, respect 80/600 characters and wait if rate-limited. Do not rapidly retry a message reported as stored. |
| No alert | Check alert mode, mute status and unread state. |
| Missing after reconnect | Verify the farm/savegame and identical server/client ZIP. Provide logs instead of editing mailbox save data. |

## Get help

Use [this mod's bug/support form](https://github.com/dafke1305/FS25_Messenger/issues/new/choose). Include the release/ZIP, FS25 and map versions, singleplayer/host/client/dedicated role, steps, incident time, full client `log.txt` and matching `server.log` for a dedicated-server incident. Add relevant screenshots/video. The package checksum is in [PUBLICATION.json](PUBLICATION.json). Remove passwords/tokens/private connection details before posting; send private evidence only through an approved private channel.

Keyboard defaults can be rebound. Current F1 prompts and your Controls settings take precedence.
