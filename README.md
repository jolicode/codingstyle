# JoliCode coding style

This repository host common boilerplate configuration files for our web projects. They are opinionated by nature, and may not be right for you.

## Installation on the host system (one time)

- Install [EditorConfig plugin](http://editorconfig.org/#download) (required for PhpStorm, Atom...);
- Use the `.gitconfig` file as a base for your local git setting (to copy in `~/.gitconfig`).

## Installation on the project (on each project)

- Inside your project, run the following command:
```
wget -qO- https://github.com/jolicode/codingstyle/archive/master.tar.gz | tar xvz --strip-components=1
```
- edit all `appname` in the new files, and make sure to adapt them to your needs.

## Usage

### Fix Coding Standard

```
make cs
```
