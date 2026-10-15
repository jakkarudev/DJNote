# Changelog

## 1.3.1 - 2026-10-15

The biggest update since launch. Desktop builds: universal macOS DMG (Apple Silicon and Intel) and Windows EXE/MSI. Android: Google Play.

### New
- **Library view**: see every Track you own in one place, whichever Playlist it's in.
- **Recently Deleted**: your last 10 deletions from the past 30 days, on every device. Undo removing Tracks from a Playlist, deleting a Playlist, or deleting Tracks from your Library.
- **Remove from Playlist** is now separate from **Delete from Library**. Removing a Track from a Playlist no longer deletes it.
- **Deleted Tracks stay in your DJ Sets and Sessions**: a Track you delete from the Library still shows, marked, in the sets that used it, with its transition notes. **Restore** puts it back in your Library. If you already have a Track with the same title and artist, you choose which to keep.
- **Matches belong to their Playlist**, and travel with it when you share or export it.
- **Export files**: Playlists, DJ Sets and Sessions export and import in one format, including transition notes, Deleted Tracks and where each value came from. When importing a DJ Set, you pick which Tracks to bring in.
- **Audio import**:
  - Reads genre, mood and energy from your files' tags.
  - Never invents a BPM or key it couldn't detect.
  - Remembers which values you typed yourself and never overwrites them without asking.
  - Lets you stop an import part-way and keep what was already analysed.
- **Duplicate tracks**: when an import finds a Track you already have, overwrite it field by field or skip it.
- **Focus vs. play**: tapping a Track selects it to look at; it gets the neon glow, and suggestions and Match colours are for it. **Play** marks what's actually playing (shown by the pulsing waveform on its cover), and it stays current until you play another Track, so a pause between Tracks doesn't record it twice. Play straight from the suggestions, and use the new Mix Assistant strip.
- **Live Sessions survive a crash**: if the app is closed mid-gig, your Live Session (played Tracks and the current Track) comes back when you reopen it. **Back** now works during a Live Session.
- **The app remembers your open Playlist** on each device.
- **Custom genres and moods follow your account** to every device, and you can remove ones you no longer want.
- **Account**: change your password, username and profile picture. **Reset account** erases your data everywhere but keeps your sign-in. Deleting your account erases it from all your devices.

### Changed
- **Free plan limits**: 2 Playlists, 60 Tracks per Playlist, 100 Tracks in the Library, 10 DJ Sets and 10 Sessions. Anything you already have over a limit is kept and can still be edited. Premium removes every limit and all ads.
- **Settings changed offline** are kept and sent once you're back online.

### Fixed
- **The app opens fast again.** It could sit on the loading screen for up to 30 seconds, online or offline; now it opens straight away from what's on your device and catches up in the background.
- **Sync is much faster** and no longer times out on large libraries. Only changed items are downloaded.
- **Editing on two devices**: the newest edit wins, and a device finds out when its change lost.
- **The selected Track no longer shows as a Match against itself.**
- **Deletions stick**: a deletion is never undone by an older edit from another device. Only Undo, Restore or importing the item again brings it back.
- Staying signed in while offline (from 1.2.2).

## 1.2.1 - 2026-06-14

- Published macOS x64 DMG release artifact for DJNote 1.2.1.
- Published Windows x64 EXE release artifact for DJNote 1.2.1.
- Updated app version metadata to 1.2.1.

## 1.1.3 - 2026-06-13

- Published initial public macOS release artifact.
- Added public documentation repository for DJNote downloads and release notes.
- Source code remains in the private engineering repository.
