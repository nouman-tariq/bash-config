# bash-config

My personal [Bash](https://www.gnu.org/software/bash/) configuration — a single `.bashrc` with sensible history settings, a tidy prompt, and a few quality-of-life tweaks.

## What's inside

- **Smarter history** — large history (`HISTSIZE=10000`), timestamps (`HISTTIMEFORMAT`), no duplicates (`HISTCONTROL=ignoreboth`), and history **shared live across all open terminals**
- **Coloured prompt & `ls`** — the standard Debian colour prompt plus `ls --color=auto`
- **ssh-agent** — started automatically for each interactive shell
- **nvm** — loads [Node Version Manager](https://github.com/nvm-sh/nvm) if installed
- **Handy bits** — `copy` alias (`xclip` to clipboard), `pass` clipboard timeout, and UTF-8 locale defaults

## Installation

Back up your current config and drop this one in:

```sh
cp ~/.bashrc ~/.bashrc.bak 2>/dev/null
curl -fLo ~/.bashrc https://raw.githubusercontent.com/nouman-tariq/bash-config/master/.bashrc
source ~/.bashrc
```

## License

Free to use and adapt.
