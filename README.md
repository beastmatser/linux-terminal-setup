# Dotfiles

My personal dotfiles, managed using stow.

```sh
git clone http://github.com/beastmatser/dotfiles && cd dotfiles

# .gitignore does not work with stow, so we'll symlink it manually
ln -s ~/dotfiles/git/.gitignore ~/.gitignore
```

Install programs using this gist:
https://gist.github.com/beastmatser/f191cb82e9830d9a87d0fb8ba12a2ca9
