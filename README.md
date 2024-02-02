# C Practice


## alias command
```
## c compile and run

function runc () {
  gcc -O $1; ./a.out
}
alias -s c=runc

alias c='(){ gcc -o $1 $1.c && ./$1}'
```
