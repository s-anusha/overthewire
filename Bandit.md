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
+ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
+ cat /var/lib/dpkg/info/bandit7.password

#### Level 7:
- un: bandit7
- pw: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
+ ls
+ grep "millionth" data.txt

#### Level 8:
- un: bandit8
- pw: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
+ ls
+ sort data.txt | uniq -u

#### Level 9:
- un: bandit9
- pw: UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
+ ls
+ strings data.txt | grep '^='

#### Level 10:
- un: bandit10
- pw: truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
+ base64 -d data.txt

#### Level 11:
- un: bandit11
- pw: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR
+ cat data.txt | tr ‘n-za-mN-ZA-M’ ‘a-zA-Z’

#### Level 12:
- un: bandit12
- pw: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
+ file data.txt
+ mkdir /tmp/qwerty098
+ cd /tmp/qwerty098
+ xxd -r ~/data.txt > datanew.txt
+ file datanew.txt
+ zcat datanew.txt > datanew2
+ file datanew2
+ bzip2 -d datanew2
+ file datanew2.out
+ zcat datanew2.out > datanew3
+ file datanew3
+ tar -xvf datanew3
+ file data5.bin
+ tar -xvf data5.bin
+ file data6.bin
+ bzip2 -d data6.bin
+ file data6.bin.out
+ tar -xvf data6.bin.out
+ file data8.bin
+ zcat data8.bin > datanew4
+ file datanew4
+ cat datanew4

#### Level 13:
- un: bandit13
- pw: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
