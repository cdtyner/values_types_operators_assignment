# Values, Types & Operators Exercises

1. What are the types of the following expressions and what do they evaluate to, and why?
* `17` integer
* `1 + 2 * 3 + 4` integer 11
* `800 / 80 / 8` integer 1.25
* `400 > 200` boolean true
* `1 !== 1`  boolean false
* `true || false` true
* `true && false` true
* `20 % 6`  integer 2
* `'a' + 'b'` string ab

2. What will the following return?
* `typeof 4` integer
*  `typeof 'hello'` string
*  `typeof true` boolean
* `2 === 1 || 3 === 4` false

3. Create a truth table for the expression A || B.

``` js

|  A      |  B      |    A || B    |
| true    |  true   |  true        |
| true    |  false  |  true        |
| false   |  true   |  true        |
| false   |  false  |  false       |

```

For reference, here is a truth table for the expression A && B:

``` js

|   A   |   B   | A & B |
| true  | true  | true  |
| false | true  | false |
| true  | false | false |
| false | false | false |

```
4. Create a truth table for the expression !A && !B.

``` js
|   A   |   B   | !A && !B |
|  true  | true  | true  |
|  false | true  | false |
|  true  | false | false |
|  false | false | false |

```




For reference, here is a truth table for the expression A && !B:

``` js

|   A   |   B   |   !B   | A & B |
| true  | true  | false  | false |
| false | true  | false  | false |
| true  | false | true   | true  |
| false | false |  true  | false |

```
5. Write a step-by-step evaluation for the following expression (remember order of operations): `2 + 3 * 2 + 1`.
  For reference, here is a exp of a step-by-step evaluation:
  ```js
  1 + 2 + 3 + 4
      3 + 3 + 4
          6 + 4
              10

  ```

``` js
 3 * 2
 2 + 6
 8 + 1
    9
```

 6. Write a step-by-step evaluation for the following expression (remember order of operations): `4 / 2 + 8 / 4`.
 ``` js
  4 / 2
  8 / 4
  2 + 2
      4

 ```

 7. Write a step-by-step evaluation for the following expression: `'ca' + 'ter' + 'pi' + 'llar'`.
 ``` js
 'ca' + 'ter' + 'pi' + 'llar'
        'cater' + 'pi' + 'llar'
                  'caterpi' + 'llar'
                              'caterpillar'

 ```
 8. Write a step-by-step evaluation for the following expression: `2 * 4 === 8 && 'car' + 'pool' === 'carpool'`.

 ``` js
 2 * 4 === 8 && 'car' + 'pool' === 'carpool'
     8 === 8 && 'car' + 'pool' === 'carpool'
          true && 'car' + 'pool' === 'carpool'
          true && 'carpool' === 'carpool'
          true && true
          true


 ```
