# Chatroom

## Introduction

This is a chatroom written in C, with multi-threaded socket programming.

## How to use

1. Compile "client.c" and "server.c" to executable program
   ```
   gcc -o server server.c
   gcc -o client client.c
   ```
2. Server runs "server"
   ```./server```
3. Distribute "client" to users, and users should run with:
   ```./client```

## Remarks
* Make sure the server and clients should stay under the same network.
* Read 4621 Project Report.pdf to know the demostration.
