# MLND
Learn Lane Detection with Deep Learning
referrence: https://github.com/mvirgo/MLND-Capstone
# 使用深度学习的车道线检测
在这个项目中，我使用基于深度学习的方法来提高车道线的检测。我最终的模型使用一个全卷积的神经网络来输出车道线的预测图像
请看我的最终完成项目报告 [这里](https://github.com/mvirgo/MLND-Capstone/blob/master/MLND%20Capstone%20Project%20Report.pdf)
或者看我的原始方案 [这里](https://github.com/mvirgo/MLND-Capstone/blob/master/proposal.pdf)

##数据集
###对于全卷积神经网络
可以下载所有我所使用的用于训练的数据集 [这里](https://www.dropbox.com/s/rrh8lrdclzlnxzv/full_CNN_train.p?dl=0) 和所有标签集（只有RGB中的G通道，使用一个额外的维度标出了车道线，这样可以在Keras中容易的使用）
###图像和系数标签
如果拟只是想要没有旋转或者翻转的原始训练图像（缩小尺寸到80x160x3），你可以在[这里](https://www.dropbox.com/s/1bnp70bhaz5kma9/coeffs_train.p?dl=0)
也可以找到相关的系数标签（不是画线标签，而是拟合曲线的系数

##软件需求
如果使用Linux或者Mac，你可以使用conda 环境文件。 















