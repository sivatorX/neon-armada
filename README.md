# Neon Armada ⚓

A neon-styled Battleship game that runs in the browser: one HTML file, no install.

## ▶ Play now: https://sivatorx.github.io/neon-armada/

## Features
- **Four opponents:** Easy, Medium, Hard and Expert. The Hard AI counts every way your ships could still lie.
- **Hidden bombs:** each sea hides 3. Hit one and you lose your next turn.
- **Bonus shot:** sink a ship and you fire again.
- **Radar:** a one-use power-up that counts hidden ship squares in a 3×3 area.
- **Show AI thinking:** a heat map of where the AI thinks your ships are.
- **Online 2-player:** create a room, send the 4-letter code to a friend and play over the internet (direct WebRTC via PeerJS, with an automatic backup connection through a public MQTT server for mobile data and strict networks).
- **Expert opponent:** plays like Hard and has its own one-time radar.
- **Turn timer:** an optional 10 seconds per shot. Too slow and you lose the turn.
- **Achievements:** 10 medals to unlock, from "First victory" to "Grand Admiral".
- **Drag & drop setup:** drag a placed ship to move it, tap it to turn it.
- **Invite link:** the host copies a link that fills in the room code for a friend.
- **Replay** of the finished game, **saved ship layouts**, win streak record.
- Neon theme, drifting waves, particle explosions, confetti, and sound and music made in code (Web Audio API).

## How to play online with a friend
1. Open the game and press **Create room**.
2. Send the 4-letter code to your friend.
3. Your friend types the code and presses **Join**.
4. Both place your ships and press **Start battle**. The player who made the room fires first.

## License
MIT. You are free to use, copy and change this code, **as long as you keep the credit to the author**
(the copyright notice in [LICENSE](LICENSE) and at the top of `index.html`).

© 2026 Armin ([sivatorX](https://github.com/sivatorX))
