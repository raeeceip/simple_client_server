# 4at

Simple Multi-User Chat.



## Quick Start

### Server

```console
$ cargo run --bin server
```

Upon running the server creates `./TOKEN` where the Authentication Token is located. You will needed to connect to the Server via the Client.

### Client

```console
$ cargo run --bin client
```

In the prompt of the Client

```console
> /connect <server ip> <token>
```
