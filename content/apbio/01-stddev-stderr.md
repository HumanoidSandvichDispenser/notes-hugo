---
title: Standard Deviation and Standard Error
date: "2022-01-01"
---

# Standard Deviation
*Standard deviation* measures how spread out the data is.

A lower standard deviation:
    - Data is closer to the mean
    - The independent variable may be causing the changes in the dependent
      variable

A higher standard deviation:
    - Data is more spread out from the mean
    - Factors other than the independent variable may be causing the changes
      in the dependent variable

To calculate standard deviation $s$

$$ s = \sqrt{\frac{\Sigma (x_i - \overline{x})^2}{n - 1}} $$

# Standard Error

*Standard error* (of the mean) is how far the sample mean is from the true
population mean.

For example, if you are sampling pine trees with a particular fungus in a
forest, you could sample all the trees in a forest (population) and calculate
the mean, but it might take too much time. So you sample a small number of
trees of the forest and you can calculate your sample mean. The standard error
is the comparison of the sample mean to the population mean. How far the sample
mean is from the population mean might indicate accuracy in the study. 

$$ SE_x = \frac{s}{\sqrt{n}} $$

<img src="../assets/stderr.png"/>

Which is a valid statement?

<img src="../assets/stderr2.png"/>

~~Fish2Whale food caused the most fish growth.~~ -- Invalid statement. Standard
error overlaps

Fish2Whale food caused more fish growth than Budget Fude. -- This is a valid
statement since the error does not overlap.
