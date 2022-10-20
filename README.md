# TCP over SOCKS5

[![Build](https://img.shields.io/github/workflow/status/appuio/tcp-over-socks/Test)][build]
![Go version](https://img.shields.io/github/go-mod/go-version/appuio/tcp-over-socks)
[![Version](https://img.shields.io/github/v/release/appuio/tcp-over-socks)][releases]
[![GitHub downloads](https://img.shields.io/github/downloads/appuio/tcp-over-socks/total)][releases]

[build]: https://github.com/appuio/tcp-over-socks/actions?query=workflow%3ATest
[releases]: https://github.com/appuio/tcp-over-socks/releases

```
NAME:
   tcp-over-socks - Connect TCP over SOCKS5

USAGE:
   tcp-over-socks [global options] command [command options] [arguments...]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --port value, -p value    local listen port (default: 12345)
   --socks5 value, -x value  socks5 server (default: "127.0.0.1:1080")
   --target value, -t value  target address including port
   --help, -h                show help (default: false)
```

## Running in Kubernetes / OpenShift

See files in `examples/`.

## Credits

Original work done by @isayme in https://github.com/isayme/go-tcp-over-socks5.
Thank you very much for the inspiration!