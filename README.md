# OOT Doot

A phone-friendly, single-file web app that plays the 12 fixed Ocarina of Time song melodies as distinct tones. It uses the remake's L, R, A, Y, X note order and displays each sequence while it plays.

## Open it on your phone

1. Put your phone and computer on the same Wi-Fi network.
2. From this folder, run `python3 -m http.server 8000` on your computer.
3. Find your computer's local network IP address, then open `http://COMPUTER-IP:8000` on your phone (for example, `http://192.168.1.20:8000`).
4. Turn up the phone volume, enable the game's ocarina microphone input, and hold the phone near the console microphone.

The page needs no build step or external dependencies. Tap a song to play it; use Stop playback to interrupt it. The Scarecrow Song is omitted because its notes are player-created.
