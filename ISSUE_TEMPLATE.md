### Expected behaviour

What should happen?


### Actual behaviour

What happens instead?


### Steps to reproduce

1. 
2. 
3. 


### Logs

Debug output is essential to identify the problem. You can enable debugging by
editing the file `opensc.conf`:
```
    # A debug level of 3 catches most problems
    # Some sensitive data may be logged, too, (e.g. PIN codes)
    debug = 3;

    # Where to write the debug output (default: `stdout`)
    #debug_file = opensc-debug.log
```

Please use Gist (https://gist.github.com/) or a similar code paster for longer
logs. Before pasting here, remove your sensitive data from your log (e.g. PIN
code or certificates).

```
Paste Log output with less than 10 lines here
```
