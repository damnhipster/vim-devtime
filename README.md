# ViM

## helping children
## in Uganda


# Why ViM?

http://vim.sexy


## Syntax
## highlighting

```ruby
require 'sinatra/base'
require 'skycom-assets'

module Sinatra
  module Skycom
    def masthead
      SkycomAssets.new("http://assets.sky.com", 300).get_masthead
    end
  end
  helpers Skycom
end
```


## Still, why ViM?
- Easy command line acccess
- GUI-Optional: works on servers
- 100% Hackable
- and...


## Modes

- COMMAND (default)
- INSERT i a o
- VISUAL v



Given the following users exist:

| name   | email           | phone |
| ------ |:---------------:| -----:|
| Aslak  | aslak@email.com | 123   |
| Matt   | matt@email.com  | 234   |
| Joe    | joe@email.org   | 456   |


## Commands

- yank y
- paste p
- undo u
- redo Ctrl-r
- change c
- delete x


## Shift it

- Shift+command will do even more
- yank line Y
- paste before P
- undo line U
- change til the end of line C
- backspace X


## Chaining

- Here we go...
- Yank A Paragraph yap
- Change 2 Words c2w
- Format to bottom =G
- Repeat last action that changed file .


## Motions

- up down left right hjkl
- top gg
- bottom G
- navigate by word w e b
- by paragraph } {
- search /
- go to character f
- go to previous character F
- scroll Ctrl-e Ctrl-y
- scroll cursor to top zt, bottom zb and middle zz of screen
- page up and down Ctrl-f Ctrl-b
- back and forward Ctrl-o Ctrl-i


## Directory

- Browse directory :e .


## Tmate

```bash
brew tap nviennot/tmate
brew install tmate
```

- Pair program remotely with vim with no lag


## Cool stuff

- revert to earlier version :earlier 15m
- save write protected file :w !sudo tee %


## ViM on OSX??

- https://gist.github.com/damnhipster/
- Gist: vim.md


## What else?

- Plugins
- Registers
- Macros
- Buffers
- Configuration


## Vimdeck

Presenting vim in vim


# Thanks!

github.com/damnhipster/vim-devtime
