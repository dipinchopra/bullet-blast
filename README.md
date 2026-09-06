# Bullet Blast

A portrait HTML5 Canvas emoji duel game. Open `index.html` directly in a modern browser, or run:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Controls

- Desktop: WASD or arrow keys to move, mouse to aim, click or space to fire.
- Touch: use the bottom joystick to move and hold FIRE to aim automatically at the opponent and shoot.
- P / Escape pauses. Use the sound toggle to mute.

Both fighters start unarmed with three hearts. Collect arena weapons: pistols have three shots, rockets have one. Pistol hits cost one heart; rocket blasts are lethal. Each fighter’s current weapon and remaining shots appear below their hearts. Defeat the opponent to advance automatically to the next duel.

Rockets swim along a wavy path with a tapering trail. The runnable HTML embeds its assets; original audio and artwork are included for editing. Mochiy Pop One's font license is included in `ui assets/Font/Mochiy_Pop_One/OFL.txt`.
