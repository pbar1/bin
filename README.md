# `bin`

My local bin directory of small, self-contained programs.

## Usage

Clone this repository and put it on your `PATH`. This snippet will clone this
repo into your current working directory and add it to your `PATH` for the
duration of your shell session:

```sh
git clone https://github.com/pbar1/bin.git pbbin
export PATH="$PWD/pbbin:$PATH"
```

> [!TIP]
> To persist the `PATH` change, don't forget to add it to your `bashrc`/`zshrc`/etc.

## Programs

### `rn`

Rename files with `sd`.

Dependencies:

- `python3`
- `sd`

### `rp`

Recursive find/replace with `rg` + `sd`.

Dependencies:

- `python3`
- `rg`
- `sd`
