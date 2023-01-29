2023/01/29
Windows用 Sysmonインストール

https://learn.microsoft.com/en-us/sysinternals/downloads/

```bat
rem JSAC2023 Workshop2 Sigma 用のLogFile作成ツール Sysmonのインストール手順
rem 
rem 2023/01/29 @HirMtsd

C:\Apps\SysinternalsSuite\Sysmon64.exe -i
```

2023/01/29
EvtxECmd で変換

https://ericzimmerman.github.io/

```bat
rem evtxファイルをcsvファイルに変換
EvtxECmd.exe -f sample.evtx --csv ./
```
