# fwcheck

Thin wrapper around ssh and netcat to check network connectivity.


## Examples
```bash
$ fwcheck localhost:81
Connection from localhost to localhost:81 OK! (closed port)


$ fwcheck 10.219.27.1 example.com:80
Connection from 10.219.27.1 to example.com:80 OK! (open port)


$ ./fwcheck 10.219.27.1 example.com:81
Connection from 10.219.27.1 to example.com:81 FAILED!
```
