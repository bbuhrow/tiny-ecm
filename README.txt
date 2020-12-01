A very fast elliptic curve method (ECM) for factorizing tiny integers (64 bits or less).

A sample build line:
gcc -O2 -march=native -g tinyecm.c -o tecm

The default build will first create a bunch of test files and then
it will factor them, creating benchmarking info.  If you already have
the files you can set 
int generate_test_files = 0;
in the main routine and rebuild.

