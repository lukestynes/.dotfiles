# My .dotfiles

This contains all of the configuration and dotfiles that I use on my Macbook.

This all works with the magic of GNU stow, which creates symlinks from this `.dotfiles` directory to the corresponding locations in the `$HOME` directory.

That way all the files exist in the git repo on your local machine, and can be edited and correctly managed from either location.

Credit to [Dreams of Autonomy](https://github.com/dreamsofautonomy) for [this video](https://www.youtube.com/watch?v=y6XCebnB9gs) and the idea.

## Requirements

For this to work, ensure that you have the following installed.

### Git

```
brew install git
```

### Stow


```
brew install stow 
```

## Installation

Checkout this .dotfiles repo to your `$HOME` directory with git

```
$ git clone https://github.com/lukestynes/.dotfiles.git
$ cd .dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
