 # Assignment 3 – Terminal Navigation Practice Sheet

## Commands for macOS / Linux / Git Bash (Windows PowerShell equivalents)

| # | Task | Command | PowerShell |
|---|---|---|---|
| 1 | Show current folder | `pwd` | `pwd` |
| 2 | List files | `ls` | `ls` |
| 3 | List with details + hidden files | `ls -la` | `ls -Force` |
| 4 | Create a folder | `mkdir practice` | `mkdir practice` |
| 5 | Enter the folder | `cd practice` | `cd practice` |
| 6 | Create an empty file | `touch index.html` | `ni index.html` |
| 7 | Create nested folders | `mkdir -p css/images` | `mkdir css/images` |
| 8 | Go up one level | `cd ..` | `cd ..` |
| 9 | Go to home directory | `cd ~` | `cd ~` |
| 10 | Copy a file | `cp index.html backup.html` | `cp index.html backup.html` |
| 11 | Rename / move a file | `mv backup.html old.html` | `mv backup.html old.html` |
| 12 | Delete a file | `rm old.html` | `rm old.html` |
| 13 | Delete a folder | `rm -r css` | `rm -r css` |
| 14 | Print file contents | `cat index.html` | `cat index.html` |
| 15 | Clear the screen | `clear` | `cls` |
| 16 | Open folder in VS Code | `code .` | `code .` |

## Practice Exercise

Starting from your home directory:

1. Create `website/` containing `index.html`, `css/style.css`, and `images/`.
2. Go into `css`, then return to `website` with `cd ..`.
3. List everything recursively using `ls -R`.
4. Rename `index.html` to `home.html`, then rename it back.
5. Open the folder in VS Code.

## Answers – Commands Used

```bash
cd ~
mkdir -p website/css website/images
touch website/index.html website/css/style.css
cd website/css
cd ..
ls -R
mv index.html home.html
mv home.html index.html
code .
```

## Practice Result

I successfully practised all 16 terminal navigation commands using PowerShell in Visual Studio Code. I also completed the additional website folder exercise, including creating files and folders, navigating between directories, listing files recursively, renaming files, and opening the website folder in VS Code.

**Status: Completed**
