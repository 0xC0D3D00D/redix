Redix
======
> a very fast persistent pure key - value store, that uses the same [RESP](https://redis.io/topics/protocol) protocol

Supported Commands
===================
- `PING`
- `SET <key> <value> [<TTL "millisecond">]`
- `GET <key> [<default value>]`
- `MGET <key1> [<key2> ...]`
- `DEL <key1> [<key2> ...]`
- `SCAN [cursor|offset|prefix|key] [keys "keys only?"] [limit "size of result"]`
- `MSET <key1> <value1> [<key2> <value2> ...]`
- `APPEND <key> <value> [<TTL>]`, like `SADD`
- `HSET <HASHMAP> <KEY> <VALUE> <TTL>`
- `HGET <HASHMAP> <KEY>`
- `HDEL <HASHMAP> <key1> [<key2> ...]`
- `HGETALL <HASHMAP>`

Install
=======
- from source: `go get github.com/alash3al/redix`
- from binaries: go [there](https://github.com/alash3al/redix/releases) and choose your platform based binary

Client SDKs
===========

Why
===
> I built this software to lear more about data modeling, data structrues and how to map any data to pure key value.

WHO AM I
========
> I'm Mohamed Al Ashaal, a software engineer, team leader