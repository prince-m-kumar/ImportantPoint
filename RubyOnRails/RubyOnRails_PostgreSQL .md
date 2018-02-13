
## Installation process for Ruby on Rails with PostgreSQL on Ubuntu 16.04 in local
#### Prerequisites
We are using `rbenv` for installation of Ruby on Rails.
1. update the local package cache <br>
  `$ sudo apt-get update `

2. Install dependencies required for rbenv and Ruby <br>
  `$ sudo apt-get install autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm3 libgdbm-dev `

#### Install rbenv
1. Clone the rbenv repository from git in home directory. <br>
`git clone https://github.com/rbenv/rbenv.git ~/.rbenv`

2. For command line utility we have to add bin in `$PATH` <br>
  `$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc` <br>
  `$ echo 'eval "$(rbenv init -)"' >> ~/.bashrc `
