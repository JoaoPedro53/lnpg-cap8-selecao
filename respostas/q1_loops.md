Java

int k = (j + 13) / 27;
int i;

while (k <= 10) {
    k = k + 1;
    i = 3 * k - 1;
}

-----------------

Python 

k = (j + 13) // 27
while k <= 10:
    k = k + 1
    i = 3 * k - 1

------------------

Haskell 

loop k
  | k > 10   = ()
  | otherwise =
      let k' = k + 1
          i  = 3 * k' - 1
      in loop k'

main = do
  let k = (j + 13) `div` 27
  loop k

-------------------

Swift

var k = (j + 13) / 27
var i: Int

while k <= 10 {
    k = k + 1
    i = 3 * k - 1
}