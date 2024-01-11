# advanced-git-commands
Advanced git commands

# Command to find number of lines added and removed in git repo (using q command - https://github.com/harelba/q?tab=readme-ov-file)

git log --author="schegde" --format=tformat: --numstat | q -t "select sum(c1), sum(c2) from -"
