Requires Dyalog APL 17.1 or newer.

Clone to:
* `Documents\Dyalog APL Files\StartupSession\out` if on Windows
* `$HOME/dyalog.files/StartupSession/out` everywhere else

Start APL.

Run `⎕SE.Out.init`

Move and resize session and output panes as wanted.

Hover mouse over output to see meta-info, or double-click to temporarily insert it for copying.

Run `⎕SE.Out.cls` to clear the screen.

You may want to experiment with editing `('Posn'(0 17))('Size'(107 103))` in `init.aplf` to adjust initial position and size.

To make the changes permanent, save your session file with `2⎕NQ⎕SE'FileWrite'`.
