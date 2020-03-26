# A Basic Introduction to Vim

Vim is a very powerful _text editor_ which actually can do much more than just editing text. The vast variety of commands, plugins, scripts, services allow you to tune vim to the level of your extreme comfort. Always remember, when you are learning Vim, just think of becoming lazier like just find a modify a piece of text investing in the least possible efforts. The more you get lazy, the more Vim helps you get lazier.


## Opening Vim

On a command prompt type the following command

```
gvim file.txt
```

This command will open a file named 'file.txt' in a new window where vim is running. I you type ```vim``` instead of ```gvim``` vim will open up in the same window as the command prompt. Note that vim will create the file if it does not exist.

## Motion and Operators

Operators in vim are used to specify the operation to be done on the selected text. Motion allows to select the text in an efficient way.



```c```: Change
```d```: Delete
```y```: Yank
```gU```: Make uppercase
```gu```: Make lowercase

## All the tricks

I will write all the tricks that I will learn here


- Regex for start of the word: ```\<```
- Regex for end of the word: ```\>```

- Regex for matching anything except a ',' ```[^,]``` 
- Catching backreferences: ```\( \)``` are used to catch backreferences.


## These key names might be useful

These names for keys are used in the documentation.  They can also be used
with the ":map" command (insert the key name by pressing CTRL-K and then the
key you want the name for).

notation	meaning		    equivalent	decimal value(s)	~
-----------------------------------------------------------------------
<Nul>		zero			CTRL-@	  0 (stored as 10) *<Nul>*
<BS>		backspace		CTRL-H	  8	*backspace*
<Tab>		tab			CTRL-I	  9	*tab* *Tab*
							*linefeed*
<NL>		linefeed		CTRL-J	 10 (used for <Nul>)
<FF>		formfeed		CTRL-L	 12	*formfeed*
<CR>		carriage return		CTRL-M	 13	*carriage-return*
<Return>	same as <CR>				*<Return>*
<Enter>		same as <CR>				*<Enter>*
<Esc>		escape			CTRL-[	 27	*escape* *<Esc>*
<Space>		space				 32	*space*
<lt>		less-than		<	 60	*<lt>*
<Bslash>	backslash		\	 92	*backslash* *<Bslash>*
<Bar>		vertical bar		|	124	*<Bar>*
<Del>		delete				127
<CSI>		command sequence intro  ALT-Esc 155	*<CSI>*
<xCSI>		CSI when typed in the GUI		*<xCSI>*

<EOL>		end-of-line (can be <CR>, <LF> or <CR><LF>,
		depends on system and 'fileformat')	*<EOL>*

<Up>		cursor-up			*cursor-up* *cursor_up*
<Down>		cursor-down			*cursor-down* *cursor_down*
<Left>		cursor-left			*cursor-left* *cursor_left*
<Right>		cursor-right			*cursor-right* *cursor_right*
<S-Up>		shift-cursor-up
<S-Down>	shift-cursor-down
<S-Left>	shift-cursor-left
<S-Right>	shift-cursor-right
<C-Left>	control-cursor-left
<C-Right>	control-cursor-right
<F1> - <F12>	function keys 1 to 12		*function_key* *function-key*
<S-F1> - <S-F12> shift-function keys 1 to 12	*<S-F1>*
<Help>		help key
<Undo>		undo key
<Insert>	insert key
<Home>		home				*home*
<End>		end				*end*
<PageUp>	page-up				*page_up* *page-up*
<PageDown>	page-down			*page_down* *page-down*
<kHome>		keypad home (upper left)	*keypad-home*
<kEnd>		keypad end (lower left)		*keypad-end*
<kPageUp>	keypad page-up (upper right)	*keypad-page-up*
<kPageDown>	keypad page-down (lower right)	*keypad-page-down*
<kPlus>		keypad +			*keypad-plus*
<kMinus>	keypad -			*keypad-minus*
<kMultiply>	keypad *			*keypad-multiply*
<kDivide>	keypad /			*keypad-divide*
<kEnter>	keypad Enter			*keypad-enter*
<kPoint>	keypad Decimal point		*keypad-point*
<k0> - <k9>	keypad 0 to 9			*keypad-0* *keypad-9*
<S-...>		shift-key			*shift* *<S-*
<C-...>		control-key			*control* *ctrl* *<C-*
<M-...>		alt-key or meta-key		*meta* *alt* *<M-*
<A-...>		same as <M-...>			*<A-*
<D-...>		command-key (Macintosh only)	*<D-*
<t_xx>		key with "xx" entry in termcap
-----------------------------------------------------------------------


