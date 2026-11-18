# SFO 相位向量与频谱泄漏演示

[打开交互演示](https://litsycn.github.io/sfo-phase-demo/)

发射子载波固定为 $k=17$，FFT 长度为 $N=64$。拖动采样频偏 $\epsilon$ 的滑块或修改 FFT 频点 $q$，观察单位相位向量、合向量终点的轨迹和合向量的模平方。

$$
v_n = e^{j2\pi\left(\frac{k}{1+\epsilon}-q\right)\frac{n}{N}},
\qquad n=0,\ldots,N-1.
$$

保持 $q=16$，将 $\epsilon$ 从 $0$ 调到 $0.0625$。此时 $k/(1+\epsilon)=16$，64 个向量同向，合向量的模平方由约 $0$ 变为 $4096$。
