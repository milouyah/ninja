# [Ninja](https://ninja-build.org/)

## Install
```bash
sudo apt install ninja-build
```

## [manual](https://ninja-build.org/manual.html)

## Writing your own Ninja files
### variables
```
cflags = -g
```

### rule
```
rule keyword
variable=value
```
[The special variables](https://ninja-build.org/manual.html#ref_rule)  

### build
```
build outputs: rulename inputs
```

## More details
### The phony rule
The special rule name phony can be used to create aliases for other targets.  
```
build foo: phony some/file/in/a/faraway/subdir/foo
```

### C/C++ header dependencies
depfile   
deps  

### Pools
  
---
## Ninja file reference

### Evaluation and scoping
```
subninja
```

---

## Tools
### [Graphviz - Graph Visualization Software](https://graphviz.org/)
```
$ sudo apt install graphviz
```
https://iamaman.tistory.com/1685 
```
dot -Tjpg foo.dot -o foo.jpg
```
