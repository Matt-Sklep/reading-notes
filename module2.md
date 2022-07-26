# Module 2

## Learning the Terminal

### Finding a Good Text Editor

Before learning the terminal, it's a good idea to find a good text editor to write programs into. There are tons of good text editors, but the best ones are the ones that:

- Help complete code keywords for you, to save you the time of typing a variable 600 times in a single document.
- Highlight the syntax used in your programs, to help you distinguish what is a variable VS commented out code or notes VS keywords.
- Has a bountiful amount of themes, which are particularly useful at reducing the eye strain you might feel from staring a computer screen for long periods of time.
- Has tons of plugins for you to download and use, which will help you be even more effecient while programming!

### Getting Started with the Terminal

The terminal is an interface that allows you to input commands and get feedback from your computer. It can be a way to access your files, open programs, or create things, all without using your mouse! Within a terminal you have a Shell, which is how the computer will execute commands that are run within the terminal.

### Useful Commands within the Terminal

The terminal has tons of commands to know and use within it, here are some of the most important ones and what they mean/do.

1. The `echo` command can be used to display messages about specific things in the terminal, such as `echo $SHELL` to see what shell you're using.
2. The `pwd` (print working directory) command tells you where you currently are within your terminal.
3. The `ls` (list) command is similar to `pwd`, but you're able to enter in perameters to see various things about your location. The structure of the command is `ls [options] [location]`.

    - Using *paths* in our `ls` commands allows us to see various files in specified places. an *absolute* path will show us files in relation to the *root* directory of the computer, while a *relative* path will show us files in relation to where we currently are in the system.

    Some important shortcuts to using paths are:

    - `~`: your home directory. Instead of typing out `/home/user/documents` typing `~/documents` will grant you the same result.
    - `.`: your relative directory. Using `./documents` will show you the files to where you currently are in the system.
    - `..`: your parent directory. Can be used as many times as one needs, but for each `../` used it shows files from that many folders above where you're currently located in the system.
4. The `cd` (change directory) command allows you to move into a specific path from where you currently are, though you must specify the location you wish to go via `cd [location]`. Without any specified location you are brought back to the home directory.

When navigating through paths in the computer, one can get stuck on a file name with spaces in it. A folder with the name `Holiday Photos` will cause trouble for the terminal as it sees *Holiday* and *Photos* as separate conditions. Two ways to get around this issue are:

1. Quotes: Typing in `cd 'Holiday Photos'` will consider anything inside the quotes to be a single item.
2. Backslash: Typing in `cd Holiday\ Photos` will remove the character immediately after the `\`, and thus treat it as a single item.

Hidden files can be made, that the terminal ignores, by putting a `.` at the beginning of the file name. One can force the terminal to acknowledge these hidden files by using the `-a` option.
