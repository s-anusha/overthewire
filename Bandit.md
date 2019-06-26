- ssh un@bandit.labs.overthewire.org -p 2220

#### Level 0:
- un: bandit0 
- pw: bandit0
+ cat readme

#### Level 1:
- un: bandit1
- pw: boJ9jbbUNNfktd78OOpsqOltutMc3MY1
+ cat ./-

#### Level 2:
- un: bandit2
- pw: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
+ cat "spaces in this filename"

#### Level 3:
- un: bandit3
- pw: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
+ cd inhere
+ ls -a
+ cat .hidden

#### Level 4:
- un: bandit4
- pw: pIwrPrtPN36QITSp3EQaw936yaFoFgAB
+ cd inhere
+ find ./ -type f | xargs file | grep text
+ cat ./-file07

#### Level 5:
- un: bandit5
- pw: koReBOKuIDDepwhWk7jZC0RTdopnAYKh
+ cd inhere
+ find ./ \! -perm /111 -size 1033c -type f | xargs file | grep text
+ cat ./maybehere07/.file2

#### Level 6:
- un: bandit6
- pw: DXjZPULLxYr17uwoI01bNLQbtFemEgo7
