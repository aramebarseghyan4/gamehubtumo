CITY DRIVE — sound files
========================

Drop these audio files into this folder. The game loads them automatically.
Any file that's missing just plays nothing (no error) — so add them at your pace.

Required filenames (.mp3, or change the names in SOUND_URLS inside car_game_3d.html):

  engine_loop.mp3    A SEAMLESS looping engine sound (idle/low rev works best).
                     The game pitches it up/down with speed for an RPM effect,
                     so a steady idle loop sounds great. ~2–5 sec, loops cleanly.

  engine_start.mp3   Starter crank that catches into a running engine. ~0.5–1.5 sec.

  engine_stall.mp3   Engine dying / cutting out. ~0.3–1 sec.

  crash.mp3          Metal impact / crunch for hitting a wall. ~0.3–1 sec.

Where to get free sounds (check the licence — CC0 is easiest):
  • https://freesound.org        (search "car engine loop", "car crash", "engine start")
  • https://pixabay.com/sound-effects/
  • https://mixkit.co/free-sound-effects/car/

Tips:
  • .ogg also works in most browsers; just update the extensions in SOUND_URLS.
  • For a clean engine loop, trim to a zero-crossing and make sure start≈end.
  • Keep files small (mono, 96–128 kbps mp3 is plenty) for fast loading.
