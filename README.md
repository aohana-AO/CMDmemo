# cmdmemo(コマンドプロンプト風メモ帳)

![スクリーンショット 2022-06-24 173016](https://user-images.githubusercontent.com/84378453/175496517-84717546-d601-4176-80ae-c137d4b3231f.png)

## Overview
- python tkinterを使用し、コマンドプロンプトみたいな見た目のメモ帳を作製。
- pyinstallerによりexe化。

## Requirement
- Windows10
- Python3.9
- tkinter
- pyinstaller

## Description
- ScrolledTextをbg="black",bd=10,blockcursor=True,insertbackground='gray',cursor='trek',fg='white',insertwidth=1,などにすることで背景黒・文字白のコマンドプロンプト基調を再現。
- 入力後上書き、開く、保存などの基本的なメモ帳機能を実装。


https://user-images.githubusercontent.com/84378453/175499403-ef40e60d-5f84-423a-9d01-06471fe17f9d.mp4



## Reference
- exe化について<br><a href="https://www.python.ambitious-engineer.com/archives/3306">https://www.python.ambitious-engineer.com/archives/3306</a>
- tkinterの関数や構成要素について
<br><a href="https://kuroro.blog/python/3IA9Mk6O9oBAniXsvSWU/">https://kuroro.blog/python/3IA9Mk6O9oBAniXsvSWU/</a>
