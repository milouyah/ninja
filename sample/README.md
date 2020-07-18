# Sample

## run
```
$ ninja
[1/1] gcc -Wall -c foo.c -o foo.o
```
  
The following files are generated.  
* .ninja_deps
* .ninja_log

.ninja_deps
.ninja_log
  

  *** -f FILE  specify input build file [default=build.ninja] ***
  ```
  $ ninja -f another.ninja
  [1/1] gcc -Wall -c foo.c -o foo.o
  ```

## tools
### graph

```
$ ninja -t graph > foo.dot
$ dot -Tjpg foo.dot -o foo.jpg
```


