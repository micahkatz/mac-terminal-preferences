# mac-terminal-preferences
My guide to setting up your terminal on Mac to look as good as ever. Includes autocomplete, syntax highlighting, and getting rid of as much white text as possible😎

Here are some steps to improve your terminal on **Mac OSX**. Of course all of these steps are optional

### I. Example

This is what my terminal looks like after adding everything

![alt text](https://raw.githubusercontent.com/micahkatz/mac-terminal-preferences/main/assets/terminalZshIntro.gif)

### II. Configure zsh

- this tutorial requires `zsh` which is different from `bash`. Let's set that up

  ```
  # change your shell to be zsh instead of bash. Optional if you already have bash
  chsh -s /bin/zsh
  ```

- If you are moving from bash, it is important to know that `.bash_profile` is now `.zshenv` and you must define your variables there

- restart your terminal for everything to reset

### III. Install oh-my-zsh

- oh-my-zsh is a great framework for managing your zsh configuration. It contains may plugins and themes. The instructions for install are there https://ohmyz.sh/

  ```
  # this will install oh-my-zsh
  sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```

- restart your terminal for everything to reset



- colored-man-pages
- zsh-autosuggestions
- zsh-syntax-highlighting
- set your `.vimrc` to have `vi syntax on` (can copy the provided `.vimrc` file)

