# colorize-term

`simple_colors` is a simple Python library that provides ANSI color codes for formatting terminal text.

## Installation
```bash
pip install colorize-term

Usage:

from colorize-term import Color

# Foreground colors
print(f"{Color.BLACK}Black text{Color.RESET}")
print(f"{Color.RED}Red text{Color.RESET}")
print(f"{Color.GREEN}Green text{Color.RESET}")
print(f"{Color.YELLOW}Yellow text{Color.RESET}")
print(f"{Color.BLUE}Blue text{Color.RESET}")
print(f"{Color.MAGENTA}Magenta text{Color.RESET}")
print(f"{Color.CYAN}Cyan text{Color.RESET}")
print(f"{Color.WHITE}White text{Color.RESET}")

# Background colors
print(f"{Color.BG_BLACK}Black background{Color.RESET}")
print(f"{Color.BG_RED}Red background{Color.RESET}")
print(f"{Color.BG_GREEN}Green background{Color.RESET}")
print(f"{Color.BG_YELLOW}Yellow background{Color.RESET}")
print(f"{Color.BG_BLUE}Blue background{Color.RESET}")
print(f"{Color.BG_MAGENTA}Magenta background{Color.RESET}")
print(f"{Color.BG_CYAN}Cyan background{Color.RESET}")
print(f"{Color.BG_WHITE}White background{Color.RESET}")

# Combined foreground and background colors
print(f"{Color.BG_YELLOW}{Color.BLACK}Black text on yellow background{Color.RESET}")
print(f"{Color.BG_BLUE}{Color.WHITE}White text on blue background{Color.RESET}")
print(f"{Color.BG_MAGENTA}{Color.CYAN}Cyan text on magenta background{Color.RESET}")
print(f"{Color.BG_GREEN}{Color.RED}Red text on green background{Color.RESET}")

