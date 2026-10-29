---
layout: default
title: B2 Business privacy policy
---

# B2 Business: Privacy Policy

**Effective date:** 30 October 2026

B2 Business ("the game", "we") is a trading card game for players aged **13 and over**. You can play it on one device, with friends on the same Wi-Fi network, or with friends online. This policy explains what information the game uses and where it goes.

## The short version
- We **don't collect personal data**, and there are **no accounts of our own and no ads**. The Android app does send us a **record of every game as it's played, crash reports and app-usage statistics**, with **no names in them** (each player is named by their seat) and **no advertising identifier**, to fix bugs and improve the game (see "Game logs and analytics"). This version has **no in-app purchases**: you earn B2 Gems by playing. If a later version sells Gems through Google Play, this policy will say what that involves before it's released.
- Everything the game stores stays **on your device**, apart from your Play Games save if you sign in to Play Games (see "Saves in Google Play Games").
- **Google Play Games (optional):** if you sign in to Play Games, your B2 Gems' history and the game records made under the same sign-in are kept with your Play Games account, and the app keeps **one save of your progress in your Google account**, so they stay yours on a new phone. We never receive your Play Games name, picture or email.
- **Notifications** ("News from B2"): only if you allow them, news, new versions and an occasional nudge if you haven't played for a while, sent by the developer, never daily. Turn them off any time in Settings (see "Notifications").
- Multiplayer games run **directly between devices on your own Wi-Fi network**, or, at an **online table**, through B2's relay on Cloudflare, which passes the game's messages between the players' phones and **keeps none of them**. Neither way stores your games' messages; the game records we keep are the ones "Game logs and analytics" describes.
- **Game logs and analytics:** game records, crashes, app usage and the history of your B2 Gems go to our **Google Firebase** project (Firestore, Crashlytics, Google Analytics), with nicknames replaced by seat numbers and no account, email or advertising identifier (see "Game logs and analytics").
- **Reporting a problem (optional):** if you report a problem or an idea from the app, the words you write go to us with the app's version, your phone's model and Android version and, if you leave it on, the game's ID; nothing goes until you press Send (see "Reporting a problem").

## What the game stores on your device
| Data | Why | How to delete it |
|---|---|---|
| Your nickname (up to 12 characters) and avatar choice | To show you at the table | Change it in the app, or clear the app's data |
| Settings (sound, music, vibration, reduced motion and which onboarding boxes you dismissed) | To remember your preferences | Change them in the app, clear the app's data or uninstall |
| Saved games (on the device that hosts a game) | To resume a game after an interruption | Delete the saved game in the app, clear the app's data, or uninstall |
| Your trophies, achievement progress and B2 Gems | To keep what you've earned across games | Clear the app's data or uninstall |
| History: the results of your last 20 finished games (the final standings, awards and everyone's holdings), with the nicknames and avatars of the players at those tables | So you can look back at how your games went | Clear the app's data or uninstall; the oldest game goes as each new one is kept |
| The kits you own and your three kit loadouts, kept in your wallet beside your B2 Gems | To keep what you've bought with Gems and set up for your next games | Clear the app's data or uninstall |
| A report of the last crash: the game as it stood, the error, and the app's recent technical log | So you can send it to us if you choose; Home offers it once | Dismiss it when offered (it's deleted then), clear the app's data, or uninstall |

This information isn't sent to us or to any third party, except the game logs and analytics described below, which carry no nickname, and your Play Games save, which goes to your own Google account if you sign in to Play Games.

**Backups.** In Settings → Your data you can make a backup: your nickname, avatar, trophies, your wallet (B2 Gems, the kits you own and your loadouts), your History and settings, as text you copy or share, to restore on a new install. It never holds the join codes or keys of games you joined, your hosts' addresses, or other players' names: History goes into it with other people's names left out. Anyone who has your backup can restore it, so keep it somewhere private. Restoring replaces what's on that device.

**Game reports.** You can copy a game report, or share it as a text file through your phone's share sheet (a download in a browser), to send to whoever looks into a problem. It holds that game's moves and settings, the app's recent technical log and how smoothly the game drew. If you joined someone else's table, it holds only what your own seat saw. It never holds your network address, the join code or your seat's private key. The game never sends a report by itself: it goes only where you send it.

## Saves in Google Play Games
If you sign in to Google Play Games in the Android app, the app keeps **one save** of your progress in your Google account, through Play Games' saved games. Google stores it for you; it isn't in our Firebase project, and we don't receive a copy.

