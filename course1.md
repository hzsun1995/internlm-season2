# 书生·浦语大模型全链路开源体系
专用模型（解决特定任务）-->>通用大模型（chatgpt和GPT-5）
书生·浦语大模型全链路开源历程

![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/e9de2885-6002-4dc6-b4af-44b94541a88a)

7B轻量小模型-问题：占用显存多少？对硬件要求多少？8G显存？
20B重量级模型
![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/6e55c8f1-ea63-4eae-b8d6-9b47b36eaaff)




InternLM2-Base
高质量和具有很强可塑性的模型基座是模型进行深度领域适配的高质量起点

InternLM2
在 Base 基础上，在多个能力方向进行了强化，在评测中成绩优异，同时保持了很好的通用语言能力，是我们推荐的在大部分应用中考虑选用的优秀基座

InternLM2-Chat
在 Base 基础上，经过SFT和 RLHF，面向对话交互进行了优化，具有很好的指令遵循、共情聊天和调用工具等的能力

新一代数据清洗过滤技术
多维度数据价值评估
基于文本质量、信息质量、信息密度等维度对数据价值进行综合评估与提升
高质量语料驱动的数据富集
利用高质量语料的特征从物理世界、互联网以及语料库中进一步富集更多类似语料
有针对性的数据补齐
针对性补充语料，重点加强世界知识、数理、代码等核心能力

书生浦语2.0（InternLM2）主要亮点

超长上下文：模型在20万token上下文，200k

综合性能全面提升：推理、数学、代码提升显著InternLM2-Chat-20B在重点评测上比肩ChatGPT。

优秀的对话和创作体验：精准指令跟随，丰富的结构化创作，在AlpacaEval2超越GPT3.5和Gemini Pro。

工具调用能力整体升级：可靠支持工具多轮调用，复杂智能体搭建。

突出的数理能力和使用的数据分析功能：强大的内生计算能力（不借助外部计算器），加入代码解释后，在GSM8K和MATH达到和GPT-4相仿水平。

# 性能全方位提升
![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/1e9c247b-fa3f-4dc2-8ec4-457d1554a067)


贴心有可靠的AI助手、充满了人文关怀的对话、富有想象力的创作、工具调用能力升级、强大的内生计算能力、代码解释器：更上一层楼、实用的数据分析功能---->>>智能客服、个人助手、行业应用
思考：手机手环数据与大模型结合，分析个人效率和提高自控能力；
    通过聊天记录，手环数据，消费数据分析心理状态和疲劳程度
接入手机接口，进行自动记账，本地自动行为分析，改善状态
基于大模型的分析手机使用习惯来管理自己手机使用行为
个人会计和法律、医疗助手
![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/ee600386-e1fd-4621-b223-c61630751bd2)

Lora模型
![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/3b30a6e7-c116-47b4-beb7-0f04b9b482ab)

数据集有哪些？文本、图像-文本、视频
评测有题目分哪些类？
Lora低成本微调
应用lagent 和agentlego怎么使用
开放体系
![image](https://github.com/hzsun1995/internlm-season2/assets/136775620/d53c9ade-01b2-489d-af18-71fb53750337)



Xtuner微调框架-是否可以应用到医学图像多任务模型（分割、超分辨率、三维重建）
全量参数微调和部分参数微调


评测--opencompass 2.0，compasskit，compasshub


KIMI性能如何？
视频生成对应的PPT的模型，图像描述？
部署


如何实现零样本的泛化？

轻松玩转书生·浦语大模型趣味 Demo
1.Demo实战
实战部署InternLM2-Chat-1.8B
创建 Intern Studio 开发机，通过 Modelscope 下载 InternLM2-Chat-1.8B 模型，完成 ClientDemo 的部署和交互

是不是可以建立一个requirements.txt,一次性来进行安装
结果截图

