```
    _                      _                 ____ _     ___
   / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
  / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
 / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
/_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
               |___/

Angular CLI: 1.6.3
Node: 8.9.4
OS: linux x64
Angular: 
...
```

# install troubleshooting

## Error while installing

- 若用 `npm install -g @angular/cli`，會產生安裝時的無窮迴圈
    - 故使用 `npm install -g --unsafe-perm @angular/cli`
    - https://github.com/angular/angular-cli/issues/6800
    
# how to use
1. 在 osx 上，用 `ng new {project}`，建立一個新專案
2. 將 docker-compose.yml 中的 yourApp 變更為專案名稱
