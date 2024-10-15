sq(squirrel): command-line snippet manager
==========================================

sq(squirrel) is a command-line snippet manager based on Just(command runner).

- Bash version: argc(Bash framework)
- Rust version: native bin without bash and argc required

# Features

# Commands

- list: list snippet - `sq list`
- add: add new snippet - `sq add` or `sq add`
- edit: edit snippet - `sq edit snippet_name`

# Bash Edition

### Get started

* Please install [Just](https://github.com/casey/just#packages) and [argc](https://github.com/sigoden/argc#install)
  first.
* Clone the repository to `$HOME/sq`: `git clone git@github.com:linux-china/sq.git $HOME/sq`
* Add the `sq` directory to your PATH: `export PATH=$PATH:/path/to/sq`
* Run `sq list` to see the available snippets

### Rust edition

- Install: `cargo binstall sq-cli`

# Why sq(squirrel)?

- Simple: sq is written by Bash and argc, easy to understand and modify
- Just: professional command runner with lots of features, good to save and run commands
- UX: `snippet.just` is normal justfile, and easy to edit with your favorite editor

# Pueue & sq

If you want to run cron job, and you can use [pueue](https://github.com/Nukesor/pueue) with sq.
Instead of sending command line to pueue, you can use sq:

- Flexible to change script after added to pueue
- Easy to manage script with sq, no shell escaping, no worry about long command line.

# References

* [argc](https://github.com/sigoden/argc): a Bash CLI framework
* [just](https://github.com/casey/just): a command runner
* [pet](https://github.com/knqyf263/pet): Simple command-line snippet manager
* Just VSCode plugin: https://marketplace.visualstudio.com/items?itemName=skellock.just
* Just JetBrains plugin: https://github.com/linux-china/jetbrains-just-plugin
* Justfile cheat sheet: https://cheatography.com/linux-china/cheat-sheets/justfile/
* pueue: https://github.com/Nukesor/pueue
