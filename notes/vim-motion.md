# Vim Motions

This assumes you already have a file with some content in it (a `txt` file is enough). If you are getting started, you can create it with another text editor and open it with Vim later.

After opening Vim, you'll be in **Normal Mode** (no need to worry about the naming). In brief, you can move your cursor without writing.

The four keys for moving the cursor are: `h`, `j`, `k`, and `l`.

- `j` and `k` are respectively for Down and Up.
- `h` and `l` are respectively for Left and Right.

You can also use the arrow keys in Vim. Indeed, `hjkl` act exactly like that. Vim gurus would say you should never use the arrow keys, but I believe there's nothing wrong with them.

I often use `j` and `k` and seldom use `h` and `l`. It makes sense in my workflow (I mainly use Vim for writing) because I often move up and down, and, when moving horizontally, there are better ways to do it. You can press `j` and `k` with your right index and middle fingers — those usually rest over `j` and `k`, roughly in the middle of the keyboard. Therefore, it's very easy to get used to them.

Before pressing any motion key, you can type any number, even multiple digits. For example, `14j` moves your cursor 14 lines down, and so it happens for the other motion keys. I don't use it that often, as I must think carefully about what number t use. It's slower to press `j` 14 times, but at least I have immediate visual feedback.
