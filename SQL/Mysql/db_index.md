#参考
[インデックスの効果を簡単に確認する方法](http://www.happytrap.jp/blogs/2012/04/01/8685/)

#インデックスを作成する

`create index user on twitter_public(user);`

`show index from twitter_public_2;`

`explain select * from twitter_public_2 where user > 1000000000000 order by user;`

`explain select * from twitter_public_2 ignore index(user) where user > 1000000000000 order by user;`
