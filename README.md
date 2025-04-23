# 你好，欢迎 👋

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AI](https://img.shields.io/badge/AI-00FFFF?style=for-the-badge&logo=artificial-intelligence&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-11A1F7?style=for-the-badge&logo=openai&logoColor=white)

```python
#!/usr/bin/env python
# -*- coding: utf-8 -*-

class AIEngineer:
    def __init__(self):
        self.name = "王祥宇"
        self.role = "AI agent 工程师 | 产品经理"
        self.language_spoken = ["中文", "English"]
        
        # AI 和机器学习技术栈
        self.ai_stack = {
            "ai agent 框架": ["LangChain", "LangGraph", "AutoGen", "MetaGPT", "CrewAI"],
            "机器学习框架": ["PyTorch", "TensorFlow"],
            "编程语言": ["Python"],
            "Web框架": ["FastAPI"],
            "DevOps": ["Docker"]
        }
        
        # 专业领域
        self.specialties = [
            "LLM应用开发与优化",
            "ai agent 系统构建",
            "AI工作流自动化",
            "机器学习模型部署"
        ]
        
    def say_hi(self):
        print("感谢访问我的主页，我专注于利用最新的AI技术解决实际问题。")
        
me = AIEngineer()
me.say_hi()
