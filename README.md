# Import Facade - A SublimePHPCompanion extension
A simple extension of the find_use command found in SublimePHPCompanion package.

## Purpose
Coworkers of mine loved to use the find_use commnand provided by PHP Companion but
wish they could more easily use it with Laravel's Automatic facades functionality.

This package provides a single command which appends 'Facades\' to the use statement
that is added by the PHPCompanion find_use command.

## Usage
Simply create a keybinding that runs the 'import_facade' command. Here's an example.
{ “keys”: [“f10”], “command”: “import_facade”}

## Installation
This package is not currently on PackageControl, and may never be depending on the level
of support I can provide to it. In order to install this package you will instead need
to place the code within this repository into your Packages folder within your
Sublime Text installation.

A simple way to do this is to simply clone the repo into
the folder. This also enables easy updating with a 'git pull' if ever needed.

### Typical Installation Directories
Mac - /Users/"username"/Library/Application Support/Sublime Text 3/Packages
