# ポリスノーツをdosbox-xで動かす方法
## 準備物
* ユーザーディスクをFDIイメージにしたもの
* CDROMをcue/binにしたもの
* DosBox-X（2023.05.01版を利用した. PC98モードにしておくこと）　

## 手順
* ユーザディスクをマウント  
`imgmount a /Users/naohirofujie/Games/PNAUTS/USER.FDI`

* CDROMをマウント  
`imgmount q /Users/naohirofujie/Games/PNAUTS/P_NAUTS.cue`

* 起動(`boot -l a` ではなくautoexecを使う)  
`a:`  
`a:> autoexec.bat`
