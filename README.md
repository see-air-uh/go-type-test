# Go Type Test

## Purpose

The purpose of this repository is to build out a golang based TUI type test tool. This type test will mostly be geared towards software devs and will include software symbols such as {} - _ += [] () and more!

### Goals

These are some goals of this repository. They may (most likely will) change through out the development life cycle of the app.

#### 1. Custom definition of tests

The user will be able to define the type of test they want to complete. They can use special symbols from languages, the duration of the test and the type of words in the test

#### 2. A local output file

The tui app should output stats of the user to an output file. This output file should give insights to the user that will show them some of the following (and more to come!)

 - per key accuracy. if the intended character is { and the user commonly mistypes it, it will log this key as an innacurate character and the percent of times they mis type it

 - show the difference between wpm of letters, vs wpm of letters and symbols in a given language (example: how fast someone is in just english letters, vs english letters and go symbols)
 



