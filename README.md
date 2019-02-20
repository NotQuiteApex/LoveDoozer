# LÖVE Doozer
A Continuous Integration script for automatically building your LÖVE projects.

I made this during the LÖVE Jam 2019 so that my team members could test out what I had made without me having to constantly make builds for every change I made.

## How to use
1. Grab the `.doozer.json` from this repo and put it in your own repo.
	1. You can find and replace the word `GAME` with your project name.
1. Go to https://doozer.io/ and add your project.
1. Add the `master` branch (or whatever branch you want to have built every commit) to the tracked branches.
Now everytime you commit and push, Doozer will build your project for Windows x32 and x64 and a `.love` file for MacOS and Linux!

## Contributing
If you wanna see other CI scripts in here, go ahead and make a PR!

## License
Copyright (c) 2019 NotQuiteApex

I don't care what you do with this, just make use of it and give credit if you feel like it.
