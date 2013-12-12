# lchamb's dotfiles

## dotfiles

These are my dotfiles. They are based on a fork of Zach Holman's excellect dotfiles project. [You can learn more the project here](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)

## install

You probably don't want to install my dotfiles. They are based on my machines and preferences. A better starting point would be to start with the original project or make your own fork:

```sh
git clone https://github.com/holman/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.

The most important files to change are probably in the `.dotfiles/git` directory. These dotfiles also assume you are using zsh instead of bash and in specific [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh).

## thanks
[Zach Holman](https://github.com/holman) did all the work and I changed a few variables.
