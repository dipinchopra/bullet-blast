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

Both fighters start unarmed with five hearts. Collect arena weapons: pistols have three shots, rockets have one. Pistol hits cost one heart and rocket blasts cost three. Fighter contact only bounces the bodies, without health loss. Each fighter’s current weapon and remaining shots appear below their hearts. The final hit and explosion play before the result screen; defeating the opponent advances to the next duel. Mobile controls remain visible after the intro, with movement on the left and firing on the right; they are inactive while paused or viewing menus.

A teal arrow follows the player. Characters and weapons are 30% larger on mobile, with compact health and ammo displays. Levels 1–5 have one opponent, levels 6–10 have two, levels 11–15 have three, and so on. Defeat all opponents before advancing. Mobile firing aims at the nearest opponent.

Rockets swim along a wavy path with a tapering trail. The runnable HTML embeds its assets; original audio and artwork are included for editing. Mochiy Pop One's font license is included in `ui assets/Font/Mochiy_Pop_One/OFL.txt`.
