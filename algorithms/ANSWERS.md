### Excercise I.

- a) O(n)
- b) O(log(n))
- c) O(sqrt(n))
- d) O(n*log(n))
- e) O(n^3)
- f) O(n)
- g) O(n)

### Excercsise II.

```
// work in progress need to go back and review notes

function maxValue(arr) {
   let maxDifference = 0;
   for (let i = arr.length - 2; i > 0; i--) {
       let maxNum = arr[arr.length - 1];
       if (maxNum > arr[i]) {
           maxDifference = Math.max(maxDifference, maxNum - arr[i]);
       }
   }
   return maxDifference;
}
```