# fillit

This is the story of a piece of Tetris, one little square and a dev walk into a bar...

### Contents
* [What is fillit?](#what-is-fillit)
* [Why would I use/try it?](#why-would-i-usetry-it)
* [How do I use it?](#how-do-i-use-it)
* [How do I test my own code?](#how-do-i-test-my-own-code)

### What is fillit?

[fillit][1] is a group project that allows you to discover and / or familiarize yourself with a recurring problem in programming: the search for an optimal solution among a very large number of possibilities, within a reasonable time. In the case of this project, it will be a question of arranging Tetriminos between them and to determine the smallest possible square that can accommodate them. Thanks [@ValeriiaMur][18] for being a great partner!

### Why would I use/try it?

The goal is to understand the concept of recursive backtracking algortihm.

You can use functions from your [personal library][14].

To speed up the program, I used bitwise operators.

### How do I use it?

Download/clone this repo.

	git clone https://github.com/asansyzb/fillit
	cd fillit
	git clone https://github.com/asansyzb/libft
	make

After run `make` in the fillit folder, an executable called `fillit` should compile directly.

The last command created a `fillit` executable in your directory. Now test it with:

I added **samples** folder, to test the program on different amount of different tetriminos.

	./fillit samples/test_8

#### How do I test my own code?
		
1. Go back to the root directory and download @jgigault's 42FileChecker:

		cd ..
		git clone https://github.com/jgigault/42FileChecker
		
2. Go into the test folder and run the test:

		cd 42FileChecker
		sh 42FileChecker.sh

Press `2` to select tests for fillit, press `1` to install [moulitest][5] as an external repo, then `1` to configure the tests, now you handle the path to your fillit and then choose which test to run on your project.

Have fun :)

[1]: https://github.com/asansyzb/fillit/blob/master/fillit.en.pdf
[2]: http://42.us.org "42 USA"
[5]: https://github.com/yyang42/moulitest
[14]: https://github.com/asansyzb/libft
[17]: https://github.com/jgigault/42FileChecker
[18]: https://github.com/ValeriiaMur
