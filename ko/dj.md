# Directory Jump (dj)

## 도움말

```bash
dj - Directory Jump

Usage:
    dj                 : 디렉토리 저장소 출력
    dj [index]         : [index] 번호로 디렉토리 이동
    dj add             : 현재 디렉토리를 저장소에 추가
    dj add [dir]       : [dir]를 디렉토리를 저장소에 추가
    dj rm              : 현재 디렉토리를 저장소에서 제거
    dj rm [index]      : [index] 번호의 디렉토리를 저장소에서 제거
    dj save <filename> : 디렉토리 저장소를 <filename>으로 저장
    dj load <filename> : <filename>을 디렉토리 저장소로 불러오기
    dj clean           : 디렉토리 저장소 비우기
    dj help            : 도움말 출력
```

## 사용법

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
