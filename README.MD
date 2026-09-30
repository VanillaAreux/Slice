# Slice — Desktop App Releases

This repo only holds built installers for **Slice**, the desktop app for
[slicesocial.netlify.app](https://slicesocial.netlify.app).
## Download

Grab the latest installer from the [Releases](../../releases) page:
`Slice-Setup.exe` (Windows only, 64-bit).

Windows SmartScreen will likely warn that the app is from an unrecognized
publisher the first time you run it — that's expected, since it isn't
code-signed. Click **More info → Run anyway** to continue.

## What it is

Slice desktop is a lightweight wrapper around the Slice web app: its own
window, taskbar and Start Menu shortcuts, a tray icon, and real Windows
notifications for messages and calls. It always loads the live site, so
the app itself never needs updating for ordinary feature changes — only
for changes to the wrapper (icon, tray behavior, notification handling,
etc.).

##Updates

Slice Update Log - Part 1

Slice now includes a full social experience with posts, profiles, search, hashtags, follows, friends, DMs, group chats, notifications, saved posts, blocking, muting, moderation, and account controls. Posts support media, forwarding, reporting, and hashtags. Search can find users or hashtags, while feeds automatically load more content as you scroll.

Slice Update Log - Part 2

Messaging has been expanded with DMs and group chats. Messages support photos, video embeds, replies, reactions, mentions, forwarding, copying, unsending, drafts, reporting, and message search. Group chats support up to 20 members, friend-only membership, photos, replies, reactions, mentions, moderation, and customizable group settings.

Slice Update Log - Part 3

Friends are now separate from follows. Users can send, accept, decline, cancel, and remove friend requests. Friends unlock voice/video calls and group chats. Profiles show friendship status, and the Friends page includes online status, requests, search, messaging, and call shortcuts. Blocking removes friendships and prevents new requests.

Slice Update Log - Part 4

Slice now supports 1:1 voice and video calls using peer-to-peer WebRTC, plus optional TURN servers for difficult networks. Calls include camera switching, microphone/camera controls, device selection, screen sharing, speaking indicators, minimized calls, keyboard shortcuts, call history, push ringing, missed-call notes, and improved mobile reliability.

Slice Update Log - Part 5

Group calls support up to 8 participants with voice, video, screen sharing, camera switching, speaking indicators, join/leave sounds, full-screen ringing, minimized calls, tile controls, reconnect handling, bitrate scaling, and call history. Blocking and muting are respected during calls, while reliability improvements help connections recover from network changes.

Slice Update Log - Part 6

Push notifications now handle incoming calls even when Slice is closed. The service worker re-fires ringing notifications until calls are answered, declined, or ended. Notifications are tied to the currently signed-in account and can be enabled from Settings. iOS has special handling for audio interruptions, autoplay restrictions, and Home Screen requirements.

Slice Update Log - Part 7

Performance has been heavily optimized. Polling slows when the app is inactive, feed refreshes stop after extended inactivity, and push-enabled devices reduce call polling. Active tabs now use roughly 12 function calls per minute instead of about 29, while long-idle sessions use far fewer. Call check-ins remain active to preserve reliability.

Slice Update Log - Part 8

Photos are supported in DMs and group chats, with private access controls and storage cleanup. Pasting an image into a message can send it directly. Optimized mode can disable animations, photos, and video embeds for better performance. Video links from YouTube, Vimeo, and supported direct video files can play directly inside messages.

Slice Update Log - Part 9

Accounts now support temporary passwords, forced password changes, password resets, session invalidation, switching accounts, account deletion, and password changes from Settings. Admins can create accounts and manage badges. Verified, Content Creator, and Slice Staff badges can be independently assigned and are logged through moderation tools.

Slice Update Log - Part 10

Settings now includes themes, fonts, notifications, online-status controls, performance mode, call sounds, password management, account switching, blocked/muted users, Terms of Service, Community Guidelines, and help. Themes and fonts are saved per device. Users can also replay the welcome tour and access keyboard shortcut documentation.

Slice Update Log - Part 11

Moderation tools now support reports for posts, DMs, group messages, and photos. Reports preserve relevant context even if messages are later unsent. Moderators can remove content or suspend users for 7 days. Reported photos remain accessible to moderators only while the associated report is open.

Slice Update Log - Part 12

Slice includes a Windows app that uses the same web interface and receives site updates without requiring a new installer. Calls continue checking while the app is minimized or hidden, and incoming calls can bring the window back to the foreground. Downloads are available through More, with Windows supported and Mac/Linux marked as planned.

Slice Update Log - Part 13

The app now includes a welcome tour for new accounts, keyboard shortcuts, device switching, audio/video controls, call minimization, jump-to-latest controls, message drafts, unread counts, and improved navigation. The More menu provides access to Settings, Saved Posts, Moderation, Downloads, Call History, Friends, Help, Terms, Guidelines, and account switching.

Slice Update Log - Part 14

Slice's core benefit is bringing your social life into one place: users can share posts, discover people, message friends, create group chats, and jump into voice or video calls without constantly switching between separate apps. The platform combines social feeds, private conversations, communities, media sharing, and real-time communication in one PWA.
