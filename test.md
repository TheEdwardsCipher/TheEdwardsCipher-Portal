---
layout: default
---

# Testing Site

This page is to test multiple things. Look! A formula!

$$ax^2 + bx + c = 0 \implies x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

Here is a piece of code:

```
clear; clc

N = 1000; % Number of parallelograms (i.e., pairs of vectors)

sum = 0; % Sum of areas

for n = 1:N
    u = randn(4, 1); % Vector u
    v = randn(4, 1); % Vector v

    umag = norm(u); % Magnitude of u
    vmag = norm(v); % Magnitude of v

    A = sqrt((umag^2)*(vmag^2) - dot(u, v)^2); % Area of parallelogram
    sum = sum + A;
end

avg = sum/N % Average of areas
```

[Front Page](./)