SOL MOONARGE - ENGLISH TRANSLATION
PC Engine Super CD-ROM2 | Japan | ICCD3004 | Redump Rev 2
Translation credits: TruMisery + AI Assist

ABOUT THIS RELEASE
------------------
Follow Soleil and Sonia through an original Irem RPG, with the story,
battles and menus in English. The Japanese voice performances, CD music
and sound effects are preserved. Even the handwritten note after the
credits has been translated, right down to its secret button sequence.

WHAT'S IN ENGLISH
-----------------
- Story and NPC dialogue, choices, quest hints, treasure messages,
  location signs and save/load labels. Speaker names, punctuation and
  line breaks were reviewed in play; voiced scenes retain their pauses.
- English subtitles for voiced scenes, including the opening, major story
  sequences and finale. Caption timing and placement were checked
  against the Japanese performances.
- Battle commands and messages, spells, equipment, item and shop text,
  inventory, party and status screens. Class titles are written out;
  Luna and Lune follow the spellings in the original cast credits.
- A proportional English font and revised window layouts. Work included
  centering location plaques, fitting longer names and quantities, and
  correcting text that ran together or overlapped.
- An English naming screen with room for six characters. Custom names
  carry through to dialogue and menus, including North's naming scene.
- English labels in the original scene selector and an English postscript
  in the style of the original artwork. Its arrows, button numerals, heart
  and TEAM PD3 signature are preserved.

PLAYTEST FIXES
--------------
Shop fixes correct garbled prices and protect progression items from
accidental sale. Item names and chest messages were corrected, including
Rainbow Specs, Goddess Staff and Demon Sword. Other fixes address extra
dialogue advances, hard-to-read pages and several cases of menu or text
window flicker. The normal in-game save format is unchanged.

REQUIRED ORIGINAL DISC
----------------------
Sol Moonarge (Japan), Rev 2 - Redump disc 44625
Catalog number: ICCD3004
Reference: http://redump.org/disc/44625/

Start with a clean Japanese Redump BIN/CUE set. Keep the CUE and all
23 BIN files together. This single xdelta takes Track 02 as its input.
Track 23 stays on the disc unchanged. Do not apply the Track 02 patch
to Track 23: they are different raw files.

HOW TO PATCH - DELTA PATCHER
---------------------------
1. Make a working copy of the complete Japanese disc folder.
2. In Delta Patcher, choose this file from the copy as Original file:
     Sol Moonarge (Japan) (Track 02).bin
3. For XDelta patch, select:
     Sol Moonarge [PCECD][T-ENG][TruMisery+AI Assist][redump].xdelta
4. Leave checksum validation enabled and apply the patch. Compare the
   resulting Track 02 with the patched hash below. Do not select the
   CUE, a CHD, an ISO or a merged BIN as the input.
5. Keep the original track filenames so the CUE still finds them.
   Launch the CUE, not the individual BIN. For hardware, use the whole
   patched disc set when preparing your image or burning your disc.

TRACK 02 - BEFORE AND AFTER
---------------------------
Clean Japanese Track 02 (43,577,856 bytes)
  CRC32:   F06138F3
  MD5:     710f12dec4b0893e6fbc2df7c84f1b68
  SHA-1:   7a772e2395b7ad85eb72168dcf95db36ae1c5b23
  SHA-256: e9b0026920fdc294c1b9237ae8bd9c8ef3107cd35f284ee36036b9de3ede56c6

English Track 02 (43,577,856 bytes)
  CRC32:   EC541801
  MD5:     d91bbb08669c92a65f4e81a96b403c84
  SHA-1:   ae022ed7cd21d4223f1665fdd11e450f4edb0d7e
  SHA-256: 418f1bc58de5f1cfee36e862d45858ed9d6b391aa1d2fcc5569dc0ba6fdc032a

HOW BATTLE ACTIONS SHAPE YOUR CLASS
-----------------------------------
Soleil and Sonia each earn a title through their own actions in battle.
There is no required character level, and a title can change as you play.
What counts is how often you act, not how much damage you deal or heal.

Swordsman - Favor ordinary attacks with FIGHT.
Mage      - Favor offensive spells and go easy on DEFEND and FLEE.
Thief     - DEFEND or FLEE often. Both count the same; use DEFEND if you
            want to stay in the fight.
Spellsword - Mix FIGHT with items or spells cast on allies. Another route
             is to mix defensive actions with mostly offensive magic.
Priest    - Use items or cast spells on allies more often than you cast
            offensive spells. Work in DEFEND rather than relying on FIGHT.
Sage      - Favor DEFEND over FIGHT and balance offensive spells with
            items or ally spells. The game weights these differently:
            aim for a few more offensive casts than support actions.
            Equal numbers of each do not guarantee Sage.

