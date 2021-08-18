Unofficial mirror of etherrocks.com (I'm not affiliated at all with the original website).

To run yourself: clone this project and run it.

To create the mirror yourself, I did this:

```
wget --mirror            \
     --convert-links     \
     --html-extension    \
     --wait=2            \
     -o log https://etherrock.com/
```

and then run it using `python -m SimpleHTTPServer 8001` or so
