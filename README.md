# Minishell
A partial reimplementation of bash from scratch created at 42 Heilbronn

## Features
- Command history
- Pipes
- File redirections and heredoc
- Environment variables
- Access to executables in path (`ls`, `cat`, `grep`, ...)
- Complex string handling
- Keyboard interupts (Ctrl-D, Ctrl-C, Ctrl-\\)
- Shell nesting
- Builtin commands
  - echo
  - export
  - unset
  - exit
  - cd
  - env
  - pwd

## Dependencies
- gcc
- GNU Make
- readline
## How to run this
```bash
# Clone the repo
git clone https://github.com/dkaisr/minishell.git
cd minishell
make
./minishell
```
