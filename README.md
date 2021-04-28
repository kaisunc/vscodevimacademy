<!-- <img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/banner.png" /> -->
<!-- <img alt="" src="http://localhost:5501/data/markdown/banner.png" /> -->
<div align="center">
      <img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/banner.png" />
</div>
<h1>VSCODE VIM ACADEMY</h1>

# ABOUT
An educational game to learn vim and vscode keys in logical, digestable levels.
Builds up your vim muscle memories by practicing vim keys 2~5 keys each level. Level text and keys are randomly generated on a per level basis. For example,

1. move forward or backward by word
2. go up or down a random number of lines
3. delete word forward or backwards from current position
4. delete word, undo or redo
5. select, delete, or change lines
6. delete, copy, or paste words
7. and more

players complete 10 sets of the tasks as quickly with as little key presses as possible. Hints and manual will be listed on the right panel(CONSOLE), your performance will be logged per task based on how fast your performed and how many keypresses you used.

---

<br>

## CATEGORIES
Levels are separated into five categories.

1. ![](https://via.placeholder.com/15/1589F0/000000?text=+) `Motions`
2. ![](https://via.placeholder.com/15/1589F0/000000?text=+) `Actions - Horizontal`
3. ![](https://via.placeholder.com/15/1589F0/000000?text=+) `Actions - Vertical`
4. ![](https://via.placeholder.com/15/1589F0/000000?text=+) `Surrounds`
5. ![](https://via.placeholder.com/15/1589F0/000000?text=+) `UI`

## COLOR CODED ACTIONS
In the editor, tasks will be shown as a color outline around the text. It can be a single character, words, lines, text objects or blocks.

1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `Inside - Move the curor inside the yellow box`
1. ![](https://via.placeholder.com/15/fd6883/000000?text=+) `Delete - Delete the contents of the red box`
1. ![](https://via.placeholder.com/15/f38d70/000000?text=+) `Select - Select the contents of the orange box`
1. ![](https://via.placeholder.com/15/addb78/000000?text=+) `Paste - Paste the contents of green box at the green cursor position`
1. ![](https://via.placeholder.com/15/e4d2d4/000000?text=+) `Copy - Copy the contents of the grey box`
1. ![](https://via.placeholder.com/15/b267e6/000000?text=+) `Editing - change, insert, indent, comment, add, minus depending on the level`
1. ![](https://via.placeholder.com/15/1589f0/000000?text=+) `Outside - Helper type for the mark level, moving outside completes the task`

<br>

# QUICK START

1. Install [ VSCODE VIM ](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) extension to enable vim emulation in vscode.
2. Install [ VSCODE VIM ACADEMY ](https://marketplace.visualstudio.com/items?itemName=kaisun.vscodevimacademy)
3. Open the command palette [ ctrl+shift+p ]()
4. Enter [ "start vva" ]() in the command palette to start the game.
   <details>
   <summary>
    Video Tutorial
   </summary>
   <img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/activation.gif" />
   </details>

<br></br>

## USER INTERFACE

### LEVEL INFO
1. Star rating on the top right is for importance
1. Total time
1. Performance log, try to keep the cyan line below the red line
   1. ![](https://via.placeholder.com/15/01B5B8/000000?text=+) `Current - current task speed`
   1. ![](https://via.placeholder.com/15/BE9E3B/000000?text=+) `Current Avg - average of current level tasks`
   1. ![](https://via.placeholder.com/15/C64349/000000?text=+) `Target - based on my times`
   1. ![](https://via.placeholder.com/15/000000/000000?text=+) `Hist - these are based on my times while play testing`
1. Task table
1. Current level keys and key description

<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/uiLevelInfo.png" />

---

<br></br>

### LEVEL NAVIGATION
To quickly continue to the next level without using the mouse, this widget will show up at the end of a level. Move the cursor using the vim keys,
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `0 - Previous Level`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `b - Retry Current Level`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `w - Next Level`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `$ - Open the Buy Extension Page`

To choose a specific level, use the console to go back to the level selection page
You can also bind keys for previous, next, and retry levels

1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `vva.prevLevel`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `vva.retryLevel`
1. ![](https://via.placeholder.com/15/f9cc6c/000000?text=+) `vva.nextLevel`

<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/endCursor.gif" />

---

<br></br>

### Vim Cheatsheet HUD

Painstakingly built SVG Animation! Unlimited resolution!

Press [ ctrl+alt+c ]()to toggle the cheatsheet in editor, this feature does not require activating VVA or a VVA license, as long as the VVA extension is installed, the cheatsheet can be shown in the editor. Grab the extension now before I put this feature behind the pay wall!

<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/cheatSheetsm.gif" />

---

<br></br>

# DEMO
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/quickDemo.gif" />

---

<details>
<summary>
Basic Levels and UI
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/basics.gif" />
</details>

<details>
<summary>
Word - Move to beginning of word(s) or end of words(s)
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/word.gif" />
</details>

<details>
<summary>
Actions Motions
</summary>
<img alt="" src="https://kaisunc.github.io/vscodevimacademy/data/images/actions_motion.gif" />
</details>

<br>

# ISSUES
1. Change to a Dark Theme, VVA currently only supports dark themes.
2. I had intended to support multiple languages, theres only english, partial chinese and japanese for now. To change language, go to settings/vva/language

<br>

# LEVELS

<details>
<summary>
Motions
</summary>

1.	Left & Right 1
2.	Up & Down 1
3.	All Directions
4.	Left & Right 2
5.	Up & Down 2
6.	Beginning of Word 1
7.	Beginning of Word 2
8.	End of Word 1
9.	Review - Word Beginning & End
1.  Bol, Eol, First Letter
2.  Review - Word Beginning & BEFCOL
3.  Beginning of Word 3
4.  End of Word 2
5.  Review - WB & ege
6.  Top and Bottom of Page
7.  Up & Down Relative
8.  Review - Top, Bottom & Relative Line
9.  Goto Line
10. Review - Goto & Relative Line
11. Top, Middle, Bottom of Screen
12. Up, Down Half Screen
13. Up, Down Full Screen
14. Review - Screen Line Movements
15. Goto Next Paragraph
16. Goto Next Sentence
17. Goto Sections 1 - End Of
18. Goto Sections 2 - Start Of
19. Goto Sections 3 - Nearest Start or End
20. Goto Sections 4 - Start or End
21. Goto % of File
22. Hover
23. Next Pair Match
24. Searching For Letters 1
25. Word Search 1
26. Word Search 2
27. Word Search 3
28. Goto Definition
29. Marks
</details>

<details>
<summary>
Actions - Horizontal
</summary>

1. Visual Mode 1 - Select & Exit
2. Visual Mode 2 - Incrementally Select
3. Select Word
4. Delete Word
5. Paste Word
6. Delete & Paste Word
7. Copy Word
8. Change Word
9. Replace Word
10. Rename Symbol
11. Actions + Motion
12. Actions + Motions
13. Undo & Redo
14. Select Find Letter
15. Select To Letter
16. Delete & Backspace
17. Delete & Backspace 2
18. Change Case
19. Add, Minus 1
20. Add, Minus 2 - Numbered
21. Replace Char & Replace With
22. Swap Characters
23. Insert At & After Cursor
24. Insert At EOL & FCOL
</details>

<details>
<summary>
Actions - Vertical
</summary>

1. Select Line
2. Select Line Incrementally
3. Delete Line
4. Copy Line
5. Change Line
6. Paste Line
7. Insert Line
8. Replace Line
9. All Line
10. Select Lines
11. Copy Lines
12. Insert Lines
13. Delete Lines
14. Change Lines
15. Copy Line & Paste
16. Join Lines
17. Swap/Move Line
18. Indent Lines
19. Comment Lines

</details>

<details>
<summary>
Surrounds
</summary>

1. Select Word Text Object
2. Select All Surround
3. Select Inside Surround
4. Delete/Change All
5. Delete/Change Inside
6. Add Surround
7. Delete Surround
8. Change Surround
9. Delete HTML Tag Inner/Outer/Surround
</details>

<details>
<summary>
UI
</summary>

1. Select Group
2. Left/Right Editor
3. Left/Right Group
4. Quick File Navigation 1 - Search
5. Quick File Navigation 2 - Last File

</details>

<br>

# THANKS
For the four initial buyers and supporters of VVA, gave me some faith that this just might work.

If you find this extension useful, spread the word, give me some feedback at the git repo or extension marketplace and perhaps buy the extension.
With enough support, I would like to rework the task decorationOptions to use svg animations instead of the vscode default fadeIn fadeOut css animation. Something cool, like arrows pointing to navigating positions or text delete animations using SVG.


# NOTES
Buy a license to unlock all the levels

[![paypal](https://www.paypalobjects.com/en_US/TW/i/btn/btn_buynowCC_LG_wCUP.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7SQ5JH6B6MHFJ)

<!-- ## NOTES TO SELF
Source GIT repo is local private
Public GIT repo is https://github.com/kaisunc/vscodevimacademy with SOURCE README copied over
Seller page is ./ , copy images from SOURCE markdown dir, NEED this for image hosting for public repo
vvaServer GIT repo is for generating licenses from paypal ipa
Vscode Marketplace page is updated when published, uses README from SOURCE REPO -->
