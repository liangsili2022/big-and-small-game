# Big & Small

猜牌游戏：根据当前牌面，预测下一张牌是更大还是更小。

## 玩法

- 牌面朝上发一张牌
- 猜测下一张牌是 **Bigger** 还是 **Smaller**
- 点数：A=1, J=11, Q=12, K=13
- 同点数时按花色：♠ > ♥ > ♦ > ♣
- 连胜越多，分数越高

## 在线体验

[GitHub Pages](https://liangsili2022.github.io/big-and-small/)

## 本地运行

```bash
# 用浏览器直接打开
open big-and-small.html

# 或启动本地服务器
python3 -m http.server 8888
# 访问 http://localhost:8888/big-and-small.html
```
