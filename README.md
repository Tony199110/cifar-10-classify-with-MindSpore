# cifar-10-classify-with-MindSpore

本文提供了一个基于开源框架MindSpore的图像识别实验。该实验演示了如何利用开源框架MindSpore完成CIFAR-10图像识别任务。阐明了整个实验功能、结构与流程，并且进行了模型的优化与调参。 
增加卷积的个数、卷积核的大小、增加网络的深度的模型超参数调整，经过实验验证，将模型的准确率从0.60提升至0.73，使损失从1.13降至0.77，说明了超参调整的有效性。由于原版LeNet5的层数少，参数量小，故猜测模型能力不足以容纳cifar-10数据集的所有特征信息，调参的方向是扩大模型参数量。增加卷积的个数、卷积核的大小、增加网络的深度均是提升模型参数的途径。
