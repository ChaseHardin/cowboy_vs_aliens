# Cowboy vs. Aliens
*This game was originally developed while attending Simpson College. This is a rewrite while performing TDD.*

# Run Unit Tests
- At the root directory, run the `./run_all_unit_tests.sh` file.


# Setup Development Environment
It is recommended to setup a virtual Python environment using Pyenv. This prevents your development environments from colliding when working with multiple Python versions.

- Follow [docs](https://github.com/pyenv/pyenv) to install Pyenv.
- Ensure the following commands were run:
```
brew install pyenv
brew install pyenv-virtualenv
```

## Steps to Configure
* Install Python on Pyenv by running `pyenv install 3.6.1`
* Create environment by running: `pyenv virtualenv 3.6.1 cowboy_vs_aliens_env`. This command format is `pyenv virtualenv <python_version> <environment_name>`
* To activate environment do one of the following:
    * Within the directory, type `pyenv activate cowboy_vs_aliens_env`
    * Create a file name `.python-version` with the environment name, `cowboy_vs_aliens_env` inside. This will activate whenever the directory is opened. 
* Ensure that either your `.bash_profile` or `.zshrc` (if using ZShell) contains this content:
```
eval "$(pyenv init -)"
```
This command will ensure that your Python version changes when activating.
