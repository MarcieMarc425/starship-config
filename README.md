# Terminal configs

## Screenshot
<img width="746" alt="Screen Shot 2022-03-18 at 12 15 59 PM" src="https://user-images.githubusercontent.com/32941251/158936466-5b7076a7-8461-418c-8815-dbed5be00108.png">

## Oh-my-zsh

```sh
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Starship

```sh
brew install starship
```

## Neofetch

```sh
brew install neofetch
```

## Nerd Fonts
Install [Nerd Fonts](https://www.nerdfonts.com/font-downloads) (i.e. Fira Code)

## zsh-autosuggestions
1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

    ```sh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

    ```zsh
    plugins=( [plugins...] zsh-autosuggestions)
    ```

3. Start a new terminal session.

### zsh-syntax-highlighting
1. Clone this repository in oh-my-zsh's plugins directory:

    ```zsh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```

2. Activate the plugin in `~/.zshrc`:

    ```zsh
    plugins=( [plugins...] zsh-syntax-highlighting)
    ```

3. Restart zsh (such as by opening a new instance of your terminal emulator).

### zsh-z
1. Clone this repository in oh-my-zsh's plugins directory:

    ```zsh
    git clone https://github.com/agkozak/zsh-z ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-z
    ```

2. Activate the plugin in `~/.zshrc`:

    ```zsh
    plugins=( [plugins...] zsh-z)
    ```

3. Restart zsh (such as by opening a new instance of your terminal emulator).
