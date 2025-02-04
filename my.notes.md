# 2025-02-01

Try again using simpler approach

## First time using script on machine
1. Activate desired python environment
   > source ~/Python/user/bin/activate
2. Install tools 
   > python3 -m pip install setuptools
3. Build program and install
   > python3 -m pipx install text2qti

## Above steps complet

> text2qti ...

# 2025-01-22

## Using 'uv'

To install use
> $ uv pip install text2qti
To run use 
> $ uv run text2qti


# 25 Oct 2021

## Grade Posting Policy

- Original code has grades posted automatically
- Changed setting for post_manually from false to true
  Would be nice to include this as an option on a per quiz basis and/or set a value when installing.
  See current options you can change at start of file as a guide.

## Package installation
- I find installing the package confusing.
  It seems like the suggestions given install not from the repo, but from some other respository.
  Because I want to use my modified code... 
  - TO INSTALL USE:  python setup.py install --user
    - This places the executable in ~/.local/bin
