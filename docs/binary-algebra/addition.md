---
layout: circuitverse
title: Addition
nav_order: l0s000
cvib_level: basic
parent: Binary algebra
has_children: false
---


# Binary addition
{: .no_toc}


## Table of contents
{: .no_toc .text-delta}

1. TOC
{:toc}


## Addition

Binary addition is similar to Decimal addition. As this addition is binary, it implies that you cannot have a number greater than 1 i.e., when you do '1+1' it gives 0 with carry 1 i.e, 10.

```yaml
Examples :
0 + 0 = 0
0 + 1 = 1
1 + 0 = 1
1 + 1 = 1

    1 1   (3)
  + 1 0   (2)
  -----
  1 0 1   (5)
  -----
```

In the above example, for units place gives 1 as the submission of 1 and 0, whereas, when addition occurs at the ten's place where 1 and 1 are added, it gives 10 not 2 because this is binary addition which results in carry of 1 and 0 as a result of the submission. The example below gives 110 because it results in 1~~1~~1 at the tens place which is 11 in binary. As two 1's gives 10, further if you add 1 it will give 11.

```yaml
  1 1   (3)
+ 1 1   (3)
-----
1 1 0   (6)
-----
```


{:.quiz}
1. What is the answer to `1100` + `0011`= ?
   1. 1111
   * 1101
   * 1110
   * 1100
2. `11111111` + `00100000` = `100011111` is an example of `______`
   1. Overflow error
   * 8 bit binary addition
3. What is the answer to `01101011` + `01010100`= ?
   1. 10111111
   * 01111011
   * 11101111
   * 11101101  
