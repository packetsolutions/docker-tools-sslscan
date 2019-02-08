Docker package of the sslcan binary

Bind to a bash alias:
```
alias sslscan='docker run --rm packetsolutions/sslscan'
```

To Run
```
sslscan www.google.com
```


Or Build manually using the command:

```
docker build -t sslscan .
alias sslscan='docker run --rm -it sslscan'
```
