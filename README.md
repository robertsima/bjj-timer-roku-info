# BJJ Timer for Roku

Marketing, store listing, and support information for the **BJJ Timer** Roku channel.

The app source code lives in a separate repository: [bjj-timer-roku](https://github.com/robertsima/bjj-timer-roku).

## About

BJJ Timer is a single-screen round timer built for Brazilian Jiu-Jitsu training. Configure rounds, breaks, and presets from your Roku remote — no account, backend, or internet connection required after install.

**Developer:** Robert Sima  
**Contact:** [robertsima88@gmail.com](mailto:robertsima88@gmail.com)

## Features

- Round, break, and 10-second pre-round countdown
- Presets: Competition, Drilling, Open Mat, and Custom
- Audio cues: countdown beeps plus a distinct round-start tone
- Visual warnings in the last 10 seconds of a round; flash in the last 3 seconds
- Pause, resume, skip pre-round/break, and end session
- Adjust total rounds during an active session
- Session summary with completed rounds and total mat time

## Presets

| Preset | Round length | Break | Rounds |
|--------|--------------|-------|--------|
| Custom | User-defined | User-defined | User-defined |
| Competition | 5:00 | 0:30 | 6 |
| Drilling | 3:00 | 0:30 | 5 |
| Open Mat | 6:00 | 0:20 | Infinite |

Default round increment when adjusting: 30 seconds.

## Remote controls

| Key | Setup | Active timer | Session complete |
|-----|-------|--------------|------------------|
| OK / Play | Start session | Pause / Resume | New session |
| Up / Down | Select setting | Adjust total rounds | — |
| Left / Right | Adjust setting | — | — |
| * (info) | — | Skip pre-round or break | — |
| Back | Exit app | End session (return to setup) | Return to setup |

## Repository contents

```
assets/          Channel poster and splash artwork (Roku store sizes)
screenshots/     Preview images for store listing and README
docs/            Privacy policy and terms of service
STORE_LISTING.md Suggested copy for Roku Developer Dashboard fields
```

## Screenshots

| File | Description |
|------|-------------|
| [screenshots/00-channel-poster.png](screenshots/00-channel-poster.png) | Channel poster (HD) |
| [screenshots/01-app-preview.jpg](screenshots/01-app-preview.jpg) | Splash / preview image |

Add device captures of setup, active round, break, and session complete screens to `screenshots/` when available for the Channel Store submission.

## Legal

- [Privacy Policy](docs/PRIVACY.md)
- [Terms of Service](docs/TERMS.md)

## License

App software is maintained in the [bjj-timer-roku](https://github.com/robertsima/bjj-timer-roku) repository. Marketing assets in this repository are provided for store listing and documentation purposes.
