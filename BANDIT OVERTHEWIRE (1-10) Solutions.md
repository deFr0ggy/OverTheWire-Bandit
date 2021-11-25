# BANDIT OVERTHEWIRE (1-10) Solutions
> Author: Frog Man
> Twitter: https://twitter.com/deFr0ggy
> LinkedIn: https://linkedin.com/in/kamransaifullah

## Level 0
```
Username: bandit0
Password: bandit0
Command: cat
FLAG - boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```

## Level 1
```
Username: bandit1
Password:boJ9jbbUNNfktd78OOpsqOltutMc3MY1
Command: cat < -
Flag: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```

## Level 2
```
Username: bandit2
Password:CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
Command: cat
Flag: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
```

## Level 3
```
Username: bandit3
Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
Command: ls -la, cat
Flag: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
```

## Level 4
```
Username: bandit4
Password: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
Command: for i in {0..9}; do cat < -file0$i; done OR cat
Flag: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
```

## Level 5
```
Username: bandit5
Password: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
Command:  find -type f -size 1033c, cat
Flag: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
```

## Level 6
```
Username: bandit6
Password: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
Command:  find / -size 33c -user bandit7 -group bandit6 2>/dev/null, cat
Flag: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
```

## Level 7
```
Username: bandit7
Password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
Command:  cat data.txt | grep millionth
Flag: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
```

## Level 8
```
Username: bandit8
Password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV    
Command:  cat data.txt | sort -n | uniq -u
Flag: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
```

## Level 9
```
Username: bandit9
Password: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR    
Command:  strings data.txt | grep "="
Flag: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
```

## Level 10
```
Username: bandit10
Password: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk    
Command:  cat data.txt | base64 -d
Flag: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
```