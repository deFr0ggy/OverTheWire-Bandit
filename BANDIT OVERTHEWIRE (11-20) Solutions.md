# BANDIT OVERTHEWIRE (11-20) Solutions
```
Author: Frog Man
Twitter: https://twitter.com/deFr0ggy
LinkedIn: https://linkedin.com/in/kamransaifullah
```

## Level 11
```
Username: bandit11
Password: IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR    
Command: cat data.txt | tr '[A-Za-z]' '[N-ZA-Mn-za-m]'
Flag: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu
```

## Level 12
```
Username: bandit12
Password: 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu    
Command: xxd -r file | Regular unzipping using different utilities.
Flag: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL
```

## Level 13
```
Username: bandit13
Password: 8ZjyCRiBWFYkneahHwxCv3wb2a1ORpYL    
Command: ssh -i sshkey.private bandit14@localhost
Flag: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e
```

## Level 14
```
Username: bandit14
Password: 4wcYUJFw0k0XLShlDzztnTBHiqxU3b3e    
Command: nc localhost 30000
Flag: BfMYroe26WYalil77FoDi9qh59eK5xNr
```

## Level 15
```
Username: bandit15
Password: BfMYroe26WYalil77FoDi9qh59eK5xNr    
Command: echo "BfMYroe26WYalil77FoDi9qh59eK5xNr" | openssl s_client -connect localhost:30001 -ign_eof
Flag: cluFn7wTiGryunymYOu4RcffSxQluehd
```

## Level 16
```
Username: bandit16
Password: cluFn7wTiGryunymYOu4RcffSxQluehd    
Command: NMAP, echo "cluFn7wTiGryunymYOu4RcffSxQluehd" | openssl s_client -connect localhost:31790
Flag: 

      

-----BEGIN RSA PRIVATE KEY-----

MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ

imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ

Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu

DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW

JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX

x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD

KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl

J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd

d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC

YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A

vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama

+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT

8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx

SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd

HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt

SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A

R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi

Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg

R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu

L8ktHMPvodBwNsSBULpG0QKBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni

blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU

YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM

77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b

dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3

vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=

-----END RSA PRIVATE KEY-----
```

## Level 17
```
Username: bandit17
Password: hbandit17.key    
Command: chmod 600 bandit17.key, ssh -i bandit17.key bandit17@localhost
Flag: xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
```

## Level 18
```
Username: bandit18
Password: xLYVMN9WE5zQ5vHacb0sZEVqbrp7nBTn
Command: cat
Flag: kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
```

## Level 19
```
Username: bandit19
Password: kfBf3eYk5BPBRzwjqutbbfE887SVc5Yd
Command: ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme
Flag: IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
```

## Level 20
```
Username: bandit20
Password: IueksS7Ubh8G3DCwVzrTd8rAVOwq3M5x
Command: ./bandit20-do cat /etc/bandit_pass/bandit20
Flag: GbKksEFF4yrVs6il55v6gwY5aVje5f0j
```