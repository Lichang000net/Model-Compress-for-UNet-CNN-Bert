# Model-Compress-for-UNet-CNN-Bert
使用 DepthWise 和 PointWise 卷积简化滑坡语义分割任务中的 Unet模型 
以ResNet18 作为base模型，使用7层CNN模型进行知识蒸馏，
对滑坡二分类任务中的7层CNN模型，根据 gamma 系数裁剪模型结构 
使用 LSTM蒸馏 情感分类任务中 fine-tuning 的 Bert 模型
