# Fishing Planet Boat Walking — Chamaeleon Cruiser (V4)

An experimental, unofficial boat-walking feature for the **Chamaeleon cruiser** in **Fishing Planet 2.10.5.2, Microsoft Store/Xbox app on Windows**. Walk around the rear deck, lower seating area and bow, and climb to the upper helm deck.

This is a Windows helper, not an Xbox One/Series console add-on or a Microsoft Store listing. Compatibility with the Steam edition, other boats and other game versions has not been established.

## What this feature adds

Walk around your boat for exploration and enjoyment, instead of staying at a fixed fishing or steering position. You must already have access to the Chamaeleon cruiser through the game. This helper does not unlock the boat, bypass purchases, or change fish behaviour, bite rates, rewards, tackle settings or engine controls.

**[Download the V4 Windows ZIP](https://github.com/dale746/chamaeleon-boat-walking/releases/download/v4/Chamaeleon-Whole-Boat-Walking-PC-Prototype-V4.zip)** · **[Release notes](https://github.com/dale746/chamaeleon-boat-walking/releases/tag/v4)**

## Download and start

Download the V4 ZIP from [Releases](https://github.com/dale746/chamaeleon-boat-walking/releases) and extract it. Choose **Chamaeleon-Whole-Boat-Walking-PC-Prototype-V4.zip**, not GitHub’s automatically generated source-code archives.

1. Start Fishing Planet normally and enter a fishing position on the Chamaeleon.
2. Run **Start walking.cmd** once.
3. Focus the game and press **F8** to enable walking. The left stick moves; the right stick looks around.
4. Press **F8** again to return to your normal fishing position.

There is no ten-minute timeout. The helper stays available until the game closes. Run it again after each new game session. It does not start automatically or modify installed game files. Use one walking-helper version per game session; restart the game before switching versions.

## Fishing and controls

Walking with a held rod, casting and continuing to move were observed during development. Drawing a rod without losing the moved position and use from all five fishing positions were reported in testing. Slow-trolling walking was tested in V2; V4 retains those controls. Use the controller to walk while trolling; keyboard W/S keeps the game’s normal throttle behavior.

**A keeps its normal interaction.** Switching to the helm, changing fishing positions, boarding, certain menus, leaving the game window, or rod-stand positioning can return normal placement. F8 can enable walking again from a normal fishing position. Fish behavior, tackle settings and engine controls are unchanged.

## Routes and verification

Use either side platform to reach the lower seating area. At the small landing above the short side stairs, turn inward before continuing forward. For the higher stairs, approach from the rear, walk forward onto the first steps, then turn inward toward the steering wheel.

The V4 live test recorded **two climbs up the left higher stairs to the helm and two descents**, plus a bow round trip and return to the lower seating area. The right higher stair route passed offline tests; a complete live climb on that side has not been recorded.

## Known limitations

- Narrow landings and turns can still feel awkward.
- Stairs use a smoothed first-person approximation; decorative rails or stair hardware may visibly clip. This is not full character collision.
- The enclosed cabin, cabin roof and canopy are excluded.
- F8 may refuse activation at some viewing angles. Finish any boat interaction, adjust your view and try again.
- Whether other players see the moved position, and a complete fish catch from it, remain unverified.

The ZIP includes detailed instructions, helper source and the MinHook license. This project is not affiliated with or endorsed by Fishing Planet.

**V4 ZIP SHA-256:** `c763c6ddfbb43115ba6e16cad755eb4d170e6fd543cfd9ed303b0e90f64ffa9f`
