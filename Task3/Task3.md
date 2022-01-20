# 绘图与第三方库使用

## 任务要求

要求读入上一个任务生成的csv文件（或者直接读取rmsd.xvg文件），并绘制rmsd随时间变化的曲线图。



## 任务检查

**代码说明**

绘图需要用到第三方库，你可以使用你喜欢的第三方库来进行折线图的绘制。（当然，你如果不愿意用第三方库，要用turtle手搓折线图，我也没意见）。

常见的第三方绘图库有：

- matplotlib (最常见)
- pyecharts (基于百度开源的Echarts)
- plotly (基于javascript，可交互)
- ggplot (从R语言的ggplot2移植过来的)
- PyG2Plot (基于G2Plot，和蚂蚁金服有关)

也有很多在matplotlib基础上进一步封装和调整的库，如Seaborn等；更多和绘图有关的库请参考相关教程和文章 https://www.zhihu.com/question/39684179 。有开源专门用于科研绘图的（样式接近发表文章中的样式）https://github.com/garrettj403/SciencePlots 。

第三方库的安装请参考相关的文档和说明。备注：如果从官方源pip安装库太慢了，可以考虑给pip换源，例如：

使用官方源：

```bash
pip install matplotlib
```

使用清华源：

```bash
pip install matplotlib -i https://pypi.tuna.tsinghua.edu.cn/simple
```



**代码检查**

以上一次任务中有git管理的目录为工作目录，将生成的折线图保存到代码的同一级目录里，git commit，并将折线图文件和代码都push到远程仓库里，提交远程仓库的链接即可。