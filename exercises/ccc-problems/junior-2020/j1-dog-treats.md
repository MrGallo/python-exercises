# J1: Dog Treats





### Problem Description
Barley the dog loves treats. At the end of the day he is either happy or sad depending on the number and size of treats he receives throughout the day. The treats come in three sizes: `small`, `medium`, and `large`. His happiness score can be measured using the following formula:

`1 Ã— S + 2 Ã— M + 3 Ã— L`

where `S` is the number of small treats, `M` is the number of medium treats and `L` is the number of large treats.

If Barleyâ€™s happiness score is `10` or greater then he is happy. Otherwise, he is sad. Determine whether Barley is happy or sad at the end of the day.

### Input Specification
There are three lines of input. Each line contains a non-negative integer less than `10`. The first line contains the number of small treats, `S`, the second line contains the number of medium treats, `M`,
and the third line contains the number of large treats, `L`, that Barley receives in a day.

### Output Specification
If Barleyâ€™s happiness score is `10` or greater, output `happy`. Otherwise, output `sad`.

**Sample Input 1**
```
3
1
0
```

**Output for Sample Input 1**
```
sad
```

**Explanation of Output for Sample Input 1**
Barleyâ€™s happiness score is `1 Ã— 3 + 2 Ã— 1 + 3 Ã— 0 = 5`, so he will be `sad`.

**Sample Input 2**
```
3
2
1
```

**Output for Sample Input 2**
```
happy
```

**Explanation of Output for Sample Input 2**
Barleyâ€™s happiness score is `1 Ã— 3 + 2 Ã— 2 + 3 Ã— 1 = 10`, so he will be `happy`.






## Tests
```python

```
