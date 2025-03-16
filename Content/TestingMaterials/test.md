---
layout: default
title: "Testing"
author: "William Edwards Cipher"
date: "2025-03-12"
---

# Testing Site

Lorem ipsum odor amet, consectetuer adipiscing elit. Congue commodo augue condimentum ligula malesuada convallis. Aridiculus ullamcorper cursus nunc suscipit hac. Tristique lectus ornare mi dignissim tortor sem platea. Maximus odio eleifend suspendisse felis dolor commodo cras mollis. Aefficitur ante volutpat laoreet cubilia enim. Dui arcu ultricies vestibulum class metus amet. Scelerisque mus aliquam dictum volutpat inceptos finibus venenatis curae. Et posuere vestibulum elementum tristique; potenti erat.

![A very wide image.](./Sierra_HDR_Panorama_DFX8048_2280x819_Q40_wm_mini.png "Landscape")

Maecenas malesuada primis gravida nisi consequat neque. Molestie sollicitudin egestas vestibulum imperdiet nisi phasellus rutrum. Duis duis amet adipiscing eu mus cubilia nibh dolor. Suspendisse penatibus placerat nibh a rhoncus class. Sociosqu velit bibendum ac hendrerit luctus nisl. Curabitur fusce aenean varius conubia etiam pretium etiam pretium. Egestas dictum leo porttitor consequat sit proin aliquet suscipit tristique. Habitasse et natoque venenatis eleifend dolor augue. Fames ex varius facilisi ipsum pretium quis dignissim consectetur nisi.

![Stelle nomming a watermelon.](./Sticker_PPG_03_Stelle_01.png "Stelle_Nom")

Accumsan consectetur fermentum quis orci leo pellentesque consectetur ultrices. Diam iaculis venenatis eros condimentum cras proin aliquet. Sapien faucibus ipsum lacinia tincidunt sociosqu vel pellentesque? Amet egestas a litora rutrum eleifend. Platea fringilla sapien rhoncus ut vivamus purus aenean. Aliquet convallis maecenas vivamus class maximus class risus etiam? Dictum est risus dolor volutpat et tortor gravida. Ad vehicula pellentesque etiam adipiscing ad felis bibendum euismod. Tortor taciti orci ante curae, gravida quisque. Class blandit proin egestas dolor mauris eget.

## Mathematical Typesetting

The quadratic formula is stated as follows:

$$ax^2 + bx + c = 0 \implies x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

where $$b^2 - 4ac$$ is called the discriminant. This site is currently using MathJax to display math.

## Code

The following code block is copied from a `MATLAB` file:

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