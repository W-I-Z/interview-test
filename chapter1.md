# Chapter1. 2つの要素の和のインデックス値を返す

整数の配列を引数で与えられたときに、2つの要素の和がターゲットの整数となる場合  
その要素のインデックスを返すメソッドを実装してください。

<details>
<summary>注意点</summary>

* 同じ要素を2回以上使用することはできません
</details>
You may assume that each input would have exactly one solution, and you may not use the same element twice.

## 例

```
nums = [2, 7, 11, 15], target = 9,

nums[0] + nums[1] = 2 + 7 = 9,
return [0, 1].
```