- **What's in it:** what a backup holds (your nickname, avatar, trophies, the kits you own and your loadouts, your History with other people's names left out, and your settings), with a random ID for the phone that saved it and the time. **Your B2 Gems aren't in it:** your Gems' history keeps your balance, and a restore takes your Gems from there.
- **When it's saved:** after each finished game and when you leave the app, if something changed. A phone saves only once it made the save or restored it. If your account holds a save another phone made, the app asks first: **Restore** or **Not now** on a new phone, or which of the two to keep on a phone with its own progress. Nothing is replaced without your choice.
- **Deleting it:** in Google Play Games' settings, which can delete a game's data (B2 Business). Uninstalling the game doesn't delete it.

## Playing with friends on your Wi-Fi
- When you **host** a game, your phone runs a small game server on your local network. Other players join from the app or by scanning a QR code in their web browser.
- The devices exchange only what the game needs:
  - nicknames and avatar choices, and the frame and podium celebration you equipped in the Store;
  - your Business Card's game highlights, such as games played, wins and trophies, which the others at your table can see, with your best net worth, the highest you have finished a game with. Other players' phones show these during the game and don't keep them;
  - the moves you make;
  - the information the game rules make public, such as stakes and Boosters.
- Private game details, such as another player's cash and net worth, are not shown to others unless that player chooses to reveal them.
- **On a Wi-Fi table, everything stays on your local network.** Nothing goes over the internet to us.
- The 4-digit join code and QR code only let people on the same network join your table.
- Local network play uses an unencrypted connection on your own network. **Play on networks you trust**, such as your home Wi-Fi or your phone's hotspot, not open public Wi-Fi.
- If a friend joins with a web browser, the page is served by the host phone itself. It doesn't load anything from the internet.

## Playing with friends online
- When you **invite friends online**, your phone still runs the game. It connects to **B2's relay**, a small service on Cloudflare's network, which passes messages between your phone and each friend's phone over an **encrypted connection**.
- The relay passes the same game information as a Wi-Fi table: nicknames and avatars, Business Card highlights, the moves you make, and what the rules make public. Private details, such as another player's cash and net worth, are never sent to anyone else.
- **The relay keeps no messages.** While a table exists it keeps only the table's code and a key that lets the host's phone back in, and it forgets a table 24 hours after its host leaves.
- Like any internet service, Cloudflare handles your device's network address to deliver the messages. The relay doesn't record it, and **players never see each other's addresses**. Cloudflare's own privacy policy covers its network.
- Anyone with your table's **invite link** joins at once, and anyone who types its **6-character code** waits for you to let them in. Share them only with friends.
- Online tables are played in the app only, and are optional: Wi-Fi play works without the internet.

## Permissions the Android app uses
| Permission | Why |
|---|---|
| Network access (Internet) | Needed to host or join games on your local Wi-Fi, for online tables through B2's relay, and to send the game logs and analytics (see "Game logs and analytics"). Not used for anything else. |
| Wi-Fi multicast | To find games hosted on your network |
| Network state | To notice when your Wi-Fi drops or changes, so the game can reconnect |
| Keep the device awake | To keep a hosted game running while you play, also with the screen off |
| Run in the foreground (connected device) and show notifications | While you host a game, a notification ("Hosting your B2 table") keeps the game going for your friends with your screen off. If you allow them, the same permission shows **News from B2** (see "Notifications"). You're asked once for notifications, and hosting works without them. |

The game doesn't use your camera, microphone, location, contacts, photos or phone identifiers.

## Notifications
The Android app can show notifications called **News from B2**: news about the game, a new version to update to, and now and then a nudge if you haven't played for a while. The developer writes and sends each one from Google Firebase's console, at most about once a week; the app never sends daily reminders or counts days in a row.

- **Off until you allow them.** The first time you open the app it asks once; Android then asks too. Settings → Sound → **News from B2** turns them on or off at any time; off, your phone is removed from the list they're sent to.
- **What is used:** to deliver them, Google's **Firebase Cloud Messaging** gives your phone a registration (tied to Firebase's installation ID) while News from B2 is on. Google keeps it; we don't store it, and it isn't tied to your name or account.
- **While you're playing,** a notification that arrives waits until you're back on the home screen, and one that's too long or uses words the game doesn't allow is not shown.

## Reporting a problem
In the Android app you can tell us about a problem or an idea: **Report a problem** is on the home screen, in Settings → About, in a game's menu, on the podium at a game's end and beside each game on History, and after a crash.

- **What's sent, only when you press Send:** what kind it is (something broken, a rule that looks wrong, or an idea), the words you write (up to 500 characters), where in the app you wrote it, and, if you leave its switch on, the ID of the game it's about. With them go the app's version and the game rules' and network protocol's versions, your phone's maker and model and its Android version, the random installation ID and the anonymous sign-in ID (the same ones the game logs use), and the time it arrived.
- **Please don't write your name, phone number, email or anything else about yourself.** We don't ask for a way to reply. After you send a report, the app shows you its short code, which you can quote if you write to us.
- **Why:** to find and fix what went wrong, and to hear your ideas. The installation ID lets us read that phone's crash reports, and the game's ID that game's record (see "Game logs and analytics").
- **Where it goes:** our Cloud Firestore project in Google Firebase, like the game logs. With no internet, it waits on your phone and goes once you're online. A phone sends at most five a day.
- **How long:** up to 24 months, then deleted. To have a report deleted sooner, write to us with its code.
- A browser that joins a Wi-Fi table has no Report a problem and sends nothing.

