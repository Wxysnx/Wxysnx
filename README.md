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
        self.role = "AI Agent 工程师 | 产品经理"
        self.language_spoken = ["中文", "English"]
        
        # AI 和机器学习技术栈
        self.ai_stack = {
            "智能体框架": ["LangGraph", "CrewAI", "Microsoft AutoGen", "LangChain", "MetaGPT"],
            "大语言模型": ["OpenAI GPT", "Anthropic Claude", "DeepSeek"],
            "RAG技术": ["Agentic RAG", "RecursiveCharacterTextSplitter", "向量化检索", "混合记忆架构"],
            "多模态应用": ["医学影像处理", "BiomedCLIP", "多模态融合算法"],
            "分布式推理": ["vLLM", "Ray Framework"],
            "数据存储": ["ChromaDB", "MongoDB Atlas", "Redis"],
            "后端开发": ["FastAPI", "asyncio", "事件驱动架构"],
            "云原生技术": ["Kubernetes", "Docker", "Kafka"]
        }
        
        # 专业领域
        self.specialties = [
            "多智能体系统设计与实现",
            "LLM应用开发与集成",
            "State Graph 工作流设计",
            "垂直领域AI解决方案",
            "记忆管理系统设计",
            "RAG技术与向量数据库应用",
            "高性能分布式AI系统"
        ]
        
        # 项目经验
        self.projects = {
            "AI记忆增强系统": "基于LangGraph的智能生成式AI记忆管理系统，解决LLM上下文限制问题",
            "CT影像智能分析系统": "基于CrewAI的多智能体医学影像分析系统，为放射科医生提供智能辅助诊断",
            "Agentic RAG系统": "基于LangChain和LangGraph的智能检索增强生成系统，实现动态工作流程",
            "网页内容摘要系统": "基于AutoGen框架的多代理网页内容智能提取系统",
            "自动化股票分析系统": "基于CrewAI的多智能体股票分析工具，集成SEC EDGAR数据分析",
            "对话记忆管理系统": "基于LangGraph的持久化对话代理，实现高效的消息处理和记忆管理"
        }
        
        # 专业优势
        self.strengths = [
            "精通前沿智能体框架，具备复杂多代理系统设计能力",
            "深入理解大语言模型应用与集成技术",
            "将AI Agent技术应用于医疗、金融和内容分析等垂直领域",
            "精通记忆管理系统设计和云原生AI部署",
            "深入理解RAG技术与向量数据库应用"
        ]
    
    def say_hi(self):
        print(f"👋 你好！我是{self.name}，一位{self.role}")
        print("✨ 我专注于LLM、多智能体系统和RAG技术的开发，致力于构建下一代AI应用。")
        print("🚀 我熟练运用LangGraph、CrewAI、AutoGen等前沿智能体框架构建复杂系统。")
        print("🔍 拥有扎实的智能体架构设计经验和垂直领域AI解决方案能力。")
        print("💡 欢迎探索我的项目，或就AI Agent相关技术进行交流！")

me = AIEngineer()
me.say_hi()
