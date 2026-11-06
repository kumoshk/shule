# shule
A Linux Python Tkinter text editor, authoring environment, IDE, plaintext e-book reader, and so on.

You can download and read about Shule on my website. See <https://vertex.alwaysdata.net/software.html> and <https://vertex.alwaysdata.net/shule_changelog.html>.

A few notes:
* Shule is Python source code. It's not compiled. It doesn't need to be compiled.
* The interface is fairly minimal. It has a text area, a menu, a statusbar, and a tab bar.
* Shule is feature-rich. No minimalism here.
* Shule is innovative. You will find lots of features here that you probably won't find elsewhere.
* Shule allows you to be productive.
* Shule allows you to find and quickly access what you've created (if you choose to use the pertinent features).
* Shule has a concept that it refers to as indexes. Indexes are simply directory structures with uniquely-named text files within. However, Shule makes it fast and easy to access and create these in a variety of ways. There are custom indexes, directory indexes, and file indexes. Custom indexes have code names and arbitrary directories that you specify. Directory indexes are indexes for a whole directory (the index is an index in that directory). A file index is an index for a specific file. So, if you write a novel or something, you can make a file index for it that serves as a glossary, an encyclopedic dictionary, or some such (in plaintext).
* Shule has Python-style regular expressions (not Tkinter-style ones, despite using Tkinter). That means you can do groups and functions, too.
* Password-protection is a thing.

Here are some of the features I personally use a lot, in no super particular order:
* Favorites. I start me editor, press Ctrl+Shift+D and type in whatever favorite I'm looking for. This pulls up the files I need at the locations I need them.
* Compose keys. In Shule, these are four different keys that allow you to enter a code, after which something special happens. It might output text (of any particular length) or execute a function. You can make your own codes and your own schemes. You can save your compose schemes. Compose keys are really nice when you run out of keyboard shortcuts: The Menu compose key is the one used for those by default. The left-Windows key is the one that most closely resembles the Linux compose key. Right-Windows key and the Insert key (not the ten-key pad one) are two more compose keys.
* Custom indexes (I'll probably use file indexes and directory indexes more often in time)
* Timestamps.
* Search and replace (often with regular expressions), and related features
* Jump (Go to line)
* Reading mode paragraph jumps (up and down); this helps me to stay sane
* Random name generation, and stuff like that
* Tabs
* Auto-indent
* Word wrap
* Color customization
* Inverting colors: Menu+inv
* Margin adjustments (and Menu+tm to toggle them on and off)
* Ctrl+Shift+i (to open/create files/directories by path)
* Ctrl+m (to quickly open/create a file in the same directory as the open file)
* Undo/redo
* Upper-case, lower-case, and title case
* Sort ascending/descending/shuffle: Menu+asc, Menu+des, Menu+shu
* Alt+2 (to bullet every line)
* Shift+Alt+2 to unbullet every line
* Alt+3 (to number every line)
* Shift+Alt+3 to un-number every line
* Pressing tab on selected text to indent every line
* Pressing shift+tab on selected text to unindent every line
* copy/paste/cut
* Jump to random line
* Password-protection (symmetric encryption) of files
* I code in Python in it a lot, so I use F5 to run programs a lot

Warnings and disclaimers:
* Shule has a single developer who doesn't get paid for it. (Not zillions of professionals.)
* The source code does not conform to every industry standard. It has its own standards.
* There is no syntax highlighting, nor is there line numbering (but you can see what line you're on in the statusbar).
* I imagine at least a large handful of features are probably new to you. Don't forget to use Ctrl+z to undo if you need to.
* Updates may or may not be compatible with backed-up data, depending on what I update.
* You are advised to use the latest version. Some of the old versions have some pretty major bugs. You should normally use the latest version, and check for updates (especially soon after a release). The changelog should tell you when I find new bugs, even before a release. If you are using a super old version, you should know that the current one is way better!
* I've been coding in Kubuntu 26.04.1, lately. It's possible some of the changes I've made since then might not work as favorably on other environments (but as far as I know, it still works fine on others).
