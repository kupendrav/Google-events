# 🚀 AI Agents Development Workshop

**A 5-Day Hands-On Course by Kaggle & Google**

Welcome to the AI Agents Development Workshop! This comprehensive course takes you from building your first AI agent to creating sophisticated multi-agent systems with observability and inter-agent communication.

## 📚 Course Overview

This workshop teaches you how to build intelligent agents using Google's **Agent Development Kit (ADK)** and the **Gemini API**. Through hands-on Jupyter notebooks, you'll learn to create agents that can take actions, use tools, manage memory, and collaborate with other agents.

### What You'll Learn

- ✅ Build AI agents that can take actions beyond simple responses
- ✅ Create and integrate custom tools for your agents
- ✅ Implement memory management and stateful conversations
- ✅ Add observability with logs, traces, and metrics
- ✅ Enable multi-agent communication using the A2A protocol

## 🗓️ Workshop Schedule

### 📅 [Day 1: From Prompt to Action](Day_1a_From_Prompt_to_Action.ipynb)
**Your First AI Agent**

Learn the fundamentals of building AI agents that can do more than just respond to prompts.

**Topics Covered:**
- Setting up your development environment
- Creating your first agent with built-in tools
- Using Google Search integration
- Understanding agent responses and actions

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kupendrav/Google-events/blob/main/Day_1a_From_Prompt_to_Action.ipynb)

**White Paper:** [Introduction to Agents](white-papers/Introduction%20to%20Agents.pdf)

---

### 📅 [Day 2: Agent Tools](Day_2a_Agent_Tools.ipynb)
**Unlocking the Power of Custom Tools**

Transform isolated agents into powerful assistants by building custom tools and integrating external services.

**Topics Covered:**
- Why agents need tools
- Building custom function-based tools
- Delegating to specialized agents
- Tool orchestration and integration
- Working with the Model Context Protocol (MCP)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kupendrav/Google-events/blob/main/Day_2a_Agent_Tools.ipynb)

**White Paper:** [Agent Tools & Interoperability with Model Context Protocol (MCP)](white-papers/Agent%20Tools%20%26%20Interoperability%20with%20Model%20Context%20Protocol%20%28MCP%29.pdf)

---

### 📅 [Day 3: Agent Sessions & Memory](Day_3a_Agent_Sessions.ipynb)
**Building Stateful Agents**

Learn how to give your agents memory so they can maintain context across conversations and interactions.

**Topics Covered:**
- Understanding sessions and events
- Building stateful agents
- Persisting sessions in databases
- Context engineering and memory management
- Long-term vs. short-term memory
- Shared memory across agents

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kupendrav/Google-events/blob/main/Day_3a_Agent_Sessions.ipynb)

**White Paper:** [Context Engineering: Sessions & Memory](white-papers/Context%20Engineering_%20Sessions%20%26%20Memory.pdf)

---

### 📅 [Day 4: Agent Observability](Day_4a_Agent_Observability.ipynb)
**Logs, Traces & Metrics**

Master the art of debugging and monitoring your agents in production environments.

**Topics Covered:**
- What is agent observability?
- Foundational pillars: logs, traces, and metrics
- Implementing logging strategies
- Tracing agent execution flows
- Monitoring agent performance
- Debugging complex agent behaviors

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kupendrav/Google-events/blob/main/Day_4a_Agent_Observability.ipynb)

**White Paper:** [Agent Quality](white-papers/Agent%20Quality.pdf)

---

### 📅 [Day 5: Agent-to-Agent Communication](Day_5a_Agent2Agent_Communication.ipynb)
**Building Multi-Agent Systems**

Create collaborative systems where multiple agents work together to solve complex problems.

**Topics Covered:**
- Overview of Agent2Agent (A2A) protocol
- Building multi-agent architectures
- Inter-agent communication patterns
- Coordinating specialized agents
- Integrating external agent systems

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kupendrav/Google-events/blob/main/Day_5a_Agent2Agent_Communication.ipynb)

