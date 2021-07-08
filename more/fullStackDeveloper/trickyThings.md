
#### 1. JS handles decimal points / floats differently
`0.1 + 0.2 === 0.3` -----> false: 0.1 + 0.2 = 0.30000000000000004
<details>
  <summary>Know More</summary>
  1. You can correct the above statement by `(0.2 * 10 + 0.1 * 10) / 10 === 0.3`
  2. The maximum number of decimals is 17
</details>
