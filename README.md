# fwcheck

Thin wrapper around ssh and netcat to check network connectivity.


## Examples
```bash
$ fwcheck localhost:81
[OK]     localhost -> localhost:81 OK! (closed port)


$ fwcheck 10.219.27.1 example.com:80
[OK]     10.219.27.1 -> example.com:80 (open port)


$ ./fwcheck 10.219.27.1 example.com:81
[FAILED] 10.219.27.1 -> example.com:81 (timeout)
```
