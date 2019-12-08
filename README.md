# vim-ide-multios

Overview
--------

This ansible ansible 2.9 role installs vim and many usefull plugins and also generates a valid .vimrc

Taken over from https://github.com/c8m6/ansible-role_vim and added support for multiple Linux OS Distributions.

## Loaded Plugins
```
      syntastic
      tabular
      vim-addon-manager-knwon-repositories
      vim-airline
      vim-airline-themes
      vim-fugitive
      vim-puppet
      onedark
      nerdtree
      vim-surround
      vim-gitgutter
      YouCompleteMe
      ultisnips
      vim-snippets
      vim-bufferline
      vim-eunuch
      vim-todo-list
      indentLine
      vim-janitor
      command-t
```
## Vim Shortcuts

<ctrl> T: CommanderT (fuzzysearch)
<ctrl> N: Nerdtree
j / k: comfortable motion

## Use this role standalone (not included as role in an existing playbook)

```
# ansible-playbook -i 'localhost,' --connection=local -K standalone.yml
```

