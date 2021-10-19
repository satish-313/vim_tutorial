# vim_tutorial

1.	how to open a file in vim from command prompt or terminal?
	$ vim <file_name>
	$ vim hello.html

2.	how to quit vim ?
	$ :q! - quit without saving
	$ :wq - quit wiht saving

3.	how to write vim ?
	first press i letter, then it will shift to insert mode. after insert mode you can write.
	for exit from insert mode press esc.

4.	how to save file without quiting vim?
	$ :w - it will save the file without quiting, similar to clrt+s. After save it will automatic shift to insert mode.

5.	how to undo the vim text editor?
	$ u

simple navigation in vim
1.	to move up - k, to move down - j, to move left - l, to move right - h.
	to perform the k or l multiple time instead use the number and command. it not excluse to move command, it apply to every
	vim command line - 20k move up 20 line, 4u undo previous 4th time.

common command in vim

1.	how to delete a line in vim?
	$ dd - delete whole line

2.	how to move bottom line to top line in vim?
	$ G - move the cursor to botton line or anothe command is ]]
	$ gg - move the cursor to top line or another command is [[

3.	how to skip the some code or paragraph block ?
	$ } - move some code block to next bottom space line 
	$ { - move some code block to above space line

4.	how to copy paste in vim?
	$ yy - to copy to clipboard
	$ p - to paste content to down
	$ P - to paste content to up. 
	$ in case of dd it will add the content in clipboard.

5.	how to copy code block in vim?
	first we need to know how much i select the file for this we use visual mode in vim.
	$ V - for visual mode here we can select the file by using l or } command then $ yy or$ dd for copy 
	then $ p - for paste

6.	how to insert a line in vim?
	$ o - for insert a line and it by default shift into insert mode.
	$ O - for insert a line above the cursor.

command for movement in the horizontal direction

1.	how to move to next word in vim ?
	$ w - move to next word.
	$ b - move to backward direction.

2.	how to move start of line?
	$ 0 - move to start of line.
	$ ^ - move to start of letter in a line.

3.	how to move end of line?
	$ $ - move to end of line.

4.	how to move particular thing in a line?
	$ t<symbol or letter> - cursor move before the thing.
	$ f<symbol or letter> - cursor move to the thing.

5.	how to move to concecutive similar?
	$ % - if you select the { and press $ it will move to next } sign.

6.	how to change a word in vim?
	$ cw - it will delete a word and put in insert mode.

searching a similar word

1.	how to search similar word or function in vim?
	$ * - to search similar word.

2.	if want to repeat a command in searching like t( one more instance?
	$ ; - to move next instance.

3.	how to center your work or cursor to middle?
	$ zz - move or shift your work to center of screen.

4.	how to move a letter forward and insert to i mode?
	$ a - shift to insert mode and move curosor to next line.

5. 	how to move the end of line, it is not similar to $ sign?
	$ A - move the cursor left to end of line and insert to insert mode.

6.	how to delete a letter in vim?
	$ x - delete a letter.

miscellaneous command

1.	how to change case in vim?
	$ ~ - to change the case.

2.	how to redo the last command in vim?
	$ . - repeat the last command.

3.	how to replace a letter in vim?
	$ r<letter> - replace letter.

4.	how to indent in the vim ?
	$ > - to indent first select the file using V.

5.	how to use macro or save bunch of repeating command?
	$ q - it will start the then save a letter to start command. use @<save_letter> to execute the command.
	to end the command use q again.