## Children
The game is intended for players aged 13 and over. We don't knowingly collect personal information from anyone, including children: the game logs and analytics carry no nickname, account, contact detail or advertising identifier, only random identifiers. A problem report holds only the words its player writes, and the app asks them to leave out anything about themselves.

## Game logs and analytics
The Android app sends us information about how the game is played, so we can fix bugs and improve the game. It uses Google Firebase: **Cloud Firestore** for game records, **Crashlytics** for crash reports, **Google Analytics for Firebase** for app usage, **Remote Config** for the update check, and **Firebase Authentication**'s anonymous sign-in. There is no switch to turn this off: it's part of how the game is tested and improved. The web page a host's phone serves to friends on Wi-Fi sends nothing.

- **Game records, while you play:** each game you play (alone, hosted or joined) is recorded as it goes: its settings and every move, after each trade and when the app goes to the background, then the whole game when it ends or you leave it. **Every player's nickname is replaced by their seat number** ("Seat 1"). The record includes the app's technical log of your taps: what you tapped, whether it counted, and the seconds left on the timer.
- **Crash reports:** when the app crashes, Crashlytics receives the error, where in the app it happened, your phone's model and operating-system version, the app version, and the ID of the game you were playing.
- **App usage (Google Analytics):** when the app is opened, how long it's used, which screens are shown, when a game starts and ends (alone, hosted or joined, how many seats), your phone's model, operating system and app version, and your approximate country or region, which Google works out from your network address. **No advertising identifier is collected, and ad personalisation is off.** We don't use this for advertising.
- **Identifiers:** a random installation ID the app makes on first use, an anonymous Firebase sign-in ID, and Firebase's app-instance ID. They let one phone's games and sessions be read together, so we can see how often the game is played, where players stop, and which features are used (Analytics' user ID is the installation ID). None is tied to your name, email, account or phone number. If you sign in to Google Play Games, Firebase links its sign-in ID to your Play Games account (by an ID Google gives B2 for you): the Gems history and game records under it are then kept with that account, still with no name, picture or email.
- **Your B2 Gems' history:** your Gems stay on your device, and the app also records your balance and each change to it in Firestore, so a question about your Gems can be looked up: the Gems a game earned (naming the game by its number), a How to play lesson's Gem (naming the lesson), a kit or a cosmetic you bought (naming it), the balance after each, a backup you restored, the Gems you held when the history began, the app's version, the random installation ID and the time, under your Firebase sign-in ID (linked to your Play Games account if you sign in to it). The record never changes the Gems on your device.
- **Update check:** the app asks Firebase Remote Config which version of the game is the oldest that may still be played, and where to get the new one. If yours is older, the app asks you to update it before you play again (a game you're playing finishes first). This request carries Firebase's installation ID and the app's version, and nothing about your games.
- **A game's ID:** the app can copy a game's ID for you (its random installation ID and the game's number), from a problem report, so you can tell us which game to look at; a problem report also sends it for you. It shows only once you copy it.
- **What's never sent:** your nickname or other players' nicknames, avatars, email, contacts, precise location, advertising identifiers, join codes or other players' private details.
- **Where it goes and who processes it:** Google, as the Firebase service provider, in the developer's Firebase project. Google's privacy policy covers its services. Data is encrypted in transit.
- **How long:** game records for up to 24 months, crash reports for 90 days (Crashlytics' own limit), and Analytics' detailed data for 14 months, then deleted; your Gems' history for as long as the game is offered, so a later question can still be checked.
- **Not for sale:** never sold, never shared with anyone else, never used for advertising.
- If a game can't be sent (no internet), the phone keeps it and sends it later. Because none of this carries a name or account, we can't tell which records are yours; ask us at the address below if you have questions.

## Sharing and selling
We don't sell or share personal information. The game logs and analytics stay in the developer's Firebase project and are used only as "Game logs and analytics" says.

## Changes to this policy
If we change this policy, we'll update the effective date above. Significant changes, such as adding analytics, will also be noted in the app's release notes.

## Contact
Questions about privacy: RishabhBuilds@gmail.com (Rishabh Agrawal, the developer of B2 Business).

© 2010–2026 Rishabh Agrawal. B2 Business is an original card game by Rishabh Agrawal, played as physical cards since 2010, with its first manual in 2012. This app is its digital edition.
