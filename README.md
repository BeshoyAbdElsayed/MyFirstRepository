

#### Test 1:
![Image description](test1.png)

```
 {-2, -2, -2, -2,  1,  0,  0,  0},
 {-2, -2, -2, -2,  1,  0,  1,  1},
 {-2, -2, -2,  3,  1,  0,  1, -2},
 {-2, -2, -2,  1,  0,  1,  2, -2},
 {-2, -2, -2,  1,  1,  2, -2, -2},
 {-2, -2, -2, -2, -2, -2, -2, -2},
 {-2, -2, -2, -2, -2, -2, -2, -2},
 {-2, -2, -2, -2, -2, -2, -2, -2}
```

## Output: 
```
panels that will be flagged:
(3, 1)
(7, 2)
(6, 4)
panels that will be revealed:
```



 #### Test :
![Image description](test2.png)

```
 {-2, -2, -2, -2, -2, -2, -2, -2, -2},
{-2, -2, -2, -2,  3,  1,  1,  2, -2},
{-2, -2, -2, -2,  1,  0,  0,  1, -1},
 {-2, -2, -2,  3,  1,  0,  0,  1,  1},
{-2, -2, -1,  2,  0,  0,  0,  0,  0},
{-2,  2,  2,  1,  0,  0,  0,  0,  0},
{-2,  1,  0,  0,  0,  0,  0,  0,  0},
{-2,  1,  0,  0,  0,  0,  0,  0,  0},
{-2,  1,  0,  0,  0,  0,  0,  0,  0}
```

## Output:
```
 panels that will be flagged:
(3, 2)
(2, 3)
(1, 4)
panels that will be revealed:
(8, 1)
```
