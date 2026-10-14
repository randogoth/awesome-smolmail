# Awesome smolmail [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A collection of awesome things around the [smolmail protocol](https://smol.place) ecosystem.

Please contribute to this list to link to all the awesome smolmail projects out there.

## What is smolmail

[Excerpt from smol.place](https://smol.place):

> A small, decentralised mail system where every message is encrypted end to end. It's simple enough that you can write your own client in an afternoon.
> - One key is your identity. Back up 32 bytes and you've backed up everything.
> - Only the recipient can read your mail. Servers store sealed envelopes they can't open.
>  -No middlemen. Your client delivers straight to the recipient's server.


## smolmail Specification 

- [Official protocol specification](https://smol.place/SPEC)
- [Article about the inception](https://randogoth.com/smolmail.html)

## Clients

### Terminal
- [fumi](https://code.randogoth.com/randogoth/fumi) (Rust) - A stable client for smolmail
- [smolmail](https://code.randogoth.com/randogoth/smolmail) (Python) - The LLM written reference implementation.

### Graphical
#### Cross-platform
- [carrier](https://code.randogoth.com/randogoth/carrier) (Rust) - A simple Adwaita GTK4 desktop client for Smol Mail based on `fumi-core`
- [gsmol](https://code.randogoth.com/randogoth/gsmol) (JS/Python) - Browser based webmail client for smolmail with a Websocket bridge
#### Mobile
- [kirakira](https://code.randogoth.com/randogoth/kirakira) (Flutter/Rust) - Client for Android and Linux desktop based on `fumi-core`

### Servers
- [bunshin](https://code.randogoth.com/randogoth/bunshin) (Rust) - Production ready server with TCP and RNS endpoints

### Services
- [pneumatube](https://code.randogoth.com/randogoth/pneumatube) (Python/Rust) - A gateway bridging a smolmail account and an SMTP mailbox based on `fumi-core`
- [smolboid](https://code.randogoth.com/randogoth/smolboid) (Rust) - Server to publish signed [twtxt](https://twtxt.dev/) over smolmail based on `fumi-core`
