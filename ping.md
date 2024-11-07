# Ping Command
> The ping command is a simple way to check whether a server is up and running. It sends a small packet of data to the server and waits for a response. If the server is up, it will respond with the time it took to receive the packet. If the server is down, it will not respond at all.

## -c, --count
- Stop after sending count ECHO_REQUEST packets.
- Read more
```bash
ping -c 5 example.com
```

## -i, --interval
- Wait interval seconds between sending each packet.
- Read more
```bash
ping -i 2 example.com
```

## -s, --size
- Specify the number of data bytes to be sent.
- Read more
```bash
ping -s 100 example.com
```

## -t, --ttl
- Set the IP Time to Live.

```bash
ping -t 64 example.com
```

## -W, --timeout
- Time to wait for a response, in seconds.
- Read more
```bash
ping -W 2 example.com
```

## -v, --verbose
- Verbose output.
- Read more
```bash
ping -v example.com
```

## -4
- Use IPv4 only.
- Read more
```bash
ping -4 example.com
```

## -6
- Use IPv6 only.
- Read more
```bash
ping -6 example.com
```

## -A, --adaptive
- Adapt the wait interval between two successive packets.
- Read more
```bash
ping -A example.com
```

## -B, --bind
- Bind to a source address.
- Read more
```bash
ping -B
```