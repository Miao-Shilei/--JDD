# --JDD
高潜用户预测---季军
由于主办方京东要求不能提供代码分享，抱歉，暂不提供分享代码，下面是一些基本思路供大家学习交流，欢迎私信我！！

比赛简介：
比赛以京东商城真实的用户、商品和行为数据（脱敏后）为基础。通过数据挖掘的技术和机器学习的算法，构建用户购买商品预测模型，输出高潜用户和目标商品的匹配结果，为精准营销提供高质量的目标群体。为电商用户提供更简单、快捷、省心的购物体验。

软件环境：python3*
硬件环境：16G内存+
责任描述：1、特征工程---包括设计特征（特色特征---设计衰减指数特征）；
2、解决样本不平衡问题（采用深度学习思想对正样本划窗采样---划窗增加正样本）；
3、构建用户购买预测模型（记为U模型）；
4、构建用户-商品预测模型（记为U-I模型）；
5、构建两个融合方式（stacking算法融合；U模型与UI模型结果融合）。
