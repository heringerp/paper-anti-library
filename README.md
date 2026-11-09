# Paper anti-library

An [anti-library](https://en.wikipedia.org/wiki/Antilibrary) is a pile of books owned but not yet read. This script tries to do the same but for papers in *.pdf format. Perhaps taking the 'pile' part a bit to literally.

Running the tool once will create the folders `~/paal/to_read` and `~/paal/finished`. Add new papers to the `~/paal/to_read` folder.

```
# Get the path of the most recently added paper (current paper)
paal

# Uses the $EDITOR environment variable to open a markdown notes file for the current paper
paal -r

# Marks the current paper as finished by moving it (and possibly its notes) to `~/paal/finished`
paal -f
```
