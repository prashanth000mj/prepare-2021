
#### 1. JS handles decimal points / floats differently
`0.1 + 0.2 === 0.3` -----> false: 0.1 + 0.2 = 0.30000000000000004
<details>
  <summary>Know More</summary>
  <pre>
  1. You can correct the above statement by `(0.2 * 10 + 0.1 * 10) / 10 === 0.3`
  2. The maximum number of decimals is 17
  3. Numbers in JavaScript are actually floating points
  
  References: 
  <a href="https://modernweb.com/what-every-javascript-developer-should-know-about-floating-points/">What Every JavaScript Developer Should Know About Floating Points</a>
  <a href="https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html">What Every Computer Scientist Should Know About Floating-Point Arithmetic</a> <b>-- YET TO REAB</b>
  </pre>
  
</details>
