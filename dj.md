# Directory Jump (dj)

## Help

```bash
dj - Directory Jump

Usage:
    dj                 : Display directory repository
    dj [index]         : Move to directory at [index] number
    dj add             : Add current directory to repository
    dj add [dir]       : Add [dir] directory to repository
    dj rm              : Remove current directory from repository
    dj rm [index]      : Remove directory at [index] number from repository
    dj save <filename> : Save directory repository as <filename>
    dj load <filename> : Load <filename> as directory repository
    dj clean           : Clear directory repository
    dj help            : Display help
```

## Usage

```bash
/home/username $ dj add
Added directory: /home/username

/home/user $ dj
    1 /etc/caddy
    2 /home/username
    3 /home/username/Desktop
    4 /home/username/Documents
    5 /home/username/Repo
    6 /var/www/html

/home/user $ dj 3
Changing directory to: /home/username/Desktop

/home/username/Desktop $
```
