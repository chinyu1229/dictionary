# dictionary

## complier

server:
```
gcc dict_server.c -o server -lsqlite3
```

client:
```
gcc dict_client.c -o client -lcrypto
```

envirnoment: Ubuntu 20.04 LTS

install lib:
```
sudo apt install sqlite3
sudo apt-get install openssl
sudo apt-get install libssl-dev
```
Exec:

```
./server <ip> <port>
./client <ip> <port>
```

## description

Use fork() ,make multiple clients.



