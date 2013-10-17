getch.h
=======

getch() implementation

## install

```c
$ clib install jwerle/getch.h
```

## usage

```c
int c;
while ((c = getch()) != EOF) {
  printf("c = %c\n", c);
}
```

## license

MIT
