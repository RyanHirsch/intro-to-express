# Intro to Express

## Build a Manual Webserver

1. Start up a local netcat server via `nc -l 4000`
1. Open another tab and run `nc localhost 4000` to connect to the server
1. Demonstrate the ability to send messages back and forth
1. Stop and re-launch `nc -l 4000`
1. Open Chome and go to `http://localhost:4000`
1. We see the HTTP verb, the resource it is acting upon, and the protocol version
1. In the reply send the following
    ```txt
    HTTP/1.1 200 ok
    Content-Type: text/plain; charset=utf-8
    Content-Length: 4

    hi!
    ```
1. The format we just saw was MIME format HTTP
1. The request consisted of key value pairs
1. `Host` is required and how different servers  can do things like host multiple websites

## History

## Do we need express

## Express Components

### Router and Routes

### Middleware

## In Action

1. Testing
1. Debugging

## Advanced Project

## Excersizes using Express

1. NodeSchool [`expressworks`](https://github.com/azat-co/expressworks)

## References

- [Intro to HTTP with Netcat and Chrome](https://coolaj86.com/articles/intro-to-http-with-netcat-node-connect.html)
- [The Unbelievable History of the Express JavaScript Framework](https://thefullstack.xyz/history-express-javascript-framework/)
- [Introduction to Node & Express](https://medium.com/javascript-scene/introduction-to-node-express-90c431f9e6fd)
- [Building a RESTful API: Node and Express 4](https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4)
