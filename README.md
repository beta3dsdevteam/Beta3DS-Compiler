This is a Windows compiler for Beta3DS, a port of b1.7.3 Minecraft to the 3DS Family of systems.

REQUIRED
- a .jar of version b1.7.3
- dsp.firm file for audio

Makes the 3ds folder for Beta3DS, so you don't have to copy files by hand.

1. Double-click Beta3DS-SD-maker.exe.
2. Browse to your b1.7.3.jar (the one from .minecraft\versions\b1.7.3\).
   Optional, but it gives you the real textures.
3. Browse to your resources folder (the one from your 1.7.3 instance).
   Optional, but it gives you the sounds and music.
4. Optional: browse to dspfirm.cdc, the DSP firmware you dumped with the DSP1 homebrew.
   Audio on the 3DS needs it. The app can't make it for you.
5. Browse to your SD card (the folder that holds, or will hold, the 3ds folder).
6. Press "Make the 3ds folder".

It writes:
  3ds\beta3ds.3dsx              the game (built into the app)
  3ds\beta3ds\b1.7.3.jar        a copy of your jar
  3ds\beta3ds\resources\...     the sound and music folders the game reads
  3ds\dspfirm.cdc               a copy of your DSP firmware, if you chose one

Then put the card in the 3DS and start Beta3DS from the Homebrew Launcher.

Nothing from Minecraft is in this app. Everything from Minecraft is copied from your own files.
The game runs without the jar, resources or firmware; it just uses its built-in textures and
sounds (and no audio without the firmware).

To build it yourself, see source\build.sh.
