# pbcopy

`pbcopy` is a helpful command that you can use to copy a terminal command output to your clipboard.

If you run the command `ls` within a folder, you see a list of all the files and sub-directories within that folder. But you can only see them through your terminal.

If you want to copy the output of every command — we'll use `ls` in this example, type the following.

```terminal
ls | pbcopy
```

You won't see anything in the output, not even the result you expect from the initial command. That's because it's all on your clipboard. If you open a standard `.txt` file, you can paste the content into it.