# JobQueue Prototype for Learning

I needed a job queue for a project. While I still plan on either getting one off
the shelf or otherwise doing something smarter. I figured I could prototype one
in an afternoon to see how it might work. This is just that. The code is a bit
messy, the word prototype is used in the title of this readme for a reason, etc.

## Building

My `Makefile` is specifically for `clang` because I was being pretty lazy.
Theoretically any C++11 compiler could compile this, and most of my switches are
just to generate warnings to help me catch errors. If you run `make` after
checking this out on a machine with `clang` installed, it will compile and run.

## License

ISC but really you don't want to use this, probably not even as a reference.
