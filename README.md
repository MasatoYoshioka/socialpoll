O'REILLY 

Go言語によるWebアプリケーション開発

Chapter 5 socialpoll


```
$mongo
>use ballots
>db.polls.insert({"title" : "今の気分は?", "options" : [ "happy", "sad", "fail", "win" ]})
```

```
$nsqlookupd
```

```
$nsqd --lookupd-tcp-address=127.0.0.1:4160
```

```
$mongod --dbpath ./db
```

```
$./counter/counter
```

```
$./twittervotes/twittervotes
```
