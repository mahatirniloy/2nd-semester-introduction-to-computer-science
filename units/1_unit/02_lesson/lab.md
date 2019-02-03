# Lab 1.02 - Using the Interpreter

## Part 1
Using the interpreter, type in the expressions below. Copy and paste the output into the output column. If the result is unexpected, note that in the third column.


### Section 1

| |**Input** | &nbsp; &nbsp; **Output** &nbsp; &nbsp;|**Did it do something unexpected?**|
|-| ----| ------- | ----------- |
|a| `5 + 2 * 2` |9<br><br><br><br>| | 
|b| `2/3 `|0.6666666666666666<br><br><br><br>| | 
|c| `2.0 * 1.5`|3.0<br><br><br><br>| | 
|d| `(2 + 3) * 10`|50<br><br><br><br>| | 
|e| `5.0 // 2` |2.0<br><br><br><br>| | 
|f| `5.0 % 2` |1.0<br><br><br><br>| | |
    

### Section 2

||**Input** | &nbsp; &nbsp; **Output** &nbsp; &nbsp;|**Did it do something unexpected?**|
|-| ----| ------- | ----------- |
|a| `a` |Error ("a"=a)<br><br><br><br>|Yes, error showed up | 
|b|`'a'`|a<br><br><br><br>| | |

### Section 3

||**Input** | &nbsp; &nbsp; **Output** &nbsp; &nbsp;|**Did it do something unexpected?**| 
|-| ----| ------- | ----------- |
|a| `'a + b'`|a+b<br><br><br><br>| | 
|b| `'a' + 'b'`|ab<br><br><br><br>|| | 


### Section 4

||**Input** | &nbsp; &nbsp; **Output** &nbsp; &nbsp;|**Did it do something unexpected?**|
|-| ----| ------- | ----------- |
|a| `'a' * 'b'` |Error ("a" * "b"=a*b<br><br><br><br>|Yes, error showed up. | 
|b| `'a' * 2` |aa<br><br><br><br>| | |

## Part 2
**Before going to the IDE: **

1. For each item, predict the data type of the result and enter into the "String/Integer/Float" column.
2. Next, predict the value of the result for each item and enter into it into the "Prediction of Result" column.

||     **Expression**     | **String/Integer/Float** | **Prediction of Result** | **Interpreter Result** |
|-| :------------------: | :-----------------------: | :--------------------: | :-----------------: |
|a| `10 * 2`            |  <br><br> integer <br><br>               |    20               |         20         | 
|b| `.5 * 2`           |  <br><br> Float <br><br>                       |1                      |1.0                  | 
|c| `10/2`             |  <br><br> Float  <br><br>                       |5                      |5.0                   | 
|d| `10%2`            |    <br><br> integer <br><br>                     |0                      |0                  | 
|e| `2 ** 3`           |   <br><br> integer <br><br>                      |8                      |8                   | 
|f| `(2+5)*3`          |    <br><br> integer <br><br>                     |21                      |21                   | 
|g| `2 + 5 * 3`         |   <br><br> integer <br><br>                      |17                      |17                   | 
|h| `'ab' + '12' + '3'` |    <br><br> string <br><br>                     |ab123                      |ab123                   | 
|i| `x`                |    <br><br> string <br><br>                     |x                      |x                   | 
|j| `"ab" + "cd"`      |    <br><br> string <br><br>                     |abcd                      |abcd                   | 
|k| `'abc' * 2`        |    <br><br> string <br><br>                     |abcabc                      |abc                   | 
|l| `'1'*2 + '2' * 3`  |   <br><br> integer <br><br>                      |11223                      |1123                   | 
|m| `1 * 2 + '3' * 2`  |   <br><br> integer <br><br>                      |1133                      |1133                   | 
|n| `'A' ** 2`         |  <br><br> string <br><br>                       |aa                      |aa                   | 
|o| `'bc' % 2`        |   <br><br> string <br><br>                      |bc%2                      |bc%2                   | 
|p| `'bc' / 2`         |   <br><br> string <br><br>                      |bc/2                      |bc/2                   |

**Now go to the IDE:** 
1.  Use the interpreter to evaluate the expressions, write down results in the "Interpreter Result" column.
