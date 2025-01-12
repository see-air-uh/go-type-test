# Go Type Test

## Purpose

The purpose of this repository is to build out a golang based TUI type test tool. This type test will mostly be geared towards software devs and will include software symbols such as {} - _ += [] () and more!

The secondary audience of the type test tool is users who want to learn to properly touch type, or are learning different keyboard layouts. A goal of this project is to be able to import qmk keymaps with popular keyboars (starting with the lily58!) and allow the user to visualize their keyboard accuracy on their layouts! This view can also help the users find different keys on a new keyboard layout.

### Goals

These are some goals of this repository. They may (most likely will) change through out the development life cycle of the app.

#### 1. Custom definition of tests

The user will be able to define the type of test they want to complete. They can use special symbols from languages, the duration of the test and the type of words in the test

#### 2. A local output file

The tui app should output stats of the user to an output file. This output file should give insights to the user that will show them some of the following (and more to come!)

 - per key accuracy. if the intended character is { and the user commonly mistypes it, it will log this key as an innacurate character and the percent of times they mis type it

 - show the difference between wpm of letters, vs wpm of letters and symbols in a given language (example: how fast someone is in just english letters, vs english letters and go symbols)
 
#### 3. A keymap visualizer

The tui app should be able to load in keymap.c files, read the layout, and display it in the terminal. It should also be able to emulate layers. For example: if you are on the layout page and press the RAISE key, the raise layer should render, and once you release the RAISE key the normal layer should render.


