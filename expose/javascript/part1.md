# Part 1. A Quick Introduction...

![image1](pictures\lab4-part1a-q1+2.png)

1. Line 9 will print 'values added: 20'
2. Line 13 will print 'final result: 20', since result was declared using var it is accessible outside of its block
3. Using var should be avoided because it makes the variable accessible anywhere inside the function regardless of what block it's in, which leads to naming conflicts and scoping issues. 

![image2](pictures\lab4-part1a-q3+4.png)

4. Line 9 prints 'values added: 20'
5. Line 13 returns an error because result was declared using let, so it's not accessible outside of its block

![image3](pictures\lab4-part1a-q5+6.png)

6. Line 9 returns an error because result is declared using const
7. Line 13 returns an error because result was declared using let, so it's not accessible outside of its block