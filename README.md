This vault is to reproduce the weird bug I found covered [here](https://forum.obsidian.md/t/obsidian-crashes-in-very-specific-circumstances-due-to-lf-vs-crlf/85190)

Opening [[Crash Content CRLF]] will crash your obsidian. 

If you open any of the broken files in some other editor, change line endings to LF, there will be no crash if you open them.

If when you clone the repo line endings are automatically updated to `LF`, going into another editor and changing [[Crash Content CRLF]] line endings back to `CRLF` will make it crash again.
