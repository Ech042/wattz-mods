# Wattz mods

The finished custom mods for the Wattz pack, and nothing else. No source code.

## Players: one-time setup

1. Open the [`get-the-updater`](get-the-updater/) folder and download the `wattz_updater` jar
   (click it, then the download button).
2. Put it in your instance's `mods` folder, next to the other mods.
3. Start the game.

That's it. Every time you start the game, the updater checks this page and brings the pack's
custom mods up to date before anything loads. If you're offline, the game just starts with what
you have.

## Why this is safe

The list of mods here is signed with a key only the pack owner has, and every jar is checked
against it before it's installed. If anything here were changed by someone else, the updater
would refuse it and change nothing. The updater only touches the pack's own custom mods. It
never touches your other mods, configs or worlds.

To turn it off: delete the jar, or set `enabled=false` in `config/wattz_updater.properties`.
