# **\[Workshop\] Emacs configuration**

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

In the `~/.emacs.d/` directory, create a `themes/` folder, and download the [monokai theme](https://github.com/oneKelvinSmith/monokai-emacs/blob/master/monokai-theme.el) in it.

In the `interface.el` file, ensure that the monokai theme is loaded each time you open emacs.

---

## **Exercise 5 - Mouse click**

Create a `mouse.el` file (make sure it is included in the `init.el` file).

In the `mouse.el` file, enable the mouse click.

---

## **Exercise 6 - Tabs**

Create a `programming.el` file.

In order to respect the Epitech coding style, make sure that the TAB key indents the text with 4 spaces.

---

## **Exercice 7 - Pairs**

Using the `electric-pair-mode` package, ensure that:
- the `"` character is added to the buffer when you add a `"` character
- the `}` characher is added to the buffer when you add a `{` character
- the `'` character is added to the buffer when you add a `'` character

---

## **Exercise 8 - Trailing spaces**

In the `programming.el` file, make sure that all the trailing spaces are removed when you save the buffer.

---

