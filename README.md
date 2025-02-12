# RetKonfirmi
RetKonfirmi (EN: Lit., Web-Confirm) is a ZSH Script that checks for and confirms the status of a website/page on whether it is up or not.

Usage: `website_status_checker.zsh [OPTIONS]`

This script checks the status of a website and prints if it is up or down.

# Options:
```
  --hide_time        Hide the timestamp in the output.
  --monochrome       Disable colored output.
  --interval <sec>   Set the check interval in seconds (default: 15 seconds).
  --log              Enable logging of messages to a log file.
  --logdir <path>    Specify a custom directory for logs (default: $HOME).
  --help             Display this help message and exit.
```

# Example:
```
  ./website_status_checker.zsh --interval 30 --log --logdir /tmp
```
