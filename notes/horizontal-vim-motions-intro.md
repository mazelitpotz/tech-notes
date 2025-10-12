# Introduction to Horizontal Vim Motions

Within a line, you can use `h` and `l` to move horizontally. Both options allow you to move, respectively, one character to the left or one to the right.

Let's use a sample file to go through the details of this note.

```txt
This is a simple line.
```

The easiest method that you can learn is typing any number before `h` or `l`. If you want to move the cursor over the "s" in "simple", you would type `10l`. That's easy to remember, but not so effective in your daily use.

The next step is moving word by word. There are three keys to remember here.

- `w` moves the cursor to the start of the next word.
- `e` moves the cursor to the end of the current word.
- `b` moves the cursor to the start of the previous word.

Starting with the cursor at the start of the file above (initial "T"), and typing what I am mentioning, you'll get the following movement.

You can also use any number before any of those letters to "multiply" its effect.

- `w`: the cursor moves over the "i" in "is".
- `w`: the cursor moves over the "a".
- `2w`: the cursor moves over the "l" in "line" (you use this command to move two words ahead).
- `b`: the cursor moves to the "s" in "simple".
- `e`: the cursor moves to the "e" in "simple".
- `3b`: the cursor moves to the "i" in "is"
- `3e`: the cursor moves back to the "e" in "simple".

In short, this system becomes more effective because it's easier to guess the number of words than the number of characters. I often use `w` and `b` (rarely `e`) along with other horizontal motions.

---
 #vim