# Modify a file in Vim

When opening a document in Vim, you are in **Normal Mode**. In this mode, you can primarily move your cursor and do other things like copy, paste, and delete. If you want to insert new text, you would need to enter **Insert Mode**.

There are several ways to do this. The most immediate is by pressing `i`. It stands for "Insert", and it places the cursor before the character highlighted in Normal Mode.

Let's make an example. Suppose you have:

```
Hello Word!
```

There's a typo here, and you want to fix it.

After opening the file, the cursor will be positioned directly over the initial `H`. From here:

- Move the cursor using `l` until you get to the final `d`.
- Press `i` to enter **Insert Mode**. The cursor changes its shape, becoming thin, and positions itself between the `r` and the `d`.
- Add the missing `l`, as you would do in a standard text editor.
- Come back to normal mode by pressing `Esc`.

The file is now changed but not yet saved. To save the file, type `:w` (column-w).

Once the file is saved, you can [close the document](vim-quit.md).

---

#normal-node #insert-mode #vim