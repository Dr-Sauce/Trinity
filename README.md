# Trinity

iOS Release Notifications, Signing Status, delayed OTA. Are you getting it? These are not three separate things. We are calling it **Trinity**.

<img width="100" height="100" alt="${f}" src="https://github.com/user-attachments/assets/2df5c1fa-9114-4c16-a506-55d8368b184b" />

# Features:
- Receive Apple products software updates.
- View iOS signing status.
- View iOS delayed OTA schedule.

# Install:
1. Get [a-Shell mini](https://apps.apple.com/us/app/a-shell-mini/id1543537943).
2. Go to [**Releases**](https://github.com/Dr-Sauce/Coexist/releases/latest) and open iCloud link. Once Shortcuts app opens press **Add Shortcut**.

# Teaser:
https://github.com/Dr-Sauce/Trinity/assets/82555878/74a6958e-5b75-4ea0-88bd-c44040181ba8

**Music:** [Deus Ex Machina - Dancing About Architecture](https://soundcloud.com/dancingaboutarchitecture-music/deus-ex-machina)

# Receive software updates:

1. Open **Shortcuts** app → **Automation** tab → Press **+** on the top right corner → **Create Personal Automation**. Select a trigger(I personally recommend **Charger** or **Time of Day**) → Configure settings and press **Next**.
![Picture1](https://github.com/Dr-Sauce/ReVancedNotifier/assets/82555878/e1c95448-c144-43c4-9c07-95e4eab59223)

2. Press **+ Add Action** → Search for **Run Shortcut** and select it → Press **'Shortcut'** from **Run Shortcut** → Select **Trinity**.
![Picture2](https://github.com/Dr-Sauce/ReVancedNotifier/assets/82555878/ff279bfe-a424-4cbd-9b02-37e7a1240df3)

3. Press the blue icon **▽** and press **Input - Choose variable** → Select **Current Date** → Press **Next** → Disable **Ask Before Running** and press **Don't ask** → Press **Done**.
![Picture3](https://github.com/Dr-Sauce/ReVancedNotifier/assets/82555878/80d441e5-f9d7-4025-84a5-5b9a134b3de4)

4. Now try it out if it works well! You'll receive notifications if there's a new update. (Use [Truecuts](https://github.com/qnblackcat/rootless-tweaks/releases/download/090623/com.ethanrdoesmc.truecuts_1.2.0_iphoneos-arm64.deb) to remove **Running your automation** notification if your iPhone is jailbroken)
![Picture5](https://github.com/Dr-Sauce/ReVancedNotifier/assets/82555878/db974238-6d72-4cc7-b079-ac6b1673dcad)

# Credits:

**[AppleDB](https://appledb.dev/) Team -** Helped manage API usage.

**[u/jaycos](https://www.reddit.com/user/jaycos) -** Provided an efficient way to only push notifications for the latest version in each major OS.

**[u/mvan231](https://www.reddit.com/user/mvan231) -** Improved notification settings.

[**@PARKasd**](https://github.com/PARKasd) - Provided a way to download delayed OTA profiles.

[**u/gluebyte**](https://reddit.com/user/gluebyte) - Fixed Trinity on iOS 16+.


# Sources:

[IPSW Downloads API](https://ipswdownloads.docs.apiary.io/) ([ipsw.me](https://ipsw.me/))

[delayed OTA](https://dhinakg.github.io/delayed-otas.html) ([@dhinakg](https://github.com/dhinakg))

[MobileGestalt Device Info](https://routinehub.co/shortcut/4920) ([@atnbueno](https://github.com/atnbueno))

[Shortcut Updater](https://github.com/Dr-Sauce/ShortcutUpdater) ([Dr-Sauce](https://github.com/Dr-Sauce))

