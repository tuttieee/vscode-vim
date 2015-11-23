vim style key-binding for VSCode

## Require

* VSCode 0.10.1
* typescrpt ```npm install -g typescript```

## install

### windows

```
git clone https://github.com/74th/vscode-vim.git %USERPROFILE%\.vscode\extensions\vscode-vim
cd %USERPROFILE%\.vscode\extensions\vscode-vim
tsc
```
### Mac,Linux

```
git clone https://github.com/74th/vscode-vim.git $HOME/.vscode/extensions/vscode-vim
cd $HOME/.vscode/extensions/vscode-vim
tsc
``` 

## support

* h j k l 0 $ w b tx fx Tx Fx
* i a s o x I A S O X
* d y c dd yy cc Ndd Nyy Ncc D C p P

## never support

* : (you should get use to command palette)
* / ? (you shoud use default search function)
* Ctrl-x Cmd-x Alt-x Meta-x

## future suppprt

* g G
* ; ,
* J
* "xd "xy "xc "xp
* ~
* > <
* % [ ]
* + -
* ...

## low priority

* .
* =
* *
* m `
* q @
* v
* ...

## JISキーボードユーザへ

VSCodeのキーバインドの不具合が見つかっています。tX、fXのアクションや、Insertモード中に入力できない文字があります。
その場合、Ctrl-Spaceのサジェスチョン表示し、その時に入力してください。サジェスチョン表示中はVimStyleでは制御しないようにしています。