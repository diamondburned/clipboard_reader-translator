# clipboard_reader-translator

####Reads out loud your clipboard, sends a notification and reads the original clipboard out loud.

The script automatically detects the language of the clipboard and translates (reads) them accordingly.

Requirements: `gawk` (3.1+), `notify-osd` (to send notifications) and `bash`

Optional requirements: `mpv`/`mplayer` and `mpg123` for Text-to-Speech

Instructions:
1. Clone the repository: `git clone https://github.com/diamondburned/clipboard_reader-translator.git`
2. `cd` into the directory
3. Copy whatever you want to be read/translated/whatever
4. Run `./readtrans`
5. [Optional] Bind `readtrans` to a key (make sure to properly modify the locations inside `readtrans`)

Screenshot: https://dl1.moddage.site/1519187822.png (Audio will be played)

Script originally from: http://git.io/trans

GitHub Repository: https://github.com/soimort/translate-shell

The script was *slightly* modified to remove formattings in order for Bash to not screw up. The script was renamed to `mainscript` and was originally made by `soimort`.
