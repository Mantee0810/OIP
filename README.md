# OIP
这是一个**即插即用**的模块，自适应不同大小的输入（不需要手动输入**任何**参数）

```python
if __name__ == '__main__':
```
中的代码展示了对不同size张量的自适应性

## 用法
在模型的类定义中，按以下方式处理：
* from OIPModule.py import OIPModule
* 在__init__函数中，加入`self.oip = OIPModule()`
* 在forward函数中，加入`map = self.oip(map)`
即可完成模块插入

## 数据集
数据集与下载链接：

[SUN RGB-D](https://rgbd.cs.princeton.edu/)

[NYUv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)

## 基础代码来自公开仓库

[ESANet](https://github.com/TUI-NICR/ESANet)

