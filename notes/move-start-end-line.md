# Move to the Start-End of the line

You can move to the start or end of the line. This is faster than [jumping through words](horizontal-vim-motions-intro.md).

There are three characters to remember here.

- `0` moves to the start of the line (no matter which character you have)
- `^` moves to the first non-blank character. This is often useful for programming when you usually use indentation. Therefore, the first character of a line may be a 
- `$` moves at the end of the line.

If you are familiar with [Regular Expressions](https://en.wikipedia.org/wiki/Regular_expression), you know that `^` and `$` define, respectively, the start and end of the string you are dealing with.

If you also want to add some text at the start/end of the line, there's a better system. You can use `I` (capital `i`) to automatically move the cursor to the start of the line and switch to Insert Mode. You can also use `A` to move to the end of the line and automatically append some text.

Usually, `A` is the character I use the most, as it's very common to add new things after some text that you already have.

---

#vim 
