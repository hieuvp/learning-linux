# Vim Essentials

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Essential Navigation Commands](#essential-navigation-commands)
- [Exercise 02 Essential Navigation Commands](#exercise-02-essential-navigation-commands)
- [Exercise 02 Essential Navigation Commands - Walkthrough](#exercise-02-essential-navigation-commands---walkthrough)
- [Deleting Text and "Thinking in Vim"](#deleting-text-and-thinking-in-vim)
- [Exercise 03 - Deleting Text](#exercise-03---deleting-text)
- [Exercise 03 - Deleting Text - Walkthrough](#exercise-03---deleting-text---walkthrough)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Essential Navigation Commands

<https://superuser.com/questions/599150/why-arrow-keys-are-not-recommended-in-vim>

Using the arrow keys is considered a bad habit, because if you're using the arrow keys you're probably missing out on many of vim's lovely features.

When people first start to use vim, they tend to stay in insert mode since this is more like conventional text editing.
To be effective in vim however, you should only be in insert mode when you're actually entering text.
If you want to move the cursor around, you should be in normal mode.
You should pretty much be in normal mode by default.

In normal mode there are a million shortcuts for moving around. You can use hjkl to move around one space at a time, or you can move by words, paragraphs and so on. If you're in normal mode, there's no point in using the arrow keys instead of hjkl since they're further away.

There's the attitude that if you're using the arrow keys, you're using vim "wrong". The truth is that vim has a really really steep learning curve, so while you're learning do whatever keeps you sane. When I first started using vim I did everything the "wrong" way and I didn't have any problems breaking the habits once I learned more of vim's commands.

As an example, when I first started, say I wanted to change the text in quotes:

String mystring = "I want to change this";

I would go into insert mode, move to the end of the string using the arrow keys, press backspace until the string was gone, and enter the new text.

A much better way is to put your cursor anywhere in the string (normal mode), then press ci". This will change in ". It will delete everything between the quotes and put you into insert mode so that I can enter the new text.

## Exercise 02 Essential Navigation Commands

## Exercise 02 Essential Navigation Commands - Walkthrough

## Deleting Text and "Thinking in Vim"

## Exercise 03 - Deleting Text

## Exercise 03 - Deleting Text - Walkthrough
