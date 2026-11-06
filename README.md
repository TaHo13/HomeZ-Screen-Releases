# HomeZ Screen releases

The newest build of [HomeZ Screen](https://github.com/TaHo13), a custom home screen for Google TV / Android TV, for its built-in **Check for updates** (Customize → About HomeZ).

- `homez-screen-<version>.apk`: the app
- `latest.json`: its version, checksum and what changed
- `screensaver/`: HomeZ's own screen saver photos, shown until a TV has an album of its own (`list.json` names them). Photos from [Unsplash](https://unsplash.com), credited below.

## Install HomeZ on a TV (no computer needed)

1. On the TV, open the **Play Store** and install **Downloader** (free, by AFTVnews).
2. Open Downloader and type this link into its address box, then choose **Go**:
   `https://raw.githubusercontent.com/TaHo13/HomeZ-Screen-Releases/main/homez-screen.apk`
3. When the TV says it can't install apps from Downloader, choose **Settings**, turn Downloader **on**, press Back, then choose **Install**. If Google Play Protect asks about HomeZ (it isn't from the Play Store), choose **Install anyway**.
4. Choose **Open**. HomeZ walks you through the rest, about five minutes:
   - turning on **USB debugging** (Settings → System → About → press OK on *Android TV OS build* 7 times, then System → Developer options → USB debugging; HomeZ's **Open About** and **Open Developer options** buttons take you straight there), and choosing **Always allow** when the TV asks;
   - making HomeZ the **home screen** (Google's home screen is switched off, not removed);
   - an optional **tidy-up** of the TV maker's ad and tracking apps (onn., Hisense and TCL) and faster animations;
   - **ad blocking** for the whole TV with AdGuard DNS (Private DNS), which you can turn off in Customize → About HomeZ.

Everything can be undone from the TV: Customize → About HomeZ → **Remove HomeZ…** switches Google's home screen back on, can undo the tidy-up and ad blocking, and uninstalls HomeZ. You can delete Downloader afterwards.

TVs that only offer **Wireless debugging** with a pairing code (some newer Google TV models) can't be set up this way yet.

## Updates

A TV only installs an update that is newer and signed with the same key as the copy it already has. The app files are written by `app/release.sh`, the photos by `app/publish-saver.sh`.

## Screen saver photo credits

All from [Unsplash](https://unsplash.com), used under the [Unsplash License](https://unsplash.com/license). Thank you to the photographers:

- Aperture Vintage: [photo](https://unsplash.com/photos/Z6EpCdMcoUU)
- Guillermo Ferla: [photo](https://unsplash.com/photos/Oze6U2m1oYU)
- Jeremy Thomas: [photo](https://unsplash.com/photos/E0AHdsENmDg)
- Jongsun Lee: [photo](https://unsplash.com/photos/F-pSZO_jeE8)
- Luis Osa Garcia: [photo](https://unsplash.com/photos/QWRbiaYVcYE)
- Mike Petrucci: [photo](https://unsplash.com/photos/uIf6H1or1nE)
- NASA: [1](https://unsplash.com/photos/2W-QWAC0mzI), [2](https://unsplash.com/photos/ErjNGXc9mqA), [3](https://unsplash.com/photos/Q1p7bh3SHj8), [4](https://unsplash.com/photos/jlV2k_Fx0fc), [5](https://unsplash.com/photos/w9sZL_hvNug), [6](https://unsplash.com/photos/yZygONrUBe8)
- ostudio: [photo](https://unsplash.com/photos/ntaDx8ktBCw)
- Steve Busch: [photo](https://unsplash.com/photos/npMGtVIQNdc)
- Viktor Forgacs: [photo](https://unsplash.com/photos/QDMEADvb4PE)
- Vivek Doshi: [photo](https://unsplash.com/photos/obsBswnv7FI)
