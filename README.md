# dsd
Domain Status Detector by check nameserver(NS)

## Usage

```shell
λ eagle [~] → go get -u github.com/eaglewu/dsd

λ eagle [~] → dsd -h
Usage of dsd:
  -a	only print available domains
  -c int
    	concurrent numbers (default 5)
  -d	debug
  -e string
    	domain extensions, eg: .com .io .net (default ".com .cn .net")
  -s duration
    	sleep seconds (default 1s)
  -t duration
    	timeout (default 3s)
  -w string
    	Words eg: apple mac (split with single space)
     
```

EG
```shell
λ eagle [~] → dsd -t 10s -e ".io .co .com" -c 2 -s 5s -w "apple4 apple5 apple6"
```

