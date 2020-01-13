# FC 小蜜蜂 临摹

使用 Phaserjs3 + TS 重构 FC 小蜜蜂

[参考 - H5 游戏开发：FC 小蜜蜂](https://aotu.io/notes/2018/01/28/galaxian/)

## 启动

```
npm start
```

![截图-开始](https://s2.ax1x.com/2020/01/13/lHct0S.md.png)
![截图-游戏](https://s2.ax1x.com/2020/01/13/lHcGOf.md.png)
![截图-失败](https://s2.ax1x.com/2020/01/13/lHcYm8.md.png)

## 开发步骤

先列出大纲，详细文章正在整理中...，择日更新

### 初始化画布

### 初始化四个场景

建立四个场景： 开始、游戏、失败、成功

### 开始场景

图片与文本定位的差别

背景滚动

资源加载

进度条

点击事件

转转到游戏场景

### 游戏场景

初始化小蜜蜂

分三组

蜜蜂飞舞动画
整体移动动画

初始化飞机

飞机移动

子弹发射逻辑处理

碰撞逻辑处理

爆炸动画

加分与生命值

成功与失败转场

### 失败、成功场景

成功场景显示所得分数

场景之前传参
