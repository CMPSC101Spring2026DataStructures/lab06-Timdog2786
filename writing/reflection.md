# CS101 Spring 2026 — Practice Midterm Reflection

Name: Timothy Moisio
Date: 3/13/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `TO_DO` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I felt quite postive and optimistic about my performance. I felt comfortable on almost all topics. I found lambdas to be the most difficult.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

I do not have any questions i was unsure about, nor do i know as off right now that i got any wrong.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

The dfference between a postive and negative step in 'range(a, b, step)' is that with a postive step, the range is adding to a to get to b, while a negatie step subtracts from a to get to be. an example of postive is range(1,9,2), and for a negative is range(1,9,-2)

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A key difference between a list and a tuple is that a tuple is unmutable. A difference btween a dictionary and a set is that a set has no duplicates and a dictionary has key that respsents values. You would choose a list when you have various values, that keep being added or subtracted from, and keep track of duplicates. You would use a tuples when you have a set of values that will never change or need to be added to the set. You would use a dictionary if you have values that have another value closely respseneted to it. You would use a set when you need a list but to remove duplicates.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A defualt parameter is a value that python uses when you dont put any value into the parameters.
```
def example_math(a, b=99)
    return a + b
```
in this example, if the user does not put into a 'b' value, it will add 99 to 'a'.

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [n*2 if n % 3 == 0 for range(1,11)]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

64, because python does 2**2 to get 4 then does 4**3 to get 64

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are predefine objects that have certain attrubits and methods. They are necessary in programming to keep code conherent and allow object oriented programming.

---

(Did you remember to add your name and date at the top of this document?)
