# Timberline Arena

A first-person movement shooter with pixel-art characters in a 3D world: slides, wall kicks and climbs, team fights
in a walled forest village, a battle royale in the valley, and nights of the undead on Graymoor.

## Get the game

1. Download the **Timberline Launcher**:
   - **Windows:** [`Timberline-Launcher-Windows.zip`](https://github.com/LanaCodes-Boop/timberline-arena-releases/releases/download/launcher-v1.1.2/Timberline-Launcher-Windows.zip)
   - **macOS:** [`Timberline-Launcher-macOS.zip`](https://github.com/LanaCodes-Boop/timberline-arena-releases/releases/download/launcher-v1.1.2/Timberline-Launcher-macOS.zip)
2. Unzip it and start Timberline Launcher.
3. Press **Install**, then **Play**. Every time it starts, the launcher looks for a new version and offers to update.
   Your settings and key bindings are kept.

The builds are not code-signed yet:

- Windows shows "Windows protected your PC". Choose *More info*, then *Run anyway*.
- On macOS, right-click Timberline Launcher and choose *Open* the first time.

## Play with friends

One of you hosts, the others join. Everything happens in the launcher.

**To host** (friends anywhere, not only on your own network):

1. Press **Host a match on this computer**. The first time, the launcher fetches Cloudflare's tunnel program (about
   40 MB); Windows may ask whether the launcher may use the network: allow it.
2. After a few seconds **Your invite link** appears. Press **Copy** and send it to your friends.
3. Press **Play**, choose **Create Room**, and wait for them in the lobby.

No account and no router setup are needed. The link is new every time you start hosting, and it stops working when you
stop hosting or close the launcher. Untick *Friends on other networks can join* to host for your own network only.

**To join:** paste the link your friend sent under **Server** and press **Play**. Rooms that are open on that server
are listed at the top of the main menu: click **Join …**. (A room code or an invite link from the lobby works too.) A link that is on your
clipboard when you open the launcher is offered with one click.

The tunnel only carries the first contact. After that the game talks to each player directly where their networks
allow it (the corner of the screen shows DIRECT); otherwise it stays on the relay (RELAY), which costs some ping.

If your connection drops your place is held for 25 seconds, and the game picks it up again by itself.

**F11** (or Alt+Enter) switches full screen. Everything else on the keyboard belongs to the game: there is no browser
around it, so Ctrl+W crouch-walks instead of closing a tab.

Something not working? **Logs** at the bottom of the launcher opens the folder with `launcher.log` and `host.log`.

## What the launcher does

It reads a signed list of the game's files from this repository's latest release, downloads the package, checks every
file against that list, and only then installs. **Repair** checks the installed files again; **Back to …** returns to
the version you had before an update. Without a connection the installed version still starts.

## Credits

Sounds and 3D props by Kenney (CC0), further sounds and music from OpenGameArt (CC0); the full list ships with the
game. Built with three.js and Electron.
