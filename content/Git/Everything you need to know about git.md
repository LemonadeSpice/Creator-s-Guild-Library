## What it is
- Fun tool
- Manages everything for you, lets you download changes and uploads yours
- Keeps track of who did what, when and exactly what they did
- Works as a dynamic backup that lets you undo any changes easily, there is a high chance most broken projects are recoverable if git was used
- Downloads/uploads changes **only**, much better than sending the whole file every time

>[!info]
>Nowadays you don't have to use the big scary terminal, [Github Desktop](https://desktop.github.com/download/) runs most of the same commands you can run on terminal but they are comfortable buttons and UI instead
>
>![[Pasted image 20260614183440.png]]
## What to do to not break it
- Let your team know when you're working on a file (avoids merge conflicts)
- Don't touch files being edited by other people
- Do a Git Pull before you start working
- Do a Git Commit and and a Git Push when you're done

## What the is a merge conflict
- Something you don't want
- You were editing one or more files while somebody else uploaded a modified version of it
- Will let you decide which file (or lines of a file) to keep and which ones to delete
- Won't happen if you follow everything above