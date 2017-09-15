# matlab_code
some algorithm write by matlab

remove detrend:去除信号的线性趋势，matlab中有一个detrend函数，这个是自己写的。首先把数据用最小二乘法拟合出一条直线y=a+bx，在信号中减去这条直线，最后
               使得数据的平均值趋于零。
