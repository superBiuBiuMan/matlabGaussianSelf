# matlabGaussianSelf
Matlab实现高斯模糊非库函数

# 高斯模糊步骤
1.创建高斯矩阵
2.高斯矩阵和图片矩阵相乘
3.输出

# 高斯模糊具体
1.创建高斯矩阵(注意,保证矩阵相加为1)
![image](https://raw.githubusercontent.com/1464815392/matlabGaussianSelf/main/%E9%AB%98%E6%96%AF%E4%BA%8C%E7%BB%B4%E7%9F%A9%E9%98%B5.png)

2.高斯矩阵(比如3*3)和图片矩阵(3*3)相乘得运算结果,运算结果为一个矩阵,矩阵的和即为该点像素的值,比如红色圈出矩阵即为图片中的矩阵,和高斯矩阵相乘后的值相加即为圆圈里面的值
![image](https://raw.githubusercontent.com/1464815392/matlabGaussianSelf/main/%E7%9F%A9%E9%98%B5.png)

3.依次循环

4.结束(附一张效果图)
![image](https://raw.githubusercontent.com/1464815392/matlabGaussianSelf/main/%E9%AB%98%E6%96%AF%E7%BB%93%E6%9E%9C.png)
