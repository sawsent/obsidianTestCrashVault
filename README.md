This vault is to reproduce the weird bug I found covered [here](https://forum.obsidian.md/t/obsidian-crashes-in-very-specific-circumstances-due-to-lf-vs-crlf/85190)

Opening [[Crash Content CRLF]] will crash your obsidian. 

If you open crash.md in some other editor, change line endings to LF, and restart obsidian, there will be no crash.

If you open [[Crash Content LF]], you will see exactly what is in [[Crash Content CRLF]], but with LF line endings, so it will not crash.

If you open another editor, change [[Crash Content LF]] line endings to CRLF, and open the note, obsidian will crash.
