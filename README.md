# SideNotes Workflow for Alfred

[SideNotes](https://www.apptorium.com/sidenotes) is an app that keeps your notes on the side of the screen. Appears when you click a little bar or move your cursor to the screen side. 

[Alfred](https://www.alfredapp.com) is a powerful app that looks like Spotlight but
has far more features. Besides searching, it offers hotkeys, keywords, text expansions and more.
It can be easily integrated with other apps and now it's integrated with SideNotes, as well.

This workflow allows you to take notes in SideNotes, create new folders, change theme, search any text in notes and use snippets.

![SideNotes Workflow](https://user-images.githubusercontent.com/868275/139557524-5567773c-4c35-41d9-b320-f01e48a2088b.jpg)

## Features
SideNotes workflow offers:
* keywords (commands) – most of them starts with `sn ` prefix;
* possibility to define a global hotkey, so you can create a note with a selected text;
* ability to save current text (in Alfred) or the selected file in SideNotes;
* a fallback search.

## Creating Notes
You can create a new note using `sn note` command or its short version `:`
```
sn note hello world
```
or
```
: hello world
```

Then, once you press return key, you choose a folder and it's done.

### Creating Notes From Selected Text or File
You can create a note using selected text in any app. Or using a selected
file in Finder.

Simple press Option-Command-\\. Now you need to choose *Save in SideNotes*
option. Then choose a folder and your note is created.

#### Hotkey
You can set a hotkey for this action. Then you won't have to choose *Save in SideNotes*
action. To do so, open Alfred Preferences, go to *Workflows*, select *SideNotes*,
and find *Selection in macOS* object. Double click it, and set a hotkey.

## Creating Folders
To create a new folder, enter:
```
sn folder Folder Name
```

## Searching
To start searching, enter:
```
sn search text you're looking for
```

### Fallback Search
You can also start searching with entering the
text you're looking for in Alfred and choosing *Search SideNotes for '(...)'* option.

Please note that this option is not enabled by default. It's available by
configuring a [Fallback Search](https://www.alfredapp.com/help/features/default-results/fallback-searches/):
1. Open Alfred Preferences
2. Go to *Features* and look for *Fallbacks* section at the end.
3. Click *Setup fallback results*'.
4. Click + button and choose *Search SideNotes for '{query}'* from *Workflow Trigger*.
5. Click save.

## Choosing Theme
To quickly set a theme, enter:
```
sn theme
```
now choose a theme from the list, press return key and enjoy SideNotes
in a new look.

## Show SideNotes Preferences
You can quickly access SideNotes Preferences:
```
sn pref
```

## Snippets
SideNotes allows you to use your notes as [snippets](https://www.apptorium.com/sidenotes/tips/how-to-use-text-snippets).
You can quickly copy note content by pressing a Command-Option-C in the Search window.

With Alfred, it works even better. Simple enter `snippet` command, find your
note and press Return to copy note content or Command-Return to copy and **paste it
in the active app**.

## One More Thing
We've made a SideNotes theme for Alfred. Check it out here: [https://www.alfredapp.com/extras/theme/He7aMCi2Rz](https://www.alfredapp.com/extras/theme/He7aMCi2Rz)
