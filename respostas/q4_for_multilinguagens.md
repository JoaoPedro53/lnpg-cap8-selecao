C

int i, j, n = 100;
int sum = 0;

for (i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

----------------------

C++

int i, j, n = 100;
int sum = 0;

for (i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

-----------------------

Javascript

let i, j, n = 100;
let sum = 0;

for (i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

------------------------

Go

package main

func main() {
    n := 100
    sum := 0

    for i, j := 0, 17; i < n; i, j = i+1, j-1 {
        sum += i*j + 3
    }
}

------------------------

Kotlin

var i = 0
var j = 17
val n = 100
var sum = 0

for (; i < n; i++, j--) {
    sum += i * j + 3
}