# 2022年天文数据与处理的课程作业：

## A-光谱拟合

1.用Gauss模型拟合Halpha、Hbeta、[OIII]5007以及[NII]6584的发射线

_目标源光谱：spec-55976-F5597612_sp08-188.fits.gz_

2.计算该光谱对应天体的视向速度

### Tips

- _首先测量谱线的观测波长（线心波长）_

- _红移=（观测波长-静止波长）/静止波长_

- _视向速度=红移*光速_

- _四条谱线的静止波长分别为:6563A, 4863A, 5007A, 6584A_

- _数据读取等相关代码操作参考：SpectraFitting.ipynb_

### 要求

_需要给出计算结果和可运行的源代码_
