# Convolutional-Block-Attention-Module_PPT
This is Convolutional Block Attention Module PPT of follow_bobo workshop
加入公号：follow_bobo,加入机器学习交流群

这是今年ECCV2018的一篇文章，主要贡献为提出一个新的网络结构。之前有一篇论文提出了SENet，在feature map的通道上进行attention生成，然后与原来的feature map相乘。这篇文章指出，该种attention方法只关注了通道层面上哪些层会具有更强的反馈能力，但是在空间维度上并不能体现出attention的意思。CBAM作为本文的亮点，将attention同时运用在channel和spatial两个维度上，CBAM与SE Module一样，可以嵌入了目前大部分主流网络中，在不显著增加计算量和参数量的前提下能提升网络模型的特征提取能力

