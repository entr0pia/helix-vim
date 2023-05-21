# Helix-Vim

A Vim-like configuration for Helix, forked from [LGUG2Z](https://github.com/LGUG2Z/helix-vim).

## Different from the origin

1. Enable the relative line number
2. `dd`, `yy` support multi-line operation, [refer](https://github.com/LGUG2Z/helix-vim/issues/13)
3. Remove `O`, `o` customized

## Usage

1. Enter the path of the `config`
    - Windows: `~\AppData\Roaming`, `%AppData%` (Explorer and CMD), `$env:APPDATA` (PowerShell)
    - Linux and Mac: `~/.config`
2. Backup and remove the `hexlix` directory, if it exists
3. Clone this Repo to `hexlix`:
    ```
    git clone https://github.com/entr0pia/helix-vim.git hexlix
    ```

**OR**

> Check out the `config.toml` file in this repository. It only
contains key mappings. These were the most important key mappings to allow me
to use as much of my Vim muscle-memory as possible when editing text in Helix.  
> If you are used to doing `c` commands a lot, you're going to have to adapt
to selecting the area you want with `v` and then deleting it.  
> With this being said, a lot of the most basic stuff (including `C`, `0`, `$`,
`^`, `G`, `{}` and `%`!) that you rely on every day to edit and navigate a text
file without thinking about it, is implemented.  
> Feel free to fork this, personalize it, make suggestions, improvements, fill in
gaps that I don't know how to fill, etc.
