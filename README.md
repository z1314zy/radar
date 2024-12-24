雷达数据集
![image](https://github.com/user-attachments/assets/21dad91f-6f54-42e7-9dfe-b16a058b9ba0)

雷达跌倒检测数据集来源于https://blog.csdn.net/sxyang2018/article/details/129760027。作者为：洋洋Young
该数据集使用德州仪器公司IWR684毫米波雷达，采集人体不同动作的原始雷达数据。雷达数据采集所使用的软硬件信息如下:
雷达型号:Texas Instrument IWR6843
雷达主控板:DCA1000
电脑操作系统:Windows 10
雷达配套软件:mmWave Studio
雷达数据的采集地点位于深圳大学致腾楼数字信号处理以及 VLS| 实现实验室(509-1室)，下图为实验室环境以及雷达数据采集平台：  
![image](https://github.com/user-attachments/assets/6060dad5-6ce9-4546-b4a6-7d4724d837f0)
![image](https://github.com/user-attachments/assets/b572863e-7e6c-4f23-a510-4bce4b046d01)

探讨了基于雷达与深度学习的摔倒检测技术，利用德州仪器的IWR6843毫米波雷达收集人体动作数据，包括坐下、行走、跳跃、前摔、后摔和侧摔等。通过数据采集和处理，建立了一个包含12000个动作的雷达数据集，并采用8:1:1比例划分为训练、验证和测试集。为提取微多普勒效应特征，应用短时傅里叶变换进行时频谱分析，为后续深度学习模型提供输入。