Any usable battle item counts toward support, even if it does not heal.
Only the character taking the action gets credit.

OPTIONAL STATUS CHEAT
---------------------
Open a character's STATUS screen. Tap and release each direction:

  UP, UP, UP, DOWN, DOWN, DOWN

Listen for the short rising and falling confirmation sound. Close and
reopen Status to refresh the displayed stats. The code:

- Raises current party members below level 60 to level 60 with stat
  growth. It does not lower a higher level or stack extra stat boosts
  when repeated.
- Restores HP and MP, keeps them filled and supplies gold while active.
- Grants the sellable Demon Sword. If the bag is full, free a slot and
  enter the code again. An existing bag copy is not duplicated.

Resetting the game clears the active cheat. Levels, stats and items
already written to an in-game save remain in that save. To keep an
unassisted playthrough, use a separate save slot.

OPTIONAL RANDOM ENCOUNTER MENU
------------------------------
While exploring, tap and release:

  UP, DOWN, DOWN, UP, DOWN, DOWN, LEFT, RIGHT

Choose Double, Normal, Half or None. Button I applies the setting;
button II cancels. Resetting restores Normal.

BONUS FROM THE ORIGINAL GAME
----------------------------
The translated postscript reveals the original title-screen command:

  UP, LEFT, DOWN, RIGHT, II, I, II, I

This opens the scene selector. It is separate from the Status cheat.

TESTED ON
---------
- Geargrafx emulator
- Core Grafx + Super HD System3 Pro
- Turbo Duo

When checking the translation, boot the patched disc and start a game or
load a normal in-game save. An emulator state made on a different build
can restore the old text, artwork and program code.

REDUMP ORIGINAL TRACK CHECKLIST
-------------------------------
These are hashes of the clean input disc. After following the single-
patch instructions, only Track 02 should differ from this list.

  Track         Bytes    CRC32       SHA-1
  01      7,916,832    22144D0F    3b472f5e80bbf8259e09f8e4f547567bddb02490
  02     43,577,856    F06138F3    7a772e2395b7ad85eb72168dcf95db36ae1c5b23
  03     20,841,072    31C340D3    ad31854812a769fc6ba93e50d8d1b627e7fa4362
  04     13,930,896    FCD426AC    3584f6a254ceee2e6f014e7479bc168fdeec0504
  05     20,756,400    72266ABE    32b0f424e201e0be73a6c05dad29ef946b369ad9
  06     13,220,592    AD856637    3d6811af94e8a267b49f75daed40ebe7c3362c45
  07     16,435,776    128B38CA    099e68c2c11053b6eb725c02e621f4bd519fb6b4
  08     15,019,872    77AA901C    39dfcc9322970e3a076432dc518235cf7048968d
  09     15,734,880    927DA8E9    e7742576a78e6acd212776c020fc092ae7e25623
  10     18,830,112    C21180C3    9f24c4ee229b105ac5410e2b04927d1bae513fa8
  11     20,206,032    835077A1    38527189578d24b8b7aa09158c64550ea71726e7
  12     20,711,712    16E80C72    268759927d1372013238ed815f94c5c224f5e26d
  13     18,126,864    30C9255A    dad3081fc36e767440ec79763f2b9087c1d0829b
  14     34,381,536    07859D59    d022772724cccf8e532a9765af53fc213b13cc37
  15     32,996,208    FB9E5649    d3696d67bc946cec9527d3a526302f8ce72ccb52
  16     18,498,480    02F68729    b3dff3186f0bdf165a1640e54eca79e50c914ff8
  17     17,621,184    DED353CB    d990ca41b129bde6b42906d8b3d2db03c25a6cf0
  18     33,859,392    A71B2A82    d1c358872b49fd34e21cadd69644073a1e54a548
  19     14,610,624    C82382B5    b11129e039b6aca984b137be1ce267304cdd7297
  20     19,458,096    6418B6B6    609c68083996e1c689abdf940cd544ff668c5193
  21     28,873,152    C30B2D15    3b9b1c5aaad93e7f76bc1c5c92cef77d490528c9
  22     33,960,528    BFDF095D    aab522d8bf85e476bdc1777ce310615cd3c70177
  23     43,227,408    F048B3D7    2af282c912366dbb63caf7c5e0581a6224563b37

CREDITS
-------
English translation: TruMisery + AI Assist
Project direction, English editing and playtesting: TruMisery
AI assistance: translation support, programming, graphics, subtitles
and verification.

Thank you to the original Sol Moonarge team at Irem, and to everyone
keeping PC Engine games playable. Please keep this README with the patch.
This is an unofficial fan translation. The original game, artwork, voices
and music belong to their respective rights holders.
