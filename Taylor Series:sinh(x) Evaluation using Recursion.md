EX: 7.5 Evaluate the series:

### Aim: To write a Python program to evaluate the sum of the series using recursion.

### Algorithm:
Got it! Here’s the **Aim** and **Algorithm** for the program that evaluates the series:

---

### Aim:

Write a Python program to evaluate the sum of the series

$$
S = \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \cdots + \frac{1}{n!}
$$

using recursion.

---

### Algorithm:

1. **Start**
2. Read the input value $n$, which represents the number of terms in the series.
3. Define a recursive function `factorial(num)`:

   * If `num` is 0 or 1, return 1.
   * Else return `num * factorial(num - 1)`.
4. Define a recursive function `series_sum(n)`:

   * If $n = 1$, return $\frac{1}{1!}$.
   * Else return $\frac{1}{n!} + \text{series_sum}(n - 1)$.
5. Call `series_sum(n)` to compute the sum of the series.
6. Print the result.
7. **End**

---


### Program:
```
reg no:212223070012
name:Lithick Kumar M N
def fact(n):
    if n==0:
        return 1
    else:
        return n*fact(n-1)
n=int(input())
sum=0
for i in range(1,n+1):
    sum=sum+(1/fact(i))
print(sum)

```
### Output:
![image](https://github.com/user-attachments/assets/cb84cfb8-d517-4833-8578-da37b89141f4)


### Result: Thus, the given program is implemented and executed successfully .



 
