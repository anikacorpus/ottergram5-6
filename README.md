CPSC 473 - Web Front-End Engineering for Internet Applications
Assignment 3 - Spring 2017

Section 2 due February 27.  Section 1 due February 22.

In this assignment, you will configure ESLint, work through Chapters 5 and 6 of the textbook, and upload the result to GitHub.

Complete the following:
Work through Chapter 5.  Verify that your code renders the thumbnail list in the correct direction (horizontal or vertical) in and out of device mode.

From the command line, install the ESLint tool with

	npm install -g eslint

then switch to your ottergram/ directory and run

	eslint --init

Answer the config initialization wizard’s questions as follows:
? How would you like to configure ESLint? Answer questions about your style
? Are you using ECMAScript 6 features? No
? Where will your code run? Browser
? Do you use CommonJS? No
? Do you use JSX? No
? What style of indentation do you use? Spaces
? What quotes do you use for strings? Single
? Do you require semicolons? Yes
? What format do you want your config file to be in? JSON

For the question

? What line endings do you use?

	Choose Unix if you are on macOS or Linux.
Work through Chapter 6.  As you make changes to main.js, verify that you see error messages from ESLint.
Confirm that clicking each thumbnail changes the detail image and title to match.
Complete the Silver Challenge: Link Hijack.  Place your code in scripts/hijack.js.
Push the contents of your ottergram directory into a new public GitHub repository.
