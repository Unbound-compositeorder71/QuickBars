# ⚙️ QuickBars — Home Assistant on your TV

If you've ever tried to turn off the lights while watching a movie and had to fumble for your phone, unlock it, open Home Assistant, find the right dashboard… QuickBars fixes that. It puts your most-used HA controls directly on your Android TV screen.

---

## What it does

QuickBars is an Android / Android TV app that connects to your Home Assistant server and gives you a fast, clutter-free interface for controlling smart home devices.

- Flip lights on and off without leaving your couch
- Run scenes with one remote click
- Check sensor readings at a glance
- Fully configurable — you pick what shows up and in what order

No account creation. No cloud middleman. Just your HA server, your devices, your rules.

---

## Screenshots

*(Coming soon — PRs welcome!)*

---

## Installation

### On an Android TV or phone

1. Go to the [Releases page](../../releases) and download the latest APK
2. Transfer the APK to your device (USB, email, or `adb install`)
3. Open the file and approve installation from unknown sources if prompted
4. Launch QuickBars

### On a PC (via Android emulator)

If you want to try QuickBars without an Android device, use [Bluestacks](https://www.bluestacks.com) or any Android emulator:

1. Install the emulator
2. Drag the QuickBars APK into the emulator window
3. Launch QuickBars inside the emulator

---

## Connecting to Home Assistant

1. Open QuickBars
2. Enter your Home Assistant server's IP or URL (example: `http://192.168.1.100:8123`)
3. Enter your HA username and password (or a long-lived access token)
4. Allow network access when prompted

---

## Customizing your QuickBars

1. Tap **Add New Bar**
2. Pick the devices, scenes, or entities you want quick access to
3. Arrange them however you like
4. Save

You can add bars for different rooms, different times of day, or different family members.

---

## Requirements

- Home Assistant instance running and reachable on your network
- An Android device (phone, tablet, or TV) running Android 7.0 or newer
- Or a PC with an Android emulator

---

## Troubleshooting

- **Won't connect?** Double-check your HA server IP and that your device is on the same network.
- **Firewall blocking?** Make sure port 8123 is open on your HA machine for local traffic.
- **App crashing?** Try clearing the app data and re-entering your HA credentials.
- **Emulator can't reach HA?** Check the emulator's network bridge settings — some default to NAT and need switching to bridged mode.

If you're stuck, check the [GitHub Issues](../../issues) tab. If there's nothing matching your problem, open a new one.

---

## Contributing

Found a bug? Have an idea? Pull requests are welcome.

1. Fork this repo
2. Create a branch: `git checkout -b my-fix`
3. Make your changes
4. Push and open a PR

---

## License

GPL v3. See [LICENSE](LICENSE).
