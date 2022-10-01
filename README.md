# Welcome to the Urbanclictionary repository!

# About

Urbanclictionary is a **commandline-based application** for the terrific [Urban Dictionary](https://cutt.ly/lV1iaTj).

The application has been made by [devlocalhost](https://cutt.ly/JV1izx1) and I've forked it to make it better! This is still a work in progress and the codebase is, **for now**, what they've originally written. The only thing that's been changed is this README file to make it more user-friendly.

# Installing the application

1. Clone the repository. If you don't know how to do it:
    1. Copy this URL: https://github.com/archthegreat/urbanclictionary/
    2. Open the Terminal (if you use Linux/MacOS) or [Git Bash](https://gitforwindows.org/) (if you use Windows)
    3. On the Terminal type:
        ```bash
        $ git clone https://github.com/archthegreat/urbanclictionary/
        ```
2. On your command line (Terminal/Git Bash) type:
    ```bash
    $ cd urbandictionary
3. The format for the command is:
    ```bash
    $ ./urbanclictionary [WORD] [RESULT_NUMBER] [%PAGE_NUMBER]
    ```


# How to use the application

The word is, of course, the word whose meaning you want to search.

Urban Dictionary has numerous entries for one word: the `result_number` refers to which entry you want to search for: the first entry would be '1', the second entry would be '2' and so on.

For some words, e.g. [bruh](https://www.urbandictionary.com/define.php?term=Bruh) there are **more than one page** for a word. For such words you can also specify the `page_number`. For example, if you'd want to see the 2nd page type `%2` instead of the `[PAGE_NUMBER]`

An example is provided here for the word *github* without mentioning any ```result_number``` or ```page_number``` (For most cases, this is what you'd want to do):
![Screenshot providing the output of ```$ ./urbandictionary github```](https://i.imgur.com/B46FCkR.png)

If you want the 3rd entry, you'd type:

![Screenshot providing the output of ```$ ./urbandictionary github 2```](https://i.imgur.com/N1OAAoI.png)

If you just type `./urbanclictionary` you'd see:

![Screenshot providing the output of ```$ ./urbandictionary```](https://i.imgur.com/riVOK32.png)

# A bit more about `word`, `result_number` and `page_number`

The following screenshots further illustrate the idea of `word`, `result_number` and `page_number`:
    
    1. `word`

    
![word](https://i.imgur.com/1WwWPsB.png)
    
    2. `result_number`

![result_number](https://i.imgur.com/YuaKnaE.png)

    3. `page_number`

![page_number](https://i.imgur.com/UmyGLcr.png)

---
NOTE: All of the commands in this example are in the directory `urbanclictionary` which is a clone of this repository. If you execute any command from this directory's parent, all commads would have to be preceded by `./urbanclictionary/urbanclictionary` instead of `./urbanclictionary`.