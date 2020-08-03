# DeepLearningForTimeSeriesForecasting
深度学习以进行时间序列预测
## 序言  
+ ***7天迷你课***  
```
  3.用于时间序列预测的MLP  
  4.用于时间序列预测的CNN  
  5.用于时间序列预测的LSTM  
  6.编码器-解码器LSTM多步预测  
  7.用于时间序列预测的CNN-LSTM  
```  
## 一、预测趋势和季节性（单变量）
### 1.基于SARIMA预测的网格搜索超参数优化  
```
  1.网格搜索框架  
  2.无趋势和季节性研究  
  3.趋势性研究  
  4.季节性研究  
  5.趋势和季节性研究  
```  
+ ***1_1.为时间序列预测创建ARIMA模型***  
```
  1.数据预览  
  2.预览一下数据的自相关图  
  3.预览残差图和残差的密度分布图  
  4.滑动窗口预测ARIMA模型  
```  
+ ***1_2.如何网格搜索ARIMA超参数***  
```
  每日女性出生研究  
  洗发水销售研究  
```
+ ***1_3.自相关和篇自相关介绍***  
```
  1.自相关ACF图  
  2.偏自相关PACF图  
``` 
### 2.基于三重指数平滑预测的网格搜索超参数优化 
```
  1.网格搜索框架  
  2.无趋势和季节性研究  
  3.趋势性研究  
  4.季节性研究  
  5.趋势和季节性研究  
```  
### 3.单变量时间序列预测开发深度学习模型  
```
  2.多层感知器模型  
  3.卷积神经网络模型_CNN  
  4.递归神经网络模型_LSTM  
  5.递归神经网络模型_CNN+LSTM  
  6.递归神经网络模型_ConvLSTM2D  
```
## 二、几种模型类型
### 1.用于时间序列预测的MLP
```
  01.(多步+单变量输入)_(单步+单变量输出)_监督学习数据
  02.(多步+单变量输入)_(单步+单变量输出)_MLP模型
  03.(多步+多变量输入)_(单步+单变量输出)_监督学习数据
  04.(多步+多变量输入)_(单步+单变量输出)_MLP模型
  05.(多步+多变量输入)_(单步+多变量输出)_监督学习数据
  06.(多步+多变量输入)_(单步+多变量输出)_MLP模型
  07.多路输入_(多步+多变量输入)_(单步+单变量输出)_MLP模型
  08.多路输出_(多步+多变量输入)_(单步+多变量输出)_MLP模型
  09.(多步+单变量输入)_(多步+单变量输出)_监督学习数据
  10.(多步+单变量输入)_(多步+单变量输出)_MLP模型
  11.(多步+多变量输入)_(多步+单变量输出)_监督学习数据
  12.(多步+多变量输入)_(多步+单变量输出)_MLP模型
  13.(多步+多变量输入)_(多步+多变量输出)_监督学习数据
  14.(多步+多变量输入)_(多步+多变量输出)_MLP模型
```
### 2.用于时间序列预测的CNN
```

```