# Matthew's Reading Journal

My name is Matthew Sklepowich and I am currently learning various programming languages through Code Fellows. This page is meant for me to store notes as I learn new things with them. My Github portfolio page can be found [here](https://github.com/Matt-Sklep).

### What is the Growth Mindset?

```
The Growth mindset is a way of thinking that helps an individual succeed inside and outside of work. 
By not walking away at the sight of a problem, but instead using the challenge as a motivation, 
you're able to become more productive. Turning your frustrations into motivations creates better
habits for you and helps lift up your way of life.
```

### Reminders to Keep a Growth Mindset

- Don't walk away from a problem when you get stuck. Recognize what you're feeling from this problem, and use those feelings as motivation to find the solution.
- At the end of the day, ask yourself how it went. Highlight the positives and recognizes the negatives *while coming up with solutions so they don't occur again.*
- Your peers aren't competition, but are people who you can bounce ideas off of. Using two minds is greater than one, and this will lead to all parties becoming stronger.

--------------------------------------------

### Using Markdown with Github Pages

Using Markdown with Github Pages is a great way to build an impressive-looking website without any knowledge of programming languages.

#### Symbols Used for Styling
Markdown uses a small handful of symbols on a keyboard to create stylistic changes to your webpage. There are a few select symbols that drastically change the flow of your webpage from just being a screen with text.

```# Symbols```
By putting 1-6 `#` symbols (and a space) before a header, you can change the size of your headings to help visitors know where something new starts. 1 # is the biggest a header can be, and 6 # is the smallest.

```* & _ Symbols```
The asterisk and the underscore both allow you to bold and italicize your text, by placing a number of them on both sides of the text you want to emphasize. *1* of these symbols on each side italicizes, **2** will bold, and ***3*** will italicize and bold.

```Making Lists```
Lists are incredibly easy to make. All one needs to do to start one is by starting at the number 1, adding a period and a space, and then adding the first item in the list. After that Markdown will automatically add entries every time you press enter. 
1. It's
2. Very
3. Simple!

Unordered lists are very similar, though to start them you use the `-, *, or +` sign with a space before each item.
- Just
- Like
- This!

You can also add images, easily display code, and link to other webpages using Markdown!

#### Using GitHub Pages to start a Webpage
GitHub Pages is a tool that easily allows you to create your own website, again with no programming knowledge! Simply create a GitHub account, create a new, public Repository, and by traversing to the `Settings` menu at the top right of the page, then going to the `Pages` tab, you can launch your webpage to the public. GitHub Pages gives you many different themes to help make your website more appealing too!

--------------------------

### Learning the Terminal

```Finding a Good Text Editor```
Before learning the terminal, it's a good idea to find a good text editor to write programs into. There are tons of good text editors, but the best ones are the ones that:
- Help complete code keywords for you, to save you the time of typing a variable 600 times in a single document.
- Highlight the syntax used in your programs, to help you distinguish what is a variable VS commented out code or notes VS keywords.
- Has a bountiful amount of themes, which are particularly useful at reducing the eye strain you might feel from staring a computer screen for long periods of time.
- Has tons of plugins for you to download and use, which will help you be even more effecient while programming!

```Getting Started with the Terminal```

The terminal is an interface that allows you to input commands and get feedback from your computer. It can be a way to access your files, open programs, or create things, all without using your mouse! Within a terminal you have a Shell, which is how the computer will execute commands that are run within the terminal.

```Useful Commands within the Terminal```
The terminal has tons of commands to know and use within it, here are some of the most important ones and what they mean/do.

- The `echo` command can be used to display messages about specific things in the terminal, such as `echo $SHELL` to see what shell you're using.
- The `pwd` (print working directory) command tells you where you currently are within your terminal. 
- The `'ls` (list) command is similar to `pwd`, but you're able to enter in perameters to see various things about your location. The structure of the command is `ls [options] [location]`.
    - Using *paths* in our `ls` commands allows us to see various files in specified places. an *absolute* path will show us files in relation to the *root* directory of the computer, while a *relative* path will show us files in relation to where we currently are in the system.

    Some important shortcuts to using paths are:
    - `~`: your home directory. Instead of typing out `/home/user/documents` typing `~/documents` will grant you the same result.
    - `.`: your relative directory. Using `./documents` will show you the files to where you currently are in the system.
    - `..`: your parent directory. Can be used as many times as one needs, but for each `../` used it shows files from that many folders above where you're currently located in the system.
 
- The `cd` (change directory) command allows you to move into a specific path from where you currently are, though you must specify the location you wish to go via `cd [location]`. Without any specified location you are brought back to the home directory.

When navigating through paths in the computer, one can get stuck on a file name with spaces in it. A folder with the name `Holiday Photos` will cause trouble for the terminal as it sees *Holiday* and *Photos* as separate conditions. Two ways to get around this issue are:
1. Quotes: Typing in `cd 'Holiday Photos'` will consider anything inside the quotes to be a single item.
2. Backslash: Typing in `cd Holiday\ Photos` will remove the character immediately after the `\`, and thus treat it as a single item.

Hidden files can be made, that the terminal ignores, by putting a `.` at the beginning of the file name. One can force the terminal to acknowledge these hidden files by using the `-a` option.

---------------------------





