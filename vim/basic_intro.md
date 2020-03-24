# A Basic Introduction to Vim

Vim is a very powerful _text editor_ which actually can do much more than just editing text. The vast variety of commands, plugins, scripts, services allow you to tune vim to the level of your extreme comfort. Always remember, when you are learning Vim, just think of becoming lazier like just find a modify a piece of text investing in the least possible efforts. The more you get lazy, the more Vim helps you get lazier.


## Opening Vim

On a command prompt type the following command

```
gvim file.txt
```

This command will open a file named 'file.txt' in a new window where vim is running. I you type ```vim``` instead of ```gvim``` vim will open up in the same window as the command prompt. Note that vim will create the file if it does not exist.


## All the tricks

I will write all the tricks that I will learn here


- Regex for start of the word: ```\<```
- Regex for end of the word: ```\>```

- Regex for matching anything except a ',' ```[^,]``` 
- Catching backreferences: ```\( \)``` are used to catch backreferences.
