# Development tools on docker
Flow to manage development tools on your computer with Docker

### Steps to install
- Install git and make
- Install docker and docker compose
- Use following instruction to install dtod
  ```bash
  git clone git@github.com:rasodu/dtod.git ~/.dtod
  cd ~/.dtod
  cp .env.example .env
  ln -s ~/.dtod/bin/dtod ~/.dotfiles/bin_local/dtod
  ```
- Start containers
  ```bash
  dtod start
  ```