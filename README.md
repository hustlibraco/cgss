# cgss
go语言编程第四章演示项目
```Bash
$cd src/cgss
$go run cgss.go
```

  Casual Game Server Solution
  
  A new session has been created successfully.

Commands:
        login   <username><level><exp>
        logout  <username>
        send    <message>
        listplayer
        quit(q)
        help(h)

Command> login libraco1 1 1  

Command> login libraco2 2 2

Command> listplayer

1 : &{libraco1 1 1 0 <nil>}

2 : &{libraco2 2 2 0 <nil>}

Command> send who are you

libraco1 receive message: who are you

libraco2 receive message: who are you

Command> logout libraco1

Command> listplayer              

1 : &{libraco2 2 2 0 <nil>}

Command> logout libraco2   

Command> listplayer

Failed.  No player online.

Command> q
```
