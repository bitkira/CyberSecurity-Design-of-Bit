# CyberSecurity-Design-of-Bit
# 项目说明

将项目在github开源呈现，便于小组二人远程更新工作内容

项目主题：生成图样对抗与ai安全

目标实现

本次设计打算完成如下三个目标：

1.顶会文章的阅读与复现

2.基于此框架训练模型发表ieee会议论文

3.基于此框架完成图样对抗的效果实现和性能增强

超额任务：

将ai安全的其他前沿问题囊括在项目中，争取也有所涉猎

首先小组成员学习了基于pytorch的深度学习框架搭建方法 
学习资料如下：

Learn PyTorch for deep learning in a day. Literally.：https://www.youtube.com/watch?v=Z_ikDlimN6A&t=86381s 课程时间（25h） 参考教材 https://www.learnpytorch.io/


# 对抗样本攻击定义
## 对抗样本攻击的定义
攻击者通过在**干净样本**中添加人们难以察觉的细微扰动，使图像识别系统以较高置信度出现攻击者想要的任意错误结果
## 对抗样本的定义
添加细微扰动后的干净样本称为对抗样本
# 对抗样本攻击的分类
## 按照攻击后效果分类
### 定向攻击 Targeted Attack
定向攻击要做到既降低模型对输入样本真实标签的置信度，又要提升攻击者指定标签的置信度（困难）
### 非定向攻击 Non-Targeted Attack
只要做到将模型结果误导到其他错误的类别（简单）
## 按攻击环境分类
### 白盒攻击 White-Box Attack
已知目标模型所有





### 黑盒攻击 Black-Box Attack





