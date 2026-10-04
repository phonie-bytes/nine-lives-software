# Changelog

All versions are on [GitHub Releases](https://github.com/phonie-bytes/noir-midnight-ledger/releases).

## v5.4.1 - 2026-10-04
- A fiction disclaimer: at the end of the credits, on the About screen, in the player's manual
  and the README. Port Harlow is imaginary; any resemblance to real people or events is coincidental.
- **Ten save slots** (was five); the save / load screen fits them all, and named saves show the
  name and score without running under the buttons.
- A dev tool that writes named practice saves (e.g. "Talk to Knuckles") into empty slots.

## v5.4 - 2026-10-04 - "The Liars"
- Four new people, each with a portrait, a voice and things to say - not all of it true:
  - **Vera**, the Blue Moon's cigarette girl, swears Eddie left with a woman in Rita's red coat.
  - **Swede**, a drunk sailor on Harbor Street, "saw" Eddie fall off Pier 9.
  - **Officer Dunn**, a friendly young cop, whispers that Pike's been flashing money.
  - **Mr. Fisk**, Eddie's neighbor, knows exactly where Eddie hid the papers. He doesn't.
- Four new red-herring deductions, and two new endings for believing them:
  **The Wrong Woman** and **The Easy Answer**. Dunn's story turns Muldoon against you;
  Fisk's sends you on a wasted trip that costs forty minutes of the clock.
- Every lie has a detail in the world that gives it away, for players who look closely.
- Fixed: after an answer that ends the story (an accusation over the phone), the topic menu
  no longer pops back up in front of the ending.

## v5.3 - 2026-10-04
- **Rename and delete saved games**: every slot on the save / load screens has RENAME (type a
  name, Enter to keep) and DELETE (with a "for good?" check). Names survive saving over a slot.
- Fixed: the screenshot tools (`--screens`, `tools/doc_images.ps1`) could overwrite the
  player's autosave. The tools never autosave now.

## v5.2.1 - 2026-10-04
- Eddie's hat in Warehouse 9 now pins its clue whether you LOOK at it or USE it (before, only
  LOOK did - so the "where Eddie died" deduction could be missed), and it's easier to click.

## v5.2 - 2026-10-04
- Talking with a gun on you no longer gets you shot on the spot: you get an answer, and it
  costs two seconds of the standoff clock. (Talk too long and you're still shot.)
- A non-violent way out of the Pier 4 cannery ambush: hand Brody's gunmen his envelope.

## v5.1 - 2026-10-04
- Fixed: calling it in from the Pier 9 call box no longer jumps to Kane's office while the
  police are still arriving - the pier scene plays out at the pier, then act two begins.
- A cheat for the end: type a certain name on the last page (or during the credits) and they
  list **what you missed**, with the points each was worth. (The design manual has the code.)
- **QUIT** button on the title screen.

## v5.0 - 2026-10-03
- **Deductions**: click two cards in the case notebook to connect them and work something out.
  Some are required (the Blue Moon password, who "B." is, where Brody goes tonight), some
  score points. Each act is still 100 points.
- **Red herrings**: not every clue is true. Lies and planted evidence add up to wrong
  conclusions: the Pier 4 cannery ambush, accusing honest Muldoon, or phoning in Big Tony
  for Eddie's murder - a new ending, **The Wrong Man**.
- **Difficulty**: Easy / Normal / Hard - second chances (5/3/1), hints and gut feelings, "?"
  on doubtful clues, standoff time, deadlines, TAB labels.
- **Timed standoffs**: a DRAW! bar and a ticking clock whenever someone has a gun on Kane;
  fumbling (like loading the revolver) costs seconds.
- **Deadlines and health**: a clock to midnight in each act; miss it and Kane wears down
  until he rests - or dies. Fights hurt too.
- **Pause menu** (Esc / MENU) with the version and credits, save / load, notes, settings, quit.
- **Settings**, remembered between games: game speed, text speed, look, volumes, difficulty.
- New room: the Pier 4 cannery. New sounds: the standoff tick, the deduction chime.

## v4.3 - 2026-09-30
- The end credits roll by themselves a few seconds after the last page (or click ROLL CREDITS).
- The credits (and the About screen) say the game was made with the assistance of Claude.
- Pictures in the manuals: 36 screenshots and room paintings in `docs/images/`, rebuilt from
  the game itself by `pwsh tools/doc_images.ps1` (`--doc-images` for `--screens` / `--autoplay`).
- The last honor pop-up no longer covers the newspaper on the final page.

## v4.2 - 2026-09-30
- **Documentation that grows with the game**: `docs/MANUAL.md` (player's manual),
  `docs/DESIGN.md` (design & systems manual), generated `docs/WALKTHROUGH.md` and
  `docs/REFERENCE.md` (a test fails when they fall behind the game), this changelog.
- **Second chances**: three per game. Some deaths can be survived - depending on what Kane
  carries and how he has treated people - putting you back a moment before the fatal move.
- **New death screen**: a scene for each way to die (shot, drowned, beaten, poisoned, run
  down, drunk), a fade through red, a Sierra-style epitaph, and why a second chance isn't there.
- **End credits**: cast with portraits, designer, studio, your ending - then THE END.
  Roll them from the final page or from the About screen.
- **The Blue Moon's furniture fixed**: stools and table legs were being painted over by the
  floor in every look; now proper stools, pedestal tables and bistro chairs (Kane walks around them).
- `--autoplay --hard` plays the rough route; `--screens` also captures credits and death screens.

## v4.1 - 2026-09-30
- Sierra-style studio intro: **Nine Lives Software** - a cat on a rooftop against the moon,
  a nine-note jingle, "presents... a game designed by Pieter De Villiers". Skippable.

## v4.0 - 2026-09-30
- **Act two, "The Bluecoat"**: five new rooms, cab travel, six new characters, a finale
  standoff, four endings. The title screen offers *act one only* or *the full story*.
- **Honor meter**: rough people up or pull a gun for answers; honor decides who helps you
  and how it ends.
- **Case notebook** (N): clue cards, red string, current lead, honor.
- Sierra-style portraits in dialogue; Kane idles and smokes; depth sorting behind props.
- Tension music and a stinger at standoffs; crowd murmur in the club.
- Instant start-up (music composed in the background); About screen.

## v3.0 - 2026-09-29
- Pathfinding around furniture and people; double-click exits; "ask about" topic menus.
- Red accent in every room; rain splashes, puddle ripples, neon glow; club dust and haze;
  cigarette smoke; Rita sways; fades between rooms.
- Typewriter text with voice blips; per-room jazz; foghorns.

## v2 + accent - 2026-09-29 (untagged, commit `6827a72`)
- The red accent look; C cycles accent / grayscale / 1-bit.

## v2.0 - 2026-09-29
- Grayscale noir with lighting, vignette and film grain; hover highlights; TAB labels;
  crisp text; save/load with autosave.

## v1.0 - 2026-09-29
- The original 1-bit black & white adventure: six rooms, 100 points.
