# Linux finger Command
-------------------
### Command Introduction (命令介绍)
> **SYNOPSIS**
### Command Format and Options (命令格式和选项)
```
usage: finger [-lmps] [login ...]
```
### Command Example (命令范例)
```

  finger

  User information lookup program.

  - Display information about currently logged in users:
    finger

  - Display information about a specific user:
    finger username

  - Display the user's login name, real name, terminal name, and other information:
    finger -s

  - Produce multi-line output format displaying same information as -s as well as user's home directory, home phone number, login shell, mail status, etc.:
    finger -l

  - Prevent matching against user's names and only use login names:
    finger -m


```
