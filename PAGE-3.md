## **Page 3**

![foolmath logo](./images/ramanujan.png)

[Previous Page](./PAGE-2.md#page-2)&nbsp;|&nbsp;Next Page&nbsp;|&nbsp;[Contribute](#support-foolmath)

### **Sum of Cubes Identity**

Another valid proof.

```math
\begin{alignat*}{5}
&\small\text{Ever seen?}\qquad&1^3+2^3\quad&=\quad&&(1+2)^2\\
&\,&1^3+2^3+3^3\quad&=&&(1+2+3)^2\\
&\,&1^3+2^3+3^3+4^3\quad&=&&(1+2+3+4)^2\\
&\small\text{That is}&\sum_{i=1}^{n}i^3\quad&=&&\left(\sum_{i=1}^{n}i\right)^2\\
&\rlap{\text{It is called Sum of Cubes Identity (a.k.a. Square of the Sum)}}\\
&\rlap{\text{Here's the proof.}}\\ \\
&\rlap{\large\text{Step 1. Base Case}}\\
&\,&\sum_{i=1}^{1}i^3\quad&=&&1^3\quad=\quad1\\
&\,&\left(\sum_{i=1}^{1}i\right)^2\quad&=&&1^2\quad=\quad1\\
&\small\text{i.e.}&\sum_{i=1}^{1}i^3\quad&=&&\left(\sum_{i=1}^{1}i\right)^2\\
&\rlap{\large\text{Step 2. Induction Hypothesis}}\\
&\small\text{assuming}&\sum_{i=1}^{k}i^3\quad&=&&\left(\sum_{i=1}^{k}i\right)^2\\
&\rlap{\large\text{Step 3. Induction Step}}\\
&\rlap{\text{We need to prove that the formula also holds for k + 1.}}\\
&\rlap{\text{That is, we need to prove:}}\\
&\,&\sum_{i=1}^{k+1}i^3\quad&=&&\left(\sum_{i=1}^{k+1}i\right)^2\\
&\,&\,&=&&\left(\sum_{i=1}^{k}i+(k+1)\right)^2\\
&\,&\,&=&&\left(\frac{k(k+1)}{2}+(k+1)\right)^2\\
&\small\text{factor }(k+1)&\,&=&&\left((k+1)\left(\frac{k}{2}+1\right)\right)^2\\
&\,&\,&=&&\left(\frac{(k+1)(k+2)}{2}\right)^2\\
&\,&\sum_{i=1}^{k+1}i^3\quad&=&&\left(\sum_{i=1}^{k+1}i\right)^2\\
&\rlap{\text{This matches the formula for }n=k+1\text{, completing the induction step.}}\\
&\rlap{\large\text{Step 4. Conclusion}}\\
&\small\text{Thus}&\sum_{i=1}^{n}i^3\quad&=&&\left(\sum_{i=1}^{n}i\right)^2\qquad&&\small\text{(valid proof)}\\
\end{alignat*}
```
_source code:_&nbsp;[sum_of_the_cubes_id.tex](./src/sum_of_the_cubes_id.tex)&nbsp;|&nbsp;[Go to top](#page-2)&nbsp;|&nbsp;[TOC](https://github.com/chunglim/foolmath#table-of-contents)

### **Support _foolmath_**

I keep adding these kinds of freaks or topics, which are considered interesting, no matter what they are foolish or valid math. **_foolmath_** is a passion project I do under my curiosity at my retirement. Your support will motivate me to curate and expand this repository with even more fascinating content, and especially it can help me pay the bills.

If you find **_foolmath_** entertaining, educational, or you simply enjoy its content, or just feeling generous, please consider [buy me a coffee](https://www.buymeacoffee.com/chunglim). I will highly appreciate and will be very grateful.

<a href="https://www.buymeacoffee.com/chunglim" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

<img src="./images/bmc_qr.png" width="217"/>

Note: All contributions are voluntary and not required to access or use the content. See [LICENSE](./LICENSE.md).<br><br>
[Go to top](#page-2)&nbsp;|&nbsp;[TOC](https://github.com/chunglim/foolmath#table-of-contents)&nbsp;|&nbsp;[Previous Page](./PAGE-2.md#page-2)&nbsp;|&nbsp;Next Page
<br><br>