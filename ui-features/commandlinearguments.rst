Command Line Arguments
~~~~~~~~~~~~~~~~~~~~~~

:-CD: Allows the game to run without the Yuri's Revenge CD. Requires
  the content of the Yuri's Revenge CD to be copied to the Red Alert 2
  directory first. The First Decade users already have all the required
  files installed, so no further action has to be taken. Command line
  option to not require the Yuri's Revenge game disk.
:-NOLOGO: Prevents the EA logo video from playing before the game
  begins to load. NB: Launch Base has its own option to just prevent the
  video playing for mods that do not include their own video. Command
  line option to not play the EA/Westwood logo video.
:-LOG: Turns debug.log file writing on initially. See Internal Errors
  / Debugging
:-STRICT: Throws an Internal Error on game load if a not-necessarily-
  critical error is detected. For example, when you set a flag to a non-
  empty value that cannot be parsed. NB: There are several existing
  errors in the stock rules that will trip this so you will need to
  clean them up before using it.
:-AI-CONTROL: Enables AI Control feature. Entering this command in the
  command line before opening Yuri's Revenge allows the player to assign
  a hotkey to allowing AI control. NB: This feature was designed
  primarily for the purposes of offline testing and AI design testing.
  Due to this, feature complexity, lack of interest and a change in
  personnel, please note that this feature is NOT officially supported.


.. versionadded:: 0.1



<<<SEPARATOR>>>
