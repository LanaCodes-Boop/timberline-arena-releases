# Timberline Arena

A first-person movement shooter with pixel-art characters in a 3D world: slides, wall kicks and climbs, team fights
in a walled forest village, a battle royale in the valley, and nights of the undead on Graymoor.

## Get the game

1. Download the **Timberline Launcher** from the [latest release](https://github.com/LanaCodes-Boop/timberline-arena-releases/releases/latest):
   - **Windows:** [`Timberline-Launcher-Windows.zip`](https://github.com/LanaCodes-Boop/timberline-arena-releases/releases/latest/download/Timberline-Launcher-Windows.zip)
   - **macOS:** [`Timberline-Launcher-macOS.zip`](https://github.com/LanaCodes-Boop/timberline-arena-releases/releases/latest/download/Timberline-Launcher-macOS.zip)
2. Unzip it and start Timberline Launcher.
3. Press **Install**, then **Play**. Every time it starts, the launcher looks for a new version and offers to update.
   Your settings and key bindings are kept.

The builds are not code-signed yet:

- Windows shows "Windows protected your PC". Choose *More info*, then *Run anyway*.
- On macOS, right-click Timberline Launcher and choose *Open* the first time.

## Play with friends

The game needs a server to meet on. In the launcher, under **Server**:

- **Join a friend:** paste the address or the invite link they gave you, then press **Play**. An invite link takes you
  straight into their room.
- **Host on your own computer:** press **Host a match on this computer**, then **Play**. The launcher shows the address
  players on your network type in. (Playing with people outside your network needs a server they can reach; the
  person who hosts will send you its address.)

If your connection drops your place is held for 25 seconds, and the game picks it up again by itself.

**F11** (or Alt+Enter) switches full screen. Everything else on the keyboard belongs to the game: there is no browser
around it any more, so Ctrl+W crouch-walks instead of closing a tab.

## What the launcher does

It reads a signed list of the game's files from this repository's latest release, downloads the package, checks every
file against that list, and only then installs. **Repair** checks the installed files again; **Back to …** returns to
the version you had before an update. Without a connection the installed version still starts.

## Credits

Sounds and 3D props by Kenney (CC0), further sounds and music from OpenGameArt (CC0); the full list ships with the
game. Built with three.js and Electron.
