# Jekyll Site Manager

A simple bash script to perform the following functions:

## Installation

1. Copy the file into a `bin` folder in your home directory, and add it to the path.
2. Change permissions with this command:
	`sudo chmod +x site`
3. Restart terminal session and type `site` to see the options.

## Usage

Navigate to the Jekyll project directory and use the script in the following format: `site <command>`

The commands for use are:
- `build` the site
- `push` to git
- `demo` locally
- `open` source folder in editor of choice
- `files` opens the site folder in a file manager
- `meta` opens the script
- `publish` uses [surge](https://surge.sh) to deploy the static site. You can replace this part as per your needs.

## Notes

Feel free to edit and customise this script. I use a modified version of this script for my personal blogs and websites.

This version uses the following programs:
- [Sublime Text](https://www.sublimetext.com/3) (editor of choice) due to its speed in opening large number of files quickly.
- [Surge.sh](https://surge.sh) , my favourite static site hosting service.