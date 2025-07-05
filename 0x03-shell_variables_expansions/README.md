# 0x03. Shell, init files, variables and expansions

This directory contains scripts that demonstrate basic shell scripting skills focused on:

- Creating and using aliases
- Understanding shell variables
- Expansions (arithmetic, brace, variable, command substitution)
- Initialization files like `.bashrc`
- Managing environment variables

## Task 0 - Alias

**File:** `0-alias`  
Creates an alias `ls` with the value `rm *`. When sourced, the alias replaces the `ls` command with a command that removes all files in the current directory.

```bash
alias ls='rm *'
