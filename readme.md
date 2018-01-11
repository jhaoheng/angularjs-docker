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
3. angular 預設 port 為 4200, 啟動 `docker-compose up` 後約 44 秒 log
```
Recreating App ... done
Attaching to App
App          | Thu Jan 11 01:14:03 UTC 2018 // <======= start
App          | ** NG Live Development Server is listening on 0.0.0.0:4200, open your browser on http://localhost:4200/ **
App          | Date: 2018-01-11T01:14:47.635Z
App          | Hash: dba89ff94ec4df4c657f
App          | Time: 18026ms
App          | chunk {inline} inline.bundle.js (inline) 5.79 kB [entry] [rendered]
App          | chunk {main} main.bundle.js (main) 19 kB [initial] [rendered]
App          | chunk {polyfills} polyfills.bundle.js (polyfills) 547 kB [initial] [rendered]
App          | chunk {styles} styles.bundle.js (styles) 33.5 kB [initial] [rendered]
App          | chunk {vendor} vendor.bundle.js (vendor) 7.4 MB [initial] [rendered]
App          | 
App          | webpack: Compiled successfully.
```