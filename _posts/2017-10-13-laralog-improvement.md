## Set up synchronization by git  
---

#### check-out git version
>git --version

#### check-out git configuration
>git config --list

#### Set up git synchronization between github,aws and mac
>git remote -v
>git remote add origin https://github.com/Cassini17/laralog.git
>git push --set-upstream origin master

#### synchronize github with aws
>git push

## Set-up Mac 
---
#### Download and install sublime text 3
[sublime website](https://sublimetext.com)
#### Register sublime
—– BEGIN LICENSE —–
TwitterInc
200 User License
EA7E-890007
1D77F72E 390CDD93 4DCBA022 FAF60790
61AA12C0 A37081C5 D0316412 4584D136
94D7F7D4 95BC8C1C 527DA828 560BB037
D1EDDD8C AE7B379F 50C9D69D B35179EF
2FE898C4 8E4277A8 555CE714 E1FB0E43
D5D52613 C3D12E98 BC49967F 7652EED2
9D2D2E61 67610860 6D338B72 5CF95C69
E36B85CC 84991F19 7575D828 470A92AB
—— END LICENSE ——

#### install mysql on mac
>brew install mysql

#### set-up mysql on mac
>brew services start mysql
>mysql_secure_installation
>modify .env

#### restore mysql tables
>php artisan migrate

