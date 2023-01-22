# Incremental Search for Vscode

<!-- todo: there is many gifs to load -->
<!-- todo: only READme file is needed-->

This extension brings a very basic emacs isearch experience to VS Code.

## What is Incremental Search?

Incremental search is a better find mode than ctrl-F.

[isearch.gif](art.txt)

Normal search uses ctrl-F and F3 shortcuts to enter the find mode and
uses enter and shift-enter shortcuts to find next or previous find matches.

## Story-time

I used emacs editor for a while and get addicted to the incremental search feature in it. It helped me on navigating the text files seamlessly. It made it a habit for me to use find and search features everywhere.

Even after using Vscode, I could not do without the incremental search feature. I tried to find incremental search in many extensions. Most of them are too obtrusive in the sense that they change the general Vscode experience too much. I did want a working, simpler extension.

After 3-4 months of frustration, while I was adding Vscode shortcuts I find the CloseFindWidget and Find Next commands. I figured out that i can create a basic
incremental search just by creating three more keybindings.

Then i bind those shortcuts. I have been very content while i have been using them.

Today i figured out that i can also ship those changes as an Vscode extensions.

## Use cases

This extension defines three shortcuts.
Ctrl-f after first  

## Getting Started

There are not any settings in the extension.
Installing the extension will load shortcuts automatically.
In order to disable the shortcuts, disable the extension.

## Replicating the Experience Without Installing the Package

You can replicate the experience by creating keyboard shortcuts manually.
You can get the names of the shortcuts from the Feature Contributions tab. 

To create shortcuts manually:
Press Ctrl-Shift-p to run the command "Preferences: Open Keyboard Shortcuts"
or use the shortcut (Ctrl-k Ctrl-s)

[gif]


Bind C-f to Find Next
(Inherit it from <enter> Find Next)

[gif]


Bind leftArrow to closeFindWidget
Bind rightArrow to closeFindWidget
(Inherit those from <escape> closeFindWidget keys)

[gif]

## My github account

[My github account](https://github.com/oakasapoglu)
