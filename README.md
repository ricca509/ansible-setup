# ansible-setup

## How to use

For a brand new install: `./bin/bootstrap`

To re-run only ansible `./bin/run` 

**Note** `bootstrap` and `run` only run the core `osx-core.yaml` playbook.

## Cloning private repositories

SSH keys are stored in 1Password.
In 1Password, go to Preferences -> Developer and check "Use the SSH Agent". The snippet to read SSH keys from 1Password is already in the [.dotfiles](https://github.com/ricca509/.dotfiles/commit/6053163eed3db3a561a70f725d47dffe25d382d1).
