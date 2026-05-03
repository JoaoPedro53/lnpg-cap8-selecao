Java 

int j = -3;

for (int i = 0; i < 3 && j <= 0; i++) {

    int expr = j + 2;

    if (expr == 3 || expr == 2) {
        j--;
    } else if (expr == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}

--------------------

Python 

j = -3
i = 0

while i < 3 and j <= 0:
    expr = j + 2

    if expr == 3 or expr == 2:
        j -= 1
    elif expr == 0:
        j += 2
    else:
        j = 0

    if j <= 0:
        j = 3 - i

    i += 1

---------------------

Javascript

let j = -3;

for (let i = 0; i < 3 && j <= 0; i++) {

    let expr = j + 2;

    if (expr === 3 || expr === 2) {
        j--;
    } else if (expr === 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j <= 0) {
        j = 3 - i;
    }
}