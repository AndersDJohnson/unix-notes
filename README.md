# unix-notes
UNIX notes (Linux, Mac).

## See Also
* [AndersDJohnson/mac-notes][mac-notes]
* [AndersDJohnson/windows-notes][windows-notes]
* [AndersDJohnson/dotfiles](https://github.com/AndersDJohnson/dotfiles)

## Process on port?
```
lsof -i :3000
```

## Loops

### Files

```
for FILE in *.jpg; do
  # ...
done
```

```
for FILE in `find . -type f -name "*.txt"`; do
  # ...
done
```

```
while IFS= read -r file; do
  # ...
done < "files.txt"
```

http://www.cyberciti.biz/faq/bash-loop-over-file/



[mac-notes]: https://github.com/AndersDJohnson/mac-notes
[windows-notes]: https://github.com/AndersDJohnson/windows-notes
