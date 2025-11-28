# alx-system_engineering-devops# 0x03. Shell, Init Files, Variables and Expansions

This project introduces shell initialization files, variables (local, global, and reserved), expansions, shell arithmetic, and aliases.  
Each script in this directory performs a specific task related to these concepts.

---

## File: `0-alias`

### Description
This script creates a new alias in the current shell session.

### Alias Details
- **Name:** `ls`  
- **Value:** `rm *`  

After the script is sourced, the command `ls` will run `rm *` instead of listing files.

### How It Works
The script contains exactly two lines:
1. `#!/bin/bash`
2. `alias ls='rm *'`

### Usage
Load the alias into the current shell:


## File: `1-hello_you`

### Description
This script prints a greeting message to the current Linux user.  
It uses the environment variable `USER`, which stores the username of the person currently logged in.
