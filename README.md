## 侧信道攻击中一些常用方法的实现

> 与`https://i4mhmh.cn/archives/f61244c1.html`搭配食用更佳

### Datasets

将纽创信安设备上采集到的`0.2W`条未加掩码的原始能量迹作为数据集,格式如下:

| 字段       | 含义   | shape         |
| ---------- | ------ | ------------- |
| traces     | 能量迹 | (2000, 15000) |
| plaintext  | 明文   | (2000, 16)    |
| ciphertext | 密文   | (2000, 16)    |
| key        | 密钥   | (2000, 16)    |

用法:

> python==3.10.1

    &emsp;开箱即用.
