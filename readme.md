InteFuzz is the first framework that synergically integrates multiple fuzzing optimizations to maximize performance gains. Intefuzz is an extension of AFL which is written and maintained by Michal Zalewski <[lcamtuf@google.com](mailto:lcamtuf@google.com)>, so its basic usage is like AFL, which can be found in <http://lcamtuf.coredump.cx/afl/>.

InteFuzz employs branch based seed selection by default, add -v option to use block based seed selection; Similarly, InteFuzz uses branch based seed mutation by default, add -z option to use branch based seed mutation; The selection has a higher priority than mutation by default. To prior the mutation step, please use the -u option.

