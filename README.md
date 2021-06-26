jcal - [Forked From ashkang/jcal](https://github.com/ashkang/jcal)
====

C implementation of Jalali calendar is a small and portable free software library to manipulate date and time in Jalali calendar system.
It's written in C and has absolutely zero dependencies. It works on top of any POSIX.1-2001 (and later) compatible
libc implementations. Jalali calendar provides an API similar to that of libc's timezone, date and time functions.

Jalali calendar package consists of a library namely libjalali and two simple and easy to use terminal tools, jcal
and jdate with functionality similar to UNIX cal and date.

## Compile & Run

First navigate to `src` directory,

`cd src`

### To make _jdate_

```
make date
./jdate
```

### To make _jcal_

```
make cal
./jcal
```
