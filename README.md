# Emerging-Technologies-Labs

# TASK 1 - Calculating the square root of 2

*The square root of 2 or root 2 is represented using the square root symbol √ and written as √2 whose value is 1.414. This value is widely used in mathematics. Root 2 is an irrational number as it cannot be expressed as a fraction and has an infinite number of decimals. So, the exact value of the root of 2 cannot be determined.*

## Newton's Method:
[2]
![Newton's Method](images/newtons_method.png)

Newton's Method of calculating square roots is an iterative root-finding algorithm, that produces successively better approximations of the root. Where ${\alpha}_{0} $ is an initial approximation of $\sqrt{N}$. If the initial approximation is suitably chosen, the process converges quickly and accurate approximations to $\sqrt{N}$ are obtained after only a few iterations. However, if extended multiple-precision approximations to $\sqrt{N}$ are sought, the computation time increases rapidly because of the times required for dividing ${N}$ by a many-digit number. Generally, the time required for floating-point division on modern electronic computers compared to floating-point multiplication is at least twice as much for double precision computations.

![Iterational Accuracy](images/iterations.png)

This is an example of the algorithm each time it runs. Where ${\alpha}_{0}=1$, ${\alpha}_{1}=1.5$, and so on for 5 iterations until it is accurate to 100 decimal places (python can only display 52).

### References
[1] The square root of 2; Ian McLoughlin; https://web.microsoftstream.com/video/214c8379-7c67-45b5-910d-39ec5d269223<br/>
[2] The square root of 2 to 1 million decimals; Jacques Dutka; https://www.jstor.org/stable/2004359?seq=1&cid=pdf-reference<br/>
[3] Methods of Computing Square Roots; Wikipedia; https://en.wikipedia.org/wiki/Methods_of_computing_square_roots
