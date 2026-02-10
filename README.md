hamming-code-calculator
=======================
```
"11011 11000 11010 00110".replaceAll(/\s+/g, "").split("").reduce((count, currentValue, currentIndex) => {
   return currentIndex % 2 == 0 && currentValue == 1 ? (count + 1) : count
}, 0)
even parity: count is even ? 0 : 1
odd parity: count is odd ? 0 : 1
```
