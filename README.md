# Features

This extension adds tkinter snippets to VS Code. There are currently 7 snippets in this pack, however I will be adding more.

For list of snippets look at the bottom of the page

# Usage

To use these snippets simply type a snippet into your editor and press tab. There will be fields you have to fill out, such as position, text etc. To fill this info out simply start typing. Once you fill in a field press tab to move on to the next field.

There are currently two types of snippets. For info on what each type means look at the section below

# Snippet types

## Regular snippets

Lets you type in the name of the variable for your element, as well as some basic info usually used with the element.

### Example:

![](images/flcexample.png)

## No variable snippets

prefix: **nv** 

If you put nv before the regular snippet, you get an element without a variable. These are not always recommended however they are useful sometimes.

### Example:

![](images/nvflcexample.png)

## Basic snippets

prefix: **b**

If you put b before the regular snippet, you get an element with only the prompt for a variable name and window selection.

### Example:

![](images/bfbcexample.png)

# List of snippets

## Regular snippets

**ftc** - creates a new tkinter window

**flc** - creates a new label

**fec** - creates a new entry

**fbc** - creates a new button

## nv snippets *(no variable)*

**nvflc** - creates a new label without using a variable

**nvfec** - creates a new entry without using a variable

**nvfbc** - creates a new button without using a variable

## b snippets *(basic)*

**bftc** - creates a new basic tkinter window

**bflc** - creates a new basic label

**bfec** - creates a new basic entry

**bfbc** - creates a new basic button

## Other snippets

**tki** - from tkinter import *