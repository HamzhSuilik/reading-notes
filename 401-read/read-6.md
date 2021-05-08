# Random Module in Python
Import random module
```import random ```
To generate integer random number
The output range is [1-5]
```print random.randint(0, 5) ```

To generate integer random number from 0 to X : (float)

`import random`
`random.random() * X`

**Choice**
Generate a random value from the sequence sequence.
```random.choice( [‘item_1', ‘item_2', ‘item_3'] ). ```
The output should be any item of the list (randomly)
For example : item_1

Shuffle
Randomly rearranges items in the list
Syntax :
`random.shuffle(list)`

Randrange :
Generate a random number with specific step starting from initial value 
`random.randrange(start, stop, step) `

For example this code print even random number from 0 and 100

```import random
 for i in range(2):
 print random.randrange(0, 100, 5) 
```
The expected output : 2,4,6,8,10,12, ….. 98 , 100

# Risk Analysis in Software Testing

Risk in Software : The probability of any unwanted incident

**Why use Risk Analysis?**
We use Risk Analysis to identify potential problems and write tests that discover any expected problems

**possible risks that you could encounter :**
- Use of new hardware
- Use of new technology
- Use of new automation tool
- The sequence of code
- Availability of test resources for the application

**risk magnitude indicators :**
* High: the effect of the risk would be very high and non-tolerable.
* Medium: it is tolerable but not desirable. limited risk.
* Low: it is tolerable. There lies little or no external exposure or no financial loss.

**Business Risks:** .It is the risk that may come from your company or your customer, not from your project. It is usually related to a misunderstanding between work teem and customer .

**Software Risks:** the risks associated with the software development process.

**Risk Assessment** is the most important step in the risk analysis process
**There are three perspectives of Risk Assessment:**
- Effect
- Cause
- Likelihood


**Risk Analysis steps:**

Searching the risk
Analyzing the impact of each individual risk
Measures for the risk identified







