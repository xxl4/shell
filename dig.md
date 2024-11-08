# Dig Command
> The dig command is a DNS lookup utility that is used to query DNS servers. It is a useful tool for troubleshooting DNS issues. The dig command can be used to query different types of DNS records, such as A, AAAA, CNAME, MX, NS, PTR, SOA, and TXT records.

## -4, -6
- Use IPv4 or IPv6 only.
- Read more
```bash
dig -4 example.com
```
```bash
dig -6 example.com
```

## +short
- Display only the answer section.
- Read more
```bash
dig +short example.com
```

## +trace
- Trace the delegation path from the root name servers.
- Read more
```bash
dig +trace example.com
```

## +all
- Print all records.
- Read more
```bash
dig +all example.com
```

## +noall
- Print no records.
- Read more
```bash
dig +noall example.com
```

## +answer
- Print answer section only.
- Read more
```bash
dig +answer example.com
```

## +authority
- Print authority section only.
- Read more
```bash
dig +authority example.com
```

## +additional
- Print additional section only.
- Read more
```bash
dig +additional example.com
```

## +comments
- Print comment lines.
- Read more
```bash
dig +comments example.com
```

## +noquestion
- Print no question section.
- Read more
```bash
dig +noquestion example.com
```

## +nostats
- Print no statistics section.
- Read more
```bash
dig +nostats example.com
```

## +qr
- Print query response.
- Read more
```bash
dig +qr example.com
```

## +tcp
- Use TCP for the query.
- Read more
```bash
dig +tcp example.com
```

## +notcp
- Do not use TCP for the query.
- Read more
```bash
dig +notcp example.com
```

## +ignore
- Ignore truncation in UDP responses.
- Read more
```bash
dig +ignore example.com
```

## +noignore
- Do not ignore truncation in UDP responses.
- Read more
```bash
dig +noignore example.com
```

## +fail
- Do not try the next server if the query fails.
- Read more
```bash
dig +fail example.com
```

## +nofail
- Try the next server if the query fails.
- Read more
```bash
dig +nofail example.com
```

## +besteffort
- Try to parse even unknown options.
- Read more
```bash
dig +besteffort example.com
```

## +dnssec
- Request DNSSEC records.
- Read more
```bash
dig +dnssec example.com
```

## +sigchase
- Chase DNSSEC signature chains.
- Read more
```bash
dig +sigchase example.com
```

## +trusted-key
- Specify a trusted key.
- Read more
```bash
dig +trusted-key example.com
```

## +topdown
- Turn on top-down mode.
- Read more
```bash
dig +topdown example.com
```

## +nsid
- Request the NSID.
- Read more
```bash
dig +nsid example.com
```

## +bufsize
- Set the EDNS buffer size.
- Read more
```bash
dig +bufsize=512 example.com
```

## +edns
- Set EDNS version.
- Read more
```bash
dig +edns=1 example.com
```
