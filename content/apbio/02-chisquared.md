---
title: Chi Squared Test
date: "2022-01-02"
---

# Hypotheses

* A hypothesis is a statement of the researcher's idea or guess
* To test a hypothesis, the first thing to do is write a statement called the
  *null hypothesis*
  * The null hypothesis is often the opposite of the researcher's guess

## Example

Null hypothesis: *There is no difference between the average number of streams
per square kilometer and the bedrock type.

Alternative hypotheses: *There is a difference between the average number of
streams per square kilometer and the bedrock type.

# Chi Squared Test $\chi$

$\chi^2 = \Sigma \frac{(O - E)^2}{E}$

$O =$ observed

$E =$ expected

## Example

In a bag of 55 M&M's, there are 16 browns, 9 blues, 11 oranges, 7 greens, 4
reds, and 8 yellows.

An unofficial report expects a bag of M&M's to consist of 13% browns, 24%
blues, 20% oranges, 16% greens, 13% reds, and 14% yellows.

Null hypothesis $H_0$: *There is **no significant difference** between the color
distribution of the M&M’s from the unofficial report and the actual color
distribution of the M&M’s*

| | Brown | Blue | Orange | Green | Red | Yellow | **Total** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Observed $O$ | 16 | 9 | 11 | 7 | 4 | 8 | 55 |
| Expected $E$ | 7 | 13 | 11 | 9 | 7 | 8 | 55 |
| Difference $(O-E)$ | 81 | 16 | 0 | 4 | 9 | 0 | *N/A* |
| Difference Squared $(O-E)^2$ | 81 | 16 | 0 | 4 | 9 | 0 | *N/A* |
| $\frac{(O-E)^2}{E}$ | 11.6 | 1.2 | 0 | 0.4 | 1.3 | 0 | $\chi^2 = 14.5$ |

Now we calculate our degrees of freedom, which is the number of categories
minus one = 5.

<!--| Degrees of Freedom | Probabilities |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | 0.016 | 0.46 | 1.32 | 2.71 | 3.84 | 6.64 |
| 2 | 0.21 | 1.39 | 2.77 | 4.61 | 5.99 | 9.21 |
| 3 | 0.58 | 2.37 | 4.11 | 6.25 | 7.82 | 11.35 |
| 4 | 1.06 | 3.36 | 5.39 | 7.78 | 9.49 | 13.28 |
| 5 | 1.61 | 4.35 | 6.63 | 9.24 | 11.07 | 15.09 |-->

<table>
    <thead>
        <tr>
        <th>Degrees of Freedom</th>
        <th colspan="4">Accept null hypothesis</th>
        <th colspan="2">Reject null hypothesis</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td>0.016</td>
            <td>0.46</td>
            <td>1.32</td>
            <td>2.71</td>
            <td>3.84</td>
            <td>6.64</td>
        </tr>
        <tr>
            <td>2</td>
            <td>0.21</td>
            <td>1.39</td>
            <td>2.77</td>
            <td>4.61</td>
            <td>5.99</td>
            <td>9.21</td>
        </tr>
        <tr>
            <td>3</td>
            <td>0.58</td>
            <td>2.37</td>
            <td>4.11</td>
            <td>6.25</td>
            <td>7.82</td>
            <td>11.35</td>
        </tr>
        <tr>
            <td>4</td>
            <td>1.06</td>
            <td>3.36</td>
            <td>5.39</td>
            <td>7.78</td>
            <td>9.49</td>
            <td>13.28</td>
        </tr>
        <tr>
            <td>5</td>
            <td>1.61</td>
            <td>4.35</td>
            <td>6.63</td>
            <td>9.24</td>
            <td> **11.07** </td>
            <td>15.09</td>
        </tr>
    </tbody>
</table>

$\chi^2 = 14.5$, which is greater than the critical value $11.07$. This means
the null hypothesis is rejected.

Alternative hypothesis $H_A$: *There **is a significant difference** between the color
distribution of the M&M’s from the unofficial report and the actual color
distribution of the M&M’s*

From this, we can conclude there are several other factors that may be
affecting our color distribution.
