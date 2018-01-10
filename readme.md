# install troubleshooting

## Error while installing

- 若用 `npm install -g @angular/cli`，會產生安裝時的無窮迴圈
    - 故使用 `npm install -g --unsafe-perm @angular/cli`
    - https://github.com/angular/angular-cli/issues/6800