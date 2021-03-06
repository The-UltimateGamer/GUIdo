# FAQ

## What do I need?

You will need:
- A working Python interpreter, version 3 and up
- The [pygame module](pygame.org) installed

## How do I run the program?
Run `stub.py` either by double-clicking on it (in Windows) or using the command line.

## FAQ for `vis`
### How do I use `vis`?
When you open it up through the virtual terminal, you will be put in *input mode*, which means whatever you type will be written into the file. `vis` is a *line-based* editor, meaning you can only edit the line you're on.  

Enter `vis <filename>` to start editing a file. Press <kbd>Enter</kbd> whenever you have finished editing a line. The line will be immediately saved and cannot be altered again in this editing session. Press <kbd>Esc</kbd> to exit `vis`.

### Where do the files go?
Everything you created in Winnux 58 will go into the `files.img` *virtual disk*. You can view them using the `cat` command in the virtual terminal. Note that `files.img` is **NOT** a traditional disk image, so don't try to mount that!