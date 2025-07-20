<p align="center">
  <img src="https://raw.githubusercontent.com/remarkablegames/the-question/master/game/gui/window_icon.png" alt="The Question">
</p>

# The Question

![release](https://img.shields.io/github/v/release/remarkablegames/the-question)
[![build](https://github.com/remarkablegames/the-question/actions/workflows/build.yml/badge.svg)](https://github.com/remarkablegames/the-question/actions/workflows/build.yml)
[![lint](https://github.com/remarkablegames/the-question/actions/workflows/lint.yml/badge.svg)](https://github.com/remarkablegames/the-question/actions/workflows/lint.yml)

❓ The Question

Play the game on:

- [remarkablegames](https://remarkablegames.org/the-question)

## Prerequisites

Download [Ren'Py SDK](https://www.renpy.org/latest.html):

```sh
git clone https://github.com/remarkablegames/renpy-sdk.git
```

Symlink `renpy`:

```sh
sudo ln -sf "$(realpath renpy-sdk/renpy.sh)" /usr/local/bin/renpy
```

Check the version:

```sh
renpy --version
```

## Install

Clone the repository to the `Projects Directory`:

```sh
git clone https://github.com/remarkablegames/the-question.git
cd the-question
```

## Run

Launch the project:

```sh
renpy .
```

Or open the `Ren'Py Launcher`:

```sh
renpy
```

Press `Shift`+`R` to reload the game.

Press `Shift`+`D` to open the developer menu.

## Cache

Clear the cache:

```sh
find game -name "*.rpyc" -delete
```

Or open `Ren'Py Launcher` > `Force Recompile`:

```sh
renpy
```

## Lint

Lint the game:

```sh
renpy game lint
```

## License

[MIT](LICENSE)