**White Paper:** [Prototype to Production](white-papers/Prototype%20to%20Production.pdf)

---

## 🛠️ Prerequisites

Before starting this workshop, you should have:

- **Basic Python Knowledge**: Familiarity with Python programming
- **Kaggle Account**: [Sign up for free](https://www.kaggle.com/) (required for running notebooks)
- **Gemini API Key**: [Create one in Google AI Studio](https://aistudio.google.com/app/api-keys)
- **Account Verification**: Verify your phone number on Kaggle to use the Gemini API

## 🚀 Getting Started

### Option 1: Run on Kaggle (Recommended)

1. Navigate to any day's notebook on Kaggle
2. Click "Copy & Edit" to create your own copy
3. Add your Gemini API key to Kaggle Secrets
4. Start learning!

### Option 2: Run on Google Colab

1. Click the "Open in Colab" badge on any notebook
2. Follow the setup instructions in the notebook
3. Configure your Gemini API key
4. Run the cells sequentially

### Option 3: Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/kupendrav/Google-events.git
   cd Google-events
   ```

2. Install dependencies:
   ```bash
   pip install google-adk google-generativeai
   ```

3. Set your API key:
   ```bash
   export GEMINI_API_KEY='your-api-key-here'
   ```

4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

## 📖 Additional Resources

### White Papers

All workshop white papers are available in the [`white-papers/`](white-papers/) directory:

- [Introduction to Agents](white-papers/Introduction%20to%20Agents.pdf)
- [Agent Tools & Interoperability with MCP](white-papers/Agent%20Tools%20%26%20Interoperability%20with%20Model%20Context%20Protocol%20%28MCP%29.pdf)
- [Context Engineering: Sessions & Memory](white-papers/Context%20Engineering_%20Sessions%20%26%20Memory.pdf)
- [Agent Quality](white-papers/Agent%20Quality.pdf)
- [Prototype to Production](white-papers/Prototype%20to%20Production.pdf)

### Official Documentation

- [Google ADK Documentation](https://google.github.io/adk-docs/)
- [Gemini API Documentation](https://ai.google.dev/gemini-api/docs)
- [Kaggle Notebooks Documentation](https://www.kaggle.com/docs/notebooks)

## 💡 Learning Path

We recommend following the workshop in order:

1. **Day 1** - Build your foundation with basic agent concepts
2. **Day 2** - Expand capabilities with custom tools
3. **Day 3** - Add intelligence with memory and sessions
4. **Day 4** - Ensure reliability with observability
5. **Day 5** - Scale up with multi-agent systems

Each day builds upon the previous lessons, so following this sequence will give you the best learning experience.

## 🎯 What You'll Build

By the end of this workshop, you'll be able to:

- Create production-ready AI agents with custom capabilities
- Implement sophisticated tool integrations
- Build agents that remember context across interactions
- Monitor and debug agent behavior in production
- Design and implement multi-agent collaborative systems

## ❓ FAQ

**Q: Do I need to submit anything?**  
A: No! This is a hands-on learning experience. Work through the notebooks at your own pace.

**Q: Is the Gemini API free?**  
A: Yes, the Gemini API offers a free tier. Check the [pricing page](https://ai.google.dev/pricing) for details.

**Q: Can I modify the notebooks?**  
A: Absolutely! These notebooks are designed for experimentation. Make copies and customize them.

**Q: Where can I get help?**  
A: Check the Kaggle discussion forums or the Google ADK documentation for support.

## 📄 License

Copyright 2025 Google LLC. Licensed under the Apache License, Version 2.0.

---

## 🤝 Contributing

This is a workshop repository. For issues or suggestions, please open an issue in the repository.

---

**Ready to build intelligent agents? Start with [Day 1](Day_1a_From_Prompt_to_Action.ipynb)!** 🚀
