# Tcpdump Commands
> tcpdump is a command-line packet analyzer. It allows the user to display TCP/IP and other packets being transmitted or received over a network to which the computer is attached.

## -A, --print
- Print each packet (minus its link level header) in ASCII. Handy for capturing web pages.

```bash
tcpdump -A
```

## -c, --count
- Exit after receiving count packets.

```bash
tcpdump -c 5
```

## -D, --list-interfaces
- Print the list of the network interfaces available on the system.

```bash
tcpdump -D
```

## -i, --interface
- Listen on interface.

```bash
tcpdump -i eth0
```

## -n, --numeric
- Don't convert addresses (i.e., host addresses, port numbers, etc.) to names.

```bash
tcpdump -n
```

## -nn
- Don't convert protocol and port numbers etc. to names either.

```bash
tcpdump -nn
```

## -r, --read
- Read packets from file (which was created with the -w option).

```bash
tcpdump -r file.pcap
```

## -s, --snaplen
- Snarf snaplen bytes of data from each packet rather than the default of 65535 bytes.

```bash
tcpdump -s 1500
```

## -S
- Print absolute sequence numbers.

```bash
tcpdump -S
```

## -v, --verbose
- Print more detailed output.

```bash
tcpdump -v
```

## -vv
- Print even more detailed output.

```bash
tcpdump -vv
```

## -h --help
- Display help information.

```bash
tcpdump -h
```
