# JoliCode coding style

This repository host common boilerplate configuration files for our web projects. They are opinionated by nature, and may not be right for you.

## Installation on the host system (one time)

- Install [EditorConfig plugin](http://editorconfig.org/#download) (required for PhpStorm, Atom...);
- Use the `.gitconfig` file as a base for your local git setting (to copy in `~/.gitconfig`).

## Installation on the project (on each project)

- Inside your project, run the following command:
```
wget -qO- -O coding.tmp.zip https://github.com/jolicode/codingstyle/archive/master.zip && unzip -j coding.tmp.zip && rm coding.tmp.zip
```
- edit all `appname` in the new files, and make sure to adapt them to your needs.

## Usage

### Fix Coding Standard

```
make cs
```
