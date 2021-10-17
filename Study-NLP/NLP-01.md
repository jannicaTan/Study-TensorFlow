## ML Framework——

##### Linear models:

存在限制性成为Model Bias，不能够模拟真实状况。

##### Piecewise Linear= constant(常数项)+sum of a set of(变量)

变量：不同的转折点(pieces)的折线相加

- 第一段折线：0(初始横线)+1
- 第二段折线：0+1+2
- 第三段折线：0+1+2+3

转折点越多，变量越多。如果为曲线，可以取点变为折线。

##### Sigmoid Function：y=c sigmoid(b+wX1)

每个Sigmoid被称为一个Neuron(神经元)——Hidden Layer，多个Hidden Layer成为Deep Learning

- 自变量越大，越接近C
- 自变量越小，越接近于0
- 通过调整c（斜率）/b（左右移动）/w（高度变化），使Sigmoid接近Hard Sigmoid

##### Piecewise Linear➡️`y=b+总和(Ci sigmoid(bi+wix1))`

 

重新定义——θ

#### Step1:function  with unknown式子

More Features：加图

- 推理sigmoid()的括号内的内容，用线代表示`r=b+Wx`
- a=sigmoid()之后，与Ci加
- 再与b相加

#### STEP2:LOSS=L(θ)

- 给定θ的值:即给定c/b/w/x，得到一个计算y
- 与真实值y进行求差，获得e
- 将所有e相加求取平均值

#### STEP3:New Model——求取θ*使得Lossmin

- 随机选择一个θ=θ0的情况,求取每一个参数对L的微分，集合起来获得gradient
- 更新参数（update)
- 计算完毕所有的batch（1 epoch）
- epoch=examples/baches



##### Activation Function：ReLU与Sigmoid

**ReLU:**多个Linear折线叠加

- ReLU与Sigmoid转换



Overfitting:在训练资料准确度变好，但是预测资料的准确度变差















 