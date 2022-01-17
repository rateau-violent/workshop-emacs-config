# **\[Workshop COBRA\] Emacs configuration**

## **Exercise 0 - Setup**

1. Remove the `.emacs` directory at your root if it exists.
2. Create a `.emacs.d` directory at your root if it doesn't exists.
3. In the `~/.emacs.d/`, create a `init.el` file. This file will be the entry point of your configuration.
4. Make sure emacs is not opened in a graphical window but in a terminal (like during exams).
5. Here are the [emacs shortcuts](https://www.gnu.org/software/emacs/refcards/pdf/refcard.pdf) to help you.

---

## **Exercise 1 - Packages**

In order to install packages in emacs, you need to set up the archives links.

Setup the folowing package archives:
   - org: http://orgmode.org/elpa/
   - gnu: http://elpa.gnu.org/packages/
   - melpa-stable: http://stable.melpa.org/packages/
   - melpa: https://melpa.org/packages/

Before installing a package, make sure to refresh the packages content.

---

## **Exercise 2 - Lockfiles and backup files**

In the `init.el` file, make sure that the lockfiles and the backup files are disabled.

---

## **Exercise 3 - Lines and columns**

In the `~/.emacs.d/` directory, create a new file called `interface.el`.

In order for your configutation to contain the code written in this new file, make sure that it is included in the `init.el` file.

In the `interface.el` file, make sure that the configuration will display the number of lines and columns in your emacs buffer.


---

## **Exercise 4 - Theme**

**Required package:** monokai-theme

In the `~/.emacs.d/interface.el` file, enable the monokai theme so it is loaded each time you open emacs.

---

## **Exercise 5 - Mouse click**

**Required package:** xterm-mouse-mode

Create a `mouse.el` file (make sure it is included in the `init.el` file).

In the `mouse.el` file, enable the mouse click.

---

## **Exercise 6 - Tab characters**

Create a `programming.el` file.

In order to respect the Epitech coding style, make sure that the TAB key indents the text with 4 spaces.

---

## **Exercice 7 - Pairs**

**Required package:** electric-pair-mode

Ensure that:
- the `"` character is added to the buffer when you add a `"` character
- the `}` characher is added to the buffer when you add a `{` character
- the `'` character is added to the buffer when you add a `'` character

---

## **Exercise 8 - Trailing spaces**

In the `programming.el` file, make sure that all the trailing spaces are removed when you save the buffer.

---
 
## **Exercise 9 - Treemacs**

**Required package:** treemacs

Treemacs is a package that enables to have a tree with some repositories and the foilders/files it contains in your emacs buffer.

In the `programming.el` file, make sure that treemacs is launched each time you open a new emacs buffer.

--- 

## **Exercise 10 - Shortcuts**

**Required package:** tab-bar-mode

Create a new file called `keyboard-shortcuts.el`.

Ensure that:
   - `Ctrl+n` opens a new tab bar in your emacs buffer
   - `Ctrl+q` closes the tab bar in your emacs buffer
   - `Ctrl+t` opens / closes treemacs
   - `Ctrl+A` adds a new repository to treemacs
   - `Ctrl+D` removes a repository to treemacs

---

## **Exercise 11 - Autocomplete**

**Required packages:** global-company-mode, company-c-headers

Make sure that autocompletetion is enabled for C language and C headers.

---

## **Exercise 12 - Package auto installation**

In the `init.el` file, create a list of packages and make sure that all of the packages are installed (if they are not already) when you launch emacs.
