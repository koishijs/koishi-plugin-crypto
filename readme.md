# koishi-plugin-crypto

[![npm](https://img.shields.io/npm/v/koishi-plugin-crypto?style=flat-square)](https://www.npmjs.com/package/koishi-plugin-crypto)

在 Koishi 中体验传统的文本加密算法。

## 指令：crypto

- 基本语法：`crypto  <algorithm> <text:rawtext>`
- 示例：
  - `crypto vigenere(keyword) "Hello World"` -> `Rijhc Nrbpb`
  - `crypto vigenere(keyword) -d "Rijhc Nrbpb"` -> `Hello World`
