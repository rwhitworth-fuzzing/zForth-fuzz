id:000000,sig:08,src:000098,op:flip4,pos:5

```
#0  0x0000000000405c84 in do_prim (op=<optimized out>, input=<optimized out>) at ../zforth/zforth.c:639
#1  run (input=<optimized out>) at ../zforth/zforth.c:465
#2  0x0000000000403404 in execute (addr=74) at ../zforth/zforth.c:497
#3  handle_word (buf=<optimized out>) at ../zforth/zforth.c:757
#4  handle_char (c=<optimized out>) at ../zforth/zforth.c:801
#5  zf_eval (buf=<optimized out>) at ../zforth/zforth.c:884
#6  0x00000000004017a6 in do_eval (src=<optimized out>, line=<optimized out>, buf=<optimized out>) at main.c:30
#7  include (fname=<optimized out>) at main.c:69
#8  0x0000000000402145 in main (argc=<optimized out>, argv=<optimized out>) at main.c:261
```

